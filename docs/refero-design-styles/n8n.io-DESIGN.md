# n8n — soft machinery, human control

## Overview

A light, technical marketing style with the friendliness of a working studio rather than the spectacle of futuristic AI. Near-white and charcoal dominate, with blush pink controls, compact grotesk headlines and uppercase monospace labels. Dotted work surfaces, readable interface diagrams, pixel-built symbols and candid workplace photography balance technical density with human warmth.

### Essentials

- Compressed promises above an open workbench: centered 64px/0.85 medium grotesk headlines with -0.01em tracking, 18px/22px support and a small working product scene below, all on a pale dotted field.
- Controls feel like soft equipment labels: 42px-high pill buttons use 14px/18px uppercase mono with 0.02em tracking, 12px 16px padding and blush pink for the primary action.
- Color marks decisions, not whole chapters: the overwhelming majority of the page stays #fafafa and neutral grays; #ffbcca is concentrated in actions and selected capsules, with #ff91ac in small markers and emphasis.
- Technical proof lives on dark work surfaces: #212121 panels with 24px corners stage connected modules and fine dots; retain a diagram or simplified real interface rather than substituting decorative abstract AI art.
- The dotted grid becomes a visual language: carry it through the opening, headline backplates and the 480px-deep footer field; include a pixel-built capability symbol made of separated rounded squares.
- A human-scale finish balances the machinery: a 48px/1 centered closing promise on dots faces a 688px-wide candid work photograph, followed by a dark inset footer with 24px corners. Use an authentic task or workspace photograph when no product-specific people imagery exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blush control | `#ffbcca` | `--color-pink` | action, accent | Primary buttons and selected capsule labels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Active pink | `#ff91ac` | `--color-pink-strong` | accent, text, action | Primary hover fill, label endpoint dots, small proof markers and selected phrases. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#161616` | `--color-ink` | text | Primary headings, body and secondary-action text. |
| Workbench charcoal | `#212121` | `--color-charcoal` | background, surface, text | Product stages, capability cards, footer and primary-button text. |
| Secondary charcoal | `#303030` | `--color-raised-dark` | surface, accent | Quote cards, dark table headers and footer dots. |
| Dark separator | `#474747` | `--color-edge` | border, surface | Rules in dark comparisons, inactive dark pills and small footer badges. |
| Secondary copy | `#616161` | `--color-muted` | text | Attributions and inactive chapter labels. |
| Subtle link gray | `#8f8f8f` | `--color-subtle` | text, border | Low-emphasis links against dark surfaces. |
| Mid-light gray | `#d9d9d9` | `--color-card` | surface, border, action | Secondary buttons, support panels and fine separators on light sections. |
| Soft gray | `#f0f0f0` | `--color-soft` | surface | Navigation capsule, quote cards, plan cards and FAQ rows. |
| Near-white canvas | `#fafafa` | `--color-canvas` | background, text | Default page canvas and inverse text on charcoal. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| long-form customer stories | Article pink | `#ef3a7a` | `--color-article-link` | link | Underlined inline editorial links. |
| feature collections and product detail pages | Widget gray | `#e6e6e6` | `--color-widget` | surface | Large inset capability collections and alternate secondary buttons. |

## Typography

