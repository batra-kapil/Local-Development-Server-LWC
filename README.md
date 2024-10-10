# What is Salesforce Local Development Server? Step by step guide for installation and use

With Local Dev (Beta), you can develop your Lightning web components (LWCs) in a real-time preview of your Lightning app or Experience Cloud Lightning Web Runtime (LWR) site. The preview automatically updates when you save changes to your source code, so you can iterate faster on your LWCs without deploying code or manually refreshing the preview in your browser.


## Who Can Access the Local Dev Beta Experience? 
Local Dev is available for users in Winter '25 sandboxes as an open beta, and it's turned off by default. You can also enable Local Dev for scratch orgs.
With Local Dev, you can run a preview of the following types of Salesforce projects.
- Lightning Experience
- Salesforce mobile app
- LWR Sites for Experience Cloud

## Steps to install and use Local Dev Server

Step 1 : Create a Winter 25 developer org using below link  
https://www.salesforce.com/form/signup/prerelease-winter25/

Step 2 : Enable the Dev Hub

Step 3 : Create a Scratch Org

Step 4 : Install the local dev server using this command "sf plugins install @salesforce/plugin-lightning-dev"

Step 5 : Enable Local Dev Server -- > Quick Find --> Local Dev

Step 6 : In your SFDX project, open the file config/project-scratch-def.json.
In the settings section of the file, add the key "enableLightningPreviewPref" and set it to true.

step 7 : Run this command in terminal and enjoy the show "sf lightning dev app"

Your environment will be getting a message at the top if you have installed it successfully.

I have used below component to test it in the video tutorial : 
https://www.salesforcebolt.com/2022/04/custom-password-validation-ui-LWC.html
