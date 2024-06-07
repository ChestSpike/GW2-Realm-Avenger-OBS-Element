# GW2 Realm Avenger OBS Element
 
Display the Realm Avenger achievement progress in OBS.

## Step 1:

Download these files and put them in a folder (or don't, won't judge):
 - [gw2swoosh.png](https://github.com/Evorss/GW2-Realm-Avenger-OBS-Element/blob/main/gw2swoosh.png
   "gw2swoosh.png") (needed for the background)
 - [realm_avenger.html](https://github.com/Evorss/GW2-Realm-Avenger-OBS-Element/blob/main/realm_avenger.html
   "realm_avenger.html")

You need to provide an API Key with account and progression checked off.

    const apiKey = "API_KEY HERE"
You can adjust these parameters however you want to or any other part of the code:

    var  enableAnimation = true;
    const  refreshInterval = 5000; //this is in ms;
    const  text = "Realm Avenger Progress:"

## Step 2:
In OBS add the element as a Browser source, set the size as you see fit. (600x70 recommended)
![image](https://github.com/Evorss/GW2-Realm-Avenger-OBS-Element/assets/28312930/560c3452-24eb-4dbc-8feb-cb64c5d5a446)

If you see this, that means that the API Key is incorrect or not set.
![image](https://github.com/Evorss/GW2-Realm-Avenger-OBS-Element/assets/28312930/94cee704-f736-4310-b0ab-ccea6435fb94)

