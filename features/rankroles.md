---
title: Rank roles - Feature
description: Information about the automated rank roles.
published: true
date: 2024-05-02T13:00:20.296Z
tags: ranks, rank, role, roles, improved, improved rank roles, peak elo
editor: markdown
dateCreated: 2023-04-13T08:11:20.807Z
---

# Rank roles 

**Discord roles for users of a Discord server are a great thing. Zoe provides rank roles based on the rank of the connected League of Legends account for every [player](/en/terms/player) and updates them regularly. You can still customise these roles in their name, color and permissions after they have been created. Keep in mind that Zoe needs to have the permissions to assign them still.
If a role is deleted, the feature still works with the remaining roles (you can use this to show only a specific ranks if you wish).**

<br>

>There are two instances of rank roles. You need a premium server to access improved rank roles. Therefore, this page is divided into two parts. **If you want to learn more about improved rank roles click on the right tab**.
>{.is-info}

<br>

## Rank roles {.tabset}
### **Basic rank roles**
>This feature is available for all servers.
>{.is-success}

To activate rank roles use the command [`/config`](/en/commands/administrative/config) and select the option `Automated rank-role features` in the dropdown menu.
<img src="/basic_rankroles_1.png" width="40%"  />


In the next menu select Option :one:`Rank Role Feature`.
<img src="/basic_rankroles_2.png" width="40%"  />

If necessary, read the description and confirm the activation with :white_check_mark:and then select for which queues/modes the roles should count. Use the buttons to activate or deactivate the categories. You have the choice between Solo/DuoQ, Flex and TFT. Then confirm this selection with `Activate`.
![](/basic_rankroles_3-4.png)

This takes a short moment, because Zoe has to create a role for each League of Legends rank. After a refresh the roles are then assigned to all [registered players](/en/terms/player).
![](/basic_rankroles_6.png)

>To change your chosen queue configuration head back to the same config option and simply update it using the buttons. After that press `Update`.
>{.is-info}

### **Improved rank roles**
>This feature is only available for [boosted](/en/Zoe-Points-And-Boosting) servers.
>{.is-success}

To activate improved rank roles use the command [`/config`](/en/commands/administrative/config) and select the option `Automated rank-role features` in the dropdown menu.
<img src="/basic_rankroles_1.png" width="40%"  />

In the next menu select Option :two:`Rank Role Improved`.
<img src="/improved_rankroles_1.png" width="40%"  />

You can also assign the improved rank roles by **peak elo**. Choose :three:`Peak Elo Rank Role` in this menu. One more step is required for peak elo rank roles: select the season/split. 
<img src="/improved_rankroles_peakelo_1.png" width="40%"  />
<img src="/improved_rankroles_peakelo_2.png" width="80%"  />
After that the creation is the same as for improved rank roles.

If necessary, read the description and confirm the creation with `Continue to the settings` 
<img src="/improved_rankroles_2.png" width="70%"  />

Now for the settings. On the top of the message you can see the current configuration.
<img src="/improved_rankroles_settings_1.png" width="50%"  /> <br>
Right below that you can find examples of the roles that will be created.
<img src="/improved_rankroles_settings_2.png" width="50%"  /> <br>

On the bottom you can change the following settings with the **4 dropdown lists**: <br>
_**Rank scale** *(single selection)*_
- Every rank (Iron, Bronze, Silver,...)
- Every second division (Iron IV-III, Iron II-I, Bronze IV-III,...) 
- Or every division (Iron IV, Iron III, Iron II,...) 
<br>
_**Queue** *(multiple selection possible)*_
- Solo/Duo
- Flex
- TFT

_**Minimum rank** *(single selection)*_
Select the lowest rank to create here (for all ranks put Iron IV *(standard)*)

_**Maximum rank** *(single selection)*_
Select the highest rank to create here (for all ranks put Challenger *(standard)*)
<br>
**And with the 2 buttons at the end of the message the following settings can be made:** <br>
_**Server specific roles** *(Yes/No)*_
Yes: Creates every role for every [server region](/en/terms/region) (NA, EUNE, EUW, KR, etc.)
No (standard): All [server regions](/en/terms/region) are treated the same, no extra roles per [server region](/en/terms/region)
<br>
_**Queue specific roles** *(Yes/No)*_
Yes: Creates every role for every queue/gamemode (Solo/Duo, Flex and TFT)
No (standard): All queue/gamemodes are treated the same, no extra roles per queue/gamemodes
<img src="/improved_rankroles_settings_3.png" width="80%"  />
With the other buttons you can `Cancel the creation` and close the configuration or
`Continue to the next step` after you made all changes you wanted and finalize the improved rankroles.

>Please note that a discord server can hav a maximum of 250 slots for roles. Therefore its not possible to create a role for every division for every [server region](/en/terms/region) and queue/gamemode etc.
>{.is-warning}

With the next menu you can change, update oder delete every role seperately if you wish to do that. You can navigate up and down with the buttons. If you are finished or want to skip this step click on `Create the option with these settings`.
<img src="/improved_rankroles_4.png" width="80%"  />
Updating a role looks like this:
<img src="/improved_rankroles_edit.png" width="70%"  />

This takes a short moment, because Zoe has to create a role for each League of Legends rank or division etc.

<img src="/improved_rankroles_5.png" width="30%"  />

>To change your chosen  configuration head back to the same config option and simply update it using the buttons.
>{.is-info}