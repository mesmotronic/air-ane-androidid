Android ID ANE
==============

Enables Adobe AIR 3.1+ for Android to access [ANDROID_ID](http://developer.android.com/reference/android/provider/Settings.Secure.html#ANDROID_ID). That's it.

Adds about 2KB to your app. Released under BSD license.

app.xml
-------

```
<extensions>
    <extensionID>com.mesmotronic.ane.androidid</extensionID>
</extensions>
``` 

ActionScript
------------

```actionscript
import com.mesmotronic.ane.AndroidID;

trace(AndroidID.ANDROID_ID);
```
