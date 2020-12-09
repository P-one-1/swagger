# README

Versions and STEPS of implementation:

* Ruby version	ruby '2.5.1'

* gem 'rails', '~> 5.2.4', '>= 5.2.4.4'

* 1. rails new swagger-demo --api

* 2. rails generate model Pet name photo_url status

* 3. rails generate scaffold_controller api/v1/pets

* 4. rails generate rspec:install

* 5. rails g rswag:install

* 6. rake rswag:specs:swaggerize
