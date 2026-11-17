# Linear — instruments after midnight

## Overview

A near-black, software-native style with cool white grotesk typography and an unusually restrained sense of spectacle. Detailed interfaces emerge from darkness like instruments under low light, while occasional acid-yellow and frosted pastel proof cards interrupt the monochrome field. It suits sophisticated tools and technical platforms: sparse in its prose, dense inside demonstrations, and confident without theatrical sales language.

### Essentials

- Headlines feel like a product interface enlarged, not advertising display type: Inter Variable at 64px/1, weight 510, -0.022em tracking; section titles use 48px/1 with the same weight and tracking.
- The first impression is a left-aligned statement above a working instrument: a two-line headline, 15px support line, a small right-aligned news link, and a 1320px-wide interface stage beginning within the first 900px. The default landing-page treatment is dark and product-led.
- Actions are small machined pills rather than colored banners: 9999px radius, pale #e5e5e6 primary fill, translucent white secondary fill, 44px height and 20px horizontal padding; the persistent navigation uses a 32px version.
- Darkness is the dominant material: #08090a canvas, #0f1011 panels, #f7f8f8 headings and #8a8f98 supporting copy. Chromatic marketing fills belong to isolated proof cards, not alternating full-width bands; preserve a bright proof interruption against the much longer neutral field.
- Demonstrations fade into the page rather than sitting in bright browser mockups: 12px panel corners, 0.5px–1px translucent edges, overlapping foreground windows and bottom/side vignettes. Include a convincing instrument-like scene; without finished product media, construct a focused interface fragment with real labels and plausible state.
- Technical figure markings and wireframe objects make abstract benefits tangible: 12px/16.8px uppercase mono captions, three separated columns, and approximately 270px monochrome isometric drawings. Carry this device into a new page with original geometric diagrams.
- The final promise is larger than the opening: a centered, two-line 72px/1 statement at weight 510, a 40px gap to paired pills, and 224px of breathing room above and below. Preserve this monumental verbal punctuation, independently of the order of earlier sections.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid proof | `#e4f222` | `--color-proof-lime` | surface | One bright testimonial card; a concentrated interruption rather than a site-wide action color. |
| Frosted blue | `#d1e6ff` | `--color-proof-blue` | surface | Visible blue end of the proof-card gradient: #b2d5ff beneath a 40% white veil. |
| Frosted lilac | `#ece3ff` | `--color-proof-lilac` | surface | Visible lavender end of the proof-card gradient: #dfd1ff beneath a 40% white veil. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool white | `#f7f8f8` | `--color-heading` | text | Headlines, emphasized labels and dark-surface actions. |
| Pale action | `#e5e5e6` | `--color-button` | action, border | Primary pill fill and matching edge. |
| Silver | `#d0d6e0` | `--color-body` | text | Large explanatory copy and stronger small labels. |
| Slate | `#8a8f98` | `--color-muted` | text, link | Body prose, navigation and secondary links. |
| Graphite text | `#62666d` | `--color-faint` | text | Dates, figure markings and tertiary legal links. |
| Raised translucent edge | `#262727` | `--color-panel-edge` | border | Visible white-at-12% edge on the canvas for floating panels. |
| Structural rule | `#23252a` | `--color-rule` | border | Footer boundary and structural separators. |
| Fine translucent edge | `#1c1d1e` | `--color-edge` | border | Visible white-at-8% edge on the canvas; actual layers retain the alpha recipe. |
| Soft glass | `#141516` | `--color-soft-wash` | surface | Visible result of white at 5% over the canvas; secondary pills. |
| Frame charcoal | `#101112` | `--color-frame` | surface | Large instrument frame backing. |
| Raised charcoal | `#0f1011` | `--color-panel` | surface | Floating product panels. |
| Deep frame | `#090a0b` | `--color-deep-frame` | surface | Dark outer casing of the opening product scene. |
| Midnight canvas | `#08090a` | `--color-canvas` | background, text | Default page background and inverse text on pale proof cards. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Comparison rule | `#202122` | `--color-table-rule` | border | Vertical separators in comparison tables. |
| pricing pages | Billing indigo | `#5e6ad2` | `--color-toggle` | action | Small billing switch, not a primary marketing button. |

## Typography

