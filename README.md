# Discord-RGB-Snippet-WIP
 A work in progress Discord CSS Chroma RGB theme with as Powercord UI element support. (This is my first theme and it shows.) 
  The theme has an animated gradient bar at the top and the bottom of the window as well

**I am still trying to work out a way to make sure everything syncs up**
As a temp fix just open up settings to restart the animations playing.

## Installation
I have 2 versions. One where most text outside chat is RGB however it can get a bit laggy as it has some sort of css memory leak when it comes to animations looping and staying loaded.

To install, go to *your themes folder with , a command prompt/terminal* and enter the following:

    git clone https://github.com/Fahrenheit/Discord-RGB-Snippet-WIP

To change between the full RGB and the UI Only RGB swap out **Discord-RGB-No-Text-Theming.css** and **Discord-RGB.css** in powercord_manifest.json.
The default should look like "theme": "Discord-RGB-No-Text-Theming.css". To swap change the css file in the quotations to look like "theme": "Discord-RGB.css"


## Credits

Help from albaraathunder for finding some classes and helping come up with ideas.

Help from Human for figuring out the cause of lag and working out a way to reduce the CSS mem leak.
