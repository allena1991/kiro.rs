# Lama Lama — full throttle halftone

## Overview

An outspoken, art-directed style with a cinematic dark canvas, warm cream lettering and a deliberately tiny technical countervoice. Dense grotesk headlines sit against tactile moving imagery, while editorial paragraphs and ruled project indexes leave wide areas of breathing room. It suits ambitious products, creative tools and service-led launches; a cream-and-black variant brings the same attitude to explanatory pages.

### Essentials

- Headlines hit like compressed declarations: bold uppercase grotesk at 72px/0.8 with -0.02em tracking in the opening, 80px/0.8 for major section and closing lines.
- The first impression is a film, not a centered sales card: a 1440×900 atmospheric stage, a three-line headline across seven grid columns at lower left, and 20px support copy across three columns at lower right.
- Technical furniture stays miniature and squared: uppercase 10px/18px mono labels, bracketed captions, 50px action heights, 4px corners and small diagonal arrows rather than pill buttons.
- Color lives inside the work: most page furniture remains charcoal #1a1c1c and cream #f9f4eb; vivid color occupies bounded photographs and project imagery, not recurring decorative UI fills.
- Proof behaves like an editorial index: 168px ruled rows, names and small tags on the left, 120px-high image strips on the right with 8px gaps, rather than a conventional card deck.
- A halftone atmosphere and a monumental sign-off are signature devices: convert photographic forms into low-contrast dot fields behind a chapter, then give an 80px/0.8 two-line closing invitation its own spacious stage. Without film or photography, use an original abstract material study and its halftone derivative.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#f9f4eb` | `--color-text` | text, action, surface | Default lettering and filled actions; also the inverse canvas on explanatory pages. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-black` | surface, text | Dark floating navigation layer, tags and portrait contact chips; navigation uses 60% opacity. |
| Charcoal canvas | `#1a1c1c` | `--color-canvas` | background | Default marketing canvas, also the dark base beneath moving imagery. |
| Cream hairline on charcoal | `#474745` | `--color-dark-rule` | border | Visible result of cream at 20% over charcoal; used for index rules and outline buttons. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Clock signal | `#ff0000` | `--color-status` | accent | A 4px status dot within the tiny bracketed clock; not a broad brand accent. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light service and capability pages | Near-black ink | `#010101` | `--color-ink` | text, action, border | Lettering and inverse actions on cream. |
| light service and capability pages | Ink hairline on cream | `#c7c3bc` | `--color-light-rule` | border | Visible result of near-black at 20% over cream. |
| light service and capability pages | Faint ink edge on cream | `#e0dcd4` | `--color-light-faint` | border | Visible result of near-black at 10% over cream; testimonial outline and compact metric dividers. |
| light service and capability pages | White inserts | `#ffffff` | `--color-white` | surface, text, action | Tags, contact chips and small filled actions on cream. |

## Typography

