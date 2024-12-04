# Polling locations

## Background

Canada is divided into 338 electoral districts or `ridings`. Each riding is divided into polling divisions or `polls`. The number of polls per riding varies but is usually between 170-250. On election day each poll is assigned a polling location (`polling_location`) where people will vote for their assigned poll. Polls can share the same polling location.

## Application structure

The application is a Rails 7.1.3.4 application using Ruby 3.3.0. Tailwind CSS is used to style the application, and is included in the procfile. `./bin/dev` should get you up and running after you install the dependencies. 

There is a `seeds.rb` file to provide you some base data to work with. After you seed your database you should have 338 ridings, 69,606 polls, and 207 polling locations (all in the riding of Avalon).
