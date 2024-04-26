---
title: How to setup Zoe for a friends/team Discord server?
description: This is a suggestion on how to set up a friends/team Discord server.
published: true
date: 2024-04-26T18:14:40.796Z
tags: team, server, guide, friends, team server, friends server
editor: markdown
dateCreated: 2023-05-17T20:26:16.992Z
---

>**You want to use Zoe on a team or friends Discord server?** 
We are talking about a server that is just for a team or a group of friends. Here you can find a "template" on how to set up Zoe for this use.
The (current) _starting state_ should be that you have **invited Zoe** and have done the first two steps: **set the language and the default region** (see [Zoe Setup](/en/setup)). 

<br>

## **1. Discord channels** <br>
> :one:If you haven't already, create a Discord channel for bot commands for everyone to register and use commands like [`/stats profile`](/en/commands/stats/profile). <br>
> :two:If you want to use leaderboards (which will be created in the next step), please create a separate channel for all leaderboards. We recommand making this a read-only channel, so only Zoe can send messages in the channel.
>{.is-info}

<br>

## **2. Zoe features** <br>
>:three:In your command channel you can now create an [infochannel](/en/features/infochannel) to get a general overview of all players. You can do this with the command `/create infochannel`. <br>
> :four:Next is a channel for logging the matches played. You can now choose between the [rankchannel](/en/features/rankchannel), if you want to **focus on players' ranks and LP won/lost,** and the [matchhistorychannel](/en/features/matchhistorychannel), if you want to **focus on a general match history with detailed statistics.**
>For the [rankchannel](/en/features/rankchannel) use the command [`/create rankchannel`](/en/commands/rankchannel/create) and for the [matchhistorychannel](/en/features/matchhistorychannel) use [`/create matchhistorychannel`](/en/commands/matchhistorychannel/create). <br>
> :five:Next come the [leaderboards](/en/features/leaderboards). You can choose from different goals, but here are some recommendations: Solo/duo rank, OTP (most champion mastery points), account level or total mastery points. You can create [leaderboards](/en/features/leaderboards) with the command [`/create leaderboard`](/en/commands/leaderboard/create). Select the previously created channel in the channel selection.
>>We recommend making all these channels **read-only** (for non-"moderators"/"administrators"), that only Zoe can send messages into them.{.is-warning}
> 
> :six: Let's move on to the [rankroles](/en/features/rankroles).  These are Discord roles for each player based on the rank of the connected League of Legends account and are updated regularly by Zoe. You can customise the name, color and permissions of these roles after they have been created. For that you need to head into the configuration. [Click here for intructions.](/en/features/rankroles) <br>
> :seven: For teams and friends who play together as a team, it is worth creating a [clashchannel](/en/features/clashchannel) in which the next clash dates and a team analysis are automatically displayed when clashes take place. You can create one with [`/create clashchannel`](/en/commands/clashchannel/create).
>{.is-info}

<br>

## **3. Zoe configuration** <br>
>**You can/should activate the following options in the cofiguration ([`/config`](/en/commands/administrative/config)).**  <br>
:eight:In order for all members to have to register themselves on your server in Zoe, you must activate the command beforehand. You can find instructions on how to do this here: [Enable register command](/en/Zoe-Configuration/Usermanagment/Register) <br>
>{.is-info}

<br>

## **4. Final words**
>Please note that not all of Zoes features are listed here. as this is only a suggestion. Ultimately, you decide which features you use and how you use them.
>{.is-info}

> Feel free to check out all the other [features](/en/features), [commands](/en/commands/) and [Zoes configuration](/en/Zoe-Configuration).
>{.is-success}