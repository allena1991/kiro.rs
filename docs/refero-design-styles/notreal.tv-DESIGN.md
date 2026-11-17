# NotReal — gallery meets synthetic delight

## Overview

An art-directed, light editorial style where sober black typography frames exuberant synthetic worlds. Regular grotesk text is threaded with expressive calligraphic serif phrases, while staggered images bring jewel colors, tactile materials and cinematic light. It suits visually ambitious products, creative tools and premium objects with a story best told through demonstrations rather than dense interface chrome.

### Essentials

- Identity behaves like a gallery title: a black wordmark artwork approximately 436px × 95px anchors the left of the opening, opposite a 24px/26px statement with 24.5px serif phrases.
- The first proof arrives before a sales pitch: a sharp-cornered 894px × 503px image occupies about two thirds of the content width, with the next smaller image staggered down the opposite side.
- Two voices share one sentence: regular Telegraf labels at 25px/25px lead into Ogg phrases at 25.5px/1.5; chapter headings pair 40px/45px sans with 40.8px/45px serif.
- Actions are typography, not capsules: 25px navigation has 1px tracking and underlined hover treatment; footer links use 20px type with no filled button shell.
- Color belongs to the exhibited work: the page canvas stays #f2f2f2 with #000000 text, while rectangular media can be fully saturated and occupy most of a screen; there is no site-wide chromatic accent.
- The gallery has its own public-address strip: include a 100px-high, horizontally moving invitation between 1px black rules, mixing 55px sans and serif with arrows. Include the vertically rotated edge annotation and a thin ruled footer as companion editorial markings.
- Images are material experiences rather than stock decoration: metallic facets, rubbery volumes, translucent glass and soft cast shadows fill clean rectangular stages. When no cinematic media exists, stage a real product or a small set of custom geometric objects with the same directional light and tactile finish.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black lettering | `#000000` | `--color-ink` | text, link, border, action | All primary marketing lettering, arrows and ticker rules. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal rule | `#292a2c` | `--color-rule` | border | Thin footer separator. |
| Gallery grey | `#f2f2f2` | `--color-canvas` | background, surface, border | Continuous page and fixed navigation canvas; also the inconspicuous bottom border on navigation text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| filterable galleries | Filter grey | `#868686` | `--color-muted` | text, link | Inactive category links; active category becomes black and serif. |

## Typography

- **telegraf** — Primary prose, navigation, labels and the sans half of mixed headings. Open, geometric grotesk with a low-key regular weight and broad circular forms. If unavailable, use **DM Sans**. Use weight 400; retain the modest positive tracking. Font stack: "telegraf", "DM Sans", Arial, sans-serif.
- **ogg** — Expressive phrases embedded within sans prose, subtitles and editorial invitations. High-contrast calligraphic serif with visibly inclined, flowing forms; the distinctive shape comes from the face rather than a bold weight. If unavailable, use **Cormorant Garamond**. Use regular italic to approach the flowing Ogg silhouette; tune width before increasing weight. Font stack: "ogg", "Cormorant Garamond", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| ticker-sans | telegraf | 400 | 55px | 1.1 | 0.0018em | Repeated destination and arrow text in the moving invitation. |
| ticker-serif | ogg | 400 | 55px | 1.1 | -0.0364em | Human invitation phrase in the moving strip. |
| chapter-heading | telegraf | 400 | 40px | 1.125 | 0.0025em | Chapter statements and the underlined first phrase of title pairs. |
| project-subtitle | ogg | 400 | 25.5px | 1.5 | -0.0196em | Second line of a media caption. |
| project-label | telegraf | 400 | 25px | 1 | normal | First line of a media caption, usually ending in an em dash. |
| navigation | telegraf | 400 | 25px | 1 | 0.04em | Main navigation text. |
| opening-emphasis | ogg | 400 | 24.5px | 1.062 | -0.0204em | A few inline phrases inside the opening statement, sharing its baseline. |
| opening-statement | telegraf | 400 | 24px | 1.083 | 0.021em | Compact opening statement opposite the identity artwork. |
| body | telegraf | 400 | 20px | 1.33333 | 0.025em | Explanatory paragraphs, credits and back-to-top links. |
| footer-link | telegraf | 400 | 20px | 0.75 | normal | Sparse social link row. |
| discipline | telegraf | 400 | 15px | 2 | 0.033em | Small lowercase slash-separated descriptors beneath featured media captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | chapter-emphasis | ogg | 400 | 40.8px | 1.103 | -0.0123em | Expressive companion phrase for detailed product stories. |
| gallery and company pages | editorial-emphasis | ogg | 400 | 40.8px | 1.103 | normal | Companion phrase after the em dash in gallery and company headings. |
| company pages | capability-title | ogg | 400 | 30.6px | 1.143 | -0.0163em | Titles of three parallel capability columns. |
| company pages | intro-prose | telegraf | 400 | 30px | 1.33333 | normal | Longer introductory company paragraphs. |
| company proof lists | recognition-detail | ogg | 400 | 25.5px | 1.216 | normal | Inline detail following an institution label. |
| company proof lists | recognition-label | telegraf | 400 | 25px | 1.24 | 0.02em | Date and institution within a continuous proof list. |
| filterable galleries | filter | telegraf | 400 | 20px | 1.5 | 0.005em | Wrapping slash-separated filter list. |