- **n8n Baumer Uniwidth** — All marketing headings, descriptions, prices and quotes. Compact contemporary grotesk with friendly open forms; medium rather than bold headlines. If unavailable, use **Inter**. Use 400 and 500; retain tight display line spacing and tracking. Font stack: "n8n Baumer Uniwidth", "Inter", Helvetica, system-ui, -apple-system, sans-serif.
- **n8n Baumer Mono** — Navigation, buttons, eyebrows, capsules and comparison values. Plain technical monospace, mostly uppercase, with gently spaced labels. If unavailable, use **IBM Plex Mono**. Use regular weight and 0.02em tracking for labels. Font stack: "n8n Baumer Mono", "IBM Plex Mono", ui-monospace, "SF Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | n8n Baumer Uniwidth | 500 | 64px | 0.85 | -0.01em | Default landing-page opening promise, usually split into two tightly stacked lines. |
| heading-xl | n8n Baumer Uniwidth | 500 | 48px | 1 | -0.01em | Centered chapter introductions, photo pairings and closing promises. |
| heading-lg | n8n Baumer Uniwidth | 500 | 40px | 1.05 | -0.01em | Left-aligned feature chapters and dark use-case panel headlines. |
| quote | n8n Baumer Uniwidth | 500 | 32px | 1.125 | normal | Text-only testimonial cards and substantial supporting statements. |
| heading-sm | n8n Baumer Uniwidth | 500 | 24px | 1 | normal | Feature selectors and compact card titles. |
| lead | n8n Baumer Uniwidth | 400 | 18px | 22px | normal | Opening support paragraphs. |
| body | n8n Baumer Uniwidth | 400 | 16px | 1.25 | normal | Default marketing paragraphs, FAQ questions and feature descriptions. |
| card-label | n8n Baumer Uniwidth | 500 | 16px | 1.25 | normal | Small titles below capability illustrations. |
| caption | n8n Baumer Uniwidth | 400 | 14px | 18px | normal | Compact card descriptions and testimonial attributions. |
| action-label | n8n Baumer Mono | 400 | 14px | 18px | 0.02em, uppercase | Buttons, navigation, eyebrow capsules and footer column links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing, feature index, product detail and customer story openings | compact-display | n8n Baumer Uniwidth | 500 | 56px | 1 | -0.01em | Short centered opening headings; customer stories highlight a short phrase in pink. |
| long-form customer stories | article-link | n8n Baumer Uniwidth | 500 | 18px | 22px | normal | Inline underlined links and emphasized article phrases. |

**Notes:**

- Use medium weight 500 to create authority without heavy bold. Display tracking is consistently -0.01em; smaller headings return to normal tracking.
- The 64px opening has deliberately tighter leading than the 56px and 48px headings. Keep clear 24px support gaps so the compressed heading remains readable.
- Mono is a labeling system, not the body font. Long-form stories reuse the 18px/22px lead and 32px/36px quote recipes for article body and section headings.

## Layout

**Density:** Airy at section scale, compact inside controls and information cards; long technical demonstrations are given their own reading room.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Dominant horizontal padding and gutter rhythm; 12px control gaps are a deliberate smaller exception.

| Value | Use |
| --- | --- |
| 8px | Tight icon gaps and compact collection gutters. |
| 12px | Button pair gaps and capsule-to-copy intervals. |
| 16px | Main grid gutters, heading-to-body gaps and card side padding. |
| 24px | Page edges, default card padding and centered heading support gaps. |
| 32px | Large card padding and text-only quote insets. |
| 48px | Logo-strip vertical padding and broad heading-to-support separation. |
| 64px | Centered section introduction to card collection. |
| 96px | Default major section vertical padding. |

### Containers and grids

- **wide**: max width 1392px · side padding 24px. Wide stage, photo splits and large feature bands centered on the page.
- **default**: max width 1190px · side padding 24px. Dark use-case panels, proof pairs and enterprise grids.
- **copy**: max width 800px · side padding 24px. Centered introductory support text; actual line length remains much narrower when copy is short.
- **faq**: max width 788px · side padding 24px. Single centered column of accordion questions.
- **photo split**: max width 1392px · 2 columns · gap 16px. Equal 688px desktop halves; one centered statement and one photograph or demonstration.
- **capability grid**: max width 1190px · 4 columns · gap 16px. Four 286px-wide dark cards with square illustration areas.
- **chapter showcase**: max width 1392px · 2 columns · gap 16px. A narrow left explanatory rail with 360px selectors beside an 875px-wide media stage; the left structural column is 453px.
- **article** (only for long-form customer stories): max width 1190px · 2 columns · gap 32px. A narrow left facts rail and a 772px reading column on the right; article text is not centered.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 9999px (pill) |
|  | panels and cards | 24px |
|  | small utility badges | 4px |
| feature collections | embossed cells | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| feature collections | shallow emboss | `3px 3px 6px 0px rgba(0,0,0,0.1) inset, -3px -3px 6px 0px rgba(255,255,255,0.6) inset` | Shallow recessed cells with light from the upper-left shadow edge and a bright lower-right edge. |

### Surfaces

#### Canvas · level 0

**Use:** Default light page.

**CSS:** `background: #fafafa; color: #161616`

#### Soft card · level 1

**Use:** Grouped supporting copy, plans, FAQ rows and quotes.

**CSS:** `background: #f0f0f0; border-radius: 24px; box-shadow: none`

**Observed:** Flat solid fill rather than a floating white card with a drop shadow.

**Transfer:** Use neutral tonal differences to group content.

#### Dark workbench · level 1

