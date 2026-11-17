# Trawelt — first-class graphic journeys

## Overview

An editorial consultancy style with the confidence of a graphic identity system and the warmth of a travel magazine. Black stages alternate with parchment and pale sage, while mint navigation and a grass-green ending give the experience an unmistakable signature. Fine serif phrases meet regular grotesk continuations, supported by architectural photography, colorful studio portraits and playful physical-object artwork. The density is low, with expressive objects and enormous numerals carrying as much weight as the copy.

### Essentials

- Headlines change voice mid-thought: pair Reckless Neue at 250 with Labour Grotesk at 400, both 53.2px/1.2, rather than using bold emphasis.
- The opening is a gallery, not a centered slogan: a 30.7px/1.2 promise occupies the upper-left 682px, above a centered 385px cream image frame with dimmed neighboring images extending beyond the edges.
- Navigation feels like joined luggage labels: four adjacent mint blocks, 72px high with 15px corners, sit inside an 18.3px fixed inset; conversion buttons are 52px high with 10.1px corners, never pills.
- Color lives in whole chapters: black dominates the default landing treatment, parchment and sage carry long editorial bands, and saturated green fills the entire 956px closing area rather than appearing as a scatter of accents.
- Physical graphic ephemera make the promise tangible: green ticket-like cards, a stamp and directional marks are staged on black; use a custom SVG card-and-seal composition when no physical product exists.
- Numbers become scenery: 435px regular grotesk chapter numbers with 0.8 line height and -31.5px tracking sit beside small descriptive labels and fine rules; the ending adds a running 53.2px invitation above a near-full-width black wordmark. Preserve both the overscale graphic device and the monumental ending for new content.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ticket green | `#2d9b4c` | `--color-green` | background, accent, action, text | Full closing band, printed graphic ephemera, main image-frame action and navigation hover. |
| Navigation mint | `#d3ffc3` | `--color-mint` | surface, action | Joined navigation panels across every theme. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Parchment | `#e7d5ba` | `--color-parchment` | background | Large explanatory and numbered capability bands. |
| Black ink | `#000000` | `--color-ink` | text, background, border | Default dark stage and light-section text; also rules, symbols and closing wordmark. |
| Half-strength ink | `#808080` | `--color-muted-copy` | text | Visible black at 0.5 over white for secondary explanations; on tinted bands keep black at 0.5 so the tint shows through. |
| Fine frame edge | `#cccccc` | `--color-fine-edge` | border, text | Black at 0.2 over white; use the alpha recipe over cream frames and mustard number rails so the underlying fill remains visible. |
| Editorial sage | `#e4e9dc` | `--color-sage` | background, surface | Editorial and case-study carousel bands. |
| Pale card green | `#eaefde` | `--color-pale-green` | surface, text | Primary button label; also the large audience detail card in the warm product variant. |
| Frame cream | `#efefe7` | `--color-cream` | surface | Three-part frame around the active opening image. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| warm AI product campaigns | Mustard | `#ce9f27` | `--color-mustard` | background | Full partnership, explanation and numbered-interaction bands. |
| warm AI product campaigns | Burnished ochre | `#a96d35` | `--color-ochre` | background | Audience-selector chapter behind the pale detail panel. |
| warm product campaign accordions | Detail ink | `#666666` | `--color-detail-copy` | text | Black at 0.6 over white for expanded compact panels. |
| light service catalogs | Parenthetical gray | `#999999` | `--color-parenthetical` | text | Black at 0.4 over white for parenthetical capability descriptions. |
| light service catalogs | Catalog rule | `#b3b3b3` | `--color-divider` | border | Black at 0.3 over white for capability-row bottom rules. |
| light editorial pages and dark-section text | White | `#ffffff` | `--color-paper` | text, background, surface | Text on black and alternate light canvas. |

## Typography

