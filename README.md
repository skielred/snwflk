Snowflake
=========
What is Snowflake?
-------------
Snowflake is a minimalistic theme modification suite for TweetDeck. It's like real flat. [Darker than flat](http://i.imgur.com/F8RAEcw.jpg). [Flatter-than-light](http://i.imgur.com/F8RAEcw.jpg).  return
Sorry, I got carried away.  return
Plus, there various are fancy color schemes!  return
Minima is a spiritual successor to pixeldesu's Modern TweetDeck, with easier-to-read columns and stuff.  return
Also, we're sorry, if you're a dev, our code is pretty messy.  return
We're looking for a JS dev and someone that's good with Firefox extensions too!  return
[Which color scheme do you like the most?](http://strawpoll.me/2823721/)  return

Installation
-------------
- Install Stylish for Chrome/Firefox.
- Click on the Stylish icon.
- Click on "Manage installed styles" (Chrome) or "Manage styles" (Firefox).
- Click on "Write New Style".
- Type *Snowflake [whatever version]* in the `Name` textbox.
- **On Chrome:** Create a rule pointing to *URLs starting with* `https://tweetdeck.twitter.com`.
- **On Firefox:** Add the following into the textbox, on a single line:
`@-moz-document url-prefix("https://tweetdeck.twitter.com") {`.
- Paste the text from `snowflake [whatever].css` into the textbox, below the `@moz-document...` line if you have one.
- **Firefox only:** Scroll to the bottom of the textbox and add an extra line with a single `}` on it.
- Click on save.

Releases
-------------
- Snowflake Classic White [SCW]: Unavailable (Needs re-releasing)
- [Snowflake Classic Black](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20classic%20black.css) [SCB]
- [Snowflake Minima Black Aqua](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%20aqua.css) [SMBW]: Black and Blue color scheme
- [Snowflake Minima Black Fire](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%20fire.css) [SMBF]: Black and Red color scheme
- [Snowflake Minima Black Aero](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%20aero.css) [SMBA]: Black and Purple color scheme
- [Snowflake Minima Black Earth](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%20earth.css) [SMBE]: Black and Pale Green color scheme
- [Snowflake Minima Black Dust](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%dust.css) [SMBD]: Black and Orange color scheme
- [Snowflake Minima Black Sandstorm](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%20sandstorm.css) [SMBS]: Black and Pale Yellow color scheme
- [Snowflake Minima White Aqua](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20white%20aqua.css) [SMWW]: Blue and white color scheme

Known issues
-------------
~~We're working on these issues, and doing what we can to fix these.~~ I am proud to say, we have fixed all the issues we could fix!
Known issues on Snowflake Minima Black Aqua (SMBA):
- ~~The "Follow" button has a white font, which makes it harder to read, such as on this [screenshot](http://i.imgur.com/IZfNAt9.png).~~
- ~~The retweet window is also hard to read, like on this [screenshot](http://i.imgur.com/srcyrHj.png).~~
- ~~The column options are unavailable.~~ Finally fixed!
- ~~"Fix" the Tweet button that does not appear when there is nothing to tweet, and looks rather [ugly](http://i.imgur.com/4Iz1n7S.png) in the theme.~~
- Even if the Tweet button is fixed, there are weird issues with it.
- ~~Fix [this](http://i.imgur.com/6LAN0jy.png). It's fucking ugly, and I don't even know where to begin with *what exactly* is wrong, because **everything** is wrong.~~ FIXED!
- ~~Believe it or not, I had flattened the "Follow" and "Edit profile" button by removing the border, but something fucked it up (I don't know what) so I'm going to look further into fixing it.~~ Nevermind, it fixed itself on its own. Somehow.
- ~~REfix the column options. Somehow it fucks itself up on its own all the time.~~ Fixed. TweetDeck default CSS was overlapping the tweak, had to implement priority attribute.

Known issues on color schemes variations:
- ~~Some things are still blue. Gotta change it.~~

To-do list
-------------

- Reorganize the code, make it more *easy to read* and **add comments for other developers**.
- ~~Fix issues (nuff said)~~
- ~~Commit a theme-wise version of Snowflake Classic Black~~
- Commit a theme-wise version of Snowflake Classic White
- ~~Change the scrollbar to make it less invasive.~~ Hard to do, and honestly, could be worse.
- ~~MOAR FLATTENING~~ I don't see how I can flatten it more.
- ~~#BringBackOurColumnOptions~~ Fixed.
- ~~Remove the [padding](http://i.imgur.com/nKjHJ8A.png) between the compose box text and the "Tweet" text.~~ Had managed to do it, but I'll have to give up on it, as Twitter fucked up their code, and other stuff will be affected.
- ~~Darkening a little bit the theme to make it more eyes-friendly and improving contrast for readability maybe? (SMB)~~ Done.
- ~~Maybe blackening the profile options as well, to make them fit into the theme like the Options and dropdown menus. (SMB)~~ Done.
- Flattening stuff such as the closing cross or the drag'n'drop thingy on the profiles/windows.
- ~~Adding the new loading screen.~~ Done.
- ~~Commit Snowflake Minima Black Fire and rename Snowflake Minima Black to Aqua.~~ Done. Fire still needs fixes.
- ~~[Would you like to see the font change?](http://strawpoll.me/2823751)~~ Nevermind, fonts will be implemented as an option.
- Create a Chrome extension! Automatic implementation of CSS (making Stylish unnecessary), easier choice of options and automatic updating! What's better? We're on it. Coming soon. What's more? We might overwrite JS, with cool features such as a new notification sound.

Credits
-------------

- [Berter](http://twitter.com/BerterTheBoss); created Snowflake Classic White.
- [Diamant](http://twitter.com/diamantlefou); created Snowflake Classic Black.
- [Scimitar](http://twitter.com/AlmtyCwrd); created the Snowflake Minima suite.
- [Calv](http://twitter.com/calvcoll) who gave us useful advice and fixed a lot of issues.
- [Haruto](http://twitter.com/LordHaruto) who fixed a lot of issues, and is working on the Chrome extension.  
- Special thanks to [pixeldesu](http://twitter.com/pixeldesu) (http://pixelde.su/) for Modern TweetDeck, which features were the main additions of Snowflake Minima.
