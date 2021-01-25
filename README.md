# Trilium for YunoHost

[![Integration level](https://dash.yunohost.org/integration/trilium.svg)](https://dash.yunohost.org/appci/app/trilium) ![](https://ci-apps.yunohost.org/ci/badges/trilium.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/trilium.maintain.svg)  
[![Install Trilium with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=trilium)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Trilium quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Trilium Notes is a hierarchical note taking application with focus on building large personal knowledge bases.

**Shipped version:** 0.45.8

## Screenshots

![](https://raw.githubusercontent.com/wiki/zadam/trilium/images/screenshot.png)

## Demo

* [Official demo](https://demo.hedgedoc.org/)

## Configuration

You can configure HedgeDoc by editing this file `/var/www/hedgedoc/config.json` using the [documentation](https://github.com/hedgedoc/hedgedoc/blob/master/docs/configuration.md)  
When you finished editing the configuration, for your changes to take effect, you will have to run: `sudo systemctl restart hedgedoc`.

## Documentation

 * Official documentation: https://github.com/hedgedoc/hedgedoc/tree/master/docs
 * YunoHost documentation: https://yunohost.org/#/app_hedgedoc

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/trilium%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/trilium/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/trilium%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/trilium/)

## Limitations

* HedgeDoc needs more than 3 GB of RAM to build.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/trilium_ynh/issues
 * App website: https://github.com/zadam/trilium
 * Upstream app repository: https://github.com/hedgedoc/hedgedoc
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/trilium_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/trilium_ynh/tree/testing --debug
or
sudo yunohost app upgrade trilium -u https://github.com/YunoHost-Apps/trilium_ynh/tree/testing --debug
```
