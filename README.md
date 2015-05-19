![Snowflake for TweetDeck](https://lh4.googleusercontent.com/-BWhQgIxSK3o/VEfFgg1x-LI/AAAAAAAACAU/DmN1YmAhxCM/w1200-h500-no/Snowflake_banner_blue.png)


What is Snowflake?
-------------
Snowflake is a minimalistic theme modification suite for TweetDeck. It's like real flat. [Darker than flat](http://i.imgur.com/F8RAEcw.jpg). [Flatter-than-light](http://i.imgur.com/F8RAEcw.jpg).  
Sorry, I got carried away.  
Plus, there various are fancy color schemes!  
Minima is a spiritual successor to pixeldesu's Modern TweetDeck, with easier-to-read columns and stuff.  
Also, we're sorry, if you're a dev, our code is pretty messy.  
We're looking for a JS dev and someone that's good with Firefox extensions too!  
[Which color scheme do you like the most?](http://strawpoll.me/2823721/)  

## Installation

These instructions are for Stylish on [Chromium-based browsers (like Chrome)](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe) and [Mozilla-based browsers (like Firefox)](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome). Steps will vary based on browser and plugin.

### How to add a new style

* Click on the Stylish icon.
* Click on "Manage installed styles" (Chrome) or "Manage styles" (Firefox).
* Click on "Write New Style"
* Name it "Snowflake whatever"

### How to install this style

* Name the Style anything you want, but something easy to recognise like *Snowflake* would be good.
* Paste the text from `snowflake whatever.css` for the theme you use into the textbox.

#### Chrome

* Create a rule pointing to `URLs starting with` `https://tweetdeck.twitter.com`.
* Click on **Save** and look at TweetDeck!

#### Chrome Web App (Extension)

This is a bit more work and does **NOT** require Stylish

* Download your stylesheet
* Open your file manager/explorer and navigate to `%UserProfile%\AppData\Local\Google\Chrome\User Data\Default\Extensions\hbdpomandigafcibbmofojjchbcdagbl\`
* Next, click on the folder resembling a version number, and afterwards navigate to `web` and `css`
* Now, open `snowflake whatever.css`
* **IMPORTANT STEP:** Don't replace the styles with the one from Snowflake, go down 1-2 lines and paste the Snowflake style after the original one.
* Refresh the tab/standalone window with the Chrome Extension, and you now have your style installed!

#### Firefox

* Add the following into the textbox on a single line, before the contents of Snowflake.css: 
* `@-moz-document url-prefix("https://tweetdeck.twitter.com") {`
* Scroll to the bottom of the textbox and add an extra line with a single `}` on it.
* Click on **Save** and look at TweetDeck!

Releases
-------------
- Snowflake Classic White [SCW]: Unavailable (Needs re-releasing)
- [Snowflake Classic Black](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20classic%20black.css) [SCB]
- [Snowflake Minima Black Aqua](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%20aqua.css) [SMBW]: Black and Blue color scheme
- [Snowflake Minima Black Pyro](https://github.com/WinterReign/Snowflake/blob/master/snowflake%20minima%20black%20pyro.css) [SMBF]: Black and Red color scheme
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
- [This](https://a.pomf.se/ywkrxb.png) looks like shit. Needs fixing badly.

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
- Flattening stuff such as the closing cross or the drag'n'drop thingy on the profiles/windows. Update: On it. Just gotta work out everything before comitting the changes.
- ~~Adding the new loading screen.~~ Done.
- ~~Commit Snowflake Minima Black Fire and rename Snowflake Minima Black to Aqua.~~ Done. Fire still needs fixes.
- ~~[Would you like to see the font change?](http://strawpoll.me/2823751)~~ Nevermind, fonts will be implemented as an option.
- Instead of darkening the background when you open a profile, make it blurry. This seems a little bit tricky to do. Might need an extension to do the work.
- Create a Chrome extension! Automatic implementation of CSS (making Stylish unnecessary), easier choice of options and automatic updating! What's better? We're on it. Coming soon. What's more? We might overwrite JS, with cool features such as a new notification sound.
- Some of our users have been using this with [TweetDeck Enhancer](https://github.com/ryandolan123/TweetDeck-Enhancer), and obviously, the two CSS are conflicting. Working on it.

Credits
-------------

- [Berter](http://twitter.com/BerterTheBoss); created Snowflake Classic White.
- [Diamant](http://twitter.com/diamantlefou); created Snowflake Classic Black.
- [Scimitar](http://twitter.com/wplanetary); created the Snowflake Minima suite.
- [Calv](http://twitter.com/calvcoll) who gave us useful advice and fixed a lot of issues.
- [Haruto](http://twitter.com/LordHaruto) who fixed a lot of issues, and is working on the Chrome extension.
- [Yukito](http://twitter.com/Yukito_kun_) who made a fancy logo!
- [Knowzen](http://twitter.com/Knowzen) who made fixes on his own and helped quite a lot!
- [Shookaite](http://twitter.com/Shookaite) who fixed some ugly shit on Minima White. 
- Special thanks to [pixeldesu](http://twitter.com/pixeldesu) (http://pixelde.su/) for Modern TweetDeck, which features were the main additions of Snowflake Minima.
