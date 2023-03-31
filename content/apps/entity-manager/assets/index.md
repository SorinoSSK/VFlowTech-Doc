---
title: "Assets"
description: ""
date: 2021-02-21T14:06:15+08:00
lastmod: 2021-02-21T14:06:15+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3030
toc: true
---

## Introduction

<p style="text-align: justify;">
An asset is any physical object or space that is of interest in a VFlowTech Energy System project. Examples of assets could be the battery unit, building, factory, solar panel, wind turbine, truck, fridge, motor, pump, generator, inverter, compressor, gearbox, etc. An asset can be a child of other assets, thus creating an asset hierarchy.
</p>

## Creating an Asset

<p style="text-align: justify;">
To create an Asset, we need to be in Assets tab.
</p>

{{< img-simple src="asset-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Similar to Asset Types, on the top right of Assets list, there is an add asset button.
</p>

{{< img-simple src="asset-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on <b>Add Asset</b> button will open a modal. The Add asset modal contains 3 sub sections - Details, Position and Metadata (Fixed Data).
</p>

{{< img-simple src="add-asset-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we have to select an asset type using a dropdown menu which will display all asset types that we have created for selection. After which, we have to enter the asset's name and it's description (optional). Click on the next button after entering the details.
</p>

{{< img-simple src="add-asset-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the next section named Position, there are dropdown menus to select the Asset's Caretaker(s) and Asset Hierarchy.
</p>

{{< img-simple src="add-asset-sec3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the last section named Metadata (Fixed Data), a Metdata list of the selected Asset Type will be displayed and clicking on save button will create an asset.
</p>

## Editing an Asset

{{< img-simple src="edit-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on edit assets button will open up a modal. The modal contain 2 sub sections - Details, Position and Metadata(Fixed data).
</p>

{{< img-simple src="edit-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section named Details, we can modify the selected asset type, asset name and it's description (optional).
</p>

{{< img-simple src="edit-assets2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to change the position of assets, we can do that on the second section. E.g Position and edit the Asset's Caretaker(s) and Asset Hierarchy.
</p>

{{< img-simple src="edit-assets3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we require to modify the Metadata (Fixed Data), we can do that in the Metdata list of the selected Asset as shown above.
</p>

<p style="text-align: justify;">
After entering the details, clicking on save button will save the modification of the Asset.
</p>

## Deleting an Asset

{{< img-simple src="delete-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on delete asset button will open up a Confirm modal.
</p>

{{< img-simple src="delete-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we click on <b>yes</b>, the specific asset will be deleted.
</p>

## Viewing an Asset

{{< img-simple src="view-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on view asset button will open up a view modal.
</p>

{{< img-simple src="view-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
View modal contains the asset's information such as Asset name, description, properties, and metadata.
</p>

## Duplicating an Asset

<p style="text-align: justify;">
If we have an existing Asset with the required Asset Type, we can perform duplication of the asset by clicking on duplicate icon in the actions column.
</p>

{{< img-simple src="duplicate-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on duplicate asset button will open up a modal.
</p>

{{< img-simple src="duplicate-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Entering the name of the new asset will create an asset with the same properties of the asset which it is duplicated from.
</p>