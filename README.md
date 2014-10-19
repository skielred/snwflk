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
