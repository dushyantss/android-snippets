``` xml
<uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
```

``` java
private boolean isNetworkAvailableAndConnected(context) {
 ConnectivityManager cm =
 (ConnectivityManager) context.getSystemService(CONNECTIVITY_SERVICE);
 boolean isNetworkAvailable = cm.getActiveNetworkInfo() != null;
 boolean isNetworkConnected = isNetworkAvailable &&
 cm.getActiveNetworkInfo().isConnected();
 return isNetworkConnected;
 }
``` 
