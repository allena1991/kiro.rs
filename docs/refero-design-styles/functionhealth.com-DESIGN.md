# Function Health — terracotta meets human science

## Overview

A warm, editorial approach to serious technology, balancing human reassurance with scientific depth. Cream and oatmeal surfaces, charcoal text and burnt terracotta accents support fine serif headlines, expressive italics and light sans-serif explanations. Cinematic portraits, restrained data illustrations and intimate customer films make a spacious, predominantly light experience suited to consequential services and membership products.

### Essentials

- Headlines turn a factual statement into a human promise: Financier Display at 80px/0.9 for the opening and 64px/1 for section leads, weight 300, normal tracking, with an italic phrase rather than a second type family.
- The opening is a human scene, not a software billboard: an 860px full-bleed portrait stage beneath a 40px announcement strip, bottom-left copy within 540px, one light 50px pill action and three compact proof points aligned at lower right. Use a warmly lit contextual portrait when no product film exists.
- The page is mostly warm paper: #fef9ef canvas and #f5eee1 cards and closing bands; #b05a36 belongs to italic phrases, actions, fine icons and one emphatic comparison column rather than whole bright sections.
- Actions feel compact and rounded against delicate typography: 16px/1.5 sans-serif at weight 600, 12px 25px padding, 50px height and pill corners; pair a terracotta fill with a terracotta outline on light sections.
- Proof has two human scales: square expert portraits with names below and 288px × 512px customer films with 12px corners, dark lower fades and central frosted play circles. For products without filmed stories, use real customer portraits and concise approved quotations in the same frames.
- A visual proof device interrupts the paper without turning the site into a dashboard: fine terracotta charts, dot maps or small explanatory diagrams sit in warm cards. Every new page needs a compact visual explanation of change, reach or process; use a simple SVG chart if no interface is available.
- The ending is a small editorial provocation followed by a substantial paper object: a 64px mixed roman/italic closing line on an oatmeal band, then an inset cream footer with 24px corners, 56px padding and a broad soft shadow. Keep the device even when the closing message changes.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt terracotta | `#b05a36` | `--color-accent` | accent, text, action, border, link | Italic emphasis, primary actions, outline actions, small checks and announcement strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Field white | `#ffffff` | `--color-field` | surface | Small form fields, not the general page canvas. |
| Cream paper | `#fef9ef` | `--color-canvas` | background, text, surface | Dominant page canvas and light text over dark photography. |
| Oatmeal | `#f5eee1` | `--color-oatmeal` | surface, background | Process cards, logo tiles, accordion rows and the shared closing/footer band. |
| Warm stone | `#ddd6ca` | `--color-media-base` | surface | Backing beneath customer media; always covered by imagery. |
| Warm hairline | `#d1c9bf` | `--color-rule` | border | Card outlines, grid rules and quiet dividers. |
| Field edge | `#737373` | `--color-field-edge` | border | Input outlines that remain slightly stronger than card rules. |
| Graphite | `#515151` | `--color-muted` | text | Secondary copy and large quantitative proof numerals. |
| Charcoal | `#2a2b2f` | `--color-ink` | text, background, action | Headlines, body copy, dark image backing and interactive dark states. |

## Typography

