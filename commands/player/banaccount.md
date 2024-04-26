---
title: /banaccount - Command
description: Information about the /banaccount command
published: false
date: 2024-04-26T09:55:38.897Z
tags: command, banaccount
editor: markdown
dateCreated: 2024-04-22T16:28:43.849Z
---

# /banaccount

## Information
**This command launches the banlist wizard. This allows you (an account owner) to delete their account from other servers and add it to the banlist to make it impossible for others to add, completely removing it from Zoe.**

### Permissions needed:
>**None** - every user on a server can use this command (as long as not further restricted by permission) {.is-success}

>**Account ownership** - this command requires verification of ownership of a league account (not discord-related) {.is-info}

<br>

## Usage
###### :one: Command
You start with issuing the command as seen below, just type your corresponding details for [region](/en/terms/region), [gamename and tag](/en/terms/riotid):
<img src="/en_/en_banaccount_riotid.png" width="70%" img>
<br>

###### :two: Verification prompt
After that you will see the verification message with an summoner icon which you must set for the account specified before.
<img src="/en_/en_banaccount_riotid_2.png" width="50%" img>
<br>

###### :three: Open the game client
Open the League of Legends client and log in if necessary. Click on your profile and summoner icon to change it.
<img src="/en_/en_banaccount_riotid_3.png" width="60%" img>
<br>

###### :four: Select the icon
Scroll down to the bottom of the icons list, choose the one shown in the embed and exit the icon selection to save your icon.
<img src="/en_/en_banaccount_riotid_4.png" width="60%" img>
<br>

###### :five: Confirm verification
After the icon is changed click on `Done` to verify your ownership of the account. The next message contains a list with all server in which your account is added. With the corresponding servername if youre a member, else with the servers ID.
<img src="/en_/en_ban_account_6.png" width="35%" img>
<br>

###### :six: Proceed further
You can use the following commands: <br>

## Commands {.tabset}
### `@Zoe kick server-number`
Example:
<img src="/en_/en_ban_account_7.png" width="25%" img> <br>
>**Removes your account** from the corresponding sever.{.is-success} 

>**Doesn't restrict** users from **adding** your account again.{.is-danger}

### `@Zoe kick all`
Example:
<img src="/en_/en_ban_account_8.png" width="20%" img> <br>
>**Removes your account** from all servers.{.is-success} 

>**Doesn't restrict** users from **adding** your account again.{.is-danger}

### `@Zoe ban`
Example:
<img src="/en_/en_ban_account_9.png" width="20%" img> <br>
>**Restricts** everyone from **adding** your account on any server.{.is-success} 

>Your account **isn't removed from any server** its currently on.{.is-danger}

## How to completely remove your account
So if you want to completely remove your account from Zoe use `@Zoe ban` (to no longer allow adding the account on Zoe) and `@Zoe kick all` (to remove it from all servers it is currently added to).
