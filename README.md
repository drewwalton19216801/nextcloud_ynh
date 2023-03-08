<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Nextcloud for YunoHost

[![Integration level](https://dash.yunohost.org/integration/nextcloud.svg)](https://dash.yunohost.org/appci/app/nextcloud) ![Working status](https://ci-apps.yunohost.org/ci/badges/nextcloud.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/nextcloud.maintain.svg)

[![Install Nextcloud with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nextcloud)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Nextcloud quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Nextcloud Hub is a fully open-source on-premises content collaboration platform. Teams access, share and edit their documents, chat and participate in video calls and manage their mail and calendar and projects across mobile, desktop and web interfaces.

### YunoHost-specific features

In addition to Nextcloud core features, the following are made available with
this package:

 * Integrate with YunoHost users and SSO - i.e. logout button
 * Allow one user to be the administrator (set at the installation)
 * Allow multiple instances of this application
 * Optionally access the user home folder from Nextcloud files (set at the installation, the sharing is enabled by default)
 * Serve `/.well-known` paths for CalDAV and CardDAV on the domain only if it's not already served - i.e. by Baïkal


**Shipped version:** 25.0.4~ynh2

**Demo:** https://demo.nextcloud.com/

## Screenshots

![Screenshot of Nextcloud](./doc/screenshots/screenshot.png)

## Documentation and resources

* Official app website: <https://nextcloud.com>
* Official user documentation: <https://docs.nextcloud.com/server/latest/user_manual/en/>
* Official admin documentation: <https://docs.nextcloud.com/server/stable/admin_manual/>
* Upstream app code repository: <https://github.com/nextcloud/server>
* YunoHost documentation for this app: <https://yunohost.org/app_nextcloud>
* Report a bug: <https://github.com/YunoHost-Apps/nextcloud_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing --debug
or
sudo yunohost app upgrade nextcloud -u https://github.com/YunoHost-Apps/nextcloud_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
