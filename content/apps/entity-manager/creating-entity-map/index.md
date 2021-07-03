---
title: "Creating Entity Map"
description: ""
date: 2021-02-21T14:06:32+08:00
lastmod: 2021-02-21T14:06:32+08:00
draft: false
images: []
menu:
  apps:
    parent: "entity-manager"
weight: 3040
toc: true
---

## Introduction

Entity Map is the place where tree structure of our Project Entities can be seen in Map view or Outline view. By default we get organzation and project name in entity map.

{{< img-simple src="entity-map-structure.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

## Creating Entity Map

Project is a child entity of Organization, which is the root element. We can add child entities to our Project. Hovering on the Project name gives us the option to add child entity.

{{< img-simple src="child-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

After clicking on it, Add Child Entity modal opens us which asks about the entity that we want to add - Asset or Sensor.

{{< img-simple src="add-sensor-asset.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we select Asset, then Add asset modal opens up where we add the details and a new asset is created as a child entity to project.

{{< img-simple src="add-asset-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Similary when we select sensors, Add sensor modal opens up where we add the details and a new sensor is created as a child entity to project.

{{< img-simple src="sensor-sec1.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Following the entity notation, newly created entities have black border. Once they're saved they became saved entities then the black border disappears.

{{< img-simple src="new-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

To save the newly added entites, we use the save button on top to save the entire entity map.

{{< img-simple src="child-sibling-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

We can add Child or Sibling entity to Assets whereas only Sibling entity can be added to Sensors. Hovering on Assets/Sensors show to option to add entity as child/sibling.

{{< img-simple src="only-sibling-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

Clicking on Child Entity/Sibling Entity we again get the same Add asset modal to add Asset or Sensor.

On selecting an entity we can see it's properties/details on the right sidebar.

{{< img-simple src="save-delete-entity.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

If we wish to change details of any entity, we click on it and in the properties section on the right, we can change the details and click on save button to save the changes of that particular entity.

In order to delete any entity, we select it and in the Properties sections, Delete button is there to delete the entity.
