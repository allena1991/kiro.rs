# Accept & Proceed — staggered cultural catalogue

## Overview

A warm-paper editorial identity with the confidence of a design exhibition rather than a sales funnel. Regular-weight grotesk typography, small technical labels and an unusually spacious staggered image layout let projects supply the color and drama. It suits creative tools, ambitious technology and culture-facing products that can demonstrate their ideas through real objects, environments and visual systems. The default is light and low-density, with a charcoal institutional variant.

### Essentials

- The opening is an understated title film, not a billboard: a 1440×810 stage below a 64px navigation bar, with a single regular-weight, black-and-gray line near its left-hand vertical center; no stacked conversion buttons.
- Headings behave like editorial sentences: Messina Sans at weight 400, 35px/1.2 for introductions, 24px/32px for section leads and 20px/28px for featured captions, with -0.01em tracking.
- The image layout advances by unequal steps: 44px side gutters, 24px column gaps and 128px chapter intervals; alternate 1352px-wide media, 1008px centered images and 836px offset images at a 1440px viewport.
- The frame stays neutral while the work carries color: warm #f9f7f3 paper, #ecebe7 closing bands, black text and gray labels; saturated color belongs inside image rectangles, not buttons or whole marketing sections.
- Actions are small rounded lozenges, labels are almost square: 40px-high buttons with 20px radius and 17px type contrast with 28px-high outlined tags, 3.4px corners and 20px geometric icons separated from their text by a hairline.
- A living numeral sculpture closes the page: a 33.7px custom clock sits low in a spacious 619px closing band beside contacts, a compact email capsule and a short belief statement. Rebuild the clock with connected circular dots when custom numeral artwork is unavailable.
- Proof must be staged as an exhibition: use 8px-corner photographs, motion stills or composed visual artifacts with captions outside the frame; if there is no finished campaign imagery, show a photographed prototype, a clear interface composition and a process artifact instead.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, link | Primary text, editorial rules and the light-theme clock. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial white | `#ffffff` | `--color-white` | background, text | Editorial catalogue band and primary image-overlay captions. |
| Warm paper | `#f9f7f3` | `--color-canvas` | background, text | Default page canvas; reversed primary text for the charcoal variant. |
| Title-film gray | `#ebebeb` | `--color-opening-stage` | background | Pale neutral field of the opening title artwork; keep it distinct from the warmer page. |
| Closing stone | `#ecebe7` | `--color-stone` | background, surface, action | Closing band, button fills and selected navigation capsules. |
| Email capsule gray | `#e0dfdb` | `--color-form-fill` | surface | Visible email capsule on stone, built with black at 5% opacity. |
| Soft marking gray | `#a2a1a1` | `--color-muted` | text, border | Visible muted labels and hairlines on warm paper, made with rgba(140,140,140,0.8). The same alpha gray becomes darker against charcoal. |
| Title-film secondary ink | `#707070` | `--color-opening-secondary` | text | The softer second phrase within the opening title artwork. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| institutional and capability pages | Institutional charcoal | `#151515` | `--color-charcoal` | background, action | Page canvas and selected navigation in the reversed institutional theme. |
| institutional and capability pages | Raised charcoal band | `#262626` | `--color-dark-band` | background, surface | Closing band against the darker institutional canvas. |

## Typography

