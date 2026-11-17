# Guglieri — objects on an editorial stage

## Overview

A stark, image-led portfolio language with the confidence of a design exhibition and the friendliness of a personal introduction. Black and white canvases, tightly packed grotesk headlines, miniature navigation and tactile three-dimensional objects produce a deliberately uneven density. It suits design-led tools, creative products and small teams with work worth showing; documentary photography gives the polished objects a human counterweight.

### Essentials

- The page reads from a right-hand stage: identity sits at the upper left, a 22px introduction and the 64px headline occupy the right half, while the left half stays open until the main artwork arrives.
- Headlines are compact verbal objects: 64px/68px grotesk, -0.04em tracking, sentence case and dense bold silhouettes; supporting editorial labels step down to 32px/1.2.
- Actions are almost mute: the default hero action is a white 180px × 40px capsule with a centered black arrow, 28px radius and no visible label, accompanied by 4px-high slide marks.
- Color belongs to things, not the page chrome: black and white dominate the canvas; saturated accents are concentrated inside the hero objects and small inline illustrations. A yellow word highlight is reserved for the light showcase variant.
- A tactile object spectacle must anchor the page: oversized white-faced, dark-edged extruded symbols rise from the bottom of a black 900px media stage. Without custom 3D assets, use layered SVG product symbols with bevel-like edges and hard sidewalls, not a generic interface rectangle.
- The ending is a destination, not a sitemap: a two-column contact band uses 32px text and 116px vertical padding, followed by edge-to-edge imagery with a 64px “Next —” destination title. Carry this image-link device into every new page.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage white | `#ffffff` | `--color-foreground` | text, action, background | Default headings, social links and hero action; canvas for light editorial and showcase variants. |
| Navigation gray | `#575757` | `--color-nav-muted` | text, link | Inactive dark-theme navigation. |
| Introduction charcoal | `#454545` | `--color-header-muted` | text | Low-emphasis introductory text and time line on the default dark canvas. |
| Deep neutral | `#1c1c1c` | `--color-deep-neutral` | text, surface | Inactive slide marks and dark prefix on an image whose light areas support it. |
| Stage black | `#000000` | `--color-canvas` | background, text | Default marketing canvas and dark media backing; primary text on light editorial variants. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light editorial sections and feedback forms | Editorial ink | `#111111` | `--color-ink` | text, action | Text and compact dark actions on light surfaces. |
| showcases and editorial proof | Object backing | `#f0f0f0` | `--color-tile` | surface | Flat square object tiles and date badges. |
| light editorial sections | Editorial gray | `#868686` | `--color-body-muted` | text | Long-form chronology descriptions and secondary captions. |
| light editorial openings | Inactive light headline | `#d1d3d6` | `--color-headline-muted` | text | De-emphasized words within light-theme display sentences. |
| light editorial pages | Light introduction gray | `#cfcfcf` | `--color-light-header-muted` | text, link | Light-theme introduction and inactive navigation. |
| dark archive openings | Inactive dark headline | `#333333` | `--color-dark-headline-muted` | text | Visible result of white at 0.2 opacity over black in split-emphasis display sentences. |
| light showcase openings | Word-marker yellow | `#ffdb00` | `--color-highlight` | accent, surface | A single rounded highlight behind one display phrase, not a conversion-button color. |

## Typography

- **Raveo Variable Variable** — All editorial text, headlines, navigation and captions. Compact contemporary grotesk with open counters and strong, tightly spaced display forms; body text has a much lighter visual texture than the headlines. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **Inter**. Use bold display cuts and regular body cuts to preserve the visual contrast; tune width before changing line breaks. Font stack: "Raveo Variable Variable", "Inter", Arial, sans-serif.
- **Inter Display** — Small live local-time numerals in the identity header. Neutral proportional sans numerals. If unavailable, use **Inter**. Font stack: "Inter Display", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Raveo Variable Variable | 1000 | 64px | 68px | -0.04em | Hero title, primary section heading and image-link destination. |
| next-prefix | Raveo Variable Variable | 1000 | 64px | 1 | -0.04em | The short prefix preceding the bold destination in the closing image link; keep its visual texture lighter than the destination. |
| contact-heading | Raveo Variable Variable | 1000 | 32px | 1.2 | -0.02em | Contact invitation, social links and editorial side labels; invitation appears lighter than social link names. |
| introduction | Raveo Variable Variable | 1000 | 22px | 26px | -0.02em | Header identity, location and short professional introduction. |
| clock | Inter Display | 400 | 22px | 26px | normal | Local-time numerals aligned inline with introduction text. |
| navigation | Raveo Variable Variable | 1000 | 14px | 1.6 | -0.02em | Navigation and archive row content. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| light showcases | collection-heading | Raveo Variable Variable | 1000 | 40px | 1.2 | -0.02em | Headings above smaller project collections. |
| light long-form editorial pages | editorial-lead | Raveo Variable Variable | 1000 | 28px | 1.3 | -0.02em | Substantial introductory prose in the right-hand column. |
| light long-form editorial pages | editorial-body | Raveo Variable Variable | 1000 | 18px | 1.4 | -0.02em | Chronology descriptions and organization names, distinguished by color and visual emphasis. |
| showcases and editorial proof | caption | Raveo Variable Variable | 1000 | 12px | 1.2 | normal | Two-line project labels, role metadata and date-badge numerals. |

