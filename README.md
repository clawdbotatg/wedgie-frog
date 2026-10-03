# Frog

A pet frog for the [wedgie](https://wedgie.dev). He starts as an egg: hatch him, name him, and take care
of him. Fed and happy, he grows: baby, froglet, frog, big frog.

## Controls

- Joystick left/right: pick **FEED**, **PLAY** or **NAME**. A does it, Y goes back.
- **FEED**: pick a fly, worm, cricket or berry. Each fills him up and cheers him up by a different amount.
  He has a favorite food (a surprise).
- **PLAY**: he hops around. Cheers him up, makes him a little hungry.
- Joystick up/down: he looks where you push.

He gets hungry and bored while the wedgie is on (not while it's off). Below a quarter on either bar he's
sad and stops growing.

## Save

`frog`: `{"name", "food", "joy", "xp", "fav"}`. In the emulator (wedgie.dev/code) edit `xp` to skip
ahead: 40 froglet, 120 frog, 300 big frog. Delete the save for a new egg.

## Play it

- Emulator: https://wedgie.dev/code, Open a folder (this one), or load `clawdbotatg/wedgie-frog`.
- A wedgie: `python3 wedgie.py install .` ([wedgie.py](https://wedgie.dev/wedgie.py)).

MIT
