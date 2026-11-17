# Ciridae — blueprints and embers

## Overview

Cinematic darkness opens into warm, technical paper layouts, giving ambitious software a tangible, industrial character. Condensed grotesk headlines, plain regular-weight prose and tiny monospaced markings balance emotional atmosphere with engineering credibility. Defocused moving imagery and fine isometric diagrams suit complex products and hands-on services; the overall density is airy, with concentrated pockets of explanatory detail.

### Essentials

- A cinematic promise floats above technical paper: an approximately 865px dark opening uses a centered two-line 104px condensed uppercase headline at 0.88 line height, then yields to warm cream and parchment bands.
- Headlines have two distinct gears: condensed 64px/0.96 section leads with -0.046em tracking contrast with wider grotesk editorial statements and quotes, all at weight 400.
- Conversion has an industrial hierarchy: the hero action is a square-cornered rust rectangle with 16px 24px padding; utility actions are 42px outline pills and secondary actions are small underlined mono text.
- Color behaves like a working annotation: parchment #eae1ce and near-white #fcfbf8 dominate the middle of the page; rust #cc6437 is confined to the opening action, active diagram parts and a singled-out proof mark rather than whole bands.
- Every landing page pairs atmospheric light with an engineered model: a full-bleed dark, softly blurred warm/cool opening and a fine-line isometric system diagram on bare paper. Without original footage or product art, use layered defocused light forms and a simple exploded SVG stack.
- Labels read like blueprint marginalia: 11px/1.35 uppercase mono at 0.08em tracking, numbered steps and 1px rules organize illustrations and proof without rounded card chrome.
- The ending is a small illuminated brand shrine, not just link columns: a centered emblem and wordmark, 32px uppercase condensed invitation, a tiny amber-highlighted proof phrase, paired outline pills and three directory columns sit on a top-centered charcoal radial glow.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Parchment | `#eae1ce` | `--color-canvas` | background, surface | Main technical chapters, proof bands and testimonial cards. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fired rust | `#cc6437` | `--color-rust` | accent, action, link | Primary hero action, highlighted diagram segment, final comparison bar and link hover. |
| Amber glint | `#e8b768` | `--color-amber` | accent, text | Single short footer proof figure and hero-action hover/focus. |
| Burnished brown | `#8d4323` | `--color-rust-dark` | text, link | Underlined-link hover and emphasis at the end of the editorial statement. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Night | `#0b0b0b` | `--color-dark` | background | Dark closing canvas and recruiting opening. |
| Warm black | `#14110d` | `--color-ink` | text, background, action | Primary text on light paper, diagram lines and filled closing action. |
| Charcoal glow | `#272a2a` | `--color-glow` | background, border | Top-center radial light in the footer and recruiting list top rule. |
| Brown charcoal | `#37332a` | `--color-body` | text, border | Body copy, explanatory labels and fine diagram strokes. |
| Technical brown | `#5b5548` | `--color-muted` | text | Small diagram captions and numbered quote indices. |
| Utility gray | `#575757` | `--color-utility-gray` | border, text | Utility outline action on neutral navigation treatment; use chalk when over dark imagery. |
| Parchment hairline | `#bbb3a4` | `--color-rule` | border | Visible result of warm black at 22% over parchment. On near-white the same alpha rule appears lighter. |
| Warm gray | `#d3cec4` | `--color-hero-support` | text | Supporting copy against cinematic darkness. |
| Navigation gray | `#e1e1e1` | `--color-nav-text` | text | Top-level navigation on dark imagery. |
| Chalk | `#efede7` | `--color-light-ink` | text, border | Footer text and outline actions; used at 22% alpha for dark dividers, 55–62% alpha for muted labels. |
| Ivory | `#f7f2e7` | `--color-cream` | text, background | Hero display text and final light conversion band. |
| Near-white paper | `#fcfbf8` | `--color-paper` | background | Editorial breathing space, process and testimonial sections. |
| White | `#ffffff` | `--color-white` | text, border | Recruiting typography and outline action; at 58% alpha for light band edges and at low alpha for utility hover glow. |

## Typography

