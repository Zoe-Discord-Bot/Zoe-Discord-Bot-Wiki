---
title: /add account  - Command
description: Information about the /add account command
published: true
date: 2025-02-10T19:38:01.719Z
tags: command, account, add
editor: markdown
dateCreated: 2024-04-22T16:00:47.644Z
---

# /add account @DiscordUser region gamename tag
## Information
**This command is used to connect another/secondary League of Legends account with a [player](/en/terms/player) in Discord. Just simply specify the `Discord user`, [`region`](/en/terms/region), [`gamename and tag (Riot ID)`](/en/terms/riotid) in the syntax to add the account. You can mix any region.**
<br>

### Permissions needed:
>**Manage channels** - only users with this permission ("moderators"/"administrators") can use this command as it affects Zoe for the server more deeply {.is-warning}

<br>

## Usage
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/add account</span>
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
| `user` | :heavy_check_mark: | The Discord mention of the [player](/en/terms/player) you want to add an account to |
| `region` | :heavy_check_mark: | The [regiontag](/en/terms/region) of the [region](/en/terms/region) the account is in |
| `game-name` | :heavy_check_mark: | The first part of the accounts [Riot ID](/en/terms/riotid) |
| `tag` | :heavy_check_mark: | The second part of the accounts [Riot ID](/en/terms/riotid) |
<br>

## Related commands/pages:
- [/create player](/en/commands/player/create)
{.links-list}