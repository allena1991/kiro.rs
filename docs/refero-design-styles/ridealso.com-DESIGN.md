# ALSO — mechanical wonder playground

## Overview

A cinematic, tactile style where serious engineering meets playful possibility. Regular grotesk headlines and condensed equipment-like labels sit among natural-light photography, enormous studio renders and black theatrical stages. Purple, pale gray and dusty blue alternate with warm cream; the density is low at chapter level and compact inside controls and cards.

### Essentials

- The product owns the opening, not the headline: a full-width 704px moving-image stage, 96px regular grotesk title at lower left and a 56px purple action at lower right.
- Headlines feel spoken while labels feel stamped: ABCCameraPlainVariable at weight 400, 60px/0.93 with -0.05em tracking for chapter leads; Serial C at weight 900, 16px/1.5 in capitals for actions and short explanations.
- Controls have a pressed-plastic edge: pill silhouettes, 1px dark outlines and a hard 2px purple underside rather than floating soft shadows.
- Color arrives in chapters, not everywhere: black and pale-gray stages carry most of the product story; dusty blue backs a lifestyle chapter, purple anchors actions and the closing band, and orange is confined to the 32px announcement strip.
- Technical detail is made physical: square 443px close-up media with 24px corners, white capital captions on black, and oversized isolated products on #f0f0f0. Use detailed interface or material close-ups when a product has no physical object.
- Wonder has a visual device: include a luminous circular detail on black or a scattered field of small feature symbols around a 60px headline; simplified SVG symbols and a CSS halo are the minimum equivalent.
- The ending is monumental: a 244px purple invitation band leads into a 914px dark-purple, black-flecked footer with lavender links and a full-width wordmark sculpture about 1360px × 335px. Use the new identity as artwork, not a small repeated logo.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bright amethyst | `#c181ff` | `--color-hero-action` | action | Default conversion pill over opening media. |
| Amethyst | `#ac74fc` | `--color-purple` | background, action, link, accent | Core brand color: closing invitation band, feature accent, footer links and exploratory controls. |
| Purple underside | `#381b5e` | `--color-button-edge` | border | Hard 2px lower shadow on outlined pills. |
| Deep purple | `#361a5b` | `--color-footer` | background | Textured monumental closing footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement orange | `#f88427` | `--color-orange` | background | Thin animated promotional strip; not a general section fill. |
| Violet halo | `#9d6ae5` | `--color-halo` | accent | Soft light around the circular detail on black. |
| Dusty blue | `#a6b8c6` | `--color-dusty-blue` | background | Lifestyle and adaptability feature chapter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-black` | background, text | Default theatrical feature stages and dark stat tiles. |
| Chrome ink | `#0b0b0b` | `--color-ink` | text, border | Light-surface text and fine button outlines. |
| Charcoal | `#1f1f1f` | `--color-charcoal` | text, border, surface | Dark body text, media edges and dark commerce actions. |
| Control housing | `#333333` | `--color-control` | surface | Capsule enclosing carousel arrows and pagination. |
| Caption gray | `#ababab` | `--color-caption` | text | Small explanations below feature imagery on black. |
| Soft white | `#cccccc` | `--color-muted` | text | Paragraphs accompanying white headlines on black. |
| Studio gray | `#f0f0f0` | `--color-canvas` | background, surface | Primary light product stage. |
| Technical gray | `#f1f1f1` | `--color-spec-canvas` | background | Dimensions and technical proof stages. |
| Pale lilac | `#f7f1ff` | `--color-lilac` | surface | Information cards and inactive carousel dots. |
| White | `#ffffff` | `--color-white` | text, surface, action | Headlines on media and black; white cards and secondary pills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and recruiting narratives | Electric blue | `#5e74ff` | `--color-electric-blue` | background | Recruiting chapter behind white text and black location panels. |
| event campaigns | Bright lime | `#b1ff8f` | `--color-lime` | surface, action | Inset signup invitation panel. |
| company narratives | Violet paper | `#f6f1f7` | `--color-company-paper` | background | Product-family composition and narrative text. |
| catalogs and event directories | Warm cream | `#fff5ec` | `--color-cream` | background | Commerce and practical information canvas. |

