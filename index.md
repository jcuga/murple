Work in Progress.  Play the demo (first 5 levels):
* [Murple-DEMO.bin][1]

[1]:/murple/download/Murple-DEMO.bin

![Screenshot Level 1](/murple/assets/img/screenshot-l1.png)

# Murple - Atari 2600 Game
![Merve](/murple/assets/img/merve.png)

You are `Merve`, a dedicated employee of the `Intergalactic Crayon Corporation` working diligently at the main factory on planet `Merph`.  Your job is to color batches of blank crayons so they can be shipped off to all of the girls and boys in the galaxy.

## Gameplay
Colored droplets will fall from the top of the screen, one at a time.  You have to color all of the crayons by steering the droplets into them.

Crayons start off blank.

![Blank Crayon](/murple/assets/img/crayon-blank.png)

One drop will half-color them.

![Half Colored Crayon](/murple/assets/img/crayon-half.png)

A second drop will complete them.

![Fully Colored Crayon](/murple/assets/img/crayon-full.png)

Be careful not to hit any finished crayons with a third droplet, or they will turn murple colored!

![Murple Crayon](/murple/assets/img/crayon-murple.png)

Once all of the crayons on screen are fully colored (or murpled), they will be tallied and another row of blank crayons will appear.  You win the level when the crayon color quota has been met.  The current supply and quota are displayed at the bottom of the screen.  The vertical line is the target/goal amount.

![Color bars and goal line](/murple/assets/img/color-bars.png)

At the bottom of the screen are drains that you can steer the droplets into to recycle them if not needed.

![Drain example](/murple/assets/img/drain-ex.png)

If you accidentally color a crayon the wrong color--or turn some murple--don't worry, just keep playing.  When the current round of crayons are fully filled in, they will be tallied and a new rows of blank crayons will appear.

If you think that you have colored in all six crayons but play continues, look again.  You probably have a half-colored crayon out there still.  The crayons are full when they have the two vertical black lines on them (right image), whereas half-filled crayons are half-checkered (left image):

![Half versus Full Crayons](/murple/assets/img/half-versus-full.png)

### Color Combinations
* Two of any primary color (`red`, `yellow`, `blue`) make themselves.
* `red` and `blue` make `purple`.
* `yellow` plus `blue` make `green`.
* `yellow` plus `red` make `orange`.

## Controls
* Move color drops `left` & `right` with the `Joystick`.
* Hold `up` to fall more slowly.
* Hold `down` to fall faster.
* `Fire` button is used for menu selection/continue and to un-pause.
* Pause the game with the `Color/BW` Switch, hit `Fire` to un-pause.

## What is murple? And other Dangers...
![Overflowed Murple](/murple/assets/img/screenshot-lose-game.png)

`Murple` is a toxic byproduct of the crayon making process.  It forms when too much crayon color ink is mashed together.  It collects at the bottom of the factory floor in a large vat.

![Murple Vat](/murple/assets/img/murple-vat.png)

If you over-color a crayon, or hit the wall with your color droplet, more `murple` will collect in the vat.  If the vat overflows, you lose!

### Over Production
Be sure not to make too much of any single color.  Your goal is the vertical line.  If you make so much that one of the inventory lines touch the murple vat, you lose!

![Getting to be too much](/murple/assets/img/too-much-1.png)

![Too much you lose](/murple/assets/img/too-much-2.png)

### Continue after Losing
If you lose, you can still opt to keep playing from the current level, but your score will be reset to zero.

### Reducing Murple Damage
Any time you complete a row of crayons, the amount of murple in the vat will go down.  If you complete a perfect row (one of every color) the murple reduction will be even greater.


## Aids and Obstacles
As you advance through the levels, you'll encounter:

### Double Droplets
![Double Droplet](/murple/assets/img/double-drop.png)

These droplets are used twice.  Hitting a crayon will turn a double-droplet into a single droplet.  Plan ahead for where you're moving next after your current crayon target.

The frequency of double-droplets will vary by level.

### Trampolines
![Trampoline](/murple/assets/img/trampoline.png)

Normally, you are always falling down.  Hit a trampoline and you will reverse direction.  This will help you reach otherwise impossible locations.

Trampolines will cycle to different positions as you hit them.  They reset to the start when a new droplet enters from above.

### Toggle Switches
![Toggle Switch](/murple/assets/img/toggle-switch.png)

You can hit these to toggle parts of the playfield on/off.  They can open/close doors to make certain parts of the level accessible.

### Color Changing Pellet
Rainbow colored squares.  Hit these to change the color of your droplet.

### Moving Obstacles
These look like color changing pellets, but are the same color as the playfield, and moving.  Avoid hitting these as they'll pop your droplet and you'll take damage.

### Coloring a Perfect Round
A `perfect round` is when you complete coloring all 6 crayons on screen, each with a unique color (red, yellow, blue, orange, purple, green).

![Example Perfect Round](/murple/assets/img/perfect-round.png)

There are several benefits to coloring a perfect round--and this should always be your goal when possible:

* You receive an extra `500` points.
* You receive a bonus column of inventory--an extra crayon of every color.  But if you are near the goal line, the bonus inventory will not be applied to any colors that would otherwise exceed the goal, thus avoiding any overstock score penalty.
* The game plays an extra tune `:)`
* An observant reader may ask "but if I get an extra column of inventory, doesn't that mean I have less opportunity to score points?"  Great question!  The answer is: yes, you don't have to color in as many crayons, but No: the `500` is worth more than a full set of crayons (`300`), so you still come out ahead.


## Difficulty
At the start of the game, players can select from `easy`, `medium`, and `hard`.

![Select Difficulty](/murple/assets/img/difficulty-select.png)

The easier difficulties mean slower movement and a smaller number of crayons required to advance to the next level.  Harder difficulties move more quickly and require more crayons to be completed.  Damage is more severe on harder difficutly as well.

Use the `left difficulty switch` to control long/short game mode.

* `B` left difficulty is for shorter games by giving the player an extra 2 completed crayons of every color.
* `A` left difficulty is for longer games as the player needs to complete more crayons of every color to advance.

Note that the longer game mode / harder difficulty mean a higher maximum possible score.

## Scoring
| Action | Score Amount |
|--------|---------------
| Fully color a Crayon | `10` |
| Tally a completed Crayon in the inventory | `40` |
| Complete a perfect round (one of each color)  | `500` |
| Complete a Level (Easy/Medium difficulty) | `1000` |
| Complete a Level (Hard difficulty) | `2000` |

Note that you get an extra bonus on Hard difficulty, and that the number of crayons required to complete a level vary, thus the maxium possible score varies.  Also note that there are a total of `15` levels.

A perfect score for a level is acheived by filling in crayons perfectly--one of every color, every time.  Thus getting the perfect round bonus (`+500`).  Also, you have to not have any excess murple or inventory left over, as they result in reduced points at the end of the level.  Completing a round of crayons will award a small murple/damage reduction.  Completing a perfect round will award an even bigger reduction.

### Maximum Score Per Game Mode
| Difficulty | Left Difficulty Switch | Crayons Per Level | Max Possible Score |
|---|---|---|----|
| `Easy` | `B` | `6` of each color | `51,000` |
| `Easy` | `A` | `8` of each color | `63,000` |
| `Medium` | `B` | `7` of each color | `63,000` |
| `Medium` | `A` | `9` of each color | `75,000` |
| `Hard` | `B` | `8` of each color | `78,000` |
| `Hard` | `A` | `10` of each color | `90,000` |

### Score Penalties
When you complete a level, you will receive a level bonus (`1000`, or `2000` on hard difficulty).  But you will also lose points for any extra murple in the vat (up to ~`-200` if the vat is really full), and for any "overstock" manufactured crayons.  Meaning, any finished crayon colors that pass the goal line will result in a score penalty.  The penalty is `-250` points per *column* of overstock. 

* **TIP:** it is better to overstock crayons of different colors than by a bunch of the same color.  The penalty is per column, so for example, you recieve a bigger penalty for having 3 extra green crayons past the goal line than having 5 extra crayons, each of a different color.  So when you are trying to finish the last round of crayons to beat a level, and you have an uneven amount of inventory, try and "spread out" which colors are over the line versus a single line growing too long.

## Tips & Tricks
* Hold `Up` while moving--in harder difficulties and later levels, this is required to make it through tight turns!
* If you don't have a use for the current color, move the droplet to one of the bottom exits to recyle it.
* It's better to recycle some colors to wait for the right one and achieve a perfect round (one crayon of every color).
* You can complete levels faster--and score more points--by coloring in a perfect round--you get an extra crayon of every color and a score bonus for each perfect round.
* If the murple vat is almost full and you are about to lose, try to clear the current round of crayons as clearing a round will result in a damage reduction/vat level lowering.
* Don't be too lopsided in the color of crayons!  If the inventory line at the bottom grows too far, it will tip over the murple vat and you'll lose!
* If you have a double-droplet, plan ahead! If you are aiming for a certain crayon, is there a path for the remaining drop to still be used without hitting the wall?  Look for trampolines and toggle-switches to get you out of trouble.
* If your color amounts collected so far are not even (color lines are different lengths at the bottom), you should still try and color in perfect rounds (one crayon of every color).  This is for two reasons:  First, you will receive an extra crayon of every color.  Second: when awarding extra crayons, you won't receive any that would make you exceed the goal line.  So the best approach is to aim for perfect rounds to double up on supply that will "even out" at the end if you previously had uneven amounts colored in.

## Screenshots

![Screenshot Level 2](/murple/assets/img/screenshot-l2.png)

![Screenshot Level 3](/murple/assets/img/screenshot-l3.png)

![Screenshot Level 4](/murple/assets/img/screenshot-l4.png)


## Credits
Game and concept by `Justin Cuga`, 2025.

Written in `Batari Basic` (with some `asm`) using the `DPC+ kernel`.

Very little ROM was wasted in this process:
```
    20 bytes of ROM space left in bank 1
    24 bytes of ROM space left in bank 2
    86 bytes of ROM space left in bank 3
    1 bytes of ROM space left in bank 4
    1 bytes of ROM space left in bank 5
    24 bytes of ROM space left in bank 6
```
(all 15 levels are already in the ROM, levels 6-15 are just stub data waiting to be tweaked...)


P.S., There is a cheat-code to skip to any level :)