- **Messina Sans** — All ordinary headings, body text, captions, navigation and buttons. A compact contemporary grotesk, used entirely in regular weight with gently tightened spacing. If unavailable, use **Inter**. Use weight 400 and retain the negative tracking; check line wraps against the compact text measures. Font stack: "Messina Sans", "Inter", Arial, sans-serif.
- **Letterformvariations 04 Dmgx** — The sculptural digital clock in the closing band. Experimental rounded, connected-dot numerals; graphic rather than technical monospace. If unavailable, use **Doto**. Use the heavier dotted cuts or construct connected circular modules in SVG. Font stack: "Letterformvariations 04 Dmgx", "Doto", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| opening-line | Messina Sans | 400 | 44px | 1.2 | normal | size 3.056vw | The single-line title artwork, with black introductory words followed by softer gray words. Keep its scale modest relative to its very large stage. |
| heading-lg | Messina Sans | 400 | 35px | 1.2 | -0.01em | fixed | Editorial introductions and project title-plus-promise pairs. |
| clock | Letterformvariations 04 Dmgx | 400 | 33.7px | 1 | normal | fixed | Large decorative hours, colon and minutes along the footer baseline. |
| section-heading | Messina Sans | 400 | 24px | 32px | -0.01em | fixed | Section leads and the catalogue's introductory sentence. |
| footer-heading | Messina Sans | 400 | 24px | 40px | -0.01em | fixed | Contact and social headings and their muted link lists. |
| featured-caption | Messina Sans | 400 | 20px | 1.4 | -0.01em | fixed | Featured image titles and their one-sentence outcome lines. |
| body | Messina Sans | 400 | 17px | 24px | -0.01em | fixed | Standard descriptive text, catalogue rows and compact project captions. |
| navigation | Messina Sans | 400 | 17px | 1 | -0.01em | fixed | Header navigation labels. |
| button | Messina Sans | 400 | 17px | 1 | normal | fixed | Rounded action labels. |
| tag | Messina Sans | 400 | 14px | 1 | normal | fixed | Outlined classification labels beside a geometric symbol. |
| footer-statement | Messina Sans | 400 | 14px | 24px | -0.01em | fixed | Compact belief statement in the closing band. |
| form-label | Messina Sans | 400 | 10px | 1.6 | -0.01em | fixed | Small invitation above the email capsule. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| project directory pages | index-heading | Messina Sans | 400 | 35px | 48px | -0.01em | fixed | Short directory title above a same-size gray introductory sentence. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep headings and supporting statements at the same weight; size, placement and ink tone carry the hierarchy.
- Ordinary text uses -0.01em tracking across sizes; buttons and technical tags retain normal tracking.
- The title artwork is larger than the editorial introductions but intentionally far smaller than a full-width display headline. Do not turn it into bold oversized campaign typography.
- Captions usually put the name and the outcome on consecutive lines, with no size change; directories mute the outcome while featured entries keep it black.

## Layout

**Density:** Airy at section scale and compact within text groups: images occupy broad areas separated by long pauses, while names and outcomes sit tightly together.

### Spacing

**Spacing system:**

- **token step** 8px — Base for declared spacing tokens; the system also uses 12px local gaps and a 44px desktop edge gutter.

| Value | Use |
| --- | --- |
| 8px | Section-heading to supporting-text gap and navigation item gap. |
| 12px | Wrapping tag gaps and close local arrangements. |
| 16px | Small local spacing and action alignment within editorial rows. |
| 24px | Primary grid gutter and credits heading-to-text gap. |
| 32px | Space before catalogue rules and disclosure actions. |
| 40px | Closing-band top and bottom padding; editorial-band top padding. |
| 44px | Desktop container side padding. |
| 48px | Featured image-overlay inset and larger local separation. |
| 64px | Fixed navigation height and opening-stage offset. |
| 80px | Catalogue list to its continuation action. |
| 128px | Main project-image chapter separation. |
| 152px | Lower spacing after project credits. |

### Containers and grids

- **main container**: max width 1920px · 8 columns · gap 24px · side padding 44px. Centered master grid; at 1440px the usable width is 1352px. Align text and media to its eight columns rather than centering every section.
- **half width text**: max width 664px · 2 columns · gap 24px. Title and promise occupy the right half of the main grid, leaving the left half largely open or holding a tiny back-to-index control.
- **media widths**: max width 1352px. At desktop, alternate full-container media with centered 1008px frames and left- or right-aligned 836px frames. Small supporting pictures can be 320px wide.
- **editorial catalogue**: 8 columns · gap 24px. A section title takes the left quarter; the introductory sentence and ruled list occupy the remaining three quarters, about 1014px at desktop.
- **related grid** (only for case-study endings): 3 columns · gap 24px. Three square 320px images with captions and tags sit to the right of a narrow section-title column.
- **quote measure** (only for institutional and capability pages): max width 454px. A small left-aligned testimonial area with a large unoccupied field beside it.

