# Design Brief Generator

## Purpose
Produce design briefs that a freelance designer, agency, or internal team can execute from without a 45-minute kickoff call. Every field is filled. No ambiguity.

## Trigger Phrases
- "Write me a design brief"
- "I need to brief a designer"
- "Create a brief for [specific deliverable]"
- "Help me write a creative brief"

## Inputs Required
1. What's being designed (logo, landing page, pitch deck, social templates, packaging, etc.)
2. Who's the audience for this deliverable
3. What's the single most important thing this design must communicate
4. Brand context (provide or reference existing Brand DNA)
5. Timeline and constraints (if any)
6. What "done" looks like — what does the user need to approve/ship

## Brief Generation Process

### Step 1: Clarify the Deliverable
If the user says "I need a design brief," ask what's being designed. Don't produce a generic brief — the format changes based on the deliverable:

| Deliverable | Key Sections |
|---|---|
| Logo/wordmark | Brand attributes, usage contexts, competitive marks to avoid |
| Landing page | Conversion goal, content hierarchy, page structure |
| Pitch deck | Story arc, data to include, audience context |
| Social templates | Platform specs, content types, frequency |
| Packaging | Physical specs, shelf context, regulatory requirements |
| App/product UI | User flows, interaction patterns, component needs |

### Step 2: Fill the Template
Use `templates/design-brief.md` as the structure. Fill every field based on user inputs and brand context. Where the user hasn't provided info, make an opinionated recommendation and flag it as an assumption.

### Step 3: Add Visual Direction
Pull from the brand's visual direction (from discovery or existing brand DNA):
- Specific color codes
- Font names
- Imagery rules
- Layout principles
- 3 visual references with "what to take from this" notes

### Step 4: Define Success Criteria
Write 3-5 specific, evaluable criteria. Not "looks good" — things like:
- "A user can identify what this product does within 3 seconds"
- "The design passes the Competitor Swap Test"
- "Primary CTA is the most visually dominant element on the page"

### Step 5: Anticipate Questions
List 5 questions a designer would likely ask, and answer them preemptively.

## Output
A complete, ready-to-send design brief in markdown. The user should be able to copy-paste this into a Notion doc or email and send it to a designer with zero edits.

## Example Exchange

**User:** "I need a design brief for our new landing page. We're Vaultly, AP automation for finance teams."

**Wizard:** 
```
# Design Brief: Vaultly Landing Page

## Overview
Redesign the Vaultly marketing landing page to convert mid-market 
CFOs and finance leaders evaluating AP automation tools.

## Objective
Primary: Drive demo requests from qualified finance leaders
Secondary: Establish Vaultly as the "craft-forward" AP tool 
(distinct from Tipalti/Bill.com's corporate aesthetic)

## Target Audience
- CFOs and VP Finance at companies with 100-1000 employees
- Currently using manual AP processes or legacy tools
- Technically savvy enough to evaluate software independently
- Skeptical of "AI" claims — need proof, not promises

## Key Message
"Your AP closes itself." 
Vaultly handles routine invoices end-to-end so finance teams 
do finance work, not data entry.

## Content Hierarchy
1. Hero: Value prop + single CTA (Book Demo)
2. Social proof: Logo bar + one specific metric
3. How it works: 3-step visual flow
4. Features: 3 key capabilities with product screenshots
5. ROI section: Time/money saved calculator or proof point
6. Testimonial: One specific quote from a named CFO
7. Final CTA: Repeat demo request

[...continues with full visual direction, constraints, 
success criteria, and preemptive Q&A]
```

**User:** "Add a section about integrations."

**Wizard:** "Added. But I'd push it below the testimonial — integration lists are trust signals, not decision drivers. CFOs don't pick AP tools based on how many logos you show. They pick based on 'will this actually work?' Put the integration section after the social proof that it does."
