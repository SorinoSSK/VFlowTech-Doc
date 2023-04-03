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
<p style="text-align: justify;">
Entity Manager App allows us to design a flexible multi-level project hierarchy which can be mapped to any VFlowTech Energy System use-case.
</p>

<p style="text-align: justify;">
An entity is an asset or a sensor which is distinct and independent VFlowTech Energy System. Entities belong to a project and entities of one project are not visible or accessible to other projects.
</p>

Look out for this icon for the Entity Manager app.

{{< img-simple src="entity-manager.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

You can find the icon in the appbar as shown below.

{{< img-simple src="entity-manager-in-appbar.png" alt="Entity Manager icon in the appbar" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on this icon will launch the Entity Manager app. The Entity Manager app will open, and default tab is the `Home` tab, as in the image below.
</p>

{{< img-simple src="entity-manager-home.png" alt="Entity Manager home" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the Entity Manager app, there is a sidebar menu with the following icons.
</p>

{{< img-simple src="entity-manager-menu.png" alt="Entity Manager menu" class="border-0 rounded-circle" >}}

The icons meant the following (Left to Right):

1. [Entity Map](#entity-map)
2. [Assets](#assets)
3. [Sensors](#sensors)
4. [Activity](#activity)

Things we can do using Entity Manager App:

1. Multi-level assets
2. Custom assets and sensors
3. Custom metadata and parameters
4. Easy interactive entity map UI
5. Custom alert rules, see [Alert Rule]({{<ref "apps/entity-manager/settings/index.md">}})
## Entity Map

<p style="text-align: justify;">
The second tab in Entity Manager app is Entity Map which allows the display of a visual representation of a project's hierarchy. Every project has a unique entity map.
</p>

The icon below denotes Entity Map.

{{< img-simple src="entity-map.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this icon will open Entity Map Tab.

{{< img-simple src="entity-map-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Entity Map tab will open up, and it will display a list of projects in the organisation. We can view the list of project in either <b>grid view</b> or <b>list view</b>.
</p>

{{< img-simple src="projects-grid-view.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

There is a searchbar to quickly seach for projects.

{{< img-simple src="projects-list-view.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on any project to open Entity Map of that project.

{{< img-simple src="entity-map-project-selection.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Entity Map will be opened, containing a map of Entities (Organzation, Project, Sensors and Assets) which can be viewed in either Outline View or Map View. Nested entities can be expanded/collapsed using the gray icon which is present in the bottom left of all the nested entities.
</p>

{{< img-simple src="entity-map-structure.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on any entity will display it's properites on the right sidebar. Entity (Assets, Sensors) details can also be viewed/updated using this sidebar.
</p>

## Assets

Assets is the third tab in Entity Manager app.

<p style="text-align: justify;">
An asset is any physical object or space that is of interest in a VFlowTech Energy System project. Examples of assets could be building, ship, factory, solar panel, wind turbine, truck, fridge, motor, pump, generator, inverter, compressor, gearbox, etc. An asset can child other assets, thus creating an asset hierarchy.
</p>

<p style="text-align: justify;">
For example `Building > Apartment > Fridge`. An asset can also have child sensors below it.
</p>

{{< img-simple src="assets.png" alt="Assets" class="border-0 rounded-circle" >}}

Clicking on this icon will open Assets Tab.

{{< img-simple src="assets-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Assets tab will open up, and it will display a list projects within the organization which can be viewed in either <b>grid view</b> or <b>list view</b>.
</p> 

[(Similar to projects shown in Entity Map)](#entity-map).

{{< img-simple src="asset-project-selection.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Click on any project to view assets of the project. The page contains two tabs, Assets and Asset Types.
</p>

{{< img-simple src="asset-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Assets contains an assets list along with their Names, Asset Types, Metadata and Actions. In the <b>Actions</b> column, we have the option to edit, delete, view and duplicate assets. There is also a search bar to search for assets.
</p>

{{< img-simple src="asset-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
At the top right corner of Assets list there is a button to add asset. Clicking on <b>Add Asset</b> button will open an add asset modal, using which we can use to add Assets. 
</p>

[[Read more in Creating an Assets section]]({{<ref "/apps/entity-manager/assets">}})

{{< img-simple src="asset-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
The second tab is the <b>Asset Types</b> which contains a list of asset type along with their Names, Metdata and Actions. Similar to Assets, there is also a search bar to search for asset types.
</p>

{{< img-simple src="asset-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
At the top right corner of Asset Types, there is a button to add asset type. Clicking on <b>Add Asset Type</b> button will open an add asset type modal, which we can use to add <b>Asset Type</b>.
</p>

## Sensors

Sensors is the fourth tab in Entity Manager app.

<p style="text-align: justify;">
A sensor is a device to measure details of its surroundings which is a device installed in an asset. With respect to the entity map, we could define that the sensor is the child of that asset.
</p>

<p style="text-align: justify;">
An examples of sensors could be temperature sensors, humidity sensors, air quality sensors, energy meters, flow meters, etc. A sensor is always a leaf node in an entity map ie. it can not child any other entity. And a sensor must always have a parent entity that can either be an asset in the project or the project itself.
</p>

An example of a hierarchy with the sensor being the leaf node is `Building > Apartment > Fridge > Temperature Sensor`.

{{< img-simple src="sensors.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Click on this icon to open Sensors Tab.

{{< img-simple src="sensors-tab.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Sensors tab will open up, and it will display all projects within the organisation which can be viewed in either <b>Grid view</b> or <b>List view</b>.
</p>

[(Similar to projects shown in Entity Map)](#entity-map).

{{< img-simple src="sensor-project-selection.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Click on any project to view the list of sensors within the project. The sensor tab contains two sub tabs, Sensors and Sensor Types.
</p>

{{< img-simple src="sensor-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Sensors contain a list of sensors along with their Names, Sensor Types, Metadata, Parameters and Actions. In the Actions column, we have the option to edit, delete, view and duplicate sensors. There is also a search bar to search for sensors.
</p>

{{< img-simple src="sensor-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
At the top right corner of sensors list, there is a button to add sensor. Clicking on <b>Add Sensor</b> button will open an add sensor modal, which we can use to add Sensors. 
</p>

[[Read more in Creating a Sensors section]]({{<ref "/apps/entity-manager/sensors">}})

{{< img-simple src="sensor-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
The second tab is Sensor Types which contains a list of sensor type along with their Names, Metdata, Paramters and Actions. Similar to sensors, there is also a search bar to search for sensor types.
</p>

{{< img-simple src="sensor-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
On the top right of Sensor Types list there is a button to add sensor type. Clicking on <b>Add Sensor Type</b> button will open an add sensor type modal, which we can use to add Sensor Type.
</p>