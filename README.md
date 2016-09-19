# stellar-donation-plugin
JS Plugin to receive Lumens donations on your site

This plugin adds a form to your webpage in order for users to donate lumens to a specified stellar account.

#Installation
Download the "stellar.donate.js" file and add it to your web page

`<script type="text/javascript" src="stellar.donate.js"></script>`

#Usage
Place the following code snippet in any part of your page

`<div id="stellar-donate" data-dest="YOUR-STELLAR-ACCOUNT-ID"></div>`

Remember to replace "YOUR-STELLAR-ACCOUNT-ID" with your actual account ID.

#Demo
See it live in action here
[on the Saza Wallet Website](https://www.saza.com.ng "Saza Wallet")

#How It Works
Note that this plugin works with the donate endpoint of the Saza Wallet API.

User Inputs:
- Amount: Amount to be donated in XLM
- Source Seed: The seed for the source account sending the donation

These values are sent to Saza for processing and if all values are apporpriate the amount is transfered to the destination account specified above.

**Note:** The seed is not stored by Plugin or Saza. This is just used for verification and signing of the transaction by the source account

#Recommendation
- It is **STRONGLY RECOMMENDED** that this plugin is used over https connections only.
- This plugin uses [twitter bootstrap](https://www.getbootstrap.com "Twitter Bootstrap") for styling. You should add this to your project or use alternative styles.






