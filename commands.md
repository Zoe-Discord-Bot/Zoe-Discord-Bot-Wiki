---
title: Zoe Commands
description: In here you find all commands listed.
published: true
date: 2024-01-09T16:49:07.526Z
tags: commands, cmd, cmds, order, orders, command
editor: markdown
dateCreated: 2021-07-05T11:30:13.397Z
---

# Zoe Commands - List

> This list contains all commands you can use. Click on any link on the right to look at a more detailed site about a command.

## Important Commands

| Command | Explanation | Link |
| --- | --- | --- |
| `/setup` | With this command you will get information on how to set up Zoe on your Discord server. Useful if you need to re-setup Zoe after a reset. | [Click here](/en/commands/important/setup/) |
| `/language` | With this command you can select the language Zoe speaks on your Discord server. | [Click here](/en/commands/important/language/) |
| `/config` | This command opens an interactive message in which you can configure Zoe navigating with reactions. | [Click here](/en/commands/important/config/) |
| `/refresh` | By issueing the command the [infopanel](/en/features/infoChannel) and each [leaderboard](/en/features/leaderboards), etc. will be updated manually. | [Click here](/en/commands/important/refresh/) |
| `/help` | When you execute this command, Zoe sends you a help message with helpful wiki pages. | [Click here](/en/commands/important/help/) |
| `/reset` | The command performs a reset for your server. It resets the current configuration of your server. Try using this command when something is not going right. | [Click here](/en/commands/important/reset/) |
| `/boost` | This command lets you [boost](/en/commands/important/boost) the server you're using to a [premium server](/en/Zoe-Points-And-Boosting). | [Click here](/en/commands/important/boost) |
| `/subscription` | This command shows you your current Zoe subscription status. | [Click here](/en/commands/important/subscription) |

## Channel Feature Commands

### Infochannel

| Command | Explanation | Link |
| --- | --- | --- |
| `/create infochannel` | This command creates a new [infochannel](/en/features/infoChannel) in which Zoe can send information about [players](/en/terms/player) current games. | [Click here](/en/commands/create/infoChannel/) |
| `/delete infochannel` | Using this command deletes the [infochannel](/en/features/infoChannel) of your server after a refresh. | [Click here](/en/commands/delete/infoChannel/) |
| `/define infochannel` | With this command you can create an [infochannel](/en/features/infoChannel) like the create command, except that the discord text channel already exists and is only defined. | [Click here](/en/commands/define/infoChannel/) |
| `/undefine infochannel` | This command undefines the current [infochannel](/en/features/infoChannel). This does not delete the text channel, Zoe will just not send anything in it anymore. | [Click here](/en/commands/undefine/infoChannel/) |

### Rankchannel

| Command | Explanation | Link |
| --- | --- | --- |
| `/create rankchannel` | This command creates a [rankchannel](/en/features/rankChannel) in which Zoe sends updates about ranks of registered players. | [Click here](/en/commands/create/rankChannel/) |
| `/delete rankchannel` | Deletes the [rankchannel](/en/features/rankChannel) of your server. | [Click here](/en/commands/delete/rankChannel/) |
| `/define rankchannel` | Creates an [rankchannel](/en/features/rankChannel) like the create command, except that the text channel already exists and is only defined. | [Click here](/en/commands/define/rankChannel/) |
| `/undefine rankchannel` | Undefines the current [rankchannel](/en/features/rankChannel). This does not delete the text channel, Zoe will just not send anything in it anymore. | [Click here](/en/commands/undefine/rankChannel/) |

### Clashchannel

| Command | Explanation | Link |
| --- | --- | --- |
| `/create clashchannel` | This command creates a new [clashchannel](/en/features/clashChannel) in which Zoe can send information about the current and upcoming clash for a specific league account. | [Click here](/en/commands/create/clashChannel/) |
| `/delete clashchannel` | Use this command to delete an existing [clashchannel](/en/features/clashChannel). | [Click here](/en/commands/delete/clashChannel/) |
| `/clash refresh` | This command must be sent within a [clashchannel](/en/features/clashChannel) in order for it to be refreshed. | [Click here](/en/commands/clash/refresh/) |
| `/clash analysis` | This command sends an analysis of a team. If this command is sent within a [clashchannel](/en/features/clashChannel), the region is not mandatory. | [Click here](/en/commands/clash/analysis/) |