- **Financier Display** — Display headlines, section headings, card headings and prices. Fine, high-contrast editorial serif with slender roman forms and fluid, sharply sloped italics. If unavailable, use **Cormorant Garamond**. Use weight 300 and genuine italic; tune wrapping to preserve the compact lines. Font stack: "Financier Display", "Cormorant Garamond", Georgia, serif.
- **FT Base** — Paragraphs, navigation, actions, names and quantitative proof. Open, rounded contemporary sans-serif; light prose contrasts with semibold labels. If unavailable, use **DM Sans**. Use weights 300 and 600; retain normal tracking except for large stat numerals. Font stack: "FT Base", "DM Sans", system-ui, sans-serif.
- **Fragment Mono** — Portrait quotation credits and motion-control labels. Small technical capitals with clear, evenly spaced letterforms. Font stack: "Fragment Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display-italic | Financier Display | 300 italic | 80px | 0.9 | normal | fixed | Default cinematic opening headline in cream; also the accented phrase of editorial openings. |
| display-roman | Financier Display | 300 | 80px | 0.9 | normal | fixed | Large price amounts and roman portions of display statements. |
| heading | Financier Display | 300 | 64px | 1 | normal | fixed | Main section headings and closing statements. |
| heading-italic | Financier Display | 300 italic | 64px | 1 | normal | fixed | Terracotta phrase within a section heading; strikethrough is reserved for superseded prices, not ordinary italic emphasis. |
| stat | FT Base | 300 | 64px | 1 | -2px | fixed | Large numbers in outlined proof cards. |
| heading-card | Financier Display | 300 | 45px | 1 | normal | fixed | Capability categories and membership card names. |
| heading-small | Financier Display | 300 | 34px | 1.15 | normal | fixed | Numbered explanatory card titles. |
| newsletter-heading | Financier Display | 300 | 27.6px | 1.1 | normal | size clamp(1.625rem, 1.5rem + 0.25vw, 1.875rem) | Small editorial footer invitation; accent its final phrase in italic terracotta at the same size. |
| hero-proof | FT Base | 600 | 24px | 1.25 | normal | fixed | Three short proof values against opening photography. |
| price-period | FT Base | 300 | 24px | 1.5 | normal | fixed | Small billing period baseline-aligned beside a display price. |
| section-support | FT Base | 300 | 20px | 1.5 | normal | fixed | Centered support line beneath major section headings. |
| item-heading | FT Base | 600 | 20px | 1.5 | normal | fixed | Process numbers and short feature headings. |
| body-lead | FT Base | 300 | 18px | 1.5 | normal | fixed | Hero explanation and feature paragraphs. |
| person-name | FT Base | 600 | 18px | 1.5 | normal | fixed | Expert and team names. |
| body | FT Base | 300 | 16px | 1.5 | normal | fixed | Navigation links, feature lists and compact explanatory copy. |
| action | FT Base | 600 | 16px | 1.5 | normal | fixed | Buttons, accordion questions and prominent field labels. |
| film-caption | FT Base | 300 | 16px | 1.2 | normal | fixed | Short customer story synopsis over the bottom image fade. |
| caption | FT Base | 300 | 14px | 1.5 | normal | fixed | Compact descriptions and secondary captions. |
| label | FT Base | 600 | 14px | 1.5 | normal | fixed | Footer column headings and small credibility labels. |
| technical-credit | Fragment Mono | 400 | 11px | 1.2 | 0.1em, uppercase | fixed | Quotation credits over portraits and motion labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| specialist service catalogs | offer-title | FT Base | 600 | 24px | 1.2 | normal | fixed | Dense service-plan card headings. |
| process walkthroughs | step-eyebrow | FT Base | 600 | 16px | 1.2 | 0.05em, uppercase | fixed | Step number and short chapter label. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep roman and italic heading phrases within one continuous sentence. The italic phrase can start or finish the statement and can wrap as a unit.
- Do not tighten the serif tracking. Its delicacy comes from weight 300 and close line heights, not negative letter spacing.
- Sans-serif prose is predominantly weight 300; reserve 600 for actions, names and compact headings. Large numerical proof is sans-serif, while prices are serif.
- The display headline is intentionally smaller than the dominant human subject. It does not compete with the face for the full screen.

## Layout

**Density:** Airy between chapters, compact within information blocks; broad paper margins frame small, readable units.

### Spacing

**Spacing system:**

- **step** 8px — Common working increment for larger gaps; 12px is also a frequent declared compact gap.

| Value | Use |
| --- | --- |
| 8px | Card title-to-description gap and small inline groups. |
| 12px | Accordion row gaps, name-to-image gaps and form gaps. |
| 16px | Headline-to-support gap and paired action gap. |
| 24px | Portrait grid gaps and proof-card inner padding. |
| 32px | Three- and four-column card gutters and content group separation. |
| 40px | Hero support-to-action gap and process-card vertical padding. |
| 56px | Raised panel padding and split proof section gutter. |
| 64px | Section-heading-to-content gap and footer group separation. |
| 80px | Alternate feature-section top padding and split editorial opening gutter. |
| 99.2px | Default major-section top and bottom padding. |
| 120px | Closing band's upper padding and lower footer row separation. |

### Containers and grids

- **content-container**: max width 1376px · side padding 96px. Centered desktop sections occupy 1248px at a 1440px viewport; retain wide outer paper margins.
- **header-shell**: max width 1440px · side padding 64px. Navigation projects wider than the section content; the inner bar is 1312px wide at desktop.
- **process-grid**: 3 columns · gap 32px. Equal-width numbered cards under a centered heading.
- **portrait-grid**: 4 columns · gap 32px. Customer film row or mixed portrait-and-award mosaic.
- **feature-split**: 2 columns · gap 80px. A 612px × 535px media block beside explanatory text; reverse the media side between chapters.
- **narrow-panel**: max width 1088px. Comparison table and raised pricing panel, inset further than ordinary content.
- **accordion-column**: max width 864px. Centered list of questions or opportunity categories.
- **editorial-split** (only for institutional and recruiting pages): 2 columns · gap 80px. Nearly equal columns for a large left headline and right prose in institutional openings.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-fields | 9999px (pill) |
|  | media-and-cards | 12px |
|  | portrait-and-accordion | 6px |
|  | raised-panels | 24px |
|  | small-square-control | 4px |
| process walkthroughs | walkthrough-top-corners | 40px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| raised-paper | `12px 32px 80px 0px rgba(42,43,47,0.1)` | Pricing and footer panels only. |
| light-hero-action | `0px 2px 12px 0px rgba(0,0,0,0.1)` | Light action over the cinematic opening. |
| play-glass | `0px 0px 32px 0px rgba(0,0,0,0.15)` | Circular play controls over customer films. |

