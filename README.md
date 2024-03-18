# Unraid Templates
- [Airsonic-advanced](#airsonic-advanced)
- [Apprise](#apprise)
- [ArchiveBox](#archivebox)
  * [First installation](#first-installation)
  * [Configuration](#configuration)
- [Backuppc](#backuppc)
- [Changedetection.io](#changedetectionio)
- [Commento](#commento)
  * [Notes](#notes-1)
- [Crypto-exchanges-gateway](#crypto-exchanges-gateway)
- [CryptPad](#cryptpad)
  * [First installation](#first-installation-1)
- [CyberChef](#cyberchef)
- [db-backup](#db-backup)
  * [Environment Variables](#environment-variables)
- [ddns-route53](#ddns-route53)
  * [Before running the docker](#before-running-the-docker)
- [Docpht](#docpht)
- [ecoDMS](#ecodms)
- [Element-web](#element-web)
- [Epicgames-freegames](#epicgames-freegames)
- [Filestash](#filestash)
- [Flarum](#flarum)
  * [Default username and password](#default-username-and-password-2)
  * [Notes](#notes-2)
- [FreePBX](#freepbx)
  * [First installation](#first-installation-2)
- [Freescout](#freescout)
  * [Creating User](#creating-user)
- [Gossa](#gossa)
- [Gotify](#gotify)
  * [Before running the docker](#before-running-the-docker-1)
  * [Default username and password](#default-username-and-password-3)
- [Homer](#homer)
- [Keycloak](#keycloak)
- [Kiwix-serve](#kiwix-serve)
  * [Notes](#notes-4)
  * [Content](#content)
- [Leantime](#leantime)
  * [First installation](#first-installation-3)
- [Librenms](#librenms)
  * [Notes](#notes-5)
- [Linkace](#linkace)
- [Linkding](#linkding)
- [Matomo](#matomo)
- [Matrix](#matrix)
  * [Guides](#guides)
- [Mattermost](#mattermost)
- [Mattermost-push-proxy](#mattermost-push-proxy)
  * [Notes](#notes-6)
  * [Before running the docker](#before-running-the-docker-2)
- [Mediagoblin](#mediagoblin)
  * [Default username and password](#default-username-and-password-4)
- [Memcached](#memcached)
- [Miniflux](#miniflux)
- [Moodle](#moodle)
  * [Notes](#notes-7)
- [Netbox](#netbox)
  * [Notes](#notes-9)
- [Nut](#nut)
- [phpBB](#phpbb)
- [PsiTransfer](#psitransfer)
  * [Notes](#notes-10)
- [Pterodactyl-panel](#pterodactyl-panel)
  * [Creating User](#creating-user-1)
- [Pure-FTPd](#pure-ftpd)
  * [Notes](#notes-11)
- [Quakejs](#quakejs)
- [Notes](#notes-12)
- [Reactive-resume](#reactive-resume)
- [Redis](#redis)
- [Riot-web](#riot-web)
  * [Before running the docker](#before-running-the-docker-3)
- [Send](#send)
- [Shaarli](#shaarli)
- [Shlink](#shlink)
- [Shlink-web-client](#shlink-web-client)
  * [Before Installing](#before-installing)
- [Solr](#solr)
- [StackEdit](#stackedit)
- [Synapse-admin](#synapse-admin)
- [Tar1090](#tar1090)
- [Torprivoxy](#torprivoxy)
- [tt-rss](#tt-rss)
- [Wallabag](#wallabag)
  * [Default username and password](#default-username-and-password-6)
  * [PHP errors](#php-errors)
  * [Missing texture and images](#missing-texture-and-images)
- [Weechat](#weechat)
- [Wifi-card](#wifi-card)
- [YaCy](#yacy)
  * [Default username and password](#default-username-and-password-7)
  * [Notes](#notes-14)

----
# Airsonic-advanced
![Airsonic-advanced](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/airsonic-advanced.png)

Airsonic-Advanced is a free, web-based media streamer, providing ubiquitous access to your music. 

**Application Name:** Airsonic-advanced

**Application Site:** https://github.com/airsonic-advanced/airsonic-advanced

**Docker Hub:** https://hub.docker.com/r/airsonicadvanced/airsonic-advanced/

**Github:** https://github.com/airsonic-advanced/airsonic-advanced

**[`^back to top^`](#unraid-templates)**

----
# Apprise
![Apprise](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/apprise.png)

Push Notifications that work with just about every platform! 

**Application Name:** Apprise

**Application Site:** https://github.com/caronc/apprise

**Docker Hub:** https://hub.docker.com/r/caronc/apprise/

**Github:** https://github.com/caronc/apprise

**[`^back to top^`](#unraid-templates)**

----
# ArchiveBox
![ArchiveBox](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/archivebox.png)

ArchiveBox is a powerful self-hosted internet archiving solution written in Python 3. You feed it URLs of pages you want to archive, and it saves them to disk in a varitety of formats depending on the configuration and the content it detects. 

**Application Name:** ArchiveBox

**Application Site:** https://archivebox.io/

**Docker Hub:** https://hub.docker.com/r/nikisweeting/archivebox

**Github:** https://github.com/pirate/ArchiveBox
## First installation 
1. **Run** the Archivebox Docker and **Console** to it.
```su - archivebox```
```cd /data```
```archivebox init```
```archivebox manage createsuperuser```
2. **Edit** Archivebox Docker Click at **Advanced View** put ```server 0.0.0.0:8000``` in **Post Arguments**.
## Configuration
To edit configuration open Archivebox folder and Edit ArchiveBox.conf (https://github.com/pirate/ArchiveBox/wiki/Configuration)

**[`^back to top^`](#unraid-templates)**

----
# Backuppc
![Backuppc](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/backuppc.png)

BackupPC is a free disk-to-disk backup software suite with a web-based frontend.

**Application Name:** Backuppc

**Application Site:** https://backuppc.github.io/backuppc/

**Docker Hub:** https://hub.docker.com/r/tiredofit/backuppc/

**Github:** https://www.github.com/tiredofit/docker-backuppc

**[`^back to top^`](#unraid-templates)**

----
# Changedetection.io
![Changedetection.io](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/changedetection.io.png)

*<div>Icons made by <a href="https://www.flaticon.com/authors/roundicons" title="Roundicons">Roundicons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

Self-hosted website change detection monitoring.

**Application Name:** Changedetection.io

**Application Site:** https://github.com/dgtlmoon/changedetection.io

**Docker Hub:** https://hub.docker.com/r/dgtlmoon/changedetection.io

**Github:** https://github.com/dgtlmoon/changedetection.io

**[`^back to top^`](#unraid-templates)**

----
# Commento
![Commento](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/commento.png)

Commento is a platform that you can embed in your website to allow your readers to add comments. 

**Application Name:** Commento

**Application Site:** https://commento.io

**Docker Hub:** https://gitlab.com/commento/commento

**Github:** https://gitlab.com/commento/commento
## Notes
* PostgreSQL DB Required (Not Included)

**[`^back to top^`](#unraid-templates)**

----
# Crypto-exchanges-gateway
![Crypto-exchanges-gateway](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/crypto-exchanges-gateway.png)

*<div>Icons made by <a href="https://www.flaticon.com/authors/vitaly-gorbachev" title="Vitaly Gorbachev">Vitaly Gorbachev</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

**Application Name:** Crypto-exchanges-gateway

**Application Site:** https://github.com/aloysius-pgast/crypto-exchanges-gateway

**Docker Hub:** https://hub.docker.com/r/apendergast/crypto-exchanges-gateway/

**Github:** https://github.com/aloysius-pgast/crypto-exchanges-gateway

**[`^back to top^`](#unraid-templates)**

----
# CryptPad
![CryptPad](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/cryptpad.png)

CryptPad is a private-by-design alternative to popular office tools and cloud services. 

**Application Name:** CryptPad

**Application Site:** https://cryptpad.fr/

**Docker Hub:** https://hub.docker.com/r/promasu/cryptpad

**Github:** https://github.com/xwiki-labs/cryptpad

**[`^back to top^`](#unraid-templates)**
## First installation
* mkdir -p /mnt/user/appdata/element-web/config
* wget -O /mnt/user/appdata/element-web/config/config.json https://raw.githubusercontent.com/vector-im/element-web/develop/element.io/app/config.json 
* Edit config.json "httpUnsafeOrigin" change localhost to your ip 
* remove "//" in "httpAddress"
----
# CyberChef
![CyberChef](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/cyberchef.png)

CyberChef is a simple, intuitive web app for carrying out all manner of "cyber" operations within a web browser. These operations include simple encoding like XOR or Base64, more complex encryption like AES, DES and Blowfish, creating binary and hexdumps, compression and decompression of data, calculating hashes and checksums, IPv6 and X.509 parsing, changing character encodings, and much more.

**Application Name:** CyberChef

**Application Site:** https://gchq.github.io/CyberChef/

**Docker Hub:** https://hub.docker.com/r/mpepping/cyberchef/

**Github:** https://github.com/mpepping/docker-cyberchef/

**[`^back to top^`](#unraid-templates)**

----
# db-backup
![db-backup](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/db-backup.png)

For backing up multiple type of DB Servers, currently supports CouchDB, InfluxDB, MySQL, MongoDB, Postgres, Redis servers.

*<div>Icons made by <a href="https://www.flaticon.com/authors/srip" title="srip">srip</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

**Application Name:** db-backup

**Application Site:** https://github.com/tiredofit/docker-db-backup 

**Docker Hub:** https://hub.docker.com/r/tiredofit/db-backup/

**Github:** https://github.com/tiredofit/docker-db-backup 
## Environment Variables
| Parameter | Description |
|-----------|-------------|
| `COMPRESSION` | Use either Gzip `GZ`, Bzip2 `BZ`, XZip `XZ`, or none `NONE` - Default `GZ`
| `DB_TYPE` | Type of DB Server to backup `couch` `influx` `mysql` `pgsql` `mongo` `redis` `rethink`
| `DB_HOST` | Server Hostname e.g. `mariadb`
| `DB_NAME` | Schema Name e.g. `database`
| `DB_USER` | username for the database - use `root` to backup all MySQL of them.
| `DB_PASS` | (optional if DB doesn't require it) password for the database
| `DB_PORT` | (optional) Set port to connect to DB_HOST. Defaults are provided
| `DB_DUMP_FREQ` | How often to do a dump, in minutes. Defaults to 1440 minutes, or once per day.
| `DB_DUMP_BEGIN` | What time to do the first dump. Defaults to immediate. Must be in one of two formats
| | Absolute HHMM, e.g. `2330` or `0415`
| | Relative +MM, i.e. how many minutes after starting the container, e.g. `+0` (immediate), `+10` (in 10 minutes), or `+90` in an hour and a half
| `DB_CLEANUP_TIME` | Value in minutes to delete old backups (only fired when dump freqency fires). 1440 would delete anything above 1 day old. You don't need to set this variable if you want to hold onto everything.
| `DEBUG_MODE` | If set to `true`, print copious shell script messages to the container log. Otherwise only basic messages are printed.
| `MD5` | Generate MD5 Sum in Directory, `TRUE` or `FALSE` - Default `TRUE`
| `PARALLEL_COMPRESSION` | Use multiple cores when compressing backups `TRUE` or `FALSE` - Default `TRUE` |
| `SPLIT_DB` | If using root as username and multiple DBs on system, set to TRUE to create Seperate DB Backups instead of all in one. - Default `FALSE` |

**[`^back to top^`](#unraid-templates)**

----
# ddns-route53
![ddns-route53](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/ddns-route53.png)

Simple dynamic DNS updater script using Amazon Route53.

**Application Name:** ddns-route53

**Application Site:** https://github.com/crazy-max/ddns-route53

**Docker Hub:** https://hub.docker.com/r/crazymax/ddns-route53/

**Github:** https://github.com/crazy-max/ddns-route53
## Before running the docker
* Create ddns-route53.yml file in /mnt/user/appdata/ddns-route53/ - https://github.com/crazy-max/ddns-route53/blob/master/doc/configuration.md

**[`^back to top^`](#unraid-templates)**

----
# Docpht
![Docpht](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/docpht.png)

With DocPHT you can take notes and quickly document anything and without the use of any database.  

*Icons made by <a href="https://www.flaticon.com/authors/freepik" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>*

**Application Name:** Docpht

**Application Site:** https://docpht.org/

**Docker Hub:** https://hub.docker.com/r/docpht/docpht/

**Github:** https://github.com/docpht/docpht

**[`^back to top^`](#unraid-templates)**

----
# ecoDMS
![ecoDMS](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/ecoDMS.png)

easily archive, manage, and find all documents on your PC or from your smart phone and tablet.

**Application Name:** ecoDMS

**Application Site:** https://www.ecodms.de/index.php/en/

**Docker Hub:** https://hub.docker.com/r/ecodms/allinone-18.09/

**Github:** https://hub.docker.com/r/ecodms/allinone-18.09/

**[`^back to top^`](#unraid-templates)**

----
# Element-web
![Element-web](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/element-web.png)

**Application Name:** Element-web

**Application Site:** https://element.io/

**Docker Hub:** https://hub.docker.com/r/vectorim/element-web/

**Github:** https://www.github.com/vector-im/element-web

**[`^back to top^`](#unraid-templates)**

----
# Epicgames-freegames
![Epicgames-freegames](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/epicgames-freegames.png)

*<div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

**Application Name:** Epicgames-freegames

**Application Site:** https://github.com/claabs/epicgames-freegames-node

**Docker Hub:** https://hub.docker.com/r/charlocharlie/epicgames-freegames/

**Github:** https://github.com/claabs/epicgames-freegames-node

**[`^back to top^`](#unraid-templates)**

----
# Filestash
![Filestash](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/filestash.png)

**Application Name:** Filestash

**Application Site:** https://www.filestash.app/

**Docker Hub:** https://hub.docker.com/r/machines/filestash/

**Github:** https://github.com/mickael-kerjean/filestash

**[`^back to top^`](#unraid-templates)**

----
# Flarum
![Flarum](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/flarum.png)

Forums made simple. Modern, fast, and free!

**Application Name:** Flarum

**Application Site:** https://flarum.org/

**Docker Hub:** https://hub.docker.com/r/crazymax/flarum/

**Github:** https://github.com/crazy-max/docker-flarum
## Default username and password
Username: ```flarum```
Password: ```flarum```
## Notes
* Make Sure the base url is right if it local use only use http://<ip>:8000 and if you are hosting it on your domain it should be http://example.com or https://example.com.

**[`^back to top^`](#unraid-templates)**

----
# FreePBX
![FreePBX](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/freepbx.png)

Asterisk-based open source phone system.

A Dropbox-like file manager that let you manage your data anywhere it is located:
FTP • FTPS • SFTP • WebDAV • Git • S3 • LDAP • Mysql
CardDAV • CalDAV • Backblaze B2 • Minio
Dropbox • Google Drive 

**Application Name:** FreePBX

**Application Site:** https://www.freepbx.org/

**Docker Hub:** https://hub.docker.com/r/tiredofit/freepbx/

**Github:** https://github.com/tiredofit/docker-freepbx/
## First installation 
* Take time be patient
* Wizard setup go to http://freepbx/admin/config.php
* Use Database

**[`^back to top^`](#unraid-templates)**

----
# Freescout
![freescout](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/freescout.png)

An open source Helpscout / Zendesk alternative.

**Application Name:** Freescout

**Application Site:** https://freescout.net/

**Docker Hub:** https://hub.docker.com/r/tiredofit/freescout/

**Github:** https://www.github.com/tiredofit/docker-freescout
## Creating User
* CLI ```cd /www/html``` then ```php artisan freescout:create-user```

**[`^back to top^`](#unraid-templates)**

----
# Gossa
![Gossa](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/gossa.png)

A fast and simple webserver for your files, that's dependency-free and with under 250 lines of code, easy to review.

*<div>Icons made by <a href="https://www.flaticon.com/authors/srip" title="srip">srip</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

**Application Name:** Gossa

**Application Site:** https://www.github.com/pldubouilh/gossa

**Docker Hub:** https://hub.docker.com/r/pldubouilh/gossa/

**Github:** https://www.github.com/pldubouilh/gossa

**[`^back to top^`](#unraid-templates)**

----
# Gotify
![Gotify](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/gotify.png)

A simple server for sending and receiving messages (in real time per WebSocket).

**Application Name:** Gotify

**Application Site:** https://gotify.net/

**Docker Hub:** https://hub.docker.com/r/gotify/server/

**Github:** https://github.com/gotify/server/ 
## Before running the docker
```mkdir -p /mnt/user/appdata/gotify/config/```
```wget -O /mnt/user/appdata/gotify/config/config.yml https://raw.githubusercontent.com/gotify/server/master/config.example.yml```
## Default username and password
* Username: ```admin```
* Password: ```admin```
    
**[`^back to top^`](#unraid-templates)**

----
# Homer
![Homer](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/homer.png)

A dead simple static HOMepage for your servER to keep your services on hand, from a simple `yaml` configuration file. 

**Application Name:** Homer

**Application Site:** https://github.com/bastienwirtz/homer

**Docker Hub:** https://hub.docker.com/r/b4bz/homer

**Github:** https://github.com/bastienwirtz/homer

**[`^back to top^`](#unraid-templates)**

----
# Keycloak
![Keycloak](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/keycloak.png)

**Application Name:** Keycloak

**Application Site:** https://www.keycloak.org/

**Registry:** https://quay.io/repository/keycloak/keycloak

**Github:** https://github.com/keycloak/keycloak

**[`^back to top^`](#unraid-templates)**

----
# Kiwix-serve
![Kiwix-serve](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/kiwix.png)

**Application Name:** Kiwix-serve

**Application Site:** https://www.kiwix.org/

**Docker Hub:** https://hub.docker.com/r/kiwix/kiwix-serve/

**Github:** https://github.com/kiwix/kiwix-tools
## Notes
* When using variable "DOWNLOAD" remove the link after the download so you don't re-download the same content again
## Content
For more content https://wiki.kiwix.org/wiki/Content

**[`^back to top^`](#unraid-templates)**

----
# Leantime
![Leantime](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/leantime.png)

**Application Name:** Leantime

**Application Site:** https://leantime.io/

**Docker Hub:** https://hub.docker.com/r/leantime/leantime/

**Github:** https://github.com/Leantime/docker-leantime
## First installation 
* First setup go to http://leantime/install

**[`^back to top^`](#unraid-templates)**

----
# Librenms
![Librenms](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/librenms.png)

**Application Name:** Librenms

**Application Site:** https://www.librenms.org/

**Docker Hub:** https://hub.docker.com/r/librenms/librenms/

**Github:** https://github.com/librenms/docker
## Notes
* Database must be CHARACTER SET utf8 COLLATE utf8_unicode_ci

**[`^back to top^`](#unraid-templates)**

----
# Linkace
![Linkace](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/linkace.png)

**Application Name:** Linkace

**Application Site:** https://www.linkace.org/

**Docker Hub:** https://hub.docker.com/r/linkace/linkace/

**Github:** https://github.com/Kovah/LinkAce/

**[`^back to top^`](#unraid-templates)**

----
# Linkding
![Linkding](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/linkding.png)

**Application Name:** Linkding

**Application Site:** https://github.com/sissbruecker/linkding

**Docker Hub:** https://hub.docker.com/r/sissbruecker/linkding/

**Github:** https://github.com/sissbruecker/linkding

**[`^back to top^`](#unraid-templates)**

----
# Matomo
![Mailpile](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/matomo.png)

**Application Name:** Matomo

**Application Site:** https://matomo.org/

**Docker Hub:** https://hub.docker.com/r/bitnami/matomo/

**Github:** https://github.com/bitnami/bitnami-docker-matomo
 
**[`^back to top^`](#unraid-templates)**

----
# Matrix
![Matrix](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/matrix.png)

**Application Name:** Matrix

**Application Site:** https://matrix.org/

**Docker Hub:** https://hub.docker.com/r/avhost/docker-matrix

**Github:** https://github.com/AVENTER-UG/docker-matrix
## Guides
* Unraid User - PSYCHOPATHiO [Guide](https://forums.unraid.net/topic/89502-support-a75g-repo/?do=findComment&comment=839576)
* More info about matrix configuration [here](https://github.com/matrix-org/synapse/blob/master/README.rst)

**[`^back to top^`](#unraid-templates)**

----
# Mattermost
![Mattermost](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/mattermost.png)

**Application Name:** Mattermost

**Application Site:** https://mattermost.com/

**Docker Hub:** https://hub.docker.com/r/mattermost/mattermost-team-edition/

**Github:** https://github.com/mattermost/mattermost-server

**[`^back to top^`](#unraid-templates)**

----
# Mattermost-push-proxy
![Mattermost-push-proxy](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/mattermost-push-proxy.png)

**Application Name:** Mattermost-push-proxy

**Application Site:** https://mattermost.com/

**Docker Hub:** https://hub.docker.com/r/mattermost/mattermost-push-proxy/

**Github:** https://github.com/mattermost/mattermost-push-proxy
## Notes
* https://developers.mattermost.com/contribute/mobile/push-notifications/service/
## Before running the docker
* ```mkdir /mnt/user/appdata/mattermost-push-proxy/config```
* ```cd /mnt/user/appdata/mattermost-push-proxy/config```
* ```wget https://raw.githubusercontent.com/mattermost/mattermost-push-proxy/master/config/mattermost-push-proxy.json```

**[`^back to top^`](#unraid-templates)**

----
# Mediagoblin
![Mediagoblin](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/mediagoblin.png)

**Application Name:** Mediagoblin

**Application Site:** https://mediagoblin.org/

**Docker Hub:** https://hub.docker.com/r/mtlynch/mediagoblin/

**Github:** https://www.github.com/mtlynch/mediagoblin-docker
## Default username and password
* Username: ```admin```
* Password: ```admin```

**[`^back to top^`](#unraid-templates)**

----
# Memcached
![Memcached](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/memcached.png)

**Application Name:** Memcached

**Application Site:** https://memcached.org/

**Docker Hub:** https://hub.docker.com/r/bitnami/memcached
    
**Github:** https://github.com/bitnami/bitnami-docker-memcached

**[`^back to top^`](#unraid-templates)**

----
# Miniflux
![Miniflux](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/miniflux.png)

**Application Name:** Miniflux

**Application Site:** https://miniflux.app/

**Docker Hub:** https://hub.docker.com/r/miniflux/miniflux/

**Github:** https://github.com/miniflux/miniflux

**[`^back to top^`](#unraid-templates)**

----
# Moodle
![Moodle](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/moodle.png)

**Application Name:** Moodle

**Application Site:** https://moodle.org/

**Docker Hub:** https://hub.docker.com/r/bitnami/moodle/

**Github:** https://github.com/bitnami/bitnami-docker-moodle

## Notes
* Admin username and password is setup at in docker variables then you can change in Miniflux settings. Docker variable will be ignored when you change it inside the docker.
* PostgreSQL DB Required (Not Included)

**[`^back to top^`](#unraid-templates)**

----
# Netbox
![Netbox](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/netbox.png)

**Application Name:** Netbox

**Application Site:** https://github.com/netbox-community/netbox

**Docker Hub:** https://hub.docker.com/r/pitkley/netbox

**Github:** https://github.com/pitkley/docker-netbox
## Notes
* Create User cli to the docker then ```./manage.py createsuperuser```
* PostgreSQL DB Required (Not Included)

**[`^back to top^`](#unraid-templates)**

----
# Nut
![Nut](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/nut.png)

*<a href="https://www.flaticon.com/free-icons/squirrel" title="squirrel icons">Squirrel icons created by Freepik - Flaticon</a>*

**Application Name:** Nut

**Application Site:** https://github.com/shawly/docker-nut

**Docker Hub:** https://hub.docker.com/r/shawly/nut

**Github:** https://github.com/shawly/docker-nut

**[`^back to top^`](#unraid-templates)**

----
# phpBB
![phpBB](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/phpbb.png)

**Application Name:** phpBB

**Application Site:** https://www.phpbb.com/

**Docker Hub:** https://hub.docker.com/r/bitnami/phpbb

**Github:** https://github.com/bitnami/bitnami-docker-phpbb/

**[`^back to top^`](#unraid-templates)**

----
# PsiTransfer
![psitransfer](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/psitransfer.png)

*<div>Icons made by <a href="https://www.flaticon.com/authors/google" title="Google">Google</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

**Application Name:** PsiTransfer

**Application Site:** https://github.com/psi-4ward/psitransfer

**Docker Hub:** https://hub.docker.com/r/psitrax/psitransfer/

**Github:** https://github.com/psi-4ward/psitransfer
## Notes
* Admin Page just add ```/admin``` to your URL

**[`^back to top^`](#unraid-templates)**

----
# Pterodactyl-panel
![pterodactyl-panel](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/pterodactyl-panel.png)

**Application Name:** Pterodactyl-panel

**Application Site:** https://pterodactyl.io/

**Docker Hub:** https://hub.docker.com/r/ccarney16/pterodactyl-panel

**Github:** https://github.com/ccarney16/pterodactyl-docker
## Creating User
* CLI ```cd /www/html``` then ```php artisan p:user:make```

**[`^back to top^`](#unraid-templates)**

----
# Pure-FTPd
![Pure-FTPd](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/pure-ftpd.png)

*<div>Icons made by <a href="https://www.flaticon.com/authors/good-ware" title="Good Ware">Good Ware</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

**Application Name:** Pure-FTPd

**Application Site:** https://www.pureftpd.org/project/pure-ftpd/

**Docker Hub:** https://hub.docker.com/r/crazymax/pure-ftpd/

**Github:** https://github.com/crazy-max/docker-pure-ftpd
## Notes
* Creating User use console then ```pure-pw useradd admin -u 99 -g 100 -d /home/admin -m``` then enter password of your choosing.
* https://github.com/crazy-max/docker-pure-ftpd#notes

**[`^back to top^`](#unraid-templates)**

----
# Quakejs
![Quakejs](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/quakejs.png)

**Application Name:** Quakejs

**Application Site:** https://github.com/treyyoder/quakejs-docker

**Docker Hub:** https://hub.docker.com/r/treyyoder/quakejs/

**Github:** https://github.com/treyyoder/quakejs-docker
# Notes
* Use Custom:br0 https://youtu.be/2VnQxxn00jU?t=121 put Fixed IP address
* Copy the ip and access it using you broswer

**[`^back to top^`](#unraid-templates)**

----
# Reactive-resume
![Reactive-resume](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/reactive-resume.png)

**Application Name:** Reactive-resume

**Application Site:** https://rxresu.me/

**Docker Hub:** https://hub.docker.com/r/amruthpillai/reactive-resume/

**Github:** https://www.github.com/AmruthPillai/Reactive-Resume

**[`^back to top^`](#unraid-templates)**

----
# Redis
![Redis](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/redis.png)

**Application Name:** Redis

**Application Site:** https://redis.io/

**Docker Hub:** https://hub.docker.com/r/bitnami/redis/

**Github:** https://github.com/bitnami/bitnami-docker-redis

**[`^back to top^`](#unraid-templates)**

----
# Riot-web
![Riot-web](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/riot-web.png)

Riot is a glossy web client with an emphasis on performance and usability.

**Application Name:** Riot-web

**Application Site:** https://riot.im/

**Docker Hub:** https://hub.docker.com/r/vectorim/riot-web/

**Github:** https://www.github.com/vector-im/riot-web
## Before running the docker
1. ```mkdir -p /mnt/user/appdata/riot-web/config```
2.    ```wget -O /mnt/user/appdata/riot-web/config/config.json https://riot.im/develop/config.json```

**[`^back to top^`](#unraid-templates)**

----
# Searx
![Searx](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/searx.png)

Searx is a free internet metasearch engine which aggregates results from more than 70 search services. Users are neither tracked nor profiled. Additionally, searx can be used over Tor for online anonymity.

**Application Name:** Searx

**Application Site:** https://github.com/asciimoo/searx

**Docker Hub:** https://hub.docker.com/r/searx/searx/

**Github:** https://github.com/asciimoo/searx
    
**[`^back to top^`](#unraid-templates)**

----
# Send
![Send](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/send.png)

**Application Name:** Send

**Application Site:** https://gitlab.com/timvisee/send

**Docker Hub:** registry.gitlab.com/timvisee/send:latest

**Github:** https://gitlab.com/timvisee/send
    
**[`^back to top^`](#unraid-templates)**

----
# Shaarli
![Shaarli](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/shaarli.png)

**Application Name:** Shaarli

**Application Site:** https://github.com/shaarli/Shaarli

**Docker Hub:** https://hub.docker.com/r/shaarli/shaarli/

**Github:** https://github.com/shaarli/Shaarli
    
**[`^back to top^`](#unraid-templates)**

----
# Shlink

Shlink is a self-hosted URL shortener which provides both a REST and a CLI interface to interact with it.

![Shlink](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/shlink.png)

**Application Name:** Shlink

**Application Site:** https://shlink.io/

**Docker Hub:** https://hub.docker.com/r/shlinkio/shlink/

**Github:** https://github.com/shlinkio/shlink

**[`^back to top^`](#unraid-templates)**

----
# Shlink-web-client

Shlink is a self-hosted URL shortener which provides both a REST and a CLI interface to interact with it.

![Shlink-web-client](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/shlink-web-client.png)

**Application Name:** Shlink-web-client

**Application Site:** https://shlink.io/

**Docker Hub:** https://hub.docker.com/r/shlinkio/shlink-web-client/

**Github:** https://www.github.com/shlinkio/shlink-web-client
## Before Installing
1. Install shlink
2. CLI to it and enter "shlink api-key:generate"
3. Copy the api and add and edit to servers.json

* https://hub.docker.com/r/shlinkio/shlink-web-client/ servers.json

**[`^back to top^`](#unraid-templates)**

----
# Solr
![Solr](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/solr.png)

Solr is an open-source enterprise-search platform, written in Java.

**Application Name:** Solr

**Application Site:** https://lucene.apache.org/solr/

**Docker Hub:** https://hub.docker.com/r/bitnami/solr

**Github:** https://github.com/bitnami/bitnami-docker-solr

**[`^back to top^`](#unraid-templates)**

----
# StackEdit
![Shiori](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/stackedit.png)

StackEdit is a free, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.

**Application Name:** StackEdit

**Application Site:** https://stackedit.io/

**Docker Hub:** https://hub.docker.com/r/qmcgaw/stackedit/

**Github:** https://github.com/qdm12/stackedit-docker

**[`^back to top^`](#unraid-templates)**

----
# Synapse-admin
![Synapse-admin](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/synapse-admin.png)

*Icons made by <a href="https://www.flaticon.com/free-icon/matrix_1774127" title="Vitaly Gorbachev">Vitaly Gorbachev</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>*

Synapse admin ui

**Application Name:** Synapse-admin

**Application Site:** https://github.com/Awesome-Technologies/synapse-admin

**Docker Hub:** https://hub.docker.com/r/awesometechnologies/synapse-admin/

**Github:** https://github.com/Awesome-Technologies/synapse-admin

**[`^back to top^`](#unraid-templates)**

----
# Tar1090
![Tar1090](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/tar1090.png)

*Icons made by <a href="https://smashicons.com/" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>*

Provides an improved webinterface for use with ADS-B decoders readsb / dump1090-fa 

**Application Name:** Synapse-admin

**Application Site:** https://www.github.com/mikenye/docker-tar1090

**Docker Hub:** https://hub.docker.com/r/mikenye/tar1090

**Github:** https://www.github.com/mikenye/docker-tar1090

**[`^back to top^`](#unraid-templates)**

----
# Torprivoxy
![Torprivoxy](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/torprivoxy.png)

*Icons made by <a href="https://www.flaticon.com/authors/photo3idea-studio" title="photo3idea_studio">photo3idea_studio</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>*

Docker Tor proxy (http and shell) built on Alpine Linux 

**Application Name:** Synapse-admin

**Application Site:** https://github.com/avpnusr/torprivoxy

**Docker Hub:** https://hub.docker.com/r/avpnusr/torprivoxy/

**Github:** https://github.com/avpnusr/torprivoxy

**[`^back to top^`](#unraid-templates)**

----
# tt-rss
![tt-rss](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/tt-rss.png)

Tiny Tiny RSS is a free RSS feed reader. It is a web application which must be installed on a web server.

**Application Site:** https://tt-rss.org/

**Docker Hub:** https://hub.docker.com/r/lunik1/tt-rss/

**Github:** https://github.com/lunik1/docker-tt-rss

**[`^back to top^`](#unraid-templates)**

----
# Wallabag
![Wallabag](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/wallabag.png)

Wallabag is a self hostable application for saving web pages: Save and classify articles. Read them later. Freely. 

**Application Name:** Wallabag

**Application Site:** https://wallabag.org/

**Docker Hub:** https://hub.docker.com/r/wallabag/wallabag

**Github:** https://www.github.com/wallabag/docker
## Default username and password
Username: ```wallabag```
Password: ```wallabag```
## PHP errors
* https://github.com/wallabag/docker/issues/185
## Missing texture and images 
* Make sure the domain variable is right http://ip:6500 and if you are hosting it http://wallabag.example.com or https://wallabag.example.com.

**[`^back to top^`](#unraid-templates)**

----
# Weechat
![Weechat](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/weechat.png)

WeeChat is a free and open-source Internet Relay Chat client, which is designed to be light and fast.

**Application Site:** https://weechat.org/

**Docker Hub:** https://hub.docker.com/r/jkaberg/weechat/

**Github:** https://www.github.com/jkaberg/dockerfiles

**[`^back to top^`](#unraid-templates)**

----
# Wifi-card
![Wifi-card](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/wifi-card.png)

*<div>Icons made by <a href="https://www.flaticon.com/authors/bqlqn" title="bqlqn">bqlqn</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

Print a QR code for connecting to your WiFi 

**Application Name:** Wifi-card

**Application Site:** https://github.com/bndw/wifi-card

**Docker Hub:** https://hub.docker.com/r/bndw/wifi-card/

**Github:** https://github.com/bndw/wifi-card

**[`^back to top^`](#unraid-templates)**

----
# YaCy
![YaCy](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/yacy.png)

YaCy is a distributed Web Search Engine, based on a peer-to-peer network.

**Application Name:** YaCy

**Application Site:** https://yacy.net/

**Docker Hub:** https://hub.docker.com/r/yacy/yacy_search_server/

**Github:** https://www.github.com/yacy/yacy_search_server
## Default username and password
Username: ```admin```
Password: ```docker```

## Notes
Set an admin account immediately after the first start-up. Open:
http://<ServerIP>:8090/ConfigAccounts_p.html 
**[`^back to top^`](#unraid-templates)**

----