**Notes:**

- Keep sentence case. Display tracking tightens to -0.04em; smaller editorial text uses -0.02em, with untracked 12px metadata.
- Headlines and social destinations have bold silhouettes, while the invitation, time/location and long paragraphs appear regular. Preserve that optical distinction when using the substitute family rather than applying one heavy cut indiscriminately.
- Split-emphasis display sentences use strong and muted words within one uninterrupted sentence; they are not separate headings or a rainbow text effect.

## Layout

**Density:** Airy at the level of the page, compact within navigation, metadata and archive rows. Broad empty left halves contrast with closely packed right-column headlines and near-touching object tiles.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Gap between title and secondary project caption. |
| 4px | Gutters between adjacent project tiles and between slide marks. |
| 8px | Navigation padding and caption horizontal inset. |
| 12px | Media-to-caption gap. |
| 16px | Default page side inset and header top padding. |
| 20px | Opening editorial top padding and feedback-card padding. |
| 24px | Hero action-to-slide-mark gap, image-link title side inset and editorial group spacing. |
| 40px | Hero headline-to-action separation. |
| 48px | Separation of broad editorial content groups. |
| 80px | Chronology section top space. |
| 104px | Bottom padding of short text-led openings. |
| 116px | Top and bottom padding of the contact band. |

### Containers and grids

- **page frame**: max width 1920px · side padding 16px. Wide page frame with narrow outer edges; hero and closing media bleed beyond this inset.
- **editorial halves**: 2 columns · gap 10px. Equal-width halves: left for identity or a sticky section label, right for headline, body or social links. At 1440px the right-hand opening text starts near the midpoint.
- **showcase grid** (only for light showcases): 6 columns · gap 4px · side padding 16px. Light-theme object index. Featured items span two tracks for three approximately 467px squares; ordinary items use one track for six approximately 231px squares.
- **chronology proof grid** (only for long-form editorial proof): 3 columns · gap 4px. Three approximately 227px square project images within the right-hand editorial column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | hero action | 28px |
|  | slide marks | 4px |
| showcases and editorial proof | object tile | 16px |
| chronologies | date badge | 20px |
| community feedback | feedback panel | 16px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default marketing page canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Objects and type sit directly on the canvas without a panel border, gradient or raised card.

**Transfer:** Make the object silhouette and type hierarchy carry the composition.

#### White editorial canvas · level 0

**Only for:** showcases and long-form editorial pages

**Use:** Alternate light treatment for dense collections and prose.

**CSS:** `background: #ffffff; color: #111111`

**Observed:** A direct theme inversion, retaining the same narrow margins and right-half alignment.

**Transfer:** Choose it for reading and catalog browsing rather than interleaving arbitrary light and dark feature bands.

#### Object tile · level 1

**Only for:** showcases and editorial proof

**Use:** Neutral backing for isolated product objects and interface thumbnails.

**CSS:** `background: #f0f0f0; border-radius: 16px; overflow: hidden; box-shadow: none`

**Observed:** Square image well, with the caption outside on the page canvas; no enclosing card outline.

**Transfer:** Center the artifact with enough breathing room to preserve its silhouette.

#### Word marker

**Only for:** light showcase openings

**Use:** Single emphasized phrase inside a display sentence.

**CSS:** `background: #ffdb00; border-radius: 100px; padding: 0px 32px`

**Observed:** A rounded backing extends beyond a short black phrase; it is not an action.

