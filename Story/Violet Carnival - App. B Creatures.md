# Appendix B: Creatures

This appendix contains the full stat blocks for every named creature in *Vaelithra III: Violet Carnival*, referenced throughout *Parts I–IV*. The Inevitables who appear in the adventure's closing scene are narrative-only cameos and have no stat blocks here.

## Belgruth, The Grand Puppeteer (Phase 1)

The carnival's true master, disguised for decades as "Bel," a generous investor. Beneath its glamour, Belgruth is a demon of the **Little Sins** pantheon, feeding on abducted guests' souls and turning them into Gluttonettes. It opens the final battle in this human-like form, relying on charm and fear rather than brute strength.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Belgruth, The Grand Puppeteer
size: Medium
type: Fiend (Demon)
alignment: Chaotic Evil
cr: 8
ac: 16
hp: 170
hit_dice: 20d8+80
speed: 30ft
stats: [10,14,18,18,16,20]
saves:
  - CON: 7
  - INT: 7
  - WIS: 6
  - CHA: 8
skillsaves:
  - Deception: 8
  - Insight: 6
  - Performance: 8
  - Persuasion: 8
damage_resistances: Cold, Fire, Lightning; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks
damage_immunities: Poison
condition_immunities: Charmed, Exhaustion, Frightened, Poisoned
senses: Truesight 120 ft., Passive Perception 13
languages: Abyssal, Common, Telepathy 120 ft.
traits:
  - name: Magic Resistance
    desc: Belgruth has advantage on saving throws against spells and other magical effects.
  - name: Aura of Temptation (15 ft.)
    desc: Any hostile creature that starts its turn in this aura must succeed on a DC 16 Wisdom saving throw or have disadvantage on attack rolls and ability checks until the start of its next turn. On a success, the creature is immune to this aura for 24 hours.
  - name: Grand Puppeteer
    desc: As a bonus action, Belgruth commands up to three Gluttonettes within 60 feet that it can see; each can move up to its speed and make one attack.
  - name: Innate Spellcasting
    desc: "Belgruth's spellcasting ability is Charisma (spell save DC 16), requiring no material components. At will: detect thoughts, disguise self, minor illusion, suggestion. 3/day each: charm person, enthrall, hold person, phantasmal force, psychic lance. 1/day each: dominate person, mass suggestion."
  - name: Legendary Resistance (2/Day)
    desc: If Belgruth fails a saving throw, it can choose to succeed instead.
actions:
  - name: Multiattack
    desc: Belgruth makes two Draining Touch attacks.
  - name: Draining Touch
    desc: "Melee Spell Attack: +8 to hit, reach 5 ft. Hit: 12 (2d6 + 5) Psychic damage, and Belgruth regains hit points equal to the damage dealt."
  - name: Puppeteer's Gaze (Recharge 5-6)
    desc: One creature Belgruth can see within 60 feet must succeed on a DC 16 Wisdom saving throw or take 21 (6d6) Psychic damage and become Frightened for 1 minute, repeating the save at the end of each of its turns.
legendary_description: Belgruth can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature's turn. Belgruth regains spent legendary actions at the start of its turn.
legendary_actions:
  - name: Move
    desc: Belgruth moves up to its speed.
  - name: Command Gluttonette (Costs 1)
    desc: Belgruth commands one Gluttonette within 60 feet to make one attack.
  - name: Whisper of Doubt (Costs 2)
    desc: One creature Belgruth can see within 60 feet must succeed on a DC 16 Wisdom saving throw or have disadvantage on its next attack roll or ability check.
creature: Belgruth, The Grand Puppeteer
```

***Transformation.*** When reduced to 0 hit points, Belgruth does not die — it explodes with rotten energy and transforms into **Belgruth, The Ravenous Maw**, arriving at 40–50% of its new maximum hit points (see *Part IV: Into the Big Top* for the full transition).

## Belgruth, The Ravenous Maw (Phase 2)

Belgruth's true form, unleashed once its human disguise is stripped away. Larger, faster, and far more dangerous, it fights now to devour rather than manipulate.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Belgruth, The Ravenous Maw
size: Large
type: Fiend (Demon)
alignment: Chaotic Evil
cr: 10
ac: 17
hp: 220
hit_dice: 20d10+110
speed: 40ft, climb 30ft
stats: [22,10,24,14,12,20]
saves:
  - STR: 10
  - CON: 11
  - WIS: 5
  - CHA: 9
skillsaves:
  - Athletics: 10
  - Intimidation: 9
  - Perception: 5
damage_resistances: Cold, Fire, Lightning; Bludgeoning, Piercing, and Slashing from Nonmagical Attacks
damage_immunities: Poison
condition_immunities: Charmed, Exhaustion, Frightened, Poisoned, Restrained
senses: Truesight 120 ft., Passive Perception 15
languages: Abyssal, Common, Telepathy 120 ft.
traits:
  - name: Magic Resistance
    desc: Belgruth has advantage on saving throws against spells and other magical effects.
  - name: Aura of Despair (30 ft.)
    desc: Any hostile creature that starts its turn in this aura must succeed on a DC 17 Wisdom saving throw or be Frightened until the start of its next turn. On a success, the creature is immune to this aura for 24 hours.
  - name: Devouring Maw
    desc: Belgruth's attacks deal an extra 3 (1d6) Psychic damage against Frightened targets.
  - name: Legendary Resistance (2/Day)
    desc: If Belgruth fails a saving throw, it can choose to succeed instead.
  - name: Soul Consumption
    desc: When a humanoid within 30 feet of Belgruth is reduced to 0 hit points, Belgruth gains 20 temporary hit points.
actions:
  - name: Multiattack
    desc: Belgruth makes three attacks - one Claw, one Tongue Lash, and one Gnashing Bite.
  - name: Claw
    desc: "Melee Weapon Attack: +10 to hit, reach 10 ft. Hit: 15 (2d8 + 6) Slashing damage."
  - name: Tongue Lash
    desc: "Melee Weapon Attack: +10 to hit, reach 15 ft. Hit: 13 (2d6 + 6) Bludgeoning damage plus 7 (2d6) Acid damage. A Large or smaller target is grappled (escape DC 18); until the grapple ends, Belgruth can't use Tongue Lash on another target."
  - name: Gnashing Bite
    desc: "Melee Weapon Attack: +10 to hit, reach 5 ft., one grappled creature. Hit: 19 (3d8 + 6) Piercing damage plus 10 (3d6) Psychic damage. If this reduces the target to 0 hit points, it is swallowed: blinded, restrained, has total cover against outside attacks, and takes 10 (3d6) Acid damage at the start of each of Belgruth's turns. If Belgruth takes 30+ damage in a single turn from a creature inside it, Belgruth must succeed on a DC 15 Constitution save or regurgitate all swallowed creatures, which land prone. A swallowed creature can escape with 15 feet of movement if Belgruth dies."
  - name: Belly Burst (Recharge 4-6)
    desc: Each creature within a 20-foot radius must succeed on a DC 17 Dexterity saving throw or take 28 (8d6) Psychic damage and be pushed 10 feet; half damage and no push on a success.
legendary_description: Belgruth can take 3 legendary actions, choosing from the options below. Only one legendary action can be used at a time and only at the end of another creature's turn. Belgruth regains spent legendary actions at the start of its turn.
legendary_actions:
  - name: Move
    desc: Belgruth moves up to its speed.
  - name: Slam (Costs 1)
    desc: Belgruth makes one Claw attack.
  - name: Gorge (Costs 2)
    desc: Belgruth uses Gnashing Bite.
creature: Belgruth, The Ravenous Maw
```

## Juval Garnix, The Withered Dalang

The carnival's gaunt puppeteer, hollowed out by grief and Belgruth's manipulation into accepting a demon's bargain to save his failing carnival. Encountered first as an unnamed figure at the gate in *Part II*, then again — immovable, aching — at the Dalang's Final Gate in *Part IV*.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Juval Garnix, The Withered Dalang
size: Medium
type: Humanoid (Human)
alignment: Chaotic Neutral
cr: 7
ac: 15
hp: 104
hit_dice: 16d8+32
speed: 30ft
stats: [8,14,14,12,16,18]
saves:
  - WIS: 6
  - CHA: 7
skillsaves:
  - Deception: 7
  - Insight: 6
  - Performance: 7
  - Persuasion: 7
  - Arcana: 4
damage_resistances: Psychic
senses: Passive Perception 13
languages: Common, Elvish, Sylvan
traits:
  - name: Spellcasting
    desc: "Juval is a 7th-level warlock (spell save DC 15, +7 to hit with spell attacks). Cantrips: eldritch blast (2 beams), minor illusion, friends. 1st-3rd level (2 4th-level slots): charm person, faerie fire, hold person, misty step, hypnotic pattern, counterspell, fear. 4th level: blight, phantasmal killer."
  - name: Eldritch Invocations
    desc: Agonizing Blast (adds Charisma modifier to eldritch blast damage); Misty Visions (casts silent image at will); Mask of Many Faces (casts disguise self at will).
  - name: Fey Presence (1/Rest)
    desc: As a bonus action, each creature in a 10-foot cube originating from Juval must succeed on a DC 15 Wisdom saving throw or be Charmed or Frightened until the end of Juval's next turn.
  - name: Withered Heart
    desc: Juval has disadvantage on saving throws against being Frightened, but if he succeeds on such a save, he can react to cast a spell he knows without expending a spell slot.
  - name: Echo of Vaelithra (1/Rest)
    desc: Juval grants advantage on the next attack roll, saving throw, or ability check made by one creature within 30 feet of him.
actions:
  - name: Dagger
    desc: "Melee or Ranged Weapon Attack: +5 to hit, reach 5 ft. or range 20/60 ft. Hit: 4 (1d4 + 2) Piercing damage."
  - name: Eldritch Blast
    desc: "Ranged Spell Attack: +7 to hit, range 120 ft. Hit: 1d10 + 4 Force damage per beam (2 beams)."
creature: Juval Garnix, The Withered Dalang
```

## Sylvia Garnix, The Beacon of Fading Hope

Juval's wife, abducted by Belgruth and chained to the Old Stage as leverage against him. This stat block represents her strength at full power — before her capture, or once freed and restored mid-fight; during most of the adventure she appears only chained and at 0 hit points.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Sylvia Garnix, The Beacon of Fading Hope
size: Medium
type: Humanoid (Half-Elf)
alignment: Lawful Good
cr: 4
ac: 16
hp: 68
hit_dice: 12d8+12
speed: 30ft
stats: [10,12,12,10,18,14]
saves:
  - WIS: 7
  - CHA: 5
skillsaves:
  - Insight: 7
  - Medicine: 7
  - Persuasion: 5
senses: Darkvision 60 ft., Passive Perception 14
languages: Common, Elvish
traits:
  - name: Fey Ancestry
    desc: Sylvia has advantage on saving throws against being Charmed, and magic can't put her to sleep.
  - name: Spellcasting
    desc: "Sylvia is an 8th-level cleric (spell save DC 15, +7 to hit with spell attacks). Cantrips: guidance, light, sacred flame, thaumaturgy. 1st level (4 slots): bless, cure wounds, guiding bolt, shield of faith. 2nd level (3 slots): aid, hold person, spiritual weapon. 3rd level (3 slots): beacon of hope, dispel magic, spirit guardians. 4th level (2 slots): death ward, guardian of faith."
  - name: Disciple of Life
    desc: Sylvia's healing spells restore additional hit points equal to 2 plus the spell's level.
  - name: Channel Divinity - Preserve Life (1/Rest)
    desc: Sylvia can distribute 40 hit points among creatures within 30 feet, up to half a creature's hit point maximum.
actions:
  - name: Mace
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft. Hit: 4 (1d6 + 1) Bludgeoning damage."
creature: Sylvia Garnix, The Beacon of Fading Hope
```

## Varquin, The Whispering Oracle