- **Inter Variable** — All marketing headlines, prose, navigation and actions. High-x-height grotesk with open counters; intermediate variable weights keep headings firm but not bold. OpenType features: "cv01", "ss03". Font stack: "Inter Variable", "SF Pro Display", -apple-system, system-ui, "Segoe UI", Roboto, sans-serif.
- **Berkeley Mono** — Figure numbers, dates and technical annotations. Compact utilitarian monospace, used sparingly rather than as a headline face. If unavailable, use **IBM Plex Mono**. Use 400 with normal tracking. Font stack: "Berkeley Mono", "IBM Plex Mono", ui-monospace, "SF Mono", Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monument | Inter Variable | 510 | 72px | 1 | -0.022em | Centered closing promise; also the enlarged headline in focused feature campaigns. |
| display | Inter Variable | 510 | 64px | 1 | -0.022em | Default left-aligned opening headline. |
| heading | Inter Variable | 510 | 48px | 1 | -0.022em | Section titles, positioning statements and pricing-page title. |
| quote | Inter Variable | 400 | 32px | 1.125 | -0.022em | Dark quotation text on bright proof cards. |
| lead | Inter Variable | 400 | 24px | 1.33 | -0.012em | Explanatory statement opposite a section title. |
| button | Inter Variable | 510 | 16px | 44px | normal | Primary and secondary closing actions. |
| body | Inter Variable | 400 | 15px | 1.6 | -0.011em | Default prose and text links, including the opening support line. |
| item-title | Inter Variable | 510 | 15px | 1.6 | -0.011em | Small benefit names, update titles and inline proof numbers. |
| small | Inter Variable | 400 | 13px | 1.5 | -0.01em | Footer links, plan bullet text and subordinate labels. |
| small-title | Inter Variable | 510 | 13px | 1.5 | -0.01em | Footer column titles and small campaign eyebrow. |
| navigation | Inter Variable | 400 | 13px | 1.5 | normal | Top-level navigation links. |
| button-small | Inter Variable | 510 | 13px | 32px | normal | Compact navigation signup action. |
| figure | Berkeley Mono | 400 | 12px | 1.4 | normal, uppercase | Figure numbers, uppercase dates and instrument-like captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | plan-title | Inter Variable | 590 | 24px | 1.33 | -0.012em | Plan names. |
| pricing pages | table-heading | Inter Variable | 510 | 24px | 1.33 | -0.012em | Comparison column and category headings. |
| focused feature campaigns | campaign-support | Inter Variable | 400 | 17px | 1.6 | normal | Two-line support paragraph under a focused campaign headline. |
| developer platform pages | campaign-close-support | Inter Variable | 400 | 17px | 1.4 | -0.012em | Centered support beneath the developer closing invitation. |

**Notes:**

- Display and section headings share weight 510 and -0.022em tracking; hierarchy comes from scale and composition rather than a jump to bold.
- Keep large explanatory copy at weight 400 and cool silver. Default prose is smaller and dimmer, creating a deliberate divide between narrative and interface density.
- Use mono only as small technical punctuation. Figure labels can be further subdued with opacity; do not turn every eyebrow into an uppercase mono label.

## Layout

**Density:** Airy narrative with dense demonstrations: large chapter intervals surround tightly packed UI and compact navigation.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Benefit title-to-copy gaps and tight grouped controls. |
| 12px | Paired closing actions and adjacent demonstration panels. |
| 16px | Short heading-to-support gaps in compact closing invitations. |
| 24px | Editorial paragraph gaps and proof-card vertical padding. |
| 32px | Inner section inset, panel columns and proof-card horizontal padding. |
| 40px | Closing headline-to-action gap. |
| 46px | Outer desktop content padding inside the wide container. |
| 48px | Section support-to-text-link interval. |
| 56px | Footer top and bottom padding. |
| 64px | Update-column gaps. |
| 96px | Chapter-heading-to-illustration separation. |
| 128px | Major capability chapter top and bottom padding. |
| 224px | Space above and below the monumental closing call. |

### Containers and grids

- **wide-container**: max width 1436px · side padding 46px. Centered desktop shell; its inner stage is 1344px wide at a 1440px viewport. Text usually receives a further 32px inset.
- **heading-pair**: 2 columns · gap 0px. Equal-width columns: title on the left, support and text link on the right, each with 32px side inset.
- **benefit-grid**: 3 columns · gap 0px. Contiguous diagram columns separated by faint vertical rules.
- **updates**: 4 columns · gap 64px. Four 272px text entries on a shared timeline.
- **footer-grid**: 6 columns · gap 0px. Brand-symbol column plus five navigation columns; small legal row aligns beneath the first text column.
- **closing-measure**: max width 722px. Centered two-line closing heading; constrain the measure so each sentence occupies a separate line.
- **plan-grid** (only for pricing pages): 4 columns · gap 0px. Equal plan columns, 336px wide at desktop with 32px internal side padding.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | product-panels | 12px |
|  | proof-cards | 8px |
| company pages | portraits | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-panel | `rgba(0, 0, 0, 0.25) 0px 2px 32px 0px` | Very soft black lift beneath layered demonstration windows. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous page field.

