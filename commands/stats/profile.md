---
title: /stats profile - Command
description: Information about the /stats profile command
published: true
date: 2025-01-19T01:48:57.350Z
tags: stats, stats profile, player stats, profile, riotid
editor: markdown
dateCreated: 2021-07-13T10:38:02.384Z
---

# /stats profile
## Information
**Zoe provides information about the selected profile, including the top 3 highest champions, a summary of all masteries, the last 3 games played, ranking statistics of the profile and a chart with the 6 highest mastery champions.**
<br>

### Permissions needed:
>**None** - every user on a server can use this command (as long as not further restricted by permission) {.is-success}

<br>


## Usage
<div class="discord-preview">
  For yourself
    <div class="dcp-chatbar">
        <img src="https://zoe-discord-bot.ch/img/favicon.ico" class="dcp-avatar">
        <span class="dcp-command">/stats profile</span>
        <button class="dcp-send-btn">&#10148;</button> 
    </div><br>
  		For registered players on your sever
      <div class="dcp-chatbar">
        <img src="https://zoe-discord-bot.ch/img/favicon.ico" class="dcp-avatar">
        <span class="dcp-command">/stats profile</span>
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
        <img src="https://zoe-discord-bot.ch/img/favicon.ico" class="dcp-avatar">
        <span class="dcp-command">/stats profile</span>
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
| `user` | :x: | The Discord mention of the [player](/en/terms/player) you want to show the statistics of |
| `region` | :x: | The [regiontag](/en/terms/region) of the [region](/en/terms/region) the account you want to show the statistics of |
| `game-name` | :x: | The first part of the [players](/en/terms/player) [Riot ID](/en/terms/riotid) of the account you want to show the statistics of|
| `tag` | :x: | The second part of the [players](/en/terms/player) [Riot ID](/en/terms/riotid) of the account you want to show the statistics of |
<br>

## Example
<img src="/en_/en_stats_profile.png" width="400">
 <br>
 
## Related commands/pages:
- [All stats commands](/en/commands/stats)
{.links-list}