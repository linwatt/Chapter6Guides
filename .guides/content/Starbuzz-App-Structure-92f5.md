The app contains three activities. `TopLevelActivity` is the app’s top-level activity and allows the user to navigate through the app. `DrinkCategoryActivity` is a category activity; it contains a list of all the drinks. The third activity, `DrinkActivity`, displays details of a given drink.

![](.guides/img/9.png)


1) When the app gets launched, it starts activity `TopLevelActivity`. The activity uses layout *activity_top_level.xml*. The activity displays a list of options for Drinks, Food, and Stores.

2) The user clicks on Drinks in `TopLevelActivity`. This launches activity `DrinkCategoryActivity`. This activity displays a list of drinks.

3) Details of the drinks are held in the *Drink.java* class file. `DrinkCategoryActivity` gets the values for its list of drinks from this class.

4) The user clicks on a drink in `DrinkCategoryActivity`.This launches activity `DrinkActivity`. The activity uses layout *activity_drink.xml*.

5) `DrinkActivity` gets details of the drink from the *Drink.java* class file.
