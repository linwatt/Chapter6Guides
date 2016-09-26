If there’s no layout, how are we going to get the data in ListView? We can’t reference the strings.xml like we normally do

![](.guides/img/35.png)

Using android:entries only works if the data is a static array in strings.xml. 

If you need to bind your list view to data held in something other than a string array resource, you need to take a different approach; you need to write activity code to bind the data. In our case, we need to bind our list view to the drinks array in the drinks class. 