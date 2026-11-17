# Analogue — objects before words

## Overview

A museum-like product presentation that makes engineered objects feel collectible and consequential. Black, white and cool grey alternate in expansive chapters, with geometric sans-serif text and unusually restrained interface furniture. Monumental studio renders, close material studies and occasional monochrome working photographs carry more of the story than the copy. It suits beautifully made hardware and visually demonstrable products with real technical depth.

### Essentials

- The object is the opening headline: a full-width dark stage, two staggered product views filling roughly the central 60% of the width, and a 78px navigation band; the verbal introduction arrives below the first 900px.
- Headings speak at human scale beside monumental pictures: regular 35.3px/1 section headings and grey 26.5px/1.1 support copy, both with normal tracking; the introduction uses weight 500 rather than inflated display type.
- Controls behave like small equipment markings: white or black fully rounded pills with 8.9px vertical and 17.7px horizontal padding, not oversized rectangular conversion banners.
- Color belongs to the object, not the interface: black, white and neutral grey occupy the page furniture throughout; saturated screens, finishes and carefully lit product scenes supply the chromatic emphasis.
- Photography is an argument about construction: include an oversized full-object stage and a macro or orthographic detail study, backed by black or seamless grey. For a nonphysical product, stage a tangible output or sharply framed interface in the same two scales.
- Narrative breathing room is architectural: centered feature chapters use 223.3px top and bottom padding at desktop, intercut with edge-to-edge media rather than boxed feature dashboards.
- Technical credibility becomes an image: include a fine-line construction drawing or equivalent structural diagram on black, supported by compact three-column specifications; simple original SVG outlines are the minimum equivalent.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, action, border | Primary dark-stage text, white feature chapters and light conversion pills. |
| Soft white | `#f4f4f4` | `--color-button-text` | text | Text on black product-story buttons. |
| Newsletter hairline | `#e5e7eb` | `--color-rule` | border | Fine bottom rule beneath the email form. |
| Technical silver | `#e1e2e2` | `--color-technical-panel` | surface | Broad inset panel for an engineering story and internal component imagery. |
| Gallery grey | `#dddddd` | `--color-gallery` | surface | Tall orthographic detail plate. |
| Accessory grey | `#dadada` | `--color-accessory` | surface | Square accessory imagery backing. |
| Introductory silver | `#b3b3b3` | `--color-intro` | text | Large weight-500 introduction beneath the opening scene. |
| Feature grey | `#8a8a8a` | `--color-support` | text | Default explanatory paragraphs on both white and black. |
| Secondary gallery grey | `#828282` | `--color-gallery-secondary` | surface | Smaller supporting views below the tall plate. |
| Engineering grey | `#7a7a7a` | `--color-engineering-text` | text | Smaller editorial explanations inside the engineering inset. |
| Detail grey | `#797979` | `--color-detail-text` | text | Accessory-card explanations. |
| Near-black stage | `#0d0e10` | `--color-stage` | background | Opening product stage and its introductory continuation. |
| Black | `#000000` | `--color-black` | background, text, action | Default product-page canvas, ink on light chapters and inverse buttons. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| edition and collaboration galleries | Edition paper | `#f9f9f9` | `--color-catalog-paper` | background | Light campaign gallery canvas. |
| multi-product catalogues | Violet product stage | `#6a69d1` | `--color-catalog-purple` | background | One full-bleed product-family tile, with white labels; not a site-wide action color. |
| multi-product promotional pages | Launch stage grey | `#eaeaea` | `--color-launch-grey` | surface | Seamless grey promotional stage. |

## Typography