- **Labour Grotesk** — All body copy, navigation, numbers and the second phrase of paired headings. Open, regular-weight grotesk with round counters and a friendly editorial cadence. If unavailable, use **DM Sans**. Use 400; tune line breaks to the same width before changing size. Font stack: "Labour Grotesk", "DM Sans", Arial, sans-serif.
- **Reckless Neue** — The first phrase of paired headings and small printed taglines. Delicate high-contrast editorial serif; light and upright, not a decorative italic. If unavailable, use **Cormorant Garamond**. Use 300 and preserve the broad phrase widths. Font stack: "Reckless Neue", "Cormorant Garamond", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| chapter-number | Labour Grotesk | 400 | 435px | 0.8 | -0.0724em | fixed | Oversized ruled capability index. |
| heading-serif | Reckless Neue | 250 | 53.2px | 1.2 | normal | fixed | First phrase of major editorial headings. |
| heading-sans | Labour Grotesk | 400 | 53.2px | 1.2 | normal | fixed | Continuation of major headings and running closing invitation. |
| heading-small-serif | Reckless Neue | 250 | 42.7px | 1.1 | -0.01em | fixed | First phrase of compact explanatory headings and centered graphic introductions. |
| heading-small-sans | Labour Grotesk | 400 | 42.7px | 1.1 | -0.01em | fixed | Continuation of compact paired headings. |
| opening-frame-serif | Reckless Neue | 250 | 38.8px | 1.2 | -0.01em | fixed | Short opening-frame promise above the active image. |
| opening-frame-sans | Labour Grotesk | 400 | 38.8px | 1.2 | -0.01em | fixed | Active image category and concluding phrase in the opening frame. |
| lead | Labour Grotesk | 400 | 30.7px | 1.2 | normal | fixed | Opening promise, large positioning statements and recruitment heading. |
| editorial-body | Labour Grotesk | 400 | 28px | 1.2 | normal | fixed | Large explanatory paragraphs and editorial card titles. |
| section-label | Labour Grotesk | 400 | 22.8px | 1.3 | 0.01em | fixed | Sentence-case section labels and larger supporting copy. |
| text-link | Labour Grotesk | 400 | 22.8px | 1.1 | -0.01em | fixed | Underlined section actions. |
| body | Labour Grotesk | 400 | 20px | 1.3 | normal | fixed | Explanatory body paragraphs, article descriptions and lists. |
| caption | Labour Grotesk | 400 | 16px | 1.5 | normal | fixed | Names, roles, metadata and footer links. |
| button | Labour Grotesk | 400 | 16px | 1 | normal | fixed | Navigation actions and filled buttons. |
| ticker-aside | Labour Grotesk | 400 | 16px | 1.2 | normal | fixed | Small refrain between closing invitations and buttons. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| warm product campaigns | active-number | Labour Grotesk | 400 | 450px | 0.82 | -0.0395em | size 31.25vw | Selected oversized number alongside expandable product benefits. |
| warm product campaigns | inactive-number | Labour Grotesk | 400 | 60px | 0.82 | -0.0395em | size 4.16667vw | Small low-opacity alternatives in the number rail. |
| light service catalogs | catalog-row | Labour Grotesk | 400 | 22.8px | 1.2 | normal | fixed | Capability titles with a muted parenthetical qualifier. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Pair serif and sans at the same size and line height; the change of construction supplies emphasis without a weight increase.
- Major 53.2px phrases use normal tracking. Compact headings and frame text tighten to -0.01em; section labels instead open to 0.01em.
- The serif remains upright even where markup uses emphasis. Most reading text and all huge numerals remain regular weight.
- Only the campaign number rail has a confirmed viewport-based scale; use the other desktop recipes as the reference sizes.

## Layout

**Density:** Airy: very broad chapter breathing room contrasts with tightly joined navigation and image-frame segments.

### Spacing

| Value | Use |
| --- | --- |
| 18.3px | Navigation outer inset and accordion header vertical padding. |
| 26.6px | Page gutters, grid gaps and large panel padding. |
| 36.7px | Portrait caption offset, paragraph-to-action breathing room and chapter-row padding. |
| 56.7px | Large internal gaps and expanded compact-panel bottom padding. |
| 63.4px | Editorial heading-row to image-row separation. |
| 73.3px | Secondary chapter spacing and portrait row gaps. |
| 90px | Explanatory chapter top and bottom padding. |
| 126.6px | Large internal breaks and case-study top padding. |
| 186.7px | Major editorial chapter top padding and dark expertise section padding. |

### Containers and grids