## Corner radius

| Element | Radius |
| --- | --- |
| media frames | 8px |
| action lozenges | 20px |
| navigation and email ends | 100px |
| classification tags | 3.4px |
| dots and return control | 50% |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #f9f7f3; color: #000000`

**Observed:** A warm neutral ground surrounds the media; cards do not add separate white boxes.

**Transfer:** Let the page itself be the caption backing.

#### Editorial white band · level 0

**Use:** A change of register for an editorial or resource catalogue.

**CSS:** `background: #ffffff; padding-top: 40px; padding-bottom: 188px`

**Observed:** The white band meets the warm canvas directly without a border or shadow.

**Transfer:** Use this clean change of surface for structured reading after visual proof.

#### Stone closing band · level 0

**Use:** The shared contact and subscription ending.

**CSS:** `background: #ecebe7; padding-top: 40px; padding-bottom: 40px`

**Observed:** A broad flat band, not a floating card; it gives the low clock and contact columns a common ground.

**Transfer:** Keep all closing functions on one surface.

#### Frosted navigation · level 2

**Use:** Fixed translucent navigation above content.

**CSS:** `background: rgba(249, 247, 243, 0.8); backdrop-filter: blur(15px)`

**Observed:** The bar lets images show softly through it. The institutional version uses rgba(46,46,46,0.8).

**Transfer:** Apply blur to the bar only, not to project images or ordinary content panels.

#### Charcoal canvas · level 0

**Only for:** institutional and capability pages

**Use:** Reversed narrative variant.

**CSS:** `background: #151515; color: #f9f7f3`

**Observed:** Warm off-white headings and alpha-gray supporting text sit on a nearly black ground; the final band lifts to #262626.

**Transfer:** Keep the same grid, type weight and image corners when reversing the palette.

## Components

### Fixed navigation

**Use:** Global orientation without competing with the visual work.

**CSS:** `height: 64px; position: fixed; top: 0px; width: 100%; backdrop-filter: blur(15px)`

**Text style:** `navigation` — Messina Sans 400 · 17px/1 · tracking -0.01em

**Observed:** Brand name sits at the far left; three short navigation links begin around the middle; a wider editorial destination anchors the far right. Use Frosted navigation behind the content.

**Transfer:** Use a compact text identity and a few short destinations rather than an oversized logo or a separate bright conversion button.

### Navigation capsule

**Use:** Individual navigation targets and selected destinations.

**CSS:** `height: 40px; width: 100px; border-radius: 100px; padding-top: 12px; text-align: center`

**Text style:** `navigation` — Messina Sans 400 · 17px/1 · tracking -0.01em

**Observed:** Default links are unfilled. The selected directory link gains a stone capsule; reversed navigation uses white text and a darker selected capsule. The far-right destination is 200px wide.

**States:** Declared: hover background-color #ecebe7 and color #000000; active outline 0px. Focus-visible treatment is unspecified.

### Action lozenge

**Use:** Small, low-pressure reading or listening action.

**CSS:** `background: #ecebe7; color: #000000; border-radius: 20px; height: 40px; padding-top: 12px; padding-right: 33px; padding-left: 33px; text-align: center; mix-blend-mode: multiply`

**Text style:** `button` — Messina Sans 400 · 17px/1

**Observed:** Text-only, without an arrow. The continuation version is 141px wide; repeated row actions are 100px wide. Disclosure versions are 140px wide and do not use multiply blending.

**States:** Declared: hover filter invert() and outline 0px; active outline 0px; transition 0.2s. Focus-visible treatment is unspecified.

**Transfer:** Use short verbs and neutral fills, keeping actions visually smaller than the imagery.

### Classification tag

**Use:** Tiny reusable markers that connect imagery to capability categories.

