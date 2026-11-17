# Break Maiden — punchy poster gallery

## Overview

A black gallery shell gives exuberant creative work room to shout. Towering condensed capitals, plain grotesk captions and occasional literary serif passages make it feel part poster, part design annual. Bright product photography and graphic identities supply the color, while the surrounding interface stays monochrome and sparse. It suits visually distinctive products, creative services and image-led launches.

### Essentials

- Headlines behave like illustrated posters: white Martin capitals at 152.8px, regular weight and 0.6 line height, interrupted by inline white arrows and bursts.
- The opening is deliberately lopsided: a roughly 896px headline block sits left, with a 382px support paragraph aligned near its lower edge at right; the first three image columns enter within the first 900px.
- Actions are typography, not capsules: 19.5px navigation links and 22.2px footer links sit directly on black without a filled button silhouette.
- The shell relinquishes color to the work: #000000 canvas, #ffffff type, #8e8e8e descriptive lines and #929292 inactive navigation surround vivid, square-edged media; no colored interface bands.
- Proof reads as a staggered image wall: three approximately 439px columns with 18px gutters, varied image proportions, and white-name/gray-tagline captions below rather than on top.
- Graphic punctuation is part of the voice: thin white arrows and radial stars must interrupt the headline or another major statement; use simple custom SVG line art when no product illustration exists.
- The exit is understated but definite: a 1px white rule spans the content width above copyright at left and a small social action at right; detailed showcases add a monumental arrow-led onward link.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Poster white | `#ffffff` | `--color-foreground` | text, link, border, accent | Headlines, active navigation, graphic linework and full-width rules. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Description gray | `#8e8e8e` | `--color-secondary` | text | Project taglines, supporting prose and metadata. |
| Gallery black | `#000000` | `--color-canvas` | background, surface | All page chrome and the space between media. |
| Navigation gray | `#929292` | `--color-nav-muted` | text, link | Inactive navigation, distinct from descriptive copy. |

## Typography

- **Martin** — Poster headlines and oversized onward actions. Very condensed, heavy-looking capitals with blunt ends; the regular cut delivers the visual force. If unavailable, use **Anton**. Use 400; tune width and line breaks to preserve the condensed poster silhouette. Font stack: "Martin", "Anton", Impact, sans-serif.
- **America** — Navigation, support paragraphs, project captions and footer. Unfussy regular grotesk; clean, spacious and deliberately secondary to the art. If unavailable, use **Inter**. Use 400 and normal tracking. Font stack: "America", "Inter", Arial, sans-serif.
- **Sectra** (only for editorial company sections and detailed showcases) — Narrative headings and running capability lists. High-contrast literary serif that softens the emphatic display face. If unavailable, use **Libre Caslon Text**. Font stack: "Sectra", "Libre Caslon Text", Georgia, serif.
- **Helvetica Neue** (only for store listings) — Product titles and prices. Neutral compact commerce typography. If unavailable, use **Arimo**. Font stack: "Helvetica Neue", "Arimo", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Martin | 400 | 152.8px | 0.6 | normal, uppercase | Main poster headline; compose short clauses across tightly stacked lines with inline graphics. |
| body | America | 400 | 22.2px | 1.5 | normal | Support paragraph and footer ownership line. |
| caption | America | 400 | 22.2px | 1.25 | normal | Project name, its gray descriptive line, small section labels and social action. |
| navigation | America | 400 | 19.5px | 1 | normal | Top-level navigation links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| detailed showcase endings | onward-display | Martin | 400 | 152.8px | 96px | normal, uppercase | Large continuation action paired with an even larger arrow. |
| editorial company sections and detailed showcases | editorial-heading | Sectra | 400 | 43.1px | 1.25 | normal | Sentence-case narrative headings, project title and comma-separated capability list. |
| store openings | store-intro | America | 400 | 24.6px | 1 | normal | Centered authorship line below the display headline. |
| store listings | product-title | Helvetica Neue | 400 | 19.5px | 0.75 | normal | Centered short product names under square artwork. |
| store listings | price | Helvetica Neue | 400 | 14.3px | 1.2 | normal | Price directly below the product title. |

**Notes:**

- Keep regular weights throughout: the display face itself supplies the heavy silhouette, rather than a bold body hierarchy.
- Normal tracking is shared across the scale. Compression comes from the display face and exceptionally tight leading, not negative letter spacing.
- The display face has unusual vertical metrics. When substituting, match the visible cap height and prevent collisions between stacked lines instead of blindly reproducing its line box.
- Gray project descriptions remain upright; their hierarchy comes from color, not italic styling.

