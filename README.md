![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/cyberchef.png)

# CyberChef
**Application Name:** CyberChef
**Application Site:** https://gchq.github.io/CyberChef/
**Docker Hub:** https://hub.docker.com/r/aude/cyberchef
**Github:** https://github.com/aude/cyberchef-docker

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/dashmachine.png)
# Dashmachine
**Application Name:** Dashmachine
**Application Site:** https://hub.docker.com/r/rmountjoy/dashmachine/
**Docker Hub:** https://hub.docker.com/r/rmountjoy/dashmachine/
**Github:** https://github.com/rmountjoy92/DashMachine
## Default username and password:
Username: ```admin```
Password: ```admin```
## ~~Unauthorized~~
~~If you get unauthorized page add /login <- ```http://IP:PORT/login```~~

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/db-backup.png)
# db-backup
**Application Name:** db-backup
**Application Site:** https://hub.docker.com/r/tiredofit/db-backup/
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

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/droppy.png)
# Droppy
**Application Name:** Droppy
**Application Site:** https://droppy.silverwind.io/
**Docker Hub:** https://hub.docker.com/r/silverwind/droppy/
**Github:** https://github.com/silverwind/droppy

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/filerun.png)
# FileRun
**Application Name:** FileRun
**Application Site:** https://filerun.com/
**Docker Hub:** https://hub.docker.com/r/afian/filerun/
**Github:** https://github.com/filerun/docker
## Default username and password:
Username: ```superuser```
Password: ```superuser```

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/freepbx.png)
# FreePBX
**Application Name:** FreePBX
**Application Site:** https://www.freepbx.org/
**Docker Hub:** https://hub.docker.com/r/tiredofit/freepbx/
**Github:** https://github.com/tiredofit/docker-freepbx/
## First installation 
* Take time be patient
* Wizard setup go to http://freepbx/admin/config.php

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/golinks.png)
# Golinks
**Application Name:** Golinks
**Application Site:** https://github.com/prologic/golinks
**Docker Hub:** https://hub.docker.com/r/prologic/golinks/
**Github:** https://github.com/prologic/golinks
## Usage
https://github.com/prologic/golinks#usage
    
----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/gotify.png)
# Gotify
**Application Name:** Gotify
**Application Site:** https://gotify.net/
**Docker Hub:** https://hub.docker.com/r/gotify/server/
**Github:** https://github.com/gotify/server/ 
# Before running the docker
```mkdir -p /mnt/user/appdata/gotify/config/```
```wget -O /mnt/user/appdata/gotify/config/config.yml https://raw.githubusercontent.com/gotify/server/master/config.example.yml```
## Default username and password:
Username: ```admin```
Password: ```admin```

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/homer.png)
# Homer
**Application Name:** Homer
**Application Site:** https://github.com/bastienwirtz/homer
**Docker Hub:** https://hub.docker.com/r/b4bz/homer
**Github:** https://github.com/bastienwirtz/homer
## Before running the docker
```mkdir -p /mnt/user/appdata/homer/config/```
```wget -O /mnt/user/appdata/homer/config/config.yml https://raw.githubusercontent.com/bastienwirtz/homer/master/config.yml```

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/jitsi.png)
# Jitsi
**Application Name:** Jitsi
**Application Site:** https://github.com/bastienwirtz/homer
**Docker Hub:** https://hub.docker.com/r/b4bz/homer
**Github:** https://github.com/bastienwirtz/homer
## Change appdata location
```/mnt/user/appdata/jitsi-web``` -> ```/mnt/user/appdata/jitsi/web/```
```/mnt/user/appdata/jitsi-prosody``` -> ```/mnt/user/appdata/jitsi/prosody/```
```/mnt/user/appdata/jitsi-jvb``` -> ```/mnt/user/appdata/jitsi/jvb/```
```/mnt/user/appdata/jitsi-jicofo``` -> ```/mnt/user/appdata/jitsi/jicofo/```
## Variables
https://github.com/jitsi/docker-jitsi-meet

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/kiwix.png)
# Kiwix-serve
**Application Name:** Kiwix-serve
**Application Site:** https://www.kiwix.org/
**Docker Hub:** https://hub.docker.com/r/kiwix/kiwix-serve/
**Github:** https://github.com/kiwix/kiwix-tools
## Info
* When using variable "DOWNLOAD" remove the link after the download so you don't re-download the same content again
## Content
For more content https://wiki.kiwix.org/wiki/Content

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/mailpile.png)
# Mailpile
**Application Name:** Mailpile
**Application Site:** https://www.mailpile.is/
**Docker Hub:** https://hub.docker.com/r/rroemhild/mailpile/
**Github:** https://github.com/rroemhild/docker-mailpile
 
----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/matrix.png)
# Matrix
**Application Name:** Matrix
**Application Site:** https://matrix.org/
**Docker Hub:** https://hub.docker.com/r/avhost/docker-matrix
**Github:** https://github.com/AVENTER-UG/docker-matrix
## Guides
* Unraid User - PSYCHOPATHiO [Guide](https://forums.unraid.net/topic/89502-support-a75g-repo/?do=findComment&comment=839576)
* More info about matrix configuration [here](https://github.com/matrix-org/synapse/blob/master/README.rst)

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/miniflux.png)
# Miniflux
**Application Name:** Miniflux
**Application Site:** https://miniflux.app/
**Docker Hub:** https://hub.docker.com/r/miniflux/miniflux/
**Github:** https://github.com/miniflux/miniflux
## Info
* Admin username and password is setup at in docker variables then you can change in Miniflux settings. Docker variable will be ignored when you change it inside the docker.
* PostgreSQL DB Required (Not Included)

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/riot-web.png)
# Riot-web
**Application Name:** Riot-web
**Application Site:** https://miniflux.app/
**Docker Hub:** https://hub.docker.com/r/miniflux/miniflux/
**Github:** https://github.com/miniflux/miniflux
## Before running the docker
```mkdir -p /mnt/user/appdata/riot-web/config```
```wget -O /mnt/user/appdata/riot-web/config/config.json https://riot.im/develop/config.json```

----
![](https://raw.githubusercontent.com/A75G/docker-templates/master/templates/icons/wallabag.png)
# Wallabag
**Application Name:** Wallabag
**Application Site:** https://wallabag.org/
**Docker Hub:** https://hub.docker.com/r/wallabag/wallabag
**Github:** https://www.github.com/wallabag/docker
## Default username and password:
Username: ```wallabag```
Password: ```wallabag```
## PHP errors
https://github.com/wallabag/docker/issues/185
## Missing texture and images 
Make sure the domain variable is right http://ip:6500 and if you are hosting it http://wallabag.example.com or https://wallabag.example.com.
