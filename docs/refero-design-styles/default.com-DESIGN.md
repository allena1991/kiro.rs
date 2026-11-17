# Default — systems in low light

## Overview

A near-black software marketing style with pale grotesk typography, smoked panels and restrained operational color. Expansive introductions give way to tightly packed interface demonstrations and testimonial mosaics. Faint structural rails, softly fading product scenes and a monumental dot-matrix sign-off give technical products a composed, tactile presence.

### Essentials

- Headlines feel like a softly illuminated sentence rather than a slogan in bold: Inter 400, 64px/0.94, -0.02em tracking, with white-to-70%-white gradient lettering.
- The opening separates promise from explanation: a roughly 644px two-line headline on the left, a 368px support-and-action column on the right, then subdued customer marks and a 1248px-wide working-product stage.
- Conversion controls are small bright keys, not oversized pills: #f2f2f2 fill, #333333 text, 10px corners, 8px 16px padding and 13px medium text; navigation actions remain smoked and dark.
- Nearly the entire page stays charcoal: #0b0c0e canvas, #0e0f11 panels, #121315 proof cards, 1px subdued rules. Green, blue and coral are confined to small workflow statuses, application details and 24px category icons, never broad marketing bands.
- Product imagery lives in the same darkness as the page: dark interfaces, fine edges, small layered windows and bottom-edge fades. Include a concrete interface scene; when no finished interface exists, construct a focused workflow with a few legible cards rather than substituting generic stock art.
- The ending has architectural weight: a double-rimmed 20px-radius conversion enclosure with a muted warm-gray floor glow, followed by a giant pale dot-matrix word sculpture cut by the bottom edge. Recreate the sculpture using the new identity or a short product word; both glow and dotted lettering are signature devices.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Category blue | `#0ea5e9` | `--color-blue` | accent | 24px category icon backgrounds. |
| Category mint | `#10b981` | `--color-mint` | accent | 24px category icon backgrounds. |
| Category coral | `#f87171` | `--color-coral` | accent | Small category icon backgrounds and workflow status details; keep confined to icon-sized areas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bright key | `#f2f2f2` | `--color-action` | action, surface | Primary action fill. |
| Stage black | `#0a0a0a` | `--color-stage` | surface | Dotted workflow stage. |
| Near-black canvas | `#0b0c0e` | `--color-canvas` | background | Continuous page ground. |
| Smoked panel | `#0e0f11` | `--color-panel` | surface | Feature cards and compact navigation tiles. |
| Proof charcoal | `#121315` | `--color-proof` | surface | Testimonial cards. |
| Smoked control | `#161719` | `--color-glass` | surface | Visible approximately 4.5% white over the canvas for header actions and documentation chips. |
| Fine panel edge | `#1a1b1c` | `--color-fine-edge` | border | Visible 6% white edge over the canvas; implement as rgba(255,255,255,0.06). |
| Tile edge | `#1b1b1d` | `--color-tile-edge` | border | Subtle compact tile outline. |
| Structural rule | `#1f1f21` | `--color-rule` | border | Section dividers, frame rails and proof-card borders. |
| Chip edge | `#212224` | `--color-chip-edge` | border | Visible 9% white edge over the canvas for small chips. |
| Lit rim | `#28292b` | `--color-rim` | border | Visible 12% white rim over the canvas for feature and conversion frames. |
| Key lettering | `#333333` | `--color-action-ink` | text | Text on bright actions. |
| Muted gray | `#71717a` | `--color-muted` | text | Tiny resource labels and secondary section labels. |
| Support gray | `#a4a5a6` | `--color-support` | text | Supporting text and navigation, rendered as 62.9% white over the canvas. |
| Pale foreground | `#e6e6e6` | `--color-foreground` | text | Main text, rendered as 89.8% white over dark ground. |
| Light source | `#ffffff` | `--color-white` | text, accent | Gradient headline start, small white icons and dot lettering; reduce alpha for tonal hierarchy. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Operational green | `#4ade80` | `--color-green` | accent | Small successful workflow statuses; no large marketing fills. |

## Typography

