# Preamble
Any Ranged Weapon fires a projectile known as its Ammunition. Much like their counterparts, each Ammunition is a Base and a collection of Tags.

## Bases
### Classic
#### Sling-Bullet
#### Arrow
#### Bolt
#### Great-Arrow
### Modern
#### Powder-Shot
#### Low Caliber
#### High Caliber
#### Shotshell
#### Energy

## Tags
### Required Tags
#### Size
This is the mechanical Size of the Ammunition. All Ammunition is 'stackable' to the value indicated after their Size - either Small or Tiny.

#### Ammunition Damage Dice
This is the amount (y) and type (x) of dice you will roll to deal damage with this Ammunition.

#### Ammunition Damage Type
This is the type of damage that this Ammunition deals. Mundane Ammunition only ever deal Piercing, Bludgeoning, and/or Slashing damage.

### Mundane Tags
#### Fragile
When this Ammunition is expended, it cannot be recovered.

#### Durable
When this Ammunition is expended, it can be recovered. 

Note the amount of this Ammunition you spend during combat. After combat, you may attempt to recollect your ammunition by making a Investigation Skill Check.

If the Total of your Check is 10 or greater, you may recover half of your expended Ammunition.

If the Total of your Check is 20 or greater, you may recover all of your expended Ammunition.

### Specialized Tags
#### Barbed / Hollow Point
When you deal Damage using this Ammunition, you apply one stack of the 'Bleeding' [[Ailment]].

#### Coring / Armor Piercing
When you deal Damage using this Ammunition, you may deal half that damage as True Damage.

#### Over-Pressured
When you make an Attack using this Ammunition, the Complexity Value of your Weapon increases by 2.

#### Explosive
When you make an Attack using this Ammunition, the Complexity Value of your Weapon increases by 4. 

This Ammunition's Damage Type is Force.

#### Tracer
When you make an Attack using this Ammunition, the space your target occupies is lit by Low Light until the end of your turn.

#### Incendiary (x)
When you make an Attack using this Ammunition, if the space your target occupies is 'Flammable', it becomes 'Enflamed'.

If you hit with an Attack using this Ammunition, your target gains a number of stacks of the 'Burning' [[Ailment]] equal to the value indicated (x).

# Example Ammunition
### Projectile Ammunition
| Title                       | Base         | Size       | D. Dice | D. Type     | Other                              |
| --------------------------- | ------------ | ---------- | ------- | ----------- | ---------------------------------- |
| Pebble                      | sling-bullet | Tiny (15)  | 1d4     | Bludgeoning | Fragile                            |
| Clay Bullet                 | sling-bullet | Small (6)  | 1d6     | Bludgeoning | Fragile                            |
| Lead Bullet                 | sling-bullet | Small (3)  | 1d6     | Bludgeoning | Durable                            |
| Cherry Bomb                 | sling-bullet | Small (8)  | 1d4     | Force       | Fragile, Explosive                 |
| Clay Bomb                   | sling-bullet | Small (4)  | 2d8     | Force       | Fragile, Explosive                 |
| Clay Firebomb               | sling-bullet | Small (4)  | 2d4     | Force       | Fragile, Explosive, Incendiary (3) |
| Sharpened Wooden Arrow      | arrow        | Small (30) | 1d4     | Piercing    | Fragile                            |
| Bodkin Wooden Arrow         | arrow        | Small (30) | 1d6     | Piercing    | Fragile                            |
| Broadhead Wooden Arrow      | arrow        | Small (30) | 1d6     | Piercing    | Fragile, Barbed                    |
| Corehead Wooden Arrow       | arrow        | Small (30) | 1d4     | Piercing    | Fragile, Coring                    |
| Sharpened Steel Arrow       | arrow        | Small (25) | 1d6     | Piercing    | Durable                            |
| Bodkin Steel Arrow          | arrow        | Small (25) | 1d8     | Piercing    | Durable                            |
| Broadhead Steel Arrow       | arrow        | Small (25) | 1d8     | Piercing    | Durable, Barbed                    |
| Corehead Steel Arrow        | arrow        | Small (25) | 1d6     | Piercing    | Durable, Coring                    |
| Sharpened Wooden Bolt       | bolt         | Tiny (20)  | 1d4     | Piercing    | Fragile                            |
| Bodkin Wooden Bolt          | bolt         | Tiny (20)  | 1d6     | Piercing    | Fragile                            |
| Broadhead Wooden Bolt       | bolt         | Tiny (20)  | 1d6     | Piercing    | Fragile, Barbed                    |
| Corehead Wooden Bolt        | bolt         | Tiny (20)  | 1d4     | Piercing    | Fragile, Coring                    |
| Sharpened Steel Bolt        | bolt         | Tiny (15)  | 1d4     | Piercing    | Durable                            |
| Bodkin Steel Bolt           | bolt         | Tiny (15)  | 1d6     | Piercing    | Durable                            |
| Broadhead Steel Bolt        | bolt         | Tiny (15)  | 1d6     | Piercing    | Durable, Barbed                    |
| Corehead Steel Bolt         | bolt         | Tiny (15)  | 1d4     | Piercing    | Durable, Coring                    |
| Sharpened Wooden Greatarrow | great-arrow  | Small (5)  | 2d6     | Piercing    | Fragile                            |
| Broadhead Wooden Greatarrow | great-arrow  | Small (5)  | 3d6     | Piercing    | Fragile, Barbed                    |
| Corehead Wooden Greatarrow  | great-arrow  | Small (5)  | 2d6     | Piercing    | Fragile, Coring                    |
| Sharpened Steel Greatarrow  | great-arrow  | Small (3)  | 2d6     | Piercing    | Durable                            |
| Broadhead Steel Greatarrow  | great-arrow  | Small (3)  | 3d6     | Piercing    | Durable, Barbed                    |
| Corehead Steel Greatarrow   | great-arrow  | Small (3)  | 2d6     | Piercing    | Durable, Coring                    |
| Solid Ball                  | shaped       | Medium     | 4d8     | Bludgeoning | Durable                            |
| Grape Ball                  | shaped       | Medium     | 3d6     | Piercing    | Fragile                            |

### Cartridge Ammunition
All Cartridge Ammunitions inherently have the 'Fragile' Tag.

| Title                       | Base         | Size       | D. Dice | D. Type     | Other                          |
| --------------------------- | ------------ | ---------- | ------- | ----------- | ------------------------------ |
| Round Powder Shot           | powder-shot  | Tiny (15)  | 1d4     | Bludgeoning |                                |
| Point Powder Shot           | powder-shot  | Tiny (15)  | 1d6     | Piercing    |                                |
| Grape Powder Shot           | powder-shot  | Tiny (15)  | 1d10    | Piercing    |                                |
| .22LR (FMJ)                 | low caliber  | Tiny (25)  | 1d4     | Piercing    |                                |
| 9mm (FMJ)                   | low caliber  | Tiny (25)  | 1d6     | Piercing    |                                |
| 9mm (JHP)                   | low caliber  | Tiny (25)  | 1d6     | Piercing    | Hollow Point                   |
| 9mm (JHP+P)                 | low caliber  | Tiny (25)  | 2d4     | Piercing    | Hollow Point, Over-Pressured   |
| 9mm (AP)                    | low caliber  | Tiny (25)  | 1d6     | Piercing    | Armor Piercing                 |
| .357 Magnum (FMJ)           | low caliber  | Tiny (20)  | 1d8     | Piercing    |                                |
| .357 Magnum (JHP)           | low caliber  | Tiny (20)  | 1d8     | Piercing    | Hollow Point                   |
| .357 Magnum (JHP+P)         | low caliber  | Tiny (20)  | 2d6     | Piercing    | Hollow Point, Over-Pressured   |
| 10mm (FMJ)                  | low caliber  | Tiny (25)  | 1d6     | Piercing    |                                |
| 10mm (JHP)                  | low caliber  | Tiny (25)  | 1d6     | Piercing    | Hollow Point                   |
| 10mm (JHP+P)                | low caliber  | Tiny (25)  | 2d6     | Piercing    | Hollow Point, Over-Pressured   |
| 10mm (AP)                   | low caliber  | Tiny (25)  | 1d6     | Piercing    | Armor Piercing                 |
| .45 ACP (FMJ)               | low caliber  | Tiny (25)  | 1d8     | Piercing    |                                |
| .45 ACP (JHP)               | low caliber  | Tiny (25)  | 1d8     | Piercing    | Hollow Point                   |
| .45 ACP (JHP+P)             | low caliber  | Tiny (25)  | 2d6     | Piercing    | Hollow Point, Over-Pressured   |
| .45 ACP (AP)                | low caliber  | Tiny (25)  | 1d8     | Piercing    | Armor Piercing                 |
| .45 ACP (HE)                | low caliber  | Tiny (25)  | 1d8     | Force       | Explosive                      |
| 5.45x39mm USSR (FMJ)        | high caliber | Tiny (15)  | 2d6     | Piercing    |                                |
| 5.45x39mm USSR (JHP)        | high caliber | Tiny (15)  | 2d6     | Piercing    | Hollow Point                   |
| 5.45x39mm USSR (AP)         | high caliber | Tiny (15)  | 2d6     | Piercing    | Armor Piercing                 |
| 5.45x39mm USSR (AP+I)       | high caliber | Tiny (15)  | 2d6     | Piercing    | Armor Piercing, Incendiary (1) |
| 5.56x45mm NATO (FMJ)        | high caliber | Tiny (15)  | 2d6     | Piercing    |                                |
| 5.56x45mm NATO (JHP)        | high caliber | Tiny (15)  | 2d6     | Piercing    | Hollow Point                   |
| 5.56x45mm NATO (AP)         | high caliber | Tiny (15)  | 2d6     | Piercing    | Armor Piercing                 |
| 5.56x45mm NATO (AP+I)       | high caliber | Tiny (15)  | 2d6     | Piercing    | Armor Piercing, Incendiary (1) |
| .303 British (FMJ)          | high caliber | Tiny (15)  | 2d8     | Piercing    |                                |
| .303 British (JHP)          | high caliber | Tiny (10)  | 2d8     | Piercing    | Hollow Point                   |
| .303 British (AP)           | high caliber | Tiny (10)  | 2d8     | Piercing    | Armor Piercing                 |
| .303 British (AP+I)         | high caliber | Tiny (10)  | 2d8     | Piercing    | Armor Piercing, Incendiary (1) |
| 7.62x39mm USSR (FMJ)        | high caliber | Tiny (10)  | 3d6     | Piercing    |                                |
| 7.62x39mm USSR (JHP)        | high caliber | Tiny (10)  | 3d6     | Piercing    | Hollow Point                   |
| 7.62x39mm USSR (AP)         | high caliber | Tiny (10)  | 3d6     | Piercing    | Armor Piercing                 |
| 7.62x39mm USSR (AP+I)       | high caliber | Tiny (10)  | 3d6     | Piercing    | Armor Piercing, Incendiary (1) |
| 7.62x51mm NATO (FMJ)        | high caliber | Tiny (10)  | 3d6     | Piercing    |                                |
| 7.62x51mm NATO (JHP)        | high caliber | Tiny (10)  | 3d6     | Piercing    | Hollow Point                   |
| 7.62x51mm NATO (AP)         | high caliber | Tiny (10)  | 3d6     | Piercing    | Armor Piercing                 |
| 7.62x51mm NATO (AP+I)       | high caliber | Tiny (10)  | 3d6     | Piercing    | Armor Piercing, Incendiary (1) |
| 7.62x54mmR USSR (FMJ)       | high caliber | Small (15) | 3d8     | Piercing    |                                |
| 7.62x54mmR USSR (AP)        | high caliber | Small (15) | 3d8     | Piercing    | Armor Piercing                 |
| .338 Lapua (FMJ)            | high caliber | Small (15) | 3d10    | Piercing    |                                |
| .338 Lapua (JHP)            | high caliber | Small (15) | 3d10    | Piercing    | Hollow Point                   |
| .338 Lapua (AP)             | high caliber | Small (15) | 3d10    | Piercing    | Armor Piercing                 |
| .338 Lapua (AP+I)           | high caliber | Small (15) | 3d10    | Piercing    | Armor Piercing, Incendiary (1) |
| .50 BMG (FMJ)               | high caliber | Small (15) | 3d12    | Piercing    |                                |
| .50 BMG (AP)                | high caliber | Small (15) | 3d12    | Piercing    | Armor Piercing                 |
| .50 BMG (AP+I)              | high caliber | Small (15) | 3d12    | Piercing    | Armor Piercing, Incendiary (1) |
| Bottle Rocket               | high caliber | Small (30) | 2d6     | Force       | Explosive                      |
| 12/70 Birdshot              | shotshell    | Tiny (15)  | 1d6     | Piercing    |                                |
| 12/70 Buckshot              | shotshell    | Tiny (12)  | 1d12    | Piercing    |                                |
| 12/70 Full Slug             | shotshell    | Tiny (10)  | 2d6     | Piercing    |                                |
| 12/70 Sabot Slug            | shotshell    | Tiny (8)   | 2d8     | Piercing    | Armor Piercing                 |
| 12/70 Breach Slug           | shotshell    | Tiny (8)   | 2d4     | Piercing    |                                |
| 12/70 Flash Shot            | shotshell    | Tiny (12)  | 1d4     | Piercing    | Blinding (3)                   |
| 12/70 Beanbag               | shotshell    | Tint (12)  | 1d8     | Bludgeoning |                                |
| OG-7V Warhead               | shaped       | Medium     | 8d10    | Force       | Explosive                      |
| PG-7VL Warhead              | shaped       | Medium     | 12d10   | Force       | Explosive, Incendiary (1)      |
| 40mm High Explosive Grenade | shaped       | Small      | 4d8     | Force       | Explosive                      |
| 40mm Incendiary Grenade     | shaped       | Small      | 3d8     | Force       | Explosive, Incendiary (3)      |
| 40mm Non-Lethal Grenade     | shaped       | Small      | 3d6     | Force       | Explosive, Concussive (5)      |
| 40mm Smoke Grenade          | shaped       | Small      | -       | -           |                                |
| 15mm Firework Shell         | shaped       | Small      | 3d4     | Force       | Explosive, Incendiary (1)      |

### Energy Ammunition
| Title  | Base   | Size       | D. Dice | D. Type | Other          |
| ------ | ------ | ---------- | ------- | ------- | -------------- |
| Diesel | energy | Tiny (100) | 2d8     | Fire    | Incendiary (3) |
| Napalm | energy | Tiny (50)  | 3d6     | Fire    | Incendiary (5) |
