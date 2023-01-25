# Raid Alert-Button
DOWNLOAD ZIP FILE BEFORE COPYING. A Sammi Button in JSON format for streamers to respond to virtual raids from other streamers and display effects on the screen.

How to instal: 
Download as zip file. Unzip, open, then copy the text that is between the brackets {} to your clipboard. Open "SAMMI CORE.exe", then open a Deck. Once there, right click on a square and select "Import from JSON". If you get the messege "this string is not a properly formated JSON string", make sure the text you copied from the unzipped file starts and ends with {}. (JSON text coppied from the github webpage will not format correctly.) 

How to work: 
You will need to have both SAMMI Core as well as OBS installed & linked to one another. 
On OBS create 1-3 Scenes, one called "Alerts" and two optional scenes called "HUD" and "Credits" where you will keep all the sources you will need.
All sources called "... Alert" refer to media or effects that you want to play when that Alert is triggered. All sources called "... Text" refer to the text that appears on screen when the associated Alert is triggered. 
All sources called "HUD ..." refer to an optional feature to have your most recent contributors name cycle somewhere on screen. For more information see button "HUD". 
"Saving to Credits" Section refers to another button for end-of-stream credits of all your contributors for that session. For more information, see button "End Credits". 

How to Customize:
All sections in Red should not be changed.

All sections in Blue interact with OBS and will need to have exactly the same name for sources in OBS & SAMMI in order to connect. Delays should be changed based on what timing best fits your media/effects.

All Sections in Purple can be customized BUT, BE AWARE of variables that need to be wrapped like this /$Variable$/ in order to get read correctly. Find more varibale rules at https://sammi.solutions/docs/ . Buttons were set up for Twitch but can be modified for Youtube with ease.  

All sections in Green (Optional) can be turned off by the checkbox to their upper right until desired.
