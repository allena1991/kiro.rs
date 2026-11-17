# Warp — executable field notes

## Overview

A light, technical style that feels like a working instrument rather than a glossy software brochure. Pale lavender paper, near-black lettering and concentrated electric blue surround semi-monospace headlines, fine ruled frames and live-looking diagrams. It suits developer tools and infrastructure products with substantial explanations, compact supporting copy and large, carefully staged demonstrations. Human photography supplies warmth in customer and company stories without changing the restrained technical tone.

### Essentials

- Headlines behave like typeset terminal prose: regular azeretSemiMono at 54px/1.05 with -2px tracking for the opening, then 34px/1.65 with the same tracking for chapters.
- The opening is a technical exhibit, not a floating app mockup: left-aligned two-line promise, 16px mono support, two 34px rectangular actions and a 1132px-wide ruled figure whose lower edge continues below the first screen.
- The page carries instrument markings: 11px uppercase eyebrows with 0.08em tracking, bracketed 10.5px figure captions with 0.1em tracking, hairline boundaries and tiny registration marks. Carry these devices into every new landing page.
- Color is concentrated into operational signals and one proof interruption: #fbf9fe and white dominate, #2a1eff marks active states and the 64px chapter bar, and a full-width blue proof band provides a deliberate exception to the pale page.
- Buttons are compact labels, not soft capsules: 4px corners, 6px 16px padding, 12px/1.65 uppercase mono lettering with 0.05em tracking; pair dark filled and white outlined versions.
- Imagery is nested inside an annotated apparatus: 1px dark outer frame, pale lavender backing, a 16px dot-grid inset and white inner content. Include a live-looking data field or process diagram; when there is no interface to show, construct a meaningful matrix of small status squares and a captioned legend.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#2a1eff` | `--color-blue` | accent, background, action, link | Active demonstrations, chapter navigation, hover accents and the saturated proof band. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Aubergine ink | `#1a1522` | `--color-ink` | text, border, action | Default headings, hard figure edges and primary action fills. |
| Secondary ink | `#706c76` | `--color-muted` | text | Visible secondary ink on lavender paper; use rgba(26,21,34,0.62) so it adapts to its backing. |
| Annotation gray | `#a19ea6` | `--color-faint` | text | Quiet captions and indices: rgba(26,21,34,0.4) over lavender paper. |
| Lavender hairline | `#d7d5db` | `--color-rule` | border | Visible dividers on lavender paper, made with rgba(26,21,34,0.16). |
| Figure lavender | `#f6f5fb` | `--color-panel` | surface | Outer demonstration frames and subdued hover fills. |
| Lavender paper | `#fbf9fe` | `--color-canvas` | background | Default marketing canvas. |
| White | `#ffffff` | `--color-white` | surface, text | Figure interiors, cards and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and recruitment pages | Lilac | `#cbb0f7` | `--color-lilac` | action, accent | Secondary navigation conversion action and featured-role treatments. |
| pricing pages | Lilac wash | `#f4f1fc` | `--color-purple-wash` | surface | Visible 15% #cbb0f7 over cool paper for product and billing selectors. |
| pricing and recruitment pages | Carbon | `#000102` | `--color-legacy-ink` | text, action | Grotesk headlines and square black buttons. |
| pricing and recruitment pages | Slate text | `#44494a` | `--color-legacy-secondary` | text | Body paragraphs and dense commercial detail. |
| pricing and recruitment pages | Slate edge | `#b3b8ba` | `--color-legacy-border` | border | Download boxes and job-list separators; reduce to 20% alpha in comparison tables. |
| pricing and recruitment pages | Ice gray | `#eaf0f2` | `--color-footer-wash` | background | Full-width commercial footer. |
| pricing and recruitment pages | Cool paper | `#fbfdfd` | `--color-legacy-canvas` | background | Cooler canvas for commercial and recruitment layouts. |

## Typography

