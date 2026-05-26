# Brand Discovery Engine

## Purpose
Build a complete brand foundation for companies that have a product but no brand — or
a brand that's a logo someone picked from a template and a tagline that describes
what the company does without saying why anyone should care.

This module produces a Brand DNA document the founder can hand to any designer,
copywriter, or agency and get consistent output without a briefing meeting.

---

## The Discovery Order

Do NOT start with aesthetics. The order matters:

1. **Brand Tension** — the magnetic contradiction the brand holds
2. **Category Villain** — what the brand exists to fight
3. **Archetype** — the personality through which the brand fights it
4. **Positioning** — where in the market the brand lives
5. **Messaging** — how the brand says what it believes
6. **Visual Direction** — how the brand looks doing it

Starting with "what should it look like" produces brands with costumes but no body.

---

## Context Intake

If the user hasn't provided full context, ask everything in ONE message:

```
To give you a brand foundation that will actually work, I need to understand
the business first. Fill in as much as you can:

BUSINESS: Company name + one-liner (what do you do, for whom, and what changes
for them?). Category. B2B or B2C or both. Pricing tier. Stage. Geography/market.
Current traction (ARR, users, notable customers).

CUSTOMER: Who writes the check (ICP — title, company size, budget authority).
Who uses it daily (user persona). The 3 things that genuinely keep your best customer
up at night. The 3 reasons your hardest prospects don't buy. How sophisticated is
your audience?

COMPETITION: 2-3 direct competitors (name them). 1-2 brands you genuinely admire —
any industry, any category (what specifically about them?). What visual/verbal clichés
does your category drown in? Where do you see whitespace?

BRAND: What does your current brand look/feel like, honestly? What should people
feel 10 seconds after encountering your brand? Give me 2-3 visual references (brand
names, URLs, or descriptions). What do you explicitly hate — visually, verbally, or
both? In one honest sentence: what's the biggest thing wrong with your brand right now?
```

---

## Step 1: Find the Brand Tension

Reference `frameworks/brand-tension.md` for the full framework.

Ask the three diagnostic questions:
1. **The Industry Lie:** What does your category claim that you know is false?
2. **The Unwilling Trade-off:** What does your category force on customers that you refuse to accept?
3. **The Impossible Combination:** What two things does your audience want that everyone says can't coexist?

Diagnose and present:
> "Your brand holds a specific tension: **[Pole A] / [Pole B]**."
> "This tension means: [1-2 sentences on the creative implication — what this makes
> possible that competing brands can't do]."
> "Brands that hold similar tensions: [1-2 real examples with a brief explanation of
> the parallel and where it diverges]."

---

## Step 2: Name the Category Villain

Reference `frameworks/category-villain.md` for the full framework.

Identify:
- What behavior, attitude, or system does this brand exist to end?
- What villain archetype does this fall into (Gatekeeper / Exploiter / Complicator / Dignitarian / Time Thief)?

Draft the villain statement:
> "[Brand] exists because [villain behavior] has been [doing X to customers] for too long."

This statement should make the founding team feel something. If it feels like a
press release, it's not specific enough.

---

## Step 3: Archetype Diagnosis

Reference `frameworks/archetypes.md` for the full framework.

Map to 1 primary + 1 secondary archetype. Present as:
> "Based on [specific inputs], your brand is a **[Primary]** with a **[Secondary]** streak."
>
> "What this combination means: [2-3 sentences on the specific visual and verbal
> implications of this exact pairing — not the archetypes in isolation, the combination]."
>
> "This puts you in similar territory to [real brand] — except yours is for [their
> specific category/audience], which means [what's different]."

Ask: "Does this feel right, or is there a direction you'd push back on?"

If they push back: "Tell me what feels wrong. Is it the primary archetype, the secondary,
or the combination?" Then recalibrate with specific reasoning for the change.

---

## Step 4: Positioning

Reference `frameworks/positioning.md` for the full frameworks.

**4A. The Onliness Statement:**
Draft the onliness statement. Read it to them. Ask: "If you said this to a smart person
who'd never heard of you, would they immediately understand why you and not a competitor?"

**4B. Against / For / Beyond:**
| Dimension | [Brand] |
|---|---|
| **Against** | [What you're explicitly, provably not] |
| **For** | [Who you serve — by name, not category] |
| **Beyond** | [What you make possible that didn't exist before] |

**4C. Visual Direction Scores:**
Score on all 5 axes. Score 1-2 competitors on the same axes. Show the territory
gap and explain the opportunity.

---

## Step 5: Messaging Foundation

Reference `frameworks/messaging.md` for the full framework.

Build in this order:

**Category claim** (one phrase)

**Brand promise** (one sentence — must pass the falsifiability test)

**Proof points** (3 — each in [fact] → [customer meaning] format)

**Taglines** (5 options minimum — one per strategic angle):
1. Outcome-first
2. Enemy-first
3. Identity-first
4. Category-first
5. Provocation

For each: strategic angle, best context, confidence rating.

**Voice** (4 dimensions, scored):
Formal ↔ Casual / Reserved ↔ Enthusiastic / Serious ↔ Humorous / Technical ↔ Accessible

**Voice rules** (5 specific rules — things the brand always does and never does):
Format: "Always [specific behavior]" and "Never [specific behavior]"

---

## Step 6: Visual Direction

Reference `modules/visual-direction.md` for the full process.

Produce:
- 5-axis visual scale scores (with competitor comparison)
- Color system (hex codes, roles, emotional function for each color)
- Typography direction (specific font names or categories, type scale)
- Imagery rules (style, treatment, subject matter, explicit avoidances)
- Layout principles
- 3 reference brands with steal/skip guidance
- 3 AI image prompts ready to paste into Midjourney or Flux

---

## Step 7: Brand DNA Document

Compile everything into the Brand DNA template (`templates/brand-dna.md`).

Every field filled. No placeholders. No "[TBD]." Where the user hasn't provided
information and it genuinely can't be inferred, make an opinionated recommendation
and flag it clearly as an assumption for their review.

---

## The Discovery Example

**User input:**
> "I'm building Vaultly — B2B SaaS for finance teams, automates accounts payable.
> Seed stage, $500k ARR, targeting mid-market CFOs. We look like every fintech —
> navy blue, 'efficiency' messaging. Competitors: Tipalti, Bill.com. We love Stripe,
> Linear. Want modern, trustworthy, not stuffy."

**Wizard response opens:**

> "Before we talk about what it looks like, let's talk about what it believes."
>
> **Brand Tension: Craft-Obsessed / Finance Infrastructure**
>
> "Vaultly sits in a specific contradiction: the people who care most about craft —
> who'd use Linear over Jira because the experience matters — are building tools for
> an industry that's never been cared for aesthetically. The tension is: a design tool
> built for a domain that's historically treated design as noise.
>
> This is the Stripe move applied to AP. Stripe didn't just build a better payment
> API — they made infrastructure beautiful, and that became its own argument for
> quality. Your visual and verbal language should make CFOs feel like someone who
> gives a damn built this. Not because you told them you care, but because they can
> see it in every pixel and every line of copy."
>
> **Category Villain: The Complicator**
>
> "Vaultly exists because AP software has been treating finance teams as data-entry
> clerks for too long. The villain isn't Tipalti specifically — it's the assumption
> that digitizing a manual process is the same as automating it. Your competitors
> built a faster version of the same broken workflow. Vaultly ends the workflow."
>
> [Continues with archetype, positioning, messaging, visual direction...]