A human Vaelithra bound within the demiplane Belgruth created, unable to act openly against it. She guides the party through symbol and riddle throughout the carnival, gives away half her own power to help Juval, and can intervene once, at great cost, if the final battle turns against the party.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Varquin, The Whispering Oracle
size: Medium
type: Humanoid (Half-Elf)
alignment: Chaotic Good
cr: 8
ac: 15
hp: 104
hit_dice: 16d8+32
speed: 30ft
stats: [8,16,14,12,16,20]
saves:
  - DEX: 6
  - WIS: 6
  - CHA: 8
skillsaves:
  - Deception: 8
  - Insight: 6
  - Performance: 8
  - Persuasion: 8
  - Arcana: 4
  - Stealth: 6
condition_immunities: Charmed, Frightened
senses: Darkvision 60 ft., Passive Perception 13
languages: Common, Elvish, Sylvan
traits:
  - name: Fey Ancestry
    desc: Varquin has advantage on saving throws against being Charmed, and magic can't put her to sleep.
  - name: Spellcasting
    desc: "Varquin is a 10th-level bard (spell save DC 16, +8 to hit with spell attacks). Cantrips: vicious mockery, minor illusion, prestidigitation, mage hand. 1st level (4 slots): charm person, comprehend languages, healing word, sleep. 2nd level (3 slots): calm emotions, hold person, phantasmal force. 3rd level (3 slots): hypnotic pattern, major image, dispel magic. 4th level (3 slots): confusion, dimension door. 5th level (2 slots): dominate person, scrying."
  - name: Bardic Inspiration (5/Day)
    desc: As a bonus action, Varquin gives one creature within 60 feet a Bardic Inspiration die (1d8), usable within the next 10 minutes.
  - name: Cutting Words (5/Day)
    desc: As a reaction when a creature Varquin can see within 60 feet makes an attack roll, ability check, or damage roll, Varquin can expend a Bardic Inspiration die and subtract it from that roll.
  - name: Vaelithra's Echo (1/Rest)
    desc: Each creature in a 15-foot cube within 60 feet of Varquin must succeed on a DC 16 Wisdom saving throw or be Charmed or Frightened until the end of its next turn. On a success, the creature is immune to this effect for 24 hours.
actions:
  - name: Dagger
    desc: "Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 20/60 ft. Hit: 5 (1d4 + 3) Piercing damage."
creature: Varquin, The Whispering Oracle
```

## Juval Simulacrum, The Masked Puppet

A construct animated by a fragment of Varquin's own power, given to Juval so she could guide the party through the carnival without acting openly herself. It appears briefly during the carousel puzzle in *Part II*, and can optionally join Belgruth's side as reinforcement in the final battle if the DM wants a longer fight (see *Part IV*).

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Juval Simulacrum, The Masked Puppet
size: Medium
type: Construct
alignment: Chaotic Evil
cr: 3
ac: 14
hp: 91
hit_dice: 14d8+28
speed: 30ft
stats: [14,12,14,8,12,14]
skillsaves:
  - Perception: 3
  - Deception: 4
damage_resistances: Psychic
condition_immunities: Charmed, Exhaustion, Frightened, Poisoned
senses: Darkvision 60 ft., Passive Perception 13
languages: Understands Common and Abyssal but can't speak, Telepathy 60 ft. (with controller only)
traits:
  - name: Controlled by Juval
    desc: As a bonus action, Juval can command the Simulacrum if within 120 feet. It becomes inert if Juval is incapacitated or moves more than 120 feet away.
  - name: Mask of Illusions
    desc: The Simulacrum can cast minor illusion at will.
  - name: Fading Charm
    desc: Each creature within 10 feet that starts its turn there must succeed on a DC 12 Wisdom saving throw or have disadvantage on its next attack roll.
  - name: Gluttonous Nature
    desc: When a creature within 30 feet is reduced to 0 hit points, the Simulacrum regains 10 hit points.
actions:
  - name: Multiattack
    desc: The Simulacrum makes two Slam attacks.
  - name: Slam
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft. Hit: 7 (1d8 + 3) Bludgeoning damage plus 5 (1d10) Psychic damage."
  - name: Whisper of Doubt
    desc: As a bonus action, one creature within 30 feet must succeed on a DC 12 Wisdom saving throw or have disadvantage on its next saving throw against a spell or magical effect.
creature: Juval Simulacrum, The Masked Puppet
```

