# Open Issues and Next Steps

Known inconsistencies, the attribute scale audit and the next-steps checklist.

## Inconsistencies and gaps

These are contradictions between drafts, or rules that point at something that doesn't exist. Each needs a one-line decision from you.

| Issue | Where | Suggested fix |
| --- | --- | --- |
| Rank point schedule sums to 21, but the text says 24 and the target build needs 22 | Skills | Moot 2026-10-14: rank points were replaced by d100 Training (see the Skill Tests tab) |
| Dwarf drafts disagree on poison save advantage | Dwarves | You removed it twice; treat as gone |
| Dark Elf: choose one invocation, or get all three? | Elves | Decide; your original text said choose one |
| Gnome Cunning and Blow for Blow use advantage; Hunter's Mark gives +1d4 Armor | Gnomes, abilities | Confirm each is a deliberate exception to the minimize-advantage pillar |
| "Exposed" means +1d4 damage in Opening Strike, but 0 Guard in the Guard draft | Opening Strike, Combat | Rename one of them |
| Standfast references a "Hold the Line" option of Fight or Flight that doesn't exist | Standfast | Change the synergy to the Fight option, or cut it |
| 5e terms remain: Proficiency Bonus, Dash, Disengage, bonus action, concentration | Many abilities | Resolved 2026-10-15: DCs use two attribute modifiers plus Potency, so Proficiency Bonus is retired; the Wisdom save was resolved 2026-10-15 (Visage of Frenzy now uses Courage) |
| Hunter's Mark check has no DC | Hunter's Mark | Set a DC or make it opposed |
| Extra Attack and Dark Covenant have names and flavor, but no system rules | Abilities | Write rules text once action economy and Warlock invocations exist |
| Brief Rest and Short Rest used but undefined (resolved 2026-10-16: see Encounters and rests) | Throughout | Define both against the one-week Long Rest |
| Fatigue vs Exhaustion used interchangeably | Frenzy family | Pick one term and define its levels |
| Armor vs AC vs Defense all used for the number you hit | Crits, Fight or Flight, Guard | Settle on one term (Defense was proposed) |
| Grit, Focus and Fortune pools of 0 at +0 modifier | Expressions | Resolved: Grit and Focus became tens-digit pools (2026-10-17); the Fortune pool has a minimum of 0 (Established 2026-10-24) |
| Fortune overlaps with the Providence-in-saves substitution | Expressions, Saves | Fold the save rule into Fortune, or keep both |
| HP stays "like D&D" while the Guard plan wants low, slow-growing HP | Combat | Decide the HP scale before Guard math |
| Rally costs 1 Grit, but Grit equals Vigor mod and refreshes only on a week-long Long Rest, so most characters could Rally once or twice a week. Grit is also meant for survival and conditions, not damage reduction | The Exchange, Grit | Resolved 2026-10-12: Rally stays tied to Grit; Vigor at least half its maximum grants 1 free Grit per day |
| Generic Step (Minor, 5 ft without provoking) duplicates Relentless Advance (1 Momentum) and undercuts Quick Step (1 Tempo) | The Exchange, Momentum, Tempo | Proposed: cut Step; moving without provoking is what Momentum and Tempo buy |
| Free Harry (+2 Guard damage) outclasses Press the Attack (1 Momentum for +1 damage) | The Exchange, Momentum | Proposed: keep Harry as the floor; Press the Attack adds to both Guard and HP damage and stacks with Harry |
| Aim listed as a generic action, but Focus (Refine) and Tempo already replaced the Aim idea | Universal actions, Focus | Proposed: drop Aim from the generic list |

Also missing: dying rules, injury thresholds and tables, backgrounds, feats, the progression tree's point costs, equipment and weapon stats.

### Attribute scale audit (2026-10-13)

The 1–10 scale (modifier = score − 5) was checked against every rule that reads an attribute. Racial totals all pass (+1/+1/−1 for every race and subrace, including Ferrous and Gem Dragonborn). Thirteen issues remain; fixes are Proposed.