**CSS:** `display: flex; align-items: center; height: 28px; border: 1px solid rgba(140, 140, 140, 0.8); border-radius: 3.4px; color: rgba(140, 140, 140, 0.8)`

**Text style:** `tag` — Messina Sans 400 · 14px/1

**Observed:** A 20px geometric icon occupies a square cell, followed by a 1px divider and the text with 7.5px side margins. Tags wrap with 12px gaps, typically 18px beneath the caption. On an image, border and text reverse to translucent white.

**Transfer:** Create two or three stable, meaningful classifications, each with its own minimal geometric symbol.

### Project media card

**Use:** Featured proof with a concise title and outcome.

**CSS:** `border-radius: 8px; overflow: hidden; object-fit: cover; max-width: 100%`

**Text style:** `featured-caption` — Messina Sans 400 · 20px/1.4 · tracking -0.01em

**Observed:** The CSS applies to the media frame, not a box around the whole article. Caption text sits 30px beneath the image, followed by Classification tag. A wide immersive variant places white captions in the lower-left of the image with a 48px inset. Directory cards use body type and gray supporting text.

**Transfer:** Pair a real artifact or contextual image with one outcome sentence; vary the image width while keeping caption alignment exact.

### Editorial catalogue row

**Use:** Structured resources or releases with compact metadata and an action.

**CSS:** `display: grid; grid-template-columns: repeat(6, 1fr); column-gap: 24px; border-top: 1px solid #000000`

**Text style:** `body` — Messina Sans 400 · 17px/24px · tracking -0.01em

**Observed:** Rows are typically 79px high and may grow for wrapped titles. A topic takes one column, the title three, short metadata one, and an Action lozenge the last. The text trigger has 15px vertical padding; the last row also receives a bottom rule.

**Transfer:** Use for a resource library, updates or a compact knowledge series, preserving the tabular rather than card-based rhythm.

### Email capsule

**Use:** Compact newsletter signup in the closing band.

**CSS:** `display: flex; max-width: 292px; height: 40px; border-radius: 100px; overflow: hidden`

**Text style:** `body` — Messina Sans 400 · 17px/24px · tracking -0.01em

**Observed:** The left input is 198px wide with 20px left and 8px vertical padding. A 94px Submit segment completes the same silhouette; both use rgba(0,0,0,0.05), with no visible seam. A form-label invitation sits 8px above it. In the dark variant the segments use rgba(236,235,231,0.1).

**Transfer:** Keep the submit action inside the same capsule instead of placing a second button beside the field.

### Footer contact list

**Use:** Closing navigation for social and contact routes.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; color: rgba(140, 140, 140, 0.8)`

**Text style:** `footer-heading` — Messina Sans 400 · 24px/40px · tracking -0.01em

**Observed:** Black category headings precede gray text-only links of the same size. Social and contact columns stand beside a much smaller belief statement; they are not grouped into cards.

**Transfer:** Group routes by reader intent, and let gray links remain visually subordinate to black labels.

### Sculptural clock

**Use:** The distinctive low-positioned ending device.

**CSS:** `display: flex; gap: 3.4px; color: #000000`

**Text style:** `clock` — Letterformvariations 04 Dmgx 400 · 33.7px/1

**Observed:** Hours, colon and minutes form one connected-dot composition. It aligns near the footer's lower baseline, beneath the belief statement rather than centered across the page. The reversed version is warm off-white.

**Transfer:** Use a live local-time readout in a dotted display font or custom SVG; retain the playful numeral construction without turning it into a performance metric.

### Small quote carousel

**Only for:** institutional and capability pages

**Use:** Personal corroboration after capability descriptions.

**CSS:** `max-width: 454px; position: relative; padding-bottom: 90px; color: #ffffff`

**Text style:** `body` — Messina Sans 400 · 17px/24px · tracking -0.01em

**Observed:** A 24px section lead precedes a regular 17px quotation by 8px. Attribution follows with a 12px gap and 50% white. Four 10px circular indicators sit below; the active dot is white and inactive dots are 20% white, each in a 22×30px target.