## Typography

- **ABCCameraPlainVariable** — Headlines, paragraphs, stat values and product names. Unembellished regular grotesk with compact, tightly joined display settings. If unavailable, use **Inter**. Use weight 400 and retain tight negative tracking. Font stack: "ABCCameraPlainVariable", "Inter", Arial, sans-serif.
- **Serial C** — Uppercase navigation, actions, specification labels and short benefit captions. Narrow, utilitarian lettering with a typewriter-like industrial rhythm; declared black weight but visually fine condensed strokes. If unavailable, use **Roboto Mono**. Use condensed letter proportions where possible; preserve short lines and capitals. Font stack: "Serial C", "Roboto Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ABCCameraPlainVariable | 400 | 96px | 0.91 | -0.052em | Short product identifier in the opening; category title variant is centered over media. |
| chapter | ABCCameraPlainVariable | 400 | 60px | 0.93 | -0.05em | Major feature promises and closing comparison headline. |
| heading | ABCCameraPlainVariable | 400 | 44px | 1.09 | -0.045em | Invitation bands, editorial section headings and company narrative chapters. |
| subheading | ABCCameraPlainVariable | 400 | 32px | 1.12 | -0.047em | Comparison names, footer category links and information-card titles. |
| small-heading | ABCCameraPlainVariable | 400 | 20px | 1.2 | -0.025em | Compact stat values, footer group titles and commerce names. |
| body | ABCCameraPlainVariable | 400 | 16px | 1.5 | -0.015625em | Paragraphs beneath chapter headlines and invitation support. |
| action | Serial C | 900 | 16px | 1.5 | normal, uppercase | Buttons, opening support line and centered feature captions. |
| navigation | Serial C | 900 | 16px | 1.25 | 0.0625em, uppercase | Primary navigation over opening imagery. |
| footer-link | Serial C | 900 | 16px | 1.5 | 0.0625em, uppercase | Secondary footer navigation. |
| caption | ABCCameraPlainVariable | 400 | 14px | 1.42 | normal | Detailed feature explanations below short uppercase titles. |
| technical-label | Serial C | 900 | 14px | 1.42 | 0.036em, uppercase | Compact support text, prices and performance summaries. |
| stat-label | Serial C | 900 | 12px | 1.3 | 0.083em, uppercase | Labels under stat values. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and event pages | editorial-display | ABCCameraPlainVariable | 400 | 72px | 0.94 | -0.055em | Centered title over a documentary photograph. |
| news and story collections | story-title | ABCCameraPlainVariable | 400 | 24px | 1.16 | -0.042em | Multi-line editorial card headlines. |

**Notes:**

- Keep all grotesk headings at 400; contrast comes from scale, case and spacing, not heavier heading weights.
- Display tracking tightens to roughly -0.05em, while body tracking relaxes and equipment labels use normal or positive spacing.
- Wordmark artwork is a separate oversized graphic, not an additional heading font or a substitute for the 96px opening title.

## Layout

**Density:** Airy cinematic chapters with compact equipment-like labels and controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Stat tile gaps, pagination housing padding and stacked category-link gaps. |
| 12px | Icon-to-label button gap and compact directory gutters. |
| 16px | Media grid gutters, paragraph gaps and commerce-card inner inset. |
| 20px | Editorial and directory card padding; outer header inset. |
| 24px | Medium button horizontal padding and commerce-card bottom padding. |
| 32px | Large button horizontal padding and grouped proof-block spacing. |
| 40px | Primary desktop section side inset. |
| 56px | Opening bottom inset and smaller section breathing room. |
| 64px | Footer navigation top inset. |
| 80px | Default major section top/bottom padding and footer graphic separation. |
| 96px | Extra breathing room below centered proof introduction. |
| 144px | Wide separation between text and circular product detail. |

### Containers and grids

