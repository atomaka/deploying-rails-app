##  Setup a Middleware for Server

* Retrieve suggested Puma configuration

```
wget https://raw.githubusercontent.com/puma/puma/master/tools/jungle/upstart/puma-manager.conf
wget https://raw.githubusercontent.com/puma/puma/master/tools/jungle/upstart/puma.conf
```

* Update puma.conf

```
setuid app
setgid app
```

* Add configuration to bash execution

```
export SECRET_KEY_BASE="YOUR_SECRET_KEY_HERE"
```

note:
