<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Adminer for YunoHost

[![Integration level](https://dash.yunohost.org/integration/adminer.svg)](https://dash.yunohost.org/appci/app/adminer) ![](https://ci-apps.yunohost.org/ci/badges/adminer.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/adminer.maintain.svg)  
[![Install Adminer with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=adminer)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Adminer quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Adminer (formerly phpMinAdmin) is a full-featured database management tool written in PHP. Conversely to phpMyAdmin, it consist of a single file ready to deploy to the target server. Adminer is available for MySQL, MariaDB, PostgreSQL, SQLite, MS SQL, Oracle, Elasticsearch, MongoDB and others via plugin.

**Shipped version:** 4.8.1~ynh3

**Demo:** https://demo.adminer.org/adminer.php?username=

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Configuration

You need to know the root password from here `/etc/yunohost/mysql` or the app username and password from `setting.yml` under `/etc/yunohost/apps/appname` to login.
For themes download the `adminer.css` from the main website and replace the file in the app folder.
If you have problems with drivers see here: https://www.adminer.org/en/drivers.

## Documentation and resources

* Official app website: https://www.adminer.org/
* Upstream app code repository: https://github.com/vrana/adminer/
* YunoHost documentation for this app: https://yunohost.org/app_adminer
* Report a bug: https://github.com/YunoHost-Apps/adminer_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/adminer_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
or
sudo yunohost app upgrade adminer -u https://github.com/YunoHost-Apps/adminer_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps