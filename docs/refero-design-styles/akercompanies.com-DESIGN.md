# Aker — landscapes and ledgers

## Overview

An expansive editorial style that pairs the scale of landscape photography with the order of an institutional ledger. Mostly white layouts, black sans-serif typography and fine rules are interrupted by ocean blue, forest green and earthy tones. Human serif details, candid outdoor photographs and oversized numbers soften the businesslike structure. It suits considered, place-aware products and service brands with substantial stories and proof rather than dense feature lists.

### Essentials

- The opening is a landscape with a masthead, not a centered sales pitch: a full-viewport photograph or film, a 432×111px wordmark at the lower left, a 288px-wide serif introduction near mid-height and a 480px-wide destination cluster at the lower right.
- Headings feel light and compressed vertically: the default section heading is Proxima Nova 62px/0.9, weight 400, tracking -0.03em; capability titles use 48px/1, weight 300, tracking -0.02em.
- The page reads like a spacious ledger: 22px outer gutters, 1px separators, narrow index columns and large paired fields; proof numbers reach 174px/1 at weight 300 with -0.04em tracking.
- Actions are small translucent capsules rather than loud blocks: conversion buttons are 244×51px with 160px radii, 5px backdrop blur and thin right arrows; inline exploration links split the label pill from a circular arrow.
- Color arrives in substantial, bounded chapters: the default is predominantly white, with a charcoal proof chapter and an ocean-blue conversion panel; sage, clay and warm taupe belong to editorial or people-focused variants rather than a rainbow of feature cards.
- Photography carries atmosphere and proof together: sunlit architecture, water, forests and candid people are framed as half-width landscapes, tall editorial images or full-bleed scenes, with restrained 8px corners and no floating-device mockups. Use real environments of use when a product has no physical object.
- Monumental identity and staggered proof are signature devices: repeat an oversized project wordmark in the ending and use an offset two-column numbers ledger somewhere in the narrative. A typeset project name and verified outcome figures provide the fallback without custom identity artwork.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep ocean | `#002934` | `--color-ocean` | background, surface, link | Default solid conversion panel and dark blue editorial chapters; small exploration text. |
| Forest green | `#193f32` | `--color-forest` | text, background, surface | People contact panel and sage editorial typography. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background | Primary text, identity artwork and compact navigation backing. |
| Charcoal chapter | `#1c1c1c` | `--color-charcoal` | background, text | Dark explanatory chapter, with white typography. |
| Soft ink | `#333333` | `--color-soft-ink` | text | Visible result of black at 80% opacity on white, used for monumental proof numbers. |
| Secondary gray | `#666666` | `--color-muted` | text | Secondary explanatory text; also the visible result of black at 60% on white. |
| Grid rule | `#bfbfbf` | `--color-rule` | border | Editorial grid dividers and department separators. |
| Pale edge | `#e5e4e4` | `--color-edge` | border, surface, text | Directory row separators and neutral conversion panels in the editorial variant. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Default page canvas and reversed text on photography or dark chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruiting contact panels | Inset forest | `#18372c` | `--color-email-green` | surface | Darker inset email strip within the forest contact panel. |
| brand-story and people narratives | Burnt clay | `#b75928` | `--color-clay` | background, surface, accent | Mission band, editorial indices and culture conversion panel. |
| community feeds | Dusty rose | `#d9c6c6` | `--color-rose` | surface | Social identity tile variation. |
| brand-story and community narratives | Sage field | `#c8cfba` | `--color-sage` | background, surface | Extended commitment chapter continuing through its footer; also a social account tile. |
| community feeds | Blue gray | `#ccdce3` | `--color-blue-gray` | surface | Social identity tile variation. |
| recruiting graphics | Tag charcoal | `#262626` | `--color-pill-dark` | surface | Large serif category pills on charcoal. |
| portfolio openings | Olive stone | `#3f3a32` | `--color-olive-stone` | background | Grained backdrop for a split-title portfolio opening. |
| recruiting and community narratives | Warm taupe | `#cfc3ba` | `--color-taupe` | background, surface | People collage opening and social identity tiles. |
| recruiting pages | Warm cream | `#f5f3ed` | `--color-cream` | surface, text | Recruiting conversion card and its reversed talent-panel heading. |

## Typography

- **Proxima Nova** — All primary headings, paragraph text, labels and actions. Open, rounded humanist-geometric sans with a light editorial display cut and unobtrusive small text. If unavailable, use **Montserrat**. Use weights 300–600; preserve light display weights and tight tracking, and check line wraps against the wider substitute. Font stack: "Proxima Nova", "Montserrat", Arial, sans-serif.
- **Lora** — Small opening introduction; selected editorial phrases, role titles and contact addresses. Warm, bracketed serif with expressive italic forms; a human counterpoint rather than the main display voice. Font stack: "Lora", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat-number | Proxima Nova | 300 | 174px | 1 | -0.04em | Dominant figures in a staggered proof ledger; black at 80% on white. |
| section-heading | Proxima Nova | 400 | 62px | 0.9 | -0.03em | Default section leads and large conversion headings. |
| capability-title | Proxima Nova | 300 | 48px | 1 | -0.02em | Titles in numbered capability rows. |
| statement | Proxima Nova | 400 | 36px | 1 | -0.02em | Short positioning statement following the opening. |
| accordion-title | Proxima Nova | 400 | 24px | 1 | -0.02em | Expandable explanatory topic labels on charcoal. |
| stat-caption | Proxima Nova | 500 | 18px | 1.15 | normal | Short bottom-aligned explanations in the proof ledger; black at 60% on white. |
| body | Proxima Nova | 400 | 16px | 1.25 | -0.01em | Default support paragraphs and accordion descriptions. |
| card-label | Proxima Nova | 500 | 16px | 1.3 | normal | Labels above conversion headings. |
| hero-caption | Lora | 400 | 15.2px | 1.35 | 0.0105em | Two-line opening positioning sentence; the opening identity itself is wordmark artwork. |
| hero-action | Proxima Nova | 400 | 15.2px | 1.5 | normal | Translucent utility pills within the opening destination cluster. |
| footer-link | Proxima Nova | 400 | 14.4px | 1.5 | normal | Primary and secondary navigation within the ending. |
| conversion-action | Proxima Nova | 600 | 14px | 1.15 | -0.01em | Large capsule action text. |
| inline-action | Proxima Nova | 600 | 13.6px | 1.5 | normal | Small exploration links and compact profile actions. |
| eyebrow | Proxima Nova | 500 | 12px | 1 | -0.02em | Small sentence-case section identifiers, typically at half text opacity. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| portfolio and abstract editorial openings | split-title | Proxima Nova | 500 | 128px | 1.1 | normal, uppercase | Words separated across a portfolio opening or a lower-left abstract title. |
| people and brand-story pages | page-title | Proxima Nova | 500 | 120px | 0.75 | 0.04em, uppercase | Bottom-left people or story opening title; also staggered verbs across sage chapters. |
| portfolio chapters | editorial-title | Proxima Nova | 300 | 62px | 0.95 | -0.025em | Lighter chapter titles and introductory statements. |
| portfolio chapters | editorial-subtitle | Proxima Nova | 300 | 48px | 1.1 | -0.02em | Multiline editorial chapter proposition. |
| long-form editorial pages | editorial-quote | Proxima Nova | 300 | 48px | 1 | -0.025em | Large offset statements between photographic spreads. |
| brand-story mission bands | serif-emphasis | Lora | 400 italic | 48px | 1.05 | -0.02em | Selected verbs inside a serif mission statement. |
| recruiting graphics | category-pill | Lora | 400 | 30.7px | 1.15 | normal | Oversized category words scattered at the foot of a dark panel. |
| recruiting contact panels | email-address | Lora | 400 | 30px | 1.2 | -0.03em | Large email copy action in an inset green strip. |
| brand-story pages | numbered-observation | Proxima Nova | 400 | 26px | 1.15 | -0.04em | Substantial statements in ruled numbered rows. |
| community feeds | social-identity | Lora | 400 | 24px | 1.2 | -0.02em | Bottom-left account names inside pastel feed tiles. |
| team directories | person-name | Proxima Nova | 400 | 18px | 1.4 | normal | Names within compact department directories. |
| team directories | person-role | Lora | 400 italic | 18px | 1.4 | normal | Roles in a separate muted column beside names. |
| long-form editorial pages | editorial-body | Proxima Nova | 400 | 16px | 1.3 | normal | Narrow secondary column in photographic chapters. |

**Notes:**

- Default headings are sentence case. Uppercase is reserved for large editorial page titles and identity artwork, not applied to every label.
- Keep weight and tracking together: regular 62px headings are tighter than 48px capability titles, while 174px figures use -0.04em. The unusually positive tracking of editorial page titles is a separate treatment.
- The main opening and footer identities are SVG letterforms, 432×111px at desktop; use equivalent project-name artwork rather than treating the opening as a conventional centered headline.
- The root sizing expression is calc(0.812695rem + 0.208117vw); rem-based dimensions follow that shared scaling. Preserve the desktop relationships rather than independently resizing every role.

## Layout

**Density:** Airy at the section scale, compact within labels and links; large image fields and proof cells create pauses without enlarging body text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small grid-section inset and footer heading separation. |
| 12px | Compact directory row padding and inline icon separation. |
| 12.8px | Opening destination-cluster gaps. |
| 16px | Conversion label-to-heading gap and narrow editorial grid gutters. |
| 20px | Capability content stack gaps. |
| 21px | Eyebrow-to-section-heading gap. |
| 22px | Global outer gutters and paired conversion-card gap; declared normal spacer. |
| 32px | Conversion-card padding and reusable content-grid gap. |
| 37px | Declared section-space token for standard chapter top and bottom padding. |
| 48px | Vertical padding surrounding conversion-card pairs and department-group separation. |
| 80px | Portfolio chapter transition padding. |
| 120px | Long-form statement top inset. |
| 140px | Brand-story numbered-list top and bottom breathing room. |

### Containers and grids

