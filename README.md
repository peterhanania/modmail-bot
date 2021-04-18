<h1 align="center">
Discord Mod Mail bot
  <br>
</h1>


<p align="center">
  <a href="#about">About</a>
  •
  <a href="#features">Features</a>
  •
  <a href="#installation">Installation</a>
  •
  <a href="#setting-up">Setting Up</a>
  •
  <a href="#setting-up">Credits</a>
</p>

## About

An open source discord.js modmail bot to handle support in your server.

If you liked this repository, feel free to leave a star ⭐!

## Features

-Organised tickets<br>
-Logging<br>
-Transcripts<br>

## Installation

```
git clone https://github.com/peterhanania/modmail-bot.git
```
then run:
```
npm install
```


## Setting Up

Set up all your information in the *config.json* File in the `config` folder as such
```
{
    "token": "YOUR BOT TOKEN", 
    "prefix": "PREFIX FOR THE BOT", 
    "mongooseString": "MONGOOSE PASS", 
    "guild": "GUILD IN WHICH THREADS ARE CREATED (STAFF SERVER)",
    "mainServer": "MAIN GUILD IN WHICH THE BOT IS USED (NOT STAFF SERVER)",  
    "mainCategory": "CATEGORY UNDER WHICH THREADS ARE CREATED", 
    "logs": "CHANNEL IN WHICH EVENTS ARE LOGGED", 
    "modMailRole": "ROLE PINGED WHEN THREADS ARE CREATED (SUPPORT ROLE)"
}
```



Once done, you can launch the bot with `node index.js` or `node .`. 

## Credits
The following bot was developed by `zhue#5683`
Main repo [here](https://github.com/zhue675/discord-modmail)



Any questions? DM me on <a href="https://discord.com/users/710465231779790849">Discord</a>.
