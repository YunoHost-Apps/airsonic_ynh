<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Airsonic-Advanced YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/airsonic.svg)](https://dash.yunohost.org/appci/app/airsonic) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/airsonic.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/airsonic.maintain.svg)

[![Instalatu Airsonic-Advanced YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Airsonic-Advanced YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Airsonic-Advanced is a more modern implementation of the Airsonic fork with several key performance and feature enhancements. It adds and supersedes several features in Airsonic.

Airsonic is a free, web-based media streamer, providing ubiquitous access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously.

Airsonic is designed to handle very large music collections (hundreds of gigabytes). Although optimized for MP3 streaming, it works for any audio or video format that can stream over HTTP, for instance AAC and OGG. By using transcoder plug-ins, Airsonic supports on-the-fly conversion and streaming of virtually any audio format, including WMA, FLAC, APE, Musepack, WavPack and Shorten.

If you have constrained bandwidth, you may set an upper limit for the bit rate of the music streams. Airsonic will then automatically re sample the music to a suitable bit rate.

In addition to being a streaming media server, Airsonic works very well as a local jukebox. The intuitive web interface, as well as search and index facilities, are optimized for efficient browsing through large media libraries. Airsonic also comes with an integrated Podcast receiver, with many of the same features as you find in iTunes.


**Paketatutako bertsioa:** 11.0.0~ynh5

## Pantaila-argazkiak

![Airsonic-Advanced(r)en pantaila-argazkia](./doc/screenshots/screenshot_01.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://airsonic.github.io/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/airsonic-advanced/airsonic-advanced>
- YunoHost Denda: <https://apps.yunohost.org/app/airsonic>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/airsonic_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
edo
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
