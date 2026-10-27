# Combat

Criticals, Defense, Guard and HP, Injuries and Dying, calibration, initiative, the action economy, the three-action proof and Showdowns.

Combat is built around earned decisiveness: ordinary hits wear down Guard, openings come from precision and pressure, and only then do bodily wounds land. You were about to set Guard's numbers when the chats ended.

### Critical hits

- **Precision Critical (Established):** the final attack result exactly equals the target's Defense.
- **Overwhelming Critical (Established direction):** the result beats Defense by 10 or more, so skilled fighters still crit weak foes.
- **Focus steering (Established):** Refine: spend 1 Focus to move an attack roll 1 toward a crit result, including lifting a miss by 1 onto exactly Defense; at most 1 Focus per attack (see Focus).
- **What a crit does (Established):** no extra damage by default. It applies a condition set by the weapon's family. **Quality tiers (Established 2026-10-16):** Crude weapons apply nothing; Common apply the family's first effect; Fine let the attacker choose either effect; Masterwork apply both. Crit conditions follow the conditions framework: they last until the end of the target's next turn, except Bleeding (until bound) and Sundered (until the encounter ends).
- **Weapon crit effects (Established 2026-10-16):** see the table below. Thrown weapons use their own family (a javelin crits as a spear, a hatchet as an axe). Dazed is left out of every weapon family on purpose and is reserved for abilities and feats, because about a third of hits are crits and losing half a turn that often is the strongest swing in the game. Replaces the earlier proposal (dagger → Bleed; warhammer → Dazed or knockdown; spear → Impale; greatsword → Sunder or push back; club → Staggered).
- **Natural 20 (Rejected 2026-10-16):** no automatic hit on a natural 20 and no automatic miss on a natural 1, matching saves. Criticals come only from Precision and Overwhelming results. Logged for player feedback alongside saves.

| Family | Examples | Common effect | Fine adds the choice of |
| --- | --- | --- | --- |
| Short blades | dagger, knife, short sword | Bleeding +1 | Exposed |
| Long blades | longsword, sabre, rapier | Exposed | Bleeding +1 |
| Axes & great blades | battleaxe, greataxe, greatsword | Sundered | Staggered |
| Light blunt | club, mace, flail | Staggered | Flat-Footed |
| Heavy blunt | warhammer, maul | Prone | Staggered |
| Spears & polearms | spear, pike, halberd | Impaled | Prone |
| Bows | shortbow, longbow | Slowed | Bleeding +1 |
| Crossbows | crossbow | Sundered | Staggered |
| Unarmed | fists, grapples | Staggered | Grabbed (needs a free hand) |

Future design space (noted 2026-10-16): fighting styles or actions that let swordsmen capitalize on their own crits (Exposed in particular), to be designed later.

**The Misericorde rule (Established 2026-10-17):** short blades find the gaps. When a short blade (dagger, knife, short sword) damages Guard, ignore the target's armor Guard Reduction. Parry still reduces the damage as normal. A knife will never out-duel a sword, but it is the answer to armor: the narrow blade slipped between the plates.

**Improved and Superior Critical (Open)** — three versions were proposed; your last stated preference is the third:

| Version | Improved Critical | Superior Critical |
| --- | --- | --- |
| Widen precision window | Crit on AC or AC+1 | AC to AC+2 |
| Stronger Focus | Each Focus point moves the roll 2 | Moves it 3 |
| Your stated direction | Crit conditions are more potent or last longer | Crits also add damage |

If Superior Critical adds a weapon die, decide how Brutal Critical stays distinct.

### Defense, Guard and HP (Draft)

The d20 stays the core resolution die (Established). Damage flows through these layers:

1. **Defense** — d20 + modifiers vs Defense decides whether an attack connects.
2. **Guard** — absorbs ordinary hits. It measures how much pressure you can take before you become vulnerable.
3. **0 Guard** (Established) — the hit that drops Guard to 0 stops there and any extra damage is lost. While at 0 Guard, every hit that connects damages HP. Only specific abilities or weapons, used under their stated conditions, carry extra damage through to HP (carry-through). None are defined yet; they will be set with criticals, weapons and Committed actions.
4. **HP** — bodily injury; works like D&D with changes. Taking too much at once causes an **Injury** or **Grave Wound/scar**.
5. **0 HP** — you fall Dying (The Ebb sets your Injury when you are stabilized): Prone, unable to act (Stay Standing can delay this one turn). Dying follows The Ebb (below).

**Attack and Defense (Established 2026-10-15):** an attack rolls d20 + attribute modifier A + attribute modifier B, where the weapon's category names the two attributes (maximum +7 from attributes). Defense = the armor's Defense value + Poise modifier + Vigor modifier, with the combined bonus capped at +7: slipping the blow, and the stamina to keep your guard up. An armor may limit or forbid that bonus; plate, for example, adds none. (Changed 2026-10-16 from armor + Poise, to stop Poise counting twice.) There is no proficiency or training bonus. The weapon pairs and armor values are Draft and will be set next.

**Poise penalties (Established 2026-10-15):** armor can cap or remove the Defense bonus, but a negative Poise or Vigor modifier always applies, whatever the armor.

