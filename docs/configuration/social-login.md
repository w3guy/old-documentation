ProfilePress is bundled with a social login feature whereby users can log in to their existing account or create an account using their social media accounts.  


Currently, only Facebook, Twitter, LinkedIn, Google and GitHub is supported. More coming soon.


Let's go over the process of creating applications in the various social networks in order to get the required app. credentials.


**Note:** The generated application credentials should go into appropriate form field in `Social Login` settings page and subsequently saved.


![ProfilePress social login settings page](img/social-app-credentials.png)


## Creating a Facebook Application

Visit [https://developers.facebook.com](https://developers.facebook.com) and click the `Add New App` menu link.


![Facebook developer page](img/fb-developer-page.png)


On the pop-up page, click the `advance setup` link.


![Create new Facebook Application](img/fb-add-new-app.png)


Enter a name for your new app, choose an App Category and click on `Create App ID` button.


![Facebook Application details](img/fb-app-details.png)


Perform the security check and submit

![Facebook security check](img/fb-security-check.png)


Now you have successfully created a Facebook Application and you should be redirected to the Application page which should look like the one on the image below.


![Facebook application dashboard](img/fb-app-dashboard.png)


Currently, your application is in development or sandbox mode.

To get the App Live, click on **Status & Review** sidebar menu, slide the switch close to the app name to `Yes` and finally, click the `Confirm` button.


![Change Facebook application status to live](img/fb-app-live.png)


Go back to the application settings, click the `Add Platform` button.


![Add platform to application](img/add-platform.png)


Select **Website** and enter your website URL in the corresponding form and save.


![Facebook appplication website platform](img/fb-website-platform.png)


Copy and save the `App ID` and `App Secrete` to ProfilePress `Social Login` plugin page.



## Creating a Twitter Application

Login to Twitter [developer center](ps://dev.twitter.com/) using your Twitter account and navigate to the [Application Management](https://apps.twitter.com/) console.


Click on the **Create New App button** to initiate the Twitter application creation.


Fill the form and click the submit button to create the application.


![Twitter application form](img/twitter-application-form.png)


Below are the form fields and their description.


**Name:** Display name of your application. Also use during user authentication.


**Description:** A short description of your website.


**Website:** The full URL of your website. (prefixed with `http://` or `https://`)


**Callback URL:** `http://yoursite.com/wp-content/plugins/profilepress/social-login/?hauth.done=Twitter`.  
Replace `http://yoursite.com` with your website URL.


Read and agree to the *Developer Agreement* and finally, click the create button.


We're now done creating the application.


To get the application consumer key and secret needed by ProfilePress, navigate to the API Keys tab.


The API keys and API secret is also referred to as the consumer key and consumer secret, respectively.


![Application consumer keys and secrete](img/app-keys-secret.png)


Although not needed by ProfilePress, the access token and access token secrets are used during users authentication.


To get these tokens; still at the API Keys tab, scroll downward and click on the `Create my access token` button.


![Token button](img/create-access-tokens.png)


Refresh the page and the application tokens will be shown to you.


![Twitter application access tokens](img/access-token-details.png)



## Creating a LinkedIn Application
