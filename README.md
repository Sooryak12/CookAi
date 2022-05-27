## CookAi
##### Analysis was done in Analysis.ipynb
##### Refer Process file to understand the model.
##### Final_code_script will be used for the App
##### df-en-final is cleaned dataframe.
##### Ingredient file contains the list of all ingredients with their counts.



#### Criteria of choosing dish:

1)Added Common Ingredients [sugar,salt,water] by default.

2)Priority ranking is made based on the type of ingredients missing .[If user lacks a common ingredients for a recipe it will get better rank.ex:Curd will rank higher than saffron strands]

3)Algorithm now ranks on 3 parameters .[No. of User ingredients used ,No. of  recipe ingredients missing from user specified ingredients,Priority of Missing Ingredients].
