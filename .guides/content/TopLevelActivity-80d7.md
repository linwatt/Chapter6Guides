When we created our project, we called our default activity TopLevelActivity.java, and its layout activity_top_level.xml. We need to change the layout so it displays an image and a list.

![](.guides/img/15.png)

Here’s the code to define the image view in the layout:

![](.guides/img/16.png)

When you use an image view in your app, you can use the android:contentDescription attribute to add a description of the image; this makes your app more accessible. In our case, we’re using a string value of "@string/starbuzz_logo". We then add this to strings.xml:

![](.guides/img/17.png)