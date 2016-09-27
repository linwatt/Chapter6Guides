**1) When the user starts the app, it launches TopLevelActivity.**

**2) The onCreate() method in TopLevelActivity creates an onItemClickListener and links it to the activity’s ListView.**

![](.guides/img/53.png)

**3) When the user clicks on an item in the list view, the onItemClickListener’s onItemClick() method gets called.**
If the Drinks item was clicked, the `onItemClickListener` creates an intent to start `DrinkCategoryActivity`.

![](.guides/img/54.png)

**4) DrinkCategoryActivity is a ListActivity.**
The `DrinkCategoryActivity` list view uses an 
`ArrayAdapter<Drink>` to display a list of the drink names.

![](.guides/img/55.png)

**5) When the user chooses a drink from the ListView, the onListItemClick() method gets called.**

![](.guides/img/56.png)

**6) The DrinkCategoryActivity’s onListItemClick() method creates an intent to start DrinkActivity, passing along the drink number as extra information.**

![](.guides/img/57.png)

**7) DrinkActivity is launched.**
It retrieves the drink number from the intent, and gets details for the correct drink from the `Drink` class. It uses this information to update its views.

![](.guides/img/58.png)



