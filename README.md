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

Generate sample app flow

Generate from docker setting file from copilot.
List is
- Dockerfile
- docker-compose.yml
- Gemfile

touch Gemfile.lock
docker compose run web rails new . --force --no-deps --database=mysql
docker compose build
docker compose up