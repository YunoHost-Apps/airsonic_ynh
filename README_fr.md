<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Airsonic-Advanced pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/airsonic.svg)](https://dash.yunohost.org/appci/app/airsonic) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/airsonic.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/airsonic.maintain.svg)

[![Installer Airsonic-Advanced avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Airsonic-Advanced rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Airsonic-Advanced est une implémentation plus moderne de la bifurcation d'Airsonic avec plusieurs améliorations clés en termes de performances et de fonctionnalités. Elle ajoute et remplace plusieurs fonctionnalités d'Airsonic.

Airsonic est un streamer multimédia gratuit, basé sur le web, qui fournit un accès omniprésent à votre musique. Utilisez-le pour partager votre musique avec vos amis, ou pour écouter votre propre musique au travail. Vous pouvez diffuser votre musique sur plusieurs lecteurs simultanément.

Airsonic est conçu pour gérer de très grandes collections de musique (des centaines de gigaoctets). Bien qu'il soit optimisé pour le streaming MP3, il fonctionne pour tout format audio ou vidéo pouvant être diffusé par HTTP, par exemple AAC et OGG. En utilisant des plug-ins de transcodage, Airsonic prend en charge la conversion et le streaming à la volée de pratiquement tous les formats audio, notamment WMA, FLAC, APE, Musepack, WavPack et Shorten.

Si vous avez une bande passante limitée, vous pouvez fixer une limite supérieure pour le débit binaire des flux musicaux. Airsonic rééchantillonnera alors automatiquement la musique à un débit binaire approprié.

En plus d'être un serveur de médias en streaming, Airsonic fonctionne très bien comme un jukebox local. L'interface web intuitive, ainsi que les fonctions de recherche et d'indexation, sont optimisées pour une navigation efficace dans les grandes bibliothèques de médias. Airsonic est également livré avec un récepteur de podcasts intégré, avec la plupart des fonctionnalités que vous trouvez dans iTunes.


**Version incluse :** 11.0.0~ynh5

## Captures d’écran

![Capture d’écran de Airsonic-Advanced](./doc/screenshots/screenshot_01.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://airsonic.github.io/docs/>
- Dépôt de code officiel de l’app : <https://github.com/airsonic-advanced/airsonic-advanced>
- YunoHost Store : <https://apps.yunohost.org/app/airsonic>
- Signaler un bug : <https://github.com/YunoHost-Apps/airsonic_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
ou
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
