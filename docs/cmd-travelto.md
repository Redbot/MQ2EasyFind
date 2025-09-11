---
tags:
  - command
---

# /travelto

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/travelto [zonename] [@ easyfind command]
/travelto group [command]
/travelto activate | stop | dump
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Find a route to the specified `[zonename]` (short or long name) and then follow it.
<!--cmd-desc-end-->

## Options

**`(no option)`**
:   Display help text

**`[zonename]`**
:   Find a route to the specified `[zonename]` (short or long name) and then follow it.

**`[zonename] @ [easyfind command]`**
:   Upon arrival in `[zonename]`, execute `[easyfind command]`  
    e.g. `/travelto poknowledge @ Dogle Pitt`

**`group [command]`**
:   Broadcasts the command to the group, using the configured group plugin.

**`activate`**
:   If an existing zone path is active (created by the zone guide), activate that path with `/travelto`.

**`stop`**
:   Stops an active `/travelto`.

**`dump`**
:   Dumps zone information from the zone guide to `resources/ZoneGuide.yaml`.
