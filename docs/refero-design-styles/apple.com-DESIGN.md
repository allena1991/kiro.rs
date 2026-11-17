# Apple — hardware as theater

## Overview

A cinematic, object-led style that makes sophisticated technology feel immediate and desirable. Monumental neo-grotesk headlines and immaculate product renders sit on black and charcoal stages, with white and pale gray retail chapters providing a brighter counterpoint. Blue is reserved for actions; material color, reflections and richly lit photography supply most of the emotion. The composition is sparse at the story level and increasingly informative near comparison and purchase.

### Essentials

- The product is a stage event, not an illustration beside a pitch: a full-width black opening puts a horizontal object across roughly two thirds of the screen, backed by luminous dimensional lettering, with an 80px/84px promise anchored below.
- Headlines speak in sculpted sentence fragments: SF Pro Display 600, 96px/100px with -0.015em tracking for chapter statements; 48px/52px section headings remain visibly subordinate.
- Conversion controls look like small polished instruments: 44px blue pills with 11px 21px padding, accompanied by restrained text links and 36px circular gallery paddles.
- Neutral theater dominates the page: black and #1d1d1f carry the main narrative, #f5f5f7 and white carry shopping and trust; blue occupies controls and links rather than broad backgrounds.
- Material revelation is a signature device: include an oversized, sharply lit detail or exploded construction view, plus a luminous word sculpture. With no physical object, use a single high-resolution interface plane and dimensional benefit lettering rather than a collage.
- Proof is designed as an object too: centered white figures at 48px/52px sit in black 28px-radius tiles inside a charcoal comparison panel, with short gray qualifiers and selectively bright pictograms.
- The emotional story resolves into useful browsing: a light surface switch introduces white 28px-radius cards, side-by-side choices and an unusually spacious category directory before the compact global footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#0071e3` | `--color-blue` | action, background | Filled conversion pills and keyboard focus outlines. |
| Luminous blue | `#2997ff` | `--color-dark-link` | link | Links on black and charcoal. |
| Reading blue | `#0066cc` | `--color-light-link` | link, border | Links and outlined actions on light surfaces. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Card white | `#ffffff` | `--color-white` | surface, text, background | White cards, light editorial canvas, button labels and emphasized prose. |
| Directory white | `#fafafc` | `--color-index` | background | Broad category navigation band at the end of a product story. |
| Soft white | `#f5f5f7` | `--color-headline` | text, background | Main dark-theme headings; light shopping bands and footer canvas. |
| Control silver | `#e8e8ed` | `--color-control` | surface | Round expansion buttons on white cards. |
| Light divider | `#d2d2d7` | `--color-rule` | border, text | Light-theme comparison rules and discreet photographic credits. |
| Narrative gray | `#86868b` | `--color-secondary` | text | Dark-theme explanatory prose, selectively interrupted by brighter phrases. |
| Label gray | `#6e6e73` | `--color-muted` | text, border | Chapter eyebrows, light-theme supporting labels and comparison selector outlines. |
| Dark edge | `#333336` | `--color-edge` | border, text | Faint outlines around black media and strong directory links on light. |
| Chapter charcoal | `#1d1d1f` | `--color-charcoal` | background, surface, text | Alternate dark chapters and raised comparison panels; primary text on light surfaces. |
| Near-black panel | `#161617` | `--color-panel` | surface | Inset charging or technical proof panel. |
| Stage black | `#000000` | `--color-canvas` | background, surface | Default cinematic page canvas and inset proof tiles. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| impact and progress storytelling | Highlighter green | `#00d959` | `--color-green` | accent, surface | Marker swashes, large line illustrations and selected report tabs. |
| impact and progress storytelling | Deep green ink | `#074237` | `--color-forest` | text | Dark pictograms and captions against vivid green. |

## Typography

