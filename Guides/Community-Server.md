---
title: How to setup Zoe for a League of Legends community Discord server?
description: This is a suggestion on how to set up a League of Legends community Discord server.
published: true
date: 2023-09-04T14:20:27.838Z
tags: community, server, community server, guide
editor: markdown
dateCreated: 2023-05-17T12:49:04.078Z
---

>**You want to use Zoe on a community Discord server?** 
We are talking about a server that is not just a team or a group of friends. Here you can find a "template" on how to set up Zoe for this use.
The (current) _starting state_ should be that you have **invited Zoe** and have done the first two steps: **set the language and the default region** (see [Zoe Setup](/en/setup)). 

<br>

## **1. Discord channels** <br>
> :one:If you haven't already, create a Discord channel for bot commands that only your server staff (moderators, administrators, etc.) can see for commands like `/config`, and a command channel for everyone to [register](/en/commands/important/register) or use commands like [`/stats profile`](/en/commands/stats/profile). They can look like this for example: 
><img src="/guide_communityserver_1.png" width="30%" /> <br>
> :two:If you want to use [leaderboards](/en/features/leaderboards) (which will be created in the next step), please create a separate channel for all [leaderboards](/en/features/leaderboards). We recommand making this a read-only channel, so only Zoe can send messages in the channel.
>{.is-info}

<br>

## **2. Zoe features** <br>
>:three:In your command channel you can now create an [infochannel](/en/features/infoChannel) to get a general overview of all [players](/en/terms/player). You can do this with the command [`/create infochannel`](/en/commands/create/infoChannel). <br>
> :four:Next is a channel for logging the matches played. You can now choose between the [rankchannel](/en/features/rankChannel), if you want to **focus on [players'](/en/terms/player) ranks and LP won/lost,** and the [matchhistorychannel](/en/features/matchhistoryChannel), if you want to **focus on a general match history with detailed statistics.**
>For the [rankchannel](/en/features/rankChannel) use the command [`/create rankchannel`](/en/commands/create/rankChannel) and for the [matchhistorychannel](/en/features/matchhistoryChannel) use [`/create matchhistorychannel`](/en/commands/create/matchhistorychannel). <br>
> :five:Next come the [leaderboards](/en/features/leaderboards). You can choose from different goals, but here are some recommendations: Solo/Duo rank, OTP (most champion mastery points) or total mastery points. You can create [leaderboards](/en/features/leaderboards) with the command [`/create leaderboard`](/en/commands/create/leaderboard). Select the previously created channel in the channel selection.
>>We recommend making all these channels **read-only** (for others), that only Zoe can send messages into them.{.is-warning}
>
>When you are done, it might look like this:
><img src="/guide_communityserver_2.png" width="30%" /> 
> :six: Let's move on to the [rankroles](/en/features/rankroles).  These are Discord roles for each [player](/en/terms/player) based on the rank of the connected League of Legends account and are updated regularly by Zoe. You can customise the name, color and permissions of these roles after they have been created. For that you need to head into the configuration. [Click here for intructions.](/en/features/rankroles)
>{.is-info}

<br>

## **3. Zoe configuration** <br>
>**You can/should activate the following options in the cofiguration ([`/config`](https://wiki.zoe-discord-bot.ch/en/commands/important/config)).**  <br>
:seven:In order for all members to have to register themselves on your server in Zoe, you must activate the command beforehand. You can find instructions on how to do this here: [Enable register command](https://wiki.zoe-discord-bot.ch/en/Zoe-Configuration/Usermanagment/Register) <br>
> :eight:If you want to make sure that members only add accounts to Zoe that they own, you can turn on owner verification. See the instructions here: [Account owner verification](/en/Zoe-Configuration/Usermanagment/Verification) <br>
> :nine:Optionally, you can set that only members who have registered can view the infochannel. To do that, have a look here: [Hide infochannel](/en/Zoe-Configuration/Infochannel/Hide-Infochannel)
>{.is-info}

<br>

## **4. Final words**
>Please note that not all of Zoes features are listed here. as this is only a list of suggestions. Ultimately, you decide which features you use and how you use them.
>{.is-info}

> Feel free to check out all the other [features](/en/features), [commands](/en/commands/) and [Zoes configuration](/en/Zoe-Configuration).
>{.is-success}