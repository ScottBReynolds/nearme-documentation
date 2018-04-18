---
title: Updating the Marketplace Kit
permalink: /get-started/updating-marketplace-kit
---

This guide will help you update the Platform OS Marketplace Kit to the latest version. The Marketplace Kit allows you to easily deploy your configuration files and assets to our platform, and communicate with the Platform OS API. We continuously improve and add new functionality to the Marketplace Kit, so we recommend to use the latest version.

## Requirements

To be able to update the Marketplace Kit, you have to have it installed on your computer. If you don't have the Marketplace Kit installed, the installation process will automatically install the latest version.

* [Installing the Marketplace Kit]()

## Steps

Updating the Marketplace Kit is a two-step process:

1.  Update the Marketplace Kit
2.  Check the version number

### Step 1: Update the Marketplace Kit

To update the Marketplace Kit to the latest version, enter:

```
npm -g install @platform-os/marketplace-kit
```

If your node is installed for all users you might need to use `sudo` to install npm packages globally:

```
sudo npm i -g @platform-os/marketplace-kit
```

You can follow the update process in your command-line (something similar to this will be displayed during the update):

```
/usr/local/bin/marketplace-kit-env -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-env.js
/usr/local/bin/marketplace-kit -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit.js
/usr/local/bin/marketplace-kit-env-list -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-env-list.js
/usr/local/bin/marketplace-kit-env-add -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-env-add.js
/usr/local/bin/marketplace-kit-deploy -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-deploy.js
/usr/local/bin/marketplace-kit-init -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-init.js
/usr/local/bin/marketplace-kit-push -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-push.js
/usr/local/bin/marketplace-kit-archive -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-archive.js
/usr/local/bin/marketplace-kit-sync -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-sync.js
/usr/local/bin/marketplace-kit-watch -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-watch.js
/usr/local/bin/marketplace-kit-logs -> /usr/local/lib/node_modules/@platform-os/marketplace-kit/marketplace-kit-logs.js
+ @platform-os/marketplace-kit@1.1.0
added 28 packages and updated 3 packages in 5.227s
```

### Step 2: Check the version number

Use the following command to check the version number of your Marketplace Kit:

```
marketplace-kit -V
```

Running this command displays the version number of your Marketplace Kit, for example:

```
1.1.0
```

## Next steps

Congratulations! You have updated your Marketplace Kit. You can use it to create your required directory structure, or to deploy and sync your changes.

* [Creating the Required Directory Structure]()
* [Deploying and Syncing Changes]()

## Questions?

We are always happy to help with any questions you may have. Consult our [documentation](), [contact support](), or [connect with our sales team]().