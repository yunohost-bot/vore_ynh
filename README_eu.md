<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Vore YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/vore.svg)](https://dash.yunohost.org/appci/app/vore) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/vore.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/vore.maintain.svg)

[![Instalatu Vore YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vore)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Vore YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

A simple, multi-tenant feed reader

### Client:

- rss and atom support
- minimal, simple, reliable, fast
- refresh your feeds automatically
- display a chronological list of feed items


**Paketatutako bertsioa:** 2023.08.09~ynh2

**Demoa:** <https://vore.website/j3s>

## Pantaila-argazkiak

![Vore(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://git.j3s.sh/vore>
- Administratzaileen dokumentazio ofiziala: <https://j3s.sh/thought/vore-a-new-rss-feed-reader.html>
- Jatorrizko aplikazioaren kode-gordailua: <https://git.j3s.sh/vore/tree/main/>
- YunoHost Denda: <https://apps.yunohost.org/app/vore>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/vore_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/vore_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/vore_ynh/tree/testing --debug
edo
sudo yunohost app upgrade vore -u https://github.com/YunoHost-Apps/vore_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
