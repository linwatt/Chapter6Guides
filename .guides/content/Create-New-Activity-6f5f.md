Create the new activity called DrinkCategoryActivity and uncheck the Generate Layout File

![](.guides/img/32.png)

Here’s what the basic code looks like to create a list activity. As you can see, it’s very similar to creating an activity. Replace the contents of DrinkCategoryActivity.java with the code below:


![](.guides/img/33.png)

The above code creates a basic list activity called DrinkCategoryActivity. Because it’s a list activity, it needs to extend the ListActivity class rather than Activity. 

The other difference is that you don’t need to use the setContentView() method to say what layout the list activity should use. This is because list activities define their own layouts so you don’t need to create one yourself. The list activity handles this for you.