- **edge container**: max width 1440px · side padding 22px. At desktop, content occupies 1396px within nearly edge-to-edge page composition; do not shrink everything to a conventional centered narrow site shell.
- **paired fields**: 2 columns · gap 22px. Equal 687px fields for conversion cards, capability content and photographs, and proof columns.
- **capability row**: 3 columns · gap 0px. A 72px index rail, a flexible content column and a 687px image field; content paragraphs stop at 411px.
- **editorial thirds**: 3 columns · gap 16px. Near-equal thirds separated by 1px vertical rules; headline may span two columns while a 320px support column sits low in the middle.
- **quote measure**: max width 672px · side padding 24px. Offset a large quote to the second third of the page; keep substantial space on its left.
- **hero destination cluster**: max width 480px · 2 columns · gap 12.8px. Anchor the destination cluster to the lower right, with a wide top card and two smaller lower destinations.
- **social field** (only for community feeds): 4 columns · gap 12.8px. Four staggered columns of 329px squares, tall photographs, identity tiles and caption cells separated by hairlines.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards and images | 8px |
|  | conversion capsules | 160px |
|  | utility capsules | 80px |
|  | accordion control | 50% |
| recruiting contact panels | contact panel | 10px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing page field.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat, unshadowed field. Content is organized by fine rules, not raised white cards.

**Transfer:** Let whitespace and image scale establish hierarchy.

#### Charcoal chapter · level 0

**Use:** A substantial explanatory contrast chapter.

**CSS:** `background: #1c1c1c; color: #ffffff; padding: 37px 22px`

**Observed:** Thin white rules at 12% opacity separate topics; the photography remains colorful.

**Transfer:** Use for decision criteria or an explanation that benefits from an image-linked accordion.

#### Ocean panel · level 1

**Use:** Default solid conversion panel.

**CSS:** `background: #002934; color: #ffffff; border-radius: 8px; padding: 32px; box-shadow: none`

**Observed:** Flat saturated dark blue with a small label, large heading and a generous empty middle.

**Transfer:** Pair with a photographic panel rather than adding bevels or gradients.

#### Hero glass · level 1

**Use:** Dark destination cards over the opening scene.

**CSS:** `background: rgba(0, 0, 0, 0.6); border-radius: 8px; backdrop-filter: blur(20px)`

**Observed:** Near-black translucent backing gathers image and text; the scene remains perceptible through it.

**Transfer:** Keep the glass confined to the opening navigation cluster.

#### Photo legibility veil · level 1

**Use:** Text-bearing photographic conversion cards.

**CSS:** `background: linear-gradient(rgba(6, 11, 17, 0.5), rgba(4, 4, 4, 0) 89%); border-radius: 8px`

**Observed:** A dark-to-transparent veil protects the heading near the upper edge without flattening the whole photograph.

**Transfer:** Layer above an image and below text.

#### Sage editorial field · level 0

**Only for:** brand-story commitment chapters

**Use:** An extended alternate canvas, including the closing footer.

**CSS:** `background: #c8cfba; color: #193f32`

**Observed:** Forest-colored typography and rules at 20% opacity share the soft green backing; no separate raised cards.

**Transfer:** Let one sustained tone connect a narrative instead of recoloring each subsection.

#### Clay mission band · level 0

**Only for:** brand-story mission bands

**Use:** Warm serif statement opposite a tall nature photograph.

**CSS:** `background: #b75928; color: #ffffff; padding: 16px`

**Observed:** Two-thirds text field and one-third image field, separated by a pale vertical rule.

**Transfer:** Make the mission human with a short serif proposition and tangible environmental imagery.

#### Grained stone · level 0

**Only for:** portfolio openings

**Use:** Neutral backing around an isolated image and split title.

**CSS:** `background: #3f3a32`

**Observed:** Very fine noise at 0.045 opacity adds a dry, mineral texture.

**Transfer:** Use an SVG turbulence layer over the solid field; keep the grain barely perceptible.

#### Forest contact panel · level 1

**Only for:** recruiting contact panels

**Use:** Large direct-contact close.

**CSS:** `background: #193f32; border-radius: 10px; padding: 32px 24px 28px`

**Observed:** Cream heading, small instructions and an inset darker email strip.

**Transfer:** Use as a direct correspondence alternative to a form.

## Components

### Navigation badge

**Use:** Persistent access to navigation without a full-width header.

**CSS:** `position: fixed; right: 22px; top: 18.4px; width: 118px; height: 31px; background: #000000; color: #ffffff; border-radius: 8px; z-index: 98`

**Observed:** A small project wordmark sits beside two horizontal menu lines. It remains at the upper right on both white and photographic backgrounds; expanded navigation uses compact white links and fine rules.

**Transfer:** Fit the new project identity into the badge while preserving its compact silhouette.

### Hero destination tile

**Use:** Contextual exploration within the opening scene.

**CSS:** `background: rgba(0, 0, 0, 0.6); border-radius: 8px; backdrop-filter: blur(20px); width: 480px; height: 192px; overflow: hidden`

**Text style:** `body` — Proxima Nova 400 · 16px/1.25 · tracking -0.01em

**Observed:** The wide tile pairs a photograph on the left with a short topic and proposition on the right; smaller destinations below use an image or identity symbol and a label.

