<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 的 Vore

[![集成程度](https://dash.yunohost.org/integration/vore.svg)](https://dash.yunohost.org/appci/app/vore) ![工作状态](https://ci-apps.yunohost.org/ci/badges/vore.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/vore.maintain.svg)

[![使用 YunoHost 安装 Vore](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=vore)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Vore。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

A simple, multi-tenant feed reader

### Client:

- rss and atom support
- minimal, simple, reliable, fast
- refresh your feeds automatically
- display a chronological list of feed items


**分发版本：** 2023.08.09~ynh2

**演示：** <https://vore.website/j3s>

## 截图

![Vore 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <https://git.j3s.sh/vore>
- 官方管理文档： <https://j3s.sh/thought/vore-a-new-rss-feed-reader.html>
- 上游应用代码库： <https://git.j3s.sh/vore/tree/main/>
- YunoHost 商店： <https://apps.yunohost.org/app/vore>
- 报告 bug： <https://github.com/YunoHost-Apps/vore_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/vore_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/vore_ynh/tree/testing --debug
或
sudo yunohost app upgrade vore -u https://github.com/YunoHost-Apps/vore_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
