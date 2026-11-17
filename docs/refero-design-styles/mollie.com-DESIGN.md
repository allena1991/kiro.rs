# Mollie — warm money in motion

## Overview

A spacious, approachable product style that makes complex infrastructure feel tangible and human. White and warm chalk canvases, espresso controls and small orange accents frame regular-weight grotesk typography, lived-in photography and sculptural product imagery. Large demonstrations and occasional luminous black stages punctuate an otherwise restrained, low-density marketing experience.

### Essentials

- Headlines behave like plain-spoken posters, not bold advertising: regular-weight Inter at 82px/1 with -2.4px tracking for the opening and 56px/1.1 with -0.02em tracking for major chapters.
- The opening separates the promise from the explanation: an approximately two-thirds-width, two-line headline sits left, a 341px support-and-action column sits right, and a near-full-width photographic stage begins beneath them at 436px.
- Controls feel like rounded espresso lozenges: main actions are 50px tall with 16px 24px padding and 140px radius; secondary actions use warm off-white with 142px radius, never a bright primary fill by default.
- Color belongs to objects and concentrated moments: most reading areas remain white or #f7f4f1; orange #e07122 marks short underlined links, while one black 16px-radius stage concentrates amber light and white text rather than spreading gradients throughout the page.
- Show the product as an object in someone's world: warm natural-light photographs, fanned or tilted physical artifacts, and floating 16px-radius glass notifications. Every new page needs a tactile product stage; when no physical object exists, use a polished interface panel with a few dimensional cards over contextual photography.
- Small labels temper the giant type with machine-like detail: IBM Plex Mono at 11px/1.3, weight 500, uppercase and 0.03em tracking; the opening proof label is 13px/1.3.
- A sideways continuation creates a distinctive final impression: tall 380×560px photographic and espresso-backed product tiles sit 24px apart, clip at the viewport edges and carry tiny bottom captions. Pair this device with an expansive conversion statement rather than ending abruptly after feature cards.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Espresso | `#3b281d` | `--color-action` | action, background | Default primary buttons and compact signup control. |
| Roasted brown | `#211006` | `--color-tile-brown` | surface | Tall closing product tiles behind isolated devices and interfaces. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnished orange | `#e07122` | `--color-link` | link, accent, action | Underlined exploration links and their chevrons. Solid action fills belong to the alternate conversion treatment. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline black | `#000000` | `--color-ink` | text, background | Default display text and concentrated black stages. |
| Soft black | `#111111` | `--color-text` | text | Card titles, questions and reading text. |
| Secondary black | `#666666` | `--color-secondary-text` | text | Visible black at 60% over white for technical labels and support lines; inverse labels use white at 60% on dark surfaces. |
| Mid gray | `#808080` | `--color-muted` | text | Secondary paragraphs, prices and captions. |
| Light gray | `#919191` | `--color-fineprint` | text | Subdued footer utility text. |
| Control edge | `#c4c4c4` | `--color-edge` | border | Thin visible outline around the locale selector. |
| Chalk hairline | `#e4e1df` | `--color-rule` | border | Visible result of rgba(71,71,71,0.1) separators over chalk; use the alpha recipe when the backing changes. |
| Chalk | `#f5f2f0` | `--color-band` | background, surface | Conversion panels; extensive backgrounds for comparison and capability-led pages. |
| Warm porcelain | `#f7f4f1` | `--color-warm-card` | surface | Default large product cards and sculptural product stages. |
| Pale shell | `#f7f4f2` | `--color-secondary-action` | action, surface | Secondary pill buttons. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, raised panels and inverse lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dedicated account-style product launches | Bright orange label | `#f56905` | `--color-product-label` | text, accent | Technical category eyebrows over dark and light product chapters. |
| dedicated product launches and capability showcases | Near-black umber | `#0f0b08` | `--color-deep-stage` | background, surface | Dark product chapters and floating-object showcase panels. |
| dedicated account-style product launches | Cocoa | `#2f231d` | `--color-hero-brown` | background | Enclosed dark launch hero behind white type, phone and floating panels. |

## Typography

