# HTML 5 Nyan Cat #

This is an attempt at faithfully reproducing [this YouTube video](http://www.youtube.com/watch?v=QH2-TGUlwu4) as closely as possible, while looping infinitely, purely with HTML5 and SVG. No plugin-based audio players, no animated GIFs. Just code, music, and the browser.


## Known bugs with this code ##

The animation doesn't work on mobile browsers that do actually support `image/svg+xml`.


## Known browser issues ##

### Global ###
* Some browsers don't support `<audio>`
* Some browsers don't support object tags with `image/svg+xml`

### Firefox ###
* [BMO Bug 654787](https://bugzilla.mozilla.org/show_bug.cgi?id=654787): Looped audio is not seamless

#### Firefox on Linux with PulseAudio ####
* [BMO Bug 582513](https://bugzilla.mozilla.org/show_bug.cgi?id=582513) and [PulseAudio bug 866](http://pulseaudio.org/ticket/866): Two-second delay at end of each loop


## Contributors ##

* [Ian Weller](https://github.com/ianweller): HTML, CSS and SVGs
* [Ryan Rix](http://rix.si): Audio splicer and finder of `<audio>` bugs
