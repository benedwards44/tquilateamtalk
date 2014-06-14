# Tquila Team Talk Source Code

The Tquila Team Talk applications provide tools for both live chat and real time video conferencing within Salesforce. The applications use GoInstant APIs from within VisualForce pages.

## Getting Started

To get started, you first need to create a GoInstant account. Head to http://goinstant.com and register an account. Following creation of an account, you need to create a new App. Doing so will give you the app Id and app name, which is needed for the connection to the GoInstant server. Once you have created your app, you also need to head to the Authentication section and ensure Salesforce is enabled as an authentication method for your app.

## Deploy Code

Use a deployment tool (Force.com Migration/Ant or Force.com IDE) to deploy the code into your Salesforce Org. The application is light on code, which involves a few VisualForce pages and some static resources.

## Enter app id and app name

Both the ttt_ChatRoom and ttt_VideoConference pages require you to add in your app id and app name, which was created when you set up your GoInstant app.