- **Pragmatica Cond** — Hero, section headlines, period figures and closing invitation. Tall, narrow industrial grotesk with open counters and a regular stroke. If unavailable, use **Roboto Condensed**. Use 400; retain tight headline tracking and compact line height. Font stack: "Pragmatica Cond", "Roboto Condensed", Arial, sans-serif.
- **Pragmatica** — Editorial statements, wider section headings, quotes and body copy. Neutral neo-grotesk whose regular weight lets size and spacing provide hierarchy. If unavailable, use **Roboto**. Use 400; do not compensate with semibold headings. Font stack: "Pragmatica", "Roboto", Arial, sans-serif.
- **ABC Monument Grotesk Mono** — Navigation, blueprint captions, technical labels and secondary links. Compact mechanical mono with deliberately spaced capitals. If unavailable, use **Roboto Mono**. Use 400 with the role-specific tracking. Font stack: "ABC Monument Grotesk Mono", "Roboto Mono", monospace.
- **Roboto Mono** — Button labels and short utility metadata. Plain monospaced uppercase lettering with slightly negative tracking. Font stack: "Roboto Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Pragmatica Cond | 400 | 104px | 0.88 | -0.02em, uppercase | fixed | Centered two-line opening promise. |
| heading | Pragmatica Cond | 400 | 64px | 0.96 | -0.046em | fixed | Default section heading and light closing conversion headline. |
| heading-wide | Pragmatica | 400 | 64px | 0.96 | -0.046em | fixed | Editorial process introduction, where wider letters complement the technical figures. |
| quote-featured | Pragmatica | 400 | 64px | 1.02 | -0.03em | fixed | Dominant testimonial. |
| heading-medium | Pragmatica | 400 | 48px | 1 | -0.042em | fixed | Proof-band heading and chart introduction. |
| statement | Pragmatica | 400 | 36px | 1.25 | -0.034em | fixed | Centered manifesto-style statement on a wide quiet band. |
| period | Pragmatica Cond | 400 | 36px | 1.1 | normal | fixed | Duration or milestone figure above each process illustration. |
| footer-invitation | Pragmatica Cond | 400 | 32px | 1.04 | -0.02em, uppercase | size clamp(1.375rem, 3.2vw, 2rem) | Centered two-line invitation in the dark ending. |
| quote | Pragmatica | 400 | 28px | 1.25 | -0.01em | fixed | Supporting testimonial cards. |
| card-heading | Pragmatica | 400 | 21px | 1.3 | -0.01em | fixed | Short process outcome titles. |
| body | Pragmatica | 400 | 18px | 1.6 | normal | fixed | Hero support and section introductions. |
| body-small | Pragmatica | 400 | 16px | 1.55 | normal | fixed | Process descriptions and explanatory paragraphs. |
| action | Roboto Mono | 400 | 14px | 1.1 | -0.02em, uppercase | fixed | Filled and outlined action labels. |
| label | ABC Monument Grotesk Mono | 400 | 13px | 1.3 | 0.06em, uppercase | fixed | Section eyebrows, secondary text links and quote attribution. |
| footer-link | ABC Monument Grotesk Mono | 400 | 12px | 1.5 | 0.04em, uppercase | fixed | Footer directory links. |
| proof-caption | ABC Monument Grotesk Mono | 400 | 12px | 1.4 | 0.08em, uppercase | fixed | Short proof phrase with amber figure beneath the footer invitation. |
| caption | ABC Monument Grotesk Mono | 400 | 11px | 1.35 | 0.08em, uppercase | fixed | Blueprint captions, phase labels and quote indices. |
| navigation | ABC Monument Grotesk Mono | 400 | 11px | 1.1 | 0.06em, uppercase | fixed | Top navigation triggers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| recruiting pages | role-title | Pragmatica | 400 | 16px | 1 | normal, uppercase | fixed | Centered vacancy title in a ruled list. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular weight is the default throughout; condensed versus wider sans is a structural distinction, not a weight change.
- Large headings tighten to -0.046em, while small technical capitals open to 0.06–0.08em. Keep body copy untracked.
- The opening is uppercase; ordinary light-section headings are sentence case. Quote text is the wider sans, not the condensed display face.

## Layout

