# zayn-heardle

_ZAYN Heardle (or Zeardle, if you will) by [@eggtartemily](https://twitter.com/eggtartemily)_

This is a spin-off of the original [Heardle](https://www.heardle.app/) but for ZAYN songs. Each song is randomly chosen from his discography, including features. I do not own any rights to the songs used in this game. All copyright goes to ZAYN, RCA Records, and other relevant parties.

The code for this project is remixed from the [Taylor Swift Heardle](https://taylor-swift-heardle.glitch.me/).

### How to create your own custom Heardle [WIP]
1. Create a Glitch account.
2. Remix this project (or another existing custom Heardle project on Glitch).
3. In the `index.html` file, change every instance of 'ZAYN' to your artist. You can find and replace by hitting command+option+F on Mac (I don't know what the shortcut is on Windows).
4. In the `index.html` file, there is a long link to a photo of ZAYN. Replace every instance of this link with a URL to a photo of your choice.
5. In the `index.html` file, remove the Google Analytics tag at the bottom. You can replace it with your own if you want to track your site usage ([instructions here](https://support.google.com/analytics/answer/9306384?hl=en)) but it's optional.
6. In the `main.js` file, go to line 9068 where the variable `const Cn` is defined. This is your list of songs. The songs should go in the order you want the game to go. You can manually enter the songs or if you know how, you can write a separate script to randomize the tracks so you can just copy and paste.
7. In the `main.js` file, 

FYI: I am not a web developer. If you find a bug or want to help me write better code for this, DM me on [Instagram](https://instagram.com/emilyomgee) or [Twitter](https://twitter.com/eggtartemily).