---
title: /add playertoteam - Command
description: Information about the /add playertoteam command
published: true
date: 2025-02-10T19:38:40.299Z
tags: command, add player to team
editor: markdown
dateCreated: 2024-04-22T17:21:20.687Z
---

# /add playertoteam @DiscordUser team-name
## Information
**This command adds the mentioned [player](/en/terms/player) to the named team. For this, it must first be [created](/en/commands/team/create) and an [infopanel](/en/features/infochannel) must exist on your server.**
<br>

### Permissions needed:
>**Manage channels** - only users with this permission ("moderators"/"administrators") can use this command as it affects Zoe for the server more deeply {.is-warning}

<br>

## Usage
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/add playertoteam</span>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">user</span>
                <span class="dcp-arg-value">
              	<span class="dcp-mention">@timfernix</span>
              </span>
            </div>
        </div>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">team-name</span>
                <span class="dcp-arg-value">Zoe Staff</span>
            </div>
        </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Arguments
| Argument | Required | Description |
|----------|----------|-------------|
| `user` | :heavy_check_mark: | Mention the player you want to add to a team |
| `team-name` | :heavy_check_mark: | Choose the name of the team you want to add the player to |
<br>
 
## Related commands/pages:
-   [/create team](/en/commands/team/create)
-   [/create infochannel](/en/commands/infochannel/create)
{.links-list}