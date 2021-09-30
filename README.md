android-java-activity-lifecycle

# Android LifeCycyle of one Activity
> This is in Java

Use to check the github commits

We are chechecking these functions:
```JAVA
@Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.i("Activity1", "onCreate");
    }

    @Override
    protected void onStart() {
        super.onStart();
        Log.i("Activity1", "onStart");
    }

    @Override
    protected void onResume() {
        super.onResume();
        Log.i("Activity1", "onResume");
    }

    @Override
    protected void onPause() {
        super.onPause();
        Log.i("Activity1", "onPause");
    }

    @Override
    protected void onStop() {
        super.onStop();
        Log.i("Activity1", "onStop");
    }

    @Override
    protected void onDestroy() {
        super.onDestroy();
        Log.i("Activity1", "onDestroy");
    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Log.i("Activity1", "onRestart");
    }
```

# Step 1:
Create an empty activity app. You can run it on a device.

# Step 2:
Modify the MainActivity.java file ovveride tha activity's methods.