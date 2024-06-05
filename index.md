<h1 align="center">Buckshot Roulette Discord Bot</h1>

[![Github release](https://img.shields.io/badge/current_bot_version-v0.5.4-green?style=for-the-badge
)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)
[![updated](https://img.shields.io/badge/Last%20update-13th%20may%20at%2008%3A42-00ffff?style=for-the-badge)](./ToS.html)

[![tos](https://img.shields.io/badge/terms_of_service-v1.0.2-green?style=for-the-badge
)](.\ToS.html)
[![updated](https://img.shields.io/badge/Last%20update-5th%20June%20at%2010%3A49-00ffff?style=for-the-badge)](.\ToS.html)

[![privacy policy](https://img.shields.io/badge/Privacy_Policy-v0.1.0.4-green?style=for-the-badge
)](./Privacy%20Policy.html)
[![updated](https://img.shields.io/badge/Last%20update-6th%20may%20at%2008%3A28-00ffff?style=for-the-badge)](./Privacy%20Policy.html)

# Overview
- [Informations](#brdb)
    - [Word](#word)
    - [Todo](#todo)
- [how to Install](#install)
- [How to](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/web/how-to.html)
    - [play](#play)
    - [setup](#setup)
        - [Boot channel setup](#boot)
        - [Vote channel setup](#votes)
- [Features](#features)
    - [Game](#game)
    - [Commands](#commands)
- [BRDB version](#versions)
- [Permissions and usage](#permissions)
- [Links](#links)
- [Credits](#credits)

# BRDB
This is the official Buckshot Roulette Discord Bot repo of Raven's bot

## WORD
if you encounter any bugs, errors or anything else, then make sure to report it.

I might need to join the server to identify the error and fix it.

# TODO
- [ ] Dealer adrenaline action
- [ ] change save files from user specific to user and channel specific save
- [ ] 24/7 hosting

# [HOW-TO](#overview)
``How-to`` Informations are here. 

## [PLAY](#overview)
``How-to-play``

1. go into the designated channel/thread/forum or create a new private thread.

[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)
](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)

2. type ``/buckshot_roulette player start``.

[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)


3. play by using the modal menu or buttons under the embed messages.

[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)

4. get current game info (charges, inv, loaded shells) via ``/buckshot_roulette player info``.

[![image](https://img.shields.io/badge/Image%20status-pending-ff0000?style=for-the-badge)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)


## [SETUP](#overview)
you get how-to-setup infos here.

### [Boot](#overview)
How to setup the booting message channel for the bot.

You get messages, when the bot goes online.

1. type ``/buckshot_roulette setup booting_message select_channel:[any channel]``

[![boot1](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/web/images/boot1.png)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)


2. wait for the bot to send himself a verification message.

[![boot2](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/web/images/boot2.png)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)


3. Setup is done. You now receive booting messages from the bot, when its online.

[![boo3](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/web/images/boot3.png)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)

### [Votes](#overview)
How to setup the vote message channel for the bot.

you can vote for upcomming updates or changes.

1. type ``/buckshot_roulette setup vote_channel select_channel:[any channel]``

[![vote1](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/web/images/vote1.png)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)


2. wait for the bot to send himself a verification message.

[![vote2](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/web/images/vote2.png)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)


3. Setup is done. You now receive vote messages from the bot, when there are new votes.

[![vote3](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/web/images/vote3.png)](https://raven-sgwc.github.io/Buckshot-Roulette-Discord-Bot/)


# [FEATURES](#overview)

## [GAME](#overview)
Player actions:

| Supported since Version | Action | Supported |
| --- | --- | --- |
| <0.2.x | SHOOT SELF | ✅ |
| <0.2.x | SHOOT DEALER | ✅ |
| <0.2.x | BEER | ✅ |
| <0.2.x | HANDCUFFS | ✅ |
| <0.2.x | MAGNIFYING GLASS | ✅ |
| <0.2.x | SAW | ✅ |
| <0.2.x | CIGARETTS | ✅ |
| <0.2.x | EXPIRED MEDICINE | ✅ |
| <0.2.x | BURNER PHONE | ✅ |
| <0.2.x | ADRENALINE | ✅ |
| <0.2.x | INVERTER | ✅ |

Dealer actions:

| Supported since Version | Action | Supported |
| --- | --- | --- |
| <0.4.x | SHOOT SELF | ✅ |
| <0.4.x | SHOOT PLAYER | ✅ |
| <0.4.x | BEER | ✅ |
| <0.4.x | HANDCUFFS | ✅ |
| <0.4.x | MAGNIFYING GLASS | ✅ |
| <0.4.x | SAW | ✅ |
| <0.4.x | CIGARETTS | ✅ |
| <0.4.x | EXPIRED MEDICINE | ✅ |
| 0.4.8 | BURNER PHONE | ✅ |
| ❎ | ADRENALINE | ❎ |
| <0.4.x | INVERTER | ✅ |

## [COMMANDS](#overview)
> Note
> Admin commands are only avalable for the bot owner.
>

| Version | Command | Command Sup Group | Command Group | Result | 
| --- | --- | --- | --- | --- |
| 0.1.5 | buckshot_roulette | player | start | Creates a message with a modal menu to select actions and start the game in your current channel |
| 0.2.7 | buckshot_roulette | player | info | Get informations about your current game |
| 0.4.1 | buckshot_roulette | ranks | local | Get all scores in your server |
| 0.4.1 | buckshot_roulette | ranks | global | Get all scores from every server |
| 0.4.6 | buckshot_roulette | setup | booting_message | Creates a Booting webhook in a desired channel |
| 0.5.2 | buckshot_roulette | setup | vote_channel | ❎ |
| 0.5.2 | buckshot_roulette | admin | vote | Nothing/.deferUptade() |
| 0.5.2 | buckshot_roulette | admin | get_vote | Nothing/.deferUptade() |

# [VERSIONS](#overview)

| Version | Feature |
| --- | --- |
| 0.5.4 | Fixed a bug, that could cause the dealer to always shoot live at you, when the gun is loaded blank after userd burner phone on that round |
| 0.5.3 | changed booting message conf. and bug fix |
| 0.5.2 | Added 1 new setup command |
| <0.5.1 | Basically everything else (didn't noted all changes) |

# [PERMISSIONS](#overview)
> Important
> Required permissions are subject to change
>

> Warning
> Make sure the bot has the requred permissions or it will not work correctly.
> 

| Permission | Default | Required | Usage |
| --- | --- | --- | --- |
| Add Reactions | ✅ | ❎ | Nothing yet, but planned in the future |
| Administrator | ❎ | ❎ | ❎ |
| Attach Files | ✅ | ✅ | requred for the game embed to work properly |
| Ban Members | ❎ | ❎ | ❎ |
| Change Nickname | ✅ | ❎ | no usage yet |
| Connect | ❎ | ❎ | ❎ |
| Create Events | ✅ | ❎ | creating events for votes |
| Create Expressions | ❎ | ❎ | ❎ |
| Create Instant Invite | ✅ | ✅ | required to give quick and helpfull support and bug fixes |
| Create Polls | ✅ | ✅ | for feature and other votes required |
| Create Private Threads | ❎ | ❎ | ❎ |
| Create Public Threads | ❎ | ❎ | ❎ |
| Deafen Members | ❎ | ❎ | ❎ |
| Embed Links | ✅ | ✅ | required forthe game embed to work properly |
| Kick Members | ❎ | ❎ | ❎ |
| Manage Channels | ❎ | ❎ | ❎ |
| Manage Events | ✅ | ✅ | required to make changes in poll events |
| Manage Expressions | ❎ | ❎ | ❎ |
| Manage Messages | ❎ | ❎ | ❎ |
| Manage Nicknames | ❎ | ❎ | ❎ |
| Manage Roles | ❎ | ❎ | ❎ |
| Manage Server | ❎ | ❎ | ❎ |
| Manage Threads | ❎ | ❎ | ❎ |
| Manage Webhooks | ✅ | ✅ | required to create a booting webhook |
| Mention Everyone | ✅ | ❎ | used for @here pings for booting messages and polls |
| Moderate Members | ❎ | ❎ | ❎ |
| Move Members | ❎ | ❎ | ❎ |
| Mute Members | ❎ | ❎ | ❎ |
| Priority Speaker | ❎ | ❎ | ❎ |
| Read Message History | ✅ | ❎ | required for remote support (WIP) |
| Read Messages/View Channels | ✅ | ✅ | required for the bot to register booting webhook and game embeds |
| Request To Speak | ❎ | ❎ | ❎ |
| Send Messages | ✅ | ✅ | required for the game embeds and everything else |
| Send Messages in Threads | ✅ | ✅ | required if bot is used in a thread or forum |
| Send TTS Messages | ❎ | ❎ | ❎ |
| Speak | ❎ | ❎ | ❎ |
| Use Embedded Activities | ✅ | ✅ | embed working stuff |
| Use External Emojis | ✅ | ✅ | Bot uses emojis from other servers to work properly |
| Use External Sounds | ❎ | ❎ | ❎ |
| Use External Stickers | ❎ | ❎ | ❎ |
| Use Slash Commands | ✅ | ✅ | required for the bot to work in general |
| Use Soundboard | ❎ | ❎ | ❎ |
| Use Voice Activity | ❎ | ❎ | ❎ |
| Video | ❎ | ❎ | ❎ |
| View Audit Log | ❎ | ❎ | ❎ |
| View Creator Monetization Insights | ❎ | ❎ | ❎ |
| View Server Insights | ❎ | ❎ | ❎ |

# [LINKS](#overview)
[Main server:](https://Discord.gg/9Nu2KNWSwn)
```
https://Discord.gg/9Nu2KNWSwn
```

[Bot invite link:](https://discord.com/oauth2/authorize?client_id=1228396964970889286)
```
https://discord.com/oauth2/authorize?client_id=1228396964970889286
```
# [CREDITS](#overview)
Friend and Support during developement
- Waulesi

Beta 0.4.x testers
- Luke
- Lyna
- Char Aznable
- antlerswitch
- ANONYMOUS
- ANOMYMOUS
- ANONYMOUS
