---
title: /stats teamanalysis - Command
description: Information about the /stats teamanalysis command
published: true
date: 2025-02-10T19:39:35.564Z
tags: stats, analysis, team, team analysis, team stats, teamanalysis, stats teamanalysis, riotid
editor: markdown
dateCreated: 2021-07-13T11:00:45.454Z
---

# /stats teamanalysis
## Information
**When you execute this command you have to specify 5 accounts with their [Riot ID](/en/terms/riotid) and optionally add a lane so that Zoe can start an analysis. Zoe evaluates who could play what on which position (if not already defined) and the champions that could be played (or banned based versus the team) are indicated.**
<br>

### Permissions needed:
>**None** - every user on a server can use this command (as long as not further restricted by permission) {.is-success}

<br>

## Usage
*In this example only 1 out of 5 accounts is specified. In order for the command to work you need to specify 5 accounts.*
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/stats teamanalysis</span>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">account1-riot-id</span>
                <span class="dcp-arg-value">Star Guardian Ez#real</span>
            </div>
          			<div class="dcp-arg">
                <span class="dcp-arg-label">account2-riot-id</span>
                <span class="dcp-arg-value">...</span>
            </div>
        </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Arguments
| Argument | Required | Description |
|----------|----------|-------------|
| `account1-riot-id` | :heavy_check_mark: | Specify the [Riot ID](/en/terms/riotid) of the first account in the analysis |
| `account2-riot-id` | :heavy_check_mark: | Specify the [Riot ID](/en/terms/riotid) of the second account in the analysis |
| `account3-riot-id` | :heavy_check_mark: | Specify the [Riot ID](/en/terms/riotid) of the third account in the analysis |
| `account4-riot-id` | :heavy_check_mark: | Specify the [Riot ID](/en/terms/riotid) of the fourth account in the analysis |
| `account5-riot-id` | :heavy_check_mark: | Specify the [Riot ID](/en/terms/riotid) of the fith account in the analysis |
<br>
 
## Example
#### Picks for your team
![](/en_/en_stats_teamanalysis_picks.png)
<br>

#### Bans against your team
![](/en_/en_stats_teamanalysis_bans.png)

 <br>
 
## Related commands/pages:
- [/clash analysis](/en/commands/clashchannel/analysis)
- [All stats commands](/en/commands/stats)
{.links-list}