### Surfaces

#### Paper canvas · level 0

**Use:** Ordinary page sections.

**CSS:** `background: #fef9ef; color: #2a2b2f`

#### Oatmeal band · level 0

**Use:** Continuous closing and footer background.

**CSS:** `background: #f5eee1`

**Observed:** The closing message and inset footer share one tonal field.

**Transfer:** Let the footer read as an object placed on the band's backing.

#### Flat warm card · level 1

**Use:** Explanatory cards and logo tiles.

**CSS:** `background: #f5eee1; border-radius: 12px; box-shadow: none`

**Observed:** Subtle tonal separation replaces outlines on most explanatory cards.

**Transfer:** Use for small illustrations with short explanations.

#### Outlined proof · level 1

**Use:** Numerical proof and small operational facts.

**CSS:** `background: #fef9ef; border: 1px solid #d1c9bf; border-radius: 12px`

**Observed:** Shares the canvas color so that the fine outline defines the box.

**Transfer:** Pair a large number with one small chart or pictorial explanation.

#### Raised paper · level 2

**Use:** Conversion panel and footer.

**CSS:** `background: #fef9ef; border-radius: 24px; box-shadow: 12px 32px 80px 0px rgba(42,43,47,0.1)`

**Observed:** Only a few broad panels receive the long diffuse shadow.

**Transfer:** Reserve elevation for high-level conversion and utility groups.

#### Dark portrait stage · level 0

**Use:** Cinematic product opening.

**CSS:** `background: #2a2b2f; color: #fef9ef`

**Observed:** Full-bleed moving portrait with darker lower and left regions supporting copy; the natural photographic colors remain visible.

**Transfer:** Use a contextual human portrait and a restrained dark gradient, not a flat black hero.

#### Comparison highlight · level 2

**Use:** Selected product column within a comparison table.

**CSS:** `background: linear-gradient(#b05a36, rgba(216,161,131,0.96)); border-radius: 24px; box-shadow: 0px 4px 30px 0px rgba(0,0,0,0.1)`

**Observed:** A narrow vertical terracotta column projects above a wide oatmeal table; cream rules cross the highlighted column.

**Transfer:** Use for one emphatic contrast, not every pricing card.

#### Frosted play glass · level 3

**Use:** Play control over portrait film.

**CSS:** `background: linear-gradient(202deg, rgba(254,249,239,0) 52.18%, rgba(254,249,239,0.4) 135.96%); border-radius: 9999px; backdrop-filter: blur(25.6px); box-shadow: 0px 0px 32px 0px rgba(0,0,0,0.15)`

**Observed:** The portrait remains legible through an 80px circular lens.

**Transfer:** Keep glass localized to media controls; do not make all cards translucent.

#### Stacked chapter sheet · level 1

**Only for:** process walkthroughs

**Use:** Sticky procedural chapters.

**CSS:** `background: #fef9ef; border-top: 1px solid #d1c9bf; border-radius: 40px 40px 0px 0px; position: sticky`

**Observed:** Each new sheet overlaps the previous content while earlier chapter labels remain visible above it.

**Transfer:** Use when a process benefits from a deliberate chapter-by-chapter explanation.

## Components

### Navigation

**Use:** Persistent marketing navigation above the main content.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 80px; padding: 8px 32px; background: rgba(0,0,0,0.07); border-radius: 12px; backdrop-filter: blur(20px)`

**Text style:** `body` — FT Base 300 · 16px/1.5

**Observed:** Logo left, centered text links, login and conversion action right, then search and menu icons. Both text links and menu icon are present on desktop. The photographic opening uses cream text and a light action; light content uses charcoal links, terracotta brand color and a filled primary action.

**Transfer:** Keep the desktop bar wider than the content container and change its contrast with the backing.

### Primary button

**Use:** Main conversion on light content.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 50px; padding: 12px 25px; background: #b05a36; color: #fef9ef; border: 1px solid #b05a36; border-radius: 9999px`

**Text style:** `action` — FT Base 600 · 16px/1.5

**Observed:** Compact content-width pill, or full-width within a pricing column; centered labels.

**States:** Declared: hover background #2a2b2f, color #fef9ef and border-color #2a2b2f; focus-visible uses the same colors with 2px solid rgba(176,90,54,0.35) outline and 2px outline-offset.

### Secondary button

**Use:** Paired explanatory or exploratory action.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 50px; padding: 12px 25px; background: #fef9ef; color: #b05a36; border: 1px solid #b05a36; border-radius: 9999px`

**Text style:** `action` — FT Base 600 · 16px/1.5

**Observed:** Appears beside the primary action with 16px separation, not as a competing filled pill.

