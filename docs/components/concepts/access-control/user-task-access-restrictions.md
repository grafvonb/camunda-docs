---
id: user-task-access-restrictions
title: "User task access restrictions"
sidebar_label: "User task access restrictions"
description: "Control the level of access a user or group has to perform tasks in the system via user task access restrictions."
---

:::caution
User task access restrictions are enabled by default on SaaS.
:::

User task access restrictions allow you to restrict access of user tasks in Tasklist to [users](../../console/manage-organization/manage-users.md) or
[groups](user-groups.md) where they are assignees or candidates.

### User task access restrictions

User task access restrictions are used in Tasklist to control task access for a
user or [group](user-groups.md). The restrictions are
related to the candidate users or groups set up on user task definitions.

For example, if a task has a candidate group named `Team A` and a candidate user named `example`, only the
users that belong to `Team A` and the user `example` will have access to the task.

### Enabling/disabling user task access restrictions

User task access restrictions are enabled by default. To disable them, navigate to the **Settings** section of Console and click the **Enforce user task restrictions** toggle to enable or disable the functionality.

![Enabling User Task Restriction](../assets/access-control/enforce-user-task-restriction.png)

When activated, tasks assigned to users or candidate groups are only visible to the assigned user or respective group members. When deactivated, every user can see any task, regardless of the assignment.