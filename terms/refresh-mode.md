---
title: Refresh & Refresh mode
description: Learn about how Zoe's refresh works.
published: true
date: 2025-09-07T11:05:35.779Z
tags: refresh, update, mode, refresh mode, zoe mode
editor: markdown
dateCreated: 2021-07-07T19:15:54.142Z
---

# Refresh & Refresh mode
## Information
**With V1.14.0 the refresh system has been completely reworked and now works on a per-account basis.**
**Every account is refreshed independently every 20 minutes. Premium servers enjoy faster refresh rates of 10 minutes or even 5 minutes depending on their size.**
**In addition, Zoe dynamically adjusts the refresh schedule when games are detected (see below), making the system far more accurate and responsive than before.**
<br>

### How it works
- **Base refresh**: Every 20 minutes per account (10 / 5 minutes on premium servers depending on size).  
- **During games**:  
  - One refresh between **7–8 minutes** into the game.  
  - Every **2 minutes** after **15 minutes** of game time.  
- **After games**:  
  - Every **2 minutes** for **20 minutes** after a game finishes, to catch re-queues quickly.  

This ensures that messages related to game start, end and rank changes are detected and delivered much faster, especially after the first game of a session.
<br>

## Related commands/pages:
-   [/refresh](/en/commands/basic/refresh/)
{.links-list}

<br>

## Refresh with game detection

If a registered [player](/en/terms/player) has activated the Discord presence, Zoe can still detect the start and end of a game directly and trigger an immediate update.  
This works in addition to the per-account refresh cycle and increases responsiveness even more.  
It is therefore highly recommended to activate Discord presence if you want the best and fastest results with Zoe.

> If you are streaming via Discord or using a recording program that changes the Discord rich presence (like MedalTV), the above principle does not work. Please end your stream or turn off the Discord Presence of the program so that `Playing League of Legends` is visible, only then will you receive all the information directly (This is because `Streaming League of Legends` or `Clipping League of Legends` is displayed instead of `Playing League of Legends`). <br>
> ![](/discord_presence.png)
>{.is-info}

<br>

## Refresh command
The [`/refresh`](/en/commands/basic/refresh) command triggers a manual refresh for the server you use it on.  
Every feature is refreshed with this command besides the [clashchannel](/en/features/clashchannel).  
The [clashchannel](/en/features/clashchannel) can be refreshed with the command [`/clash refresh`](/en/commands/clashchannel/refresh/).
