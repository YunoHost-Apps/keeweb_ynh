# Keeweb for YunoHost

[![Integration level](https://dash.yunohost.org/integration/keeweb.svg)](https://dash.yunohost.org/appci/app/keeweb)  
[![Install Keeweb with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=keeweb)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Keeweb quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Web client for reading and editing Keepass files locally. It can also sync with WebDAV (Owncloud, Nextcloud...), Dropbox, Google Drive, OneDrive...

**Shipped version:** 1.6.3

## Screenshots

![](https://github.com/keeweb/keeweb/blob/master/img/screenshot.png)

## Demo

https://app.keeweb.info/

## Configuration

Use the web panel of Keeweb to configure it.

## Documentation

 * Official documentation: https://github.com/keeweb/keeweb/wiki
 * YunoHost documentation: There no other documentations, feel free to contribute.

## YunoHost specific features

#### Multi-users support

No users support.

#### Supported architectures

* x86-64b - ![](https://ci-apps.yunohost.org/ci/logs/keeweb%20%28Community%29.svg)
* ARMv8-A - ![](https://ci-apps-arm.yunohost.org/ci/logs/keeweb%20%28Community%29.svg)
* Jessie x86-64b - ![](https://ci-stretch.nohost.me/ci/logs/keeweb%20%28Community%29.svg)

## Additionnal informations

### Usage with OwnCloud/NextCloud
1. Open your file through webdav using https://linktoowncloud/remote.php/webdav/PATH-TO-YOUR-KDBX-FILE and your username and password (no need to enter username and password if you are using a private Keeweb, as it will automatically detect that you are logged in OwnCloud/NextCloud

### Usage for Dropbox sync
1. [create](https://www.dropbox.com/developers/apps/create) a Dropbox app
2. find your app key (in Dropbox App page, go to Settings/App key)
3. Enter the app key when prompted

### Add default files on your homepage
1. Read https://github.com/keeweb/keeweb/wiki/Configuration#json-app-config
2. In your config.json add the "files" entry with the appropriate settings

## Links

 * Report a bug: https://github.com/YunoHost-Apps/keeweb_ynh/issues
 * Keeweb website: https://keeweb.info/
 * YunoHost website: https://yunohost.org/

---

Developers infos
----------------

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --verbose
or
sudo yunohost app upgrade keeweb -u https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --verbose
```
