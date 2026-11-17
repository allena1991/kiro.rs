# Lamborghini — cinematic mechanical theatre

## Overview

A dramatic, image-led style for premium products whose form and performance deserve a theatrical reveal. Black and charcoal stages alternate with brilliant white galleries, with yellow and muted gold confined to small signals of action. Towering condensed sans-serif titles contrast with broad, matter-of-fact supporting type; photography and polished product renders carry more of the story than text.

### Essentials

- Titles feel like vertical machinery rather than conventional headlines: uppercase LamboType at 120px/110px, weight 400 and normal tracking, paired with broad 27px/37px uppercase lead-ins.
- The opening is a film poster in motion: a 900px full-bleed scene beneath a 104px fixed header, a lower-left title group, and a 72px white action aligned toward the opposite edge.
- Geometry distinguishes controls from decoration: square-ended rectangular actions use 24px padding and 24px icons; carousel arrows sit inside 72px outlined hexagons. Include the hexagonal control language on every new page.
- Color belongs to the product and the decisive action, not the canvas: broad #000000, #181818 and #ffffff fields dominate; #ffc000 and #917300 appear on selected buttons and 2px active tab rules.
- Every page needs a monumental product stage: isolate the object with directional light and a grounded contact shadow, or place it in an atmospheric full-bleed scene. If no physical object exists, stage a sharply lit device or a composed product demonstration rather than a generic illustration.
- The contrast between gallery and theatre is structural: a white, side-on product presentation uses a 900px-wide image stage; the charcoal conversion stage pushes a three-quarter object beyond the right edge while keeping the copy in the left five grid columns.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action yellow | `#ffc000` | `--color-yellow` | action, accent, border | High-priority configuration and film actions; selected dark-theme tab rule. |
| Gallery gold | `#917300` | `--color-gold` | action, border | Filled discovery action and selected tab rule on the white product gallery. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-white` | background, text, action, border | Gallery canvas, default filled action on dark media, bright controls and outlines. |
| Soft white | `#f5f5f5` | `--color-off-white` | text, surface | Large titles on dark fields; pale portrait backgrounds on organizational pages. |
| Light paragraph | `#dcdcdc` | `--color-body-light` | text, border | Longer copy on black and charcoal; light chronological rules. |
| Action hover grey | `#c4c4c4` | `--color-hover` | text, action | White-action hover fill and secondary-action hover text; technical labels. |
| Inactive grey | `#969696` | `--color-inactive` | text, border, accent | Inactive dark tabs, metric descriptions, carousel progress tracks and pale table rules. |
| Mid-grey edge | `#7d7d7d` | `--color-rule` | text, border | Hairlines, white-gallery inactive tabs and outlined hexagonal controls. |
| Gallery headline grey | `#494949` | `--color-gallery-heading` | text | Monumental headline above the white product stage. |
| Theatre charcoal | `#181818` | `--color-charcoal` | background, text, surface | Configuration and technical chapters; primary light-theme heading ink. |
| Stage black | `#000000` | `--color-black` | background, text, action | Film stages, footer and text or actions on white. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical and chronological sections | Technical edge | `#626262` | `--color-technical-rule` | text, border | Technical list separators and inactive chronology labels. |
| editorial and organizational pages | Dark paragraph | `#313131` | `--color-body-dark` | text, border | Editorial copy on light surfaces and dark chronology rules. |
| chronological sections | Muted chronology | `#ababab` | `--color-chronology-muted` | text | Unselected decade labels on dark chronology navigation. |

## Typography