- **Inter** — All display, heading, paragraph and control text; use the variable family for large headings. Open, unornamented grotesk; regular-weight headlines rely on scale and negative tracking rather than heavy strokes. Font stack: "Inter", Arial, sans-serif.
- **IBM Plex Mono** — Uppercase section identifiers, category labels and small proof lines. Compact mechanical lettering that contrasts with the broad, conversational sans. Font stack: "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 400 | 82px | 1 | -0.0293em, features "cv02", "cv03", "cv04", "cv08", "cv10", "cv12", "cv13", "dlig", "ss03" | Default left-aligned two-line opening promise. |
| heading | Inter | 400 | 56px | 1.1 | -0.02em, features "cv08", "cv12", "cv13", "ss03" | Major chapter headings, human-support section and conversion statements. |
| heading-split | Inter | 400 | 36px | 1.2 | -0.02em, features "cv08", "cv12", "cv13" | Narrow text column beside a large interface demonstration. |
| card-heading | Inter | 400 | 32px | 1.2 | -0.02em, features "cv12", "cv13" | Paired large product cards. |
| body | Inter | 400 | 18px | 1.3 | -0.02em | Chapter explanations and primary supporting paragraphs. |
| question | Inter | 500 | 18px | 1.1 | -0.022em | Commercial FAQ row labels. |
| body-small | Inter | 400 | 16px | 1.4 | -0.02em | Compact benefit rows and short descriptions. |
| hero-support | Inter | 400 | 16px | 1.3 | -0.025em | Compact support paragraph in the opening's right-hand column. |
| button | Inter | 500 | 16px | 1.2 | -0.0125em | Primary and secondary button labels. |
| explore-link | Inter | 600 | 16px | 1.2 | normal | Orange underlined exploration links. |
| tile-label | Inter | 500 | 16px | 1.2 | -0.03em | Capability index and glass callout titles. |
| selector | Inter | 500 | 15px | 1.3 | normal | Locale picker text. |
| navigation | Inter | 500 | 14px | 1.3 | -0.023em | Compact top-level navigation. |
| proof-label | IBM Plex Mono | 500 | 13px | 1.3 | normal, uppercase | Small opening proof statement above the main promise. |
| footer-link | Inter | 500 | 13px | 1.3 | -0.023em | Dense navigation columns in the footer. |
| eyebrow | IBM Plex Mono | 500 | 11px | 1.3 | 0.03em, uppercase | Section markers and footer group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| careers and culture pages | culture-display | Inter | 400 | 100px | 1.1 | -0.04em, features "cv08", "cv12", "cv13" | Centered recruitment manifesto framed by people photography. |
| dedicated account-style product launches | launch-display | Inter | 400 | 88px | 1.05 | -0.02em, features "cv08", "cv12", "cv13", "dlig" | White multiline promise in an enclosed dark hero. |
| pricing and broad solution pages | centered-display | Inter | 400 | 78px | 1 | -0.0308em, features "cv08", "cv10", "cv12", "cv13", "dlig", "ss03" | Centered comparison or capability-led opening. |
| pricing and broad solution pages | solution-heading | Inter | 400 | 64px | 1.1 | -0.02em, features "cv08", "cv12", "cv13", "ss03" | Broad solution chapter headings and alternate closing call. |
| dedicated account-style product launches | launch-heading | Inter | 400 | 62px | 1.1 | -0.02em, features "cv08", "cv12", "cv13" | Centered chapter headings. |
| careers and culture pages | culture-heading | Inter | 400 | 58px | 1.1 | -0.0276em, features "cv08", "cv12", "cv13" | Centered jobs, stories and FAQ headings. |
| pricing pages | plan-price | Inter | 400 | 44px | 1 | -0.02em | Plan amounts with much smaller period suffixes. |
| careers and culture pages | culture-stat | Inter | 600 | 39px | 1.1 | -0.0385em, features "case" | Four compact factual numbers beneath introductory prose. |
| pricing and broad solution pages | plan-heading | Inter | 400 | 34px | 1.1 | -0.0206em | Large comparison card titles. |
| dedicated account-style product launches | launch-support | Inter | 400 | 28px | 1.35 | -0.02em | Large translucent white paragraph beneath launch promise. |
| pricing and broad solution pages | plan-body | Inter | 400 | 16px | 1.4 | -0.006em | Muted comparison and capability-card descriptions. |
| dedicated account-style product launches | launch-eyebrow | IBM Plex Mono | 500 | 12px | 1.3 | 0.03em, uppercase | Orange category labels. |

**Notes:**

- Use Inter's variable build for display recipes and preserve each recipe's feature settings; ordinary paragraphs do not inherit the display alternates.
- The default hero is larger but more tightly led than section headings: 82px/1 versus 56px/1.1. Do not normalize these into one heading style.
- Use sentence case for promises and benefit headings; uppercase is confined to the small mono hierarchy.
- Keep reading paragraphs narrow enough to form two to four lines. The largest centered chapter titles usually occupy a 720px text measure.

## Layout

**Density:** Airy at the section level, compact within labels, controls and interface demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 7px | Default gap from a small section eyebrow to its heading. |
| 10px | Compact icon-and-text or benefit-row inner spacing. |
| 12px | Heading to paragraph or exploration-link spacing in compact groups. |
| 16px | Footer label groups and card-title spacing. |
| 20px | Product chapter heading to support copy. |
| 24px | Paired opening actions, comparison-card gaps and closing-tile gaps. |
| 32px | Comparison-card side padding and three-column solution-card gaps. |
| 36px | Two-column product-card gutters. |
| 40px | Inner side padding of wide stages and product cards. |
| 56px | Large footer row separation and launch stage heading-to-art spacing. |
| 80px | Footer top padding and separation beneath conversion band. |
| 90px | Top padding within warm sculptural product chapters. |
| 120px | Major white-section vertical padding. |

### Containers and grids