- **page-container**: max width 1860px · side padding 26.6px. Centered wide container; at 1440px the content occupies about 1387px.
- **editorial-grid**: 12 columns · gap 26.6px. Organize asymmetrical text, portraits and editorial panels with large empty spans.
- **two-column-chapter**: 2 columns · gap 26.6px. Equal columns for narrative and giant numbered sequence.
- **opening-promise**: max width 682px. Upper-left opening promise occupies just under half the desktop width.
- **diagram-and-copy** (only for light explanatory pages): 2 columns · gap 26.6px. A 2:1 split gives conceptual line art two thirds of the width and narrow reading copy the remaining third.
- **portrait-wall** (only for team and culture pages): 2 columns · gap 26.6px. Two 503px-wide portrait columns begin after an empty left quarter of the page.

## Corner radius

| Element | Radius |
| --- | --- |
| navigation-and-frame | 15px |
| buttons-and-panels | 10.1px |
| carousel-controls | 50% |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default landing canvas and human-expertise chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat uninterrupted black; imagery and type float directly on the stage.

**Transfer:** Use negative space and image scale rather than raised containers.

#### Parchment chapter · level 0

**Use:** Numbered process and capability narratives.

**CSS:** `background: #e7d5ba; color: #000000`

**Observed:** Full-width matte warm neutral, with no enclosing border or round corners.

**Transfer:** Change the entire chapter surface, not individual tiles.

#### Sage editorial band · level 0

**Use:** Articles and case studies.

**CSS:** `background: #e4e9dc; color: #000000`

**Observed:** Low-contrast greenish paper supporting square photography and unboxed copy.

**Transfer:** Let the band unify the editorial group.

#### Green close · level 0

**Use:** Shared conversion and footer territory.

**CSS:** `background: #2d9b4c; color: #000000; overflow: hidden`

**Observed:** A single full-width saturated field houses the running invitation, small navigation and giant identity artwork.

**Transfer:** Keep all closing content on the same flat fill.

#### Cream segmented frame · level 1

**Use:** Active opening image and its split promise.

**CSS:** `background: #efefe7; color: #000000; border-radius: 15px; padding: 15px`

**Observed:** Three joined rounded segments form a top label, central image mount and bottom phrase/action; faint internal rules emphasize the seams.

**Transfer:** Use physical framing rather than a floating software window.

#### White editorial canvas · level 0

**Only for:** light company and service pages

**Use:** Alternate page theme.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Large open white areas behind object art and line diagrams.

**Transfer:** Keep the mint header and green closing system unchanged.

#### Warm campaign fields · level 0

**Only for:** warm product campaigns

**Use:** Extended product explanation and interaction.

**CSS:** `background: #ce9f27; color: #000000`

**Observed:** Mustard explanation chapters transition to an ochre audience-selector chapter.

**Transfer:** Keep the stronger earth colors confined to this campaign treatment.

#### Pale detail panel · level 1

**Only for:** warm product campaigns

**Use:** Selected audience image and benefit paragraph.

**CSS:** `background: #eaefde; border-radius: 10.1px; padding: 26.6px`

**Observed:** Broad two-column panel against ochre; photograph occupies its left half and copy its right half.

**Transfer:** Use a single substantial selected panel rather than a grid of small cards.

## Components

### Joined navigation

**Use:** Fixed cross-theme navigation.

**CSS:** `display: flex; justify-content: flex-end; align-items: center; height: 72px; background: #d3ffc3; border-radius: 15px`

**Text style:** `button` — Labour Grotesk 400 · 16px/1

**Observed:** Separate wordmark and circular-symbol blocks touch the long menu panel; the action is a fourth touching block. The surrounding fixed wrapper has 18.3px padding and sits above every chapter.

**Transfer:** Use the new identity as a wordmark plus compact symbol, retaining the joined-panel silhouette.

### Navigation action

**Use:** Persistent conversion entry.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 72px; padding: 0px 26.6px; background: #d3ffc3; color: #000000; border-radius: 15px`

**Text style:** `button` — Labour Grotesk 400 · 16px/1

**Observed:** Attached to the right end of the menu, visually distinct through its own rounded silhouette.

**States:** Declared: hover background #2d9b4c; focus-visible outline 0px and box-shadow 0 0 0 2px #fff,0 0 0 4px #000000.