- **azeretSemiMono** — Default marketing headlines, explanations, labels and navigation. Semi-monospace with broad terminal-like letterforms, softened by proportional rhythm and very tight headline spacing. If unavailable, use **Azeret Mono**. Use regular and medium weights; preserve tight headline tracking. Font stack: "azeretSemiMono", "Azeret Mono", ui-monospace, monospace.
- **theFuture** — Bold feature labels and proof headings; regular grotesk display for commercial and recruitment variants. Rounded geometric grotesk with single-storey forms and a direct, friendly technical character. If unavailable, use **Outfit**. Use 400 for display and 700 for compact feature labels. Font stack: "theFuture", "Outfit", system-ui, sans-serif.
- **Matter** (only for pricing and recruitment pages) — Prose, plan titles and price numerals. Unshowy contemporary sans with economical text proportions. If unavailable, use **Inter**. Font stack: "Matter", "Inter", system-ui, sans-serif.
- **matterMono** (only for pricing and recruitment pages) — Commercial action labels and recruitment benefits. Compact monospace with a strong administrative tone. If unavailable, use **Azeret Mono**. Font stack: "matterMono", "Azeret Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | azeretSemiMono | 400 | 54px | 1.05 | -2px | Default opening promise, wrapping to two lines. |
| heading | azeretSemiMono | 400 | 34px | 1.65 | -2px | Chapter headings. |
| stat | azeretSemiMono | 600 | 30px | 1.1 | 0.05em, uppercase | Numerical proof above small charts. |
| proof-heading | theFuture | 700 | 28px | 1.65 | -0.02em | White outcome headline on the blue proof band. |
| faq-heading | azeretSemiMono | 400 | 28px | 1.65 | -2px | Compact late-page question section. |
| feature-title | theFuture | 700 | 18px | 1.65 | -0.02em | Capability row titles; lowercase for ordinary phrases, retaining acronyms. |
| hero-support | azeretSemiMono | 400 | 16px | 1.65 | normal | Opening explanation. |
| faq-question | azeretSemiMono | 400 | 14px | 1.65 | normal, lowercase | Question labels in ruled accordion rows. |
| body | azeretSemiMono | 400 | 13.5px | 1.65 | normal | Section support lines. |
| card-body | azeretSemiMono | 400 | 12.5px | 1.65 | normal | Compact capability explanations. |
| button | azeretSemiMono | 500 | 12px | 1.65 | 0.05em, uppercase | Default conversion actions. |
| footer-link | azeretSemiMono | 400 | 12px | 1.65 | normal, lowercase | Small directory links. |
| eyebrow | azeretSemiMono | 500 | 11px | 1.65 | 0.08em, uppercase | Chapter labels and small online-status annotations. |
| tab | azeretSemiMono | 500 | 11px | 1.65 | 0.06em, uppercase | Demonstration chapter tabs. |
| figure-caption | azeretSemiMono | 400 | 10.5px | 1.65 | 0.1em | Bracketed figure labels, centered in thin frame bars. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and recruitment pages | commercial-display | theFuture | 400 | 72px | 1.1 | -0.035em | Openings with a plain commercial or recruitment promise. |
| pricing and recruitment pages | commercial-heading | theFuture | 400 | 50.4px | 1.25 | -0.035em | Large section leads. |
| pricing pages | price | Matter | 600 | 48px | 1 | -0.025em | Plan price or custom-price descriptor. |
| pricing pages | plan-title | Matter | 400 | 24px | 32px | -0.025em | Plan names. |
| pricing and recruitment pages | commercial-body | Matter | 400 | 16px | 1.5 | normal | Main explanatory prose. |
| pricing pages | plan-body | Matter | 400 | 14px | 24px | normal | Dense plan descriptions and benefit lists. |
| recruitment pages | benefit-title | matterMono | 600 | 14px | 2 | normal | Small benefits headings. |
| recruitment pages | benefit-body | matterMono | 400 | 14px | 2 | normal, uppercase | Matter-of-fact benefit details beneath their titles. |

**Notes:**

- Keep the default display regular rather than bold. The same -2px tracking gives the 34px chapter headings an unusually compressed texture.
- Use grotesk boldness for small feature titles and the blue proof statement, not for the main mono promise.
- Small explanations retain a 1.65 line-height even when set at 12.5px. Commercial pages instead use larger sans prose and more open display headings.
- Do not apply a fluid type formula to the desktop recipes; retain their relative hierarchy when adapting to narrow layouts.

## Layout

