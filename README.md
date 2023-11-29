# Zalo-Login-JS
Log in to your Zalo application with a Zalo account, using html and javascript. Return an access token if login is successful.

Demo: https://caohanh1502.github.io/Zalo-Login-JS
## How to:
- Go to Zalo Dev page: https://developers.zalo.me/apps
- Copy the app ID of your application and paste it into stringvalue.js
- Set "Callback URL" to point to auth.html: ```https://developers.zalo.me/app/<Your_App_ID>login```
- You will also need to turn off "Check secret key when calling api get access token".
- Upload files to your web hosting, then verify the domain: ```https://developers.zalo.me/app/<Your_App_ID>/verify-domain```

### Get rid of the saved access token (force logout):
- Go to Zalo web: https://chat.zalo.me
- Login, then logout.