**CSS:** `background: #08090a; color: #f7f8f8`

**Observed:** No alternating light page bands; most separation is achieved through space and hairlines.

**Transfer:** Let content and local staging create chapters without changing the page theme.

#### Instrument panel · level 1

**Use:** Dark product-scene window.

**CSS:** `background: #0f1011; border: 0.5px solid rgba(255, 255, 255, 0.12); border-radius: 12px; box-shadow: rgba(0, 0, 0, 0.25) 0px 2px 32px 0px`

**Observed:** Edges catch light while the interior remains only slightly lighter than the canvas.

**Transfer:** Use for demonstrations, not as a universal wrapper around all prose.

#### Instrument casing · level 1

**Use:** Large opening application frame.

**CSS:** `background: #101112; border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 12px`

**Observed:** A darker outer shell and a subtle light field sit behind the interface.

**Transfer:** Give a wide product scene an architectural edge without browser chrome.

#### Frosted proof · level 1

**Use:** Wide testimonial card.

**CSS:** `background: linear-gradient(#d1e6ff, #ece3ff); border-radius: 8px; color: #08090a; padding: 24px 32px`

**Observed:** A pale blue-to-lavender field supports black text and oversized translucent brand-symbol artwork.

**Transfer:** Use an original oversized translucent geometric mark as a watermark; keep the quotation fully readable.

#### Acid proof · level 1

**Use:** Narrow companion testimonial card.

**CSS:** `background: #e4f222; border-radius: 8px; color: #08090a; padding: 24px 32px`

**Observed:** The brightest saturated marketing surface is concentrated into one card.

**Transfer:** Reserve the acid field for a short, strong piece of credible proof.

#### Local light field

**Use:** Subtle illumination beneath interface fragments.

**CSS:** `background: radial-gradient(circle, rgba(255, 255, 255, 0.04) 0%, rgba(0, 0, 0, 0) 50%); width: 400px; height: 400px; mix-blend-mode: lighten`

**Observed:** A barely visible neutral glow adds material depth, not a colorful halo.

**Transfer:** Place behind the demonstration focal point and keep page text outside it.

## Components

### Fixed navigation

**Use:** Persistent desktop site navigation.

**CSS:** `position: fixed; top: 0px; width: 100%; z-index: 100; background-image: linear-gradient(rgba(11, 11, 11, 0.8) 0%, oklab(0.149576 0.00000680983 0.00000298768 / 0.761905) 100%); border-bottom: 1px solid rgba(255, 255, 255, 0.08); backdrop-filter: blur(20px)`

**Text style:** `navigation` — Inter Variable 400 · 13px/1.5

**Observed:** A 72px navigation row plus its bottom edge; symbol and name anchor the left, small links cluster on the right, followed by a separator, login and Compact signup. Content beneath subtly blurs through the bar.

**Transfer:** Keep the navigation visually lighter and smaller than the opening statement.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #e5e5e6; color: #08090a; border: 1px solid #e5e5e6; border-radius: 9999px; padding: 0px 20px; height: 44px; display: flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `button` — Inter Variable 510 · 16px/44px

**Observed:** Pairs with Secondary button. Pricing uses a 40px version with 13px text; focused campaigns use 40px with 15px text and sometimes a small play icon.

**States:** Declared: hover background #ffffff; focus-visible solid 1px outline with 2px offset; active transform scale(0.97).

### Secondary button

**Use:** Sales or supporting action beside the primary pill.

**CSS:** `background: rgba(255, 255, 255, 0.05); color: #f7f8f8; border-radius: 9999px; padding: 0px 20px; height: 44px; backdrop-filter: blur(4px); box-shadow: rgba(255, 255, 255, 0.03) 0px 0px 0px 1px inset, rgba(255, 255, 255, 0.04) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.6) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 4px 4px 0px`

**Text style:** `button` — Inter Variable 510 · 16px/44px

**Observed:** A subtly modeled dark pill, not an empty outlined rectangle.

**States:** Declared: hover background #191a1b; focus-visible solid 1px outline with 2px offset; active background #191a1b and transform scale(0.97).

### Compact signup

**Use:** Navigation conversion action.

**CSS:** `background: #e5e5e6; color: #08090a; border: 1px solid #e5e5e6; border-radius: 9999px; padding: 0px 12px; height: 32px`

**Text style:** `button-small` — Inter Variable 510 · 13px/32px

**Observed:** The compact member of the pale action family; remains subordinate to the page headline.

**States:** Declared: hover background #ffffff; focus-visible solid 1px outline with 2px offset; active transform scale(0.97).

### Text link

**Use:** Low-pressure route to deeper product details.

**CSS:** `color: #8a8f98; display: inline-flex; align-items: center`

**Text style:** `body` — Inter Variable 400 · 15px/1.6 · tracking -0.011em

**Observed:** Text followed by a fine right arrow, without a surrounding pill; usually sits beneath the explanatory column.

**States:** Declared: hover filter brightness(1.3); focus-visible outline offset 2px; active filter brightness(1.6).

### Feature index

**Use:** Small linked capability inventory below a large demonstration.

**CSS:** `color: #8a8f98; display: flex; align-items: center; justify-content: space-between`

**Text style:** `body` — Inter Variable 400 · 15px/1.6 · tracking -0.011em

**Observed:** Two-column group of compact rows; a subdued plus sits at the far end of each link, not in a circular badge.

**Transfer:** Name subordinate capabilities without giving each another large card.

### Session panel

**Use:** Repeated interface demonstrations.

**CSS:** `background: #0f1011; border: 0.5px solid rgba(255, 255, 255, 0.12); border-radius: 12px; box-shadow: rgba(0, 0, 0, 0.25) 0px 2px 32px 0px; width: 400px; height: 560px; overflow: hidden; display: flex; flex-direction: column`

**Observed:** Small header identifies a tool, then a user request, status and task output. A horizontal run is partially visible through side and bottom fades.

**Transfer:** Replace the interaction with a plausible task for the new product; retain the single-window scale and restrained status colors.

### Proof card

**Use:** Bright testimonial interruption.

**CSS:** `background: linear-gradient(#d1e6ff, #ece3ff); border-radius: 8px; padding: 24px 32px; height: 480px; color: #08090a; display: flex; flex-direction: column; position: relative; overflow: hidden`

**Text style:** `quote` — Inter Variable 400 · 32px/1.125 · tracking -0.022em

**Observed:** Wide card beside a half-width acid-yellow companion, separated by 8px. Quote is at the top; symbol, author and role sit below. Watermark art is oversized and partially clipped.

**States:** Declared: hover filter brightness(1.03); focus-visible solid 1px outline with 2px offset.

**Transfer:** Use genuine testimony, with a short quote and compact attribution; use the acid companion only as localized proof emphasis.

### Footer link

**Use:** Repeated secondary navigation.

**CSS:** `color: #8a8f98; display: inline-flex; align-items: center; height: 28px`

**Text style:** `small` — Inter Variable 400 · 13px/1.5 · tracking -0.01em

**Observed:** Five link columns beside a symbol column. Titles use small-title and precede the list by 24px; list rows are separated by 2px. Legal links are dimmer and sit 80px below the main group.

**States:** Declared: hover color #f7f8f8; focus-visible solid 1px outline with 2px offset.

### Footer shell

**Use:** Final site boundary.

**CSS:** `background: #08090a; border-top: 1px solid #23252a; position: relative`

**Observed:** Approximately 494px deep on desktop; a six-column inner grid uses 56px vertical padding, 46px outer side padding and 32px within text columns. No giant wordmark or newsletter form.

**Transfer:** End with a functional, low-contrast navigation directory.

### Plan column

**Only for:** pricing pages

**Use:** Tier overview.

**CSS:** `display: flex; flex-direction: column; padding: 0px 32px; border-left: 1px solid rgba(255, 255, 255, 0.05)`

**Text style:** `plan-title` — Inter Variable 590 · 24px/1.33 · tracking -0.012em

**Observed:** Name, price, billing strip, checked feature list and bottom-aligned actions; first column omits the left rule. All columns share height. Only the preferred tier receives the pale primary action; other actions remain dark.

**Transfer:** Keep plan differences in text and checks rather than tinted card backgrounds.

### Comparison cell

**Only for:** pricing pages