- **SF Pro Display** — Headlines, chapter eyebrows, large explanatory copy and figures. Compact neo-grotesk with a high x-height, open counters and controlled semibold weight. If unavailable, use **Inter**. Use 600 for core headings and retain size-specific tracking. Font stack: "SF Pro Display", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **SF Pro Text** — Buttons, links, captions, card body and navigation. Small-size companion with sturdy spacing; tightened tracking keeps labels compact. If unavailable, use **Inter**. Use 400 and 600; preserve the smaller optical scale. Font stack: "SF Pro Text", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | SF Pro Display | 600 | 96px | 100px | -0.015em | Monumental chapter statements, usually one or two lines. |
| hero-promise | SF Pro Display | 600 | 80px | 1.05 | -0.015em | Opening benefit line beneath the product name. |
| feature-display | SF Pro Display | 600 | 64px | 68px | -0.009em | Focused technical chapter statement. |
| heading-lg | SF Pro Display | 600 | 56px | 60px | -0.005em | Comparison panel title and major supporting heading. |
| heading | SF Pro Display | 600 | 48px | 52px | -0.003em | Section headers and large proof figures. |
| product-name | SF Pro Display | 600 | 32px | 1.125 | 0.004em | Product identifier above the opening promise. |
| card-heading | SF Pro Display | 600 | 28px | 1.143 | 0.007em | White feature cards and elevated category links. |
| lead | SF Pro Display | 600 | 21px | 1.381 | 0.011em | Explanatory chapter prose, gray with selected white phrases. |
| eyebrow | SF Pro Display | 600 | 21px | 1 | 0.011em | Sentence-case chapter category, 20px above the statement. |
| caption-strong | SF Pro Text | 600 | 17px | 1.235 | -0.022em | Run-in caption labels and compact explanatory copy. |
| body | SF Pro Text | 400 | 17px | 1.235 | -0.022em | Card body and text links. |
| button | SF Pro Text | 400 | 17px | 1.176 | -0.022em | Main conversion pill labels. |
| price | SF Pro Text | 600 | 14px | 1.286 | -0.016em | Compact two-line pricing in the opening action platter. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| immersive experience narratives | cinema-display | SF Pro Display | 700 | 80px | 1.05 | -0.015em | Centered promise over a full-screen use-case film. |
| impact and progress storytelling | marker-display | SF Pro Display | 600 | 80px | 1 | -0.015em | Two-line centered statements with a marker swash behind the first phrase. |
| immersive experience narratives | cinema-eyebrow | SF Pro Display | 700 | 24px | 1.167 | 0.009em | Centered use-case label above the cinematic promise. |
| benefit education pages | tile-heading | SF Pro Display | 600 | 21px | 1.19 | 0.011em | Small benefit heading above tile-body. |
| benefit education pages | tile-body | SF Pro Display | 600 | 19px | 1.421 | 0.012em | Longer benefit explanations within expansive light tiles. |
| multi-model comparison sections | comparison-copy | SF Pro Text | 400 | 14px | 1.43 | -0.016em | Centered attribute rows beneath product choices. |
| editorial landscape photography | credit | SF Pro Text | 400 | 12px | 1.333 | -0.01em | Discreet right-aligned photographic location credit. |

**Notes:**

- The name is smaller than the promise: 32px over 80px, not a giant repeated product name.
- Negative tracking strengthens with headline size, from -0.003em at 48px to -0.015em at 80–96px. Mid-size labels instead have slight positive tracking.
- Emphasis in chapter prose changes gray to white without making every sentence bold. Caption labels run directly into the explanation rather than adding another stacked heading.
- Dimensional opening lettering is artwork, not another ordinary heading. Keep it visually distinct from the measured text hierarchy.

## Layout

**Density:** Airy in the cinematic narrative, compact only within controls and comparison rows.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Price-line separation. |
| 12px | Card heading to body; portal tile gutters. |
| 18px | Between circular gallery paddles. |
| 20px | Primary card gutters and eyebrow-to-headline separation. |
| 24px | Feature statement to lead and repeated media-row spacing. |
| 28px | Gallery image to inset caption. |
| 32px | Feature-card copy padding and proof-tile inner padding. |
| 45px | Inner horizontal copy inset in benefit-education tiles. |
| 48px | Section header to gallery; directory heading to columns. |
| 64px | Chapter copy to media and major internal breathing room. |
| 72px | Comparison panel top padding and design-heading to object stage. |
| 80px | Broad separation before featured card content. |
| 120px | Reduced major section padding and comparison panel bottom padding. |
| 144px | Default top and bottom padding for narrative and shopping chapters. |
| 224px | Extended exit space after the highlights stage. |

### Containers and grids

