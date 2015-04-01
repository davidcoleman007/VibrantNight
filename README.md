# VibrantNight
Super Clean, Dark Eclipse Theme - requires Eclipse 4.4+

Instructions:
download and install Eclipse 4.4+
Go to the Marketplace and install the plugin: Eclipse Color Theme
  - http://marketplace.eclipse.org/content/eclipse-color-theme
Install the plugin: Jeeeyuls
  - http://marketplace.eclipse.org/content/jeeeyuls-eclipse-themes

restart Eclipse as needed.

open Preferences:
go to General -> Appearance -> Jeeeyul's Themes -> Presets
  - click <Import>
  - select the file "VibrantNight.epf" included in this repo
  - Select "VibrantNight" in the list of presets and then click <Apply>

Go to  General -> Appearance -> Color Theme
  - select the "Vibrant Ink" theme
  - Apply

Go to Preferences -> Ant
  - set "Ant warning message" color to : (r/g/b) 250/100/0
  - set "Ant Info message" to : 255/255/0
  - set "Ant verbosse message" to : 0/200/125
  - set "Ant debug message" to : 0/255/255

If you use eGit, go to: Preferences -> Appearance -> Colors and Fonts
  - expand the GIT tree
  - set "uncommitted Change (foreground) to yellow, so that your package explorer will look good when you have change annotations visible.

Go to Preferences -> Editors -> Text Editors
  - set Line number foreground to green or orange (whichever you like)
  - play arround with the current line highlight until you are happy - I like a blue for current line and a medium black/green tint for current debug line.  It should be visible from all angles and complement the syntax colors.

If you are on Windows and want to use Flash Builder
  - add the file "fb-4_7-plugin-encoded.link" to your %eclipse_root%/dropins folder (while Eclipse is not running)
  - edit the file and make SURE that the path is correct and points to your Flash Builder installation.
  - note, this has only been tested on Eclipse 4.4.2, and with both 64 bit eclipse and 64 bit Flash builder 4.7.  Flash builder is legal and not cracked.  I don't know if it will work on non-legal copies.  Don't ask me to help you, because I won't.
  - I recommend that you only attempt this with 64 bit versions of these applications; however, in THEORY it will work with matching 32 bit versions as well.

Launch eclipse and WAIT!!!!
  - It will take a much longer time than usual the first time that you launch after adding this dropin
  - do not kill the process.  Just be patient.
  - when it loads after quite a few minutes (registering the dropin for the first time), you should have a functional flash builder on top of your brand new Eclipse instance!
  - HAPPY DAY!

Once it runs, modify the Flash Builder Syntax coloring to the following settings:
  - ActionScript
    - ASDoc : #521283
    - Bracket/Brace : #fff600
    - Comment : #bf97de
    - Default : white
    - class/function/interface/package : leave as is
    - trace : #f2b3b3
    - var : #88cfec / -bold +italic
    - metadata : #5bfb04
    - operator : #fff600
    - string : #63ff7d
  - MXML
    - ASDoc : #521283
    - Comment : #bf97de
    - Component : #7ed9f3
    - Special : #ffba00
    - String : #63ff7d
    

    
