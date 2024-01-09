---
title: Rangrollen - Feature
description: Informationen über die automatisierten Rangrollen.
published: true
date: 2024-01-09T14:29:52.754Z
tags: rang, ränge, rolle, rollen, verbesserte, verbesserte rangrollen
editor: markdown
dateCreated: 2023-08-12T19:12:57.016Z
---

# Rangrollen

>**Discord-Rollen für Nutzer eines Discord-Servers sind eine tolle Sache. Zoe stellt Rangrollen basierend auf dem Rang des verbundenen League of Legends-Accounts für jeden Spieler zur Verfügung und aktualisiert diese regelmäßig. Du kannst diese Rollen noch in ihrem Namen, ihrer Farbe und ihren Berechtigungen anpassen, nachdem sie erstellt worden sind. Denke daran, dass Zoe die Berechtigungen haben muss, um sie noch zuzuweisen. <br>
> Wenn eine Rolle gelöscht wird, funktioniert das Feature weiterhin mit den verbleibenden Rollen (Du kannst dies nutzen, um nur bestimmte Ränge anzuzeigen, wenn du dies wünscht).**
>{.is-info}

>Es gibt zwei Instanzen von Rangrollen. Du benötigst einen Premium-Server, um Zugriff auf verbesserte Rangrollen zu erhalten. Daher ist diese Seite in zwei Teile unterteilt. **Wenn du mehr über verbesserte Rangrollen erfahren möchtest, klicke auf den rechten Reiter**.
>{.is-warning}

<br><br>

## Rangrollen {.tabset}
### **Einfache Rangrollen**
>Dieses Feature ist für alle Server verfügbar.
>{.is-success}

>Um Rangrollen zu aktivieren, verwende den Befehl [`/config`](/de/commands/important/config) und wähle die Option `Automatisierte Rank-Rollen-Funktionen` im Dropdownmenü.
<img src="/basic_rankroles_1.png" width="40%"  />
>{.is-info}

>Wähle im nächsten Menü Option :one:`Rangrollen Feature`.
<img src="/basic_rankroles_2.png" width="40%"  />
>{.is-info}

>Lese ggf. die Beschreibung und bestätige die Aktivierung mit :white_check_mark:und wähle dann aus, für welche Warteschlangen/Modi die Rollen gelten sollen. Verwende die Schaltflächen, um die Kategorien zu aktivieren oder zu deaktivieren. Du hast die Wahl zwischen Solo/DuoQ, Flex und TFT. Bestätige diese Auswahl anschließend mit `Aktivieren`.
![basic_rankroles_3-4.png](/basic_rankroles_3-4.png)
>{.is-info}

>Dies dauert einen kurzen Moment, da Zoe für jeden League of Legends-Rang eine Rolle erstellen muss. Nach einem Refresh werden die Rollen dann allen registrierten Spielern zugewiesen.
![basic_rankroles_6.png](/basic_rankroles_6.png)
>{.is-info}
---
>Um die gewählte Warteschlangenkonfiguration zu ändern, kehre zur gleichen Konfigurationsoption zurück und aktualisieren sie einfach mit den Schaltflächen. Danach drücke `Aktualisieren`.
>{.is-info}

