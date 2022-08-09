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

A sensor is a device to measure some metric in its surroundings which is typically the asset on which the sensor is installed. With respect to the entity map, we can say that the sensor is the child of that asset.

## Creating a Sensor

Now to create a Sensor, we need to be in Sensors tab.

{{< img-simple src="sensor-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Similar to Sensor Types, on the top right of Sensors list, there is an Add sensor button.

{{< img-simple src="sensor-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this button will open a modal. The Add sensor modal contains tree sections - Details, Position and Metadata (Fixed Data).

{{< img-simple src="sensor-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we have to select a sensor type using a dropdown which shows all the sensor types that we've created. Then we have to enter the sensor name and it's description (optional). Click on next button after entering the details.

{{< img-simple src="sensor-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the next section named Position, there is a dropdown to select the Sensors's Caretaker(s) and Sensors Hierarchy.

{{< img-simple src="sensor-sec3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the last section named Metadata (Fixed Data), a list of selected Sensors Type's metadata is displayed. Clicking on save button will create a Sensor for us.

{{< img-simple src="sensor-duplicate.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we already have a Sensor with required Sensor Type, then we can simply duplicate the sensor by clicking on the duplicate icon in the actions column. We just have to enter the new Sensor name and it'll create a sensor with the same properties of the sensor from which it was duplicated.

This is how we create Sensors.


## Editing a Sensors

{{< img-simple src="edit-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on edit sensors button will open up a modal. The modal contains two sections - Details, Position and Metadata(Fixed data).

{{< img-simple src="edit-sensor1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we can edit selected sensor type, sensor name and it's description (optional).

{{< img-simple src="edit-sensor2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we want to change the position of sensor, we have to click on second section i.e Position and edit the Sensor's Caretaker(s) and Sensor Hierarchy.

{{< img-simple src="edit-sensor3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

And if we want to edit the Metadata (Fixed Data), Metdata list of selected Sensor is displayed.

After entering the details, clicking on save button will edit a Sensor for us.

## Deleting a Sensor

{{< img-simple src="delete-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on delete sensor button will open up a Confirm modal.

{{< img-simple src="delete-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we click on yes then the specific sensor will be deleted.

## Viewing a Sensor

{{< img-simple src="view-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on view sensor button will open up a view modal.

{{< img-simple src="view-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

View modal contains the sensor information such as Sensor name, description, parameter, parent type, sensor type, metadata and also Sensor data.

## Duplicating a Sensor

If we already have a Sensor with required Sensor Type, then we can simply duplicate the sensor by clicking on the duplicate icon in the actions column.

{{< img-simple src="duplicate-sensor-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on duplicate sensor button will open up a modal.

{{< img-simple src="duplicate-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

We just have to enter the new Sensor name and it’ll create a sensor with the same properties of the sensor from which it was duplicated.