- **LamboType** — All marketing text, from display titles to paragraphs and actions. A coordinated family with extremely condensed, heavy-looking display and action lettering contrasted against broad geometric supporting capitals and readable regular paragraphs. If unavailable, use **Roboto Condensed**. Use 700 for the condensed display silhouette; use the wider Roboto companion for body and broad section headings. Font stack: "LamboType", "Roboto Condensed", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | LamboType | 400 | 120px | 110px | normal, uppercase | Condensed product names, monumental gallery statements and large conversion titles. |
| banner | LamboType | 400 | 80px | 90px | normal, uppercase | Condensed title in a shallow image-backed action band. |
| section-heading | LamboType | 400 | 40px | 46px | normal, uppercase | Broad chapter labels and section header rows. |
| lead-in | LamboType | 400 | 27px | 37px | normal, uppercase | Broad supporting capitals above condensed display titles; image-card titles and ruled list headings. |
| action | LamboType | 400 | 18px | 28px | normal, uppercase | Condensed button lettering; maintain the contrast with broad tab labels. |
| body | LamboType | 400 | 18px | 28px | normal | Editorial paragraphs and centered product introductions. |
| tab-label | LamboType | 400 | 16px | 26px | normal, uppercase | Broad tab lettering, navigation destinations and breadcrumbs. |
| support | LamboType | 400 | 16px | 26px | normal | Supporting explanatory text and compact links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| long-form product and editorial pages | chapter-heading | LamboType | 400 | 54px | 64px | normal, uppercase | Broad explanatory chapter headings and split editorial feature titles. |
| technical and service chapters | feature-title | LamboType | 400 | 36px | 46px | normal, uppercase | Broad capitals inside technical and service media cards. |
| quantified product proof | metric-label | LamboType | 400 | 24px | 34px | normal | Units beside display numerals and muted explanations beneath them. |

**Notes:**

- Keep the condensed display silhouette separate from the broad section headings even though both belong to one family and declare weight 400. Do not make every text role equally narrow.
- Uppercase establishes hierarchy without added letter spacing. Body paragraphs remain sentence case.
- The display's 120px type produces roughly 84px-high visible capitals; reproduce its tall, narrow proportions rather than replacing it with a wide 120px grotesk.

## Layout

**Density:** Airy at section scale and controlled within modules: images occupy large stages, while actions and tabs align on tight repeated gaps.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Section padding and most layout-level vertical distances.

| Value | Use |
| --- | --- |
| 8px | Menu icon-to-label gap and compact control padding. |
| 16px | Short support gaps, footer link rows and technical list padding. |
| 24px | Default grid gutter, action padding and space between paired actions. |
| 32px | Tab-list breathing room and media-card horizontal inset. |
| 40px | Table row padding and technical-card vertical inset. |
| 48px | Heading-to-paragraph or action-group separation; accordion vertical padding. |
| 56px | Shallow image-band vertical padding. |
| 64px | Footer block padding. |
| 80px | Default major section top and bottom padding. |
| 160px | Space below the opening title and action composition. |

### Containers and grids

- **container**: max width 1320px · side padding 12px. Centered desktop container; at 1440px its outer edge begins at 60px and text begins at 72px. Nested row and column gutters preserve a 1296px content span.
- **three-column media**: 3 columns · gap 24px. Three 416px portrait image tiles fill the content width.
- **split editorial**: 2 columns · gap 24px. Two 636px content columns. A 526px by 600px image occupies five of twelve grid columns, while text uses six, leaving a breathing column.
- **product gallery stage**: max width 900px. Centered side-profile product presentation with neighbouring slides visible beyond the main stage.
- **technical carousel** (only for technical product stories): gap 24px. 708px by 405px technical slides are offset toward the right, showing the next slide at the viewport edge.

## Corner radius

| Element | Radius |
| --- | --- |
| actions and media | 0px |

## Surfaces and depth

### Surfaces

#### White gallery · level 0

**Use:** High-key product browsing and catalog presentation.

**CSS:** `background: #ffffff; color: #181818; box-shadow: none`

**Observed:** An open canvas, not a collection of elevated cards.

**Transfer:** Let the isolated object and grounded image shadow define the stage.

#### Charcoal theatre · level 0

**Use:** Configuration, film chapters and service content.

**CSS:** `background: #181818; color: #f5f5f5; box-shadow: none`

**Observed:** Adjacent sections often continue the same dark field without card boundaries.

**Transfer:** Use imagery, section padding and type scale to distinguish chapters.

#### Black stage · level 0

**Use:** Hero media, compact action bands and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Media can dissolve into the surrounding black, especially around lower-edge title groups.

**Transfer:** Use a black-backed composition instead of drawing a visible image container.

