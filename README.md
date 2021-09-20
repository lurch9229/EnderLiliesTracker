# EnderLiliesTracker
EmoTracker Package for Ender Lilies: Quietus of the Knights Randomizer.

This package contains a Map tracker, which features all the areas of the game, a world map variant, which has all locations on a single map, and 2 items only variants.

plans for the future include adding settings for each randomization option and an Entrance Randomization variant.

Logic for the Verboten domain that involves going through blight is currently set to needing mask, or having 3 priestess' wishes, spellbound anklet 150+hp (this includes health boosts from Soiled Prayer Beads and Royal Aegis Curio (not the unused health relic) and 5 relic slots, or having 150+hp, holy water, spellbound anklet and 6 relic slots along with movement needed to each check.

Logic to get through the Abyss Hell Run is set to needing 300+hp, spellbound anklet, ruined witches book, 3 wishes and 7 relic slots. this needs more vigorus testing so please let me know if you find over ways to get through gaunlet. Thanks.

Please address issues to this repository, or contact me on Discord Lurch9229#4849.
If you want to add logic changes via PR then please you this layout -

"access_rules": 
[
"$B1ACCESS,hook"
]

$B1ACCESS is the logic needed to reach the room, which can be found in the logic.lua.

PRs will be merged on a monthly basis, as to not bog down Emosaru with updates for the EmoTracker App.

I hope you enjoy using this tracker alongside your rando playthroughs. Good Luck, Have Fun everyone.
