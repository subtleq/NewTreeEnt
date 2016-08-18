Project to try and help with healthier eating by picking food based on nutrients and price.

The main part of this is the list of foods, in the following format:

[food name]|[price]|[nutrient 1]:[amount]|[nutrient 2]:[amount]|...|[nutrient N]:[amount]

where:
[food name] - name of the food item
[price] - price for the food item
[nutrient N] - name of the Nth nutrient
[amount] - amount of the Nth nutrient

additionally, compound foods can be listed as:

[food name]|[price]|[component 1]:[amount]|[component 2]:[amount]|...|[component N]:[amount]

where:
[component N] - name of the Nth food component
[amount] - amount of a given component


If a compound food has a price of 0, the price of the components multiplied by their respective amounts and totaled together is used.


Essentially, the point is to try and find the cheapest combinations of complete nutrient requirements.
