The Legend of Zelda II (NES/SNES?)

[[TOC]]

# Overview

So after reading about [Zelda II: The Adventure of Link](https://en.wikipedia.org/wiki/Zelda_II:_The_Adventure_of_Link), it turns out the "Legend" isn’t about the Zelda that Link saves in the first one, but about an ancient princess put under a sleeping spell (whom Link saves in the second game). But I think it would be cool to tell the story of *that* Zelda, where she is the protagonist.

OR, what if we did a hack of Zelda II on the NES, changing the protagonist to be *Zelda*, trying to save a sleeping *Link*! I always wanted to change the game to incorporate Link using arrows and boomerangs, and I think it would make a lot more sense to have a focus on magic and ranged weapons if Zelda is the protagonist. How hard is it to create our own sprites, and then to import them into the game? Probably pretty hard :-)

Not worth it to incorporate merchants and rupees and stuff. Perhaps some early dialogue that everyone is willing to help the Princess on her quest to save the hero, Link?

This could be such a cool chapter in the Link/Zelda saga! And it would be a great excuse for the game being so different in style from the first one. Gah! I’m actually really excited to develop this!

One final note: I think I want to change as little as possible about the game (after we change the main character to Zelda and implement a multi-weapon system with D&D hit-rules ;-P). Inasmuch as we can, I’d simply like to make more sense out of what happens and why, to tell a more compelling story.

# The Story

**Original Story:** http://www.zeldadungeon.net/wiki/The_Adventure_of_Link_Story

In the aftermath of the first Legend of Zelda, Link falls prey to Ganon’s Curse (perhaps placed on the red ring you find in the final dungeon). He falls into a deep sleep, and none know how long he will last. Zelda embarks on a quest to banish Ganon’s curse and awaken Link.

Unbeknownst to Zelda, Ganon’s followers implement a plan to bring him back (this is a mystery that is uncovered as you play). It becomes clear that Ganon’s return depends on Link’s survival, and so in the end Zelda (perhaps after winning the Triforce of Wisdom) makes the hard decision to let Link die so that Ganon cannot be revived.

Questions to answer:

* What do the palaces and the gems have to do with anything?

* Even more basic, what are the palaces? Why are there monsters guarding the statues? What does this tell us about Hyrule?

# Maps

What I would like to do is to redraw the map so that the original Zelda took place all within the vicinity of Death Mountain, so the new game will simply be a broader picture of Hyrule, rather than a completely different one.

I would also like to make the palaces more distinct (and possibly have a more navigable layout; not sure how to do that yet, though). This game needs a map system. Maps of the palaces are hidden in nearby towns! Speaking of, the towns need to have more personality, too, incorporating features of the nearby geography.

# Weapons

Link’s sword was a complete joke in the Zelda II. I’d like to use the same mechanic but make it clear that it’s Zelda’s knife, and really only for close-range melee stuff. Her primary weapon should be her bow. Man, it’d be so great to have just a couple more buttons! Like a dedicated knife button, bow/arrow button, jump button, and then an alternate weapon button (actually, I haven’t thought of anything other than a boomerang yet). Maybe we could approach this more as a port of the game to the SNES? Is there an SNES game with similar enough mechanics that we could use it as the base for a hack? Or should we just say, "Fuck it" and make our own game from scratch? (Sidenote: the guy who made AM2R (Another Metroid 2 Remake) started with a program called GameMaker, and eventually programmed in C#.)

More D&D style stats/hit calculations?

The "sword" meter upgrade in the original game should be changed to simply “power” meter upgrade, perhaps affecting base hit calculations for all attacks.

## Bow

* I’d like to incorporate a couple of bow upgrades. Different bows would increase the range, total attack power, firing speed, etc.

* I was also thinking that it’d be cool to have arrow upgrades, but ones that upgrade distinct stats from the bows. Upgrading the arrows increases the consistency (and frequency of critical hits, and maybe also the range?).

* In keeping with the minimalist style of the NES, these stat things will probably have to be opaque to the player. But perhaps we could name the bow/arrow upgrades to give clues?

## Boomerang

* Steal the mechanic from the enemies that use boomerangs early in the game. Perhaps high/low throw?

* Incorporate weapon-switching mechanic (this sucks with only two buttons, esp when one of them has to be dedicated to a jump)

* It should damage un-armored enemies, and stun armored ones.

* Upgrade(s) with greater range and/or power?

## Melee

* **Knife**: basic starting weapon. I think we just keep the mechanic of Link’s lame-ass sword.

* **Spear**: This could be really cool. A bit stronger, and with better range. Also really cool to implement the upthrust/downthrust with this weapon. It already exists as a weapon later enemies use.

# Clothes/Armor

I think it would be cool if Zelda wore a cloak (which would be much easier to implement on SNES hardware). Also, it would be sweet if she started out wearing all white, and then as the game went on her clothes got dirtier and dirtier; perhaps different garments could "dirty" at different rates in different environments!

# SNES Sprite Requirements

[https://megacatstudios.com/blogs/press/snes-sprite-engine-design-guidelines](https://megacatstudios.com/blogs/press/snes-sprite-engine-design-guidelines)

**Sizes:** A SNES sprite can be 8x8, 16x16, 32x32 or 64x64. Sizes cannot be chosen freely. A game can have two of the predetermined size combinations:

* 8x8, 16x16

* 8x8, 32,32

* 8x8, 64x64

* 16x16, 32x32

* 16x16, 64x64

* 32x32, 64x64