**Use:** Dense feature comparison.

**CSS:** `display: flex; align-items: center; padding: 14px 32px; border-left: 1px solid #202122`

**Text style:** `body` — Inter Variable 400 · 15px/1.6 · tracking -0.011em

**Observed:** 44px rows under a sticky column header; a double-width feature-name column precedes four equal value columns. Checks are pale filled circles, unavailable entries are faint crosses. Category rows use table-heading with 42px vertical padding.

**Transfer:** Keep vertical guides but avoid a spreadsheet's full horizontal lattice.

## Imagery and graphics

### Emergent interface stage

**Use:** Opening and major capability chapters.

**Observed:** Wide dark application scenes occupy more area than the prose. Foreground chat, chart or code windows overlap a larger board or timeline. Sharp, small interface text lives near the focal point while edges sink into black; color is limited to tiny status markers, syntax and plotted data.

**Transfer:** Create one recognizable workflow with a large background instrument and one foreground detail. If complete product media is unavailable, build a real-looking fragment rather than a generic dashboard collage.

**Build:** Use a 1320px-wide rounded charcoal frame with a 1px white-at-8% edge; layer a 400px or 672px foreground window above it. Add a 400px radial white-at-4% light field behind the focal point. Overlay canvas-to-transparent linear gradients across the side edges and bottom, leaving the meaningful interaction unmasked.

### Wireframe benefit objects

**Use:** Abstract benefit explanations.

**Observed:** Three almost-black isometric objects: stacked rounded slabs, grouped cuboids and a progressively rising fin array. Thin grey edges, restrained top highlights and no solid bright fills; figures sit between mono labels above and small benefit copy below.

**Transfer:** Translate the new product's principles into original geometric constructions with the same faint technical-drawing treatment.

**Build:** Draw SVG paths on a roughly 300px square viewBox. Project rectangles into diamonds using diagonal edges near 30 degrees; repeat 6–10 planes with 12px vertical offsets, or group three cuboids at different heights. Use 1px strokes in white at 8%–25%, dark faces matching the canvas, and a subtle vertical opacity gradient. Keep the front-most top edge strongest.

### Proof watermark

**Use:** Bright testimonial cards.

**Observed:** Oversized low-opacity geometric symbol is clipped far beyond the pale card, adding an almost embossed layer behind the quote.

**Transfer:** Use an original abstract mark or simple concentric geometry, not a literal product interface.

**Build:** Place an SVG geometric emblem behind the text at roughly 1200px square, clipped by the card. Use white paths at low opacity, no outlines, and keep the quote and attribution above it.

### Partner showcase

**Only for:** integration and ecosystem pages

**Use:** Featured integrations followed by a compact directory.

**Observed:** Three tall visual cards contrast white, charcoal and blue-to-lilac backings. Each has a partner symbol at top, a single focused interface interaction in the middle and a small title/description near the bottom. The directory beneath returns to unfilled columns with vertical rules.

**Transfer:** Use partner-appropriate local materials only within this showcase; do not turn the whole page into a pastel grid.

### Human and cursor collage

**Only for:** developer platform closing sections

**Use:** Distinctive closing artwork beneath a centered invitation.

**Observed:** White pixelated pointing-hand cursors spread from the left toward a large grayscale sculptural human hand entering from the right. The contrast between digital pointers and tactile stone-like anatomy sits on unbroken black.

**Transfer:** Use a different human/tool relationship suited to the product, retaining monochrome cutouts and the contrast between pixel and physical texture.

**Build:** Create a transparent monochrome hand or tool cutout, about 905px wide, entering from the lower-right edge. Scatter small original pixel pointer SVGs across a loose left-to-right field; use hard white pixels, staggered positions and slight directional rotation. Keep the central heading and controls clear above the collage. A high-quality grayscale tool cutout plus a handful of simple pixel pointers is the minimum version.

### Company film and portraits

**Only for:** company pages

**Use:** Humanize an otherwise technical page.

**Observed:** A broad 16:9 film frame with an 8px edge radius shows a warmly lit working environment. Below it, square monochrome head-and-shoulders portraits use 4px corners, muted studio backdrops and compact names/roles. A long four-column text roster deliberately gives the wider team equal typographic weight.

**Transfer:** Use authentic people in working environments for the film, controlled grayscale portraits for leadership, and a text roster for breadth; avoid cheerful stock-office collages.

### Icons

**Observed:** Small filled SVG symbols dominate: 16px for interface and action context, 14px for secondary controls, 20px for larger actions. Pale grey and muted grey are the norm; arrows and plus signs are fine and compact. Integration marks retain their own silhouettes.

**Transfer:** Choose simple filled or mixed-weight utility icons with the same compact footprint. Use status colors inside demonstrations rather than beside every marketing sentence.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** Fixed navigation sits above a large uninterrupted dark breathing area. A left-aligned two-line display headline spans about two thirds of the width, followed after 32px by one small muted support line; a tiny news/action link anchors the far right of that support row. After roughly 70px, a broad instrument casing begins, about 1320px wide with 60px viewport margins. Layers run from canvas through a neutral light backing, dark casing, application interface and fine edge highlights. Within the first 900px the full headline, support line, news link and upper portion of the main interface are visible; the rest of the interface and subsequent proof lie below. There is no large hero CTA pair; the pale navigation signup supplies the immediate conversion route.

**Transfer:** State the new product's category and audience in an equally compact two-line promise. Build a focused interface fragment if no polished product media exists. Focused feature campaigns open earlier with a 72px two-line promise, a small eyebrow, 17px support and a 40px watch action over a panel carousel. Pricing opens compactly with a 48px title and plans; company stories retain the 64px headline above a broad film.

**Avoid:** Do not center the default opening, replace the product stage with a stock illustration, add a bright full-width gradient behind the headline, or insert an oversized two-button sales block.

**Text style:** `display` — Inter Variable 510 · 64px/1 · tracking -0.022em

### Positioning statement and figures

**Observed:** A 48px statement runs across a wide measure, with a white opening thought continuing into muted grey explanation. Below, the benefit-grid holds Wireframe benefit objects, figure captions, small names and two or three lines of prose; only thin vertical rules separate columns.

**Transfer:** Use a concise category argument and a few original geometric metaphors rather than a conventional icon-card feature list.

**Text style:** `heading` — Inter Variable 510 · 48px/1 · tracking -0.022em

### Capability chapter

**Observed:** 128px top and bottom padding. The heading-pair places a short 48px title opposite 24px support, with Text link 48px below support. A 96px interval leads into the Emergent interface stage; Feature index rows sit beneath it. Scenes can extend beyond the container and fade at their boundaries.

**Transfer:** Organize around meaningful jobs or outcomes, each with one dominant visual interaction, rather than reproducing a fixed number of chapters.

**Text style:** `heading` — Inter Variable 510 · 48px/1 · tracking -0.022em

### Update timeline

**Observed:** A 48px title sits above four text columns separated by 64px. A thin horizontal line and tiny nodes connect the items; title, truncated short description and uppercase mono date form each entry. A restrained Text link sits below.

**Transfer:** Use this for release notes, research milestones or other dated proof of continued work.

**Text style:** `heading` — Inter Variable 510 · 48px/1 · tracking -0.022em

### Bright proof interruption

**Observed:** Proof card uses an approximately two-to-one wide/narrow pairing, 480px tall, with 8px between cards. Pale gradient and acid-yellow fields carry 32px black quotes. Beneath, a 15px proof sentence emphasizes its number at weight 510 instead of creating a giant stat block; a story link aligns opposite.

**Transfer:** Create a concentrated bright moment using customer testimony or another verifiable proof point. Keep numerical proof integrated into prose.

**Text style:** `quote` — Inter Variable 400 · 32px/1.125 · tracking -0.022em

### Monumental closing call

**Observed:** A centered 72px two-line heading fits a 722px measure. Paired Primary button and Secondary button follow after 40px, separated by 12px. The group has 224px breathing room above and below before Footer shell.

**Transfer:** Close with two balanced clauses linking ambition to present availability, then the shortest useful action pair.

**Text style:** `monument` — Inter Variable 510 · 72px/1 · tracking -0.022em

### Plan overview and comparison

**Only for:** pricing pages

**Observed:** A compact 48px title introduces four Plan columns without filled card backgrounds. A subdued social-proof transition leads to a long Comparison cell matrix, whose category titles use table-heading. Column labels stick below the fixed navigation. Repeated actions finish the matrix, followed by a small qualification/documentation line, the Monumental closing call and Footer shell.

**Transfer:** Give quick purchase decisions first and detailed evaluation second; highlight the preferred action, not the entire tier.

**Text style:** `heading` — Inter Variable 510 · 48px/1 · tracking -0.022em

### Capability and ecosystem grid

