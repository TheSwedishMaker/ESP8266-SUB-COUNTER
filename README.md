# ESP8266-SUB-COUNTER
A simple YouTube and Instagram Subscriber Counter

This is an ongoing project to create a subscriber counter using an ESP8266 Wemos D1 mini with a LED Matrix Display. 

Follow the instructions below to create your own. Watch the video to get more information on how to do the wiring. 

Use the code on your project. 

- Enter the Wifi SSID and your password at the marked location in the file. 
- Enter your Google API V3 key at the marked location
- Enter your Channel ID at the marked location

UPDATE 20210121 
Since Instagram has blocked several request being made from the same IP-adress this now uses a workaround with Facebook API. 

You need to get a Long Lived User Access Key from Facebook API. Follow this video guide to create the USER ID and ACCESS TOKEN: https://www.youtube.com/watch?v=9UCyRyJyZAo Once that is done, go here: https://developers.facebook.com/tools/debug/accesstoken and paste your Access token and then click Debug and then click Extend Access Token. This extended access token will work for about two months until it has to be replaced with a new one. This is the best working option so far. 

Add the access token and User Id to the main sketch. 

That's it. 

Watch the video for more details or read the complete guide over on theswedishmaker.com
