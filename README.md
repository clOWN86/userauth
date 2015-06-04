# Lemonstand V1 Google Analytics oAuth2
Brings Lemonstand V1 Google Analytics signing method up to date with oAuth2

1. Login to your Google Developers Console.
2. Create a project (if you haven't already got an active project)
3. Navigate to Apis under Apis & Auth and add the Analytics API to your project.
4. Navigate and create Credentials from the sidebar under Apis & Auth choose Web Application as your option, leave the Redirect URIs callback as it is (oauth2callback) prepend your domain (if not automatically pre-pended).
5. Logout of Lemonstand V1 admin area.
6. Create a new folder called googleanalytics in the modules section of your Lemonstand V1 software.
7. Add the content of this folder to the newly created googleanalytics folder.
8. Login to Lemonstand V1, you will possibly see a large alert on the dashboard, ignore this.
9. Navigate to System > Settings > Statistics and Dashboard
10. Enter your Google Developer Console credentials *NOTE* Making sure your Redirect URI is identical to the one used in Google Developer Console and Save.

# On Save
1 of 2 options will occur when accepting and authorising the web app.

1. You will either be redirected to Google Authorisation page to accept and authorise the web app.
2. An alert will flash up on the stats page with a message along the lines of "TEMPORARY MOVED" with an option to click a link which says 'here'.

If option 2 is the option click the 'here' link which will then take you through to option 1 where you can proceed to accept and authorise.