---
title: /create player - Befehl
description: Lerne mehr über den /create player Befehl.
published: true
date: 2025-02-21T18:13:24.627Z
tags: create, player, spieler, erstellung, erstellen
editor: markdown
dateCreated: 2023-09-18T09:25:00.382Z
---

# /create player @DiscordUser region gamename tag
## Informationen
**Dieser Befehl wird verwendet, um einen Spieler zu erstellen.  Dazu musst Du die entsprechenden Daten für `@DiscordUser`, [`Region`](/de/terms/region), [`Gamename und Tag (Riot ID)`](/de/terms/riotid) eingeben, um einen League of Legends Account mit einem Mitglied Deines Discord-Servers zu verknüpfen. Du kannst alle Server-Regionen-Tags hier finden: [Regionen](/de/terms/region)**

**Dieser Befehl ist für Administratoren gedacht, die das Konto für ihre Spieler erstellen wollen.**
<br>

### Erforderliche Berechtigungen:
>**Kanäle verwalten** - nur Benutzer mit dieser Berechtigung („Moderatoren“/„Administratoren“) können diesen Befehl verwenden, da er Zoe für den Server tiefergehend beeinflusst {.is-warning}

<br>

## Nutzung
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/create player</span>
        <div class="dcp-args">
            <div class="dcp-arg">
                <span class="dcp-arg-label">user</span>
                <span class="dcp-arg-value">
              	<span class="dcp-mention">@timfernix</span>
              </span>
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
        </div>
        <button class="dcp-send-btn">&#10148;</button> 
    </div>
</div>

###### Argumente
| Argument | Notwendig | Beschreibung |
|----------|----------|-------------|
| `user` | :heavy_check_mark: | Die Discord-Erwähnung des [Spielers](/de/terms/player) den du erstellen willst |
| `region` | :heavy_check_mark: | Der [regiontag](/de/terms/region) der [region](/de/terms/region), in der sich der Spieler befindet |
| `game-name` | :heavy_check_mark: | Der erste Teil der Spieler [Riot ID](/de/terms/riotid) |
| `tag` | :heavy_check_mark: | Der zweite Teil der Spieler [Riot ID](/de/terms/riotid) |
<br>

## Verwandte Befehle/Seiten:
-   [/delete player](/de/commands/player/delete/)
{.links-list}