**Use:** Product demonstrations, dark capability cards and footer.

**CSS:** `background: #212121; color: #fafafa; border-radius: 24px`

**Observed:** Dotted media areas sit inside the charcoal silhouette; surrounding page remains light.

**Transfer:** Show useful process detail with enough contrast to read the major objects.

#### Support inset · level 1

**Use:** A small explanatory block beneath a dotted headline beside a photograph.

**CSS:** `background: #d9d9d9; border-radius: 24px; padding: 32px`

**Observed:** Often aligned to the right side of the text half instead of filling its entire width.

**Transfer:** Keep support subordinate to the headline and media.

#### Footer dot field · level 1

**Use:** The broad low-contrast technical field in the footer.

**CSS:** `background-image: radial-gradient(circle, #303030 2px, rgba(0,0,0,0) 2px); background-size: 24px 24px; height: 480px`

**Observed:** Dots sit over Dark workbench between the upper navigation group and the bottom utility row.

**Transfer:** Preserve this spacious graphic punctuation without adding a giant headline.

#### Widget band · level 1

**Only for:** feature collections and product detail pages

**Use:** Broad inset panel grouping related capabilities.

**CSS:** `background: #e6e6e6; border-radius: 24px`

**Observed:** Small registration-cross details can sit just outside the corners; tightly fitted internal cells contrast with generous page spacing.

**Transfer:** Use as a bounded comparison or capability collection, not the global page background.

#### Embossed cell · level 2

**Only for:** feature collections

**Use:** Recessed neutral cards within Widget band.

**CSS:** `border-radius: 16px; box-shadow: 3px 3px 6px 0px rgba(0,0,0,0.1) inset, -3px -3px 6px 0px rgba(255,255,255,0.6) inset`

**Observed:** The cell shares its parent's tone; subtle opposing inset shadows make the edge visible.

**Transfer:** Reserve the effect for technical collections rather than every card.

## Components

### Navigation capsule

**Use:** Fixed global navigation above all page types.

**CSS:** `background: #f0f0f0; border-radius: 9999px; height: 50px; padding: 4px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `action-label` — n8n Baumer Mono 400 · 14px/18px · tracking 0.02em · uppercase

**Observed:** An inset horizontal bar, 1344px wide at desktop, sits 12px from the top. Brand left, menu links in the center, sign-in and Primary button right. Small dotted chevrons mark expandable labels.

**Transfer:** Keep the bar light even when it crosses dark sections.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #ffbcca; color: #212121; border-radius: 9999px; padding: 12px 16px; height: 42px; display: flex; align-items: center; justify-content: center`

**Text style:** `action-label` — n8n Baumer Mono 400 · 14px/18px · tracking 0.02em · uppercase

**Observed:** A compact text-first control; pairs with Secondary button rather than a second pink action. Plan cards stretch the same control across their inner width.

**States:** Declared: hover background-color #ff91ac; focus-visible outline-style solid and outline-width 1px.

### Secondary button

**Use:** Sales conversations or a lower-priority destination.

**CSS:** `background: #d9d9d9; color: #161616; border-radius: 9999px; padding: 12px 16px; height: 42px`

**Text style:** `action-label` — n8n Baumer Mono 400 · 14px/18px · tracking 0.02em · uppercase

**Observed:** Same silhouette and type as Primary button. A lighter #e6e6e6 variant belongs to product-detail and pricing support blocks.

**States:** Declared: hover background-color #c2c2c2; focus-visible outline-style solid and outline-width 1px.

### Endpoint capsule

**Use:** Short eyebrows and proof-category labels.

**CSS:** `background: #f0f0f0; color: #161616; border-radius: 9999px; padding: 4px 12px; position: relative`

**Text style:** `action-label` — n8n Baumer Mono 400 · 14px/18px · tracking 0.02em · uppercase

**Observed:** Two 6px pink endpoint dots sit halfway outside the left and right edges. Selected labels use pink fill and dark endpoint dots; dark chapter tabs use charcoal-gray fill.

**Transfer:** Use terse category language, not a full headline.

### Chapter selector

**Use:** Sticky feature-navigation rail beside a changing product stage.

**CSS:** `background: #fafafa; border-top: 1px solid #d9d9d9; padding: 12px 16px; max-width: 360px`

**Text style:** `heading-sm` — n8n Baumer Uniwidth 500 · 24px/1

