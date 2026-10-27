# Dark Fantasy System — Asloria Design Bible

Oct 12, 2026 · @Hunter

## How to read this doc

This consolidates every system decision recovered from the ChatGPT export, with the latest version of each rule winning over earlier drafts.

From 2026-10-24 the project files are six read-only direction files (00 Read First to 05 Playtest and Balance); the earlier ChatGPT-era files are retired. This doc is the editable working copy: this tab holds the creative vision and setting, the game rules live in the topic tabs listed below, and design philosophy, the ability template and the playtest workflow live in Design Toolkit.

**Status labels** used throughout:

- **Established**: you approved it. It is the current rule and less likely to change, but it can be revised as the game develops; a revision still needs your approval and a Decision log row noting what it replaces (meaning clarified 2026-10-26).
- **Draft**: agreed in direction, numbers or wording still open.
- **Proposed**: suggested in the chats, never confirmed by you.
- **Open**: a question raised but not answered.

**Sources recovered**

| Conversation | Dates | What it holds |
| --- | --- | --- |
| Dark Fantasy Race Creation | Apr 2025 | Hollowborn, Hollowborn traditions, early freeform magic tags |
| Dark Fantasy TTRPG Progress | Apr 2025 | Elves, attributes, saves, skills, tools, Dwarves, Dragonborn, Gnomes |
| Dark Fantasy Skill System | May 2025 onward | Paths, 5e ability conversion, crits, archetypes, Attribute Expressions, Clarity, Guard, initiative |

**Not recoverable from the export:** content that lived only in ChatGPT canvases or generated .docx files. That includes the polished Dragonborn lore and Dragonborn character sheet, and the final formatted Skills, Dwarves and Elves Word docs (their text survives in the chat itself). Older 2023 chats (an Eldoria setting, a 1–10 D&D campaign) are unrelated and left out.

**Tabs (reorganized 2026-10-24).** Each topic has its own tab, so a question needs only the tab it is about.

| Tab | What it holds |
| --- | --- |
| Core Rules | Core resolution, attributes, saves, rests, skills and tools, the Attribute Expressions |
| Skill Tests | The d100 skill system in full |
| Races | Races and subraces |
| Paths and Abilities | Progression, the Path tree, archetypes, mage archetypes, finalized abilities, ability triage |
| Ability Catalog | Every Path ability with its data fields |
| Combat | Criticals, Defense, Guard and HP, Injuries and Dying, calibration, initiative, action economy, Showdowns |
| Clarity and Conditions | Clarity, Mental Scars and the condition glossary |
| Open Issues and Next Steps | Inconsistencies, the attribute scale audit and the next-steps checklist |
| Decision log | Every confirmed decision, oldest first |
| Design Toolkit | Working methods and the working prompts |
| Player Feedback Log | Player-facing alternatives for feedback |

## Creative vision and design pillars

Asloria is a gritty, low-power dark fantasy where the gods have abandoned the world, institutions have collapsed, and every advantage carries a price. Touchstones you named: The Witcher, Game of Thrones, Berserk; mechanically D&D 5e, Dungeon Crawl Classics, Pathfinder, Call of Cthulhu, Fallout d20, Shadowrun.

**Tone (Established)**

- Less powerful than 5e at every level; abilities feel grounded, not whimsical or heroic.
- Magic is rare, feared and costly. Mages pay with sanity, a bargain's price, time or certainty.
- Tragedy over triumph: civilizations hide their collapse, the dead do not rest, knowledge survives as scraps.

**Tonal principles (Established 2026-10-24).** Darkness needs contrast: warmth, beauty, humor and real victories matter because they are vulnerable. Horror may be visceral when it reveals character, stakes or consequence, never as empty shock. Magic is mechanically clear but fictionally uncanny. Ordinary life stays grounded. Names are restrained and memorable. Faith survives divine abandonment: religion stays influential though the gods are silent. Maxim: "Do not mistake darkness for depth, cruelty for realism, or obscurity for mystery."

**Design pillars**

1. **Trade negatives for positives.** Races get +1/+1/−1; abilities carry costs, fatigue or exposure. (Established)
2. **Minimize advantage.** You repeatedly replaced 5e advantage with flat bonuses or a d4. Advantage appears only where it should feel lethal, as in Blow for Blow. (Established)
3. **Fantasy first.** Every mechanic answers "what should this feel like?" before "is it balanced?" (Established)
4. **Power costs commitment.** The stronger an action, the more chance opponents get to respond. (Established)
5. **Tiered asymmetry.** Martials share one combat language with small differences; mages play fundamentally different games from martials and from each other. (Established)
6. **Every attribute changes how you play,** not just a number you add. (Established)
7. **Conditions over damage.** Criticals and many abilities create conditions and openings rather than bigger numbers. (Established)
8. **Keep universal tracks minimal.** Guard and HP are universal; everything else is a condition, an archetype-specific cost, or an Attribute Expression. (Draft)
9. **Equipment matters.** Weapon quality decides what a critical does. (Established)
10. **When unsure, err toward underpowered.** Players welcome balance changes that add and resent changes that take away, so a new rule or number that might be too strong starts on the weaker side and is raised after testing. (Established 2026-10-16)

**Design checklist (Proposed):** for each new mechanic, answer Fantasy, Identity, Gameplay Loop, Interactions, and Counterplay.

**Player fantasy (Established 2026-10-24).** Characters become legendary mortals, not invincible superheroes: they achieve extraordinary things while staying vulnerable to injury, ambush, exhaustion and loss. Sword is predominantly martial, Sorcerer supernatural and Wanderer practical; hybrids blend these without erasing them. Significant costs are meaningful and selective, kept for consequential techniques, deep commitments, rituals and bargains, never attached to routine actions. Paths are not personalities or moral alignments.

## Setting: Asloria

The central truth of the setting is that the gods of Asloria have abandoned the Plane, leaving mortals to fend for themselves against forces that would ravage the world. (Established)

**Established world facts**

- The world is called Asloria; the material world is "the Plane."
- History is counted in Eras. The First Era began roughly 3,000 years ago; the present is the Third Era, marked by war and displacement.
- Learned institutions (academies, colleges) are long abandoned, which is why there is no scholar-mage archetype.
- The Veil is a damaged boundary between life and death, dream and waking; Veilwalkers and Clarity both draw on it.
- Dwarves are a fallen civilization hiding their collapse from outsiders (see Races).
- Dragonborn hail from the sovereign nation of Hyrrokkin; many were scattered across the realm in the Third Era.
- Dark Elves live in the subterran, steeped in Pact and Ritual Magic, possibly its progenitors.
- Necromancy leans toward communing with and commanding the dead by ancient laws, not raising armies.

**Proposed lore from the Hollowborn chats (never confirmed by you)**

| Tradition | Region | Faction | Origin event |
| --- | --- | --- | --- |
| Ashen Choir | The Drowned Vale | Circle of Pale Song | Fall of Virelin, a god's temple city that collapsed in one night |
| Bleakwardens | The Blightmarches | Order of the Cold Vigil | The Corpse Wars, when necromancers raised plague-pit armies |
| Quiet Path | Urban underworlds | Whisperflame Society | The Inquisition of Vorthen, which hunted Hollowborn |

Proposed Dwarven lore includes the Stonefather and Forge Mothers (silent gods), the Deep Ones unleashed by Dwarven greed, the Vaults of Shame, and a Code of Silence.
