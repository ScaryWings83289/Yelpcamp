# YelpCamp: Data Persistence


## Style the campgrounds page
* Add a better header/title
* Make campgrounds display in a grid

## Style the Navbar and Form
* Add a navbar to all templates
* Style the new campground form

## Add Mongoose
* Install and configure mongoose
* Setup campground model
* Use campground model inside of our routes!

## Show Page
* Review the RESTful routes we've seen so far
* Add description to our campground model
* Show d.collection.drop()
* Add a show route/templates

## Refactor Mongoose Code
* Create a models directory
* Use module.exports
* Require everything correctly!

## Add Seeds File
* Add a seed.js file
* Run the seeds file every time the server starts

## Add the Comment model!
* Make our errors go away1
* Display comments on campground show page

## Comment New/Create
* Discuss nested routes
* Add rhe comment new and create routes
* Add the new comment form

## Style Show Page
* Add Sidebar to show page
* Display comments nicely

## Finish Styling Show Page
* Add public directory
* Add custom stylesheet

## Auth Part 1 - Add User Model
* Install all packages needed for auth
* Define User Model

## Auth Part 2 - Register
* Configure Passport
* Add register routes
* Add register templat

## Auth Part 3 - Login
* Add login routes
* Add login template

## Auth Part 4 - Logout/Navbar
* Add logout route
* Prevent user from adding a comment if not signed in
* Add links to navbar
* Show/hide auth links correctly

## Auth Part 5 - Show/Hide links
* Show/hide auth links in navbar correctly

## Refactor The Routes
* Use express router to reorganize all routes

## Users + Comments
* Associate users and comments
* Save author's name to a comment automatically

## Users + Campgrounds
* Prevent an unauthenticated user from creating a campground
* Save username+id to a newly created campground

## Editing Campgrounds
* Add Method-Override
* Add Edit Route for Campgrounds
* Add link to Edit Page
* Add Update Route
* Fix $set problem

## Deleting Campgrounds
* Add Destroy Route
* Add Delete button

## Authorization
* User can only edit his/her campgrounds
* User can only delete his/her campgrounds
* Hide/Show edit and delete buttons

## Editing Comments
* Add Edit route for comments
* Add Edit button
* Add Update route

<!-- /campgrounds/:id/edit-->
<!-- /campgrounds/:id/comments/:comment_id/edit-->

# Deleting Comments
* Add Destroy route
* Add Delete button

<!--Campground Destroy Route : /campgrounds/:id-->
<!--Comment Destroy Route    : /campgrounds/:id/comments/:comment_id-->

## Authorization Part 2: Comments
* User can only edit his/her comments
* User can only delete his/her comments
* Hide/Show edit and delete buttons
* Refactor Middleware

## Adding in Flash
* Demo working version
* Install and configure connect-flash
* Add Booststrap alerts to header





================================
       RESTFUL ROUTES
================================
name     url        verb            description
-----------------------------------------------------------
INDEX   /dogs       GET    Display a list of all dog
NEW     /dogs/new   GET    Display form to make a new dog
CREATE  /dogs       POST   Add new dog to DB
SHOW    /dogs/:id   GET    Show info about one dog

Campground Page
----------------------------
INDEX   /campgrounds
NEW     /campgrounds/new
CREATE  /campgrounds
SHOW    /campgrounds/:id

Comments
--------------------------------------------
NEW     /campgrounds/:id/comments/new   GET
CREATE  /campgrounds/:id/comments       POST