- **Inter** — All marketing headings, paragraphs, navigation and labels. Neutral grotesk with a high x-height; regular display weights and subtly tightened text. Font stack: "Inter", "Inter Fallback", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 400 | 64px | 0.94 | -0.02em | fixed | Opening headline and the centered major capability introduction. |
| closing-heading | Inter | 400 | 52px | 1 | -0.02em | fixed | Centered closing promise within the illuminated enclosure. |
| quote-feature | Inter | 400 | 32px | 1.18 | normal | fixed | Large portrait-led testimonial cards. |
| card-heading | Inter | 500 | 20px | 1.3 | normal | fixed | Large illustrated capability cards. |
| tile-heading | Inter | 500 | 20px | 1.2 | normal | fixed | Compact linked outcome tiles. |
| quote | Inter | 400 | 20px | 1.5 | -0.01em | fixed | Standard testimonial cards. |
| body | Inter | 500 | 16px | 22px | -0.02em | fixed | Opening support and short section descriptions. |
| eyebrow | Inter | 500 | 14px | 18px | -0.023em | fixed | Sentence-case introductory labels and feature categories. |
| nav | Inter | 400 | 14px | 20px | -0.023em | fixed | Navigation links. |
| nav-action | Inter | 500 | 14px | 20px | -0.023em | fixed | Header conversion action. |
| attribution | Inter | 450 | 13px | 20px | normal, features "ss01", "ss03" | fixed | Secondary role and organization line beneath a testimonial name. |
| button | Inter | 500 | 13px | 1.5 | normal | fixed | Default bright action in the opening. |
| closing-button | Inter | 500 | 13px | 18px | -0.015em | fixed | Compact action in the closing enclosure. |
| footer | Inter | 400 | 12.5px | 18px | -0.026em | fixed | Footer columns and utility links. |
| chip | Inter | 500 | 11.5px | 1.05 | -0.028em | fixed | Case-study and documentation chips. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| product-detail chapters | product-heading | Inter | 400 | 52px | 1 | -0.025em | size clamp(2rem, 4vw, 3.25rem) | Left-aligned chapter headings above wide interface scenes. |
| product-detail supporting sections | secondary-heading | Inter | 400 | 44px | 1.05 | -0.0205em | size clamp(2rem, 3.6vw, 2.75rem) | Infrastructure and FAQ section headings. |
| product-detail testimonial interludes | quote-standalone | Inter | 400 | 42px | 1.2 | -0.0214em | fixed | Single centered quotation without a card. |
| product-detail cards | product-card-heading | Inter | 500 | 20px | 1.4 | normal | fixed | Titles under small icon wells. |
| FAQ sections | faq-question | Inter | 500 | 18px | 28px | -0.018em | fixed | Accordion question text. |
| product-detail cards | product-card-body | Inter | 400 | 16px | 22px | -0.02em | fixed | Lower-contrast explanatory copy. |
| FAQ sections | faq-answer | Inter | 400 | 15px | 1.8 | -0.021em | fixed | Explanatory accordion answers. |
| product-detail actions | secondary-button | Inter | 500 | 13px | 18px | -0.015em | fixed | Documentation button accompanying the primary action. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep display lettering regular rather than bold. Negative tracking is part of the compact, sentence-like silhouette.
- Headline gradients run from white to 70% white. Use background-clip:text, with enough vertical padding to preserve glyph extents.
- Body copy is unusually compact at 16px/22px. Distinguish support from headings through alpha rather than adding another type family.
- For the closing support line use the body geometry at weight 480 and 70% white. Testimonial names use 16px/22px at weight 440; the attribution recipe is the smaller second line.

## Layout

**Density:** Airy between narrative blocks, tightly assembled within demonstrations and card grids.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Capability grid gutters and inner demonstration frame inset. |
| 8px | Action gaps and testimonial mosaic gutters. |
| 10px | Feature category-to-title and card title-to-body gaps. |
| 16px | Compact tile padding and content gap. |
| 20px | Product chapter heading-to-support gap. |
| 24px | Standard testimonial padding and opening support-to-action gap. |
| 32px | Large card padding and internal feature group separation. |
| 48px | Inner horizontal inset within the framed content shell. |
| 50.4px | Half-section inset around the conversion enclosure and secondary chapter heading top padding. |
| 64px | Footer top padding and generous grouped-content separation. |
| 96px | Opening top space beneath navigation and end padding for the tile index. |
| 100.8px | Product chapter and standalone testimonial vertical rhythm. |
| 128px | Major capability introduction top padding. |