**Transfer:** Highlight a colloquial phrase about the product's process or outcome.

## Components

### Navigation link

**Use:** Compact persistent section navigation.

**CSS:** `padding: 8px; height: 38px; color: #575757; background: transparent; display: flex; align-items: center`

**Text style:** `navigation` — Raveo Variable Variable 1000 · 14px/1.6 · tracking -0.02em

**Observed:** A horizontal cluster starts at the left edge below the identity header and remains at the top during deeper reading. The current destination is white on dark; light-theme inactive items are pale gray and active items dark.

**Transfer:** Keep labels short and the cluster subordinate to the editorial content.

### Arrow capsule

**Use:** Main hero destination action.

**CSS:** `width: 180px; height: 40px; padding: 0px 40px; background: #ffffff; border-radius: 28px; backdrop-filter: blur(20px); display: flex; align-items: center; justify-content: center`

**Observed:** A black rightward arrow is the only visible content; slide marks sit beside the control rather than inside it.

**Transfer:** Provide an accessible destination name without adding a long visible button label.

### Slide marks

**Use:** Progress indicator beside the main hero action.

**CSS:** `display: flex; gap: 4px; height: 4px`

**Observed:** One white 60px bar and two dark 20px bars form a low horizontal strip; all ends use 4px rounding.

**Transfer:** Use the expanded white segment to make the active item obvious without dot pagination.

### Social text link

**Use:** Prominent stacked secondary contact destinations.

**CSS:** `color: #ffffff; text-decoration: none`

**Text style:** `contact-heading` — Raveo Variable Variable 1000 · 32px/1.2 · tracking -0.02em

**Observed:** Three bold names stack in the right-hand half while the lighter invitation and address occupy the left. On light sections these links use dark ink.

**Transfer:** Keep the link group short and use actual destination names.

### Next image link

**Use:** Large closing continuation destination.

**CSS:** `position: relative; display: flex; overflow: hidden; background: #000000`

**Text style:** `display` — Raveo Variable Variable 1000 · 64px/68px · tracking -0.04em

**Observed:** Edge-to-edge image with a title over the upper-left corner, inset 24px horizontally and 32px from the top. The prefix is lighter than the bold destination; imagery supplies the contrast rather than a boxed label.

**Transfer:** Link to a meaningful next chapter with a distinct photograph or object view.

### Project tile

**Only for:** showcases and editorial proof

**Use:** Repeated visual proof item.

**CSS:** `display: flex; flex-direction: column; gap: 12px; overflow: clip`

**Text style:** `caption` — Raveo Variable Variable 1000 · 12px/1.2

**Observed:** Object tile media comes first, then a title and muted category on two lines with a 2px gap and 8px left inset. The largest examples are square media above the same tiny caption treatment.

**Transfer:** Use a concrete artifact name followed by a two- or three-word format or category.

### Archive row

**Only for:** archives and resource indexes

**Use:** Dense, scannable linked proof.

**CSS:** `height: 46px; background: #000000; display: flex; align-items: center; overflow: hidden`

**Text style:** `navigation` — Raveo Variable Variable 1000 · 14px/1.6 · tracking -0.02em

**Observed:** Full inset width, divided into quarter-width date, quarter-width context and half-width title. Fine dark rules separate rows; a small arrow on linked entries is aligned at the far right.

**Transfer:** Adapt the columns to release date, category and resource name rather than turning entries into cards.

### Date badge

**Only for:** chronologies

**Use:** Date range paired with an organization or milestone.

**CSS:** `height: 32px; background: #f0f0f0; border-radius: 20px; position: relative`

**Text style:** `caption` — Raveo Variable Variable 1000 · 12px/1.2

**Observed:** A small centered date capsule aligns opposite an organization icon; widths vary from 64px to 98px.

**Transfer:** Keep the badge descriptive, not promotional.

### Feedback panel

**Only for:** community feedback

**Use:** Small visitor-message form over the lower media region.

**CSS:** `width: 280px; background: #ffffff; border-radius: 16px; padding: 20px; display: flex; flex-direction: column; gap: 8px`

**Observed:** A small colorful overlapping-note emblem precedes a compact invitation, helper sentence, two 40px-high pale pill fields and a dark pill submit control. The panel overlays the lower-right image without a full-page scrim.

**Transfer:** Use this only when public participation is part of the product; do not replace the main conversion action with it.

## Imagery and graphics

### Extruded object spectacle

**Use:** Signature visual anchor for the main marketing stage.

**Observed:** White-faced cursor and hand symbols with thick nearly black bevels and visible dark sidewalls cluster across the lower stage. They tilt independently in shallow perspective; small cyan, blue, green and magenta objects punctuate the otherwise monochrome mass. The artwork occupies much more area than the short headline and is cut by the lower viewport edge.

**Transfer:** Turn recognizable product actions or artifacts into a small family of tactile symbols. The minimum version is a well-composed set of layered vector objects with convincing extrusion and lighting, not a flat stock icon grid.

**Build:** Draw 6–10 distinct SVG silhouettes with white front faces and thick charcoal outlines. Duplicate each path behind its face with successive 1px diagonal offsets over about 16px to form sidewalls; use dark-to-mid-gray side shading, a narrow top-left highlight and soft black contact shadows. Rotate individual objects by different small angles and arrange a loose rising arc across the lower two thirds of the stage. Add one or two glossy colored disks; keep the ground black with no visible horizon.

### Documentary continuation

**Use:** Closing image-link device.

**Observed:** Wide, tightly framed photographs show a monochrome studio shoot, a physical award on a cutting mat, and a speaker facing an auditorium. Another ending uses an extreme side view of hardware against pale gray. These are full-bleed scenes rather than thumbnails, with the next-destination title overlaid at the upper left.

**Transfer:** Use authentic making, usage or product-detail imagery with a legible upper-left area. For a product without people or a studio, create a sharply lit macro product detail against a plain neutral backing.

### Isolated catalog artifacts

**Only for:** showcases and editorial proof

**Use:** Repeated square media wells.

**Observed:** Cameras, app icons, small devices, laptops and interface compositions float centrally on pale gray. Soft local shadows belong to the artifact image, not the tile. Some editorial thumbnails instead fill the square with a film frame or interface scene; all keep the same rounded boundary.

**Transfer:** Normalize varied proof into square frames, using contained objects where possible and deliberate full-frame scenes where context matters.

### Portrait diptych

**Only for:** people and company editorial pages

**Use:** Human introduction below a short text-led opening.

**Observed:** Two almost equal 702px-wide photographs sit side by side with a narrow seam and rounded upper corners: one dark environmental portrait and one softly lit close portrait against pale blue.

**Transfer:** Pair a contextual working image with a closer human portrait; retain the contrast in distance and light rather than using two interchangeable headshots.

### Inline visual punctuation

**Only for:** text-led editorial openings

**Use:** Small visual interruptions in a wrapped display sentence.

**Observed:** A small bridge illustration, speaker cutouts and an orange material-like object sit inline among words; a yellow rounded phrase marker appears in the light showcase treatment.

**Transfer:** Use one relevant symbolic object or cutout at roughly a line's height. It should help explain a phrase without becoming a separate illustration block.

**Build:** Place a transparent SVG or PNG inline in a wrapping flex text composition, vertically centered to the 68px line box. Give it the width of a short word and preserve its irregular silhouette; use a simple product-relevant emblem when custom illustration is unavailable.

### Icons

**Observed:** Sparse right arrows rather than a feature-icon system. Hero arrow is approximately 23px × 20px; archive arrows are 18px with a 2px rounded stroke. Theme contrast is black or white.

**Transfer:** Use a consistent simple arrow for navigation; reserve the elaborate tactile symbol family for the hero artwork.

## Section recipes

How recurring sections are built.

### First screen: Object stage opening

**Observed:** The first 900px contains a 140px identity header with 16px edges: name and local time on the left, a muted 22px introduction on the right. A fine horizontal division and miniature Navigation link cluster sit beneath. The black media stage begins after a 200px top region. A two-line white 64px/68px title occupies the right half, about half the page width; the left half remains empty. Arrow capsule and Slide marks appear 40px below the title. Behind and beneath them, the Extruded object spectacle rises across the lower width, with large objects visible in the first screen and continuing below it. The full stage is 900px high; the contact region is below the first screen.

**Transfer:** Default new marketing pages use this dark stage. Replace the symbols with a tactile vocabulary specific to the new product, retaining a concise right-half title and the large lower object mass. Text-led archive and editorial variants retain the identity header and right-half 64px title but use a four-line split-emphasis sentence; light showcases introduce the first large proof row within the opening screen.

**Avoid:** Do not center a headline above a small generic dashboard or fill the empty left half with a second sales paragraph. Do not move the main object into a bordered card.

