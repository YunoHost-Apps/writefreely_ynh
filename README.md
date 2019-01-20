# writefreely_ynh

[![Integration level](https://dash.yunohost.org/integration/writefreely.svg)](https://ci-apps.yunohost.org/jenkins/job/writefreely%20%28Community%29/lastBuild/consoleFull)  
[![Install WriteFreely with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=writefreely)

> *This package allow you to install WriteFreely quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
WriteFreely is a beautifully pared-down blogging platform that's simple on the surface, yet powerful underneath.

Can be run as Single User Blog or Multi User Instance.

Each User can be limited from 1 to unlimited blogs.

**Shipped version:** 0.70

## Licence

LICENSE GPL-3.0

## Demo

* [Official demo](https://write.as/new)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * [Official documentation](https://writefreely.org/start)

#### Multi-users support

No LDAP and no HTTP auth supported

Depending of the configuration, the app be used by multiple users

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/writefreely%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/writefreely%20(Community)/)
* ~~ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/writefreely%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/writefreely%20(Community)%20(%7EARM%7E)/)~~
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/jenkins/job/writefreely%20(Community)/badge/icon)](https://ci-stretch.nohost.me/jenkins/job/writefreely%20(Community)/)

## Limitations

* Any known limitations.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/writefreely_ynh/issues
 * App website: https://writefreely.org/
 * GitHub website: https://github.com/writeas/writefreely
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing --debug
or
sudo yunohost app upgrade writefreely -u https://github.com/YunoHost-Apps/writefreely_ynh/tree/testing --debug
```
