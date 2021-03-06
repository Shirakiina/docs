# GitHub authentication

CoreOS Enterprise Registry supports using GitHub or GitHub Enterprise as an authentication system.

## Create an OAuth application in GitHub

Following the instructions at [Create a GitHub Application](github-app.md).

**NOTE:** This application must be **different** from that used for GitHub Build Triggers.

## Visit the management panel

Sign in to a super user account and visit `http://yourregister/superuser` to view the management panel:

<img src="img/superuser.png" class="img-center" alt="Enterprise Registry Management Panel"/>

## Enable GitHub authentication

<img src="img/enable-auth.png" class="img-center" alt="Enable GitHub Authentication"/>

- Click the configuration tab (<span class="fa fa-gear"></span>) and scroll down to the section entitled **GitHub (Enterprise) Authentication**.
- Check the "Enable GitHub Authentication" box
- Fill in the credentials from the application created above
- Click "Save Configuration Changes"
- Restart the container (you will be prompted)