- **wide stage**: max width 1920px · side padding 0px. Full-bleed photographs and product scenes; do not put them inside a conventional centered text container.
- **content frame**: max width 1400px · side padding 40px. Wide feature rows and footer navigation; at desktop, content commonly spans 1360px.
- **feature trio**: 3 columns · gap 16px · side padding 40px. Three equal media-first columns, each about 443px wide; carousels can reveal a clipped next card.
- **detail pair**: 2 columns · gap 144px. Two 480px regions: left narrative and right circular detail, centered in the stage.
- **text measure**: max width 560px · side padding 20px. Centered proof headline and support; split chapters use a 480px paragraph width.
- **closing comparison**: 2 columns · gap 16px · side padding 40px. Paired product choices about 672px wide on a black stage.
- **catalog** (only for catalog pages): 3 columns · gap 16px · side padding 20px. 260px filter rail separated by 32px from a three-column product grid.

## Corner radius

| Element | Radius |
| --- | --- |
| pills | 9999px (pill) |
| feature media | 24px |
| commerce and editorial cards | 16px |
| stat tiles | 8px |
| circular detail | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| button underside | `0px 2px 0px 0px #381b5e` | Outlined action pills. |
| soft card | `0px 1px 2px 0px rgba(0, 0, 0, 0.08)` | White editorial and commerce cards. |
| detail halo | `0px 0px 100px 8px #9d6ae5` | Circular product detail on black. |

### Surfaces

#### Black theater · level 0

**Use:** Default feature and technology canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Large uninterrupted dark fields carry isolated objects, white headlines and muted explanations.

**Transfer:** Group closely related capabilities into one dark chapter rather than making every row a separate card.

#### Studio floor · level 0

**Use:** Isolated product and quantified proof stages.

**CSS:** `background: #f0f0f0; color: #000000`

**Observed:** Render backgrounds merge into the page; technical dimensions use #f1f1f1.

**Transfer:** Match the image backing to the section so there is no visible rectangular image boundary.

#### Blue lifestyle band · level 0

**Use:** Human use-case and adaptability chapter.

**CSS:** `background: #a6b8c6; color: #1f1f1f`

**Observed:** Dusty-blue field surrounds portrait photography and dark small captions.

**Transfer:** Use one flat muted-color stage as relief from black technology scenes.

#### Purple invitation · level 0

**Use:** Closing relationship-building call.

**CSS:** `background: #ac74fc; color: #1f1f1f`

**Observed:** A full-width band with simple left-aligned headline and one short support line.

**Transfer:** Give a short ongoing-value invitation its own color band.

#### White card · level 1

**Use:** Commerce and editorial groupings.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.08)`

**Observed:** The rounded outer container is distinct from the tighter inset image frame.

**Transfer:** Keep shadow almost imperceptible; let backing color and corners establish the object.

#### Flecked purple footer · level 0

**Use:** Monumental end of every page.

**CSS:** `background-color: #361a5b; color: #ac74fc`

**Observed:** Dense tiny irregular black chips cover the purple substrate behind navigation and an enormous flat lavender wordmark.

**Transfer:** Use a repeating irregular fleck texture and the new identity rendered as a full-width flat vector.

#### Warm directory canvas · level 0

**Only for:** catalogs and event directories

**Use:** Practical browse-oriented content.

**CSS:** `background: #fff5ec; color: #0b0b0b`

**Observed:** Warm cream backs white merchandise cards or pastel directory panels.

**Transfer:** Preserve the warmer browse variant rather than making it the default technical stage.

## Components

### Overlay navigation

**Use:** Top-level orientation on immersive media.

**CSS:** `display: flex; padding: 0px 15px; border-radius: 16px; color: #ffffff; max-width: 1920px`

**Text style:** `navigation` — Serial C 900 · 16px/1.25 · tracking 0.0625em · uppercase

**Observed:** Identity sits left; four widely spaced navigation groups occupy the center; a compact white pill and outline shopping/account icons sit right. The shell is inset 20px and is transparent over the opening.

**Transfer:** Keep navigation visually subordinate to the scene, with an alternate dark-text treatment only where contrast requires it.

### Primary button

**Use:** Main conversion action over opening media.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; background: #c181ff; color: #000000; padding: 16px 32px; height: 56px; border-radius: 9999px; outline: 1px solid #0b0b0b; outline-offset: -1px; box-shadow: 0px 2px 0px 0px #381b5e`

**Text style:** `action` — Serial C 900 · 16px/1.5 · uppercase

**Observed:** Text is centered in a compact outlined capsule; its dark underside makes the control feel tangible.

**States:** Declared: hover not specified; focus-visible not specified; active transform translateY(2px).

### Secondary button

**Use:** Neutral action on photographs, cards or information bands.

**CSS:** `background: #ffffff; color: #0b0b0b; padding: 12px 24px; height: 48px; border-radius: 9999px; outline: 1px solid #0b0b0b; outline-offset: -1px; box-shadow: 0px 2px 0px 0px #381b5e`

**Text style:** `action` — Serial C 900 · 16px/1.5 · uppercase

**Observed:** The same chrome also appears as a 40px small control with 8px 20px padding and a 56px large control with 16px 32px padding.

**States:** Declared: hover not specified; focus-visible not specified; active transform translateY(2px).

### Stat tile

**Use:** Compact quantified proof under a centered promise.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 16px; background: #000000; color: #ffffff; border-radius: 8px; width: 170px; height: 80px`

**Text style:** `small-heading` — ABCCameraPlainVariable 400 · 20px/1.2 · tracking -0.025em

**Observed:** Four tiles in a row with 8px gaps. Value and small supporting icon share the upper line; a stat-label sits below. Values are only 20px, not oversized numerals.

**Transfer:** Use short comparable metrics; reserve the larger scale for the headline above.

### Feature media frame

**Use:** Product close-ups and human use-case panels.

**CSS:** `overflow: hidden; border: 1px solid #1f1f1f; border-radius: 24px`

**Observed:** Square close-ups are about 443px wide; lifestyle variants are portrait 443px × 553px. Captions remain outside the image frame, directly on the section backing.

**Transfer:** Separate tactile detail images from their explanations; do not wrap the whole feature in white chrome.

### Carousel dock

**Use:** Small centered navigation beneath dark media rows.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; padding: 8px; background: #333333; border-radius: 9999px; margin-top: 32px; margin-bottom: 32px`

**Observed:** Two 48px white circular arrows enclose small pale dots; selected pagination is a dark square rather than another outlined circle. Inactive previous arrow is at opacity 0.6.

**Transfer:** Keep the dock much narrower than the imagery; use a visible next-card edge to signal horizontal continuation.

### Footer link

**Use:** Secondary navigation on textured purple.

**CSS:** `color: #ac74fc; padding: 0px`

**Text style:** `footer-link` — Serial C 900 · 16px/1.5 · tracking 0.0625em · uppercase

**Observed:** Small uppercase links stack at 16px gaps below regular 20px group labels. Larger 32px category links occupy the left half.

**States:** Declared: hover color #ffffff; focus-visible not specified; active not specified.

### Commerce card

**Only for:** catalog pages

**Use:** Product browsing and quick actions.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.08); display: flex; flex-direction: column`

**Text style:** `small-heading` — ABCCameraPlainVariable 400 · 20px/1.2 · tracking -0.025em

**Observed:** A 359px × 543px card contains a 327px square studio image, regular product title, compact uppercase color and price line, circular color options, then paired white Explore and charcoal Quick Add pills. Inner content has 16px inset and 24px bottom padding.

**Transfer:** Use the pair of equal actions only when immediate purchase and product education are both useful.

### Story card

**Only for:** news and story collections

**Use:** Editorial proof on a dark backing.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #ffffff; padding: 20px; border-radius: 16px; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.08)`

**Text style:** `story-title` — ABCCameraPlainVariable 400 · 24px/1.16 · tracking -0.042em

**Observed:** Four 332px × 443px cards form a horizontal row; each starts with a 292px × 219px image, then a multi-line black headline and bottom-aligned black Read More pill.

### Directory card

**Only for:** event and location directories

**Use:** Practical location information with documentary image.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 20px; padding: 20px; background: #ac74fc; border-radius: 16px`

**Text style:** `subheading` — ABCCameraPlainVariable 400 · 32px/1.12 · tracking -0.047em

**Observed:** Three 451px × 601px panels sit in a row with 12px gaps. Category chip, place name and underlined address sit at top; landscape architecture photo sits low with an 8px radius and fine dark edge. Pale lilac and pale green variants distinguish partner groups.

**Transfer:** Group records by meaningful category instead of assigning a new color to every record.

