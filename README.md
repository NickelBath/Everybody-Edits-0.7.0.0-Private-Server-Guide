# Everybody-Edits-0.7.0.0-Private-Server-Guide
A guide for making an everybody edits server with most of the files provided

Tools you need:

JPEXS Free Flash Decompiler [Github Repo of JPEXS](https://github.com/jindrapetrik/jpexs-decompiler)
A Flash Player:
  [Newgrounds Player (Windows)](https://www.newgrounds.com/flash/player)
  [Standalone Flash Player (linux) (flathub)](https://flathub.org/apps/details/com.adobe.Flash-Player-Projector)
  
firstly create a PlayerIO Game and download the files
on the starting page of the playerIO server

second, you'll have to make a dll or you can use the one used in EEmulator, really doesn't make a difference

third, upload the game code that should be named "FlixelwalkerFX3"

then, open the Flash Decompiler and open the SWF, opening the scripts folder and open the <default package>
look for a script named "mygame" and open it, going to line 49 that should be
"PlayerIO.connect(stage, "game-string","public","whatever","",function(c:Cleint):void"

if you went on the page of your PlayerIO game you would have noticed something titled ">your game< game ID: >your game id<"
copy the game id and replace the old game string with your new game string.

if you followed the guide (and if you have uploaded the DLl game code) you would be able to launch a new room
