When ProfilePress is [installed and activated](../installation.md), the custom pages it create for login, registration and password reset are automatically set as WordPress default. Thus when a users visit the following URLs:


* http://yoursite.com/wp-login.php
* http://yoursite.com/wp-login.php?action=register
* http://profilepress.net/wp-login.php?action=lostpassword


They will be redirect to the page containing the custom login, registration and password reset form created by ProfilePress.


**An example:** click [http://profilepress.net/wp-login.php](http://profilepress.net/wp-login.php) and you will be redirected to the website custom login page.


To alter these pages settings, click the **Settings** ProfilePress menu and go to the `Global Settings` section.


Let's see how to redirect users to a custom WordPress page after they log in and log out of your website.


### User Redirections

To redirect users to a custom page after they log in and log out, select the pages in `Redirection` section and save.


![Login, logout and edit-profile redirect](img/user-redirection.png)


If you've created a custom [edit profile page](../build/edit-profile) and want users to be redirected to the page when they click the `Your Profile` link in WordPress dashboard, check the activate checkbox of **Edit User Profile**.

![WordPress default profile link](img/wp-default-profile.png)
