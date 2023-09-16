---
title: Zoe Setup
description: On this site you can learn about how to setup Zoe in your Discord Server.
published: true
date: 2023-09-16T07:19:06.893Z
tags: setup, initialise, set up
editor: markdown
dateCreated: 2021-07-05T11:16:55.742Z
---

# Zoe Discord Bot Setup

<br>

> Be aware that to set up and use Zoe you need the `Manage channels` permission on your server (if you are not the administrator anyway).
{.is-warning}

<br>

## Adding Zoe 

You can add Zoe to your server by clicking on [`Add the bot`](https://zoe-discord-bot.ch/invite.html) on the homepage, on sites like [top.gg](https://top.gg/de/bot/550737379460382752) or [bots.ondiscord.xyz](https://bots.ondiscord.xyz/bots/550737379460382752) and here on the Wiki in the bottom left in the menu bar.

<br>
  
## Authorizing Zoe

Now you may have to log in to Discord, then select the server you want to add Zoe to and confirm Zoe's permissions. You may have to solve a captcha and then you can start.

![](/en_/en_add_zoe_full.png)

## Setup

When Zoe is added for the first time, it sends a short message to the default channel of the server.

Then follows the first setting. You should select the language you want Zoe to speak on your server. (For more information, see [`/language`](/en/commands/important/language)). You can navigate with the reactions and then confirm the language you want Zoe to speak.

![](/en_/en_setup_language.png)

Directly after that, you have to select the standard [League of Legends server region](/en/terms/region). Available are the following tags:

| Tag | BR  | EUNE | EUW | LAN | LAS | NA  | OCE | RU  | TR  | JP  | KR  | PH  | SG  | TW  | TH  | VN  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Region | Brazil | Europe Nordic & East | Europe West | Latin America North | Latin America South | North America | Oceania | Russia | Turkey | Japan | Republic of Korea | The Philippines | Singapore, Malaysia & Indonesia | Taiwan, Hong Kong & Macao | Thailand | Vietnam |

> Don't worry, you can always choose any region you want. Setting the default region will not lock any other regions.
>{.is-warning}

> You can change this setting later in the configuration if you wish (see [`/config`](/en/commands/important/config)).
>{.is-info}
  
![](/en_/en_setup_region.png) 
> Now Zoe sends another message about what you can do next. Read more in the next section.
>{.is-info}

> **You can now _follow this page_ (recommended) if you are not sure what you want and want to get an overview or continue with the [guide for a server with friends or for a team](https://wiki.zoe-discord-bot.ch/en/Guides/Team-Server) or the [guide for a  community server](https://wiki.zoe-discord-bot.ch/en/Guides/Community-Server) to see differentiated lists.**
  
<br>

# 1\. Adding data (aka registering [players](/en/terms/player))

To use Zoe, you must first [register](/en/commands/important/register)/[create](/en/commands/create/player) [players](/en/terms/player). A [player](/en/terms/player) consists of a Discord account and one or more League of Legends accounts and will be displayed in the various [features](/en/features) you will use.

**There are two ways of doing so:**

1.  You can create them with the commands [`/create player`](/en/commands/create/player) (allows you to create a discord account with a League account for everyone/someone else)
2.  Also, you can enable the option in the [configuration](/en/Zoe-Configuration) that any Discord user on your server can use the [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) command to connect their own account (See more under [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) and [`/config`](https://wiki.zoe-discord-bot.ch/en/commands/important/config)).

[`/add account`](/en/commands/add/account) allows you to add a League of Legends account to an already registered/created [player](/en/terms/player).

To delete a [player](/en/terms/player), use the commands [`/delete player`](/en/commands/delete/player) (delete the player) and [`/remove account`](/en/commands/remove/account) (delete a player's League account).

> You can display all registered [players](/en/terms/player) with the [`/show players`](/en/commands/important/show-players) command if you wish.
>{.is-info}

<br>
  
# 2\. Show players (aka use [features](/en/features))
>You don't have to set up any of these [features](/en/features), this is just a suggestion-list. If you want to look around all features, [here is a link to all the features](/en/features) and [here to all commands](/en/commands/).
>{.is-info}
  
<br>

## Infochannel (read-only channel recommended)

The [infochannel](/en/features/infoChannel) contains stats on [players](/en/terms/player) as well as stats on games currently in progress.

![](/en_/en_infochannel.png)
![](/en_/en_gamecard.png)

- [Infochannel *For more information about the infochannel click here.*](/en/features/infoChannel)
{.links-list}

<br>
  
## Rankchannel (read-only channel recommended)

The [rankchannel](/en/features/rankChannel) is, where a message will be sent after each ranked game of a [registered players](/en/terms/player). These messages contain the amount of won or lost LP and some stats on the [players](/en/terms/player) ingame performance like KDA, duration of the game and itembuild.

![](/en_/en_rankchannel_message.png)

- [Rankchannel *For more information about the rankchannel click here.*](/en/features/rankChannel)
{.links-list}
  
<br>
  
## Clashchannel

This channel will send stats about an account in relation to clash. It will contain schedules of future clashes in your timezone as well as stats about your team. You will also be able to do an detailed analysis of enemy teams with ban recommendations.

![](/en_/en_stats_teamanalysis_picks.png)

- [Clashchannel *For more information about the clashchannel click here.*](/en/features/clashChannel)
{.links-list}

<br>
  
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

![](/en_/en_leaderboard_championmasterypoints.png)

- [Leaderboards *For more information about leaderboards click here.*](/en/features/leaderboards)
{.links-list}

<br>
  
## Automated Discord roles by League rank

You can set up an automatic rank system with Zoe easily. The roles will be refreshed regularly automatically. The premium version of this feature offers more options (filter by server region, display of each division, full control over each role and more).

![](/improved_rankroles_5.png)

- [Rankroles *For more information about rankroles click here.*](/en/features/rankroles)
{.links-list}
  
<br>
  
Once your features are set up correctly, they will update automatically as soon as a game is detected via the Discord presence of [registered players](/en/terms/player) or once an hour at least. You can also refresh your server with the command [`/refresh`](/en/commands/important/refresh).
 
<br>
  
# 3\. Customize these features (because every server is different)

> To manage Zoe and all the different settings it offers, use this command: [`/config`](/en/commands/important/config). 
 Read everything about the configuration here: [**Configuration**](/en/Zoe-Configuration/).
>{.is-info}

<br>
  
# 4\. Going further (We never stop!)

Zoe has many more features. You can have a look at all commands if you click [HERE](http://wiki.zoe-discord-bot.ch/en/commands).

One example being [`/stats profile`](/en/commands/stats/profile) letting you view a players profile:

![](/en_/en_stats_profile.png)

<br>
  
# Setup - Final words

> Zoe is an actively developed bot that offers a ⭐[premium subscription](/en/support)⭐ to support its development. This subscription offers some additional options but is by far not mandatory. 
For more information: [Subscription Wiki page](https://wiki.zoe-discord-bot.ch/en/support), [Boosting](https://wiki.zoe-discord-bot.ch/en/Zoe-Points-And-Boosting), [`/subscription`](/en/commands/important/subscription) and [`/boost`](/en/commands/important/boost)  
- [Commands *If you want to see the list of commands: `/help` or click here.*](/en/commands)
- [Discord Server *If you have any questions, suggestions or need help, please come here*](https://discord.gg/whc5PrC)
- [Setup *To review the setup help message, do the command: `/setup`*](/en/commands/important/setup)
{.links-list}
  