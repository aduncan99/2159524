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

### Improvements:
* Added Next Wave button for debugging (work in progress)
* Added confirmation window to prevent accidental reloads or window exiting.
* Added wave 36 (which is kind of hard, god mode recommended)
* Changed font color to red so that it's easier to see
* Added enemy info to README.md
* Added notes.md for developer notes (TODO, FIXME, etc.)
* Added 'monkey' enemy