#### Film legibility veil

**Use:** Overlay between full-bleed media and foreground type.

**CSS:** `background: linear-gradient(180deg, rgba(0,0,0,0.2) 0%, rgba(0,0,0,0) 35%, rgba(0,0,0,0.85) 100%)`

**Observed:** The middle preserves the scene while the bottom darkens toward black; the header adds a separate charcoal-to-transparent veil.

**Transfer:** Match the image's tonal falloff so white lettering remains legible without a boxed caption.

#### Pale portrait field · level 0

**Only for:** organizational biographies

**Use:** A softer light variant for leadership features.

**CSS:** `background: #f5f5f5; color: #181818`

**Observed:** A clean portrait silhouette sits against a nearly matching pale background.

**Transfer:** Keep portraits natural and the backing neutral rather than adding decorative frames.

## Components

### Fixed navigation

**Use:** Persistent minimal site orientation.

**CSS:** `position: fixed; height: 104px; width: 100%; z-index: 1040; background-image: linear-gradient(rgb(24, 24, 24), rgba(24, 24, 24, 0))`

**Observed:** Menu and hamburger sit at left, a small standalone emblem is centered, and search sits at right. The header becomes an opaque charcoal band over the following content.

**Transfer:** Use the new identity as a compact centered mark rather than expanding into a full horizontal menu.

### White action

**Use:** Default discovery action over dark fields or imagery.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; height: 72px; padding: 24px; background: #ffffff; color: #000000; border-radius: 0px; box-sizing: border-box`

**Text style:** `action` — LamboType 400 · 18px/28px · uppercase

**Observed:** Label first, directional or purpose-specific icon last. Width follows content rather than filling the column.

**States:** Declared: hover background #c4c4c4; focus-visible outline 2px solid #1e90ff, outline-offset -1px, background #ffffff.

### Outline action

**Use:** Secondary action paired with a filled conversion button.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; height: 72px; padding: 24px; border: 1px solid #ffffff; color: #ffffff; background: transparent; border-radius: 0px; box-sizing: border-box`

**Text style:** `action` — LamboType 400 · 18px/28px · uppercase

**Observed:** Uses an envelope or other purpose-specific trailing icon. Light editorial variants invert the border and text to black.

**States:** Declared: hover border-color #c4c4c4, background #181818, color #c4c4c4; focus-visible color #ffffff, outline 2px solid #1e90ff, outline-offset -1px.

### Yellow action

**Use:** The decisive action inside a charcoal conversion stage.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; height: 72px; padding: 24px; background: #ffc000; color: #000000; border-radius: 0px; box-sizing: border-box`

**Text style:** `action` — LamboType 400 · 18px/28px · uppercase

**Observed:** Usually paired with Outline action; film chapters use the same treatment with a play symbol.

**States:** Declared: hover background #997300; focus-visible background #ffc000, outline 2px solid #1e90ff, outline-offset -1px.

### Gallery action

**Use:** Product exploration on the white gallery.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; height: 72px; padding: 24px; background: #917300; color: #ffffff; border-radius: 0px; box-sizing: border-box`

**Text style:** `action` — LamboType 400 · 18px/28px · uppercase

**Observed:** Muted gold is distinct from the bright yellow used on charcoal. Companion actions can be underline-only or unboxed.

**States:** Declared: hover background #423500; focus-visible background #917300, outline 2px solid #1e90ff, outline-offset -1px.

### Hexagon arrow

**Use:** Signature previous and next controls on galleries.

**CSS:** `width: 72px; height: 72px; padding: 24px; background: transparent; border: 0px; position: absolute`

**Observed:** A point-up six-sided SVG frame has a 1px grey outline and a small centered chevron. Disabled controls are paler; dark-image versions can use solid white backing.

**Transfer:** Draw the frame with SVG points 36,1 67,18 67,54 36,71 5,54 5,18; keep the chevron much smaller than its enclosing hexagon.

### Product tabs

**Use:** Switch between product alternatives within a stage.

**CSS:** `padding: 24px; border-bottom: 2px solid #ffc000; color: #ffffff; text-align: center; position: relative`

