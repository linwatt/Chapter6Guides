### Pass data to an activity using the ListActivity onListItemClick() method

When you use a list activity to display categories, you’ll usually use the **onListItemClick()** method to start another activity that displays details of the item the user clicked. To do this, you create an intent that starts the second activity. You then add the ID of the item that was clicked as extra information so that the second activity can use it when the activity starts.


In our case, we want to start DrinkActivity and pass it the ID of the drink that was selected. DrinkActivity will then be able to use this information to display details of the right drink. 

![](.guides/img/47.png)