### Primary button

**Use:** Conversion within the active image frame.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 52px; padding: 0px 10.1px; border-radius: 10.1px; background: #2d9b4c; color: #eaefde`

**Text style:** `button` — Labour Grotesk 400 · 16px/1

**Observed:** Compact text-only rectangle positioned beside the concluding frame phrase.

**States:** Declared: hover opacity 1 and background-color #000000; focus-visible outline 0px and box-shadow 0 0 0 2px #fff,0 0 0 4px #000000.

### Closing button

**Use:** Repeated conversion within the running footer invitation.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; height: 52px; padding: 0px 31.5px; border-radius: 10.1px; background: #000000; color: #2d9b4c`

**Text style:** `button` — Labour Grotesk 400 · 16px/1

**Observed:** Black rectangle alternates with large invitation text and a small refrain along the green rail.

### Section text link

**Use:** Secondary actions at chapter edges.

**CSS:** `position: relative; color: #000000; text-decoration: underline`

**Text style:** `text-link` — Labour Grotesk 400 · 22.8px/1.1 · tracking -0.01em

**Observed:** Plain underlined text, usually right-aligned opposite a section label. Dark sections reverse the text to white.

**States:** Declared: hover state unspecified; focus-visible outline 0px and box-shadow 0 0 0 2px #fff,0 0 0 4px #000000.

### Opening frame segment

**Use:** Top and bottom framing pieces around an active photograph.

**CSS:** `background: #efefe7; color: #000000; border-radius: 15px; padding: 15px; overflow: hidden`

**Text style:** `opening-frame-serif` — Reckless Neue 250 · 38.8px/1.2 · tracking -0.01em

**Observed:** The upper segment carries the serif phrase; the lower segment switches to sans and contains the Primary button. A faint 1px black-at-0.2 rule sits inside each join.

**Transfer:** Split one promise across the frame while the middle names the selected use case.

### Carousel arrow

**Use:** Article and case-study navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 80px; height: 80px; border: 6px solid #000000; border-radius: 50%; color: #000000; background: transparent`

**Observed:** A bold directional SVG fills the inner 68px; paired controls have a 15px gap. The unavailable previous arrow is faded to opacity 0.1.

**States:** Declared: hover outline none and background-color currentcolor; focus-visible outline 0px and box-shadow 0 0 0 2px #fff,0 0 0 4px #000000; active outline none.

### Editorial story card

**Use:** Feature an article in a horizontal carousel.

**CSS:** `display: grid; grid-template-columns: repeat(8, 1fr); gap: 26.6px; padding-right: 82.5px; overflow: hidden`

**Text style:** `editorial-body` — Labour Grotesk 400 · 28px/1.2

**Observed:** Wide square-edged photograph comes first, then a narrower column with title, muted Body description, small read link and category/date row. The next story's image peeks from the right. No separate card fill.

**Transfer:** Use an editorial subject photograph instead of a product dashboard thumbnail.

### Footer link cluster

**Use:** Compact navigation beneath the running invitation.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); gap: 26.6px`

**Text style:** `caption` — Labour Grotesk 400 · 16px/1.5

**Observed:** Three narrow link columns occupy only the left quarter; copyright aligns far right. A small two-font promise sits lower left above the huge identity mark.

**Transfer:** Keep utility navigation deliberately small so the final wordmark remains the dominant object.

### Capability accordion

**Only for:** light service catalogs

**Use:** Explain stages without a stack of filled cards.

**CSS:** `border-bottom: 1px solid rgba(0, 0, 0, 0.3)`

**Text style:** `catalog-row` — Labour Grotesk 400 · 22.8px/1.2

**Observed:** Each 65px closed row has a black title, gray parenthetical qualifier and right-edge plus. Header padding is 18.3px vertically. One expanded row reveals a Body paragraph and short bullet list, with minus indicator.

**Transfer:** Keep stage names brief and put precise capabilities in the expanded panel.

### Audience detail card

**Only for:** warm product campaigns

**Use:** Selected audience-specific benefit.

**CSS:** `display: grid; background: #eaefde; border-radius: 10.1px; padding: 26.6px`

**Text style:** `editorial-body` — Labour Grotesk 400 · 28px/1.2

**Observed:** Left photograph and right benefit statement share a broad panel; a rotated green postage stamp sits beneath the copy. Large audience names sit outside it on the ochre canvas.

## Imagery and graphics

### Opening photographic strip

**Use:** Default landing-page opening object.

**Observed:** Warm interiors and destination environments form a horizontal image strip across black. The active center image is bright and cream-framed; its neighbors are dimmed, smaller and cut by the viewport edges. The active object takes about one quarter of the page width.

**Transfer:** Show the new product's environments, outcomes or use cases with one sharply readable center image. For intangible software, use a crafted workspace or outcome illustration rather than a dense screenshot.

### Printed green ephemera

**Use:** Signature graphic statement on a black stage.

**Observed:** Two slightly rotated green ticket-like cards use black typographic printing, directional arrows, a postage stamp and fine material grain. They form a substantial centered composition under a paired heading.

**Transfer:** Create an original two-piece physical token of the new promise. Minimum acceptable treatment is a carefully typeset SVG composition with a custom seal and restrained grain.

**Build:** Use a roughly 488px by 368px SVG card beside a narrower 302px by 337px card. Give both rounded corners; rotate the broad card about -6deg and the narrow card about 3deg. Fill with ticket green, add black type, a thin outlined capsule and bent arrow; layer a small perforated-edge square seal. Apply very low-opacity monochrome noise clipped to the card surfaces.

### Monumental closing identity

**Use:** Signature final graphic on every page.

**Observed:** A black wordmark and circular symbol stretch across almost the full content width, about 1387px by 305px, on saturated green. It is artwork, not a normal text headline.

**Transfer:** Use the new product's own identity as equally large black vector artwork. If the identity is short, pair it with a simple original symbol to fill the width.

**Build:** Set an SVG viewBox matching the identity's proportions, width 100%, with black paths or heavy custom-set lettering. Align the wordmark and an outlined circular symbol on one visual baseline; retain about 26.6px side gutters and a small bottom clearance.

### Editorial environment photography

**Use:** Articles, use cases and customer proof.

**Observed:** Sunset silhouettes, saturated neon signage, architecture, palms and aerial waterfronts supply a magazine-like contrast to flat color fields. Article images are 10:7; case-study images are 4:3, with square edges.

**Transfer:** Use photographs that convey lived outcomes and atmosphere. Preserve natural color differences rather than applying a uniform green filter.

### Conceptual line diagrams

**Only for:** explanatory company, service and product pages

**Use:** Explain relationships without literal product UI.

**Observed:** Thin black circles, overlapping orbits, a square, endpoints and connecting lines sit directly on white or mustard fields. Tiny labels describe relationships; art occupies half to two thirds of the width.

**Transfer:** Translate the new product's relationships into two or three geometric forms with sparse labels.

**Build:** Use SVG with no fill and black strokes around 2px at desktop. Draw overlapping circles or a circle inscribed in a square; connect dots with straight diagonal segments and place small regular sans labels outside the shapes. Keep the backdrop identical to the surrounding chapter.

### Floating object posters

**Only for:** company, service and focused product openings

**Use:** Portrait-format media opposite a bottom-anchored heading.

**Observed:** A gray stickered cup floats over red fading to white; a key ring floats over a lime gradient; blue soap and its white carton float against deep blue fading to pale gray. Objects are tilted, realistically lit, and isolated inside hard-edged portrait rectangles.

**Transfer:** Choose a familiar physical metaphor for the new offering and render one sculptural still life with tactile material. A clean cutout photograph over a vertical color fade is the minimum substitute; match the soft transition rather than exact gradient stops.

**Build:** Use a 3:4 portrait poster with a two- or three-stop vertical gradient. Center a transparent object render, rotated about 15–25deg, leaving clear air around it. Keep the gradient inside the poster; add original small label or seal details rather than ambient page-wide glow.

### Studio portrait wall

**Only for:** people and expertise chapters

**Use:** Human proof against black.

**Observed:** Natural-color waist-up studio portraits use blue, red, purple, green, cream and ochre backdrops. Rectangular 3:4 images have no corner rounding; 16px names and muted roles sit about 36.7px below. Small expertise cards are 327px by 436px; culture-wall portraits are 503px by 671px.

