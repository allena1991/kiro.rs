# Sunday — machines at home

## Overview

An approachable, film-led style that makes sophisticated technology feel like part of ordinary life. White and warm cream space, charcoal lettering and a concentrated flash of sun yellow surround softly lit domestic photography and tactile product close-ups. Regular grotesk headlines meet small monospaced labels; the overall density is spacious, with unusually compact controls. It suits human-centered hardware, helpful software and technically ambitious products with an everyday benefit.

### Essentials

- An introduction rather than a sales shout: a centered 120px/1 regular grotesk headline with -0.025em tracking sits over a nearly edge-to-edge domestic film, inset 24px with 12px corners.
- Human scale and equipment markings coexist: narrative headings use sans at weight 400, while navigation, captions and calls to action use 14px mono with 0.025em tracking.
- Controls stay small even when the scene is enormous: outlined pill actions are 40–42px high, with 12px vertical padding and 14px leading-side padding; no oversized conversion rectangles.
- Color arrives in chapters, not confetti: white and cream carry the long story, pale sage and blue back selected product moments, and a full-width 450px yellow closing reveal concentrates the strongest flat color. Keep yellow elsewhere to a short accent line.
- Proof feels lived-in: broad 16:9 films show the product doing real work in softly lit spaces, followed by tightly joined explanatory and demonstration tiles with 8px gaps. Without film, use a credible staged photograph or recorded workflow in the same broad frame.
- A short promise becomes a spatial word composition: 104px/1 lettering is spread across an airy cream field, with the outcome word separated and anchored toward the right; create this device with original benefit language.
- The ending gives time back: a tiny centered everyday-life line, three outlined context pills and a small brand symbol occupy a bright yellow 450px field beneath a rounded light footer. Preserve this humane sign-off device with relevant local or product context.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sun yellow | `#f7e731` | `--color-sun` | background, accent, text | Closing reveal field and brief highlighted support copy on charcoal. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sage | `#aec2b8` | `--color-sage` | background | Muted green opening of the isolated-object gradient stage. |
| Sand | `#eadcce` | `--color-sand` | surface | Tactile safety or product-detail card backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Default canvas, navigation and inverse lettering. |
| Cream | `#faf7eb` | `--color-cream` | background | Warm editorial promise fields and the recruiting canvas. |
| Warm light gray | `#f3f3f0` | `--color-stone` | surface, background | Product-detail stage, newsletter strip and technical information panels. |
| Gradient warm gray | `#ecece8` | `--color-warm-gray` | background | Pale end of the isolated-object gradient. |
| Soft ink edge | `#e8e8e8` | `--color-rule` | border | Visible ink at 10% on white; fine rules, cards and navigation outlines. |
| Pill edge | `#e6e6e6` | `--color-action-edge` | border | Visible black at 10% on white; outlined light actions. |
| Inverse gray | `#999999` | `--color-inverse-secondary` | text | White at 60% on black for secondary text in dark chapters. |
| Secondary gray | `#6f6f6f` | `--color-secondary` | text, link | Visible result of ink at 63% on white; supporting text and footer links. |
| Inverse hairline | `#333333` | `--color-inverse-edge` | border | White at 20% on black for dark action and media outlines. |
| Soft black ink | `#1a1a1a` | `--color-ink` | text, surface | Primary lettering and charcoal call-to-action bands. |
| Film black | `#000000` | `--color-black` | background, text, action | Media backing, technical dark chapters and button inversion. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience participation sections | Pale blue | `#d9ecee` | `--color-ice` | background | Playful audience-participation field. |
| recruiting pages | Cream navigation | `#fefdfa` | `--color-nav-cream` | surface | Warm navigation surface over recruiting photography. |

## Typography

