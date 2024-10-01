<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Vore untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/vore.svg)](https://ci-apps.yunohost.org/ci/apps/vore/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/vore.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/vore.maintain.svg)

[![Pasang Vore dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vore)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Vore secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

A simple, multi-tenant feed reader

### Client:

- rss and atom support
- minimal, simple, reliable, fast
- refresh your feeds automatically
- display a chronological list of feed items


**Versi terkirim:** 2023.08.09~ynh2

**Demo:** <https://vore.website/j3s>

## Tangkapan Layar

![Tangkapan Layar pada Vore](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://git.j3s.sh/vore>
- Dokumentasi admin resmi: <https://j3s.sh/thought/vore-a-new-rss-feed-reader.html>
- Depot kode aplikasi hulu: <https://git.j3s.sh/vore/tree/main/>
- Gudang YunoHost: <https://apps.yunohost.org/app/vore>
- Laporkan bug: <https://github.com/YunoHost-Apps/vore_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/vore_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/vore_ynh/tree/testing --debug
atau
sudo yunohost app upgrade vore -u https://github.com/YunoHost-Apps/vore_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
