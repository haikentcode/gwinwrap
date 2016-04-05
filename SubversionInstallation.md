### Warning ###
The following instructions are only recommended if you are willing to possibly experience crashes and freezes, as well as bugs. If you are NOT willing to do this, please do not use gwinwrap just yet. This is a budding application and it is not without its faults. Come back once the final release is out, and you will be content with a stable experience :)

### What's New? ###
A list of all changes to the code is available, with notes about potential problems and/or bugs. The current revision appears on top. [View list of Changes...](http://code.google.com/p/gwinwrap/source/list)

# Installation via SVN for Ubuntu users #

  1. Make sure you have [installed xwinwrap](http://www.getdeb.net/search.php?keywords=xwinwrap) from getdeb.net.
  1. **Optional:** Install extra screensavers from Synaptic Package Manager by searching for "xscreensaver" and installing likely packages.
  1. Open a terminal window (Applications>Accessories>Terminal).
  1. **Optional:** Install mplayer for video support:
```
sudo apt-get install mplayer
```
  1. Install SVN:
```
sudo apt-get install subversion
```
  1. Run the following command to download the code:
```
svn checkout http://gwinwrap.googlecode.com/svn/trunk/ gwinwrap-read-only
```
  1. 'cd' (change directories) to the directory you just downloaded:
```
cd $HOME/gwinwrap-read-only
```
  1. Make gwinwrap executable:
```
chmod a+x gwinwrap.py
```
  1. And run the application:
```
./gwinwrap.py
```

If this seems complex, it is because this is a new application and is not stable enough to be run outside of a terminal (in my opinion). It is of course possible (once making the gwinwrap.py file executable) to double-click gwinwrap.py to launch gwinwrap, but you may want to see the terminal output.

A setup.py script is planned to make installation simpler.

## Easily Updating ##
If updates are made to the code, you can "cd" to the gwinwrap-read-only directory:
```
cd $HOME/gwinwrap-read-only
```
then run
```
svn up
```
and your code will update the the latest and greatest (but not necessarily the most bug-free) version!