**Text style:** `display` — Raveo Variable Variable 1000 · 64px/68px · tracking -0.04em

### Contact and image continuation

**Observed:** A contact band pairs the invitation and address at left with Social text link items at right. It has 16px side insets, 10px between halves and 116px top and bottom padding. Next image link begins immediately afterward, filling the width with a 64px prefix-and-destination title. The band stays black on the default dark treatment; light editorial variants keep the band white before the photographic or product-image destination.

**Transfer:** Close with one direct human-scale invitation and a visually substantial next chapter, not a dense multi-column sitemap.

**Text style:** `contact-heading` — Raveo Variable Variable 1000 · 32px/1.2 · tracking -0.02em

### Split-emphasis statement

**Only for:** text-led editorial and archive openings

**Observed:** A wrapped display sentence sits entirely in the right half with 20px top and 104px bottom padding. Strong words are black on white or white on black; other words use pale gray or white at 0.2 opacity. Inline visual punctuation shares the sentence baseline.

**Transfer:** Choose a few meaningful words to foreground within a coherent statement. Use a concrete quantity or role rather than a detached oversized stat.

**Text style:** `display` — Raveo Variable Variable 1000 · 64px/68px · tracking -0.04em

### Object collection

**Only for:** showcases

**Observed:** A right-half section title precedes Project tile entries spanning the full inset width. A featured row shows three large squares; secondary collections use six smaller squares on the showcase grid. The first section label uses display size, later collection labels use collection-heading.

**Transfer:** Separate flagship proof from a compact supporting index through tile scale, not through extra card decoration.

### Editorial label and reading column

**Only for:** long-form editorial pages

**Observed:** A 32px left-hand section label anchors a long right-column story. Introductory prose uses editorial-lead; the chronology changes to editorial-body in gray with small dark names and caption metadata. Date badge sits opposite a small organization icon; Project tile proof appears in three columns below the description. Thin separators divide milestones.

**Transfer:** Use the format for origins, capability history or implementation chapters; keep the left label stable while the right column develops.

### Ruled archive

**Only for:** archives and resource indexes

**Observed:** A display section title in the right half and a small date range lead into full-width Archive row entries. Tiny column labels organize the quarter/quarter/half alignment. Repeated rows form an uninterrupted list rather than separate cards.

**Transfer:** Use this treatment when breadth of proof matters more than individual imagery.

### Compact logo proof

**Only for:** long-form credibility pages

**Observed:** A small monochrome logo matrix occupies only the right half beneath the final chronology copy: seven marks per row, evenly allocated approximately 97px × 41px slots with 24px row gaps.

**Transfer:** Use an understated grayscale partner or compatibility matrix as supporting proof rather than a full-width promotional wall.

## Page flow

**Storyline:** Identity and context → focused statement or object spectacle → visible proof at the appropriate density → direct invitation → image-led continuation.

### Short image-led landing page

1. **Identity** — Two-column introduction with local-time detail and compact navigation.
2. **Product demonstration** — Right-half headline and arrow action above an oversized tactile object composition.
3. **Closing call** — Contact invitation paired with stacked social destinations.
4. **Continuation** — Full-width documentary image link with a large destination title.

**Transfer:** Keep a short landing page visually complete through a memorable product scene and a strong ending rather than adding generic benefit sections.

### Archive or resource index

1. **Quantified proof** — Split-emphasis sentence embeds a quantity and time span into the right-hand headline.
2. **Proof index** — Section heading, date-range detail and dense ruled rows.
3. **Closing call** — Dark contact band.
4. **Continuation** — Full-width artifact photograph with next-destination title.

**Transfer:** Translate breadth of experience into a useful dated catalog of resources, releases or appearances.

### Visual showcase

1. **Promise** — Light split-emphasis statement with a small inline object and yellow phrase marker.
2. **Flagship proof** — Three large object tiles with tiny captions.
3. **Supporting proof** — Smaller named collections in a six-column grid.
4. **Closing call** — Light contact band followed by a dark auditorium image destination.

**Transfer:** Use a large-to-small proof hierarchy for products, use cases or customer work.

### Long-form company or creator story

1. **Identity** — Light right-half introduction and a paired environmental and close portrait.
2. **Context** — Left section label and substantial right-column prose.
3. **Credibility chapters** — Long chronology with dates, icons, descriptions and compact three-column visual proof.
4. **Social proof** — Small grayscale logo matrix restricted to the reading column.
5. **Closing call** — Light contact band and pale-gray hardware-detail continuation image.

**Transfer:** Tell a substantive story through labeled chapters and tangible artifacts rather than converting every paragraph into a card.

## Writing

Direct, personal and craft-aware. Confidence comes from specific work, roles and duration, with occasional informal language that keeps the polished presentation human.

**Do not copy:** Do not reuse the person's name, email address, proprietary artwork, company affiliations, event history, customer logos, career claims, exact quantities or visitor quotations as claims for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Introductions shift between first-person statements and third-person biographical description. Closing language is an open invitation rather than an imperative sales pitch; the reader is rarely addressed as “you.”
- **Rhythm:** Short noun labels and compact destination names contrast with complete, multi-line introductory statements. Longer prose is reserved for the reading column; headline punctuation and occasional colloquialisms feel conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A concrete artifact or outcome, sometimes followed by where it is available. | 5–9 words | “Cursors available in Figma community” |
| Supporting introduction | Role, duration and specialization expressed as one informative sentence. | 20–30 words | “Designer and educator with two decades of experience specialized in designing products, digital experiences, and building overpowered teams obsessed with craft.” |
| Section label | Plain descriptive nouns rather than a benefit slogan. | 1–3 words | “All talks”<br>“Personal projects”<br>“Work Experience” |
| Closing invitation | Two linked purposes phrased as a friendly invitation. | 5–9 words | “Reach out to connect or collaborate” |
| Destination action | Arrow-only hero action; elsewhere direct destination names. | 0–2 visible words | “Next — About”<br>“LinkedIn” |
| Informal emphasis | A small maker's colloquialism inside otherwise direct prose. | 1–3 words | “final_final” |

**Words and phrasing to use:** design; craft; products; experiences; connect; collaborate; selected; recent; specific artifact names

**Avoid:** revolutionary; game-changing; unlock your potential; supercharge everything; enterprise jargon without concrete work

**Rules:**

- Write introductions as complete statements, not stacks of disconnected superlatives.
- Label proof with its actual name and format.
- Embed quantities in sentences and support them with an index or artifacts.
- Reserve warmth and informal phrasing for a few small moments rather than making every label a joke.

## Do's and Don'ts

### Do

- Keep the default canvas black with white 64px headlines.
- Align the principal opening copy to the right half while the identity anchors the left.
- Keep hero action geometry at 180px × 40px with a centered arrow.
- Use 16px page insets but let the hero and closing image bleed to the edges.
- Keep project captions at 12px/1.2 beneath square media, not overlaid on it.
- Use 4px gutters to make object collections read as a tightly edited contact sheet.
- Give the contact band 116px vertical padding and maintain its two-column balance.
- Carry the large image-link ending through both dark and light page variants.

### Don't

- Do not turn the yellow phrase marker into the default button treatment.
- Do not add broad colored section backgrounds around the tactile hero; color should live primarily within the objects.
- Do not give object tiles a card shadow or border; depth belongs inside their artwork.
- Do not increase all captions to 16px body copy; the contrast between tiny indexing and large artifacts is essential.
- Do not apply -0.04em tracking to metadata; 12px captions remain untracked.
- Do not substitute giant standalone numbers for the archive's sentence-based quantified statement.
- Do not make every link a capsule; social and navigation destinations remain text.
- Do not replace the closing image destination with a conventional legal-heavy sitemap.

## Motion and responsive

### Motion

**Observed:**

- The hero includes slide-progress marks, and the compact navigation remains visible during deeper reading.
- No action or surface hover, focus-visible or active visual state is established.

**Transfer:**

- Retain the static hierarchy of the object stage and expanded slide mark even when presenting a single deliberate still composition.

**Unknown:**

- Hero slide timing, object animation, easing and interaction triggers are not established.

### Responsive

**Observed:**

- Width breakpoint declarations occur around 810px and 1200px.

**Transfer:**

- Recommended adaptation: collapse the two-column editorial split into a single reading column while keeping identity before the headline.
- Recommended adaptation: reduce the object count in the lower hero rather than shrinking all tactile symbols into an illegible row; preserve the arrow capsule and the image-link ending.
- Recommended adaptation: reduce showcase columns while preserving square media and tiny external captions.

**Unknown:**

- Narrow-screen type sizes, exact grid counts, sticky-navigation behavior and mobile object arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
