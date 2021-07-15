---
title: "Data Insights"
description: ""
date: 2021-02-21T14:47:20+08:00
lastmod: 2021-02-21T14:47:20+08:00
draft: false
images: []
menu:
  apps:
    parent: "data-insights"
weight: 7010
toc: true
---

## Introduction

The DataInsights app is the one which is responsible for aggregated data analytics and visualisation, historical trends or future forecasts of IoT data. Using this app, we gather data, then transform them into something useful which can be presented visually so that the user can interpret about what data is telling. Also, we store these visual representations created by user so that they can refer it in the future, if they wants to access it again.

To use the app look out for the following icon

{{< img-simple src="data-insights.png" alt="Data Insights app" class="border-0 rounded-circle" >}}

You can find it in the appbar as shown below.

{{< img-simple src="data-insights-in-appbar.png" alt="Data Insights icon in the appbar" class="border-0 rounded-circle" >}}

Click on this icon to launch the Data Insights app. The Data Insights app will open, and default tab is the `Home` tab, as in the image below.

{{< img-simple src="data-insights-home.png" alt="Data Insights home" class="border-0 rounded-circle" >}}

In the Data Insights app, there is a sidebar menu with the following icon.

{{< img-simple src="data-insights-menu.png" alt="Data Insights menu" class="border-0 rounded-circle" >}}

The icons mean the following (L to R):

1. [Analyzer](#analyzer)

## Analyzer

Analyzer is where user creates analysis table using data-source(database) and then on the basis of the analysis table, they can create visualizations for visual representations of data.

In order to proceed, user first has to choose respective project like this:
1. Click on the Analyzer icon in the left sidebar
2. Choose a project

{{< img-simple src="project_listing.png" alt="Project listing" class="border-0 rounded-circle" >}}

All the Analysis and visualuzations are grouped on the basis of project, so in order to do analysis user has to select respective project.

On clicking any of the projects you will be able to see list of analysis tables in the project like below

{{< img-simple src="analysis-table-list.png" alt="Analysis Table listing" class="border-0 rounded-circle" >}}

Analysis Table listing shows the following information about Analysis Table:
  - `Analysis Table`: Name of the analysis table
  - `Made By`: Analysis Table's creator name
  - `Visualizations`: Total number of visual representations created from the respective analysis table 
  - `Made on`: Analysis Table's creation date
