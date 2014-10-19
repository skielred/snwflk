Snowflake
=========
Installation
-------------
- Install Stylish for Chrome/Firefox.
- Click on the Stylish icon.
- Click on "Manage installed styles" (Chrome) or "Manage styles" (Firefox).
- Click on "Write New Style".
- Type *Snowflake* in the `Name` textbox.
- **On Chrome:** Create a rule pointing to *URLs starting with* `https://tweetdeck.twitter.com`.
- **On Firefox:** Add the following into the textbox, on a single line:
`@-moz-document url-prefix("https://tweetdeck.twitter.com") {`.
- Paste the text from `style.css` into the textbox, below the `@moz-document...` line if you have one.
- **Firefox only:** Scroll to the bottom of the textbox and add an extra line with a single `}` on it.
- Click on save.

Known issues
-------------
We're working on these issues, and doing what we can to fix these.
Known issues on Snowflake Minima Black (SMB):


- ~~The "Follow" button has a white font, which makes it harder to read, such as on this [screenshot](http://i.imgur.com/IZfNAt9.png).~~
- ~~The retweet window is also hard to read, like on this [screenshot](http://i.imgur.com/srcyrHj.png).~~
- The column options are unavailable.

To-do list
-------------

- Fix issues (nuff said)
- Commit a theme-wise version of Snowflake Classic Black
- Commit a theme-wise version of Snowflake Classic White
- Write and commit Snowflake Minima White
- Change the scrollbar to make it less invasive.
- "Fix" the Tweet button that does not appear when there is nothing to tweet, and looks rather [ugly](http://i.imgur.com/4Iz1n7S.png) in the theme.
- MOAR FLATTENING
- #BringBackOurColumnOptions
- Remove the [padding](http://i.imgur.com/nKjHJ8A.png) between the compose box text and the "Tweet" text.

Credits
-------------

Berter (@BerterTheBoss); created Snowflake Classic White.
Diamant (@diamantlefou); created Snowflake Classic Black.
Scimitar (@AlmtyCwrd); created Snowflake Minima Black.
Special thanks to pixeldesu (@pixeldesu / http://pixelde.su/) for Modern TweetDeck, which features were the main additions of Snowflake Minima.
