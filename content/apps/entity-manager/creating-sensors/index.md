---
title: "Creating Sensors"
description: ""
date: 2021-02-21T14:06:19+08:00
lastmod: 2021-02-21T14:06:19+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3020
toc: true
---

## Introduction

Similar to Assets, Sensors contains two tabs - Sensors and Sensor Types. Sensor and Sensor Types tab contains of list of Sensors and Sensor Types respectively.

In order to create an Sensor, we first need to create an Sensor Type for that.

Every sensor is created from a sensor type. For example, there could be many `temperature-sensors` labeled `tmpr-1, tmpr-2, ...` in a project, but all of those might be coming from the sensor type called `tmpr`. This is done to allow comparison among similar sensors belonging to the same sensor type.

## Creating a Sensor Type

To create a Sensor Type, we first need to go to Sensor Types tab.

{{< img-simple src="sensor-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

On the top right of Sensor types list, there is an Add Sensor type button.

{{< img-simple src="sensor-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this button will open up a modal. The modal contains three sections - Details, Metadata (Fixed Data) and Parameters (Streaming Data).

{{< img-simple src="sensor-type-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we have to enter the Sensor Type name and it's description (optional).

{{< img-simple src="sensor-type-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Then clicking on next will take us to the next section named Metadata (Fixed Data) where we add Metadata Name, Data Type and Unit. We can create multiple Metadata using the Add New button.

{{< img-simple src="sensor-type-sec3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the last section named Parameters (Streaming Data), we add Parameter Name, Data Type and Unit. We can create multiple Parameters using the Add New button.

After entering the details, clicking on save button will create an Sensor Type for us.

{{< img-simple src="sensor-type-duplicate.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we already have an Sensor Type with required metadata, then we can simply duplicate the sensor type by clicking on the duplicate icon in the actions column. We just have to enter the new Sensor Type name and it'll create the sensor type with the same properties of the sensor type from which it was duplicated.

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
