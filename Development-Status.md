---
title: Zoe Development Status
description: If you are interested in what features await you in the future, you can get an insight here.
published: true
date: 2023-08-15T11:49:50.130Z
tags: dev, status, dev status, development, development status, future, next features
editor: markdown
dateCreated: 2023-05-11T20:07:22.784Z
---

## **Indicators**

| Indicator | Meaning | Description |
| --- | --- | --- |
| ⚫   | **Recorded** | We are aware of this feature/change, but do not have a patch planned yet. |
| ⚪   | **Scheduled** | We are aware of this feature/change and have it planned for a patch. |
| 🔴  | **Delayed** | We have determined that we need to delay this feature/change until a later date. |
| 🟡  | **In Development** | The feature/change is currently being worked on. |
| 🔵  | **In Testing** | The feature/change is currently being tested for bugs and functionality. |
| 🟢  | **Done** | The feature/change is ready for use and we are preparing for the patch. |
| ⭐   | **Early Access** | The feature/change is currently only available for early access servers/users. |
| 🏁  | **Deployed** | The feature/change is made available to all Zoe users. |

# Scheduled future changes

> Generally, the changes listed on this page are implemented. However, we do not guarantee that this is always the case. We would also like to point out that we reserve the right to make small changes to the schedule. Thank you for your understanding.

### 1.13.3 / Fixes

-   🏁 **Internal**: Optimise database usage to avoid slowdowns (Will continue even after being deployed)
-   🏁 **Fix**: Champion analysis
-   🏁 **Fix**: Simplify subscription embed to make it more clear overall
-   🏁 **QoL**: Discord namechange > display usernames correctly
-   🏁 **Fix**: Add option to disable rank update or select in which interval it is sent in the rankchannel
-   🏁 **Fix:** fix discord markdown issues on leaderboards
-   🏁 **Fix**: Correct period strings when using the rankupdate command

### 1.14 / AI Match Summary & Quality of Life

-   🟡 **Feature**: AI Match Summary (summarizes a game in text in a way that you can choose)
-   ⚪ **Feature**: Adding Champion analysis as seperate command
-   ⚪ **QoL**: Add another digit to make average KDA more detailed
-   ⚪ **QoL**: Improve team-analysis to add several players in one command
-   ⚪ **QoL**: Increase listed matches in matchhistory command (5 > 10)
-   ⚪ **QoL**: Small change to matchhistorychannel and command to increase visibility of KDA
-   ⚪ **QoL**: Auto refresh after /register was done to instantly add the registered player to infopanel and give their rank.

### 1.14.1 / Lane icons and automated Roles

-   ⚪ **QoL**: Add lane icons to clashchannel and team-analysis.
-   ⚪ **Feature**: Lane roles: roles that are assigned to registered players based on what lanes they played in recent games.
-   ⚪ **Feature**: Rank Roles (Free, Premium and Peak-Elo): Add a "unranked/In Placements" role to the bottom of ranks that shows at season start & unranked players

### 1.14.2 / More & better leaderboards

-   ⚪ **Feature**: Winrate leaderboard for winrate in general, per champion or per queue (Solo/Duo, Flex) in the last 30 days.
-   ⚪ **Feature**: Recent playtime leaderboard for playtime in general, per champion or per queue (Solo/Duo, Flex (TFT tbt.)) in the last 30 days.
-   ⚪ **Feature**: Average KDA leaderboard per queue (Solo/Duo, Flex (TFT tbt.))
-   ⚪ **Feature**: New way to create leaderboards for teams
-   ⚪ **QoL**: Add Mastery emotes and new filter option to mastery leaderboards

### 1.14.3 / Patchnotes

-   ⚪ **Feature**: League of Legends or/and TFT patchnotes are provided in a channel of your choice.

### 1.14.4 / Matchhistorychannel

-   ⚪ **QoL**: Display mhc runes only in detailed view
-   ⚪ **Config**: create a setting to choose which view is displayed by default

### 1.15 / More and better advice & analysis

-   ⚪ **Feature**: Early game advice
-   ⚪ **Feature**: team- and clashanalysis of possible matchups, advantages and disadvantages
-   ⚪ **QoL**: Automatically analyse enemies in clashchannel

# Recorded future changes

> Here are ideas listed which we have already recorded but which are not yet planned for a patch.

-   ⚫ Feature: Allow Zoe to give your server members nicknames based on their summonername (main account)
-   ⚫ QoL: Add a filter to rankupdate messages to select queues
-   ⚫ QoL: Add a filter to the rankchannel to select queues