## Imagery and graphics

### Documentary motion

**Use:** Opening and full-bleed breathing spaces between technical chapters.

**Observed:** Natural sunlight, warm skin and stone, desaturated green woodland, urban streets and real people using the product. Moving subjects are allowed to blur; close framing often cuts off wheels or bodies. The first scene fills the width rather than sitting beside text.

**Transfer:** Shoot the new product in real use, including a tight functional detail in motion. Without video, use a single cinematic photo with deliberate foreground/background depth.

### Studio engineering renders

**Use:** Oversized product reveals, detail strips and comparison choices.

**Observed:** Neutral ivory and black materials, translucent housings, subtle purple hardware, soft broad light and almost-white gray backings. Hero objects take most of the frame; macro views expose joints, interfaces and charging parts.

**Transfer:** Render or photograph the actual product with soft shadows and matched gray floor. A clean isolated image plus two real material close-ups is preferable to an unrelated decorative 3D object.

### Luminous circular detail

**Use:** Signature technology demonstration on black.

**Observed:** A 480px circular interface detail floats to the right of a short headline and paragraph. The crisp light disk is surrounded by a diffuse violet aura, not a hard ring.

**Transfer:** Show one meaningful control, diagram or functional detail in a circular mask; keep the surrounding stage truly black.

**Build:** Use a 480px square with border-radius:50%, overflow:hidden and box-shadow:0px 0px 100px 8px #9d6ae5. Place a high-contrast detail inside; do not blur its content.

### Orbiting feature symbols

**Use:** Playful promise chapter within the dark technical story.

**Observed:** Small illustrated route maps, badges, progress rings and tiny controls scatter at mixed rotations around centered white text with a purple changing final line. Peripheral symbols are darker than the center.

**Transfer:** Use the new product's capabilities as a small family of outlined illustrated symbols; maintain a broad clear text zone.

**Build:** Create 6–10 original SVG symbols from rounded rectangles, circles, simple paths and short labels. Repeat 20–30 instances at 48px–120px sizes around the outer two thirds of a black stage, rotate between -30deg and 30deg, lower peripheral opacity, and put the 60px white headline above them with one purple line.

### Fleck texture and word sculpture

**Use:** Signature closing identity field.

**Observed:** Black irregular chips and specks interrupt a deep-purple field. An enormous lavender vector wordmark anchors the bottom, with dense letterforms and generous clear space above.

**Transfer:** Render the new brand name as a wide, heavy vector or tightly fitted bold sans word sculpture; keep it flat and unlit.

**Build:** Tile an SVG pattern about 360px square containing many irregular black polygons 1px–6px wide at varied rotations and spacing over #361a5b. Keep texture small and non-gridlike. Layer navigation and a full-width #ac74fc wordmark above it; allow about 80px separation before the 335px-high identity graphic.

### Engineering line landscape

**Only for:** company narratives

**Use:** Vision and engineering-platform chapter.

**Observed:** An exploded mechanical assembly becomes a full-bleed line drawing in pale violet over a deep-to-light purple vertical field. Centered white prose is surrounded by fine detailed gears, shafts and housings.

**Transfer:** Use a real system diagram relevant to the new organization, not stock circuit-board art.

**Build:** Export fine outlined paths from a product diagram, enlarge them beyond the section edges, and draw in rgba(172,116,252,0.6) over a vertical gradient from #361a5b to #ac74fc. Keep text in a centered clear measure.

### Icons

**Observed:** Navigation and social icons are 24px outline SVGs with 1.5px rounded strokes; carousel arrows use 24px icons with 2px square-ended strokes. The exploratory pill uses a playful eye symbol rather than a chevron.

**Transfer:** Use sparse functional outline icons, and reserve one illustrative eye-like discovery symbol for exploratory actions rather than adding icons to every button.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product opening

**Observed:** A 32px promotional ribbon sits above a 704px edge-to-edge film. The image is a close moving functional detail, not a centered catalog silhouette. A subtle 15% black overlay sits over the media; transparent Overlay navigation sits on top. The white 96px product identifier and two-line capital support occupy the lower-left quarter with 32px side inset and 56px bottom breathing room. Primary button anchors the opposite lower edge. Within the first 900px the entire film, navigation, support and action are visible; the pale-gray proof stage begins and its centered headline peeks in, while the stat row and large isolated object fall below.

