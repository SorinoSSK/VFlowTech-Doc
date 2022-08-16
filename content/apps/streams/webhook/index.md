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

Webhook node can be used to call external Rest API and the response can be appended in the payload.

### Action Fields

#### Name
Name field can be used to give custom name to the node.

#### URL
The API URL that needs to be called.

#### HTTP Method
Select the HTTP method of the API from the dropdown.
Available options are:
- PUT
- POST
- PATCH
- GET

#### Headers
Add headers as JSON object in the header input field.

#### Body
If you want to pass body in the API call, add it as stringfied JSON in this field,
it will be sent as body when calling the API.

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