**Transfer:** Keep a single readable quote visible at a time; this is a small editorial aside, not a giant quote wall.

## Imagery and graphics

### Title-film typography

**Use:** The default first-screen visual signature.

**Observed:** A pale gray, edge-to-edge 16:9 stage contains just a short black introductory phrase and a gray identity phrase, placed near the left edge at mid-height. The line takes roughly a third of the stage width, leaving most of the field open.

**Transfer:** Use a short statement of identity or intent rendered as live type if there is no film. The statement itself is enough; no stock illustration is needed.

**Build:** Use a 1440×810 proportional wrapper with background #ebebeb and 8px lower corners. Position one regular sans line at the vertical center with a 30px left inset at desktop. Set the opening-line recipe, split the phrase into black and #707070 spans, and scale the line relative to viewport width.

### Contextual proof photography

**Use:** Primary visual storytelling across the marketing page and project stories.

**Observed:** Installations, screens, printed campaigns, products and people using the work are photographed in real spaces. Images retain environmental light, materials and occasional grain; dark blue-lit spaces contrast with pale or natural scenes. Frames range from broad landscapes to square details; the page remains largely empty around smaller images.

**Transfer:** Show your product being used in a credible setting, not only isolated device mockups. Combine a wide contextual view with a tighter human or material detail. Preserve natural color inside the image rather than tinting the surrounding canvas.

### Composed artifacts and interface boards

**Use:** Explanatory proof between contextual photographs.

**Observed:** Flat interface compositions, diagrams, brand-system sheets and physical objects are staged inside the same rounded rectangles as photographs. Pale gray boards can hold multiple screens; dark boards can present objects with directional light. Their internal typography belongs to the artifact, not the marketing type system.

**Transfer:** Build a real, populated interface board or a photographed process sheet. Use one clean neutral backing and a clear focal hierarchy; keep internal shadows within the artwork rather than adding shadows to page cards.

### Point-cloud city

**Only for:** data-led demonstration media

**Use:** An atmospheric alternative to literal product photography.

**Observed:** A high-key cyan city dissolves into tiny points and soft depth layers on a nearly white ground. It fills a wide media rectangle; small reversed captions sit low within it.

**Transfer:** Use a point-cloud rendering of an environment or object relevant to the new product, retaining the airy data-like texture.

**Build:** In SVG or canvas, sample a simple city or object silhouette into many small cyan points with varied opacity. Use denser vertical clusters for near forms and lighter, blurred clusters behind; leave substantial near-white negative space. Treat the result as one media asset rather than a page-wide decorative particle background.

### Finished work and process diptych

**Only for:** long-form case studies

**Use:** Demonstrate that a visible outcome has a real system behind it.

**Observed:** Finished installations alternate with production crates, drawings, interface studies, printed manuals and packaging. One large image can be followed by a much smaller offset detail; pairs are intentionally unequal.

**Transfer:** Pair a polished result with a relevant construction or decision artifact. Use genuine process material rather than making fake technical drawings solely as decoration.

### Icons

**Observed:** Marketing icons are restrained geometric outlines: circle, diagonal square and a clustered-circle symbol inside 20px tag cells, plus a 16px four-square index icon within a 40px circular control. Gray on paper and translucent white on image overlays.

**Transfer:** Use simple SVG geometry with consistent thin strokes and no fills or colorful icon tiles. Keep category symbols and navigation symbols distinct from any icon language shown within product artwork.

## Section recipes

How recurring sections are built.

### First screen: Title-film opening

**Observed:** Paper canvas supports a 64px fixed Frosted navigation layer; beneath it a full-width 810px-high Title-film typography stage fills nearly all the first 900px. Its single regular-weight black-and-gray line sits near the left edge at the stage's vertical center, much smaller than the available field. Background, title artwork and navigation are the only substantive layers. There is no supporting paragraph or in-stage action cluster; navigation provides the visible actions. Project proof begins below the fold after a generous pause.

