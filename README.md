# Project manager - SaaS - Work-in-progress

This is a project management system. There is a free tier of one project, with multiple users, and a paid tier of multiple projects. 
There will be a admin user. Devise is used for authentication.

It is built with Ruby 2.6.3 on Rails 6.1 and PostgresSQL as the dev and prod db, browser tested on safari and chrome. Created Jan 2021 as part of a Ruby on Rails tutorial by Mashrur Hossain.

## Steps Followed
 
* Create new rails app specifying to use postgres for the db
<!-- * Configure the config/database.yml file for the user role and db specified in setup -->
<!-- * Install React Router, Bootstrap, jQuery and Popper for the front-end -->
<!-- * Set up the Homepage index as root route -->
<!-- * Configure Rails to use React for the front-end -->


## To Run App on your local machine:

From the terminal: Clone the repo and change to that directory:
```
$ git clone https://github.com/laurieroy/rrails-proj-mgmt-saas
```

Install the gems locally:
```
$ bundle install
```

Create databases: 
```
$ rails db:create db:migrate
```
(builds a development and testing database)


<!-- Seed database with initial 9 recipes: (optional). It runs the code found in `~/rails_react_recipe/db/seeds.rb`.
```
$ rails db:seed
``` -->

## Run
To run your server locally
```
$ rails s
```

By default the application will listen on port 3000. Nav to http://localhost:3000 to see the app in the browser.

To shut down the server use `Ctrl-C`

<!-- ### TODO:

 I plan to add in the following functionality: -->