### Matchhistorychannel

| Command | Explanation | Link |
| --- | --- | --- |
| `/create matchhistorychannel` | This command creates a [matchhistorychannel](/en/features/matchhistoryChannel) in which Zoe sends all played games of the selected [players](/en/terms/player). | [Click here](/en/commands/create/matchhistorychannel) |
| `/delete matchhistorychannel` | Using this command deletes the [matchhistorychannel](/en/features/matchhistoryChannel) of your server. | [Click here](/en/commands/delete/matchhistorychannel) |

### Leaderboards

| Command | Explanation | Link |
| --- | --- | --- |
| `/create leaderboard` | This command starts the wizard for creating [leaderboards](/en/features/leaderboards). | [Click here](/en/commands/create/leaderboard/) |
| `/delete leaderboard` | This command starts the wizard for deleting existing [leaderboards](/en/features/leaderboards). | [Click here](/en/commands/delete/leaderboard/) |

## Player/Account/Team Commands

| Command | Explanation | Link |
| --- | --- | --- |
| `/register` | With this command, [players](/en/terms/player) on your server can register themselves for Zoe (needs to be enabled first). | [Click here](/en/commands/important/register/) |
| `/create player` | This command creates a new [player](/en/terms/player) with the given information. | [Click here](/en/commands/create/player/) |
| `/delete player` | By issuing this command you delete the mentioned [player](/en/terms/player) from the system in your server. | [Click here](/en/commands/delete/player/) |
| `/create team` | This command creates a new team with the given name. This allows grouping players in the [infopanel](/en/features/infoChannel). | [Click here](/en/commands/create/team/) |
| `/delete team` | Use this command to delete the mentioned team from the system in your server. | [Click here](/en/commands/delete/team/) |
| `/add playertoteam` | This command adds the mentioned [player](/en/terms/player) to the named team. | [Click here](/en/commands/add/playerToTeam/) |
| `/remove playerfromteam` | Removes the mentioned [player](/en/terms/player) from the named team. | [Click here](/en/commands/remove/playerToTeam/) |
| `/add account` | This command is used to connect another/secondary League of Legends account with a [player](/en/terms/player) in discord. | [Click here](/en/commands/add/account/) |
| `/remove account` | Removes the named account from the mentioned [player](/en/terms/player). | [Click here](/en/commands/remove/account/) |
| `/banaccount` | Launches the banlist wizard. This allows you (an lol account owner) to delete their account from other servers and add it to the banlist to make it impossible for others to add it. | [Click here](/en/commands/other/banAccount/) |
| `/show players` | With this command you will get displayed all [players](/en/terms/player) on your server with all their accounts. | [Click here](/en/commands/important/show-players/) |

## Stats Commands

| Command | Explanation | Link |
| --- | --- | --- |
| `/stats profile` | Zoe provides some information about the selected profile. | [Click here](/en/commands/stats/profile/) |
| `/stats predictrole` | Zoe predicts the role of 5 given accounts when they play together. | [Click here](/en/commands/stats/predictRole/) |
| `/stats teamanalysis` | Zoe predicts the role of 5 given accounts when they play together with pick and ban recommendations. | [Click here](/en/commands/stats/teamAnalysis/) |
| `/stats matchhistory` | Allows you to browse the match history of LoL accounts and view match stats. | [Click here](/en/commands/stats/matchhistory) |
| `/stats rankupdate` | Zoe sums up information about LP-gains and -losses in one day, one week and one month. | [Click here](/en/commands/stats/rankupdate) |

## Other Commands

| Command | Explanation | Link |
| --- | --- | --- |
| `/patchnotes` | This command sends you the current [Zoe patchnotes](/en/patchnotes) which are in English. | [Click here](/en/commands/other/patchNotes/) |