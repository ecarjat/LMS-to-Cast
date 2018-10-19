Allows Chromecast devices to be used in Logitech Media Server.
Pre-packaged versions for Windows (XP and above), Linux (x86, x64 and ARM) and OSX can be found here https://sourceforge.net/projects/lms-to-cast/ and here https://sourceforge.net/projects/lms-plugins-philippe44/

See support thread here: http://forums.slimdevices.com/showthread.php?104614-Announce-CastBridge-integrate-Chromecast-players-with-LMS-(squeeze2cast)&p=835640&viewfull=1#post835640

To re-compile, use makefile (Linux only, need some mods for OSX and Windows) using:
https://github.com/nanopb/nanopb
https://github.com/akheron/jansson
https://github.com/philippe44/mDNS-SD (use fork v2)
https://sourceforge.net/projects/pupnp (there are a few patches to apply first against 1.6.19)

