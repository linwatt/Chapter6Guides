- Sort your ideas for activities into top-level activities, category activities, and detail/edit activities. Use the category activities to navigate from the top-level activities to the detail/edit activities.

- Image resources go in one or more of the drawable* folders. You reference them in your layout using 
<font style="font-family:courier;">@drawable/image_name</font>. You access them in your activity code using <font style="font-family:courier;">R.drawable.image_name.</font>

- An ImageView holds an image. Add it to your layout using <**ImageView**>. Use <font style="font-family:courier;">android:src</font> to set its source, and 
<font style="font-family:courier;">android:contentDescription</font> to give it an accessible label. The equivalent methods in Java are 
<font style="font-family:courier;">setImageResource()</font> and <font style="font-family:courier;">setContentDescription()</font>.

- A **ListView** displays items in a list. Add it to your layout using <**ListView**>.

- Use <font style="font-family:courier;">android:entries</font> in your layout to populate the items in your list views from an array defined in strings.xml.

- A **ListActivity** is an Activity that comes with a ListView. You get a reference to the ListView using <font style="font-family:courier;">getListView()</font>.
  - A ListActivity has its own default layout, but you can replace it with your own.

- An **adapter** acts as a bridge between an AdapterView and a data source. ListViews and Spinners are both types of AdapterView.

- An **ArrayAdapter** is an adapter that works with arrays.

- Handle click events on Buttons using 
<font style="font-family:courier;">android:onClick</font> in the layout code.

- Handle click events on a ListView in a ListActivity by implementing the <font style="font-family:courier;">onListItemClick()</font> method.

- Handle click events elsewhere by creating a listener and implementing its click event.

