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
  After clicking on the new widget action, right sidebar will be opened as shown below.
  {{< img-simple src="right-sidebar.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  As you can see Add New Widget consists of 3 steps:

  1. Widget: Choosing a widget <br/>
    User can choose a widget from many options and we have categorized the widgets in 4 different ways.
      * Timeseries: These type of widgets are mainly used to plot historical and realtime data.
      {{< img-simple src="timeseries-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

      * Gauge: These type of widgets should be used to display realtime data.
      {{< img-simple src="gauge-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

      * Cards: Card widgets are mainly used to create cards.
      {{< img-simple src="card-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

      * Consumption
      {{< img-simple src="consumption-widgets.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  1. Data: Connecting sensor parameters to above widget.
    After selecting a widget, user can connect different sensor parameters to the widget from the Organisation Heirarchy tree. <br/>
    This step will not be present in case of Static and Image cards, since these cards will not display any data. If you want to display sensor data in form of card, we have Dynamic card for that purpose. <br/> <br/>
    Once you select the widget, below screen will be visible. Click on Choose Data button <br/>
    {{< img-simple src="sensorData.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
    Then select the desired sensors <br/>
    {{< img-simple src="selectNode.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  1. Settings: Configure widget visual and data settings. <br/>
    Once the user is done with selecting sensor parameters, they can configure few settings for better visual display of widgets. <br/>
    Visual settings are mainly used to add title, background color and for other visual settings of a widget.<br/>
    {{< img-simple src="visualSettings.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  **Let's take an example to create a new widget step by step.**

  As we discussed first step is to choose a widget, we will select a Line Timeseries and then click next. <br/>
  {{< img-simple src="lineTimeSeries.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  After selecting a widget user can connect different sensor parameters to a widget, so let's suppose we want to compare between the power consumption in two Apartments, Apt Red 11 and Apt Red 12, so we will select the voltage parameter of these two asset energy meter sensors and then click next.
  {{< img-simple src="selectNode.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Now we are done with connecting data to our widgets, we will add visual and data settings.
  As shown below you can see we have different settings available to configure, for now we will just set the title, subtitle, x axis label and y axis label of the timeseries widget. <br/>

  Set Title <br/>
  {{< img-simple src="widgetTitle.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Title Text Formatting <br/>
  {{< img-simple src="formatting.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Set Background Color<br/>
  {{< img-simple src="selectBgColor.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  In case of timeseries, by default X Axis label will be Date as shown below, but user can change it.<br/>
  {{< img-simple src="xAxis.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Set Y Axis label<br/>
  {{< img-simple src="yAxis.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Add Range (Optional) <br/>
  If we need colored bands on our charts then this option is usefull, user can plot multiple band by adding multiple ranges. <br/>  
  User can change the range from, and range to and also change the color of the range band. <br/>
  {{< img-simple src="yAxisThreshold.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Range Error<br/>
  If user accidently add to value lower then from value this kind of error will be shown to the user <br/>
  Range To value is always be greather then range from value, Once user correct the range the error will be disappear. <br/>
  {{< img-simple src="yAxisThresholdError.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  In the legend settings, we will set the color and name of two different series we have selected as shown below.<br/>
  {{< img-simple src="legendSettings.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  As you can see, for Apt red 11 we have set blue shade color and for Apt red 12 we have set green color.

  Once we are done with the settings, we can click on apply button and after that new widget will be added to the dasbhoard.
  {{< img-simple src="newWidget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Power consumption widget which we have added now will have some default size, if user want to expand or collpase the size of the widget, it can be done by expanding or collapsing the icon present at the bottom right corner of the widget as shown below.
  {{< img-simple src="widgetSize.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  
  On expanding it will be adjusted to the size user want, I have expanded the widget to take the full width and height as shown below.
  {{< img-simple src="expandedWidget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  Once user is done with adding widgets, then user can save these changes by clicking on the Save button present at the dashboard header.
  {{< img-simple src="saveDashboard.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  After saving the dashboard, it will be automatically switched to view mode.
  {{< img-simple src="savedDashboard.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  **Note** <br/>
  On saving a widget, it will be automatically added to the bottom of the other widgets as shown above in the selected tab.
  If you want a widget to be added in other tab, then first user has to switch to other tab and then user can add new widget in that tab.

### Update a widget

  To update an existing widget, first user has to switch the dashboard in edit mode.
  Once the dashboard is in edit mode, existing widget can be updtated by clicking on the pencil icon present at the top right corner of the widget. <br/>
  {{< img-simple src="editWidget.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
  To Edit sensor data, Click on edit icon shown in below image <br/>
  {{< img-simple src="sensorEdit.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
  Let's add one more sensor parameter to the widget, here we are adding voltage of Apt red 11 as shown below. <br/>
  {{< img-simple src="addSensor.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
  Also, let's update the backround color of the widget as shown below <br/>
  {{< img-simple src="bgChange.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>
  On Saving widget will updated as per the settings we have done as below <br/>
  {{< img-simple src="updatedWidget.png" alt="Dashboards app" class="border-0 rounded-circle" >}} <br/>

  **Note** <br/>
  User cannot update the type of an existing widget. If user wants to change this, then first delete widget and then create new widget of different type.

### Delete a widget

  User can remove an existing widget on the dashboard by clicking on the dustbin icon present at the top right corner of the widget.
  {{< img-simple src="deleteWidget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  User can add more widgets as per the requirements. Below are some of the examples of dashboard.
  {{< img-simple src="example1.png" alt="Dashboards app" class="border-0 rounded-circle" >}}
  {{< img-simple src="example2.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  ### Duplicate a widget

  We can duplicate widget in same dasbhoard panels as well as in different dashboard's panels also. <br/>
  
  1. To duplicate widget, First switch the dashboard in edit mode, just click on the pencil icon present on the dashboard header.
  {{< img-simple src="editDashboard.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  2. Once the dashboard switched into the eidting mode, when user hover mouse point on the widget the three icons will be shown to user <br/>
  Click on the first copy/duplicate icon <br/>
  {{< img-simple src="copyWidget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}

  3. The Duplicate widget modal will be appear on the screen <br/>
    Select the targated dashboard, panel (and subpanel) and click on save, widget will be duplicated on the targetd place. <br/>
  {{< img-simple src="duplicateWidget.png" alt="Dashboards app" class="border-0 rounded-circle" >}}