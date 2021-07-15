---
title: "Entity Manager"
description: ""
date: 2021-02-21T14:05:46+08:00
lastmod: 2021-02-21T14:05:46+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3010
toc: true
---

## Introduction

Entity Manager App helps us in designing a flexible multi-level project hierarchy which can be mapped to any real-world IoT use-case.

An entity is basically an asset or a sensor with distinct and independent existence. Entities always belong to a project. Entities of one project are not visible or accessible to other projects.

Look out for this icon for the Entity Manager app.

{{< img-simple src="entity-manager.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

You can find it in the appbar as shown below.

{{< img-simple src="entity-manager-in-appbar.png" alt="Entity Manager icon in the appbar" class="border-0 rounded-circle" >}}

Click on this icon to launch the Entity Manager app. The Entity Manager app will open, and default tab is the `Home` tab, as in the image below.

{{< img-simple src="entity-manager-home.png" alt="Entity Manager home" class="border-0 rounded-circle" >}}

In the Entity Manager app, there is a sidebar menu with the following icons.

{{< img-simple src="entity-manager-menu.png" alt="Entity Manager menu" class="border-0 rounded-circle" >}}

The icons mean the following (L to R):

1. [Entity Map](#entity-map)
2. [Assets](#assets)
3. [Sensors](#sensors)
4. [Activity](#activity)

Things we can do using Entity Manager App:

1) Multi-level assets
2) Custom assets and sensors
3) Custom metadata and parameters
4) Easy interactive entity map UI

## Entity Map

The second tab in Entity Manager app is Entity Map which is a visual representation of a project's hierarchy. Every project has one entity map.

Below icon denotes Entity Map.

{{< img-simple src="entity-map.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on this icon to open Entity Map Tab.

{{< img-simple src="entity-map-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Entity Map tab will open up, and it'll show all the projects of the organization which can be viewed in either Grid view or List view.

{{< img-simple src="projects-grid-view.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

There is a searchbar to quickly seach for projects.

{{< img-simple src="projects-list-view.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on any project to open Entity Map of that project.

{{< img-simple src="entity-map-project-selection.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Entity Map will open which contains a map of Entities (Organzation, Project, Sensors and Assets) which can be viewed in Outline View or Map View. The nested entities can be expanded/collapsed using the gray icon which is present in the bottom left of all the nested entities.

{{< img-simple src="entity-map-structure.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on any entity will show it's properites in the right sidebar. Entity (Assets, Sensors) details can also be viewed/updated using this sidebar.

## Assets

Assets is the third tab in Entity Manager app.

An asset is any physical object or space that is of interest in an IoT project. Examples of assets could be building, ship, factory, solar panel, wind turbine, truck, fridge, motor, pump, generator, inverter, compressor, gearbox, etc. An asset can child other assets below it, thus creating an asset hierarchy.

For example `Building > Apartment > Fridge`. An asset can also have child sensors below it.

{{< img-simple src="assets.png" alt="Assets" class="border-0 rounded-circle" >}}

Click on this icon to open Assets Tab.

{{< img-simple src="assets-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Assets tab will open up, and it'll show all the projects of the organization which can be viewed in either Grid view or List view (Similar to projects shown in Entity Map).

{{< img-simple src="asset-project-selection.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on any project to open Assets of that project. It contains two tabs, Assets and Asset Types.

{{< img-simple src="asset-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Assets contains the assets list with their Names, Asset Types, Metadata and Actions. In the Actions column, we have options to edit, delete, view and duplicate assets. There is a search bar to search for assets.

{{< img-simple src="asset-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

On the top right of Assets list there is a button to Add asset. Clicking on that button will open an Add Asset modal, using which we can add Assets. (Discussed in Creating Assets section)

{{< img-simple src="asset-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

The second tab is Asset Types which contains the asset type list with their Names, Metdata and Actions. Similar to Assets, there is a search bar to search for asset types.

{{< img-simple src="asset-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

On the top right of Asset Types list there is a button to Add asset type. Clicking on that button will open an Add Asset Type modal, using which we can add Asset Type.

## Sensors

Sensors is the fourth tab in Entity Manager app.

A sensor is a device to measure some metric in its surroundings which is typically the asset on which the sensor is installed. With respect to the entity map, we can say that the sensor is the child of that asset.

Examples of sensors could be temperature sensors, humidity sensors, air quality sensors, energy meters, flow meters, etc. A sensor is always the leaf node in an entity map ie. it can not child any other entity. And a sensor must always have a parent entity that can either be an asset in the project or the project itself.

An example of a hierarchy with the sensor being the leaf node is `Building > Apartment > Fridge > Temperature Sensor`.

{{< img-simple src="sensors.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on this icon to open Sensors Tab.

{{< img-simple src="sensors-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Sensors tab will open up, and it'll show all the projects of the organization which can be viewed in either Grid view or List view. (Similar to projects shown in Entity Map).

{{< img-simple src="sensor-project-selection.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on any project to open Sensors of that project. It contains two tabs, Sensors and Sensor Types.

{{< img-simple src="sensor-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Sensors contains the sensors list with their Names, Sensor Types, Metadata, Parameters and Actions. In the Actions column, we have options to edit, delete, view and duplicate sensors. There is a search bar to search for sensors.

{{< img-simple src="sensor-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

On the top right of Sensors list there is a button to Add Sensor. Clicking on that button will open an Add Sensor modal, using which we can add Sensors. (Discussed in Creating Sensors section)

{{< img-simple src="sensor-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

The second tab is Sensor Types which contains the sensor type list with their Names, Metdata, Paramters and Actions. Similar to Sensors, there is a search bar to search for sensor types.

{{< img-simple src="sensor-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

On the top right of Sensor Types list there is a button to Add sensor type. Clicking on that button will open an Add Sensor Type modal, using which we can add Sensor Type.

## Activity

Activity is the fifth tab in Entity Manager app.

{{< img-simple src="activity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on this icon to open Activity Tab.

{{< img-simple src="activity-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}
