---
title: "Glossary"
description: ""
date: 2021-02-21T13:28:54+08:00
lastmod: 2021-02-21T13:28:54+08:00
draft: false
images: []
menu:
  apps:
    parent: "vft-energy-system"
weight: 1070
toc: true
---

Below is a glossary of terms and their definitions used in VFT.

* **Alert**. An alert is an event triggered by some rules defined by a user. Any _app_ can create an alert. An alert is shown on the frontend UI in the form of a notification.

* **Analysis Table**. In the Data Insights app, an analysis table is a table that a user can create by selecting (drag-n-drop) the data fields (metadata or parameters) associated with more or more parent entities (asset or sensor). Think of the analysis table as a multi-dimensional [OLAP cube](https://en.wikipedia.org/wiki/OLAP_cube).

* **Asset** An asset is any physical object or space that is of interest in an IoT project. Examples of assets could be building, ship, factory, solar panel, wind turbine, truck, fridge, motor, pump, generator, inverter, compressor, gearbox, etc. An asset can child other assets below it, thus creating an asset hierarchy. For example `Building > Apartment > Fridge`. An asset can also child sensors below it.

* **Asset Type**. Every asset is created from an asset type. For example, there could be many `motors` labeled `motor-1, motor-2, ...` in a project, but all of those might be coming from the asset type called `motor`. This is done to allow comparison among similar assets belonging to the same asset type.

* **Dashboard**. A dashboard is a virtual space or canvas on which a user can create visualizations by selecting the type of widget they want to display and the associated data source(s). A dashboard can consist of one or more tabs. Dashboards do not belong to any project but are visible across the organization only to users who are allowed access to the Dashboards app of course.

* **Entity**. An entity is an asset or a sensor with distinct and independent existence. Entities always belong to a project. Entities of one project are not visible or accessible to other projects.

* **Entity Map**. An entity map is a visual representation of a project's hierarchy. Every project has one entity map.

* **Gateway**. A gateway is a hardware device which can interface with one or more sensors, collect the sensor data (RS485, 4-20mA, 0-10V, pulse, etc.), and transmit the data over some communication channel (WiFi, 3G/4G, LoRaWAN, Sigfox, NB-IoT, Satellite, etc.) on some communication protocol (HTTPS, MQTT, CoAP).

* **Metadata**. Metadata are fixed attribute values related to any `asset type` or `sensor type`. For example, an asset type `building` could have two metadata: `year of construction` and `number of floors`. When we create an asset of this asset type, we must initialize the metadata fields. If we create an asset called `building-1` then we should (recommended) fill in values in those metadata fields, such as `year of construction = 2010` and `number of floors = 20`. This concept also holds true for sensor types. For example, a sensor type `temperature sensor` could have three metadata: `brand`, `maximum temperature limit`, and `accuracy`. Unlike parameters which are continuous time-series data, metadata are fixed attributes defining an asset or a sensor.

* **Notification**. A notification is a message displayed to the user on the frontend informing them of some event. An example of a notification could be an alert. But there are other types of notifications too. Notifications are shown on the frontend UI as color-coded toast messages – typically _green_ for success, _yellow_ for warning, _red_ for error, _blue_ for info, and _gray_ for custom messages.
{{< img-simple src="notifications.png" alt="Notifications" class="border-0 rounded-circle" >}}

* **Organization** An organization is a group of users who identify themselves under a common banner typically that of a company. An organization must have at least one or more organization admin(s), commonly referred to as org-admin. It can have other users who are members and must be assigned some user roles(s) by the org-admin. An organization can have multiple projects. Projects, entities, gateways, and data of one organization are not accessible to other organizations. So the hierarchy is like `Organization > Project > Entities and Gateways`.

* **Parameter**. Parameters are continuous time-series telemetry values related to any `sensor type`. For example, a sensor type `energy meter` could have five parameters: `voltage`, `current`, `power`, `energy`, and `power factor`. When we create a sensor of this sensor type, the parameter fields get created too. And when the IoT gateway device sends these time-series parameter values, they get stored in the database as time-series data. The interval between the data point could be anything – 1 second, 1 minute, or 1 hour. Unlike metadata which are fixed attributes, parameters are continuous time-series data points associated with a sensor. For how to map the IoT streaming data to the sensor parameters, read [Parameter Mapping]({{<ref "/apps/iot-manager/parameter-mapping">}}).

* **Project**. A project is an isolated space with its own entities (assets and sensors) and gateways. A project belongs to one organization and projects of one organization are not accessible to other organizations. And the entities and gateways of one project are not visible or accessible to other projects, even within to the same organization. So the hierarchy is like `Organization > Project > Entities and Gateways`.

* **Report**. A report is a document that presents information (tables, visualization, images, other data) in an organized format aka. the report template. A report can be created and exported in the Report Wizard app.

* **Sensor**. A sensor is a device to measure some metric in its surroundings which is typically the asset on which the sensor is installed. With respect to the entity map, we can say that the sensor is the child of that asset. Examples of sensors could be temperature sensors, humidity sensors, air quality sensors, energy meters, flow meters, etc. A sensor is always the leaf node in an entity map ie. it can not child any other entity. And a sensor must always have a parent entity that can either be an asset in the project or the project itself. An example of a hierarchy with the sensor being the leaf node is `Building > Apartment > Fridge > Temperature Sensor`.

* **Sensor Type**. Every sensor is created from a sensor type. For example, there could be many `temperature-sensors` labeled `tmpr-1, tmpr-2, ...` in a project, but all of those might be coming from the sensor type called `tmpr`. This is done to allow comparison among similar sensors belonging to the same sensor type.

* **Tab**. A tab is a new space inside a dashboard. In other words, a dashboard is made up of one or more tabs.

* **Task**. A task is a process that will execute at intervals defined by a user. A task is like a _bot_ performing RPA schedules. Tasks can be created in the Data Cruncher app.

* **Topology** A topology is the collapsed version of an entity map.

* **User**. A user is a person who uses the VFT platform.

* **User Role**. Within an organization, the org-admin(s) can define user roles. User roles are associated with permissions ie. which apps and actions are allowed to that user role. When an org-admin adds a new user of type `member`, this new user is assigned one or more user roles. This user's permissions will be the union of the permissions of all the user role they have been assigned to.

* **User Type**. There are three user types: super-admin, org-admin, and member.

  * **Super-admin**. Super-admin is the admin of the entire VFT instance, which can host more than one organization (multi-tenancy). Only the super-admin(s) have access to the Tenant Manager app.

  * **Org-admin**. Org-admin is the admin of a particular organization. Within an organization, the org-admin(s) have all permissions.

  * **Member**. Member is a regular user within an organization. An org-admin can add a member and assign them one or more user roles.

* **Visualization**. A visualization is a widget displaying some data of interest.

* **Widget**. A widget is a form of visualizing data on a chart. Examples of widgets charts are: pie, bar, stacked bar, column, line, area, gauge, doughnut, map, bubble, radar, scatter, comparison, gantt, etc.
{{< img-simple src="widgets.png" alt="Widgets" class="border-0 rounded-circle" >}}
