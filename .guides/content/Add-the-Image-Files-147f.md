We need to add these image files to the project, along with an image of the Starbuzz logo so that we can use it in our top-level activity. 

To do this, download the files starbuzz-logo.png, cappuccino. png, filter.png, and latte.png from https://tinyurl.com/HeadFirstAndroid. 

Then drag the file to the *app/src/main/res/drawable* folder in your Starbuzz project. When you add images to your apps, you need to decide whether to display different images for different density screens. In our case, we’re going to use the same resolution image irrespective of screen density, so we’ve put a single copy of the images in one folder. If you decide to cater for different screen densities in your own apps, put images for the different screen densities in the appropriate drawable* folders as described in Chapter 5.

![](.guides/img/13.png)

When you save images to your project, Android assigns each of them an ID in the form `R.drawable.image_name`. As an example, the file latte.png is given an ID of `R.drawable.latte`, which matches the value of the latte’s image resource ID in the `Drink` class.


![](.guides/img/14.png)
