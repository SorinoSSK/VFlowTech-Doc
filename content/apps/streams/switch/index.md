---
title: "Switch"
description: ""
date: 2022-08-13T08:32:06+05:30
lastmod: 2022-08-13T08:32:06+05:30
draft: false
menu:
  apps:
    parent: "streams"
weight: 1016
images: []
---

Switch node can be used to divert the pipeline execution based on the gateways/asset that is selected.

### Action Fields

#### Name
Name field can be used to give custom name to the node.

#### Match All
When we want all the condition of switch node to be matched then toggle this flag.
The further pipelines of switch predicates will be executed of the all the condition match.

#### Output
We can add dynamic output in switch node, where we need to input following values for each output.
Based on the entities that are selected in the output, if the payload contains data related to that entity then the respective output
will be triggered.

- Entity Name

Name of the output port.

- Entity Type

Here we need to select what kind of entity needs to be matched ie. Gateway or Asset.

- Entity Selection

Based on the entity type selected we need to select the actual entities from the dropdown.

Following is example of switch node fields:

{{< img-simple src="switch_node_fields.png" alt="Role Manager app" class="border-0 rounded-circle" >}}


