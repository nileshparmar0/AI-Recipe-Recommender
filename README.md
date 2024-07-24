Recipe Recommender AI

This project is an AI-powered recipe generator that suggests recipes based on the ingredients you have and your dietary preferences. It uses natural language processing (NLP) to preprocess ingredients and match them with a database of recipes.

Installation:
To run this project, you need to have Python and the necessary libraries installed.

Prerequisites:
• Python 3x
• NLTK (Natural Language Toolkit)

Installing NLTK
You can install NLTK using pip:
    pip install nltk

Downloading NLTK Data:
The script requires specific NLTK data packages. You can download them using the following commands:
    import nltk
    nltk.download('punkt')
    nltk.download('stopwords')

How the Project Works:
1. Recipe Database: A sample database of recipes with ingredients, source links, dietary preferences, and instructions.

2. Preprocessing: The preprocess_recipe function uses NLTK to tokenize and remove stopwords from the input ingredients.

3. Generate Recipe: The generate_recipe function matches the processed ingredients with the recipes in the database, considering dietary preferences if provided.

4. Suggest Similar Recipes: The suggest_similar_recipes function suggests two similar recipes from the database.

5. User Interaction: The main function interacts with the user to get the list of ingredients and dietary preferences, generates a recipe, and suggests similar recipes.

Running the Project
To run the project, execute the following command:
    python recipe_generator.py

Author:
This project was developed by Nilesh Parmar. 
Feel free to contact me for any questions or feedback.
https://www.linkedin.com/in/nilesh-parmar-/