**Defense range (Draft 2026-10-15):** Defense runs from 8 (no armor, the lowest starting Poise of 25) to 18, the tentative maximum for standard gear. 18 is not a cap: relics, magic and other extraordinary sources can raise Defense further, to a tentative whole-game maximum of about 30 (creator's estimate, subject to change). Armor, quality and other bonuses will be fitted into this range. The "reached by" column was written before the 2026-10-16 change (Defense now adds Poise + Vigor, and the draft armor bases dropped by 1 to none 9, light 10, medium 11, plate 13) and needs redoing; the hit chances for each Defense value are unaffected. Hit chance is d20 + attack bonus ≥ Defense; Overwhelming critical means beating Defense by 10 or more.

| Defense | Reached by (draft examples) | Hit % at attack +0 | +2 (typical new) | +4 (best new) | +7 (XP cap) | +10 (cap + gear) | Overwhelming % at +7 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 8 | No armor, Poise 25–34 | 65 | 75 | 85 | 100 | 100 | 50 |
| 9 | No armor, Poise 35–44 | 60 | 70 | 80 | 95 | 100 | 45 |
| 10 | No armor, Poise 45–54; light, Poise 35–44 | 55 | 65 | 75 | 90 | 100 | 40 |
| 11 | Light, Poise 45–54; medium, Poise 35–44; no armor, Poise 55 | 50 | 60 | 70 | 85 | 100 | 35 |
| 12 | Medium, Poise 45–54; no armor, Poise 60 | 45 | 55 | 65 | 80 | 95 | 30 |
| 13 | Light, Poise 60; plate, Poise 35–44; no armor, Poise 65 | 40 | 50 | 60 | 75 | 90 | 25 |
| 14 | Plate (Poise 45+); medium, Poise 60+; light, Poise 65; no armor, Poise 70 | 35 | 45 | 55 | 70 | 85 | 20 |
| 15 | Fine plate; light, Poise 70; no armor, Poise 75 | 30 | 40 | 50 | 65 | 80 | 15 |
| 16 | Masterwork plate; light, Poise 75; Masterwork medium, Poise 60+ | 25 | 35 | 45 | 60 | 75 | 10 |
| 17 | Masterwork relic plate; Fine light, Poise 75 | 20 | 30 | 40 | 55 | 70 | 5 |
| 18 | Masterwork light, Poise 75; no armor, Poise 90 (gear maximum) | 15 | 25 | 35 | 50 | 65 | 0 |

Resolved 2026-10-15: 18 is the standard-gear maximum, not a hard cap, so high Poise and temporary bonuses such as Dodge may exceed it. Open: Defense above 20 outruns the largest attack bonus a character can reach (+10), so Defense 25–30 is nearly untouchable unless monsters and extraordinary attackers can go beyond +10.

**Weapon attack pairs (Established 2026-10-15):** each weapon category names the two attributes its attack bonus adds.

| Category | Examples | Attack pair |
| --- | --- | --- |
| Heavy | Greataxe, greatsword, maul, warhammer | Might + Vigor |
| Martial | Sword, axe, mace, spear | Might + Acuity |
| Finesse | Dagger, rapier, short blade | Poise + Acuity |
| Bows | Shortbow, longbow | Acuity + Might |
| Mechanical | Crossbow (firearm, if Asloria has them) | Acuity + Sagacity |
| Thrown | Javelin, throwing axe, throwing knife | Might + Acuity |
| Unarmed | Fists, brawling strikes | Might or Poise, + Acuity or Vigor |

Unarmed lets brawlers come in several builds: a bruiser (Might + Vigor), a boxer (Might + Acuity), a scrapper (Poise + Vigor) or a quick striker (Poise + Acuity). Proposed: the brawler picks one attribute from each half as their fighting style, and it stays fixed until changed through training. Open: whether Asloria has firearms.

**Damage (Established 2026-10-15):** damage = weapon die + damage bonus. The damage bonus is the tens digit of the weapon's damage attribute minus 5 (score 40–49 gives −1, 50–59 gives 0, 60–69 gives +1, 75 gives +2, 100 gives +5). Penalties apply, and a hit always deals at least 1. Damage attributes: Might for Heavy, Martial, Bows and Thrown; Poise for Finesse; the brawler's chosen Might or Poise for Unarmed; none for Mechanical, which relies on a larger die. Weapons, abilities and other sources will add damage and hit chance through their own channels, to be set later.

**Guard and HP (Established 2026-10-16; numbers Draft):** Guard = 6 + shield + training. Everyone has 6; a standard shield adds +2; martial training (a Sword Path ability bought with XP) adds +2. Attributes never add Guard. HP = the race's HP value + Vigor's tens digit. Both can grow beyond this through XP purchases, gear and other means, to be designed later. Race HP values are not set yet; 5 is used as a placeholder for testing.

HP recovers mostly on a Long Rest (a week). (Established)

**Injuries (Established 2026-10-16; table and numbers Draft):** you gain an Injury when a single hit deals HP damage equal to or above your wound threshold, and a fall to 0 HP sets its Injury through The Ebb when you are stabilized (revised 2026-10-17). The wound threshold is Vigor's tens digit + 4. An Injury is a lasting impairment (a cracked rib, a torn shoulder) that heals only with treatment and a Long Rest. At Vigor 50 (threshold 9), one HP hit causes an Injury about 12% of the time with a sword (d8+1), 42% with a greataxe (d12+1), and never with a dagger or mace. The Injury table is still to be built, alongside conditions.

**Injury table (Established 2026-10-17; numbers Draft).** When you gain an Injury, the GM rolls d10 for location and d100 for severity, adding 5 per point the hit exceeded your wound threshold (or per point of overkill when you reach 0 HP), as on the Falling table. 01–65 Light, 66–95 Serious, 96+ Maiming. The effect is the same whatever the weapon; the GM narrates it by damage type (a mace cracks ribs, a sword opens them, a spear punctures them). An Injury takes effect at once.

| d10 | Location | Light | Serious |
| --- | --- | --- | --- |
| 1–2 | Head | Rung: initiative −2, Focus maximum −1 | Concussed: Dazed in the first round of each encounter, initiative −2, Focus maximum −2 |
| 3–5 | Torso | Cracked ribs: Guard maximum −1 | Broken ribs: Guard maximum −2 |
| 6–7 | Weapon arm | Wrenched: −1 to attacks | Torn: −2 to attacks, and you can't Parry |
| 8 | Off arm | Sprained: no Shield Block; two-handed weapons −1 to attack | Broken: you can't hold a shield; two-handed weapons −2 to attack |
| 9–10 | Legs | Twisted: Speed −10 ft, can't Sprint | Torn: Speed halved, can't Sprint or Dodge |

**Maiming (96+):** the Serious effect, and the wound turns: unless it is treated before the end of your next Short Rest, it becomes a Grave Wound.

**Same location again:** a new Injury where you already have one makes that Injury one step worse (Light to Serious, Serious to Maiming) instead of adding a second. A new Injury on a Maiming wound is a Grave Wound at once.

**Treatment and healing:** treating an Injury takes a successful Medicine test (Tend) during a Brief or Short Rest, one test per Injury: Normal for Light, Medium for Serious, Hard for Maiming. A failed test can be tried again at the next rest. A treated Light Injury heals at the end of the next Long Rest. A treated Serious Injury becomes Light at the end of a Long Rest, so it takes two. Untreated Injuries don't heal. Endure can suspend one Injury for 1 Grit.

**Tested (Proposed findings):** about 1.0–1.7 Injuries per fighter who falls, and 3–8% of duel winners take one (about 40% of a 2v2 winning side, counting fallen allies). Severity comes out about 53% Light, 30% Serious and 17% Maiming. One Light Injury drops a fighter to 44–48% against the same build uninjured; one Serious drops them to 37–45%; two Serious Injuries (torso and weapon arm) to 27–32%. Leg Injuries change nothing in the engine because movement isn't modeled. Off-arm Injuries hurt only shield and two-handed fighters. A first draft with Guard maximum −2 / −4 on the torso was too harsh (25–30% for Serious), so the torso was halved.

**Expedition sim (Proposed findings, 2026-10-17):** a party of four (Duelist, Defender, Bruiser, dagger Skirmisher) carries HP, Injuries, Grit and Focus through three days of fights against nameless bandits (no Grit or Focus, die at 0 HP). Between fights: Brief Rests with a Medicine 45% healer (Tend and Injury treatment), nightly Short Rests, The Ebb for anyone who falls, and allies bandaging the fallen when they aren't outnumbered. Three bandits is an easy fight (fresh party always wins) and four a standard one. Results: an easy fight drops about 0.8 PCs and a standard one about 1.6. About 36% of falls end Grievous or Mortal on The Ebb, and 5–7% of falls die. Per fight, a party gains about 1 Injury and 0.3–0.6 Grave Wounds. Over three days: one easy fight a day, every expedition finishes, with about 2 open Injuries and 1 Grave Wound across the party; two easy fights a day, 6% of parties are wiped out, and survivors carry about 4 open Injuries and 2.7 Grave Wounds; one standard fight a day, 9% wiped out; two standard fights a day, 63% wiped out. Parties start fights at 72–90% of their HP. Where the Grave Wounds come from: about 80% from Grievous or Mortal Ebb results, about 15% from untreated Maiming, a few from repeated Injuries to one location. Retests: crit conditions, Grit's condition uses and Refine still barely change expedition results, because nearly every Injury comes from falling to 0 HP, not from big single hits. Turning off Shake It Off and Endure slightly lowers falls, because the simulated players spend Grit that later Rallies needed. Refine is worth about 3 points of expedition survival. Caveats: simulated players focus the weakest target, never retreat, and get no magic; foes never flee; Grave Wounds are placeholders.

**Grave Wound table and Bear the Wound in the expedition sim (Proposed findings, 2026-10-17):** with every Grave Wound permanent (the old placeholder), about 40–43% of falls left a permanent wound. With the table, 17–19% of falls end in a Ruin (3–4% a Loss), 15–17% in a Lingering wound, 10–12% in a Scar, and 5–7% in death. Over three days of two easy fights a day, a party ends with about 1.2 permanent wounds instead of 2.7. Grave Wound rolls come from Grievous Ebb results (47%), Mortal (26%), Maiming that turns (14%) and new Injuries on Maiming or Lingering wounds (12%). Bear the Wound is used 0.2–0.7 times per fight (players keeping 2 Grit for Rally and Stay Standing) and doesn't change survival, falls or deaths: the injured are usually the ones who fell, and they come back at low HP, which matters more than the Injury's penalty. Its value is relief and choice, not survival.

**Longevity tests (Proposed findings, 2026-10-17):** seven-day expeditions, either two easy fights a day or one standard fight a day, with the Injury and Grave Wound tables. As things stand, about half of parties are wiped out within the week, Injuries run 1.2 (easy) to 1.8 (standard) per fight, about 22% of falls end in a Ruin, and survivors finish with 4–7 open Injuries and 3–4 permanent wounds. Recommended package (Proposed): (1) falling sets its Injury through The Ebb at stabilization instead of automatically: Grazed, no Injury; Bleeding, an Injury rolled normally; Grievous, an Injury rolled at +30 severity instead of a Grave Wound roll; Mortal, a Grave Wound roll at +20 instead of +40; (2) a Short Rest restores HP equal to the full Vigor tens digit, not half. Results with the package: Injuries per fight fall to 0.45 (easy) and 0.62 (standard), Ruin to 9–10% of falls, survivors' permanent wounds to 1.1–1.6 over the week, and finished expeditions rise from 50–51% to 62–64%; deaths stay at about 7% of falls. Changing only the Injury rules cuts Injuries and Grave Wounds but barely helps survival; the Short Rest HP change is what adds longevity. Waking at half the Vigor tens digit instead of 1 HP would add about 4 more points of finished expeditions and is held in reserve.

**Grave Wounds (Established direction):** permanent marks (a lost eye, a ruined hand) from the worst Injury results and from being struck while Dying; healed only by exceptional means or never.

**Grave Wound table (Established 2026-10-17; numbers Draft).** Roll d100 and add 20 for every source: a Mortal result on The Ebb, a Maiming wound that turns, a new Injury on a Maiming or Lingering wound, or being struck while Dying (the +20 for being struck while Dying is Draft; it wasn't set before). A Grievous result no longer rolls here; it gives an Injury at +30 severity instead. A Maiming wound keeps its location; an Ebb result rolls location on the Injury table's d10.

| d100 + modifier | Result | Effect |
| --- | --- | --- |
| 01–40 | Scar | A permanent mark with no rules effect: the story the body tells. |
| 41–75 | Lingering wound | The location's Serious Injury effect. It heals only after three Long Rests, each with a successful Hard Medicine test. |
| 76+ | Ruin | Permanent: the location's Light Injury effect forever, healed only by exceptional means. Roll d6: on a 6, or if you already have a Ruin there, it is a Loss instead: the eye, hand, arm or leg is gone, and the location's Serious effect is permanent (a lost eye also gives −2 to ranged attacks). |

Note: Lingering wounds heal, so not every result on this table is permanent; this softens the earlier direction that Grave Wounds heal only by exceptional means or never. Scars and Ruin keep it.

**Stabilizing (Established 2026-10-16):** an ally stabilizes a Dying character with a successful Tend (Medicine, Use a Skill) or by using a bandage (Use an Item, no test). A stable character stays unconscious at 0 HP and wakes at 1 HP after 1d4 hours, or sooner if healed.

**The Ebb: dying (Established 2026-10-16; numbers Draft).** A GM-only system. The GM rolls in secret and keeps the fallen character's severity private; players see only what their characters see, so they never know exactly how long they have, only that they must act.

1. **Falling table.** When a character falls, the GM secretly rolls d100: +5 per point of damage the felling blow dealt past 0 HP, +20 if it was an Overwhelming critical, −3 × the character's Vigor tens digit. 01–40 Grazed, 41–70 Bleeding, 71–90 Grievous, 91+ Mortal.
2. **Each round,** at the end of the fallen character's turn, the GM secretly rolls d6. Grazed: 1 worsens a step, 6 the bleeding stops by itself (stable). Bleeding: 1–2 worsens, 6 eases to Grazed. Grievous: 1–2 worsens. Mortal: 1–3, the character dies.
3. **A hit on a fallen character** worsens them one step and leaves a Grave Wound.
4. **What players see.** GM cues: Grazed, groaning and trying to rise; Bleeding, blood pooling and ragged breath; Grievous, pale and still, eyes unfocused; Mortal, a rattle in the throat, barely breathing. Anyone who attempts a Tend learns the true severity, even on a failed test.
5. **Cost of survival** (when stabilized): Grazed, wake at 1 HP after 1d4 hours, with no Injury; Bleeding, the same, plus an Injury rolled normally, and that night's rest restores no HP; Grievous, the same, plus an Injury rolled at +30 severity; Mortal, a roll on the Grave Wound table at +20, unconscious until the next Short Rest. (Revised 2026-10-17: Grievous no longer rolls on the Grave Wound table, and Mortal is no longer a certain permanent wound, since a Scar is possible.)
6. **Grit, "I refuse to die":** once while fallen, the player may spend 1 Grit; the GM ignores the next roll that would worsen them, without saying whether it mattered.
7. **Fortune, "Providence watches":** the player may spend a point to have the GM secretly reroll the Falling table.

Tested (Vigor 50): left alone, Grazed dies 40% of the time (recovers alone 60%), Bleeding 80%, Grievous and Mortal always (about 5 and 2 rounds). After a hard hit (4 past 0 HP), the chance the character is already dead when help arrives is 8% after 1 round, 15% after 2, 22% after 3 and 37% after 5; after an Overwhelming critical, 17%, 29%, 39% and 55%. Vigor 75 lowers these and Vigor 30 raises them.

**GM rule (Proposed):** nameless foes and most monsters simply die or flee at 0 HP; only named foes use the Dying rules.

**Guard principles (Proposed, broadly endorsed):**

- Keep Guard small: \~8–12 for an unarmored commoner, \~12–20 for trained or armored fighters, \~20–25 at most. Ordinary hits might deal 2–5.
- Guard grows little with level. Base Guard comes mainly from archetype, equipment and features, not attributes, so Vigor and Poise aren't mandatory.
- Guard recovers in combat only through actions (Withdraw, Guard, Take Cover), by fixed amounts: \~2–3 minor, \~4–6 dedicated. It fully resets once out of danger.
- **Armor** mainly reduces Guard damage; heavy weapons may penetrate it. **Shields** raise Guard and enable active blocks.
- Bypassing Guard should be rare and frightening: helpless or unaware targets, certain crits, First Blood, some monsters and magic.
- No penalties for low HP; Injuries carry the impairment, avoiding a death spiral.
- Keep max HP fairly low and slow-growing so wounds stay dangerous.
- Recovery tiers: Guard in seconds; HP in days or weeks; Injuries in weeks plus treatment; Grave Wounds through exceptional means or never.
- Monsters use the same Defense / Guard / HP stats in different proportions.

*Guard tells us how the fight is going. HP tells us how hurt you are. Injuries tell us what happened to you.*

### Guard math: first simulation (Proposed)

First pass at level-1 Guard numbers, tested with 20,000 simulated fights per matchup. Every number in this section is Proposed until you approve it.

**Hypothesis:** Guard should keep a fight readable for a few rounds before bodily harm starts, and a broken Guard should be the turning point.

**Values filled in for the test.** The Bible has no numbers yet for these, so I chose values inside the existing bands:

- Attack: d20 + 4 at level 1 (attribute +2, training +2).
- Defense of an evenly matched fighter: about 10 above the attacker's bonus (14 against +4), a 55% hit chance.
- One damage roll (weapon die + attribute) hits Guard, minus armor Guard Resistance (GR, minimum 1). At 0 Guard the same roll hits HP; armor does not reduce HP damage.
- Overflow lost (Established). One attack or one recovery per turn, since the action economy is undecided.

| Combatant | Weapon (damage) | Defense | Guard | Armor GR | HP |
| --- | --- | --- | --- | --- | --- |
| Duelist | Sword (d8+2) | 14 | 10 | 1 (light) | 12 |
| Defender | Mace (d6+2), shield | 15 | 13 | 2 (medium) | 14 |
| Bruiser | Greataxe (d12+2) | 12 | 9 | 1 (light) | 14 |
| Skirmisher | Dagger (d4+2) | 16 | 8 | 0 | 10 |
| Thug | Club (d6+1), +2 to hit | 11 | 7 | 0 | 8 |

**Results** (recommended rules below; side 1 listed first)

| Matchup | Side 1 wins | Avg rounds | 90% end by round | Guard first breaks | Winner's HP lost |
| --- | --- | --- | --- | --- | --- |
| Duelist vs Duelist | 50% | 6.9 | 10 | Round 3.2 | 30% |
| Defender vs Bruiser | 59% | 7.3 | 10 | Round 3.2 | 25% |
| Skirmisher vs Duelist | 23% | 7.5 | 11 | Round 3.2 | 37% |
| Duelist vs 1 Thug | 99% | 4.5 | 7 | Round 2.1 | 4% |
| Duelist vs 2 Thugs | 57% | 7.5 | 10 | Round 2.0 | 30% |
| Duelist vs 3 Thugs | 7% | 5.9 | 9 | Round 1.8 | 50% |
| Recovering Duelist vs attacking Duelist | 56% | 9.4 | 14 | Round 3.2 | 27% |
| Recovering Defender vs Bruiser | 66% | 9.3 | 14 | Round 3.2 | 22% |
| 3 Duelists vs 3 Duelists | 50% | 10.9 | 15 | Round 1.3 | 24% |

**Findings**

1. **Free Guard recovery was always the right move.** Because overflow is lost, any Guard regained, even 2, soaks the next whole hit. A fighter who recovered whenever Guard hit 0 won 89–95% of mirror fights. Making recovery a Committed action that a connecting hit cancels brings that to 56–66%: a real option, not the only one.
2. **Fights run long.** Duels last about 7 rounds and 3v3 fights about 11. Guard breaks around round 3, then HP takes 3–4 more rounds. Cutting Guard from 14 to 10 saved only about one round; the bigger lever is damage per round, which waits on the action economy.
3. **Lower Defense makes Overwhelming criticals too common.** Dropping Defense to 12 shortens fights, but beat-by-10 crits jump from 9% to 23% of hits. Keeping equal-level Defense about 10 above attack bonus makes Overwhelming a natural-20 event between equals.
4. **HP is a short fuse.** One d8+2 hit takes half of 12 HP, so most HP phases end in 2–3 hits. That suits the tone, but Injury rules will trigger in most fights, so set their thresholds with that in mind.
5. **Outnumbering is deadly, as intended.** A Duelist beats one thug 99% of the time, two 57%, three 7%.
6. **Precision criticals land on about 9% of hits** (5% of attacks), roughly one per duel, whatever the Defense.
7. **Light weapons are weak.** The dagger Skirmisher wins only 23% against a Duelist; high Defense does not make up for d4 damage. Their identity needs to come from crit conditions or Tempo.
8. **Fixed Guard damage per weapon was tested and rejected.** It flattened weapon differences, and armor let the shield Defender beat the greataxe Bruiser 87% of the time.

**Recommendation (Proposed)**

- Guard damage uses the same damage roll as HP, minus armor GR.
- **Recover Guard (now Rally, below)** is a Committed action: declare it on your turn; at the start of your next turn regain 5 Guard, unless an attack connects with you first.
- Level-1 Guard: superseded by the Action economy section below (commoner 6, trained fighter 8, shield and armor 10), retuned once reactions and Minor actions were added.
- Equal-level Defense is about attack bonus + 10. (Superseded 2026-10-15 by the Attack and Defense rule above; a hit chance near 55% between evenly matched fighters stays a calibration reference, Proposed.)

**Next test:** settle the action economy (1 Major + 1 Minor was proposed), then rerun fight length.

**Open:** none. Target set 2026-10-12 (Established): an even 1v1 duel lasts about 7 rounds, unless the action economy grows well past 2 actions per round. Larger group fights may run longer.

### Calibration on the 0–100 scale (Proposed, 2026-10-16)

The new rules hold the duel target: an even duel between new characters lasts about 8 rounds with one Rally each, and veterans stay in the same range. The fight engine used two-attribute attacks, armor + Poise Defense, the new damage rule, Guard = 6 + shield + training, HP = 5 (placeholder race value) + Vigor tens digit, the Exchange and one Rally per fighter. It used the draft armor table and did not model crit conditions, movement or other Expressions. 8,000 fights per matchup.

| Fighter | Attack | Damage | Defense | GR | Guard | HP |
| --- | --- | --- | --- | --- | --- | --- |
| Duelist (Might 60, Poise 55; sword, light) | +3 | d8+1 | 12 | 1 | 8 | 10 |
| Defender (Might 60, Poise 50; sword, plate, shield) | +2 | d8+1 | 14 | 3 | 10 | 10 |
| Bruiser (Might 60, Vigor 60; greataxe, light) | +4 | d12+1 | 10 | 1 | 8 | 11 |
| Skirmisher (Poise 60, Acuity 60; dagger, no armor) | +4 | d4+1 | 12 | 0 | 8 | 9 |
| Thug (untrained; club) | +0 | d6+0 | 10 | 0 | 6 | 9 |
| Veteran Duelist (XP ceiling, Fine gear) | +7 | d8+2 | 17 | 1 | 10 | 11 |

| Matchup (1 Rally each) | Side 1 wins | Avg rounds | 90% end by |
| --- | --- | --- | --- |
| Duelist vs Duelist | 50% | 8.0 | 11 |
| Defender vs Bruiser | 62% | 7.7 | — |
| Bruiser vs Duelist | 59% | 6.3 | — |
| Skirmisher (dagger) vs Duelist | 28% | 8.0 | 12 |
| Skirmisher (rapier) vs Duelist | 40% | 7.6 | — |
| Duelist vs 2 Thugs | 47% | 8.1 | 12 |
| 3 Duelists vs 3 Duelists | 51% | 10.2 | 15 |
| Veteran Duelist mirror | 49% | 8.6 | 12 |
| Veteran Duelist vs new Duelist | 98% | 5.8 | 9 |
| Veteran Duelist vs 3 Thugs | 92% | 10.6 | 13 |

Findings:

- Duel length is on target: 6.2 rounds with no Rally, 8.0 with one each, and the veteran mirror 8.6. Gear Defense (+2) keeps pace with the veteran's +7 attack.
- Hit chance between equals is 55–59%. Precision criticals land on about 9% of hits; Overwhelming on 10–14% of hits between equals and 25–30% against much weaker foes.
- Build matters more than before. A plate-and-shield Defender who puts points into Vigor (attack +1, d6 mace) wins only 35% against the Bruiser; the same armor with Might and Poise and a sword wins 62%. Vigor adds little in a fight until Grit and conditions are modelled.
- Light weapons are still weak without their crit conditions (dagger 28%, rapier 40% against a Duelist), as expected.
- Advancement is a steep gap: a veteran at the XP ceiling beats a new character 98% of the time and handles three thugs 92% of the time.

**Guard and HP limits.** Fight length grows by about 1 round for every +4 Guard and about 1.2–1.5 rounds for every +4 HP. Damage grows slowly (+2 at the XP ceiling), so Guard and HP growth must stay modest or be matched by damage from weapons and abilities. Proposed envelope:

| Stage | Guard | HP | Veteran duel length |
| --- | --- | --- | --- |
| Creation | 6–10 | race value + 2–6 (7–11 with race 5) | about 8 rounds |
| XP ceiling with standard gear | up to about 14 | up to about 16 | about 11 rounds |
| Whole game (relics, magic, legend) | up to about 25 | up to about 30 | 18+ rounds unless damage also grows |

Rule of thumb (Proposed): each +4 Guard or +4 HP above the creation range should come with about +1 damage per hit from weapons or abilities to keep fights the same length. Accepted 2026-10-16 as working limits. HP also gets a hard limit like Guard's, but it will be calculated backwards from tests: once damage sources are known, set the HP limit that keeps evenly matched fights at the target length.

**Resolved 2026-10-16: Poise no longer dominates.** Poise counted twice (Martial attack pair and Defense). Ten options were tested by raising one attribute by 10 from an even 55 start. Adopted: Martial weapons attack with Might + Acuity, and Defense = armor + Poise + Vigor. Value of +10 points before → after: Might 74% → 74%, Poise 78% → 68%, Vigor 52% → 70%, Acuity 50% → 65%. Draft armor bases dropped by 1 to keep duel length on target.

**Calibration after the change (Proposed, 2026-10-16):** Grit = Vigor tens digit; Rally and Stay Standing once per encounter. Builds reallocated for the new rules (a new fighter spreads points over Might, Acuity, Poise and Vigor).

| Fighter | Attack | Damage | Defense | GR | Guard | HP |
| --- | --- | --- | --- | --- | --- | --- |
| Duelist (Might 60, Acuity 55, Poise 55, Vigor 55; sword, light) | +3 | d8+1 | 12 | 1 | 8 | 10 |
| Defender (Might 60, Acuity 55, Vigor 60; sword, plate, shield) | +3 | d8+1 | 13 | 3 | 10 | 11 |
| Bruiser (Might 60, Vigor 60, Poise 50; greataxe, light) | +4 | d12+1 | 12 | 1 | 8 | 11 |
| Skirmisher (Poise 60, Acuity 60; dagger, no armor) | +4 | d4+1 | 11 | 0 | 8 | 10 |
| Veteran Duelist (XP ceiling, Fine gear) | +7 | d8+2 | 18 | 1 | 10 | 11 |

| Matchup | Side 1 wins | Avg rounds | 90% end by |
| --- | --- | --- | --- |
| Duelist vs Duelist | 50% | 8.4 | 12 |
| Defender vs Bruiser | 50% | 8.3 | 12 |
| Defender vs Duelist | 79% | 9.3 | 13 |
| Bruiser vs Duelist | 71% | 7.0 | 10 |
| Skirmisher (dagger) vs Duelist | 24% | 8.4 | 12 |
| Skirmisher (rapier) vs Duelist | 37% | 7.9 | 11 |
| Duelist vs 2 Thugs | 50% | 8.3 | 12 |
| 3 Duelists vs 3 Duelists | 51% | 11.9 | 17 |
| Veteran Duelist mirror | 50% | 9.9 | 14 |
| Veteran Defender vs Veteran Duelist | 49% | 9.8 | 14 |
| Veteran Duelist vs new Duelist | 99% | 6.2 | 9 |

Watch items: heavy weapons are strong (the greataxe Bruiser beats the Duelist 71%) because Vigor now feeds the heavy attack pair, Defense, HP and Grit; Committed great-weapon strikes, not yet modelled, may be the natural cost. Group fights run long (3v3 about 12 rounds). Veteran duels run about 10 rounds, with Overwhelming criticals disappearing between veterans (Defense 18 against +7).

**Calibration with every adopted rule on (Proposed, 2026-10-16):** Committed Strike (+2 to hit, carry-through, no reaction and −2 Defense while pending, used when the foe's Guard is low), Shield Block as +3 Defense, Rally and Stay Standing once per encounter. Results: Duelist mirror 6.4 rounds (90% by 10), Defender vs Bruiser 54% in 6.5, Defender vs Duelist 84%, Bruiser vs Duelist 73%, dagger Skirmisher vs Duelist 14%, 3v3 10.7 rounds, veteran mirror 7.1. Hit chance rises to about 65–70% and Overwhelming criticals to about 25% of hits, because a Committed Strike swings 4 points (+2 to hit, −2 Defense on the committer). Duels now run slightly under the 7-round target; revisit Guard or HP when the HP limit is derived, after crit conditions are modelled.

**Calibration with crit conditions (Proposed findings, 2026-10-16, corrected):** engine now applies the weapon crit table with Common gear, binding Bleeding with one bandage per fight. Bleeding does not break Committed actions, because the Established text breaks them only when a hit damages HP. Fight length is unchanged (Duelist mirror 6.3 rounds, 2v2 8.7). Crits land about 2–3 times per duel. The dagger Skirmisher rises from 13% to 25% against the Duelist (2v2: 11% to 25%); Bleeding deals about 4.4 HP per dagger duel. (A first run wrongly let Bleeding break Rally and Committed Strikes, which pushed the dagger to 49%.) Every other condition is worth almost nothing in a single fight: Common versus Crude gear moves greataxe, maul, spear, mace and sword results by 0–2 points, and Fine or Masterwork upgrades for those families by the same. The one big quality swing is a Fine long blade choosing Bleeding (about +10 points). The other conditions pay off through systems the engine doesn't model yet: Injuries (Exposed sends a hit to HP, where the wound threshold lives), HP attrition across fights (Guard resets, HP doesn't), movement (Impaled, Slowed, Prone's half-Speed stand) and future abilities. Initiative rerolled each round lets an attacker sometimes act twice in a row, so 'until the end of the target's next turn' conditions occasionally help the attacker too; fixing initiative per fight changed results by 4 points or less. Grit is unaffected: about 1.1 Grit spent per duel, and the weekly pool results match the earlier runs.

**Movement and range in the engine (Proposed findings, 2026-10-18).** The engine now has a positional mode: a straight-line field, Speed 30, Sprint, Prone's half-Speed stand, Slowed, Impaled, reach, bows and thrown weapons, and walls for Driving Strike collisions. Placeholders, not canon: longbow d8; javelin d6 (spear family) with a 60 ft range; no range penalties; Juggernaut's undefined Charge treated as moving up to your Speed again and making a melee attack. Not modeled: cover (no rule yet), Croisé, Promenade, Breach and creature collisions (they need a grid). Builds use the Duelist's attributes; 3,000–4,000 fights per result.

- **Committed Strike and leaving reach.** Nothing stops a character leaving an engagement, so a target simply steps out of reach and the strike fizzles. When players do that, the Duelist mirror stretches from 6.4 to 9.1 rounds and builds that commit lose 4–13 points against the Duelist (Defender 83% to 70%, Spearman 61% to 52%, greataxe Bruiser 73% to 69%), while the dagger gains 13 (44% to 57%). Letting the strike follow 10 ft changes nothing (the target steps 20 ft). Proposed fix: leaving the reach of a creature whose Committed Strike targets you makes it resolve at once, before you move. That restores the calibrated results exactly (letting the strike follow up to your Speed does too, with more bookkeeping). The results below assume this fix.
- **Melee baseline.** With the fix, melee matchups match the old all-engaged engine within 1–2 points; a 60 ft approach adds about half a round.
- **Archers.** An archer with the Duelist's numbers (same +3 to hit, d8+1, no Parry) beats the Duelist 58% from 60 ft (one free volley; 45% if the fight starts in reach), and 71% if it kites in an open field. It loses to plate and shield (Defender 21%) and beats the dagger (61%). Shooting with a foe in reach has no penalty; options tested (archer wins when caught at 0 ft / standing at 60 ft / kiting / in 2v2): none 46/58/70/44%; −1 to the shot 39/50/67/43%; −2 to the shot 33/44/61/40%; can't Ward that turn (it Harries instead) 45/56/67/47%; −2 Defense until your next turn 34/48/60/41%. Adopted 2026-10-18: −2 Defense against melee attacks until the start of your next turn, for bows and crossbows only (see Shooting in the press).
- **The Tempo kite.** In an open field, an archer that spends Chassé every turn stays out of reach indefinitely, paid for by the on-turn beat its ranged attacks earn: 49% to 81%, and the Duelist has to Sprint about 5 times a fight. If only melee attacks earn the on-turn beat, it drops to 52%. Walls mostly remove it anyway (180 ft arena 47%, 100 ft room 37%). Melee Tempo results don't change with movement (dagger Skirmisher 46–47%). Pas de Deux adds about 1 point in 2v2 (0.7 uses a fight).
- **Ironstring.** Even head-to-head with a plain archer (49% at Might 60, 52% at Might 70), but against the Duelist it wins 71% where the plain archer wins 60% (65% if the Duelist stops committing into it). Draw Weight does almost all of it: pushing a committed foe out of reach breaks its strike. Without Draw Weight, Ironstring falls to 55%, below the plain archer, because its gains replace the universal ones and starve Crushing Blows. Pinning Shot and Full Draw add about nothing. Rerun with Shooting in the press (and a pending Full Draw's −2 Defense): against the Duelist the plain archer wins 49% and Ironstring 63%, so the 14-point Draw Weight gap remains.
- **Hurler.** 48% at Might 60 (50% at 70) against the same build carrying javelins. Its gains come only in round 1 (about 0.8 Momentum a fight), so it never reaches Hold I; throwing at adjacent foes makes it worse (39%). It needs a gain source in melee, or a reason to break away and throw again.
- **Vanguard.** Played straight, it wins 47–48%. Backing off 10 ft and re-closing each turn farms 'move 10+ ft toward a foe and attack' (56%), since nothing stops leaving. Collisions matter only in tight spaces: in a 30 ft room it wins 58% (Battering Ram 0.6 times a fight).
- **Driving Strike and Juggernaut.** Rarely worth spending in duels. In the open, Driving Strike's use is pushing a foe out of reach to break its Committed Strike. Into a wall it turns Momentum into Guard damage 1 for 1 with no cap (the Crushing Blows cap doesn't apply), but in a 30 ft room that came up only about 0.2 times a fight. Juggernaut is starved: chasing a kiter is exactly when you have no Momentum (0.04 uses a fight).
- **Prone, Slowed and Impaled** matter only when foes are apart, which is rare in duels; in 1v1 Prone is nearly worthless because the target stands at the start of its turn. Shove isn't simulated yet. Conflict to settle: the Wrestle table has Shove resolved by a Footing save, while the 2026-10-18 Decision log row calls it an unarmed attack against Defense.

### Initiative and action commitment (Established draft)

- **Initiative is rerolled every round**, representing control of the fight's rhythm.
- **Tempo** is the main tool to manipulate it: add to the roll, move up after rolling, or swap with an ally. Authority, Focus and Fortune may also touch initiative.
- **Instant actions** resolve immediately on your turn. This is the default: attacks, most spells, grapples, shoves, potions.
- **Committed actions** are declared now and resolve later, so everyone sees them coming and can react: overhead great-weapon strikes, charges, bracing a spear, rituals, powerful sorcery.
- **Quick actions were dropped** because initiative, Poise and Tempo already cover speed. Weapon identity comes from Guard pressure and crit effects, not timing.
- Simultaneous secret declaration and weapon-speed phases were considered and rejected as too heavy.

**Declare-then-act round (Prototype, Proposed 2026-10-19).** Goal: make prediction matter by letting creatures see what is coming. Initiative would decide who *hears* more, not only who strikes first. Each round:

1. **Initiative**, rolled as now.
2. **Declare, slowest first.** Each creature states its Minor (Harry or Ward) and its Major (attack a named foe, Committed Strike on a named foe, Rally, Use an Item, Wrestle, Sprint and so on). The GM declares monsters' intents in the fiction ("the brute draws its maul back toward Aldric"). Quicker creatures hear everyone slower than them before they choose.
3. **Act, fastest first.** Each creature carries out what it declared. If its target has fallen, it makes the same action against another foe, or holds.
4. **Committed actions resolve at the end of the round**, fastest first. Until then their costs apply (Committed Strike: no reaction, −2 Defense), and a hit to HP breaks them.

Open: whether you may change a declaration when your turn comes, at a cost (for example 1 Focus); whether initiative is rolled each round or once per encounter.

**Prototype findings (Proposed, 2026-10-19; everyone engaged, no movement yet).** The round itself works. With every creature on the old rule of thumb, matchups stay within 0–5 points of the old turn order (Bruiser and Spearman drop 5, since their strikes now wait until the end of the round) and fight length is unchanged (Duelist mirror 6.1 rounds). But reading is worth little:

- A reading player beats the same build on the rule of thumb only 48–53%.
- Even hearing every foe's plan, it wins 45–55% in duels and 46–64% in 2v2 (the gain is mostly in choosing targets).
- +5 initiative is worth about the same as before (57% old, 58–59% declare-then-act).
- Initiative rolled each round or once per encounter changes results by 2 points or less.

Why: the Exchange's options pay off in small, similar amounts (Harry +1 Guard damage, Parry −2, Dodge +2 Defense, Block +3), so knowing what a foe will do rarely changes your best answer. The round structure gives prediction somewhere to live; options that clearly counter each other (the proposed counter-wheel of Press, Ward and Committed) are what would make it pay.

**The counter-wheel (Prototype, Proposed 2026-10-19).** Built on the declare-then-act round. Each round, each creature declares one stance:

- **Press:** attack a named foe (Harry included). No defensive reaction this round.
- **Guard:** no attack. Ward against every attack this round (a reaction for each), and +2 Defense against attacks that aren't Committed. Riposte: when a melee attack against you misses, attack that foe at once. If nothing hit you this round, regain 1 Guard at the end of it.
- **Commit:** a Committed Strike on a named foe. It lands at the end of the round with +2 to hit, Guard overflow carrying to HP, and it crashes through: the target can't Parry, Block or Dodge it, and the Guard stance's bonus doesn't apply. Until it lands: no reaction, −2 Defense. Any hit on you before then knocks it off line, so it lands as a plain attack (no +2, no carry, no crash-through); a hit to your HP still breaks it entirely.

The wheel: Press beats Commit, Guard beats Press, Commit beats Guard. Who declares first: the GM declares every monster's stance and target first, in the fiction; the players then declare, talking freely; everyone acts in initiative order and Committed actions land at the end of the round. Rally and binding a wound stay separate Majors.

**Counter-wheel findings (Proposed, 2026-10-19; everyone engaged, Duelist-stat builds).**

- **Reading now matters.** Without the wheel, a player who hears every foe's plan wins 45–55% against a same-stat rule of thumb. With the wheel as written above it wins 72–82% (78–92% against random stances). A harder wheel, where any hit cancels a Commit, makes it 88–96%: reading decides almost everything.
- **Initiative must not decide who declares last.** Between equals, whoever declares last counters every round, so +5 initiative wins 75–85% (old turn order: 57%), whichever side of initiative declares first. Declaring by side (monsters first, then players) avoids this.
- **Monster "read tax."** For a same-stat foe that telegraphs to give a perfect reader an even fight, it needs about +6 Guard, +6 HP and +1 damage (52%). Monster design lever: cunning foes could declare after the players, or feint.
- **Calibration.** With everyone on the rule of thumb, fight length is unchanged (Duelist mirror 6.1 rounds); the Defender drops from 86% to 76% against the Duelist, the Bruiser from 74% to 69%, and the dagger goes from 45% to 48%.
- **Not yet worked out:** Tempo, Momentum, Ironstring's Full Draw, Quick Blade and Shield Block under stances; movement (leaving reach while in Guard); Expressions that bend the wheel (a Feint, holding a Commit through a hit).

**Expressions in the counter-wheel (Proposed findings, 2026-10-19).** A reading player against a same-stat monster carrying the read tax (+6 Guard, +6 HP, +1 damage) wins 52% (8.9 rounds); each Expression was switched on for one side. Feint, Unbroken and Adapt are test abilities, not canon.

- **Existing uses barely move it.** Refine +1 point. Tempo kit (Off Beat, Pirouette, Coda, Plié) +4, mostly Pirouette and Coda. Off Beat is never used, because a reader never presses into a Guard. Crushing Blows +1. Breaker ±0. Bulwark gains nothing in light armor (it Dodges instead of Parrying).
- **Abilities that bend the wheel move it a lot.**
  - **Feint** (test, 2 Tempo): show a false stance, then use the stance that beats the player's answer. As a monster tool it drops the player from 52% to 40% when used half the time it can (0.65 a fight), and to 33% when used every time.
  - **Unbroken** (test, 1 Grit): a hit doesn't knock your Commit off line. As a monster tool, 52% to 38%. A reading player never needs it, since it only commits when nobody can hit it.
  - **Cunning foes**, who declare after the players, are brutal: an equal-stat cunning monster wins 91%. **Adapt** (test, 1 Focus: change your stance after everyone has declared) brings the player from 9% to 17%, or from 22% to 37% against a cunning foe with −3 Guard and −3 HP.
- **Implication.** The current Expression uses were built for the old turn; in the wheel, their value would come from bending a different edge of it. Tempo is deception (Feint), Focus is perception (Adapt, seeing through a Feint), Grit is holding on (Unbroken), and Momentum is force (for example, a Press that overbears a Guard). Monster design gets four levers: the read tax, cunning, feints and Unbroken.

**Choice matrices (Proposed findings, 2026-10-19).** A one-round payoff test, Duelist against Duelist: for each pair of choices, the net Guard and HP swing (HP counted double). It checks whether the right answer depends on the foe's choice.

- **Established Exchange** (Harry and attack, Ward and attack, Committed Strike): the Committed Strike is the best answer to everything, both at full Guard and once Guard is worn to 4. The best and worst answers differ by only 0.3 at full Guard (2.7 once Guard is worn). This is the structural reason commits are spammable and reading barely pays.
- **Counter-wheel as drafted:** choices matter about ten times more at full Guard (spread 3.2), and no stance is always best. But it isn't a true wheel yet:
  - Guard is never the best answer; even against Press it loses (−0.75).
  - Once Guards are worn, Commit is best against everything.
  - The high win rates for reading players came mostly from punishing opponents who Guard or Commit at the wrong time, not from a balanced cycle.
- **Next test:** tune Guard until it beats Press, and make Press clearly beat Commit when Guard is low, until every stance is the best answer to something in every state.

**Counter-wheel v2 (Prototype, Proposed 2026-10-20; supersedes the draft above for testing).**

- **Press:** attack a named foe (Harry included). No defensive reaction this round.
- **Guard:** no attack. You may Ward against every attack this round. Against attacks that aren't Committed, you get +2 Defense and their Guard damage is reduced by 1. Riposte: once a round, after a melee attack against you, hit or miss, attack that foe at once. If nothing hit you this round, regain 1 Guard.
- **Commit:** a Committed Strike on a named foe. It lands at the end of the round with +2 to hit and Guard overflow carrying to HP. The Guard stance's +2 and its damage reduction don't apply against it, but Parry, Block and Dodge do. Until it lands: no reaction, −2 Defense. Caught mid-wind-up: any hit on you knocks the strike off line (it lands as a plain attack), and that hit's Guard overflow carries into your HP; a hit to HP breaks the strike entirely.
- **What can be seen:** a foe winding up a Committed action (a strike, a Rally, a charge, a ritual) is visible, and the GM announces it. Whether a foe will Press or Guard is not visible: the GM decides it when declaring and reveals it in play. **Read the Fight** (test, 1 Focus, once a round) reveals one foe's stance.

**v2 findings (Proposed, 2026-10-20).**

- **It is a true wheel.** In the one-round matrix, every stance is the best answer to something, at full Guard and with Guard worn to 4. Guard beats Press by 0.9 (1.2 when worn), Press beats Commit by 0.9 (3.5), Commit beats Guard by 3.6 (4.5).
- **The balanced mix is about two-thirds Press, a sixth Guard and a sixth Commit** at full Guard; Guard rises to about a third once Guards are worn. Committing is now an occasional read, not a stance.
- **Calibration holds with both sides on the rule of thumb.** Duelist mirror 51%, 6.1 rounds. Against the Duelist: Defender 77% (old engine 86%), Bruiser 68% (74%), Spearman 60% (60%), dagger 47% (45%). With both sides playing the balanced mix, fights run about 8 rounds.
- **Full visibility breaks it.** If every stance is visible, a player who hears the foe wins 85–95% even against the balanced mix, because in a true wheel knowing the choice means always countering it. Hence only wind-ups are visible.
- **With only wind-ups visible,** reading is worth +10 to +24 points:
  - The hearing player wins 55–73% against a same-stat foe playing the balanced mix, and 61–74% against the rule of thumb.
  - The read tax is small: a monster with +2 Guard and +2 HP gives 56%.
  - Read the Fight adds about 16 points (60% to 76% against an equal foe), which gives Focus a central role in the wheel.

*Power should come at the cost of commitment.*

### Action economy (Open)

Proposed: replace 5e bonus actions with **1 Major + 1 Minor action, movement, and 1 reaction**. Reactions should be common. Optional stances and a per-turn "Tactical Step" were floated. You haven't decided, and existing abilities still say "bonus action."

**Update 2026-10-21.** Bonus actions translate to Minor actions (Established). Proposed: emulate Pathfinder 2e's three-action turn. This conflicts with the Established Exchange structure below (Move + 1 Major + 1 Minor + 1 reaction, tested to an even 8-round duel), so the Exchange stands until the creator decides (deferred 2026-10-21: all work continues on the Exchange, and a switch would be handled when it happens); if adopted, the Exchange, Committed Strike, Harry, Ward, Sprint and every action-costed ability need re-pricing and the duel sims need rerunning.

#### The Exchange: turn structure (Established structure; numbers Draft)

Each turn you make one damage decision (your Major action) and one rhythm decision (your Minor action): press the foe or guard yourself. These are generic actions every character can use, before any path ability interacts with them. Tested at level 1, this gives an even duel of about 8 rounds with no single always-correct choice.

**Your turn:** Move + 1 Major action + 1 Minor action. **Reaction:** 1 per round, refreshed at the start of your turn.

| Action | Type | Effect |
| --- | --- | --- |
| Move | Movement | Move up to your Speed, set by race and subrace: most 30 ft, some 25 or 35 ft |
| Attack | Major, Instant | d20 + attack bonus vs Defense; damage hits Guard (minus armor GR), or HP at 0 Guard |
| Committed Strike | Major, Committed | See Committed Strike below |
| Wrestle | Major | Grab or Shove a foe; it resists with a Footing save. Rules text to be written |
| Sprint | Major | Move up to your Speed again this turn (twice your Speed in total). Not while Grabbed; difficult terrain still costs extra |
| Use a Skill | Major | Make one d100 skill test whose outcome matters now, at a difficulty the GM sets: Hide (Stealth), Search for a hidden foe, object or trap, Help (your success makes an ally's next test one tier easier; Help doesn't boost attacks), Recall lore, Sway a foe (Influence), Tend a wound (Medicine). Combat tests can earn ticks and trigger Breakthroughs and Setbacks. What Hide and Tend achieve waits on the Hidden condition and the Dying and Bleeding rules |
| Ready | Major | Choose a trigger and an action; when the trigger happens before your next turn, take the action. Uses your Major action and your reaction |
| Use an Item | Major | Use an item that has an effect (potion, bandage, oil) |
| Cast | Major | Placeholder until magic is built |
| Harry | Minor | Choose before your Attack this turn (any weapon attack, including a Committed Strike declared this turn). If it hits and damages Guard, it deals +1 Guard damage (changed from +2 on 2026-10-18; boosts add to this base). Never adds damage to HP and never carries through; no effect against a foe at 0 Guard |
| Ward | Minor | Until the start of your next turn you may spend your reaction on Parry, Shield Block or Dodge; without Ward you can't use them. One defensive reaction per round. Not available while Ready or a Committed Strike holds your reaction. Mark it with a token |
| Interact | Minor | Draw or stow, open a door, pick up an item |
| Parry | Reaction (Ward) | When a melee attack hits you while your Guard is above 0, reduce that hit's Guard damage by 2 (after armor GR, minimum 1). You must be holding a melee weapon. Future upgrade: Parry projectiles |
| Shield Block | Reaction (Ward) | When a creature makes an attack roll against you, declare before the roll: +3 Defense against that attack (Draft value). Requires a shield; works in any armor, against melee and ranged attacks, whatever your Guard. Shield type may change the value later |
| Dodge | Reaction (Ward) | When a creature makes an attack roll against you, declare before the roll: +2 Defense against that attack. Light or no armor only; works whatever your Guard. Not while Grabbed or Prone; does not apply to saves (area effects use Reflex) |

**Wrestle rules text (Established 2026-10-18; numbers Draft).** Wrestle is a Major action with three base uses: Grab, Shove and Escape (revised 2026-10-18; Pin and Grab-as-a-strike come only through specific abilities, such as Sword path abilities). Grab, Shove and Pin are melee attacks using the unarmed pair ((Might or Poise) + (Acuity or Vigor)) against Defense; they deal no damage, Harry doesn't apply, and they can crit (the unarmed crit effects). Your **Wrestle DC** = 10 + your Might modifier + your Poise modifier (the Footing pair, capped at +7). Grappling is its own mechanic, not Athletics.

| Use | Needs | On a hit |
| --- | --- | --- |
| Grab | A free hand; the target no more than one size larger than you | The target is Grabbed. You hold it with your main hand; while you do, you can attack only with your off hand (a fist or a one-handed weapon held there), and you can't use a two-handed weapon. You can move it with you at half Speed. |
| Shove | — | The target makes a Footing save against your Wrestle DC; on a failure you push it 5 ft or knock it Prone (your choice; a creature larger than you can only be pushed). |
| Pin | A creature you already have Grabbed; both hands | The target is Restrained (Major). You can't attack while pinning. Not a base use: Pin is unlocked only by specific abilities. Once available, you can't Pin the same creature on two turns in a row (Established 2026-10-18). |
| Escape | You are Grabbed or Restrained | No attack roll: make a Footing save (strength) or a Reflex save (slipping free), your choice, against the grabber's Wrestle DC. Success ends Grabbed, or turns Restrained into Grabbed. |

Grabbed and Restrained also end when the grabber lets go (no action), is Incapacitated, or is moved out of reach. Dodge can avoid a Grab, Shove or Pin like any attack; Parry can't reduce them (they deal no Guard damage). Momentum: a successful Grab or Shove generates Momentum for characters without a Doctrine; Brawler's triggers are listed with the Doctrine.

**Holding on (Established 2026-10-18; numbers Draft):** when a hit damages your HP while you are grabbing or pinning a creature, make a Fortitude save, DC 10 + the HP damage taken (Established 2026-10-18). Off-hand attacks while grabbing take the general off-hand penalty, which is still to be set; later abilities can reduce it. On a failure you lose your grip and the creature is free. Escape stays a Major action.

**Wrestle and Brawler sims (Proposed findings, 2026-10-18).** A Might-60 grappler in light armor against the sword Duelist. As written: an unarmed striker who never grapples wins 17% (fists are d4 with no Misericorde); a grappler without a Doctrine wins 22%; the Brawler Doctrine 35%; a Brawler with a dagger in the off hand 41%. An off-hand penalty of −2 would cost 5–7 points. Two problems: Grab spends a Major action for a weak effect (Grabbed only removes Dodge and movement), and Pin and Escape trade Major actions with no damage, so duels with pinning run about 12 rounds instead of 6–7 (the grappler wins mainly by making the victim spend turns escaping; a one-round Pin that needs no escape drops the grappler to 0–2%). In 2v2 a Brawler pair falls to 31–34%, because the Grab turn does nothing for the party. Tested fix: Grab as a strike that seizes (an unarmed attack that deals its damage and leaves the target Grabbed on a hit): no-Doctrine grappler 32%, Brawler 44%, Brawler with an off-hand dagger 52%, Brawler in 2v2 47% (52% if it never Pins). Pin's stall remains. Letting grabbed foes not Parry the grabber changed nothing measurable.

**After the 2026-10-18 revision (Proposed findings):** with base Wrestle only (Grab, Shove, Escape), a grappler wins 9% against the Duelist, a Brawler 9%, a Brawler with an off-hand dagger 16%, and a Brawler pair 36% in 2v2: grabbing costs a Major action and the follow-up is a d4 off-hand fist. With Pin unlocked (no repeat): Brawler 22% (9.8 rounds), with dagger 32%. With Pin and Grab-as-a-strike unlocked: Brawler 34%, with dagger 45%, Brawler pair 50% (fights about 10 rounds, down from 12.6). The no-repeat rule shortens the Pin stall but doesn't remove it.

Removed 2026-10-16: Step (cut); Withdraw and Opportunity Strike (to become feats or abilities); Rally (moved to Grit's uses). Grapple and Shove became Wrestle; Hide, Search and Help became Use a Skill.

**Leaving a fight (Established 2026-10-16):** nothing in the base rules stops a character from leaving an engagement. Feats and abilities (an Opportunity Strike feat, abilities that pin a foe in place, a Withdraw counter-feat) can change that, so a foe who won't let you leave is a surprise, not a rule. Wood Elves keep 40 ft Speed, the only race outside the 25–35 ft range for now.

**Shooting in the press (Established 2026-10-18; value Draft):** when you make a bow or crossbow attack while a hostile creature that can act has you within its reach, you take −2 Defense against melee attacks until the start of your next turn. Thrown weapons are exempt. It stacks with a Committed Strike's −2 Defense. Full Draw is a Committed Strike made with a bow; declaring it while in the press counts as shooting in the press, instead of when it resolves, so you are at −4 against melee attacks until it resolves (Established 2026-10-18; clarified 2026-10-26).

**Surprise (Established 2026-10-16):**

- **Surprised:** ambushed in a fight you didn't see coming. In the first round you act after everyone who isn't Surprised, and you can't Ward or use reactions until your first turn ends. It ends at the end of your first turn.
- **Unaware:** asleep, fully distracted, or with no idea an enemy is there. An attack against you ignores your Guard and hits HP directly. It ends the moment you are attacked or warned.
- **Springing an ambush:** each ambusher makes a Stealth test (Use a Skill: Hide) at a difficulty set by the targets' watchfulness (Normal for a careless crowd up to Very Hard for alert sentries). If every ambusher succeeds, the targets are Surprised. Targets who could not possibly have noticed are Unaware. Unaware is meant for real ambushes only.

**Shield Block vs Dodge (Established 2026-10-16):** both raise Defense against one attack, separated by strength and fantasy. Shield Block gives the larger bonus but costs your off-hand and needs a shield; Dodge gives less but leaves your hands free and needs light or no armor. Tested: Shield Block at +3 Defense performs like the old −3 Guard version (plate-and-shield defender beats the greataxe fighter 48%, the duelist 78%); +4 is slightly stronger and +2 slightly weaker.

**Committed actions (Established 2026-10-16):** declare a Committed action as your Major action and name its target. It resolves at the start of your next turn, before you do anything else. If a hit damages your HP before then, the action is broken and has no effect; a hit that only reduces your Guard does not break it. You can have only one Committed action pending at a time. Rally, Committed Strike, charges, bracing a spear and rituals all use this frame.

Future design notes: add a defensive Committed action; let characters who invest in Committed actions gain more damage, keep their reaction while committed, or feint with a Committed action to bait foes.

**Blood-paid Commit (Proposed idea 2026-10-25, from the cut Divine Smite rework "Wrath Unanswered"; working name).** A possible Committed Strike upgrade: when you declare a Committed Strike, you may lose 1d4 HP (ignores Guard, can't be reduced, paid whether or not the strike lands). This loss does not break the strike. If the strike hits, its damage ignores the target's Guard and goes straight to HP. If the cost drops you to 0 HP, you fall Dying and the strike is lost. Unsimmed; check against Committed Strike's existing carry-through and the three-action payoff (+2 damage, free landing strike). Flavor reference: *No god heard the prayer. So she paid for the answer herself.*

**Committed Strike (Established 2026-10-16):** Major action, Committed. Choose a foe within your melee reach. Until the strike resolves you have no reaction and take −2 to Defense. When it resolves, make an attack against that foe with +2 to the attack roll. If the hit reduces the foe's Guard to 0, any damage left over after armor carries through to its HP; Harry's bonus never carries through. Melee only for now (a ranged "Aimed Shot" may come with bows). Tested: timed for when the foe's Guard is low, it wins 56–58% against not committing for a duelist or a greataxe fighter, and only 46% for a plate-and-shield defender, so it pays off when timed well without being automatic.

Established (2026-10-16): if the foe has left your reach when the strike resolves, you may strike another foe within reach instead; if there is none, the strike ends with no effect and your reaction and Defense return at once, so nothing else is lost.

**Universal actions improve with training (Established direction 2026-10-16):** every combat action available to all characters (Parry, Dodge, Shove, Grapple and the rest) may be improved through ability trees later. A wizard can try to Parry; a fighter who has trained it does it better. Build this into the ability trees after the first playtests; it does not affect them.

**Watch item:** one-handed weapons used with an empty off-hand (the shieldless Duelist, daggers) lose to two-handed and sword-and-shield kits. They need their own benefit when weapons are designed (a dueling style, a better Parry or similar).

**Retuned level-1 Guard:** commoner 6, trained fighter 8, shield and armor 10, greataxe bruiser 7, dagger skirmisher 6. Each fighter has 1 Grit (one Rally).

**Results** (simulated, Harry/Ward chosen by simple tactics)

| Matchup | Side 1 wins | Avg rounds | 90% end by round |
| --- | --- | --- | --- |
| Duelist vs Duelist | 49% | 7.9 | 11 |
| Defender vs Bruiser | 62% | 8.1 | 11 |
| Skirmisher vs Duelist | 37% | 8.7 | 13 |
| Duelist vs 2 Thugs | 49% | 7.6 | 11 |
| 3 Duelists vs 3 Duelists | 50% | 10.4 | 16 |

**No choice dominates.** Always Harry vs tactical play: 49%. Always Ward vs tactical: 48%. Always Harry vs always Ward: 52%.

**What the testing ruled out**

- **Unlimited Rally:** when both fighters can Rally freely, duels stretch to 13–15 rounds whatever the Guard size, because any regained Guard soaks a whole hit. Tying Rally to Grit caps it.
- **A Minor action that restores Guard:** it becomes the right move every turn and pushes duels past 20 rounds.
- **Free defensive reactions every round:** add about 2 rounds and favor armor heavily. Requiring Ward makes defense a choice that costs pressure.

**Why it fits:** Harry or Ward is a readable, repeated choice that builds the rhythm you asked for. A broken Guard becomes a decision point: spend Grit and risk a Rally, or fight on exposed. Light fighters get an identity through Dodge (the dagger Skirmisher rose from 23% to 37%). Reactions stay common, as the Bible intends.

**Tradeoffs and edge cases**

- Ward needs a marker (a token or die) until your next turn.
- Rally spends Grit, so Vigor helps in long fights. Watch that it does not become a mandatory attribute; every character should have at least 1 Grit.
- Abilities that say "bonus action" (Spur to Strike, Visage of Frenzy, Hunter's Mark and others) would become Minor actions. They then compete with Harry and Ward, which gives them a real cost.
- Group fights still run about 10 rounds; monster design (several weaker foes, multi-attack brutes) is the lever there.
- Not yet modeled: crit conditions, Tempo, Momentum, Focus steering, Committed Strikes and movement.

**Favoring a fantasy is intended (Established direction).** Heavy armor should be the easiest way to guard and Ward. Tanking without armor should still be possible: an armored fighter tanks with few resources and little thought, while an unarmored character (a mage, say) tanks through creative use of abilities, magic and resources. Light weapons such as daggers earn their place through crit conditions and creating openings, not raw damage.

### Three-action economy (Proposed; proof 2026-10-24)

Why: the creator's players enjoy Pathfinder 2e, so a PF2e-style three-action turn is being proved out for everyday combat. Dramatic single combat gets its own hidden-intent system (Showdowns, below). This is a test of a possible replacement for the Exchange; the Exchange stays the current rule until the creator adopts or rejects this.

**Rules tested (Proposed):**

- Each turn: 3 actions and 1 reaction.
- **Strike** (1 action). The 2nd and 3rd Strike in a turn take −4 and −8; light weapons (agile) take −3 and −6. PF2e's −5/−10 doesn't fit Asloria's +2 to +7 attack bonuses.
- **Ward** (1 action): enables Parry, Shield Block or Dodge and gives +1 Defense until the start of your next turn (like PF2e's Raise a Shield).
- **Committed Strike** (2 actions, Committed): lands at the start of your next turn with +2 to hit, carry-through and **+2 damage**, and doesn't count toward that turn's attack penalty. −2 Defense and no reaction while pending, as now.
- **Harry** cut: a second Strike already does the pressing.
- Standing from Prone costs 1 action (engine assumption, needs a ruling).
- Former bonus-action abilities cost 1 action.

**Proof results** (Proposed findings). Engine rebuilt from the Bible's builds, crit conditions, Rally, Stay Standing and bandages; all-engaged, no movement or Expressions; 3,000–5,000 fights per result. The rebuilt Exchange baseline matches the Bible within a few points except the dagger (38% here, 25% in the Bible's all-engaged run).

| Matchup | Exchange now | 3-action, Guard/HP +2 | 3-action, Guard/HP +4 |
| --- | --- | --- | --- |
| Duelist mirror | 50%, 6.7 rds | 49%, 5.5 | 50%, 6.3 |
| Defender v Duelist | 79%, 7.5 | 82%, 6.2 | 83%, 7.2 |
| Bruiser v Duelist | 70%, 5.7 | 72%, 4.7 | 73%, 5.3 |
| Dagger v Duelist | 38%, 6.9 | 28%, 5.5 | 26%, 6.3 |
| Defender v Bruiser | 51%, 6.7 | 51%, 5.6 | 51%, 6.4 |
| Duelist v 2 Thugs | 43%, 7.7 | 43%, 6.5 | 44%, 7.7 |
| 2v2 Duelists | 50%, 8.8 | 50%, 7.4 | 50%, 8.4 |

- **Fight length.** Untuned, the mirror drops to 4.7 rounds (about 1.6 Strikes a turn). **Decided 2026-10-24: target about 5.5–6 rounds for an even duel, with Guard and HP each +2 (option b).** A 6-round three-action duel holds about as many decisions as a 7-round Exchange duel.
- **Committed Strike.** A straight conversion (+2 to hit, carry-through) is a trap: committers win 34–40% against fighters who never commit. With +2 damage and a free landing strike, well-timed commits win 53–56%, matching the Exchange. Removing the −2 Defense pushed it to 57–62% (too strong). Committing into a Guard already broken loses in every version.
- **Precision criticals.** Only about 0.4 of 1.9 crits per duel come from penalized attacks, because third Strikes are rare. No fix for now; watch abilities that grant cheap extra Strikes. Precision on first Strikes only costs the dagger about 2 points.
- **Attack penalty size barely matters** (−3, −4 and −5 give nearly identical results); −4/−8 is the working value.
- **Turn shapes are low-stakes.** Strike-Strike-Ward, triple Strike and a smart policy all land within 3 points of each other. Nothing dominates, but the decision value must come from one-action options competing for the third action: movement, Tempo Steps, Focus Actions and path abilities.
- **Harry as a one-action buff** is worth almost nothing.
- **Group fights shorten** (2v2 8.8 → 7.4 rounds), easing the old group-length watch item.
- **The dagger loses about 10 points**; light weapons need a smaller penalty, Tempo or other identity.
- **Initiative once per encounter** shortened fights and cost the dagger about 5 points; keep rolling each round for now.

### Showdowns: dramatic single combat (Proposed skeleton, 2026-10-24)

Everyday combat stays open and three-action; a Showdown switches to hidden intent for duels that matter. It builds on counter-wheel v2, whose one weakness (full visibility breaks it) doesn't apply when both duelists choose in secret.

- **Entering:** by agreement or challenge, or when the GM calls a climactic duel; two combatants engaged one on one while the scene pauses around them. A Showdown can never be entered while initiative is active (Established 2026-10-24).
- **Purpose (Established 2026-10-24):** a Showdown is a mini-game in which players compete narratively in single, mostly mutual combat. It is meant to be fun first.
- **Interruption (Established 2026-10-24):** if a Showdown is interrupted before it ends, it ends immediately, initiative is rolled, and all resources spent are refunded and all Guard and HP damage and conditions are reversed, so everyone returns to the state they were in before the Showdown. An interruption is any time a third party enters the Showdown. It is usually the players' doing, but the GM may interrupt a Showdown too.
- **Completed Showdown (Established 2026-10-24):** Guard, HP and conditions from a Showdown that reaches its end persist.
- **The fall (Established 2026-10-25):** if a duelist falls (0 HP), the Showdown ends at once, whatever the stakes. It counts as completed, so its damage persists, and the fallen duelist follows the normal Dying rules. In a duel to the death, the victor may strike the fallen foe (the normal rules for striking the Dying apply). In a duel to first blood or to the yield, a fall is an accident; striking again breaks the stakes, with consequences left to the fiction.
- **Allies (Established 2026-10-25):** any mechanical help to either duelist during a Showdown counts as entering it, so it is an interruption. Allies help before the duel (rumors, reputation, advice) and after it.
- **Who duels (Established 2026-10-25):** only a foe with a habit card duels. A beast or monster can have an instinct card: a base table plus reaction habits, with no Gambits, Techniques or unique Gambits.
- **Declining (Established 2026-10-24):** a duelist can always decline a challenge, with the consequences left to the fiction. Pride, honor or a hostage can press a foe into one.
- **Who may duel with what (Established 2026-10-24):** the three common Gambits (Disarm, Stop-Thrust, Headlong) are open to every duelist. Techniques and unique Gambits are what characters earn. Learned unique Gambits are not capped; the GM controls them through the moment of learning.
- **Stakes:** named before the first pass: to the yield, to first blood (the first HP damage), or to the death.
- **The pass:** each pass replaces a round. Both secretly choose **Press, Guard or Commit** and reveal together; resolve by the v2 wheel (Guard beats Press, Press beats Commit, Commit beats Guard). Guard, HP and Injuries work as normal, so Guard is the duel's "who's winning" track and no new resource is added.
- **Expressions bend the wheel:** Focus to *Read* (the GM reveals the foe's whole stance for this pass; Established 2026-10-24, Focus cost Established 2026-10-25: 1 Focus, at most 2 per Showdown); Tempo to *Feint* (after the reveal, switch between Press and Commit); Grit for *Unbroken* (a hit doesn't knock your Commit off line; in a Showdown it also keeps the Commit from breaking when the hit reaches HP, Established 2026-10-25); Momentum to *Overbear* (your Press breaks through a Guard).
- **Duel Techniques:** special actions that exist only in Showdowns. A character carries 2–3, learned through a Sword-path line (working name Dueling Forms); each is usable once per Showdown, played face-down with a stance. Sketches:
  - *Bind* (with Guard): if the foe Pressed, blades lock; next pass it can't Commit.
  - *Measure the Distance* (with Guard): next pass, the foe must name one stance it won't choose.
  - *The False Tell* (with Press): if the foe chose Guard, your attack ignores the Guard stance's bonuses.
  - *Misericorde* (with Commit, against a foe at 0 Guard): if it lands, it is an Overwhelming critical.

Showdown numbers on the three-action Guard/HP values and Technique and Expression strength were settled on 2026-10-25 (below). Hand size, nameless foes, allies and monsters were settled on 2026-10-25.

**Showdown sim (Proposed findings, 2026-10-24).** Duelist-stat builds with the three-action Guard/HP +2, crit conditions and bandages; no Rally; both stances hidden and revealed together; 4,000–5,000 duels per result. Test Expressions were given 1–3 uses per Showdown.

- **Rules fix needed (Proposed):** Riposte doesn't trigger against a Committed Strike (it crashes through). Without this, Commit doesn't beat Guard and the wheel breaks.
- **The wheel holds.** One-pass payoffs (net Guard + 2×HP): Guard beats Press by 1.2 (1.4 worn), Press beats Commit by 0.4 (2.2 worn), Commit beats Guard by 2.7 (3.1 worn). The equilibrium mix is Press 62%, Guard 8%, Commit 30% at full Guard, and 47/33/20 once worn.
- **Length.** To the death: 8.4 passes (90% by 13). To first blood: 3.8 passes. Showdowns inherit build gaps: Defender 79%, Bruiser 71%, dagger 20% against the Duelist.
- **Reading habits is the skill.** Equilibrium play neither exploits nor can be exploited (50% even against a foe who always Presses). An adaptive reader wins 52% against equilibrium, 74% against always-Press, 62% against an aggressive temperament (Press 80%), 53% against a cautious one. First-blood duels end before habits show (51%). GM implication: give foes a temperament for players to read; equilibrium play is the cunning foe.
- **Expressions, per use:** Feint (switch Press and Commit after the reveal) about +7 (57% at 1 use, 62% at 2), the strongest. Read revealing the whole stance about +4 (54%, 58%). Read naming one stance the foe didn't pick about +2 (52/53/56% at 1/2/3 uses). Overbear about +1. Unbroken about 0 (rarely triggers); its Showdown version (2026-10-25) is about +5 at one use, +6 at two.
- **Techniques.** The first sketches are worth nothing (47–52%): their effects depend on the foe picking a particular stance, so they fire only 0.14–0.37 times a duel. Stronger versions: Measure the Distance (next pass, the foe reveals first) +5 and always usable; False Tell (a Press into a Guard lands as a Commit) +2; Bind (a caught Press deals no damage and the foe reveals first next pass) and Misericorde (at Guard 4 or less, a landing Commit goes straight to HP) about 0. A hand of 2 gives 56%, a hand of 3 gives 57%, both sides holding a hand gives 50%, and a full kit (hand of 3, 1 Feint, 1 Read) gives 65% against a bare duelist.
- **Rules gap:** two Measures on the same pass cancel (each would need to see the other first).
- **Design lesson:** a Technique should change the reveal or the resolution whatever the foe picks, rather than pay off only if the foe chose a given stance; target about +4 to +6 each.

Next: redesign Bind, False Tell and Misericorde on that lesson and retest; decide the Read version and Feint's cost; Rally in Showdowns; the dagger's Showdown gap.

**Duel Techniques v3 (Proposed, 2026-10-24).** Redrafted on the design lesson: each changes the reveal or the resolution whatever the foe picks. Each is usable once per Showdown. Sim values are against a bare duelist of the same build, to the death, 5,000–6,000 duels each.

- **Measure the Distance** (information). *You give ground, watch the point of their blade, and learn the rhythm of their feet.* Play it with any stance. Next pass, your foe reveals its stance before you choose. If both duelists Measure on the same pass, both cancel. Sim: +5 (55%), used every duel.
- **Bind** (recovery). *Steel meets steel and locks at the hilts; whoever holds the bind decides what comes next.* After the reveal, if your stance loses, call the Bind: the pass doesn't resolve. You lose 2 Guard (holding the bind costs strength), your foe chooses a new stance openly, and you choose yours after seeing it. Sim: +4 at 2 Guard (54%), +7 at 1 Guard, +8 free; used 0.9 times a duel.
- **False Tell** (deception). *Your shoulder promises one thing and your blade does another.* After the reveal, if your stance loses, change it to the stance that beats your foe's. Sim: +8 (58%), and a −2 attack penalty on the switched stance changes nothing. It overlaps Tempo's Feint (+6): decide whether False Tell is the Sword-path Feint (and Feint stays a Tempo option), or one of them goes.
- **Misericorde** (finisher). *The thin blade between the plates, when there is nothing left to stop it.* Play it with Commit against a foe at 2 Guard or less. If the strike lands unbroken, the foe falls: Dying in a duel to the death, yielding in a duel to the yield. Sim: +3 at 2 Guard or less (53%), ends 0.19 duels in 1 by itself; at 4 Guard or less, +8 and 0.25 duels in 1 (too strong); at 0 Guard, +2. Its value is the dramatic close more than the win rate.

Hands. Measure + Bind + Misericorde: 65%. Measure + False Tell + Bind: 68%. Bind + Misericorde: 58%. Two duelists with the same hand: 50%. A full hand opens a large gap against an untrained duelist and none between trained ones, so a proposed default is 2 Techniques at first, rising to 3 through Dueling Forms.

These open items were all settled on 2026-10-25 (below): Bind's cost, False Tell versus Feint, Misericorde's threshold and Ebb severity, Techniques for foes, and the dagger's Showdown gap.

**Gambits (Proposed, 2026-10-24).** Creator's goal: the thrill of a niche choice that would usually be a mistake paying off big on a correct read. A Gambit is chosen in secret in place of a stance and revealed with it. Each punishes one stance hard, and a wrong guess always costs.

- **Disarm** (punishes Press): *you catch their blade on the rush and wrench it away.* Their attack doesn't happen, you make a free attack, and they spend the next pass recovering their weapon (no stance).
- **Stop-Thrust** (punishes Commit): *you strike into the wind-up.* Attack at +2, damage straight to HP; if it hits, their strike is broken.
- **Headlong** (punishes Guard): *you throw your whole body through their wall.* Their Guard drops to 0 and you make a free attack.
- **Wrong guess (all Gambits):** you're left open, and your foe makes a free plain attack against you on top of whatever its stance does.
- **A trick only works once:** a Gambit that pays off is spent for the Showdown; one that fails can be tried again.

**Sim (Proposed findings).** Duelist builds, to the death, 3,000–4,000 duels each.

- **Size of the moment.** A correct Gambit swings 5.5 to 15 points of Guard + 2×HP (Disarm +5.5, Stop-Thrust +8, Headlong +9 worn to +15 at full Guard), 3–5 times a correct normal counter (+1.2 to +2.7). Wrong, it costs 3 to 8.
- **The wrong-guess cost is the hinge.** Without it, Gambits are safe and become the whole game (equilibrium 100% Gambits). With the free attack at +2, or Headlong leaving you Exposed, they're never worth playing. A plain free attack leaves them niche: about 12% of passes at full Guard in equilibrium, and none once Guards are worn.
- **Headlong is never played in equilibrium** (Guard is a rare stance); it exists purely to punish a foe who habitually Guards.
- **Between balanced duelists** Gambits change nothing structural: 0.4 a duel, 35% right, 51% wins, 8.3 passes (unchanged).
- **Against a readable habit they deliver the moment.** A reader against an aggressive foe (Press 80%) goes from 58% to 63%, playing about 1 Gambit a duel and calling it right 71–80% of the time.
- **Guessing on a weak read loses.** Against cautious, reckless or balanced foes, Gambits played on any hunch are right only 41–46% and cost 0–5 points. Played only when the target stance seems at least 60% likely, they break even to +3 (balanced: 54% to 56%). The skill is waiting for the read.
- **No runaway combo with Read the Fight** in this test (Read ×2 plus Gambits: 0 to +4).
- **"A trick only works once"** never mattered in the sims (rarely right twice); it is kept for fiction and variety at no cost.

**Reading in Showdowns (Established 2026-10-24).** There is no rules mechanic for reading a foe's habits and no late-duel Gambit. The GM uses descriptive tools to tell players what they see (footwork, breathing, where the eyes go, how the foe answered the last exchange), and players decide from that description and their own pattern recognition. Gambits dropping out once Guards are worn is the intended shape. A foe's temperament is expressed through the GM's description, not through a stat players can query.

Read the Fight and Measure the Distance stay in Showdowns (Established 2026-10-24): they reveal a single choice, not a habit, so they don't conflict with reading by description.

**The GM's descriptive toolkit (Established 2026-10-25).** Reading a foe should be a skill that rewards attention, without ever giving players full sight of the foe's choice, which breaks the wheel. Gambits as path signatures were settled on 2026-10-25 (below).

- **What the GM voices.** The bearing at the start of the duel and whenever a player asks; the live tell, once per pass, before the roll; and the aftermath after the reveal, said plainly so players can learn the patterns (Press reads as short, quick, point forward; Guard as closed, weight back, blade between; Commit as a gathered, long stroke).
- **Honesty rules.** (1) A tell describes a tendency, never the choice: describe first, roll after. (2) The same tell gets the same words every time. (3) Never voice a tell for a habit that isn't live, and never invent one for a plain table roll. (4) A foe lies only through its mechanics (its own False Tell or Feint), narrated after the reveal as the switch it is. (5) Never name a stance; describe the body, breath, eyes and footing.
- **By readability.** Open-book foes: tells said bluntly and unprompted. Familiar foes: tells voiced, but subtle. Puzzle foes: tells only when a player asks what they see, so knowledge from before the duel matters most.
- **Shifts and the stance itself.** Describe a shift big, and only once. Read the Fight is the only way to see the stance itself.

#### GM toolkit: reading by description (Draft, promoted 2026-10-24)

Purpose: give players something true to read without a rules mechanic. A foe in a Showdown has a **temperament** (its habits), and the GM shows that temperament through description. Players win by noticing it.

**The four principles**

1. **Describe the inclination, then choose.** Each pass, describe the foe's bearing *before* you pick its stance, and draw the description from its temperament and the state of the duel, never from the stance you've already picked. Otherwise every description is a perfect tell, and the sims show a perfect tell decides the duel (85–95%).
2. **Tells are true tendencies, not promises.** A foe that leans forward Presses more often, not always. Never describe something that contradicts the temperament; the description stays honest even when this pass goes against the pattern.
3. **Habits must be consistent to be learnable.** Keep the same words for the same leanings across the whole duel, so players can match patterns. A habit that changes, changes for a reason the players can see (it got hurt, it got scared, its trick failed).
4. **The payoff is the reveal.** Describe the clash after both stances are shown, and give a landed Gambit its moment in kind: the sword spinning away, the wind-up broken, the wall shattered.

**Vocabulary of leaning** (use these, or the table's own, consistently):

- *Leaning to Press:* weight forward, the point never still, closing a half-step at a time, impatient breath, eyes on your hands.
- *Leaning to Guard:* weight back, blade centered, small careful steps, shield high, eyes on your shoulders, waiting.
- *Leaning to Commit:* settling, a stillness that wasn't there before, the grip shifting, a held breath, eyes fixed on one place on your body.

**Three kinds of habit** (richer than raw frequency; only frequency habits have been simulated so far):

- *Frequency:* what it does most (the Hound Presses).
- *Sequence:* what it does after what it just did (after Guarding, it always Presses).
- *Reaction:* what it does after what happened to it (after taking a hit, it Commits).

**Temperaments**

Each has a bearing (how it looks at the start), its habits, and how it shifts. The optional d6 is a GM aid for staying consistent and honest, not a player mechanic; roll it after describing.

- **The Hound** (aggressive). *Bearing:* already moving when the duel begins; never gives ground. *Habits:* Presses most passes; after taking a hit, Presses harder. *Shift:* once its Guard is worn, it Commits more. *d6:* 1–4 Press, 5 Commit, 6 Guard. Sims: the most readable temperament (a reader wins 58–63%; Disarm is the Gambit to wait for).
- **The Wall** (cautious). *Bearing:* settles in and lets you come. *Habits:* Guards often; after Guarding twice, it Presses. *Shift:* after landing a hit, it Commits next pass. *d6:* 1–2 Press, 3–5 Guard, 6 Commit. Sims: less readable (53–56%); Headlong is the Gambit for it.
- **The Gambler** (reckless). *Bearing:* restless, grinning, too eager for one big blow. *Habits:* Commits far more than it should; after a Commit is broken, it Presses. *Shift:* the more it's losing, the more it Commits. *d6:* 1–3 Press, 4–5 Commit, 6 Guard. Stop-Thrust is the Gambit for it.
- **The Old Soldier** (balanced). *Bearing:* economical, unhurried, gives nothing away. *Habits:* close to the balanced mix; few tells, and its description says so. *Shift:* none to speak of. *d6:* 1–3 Press, 4 Guard, 5–6 Commit. Use for masters and cunning foes; reading it gains little (about 52%).
- **The Cornered** (changing). *Bearing:* careful, measuring the exits. *Habits:* plays as the Wall while its Guard holds, then as the Gambler once worn. *Shift:* the change is the tell; describe it when it happens. Tests whether players notice a habit changing.
- **The Showman** (likes its tricks). *Bearing:* flourishes, plays to the crowd. *Habits:* repeats whatever worked last pass; if a stance won, it uses it again. *Shift:* if humiliated (a Gambit lands on it), it turns Hound. A sequence habit players can punish once they see it.

Open: simulate sequence and reaction habits (only frequency habits are tested); whether foes get Gambits of their own, and how a GM describes a foe preparing one. How many temperaments the core book needs was settled on 2026-10-25 (below).

**Temperament and foe-Gambit sim (Proposed findings, 2026-10-24).** Duelist builds to the death, 2,000–2,500 duels per result. Each temperament was built as written above, including its sequence and reaction habits. Players held all three Gambits and used one only when its target looked at least 60% likely. Three kinds of player were tested: one mixing stances evenly (no reading), one learning the foe's habits from scratch during the duel, and one who has the foe figured out (the ceiling of what a good description can convey).

| Temperament | Even mix | Learning in the duel | Foe figured out | Player Gambits when figured out |
| --- | --- | --- | --- | --- |
| Hound | 49% | 55–56% | 71% | 1.1 a duel, 81% right |
| Wall | 55% | 56–58% | 76% | 1.2, 90% |
| Gambler | 51% | 51–53% | 67% | 0.7, 84% |
| Old Soldier | 52% | 52–53% | 56% | 0.3, 50% |
| Cornered | 53% | 52–53% | 72% | 1.0, 91% |
| Showman | 52% | 56–57% | 77% | 1.2, 90% |

- **All habit types are readable and worth reading.** Once figured out, the readable temperaments give 67–77% and Gambits called on them land 81–91%. Sequence and reaction habits (Wall, Cornered, Showman) are as readable as raw frequency (Hound) or more. The Old Soldier works as the master: 56% even when known.
- **Learning cold inside one duel captures little** (0 to +8 points). About 8 passes is too few to spot a pattern statistically, and a learner that tracks sequences and reactions did no better than one tracking frequency. So the GM's description must carry the habit: description is worth up to about 20 points, which supports the creator's decision that reading happens through description.
- **Foe Gambits** (aimed at the player's most common recent stance, about 1 pass in 6; the Showman more often; the Old Soldier only when the player's habit is clear) come to 0.4–1.1 a duel.
  - Against a player mixing evenly they land about 40% (below break-even), leaving that player at 50–55%.
  - Against a player who reads by frequency they land about 40% and erase the reading edge (53–58% down to 50–51%): a player who falls into a habit gets punished.
  - Against a player who has the foe figured out they land only 8–11%, and that player still wins 55–75%.
  - Reading becomes two-way: the GM reads the players too.
- **Length** is unchanged (7.3–8.3 passes).

GM implications (Draft, promoted 2026-10-24): state a foe's habit in its bearing early and repeat it in the same words, since players can't be expected to find it statistically; aim foe Gambits at a player's visible habit, and use "a trick only works once" for foes as well; reputations and rumors ("they say he always gives ground twice, then lunges") are a natural way to let players arrive knowing a habit.

**Foe Gambits (Draft, promoted 2026-10-24).** Foes may use Gambits. The GM aims a foe's Gambit at a player's visible habit, chooses it in secret like any stance (describe first, then choose), and the same costs apply: a wrong guess gives the player a free plain attack, and a Gambit that pays off is spent for that Showdown. How often each temperament gambles is in the Gambit rate table below.

**Gambit rate by temperament (Draft, promoted 2026-10-24).** Each temperament gets a Gambit habit: what makes it gamble, and how often when that happens (a d6 chance, so the GM aid stays a d6). Sim: rates 0 to 3 in 4 for each temperament, 1,500 duels per cell (the table uses the tested rates nearest each d6 chance: 0.5, 0.3 and 0.15), against three players: one mixing stances evenly, one prone to habits (reads by frequency), and one who has the foe figured out.

| Temperament | Gambit habit | Rate when triggered | Foe Gambits per duel | Player win: even / habit-prone / figured out (no foe Gambits) |
| --- | --- | --- | --- | --- |
| Hound | Reaction: you repeated a stance twice running, it Gambits against it | 1 in 2 (4–6) | 0.8 | 52 / 48 / 71% (49 / 56 / 70%) |
| Wall | Aimed at your most common recent stance, any pass | 1 in 3 (5–6) | 1.3 | 53 / 50 / 77% (51 / 55 / 74%) |
| Gambler | Random Gambit, any pass | 1 in 6 (6) | 0.8 | 56 / 56 / 68% (49 / 52 / 64%) |
| Old Soldier | Careful: only when 3 of your last 4 passes were the same stance | 1 in 3 (5–6) | 0.5 | 53 / 48 / 58% (51 / 51 / 54%) |
| Cornered | Desperate: aimed, only once its own Guard is worn | 1 in 2 (4–6) | 1.1 | 52 / 45 / 77% (49 / 51 / 75%) |
| Showman | Aimed at your most common recent stance, any pass | 1 in 3 (5–6) | 1.3 | 54 / 51 / 77% (52 / 55 / 76%) |

Findings:

- **Foe Gambits never help a foe against a player mixing evenly** (player 50–56% at every rate tested); they only punish players who fall into habits (down to 42–50%). That is the intended job.
- **Gambling is itself a habit.** Against a player who has the foe figured out, foe Gambits land only 11–17%, and frequent gambling makes the foe easier to read (the Wall at 3 in 4: 74% to 84%).
- **Aimed, careful and reaction Gambits land 50–63%** against habit-prone players. **Random Gambits land 30–35%** against everyone, so the Gambler loses by gambling; above 1 in 6 it hands duels away (61–75% at 1 in 3 or more).
- **The useful band is about 0.5–1.3 foe Gambits a duel.** Below it, habits go unpunished; above it, the foe gives itself away.
- Description: by the describe-first principle, a foe's interest in a player's habit is described before its choice ("his eyes keep going back to your sword hand").

The Gambler stays a losing gambler by design (Draft): its random Gambits are its flaw, and players who read it profit.

**Known Gambits (Proposed, 2026-10-24).** Each temperament knows only some Gambits, which gives it flavour and lets players who learn a foe know which stances are safe against it. Sim: same rates as above, 1,500 duels per cell; player win against even / habit-prone / figured-out players (foe Gambits per duel, % right).

| Temperament | Known Gambits | With its known Gambits | With all three |
| --- | --- | --- | --- |
| Hound | Headlong, Disarm | 52 / 47 / 70% (0.6, 43–57%) | 53 / 47 / 74% |
| Wall | Disarm, Stop-Thrust | 53 / 52 / 74% (1.1, 45–55%) | 55 / 50 / 77% |
| Gambler | all three, at random | 57 / 57 / 64% | — |
| Old Soldier | all three | 52 / 49 / 59% (0.5, 39–58%) | — |
| Cornered | all three (desperation takes anything) | 53 / 47 / 76% (1.2, 41–54%) | — |
| Showman | Disarm, Headlong | 51 / 50 / 74% (0.9, 43–46%) | 54 / 53 / 75% |
| The Sharp | all three | see below | — |

- **Two known Gambits keep nearly all the punishing power** and make the foe slightly harder to exploit once known (Hound 74% → 70%).
- **One Gambit is too thin for most temperaments:** the Hound with only Headlong gambles 0.1 times a duel and stops punishing habits (53%); the Cornered with only Stop-Thrust likewise (55%). Disarm alone works for the Wall and Showman (0.6–0.8 a duel, nearly the same results), so a one-Gambit foe is possible but a weaker opponent.
- **The Cornered is better with all three:** limited to two, it gambles a third as often and punishes habits less (54% vs 47%).

**The Sharp: a winning gambler (Proposed, 2026-10-24).** *Bearing:* loose and smiling, watching your feet instead of your blade, always a breath ahead. *Habit:* leans to Press and Commit (d6: 1–3 Press, 4–5 Commit, 6 Guard), and gambles against **the stance you just used**, 1 in 3 (5–6) on any pass. *Luck:* a monster trait (Established 2026-10-24, available only to the Sharp for now): twice per Showdown, a wrong Gambit doesn't leave it open (the blade that should have found it slides past; describe it as fortune, not providence). Sim, player win against even / habit-prone / figured-out players:

- Sharp without luck, 1 in 3: 54 / 45 / 67% (1.4 Gambits a duel, 55% right against habit-prone players).
- Sharp without luck, 1 in 2: 56 / 43 / 74% (gambling more makes it easier to read).
- **Lucky Sharp, 1 in 3: 49 / 42 / 62%**: the only foe tested that holds even against a player mixing well, crushes careless players, and stays the hardest readable foe once known.
- Luck alone doesn't make a gambler win: a random Gambler with 2 or more misses forgiven still loses (53–58%). What wins is aim (reading the player's last move) plus luck to survive the misses.

Resolved 2026-10-24: foes may carry unique Gambits, and the Sharp's luck is a monster trait only the Sharp has for now. The remaining open items are at the end of this section.

#### Unique Gambits (direction Established 2026-10-24; the six examples Proposed)

Foes get Gambits that belong to them alone: a school's secret, a lineage's habit, one duelist's trademark. A unique Gambit follows the rules of any Gambit (chosen in secret in place of a stance, answered by a free attack when you guess wrong, spent once it pays off), but it usually punishes a sequence (one stance following another) rather than a single stance, and it can be learned.

**Learning (Established 2026-10-24).** Unique Gambits are designed so that a player can learn one by facing enough foes who use it. There is no counter and no sheet bookkeeping: the GM decides if and when a player is ready, and the moment of learning is a narrative one (an old duelist's lesson, a rival's confession, a scar that finally makes sense). Once learned, it is used exactly like a common Gambit.

**GM guidance (Proposed).** About three sightings is a natural threshold, fewer when one is dramatic. A sighting can be the Gambit used against the player, against an ally or a rival, or only described in the fiction. Left unstaged, a foe shows its unique Gambit roughly once in every 3 to 15 duels (the Wall's almost never; see the sim), so a GM who wants it learned should stage it: use it deliberately at the foe's best moments, or let rumor and other duels show it.

**Designing a unique Gambit (Proposed checklist).** (1) It punishes something the players can see coming, a stance or a stance following another, never a hidden roll. (2) Its trigger is rarer than a single stance, so its payoff is larger (the Gambit sim's scaling rule: the rarer the trigger, the bigger the swing). (3) Its effect is visible when it lands and when it fails, so players can learn what it does by watching. (4) A wrong guess costs the standard free attack, which a gambling style may raise. (5) It is tied to a habit the GM can describe, so the description carries the tell. (6) It stays niche: worth +6 to +8 against the foe it came from and little elsewhere, a reward for specializing and not a spike in power.

| Unique Gambit | Foe | Trigger | Effect when right | Value to a player who has the foe figured out (win rate points) |
| --- | --- | --- | --- | --- |
| Give Ground | Hound | Foe Presses, and Pressed last pass too | The rush finds only air: the attack is cancelled, the foe is Exposed, and you strike at +2 | +8 against the Hound, +6 against the Showman, about 0 elsewhere (1.0 uses a duel against the Hound, 82% right) |
| Turn the Blade | Wall | Foe Presses after Guarding last pass | Attack cancelled, foe Exposed, and you strike at +4 straight to HP | +1 to +3 (0.2 to 0.4 uses a duel; the rarest trigger) |
| Through the Press | Gambler | Foe Presses | Attack cancelled and you strike at +4 straight to HP. Wrong: the foe's free attack is at +4 | +6 against the Hound, +4 against the Gambler and the Cornered, +2 against the Showman, −4 against the Old Soldier (a high-variance Gambit) |
| Seen It Before | Old Soldier | Foe plays the same basic stance as last pass | Their stance fails (a Press is cancelled, a Commit broken, a Guard loses its bonuses) and you strike at +2 | +4 to +6 against the Hound, Wall, Cornered and Showman, 0 against the Old Soldier. The broadest of the six; keep it rare |
| Last Measure | Cornered | Foe Presses; usable only at Guard 2 or less | Attack cancelled, you recover 3 Guard, and you strike at +2 | +5 to +7 against the Hound, Gambler and Showman, +3 against the Old Soldier, 0 against the Wall and Cornered |
| Cut the Flourish | Showman | Foe Commits after Pressing last pass | You strike into the wind-up at +4 straight to HP, and if it lands their strike is broken | +7 against the Wall, +3 against the Cornered, about 0 elsewhere |

**Design notes from the sim (Proposed findings, 2026-10-24).** Seen It Before first targeted any Gambit and never worked: foes' Gambits are too unpredictable for the trigger to ever look likely, so it became a repeated stance. Last Measure first triggered on any attack and added 4 to 8 points against every foe; limiting it to a Press and letting the strike back in tuned it to a desperation tool. Turn the Blade needed Exposed and +4 to be worth its rare trigger.

**Sim, held by foes (1,200 to 1,500 duels per cell).** Used when the GM's read of the player fits, a foe's unique Gambit appears 0 to 0.33 times a duel and moves the player's win rate by −4 to +3 points, so it is flavor and not threat. Staged (used whenever the trigger could occur), five of the six appear 0.2 to 0.85 times a duel (Turn the Blade stays at 0.03 to 0.2), and results stay within about 4 points either way, with three exceptions: Through the Press costs a player who has read the Gambler 9 points (66% → 57%) through sheer variance, and the Old Soldier's and the Cornered's misfires hand the player 7 points (52% → 59%, 72% → 79%).

**Stakes change who wins (Proposed finding, 2026-10-24).** Duelist-stat builds on the base stance wheel (no Gambits), 3,000 duels per cell; win rate of the first-named build, mean passes.

| Matchup | To the death | To first blood | To the yield (Guard 0) |
| --- | --- | --- | --- |
| Duelist mirror | 51%, 8.5 passes | 49%, 3.8 | 50%, 4.3 |
| Defender v Duelist | 80%, 9.5 | 68%, 4.3 | 81%, 5.3 |
| Bruiser v Duelist | 71%, 7.1 | 56%, 3.6 | 77%, 3.0 |
| Dagger v Duelist | 20%, 8.3 | 52%, 2.8 | 20%, 4.3 |

Stakes are a dial. First blood levels the builds (the dagger is even), while the yield and the death reward weight and armor. Proposed definition of the yield: a duelist whose Guard is 0 at the end of a pass has yielded, and if both are at 0 the one with more HP wins.

**Open items settled (Established 2026-10-25; proposed 2026-10-24).** When a foe's unique Gambit and a common Gambit both fit, it uses the unique one, its signature moment. Headlong's size stays as tested (+9 worn to +15 at full Guard): it is rarely right between even duelists by design. Read the Fight costs 1 Focus per use, at most 2 per Showdown (about +4 per use; the cap keeps a full pool from deciding a duel), subject to the Focus pool numbers. Bind costs 2 Guard (+4). Misericorde works at Guard 2 or less. A duelist starts with 2 Techniques and holds 3 at mastery. Two Measures on the same pass cancel. Feint (Tempo) and False Tell both stay: Feint is the Tempo Expression and switches only between Press and Commit, costing a 2-Tempo Flourish once per pass; False Tell is the Sword-path Technique and may switch to any stance. There is no Rally and no item use in a Showdown, so Guard stance's +1 regain is the only recovery (the sims gave each duelist one free bandage; without it Bleeding is more dangerous). Which Technique each fighting style grants moves to the Ability Catalog. Nameless troops do not duel; only a foe with a temperament does, named or given one by the GM.

**Settled by the creator (Established 2026-10-24).** The questions that were open here are answered and recorded in the Showdown rules list above: completed Showdowns persist, an interruption reverses everything, a third party entering is an interruption, a duelist may always decline, the three common Gambits are open to all, and learned unique Gambits are not capped. The settlements in the paragraph above were approved by the creator on 2026-10-25 and are Established.

**Open items settled (Established 2026-10-25).** Sims are in the Project's `sims/showdown_open.py` and `showdown_open2.py`. The fall, allies and who duels are in the Showdown rules list above; the rumor table is under Rumors below.

- **Misericorde's Ebb severity:** a foe felled by Misericorde is Grievous (an Injury at +30 when stabilized), or Mortal if the strike was also an Overwhelming critical. When both duelists hold it, Misericorde ends about 0.46 duels to the death in 1.
- **Techniques for foes:** a threat dial, at most one per named foe. Measure or Bind for veterans (about −3 to −5 points for the player), Misericorde for killers (−4 to −6), False Tell for masters (−8 to −10, and reading doesn't beat it). Two only for a campaign nemesis (−13 to −15).
- **The dagger's gap:** with a short blade, Misericorde works against a foe at Guard 4 or less (value Draft, pending playtest). First blood stays the dagger's natural stakes. Sim, dagger v Duelist to the death: bare 41%, with the short-blade Misericorde 45%, adding Measure 54%. This engine's dagger baseline differs from the earlier engine's (41% against 20%).
- **Gambits as path signatures:** once per Showdown, a wrong guess with your path's signature Gambit doesn't leave you open. Dagger: Stop-Thrust; heavy blade: Headlong; long blade: Disarm (Established 2026-10-25; about +2 points, more for a player who gambles loosely). Worth about +1 to +4 points; making the Gambit itself stronger was worth 0 to +3.
- **Core temperaments:** Hound, Wall, Gambler and Old Soldier in the core book; Cornered and Showman as advanced temperaments; the Sharp as a villain template.
- **Rumors:** the softer truth table. With the old table, a "half true" rumor was a trap (24–31% when trusted) and rolled rumors did worse than learning during the duel; the softer table beats learning alone by 2–4 points.
- **Technique and Expression strength:** settled as tested, with no changes. In the 2026-10-25 sims (learning and figured-out players against the Hound and the Old Soldier, plus the even mirror), each Technique is worth about +2 to +7 points in most matchups. False Tell is the strongest (+4 to +10) and sits in every top hand; Bind is the weakest (+0 to +4), buying certainty for its 2 Guard; Misericorde adds nothing to a player already winning, as a finisher should. A starting hand of 2 gives 56–65% against a foe with no Technique and 46–53% against a master holding False Tell; a mastery hand of 3 gives 61–69% and 52–58%. Read is about +4 per use and Feint +1 to +7. Overbear stays as written (+0 to +2); stopping the riposte made it +8 to +9, a whole Technique's worth for a pool spend.
- **Unbroken in a Showdown:** a hit doesn't knock your Commit off line or break it, even when the hit reaches HP. About +5 at one use and +6 at two (as written it was +0 to +2).
- **Showdown values:** Showdowns use whatever Guard and HP everyday combat settles on, with no separate Showdown values. Swapping the Exchange values for the three-action ones moved Technique values by 3 points or less and stakes results by 4 or less. Rerun the Showdown sims when everyday combat is decided.

**Rulebook (creator decision, 2026-10-24).** No separate GM's-guide write-up of the Showdown rules is needed now. Every system will be revised into rulebook format later, when the time comes.

#### NPC habit toolkit (Proposed, 2026-10-24)

A foe's behavior in a Showdown is a habit card: a base table, up to three habits, a Gambit habit, an optional unique Gambit, a shift and a bearing. All of it is rules except the bearing, which is what the players read. The six temperaments above are habit cards already built; this is how to build others.

**Building a card.** (1) Base table: a d6 split among Press, Guard and Commit, whose skew is the foe's resting temperament. Aggressive is Press 4, Guard 1, Commit 1 (the Hound); Balanced is Press 3, Guard 1, Commit 2 (the Old Soldier, Gambler, Showman and Sharp); Cautious is Press 2, Guard 3, Commit 1 (the Wall, and the Cornered while its Guard holds). Heavy is Press 2, Guard 1, Commit 3 (no named card yet). (2) Habits, none to three: each is a trigger, a response and a strength. Roll a d6 for the strength (always applies on any roll, usually on 1 to 5, often on 1 to 4); if it applies, play the response, otherwise roll again on the base table. If several triggers hold, use the first habit on the card. (3) Gambit habit: pick a style (aimed, careful, reaction, desperate, repeat or random), a chance in sixths, the Gambits the foe knows, and a unique Gambit if it has one. The rate table above gives working values; aim for 0.5 to 1.3 foe Gambits a duel. (4) Shift: one trigger that changes the card for the rest of the duel (the Cornered turns Gambler once worn; the Showman turns Hound when a Gambit lands on it). Describe it the moment it happens; it is the best tell there is. (5) Bearing and tells: one sentence of bearing, plus one tell per habit, in the same words every time. (6) Danger: the card sets only what the foe chooses. What its hits do comes from its ordinary stat block (weapon, Guard, HP, conditions on hit), so a fragile foe with a vicious weapon is built there, not here.

| Trigger | Kind | A tell the GM can voice |
| --- | --- | --- |
| It took a hit last pass | Reaction | A rolled shoulder, a spit, a faster step in |
| It landed a hit last pass | Reaction | A half-smile and a shifting grip: it wants that again, bigger |
| Its strike was broken last pass | Reaction | A hard look at its own blade, jaw set |
| It won the pass | Reaction | Stands a little taller, settles into what worked |
| It used the same stance twice running | Sequence | The same motion again, and a held breath before the third |
| You Guarded, Pressed or Committed last pass | Reaction to you | Its eyes drift to where your weight was |
| Its Guard is worn (two-thirds of its starting Guard or less, rounded down; 4 at the standard 6) | State | Ragged footwork, audible breath |
| It is behind | State | A glance at the crowd, the door, the ground behind you |
| You are worn (two-thirds of your starting Guard or less, rounded down) | State | Its eyes drop to your lead foot, your grip, the breath you can't hide |
| It is the first pass of the duel | State | It sets its feet before you've finished drawing; the first move is already decided |

A response is a stance, or a repeat of its last stance. The engine supports all ten triggers; the readability sims below used three (took a hit, you Guarded, landed a hit). You are worn and It is the first pass of the duel were tested on 2026-10-25 (Established). A first-pass habit adds no ceiling and can't be learned during a duel, since it fires once, so it works as knowledge carried in (a rumor, a reputation, a rematch). A you-are-worn habit raises the ceiling about as much as a second habit. Sample foes, figured out / learning / even mix: a one-habit comparison 74/59/42, a first-pass Commit (always) 74/54/42, a you-are-worn Commit (usually) 78/62/50. Even mixing dipped to 42% against these Press-leaning cards, below the 44–49% recorded against the temperaments, but is still not trapped.

**Readability dial (Proposed findings, 2026-10-24).** Duelist builds, no foe Gambits, 1,000 duels per cell; win rate of the player. A figured-out player knows the card exactly; a learning player tracks stances and sequences from scratch during the duel. Differences under about 3 points are noise.

| Dial | Build | Figured-out player | Learning during the duel | Even-mixing player |
| --- | --- | --- | --- | --- |
| Guarded | Balanced table, no habit, or one that applies only often | 55 to 66% | 49 to 51% | 51 to 54% |
| Open book | Aggressive or Cautious table plus one habit that always applies | 74 to 75% | 58 to 62% | 50 to 52% |
| Familiar | Any table plus one or two habits that usually apply | 71 to 77% | 52 to 60% | 47 to 54% |
| Puzzle | Any table plus three habits, usually or always | 78 to 84% | 49 to 54% | 49 to 53% |

The first habit does most of the work: a table alone leaves a figured-out player at 55 to 66%, and one habit lifts that to 66 to 75%. A second adds a few points and can still be learned during a duel. A third raises the ceiling again, but a player learning during the duel falls back to the table's level, so a three-habit foe needs prior knowledge (a rumor, an earlier duel, a reputation). Strength matters as much as number: always adds about 4 to 7 points of ceiling over often. Even-mixing players are unaffected throughout, so habits never trap sound play. Duel length stays between 7.5 and 9 passes. The learning player in the sim has only its own pattern counting, and description is worth far more to a real player, so treat the learning column as a floor.

**Running a pass.** Update the tracker: the foe's last two stances, who lost Guard or HP last pass, and whether it is worn. Check the habits in order; the first whose trigger holds is live. Describe the bearing, leaning toward the live habit's stance (or the table's most common stance). Only then roll: the strength die, then the table if needed. Next check the Gambit habit, and if it fires, play the Gambit instead, in secret. The players choose, both sides are revealed, and you narrate and update the tracker. Because the description comes from the habit and the roll comes after it, a tell is a true tendency and never a promise.

**Rumors (Established 2026-10-25; tested).** A rumor states one habit. To decide how true it is, roll a d6: 1 false (a habit the foe lacks), 2 out of date (the foe has since shifted), 3 to 4 trigger only (it names what to watch for, not what the foe does), 5 to 6 true. Open-book foes can simply be told about truthfully; save false and out-of-date rumors for puzzle foes, where prior knowledge is the point.

| Foe | Dial | Table | Habits | Gambits | Bearing and tells |
| --- | --- | --- | --- | --- | --- |
| Old Gorm, a tavern champion | Open book | Aggressive (Press 4, Guard 1, Commit 1) | Took a hit: Press (always) | None | Sways on his feet, grinning, the point never still. Every time you hurt him he spits and comes in harder. |
| Sergeant Hale, a veteran of the Third Era wars | Familiar | Cautious (Press 2, Guard 3, Commit 1) | Took a hit: Press (usually). You Guarded: Press (usually) | Disarm and Stop-Thrust, aimed, 1 in 3 | Feet planted, shield rim at his chin. He rolls his shoulder when you hurt him and grows restless when you hold your guard. |
| Marrow, a ferryman who has killed on the river for twenty years | Puzzle | Cautious (Press 2, Guard 3, Commit 1) | Took a hit: Press. You Guarded: Press. Landed a hit: Commit (all always) | Stop-Thrust, aimed, 1 in 3 | Unhurried, with a boat-hook's reach, never looking at your blade. He breathes through his nose after a hard exchange and steps in, leans in when you hold your guard, and goes still after he lands one. |

The readability sims cover three habit triggers (two more were tested on 2026-10-25); the card itself is the record for recurring named foes.