**Text style:** `tab-label` — LamboType 400 · 16px/26px · uppercase

**Observed:** Selected dark tabs use a yellow bottom rule; inactive tabs use grey text and a thinner grey rule. The white gallery switches selected text to black and the rule to gold. Tabs remain individual underline segments with 24px gaps, never pill backgrounds.

### Footer navigation

**Use:** Site-wide closing information and identity.

**CSS:** `display: flex; flex-wrap: wrap; padding: 64px 0px; background: #000000; color: #ffffff`

**Text style:** `tab-label` — LamboType 400 · 16px/26px · uppercase

**Observed:** Compact destination columns occupy the left two thirds, with a social icon cluster on the right. Two subsequent full-width hairline-separated information bands lead to a small centered standalone emblem. The ending is an information-rich black field, not an oversized slogan.

**Transfer:** Preserve the calm centered identity sign-off below the utility content; supply only the new product's necessary information.

### Portrait media tile

**Only for:** organizational navigation

**Use:** Image-backed destinations arranged in a three-column row.

**CSS:** `height: 600px; padding: 40px 32px; position: relative; background: #000000; color: #f5f5f5; box-sizing: border-box`

**Text style:** `lead-in` — LamboType 400 · 27px/37px · uppercase

**Observed:** A darkened full-height photograph fills each tile, broad capitals sit at its upper-left, and White action is anchored near its lower-left.

**Transfer:** Choose distinct real environments or people, not three generic decorative textures.

### Ruled action row

**Only for:** organizational resources and biographies

**Use:** Flat lists of people or downloadable resources.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 40px 0px; border-bottom: 1px solid #7d7d7d`

**Text style:** `lead-in` — LamboType 400 · 27px/37px · uppercase

**Observed:** Heading at left and an outlined action at right; biography rows add a sentence-case role beneath the heading. Rows use the page field rather than a separate card fill.

### FAQ row

**Only for:** service and support pages

**Use:** Broad question list under a segmented topic selector.

**CSS:** `padding: 48px 0px; border-bottom: 1px solid #7d7d7d; color: #f5f5f5`

**Text style:** `lead-in` — LamboType 400 · 27px/37px · uppercase

**Observed:** Uppercase question takes most of the width; a 42px outlined square containing a fine plus sits at the right. Short rows are 139px high, and longer questions wrap rather than shrink.

**Transfer:** Keep the controls visually distinct from hexagonal gallery arrows.

## Imagery and graphics

### Cinematic opening scene

**Use:** Primary first-screen backdrop.

**Observed:** A low-angle moving object crosses a track in cool blue-grey light. Directional blur and the broad road foreground create speed; the object occupies the upper-middle rather than crowding the title. A black lower fade supports white copy.

**Transfer:** Film a product in its real environment with a strong directional perspective. Without motion assets, use a single composed photograph or render with the same low viewpoint, subdued palette and dark lower foreground.

### Isolated product sculpture

**Use:** White browsing gallery and charcoal conversion stage.

**Observed:** The white version presents a precise side profile with a soft contact shadow and no enclosing frame. The dark version enlarges a front three-quarter view, cropping it at the right edge; glossy silver surfaces and bright seams stand out against charcoal.

**Transfer:** Render the new product as a complete silhouette on white and a dramatic close view on dark. For software, stage a clean device with the actual interface and retain a clear object silhouette.

**Build:** Use a transparent object image over #ffffff or #181818. Add an elliptical rgba(0,0,0,0.28) floor shadow below its base, about 70% of the object's width and 12px high with 12px blur. Keep the image itself sharp; on the dark stage allow the right third to extend beyond the viewport.

### Technical still-life

**Only for:** long-form technical product pages

**Use:** Capability films and detail carousels.

**Observed:** Mechanical assemblies float in black space or stand on dark textured flooring, lit by narrow cool highlights. Hero media is 1296px by 650px; detail slides are 708px by 405px with a partial neighbour visible.

**Transfer:** Use close-lit internals, material studies or genuine diagrams. A carefully lit still render of one mechanism is the minimum equivalent; do not substitute unrelated abstract neon art.

### Editorial documentary