**Notes:**

- Use regular weight throughout; typeface changes, underlining and scale create emphasis instead of bold blocks.
- Keep the serif close to the sans size: 24.5px beside 24px, 25.5px beside 25px and 40.8px beside 40px. These small differences preserve optical equality.
- The largest identity is an artwork, not an oversized sans marketing headline. Keep it separate from the compact opening statement.
- Do not force a synthetic italic onto the Ogg face; preserve its native flowing letterforms. The substitute needs italic to approximate that silhouette.

## Layout

**Density:** Airy, with compact caption stacks and substantial irregular pauses between independently staggered media.

### Spacing

| Value | Use |
| --- | --- |
| 18px | Padding above the first caption line. |
| 20px | Seams between full-bleed case-study media and chapter title bottom space. |
| 22px | Desktop gutter formed by two 11px column insets. |
| 26.7px | Paragraph separation. |
| 44px | Desktop page side inset. |
| 80px | Text chapter top and bottom padding; four rhythm units. |
| 100px | Approximate separation before explanatory text following a large media stage. |
| 150px | Extended editorial pause before a substantial change of subject. |

### Containers and grids

- **page-container**: max width 2648px · side padding 44px. Centered desktop content shell; at 1440px the working span is 1352px.
- **editorial-grid**: 12 columns · gap 22px. An underlying column logic supports thirds, halves and two-thirds media widths without making every row symmetrical.
- **featured-gallery**: 2 columns · gap 22px. Unequal and alternating featured placements: 894px wide media beside 436px media, then 665px pairs. Offset their tops rather than aligning every card.
- **explanatory-split**: 2 columns · gap 22px. Heading on the left and prose on the right; the heading may occupy only the leftmost third while prose starts at the halfway line.
- **catalog-gallery** (only for filterable galleries): 3 columns · gap 22px. Independent masonry columns of approximately 437px, maintaining each image's aspect ratio.
- **reading-column** (only for company pages): max width 500px. Restrained text measure within company capability columns.
- **full-bleed-media** (only for case studies): max width 2560px · side padding 0px. Large case-study image stages bypass the text inset and reach both viewport edges.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media-and-cards | 0px |
| company image sliders | gallery-arrow-hit-area | 50% |

## Surfaces and depth

### Surfaces

#### Gallery canvas · level 0

**Use:** Continuous backing for typography, navigation and unboxed captions.

**CSS:** `background: #f2f2f2; color: #000000`

**Observed:** The canvas remains visible around differently colored media; there are no raised card shells.

**Transfer:** Let the product images carry the palette while the surrounding page stays neutral.

#### Ruled invitation · level 0

**Use:** Editorial broadcast band.

**CSS:** `border-top: 1px solid #000000; border-bottom: 1px solid #000000; height: 100px; overflow: hidden; position: relative`

**Observed:** The text travels horizontally through a narrow, full-content-width slit.

**Transfer:** Use one continuous repeated invitation and destination, not a boxed announcement card.

#### Footer rule · level 0

**Use:** Separation of ownership and utility links from social destinations.

**CSS:** `border-top: 1px solid #292a2c; margin-top: 15px`

**Observed:** A single horizontal line, without a different footer background.

**Transfer:** Keep the page's visual energy above this understated finish.

## Components

### Fixed navigation

**Use:** Primary navigation and contact action.

**CSS:** `position: fixed; z-index: 120; background-color: #f2f2f2; height: 60px; color: #000000`