- **story-container**: max width 1260px · side padding 90px. Centered desktop story width at 1440px; galleries begin at its left edge and can extend beyond the right viewport.
- **copy-column**: max width 840px. Centered explanatory lockups within the wider product stage.
- **detail-stage**: max width 1050px. Inset technical media, selector and quantified proof.
- **proof-grid**: max width 1050px · 3 columns · gap 20px. Six near-square proof tiles in two rows inside the broad charcoal panel.
- **footer-container**: max width 980px · side padding 22px. Narrower centered directory, credits and legal utility area.
- **benefit-grid** (only for benefit education pages): max width 1390px · 2 columns · gap 25px · side padding 25px. Two expansive light tiles alternate with a full-width tile.
- **portal-grid** (only for multi-product portals): 2 columns · gap 12px · side padding 12px. Edge-near rectangular campaign tiles rather than a rounded-card wall.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards | 28px |
|  | pills | 980px |
|  | local-navigation | 18px |
|  | icon-controls | 50% |
| benefit education pages | education-tiles | 30px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| glass-edge | `0px 0px 0px 1px rgb(40, 40, 40)` | Fine dark local-navigation edge, not a floating drop shadow. |

### Surfaces

#### Black stage · level 0

**Use:** Default story background.

**CSS:** `background: #000000; color: #f5f5f7`

**Observed:** Media edges disappear into the canvas; the object is revealed by lighting rather than a decorative container.

**Transfer:** Use clean black around the most dramatic object scenes.

#### Charcoal chapter · level 0

**Use:** Alternate narrative chapters and comparison panel backing.

**CSS:** `background: #1d1d1f; color: #f5f5f7`

**Observed:** Broad full-width chapters interrupt the black stage without introducing a new chromatic theme.

**Transfer:** Change the neutral value to separate a capability family.

#### Light shopping band · level 0

**Use:** Purchase support, trust, comparison and footer.

**CSS:** `background: #f5f5f7; color: #1d1d1f`

**Observed:** The dark story opens into an extended light tail, not a final isolated CTA stripe.

**Transfer:** Let the ending become useful browsing at a more informational density.

#### White card · level 1

**Use:** Offer and trust cards on the light shopping band.

**CSS:** `background: #ffffff; border-radius: 28px; box-shadow: none; overflow: clip`

**Observed:** Flat bright surfaces rely on contrast and curved silhouettes, not elevation shadows.

**Transfer:** Keep images and copy inside the same clean enclosure.

#### Technical panel · level 1

**Use:** A self-contained technical proof block.

**CSS:** `background: #161617; border-radius: 28px`

**Observed:** A near-black value creates separation within the black chapter.

**Transfer:** Use for one concentrated proof rather than every paragraph.

#### Outlined media · level 1

**Use:** Dark media whose boundaries need separation.

**CSS:** `border: 1px solid #333336; border-radius: 28px; overflow: hidden`

**Observed:** The line is a subtle edge, not a bright frame.

**Transfer:** Apply only where black media meets a black canvas.

#### Local glass · level 2

**Use:** Floating product navigation.

**CSS:** `background: rgba(18, 18, 18, 0.8); border-radius: 18px; backdrop-filter: blur(20px); box-shadow: 0px 0px 0px 1px rgb(40, 40, 40)`

**Observed:** Compact dark glass stays above the story while imagery passes behind it.

**Transfer:** Reserve blur for actual controls over media.

#### Light navigation glass · level 2

**Only for:** light multi-product portals

**Use:** Full-width global navigation.

**CSS:** `background: rgba(255, 255, 255, 0.8); backdrop-filter: saturate(1.8) blur(20px)`

**Observed:** Thin translucent band rather than a rounded floating panel.

**Transfer:** Use the light navigation treatment with the portal variant.

## Components

### Primary button

**Use:** The main purchase or conversion action.

**CSS:** `background: #0071e3; color: #ffffff; border-radius: 980px; padding: 11px 21px; height: 44px; border: 1px solid transparent`

**Text style:** `button` — SF Pro Text 400 · 17px/1.176 · tracking -0.022em

**Observed:** A short verb in a filled pill; the opening pairs it with pricing inside a dark platter. Smaller 36px and 24px variants serve cards and local navigation.

