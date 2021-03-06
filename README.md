## Now Playing
Small app to share what you're currently listening to (Music app only!)

After unsubscribing from Apple Music, there wasn't a quick way to share what I'm currently listening to with friends. With Apple Music you can share the iTunes link which is formatted nicely within the Messages app. Missing that feature quite a lot, I whipped up the majority of this app within a few hours just to restore this functionality. Tap on the artwork to share.

### Known Issues
Please look at the [TODO](https://github.com/greenywd/NowPlaying/search?q=TODO&unscoped_q=TODO)s and [FIXME](https://github.com/greenywd/NowPlaying/search?q=FIXME&unscoped_q=FIXME)s before reporting a bug.

### To-Do
- [ ] ~~Backport to iOS 11 as iOS 12 changed a few things~~ Works on iOS 11.3.1, iPhone 6 with a few bugs
- [ ] Create macOS app (Marzipan???)
- [ ] Add settings pane - customise the string, include artwork, etc.
- [ ] Resize image when sharing - 1280x1280 artwork is probably a little excessive and is quite large when sharing in Messages.
- [ ] Add a widget/message extension for ease of access
- [ ] Test when a song doesn't have proper tagging (i.e missing tag will probably show as 'nil' or not be added at all instead of 'Unknown Artist' or similar).
- [ ] Spotify support
- [ ] Think of a better name

### Screenshots
#### App (Unfinished UI)
<img src="https://raw.githubusercontent.com/greenywd/NowPlaying/master/screenshot-app-nowplaying.jpeg" width="375" height="812">

#### iMessage Extension
<img src="https://raw.githubusercontent.com/greenywd/NowPlaying/master/IMG_4962.jpeg" width="350" height="451">
