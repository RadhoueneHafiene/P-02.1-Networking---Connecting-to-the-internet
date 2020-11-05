# P-02.1-Networking---Connecting-to-the-internet
# 7. Task 6: Missing Permission

Comment out the
<uses-permission android:name="android.permission.INTERNET" /> 
             
statement in the AndroidManifest.xml and then run the app. Make a search in the app, and then look in the Android Monitor logcat.

QUESTION

In the Android Monitor logcat, what error do you see when the app tries to connect to the Internet?

E/RichInputConnection: Unable to connect to the editor to retrieve text