## Gluttonette, Tier 1 (The Ravenous Shadow)

Constructs made from consumed souls, wandering the carnival as guards and reinforcements. All three tiers share the same origin and general appearance — masked, silent, faintly wrong — differing mainly in age and strength.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Gluttonette, Tier 1 (The Ravenous Shadow)
size: Medium
type: Construct
alignment: Chaotic Evil
cr: 1
ac: 13
hp: 85
hit_dice: 10d8+40
speed: 30ft
stats: [14,10,18,6,10,8]
damage_resistances: Psychic
condition_immunities: Charmed, Exhaustion, Frightened, Poisoned
senses: Darkvision 60 ft., Passive Perception 12
languages: Understands Common but can't speak
traits:
  - name: Memory Drain
    desc: When the Gluttonette hits a creature with a melee attack, that creature must succeed on a DC 13 Wisdom saving throw or have disadvantage on its next attack roll or ability check.
actions:
  - name: Multiattack
    desc: The Gluttonette makes two Slam attacks.
  - name: Slam
    desc: "Melee Weapon Attack: +4 to hit, reach 5 ft. Hit: 9 (1d8 + 5) Bludgeoning damage plus 7 (2d6) Psychic damage."
  - name: Echoing Wail (Recharge 6)
    desc: Each creature within 15 feet must succeed on a DC 13 Wisdom saving throw or be Frightened until the end of its next turn.
creature: Gluttonette, Tier 1 (The Ravenous Shadow)
```

## Gluttonette, Tier 2 (The Hungry Husk)

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Gluttonette, Tier 2 (The Hungry Husk)
size: Medium
type: Construct
alignment: Chaotic Evil
cr: 1
ac: 12
hp: 78
hit_dice: 12d8+24
speed: 30ft
stats: [12,10,14,6,10,8]
damage_resistances: Psychic
condition_immunities: Charmed, Exhaustion, Frightened, Poisoned
senses: Darkvision 60 ft., Passive Perception 12
languages: Understands Common but can't speak
traits:
  - name: Lingering Hunger
    desc: A creature damaged by the Gluttonette has its speed reduced by 10 feet until the end of its next turn. This effect doesn't stack.
actions:
  - name: Suffocating Embrace
    desc: "Melee Weapon Attack: +3 to hit, reach 5 ft. Hit: 6 (1d8 + 2) Bludgeoning damage plus 3 (1d6) Necrotic damage. A Medium or smaller target is grappled (escape DC 12)."
creature: Gluttonette, Tier 2 (The Hungry Husk)
```

## Gluttonette, Tier 3 (The Fading Echo)

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Gluttonette, Tier 3 (The Fading Echo)
size: Medium
type: Construct
alignment: Chaotic Evil
cr: 1
ac: 11
hp: 65
hit_dice: 10d8+20
speed: 30ft
stats: [10,10,12,6,10,8]
damage_resistances: Psychic
condition_immunities: Charmed, Exhaustion, Frightened, Poisoned
senses: Darkvision 60 ft., Passive Perception 12
languages: Understands Common but can't speak
traits:
  - name: Ephemeral Presence
    desc: When the Gluttonette dies, each creature within 10 feet must succeed on a DC 11 Constitution saving throw or take 7 (2d6) Psychic damage; half damage on a success.
actions:
  - name: Soul Shiver
    desc: "Melee Spell Attack: +3 to hit, reach 5 ft. Hit: 10 (3d6) Psychic damage."
