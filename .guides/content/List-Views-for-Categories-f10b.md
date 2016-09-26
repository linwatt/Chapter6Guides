When you structure your app in this way, you need a way of navigating between your activities. A common approach used in this situation is to use **list views**. A list view allows you to display a list of data that you can then use to navigate through the app.

Using our Starbuzz example, we said we'd have a category activity that would display a list of drinks. This might look like:
![](.guides/img/6.png)

The activity uses a list view to display all the drinks that are sold by Starbuzz. To navigate to a particular drink, the user clicks on one of the drinks, and the details of that drink are displayed.

![](.guides/img/7.png)

The drink activity is launched when the user clicks on one of the drinks listed by the drink category activity. This activity displays details of the drink the user has selected, such as its name, an image of what it looks like, and a description.