### Containers and grids

- **content shell**: max width 1240px. Centered frame for navigation, card grids, proof and footer; at 1440px it leaves 100px margins. Faint vertical rails align sections.
- **opening shell**: max width 1248px · 2 columns · gap 40px. Asymmetric headline-and-support layout; headline width up to 644px, support width 368px, aligned toward the bottom.
- **capability grid**: 2 columns · gap 6px. Two wide illustrated cards above a row of three narrower cards; preserve the tight joined-panel appearance.
- **outcome grid**: 4 columns · gap 6px. Compact linked outcome index, typically two rows.
- **proof mosaic**: gap 8px. Mixed-width testimonial rows: portrait-led wide card beside a narrow quote, three equal cards in the middle, then a reversed wide composition.
- **product chapter** (only for product-detail chapters): max width 1240px · side padding 48px. Heading block constrained to 616px including inset; media expands to 1228px and detail cards span two or three columns.
- **faq column** (only for FAQ sections): max width 760px · side padding 48px. Centered wrapper yielding a 664px question column at desktop.

## Corner radius

| Element | Radius |
| --- | --- |
| actions and chips | 10px |
| proof and detail cards | 12px |
| capability cards and tiles | 16px |
| conversion outer frame | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| bright key | `0px 1px 4px 0px rgba(0,0,0,0.1), 0px 0px 1px 0px rgba(0,0,0,0.1)` | Small contact shadow on primary buttons. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous marketing ground.

**CSS:** `background: #0b0c0e; color: #e6e6e6`

**Observed:** Horizontal section boundaries and vertical shell rails use structural rule.

**Transfer:** Maintain a continuous dark field across narrative changes.

#### Smoked capability · level 1

**Use:** Illustrated feature cards.

**CSS:** `background: linear-gradient(180deg, rgba(112,103,103,0) 35%, rgba(112,103,103,0.08) 70%, rgba(82,74,82,0.08) 100%), #0e0f11; border: 1px solid rgba(255,255,255,0.12); border-radius: 16px; overflow: clip`

**Observed:** Near-neutral warm-gray sheen is concentrated low in each card. Most of the area remains black, with UI objects floating inside.

**Transfer:** Match the soft low-intensity sheen; exact gradient stops are not essential.

#### Proof card · level 1

**Use:** Customer statements.

**CSS:** `background: #121315; border: 1px solid #1f1f21; border-radius: 12px`

**Observed:** Flat charcoal rather than a luminous glass effect.

**Transfer:** Use for documentary proof with restrained portrait treatment.

#### Workflow stage · level 1

**Use:** Large opening demonstration.

**CSS:** `background: radial-gradient(circle, rgba(255,255,255,0.06) 0.7px, rgba(0,0,0,0) 0.9px), #0a0a0a; border: 1px solid rgba(255,255,255,0.06); border-radius: 16px 16px 0px 0px`

**Observed:** Fine low-contrast dot field behind connected panels, with top and bottom masks blending into the stage.

**Transfer:** Use a fine repeated grid as a backing, not a prominent decorative pattern.

#### Conversion enclosure · level 1

**Use:** Closing action stage.

**CSS:** `border: 1px solid rgba(255,255,255,0.12); border-radius: 20px; padding: 6px; backdrop-filter: blur(27px); overflow: clip`

**Observed:** An inset 16px-radius inner panel creates a double rim. A muted gray-mauve gradient rises from the lower half, behind centered text.

**Transfer:** Retain the double edge and low floor glow rather than turning the panel into a bright colored banner.

#### Detail card · level 1

**Only for:** product-detail chapters

**Use:** Icon-led capability explanations and supporting illustrated cards.

**CSS:** `background: #0e0f11; border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; padding: 32px`

**Observed:** Two- or three-column rows sit directly under an expansive media stage.

**Transfer:** Group precise supporting capabilities beneath a demonstrated result.

## Components

### Navigation

**Use:** Persistent orientation at the top of the page.

**CSS:** `height: 72px; background: #0b0c0e; border-bottom: 1px solid #1f1f21; position: sticky; top: 0px`