**Only for:** integration and ecosystem pages

**Observed:** A heading-pair introduces a 2×2 bordered grid with roughly 672px cells, each showing a focused interface fragment above a 15px name and description. A later Partner showcase introduces larger local color contrasts, followed by a compact four-column directory.

**Transfer:** Use the first grid to explain behavior and the showcase to prove compatibility; do not conflate both into identical cards.

**Text style:** `heading` — Inter Variable 510 · 48px/1 · tracking -0.022em

### Editorial company chapter

**Only for:** company pages

**Observed:** Heading-pair composition carries a 48px left title against a 24px lead and 15px paragraphs on the right, separated by 24px. Portraits form a four-column wall, then a long four-column roster. Institutional proof uses two small pale logo plaques above a two-column list of compact names and roles; the page returns to the Monumental closing call and Footer shell.

**Transfer:** Replace the subject matter with the organization's real story, people and supporters while preserving the editorial hierarchy and understated list treatment.

**Text style:** `heading` — Inter Variable 510 · 48px/1 · tracking -0.022em

### Developer invitation

**Only for:** developer platform pages

**Observed:** Centered 48px heading, two-line campaign-close-support paragraph and paired 40px actions sit above Human and cursor collage. Large black space protects the invitation; Footer shell closes the page without an additional monumental slogan.

**Transfer:** Close with a specific making or extending invitation and a monochrome physical/digital metaphor.

**Text style:** `heading` — Inter Variable 510 · 48px/1 · tracking -0.022em

## Page flow

**Storyline:** Category promise → tangible demonstration → explanation of distinct advantages → deeper capability or evaluation blocks → credible proof → focused invitation → functional directory.

### Broad product landing page

1. **Promise and demonstration** — Left statement over one wide working instrument.
2. **Positioning** — Large mixed-white-and-grey statement followed by numbered wireframe benefits.
3. **Capability chapters** — Paired title/support rows and layered interface scenes with compact link inventories.
4. **Freshness and social proof** — Timeline entries, bright testimonial pair and understated inline numerical proof.
5. **Closing call** — Monumental centered promise, paired pills and five-column directory beside a symbol.

**Transfer:** Use the dark product stage as the default for a new landing page; adapt the chapter sequence to the actual product story.

### Purchase evaluation page

1. **Pricing** — Compact heading and equal-height tier columns with bottom-aligned actions.
2. **Social proof** — Restrained trust statement and customer-story route.
3. **Objection handling** — Sticky-header comparison table grouped by category, repeated actions and small qualification note.
4. **Closing call** — Same monumental closing treatment and footer directory.

**Transfer:** Lead with the decision, then support careful comparison without adding marketing-card decoration.

### Focused capability and ecosystem campaign

1. **Promise** — Eyebrow, two large parallel clauses, support and watch action.
2. **Product demonstration** — Wide run of dark session windows with edge fades and small previous/next controls.
3. **Capability explanation** — Split heading pair and ruled 2×2 illustration grid.
4. **Ecosystem proof** — Three featured visual cards followed by a compact directory.
5. **Closing invitation** — Centered build invitation with physical-hand/pixel-pointer collage, then shared footer.

**Transfer:** Use this variant when adoption depends on showing a new interaction and its compatibility with existing tools.

### Company narrative and credibility page

1. **Mission** — Left 64px headline and one short support sentence over a broad film.
2. **Editorial context** — Split title and long-form explanation.
3. **Human proof** — Monochrome portrait wall followed by a long, even-weight text roster.
4. **Institutional proof** — Small pastel logo plaques and compact names/roles.
5. **Closing call** — Monumental product invitation and shared footer directory.

**Transfer:** Keep human media local to the company story while maintaining the dark canvas and typographic system.

## Writing

Direct, composed and technically literate. Ambition is expressed through declarative category statements, then grounded in specific workflow behavior rather than emotional hype.

**Do not copy:** Do not reuse Linear's names, logo, product names, partner marks, customer quotes, company counts, dates, pricing, claims or distinctive slogans. Source examples illustrate structure and tone only; use the new product's own verified facts and original language.