- **sans** — All narrative headlines and paragraphs. Rounded, friendly neo-grotesk with a single-storey alternate and regular-weight display forms. OpenType features: "ss01". If unavailable, use **Inter**. Use weight 400 and enable ss01; retain tight display tracking. Font stack: "sans", "Inter", system-ui, Arial, Helvetica, sans-serif.
- **mono** — Labels, navigation, footer, metadata and actions. Small, lightly spaced monospaced lettering that feels like instrument labeling rather than code. OpenType features: "kern". If unavailable, use **DM Mono**. Use weight 400 at 14px, without uppercase conversion. Font stack: "mono", "DM Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental-heading | sans | 400 | 142px | 1 | -0.025em | One expansive product-detail chapter title. |
| display | sans | 400 | 120px | 1 | -0.025em | Centered primary product introduction. |
| word-composition | sans | 400 | 104px | 1 | -0.025em | Separated words in the spatial benefit interlude. |
| film-heading | sans | 400 | 84px | 1.1 | -0.025em | Centered white capability title over a large film. |
| statement | sans | 400 | 42px | 1.15 | -0.025em | Full-width introductory statements; also bottom-centered titles in immersive editorial openings. |
| centered-lead | sans | 400 | 32px | 1.2 | -0.025em | Centered explanation between visual chapters. |
| section-heading | sans | 400 | 24px | 1.3 | -0.025em | Two-line section heading pairs and substantial adjacent introductory text. |
| body | sans | 400 | 20px | 1.4 | normal | Large explanatory cards and long-form technical prose. |
| body-small | sans | 400 | 18px | 1.4 | normal | Supporting card text, FAQ questions and principle rows. |
| label | mono | 400 | 14px | 1.2 | 0.025em | Section markings, footer links and short call-to-action headings. |
| action | mono | 400 | 14px | 1 | 0.025em | Pill button and context-pill text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company profiles and technical reference sections | editorial-caption | sans | 400 | 14px | 1.4 | normal | Biographical captions and compact technical definitions. |

**Notes:**

- Headlines grow through size and placement, not bold weight. Keep all narrative recipes at 400.
- Display and section lettering share -0.025em tracking; body text returns to normal. Mono labels use 0.025em spacing and sentence case.
- Use the 120px introduction as the landing-page default. The 42px two-line immersive title belongs to editorial, recruiting and technical openings.
- Use underlines for important inline terms, not colored body links.

## Layout

**Density:** Airy in the narrative, tightly packed within media groups; long breathing intervals contrast with small labels and controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Joined media tiles, button groups and compact stacks. |
| 12px | Card and media inset padding; footer link stack gaps. |
| 16px | Centered band content gaps and FAQ question top padding. |
| 24px | Page gutters, editorial grid gaps and band padding. |
| 48px | Support-to-action separation and editorial subgroups. |
| 96px | Major section top and bottom padding. |
| 128px | Bottom spacing between technical reference chapters. |
| 160px | Separation after major capability demonstrations. |

### Containers and grids

- **page-grid**: 12 columns · gap 24px · side padding 24px. Full-width desktop editorial grid. Split heading and explanation into two equal six-column fields.
- **media-grid**: 6 columns · gap 8px · side padding 24px. Hero film spans all columns; lower proof tiles divide into equal halves or thirds.
- **reading-column**: max width 786px · side padding 24px. Centered large explanatory paragraphs; shorter film below is 684px wide at desktop.
- **footer-columns**: 3 columns · gap 24px. Three equal link columns occupy the right half; the left half holds a one-line company descriptor.
- **reference-content** (only for recruiting listings and technical reference sections): max width 1038px · gap 24px. Right-aligned nine-column content area beside a three-column local index.

## Corner radius

| Element | Radius |
| --- | --- |
| cards-and-navigation | 12px |
| actions-and-context-pills | 9999px (pill) |
| detail-stage | 24px |
| media-labels | 4px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #ffffff; color: #1a1a1a`

#### Warm editorial field · level 0

**Use:** Spatial word promise and warm recruiting content.

**CSS:** `background: #faf7eb; color: #1a1a1a`

**Observed:** A broad flat field, not a paper texture.

**Transfer:** Use cream for a sustained editorial pause, rather than alternating every card.

#### Detail stage · level 0

**Use:** A distinct tactile product chapter.

**CSS:** `background: #f3f3f0; border-radius: 24px`

**Observed:** Inset within white, carrying an oversized title and a horizontal rail of product-detail cards.

**Transfer:** Give one meaningful chapter a continuous backing instead of a collection of floating panels.

#### Dark chapter · level 0

**Use:** Technical depth and high-contrast film moments.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Full-width dark ground; inner process cards use charcoal rather than shadows.

**Transfer:** Reserve sustained darkness for a distinct story mode.

#### Outline card · level 1

**Use:** Narrative copy beside visual proof.

**CSS:** `border: 1px solid rgba(26, 26, 26, 0.1); border-radius: 12px; padding: 12px; box-shadow: none`

