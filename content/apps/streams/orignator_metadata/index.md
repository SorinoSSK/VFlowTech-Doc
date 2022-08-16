---
title: "Orignator Metadata"
description: ""
date: 2022-08-13T08:32:06+05:30
lastmod: 2022-08-13T08:32:06+05:30
draft: false
menu:
  apps:
    parent: "streams"
weight: 1015
images: []
---

Orignator Metadata action node can be used to load gateway metadata and append it in the payload.
This action loads following metadata of gateway:
- Gateway static data
- Gateway current location
- Gateway name
- Gateway status

### Action Fields

#### Name
Name field can be used to give custom name to the node.

#### Destination
Destination is the path in the payload where the metadata should be appended.

Example:
Let's say we have following metadata of gateway

```json
{
    "name": chiller_room_gateway,
    "status": active
}
```

We wanted it as follows in the payload:

```json
{
    "chillers": {
        "ice_section": {
            "name": chiller_room_gateway,
            "status": active
        }
    }
}
```

We will write destination as `chillers.ice_section`.
The keys will be separated by `.`.