- **circularXx** — All marketing text, from section headings to navigation and specifications. Rounded geometric sans with open counters and a friendly but technical cadence; mostly regular with medium emphasis. OpenType features: "ss08". If unavailable, use **DM Sans**. Use 400, 450 and 500; preserve regular heading weight and compact line spacing. Font stack: "circularXx", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading | circularXx | 400 | 35.3px | 1 | normal | size clamp(24px, 2.449vw, 100px) | Default centered capability heading and final product-price statement. |
| intro | circularXx | 500 | 35.3px | 1 | normal | size clamp(24px, 2.449vw, 100px) | Product introduction headline and its large silver descriptive block. |
| technical-heading | circularXx | 500 | 35.3px | 1.5 | normal | size clamp(24px, 2.449vw, 100px) | Title above the engineering drawing and specification columns. |
| support | circularXx | 400 | 26.5px | 1.1 | normal | size clamp(18px, 1.837vw, 100px) | Centered feature explanations beneath section headings. |
| feature-card-heading | circularXx | 400 | 26.5px | 1 | normal | size clamp(18px, 1.837vw, 100px) | Three-column capability-card titles on black. |
| card-heading | circularXx | 400 | 20.6px | 1 | normal | size clamp(14px, 1.429vw, 100px) | Left-aligned accessory titles. |
| technical-label | circularXx | 400 | 20.6px | 1.5 | normal | size clamp(14px, 1.429vw, 100px) | Specification column labels and small engineering-panel paragraphs. |
| card-body | circularXx | 400 | 19.1px | 1.2 | normal | size clamp(13px, 1.326vw, 100px) | Accessory explanations. |
| technical-body | circularXx | 400 | 17.6px | 1.5 | normal | fixed | Bullet-list specifications. |
| button | circularXx | 400 | 16px | 1 | normal | fixed | Product-story action pills. |
| purchase-button | circularXx | 400 | 14.7px | 1 | normal | fixed | Compact final availability action. |
| navigation | circularXx | 400 | 13.2px | 1.11 | normal | size clamp(9px, 0.918vw, 100px) | Small stacked navigation links. |
| caption | circularXx | 400 | 13.2px | 1.5 | normal | size clamp(9px, 0.918vw, 100px) | Footer copy, newsletter controls and gallery-view captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| multi-product promotional pages | campaign-display | circularXx | 500 | 52.9px | 1.11 | -0.05em | size clamp(36px, 3.673vw, 100px), tracking -0.183673vw | Large centered promotional promise or closing statement. |
| press-review rails | review-score | circularXx | 500 | 35.3px | 1 | -1.2px | size clamp(24px, 2.449vw, 100px), tracking -0.0816327vw | Score at the upper-left of a review card. |
| catalogue and edition galleries | catalog-heading | circularXx | 500 | 26.5px | 1.11 | -0.7px | size clamp(18px, 1.837vw, 100px), tracking -0.0510204vw | Bottom-left product label on an image-led tile. |
| press-review rails | review-quote | circularXx | 450 | 20.6px | 1.14 | -0.6px | size clamp(14px, 1.429vw, 100px), tracking -0.0408163vw | Short quotation anchored near the bottom of a review card. |
| catalogue and edition galleries | status | circularXx | 400 | 14.7px | 1.5 | normal | size clamp(10px, 1.02vw, 100px) | Outlined availability capsule text. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default hierarchy uses weight 400 and normal tracking, not bold compressed display type. The large introduction is the deliberate weight-500 exception.
- Promotional and catalogue variants tighten tracking; do not spread their negative tracking into ordinary product-story paragraphs.
- Use sentence case. Superscript product suffixes are small brand-lockup artwork rather than a general-purpose heading style.

## Layout

**Density:** Airy at chapter level and compact within controls: the product image has room to dominate while labels stay economical.

### Spacing

| Value | Use |
| --- | --- |
| 5.8px | Narrow separation between supporting gallery views. |
| 11.8px | Card-title to explanation spacing. |
| 17.6px | Accessory grid gaps and image-to-title spacing in compact capability cards. |
| 20.6px | Outer inset around the product detail gallery and engineering panel. |
| 26.5px | Review-card padding. |
| 29.4px | Desktop outer wrapper side padding. |
| 35.3px | Section heading to support copy and support to action. |
| 82.3px | Heading-pair to broad demonstration artwork. |
| 97px | Technical-panel lower padding and separation before specification columns. |
| 187.2px | Centered explanation to accessory or capability grid. |
| 223.3px | Top and bottom padding of major feature chapters. |

### Containers and grids

