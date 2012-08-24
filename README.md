## Setup Compy Backgrounds

### Prepare default folder. I call it "cool"
To set this up, do this:

````
cd ~/Pictures
mkdir wallpapers
mkdir wallpapers/cool
````

Put files in ~/Pictures/wallpapers/cool

### Setup Rotating Background
1. Change background on second desktop
1. Add ~/Pictures/wallpapers/cool
1. Select the cool folder (of course)
1. Set desired rotation preference (I have it set to 5 mins)

### Global Hotkeys
1. Download Spark ( http://www.macupdate.com/app/mac/14352/spark )
1. I created an Applescript shortcut of Option+Command+b to call ~/Dropbox/wallpapers/scripts/random-bg-second-monitor-cool
1. Copy random-bg-second-monitor-cool.scpt to another file for other desktop background directories

## To set up iTerm to be awesome:

### Sym-link the iterm switcher script
````
cd ~/Library/Application\ Support/iTerm
mkdir Scripts
cd Scripts
ln -s ~/Dropbox/wallpapers/scripts/iterm-bg-switcher.scpt
````

### Configure iTerm
1. Open preferences
1. Go to the "Keys" tab
1. Add a Global Shortcut Key
1. I set my binding to Command+g to "Select the Menu Item" of "iterm-bg-switcher" from the "Scripts" area