**Observed:** Text is left aligned. Only the active chapter expands into a short body explanation; inactive headings are gray. The visual stage stays prominent as the reader advances.

**Transfer:** Use a small set of demonstrable capabilities; show their corresponding states rather than unrelated images.

### Capability card

**Use:** Compact proof of product maturity.

**CSS:** `background: #212121; color: #fafafa; border-radius: 24px; padding: 24px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `card-label` — n8n Baumer Uniwidth 500 · 16px/1.25

**Observed:** A square pixel-symbol graphic comes first, followed by a small medium title and 14px/18px explanation with a 4px gap. Illustration occupies more area than the text.

**Transfer:** Give each card a distinct functional symbol and a concrete explanation.

### Testimonial tile

**Use:** A broad horizontal track of human proof.

**CSS:** `background: #303030; color: #fafafa; border-radius: 24px; padding: 32px; max-width: 386px; height: 480px; overflow: hidden`

**Text style:** `quote` — n8n Baumer Uniwidth 500 · 32px/1.125

**Observed:** Text-only tiles use 32px/36px statements; portrait or meeting-photo tiles use smaller 24px/24px quotes. Alternating light and dark treatments, mono attribution labels and edge-clipped neighboring cards make a continuous track.

**Transfer:** Mix genuine portrait quotes with short text-only statements instead of identical logo cards.

### FAQ row

**Use:** Objection handling in a centered stack.

**CSS:** `background: #f0f0f0; color: #161616; border-radius: 24px; padding: 24px; display: flex; align-items: center; gap: 48px; width: 100%`

**Text style:** `body` — n8n Baumer Uniwidth 400 · 16px/1.25

**Observed:** Closed desktop rows are 68px tall, stacked 16px apart in a 788px column. The question grows to fill the row; a small plus sits on the right.

**States:** Declared: hover not specified; focus-visible outline-style solid and outline-width 1px.

**Transfer:** Let longer questions wrap and increase row height rather than shrinking type.

### Footer link

**Use:** Upper footer navigation columns.

**CSS:** `color: #fafafa; border-radius: 9999px; padding: 12px 16px; display: flex; align-items: center; gap: 8px`

**Text style:** `action-label` — n8n Baumer Mono 400 · 14px/18px · tracking 0.02em · uppercase

**Observed:** Three narrow columns are grouped on the right opposite the brand mark. Tiny gray badges can attach to labels. The bottom row instead uses smaller sans utility links, centered social icons and right-aligned copyright.

**States:** Declared: hover not specified; focus-visible outline-style solid and outline-width 1px.

### Plan card

**Only for:** pricing pages

**Use:** Comparable tiers with aligned price and conversion rows.

**CSS:** `background: #f0f0f0; color: #161616; border-radius: 24px; padding: 32px 16px; display: grid; row-gap: 32px`

**Text style:** `body` — n8n Baumer Uniwidth 400 · 16px/1.25

**Observed:** Four equal desktop columns with 16px gutters. Order: 24px title and brief audience description, 32px price with smaller billing qualifier, near-white rounded usage selector, full-width pink action, ruled hosting row, checkmarked feature list. All tiers share the same neutral card treatment.

**Transfer:** Align repeated content rows and communicate selection through controls, not an oversized featured tier.

### Comparison row

**Only for:** pricing and product comparison sections

**Use:** Dense factual feature or option comparison.

**CSS:** `border-bottom: 1px solid #474747; height: 53px`

**Text style:** `body` — n8n Baumer Uniwidth 400 · 16px/1.25

**Observed:** Rows sit inside a rounded Dark workbench table. The left feature column takes half the 1190px table; remaining plan columns divide the other half. A #303030 header is 66px high with mono labels. Pink check circles and mono values occupy the centered cells; narrative comparisons use taller rows.

**Transfer:** Group a long comparison into separate rounded tables rather than one endless grid.

### Editorial inline link

**Only for:** long-form customer stories

**Use:** Inline named entities and key supporting references.

**CSS:** `color: #ef3a7a; text-decoration-line: underline`

**Text style:** `article-link` — n8n Baumer Uniwidth 500 · 18px/22px

**Observed:** Links remain part of the paragraph, not pills. Other emphasized phrases use medium underlined ink instead of pink.

**States:** Declared: hover color #cb1861; focus-visible outline-style solid and outline-width 1px.

## Imagery and graphics

### Dotted work surface

**Use:** A signature background for the opening and compact heading backplates; also present inside technical demonstrations.

