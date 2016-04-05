# Easily add motion to your desktop! #
![![](http://farm4.static.flickr.com/3274/2809972354_44e3cef7f9_m.jpg)](http://farm4.static.flickr.com/3274/2809972354_141e952e3b_o.png) ![![](http://farm4.static.flickr.com/3174/2809972350_ed29c0805d_m.jpg)](http://farm4.static.flickr.com/3174/2809972350_9c3ac30c85_o.png)
![![](http://farm4.static.flickr.com/3012/2809983006_7d4a26861f_m.jpg)](http://farm4.static.flickr.com/3012/2809983006_78f320136b_o.png)

## I strongly recommend using [this new fix of xwinwrap](http://tech.shantanugoel.com/projects/linux/shantz-xwinwrap) with gwinwrap--the sticky feature is now fixed so minimizing all will no longer minimize the xwinwrap effect! The link includes a deb; you must UNinstall old xwinwrap before trying to install this version. ##

### [SVN Installation for Ubuntu users...](http://code.google.com/p/gwinwrap/wiki/SubversionInstallation) ###

## Choose, set, and run--it's that simple. ##

A **simpler alternative** to xwinwrap's confusing commands, this unofficial chooser panel currently supports both **xscreensavers** and **videos** (through mplayer). It offers a few **options** (opacity and whether to use nice) and starts xwinwrap with a screensaver or video of choice (+ optional arguments). If the chosen screensaver allows the "--speed" option, it will detect that and enable the slider (this is not always reliable).

A few **example presets** are included, but it's easy to create your own **new effects** and save them to use again.

For now, execute it in the directory. It requires **xscreensaver** and **xwinwrap**, and **mplayer** for video support.

### TODO (in order of priority) ###
  1. Add a button to show the manpage of the effect the user wishes to use (for easier options reference)
  1. Add an Import/Export option so that users can share their own custom presets with others.
  1. Detect screensaver arguments and add widgets accordingly, along with a brief description and the name, rather than filename, of the saver (this would be quite a task).
  1. Code is written by newbie coder (me), perhaps it needs cleanup.