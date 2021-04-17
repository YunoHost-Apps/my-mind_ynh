# My Mind for YunoHost

[![Integration level](https://dash.yunohost.org/integration/my-mind.svg)](https://dash.yunohost.org/appci/app/my-mind) ![](https://ci-apps.yunohost.org/ci/badges/my-mind.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/my-mind.maintain.svg)  
[![Install My Mind with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=my-mind)

> *This package allow you to install My Mind quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
My Mind is a web application for creating and managing Mind maps. It is free to use and you can fork its source code. It is distributed under the terms of the MIT license.
New to mind maps? They are useful, aesthetic and cool! Read more about these special diagrams in [the Wikipedia article](http://en.wikipedia.org/wiki/Mind_map).

**Shipped version:** 1.2

## Screenshots

![](https://github.com/ondras/my-mind/blob/master/screenshot.png)

## Demo

* [Official demo](http://my-mind.github.io/?map=examples/features.mymind)

## Documentation

 * Official documentation: https://github.com/ondras/my-mind/wiki
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-user support

 * Are LDAP and HTTP auth supported? **No**
 * Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/my-mind.svg)](https://ci-apps.yunohost.org/ci/apps/my-mind/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/my-mind.svg)](https://ci-apps-arm.yunohost.org/ci/apps/my-mind/)

## Limitations

* Any known limitations.

## Additional information

* Other info you would like to add about this app.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/my-mind_ynh/issues
 * App website: http://my-mind.github.io/
 * Upstream app repository: https://github.com/ondras/my-mind
 * YunoHost website: https://yunohost.org/

---

## Developers infos

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/my-mind_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/my-mind_ynh/tree/testing --debug
or
sudo yunohost app upgrade my-mind -u https://github.com/YunoHost-Apps/my-mind_ynh/tree/testing --debug
```