- **edge-to-edge stage**: side padding 0px. Product scenes span the full window; at desktop they are commonly 1080px tall and can exceed a viewport.
- **heading wrapper**: side padding 29.4px. Centered text occupies roughly 60–70% of the window; use a narrower paragraph inside the first technical feature to keep its lines short.
- **accessory grid**: 4 columns · gap 17.6px · side padding 72px. Four equal 311px-wide accessory columns at 1440px; image, title and paragraph align left.
- **capability grid**: 3 columns · gap 54px · side padding 101px. Three 376px-wide media-and-text columns on black.
- **technical columns**: 3 columns · gap 69.1px · side padding 144px. An 1152px-wide drawing above three 338px specification columns.
- **utility grid**: 16 columns · gap 5.9px · side padding 29.4px. Navigation and footer share a broad distributed grid: mark at left, two-line navigation groups in the middle, cart at far right.
- **catalogue grid** (only for multi-product catalogues): 2 columns · gap 0px · side padding 0px. Full-width lead tiles followed by paired 720px square tiles; edition galleries remain one full-width column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 9999px (pill) |
|  | detail gallery | 8px |
|  | accessory media | 12px |
| press-review rails | review cards | 17.6px |

## Surfaces and depth

### Surfaces

#### Black canvas · level 0

**Use:** Default long-form product page and dark feature chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black with no elevated panel shadows.

**Transfer:** Let media lighting create depth instead of UI elevation.

#### Opening stage · level 0

**Use:** Hero image and verbal introduction continuation.

**CSS:** `background: #0d0e10; color: #ffffff`

**Observed:** A near-black photographic backing merges into a matching flat introduction band. A lower image fade uses a 181deg transparent-to-near-black gradient.

**Transfer:** Match the image background to the continuation so its edge disappears.

#### White chapter · level 0

**Use:** Bright capability explanations between dark media stages.

**CSS:** `background: #ffffff; color: #000000; padding: 223.3px 0px`

**Observed:** The color switch is full width, without border, card shadow or rounded section boundary.

**Transfer:** Use the switch to distinguish an explanatory pause from an immersive object study.

#### Engineering inset · level 1

**Use:** Internal-construction story.

**CSS:** `background: #e1e2e2; color: #000000; padding-bottom: 97px`

**Observed:** Inset 20.6px from the black page; centered text above a large internal-component macro and two explanatory columns below.

**Transfer:** Use a credible cutaway, process image or structural view, not a decorative abstract blob.

#### Promotional grey stage · level 0

**Only for:** multi-product promotional pages

**Use:** Centered launch or availability scene.

**CSS:** `background: #eaeaea; color: #000000`

**Observed:** An object grouping sits on a seamless light-grey ground with photographic contact shadows.

**Transfer:** Keep the ground continuous with the image and put actions beneath the object.

## Components

### Distributed navigation

**Use:** Global wayfinding over the opening stage.

**CSS:** `position: sticky; z-index: 9999; color: #ffffff; background: transparent`

**Text style:** `navigation` — circularXx 400 · 13.2px/1.11

**Observed:** A 78px-high band places a 32×30px solid mark left, three widely separated two-link stacks across the middle and a 31×34px cart-count glyph right. Text changes to black on light gallery pages.

**States:** Declared: hover text-decoration-color var(--color-menuForeground); focus-visible not specified.

**Transfer:** Use a small original mark and a compact cart or equivalent utility; preserve the scattered editorial alignment rather than a centered link row.

### Primary pill

**Use:** Single product-story action on a dark chapter.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; background: #ffffff; color: #000000; border-radius: 9999px; padding: 8.9px 17.7px; gap: 5.9px`

**Text style:** `button` — circularXx 400 · 16px/1

**Observed:** An unadorned compact capsule, centered under support copy. On light chapters the inverse is black with soft-white text. The final purchase action uses the smaller purchase-button recipe.

**Transfer:** Keep action text short; availability and unavailable states use the same restrained construction.

### Accessory card

**Use:** Related parts, configurations or supporting capabilities.

**CSS:** `background: #dadada; border-radius: 12px; overflow: hidden`

