---
title: Zoe Setup
description: On this site you can learn about how to setup Zoe in your Discord Server.
published: true
date: 2025-06-09T13:02:38.163Z
tags: setup, initialise, set up
editor: markdown
dateCreated: 2021-07-05T11:16:55.742Z
---

# Zoe Setup
> Be aware that to set up Zoe you need the `Manage channels` permission on your server (if you are not the administrator anyway).
{.is-warning}

<br>

## Adding Zoe 
You can add Zoe to your server by clicking on [<kbd>Add to Discord</kbd>/<kbd>Invite Zoe</kbd>](https://zoe-discord-bot.ch) on the homepage, on sites like [top.gg](https://top.gg/de/bot/550737379460382752) or [bots.ondiscord.xyz](https://bots.ondiscord.xyz/bots/550737379460382752) and here on the Wiki in the bottom left in the menu bar.
<br>
  
## Authorizing Zoe
Now you may have to log in to Discord, then select the server you want to add Zoe to and confirm Zoe's permissions. You may have to solve a captcha and then you can start.
![](/img/general/discord_setup.png)

## Setup
When Zoe is added for the first time, it sends a short message to the default channel of the server.

Then follows the first setting. You should select the language you want Zoe to speak on your server. (For more information, see [`/language`](/en/commands/administrative/language)). You can navigate with the reactions and then confirm the language you want Zoe to speak.

<div class="discord-preview">
    <div class="embed">
      <div><b>English (100%)</b></div>
       <div>Arabic (31.9%)</div>
       <div>Deutsch (100%)</div>
      <div>Español (48.3%)</div>
      <div>Français (73.4%)</div>
      <div>Italiano (96%)</div>
      <div>Polski (27.6%)</div>
      <div>Português/BR (42.8%)</div>
      <div>Русский (26.3%)</div>
      <div>Turkish (20.9%)</div>
    </div>
    <div class="reactions">
        <div class="reaction">🔼 1</div>
        <div class="reaction">✅ 1</div>
        <div class="reaction">❎ 1</div>
        <div class="reaction">🔽 1</div>
    </div>
</div>
<br>

Directly after that, you have to select the standard [League of Legends server region](/en/terms/region) (which you can find here if you need help: [Regions](/en/terms/region)).

> Don't worry, you can always choose any region you want. Setting the default region will not lock any other regions.
>{.is-warning}

> You can change this setting later in the configuration if you wish (see [`/config`](/en/commands/administrative/config)).
>{.is-info}
 
<div class="discord-preview">
    <div class="embed">
        <div><b>Region EUW</b></div>
        <div>Region EUNE</div>
        <div>Region BR</div>
      	<div>Region JP</div>
      	<div>Region KR</div>
      	<div>Region LAN</div>
      	<div>Region LAS</div>
      	<div>Region NA</div>
      	<div>Region OCE</div>
      	<div>Region TR</div>
				<div>Region RU</div>
				<div>Region SEA</div>
				<div>Region VN</div>
				<div>Region TW</div>
				<div>Region ME</div>
				<div>Region Any (disabled)</div>      
    </div>
    <div class="reactions">
        <div class="reaction">🔼 1</div>
        <div class="reaction">✅ 1</div>
        <div class="reaction">❎ 1</div>
        <div class="reaction">🔽 1</div>
    </div>
</div>
<br>

Now Zoe sends another message about what you can do next. Read more in the next section.

**You can now _follow this page_ (recommended) if you are not sure what you want and want to get an overview or continue with the [guide for a server with friends or for a team](/en/Guides/Team-Server) or the [guide for a  community server](/en/Guides/Community-Server) to see differentiated lists.**
  
<br>

# 1\. Adding data (aka registering [players](/en/terms/player))
To use Zoe, you must first [register](/en/commands/player/register)/[create](/en/commands/player/create) [players](/en/terms/player). A [player](/en/terms/player) consists of a Discord account and one or more League of Legends accounts and will be displayed in the various [features](/en/features) you will use.

**There are two ways of doing so:**
1.  You can create them with the commands [`/create player`](/en/commands/player/create) (allows you to create a discord account with a League account for everyone/someone else)
2.  Also, you can enable the option in the [configuration](/en/Zoe-Configuration) that any Discord user on your server can use the [`/register`](/en/commands/player/register) command to connect their own account (See more under [`/register`](/en/commands/player/register) and [`/config`](/en/commands/administrative/config)).
- [`/add account`](/en/commands/player/addaccount) allows you to add a League of Legends account to an already registered/created [player](/en/terms/player).
- To delete a [player](/en/terms/player), use the commands [`/delete player`](/en/commands/player/delete) (delete the player) and [`/remove account`](/en/commands/player/removeaccount) (delete a player's League account).

> You can display all registered [players](/en/terms/player) with the [`/show players`](/en/commands/player/show-players) command if you wish.
>{.is-info}

<br>

# 2\. Show players (aka use [features](/en/features))
>You don't have to set up any of these [features](/en/features), this is just a suggestion-list. If you want to look around all features, [here is a link to all the features](/en/features) and [here to all commands](/en/commands/).
>{.is-info}
  
<br>

## Infochannel (read-only channel recommended)
The [infochannel](/en/features/infochannel) contains stats on [players](/en/terms/player) as well as stats on games currently in progress.

![](/img/features/infopanel.jpg)
![](/img/features/gamecard.png)

- [Infochannel *For more information about the infochannel click here.*](/en/features/infochannel)
{.links-list}

<br>
  
## Rankchannel (read-only channel recommended)
The [rankchannel](/en/features/rankchannel) is, where a message will be sent after each ranked game of a [registered players](/en/terms/player). These messages contain the amount of won or lost LP and some stats on the [players](/en/terms/player) ingame performance like KDA, duration of the game and itembuild.

![](/img/features/rankchannel_msg.png)

- [Rankchannel *For more information about the rankchannel click here.*](/en/features/rankchannel)
{.links-list}
  
<br>
  
## Clashchannel
This channel will send stats about an account in relation to clash. It will contain schedules of future clashes in your timezone as well as stats about your team. You will also be able to do an detailed analysis of enemy teams with ban recommendations.

![](/img/commands/stats_teamanalysis_picks.png)

- [Clashchannel *For more information about the clashchannel click here.*](/en/features/clashchannel)
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
- 	Betting points

![](/img/features/leaderboard_championmastery.png)

- [Leaderboards *For more information about leaderboards click here.*](/en/features/leaderboards)
{.links-list}

<br>
  
## Automated Discord roles by League rank
You can set up an automatic rank system with Zoe easily. The roles will be refreshed regularly automatically. The premium version of this feature offers more options (filter by server region, display of each division, full control over each role and more).

![](/img/features/rankroles.jpg)

- [Rankroles *For more information about rankroles click here.*](/en/features/rankroles)
{.links-list}
  
<br>
  
Once your features are set up correctly, they will update automatically as soon as a game is detected via the Discord presence of [registered players](/en/terms/player) or once an hour at least. You can also refresh your server with the command [`/refresh`](/en/commands/basic/refresh).
 
<br>
  
# 3\. Customize these features (because every server is different)
To manage Zoe and all the different settings it offers, use this command: [`/config`](/en/commands/administrative/config). 
 Read everything about the configuration here: [**Configuration**](/en/Zoe-Configuration/).

<br>
  
# 4\. Going further (We never stop!)
Zoe has many more features. You can have a look at all commands if you click [HERE](/en/commands).
One example being [`/stats profile`](/en/commands/stats/profile) letting you view a players profile:

![](/img/commands/stats_profile.png)
<br>
  
# Setup - Final words
Zoe is an actively developed bot that offers a [<kbd>⭐ premium subscription ⭐</kbd>](/en/support) to support its development. This subscription offers some additional options but is by far not mandatory. 
For more information: [Support us](/en/support), [Boosting](/en/Zoe-Points-And-Boosting), [`/subscription`](/en/commands/subscription/subscription) and [`/boost`](/en/commands/subscription/boost) 

- [Commands *If you want to see the list of commands: `/help` or click here.*](/en/commands)
- [Discord Server *If you have any questions, suggestions or need help, please come here*](https://discord.gg/whc5PrC)
- [Setup *To review the setup help message, use `/setup`*](/en/commands/administrative/setup)
{.links-list}