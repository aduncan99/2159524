# towerdefense
This is an improved version of rsaihe's tower defense game. You can play the original
[here](https://rsaihe.github.io/towerdefense/).

You can also make and edit custom maps using this
[map editor](https://rsaihe.github.io/td-editor/). Instructions are located on
the Github [repo](https://github.com/rsaihe/td-editor/).

### Controls:
* Esc to deselect tower
* Left and right brackets to change map size (will reset game!)
* Mouse to place a tower
* Spacebar to pause
* 0-9 to select a tower to place
* F to toggle FPS display
* G to toggle god mode
* H to toggle displaying enemy health bars
* M to import and load map string (will reset game!)
* P to toggle display particle effects (turning them off helps with lag)
* Q to toggle towers firing
* R to reset game
* S to sell selected tower
* U to upgrade selected tower
* V to mute sound volume
* W to toggle delay between waves
* X to export map string (copies to clipboard)
* Z to return to default zoom level (will reset game!)

### Enemies:
* Weak, cash 1, health 35
* strong, cash 1, health 75
* fast, cash 2, health 75, speed 2
* strongFast, cash 2, health 135, speed 2
* medic, cash 4, health 375, immune regen
* stronger, cash 4, health 375
* faster, cash 4, health 375, resistant explosion, speed 3
* tank, cash 4, health 750, immune poison slow, resistant energy physical, weak explosion piercing
* taunt, cash 8, health 1500, immune poison slow, resistant energy physical
* spawner, cash 10, health 1150, ability spawn
* monkey, cash 2, health 20, speed 3, resistant energy explosion piercing
* armorMonkey, cash 4, health 1300, speed 3, resistant explosion energy 

### Improvements:
* Added confirmation window to prevent accidental reloads or window/tab exiting.
* Changed font color to red so that it's easier to see
* Added enemy info to README.md
* Added notes.md for developer notes (TODO, FIXME, etc.)
* Added 'monkey' enemy
* Added 'armorMonkey' enemy
* Added Minigun Tower (gun --> machine gun --> minigun)
* Added Fallout Tower (slow --> poison --> fallout)

### Maps:
* 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