- **SuisseBPIntl** — All readable headings, paragraphs, project names and menu links. Neutral Swiss grotesk: muscular bold capitals against economical regular text, consistently tight spacing. If unavailable, use **Inter**. Use 400 and 700; preserve tight tracking and compressed display leading. Font stack: "SuisseBPIntl", "Inter", Helvetica, Arial, sans-serif.
- **Sometype** — Eyebrows, buttons, tags, utility captions and clock numerals. Small monospaced lettering with a mechanical, understated feel. If unavailable, use **Sometype Mono**. Use 500 for labels and actions. Font stack: "Sometype", "Sometype Mono", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | SuisseBPIntl | 700 | 80px | 0.8 | -0.02em, uppercase | fixed | Chapter headlines, case titles and closing invitation. |
| hero | SuisseBPIntl | 700 | 72px | 0.8 | -0.02em, uppercase | size clamp(4.5rem, 2.25rem + 2.5vw, 6.75rem) | Default opening statement, broken into a compact block. |
| editorial-lead | SuisseBPIntl | 400 | 48px | 0.9 | -0.02em | size clamp(3rem, 1.5rem + 1.67vw, 4.5rem) | Long editorial statements; first line can indent by one grid column. |
| editorial-secondary | SuisseBPIntl | 400 | 40px | 1 | -0.02em | fixed | Narrower story paragraphs paired with tall photography. |
| capability-lead | SuisseBPIntl | 400 | 32px | 1 | -0.02em | fixed | Multi-line capability statement below the chapter heading. |
| body | SuisseBPIntl | 400 | 20px | 1.2 | -0.02em | size clamp(1.25rem, 0.9375rem + 0.35vw, 1.5625rem) | Hero supporting paragraph, chapter support and closing reassurance. |
| body-small | SuisseBPIntl | 400 | 16px | 1.4 | -0.02em | size clamp(1rem, 0.856875rem + 0.16vw, 1.14313rem) | Detailed explanatory text, case summary and capability lists. |
| navigation | SuisseBPIntl | 400 | 16px | 1.4 | -0.02em | fixed | Expanded navigation entries. |
| label | Sometype | 500 | 10px | 18px | -0.02em, uppercase | fixed | Bracketed labels, metadata, button copy, tags and compact numerical proof. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| process chapters | process-number | SuisseBPIntl | 700 | 70.1px | 0.8 | normal, uppercase | fixed | Two-digit ordinal to the left of each chapter title. |
| process chapters and culture principles | process-heading | SuisseBPIntl | 700 | 60px | 0.8 | -0.02em, uppercase | fixed | Numbered process titles and short principle headings; also the centered culture opening. |
| light service and capability pages | service-support | SuisseBPIntl | 400 | 24px | 1.2 | -0.02em | fixed | Secondary benefit statement between introduction and process. |
| process chapters | process-list | SuisseBPIntl | 400 | 22px | 1.2 | -0.02em | fixed | Unbulleted deliverables under each process title. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The display system uses 700-weight uppercase with unusually tight 0.8 leading. Regular editorial leads remain sentence case and switch to 0.9–1 leading rather than becoming bold.
- Tracking is consistently -0.02em across both families; the large process ordinal is the deliberate normal-tracking exception.
- Tiny mono utility text is a counterpoint to the oversized grotesk, not a substitute for paragraph typography. Maintain semantic headings even when animating individual words.

## Layout

**Density:** Airy at chapter scale, compact inside indexes and utilities; substantial pauses surround tightly typeset statements.

### Spacing

**Spacing system:**

- **horizontal-step** 8px, horizontal — Common horizontal spacing rhythm; the separate 10px declared gap also governs compact actions.
- **declared-gap** 10px, horizontal — Declared compact grid gap and button icon spacing.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Image-strip gaps and adjacent closing actions. | fixed |
| 16px | Floating furniture distance from viewport edges; smaller-layout side margin. | fixed |
| 24px | Desktop grid gutters, index row top and bottom padding, label-to-opening-headline gap. | fixed |
| 30px | Editorial heading-to-support gap. | fixed |
| 32px | Testimonial padding and capability sub-block gap. | fixed |
| 40px | Desktop side margins and compact block separation. | fixed |
| 48px | Closing paragraph-to-actions and heading-to-contact-chip space. | fixed |
| 56px | Editorial lead to project index. | fixed |
| 80px | Standard explanatory section padding. | fixed |
| 115.3px | One-column editorial indent or deliberate column separation. | calc(((100vw - (2 * 2.5rem + (12 - 1) * 1.5rem)) / 12) * 1 + 1 * 1.5rem) |
| 160px | Large section breathing room and closing bottom padding. | fixed |
| 240px | Major dark chapter and closing top padding. | fixed |
| 320px | Deep breathing room before the initial editorial proof introduction. | fixed |

### Containers and grids

- **desktop-grid**: 12 columns · gap 24px · side padding 40px. Fluid full-width editorial grid, yielding 1360px usable width at 1440px; no general fixed page max-width.
- **split-story**: 2 columns · gap 24px. Six-column halves of 668px; text frequently occupies only five columns, 553px, with unused columns preserving asymmetry.
- **navigation-island**: max width 438px. Top-centered compact floating navigation with a narrow expanded menu beneath it.
- **utility-rail**: max width 160px · gap 4px. Upper-right stack of contact and expandable media teasers.