**States:** Declared: hover background #2a2b2f, color #fef9ef and border-color #2a2b2f; focus-visible uses the same colors with 2px solid rgba(176,90,54,0.35) outline and 2px outline-offset.

### Light hero button

**Use:** Conversion against dark photography.

**CSS:** `height: 50px; padding: 12px 25px; background: #fef9ef; color: #b05a36; border: 1px solid #fef9ef; border-radius: 9999px; box-shadow: 0px 2px 12px 0px rgba(0,0,0,0.1)`

**Text style:** `action` — FT Base 600 · 16px/1.5

**Observed:** Sits below a short support paragraph rather than directly beneath the headline.

**States:** Declared: hover background #b05a36, color #fef9ef and border-color #b05a36; focus-visible uses the same colors with 2px solid rgba(176,90,54,0.35) outline and 2px outline-offset.

### Numbered explanation card

**Use:** Make the first product explanation feel easy to understand.

**CSS:** `background: #f5eee1; border-radius: 12px; padding: 40px 20px; display: flex; flex-direction: column; align-items: center; gap: 8px`

**Text style:** `heading-small` — Financier Display 300 · 34px/1.15

**Observed:** Centered terracotta step number, serif title, small sans-serif support and a low-contrast illustration occupying the lower half. The image area is around 340px × 200px.

**Transfer:** Illustrate one idea per card using a miniature schedule, graph or action list, not a full application screen.

### Accordion row

**Use:** Questions and expandable category lists.

**CSS:** `background: #f5eee1; border: 1px solid #d1c9bf; border-radius: 6px; overflow: hidden`

**Text style:** `action` — FT Base 600 · 16px/1.5

**Observed:** A closed row is 62px tall within an 864px column. The question has 24px left padding; a cream 36px square with a 4px radius and fine warm outline holds a terracotta plus at right. Questions use 12px vertical padding; answers use body text. Recruiting categories use the same shape with 16px row gaps rather than 12px.

### Pricing panel

**Use:** One clear membership offer.

**CSS:** `background: #fef9ef; border: 1px solid #d1c9bf; border-radius: 24px; box-shadow: 12px 32px 80px 0px rgba(42,43,47,0.1); padding: 56px; display: grid; grid-template-columns: minmax(0px, 1fr) 1px minmax(0px, 1fr); gap: 56px`

**Text style:** `heading-card` — Financier Display 300 · 45px/1

**Observed:** Left: eligibility label, serif plan name, display price with small baseline period, annual billing note and full-width Primary button. Right: a single vertical checklist separated by a hairline. A heading above uses an italic crossed-out old amount inline with the current amount.

**Transfer:** Use one unambiguous offer and separate billing details from benefits.

### Stat card

**Use:** Operational or quantified proof.

**CSS:** `border: 1px solid #d1c9bf; border-radius: 12px; padding: 24px 24px 32px; display: grid; gap: 20px`

**Text style:** `stat` — FT Base 300 · 64px/1 · tracking -2px

**Observed:** Small mixed-weight label, large graphite sans-serif numeral and a restrained terracotta chart or dot map. One tall chart card can sit beside a map card and a shorter supporting fact.

**Transfer:** Replace the metric and figure with real proof while retaining the lightweight numeral.

### Customer film card

**Use:** Human outcome stories.

**CSS:** `background: #ddd6ca; border-radius: 12px; position: relative; overflow: hidden; width: 288px; height: 512px`

**Text style:** `film-caption` — FT Base 300 · 16px/1.2

**Observed:** Edge-to-edge portrait video or still; lower black fade holds a small semibold name and short lighter synopsis. Center an 80px Frosted play glass control containing a cream triangle. Four cards form a desktop row.

**Transfer:** Use authentic people speaking in familiar settings; a still portrait plus approved quotation is the minimum equivalent.

### Pill input

**Use:** Email subscription and location lookup.

**CSS:** `height: 48px; padding: 0px 20px; background: #ffffff; border: 1px solid #737373; border-radius: 9999px`

**Observed:** Single-line field beside a Primary button, with 12px gap; newsletter field width is 329px, location fields are shorter. The field is visually distinct from cream paper.

**Transfer:** Keep forms short and integrated with the explanatory text rather than inside separate heavy containers.

### Footer card

**Use:** Shared closing utility object.

**CSS:** `background: #fef9ef; border-radius: 24px; box-shadow: 12px 32px 80px 0px rgba(42,43,47,0.1); padding: 56px; display: flex; flex-direction: column; gap: 64px`

**Text style:** `body` — FT Base 300 · 16px/1.5

**Observed:** Brand mark above three narrow link columns at left and a serif newsletter invitation at right. Lower left holds distribution badges and a QR code; lower right holds small social circles and policy links. Dense disclosures and copyright remain outside the raised card on the oatmeal background.

**Transfer:** Replace distribution links with relevant product channels while keeping the two-level footer hierarchy.

### Comparison column

**Use:** Highlight the main product in a factual side-by-side comparison.