**Transfer:** Choose a few meaningful entry points, not an inventory of every navigation link.

### Hero utility pill

**Use:** Short contact or people link inside the opening destination cluster.

**CSS:** `background: rgba(255, 255, 255, 0.2); color: #ffffff; border-radius: 80px; backdrop-filter: blur(5px); width: 114px; height: 37px; padding: 12.8px; display: flex; align-items: center; justify-content: center`

**Text style:** `hero-action` — Proxima Nova 400 · 15.2px/1.5

**Observed:** Two small pills share a row above the lower destination tile.

**States:** Declared: hover background-color rgba(255, 255, 255, 0.35); focus-visible unspecified; active outline 0px.

### Explore link

**Use:** Low-emphasis continuation below a capability paragraph.

**CSS:** `display: flex; align-items: center; height: 26px; color: #002934; border-radius: 9999px`

**Text style:** `inline-action` — Proxima Nova 600 · 13.6px/1.5

**Observed:** A pale-gray 70×26px text capsule is followed by a separate 26px circular arrow. The text wrapper has 12px horizontal padding; the full assembly is about 102px wide.

**Transfer:** Keep the arrow separate rather than turning the whole link into a large filled button.

### Capability row

**Use:** Explain a capability alongside concrete visual proof.

**CSS:** `display: grid; grid-template-columns: 72px minmax(0px, 1fr) 687px; padding: 10px 0; border-top: 1px solid rgba(0, 0, 0, 0.2)`

**Text style:** `capability-title` — Proxima Nova 300 · 48px/1 · tracking -0.02em

**Observed:** Two-digit index in the first rail; title, a narrow paragraph and Explore link in the middle; 687×476px photograph at right. Each desktop row occupies about 497px.

**Transfer:** Use active one- or two-word capability titles and let each photograph explain a different aspect.

### Accordion control

**Use:** Reveal a topic and coordinate the adjacent photograph.

**CSS:** `width: 42px; height: 42px; border: 1px solid rgba(255, 255, 255, 0.12); border-radius: 50%; color: #ffffff; position: relative`

**Text style:** `accordion-title` — Proxima Nova 400 · 24px/1 · tracking -0.02em

**Observed:** The circular plus/minus precedes the text by 25px. Closed topic headers are about 74px high; an open row expands to about 200px and includes a narrow supporting paragraph. One topic is visibly expanded.

**Transfer:** Preserve a single clear image/topic relationship rather than displaying unrelated miniature icons.

### Stat cell

**Use:** Large-scale quantified proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; width: 687px; height: 464px; padding: 23px 0 21px; border-bottom: 1px solid rgba(0, 0, 0, 0.2)`

**Text style:** `stat-number` — Proxima Nova 300 · 174px/1 · tracking -0.04em

**Observed:** The enormous number sits near the top; its short muted explanation sits at the bottom. Adjacent columns are offset vertically, and a central hairline creates a ledger rather than a regular tile grid.

**Transfer:** Use verified figures with short units and enough space for the full value without shrinking it.

### Conversion card

**Use:** A strong audience-specific next step.

**CSS:** `background: #002934; color: #ffffff; border-radius: 8px; padding: 32px; width: 687px; height: 640px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `section-heading` — Proxima Nova 400 · 62px/0.9 · tracking -0.03em

**Observed:** Label and headline occupy the upper left. The lower left holds a Conversion button; a 144×149px identity symbol balances the lower right. The adjacent variant is a full-cover candid photograph. Editorial variants use pale gray with black text; recruiting uses cream; culture uses clay.

**Transfer:** Keep the solid-panel-plus-photo contrast and use the new project's own simple symbol.

### Conversion button

**Use:** Primary action within a conversion panel.

**CSS:** `display: flex; justify-content: space-between; align-items: center; width: 244px; height: 51px; padding: 0 20px 0 24px; border-radius: 160px; background: rgba(212, 211, 211, 0.15); backdrop-filter: blur(5px); color: #ffffff`

**Text style:** `conversion-action` — Proxima Nova 600 · 14px/1.15 · tracking -0.01em

**Observed:** Text sits at the left and a thin 20×18px right arrow at the right. The photograph-backed version uses black at 35% opacity. Editorial pale-panel buttons are 192×56px, use 16px semibold text and a subtle gray horizontal gradient; recruiting uses a pale cream capsule.

**States:** Declared: hover background-color rgba(212, 211, 211, 0.3); focus-visible unspecified; active outline 0px. The dark photo variant increases black backing to 50%; editorial gradient variants use brightness(95%).

### Masthead footer

**Use:** The final identity-led ending after the closing action.

**CSS:** `border-top: 1px solid rgba(0, 0, 0, 0.1); padding-top: 8px; color: #1c1c1c`

**Text style:** `footer-link` — Proxima Nova 400 · 14.4px/1.5

**Observed:** The navigation occupies the right 60% while the left stays open. A 432×111px project wordmark anchors the lower left; small legal links, location and local time align along the bottom to its right. The default ending is 437px high; long editorial versions are 644px with more space above navigation. Sage narratives continue the sage background through the footer.

