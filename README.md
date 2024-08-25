# 🩵 DiscordGML

DiscordGML does everything to make it easier for you to write apps/bots in GameMaker.

> [!TIP] 
> Documentation, helpful tips, tutorials and examples can be found here: 
https://github.com/OliverDoCode/GameMaker-DiscordAPI-Integration/tree/main/docs

> [!NOTE]
> You can download **DiscordGML .yymps file** via the Discord: https://discord.gg/PVV3afa3GC

## Features
- create multiple bots/apps in one project
- easy use of the discord gateway and http requests
- let GameMaker show you everything in the help window
- simple programming thanks to various auxiliary systems such as auto-response system or auto-command updater
- send files in messages, including sprites or surfaces
- also suitable for beginners
- high priority of error handling
- Compliance with the rules of the Discord Api

## Missing, but in progress:
- Receive and send audio data
- Sharding

> [!CAUTION]
> DiscordGML/OliverDoCode assumes no liability for GameMaker projects / Discord bots/apps that regularly exceed the 
[rate limits](https://discord.com/developers/docs/topics/rate-limits) of the API. Every developer who creates a bot with DiscordGML is responsible for their own project. DiscordGML is **open source** and can be modified and controlled by anyone. Therefore, make sure that you **ALWAYS** download the **ORIGINAL version** of DiscordGML and **not a modified copy** without being 100% sure that your secret data (like the Discord bot token) will not be shared with others. 

## Functions of DiscordGML that we work with

**app()**
You can do everything with it around your app

**build()**
You use it to build objects 

**type()**
Contains all the types you need to build objects

**wrap()**
Wrap an object to see in the help window of GameMaker what this object can contain

**flags()**
Contains all flags and a function that can check flags
