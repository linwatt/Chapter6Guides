Once you’ve created the OnClickItemListener, you need to attach it to the list view. You do this using the ListView **setOnItemClickListener()** method. The method takes one argument, the listner itself:

![](.guides/img/25.png)


Adding the listener to the list view is crucial, as it’s this step that makes the listener get notified when the user clicks on items in the list view. If you don’t do this, the items in your list view won’t be able to respond to clicks.
