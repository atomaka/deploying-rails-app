##  Quick Configuration Updates

* `config/routes`

```
Rails.application.routes.draw do
  resources :jokes
  root to: 'jokes#index'
end
```

* `Gemfile`

```
gem 'therubyracer', platforms: :ruby
```

note:
- Or use nodejs
