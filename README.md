# joywave-heardle

A clone of [Heardle](https://www.heardle.app/), and [K-Pop Heardle](https://heardle-kpop.glitch.me/) but for Joywave songs.

Each Joywave Heardle is randomly chosen from Joywave's discography.

code edited from: [WJSN Heardle](https://github.com/haseul/wjsn-heardle)

 <br /> 
 <br /> 
 <br /> 
 
HOW TO MAKE YOUR OWN HEARDLE (as of 4/4/22)

1. Remix this project to create your own copy of the code
2. Rename the project with the URL that you'd like to Heardle to live at
3. Open the **index.html** file & replace **"Joywave"** with the artist/genre of your heardle
4. Open the **main.js** file and replace **"Joywave"** with the artist/genre of your heardle - This will update all the text boxes where Joywave shows up
5. In the **main.js** file, replace **"@joywavez"** with your own twitter or instagram handle - This will update the contact info
6. On line **3908** of **main.js**, update the **startDate** to the current date - This will start the counter for your Heardle
7. On line **8593** of **main.js**, "const **Cn**" is initialized. Replace the text with a list of song titles that you want to show up as options in your Heardle. It should follow the format **"Song - Artist".** Make sure each song is in quotes and has a comma after it
8. On line **8666** of **main.js**, "**On**" is initialized. Here you'll have to replace the links with links to your songs. Soundcloud links work best. Each link will have to follow the following format:
   `{ url: "<link>", answer: "Song - Artist" },`
9. The order of the songs in "const Cn" should match the order in "On".

<br /> 
<br />

At the moment, the order of the songs match the order that the Heardle's will appear, so if you dont want to ruin the surprise, have someone else upload the order of the songs and links for you!

<br /> 
<br />

Glitch auto saves your code, so your changes should be available as soon as the code is editted
Heardle doesnt work in the "Open Preview Pane" option, so make sure to view it in the "Preview in new window" option
