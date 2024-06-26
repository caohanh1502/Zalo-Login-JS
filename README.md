# Zalo-Login-JS
Log in to your Zalo application with a Zalo account, using html and javascript. Return an access token if login is successful.

The **code challenge** and **code verifier** are generated using [PKCE method](https://www.oauth.com/oauth2-servers/pkce/)

Demo: https://caohanh1502.github.io/Zalo-Login-JS
## Note:
No server required so the option "Check secret key when calling api get access token" in the login settings need to be turned off.
## How to:
- Go to Zalo Dev page: https://developers.zalo.me/apps
- Copy the app ID of your application and paste it into ```stringvalue.js```
- Upload files to your web hosting, then verify the domain: ```https://developers.zalo.me/app/<Your_App_ID>/verify-domain```
- Go to the login settings (```https://developers.zalo.me/app/<Your_App_ID>/login```) and set "Callback URL" to point to ```auth.html``` 

### Logout:
- Go to Zalo dev page: https://developers.zalo.me
- Logout (hover over your profile image at top right to see the option).

### Credits:
Most of the codes are based on this post: https://nguyenphudung.com/huong-dan-lay-access-token-v4-qua-zalo-api-php
