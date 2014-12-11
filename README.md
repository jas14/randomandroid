randomandroid
=============

Random classes I make for Android.

Includes:

### DeactivatableLinkMovementMethod
Link the LinkMovementMethod, but doesn't follow the link if the user dragged and released far enough away. To use, just set as your `TextView`'s movement method, like this:


    TextView myTextView = (TextView) findViewById(R.id.my_text_view);
    myTextView.setMovementMethod(DeactivatableLinkMovementMethod.getInstance());