- **marketing-container**: max width 1400px · side padding 40px. Centered wrapper. At 1440px, its 20px outer margins plus inner padding place ordinary content 60px from the window edges, giving a 1320px working width.
- **heading-measure**: max width 720px. Centered major heading and short explanatory blocks.
- **paired-product-grid**: 2 columns · gap 36px. Two equal 642px product cards within the working width.
- **footer-grid**: 5 columns · gap 15px. Five visual columns; some columns contain two vertically stacked navigation groups.
- **solution-grid** (only for broad solution pages): 3 columns · gap 32px. Three equal capability or photographic audience cards, with a double-width item where the object needs more room.
- **culture-container** (only for careers and culture pages): max width 1200px · side padding 40px. 1120px working width for list rows and FAQ; long introductory prose narrows further to 824px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | product stages and media | 16px |
|  | primary buttons | 140px |
|  | secondary buttons | 142px |
|  | locale selector | 8px |
| pricing and broad solution pages | comparison cards | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| hairline lift | `rgba(0, 0, 0, 0.15) 0px 0px 1px 0px` | White comparison and capability cards; enough to separate surfaces without a visibly cast shadow. |
| button inner glint | `rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset` | Espresso primary actions. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

#### Warm product stage · level 1

**Use:** Large sculptural product panels.

**CSS:** `background: #f7f4f1; border-radius: 16px; overflow: hidden`

**Observed:** Used as both paired cards and a wide centered product chapter; no heavy outline.

**Transfer:** Give the main object room and let warm neutral backing connect it to adjacent photography.

#### Chalk band · level 0

**Use:** Conversion panel or long-form solution background.

**CSS:** `background: #f5f2f0`

**Observed:** The default closing conversion panel rounds its corners to 16px; comparison-led pages extend the same color across many chapters.

**Transfer:** Use the neutral change to group a decision, not as a new accent color.

#### Black light stage · level 1

**Use:** One concentrated technical or product-power moment.

**CSS:** `background: #000000; color: #ffffff; border-radius: 16px; overflow: hidden`

**Observed:** A large amber illuminated sculpture fills the middle, with centered text above the brightest area and a floating glass callout below.

**Transfer:** Use a simple luminous object or repeated dot construction if complex 3D artwork is unavailable.

#### Smoked glass · level 2

**Use:** Notifications over photography and callouts over the light sculpture.

**CSS:** `background: rgba(0, 0, 0, 0.3); border-radius: 16px; backdrop-filter: blur(20px); filter: saturate(1.3); box-shadow: rgba(255, 255, 255, 0.17) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.18) 0px -1px 0px 0px inset, rgba(255, 255, 255, 0.13) 1px 0px 0px 0px inset, rgba(255, 255, 255, 0.13) -1px 0px 0px 0px inset`

**Observed:** Small success notifications also use black at 20%; dark launch account overlays instead use white at 7%. Edges are internal glints rather than thick borders.

**Transfer:** Limit each panel to a short state or one compact explanatory pair; keep the scene visible through it.

#### Espresso tile · level 1

**Use:** Isolated product objects in the sideways continuation.

**CSS:** `background: #211006; border-radius: 16px; overflow: hidden`

#### White comparison card · level 1

**Only for:** pricing and broad solution pages

**Use:** Plans, grouped benefits and capability explanations.

**CSS:** `background: #ffffff; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.15) 0px 0px 1px 0px`

**Observed:** White cards sit on chalk with very faint edge definition.

**Transfer:** Keep the silhouette simple and let text and demonstration establish hierarchy.

#### Dark launch canvas · level 0

**Only for:** dedicated account-style product launches

**Use:** Large enclosed launch hero.

**CSS:** `background: #2f231d; color: #ffffff; border-radius: 16px; overflow: hidden`

**Observed:** Near-black umber chapters follow on #0f0b08; these are warm browns, not blue-gray technology backgrounds.

**Transfer:** Reserve the extended dark treatment for an object-led flagship launch rather than applying it to ordinary marketing sections.

## Components

### Navigation

**Use:** Persistent orientation and compact signup action.

**CSS:** `height: 54px; background: #ffffff; position: fixed; top: 0px; z-index: 10; max-width: 1400px`

**Text style:** `navigation` — Inter 500 · 14px/1.3 · tracking -0.023em

**Observed:** Logo left, five compact destination groups across the left half; contact, login and a small espresso signup pill align right. The page remains visible below the slim bar. Solution pages add a second 54px category-and-anchor row; culture navigation instead uses a 56px translucent bar with two destinations.

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #3b281d; color: #ffffff; border-radius: 140px; padding: 16px 24px; height: 50px; display: inline-flex; align-items: center; justify-content: center; box-shadow: rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset`

**Text style:** `button` — Inter 500 · 16px/1.2 · tracking -0.0125em

**Observed:** Text-only lozenge; content determines width. Orange is an alternate closing-action treatment on broad solution and comparison pages, not the default hero button.

**Transfer:** Use one primary action and a quieter conversation or discovery action beside it.

### Secondary button

**Use:** Conversation or secondary conversion action.

**CSS:** `background: #f7f4f2; color: #000000; border-radius: 142px; padding: 16px 24px; height: 50px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — Inter 500 · 16px/1.2 · tracking -0.0125em

**Observed:** Same visual mass as the main button but pale, without a prominent outline. Comparison cards may stretch both actions to full width and 54px height.

### Explore link

**Use:** Move from a benefit story to deeper detail.

**CSS:** `color: #e07122; text-decoration-line: underline; padding: 4px 0px; display: inline-flex; align-items: center; gap: 2px`

