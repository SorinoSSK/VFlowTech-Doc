---
title: "Creating Gateways"
description: ""
date: 2021-02-21T14:09:17+08:00
lastmod: 2021-02-21T14:09:17+08:00
draft: false
images: []
menu:
  apps:
    parent: "iot-manager"
weight: 4020
toc: true
---

## Overview

Inorder to connect a physical device and send data to the platform we need to create a gateway in the IoT manager app. The gateway is a digital representation of the physical device. The gateway creates a unique identity for the device sending the data, and defines the credentials which will be used to connect to the platform. The gateway holds all the information for the device including its status(active/inactive)\

### Create a Gateway

To create a gateway navigate to the gateway listing page for a project.\
`Gateways` -> `Project`

On the listing page click on add gateway button to add a new gateway

{{< img-simple src="add-gateway.png" alt="Topology Tree" class="border-0 rounded-circle" >}}

Upon clicking a modal appears to fill in the details for the gateway

{{< img-simple src="gateway-add-modal1.png" alt="Topology Tree" class="border-0 rounded-circle" >}}

{{< img-simple src="gateway-add-modal2.png" alt="Topology Tree" class="border-0 rounded-circle" >}}

- The first step is to add an identifiable name for the gateway. \
- The second step is to choose the channel over which data will be sent. The current
supported channels are: \
  - MQTT
  - HTTP

- The user can then select the position where they want to place the gateway. The
    position can be any asset or the project.

After creating a gateway you can open it to see the more infomration about the gateway. See [Gateway Details]({{<ref "apps/iot-manager/gateway-details/index.md">}}) page for more info.

{{< img-simple src="gateway-details-action.png" alt="Topology Tree" class="border-0 rounded-circle" >}}