**Transfer:** Use consistent lighting and framing but vary backdrop colors; stagger a few smaller portraits beside editorial copy for a landing page, reserving the dense wall for a team page.

### Icons

**Observed:** Graphic arrows and circular directional symbols, not a generic thin icon library. Carousel arrows occupy 68px inside 80px circles; a 52px circular symbol appears in navigation. Small decorative identity glyphs can sit inline with lead text.

**Transfer:** Use a small coherent family of bold black directional glyphs and original circular seals; reverse only where needed on black.

## Section recipes

How recurring sections are built.

### First screen: Framed gallery opening

**Observed:** Black stage beneath Joined navigation. A regular white Lead promise begins immediately below the header at upper left and spans just under half the width. Below a broad empty interval, a horizontal strip of environmental images crosses the entire viewport. The bright active image is centered in a 385px-wide Cream segmented frame, about 488px tall; surrounding images sit lower and dimmer behind it. The top frame phrase is Opening-frame-serif, the selected category and bottom phrase are Opening-frame-sans, and the Primary button shares the bottom segment. All of the promise, image, frame and action are visible within the first 900px; the stage ends around 864px, before the next graphic chapter.

**Transfer:** Use a short outcome promise and a central use-case gallery. If there is no photographic product, commission one polished environment illustration per use case and preserve the bright-center/dim-neighbor hierarchy. Focused product or editorial pages instead open with upper-left support copy, a paired 53.2px heading anchored near the lower left, and a right-hand portrait object poster; light editorial pages use white, while product campaigns may stay black.

**Avoid:** Do not turn this into a giant centered hero headline above a full-width dashboard or give every gallery image equal brightness.

**Text style:** `lead` — Labour Grotesk 400 · 30.7px/1.2

### Two-voice heading

**Observed:** Heading-serif opens the thought and Heading-sans continues it at equal scale, often on adjacent lines with about 3px between text boxes. Compact versions use the 42.7px pair. Long headings stay left aligned; graphic introductions can be centered.

**Transfer:** Write one connected thought that benefits from a change of voice, not two unrelated slogans.

**Text style:** `heading-serif` — Reckless Neue 250 · 53.2px/1.2

### Tangible promise stage

**Observed:** Black stage, centered compact two-font heading, green Printed green ephemera graphic about 90px below, then centered Lead explanation underneath. The graphic is substantially wider than a small illustration badge.

**Transfer:** Give the offering a memorable physical token and let it carry the brand promise.

### Ruled numerical chapter

**Observed:** Parchment chapter with narrative in the left half and a tall clipped sequence in the right half. Chapter-number numerals dominate the right, aligned with small stage labels and thin horizontal rules; the next number is partially visible. The narrative uses the two-voice heading and Editorial-body paragraphs.

**Transfer:** Use the monumental numbers as process or capability indices, not invented performance statistics.

**Text style:** `chapter-number` — Labour Grotesk 400 · 435px/0.8 · tracking -0.0724em

### Relationship explanation

**Observed:** A large Conceptual line diagram occupies the left two thirds; a narrow right column contains a compact two-voice heading, Body explanation and small monochrome partner marks. The light variant uses about 90px vertical padding.

**Transfer:** Describe how the product connects two domains using sparse geometry, not decorative charts.

### Expertise composition

**Observed:** Black stage, left-aligned two-voice heading and broad muted Lead copy, with isolated 3:4 portraits in narrow right-side columns and small Caption labels. A text link sits at a lower edge. The larger culture variant expands to a two-column portrait wall while keeping the left quarter open.

**Transfer:** Pair a statement of expertise with real people or a similarly tangible source of accountability.

### Editorial carousel band

**Observed:** Sage editorial band with Section-label at upper left and Section text link at upper right; a paired heading and Carousel arrow controls follow. Editorial story card puts a 589px by 412px photograph beside a narrow text column, with the next image peeking at the edge. Major top padding is 186.7px.

**Transfer:** Use this for useful editorial content or proof. A case-study variant uses a 53.2px sans title, large explanation and action at left with a 562px by 422px image at right.

### Expandable capability catalog

**Observed:** On white, Capability accordion occupies roughly two thirds of the width. A related editorial teaser and square environment photograph occupy the remaining third. The first row is expanded, with paragraph and bullets; subsequent rows remain compact.

