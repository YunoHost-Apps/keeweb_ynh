# Keeweb pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/keeweb.svg)](https://dash.yunohost.org/appci/app/keeweb) ![](https://ci-apps.yunohost.org/ci/badges/keeweb.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/keeweb.maintain.svg)  
[![Installer Keeweb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=keeweb)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Keeweb rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Gestionnaire de mots de passe compatible avec KeePass

**Version incluse :** 1.18.7~ynh1

**Démo :** https://app.keeweb.info/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Documentations et ressources

* Site officiel de l'app : https://keeweb.info/
* Documentation officielle de l'admin : https://github.com/keeweb/keeweb/wiki
* Dépôt de code officiel de l'app : https://github.com/keeweb/keeweb
* Documentation YunoHost pour cette app : https://yunohost.org/app_keeweb
* Signaler un bug : https://github.com/YunoHost-Apps/keeweb_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade keeweb -u https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps