# Ship and Crew

## TL9 Merchant Trader
 
Using a 200-ton hull (4 Hull, 4 Structure,) the Merchant Trader is frequently encountered along well-established trade routes. It mounts jump drive A, maneuver drive A, and power plant A, giving a performance of Jump-1 and 1-G acceleration. *Fuel tankage of 24 tons* supports the power plant for four weeks and one Jump-1 jump. Adjacent to the bridge is a computer Model 2. The ship is equipped with Basic Civilian sensors (DM-2.) There are ten staterooms and twenty low berths. The ship has two hardpoints and two tons allocated to fire control. *Cargo capacity is 85 tons*. The hull has a standard configuration, and is armored with Titanium Steel (2 points.) Special features include two tons of fuel processors (processes 40 tons of unrefined fuel into refined fuel per day) and fuel scoops. The ship requires a crew of three: one pilot, one navigator and one engineer. (If weapons are installed, this vessel will also require two gunners. Ships may also wish to carry a medic and a steward.) *The ship can carry eight high passengers or 16 middle passengers* at double occupancy (seven high or 14 middle passengers with gunners) and twenty low passengers*. The ship costs MCr34.929 (including discounts and fees) and takes 44 weeks to build.

**Monthly Mortgage:** ` ` Cr103,870 for 30 years (Paid for with 5 ship shares from Rachel Reid)

**Monthly Maintenance**: Cr2,911 (Mcr34.929 * 0.001 / 12)

**Fuel and life support per week in space**: Cr 17,000

**Crew Salaries per month**: Cr15,000 (Pilot: Cr6,000, Navigator: Cr5,000, Engineer: Cr4,000)

## Crew

### Lady Elizabeth Brunnel 757BBA 38yo Female (Pilot)

High Tech homeworld

Retirement: 10,000 annual pension

*Skills: Advocate-1, Comms-0, Computer-1, Engineering-1, Gun Combat-0, Gunnery-0, Jack-of-trades-1, Leadership-1, Melee combat-1, Navigation-1, Piloting-2, Tactics-2, Vehicle-0, Zero-G-1*
#### Inventory
- Cr10,100
- Low Passage x2
- Mesh Armor (5 AR)
- Auto Pistol (2D6 damage)
- Personal communicator
#### Term 1- Navy 0
- Enlistment (INT 6+): 13
- Survival (INT+5): 12 (Easy term)
- Commission (SOC+7): 10
- Skills: Tactics & Computers
- Re-enlistment (5+): 11 (They really wanted her back)
#### Term 2- Navy 1
- Survival (INT+5): 7 (Typical term, not too easy but not really hard)
- Advancement (EDU+6): 9
- Skills: Melee combat & Jack-of-trades
- Re-enlistment (5+): 10

#### Term 3- Navy 2
- Survival (INT 5+): 7
- Advancement (EDU 6+): 4 failed
- Skills: Leadership & Engineering
- Re-enlistment (5+): 7

#### Term 4- Navy 2
- Survival (INT 5+): 8
- Advancement (EDU 6+): 10
- Skills: Piloting & Advocate
- Reenlistment (5+): 12 Required
- Aging: 3- No effect

#### Term 5-Navy 3
- Survival: 10
- Advancement: 6 (Just barely passed)
- Skills: Piloting & Navigation
- Reenlistment: 7
- Aging: 0- Reduce
#### Mustering out Navy 4
Benefits: 6
1. Cr1,000
2. Cr20,000
3. Cr5,000
4. Low Passage
5. +1 EDU
6. Low Passage

### Rachel Reid 88BBA8 42yo Female (Engineer)

Garden Homeworld

Retirement: Cr12,000 annual pension

*Skills: Animal-0, Broker-0, Coms-1, Engineering-1, Gun combat-0, Gunnery-1, Medicine-4, Melee combat-1, Navigation-1, Piloting-1 Steward-1, Tactics-2, Vehicle-0*

#### Inventory
- Cr40,300
- Mesh Armor (5 AR)
- Auto Pistol (2D6 damage)
- Personal communicator
#### Term 1- Merchant 0
- Enlistment (INT 4+):  5
- Survival (INT 5+): 11
- Commission (INT 5+): 9
- Skills: Melee combat & Coms
- Reenlistment (4+): 10

### Term 2-Merchant 1
- Survival (INT 5+): 9
- Advancement (EDU 8+): 6 failed
- Skills: Piloting & Engineering
- Reenlistment (4+): 6

### Term 3- Merchant 1
- Survival (INT 5+): 6
- Advancement (EDU 8+): 11
- Skills: Medicine & Tactics
- Reenlistment (4+): 6

### Term 4- Merchant 2
- Survival (INT 5+): 8
- Advancement (EDU 8+): 11
- Skills: Navigation & Medicine
- Reenlistment (4+): 7
- Aging: 0- Reduce STR

### Term 5- Merchant 3
- Survival (INT 5+): 9
- Advancement (EDU 8+): 9
- Skills: Medicine x2
- Reenlistment (4+): 12 (Mandatory additional term)
- Aging: 1- No effect

### Term 6- Merchant 4
- Survival (INT 5+): 11
- Advancement (EDU 8+): 8
- Skills: Gunnery & Tactics
- Reenlistment (4+): 9
- Aging: 0- Reduce DEX

#### Mustering Out Merchant 5
Benefits: 7
1. Cr50,000
2. Cr1,000
3. Cr5,000
4. +1 EDU
5. Weapon
6. Explorer's Society
7. 5 ship shares

### Stan Wilson 969795 28yo Male (Navigator)
Dessert Homeworld

*Skills: Computer-1, Coms-1, Demolitions-1, Electronics-0, Gun Combat-0, Gunnery-0, Jack-of-trades-1, Medicine-1, Navigation-1, Recon-0, Piloting-1, Survival-0*
#### Inventory
- Cr54,350
- Mesh armor (5 AR)
- Personal Communicator
- Auto Pistol (2D6 damage)

#### Term 1- Scout
- Enlistment (INT 6+): 6
- Survival (END 7+): 8
- Skills: Jack-of-trades & Coms
- Reenlistment (6+): 6

#### Term 2- Scout
- Survival (END 7+): 9
- Skills: Medicine & Computer
- Reenlistment (6+): 6

#### Term 3- Scout
- Survival (END 7+): 3
- Mishap: 6- Medically discharged
	- Injured: 3- Missing eye or limb. Reduce Strength or Dexterity by 2.
	- Missing eye, DEX - 2
- Skills: Demolitions & Navigation

#### Mustering Out- Scout
Benefits: 2
1. 50,000
2. 20,000


*Key*: STR-DEX-END-INT-EDU-SOC

```python
# This script will roll 6 stats of 3d6 with the lowest dropped.
# This makes for more heroic character.
# Output is a 6 digit pseudo-hexadecimal value, each digit represents a stat.

import random

hex = "0 1 2 3 4 5 6 7 8 9 A B C D E F".split(" ")
result = ""
for _ in range(6):
	rolls = []
	rolls.append(random.randint(1, 6))
	rolls.append(random.randint(1, 6))
	rolls.append(random.randint(1, 6))
	rolls.remove(min(rolls))
	result += hex[rolls[0] + rolls[1]]

print(result)
```
