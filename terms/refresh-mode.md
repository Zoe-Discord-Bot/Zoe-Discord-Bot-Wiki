---
title: Refresh & Refresh mode
description: Learn about how Zoe's refresh works.
published: true
date: 2024-07-03T06:46:26.451Z
tags: refresh, update, mode, refresh mode, zoe mode
editor: markdown
dateCreated: 2021-07-07T19:15:54.142Z
---

# Refresh & Refresh mode
## Information
**All servers are updated at least once an hour. Unfortunately, there is currently no way to increase this in a stable way.** <br>
**What you can do is be online and activate Discord presence, Zoe will detect the start and end of your game and update directly at the right time. This is sufficient for most cases.** <br>
**There are plans to rework the refresh system to make it smarter, with a system that detects the hours of activity per account and refreshes them more frequently during those periods. But this isn't implemented yet.**

## Related commands/pages:
-   [/refresh](/en/commands/basic/refresh/)
{.links-list}

<br>

## Refresh with game detection

If a registered [player](/en/terms/player) has activated the Discord presence, Zoe can see the start and end of a game and will trigger an update. This increases Zoe's responsiveness many times over. Therefore, it is highly recommended to activate the Discord presence if you want to get good & fast results with Zoe.

>If you are streaming via Discord or using a recording program that changes the Discord rich presence (like MedalTV) the above principle does not work. Please end your stream or turn off the Discord Presence of the program so that `Playing League of Legends` is visible, only then will you receive all the information directly (This is because `Streaming League of Legends` or `Clipping League of Legends` is displayed instead of `Playing League of Legends`). <br>
> ![](/discord_presence.png)
>{.is-info}

<br>

## Refresh command
The [`/refresh`](/en/commands/basic/refresh) command triggers a refresh manually for the server you use it on. Every feature is refreshed with this command besides the [clashchannel](/en/features/clashchannel). The [clashchannel](/en/features/clashchannel) can be refreshed with the command [`/clash refresh`](/en/commands/clashchannel/refresh/).

