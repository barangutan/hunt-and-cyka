# Hunt-and-Cyka
4v1 (Radiant v Dire)

## The concept 

A medium-large sized forest map draped in darkness throughout the entire game. A team of four Snipers are on the hunt for a lone Riki. Snipers spawn at a radiant base, Riki spawns randomly at one of 5 towers dotted throughout the map. There are no lanes in the traditional sense of the word; just pathways carved throughout the forest. Plenty of juking spots, hidden paths & at least 6-7 glades (open areas). 

There are three “rune” spots on the map - in the place of runes are TP scrolls. These are the only consumables in the game. TP scrolls are used to teleport to towers and, in the case of Sniper’s, friendly units (see Sniper ‘R’ ability)

Goal:

* Radiant: hunt Riki and kill him before the timer runs out. 
* Dire: destroy 4 out of the 5 towers before the timer runs out.

## Radiant

Radiant consists of four Snipers with the follow abilities:

#### Q. Rocket Flare

Based on Clockwerk’s “Rocket Flare” ability.

> Fires a global range flare that explodes over a given area, damaging Riki and providing vision of him for 5 seconds and vision over the area for 10.

_Range_: Global<br/>
_Radius_: 575<br/>
_Duration_: 5<br/>
_Damage_: 100/120/150/200<br/>
_Cooldown_: 40/35/30/20<br/>

#### W. Scouting Hawk

Based on Beastmaster’s “Call of the Wild” ability.

> Sniper calls for a watchful hawk. It does not reveal invisible units. It’s used for scouting the map and becomes invisible itself after 3 seconds of being motionless. 

_Duration_: 60/80/100/150<br/>
_Cooldown_: 60/80/80/100

#### E. Heartbleed

Based on Necrophos’ “Hearthstopper Aura” passive.

> Deals HP removal damage. Percentage of which is based on Riki’s max HP.

_Radius_: 300<br/>
_HP loss per second_: 0.6%/0.9%/1.2%/1.5%

#### R. Static Cage

Based on Disruptor’s “Kinetic Field” ability.

> This is a channeled ability. The player who channels the static cage cannot right-click Riki or use other abilities. Static cage traps Riki and gives vision of him for the duration. Other radiant players may teleport to the channeling player if they have a TP scroll. The teleport takes the duration of cage + an additional 3 seconds.

_Range_: 600<br/>
_Radius_: 225<br/>
_Formation Time_: 1.2<br/>
_Duration_: 2.5/3/3.5/4<br/>
_Cooldown_: 60/50/40/30

---

All radiant abilities get leveled up after Riki falls below a certain percentage of his max HP. When he falls:

below 75%, all abilities are upgraded to level 2.
below 50%, all abilities are upgraded to level 3.
below 25%, all abilities get maxed out to level 4.

## Dire

Dire consists of a lone Riki who starts off with 2,000 health and zero HP regen.

Riki has permanent invisibility from the start. He breaks out of invisibility whenever he attacks a radiant player, a tower, or whenever he cuts through a tree.

As mentioned already, Riki’s objective is to destroy 4 out of the 5 towers on the map. His base attack starts out low but he gains a certain percentage increase every time he kills a radiant player. More kills = easier to take down towers. This gives an incentive for the hunted to become the hunter!

Riki’s healthbar is visible to every player on the radiant. By implementing this mechanic, radiant players will be able to tell when Riki is within close proximity to one of them, as their Heartbleed passive will slowly reduce his healthbar. Unfortunately they won’t be able to tell which of the team he’s close to, so they must utilize their abilities to reveal him and deal damage by right-clicking him.

## Potential Issues

A balanced game would ideally consist of radiant having enough incentive to split up and hunt for Riki across the entire map, while dire implements the necessary cunning to stay hidden and take down the towers.

Some things that have to be addressed:

Radiant travelling around the map as four. 

Pros: 
* they’re easily able to detect Riki when he’s nearby
* they’re able to quickly burst him down
Cons:
* they cover less ground and may take a lot of time to find him. Leaving several of the towers open for quick takedown unless they have TP scrolls.
