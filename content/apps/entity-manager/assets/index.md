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

An asset is any physical object or space that is of interest in an IoT project. Examples of assets could be building, ship, factory, solar panel, wind turbine, truck, fridge, motor, pump, generator, inverter, compressor, gearbox, etc. An asset can child other assets below it, thus creating an asset hierarchy.

## Creating an Asset

Now to create an Asset, we need to be in Assets tab.

{{< img-simple src="asset-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Similar to Asset Types, on the top right of Assets list, there is an Add asset button.

{{< img-simple src="asset-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this button will open a modal. The Add asset modal contains tree sections - Details, Position and Metadata (Fixed Data).

{{< img-simple src="add-asset-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we have to select an asset type using a dropdown which shows all the asset types that we've created. Then we have to enter the asset name and it's description (optional). Click on next button after entering the details.

{{< img-simple src="add-asset-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the next section named Position, there is a dropdown to select the Asset's Caretaker(s) and Asset Hierarchy.

{{< img-simple src="add-asset-sec3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the last section named Metadata (Fixed Data), Metdata list of selected Asset Type is displayed. Clicking on save button will create an Asset for us.

This is how we create Assets.

## Editing a Asset

{{< img-simple src="edit-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on edit assets button will open up a modal. The modal contains two sections - Details, Position and Metadata(Fixed data).

{{< img-simple src="edit-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we can edit selected asset type, asset name and it's description (optional).

{{< img-simple src="edit-assets2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we want to change the position of assets, we have to click on second section i.e Position and edit the Asset's Caretaker(s) and Asset Hierarchy.

{{< img-simple src="edit-assets3.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

And if we want to edit the Metadata (Fixed Data), Metdata list of selected Asset is displayed.

After entering the details, clicking on save button will edit a Asset for us.

## Deleting a Asset

{{< img-simple src="delete-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on delete asset button will open up a Confirm modal.

{{< img-simple src="delete-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we click on yes then the specific asset will be deleted.

## Viewing a Asset

{{< img-simple src="view-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on view asset button will open up a view modal.

{{< img-simple src="view-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

View modal contains the asset information such as Asset name, description, properties, metadata.

## Duplicating a Asset

If we already have an Asset with required Asset Type, then we can simply duplicate the asset by clicking on the duplicate icon in the actions column.

{{< img-simple src="duplicate-assets-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on duplicate asset button will open up a modal.

{{< img-simple src="duplicate-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

We just have to enter the new Asset name and it’ll create an asset with the same properties of the asset from which it was duplicated.