## Corner radius

| Element | Radius |
| --- | --- |
| controls-and-panels | 4px |
| clock-dot | 50% |

## Surfaces and depth

### Surfaces

#### Dark canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #1a1c1c; color: #f9f4eb`

**Observed:** Continuous charcoal field; chapters are separated through spacing and rules rather than raised cards.

**Transfer:** Keep the structural page neutral while original media supplies color.

#### Navigation glass · level 2

**Use:** Floating navigation island.

**CSS:** `background: rgba(0,0,0,0.6); border-radius: 4px; backdrop-filter: blur(4px)`

**Observed:** The glass stays localized to small utility furniture. The light-theme navigation uses white at 60% instead.

**Transfer:** Retain legibility over changing imagery without a full-width opaque header.

#### Ruled field · level 0

**Use:** Project rows and capability dividers.

**CSS:** `border-top: 1px solid rgba(249,244,235,0.2)`

**Observed:** Hairlines span the available width; light theme uses near-black at 20%.

**Transfer:** Prefer a rule and clear column alignment over an enclosing card.

#### Cream canvas · level 0

**Only for:** light service and capability pages

**Use:** Explanatory alternate theme.

**CSS:** `background: #f9f4eb; color: #010101`

**Observed:** The cream field continues through introduction, proof, process, project index and closing; small inserts become white.

**Transfer:** Invert a whole page theme rather than alternating every section between light and dark.

#### Faint outline panel · level 1

**Only for:** light service and capability pages

**Use:** Small editorial endorsement panel.

**CSS:** `background: transparent; border: 1px solid rgba(1,1,1,0.1); border-radius: 4px; box-shadow: none`

**Observed:** No elevation; the outline groups a portrait, role label and compact statement.

**Transfer:** Use sparingly as an offset proof note, not as the default container for every feature.

## Components

### Navigation island

**Use:** Persistent wayfinding above cinematic and editorial content.

**CSS:** `position: fixed; top: 16px; left: 50%; transform: translateX(-50%); width: 438px; height: 50px; border-radius: 4px; background: rgba(0,0,0,0.6); backdrop-filter: blur(4px); z-index: 20`

**Text style:** `label` — Sometype 500 · 10px/18px · tracking -0.02em · uppercase

**Observed:** Small geometric logo at left, contextual one-line quip centered, hamburger at right. Expands down into menu rows and paired conversion actions; the visible resting state is compact.

**Transfer:** Use the new product's own small mark and contextual microcopy.

### Menu row

**Use:** Expanded main navigation.

**CSS:** `display: flex; align-items: center; height: 50px; width: 438px; color: #f9f4eb`

**Text style:** `navigation` — SuisseBPIntl 400 · 16px/1.4 · tracking -0.02em

**Observed:** Main entries stack vertically with small icons at left. Nested service entries are 40px tall, use 14px/19.6px grotesk text and a 43px left indent. Light theme inverts text to near-black.

### Outline action

**Use:** Default in-content conversion links, especially the closing pair.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 50px; padding: 0 16px; gap: 10px; border: 1px solid rgba(249,244,235,0.2); border-radius: 4px; background: transparent; color: #f9f4eb`

**Text style:** `label` — Sometype 500 · 10px/18px · tracking -0.02em · uppercase

**Observed:** Short label followed by a tiny up-right arrow. Width follows copy, commonly 135px. The light explanatory theme uses an ink outline for mid-page actions and white-filled closing actions.

### Filled action

**Use:** High-contrast actions inside the expanded navigation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 50px; width: 204px; padding: 0 16px; gap: 10px; background: #f9f4eb; color: #000000; border-radius: 4px`

**Text style:** `label` — Sometype 500 · 10px/18px · tracking -0.02em · uppercase

**Observed:** Paired in two columns with a 4px gap. The light-theme equivalent uses near-black fill and white lettering.

### Portrait contact chip

**Use:** Human contact at top right and below the closing headline.

**CSS:** `display: inline-flex; align-items: center; height: 50px; padding: 0 32px 0 11px; gap: 20px; background: #000000; color: #f9f4eb; border-radius: 4px; overflow: hidden`

**Text style:** `label` — Sometype 500 · 10px/18px · tracking -0.02em · uppercase

**Observed:** A small square portrait leads the telephone or contact label. In-flow width is 169px; the fixed rail version is 160px and has a translucent cream backing with dark text. On cream, the in-flow chip is white.

### Utility teaser

**Use:** Expandable supporting media beneath the fixed contact chip.

**CSS:** `width: 160px; height: 50px; padding: 0 12px; border-radius: 4px; background: rgba(0,0,0,0.4); backdrop-filter: blur(4px); overflow: hidden`

**Text style:** `label` — Sometype 500 · 10px/18px · tracking -0.02em · uppercase

**Observed:** Stacked 4px apart. A label and parenthesized plus/minus control head an expanded vertical media preview. Context changes along the page; this rail is separate from main reading content.

**Transfer:** Show a product film, overview or useful related story rather than a generic promotion.

### Compact category action

**Use:** Small chapter-entry links beneath a capability heading.

**CSS:** `display: inline-flex; align-items: center; height: 34px; padding: 0 16px; gap: 10px; border: 1px solid rgba(249,244,235,0.2); border-radius: 4px; color: #f9f4eb`

**Text style:** `label` — Sometype 500 · 10px/18px · tracking -0.02em · uppercase

**Observed:** Three compact outlined links with up-right arrows; grouped with a 10px gap, wrapping when necessary.

### Project index row

**Use:** Visually rich proof without large card stacks.

**CSS:** `position: relative; padding: 24px 40px; height: 168px; overflow: hidden; border-top: 1px solid rgba(249,244,235,0.2); text-align: left; color: #f9f4eb`

**Text style:** `body` — SuisseBPIntl 400 · 20px/1.2 · tracking -0.02em

**Observed:** Name at left, tiny dark category tags beside it, parenthesized expansion symbol near the middle, and an image strip occupying the right half. Media mixes portrait and landscape frames at 120px high. Expanded content reveals larger imagery and a summary. Light theme reverses rules and tag fills.

**Transfer:** Use this for case studies, integrations or use-case proof; vary image proportions rather than enclosing every item in an identical tile.

### Endorsement panel

**Only for:** light service and capability pages

**Use:** Offset human proof beside a compact outcome table.

**CSS:** `display: flex; flex-direction: column; gap: 40px; width: 322px; padding: 32px; border: 1px solid rgba(1,1,1,0.1); border-radius: 4px; color: #010101`

**Text style:** `body-small` — SuisseBPIntl 400 · 16px/1.4 · tracking -0.02em

**Observed:** Small vertical portrait and bracketed job label share the top area; a concise statement follows well below. Canvas shows through.

### Metric row

**Only for:** light service and capability pages

**Use:** Compact quantified proof table.

**CSS:** `display: flex; align-items: center; justify-content: space-between; min-height: 40px; gap: 16px; border-bottom: 1px solid rgba(1,1,1,0.1); color: #010101`

**Text style:** `label` — Sometype 500 · 10px/18px · tracking -0.02em · uppercase

**Observed:** Readable grotesk metric names on the left and much smaller mono values to the right; the overall table is 437px wide. Numerals are intentionally not giant stat headlines.

**Transfer:** Use only substantiated outcomes; keep the small numeric countervoice.

## Imagery and graphics

### Monochrome material film

**Use:** Default full-screen opening stage.

**Observed:** Extreme close-up, liquid or fibrous black forms streak upward into blown-out pale light. Soft focus, turbulent edges and high contrast occupy the entire viewport; the lower area remains dark enough for cream text.

**Transfer:** Create an original macro study of a relevant material or abstract product texture. Minimum acceptable replacement is a high-resolution still with the same sweeping black-to-light silhouette, not an empty gradient.

**Build:** Use a full-bleed original texture under the page text. For a procedural fallback, layer broad off-white ellipses behind several irregular black SVG paths rising diagonally from the bottom; apply SVG turbulence displacement to their edges, soften the background shapes with a 20px blur, and retain a dark lower third. Keep text and controls in separate sharp layers.