**Text style:** `card-heading` — circularXx 400 · 20.6px/1

**Observed:** Only the media plate is painted and rounded; title and grey explanation sit outside it on the white page. Four equal columns show isolated objects at consistent scale. A black media variant uses a tiny outlined identifier at the lower left.

**Transfer:** Align all object views to the same orientation and use the card-body recipe for explanations.

### Orthographic gallery

**Use:** Slow inspection of physical construction.

**CSS:** `position: relative; background: #dddddd; border-radius: 8px`

**Text style:** `caption` — circularXx 400 · 13.2px/1.5

**Observed:** A 1399px-wide tall primary plate is followed by three equal 462×395px supporting plates, separated by 5.8px. Supporting plates use darker grey. Small view names sit in the bottom-left corner.

**Transfer:** Show side, rear and connector views rather than repeating the same hero angle.

### Newsletter line

**Use:** Footer email signup.

**CSS:** `display: inline-flex; justify-content: space-between; border-bottom: 1px solid #e5e7eb; padding-bottom: 11.8px; margin-top: 23.5px`

**Text style:** `caption` — circularXx 400 · 13.2px/1.5

**Observed:** A short invitation sits above an approximately 385px-wide line. A borderless transparent email field occupies the left and a plain Subscribe text action the right; there is no boxed input or filled button.

### Utility footer

**Use:** The final page ending.

**CSS:** `background: #000000; color: #ffffff`

**Text style:** `caption` — circularXx 400 · 13.2px/1.5

**Observed:** A compact 282px band: small mark left, two link columns in the middle, Newsletter line right. A widely separated bottom row aligns company name, rights, year and social links to those same columns. Catalogue and edition pages invert to white with black text.

**Transfer:** Keep the footer informational rather than turning it into a second giant conversion pitch.

### Catalogue tile

**Only for:** catalogue and edition galleries

**Use:** Large linked product-family or release image.

**CSS:** `display: block; position: relative; background: #000000; color: #ffffff`

**Text style:** `catalog-heading` — circularXx 500 · 26.5px/1.11 · tracking -0.7px

**Observed:** A single image occupies the tile. A bottom overlay pairs the product name left and Status capsule right, with 29.4px left and bottom padding and 36.7px right padding. No inter-tile gap or card outline.

**Transfer:** Let each family own its backing and object grouping; choose foreground contrast from the actual image.

### Status capsule

**Only for:** catalogue and edition galleries

**Use:** Availability annotation within a linked tile.

**CSS:** `display: flex; align-items: center; border: 1px solid #ffffff; border-radius: 9999px; padding: 2.9px 7.2px; color: #ffffff`

**Text style:** `status` — circularXx 400 · 14.7px/1.5

**Observed:** Outlined rather than filled, about 30px high. A black-ink version sits over light media. The whole tile is the link; the capsule is an annotation, not a separate competing button.

### Review card

**Only for:** press-review rails

**Use:** Third-party proof on a horizontal overflow rail.

**CSS:** `position: relative; width: 332px; height: 294px; padding: 26.5px; border: 1px solid rgba(255, 255, 255, 0.5); border-radius: 17.6px`

**Text style:** `review-quote` — circularXx 450 · 20.6px/1.14 · tracking -0.6px

**Observed:** Score at upper left, publication mark upper right, short quotation near the lower edge and subdued attribution beneath. Adjacent cards continue beyond both viewport edges with 17.6px gaps.

**Transfer:** Use only real attributed proof; keep generous empty space between score and quotation.

## Imagery and graphics

### Monumental studio object

**Use:** Required opening image and recurring visual proof.

**Observed:** Two sharply rendered black-and-white handheld objects stand at staggered heights in a near-black seamless space. The left object is taller and farther back; the white front object enters lower on the right. Both extend beyond the first screen. Restrained edge light describes matte plastic, glass and precise machining; the displays carry vivid color.

**Transfer:** Use original studio photography or an accurate 3D model, with a dark rear view and a lighter foreground view. If no physical object exists, place two real outputs or interface planes at staggered depth; preserve the oversized silhouette and sparse backing.