#### Sage object stage · level 0

**Use:** A clean isolated-product transition.

**CSS:** `background: linear-gradient(in oklab, #aec2b8 33%, #ecece8 100%)`

**Observed:** A pale vertical gradient holds a large isolated object, with white promise text above it.

**Transfer:** Keep the gradient broad and muted, with no neon glow.

#### Sun reveal · level 0

**Use:** Signature closing field.

**CSS:** `background: #f7e731; color: #000000; min-height: 450px`

**Observed:** The light footer ends as a rounded sheet above an exposed yellow underlayer.

**Transfer:** Keep the saturated field largely empty so the tiny sign-off feels intentional.

## Components

### Floating navigation

**Use:** Persistent compact brand and menu access.

**CSS:** `width: 330px; height: 60px; background: #ffffff; border: 1px solid rgba(26, 26, 26, 0.1); border-radius: 12px; backdrop-filter: blur(40px); overflow: hidden`

**Observed:** Centered near the top with 24px outer spacing; symbol at left, wordmark centered and two-line menu at right. Recruiting uses the cream navigation surface; technical film uses translucent gray.

**Transfer:** Use the new brand's compact mark and wordmark, retaining the small isolated bar rather than a full-width nav.

### Outline action

**Use:** Default exploration and conversion action on light ground.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 12px 14px; gap: 4px; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 9999px; color: #000000; background: transparent`

**Text style:** `action` — mono 400 · 14px/1 · tracking 0.025em

**Observed:** A restrained text-only pill; paired actions sit side by side. Subscribe variant adds a small circular arrow and reaches 42px high.

**States:** Declared: hover border-color #000; background-color #000; color #fff; focus-visible not specified.

**Transfer:** Keep action labels short and sentence case.

### Inverse action

**Use:** Actions over dark bands or photographs.

**CSS:** `display: inline-flex; align-items: center; height: 42px; padding: 12px 10px 12px 14px; gap: 6px; border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 9999px; color: #ffffff; background: transparent`

**Text style:** `action` — mono 400 · 14px/1 · tracking 0.025em

**Observed:** Text followed by a small arrow in a translucent circular well.

**States:** Declared: hover border-color #fff; background-color #fff; color #000; focus-visible not specified.

### Explanation tile

**Use:** Copy paired with a demonstration.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 12px; border: 1px solid rgba(26, 26, 26, 0.1); border-radius: 12px`

**Text style:** `body` — sans 400 · 20px/1.4

**Observed:** Small mono caption sits at the top; paragraph sits low in the tile, leaving a deliberate internal void. Narrower third-width variants use body-small.

**Transfer:** Match the adjacent film's height rather than shrinking the card to its text.

### FAQ row

**Use:** A concise objection-handling list.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; padding: 16px 0 0 0; color: #1a1a1a; text-align: left`

**Text style:** `body-small` — sans 400 · 18px/1.4

**Observed:** Each question lives under a separate ink-at-10% top rule with a 16px chevron at far right; rows are separated by about 32px of combined gap and margin. Section title occupies the left half of the page.

**Transfer:** Use real questions and keep answers behind the disclosure.

### Newsletter strip

**Use:** Low-pressure secondary conversion near the footer.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 16px; padding: 24px; min-height: 110px; background: #f3f3f0; border-radius: 12px`

**Text style:** `label` — mono 400 · 14px/1.2 · tracking 0.025em

**Observed:** A short heading, muted support line and Outline action share one centered horizontal line. Recruiting variant is charcoal with inverse text and Inverse action.

### Footer link

**Use:** Compact grouped navigation.

**CSS:** `color: rgba(26, 26, 26, 0.63); text-decoration: none`

**Text style:** `label` — mono 400 · 14px/1.2 · tracking 0.025em

**Observed:** Small mono links beneath darker group labels, in three right-side columns with 12px stack gaps.

**States:** Declared: hover color #1a1a1a; focus-visible not specified.

### Tactile detail card

**Use:** Close-up evidence of physical or experiential qualities.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); gap: 24px; padding: 12px; background: #eadcce; border-radius: 12px; overflow: hidden`

**Text style:** `body-small` — sans 400 · 18px/1.4

