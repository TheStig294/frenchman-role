# Frenchman Role for Custom Roles for TTT
**The "Frenchman" role for Custom Roles for TTT**\
The Frenchman is a member of the jester team that becomes temporarily invincible, and able to damage others when they take damage!\
\
On taking damage they are forced to use a baguette (a crowbar that one-hit kills and has longer range), and have 1 minute (by default) to kill everyone else to win! They automatically die after their time is up.


## ConVars
**ttt_frenchman_enabled** (Default 0)\
*Whether or not the Frenchman should spawn*\
\
**ttt_frenchman_adrenaline_rush** (Default 52)\
*The time in seconds the frenchmans adrenaline rush lasts for. Set to 0 to disable*\
\
**ttt_frenchman_adrenaline_baguette** (Default 1)\
*Whether the frenchman is forced to use a baguette when they activate*\
\
**ttt_frenchman_baguette_hit_distance** (Default 150)\
*How far the baguette can hit*\
\
**ttt_frenchman_baguette_hitbox_area** (Default 30)\
*AOE angle the baguette can hit players from the centre of the screen*\
\
**ttt_frenchman_adrenaline_baguette_damage** (Default 1000)\
*How much damage the baguette does per swing*\
\
**ttt_frenchman_hide_when_active** (Default 0)\
*Whether the frenchman is hidden from usual hud popups like the player name, health popup when you look at someone, or radar pings*\
\
**ttt_frenchman_starting_health** (Default 5)\
*The amount of health the Frenchman starts with*\
\
**ttt_frenchman_max_health** (Default 5)\
*The maximum amount of health the Frenchman can have*\
\
**ttt_frenchman_drain_health_to** (Default 0)\
*The amount of health to drain the frenchman down to. Set to 0 to disable*\
\
**ttt_frenchman_adrenaline_ramble** (Default 1)\
*Whether the frenchman makes a sound when they activate*\
\
**ttt_frenchman_spawn_weight** (Default 1)\
*The weight assigned to spawning the Frenchman*\
\
**ttt_frenchman_min_players** (Default 0)\
*The minimum number of players required to spawn the Frenchman*\
\
**ttt_frenchman_shop_sync** (Default 0)\
*Whether the Frenchman should have access to all detective shop items*\
\
**ttt_frenchman_credits_starting** (Default 1)\
*The number of credits the Frenchman should start with*\
\
**ttt_frenchman_shop_random_enabled** (Default 0)\
*Whether the Frenchman's shop contains a random selection of items it's assigned*\
\
**ttt_frenchman_shop_random_percent** (Default 100)\
*The percent chance that each weapon in the Frenchman's shop will not be shown*\
\
**ttt_frenchman_name** (Default Frenchman)\
*The name of the Frenchman role*\
\
**ttt_frenchman_name_plural** (Default Frenchmen)\
*The name of multiple Frenchmen roles*\
\
**ttt_frenchman_revoke_invincibility_when_only_baddies_left** (Default 0)\
*Whether the frenchman's invincibility is revoked when only non-innocent/detective players are still alive*


## You must enable the role for it to spawn!
If hosting a game from the main menu, put **ttt_frenchman_enabled 1** in your listenserver.cfg.\
(Normally at: C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod\cfg)\
\
If hosting a game from a dedicated server, put **ttt_frenchman_enabled 1** in your server.cfg.

## Credits
Credit goes to [Noxx](https://steamcommunity.com/id/noxxflame) and [Malivil](https://steamcommunity.com/id/malivil) for the code for making the frenchman activate, making Custom Roles itself, and external roles possible!

## Steam Workshop Link
https://steamcommunity.com/sharedfiles/filedetails/?id=2876412670
