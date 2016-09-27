We want to start `DrinkActivity` and pass it the ID of the drink that was selected.` DrinkActivity` will then be able to use this information to display details of the right drink. Here's the code:

![](.guides/img/48.png)

It’s common practice to pass the ID of the item that was clicked as it’s the ID of the underlying data. If the underlying data is an array, the ID is the index of the item in the array. If the underlying data comes from a database, the ID is the ID of the record in the table. Passing the ID of the item in this way means that it’s easier for the second activity to get details of the data, and then display it. 

That’s everything we need to make `DrinkCategoryActivity` start `DrinkActivity` and tell it which drink was selected. 
