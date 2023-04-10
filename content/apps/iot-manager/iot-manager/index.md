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
<p style="text-align: justify;">
The IoT Manager app is one of the most essential apps on the platform which allows user to manage devices sending data to the platform. These devices form the backbone of the IoT newtwork that will be used for sensing and monitoring any IoT infrastructure. In VFT Energy System, devices collecting data from multiple sensors and transmit them over some communication channel(Wifi, 3G/4G, etc) using a communication protcol(HTTP, MQTT) are referred to as `gateways`.
</p>
<p style="text-align: justify;">
Gateways are digital representation of physical devices which send data to the platform. While defining a gateway, user defines all the artifacts which will be required for the management and security of physcial devices provisioned for a use case. Gateways in VFT Energy System platform are grouped by their projects.
</p>

To use the app look out for the following icon.

{{< img-simple src="iot-manager.png" alt="IoT Manager app" class="border-0 rounded-circle" >}}

You can find it in the appbar as shown below.

{{< img-simple src="iot-manager-in-appbar.png" alt="IoT Manager icon in the appbar" class="border-0 rounded-circle" >}}

Click on this icon to launch the IoT Manager app. The IoT Manager app will open, and default tab is the `Home` tab, as in the image below.

{{< img-simple src="iot-manager-home.png" alt="IoT Manager home" class="border-0 rounded-circle" >}}

In the IoT Manager app, there is a sidebar menu with the following icons.

{{< img-simple src="iot-manager-menu.png" alt="IoT Manager menu" class="border-0 rounded-circle" >}}

The icons mean the following (Left to Right):

1. [Topology](#topology)
2. [Gateways](#gateways)

We can also create the alert rules for the sensor parameters, see [Alert Rule]({{<ref "apps/iot-manager/settings/index.md">}})

## Topology
<p style="text-align: justify;">
The toplogy feature shows the hierarchy of assets, sensors, and gateways. The main ideology behind it is to better display how assets and sensors are placed on the platform with respect to the physical gateways in the actual world. 
</p>

<p style="text-align: justify;">
Assets are the physcial entities and they are monitored with the help of sensors. You may read more about entities in the link below. Gateways are used to retrieve sensor's data and sending them to the platform. Unlike a sensor gateway that retrieve data only from assets it is associated physically with, a gateway can retrieve data from multiple sensors which could be spreaded across different assets.
</p>

[[Entity Manager]]({{<ref "/apps/entity-manager/entity-manager/index.md">}})

{{< figure src="GatewayTopology.svg" width="600px" >}}

### Gateway topology

<p style="text-align: justify;">
The gateway topology is defined per project. To see the topology
</p>

1. Click on the topology icon in the left sidebar.
2. Choose a project.

   {{< img-simple src="project-list.png" alt="Project listing" class="border-0 rounded-circle" >}}

3. Expand the tree and click on any gateway to show the sensors it is connected to.

{{< img-simple src="topology-tree.png" alt="Topology Tree" class="border-0 rounded-circle" >}}

## Gateways
<p style="text-align: justify;">
The `Gateways` tab displays all the gateways which were created in a project. The application also allows users to create new gateway in a project.
</p>
<p style="text-align: justify;">
To view all gateways of a project, click on the gateways tab and select the projects.
</p>

{{< img-simple src="project-list-gateway.png" alt="Project List Gateway Tab" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Upon clicking on any project, you will be able to view the list of gateways in the specific project.
</p>

{{< img-simple src="gateway-list.png" alt="Topology Tree" class="border-0 rounded-circle" >}}

The gateways listing shows the following information about gateways:

- `Name`: A user identifiable name for the gateway.
- `UUID`: A unique identifier for the gateway.
- `Channel`: The transport protocol being used by the gateway.
- `Status`: The status of the gateway, if it's active or inactive.