**Text style:** `navigation` — telegraf 400 · 25px/1 · tracking 0.04em

**Observed:** Four widely distributed text links occupy the right half. A small black identity appears at the left on interior pages and after scrolling; the active interior destination changes to the expressive serif.

**States:** Declared: hover remains black with underline; focus-visible unknown. Background transition is 0.2s linear.

**Transfer:** Use short destination nouns and a plain contact link rather than introducing a filled CTA.

### Navigation text action

**Use:** Link treatment for main actions.

**CSS:** `color: #000000; border-bottom: 2px solid #f2f2f2; transition: 0.2s linear`

**Text style:** `navigation` — telegraf 400 · 25px/1 · tracking 0.04em

**Observed:** The invisible baseline border preserves a minimal text-only presentation.

**States:** Declared: hover color #000000 and text-decoration underline; focus-visible unknown.

### Media caption

**Use:** Identification beneath gallery media.

**CSS:** `padding-top: 18px; color: #000000`

**Text style:** `project-label` — telegraf 400 · 25px/1

**Observed:** A sans name and short phrase lead into a serif subtitle on the next line. Featured entries add the smaller slash-separated discipline line beneath; catalog entries omit it.

**Transfer:** Caption the actual demonstration with a specific name and format, keeping the mixed-family hierarchy.

### Discipline line

**Use:** Compact metadata beneath selected media.

**CSS:** `font-size: 15px; line-height: 30px; letter-spacing: 0.5px; color: #000000`

**Text style:** `discipline` — telegraf 400 · 15px/2 · tracking 0.033em

**Observed:** Lowercase descriptors read as one unboxed line, separated by spaced slashes.

### Invitation ticker

**Use:** A conspicuous invitation embedded among visual proof.

**CSS:** `height: 100px; border-top: 1px solid #000000; border-bottom: 1px solid #000000; overflow: hidden; position: relative`

**Text style:** `ticker-sans` — telegraf 400 · 55px/1.1 · tracking 0.0018em

**Observed:** A serif invitation joins sans destinations and arrows in a repeated horizontal track. The phrase intentionally exceeds the viewport.

**Transfer:** Change the destination and invitation to suit the product; preserve the two type voices and clipped continuation.

### Back to top

**Use:** Utility action at the end of long content.

**CSS:** `color: #000000; text-align: right; transition: 0.2s linear`

**Text style:** `body` — telegraf 400 · 20px/1.33333 · tracking 0.025em

**Observed:** Placed opposite ownership text immediately above the footer rule.

**States:** Declared: hover color #000000 and text-decoration underline; focus-visible unknown.

### Social destination

**Use:** Final row of outbound links.

**CSS:** `color: #000000; line-height: 15px; transition: 0.2s linear`

**Text style:** `footer-link` — telegraf 400 · 20px/0.75

**Observed:** Four destinations are spaced across the entire working width; outer links align to the page edges, inner links sit near thirds.

**States:** Declared: hover color #000000 and text-decoration underline; focus-visible unknown.

### Category filter

**Only for:** filterable galleries

**Use:** Narrowing a large image catalog.

**CSS:** `color: #868686; font-size: 20px; line-height: 30px; letter-spacing: 0.1px; transition: 0.2s linear`

**Text style:** `filter` — telegraf 400 · 20px/1.5 · tracking 0.005em

**Observed:** A wrapping text list sits in the upper-right third above the media. Slashes separate categories; the current selection is black serif, not a chip.

**States:** Declared: hover color #000000 and text-decoration underline; focus-visible unknown.

### Gallery arrow

**Only for:** company image sliders

**Use:** Previous and next image controls.

**CSS:** `width: 65px; height: 65px; border-radius: 50%; padding: 1px 6px; position: absolute; transform: translate(0px, -50%); transition: 0.2s linear`

**Observed:** Large white directional arrows overlay the far left and right of the image, vertically centered. The circular hit area has no visible circular fill.

**States:** Declared: active opacity 0.6; hover and focus-visible unknown.

### Related image link

**Only for:** case-study endings

**Use:** Continue browsing through adjacent stories.

**CSS:** `background-size: cover; background-position: 50% 50%; position: relative`

**Observed:** Two landscape thumbnails, each 665px × 383px at desktop, sit side by side beneath a serif directional heading. Their default appearance is image-led rather than a text-heavy card.