### Photographic halftone field

**Use:** Signature atmospheric chapter backing and transition out of the opening.

**Observed:** A low-contrast photograph becomes a screen of tiny cream square-like dots over charcoal. Large faces, arms and environmental shapes emerge from density changes rather than full-color pixels; foreground headings and text remain crisp.

**Transfer:** Derive the dot field from an original product-use photograph or the abstract opening material. Include this device on new marketing pages without making every section textured.

**Build:** Downsample the chosen image to a roughly 6px sampling grid at desktop size. In canvas or SVG, draw 1–2px cream squares per sample, using local luminance to control opacity and density; place over charcoal with peak opacity around 0.2. Fade edges with a vertical mask and keep strong textual regions lower contrast. This is a construction target, not a fixed dot count.

### Candid editorial photography

**Use:** Human context between capability chapters and proof.

**Observed:** Warm natural-light office details, plants, people working and imperfect close-ups; two small vertical frames can sit beside a much larger portrait. Images have hard rectangular edges, no ornamental frames, and tiny mono captions.

**Transfer:** Photograph real use environments and details. Pair one scene-setting close-up with one human action shot, keeping the asymmetrical scale and unpolished warmth.

### Case study art direction

**Only for:** case-study and project proof sections

**Use:** Show the work at both thumbnail and immersive scale.

**Observed:** A full-width packaging photograph shows tactile brown board, oversized orange lettering and hard cast shadows on a light gray ground. Other panels alternate lifestyle photography, interface compositions, icon sheets and product details; two 668px columns with a 24px gap alternate with broad 1360px images.

**Transfer:** Show an equivalent range of materials, product use and interface context. Keep the project's colors within its artwork instead of turning them into site-wide tokens.

### Red liquid field

**Only for:** culture and manifesto openings

**Use:** An immersive alternate cinematic opening.

**Observed:** Deep crimson ripples and translucent pink highlights fill the screen behind a small centered cream declaration, creating a visceral rather than technical mood.

**Transfer:** Use an original expressive material film appropriate to the culture story, maintaining one dominant hue and plenty of visual depth.

**Build:** Use an original liquid macro texture or a displaced SVG field: overlapping deep red and translucent pale-red organic paths, feTurbulence plus feDisplacementMap, a dark vignette and a lightly blurred highlight layer. Keep the centered text sharp; avoid uniform flat red.

### Icons

**Observed:** Tiny monochrome solid SVGs, mostly 10×10px, with 7×8px and 7×7px variants. Diagonal arrows, plus/minus and parenthesized symbols accompany actions; a simple hamburger opens navigation.

**Transfer:** Choose sparse geometric utility marks in the current text color. Keep them secondary to mono labels; avoid decorative multicolor icon sets.

## Section recipes

How recurring sections are built.

### First screen: Cinematic lower-third opening

**Observed:** The first 900px are a full-viewport Monochrome material film with a Navigation island centered 16px from the top and the contact/Utility teaser rail at upper right. At the lower left a bracketed label precedes the 72px/0.8 hero block by 24px; the statement spans seven grid columns, about 783px, over three compact lines. A 322px-wide supporting paragraph sits lower right, baseline-aligned with the headline block. Layers run from charcoal base to film, contrast-aware cream text, then floating utility furniture. A thin bottom rule and tiny location, clock, social and language utilities complete the screen. The main conversion is the fixed contact chip rather than a large centered button cluster. Editorial proof begins below the first viewport.

**Transfer:** Give a different product a concise, forceful declaration and an original high-contrast material study; retain the left-heavy lower-third composition and small human contact affordance. Case studies instead open with a left title, rule, tags, short summary and tall right-hand media. Explanatory pages use a cream canvas and centered 80px statement above a split introduction; culture stories use the scoped Red liquid field and centered 60px statement.

**Avoid:** Do not reduce the opening to a centered headline, two oversized pills and a floating device mockup. Do not let bright media eliminate contrast in the lower text zone.

**Text style:** `hero` — SuisseBPIntl 700 · 72px/0.8 · tracking -0.02em · uppercase

