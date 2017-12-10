Visit [https://developers.facebook.com](https://developers.facebook.com) and click the `Add New App` menu link.


![Facebook developer page](img/fb-developer-page.png)


On the pop-up page, click the `advance setup` link.


![Create new Facebook Application](img/fb-add-new-app.png)


Enter a name for your new app, choose an App Category and click on `Create App ID` button.


![Facebook Application details](img/fb-app-details.png)


Perform the security check and submit

![Facebook security check](img/fb-security-check.png)

You will then see a screen with list of Facebook products. Hover your cursor to **Facebook Login** and click the "Set up" button.


Now you have successfully created a Facebook Application and you should be redirected to the Application page which should look like the one on the image below.


![Facebook application dashboard](img/fb-app-dashboard.png)


Currently, your application is in development or sandbox mode.

To get the App Live, click on **App Review** sidebar menu, slide the switch close to the app name to `Yes` and finally, click the `Confirm` button.


![Change Facebook application status to live](img/fb-app-live.png)


Go back to the application **Settings >> Basic**, click the `Add Platform` button.


![Add platform to application](img/add-platform.png)


Select **Website** and enter your website URL in the corresponding form and save.


![Facebook appplication website platform](img/fb-website-platform.png)

Go to **Facebook Login >> Settings**

Ensure "Client OAuth Login" and "Web OAuth Login" are enabled. In **Valid OAuth redirect URIs**, enter `https://yoursite.com/wp-content/plugins/profilepress/social-login/?hauth_done=Facebook`. Replace "https://yoursite.com" with your website URL. If your website url contains "www", don't forget to include it in the redirect URI settings like so `https://www.yoursite.com/wp-content/plugins/profilepress/social-login/?hauth_done=Facebook`

![Facebook client OAuth settings](img/facebook-app-oath-settings.png)


Copy and save the `App ID` and `App Secrete` to the appropriate fields in ProfilePress [Social Login](configuration.md) settings page.
