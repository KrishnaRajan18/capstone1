#*PROJECT PROPOSAL*

What goal will your website be designed to achieve?

*  My website will be used to search for a recipe- according to the ingredient/ by recipe name.Save a recipe to favorites and create a grocery list with the ingredients in a recipe.

 What kind of users will visit your site? In other words, what is the demographic of your users?

  * Users like students/ working individuals who need quick access to the recipes and its ingredients for a grocery shopping will access my site.

What data do you plan on using? You may have not picked your actual API yet,which is fine, just outline what kind of data you would like it to contain.
I would be using the following Technologies

* Backend: Python, Flask, PostgreSQL, SQLAlchemy
* Frontend: JavaScript, jQuery, AJAX, JSON, Jinja2, HTML5, CSS, Bootstrap
* API: Spoonacular API


 What does your database schema look like?
   
 * There will be USERS,RECIPES,LISTS,INGREDIENTS,CUSINE,AISLE TABLE 

## Features

Users can log in or register in the homepage. 

Once a user is logged in, it will lead to a page, where users can create grocery lists via AJAX POST requests, and access previously saved ones. 

Users can also search for recipes, triggering Spoonacular API calls to access recipe data.

Users can append a recipe's ingredients into a grocery list.The grocery list is organized by aisle categories, saving users from scavenger hunting in grocery stores.


Lastly, users can fovorite a recipe for future, via AJAX POST requests, which can be accessed in their profile page. The profile page includes user info .


