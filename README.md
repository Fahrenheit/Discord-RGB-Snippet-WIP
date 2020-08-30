# Discord-RGB-Snippet-WIP
 A work in progress Discord CSS Chroma RGB theme. (Has Powercord UI element support)
 The theme has an animated gradient bar at the top and the bottom of the window as

## Installation
I have 2 versions. One where most text outside chat is RGB however it can get a bit laggy as css has some sort of memory leak when it comes to animations looping.

For quick installation, go to **Settings -> Themes -> Quick CSS** and copy-paste the following code

RGB FOR EVERYTHING EXCEPT CHAT

    @import url("https://raw.githubusercontent.com/Fahrenheit/Discord-RGB-Snippet-WIP/master/Discord-RGB.css");


RGB UI ELEMENTS ONLY

    @import url("https://raw.githubusercontent.com/Fahrenheit/Discord-RGB-Snippet-WIP/master/Discord-RGB-No-Text-Theming.css");


## Credits

Help from albaraathunder for finding some classes and helping come up with ideas.

Help from Human for figuring out the cause of lag and working out a way to reduce the CSS mem leak.