**Density:** Airy chapters around dense instrument panels: broad section padding surrounds compact labels, actions and explanatory text.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-label gap and feature-title-to-copy gap. |
| 10px | Chapter headline-to-support gap. |
| 12px | Small control and install-panel spacing. |
| 14px | Number-to-feature content and eyebrow-to-heading separation. |
| 16px | Paired actions and nested dot-field pitch. |
| 20px | Feature row and testimonial padding; wall gutters. |
| 24px | Container side padding and commercial card padding. |
| 32px | White inner proof-panel padding. |
| 40px | Two-column proof gap and opening text-to-figure separation. |
| 56px | Default chapter top and bottom padding. |
| 64px | Blue proof padding and commercial section rhythm. |

### Containers and grids

- **marketing-container**: max width 1180px · side padding 24px. Centered outer wrap; at 1440px the inner content spans 1132px. Align headings, figures and footer to this inner edge.
- **capability-split**: 2 columns · gap 0px. Equal-width numbered list and tall demonstration, enclosed by shared hairlines.
- **proof-split**: 2 columns · gap 40px. Vertically centered copy beside a light chart panel in the blue band.
- **product-grid**: 3 columns · gap 0px. Flush white columns with shared dividers and square media above descriptions and actions.
- **testimonial-wall**: 3 columns · gap 20px. Short quote cards of independent heights.
- **commercial-container** (only for pricing and recruitment pages): max width 1280px · side padding 40px. Centered 1200px inner content on desktop.
- **plans** (only for pricing pages): 3 columns · gap 8px. Three individual plans followed by a two-column organizational tier row.
- **commercial-faq** (only for pricing pages): max width 1024px · side padding 40px. A narrower 944px question list.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-small-cards | 4px |
|  | figure-frames | 0px |
|  | inner-proof-card | 6px |
| testimonial walls | avatars | 50% |
| pricing pages | billing-selector | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Lavender canvas · level 0

**Use:** Default landing-page field.

**CSS:** `background-color: #fbf9fe`

**Observed:** Faint dot texture and vertical alignment guides sit behind the content, strongest near the top. Most of the page remains pale.

**Transfer:** Keep decoration subordinate to the annotated frames.

#### Figure shell · level 1

**Use:** Major demonstrations and data illustrations.

**CSS:** `background-color: #f6f5fb; border: 1px solid #1a1522; border-radius: 0px; box-shadow: none`

**Observed:** A slim caption bar separates the outer frame from the inset dot-grid well.

**Transfer:** Frame a real interface or purpose-built diagram as an exhibit.

#### Dot-grid well · level 2

**Use:** Backing inside Figure shell.

**CSS:** `background-color: #ffffff; background-image: radial-gradient(circle at 1px 1px, rgba(26,21,34,0.16) 1.2px, rgba(0,0,0,0) 0px); background-size: 16px 16px; border: 1px solid #1a1522; padding: 18px; margin: 0px 14px 14px`

**Observed:** A white inner content panel hides most dots; the pattern survives as a technical mat around it.

**Transfer:** Use the grid as backing, not as interference over detailed interface text.

#### White content panel · level 3

**Use:** Data, process and proof within framed demonstrations.

**CSS:** `background-color: #ffffff; border: 1px solid rgba(0,0,0,0.1); border-radius: 6px; padding: 32px`

**Observed:** Very little depth; hierarchy comes from nested rules rather than shadows.

**Transfer:** Group related measurements in a shared panel.

#### Blue proof field · level 0

**Use:** High-contrast outcome story.

**CSS:** `background-color: #2a1eff; background-image: radial-gradient(circle at 1px 1px, rgba(255,255,255,0.18) 1.2px, rgba(0,0,0,0) 0px); background-size: 26px 26px; padding: 64px 0px; color: #ffffff`

**Observed:** A full-width interruption, not a small colored card.

**Transfer:** Reserve this field for one particularly concrete piece of proof.

#### Commercial canvas · level 0

**Only for:** pricing and recruitment pages

**Use:** Plain cool-white page variant.

**CSS:** `background-color: #fbfdfd; color: #000102`

**Observed:** No elaborate technical figure system around every section; photography and sans headings lead.

**Transfer:** Use this quieter variant for transactional and organizational content.

#### Commercial footer field · level 0

**Only for:** pricing and recruitment pages

**Use:** Broad closing directory.

**CSS:** `background-color: #eaf0f2; padding: 32px 0px 64px`

**Observed:** Five columns above legal, certification and status information.

**Transfer:** Keep the lighter commercial ending distinct from the compact mono footer.

## Components

### Primary button

**Use:** Main landing-page conversion action.

