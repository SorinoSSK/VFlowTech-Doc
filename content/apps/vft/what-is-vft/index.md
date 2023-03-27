---
title: "What is VFT?"
description: ""
date: 2021-02-21T13:28:29+08:00
lastmod: 2021-02-21T13:28:29+08:00
draft: false
images: []
menu:
  apps:
    parent: "vft"
weight: 1030
toc: true
---

VFT is a 100% self-service no-code intuitive IoT platform for rapid implementation of enterprise IoT projects. It enables quick development, management, and scaling of IoT projects. VFT is available both as an on-cloud and on-premises solution.

## Feature Highlights

With VFT you are able to:

* Define your multi-level IoT project hierarchy exactly as in the real world
* Define the relation between your project entities ([assets]({{<ref "/apps/entity-manager/assets">}}) and [sensors]({{<ref "/apps/entity-manager/sensors">}}))
* Provision IoT gateways (devices) for your IoT streaming data
* Collect and visualize data from your assets and sensors
* Perform aggregated trend analytics on historical data
* Analyze incoming sensor data and trigger alarms with customizable event rules
* Design dynamic and responsive dashboards and share them externally
* Enable use-case specific features using customizable stream rules
* And much more ...

## VFT Overview

{{< img-simple src="vft-overview.png" alt="VFT overview" class="border-0 rounded-circle" >}}
VFT overview. [![Enlarge](enlarge.png "Enlarge")](vft-overview.png)

The simplest way to understand the building blocks of an IoT project is:

Hardware → Communication → Software Backend → Applications

The **VFT Core** sits in the *Software Backend* layer, does all the heavy lifting, and interacts with the **VFT Frontend** ie. the *Applications* layer through a set of APIs. We call the combined VFT Core and Frontend experience the VFT Platform. Now talking about the layers below – VFT supports major IoT *Communication* protocols such as HTTPS, MQTT, CoAP, and it agnostic to the IoT *Hardware*, commonly referred to as device or gateway. This means VFT can ingest data from any hardware source (sensors, gateways, devices of any brand, of any output type ie. RS485, 4-20mA, 0-10V, pulse, etc., over any channel ie. WiFi, 3G/4G, LoRaWAN, Sigfox, NB-IoT, Satellite, etc.) as long as they are communicating over the supported protocols (HTTPS, MQTT, CoAP).

The VFT platform consists of multiple blocks responsible for handling different aspects needed to run a complete IoT platform (as shown in the figure below). And one of the most important user-facing blocks is the VFT AppStore. VFT is an app-based platform with a very intuitive OS-like UI.

The apps in the VFT AppStore can be segregated into six categories:

* Core
* Productivity
* Management
* Analytics
* Security
* General

{{< img-simple src="vft-apps.png" alt="VFT apps" class="border-0 rounded-circle" >}}
VFT apps. [![Enlarge](enlarge.png "Enlarge")](vft-apps.png)

As of the publishing of this page, dated 7 March 2021, a total of 32 apps are in our roadmap as shown in the figure above. But currently 10 apps have been released. For details visit the [VFT Apps]({{<ref "/apps/vft/vft-apps">}}) page.

## VFT Characteristics

{{< img-simple src="vft-characteristics.png" alt="VFT characteristics" class="border-0 rounded-circle" >}}
VFT characteristics. [![Enlarge](enlarge.png "Enlarge")](vft-characteristics.png)

VFT is built using the industry's leading software products and best practices followed by some of the leading software companies globally. VFT brings high-performance software engineering to IoT.

## VFT Pillars

{{< img-simple src="vft-pillars.png" alt="VFT pillars" class="border-0 rounded-circle" >}}
VFT pillars. [![Enlarge](enlarge.png "Enlarge")](vft-pillars.png)

The three key pillars of VFT are _analytics_, _scalability_, and _security_.