**Transfer:** Use a short product name and a tight real-use detail film; a well-lit documentary still is the minimum fallback. Retain the asymmetric lower-edge text/action arrangement. Catalogs instead open with a centered 96px category title; company and event pages use centered 72px titles on wider documentary views; a general marketing home uses a centered 60px announcement with a white action.

**Avoid:** Do not replace the cinematic stage with a text-heavy split hero, giant abstract gradient, or isolated object floating beside a paragraph.

**Text style:** `display` — ABCCameraPlainVariable 400 · 96px/0.91 · tracking -0.052em

### Compact proof and giant object

**Observed:** Studio floor carries a centered chapter headline and compact technical-label support within a 560px measure. Four Stat tiles follow, then an exploratory purple pill. A huge softly lit isolated product sits below, extending far beyond the text measure.

**Transfer:** Pair a concise emotional promise with a few verifiable metrics, then make the object or service artifact large enough to reward inspection.

**Text style:** `chapter` — ABCCameraPlainVariable 400 · 60px/0.93 · tracking -0.05em

### Black detail carousel

**Observed:** Black theater has 80px vertical breathing room, three visible 443px square Feature media frames, 16px gutters and a clipped next panel. Centered action-style benefit captions sit outside the images. Carousel dock sits underneath.

**Transfer:** Give each panel one specific physical capability or workflow rather than a generic feature noun.

**Text style:** `action` — Serial C 900 · 16px/1.5 · uppercase

### Lifestyle capability chapter

**Observed:** Blue lifestyle band combines a centered short promise and exploratory action with a trio of portrait Feature media frames. Each has a short uppercase title followed by 14px sentence-case explanation. A full-width documentary image can extend the story without another headline.

**Transfer:** Use three human-scale situations demonstrating the same capability in different contexts, preserving the muted-blue backing.

**Text style:** `caption` — ABCCameraPlainVariable 400 · 14px/1.42

### Luminous split demonstration

**Observed:** Black theater pairs a 480px narrative region on the left and Luminous circular detail on the right with a 144px gap. The 60px headline wraps into two short lines; muted 16px prose follows with a 16px gap. A Carousel dock controls alternate demonstrations below.

**Transfer:** Give one important control or feature this focused treatment rather than showing a dashboard wall.

**Text style:** `chapter` — ABCCameraPlainVariable 400 · 60px/0.93 · tracking -0.05em

### Technical reassurance

**Observed:** Technical gray stage places a large side-on product illustration left and a narrow specification table right. Table has a purple heading strip, white rows and a fine dark perimeter; small notes sit immediately below.

**Transfer:** Use dimensions, compatibility or a similarly practical decision aid at the same modest density; keep the visual explanation dominant.

### Paired closing choice

**Observed:** Black theater introduces a centered 60px closing line above two large pale-gray product scenes, each with upper-left 32px name, upper-right compact performance/price labels and lower-left white order pill.

**Transfer:** Close with two meaningful versions or paths to action; preserve the image-led comparison rather than introducing a dense pricing matrix.

**Text style:** `chapter` — ABCCameraPlainVariable 400 · 60px/0.93 · tracking -0.05em

### Invitation and monumental footer

**Observed:** Purple invitation is 244px high with 80px vertical padding and a left-aligned 44px headline above a short body line. Flecked purple footer follows with 64px top and 40px side padding. Large category links fill the left half; three small navigation groups and social/legal row occupy the right. An 80px separation precedes a 1360px × 335px word sculpture; bottom padding is 24px.

**Transfer:** Always preserve the textured identity ending and oversized word sculpture. Adapt the invitation and navigation taxonomy to the new product; a working subscription control can occupy the spare invitation area.

**Text style:** `heading` — ABCCameraPlainVariable 400 · 44px/1.09 · tracking -0.045em

### Browse grid

**Only for:** catalog pages

**Observed:** Warm directory canvas supports the Catalog layout with sticky-looking stacked filters and White cards. Product imagery is neutral studio work; a full-photo promotional card interrupts the grid. A four-card recommendation row appears before the common closing.

