# Hex — curiosity on drafting paper

## Overview

An editorial technology style that makes analytical software feel human without losing its technical credibility. Warm off-white paper, eggplant ink and delicate drafting marks surround broad grotesk headlines paired with slender italic serif phrases. Layered interfaces and fine diagrammatic illustrations carry most of the visual storytelling; charcoal, rose and lavender form a more immersive product and enterprise variant. The overall density is airy, with detailed demonstrations concentrated into carefully framed scenes.

### Essentials

- Headlines combine a confident statement with a human aside: 74px/1.2 bold semi-extended sans paired with 96.2px/0.75 weight-200 italic serif in the opening; section pairs use 60px/1.3 sans and 78px/1.3 italic.
- The opening is a typographic drafting board, not a device mockup: a 700px paper stage, centered headline about two thirds of the viewport wide, inline capability capsules, two 50px actions and a two-row proof strip visible within 900px.
- Conversion controls look like small engineered plates: 1px edges, nearly square corners, pale rose inset wash and little outlined corner loops on the primary; 38px navigation, 42px section and 50px hero sizes. Pills belong to inline capability links, not the main actions.
- Color is rationed to details: off-white and eggplant cover the ordinary page; mint, lavender and blue appear in small icon wells, diagrams and interfaces. The dark variant uses #14141c with #f5c0c0 support text rather than saturated full-page color.
- Technical framing is a signature, not decoration to omit: 1px perimeter rails, 64px grid cells, corner registration marks, dotted or dashed guides and subtle paper grain recur around important scenes. Use an original line diagram when product media is unavailable.
- Interfaces float as overlapping evidence of work: white panels with 4px–6px corners, hairline edges and broad soft shadows sit beside narrow copy columns. Preserve one dominant panel and smaller supporting windows instead of a uniform wall of thumbnails.
- Small text grounds the editorial scale: 10px uppercase mono proof labels, 12px mono annotations and footer headings, 14px utility text, and 20px/1.5 light body copy. Include a thin announcement ticker and a ruled, multi-column human-feeling footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Eggplant | `#31263b` | `--color-eggplant` | text, accent | Light-theme body text and first stop of display gradients; also used as a 5% wash on technical tiles. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ochre annotation | `#a98529` | `--color-ochre` | text, accent | Small technical labels on capability panels; a 7% wash backs the label, not the whole section. |
| Rose edge | `#cda0a5` | `--color-rose-edge` | border | Rose end of primary action gradient outlines. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep violet ink | `#01011b` | `--color-deep-ink` | text | Second stop of light headline gradients. |
| Display ink | `#14141c` | `--color-ink` | text, background | Primary light-theme text and dark-theme canvas. |
| Secondary ink | `#43394c` | `--color-secondary-ink` | text, link | Light-theme navigation auxiliaries, footer links and proof labels. |
| Muted violet gray | `#89828d` | `--color-muted` | text | Attributions and legal or footer secondary text on paper. |
| Emphasized paper edge | `#afa9b1` | `--color-strong-rule` | border | Stronger light control borders on hover and endpoints of repeated divider gradients. |
| Paper edge | `#dbd7da` | `--color-rule` | border | Outer rails, secondary actions and FAQ separators. |
| Grid line | `#e9e5e8` | `--color-grid` | border, surface | Faint technical grids, proof-card dividers and light hover fills. |
| Blush paper | `#fcf8f8` | `--color-proof-band` | background | Slightly differentiated testimonial band. |
| Warm paper | `#fffcfc` | `--color-canvas` | background, surface | Default page and light action base. |
| Interface white | `#ffffff` | `--color-white` | surface, text | White interface panels; primary headings in dark sections. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark product, enterprise and pricing pages | Rose quartz | `#f5c0c0` | `--color-rose` | text, accent, border | Supporting copy, primary action text and subtle tinted strokes; use alpha washes rather than flat pink bands. |
| dark product, enterprise and pricing pages | Dusty rose | `#e3b2b3` | `--color-rose-secondary` | text, link | Footer and secondary links. |
| dark product and enterprise pages | Lavender | `#ad8eb6` | `--color-lavender` | accent, background, border | Numbered section markers, gradient action edges and a low-intensity glow behind the product opening. |
| dark product, enterprise and pricing pages | Muted rose | `#99797d` | `--color-rose-muted` | text | Secondary footer text and legal links. |
| dark product, enterprise and pricing pages | Recessed dark rail | `#2b252c` | `--color-dark-rail` | border, surface | Lower-contrast vertical page guides and action hover fill. |
| dark product, enterprise and pricing pages | Dark rose-gray edge | `#3a3138` | `--color-dark-rule` | border, surface | Panel outlines, rails and separators. |
| dark product, enterprise and pricing pages | Emphasized dark edge | `#6a565b` | `--color-dark-strong-rule` | border | Divider gradient endpoints and stronger control hover outlines. |

## Typography