**Build:** Use a full-width near-black stage with one large transparent-background object layer on the left and a second lower layer on the right. Preserve object aspect ratios and clip the lower scene at the viewport. Add only a lower fade into the stage color; the material highlights must come from the render or photography, not CSS drop shadows.

### Macro and construction study

**Use:** Required inspection-scale counterpoint to the full object.

**Observed:** Extreme diagonal close-ups reveal a pixel grid, glossy bezel and small green hardware control; later a circuit board fills the lower edge of a silver panel with shallow focus. Orthographic gallery plates isolate a tall side silhouette and ports against flat grey.

**Transfer:** Choose the feature whose quality is visible at very close range: texture, join, display, finish or structural layer. Use an honest enlarged detail or clean original diagram if macro photography is unavailable.

### Layered demonstration planes

**Use:** Visual comparison within a bright capability chapter.

**Observed:** Several rectangular screen images are repeated as equally angled parallel planes, overlapping from left to right across nearly the full width. Pixel texture remains crisp and the white background is unadorned.

**Transfer:** Show different modes or outputs with a shared perspective, using actual content instead of unrelated decorative cards.

**Build:** Place six equal rectangular image planes in a horizontal row, apply the same skew or 3D Y rotation to each, overlap each preceding plane slightly, and align their upper edges along a rising diagonal. Keep original content color, no frame chrome and no rounded corners.

### Technical line drawing

**Use:** Required visual specification device.

**Observed:** Thin low-contrast light strokes on black show rear, side and front elevations plus supporting parts; the artwork spans 1152px above the specification columns. Dimension arrows and tiny construction labels are secondary to the silhouettes.

**Transfer:** Draw the new product's outline and a few meaningful internals or relationships. A software equivalent can show system structure or a concise flow diagram, retaining the black field and fine light lines.

**Build:** Use an SVG viewBox with aligned front, side and rear outlines. Set fill to none, strokes to white at low opacity, and stroke-width around 1px at final desktop scale. Add a few parallel dimension lines with short perpendicular terminals and small labels; do not add a blueprint grid.

### Working photograph

**Use:** A contextual chapter demonstrating a secondary workflow.

**Observed:** A full-width grainy monochrome overhead photograph shows the product physically connected to a laptop on a tactile tabletop. Cropped equipment and looping cables lead the eye; this is functional context rather than a lifestyle portrait.

**Transfer:** Photograph an authentic working arrangement in black and white, with the product legible and cables or tools forming a natural composition.

### Pixel control sculpture

**Only for:** control-system or interface chapters

**Use:** Graphic enlargement of a product's own visual language.

**Observed:** White pixel-stepped circles, letters and directional symbols form a large six-column partial grid on black. Some circles are solid and others outlined, all with deliberately stair-stepped edges.

**Transfer:** Enlarge a small coherent set of the new product's own control symbols. Keep this confined to a chapter explaining its controls rather than using retro decoration everywhere.

**Build:** Draw symbols on a small integer SVG grid, using square steps to approximate circles and diagonal edges. Scale with crisp edges into approximately 173px cells, alternate white filled and white outlined forms, use black negative-space glyphs, and space cells about 8.8px apart.

### Edition material theatre

**Only for:** edition and collaboration galleries

**Use:** Distinct release and finish presentations.

**Observed:** Transparent colored shells fan out on black with bright edge reflections; anodized objects line up tightly on pale grey; one phosphorescent green object fills an oblique shallow-focus close-up. Saturation comes from the material and scene light.

**Transfer:** Give each finish an appropriate studio treatment, preserving a common object scale and bottom-caption system. Match a luminous material's soft bloom without adding a generic page-wide neon aura.

**Build:** For luminous finishes, combine a sharply masked original object render with a second blurred silhouette layer behind it at low opacity, keeping the emission local to edges and body. Use a nearly black surrounding scene and retain a focused highlight on one plane; exact glow stops are not essential.

### Icons

**Observed:** Utility graphics are sparse, mostly solid black or white SVG: 32×30px header mark, 31×34px cart glyph and 25×23px footer mark. Gallery arrows are 12×21px, using a 0.8px butt-capped white stroke.

**Transfer:** Use simple original utility glyphs at these small scales; reserve enlarged symbolic graphics for an explanatory product chapter.

## Section recipes

How recurring sections are built.

### First screen: Object-first opening

**Observed:** Opening stage extends 1393px vertically and begins behind Distributed navigation. Back to front: near-black field, tall dark object left, lower white object right, sparse white utility navigation above. The paired objects occupy roughly the central 60% of the width, leaving black air at both sides; their bottoms run below the fold. Within the first 900px there is navigation and product imagery only: no verbal headline, support line or conversion action. The intro headline uses intro at 35.3px/1, but belongs below this first screen, followed by the silver introduction block.

**Transfer:** Make the product itself readable before explaining it. Without a physical model, compose two compelling original outputs or interface surfaces at different depths against the dark field. Promotional pages can instead open with a split dark/light stage and paired 47px product names; catalogue and release galleries open with one large object tile whose caption and status sit at its bottom.

**Avoid:** Do not add a giant slogan across the objects, a left-copy/right-image SaaS layout, or a floating primary CTA above the fold.

**Text style:** `intro` — circularXx 500 · 35.3px/1

### Verbal introduction

**Observed:** Centered white introduction heading followed about 35.3px later by a silver paragraph in the same intro recipe. The content is approximately 834px wide within the near-black continuation and ends with 176.4px of lower breathing room.

**Transfer:** Introduce category, purpose and the distinguishing mechanism in a single concentrated block; retain the visual equality of headline and large paragraph.

**Text style:** `intro` — circularXx 500 · 35.3px/1

### Capability chapter

**Observed:** White chapter pairs heading with support copy at a 35.3px gap, centered inside the heading wrapper. Many chapters have 223.3px upper and lower padding; a visual demonstration can follow after 82.3px. Dark chapters invert the heading while retaining grey supporting text.

**Transfer:** Give each chapter one demonstrable claim and let the next large image substantiate it.

**Text style:** `heading` — circularXx 400 · 35.3px/1

### Accessory grid chapter

**Observed:** Centered heading and explanation are followed after 187.2px by four Accessory cards. Each card places its media plate first, then a left-aligned title and grey paragraph. The cards share image scale without an enclosing painted text box.

**Transfer:** Use for modules, configurations or supporting tools that merit genuine individual explanation.

**Text style:** `card-heading` — circularXx 400 · 20.6px/1

### Inspection gallery

**Observed:** Orthographic gallery is inset 20.6px within a black chapter. A very tall side view dominates, then three tightly separated rear, top and front views sit beneath it with small corner captions.

**Transfer:** Let a distinctive construction detail warrant an unusually tall image; pair it with compact contextual views.

### Engineering proof panel

**Observed:** Engineering inset combines centered heading and smaller grey explanatory text with an oversized component image; two narrow prose columns and a centered black Primary pill finish the panel.

**Transfer:** Explain how quality is achieved, using a real structure or process rather than another list of benefits.

**Text style:** `heading` — circularXx 400 · 35.3px/1

### Specification and purchase close

**Observed:** Technical line drawing sits under technical-heading, then three specification columns appear after about 97px. A centered product name and price uses heading, followed by Primary pill in its purchase-button size. A final 720px-wide paired product portrait follows; compact muted notes precede Utility footer.

**Transfer:** Move from engineering detail to a clean availability decision and one last object portrait. Include factual qualifications only where relevant.

**Text style:** `technical-heading` — circularXx 500 · 35.3px/1.5

### Distributed footer ending

**Observed:** Utility footer keeps the page's informational ending low and horizontal: four spatial anchors across 1381px, 35.3px upper padding, two middle link columns, Newsletter line at right and a separate bottom alignment row.

**Transfer:** Preserve its compact utility hierarchy after either a large purchase portrait or an image catalogue.

### Catalogue image stack

**Only for:** catalogue and edition galleries

**Observed:** Catalogue tile scenes touch edge to edge. Lead scenes are full width, commonly 882–1080px tall; secondary catalogue objects sit in paired square tiles. Edition galleries retain full-width scenes with bottom names and Status capsules through to the last release, then switch directly to the light Utility footer.

**Transfer:** Use as an image-led directory or archive rather than adding a separate editorial chapter to every item.

**Text style:** `catalog-heading` — circularXx 500 · 26.5px/1.11 · tracking -0.7px

### Proof rail and closing belief

**Only for:** multi-product promotional pages

**Observed:** Review cards form a clipped horizontal rail on black. A later centered campaign-display statement spans approximately 863px with an underlined catalogue link below; the page then resolves into the dark Utility footer. A separate 47px-high announcement ticker uses repeated short updates with about 61.7px gaps.

**Transfer:** Use the rail for authentic external proof and the closing statement for a succinct product philosophy, not a second feature list. Treat the ticker as a timely update strip rather than a permanent promotional ribbon.

**Text style:** `campaign-display` — circularXx 500 · 52.9px/1.11 · tracking -0.05em

## Page flow

**Storyline:** object encounter → concise positioning → alternating visual proof and capability explanations → construction credibility → availability decision → practical footer

### Long-form flagship product presentation

1. **Product encounter** — Immersive dark object stage without an above-fold slogan.
2. **Positioning** — Large centered introduction followed by a focused object view.
3. **Capability proof** — Alternating white heading pairs, full-width close-ups, mode demonstrations and accessory grids.
4. **Use-case expansion** — Contextual monochrome photograph, secondary workflow explanation and supporting parts.
5. **System credibility** — Capability cards, a control-symbol sculpture and an inset construction story.
6. **Technical proof** — Fine-line elevations and compact specification columns.
7. **Closing action** — Product name, price, small availability pill, last product portrait and qualifications before the dark footer.

**Transfer:** Choose chapters that have visible proof. Keep the alternation between immersive media and concise explanation without inheriting the original chapter count.

### Multi-product promotional landing

1. **Discovery** — Contrasting split scene with two named products and underlined exploration links.
2. **Availability** — Large centered product grouping, a brief stock headline and compact pill.
3. **Campaign distinction** — Special-finish or collaboration stage with minimal action text.
4. **Timely update** — Narrow repeating announcement strip.
5. **Conversion** — Seamless-grey studio object arrangement and centered buying controls.
6. **External proof** — Horizontal score-and-quotation rail.
7. **Closing belief** — Large centered statement, underlined catalogue link and dark utility footer.

**Transfer:** Let each promotion have an independent scene while navigation and controls remain consistent.

### Product-family directory

1. **Primary discovery** — Large full-width product tiles with small bottom labels.
2. **Breadth** — Additional full-width family stages followed by paired square tiles.
3. **Practical ending** — The last square product pair runs straight into a white utility footer.

**Transfer:** Prioritize image recognition and concise availability over repeated descriptive copy.

### Release and finish archive

1. **Featured release** — Two special-finish objects on a pale canvas with name and status at the bottom.
2. **Range demonstration** — Full-width material-led scenes alternate black, pale neutral and locally colored photography.
3. **Archive closure** — A last pale floating-object study and bottom status lead directly to the white utility footer.

**Transfer:** Give each release a distinct material scene while keeping image dimensions and caption behavior consistent.

## Writing

Earnest, specialist and openly enthusiastic about engineered quality. Short declarations introduce expansive capabilities, then concrete mechanisms, compatibility details and specifications supply the authority.

**Do not copy:** Do not reuse Analogue names, logos, partnerships, game artwork, proprietary product names, prices, compatibility counts, performance superlatives, publication logos or quotations as claims for another product. Replace them with original assets and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use the product's name for factual explanations, we for design intention and you or your for the user's possibilities. Avoid a constant sales-agent voice.
- **Rhythm:** Headlines are often 4–9 words and sentence case. Support copy is a compact paragraph with short emphatic fragments mixed into factual sentences. Actions are usually 2–5 words; technical lists are direct and unembellished.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Introduction | Meet the named product, then define its cultural or practical purpose. | Two short sentences | “Meet [Brand] Pocket.”<br>“A tribute to portable gaming.” |
| Capability headline | Name a specific experience or outcome, not an abstract value. | 4–9 words | “Play Pocket on the big screen.”<br>“The most advanced display in handheld gaming.” |
| Technical explanation | Lead with a design choice and support it with a specific mechanism or measurement. | One compact paragraph | “Pocket is designed around a first-in-class 3.5”, 615 ppi, LCD.” |
| Action | Literal exploration, availability or store direction. | 2–5 words | “Available now”<br>“Learn more about FPGA”<br>“Explore Now” |
| Catalogue annotation | Product or edition name paired with a plain availability phrase. | Name plus 2–3 words | “Out of Stock”<br>“Sold Out” |

