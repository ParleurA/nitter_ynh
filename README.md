<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Nitter for YunoHost

[![Integration level](https://dash.yunohost.org/integration/nitter.svg)](https://dash.yunohost.org/appci/app/nitter) ![Working status](https://ci-apps.yunohost.org/ci/badges/nitter.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/nitter.maintain.svg)  
[![Install Nitter with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=nitter)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Nitter quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A free and open source alternative Twitter front-end focused on privacy and performance.
Inspired by the Invidious project.

### Features
- No JavaScript or ads
- All requests go through the backend, client never talks to Twitter
- Prevents Twitter from tracking your IP or JavaScript fingerprint
- Uses Twitter's unofficial API (no rate limits or developer account required)
- Lightweight (for @nim_lang, 60KB vs 784KB from twitter.com)
- RSS feeds
- Themes
- Mobile support (responsive design)


**Shipped version:** 2022.06.19~ynh1

**Demo:** https://nitter.net/

## Screenshots

![Screenshot of Nitter](./doc/screenshots/screenshot.png)

## Disclaimers / important information

### Configuration

Nitter config file is stored in `/opt/yunohost/nitter/nitter.conf` (for the first instance, subsequent installs will go in `nitter__2`, `nitter__3`, etc). Users can override the defaults and set custom settings at `https://instance-domain.tld/settings`.
## Documentation and resources

* Official app website: <https://nitter.net/>
* Official admin documentation: <https://github.com/zedeus/nitter/wiki>
* Upstream app code repository: <https://github.com/zedeus/nitter>
* YunoHost documentation for this app: <https://yunohost.org/app_nitter>
* Report a bug: <https://github.com/YunoHost-Apps/nitter_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/nitter_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/nitter_ynh/tree/testing --debug
or
sudo yunohost app upgrade nitter -u https://github.com/YunoHost-Apps/nitter_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
