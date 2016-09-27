The `onCreate()` method in `TopLevelActivity` creates an `onItemClickListener` and links it to the activity’s `ListView`.

![](.guides/img/26.png)

When the user clicks on an item in the list view, the `onItemClickListener`’s `onItemClick()` method gets called.
If the Drinks item is clicked, the `onItemClickListener` creates an intent to `startDrinkCategoryActivity`.


![](.guides/img/27.png)