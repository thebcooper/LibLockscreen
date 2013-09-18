LibLockscreen, the easiest way to make/load custom lockscreens on iOS.

v0.1

ABOUT:

Fully supporting every display resolution, this is a "lib" (whatever that is, library I'm guessing) to provide easy methods for basic lockscreen functionality.
This gives you (the developer) a blank canvas on which to work, with simpler API to use than through a series of hooks like before.
User wise, this will allow the user to switch lockscreens with ease, going day to day on a different lockscreen.


README:

No source code yet I'm thinking...  Hopefully after I add in more stuff and figure out the licenseing. (have any suggestions on what to use for this?).
This is a very very very developmental (is that a word?) thing, and should be treated as such. It is probably missing a lot of features, and not doing things right either. I'm still new to obj-c, so I learn as I go.
Yes, there is a LOT of stuff to add to this, and thing to cleanup/fix. Just something to get the idea out there and to the public.

I'm hoping this encourages developers to make nice looking lockscreens without worrying about messing something up functionality wise.


CURRENT FEATURES:

Loading of custom lockscreen bundles (and disabling the feature entirely)
Means to respond to passcode being accepted or failing, as well as showing/hiding the passcode (called when it shows or hides, not for showing or hiding it)
Method that is called whenever the clock should be updated.
Intercepting the show/hide of the media controls (for presenting your own I'm guessing)
Easily get artist and album name change (looking back, I was sick when I programmed that and forget to get the song as well... will fix that later)
Detecting when a call is incomming, as well as the show/hide of the emergency call screen.
Handling of notifications, they are passed to your lockscreen in a simple NSDictionary.
Unlock the device.
Show the passcode screen of the device
Get the lockscreen background UIImage of the device.

SEE IT IN ACTION:

Add in http://bcooper.me/beta to your Cydia sources and install it, as well as the example1 (subject to renaming, and then publishing to cydia after it is completed...).

Also check out the NIC template for liblockscreen, so you can make your own :)
