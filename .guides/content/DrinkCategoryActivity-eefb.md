In our case, we're going to use an array adapter to display data from the Drink.drinks array in the list view.

To initialize the array adapter, you first specify what type of data is contained in the array you want to bind to the list view. 

You then pass it three parameters: a Contex (usually the current activity), a layout resource that specifies how to display each item in the array, and the array itself. 

Here’s the code to create an array adapter that displays Drink data from the Drink.drinks array.

![](.guides/img/37.png)

You then attach the array adapter to the list view using the ListView setAdapter() method.

Behind the scenes, the array adapter takes each item in the array, converts it to a String using its toString() method and puts each result into a text view. It then displays each text view as a single row in the list view.

![](.guides/img/38.png)
