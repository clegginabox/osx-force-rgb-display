# osx-force-rgb-display

I take no credit for writing this, I just have to search Google to find it everytime I need it.
All credit to Andreas Schwarz @ http://embdev.net/topic/284710

This is a fix for OSX thinking your external monitor is a TV.

- Clone the repository
- Connect only the external monitor(s) in question (I closed my MacBook lid, for example). The script will make override files for any connected monitor.
- Type `ruby patch-edid.rb` in Terminal.
- A new folder will be created in the root of the repo. Move it into the “/System/Library/Displays/Overrides” folder. If Finder tells you that you are overwriting an existing folder, consider backing it up first.
- Restart your computer, enjoy your monitor.
