---
Title: Create and edit a Cloud Account
description:
weight: 20
alwaysopen: false
categories: ["RC"]
aliases: /rv/how-to/view-edit-cloud-account/
        /rv/how-to/creating-cloud-account/
        /rc/how-to/creating-cloud-account/
---

Many customers use cloud provider accounts provisioned and maintained by Redis Labs.

Customers with existing Amazon Web Services accounts can provision their Flexible or Annual subscriptions to use their existing AWS accounts.  

To do so, you associate your existing AWS account as a _cloud account_ for your subscription, which requires entering credentials to enable monitoring, maintenance, and technical support.

You need to create:

1. A programmatic user and provide us with the access key and secret access key for that user.
1. A console role and provide us with that role name.

To create or edit a cloud account in Redis Cloud:

1. Sign into the admin console and then select the target subscription.

1. From the console menu, select **Cloud Accounts** and then either:

    - Select the ![Add](/images/rs/icon_add.png#no-click "Add") to add a new account.

    - Select the account that you want to edit and then select **Edit**.

1. Enter the cloud account details, which include:

    - **Account Name** - A meaningful name for the account
    - **AWS_ACCESS_KEY_ID** - The AWS access key for the programmatic user
    - **AWS_SECRET_ACCESS_KEY** - The AWS secret access key for the programmatic user
    - **IAM Role Name** - The name of the console role with access to the console

1. Select **Save**.

Use the **Delete** button to remove a cloud account from your subscription.
