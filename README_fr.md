# Tiki pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/tiki.svg)](https://dash.yunohost.org/appci/app/tiki) ![](https://ci-apps.yunohost.org/ci/badges/tiki.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/tiki.maintain.svg)  
[![Installer Tiki avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=tiki)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Tiki rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

TikiWiki, est un système de gestion de contenu et une suite bureautique en ligne basée sur un wiki libre et open source. En plus de permettre les sites web et portails sur Internet et sur intranets et extranets, Tiki contient plusieurs fonctionnalités de collaboration lui permettant de fonctionner comme un système de gestion de contenu géospatial (GeoCMS) et application Web Groupware. s

**Version incluse :** 24.0~ynh1

**Démo :** https://tiki.org/Try-Tiki

## Captures d'écran

![](./doc/screenshots/Screenshot.png)

## Avertissements / informations importantes

Database credentials are sent by mail for the post installation. `http://example.org/tiki-install.php`
## Documentations et ressources

* Site officiel de l'app : https://tiki.org/
* Documentation officielle de l'admin : https://doc.tiki.org
* Dépôt de code officiel de l'app : https://gitlab.com/tikiwiki/tiki/
* Documentation YunoHost pour cette app : https://yunohost.org/app_tiki
* Signaler un bug : https://github.com/YunoHost-Apps/tiki_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/tiki_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/tiki_ynh/tree/testing --debug
ou
sudo yunohost app upgrade tiki -u https://github.com/YunoHost-Apps/tiki_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps