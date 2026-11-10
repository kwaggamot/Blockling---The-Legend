# Blockling: The Legend

A tiny block was born in Super Block World, where size is everything. The Block King took one look at this one-block "Speck" and kicked it off the edge of the world. Now it has to bounce, break and grow its way home.

**To play:** open `index.html` in any modern browser. It is a single file, works on desktop and phone, and saves your progress in the browser.

## How it plays

- **Bounce back.** Red spiky balls are thrown at you. Touch one and it becomes yours. Balls bounce off any side of your block: the top aims them, the sides knock them away, and with the WALL up they can hit the bottom and boost off it, charged and hitting harder. Your balls break blocks. If a red ball gets past you, you lose a heart.
- **Grow.** Every level you clear makes you one size bigger, from Speck to Monolith at level 10.
- **Morph.** After the Level 10 boss you stop growing and start changing shape. There are six forms (Spike, Mirror, Magnet, Prism, Phase, Titan), each with a passive and an active ability. Unlock them with ◆ shards from missions and bosses.
- **Fuse.** From Level 5, merge two stored power-ups into a stronger one. After the first boss, fuse two fusions into the **SUPER BLOCK** ultimate.
- **Missions.** Every level has two optional missions that pay out shards.
- **Worlds.** Ten hand-made worlds, each with its own look and boss, then endless generated worlds after that.

The game opens with an animated story: Blockling is born in Super Block World, gets kicked out by the Block King for being too small, crash-lands in the Exile Plains, and sets off home. You can watch it again from the title screen.

Each level opens with Blockling flying in, telling you "Let's do this!", then turning to face the blocks.

## Controls

| Action | Keyboard | Touch / mouse |
|---|---|---|
| Move | ← → or A D | Drag or move anywhere on the field |
| Use power-up slot | 1–4 | Tap the slot |
| Fuse | F | FUSE button |
| Morph ability | Q or Space | MORPH button |
| Pause | P or Esc | II button |

## Power-ups (catch these)

| Power-up | Effect | From level |
|---|---|---|
| GROW | Double your width for 10s | 1 |
| ×2 | Double every ball you own | 1 |
| WALL | A floor that bounces every ball back for 10s and turns red balls into yours. Balls it sends up into the bottom of your block bounce off faster | 1 |
| SLOW | Enemy balls crawl for 8s | 1 |
| FIRE | Your balls burn straight through blocks for 8s | 1 |
| +HP | Restore one heart and clear every power-down | 1 |
| LASER | Shoot lasers from both corners for 8s | 3 |

## Power-downs (dodge these)

| Power-down | Effect | From level |
|---|---|---|
| SHRINK | You shrink to half width for 8s | 6 |
| RUSH | Enemy balls fly 40% faster for 8s | 6 |
| SLUG | You move at half speed for 8s | 9 |
| FLIP | Left and right swap for 6s | 12 |
| JAM | Your power-up slots lock for 8s | 15 |
| DARK | The lights go out except around you for 8s | 20 |

+HP clears every power-down, and SUPER BLOCK makes you immune.

## Fusion recipes

| Pair | Result |
|---|---|
| GROW + ×2 | TITAN STORM: huge for 12s and 6 new balls |
| GROW + WALL | FORTRESS: huge and walled in for 15s |
| FIRE + ×2 | METEOR RAIN: 8 fireballs and 10s of fire |
| FIRE + LASER | INFERNO: burning lasers that pierce for 12s |
| LASER + SLOW | SNIPER: lasers and slow-mo for 12s |
| +HP + WALL | SANCTUARY: +2 hearts and a wall for 15s |
| FIRE + SLOW | COMET: fire and slow-mo for 12s |
| ×2 + ×2 | SWARM: quadruple your balls |
| GROW + GROW | GIGANTIC: triple width for 12s |
| Any other pair | OVERDRIVE: both effects, 60% longer |
| Fused + Fused | SUPER BLOCK (ultimate) |

## Ads (only on sites that provide them)

The game itself contains no ad code. If the page it runs on provides Google's standard `adBreak()` call (as games.dunescholars.com does), Blockling uses it like this:

- **Nothing on Levels 1–3.**
- **A short break** may play after tapping **Next** on the Level clear screen. Google limits how often, and there is never one straight after a reward ad.
- **Optional rewards**, offered only when an ad is ready and always the player's choice:
  - Level clear: watch an ad for one bonus (a free power-up or a bonus fusion waiting in slot 1 on the next level, or double the shards just earned).
  - Squashed: watch an ad to keep going on the same level with 2 hearts (once per attempt).

Anywhere without `adBreak()` (opening `index.html` directly, GitHub Pages) none of this appears.

## Playing it online

Turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder) and the game will be served at `https://kwaggamot.github.io/Blockling---The-Legend/`.
