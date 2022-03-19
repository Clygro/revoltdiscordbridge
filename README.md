# Revolt Discord Bridge
A bridge between revolt and discord using [revchatapi](https://www.npmjs.com/package/revchatapi)

## How to use?
### Setup
Go into the `index.js` file and edit: <nr>
Revolt bot token: <br>
`const revolt = "2aeNb1c-Pe8viI0r4w9zYnigi_3orVEMP5eR4G07G_p33zG74YKIF0KTDGIP9tUr"` 
Discord bot token: <br>
`const discord = "OTU0ODgxNjAxODg2NjM0MDEz.YjZkyg.djQsgN7DwG-bB8Fne7u3fZevW2g"`
Add your discord channel ids to the discordChannels array: <br>
Example: `const revChannels = ["265149813841068032"]`
Add your revolt channel ids to the revChannels array: <br>
Example: `const revChannels = ["01FFR5BSGAXVP1NJ4FSDEZ2JJH"]`

### Starting the bot
You may need to install some stuff using `npm` if you don't have it installed already, try installing the `npm` package. <br>
Next you will also need to install `revchatapi` (do `npm install revchatapi` to install).<br>
You will also need discord.js installed (do `npm install discord.js` to install) <br>
cd into your directory, if unsure do `cd` then do `cd revoltdiscordbridge`. <br>
Type `node .` into your command line. <br>
The bot should online, enjoy!
