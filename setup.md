---
title: Zoe Setup
description: On this site you can learn about how to setup Zoe in your Discord Server.
published: true
date: 2023-05-13T20:02:52.788Z
tags: setup, initialise, set up
editor: markdown
dateCreated: 2021-07-05T11:16:55.742Z
---

# Zoe Discord Bot Setup

<p>

> Be aware that to set up and use Zoe you need the `Manage channels` permission on your server (if you are not the administrator anyway).
{.is-warning}
<p>

## Adding Zoe

You can add Zoe to your server by clicking on `Add the bot` on the homepage, on sites like [top.gg](https://top.gg/de/bot/550737379460382752) or [bots.ondiscord.xyz](https://bots.ondiscord.xyz/bots/550737379460382752) and here on the Wiki in the bottom left in the menu bar.
<p>
  
## Authorizing Zoe

Now you may have to log in to Discord, then select the server you want to add Zoe to and confirm Zoe's permissions. You may have to solve a captcha and then you can start.

![](/new_setup1-3.png)

## Setup

When Zoe is added for the first time, it sends a short message to the default channel of the server.

Then follows the first setting. You should select the language you want Zoe to speak on your server. (For more information, see [`/language`](/en/commands/important/language)). You can navigate with the reactions and then confirm the language you want Zoe to speak.

![](/new_setup5.png)

Directly after that, you have to select the standard League of Legends server region. Available are the following tags:

| Tag | BR  | EUNE | EUW | LAN | LAS | NA  | OCE | RU  | TR  | JP  | KR  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Region | Brazil | Europe Nordic & East | Europe West | Latin America North | Latin America South | North America | Oceania | Russia | Turkey | Japan | Republic of Korea |

> You can change this setting later in the configuration if you wish (see [`/config`](/en/commands/important/config)).
>{.is-info}
  
![](/new_setup4.png)

> Now Zoe sends another message about what you can do next. Read more in the next section.
<p>

# 1\. Adding data (aka registering players)

To use Zoe, you must first register/create players. A player consists of a Discord account and one or more League accounts and will be displayed in the various features you will use.

**There are two ways of doing so:**

1.  You can create them with the commands [`/create player`](/en/commands/create/player) (allows you to create a discord account with a League account for everyone/someone else)
2.  Also, you can enable the option in the configuration that any Discord user on your server can use the [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) command to connect their own account (See more under [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) and [`/config`](https://wiki.zoe-discord-bot.ch/en/commands/important/config)).

[`/add account`](/en/commands/add/account) allows you to add a League account to an already registered/created discord account.

To delete a player, use the commands [`/delete player`](/en/commands/delete/player) (delete the player) and [`/remove account`](/en/commands/remove/account) (delete a player's League account).

> You can display all registered players with the [`/show players`](/en/commands/important/show-players) command if you wish.
>{.is-info}
<p>
  
# 2\. Show players (aka use features)

## Infochannel (read-only channel recommended)

The infochannel contains stats on players as well as stats on games currently in progress.

![](/new_infopanel.png)
<img src="/new_gamecard.png" width="50%" />

> For more information about the infochannel click [HERE](/en/features/infoChannel).
  >{.is-info}
<p>
  
## Rankchannel (read-only channel recommended)

The rankchannel is, where a message will be sent after each ranked game of the registered players. These messages contain the amount of won or lost LP and some stats on the player ingame performance like KDA, duration of the game and itembuild.

![](/new_rankchannel_message.png)

> For more information about the rankchannel click [HERE](/en/features/rankChannel).
  >{.is-info}
<p>
  
## Clashchannel

This channel will send stats about an account in relation to clash. It will contain schedules of future clashes in your timezone as well as stats about your team. You will also be able to do an detailed analysis of enemy teams with ban recommendations.

![](/new_statsteamanalysis.png)

> For more information about the clashchannel click [HERE](/en/features/clashChannel).
  >{.is-info}
<p>
  
## Leaderboards (a dedicated channel with several leaderboards within is recommended)

This feature allows you to create leaderboards that refresh automatically. Several types are available to you:

-   Total Mastery Points
-   **Mastery Points on a champion**
-   Rank in a Queue (Solo/DuoQ, Flex, etc)
-   All Queue Rank
-   Average KDA
-   Average KDA on a champion
-   Best Champion ("OTP")
-   Account Level

![](/new_leaderboard_mastery_points_champion.png)

> For more information about leaderboards click [HERE](/en/features/leaderboards).
  >{.is-info}
<p>
  
## Automated Discord roles by League rank

You can set up an automatic rank system with Zoe easily. The roles will be refreshed regularly automatically. The premium version of this feature offers more options (filter by server region, display of each division, full control over each role and more).

![](/improved_rankroles_5.png)

Once your features are set up correctly, they will update automatically as soon as a game is detected via the Discord presence of registered players or once an hour at least. You can also refresh your server with the command [`/refresh`](/en/commands/important/refresh).

> For more information about rankroles click [HERE](/en/features/rankroles).
  >{.is-info}
<p>
  
# 3\. Customize these features (because every server is different)

> To manage Zoe and all the different settings it offers, use this command: [`/config`](/en/commands/important/config). 
 Read everything about the configuration here: [**Configuration**](/en/Zoe-Configuration/).
>{.is-info}
<p>
  
# 4\. Going further (We never stop!)

Zoe has many more features. You can have a look at all commands if you click [HERE](http://wiki.zoe-discord-bot.ch/en/commands).

One example being [`/stats profile`](/en/commands/stats/profile) letting you view a players profile:

![](/new_statsprofile.png)
<p>
  
# Setup - Final words

> Zoe is an actively developed bot that offers a premium subscription to support its development. This subscription offers some additional options but is by far not mandatory. For more information: [`/subscription`](/en/commands/important/subscription) [`/boost`](/en/commands/important/boost)
  

> If you want to see the list of commands: [`/help`](/en/commands/important/help) or click [HERE](/en/commands/).
> If you have any questions, suggestions or need help, please come here: [https://discord.gg/whc5PrC](https://discord.gg/whc5PrC)   
> *To review the setup help message, do the command:* [`/setup`](/en/commands/important/setup)
  >{.is-info}