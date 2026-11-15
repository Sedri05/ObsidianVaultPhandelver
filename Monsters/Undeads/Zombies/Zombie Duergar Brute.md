
```statblock
layout: Basic 5e Layout
name: Zombie Duergar Brute
size: Medium
type: Undead
subtype: Dwarf
alignment: Evil
ac: 16
hp: 68
hit_dice: 8d8 + 32 
speed: 30ft.
stats: [18, 8, 18, 5, 9, 5]
saves:
  - Constitution: +6
  - Strength: +6
damage_resistances: Cold  
damage_immunities: Poison 
condition_immunities: Poisoned
senses: Darkvision 60ft., passive Perception 9
languages: Understands Dwarvish but can't speak
cr: 3
traits:
  - name: Multiattack
    desc: "The brute makes two War Picks attacks."
  - name: Undead Fortitude
    desc:  "If damage reduces the zombie to 0 hit points, it must make a Constitution saving throw with a DC of 5+the damage taken, unless the damage is radiant or from a critical hit. On a success, the zombie drops to 1 hit point instead."
  - name: Duergar Resilience.
    desc: "The zombie has advantage on saving throws against illusions and against being charmed or paralyzed."
actions:
  - name: Enlarge (Recharges after Short or Long Rest).
    desc: "For 1 minute, the duergar magically increases in size, along with anything it is wearing or carrying. While enlarged, the duergar is Large, doubles its damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the duergar lacks the room to become Large, it attains the maximum size possible in the space available."
  - name: War Pick
    desc: "Melee Weapon Attack: +6 to hit, reach 5ft., one target. Hit 1 (1d8+4) piercing damage, or 1 (2d8+4) piercing damage while enlarged."
  - name: Javelin
    desc: "Melee or Ranged Weapon Attack: +6 to hit, reach 5ft. or range 30/120ft., one target. Hit 1 (1d6 + 4) piercing damage or 1 (2d6 + 4) piercing damage while enlarged."
  - name: "Corpse Explosion (Recharges after Short or Long Rest)."
    desc: "The brute can target one corpse it can see within 60ft. and cause it to explode. Any creature within 10ft. of this corpse must make a DC14 Constitution saving throw, taking 1 (3d10) Necrotic damage on a failure, or half as much on a success."
```