**Only for:** organizational and heritage pages

**Use:** Split text-image chapters and institutional tiles.

**Observed:** Tall 526px by 600px images alternate sides: a black-and-white profile portrait, a close-up identity detail, a populated event scene, or factory architecture at dusk. Institutional tiles use darker overlays and full-bleed portrait framing.

**Transfer:** Use actual people, locations, process and artifacts with varied viewing distance. Keep image edges rectangular and avoid stock-photo collages.

### Service in context

**Only for:** connected-product and support pages

**Use:** Two large pathway tiles and smaller service cards.

**Observed:** A dashboard close-up and a hand holding a phone establish use in context. Two 636px by 600px pathway images carry giant bottom-aligned display labels; smaller 416px by 500px cards blend photography into charcoal beneath their captions.

**Transfer:** Show the service on a real device in a plausible environment, then fade the lower image into the page color for caption legibility.

### Icons

**Observed:** Mostly 24px monochrome SVG marks: arrows, thin plus signs, envelopes, search and configuration cubes. Gallery frames are 72px hexagons with 1px strokes; technical detail expanders use small white filled hexagons. Social marks form a compact footer cluster.

**Transfer:** Use geometric, restrained icons with square-ended fine lines. Reserve hexagonal enclosing shapes for navigation and product detail, not every icon.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product opening

**Observed:** The first 900px is a single edge-to-edge scene. From back to front: black canvas, full-cover moving image, bottom-darkening veil, Fixed navigation, then white title and action. The object sits in the upper-middle, with open perspective foreground below it. A broad 27px uppercase lead-in sits above a narrow 120px product name near the lower-left of the 1296px content span. The title group occupies roughly the left third; White action sits toward the right, aligned with the title's lower edge. About 160px remains beneath the foreground composition. No prose paragraph, metrics or following gallery appears in this first screen.

**Transfer:** Use a sharply directed product film, environmental still or dark-backed render with a similarly open foreground. Keep one promise, one name and one action. Editorial and service variants retain the same lower-left title silhouette, add breadcrumbs below the header, and may omit the hero action; flagship variants pair White action with Outline action.

**Avoid:** Do not turn the first screen into a centered text stack above a small rounded product card, or brighten the whole frame until the lower title loses contrast.

**Text style:** `display` — LamboType 400 · 120px/110px · uppercase

### Gallery reveal

**Observed:** White gallery follows a broad section header row. A centered product identity graphic and display statement introduce a 900px side-profile image stage. Hexagon arrow controls occupy opposite outer edges; a pale partial neighbouring object signals lateral browsing. Product tabs and Gallery action with companion text actions sit below the object.

**Transfer:** Show one coherent product silhouette at a time. Preserve the dramatic difference between this high-key gallery and the dark opening.

### Conversion sculpture

**Observed:** A 900px charcoal field begins with centered Product tabs. Below, a left five-column text group pairs a Lead-in with Display and Yellow action plus Outline action. An enlarged three-quarter object fills the right side and extends beyond its edge.

**Transfer:** Frame personalization, selection or a decisive next step as a product encounter rather than a form panel.

### Compact image action band

**Observed:** A 288px full-width image-backed black band places an 80px condensed title above a short row of 72px actions, with 56px vertical inset. Service variants use two consecutive bands: first policy reassurance, then a smaller 24px support prompt.

**Transfer:** Use a task-oriented transition to help, location, trial or contact without adding a full second hero.

**Text style:** `banner` — LamboType 400 · 80px/90px · uppercase

### Alternating editorial feature

**Observed:** A 760px band uses 80px top and bottom padding, a 526px by 600px image, and a six-column text area. Broad 54px headings lead into 18px paragraphs and one rectangular action. Image placement alternates left and right; dark corporate and white heritage treatments remain distinct.

**Transfer:** Use for origin, method or values when real narrative content exists; choose the background treatment by page purpose.

**Text style:** `chapter-heading` — LamboType 400 · 54px/64px · uppercase

### Performance proof and chapters

