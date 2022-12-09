# Recipe Share
Recipe share is a website to keep and share your favourite recipes, which uses the Code Institute mock terminal on Heroku to run. 

Users can look at recipes and decide what they like. They can add their own recipes, read it,  edit if there are any changes and delete if 
they no longer want to change it. 

https://fun-recipe.herokuapp.com/

<img src="assets/images/responsive.jpg" width=50% alt="responsive design">

### User stories
 * The user will be able to look at and search for recipes. 
 * The user will be able to edit the recipe if they have made errors or need to make changes. 
 * The user will be able to delete the recipes when they no longer want to share it. 
 * The user will be able to sign-up, login and logout when needed. 
 * The user author will be the only one who can edit and delete their recipe.


## How to use the app
### Before login

 * The user will be able to see the name and a basic description of the recipe on the home page

<img src="assets/images/home.jpg" width=50% alt="Home recipe page">

 * The user will be able to search for the type of recipe they would like. 
 
 <img src="assets/images/search.jpg" width=50% alt="Search bar">

 * When the user clicks on here to see the recipe, they will be taken to the full recipe.
 * While logged out they wont be able to add, delete or edit recipes. 

<img src="assets/images/recipe_no_user.jpg" width=50% alt="Recipe page when not logged on">

### Signing up

 * The user is able to sign up. 
 * The user must give their username and make a password, which they will need to confirm. 
 
<img src="assets/images/sign.jpg" width=50% alt="Sign up page">
 
### Logout and login

 * The user is able to logout and login when needed.
 
<img src="assets/images/signout.jpg" width=50% alt="Logout">
 
<img src="assets/images/signup.jpg" width=50% alt="Login page">

### When the user is logged in 
 * When the user is logged in they are able to add their own recipes and share it with others. 
 
<img src="assets/images/add.jpg" width=50% alt="Add recipe page">
  
 * Only the author of the recipe will see the edit and delete buttons. 
 
<img src="assets/images/recipe.jpg" width=50% alt="Logged in recipe page"> 
   
  * The author will be able to update their recipes when needed. 
   
<img src="assets/images/update.jpg" width=50% alt="Update recipe picture"> 

* The author will be able to delete their recipes if they no longer wish to share it. 

<img src="assets/images/delete.jpg" width=50% alt="Delete recipe picture">
   
## Features
 *  Users need can find recipes online. 
 * A nice place for the user to store their recipes. 

 ## Testing
 
 ### User story testing
 * The user is able to search for recipes. 
 * The user is able to edit the recipe if they have made errors or need to make changes. 
 * The user is able to delete the recipes when they no longer want to share it. 
 * The user can sign-up, login and logout when needed. 
 * The user author is the only one who can edit and delete their recipe.


## Bugs
### Solved Bugs

### Remaining Bugs

### Validator Testing

## Deployment
This project was deployed early using Code Institute's mock terminal for Heroku
 #### Steps for early deployment:
  * Start by making a database using ElephantSQL. 
  * Then create a new Heroku app. 
  * Click on settings and Go to Convig Vars
  * Set Key to Port and Value to 8000. 
  * Then add my SECRET_KEY - same SECRET_KEY used on env.py
  * Then add DISABLE_COLLECTSTATIC for early deployment
  * Click on Deploy at top of page. 
  * Change Deployment method to GitHub. 
  * Connect to GitHub and add repository recipe. 
  * Check if manual deploy is on main otherwise set to main. 
  * Click on Deploy Branch
 #### Steps for final deployment:
  * Start by making a database using ElephantSQL. 
  * Then create a new Heroku app. 
  * Click on settings and Go to Convig Vars
  * S

## Credits
 * Code institute for the deployment terminal
 * Code institute Hello Django and I think before I blog.  
 
