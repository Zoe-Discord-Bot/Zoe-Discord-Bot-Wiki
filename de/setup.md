---
title: Zoe Einrichtung
description: Auf dieser Seite erfährst du, wie du Zoe auf deinem Discord-Server einrichten kannst.
published: true
date: 2023-05-19T13:40:06.868Z
tags: setup, einrichten, einrichtung, start
editor: markdown
dateCreated: 2021-08-16T13:05:23.601Z
---

# Zoe Discord Bot Einrichtung

### Hier findest du alles über Zoes Einrichtung.

Du möchtest Zoe auf deinem Server verwenden? So wird es gemacht! Es gibt auch eine Anleitung auf YouTube (auf Englisch) : [Click here!](https://youtu.be/QH1v9FTWj68)

Um Zoe einzurichten und zu nutzen, benötigst du die Berechtigung "Kanäle verwalten" auf deinem Server (falls du nicht ohnehin der Administrator bist).

## Zoe hinzufügen

Du kannst Zoe zu deinem Server hinzufügen, indem du auf der Homepage auf "Add the bot" klickst, auf Seiten wie top.gg oder bots.ondiscord.xyz und hier im Wiki unten links in der Menüleiste.

## Zoe authorisieren

Nun musst du dich ggf. bei Discord anmelden, dann den Server auswählen, dem du Zoe hinzufügen möchtest, und Zoes Berechtigungen bestätigen. Eventuell musst du noch ein Captcha lösen und dann kannst du loslegen.

![](/en-auth-zoe-1.png)

## Setup

Wenn Zoe zum ersten Mal hinzugefügt wird, sendet sie eine kurze Nachricht an den Standardkanal des Servers.

Dann folgt die erste Einstellung. Du solltest die Sprache auswählen, die Zoe auf deinem Server sprechen soll. (Für weitere Informationen siehe >language). Du kannst mit den Reaktionen navigieren und dann die Sprache bestätigen, die Zoe sprechen soll.

![](/en-auth-setup-1.png)

Direkt danach musst du die Standard League of Legends Serverregion auswählen. Verfügbar sind:

BR - Brasilien

EUNE - Europa Nordisch & Ost

EUW - Europa West

LAN - Lateinamerika Nord

LAS - Lateinamerika Süd

NA - Nordamerika

OCE - Ozeanien

RU - Russland

TR - Türkei

JP - Japan

KR - Republik Korea

Du kannst diese Einstellung später in der Konfiguration ändern, wenn du dies wünscht (siehe >config).

![](/en-auth-setup-region-1.png)

Jetzt sendet Zoe eine weitere Nachricht darüber, was als nächstes passiert. Mehr dazu im nächsten Abschnitt.

## Eine Informationstafel erstellen und Spieler hinzufügen

Jetzt können wir loslegen. Als erstes erstellst du einen Infokanal oder ein Infopanel, das sich in diesem Kanal befindet. Alle Spieler, die du jetzt anlegst, werden hier mit ihren Konten aufgelistet.

Verwende dazu den Befehl [`>create infoChannel nameOfTheChannel`](/en/commands/create/infoChannel/). Gib für `nameOfTheChannel` einen Namen für den gewünschten Kanal ein.

Zum Anlegen von Spielern benutze den Befehl [`>create player @DiscordMentionPlayer (Region) (SummonerName)`](/en/commands/create/player/) und zum Hinzufügen von Sekundärkontos[`>add accountToPlayer (Region) (SummonerName`](/en/commands/add/account/). Wenn die Option in der Konfiguration aktiviert ist, können sich Spieler auch mit dem Befehl [`>register`](/en/commands/important/register/) selbst hinzufügen.

Und schon kann's losgehen! Für die anderen Funktionen kannst du hier klicken: Kernfunktionen (noch nicht fertig)