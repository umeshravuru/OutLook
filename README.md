# OutLook
Outlook API's to send email 

1. Take the get endpoint from "Hit this in browser"
2. It will ask you to login.
3. Once we login, it will redirect to a localhost url.
4. Copy the value after code  in the URL.
5. Use that value in "Get Access and Refresh Token Uisng 'CODE'" tab to get access and refres token.
6. Use that access token in. "Send email using Access token" to send emails.
7. When ever the access token is expired use "Get Access Token from Refersh token" with Refresh toekn from step 5.

Note: 
1. Access token will expire after some time.
2. Refresh token expires when more than X refresh token were generated, the oldest one expires.
