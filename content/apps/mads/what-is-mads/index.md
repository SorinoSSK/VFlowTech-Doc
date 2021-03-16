---
title: "What is MADS?"
description: ""
date: 2021-02-21T13:28:29+08:00
lastmod: 2021-02-21T13:28:29+08:00
draft: false
images: []
menu:
  apps:
    parent: "mads"
weight: 1030
toc: true
---

MADS is a 100% self-service no-code intuitive IoT platform for rapid implementation of enterprise IoT projects. It enables quick development, management, and scaling of IoT projects. MADS is available both as an on-cloud and on-premises solution.

## Feature Highlights

With MADS you are able to:

* Define your multi-level IoT project hierarchy exactly as in the real world
* Define the relation between your project entities ([assets]({{<ref "/apps/entity-manager/creating-assets">}}) and [sensors]({{<ref "/apps/entity-manager/creating-sensors">}}))
* Provision IoT gateways (devices) for your IoT streaming data
* Collect and visualize data from your assets and sensors
* Perform aggregated trend analytics on historical data
* Analyze incoming sensor data and trigger alarms with customizable event rules
* Design dynamic and responsive dashboards and share them externally
* Enable use-case specific features using customizable stream rules
* And much more ...

## MADS Overview

{{< img-simple src="mads-overview.png" alt="MADS overview" class="border-0 rounded-circle" >}}
MADS overview. [![Enlarge](enlarge.png "Enlarge")](mads-overview.png)

The simplest way to understand the building blocks of an IoT project is:

Hardware → Communication → Software Backend → Applications

The **MADS Core** sits in the *Software Backend* layer, does all the heavy lifting, and interacts with the **MADS Frontend** ie. the *Applications* layer through a set of APIs. We call the combined MADS Core and Frontend experience the MADS Platform. Now talking about the layers below – MADS supports major IoT *Communication* protocols such as HTTPS, MQTT, CoAP, and it agnostic to the IoT *Hardware*, commonly referred to as device or gateway. This means MADS can ingest data from any hardware source (sensors, gateways, devices of any brand, of any output type ie. RS485, 4-20mA, 0-10V, pulse, etc., over any channel ie. WiFi, 3G/4G, LoRaWAN, Sigfox, NB-IoT, Satellite, etc.) as long as they are communicating over the supported protocols (HTTPS, MQTT, CoAP).

The MADS platform consists of multiple blocks responsible for handling different aspects needed to run a complete IoT platform (as shown in the figure below). And one of the most important user-facing blocks is the MADS AppStore. MADS is an app-based platform with a very intuitive OS-like UI.

The apps in the MADS AppStore can be segregated into six categories:

* Core
* Productivity
* Management
* Analytics
* Security
* General

{{< img-simple src="mads-apps.png" alt="MADS apps" class="border-0 rounded-circle" >}}
MADS apps. [![Enlarge](enlarge.png "Enlarge")](mads-apps.png)

As of the publishing of this page, dated 7 March 2021, a total of 32 apps are in our roadmap as shown in the figure above. But currently 10 apps have been released. For details visit the [MADS Apps]({{<ref "/apps/mads/mads-apps">}}) page.

## MADS Characteristics

{{< img-simple src="mads-characteristics.png" alt="MADS characteristics" class="border-0 rounded-circle" >}}
MADS characteristics. [![Enlarge](enlarge.png "Enlarge")](mads-characteristics.png)

MADS is built using the industry's leading software products and best practices followed by some of the leading software companies globally. MADS brings high-performance software engineering to IoT.

## MADS Pillars

{{< img-simple src="mads-pillars.png" alt="MADS pillars" class="border-0 rounded-circle" >}}
MADS pillars. [![Enlarge](enlarge.png "Enlarge")](mads-pillars.png)

The three key pillars of MADS are _analytics_, _scalability_, and _security_.
