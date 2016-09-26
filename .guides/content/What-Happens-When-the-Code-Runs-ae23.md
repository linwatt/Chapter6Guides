![](.guides/img/41.png)
**1) When the user clicks on the Drinks option, DrinkCategoryActivity is launched**. 
As DrinkCategoryActivity is a list activity, it has a default layout containing a single ListView object. This layout is created behind the scenes in Java code, so it’s not defined by XML.

![](.guides/img/42.png)

**2) DrinkCategoryActivity creates an ArrayAdapter** <**Drink>, an array adapter that deals with arrays of Drink objects.**

![](.guides/img/43.png)

**3) The array adapter’s source is the drinks array in the Drink class.**
It uses the Drink.toString() method to return the name of each drink.

![](.guides/img/44.png)

**4) DrinkCategoryActivity makes the ListView use the array adapter using the setAdapter() method.**
The list view uses it to display a list of the drink names.