**Observed:** The technical variant starts with centered introduction copy and three monumental numeric values, each using 120px numerals, 24px units and muted 24px descriptions separated by 40px. Capability chapters then combine a centered 54px heading, 24px support gap and large media; offset detail carousels alternate with full-width 1440px by 810px galleries.

**Transfer:** Use verified metrics and a small number of visible mechanisms. Keep the repeatable chapter language, but let content determine chapter count.

### Chronology browser

**Observed:** Flat chronology columns use a year, a compact image, a 27px uppercase milestone heading and an underlined View more link. A horizontal decade selector sits below with segmented 2px rules. The dark variant supports institutional narrative; the white variant sits beside a side-profile catalog gallery.

**Transfer:** Use for meaningful product evolution or release milestones, preserving sideways browsing rather than converting it into a vertical decorative timeline.

### Support resolution

**Observed:** Service pages pair two image pathways with giant display labels, then use a horizontally overflowing smaller service-card row. A 40px FAQ chapter heading leads to Product tabs and FAQ rows. Image action bands close the support story before Footer navigation.

**Transfer:** Separate discovery, education and objection handling. Keep support pages theatrical without hiding useful questions.

### Information-rich sign-off

**Observed:** Footer navigation begins a black closing field approximately 899px tall. Utility links and social marks precede two white hairline-separated text bands with 64px padding. A small centered emblem finishes the page below the information, leaving open black space around it.

**Transfer:** Use the same visual cadence with proportionate utility and legal content; the centered identity remains the visual full stop.

## Page flow

**Storyline:** cinematic promise → product encounter → deeper understanding or proof → decisive task → utility and centered identity sign-off

### Broad product discovery and conversion

1. **Promise** — Full-screen film with lower-left condensed title and opposing white action.
2. **Product encounter** — White profile gallery, hexagonal arrows and segmented product tabs.
3. **Task bridge** — Shallow image-backed destination band.
4. **Conversion** — Charcoal oversized product sculpture with yellow primary and outlined secondary actions.
5. **Sign-off** — Black utility footer, ruled information bands and centered emblem.

**Transfer:** Use the light/dark alternation as a discovery-to-decision narrative, not a prescribed section count.

### Organizational credibility

1. **Context** — Environmental hero with breadcrumb and lower-left title.
2. **Explanation** — Black split feature with location imagery and concise profile.
3. **Track record** — Dark horizontal milestone browser and decade controls.
4. **Accountability** — Pale portrait feature followed by white ruled biography rows.
5. **Further discovery** — Three darkened portrait image destinations.
6. **Verification** — Black ruled resource download list.
7. **Sign-off** — Shared black footer and centered identity.

**Transfer:** Translate into credible people, process and verification content for the new organization.

### Heritage and evolution

1. **Emotional context** — Atmospheric photographic hero with a brief title.
2. **Portfolio proof** — White side-profile catalog browser.
3. **Track record** — White milestone cards with decade navigation.
4. **Narrative depth** — Alternating white split image-and-copy chapters.
5. **Sign-off** — Black footer directly after the last editorial feature.

**Transfer:** Pair artifacts with specific historical explanations rather than broad nostalgia claims.

### Flagship technical product story

1. **Promise** — Dark frontal product reveal, breadcrumbs and paired actions.
2. **Quantified proof** — Centered introduction and three giant metrics.
3. **Mechanism** — Repeated media-led capability chapters and offset technical carousels.
4. **Desire** — Full-bleed galleries and material-focused interior imagery.
5. **Verification** — Two-column technical specification heading and ruled data list.
6. **Conversion** — Shallow image action band, assurance strip and shared footer.

**Transfer:** Keep this extended dark variant for products with enough real detail to sustain it; use fewer chapters when the product is simpler.

### Connected service education and support

1. **Promise** — Device-in-context hero with a two-line condensed service name.
2. **Explanation** — Full-width film with monumental statement and compact support copy.
3. **Choice** — Two image-backed pathways with giant lower labels.
4. **Capabilities** — Horizontal service cards with concise captions.
5. **Objection handling** — Topic tabs and generous ruled FAQ rows.
6. **Reassurance** — Policy band followed by a separate contact-support band.
7. **Sign-off** — Shared black footer and centered identity.

