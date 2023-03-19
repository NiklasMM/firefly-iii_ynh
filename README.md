<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Firefly III for YunoHost

[![Integration level](https://dash.yunohost.org/integration/firefly-iii.svg)](https://dash.yunohost.org/appci/app/firefly-iii) ![Working status](https://ci-apps.yunohost.org/ci/badges/firefly-iii.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/firefly-iii.maintain.svg)

[![Install Firefly III with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=firefly-iii)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Firefly III quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

"Firefly III" is a (self-hosted) manager for your personal finances. It can help you keep track of your expenses and income, so you can spend less and save more. Firefly III supports the use of budgets, categories and tags. Using a bunch of external tools, you can import data. It also has many neat financial reports available.

Firefly III should give you insight into and control over your finances. Money should be useful, not scary. You should be able to see where it is going, to feel your expenses and to... wow, I'm going overboard with this aren't I?

But you get the idea: this is your money. These are your expenses. Stop them from controlling you. I built this tool because I started to dislike money. Having money, not having money, paying bills with money, you get the idea. But no more. I want to feel "safe", whatever my balance is. And I hope this tool can help you. I know it helps me.


**Shipped version:** 6.0.5~ynh1

**Demo:** https://demo.firefly-iii.org/login

## Screenshots

![Screenshot of Firefly III](./doc/screenshots/imac-complete.png)

## Documentation and resources

* Official app website: <https://firefly-iii.org/>
* Official admin documentation: <https://docs.firefly-iii.org/firefly-iii/about-firefly-iii/introduction/>
* Upstream app code repository: <https://github.com/firefly-iii/firefly-iii>
* YunoHost documentation for this app: <https://yunohost.org/app_firefly-iii>
* Report a bug: <https://github.com/YunoHost-Apps/firefly-iii_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/firefly-iii_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/firefly-iii_ynh/tree/testing --debug
or
sudo yunohost app upgrade firefly-iii -u https://github.com/YunoHost-Apps/firefly-iii_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