**Transfer:** Keep the oversized identity, right-heavy navigation and low metadata baseline rather than filling every column.

### Directory row

**Only for:** team directories

**Use:** Compact people listing grouped by department.

**CSS:** `border-bottom: 1px solid #e5e4e4; display: grid; grid-template-columns: 1fr 1fr; gap: 32px; padding: 12px 0`

**Text style:** `person-name` — Proxima Nova 400 · 18px/1.4

**Observed:** A 38px colored initials circle precedes the name; the second column holds an italic serif role at half opacity. Departments occupy the left third; rows occupy the right two-thirds. Department rules are darker than row separators; the resting row is about 63px high.

**Transfer:** Use compact initials and roles rather than a portrait-card wall.

### Email copy strip

**Only for:** recruiting contact panels

**Use:** A direct-contact action with visible copy affordance.

**CSS:** `background: #18372c; border-radius: 10px; height: 119px; display: flex; justify-content: space-between; overflow: hidden`

**Text style:** `email-address` — Lora 400 · 30px/1.2 · tracking -0.03em

**Observed:** The address is inset 48px at left. A 120px charcoal square at right holds an outlined duplicate-sheets icon. A short two-line instruction list sits above the strip.

**Transfer:** Use one primary correspondence channel and retain the large serif address rather than substituting an input form.

## Imagery and graphics

### Environmental opening scene

**Use:** The default first impression.

**Observed:** A full-bleed aerial film shows a residential landscape, autumn forest and distant horizon; a black veil at 20% lowers brightness so white identity and serif copy remain readable. Photography fills the entire first viewport and feels real, not studio-rendered.

**Transfer:** Use a slow environmental view of the new product's world: a workplace, landscape, workshop or lived-in setting. A high-quality still is the minimum version; preserve the horizon, depth and large uninterrupted image area.

### Editorial photography

**Use:** Capability rows and long-form spreads.

**Observed:** Warm brick and timber interiors, blue water, courtyards and city views are shown in natural light. Landscape frames alternate with tall images and near-full-width spreads; images sit directly on white or ocean backing, with small corners and no decorative frames. Occasional black-and-white office imagery adds documentary contrast.

**Transfer:** Show tangible use and human surroundings. For a digital product, pair a real working environment with one clean interface image rather than building a page entirely out of dashboards.

### Identity masthead

**Use:** Monumental opening and ending anchor.

**Observed:** A short uppercase sans wordmark appears as 432×111px artwork, white over the opening and black on the ending. It is much larger than utility text but occupies only the lower-left portion, not the full page width.

**Transfer:** Typeset the new project's name in an open sans or create a simple SVG wordmark; retain its approximately 30%-of-viewport width and broad capital silhouette.

**Build:** Use a responsive SVG viewBox around the project's own uppercase name. Set width to 432px at a 1440px layout, preserve aspect ratio and use currentColor. Anchor within the 22px left and bottom inset; use white over imagery and black on light canvas.

### Abstract landscape linework

**Only for:** abstract editorial openings

**Use:** An atmospheric alternative for a people or institutional introduction.

**Observed:** A heavily defocused landscape produces dark green, gray-blue and earthy brown fields. Thin white paths sweep across it in oversized rounded, angular loops; small italic serif words float near the paths. A lower-left uppercase page title remains the only large text.

**Transfer:** Blur an environmental image into broad soft masses, then add original line paths related to the new project's concepts. Keep the image atmosphere and sparse annotations rather than drawing a literal diagram.

**Build:** Layer a cover photograph beneath backdrop-filter brightness(0.8) blur(50px). Add an SVG spanning the viewport with two open, irregular paths: long diagonal runs, broad curved returns and rounded corners; use a 1px rgba(255,255,255,0.7) stroke with no fill. Place 16px italic serif annotations in the open spaces.

### Recruiting collage and category pile

**Only for:** recruiting pages

**Use:** A people-centered opening and a playful conversion companion.

**Observed:** The opening arranges three differently sized images on taupe: a black-and-white office at upper left, a candid group image high at right and a tall building image below it. The lower-left title has ample empty space around it. Later, large dark serif capsules lie at varied angles along the bottom of a charcoal square.

**Transfer:** Combine a place, a candid group and a product-context image. Translate role names into the new project's disciplines and keep their graphic pile low in the panel.

**Build:** For the category pile, clip a 687×640px charcoal panel at 8px radius. Place four #262626 pills with white Lora text around 30.7px, 20px vertical and 49px horizontal padding, anchored near the lower edge. Rotate individual pills at modest opposing angles and overlap their ends; leave the upper half mostly open.

### Community editorial feed

**Only for:** community feeds

**Use:** Dense but airy proof of activity and local texture.

**Observed:** Four masonry-like columns mix 329px pastel account squares, square food and interior photos, tall candid images and white caption cells. Serif account names sit low on solid taupe, sage, rose and blue-gray tiles; thin vertical and horizontal separators keep the collage ordered. Rounded hashtag pills collect near the foot of caption cells.

**Transfer:** Use genuine activity around the new product, with curated image variety and concise captions; avoid making every cell the same size or every post a card with a shadow.

