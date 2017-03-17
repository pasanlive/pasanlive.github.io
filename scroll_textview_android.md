# Making TextView scrollable in Android

Just set the

	android:maxLines = "AN_INTEGER"	
	android:scrollbars = "vertical"
properties of your TextView in your layout's xml file.

Then use:

	yourTextView.setMovementMethod(new ScrollingMovementMethod());

in your code.

Bingo, it scrolls!