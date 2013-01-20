Artisan for iOS
===========

Artisan is a simple iOS application to search for and display information and mixes from a particular musical artist. It utilizes the 8Tracks and Last.FM APIs.

If you have any questions, email me at nathan@nathanmock.com or create a new issue with specifics.

## Getting Started
Obtain your API keys from [Last.FM](http://www.last.fm/api/account/create) and [8Tracks](http://8tracks.com/developers/new).

Next, open up Xcode and define the constants, `EIGHT_TRACKS_API_KEY`and `LAST_FM_API_KEY` in [`ArtistInformationResultsHandler.h`](https://github.com/nmock/artisan-ios/blob/master/Artisan/ArtistInformationResultsHandler.h) with the API keys you just obtained.

## Screen Shots
![Initial Screen](http://i.imgur.com/0BaXNIN.png)
![Artist Information](http://i.imgur.com/kN965LI.png)
![Mixes](http://i.imgur.com/oQ4LOEr.png)

## Why is this open source?
This is open source because I hope that you can learn from it! This is a simple app that should inspire new iOS app developers. I am still learning too, so any improvements or suggestions in the way that I am doing things are greatly appreciated.

This is also my way of giving back to the community, I have learned so much from other open source projects here on GitHub. This is my first project I've decided to make open source, hopefully I can contribute more in the future.


## License
Artisan for iOS is released under a slightly modified [Simplified BSD License](https://github.com/nmock/artisan/blob/master/LICENSE).

Please don't upload this code directly to the App Store as is without making subsantial improvements. In other words, please don't be a jerk.


## Contributing
If you want to fix bugs or implement new features, have at it! All that I ask is that you make proper attributions. If you make something spiffy, send it over, I'd love to see it! Keep those pull requests coming!


## Stay updated
Check out my other app on the App Store, [Instago](http://www.instagoapp.com) ([@instagoapp](http://www.twitter.com/instagoapp)). 

Follow me on Twitter, [@nmock](http://www.twitter.com/nmock).


## Known Bugs / Possible improvements
More robust API response field / error checking

Paginate 8Tracks mix feed

Wrap 8Tracks mix feed

Parse / handle links in artist bio (i.e. correct mispellings, link to other artist pagees, etc.)

Save bandwidth / load times by loading remote @2x / @1x assets appropriately

Abstract view drawing methods

Handle no results
