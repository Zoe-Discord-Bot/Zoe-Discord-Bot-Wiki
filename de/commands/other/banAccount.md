---
title: /banaccount - Befehl
description: Lerne wie du deinen Account von Zoe entfernen kannst.
published: true
date: 2025-02-21T20:38:16.421Z
tags: account, ban, banaccount
editor: markdown
dateCreated: 2024-01-09T14:16:29.089Z
---

# /banaccount
## Informationen
**Dieser Befehl startet den Bannlisten-Assistenten. Dies ermöglicht es dir (einem Kontobesitzer), sein Konto von anderen Servern zu löschen und es zur Verbotsliste hinzuzufügen, um es für andere unmöglich zu machen, es hinzuzufügen, und es vollständig von Zoe zu entfernen.**

### Erforderliche Berechtigungen:
>**Keine** - jeder Benutzer des Servers kann diesen Befehl nutzen (solang nicht weiter durch Berechtigungen eingeschränkt) {.is-success}

>**Kontoinhaberschaft** - dieser Befehl erfordert die Überprüfung des Besitzes eines League-Kontos (nicht discordbezogen) {.is-info}

<br>

## Nutzung
###### :one: Befehl
Beginne damit, den Befehl wie unten aufgeführt auszuführen und füge deine passenden Details für die [Region](/de/terms/region), [Gamename und Tag](/de/terms/riotid):
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/banaccount</span>
        <div class="dcp-args">
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">region</span>
                <span class="dcp-arg-value">EUW</span>
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">game-name</span>
                <span class="dcp-arg-value">Star Guardian Ez</span>
            </div>
          <div class="dcp-arg">
                <span class="dcp-arg-label">tag</span>
                <span class="dcp-arg-value">real</span>
            </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Argumente
| Argument | Notwendig | Beschreibung |
|----------|----------|-------------|
| `region` | :heavy_check_mark: | Der [Regiontag](/de/terms/region) der [Region](/de/terms/region) in dem der Spieler ist |
| `game-name` | :heavy_check_mark: | Der erste Teil der  [Spieler](/de/terms/player) [Riot ID](/de/terms/riotid) |
| `tag` | :heavy_check_mark: | Der zweite Teil der [Spieler](/de/terms/player) [Riot ID](/de/terms/riotid) |
<br>

###### :two: Verifikation
Danach siehst du die Bestätigungsnachricht mit einem Beschwörersymbol, das du für das zuvor angegebene Konto einstellen musst.
![](/img/commands/verification_promt.png)
<br>

###### :three: Öffne den Spielclient
Öffne den League of Legends-Client und logge dich ein, falls nötig. Klicke auf Dein Profil und das Beschwörersymbol, um es zu ändern.
![](/img/commands/client_profile.png)
<br>

###### :four: Wähle das Symbol aus
Blättere bis zum Ende der Symbolliste, wähle das eingebettete Symbol aus und verlasse die Symbolauswahl, um das neue Symbol zu speichern.
![](/img/commands/client_icons.png)
<br>

###### :five: Bestätige die Verifikation
Nachdem das Symbol geändert wurde, klicke auf „Fertig“, um zu bestätigen, dass du der Besitzer des Kontos bist. Die nächste Nachricht enthält eine Liste mit allen Servern, auf denen Dein Konto hinzugefügt wurde. Mit dem entsprechenden Servernamen, wenn Du ein Mitglied bist, sonst mit der Server-ID.
![](/img/commands/banaccount_servers.png)
<br>

###### :six: Fahre fort
Nun kannst du die folgenden Dinge tun: <br>

## Befehle {.tabset}
### Entferne dein Konto von einem Server
Beispiel:
<div class="discord-preview">
    <div class="dcp-chatbar">
                <span class="dcp-mention">@Zoe</span>&nbsp;kick 3
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

>**Entfernt dein Konto** von dem ausgewählten Server (hier ID 3). {.is-success}

>Dies **verhindert nicht das Hinzufügen** von diesem Konto {.is-danger}

### Entferne dein Konto von allen Servern
Beispiel:
<div class="discord-preview">
    <div class="dcp-chatbar">
                <span class="dcp-mention">@Zoe</span>&nbsp;kick all
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

>**Entfernt dein Konto** von allen Servern. {.is-success}

>Dies **verhindert nicht das Hinzufügen** von diesem Konto {.is-danger}

### Verhindern des Hinzufügen deines Kontos
Beispiel:
<div class="discord-preview">
    <div class="dcp-chatbar">
                <span class="dcp-mention">@Zoe</span>&nbsp;ban
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>
 
>**Verhindert das Hinzufügen** deines Kontos zu jeden Server. {.is-success}

>Dein Konto **wird nicht von Servern entfernt** auf denen es hinzugefügt ist. {.is-danger}

## Wie entfernst du dein Konto komplett?
Wenn du dein Konto komplett von Zoe entfernen willst nutze die folgenden Befehle:
- [x] `@Zoe ban` - um das Hinzufügen des Kontos zu verhindern
- [x] `@Zoe kick all` - um das Konto von allen Servern zu entfernen, auf denen es hinzugefügt ist 