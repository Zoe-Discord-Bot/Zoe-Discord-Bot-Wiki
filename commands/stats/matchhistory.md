---
title: /stats matchhistory - Command
description: Information about the /stats matchhistory command
published: true
date: 2025-02-22T00:50:41.572Z
tags: command, stats, statistics, matchhistory
editor: markdown
dateCreated: 2023-04-09T12:03:20.071Z
---

# /stats matchhistory
## Information
**The matchhistory command which will allow you to browse the match history of League of Legends accounts and view basic statistics like gamemode, champion and KDA. This feature incorporates a new experimental AI based feature that summarizes your game in one line. You can select a game to show more details about the game like CS, ranks and killparticipation.**
<br>

### Permissions needed:
>**None** - every user on a server can use this command (as long as not further restricted by permission) {.is-success}

<br>

## Usage
<div class="discord-preview">
  For yourself
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/stats matchhistory</span>
        <button class="dcp-send-btn">&#10148;</button> 
    </div><br>
  		For registered players on your sever
      <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/stats matchhistory</span>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">user</span>
                <span class="dcp-arg-value">
              	<span class="dcp-mention">@timfernix</span>
              </span>
            </div>
        </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div><br>
  			For every other account
        <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/stats matchhistory</span>
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
| `user` | :x: | The Discord mention of the [player](/en/terms/player) you want to show the matchhistory of |
| `region` | :x: | The [regiontag](/en/terms/region) of the [region](/en/terms/region) the account you want to show the statistics of |
| `game-name` | :x: | The first part of the accounts [Riot ID](/en/terms/riotid) you want to show the matchhistory of |
| `tag` | :x: | The second part of the accounts [Riot ID](/en/terms/riotid) you want to show the matchhistory of |
<br>
 
## Example
### Example of the stats matchhistory overview
![](/img/commands/stats_matchhistory_overview.png)
<br>

### Example of a stats matchhistory game 
![](/img/commands/stats_matchhistory_game.png)
<br>
 
## Related commands/pages:
- [All stats commands](/en/commands/stats)
{.links-list}