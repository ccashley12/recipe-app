# recipe_app

## Overview
recipe_app focuses on creating a web application using the Django framework. The backend stores recipes and their respective data, and users can create their own recipes, as well as read what is already available. There is currently **no user registration available** for this application as it is out of the scope of the project requirements, so a superuser must be created in order to login to the app.

## Features
- User Authentication: Secure user login system.

- Recipe Management: Users can create recipes and upload images for them.

- Difficulty Calculation: The application calculates the difficulty of recipes based on cooking time and number of ingredients.

## Usage
- Home: The home page displays a welcome message and login button. Clicking Login will redirect users to the login form on a separate page.

- Collection: The Collection page displays a list of all available recipes within the app. Clicking on a recipe name or image will navigate to its Details page.

- Details: The Details page shows detailed information about a recipe, including ingredients, cooking time, difficulty, and its image.

- About: The About page shows developer contact information, including portfolio website link, LinkedIn, GitHub, Medium, and email address.

- Search: The Search page allows users to search for any and all recipes available within the database and provides chart visualizations related to recipes data.

- Add Recipe: Form for adding recipes, including fields for the name, ingredients, cooking time, and image. Difficulty is automatically calculated.
