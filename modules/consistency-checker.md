# Brand Consistency Checker & "Why Does This Feel Off?" Diagnostic

## Image Handling Protocol

When a user uploads an image — a screenshot, a logo, a landing page, an ad — analyze
in this exact order before diagnosing:

**1. First impression (5 seconds, instinct only)**
Name the emotion the design creates before analyzing any element. This is the most
honest read. Write it down before it's contaminated by analysis.

**2. Hierarchy read**
Where does the eye land first? Second? Third? Does this sequence serve the communication
goal? Is the CTA visible in the first three stops?

**3. Consistency check**
Does everything feel like it came from the same hand? Same visual language — color,
type, spacing, image treatment? Or do different sections feel like they were made
by different people without talking to each other?

**4. Differentiation check**
Apply the Competitor Swap Test immediately. Could this belong to a competitor?
If yes, what's the most efficient fix to make it unmistakably theirs?

**5. Named heuristic failures**
Run through the priority heuristics from `frameworks/critique-heuristics.md`:
H4 (Competitor Swap) → H1 (5-Second) → H5 (So What) → H11 (Brand Coherence) → H8 (Emotion).

**Then prescribe.** One fix at a time, in priority order.

---

## When to Run a Consistency Audit vs. "Why Does This Feel Off?"

**Run the Consistency Audit when:**
- User has multiple touchpoints and wants to know if they cohere
- Company is scaling and different teams are producing brand materials
- Post-rebrand, verifying the new brand landed consistently

**Run the "Why Does This Feel Off?" diagnostic when:**
- User shares one piece of work and it doesn't feel right but they can't name why
- Something works technically but feels wrong emotionally or aesthetically
- The designer is "on brief" but the result is still missing something

---

## The Consistency Audit

### Step 1: Establish the Benchmark
Before auditing, establish what "on-brand" means. Hierarchy of sources:
1. Brand DNA document (if it exists)
2. The brand's best-performing touchpoint (if no formal guidelines)
3. The touchpoint the founding team points to when asked "what do you want it to look like?"

If none of these exist, this is a discovery problem, not a consistency problem.
Go to `modules/discovery.md` first.

### Step 2: The 6-Dimension Audit
For each touchpoint, score against the benchmark:

| Dimension | What to evaluate |
|---|---|
| **Color** | Same palette? Ratios maintained? Accent used correctly (not everywhere)? |
| **Typography** | Same fonts? Same hierarchy system? Consistent weights? |
| **Voice** | Same tone? Formal/casual consistent? Brand vocabulary used? |
| **Imagery** | Same style? Consistent treatment and quality level? |
| **Layout** | Same spacing? Same density? Same structural patterns? |
| **Personality** | Does each touchpoint feel like the same brand made it? |

### Step 3: Score Each Touchpoint

Grade: **A** (on-brand) / **B** (minor drift) / **C** (noticeable inconsistency) / **D** (off-brand)

| Touchpoint | Color | Type | Voice | Imagery | Layout | Personality | Overall |
|---|---|---|---|---|---|---|---|
| Website | | | | | | | |
| App/product UI | | | | | | | |
| Social media | | | | | | | |
| Email | | | | | | | |
| Pitch deck | | | | | | | |
| Documentation | | | | | | | |
| Job listings | | | | | | | |
| Ad creatives | | | | | | | |

### Step 4: Root Cause Diagnosis

**Don't just fix symptoms. Name the root cause.**

| Root Cause | Signs | Fix |
|---|---|---|
| **No system** | Every touchpoint looks different; no common elements | Build the brand system before fixing individual touchpoints |
| **Too many cooks** | Touchpoints in the same channel look inconsistent | Brand ownership + review process before publishing |
| **Platform defaults** | Mailchimp/HubSpot/Canva templates without customization | Build branded templates for every platform used |
| **Time pressure** | Quality cliff between important pages and secondary ones | Brand checklist before any asset goes live |
| **Unmanaged evolution** | Website evolved, old templates persist | Hard deadline to migrate everything |
| **Missing verbal guidelines** | Visual brand is strong, copy is all over the place | Voice rules + sample copy for every context |
| **Missing visual guidelines** | Copy is on-brand, visual execution varies | Document the visual system |

### Step 5: Priority Fixes

For each failing touchpoint, prescribe:

> **[Touchpoint]: [Current Grade] → [Target Grade]**
> - Fix 1: [Specific change — hex codes, font names, exact language]
> - Fix 2: [Specific change]
> - Priority: High / Medium / Low
> - Effort: 30 minutes / Half-day / Full redesign

