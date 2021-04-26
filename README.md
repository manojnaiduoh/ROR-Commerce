# RORCommerce

Run these commands sequentially after cloning the repo...

* `bundle update`
* `bundle install`
* `sudo apt-get install imagemagick`
* `bundle exec rails g spree:install --user_class=Spree::User`
* `bundle exec rails g spree:auth:install`
* `bundle exec rails g spree_gateway:install`
* `rails s`
### After execution of above commands. Follow these...

*  Now visit `http://localhost:3000`
*  Visit `http://localhost:3000/admin` for admin dashboard and use | email -> `spree@example.com` | password -> `spree123`