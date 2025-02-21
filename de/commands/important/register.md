---
title: /register- Befehl
description: Informationen über den Befehl /register
published: true
date: 2025-02-21T18:04:27.908Z
tags: register, registrierung, neu, neuer spieler, benutzer
editor: markdown
dateCreated: 2023-08-22T08:45:41.344Z
---

# /register region gamename tag
## Informationen
**Mit diesem Befehl können sich [Spieler](/de/terms/player) selbst zu Zoe hinzufügen. Dazu musst du die [`Region`](/de/terms/region), den [`Gametag und Tag (Riot ID)`](/de/terms/riotid) angeben. Dies funktioniert nur, wenn [die Option in der Konfiguration](/de/Zoe-Konfiguration/Benutzermanagement/Register) aktiviert ist ([`/config`](/de/commands/administrative/config)).**
<br>

### Erforderliche Berechtigungen:
>**Keine** - jeder Benutzer des Servers kann diesen Befehl nutzen (solang nicht weiter durch Berechtigungen eingeschränkt) {.is-success}

>**Konfiguration** - damit dieser Befehl verwendet werden kann, muss er zuvor in der Konfiguration aktiviert werden. {.is-info}

<br>

## Nutzung
<div class="discord-preview">
    <div class="dcp-chatbar">
        <img src="/zoe_logo.png" class="dcp-avatar">
        <span class="dcp-command">/register</span>
        <div class="dcp-args">
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
| `region` | :heavy_check_mark: | Der [regiontag](/de/terms/region) der [region](/de/terms/region), in der sich der Spieler befindet |
| `game-name` | :heavy_check_mark: | Der erste Teil der Spieler [Riot ID](/de/terms/riotid) |
| `tag` | :heavy_check_mark: | Der zweite Teil der Spieler [Riot ID](/de/terms/riotid) |
<br>

## Verwandte Befehle/Seiten:
-   [/create player](/de/commands/player/create/)
{.links-list}