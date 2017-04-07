## Task

Build a clone of Yelp. The app should allow users to create and review restaurants.

## How to Use
- Visit our app on heroku: https://rafa-yelp.herokuapp.com/restaurants
To view tests:
- Clone this repo
- Install Bundler and gems
- Run rSpec in Command Line

## User Stories

```
As a user,
So I can read about a restaurant
I want to see restaurant reviews

As a visitor,
So that I can review a restaurant
I want to be able to create a restaurant listing (name, description)

As a visitor,
So that I can take down a bad entry
I want to be able to delete a restaurant entry

As a visitor,
So that I can fix an incorrect entry
I want to be able to edit a restaurant entry

As a user,
So I can see how good a restaurant is
I want to see average restaurant ratings

As a restaurant reviewer,
So that I can review a restaurant
I want to leave a score out of 5 and a comment

As a site owner
So that all restaurant entries are valid
I want to make sure they're always made with at least a name and description

As a user
So that I can leave a review
I want to be able to make an account

As a user
So that I can use my account
I want to be able to sign in

As a user
For privacy
I want to be able to sign out of my account

As a user
So that I can find buttons more easily
I want to have a nav-bar at the top of the page

As a user
So that I know who's posted what
I want user email address displayed with review

As a site owner
To keep reviews unbiased
I want a user to not be able to review their own restaurant

As a user
So I can sign in more easily
I would like the option to sign in with Facebook

As a user
So I know where a restaurant is
I would like to view its location on a map

As a user
To enhance my experience
I would like to see an image of each restaurant
```

## Version 1: MVP
- Visitors can create new restaurants using a form, specifying a name and description
- Restaurants can be edited and deleted
- Visitors can leave reviews for restaurants, providing a numerical score (1-5) and a comment about their experience
- The restaurants listings page should display all the reviews, along with the average rating of each restaurant

## Version 2:
- Users can register/login
- Sign in/out/up buttons displayed at top of page depending on whether user is signed in
- The email address of the reviewer should be displayed as part of the review
- Validations should be in place for the restaurant and review forms - restaurants must be given a name and rating, reviews must be given a rating from 1-5 (comment is optional)

## Version 3:
- Add option to sign in with Facebook
- Add option to upload an image when creating a restaurant
- Display location of restaurant on map

## Technologies used
- Ruby, RAILS, HTML
- Tested with rSpec, Capybara, Shoulda
- OmniAuth, Devise, Google Maps API, Geocoder, Paperclip, Cloudinary, Heroku
- Workflow planning with Trello
