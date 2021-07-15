---
title: "Editing Dashboards"
description: ""
date: 2021-02-21T14:13:32+08:00
lastmod: 2021-02-21T14:13:32+08:00
draft: false
images: []
menu:
  apps:
    parent: "dashboards"
weight: 5040
toc: true
---

To switch the dashboard in edit mode, just click on the pencil icon present on the dashboard header.
{{< img-simple src="edit-dashboard.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
In edit mode dashboard will look something like below.
{{< img-simple src="edit-mode-dashboard.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
In edit mode, dashboard header options also changes as shown above.
User will not be able to switch to other dashboards in edit mode.

In edit mode, user can perform three actions on dashboard:

* Add New Widget <br/>
* Update a widget <br/>
* Delete a widget

### Add New widget

  To add a widget, user can click on the New widget option present at the right section of the dashboard header.
  {{< img-simple src="new-widget-action.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  After clicking on the new widget action, modal will be opened as shown below.
  {{< img-simple src="new-widget-modal.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  As you can see Add New Widget consists of 3 steps:

  1. Widget: Choosing a widget <br/>
    User can choose a widget from many options and we have categorized the widgets in 4 different ways.
      * Timeseries: These type of widgets are mainly used to plot historical and realtime data.
      {{< img-simple src="timeseries-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

      * Gauge: These type of widgets should be used to display realtime data.
      {{< img-simple src="gauge-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

      * Cards: Card widgets are mainly used to create cards.
      {{< img-simple src="card-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

      * Control
      {{< img-simple src="control-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  1. Data: Connecting sensor parameters to above widget.
    After selecting a widget, user can connect different sensor parameters to the widget from the Organisation Heirarchy tree. <br/>
    This step will not be present in case of Static and Image cards, since these cards will not display any data. If you want to display sensor data in form of card, we have Dynamic card for that purpose. <br/> <br/>
    {{< img-simple src="select-data.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  1. Settings: Configure widget visual and data settings. <br/>
    Once the user is done with selecting sensor parameters, they can configure few settings for better visual display of widgets. <br/>
    User can configure two types of settings for a widget, Visual and Data settings. <br/> <br/>
    Visual settings are mainly used to add title, subtitle, background color and for other visual settings of a widget.
    {{< img-simple src="visual-settings.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
    Data settings are used to configure color and name for a series(sensor parameters which user will select from organisation heirarchy tree).
    {{< img-simple src="data-settings.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  **Let's take an example to create a new widget step by step.**

  As we discussed first step is to choose a widget, we will select a Line Timeseries and then click next.
  {{< img-simple src="select-timeseries.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  After selecting a widget user can connect different sensor parameters to a widget, so let's suppose we want to compare between the power consumption in two Apartments, Apt White 11 and Apt White 12, so we will select the power parameter of these two asset energy meter sensors and then click next.
  {{< img-simple src="select-sensor-params.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Now we are done with connecting data to our widgets, we will add visual and data settings.
  As shown below you can see we have different settings available to configure, for now we will just set the title, subtitle, x axis label and y axis label of the timeseries widget. <br/>

  Set Title
  {{< img-simple src="title-text.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Set Subtitle
  {{< img-simple src="subtitle-text.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  In case of timeseries, by default X Axis label will be Date as shown below, but user can change it.
  {{< img-simple src="x-axis-label.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Set Y Axis label
  {{< img-simple src="y-axis-label.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  On the data settings, we will set the color and name of two different series we have selected as shown below.
  {{< img-simple src="data-settings-values.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  As you can see, for Apt white 11 we have set blue shade color and for Apt white 12 we have set yellow color.

  Once we are done with the settings, we can click on save button and after that new widget will be added to the dasbhoard.
  {{< img-simple src="newly-added-widget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Power consumption widget which we have added now will have some default size, if user want to expand or collpase the size of the widget, it can be done by expanding or collapsing the icon present at the bottom right corner of the widget as shown below.
  {{< img-simple src="expand-widget-size.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  
  On expanding it will be adjusted to the size user want, I have expanded the widget to take the full width and height as shown below.
  {{< img-simple src="expanded-power-consumption-widget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Once user is done with adding widgets, then user can save these changes by clicking on the Save button present at the dashboard header.
  {{< img-simple src="save-dashboard.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  After saving the dashboard, it will be automatically switched to view mode.
  {{< img-simple src="saved-dashboard.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  **Note** <br/>
  On saving a widget, it will be automatically added to the bottom of the other widgets as shown above in the selected tab.
  If you want a widget to be added in other tab, then first user has to switch to other tab and then user can add new widget in that tab.

### Update a widget

  To update an existing widget, first user has to switch the dashboard in edit mode.
  Once the dashboard is in edit mode, existing widget can be updtated by clicking on the pencil icon present at the top right corner of the widget.
  {{< img-simple src="edit-widget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  Let's add one more sensor parameter to the widget, here we are adding power consumption of Apt white 21 as shown below.
  {{< img-simple src="add-sensor-param.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  Also, let's update the backround color of the widget and plot background of the chart as shown below
  {{< img-simple src="update-visual-settings.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  On Saving widget will updated as per the settings we have done as below
  {{< img-simple src="updated-widget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  **Note** <br/>
  User cannot update the type of an existing widget. If user wants to change this, then first delete widget and then create new widget of different type.

### Delete a widget

  User can remove an existing widget on the dashboard by clicking on the dustbin icon present at the top right corner of the widget.
  {{< img-simple src="delete-widget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  User can add more widgets as per the requirements. Below are some of the examples of dashboard.
  {{< img-simple src="dashboard-example1.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  {{< img-simple src="dashboard-example2.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