**Transfer:** Offer two genuinely related demonstrations with contrasting images.

## Imagery and graphics

### Identity artwork

**Use:** Large opening identity and smaller navigation mark.

**Observed:** A black high-contrast serif wordmark occupies a 436px × 95px artwork box at desktop; it feels sculptural but remains flat black, with no glow or color.

**Transfer:** Create a typographic artwork from the new product's own short name. Preserve the slender hairlines, substantial vertical stems and generous left-hand presence.

**Build:** Set the new name in a high-contrast display serif inside an SVG viewBox 0 0 436 95. Fit the lettering to the box using textLength or outlined paths, with black fill and no stroke. Use the same artwork at approximately 160px × 36px in the navigation; preserve proportions instead of stretching.

### Tactile synthetic still life

**Use:** Primary featured media and repeated product demonstrations.

**Observed:** Large sharp rectangles show carefully lit 3D objects: a faceted gold form against lilac reflective folds, bright rubbery volumes, iridescent liquid and balanced product compositions. Wide views alternate with close material details, and color remains entirely within the image boundary.

**Transfer:** Stage the product or an abstract model of its benefit as a convincing object. Minimum version: a high-quality photograph or render of one object with intentional backdrop, visible surface grain, broad soft highlights and a real contact shadow.

**Build:** Use a 3D or photographed set with one central object occupying roughly half the frame, a large soft key light above-left and a weaker colored fill. Add two or three secondary geometric props at contrasting scales. Give one material metallic reflections, another a satin or rubber finish and one translucent edge. Render the entire rectangular backdrop with the objects; do not substitute a page-level gradient.

### Interface as physical object

**Only for:** software case studies

**Use:** Hero demonstrations and themed image chapters.

**Observed:** A readable interface floats upright among miniature grassy islands, flowers, ribbons and everyday objects. Pink, blue, violet or mint studio worlds surround the UI; soft directional shadows and reflections make the composition physical. Full-width scenes alternate with square pairs and prop-only still lifes.

**Transfer:** Use the new interface as the central product, surrounding it with a small, coherent set of objects that express its use. A simpler acceptable version uses one readable interface plane, one ground platform and three contextual props rather than a generic floating dashboard.

**Build:** Place the interface on a slightly tilted rectangular plane at the center of a 3D studio scene. Use an oval or irregular ground platform below, one tall prop behind and smaller props around the sides; keep foreground props clear of essential UI. Apply a soft monochromatic or two-color environment and one broad key light so cast shadows share a direction.

### Playful inflated campaign

**Only for:** playful physical-product campaigns

**Use:** A distinct, vivid product world.

**Observed:** Serum bottles nestle among oversized purple and pink inflated shapes; translucent gummy fruit and floating bubbles appear against pink or lilac backgrounds. Macro views crop into caps and glossy surfaces; a three-image row isolates individual props.

**Transfer:** Choose physical metaphors for the product's ingredients or benefits, rendered with rounded glossy volume rather than flat iconography.

**Build:** Model three rounded organic forms at different scales with slightly uneven silhouettes, clear-coat highlights and soft subsurface shading. Stage one product between them on a seamless pastel background. Use shallow depth of field for close-ups and a matching orthographic prop study for the three-up row.

### Airborne luxury campaign

**Only for:** refined physical-product campaigns

**Use:** A quieter premium chapter distinct from the playful variant.

**Observed:** Pearlescent compact objects, fine powder and floating feathers occupy pale blue, blush, lavender and warm gold studio spaces. Edges are reflective and faceted, highlights are broad, and close-ups are cropped beyond the image frame.

**Transfer:** Translate the product's lightness or refinement into a sparse material study, using fabric, paper, fine particles or another relevant physical counterpoint.

**Build:** Use one faceted reflective object with two thin curved translucent surfaces placed at different depths. Light with a broad warm key and cool fill. For a particle scene, distribute tiny low-opacity points in a loose radial cloud behind the object, denser near the center and fading outward; keep the product silhouette legible.

### Process plates

**Only for:** design-system case studies

**Use:** Explain the visual rules behind an image family.

**Observed:** Neutral-backed graphic plates show compact palette stacks, a central scene with callout leaders and labels around it. The plates are designed media, not interactive site cards; their internal rounded swatches do not change the site's square media framing.

**Transfer:** Show a real system: palette, composition and material decisions. Keep the explanation diagrammatic and subordinate to the finished images.

