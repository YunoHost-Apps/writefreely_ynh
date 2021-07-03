# WriteFreely pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/writefreely.svg)](https://dash.yunohost.org/appci/app/writefreely) ![](https://ci-apps.yunohost.org/ci/badges/writefreely.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/writefreely.maintain.svg)  
[![Installer WriteFreely avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=writefreely)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer WriteFreely rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Permet de créer un blog fédéré minimaliste ou une communauté entière.

**Version incluse :** 0.13.1~ynh1

**Démo :** https://write.as/new

## Captures d'écran

![](./doc/screenshots/screenshots2.png)
![](./doc/screenshots/screenshots1.png)

## Avertissements / informations importantes

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * **WriteFreely** require a dedicated **root domain**, eg. writefreely.domain.tld
    * i386 architectures not supported
    * No LDAP and no HTTP auth supported

* Other infos that people should be aware of, such as:
    * If User Mode is configured Multiple users, the app be used by multiple users
    * Additionals parameters can be configured in Settings / Admin settings.

## Documentations et ressources

* Site officiel de l'app : https://writefreely.org
* Documentation officielle utilisateur : https://writefreely.org/start
* Dépôt de code officiel de l'app : https://github.com/writeas/writefreely
* Documentation YunoHost pour cette app : https://yunohost.org/app_writefreely
* Signaler un bug : https://github.com/YunoHost-Apps/writefreely_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing --debug
ou
sudo yunohost app upgrade writefreely -u https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps