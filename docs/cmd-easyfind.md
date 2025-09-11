---
tags:
  - command
---

# /easyfind

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/easyfind [search term] | nav [nav command] | group [command]
/easyfind stop | ui
/easyfind reload [<filename>] | reloadsettings | migrate | help
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Finding locations in the current zone.
<!--cmd-desc-end-->

## Options

**`(no option)`**
:   Shows help text

**`[search term]`**
:   Searches the Find window for the given `[search term]`, either exact or partial match. If found, begins navigation. `[search term]` may also be a zone shortname. In this case, the closest zone connection matching for that zone will be found.

**`group [command]`**
:   Broadcasts the command to the group, using the configured group plugin. e.g EasyFind.yaml could have the following configured - GroupPlugin: eqbc

**`stop`**
:   Stops an active EasyFind.

**`reload [<filename>]`**   
:   Reload zone connections. Providing a filename after reload will load an alternate ZoneConnections.yaml file, so long as it's in your `\Resources\EasyFind` folder.

**`reloadsettings`**
:   Reloads settings from the config file

**`ui`**
:   Toggle EasyFind ui

**`migrate`**
:   Migrate MQ2EasyFind.ini from old MQ2EasyFind to new format (yaml config file)

**`nav [nav command]`**
:   Find using a nav command of Find window

## Examples

- `/easyfind reload ZoneConnections_Emu.yaml`  
  Loads an alternate Zone connection file called ZoneConnections_Emu.yaml
