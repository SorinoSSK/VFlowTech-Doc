---
title: "Creating Assets"
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

{{< img-simple src="asset-type-duplicate.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we already have an Asset Type with required metadata, then we can simply duplicate the asset type by clicking on the duplicate icon in the actions column. We just have to enter the new Asset Type name and it'll create an asset type with the same properties of the asset type from which it was duplicated.

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

{{< img-simple src="asset-duplicate.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we already have an Asset with required Asset Type, then we can simply duplicate the asset by clicking on the duplicate icon in the actions column. We just have to enter the new Asset name and it'll create an asset with the same properties of the asset from which it was duplicated.

This is how we create Assets.
