---
title: How to setup Zoe for a League of Legends community Discord server?
description: This is a suggestion on how to set up a League of Legends community Discord server.
published: false
date: 2023-05-17T14:01:05.882Z
tags: community, server, community server, guide
editor: markdown
dateCreated: 2023-05-17T12:49:04.078Z
---

>**You want to use Zoe on a community Discord server?** 
We are talking about a server that is not just a team or a group of friends. Here you can find a "template" on how to set up Zoe for this use.
The (current) _starting state_ should be that you have **invited Zoe** and have done the first two steps: **set the language and the default region** (see [Zoe Setup](/en/setup)).

> ### :one: **Discord channels** <br>
>If you haven't already, create a Discord channel for bot commands that only your server staff (moderators, administrators, etc.) can see for commands like /config and one command channel for everyone for them to register or using commands like /stats profile. They can look like this for example: 
><img src="" width="45%" /> <br>
>If you want to use leaderboards (which will be created in the next step) please create a dedicated channel for all leaderboards. We recommand making this a read-only channel, so only Zoe can send messages in the channel.
>{.is-info}

> ### :two: **Zoe features** <br>
>In your staff command channel you can now go ahead and create an infochannel for a general overview over all players. You can do this with the command /create infochannel. After you are done it should look something like this:
><img src="" width="35%" /> <br>
>Next would be a channel to log played matches. You can now choose between the rankchannel if you would like to focus on players ranks and won/lost LP and the matchhistorychannel if you would like to focus on a more general matchhistory with detailed statistics.
>For the rankchannel use the command /create rankchannel and for the matchhistorychannel /create matchhistorychannel
>
>Next up are leaderboards. You can pick from various goals but here are some recommendations: Solo/Duo rank, OTP (most mastery points on one champion) or total mastery points. You can create leaderboards with the command /create leaderboard. Choose the earlier created channel in channel selection.
WARN: We recommand making all of these read-only channels, so only Zoe can send messages in the channel.
If youre finished it could look like this:
><img src="" width="35%" /> 
>{.is-info}

> ### :three: **Zoe configuration** <br>
><img src="" width="35%" /> <br>
>{.is-info}

> ### :four: **Final words**
>{.is-info}

>Please note that not all of Zoes features are listed here. Feel free to check out all the other [features](/en/features), [commands](/en/commands/) and [Zoes configuration](/en/Zoe-Configuration).
>{.is-warning}