### Sage commitment collage

**Only for:** brand-story commitment chapters

**Use:** A sustained values narrative with tangible external context.

**Observed:** Large forest-green verbs are staggered left then right over sage, with a wide sunrise coastline image. A following three-column ruled field mixes a simple circular identity graphic, short numbered texts, a tall boardwalk image and a square autumn-lake image.

**Transfer:** Translate commitments into a few active verbs and pair them with real places or people affected by the product. Keep the color field continuous and the image variety deliberate.

**Build:** Construct the identity tile as an unfilled 300px SVG circle with a faint forest stroke and the project's own centered symbol. Use 1px rgba(25,63,50,0.2) separators for the surrounding grid. For a dotted link underline, use radial-gradient(circle, rgba(58,87,72,0.7) 1.4px, rgba(0,0,0,0) 1.6px) repeated along a narrow baseline.

### Icons

**Observed:** Thin directional arrows, simple plus/minus controls and outlined utility symbols dominate. Conversion arrows are 20×18px with a 1px butt-capped stroke; accordion controls use 42px circles. Large chapter emblems are geometric line drawings, distinct from the small UI icons.

**Transfer:** Use simple line icons with square ends and generous negative space. Keep arrows directional and understated; reserve large original emblems for chapter identity rather than adding an icon to every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Landscape masthead opening

**Observed:** The first 900px is a single full-viewport environmental scene. From back to front: a cover aerial film, a black 20% veil, a mid-height hairline and 288px-wide two-line Hero-caption at left, the oversized Identity masthead along the lower left, and the Hero destination tile cluster in the lower right. The cluster occupies roughly the right third and lower half of the viewport: a 480×192px wide image-and-copy destination above two smaller tiles, with Hero utility pills nested between. The Navigation badge floats at upper right. The wordmark is 432×111px artwork rather than a conventional headline; it spans about 30% of the viewport width. The scene, identity, support line and exploration actions are visible before scrolling; the white positioning statement and capability rows begin below the fold.

**Transfer:** For a new marketing page, preserve the asymmetry and environmental scale. Use an original project-name masthead, a single restrained positioning sentence and a small set of contextual destinations. A compelling still photograph of the product's environment is sufficient when film is unavailable. Recruiting opens with a taupe collage and a bottom-left Page-title; story pages use full-cover photography and the same bottom-left title; portfolios can split a title around one central image.

**Avoid:** Do not replace this with a centered headline, stacked paragraph and giant primary button above a small isolated product render. Do not turn the opening destination cluster into a full-width navigation bar.

**Text style:** `hero-caption` — Lora 400 · 15.2px/1.35 · tracking 0.0105em

### Heading pair and positioning pause

**Observed:** A short Statement appears on white with substantial vertical breathing room. Subsequent section headings align to the outer gutter, with an Eyebrow followed by 21px and the Section-heading. The heading occupies a small portion of the available page width rather than centering over the content.

**Transfer:** Use the statement to frame the product's approach, then concise labels and headings to orient the reader.

### Capability ledger

**Observed:** Capability row components form a continuous ruled list. Each pairs an index rail, light Capability-title, narrow Body paragraph and Explore link with a half-width image. White space below the short copy is intentional; the image determines the row's scale.

**Transfer:** Organize by distinct user outcomes or product capabilities; the number of rows follows the content.

### Image-linked explanation chapter

**Observed:** Charcoal chapter with a heading pair, a large portrait-oriented photograph at left and ruled topics at right. Accordion control components carry plus/minus symbols and Accordion-title text; an expanded item exposes a short Body paragraph. A small continuation action sits near the upper-right edge.

**Transfer:** Use for criteria, product principles or selection guidance with a meaningful photo for each topic.

### Staggered quantified proof

**Observed:** A two-column grid of Stat cell components has a vertical center rule and offset horizontal baselines. The introductory left cell contains the heading at top and a caption at bottom; the right begins with a large figure lower down. Figures and short captions alternate down the columns, with large open interiors and no card fills.

**Transfer:** Retain the staggered ledger device with truthful numbers relevant to the new offering. Use fewer entries rather than reducing all figures to conventional small stats.

### Paired closing invitations

**Observed:** Two 687×640px Conversion card components sit within 22px outer gutters and a 22px gap, with 48px space above and below. A solid Ocean panel with a large original symbol balances a candid photographic card with a Photo legibility veil. Labels and 62px headings sit near the top; Conversion buttons sit near the lower left.

**Transfer:** Give two distinct audiences or next steps equally confident destinations. The solid card should carry the strongest brand color; the photo card adds human warmth.

### Identity-led ending

**Observed:** Masthead footer is separated by a faint rule. Navigation begins in the right portion; a large field of white remains at left until the low wordmark. The bottom metadata row is quiet and aligned with the wordmark's baseline. Editorial endings allow more vertical space; the sage story variant keeps its colored canvas.

**Transfer:** End with an unmistakable project identity and useful navigation rather than another sales headline.

### Editorial chapter spread

**Only for:** portfolio and long-form editorial pages

