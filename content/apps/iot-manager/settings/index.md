---
title: "Alert Rules "
description: ""
date: 2021-02-21T14:09:34+08:00
lastmod: 2021-02-21T14:09:34+08:00
draft: false
images: []
menu:
  apps:
    parent: "iot-manager"
weight: 4060
toc: true
---

## Introduction

Alert rules are the rules that are sent to the email ids or phone numbers if the specific condition is matched for the particular sensor parameters.

Alert Rules is the place where we can create the alert rules for sensors for the particular project. 

To create the alert rules, we have to go to the settings tab from the side bar.

{{< img-simple src="setting-btn-select.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}

The Alert rules list contains name of the rule(Rule Name), date it was created(Created at), severity, alert actions, status, and action buttons.

{{< img-simple src="alert-rule-list.png" alt="Entity Manager app" class="border-0 rounded-circle" >}}


## Creating an Alert rule

Now to create an alert rule, we click on the Add rule button.

{{< img-simple src="add-alert-rule-btn.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

Clicking on this button will open a modal. The Add alert rule modal contains three sections: Details, Conditions, and Actions.

{{< img-simple src="add-alert-rule-1.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

In the first section named "Details," we have to add the alert rule name, rule severity(low, medium, high), project selection, and message.

{{< img-simple src="add-alert-rule-2-1.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

In the next section named Conditions, there are three tabs: data, policy, and grouping.

In the data tab, we have to select the sensor parameter for which we have added the alert rules.

After selecting the data, click on the Next button.

{{< img-simple src="add-alert-rule-2-2.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

In the policy tab, we have to select the parameters for which we have to add alerts. In the parameter sections, we have 3 options. i.e

1. Alert when data is outside the bounded range (this is where we define the parameter's upper and lower bounds).
2. Alert when data exceeds the upper threshold (we define the upper value for the parameter here).
3. Alert when data falls below the lower threshold (we define the lower value for the parameter here).

If the condition is matched with the selected dropdown, then the alert rule will be fired.

After adding the policy, click on the Next button.

{{< img-simple src="add-alert-rule-2-3.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

In the grouping tab, we can fire alerts in the groups at a particular time interval. 

After adding the grouping time interval, first click on Done at the top right corner, then click on the Next button at the bottom right corner.

{{< img-simple src="add-alert-rule-3-1.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

In the last section named Actions, there are two tabs: Media and Recipients.

In the Media tab, we can select how we want to send the alerts via SMS or email. 

After selecting the media, click on the Next button, which is at the top right corner.

{{< img-simple src="add-alert-rule-3-2.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

In the Recipients tab, we can add phone numbers or email IDs where the alert rules will be sent. 

After adding the recipients, click on the Done button at the top right corner and then click on the Save button to add the alert rule. 

This is how we create alert rules.

## Editing a Alert rule

{{< img-simple src="edit-alert-rule-btn.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

Clicking on the edit alert rule button will open up a modal. The modal contains three sections: details, conditions, and actions.

{{< img-simple src="edit-alert-rule-1.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

In the first section named "Details," we can edit the alert rule name, rule severity(Low, medium, or high), project selection, and the message.

{{< img-simple src="edit-alert-rule-2-1.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

{{< img-simple src="edit-alert-rule-2-2.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

{{< img-simple src="edit-alert-rule-2-3.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

If we want to change the data, policy or grouping interval for the alert rule, then we have to click on the second section, i.e., Condition, and then we can edit the selected data, parameters, and also the time interval for grouping alerts.

{{< img-simple src="edit-alert-rule-3-1.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}
{{< img-simple src="edit-alert-rule-3-2.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

And if we want to edit the media or recipients, then we have to click on the third section, i.e., actions, and then we can add or remove the media and recipients . 

After entering the details, clicking on the save button will edit the alert rule for us.

## Deleting a Alert rule

{{< img-simple src="delete-alert-rule-btn.png" alt="Iot Manager app" class="border-0 rounded-circle" >}}

Clicking on the delete alert rule button will open up a confirm modal.

{{< img-simple src="delete-alert-rule-modal.png" alt="iot Manager app" class="border-0 rounded-circle" >}}

If we click on yes, then the specific alert rule will be deleted.
