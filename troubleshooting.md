---
title: Zoe Troubleshooting
description: With this guide you can try to solve minor issues yourself.
published: false
date: 2023-05-07T10:48:59.476Z
tags: help, troubleshooting, quickhelp, problem solving, online status, permissions
editor: markdown
dateCreated: 2023-05-07T09:24:15.617Z
---

# Troubleshooting

> *Zoe is not responding to my commands/not updating the infoboard or leaderboard/not sending gamecards,  rankchannel/matchhistorychannel-messages. What's wrong with it?*
> **Here is what you can check now!**

<br>

## 1. Check Discord status
> First, check Zoe's Discord status. If it is not green (online) but red (do not disturb) or greyed out (offline), it is most likely because an update to a newer version is in progress or we are investigating an issue.
> >🟢 **Online:** Zoe is functional
> >🔴 **Do not disturb:** Zoe is booting/shutting down
> >⚫ **Offline:** Zoe is currently offline because of an update or issue
><pr>
>
> For more information you can check out the announcement channel on our Discord server. You find an invite on the bottom left.
>{.is-info}
  
<br>

## 2. Check permissions
>Secondly, check Zoe's role to see if you have given her all the permissions it needs. You also need to check the permissions on your command channel and on the target channel (e.g. for leaderboards) to make sure there are no overwrites. <br>
> **Needed permissions are:**
>`MANAGE_CHANNELS` -  Allows management and editing of channels
>`VIEW_CHANNELS` - Allows view of a channel, which includes reading messages in text channels
>
>`MANAGE_MESSAGES` - Allows for deletion of  messages
>`SEND_MESSAGES` - Allows for sending messages in a channel
>`READ_MESSAGE_HISTORY` - Allows for reading of message history
>
>`ATTACH_FILES` - Allows for uploading images and files
>`ADD_REACTIONS` - Allows for the addition of reactions to messages
>`USE_EXTERNAL_EMOJIS` - Allows the usage of custom emojis from other servers
>`EMBED_LINKS` - Links sent by users with this permission will be auto-embedded
>
>`MANAGE_GUILD_EXPRESSIONS` - Allows management and editing of emojis
>`MANAGE_ROLES` - Allows management and editing of roles
>`USE_APPLICATION_COMMANDS` - Allows to use application commands, slash commands and context menu commands.
> > If roles dont work for you, also check that Zoe is above all other roles in the server settings.{.is-warning}
>
>{.is-info}
  
<br>

## 3. Additional information
> ### Discord presence issue
>If you are **streaming via Discord** or using a **recording/clipping program** that changes the Discord Rich Presence (like MedalTV or similar), Zoe will not be able to perceive the current game and will not send an gamecard or update the infopanel.
Please **end your stream or turn off the Discord Presence of the program** so that `Playing League of Legends` is visible, only then will you receive all the information directly, as the passive refresh takes longer.
>{.is-info}
  
> ### Slash commands issue
>If the slash comands do not work for you, first check if Zoe has the permission to `USE_APPLICATION_COMMANDS`. If Zoe has this permission but it still doesn't work, it's probably because you invited Zoe via an outdated link that didn't have the `application.commands` invite-option enabled. This must be done by the developer when inviting Zoe and is done in all new invitation links. 
To fix this, you can kick Zoe and add it again with the new and correct invitation link. 
> >Dont worry, your configuration is saved. {.is-warning} 
>
>{.is-info}
 
  <br>
  
## Still not working?
>If it still does not work, please ask your question / express your problem in a support post on the Zoe Discord server. You can find an invite on the bottom left.
>{.is-success}

