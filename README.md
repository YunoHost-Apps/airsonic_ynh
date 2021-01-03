# Airsonic for YunoHost

[![Integration level](https://dash.yunohost.org/integration/airsonic.svg)](https://dash.yunohost.org/appci/app/airsonic) ![](https://ci-apps.yunohost.org/ci/badges/airsonic.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/airsonic.maintain.svg)  
[![Install Airsonic with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=airsonic)

> *This package allow you to install Airsonic quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview

Airsonic is a free, web-based media streamer, providing ubiquitous access to your music. Use it to share your music with friends, or to listen to your own music while at work. You can stream to multiple players simultaneously, for instance to one player in your kitchen and another in your living room.

Airsonic is designed to handle very large music collections (hundreds of gigabytes). Although optimized for MP3 streaming, it works for any audio or video format that can stream over HTTP, for instance AAC and OGG. By using transcoder plug-ins, Airsonic supports on-the-fly conversion and streaming of virtually any audio format, including WMA, FLAC, APE, Musepack, WavPack and Shorten.

If you have constrained bandwidth, you may set an upper limit for the bit rate of the music streams. Airsonic will then automatically re sample the music to a suitable bit rate.

In addition to being a streaming media server, Airsonic works very well as a local jukebox. The intuitive web interface, as well as search and index facilities, are optimized for efficient browsing through large media libraries. Airsonic also comes with an integrated Podcast receiver, with many of the same features as you find in iTunes.

**Shipped version:** 10.6.2

## Screenshots

![Sreenshot of home page of Airsonic](screenshot_01.png)

## Demo

* [Official demo](https://airsonic.github.io/demo/)

## Configuration

How to configure this app: by an admin panel.

## Documentation

* Official documentation: https://airsonic.github.io/docs

## YunoHost specific features

* YunoHost LDAP accounts supported: you can login with them
* [Multimedia](https://github.com/YunoHost-Apps/yunohost.multimedia) handled
* Memory RAM limit set to 256 MB because Airsonic was often killed by lack of RAM (hello OOM killer)
  * See https://www.reddit.com/r/airsonic/comments/doscco/jvm_memory_issues/

## Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/airsonic%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/airsonic/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/airsonic%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/airsonic/)

## Links

* Report a bug: https://github.com/YunoHost-Apps/airsonic_ynh/issues
* App website: https://airsonic.github.io/
* Upstream app repository: https://github.com/airsonic/airsonic
* YunoHost website: https://yunohost.org/

---

## Developers info

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing).

To try the testing branch, please proceed like that.

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
or
sudo yunohost app upgrade airsonic -u https://github.com/YunoHost-Apps/airsonic_ynh/tree/testing --debug
```
