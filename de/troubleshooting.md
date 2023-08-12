---
title: Zoe Fehlersuche
description: Mit Hilfe dieses Schemas kannst du selbst kleinere Fehler beheben.
published: true
date: 2023-08-12T12:15:30.198Z
tags: troubleshooting, fehlersuche, fehler, suche
editor: markdown
dateCreated: 2023-08-12T12:15:30.198Z
---

# Fehlersuche

> *Zoe reagiert nicht auf meine Befehle und aktualisiert weder die Infotafel noch Ränge und sendet keine Spielkarten, Rangkanal- oder Spielverlauf-Kanal-Nachrichten. Was ist los mit Zoe?*
> **Hier ist, was du jetzt überprüfen kannst!**

<br>

## 1. Discord Status überprüfen
> Prüfe zunächst Zoes Discord-Status. Wenn er nicht grün (online), sondern rot (nicht stören) oder ausgegraut (offline) ist, liegt das höchstwahrscheinlich daran, dass ein Update auf eine neuere Version im Gange ist oder wir ein Problem untersuchen.
> >🟢 **Online:** Zoe ist funktionell
> >🔴 **Bitte nicht stören:** Zoe stoppt/startet neu
> >⚫ **Offline:** Zoe ist derzeit wegen einer Aktualisierung oder eines Problems offline
><pr>
>
> Für weitere Informationen kannst du den Ankündigungskanal auf unserem Discord-Server besuchen. Eine Einladung findest du unten links.
>{.is-info}
  
<br>
  
## 2. Berechtigungen überprüfen
>Überprüfe als zweites Zoes Rolle, um festzustellen, ob du ihr alle erforderlichen Berechtigungen erteilt hast. Du musst auch die Berechtigungen in deinem Befehlskanal und in dem Zielkanal (z. B. für Bestenlisten) überprüfen, um sicherzustellen, dass es keine Überschreibungen gibt. <br>
> **Erforderliche Berechtigungen sind:**
>`MANAGE_CHANNELS` -  Ermöglicht die Verwaltung und Bearbeitung von Kanälen
>`VIEW_CHANNELS` - Ermöglicht die Ansicht eines Kanals, was das Lesen von Nachrichten in Textkanälen einschließt
>
>`MANAGE_MESSAGES` - Ermöglicht das Löschen von Nachrichten
>`SEND_MESSAGES` - Ermöglicht das Senden von Nachrichten in einem Kanal
>`READ_MESSAGE_HISTORY` - Ermöglicht das Lesen des Nachrichtenverlaufs
>
>`ATTACH_FILES` - Ermöglicht das Hochladen von Bildern und Dateien
>`ADD_REACTIONS` - Ermöglicht das Hinzufügen von Reaktionen zu Nachrichten
>`USE_EXTERNAL_EMOJIS` - Erlaubt die Verwendung von benutzerdefinierten Emojis von anderen Servern
>`EMBED_LINKS` - Links, die von Benutzern mit dieser Berechtigung gesendet werden, werden automatisch eingebettet
>
>`MANAGE_GUILD_EXPRESSIONS` - Ermöglicht die Verwaltung und Bearbeitung von Emojis
>`MANAGE_ROLES` - Ermöglicht die Verwaltung und Bearbeitung von Rollen
>`USE_APPLICATION_COMMANDS` - Allows to use application commands, slash commands and context menu commandsErmöglicht die Verwendung von Anwendungsbefehlen, Schrägstrichbefehlen und Kontextmenübefehlen
>
> > Wenn die Rollen bei dir nicht funktionieren, überprüfe auch, ob Zoe in den Servereinstellungen über allen anderen Rollen steht.{.is-warning}
>
>{.is-info}
  
## 3. Zusätzliche Informationen
> ### Discord Presence Problem
>Wenn du **über Discord streamst** oder ein **Aufnahme-/Clip-Programm** benutzt, das die Discord-Präsenz ändert (wie MedalTV oder ähnliches), kann Zoe das aktuelle Spiel nicht wahrnehmen und wird keine Spielkarte senden oder die Infotafel aktualisieren.
Bitte **beenden deinen Stream oder schalte die Discord-Präsenz des Programms aus**, so dass `Spielt League of Legends` sichtbar ist, nur dann erhältst du alle Informationen direkt, da die passive Aktualisierung etwas länger dauert.
>{.is-info}  
  
> ### Schrägstrich-Befehl Problem
>Wenn die Schrägstrich-Befehle bei dir nicht funktionieren, überprüfe zunächst, ob Zoe die Berechtigung `USE_APPLICATION_COMMANDS` hat. Wenn Zoe diese Berechtigung hat und es trotzdem nicht funktioniert, liegt es wahrscheinlich daran, dass du Zoe über einen veralteten Link eingeladen hast, bei dem die Option "application.commands" nicht aktiviert war. Dies muss vom Entwickler beim Einladen von Zoe geschehen und wurde bei allen neuen Einladungslinks durchgeführt. 
Um das Problem zu beheben, kannst du Zoe vom Server entfernen und mit dem neuen und korrekten Einladungslink erneut einladen. 
> > Keine Sorge, deine Konfiguration bleibt gespeichert. {.is-warning} 
>
>{.is-info}

<br>
  
## Funktioniert es immer noch nicht?
>Wenn es dann immer noch nicht funktioniert, stelle bitte deine Frage / teile uns dein Problem in einem Support-Post auf dem Zoe-Discord-Server mit. Eine Einladung findest du unten links.
>{.is-success}