**Observed:** A subtle regular array of tiny dots across near-white, denser and more visible near the main statement; dark work surfaces invert the contrast. This is a flat technical texture, not a starfield or glow.

**Transfer:** Keep the grid behind words and diagrams with low contrast. New content still uses a dotted heading plate and an open dotted first screen.

**Build:** For the light version, use an SVG pattern of small #d9d9d9 circles on roughly 18px centers and fade it toward the outer edges with a radial mask. Clip a separate pattern to the heading backplate. For the dark footer use 2px-radius #303030 dots at 24px intervals on #212121. The light pattern spacing is design guidance; keep its quiet visual weight.

### Readable process stage

**Use:** Main product demonstration and changing feature media.

**Observed:** Connected square and circular modules, thin curved connectors, short labels and occasional colored service icons sit on charcoal dot fields. Light opening media can show a prompt composer or a slim connected process instead. Media is broad and rounded, usually substantially larger than adjacent text.

**Transfer:** Use the new product's real interface or draw a truthful simplified process. Without rich media, show three to five labeled actions and an actual result; keep the human-readable logic.

**Build:** Place 70px–72px rounded modules on a dotted stage, connect them with thin neutral SVG paths and small port circles, then add one concise title beneath each. Use charcoal modules in dark stages and soft-gray modules in light stages. Confine service colors to small icons; preserve neutral surroundings.

### Pixel capability symbols

**Use:** Signature illustrations within capability collections.

**Observed:** Simple shields, timers, braces and structural symbols are assembled from separated rounded square pixels. Large white symbols occupy square dark dotted windows; small dark symbols head embossed light cards.

**Transfer:** Construct functional symbols relevant to the new product, using a consistent block grid instead of a conventional line-icon set.

**Build:** Draw an SVG on an 8-by-8 or 10-by-10 grid. Populate only the cells needed for the silhouette with rounded rectangles separated by a small consistent gap. Use #fafafa over #212121, reverse to #161616 on light gray, and retain generous clear space around the symbol. A static SVG is sufficient.

### Candid work photography

**Use:** Human counterweight in photo splits, proof sections and closing calls.

**Observed:** People concentrating on laptops, colleagues around a table, hands on a keyboard and lived-in desks with cables and cups. Natural window light, muted warm or green surroundings, casual clothing and unpolished work environments. Photos fill rounded landscape frames, often 688px wide, with no decorative device mockup.

**Transfer:** Commission or select believable images of the intended users doing real work. Match the daylight and restrained color, and keep surrounding typography on the light canvas.

### Portrait proof

**Use:** Customer proof and testimonial tracks.

**Observed:** Small 132px-square portraits sit beside compact quotes in soft-gray cards; larger vertical portraits and meeting images fill testimonial tiles, sometimes with a dark bottom fade for light text.

**Transfer:** Keep names and roles readable and use human expressions rather than anonymous avatars.

### Editorial resource tiles

**Only for:** resource and feature index pages

**Use:** Mixed article-card grid.

**Observed:** Four-column tiles alternate light diagrams, dark dotted typographic covers and image-backed covers with bottom fades. Titles are usually 24px; deliberately oversized 56px type is used on text-only dark covers.

**Transfer:** Alternate cover construction while maintaining the common 24px outer silhouette. Set new titles to sensible line breaks rather than treating truncated fragments as a typographic motif.

### Icons

**Observed:** Small marketing utility icons are mostly filled SVGs at 20px; comparison help icons are 18px and compact media affordances are 16px. Capability graphics use a separate square-pixel construction. Pink checks, dark text icons and light social marks inherit their surrounding contrast.

**Transfer:** Use compact filled utilities and a consistent pixel-symbol family for large capability art; keep colorful vendor marks inside product diagrams.

## Section recipes

How recurring sections are built.

### First screen: Open dotted workbench

**Observed:** The first screen is a near-white dot field behind a floating Navigation capsule. A centered two-line promise starts below the navigation with 144px top spacing, spanning about half the viewport width. It uses display at 64px/0.85, medium ink, with no gradient or ornamental italics. A centered 18px/22px support paragraph follows after 24px, then a 12px-gap pair of Primary button and Secondary button after another 24px. Below the actions, a small centered product scene occupies roughly 590px of width: a soft-gray prompt composer with a near-white text area, tiny utility icons and compact suggestion capsules. The broad dotted field stays visible around it. The headline, support, both actions and entire main object are visible within the first 900px; the trust strip begins below the opening.