- **Addressing the reader:** Use 'you' and 'your team' for practical outcomes; use 'we' in company narrative. Product explanations often start with an imperative verb, while positioning statements refer to the product by name.
- **Rhythm:** Short noun-phrase section titles, balanced headline clauses and one or two measured support sentences. Longer editorial paragraphs remain plain and factual. Periods often give short statements finality; exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Define the product's category and audience, or pair two complementary clauses. | 6–12 words, usually two lines | “The product development system for teams and agents”<br>“Artificial colleagues. Natural collaboration.” |
| Supporting line | State what the tool is purpose-built to do, then name the broader context. | 10–25 words | “Purpose-built for planning and building products. Designed for the AI era.” |
| Section title | Name a concrete activity or pair related activities. | 2–5 words | “Planning and monitoring”<br>“Build, review, and ship” |
| Capability explanation | Start with an action, then show what changes in the workflow. | 18–35 words | “Automatically turn conversations and customer feedback into actionable issues that are instantly routed, labeled, and prioritized for the right team.” |
| Closing statement | Balance a future-facing promise with an immediate, concrete invitation. | 6–10 words | “Built for the future. Available today.” |
| Primary action | Use a familiar verb phrase with no persuasion attached. | 2–3 words | “Get started”<br>“Start building” |

**Words and phrasing to use:** purpose-built; plan; build; ship; focused; workflows; context; clarity; alongside; from … to …

**Avoid:** revolutionary; supercharge; game-changing; unlock your potential; magic; effortless everything

**Rules:**

- Make large claims brief, then demonstrate a real mechanism in the support line.
- Use concrete nouns and verbs from the reader's work instead of adjective stacks.
- Let testimony supply stronger emotion than the product narrator.
- Keep inline proof numbers embedded in a sentence instead of turning every fact into an outsized stat.
- Keep link labels descriptive and short; use arrows for continuation and plus signs for subordinate capabilities.

## Do's and Don'ts

### Do

- Keep the continuous canvas at #08090a and raised panels close to #0f1011.
- Use weight 510 rather than 700 for 48px–72px headings.
- Give desktop prose a further 32px inset within the wide stage.
- Separate major capability chapters with 128px top and bottom padding.
- Keep the main action at 44px high with a 9999px radius and pale neutral fill.
- Include a sharply readable focal interaction inside each dark vignette.
- Use 12px uppercase mono markings to give diagrams an instrument-like register.
- Concentrate saturated color in one bright proof moment and retain black quote text.
- Keep the final centered promise larger than the opening at 72px.

### Don't

- Do not use indigo as the universal CTA color; the marketing action is pale grey.
- Do not use 24px rounded corners on ordinary panels; the characteristic panel corner is 12px.
- Do not raise default body copy to 20px; the 15px prose is part of the restrained hierarchy.
- Do not convert every feature into a filled charcoal tile; many groups use only vertical hairlines.
- Do not make statistics giant by default; numerical proof is often a 15px inline emphasis.
- Do not turn the neutral demonstration glow into a bright purple neon aura.
- Do not use pure white backgrounds for entire pricing or company pages; local light cards sit on black.
- Do not add a newsletter form or oversized logo at the footer; preserve the compact directory.
- Do not use thick outline icons everywhere; small filled utility symbols are the dominant vocabulary.

## Motion and responsive

### Motion

**Observed:**

- Action states brighten pale fills or darken translucent pills; active buttons scale to 0.97.
- Proof-card links declare filter .16s cubic-bezier(.25, .46, .45, .94).
- Some surfaces declare background 0.4s ease-out; text links use a quick-transition variable whose resolved duration is unspecified.
- Session content, carousel controls and video playback support changing product scenes rather than static decorative illustration.

**Transfer:**

- Keep surface interactions materially subtle: brightness, small fill changes and the declared press scale.
- Animate useful interface state within a stable dark frame rather than moving whole narrative sections for spectacle.

**Unknown:**

- Full scene sequencing, on-scroll timing and transition-variable durations are not established.

### Responsive

**Observed:**

- The desktop shell declares a 1436px maximum with 46px side padding; a smaller page-sized shell uses 24px padding.
- Styles declare breakpoints including 640px, 768px, 1024px, 1280px and 1440px.
- Some wide demonstrations, benefit figures, updates and proof groups have mobile/laptop visibility variants.

**Transfer:**

- On narrow layouts, stack the title/support pair while retaining its hierarchy and original reading order.
- Preserve a single legible focal interface fragment rather than shrinking an entire desktop application to fit.
- Keep comparison labels associated with their values using a horizontally scrollable matrix or per-tier view; this is adaptation guidance, not a prescribed original layout.

**Unknown:**

- Mobile typography sizes, actual narrow-screen layouts, menu behavior and exact visibility thresholds are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
