# Installing Bootstrap on Rails 6 with Webpacker

This is the code for a simple tutorial that shows how to install Bootstrap on Rails 6 with Webpacker.

## Important files

* package.json
* config/webpack/environment.js
* app/javascript/packs/application.js
* app/javascript/packs/stylesheets/application.scss
* config/routes.rb
* app/views/layouts/application.html.erb
* app/views/hello/world.html.erb

## Setup

Clone the repository and change to the project directory.

    git@github.com:danielsellergren/tutorial-bootstrap-rails-6.git
    cd tutorial-bootstrap-rails-6/

Install all Ruby and JavaScript dependencies.

    bundle install
    yarn install

Run the server and open https://localhost:3000 in your browser.

    rails server
    open https://localhost:3000