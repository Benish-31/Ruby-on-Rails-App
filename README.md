# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

* rails g scaffold friends first_name:string last_name:string email:string phone:string twitter:string # We create migration 

* rails db:migrate # We push migration

* rails routes 

* rails g controller home index # create a controller

* rails g devise:views # create all authorisation pages

* rails generate devise:install 

* rails generate devise user # create migration

* rails db:migrate # push migration

* rails g migration add_user_id_to_friends user_id:integer:index

* rails db:migrate