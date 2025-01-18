---
title: /clash analysis - Command
description: Information about the /clash analysis command
published: true
date: 2025-01-18T22:46:34.783Z
tags: command, clash, analysis
editor: markdown
dateCreated: 2024-04-23T07:38:57.405Z
---

# /clash analysis region gamename tag
## Information
**This command only works if the specified user is in a full clash team. Only then Zoe sends an analysis of the team. If this command is sent within a [clashchannel](/en/features/clashchannel), the [region](/en/terms/region) is not mandatory.
Zoe gives you information about 3 possible picks, a flexpick and probable bans against your team.
If you want to analyse an opposing team, you need a [gamename and tag (Riot ID)](/en/terms/riotid) of a player of the opposing team.**
<br>

### Permissions needed:
>**None** - every user on a server can use this command (as long as not further restricted by permission) {.is-success}

<br>

## Usage
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="https://zoe-discord-bot.ch/img/favicon.ico" class="dcp-avatar">
        <span class="dcp-command">/clash analysis</span>
        <div class="dcp-args">
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
| `region` | :heavy_check_mark: | The [region tag](/en/terms/region) of the [region](/en/terms/region) the player is in |
| `game-name` | :heavy_check_mark: | The gamename of the player (first part of the [Riot ID](/en/terms/riotid)) |
| `tag` | :heavy_check_mark: | The tag of the player (second part of the [Riot ID](/en/terms/riotid)) |
<br>
 
## Example
![](/en_/en_clashchannel_active.png)
<br>
 
## Related commands/pages:
-   [/create clashchannel](/en/commands/clashchannel/create)
{.links-list}