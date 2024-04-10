<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# Airsonic-Advanced para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/airsonic.svg)](https://dash.yunohost.org/appci/app/airsonic) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/airsonic.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/airsonic.maintain.svg)

[![Instalar Airsonic-Advanced con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar Airsonic-Advanced de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

Airsonic-Advanced is a more modern implementation of the Airsonic fork with several key performance and feature enhancements. It adds and supersedes several features in Airsonic.

Airsonic is a free, web-based media streamer, providing ubiquitous access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously.

Airsonic is designed to handle very large music collections (hundreds of gigabytes). Although optimized for MP3 streaming, it works for any audio or video format that can stream over HTTP, for instance AAC and OGG. By using transcoder plug-ins, Airsonic supports on-the-fly conversion and streaming of virtually any audio format, including WMA, FLAC, APE, Musepack, WavPack and Shorten.

If you have constrained bandwidth, you may set an upper limit for the bit rate of the music streams. Airsonic will then automatically re sample the music to a suitable bit rate.

In addition to being a streaming media server, Airsonic works very well as a local jukebox. The intuitive web interface, as well as search and index facilities, are optimized for efficient browsing through large media libraries. Airsonic also comes with an integrated Podcast receiver, with many of the same features as you find in iTunes.


**Versión proporcionada:** 11.0.0~ynh5

## Capturas de pantalla

![Captura de pantalla de Airsonic-Advanced](./doc/screenshots/screenshot_01.png)

## Documentación e recursos

- Documentación oficial para admin: <https://airsonic.github.io/docs/>
- Repositorio de orixe do código: <https://github.com/airsonic-advanced/airsonic-advanced>
- Tenda YunoHost: <https://apps.yunohost.org/app/airsonic>
- Informar dun problema: <https://github.com/YunoHost-Apps/airsonic_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
ou
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
