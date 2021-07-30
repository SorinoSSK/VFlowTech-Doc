---
title: "Exporting Visualisation"
description: ""
date: 2021-02-21T14:47:58+08:00
lastmod: 2021-02-21T14:47:58+08:00
draft: false
images: []
menu:
  apps:
    parent: "data-insights"
weight: 7040
toc: true
---

## Overview

It is possible to export the created visualization to the dashboard using export visualization feature.

### Exporting Visualization

To export any Visualization, click on the `Export` button:

{{< img-simple src="export-button.png" alt="Export Visulization" class="border-0 rounded-circle" >}}

Upon clicking on `Export` button, `Export Widget` modal will open like this:

{{< img-simple src="export-widget.png" alt="Export Widget" class="border-0 rounded-circle" >}}

Export Widget modal has following fields which user needs to fill:

- `Title`: Title of the widget, which will be shown on dashboard
- `Description`: Description of the widget which will be shown on dashboard
- `Dashboard`: User needs to select from available dashboards, where this visualization will be exported
- `Panel`: User needs to select from panels of the above selected dashboard

User needs to select a dashboard from dropdown of all available dashboards, where the respective visualiuzation gets exported as widget. Also, they have to choose a panel from the available panels of the selected dashboard.

{{< img-simple src="dashboard-dropdown.png" alt="Dashboard Dropdown" class="border-0 rounded-circle" >}}

{{< img-simple src="panel-dropdown.png" alt="Panel Dropdown" class="border-0 rounded-circle" >}}

So, this is how the final modal will look, if user fills all the information to export:

{{< img-simple src="exported-details.png" alt="Exported Details" class="border-0 rounded-circle" >}}

Upon clicking on `Save` button, respective visualization will gets exported to the panel of the selected dashboard.

User can go to `dashboards` app and choose the respective dashboard and verify if visualization is exported or not.

{{< img-simple src="exported-to-dashboard.png" alt="Exported to Dashboard" class="border-0 rounded-circle" >}}
