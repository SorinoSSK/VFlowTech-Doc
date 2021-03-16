---
title: "Glossary"
description: ""
date: 2021-02-21T13:28:54+08:00
lastmod: 2021-02-21T13:28:54+08:00
draft: false
images: []
menu:
  apps:
    parent: "mads"
weight: 1070
toc: true
---

Below is a glossary of terms and their definitions used in MADS.

* **Alert**. An alert is an event triggered by some rules defined by an user. Any _app_ can create an alert. An alert is shown on the frontend UI in the form of a notification.

* **Analysis Table**. In the Data Insights app, an analysis table is a table that a user can create by selecting (drag-n-drop) the data fields (metadata or parameters) associated with more or more parent entities (asset or sensor). Think of the analysis table as a multi-dimensional [OLAP cube](https://en.wikipedia.org/wiki/OLAP_cube).

* Asset

* Asset Type

* Dashboard

* **Entity**. An entity is an asset or sensor with distinct and independent existence.

* **Entity Map**. An entity map is a visual representation of a project's hierarchy. Every project has one entity map.

* **Gateway**. A gateway is a hardware device which can interface with one or more sensors, collect the sensor data (RS485, 4-20mA, 0-10V, pulse, etc.), and transmit the data over some communication channel (WiFi, 3G/4G, LoRaWAN, Sigfox, NB-IoT, Satellite, etc.) on some communication protocol (HTTPS, MQTT, CoAP).

* **Notification**. A notification is a message displayed to the user on the frontend informing them of some event. An example of a notification could be an alert. But there are other types of notifications too. Notifications are shown on the frontend UI as color-coded toast messages – typically _green_ for success, _yellow_ for warning, _red_ for error, _blue_ for info, and _gray_ for custom messages.
{{< img-simple src="notifications.png" alt="Notifications" class="border-0 rounded-circle" >}}

* Organization

* Parameter

* **Project**. A project is an isolated space with its own assets, sensors and gateways.

* Report

* Sensor

* **Sensor Type**.

* **Tab**. A tab is a new space inside a dashboard.

* **Task**. A task is a process that will execute at intervals defined by an user. A task is like a _bot_ performing RPA schedules.

* **Topology** A topology is the collapsed version of an entity map.

* **User**. An user is a person who uses the MADS platform.

* **User Role**. Within an organization, the org-admin(s) can define user roles. User roles are associated with permissions ie. which apps and actions are allowed to that user role. When an org-admin adds a new user of type `member`, this new user is assigned one or more user roles. This user's permissions will be the union of the permissions of all the user role they have been assigned to.

* **User Type**. There are three user types: super-admin, org-admin, and member.

	* **Super-admin**. Super-admin is the admin of the entire MADS instance, which can host more than one organization (multi-tenancy). Only the super-admin(s) have access to the Tenant Manager app.
	* **Org-admin**. Org-admin is the admin of a particular organization. Within an organization, the org-admin(s) have all permissions.
	* **Member**. Member is a regular user within an organization. An org-admin can add a member and assign them one or more user roles.

* **Visualization**. A visualization is a widget displaying some data of interest.

* **Widget**. A widget is a form of visualizing data on a chart. Examples of widgets charts are: pie, bar, stacked bar, column, line, area, gauge, doughnut, map, bubble, radar, scatter, comparison, gantt, etc.
{{< img-simple src="widgets.png" alt="Widgets" class="border-0 rounded-circle" >}}