**CSS:** `background: linear-gradient(#b05a36, rgba(216,161,131,0.96)); border-radius: 24px; box-shadow: 0px 4px 30px 0px rgba(0,0,0,0.1); color: #fef9ef; width: 219px; padding-bottom: 56px`

**Text style:** `body` — FT Base 300 · 16px/1.5

**Observed:** Projects above the oatmeal comparison panel; rows are about 71px tall. Highlighted checkmarks are cream discs; the alternative uses quieter outlined crosses. Rules stay aligned across all columns.

**Transfer:** Compare verifiable capabilities with concise row labels rather than long sales paragraphs.

## Imagery and graphics

### Cinematic human portrait

**Use:** Default marketing opening.

**Observed:** A large side-profile portrait outdoors fills the entire width. Warm low sunlight catches the face and hair; muted olive hills and blue-gray sky recede behind it. The subject occupies the center and right while the bottom-left landscape darkens for text. The image dominates far more space than the headline.

**Transfer:** Photograph a real person in a context that conveys the product's benefit, with directional natural light and room for bottom-left copy. A still with the same framing is sufficient when film is unavailable.

### Miniature explanatory diagrams

**Use:** Numbered cards and visual proof between editorial sections.

**Observed:** Tiny cream cards, terracotta selected dates, sparse line charts with circular nodes, and stacked action rows float within oatmeal cards. The palette stays soft; no device chrome is needed.

**Transfer:** Reduce a workflow to one legible diagram per idea. Preserve generous blank space around the diagram rather than making a dense dashboard.

**Build:** Use a 340px × 200px SVG stage. Draw cream rounded tiles with 1px warm-gray edges, a thin terracotta trend path and small circular markers. Add only a few short gray labels; use translucent terracotta fills for selected states. Keep the whole illustration centered and narrower than its card.

### Portrait proof mosaic

**Use:** Editorial credibility section.

**Observed:** Four 288px-wide columns alternate short oatmeal award tiles and taller 288px × 379px portrait quotation cards. Portraits mix muted color and monochrome; dark lower fades support cream quotations with tiny uppercase mono names.

**Transfer:** Combine approved customer or expert photographs with genuine third-party recognition. If recognition assets are unavailable, use a concise attributed proof quote in the short tile rather than inventing a badge.

### Expert portraits

**Use:** Authority rails and grids.

**Observed:** Square chest-up portraits on natural, subdued backgrounds; rounded 6px edges, names below in semibold sans and two or three compact credential lines. Horizontal rails use 280px portraits and 32px gaps.

**Transfer:** Use authentic specialists or makers, with consistent framing and restrained color. Let credentials live below the photo, not on top of it.

### Dot map and bar proof

**Use:** Reach and growth sections.

**Observed:** Fine terracotta dots describe a geographic silhouette; an ascending column chart uses pale-to-deeper terracotta bars, faint horizontal guides and tiny labels. These graphics accompany large lightweight sans numerals in outlined paper cards.

**Transfer:** Represent a real distribution, growth pattern or relevant topology. When geography is irrelevant, a dotted system diagram can preserve the same material.

**Build:** Create an SVG silhouette or mask filled with 3px–5px circles on a regular 8px–12px lattice. Vary circle opacity between 0.15 and 0.65 using terracotta, leaving a few stronger nodes. For the chart, use narrow evenly spaced terracotta rectangles with opacity increasing left to right and 1px warm-gray guides.

### Contextual service photography

**Use:** Split feature chapters.

**Observed:** Warm, natural photographs in 612px × 535px rounded frames show real service use in familiar surroundings. Recruiting variants show a candid outdoor group rather than isolated corporate headshots.

**Transfer:** Show the action and setting that make the product tangible. Keep natural skin tones, modest contrast and the same broad landscape frame.

### Copper glass demonstration

**Only for:** process walkthroughs

**Use:** Illustrated product explanations within stacked chapters.

**Observed:** Square rounded artwork shows diagonal copper and charcoal ribbed material with a soft gray-green highlight. Translucent interface fragments, thin cream rules and large serif numerals float above it; small green status arcs are confined to the interface artwork.

**Transfer:** Use a small number of product-relevant interface fragments over a warm abstract material, not an entire screenshot. A simpler translucent statistic and one graph are an acceptable equivalent.

**Build:** In a square 12px-rounded frame, layer diagonal linear gradients at roughly 135deg using terracotta, charcoal and cream at varied alpha. Add parallel elongated polygons with soft shadows and an SVG turbulence mask at low opacity for grain. Overlay one or two rounded translucent panels with rgba(254,249,239,0.12) fill, a fine cream-alpha edge and backdrop blur. Keep the exact gradient stops subordinate to a warm, softly lit ribbed surface.

### Scan contour portrait

**Only for:** advanced technical product campaigns

**Use:** Specialist hero and feature imagery.

