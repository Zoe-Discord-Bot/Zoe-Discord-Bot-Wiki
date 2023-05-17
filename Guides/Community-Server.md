---
title: How to setup Zoe for a League of Legends community Discord server?
description: This is a suggestion on how to set up a League of Legends community Discord server.
published: false
date: 2023-05-17T16:45:25.035Z
tags: community, server, community server, guide
editor: markdown
dateCreated: 2023-05-17T12:49:04.078Z
---

>**You want to use Zoe on a community Discord server?** 
We are talking about a server that is not just a team or a group of friends. Here you can find a "template" on how to set up Zoe for this use.
The (current) _starting state_ should be that you have **invited Zoe** and have done the first two steps: **set the language and the default region** (see [Zoe Setup](/en/setup)). 
:one::two::three::four::five::six::seven::eight::nine:
<br>

## **1. Discord channels** <br>
> :one:If you haven't already, create a Discord channel for bot commands that only your server staff (moderators, administrators, etc.) can see for commands like `/config`, and a command channel for everyone to register or use commands like `/stats profile`. They can look like this for example: 
><img src="" width="45%" /> <br>
> :two:If you want to use leaderboards (which will be created in the next step), please create a separate channel for all leaderboards. We recommand making this a read-only channel, so only Zoe can send messages in the channel.
>{.is-info}

<br>

## **2. Zoe features** <br>
>:one:In your command channel you can now create an [infochannel](/en/features/infoChannel) to get a general overview of all players. You can do this with the command `/create infochannel`. Afterwards it should look something like this:
><img src="" width="35%" /> <br>
> :two:Next is a channel for logging the matches played. You can now choose between the [rankchannel](/en/features/rankChannel), if you want to **focus on players' ranks and LP won/lost,** and the [matchhistorychannel](/en/features/matchhistoryChannel), if you want to **focus on a general match history with detailed statistics.**
>For the [rankchannel](/en/features/rankChannel) use the command `/create rankchannel` and for the [matchhistorychannel](/en/features/matchhistoryChannel) use `/create matchhistorychannel`. <br>
> :three:Next come the [leaderboards](/en/features/leaderboards). You can choose from different goals, but here are some recommendations: Solo/duo rank, OTP (most champion mastery points) or total mastery points. You can create [leaderboards](/en/features/leaderboards) with the command `/create leaderboard`. Select the previously created channel in the channel selection.
>>We recommend making all these channels **read-only** (for others), that only Zoe can send messages into them.{.is-warning}
>
>When you are done, it might look like this:
><img src="" width="35%" /> 
> :four: Let's move on to the [rankroles](/en/features/rankroles).  These are Discord roles for each player based on the rank of the connected League of Legends account and are updated regularly by Zoe. You can customise the name, color and permissions of these roles after they have been created. For that you need to head into the configuration. [Click here for intructions.](/en/features/rankroles)
>{.is-info}

<br>

## **3. Zoe configuration** <br>
>**You can/should activate the following options in the cofiguration ([`/config`](https://wiki.zoe-discord-bot.ch/en/commands/important/config)).** 
:one:In order for all members to have to register themselves on your server in Zoe, you must activate the command beforehand. You can find instructions on how to do this here: [Enable register command](https://wiki.zoe-discord-bot.ch/en/Zoe-Configuration/Usermanagment/Register) <br>
> :two:If you want to make sure that members only add accounts to Zoe that they own, you can turn on owner verification. See the instructions here: [Account owner verification](/en/Zoe-Configuration/Usermanagment/Verification) <br>
> :three:Optionally, you can set that only members who have registered can view the infochannel. To do that, have a look here: [Hide infochannel](/en/Zoe-Configuration/Infochannel/Hide-Infochannel)
>{.is-info}

<br>

## **4. Final words**
>Please note that not all of Zoes features are listed here. as this is only a suggestion. Ultimately, you decide which features you use and how you use them.
>{.is-info}

> Feel free to check out all the other [features](/en/features), [commands](/en/commands/) and [Zoes configuration](/en/Zoe-Configuration).
>{.is-success}