**Transfer:** Make the statement a two-part promise tied to a visible task. Without a composer or interactive demo, use a truthful small process diagram or annotated result on the same dotted field. Product-detail openings can use 56px headings and a slim process chain; pricing and feature-index openings use a shorter dotted title plate, compact support and earlier access to plans or capabilities. Story openings use a wider title with one pink phrase.

**Avoid:** Do not turn the first screen into a dark sci-fi scene, enlarge the demo into an edge-to-edge dashboard, or place a decorative photograph above the working product object.

**Text style:** `display` — n8n Baumer Uniwidth 500 · 64px/0.85 · tracking -0.01em

### Centered heading pair

**Observed:** A heading-xl statement sits above compact body copy with a 24px gap and optional paired actions after 24px. The whole introduction is centered; the main collection starts about 64px later.

**Transfer:** Use a short outcome headline and one explanatory sentence before introducing proof.

**Text style:** `heading-xl` — n8n Baumer Uniwidth 500 · 48px/1 · tracking -0.01em

### Dark use-case theater

**Observed:** Dark workbench within the 1190px container, padded 32px, starts with a row of compact role tabs. A roughly 360px left copy column uses heading-lg, body and a subdued text link; a much wider readable process scene sits to its right.

**Transfer:** Let tabs stand for reader jobs or scenarios. Keep a specific outcome visible beside each demonstration.

**Text style:** `heading-lg` — n8n Baumer Uniwidth 500 · 40px/1.05 · tracking -0.01em

### Scroll chapter showcase

**Observed:** Chapter selector and heading-lg occupy a narrow left rail while an 875px by 583px dark rounded demonstration stays on the right. Advancing the chapter reveals a new short explanation and an updated stage. Top-level section padding is 96px; divider rules make the rail legible.

**Transfer:** Use this for capabilities that genuinely benefit from successive states. On a shorter page use a compact selectable sequence rather than copying the long reading distance.

**Text style:** `heading-lg` — n8n Baumer Uniwidth 500 · 40px/1.05 · tracking -0.01em

### Photographic statement split

**Observed:** Two equal halves within the wide container. The text half has a centered heading-xl over a pale dotted plate, often with a right-aligned Support inset below; the other half is candid landscape photography or a functional product video. Sides alternate between chapters.

**Transfer:** Contrast an emotional outcome with a credible work scene and keep supporting prose in a compact block.

**Text style:** `heading-xl` — n8n Baumer Uniwidth 500 · 48px/1 · tracking -0.01em

### Pixel proof collection

**Observed:** Centered heading pair above four Capability cards, 16px apart within 1190px. An alternate product-detail collection uses Widget band with a headline to the left and a tight two-by-two inset card grid; feature catalogs use four-column Embossed cells with smaller dark pixel symbols.

**Transfer:** Use the dark card collection for ordinary landing pages; reserve dense embossed variants for capability catalogs.

### Quantified human proof

**Observed:** Two 587px-wide proof columns each lead with a 40px outcome statement on dots, then a soft-gray quote strip with a 132px portrait, compact quote and muted attribution, followed by a small secondary action. A separate Testimonial tile track mixes photographs and text with clipped neighboring tiles.

**Transfer:** Put the measurable result in the headline and human explanation below; use a testimonial track when there are multiple genuinely distinct voices.

**Text style:** `heading-lg` — n8n Baumer Uniwidth 500 · 40px/1.05 · tracking -0.01em

### Human closing call

**Observed:** A Photographic statement split pairs a 48px centered promise over dots with a candid work photo, usually 688px by 459px. One pink action sits directly beneath the statement; some product variants add a gray sales action. Vertical section padding is 96px.

**Transfer:** End with a usable next step and a human image of the product's intended benefit, not a giant accent-colored banner.

**Text style:** `heading-xl` — n8n Baumer Uniwidth 500 · 48px/1 · tracking -0.01em

### Inset technical footer

**Observed:** A 24px page inset contains a 1392px-wide Dark workbench with 24px corners. Upper content places a modest mark left and three narrow Footer link columns right. A 480px Footer dot field separates navigation from the compact bottom row: utility links left, five small social icons centered, legal ownership right. The whole footer module is about 992px tall including its inset.

**Transfer:** Retain the generous low-contrast dot field as a deliberate ending device; adapt link groups to the new information architecture.

