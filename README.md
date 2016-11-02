# README

<<<<<<< HEAD
=======
<<<<<<< HEAD
>>>>>>> george
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
<<<<<<< HEAD
=======
=======
users- john
ships-george
jobs
locations

users
    has many:ships, jobs

ships
    has many: jobs

jobs
    has many:ships
    has one: location

locations
    has many: ships, jobs
>>>>>>> cd31e288dc7e05f8ae4614a75e4f2bd5184195db
>>>>>>> george
