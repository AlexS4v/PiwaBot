## Introduction

PiwaBot is a discord bot, made by players for players, that provides many commands for the game osu! Our project is not affiliated with [**ppy**](https://ppy.sh). Currently, it's running on a low cost server, but in the future, if it'll be necessary, we'll try to expand our infrastructure. 

It's written in C# for the framework .Net Core, using a custom Discord API wrapper and other external libraries:
* [OppaiSharp](https://github.com/HoLLy-HaCKeR/OppaiSharp)
* [Newtonsoft](https://github.com/JamesNK/Newtonsoft.Json)
* [System.Drawing.Common](https://www.nuget.org/packages/System.Drawing.Common/).

### Commands

Here is the list of the available commands you can execute. <br>
***Note:*** *Please, wait one second before sending another command, or your command won't be executed.*

```markdown

# General

- .ping: Measures the milliseconds elapsed while sending a message. 

# osu!

- .follow <Username>: Starts to follow specified player's activities in the current channel: 
PiwaBot will send a message (in the channel where the command was executed) when he'll get at least an S or more than 100 pp. It'll also send a message when there's a new profile's recent activity.

- .unfollow <Username>: Stops following specified player's activities in the current channel.
- .unfollowall: Stops following the activities of all users previously specified, in the current channel.

- .pp <Beatmap Link> (Mods): Calculates the pp of the specified beatmap. Optionally you can specify the mods typing them after the link, splitted by a space, using their abbreviations:
  - EZ: Easy, NF: NoFail, HT: HalfTime, HR: HardRock, HD: Hidden, DT: DoubleTime, NC: NightCore, FL: Flashlight, SO: SpunOut

- .orb: Searches for a random beatmap, and gives it to you when the bot finds one.
- .osustats <Username>: Gives osu! stats of a specified player.

More commands will be introduced soon!
```

### Bugs

Because PiwaBot is currently in a beta stage, bug can often be encountered. You're are able to report them in the official github [repository](https://github.com/Alexs4v/PiwaBot/issues).

### Support us!

We are just students and we can't afford powerful servers when they'll be necessary. If you like what we did, you can support us throught donations. 

*Not available yet.*