**Transfer:** For a new landing page, make the same unhurried first impression with a short live-type identity statement and a pale title stage. A project-story variant opens instead with a full-bleed contextual photograph or film and moves the title-plus-outcome pair below it. Directory and institutional variants open with heading-lg text on the right half, beginning 74px beneath navigation.

**Avoid:** Do not add a centered oversized headline, dashboard collage, floating badges and two conversion buttons to this sparse opening.

**Text style:** `opening-line` — Messina Sans 400 · 44px/1.2

### Staggered proof exhibition

**Observed:** Project media card alternates widths and alignments on the eight-column grid. Full 1352px landscapes contrast with centered 1008px images and smaller asymmetric pairs. Featured captions use featured-caption type; name and outcome follow without a gap, then tags. Wide overlay variants use white text low on the image.

**Transfer:** Use differing scales to indicate importance and visual variety. Keep broad 128px breathing intervals between major image chapters; choose the number and order of examples for the new narrative.

**Text style:** `featured-caption` — Messina Sans 400 · 20px/1.4 · tracking -0.01em

### Editorial resource band

**Observed:** Editorial white band holds a section label in the left quarter and a 24px introductory sentence in the right three quarters. Editorial catalogue row begins 32px below the introduction. Repeated rules, compact metadata and 100px Action lozenge controls create an index; a continuation action sits 80px below the list.

**Transfer:** Use this device to give the page an intellectual or editorial dimension through useful resources, releases or conversations rather than another marketing card grid.

**Text style:** `section-heading` — Messina Sans 400 · 24px/32px · tracking -0.01em

### Contact landscape ending

**Observed:** Stone closing band is 619px high with 40px top and bottom padding and 44px side gutters. Social links occupy the first quarter, contacts the second, and a 320px-wide footer-statement begins in the right half. Email capsule sits beneath the social routes with a long 120px separation. Small trust marks anchor the lower left, Sculptural clock sits below the statement, and fine utility text anchors the lower right. A great deal of open space separates the two horizontal registers. The dark variant lifts its band to #262626 and is 643px high.

**Transfer:** End with useful routes, a compact invitation, an original belief statement and the living clock rather than a huge final sales headline. Reflow the functions as needed while retaining the spacious high-and-low composition.

**Text style:** `footer-heading` — Messina Sans 400 · 24px/40px · tracking -0.01em

### Right-half title pair

**Only for:** project stories, directories and institutional pages

**Observed:** A small title and an outcome or introductory sentence share heading-lg size and weight in a 664px right-half measure. The left half stays mostly unoccupied; case studies place a circular return control there. Project introductions begin with 60px top padding, place tags below the title pair and an Action lozenge 32px after the tags; the intro has substantial lower breathing room.

**Transfer:** State what the product is and what changes because of it, using a title and a sentence rather than two unrelated display treatments.

**Text style:** `heading-lg` — Messina Sans 400 · 35px/1.2 · tracking -0.01em

### Capability and image alternation

**Only for:** institutional and capability pages

**Observed:** Charcoal canvas carries off-white section-heading text and gray body descriptions separated by 8px. Short bullet lists follow. Images alternate between a 664px right-half scene and a 492px left-side detail, while later capability text aligns to the right. Small quote carousel follows a long pause.

**Transfer:** Divide the offering into a few plain-language capabilities and demonstrate each through a concrete image. Preserve the alternating text and image weights rather than making identical feature cards.

**Text style:** `section-heading` — Messina Sans 400 · 24px/32px · tracking -0.01em

### Credits and related proof

**Only for:** case-study endings

**Observed:** After the final project image, a compact Credits block sits on the right half with 96px top padding, a 17px heading and small contributor text below. A three-item related grid uses square 320px media, body captions and Classification tag; a narrow left title column keeps the grid asymmetrical. This leads into Stone closing band.

**Transfer:** Acknowledge real collaborators and offer adjacent stories at a smaller visual scale than the main case study. Do not invent contributor lists if the new content has none.

**Text style:** `body` — Messina Sans 400 · 17px/24px · tracking -0.01em

## Page flow

**Storyline:** identity → curated visible proof → deeper explanation or editorial resources → useful routes and a living closing signature

### General marketing landing page

1. **Identity** — A nearly full-screen title film with one black-and-gray statement.
2. **Selected proof** — A varied-scale exhibition of featured project imagery, captions and classifications.
3. **Editorial depth** — A white resource band turns into a ruled index with small reading or listening actions.
4. **Closing invitation** — A stone contact landscape with newsletter capsule, belief statement and sculptural clock.

**Transfer:** Use a spare identity statement, then prove the product through a few visually distinct outcomes; let editorial value and useful routes replace aggressive funnel repetition.

### Technology or experience case study

1. **Contextual demonstration** — A full-bleed photograph places a real interactive installation in its environment.
2. **Promise** — Right-half project title, outcome sentence, classification and disclosure button.
3. **Detailed proof** — Large image chapters alternate contextual photography, interface boards, close-up interaction and production material.
4. **Attribution and continuation** — Right-half credits and three smaller related projects.
5. **Closing invitation** — The shared stone contact landscape and live clock.

**Transfer:** Make a deep technical story legible through the sequence of outcomes, systems and real-world use rather than lengthy sales prose.

### Visual-system case study

1. **Immediate identity** — Full-width film or photography presents the finished identity in cultural context.
2. **Promise** — The right-half title pair names the transformation, followed by tags and a disclosure action.
3. **System breadth** — An extended sequence moves among design-system sheets, real-world applications, packaging and underlying strategic artifacts, using alternating frame sizes.
4. **Attribution and adjacent proof** — Compact credits precede a related-project row.
5. **Closing invitation** — The shared contact, signup and clock ending.

**Transfer:** Demonstrate a coherent system across relevant touchpoints without carrying the featured project's internal colors and type into the page shell.

### Institutional and capability narrative

1. **Point of view** — A right-half introduction on charcoal establishes people and beliefs.
2. **Capabilities** — Concise section leads, support lines and short bullet lists alternate with images.
3. **Social corroboration** — A small left-aligned quote carousel occupies a broad dark field.
4. **Closing invitation** — A lighter charcoal band reverses the shared contact landscape and clock.

**Transfer:** Use the reversed theme for an institutional narrative while maintaining the same regular-weight type, staggered grid and small-scale proof.

### Browsable project directory

1. **Orientation** — A small right-half title and muted introductory sentence leave the left side open.
2. **Breadth of proof** — A long staggered two-column image catalogue varies card widths, title wraps and category tags.
3. **Closing invitation** — The shared stone ending consolidates contacts, signup, belief and clock.

**Transfer:** Provide browsing depth through irregularly scaled but carefully aligned examples, not a uniform dashboard of identical cards.

## Writing

Reflective, assured and culturally literate. The language combines strategic ambition with practical verbs and gives the work room to substantiate the claim.

**Do not copy:** Do not reuse the agency's name, project names, client names, signature programme title, certifications, membership claims, collaborator credits, testimonials or outcome claims. Source examples illustrate verbal construction, not copy to transplant.

- **Addressing the reader:** Use we for the maker or team and brands, people or teams for beneficiaries. Direct you-address is rare; an occasional question creates a human closing rather than a hard sell.
- **Rhythm:** Short titles are followed by one sentence with an active verb and a meaningful contrast. Longer institutional copy breaks into small paragraphs. Buttons remain literal and economical; avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Identity line | A plain statement of who is speaking, with the identity phrase visually softened. | A single short line | “We are [Brand]” |
| Project promise | Start with a participle and connect an abstract challenge to a human or tangible result; use contrast when it clarifies the idea. | 6–12 words | “Translating complex technologies into human experiences”<br>“Building rules for the brand that broke them” |
| Capability heading | A short we-led active statement; the support line explains how it helps. | 4–7 words | “We set new ambitions”<br>“We facilitate new connections” |
| Supporting line | Name the change in behavior or understanding, not a list of features. | One compact sentence | “Making clarity and ethics matter as much as innovation”<br>“We help brands find their pathway forward.” |
| Action | Literal verb phrase, with no promotional intensifier. | 1–2 words | “Listen”<br>“See More”<br>“Read More” |
| Closing thought | Follow a short belief statement with an open-ended human question. | One short question | “What do you believe?” |

