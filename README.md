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

# 👉 Step 1:
Create an empty activity app. You can run it on a device.

# 👉 Step 2:
Modify the `MainActivity.java` file ovveride tha activity's methods.
Use the following package to log:
```JAVA
import android.util.Log;
```

Add a Log into `onCreate`:

```JAVA
Log.i("Activity1", "onCreate");
```

Ovveride the other methods with the log:

```JAVA
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

👍 Finally you can check the app, the logs will be visible in `LogCat`. Use the tag `Activity1` to filter the logcat.