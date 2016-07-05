# karty-do-gwinta---gwent-5-decks
More modification from no-online-gwent founded on reddit.  Added all cards to 5 decks Skellige, Nillfgard, Northen, Monster and Scoiatele. Work realy nice

#Gwent-Online - code below you will find in original place: https://github.com/exane/not-gwent-online
- i just modify little code and set it little better.
- You can just copy and overwrite my changes and they will work with old code: all folder "/build"  with PNG files and "/assets" folder.
- or just download all files from this repository 

#Introduction
Not-Gwent-Online is a standalone multiplayer version of Gwent, a card game from The Witcher 3. 

#Install
##- Requirements
- [node.js](https://nodejs.org/) installed
- [GraphicsMagick](http://www.graphicsmagick.org) installed (for generating sprites)
- Any Webserver like xampp, wamp, lamp etc

##- Build
Make sure to clone the project in your webserver root folder, otherwise you won't be able to access your client later.
The root folder is often called 'www' or 'htdocs', but depends on your installed webserver.
```git
cd ~/myWebserverRoot
git clone https://github.com/exane/not-gwent-online
cd not-gwent-online
npm install
npm run build
```


##- Config
- go to /public and open Config.js
- change hostname to your address. (e.g., "192.168.123.1") <br>Make sure you don't have a trailing slash after your IP or address. (e.g., "192.168.123.1/")
- If you have to change the port then make sure you change the port on your server as well. <br>You find the server port in /server/server.js on line #18 "app.listen(#port)";

##- Start Server
```
cd ~/myProjectDirectory/not-gwent-online
node server/server.js
```

##- Start Client
- Open your browser and go to "192.168.123.1/not-gwent-online/public" or wherever you saved your project.

# - Update information:
- Added all card in all decks (mostly in polish)
- Added  new deck of skellige card. -needs more improvement to work best.
- to set your own deck just go and delete or set "//" comment line next to the name of your card that you want play. Deck file to change you will find at: /assets/data/deck.js
- to change graphic polish to english card just overwrite all .PNG file from "/public/build old"  to "/build/"

# have fun with gwent