**Observed:** A side-profile human on a nearly black olive background is encircled by loose terracotta elliptical scan loops. A lighter version uses a cream background, soft portrait light and fine contour lines down the neck. A separate dark silhouette sits against warm apricot light with small floating coverage labels.

**Transfer:** Use a relevant object or human silhouette with sparse elliptical contour paths to imply investigation; do not turn the whole page into a glowing science-fiction scene.

**Build:** Overlay three or four tilted SVG elliptical paths around the upper subject, with no fill and a 3px terracotta stroke at approximately 0.6 opacity. Clip paths behind the subject on alternating segments to suggest depth. On light imagery, add a sparse 1px cream contour mesh at low opacity.

### Icons

**Observed:** Small terracotta outlined circle-checks are typically 18px with 1.5px–1.7px strokes. Search is 20px and menu 24px, using thin rounded strokes. Accordion plus signs sit inside 36px bordered cream squares; play icons are filled cream triangles.

**Transfer:** Choose a thin, uncomplicated outline set. Use terracotta for supportive checks, charcoal for utility controls on paper and cream against dark media; do not use heavy filled feature-icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Cinematic portrait opening

**Observed:** A 40px terracotta announcement strip sits above an 860px full-bleed image stage, filling the first 900px. The human subject dominates the central and right two thirds; a muted landscape extends to all edges. Dark backing and a low dark image fade sit behind the copy, then the portrait, then the frosted Navigation above and the text/action layer below. A small translucent eligibility badge precedes an 80px italic cream headline at lower left, followed by an 18px support paragraph within 540px and a Light hero button 40px below the paragraph. The copy block sits about 80px above the stage bottom. Three short hero-proof values with small sublabels and vertical hairlines occupy the lower right, level with the action. A small circular pause control sits at the far lower right. Headline, support, action, subject and proof all appear within the first screen; the next editorial section begins below it.

**Transfer:** Preserve the scale relationship between a dominant person or product-in-use photograph and compact lower copy. Without film, use a still environmental portrait with directional warm light. Institutional and recruiting pages instead open on paper with a left 80px roman/terracotta-italic statement and right prose/action column; a process page uses a centered roman/italic title above its first chapter. A specialist campaign can use a darker portrait and a roman/italic two-line claim.

**Avoid:** Do not center a giant headline over a tiny product mockup, place a dense dashboard behind the text, or replace the image stage with a feature-card grid.

**Text style:** `display-italic` — Financier Display 300 italic · 80px/0.9

### Editorial heading pair

**Observed:** A 64px roman heading includes one same-size terracotta italic phrase; support follows after 16px at 20px/1.5. Center the pair over grids, left-align it in split chapters. Leave about 64px before major content.

**Transfer:** Write a factual setup and an expressive conclusion as one sentence; keep the hierarchy even with different content.

**Text style:** `heading` — Financier Display 300 · 64px/1

### Three-part explanation

**Observed:** Editorial heading pair above a three-column process-grid of Numbered explanation cards, then centered Primary button and Secondary button. Cards use 32px gutters; major section padding is 99.2px.

**Transfer:** Explain an unfamiliar product with three concise ideas, each supported by a small visual rather than a paragraph wall.

### Ruled capability matrix

**Observed:** Three columns of 45px serif categories with fine vertical rules, small terracotta count labels and light sans-serif lists. A second row continues under horizontal rules; a final oatmeal cell carries a large italic continuation phrase and an outline action.

**Transfer:** Group a broad offering by user intent, with short examples and a separate deeper exploration action.

### Human proof chapters

**Observed:** An Editorial heading pair introduces either the Portrait proof mosaic or a row of Customer film cards. A separate expert rail uses square portraits with captions below, plus an outlined circular next control and a soft edge fade.

**Transfer:** Separate third-party credibility, customer outcomes and expert authority rather than mixing all proof into identical quote boxes.

### Quantified reach split

**Observed:** Left explanatory heading, short lead paragraph and compact location form; right a grouped set of Stat cards with large numerals, a chart, dot map and small service fact. The proof group is 672px wide with 20px internal gaps; the text-to-proof gap is 56px.

**Transfer:** Combine one concrete question the visitor can answer with visual proof of scale or availability.

### Raised comparison and offer

**Observed:** A centered editorial heading introduces the Comparison column inside an oatmeal table. Pricing uses a separate Pricing panel under a short statement with an inline crossed-out old amount and replacement price; three small rating quotations can sit below.

**Transfer:** Use comparison to establish the difference and a single offer to make the decision simple. Only cross out a price when the old price is genuine.

### Final editorial invitation

**Observed:** A 440px oatmeal band uses 120px top and 96px bottom padding. A centered 64px roman/terracotta-italic question is answered by a brief 20px line, then paired actions 64px below. Recruiting variants use a work-oriented statement and one action; process variants can use a fully italic aspirational line.

**Transfer:** Close with a short reversal of a familiar assumption, then an understated invitation. Retain the editorial device rather than another feature list.