**States:** Declared: hover background #0076DF and white text; focus-visible outline 2px solid #0071e3 with 3px offset; active background #006EDB.

### Text action

**Use:** Secondary exploration and film links.

**CSS:** `color: #2997ff; text-decoration: none`

**Text style:** `body` — SF Pro Text 400 · 17px/1.235 · tracking -0.022em

**Observed:** Chevron or circled play symbol follows the label. Light surfaces use reading blue; the link can align to the far edge of a section heading row.

**States:** Declared: hover underline; focus-visible outline 2px solid #0071e3 with 1px offset.

### Product navigation

**Use:** Persistent orientation and purchase access in a long story.

**CSS:** `background: rgba(18, 18, 18, 0.8); border-radius: 18px; backdrop-filter: blur(20px); max-width: 1024px; height: 52px; padding: 12px 0px`

**Observed:** A floating horizontal product bar: identifier left, exploration and a tiny purchase pill right. It reveals after the opening rather than competing with the first object.

**Transfer:** Keep this a utility rail, not a second hero.

### Comparison selector

**Use:** Choose a previous version or comparison baseline.

**CSS:** `background: rgba(255, 255, 255, 0.04); border: 1px solid #6e6e73; border-radius: 980px; height: 44px; padding: 0px 45px 0px 24px`

**Observed:** Visible label above a wide native selector with a downward chevron; centered beneath an introductory claim or aligned to the right of a panel title.

**Transfer:** Use a real select with a truthful baseline and update the proof, not just its label.

### Proof tile

**Use:** Quantified capability or compact visual proof.

**CSS:** `background: #000000; border-radius: 28px; height: 300px; overflow: clip; display: grid`

**Text style:** `heading` — SF Pro Display 600 · 48px/52px · tracking -0.003em

**Observed:** Centered figure and gray qualifier alternate with product details and glowing silicon imagery. The 337px-wide desktop tiles sit inside a larger charcoal enclosure.

**Transfer:** Mix figures and object fragments while keeping one claim per tile.

### Offer card

**Use:** Buying benefits or related trust information.

**CSS:** `background: #ffffff; border-radius: 28px; display: flex; flex-direction: column; justify-content: space-between; overflow: clip`

**Text style:** `card-heading` — SF Pro Display 600 · 28px/1.143 · tracking 0.007em

**Observed:** Small category label, short headline, body, large lower illustration and a circular expansion control. Copy is inset 32px; 372px-wide gallery cards continue offscreen.

**Transfer:** Use a product still, a clean symbolic illustration or a relevant close-up in the lower half.

### Gallery paddle

**Use:** Next and previous media navigation.

**CSS:** `background: rgba(66, 66, 69, 0.72); color: rgba(255, 255, 255, 0.8); width: 36px; height: 36px; border-radius: 36px; display: flex; align-items: center; justify-content: center`

**Observed:** Filled chevrons in paired circles, 18px apart, aligned below the right edge of the gallery. Disabled previous control has opacity 0.36; light-gallery circles are pale gray.

**States:** Declared: hover background rgba(73,73,76,0.7256); focus-visible outline 2px solid #0071e3 with 3px offset; active background rgba(57,57,60,0.7424).

### Media caption

**Use:** Explain a gallery item without placing a paragraph over its image.

**CSS:** `padding: 28px 16px 0px`

**Text style:** `caption-strong` — SF Pro Text 600 · 17px/1.235 · tracking -0.022em

**Observed:** A bright run-in label immediately followed by gray explanatory copy; caption remains outside the rounded image.

**Transfer:** Use one technical detail and its practical benefit.

### Category directory

**Use:** Spacious product-family browsing before the global footer.

**CSS:** `background: #fafafc; padding: 144px 0px`

**Text style:** `card-heading` — SF Pro Display 600 · 28px/1.143 · tracking 0.007em

**Observed:** A 48px section title leads into three left-aligned columns. The first column has elevated 28px links, the others compact 17px links; labels use muted gray.

**Transfer:** Expose a small, curated next-step index rather than ending with a single oversize button.

### Global footer

**Use:** Site-wide directory and utility ending.

**CSS:** `background: #f5f5f7; display: flex; max-width: 980px`

**Observed:** A compact five-column directory follows relevant terms and a breadcrumb. Thin rules separate the content, shopping-help line and copyright/legal row; the utility area is narrower than the main story.

