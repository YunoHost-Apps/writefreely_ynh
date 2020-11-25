# WriteFreely for YunoHost

[![Integration level](https://dash.yunohost.org/integration/writefreely.svg)](https://dash.yunohost.org/appci/app/writefreely) ![](https://ci-apps.yunohost.org/ci/badges/writefreely.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/writefreely.maintain.svg)  
[![Install WriteFreely with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=writefreely)

> *This package allow you to install WriteFreely quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
WriteFreely is a beautifully pared-down blogging platform that's simple on the surface, yet powerful underneath.

Can be run as Single User Blog or Multi User Instance.

Each User can be limited from 1 to unlimited blogs.

**Shipped version:** 0.12.0

## Important points to read before installing

**WriteFreely** require a dedicated **root domain**, eg. writefreely.domain.tld

## Screenshots

![writefreely-screenshot](https://writefreely.org/img/screens/pencil-reader.png)

## Demo

* [Official demo](https://write.as/new)

## Configuration

Additionals parameters can be configure in Settings / admin settings.

## Documentation

 * Official documentation: https://writefreely.org/start

## YunoHost specific features

#### Multi-users support

No LDAP and no HTTP auth supported

If User Mode is configured Multiple users, the app be used by multiple users

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/writefreely%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/writefreely/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/writefreely%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/writefreely/)

## Limitations

* No known limitations.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/writefreely_ynh/issues
 * App website: https://writefreely.org/
 * Upstream app repository: https://github.com/writeas/writefreely
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing --debug
or
sudo yunohost app upgrade writefreely -u https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing --debug
```