**Density:** Airy overall, with compact technical labels and dense diagram annotations inside broad paper bands.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Small vertical stacks and invitation-to-proof gap. |
| 16px | Compact quote-card content and paired footer actions. |
| 24px | Action horizontal padding, featured quote stack and process figure separation. |
| 32px | Hero stack gaps, standard card padding and technical sidebar inset. |
| 40px | Footer side inset and space before its directory. |
| 48px | Heading-pair gap, featured quote padding and testimonial row gap. |
| 56px | Process introduction to timeline. |
| 64px | Chart panel vertical padding and its split-column gap. |
| 128px | Major technical section top padding and closing light-band padding. |
| 160px | Major technical section bottom padding. |
| 256px | Vertical padding around the centered editorial statement. |

### Containers and grids

- **marketing-shell**: max width 1258px · side padding 91px. Centered desktop content region within a 1440px page. It combines a 48px outer margin and 43.2px inner inset.
- **heading-pair**: 2 columns · gap 48px. Headline takes roughly three fifths of the row; a compact 345px support paragraph sits to its right, bottom-aligned.
- **technical-sheet**: 2 columns · gap 0px. A roughly 1.75:1 split gives the diagram the majority of the width; a left-ruled explanatory sidebar occupies the rest.
- **process-grid**: 3 columns · gap 0px. Equal-width process steps share one continuous top rule.
- **testimonial-grid**: 3 columns · gap 32px. One featured card spans two thirds of the row; three smaller cards sit below with a 48px row gap.
- **footer-shell**: max width 1360px · 3 columns · gap 30px · side padding 40px. Wider directory and metadata rows, framing a narrow centered brand-and-invitation stack.
- **recruiting-list** (only for recruiting pages): max width 1400px · side padding 20px. Near-edge-to-edge list, visually wider than the editorial content shell.

## Corner radius

| Element | Radius |
| --- | --- |
| Utility actions | 9999px (pill) |
| Commercial actions and proof cards | 0px |
| Step markers | 50% |

## Surfaces and depth

### Surfaces

#### Parchment canvas · level 0

**Use:** Default technical chapter background.

**CSS:** `background: #eae1ce; color: #14110d`

**Observed:** Warm flat paper, with sections separated by very faint horizontal edges.

**Transfer:** Use this for detailed explanation and visual systems.

#### White paper band · level 0

**Use:** Process, statement and testimonial chapters.

**CSS:** `background: #fcfbf8; color: #14110d`

**Observed:** Alternates with parchment without elevation or rounded containers.

**Transfer:** Let alternating paper tones separate narrative functions.

#### Ivory conversion band · level 0

**Use:** Final light commercial invitation.

**CSS:** `background: #f7f2e7; padding: 128px 0px`

**Observed:** A sparse left-aligned text stack precedes the dark ending.

**Transfer:** Keep the invitation direct and leave the right half mostly open.

#### Ruled sheet · level 1

**Use:** Diagram and compounding-value panels.

**CSS:** `border-top: 1px solid rgba(20, 17, 13, 0.22); border-bottom: 1px solid rgba(20, 17, 13, 0.22); box-shadow: none`

**Observed:** The panel is part of the page rather than an elevated card.

**Transfer:** Use rules to define a working document.

#### Parchment proof card · level 1

**Use:** Testimonials.

**CSS:** `background: #eae1ce; border: 1px solid rgba(20, 17, 13, 0.22); border-radius: 0px; box-shadow: none`

**Observed:** Flat rectangular cards on a lighter paper section.

**Transfer:** Keep contrast tonal rather than shadow-based.

#### Night glow · level 0

**Use:** Shared footer.

**CSS:** `background: radial-gradient(at 50% 0%, #272a2a 0%, #0b0b0b 78%); color: #efede7`

**Observed:** A restrained broad gray-green light at the top fades almost completely to black toward the bottom.

**Transfer:** Use the glow to illuminate the centered emblem, not as a rainbow gradient.

