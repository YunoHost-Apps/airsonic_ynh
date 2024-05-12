<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Airsonic-Advanced para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/airsonic.svg)](https://dash.yunohost.org/appci/app/airsonic) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/airsonic.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/airsonic.maintain.svg)

[![Instalar Airsonic-Advanced con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarAirsonic-Advanced rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

Airsonic-Advanced is a more modern implementation of the Airsonic fork with several key performance and feature enhancements. It adds and supersedes several features in Airsonic.

Airsonic is a free, web-based media streamer, providing ubiquitous access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously.

Airsonic is designed to handle very large music collections (hundreds of gigabytes). Although optimized for MP3 streaming, it works for any audio or video format that can stream over HTTP, for instance AAC and OGG. By using transcoder plug-ins, Airsonic supports on-the-fly conversion and streaming of virtually any audio format, including WMA, FLAC, APE, Musepack, WavPack and Shorten.

If you have constrained bandwidth, you may set an upper limit for the bit rate of the music streams. Airsonic will then automatically re sample the music to a suitable bit rate.

In addition to being a streaming media server, Airsonic works very well as a local jukebox. The intuitive web interface, as well as search and index facilities, are optimized for efficient browsing through large media libraries. Airsonic also comes with an integrated Podcast receiver, with many of the same features as you find in iTunes.


**Versión actual:** 11.0.0~ynh5

## Capturas

![Captura de Airsonic-Advanced](./doc/screenshots/screenshot_01.png)

## Documentaciones y recursos

- Documentación administrador oficial: <https://airsonic.github.io/docs/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/airsonic-advanced/airsonic-advanced>
- Catálogo YunoHost: <https://apps.yunohost.org/app/airsonic>
- Reportar un error: <https://github.com/YunoHost-Apps/airsonic_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
o
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
