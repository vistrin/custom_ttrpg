# Sync Notes — Shared Pending Changes Log

**Purpose:** One running file, shared by every chat in this project. When a chat produces new material that hasn't been folded into the canonical `memory/design-themes.md` yet, it appends an entry here instead of writing its own separate file. Once Nick reconciles an entry into the canonical doc, that entry gets deleted from this file — so at any given moment, this file's contents = "everything that's true but not yet in `design-themes.md`."

**Workflow for any chat reading this:**
1. Before treating `design-themes.md` as complete, check this file for pending entries too — they're just as canonical, just not merged yet.
2. When you (the chat) produce new locked/settled material, append a new entry below using the format underneath. Don't rewrite or remove other chats' entries — that's Nick's call once reconciled.
3. Flag conflicts explicitly if new material contradicts something already in `design-themes.md` or an existing entry here — don't silently overwrite.

**Entry format:**
```
## [Chat name/topic] — [date]
- Bullet-level summary of new/changed material
- Note which section of design-themes.md it belongs under
- Flag explicitly if it conflicts with anything already locked
```

---

## Worldbuilding chat — 2026-08-24

Status: compared against canonical doc, **no conflicts found**. All entries below are additive.

- **Design Process — Meta-Principles** (new top-level section, belongs after Tone & Philosophy)
  - "Designing by your own rules, not just playing by them" — my-osmology reframed as refusing borrowed metaphysics generally, not just hiding cosmology from players
    - "Story defines function" as an explicit method + the mechanics-before-setting ordering observation
      - Origin story: the "why is resurrection always divine?" question that kicked off Will/Way (wizard = power sought, cleric = power given)

      - **"Evil is real" × my-osmology unification** (belongs in Tone & Philosophy, near the evil/demons entries)
        - Directional inertia (discord/resentment create real inertia — same mechanism as "desecrated ground") proposed as the physical referent underneath the felt wrongness in the consent-based evil definition. GM-only, never confirmed in-fiction, consistent with existing my-osmology rules.

        - **Recognition-and-choice resolves the species/ancestry open question** (belongs in Species/Ancestry, replaces the "open question" note there)
          - Replaces "ancient grudges" as the source of inter-people conflict: birth into a culture isn't consent to its ideology; complicity begins at the moment of recognized-and-chosen continuation — same logic as "the Devil didn't make you do it, you let him," scaled up.
            - Reframes the "society of evil" trope (Drow, Githyanki, Cardassians, real-world analogues) as individuals who had universal recognition available and chose the system over it — not evil species/nations.

            - **Grown vs. constructed magic artifacts** (belongs in Magic — Cosmology & Feel, near "Wizards are engineers")
              - A "+1 sword" is engineered (Command-side, built to spec, works in anyone's hands). A *grown* artifact accumulates power through consistent Way-flavored use over time; ornamentation is a symptom of that history, not a design choice. Reframes attunement as *discovery* of what an item already became, not a permission gate.

              **Flag for the Mechanics chat:** the canonical doc's "Mechanics — System Feel" section (Genesys dual-axis draw, accessibility-with-depth goal, design-validation-by-analogy) reads as system-level content this worldbuilding session didn't generate. Worth checking whether it's duplicated in a mechanics-side file — if so, consider cutting it from the worldbuilding doc so the two copies don't drift apart.

              ---
## Worldbuilding chat — 2026-08-24 (session 2)

Status: compared against canonical doc + other pending entry in this file, **no conflicts, but overlapping target noted below**.

- **Overlap flag:** the other same-day "Worldbuilding chat" entry above also proposes a replacement for the Species/Ancestry "ancient grudges" open question (recognition-and-choice, individual moral agency). This entry proposes a *different* angle for the same slot — biological/ecological cost-structure rather than moral agency. They don't contradict each other (one's about societal "evil nation" tropes, this one's about biological difference between peoples) but both target the same doc section. Nick will need to decide if both stay, get merged, or get scoped to different subsections.

- **Species/Ancestry — biological difference without hierarchy** (belongs in Species/Ancestry, alongside/replacing part of the open question)
  - Core principle: mechanical/biological advantages must cost something in a *different currency* than the benefit, not an equal-and-opposite stat penalty — same "cost/benefit, not cosmic balance" logic already locked for magic, applied to biology.
  - Longevity (elves) reframed as a narrative cost, not just a mechanical one: centuries of outliving short-lived friends/partners is a real, specific emotional cost ("grief math"), producing genuine cultural variation in how elves relate to attachment — not a uniform trait.
  - Toughness/resilience (dwarves) and similar traits should stay *culturally contested/folk-believed* in-world rather than authorially confirmed fact — consistent with the existing lore/legend and no-confirmed-cosmology framework, just applied to biology instead of magic.
  - r/K selection proposed as the underlying ecological logic for population balance between peoples: humans read as faster-breeding/shorter-lived (r-leaning), elves as long-lived/low-fertility (K-strategist), dwarves plausibly in between or K-leaning on a different axis (toughness rather than lifespan). Explains why no single people has demographically overtaken the others without needing cultural/moral reasons — different, not better, survival strategies. Also retroactively explains the existing population estimates (500k human / 250k elf / 250k dwarf) as biology, independent of the Event.

- **Orcs — hyperactive metabolism (new concrete species concept)**
  - Orcs run a constantly elevated caloric need, short gestation, fast maturity (sexual maturity ~10–12 years). This is the mechanism behind small nomadic tribes (no region can sustain large stable orc populations long-term), absence of settled agriculture/writing/specialized crafts (no metabolic/time slack to develop them, not a cultural deficiency), and raiding behavior (a hyperactive-metabolism adolescent orc raiding a village reads as monstrous to victims, and that felt reaction stays valid, without the orc needing to be evil).
  - Explicit guardrail: every orc retains full capacity for art, philosophy, engineering, etc. if the underlying food-scarcity problem is solved — the behavior is a response to conditions, not an identity or inherent nature. A settled/food-secure orc is not "the good kind of orc," just an orc whose circumstances changed.
  - Integration into settled society (e.g., via Throughway-adjacent labor/guild food security) is a plausible, sympathetic path for orcs — but should carry its own real cost (identity/freedom trade-offs, possible in-group friction with nomadic orcs who see it as a concession), not be treated as an implicitly "correct" endpoint.
  - Likely origin point for half-orcs: contact zones, which the setting already has via recent cross-culture contact and the Throughway frontier — no need for a separate justification.

- **Cross-species design principle: plurality within every people, not just humans**
  - Elves argue with elves, dwarves with dwarves, orcs with orcs, dragons with dragons — each people needs internal disagreement/factions, not a monolithic culture, to avoid quietly reintroducing "race = culture = alignment."
  - Workflow fix for the scale problem (fully fleshing out N cultures × M peoples is exponential): define one or two generative axis(es) of internal disagreement per people up front (elves: attachment vs. protective distance from short-lived people; dwarves: toughness as private virtue vs. communal duty; orcs: raiding vs. non-raiding survival strategy, and cost of integration; dragons: whether Event-knowledge should stay buried or come out), then invent actual factions lazily, one at a time, at point of narrative need — same "grow into it" discipline already locked for government/economics.

- **Genesys mechanical note (flagged for Mechanics chat, not resolved here):** Genesys species design already uses starting-characteristic arrays + Wound/Strain thresholds + starting-XP-as-balancing-currency instead of flat D&D-style "+2 stat" bonuses, and pairs every special ability with a real in-package cost (e.g. book's own elf/dwarf examples). This is good alignment with the narrative "cost in a different currency" principle above and needs no new mechanical invention — just confirms the existing chassis already supports it. Open/unresolved: whether mixed-ancestry (half-elf/half-orc-style) characters get a formal subsystem, since Genesys core treats species choice as a single fixed pick.

## Mechanics chat — 2026-08-24

Status: compared against canonical doc and other sync-notes entries, **no conflicts found**. All entries below are additive; several close out or advance existing Open Threads rather than opening new ones.

- **Push tier dice mechanics, corrected** (belongs in Mechanics — System Feel, or a new Magic Mechanics section if one gets split out)
  - "Upgrade difficulty" = convert an existing Difficulty (purple) die to a Challenge (red) die, only adding a new Challenge die if none remain to convert. Corrects earlier drift toward treating upgrade and add as separate/stacking dice.
  - Push tiers finalized: Cautious (no change) → Bold (+1 Challenge) → Reckless (+2 Challenge, upgrade once) → Desperate (+3 Challenge, upgrade twice).

- **Toll vs. Offering, disambiguated** (belongs in Magic — Cosmology & Feel, near Cost/benefit-not-cosmic-balance)
  - "Toll" = the fixed strain/wound price of a push tier, paid by everyone regardless of training.
  - "Offering" = the Way element letting a trained caster change *what currency* pays the toll (narrative cost substituted for strain/wounds) — never reduces the toll's size, only its currency. Keeps "nothing buys the stakes down" intact.

- **Overreach: deficit concept clarified, tables drafted** (advances the existing "Deficit-to-d100 conversion rate" Open Thread — rate itself still TBD)
  - Deficit = gap between toll owed and what the caster can actually pay; triggers Overreach when a caster commits to a toll beyond their capacity. Modifies a d100 roll upward (structurally modeled on FaD's +10-per-Triumph convention on Critical Injury rolls) — exact conversion rate remains open.
  - Draft Backlash table (01–90: Overtaxed / Drained / Shaken / Fractured Focus / Spillover / Break) and Catastrophic table (91–100: Marked / Broken Vessel / Undone) written up in full; Catastrophic explicitly allows permanent results resistant to conventional treatment, consistent with the existing "permanent results resist conventional treatment" rule.

- **Transference, new special Will action** (belongs in Death/Undeath or a Special Actions section; sits alongside the already-referenced Tether)
  - Redirects harm from one person to another, gated on Bonded-tier Company (hard gate, not a difficulty mod) rather than training. Reactive/instantaneous, no concentration. On failure, harm splits between both parties rather than fully transferring ("the universe honors the gesture imperfectly").
  - Tether (already referenced in canonical doc under the revenant/undeath thread) formalized: Form + Cost/Offering, ongoing concentration, doesn't heal/stabilize — holds a target at a threshold and grants a limited window of agency. Overreach redirect rule: results are shared with the tethered target; Catastrophic results risk pulling the caster toward the same threshold.

- **Way element tier tables + shared upgrade grammar** (advances "Full branching unlock trees for all five Way elements" Open Thread — Tools tree built; Place/Form/Company/Cost still need full trees)
  - Rank-gate table confirmed: Will/Way rank 1–2 → Tier 1, 3–4 → Tier 2, 5+ → Tier 3; untrained casters limited to Cost/Offering only.
  - Element relationship-to-intent categories locked: Absent (no effect) / Approximate (counts fully, bends outcome specificity) / Opposed (rare, binary, GM-adjudicated, reserved for genuine contradictions — not a default penalty for imperfect conditions).
  - Shared axis grammar proposed across Place/Tools/Form/Company (Cost/Offering deliberately exempt, stays purely transactional): Potency / Reach / Volume / Guard — explicitly modeled on FaD's Force power trees (Strength/Magnitude/Range/Duration/Control/Mastery), closing the loop on the "validate against FaD" design-by-analogy habit already noted in the canonical doc.
  - Full worked branching example built for Tools ("Warding Charm" progressing through Reach → Volume → Guard). Place and Form axis-by-axis breakdowns discussed narratively but not yet tabled with full tier numbers.

- **Single "Will" skill confirmed** (belongs in Mechanics — System Feel or wherever skill list ends up documented)
  - Deliberately kept to one rolled skill (paired with Willpower) rather than tradition-based skills, to balance the five new Way skills already being added. Explicit tradeoff, not an oversight.

- **Rollable-Way variant — considered and shelved, not adopted** (worth a line in Open Threads if it's kept at all, otherwise safe to omit)
  - Explored as a "for funsies" tangent: what if Way were an independent rolled check instead of a deterministic modifier? Rejected for solo casting because it breaks "Way is never the thing that succeeds or fails," which was doing real work supporting the "mastery narrows odds, never removes risk" principle. Idea flagged as possibly worth reserving specifically for **Group Workings**, where genuine uncertainty (coordination/timing/trust) already exists narratively and isn't currently modeled at all — ties directly into the still-open Group Working Mechanics thread.

- **Artifact produced:** `Will_and_Way_Mechanics_Reference.docx` (v1) — a full print-style reference covering everything above plus the casting pipeline and Overreach tables, generated this session. Not in the repo; exists as a chat deliverable. Flagging in case a mechanics-specific markdown file should eventually mirror it the way design-themes.md mirrors worldbuilding.

---
              *(Next chat: append your entry above this line, using the format above.)*
              
