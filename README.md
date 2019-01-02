# ponymote-studio
A site made to help make BPM-compatible compact Reddit Ponymote CSS  
  
\[](/abcookie)  
  
## Set-up  
It's just HTML, you can host it on a server, open it up locally or [visit my website](https://rebane2001.com/ponymotes/) to use it  
  
## Usage  
1. Import and name all of your spritesheets by using the file picker under **Motesheet upload**  
2. Use the **Add emote** button to add an emote  
3. Fill out the fields:  
  **Name**: Name of the emote  
  **Spritesheet**: Spritesheet the emote is on  
  **Size**: Size of the emote in pixels  
  **Offset**: Offset of the sprite in either pixels or percentage  
  Note: Offsets work kind of opposite as to how you might expect them to, eg to go one mote to the right you would use [-100%,0%]  
  **Tags**: Tags your emote will have, seperated by commas (eg "+rainbowdash,+equestriagirls")  
4. Use either the **Update** button beside your emote or **Update all** button on the top to see a preview of how your emote will look like  
5. Repeat steps 2 to 4 until you have made all the emotes you wanted to  
6. Save the end result:  
  **Save CSS**: Saves a CSS file, you can use the contents directly on Reddit without modifications  
  **Save tags**: Saves a json file containing all the tags, give this to Typhos  
  **Save PMS**: Saves a PMS (PonyMoteStudio) project file. For bigger projects, you can leave and later load this PMS file to continue work on your project  
  
## Features
* Shows filesize as red if it goes over Reddit's limit  
* Saving/loading to custom PMS file to continue work later on  
* Exports Reddit CSS and a json taglist  
* Does some weird magic to make the CSS file incredibly compact    
* Previews your motes  
* Runs directly in your browser, cross-platform  
* Probably runs on your grandma's Windows XP laptop  
* Probably runs on your weird Gentoo i3 setup too  
* Has all the features you would ever want from it (provided you can code and it's possible to do in HTML5/JS)    
  
## Features I wish we had (might be implemented in the future)  
* Uploading separate images and turning them into a stylesheet (could be done with a HTML5 canvas)
