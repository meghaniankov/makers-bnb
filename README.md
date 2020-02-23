
# MakersBnB

A single page app clone of Airbnb built in Ruby & Javascript. This was a group project focused on building an MVP while utilizing Agile/XP principles for the first time. The team turned client specs into user stories and then worked on each user story using pair programming. The program allows users to list spaces they have available, and to hire spaces for the night.

This was the first single page app anyone on our team had built. We really enjoyed learning the fundamentals on how to build single page apps.

## App Overview

* Single Page App
* Ruby/Sinatra server
* Javascript/Query frontend
* PostgreSQL database

## The Team
[David Papamichael](https://github.com/davidpaps) / 
[Meghan Iankov](https://github.com/meghaniankov) / 
[Shadi Khazaei](https://github.com/shadz22) / 
[Ben Auld](https://github.com/Benauld)

## Getting Started
Before you run the program, make sure your gems are up to date by running:


```
$ bundle install
```

After you have installed all gems, run ```rake``` to run all PostgreSQL databse migrations

```
$ rake
```

## Running the program

### Start Server

```sh
$ rackup -p 4567
```

### View in Browser

```
localhost:4567
```

## Running the tests

To run tests for this program, run:

```
$ rspec
```

## Built With

* Ruby
* Javascript
* Jquery
* Sinatra
* PostgreSQL
* Rspec/Capybara

## User Stories

```
As the MakersBnb manger,
So I can have people use the platform,
I would like t have users sign up

As a user,
So I can have bookings
I would like to list a space

As a user,
So I can show all of my properties,
I would like to list multiple places

As a user,
So I can personalize my listing,
I would like to give the space properties (name, description, & price per night)

As a user,
So I can only rent the property when it's available,
I would like to show the dates available

As a user,
So I can easily see my listing,
I would like to be able to sign in

As a user,
So no one messes with my account when I walk away from my computer,
I would like to log out

As a user,
So I can go on a sick vacation,
I would like to request a space

As a user,
So I can make money,
I would like to approve requests to stay at my space

As a user,
So I don't have double bookings,
I would like not show booked nights as available

As a user,
So I don't miss out on a booking,
I would like to only update the nights not available when I approve a booking

```