### **Verbesserte Rangrollen**
>Diese Funktion ist nur verfügbar für [geboostete Server](http://wiki.zoe-discord-bot.ch/en/Zoe-Points-And-Boosting).
>{.is-success}

>Um verbesserte Rangrollen zu aktivieren, verwende den Befehl [`/config`](/en/commands/important/config) und wähle die Option `Automatisierte Rank-Rollen-Funktionen` im Dropdownmenü.
<img src="/basic_rankroles_1.png" width="40%"  />
>{.is-info}

>Wähle im nächsten Menü Option :two:`Verbesserte Rangrollen`.
<img src="/improved_rankroles_1.png" width="40%"  />
>{.is-info}

>Du kannst die verbesserten Rangrollen auch nach **Spitzen-Elo** zuordnen. Wähle :three:`Peak Elo Rangrollen` in diesem Menü. Für Rollen mit Spitzen-Elo-Rang ist ein weiterer Schritt erforderlich: die Auswahl der Saison/des Splits. 
<img src="/improved_rankroles_peakelo_1.png" width="40%"  />
<img src="/improved_rankroles_peakelo_2.png" width="80%"  />
Danach erfolgt die Erstellung auf die gleiche Weise wie bei verbesserten Rangrollen.
>{.is-warning}

>Lese ggf. die Beschreibung und bestätige die Erstellung mit "Weiter zu den Einstellungen". 
<img src="/improved_rankroles_2.png" width="70%"  />
>{.is-info}

>### Nun zu den Einstellungen. Oben in der Nachricht siehst dz die aktuelle Konfiguration.
><img src="/improved_rankroles_settings_1.png" width="50%"  /> <br>
>### Direkt darunter findest du Beispiele für die Rollen, die erstellt werden sollen.
><img src="/improved_rankroles_settings_2.png" width="50%"  /> <br>
>{.is-info}

> ### Im unteren Bereich kannst du über die **4 Dropdown-Listen** folgenden Einstellungen vornehmen: <br>
>_**Rangskala** *(Einfachauswahl)*_
>Jeder Rang (Eisen, Bronze, Silber,...)
>Jede zweite Division (Eisen IV-III, Eisen II-I, Bronze IV-III,...) 
>Oder jede Division (Eisen IV, Eisen III, Eisen II,...) 
><br>
>_**Warteschlange** *(Mehrfachauswähl möglich)*_
>Solo/Duo
>Flex
>TFT
><br>
>_**Minimum Rang** *(Einfachauswahl)*_
>Wähle hier den niedrigsten zu erstellenden Rang (für alle Ränge gib Eisen IV *(Standard)* ein)
><br>
>_**Maximum Rang** *(Einfachauswahl)*_
>Wähle hier den höchsten zu erstellenden Rang (für alle Ränge gib Herausforderer *(Standard)* ein)
><br>
> ### Und mit den **2 Schaltflächen** am Ende der Nachricht können die folgenden Einstellungen vorgenommen werden: <br>
>_**Server spezifische Rollen** *(Ja/Nein)*_
>Ja: Erstellt jede Rolle für jede Serverregion (NA, EUNE, EUW, KR, etc.)
>Nein (standard): Alle Serverregionen werden gleich behandelt, keine zusätzlichen Rollen pro Serverregion
><br>
>_**Warteschlange spezifische Rollen** *(Ja/Nein)*_
>Ja: Erzeugt jede Rolle für jede Warteschlange/Spielmodus (Solo/Duo, Flex und TFT)
>Nein (standard): Alle Warteschlangen/Gamemodi werden gleich behandelt, keine zusätzlichen Rollen pro Warteschlange/Spielmodus
><img src="/improved_rankroles_settings_3.png" width="80%"  />
>Mit den anderen Schaltflächen kannst du die `Erstellung abbrechen` und die Konfiguration schließen oder
>`Weiter mit dem nächsten Schritt` nachdem du alle gewünschten Änderungen vorgenommen hast, und schließe die verbesserten Rangrollen ab.
>{.is-info}

>Bitte beachte, dass ein Discord-Server maximal 250 Slots für Rollen haben kann. Daher ist es nicht möglich, eine Rolle für jede Division für jede Serverregion und Warteschlange/Spielmodus usw. zu erstellen.
>{.is-danger}

> Im nächsten Menü kannst du jede Rolle einzeln ändern, aktualisieren oder löschen, wenn du dies wünscht. Du kannst mit den Schaltflächen nach oben und unten navigieren. Wenn du fertig bist oder diesen Schritt überspringen willst, klicke auf `Option mit diesen Einstellungen erstellen`.
><img src="/improved_rankroles_4.png" width="80%"  />
>Das Aktualisieren einer Rolle sieht folgendermaßen aus:
><img src="/improved_rankroles_edit.png" width="70%"  />
>{.is-info}

>Das dauert einen kurzen Moment, denn Zoe muss für jeden League of Legends-Rang, jede Division usw. eine Rolle erstellen.
><img src="/improved_rankroles_5.png" width="30%"  />
>{.is-info}
---
>Um die gewählte Konfiguration zu ändern, kehre zur gleichen Konfigurationsoption zurück und aktualisiere sie einfach mit den Schaltflächen. 
>{.is-info}
