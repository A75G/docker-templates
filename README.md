# Unraid Templates
- [Airsonic-advanced](#airsonic-advanced)
- [Apprise](#apprise)
- [ArchiveBox](#archivebox)
  * [First installation](#first-installation)
  * [Configuration](#configuration)
- [Backuppc](#backuppc)
- [Cloudbeaver](#cloudbeaver)
  * [Notes](#notes)
- [Commento](#commento)
  * [Notes](#notes-1)
- [CryptPad](#cryptpad)
  * [First installation](#first-installation-1)
- [CyberChef](#cyberchef)
- [Dashmachine](#dashmachine)
  * [Default username and password](#default-username-and-password)
- [db-backup](#db-backup)
  * [Environment Variables](#environment-variables)
- [ddns-route53](#ddns-route53)
  * [Before running the docker](#before-running-the-docker)
- [Dispatch](#dispatch)
- [Docpht](#docpht)
- [Droppy](#droppy)
- [FileRun](#filerun)
  * [Default username and password](#default-username-and-password-1)
- [Element-web](#element-web)
- [Filestash](#filestash)
- [FreePBX](#freepbx)
  * [First installation](#first-installation-2)
- [Freescout](#freescout)
  * [Creating User](#creating-user)
- [Firefox-Syncserver](#firefox-syncserver)
- [Flarum](#flarum)
  * [Default username and password](#default-username-and-password-2)
  * [Notes](#notes-2)
- [Golinks](#golinks)
  * [Usage](#usage)
- [Gossa](#gossa)
- [Gotify](#gotify)
  * [Before running the docker](#before-running-the-docker-1)
  * [Default username and password](#default-username-and-password-3)
- [Healthchecks](#healthchecks)
- [Homer](#homer)
  * [Before running the docker](#before-running-the-docker-2)
- [Jitsi](#jitsi)
  * [Change appdata location](#change-appdata-location)
  * [Notes](#notes-3)
- [Keycloak](#keycloak)
- [Kiwix-serve](#kiwix-serve)
  * [Notes](#notes-4)
  * [Content](#content)
- [Leantime](#leantime)
  * [First installation](#first-installation-3)
- [Librenms](#librenms)
  * [Notes](#notes-5)
- [Linkding](#linkding)
- [Mailpile](#mailpile)
- [Matomo](#matomo)
- [Matrix](#matrix)
  * [Guides](#guides)
- [Mattermost](#mattermost)
- [Mattermost-push-proxy](#mattermost-push-proxy)
  * [Notes](#notes-6)
  * [Before running the docker](#before-running-the-docker-3)
- [Mediagoblin](#mediagoblin)
  * [Default username and password](#default-username-and-password-4)
- [Memcached](#memcached)
- [Miniflux](#miniflux)
- [Moodle](#moodle)
  * [Notes](#notes-7)
- [Mumble](#mumble)
  * [Notes](#notes-8)
- [Netbox](#netbox)
  * [Notes](#notes-9)
- [phpBB](#phpbb)
- [PsiTransfer](#psitransfer)
  * [Notes](#notes-10)
- [Pterodactyl-panel](#pterodactyl-panel)
  * [Creating User](#creating-user-1)
- [Pterodactyl-daemon](#pterodactyl-daemon)
- [Pure-FTPd](#pure-ftpd)
  * [Notes](#notes-11)
- [Pwndrop](#pwndrop)
- [Quakejs](#quakejs)
- [Notes](#notes-12)
- [Reactive-resume](#reactive-resume)
- [Redis](#redis)
- [Riot-web](#riot-web)
  * [Before running the docker](#before-running-the-docker-4)
- [Searx](#searx)
- [Selfoss](#selfoss)
- [Shiori](#shiori)
  * [Default username and password](#default-username-and-password-5)
  * [Notes](#notes-13)
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

**Application Name:** Backuppc

**Application Site:** https://backuppc.github.io/backuppc/

**Docker Hub:** https://hub.docker.com/r/tiredofit/backuppc/

**Github:** https://www.github.com/tiredofit/docker-backuppc

**[`^back to top^`](#unraid-templates)**

----
# Cloudbeaver
![Cloudbeaver](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/cloudbeaver.png)

CloudBeaver is a web server which provides rich web interface. Server itself is a Java application, web part is written on TypeScript and React.

**Application Name:** Cloudbeaver

**Application Site:** https://github.com/dbeaver/cloudbeaver

**Docker Hub:** https://hub.docker.com/r/dalongrong/cloudbeaver

**Github:** https://github.com/dbeaver/cloudbeaver
## Notes
* There is no appdata https://hub.docker.com/r/dalongrong/cloudbeaver

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

**Docker Hub:** https://hub.docker.com/r/aude/cyberchef

**Github:** https://github.com/aude/cyberchef-docker

**[`^back to top^`](#unraid-templates)**

----
# Dashmachine
![Dashmachine](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/dashmachine.png)

Another web application bookmark dashboard, with fun features.

**Application Name:** Dashmachine

**Application Site:** https://github.com/rmountjoy92/DashMachine

**Docker Hub:** https://hub.docker.com/r/rmountjoy/dashmachine/

**Github:** https://github.com/rmountjoy92/DashMachine
## Default username and password
* Username: ```admin```
* Password: ```admin```

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
# Dispatch
![Dispatch](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/dispatch.png)

Web-based IRC client in Go.

**Application Name:** Dispatch

**Application Site:** https://github.com/khlieng/dispatch

**Docker Hub:** https://hub.docker.com/r/khlieng/dispatch/

**Github:** https://github.com/khlieng/dispatch

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
# Droppy
![Droppy](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/droppy.png)

Self-hosted file storage server 

**Application Name:** Droppy

**Application Site:** https://droppy.silverwind.io/

**Docker Hub:** https://hub.docker.com/r/silverwind/droppy/

**Github:** https://github.com/silverwind/droppy

**[`^back to top^`](#unraid-templates)**

----
# FileRun
![FileRun](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/filerun.png)

FileRun is a self-hosted Google Drive/Photos/Music alternative. It is a full featured web based file manager with an easy to use user interface.

**Application Name:** FileRun

**Application Site:** https://filerun.com/

**Docker Hub:** https://hub.docker.com/r/afian/filerun/

**Github:** https://github.com/filerun/docker
## Default username and password
* Username: ```superuser```
* Password: ```superuser```

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
# Filestash
![Filestash](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/filestash.png)

**Application Name:** Filestash

**Application Site:** https://www.filestash.app/

**Docker Hub:** https://hub.docker.com/r/machines/filestash/

**Github:** https://github.com/mickael-kerjean/filestash

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
# Firefox-Syncserver
![Firefox-Syncserver](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/firefox-syncserver.png)

Self hosted firefox sync server.

**Application Name:** Firefox-Syncserver

**Application Site:** https://github.com/crazy-max/docker-firefox-syncserver

**Docker Hub:** https://hub.docker.com/r/crazymax/firefox-syncserver

**Github:** https://github.com/crazy-max/docker-firefox-syncserver

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
# Golinks
![Golinks](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/golinks.png)

golinks is a web app that allows you to create smart bookmarks, commands and aliases by pointing your web browser's default search engine at a running instance. Similar to bunny1 or yubnub.

*<div>Icons made by <a href="https://www.flaticon.com/authors/iconixar" title="iconixar">iconixar</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*

**Application Name:** Golinks

**Application Site:** https://github.com/prologic/golinks

**Docker Hub:** https://hub.docker.com/r/prologic/golinks/

**Github:** https://github.com/prologic/golinks
## Usage
* https://github.com/prologic/golinks#usage
    
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
# Healthchecks
![Healthchecks](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/healthchecks.png)

healthchecks is a watchdog for your cron jobs. It's a web server that listens for pings from your cron jobs, plus a web interface.

**Application Name:** Healthchecks

**Application Site:** https://healthchecks.io/

**Docker Hub:** https://hub.docker.com/r/galexrt/healthchecks/

**Github:** https://github.com/galexrt/docker-healthchecks
    
**[`^back to top^`](#unraid-templates)**

----
# Homer
![Homer](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/homer.png)

A dead simple static HOMepage for your servER to keep your services on hand, from a simple `yaml` configuration file. 

**Application Name:** Homer

**Application Site:** https://github.com/bastienwirtz/homer

**Docker Hub:** https://hub.docker.com/r/b4bz/homer

**Github:** https://github.com/bastienwirtz/homer
## Before running the docker
* ```mkdir -p /mnt/user/appdata/homer/config/```
* ```wget -O /mnt/user/appdata/homer/config/config.yml https://raw.githubusercontent.com/bastienwirtz/homer/master/config.yml```

**[`^back to top^`](#unraid-templates)**

----
# Jitsi
![Jitsi](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/jitsi.png)

**Application Name:** Jitsi

**Application Site:** https://jitsi.org/

**Docker Hub:** https://hub.docker.com/u/jitsi/

**Github:** https://github.com/jitsi/docker-jitsi-meet
## Change appdata location
```/mnt/user/appdata/jitsi-web``` -> ```/mnt/user/appdata/jitsi/web/```
```/mnt/user/appdata/jitsi-prosody``` -> ```/mnt/user/appdata/jitsi/prosody/```
```/mnt/user/appdata/jitsi-jvb``` -> ```/mnt/user/appdata/jitsi/jvb/```
```/mnt/user/appdata/jitsi-jicofo``` -> ```/mnt/user/appdata/jitsi/jicofo/```
## Notes
* https://github.com/jitsi/docker-jitsi-meet
* How it all work
![](https://335wvf48o1332cksy23mw1pj-wpengine.netdna-ssl.com/wp-content/uploads/2018/07/docker-jitsi-meet.png)

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
# Linkding
![Linkding](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/linkding.png)

**Application Name:** Linkding

**Application Site:** https://github.com/sissbruecker/linkding

**Docker Hub:** https://hub.docker.com/r/sissbruecker/linkding/

**Github:** https://github.com/sissbruecker/linkding

**[`^back to top^`](#unraid-templates)**

----
# Mailpile
![Mailpile](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/mailpile.png)

**Application Name:** Mailpile

**Application Site:** https://www.mailpile.is/

**Docker Hub:** https://hub.docker.com/r/rroemhild/mailpile/

**Github:** https://github.com/rroemhild/docker-mailpile
 
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
# Mumble
![Mumble](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/mumble.png)

**Application Name:** Mumble

**Application Site:** https://www.mumble.com/

**Docker Hub:** https://hub.docker.com/r/phlak/mumble

**Github:** https://github.com/PHLAK/docker-mumble
## Notes
* Download config.ini an customize it ```wget -O /mnt/user/appdata/mumble/config.ini https://raw.githubusercontent.com/PHLAK/docker-mumble/master/files/config.ini```
* See https://wiki.mumble.info/wiki/Murmur.ini for more options

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
# Pterodactyl-daemon
![pterodactyl-daemon](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/pterodactyl-daemon.png)

**Application Name:** Pterodactyl-daemon

**Application Site:** https://pterodactyl.io/

**Docker Hub:** https://hub.docker.com/r/ccarney16/pterodactyl-daemon/

**Github:** https://github.com/ccarney16/pterodactyl-docker

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
# Pwndrop
![Pwndrop](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/pwndrop.png)

**Application Name:** Pwndrop

**Application Site:** ttps://github.com/treyyoder/quakejs-docker

**Docker Hub:** https://hub.docker.com/r/harshavardhanj/pwndrop

**Github:** ttps://github.com/treyyoder/quakejs-docker

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

**Application Name:** Searx

**Application Site:** https://github.com/asciimoo/searx

**Docker Hub:** https://hub.docker.com/r/searx/searx/

**Github:** https://github.com/asciimoo/searx
    
**[`^back to top^`](#unraid-templates)**

----
# Selfoss
![Selfoss](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/selfoss.png)

**Application Name:** Selfoss

**Application Site:** https://selfoss.aditu.de/

**Docker Hub:** https://hub.docker.com/r/hardware/selfoss/

**Github:** https://github.com/SSilence/selfoss/
    
**[`^back to top^`](#unraid-templates)**

----
# Shiori
![Shiori](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/shiori.png)

**Application Name:** Shiori

**Application Site:** https://github.com/go-shiori/shiori

**Docker Hub:** https://hub.docker.com/r/radhifadlillah/shiori/

**Github:** https://github.com/go-shiori/shiori
## Default username and password
Username: ```shiori```
Password: ```gopher```
## Notes
* Create new account inside the web gui so the default one will be removed.

**[`^back to top^`](#unraid-templates)**

----
# Shlink
![Shlink](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/shlink.png)

**Application Name:** Shlink

**Application Site:** https://shlink.io/

**Docker Hub:** https://hub.docker.com/r/shlinkio/shlink/

**Github:** https://github.com/shlinkio/shlink

**[`^back to top^`](#unraid-templates)**

----
# Shlink-web-client
![Shlink-web-client](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/Shlink-web-client.png)

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

**Application Name:** Solr

**Application Site:** https://lucene.apache.org/solr/

**Docker Hub:** https://hub.docker.com/r/bitnami/solr

**Github:** https://github.com/bitnami/bitnami-docker-solr

**[`^back to top^`](#unraid-templates)**

----
# StackEdit
![Shiori](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/stackedit.png)

**Application Name:** StackEdit

**Application Site:** https://stackedit.io/

**Docker Hub:** https://hub.docker.com/r/qmcgaw/stackedit/

**Github:** https://github.com/qdm12/stackedit-docker

**[`^back to top^`](#unraid-templates)**

----
# Synapse-admin
![Synapse-admin](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/synapse-admin.png)

*Icons made by <a href="https://www.flaticon.com/free-icon/matrix_1774127" title="Vitaly Gorbachev">Vitaly Gorbachev</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>*
**Application Name:** Synapse-admin

**Application Site:** https://github.com/Awesome-Technologies/synapse-admin

**Docker Hub:** https://hub.docker.com/r/awesometechnologies/synapse-admin/

**Github:** https://github.com/Awesome-Technologies/synapse-admin

**[`^back to top^`](#unraid-templates)**

----
# Tar1090
![Tar1090](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/tar1090.png)

*Icons made by <a href="https://smashicons.com/" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>*
**Application Name:** Synapse-admin

**Application Site:** https://www.github.com/mikenye/docker-tar1090

**Docker Hub:** https://hub.docker.com/r/mikenye/tar1090

**Github:** https://www.github.com/mikenye/docker-tar1090

**[`^back to top^`](#unraid-templates)**

----
# Torprivoxy
![Torprivoxy](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/torprivoxy.png)

*Icons made by <a href="https://www.flaticon.com/authors/photo3idea-studio" title="photo3idea_studio">photo3idea_studio</a> from <a href="https://www.flaticon.com/" title="Flaticon"> www.flaticon.com</a>*
**Application Name:** Synapse-admin

**Application Site:** https://github.com/avpnusr/torprivoxy

**Docker Hub:** https://hub.docker.com/r/avpnusr/torprivoxy/

**Github:** https://github.com/avpnusr/torprivoxy

**[`^back to top^`](#unraid-templates)**

----
# tt-rss
![tt-rss](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/tt-rss.png)

**Application Site:** https://tt-rss.org/

**Docker Hub:** https://hub.docker.com/r/lunik1/tt-rss/

**Github:** https://github.com/lunik1/docker-tt-rss

**[`^back to top^`](#unraid-templates)**

----
# Wallabag
![Wallabag](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/wallabag.png)

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

# Wifi-card
![Wifi-card](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/wifi-card.png)

*<div>Icons made by <a href="https://www.flaticon.com/authors/bqlqn" title="bqlqn">bqlqn</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>*
**Application Name:** Wifi-card

**Application Site:** https://github.com/bndw/wifi-card

**Docker Hub:** https://hub.docker.com/r/bndw/wifi-card/

**Github:** https://github.com/bndw/wifi-card

**[`^back to top^`](#unraid-templates)**

----
# YaCy
![YaCy](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/yacy.png)

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
