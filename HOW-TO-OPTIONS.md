How to: options
=========

**NOTE: This was done and tested on the Chrome version of Snowflake. As the top lines are to change in the Firefox version, the line numbers might not be the same. Besides, that's Minima Black, so that doesn't apply to Minima White or Classic.**

Changing your global theme colors.
-------------
If you want to change colors, I suggest using the sheet for Snowflake Minima Black Magma as a base for your work.  If you use any other base CSS, the colors in this tutorial won't work.
You'll have to change various properties. To change the UI main color, search and replace `#AB2C2C` in the text with your own customized color. Replace all occurences of the color. Now, there is one thing left to do. You'll have to change `rgba(157, 67, 67, 0.66)` and `rgba(157, 67, 67, 0.1)` to a color more befitting to the one you chose. We recommend you keep the `0.66` and `0.1` as they are.

*Note: This is experimental and will be buggy. Don't try it unless you know what you are doing.*
If you want to change the shade of black that's used in the background, check out `#171717`  and change it with your shade. Keep it dark, or the theme will conflict with TweetDeck themes default settings. There are other rgba properties that won't be changed, but as I don't even recommend changing the theme background color in the first place, I won't provide additional explanations.

Changing the RT'ed/ faved or FavRT'ed tweets right border colors or disable the borders.
-------------
To change the favorited tweets colors, just replace all occurences of `#FF9B00` with the hex color code of your choice.  
To change the retweeted tweets colors, just replace all occurences of `#71B332` with the hex color code of your choice.  
The FavRT part is more complicated, as it is not the only part of the code to use this hex color code (white). To change its colors, replace the occurences of `#FFFFFF` at lines 760, 761 and 780.  
If you want to simply deactivate the borders and reinstate the old tweet colored corners, add `/*` at the beginning of line 747. Then, add `*/` at the end of either line 767 if you want to simply disable the borders, or line 781 if you want to totally remove the borders *and* the link coloring on the tweet.

Squared/ cornered profile pics.
-------------

*Note: if you are using Better TweetDeck's rounded avatars, you don't have to worry about disabling these. The squared avatars if you activate them will naturally overwrite Better TweetDeck's avatars. The rounded avatars of the CSS won't conflict over Better TweetDeck's but rather overlap these.*
The default is rounded avatars. If you prefer having squared avatars instead, however, it is also possible. Remove the `/*` at the beginning of line 786 and remove the `*/` at the end of line 804. Then, add `/*` at the beginning of line 808 and add `*/` at the end of line 826.

Custom fonts.
-------------

If you want to use a custom font, you can choose amongst [Google's catalog](https://www.google.com/fonts). You cannot use any other font, except if you host a font-face on a server, and if you knew how to do that, you wouldn't need to read this tutorial in the first place. Let's choose our font. You should be facing [this screen](http://i.imgur.com/gpctBoZ.png). Choose the font you want in the list, for instance, Roboto. Then, press the Quick-use icon that looks like [that](http://i.imgur.com/YDVJqmr.png). Now, you've got [this screen](http://i.imgur.com/2x5h65E.png). Make your choice of the styles you'd like, and select the character sets you need. The fewer, the faster your TweetDeck will be. For example, if you are to see a lot of Russian tweets, you might want to add the cyrillic and cyrillic extended sets, and so on, but it is unnecessary adding a shit ton of sets. Once you've chosen the thing, Google Fonts will automagically generate a line of code for your site. Select the `@import` [tab](http://i.imgur.com/sbtRm0b.png) and copy the line that is displayed. You will paste this line at line 1, overwriting its contents. Then, copy [this line](http://i.imgur.com/Yz8z2JR.png) and paste it in stead of lines 32 and 36, overwriting their contents.