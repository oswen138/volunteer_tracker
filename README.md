# Volunteer Tracker Application

#### An application that allows users to track projects and volunteers working on them. 10/09/2020

#### By **Ophelia Swen**

## Description

A website created with Ruby and HTML where a user can view, add, update, and delete projects. A user can also view and volunteers and add volunteers to a project. 


## Setup/Installation Requirements

1. Open terminal and navigate to "cd Desktop"
2. Clone repository with git clone "https://github.com/oswen138/volunteer-tracker.git master"
3. Run gem install bundler and run bundle install in command line to download all dependencies
4. Run tests in the command line with RSPEC
5. You can create a copy of the database by running psql in the terminal : psql volunteer_tracker < database_backup.sql
```
createdb [DATABASE NAME]
psql [DATABASE_NAME] < database_backup.sql
createdb -T [DATABASE NAME] [TEST DATABASE NAME]
```
6. Run application in the browser of choice by typing ruby app.rb in the terminal
7. Enter in "localhost:4567" in your browser of choice

## Known Bugs
* A .env file might be needed. If it does, it should have the text PG_PASS={your postgres password} i.e PG_PASS=apple

## Technologies Used
* Ruby
  * Gems: Pry, RSpec, PG, Sinatra, Sinatra-Contrib, Capybara
* HTML
* Postgres 
* PSQL

## Support and contact details

_Email no one with any questions, comments, or concerns._

### License

*{This software is licensed under the MIT license}*

Copyright (c) 2020 **_Ophelia Swen_**