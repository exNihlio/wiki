## Overview

### Stats

#### Pilots

`Pilot (Pil)` - Ability to manuever, run, dodge and push the mech beyond its limits.

`Electronics (Ele)` - Ability to use electronic systems such as targeting computers, electronic countermeasures etc.

`Artillery (Art)` - Long range shooting capability (missiles, large cannons)

`Brawl (Bra)` - Melee combat

`Duel (Due)` - Close range shooting.

#### Mecha

`Reactor (Rea)` - Powerplant strength

`Heat (Hea)` - Heatsink efficiency 

`Targeting (Tar)` - Speed and accuracy of the onboard targeting system(s)

`Armor (Arm)` -  Durability of the mech's armor

`Speed (Spe)` - Mobility of the mecha

`Weight (Wei)` - The overrall tonnage of a mech

### Stats Overview

Stats are all based on a D6 success system. Base difficulty is a 5. One must roll
a number of dice and each result >= 5 is considered a success. The difficulty of a
roll can be increased or decreased. A difficulty modifier of a +1 means a roll of 6
is required instead of a 5. Conversely a difficulty modifier of -1 means a roll of >=4
is required.

A certain number of successes is required to complete a skill check. For example, to shoot an
enemy mech, the following check may be required:

**Example**

The pilot (Callsign: Argent) attempts to shoot an enemy mecha (Callsign: Zanzibar) with his Rytech light chaingun. Argent is at close
range, so this is a `Duel (Due)` check. To shoot Zanzibar, Argent rolls a number of D6 equal to their `Due` and
`Targeting (Tar)`. In this case, their `Due` is `3` and their `Tar` is `2` for a total of 5D6. There are no special
circumstances and Zanzibar is not in cover, so the base difficulty is 5. Argent rolls a 1, 2, 4, 5, and 6. Thus they have
two successes. Zanzibar attempts to defend and rolls their `Pilot (Pil)` and `Armor (2)`. Their `Pil` is `3` and their `Arm` is `1`.
They roll a 2, 3, 3 and 6 for a single success. Argent has more successes than Zanzibar and has thus successfully hit Zanzibar.

The Ronin class light chaingun has a damage stat of 6D6, with no modifiers meaning that 6D6 is rolled for damage and every result >=5
is a single point of damage. Argent rolls a 1, 1, 3, 5, 5, 6 for a total of 3 successes. The Rytech light chaingun has a `Damage` stat of
`1`, dealing 1 damage for each success. Zanzibar therefor marks three damage on their mech damage tracker.

### Stat lines

Example Mech Statline

| Rea | Hea | Tar | Arm | Spe |
|-----|-----|-----|-----|-----|
| 3   | 2   | 3   | 5   | 2   |

Example Pilot Statline

| Pil | Ele | Art | Bra | Due |
|-----|-----|-----|-----|-----|
| 2   | 1   | 3   | 1   | 4   |

Combined Stats

`Defend` - `Pil + Spe`

`Short Range Attack (SRA)` - `Due + Tar`

`Long Rage Attach (LRA)` - `Art + Tar`

`Melee Attack (MA)` - `Bra + Tar`
1
`Run` - `Pil + Spe`

`Charge` - `Pil + Rea`

`Scan` - `Pil + Tar`


### Mech Sizes

Mecha come in four primary sizes: Light, Medium, Heavy and Super-Heavy. A light mecha comes on a
60mm base. Medium mecha on an 80mm base, large mecha on 100mm base and super-heavy on a 120mm base.

### Mecha Construction

Mecha are extremely diverse in design, ranging from the classic bipedal, to four-legged walkers, to treads,
spider legs, or even hovering on anti-grav systems. They may mount a variety of weapons, shields, electronic
countermeasures, targeting systems, rocket engines or arcane xenotechnology (ztech).

A mecha must consist of the minimum following:

"Legs", meaning either actual legs, treads, hover jets or some other exotic means of propulsion.

A "body", meaning an upper chassis upon which the "legs" are fixed.

