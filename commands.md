---
title: Zoe Commands
description: In here you find all commands listed.
published: true
date: 2025-08-18T19:43:26.254Z
tags: commands, cmd, cmds, order, orders, command
editor: markdown
dateCreated: 2021-07-05T11:30:13.397Z
---

> Click on a command to see its more detailed page.
>{.is-info}

# Basic Commands
- [/refresh *By issueing the command the infopanel and each leaderboard, etc. will be updated manually.*](/en/commands/basic/refresh/)
- [/help *When you execute this command, Zoe sends you a help message with helpful wiki pages.*](/en/commands/basic/help/)
{.links-list}

# Administrative Commands
- [/setup *With this command you will get information on how to set up Zoe on your Discord server. Useful if you need to re-setup Zoe after a reset.*](/en/commands/administrative/setup/) 
- [/language *With this command you can select the language Zoe speaks on your Discord server.*](/en/commands/administrative/language/)
- [/config *This command opens an interactive message in which you can configure Zoe navigating with reactions.*](/en/commands/administrative/config/)
- [/reset *The command performs a reset for your server. It resets the current configuration of your server. Try using this command when something is not going right.*](/en/commands/administrative/reset/)
- [/patchnotes *This command sends you the current Zoe patchnotes which are in English.*](/en/commands/administrative/patchnotes/)
- [/rawserverdata *When you execute this command, Zoe sends you the raw data of the players of your server.*](/en/commands/administrative/rawserverdata)
- [/ *.*](/en/commands/administrative/)
- [/ *.*](/en/commands/administrative/)
- [/ *.*](/en/commands/administrative/)
{.links-list}

# Channel Feature Commands
## Infochannel
- [/create infochannel *This command creates a new infochannel in which Zoe can send information about players current games.*](/en/commands/infochannel/create)
- [/delete infochannel *Using this command deletes the infochannel of your server after a refresh.*](/en/commands/infochannel/delete)
- [/define infochannel *With this command you can create an infochannel like the create command, except that the discord text channel already exists and is only defined.*](/en/commands/infochannel/define)
- [/undefine infochannel *This command undefines the current infochannel. This does not delete the text channel, Zoe will just not send anything in it anymore.*](/en/commands/infochannel/undefine)
{.links-list}

## Rankchannel
- [/create rankchannel *This command creates a rankchannel in which Zoe sends updates about ranks of registered players.*](/en/commands/rankchannel/create)
- [/delete rankchannel *Deletes the rankchannel of your server.*](/en/commands/rankchannel/delete)
- [/define rankchannel *Creates an rankchannel like the create command, except that the text channel already exists and is only defined.*](/en/commands/rankchannel/define)
- [/undefine rankchannel *Undefines the current rankchannel. This does not delete the text channel, Zoe will just not send anything in it anymore.*](/en/commands/rankchannel/undefine)
{.links-list}

## Leaderboards
- [/create leaderboard *This command starts the wizard for creating leaderboards.*](/en/commands/leaderboard/create)
- [/delete leaderboard *This command starts the wizard for deleting existing leaderboards.*](/en/commands/leaderboard/delete)
{.links-list}

## Clashchannel
- [/create clashchannel *This command creates a new clashchannel in which Zoe can send information about the current and upcoming clash for a specific league account.*](/en/commands/clashchannel/create)
- [/delete clashchannel *Use this command to delete an existing clashchannel.*](/en/commands/clashchannel/delete)
- [/clash refresh *This command must be sent within a clashchannel in order for it to be refreshed.*](/en/commands/clashchannel/refresh)
- [/clash analysis *This command sends an analysis of a team. If this command is sent within a clashchannel, the region is not mandatory.*](/en/commands/clashchannel/analysis)
{.links-list}

## Matchhistorychannel
- [/create matchhistorychannel *This command creates a matchhistorychannel in which Zoe sends all played games of the selected players.*](/en/commands/matchhistorychannel/create)
- [/delete matchhistorychannel *Using this command deletes the matchhistorychannel of your server.*](/en/commands/matchhistorychannel/delete)
{.links-list}

<br>

# Player Commands
- [/register *With this command, players on your server can register themselves for Zoe (needs to be enabled first).*](/en/commands/player/register)
- [/create player *This command creates a new player with the given information.*](/en/commands/player/create)
- [/delete player *By issuing this command you delete the mentioned player from the system in your server.*](/en/commands/player/delete)
- [/show players *With this command you will get displayed all players on your server with all their accounts.*](/en/commands/player/show-players/)
- [/add account *This command is used to connect another/secondary League of Legends account with a player in discord.*](/en/commands/player/addaccount)
- [/remove account *Removes the named account from the mentioned player.*](/en/commands/player/removeaccount)
- [/banaccount *Launches the banlist wizard. This allows you (an lol account owner) to delete their account from other servers and add it to the banlist to make it impossible for others to add it.*](/en/commands/player/banaccount)
- [/show bet-points & /bets show *Shows how many bet-points you or another player has.*](/en/commands/player/show-betpoints)
- [/bets give *This command allows you to give a specific number of your points to a specific user.*](/en/commands/player/betsgive)
{.links-list}

# Team Commands
- [/create team *This command creates a new team with the given name. This allows grouping players in the infopanel.*](/en/commands/team/create)
- [/delete team *Use this command to delete the mentioned team from the system in your server.*](/en/commands/team/delete)
- [/add playertoteam *This command adds the mentioned player to the named team.*](/en/commands/team/addplayer)
- [/remove playerfromteam *Removes the mentioned player from the named team.*](/en/commands/team/removeplayer)
- [/show team *With this command you will get displayed a short overview over all players of one team.*](/en/commands/team/show)
- [/join *Allows a player to join a team by themselves.*](/en/commands/team/join)
- [/leave *Allows a player to leave a team by themselves.*](/en/commands/team/leave)
{.links-list}

<br>

# Stats Commands
- [/stats profile *Zoe provides some information about the selected profile.*](/en/commands/stats/profile/)
- [/stats predictrole *Zoe predicts the role of 5 given accounts when they play together.*](/en/commands/stats/predictrole/)
- [/stats teamanalysis *Zoe predicts the role of 5 given accounts when they play together with pick and ban recommendations.*](/en/commands/stats/teamanalysis/)
- [/stats matchhistory *Allows you to browse the match history of LoL accounts and view match stats.*](/en/commands/stats/matchhistory)
- [/stats rankupdate *Zoe sums up information about LP-gains and -losses in one day, one week and one month.*](/en/commands/stats/rankupdate)
{.links-list}

<br>

# Subscription Commands
- [/boost *This command lets you boost the server you're using to a premium server.*](/en/commands/subscription/boost)
- [/subscription *This command shows you your current Zoe subscription status.*](/en/commands/subscription/subscription)
{.links-list}