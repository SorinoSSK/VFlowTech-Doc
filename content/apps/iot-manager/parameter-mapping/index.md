---
title: "Parameter Mapping"
description: ""
date: 2021-02-21T14:09:34+08:00
lastmod: 2021-02-21T14:09:34+08:00
draft: false
images: []
menu:
  apps:
    parent: "iot-manager"
weight: 4050
toc: true
---

## Overview

Parameter mapping is a very important concept in the IoT Manager app. It allows the user to create isolation between the how the physical devices are sending data and how data is structured in the platform.

Any server ingesting data via HTTP or MQTT, defines a schema in which it expects the data inorder to relate it with the entities created in the system.

{{< figure src="ParameterMapping.svg" width="800px" >}}

The figure above shows how we represent the physical world using a entity hierarchy in the MADS platform, and how a gateway is used to send sensor data from the physical world to the MADS world.

The IoT devices in the real world doesn't always have the flexibility to create a schema desired by the server, it's also not feasible manually to program every device in the field and configure the schema. To cater to this requirement MADS allows the fleixibility to ingest a JSON schema defined by the device. A `payload` sent by a device could take any form. A sample payload can appear like one shown below.

```json
{
  "stringKey": "value1",
  "booleanKey": true,
  "doubleKey": 42.0,
  "longKey": 73,
  "jsonKey": {
    "someNumber": 42,
    "someArray": [1,2,3],
    "someNestedObject": {"key": "value"}
  }
}
```

These keys could be coming from multiple sensor parameters connected to multiple assets. Inorder to give this a structure we need to tell the platform which key is connected to which sensor parameter. See [Entity Manager]({{<ref "apps/entity-manager/entity-manager/index.md">}}) for more details on `sensor types`, `sensors` and `sensor parameters`.

The JSON payload sent has three types of keys:

- `Object Key`: A key which contains multiple keys within it

```language-javascript
{
  "key1": {
      "key2": 1.5,
      "key3": true,
      "key4": "hi"
  }
}
```

- `List Key`: A key which contains values in the form of a list

```language-javascript
{"key": ["value1", 1, true]}
```

- `Value Key`: A key which actually holds a numerical, boolean or string value.

```language-javascript
{"key": 2.7}
```

The value keys are something which are going to be associated with a sensor parameter. Mapping the `keys` in the payload to `sensor parameters` in the system makes it easy to access the data throughout the platform instead of referencing gateway keys. One example is showing the incoming data in the dashboards using widgets. Another example would be referencing sensor parameter keys in Data Cruncher to create user defined data flows for RPA and data transformation.

To create a mapping a tree like interface is provided.
