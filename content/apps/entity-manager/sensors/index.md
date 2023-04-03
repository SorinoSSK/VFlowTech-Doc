---
title: "Sensors"
description: ""
date: 2021-02-21T14:06:19+08:00
lastmod: 2021-02-21T14:06:19+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3050
toc: true
---

## Introduction

<p style="text-align: justify;">
A sensor is a device to measure some information of its surroundings which is a device installed in an asset. With respect to the entity map, we can define that the sensor as a child of the asset it is installed in.
</p>

## Creating a Sensor

<p style="text-align: justify;">
To create a sensor, we need to be in sensors tab.
</p>

{{< img-simple src="sensor-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Similar to sensor types, at the top right corner of sensor list, there is an add sensor button.
</p>

{{< img-simple src="sensor-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on <b>Add Sensor</b> button will open a modal. The add sensor modal contains 3 sub sections - Details, Position, and Metadata (Fixed Data).
</p>

{{< img-simple src="sensor-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we can select a sensor type using the dropdown menu will display all the sensor types that we have created. Enter the sensor name, it's description (optional) and click on the next button.
</p>

{{< img-simple src="sensor-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the next section named Position, there is a dropdown menu to select Sensors's Caretaker(s) and Sensors Hierarchy.
</p>

{{< img-simple src="sensor-sec3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the last section named Metadata (Fixed Data), a list of selected Sensors Type's metadata will be displayed and by clicking on save button a sensor will be created.
</p>

{{< img-simple src="sensor-duplicate.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we have an existing sensor with the required Sensor Type, we can perform duplication of a sensor by clicking on the duplicate icon in the actions column. Entering the name of the new Sensor name will create a sensor with the same properties of the sensor which it was duplicated from.
</p>

## Editing a Sensors

{{< img-simple src="edit-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on edit sensors button will open up a modal. The modal contains 2 sub sections - Details, Position, and Metadata(Fixed data).
</p>

{{< img-simple src="edit-sensor1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we can modify the selected sensor type, sensor name, and it's description (optional).
</p>

{{< img-simple src="edit-sensor2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to change the position of the sensor, we have to access the second section. E.g Position and modify the Sensor's Caretaker(s) and Sensor Hierarchy.
</p>

{{< img-simple src="edit-sensor3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to modify the Metadata (Fixed Data), we can do that in the Metdata list as shown above. (If any)
</p>

After entering the details and clicking on save button, modification of the Sensor will be saved.

## Deleting a Sensor

{{< img-simple src="delete-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on delete sensor button will open up a confirmation modal.
</p>

{{< img-simple src="delete-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we click on <b>yes</b>, the specific sensor will be deleted.
</p>

## Viewing a Sensor

{{< img-simple src="view-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on view sensor button will open up a view modal.
</p>

{{< img-simple src="view-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
View modal contains information of the sensor such as sensor name, description, parameter, parent type, sensor type, metadata and sensor data.
</p>

## Duplicating a Sensor

<p style="text-align: justify;">
If we have an existing sensor with required the sensor type, we can perform duplication of a sensor by clicking on the duplicate icon in the actions column.
</p>

{{< img-simple src="duplicate-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on duplicate sensor button will open up a modal.
</p>

{{< img-simple src="duplicate-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Entering the new Sensor name will create a sensor with the same properties of the sensor which it was duplicated from.
</p>