**Text style:** `explore-link` — Inter 600 · 16px/1.2

**Observed:** A small right-pointing orange chevron follows the underlined label; no filled container in the default treatment.

### Capability index tile

**Use:** Compact directory between opening proof and product chapters.

**CSS:** `background: #ffffff; padding: 22px; height: 68px; display: flex; align-items: center; gap: 10px`

**Text style:** `tile-label` — Inter 500 · 16px/1.2 · tracking -0.03em

**Observed:** Ten equal cells form a connected five-column, two-row matrix. Fine warm dividers join the cells; only the four outside corners receive the 16px radius. A small gray functional icon precedes each label.

**Transfer:** Use short capability nouns and a connected grid rather than ten separate floating cards.

### FAQ row

**Use:** Resolve specific purchase objections.

**CSS:** `min-height: 73px; padding: 20px 0px; display: flex; align-items: center; gap: 10px; border-top: 1px solid rgba(71, 71, 71, 0.1)`

**Text style:** `question` — Inter 500 · 18px/1.1 · tracking -0.022em

**Observed:** Question left; a thin plus occupies a 32px square at the far right. Rows span the full text container and have no separate card fills. The launch variant reverses to white on black. Culture rows are 72px with heavier question labels.

**Transfer:** Keep one practical question per row; preserve the open horizontal span.

### Glass callout

**Use:** Secondary proposition within a dark visual stage.

**CSS:** `background: rgba(0, 0, 0, 0.3); border-radius: 16px; padding: 22px; backdrop-filter: blur(20px); filter: saturate(1.3); display: flex; align-items: center`

**Text style:** `tile-label` — Inter 500 · 16px/1.2 · tracking -0.03em

**Observed:** A short title and smaller support line sit left; a delicate white line graphic occupies the right. The wide desktop panel measures 766×106px and floats in front of the sculpture; apply the Smoked glass edge glints.

**Transfer:** Use one complementary technical capability, not another large headline.

### Footer column

**Use:** Dense but ordered destination navigation.

**CSS:** `display: flex; flex-direction: column; gap: 6px; color: #000000`

**Text style:** `footer-link` — Inter 500 · 13px/1.3 · tracking -0.023em

**Observed:** Uppercase mono group labels sit above small sentence-case links. Multiple groups stack within five visual columns. Inverse footers use subdued light-gray links and brighter active destinations.

**States:** Declared: hover color rgba(0,0,0,0.6), no underline; inverse links hover to white.

**Transfer:** Keep the footer informational, with social links and locale selection on a separate lower row.

### Locale selector

**Use:** Location and language control in the footer.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #c4c4c4; border-radius: 8px; padding: 6px; height: 34px; width: 252px; display: flex; align-items: center; gap: 12px`

**Text style:** `selector` — Inter 500 · 15px/1.3

**Observed:** Globe at left, label in the middle, down caret right. The inverse footer uses a black fill and darker outline.

### Comparison card

**Only for:** pricing and broad solution pages