### Plan comparison and objections

**Only for:** pricing pages

**Observed:** A 56px centered title and support lead to a compact billing toggle and four Plan cards. A photo split explains the billing principle, then alternate offers, logo proof, grouped dark comparison tables and a long centered FAQ row stack resolve detail. The FAQ flows directly into the shared footer without an extra photo close.

**Transfer:** Keep quick tier selection above technical detail and answer purchase mechanics in plain language.

**Text style:** `compact-display` — n8n Baumer Uniwidth 500 · 56px/1 · tracking -0.01em

### Editorial story with facts rail

**Only for:** customer stories

**Observed:** A wide centered 56px title includes one pink phrase over a dot plate, with a 16px summary below. The body splits into a left facts rail and 772px reading column. Plain small metrics with uppercase mono labels sit below the customer logo; these are not giant statistic cards. Article body is 18px/22px, section titles 32px/36px, subheads 24px/24px. A portrait quote closes the article before wider testimonial and closing sections.

**Transfer:** Use the rail for a few contextual facts and a restrained sales card; tell the challenge, adoption and outcome in the right-hand column.

**Text style:** `compact-display` — n8n Baumer Uniwidth 500 · 56px/1 · tracking -0.01em

## Page flow

**Storyline:** Promise → visible work → credibility → explained capabilities → human and quantified proof → objections or next step → technical footer.

### Broad marketing landing page

1. **Promise** — Two-line headline, paired actions and small working object on dots.
2. **Social proof** — Compact monochrome customer marks and a dark scenario theater.
3. **Capability chapters** — Wide integration statement and successive narrow-rail demonstrations.
4. **Product maturity** — Photo split and pixel-symbol capability cards.
5. **Human proof** — Quantified customer columns and mixed testimonial track.
6. **Closing call** — Dotted promise opposite work photography, then inset dark footer.

**Transfer:** Move from an immediately understandable task to deeper operational confidence, alternating interface proof and people.

### Pricing and purchase evaluation

1. **Pricing** — Compact centered title, billing toggle and four aligned neutral plan cards.
2. **Value explanation** — Photo split explains the charging principle; inset alternate offers and logo strip follow.
3. **Detailed comparison** — Grouped charcoal tables with mono headers and pink checks.
4. **Objection handling** — Long single-column FAQ stack.
5. **Ending** — Shared inset dark footer directly after FAQ.

**Transfer:** Let buyers choose quickly, then inspect details without switching visual language.

### Focused product landing page

1. **Promise** — Centered dotted headline and small process demonstration.
2. **Product demonstration** — Dark selectable theater and an embossed benefit collection.
3. **Capability explanation** — Alternating photo and product splits with a large explanatory video.
4. **Objection handling** — Dark narrative comparison, starter resources and mature-capability cards.
5. **Closing call** — FAQs, human photo close and shared footer.

**Transfer:** Explain one core distinction clearly before expanding into benefits and objections.

### Feature catalog

1. **Promise** — Short dotted title plate and dual actions.
2. **Capability chapters** — Inset build panel followed by long rail-and-stage demonstrations.
3. **Product maturity** — Dense embossed grid with pixel symbols.
4. **Community and resources** — Candid photo grouping and mixed editorial tiles.
5. **Closing call** — Dotted photo split followed by shared dark footer.

**Transfer:** Organize a broad catalog by meaningful phases, not a wall of identical cards.

### Customer outcome article

1. **Quantified promise** — Centered title with a pink phrase and a short result summary.
2. **Context** — Logo and facts rail alongside long-form reading column.
3. **Narrative proof** — Challenge, implementation, expansion and impact chapters with underlined emphasis.
4. **Human proof** — Portrait quote and wider testimonial track.
5. **Closing call** — Human work photo opposite a closing promise, followed by the same inset footer.

**Transfer:** Keep the reading column plain and let verified outcomes carry the story.

## Writing

Confident, plain-spoken and technically credible, with a conversational edge. It acknowledges tradeoffs and makes benefits tangible through visible actions and specific outcomes.

**Do not copy:** Do not reuse n8n names, logos, customer identities, proprietary interface artwork, customer quotations, metrics, prices, rankings or product claims. Source examples illustrate voice only; replace them with truthful claims for the new product.