## Components

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 1fr) auto minmax(0px, 1fr); gap: 24px; padding: 8px 24px; align-items: center`

**Text style:** `navigation` — ABC Monument Grotesk Mono 400 · 11px/1.1 · tracking 0.06em · uppercase

**Observed:** Wordmark at left, three tiny uppercase triggers with downward carets in the middle, outline action at right. The opening treatment is transparent over imagery; the logo and action read light.

**States:** Declared: hover changes trigger text to #cc6437; focus-visible uses a 2px outline with 4px offset; active scales triggers to 0.96.

### Primary button

**Use:** Main commercial action over cinematic darkness.

**CSS:** `background: #cc6437; color: #14110d; border: 1px solid #cc6437; border-radius: 0px; padding: 16px 24px; height: 51px; box-sizing: border-box`

**Text style:** `action` — Roboto Mono 400 · 14px/1.1 · tracking -0.02em · uppercase

**Observed:** A compact solid rectangle centered below hero support. On the final light band the counterpart uses warm black fill, ivory lettering and 14px vertical padding for a 46px height.

**States:** Declared: hover becomes transparent with #e8b768 text and border; focus-visible adds a 2px #e8b768 outline at 3px offset; active scales to 0.97.

### Outline pill

**Use:** Utility actions in navigation and footer.

**CSS:** `display: flex; align-items: center; justify-content: center; background: transparent; color: #efede7; border: 1px solid #efede7; border-radius: 9999px; padding: 10px 18px; height: 42px; box-sizing: border-box`

**Text style:** `action` — Roboto Mono 400 · 14px/1.1 · tracking -0.02em · uppercase

**Observed:** Paired pills sit at the center of the footer metadata row. A neutral navigation variant uses the utility-gray edge; the dark-image treatment uses a light edge.

**States:** Declared: hover adds outer 16px rgba(255,255,255,0.18) and inset 16px rgba(255,255,255,0.14) glows with a 10% current-color wash; focus-visible uses a 2px outline at 4px offset; active scales to 0.97.

### Underlined link

**Use:** Secondary commercial navigation on light sections.

**CSS:** `color: #14110d; border-bottom: 1px solid rgba(20, 17, 13, 0.44); text-decoration: none`

**Text style:** `label` — ABC Monument Grotesk Mono 400 · 13px/1.3 · tracking 0.06em · uppercase

**Observed:** Short uppercase text ends with a small northeast arrow. It sits below explanatory copy rather than competing with the filled action.

**States:** Declared: hover changes text and underline to #8d4323; focus-visible adds a 2px #8d4323 outline at 3px offset; active scales to 0.97.

### Process step

**Use:** Explain staged adoption or progression.

**CSS:** `position: relative; border-top: 1px solid #14110d; padding: 28px 32px 32px 0px`

**Text style:** `card-heading` — Pragmatica 400 · 21px/1.3 · tracking -0.01em

**Observed:** A small dot starts the rule; period figure comes first, followed by an isometric illustration, tiny phase label, short title and supporting copy. Across the row, the rule ends in an arrow. The first marker is filled and later markers are outlined.

**Transfer:** Replace durations with meaningful stages, preserving the period–diagram–label–outcome order.

### Testimonial card

**Use:** Human evidence with a document-like treatment.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 32px; background: #eae1ce; border: 1px solid rgba(20, 17, 13, 0.22); border-radius: 0px`

**Text style:** `quote` — Pragmatica 400 · 28px/1.25 · tracking -0.01em

**Observed:** Index at top, quote in the middle, thin divider and monochrome customer mark plus mono attribution at the foot. The featured version uses 48px padding, a 24px stack gap and the featured quote recipe.

**Transfer:** Keep a dominant quote visibly larger than the supporting voices.

### Workflow trace

**Use:** Tie explanatory steps to a technical diagram.

**CSS:** `border-left: 1px solid rgba(20, 17, 13, 0.22); padding: 24px 0px 24px 32px`

**Observed:** Tiny mono numbers sit left of condensed step titles and concise body copy; horizontal rules separate entries. The active number is rust while the inactive sequence stays neutral.

**Transfer:** Use a short operational sequence that explains what changes in the adjacent drawing.

### Footer directory

