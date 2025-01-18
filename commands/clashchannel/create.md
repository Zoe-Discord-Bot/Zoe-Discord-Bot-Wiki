---
title: /create clashchannel - Command
description: Information about the /create clashchannel command
published: true
date: 2025-01-18T22:40:42.354Z
tags: create, command, clashchannel
editor: markdown
dateCreated: 2024-04-23T07:29:57.900Z
---

# /create clashchannel clashchannel-name
## Information
**If you want to create a [clashchannel](/en/features/clashchannel), use this command and select a name you like for `clashchannel-name`, you still have to specify a [player](/en/terms/player) for the [clashchannel](/en/features/clashchannel) (that is in the corresponding clashteam) and select the appropriate time zone. To do this, you have to navigate through the pages or send Zoe the fitting details. The [clashchannel](/en/features/clashchannel) is now created and the next clash dates are displayed. If a clash takes place, you can start a team analysis here, for more information see [/clash analysis](/en/commands/clashchannel/analysis).**<br>

### Permissions needed:
>**Manage channels** - only users with this permission ("moderators"/"administrators") can use this command as it affects Zoe for the server more deeply {.is-warning}

<br>

## Usage
:one: Start by creating the clashchannel with:
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="https://zoe-discord-bot.ch/img/favicon.ico" class="dcp-avatar">
        <span class="dcp-command">/create clashchannel</span>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">clashchannel-name</span>
                <span class="dcp-arg-value">lol-clash</span>
            </div>
        </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Arguments
| Argument | Required | Description |
|----------|----------|-------------|
| `clashchannel-name` | :heavy_check_mark: | Choose a name for the clashchannel, for example "lol-clash" |

:two: After that you need to give Zoe an account (thats in the clashteam) by their [region](/en/terms/region), [gamename and tag](/en/terms/riotid):
<div class="discord-preview">
    <div class="dcp-chatbar">
        <span class="dcp-mention">@Zoe</span>&nbsp; (EUW) (Star Guardian Ez) (real)
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

:three: Finally give Zoe a timezone by number from a list Zoe provides:
<div class="discord-preview">
    <div class="dcp-chatbar">
        <span class="dcp-mention">@Zoe</span>&nbsp; 432
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>
<br>
 
## Example
###### Inactive clashchannel
![](/en_/en_clashchannel_inactive.png)

###### Active clashchannel
![](/en_/en_clashchannel_active.png)
<br>
 
## Related commands/pages:
-   [/clash analysis](/en/commands/clashchannel/analysis/)
{.links-list}