### Indented editorial proof lead

**Observed:** An editorial-lead statement occupies about half the page width, with its first line inset by one grid column, followed 56px later by Project index rows. A tiny bracketed section label can align to the far right of the introductory area.

**Transfer:** Introduce why the proof matters in a conversational paragraph-size headline, then let imagery carry the detail.

**Text style:** `editorial-lead` — SuisseBPIntl 400 · 48px/0.9 · tracking -0.02em

### Capability panorama

**Observed:** An 80px uppercase heading sits above Compact category actions and a 668px-wide capability-lead paragraph. A Ruled field then divides a contact prompt on the left from three narrow columns of service labels and lists on the right. Photographic halftone field spans the background; top padding is 240px and bottom padding 200px.

**Transfer:** Group a new product's capability families into concise columns; keep the atmospheric backing and the contrast between huge heading, mid-size statement and tiny mono taxonomy.

**Text style:** `capability-lead` — SuisseBPIntl 400 · 32px/1 · tracking -0.02em

### Asymmetric human story

**Observed:** Small paired vertical photographs occupy the left while a large portrait occupies the right half. The regular editorial-secondary paragraph sits below the small images with an indented first line; a compact outline link follows. Light explanatory variants pair two small photos at left with editorial-lead and body text at right, using 80px section padding.

**Transfer:** Balance a product or maker story with genuine use imagery; keep unequal text and media scale rather than mirroring two equal cards.

**Text style:** `editorial-secondary` — SuisseBPIntl 400 · 40px/1 · tracking -0.02em

### Monumental invitation and utility baseline

**Observed:** A 720px closing field uses 240px top and 160px bottom padding. An 80px/0.8 two-line invitation occupies five columns at left, with a Portrait contact chip 48px beneath. To its right, after a one-column separation, a bracketed label, short body paragraph and two Outline actions form a lower-aligned response block; actions sit 48px below the paragraph and 8px apart. At the bottom a thin baseline separates tiny identity, location, bracketed clock, social and language utilities. All five page types finish with this composition; cream pages use white action and contact inserts.

**Transfer:** Always give the new page a confident, short closing line and a human route to act. Adapt the utility facts to the new brand while preserving the sparse baseline rather than adding a dense multi-column sitemap.

**Text style:** `display` — SuisseBPIntl 700 · 80px/0.8 · tracking -0.02em · uppercase

### Compact proof and endorsement

**Only for:** light service and capability pages

**Observed:** On Cream canvas, an Endorsement panel sits in the left three grid columns, offset below the start of a right-hand explanatory paragraph. Beneath that paragraph, Metric rows form a narrow table. Values stay at 10px mono rather than becoming oversized numbers.

**Transfer:** Pair a named human viewpoint with a concise table of verified outcomes. A bracketed proof label can close the area without requiring a logo wall.

**Text style:** `body-small` — SuisseBPIntl 400 · 16px/1.4 · tracking -0.02em

### Numbered process chapters

**Only for:** process explanations

**Observed:** Wide ruled horizontal chapters are about 360px tall. A 70.1px ordinal takes the left two columns; a 60px uppercase title begins two columns farther right. A bracketed label and 22px unbulleted deliverable list sit below the title; a narrow explanatory paragraph sits at the far right. Chapters stack upward as the reader advances.

**Transfer:** Use this spacious ordinal treatment for meaningful steps or capability phases, adjusting the number of chapters to the story.

**Text style:** `process-heading` — SuisseBPIntl 700 · 60px/0.8 · tracking -0.02em · uppercase

### Immersive case gallery

**Only for:** case-study pages

**Observed:** A dark editorial introduction leads into large rectangular media: tall lifestyle imagery, full-width material photography and paired visual-system panels. Gutters remain 24px and side margins 40px. Related work returns to Project index rows before the shared closing.

**Transfer:** Alternate context, craft detail and product demonstration; make the imagery the case argument rather than surrounding it with repeated descriptive cards.

### Ruled principles and people

**Only for:** culture and team pages

