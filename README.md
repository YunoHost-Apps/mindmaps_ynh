# Mindmaps for YunoHost

[![Integration level](https://dash.yunohost.org/integration/mindmaps.svg)](https://dash.yunohost.org/appci/app/mindmaps) ![](https://ci-apps.yunohost.org/ci/badges/mindmaps.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/mindmaps.maintain.svg)  
[![Install Mindmaps with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=mindmaps)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Mindmaps quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview
Mindmaps is a HTML5 based mind mapping application. It lets you create neat looking mind maps in the browser.

**Shipped version:** 1.0

## Screenshots

![](sources/mindmaps-screenshot.jpg)

## Demo

* [Official demo](https://www.mindmaps.app/)

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: https://yunohost.org/#/app_mindmaps

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported? **No**
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/mindmaps%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/mindmaps/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/mindmaps%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/mindmaps/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/mindmaps_ynh/issues
 * App website: https://www.mindmaps.app/
 * Upstream app repository: https://github.com/drichard/mindmaps
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/mindmaps_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/mindmaps_ynh/tree/testing --debug
or
sudo yunohost app upgrade mindmaps -u https://github.com/YunoHost-Apps/mindmaps_ynh/tree/testing --debug
```
