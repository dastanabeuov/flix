# README

Steps are necessary to get the application up and running.

Configure app to start:

* Ruby version 3.0.0

* Rails version 7.0.0

* Database use

  Sqlite3 ore PgSql

* Database creation & initialization

  rails db:setup

* How to run the test suite
  
  rails s -p 3000

* Deployment instructions

  use basic git settings...

  git push heroku main
  heroku run rails db:migrate 
  heroku run rails db:seed