## Layout

**Density:** Airy around statements and sections, tightly packed inside captions; large uninterrupted image fields carry most of the information.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Store title-to-price separation. |
| 14.4px | Store item internal link gap and metadata separation. |
| 18px | Gallery gutters, image-to-caption separation and detailed showcase image gaps. |
| 28.8px | Store column gutter. |
| 43.2px | Desktop side inset, navigation item separation and store row gap. |
| 106.8px | Opening allowance for the fixed header. |

### Containers and grids

- **gallery-container**: max width 1500px · side padding 43.2px. Broad centered desktop content field; headline, galleries and footer share the same side alignment.
- **staggered-gallery**: 3 columns · gap 18px. Independent vertical stacks of varied portrait, square and landscape imagery; at 1440px the image columns are about 439px wide.
- **editorial-split**: 2 columns · gap 18px. Title or section label on the left half, narrative copy on the right. Supporting imagery can occupy the opposite half farther down.
- **store-grid** (only for store listings): 3 columns · gap 28.8px. Three equal columns, approximately 432px wide, with 43.2px row gaps and square image areas.

## Corner radius

| Element | Radius |
| --- | --- |
| media-and-links | 0px |

## Surfaces and depth

### Surfaces

#### Black gallery canvas · level 0

**Use:** Continuous background for navigation, narrative, media gutters and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Sections do not switch to colored interface panels; the black field stays continuous.

**Transfer:** Let content imagery create contrast instead of introducing additional UI surfaces.

#### Unboxed media field · level 0

**Use:** Project tiles and full-width showcase panels.

**CSS:** `border-radius: 0px; box-shadow: none`

**Observed:** Images end in hard rectangular edges without a raised frame, surrounding border or card padding.

**Transfer:** Keep photographic backdrops inside the media itself; do not turn each item into a separate UI card.

## Components

### Navigation link

**Use:** Sparse top-level navigation.

**CSS:** `display: flex; align-items: center; padding-top: 1.9px; padding-bottom: 1.9px; color: #929292`

**Text style:** `navigation` — America 400 · 19.5px/1

**Observed:** A compact circular lettermark sits at the far left of a black 107px fixed header; four plain text destinations align at right with 43.2px separation. Current destination changes to white without a pill or underline.

**Transfer:** Use the new identity as a compact left anchor and keep destination labels short.

### Illustrated headline

**Use:** Main marketing statement.

**CSS:** `color: #ffffff; font-family: Martin; font-size: 152.8px; font-weight: 400; line-height: 0.6; letter-spacing: normal`

**Text style:** `display` — Martin 400 · 152.8px/0.6 · uppercase

**Observed:** Multiple tightly stacked uppercase lines share space with a parenthesized motif, long arrow and a star-like burst. Graphics live in the text flow rather than in a separate hero illustration.

**Transfer:** Break the promise into readable clauses and insert custom graphic punctuation at semantic pauses.

### Project caption

**Use:** Identification below gallery media.

**CSS:** `color: #ffffff; margin-top: 18px`

**Text style:** `caption` — America 400 · 22.2px/1.25

**Observed:** Two left-aligned lines: white project name above an upright gray phrase. Both use the same type size and leading.

**Transfer:** Pair a short product or capability name with a concise emotional or functional interpretation.

### Divider rule

**Use:** Footer and editorial section boundary.

**CSS:** `background-color: #ffffff; height: 1px; margin-top: 12.3px; margin-bottom: 12.3px`

**Observed:** The rule extends across the shared content width, not the viewport edges.

**Transfer:** Use as a section threshold rather than outlining every item.

### Social text action

**Use:** Small closing action at the far right.

**CSS:** `color: #ffffff; text-align: right`

**Text style:** `caption` — America 400 · 22.2px/1.25

**Observed:** The action wraps into two lines in the compact right-aligned footer column; the store keeps it on one line. Copyright and year occupy two lines at the opposite end.

**Transfer:** Keep one compact destination rather than a cluster of social icons.

### Store item

**Only for:** store listings

**Use:** Clickable digital goods listing.

**CSS:** `display: flex; position: relative; flex-direction: column; justify-content: space-between`

**Text style:** `product-title` — Helvetica Neue 400 · 19.5px/0.75

**Observed:** Square monochrome artwork above a centered title and smaller price; whole item is a link, with no separate purchase button. Preview art includes enormous letter specimens and white outline characters on black.

**Transfer:** Use one clear specimen per item with title and price below, preserving the open background.

### Onward project action

**Only for:** detailed showcase endings