**Build:** Create an SVG board with four vertical stacks of unequal swatch rectangles and small labels, or place one central artwork with thin horizontal leader lines to short annotations on either side. Use the project's actual colors, not a permanent marketing accent palette.

### Working environment photography

**Only for:** company pages

**Use:** Humanize an otherwise synthetic visual practice.

**Observed:** Wide interior photographs show glass partitions, pendant lights, plants, framed artwork and people passing through. Natural greys and whites are punctuated by violet light; plain white arrows overlay the image.

**Transfer:** Use real working spaces and process moments with architectural framing, avoiding staged headshot tiles.

### Icons

**Observed:** Iconography is sparse: text arrows act as punctuation in links and the ticker, while large white arrow silhouettes overlay sliders. A small star-like mark accompanies the vertical edge annotation.

**Transfer:** Prefer directional glyphs and simple custom SVG arrows over a library of feature icons; keep the annotation mark visually secondary.

## Section recipes

How recurring sections are built.

### First screen: Identity and staggered proof opening

**Observed:** On Gallery canvas, Fixed navigation places the action row across the right half of the top 60px. Below it, a large Identity artwork anchors the left third while a three-line opening statement fills the right half. The statement is 24px/26px sans with selected 24.5px serif phrases. The first rectangular media begins around 218px down, spans about two thirds of the working width and is 894px × 503px; its Media caption and Discipline line are visible before the 900px fold. The second, 436px-wide image begins much lower on the right and continues beyond the fold. A vertically rotated location/time annotation hugs the right edge. Layers are flat: grey canvas, black identity and prose, then vivid media, with fixed navigation above everything. The opening has navigation and contact links, not a separate button row.

**Transfer:** Use the new product name as the typographic artwork, put one clear positioning sentence opposite it and lead immediately with the strongest product demonstration. Without video, use a lit object photograph or render. Catalog pages instead open with a compact underlined heading pair and filters above three columns; company pages open with prose beside a roster; case studies open with a mixed-family title above full-bleed media.

**Avoid:** Do not replace this with a centered oversized slogan, paired capsule buttons and a symmetrical dashboard mockup. Do not move the first demonstration entirely below the fold.

**Text style:** `opening-statement` — telegraf 400 · 24px/1.083 · tracking 0.021em

### Staggered proof gallery

**Observed:** Featured-gallery uses alternating thirds, halves and two-thirds widths with 22px gutters. Each image has a Media caption and selected images add a Discipline line. Large negative spaces result from intentionally unequal top alignment, not empty cards.

**Transfer:** Arrange demonstrations by visual contrast and importance, keeping captions local to their images and varying aspect ratios.

### Mixed heading pair

**Observed:** A 40px/45px regular sans phrase is underlined, followed by an em dash and a 40.8px/45px flowing serif phrase. It sits on the same line when space permits, with around 20px below before media.

**Transfer:** Combine a functional title with a warmer descriptive continuation; reserve the underline for the first phrase rather than underlining entire paragraphs.

**Text style:** `chapter-heading` — telegraf 400 · 40px/1.125 · tracking 0.0025em

### Split explanation

**Observed:** Explanatory-split separates a short 40px statement on the left from 20px prose on the right, with 80px top and bottom padding. The left statement often occupies only a third, leaving a deliberate gap before the right half begins.

**Transfer:** State the intent or benefit succinctly on the left and describe mechanism or experience on the right.

### Editorial broadcast pause

**Observed:** Invitation ticker occupies the Ruled invitation surface across the text container, using 55px sans and serif. It interrupts media with a continuous public invitation rather than ending the page as a conventional sales banner.

**Transfer:** Place the broadcast wherever the narrative needs a change of pace; the destination may be a collection, journal or community.

### Ruled utility ending

**Observed:** Ownership text is left-aligned and Back to top is right-aligned above Footer rule. Four Social destination links span the width below it. The canvas never changes color; the last proof image or final text list has room to breathe before the ending.

**Transfer:** Finish with restrained navigation and relevant destinations; let the visual content remain the climax.

### Immersive media chapter

**Only for:** case studies

**Observed:** Full-bleed-media alternates 1440px × 810px widescreen scenes, 1440px square close-ups and paired 710px square scenes separated by 20px. Short split text chapters interrupt long visual runs; stills, motion and process plates share equal prominence.