**Text style:** `nav` — Inter 400 · 14px/20px · tracking -0.023em

**Observed:** Logo left, centered short link cluster with 12px chevrons on menu items, login and smoked conversion key right. Link gap is 20.9px.

**States:** Declared: hover link color becomes rgba(255,255,255,0.898).

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #f2f2f2; color: #333333; border: 1px solid rgba(255,255,255,0.2); border-radius: 10px; padding: 8px 16px; height: 38px; box-shadow: 0px 1px 4px 0px rgba(0,0,0,0.1), 0px 0px 1px 0px rgba(0,0,0,0.1)`

**Text style:** `button` — Inter 500 · 13px/1.5

**Observed:** A compact text-only bright key. The closing variant is 36px high and uses closing-button typography.

**States:** Declared: hover filter brightness(1.06); focus-visible unspecified; active transform scale(0.97).

### Header action

**Use:** Low-emphasis conversion access in navigation.

**CSS:** `background: rgba(255,255,255,0.044902); color: #e6e6e6; border: 1px solid transparent; border-radius: 10px; padding: 8px 16px; height: 38px; backdrop-filter: blur(6px)`

**Text style:** `nav-action` — Inter 500 · 14px/20px · tracking -0.023em

**Observed:** Sits beside the unfilled login link, not as a bright competing action.

