## UPDATE

GoInstant are discontinuing all services of 31st August, so it package will cease to work.

===

# Tquila Team Talk Source Code

The Tquila Team Talk applications provide tools for both live chat and real time video conferencing within Salesforce. The applications use GoInstant APIs from within VisualForce pages.

## Getting Started

To get started, you first need to create a GoInstant account. Head to http://goinstant.com and register an account. Following creation of an account, you need to create a new App. Doing so will give you the app Id and app name, which is needed for the connection to the GoInstant server. Once you have created your app, you also need to head to the Authentication section and ensure Salesforce is enabled as an authentication method for your app.

## Deploy Code

Use a deployment tool (Force.com Migration/Ant or Force.com IDE) to deploy the code into your Salesforce Org. The application is light on code, which involves a few VisualForce pages and some static resources.

## Enter app id and app name

There is a custom setting that holds the app id and application name used across the various applications. Add a record to the Tquila Team Talk Settings custom setting and input the app id and app name generated when you created you app in GoInstant

## Ready to go!

Once you have completed the above, you are ready to go. Create a Custom Tab for each of the VisualForce pages you wish to use, or go to them directly by navigating to /apex/ttt_ChatRoom or /apex/ttt_VideoConference
