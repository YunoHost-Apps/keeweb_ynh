<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Keeweb YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/keeweb.svg)](https://dash.yunohost.org/appci/app/keeweb) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/keeweb.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/keeweb.maintain.svg)

[![Instalatu Keeweb YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=keeweb)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Keeweb YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

This webapp is a browser password manager compatible with KeePass databases. It doesn't require any server or additional resources.

**Paketatutako bertsioa:** 1.18.8~ynh2

**Demoa:** <https://app.keeweb.info/>

## Pantaila-argazkiak

![Keeweb(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://keeweb.info/>
- Administratzaileen dokumentazio ofiziala: <https://github.com/keeweb/keeweb/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/keeweb/keeweb>
- YunoHost Denda: <https://apps.yunohost.org/app/keeweb>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/keeweb_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
edo
sudo yunohost app upgrade keeweb -u https://github.com/YunoHost-Apps/keeweb_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