**Transfer:** Give each major product benefit a coherent visual world and vary the camera distance, rather than repeating one image beside a bullet list.

### People and capabilities

**Only for:** company pages

**Observed:** Two opening text columns pair 30px prose with a compact name list. Wide Working environment photography follows. Three parallel capability columns use 30.6px serif titles and 20px paragraphs, followed by a narrower image slider aligned to the right two thirds.

**Transfer:** Explain who makes the product and how the work happens; use real names and a small number of concrete capability chapters.

### Continuous recognition column

**Only for:** company proof lists

**Observed:** A mixed heading introduces a long right-side text column about 551px wide, leaving most of the left half empty. Each entry joins 25px/31px sans institution text to 25.5px/31px serif detail, with minimal separation rather than boxed awards.

**Transfer:** Use a similarly continuous list for verifiable recognition, press or credentials. Allow the contrast of date, institution and detail to do the organizing.

### Credits and onward images

**Only for:** case-study endings

**Observed:** A Credits heading sits in the left half while role-name lines in body type occupy the right. A generous pause leads to a serif previous/next invitation and two Related image links above the standard footer.

**Transfer:** Credit actual contributors or production details, then offer visually strong adjacent stories instead of adding a giant conversion panel.

## Page flow

**Storyline:** identity and positioning → visual proof → contextual explanation or deeper visual chapters → editorial invitation or credentials → onward navigation and a ruled utility ending

### Introduce an image-led product or creative offering

1. **Identity and promise** — Large identity artwork opposite a concise mixed-family positioning statement.
2. **Visual proof** — Staggered media in several sizes with two-family captions and small discipline lines.
3. **Invitation** — A large ruled ticker interrupts the gallery and points to fresh content.
4. **Closing navigation** — The final proof item gives way to the compact ruled footer and back-to-top link.

**Transfer:** Use the gallery as the primary argument and let short captions explain each proof.

### Help visitors browse a substantial catalog

1. **Orientation** — Underlined title with a warm serif continuation and right-side text filters.
2. **Exploration** — Three masonry columns preserve varied aspect ratios with consistent caption construction.
3. **Closing navigation** — Final media items remain in the masonry rhythm before the same understated footer.

**Transfer:** Use categories based on real visitor needs; retain image variety instead of uniform tiles.

### Build confidence in the people and practice behind an offering

1. **Introduction** — Prose on the left and a compact roster on the right under paired headings.
2. **Human proof** — Wide working-space image slider.
3. **Capability chapters** — Three prose columns and a second, right-aligned slider.
4. **Credentials** — A short personal statement leads into a dense, right-hand recognition list.
5. **Closing navigation** — Recognition concludes directly above the ruled utility ending.

**Transfer:** Substitute authentic people, process and credentials without changing the editorial hierarchy.

### Explain a coherent software imagery or product system

1. **Orientation** — Underlined product name plus serif project description above full-width media.
2. **Intent** — Left-hand statement and right-hand explanatory paragraphs.
3. **Visual chapters** — Distinct emotional worlds are shown through hero scenes, palette plates, composition callouts and paired still lifes.
4. **Final visual proof** — The last chapter resolves in a pair of square interface still lifes.

**Transfer:** Build chapters around meaningful product experiences and use diagrams only when they reveal a real system.

### Present a multi-part physical-product campaign

1. **Orientation** — Mixed-family campaign title followed by a square full-width product scene.
2. **Context** — A split introduction establishes the relationship between two product worlds.
3. **Product chapters** — A bright inflated world and a softer airborne world alternate macro scenes, moving images and paired studies.
4. **Attribution** — Left-hand Credits title with detailed role-name lines on the right.
5. **Onward navigation** — Two adjacent-story thumbnails lead into the ruled footer.

**Transfer:** Keep campaign worlds distinct, joined by the same typography and editorial structure.

## Writing

Confident about craft, warm about collaboration, and visually specific. Functional labels are plain while explanatory prose is enthusiastic and sensory rather than aggressively promotional.

