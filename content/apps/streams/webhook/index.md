---
title: "Webhook"
description: ""
date: 2022-08-13T08:32:06+05:30
lastmod: 2022-08-13T08:32:06+05:30
draft: false
menu:
  apps:
    parent: "streams"
weight: 1014
images: []
---

<p style="text-align: justify;">
Webhook node is used to call external Rest API and the response can be appended in the payload.
</p>

### Action Fields

#### Name
<p style="text-align: justify;">
Name field can be used to give a custom name to the node.
</p>

#### URL
<p style="text-align: justify;">
The API URL that needs to be called.
</p>

#### HTTP Method
Select the HTTP method of the API from the drop down menu.
Available options are:
- PUT
- POST
- PATCH
- GET

#### Headers
Add headers as JSON object in the header input field.

#### Body
<p style="text-align: justify;">
If you require to pass a body in the API call, you can add it as stringfied JSON in this field. The stringfied JSON will be sent as body when the API is called.
</p>

#### Destination
Destination is the path in the payload where the API response should be appended.

Example:
Let's say we got following API response

```json
{
    "temperature": 30
}
```

We wanted it as follows in the payload:

```json
{
    "machine_1": {
        "parameters": {
            "temperature": 30
        }
    }
}
```

We will write destination as `machine_1.parameters`.
The keys will be separated by `.`.