- **PP Formula SemiExtended** — Opening and major section statements. Broad, firm sans with open counters and a compact, slightly technical silhouette. If unavailable, use **Archivo**. Use the expanded width axis and weight 700; preserve tight tracking. Font stack: "PP Formula SemiExtended", "Archivo", ui-sans-serif, system-ui, sans-serif.
- **PP Formula** — Feature titles, card titles and intermediate headings. Compact heavy grotesk that gives small headings unusual presence. If unavailable, use **Archivo**. Use standard width, weights 600 and 800. Font stack: "PP Formula", "Archivo", ui-sans-serif, system-ui, sans-serif.
- **PP Editorial New** — Italic phrases within display headings. Very light, high-contrast italic serif with long, expressive strokes. If unavailable, use **Cormorant Garamond**. Use light italic; tune width to retain the long phrase silhouette. Font stack: "PP Editorial New", "Cormorant Garamond", Georgia, serif.
- **Cinetype** — Marketing body text, utility copy, navigation and actions. Light, personable technical sans, less neutral than a conventional UI grotesk. If unavailable, use **IBM Plex Sans**. Use 300 for body and 400 for utility text. Font stack: "Cinetype", "IBM Plex Sans", ui-sans-serif, system-ui, sans-serif.
- **Cinetype Mono** — Ticker, proof labels, annotations and captions. Small monospaced markings with airy tracking. If unavailable, use **IBM Plex Mono**. Font stack: "Cinetype Mono", "IBM Plex Mono", ui-monospace, monospace.
- **IBM Plex Mono** — Footer category headings and numbered enterprise chapters. Matter-of-fact monospace used in heavier uppercase and light numerals. Font stack: "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display-italic | PP Editorial New | 200 italic | 96.2px | 0.75 | -0.0192em | fixed | Slender second line of the opening headline. |
| heading-italic | PP Editorial New | 200 italic | 78px | 1.3 | -0.0237em | fixed | Expressive phrase paired with a major section heading. |
| display | PP Formula SemiExtended | 700 | 74px | 1.2 | -0.025em | size clamp(42px, 24px + 4vw, 74px) | Default opening statement. |
| heading-lg | PP Formula SemiExtended | 700 | 60px | 1.3 | -0.0308em | size clamp(38px, 25.6px + 2.75vw, 60px) | Major section statements and centered dark product openings. |
| aside-italic | PP Editorial New | 200 italic | 52px | 1.3 | -0.0192em | fixed | Smaller editorial aside under a narrow section heading. |
| heading | PP Formula | 800 | 40px | 1.3 | -0.025em | size clamp(30px, 24.4px + 1.25vw, 40px) | FAQ, closing calls and intermediate section headings. |
| feature-heading | PP Formula | 800 | 28px | 1.3 | -0.025em | size clamp(20px, 15.5px + 1vw, 28px) | Narrow-column feature statements and plan names. |
| lead | Cinetype | 300 | 24px | 1.5 | normal | fixed | Short centered support and spacious quotation copy. |
| card-heading | PP Formula | 600 | 20px | 1.3 | -0.025em | fixed | Proof, integration and editorial card titles. |
| body | Cinetype | 300 | 20px | 1.5 | normal | fixed | Primary explanatory paragraphs. |
| question | Cinetype | 400 | 18px | 24px | -0.028em | fixed | FAQ question text. |
| body-sm | Cinetype | 300 | 16px | 1.5 | normal | fixed | Proof-card descriptions and compact testimonial paragraphs. |
| caption | Cinetype | 300 | 14px | 1.571 | normal | fixed | Compact technical tile descriptions and attribution details. |
| utility | Cinetype | 400 | 14px | 1.571 | normal | fixed | Actions, footer links and utility copy. |
| nav | Cinetype | 400 | 14px | 1 | normal | fixed | Navigation links and compact header action text. |
| annotation | Cinetype Mono | 400 | 13px | 1 | 0.0833em | fixed | Technical panel labels in a faint colored wash. |
| ticker | Cinetype Mono | 400 | 12px | 1.571 | normal | fixed | Single-line announcement ticker. |
| footer-heading | IBM Plex Mono | 700 | 12px | 1.571 | 0.058em, uppercase | fixed | Compact category markers over footer links. |
| proof-label | Cinetype Mono | 400 | 10px | 0.8 | 0.0833em, uppercase | fixed | Tiny centered label interrupting a proof-strip boundary. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| enterprise openings | enterprise-display | PP Formula SemiExtended | 700 | 68px | 1.3 | -0.0308em | fixed | Left-aligned multi-line trust or scale statement. |
| pricing pages | plan-price | Cinetype | 800 | 28px | 1.571 | normal | fixed | Prices and short non-numeric plan-price labels. |
| enterprise capability chapters | chapter-number | IBM Plex Mono | 300 | 16px | 1.5 | 0.125em, uppercase | fixed | Two-digit numbered benefit markers. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Italic is a phrase-level change of voice inside a headline, not a second independent heading. Keep the sans substantially heavier than the serif.
- Use the light ink gradient from eggplant to deep violet on major headings. On dark pages, the counterpart runs from white toward translucent rose at 55deg.
- Preserve optical overflow around italic descenders: major clipped-gradient headings have 6px side allowances. The opening has extra bottom room rather than clipping the serif.
- Feature and card headings keep -0.025em tracking; body text stays at normal tracking. Mono annotations expand instead of tightening.

## Layout

**Density:** Airy at the page level, with concentrated interface detail and restrained utility spacing.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Footer link stacks and compact content gaps. |
| 12px | Header vertical padding and dark gallery card inset. |
| 15px | Card-title stacks, section-heading support gaps and dark gallery gutters. |
| 20px | Action pairs, standard grid gutters and heading-to-action spacing. |
| 30px | Proof-card insets and closing action separation. |
| 40px | Container side padding and separation between a feature action and testimonial. |
| 60px | Footer column gutters and feature-section vertical insets. |
| 70px | Copy-to-product gap and integration header-to-grid separation. |
| 80px | FAQ vertical insets and wide chapter gaps. |
| 100px | Major proof and closing-section vertical padding. |
| 160px | Lead-in space for enterprise assurance chapters. |
| 200px | Top offset for dark page openings and generous chapter separation. |

### Containers and grids