**Observed:** Short 60px uppercase principles sit left in widely spaced ruled rows, while explanatory text occupies a narrow right column. A large photographic proof moment leads to an 80px people heading, support copy and a right-half roster with names, bracketed mono roles and hairline dividers. A later film chapter uses halftone people imagery and a compact heading anchored low on the left.

**Transfer:** Use for company beliefs and human expertise only when relevant; adapt the roster to the real team and keep roles quieter than names.

**Text style:** `process-heading` — SuisseBPIntl 700 · 60px/0.8 · tracking -0.02em · uppercase

## Page flow

**Storyline:** Atmospheric promise → editorial explanation → visual or quantified proof → capability or craft chapters → human context → monumental invitation.

### Broad brand or product introduction

1. **Promise** — Full-screen material film and lower-third declaration.
2. **Visual proof** — Indented editorial lead followed by ruled image-strip indexes.
3. **Capabilities** — Large uppercase chapter heading, mid-size statement and small taxonomy columns over halftone imagery.
4. **Human context** — Asymmetric candid photography and conversational text.
5. **Closing call** — Monumental invitation, portrait contact chip and utility baseline.

**Transfer:** Use this as the default new landing-page pattern; let the product determine the proof and capability mix.

### Detailed case study

1. **Context** — Title, category tags and compact project premise beside tall lifestyle media.
2. **Product demonstration** — Immersive gallery alternating full-width and paired photographs, interface compositions and material details.
3. **Related proof** — Compact related-work index.
4. **Closing call** — Shared dark invitation and utility baseline.

**Transfer:** Let a real outcome and its visual artifacts carry the page; avoid restating every image in prose.

### Culture and company story

1. **Conviction** — Centered cream declaration on a red liquid film.
2. **Character** — Large regular manifesto, small editorial image triplet and ruled principle rows.
3. **Credibility** — Immersive recognition photograph.
4. **Human proof** — Large team heading, right-hand ruled roster and halftone culture film.
5. **Closing call** — Shared dark invitation and utility baseline.

**Transfer:** Use this expressive variant for people and beliefs, not as the default product pitch.

### Performance-oriented service explanation

1. **Promise** — Centered uppercase headline on cream, followed by a split editorial statement and product media.
2. **Quantified proof** — Offset endorsement and compact outcome table.
3. **Approach** — Paired candid details, right-side rationale and numbered process chapters.
4. **Reassurance** — Short editorial statement beside a large human photograph.
5. **Visual proof** — Large category heading and ruled project index.
6. **Closing call** — Cream invitation with white contact and action inserts.

**Transfer:** Explain a technical offering through outcomes and process, retaining the light page theme.

### Identity-led service explanation

1. **Promise** — Centered emotional declaration on cream and a large regular introduction beside expressive project media.
2. **Credibility** — Small endorsement, compact outcome table and bracketed audience-proof label.
3. **Approach** — Editorial dual content and numbered discovery-to-delivery chapters.
4. **Durability** — A short ongoing-value statement paired with a large candid image.
5. **Visual proof** — Large uppercase index heading and colorful project strips.
6. **Closing call** — Shared cream invitation and utility baseline.

**Transfer:** For a less technical product, foreground emotional character but keep the explanation concrete and structured.

## Writing

Direct, high-energy and craft-conscious, with a human streak and dry little jokes. Confidence comes through terse declarations and plain verbs rather than formal corporate language.

**Do not copy:** Do not reuse the brand name, logo, project names, artwork, contact details, location facts, client outcomes, headcount, awards, exact positioning or distinctive slogans as the new product's assets or claims. Source quotations below illustrate cadence only.

