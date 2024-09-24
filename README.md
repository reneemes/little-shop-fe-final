# Little Shop - Coupon Codes | Final Project | Frontend Starter Repo

This Vite Little Shop - Coupon Codes FE Final Project Boilerplate is built to consume and display the data from the BE Rails API built in the Mod 2 Final Project.  

## Set Up Instructions

**Note:** Do **not** clone this repo into your backend repo. Put it somewhere else as a stand alone. The BE and FE repos will remain two separate repos and you will submit the links to each.  

1. Fork repo
1. Clone forked repo and rename it `git clone <repo> <new name>`
1. `cd` into cloned repo
1. Run `npm install`
1. Run `npm run dev` to start developing.
  1. You'll see in the terminal that the project has opened at "http://localhost:5173/"

## Notes

This FE application is build to consume the data from your Rails API.  In order for it to work, you must have your Rails API running on localhost:3000. You will see fetch errors when running the FE without the BE API up and running.  

Follow the directions in the FE requirements portion of the Little Shop Coupon Codes final project spec. When you are finished with the FE work, update this README to remove the current content and follow the template below.  

______________________________________________________  
# README Template  
Before turning this project in, erase this line and everything above it and fill in the info below.  
______________________________________________________  

# Hang in There  

Link to your GitHub. Consider also providing LinkedIn link

### Abstract:
The application is designed to simulate an admin portal for a online store. The user is able to see a list of all the merchants, update their info, view their listed items, delete the listings, and view their store coupons.

### Installation Instructions:
1. Clone the repo
2. In the terminal `cd` into the project directory
3. Run `open index.html` in the terminal

### Preview of App:
![img](/assets/little-shop-fe.jpg)

### Context:
This project is built off of an already existing repo, similar to one from a previous group project. The task was to add coupon functionality to the online store.

### Learning Goals:
* Write migrations to create tables and relationships between tables
* Implement CRUD functionality for a resource
* Use MVC to organize code effectively, limiting the amount of logic included in serializers and controllers
* Use built-in ActiveRecord methods to join tables of data, make calculations, and group data based on one or more attributes
* Write model tests that fully cover the data logic of the application
* Write request tests that fully cover the functionality of the application
* Display data for users in a frontend application by targeting DOM elements

### Wins + Challenges:
Wins:
1. Working with a front-end that pulled data from an API
2. Styling the front-end coupons view
3. Getting the application functionality up and running<br>

Challenges:
1. Createing migrations
2. Working out the different error codes for each different create sad path
3. Diving into a front-end after not working in JavaScript in a long while
4. Figuring out what goes where and how much logic is too much logic in the controller