**Text style:** `heading` — Financier Display 300 · 64px/1

### Inset utility ending

**Observed:** The Footer card follows on the same Oatmeal band, spanning the standard content width. A serif newsletter invitation occupies the right column while three link groups sit left. A secondary row supplies distribution and social links; disclosures continue below on the band, ending with a compact copyright line and 40px bottom padding.

**Transfer:** Keep useful navigation and subscription visually elevated; allow necessary legal content to remain outside rather than inflating the footer card.

### Stacked process chapters

**Only for:** process walkthroughs

**Observed:** A centered 80px roman/italic title gives way to overlapping Stack chapter sheets with 40px upper corners and a hairline top. Each has a terracotta step eyebrow, 64px serif heading, brief explanation, checks and an action at left; a square Copper glass demonstration fills the right half. Prior chapter labels remain visible as successive sheets rise.

**Transfer:** Use the sheet metaphor to pace a multi-step workflow; keep the illustrative material consistent across chapters.

**Text style:** `heading` — Financier Display 300 · 64px/1

### Specialist offer catalog

**Only for:** specialist service catalogs

**Observed:** Three equal oatmeal cards with 24px gutters present icon, semibold 24px title, short explanation, 45px serif price, vertically stacked filled/outline actions, timing and inclusion checks. A two-card centered row follows for smaller offers; qualifications sit beneath the grid.

**Transfer:** Keep price and actions aligned across cards despite different descriptions. Separate membership access from direct purchase pathways.

## Page flow

**Storyline:** Human promise → simple explanation → breadth and credibility → human outcomes → practical proof and value → objections → editorial closing invitation → inset utility footer.

### Broad product or membership landing page

1. **Promise** — Cinematic portrait opening with compact proof strip.
2. **Product explanation** — Three illustrated steps followed by a moving field of concise capability labels and a small trend diagram.
3. **Capability depth** — Expert quote and ruled category matrix.
4. **Social proof** — Portrait-and-recognition mosaic, customer films and expert rail.
5. **Practical proof** — Reach statistics and location form, then highlighted comparison table.
6. **Pricing** — Single raised membership offer and brief rating quotes.
7. **Objection handling** — Narrow accordion column.
8. **Closing call** — Editorial question-and-answer band followed by inset footer and external disclosures.

**Transfer:** Borrow the alternation of human scenes, precise explanation and decisive value; select the blocks appropriate to the new product rather than reproducing the full sequence.

### Institutional story and authority page

1. **Mission** — Paper split opening: display statement left, explanatory prose right.
2. **Credibility** — Ruled horizontal chapters with award and partnership tile groups.
3. **Authority** — Square expert portrait grid, operational stats and compact security banner.
4. **People** — Five-column leadership cards with warm consistent headshots.
5. **Recruiting invitation** — Candid team image beside benefits and action.
6. **Closing call** — Shared editorial closing band and full inset utility footer with disclosures.

**Transfer:** Introduce institutional conviction through prose, then substantiate it with people, recognition and practical safeguards.

### Recruiting and opportunity page

1. **Invitation** — Split typographic opening with a personal-benefit italic ending and openings action.
2. **Culture proof** — Candid group photograph beside short team narrative.
3. **Benefits** — Four airy icon-led columns beneath a centered heading pair.
4. **Opportunities** — Centered expandable category rows.
5. **Closing call** — Work-oriented mixed-style closing line, one action and the shared full footer.

**Transfer:** Use the paper-led variant to foreground the candidate's role and show real team life instead of a cinematic sales scene.

### Process explanation page

1. **Orientation** — Centered roman/italic display title.
2. **Walkthrough** — Overlapping numbered chapter sheets with consistent copper-backed illustrations.
3. **Value** — Raised pricing offer.
4. **Practical demonstration** — Contextual service photograph opposite steps and a short form.
5. **Capability extension** — Four illustrated feature columns.
6. **Closing call** — Italic aspirational line, paired actions and shared inset footer with disclosures.

**Transfer:** Make the chapter progression the centerpiece, then resolve cost and logistics without repeating the entire broad landing-page argument.

### Specialist product campaign and catalog

1. **Promise** — Dark portrait opening with contour-loop art and an editorial display claim.
2. **Product explanation** — Warm silhouette illustration beside benefits and access actions.
3. **Offer selection** — Three detailed service-plan cards, then a smaller two-card group and qualifications.
4. **Availability** — Dot-map illustration beside search form.
5. **Combined value** — Split feature chapter tying the specialist offer to the broader membership.
6. **Human outcomes** — Short rating quotes and one enlarged portrait story.
7. **Closing call** — Shared question-and-answer closing band and full inset utility footer with disclosures.

**Transfer:** Allow denser offer information inside warm cards while maintaining editorial headings and human proof outside the catalog.

## Writing

Reassuring and ambitious, with direct statements about what the service enables. Scientific seriousness is softened by personal agency, plain explanations and short, human conclusions.

