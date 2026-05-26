# Visual Identity Direction Generator

## Purpose
Produce specific, actionable visual direction a designer can execute from without a
meeting. Not "make it modern." Actual hex codes. Specific font names. Spacing ratios.
Reference images with "steal this, not that" guidance. And AI image prompts ready to
paste into Midjourney, Flux, or DALL-E.

---

## The Visual Direction Process

### Step 1: Score the Visual Axes

Apply the 5-axis scale from `frameworks/positioning.md`. Present scores for the brand
AND 1-2 competitors to show the visual territory available.

Format:
```
[Brand]:       Minimal([n]) / Cool([n]) / Serious([n]) / Novel([n]) / Literal([n])
[Competitor]:  Minimal([n]) / Cool([n]) / Serious([n]) / Novel([n]) / Literal([n])

Visual whitespace: [Which axes are unclaimed by competitors]
Direction: [The specific territory the brand should occupy and why]
```

---

### Step 2: Color System

**Primary Color** (60% of brand applications)
- Hex, RGB, HSL
- Emotional function: not just "this color means trust" — *what kind* of trust?
  The trust of a surgeon (precise, cool, nothing personal) or the trust of a best
  friend (warm, consistent, you've seen them at their worst)?
- Why this over the adjacent option

**Secondary Color** (30% of applications)
- Hex, RGB, HSL
- Relationship to primary: complement / analogous / split-complement
- Where it works and where it should never appear

**Accent Color** (10% — CTAs, highlights, interactive elements, data callouts)
- Must contrast at WCAG AA against both light and dark backgrounds
- Use this like punctuation — if everything is accented, nothing is

**Neutral System**
| Role | Hex | Use |
|---|---|---|
| Background | | Primary page/surface background |
| Surface | | Cards, panels, secondary surfaces |
| Border | | Dividers, card edges |
| Text primary | | Body copy, headlines |
| Text secondary | | Captions, metadata, placeholder text |
| Disabled | | Inactive states |

**Dark Mode Guidance**
If the product needs dark mode, provide equivalents. Rule: dark mode is not just
inverting light mode. The primary and accent colors will need luminance adjustments.
Provide adjusted hex values for dark mode explicitly.

---

### Step 3: Typography System

**Headline Font**
- Font name (or 2-3 ranked options if no clear winner)
- Where to get it: Google Fonts / Adobe Fonts / license required
- Weight range: which weights to use for which purposes
- Tracking recommendation at display and headline sizes
- Where NOT to use it (some display fonts are illegible at small sizes)

**Body Font**
- Font name
- Optimal size range for reading (usually 15-18px for web)
- Line-height (1.5-1.7 for body text)
- Letter-spacing (usually default or very slightly expanded)
- Fallback font stack

**UI/Mono Font** (if the product handles data, code, or technical content)
- For: numbers in tables, invoice amounts, API keys, code samples
- True tabular figures are non-negotiable for financial products (monospace numbers
  that align in columns)

**Type Scale**
| Level | Size | Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| Display | 56-72px | 700 | 1.05 | -0.03em | Hero headlines only |
| H1 | 40-48px | 700 | 1.1 | -0.02em | Page titles |
| H2 | 28-32px | 600 | 1.2 | -0.01em | Section headers |
| H3 | 22-24px | 600 | 1.25 | 0 | Subsection headers |
| H4 | 18-20px | 600 | 1.3 | 0 | Card headers, callouts |
| Body Large | 18px | 400 | 1.6 | 0 | Lead paragraphs |
| Body | 16px | 400 | 1.6 | 0 | Standard copy |
| Small | 14px | 400 | 1.4 | 0.01em | Captions, labels |
| Micro | 12px | 500 | 1.3 | 0.02em | Legal, timestamps |

---

### Step 4: Imagery Direction

**Photography style** (if using photography)

Treatment options: natural / high-contrast / desaturated / duotone / documentary /
editorial. Choose one. Mixed treatments read as inconsistent.

Subject matter: people / product / abstract / environmental / combination.
If people: real users not models, real contexts not studios, real faces not posed smiles.

Category-specific avoidances (examples):
- B2B fintech: no handshakes, no stock exchange floors, no money raining down, no
  "team around a laptop" shots, no overly diverse casting that reads as stock
- Consumer wellness: no green juice being poured in slow motion, no women in white
  laughing alone, no before/after weight shots
- Developer tools: no "person typing" photos, no stock office imagery, no staged demos

**Illustration style** (if using illustration)

Style category: flat / 3D / isometric / line-only / hand-drawn / geometric / character.
Choose one style and one level of complexity. Mixing illustration styles across
touchpoints is a common consistency failure.

Color discipline within illustration: use only brand palette colors in illustrations.
No illustrations introducing new colors not in the brand system.

**Iconography**
- Style: outline / filled / duotone — must match illustration style direction
- Stroke weight: [n]px at 24×24px base
- Corner treatment: sharp / slightly rounded / fully rounded — must be consistent
- Grid: 24px or 20px — pick one

---

### Step 5: Layout Principles

- **Grid:** 12-column at desktop, 4-column at mobile, [n]px gutters
- **Spacing base unit:** [n]px — all spacing is multiples of this (4px, 8px, 12px, 16px, 24px, 32px, 48px, 64px, 96px)
- **Density:** How generous the whitespace is — reference a comparable brand on the 1-5 minimal/expressive scale
- **Elevation:** Card-and-shadow / subtle-border / flat — must be consistent across all surfaces
- **Corner radius system:** [n]px for buttons, [n]px for cards, [n]px for images — three values, all consistent

---

### Step 6: Reference Board

**3 brands with specific steal/skip guidance:**

**Reference 1: [Brand Name]**
Steal: [Specific element — a layout pattern, color approach, type treatment — with WHY it fits this brand]
Skip: [What doesn't apply and exactly why it would be wrong here]
Touchpoint: [Specific URL or description of the exact piece to reference]

**Reference 2: [Brand Name]**
[Same structure]

**Reference 3: [Brand Name]**
[Same structure]

**Anti-references (what to explicitly not look like):**
Name 2-3 brands/touchpoints that represent the visual clichés of the category.
"Do not, under any circumstances, look like [X]" — and explain exactly what to avoid.

---

### Step 7: AI Image Prompts

Produce 3-5 prompts, ready to paste into Midjourney, Flux, or DALL-E.
Each prompt includes: subject, style, color direction, composition, lighting,
and negative prompts (what to exclude).

**Prompt formula:**
```
[Subject description], [art direction style], [color palette in plain language],
[composition and framing], [lighting quality], [mood/feeling],
--no [exclusions list]
--style [reference if using Midjourney style references]
--ar [ratio]
```

**Example prompts for a B2B fintech brand (Cool/Minimal/Serious/Novel aesthetic):**

```
Prompt 1 (hero imagery — abstract):
Abstract fluid shapes suggesting data flow and precision, dark navy and electric indigo
color palette with cyan highlights, minimal composition with strong negative space,
studio lighting with subtle gradient, the mood of a finely engineered machine at rest,
photorealistic render with depth of field
--no people, text, logos, gradients that feel cheap, lens flares, warm colors, orange
--ar 16:9

Prompt 2 (product context — environmental):
Finance professional reviewing data on a minimal dark-mode interface, shot from above
as overhead flat lay, notebook and mechanical keyboard visible, cool blue-gray color
grading, natural window light from left, documentary photography style, no posing
--no smiling, stock photo composition, diverse group, laptop lifestyle shot, warm filters
--ar 4:3

Prompt 3 (abstract — brand expression):
Precise geometric forms suggesting organizational structure, deep space navy background,
thin lines of electric indigo suggesting data connections, small glowing nodes at
intersections, the aesthetic of a circuit board reimagined as fine art, 3D render
--no people, organic shapes, warm colors, busy composition, cheap gradients
--ar 1:1

Prompt 4 (pattern / background texture):
Minimal grid pattern with subtle technical texture, near-black with barely visible
structural lines in deep navy, the texture of a precision-engineered surface,
suitable for use as a background or section divider
--no visible patterns, obvious textures, warm tones, high contrast, busyness
--ar 16:9
```

**How to adapt these for other brand directions:**

For Warm/Expressive/Playful brands:
- Replace "minimal composition" with "warm dynamic composition"
- Replace "studio lighting" with "golden hour / warm daylight"
- Add "vibrant," "energetic," "joyful" to mood descriptors
- Change color references from cool to warm palette

For Minimal/Neutral/Familiar brands:
- Lead with "clean white background"
- Add "editorial photography style, Monocle magazine aesthetic"
- Use "natural, honest, direct" in mood descriptors

For Abstract/Novel brands:
- Lead with "surreal," "unexpected," "conceptual"
- Reference art movements: "brutalist composition," "Bauhaus-influenced"
- Remove realistic photography constraints
