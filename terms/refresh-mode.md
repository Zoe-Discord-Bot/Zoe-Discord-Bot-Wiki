---
title: Refresh & Refresh mode
description: Learn about how Zoe's refresh works.
published: true
date: 2023-04-17T06:31:59.759Z
tags: update, refreh, mode, refresh mode, zoe mode
editor: markdown
dateCreated: 2021-07-07T19:15:54.142Z
---

# Refresh & Refresh mode

>### Information
>All servers are updated at least once an hour. Unfortunately, there is currently no way to increase this in a stable way. <br>
>What you can do is be online and activate Discord presence, Zoe will detect the start and end of you  game and update directly at the right time. This is sufficient for most cases. <br>
>There are plans to rework the refresh system to make it smarter, with a system that detects the hours of activity per account and refreshes them more frequently during those periods. But this isnt implemented yet.
>{.is-info}

>### Related commands/pages:
>-   [/refresh](/en/commands/important/refresh/)

<br>

## Refresh with game detection

>  If a registered user has activated the Discord presence, Zoe can see the start and end of a game and will trigger an update. This increases Zoe's responsiveness many times over. Therefore, it is highly recommended to activate the Discord presence if you want to get good & fast results with Zoe.
>{.is-info}

>Note: If you are streaming via Discord or using a recording program that changes the Discord rich presence (like MedalTV).
Please end your stream or turn off the Discord Presence of the program so that `Playing League of Legends` is visible, only then will you receive all the information directly (This is because `Streaming League of Legends` or `Clipping League of Legends` is displayed instead of `Playing League of Legends`).
>{.is-warning}

![](/discord_presence.png)

<br>

## Refresh command

> The [`/refresh`](/en/commands/important/refresh) command triggers a refresh manually for the server you use it on. 
>Every feature is refreshed with this command besides the clashChannel. The clashChannel can be refreshed with the command [`>clash refresh`](/en/commands/clash/refresh/).
>{.is-info}
