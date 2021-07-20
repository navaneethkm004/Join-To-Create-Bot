[![join-to-create-bot](https://github-readme-stats.vercel.app/api/pin/?username=navaneethkm004&repo=join-to-create-bot&theme=dark)](https://github.com/navaneethkm004/join-to-create-bot)<br/>

A basic Join to Create Bot, Which works perfectly finem, Easy to setup!

## Installation | How to use the Bot

 **1.** Install [node.js v12](https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode) or higher

 **2.** Download this repo and unzip it   |   or git clone it
 
 **3.** Install all of the packages with **`npm install`**     |  the packages are   **`npm install node.js discord.js`**
 
 **4.** start the bot with **`node index.js`**

## Usage - index.js

```javascript
const Discord = require("discord.js");          //load the Discord.js Library
const client = new Discord.Client();            //make a new Client
const config = require("./config.json");        //load in all of the config files
client.on("ready", ()=>console.log("READY"));   //log when the bot gets ready
const jointocreate = require("./jointocreate"); //load the jointocreate.js file
jointocreate(client);                           //call the jointocreate file
client.login(config.TOKEN);                     //start the bot with the bot token
```

## **NOTE:**

*If you are having errors/problems with starting delete the package.json file and do, before you install the packages `npm init`*

## SUPPORT ME

<div align="center">
            <a href="https://www.buymeacoffee.com/navaneethkm" target="_blank" style="display: inline-block;">
                <img
                    src="https://img.shields.io/badge/Donate-Buy%20Me%20A%20Coffee-orange.svg?style=flat-square" 
                    align="center"
                />
            </a></div>
            
## CREDITS

<a href="https://github.com/Tomato6966/Discord-Join-to-Create/blob/main/jointocreate.js" target="_blank">Tomato6966</a>
