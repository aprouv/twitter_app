# README

# Ruby on Rails Tutorial sample application
This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*]

## Getting started
To get started with the app, clone the repo and then install the needed gems:
```
$ gem install bundler
$ bundle config set --local without 'production'
$ bundle install
```
Next, migrate the database:
```
$ rails db:migrate
```
Finally, run the test suite to verify that everything is working correctly:
```
$ rails test

If the test suite passes, you'll be ready to run the app in a local server:
```
$ rails server
