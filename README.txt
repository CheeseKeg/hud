Minetest mod "Better HUD"
=========================
version: 0.2.3 Beta

License of source code: WTFPL
-----------------------------
- "Disable Drowning" [no_drowning], PilzAdam

everything else:
(c) Copyright BlockMen (2013)


License of textures:
--------------------
hud_heart_fg.png - celeron55 (CC BY-SA 3.0), modified by BlockMen
hud_heart_bg.png - celeron55 (CC BY-SA 3.0), modified by BlockMen
hud_hunger_fg.png - PilzAdam(WTFPL), modified by BlockMen
hud_hunger_bg.png - PilzAdam(WTFPL), modified by BlockMen
wieldhand.png (from character.png) - Jordach (CC BY-SA 3.0), modified by BlockMen

everything else is WTFPL:
(c) Copyright BlockMen (2013)

This program is free software. It comes without any warranty, to
the extent permitted by applicable law. You can redistribute it
and/or modify it under the terms of the Do What The Fuck You Want
To Public License, Version 2, as published by Sam Hocevar. See
http://sam.zoy.org/wtfpl/COPYING for more details.


Using the mod:
--------------

This mod changes the HUD of Minetest. It adds a costum crosshair, a improved health bar. 
Also it adds hunger to the game and and hunger bar to the HUD.

Furthermore it disables the current way of drowning (credits go to PilzAdam) and it will have an LUA-based drowing next versions.


You can create a "hud.conf" to costumize the positions of health and hunger bar. Take a look at "hud.conf.example" to get more infos.

Hunger:
This mod adds hunger to the game. You can disable this by setting "HUD_HUNGER_ENABLE = false" in "hud.conf".

Currently supported food:
- Apples (default)
- Bread (default)
- Drawves (beer and such)
- Mooretrees
- Simple mobs
- Animalmaterials (mobf modpack)
- Fishing
- Glooptest

One apple fills up the hunger bar by 1 bread, 1 bread (from farming) 2 breads in bar.