**CSS:** `display: flex; align-items: center; gap: 6px; background: #1a1522; color: #ffffff; border: 1px solid #1a1522; border-radius: 4px; padding: 6px 16px; height: 34px; box-sizing: border-box`

**Text style:** `button` — azeretSemiMono 500 · 12px/1.65 · tracking 0.05em · uppercase

**Observed:** Sits first in a left-aligned action pair. Product-choice cards stretch it across their text area.

**States:** Declared: hover background and border #2a1eff, text #ffffff.

**Transfer:** Use one short imperative appropriate to the product.

### Secondary button

**Use:** Parallel lower-commitment action and story links.

**CSS:** `display: flex; align-items: center; gap: 6px; background: #ffffff; color: #1a1522; border: 1px solid rgba(26,21,34,0.16); border-radius: 4px; padding: 6px 16px; height: 34px; box-sizing: border-box`

**Text style:** `button` — azeretSemiMono 500 · 12px/1.65 · tracking 0.05em · uppercase

**Observed:** Paired with Primary button or placed under a customer story. The reversed version on Blue proof field is white with blue lettering.

**States:** Declared: hover border and text #2a1eff.

### Chapter navigation

**Use:** Persistent orientation on long product stories.

**CSS:** `position: fixed; height: 64px; background: #2a1eff; color: #ffffff; z-index: 6`

**Observed:** Replaces the white logo-and-menu header after the opening. Small section links are preceded by outlined keyboard-like keycaps; a white action stays at the right. The link row uses 20px gaps inside the marketing container.

**Transfer:** Use concise chapter names and maintain one conversion action.

### Figure caption bar

**Use:** Labeling the demonstration as an annotated exhibit.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 14px; padding: 8px 12px; background: #ffffff; border-bottom: 1px solid rgba(26,21,34,0.16)`

**Text style:** `figure-caption` — azeretSemiMono 400 · 10.5px/1.65 · tracking 0.1em

**Observed:** Centered bracketed title between tiny outlined terminal and grid symbols.

**Transfer:** Number meaningful diagrams and name what is being demonstrated.

### Demonstration tab

**Use:** Switching between aspects of a technical exhibit.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 44px; padding: 0px 18px; background: #2a1eff; color: #ffffff; border-radius: 0px`

**Text style:** `tab` — azeretSemiMono 500 · 11px/1.65 · tracking 0.06em · uppercase

**Observed:** Selected tab is blue; inactive tabs are white with gray text and shared vertical rules. The tab strip spans wider than the normal text inset.

**States:** Declared: hover background #f6f5fb and text #1a1522; focus-visible outline 2px solid #2a1eff with -3px offset.

### Numbered capability row

**Use:** Pairing a compact explanation with a shared demonstration.

**CSS:** `display: flex; gap: 14px; padding: 20px; background: linear-gradient(rgba(26,21,34,0.07), rgba(26,21,34,0.07)) #ffffff`

**Text style:** `feature-title` — theFuture 700 · 18px/1.65 · tracking -0.02em

**Observed:** A faint two-digit index sits left of the bold title; Card-body follows with a 6px gap. Selected row has the gray overlay; other rows are white, separated by hairlines.

**States:** Declared: hover uses the same 7% ink overlay over white.

**Transfer:** Keep explanations specific enough to justify the neighboring demonstration.

### FAQ row

**Use:** Late-page objection handling.

**CSS:** `display: flex; justify-content: space-between; gap: 20px; padding: 14px 4px; color: #1a1522; background: transparent`

**Text style:** `faq-question` — azeretSemiMono 400 · 14px/1.65 · lowercase

**Observed:** Each row belongs to a full-width item with a 1px top rule. A small blue prompt marker introduces the question, and a faint bracketed plus sits at the right; answers indent beneath the question.

**Transfer:** Use practical questions, not promotional mini-headlines.

### Footer directory link

**Use:** Low-emphasis navigation at the page ending.

**CSS:** `display: block; padding: 3px 0px; color: rgba(26,21,34,0.62)`

**Text style:** `footer-link` — azeretSemiMono 400 · 12px/1.65 · lowercase

**Observed:** The compact footer has six columns: a small emblem and descriptor plus five link groups. Muted lowercase headings sit above links; a thin rule separates the final legal line.

**States:** Declared: hover text #2a1eff.

### Testimonial card

**Only for:** customer quote walls

