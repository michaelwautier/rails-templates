# Rails Templates

Quickly generate a rails app using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).


## Minimal

Get a minimal rails app ready to be deployed on Heroku with Bootstrap, Simple form and debugging gems.

```bash
rails new \
  -T \
  -d postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/michaelwautier/rails-templates/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```

## Devise

Same as minimal **plus** a Devise install with a generated `User` model.

```bash
rails new \
  -T \
  -d postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/michaelwautier/rails-templates/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
