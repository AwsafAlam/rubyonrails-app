# Ruby on rails -app

A basic directory app in ruby on rails

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

---

## Rails cli

using the rails cli we can generate new application `rails new ruby-app` creates a new scaffolding of a ruby on rails application with all of the files and dependencies.

## Rails generator

The rails generator does a lot of boilerplate work so developers don't have to configure everything individually.

- `rails generate controller home index`

Output:

```
Running via Spring preloader in process 73401
      create  app/controllers/home_controller.rb
       route  get 'home/index'
      invoke  erb
      create    app/views/home
      create    app/views/home/index.html.erb
      invoke  test_unit
      create    test/controllers/home_controller_test.rb
      invoke  helper
      create    app/helpers/home_helper.rb
      invoke    test_unit
      invoke  assets
      invoke    scss
      create      app/assets/stylesheets/home.scss
```

Pages need webpacker to run properly

- `bundle exec rails webpacker:install`

Ruby does a lot of abstraction

- `rails routes` displays all the existing routes. [ uses rake ]

## Rest API

we can decouple the ruby on rails application and use it as a backend. for that we only need to declare the functionality in the controllers and return the expected results.

## Rake
