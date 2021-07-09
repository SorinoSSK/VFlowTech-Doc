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
the users to manage devices which send data to the platform. These devices form the 
backbone of the IoT newtwork that will be used for sensing and monitoring any 
infrastructure. In the MADS world, devices which collect data from multiple sensors 
and transmit the data over some communication channel(Wifi, 3G/4G, etc) using a 
communication protcol(HTTP, MQTT, CoAP) are referred to as `gateways`. \
Gateways are digital representation of the physical devices which send data to the
platform. While defining a gateway the user defines all the artifacts which will 
be required for the management and security of the physcial devices provisioned 
for a use case. Gateways in the platform are grouped by their projects.

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
The toplogy feature shows the hierarchy of assets, sensors and gateways. The main idea
behind it is to show the users how the assets and sensors are placed with respect to gateways
in the physical world. \
Assets are the physcial entities being monitored. The assets are monitored with 
the help of sensors, see [Entity Manager]({{<ref "apps/entity-manager/entity-manager/index.md">}}) 
app for more details on how sensors are used to monitor assets. Gateways are used 
for accumulating the sensor data and sending it to the platform. Just like sensors
gateways can be physically associated with an asset, however unlike sensors which 
collect data for only the asset they are attached with, the gateway can be collecting 
data from multiple sensors which might be present on multiple assets.

{{< figure src="GatewayTopology.svg" width="600px" >}}
#### Gateway topology
The gateway topology is defined per project. To see the topology \
1. Click on the topology icon in the left sidebar.\
2. Choose a project.

{{< img-simple src="project-list.png" alt="Project listing" class="border-0 rounded-circle" >}}
3. Expand the tree and click on any gateway to show the sensors it is connected to.
{{< img-simple src="topology-tree.png" alt="Topology Tree" class="border-0 rounded-circle" >}}

## Gateways
The `Gateways` tab shows all the gateways which were created for a project. It also
allows the user to create a new gateway in a project.

To see all the gateways for a project, click on the gateways tab and select the
projects.
{{< img-simple src="project-list-gateway.png" alt="Project List Gateway Tab" class="border-0 rounded-circle" >}}

On clicking on any of the projects you will be able to see the list of gateways in
the project. 
{{< img-simple src="gateway-list.png" alt="Topology Tree" class="border-0 rounded-circle" >}}

The gateways listing shows the following information about gateways: \
  - `Name`: A user identifiable name for the gateway. \
  - `UUID`: A unique identifier for the gateway. \
  - `Channel`: The transport protocol being used by the gateway. \
  - `Status`: The status of the gateway, if it's active or inactive. \
