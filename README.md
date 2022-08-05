<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Invidious for YunoHost

[![Integration level](https://dash.yunohost.org/integration/invidious.svg)](https://dash.yunohost.org/appci/app/invidious) ![Working status](https://ci-apps.yunohost.org/ci/badges/invidious.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/invidious.maintain.svg)  
[![Install Invidious with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=invidious)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Invidious quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Invidious is an interface allowing access to Youtube videos without going through youtube.com
In addition to constituting an advantage in terms of confidentiality (the data does not pass directly through the services of the giant), this interface offers several features:
- Audio only mode,
- Dark mode,
- Ability to display Reddit comments instead of YouTube comments,
- Ability to subscribe to channels without creating a Google account 


**Shipped version:** 22.08.05~ynh1

**Demo:** https://invidious.site/

## Screenshots

![Screenshot of Invidious](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Configuration

You can configure Invidious by modifying the configuration file `/var/www/invidious/config/config.yml` with the help of this [documentation](https://docs.invidious.io/Configuration.md).

## Limitations

* Invidious needs more than 2GB of RAM to build.

## Documentation and resources

* Official user documentation: <https://github.com/iv-org/documentation>
* Official admin documentation: <https://docs.invidious.io/>
* Upstream app code repository: <https://github.com/iv-org/invidious>
* YunoHost documentation for this app: <https://yunohost.org/app_invidious>
* Report a bug: <https://github.com/YunoHost-Apps/invidious_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/invidious_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/invidious_ynh/tree/testing --debug
or
sudo yunohost app upgrade invidious -u https://github.com/YunoHost-Apps/invidious_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
