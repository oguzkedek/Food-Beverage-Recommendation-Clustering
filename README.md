# About Dataset  

This dataset consists of 200K+ recipes and 1.1M+ recipe reviews covering 18 years of user interactions and uploads on Food.com (formerly GeniusKitchen). used in the following paper:  

Generating Personalized Recipes from Historical User Preferences Bodhisattwa Prasad Majumder, Shuyang Li, Jianmo Ni, Julian McAuley EMNLP, 2019 https://www.aclweb.org/anthology/D19-1613/

### Data Analysis Part  

In the data analysis part, detailed analyses of the recipes, users and contributors were made. In addition, using NLP techniques, ingredients, recipe names, and reviews were examined and word clouds were created. Finally, sentiment analysis was performed on the reviews, and the rating averages of the positive reviews and negative reviews were examined.  

### Content Based Recommendation  

In this part,recipe definitions and recipe steps were examined and a content-based recommendation system was built.Content-based filtering methods are based on a description of the item and a profile of the user's preferences 

### Matrix Factorization Recommendation  

The main purpose of this part, in which the basics of matrix factorization recommendations is explained and its implementation is realized, is to learn how many points our customers who did not rate for the recipe can give to these recipes by using the interaction based on the user latent factors and item latent factors.  

### Clustering  

In this part, a clustering model was bulilt based on nutritional values, ingredients and tags.  



- user_id       : User ID  
- recipe_id     : Recipe ID  
- date          : Date of interaction  
- rating        : Rating given  
- review        : Review text  
- name          : Recipe name  
- id            : Recipe ID  
- minutes       : Minutes to prepare recipe  
- contributor_id: User ID who submitted this recipe  
- submitted     : Date recipe was submitted  
- tags          : Food.com tags for recipe  
- nutrition     : Nutrition information (calories (#), total fat (PDV), sugar (PDV) , sodium (PDV) , protein (PDV) , saturated fat   
- n_steps       : Number of steps in recipe  
- steps         : Text for recipe steps, in order  
- description   : User-provided description
- ingredients   : List of ingredient names  
- n_ingredients : Number of ingredients



The dataset can be accessed from the link below.  

https://www.kaggle.com/datasets/shuyangli94/food-com-recipes-and-user-interactions?select=PP_recipes.csv