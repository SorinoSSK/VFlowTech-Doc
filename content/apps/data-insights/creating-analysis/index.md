---
title: "Creating Analysis"
description: ""
date: 2021-02-21T14:47:32+08:00
lastmod: 2021-02-21T14:47:32+08:00
draft: false
images: []
menu:
  apps:
    parent: "data-insights"
weight: 7020
toc: true
---

## Overview
Inorder to create visualizations, user needs to create analysis table in the Data Insights app. Analysis table is the central data-source with multiple columns, that serves as the base table for generating different types of visualuzations. So, we can say that analysis table can have multiple visualizations.

#### Create an Analysis Table
To create analysis table, navigate to the analysis listing page. On this page, on the right side you'll find Add Analysis Table, upon clicking on this button a model'll appear to fill in the analysis table name

{{< img-simple src="analysis-table-create.png" alt="Analysis Table Create" class="border-0 rounded-circle" >}}

Upon clicking on save button, an analysis table will be created with the specified name, and user'll be redirected to the Analysis Page

{{< img-simple src="analysis-table-show.png" alt="Analysis Table Show" class="border-0 rounded-circle" >}}

This page is divided into components:
1. Left Section
2. Right Section

Left Section shows entities of the project, which is again divided into two components(user can scroll and check):
1. Asset Type List
2. Sensor Type List
3. Show Topology

##### Asset Type List
{{< img-simple src="analysis-table-left-asset.png" alt="Analysis Table Show" class="border-0 rounded-circle" >}}

##### Sensor Type List
{{< img-simple src="analysis-table-left-sensor.png" alt="Analysis Table Show" class="border-0 rounded-circle" >}}

##### Show Topology
On clicking Show Topology button, shows the hierarchy of entities like asset_types and sensor_types. The main idea
behind it is to show the users connection between all the asset_types and the sensor_types of the project in the physical world.

On clicking Show Topology button, topology modal'll open like this:

{{< img-simple src="show-topology.png" alt="Show Topology" class="border-0 rounded-circle" >}}

Right Section consists of the columns placeholder, where user can drag and drop asset-types and sensor-types's metadata from the left side, doing so will look something like this:

{{< img-simple src="column-metadata.png" alt="Column Metadata" class="border-0 rounded-circle" >}}

After user has dragged and dropped the entities, they need to click on the Build button to generate the data.

{{< img-simple src="table-data.png" alt="Analysis Table With Data" class="border-0 rounded-circle" >}}

So, in this way our analysis table gets populated with data. There is one more thing user can do, they can add more columns or reduce columns, but they have to again click on the Build button after making such changes.