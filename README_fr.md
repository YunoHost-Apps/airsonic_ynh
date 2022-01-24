# Airsonic pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/airsonic.svg)](https://dash.yunohost.org/appci/app/airsonic) ![](https://ci-apps.yunohost.org/ci/badges/airsonic.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/airsonic.maintain.svg)  
[![Installer Airsonic avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Airsonic rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Streamez et gérez votre collection de musique

**Version incluse :** 10.6.0~ynh1

**Démo :** https://airsonic.github.io/demo/

## Captures d'écran

![](./doc/screenshots/screenshot_01.png)

## Avertissements / informations importantes

## Fonctionnalités spécifiques à YunoHost

* Comptes LDAP YunoHost pris en charge : **oui**
* [Multimédia](https://github.com/YunoHost-Apps/yunohost.multimedia) géré
* Limite de mémoire RAM fixée à 256 Mb car Airsonic quittait souvant par manque de RAM (bonjour OOM killer)
* Voir https://www.reddit.com/r/airsonic/comments/doscco/jvm_memory_issues/ 
## Documentations et ressources

* Site officiel de l'app : https://airsonic.github.io/
* Documentation officielle de l'admin : https://airsonic.github.io/docs/
* Dépôt de code officiel de l'app : https://github.com/airsonic/airsonic
* Documentation YunoHost pour cette app : https://yunohost.org/app_airsonic
* Signaler un bug : https://github.com/YunoHost-Apps/airsonic_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
ou
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps