# Acne Studios — monumental material catalogue

## Overview

A fashion-editorial style that pairs an oversized identity with almost clerical interface text. White, black and small touches of deep blue frame tactile studio photography, cool architectural film and documentary editorial images. The interface is sparse and flat, while the images feel enveloping; it suits design-led objects, collections and visually distinctive products.

### Essentials

- Identity behaves like an exhibition title laid over objects: a black wordmark spans 1080px of a 1440px-wide stage, crossing the seam between two photographs.
- The opening is a diptych rather than a sales pitch: two flush 720px × 1080px portrait panels sit immediately beneath a 60px navigation strip, with 12px uppercase category labels at their top edges.
- Headings refuse conventional display hierarchy: section titles, navigation and category captions share regular 12px/20px grotesk with 0.3px tracking; the editorial introduction rises only to 18px/24px.
- Actions look like catalogue labels, not badges: transparent, square-edged text controls; navigation uses 4px 9px 33px padding within a 60px row, while service links occupy 24px lines.
- Color belongs primarily to the material being shown: white interface fields and black text dominate, with #0018a8 reserved for small service links and #007701 for tiny availability annotations, never broad promotional fills.
- Images alternate between monumental immersion and specimen-like display: flush 2:3 portrait pairs and a full-width 16:9 scene contrast with a four-column index using 10px gutters, 30px side margins and 60px vertical breathing room.
- A catalogue-style service ending grounds the spectacle: newsletter and service summaries precede four link columns, then two 30px utility strips separated by #f2f2f2 hairlines.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Service blue | `#0018a8` | `--color-link` | link, action, text | Service links, newsletter heading, social abbreviations and destination selector; small text areas only. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White field | `#ffffff` | `--color-canvas` | background, surface | Continuous page background and opaque sticky navigation. |
| Input mist | `#f7f7f7` | `--color-input` | surface, border | Flat email field fill and matching edge. |
| Fine divider | `#f2f2f2` | `--color-rule` | border | One-pixel separators and the navigation's inset edge lines. |
| Black ink | `#000000` | `--color-ink` | text, action | Primary text, identity artwork and navigation. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| live service availability | Availability green | `#007701` | `--color-available` | text | Superscript availability annotation beside a contact method. |

## Typography

- **Helvetica Now Text** — All navigation, headings, editorial copy and captions. Matter-of-fact neo-grotesk with open counters, a regular texture and slightly spaced small labels. If unavailable, use **Roboto**. Use regular 400 and retain the small positive tracking. Font stack: "Helvetica Now Text", "Roboto", Helvetica, Arial, sans-serif.
- **Helvetica Now Micro** (only for live service availability) — Very small availability annotations. Small-optical-size grotesk with sturdy, legible shapes. If unavailable, use **Roboto**. Use 500 for the tiny annotation. Font stack: "Helvetica Now Micro", "Roboto", "Helvetica Now Text", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| editorial-intro | Helvetica Now Text | 400 | 18px | 24px | 0.0167em | A compact editorial introduction beside a large image rail. |
| label | Helvetica Now Text | 400 | 12px | 20px | 0.025em, uppercase | Section headings, navigation, image categories and service headings. This is the default headline recipe; the monumental opening identity is separate artwork. |
| body-caption | Helvetica Now Text | 400 | 12px | 20px | 0.025em | Image captions and short service explanations in sentence case. |
| service-link | Helvetica Now Text | 400 | 12px | 2 | 0.025em | Sentence-case footer links and contact methods. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| live service availability | availability | Helvetica Now Micro | 500 | 8px | 1 | 0.037em | A small raised status word beside the service label. |

**Notes:**

- Hierarchy comes from placement, image size and whitespace rather than bold headings. Keep all ordinary text at weight 400.
- The opening identity is a graphic silhouette, not an oversized paragraph heading. It is 1080px wide and contained in a 211px-high image box at desktop.
- Uppercase belongs to navigation and categorical headings; descriptive prose and footer destinations retain sentence case.

## Layout

**Density:** Airy image-led composition with compact text cells; interface labels sit close to edges while whole image fields receive almost no surrounding furniture.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Top and bottom padding of compact copy cells. |
| 9px | Left and right padding of labels and ordinary text cells. |
| 10px | Index gutters, space before footer link groups and horizontal field padding. |
| 30px | Index side margins and utility-row height. |
| 60px | Index top/bottom padding, navigation height and service-band vertical margins. |
| 90px | Space after the footer link columns before the utility strips. |

### Containers and grids

- **Full bleed framework**: 16 columns · gap 0px · side padding 0px. A full-browser-width grid without a centered maximum-width wrapper. Large media groups occupy eight or sixteen columns.
- **Portrait diptych**: 2 columns · gap 0px · side padding 0px. Equal halves, each 720px wide at a 1440px viewport, containing 2:3 portrait media.
- **Discovery index**: 4 columns · gap 10px · side padding 30px. Four equally sized portrait tiles, about 338px × 506px at desktop.
- **Editorial split**: 2 columns · gap 0px · side padding 0px. One half for the introduction, one half for a horizontally scrolling image rail. The text occupies at most 75% of its half, or 540px at desktop; rail items are 432px wide.
- **Service columns**: 4 columns · gap 0px · side padding 0px. Four equal 360px footer columns with text inset about 10px from each column edge.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and controls | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Navigation edge rules | `inset 0px 1px 0px 0px #f2f2f2, inset 0px -1px 0px 0px #f2f2f2` | Two flat hairlines, not elevation, around the white navigation strip. |

### Surfaces

#### White canvas · level 0

**Use:** All ordinary text sections and footer.

**CSS:** `background-color: #ffffff; color: #000000`

**Observed:** The interface remains one continuous field rather than a stack of colored cards.

**Transfer:** Let image backdrops supply visual variety.

#### Ruled white band · level 0

**Use:** Transitions into the discovery index and footer.

**CSS:** `background-color: #ffffff; border-top: 1px solid #f2f2f2`

**Observed:** The separator is barely visible against the white field.

**Transfer:** Use a single edge to signal a functional change without enclosing each section.

#### Input field · level 0

**Use:** Email signup.

**CSS:** `background-color: #f7f7f7; border: 1px solid #f7f7f7; border-radius: 0px; box-shadow: none`

**Observed:** A pale rectangular field sits directly on the white canvas.

**Transfer:** Reserve this solid neutral treatment for editable controls rather than general-purpose cards.

#### Utility rule strip · level 0

**Use:** Bottom destination, copyright, social and preference rows.

**CSS:** `background-image: linear-gradient(#f2f2f2 1px, rgba(0, 0, 0, 0) 0px)`

**Observed:** A one-pixel top line is painted into the background of each flat strip.

**Transfer:** Keep the utility ending visually lighter than the photographic body.

## Components

### Sticky navigation

**Use:** Persistent access without competing with the media.

**CSS:** `position: sticky; top: 0px; height: 60px; z-index: 101; background-color: #ffffff; box-shadow: inset 0px 1px 0px 0px #f2f2f2, inset 0px -1px 0px 0px #f2f2f2`

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

**Observed:** Category destinations cluster at the left and search, help, account and bag at the right. A compact centered identity becomes visible in the scrolled state, leaving the large identity to the opening.

**Transfer:** Use a small set of category names and utility functions; preserve the broad empty center.

### Navigation text control

**Use:** Category and utility action.

**CSS:** `height: 60px; padding: 4px 9px 33px; color: #000000; background: transparent; border: 1px solid transparent; border-radius: 0px`

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

**Observed:** Text is top-biased rather than vertically centered; small icons precede utility labels.

**States:** Declared: hover color #051574; focus-visible unknown; active color #051574.

### Portrait media tile

**Use:** Large image-led category destination.

**CSS:** `position: relative; overflow: hidden; aspect-ratio: 2 / 3`

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

**Observed:** The entire tile is a link. Labels sit above the image near its top edge on large pairs; the discovery variant places its label at the lower edge. Adjacent large tiles meet without gutters.

**Transfer:** Use one strongly framed subject per tile, not a collage of tiny thumbnails.

### Discovery tile caption

**Use:** A short category identifier embedded at the bottom of a portrait index tile.

**CSS:** `padding: 7px 9px; color: #000000; border: 1px solid transparent; z-index: 15`

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

**Observed:** The label shares the image plane instead of sitting in a separate card footer. The object is centered above it with ample breathing room.

### Editorial caption

**Use:** Short factual explanation below an editorial photograph.

**CSS:** `padding: 4px 9px; color: #000000; border: 1px solid transparent; overflow: hidden`

**Text style:** `body-caption` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em

**Observed:** Caption follows the image directly and aligns to its width; it is not a promotional headline.

### Service text link

**Use:** Footer destinations and contact methods.

**CSS:** `color: #0018a8; line-height: 24px; background: transparent`

**Text style:** `service-link` — Helvetica Now Text 400 · 12px/2 · tracking 0.025em

**Observed:** Unadorned sentence-case links stack one per line below a small uppercase heading. A contact method can carry a tiny green superscript status word.

**States:** Declared: hover color #051574 and outline 0px; focus-visible unknown; active color #0018a8 and outline 0px.

### Newsletter input

**Use:** Low-pressure signup in the closing service band.

**CSS:** `width: 430px; height: 60px; padding: 19px 10px; background-color: #f7f7f7; border: 1px solid #f7f7f7; border-radius: 0px`

**Observed:** A standalone rectangular email field follows the newsletter heading and a short explanation; the initial presentation has no prominent filled submit button.

**Transfer:** Make the field fluid within its column on smaller layouts.

### Footer utility strip

**Use:** The final administrative ending.

**CSS:** `display: flex; height: 30px; background-image: linear-gradient(#f2f2f2 1px, rgba(0, 0, 0, 0) 0px)`

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

**Observed:** Copyright anchors the left, short social abbreviations sit centrally and destination/language sits at the right. A second ruled strip holds a sentence-case cookie preference link at the left.

**Transfer:** Use equivalent administrative destinations, keeping the ending flat and compact.

## Imagery and graphics

### Tactile product diptych

**Use:** Signature opening and large category stages.

**Observed:** Two full-height portrait photographs meet at a hard central seam. A burgundy leather object with silver hardware fills the left while folded sea-green wool fills the right, both against softly lit warm off-white studio backdrops. Surface wear, seams, fibers and soft cast shadows remain visible; the images carry almost all the first-screen color.

**Transfer:** Photograph two complementary views or product families on related neutral backdrops with soft directional studio light. For an intangible product, use two large physical display studies or carefully staged screen objects; the minimum is two deliberate, high-resolution still-life compositions, not a gradient.

### Identity overprint

**Use:** Required signature graphic across the opening media.

**Observed:** A single solid black identity spans three quarters of the page width and crosses both image panels. Its broad letter shapes remain crisp with no enclosing panel, shadow or outline.

**Transfer:** Set the new product's own short identity as a custom wordmark or a clean neo-grotesk title. Preserve the cross-panel overprint and emphatic width.

**Build:** Create an accessible SVG wordmark in black on a transparent viewBox; use a single text line or outlined letterforms, optical kerning and no effects. Contain it in a 1080px × 211px box at 1440px page width, centered horizontally above the diptych with z-index 10. Scale its width to three quarters of the viewport; allow the exact letter height to follow the identity's proportions.

### Studio specimen index

**Use:** Compact category browsing and secondary product groups.

**Observed:** Isolated jeans, a bag and a jacket are photographed front-on against very pale gray studio fields. Products occupy the center of tall 2:3 frames with visible space around them; all four panels share a common lighting and scale logic.

**Transfer:** Use consistently framed product specimens with a neutral photographic backing. Preserve the full silhouette and resist filling every available inch.

### Architectural film stage

**Use:** A broad immersive change of pace between portrait-led groups.

**Observed:** A full-width 1440px × 810px film still looks down a cool pale archive corridor. Strong symmetrical perspective, repeated vertical storage frames and fluorescent reflections lead toward a small object and ornate circular detail at the back.

**Transfer:** Use a 16:9 film or still of the product's making, environment or installation. Keep the camera composition restrained and spatially legible; a strong architectural still is the minimum equivalent.

### Documentary editorial rail

**Use:** Supporting stories beside the editorial introduction.

**Observed:** Tall photographs show real storefronts and installations with stone, glass, tiled floors and objects. Their denser natural texture contrasts with the clean studio imagery. Images are 432px × 648px, captioned below, and the next item is visibly cut by the horizontal rail edge.

**Transfer:** Show the new product in its cultural or working context through documentary images. Retain the 2:3 format, factual captions and visible continuation.

### Icons

**Observed:** Tiny black utility symbols, mostly 10px–12px, use thin 1px strokes with butt caps. Search, help, account and bag symbols sit immediately before their labels.

**Transfer:** Choose plain line icons with no colored discs, filled backgrounds or oversized touch-target artwork; enlarge the interactive area rather than the glyph.

## Section recipes

How recurring sections are built.

### First screen: Overprinted diptych opening

**Observed:** A white 60px Sticky navigation tops two flush 720px × 1080px Portrait media tiles. From back to front: neutral photographic backdrops, large tactile objects, top-edge category labels and a black Identity overprint crossing the central seam. The identity spans 1080px inside a 211px-high graphic box, positioned in the upper-middle of the media rather than on a separate text column. Within the first 900px, navigation, category labels, most of both products and the entire identity are visible. The portrait panels continue below the fold; no explanatory paragraph or filled call-to-action sits on the first screen. Category tiles themselves are the actions.

**Transfer:** Create two complementary visual studies of the new product and lay its own short identity across them. If no photography is available, commission or render two tactile still lifes on related neutral grounds. A focused product or editorial page can use one full-bleed scene instead, while preserving the large overprint and small corner labeling.

**Avoid:** Do not substitute a centered text hero with a slogan, supporting paragraph and pill-button pair, or place the identity in an opaque banner.

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

### Flush portrait chapter

**Observed:** Two equal-width 2:3 portrait images continue the full-bleed grid. Small uppercase category labels occupy the top edge; full-length studio figures are centered on pale neutral backgrounds.

**Transfer:** Pair complementary product views, use cases or categories with matched framing and light. Let the images communicate the difference rather than adding large section headlines.

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

### Immersive landscape interval

**Observed:** The Architectural film stage occupies the full width in a 16:9 frame, with no surrounding card furniture or descriptive text block.

**Transfer:** Use a broad environmental scene to change pace and reveal context without creating another written pitch.

### Inset discovery index

**Observed:** A Ruled white band holds a small uppercase title and four Portrait media tiles. Padding is 60px vertically and 30px horizontally; gutters are 10px. Each tile has a Discovery tile caption along its lower edge.

**Transfer:** Offer a concise visual index into the new product's categories, editions or applications. Use consistent studio specimens rather than a feature-card icon grid.

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

### Editorial half and rail

**Observed:** An uppercase label and 18px/24px introduction sit in the left half, restricted to 540px at desktop. The right half is a horizontally scrolling Documentary editorial rail with 432px × 648px images and Editorial captions below. The text stays near the top, leaving a substantial white field beneath it.

**Transfer:** Pair one compact contextual introduction with a small set of documented stories or applications. Preserve the asymmetry between a calm text field and a dense image rail.

**Text style:** `editorial-intro` — Helvetica Now Text 400 · 18px/24px · tracking 0.0167em

### Service directory ending

**Observed:** A Ruled white band begins a 572px-tall footer. The upper area has newsletter signup at left, open space, and two short service summaries on the right, with 60px margins above and below. Below are four equal columns with uppercase headings, 10px before Service text links, and 90px after the column group. Footer utility strip and a separate cookie-preference row close the page.

**Transfer:** End with a restrained subscription or contact route, useful service assurances and an organized link directory. Keep administrative functions visible rather than replacing them with an oversized closing sales statement.

**Text style:** `label` — Helvetica Now Text 400 · 12px/20px · tracking 0.025em · uppercase

## Page flow

**Storyline:** Visual identity → complementary product views → environmental immersion → category index → editorial context → service and utility closure.

### Image-led collection or product landing experience

1. **Visual promise** — A monumental identity crosses a two-image stage with minimal category labels.
2. **Product breadth** — Matched portrait panels show complementary categories or uses.
3. **Contextual immersion** — A full-width landscape scene provides a spatial change of pace.
4. **Wayfinding** — A four-column specimen index makes the range directly browsable.
5. **Editorial depth** — A small introductory text field accompanies a captioned image rail.
6. **Service reassurance and final access** — Newsletter, service summaries, four-column directory, destination selector and preference links form a practical ending.

**Transfer:** Adapt the number and order of visual chapters to the product. Preserve the contrast between expansive media, tiny categorical text and the useful directory-style ending.

## Writing

Reserved, editorial and factual. Confidence comes from naming objects and documenting activities, not from praising the product.

**Do not copy:** Do not reuse the Acne Studios identity, collection names, collaborator names, exhibition descriptions, contact information, dates or commercial promises. Replace every brand-specific claim and asset with truthful equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal category naming and third-person editorial description; functional instructions use short imperatives, with occasional 'your' in service explanations.
- **Rhythm:** One- or two-word headings, brief destination labels and plain service sentences. Longer editorial introductions use flowing sentences and lists rather than stacked advertising fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening identity | The identity itself carries the opening; no separate promotional slogan. | A short product or company name | “[Brand]” |
| Section heading | Plain catalogue or editorial category, displayed uppercase. | 1–2 words | “Discover More”<br>“News” |
| Editorial introduction | Name what is new and enumerate the kinds of activity without superlatives. | A short paragraph | “The latest from [Brand]. New editions of Acne Paper, books, exhibitions, store openings and collaborations — the cultural happenings of the house.” |
| Action | Literal destination or task rather than aspirational conversion language. | 1–4 words | “Contact us”<br>“Register a return” |
| Service support | A direct benefit followed by its practical scope. | One sentence | “Fast delivery and easy returns or exchanges on all orders” |

**Words and phrasing to use:** new editions; the latest; collection; curated; collaboration; receive news; contact; services

**Avoid:** revolutionary; game-changing; unlock your potential; ultimate; don't miss out; act now

**Rules:**

- Use category nouns where a conventional marketing page would use a benefit headline.
- Let descriptions say what the object or activity is, who made it and where it belongs.
- Keep service promises specific, literal and supportable.
- Retain sentence case for explanatory prose even when the associated heading is uppercase.

## Do's and Don'ts

### Do

- Keep normal section titles at 12px/20px, weight 400, with 0.3px tracking.
- Use flush 2:3 image pairs for large category stages.
- Carry the opening identity across both panels at about three quarters of the page width.
- Keep the navigation a 60px white strip with fine #f2f2f2 edge rules.
- Use 10px gutters and 30px side padding for the inset four-column index.
- Place 12px sentence-case captions directly below editorial images.
- Reserve #0018a8 for small functional text and links.
- Close with useful link columns and compact 30px utility rows.

### Don't

- Do not turn the interface blue; large chromatic fields belong inside photography, not service bands.
- Do not round media corners or build pill-shaped navigation controls; the geometry is square.
- Do not add floating-card shadows; the navigation effect is only a pair of 1px inset rules.
- Do not bold every heading to create hierarchy; ordinary labels stay at weight 400.
- Do not enlarge the 10px–12px utility glyphs into decorative feature icons.
- Do not add a centered maximum-width wrapper around the full-bleed media grid.
- Do not transform explanatory paragraphs and image captions into all capitals.
- Do not give every editorial image an enclosed card, colored footer or raised border.

## Motion and responsive

### Motion

**Observed:**

- The header stays sticky while the page scrolls; the large identity gives way visually to a compact centered navigation identity.
- Editorial image content has horizontal overflow scrolling, and its next item remains partly visible.
- Navigation and service links declare a darker blue hover color, #051574. No transitions or animations are established for these components.

**Transfer:**

- Preserve the persistent thin navigation and horizontal editorial continuation.
- Keep state changes chromatic rather than adding scale, lift or glow effects to catalogue links.

**Unknown:**

- The timing and mechanism of the identity's change in scale or position are unspecified.
- Video playback controls, autoplay behavior and animation timing are unspecified.

### Responsive

**Observed:**

- The desktop composition uses a sixteen-column framework with half-width and quarter-width spans.
- Width breakpoints include 767px/768px, 991px/992px and 1439px/1440px.

**Transfer:**

- On narrow screens, retain edge-to-edge portrait framing and small categorical labels; stack major portrait panels when two subjects would become unreadable.
- Scale the identity to the available media width while retaining its overprint role.
- Make the signup field fit its column and keep editorial images in a horizontal rail rather than shrinking all images to thumbnails.

**Unknown:**

- Exact mobile typography, navigation controls, column changes and identity placement are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
