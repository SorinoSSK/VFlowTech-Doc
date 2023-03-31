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

As we've already discussed, Assets contains two tabs - Assets and Asset Types. Asset and Asset Types tab contains of list of Assets and Asset Types respectively.

In order to create an Asset, we first need to create an Asset Type for that.

Every asset is created from an asset type. For example, there could be many `motors` labeled `motor-1, motor-2, ...` in a project, but all of those might be coming from the asset type called `motor`. This is done to allow comparison among similar assets belonging to the same asset type.

## Creating an Asset Type

To create an Asset Type, we first need to go to Asset Types tab.

{{< img-simple src="asset-type-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

On the top right of Asset types list, there is an Add asset type button.

{{< img-simple src="asset-type-button.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on this button will open up a modal. The modal contains two sections - Details and Metadata (Fixed Data).

{{< img-simple src="asset-type-modal-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we have to enter the Asset Type name and it's description (optional).

{{< img-simple src="asset-type-modal-sec2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Then clicking on next will take us to the next section named Metadata (Fixed Data) where we add Metadata Name, Data Type and Unit. We can create multiple Metadata using the Add New button.

After entering the details, clicking on save button will create an Asset Type for us.

## Editing an Asset type

{{< img-simple src="edit-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on edit asset type button will open up a modal. The modal contains two sections - Details and Metadata(Fixed data).

{{< img-simple src="edit-asset-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we can edit the Asset Type name and it's description (optional).

{{< img-simple src="edit-asset-type2.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

And if we want to edit the Metadata (Fixed Data), Metdata list of selected Asset is displayed.

After entering the details, clicking on save button will edit an Asset type for us.

## Deleting an Asset type

{{< img-simple src="delete-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on delete asset type button will open up a Confirm modal.

{{< img-simple src="delete-assets.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we click on yes then the specific asset type will be deleted.

## Viewing an Asset type

{{< img-simple src="view-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on view asset type button will open up a view modal.

{{< img-simple src="view-asset-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

View modal contains the asset type information such as Name, description, parameters, metadata.

## Duplicating an Asset type

{{< img-simple src="duplicate-asset-type-btn.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on duplicate asset type button will open up a modal.

{{< img-simple src="duplicate-asset-type.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

We just have to enter the new Asset type name and it’ll create an asset type with the same properties of the asset type from which it was duplicated.