- **page rails**: max width 1840px · 12 columns · side padding 29px. Outer technical frame occupies 96% of the desktop width; thin perimeter rails continue through the page, with roughly 29px outer gutters at 1440px.
- **content**: max width 1240px · side padding 40px. Centered shared content container; 1160px usable interior for many grids.
- **typographic opening**: max width 1080px · side padding 32px. Centered opening headline and supporting capsules; narrow 580px supporting wrap inside the broader display.
- **feature split**: max width 1240px · 2 columns · gap 70px. A roughly 330px text column beside a larger, deliberately overlapping interface scene; alternate direction for selected chapters.
- **technical tiles**: 3 columns · gap 20px. Three approximately 373px-wide illustration-led tiles per row.
- **proof strip**: max width 1176px · 4 columns · gap 0px. One continuous bordered assembly, divided by vertical rules rather than separated floating cards.
- **faq**: max width 604px. Centered, narrow single-column list.
- **footer links**: max width 800px · 4 columns · gap 60px. Four 155px link columns, with identity on one side and a small technical ornament on the other.
- **pricing comparison** (only for pricing pages): max width 1304px · 5 columns · gap 0px. One feature-label column and four aligned plan columns; initial summary groups four plans into two bracketed pairs.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 1px |
|  | interface panels | 6px |
|  | editorial cards | 12px |
|  | capability capsules | 30px |
|  | icon wells | 50% |
| dark product demonstrations | dark interface panels | 4px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating interface | `0px 0px 0px 1px rgba(49,38,59,0.22), 0px 103px 103px 0px rgba(49,38,59,0.03), 0px 26px 57px 0px rgba(49,38,59,0.05)` | Broad, low-opacity grounding under white product scenes. |
|  | paper card | `inset 0px 0px 11px 0px rgba(0,0,0,0.05), 0px 0px 0px 1px rgba(0,0,0,0.06), 0px 16px 24px -8px rgba(0,0,0,0.05), 0px 8px 12px -4px rgba(0,0,0,0.05), 0px 4px 6px -2px rgba(0,0,0,0.05)` | Soft glass-paper cards and rounded editorial modules. |
| dark product demonstrations | dark-stage interface | `-1px 0px 0px 0px rgba(2,2,27,0.07), 1px 0px 0px 0px rgba(2,2,27,0.07), 0px -1px 0px 0px rgba(2,2,27,0.07), 0px 1px 0px 0px rgba(2,2,27,0.07), 0px 54px 74px 0px rgba(1,1,27,0.3), 0px 14px 74px 0px rgba(0,0,0,0.25)` | White panels lifted far above charcoal with deep soft shadows. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #fffcfc; color: #31263b`

**Observed:** A very fine irregular grain covers the paper at 0.06 opacity; the surface stays warm white, never visibly mottled.

**Transfer:** Use a non-interactive SVG noise overlay; retain the paper tone underneath.

#### Drafting field · level 0

**Use:** Opening stage and major proof assemblies.

**CSS:** `background-image: linear-gradient(#e9e5e8 1px, transparent 1px), linear-gradient(to right, #e9e5e8 1px, transparent 1px); background-size: 64px 64px`

**Observed:** Grid strength fades toward the text; small corner marks and stippling supply the technical atmosphere.

**Transfer:** Mask the field with a radial or vertical fade so it frames the headline rather than lining through every letter.

#### Glass paper · level 1

**Use:** Editorial cards, testimonial cards and paired capability panels.

**CSS:** `background: linear-gradient(105deg, rgba(245,192,192,0) 10.56%, rgba(245,192,192,0.02) 108.41%), rgba(253,253,253,0.4); border-radius: 12px; backdrop-filter: blur(7.5px); box-shadow: inset 0px 0px 11px 0px rgba(0,0,0,0.05), 0px 0px 0px 1px rgba(0,0,0,0.06), 0px 16px 24px -8px rgba(0,0,0,0.05), 0px 8px 12px -4px rgba(0,0,0,0.05), 0px 4px 6px -2px rgba(0,0,0,0.05)`

**Observed:** Reads as near-white paper with a barely raised translucent edge, not blue frosted glass. The larger paired panels use 6px corners.

**Transfer:** Keep translucency low and shadow spread soft; preserve grain and line art through the material.

#### Technical tile wash · level 1

**Use:** Illustrated capability grid.

**CSS:** `background: rgba(49,38,59,0.05); padding: 5px`

**Observed:** Flat squared rectangles with spare line illustrations above a title and short paragraph; no bulky raised border.

**Transfer:** Use the shallow wash for systematic information, reserving glass-paper for quotes or editorial content.

#### White product panel · level 2

**Use:** Main product scenes and their supporting windows.

**CSS:** `background: #ffffff; border-radius: 6px; box-shadow: 0px 0px 0px 1px rgba(49,38,59,0.22), 0px 103px 103px 0px rgba(49,38,59,0.03), 0px 26px 57px 0px rgba(49,38,59,0.05)`

**Observed:** Panels remain upright and crisp, with thin chrome and plausible interface contents.

**Transfer:** Use original product screens or build a small realistic UI with one legible task.

#### Blush proof band · level 0

**Use:** A compact horizontal quotation interlude.

**CSS:** `background: #fcf8f8; border-top: 1px solid #dbd7da`

**Observed:** Two parallel quotes, customer marks and compact attributions occupy a 300px band.

**Transfer:** Change the tonal value only slightly so proof remains part of the paper world.

#### Charcoal canvas · level 0

**Only for:** dark product, enterprise and pricing pages

**Use:** Immersive technical page variant.

**CSS:** `background: #14141c; color: #f5c0c0`

**Observed:** Fine grain at 0.0625 opacity, subdued rose-gray page rails and sparse vertical guides; white headings sit above dusty rose copy.

**Transfer:** Switch the entire page's text, rule and action treatment together; retain the same drafting logic.

#### Lavender horizon · level 1

**Only for:** dark product openings

**Use:** Soft lift behind the lower opening and product imagery.

**CSS:** `background: radial-gradient(at 50% 100%, rgba(173,142,182,0.4), rgba(0,0,0,0) 70%)`

**Observed:** A low lavender haze emerges from the bottom center without becoming a bright neon spotlight.

**Transfer:** Match the soft glow; exact stops are not essential. Keep text outside its brightest center.

#### Recessed dark card · level 1

**Only for:** dark product galleries and testimonials

**Use:** Dark containers for bright interface previews or quotations.