creature: Gluttonette, Tier 3 (The Fading Echo)
```

## Mr. Smiley Hat

The carnival's gatekeeper, jerky and mechanical in his movements, his hat's grin never changing. He greets every arrival with sugary warmth and validates their ticket through the Bite Ritual described in *Part I: The Invitation*. He is not a combatant and has no stake in Belgruth's schemes beyond his role — he simply performs it, endlessly.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Mr. Smiley Hat
size: Medium
type: Construct
alignment: Neutral
cr: 1/2
ac: 13
hp: 33
hit_dice: 6d8+6
speed: 30ft
stats: [10,16,12,10,12,14]
skillsaves:
  - Deception: 4
  - Performance: 4
condition_immunities: Charmed, Frightened
senses: Darkvision 60 ft., Passive Perception 11
languages: Common
traits:
  - name: Ticket Sense
    desc: Mr. Smiley Hat instinctively knows the number of bite marks remaining on any ticket he examines, and whether it was issued by the Violet Carnival.
  - name: Uncanny Reflexes
    desc: Mr. Smiley Hat has advantage on Dexterity saving throws.
actions:
  - name: Multiattack
    desc: Mr. Smiley Hat makes two Sharp Bite attacks.
  - name: Sharp Bite
    desc: "Melee Weapon Attack: +5 to hit, reach 5 ft. Hit: 7 (1d8 + 3) Piercing damage."
creature: Mr. Smiley Hat
```

## Old Man Thoraq

A one-legged old man who keeps the Giant Snail Race, cheerfully unaware of the true purpose behind the vision-sequence his snails deliver each round. He is entirely harmless, included here only for completeness — the DM should never need to roll for him.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Old Man Thoraq
size: Medium
type: Humanoid (Human)
alignment: Neutral Good
cr: 0
ac: 10
hp: 11
hit_dice: 2d8+2
speed: 20ft
stats: [8,8,12,10,12,10]
skillsaves:
  - Animal Handling: 3
  - Performance: 2
senses: Passive Perception 11
languages: Common
traits:
  - name: Snail Whisperer
    desc: Thoraq has advantage on Wisdom (Animal Handling) checks made to direct giant snails.
actions:
  - name: Crutch
    desc: "Melee Weapon Attack: +1 to hit, reach 5 ft. Hit: 2 (1d4) Bludgeoning damage."
creature: Old Man Thoraq
```

## Miss Lilith

Keeper of the carousel, absent from her booth throughout *Part II* — the party never actually meets her, and her disappearance is never explained within the adventure. Her stat block is provided for DMs who want to bring her into a scene directly, or use her as a hook for a future adventure.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Miss Lilith
size: Medium
type: Humanoid (Human)
alignment: Unaligned
cr: 1
ac: 12
hp: 27
hit_dice: 5d8+5
speed: 30ft
stats: [10,12,12,14,14,16]
skillsaves:
  - Deception: 5
  - Performance: 5
  - Insight: 4
senses: Passive Perception 12
languages: Common, Sylvan
traits:
  - name: Carnival-Bound
    desc: Miss Lilith cannot willingly leave the grounds of the Violet Carnival; the nature of this binding is left to the DM to determine.
actions:
  - name: Dagger
    desc: "Melee or Ranged Weapon Attack: +3 to hit, reach 5 ft. or range 20/60 ft. Hit: 4 (1d4 + 2) Piercing damage."
creature: Miss Lilith
```

## Whispering Lady Dima

Known to the party as **Nyonya Bisik**, a memory-residue haunting the Tunnel of Echoing Memories rather than a living being — more echo than person, worn thin by endless repetition. She poses no threat and cannot be meaningfully fought; her stat block exists only so the DM has numbers on hand if a table forces the issue.

```statblock
layout: Basic 5e Layout
source: Vaelithra III - Violet Carnival
name: Whispering Lady Dima (Nyonya Bisik)
size: Medium
type: Undead
alignment: Unaligned
cr: 0
ac: 10
hp: 1
hit_dice: 1d8-3
speed: 0ft
stats: [1,10,4,10,12,10]
damage_immunities: Poison, Psychic
condition_immunities: Charmed, Frightened, Poisoned, Prone, Restrained
senses: Darkvision 60 ft., Passive Perception 11
languages: Understands Common but speaks only in fragments
traits:
  - name: Memory Residue
    desc: Dima cannot move from the Tunnel of Echoing Memories and cannot take actions other than speaking. She cannot be targeted by attacks that require a physical form to matter, at the DM's discretion, and effectively cannot be destroyed through ordinary means.
creature: Whispering Lady Dima (Nyonya Bisik)
```
