---
title: /remove account - Command
description: Information about the /remove account command
published: true
date: 2025-01-19T01:15:46.998Z
tags: command, remove account
editor: markdown
dateCreated: 2024-04-22T16:19:55.082Z
---

# /remove account @DiscordUser region gamename tag
## Information
**This command removes the named account from the mentioned [player](/en/terms/player) on your discord server. Just simply specify the [`region`](/en/terms/region), [`gamename and tag (Riot ID)`](/en/terms/riotid) in the syntax.**
<br>

### Permissions needed:
>**Manage channels** - only users with this permission ("moderators"/"administrators") can use this command as it affects Zoe for the server more deeply {.is-warning}

<br>

## Usage
![](/en_/en_remove_account_riotid.png)
<br>

## Usage
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="https://zoe-discord-bot.ch/img/favicon.ico" class="dcp-avatar">
        <span class="dcp-command">/remove account</span>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">user</span>
                <span class="dcp-arg-value">
              	<span class="dcp-mention">@timfernix</span>
              </span>
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
        </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Arguments
| Argument | Required | Description |
|----------|----------|-------------|
| `user` | :heavy_check_mark: | The Discord mention of the [player](/en/terms/player) you want to remove an account from |
| `region` | :heavy_check_mark: | The [regiontag](/en/terms/region) of the [region](/en/terms/region) the account is in |
| `game-name` | :heavy_check_mark: | The first part of the accounts [Riot ID](/en/terms/riotid) |
| `tag` | :heavy_check_mark: | The second part of the accounts [Riot ID](/en/terms/riotid) |
<br>

## Related commands/pages:
- [/add account](/en/commands/player/addaccount) 
{.links-list}