**Use:** Navigation at the end of every page.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); gap: 30px; border-top: 1px solid rgba(239, 237, 231, 0.22); padding-top: 24px; margin-top: 40px`

**Text style:** `footer-link` — ABC Monument Grotesk Mono 400 · 12px/1.5 · tracking 0.04em · uppercase

**Observed:** Muted tiny group headings sit above uppercase links; social links are centered below a second rule, followed by copyright and legal microcopy. It is subordinate to the illuminated invitation above.

**States:** Declared: hover changes links to #cc6437; focus-visible uses a 2px outline at 4px offset; active scales links to 0.96.

### Vacancy row

**Only for:** recruiting pages

**Use:** Open-position navigation.

**CSS:** `display: grid; grid-template-columns: 38px minmax(0px, 1fr) 38px; align-items: center; padding: 20px 16px; min-height: 64px; box-sizing: border-box; border-bottom: 1px solid rgba(20, 17, 13, 0.22)`

**Text style:** `role-title` — Pragmatica 400 · 16px/1 · uppercase

**Observed:** A small outlined numbered capsule anchors the left; the job title is truly centered using equal side tracks. Rows are flat and separated by hairlines, with a darker line over the list.

**States:** Declared: focus-visible uses a 2px outline inset by 2px; hover and active remove the outline.

## Imagery and graphics

### Defocused cinematic atmosphere

**Use:** Required atmospheric opening device for marketing landing pages.

**Observed:** An edge-to-edge moving background is heavily defocused into warm copper forms on the left and smoky blue-gray shapes on the right, against a near-black field. It fills the hero rather than occupying a separate media rectangle; text stays crisp above it.

**Transfer:** Use abstracted macro footage of the new product's materials or working environment. The minimum equivalent is a slowly moving composition of defocused warm and cool light forms, never a sharp stock-office photograph.

**Build:** Start with a near-black full-bleed layer. Place two oversized elliptical warm lights at the left, one oblique horizontal and one vertical, with rgba(204,100,55,0.35); balance with rgba(120,145,160,0.2) at the upper right. Blur by 60–100px, darken the center behind text, and overlay monochrome SVG fractal noise at 0.026 opacity. Match the soft photographic light; exact stops are not essential.

### Isometric working model

**Use:** Required engineered-model device within a light technical chapter.

**Observed:** Fine dark linework constructs exploded trays, record sheets, modules and connectors in parallel isometric projection. The main diagram takes about three fifths of its panel; a few plates are rust-filled while the rest inherit the paper backing. Smaller process versions use black active tiles and faint exploded foundations.

**Transfer:** Turn the new product's inputs, work and outputs into three layers or connected modules. A clean exploded SVG with six simple trays is sufficient; preserve open paper around the drawing rather than adding a glossy 3D render.

**Build:** Use SVG groups with isometric axes around 30 degrees. Draw thin parallelogram tray tops, shallow extruded side walls and repeated inset rectangles using 1px warm-black or brown-charcoal strokes. Stack three planes with vertical gaps and dashed connector lines. Add tiny mono leaders and captions. Highlight only one or two modules with rust or warm-black fill; keep other fills paper-colored.

### Compounding proof chart

**Use:** A quantitative or directional proof device accompanying an editorial explanation.

**Observed:** A flat chart sits on the same paper, with repeated thin horizontal guides and many narrow neutral columns; the last column alone is tall and rust-colored. Labels are mono and the chart is bracketed by panel rules.

**Transfer:** Use truthful data or explicitly qualitative comparisons from the new product. Retain the one-accent ending rather than multicolored analytics chrome.

**Build:** Within a roughly 716px by 280px SVG, draw four horizontal hairline guides, a brown-charcoal baseline and evenly spaced narrow vertical rectangles. Give neutral bars a pale gray fill with thin dark top and side edges, and the final bar a rust fill. Keep labels outside the plot and avoid axes clutter.

### Emblem shrine

**Use:** Brand identifier above the hero promise and repeated as the footer's focal object.

**Observed:** A slender ivory star-like emblem is centered above the opening title, then appears smaller above a compact wordmark at the ending. It is a crisp flat silhouette against atmospheric darkness, not a large word sculpture.

**Transfer:** Use the new brand's own simple emblem, or a custom abstract geometric symbol, at approximately 140px opening scale and 105px closing scale. Preserve the ceremonial separation between emblem, name and invitation.

**Build:** Compose a small original SVG from thin concave diamond or four-point light shapes, with restrained symmetry and generous negative space. Use a single ivory fill or fine stroke; no bevel, rainbow or luminous outline.

### Recruiting typographic sculpture

**Only for:** recruiting pages

**Use:** Expressive interlude beneath the recruiting promise.

**Observed:** A narrow central arrangement of small rotated aphoristic text is visible against black beneath the centered promise.

**Transfer:** Use a restrained typographic motif with original short phrases; keep the recruiting headline and route to positions legible without relying on the motif.

**Build:** Set a few short mono or condensed text runs vertically in a narrow central SVG group, rotate them through opposing orientations, and vary opacity. Keep the text small and subordinate to the opening promise.

### Icons

**Observed:** Small diagram arrows use thin brown-charcoal strokes, including 22px by 16px arrow shapes with 1px butt-ended lines. Top navigation carets are tiny solid triangles; text links use a northeast-arrow glyph. Customer marks are monochrome.

**Transfer:** Favor line arrows, numbering and technical leaders over pictorial feature icons. Keep interface iconography out of editorial headings.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise

**Observed:** An approximately 865px full-bleed dark opening layers a warm-black base and fine grain, defocused warm/cool atmosphere, transparent Navigation, centered Emblem shrine, then the display headline, support and Primary button. The two-line 104px uppercase headline visually occupies about three fifths of the screen width, with compact 0.88 leading. The emblem sits above it in the upper-middle area; support is centered in a roughly 647px measure, separated by 32px. The action is another 32px below. All of these are visible inside the first 900px; only a sliver of the next pale section appears, while the explanatory chapters remain below.

**Transfer:** Use a similarly short transformational promise and an original emblem over the atmospheric fallback if footage is unavailable. Recruiting pages instead open on flat black with a smaller centered uppercase promise, category label and a subordinate typographic interlude; their outline action can fall below the first screen.

**Avoid:** Do not substitute a left-copy/right-dashboard hero or place the headline inside a floating rounded card. Do not expose sharp detailed media that competes with the central promise.

**Text style:** `display` — Pragmatica Cond 400 · 104px/0.88 · tracking -0.02em · uppercase

### Editorial pause

**Observed:** A near-white band gives a centered 736px text measure 256px of vertical breathing room on each side. The 36px statement uses short lines, beginning in brown-charcoal and ending with darker text and a burnished-brown phrase.

**Transfer:** State one concise point of view about the new product's market or user problem. Keep it distinct from both hero display and long-form body copy.

**Text style:** `statement` — Pragmatica 400 · 36px/1.25 · tracking -0.034em

### Technical chapter

**Observed:** A heading pair leads a Ruled sheet: a large Isometric working model at left, Workflow trace at right, small marginal captions and supplementary underlined actions below. The chapter uses 128px top and 160px bottom padding on parchment; support aligns with the bottom of the headline.

**Transfer:** Explain an unfamiliar mechanism by mapping a few meaningful steps to one coherent drawing instead of an unrelated feature-card grid.

**Text style:** `heading` — Pragmatica Cond 400 · 64px/0.96 · tracking -0.046em

### Progression and compounding

**Observed:** A wide sans introduction and support line lead to three Process steps on near-white paper, separated from the heading by 56px. A continuous fine rule with dots and an ending arrow links their period figures. Below, a ruled split panel pairs a 48px editorial heading with the Compounding proof chart.

**Transfer:** Use the timeline for adoption stages, maturity or a transformation path. Put the cumulative payoff in a separate visual proof panel rather than adding another equal-weight step.

**Text style:** `heading-wide` — Pragmatica 400 · 64px/0.96 · tracking -0.046em

### Credibility ledger

**Observed:** A parchment band contains a 48px heading and three horizontally ruled logo rows. Tiny mono labels identify different kinds of affiliation; monochrome marks occupy the rest of each row. A shallow repeated vertical hatch strip adds a technical edge.

**Transfer:** Group relevant proof into named categories, keeping marks neutral and subordinate to the assertion. Recreate the shallow hatch using 1px vertical lines spaced 12px apart.

**Text style:** `heading-medium` — Pragmatica 400 · 48px/1 · tracking -0.042em

### Asymmetric voices

**Observed:** On near-white, a condensed heading introduces one featured Parchment proof card about 828px wide, leaving open space at right. Three 398px supporting Testimonial cards form the next row, with a 32px column gap and 48px row gap. Numbering connects the cards as an ordered set.

**Transfer:** Let the strongest substantiated voice occupy more space; do not equalize every quote. Keep the human attribution visually technical.

**Text style:** `heading` — Pragmatica Cond 400 · 64px/0.96 · tracking -0.046em

### Light conversion

**Observed:** The Ivory conversion band holds a left-aligned 64px condensed headline, 18px supporting sentence and a dark rectangular action paired with an underlined process link. The text-and-action stack leaves substantial open space on the right.

**Transfer:** Ask for one concrete next step and offer a lower-commitment explanatory route beside it.

**Text style:** `heading` — Pragmatica Cond 400 · 64px/0.96 · tracking -0.046em

### Illuminated ending

**Observed:** An 831px Night glow footer begins with the centered Emblem shrine, then a 32px two-line invitation and proof-caption with one amber figure. A horizontal rule introduces a metadata row: location left, paired Outline pills center and establishment note right. Footer directory follows, then a ruled social row and centered legal text at the very bottom. The same construction ends both page types.

**Transfer:** Preserve the complete closing device with the new brand's emblem, narrow invitation and truthful short proof phrase; adapt directory categories and metadata to the product.

**Text style:** `footer-invitation` — Pragmatica Cond 400 · 32px/1.04 · tracking -0.02em · uppercase

### Recruiting ledger

**Only for:** recruiting pages

**Observed:** A near-white 750px section uses 100px vertical padding. A small centered uppercase section label sits above a broad ruled list with 124px of breathing room before its top rule. Six 65px Vacancy rows use left numbered capsules and centered titles, followed immediately by the shared Illuminated ending.

**Transfer:** Use this restrained list for positions or other editorial opportunities; let titles do the work instead of descriptive cards.

**Text style:** `role-title` — Pragmatica 400 · 16px/1 · uppercase

## Page flow

**Storyline:** Atmospheric promise → clear point of view → mechanism and progression → credibility → direct invitation → illuminated brand ending.

### Explain a complex offering and turn curiosity into a conversation

1. **Promise** — Dark cinematic stage with centered display, emblem, support and one filled action.
2. **Point of view** — A short centered statement creates a deliberate pause on light paper.
3. **Mechanism** — Ruled isometric system sheet with numbered explanatory trace.
4. **Adoption path** — Illustrated progression with period figures and a compounding-value comparison.
5. **Credibility** — Categorized monochrome affiliations, then asymmetrically scaled numbered quotes.
6. **Closing call** — Sparse ivory invitation with two action levels, followed by the full glowing footer.

**Transfer:** Choose the explanatory and proof blocks that establish confidence for the new product; preserve atmosphere, engineering imagery and the branded ending without treating the section sequence as fixed.

### Make a focused recruiting promise and expose available opportunities

1. **Promise** — Black centered recruiting introduction with expressive small typographic motif and outline route to positions.
2. **Opportunity list** — Wide near-white ledger of centered titles and numbered capsules.
3. **Closing call** — The same illuminated emblem, invitation, utility pills and directory ending.

**Transfer:** Keep this shorter page type austere and action-oriented rather than importing the full commercial explanation.

## Writing

Confident and operational, with an ambitious opening followed by concrete descriptions of work. The tone is direct and human rather than exuberant; credibility comes from named outcomes and concise partner testimony.

**Do not copy:** Do not reuse the Ciridae name, emblem, customer or investor marks, partner names, quotes, establishment date, delivery timelines, business claims or branded product names. Replace them with the new product's own assets and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we or our when describing the people delivering the service. Refer to the product by name only where it clarifies the mechanism.
- **Rhythm:** Short sentence-case headings and fragments alternate with one- or two-sentence support paragraphs. Hero and utility capitalization is typographic, not a reason to shout in body copy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | An imperative or direct promise that connects the product to a larger possibility. | 7–12 words | “Build the business AI makes possible.” |
| Section heading | Plain nouns and short declarative clauses; paired fragments can sharpen the relationship. | 4–8 words | “Your business. One operating system.”<br>“The value compounds.” |
| Supporting line | Name the actual unit of work, who participates and what happens. | 10–24 words | “One workflow. Your data. Our engineers on site, building with your team.” |
| Primary action | A direct human conversation or a specific view action. | 2–4 words | “Talk to our team”<br>“See open roles” |
| Process outcome | A concrete deliverable qualified by ownership or readiness. | 4–7 words | “A prototype on your data.”<br>“A working, integrated workflow.” |
| Recruiting promise | Speak to the candidate's contribution and tangible real-world impact. | 8–14 words | “Your code runs a real company in three months.” |

**Words and phrasing to use:** your team; work; build; connected; in daily use; start with; one; foundation; working

**Avoid:** revolutionize everything; magic; game-changing; seamless synergy; unlimited possibilities; exclamation-heavy hype

**Rules:**

- Make the headline ambitious, then explain it with an observable action or artifact.
- Use technical words only when they clarify how the offering works.
- Use timelines and numerical proof only when substantiated for the new product.
- Let quoted customers carry colorful analogies; keep the surrounding editorial voice plain.
- Keep labels terse enough to function like equipment markings.

## Do's and Don'ts

### Do

- Keep the hero at 104px condensed regular with 0.88 leading and two deliberate lines.
- Use 64px condensed section leads and 64px wider grotesk only for the editorial variant.
- Retain 128px/160px major section padding and 32px internal stacks on desktop.
- Set cards flat with 1px warm-black 22% rules and square corners.
- Pair tiny 11px technical captions with large open isometric drawings.
- Reserve rust for the compact primary action and selected proof or diagram marks.
- Give the featured quote 48px padding and the smaller cards 32px.
- Carry the radial charcoal ending through to the final centered social and legal rows.

### Don't

- Do not use semibold to manufacture hierarchy; the core type scale stays at weight 400.
- Do not turn technical panels into shadowed, rounded SaaS cards.
- Do not fill the light middle of the page with rust or unrelated saturated accents.
- Do not replace the monospaced utility labels with ordinary body sans.
- Do not give every testimonial identical scale; retain the 64px versus 28px contrast.
- Do not make the utility pills the default commercial hero button; filled commercial actions have square corners.
- Do not build a neon rainbow footer; its glow stays between #272a2a and #0b0b0b.
- Do not over-polish the diagrams into glossy 3D; their 1px linework and paper backing are essential.

## Motion and responsive

### Motion

**Observed:**

- Declared link transitions use 0.14s transform and 0.2s color with cubic-bezier(.23,1,.32,1). Underlined actions also transition border-bottom-color at 0.2s.
- Process steps declare a 0.52s ease-out entrance.
- Two long linear infinite diagram lanes declare 64s and 78s durations.
- Recruiting list surfaces declare 0.4s background and color transitions with cubic-bezier(.76,0,.24,1).

**Transfer:**

- Keep small action presses compact at 0.97 scale and navigation/link presses at 0.96 where those states apply.
- Use slow ambient movement for the atmospheric opening and technical lanes, keeping crisp text stationary.

**Unknown:**

- Exact hero video timing, scroll choreography and the full recruiting graphic animation are not specified.

### Responsive

**Observed:**

- The footer invitation uses clamp(1.375rem, 3.2vw, 2rem). Desktop compositions use wide multi-column technical sheets and centered action rows.

**Transfer:**

- On narrow screens, stack each technical diagram before its trace and keep captions attached to the corresponding drawing.
- Convert the continuous horizontal process into a vertical progression while retaining period figures, thin rules and marker dots.
- Preserve the contrast between atmospheric opening and paper explanation; reduce headline scale to maintain intentional line breaks rather than shrinking the entire page.
- Stack footer metadata and directory groups while leaving the emblem and invitation centered.

**Unknown:**

- No verified mobile layouts or breakpoint widths are available; narrow-screen arrangements above are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