---

## The "Why Does This Feel Off?" Diagnostic

When a user shares work and says something is wrong but can't name it, run through this
diagnostic before giving any feedback. Do NOT jump to a solution before identifying the problem.

### The 7 "Off" Patterns

**1. Tonal Split**
The visuals and the copy are targeting different audiences or expressing different
personalities. The visual says "premium and serious" and the headline says "hey hey hey."
Or the visual is playful and warm and the copy is clinical and formal.

*Diagnosis: "You have a Tonal Split — your visuals and copy are different brands
living in the same frame."*
*Fix: Align one to the other. Usually, align the copy to the visual since the visual
registers first.*

**2. Quality Cliff**
The hero section is polished and designed with care. Everything below the fold is
template-quality at best. The user put all their attention at the top and ran out
of energy/budget/time for the rest.

*Diagnosis: "You have a Quality Cliff at [location] — the experience drops from
designed to built in one scroll."*
*Fix: Either raise the floor or explicitly make the contrast a design choice
(sometimes stark simplicity below a rich hero can work).*

**3. Borrowed Aesthetic**
The brand looks like another brand in a different category. The borrowed aesthetic
carries the wrong associations. A startup that adopted Figma's visual language now
looks like a design tool. An enterprise brand that borrowed Duolingo's illustration
style now looks childish.

*Diagnosis: "You're borrowing [Brand X]'s aesthetic, which in your category
communicates [wrong thing]. You need to own your visual direction, not rent someone else's."*

**4. Uncanny Valley of Branding**
The brand is close enough to a recognizable style that it looks like a bad imitation
instead of its own thing. Imitating Linear without Linear's execution quality. Imitating
Apple without Apple's restraint. Close misses are worse than being far away — they signal
"we tried and didn't quite make it."

*Diagnosis: "You're in the Uncanny Valley — close enough to [reference] that you look
like a weak version of it instead of something distinct."*
*Fix: Either commit to being genuinely different or match the reference quality exactly.*

**5. Scale Mismatch**
Elements feel like they're from different zoom levels. A huge hero image paired with
tiny body text. An oversized icon next to a micro-headline. The proportional system
is broken — nothing relates to anything else.

*Diagnosis: "You have a Scale Mismatch — your elements don't belong to the same
proportional system."*
*Fix: Establish a spacing and scale system and apply it everywhere.*

**6. Color Temperature War**
Warm and cool elements are fighting for dominance. A warm photography treatment paired
with a cool, blue-dominant color palette. Earth-toned illustration with electric accent
colors. The visual temperature is inconsistent and creates subliminal discomfort.

*Diagnosis: "You have a Color Temperature War — your warm and cool elements are fighting."*
*Fix: Choose a temperature direction and ensure every element is on the same side.
Warm imagery with warm palette, or cool imagery with cool palette.*

**7. Style Mixing**
Three or more visual languages coexist without integration. Flat icons + realistic
photography + gradient buttons + hand-drawn illustration. Each element came from a
different decision made at a different time by a different person.

*Diagnosis: "You're style mixing — your visual language has [n] dialects and they
don't share a grammar."*
*Fix: Run the Consistency Audit. Pick one visual system and migrate everything to it.*

---

## The Stakeholder Translation Layer

When users need to explain brand decisions to non-design stakeholders (CEO, board,
engineering leadership, investors), translate every design decision into business language.

### Translation Rules
- Replace design terms with customer impact
- Frame every decision as a conversion or retention consequence
- Use competitor comparisons as anchors (stakeholders respect competitive context)
- Lead with the problem, not the solution

### The Translation Table

| You want to say | Say this instead |
|---|---|
| "We need more whitespace" | "Users can't find the CTA — we're losing conversions to cognitive load" |
| "The typography hierarchy is broken" | "Users don't know what to read first — they bounce before reaching the value prop" |
| "This color is off-brand" | "We look inconsistent with our other touchpoints — which erodes trust with sophisticated buyers who notice" |
| "The visual direction is too generic" | "We're invisible next to [competitor] — the Competitor Swap Test fails completely" |
| "The design is trying to do too much" | "We're asking users to make 6 decisions before they know what we do" |
| "The tone is wrong" | "[Target audience] reads this as [wrong emotion] — we surveyed [n] and they [specific reaction]" |
| "The logo needs more breathing room" | "At small sizes — app icon, email sender, browser tab — the logo becomes unreadable" |
| "We need a proper type system" | "Every new page we build requires design involvement because there's no system — it's slowing down every launch" |
