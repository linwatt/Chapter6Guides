When you want to get items in a list view to respond to clicks, you need to create an **OnItemClickListener** and implement its `onItemClick()` method.

The `OnItemClickListener` listens for when items are clicked, and the `onItemClick()` method lets you say how your activity should respond to the click. 

The `onItemClick()` method includes several parameters that you can use to find out which item was clicked, such as a reference to the view item that was clicked, its position in the list view (starting at 0), and the row ID of the underlying data.


We want to start `DrinkCategoryActivity` when the first item in the list view is clicked—the item at position 0. If the item at position 0 is clicked, we need to create an `intent` to start `DrinkCategoryActivity`. 

Here’s the code to create the listener:


![](.guides/img/24.png)