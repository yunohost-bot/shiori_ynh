<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# Shiori for YunoHost

[![Integration level](https://dash.yunohost.org/integration/shiori.svg)](https://dash.yunohost.org/appci/app/shiori) ![Working status](https://ci-apps.yunohost.org/ci/badges/shiori.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/shiori.maintain.svg)

[![Install Shiori with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shiori)

*[Read this README is other languages.](./ALL_README.md)*

> *This package allows you to install Shiori quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

Shiori is a simple bookmarks manager written in Go language. Intended as a simple clone of Pocket. You can use it as command line application or as web application. This application is distributed as a single binary, which means it can be installed and used easily.

### Features

- Simple and clean command line interface.
- Basic bookmarks management i.e. add, edit and delete.
- Search bookmarks by their title, tags, URL and page content.
- Import and export bookmarks from and to Netscape Bookmark file.
- Simple web interface for those who don't want to use a command line app.
- Where possible, by default shiori will download a static copy of the webpage in simple text and HTML format, which later can be used as an offline archive for that page.


**Shipped version:** 1.6.1~ynh1

## Screenshots

![Screenshot of Shiori](./doc/screenshots/screenshot.png)

## Documentation and resources

- Official user documentation: <https://github.com/go-shiori/shiori/wiki/Usage>
- Official admin documentation: <https://github.com/go-shiori/shiori/wiki>
- Upstream app code repository: <https://github.com/go-shiori/shiori>
- YunoHost Store: <https://apps.yunohost.org/app/shiori>
- Report a bug: <https://github.com/YunoHost-Apps/shiori_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/shiori_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
or
sudo yunohost app upgrade shiori -u https://github.com/YunoHost-Apps/shiori_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
