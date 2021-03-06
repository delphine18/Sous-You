# **Sous You**

![Home Page](./public/images/home_page.png) 
## Overview
“Sous You” is a recipe and grocery management application which can introduce new recipes to users based upon their dietary preferences. 

![Sign Up](./public/images/sign_up.png)

As users are prompted to sign up for the application they will be asked to categorize their dietary preferences as one of the following: 'Vegan', 'Vegetarian', 'Paleo', 'Pescatarian', or 'No Preference'. These 5 categories will dictate what recipes (and groceries) will be sent to the user's profile page through the Edamam API. 

![Recipe Cards](./public/images/recipes.png)

In addition to other typical fields such as name and email address, users will also be asked to provide their zip code so an integrated Google Map can show the user where all the local grocery stores in their area are. 

![Map and Grocery List](./public/images/map_grocery.png)

All answers to the sign up prompt are stored via MySQL database and authenticated through Passport. After a user creates an account, they'll easily be able to log back into their account any time!

![Log In](./public/images/login.png)

The goal of this application is to expose users to a meal planning platform each week to cook new and exciting meals that they would not normally prepare. Additionally, it aims to streamline grocery shopping for the week of recipes by providing users all of the necessary ingredients through the chosen recipes each week.

## Technologies Used

* Languages: 
    * HTML
    * CSS
    * Javascript
* Libraries:
    * Jquery
    * Bootstrap
* Database:
    * MySQL
* API’s:
    * Google Maps
    * Edamam
* Authentication:
    * Passport
* Server Hosting:
    * Heroku
* Node Modules:
    * Too many to count

## Future Development

* Users can select 5 -7 recipes out of 10 or more prompted recipes so they can have more recipes each week that suit their needs or wants.
* Budget preferences on sign up
* Grubhub/Postmates delivery option for the nights you don’t want to cook at home.
* Grocery store map shows which stores have current deals or coupons for items on your grocery list. 
* Saved recipes tab.
* More map features.
