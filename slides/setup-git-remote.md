##  Setup git Remote

* Setup the Repostiory

```
sudo su - app && cd
mkdir ~/jokes-production && cd ~/jokes-production
git init --bare
```

* Add the Hook! (~/jokes-production/hooks/post-receive)
  * post-receive from [https://goo.gl/f36vHg](https://goo.gl/f36vHg)
  * chmod +x hooks/post-receive

* Setup sudo

```
sudo sh -c 'echo "app ALL=(ALL) NOPASSWD:ALL" > /etc/sudoers.d/90-app'
```

note:
- What github does when you create a new repository
- Should definitely restrict sudo. Just add commands necessary after.
  - service puma-manager restart
  - service nginx restart