A powerplant or "reactor" to actually power the mecha.

As a rule, these _should_ be represented on the miniature, but are not neccesarily required.

The two main facets that influence mecha design are the weight and cost. A light mech
is classified as 25 tons, a medium mech is 50 tons, a heavy tank is 100 tons and a super-heavy
mech is >100 tons. 

| Class       | Tons  |
|-------------|-------|
| Light       | >=25  |
| Medium      | >=50  |
| Heavy       | >=100 |
| Super-heavy | >=150 |

Mecha "cost" is used to balance the game. The Standard System Credit (SSC) or "credit" is the universal monetary system
in the game. Before playing, the number of credits of the game size are agreed on. 100 credits is a small game, 200 credits
is a medium game and 400 credits is a large game.


### Mech Parts

Each mech part has an associated component that dictates a core stat. Legs dictate speed, chassis
dicates armor, reactors dictate the reactor stat and so on. A mech statline is the sum of the mech's
associated parts.
 
#### Legs

| Name                              | Weight | Cost | Speed | Scale |
|-----------------------------------|--------|------|-------|-------|
| Rytech Series Biped               | 2      | 5    | 2     | Light |
| Rytech Series Quadraped           | 4      | 10   | 3     | Light |
| Rytech Series Spider              | 6      | 15   | 4     | Light |

#### Chassis

| Name                              | Weight | Cost  | Armor | Scale |
|-----------------------------------|--------|-------|-------|-------|
| Rytech Series Ranger              | 7      | 10    | 2     | Light |
| Rytech Series Slammer             | 10     | 15    | 3     | Light |
| Rytech Series Sabatons            | 12     | 20    | 4     | Light |

#### Reactors

| Name                              | Weight | Cost | Reactor | Scale |
|-----------------------------------|--------|------|---------|-------|
| Rytech Series RX-10               | 1      | 5    | 2       | Light |
| Rytech Series RX-15               | 2      | 10   | 3       | Light |
| Rytech Series RX-20               | 3      | 15   | 4       | Light |

#### Weapons

| Name                              | Weight | Cost | Damage | Armor Penetration | Attack | Type      |  Scale |
|-----------------------------------|--------|------|--------|-------------------|--------|-----------|--------|
| Rytech Chaingun                   | 1      | 2    | 1      | 0                 | 5D6    | Duel      | Light  |
| Rytech Railgun                    | 2      | 5    | 3      | 1                 | 2D6    | Artillery | Light  |
| Rytech Neocarbon Axe              | 1      | 10   | 1      | 2                 | 3D6    | Brawl     | Light  |

#### Targeting Systems

| Name                              | Weight | Cost | Targeting | Scale |
|-----------------------------------|--------|------|-----------|-------|
| Rytech Theta Acquisition          | 0      | 4    | 1         | Light |
| Rytech Lambda Pinpoint            | 0      | 6    | 2         | Light |
| Rytech Gamma Precision            | 0      | 8    | 3         | Light |

#### Example Mech

**Rytech Enforcer**

```
Legs: Rytech Series Biped
Chassis: Rytech Series S
```

### Pilots

#### Pilot Abilities

```
+--------------------------+
| Skilled Pilot +----------|
|--------------------------+
| May reroll one speed die |
|--------------------------+
| Cost: 2 Credit(s)        |
+--------------------------+

+--------------------------+
| Quick Thinker +----------|
|--------------------------+
| May shift one card in the|
| priority queue by one    |
| position                 |
|--------------------------+
| Cost: 1 Credits          |
+--------------------------+

+--------------------------+
| Aggressive +-------------|
|--------------------------+
| May exchange any one die |
| for a targeting die      |
|--------------------------+
| Cost: 2 Credits          |
+--------------------------+

+--------------------------+
| Exo-Armor +--------------|
|--------------------------+
| May exchange a speed die |
| for an armor die         |
|--------------------------+
| Cost: 2 Credits          |
+--------------------------+
```
