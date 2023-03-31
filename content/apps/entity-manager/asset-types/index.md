---
title: "Asset types"
description: ""
date: 2021-02-21T14:06:15+08:00
lastmod: 2021-02-21T14:06:15+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3020
toc: true
---

## Introduction

<p style="text-align: justify;">
As discussed previously, assets contains two sub tabs - Assets and Asset Types. Asset and Asset Types tab contains of list of Assets and Asset Types respectively.
</p>

<p style="text-align: justify;">
In order to create an Asset, we first need to create an Asset Type for that.
</p>

<p style="text-align: justify;">
Every asset is created from an asset type. For example, there could be many `motors` in a project and they are labeled as `motor-1, motor-2, ...`. However, all of these motors might be categorised from the asset type called `motor`. Therefore, this function allows comparison among similar assets belonging to the same asset type.
</p>

## Creating an Asset Type

<p style="text-align: justify;">
To create an Asset Type, we first need to go to Asset Types tab.
</p>

{{< img-simple src="asset-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Ay the top right corner of asset types list, there is an add asset type button.
</p>

{{< img-simple src="asset-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on this button will open up a modal. The modal contains 2 sub sections - Details and Metadata (Fixed Data).
</p>

{{< img-simple src="asset-type-modal-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named <b>Details</b>, we have to enter the <b>Asset Type</b> name and it's description (optional).
</p>

{{< img-simple src="asset-type-modal-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on next will take us to the next section named Metadata (Fixed Data) where we can add information such as Metadata Name, Data Type and Unit. We can add multiple Metadata by using the <b>Add New</b> button.
</p>

<p style="text-align: justify;">
After entering the details, clicking on save button will create the Asset Type.
</p>

## Editing an Asset type

{{< img-simple src="edit-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on edit asset type button will open up a modal. The modal contains 2 sub sections - Details and Metadata(Fixed data).
</p>

{{< img-simple src="edit-asset-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we can modify the Asset Type name and it's description (optional).
</p>

{{< img-simple src="edit-asset-type2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to edit the Metadata (Fixed Data), we can modify them from the list of Metadata of the selected asset type as shown above.
</p>

<p style="text-align: justify;">
After entering the details, clicking on save button will modify the Asset type.
</p>

## Deleting an Asset type

{{< img-simple src="delete-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on delete asset type button will open up a confirmation modal.
</p>

{{< img-simple src="delete-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we click on <b>Yes</b>, the specific asset type will be deleted.
</p>

## Viewing an Asset type

{{< img-simple src="view-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on view asset type button will open up a view modal.

{{< img-simple src="view-asset-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
View modal contains the asset type information such as Name, description, parameters, and metadata.
</p>

## Duplicating an Asset type

{{< img-simple src="duplicate-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on duplicate asset type button will open up a modal.
</p>

{{< img-simple src="duplicate-asset-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Entering the name of the new asset type will create an asset type with the same properties as the asset type of which it was duplicated from.
</p>