**Observed:** Editorial thirds organize a numbered chapter title, a 48px proposition, tall photography, a small emblem and a 320px support paragraph placed well below the headline. Full-width image spreads and offset Editorial-quote pauses extend the chapter. One whole chapter reverses to Ocean panel color rather than tinting isolated cards.

**Transfer:** Use for a deep capability or case-study narrative, varying image scale and placing explanatory copy asymmetrically. Let the chapter count and sequence follow the argument.

**Text style:** `editorial-title` — Proxima Nova 300 · 62px/0.95 · tracking -0.025em

### Numbered editorial observations

**Only for:** brand-story pages

**Observed:** A narrow section lead is followed by full-width hairline rows. A clay-colored index occupies the left third; Numbered-observation text begins at the next third and stops within a 544px measure. Rows are about 150px high with substantial open space below the words.

**Transfer:** Present a few foundational insights or problems, each as one specific observation rather than a slogan.

**Text style:** `numbered-observation` — Proxima Nova 400 · 26px/1.15 · tracking -0.04em

### Mission and commitment field

**Only for:** brand-story pages

**Observed:** Clay mission band pairs a white serif statement with a tall nature photograph. Later, Sage editorial field sustains staggered uppercase verbs, a wide landscape, a large commitment statement and a ruled collage of numbered text and photography. The sage tone continues behind the Conversion card pair and Masthead footer.

**Transfer:** Give a genuine product principle its own visual chapter. Use action words and concrete commitments, with real supporting imagery instead of stock sustainability symbols.

### People directory

**Only for:** team pages

**Observed:** Department labels occupy the left third; Directory row components fill the remaining two-thirds. Department groups have 48px separation and stronger top rules. Names and serif italic roles are presented as a typographic roster rather than portraits.

**Transfer:** Keep professional detail compact and readable; let the directory's rhythm carry the people section.

### Direct correspondence close

**Only for:** recruiting pages

**Observed:** A Forest contact panel replaces an additional pair of conversion cards. A two-line 62px heading occupies the upper left; two short dot-led instructions sit below a fine rule near the bottom. Email copy strip spans the panel width under the instructions, followed by the white Masthead footer.

**Transfer:** Use for open-ended inquiries or applications when personal contact matters more than a multi-field form.

## Page flow

**Storyline:** environmental promise → concise positioning → capability or principle chapters → tangible and quantified proof → audience-specific invitation → identity-led ending

### Introduce an integrated offering and route different audiences

1. **Atmospheric promise** — Full-scene masthead and lower-right destination cluster.
2. **Positioning** — Short statement on a white field.
3. **Capability explanation** — Numbered image-and-text rows.
4. **Decision guidance** — Dark image-linked accordion.
5. **Quantified proof** — Staggered monumental figures.
6. **Closing call** — Solid and photographic invitation pair followed by the compact identity footer.

**Transfer:** Lead with the product's world, explain its main capabilities and substantiate them before routing the reader onward.

### Explain the people and thinking behind an organization

1. **Atmospheric introduction** — Defocused environment, white line paths and lower-left title.
2. **Foundational context** — Asymmetric statement, photographs and narrow explanatory text.
3. **Editorial pause** — A full-width image and offset large statement.
4. **People proof** — Department-led typographic directory.
5. **Closing call** — Large image, pale-and-photographic conversion pair and extended white identity footer.

**Transfer:** Use the directory variant for an organization page; retain the atmospheric opening and editorial space without making it a product landing-page default.

### Demonstrate the quality and range of work

1. **Portfolio hook** — Split uppercase title surrounding a central forest image on grained olive stone.
2. **Purpose** — Offset large proposition.
3. **Capability chapters** — Numbered editorial spreads, photographs, material details and large quote pauses; a whole middle chapter reverses to ocean blue.
4. **Activity proof** — Four-column community feed with pastel identities and candid images.
5. **Closing call** — Pale solid and photographic partnership cards, then extended white identity footer.

**Transfer:** Build distinct work chapters using real examples, alternate close detail and wide context, and use the feed only when recurring activity is meaningful.

### Attract applicants and make contact straightforward

1. **People promise** — Taupe collage with office, group and building imagery plus a lower-left uppercase title.
2. **Working proposition** — Offset 62px statement, narrow paragraph and small culture link.
3. **Opportunity** — Cream conversion card paired with a charcoal category-pill composition.
4. **Direct invitation** — Forest contact panel with instructions and large serif copy-email strip.
5. **Ending** — Compact white identity footer.

**Transfer:** Replace generic benefits tiles with candid context, a direct working proposition and one obvious application path.

### Explain a long-term philosophy and commitments

1. **Identity in context** — Full-cover photograph of a physical identity object with lower-left white title.
2. **Positioning** — Right-offset statement with a vertical rule.
3. **Purpose** — Clay serif mission band and tall nature image.
4. **Rationale** — Ruled numbered observations and candid team photographs.
5. **Long-term conviction** — Large statement opposite a tall environmental image.
6. **Commitment proof** — Sage word composition, substantial commitment text and mixed image/text grid.
7. **Closing call** — Clay and photographic invitation pair flowing into a sage identity footer.

**Transfer:** Use the sustained color variant to distinguish a deeper brand narrative; ground principles in tangible commitments and original supporting images.