**Use:** Dense first-person social proof.

**CSS:** `background: #ffffff; border: 1px solid rgba(26,21,34,0.16); border-radius: 4px; padding: 20px; margin-bottom: 20px`

**Observed:** Round avatar, bold author and muted handle precede a small mono quotation. Three masonry-like columns produce uneven bottoms rather than equal-height boxes.

**Transfer:** Use short, attributable experiences with concrete circumstances.

### Plan card

**Only for:** pricing pages

**Use:** Comparing purchase options.

**CSS:** `display: grid; gap: 24px; background: #ffffff; border-radius: 4px; padding: 24px`

**Text style:** `plan-title` — Matter 400 · 24px/32px · tracking -0.025em

**Observed:** Plan name and optional recommendation badge lead, then billing controls, a Price numeral, audience description, full-width black action and an open-circle benefit list. Additional-usage action sits near the base; shared row alignment keeps plans comparable.

**Transfer:** Explain who each option serves before listing differences.

### Install command

**Only for:** download-oriented sections

**Use:** Direct installation alongside platform choices.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; background: #ffffff; border: 1px solid rgba(26,21,34,0.16); border-radius: 4px; padding: 0px 20px; height: 48px`

**Observed:** Faint dollar prompt at the left, a single mono command and a compact copy icon at the right. Platform tabs sit beneath, divided by slashes; commercial download grids use taller command boxes with slate edges.

**Transfer:** Keep the command selectable and make the copy action visually secondary.

## Imagery and graphics

### Operational square field

**Use:** Signature first-screen product demonstration.

**Observed:** A broad white panel contains an orderly matrix of tiny gray squares, a few blue active squares and pale lilac states. Small technical labels occupy the upper corners; a bottom rule separates a compact legend and running totals. The large panel dominates the opening below the text.

**Transfer:** Represent the new product's objects, jobs or stages as a status field. With no real UI, use a legible process matrix with honest example states rather than a generic dashboard.

**Build:** Inside White content panel, make a CSS grid of 28 columns and 8 rows with small square cells. Use rgba(26,21,34,0.16) for most cells, #2a1eff for a sparse active subset and rgba(42,30,255,0.3) for waiting cells; outline completed cells instead of filling them. Give the field substantial white margins and add a thin legend rule beneath it.

### Technical paper markings

**Use:** Persistent signature framing around the marketing narrative.

**Observed:** Pale dot texture and vertical rules give the canvas a drafting-sheet quality. Tiny black registration blocks touch the side edges at chapter transitions; vertical margin notes read like instrument metadata.

**Transfer:** Use new product metadata or neutral edition labels and keep marks outside the reading column.

**Build:** Place a pointer-events:none overlay on Lavender canvas using radial-gradient(circle at 1px 1px, rgba(26,21,34,0.07) 1px, transparent 0) at 22px 22px. Fade it vertically. Add low-alpha 1px vertical SVG rules aligned to container divisions and short dark rectangular registration ticks on section boundaries. Set side annotations in 9px mono with about 2px tracking, rotated vertically.

### Interface exhibits

**Use:** Capability sections and product-choice media.

**Observed:** Real dark terminal and editor windows are isolated against sage-gray textured boards or pale lilac dot fields. Another product tile arranges white metric cards over a vivid blue tiled backing. Windows remain mostly front-facing, with large margins and little decorative perspective.

**Transfer:** Show a few convincing states of the actual product; frame and back them consistently rather than fabricating elaborate UI.

**Build:** Use a square or tall rectangular panel with a desaturated sage photograph or pale lilac backing, add subtle noise with a low-opacity SVG turbulence layer, then center a flat interface image with broad margins. For a metric-led alternative, place thin dark-bordered white charts over a simple blue orthogonal grid; keep this stronger color contained to the media area.

### Proof charts

**Use:** Quantified outcomes within technical figures and the blue band.

**Observed:** Compact 30px mono statistics sit above fine line charts, run logs and separated columns. The blue band's right half holds a white scatter-chart panel on a broad pale mat; its left half carries the outcome and action.

**Transfer:** Use a real benchmark, time series or before-and-after result. Retain annotation density without enlarging chart internals into marketing headlines.

### Customer story covers

**Use:** Paired case-study cards.

**Observed:** Square photographs of hands, desks and laptops are softly blurred, warm and slightly desaturated. White customer marks are centered over the scene; bold small captions and mono summaries sit below, outside the image.