**Use:** Large continuation into related work.

**CSS:** `color: #ffffff; text-align: center`

**Text style:** `onward-display` — Martin 400 · 152.8px/96px · uppercase

**Observed:** Display text anchors the lower left of a tall black section, while a huge thin arrow spans the right half above it. The combined graphic feels like an exit sign, followed by the shared ruled footer.

**Transfer:** For a related story or next product, pair a two-word directional label with an oversized bespoke arrow.

## Imagery and graphics

### Color-rich proof wall

**Use:** The dominant visual proof on ordinary marketing pages.

**Observed:** Product packaging, identity artwork, signage, flags, lifestyle hands and close-up material details alternate in a three-column staggered wall. Clean pastel studio stages sit beside saturated red, yellow and blue graphic fields and natural daylight scenes. Portrait and landscape frames vary, but none have rounded edges or text overlays.

**Transfer:** Art-direct several complementary views of the new product: one hero object, one in-use scene, one close detail and one graphic identity treatment. For nonphysical products, compose interface details or outcome artifacts against saturated flat backings rather than repeating browser mockups.

### Inline graphic punctuation

**Use:** Signature interruptions in the main statement and directional actions.

**Observed:** White outlined arrows, radial bursts and simple illustrative symbols occupy spaces between words. The main arrow is about 166px wide and 84px tall, while the small terminal star is much narrower. The linework contrasts with the dense condensed letters.

**Transfer:** Use an original symbol connected to the promise; a white eye, orbital loop or simple tool outline works without a complex illustration.

**Build:** Draw SVG on a transparent field: a horizontal white shaft with two open curved or angled branches at its right end, no enclosing circle; scale to 166px by 84px for inline use. Make a burst from 8–16 white radial strokes in a 45px by 84px box. Use approximately 2px strokes as design guidance and align each graphic optically with cap height.

### Studio campaign sequence

**Only for:** detailed product showcases

**Use:** Large almost full-width visual chapters.

**Observed:** Wide 1354px by 783px panels alternate full-frame scenes and seamless two-up compositions. A turquoise can is shown in pool water, on a pale cream tabletop, surrounded by ice and beside vivid pink props; tight label details alternate with playful small-scale set construction and a production-line photograph. Color remains in the artwork, separated by narrow black seams.

**Transfer:** Choose a coherent art-directed palette for one product story, then vary scale, use context, surface texture and making-of detail. Keep matching height in two-up panels; not every image needs its own paragraph.

### Monochrome people portrait

**Only for:** company storytelling

**Use:** Human context within editorial sections.

**Observed:** A straightforward black-and-white two-person portrait occupies roughly the left half of the content field below the opening narrative. Neutral gray backing and direct expressions replace the saturated product imagery.

**Transfer:** Use an honest team or maker portrait with soft even light, grayscale treatment and no decorative frame.

### Line-art capability assembly

**Only for:** company capability sections

**Use:** Illustrative counterweight to prose and a serif capability list.

**Observed:** A loose white-on-black assembly of faces, a pencil, nested shapes, an outlined letter frame, stacked planes, dots and a radial burst occupies the right side. Fine outlines coexist with a few solid white shapes.

**Transfer:** Create an original cluster of tools or process symbols, preserving line weight and irregular collage spacing rather than using a uniform icon grid.

**Build:** Assemble SVG groups in a tall rectangular field: two overlapping contour shapes near the center, a diagonal tool across the top, three offset parallelograms below, and a radial burst at the bottom. Use transparent fills, white outlines around 2px, and two solid white accent shapes. Leave black gaps between groups.

### Icons

**Observed:** Utility iconography is minimal. Arrows, stars, eyes and pictorial marks act as editorial illustrations rather than small interface controls; social navigation is written out.

**Transfer:** Prefer a short text link for navigation and reserve white custom linework for meaningful punctuation.

## Section recipes

How recurring sections are built.

### First screen: Illustrated poster opening

**Observed:** Black gallery canvas behind a 107px fixed navigation band, then a deep clear interval before the headline begins about 225px from the top. The Illustrated headline occupies roughly two thirds of the width in three lines within a roughly 896px by 300px block. White inline motifs break its dense strokes; a small star terminates the thought. A 382px support paragraph sits in the right third, aligned with the headline's bottom line, not its top. The opening section ends at about 617px; the proof wall starts about 43px later, so the first 900px includes the full statement, support and upper parts of three vivid images. Actions are the navigation and linked proof images, not a separate hero button row.

