Earlier on in the chapter, we needed to get TopLevelActivity to react to the user clicking items in the list view. To do that, we had to create an OnItemClickListener, implement its onItemClick() method, and assign it to the list view. 

We had to set up an event listener in this way because list views aren’t hardwired to respond to clicks in the way that buttons are.

### So how should we get DrinkCategoryActivity to handle user clicks?

ListActivity implements an item click listener by default
There’s a significant difference between TopLevelActivity and DrinkCategoryActivity. Whereas TopLevelActivity is a normal Activity object, DrinkCategoryActivity is a ListActivity, a special type of activity that’s designed to work with list views.

This is significant when it comes to handling user clicks. A key difference between Activity and ListActivity is that the ListActivity class already implements an on item click event listener. Instead of creating your own event listener, **when you use a list activity you just need to implement the onListItemClick() method**.

![](.guides/img/46.png)