**Transfer:** Use authentic contextual photography with a plain project or customer title; keep the soft photographic treatment and flat square framing.

### Workplace and photo-interface collage

**Only for:** pricing and recruitment pages

**Use:** Human warmth around culture, integrations and trust explanations.

**Observed:** Recruitment uses a wide daylight overhead workplace video poster, huge white title lettering and a centered round play button. Commercial feature chapters use square darkened photos of hands or laptops with crisp white UI fragments or a certification emblem layered on top.

**Transfer:** Use lived-in work scenes, natural light and cropped human gestures. Overlay only the one interface exchange or credential that explains the adjacent claim.

### Icons

**Observed:** Small monochrome filled icons generally measure 14px or 16px. Technical figures use tiny outlined terminal/grid glyphs in rectangular boxes; security illustrations use simple line symbols inside thin circles. Larger operating-system silhouettes identify download columns.

**Transfer:** Use compact functional silhouettes and text-like diagram symbols, not colorful decorative icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Annotated product opening

**Observed:** A white 64px global header sits above a white-to-lavender field with faint grid markings. In a centered 1180px wrap with 24px insets, the left-aligned Display promise spans roughly two-thirds of the available width over two lines. Hero-support follows after 18px, then Primary button and Secondary button after 26px with a 16px gap. About 40px below the actions, a 1132px-wide Figure shell begins with its thin caption bar and nested Operational square field. Within the first 900px the entire promise, support and actions are visible plus most of the main data exhibit; its lower border and following trust strip lie below the fold. Layers run from pale paper and drafting marks to dark type, compact actions, outer shell, dotted well and white status panel.

**Transfer:** Lead with a specific product category and benefit, then build an equally substantial annotated process scene if no interface is available. Download-led product pages can center the same 54px headline and replace the action pair with Install command; commercial pages open with 72px grotesk display, while recruitment aligns that display left above a broad workplace video.

**Avoid:** Do not replace the exhibit with a small floating laptop, center the default headline or turn the first screen into a dark gradient splash.

**Text style:** `display` — azeretSemiMono 400 · 54px/1.05 · tracking -2px

### Chapter heading pair

**Observed:** Default chapters use 56px vertical padding and a full-width bottom hairline. Eyebrow precedes Heading by about 14px; Body follows by 10px. Labels often include a hash-like prefix and a small online-status suffix.

**Transfer:** Name a technical idea in the label, explain its payoff in the headline and use one support line before the demonstration.

**Text style:** `heading` — azeretSemiMono 400 · 34px/1.65 · tracking -2px

### Tabbed technical explorer

**Observed:** A chapter heading and right-aligned Secondary button lead a full-width strip of Demonstration tabs. A white explanatory area precedes a nested file-tree-and-code figure. Selected tabs and selected files use blue; rules, not shadows, organize the layers.

**Transfer:** Adapt to product architecture, workflows or editable settings, keeping one concrete example per tab.

### Numbered capability split

**Observed:** A two-column shared frame pairs a vertical stack of Numbered capability rows with one tall media panel. The list and media are each about 565px wide; selected gray row corresponds to the demonstration. Small indices establish reading order without becoming decorative statistics.

**Transfer:** Use for related capabilities that share one interface or process; update the demonstration when the row changes.

### Quantified instrument panel

**Observed:** Figure shell and Dot-grid well surround a white three-column measurement panel. Each column combines a small label, Stat numeral, thin chart and tiny ruled run log. Columns have shared vertical dividers and 20px side padding.

**Transfer:** Combine three complementary measures of the same outcome rather than unrelated vanity counters.

**Text style:** `stat` — azeretSemiMono 600 · 30px/1.1 · tracking 0.05em · uppercase

### Electric proof interruption

**Observed:** Blue proof field carries a two-column 40px-gap layout, with white eyebrow, Proof-heading, pale support and a white action on the left. A roughly 544px by 340px chart on a pale mat occupies the right. The band is about 471px tall.

**Transfer:** Include this saturated proof device in the new narrative wherever a specific outcome deserves emphasis; adapt its location to the story.

**Text style:** `proof-heading` — theFuture 700 · 28px/1.65 · tracking -0.02em

### Customer evidence pair

**Observed:** Two equal square photo covers with a small gutter sit beneath the chapter lead. Each cover is followed by a bold compact title, muted mono explanation and Secondary button.

