# Android cheatsheet basic

## Click the button and display something

````
 // MainActivity.java file
   public void submitOrder(View view){
        // the function that trigger from the UI side need to have the View
        // make a private method rather doing all stuff in same thing for the line belows.
        TextView quantityTextView = (TextView) findViewById(R.id.quantity);
        quantityTextView.setText("Hello world from google");

    }
    
    // XmL code 
    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Click Me"
        android:onClick="submitOrder"/>
        
```