**Transfer:** Scale the number of columns to real destinations and keep the utility ending visually restrained.

### Benefit tile

**Only for:** benefit education pages

**Use:** Explain a capability with a large isolated product demonstration.

**CSS:** `background: #f5f5f7; border-radius: 30px; display: flex; overflow: hidden`

**Text style:** `tile-body` — SF Pro Display 600 · 19px/1.421 · tracking 0.012em

**Observed:** Copy starts at the upper left, with a small dark heading, gray body and blue link. Large device imagery sits beneath in half-width tiles, or fills the right side of a full-width tile; copy uses a 45px left inset.

**Transfer:** Alternate overview pairs with single enlarged demonstrations.

## Imagery and graphics

### Luminous word sculpture

**Use:** Signature opening graphic behind the primary object.

**Observed:** Three huge extruded silver letters sit behind a burgundy device in profile. Their smooth rounded edges catch white, pale cyan and warm reflections against absolute black; the art spans roughly two thirds of the viewport while text remains below.

**Transfer:** Make a short benefit word into dimensional stage scenery for the new product. Minimum acceptable version is vector lettering with convincing metal-like edge light plus one excellent product cutout, not ordinary white text.

**Build:** Use very heavy tightly packed SVG lettering behind the object, with a vertical charcoal-to-white-to-silver gradient, a fine white upper-edge highlight and restrained pale cyan blurred rim light. Duplicate the letter outline behind it with a slight downward offset to suggest extrusion. Mask the foreground object over the central letter area; keep the surrounding canvas black.

### Material macro

**Use:** Capability chapter art and product-detail galleries.

**Observed:** Enormous lens rings, black glass, machined edges and side controls emerge from dark surroundings. Burgundy, graphite and titanium tones remain subdued; crisp grazing highlights reveal shape. Some views extend beyond the viewport.

**Transfer:** Photograph or render one meaningful mechanism at close range with broad softbox reflections and very dark backing. For software, enlarge a single interface operation and preserve a clean silhouette.

### Cinematic demonstration

**Use:** Feature proof in large media and caption galleries.

**Observed:** Portraits, still-life arrangements and nighttime scenes use saturated red, teal, purple or warm light within the image. The surrounding marketing surface stays neutral; 696×452px media can alternate with narrower tall items.

**Transfer:** Commission a carefully lit example of what the product enables; use one coherent scene instead of stock-photo mosaics.

### Performance light

**Use:** A luminous technical emphasis within the dark story.

**Observed:** A pale mint-to-blue gradient colors the monumental performance headline; a small metallic chip has a restrained cool glow. The rest of the chapter is black with gray prose.

**Transfer:** Include a concentrated light accent at a genuine technical reveal, not a page-wide rainbow.

**Build:** Clip a horizontal pale mint, icy blue and white gradient into display lettering; enlarge the gradient layer to 300% width for a single sweep. For a small proof object, put two low-opacity cyan and violet blurred ellipses behind a silver rounded square; keep glow tightly bounded to the object.

### Human-scale immersion

**Only for:** immersive experience narratives

**Use:** Full-screen use-case chapters and the light portrait opening.

**Observed:** A person wearing the product is shown in bright neutral portraiture at the opening. Later, warm domestic interiors and travel scenes demonstrate digital content at architectural scale; centered white headlines overlay darkened films. A black technical chapter switches to exploded hardware and precise sensor details.

**Transfer:** Show the user and the effect in the same believable environment. A static staged composite is preferable to a weak simulated film.

### Progress illustration

**Only for:** impact and progress storytelling

**Use:** Marker headings, large proof posters and editorial interludes.

**Observed:** Vivid green line art overlays water photography, a dark circular heap of material or deep green backing. Large condensed-looking percentage artwork contrasts with ordinary sans captions outside 28px-radius posters. A landscape opening uses misty forest photography and a hand-drawn date emblem.

**Transfer:** Build a small visual vocabulary around the new subject: one vivid highlighter hue, diagram-like outlines and photographed material. Keep artwork numerals distinct from the normal type recipes.

**Build:** Draw simple SVG paths with rounded joins for one subject-specific outline; use green and white strokes in complementary segments. Center a large bold percentage inside, place a two-line caption low in the poster, and put detailed explanation below the image. Make heading highlights as rounded green rectangles behind the first phrase with subtly irregular SVG edges.

