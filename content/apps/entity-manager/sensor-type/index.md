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

<p style="text-align: justify;">
Similar to assets, sensors contain 2 sub tabs - Sensors and Sensor Types. Sensor and Sensor Types tab contains a list of Sensors and Sensor Types respectively.
</p>

<p style="text-align: justify;">
In order to create a Sensor, we first need to a Sensor Type created.
</p>

<p style="text-align: justify;">
Every sensor is created from a sensor type. For example, there could be many `temperature-sensors` labeled `tmpr-1, tmpr-2, ...` in a project, but all of those might be coming from the sensor type called `tmpr`. This is done to allow comparison among similar sensors belonging to the same sensor type.
</p>

## Creating a Sensor Type

<p style="text-align: justify;">
To create a Sensor Type, we need to be in the Sensor Types tab.
</p>

{{< img-simple src="sensor-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
At the top right corner of Sensor types list, there is an add sensor type button.
</p>

{{< img-simple src="sensor-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on <b>Add Sensor Type</b> button will open up a modal. The modal contains 3 sub sections - Details, Metadata (Fixed Data) and Parameters (Streaming Data).
</p>

{{< img-simple src="sensor-type-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we have to enter the name of the Sensor Type and it's description (optional).
<p>

{{< img-simple src="sensor-type-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on next will take us to the next section named Metadata (Fixed Data) where we can add Metadata Name, Data Type and Unit. We can create multiple Metadata using the <b>Add New</b> button.
</p>

{{< img-simple src="sensor-type-sec3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the last section named Parameters (Streaming Data), we can add Parameter Name, Data Type and Unit. Multiple parameters can be added by using the <b>Add New</b> button.
</p>

<p style="text-align: justify;">
After entering the details, clicking on save button will create a Sensor Type.
</p>

{{< img-simple src="sensor-type-duplicate.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we have an existing Sensor Type with the required metadata, we can perform duplication of the sensor type by clicking on the duplicate icon in the actions column. By entering the name of the new Sensor Type, it will create the sensor type with the same properties of the sensor type which it was duplicated from.
</p>

## Editing a Sensor type

{{< img-simple src="edit-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on edit sensor type button will open up a modal. The modal contains 3 sub sections - Details, Parameters(Streaming data) and Metadata(Fixed data).
</p>

{{< img-simple src="edit-sensor-type1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we can edit the name of the sensor type and it's description (optional).
</p>

{{< img-simple src="edit-sensor-type2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to add, edit or delete the Metadata (Fixed Data), we can do that in the list of Metdata of the selected Sensor type shown above.
</p>

{{< img-simple src="edit-sensor-type3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to add, edit or delete parameters (Streaming Data), we that do that in the list of parameters of the selected Sensor type as shown below.
</p>

<p style="text-align: justify;">
After entering the details and clicking on save button, modification of the sensor type will be saved.
</p>

## Deleting a Sensor type

{{< img-simple src="delete-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on delete sensor typebutton will open up a confirmation modal.
</p>

{{< img-simple src="delete-sensor.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we click on <b>yes</b>, the specific sensor type will be deleted.
</p>

## Viewing a Sensor type

{{< img-simple src="view-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on view sensor type button will open up a view modal.
</p>

{{< img-simple src="view-sensor-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
View modal contains information of the sensor type such as Sensor type name, description, parameter, and metadata.
</p>

## Duplicating a Sensor type

{{< img-simple src="duplicate-sensor-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on duplicate sensor type button will open up a modal.
</p>

{{< img-simple src="duplicate-sensor-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Entering the name of the new Sensor type will create a sensor type with the same properties of the sensor type which it was duplicated from.
</p>

