---
title: Refresh & Refresh mode
description: Learn about how Zoe's refresh works.
published: true
date: 2023-04-17T06:15:17.683Z
tags: update, refreh, mode, refresh mode, zoe mode
editor: markdown
dateCreated: 2021-07-07T19:15:54.142Z
---

# Refresh & Refresh mode

## Information

 All servers are updated at least once an hour. Unfortunately, there is currently no way to increase this in a stable way.

What you can do is be online and activate Discord presence, Zoe will detect the start and end of your game and update directly at the right time. This is sufficient for most cases.

There are plans to rework the refresh system to make it smarter, with a system that detects the hours of activity per account and refreshes them more frequently during those periods. But this isnt implemented yet.

### Related commands/pages:

-   [/refresh](/en/commands/important/refresh/)

## Refresh With Game Detection (smart mode)

If a registered user has activated the Discord presence, Zoe can see the start and end of a game and will trigger an update. This increases Zoe's responsiveness many times over. Therefore, it is highly recommended to activate the Discord presence if you want to get good & fast results with Zoe.

Note: If you share your screen with Discord's built-in stream function, the game will not be detected. (This is because "Currently streaming League of Legends" is displayed instead of "In game").

## Refresh Command

This is a command that triggers a refresh manually for one server.

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
|     | infoChannel | rankChannel | leaderboards | clashChannel |
| refresh command refreshes | Yes | Yes | Yes | No\* |

\*The clashChannel can be refreshed with the command [`>clash refresh`](/en/commands/clash/refresh/)