**Transfer:** Keep browsing utilitarian and dense inside cards without flattening the cinematic opening into a store toolbar.

### Colored directory

**Only for:** event and location directories

**Observed:** Cream selection region contains a matrix of 256px × 56px city pills and a campaign image. A bright-lime inset invitation precedes a purple three-photo expectation chapter. Partner identity bands introduce Directory cards on black or cream.

**Transfer:** Use this structure for destinations, availability or service networks, with category chips and architecture photography rather than fabricated decorative maps.

### Company narrative landscape

**Only for:** company narratives

**Observed:** A documentary title image yields to a pale-violet product-family lineup and centered prose. Engineering line landscape and a light partner-logo field give way to full-bleed workshop photography, an electric-blue recruiting invitation, and three black information panels before the shared ending.

**Transfer:** Tell origin, platform, external support and participation stories using original diagrams and real working environments; keep these editorial treatments scoped to organizational storytelling.

**Text style:** `heading` — ABCCameraPlainVariable 400 · 44px/1.09 · tracking -0.045em

## Page flow

**Storyline:** Immersive promise → tangible product proof → capability and human-use chapters → practical reassurance or participation → conversion choices → ongoing relationship and monumental identity.

### Flagship product landing page

1. **Promise** — Close functional film with lower-edge name, short commercial context and purple conversion pill.
2. **Quantified proof** — Centered emotional line, four small black metrics and enormous studio product.
3. **Capability chapters** — Black macro carousel, full-bleed use film, blue-backed adaptability portraits, playful symbol field and luminous interface demonstration.
4. **Practical reassurance** — App capabilities, documentary return to use and a dimensions diagram.
5. **Closing conversion** — Paired versions on pale studio fields, then purple invitation and textured identity footer.

**Transfer:** Choose a few product truths and alternate evidence at object, human and system scales; do not reproduce the original section count.

### Broad brand marketing home

1. **Current promise** — Centered shipping announcement over documentary product photography.
2. **Paths to engagement** — Three square image-led calls to explore, configure or experience.
3. **Social proof** — Vertical social-media strip and purple press carousel.
4. **Range and credibility** — Full-width adjacent-product scene followed by white editorial Story cards on charcoal.
5. **Relationship** — Shared purple invitation and monumental textured footer.

**Transfer:** Use a current concrete announcement and a small number of visual paths rather than summarizing every feature.

### Merchandise catalog

1. **Category identity** — Centered white category name over lifestyle photography.
2. **Browse and choose** — Cream canvas, narrow filters, three-column white product cards and one photo promotion.
3. **Cross-sell** — Four-card recommendation carousel.
4. **Relationship** — Shared invitation and textured identity ending.

**Transfer:** Reuse the brand's material and type hierarchy while letting functional product browsing remain compact.

### Event and location discovery

1. **Invitation** — Centered title on close documentary photography.
2. **Find relevance** — City selection pills and lime signup panel.
3. **Set expectations** — Purple field with three human encounter photographs and capital captions.
4. **Practical proof** — Partner identity bands, large featured location and three-column pastel Directory cards.
5. **Relationship** — Shared invitation and identity footer.

**Transfer:** Lead with action relevance, explain what the encounter offers, then provide structured practical details.

### Company narrative and participation

1. **Identity** — Centered title on an urban scene.
2. **Explain purpose** — Product-family lineup, short statement and centered multi-paragraph introduction.
3. **Platform and confidence** — Violet engineering landscape and cream partner field.
4. **Participation** — Workshop photograph, blue recruiting call and black office panels.
5. **Relationship** — Shared invitation and monumental footer.

**Transfer:** Balance the organization's larger vision with visible craft, real environments and one clear participation action.

## Writing

Confident engineering with a disarming sense of delight. Short promises sound conversational; supporting copy earns that optimism with specific mechanisms and everyday consequences.

