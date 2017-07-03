# Starter project - API
A Rails 5 API demo/starter project, linked an Ember and Semantic UI front-end.
 
The client project side can be found [here](https://github.com/etiennebaque/starter-client).

## Command history
```
rails new starter-api --api
  
# Devise
rails generate devise:install
rails generate devise user
rails db:migrate # uncomment appropriate options in user.rb before running this
rails g migration AddAuthenticationTokenToUser authentication_token:string
rails db:migrate
```

## Resources and useful links

* [Devise](https://github.com/plataformatec/devise)
