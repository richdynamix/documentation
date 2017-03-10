---
title: BitBucket Integration
LinkTitle: BitBucket Integration
menu:
  main:
    parent: 'configuration'
    weight: 100

weight: 100
---
In order to use ContinuousPipe with a BitBucket repository, you need to configure two interaction points: 

## Creating a Linked Account in ContinuousPipe

The first interaction is linking the BitBucket account to ContinuousPipe. This is needed when creating a flow so that ContinuousPipe can list repositories to select. 

Setting up a linked account is demonstrated in the Quick Start guide to [creating a flow]({{< relref "quick-start/creating-a-flow.md" >}}).

## Installing the ContinuousPipe Integration in BitBucket

The second interaction is installing the ContinuousPipe integration in BitBucket. This is needed in order to let ContinuousPipe know about any repository changes that have been made and to add comments on pull requests.

To install the integration go to your BitBucket account settings page. In the left menu, click on "Manage integrations".

![](/images/configuration/bitbucket-settings-menu.png)

You can now click on "Install add-on from URL" and enter `https://authenticator.continuouspipe.io/connect/service/bitbucket/addon/` as show in this example:

![](/images/configuration/bitbucket-addon-install.png)

The last step is to grant ContinuousPipe access to your code repository by clicking the "Grant access" button in the following screen.

![](/images/configuration/bitbucket-grant-access-popup.png)

You are now all set and the BitBucket integration is configured for your account.