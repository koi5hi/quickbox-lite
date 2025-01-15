## CHANGELOG v1.5.11

*Changelog update Friday, Jan 10, 2025*

### General additions

- Support Ubuntu 24.04

### Important changes

- Discarding the Debian 10 LTS installation ([Release EOL](https://lists.debian.org/debian-lts-announce/2024/05/msg00002.html))
- Discarding Deluge 1.3.15 on all OS versions

### Function improved

- Use Static build for all qBitTorrent version
- Transmission 4 is available

### Function updated

- quickbox backend dependency (by Tautcony)
- qBittorrent default version upgraded to v4.6.7
- Transmission WebUI now use TrguiNG by default
- Python dependency default version upgraded to v3.12.x
- `box update flexget -v <VERSION>` can be used to specify version

### Bug fixed

- Fix broken btsync installer
- Fix broken ruTorrent installer
- Fix broken noVNC installer
- Fix broken h5ai download url

---

## CHANGELOG v1.5.10

*Changelog update Wednesday, Apr 3, 2024*

### General additions

- Support qBittorrent-Clientblocker

### Important changes

- Discarding the Ubuntu 18.04 installation ([Release EOL](https://wiki.ubuntu.com/Releases))

### Function improved

- Migrating Panel State Refresh to React (by Tautcony)

### Function updated

- qBittorrent default version upgraded to v4.5.5
- Transmission default version upgrade to v3.0
- Python dependency default version upgraded to v3.11.x

### Bug fixed

- Fix broken Netdata installer
- Fix broken ZNC installer

---

## CHANGELOG v1.5.9

*Changelog update Sunday, Dec 10, 2023*

### General additions

- facilitating the selection of the Transmission version during installation(`--transmission-version`)

### Function improved

- resolving dependency issues by installing DenyHosts using venv
- only use released tag on acme.sh
- apply new node.js repo

### Function updated

- add writable flag to [newer ttyd](https://github.com/tsl0922/ttyd/commit/f8efcddb0b615de7086fdb3c5f452d1ee42f32a3)
- disable webUI UPNP on qBittorrent by default

### Bug fixed

---

## CHANGELOG v1.5.8

*Changelog update Thursday, Jul 27, 2023*

### General additions

- support Debian 12.
- support Deluge 2.1.x.
- support [SABnzbd](https://sabnzbd.org/).

### Function improved

- update vnstat statistics on dashbaord (by Tautcony).
- update qBittorrent systemd service.
- use venv for denyhosts.

### Function updated

- update node.js to v18.
- update dashboard dependency.

### Bug fixed

---

## CHANGELOG v1.5.7

*Changelog update Friday, Mar 03, 2023*

### General additions

- support h5ai to generate a shared index.

### Function improved

- update qBittorrent systemd config

### Function updated

- ruTorrent update to v4.x
- update dashboard dependency

### Bug fixed

---

## CHANGELOG v1.5.6

*Changelog update Tuesday,Sep 27, 2022*

### General additions

- support Emby
- support Jellyfin

### Function improved

- use docker compose to manage filebrowser-ee service

### Function updated

- install latest filebrowser binary by default

### Bug fixed

- fix broken dependency (deluge)

---

## CHANGELOG v1.5.5

*Changelog update Wednesday, Jul 20, 2022*

### General additions

- support rclone rcd WebUI
- support WebDAV (Rclone backend)

### Function improved

### Function updated

### Bug fixed

- fix vnstat statistics on dashbaord (by Tautcony)
- fix wrong memory statistics on dashbaord
- fix update FlexGet script

---

## CHANGELOG v1.5.4

*Changelog update Friday, May 27, 2022*

### General additions

- support ubuntu 22.04

### Function improved

- better implemented vnstat statistics on dashbaord (by Tautcony)
- replace outdated `apt-key` with `/etc/apt/trusted.gpg.d/`

### Function updated

- install qBittorrent v4.3.9 by default

### Bug fixed

- add submodule when compiling Netdata
- wrong permission in ruTorrent install and upgrade script

---

## CHANGELOG v1.5.3

*Changelog update Sunday, Mar 27, 2022*

### General additions

- support Transmission v3.0

### Function improved

- use motd instead of bashrc information

### Function updated

- nfs only run with private IP address by default

### Bug fixed

- fix qBittorrent static script
- fix switch branch button on dashboard

---

## CHANGELOG v1.5.2

*Changelog update Saturday, Jan 1, 2022*

### General additions

- add reset button in panel (by Tautcony)

### Function improved

- replace Shellinabox with ttyd
- install the latest flood repo

### Function updated

### Bug fixed

- fix ssh port in installation summary (TUI)

---

## CHANGELOG v1.5.1

*Changelog update Tuesday, Oct 19, 2021*

### General additions

- add support for Debian 11 (Bullseye)

### Function improved

- reduce websocket connection (by Tautcony)

### Function updated

### Bug fixed

- fix bug in box command

---

## CHANGELOG v1.5.0

*Changelog update Monday, Aug 30, 2021*

### Notice

- Xenial and Stretch have been removed from the master branch, please install through legacy branch
- if quickbox lite was installed, it will automatically switch to the legacy branch after the upgrade

### General additions

- add sorting options for traffic statistics in panel (by Tautcony)

### Function improved

- update code style (by Tautcony)

### Function updated

- upgrade dependencies for dashboard, update panel

### Bug fixed

- fix pyenv warning
- adapt to the latest code of acme.sh
- fix noVNC failed to connect

---

## CHANGELOG v1.4.6

*Changelog update Sunday, Apr 11, 2021*

### General additions

- add box command `box enable-dev` and `box disable-dev`

### Function improved

### Function updated

- update quickbox-ws service

### Bug fixed

- fix the bug of "Received too large SFTP packet."
- fix flexget plugin for transmission

---

## CHANGELOG v1.4.5

*Changelog update Sunday, Feb 14, 2021*

### General additions

- add support for app version selection when installing quickbox
- add support for timezone setup when installing quickbox

### Function improved

- use python3 for iotest

### Function updated

### Bug fixed

- fix the bug of disk information widget when disk space occupy 100%
- fix the bug of change password
- fix cdn selection when installing quickbox

---

## CHANGELOG v1.4.4

*Changelog update Saturday, Jan 16, 2021*

### General additions

- add support for static linked qBittorrent Binary

### Function improved

- rewrite qBittorrent install function
- add compatibility mode for cifs

### Function updated

- add support for qBittorrent 4.3.2

### Bug fixed

---

## CHANGELOG v1.4.3

*Changelog update Tuesday, Dec 15, 2020*

### General additions

- add Speedtest

### Function improved

- setup Let's Encrypt when new installing this script

### Function updated

- update libraries for backend service

### Bug fixed

- fix acme crontab job

---

## CHANGELOG v1.4.2

*Changelog update Saturday, Nov 7, 2020*

### General additions

- add support for qBittorrent 4.3.0

### Function improved

### Function updated

### Bug fixed

- fix traffic status display in focal
- fix nfs service status display

---

## CHANGELOG v1.4.1

*Changelog update Wednesday, Sep 16, 2020*

### General additions

- Add CIFS support
- Add NFS support
- Add OpenVPN support

### Function improved

- A swapfile will be active, when system memory less than 2GB
- Add service control for vsFTPD

### Function updated

* Add remove dpkg and installation lock button on the dashboard

### Bug fixed

* general bug fix on quickbox backend service

---

## CHANGELOG v1.4.0

*Changelog update Saturday, Aug 1, 2020*

### General additions

- Replace php script with websocket to manage package & service.

### Function improved

- Upgrade front-end deps, eg: jquery, bootstrap.
- Import missing css and some other assets.

### Function updated

* Refactor package management.
* Refactor service status management.

### Bug fixed

* fix permission problem in FlexGet and autoremovetorrents
* adjust package management via websocket

---

## CHANGELOG v1.3.6:

*Changelog update Sunday, Jul 19, 2020*

### General additions

* add support for Ubuntu Focal
* add support for libtorrent-rasterbar 1.2.x
* add mirror GitHub as file host mirror

### Function improved

- rewrite function for compile libtorrent-rasterbar
- add delay for reloading nginx/php while upgrade service

### Function updated

* use GitHub mirror as default
* use qBittorrent 4.2.5 with libtorrent-rasterbar 1.1.14 as default
* use rtorrent 0.9.8 as default
* use php 7.4

### Bug fixed

* fix auto-irssi remove function
* FlexGet nginx reverse proxy

---



## CHANGELOG v1.3.5:

*Changelog update Saturday, Jun 13, 2020*

### General additions

* add autoremove-torrents (According to [feature request](https://github.com/amefs/quickbox-lite/issues/27))
* add pyenv

### Function improved

- now use pyenv instead of system wide python to install FlexGet
- add notice in FlexGet install output

### Function updated

* update FlexGet reversed proxy URL
* FlexGet now use the Latest version by default

### Bug fixed

* fix typo

---



## CHANGELOG v1.3.4:

*Changelog update Saturday, May 02, 2020*

### General additions

* add File Browser Enhanced

### Function improved

- add CDN selection in TUI install method
- Remember CDN selection
- Fetching package information of pre-compiled deb package, so all packages will be able to use once upload to host

### Function updated

* add setting template for BT client

### Bug fixed

* fix disk widget problem
* fix username check

---

## CHANGELOG v1.3.3:

*Changelog update Friday, Apr 10, 2020*

### General additions

* Now support qBittorrent 4.2.2 and 4.2.3
* Add One-key install mode
* Add quickbox background service
* linuxrar upgrade to 5.9.0

### Function improved

- Add Cloudflare and OSDN mirror for deb package
- Improve help information for box command
- Remove low efficiency css animation

### Function updated

* update box upgrade command

### Bug fixed

---

## CHANGELOG v1.3.2:

*Changelog update Sunday, Mar 22, 2020*

### General additions

* Now support libtorrent-rasterbar 1.1.14
* Add average traffic status in dashboard

### Function improved

- Add packages for noVNC installation for capability

### Function updated

* Now use filebrowser 2.0.16 instead of 2.1
* Use setuptools 45.3.0 for FlexGet installation
* Removed primary mount point selection in setup
* Add multi-mount point support in disk monitor widget on dashboard

### Bug fixed

- Fix configuration for qBittorrent 4.2.x
- Fix change password for qBittorrent
- Fix username error in Syncthing installation script
- Fix conflict when fail2ban against python3.7 on Stretch

---

## CHANGELOG v1.3.1:

*Changelog update Sunday, Feb 16, 2020*

### General additions

### Function improved

- Disable caching log display
- Enhance security, and it needs to **execute updating script twice** to apply changes
- Add more status into logfile for debugging

### Function updated

### Bug fixed

- Fix configuration for qBittorrent 4.2.x

---

## CHANGELOG v1.3.0:

*Changelog update Sunday, Jan 12, 2020*

### General additions

- add FlexGet upgrade
- support qBittorrent downgrade

### Function improved

- Improve size format display

### Function updated

- install qBittorrent 4.2.1 by default
- now support qBittorrent 4.2.1 and FlexGet 3
- Remove useless lib code
- Remove quota

### Bug fixed

- Fix localize.php generator
- mktorrent Wrapper

---

## CHANGELOG v1.2.0:

*Changelog update Friday, Nov 1, 2019*

### General additions

- add FlexGet template

### Function improved

- reformat all bash scripts
- Rewrite mount point scan function
- use HTTPS to protect download url
- clean cache after upgrade ruTorrent
- auto fill BT clients' authorization info and port info in FlexGet config

### Function updated

- install qBittorrent 4.1.8 by default
- now support qBittorrent 4.1.9.1

### Bug fixed

- Apache autoremove

---

## CHANGELOG v1.1.0:

*Changelog update Wednesday, Oct 2, 2019*

### General additions

- Add Template for FlexGet
- Add qBittorrent updater
- Add new IO benchmark
- Add home permission fix script
- Add mount point switcher

### Function improved

- Merge patches from tautcony
	- Improve status update in dashboard
	- Improve mobile compatibility

### Function updated

- QuickBox Lite CLI Tools are update to date
- Support qBittorrent 4.1.8 (Install via `box install qbittorrent --qb 4.1.8`)

### Bug fixed

- noVNC uninstaller auto remove list
- rTorrent updater waiting for confirm

---

## CHANGELOG v1.0.0:

*Changelog update Friday, Sep 20, 2019*

### General additions

- Porting most of the functions in QuickBox Community Edition
- add following software:
  - Netdata
  - noVNC
  - Denyhosts
  - Fail2ban
  - Flood

### Function improved

- Rewrite `box` command
- Simplify information on dashboard

### Function updated

- Nothing

### Bug fixed

- Nothing

---