**Words and phrasing to use:** designed around; engineered; original; built in; connect; explore; compatible with; purpose built; with no compromises

**Avoid:** unlock your potential; supercharge; disruptive solution; seamless magic; hurry before it's gone; revolutionary ecosystem without explanation

**Rules:**

- Pair an ambitious claim with a concrete capability or material detail in the same chapter.
- Availability is factual, not urgency theatre.
- Use short fragments to emphasize a distinction, but let technical paragraphs remain readable prose.
- Explain interfaces in terms of what the user can do; reserve detailed specifications for the technical close.

## Do's and Don'ts

### Do

- Keep the opening predominantly image-led with a 78px distributed navigation band.
- Set ordinary section headings at weight 400 with normal tracking and line height 1.
- Keep chapter explanations grey at 26.5px/1.1 and centered.
- Maintain 223.3px chapter padding at the desktop reference scale.
- Use 8px gallery corners and 12px accessory-media corners rather than one universal radius.
- Make conversion controls compact capsules with 8.9px by 17.7px padding.
- Place names and availability at opposite bottom corners of catalogue tiles.
- Include both whole-object imagery and a meaningful inspection-scale view.
- Close technical stories with a fine-line diagram and compact factual specifications.

### Don't

- Do not apply the 52.9px promotional display recipe to every product capability heading.
- Do not turn the grey supporting paragraphs into high-contrast white blocks throughout the dark chapters.
- Do not use violet as a universal button or link token; its role is a scoped catalogue backdrop.
- Do not add raised drop-shadow UI cards to the flat black and white chapter system.
- Do not wrap accessory titles and paragraphs inside the rounded image plate.
- Do not add gradient text, multicolor pill buttons or decorative badge clusters around the product.
- Do not use the pixel-stepped control graphic as the main text font or as unrelated background texture.
- Do not enlarge the footer into a billboard; retain its 282px informational desktop band.

## Motion and responsive

### Motion

**Observed:**

- Announcement marquee declares marquee-left 40s linear infinite.
- Review cards declare opacity 0.3s cubic-bezier(0, 0, .2, 1).
- Catalogue capsules declare color-related transitions at .15s cubic-bezier(.4, 0, .2, 1).
- Navigation hover reveals the underline through text-decoration-color; some promotional exploration links remove the underline on hover.

**Transfer:**

- Use continuous lateral movement only for a narrow announcement strip or a proof rail, not for all product chapters.
- Keep material studies legible at rest; do not rely on constant motion to reveal the object.

**Unknown:**

- Scroll-animation timing, hero-image animation behavior and most focus-visible or active states are not established.

### Responsive

**Observed:**

- Declared width breakpoints: 640px, 768px, 1024px, 1280px and 1536px.
- Accessory grids declare two columns before the medium breakpoint and four afterward; the supporting gallery declares one then three.
- Feature chapter vertical padding declares 25.62vw before the medium breakpoint and 15.51vw afterward.
- Catalogue grid declares one column before the medium breakpoint and two afterward; edition galleries remain one column.

**Transfer:**

- Retain the product-first opening on narrow screens, reframe the paired objects so both silhouettes remain legible instead of shrinking a complete desktop scene.
- Stack technical prose and preserve fine-line artwork at a readable width, allowing a simpler original diagram rather than microscopic labels.
- Keep heading and support relationships intact using the supplied clamped sizes.

**Unknown:**

- Exact mobile navigation, footer arrangement and image art direction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
