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
6. In the `main.js` file, go to line 9068 where the variable `const Cn` is defined. This is your list of songs. The songs should go in the order you want the game to go. You can manually enter the songs or if you know how to, you can write a separate script to randomize the tracks and then just copy and paste. **Note: These tracks have to follow the format `Artist - Track Title` for it to display correctly in the SoundCloud widget.**
7. Next, in the `main.js` file, scroll to the section with all the SoundCloud links. Here, you will need to replace each URL and title with the corresponding track in the list that you specified in Step 6. This has to be in the same order. Again, the answer needs to be in the `Artist - Track Title` format.
8. In the `main.js` file, search for every instance of 'ZAYN'. These will include the text for the info tab, support tab, game link, game messages, etc. Replace these with your artist and customize to your liking.
9. In the `main.js` file, find where `const Vt` is defined. Below that, there will be a list of game messages that will show depending on how many tries the user guesses the song in. Customize these to your liking.

FYI: I am not a web developer. If you find a bug or want to help me write better code for this, DM me on [Instagram](https://instagram.com/emilyomgee) or [Twitter](https://twitter.com/eggtartemily).
