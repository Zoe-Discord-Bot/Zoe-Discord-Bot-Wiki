---
title: /banaccount - Command
description: Information about the /banaccount command
published: false
date: 2024-04-22T16:37:10.507Z
tags: command, banaccount
editor: markdown
dateCreated: 2024-04-22T16:28:43.849Z
---

# /banaccount

## Information
**Launches the banlist wizard. This allows you (an account owner) to delete their account from other servers and add it to the banlist to make it impossible for others to add.**

### Permissions needed:
>**None** - every user on a server can use this command (as long as not further restricted by permission) {.is-success}

>**Account ownership** - this command requires verification of ownership of a league account (not discord-related) {.is-info}

<br>

## Usage
:one: You start with issuing the command as seen below, just type your corresponding details for [region](/en/terms/region), [gamename and tag](/en/terms/riotid):
<img src="/en_/en_banaccount_riotid.png" width="70%" img>

:two: After that you will see the verification message with an summonericon which you must set for the account specified before.
<img src="/en_/en_banaccount_riotid_2.png" width="50%" img>

:three: Open the League of Legends client and log in if necessary. Click on your profile and summonericon to change it.
<img src="/en_/en_banaccount_riotid_3.png" width="60%" img>

:four: Scroll down to the bottom of the icons list, choose the one from the embeds and exit the icon selection to save your icon.
<img src="/en_/en_banaccount_riotid_4.png" width="60%" img>

:five: After the verification click on `Done`. The next message contains a list with all server in which your account is added. With a name if youre a member, else with the serverID.
<img src="/en_/en_ban_account_6.png" width="35%" img>

:six:__You can use the following commands:__ <br>
## Commands {.tabset}
### `@Zoe kick server-number`
>Deletes your player from the server with the corresponding number.
<img src="/en_/en_ban_account_7.png" width="25%" img> <br>
### `@Zoe kick all`
>Deletes your player from all servers at once.
<img src="/en_/en_ban_account_8.png" width="20%" img> <br>
### `@Zoe ban`
Restricts everyone from adding your account, but its not deleted from any server.
<img src="/en_/en_ban_account_9.png" width="20%" img> <br>

## How to completely remove your account
So if you want to completely remove your account from Zoe use `@Zoe ban` (to no longer allow adding the account on Zoe) and `@Zoe kick all` (to remove it from all servers it is currently added to).