### Floating variants

**Only for:** customizable product education

**Use:** A broad personalization panel.

**Observed:** Multiple watch forms rotate diagonally through a pale gray field; rich fabric, metal and rubber textures provide color. Partial objects enter from the edges while the copy retains a clear upper-left zone.

**Transfer:** Arrange a small family of material variants at different rotations and scales, preserving a generous blank region for copy.

### Icons

**Observed:** Utility marks are compact monochrome silhouettes or simple filled chevrons, not a conspicuous outline icon system. Gallery controls use 36px SVG canvases; detail triggers can use 24px line marks. Proof pictograms become brighter and larger only inside the proof art.

**Transfer:** Use simple chevrons, plus, play and pause symbols. Put them in the measured circles and pills; use subject-specific illustration only in proof or trust cards.

## Section recipes

How recurring sections are built.

### First screen: Sculptural product opening

**Observed:** A 44px global navigation and compact promotional strip cap a full-width black stage. The main horizontal object and luminous word sculpture occupy the middle of the screen, with black air above and below. Along the bottom of the first 900px, the left edge of the 1260px content width holds a 32px product name above the 80px promise; the right holds a dark rounded platter with two 14px price lines and Primary button. The object, identity, promise and purchase action are all visible in the first screen. Detailed introductory prose and the highlights gallery begin below it.

**Transfer:** Keep the object-first silhouette, monumental dimensional lettering and lower anchored text/action balance. Without a physical product, stage one isolated interface plane over the word sculpture. Multi-product portals instead open with a centered 56px product heading, a 28px support line, paired pills and a bright product image; educational pages use an 80px centered claim above a wide row of products, while immersive narratives use a close human portrait with identity and actions low on the frame.

**Avoid:** Do not replace the central stage with a conventional equal-width text-and-image split or bury the action below a full viewport of art.

**Text style:** `hero-promise` — SF Pro Display 600 · 80px/1.05 · tracking -0.015em

### Chapter lockup

**Observed:** Eyebrow at 21px/21px sits 20px above a display statement; centered chapters limit prose to 840px with 24–26px separation. Major chapter padding is 144px, with 64px breathing room before media. A design chapter uses the same scale left aligned.

**Transfer:** Introduce one capability family with a short category and a memorable claim, then explain the mechanism in a concise lead.

**Text style:** `display` — SF Pro Display 600 · 96px/100px · tracking -0.015em

### Highlights stage

**Observed:** Charcoal chapter uses a 48px heading left and Text action right. A 1260×612px rounded cinematic gallery sits below, with the next slide peeking at the right and a compact translucent dot-and-pause controller at the lower center.

**Transfer:** Use a small set of visibly distinct capability scenes, one claim per slide. Maintain the next-item peek rather than shrinking everything to fit.

**Text style:** `heading` — SF Pro Display 600 · 48px/52px · tracking -0.003em

### Caption gallery

**Observed:** A left-aligned 48px heading introduces oversized rounded media, commonly 696×452px, spaced 20px apart. Media caption sits outside each image; Gallery paddle pair sits below at the right.

**Transfer:** Let a wide primary example and narrower companion items create editorial variety without making a checkerboard of equal cards.

### Quantified comparison panel

**Observed:** A 1260px charcoal rounded panel has 72px top and 120px bottom padding. A 56px title aligns left and Comparison selector right; below sits the three-column Proof tile grid with 20px gaps. Large figures alternate with object images and bright simple symbols.

**Transfer:** Compare meaningful baselines using a mixture of visual and numeric proof, not six generic icon boxes.

**Text style:** `heading-lg` — SF Pro Display 600 · 56px/60px · tracking -0.005em

### Light retail resolution

**Observed:** Light shopping band changes the mood after the dark accessory or ecosystem statement. Heading and Text action precede horizontally scrollable Offer cards, followed by white side-by-side model comparison, small proof cards and trust cards.

**Transfer:** Move from desire to choosing, paying and reassurance. Use only the forms of assistance relevant to the new product.

### Benefit education mosaic

**Observed:** A 56px category heading is inset 70px from the viewport edge. Two-column Benefit tiles use 25px gutters and 30px corners; full-width image-led tiles interrupt the pairs. Copy is small relative to the almost life-size product demonstration.

