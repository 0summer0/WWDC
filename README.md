Psst, want me to love you? Then [check this out](https://getbrowserfreedom.com) 😁

# The WWDC app for OS X

This is the unofficial WWDC app for OS X.

Use this app to watch WWDC sessions on your Mac and do much more. Keep reading...

**⬇️ [Click here to download the latest release](https://raw.githubusercontent.com/insidegui/WWDC/master/Releases/WWDC_latest.zip) ⬇️**

![screenshot](screenshots/screenshot.png)

Also, check this out: [WWDC app for the new Apple TV](https://github.com/insidegui/WWDC-tvOS) :)

## Searching

The app has a powerful search feature. When you first launch the app, It indexes the videos database and downloads transcripts from ASCIIWWDC, so when you search, not only will you get search results from session titles and descriptions, but also from what the presenter said in the sessions.

The app even shows a list of phrases matching your search so you can jump right to the point in the session where your searched word/phrase appears.

![Transcript Search](screenshots/transcriptsearch.png)

With the handy filter bar you can filter sessions by year, track and focus, and also filter to show only favorited or downloaded sessions.

![Transcript Search](screenshots/filterbar.png)
	
## Sharing

You can share direct links to specific session videos. Just select the session on the list and ⌘C to copy It's URL, or use the right-click menu.

![rightmenushare](screenshots/rightmenushare.png)

## Reading

WWDC for OS X is integrated with [ASCIIWWDC](http://asciiwwdc.com), so you can see and search through transcripts of the sessions while watching the videos.

![screenshot2](screenshots/screenshot2.png)

## Build Instructions

**Pre-requisites:**

- Xcode 7.3 or later
- [CocoaPods](https://cocoapods.org)

Clone the repository:

	$ git clone --recursive https://github.com/insidegui/WWDC.git

Install dependencies:

	$ pod install


### Cask

You can also install using [Homebrew Cask](http://caskroom.io):

	$ brew cask install wwdc
	
### PlayBack Tip: Speed Up / Slow Down

Speed up or slow down playback by ⌥ + clicking on the skip forward or backward arrows on the player window.
