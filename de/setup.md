---
title: Zoe Einrichtung
description: Auf dieser Seite erfährst du, wie du Zoe auf deinem Discord-Server einrichten kannst.
published: false
date: 2023-05-19T21:46:22.233Z
tags: setup, einrichten, einrichtung, start
editor: markdown
dateCreated: 2021-08-16T13:05:23.601Z
---

# Zoe Discord Bot Einrichtung

<p>

> Um Zoe einzurichten und zu nutzen, benötigst du die Berechtigung "Kanäle verwalten" auf deinem Server (falls du nicht ohnehin der Administrator bist).
{.is-warning}
<p>

## Zoe hinzufügen

Du kannst Zoe zu deinem Server hinzufügen, indem du auf der Homepage auf `Add bot` klickst, auf Seiten wie [top.gg](https://top.gg/de/bot/550737379460382752) oder [bots.ondiscord.xyz](https://bots.ondiscord.xyz/bots/550737379460382752) und hier im Wiki unten links im Menü.
<p>
  
## Zoe authorisieren

Jetzt musst du dich mit deinem Discordkonto anmelden und den Server aussuchen, auf dem du Zoe hinzufügen willst. Bestätige dann noch Zoes Berechtigungen und löse gegebenenfalls ein Captcha. Danach ist Zoe auf deinem gewählten Server.

![](/new_setup1-3.png)

## Einrichtung

Wenn Zoe das erste mal zu einem Server hinzugefügt wird, sendet Zoe eine kurze Nachricht in den Standardkanal des Servers.

Dann folgt die erste Einstellung. Du solltest die Sprache wählen, die Zoe auf deinem Server sprechen soll. (Für mehr Informationen schau dir den [`/language`](/en/commands/important/language) Befehl an. Du kannst mit den Reaktionen unter der Nachricht durch die Sprachen navigieren.

![](/new_setup5.png)

Direkt danach musst du die standard League of Legends Serverregion auswählen. Die verfügbaren Tags sind:

| Tag | BR  | EUNE | EUW | LAN | LAS | NA  | OCE | RU  | TR  | JP  | KR  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Region | Brazil | Europe Nordic & East | Europe West | Latin America North | Latin America South | North America | Oceania | Russia | Turkey | Japan | Republic of Korea |

> Du kannst diese Einstellung später in der Konfiguration ändern wenn du willst. (Siehe dazu: [`/config`](/en/commands/important/config)).
>{.is-info}
  
![](/new_setup4.png)

> Jetzt sendet Zoe eine neue Nachricht über das nächste Vorgehen. Lies dazu mehr in der nächsten Sektion.
<p>

# 1\. Daten hinzufügen (aka Spieler registrieren)

Um Zoe nutzen zu können musst du zuerst Spieler registrieren/erstellen. Ein Spieler besteht aus einem Discordkonto und einem oder mehreren Leaguekonten und wird in den verschiedenen Features angezeigt.

**Es gibt zwei Möglichkeiten dies zu tun:**

1.  Du kannst sie selbst erstellen mit dem Befehl [`/create player`](/en/commands/create/player) (erlaubt dir einen Spieler, also Discordkonto und Leaguekonto, für jemanden/jemand anderen zu erstellen).
2.  Auch kannst du in der Konfiguration aktivieren, dass sich jeder Benutzer deines Server selbst mit dem Befehl [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) selbst einen Spieler erstellen kann. (Siehe mehr unter: [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) und [`/config`](https://wiki.zoe-discord-bot.ch/en/commands/important/config)).

[`/add account`](/en/commands/add/account) erlaubt es dir ein zusätzliches Leaguekonto zu einem bestehenden Spieler hinzuzufügen.

Um einen Spieler zu löschen, benutze den Befehl [`/delete player`](/en/commands/delete/player) (löscht den Spieler) und [`/remove account`](/en/commands/remove/account) (löscht das jeweilig verbundene Leaguekonto).

> Du kannst dir alle registrierten Spieler anzeigen lassen mit dem befehl [`/show players`](/en/commands/important/show-players).
>{.is-info}
<p>
  
# 2\. Show players (aka use features)
>You don't have to set up any of these features, this is just a suggestion-list. If you want to look around all features, [here is a link to all the features](/en/features) and [here to all commands](/en/commands/).
>{.is-info}

## Infochannel (read-only channel recommended)

The infochannel contains stats on players as well as stats on games currently in progress.

![](/new_infopanel.png)
<img src="/new_gamecard.png" width="50%" />

> For more information about the infochannel click [HERE](/en/features/infoChannel).
  >{.is-info}
<p>
  
## Rankchannel (read-only channel recommended)

The rankchannel is, where a message will be sent after each ranked game of the registered players. These messages contain the amount of won or lost LP and some stats on the player ingame performance like KDA, duration of the game and itembuild.

![](/new_rankchannel_message.png)

> For more information about the rankchannel click [HERE](/en/features/rankChannel).
  >{.is-info}
<p>
  
## Clashchannel

This channel will send stats about an account in relation to clash. It will contain schedules of future clashes in your timezone as well as stats about your team. You will also be able to do an detailed analysis of enemy teams with ban recommendations.

![](/new_statsteamanalysis.png)

> For more information about the clashchannel click [HERE](/en/features/clashChannel).
  >{.is-info}
<p>
  
## Leaderboards (a dedicated channel with several leaderboards within is recommended)

This feature allows you to create leaderboards that refresh automatically. Several types are available to you:

-   Total Mastery Points
-   **Mastery Points on a champion**
-   Rank in a Queue (Solo/DuoQ, Flex, etc)
-   All Queue Rank
-   Average KDA
-   Average KDA on a champion
-   Best Champion ("OTP")
-   Account Level

![](/new_leaderboard_mastery_points_champion.png)

> For more information about leaderboards click [HERE](/en/features/leaderboards).
  >{.is-info}
<p>
  
## Automated Discord roles by League rank

You can set up an automatic rank system with Zoe easily. The roles will be refreshed regularly automatically. The premium version of this feature offers more options (filter by server region, display of each division, full control over each role and more).

![](/improved_rankroles_5.png)

Once your features are set up correctly, they will update automatically as soon as a game is detected via the Discord presence of registered players or once an hour at least. You can also refresh your server with the command [`/refresh`](/en/commands/important/refresh).

> For more information about rankroles click [HERE](/en/features/rankroles).
  >{.is-info}
<p>
  
# 3\. Customize these features (because every server is different)

> To manage Zoe and all the different settings it offers, use this command: [`/config`](/en/commands/important/config). 
 Read everything about the configuration here: [**Configuration**](/en/Zoe-Configuration/).
>{.is-info}
<p>
  
# 4\. Going further (We never stop!)

Zoe has many more features. You can have a look at all commands if you click [HERE](http://wiki.zoe-discord-bot.ch/en/commands).

One example being [`/stats profile`](/en/commands/stats/profile) letting you view a players profile:

![](/new_statsprofile.png)
<p>
  
# Setup - Final words

> Zoe is an actively developed bot that offers a ⭐premium subscription⭐ to support its development. This subscription offers some additional options but is by far not mandatory. 
For more information: [Subscription Wiki page](https://wiki.zoe-discord-bot.ch/en/support), [Boosting](https://wiki.zoe-discord-bot.ch/en/Zoe-Points-And-Boosting), [`/subscription`](/en/commands/important/subscription) & [`/boost`](/en/commands/important/boost)
  

> If you want to see the list of commands: [`/help`](/en/commands/important/help) or click [HERE](/en/commands/).
> If you have any questions, suggestions or need help, please come here: [https://discord.gg/whc5PrC](https://discord.gg/whc5PrC)   
> *To review the setup help message, do the command:* [`/setup`](/en/commands/important/setup)
  >{.is-info}