**Do not copy:** Do not reuse ALSO's identity, wordmark, model names, coined platform names, partner logos, price/range/performance claims, awards, funding claims or quotations. Source examples illustrate tone only; write original, substantiated content for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the builders and our for the shared project. Product names appear plainly rather than as repeated slogans.
- **Rhythm:** Headlines are usually two to five words, often sentence case with a period. Capitalized equipment captions compress one idea into one or two short lines; body explanations expand to one or two direct sentences.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Chapter promise | Short familiar expression made relevant by nearby proof. | 2–5 words | “Pinch yourself.”<br>“Your mission control.” |
| Capability caption | Start with an action, then name the mechanism and useful result. | 12–22 words | “Swap one top frame for another in under three seconds.” |
| Supporting explanation | Explain a feature through a human-scale action rather than a list of abstract benefits. | 1–2 sentences | “Just roll up, and stroll away. Your TM-B locks when your phone leaves Bluetooth range, and unlocks in the same way when you return.” |
| Primary action | Direct verb plus object only when necessary. | 1–5 words | “Order Now”<br>“Explore Jobs”<br>“Schedule a Test Spin” |
| Closing invitation | Warm idiom, then simple low-commitment instruction. | 3–5 words per line | “Stay in the loop.”<br>“Join our mailing list.” |

**Words and phrasing to use:** your; built-in; swap; explore; in seconds; little; everyday; imagine; together

**Avoid:** revolutionary solution; unparalleled synergy; premium ecosystem; disruptive innovation; unlock limitless potential

**Rules:**

- Connect every playful promise to an adjacent physical, measurable or visible reason.
- Keep UI labels in capitals through styling; write prose in ordinary sentence case.
- Prefer concrete verbs and compact object names over stacked adjectives.
- Use practical conditions and qualifications where claims need them; do not let exuberant tone substitute for proof.

## Do's and Don'ts

### Do

- Keep the opening identifier at 96px and weight 400, with a short support measure.
- Use 60px/0.93 chapter leads and reserve 44px headings for secondary chapter roles.
- Preserve the hard 2px purple pill underside and 1px ink outline.
- Give feature media 24px corners while keeping captions on the section backing.
- Use 80px section breathing room and 16px media gutters as primary rhythms.
- Keep performance values at 20px above tiny capital labels in black tiles.
- Include a luminous detail or symbol constellation within the product story.
- End with the purple invitation, flecked deep-purple field and monumental new-identity artwork.

### Don't

- Do not turn the whole page purple; black and pale-gray theater should carry the product narrative.
- Do not make every action a flat rectangular block or a softly floating shadow button.
- Do not increase regular grotesk headings to bold to create hierarchy.
- Do not use huge dashboard-style stat numerals in the compact proof tiles.
- Do not put a white rounded container behind every dark-stage feature caption.
- Do not replace natural use photography with uniformly violet-tinted lifestyle pictures.
- Do not replace the footer's irregular flecks with a tidy dot grid.
- Do not promote electric-blue recruiting panels or cream browse layouts to the default product-stage treatment.

## Motion and responsive

### Motion

**Observed:**

- Outlined pill actions declare 0.2s transitions and active translateY(2px).
- Exploratory purple control declares hover #bd90fd with a 2px charcoal outline; active #c7a2fd removes the shadow and translates 2px down.
- Navigation declares color transitions of 0.35s cubic-bezier(0.4,0,0.2,1) and background-color 0.2s ease.
- Announcement strip declares an infinite linear color-fade animation; hero and use-case media include video.

**Transfer:**

- Preserve the small physical button depression rather than scaling pills on press.
- Let moving product imagery and alternate demonstrations provide spectacle while keeping navigation transitions subordinate.

**Unknown:**

- Full scroll choreography, symbol trajectories and announcement animation duration are not established.
- Focus-visible treatment is not established.

### Responsive

**Observed:**

- Desktop layout uses three-column media rows, four compact metrics and a two-column detail stage.
- Declared CSS breakpoints include 640px, 768px, 1024px, 1280px and 1440px; mobile layout behavior is not established.

**Transfer:**

- Recommended: stack text and circular detail while keeping the circle prominent and its halo inside the viewport.
- Recommended: retain horizontal swipe and visible neighboring panels for media rows rather than shrinking all three panels into unreadable columns.
- Recommended: let the closing word sculpture fit the available width and stack footer navigation groups without losing the texture field.

**Unknown:**

- Exact narrow-screen type sizes, section heights, navigation expansion and wrapping behavior are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