**CSS:** `background: radial-gradient(circle at 66.66% 50%, rgba(26,26,37,0.5) 0%, rgba(15,15,21,0.5) 80%); border-radius: 12px; box-shadow: inset 0px 0px 24px 0px rgba(17,17,24,1), 0px 0.5px 0px 0.8px rgba(47,47,65,1), 1px 6px 6px 0px rgba(0,0,0,0.24), 0px 1px 3px 0px rgba(0,0,0,0.27)`

**Observed:** A faint lit upper edge and black inset shading establish shallow depth.

**Transfer:** Keep the edge light subtle; the white interface preview should supply the contrast.

## Components

### Navigation

**Use:** Persistent centered brand and balanced link groups.

**CSS:** `display: grid; grid-template-columns: 1fr max-content 1fr; align-items: center; padding: 12px 0px`

**Text style:** `nav` — Cinetype 400 · 14px/1

**Observed:** Brand mark sits at the exact center, with primary links on both sides and login plus a compact Primary button on the right. The 62px navigation row becomes a ruled floating strip when scrolling. The surrounding fixed header is 82px; the opening ticker sits above the row.

**Transfer:** Use a compact original mark, not a long wordmark that pushes the two link groups off balance.

### Announcement ticker

**Use:** Thin news ribbon above the opening navigation.

**CSS:** `display: flex; gap: 16px; padding: 4px 0px; overflow: hidden`

**Text style:** `ticker` — Cinetype Mono 400 · 12px/1.571

**Observed:** A 27px strip carries several repeated news items, tiny symbols and right arrows. Low-contrast gray-rose backing and an inset top edge distinguish it from navigation.