- **Addressing the reader:** Speak as an active 'we' to a reader addressed as 'you' or 'your'. Keep invitations personal rather than institutional.
- **Rhythm:** Short headline fragments contrast with flowing editorial paragraphs. Paired clauses, three-part lists and blunt full stops create the pace; utility copy can add a brief wink.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening declaration | A clear identity or promise with an uncompromising second clause. | 4–15 words | “A creative digital agency that goes all in or not at all.”<br>“Designed to feel. Built to perform.” |
| Editorial lead | A conversational premise followed by specific benefits; sentence case even at display scale. | 20–45 words | “We craft brands with soul, shape and sharpness. Identities that hit the heart and hold their ground.” |
| Chapter title | A short active phrase, often balancing instinct with craft. | 1–6 words | “THINK WILD, CRAFT SHARP”<br>“Where story meets structure” |
| Utility microcopy | Tiny bracketed context or a dry one-line aside. | 2–8 words | “[ We are [Brand] ]”<br>“[ Scroll-stopping sites. Motion-first experiences. ]” |
| Closing invitation | A forceful short imperative followed by warm, practical reassurance. | 3-word heading; 1–2 support sentences | “Brief us something.”<br>“Feel free to reach out and discuss your project. We’ll make it sharper.” |
| Action | Plain verb plus object, no embellished promise. | 2–4 words | “Start a project”<br>“Schedule a call” |

**Words and phrasing to use:** craft; build; feel; sharp; move; real; story; people; from … to …; not just …

**Avoid:** revolutionary ecosystem; synergize; world-class solutions; unlock limitless potential; best-in-class; passive institutional phrasing

**Rules:**

- Pair emotional intent with a concrete function or outcome.
- Keep technical labels short and precise; save conversational warmth for paragraphs.
- Use contrast and parallel phrasing without turning every line into a slogan.
- Present measurements as proof only when they are substantiated for the new product.
- Contextual nav quips should be brief enough to remain a secondary detail.

## Do's and Don'ts

### Do

- Keep the primary opening headline at 700 weight with 0.8 leading and -0.02em tracking.
- Use a 12-column desktop grid with 40px side margins and 24px gutters.
- Keep 10px mono labels separate from readable 20px supporting paragraphs.
- Use 4px control corners consistently, including floating panels.
- Preserve the 120px-high thumbnail strip and 8px image gaps in proof indexes.
- Give major dark chapters 240px-scale breathing room rather than compressing them into feature cards.
- Carry the small portrait contact affordance into the closing field.
- Include an original halftone-backed visual moment with crisp foreground copy.

### Don't

- Do not replace the Swiss grotesk with a rounded geometric display face or serif headline.
- Do not turn 50px rectangular actions into pill buttons or tall promotional slabs.
- Do not enlarge the tiny outcome values into a dashboard-style wall of giant statistics.
- Do not distribute saturated color across navigation, buttons and section fills; keep it in the media.
- Do not add drop shadows to index rows or testimonial panels; the design has no elevation shadows.
- Do not center every editorial paragraph; preserve half-width blocks and the one-column first-line indent.
- Do not replace the sparse utility baseline with a dense newsletter-and-sitemap footer.
- Do not wrap all photography in rounded cards; editorial and case images keep hard rectangular edges.

## Motion and responsive

### Motion

**Observed:**

- Material films, halftone imagery and contextual utility microcopy change as the page progresses.
- Word-by-word text containers, clipped text reveals, expandable project media and stacking process chapters support the editorial rhythm.
- No action transition timings were established; the navigation and utility rail have visible compact and expanded compositions.

**Transfer:**

- Tie reveal and halftone changes to chapter progression while preserving the same strong settled compositions.
- Use a still material study and static halftone image when motion cannot be produced; do not leave the stage empty.

**Unknown:**

- Precise reveal durations, interaction easing, hover/focus behavior and film loop timing.

### Responsive

**Observed:**

- Desktop composition uses 12 columns, 40px margins and 24px gutters. Narrow-layout declarations indicate 16px side margins, column stacking and removal of the right utility rail.
- Opening and editorial lead sizes use the listed clamp formulas; a declared compact grid uses 6 columns and a 10px gap.

**Transfer:**

- On narrow screens, move opening support below the headline and keep the cinematic backdrop, compact top navigation and forceful short line breaks.
- Stack text and imagery while keeping meaningful differences in image scale. Keep project thumbnails in a horizontal strip rather than shrinking them into unreadable tiles.
- Convert the two-column closing invitation to a vertical reading order with the contact chip near the headline and actions beneath the support.

**Unknown:**

- Exact breakpoint widths and finished mobile compositions were not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
