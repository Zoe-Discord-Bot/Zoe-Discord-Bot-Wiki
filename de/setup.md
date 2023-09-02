---
title: Zoe Einrichtung
description: Auf dieser Seite erfährst du, wie du Zoe auf deinem Discord-Server einrichten kannst.
published: true
date: 2023-09-02T14:25:10.290Z
tags: setup, einrichten, einrichtung, start
editor: markdown
dateCreated: 2021-08-16T13:05:23.601Z
---

# Zoe Discord Bot Einrichtung

<br>

> Um Zoe einzurichten und zu nutzen, benötigst du die Berechtigung `Kanäle verwalten` auf deinem Server (falls du nicht ohnehin der Administrator bist).
{.is-warning}

<br>


## Zoe hinzufügen

Du kannst Zoe zu deinem Server hinzufügen, indem du auf der Homepage auf `Add the bot` klickst, auf Seiten wie [top.gg](https://top.gg/de/bot/550737379460382752) oder [bots.ondiscord.xyz](https://bots.ondiscord.xyz/bots/550737379460382752) und hier im Wiki unten links im Menü.
<br>
  
## Zoe authorisieren

Jetzt musst du dich mit deinem Discordkonto anmelden und den Server aussuchen, auf dem du Zoe hinzufügen willst. Bestätige dann noch Zoes Berechtigungen und löse gegebenenfalls ein Captcha. Danach ist Zoe auf deinem gewählten Server.

![](/de_/de_add_zoe_full.jpg)

## Einrichtung

Wenn Zoe das erste mal zu einem Server hinzugefügt wird, sendet Zoe eine kurze Nachricht in den Standardkanal des Servers.

Dann folgt die erste Einstellung. Du solltest die Sprache wählen, die Zoe auf deinem Server sprechen soll. (Für mehr Informationen schau dir den [`/language`](/en/commands/important/language) Befehl an. Du kannst mit den Reaktionen unter der Nachricht durch die Sprachen navigieren.

![](/new_setup5.png)

Direkt danach musst du die standard League of Legends Serverregion auswählen. Die verfügbaren Tags sind:

| Tag | BR  | EUNE | EUW | LAN | LAS | NA  | OCE | RU  | TR  | JP  | KR  | PH  | SG  | TW  | TH  | VN  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Region | Brazilien | Nord- und Osteuropa | Westeuropa | Lateinamerika Nord | Lateinamerika Süd | Nordamerika | Ozeanien | Russland | Türkei | Japan | Republik Korea | Die Philippinen | Singapur, Malaysia & Indonesien | Taiwan, Hongkong & Macao | Thailand | Vietnam |

> Du kannst diese Einstellung später in der Konfiguration ändern wenn du willst. (Siehe dazu: [`/config`](/en/commands/important/config)).
>{.is-info}
  
![](/new_setup4.png)

> Jetzt sendet Zoe eine neue Nachricht über das nächste Vorgehen. Lies dazu mehr in der nächsten Sektion.

<br>

# 1\. Daten hinzufügen (aka Spieler registrieren)

Um Zoe nutzen zu können musst du zuerst Spieler registrieren/erstellen. Ein Spieler besteht aus einem Discordkonto und einem oder mehreren Leaguekonten und wird in den verschiedenen Features angezeigt.

**Es gibt zwei Möglichkeiten dies zu tun:**

1.  Du kannst sie selbst erstellen mit dem Befehl [`/create player`](/en/commands/create/player) (erlaubt dir einen Spieler, also Discordkonto und Leaguekonto, für jemanden/jemand anderen zu erstellen).
2.  Auch kannst du in der Konfiguration aktivieren, dass sich jeder Benutzer deines Server selbst mit dem Befehl [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) selbst einen Spieler erstellen kann. (Siehe mehr unter: [`/register`](https://wiki.zoe-discord-bot.ch/en/commands/important/register) und [`/config`](https://wiki.zoe-discord-bot.ch/en/commands/important/config)).

[`/add account`](/en/commands/add/account) erlaubt es dir ein zusätzliches Leaguekonto zu einem bestehenden Spieler hinzuzufügen.

Um einen Spieler zu löschen, benutze den Befehl [`/delete player`](/en/commands/delete/player) (löscht den Spieler) und [`/remove account`](/en/commands/remove/account) (löscht das jeweilig verbundene Leaguekonto).

> Du kannst dir alle registrierten Spieler anzeigen lassen mit dem Befehl [`/show players`](/en/commands/important/show-players).
>{.is-info}

<br>
  
# 2\. Spieler anzeigen (aka Features benutzen)
>Du musst keine dieser Funktionen einrichten, dies ist nur eine Vorschlagsliste. Wenn du dir alle Funktionen ansehen möchtest, [ist hier ein Link zu allen Funktionen](/en/features) and [hier zu allen Befehlen](/en/commands/).
>{.is-info}

## Infokanal (schreibgeschützter Kanal empfohlen)

Der Infokanal enthält Statistiken zu Spielern sowie Statistiken zu laufenden Spielen.

![](/new_infopanel.png)
<img src="/new_gamecard.png" width="50%" />

> Für mehr Informationen zum Infokanal klicke [HIER](/en/features/infoChannel).
  >{.is-info}

<br>
  
## Rangkanal (schreibgeschützter Kanal empfohlen)

Der Rangkanal ist der Kanal, in dem nach jedem Ranglistenspiel der registrierten Spieler eine Nachricht verschickt wird. Diese Nachrichten enthalten die Anzahl der gewonnenen oder verlorenen LP und einige Statistiken über die Leistung des Spielers im Spiel wie KDA, Dauer des Spiels und Itembuild.
![](/new_rankchannel_message.png)

>Für mehr Informationen zum Rangkanal klicke [HIER](/en/features/rankChannel).
  >{.is-info}

<br>
  
## Clashkanal

Dieser Kanal sendet Statistiken über ein Konto in Bezug auf Clash. Er enthält Pläne für zukünftige Kämpfe in deiner Zeitzone sowie Statistiken über dein Team. Du kannst auch eine detaillierte Analyse des gegnerischen Teams mit Bannempfehlungen durchführen.

![](/new_statsteamanalysis.png)

> Für mehr Informationen zum Clashkanal klicke [HIER](/en/features/clashChannel).
  >{.is-info}

<br>
  
## Leaderboards (ein eigener Kanal mit mehreren Leaderboards wird empfohlen)

Mit dieser Funktion kannst du Leaderboards erstellen, die automatisch aktualisiert werden. Es stehen dir mehrere Arten zur Verfügung:

- Gesamtmeisterschaftspunkte
- **Meisterschaftspunkte auf einem Champion**
- Rang in einer Warteschlange (Solo/DuoQ, Flex, etc.)
- Bester Rang in der allen Warteschlange
- Durchschnittliche KDA
- Durchschnittliche KDA auf einem Champion
- Bester Champion ("OTP")
- Account-Level

![](/new_leaderboard_mastery_points_champion.png)

> Für mehr Informationen zu Leaderboards klicke [HIER](/en/features/leaderboards).
  >{.is-info}

<br>
  
## Automatisierte Discord-Rollen nach League-Rang

Du kannst mit Zoe ganz einfach ein automatisches Rollensystem einrichten. Die Rollen werden regelmäßig automatisch aktualisiert. Die Premium-Version dieses Features bietet mehr Optionen (Filter nach Serverregion, Anzeige jeder Division, volle Kontrolle über jede Rolle und mehr).

![](/improved_rankroles_5.png)

Sobald deine Rollen korrekt eingerichtet sind, werden sie automatisch aktualisiert, sobald ein Spiel über die Discord-Präsenz der registrierten Spieler erkannt wird, mindestens jedoch einmal pro Stunde. Du kannst deinen Server auch mit dem Befehl [`/refresh`](/en/commands/important/refresh) aktualisieren.

> Für mehr Informationen zu Rangrollen klicke [HIER](/en/features/rankroles).
  >{.is-info}

<br>  

# 3\. Anpassung der Features (denn jeder Server ist anders)

> Um Zoe und seine verschiedenen Einstellungen zu verwalten, verwenden diesen Befehl: [`/config`](/en/commands/important/config). 
 Lese hier alles über die Konfiguration: [**Konfiguration**](/en/Zoe-Configuration/).
>{.is-info}

<br>
  
# 4\. Wir machen immer weiter

Zoe hat viele weitere Funktionen. Du kannst dir alle Befehle ansehen, wenn du [HIER](http://wiki.zoe-discord-bot.ch/en/commands) klickst.

Ein Beispiel wäre [`/stats profile`](/en/commands/stats/profile), dass es dir erlaubt ein Profil eines Spielers anzusehen.

![](/new_statsprofile.png)

<br>
  
# Einrichtung - Schlusswort

> Zoe ist ein aktiv entwickelter Bot, der ein ⭐Premium-Abonnement⭐ zur Unterstützung seiner Entwicklung anbietet. Dieses Abonnement bietet einige zusätzliche Optionen, ist aber bei weitem nicht obligatorisch. 
Für weitere Informationen: [Abonnement Wikiseite](https://wiki.zoe-discord-bot.ch/en/support), [Boosting](https://wiki.zoe-discord-bot.ch/en/Zoe-Points-And-Boosting), [`/subscription`](/en/commands/important/subscription) & [`/boost`](/en/commands/important/boost)
  

> Wenn du die Liste mit allen Befehlen sehen willst: [`/help`](/en/commands/important/help) oder klicke [HIER](/en/commands/).
> Wenn du Fragen oder Anregungen hast oder Hilfe brauchst, komm bitte hierher: [https://discord.gg/whc5PrC](https://discord.gg/whc5PrC)   
> *Führen den Befehl aus, um die Hilfemeldung für die Einrichtung zu lesen:* [`/setup`](/en/commands/important/setup)
  >{.is-info}