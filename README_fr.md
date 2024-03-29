<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Keeweb pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/keeweb.svg)](https://dash.yunohost.org/appci/app/keeweb) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/keeweb.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/keeweb.maintain.svg)

[![Installer Keeweb avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=keeweb)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Keeweb rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

This webapp is a browser password manager compatible with KeePass databases. It doesn't require any server or additional resources.

**Version incluse :** 1.18.8~ynh2

**Démo :** <https://app.keeweb.info/>

## Captures d’écran

![Capture d’écran de Keeweb](./doc/screenshots/screenshot.png)

## Documentations et ressources

- Site officiel de l’app : <https://keeweb.info/>
- Documentation officielle de l’admin : <https://github.com/keeweb/keeweb/wiki>
- Dépôt de code officiel de l’app : <https://github.com/keeweb/keeweb>
- YunoHost Store : <https://apps.yunohost.org/app/keeweb>
- Signaler un bug : <https://github.com/YunoHost-Apps/keeweb_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
ou
sudo yunohost app upgrade keeweb -u https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
