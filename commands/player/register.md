---
title: /register- Command
description: Information about the /register command
published: true
date: 2025-02-10T19:37:22.068Z
tags: command, register
editor: markdown
dateCreated: 2024-04-26T11:24:14.774Z
---

# /register region gamename tag
## Information
**With this command, [players](/en/terms/player) can add themselves to Zoe. To do this, they must specify the [`region`](/en/terms/region), [`gametag and tag (Riot ID)`](/en/terms/riotid). This only works if [the option is activated in the configuration](/en/Zoe-Configuration/Usermanagment/Register) ([`/config`](/en/commands/administrative/config)).**
<br>

### Permissions needed:
>**None** - every user on a server can use this command (as long as not further restricted by permission) {.is-success}

>**Configuration** - in order for this command to be used, it must be enabled in the configuration beforehand {.is-info}

<br>

## Usage
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/register</span>
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
| `region` | :heavy_check_mark: | The  [regiontag](/en/terms/region) of the [region](/en/terms/region) the player is in |
| `game-name` | :heavy_check_mark: | The first part of the players [Riot ID](/en/terms/riotid) |
| `tag` | :heavy_check_mark: | The second part of the players [Riot ID](/en/terms/riotid) |
<br>
 
## Related commands/pages:
-   [/create player](/en/commands/player/create)
-   [Player](/en/terms/player)
{.links-list}