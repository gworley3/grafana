+++
title = "Dashboard and folder permissions"
description = "Grafana Dashboard and Folder Permissions Guide "
keywords = ["grafana", "configuration", "documentation", "dashboard", "folder", "permissions", "teams"]
aliases = ["/docs/grafana/latest/permissions/dashboard_folder_permissions/"]
weight = 200
+++

# Grant dashboard and folder permissions

You can assign and remove permissions for organization roles, users, and teams for specific dashboards and dashboard folders.

This page explains how to grant permissions to specific folders and dashboards.

To learn more about denying access to certain Grafana users, refer to [Restricting access]({{< relref "restricting-access.md">}}).

![Folder permissions](/img/docs/permissions/folder-permissions-7-5.png)

## Permission levels

Grafana has three permission levels that can be assigned regardless of organization role.

- **Admin -** Can edit and create dashboards and edit permissions. Can also add, edit, and delete folders.
- **Edit -** Can edit and create dashboards. _Cannot_ edit folder/dashboard permissions, or add, edit, or delete folders.
- **View -** Can only view existing dashboards/folders.

## Grant folder permissions

Folder permissions apply to the folder and all dashboards contained within it.

1. In the sidebar, hover your mouse over the **Dashboards** (squares) icon and then click **Manage**.
1. Hover your mouse cursor over a folder and then click **Go to folder**.
1. Go to the **Permissions** tab, and then click **Add Permission**.
1. In **Add Permission For**, select **User**, **Team**, or one of the role options.
1. In the second box, select the user or team to add permission for. Skip this step if you selected a role option in the previous step.
1. In the third box, select the permission you want to add.
1. Click **Save**.

## Grant dashboard permissions

1. In the top right corner of your dashboard, click the cog icon to go to **Dashboard settings**.
1. Go to the **Permissions** tab, and then click **Add Permission**.
1. In **Add Permission For**, select **User**, **Team**, or one of the role options.
1. In the second box, select the user or team to add permission for. Skip this step if you selected a role option in the previous step.
1. In the third box, select the permission you want to add.
1. Click **Save**.

## Edit permissions

To change existing permissions, navigate to the permissions page as described above. Instead of clicking **Add permission**, change or delete permissions already assigned. Changes take effect immediately.
