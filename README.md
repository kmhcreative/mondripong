# MondriPong
## A playable version of the Mondrian Pong animated GIFs

![mondripong-gif](https://raw.github.com/kmhcreative/MondriPong/master/images/mondripong_ani.gif "mondripong-gif")

These GIFs are both a joke combining the video game [Pong](https://en.wikipedia.org/wiki/Pong) with the artistic "neoplastic" style of [Piet Mondrian](https://en.wikipedia.org/wiki/Piet_Mondrian).

The first joke combining Mondrian's signature style with the classic arcade game "Pong" came from user "Custard" in March 2010 as part of the b3ta.com board's [Make Art More Awesome](http://www.b3ta.com/challenge/makeartmoreawesome/popular") challenge.

![pongdrian-gif](https://raw.github.com/kmhcreative/MondriPong/master/images/pongdrian.gif "pongdrian-gif")

The second animated GIF to circulate the Internet riffing on this same joke was "Pongdrian" by user "HappyToast" in March 2016 as part of the b3ta.com board's "[Video Game Art](http://www.b3ta.com/challenge/gameart/popular) challenge.

The first animated GIF saw a revival of social media sharing in January 2016, but surprisingly a Google search didn't turn up a playable version, so now here it is!  The second animated GIF also received a lot of social media attention and has now been added to Mondripong as an additional game mode.

The size and position of the elements is designed to reflect the size and positioning of the elements in the original animated GIF, even though they aren't necessarily ideal for a playable game.

## Version History

### Version 1.3

* "Single Player" mode against a (really stupid) computer AI player
* "Tournament" mode where winner is whomever wins most of 3, 5, 7, or 9 rounds
* Single games and rounds will end when either player scores 11 points
* Now has two game modes, one based on the 2010 "custard" GIF and the other on the 2016 "HappyToast" GIF
* Additional game modes can be added by creating a new "modes" object with the game parameters
* Game can be started at three different speeds (Easy, Normal, and Expert)
* Difficulty can be added by increasing the speed as you play
* Added a "spin" to the ball to prevent it being infinitely trapped between the paddles (it will eventually shake loose)
* On-screen touch controls so it can be played on phones and tablets
* Responsive layout that adapts to mobile device screens
* Scale the game up/down to fit/fill the screen
* Fullscreen mode (does not work on iOS devices)
* Bookmark to Homescreen on iOS and Android to run like a native app
* Added app and tile icons for mobile devices
* Now uses a custom webfont for interface
* Added an "About" page on Mondrian and the animated GIFs
* Added background/bezel (which can be variably faded out if it's too distracting)
* Redesigned game UI to accommodate new options, about, and game over screens

### Version 1.2

* Fixed collision detection on paddles

### Version 1.1

* Added believed source of original GIF to index and readme files
* Added vertical lines to paddles
* Objects now share draw function
* Added contributor section to header of javascript
* Fixed inconsistent code indentation
* Removed vertical centerline (which is not in original GIF)

### Version 1.0

Initial public release, created over the course of an afternoon.

* Improve collision detection, particularly for top/bottom of paddles
* Add touch events so it can be controlled on a phone or tablet
* Responsive layout so it adapts to smaller screens

## Thanks

The starting point for this game was an HTML5 Canvas tutorial by [Mailson](http://blog.mailson.org/2013/02/simple-pong-game-using-html5-and-canvas/) and, of course, the original animated GIFs and other contributors to this project on GitHub.
