# Paths and Abilities

Progression, Paths and archetypes, the finalized abilities and the ability triage. Every Path ability is also filed in the Ability Catalog tab.

## Progression and archetypes

There are no classes: leveling grants points spent on skills and abilities from a progression tree across three Paths, and archetypes are loose identities to guide conventional players, not class names. (Established)

**Path tree shape (Inspiration 2026-10-21: the creator's reference image guides the shape but does not set its limits; the finished tree will be much denser; details Open).** All three Paths grow from one shared root as a single tree: Sword on one side, Sorcerer through the center, Wanderer on the other. Each Path's branches split as they rise and pass through five tiers that cut across every Path: Tier I Foundation, Tier II Advanced, Tier III Specialization, Tier IV Expert, Tier V Master. Abilities in the same tier are of similar strength whatever their branch. Node types: ability nodes (some unlock directly, some offer a choice of one); convergence nodes, which require abilities from more than one Path; Path branches (progression within a Path); and cross-Path links, which unlock once prerequisites from different Paths are met. A single capstone above Tier V draws on all three Paths. Open: how a tier is entered, node costs, whether choice-of-one nodes apply to Momentum abilities, how many nodes each Path holds, and what the capstone is.

**Tier entry: two layers (Draft 2026-10-21, the working assumption for now).** Layer 1 is the layout: you can buy a node only if it connects to one you already own (the node beneath it on its branch, or a cross-Path link or convergence node whose requirements you meet), and node cost rises with tier and node size. Layer 1 is identical across all three Paths, so a tier means the same thing everywhere in the tree. Layer 2 is character prerequisites written on each node: attribute thresholds, specific earlier abilities, or abilities from two Paths for convergence nodes. Path flavor lives in Layer 2, and nodes needing an attribute above the XP ceiling are reachable only through in-world means. Tiers themselves carry no attribute gate, since each Path keys on different attributes. Proposed alongside it: two node sizes, minor nodes (gain triggers, small bonuses, tweaks; cheaper) and major nodes (Holds, Releases, Crest Releases and full abilities); choice-of-one nodes reserved for naturally exclusive choices (as Fight or Flight already is) and never used for Momentum abilities; every ability written with Path, branch, tier, node size, cost and prerequisites so an interactive tree can be generated later. A breadth gate (points spent in a Path before entering its next tier) is held back as a fallback if sims show beelining.

**Ability data fields (Established 2026-10-21).** Every ability is filed with these fields, diligently and accurately:

- **Identity:** ID, name, status (Established / Draft / Proposed / Open), origin (5e source or former Doctrine), flavor line.
- **Placement (Layer 1):** Path, branch, tier, node size, connections (the node beneath, plus any cross-Path links).
- **Requirements (Layer 2):** attribute thresholds, required abilities, convergence requirements.
- **Cost:** XP cost; resource cost (Momentum, Tempo or Grit, and whether it prompts the Expression Die); uses and refresh (per Brief, Short or Long Rest).
- **Rules:** action type (Major, Minor, reaction), Instant or Committed and its completion condition, trigger, target and range, effect, duration, failure or interruption, interactions.
- **Tags:** Gain, Hold, Release, Crest; conditions applied; weapon or style keywords.
- **Tracking:** design intent, sim status, decision-log date, change history.

Placement, cost and rules are the minimum for an ability to count as filed.

**Minor and major node definitions (Established 2026-10-21).** Test: does it give you something new to do at the table? A minor node modifies something you already have or adds a gain trigger; it adds no new action or reaction, fits in one or two lines, carries no attribute prerequisite beyond its connection, and costs less. A major node grants a new option (action, reaction, Hold, Release, Crest Release or stance) or a defining passive; it is written on the full template, can carry Layer 2 prerequisites, and sets its tier's strength benchmark.

**Martial branch layout (2026-10-21).** Grapple and Bow move from Sword to Wanderer (Established): grappling isn't martial in the same way the rest of Sword is, and archery joins Wanderer's hunter abilities. Working layout (Draft, pending the holistic review of all three Paths), with trunks that fork around Tier III:

- **Sword, Havoc** (Breaker + Frenzy; bridge: Blow for Blow; Brutal Critical once crits are decided). Forks: **Breaker** (Shattered, Sundering, Ruin, Splinter, the break-Guard gains) and **Fury** (Frenzy, Unending Frenzy, Focused Frenzy, Visage of Frenzy, Blood for Blood).
- **Sword, Onslaught** (Vanguard + Thrown; trunk: Break the Line, Relentless Advance). Forks: **Charge** (Immovable, Rolling Thunder, Battering Ram, Breach, charge and collision gains) and **Throw** (Quick Arm, Staggering Throw, Spear-Breaker, Hard on the Heels, throw-and-close gain).
- **Sword, The Line** (Bulwark + Warlord). Forks: **Shield** (Iron Hide, Shield Wall, Stand Before, Iron Will, Standfast, Warding Strike, Blood for Another, Fight or Flight, defensive gains) and **Banner** (Press, Steady, War Cry, Feed the Wolves, Command, Spur to Strike, Call to Stand, No Step Back, Warlord gains).
- **Wanderer, Grapple** (Arripe, Pin, Clinch, Iron Grip, Hold It Down, Headbutt, Slam, Throttle, held-through gain).
- **Wanderer, Hunter** (Ironstring content: Draw Weight, Bodkin, Full Draw, Pinning Shot, consecutive-hit gain; alongside Hunter's Mark, First Blood and Blood in the Water).

Notes: Wanderer now holds Momentum abilities, which free combination allows; the merged break-Guard gain sits in Havoc and ranged builds reach it across Paths; Ebb and Flow waits for the Tempo review (likely Wanderer); Witchbane stays a Sword–Sorcerer convergence node. Supersedes the seven-branch Sword skeleton (Proposed).

### Paths (Established)

| Path | Role |
| --- | --- |
| Sword | Martial combat: discipline, battlefield control, sacrifice, leadership, relentless aggression |
| Sorcerer | Magic, rituals, the dead and forbidden forces |
| Wanderer | Utility useful to any build: hunting, opportunism, mobility, survival, tactics |

Players build roles (tank, damage, support) by combining abilities from any Path. Proposed but unconfirmed: 1 Ability Point per level; abilities requiring prior investment in a Path; a cap on off-Path spending.

### Archetypes (Established 2026-10-24 as creative organization)

Archetypes are creative signposts inside the Paths, not classes, mandatory subtypes or tree gates; where an ability sits comes from the Path tree. All martials share one combat language with light asymmetry. Havoc was named Ruin until 2026-10-24.

| Path | Archetype (subtypes) | Fantasy | Tree home |
| --- | --- | --- | --- |
| Sword | Havoc (Breaker, Frenzy) | Breaks: decisive impact and escalating violence | Havoc trunk (Breaker and Fury forks) |
| Sword | Onslaught (Vanguard, Thrown) | Closes distance violently | Onslaught trunk (Charge and Throw forks) |
| Sword | The Line (Bulwark, Warlord) | Holds ground and commands | The Line trunk (Shield and Banner forks) |
| Sword | Armsmaster (unsplit) | Perfects technique: timing, reach, counters | Not yet placed |
| Sorcerer | Sorcerer, Warlock, Hexer / Ritualist, Veilwalker | See Mage archetypes below | Sorcerer Path (tree Open) |
| Wanderer | Cutthroat | The unfair fight: ambush, opportunism, precision | Not yet placed |
| Wanderer | Wayfarer | Mastery of hostile ground | Not yet placed |
| Wanderer | Alchemist | Equal exchange: remedies, poisons, crafted tools | Not yet placed; formulas and crafted items |
| Wanderer | Ranged disciplines: bows, crossbows, great bows (Marksman grouping Proposed) | Deliberate craft at distance | Hunter branch (former Ironstring content) |
| Wanderer, may cross into Sword | Grappler | Controlling a dangerous body: grappling, Arripe, unarmed strikes | Grapple branch; Sword × Wanderer convergence nodes allowed |

Primal Mystic and Ascetic are speculative concepts (Open), not archetypes; either might later emerge as a cross-path expression. Other cross-path fantasies (Pactblade, Witchfinder, Dreamstalker, combat medic, Chef / Provisioner and similar) are Proposed inspiration only. Direction cards for every archetype are in project file 03.

A separate "Aim" resource for archers was proposed early, then effectively replaced by Focus and Tempo. (Open)

### Mage archetypes (Established)

Magic is more tightly legislated than martial options: each archetype owns its domains, and others are hard or forbidden to reach.

| Archetype | Price of power | Casting system | Domains (Proposed) |
| --- | --- | --- | --- |
| Sorcerer | Self: madness, loss of identity | Creative casting; no spell list | Fire, Storm, Frost, Stone, Decay |
| Warlock | The bargain: a price the player chooses (blood, pain, sensation, service, memory, identity and so on) | Fixed invocations + limited creative casting, paid through the bargain | Example patrons, not a taxonomy: The Dead, The Deep, The Beast, The Crown, The Watchers |
| Hexer / Ritualist | Time and preparation | Structured: rituals, hexes, wards, bindings | Curses, Wards, Names, Blood, Omens |
| Veilwalker | Certainty: detachment from reality | Structured "Veil techniques" | Dreams, Memory, Reflections, Distance, Spirits, Shadows |

Key decisions:

- The Hexer/Ritualist absorbs the "learned" mage, because Asloria's institutions are gone. (Established)
- The Veilwalker merges illusionist, dreamer and spirit-binder: magic of what lies between. (Established)
- Sorcerers and Warlocks use creative casting; the Sorcerer specializes in it, the Warlock blends it with invocations. (Established)
- Two or three casting systems shared between similar archetypes, not four. (Established direction)
- Making **Death** its own domain was proposed, given the necromancy abilities. (Open)

**Archetype changes (Established 2026-10-24).** Warlocks share one bargain framework; each player chooses and combines their own prices and gifts within the eventual rules, and there are no mandatory Warlock subtypes. Blood and pain are one price among many, and patrons are examples, not a fixed list. The Alchemist moved to the Wanderer (see Archetypes above). The Ascetic is no longer a planned archetype; it stays a speculative concept that might emerge from Sorcerer + Sword or Sorcerer + Wanderer, and faith is never assumed to earn divine favor.

**Invocations as tree nodes (Proposed 2026-10-25; tabled until the Warlock bargain framework exists).** Eldritch Invocations is not built as a single ability. Each invocation is a node on the Warlock side of the Sorcerer Path, mostly minor nodes with a few major ones, bought with XP and paired with a price. Invocations that required a pact boon in 5e would take a Layer 2 prerequisite on a Dark Covenant boon (SO-001), which gives the boons a mechanical job. Candidate conversions for later, none approved: sight in unnatural darkness (from Devil's Sight), a stolen face (from Mask of Many Faces), reading what was never meant to be read (from Eyes of the Rune Keeper). Whispers of the Grave overlaps Voices Beyond the Veil (SO-003) and is not carried forward.

### Creative casting (Draft)

Sorcerers know Domains, not spells: a Fire Sorcerer can ignite, blind with sparks, heat metal or raise a wall of flame. The player describes the effect; the GM sets difficulty, cost and risk. Bigger effects generate more **Instability**; high Instability causes strange effects, madness (Clarity progression) and miscasts. Authority sets how much Instability a Sorcerer can withstand.

An earlier proposal from the first chat, "The Wound and the Will," used spell tags (Ash, Blood, Fear, Memory and so on), a casting check, combined tags at higher DCs, tag mastery, and a 0–10 Corruption track. Its tags overlap with the newer Domains. (Proposed)

### Archetype-specific cost tracks (Proposed)

- Sorcerer: **Instability**
- Warlock: **Blood Debt** (name and scope to revisit now that prices vary)
- Veilwalker: **Veil Taint** or Veil Exposure
- Ascetic (speculative concept, not an archetype): **Conviction**

### Other progression elements (Open)

Fighting Styles, Fighting Maneuvers and Maneuver Dice exist in rules text but are undesigned. Settled: Maneuver Die improvements are a scaling feature inside abilities that use the die. Maneuver Dice are now Expression Dice (Established 2026-10-21): when an Expression or ability prompts the Expression Die, you roll it, and its size comes from your highest of Vigor, Might and Poise, so hybrid builds aren't penalized. It is physical-only (Momentum, Tempo, Grit); mental Expressions operate separately. It graduates d4 → d6 → d8 for now (Established 2026-10-21); breakpoints (Established 2026-10-21), using your highest of Vigor, Might and Poise: below 50, no die is rolled and the Expression Die counts as a flat +1; 50–69, d4; 70–85, d6 (moved up from 66 on 2026-10-21 to match Hold II's Might 70); 86 and up, d8. Hold II stays at Might 70 (Established 2026-10-21). Backgrounds and feats are referenced but not built.

## Finalized abilities

Twenty-eight abilities from the 5e Keep list were converted into originals and approved; this is their latest rules text. Path labels marked "(assigned)" were never stated in the chats and are my best placement. Several still use 5e terms (Proficiency Bonus, Dash, Disengage, bonus action) that need converting.

| Ability | Path | Converted from (5e) |
| --- | --- | --- |
| Frenzy | Sword | Rage |
| Unending Frenzy | Sword | Relentless Rage |
| Focused Frenzy | Sword | Persistent Rage |
| Visage of Frenzy | Sword | Intimidating Presence |
| Blow for Blow | Sword | Reckless Attack |
| Extra Attack | Sword | Extra Attack |
| Brutal Critical | Sword | Brutal Critical |
| Call to Stand | Sword (assigned) | Rallying Cry |
| Warding Strike | Sword | Hold the Line |
| Fight or Flight | Sword | Defensive Tactics |
| Spur to Strike | Sword or Wanderer | Inspiring Surge |
| Witchbane | Sword or Wanderer | Magic User Nemesis |
| Blood for Blood | Sword | Retaliation |
| No Step Back | Sword | Bulwark |
| Break the Line | Sword | Ferocious Charger |
| Standfast | Sword | Vigilant Defender |
| Ebb and Flow | Sword | Fancy Footwork |
| Blood for Another | Sword | Warding Maneuver |
| Cut and Run | Wanderer (assigned) | Cunning Action |
| Bait and Switch | Wanderer | Misdirection |
| Opening Strike | Wanderer | Ambush Master |
| Hunter's Mark | Wanderer | Hunter's Prey |
| Blood in the Water | Wanderer | Slayer's Prey |
| First Blood | Wanderer | Assassinate |
| Dark Covenant | Sorcerer (assigned) | Pact Boon |
| Revenant Elegy | Sorcerer | Accursed Specter |
| Voices Beyond the Veil | Sorcerer | Undead Thralls |
| Speak the Old Laws | Sorcerer | Command Undead |

### Sword Path

**Frenzy** — *Less man than momentum.* Enter only when blood is drawn: you took damage, or a creature within 5 ft did. For 1 minute: +2 melee damage with Might weapons; resistance to bludgeoning, piercing and slashing; +1d4 to Might checks and saves; no spells, ranged weapons or concentration. Ends early if you finish a turn without attacking or taking damage. Twice per Long Rest. **Frenzy Fatigue:** when it ends, gain 1 level of Fatigue or take 1d6 irreducible damage.

**Unending Frenzy** — While in Frenzy and reduced to 0 HP but not killed, make a Fortitude save (DC 10); on a success you drop to 1 HP instead and Frenzy continues. The DC rises by 3 per use before a rest (10, 13, 16, 19, …), climbing the hazard ladder from Minor to Deadly. Not in heavy armor. Each use gives 1 level of Fatigue and 1 Bleeding.

**Focused Frenzy** — *A furnace, not a wildfire.* At the start of your turn, sustain Frenzy without having attacked or been hit by choosing: **Willful Sustain** (a Fortitude or Will save, your choice, DC 10, +1 DC per consecutive round) or **Blood Sacrifice** (take 1d4 irreducible damage).

**Visage of Frenzy** — Minor action, once per Short Rest. One creature within 30 ft that can see and hear you makes a Courage save (DC 10 + Presence + Might) or for 1 minute it cannot take reactions, is Frightened of you (−2 to attacks, tests one tier harder, can't willingly move closer). It repeats the save at the end of each of its turns. A creature that succeeds is immune until your next rest. Usable in or out of Frenzy.

**Blow for Blow** — Requires a melee weapon. Gain advantage on your next melee attack this turn; until your next turn, attacks against you have advantage. No armor restriction, no use limit.

**Extra Attack** — (Removed for now, 2026-10-21; disregard.) Name kept because it is clear and familiar. When you take the Attack action, attack twice. Rules text was never written; you expect to revisit it.

**Brutal Critical** — When you score a critical hit with a melee weapon, roll one additional weapon damage die. Stacks with other effects that add dice. Extra crit damage is reserved for abilities like this.

**Call to Stand** — Once per Short Rest, when you regain HP from a Sword or Wanderer Path healing effect, cry out to up to 3 allies within 60 ft who can hear and understand you. Each chooses: temporary HP equal to your Presence + Vigor modifiers (minimum 1), an immediate save to end Frightened, or reduce fatigue by one level. Each also gains +1d4 on their next attack or save within 1 minute. Not usable while silenced, gagged or unconscious.

**Warding Strike** — Reaction, once per turn, when a hostile creature moves within 5 ft: make a melee weapon attack. On a hit it makes a Footing save (DC 10 + Might + Poise) or it is Impaled until its next turn; if it is below max HP, it also gains Bleeding.

**Fight or Flight** — Choose one permanently when gained. **Fight** (heavy armor only): when hit by a melee attack, +4 to Armor until your next turn. **Flight** (no heavy armor): opportunity attacks you provoke have disadvantage.

**Spur to Strike** — Minor action, once per Short Rest. Up to 3 allies within 60 ft who hear and understand you may each immediately use their reaction to make one weapon attack. *"Steel answers to steel—move, or be left behind."*

**Witchbane** — Reaction when a creature within your weapon's reach begins casting: make a melee weapon attack. On a hit it makes a Concentration check with disadvantage; if you deal damage equal to or greater than your level, the spell fails. **Sunderer of Sigils** (once per Short Rest): on a Witchbane hit, the spell is canceled outright and the creature cannot cast until the end of its next turn. *"Every rune has a breaking point."*

**Blood for Blood** — Reaction when a creature within 5 ft damages you: make one melee weapon attack against it. +1 weapon die if its attack was a crit or inflicted a condition. On a hit, gain temporary HP equal to your Might modifier. Not in heavy armor. Use limit undecided.

**No Step Back** — Reaction, once per Short Rest. When an ally within 30 ft who can see or hear you fails a save against a harmful effect, they reroll it; on a success they also gain temporary HP equal to your Vigor modifier (minimum 1). You must wear medium or heavy armor and not be Frightened or Incapacitated.

**Break the Line** — Uses per Long Rest equal to Vigor modifier (minimum 1). Move at least 10 ft in a straight line and end adjacent to a hostile creature, then make a melee attack. On a hit it makes a Footing save (DC 10 + Might + Vigor) or falls Prone. +1 weapon die if the target was already Prone, Staggered or Bleeding. If you reduce it to 0 HP, you may spend 1 Momentum (Established 2026-10-21) to move up to half your speed and attack another target (once per round). Juggernaut merged into this ability (Established 2026-10-21): the charge keeps its Long Rest uses, and the follow-up attack costs Momentum. Works against Large creatures.

**Standfast** — Requires a melee weapon, not fatigued level 2+, and not having moved on your previous turn. You may make an opportunity attack against any hostile creature that enters or moves within your reach without using your reaction; once per creature's turn and once per creature per round. Moving ends it. Usable for rounds per Long Rest equal to Vigor modifier (minimum 1). While active: −2 to Reflex saves. Synergies: enter Standfast immediately after a Break the Line kill; Standfast attacks can trigger Warding Strike.

**Ebb and Flow** — Once per turn when you make a melee attack, choose a stance after the attack: **Opening** (+1d4 to your next melee attack this turn) or **Guard** (attacks against you take −1d4 until your next turn).

**Blood for Another** — Reaction when an ally within 5 ft is hit: roll the Expression Die and reduce the damage by the roll + your Vigor modifier. Uses per Short Rest equal to your Vigor modifier, minimum 1 (Established 2026-10-21; the Expression Die is not a spent pool, so this replaces the Maneuver Die's limit). You may then take any remaining damage instead of the ally.

### Wanderer Path

**Cut and Run** — Dash or Disengage as a Minor action. Not in heavy armor. (You removed the Hide option.)

**Bait and Switch** — Reaction when a creature attacks you and another creature is within 5 ft of you. Contest your Deception or Acrobatics against its Acuity or Insight (GM's choice). Success: the attack resolves against the adjacent creature. Failure: you take the attack but reduce the damage by 1 Maneuver Die + Poise. Purely physical, no illusion.

**Opening Strike** — +1d4 to initiative. In the first round, the first enemy you damage becomes Exposed until your next turn: the next successful attack against it by another creature deals +1d4. (Exposed here conflicts with Exposed in Guard; see the inconsistencies section.)

**Hunter's Mark** — Minor action: pick a creature you have damaged this combat and make an Insight, Investigation or Survival check (DC unset); on a success it becomes your Marked Prey. Once per turn when you hit it, choose +1d4 damage, +1d4 Armor until your next turn, or reduce its speed by 10 ft until its next turn. One Mark at a time. It ends when the prey drops to 0 HP, you mark another, or you go a full round without damaging it, moving toward it, or keeping line of sight.

**Blood in the Water** — Requires Hunter's Mark. When your Marked Prey is at half HP or less, it becomes Blooded Prey. Once per turn when you damage it, choose: it gains 1 Bleeding, or it takes −1d4 on its next attack before the end of its next turn.

**First Blood** — Once per combat, when you hit a creature that has not yet taken a turn, choose: +1 weapon die damage, inflict Bleeding, or a Footing save (DC 10 + Poise + Acuity) or fall Prone. Each creature can be affected once per combat.

### Sorcerer Path

**Dark Covenant** — *A pact sealed in blood, breath and silence.* Choose a boon. **Covenant of the Chain:** a spectral familiar, an echo of some damned soul, tethered to your will—barely. **Covenant of the Blade:** a conjured weapon of darkness and oath that shifts form when unwatched and leaves wounds that never heal cleanly. **Covenant of the Tome:** an ancient grimoire stitched in cursed vellum, written in blood, revealing its truths only under starlight and pain. Mechanics kept the same as 5e Pact Boon and are not yet translated.

**Revenant Elegy** — Once per Short Rest, when you personally kill a creature by any means, make a Presence + Occult check (DC 14) to raise a **Wraith Revenant** where it died. On the Revenant's first turn, check again (DC 14) for full control; on a failure it acts erratically but stays hostile to your enemies; on a natural 1 it turns on everyone for its duration. Lasts 1 hour or until 0 HP; one at a time. It trails cold mist. When destroyed, creatures within 10 ft make a Courage save (DC 10 + your Presence + Sagacity modifiers) or are Frightened until the end of their next turn.

*Wraith Revenant:* HP 30 + your level; AC 14; speed 30 ft, fly 30 ft (hover); Spectral Claw +6 to hit, 2d6 + Presence necrotic; Incorporeal Movement; advantage against the creature type it came from; telepathy with you within 60 ft while controlled.

**Voices Beyond the Veil** — Requires Revenant Elegy. Reaction when a humanoid dies within 30 ft: bind a fragment of its spirit for 1 hour. Use it once, then it passes on: **Whisper of Memory** (one truthful question about its identity, recent experiences, a creature it knew or a place it visited), **Lingering Knowledge** (+1d4 on one History, Investigation, Insight or Occult check about it), or **Echo of the Dead** (action; the GM reveals an image, sound or moment from its final hour).

**Speak the Old Laws** — Action: choose an undead within 60 ft and make an Occult check opposed by its Will. On a success, command it: **Halt** (cannot move until the end of its next turn), **Kneel** (falls Prone), **Retreat** (moves away from you on its next turn), **Follow** (follows you for up to 1 hour unless you or allies attack it), or **Protect** (won't willingly attack a chosen creature for 1 minute). On a failure it is immune to you until your next Short Rest. Powerful undead may gain bonuses, ignore commands against their nature, or break free at GM discretion.

**Lance the Fever** — *What you hold too long begins to hold you. Some nights you must open the door and let it out, and you never know what walks through.* Once per Short Rest, as you settle to sleep (no action), reduce your Instability by half, rounded down. The power must go somewhere; choose one: **Restless** (you gain no benefit from this Short Rest: no HP recovery and no Grit or Focus morning rolls) or **Marked Ground** (the place you slept is stained; the GM chooses an omen tied to your Domain, which may draw attention or do real harm). Converted from Arcane Recovery. (Name and concept Established 2026-10-25; the halving and the toll menu Draft until Instability has numbers.)

## Ability triage: what's left

The Keep list is done except four tabled items; the 45-ability Tweak list is in progress, worked one ability at a time (started 2026-10-25). (Established)

**Tabled from Keep (Open)**

- **Fighting Maneuvers** — the biggest open subsystem: maneuver list, Maneuver Dice, acquisition.
- **Improved Critical** and **Superior Critical** — waiting on the final crit design (see Combat).
- **Another Fighting Style** — Fighting Styles themselves are undesigned.
- **Improved Fighter Maneuver Die** — resolved: folded in as scaling inside any ability that uses a Maneuver Die.
- **Eldritch Invocations** (tabled 2026-10-25, from the Tweak list) — absorbed into the Warlock bargain framework; see Invocations as tree nodes under Mage archetypes.

**Tweak list (42 remaining of 45)** — keep the concept, expect major changes:

- Magic: Arcane Recovery (done: Lance the Fever, SO-005), Meta Magic, Mystic Arcanum, Spell Mastery, Signature Spell, Restore Balance, Wild Magic Surge, Destructive Wrath, Spirit Totem, Dampen Elements, Protective Bond, Heart of the Storm, Power Surge, Beguiling Defenses, Deflecting Shroud, Cosmic Omen (moved from Keep)
- Martial: Fighting Style, Second Wind, Martial Arts, Sneak Attack, Danger Sense, Action Surge, Stunning Strike, Uncanny Dodge, Favored Enemy, Evasion, Indomitable, Feral Senses, Elusive, Foe Slayer, Ancestral Protectors, Unwavering Mark, Fighting Spirit, Beast Companion, Spirit Shield, Bestial Soul, Aspect of the Beast, Panache, Infectious Fury, Zealous Presence, Superior Hunter's Defense, Death Strike, Survivor

**Drop list (28)** — too whimsical, too powerful, or off-theme:

Wild Shape, Aura of Protection, Aura of Courage, Improved Divine Smite, Beast Spells, Aura Improvements, Archdruid, Eldritch Master, Deflect Missiles, Slow Fall, Blind Sense, Indomitable Might, Tempestuous Magic, Bastion of Law, Misty Step, Radiant Soul, Celestial Resistance, Nature's Sanctuary, Faithful Summons, Form of the Beast, Storm Aura, Totem Spirit, Vengeful Ancestors, Call the Hunt, Totemic Attunement, Primal Champion (moved from Keep), Raging Storm (moved from Keep), Divine Smite (cut 2026-10-25; its rework is saved as a Committed Strike upgrade idea, see Combat).

**Early ideas worth remembering (Proposed):** "Last Breath" as a dark take on Second Wind (stagger on at 1 HP for one more strike, risk bleeding out). Spare names you liked for future abilities came out of the Blow for Blow, No Step Back and Break the Line naming rounds.
