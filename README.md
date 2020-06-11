"# Node_two_step_authentication" 

To create your API key, you have to sign in to Authy Dashboard. Authy is a service provided by Twilio specifically for 2 Factor Authentication .

You either have to install Authy app on your mobile or provide your phone number while signing up so that they can send you a SMS before directing to the Authy dashboard. You can either login with the authy credentials or with twilio account to which you have linked your authy account.

Once you do that, you will be asked to enter the Authy Token. If you have installed the Authy app, you will get a notification with the token in it. Alternatively you can request the token via SMS.

Assuming you are now an Authy user and logged in to your dashboard, use following steps to create an application.
1. Click on “+ New Application” link at the bottom of the navigation panel.
2. This will open up a dialog box. Let’s call our application “demo-app”.
3. In Dashboard , you can see two keys - API key for Production and API key for Testing.


Clone or Download the code.
Run npm -i  , npm install authy , npm i body-parser
Replace 'your-auth-key' with your generated key.
Run node app.js to run the application.