**Transfer:** Adapt the stages to the new buyer's questions and attach one genuinely helpful related resource.

### Warm audience selector

**Observed:** On ochre, a full-width two-voice heading precedes short explanatory copy and large audience names at left. Audience detail card occupies the right two thirds with photograph, benefit statement and postage seal. The selected audience is black; alternatives are lower opacity.

**Transfer:** Reserve this warmer variant for a focused product campaign with clearly distinct use cases.

### Running invitation and monumental close

**Observed:** Green close is 956px tall. A full-width running invitation mixes Heading-sans text, Closing button and Ticker-aside in a clipped 157px-high band with 46.6px vertical padding. Below it, Footer link cluster sits left, copyright sits right, and a small paired-font promise precedes Monumental closing identity. Broad internal gaps, including about 126.6px before the utility row, let the enormous black identity artwork finish the page.

**Transfer:** Keep the running call and near-full-width identity in every adaptation, changing the invitation and the identity to fit the new product. This is a visual destination, not a conventional compact footer.

## Page flow

**Storyline:** Outcome promise → tangible brand metaphor → explanation and proof → capability chapters → human or editorial credibility → running invitation and monumental identity.

### Broad marketing landing page

1. **promise** — Framed gallery opening makes the outcome concrete through a selected environment.
2. **positioning** — Green printed ephemera on black and a centered explanation.
3. **social proof** — Brief partner introduction and a horizontal partner group.
4. **capability chapters** — Parchment narrative with monumental numbered stages.
5. **human credibility** — Black expertise composition with staggered portraits.
6. **editorial credibility** — Sage article carousel.
7. **closing call** — Green running invitation, compact utilities and monumental identity.

**Transfer:** Keep the alternation between graphic promise, precise explanation and tangible proof; adapt the number and order of chapters to the product.

### Company and culture narrative

1. **promise** — White object-poster opening with support above a lower-left paired heading.
2. **positioning** — Orbit diagram and narrow explanatory paragraphs.
3. **human credibility** — Black team introduction and extensive two-column portrait wall.
4. **participation** — Short white recruitment strip with direct email link.
5. **editorial credibility** — Sage article carousel.
6. **closing call** — Shared green invitation and monumental identity.

**Transfer:** Let the human proof expand for a company page; use an invitation to participate where it serves the new story.

### Focused product campaign

1. **promise** — Black object-poster opening.
2. **quantified proof** — Mustard partner row with a compact attributed statistic, not an oversized KPI.
3. **product explanation** — Geometric relationship diagram and large explanatory copy.
4. **capability chapters** — Mustard accordion plus a responsive-scale active-number rail.
5. **audience relevance** — Ochre selector and pale image-and-copy detail panel.
6. **human credibility** — Black expert portrait chapter.
7. **closing call** — Shared green ending.

**Transfer:** Use the earth-color variant as a coherent campaign, with substantiated proof and differentiated audience needs.

### Service or capability catalog

1. **promise** — White object-poster opening.
2. **method explanation** — Large line diagram beside narrow heading, copy and partners.
3. **capability chapters** — Hairline accordion with an editorial teaser alongside.
4. **customer proof** — Sage case-study carousel with large title and environment photograph.
5. **closing call** — Shared green ending.

**Transfer:** Explain method before details and show one substantial proof story rather than filling the page with service tiles.

## Writing

Assured, approachable and consultative. Business outcomes are expressed through a sustained physical-journey metaphor, while explanatory paragraphs return to practical capabilities and relationships.

