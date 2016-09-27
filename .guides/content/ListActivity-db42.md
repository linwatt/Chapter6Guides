A list activity is type of activity that specializes in working with a list. It’s automatically bound to a list view, so you don’t need to create one yourself. 

![](.guides/img/31.png)

There are a couple of major advantages in using a list activity to display categories of data:

**1) You don’t need to create your own layout.**
List activities define their own layout programmatically, so there’s no XML layout for you to create or maintain. The layout the list activity generates includes a single list view. You access this list view in your activity code using the list activity’s `getListView()` method. You need this to specify what data should be displayed in the list view.


**2) You don’t have to implement your own event listener.**
The `ListActivity` class already implements an event listener that listens for when items in the list view are clicked. Instead of creating your own event listener and binding it to the list view, you just need to implement the list activity’s `onListItemClick()` method. This makes it easier to get your activity to respond when the user clicks on items in the list view. You’ll see this in action later on when we use the `onListItemClick()` method to start another activity.

**3) A ListActivity is a type of Activity that specializes in working with a ListView. It has a default layout that contains the ListView.**
Category activities generally need to display a single list view you can use to navigate to detail records, so list activities are good for this situation.