**Observed:** A wide split card places title and gray description opposite an image. Narrow variants use full-bleed imagery with inverse copy at top. Desktop cards are about 522px tall and sit in an 8px-gap horizontal rail.

**Transfer:** Translate tactile detail into close views of the actual product, interaction or output.

### Listing row

**Only for:** recruiting pages

**Use:** Open-role listings grouped by discipline.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 16px; padding: 12px 0; border-bottom: 1px solid rgba(26, 26, 26, 0.126275)`

**Text style:** `body` — sans 400 · 20px/1.4

**Observed:** Role title and muted discipline occupy the broad left area, with location in mono at right. Category labels sit above groups; a compact filter index remains in the left quarter.

**States:** Declared: hover border-color #1a1a1a; focus-visible not specified.

### Technical panel

**Only for:** technical reference sections

**Use:** Diagrams and specification groups.

**CSS:** `background: #f3f3f0; border-radius: 12px; padding: 12px`

**Text style:** `editorial-caption` — sans 400 · 14px/1.4

**Observed:** A large line illustration sits beside stacked smaller specification cards. Other chapters pair two orthographic views or use ruled glossary cells.

**Transfer:** Use honest technical diagrams with sparse captions instead of decorative dashboard widgets.

## Imagery and graphics

### Everyday product film

**Use:** Opening and capability proof; dominant visual material.

**Observed:** Warm, natural interiors, green upholstery, wood, ceramics and soft daylight surround the machine. Framing is cinematic but ordinary, often showing the product mid-task rather than posed toward camera. Broad films fill nearly the entire page width, with gently darkened exposure beneath white chapter titles.

**Transfer:** Show a new product helping someone in its real context. For software, film a credible workflow or an actual output in use; a well-lit contextual still is the minimum equivalent.

### Tactile product details

**Use:** Horizontal detail rail and product-trust chapters.

**Observed:** Tightly framed shells, controls, colored accessory forms and a hand pressing a soft surface. Matte materials, rounded forms and restrained highlights dominate; sand and muted green back split cards while close-up photos carry richer reds and yellows.

**Transfer:** Use material, craft and interaction details rather than unrelated lifestyle stock. Keep the product large enough for its finish or behavior to read.

### Isolated object transition

**Use:** A signature bridge from benefit to mechanism.

**Observed:** A white mechanical glove rises from the lower edge against pale sage fading to warm gray; the object occupies the center beneath a white promise line.

**Transfer:** Isolate one meaningful mechanism or representative output. Without a 3D asset, use a clean cutout photograph with a soft contact shadow.

**Build:** Use the Sage object stage as a full-width backing. Center a transparent product image at about 720px width on desktop, let it enter from the bottom, and keep the top half clear for a short white title. Avoid spotlights or extra floating shapes.

### Spatial promise lettering

**Use:** Signature typographic interlude.

**Observed:** Oversized regular black words on cream; the opening phrase occupies the left-to-center area and the final outcome word sits lower toward the right, surrounded by extensive empty space.

**Transfer:** Split a short before-and-after promise into meaningful phrase groups rather than mirroring the original wording.

**Build:** Use live text in the word-composition recipe inside a broad cream section. Create a two-row desktop grid: first phrase left aligned across the wider first row, outcome word right aligned on the second. Keep the entire composition within roughly 1000px and retain a tall surrounding field.

### Process dial

**Only for:** technical process explanations

**Use:** Explain a repeatable mechanism in a dark chapter.

**Observed:** A charcoal panel contains a circular instrument-like dial of fine white-gray radial ticks, a central outlined circle and a dashed radius pointing upward. Stage names ring the dial; a small yellow status dot marks the active text panel at left.

**Transfer:** Map the new product's real process onto a small number of stages. Use a static complete diagram if an interactive version is unavailable.

**Build:** Draw an SVG with two concentric sets of radial ticks using white at low opacity, a 96px central circle with 1px white outline, and a dashed vertical connector. Place four stage labels near cardinal points and a tiny yellow dot in the active side card. Back with charcoal and 12px corners; avoid decorative particles.

### Human editorial photography

**Only for:** company and recruiting pages

**Use:** Immersive openings, team proof and editorial photo strip.

**Observed:** Candid workshop work and relaxed portraits use natural light and muted saturation. A loose horizontal strip alternates portrait and landscape images with generous white gaps; biographies use a single large group portrait above compact columns.

