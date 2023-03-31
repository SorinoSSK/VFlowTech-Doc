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
weight: 2040
toc: true
---

## Introduction

<p style="text-align: justify;">
As discussed previously, Users contains two sub tabs - Users and Invites. Users and Invites tab contains of list of Users and Invites respectively.
</p>

In order to invite a User, we will need to create a User Group first. 

[[Read more in previous section]]({{<ref "/apps/role-manager/creating-user-groups">}})

## Inviting a User

To invite a user, we need to be in Users tab.

{{< img-simple src="role-manager-users-list.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

At the top right corner of Users list, there is an <b>Invite New User</b> button.

{{< img-simple src="role-manager-invite-user-button.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
Clicking on <b>Invite New User</b> button will open up a modal. The add user modal contains two sub sections - Details and Apps.
</p>

{{< img-simple src="add-user-modal-1.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the first section, <b>Details</b> secton; we have to enter the email of the user that we wanted to invite and select a User Group using the dropdown menu. The dropdown menu will display all the user groups that we have created for selection. We are able to select multiple user groups. We will click on the next button after entering the details.
</p>

{{< img-simple src="add-user-modal-2.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

<p style="text-align: justify;">
In the next section named Apps, a list of apps and action items will be displayed. The apps and action items displayed will have apps and action items pre-selected according to the user group we have select on the previous section. In this section, we can also select apps and action items which are not preset in the selected User Group which will not be in disabled state. Clicking on save button will send an email invite to user.
</p>

{{< img-simple src="role-manager-invites-list1.png" alt="Role Manager app" class="border-0 rounded-circle" >}}

After the invitation is sent, the invited email get listed in the <b>Invites</b> tab.

<p style="text-align: justify;">
The invites tab contains a list user invited into the organisation along with their Email, Level, Status and Actions. In the <b>Actions</b> column, we have options to delete and re-invite users.
</p>

Clicking on re-invite button will send an email invite to user again.

When a user accepts the email invitation, the user will be moved to the Users list from the invite list.