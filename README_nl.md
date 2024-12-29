<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Airsonic-Advanced voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/airsonic)](https://ci-apps.yunohost.org/ci/apps/airsonic/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/airsonic)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/airsonic)

[![Airsonic-Advanced met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Airsonic-Advanced snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

Airsonic-Advanced is a more modern implementation of the Airsonic fork with several key performance and feature enhancements. It adds and supersedes several features in Airsonic.

Airsonic is a free, web-based media streamer, providing ubiquitous access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously.

Airsonic is designed to handle very large music collections (hundreds of gigabytes). Although optimized for MP3 streaming, it works for any audio or video format that can stream over HTTP, for instance AAC and OGG. By using transcoder plug-ins, Airsonic supports on-the-fly conversion and streaming of virtually any audio format, including WMA, FLAC, APE, Musepack, WavPack and Shorten.

If you have constrained bandwidth, you may set an upper limit for the bit rate of the music streams. Airsonic will then automatically re sample the music to a suitable bit rate.

In addition to being a streaming media server, Airsonic works very well as a local jukebox. The intuitive web interface, as well as search and index facilities, are optimized for efficient browsing through large media libraries. Airsonic also comes with an integrated Podcast receiver, with many of the same features as you find in iTunes.


**Geleverde versie:** 11.0.20240424015024~ynh1

## Schermafdrukken

![Schermafdrukken van Airsonic-Advanced](./doc/screenshots/screenshot_01.png)

## Documentatie en bronnen

- Officiele beheerdersdocumentatie: <https://airsonic.github.io/docs/>
- Upstream app codedepot: <https://github.com/airsonic-advanced/airsonic-advanced>
- YunoHost-store: <https://apps.yunohost.org/app/airsonic>
- Meld een bug: <https://github.com/YunoHost-Apps/airsonic_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
of
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