| # | Issue | Where | Proposed fix | Priority |
| --- | --- | --- | --- | --- |
| 1 | Saves say "Agility + Perception" while skills average two modifiers. If saves add, they range −8 to +10 and a level-20 strong save (+10) nearly always beats DCs around 18 | Saves, Breath Weapon DC | Reopened 2026-10-14: saves returned to the d20; neither plain addition nor plain averaging; a balanced formula is being designed | High |
| 2 | Focus and Fortune equal their modifier and refresh only on the week-long Long Rest: 0 for an ordinary attribute, 2–3 a week for a level-1 specialist. Likely hoarded, rarely spent | Focus, Fortune | Mirror the Grit rule: 1 free point per day if the attribute is 5 or higher | High |
| 3 | Cognition and Authority are base + modifier, so a low score cuts below the archetype base (Sagacity 2 gives a fighter −2 battle plans). Contradicts "a fighter never needs Sagacity" | Cognition, Authority | Negative modifiers never reduce Cognition below base. Decide separately whether low Presence should shrink a caster's Authority | High |
| 4 | Pools go negative: static pools at score 4 or lower, Momentum and Tempo max at score 1 | All Expressions | Every pool and maximum has a floor of 0 | Medium |
| 5 | Creation lets a character take 7, 7, 7, 7, 6 by dumping two attributes to 2. Providence and Presence are cheap dumps for martial builds | Creation (Proposed) | Lowering grants points only down to 3 | Medium |
| 6 | DC formulas disagree: "8 + attribute + Proficiency" vs "8 + Presence + Might". Proficiency is undefined, and two-attribute DCs reach 18 | Break the Line, First Blood, Visage of Frenzy | Reopened 2026-10-14: save DCs stay on the d20; set one DC formula alongside the save rework. Resolved 2026-10-15: DC = 10 + two attribute modifiers (max +7) + Potency | Medium |
| 7 | Gambling adds Providence to the highest modifier (up to +10) while every other skill averages (up to +5) | Skills | Resolved 2026-10-13: Gambling % = 2% × (Providence + highest other attribute) + Training | Medium |
| 8 | Uses "per Long Rest equal to Vigor modifier" now mean 1–3 uses a week | Break the Line, Standfast | Revisit once Short and Brief Rest are defined | Medium |
| 9 | Old open question on minimum Grit at +0 Vigor. The daily-Grit rule already covers Vigor 5+ | Grit | Close it: no minimum; the daily point is the floor | Low |
| 10 | Providence-in-saves uses equal Providence modifier, which can be negative | Saves | Resolved 2026-10-24: minimum 0 uses (Established) | Low |
| 11 | "Rounded down" is ambiguous for negative averages: (0 + −1) ÷ 2 is −1 if floored, 0 if truncated | Skills | Moot for tests, which no longer average; still state the rule wherever modifiers are averaged | Low |
| 12 | Stonecunning doubles the Sagacity modifier, doubling a penalty too | Dwarves | Double only a positive modifier | Low |
| 13 | Blood for Blood grants temporary HP equal to Might modifier, which can be negative | Blood for Blood | Minimum 0 | Low |

## Next steps

You left off about to set Guard's numbers; the agreed order from there was Guard, universal actions, conditions, armor, then weapons, because each answers questions the next one raises.