**Do not copy:** Do not reuse the Trawelt identity, logo paths, proprietary graphic lettering, team names, partner logos, customer stories, attributed statistics, dates or business claims. Source examples illustrate tone only; use substantiated facts and original assets for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your' in promises; use 'we' for expertise and collaboration. Product names appear in explanations, not in every headline.
- **Rhythm:** Headings are short connected phrases, often split across two voices. Supporting statements run one to three sentences; longer advisory copy uses calm paragraphs. Actions are concise verb phrases, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An outcome for the reader, followed by how the business helps. | About 15–25 words | “Get the most out of your travel and hospitality business with tailored solutions and specialized consulting that give measurable results.” |
| Section heading | A human or journey phrase completed by a plain business meaning. | About 5–12 words | “Guiding the Expedition of Your Business Evolution”<br>“Driven by expertise United by the same purpose” |
| Supporting explanation | Start with an empathetic observation, then describe the value of a capable partner. | Two or three sentences | “Having a trusted partner during times of transformation is invaluable. That’s why you need someone who understands what lies ahead, knows the best routes, and has already traveled the road you're about to take.” |
| Primary action | A familiar low-pressure invitation. | 2–4 words | “Get in Touch” |
| Secondary action | Verb plus a clearly named destination. | 3–6 words | “Explore our services”<br>“Discover what sets us apart” |
| Closing refrain | Promise a fresh start, with a short contrasting reassurance alongside. | 4–10 words | “Your journey to business innovation begins here.”<br>“No Turbulence, only transformation” |

**Words and phrasing to use:** guide; journey; trusted partner; tailored; lasting; transformation; expertise; your business; personalized experiences

**Avoid:** crush the competition; 10x everything; disrupt or die; magic; unprecedented; hype-heavy superlatives

**Rules:**

- Choose one coherent metaphor appropriate to the new product and sustain it across headline, graphic object and closing refrain.
- Follow metaphorical headings with concrete operational benefits; do not let the body become a chain of slogans.
- Use sentence case for most actions and labels; do not add all-caps technical eyebrows.
- Distinguish a small attributed proof statistic from the giant numbers used as chapter indices.

## Do's and Don'ts

### Do

- Keep major heading pairs at 53.2px/1.2, with serif 250 and sans 400.
- Use the 26.6px gutter and gap consistently across the 12-column editorial composition.
- Join the 72px-high mint navigation pieces rather than separating them into floating pills.
- Keep the active opening frame near 385px wide and let neighboring media run beyond the viewport.
- Use 186.7px top breathing room for major editorial chapters and about 90px for compact explanations.
- Retain square-edged photography even when surrounding frame segments have 15px corners.
- Give chapter numbers 435px scale and small labels, not equal-size text and numeral columns.
- End with a full green field, running invitation and almost full-width black identity artwork.

### Don't

- Do not replace regular-weight headings with a bold startup-style sans hierarchy.
- Do not use pill radii for the 52px conversion buttons; their corners are 10.1px.
- Do not scatter mustard and ochre through the default dark-and-parchment treatment; they belong to the warm campaign variant.
- Do not add drop shadows or glass blur to flat editorial panels.
- Do not tint every photograph green; the varied natural and studio colors are part of the contrast.
- Do not turn 435px chapter indices into unsupported KPI claims.
- Do not enlarge the 16px portrait captions to compete with the faces.
- Do not shrink the final identity to a normal header-sized logo or pack the green closing area with dense utility content.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.2s cubic-bezier(0.55, 0.085, 0.68, 0.53) transitions.
- Editorial title underlines declare background-size 0.4s transitions.
- The campaign number rail declares font-size 0.4s cubic-bezier(0.445, 0.05, 0.55, 0.95) and color 0.2s cubic-bezier(0.39, 0.575, 0.565, 1).
- The closing invitation uses a horizontally translated repeating rail; the capability narrative includes a pinned, clipped numbered sequence.

**Transfer:**

- Animate selected imagery and numbered chapters as changes of focus, preserving the legibility of the surrounding editorial copy.
- Keep the closing invitation as a clipped repeated rail and retain the final identity as a stable full-width graphic.

**Unknown:**

- Running-rail speed, scroll choreography and animation durations beyond the declared rules are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 480px, 600px, 640px, 800px, 960px, 1140px, 1280px, 1440px, 1920px and 2048px.
- The active campaign number uses 31.25vw and inactive numbers use 4.16667vw.

**Transfer:**

- On narrow layouts, keep one active cream-framed image readable and allow only partial neighboring images rather than squeezing the full gallery into columns.
- Stack the narrative and numerical chapter while retaining a genuinely overscale index; keep the giant closing identity fitted to the available width.
- Treat these stacking choices as adaptation guidance, not fixed breakpoint recipes.

**Unknown:**

- Exact mobile navigation, portrait-wall collapse, typography scaling and pinned-section behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