**Transfer:** Keep education and support distinct from sales conversion while retaining the same staged imagery.

## Writing

Confident, aspirational and declarative. Emotional promises are followed by concrete engineering or institutional explanations rather than playful banter.

**Do not copy:** Do not reuse Lamborghini names, badges, model wordmarks, slogans, performance figures, heritage facts, proprietary imagery or unverified superiority and exclusivity claims. Source examples demonstrate syntax, not reusable claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Product descriptions are usually third person; actions and service guidance address the reader with direct imperatives and occasional your. Institutional prose is factual and impersonal.
- **Rhythm:** Headlines are compact uppercase phrases, often two to five words. Explanations use complete sentences and restrained punctuation; button labels are short verb-led commands.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A short conceptual phrase above a concrete product name. | 3–6 words | “The Quantum of Driving” |
| Chapter heading | A direct capability noun or concise editorial title. | 1–5 words | “Powertrain”<br>“FROM THE BEGINNING” |
| Supporting explanation | Name the mechanism and connect it to a meaningful outcome. | One or two sentences | “Motorsport-inspired technologies enhance precision, confidence and driver engagement, unlocking the purest expression of Super Veloce performance.” |
| Primary action | Imperative verb plus a clear task or destination. | 2–3 words | “Start configuration”<br>“Contact support” |
| Support question | Ask the actual reader's operational question without embellishment. | 5–15 words | “Can I deactivate the connected services?” |

**Words and phrasing to use:** design; performance; engineered; experience; discover; configure; crafted; technology

**Avoid:** cute; magic; game-changer; insane; cheap; hurry; !!!

**Rules:**

- Use one evocative promise at a time; follow it with a concrete mechanism.
- Keep actions literal even when the surrounding statement is emotional.
- Use verified numbers only, with adjacent units and explanatory labels.
- Keep editorial paragraphs readable and sentence case despite the uppercase heading system.

## Do's and Don'ts

### Do

- Use 120px/110px condensed capitals for the main product statement.
- Give paired 72px actions a 24px gap and trailing 24px icons.
- Align content to the 1320px container with 12px inner gutters.
- Use 80px top and bottom padding for major content bands.
- Keep carousel navigation hexagonal and 72px across.
- Keep product surfaces grounded with lighting and contact shadows rather than floating card shadows.
- Use 1px rules for long resource and support lists.
- Finish the information-rich black footer with a small centered identity.

### Don't

- Do not turn the yellow accent into a page-wide background; keep it concentrated on action and selection.
- Do not replace the narrow display face with a wide geometric headline at the same size.
- Do not round 72px actions into pills or soften image tiles with corner radii.
- Do not use drop-shadow elevation to separate ordinary content panels.
- Do not convert segmented underline tabs into filled capsule controls.
- Do not make body copy uppercase simply because titles and actions are uppercase.
- Do not replace the white-gallery gold with bright yellow; each belongs to a different stage.
- Do not force every product page into the extended technical chapter treatment when it has no corresponding proof.

## Motion and responsive

### Motion

**Observed:**

- The header declares transform 1s linear.
- Carousel-related controls declare width, opacity, transform and margin transitions of 0.3s; some overlays declare opacity 0.25s.
- Video-backed opening and chapter media coexist with slide-progress bars and play/pause controls.

**Transfer:**

- Keep motion concentrated in product footage, lateral galleries and progress indicators rather than animating every text block.
- Preserve a complete poster-like composition when footage is still or paused.

**Unknown:**

- Exact hero playback pacing and scroll-triggered animation sequencing are not established.

### Responsive

**Observed:**

- Styles include breakpoint boundaries at 576px, 768px, 992px, 1200px and 1440px, among additional component-specific widths.

**Transfer:**

- On narrow layouts, preserve the lower-title film-poster relationship while allowing actions below the title rather than shrinking their text.
- Stack editorial image and text panels; retain segmented horizontal browsing where partial neighbouring content communicates more options.
- Keep the centered identity and compact menu/search structure instead of exposing a crowded desktop navigation row.

**Unknown:**

- Exact mobile type sizes, scene heights and breakpoint-specific compositions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