- [ ] **Guard math:** average Guard, Guard damage per hit, recovery per defensive action, and the HP scale. Then run a few sample fights on paper at levels 1 and 20.
- [ ] **Universal combat actions:** Attack, Move, Sprint, Withdraw, Brace, Guard, Ready, Help, Grapple, Shove, Aim, Hide, Search, Interact. Settle the action economy at the same time.
- [ ] **Conditions:** define the named list, including Bleed and a fatigue ladder.
- [ ] **Armor and shields:** Guard damage reduction, penetration, shield blocks.
- [ ] **Weapons:** Guard pressure, crit conditions, quality tiers, which attacks are Committed.
- [ ] **Finish the Keep list:** Fighting Maneuvers and Maneuver Dice, Fighting Styles, Improved and Superior Critical.
- [ ] **Clean-up pass** on the inconsistencies table.
- [ ] **Convert the 45 Tweak abilities.**
- [ ] **Mage systems in detail:** Instability, Blood Debt, Hexer and Veilwalker preparations, Domains.
- [ ] **Races:** Rock and Deep Gnomes, Humans, Halflings, Half-Orcs, the Oni-inspired race, the planned special race, and a decision on Hollowborn.
- [ ] **Character creation glue:** backgrounds, feats, progression-tree costs.
- [ ] **d20 audit of all abilities:** once the hybrid is approved, revisit every ability that mentions or relies on a d20 skill check, save, DC or bonus (race and subrace traits, backgrounds, Sword, Sorcerer and Wanderer path abilities, Expressions and conditions) and rewrite it for d100 tests. Known cases so far: Break the Line, First Blood, Warding Strike, Visage of Frenzy, Revenant Elegy, Speak the Old Laws, Hunter's Mark, Unending and Focused Frenzy, Frenzy, Call to Stand, Lingering Knowledge, Witchbane, Standfast, No Step Back, Breath Weapon, Iron Gut, Stonecunning, Eldritch Mind, Gnome Cunning, Poisoned, Fortune's Second Chance.
- [x] **Save rework: design a balanced d20 save formula and the matching save DC formula (replaces the Potency discussion)**.
- [ ] **XP economy:** design the XP pool and its à la carte costs (attributes, skills, path abilities, other purchases), replacing character levels.
- [ ] **Level audit:** convert every rule that refers to a character level. Level-scaled traits found in the 2026-10-24 progression audit, each frozen at its first step until converted: Breath Weapon damage (Dragonborn, stays 1d6); Heart of Steel (Ferrous Dragonborn, +1 HP per level, so it currently grants nothing); the Telekinetic spell ladder (Gem Dragonborn); the Illusionist spell ladder (Forest Gnome, written "at 1, at 6, at 11, at 16"); the Eldritch Smith imbued-item count (Duergar); Witchbane's "damage equal to or greater than your level"; the Wraith Revenant's "HP 30 + your level"; the specialization bonus bands (Skill Tests tab); the Balance Reviewer's "levels 1, 10 and 20"; the opening line of Progression and archetypes ("leveling grants points") and the Proposed "1 Ability Point per level"; and the level-1 framing of the Guard simulations.
- [ ] **0–100 attribute rebuild:** set the conversions from attribute score to d20 modifier, skill talent, saves and Expression pools; the XP ceiling; starting scores and race adjustments; then rerun every check that used the 1–10 scale (saves, Grit, audit items, Guard simulations).
- [x] **Improvement pacing:** resolved 2026-10-24. The current tick and improvement-roll pace stands (roughly 45–60 sessions to take a skill to 90% at a typical table), because the campaign will be long.
- [x] **Focus on tests:** resolved 2026-10-17: Focus moves attack rolls only, not saves or d100 tests.
- [ ] **Skills as a category:** revisit the skill list, starting Training and surrounding architecture to confirm it is what we're aiming for.
- [ ] Expression pools (paused 2026-10-15, resume after the combat rebuild): Proposed rating = attribute tens digit; Grit and Focus regain 1 on a morning d100 roll equal to or under the score; Fortune refills only on a Long Rest; Momentum and Tempo max = rating; Cognition and Authority = base + (rating − 5), never below base. Grit study (old combat numbers): pool size fine; Rally adds about 1.5 rounds per use, so cap Rally (and Stay Standing) at once per fight. Then tune Focus, Momentum, Tempo and Fortune one at a time.
- [ ] Swordsman fighting styles or actions that capitalize on their own crits (later, creator has ideas).
- [ ] Revisit initiative (currently rerolled every round); note that per-round rerolls let an attacker act twice in a row and so benefit from its own crit conditions.
- [ ] Daggers still trail (25% vs the Duelist) once Bleeding correctly leaves Committed actions alone; retest after Injuries, attrition and Grit's condition uses are modeled. Decide whether long blades keep Bleeding as their Fine option.
- [ ] Return to Grave Wounds: build the Grave Wound table (from Grievous and Mortal Ebb results, untreated Maiming, and new Injuries on a Maiming wound). The expedition sim shows about 80% of Grave Wounds come from The Ebb, so how often a Grievous roll leaves a permanent mark is the main lever.
- [ ] Make a table of narratively flavorful Injuries for each region (head, torso, weapon arm, off arm, legs), in Light, Serious and Maiming versions and by damage type (blunt, cutting, piercing), so the GM can describe the same mechanical Injury vividly.
- [ ] Consumables for recovery: bandages and potions that add HP during Brief and Short Rests (Short Rest HP stays at half the Vigor tens digit, so longevity should come from supplies). Waking at half the Vigor tens digit instead of 1 HP is held in reserve.
- [ ] Acuity upgrade, Read the Fight: no action, 1 Focus, once per round in a fight, learn a visible foe's intent for its next turn (whom it means to strike, or whether it means to flee, yield, call for help or prepare something).
- [ ] Acuity upgrades for Spot: scouting uses, for example spending Focus after a failed Search to learn the direction of the nearest Hidden creature.
- [ ] Fighting style idea: make Harry-and-Ward-together a dual-wielding style (a light weapon in the off hand) instead of a rule for every light weapon.
- [ ] Set the general off-hand attack penalty (applies to attacking while grabbing and to dual wielding); abilities and fighting styles can reduce it later.
- [ ] **Movement follow-ups (2026-10-18):** decide the Committed Strike leaving-reach fix; whether only melee attacks earn Tempo's on-turn beat; rework Hurler gains (nothing in melee), Vanguard's farmable charge trigger and Ironstring's Draw Weight; define Charge, bow and thrown weapon stats and ranges, and cover; settle Shove (Footing save or attack against Defense); add Shove to the engine.
- [ ] **Combat decision layer (2026-10-19):** after the declare-then-act prototype, test a counter-wheel for the Exchange (Press, Ward, Committed) so that reading a declaration pays off. Back pocket: a hidden simultaneous-choice **Showdown** mechanic (both sides pick secretly, reveal together) for duels and climactic moments, kept out of everyday combat because it would slow play.
- [ ] **Ability Catalog (added 2026-10-21):** file every Path ability in the Ability Catalog tab with the Established data fields, starting with the Sword path; placement fields stay Open until the holistic review.
- [ ] **Holistic Path review:** with the catalog filled, review all three Paths together (roles, overlaps, gaps, convergence candidates), then derive branches and place abilities into tiers.
- [ ] **Momentum decisions awaiting the creator (2026-10-21):** all resolved 2026-10-21.
- [ ] **Still Open from 2026-10-21:** define Charge; decide the fate of the Fighting Maneuvers subsystem; set the penalties for 14 Short Rests without a Long Rest; translate 5e holdovers (Witchbane's 'level', Frenzy's resistance, temporary HP) into Guard-era terms.
- [ ] **Tempo and the other Expressions:** test whether the Momentum model (small universal core plus Path abilities) fits Tempo and Grit.
- [ ] **Interactive tree (later):** a clickable player resource generated from the catalog's fields.