**Transfer:** Group capabilities by human outcome; reserve the biggest tile for a feature that benefits from enlargement.

### Impact chapter and resources

**Observed:** Centered 80px marker-display statements bridge oversized product/material photography and green illustrated proof posters. The ending becomes report tabs, two-column resource lists, thumbnail news rows with dates and a restrained Show more control, then white related-topic cards.

**Transfer:** For a research or progress page, pair expressive summaries with genuinely useful documentation; keep the green marker treatment scoped to that narrative.

### Immersive chapter and open-ended close

**Observed:** A 24px category and 80px bold centered promise overlay a full-width film. The following white area holds gray lead copy and 820×530px caption galleries. Later black technical scenes give way to a light accessory split panel and a centered 56px invitation above a 24px paragraph and text link.

**Transfer:** Use the immersive variant for experiences that need human context. Close a platform story by inviting a new kind of participation, not by adding an unrelated sales slogan.

**Text style:** `cinema-display` — SF Pro Display 700 · 80px/1.05 · tracking -0.015em

### Directory ending

**Observed:** Category directory precedes relevant terms and Global footer on light neutrals. Its first column has unusually large 28px links while other columns use compact labels. The global directory has five columns within 980px; shopping help, a thin divider and legal row finish the page.

**Transfer:** Preserve a useful, quieter ending with links to comparisons, support and related categories; do not reproduce a long narrative merely to delay the footer.

## Page flow

**Storyline:** object-led promise → highlights → capability chapters with visual and quantified proof → choosing and purchase reassurance → useful onward browsing

### Flagship product launch

1. **promise** — Black sculptural object stage with lower identity and purchase platter.
2. **overview** — Highlights carousel, broad benefit statement and selectable baseline statistics.
3. **capability chapters** — Monumental design, creative, endurance and performance statements alternating macro art, demonstrations and caption galleries.
4. **quantified proof** — Charcoal comparison panel with selector and six black proof tiles.
5. **ecosystem** — Related capabilities and accessories extend the value of the central object.
6. **purchase reassurance** — Light offer cards, model comparison and short trust cards.
7. **onward browsing** — Large category directory, terms, breadcrumb, global columns and legal utility row.

**Transfer:** Borrow the contrast between cinematic desire and practical choosing; select chapters according to the new product's strongest differentiators.

### Multi-product campaign portal

1. **promise** — Bright centered product billboard with paired actions.
2. **discovery** — Alternating dark and light full-width billboards followed by a two-column campaign grid.
3. **engagement** — Large entertainment gallery and smaller continuing media strip.
4. **utility ending** — Relevant terms lead directly into compact global directory and legal row.

**Transfer:** Use when the visitor must browse several product families rather than learn one deeply.

### Progress and institutional explanation

1. **promise** — Hand-drawn date emblem over misty forest and a bold short commitment.
2. **overview** — Lifecycle highlights and an illustrated practical-action panel.
3. **proof** — Marker statements, oversized material photographs, percentages and illustrated posters.
4. **documentation** — Report tabs, resource links and news rows.
5. **onward browsing** — Related-topic cards, brief notes, breadcrumb and complete utility footer.

**Transfer:** Give progress an expressive visual shorthand while making deeper documentation easy to find.

### Benefit education and model choice

1. **promise** — Large centered claim above a horizontally overflowing product family.
2. **capability chapters** — Outcome categories introduce pairs and full-width pale demonstration tiles.
3. **personal relevance** — Floating material variants and a related service panel.
4. **choice** — Three-column comparison with aligned attributes and small buy pills.
5. **purchase reassurance** — Four service benefits, relevant terms and the full global directory.

**Transfer:** Use for audiences who need everyday reasons before choosing a model.

### Immersive experience and platform introduction

1. **promise** — Human portrait with lower identity and monochrome demo/buy actions, then a large centered manifesto.
2. **demonstration** — Full-screen use-case films with centered headings, explanatory leads and caption galleries.
3. **technical proof** — Black construction chapter with exploded hardware, sensor imagery and three restrained figures.
4. **trust** — Light statement and illustrated privacy or accessibility details.
5. **closing invitation** — Accessory split panel, centered participation invitation, terms and the complete global footer.

