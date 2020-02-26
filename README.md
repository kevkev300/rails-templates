# Rails Templates

Quickly generate a rails app with the default configuration
using [Rails Templates](http://guides.rubyonrails.org/rails_application_templates.html).


## Minimal

Complient with Heroku, Bootstrap, Simple form, debugging.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/kevkev300/rails-templates/master/minimal.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```

## Devise

Complient with Heroku, Device, Bootstrap, Simple form, debugging.

```bash
rails new \
  --database postgresql \
  --webpack \
  -m https://raw.githubusercontent.com/kevkev300/rails-templates/master/devise.rb \
  CHANGE_THIS_TO_YOUR_RAILS_APP_NAME
```
