# Toast Application
Hey folks, This is the Toast Application Project. In this project you will learn how you can customize your Toast in Android.

![alt text](https://github.com/ayushgemini/toast-application/blob/master/Screenshot_2020-05-24-16-03-00-715_com.geminisoftservices.toast.jpg)

## Usage

```java
 LayoutInflater inflater = getLayoutInflater();
                View toastLayout = inflater.inflate(R.layout.custom_toast, (ViewGroup) findViewById(R.id.llCustom));
                Toast toast = new Toast(getApplicationContext());
                toast.setDuration(Toast.LENGTH_LONG);
                toast.setView(toastLayout);
                toast.show();
      
© 2020 GitHub, Inc.
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
