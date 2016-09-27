Make sure you’ve applied all the changes to *activity_top_level.xml*, and also updated *strings.xml*. 

When you run the app, you should see the Starbuzz logo displayed on the device screen with the list view underneath it. The list view displays the three values from the options array. If you click on any of the options in the list, nothing happens, as we haven’t told the list view to respond to clicks yet. 


The next thing we’ll do is see how you get list views to respond to clicks and launch a second activity.

![](.guides/img/22.png)

This app can be built using codio!

To build the app, enter the following in the terminal:
```
./gradlew build
```

If you receive a permission denied error, enter the following:
```
chmod +x gradlew
```
And run the ./gradlew build command again

If the project builds correctly, enter the following URL on your android device to download the apk:

https://{codio domain}/app/build/outputs/apk/app-debug.apk

The domain for your codio box is listed at the top of your terminal window