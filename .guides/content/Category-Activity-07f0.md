`DrinkCategoryActivity` is an example of a category activity. A category activity is one that shows the data that belongs to a particular category, often in a list. You then use the category activity to navigate to details of the data. We’re going to use `DrinkCategoryActivity` to display a list of drinks. When the user clicks on one of the drinks, we’ll show them the details of that drink.


![](.guides/img/30.png)

To do this, we’ll create an activity containing a single list view that displays a list of all the drinks. As our activity only needs to contain a single list view with no other GUI components, we can use a special kind of activity called a **list activity**. 

So what’s a list activity? A list activity is type of activity that specializes in working with a list. It’s automatically bound to a list view, so you don’t need to create one yourself. 
