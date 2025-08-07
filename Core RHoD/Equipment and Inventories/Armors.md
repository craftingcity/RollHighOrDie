# Preamble
Within the fiction of the story you tell, your characters may use any number of Armors. For the purpose of mechanical potential, RHoD's Armors are a collection of Tags.

### Repairing Armors
When a Character takes damage while they have Armor equipped, they take that damage to their Armoring before their Vitality. That Armor remains damaged until it is Repaired.

A character can spend a number of the Armor's Materials and an equal number of Watches using relevant Tool Actions to Repair damaged Armor. For each Material spent, the Armor is repaired by a number equal to that Material's Toughness, up to the Armor's Maximum Armoring. 

# Armor Tags
### Required Tags
#### Size
This is the mechanical Size of the Armor - Small, Medium, or Large - and is used in addition to an Armor's 'Material' and 'Style' to determine the Maximum Armoring Value of that Armor.

Small Armors have a Size Multiplier of 1.

Medium Armors have a Size Multiplier of 2.

Large Armors have a Size Multiplier of 3.

#### Material
This is the material the Armor is mostly composed of. Each Material has a Toughness and a relevant Tool Action. 

The Material's Toughness is used in addition to an Armor's 'Size' and 'Style' to determine the Maximum Armoring Value of that Armor. The Material's Tool Action is used in the process of repairing an Armor of that Material.

Materials are considered either 'Light' or 'Heavy', which will determine an Armor's eligibility for use with some Features, Traits, or other Armor Tags.

##### Example Materials
| Material          | Toughness | L/H   | Tool Action |
| ----------------- | --------- | ----- | ----------- |
| Casual Cloth      | 0.2       | Light | *TAILOR*    | 
| Padded Cloth      | 1         | Light | *TAILOR*    |
| Beast Hide        | 2         | Light | *TAILOR*    |
| Tanned Leather    | 3         | Light | *TAILOR*    |
| Kevlar            | 4         | Light | *TAILOR*    |
| Bronze Chainmail  | 5         | Heavy | *FORGE*     |
| Bronze Plate      | 6         | Heavy | *FORGE*     |
| Steel Chainmail   | 6         | Heavy | *FORGE*     |
| Steel Plate       | 8         | Heavy | *FORGE*     |
| Ceramic Composite | 9         | Heavy | *CHEMISTRY* |
| Darksteel Plate   | 10        | Heavy | *FORGE*     |
| Mythril Plate     | 12        | Heavy | *FORGE*     |
| Adamantine Plate  | 16        | Heavy | *FORGE*     |

#### Style
This is the style of Armor, reflecting an Armor's 'Areas of Coverage', and is used in addition to an Armor's 'Material' and 'Size' to determine the Maximum Armoring Value of that Armor.

'Areas of Coverage' are the areas of a creature that are actually being defended by the 'Material' of this Style of Armor. 

The Style's Total Coverage Value is the total of all Coverage Values of the Style's Areas of Coverage. Areas of Coverage have a Coverage Value ranging from 1 to 3 (for example, 'Feet' has 1CV, 'Arms' has 2CV, and 'Suit' has 3CV). The following table describes the 'Areas of Coverage' an Armor may have, and their respective Coverage Value.

| Area of Coverage     | Coverage Value | Description                             |
| -------------------- | -------------- | --------------------------------------- |
| Head - Top           | 2              | Covering the top of your head           |
| Head - Back          | 2              | Covering the back and neck of your head |
| Head - Sides         | 2              | Covering both sides of your head        |
| Head - Front         | 2              | Covering your face and forehead         |
| Head - Eyes          | 1              | Covering your eyes                      |
| Upper & Lower - Suit | 3              | Covering your joints                    |
| Upper - Front        | 3              | Covering your chest                     |
| Upper - Back         | 3              | Covering your back                      |
| Upper - Arms         | 2              | Covering your upper and fore arms       |
| Upper - Hands        | 1              | Covering your hands and fingers         |
| Lower - Thighs       | 2              | Covering your thighs                    |
| Lower - Shins        | 2              | Covering your shins                     |
| Lower - Feet         | 1              | Covering your feet and toes             |

##### Example Styles
| Style           | Coverage Value | Areas of Coverage                                                     |
| --------------- | -------------- | --------------------------------------------------------------------- |
| Cap Helm        | 4              | (head - top, back)                                                    |
| Half Helm       | 6              | (head - top, back, sides)                                             |
| Full Helm       | 8              | (head - top, back, sides, front)                                      |
| Eyewear         | 1              | (head - eyes)                                                         |
| Facemask        | 2              | (head - front)                                                        |
| Combat Vest     | 3              | (upper - front)                                                       |
| Chestplate      | 6              | (upper - front, back)                                                 |
| Combat Jacket   | 8              | (upper - front, back, arms)                                           |
| Bracers         | 2              | (upper - arms)                                                        |
| Gauntlets       | 3              | (upper - arms, hands)                                                 |
| Gloves          | 1              | (upper - hands)                                                       |
| Thighguards     | 2              | (lower - thigs)                                                       |
| Shinguards      | 2              | (lower - shins)                                                       |
| Greaves         | 3              | (lower - shins, feet)                                                 |
| Boots           | 1              | (lower - feet)                                                        |
| Combat Pants    | 4              | (lower - thighs, shins)                                               |
| Combat Suit     | 3              | (upper & lower - suit)                                                |
| Full-suit Armor | 17             | (upper & lower - suit, front, back, arms, hands, thighs, shins, feet) |
| Buckler         | 3              | (upper - arms)                                                        |
| Kite Shield     | 5              | (upper - front, arms)                                                 |
| Tower Shield    | 9              | (upper & lower - front, arms, thighs, shins)                          |

#### Maximum Armoring
This is the maximum value of Armoring this Armor can provide in perfect condition. This value is equal to the Material Value plus the Coverage Value, multiplied by the Size Multiplier. 

Maximum Armoring = (Material Toughness + Coverage Value) * Size Multiplier

` current example numbers give ~700 as MaxArmoring `

> For example, let's examine a Steel Plate Full-suit Armor as made for a traditional human - Medium sized.
> Medium Armors have a SM of 2. Steel Plate has a MT of 8. Full-suit Armor has a CV of 17.
> Material Toughness (8) + Coverage Value (17) = 25
> 25 * Size Multiplier (2) = 50
> Medium Size Steel Plate Full-suit Armor has a Maximum Armoring Value of 50.

### Mundane Tags
#### Padded (x)
While your Armoring is greater than 0, you have Bludgeoning Damage Resistance and Electric Damage Resistance equal to the value indicated (x) and you have Slashing Damage Vulnerability and Fire Damage Vulnerability equal to the value indicated (x).

#### Metallic (x)
While your Armoring is greater than 0, you have Slashing Damage Resistance and Piercing Damage Resistance equal to the value indicated (x) and you have Electric Damage Vulnerability and Fire Damage Vulnerability equal to the value indicated (x).

#### Restricting (x)
While you are wearing this Armor, your Dexterity Ability Score is reduced by the indicated value (x).

#### Pockets (x)
While you are wearing this Armor, you gain the indicated number (x) of Item Slots. While using Equipment stored in these Inventory Slots, you may ignore the 'UNPACK' Interaction Cost of that Equipment.

### Specialized Tags
#### Powered (x)
While you are Resting, you may Fuel your Armor by expending the indicated number and type (x) of items. If you do, your Armor is Fueled for one Day.

If your Armor is not Fueled, you treat this Armor as if it had no other Mundane or Specialized Tags.