**Do not copy:** Do not reuse Function or Ezra names, marks, partner logos, campaign slogans, proprietary illustrations, customer quotations, clinician identities, health claims, prices, test counts or longevity promises. Substitute verified content belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Use we for service commitments and a product name only when clarity requires it.
- **Rhythm:** Short declarative headlines often split into a literal setup and italic conclusion. Support lines are usually one or two sentences; detailed explanations stay in lists or compact paragraphs. Questions are rare and purposeful; exclamation marks are unnecessary.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Direct personal imperative, or capability followed by a human accessibility benefit. | 3–9 words | “Check your health.”<br>“MRI & CT now more accessible” |
| Section heading | Plain statement completed by a warmer italic phrase. | 3–10 words | “Testing is easy”<br>“Gold standard testing, on your schedule” |
| Support | State the reader benefit in ordinary language before adding process detail. | One or two short sentences | “Share with your doctor or connect directly to AI.”<br>“Find where you make an impact.” |
| Primary action | Verb plus concrete task; exploration links explain where they go. | 2–5 words | “Start testing”<br>“See how it works”<br>“See current openings” |
| Closing line | Challenge a common assumption, then answer it plainly. | Short headline and a brief reply | “Life is short?”<br>“Make your work meaningful.” |

**Words and phrasing to use:** understand; explained; your; whole; clearer; action; baseline; on your schedule; built with; real people

**Avoid:** disruptive solution; unlock your potential; revolutionary ecosystem; biohacking jargon; fear-driven urgency; miracle; guaranteed outcomes

**Rules:**

- Attach numbers to specific capabilities and disclose conditions near the offer.
- Use human benefit in the headline and technical explanation in the supporting copy.
- Prefer practical task labels over vague calls to discover more.
- Keep credentials and qualifications factual; avoid turning every paragraph into an authority claim.
- Use the closing line for a memorable reversal, not another summary of every feature.

## Do's and Don'ts

### Do

- Keep serif headings at weight 300 with normal tracking and genuine italic spans.
- Maintain the 80px display versus 64px section-heading distinction at desktop.
- Use #fef9ef for the page and #f5eee1 for tonal separation; make white specific to fields.
- Give paired actions 16px separation and keep their height at 50px.
- Use 32px gutters for the main explanatory and film rows.
- Include a fine terracotta visual explanation on warm paper, even when no interface can be shown.
- Reserve 24px corners and broad shadows for the pricing and footer objects.
- Keep the final editorial band connected to the inset footer by one oatmeal backing.

### Don't

- Do not use a heavy geometric sans for the principal headline; the light serif contrast is fundamental.
- Do not apply negative letter spacing to every heading just because large stat numerals use -2px.
- Do not recolor every card terracotta; the comparison highlight is the exceptional broad accent fill.
- Do not replace the pill actions with squared or tall rectangular controls.
- Do not make all card corners 24px; explanatory and film cards use 12px and accordion rows 6px.
- Do not place names over expert portraits; keep their credentials below, unlike quotation portraits.
- Do not give small process cards the footer's long shadow; they are flat oatmeal surfaces.
- Do not inflate a small chart into a full-screen dashboard or add saturated UI colors to the marketing canvas.

## Motion and responsive

### Motion

**Observed:**

- Primary and outline actions declare background-color, color and border-color transitions of 0.2s.
- Social icons declare color and transform transitions of 0.15s and translateY(-1px) on hover.
- Logo carousels declare a 48s linear infinite marquee.
- Portrait opening media and moving proof fields have visible pause controls; process chapters use sticky overlapping sheets.

**Transfer:**

- Keep a nearby small mono pause control for continuously moving proof fields.
- Use the stepped paper-sheet treatment only for the procedural narrative; ordinary marketing chapters remain spacious scrolling sections.
- Preserve the declared short color transitions on pill actions rather than adding dramatic motion.

**Unknown:**

- Exact cinematic playback, scroll triggers and motion paths are not specified.
- Reduced-motion behavior and the complete relation between declared easings and animated sections are not established.

### Responsive

**Observed:**

- The desktop layout uses both a text navigation group and a menu icon.
- The styles declare many width conditions, including 479px, 767px, 991px and 1440px; these do not establish a single global breakpoint system.
- The footer invitation has a declared clamp-based size formula.

**Transfer:**

- On narrow layouts, retain the portrait's face and move lower-right proof beneath the opening text if needed; do not shrink every element proportionally.
- Stack split feature chapters and reduce multi-column grids while preserving the roman/italic heading relationship.
- Keep the comparison's highlighted product distinction legible with horizontal scrolling or a labeled stacked comparison.
- Simplify overlapping process sheets to sequential chapters when the text and artwork cannot both remain readable.

**Unknown:**

- Mobile layouts, exact breakpoint behavior, narrow-screen type sizes and navigation expansion are not established; the collapse rules above are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
