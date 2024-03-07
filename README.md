1. Add your sender ID to the app/res/values/strings.xml:
```
<string name="fcm_sender_id">YOUR_SENDER_ID</string>
```
2. Add your application code to the app/manifests/AndroidManifest.xml
```
<meta-data android:name="com.pushwoosh.appid" android:value="YOUR_APP_CODE" />
```
3. Add your google-services.json to the app/ folder