**Transfer:** Photograph real people working, with imperfect but believable environments, rather than uniform studio headshot grids.

### Icons

**Observed:** Small utilitarian outlined arrows and chevrons use 2px strokes with round caps, commonly at 16px; tiny play symbols and arrows appear in circular translucent wells. Brand symbols are solid silhouettes rather than line icons.

**Transfer:** Keep utility icons sparse, monochrome and subordinate to mono labels. Use the new brand's own solid symbol for the closing sign-off.

## Section recipes

How recurring sections are built.

### First screen: Product introduction

**Observed:** A white first screen is anchored by Floating navigation near the top center. A tiny two-line mono descriptor and availability line precede a centered display headline spanning roughly two thirds of the width. Below, a broad rounded film starts around the lower half of the viewport, inset 24px, and extends beyond the first 900px. Back-to-front layers are white canvas, contextual film, and live headline/navigation; the product is visible prominently in the film within the first screen. There is no large hero conversion button; playback and later actions carry the interaction. Introductory statement copy falls below the full film.

**Transfer:** Use a short welcoming product introduction plus a credible context image with one dominant subject. Without custom film, a contextual product photograph must carry equal scale. Editorial, recruiting and technical pages instead open with a nearly full-screen film inset 12px, 12px corners and a bottom-centered pair of statement-size lines, the second in muted white.

**Avoid:** Do not replace the opening with a two-column sales panel, a cluster of benefit badges or a generic gradient blob behind a product cutout.

**Text style:** `display` — sans 400 · 120px/1 · tracking -0.025em

### Broad statement and story card

**Observed:** A statement paragraph sits nearly full width with 24px padding. Below, a centered Outline card pairs a short body-small mission paragraph and a 440px-wide film thumbnail; large surrounding space keeps it editorial.

**Transfer:** State the everyday benefit plainly, then give the maker or method a small supporting proof card.

**Text style:** `statement` — sans 400 · 42px/1.15 · tracking -0.025em

### Spatial promise interlude

**Observed:** Warm editorial field carries Spatial promise lettering, followed by a centered-lead paragraph in a roughly 786px reading width.

**Transfer:** Use the separated phrase to turn an ordinary problem into an outcome, then explain the mechanism in one short paragraph.

**Text style:** `word-composition` — sans 400 · 104px/1 · tracking -0.025em

### Film-led capability

**Observed:** A near-full-width 16:9 contextual film carries a centered white film-heading. Below it, a tightly joined media-grid combines Explanation tile with one or two smaller uncut demonstrations. Small mono captions sit at image edges; outlined tiny autonomy and speed labels mark proof, not headline claims. Chapters finish with 160px of separation.

**Transfer:** Let each chapter prove one capability. Pair polished context footage with a quieter, literal demonstration of that same behavior.

**Text style:** `film-heading` — sans 400 · 84px/1.1 · tracking -0.025em

### Heading pair and explanation

**Observed:** A page-grid divides into equal halves: left has a section-heading title and immediately adjacent second line in secondary gray; right has a paragraph at the same scale. Sections typically use 96px vertical padding. Dark chapter reverses the same hierarchy into white and muted white.

**Transfer:** Use the first line for the claim, the second for the category, and the opposite column for the explanation. Keep this editorial hierarchy for deeper content.

**Text style:** `section-heading` — sans 400 · 24px/1.3 · tracking -0.025em

### Product detail rail

**Observed:** Detail stage holds a monumental-heading and a horizontal sequence of Tactile detail cards. Cards alternate narrow full-photo compositions and broad split layouts. A compact three-way mode pill is centered underneath for feature, rotation and anatomy views.

**Transfer:** Use a rail to reveal distinct qualities rather than repeat equal icon cards. Only expose view modes when they lead to real content.

**Text style:** `monumental-heading` — sans 400 · 142px/1 · tracking -0.025em

### Quiet closing invitation

**Observed:** A 450px charcoal band inset 24px with 12px corners centers a single compact row: white mono invitation, yellow support phrase and Inverse action. Editorial variants replace charcoal with darkened full-width human footage while preserving the small central text scale.

**Transfer:** Use one short invitation rather than enlarging the final call into another hero. Follow with Newsletter strip if updates are relevant.

**Text style:** `label` — mono 400 · 14px/1.2 · tracking 0.025em

### Footer and sun reveal