**Transfer:** Pair two materially different customer contexts rather than repeating the same claim.

### Product-choice closing

**Observed:** A compact heading and blue support line lead three flush white columns with square media, short description and different action mechanisms. The options finish before a ruled FAQ, then the compact six-column footer. There is no monumental closing headline.

**Transfer:** Offer relevant ways to use, try or adopt the product; do not force three product names when the offering has one. Preserve the direct adoption choices and low-key directory ending.

### Security cell grid

**Observed:** Six white cells share thin dividers in three columns and two rows. Small outlined circular icons sit above bold titles and compact mono explanations. It is the final substantive chapter before the compact footer on the download-led product variant.

**Transfer:** Use for concrete organizational assurances or operational safeguards, keeping claims short and verifiable.

### Commercial detail and ending

**Observed:** Cool paper supports 50.4px regular grotesk headings, 16px sans prose and 64px section rhythm. Alternating square photograph/interface collages sit beside explanations. Pricing ends with a 944px FAQ, centered sales-and-documentation invitation, a three-platform download grid, then a five-column Ice gray footer; recruitment moves from benefits to ruled job rows, the same download grid and footer.

**Transfer:** For transaction-heavy pages, trade the drafting-sheet apparatus for clear comparison and human context while preserving compact rectangular actions.

**Text style:** `commercial-heading` — theFuture 400 · 50.4px/1.25 · tracking -0.035em

## Page flow

**Storyline:** Promise → substantial demonstration → capability explanation → measurable or human proof → control and trust → adoption choices and practical questions → restrained directory.

### Platform marketing landing page

1. **Promise** — Left-aligned mono headline and paired actions over a framed live-looking status field.
2. **Social proof** — Slim muted customer and partner strip.
3. **Product demonstration** — Tabbed technical configuration explorer.
4. **Capability chapters** — Numbered split list, three-column measurement panel and layered architecture diagram.
5. **Quantified proof** — Electric-blue outcome story with a chart, followed by two photo-led customer stories.
6. **Trust** — Annotated governance demonstration.
7. **Adoption and objections** — Flush product-choice grid followed by compact ruled questions.
8. **Directory** — Six-column mono footer with a small emblem and final legal rule.

**Transfer:** Keep a substantial working exhibit and an electric proof interruption, arranging technical chapters according to the new product's explanation needs.

### Download-led product landing page

1. **Promise** — Centered mono headline and install command with platform choices.
2. **Demonstration** — Narrow explanatory column beside a framed video.
3. **Capabilities** — Numbered list plus tall interface media, then a broad integration/model graphic with four compact captions.
4. **Social proof** — Three-column short-quote wall.
5. **Trust** — Six-cell security grid.
6. **Directory** — Compact mono footer directly after the assurance grid.

**Transfer:** Let immediate installation drive the opening and let short demonstrations answer workflow questions; end with assurances rather than inserting an unrelated final sales splash.

### Recruitment page

1. **Promise** — Large left-aligned grotesk invitation and black roles action.
2. **Human context** — Wide daylight workplace video poster.
3. **Practical value** — Three-column icon-led benefits with mono uppercase detail.
4. **Selection** — Ruled job rows with one softly lilac featured entry.
5. **Adoption and directory** — Three-platform download grid and wide cool-gray footer.

**Transfer:** Move from a human invitation to concrete benefits and actionable listings; retain this page type's airy sans treatment.

### Commercial comparison page

1. **Orientation** — Two-product selector above centered grotesk display.
2. **Pricing** — Three individual plan cards followed by two organizational plans.
3. **Comparison** — Long five-plan matrix with a pinned plan/action header, 14px detail, faint row rules and lilac check marks.
4. **Capability and trust** — Alternating photo/interface feature chapters followed by a security explanation.
5. **Objection handling** — Narrow ruled FAQ and centered two-action help invitation.
6. **Adoption and directory** — Platform downloads followed by five-column cool-gray footer.

**Transfer:** Separate quick plan selection from exhaustive comparison; support the decision with examples and end with direct help rather than repeating the pricing grid.

## Writing

Confident, technically literate and matter-of-fact. The language favors specific workflows, configuration choices and measurable outcomes over inflated category claims; warmth appears in direct invitations and first-person customer experiences.