**Do not copy:** Do not reuse the NotReal identity artwork, client or campaign names, collaborator names, awards, dates, brand claims or project-specific copy. Replace them with truthful content and assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the maker's intent and process. Address the reader sparingly through invitations rather than constant second-person selling.
- **Rhythm:** Short noun-led captions and headings contrast with flowing explanatory paragraphs. Em dashes create bridges between the practical and expressive halves; slashes compress metadata. An occasional friendly exclamation is appropriate.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Identify the organization and connect craft, method and intended audience in one compact sentence. | About 25–35 words | “[Brand] is an independent design-driven creative house that combines craft, storytelling and technology to create work for global brands.” |
| Section heading | A functional noun phrase followed by an em dash and a warmer serif continuation. | 3–8 words | “Our Recent Work — Enjoy!”<br>“A little intro — About the studio” |
| Media caption | Name, short project phrase and em dash; follow with the type of work in a contrasting voice. | One or two short lines | “Vizio. More of everything —”<br>“Visual & Motion Toolkit” |
| Support paragraph | Explain the intended experience through concrete material, light and composition language. | One to three sentences | “Solidity & calmness are communicated by incorporating soft lights and cast shadows to create a peaceful & timeless visual experience.” |
| Action | Plain destination or a conversational invitation, with directional glyphs where useful. | 1–8 words | “Contact”<br>“Back to top ↑”<br>“Check out our latest news on instagram” |
| Metadata | Lowercase disciplines separated by spaced slashes. | 2–4 terms | “cgi / art direction / system” |

**Words and phrasing to use:** craft; storytelling; visual world; soft light; tactile textures; collaborating; system; playful; refined; meaningful

**Avoid:** 10x; revolutionary; disruptive; unlock your potential; seamless solutions; hurry; limited-time offer

**Rules:**

- Use precise descriptions of what an image or product actually does instead of stacking superlatives.
- Let the sans phrase identify and the serif phrase add mood or format.
- Use credits and verifiable credentials as proof rather than unsupported numerical claims.
- Keep action labels closer to editorial navigation than sales-funnel commands.

## Do's and Don'ts

### Do

- Keep the continuous canvas #f2f2f2, including the fixed 60px navigation bar.
- Preserve 44px desktop side insets and 22px gutters for inset content.
- Pair regular 25px sans captions with 25.5px serif subtitles.
- Keep the opening statement at 24px/26px and visually subordinate to the identity artwork.
- Use 80px text-chapter padding and 20px seams within full-width media runs.
- Retain both the 100px ruled ticker and the edge annotation as editorial signatures.
- Stage vivid imagery as clean, sharp-edged rectangles with tactile lighting.
- Finish long pages with a 1px rule, four distributed links and a right-aligned back-to-top action.

### Don't

- Do not introduce a permanent pink, purple or green site accent merely because that hue appears in product art.
- Do not turn the text-only 25px navigation actions into rounded filled buttons.
- Do not add card shadows, glass panels or rounded media shells to the flat gallery.
- Do not replace regular-weight mixed-family headings with bold all-sans titles.
- Do not apply the 55px ticker scale to every heading; chapter titles remain 40px.
- Do not normalize every featured image to the same aspect ratio or top alignment.
- Do not carry the process plates' rounded palette swatches into the site's card system.
- Do not expand the minimal footer into a dark multi-column sitemap or a large closing sales panel.

## Motion and responsive

### Motion

**Observed:**

- Links and many controls declare 0.2s linear transitions; the navigation background declares background-color 0.2s linear.
- The broadcast strip declares moveSlideshow with a 21s linear infinite loop.
- Navigation stays fixed while the image-led page scrolls; interior destinations use a serif active appearance.

**Transfer:**

- Keep the ticker continuously readable as a repeated track rather than a sequence of changing slogans.
- Let media motion supply the spectacle; text links keep their restrained underline feedback.

**Unknown:**

- Playback timing, scroll-reveal choreography and most easing assignments are not established.
- Focus-visible styling and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The desktop composition is defined at 1440px × 900px. Styles declare many width breakpoints, including 500px, 768px, 992px, 1170px and 1440px.
- Main inset containers have a 2648px maximum width; a 12-column layout supplies thirds and halves.

**Transfer:**

- On narrow layouts, stack the identity and statement, then alternate full-width demonstrations while keeping each mixed-family caption intact.
- Collapse masonry into fewer columns without forcing equal image heights.
- Move the vertical annotation into a short inline marking when it competes with readable media.
- Preserve the clipped ticker and its continuous phrase, allowing the invitation to remain larger than surrounding text.

**Unknown:**

- Exact mobile typography, spacing, navigation behavior and breakpoint-specific layouts are not established; the narrow-screen rules here are transfer guidance.
- No viewport-relative typography formulas are established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
