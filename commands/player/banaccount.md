---
title: /banaccount - Command
description: Information about the /banaccount command
published: true
date: 2025-02-21T20:38:15.686Z
tags: command, remove account, banaccount, hide
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
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/banaccount</span>
        <div class="dcp-args">
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">region</span>
                <span class="dcp-arg-value">EUW</span>
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">game-name</span>
                <span class="dcp-arg-value">Star Guardian Ez</span>
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">tag</span>
                <span class="dcp-arg-value">real</span>
            </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Arguments
| Argument | Required | Description |
|----------|----------|-------------|
| `region` | :heavy_check_mark: | The [regiontag](/en/terms/region) of the [region](/en/terms/region) the player is in |
| `game-name` | :heavy_check_mark: | The first part of the [players](/en/terms/player) [Riot ID](/en/terms/riotid) |
| `tag` | :heavy_check_mark: | The second part of the [players](/en/terms/player) [Riot ID](/en/terms/riotid) |
<br>

###### :two: Verification prompt
After that you will see the verification message with an summoner icon which you must set for the account specified before.
![](/img/commands/verification_promt.png)
<br>

###### :three: Open the game client
Open the League of Legends client and log in if necessary. Click on your profile and summoner icon to change it.
![](/img/commands/client_profile.png)
<br>

###### :four: Select the icon
Scroll down to the bottom of the icons list, choose the one shown in the embed and exit the icon selection to save your icon.
![](/img/commands/client_icons.png)
<br>

###### :five: Confirm verification
After the icon is changed click on `Done` to verify your ownership of the account. The next message contains a list with all server in which your account is added. With the corresponding servername if youre a member, else with the servers ID.
![](/img/commands/banaccount_servers.png)
<br>

###### :six: Proceed further
You can now do the following things: <br>

## Commands {.tabset}
### Remove account from one server
Example:
<div class="discord-preview">
    <div class="dcp-chatbar">
                <span class="dcp-mention">@Zoe</span>&nbsp;kick 3
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

>**Removes your account** from the corresponding sever (here ID 3).{.is-success} 

>**Doesn't restrict** users from **adding** your account again.{.is-danger}

### Remove account from all servers
Example:
<div class="discord-preview">
    <div class="dcp-chatbar">
                <span class="dcp-mention">@Zoe</span>&nbsp;kick all
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

>**Removes your account** from all servers.{.is-success} 

>**Doesn't restrict** users from **adding** your account again.{.is-danger}

### Restrict adding of the account
Example:
<div class="discord-preview">
    <div class="dcp-chatbar">
                <span class="dcp-mention">@Zoe</span>&nbsp;ban
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

>**Restricts** everyone from **adding** your account to any server.{.is-success} 

>Your account **isn't removed from any server** its currently on.{.is-danger}

## How to completely remove your account
So if you want to completely remove your account from Zoe:
- [x] Use `@Zoe ban` - To no longer allow adding the account on Zoe 
- [x] Use `@Zoe kick all` - To remove it from all servers it is currently added to