**Do not copy:** Do not reuse Warp names, logos, customer marks, proprietary product terminology, quotations, security claims, benchmark results, adoption counts, prices or installation commands. Substitute truthful content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address practitioners as you and teams as your team. Use we for company explanations and first-person results; product statements can simply name what the tool does.
- **Rhythm:** Headlines are concise but can carry a full technical proposition. Follow with one compact support sentence; reserve longer paragraphs for decision-making detail. Lowercase wording is common in default feature and FAQ labels, while acronyms keep their conventional form.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the category and who or what it serves, without metaphor. | 6–13 words | “Open infrastructure for cloud software factories”<br>“A coding agent for engineers who live in the terminal” |
| Chapter headline | State a concrete capability or control in plain operational terms. | 4–10 words | “Your software factory, defined in code.”<br>“Build, review, and ship in one surface” |
| Support line | List the meaningful mechanisms, then tie them to an outcome. | 10–25 words | “evals, benchmarks, and self-improvement loops drive measurable gains.” |
| Outcome proof | Describe a before-and-after result in the headline. | 7–14 words | “Cutting our cost per PR from $80 to $30” |
| Action | A concrete verb plus the object or next step. | 2–4 words | “request early access”<br>“View open roles” |
| Question | Ask the practical adoption question in the reader's own terms. | 4–12 words | “can we start small?”<br>“How is agent usage billed?” |

**Words and phrasing to use:** defined in code; built in; control; configure; your team; workflow; measure; run; review; bring your own

**Avoid:** magic; revolutionary; unleash limitless potential; effortless everything; vague transformation promises

**Rules:**

- Prefer verbs describing observable work over broad productivity adjectives.
- Follow claims with mechanisms, controls or measured results.
- Keep technical nouns when they genuinely distinguish the product; explain the relationship rather than stripping the sentence of meaning.
- Use terse figure titles and calm imperative actions, not exclamation-heavy enthusiasm.

## Do's and Don'ts

### Do

- Keep default display type at 54px regular with -2px tracking.
- Align ordinary chapters to the 1132px inner content width.
- Use 56px chapter padding and 1px shared boundaries.
- Set small supporting mono text at 1.65 line-height.
- Keep the default action pair at 34px tall with 4px corners.
- Use the blue proof field as a strong full-width interruption.
- Stage interface content inside a dark-edged figure and dotted inset.
- Finish with adoption choices, practical questions or concrete assurances and a compact directory.

### Don't

- Do not make every card blue; large blue fills belong to the chapter bar and proof interruption.
- Do not turn all headings into 700-weight geometric sans; regular semi-mono is the default display voice.
- Do not use 16px body copy everywhere; default feature descriptions are 12.5px.
- Do not replace 4px action corners with pill buttons.
- Do not add broad drop shadows to the nested figures; their hierarchy is ruled and flat.
- Do not turn tiny indices into giant decorative background numbers.
- Do not use glossy tilted device renders as the standard imagery treatment.
- Do not import the 72px commercial headline and ice-gray footer into every product landing page.

## Motion and responsive

### Motion

**Observed:**

- Action borders, colors and backgrounds use 0.15s transitions; demonstration tabs use 0.12s background and color transitions.
- The chapter navigation declares a 0.25s transform transition.
- Continuous marquees declare 38s linear loops, with another product marquee at 26s; small pulse indicators declare 2s loops.

**Transfer:**

- Let blue active states and the chapter-bar swap provide the principal sense of a working instrument.
- If animating a process field, preserve its orderly grid and clear status legend rather than introducing free-floating particles.

**Unknown:**

- Exact scroll activation thresholds, scene animation sequencing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Product layouts declare breakpoints at 400px, 540px, 640px, 760px, 768px, 860px, 861px, 1024px, 1180px and 1280px, with additional wide-screen rules.
- Commercial layout classes specify one-column grids by default, two columns from the small breakpoint and three at the large breakpoint; side insets move from 24px to 40px.

**Transfer:**

- On narrow layouts, retain the figure caption, inset backing and meaningful status legend; reduce the matrix's column count rather than shrinking all content into unreadable miniatures.
- Stack capability explanations with their corresponding media and allow chapter links to scroll horizontally.
- Keep download platform options distinct when their three-column presentation stacks.

**Unknown:**

- Mobile typography sizes, actual narrow-screen navigation behavior and precise diagram rearrangements remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
