# Keeweb pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/keeweb.svg)](https://dash.yunohost.org/appci/app/keeweb)  
[![Installer Keeweb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=keeweb)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d'installer Keeweb rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, merci de regarder [ici](https://yunohost.org/#/install_fr) pour savoir comment l'installer et en profiter.*

## Résumé
Client Web pour la lecture et l'édition de fichiers Keepass en local. Il peut également synchroniser avec WebDAV (Owncloud, Nextcloud...), Dropbox, Google Drive, OneDrive....

**Version embarquée:** 1.7.7

## Captures d'écran

![](https://github.com/keeweb/keeweb/blob/master/img/screenshot.png)

## Démo

https://app.keeweb.info/

## Configuration

Utilisez Keeweb pour configurer.

## Documentation

 * Documentation officielle: https://github.com/keeweb/keeweb/wiki
 * Documentation YunoHost: Il n'y a pas d'autre documentation, n'hésitez pas à contribuer.

## Fonctionnalités spécifiques à YunoHost

#### Support multi-utilisateurs

Pas de support utilisateurs

#### Architectures supportées.

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/keeweb%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/keeweb/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/keeweb%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/keeweb/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/keeweb%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/keeweb/)

## Informations additionnelles

### Usage avec OwnCloud/NextCloud
1. Ouvrez votre fichier via webdav en utilisant https://linktoowncloud/remote.php/webdav/PATH-TO-YOUR-KDBX-FILE et votre nom d'utilisateur et votre mot de passe (pas besoin d'entrer votre nom d'utilisateur et votre mot de passe si vous utilisez un Keeweb privé, car il détectera automatiquement que vous êtes connecté dans OwnCloud/NextCloud

### Usage pour Dropbox sync
1. [Créer](https://www.dropbox.com/developers/apps/create) une app Dropbox
2. Trouver votre clé d'application (dans la page Dropbox App, allez à Paramètres/Clé d'application)
3. Entrer la clé de l'application lorsque vous y êtes invité

### Ajouter des fichiers par défaut sur votre page d'accueil
1. Lisez https://github.com/keeweb/keeweb/wiki/Configuration#json-app-config
2. Dans votre config.json ajoutez l'entrée "files" avec les paramètres appropriés

## Liens

 * Reporter un bug: https://github.com/YunoHost-Apps/keeweb_ynh/issues
 * Site de Keeweb: https://keeweb.info/
 * Site de YunoHost: https://yunohost.org/

---

Informations à l'intention des développeurs
----------------

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing).

Pour tester la branche testing, merci de procéder ainsi.
```
sudo yunohost app install https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --verbose
ou
sudo yunohost app upgrade keeweb -u https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --verbose
```
