##  Install Ruby

* `sudo su - app`
* Install rbenv

```
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
source ~/.bash_profile
```

* Install and use Ruby

```
rbenv install 2.3.0
rbenv global 2.3.0
gem install bundler
```

note:
- rbenv vs rvm vs chruby: pick whichever you want
