# Design Toolkit

This tab is the editable copy of the working methods in the read-only project files (01 Design Philosophy, 04 Names and Ability Writing, 05 Playtest and Balance). Game content lives in the main Design Bible tab; this tab holds how we design, write and test it.

## Design philosophy

- **Trade negatives for positives (Established):** a strong ability carries a cost (fatigue, exposure, resources, injury, social fallout, setup or lost flexibility). The cost should create a decision, not just punish use.
- **Power costs commitment (Established):** big strikes, rituals and sorceries may need a wind-up or an interruption window. Use it where commitment creates counterplay, not dead time.
- **Meaningful, legible consequences:** players should see what is at stake before they act.
- **Asymmetry over symmetry:** martial and magic need not share mechanics. Judge balance by choices, risk, spotlight, reliability and outcomes.

**Cautions**

- No power creep or large automatic jumps in survivability or damage.
- Advantage/disadvantage is not the answer to every uncertainty.
- No criticals that are only double damage, double dice or an extra weapon die.
- Martial features stay grounded unless explicitly supernatural.
- No near-identical resources without a clear difference in purpose.

## Questions for every new rule

1. What experience should this create at the table?
2. What choice does the player make?
3. What is the cost or tradeoff?
4. What can opponents or the environment do in response?
5. Does it overlap an existing mechanic?
6. Is it worth its bookkeeping load?
7. Does it work at low and high advancement?
8. Does it fit the abandoned-gods, grim-fantasy premise?
9. What happens at edge cases?
10. Can it be explained briefly and ruled consistently?

## Proposal format

For any substantial mechanic: **Purpose** (the play experience) · **Recommended draft** (one version) · **Why it fits** · **Tradeoffs and edge cases** · **Status** · **Open decision** (only if one remains).

## Ability writing template

Use only the fields that matter, but never omit one that would leave the ability ambiguous.

| Field | What to state |
| --- | --- |
| Name | Grim, weathered, readable; martial names are not magical |
| Prerequisites | Path, other abilities, equipment |
| Action timing | Instant or Committed |
| Trigger | What starts it (reactions especially) |
| Target / range | Who or what, how far |
| Cost | Resource, fatigue, HP, setup or other price |
| Effect | The rules text |
| Duration | How long it lasts |
| Limits / recovery | Uses per rest, caps, stacking |
| Failure / interruption | What happens if it fails or is broken |
| Rules interactions | Guard, HP, crits, conditions, Expressions |
| Design intent | One line for the GM |

**Keep / Tweak / Drop:** Keep only if it fits and its interactions are understood. Tweak to preserve the play purpose while changing name, cost, trigger or limits. Drop if redundant, too strong, too whimsical or tied to 5e assumptions. Abilities that depend on unfinished systems (crits, Guard, conditions, resources) stay provisional.

## Playtest and balance workflow

1. **Write the hypothesis** in one sentence: what the rule should make players do or feel.
2. **Change one variable at a time** so results can be traced.
3. **Test representative cases:** evasive light fighter, armored shield defender, high-pressure melee attacker, ranged fighter, brawler/grappler, fragile but dangerous monster, large durable monster, low- and high-level characters. For magic: a reliable cheap effect, a costly big effect, a failed or interrupted cast, an unlisted creative use.
4. **Record outcomes:** rounds, how often Guard hits 0, HP lost, Injuries, defensive actions chosen, resources spent, whether each turn had a real decision, rules forgotten or disputed, archetypes that dominated or felt useless.
5. **Report:** what was tested, what happened, what matched, what felt bad, the one change to test next, what stays fixed until then.

**Red flags**

- One attribute is mandatory for too many builds, or one option is always correct.
- A resource is never spent, or always spent immediately.
- Defending is strictly worse than attacking.
- Committed actions feel like lost turns rather than bets.
- HP and Injury punish the same event without adding information.
- Crit effects make targets lose turns too often.
- A low-level character is erased by one ordinary event (unless intended), or high-level characters ignore ordinary threats.
- Heavy bookkeeping for little decision value.

## Working prompts

Prompts we use to review the game. Status: Draft. One prompt is in trial; the next is added only after it has been used on a real problem and revised.

### Asloria Balance Reviewer (Draft, first use pending)

Use it by asking for a balance review of a rule, ability, subsystem or archetype. It reads this doc first, then answers in the format below.

```markdown
**Role**
Review the balance of Asloria's mechanics. Judge whether each rule creates the intended experience at the table, not whether everything is mathematically identical. Asymmetry is a goal: archetypes and subsystems should feel different, use different resources, and may use different dice.

**Before reviewing**
- Read the Design Bible and its Decision log. Respect status labels; never treat a Draft or Proposed item as settled.
- State the design hypothesis in one sentence: what should this rule make players do or feel?
- Name the archetypes affected and the systems it touches (Defense, Guard, HP, Injury, conditions, Clarity, Expressions, Committed Actions).

**Dice systems you may use or recommend**
- d20 + modifier (core): flat 5% steps, high swing; modifiers matter most at the edges.
- d100 / percentile (roll-under or tables): 1% steps; good for corruption and sanity tracks, wild-magic or miscast tables, injury and Grave Wound tables, rare world events.
- Bell curves (2d6, 3d6): predictable results, rare extremes; good where reliability is the fantasy.
- Dice pools (roll Xd6, count successes): more dice means more competence; good for effort, rituals, sustained work.
- Step dice (d4 to d12): a trait grows by changing die size; good for scaling resources and companions.
- Roll-under (d20 or d100 under a score): good for resistance tracks like Clarity.
- Exploding dice: rare, dramatic spikes; good for wild magic and Instability.
- Bonus dice (+1d4) and keep-highest/lowest: use sparingly; the creator dislikes advantage as a default fix.
- Countdown or usage dice (roll each use; a low result shrinks the die): good for supplies, sustained spells, failing light.

**When recommending a dice system**
- Match it to the subsystem's fantasy (reliable vs. swingy, growing vs. draining, chosen vs. fated).
- Limit how many distinct dice mechanics one player must track; asymmetry should live between archetypes, not pile onto one character.
- State exactly where its output feeds the shared d20 frame: a DC, a modifier, Guard damage, a condition, or a Clarity change.

**How to compare across dice systems**
- Convert every option to the same measures: chance of success, expected value, variance, and how often the extremes occur.
- Show the numbers at roughly levels 1, 10 and 20.
- When code execution is available, compute exact probabilities or simulate rather than estimating, and show the table.
- Compare archetypes by reliability, risk, cost, spotlight, control and recovery burden, not damage per round alone.

**Output**
1. Hypothesis: what the rule should do.
2. The math: odds, expected values and swing, as a short table.
3. Verdict: does it deliver the hypothesis? Is anything always correct, never correct, or dominant?
4. Red flags: a mandatory attribute, a resource always or never spent, defensive play strictly worse than attacking, committed actions that feel like lost turns, high levels immune to ordinary threats, bookkeeping for little decision value.
5. One recommended change and the single next test to run.
6. Status: label every result Proposed unless the creator approves it.

**Asloria guardrails**
- Grounded and low-power: no large automatic scaling of damage or survivability.
- Strength comes with a cost, setup, risk or commitment.
- Criticals produce conditions, not doubled damage or extra dice by default.
- Don't lock numbers that depend on unfinished systems (Guard, conditions, crits); mark them provisional.
```

**Trial notes (fill in after first use):** what it caught, what it missed, what to change.
