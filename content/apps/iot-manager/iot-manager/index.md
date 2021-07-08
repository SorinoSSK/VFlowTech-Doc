---
title: "IoT Manager"
description: ""
date: 2021-02-21T14:09:03+08:00
lastmod: 2021-02-21T14:09:03+08:00
draft: false
images: []
menu:
  apps:
    parent: "iot-manager"
weight: 4010
toc: true
---

## Introduction
The IoT Manager app is one of the most essential apps on the platform which allows
the users to manage devices which send data to the platform. These devices form the backbone
of the IoT newtwork that will be used for sensing and monitoring any infrastructure.
In the MADS world, devices which collect data from multiple sensors and transmit the data over some
communication channel(Wifi, 3G/4G, etc) using a communication protcol(HTTP, MQTT, CoAP)
are referred to as `gateways`. 

Gateways are digital representation of the physical devices.
While defining a gateway the user defines all the artifacts which will be required for management
and security of the physcial devices provisioned for a use case.

To use the app look out for the following icon.

{{< img-simple src="iot-manager.png" alt="IoT Manager app" class="border-0 rounded-circle" >}}

You can find it in the appbar as shown below.

{{< img-simple src="iot-manager-in-appbar.png" alt="IoT Manager icon in the appbar" class="border-0 rounded-circle" >}}

Click on this icon to launch the IoT Manager app. The IoT Manager app will open, and default tab is the `Home` tab, as in the image below.

{{< img-simple src="iot-manager-home.png" alt="IoT Manager home" class="border-0 rounded-circle" >}}

In the IoT Manager app, there is a sidebar menu with the following icons.

{{< img-simple src="iot-manager-menu.png" alt="IoT Manager menu" class="border-0 rounded-circle" >}}

The icons mean the following (L to R):

1. [Topology](#topology)
2. [Gateways](#gateways)

## Topology
The toplogy feature shows the network topology of assets, sensors and gateways. It depicts
the hierarchy of assets, sensors and gateways in a project. Assets are the physcial entities being
monitored, the assets are monitored with the help of sensors, see 
[Entity Manager]({{<ref "apps/entity-manager/entity-manager/index.md">}}) app for more details 
about the asset and sensor hierearchy. Just like sensors gateways can be physically associated with an 
asset, however unlike sensors which collect data for only the asset they are attached with, 
the gateway can be collecting data from multiple sensors which might be present on multiple assets.

{{<svg "content/apps/iot-manager/iot-manager/GatewayToplogy.svg">}}

## Gateways

About Gateways
