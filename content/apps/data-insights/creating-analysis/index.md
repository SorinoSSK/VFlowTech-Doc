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

<p style="text-align: justify;">
In order to create visualizations, users have to create an analysis table within the Data Insights app. Analysis table is the central data-source containing multiple columns, that serves as the base table for generating different types of visualuzations. Therefore, we can declare that an analysis table can contain multiple visualizations.
</p>

### Create an Analysis Table

<p style="text-align: justify;">
To create an analysis table, navigate to the analysis listing page. On the right side of this page, you will find <b>Add Analysis Table</b>. Upon clicking on this button, a model will be displayed and users have to enter the name of the analysis table.
</p>

{{< img-simple src="analysis-table-create.png" alt="Analysis Table Create" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Upon clicking on save button, an analysis table will be created and user will be redirected to the Analysis Page.
</p>

{{< img-simple src="analysis-table-show.png" alt="Analysis Table Show" class="border-0 rounded-circle" >}}

This page is divided into components:

1. Left Section
2. Right Section

Left Section shows entities of the project, which is again divided into two components(user can scroll and check):

1. Asset Type List
2. Sensor Type List
3. Show Topology

#### Asset Type List

{{< img-simple src="analysis-table-left-asset.png" alt="Analysis Table Show" class="border-0 rounded-circle" >}}

#### Sensor Type List

{{< img-simple src="analysis-table-left-sensor.png" alt="Analysis Table Show" class="border-0 rounded-circle" >}}

#### Show Topology

<p style="text-align: justify;">
Upon clicking on <b>Show Topology</b> button, the hierarchy of entities like asset_types and sensor_types will be displayed. The main idea behind this is to show the connection between all the asset_types and the sensor_types of the project in the physical world.
</p>

<p style="text-align: justify;">
Upon clicking on <b>Show Topology</b> button, topology modal will be opened as shown below.
</p>

{{< img-simple src="show-topology.png" alt="Show Topology" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Right Section consists of the columns placeholder, where user can drag and drop asset-types and sensor-types's metadata from the left side, doing so will look something like this:
</p>

{{< img-simple src="column-metadata.png" alt="Column Metadata" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
After user has dragged and dropped the entities, they need to click on the Build button to generate the data.
</p>

{{< img-simple src="table-data.png" alt="Analysis Table With Data" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Thus the analysis table will be populated with data. There is one more thing user can do, they can add more columns or reduce columns, but they have to again click on the Build button after making such changes.
</p>
