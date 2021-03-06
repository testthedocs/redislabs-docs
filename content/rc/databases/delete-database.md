---
Title: Delete a database
description:
weight: 30
alwaysopen: false
categories: ["RC"]
aliases: /rc/administration/setup-and-editing/delete-databases/
        /rv/administration/setup_and_editing/deleting-database/
---
Deleting a database is just as easy as creating one.
Make sure that you are truly done with the database,
because after you delete the database it cannot be recovered (except from your backups).

{{< note >}}
- Only users that are defined as Owners on the Redis Cloud account can delete a database.
- We recommend that you create a backup of your database before deleting it.
{{< /note >}}

## Deleting a database

1. Use the admin console menu to select the **Databases** command.

1. From the databases list, select the database you want to delete.

1. When the database details appear, select the Delete icon.

1. Confirm your choice.

The database and all of its data and configurations is now deleted.
