---
title: Zoe Einrichtung
description: Auf dieser Seite erfährst du, wie du Zoe auf deinem Discord-Server einrichten kannst.
published: true
date: 2025-02-23T17:19:25.221Z
tags: setup, einrichten, einrichtung, start
editor: markdown
dateCreated: 2021-08-16T13:05:23.601Z
---

# Zoe Einrichtung
> Um Zoe einzurichten benötigst du die Berechtigung `Kanäle verwalten` auf deinem Server (falls du nicht ohnehin der Administrator bist).
{.is-warning}

<br>

## Zoe hinzufügen
Du kannst Zoe zu deinem Server hinzufügen, indem du auf der Homepage auf [<kbd>Add to Discord</kbd>/<kbd>Invite Zoe</kbd>](https://zoe-discord-bot.ch) klickst, auf Seiten wie [top.gg](https://top.gg/de/bot/550737379460382752) oder [bots.ondiscord.xyz](https://bots.ondiscord.xyz/bots/550737379460382752) und hier im Wiki unten links im Menü.
<br>
  
## Zoe authorisieren
Jetzt musst du dich mit deinem Discordkonto anmelden und den Server aussuchen, auf dem du Zoe hinzufügen willst. Bestätige dann noch Zoes Berechtigungen und löse gegebenenfalls ein Captcha und dann kannst du loslegen.
![](/img/general/discord_setup.png)

## Einrichtung
Wenn Zoe das erste mal zu einem Server hinzugefügt wird, sendet Zoe eine kurze Nachricht in den Standardkanal des Servers.

Dann folgt die erste Einstellung. Du solltest die Sprache wählen, die Zoe auf deinem Server sprechen soll. (Für mehr Informationen schau dir den [`/language`](/de/commands/administrative/language) Befehl an. Du kannst mit den Reaktionen unter der Nachricht durch die Sprachen navigieren.

<div class="discord-preview">
    <div class="embed">
      <div><b>English (100%)</b></div>
       <div>Arabic (31.9%)</div>
       <div>Deutsch (100%)</div>
      <div>Español (48.3%)</div>
      <div>Français (73.4%)</div>
      <div>Italiano (96%)</div>
      <div>Polski (27.6%)</div>
      <div>Português/BR (42.8%)</div>
      <div>Русский (26.3%)</div>
      <div>Turkish (20.9%)</div>
    </div>
    <div class="reactions">
        <div class="reaction">🔼 1</div>
        <div class="reaction">✅ 1</div>
        <div class="reaction">❎ 1</div>
        <div class="reaction">🔽 1</div>
    </div>
</div>
<br>

Direkt danach musst du die Standard League of Legends [Serverregion](/de/terms/region) auswählen. Wenn du Hilfe brauchst, findest du alle hier: [Regionen](/de/terms/region).

> Keine Sorge, du kannst immer auch andere Regionen auswählen. Das Setzen der Standardregion sperrt keinen anderen Regionen.
>{.is-warning}

> Du kannst diese Einstellung später in der Konfiguration ändern, wenn du willst. (Siehe dazu: [`/config`](/de/commands/administrative/config)).
>{.is-info}
  
<div class="discord-preview">
    <div class="embed">
        <div><b>Region EUW</b></div>
        <div>Region EUNE</div>
        <div>Region BR</div>
      	<div>Region JP</div>
      	<div>Region KR</div>
      	<div>Region LAN</div>
      	<div>Region LAS</div>
      	<div>Region NA</div>
      	<div>Region OCE</div>
      	<div>Region TR</div>
				<div>Region RU</div>
				<div>Region SEA</div>
				<div>Region VN</div>
				<div>Region TW</div>
				<div>Region ME</div>
				<div>Region Any (disabled)</div>      
    </div>
    <div class="reactions">
        <div class="reaction">🔼 1</div>
        <div class="reaction">✅ 1</div>
        <div class="reaction">❎ 1</div>
        <div class="reaction">🔽 1</div>
    </div>
</div>
<br>

Jetzt sendet Zoe eine neue Nachricht über das nächste Vorgehen. Lies dazu mehr in der nächsten Sektion.

**Du kannst jetzt _dieser Seite_ folgen (empfohlen), wenn du dir nicht sicher bist, was du willst und dir einen Überblick verschaffen willst, oder mit dem [Leitfaden für einen Server mit Freunden oder für ein Team](/en/Guides/Team-Server) oder dem [Leitfaden für einen Community-Server](/de/Guides/Community-Server) fortfahren, um differenzierte Listen zu sehen.**

<br>

# 1\. Daten hinzufügen (aka [Spieler](/de/terms/player) registrieren)
Um Zoe nutzen zu können musst du zuerst Spieler [registrieren](/de/commmands/player/register)/[erstellen](/de/commands/player/create). Ein [Spieler](/de/terms/player) besteht aus einem Discordkonto und einem oder mehreren Leaguekonten und wird in den verschiedenen [Features](/de/features) angezeigt.

**Es gibt zwei Möglichkeiten dies zu tun:**
1.  Du kannst sie selbst erstellen mit dem Befehl [`/create player`](/de/commands/player/create/) (erlaubt dir einen Spieler, also Discordkonto und Leaguekonto, für jemanden/jemand anderen zu erstellen).
2.  Auch kannst du in der Konfiguration aktivieren, dass sich jeder Benutzer deines Server selbst mit dem Befehl [`/register`](/de/commands/player/register) selbst einen Spieler erstellen kann. (Siehe mehr unter: [`/register`](/de/commands/player/register) und [`/config`](/de/commands/administrative/config)).
- Mit [`/add account`](/de/commands/player/addaccount) kannst du ein League of Legends Konto zu einem bereits registrierten/erstellten [Spieler](/de/terms/player) hinzufügen.
- Um einen [Spieler](/de/terms/player) zu löschen, verwende die Befehle [`/delete player`](/de/commands/player/delete) (lösche den Spieler) und [`/remove account`](/de/commands/player/removeaccount) (lösche das League-Konto eines Spielers).

> Du kannst dir alle registrierten [Spieler](/de/terms/player) anzeigen lassen mit dem Befehl [`/show players`](/de/commands/player/show-players).
>{.is-info}

<br>
  
# 2\. Spieler anzeigen (aka [Features](/de/features) benutzen)
>Du musst keine dieser Funktionen einrichten, dies ist nur eine Vorschlagsliste. Wenn du dir alle Funktionen ansehen möchtest, [ist hier ein Link zu allen Funktionen](/de/features) and [hier zu allen Befehlen](/de/commands/).
>{.is-info}

<br>

## Infokanal (schreibgeschützter Kanal empfohlen)
Der [Infokanal](/de/features/infochannel) enthält Statistiken zu [Spielern](/de/terms/player) sowie Statistiken zu laufenden Spielen.

![](/img/features/infopanel.jpg)
![](/img/features/gamecard.png)

- [Infokanal *Für mehr Informationen zum Infokanal klicke hier.*](/de/features/infochannel)
{.links-list}

<br>
  
## Rangkanal (schreibgeschützter Kanal empfohlen)
Der [Rangkanal](/de/features/rankchannel) ist der Kanal, in dem nach jedem Ranglistenspiel der registrierten [Spieler](/de/terms/player) eine Nachricht verschickt wird. Diese Nachrichten enthalten die Anzahl der gewonnenen oder verlorenen LP und einige Statistiken über die Leistung des [Spielers](/de/terms/player) im Spiel wie KDA, Dauer des Spiels und Itembuild.

![](/img/features/rankchannel_msg.png)

- [Rangkanal *Für mehr Informationen zum Rangkanal klicke hier.*](/de/features/rankchannel)
{.links-list}

<br>
  
## Clashkanal
Dieser Kanal sendet Statistiken über ein Konto in Bezug auf Clash. Er enthält Pläne für zukünftige Kämpfe in deiner Zeitzone sowie Statistiken über dein Team. Du kannst auch eine detaillierte Analyse des gegnerischen Teams mit Bannempfehlungen durchführen.

![](/img/commands/stats_teamanalysis_picks.png)

- [Clashkanal *Für mehr Informationen zum Clashkanal klicke hier.*](/de/features/clashchannel)
{.links-list}

<br>
  
## Leaderboards (ein eigener Kanal mit mehreren Leaderboards wird empfohlen)
Mit diesem Feature kannst du Leaderboards erstellen, die automatisch aktualisiert werden. Es stehen dir mehrere Arten zur Verfügung:

- Gesamtmeisterschaftspunkte
- **Meisterschaftspunkte auf einem Champion**
- Rang in einer Warteschlange (Solo/DuoQ, Flex, etc.)
- Bester Rang in der allen Warteschlange
- Durchschnittliche KDA
- Durchschnittliche KDA auf einem Champion
- Bester Champion ("OTP")
- Konto-Level

![](/img/features/leaderboard_championmastery.png)

  - [Leaderboards *Für mehr Informationen zu Leaderboards klicke hier.*](/de/features/leaderboards)
{.links-list}

<br>
  
## Automatisierte Discord-Rollen nach League-Rang
Du kannst mit Zoe ganz einfach ein automatisches Rollensystem einrichten. Die Rollen werden regelmäßig automatisch aktualisiert. Die Premium-Version dieses Features bietet mehr Optionen (Filter nach Serverregion, Anzeige jeder Division, volle Kontrolle über jede Rolle und mehr).

![](/img/features/rankroles.jpg)

- [Rangrollen *Für mehr Informationen zu Rangrollen klicke hier.*](/de/features/rankroles)
{.links-list}

<br>

Sobald deine Features korrekt eingerichtet sind, werden sie automatisch aktualisiert, sobald ein Spiel über die Discord-Präsenz der [registrierten Spieler](/de/terms/player) erkannt wird, mindestens jedoch einmal pro Stunde. Du kannst deinen Server auch mit dem Befehl [`/refresh`](/de/commands/basic/refresh) aktualisieren.

<br>  

# 3\. Anpassung der Features (denn jeder Server ist anders)
Um Zoe und seine verschiedenen Einstellungen zu verwalten, verwenden diesen Befehl: [`/config`](/de/commands/administrative/config). 
 Lese hier alles über die Konfiguration hier: [**Konfiguration**](/de/Zoe-Configuration/).

<br>
  
# 4\. Immer weiter (Wir hören niemals auf!)
Zoe hat viele weitere Funktionen. Du kannst dir alle Befehle ansehen, wenn du [HIER](/de/commands) klickst.
Ein Beispiel wäre [`/stats profile`](/de/commands/stats/profile), dass es dir erlaubt ein Profil eines Spielers anzusehen.

![](/img/commands/stats_profile.png)
<br>
  
# Einrichtung - Schlusswort
Zoe ist ein aktiv entwickelter Bot, der ein [<kbd>⭐ Premium Abbonement ⭐</kbd>](/de/support) zur Unterstützung seiner Entwicklung anbietet. Dieses Abonnement bietet einige zusätzliche Optionen, ist aber bei weitem nicht obligatorisch. 
Für weitere Informationen: [Unterstütze uns](/de/support), [Boosting](/de/Zoe-Points-And-Boosting), [`/subscription`](/de/commands/subscription/subscription) & [`/boost`](/de/commands/subscription/boost)
  
- [Befehle *Wenn du willst, kannst du dir die komplette Befehlsliste anschauen: `/help` oder klicke hier*](/de/commands)
- [Discord Server *Wenn du Probleme, Vorschläge oder Feedback für uns hast, komm hier her*](https://discord.gg/whc5PrC)
- [Einrichtung *Wenn du dir die Einrichtungsnachricht erneut anchauen willst nutze `/setup`*](/de/commands/administrative/setup)
{.links-list}