**Observed:** A light footer about 448px tall gives the left half to a descriptor and the right half to three link columns; legal links sit along the bottom. Rounded lower corners expose Sun reveal beneath. A 450px yellow field centers an everyday-life sign-off and three Outline action-shaped noninteractive pills for date, location and weather, then places a small solid symbol near the bottom. This ending is shared across all page types.

**Transfer:** Preserve the small-scale context and warm sign-off with your own local detail or relevant product status. Keep the pills informational, not three competing conversion buttons.

**Text style:** `label` — mono 400 · 14px/1.2 · tracking 0.025em

### Participation field

**Only for:** audience participation sections

**Observed:** A 600px pale blue band places two 24px questions on opposite sides of a centered bold symbol, with a compact black pill action below.

**Transfer:** For audience participation, frame one specific choice or request around the new product's own symbol or object.

**Text style:** `section-heading` — sans 400 · 24px/1.3 · tracking -0.025em

### Indexed technical reference

**Only for:** technical reference sections

**Observed:** A small left-side section index precedes a right-aligned 1038px content field. Technical panel groups hold an illustration beside specifications, paired orthographic drawings, ruled safety rows and a three-column glossary. Chapters separate with 128px bottom spacing.

**Transfer:** Use this denser variant when readers need inspection and assurance, not as the default landing-page body.

**Text style:** `editorial-caption` — sans 400 · 14px/1.4

## Page flow

**Storyline:** Welcome → everyday benefit → visible proof → mechanism and craft → reassurance → small invitation → humane sign-off.

### Product marketing landing page

1. **Promise** — Large centered greeting above contextual film, followed by a broad benefit statement.
2. **Capability proof** — Spatial promise interlude and film-led chapters with small literal demonstrations.
3. **Mechanism** — Isolated-object stage and centered explanation link benefit to underlying technology.
4. **Reassurance** — Tactile detail rail and ruled FAQ reduce uncertainty.
5. **Closing call** — Compact dark invitation, light newsletter strip, spacious footer and yellow context reveal.

**Transfer:** Choose the proof chapters appropriate to the product; preserve the contrast between cinematic scenes and tiny factual labels.

### Recruiting and opportunities page

1. **Invitation** — Full-screen candid workplace film with bottom-centered two-line title.
2. **Purpose** — Broad 42px editorial statement introduces the work.
3. **Available opportunities** — Cream field, left filters and grouped thin-rule role listings on the right.
4. **Alternate participation** — Darkened context-film band offers another contribution path.
5. **Closing call** — Dark newsletter strip, cream footer and the shared yellow reveal.

**Transfer:** Make the listing fast to scan and keep the surrounding imagery candid and human.

### Company narrative

1. **Identity** — Immersive human/product film and broad statement establish character.
2. **Credibility** — Loose photo strip and equal-half heading/explanation introduce the work.
3. **People** — Large portrait above compact paired biographies, then workplace film.
4. **Principles** — Ruled title-and-description rows aligned in the right half.
5. **Closing call** — Human-film recruiting invitation, light newsletter, white footer and shared yellow reveal.

**Transfer:** Use genuine people and a few plainly stated operating principles, not a dense trophy wall.

### Technical product explanation

1. **Technical promise** — Workshop-film opening leads into a black statement field and small research cards.
2. **Mechanism proof** — White heading pairs, paired demonstrations and narrow prose explain how the product works.
3. **Process** — Black chapter with a charcoal instrument dial and stage descriptions.
4. **Inspection** — Indexed specifications, line illustrations, safety rows and glossary give readers a reference layer.
5. **Closing call** — Dark context-film band, light newsletter, white footer and shared yellow reveal.

**Transfer:** Alternate intuitive evidence with inspectable detail; keep sustained dark treatments specific to mechanism chapters.

## Writing

Warm, matter-of-fact and optimistic about useful technology. Technical confidence is earned with observable behavior and simple explanations, while everyday benefits remain the point.

**Do not copy:** Do not reuse Sunday or Memo names, the flower-like brand mark, proprietary glove names, research names, founding-family language, performance claims, numerical achievements, biographies or slogans as new-product claims. Source examples illustrate voice only.

