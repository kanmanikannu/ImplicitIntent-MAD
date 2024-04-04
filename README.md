# Ex.No:3a Develop program to create a text field and a button “Navigate”. When you enter “www.gmail.com” and press navigate button it should open google page using Implicit Intents.


## AIM:

To create a navigate button using Implicit Intent to display the gmail page using Android Studio.

## EQUIPMENTS REQUIRED:

Latest Version Android Studio

## ALGORITHM:



## PROGRAM:
```
/*
Program to print the text “Implicitintent”.
Developed by: Kanmani U
Registeration Number : 212221040070
*/
```
#### @Override protected void onCreate(Bundle savedInstanceState) { EditText editText; Button button;
```
super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);

    button=findViewById(R.id.button);
    editText=findViewById(R.id.editTextText);

    button.setOnClickListener(new View.OnClickListener() {
        @Override
        public void onClick(View v) {
            String url=editText.getText().toString();
            Intent intent=new Intent(Intent.ACTION_VIEW, Uri.parse(url));
            startActivity(intent);
        }
    });
}
}
```

## OUTPUT
![MAD](https://github.com/kanmanikannu/ImplicitIntent-MAD/assets/114866367/373adb60-e076-49f9-979e-30500cb5b8a6)




## RESULT
Thus a Simple Android Application create a navigate button using Implicit Intent to display the gmail page using Android Studio is developed and executed successfully.


