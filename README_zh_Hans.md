<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Cjdns

[![集成程度](https://dash.yunohost.org/integration/cjdns.svg)](https://dash.yunohost.org/appci/app/cjdns) ![工作状态](https://ci-apps.yunohost.org/ci/badges/cjdns.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/cjdns.maintain.svg)

[![使用 YunoHost 安装 Cjdns](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=cjdns)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Cjdns。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Cjdns implements an encrypted IPv6 network using public-key cryptography for address allocation and a distributed hash table for routing. This provides near-zero-configuration networking, and prevents many of the security and scalability issues that plague existing networks.


**分发版本：** 22.7~ynh2

## 截图

![Cjdns 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 上游应用代码库： <https://github.com/cjdelisle/cjdns/>
- YunoHost 商店： <https://apps.yunohost.org/app/cjdns>
- 报告 bug： <https://github.com/YunoHost-Apps/cjdns_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
或
sudo yunohost app upgrade cjdns -u https://github.com/YunoHost-Apps/cjdns_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
