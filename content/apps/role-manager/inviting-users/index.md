---
title: "Inviting Users"
description: ""
date: 2021-02-21T13:42:04+08:00
lastmod: 2021-02-21T13:42:04+08:00
draft: false
images: []
menu:
  apps:
    parent: "role-manager"
weight: 2030
toc: true
---

## Introduction

As we’ve already discussed, Users contains two tabs - Users and Invites. Users and Invites tab contains of list of Users and Invites respectively.

In order to invite a User, we first need to create a User Group for that. (Discussed in previous section)

## Inviting a User

Now to invite a user, we need to be in Users tab.

{{< img-simple src="role-manager-users-list.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

On the top right of Users list, there is an Invite User button.

{{< img-simple src="role-manager-invite-user-button.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

Clicking on this button will open up a modal. The Add asset modal contains two sections - Details and Apps.

{{< img-simple src="add-user-modal-1.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

In the first section named Details, we have to enter the email that we want to invite and select a User Group using a dropdown which shows all the user groups that we’ve created. We can also select multiple user groups. Click on next button after entering the details.

{{< img-simple src="add-user-modal-2.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

In the next section named Apps, there is a list of apps and action items. The apps and action items shown here which are already present in the selected user group are in disabled state. Here we can also select apps and action items which are not present in the selected User Group which will not be in disabled state. Clicking on save button will send an email invite to user.

{{< img-simple src="role-manager-invites-list.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

After the invitation is sent, the invited email gets listed in the Invites tab.

When a user accepts the email invitation, then it is shown up in the Users list.

This is how we invite Users.