- **Addressing the reader:** Use you and your for everyday benefit, we for the makers' intent, and the product's name for concrete capabilities.
- **Rhythm:** Short welcoming headlines and direct chapter titles alternate with medium-length explanatory paragraphs. Tiny calls to action stay sentence case; compact fragments provide warmth without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | An everyday greeting introduces a named product without jargon. | 4–6 words | “Say hello to Memo” |
| Benefit statement | Name the audience and behavior, then connect it to regained attention or time. | Two sentences | “Built for busy households, Memo works 24/7 to make your life lighter. Hand off your repetitive to-do’s, so you can focus on what really matters.” |
| Capability headline | A literal subject-verb phrase makes the proof immediately legible. | 5–9 words | “Memo works in homes it's never seen” |
| Action | A modest verb names the next destination or contribution. | 1–3 words | “Explore Technology”<br>“Subscribe” |
| Technical positioning | Balance ambition with practical craft and human contribution. | Two short lines | “Pioneering AI, pragmatic engineering.”<br>“Powered by people.” |
| Principle | Plain spoken, concrete and slightly colloquial. | 1–6 words | “Solutions over methods”<br>“Hard things are hard” |
| Closing sign-off | A small ordinary-life observation quietly restates the emotional benefit. | Two short sentences | “The sun is out. The dishes can wait.” |

**Words and phrasing to use:** helpful; real life; works in yours; learns; hands off; time; everyday; from the lab to life

**Avoid:** disruptive ecosystem; supercharge everything; revolutionary magic; unparalleled synergy; buy now!!!

**Rules:**

- Make the chapter title understandable before explaining the technology.
- Use specific actions and conditions instead of an abstract list of superlatives.
- Translate technical mechanisms into ordinary consequences without pretending the engineering is effortless.
- Keep footer and conversion copy intimate and small, not urgent or promotional.

## Do's and Don'ts

### Do

- Keep large headings at weight 400 and -0.025em tracking.
- Use a 330px-wide floating navigation rather than stretching it across the page.
- Keep desktop outer gutters at 24px and joined media gaps at 8px.
- Use 12px corners on media and cards, reserving 24px for the broad detail stage.
- Pair a polished capability film with small factual proof and mono captions.
- Include the spatial promise and yellow context-sign-off devices using original language.
- Use 96px section breathing room and 160px after substantial media chapters.
- Let thin rules and flat fills provide structure without drop shadows.

### Don't

- Do not make all buttons black-filled; light-ground exploration defaults to a thin outlined pill.
- Do not uppercase the mono labels or enlarge them to compete with the narrative.
- Do not apply saturated yellow to every section or all card backgrounds.
- Do not turn natural interiors into glossy blue science-fiction environments.
- Do not turn compact 24px editorial section leads into repeated 84px display titles.
- Do not add floating shadow stacks to the flat 12px-radius cards.
- Do not make the yellow ending into a giant wordmark billboard; its sign-off and symbol remain small.
- Do not substitute a uniform icon-card grid for film-led proof and tactile details.

## Motion and responsive

### Motion

**Observed:**

- Declared action color transitions use .15s cubic-bezier(.4,0,.2,1); navigation uses 0.2s with the same curve.
- Declared section color changes use 0.3s cubic-bezier(.4,0,.2,1).
- Sticky headline staging, a horizontally advancing detail rail and a footer-underlayer reveal shape the long-scroll presentation.
- The technical process graphic has declared blinking and marching-ants animations.

**Transfer:**

- Retain the slow spatial reading of the word interlude and the footer reveal rather than replacing them with rapid slide carousels.
- Use the declared short color transitions for pill inversion; keep media as the primary source of movement.

**Unknown:**

- Exact scroll progress mapping, film playback logic and sequence timing are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 400px, 640px, 726px, 768px, 1024px, 1280px, 1536px, 1680px and 1792px.
- Layout declarations switch the editorial grid to full-span content below desktop and reduce outer padding from 24px to 16px in several sections.
- Action classes specify 36px height below the medium breakpoint; immersive editorial openings use a separate stacked layout at smaller widths.

**Transfer:**

- On narrow screens, stack heading pairs before explanations and let demonstration tiles follow their narrative tile.
- Reduce the spatial promise type enough to retain separated phrase groups without horizontal clipping; preserve the final word's contrasting alignment.
- Keep the yellow sign-off legible and compact, with context pills wrapping when needed.

**Unknown:**

- Exact mobile type sizes, menu-open composition and mobile behavior of the detail rail are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
