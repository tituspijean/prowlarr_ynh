# Prowlarr pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/prowlarr.svg)](https://dash.yunohost.org/appci/app/prowlarr) ![](https://ci-apps.yunohost.org/ci/badges/prowlarr.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/prowlarr.maintain.svg)  
[![Installer Prowlarr avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=prowlarr)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Prowlarr rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Gestion complète de vos indexeurs pour Radarr, Sonarr, Lidarr, ...

**Version incluse :** 0.1.10.1375~ynh1



## Captures d'écran

![](./doc/screenshots/screenshot.jpg)

## Avertissements / informations importantes

* Les architectures compatibles sont `arm`, `arm64`, et `amd64`
* Le contrôle de l'accès se fait avec le système de permissions de YunoHost.
  * L'API (`domain.tld/path/api`) est accessible aux visiteurs pour permettre le contrôle via des clients externes.

## Documentations et ressources

* Site officiel de l'app : https://prowlarr.com
* Documentation officielle de l'admin : https://wiki.servarr.com/prowlarr
* Dépôt de code officiel de l'app : https://github.com/Prowlarr/Prowlarr
* Documentation YunoHost pour cette app : https://yunohost.org/app_prowlarr
* Signaler un bug : https://github.com/YunoHost-Apps/prowlarr_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/prowlarr_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/prowlarr_ynh/tree/testing --debug
ou
sudo yunohost app upgrade prowlarr -u https://github.com/YunoHost-Apps/prowlarr_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps