When you update the views in your detail activity, you need to make sure that the values they display reflect the data you’ve derived from the intent. Our detail activity contains two text views and an image view. We need to make sure that each of these is updated to reflect the details of the drink.



...
//Get the drink from the intent
int drinkNo = (Integer)getIntent().getExtras().get(EXTRA_DRINKNO);
Drink drink = Drink.drinks(drinkNo);

{Check It!|assessment}(fill-in-the-blanks-1944146799)


{Check It!|assessment}(fill-in-the-blanks-2206092048)

{Check It!|assessment}(fill-in-the-blanks-3606999149)
