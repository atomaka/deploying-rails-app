##  Begin a Rails App

```
gem install rails && rbenv rehash
rails new jokes && cd jokes
bundle exec rails generate scaffold Joke joke:string punchline:string
bundle exec rake db:migrate
```

note:
- source: https://github.com/atomaka/jokes-rails
