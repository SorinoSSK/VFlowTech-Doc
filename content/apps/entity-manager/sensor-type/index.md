---
title: "Sensor types"
description: ""
date: 2021-02-21T14:06:19+08:00
lastmod: 2021-02-21T14:06:19+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3040
toc: true
---

## Introduction

Similar to Assets, Sensors contains two tabs - Sensors and Sensor Types. Sensor and Sensor Types tab contains of list of Sensors and Sensor Types respectively.

In order to create a Sensor, we first need to create a Sensor Type for that.

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

After entering the details, clicking on save button will create a Sensor Type for us.

{{< img-simple src="sensor-type-duplicate.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we already have an Sensor Type with required metadata, then we can simply duplicate the sensor type by clicking on the duplicate icon in the actions column. We just have to enter the new Sensor Type name and it'll create the sensor type with the same properties of the sensor type from which it was duplicated.

## Editing a Sensor type

{{< img-simple src="edit-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on edit sensor type button will open up a modal. The modal contains two sections - Details, Parameters(Streaming data) and Metadata(Fixed data).

{{< img-simple src="edit-sensor-type1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we can edit sensor type name and it's description (optional).

{{< img-simple src="edit-sensor-type2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we want to add, edit or delete the Metadata (Fixed Data), Metdata list of selected Sensor type is displayed.

{{< img-simple src="edit-sensor-type3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

And if we want to add, edit or delete the parameters (Streaming Data), Metdata list of selected Sensor type is displayed.

After entering the details, clicking on save button will edit a Sensor type for us.

## Deleting a Sensor type

{{< img-simple src="delete-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on delete sensor typebutton will open up a Confirm modal.

{{< img-simple src="delete-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we click on yes then the specific sensor type will be deleted.

## Viewing a Sensor type

{{< img-simple src="view-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on view sensor type button will open up a view modal.

{{< img-simple src="view-sensor-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

View modal contains the sensor type information such as Sensor type name, description, parameter, metadata.

## Duplicating a Sensor type

{{< img-simple src="duplicate-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on duplicate sensor type button will open up a modal.

{{< img-simple src="duplicate-sensor-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

We just have to enter the new Sensor type name and it’ll create a sensor type with the same properties of the sensor type from which it was duplicated.