**Transfer:** Show how an unfamiliar experience fits real life before revealing its mechanism, and end with an invitation appropriate to its ecosystem.

## Writing

Confident and conversational, with engineered facts underneath a playful verbal surface. Headline wit is brief; supporting prose explains what the technology does for a person.

**Do not copy:** Do not reuse Apple names, logos, product artwork, proprietary feature names, campaign slogans, performance numbers or environmental and medical claims. Source quotations below demonstrate cadence only; create original copy and substantiate new claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for benefits, we and our for deliberate design choices, and a product name for factual capability statements.
- **Rhythm:** Short fragments and paired sentences lead; fuller explanatory paragraphs follow. Periods create strong beats, and a question can receive an immediate two-word answer.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A very short benefit phrase with a double meaning. | 2–6 words | “Pro further.” |
| Chapter statement | A material or capability fact recast as a compact verbal twist. | 4–10 words | “Our finest unibody of work.”<br>“Be in the moment. All over again.” |
| Objection handling | Ask the reader's practical question and answer it briskly. | 5–9 words | “Worth the upgrade? You bet.” |
| Benefit heading | Concrete everyday outcome, occasionally with a rhyme. | 4–10 words | “You snooze. You win.” |
| Proof caption | Name the mechanism, then connect it to a result. | 1–3 sentences | “Record in more detail with support for 4K resolution with Dolby Vision HDR.” |
| Action | Plain verb, with the destination when needed. | 1–6 words | “Watch the film”<br>“Book a demo” |

**Words and phrasing to use:** designed; built-in; more; up to; your; all; feel; work; control

**Avoid:** synergy; disruptive solutions; unlock your potential; best-in-class platform; revolutionize everything

**Rules:**

- Lead with a human result; reveal the engineering in the next block.
- Use wordplay once per major statement, never in every body sentence.
- Keep numerical qualifiers adjacent to their claims and provide relevant terms.
- Prefer a useful destination label over a clever button label.

## Do's and Don'ts

### Do

- Keep the default story black and charcoal until the practical shopping chapters.
- Pair 96px semibold statements with restrained 21px explanatory prose.
- Keep major content within 1260px and ordinary chapter copy within 840px.
- Use 144px major chapter padding rather than making every block one viewport tall.
- Preserve 28px card corners and 20px gallery gutters in the core product treatment.
- Include both a dimensional word sculpture and a material-reveal scene.
- Let media continue beyond the right edge of galleries and keep captions outside the picture.
- Give the ending real comparison and navigation work to do.

### Don't

- Do not use blue as the default full-width chapter background.
- Do not replace the semibold neo-grotesk hierarchy with ultra-light type or all-cap headings.
- Do not turn every media panel into a shadowed floating card.
- Do not apply the green marker palette to ordinary product launches.
- Do not make all comparison tiles text-only; alternate numbers with object or mechanism proof.
- Do not enlarge purchase pills to match the scale of the 80px promise.
- Do not give every paragraph a separate card; use broad unboxed narrative lockups.
- Do not flatten all page types into a uniform three-column feature grid.

## Motion and responsive

### Motion

**Observed:**

- Gallery controls declare background, color and opacity transitions at 100ms linear.
- White feature cards declare transform 0.3s cubic-bezier(0,0,0.5,1) and background-color 0.344s ease.
- The performance headline declares one gradient-swipe animation lasting 3.5s linear.
- Floating local navigation declares transform 0.23s; media sequences use play/pause or replay controls.

**Transfer:**

- Use a single luminous sweep for a technical reveal rather than an endlessly moving gradient.
- Keep pause/replay controls part of cinematic media, and maintain a composed static stage when motion is absent.

**Unknown:**

- Exact scroll choreography, video durations and most scene easing are not established.

### Responsive

**Observed:**

- Width rules include 734/735px and 1068/1069px boundaries; only the desktop compositions are established.

**Transfer:**

- Recommended adaptation: stack the opening action platter beneath the promise, retain the full-width object silhouette and keep the dimensional word art behind it.
- Recommended adaptation: collapse paired education tiles and proof columns while preserving the next-slide peek in horizontal galleries.

**Unknown:**

- Mobile font sizes, navigation behavior and exact art direction at narrower widths are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
