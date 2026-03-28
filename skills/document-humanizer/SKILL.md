---
name: document-humanizer
description: >
  Transform AI-generated or overly formal documents into natural, human-sounding ones. Use when the user
  wants to make text sound less robotic, more natural, warmer, or more conversational. Triggers include:
  "humanize this", "make this sound less like AI", "my boss says this sounds too generated", "make this
  more natural", "rewrite this to sound like me", "tone this down", "make it less formal/jargon-heavy",
  "make this sound like a real person wrote it". Also use for stakeholder documents, project updates,
  proposals, or internal comms that need to feel warmer and more thoughtful.
---

# Document Humanizer

Transform documents into ones that sound like a real, thoughtful person wrote them — warm, professional, and built around how humans actually think and read.

## Mode Selection

Detect keyword before proceeding:

| Keyword | Mode | Output |
|---|---|---|
| `DETAILED` | Full rewrite | Complete arc, all frameworks, human texture. Brief "What shifted" note after. |
| `CONCISE` | Compressed | Same frameworks, one paragraph max per section. 40–60% of original. No meta-note. |
| *(neither)* | Ask | One question: "DETAILED or CONCISE mode?" |

## The Rewrite Workflow

**Step 1 — Diagnose.** Note: tip-only results, missing buy-in corners, report structure, bullet walls, passive voice, boilerplate, filler jargon.

**Step 2 — Restructure.** Rearrange to follow Human Thought Flow (below). Do this before touching language.

**Step 3 — Rewrite.** Apply frameworks. Kill boilerplate. Add human texture (DETAILED) or compress (CONCISE).

**Step 4 — Buy-in check.** Ensure main ask feels achievable, desirable, and acceptable.

**Step 5 — Output.** Clean version ready to use.

## Human Thought Flow

The critical structural fix. AI follows report logic. Humans follow narrative logic.

```
REPORT LOGIC:       Summary → Findings → Recommendations → Next Steps

HUMAN FLOW:         Why now? → What happened? → How do I know it's good?
                    → What does it mean for me? → What are we thinking?
```

**The arc (adapt to fit):**

```
[OPEN]              — Why does the reader need this now?
[HEADLINE]          — The main thing in one clear sentence
[BELOW SURFACE]     — The thinking and trade-offs behind the headline
[IMPLICATIONS]      — What this means for the reader's world
[TENSIONS]          — What's not sorted yet? What needs watching?
[SUGGESTION]        — What are we thinking? Exploratory, not directive
[CLOSE]             — One brief forward-looking thought (optional)
```

**Never skip: OPEN, IMPLICATIONS, SUGGESTION.** These make it feel human.

## The Results Iceberg

AI shows only the tip. What earns trust is surfacing what's below the waterline.

```
ABOVE:    "We've selected a vendor."

BELOW:    Options compared → cost realistic → not short-term fix
          → knock-on risks checked → accountability clear

READER:   "These people actually thought it through."
```

In DETAILED mode: 2–4 sentences per key outcome. In CONCISE: one clause is enough.

## The Buy-In Triangle

Stakeholders commit only when all three corners are met:

```
              ACHIEVABLE
             (Can we do it?)
                  /\
                 /  \
        DESIRABLE    ACCEPTABLE
     (Do they want it?) (Is it OK for everyone?)
```

AI almost always addresses only **achievable**. Check:
- **Achievable** — Shown as realistic and grounded?
- **Desirable** — Connected to what the *reader* actually cares about?
- **Acceptable** — Acknowledged who might be affected?

## Anti-Boilerplate Rules

Kill on sight — these phrases signal AI and get tuned out:

| Delete | Why |
|---|---|
| "I hope this email finds you well" | Nobody means or reads this |
| "Please find attached..." | Just say "I've attached" or nothing |
| "As per our earlier discussion..." | Reference specifically or skip |
| "Going forward, we will ensure..." | Vague. Say what specifically. |
| "It is important to note that..." | If important, just say it |
| "In conclusion..." / "To summarise..." | Good writing doesn't need labels |
| "Please do not hesitate to reach out" | Signals end of real communication |
| "We are committed to excellence" | Claims without evidence are noise |
| "This document aims to provide..." | Just provide it |
| "It goes without saying..." | Then don't say it |
| "synergy", "leverage", "robust", "holistic", "scalable" | Jargon that stopped thinking |

**The rule:** If a sentence could appear in any document, by any person, about any project — delete it.

**Openings especially:** Never open with pleasantry or context the reader already has. Open with the thing that made you write.

## Quick Substitutions

| Robotic | Human |
|---|---|
| "leverage synergies" | "work better together" |
| "robust solution" | "something that holds up in practice" |
| "it is recommended" | "I'd suggest" / "worth thinking about" |
| "the objective is to" | "what we're trying to do is" |
| "facilitate collaboration" | "get people working together" |
| "deliverables" | "what we're working toward" |
| "action items" | "next steps" / "what needs to happen" |
| "stakeholders" | name them, or "the people this affects" |
| "going forward" | "from here" / "next" |
| "utilize" | "use" |
| "it has been noted that" | "we've noticed" |
| "This approach will ensure" | "This should help make sure" |

## Tone Reference

```
TOO CASUAL:   "Hey team, so basically here's the deal..."
TOO AI:       "The strategic initiative has been assessed and recommendations..."
TARGET:       "Here's where things stand — and a couple of things worth flagging."
```

## Edge Cases

- **Formal documents** (board, legal): Apply iceberg/buy-in selectively. Humanise language without losing formality. Skip contractions if inappropriate.
- **No context provided**: Default to internal mixed-seniority stakeholder update. Flag assumption.
- **Parts already work**: Say so. Don't rewrite for the sake of it.
- **Purely informational** (no ask): Skip buy-in check. Focus on iceberg + human flow.
