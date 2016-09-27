As you’ve seen, when you get a category activity to start a detail activity, you get items in the category activity list view to respond to clicks. When an item is clicked, you create an intent to start the detail activity. You pass the ID of the item the user clicked as extra information in the intent.

When the detail activity is started, the detail activity can retrieve the extra information from the intent and use it to populate its views. In our case, we can use the information in the intent that started `DrinkActivity` to retrieve details of the drink the user clicked.


When we created `DrinkCategoryActivity`, we added the ID of the drink the user clicked as extra information in the intent. We gave it a label of `DrinkActivity.EXTRA_DRINKNO`, which we need to define as a constant in `DrinkActivity`:
```
public static final String EXTRA_DRINKNO = "drinkNo";
```

As you saw in Chapter 3, you can retrieve the intent that started an activity using the `getIntent()` method. If this intent has extra information, you can use the intent’s 
`get*()` methods to retrieve it. Here’s the code to retrieve the value of `EXTRA_DRINKNO` from the intent that started `DrinkActivity`:
```
int drinkNo = (Integer)getIntent().getExtras().get(EXTRA_DRINKNO);
```

Once you’ve retrieved the information from the intent, you can use it to get the data you need to display in your detail record.

In our case, we can use `drinkNo` to get details of the drink the user selected. `drinkNo` is the ID of the drink, the index of the drink in the drinks array. This means that you can get the drink the user clicked on using:
```
Drink drink = Drink.drinks[drinkNo];
```

This gives us a `Drink` object containing all the information we need to update the views attributes in the activity:

name="Latte"
description="A couple of espresso shots with steamed milk"
imageResourceId=R.drawable.latte