**Words and phrasing to use:** shape; build; equip; clarity; possibility; ambition into action; human experiences; systems; connections

**Avoid:** revolutionary; game-changing; supercharge; unlock your potential; seamless solution; limited time; best-in-class

**Rules:**

- Prefer a specific transformation over a claim of superiority.
- Let the project name identify the subject; let its next line express the outcome.
- Use a contrast such as complex/human or say/do only when it expresses a real proposition.
- Keep category names consistent across all cards and detailed stories.
- Use questions as invitations to reflection, not as rhetorical pressure to convert.

## Do's and Don'ts

### Do

- Keep the ordinary type at weight 400, including section headings and navigation.
- Align desktop content to 44px side gutters and 24px column gaps.
- Vary media between full-container, centered and offset widths while retaining 8px corners.
- Use 128px intervals to let major visual chapters breathe.
- Keep actions 40px high and neutral, with 17px labels.
- Use 28px outlined classification tags with small geometric icon cells.
- Give the ending a spacious upper contact register and a low 33.7px sculptural clock.
- Keep bright color within actual project media and preserve the neutral shell.

### Don't

- Do not promote the 35px editorial introduction to a heavy 80px sales headline.
- Do not put every project into an identical equal-width card with white padding and a shadow.
- Do not use 20px pill corners for classification tags; their corners are only 3.4px.
- Do not spread image-specific blues, reds or yellows into navigation fills or generic page backgrounds.
- Do not replace the small text-only lozenge with a tall gradient button and trailing arrow.
- Do not tighten the entire ending to the height of a standard compact link footer.
- Do not use the expressive clock face for body copy, navigation or technical metadata.
- Do not turn the page into a centered stack; the right-half text measures and unequal media widths are structural.

## Motion and responsive

### Motion

**Observed:**

- Navigation background-color transitions are 0.2s; action lozenges declare a 0.2s transition and hover inversion.
- Media frames declare transform 0.3s ease-out; reveal wrappers declare transform durations of 1.2s, 1.35s and 1.5s with cubic-bezier(0,0.56,0.46,1).
- The fixed header declares transform 0.2s ease-out; its backing declares height 0.4s cubic-bezier(0.215,0.61,0.355,1).
- The small cursor is a 16px alpha-black circle with blur(5px), and a 0.2s ease-out transition. Quote indicators declare background-color 0.25s.

**Transfer:**

- Keep slow reveal motion subordinate to the staggered exhibition; do not animate every label independently.
- Use quick neutral-fill or inversion feedback for small actions, reserving the longer transform cadence for media arrival.
- The closing clock should remain a living time display, not a decorative random-number animation.

**Unknown:**

- Reveal trigger positions, exact moving distances and film timing are not established.
- Focus-visible appearance and reduced-motion behavior are unspecified.

### Responsive

**Observed:**

- Width breakpoints include 479px, 767px, 768px, 991px, 992px, 1439px, 1440px and 1920px.
- The institutional variant also declares 393px, 667px and 1919px breakpoints.
- The directory's right-half introduction has a tablet-left-alignment class.

**Transfer:**

- On narrow layouts, move right-half introductions into the reading column before their media rather than retaining an empty left half.
- Preserve differences in image scale through alternating full-width and slightly inset frames; reduce long pauses without making a dense card list.
- Reflow editorial rows into topic, title and metadata groups with the lozenge retained at the end of the entry.
- Stack closing contact groups and keep the clock as a distinct lower-register device.

**Unknown:**

- Exact mobile font sizes, gutters, navigation behavior and image ordering are not established. Responsive transfers are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