**States:** Declared: hover background-color color-mix(in oklab, #ffffffe5 8%, transparent); focus-visible unspecified; active transform scale(0.97).

### Capability card

**Use:** Explain a major outcome through a miniature working scene.

**CSS:** `border: 1px solid rgba(255,255,255,0.12); border-radius: 16px; overflow: clip; display: flex; flex-direction: column`

**Text style:** `card-heading` — Inter 500 · 20px/1.3

**Observed:** Uses Smoked capability. Category label sits above a short title in a 32px-padded header; a small square diagonal-arrow control occupies the upper right. Lower space is dominated by dark interface art. Desktop height is 497px.

**Transfer:** Demonstrate one recognizable input-to-result action per card rather than listing features.

### Outcome tile

**Use:** Compact linked index of practical results.

**CSS:** `background: #0e0f11; border: 1px solid #1b1b1d; border-radius: 16px; padding: 16px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `tile-heading` — Inter 500 · 20px/1.2

**Observed:** A 24px colored app-like icon above a short title; a right arrow follows the phrase. Tiles are 306px wide by 123px at desktop.

**States:** Declared: hover background-color rgb(19,20,22); focus-visible unspecified; active transform scale(0.992).

**Transfer:** Use outcome language and small category colors, retaining the four-column density.

### Testimonial card

**Use:** Human proof in an assembled mosaic.

**CSS:** `background: #121315; border: 1px solid #1f1f21; border-radius: 12px; padding: 24px; display: flex; flex-direction: column`

**Text style:** `quote` — Inter 400 · 20px/1.5 · tracking -0.01em

**Observed:** Quote at top; name, role and small circular portrait anchored low; Case study chip floats top right. Featured variants place a grayscale portrait in a 249px-wide left panel and use quote-feature text with a dimmer concluding phrase.

**Transfer:** Alternate portrait-led anchors with smaller text-only statements.

### Resource chip

**Use:** Quiet path to deeper proof or documentation.

**CSS:** `background: rgba(255,255,255,0.044902); color: #71717a; border: 1px solid rgba(255,255,255,0.0898039); border-radius: 10px; padding: 4px 8px 4px 10px; height: 22px; display: inline-flex; gap: 4px`

**Text style:** `chip` — Inter 500 · 11.5px/1.05 · tracking -0.028em

**Observed:** Tiny diagonal arrow trails the label; usually pinned to a card's upper-right corner. Case-study chips share the geometry.

**States:** Declared: hover border and background increase to 20% and 10% of foreground with foreground text; focus-visible solid 2px outline at 2px offset with 60% foreground color; active scale(0.97).

### Footer columns

**Use:** Dense but subdued navigation and trust information.

**CSS:** `display: flex; gap: 56px`

**Text style:** `footer` — Inter 400 · 12.5px/18px · tracking -0.026em

**Observed:** Five narrow link columns to the right of a wider identity column. Links stack with 8px gaps and sit below small muted column labels; link groups have 0.7 opacity. Identity includes a short descriptor, AI-summary links and a compact certification medallion. A rule separates lower utilities and social icons.

**Transfer:** Use relevant resource categories and genuine trust signals; retain the giant dotted identity artwork beneath the utilities.

### Secondary button

**Only for:** product-detail actions

**Use:** Documentation next to conversion.

**CSS:** `background: rgba(255,255,255,0.05); color: #ffffff; border: 1px solid transparent; border-radius: 10px; padding: 8px 16px; height: 36px; backdrop-filter: blur(6px)`

**Text style:** `secondary-button` — Inter 500 · 13px/18px · tracking -0.015em

**Observed:** Small diagonal arrow follows the text, with a 4px gap. Paired actions are separated by 8px.

**States:** Declared: hover unspecified; focus-visible unspecified; active transform scale(0.97).

### FAQ row

**Only for:** FAQ sections

**Use:** Resolve practical purchase questions.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 20px 0px; width: 100%`

**Text style:** `faq-question` — Inter 500 · 18px/28px · tracking -0.018em

**Observed:** Full-width button above the answer; 20px outline chevron at right. Thin structural rules separate rows; first answer is expanded. Use faq-answer below with 24px bottom padding.

**States:** Declared: hover text becomes rgba(255,255,255,0.898).

## Imagery and graphics

### Working interface scenes

**Use:** Opening stage and recurring feature demonstrations.

**Observed:** Charcoal workflow nodes, scheduling windows, tables and editing menus rendered front-on or with very mild spatial offset. Fine borders and small application colors punctuate mostly black imagery. Wide product-detail scenes fill 1228px by 559px and dissolve into the page near their lower and side edges.

**Transfer:** Show a real task and its result in a dark interface. Minimum acceptable version is a hand-built set of three connected panels or a meaningful table with one active edit, not an empty browser frame.

**Build:** Place rounded dark UI panels over the Workflow stage; connect workflow nodes with fine dashed SVG paths. Limit saturated paint to status chips, cursors and active edges. Add a foreground linear-gradient from transparent to the canvas over the bottom portion; leave the important task controls above the fade.

### Soft floor light

**Use:** Opening atmosphere, feature panels and closing enclosure.

**Observed:** Low-saturation gray, mauve and slate light collects toward the bottom rather than forming bright neon halos. Closing treatment is stronger than the opening and remains behind typography.

**Transfer:** Preserve the sense of a dark object lit from beneath; tune alpha rather than introducing a vivid brand gradient.

**Build:** Inside an overflow-clipped panel, place an absolute lower-half layer with a vertical gradient from rgba(98,103,111,0) through rgba(112,103,103,0.4), rgba(106,91,92,0.4) to rgba(82,74,82,0.4). Keep the upper third transparent and place all text above it. For feature cards reduce these alphas to 0.08; for the opening use about 0.1.

### Dot-matrix identity sculpture

**Use:** Monumental sign-off below footer utilities.

**Observed:** A giant symbol and word rendered in tightly spaced pale circular dots. Dots brighten toward the lower strokes and fade into an ambient dot field above and beside the letters. The artwork exceeds the shell width and is intentionally cut by the page's bottom edge; its canvas is 1488px by 417px.

**Transfer:** Render the new brand name or a short meaningful product word at architectural scale. Keep it a graphic, not another readable footer heading.

**Build:** Draw the word in a bold sans mask on an offscreen canvas or SVG. Sample the mask on an approximately 6px grid, then draw small circles only where the mask is filled. Use white with variable alpha, dimming upward and toward outer edges. Add a much fainter unmasked dot grid, a 300px-high warm-neutral radial wash behind it and clip the lower part in the footer. Fit the word across nearly the full viewport; do not stretch individual letter proportions.

### Documentary portraits

**Use:** Testimonial mosaics.

**Observed:** Featured head-and-shoulders portraits are grayscale, tightly framed and backed by flat dark gray. Smaller quotes use tiny circular avatars. Photography is subordinate to the text, not a full-bleed lifestyle background.

**Transfer:** Use similarly close, neutral portraits with consistent grayscale treatment for featured proof.

### Floating support diagrams

**Only for:** product-detail supporting sections

**Use:** Illustrated capability cards beneath technical chapters.

**Observed:** Dark terminal and version-history windows tilt slightly counterclockwise; integration icons sit on individual black rounded keys; paired monochrome object icons overlap. All fade into the lower backing and occupy much more space than their short caption.

**Transfer:** Build a few relevant dark UI fragments with slight rotation and a bottom mask rather than glossy photorealistic 3D scenes.

**Build:** Layer two rounded dark panels, rotate approximately -10deg, add a thin pale rim at low alpha and place a transparent-to-canvas mask over the lower third. For integrations use a compact grid of rounded icon keys with subdued native colors.

### Icons

**Observed:** Navigation chevrons are 12px with 2px round strokes; resource arrows are 12px with 1.5px round strokes. FAQ chevrons are 20px with 2px round strokes. Compact outcome icons use white filled glyphs inside 24px colored squares with 6px corners; product-detail icons sit in 48px dark rounded wells.

**Transfer:** Use restrained Lucide-like outlines for controls and solid, app-like symbols for categories. Reserve color for the small category backing or meaningful product status.

## Section recipes

How recurring sections are built.

### First screen: Split promise and working stage

**Observed:** A 72px Navigation sits over a near-black opening with a very faint lower glow. After 96px of top space, display occupies the left half in two tightly stacked lines, up to 644px wide. A 368px body-and-Primary button column sits far right and aligns near the headline's lower edge. A low-contrast horizontal row of customer marks spans the shell underneath. The 1248px-wide Workflow stage begins around the middle of the first screen, with a small live indicator, connected workflow nodes and a larger scheduling window. Within the first 900px the headline, support, action, marks and most of the main object are visible; the demonstration's lower edge and replay control continue below.

**Transfer:** Use the same separation of a strong outcome sentence and a compact practical explanation. Construct a dark task scene if there is no finished interface. Product-detail openings use a muted eyebrow above the same display recipe, add a documentation action and move directly into a chapter after the marks rather than repeating a large hero stage.

**Avoid:** Do not center the opening into a generic SaaS stack or place a vivid abstract orb where the working product belongs. Do not let the demonstration obscure the headline or action.

**Text style:** `display` — Inter 400 · 64px/0.94 · tracking -0.02em

### Capability introduction and bento

**Observed:** A centered eyebrow introduces a two-line display headline after 128px top padding. A 64px separation leads into Capability cards: two broad panels above three narrower ones with 6px gutters. Lower illustrations remain dark and blend into their panels.

**Transfer:** Use the display introduction to state a broad operational change; distribute concrete capabilities into cards whose illustrations make that change believable.

**Text style:** `display` — Inter 400 · 64px/0.94 · tracking -0.02em

### Compact outcome index

**Observed:** Sentence-case eyebrow above a four-column, two-row Outcome tile grid. Grid gutters are 6px, tile padding 16px, and the enclosing block ends with 96px bottom padding.

**Transfer:** Offer quick routes into practical applications without adding another large heading.

### Proof mosaic

**Observed:** A ruled section contains an additional thin rectangular frame, 8px inset and 8px gutters. Testimonial cards vary in width while keeping aligned rows. Larger quotes combine grayscale portrait panels with 32px text; smaller cards use 20px quotes and low anchored attribution.

**Transfer:** Use size changes to emphasize the strongest statement without introducing accent-colored quote cards.

### Illuminated closing call

**Observed:** Conversion enclosure sits inside the 1240px shell with 50.4px outer inset. The enclosure is about 1139px wide and 482px tall. Centered closing-heading is constrained to 600px, support to 400px; body-to-action spacing is 52px. Soft floor light and nested edges give the section its emphasis, not larger controls.

**Transfer:** Restate the broad outcome in a short two-line sentence and give one clear conversion path.

**Text style:** `closing-heading` — Inter 400 · 52px/1 · tracking -0.02em

### Architectural footer

**Observed:** 64px top padding opens a rail-bounded footer. Identity and trust sit left, Footer columns right; a horizontal rule precedes utilities and social icons. The Dot-matrix identity sculpture grows below the copyright line and is cut by the bottom edge, over a faint radial wash.

**Transfer:** End with a complete resource structure and an oversized dotted word using the new identity. Keep the artwork subordinate to navigation contrast but monumental in area.

### Product demonstration chapter

**Only for:** product-detail chapters

**Observed:** Top rule and vertical shell rails frame a left-aligned product-heading with 100.8px top padding. Body follows after 20px; the 1228px-wide interface scene follows with approximately 56px separation. Two or three Detail cards fit underneath, separated by 6px gutters.

**Transfer:** Repeat the structure for distinct capabilities, varying the interface task rather than changing the entire visual language.

**Text style:** `product-heading` — Inter 400 · 52px/1 · tracking -0.025em

### Standalone testimony

**Only for:** product-detail testimonial interludes

**Observed:** A 940px-wide centered quotation uses quote-standalone, with 100.8px vertical section padding and a centered attribution group below. No painted card interrupts the continuous ground.

**Transfer:** Use one short, attributable statement as a breathing space between technical chapters.

**Text style:** `quote-standalone` — Inter 400 · 42px/1.2 · tracking -0.0214em

### Supporting system cards

**Only for:** product-detail supporting sections

**Observed:** Muted eyebrow and secondary-heading introduce a two-by-two grid of Detail cards. Floating support diagrams fill the upper area; short titles and 15px/22px descriptions sit low.

**Transfer:** Explain implementation, governance or connectivity with small concrete diagrams rather than extending the main feature chapters.

**Text style:** `secondary-heading` — Inter 400 · 44px/1.05 · tracking -0.0205em

### FAQ chapter

**Only for:** FAQ sections

**Observed:** Eyebrow and secondary-heading align with the shell's 48px inset. A narrower centered question column follows with generous separation. FAQ rows have thin rules, one expanded answer and small right-aligned chevrons.

**Transfer:** Answer precise evaluation questions in compact paragraphs; keep the section visually open rather than boxed into cards.

**Text style:** `secondary-heading` — Inter 400 · 44px/1.05 · tracking -0.0205em

## Page flow

**Storyline:** Outcome promise → working-product proof → capability explanation → human validation → practical evaluation → renewed action → architectural identity sign-off.

### Broad platform marketing and discovery

1. **Promise** — Split display headline and support/action column, subdued marks and a large connected-interface stage.
2. **Capability chapters** — Centered display introduction followed by tightly joined illustrated capability cards.
3. **Application discovery** — Small colored-icon outcome tiles create a quick navigation index.
4. **Social proof** — Mixed-width testimonial mosaic combines grayscale portrait anchors and smaller quotes.
5. **Closing call** — Double-rimmed illuminated enclosure with centered promise and bright action.
6. **Resource navigation and identity** — Dense footer columns and utilities above monumental dot-matrix lettering.

**Transfer:** Lead with a broad operational outcome and show it working; adapt the depth and placement of proof to the new product without losing the working scene and architectural finish.

### Explain a specific product through repeatable task demonstrations

1. **Promise** — Small category eyebrow, split display heading, conversion and documentation actions, then quiet customer marks.
2. **Product demonstration** — Repeated ruled chapters with left-aligned headings, broad interface scenes and two- or three-card explanatory rows.
3. **Social proof** — One large centered customer quotation.
4. **Supporting capabilities** — Two-by-two grid of floating technical illustrations with short captions.
5. **Objection handling** — Narrow FAQ accordion under a full-width heading band.
6. **Closing call** — Shared illuminated enclosure.
7. **Resource navigation and identity** — Shared footer and giant dotted word sculpture.

**Transfer:** Use this more explicit chapter structure when the visitor needs to understand specific tasks, supporting systems and evaluation details.

## Writing

Confident and operational, with little theatrical language. It presents a broad promise in the headline, then earns it with specific actions, objects and mechanisms.

**Do not copy:** Do not reuse Default's name, logo, customer marks, proprietary interface artwork, customer identities, quotations, certification claims or product performance claims. Source copy examples illustrate voice only.

- **Addressing the reader:** Use you and your team for benefits; describe the product directly for mechanisms. Customer proof speaks in the first person.
- **Rhythm:** Short sentence-case headings, one-sentence support lines and direct verb-led card titles. Longer explanatory sentences belong in technical descriptions and FAQ answers, not the opening.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A broad operational role or a concrete unified outcome, usually without punctuation. | 7–11 words | “The inbound engine behind the best teams”<br>“Every go-to-market record in one live table” |
| Supporting line | Explain scope using concrete verbs and recognizable work objects. | 13–18 words | “One platform to manage workflows, enrich records, route leads, and schedule meetings.”<br>“Build and enrich views of CRM accounts, marketing contacts, or email lists.” |
| Capability title | Verb plus a specific change or result, or a compact capability noun. | 2–7 words | “Turn demo requests into pipeline”<br>“Create views of your data layer” |
| Primary action | Plain, explicit next step with no promotional flourish. | 3–4 words | “Request a Demo”<br>“Read the docs” |
| Technical explanation | Explain what happens and when, with a concrete mechanism or safeguard. | 12–20 words | “Every agent write is logged with full attribution and a rollback path.” |

**Words and phrasing to use:** one platform; live; every; in one place; build; manage; route; run; records; views; logged; reversible

**Avoid:** revolutionary; magical; supercharge; game-changing; unleash; limitless possibilities

**Rules:**

- Write broad promises as outcomes, then use practical verbs and concrete nouns in the support.
- Name the task before the mechanism in card titles; put implementation detail in the description.
- Keep labels in sentence case except conventional action title case and proper names.
- Use customer language for emotional emphasis; keep the product's own voice matter-of-fact.

## Do's and Don'ts

### Do

- Keep hero typography at Inter 400, 64px/0.94 with -0.02em tracking.
- Use a 1240px centered structural shell and align thin section rules to it.
- Keep illustrated card gutters at 6px and proof mosaic gutters at 8px.
- Give bright actions 10px corners and 8px 16px padding.
- Use a 32px-padded header inside larger capability panels.
- Reserve 24px colored squares for category accents against the dark field.
- Keep the closing promise constrained to 600px within its nested enclosure.
- Build the dotted identity artwork as pale circles against the continuous dark ground.

### Don't

- Do not replace regular display lettering with 600–700 weight headings.
- Do not turn the neutral 12% rims into bright white outlines around every panel.
- Do not enlarge all conversion controls into 48–56px capsule buttons.
- Do not apply the 52px product chapter recipe to every card title; card titles remain 20px.
- Do not spread green status color across marketing headlines or full section backgrounds.
- Do not give testimonial cards the same glowing gradient as the closing enclosure.
- Do not make footer resources compete with the main heading scale; their recipe is 12.5px/18px.
- Do not flatten interface scenes into bright white browser mockups; their backing remains near-black.

## Motion and responsive

### Motion

**Observed:**

- Declared: primary action filter transition 0.15s ease-out and transform transition 0.15s; press scale is 0.97.
- Declared: card reveals use opacity and transform over 0.7s with cubic-bezier(0.22,1,0.36,1).
- Declared: marquee 30s linear infinite; workflow steps 6s ease-in-out infinite; workflow pulse 2.4s ease-out infinite.
- Declared: FAQ grid-row expansion uses 0.2s; navigation colors use 0.15s with cubic-bezier(0.4,0,0.2,1).

**Transfer:**

- Keep movement concentrated in working product scenes and restrained entry reveals; typography and structural rails remain visually stable.
- Preserve smaller press feedback on outcome tiles at scale(0.992), distinct from button scale(0.97).

**Unknown:**

- Exact playback order, reveal thresholds and all intermediate diagram states are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 640px, 768px, 880px, 896px, 900px, 1024px, 1280px and 1536px.
- Capability grids declare one column before the medium-width two-column layout; outcome tiles declare two columns before the four-column wide layout.
- Featured quote text declares 24px before the 32px desktop variant; compact tile text declares 15px/19px before 20px/24px.
- Closing heading declares 36px before its 52px desktop variant. Product chapter and secondary heading sizes use their clamp formulas.

**Transfer:**

- Stack the opening support beneath the promise while retaining a full-width dark task stage.
- Keep the dotted word proportional and edge-clipped at narrow widths rather than shrinking it into ordinary footer text.
- Allow mosaic rows to stack while retaining the distinction between large portrait proof and smaller quote cards.

**Unknown:**

- Rendered mobile navigation behavior and exact media composition at narrow widths are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
