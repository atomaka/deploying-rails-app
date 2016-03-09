##  Prepare Our Server

* `ssh root@XXX.XXX.XXX.XXX`
* Install packages

```
apt-get update
apt-get install git-core curl zlib1g-dev build-essential libssl-dev
libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev
libcurl4-openssl-dev python-software-properties libffi-dev
```

* Create user

```
useradd -m app
chsh app -s /bin/bash
```

note:
- Packages can be found by Gooleing for ubuntu ruby rails packages
