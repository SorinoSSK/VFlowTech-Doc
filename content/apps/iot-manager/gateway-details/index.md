---
title: "Gateway Details"
description: ""
date: 2021-02-21T14:09:17+08:00
lastmod: 2021-02-21T14:09:17+08:00
draft: false
images: []
menu:
  apps:
    parent: "iot-manager"
weight: 4040
toc: true
---

## Overview

The gateway details page provides all the information about provisioning a gateway in the field and making it ready for sending data to the platform.

{{< img-simple src="gateway-detail.png" alt="Gateway Detail" class="border-0 rounded-circle" >}}

It has the following tabs from __L__ to __R__

- Details
- Parameter
- Parameter Mapping
- Commands
- Latest Logs
- Sensors

### Details

The details page shows the information which may be required for connecting a device to the platform. While creating a gateway the user can chosse what channel(HTTP/MQTT) to use for sending the data.

The details page shows channel specific information. If the channel is HTTP then

{{< img-simple src="gateway-detail-http.png" alt="Gateway Detail" class="border-0 rounded-circle" >}}

It shows the `URL` info and the `Bearer token` which will be used to send the data to the platform. You can make a `POST` request with the payload to send data to the platform.

In case the channel is MQTT then

{{< img-simple src="gateway-detail-mqtt.png" alt="Gateway Detail" class="border-0 rounded-circle" >}}

It shows the following information for `publishing` data to the platform.

- Hostname
- Port
- ClientID
- Username
- Password
- Topic

### Parameter

The parameters tab helps to set `static` and `dynamic` parameters for a gateway.

- `Static parameters`: Static parameters are key-value pairs which define certain properties of the gateway and won't change. They can be modified by the user itself. Examples of static parameters are `model`, `make`, `serial numbers` etc. for identifiying the gateway.
- `Dynamic parameters`: Dynamic parameters are device parameters which will be sent by the gateway in the payload. Please keep in mind these parameters are different from sensor parameters. These parameters are usually related to gateway for example `battery level`, `cpu usage`, `memory usage`, `device temperature` etc.

{{< img-simple src="gateway-detail-parameter.png" alt="Gateway parameters" class="border-0 rounded-circle" >}}

### Parameter Mapping

The parameter mapping is a very important feature which allows to create a mapping between the incoming JSON payload and the sensor parameters in the system. Parameter gives a structure way incoming data is stored in the platform. Detailed information is provided about this feature on the [Parameter Mapping]({{<ref "/apps/iot-manager/parameter-mapping">}}) document.

{{< img-simple src="gateway-detail-parameter-mapping.png" alt="Parameter Mapping" class="border-0 rounded-circle" >}}

### Latest Logs

The Latest logs shows all the data which is coming from the sensors in the JSON format. Latest logs contains logs and errors.
We can see the realtime logs and errors in every 5 seconds if we turn on `auto-sync` option as per the selected timeframe

{{< img-simple src="gateway-details-latest-log.png" alt="Latest logs" class="border-0 rounded-circle" >}}

### Sensor

The sensor page shows all the sensors connected to the gateway. The connected sensors are automatically inferred from the parameter mapping page. All the sensors whose parameters are mapped to a gateway are considered connected to the gateway. See [Parameter Mapping]({{<ref "/apps/iot-manager/parameter-mapping">}}) for detailed info.

{{< img-simple src="gateway-sensors.png" alt="Gateway Sensors" class="border-0 rounded-circle" >}}
