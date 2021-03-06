Seafile for Yunohost
============

Seafile is an open Source Cloud Storage application.

Official website: <http://seafile.com/>

Requirements
------------

Functionnal instance of [Yunohost](https://yunohost.org/#/)

Installation
------------

From command line:

`sudo yunohost app install -l Seafile https://github.com/YunoHost-Apps/seafile_ynh`

Upgrade
-------

From command line:

`sudo yunohost app upgrade -u https://github.com/YunoHost-Apps/seafile_ynh`

Infos
-----

Seafile server v5.0.3

Available for x64, i386, and Raspberry Pi architecture but only tested for x64 (feedback are welcome)

Seafile no longer distribute binary for generic armhf architectures but rpi binary could work.

/!\ To login use your yunohost email not your username.

License
-------

Seafile server and its desktop clients are published under GPLv2.

Mobile clients are published under the GPLv3.

The Seafile server's web end, i.e. Seahub, is published under the Apache License.

This package is published under MIT License

TODO
-----

 - Auto login/logout, see #1
 - Test of backup/restore script

Developper infos
----------------

Please do your pull request to the Dev branch.

Test or upgrade to dev version:
```
su - admin
git clone -b Dev https://github.com/YunoHost-Apps/seafile_ynh
# to install
sudo yunohost app install -l Seafile /home/admin/seafile_ynh
# to upgrade
sudo yunohost app upgrade -f /home/admin/seafile_ynh seafile

```