## Writing

Confident, measured and purposeful, with warmth supplied by people, places and practical verbs. Claims are framed through an operating approach and tangible outcomes rather than breathless promotional language.

**Do not copy:** Do not reuse Aker's name, marks, team names, proprietary project and community names, investment totals, founding date, resident counts, fund counts, charitable commitments, addresses or source quotations as claims for another product. Examples below illustrate voice only.

- **Addressing the reader:** Mostly first-person plural: we invest, create, operate, build and commit. Reader address is sparing and appears chiefly in invitations such as joining a team or telling the company about yourself.
- **Rhythm:** Short section titles of two to five words sit above one or two purposeful sentences. Longer editorial propositions can wrap across several lines, while buttons remain brief verb-led destinations. Exclamation marks belong to community activity captions, not the institutional voice.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning | State what the organization is, then what it does differently. | One compact sentence | “[Brand] is an integrated real estate investment and operating company.” |
| Section heading | Use plain, direct orientation rather than a marketing slogan. | Three to five words | “What we do”<br>“What we look for” |
| Supporting line | Active verb, concrete object, method and enduring outcome. | One sentence of about 20–30 words | “We invest in properties with untapped potential, applying disciplined underwriting and hands-on execution to unlock lasting value.” |
| Conviction statement | Contrast the long view with a conventional short view, then explain its practical consequence. | One substantial sentence | “We think in decades, not fund cycles – and that shapes how we allocate capital, build teams, and invest in technology.” |
| Primary action | A direct verb and clear destination. | One to three words | “Explore Careers”<br>“Contact us”<br>“Job Board” |
| People invitation | Speak plainly about participation and meaningful work. | One short sentence | “Always on the lookout for new talent.” |

**Words and phrasing to use:** build; create; operate; thoughtful; lasting value; long-term; hands-on; connected; community; ownership

**Avoid:** game-changing; revolutionary; 10x everything; disrupt or die; magical; unlimited possibilities

**Rules:**

- Connect a claim to a practical method or a verifiable result.
- Let imagery supply emotion while the prose remains concrete.
- Use parallel active verbs for capability names.
- Keep proof captions short enough to sit at the foot of a large number field.
- Describe commitments specifically only when the new organization can substantiate them.

## Do's and Don'ts

### Do

- Keep standard section headings at 62px/0.9, weight 400 and -0.03em tracking.
- Use 22px outer gutters and let image-and-content fields approach the page edges.
- Keep capability paragraphs near 411px wide and editorial support near 320px.
- Maintain 1px rules and flat surfaces instead of elevation shadows.
- Use 174px light figures with bottom-aligned captions and staggered columns.
- Give conversion panels 32px padding, 8px corners and a 22px inter-panel gap.
- Keep the opening identity low at left and the 480px destination cluster low at right.
- Retain real environmental photography and the oversized footer identity even when adapting to a digital offering.

### Don't

- Do not set the main headings in bold 700 or introduce a condensed display face; the broad light sans is central to the tone.
- Do not apply uppercase and positive tracking to ordinary section labels; that treatment belongs to editorial page titles.
- Do not make every white section a rounded, shadowed card; rules and whitespace provide the structure.
- Do not turn the large proof ledger into a single tight row of 32px metrics.
- Do not replace the 8px panel corners with oversized 32px rounding across the site.
- Do not use neon gradients or colorful status badges as the default marketing palette; chromatic fields are deep, earthy chapter treatments.
- Do not expand the fixed menu badge into a conventional tall sticky header.
- Do not fill the empty side of the footer with extra promotional copy; its imbalance supports the masthead.

## Motion and responsive

### Motion

**Observed:**

- The opening scene is a background video and its surrounding section is sticky.
- Declared utility-pill background transition is 0.3s; conversion-button background transition is 0.25s.
- Accordion plus/minus lines declare transform 0.6s cubic-bezier(0.77, 0, 0.175, 1).
- Other links declare opacity 0.35s cubic-bezier(0.165, 0.84, 0.44, 1) and color 0.2s; editorial buttons declare filter 0.25s.

**Transfer:**

- Keep hover feedback tonal and restrained, changing glass opacity or brightness rather than introducing a new accent.
- Preserve the distinction between slow atmospheric media and compact utility interaction; a static environmental image can carry the same composition.

**Unknown:**

- Scroll choreography, video playback timing, carousel scheduling and any full menu-opening timing are not established.
- Focus-visible styling is not established; retain accessible focus indication rather than treating declared outline removal as design guidance.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 768px, 991px, 992px, 1440px and 1920px.
- Root font-size uses calc(0.812695rem + 0.208117vw), so rem dimensions scale together.

**Transfer:**

- On narrow layouts, preserve the distinction between atmospheric opening, readable copy and destination cluster; move destinations below the masthead if they would cover the environmental subject.
- Stack paired conversion fields and capability photography while retaining the index rail and small ruled labels.
- Reduce proof-column count before squeezing long figures; keep number and caption together.

**Unknown:**

- Actual narrow-screen compositions, type overrides, mobile menu behavior and ordering changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