**Transfer:** Use several short real updates in a continuous single line.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 50px; padding: 0px 20px; border: 1px solid transparent; border-radius: 1px; background: linear-gradient(to right, #fffcfc, #fffcfc) padding-box, linear-gradient(45deg, #cda0a5, #31263b) border-box; color: #14141c`

**Text style:** `utility` — Cinetype 400 · 14px/1.571

**Observed:** A light rose inset overlay and small outlined corner loops make the control feel like a plate held in a drawing frame. Section controls use 42px height; the header version uses 38px height and 15px horizontal padding. Dark-page controls invert the interior to charcoal, the text to rose, and the outline to a rose-to-lavender gradient. Pricing controls are 40px tall, with the trial action receiving the corner-loop emphasis.

**States:** Declared: hover background-color #e9e5e8 and border-color #afa9b1; focus-visible outline 2px solid rgba(49,38,59,0.44), outline-offset 2px; active background-color #dbd7da. Dark variant: hover background-color #2b252c and border-color #6a565b; focus-visible outline 2px solid rgba(245,192,192,0.386), outline-offset 2px; active background-color #3a3138.

**Transfer:** Build loops as four decorative small circles or rounded corner arcs attached just outside the edge; keep the label and hit area simple.

### Secondary button

**Use:** Alternative conversion or contextual exploration.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 50px; padding: 0px 20px; border: 1px solid #dbd7da; border-radius: 1px; color: #31263b; background: transparent`

**Text style:** `utility` — Cinetype 400 · 14px/1.571

**Observed:** Shares the primary's rectangular proportions without the rose wash or ornamental corners. Contextual versions use 42px height. Dark versions use a dark rose-gray edge and rose text.

**States:** Declared: hover background-color #e9e5e8 and border-color #afa9b1; focus-visible outline 2px solid rgba(49,38,59,0.44), outline-offset 2px; active background-color #dbd7da.

### Inline capability capsule

**Use:** Clickable concepts embedded into a sentence beneath the opening headline.

**CSS:** `display: flex; align-items: center; gap: 8px; height: 43px; padding: 6px 12px 6px 6px; background: rgba(255,252,252,0.7); border: 1px solid #dbd7da; border-radius: 30px; box-shadow: 0px 2px 4px 0px rgba(1,1,27,0.06)`

**Observed:** A 28px pastel circular icon well precedes light 24px text. Capsules wrap together with connecting words into a centered two-line sentence, rather than becoming a standalone tag row.

**States:** Declared: hover background-color rgba(49,38,59,0.09), text-decoration none; focus-visible outline 2px solid rgba(49,38,59,0.44), outline-offset 2px; active background-color rgba(49,38,59,0.14).

**Transfer:** Use two or three meaningful capabilities, each with a distinct pastel icon well.

### Proof card

**Use:** Outcome-led customer proof in a continuous ruled row.

**CSS:** `display: flex; flex-direction: column; gap: 15px; padding: 30px; border-right: 1px solid #e9e5e8`

**Text style:** `card-heading` — PP Formula 600 · 20px/1.3 · tracking -0.025em

**Observed:** Customer mark first, compact outcome heading second, then a body-sm explanation. Four cells share one outer frame and have no individual rounded background.

**Transfer:** Keep headings about the result, not the customer's industry; use real approved proof.

### Technical tile

**Use:** Systematic capabilities or connections presented with spare line art.

**CSS:** `display: flex; position: relative; padding: 5px; background: rgba(49,38,59,0.05)`

**Text style:** `card-heading` — PP Formula 600 · 20px/1.3 · tracking -0.025em

**Observed:** The upper area holds a 300px by 160px line illustration; lower content has 20px side insets and a 35px lead-in before the title. Caption text follows after 7px. Tiles are about 373px wide, arranged three across.

**Transfer:** Draw simple original process diagrams, each explaining one relationship rather than filling the space with icons.

### FAQ row

**Use:** Compact late-page objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 20px; min-height: 64px; border-bottom: 1px solid #dbd7da; background: transparent`

**Text style:** `question` — Cinetype 400 · 18px/24px · tracking -0.028em

**Observed:** A 604px-wide stack with a single right chevron per row. Longer questions wrap naturally; answers expand beneath the question. Dark pages retain the construction with white questions and dark rose-gray rules.

**States:** Declared: focus-visible outline 2px solid rgba(49,38,59,0.44), outline-offset 2px.

### Footer columns

**Use:** Consistent ending for all page types.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 60px; max-width: 800px`

**Text style:** `footer-heading` — IBM Plex Mono 700 · 12px/1.571 · tracking 0.058em · uppercase

**Observed:** Four link categories sit between a small identity block and a technical decorative detail. Link stacks use utility text with 10px gaps. The enclosing footer has 50px vertical padding, top and bottom rules, and a lower legal row. A short 'Made with' line and changing emoji provide the human note.

**Transfer:** Keep the ending functional and compact; a small custom line ornament can balance the identity block without becoming a second hero.

### Editorial card

**Only for:** editorial, resource and company-story sections

**Use:** External articles, interviews and company updates.

**CSS:** `display: flex; flex-direction: column; padding: 10px; background: rgba(253,253,253,0.4); border-radius: 12px; backdrop-filter: blur(7.5px); box-shadow: inset 0px 0px 11px 0px rgba(0,0,0,0.05), 0px 0px 0px 1px rgba(0,0,0,0.06), 0px 16px 24px -8px rgba(0,0,0,0.05), 0px 8px 12px -4px rgba(0,0,0,0.05), 0px 4px 6px -2px rgba(0,0,0,0.05)`

**Text style:** `card-heading` — PP Formula 600 · 20px/1.3 · tracking -0.025em

**Observed:** A wide thumbnail sits above a multi-line title; publication and date are pushed toward the bottom. Desktop cards are 360px by 388px, with 340px by 175px thumbnails, in three columns.

**Transfer:** Keep the surrounding card neutral even when editorial thumbnails are vivid.

### Plan summary

**Only for:** pricing pages

**Use:** Comparable self-service and sales-led offers.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; padding: 48px 32px 32px; position: relative`

**Text style:** `feature-heading` — PP Formula 800 · 28px/1.3 · tracking -0.025em

**Observed:** Four equal plan columns are bracketed into two pairs with small mono category labels interrupting the top edge. Each column orders icon, plan name, short audience description, plan-price, full-width action and checkmarked features. Dashed vertical rails and corner marks replace conventional rounded pricing cards; one recommended plan has a fine stippled highlight.

**Transfer:** Keep price and action baselines aligned despite different descriptions. Scope the darker theatrical treatment to purchasing decisions.

## Imagery and graphics

### Drafting atmosphere

**Use:** Signature background language in the opening and proof assemblies.

**Observed:** Warm paper grain, faint square grids, stippled fades and registration corners surround the typography. The atmosphere stays subordinate to dark text; some diagrams use arcing trajectories with tiny floating icon nodes.

**Transfer:** Recreate the drafting language around new concepts; when there is no product artwork, a small relationship diagram is the minimum acceptable visual.

**Build:** Layer a warm paper base, an SVG feTurbulence noise overlay at 0.06 opacity, and a 64px grid of 1px light-gray lines. Mask the grid toward the central text. Add 8px–12px L-shaped corner marks in muted eggplant, then a sparse dot field using 1px radial dots with a fade. For trajectories use thin low-alpha SVG curves and a few circular nodes, not a dense network.

### Floating product scenes

**Use:** Feature chapters and major product demonstrations.

**Observed:** Upright white application windows show charts, maps, tables, chat or code with authentic chrome. One broad panel is overlapped by a smaller result, dropdown or conversational window. On paper the shadows are pale violet; on charcoal the shadows are deep and broad. Product content occupies more area than the neighboring copy.

**Transfer:** Stage an original task with a useful result, a focused control and a believable supporting window. If no finished interface exists, construct a clean UI fragment with a real content hierarchy rather than an empty white card.

### Technical line illustrations

**Use:** Conceptual features and compact technical tiles.

**Observed:** Fine eggplant or rose strokes draw perspective grids, flat documents, stepped blocks, rings, toggles and connecting stems. Most surfaces are translucent or unfilled; color enters through small nodes and third-party marks rather than large painted shapes.

**Transfer:** Explain the new product's relationships using the same thin, schematic grammar.

**Build:** Use SVG paths at 1px stroke with low-alpha eggplant on paper or dusty rose on charcoal. Draw a perspective base as a shallow trapezoid with receding grid lines; float one or two outlined rectangular planes above it. Add a 20px–40px circular node or small mint indicator, with restrained translucent fills. Keep most of the drawing open.

### Compounding diagram

**Use:** A distinctive conceptual chapter graphic.

**Observed:** A large stippled circular plate is orbited by three smaller white roundels with line icons and curved micro-labels. Fine concentric paths connect the parts; the central label is compact sans.

**Transfer:** Use three mutually reinforcing stages of the new product, with one short central outcome.

**Build:** Make a roughly 417px circular plate with a 1px paper edge, soft shadow and masked dot field. Place three approximately 151px white roundels around its perimeter; add an SVG 543px orbital path behind them. Use a small central heading and text-on-path captions. Keep colored accents confined to tiny nodes.

### Lavender stage glow

**Only for:** dark product openings

**Use:** Atmospheric backing for large product media.

**Observed:** A muted lavender glow rises from below a centered opening and diffuses into charcoal, leaving the upper copy comparatively dark-backed.

**Transfer:** Use a low-saturation horizon light under the product scene, not a rainbow mesh.

**Build:** Place a bottom-centered radial gradient of rgba(173,142,182,0.4) to transparent at 70% across a wide charcoal stage. Keep the fade broad; add fine noise above it and place white interface panels in front.

### Team photography collage

**Only for:** company and culture pages

**Use:** Human proof and a less formal close to the company story.

**Observed:** A wide candid team photograph opens the story beside mission copy; later varied landscape and portrait photographs form a loose overlapping mosaic. Natural daylight, events and playful moments retain their original color, within softly rounded paper frames.

**Transfer:** Use authentic team activity and varied aspect ratios; avoid replacing it with a corporate stock-photo grid.

### Editorial thumbnails

**Only for:** resource and company-story sections

**Use:** Media-card previews.

**Observed:** Colorful event graphics, interview portraits and publication artwork sit inside restrained near-white cards. Images are wide and shallow, while titles and dates provide a consistent scaffold.

**Transfer:** Allow the content's own palette inside thumbnails while maintaining the surrounding paper material.

### Icons

**Observed:** Most action arrows and small glyphs are about 15px, with 10px by 7px dropdown chevrons. Concept icons use fine 1px line work; larger diagrams use simple geometric outlines. Mint checkmarks punctuate trust and plan lists, while capability capsules use 28px pastel circular wells.

**Transfer:** Choose spare geometric icons with light strokes; keep arrows and chevrons small and aligned to the text baseline. Use mint checks for affirmative feature proof, not as large badges.

## Section recipes

How recurring sections are built.

### First screen: Typographic drafting-board opening

**Observed:** A 700px tall paper stage fills the first screen above a 188px customer strip. Back-to-front layers are warm paper, subtle grain, fading stippled/grid atmosphere, small technical corner marks, centered headline and supporting controls. The headline spans about two thirds of the desktop width: display sans above a larger slender display-italic phrase, with a small rose sparkle near the upper right. Below it, a lead-sized sentence wraps within 580px and embeds Inline capability capsules. A centered pair of Primary button and Secondary button follows with a 20px gap and roughly 40px separation from the support block. The first 900px shows navigation, ticker, full headline, support, both actions and two rows of customer marks. The main object is the typographic composition itself; product-window scenes begin below the fold.

**Transfer:** Replace the category statement and human aside with a similarly balanced promise. Use two or three original capability capsules and a small geometric sparkle built from short radial lines. If product imagery is unavailable, keep this typographic first screen and introduce a Technical line illustration later. A company page opens with a mixed heading above a photo-and-mission split; enterprise uses a 68px left-aligned statement and a line illustration; pricing uses a plain 60px title above plan columns; dark product pages use a centered 60px statement, a compact category/docs capsule and a lavender-backed scene extending below the fold.

**Avoid:** Do not force a giant laptop, photograph or oversized logo into this opening; do not make the italic phrase a bold sans line or turn all support words into pills.

**Text style:** `display` — PP Formula SemiExtended 700 · 74px/1.2 · tracking -0.025em

### Heading pair

**Observed:** A heading-lg statement combines with a heading-italic phrase, either on separate centered lines or within a single long line. A 20px or 24px support paragraph follows with about 15px–20px space. The phrase carries emotion while the sans carries the concrete claim.

**Transfer:** Use the italic for the human benefit or framing phrase and the sans for the substantive statement; wrap at natural phrase boundaries.

**Text style:** `heading-lg` — PP Formula SemiExtended 700 · 60px/1.3 · tracking -0.0308em

### Feature and working scene

**Observed:** Within the content container, a narrow copy column contains a line icon, feature-heading, contextual 42px action and compact quote below a dashed rule. A larger Floating product scenes composition sits beside it; some windows deliberately extend beyond the container. Columns alternate selectively, with 60px vertical insets and wide breathing room.

**Transfer:** Explain one task per scene, and let the interface visibly complete it. Use short relevant proof near the feature rather than a generic paragraph.

**Text style:** `feature-heading` — PP Formula 800 · 28px/1.3 · tracking -0.025em

### Paired principle panels

**Observed:** Two Glass paper panels sit side by side with a 20px gutter. Each has a shallow line-art scene, a small tinted annotation, feature-heading, short body-sm paragraphs or bullets and an action near the bottom. Panels use 6px corners, about 610px width and a 256px illustration area.

**Transfer:** Pair complementary differentiators such as freedom and control; maintain equal visual weight without duplicating the same content format.

**Text style:** `feature-heading` — PP Formula 800 · 28px/1.3 · tracking -0.025em

### Framed proof assembly

**Observed:** A 1176px wide frame joins a drafting-field headline region to four Proof cards below it. Registration corners, 64px grid cells and hairline dividers create one assembly. A larger quote card and compact review or award proof continue beneath, rather than repeating four more identical cells.

**Transfer:** Use the frame to collect one strong proof narrative; mix short outcomes with a longer authentic customer voice.

**Text style:** `heading-lg` — PP Formula SemiExtended 700 · 60px/1.3 · tracking -0.0308em

### Technical capability grid

**Observed:** A centered Heading pair and narrow lead line introduce three-column Technical tiles. Each tile reserves its upper half for spare SVG line art and its lower half for card-heading and caption. The grid uses 20px gutters and two rows when needed; small connection controls can sit within the artwork.

**Transfer:** Use this construction for integrations, architecture, workflows or interoperable systems, not just lists of product logos.

**Text style:** `card-heading` — PP Formula 600 · 20px/1.3 · tracking -0.025em

### Conversion bridge

**Observed:** The light variant uses a 263px high band with dashed top and bottom borders inside 100px vertical outer padding. A roughly 940px content area divides a feature-heading, body line and two actions from a narrower plan-discovery column separated by a dashed vertical rule. Dark enterprise uses a large statement and check list beside a bordered call card; dark product uses a centered 40px invitation and a single action in a fine frame.

**Transfer:** Offer an immediate next step and a lower-commitment path, keeping the visual tone of the current page instead of introducing a generic colored CTA slab.

**Text style:** `feature-heading` — PP Formula 800 · 28px/1.3 · tracking -0.025em

### Fading rules and questions

**Observed:** A bundle of 1px horizontal rules spaced 3px apart fades through decreasing opacity above the narrow FAQ. The FAQ uses a centered 40px title, 36px lead-in to FAQ rows and a small contact line beneath. On dark pages the rules are rose-gray; on paper they are gray-violet.

**Transfer:** Use the fading-rule device as the final chapter transition even if a short page closes without FAQ. Choose actual purchase or adoption questions.

**Text style:** `heading` — PP Formula 800 · 40px/1.3 · tracking -0.025em

### Ruled human footer

**Observed:** A 555px footer is bounded by hairlines and outer page rails, followed by a 32px bottom rail zone. Footer columns sit centrally, a small identity and playful made-with line sit left, and a tiny technical detail balances the right. Legal links are a subdued line below the categories. The light or charcoal page theme continues all the way to the end.

**Transfer:** Finish with useful navigation and a small human detail, not another oversized sales claim. On company-story pages this follows the photography directly; product pages follow the final contact card, and pricing and enterprise follow questions.

**Text style:** `footer-heading` — IBM Plex Mono 700 · 12px/1.571 · tracking 0.058em · uppercase

### Numbered assurance chapter

**Only for:** enterprise pages

**Observed:** A major white heading introduces two-column text blocks with lavender chapter-number markers, feature-heading titles and rose body copy. Compliance or assurance marks appear in separate outlined squares beside the text. Large chapter gaps preserve the expansive dark stage.

**Transfer:** Ground trust claims in concrete controls, certifications or service commitments, using only supported assertions.

**Text style:** `chapter-number` — IBM Plex Mono 300 · 16px/1.5 · tracking 0.125em · uppercase

### Product gallery and alternating chapters

**Only for:** dark product landing pages

**Observed:** A centered major promise and support precede a wide White product panel. A three-column gallery follows with dark recessed cards and bright original app previews, small mono tags and compact headings. Later chapters alternate narrow 40px headings and rose body copy with oversized white product windows, with about 160px between scenes.

**Transfer:** Show a range of useful outputs before examining individual interactions. Preserve bright product content against the dark canvas.

**Text style:** `heading` — PP Formula 800 · 40px/1.3 · tracking -0.025em

### Pricing architecture

**Only for:** pricing pages

**Observed:** A plain title and one utility-sized support line lead directly to Plan summary columns. Two bracketed plan groups, dashed rails, small category labels and one stippled recommended tier form the opening. A later five-column comparison uses roughly 46px rows and category breaks with card-heading labels. Repeated plan actions stay accessible above the matrix.

**Transfer:** Organize by audience and decision, align price and action rows, and keep comparison content readable without turning every cell into a card.

**Text style:** `heading-lg` — PP Formula SemiExtended 700 · 60px/1.3 · tracking -0.0308em

### Editorial and people chapters

**Only for:** company-story pages

**Observed:** Mixed serif/sans headings organize an investor-mark field, a three-column Editorial card grid and a more relaxed photo mosaic. The closing people chapter uses a left-aligned heading, mission-like support and two compact actions beside a loose collection of images.

**Transfer:** Use the company story to move from purpose to external confidence to people. Let photography break the rigid card rhythm without dropping the technical framing.

**Text style:** `heading-lg` — PP Formula SemiExtended 700 · 60px/1.3 · tracking -0.0308em

## Page flow

**Storyline:** Category promise → concrete working demonstration → differentiated capabilities → credible outcomes → adoption or purchase help → restrained final action and ruled footer.

### Introduce a broad platform with both technical depth and human accessibility

1. **Promise** — Mixed sans/italic opening with clickable capabilities and paired actions.
2. **Social proof** — Two rows of customer marks beneath a tiny technical label.
3. **Differentiation** — Centered thesis surrounded by subtle orbital icon art.
4. **Product demonstration** — Several narrow-copy and large-interface chapters, including a circular reinforcing-system diagram.
5. **Principles and proof** — Paired illustrated panels, quotation band, outcome-led proof frame and broader testimonial.
6. **Adoption** — Technical capability tiles and a dashed conversion bridge.
7. **Objection handling and ending** — Fading-rule transition, narrow FAQ, then ruled light footer.

**Transfer:** Use this for a broad product whose promise needs several visible forms of proof; shorten the number of chapters without losing the signature drafting atmosphere.

### Explain the organization behind the product

1. **Purpose** — Mixed headline above a candid team photo beside mission and company narrative.
2. **External confidence** — Customer strip and investor-mark field with a short editorial heading.
3. **Public presence** — Three-column editorial cards with thumbnails, titles, publication and date.
4. **People and invitation** — Loose team-photo mosaic beside a hiring or handbook invitation.
5. **Ending** — The light ruled footer follows the people chapter directly.

**Transfer:** Replace the organizational facts with a truthful origin, external confidence and authentic people imagery; do not add a generic FAQ just to match other page types.

### Resolve high-stakes adoption and trust concerns

1. **Promise** — Dark split hero with a tall sans statement, rose support, two-column check list and technical line illustration.
2. **Social proof** — A restrained tinted strip of customer marks.
3. **Assurance chapters** — Numbered compliance blocks, governance illustration and a support-focused chapter.
4. **Adoption** — Mixed editorial heading and technical integration tiles.
5. **Closing call** — Complete-solution statement and check list beside a bordered sales invitation.
6. **Objection handling and ending** — Fading rules, FAQ and dark ruled footer.

**Transfer:** Move from operational risk to concrete controls and support, then make evaluation easy.

### Help a visitor compare offers and choose a commitment level

1. **Decision framing** — Plain title, compact help line and four plan columns grouped in bracketed pairs.
2. **Social proof** — Quiet customer-mark band.
3. **Comparison** — Aligned matrix with repeated plan headers and category-based rows.
4. **Objection handling** — FAQ focused on trial, cancellation, credits and eligibility.
5. **Ending** — Dark ruled footer after the contact line; no separate large conversion hero.

**Transfer:** Use the common frame and type system while prioritizing comparison density over editorial drama.

### Make a specific product capability tangible and desirable

1. **Promise** — Centered dark hero, compact category/docs capsule, rose support and paired actions over a lavender horizon.
2. **Product demonstration** — A large working interface and a gallery of possible outputs.
3. **Capability chapters** — Alternating scenes show creation, presentation, follow-up, exploration and delivery with short action-led headings.
4. **Social proof** — Two dark quote cards.
5. **Collaboration proof** — Large main window overlapped by comment, sharing and revision details.
6. **Closing call and ending** — Fading-rule transition, framed contact invitation and dark ruled footer; no FAQ.

**Transfer:** Begin with a broad output promise, then show the actual interactions that make it believable. Let the last product scene demonstrate shared use before inviting contact.

## Writing

Confident, curious and technically literate, with enough playfulness to feel made by real people. Benefits are stated plainly and backed with visible workflows, named controls or customer stories rather than abstract superlatives alone.

**Do not copy:** Do not reuse Hex's name, logo, proprietary artwork, customer or investor marks, quotes, performance numbers, pricing, certifications or product-specific claims. Supply original content and verified claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we for the people building or supporting the product. Name the product where a concrete capability needs a subject.
- **Rhythm:** Short outcome headlines mix with light one- or two-sentence support. Feature titles are often verbs or a compact question-and-answer pair; utility labels stay brief. Occasional conversational asides and playful company copy soften the technical vocabulary.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category, then add a human or audience-oriented reframing phrase. | 7–12 words | “The Analytics platform for humans and agents” |
| Feature heading | A useful action paired with its desirable result. | 5–12 words | “Ask a question, get a trusted answer”<br>“Ground every answer in your organization’s context” |
| Supporting line | Explain the practical mechanism in an accessible sentence, including credible specifics where helpful. | 10–30 words | “Out-of-the-box connections and flexible APIs make setup a breeze.”<br>“Connect to data, provision users, and enforce permissions with ease.” |
| Product chapter heading | Conversational action fragments or a question answered immediately. | 3–8 words | “Follow-up question? Just ask.”<br>“Prompt, build, share” |
| Action | Concrete verb plus destination, with free or trial qualifiers only when true. | 2–6 words | “Get started for free”<br>“Explore the Context Engine”<br>“Contact Sales” |
| Closing help | A low-pressure invitation to resolve uncertainty. | 4–18 words | “Questions? Talk to us”<br>“Get in touch and find out which plan is right for you.” |

**Words and phrasing to use:** build; share; explore; trusted; your team; context; with ease; right where you need them; get started; beautiful

**Avoid:** revolutionary synergy; 10x everything; unleash limitless potential; frictionless paradigm; enterprise jargon without a named control; unqualified guarantees

**Rules:**

- Pair an ambitious statement with a visible mechanism or result nearby.
- Use technical nouns when they clarify implementation; explain the user benefit in ordinary language.
- Write headings that remain meaningful without their illustration.
- Keep testimonials in their actual customer's voice and separate them visibly from product claims.
- Use playful details in company copy, the ticker or the footer rather than sprinkling jokes into every trust claim.

## Do's and Don'ts

### Do

- Pair 74px bold display sans with a much lighter 96.2px italic phrase in the default opening.
- Keep core body paragraphs at 20px/1.5 and reserve 14px for utility or compact descriptions.
- Use the 1240px content container and 20px gutters for repeatable card systems.
- Include 1px drafting rails and fading grid fields around major assemblies.
- Give the primary action a near-square outline and 50px hero height, with 42px contextual and 38px header variants.
- Stage bright, upright interface panels with 4px–6px corners and at least one overlapping supporting detail.
- Use rose support text and dark rose-gray rules consistently throughout a dark variant.
- Retain the final multi-column ruled footer and its small human note.

### Don't

- Do not turn the default paper page into a black background merely because the specialist product variant is dark.
- Do not use the serif for body paragraphs or replace the light italic contrast with a heavy italic grotesk.
- Do not round primary and secondary buttons into 24px-radius pills; reserve that silhouette for sentence capsules.
- Do not add saturated gradients to broad ordinary marketing sections; color belongs mainly to small details and product content.
- Do not make every content group a raised 12px card; proof rows share straight dividers and technical tiles remain flat.
- Do not flatten the product storytelling into equally sized thumbnails with no dominant window.
- Do not use 4px or 6px heavy borders for the drafting frame; hairlines are 1px.
- Do not let grain become coarse texture or render the 64px grid at full strength behind all paragraph text.

## Motion and responsive

### Motion

**Observed:**

- Declared: the announcement ticker runs continuously for 56s with linear timing.
- Declared: button background and border transitions use 0.25s cubic-bezier(0.25, 0.1, 0.25, 1); many simple links use background-color 0.1s linear.
- Declared: paper-noise animations include 8s and 16s linear repeating cycles; some noise layers are paused.
- Declared: cards transition border, transform and box-shadow over 529.33ms using a sampled linear easing.

**Transfer:**

- Keep motion concentrated in the narrow news ribbon, subtle texture and small control feedback rather than moving whole text sections continuously.
- Preserve the staged overlap of product windows when animating them; the final resting composition must be complete and legible.

**Unknown:**

- Complete sampled card easing, exact scroll choreography and all reduced-motion behavior are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 360px, 420px, 450px, 480px, 600px, 767px, 800px, 801px, 1000px, 1250px, 1381px and 1638px.
- Display and heading sizes use the clamp formulas recorded in the type recipes.

**Transfer:**

- On narrow layouts, keep the mixed headline as the first visual event and allow capability capsules to wrap with their connecting sentence.
- Stack copy before its product scene; preserve a main panel and one supporting overlay rather than shrinking every window to unreadable scale.
- Reduce multi-column proof and technical grids progressively while keeping thin rules and registration marks visible; allow the pricing matrix its own horizontal scrolling region.

**Unknown:**

- Specific mobile menu behavior, exact grid-collapse thresholds and narrow-screen media arrangements are not established; the stacking rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