**Use:** Explain a plan or buying path.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 38px 32px 32px 32px; box-shadow: rgba(0, 0, 0, 0.15) 0px 0px 1px 0px; display: flex; flex-direction: column`

**Text style:** `plan-heading` — Inter 400 · 34px/1.1 · tracking -0.0206em

**Observed:** Title, muted paragraph, a vertical list of small icon-led benefits and a bottom-aligned full-width action. Two cards have equal height even when lists differ; dark action marks the self-service path and pale action the sales path.

**Transfer:** Compare two meaningful buying behaviors; do not imply that every card is the recommended plan.

## Imagery and graphics

### Human product photography

**Use:** Opening stage, customer stories and tall closing tiles.

**Observed:** Warm, believable business and personal moments: someone using a phone on a leather sofa, cycling outdoors, shop interiors and hands holding devices. Natural window or late-day light, brown leather, cream textiles, muted foliage and dark clothing create warmth without a colored wash. The opening image spans almost the whole viewport below the text and continues beyond the first fold; corners are rounded.

**Transfer:** Photograph the new product being used in a real setting, with one readable object or interaction as the focus. When custom photography is unavailable, choose a truthful contextual image and overlay a compact functional interface rather than a generic office-team stock photo.

### Sculptural product objects

**Use:** Warm product chapters and the sideways continuation.

**Observed:** Payment cards fan outward around a shared lower pivot; terminals form a staggered angled cluster; upright phones and broad dashboard panels overlap. Metallic black, ivory, copper-orange and iridescent finishes give otherwise plain rectangular objects material interest. Objects occupy more space than their short headings, over porcelain or espresso backing.

**Transfer:** Stage the new product's artifacts with this same hierarchy: one principal object, two to four supporting surfaces, shallow rotations and soft contact shadows. For software, a large interface panel plus two compact related cards is the minimum equivalent.

**Build:** Use an isolated product render or a rounded HTML interface as the central layer. Place supporting rectangular cards behind it with distinct rotations about a shared bottom-center origin, spanning roughly -25deg to 25deg as design guidance. Use black, cream and copper material fills, soft directional highlights and a restrained shadow; keep type and controls on the objects subordinate to the page headline.

### Amber data sculpture

**Use:** Signature concentrated light moment on the Black light stage.

**Observed:** Two vertically overlapping circular or bowl-like illuminated volumes fill the center of a black panel. Their edges burn amber, the lower rim approaches pale warm light, and repeated tiny binary markings wrap the forms. White headline and support text occupy the darker upper interior; glass floats across the brighter lower area.

**Transfer:** Keep the black-to-amber contrast and circular depth even for a nontechnical product. A pair of carefully shaded SVG discs with a clipped marking pattern is the minimum acceptable equivalent.

**Build:** In a 1320px-wide clipped black panel, center two overlapping SVG ellipses around half the panel width. Shade each from transparent black in the upper interior through translucent orange near the rim to translucent white at the lowest edge. Clip a dense 0/1 text pattern to each ellipse and reduce its opacity; use a blurred orange duplicate behind the sharp form. Offset the lower ellipse downward and behind the upper. Keep the headline above the light rim and the glass panel in front. Match the soft glow; exact gradient stops are not essential.

### Interface demonstrations

**Use:** Large visual proof after an outcome-led heading.

**Observed:** Readable dashboards use cream navigation rails, white tables and modest corner rounding; dark dashboards appear beside a white floating checkout panel. Framing ranges from a 1200×750px desktop panel to upright mobile devices. Accents inside these interfaces are functional and can be more varied than the surrounding marketing palette.

**Transfer:** Show one complete workflow or outcome at a time. Use actual product UI or a credible simplified mockup; do not promote tiny internal interface typography into the page's type system.

### Photographic story cards

**Use:** Customer proof and audience-specific pathways.

**Observed:** Wide customer images are arranged as a horizontally clipped carousel with the central card dominant. Audience cards use tall full-bleed images, white copy toward the bottom and a black fade for legibility. Captions and customer marks stay beneath images or in their darker regions; imagery is not reduced to circular avatars.

**Transfer:** Use project-relevant environments and outcomes. Keep the carousel or gallery's continuation visible at the edges and give each image a genuine story rather than arbitrary decorative color.

### Floating capability objects

**Only for:** broad solution pages

**Use:** Show breadth without a dense comparison table.

**Observed:** Small rounded square service symbols tilt and drift around a central white statement on a near-black warm stage. Color remains on the objects, not the background.

**Transfer:** Use the new product's real integration or capability symbols with varied rotations and depth; keep the headline's center clear.

**Build:** Arrange roughly 95px rounded-square SVG tiles around the perimeter of a 1320×700px dark panel. Vary rotations and opacity, clip some tiles at panel edges and leave a broad central text zone. Use authentic symbol colors only on tile faces; do not add a rainbow background.

### People constellation

**Only for:** careers and culture pages

**Use:** Humanize the opening manifesto and later culture gallery.

**Observed:** Five vertical candid workplace photos float around a centered headline: upper corners, lower sides and one partly visible at the bottom center. Their widths are about 230–245px with softly rounded corners. Later imagery forms a much larger three-column editorial gallery.

**Transfer:** Use candid people and workplace details with warm, mixed natural light. Maintain irregular placement around the central text rather than turning the opening into a uniform employee grid.

### Icons

**Observed:** Compact monochrome functional symbols accompany index cells and benefit lists, generally 18px or about 22px. The index uses rounded 1.5px linework; orange exploration chevrons are about 14×15px. Plus signs are thin and unboxed; partner symbols retain their own colors.

**Transfer:** Choose a coherent rounded outline set for functional concepts, using black or gray by default. Reserve orange for directional exploration links and keep multicolor marks inside product or integration demonstrations.

## Section recipes

How recurring sections are built.

### First screen: Promise above a lived-in stage

**Observed:** A slim Navigation sits over an expansive white introduction. The text begins 175px down: a tiny mono proof line above a two-line regular headline occupying roughly two thirds of the content width on the left. A 341px support column aligns near the headline's lower half on the right, with a short paragraph and a paired Primary button and Secondary button below, separated by 24px. The default display is 82px/1 with -2.4px tracking; its second line changes the benefit while preserving the opening phrase. Below a 54px breathing interval, a 1400px-wide rounded photographic stage starts at 436px, with warm lifestyle footage or imagery behind small dark glass success notices at its upper left. Within the first 900px, navigation, the complete promise, explanation, both actions and the upper portion of the main photographic object are visible; the photo's lower edge and subsequent proof sit below the fold.

**Transfer:** Keep the asymmetrical text hierarchy and wide human stage for a new marketing page. Use a truthful contextual photo plus one legible product overlay if no original footage exists. Comparison pages instead center a 78px promise above two buying-path cards on chalk; solution pages center the promise above a large interface demonstration; flagship launches use the dark enclosed object composition; culture pages use the people constellation.

**Avoid:** Do not put the default headline over a dark photo, center all the copy by habit, or replace the large lived-in stage with a small floating dashboard beside the headline.

**Text style:** `display` — Inter 400 · 82px/1 · tracking -0.0293em

### Eyebrow and outcome chapter

**Observed:** An 11px mono eyebrow sits 7px above a 56px centered heading, usually constrained to 720px. Explanations follow in 18px text; a short orange Explore link concludes the heading group when needed. Large white chapters use 120px vertical padding; warm object chapters begin with 90px.

**Transfer:** Introduce one outcome, then make the visual proof substantially larger than the copy. Use the launch or solution heading variants only within their corresponding page types.

**Text style:** `heading` — Inter 400 · 56px/1.1 · tracking -0.02em

### Paired product stages

**Observed:** Two Warm product stage cards, 642×546px with a 36px gutter, put compact category, 32px benefit title and Explore link at the top left. Large clustered objects fill and clip through the lower half. A wide matching stage can follow with a centered 56px heading and fan-like object arrangement above thin separated benefit rows.

**Transfer:** Pair two complementary ways the product helps, then devote a larger stage to the strongest outcome. Recompose objects instead of repeating the same screenshot at different sizes.

**Text style:** `card-heading` — Inter 400 · 32px/1.2 · tracking -0.02em

### Working interface beside compact explanation

**Observed:** A narrow left column uses heading-split and body recipes, with stacked capability labels separated by subtle rules. A much larger dashboard panel occupies the right and may extend beyond the content boundary. The text is aligned to the interface's upper edge rather than vertically centered as a generic split hero.

**Transfer:** Let one real workflow carry the visual argument. Use the smaller heading recipe to avoid competing with the interface.

**Text style:** `heading-split` — Inter 400 · 36px/1.2 · tracking -0.02em

### Technical light chapter

**Observed:** The Black light stage combines the Amber data sculpture, a centered white heading, a narrow explanation and orange Explore link. The Glass callout floats near the bottom over the sculpture. Outside margins remain white, making the contained dark scene feel deliberate rather than a site-wide theme switch.

**Transfer:** Use this signature device for the product's underlying power or most abstract advantage, replacing the proposition and markings without requiring a developer-focused subject.

**Text style:** `heading` — Inter 400 · 56px/1.1 · tracking -0.02em

### Human support proof

**Observed:** A small cluster of circular portraits precedes a centered heading and short gray paragraph. Three compact proof columns below combine a short benefit with a much smaller explanatory line; trust marks are subordinate to the promise.

**Transfer:** Use real service, reliability or human-help evidence appropriate to the new product rather than a generic testimonial wall.

**Text style:** `heading` — Inter 400 · 56px/1.1 · tracking -0.02em

### Conversion band and sideways continuation

**Observed:** A Chalk band with 16px corners uses 81px vertical and 40px side padding. Its wide left side carries a two-line 56px statement and Primary button plus Explore link; a narrower right column presents a brief reassurance and underlined pricing detail. After 80px of separation, the 560px-tall sideways tile strip mixes photography, isolated devices on Espresso tile backing and interface fragments with small bottom captions. Tiles are 380px wide, 24px apart and visibly continue beyond both edges.

**Transfer:** Use the conversion band to resolve the next decision and the strip to reinforce the product's tangible range. Preserve the sideways continuation device somewhere in the page without treating this exact section order as fixed.

**Text style:** `heading` — Inter 400 · 56px/1.1 · tracking -0.02em

### FAQ and directory ending

**Observed:** Commercial FAQs are full-width 73px rows with thin rules, left labels and right plus signs. The default footer is white with five visual columns, mono group names, 13px links, social row, locale selector and a very subdued legal tail. The dark solution ending keeps both conversion and footer black; the launch FAQ is black but its footer returns to white.

**Transfer:** Choose the ending theme deliberately rather than automatically making every footer dark. Include the locale and utility layer when the new product actually needs it.

**Text style:** `question` — Inter 500 · 18px/1.1 · tracking -0.022em

### Buying-path comparison and rate ledger

**Only for:** pricing pages

**Observed:** A centered mono label and 78px headline introduce two Comparison cards on a chalk field. A full-width third pathway can sit beneath. Three-column plan comparison uses 44px amounts and compact period suffixes; beneath it, a white ledger aligns symbols and names left with muted rates right. Standard ledger rows are 80px with 24px padding, while detailed rows expand into sublines separated by 8px gaps. FAQ and a wide white closing call precede the regular footer.

**Transfer:** Start with buying choices, then provide a scan-friendly detailed ledger and objection handling. Keep explanatory subdivisions aligned across rows; do not style every rate as a standalone card.

**Text style:** `centered-display` — Inter 400 · 78px/1 · tracking -0.0308em

### Dark object-led launch

**Only for:** dedicated account-style product launches

**Observed:** A 1360×866px Cocoa panel sits inside white margins beneath Navigation. Three-line 88px white promise and 28px translucent support occupy the left; an upright 325×677px phone dominates the center-right, with floating account panels farther right. Orange mono category label, a white pill action and tiny terms sit below the promise. Subsequent chapters alternate centered white introductions, near-black product systems and a broad dashboard demonstration. A narrow checklist-based offer closes the product argument before a dark manifesto interlude, black FAQ and white footer.

**Transfer:** Use this variant for a flagship object with a convincing standalone interface. Preserve the contrast between warm brown opening, near-black technical chapters and clean white proof; do not import this entire dark sequence into an ordinary landing page.

**Text style:** `launch-display` — Inter 400 · 88px/1.05 · tracking -0.02em

### Capability mosaic and photographic pathways

**Only for:** broad solution pages

**Observed:** A centered 64px heading introduces a three-column mosaic of white 24px-radius cards on chalk, each with small mono category, benefit title, muted paragraph and substantial demonstration below. One card may span two columns. Separate tall photographic cards use bottom-aligned white text and dark fades for audience pathways. A later story carousel expands one image while neighboring cards remain narrow.

**Transfer:** Use a mosaic to explain distinct capabilities, then photographs to distinguish use contexts; keep the two card systems visually distinct.

**Text style:** `solution-heading` — Inter 400 · 64px/1.1 · tracking -0.02em

### Culture narrative and small ending

**Only for:** careers and culture pages

**Observed:** A 100px centered manifesto sits among five floating candid portraits, followed by a 1120px-wide opportunity list, two-column story teasers, narrow introductory prose, four 39px semibold factual numbers and a small bullet-like value matrix. Larger editorial photography leads toward a centered 58px FAQ heading and five 72px rows. The ending is notably minimal: a small logo left, pale utility links and social symbols right, with no commercial five-column directory or conversion band.

**Transfer:** For a culture-oriented page, make people and factual details carry proof. Retain the larger opening scale and minimal ending only in this page family.

**Text style:** `culture-display` — Inter 400 · 100px/1.1 · tracking -0.04em

## Page flow

**Storyline:** Promise → tangible product experience → breadth and capability chapters → customer or operational proof → reassurance and decision → visually memorable continuation → useful navigation.

### Broad marketing landing page

1. **Promise** — Asymmetrical headline and explanation above a warm photographic stage with floating status notices.
2. **Breadth** — Small customer marks and a connected capability index.
3. **Product demonstration** — Paired object stages, a large warm centerpiece and a split interface chapter.
4. **Proof** — Photographic customer carousel, contained amber-on-black technical chapter and human-support reassurance.
5. **Closing call** — Wide chalk conversion band with a secondary reassurance column.
6. **Continuation and navigation** — Tall sideways product-and-photo strip, then a white five-column directory with locale and utilities.

**Transfer:** Use concrete demonstrations to turn a broad promise into a few memorable product experiences, then end with both a decision and visual momentum.

### Comparison and pricing decision page

1. **Buying choice** — Centered promise above two equal white comparison cards on chalk, plus a broad specialist path.
2. **Detailed comparison** — Compact categories, three plans with restrained price numerals, supporting hardware or service rows.
3. **Transparency** — Long white ledger with left labels, right-aligned rates and nested explanatory rows.
4. **Objection handling** — Additional fees and full-width FAQ rows.
5. **Closing call** — White heading-and-actions band, breadcrumb and white directory footer.

**Transfer:** Keep the top decision simple while allowing detailed terms to be genuinely useful farther down; do not force marketing-image density into a ledger.

### Flagship product launch

1. **Promise and object** — Warm brown enclosed hero with white text, oversized phone and floating glass summaries.
2. **System demonstration** — Centered introduction followed by connected product panels, card objects and dark capability chapters.
3. **Practical proof** — Photographic usage cards, complete dashboard and integration strips.
4. **Offer** — Narrow checklist within a broad chalk panel and compact signup action.
5. **Belief and objections** — Dark manifesto artwork interlude then inverse FAQ.
6. **Navigation** — Return to the white directory footer.

**Transfer:** Use alternating object, system and real-world proof to make a new standalone product credible; retain a distinct launch theme without rewriting core controls.

### Broad solution and capability page

1. **Promise** — Centered 78px headline, support and paired actions above a dashboard with overlapping checkout.
2. **Social proof and breadth** — Trust marks and customer logos, followed by floating symbols on a dark stage.
3. **Capability chapters** — Tabbed demonstration, white capability mosaic on chalk and equal buying-path cards.
4. **Audience and customer proof** — Tall photographic pathways, split benefits-and-story panel and expanded story carousel.
5. **Closing decision** — Centered contact call, editorial story cards and a compact capability directory.
6. **Final call and navigation** — Black conversion band with orange action, breadcrumb and matching dark directory footer.

**Transfer:** Use larger centered chapter headings and a chalk field to unify many capabilities; keep the dark footer as a scoped ending rather than a default.

### Careers or culture narrative

1. **Mission invitation** — Oversized centered statement surrounded by candid people photos and one small orange link.
2. **Opportunity** — Wide list rows with compact location and discipline pills.
3. **Culture proof** — Story teasers, narrow prose, four compact statistics and a small values matrix.
4. **Atmosphere** — Large three-column editorial photography gallery.
5. **Objection handling and ending** — Centered FAQ followed by a spare logo-and-utility footer.

**Transfer:** Replace commercial buying decisions with opportunities and human proof; do not carry over pricing calls or the dense commercial directory.

## Writing

Direct, capable and warm, with a builder's impatience for complexity. Benefits sound useful rather than grandiose, and confidence is supported by concrete mechanisms and plain terms.

**Do not copy:** Do not reuse Mollie's name, logo, product artwork, customer marks, quotes, trust ratings, merchant counts, financial claims, cashback percentages, pricing or regulatory statements. Source examples demonstrate structure and tone only; all new claims need the new product's own support. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your business. Use we for the team doing the difficult work behind the scenes; name the product only when clarity requires it.
- **Rhythm:** Headlines are usually short clauses or balanced two-part promises. Support uses one or two practical sentences, often with a three-item list; action labels are terse verbs. Longer technical explanations remain conversational and avoid hype punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name a broad everyday outcome, or contrast the first step with later scale. | 5–12 words | “The platform for managing your money”<br>“Flexible online payments, from first sale to full scale” |
| Section headline | Use a direct imperative or a contrast between the task and the burden removed. | 5–11 words | “Run your finances, not just your reports”<br>“Made by builders, not bankers” |
| Supporting line | Connect a real frustration to an operational mechanism and human benefit. | 15–35 words | “Problems cost you money. We handle yours with people who know your market and speak your language.” |
| Primary action | Verb plus the next concrete step, with a quieter human conversation alternative. | 2–4 words | “Get started now”<br>“Contact sales” |
| Reassurance | State the limits or absence of friction in short parallel phrases. | 6–15 words | “No minimum costs, no lock-in contracts.” |
| Culture invitation | Invite participation in a specific problem worth solving. | 5–9 words | “Help to eliminate financial bureaucracy” |

**Words and phrasing to use:** built; ready; control; one place; from first step to full scale; your business; without the complexity; get started; talk to us; save time

**Avoid:** revolutionary ecosystem; unlock limitless possibilities; cutting-edge synergy; disruptive excellence; exclamation-heavy urgency; unqualified best-in-class

**Rules:**

- Lead with the result, then explain the mechanism in the support line.
- Use concrete verbs and ordinary nouns in preference to abstract industry language.
- Let an honest constraint, term or practical reassurance sit near conversion actions.
- Use balanced contrasts sparingly to make large headlines memorable.
- Give each chapter one promise; leave detailed feature inventories to compact lists or ledgers.

## Do's and Don'ts

### Do

- Keep default display and major chapter headings at weight 400, with their tightly specified tracking.
- Use 1400px wrappers with 40px inner side padding to preserve the broad desktop stage.
- Separate large chapter copy from imagery with genuine breathing room, using 90px or 120px section padding.
- Use 16px corners for tactile product stages and 24px corners for scoped comparison cards.
- Keep orange exploration text at 16px weight 600 with an underline and tiny chevron.
- Combine lived-in warm photography with a legible product object or glass notification.
- Preserve one concentrated amber-on-black visual stage and the horizontally continuing tall-tile device.
- Align comparison-card actions along the bottom, even when benefit lists differ in length.

### Don't

- Do not make the ordinary hero button orange or blue; espresso is the default primary action.
- Do not replace the regular 82px headline with a heavy 64px startup-style slogan.
- Do not spread warm gradients across the white page; concentrate light inside its black stage.
- Do not turn the connected 68px-high capability index into a grid of widely separated shadow cards.
- Do not add deep drop shadows to white comparison cards; the 1px hairline lift is sufficient.
- Do not use blue-black as the launch hero backing; its warmth comes from cocoa and near-black umber.
- Do not make every picture a small thumbnail beside long copy; the product scenes should dominate their chapters.
- Do not automatically append a dark directory footer to culture content; that variant ends with a spare utility row.

## Motion and responsive

### Motion

**Observed:**

- Link color transitions are declared at 0.2s cubic-bezier(0.44,0,0.56,1).
- The opening benefit line changes while its introductory phrase remains stable; the closing product strip is arranged as a horizontally translated ticker.
- Customer proof uses previous and next controls; object arrangements include rotated and overlapping layers.

**Transfer:**

- Keep the changing hero benefit to a stable line box so the adjacent support and buttons do not move.
- Use horizontal continuation for product breadth rather than adding vertical stacks of duplicate tiles.
- Keep color transitions subtle; the tactile objects and luminous stage carry the expressive emphasis.

**Unknown:**

- Ticker speed, hero rotation duration, object animation timing and scroll choreography are not specified.
- Button focus-visible and active designs are not established.

### Responsive

**Observed:**

- Layout breakpoint declarations cluster around 810px and 1200px, with further large-screen adjustments near 1400px and 1440px.

**Transfer:**

- On narrow screens, stack the promise before support and actions, then preserve a wide photographic stage with a purposeful subject position.
- Reduce object count and overlapping offsets before shrinking all interface text into illegibility.
- Collapse paired and three-column chapters into a readable sequence while retaining their warm stage backings.
- Keep a clipped sideways continuation for the tall tiles; reduce the number visible rather than compressing each object into a thumbnail.

**Unknown:**

- Exact small-screen typography, padding, menu behavior and breakpoint-specific rearrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