**Transfer:** Use a similarly short outcome-led promise with a white arrow and original symbolic punctuation. If there is no rich photography, construct bold graphic product or outcome specimens for the first three panels. Company storytelling uses the same left-led illustrated statement; stores center a single-line display heading with an authorship line; detailed showcases begin with a serif title and narrative split instead.

**Avoid:** Do not replace the asymmetrical composition with a centered SaaS headline, a pill CTA row and one floating dashboard.

**Text style:** `display` — Martin 400 · 152.8px/0.6 · uppercase

### Staggered proof gallery

**Observed:** Staggered-gallery layout on Black gallery canvas, with Unboxed media field images and Project caption beneath each. Images dominate; captions remain short and the independently paced columns create irregular black gaps.

**Transfer:** Present outcomes, artifacts or product variants as visual proof. Vary image proportions deliberately while preserving the 18px column seams.

**Text style:** `caption` — America 400 · 22.2px/1.25

### Ruled minimal footer

**Observed:** A full-width Divider rule within the side insets separates content from a compact two-ended footer. White copyright and year align left in body type; Social text action aligns right in caption type. A 59px black tail follows. The store leaves more black breathing space before the rule.

**Transfer:** Retain this low-density ending on new pages, with the new ownership line and one useful follow or contact destination.

**Text style:** `body` — America 400 · 22.2px/1.5

### Ruled editorial split

**Only for:** company storytelling

**Observed:** A Divider rule introduces a small sans section label at left and a 43.1px serif narrative heading with gray body copy in the right half. A grayscale portrait sits on the left farther down. The capability section reverses emphasis: gray prose and a large serif comma-separated list at left, Line-art capability assembly at right.

**Transfer:** Use this for provenance, approach or capabilities when the reader needs narrative detail rather than a gallery. Let one concise serif statement carry the section hierarchy.

**Text style:** `editorial-heading` — Sectra 400 · 43.1px/1.25

### Detailed showcase introduction and panels

**Only for:** detailed product showcases

**Observed:** A two-column introduction begins around 250px down: serif project title and gray discipline metadata on the left, white narrative paragraph on the right. The first wide media begins around 611px, followed by 1354px by 783px images with 18px black gaps and occasional integrated two-up scenes.

**Transfer:** Introduce the problem and the type of work briefly, then let a coherent sequence of hero, detail, use and production images explain the result.

**Text style:** `editorial-heading` — Sectra 400 · 43.1px/1.25

### Centered specimen catalog

**Only for:** store listings

**Observed:** A centered single-line display headline begins around 166px down. A 24.6px authorship line follows, then a three-column Store item grid. The 432px square monochrome previews blend into black; titles and prices are centered below. The last row remains naturally incomplete instead of stretching its remaining item.

**Transfer:** Use for a compact purchasable collection; keep specimen art readable and the selling metadata concise.

**Text style:** `display` — Martin 400 · 152.8px/0.6 · uppercase

### Directional showcase exit

**Only for:** detailed showcase endings

**Observed:** A tall black interval gives the Onward project action room: large condensed type at lower left and a 695px by 500px arrow graphic across the right. The shared footer follows rather than adding a newsletter panel.

**Transfer:** Turn the next story, product or collection into a clear visual direction instead of a conventional card.

**Text style:** `onward-display` — Martin 400 · 152.8px/96px · uppercase

## Page flow

**Storyline:** A forceful statement or compact introduction → visual proof or human context → deeper detail where needed → a directional next step → a spare ruled sign-off.

### Image-led marketing and work discovery

1. **Promise** — Illustrated poster statement paired with a short lower-right support paragraph.
2. **Visual proof** — Long three-column staggered gallery of colorful work with concise two-line captions.
3. **Sign-off** — Ruled ownership line and small social text action.

**Transfer:** Use the gallery as the main argument for visually differentiated products; let the artifacts demonstrate range rather than adding repetitive benefit cards.

### Detailed product or project story

1. **Context** — Serif title and metadata opposite a short narrative paragraph.
2. **Demonstration** — Wide art-directed image sequence, including paired views, graphic detail, use and production.
3. **Continuation** — Monumental next-project text and oversized directional arrow.
4. **Sign-off** — Shared ruled footer.

**Transfer:** Choose an image sequence that answers what it is, how it feels, how it works and how it is made, without requiring a caption on every panel.

### Browse a compact digital product collection

1. **Collection promise** — Centered condensed display title and short authorship line.
2. **Catalog** — Three-column square specimen grid with centered names and prices.
3. **Sign-off** — Open black space followed by the shared rule and social action.

**Transfer:** Keep the store visually related through black, white and typography, but use regular rows instead of the marketing gallery's stagger.

