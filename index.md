## Introduction

PiwaBot is a discord bot, made by players for players, that provides many commands for the game osu! Our project is not affiliated with [**ppy**](https://ppy.sh). Currently, it's running on a low cost server, but in the future, if it'll be necessary, we'll try to expand our infrastructure. 

It's written in C# for the framework .Net Core, using a custom Discord API wrapper and other external libraries:
* [OppaiSharp](https://github.com/HoLLy-HaCKeR/OppaiSharp)
* [Newtonsoft](https://github.com/JamesNK/Newtonsoft.Json)
* [System.Drawing.Common](https://www.nuget.org/packages/System.Drawing.Common/).

## If you need support, [join our discord server](https://discord.gg/4C2rR8D).

### Commands

Here is the list of the available commands you can execute. <br>
***Note:*** *Please, wait one second before sending another command, or your command won't be executed.*

```markdown
# General

- .ping: Measures the milliseconds elapsed while sending a message.

- .poll-create | .pc <"Question"> (<"Answer">...): Creates a poll.
- .poll-vote | .pv <Answer Number>: Votes an answer of the active poll in the current guild. 
- .poll-close | .pcl: Closes the active poll in the current guild. You must to be its creator or an administrator.

# osu!

- .follow <"Username">: Starts following specified player's activities in the current channel, for example: recent activities, S ranks and scores that are worth more than 100pp. 
- .unfollow <"Username">: Stops following specified player's activities in the current channel.
- .unfollowall: Stops following the activities of all users previously specified in the current channel.
- .following: Displays all followed users in the current channel.

- .pp <Beatmap Link> (Mods...): Calculates the pp of the specified beatmap. Optionally you can specify the mods typing them after the link, splitted by a space, using their abbreviations:
  - EZ: Easy, NF: NoFail, HT: HalfTime, HR: HardRock, HD: Hidden, DT: DoubleTime, NC: NightCore, FL: Flashlight, SO: SpunOut
  
- .orb: Searches for a ranked beatmap, and gives it to you when the bot finds one.
- .orb-u: Searches for a ranked or unranked beatmap, and gives it to you when the bot finds one.
- .osustats <"Username">: Gives osu! stats of a specified player.

More commands will be introduced soon!
```

### Bugs

PiwaBot is currently in a beta stage, so bugs can often be encountered. You're are able to report them in the official github [repository](https://github.com/Alexs4v/PiwaBot/issues).

### Support us!

We are just students and we can't afford powerful servers if it'll be necessary. If you like what we do, you can support us throught donations. 

*Not available yet.*

### [Invite PiwaBot to your discord server!](https://discordapp.com/api/oauth2/authorize?client_id=402190218679287811&permissions=519232&scope=bot)