- **Addressing the reader:** Speak directly to you and your team. Name the product when describing what it does; use we sparingly rather than turning every paragraph into a company statement.
- **Rhythm:** Short verb-led headlines and compact one- or two-sentence support blocks. Plus signs join complementary ideas; periods and brief fragments give the copy an assured conversational rhythm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Pair a concrete action with a reassurance or visible consequence. | 4–10 words | “Build the agent. Understand its workflow.”<br>“Think it + build it + run it” |
| Capability heading | Name an outcome in everyday terms rather than listing infrastructure. | 4–9 words | “Move fast + break nothing”<br>“Your token spend, tamed” |
| Supporting explanation | State a mechanism with plain verbs and the reason it matters. | 1–3 short sentences | “The workflow is the documentation. No separate docs. No handover write-ups.”<br>“See every step. Stay in control.” |
| Primary action | A concise verb pointing toward useful activity. | 2–3 words | “Start building”<br>“Start free trial” |
| Objection heading | Ask the practical question the reader is already considering. | 5–12 words | “But can’t I just build in a coding agent?”<br>“Need something a bit different?” |
| Proof headline | Name a customer outcome with a meaningful number and a specific change. | 7–12 words | “Huel saved 1,000 hours with an AI-first culture” |

**Words and phrasing to use:** build; run; see; understand; ship; follow; control; in production; built in; your team

**Avoid:** revolutionary; magical AI; limitless possibilities; unlock synergies; seamless transformation; next-generation paradigm

**Rules:**

- Explain what a person can inspect, change or achieve instead of merely calling the product powerful.
- Pair ambition with reassurance; do not promise speed without explaining control.
- Use plus signs for genuinely complementary ideas, not as decoration in every sentence.
- Allow a memorable analogy or lightly playful fragment, then return to concrete mechanisms.
- Keep technical names where they help evaluation; introduce them through reader benefits.

## Do's and Don'ts

### Do

- Set the main landing promise at 64px, weight 500, -0.01em tracking and 0.85 line height.
- Keep uppercase mono labels at 14px/18px with 0.02em tracking.
- Use the 42px pink pill and a same-height gray companion for paired actions.
- Place wide sections within 1392px and ordinary proof panels within 1190px.
- Keep 16px gutters between primary card-grid columns and 24px default card insets.
- Give major sections 96px vertical padding, with 48px for compact trust strips.
- Include the dot field and square-pixel illustration language alongside real product proof.
- Close with human-scale photography and the inset 24px-corner charcoal footer.

### Don't

- Do not substitute heavy 700-weight display text for the medium grotesk headings.
- Do not apply pink to full-width section backgrounds; its job is concentrated control and emphasis.
- Do not replace 24px panel corners with sharp rectangles or make every panel pill-shaped.
- Do not give flat gray cards broad floating drop shadows; the special shadow treatment is inset emboss.
- Do not use monospace for marketing paragraphs or long article prose.
- Do not promote colors from service icons into the main site palette.
- Do not turn the customer-story facts rail into enormous multicolored KPI tiles.
- Do not give every pricing tier a different accent color or add an unsupported raised featured-plan effect.

## Motion and responsive

### Motion

**Observed:**

- Declared action states include primary pink hover, secondary gray hover and 1px solid focus-visible outlines.
- Declared transitions include opacity 0.3s cubic-bezier(.4,0,.2,1), scale and background-color .15s cubic-bezier(0,0,.2,1), and chapter text-color changes over 0.5s.
- The product stages show different process states while the text rail stays in place; testimonial tiles extend beyond the page edges.

**Transfer:**

- Tie stage changes to meaningful chapter selection. A static readable diagram remains the baseline version of the technical stage.
- Keep hover feedback local to the pill or link; do not animate entire marketing sections as if they were interface controls.

**Unknown:**

- Exact playback, scroll choreography and carousel timing are not established.
- No entrance-animation duration or autonomous demo sequence is prescribed.

### Responsive

**Observed:**

- Styles declare width breakpoints at 425px, 440px, 450px, 624px and 767px.
- Layout classes also specify desktop navigation hiding, stacked-to-grid feature arrangements and a hidden narrow-screen chapter rail.

**Transfer:**

- On narrow screens, stack statement and media while retaining the dotted title treatment and rounded stage.
- Replace a long sticky chapter rail with sequential readable chapters; keep each explanation attached to its corresponding demonstration.
- Let pricing columns scroll or stack without compressing 16px body copy; keep comparison labels attached to values.

**Unknown:**

- Exact mobile type sizes, navigation behavior and mobile media compositions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