### Explain people, approach and capabilities

1. **Belief** — Left-aligned poster headline with eye, burst and arrow punctuation.
2. **Human context** — Ruled split section with serif narrative, gray supporting prose and grayscale portrait.
3. **Capabilities** — Another ruled section combines prose, running serif service list and white line-art collage.
4. **Sign-off** — Shared minimal footer without a large continuation action.

**Transfer:** Replace the subject with the new organization's story and useful capability groups while retaining the editorial contrast and human imagery.

## Writing

Confident and direct, with an occasional compact pun. The work speaks loudly while the interface copy stays plain; longer passages explain people and process without a hard sell.

**Do not copy:** Do not reuse Break Maiden's name, circular wordmark, horse artwork, client identities, product designs, founder history, dates, project claims or distinctive taglines. Source examples illustrate cadence only.

- **Addressing the reader:** The studio uses collective we in its strongest statements and third-person naming in descriptive copy. The visitor is rarely addressed directly.
- **Rhythm:** Headlines are brief declarative statements in capitals, often around 7–10 words. Captions pair a name with a 2–7 word phrase; body text is one compact paragraph, and actions use one or two words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero statement | Collective subject, active design verb and directional outcome. | 7–10 words | “WE HELP NEW & EXISTING BRANDS STAY AHEAD”<br>“WE USE DESIGN TO MOVE IDEAS FASTER FORWARD” |
| Support paragraph | Name the organization and its concrete specialty in one sentence. | One sentence | “[Brand] is an innovative creative studio that specializes in branding, packaging, and illustration” |
| Project tagline | Compact expressive interpretation of the work, not a technical specification. | 2–7 words | “A New Kind of Soda”<br>“Just Add Perspective” |
| Editorial heading | Plain sentence-case statement with a human or contextual fact. | One short statement | “A fast and efficient duo working together since 2018” |
| Action | Literal destination or next step. | 1–2 words | “Follow Us”<br>“NEXT PROJECT” |

**Words and phrasing to use:** active verbs such as help, move, make; directional language such as ahead, forward, next; concrete discipline names; short playful descriptive phrases

**Avoid:** growth-hacking jargon; long superlative stacks; technical marketing acronyms in headlines; pushy urgency language

**Rules:**

- Let a headline make one clear claim rather than enumerate features.
- Keep gallery captions shorter than the image is visually complex.
- Use sentence case for narrative headings and names; reserve capitals for poster statements and monumental actions.
- State capabilities as a running list when appropriate instead of inventing many tiny feature headings.

## Do's and Don'ts

### Do

- Keep the shell at #000000 with #ffffff primary text.
- Set project names and gray taglines at the same 22.2px size and 1.25 leading.
- Use 18px gallery gutters and hard rectangular image edges.
- Align major content and footer rules to the 43.2px desktop side inset.
- Maintain the contrast between 152.8px condensed display and 22.2px regular support text.
- Put graphic punctuation inside a major text statement, not only beside it.
- Use 43.1px regular serif headings for editorial variants.
- Finish with a 1px content-width rule and a small two-ended footer.

### Don't

- Do not replace black with a charcoal dashboard surface; the hard black is central to the gallery effect.
- Do not use gray navigation as the primary headline color; white carries the statements.
- Do not turn descriptive gray captions into pale boxed badges.
- Do not normalize every marketing image to an identical square; the stagger needs varied proportions.
- Do not add shadows or rounded corners to the proof wall.
- Do not bold the body and caption hierarchy; it is regular-weight and color-led.
- Do not apply the store's centered metadata treatment to the default project gallery.
- Do not add a large multi-column sitemap or colored subscription slab beneath the ruled sign-off.

## Motion and responsive

### Motion

**Observed:**

- The header is fixed and has a vertically hidden position during scrolling.
- No specific hover, focus-visible or active transition is established for the links.

**Transfer:**

- Keep any header movement subordinate to the poster and gallery; the layout must read clearly without motion.

**Unknown:**

- Reveal choreography, durations, hover behavior and transition easing for individual components are not established.

### Responsive

**Observed:**

- Styles define width thresholds at 767px and 768px.

**Transfer:**

- On narrow screens, preserve the headline's condensed silhouette and inline punctuation while reflowing clauses; place the lower-right support paragraph below it.
- Collapse the independent image columns into a readable vertical sequence while retaining hard edges and captions below.
- Stack the editorial title and narrative rather than shrinking the serif heading into caption size.

**Unknown:**

- Exact mobile font sizes, gutters, navigation pattern and gallery column counts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
