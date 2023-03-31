---
title: "Entity Map"
description: ""
date: 2021-02-21T14:06:32+08:00
lastmod: 2021-02-21T14:06:32+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3080
toc: true
---

## Introduction

<p style="text-align: justify;">
Entity Map displayes a tree structure of our Project Entities which can be viewed in map view or outline view. By default, we have the organsation name and the project name in entity map.
</p>

{{< img-simple src="entity-map-structure.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

## Creating Entity Map

<p style="text-align: justify;">
Project is a child entity of an organization, the root element and we can add child entities to our project. Hovering on the project's name will give us the option to add child entity.
</p>

{{< img-simple src="child-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
After clicking on it, Add Child Entity modal opens us which asks about the entity that we want to add - Asset or Sensor.
</p>

{{< img-simple src="add-sensor-asset.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Add asset modal open up if we click on <b>Asset</b> where we can add details of a new asset. The new asset will be created as a child entity to the project.
</p>

{{< img-simple src="add-asset-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Similarly to asset model, an add sensor model will open up when we click on <b>Sensor</b>, where we add details of a new sensor. The new sensor will be created as a child entity to the project.
</p>

{{< img-simple src="sensor-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Following the entity notation, newly created entities will be notated with a black border. However, after saving the entity map, entities will have their black border removed.
</p>

{{< img-simple src="new-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
We can save newly added entities by clicking on save button at the top of the entity map.
</p>

{{< img-simple src="child-sibling-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
We can add a <b>Child</b> or <b>Sibling</b> entity to assets but only a sibling entity to a sensor. We can verify this by hovering on Assets/Sensors and the option to add the entity as child/sibling will be displayed.
</p>

{{< img-simple src="only-sibling-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on a child entity/ sibling entity we can get a similar add asset modal to add an Asset or Sensor.
</p>

<p style="text-align: justify;">
Upon selecting an entity we can view it's properties/ details on the right sidebar.
</p>

{{< img-simple src="save-delete-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
If we wish to modify the details of any entity, we can click on the entity and change it in the properties section at the right sidebar. Clicking on the save button will save all changes of that particular entity.
</p>

<p style="text-align: justify;">
To delete any entity, we can click on an entity and delete it by clicking on the <b>Delete</b> button in the properties sections at the right sidebar.
</p>