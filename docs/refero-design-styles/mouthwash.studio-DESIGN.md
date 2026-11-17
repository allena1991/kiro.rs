# Mouthwash Studio — image-led typographic ballast

## Overview

An image-led editorial style with the confidence of a cultural institution and the pacing of a portfolio. A pale gray canvas, black grotesk typography and subdued gray annotations leave photography, film and product art to carry the color. Dense, tightly stacked statements alternate with expansive image fields and unusually empty margins. It suits design-conscious products and organizations whose work can be shown rather than explained; an inverted black treatment supports deeper institutional stories.

### Essentials

- The first impression is a film frame, not a slogan-and-button stack: a centered 1100×619px media stage starts 130px down at desktop, inside a 1320px content field with 60px page gutters.
- Headings and declarations share one compressed speaking voice: Suisse BP Intl at 62px, weight 400, line height 0.85 and tracking -0.035em; even long introductory prose uses this scale.
- Actions look like tiny rectangular editorial tabs or unboxed text: navigation is 36px high with 2px corners and 10px 12px 8px padding; taxonomy chips use 12px type, 7.2px padding and 2px corners.
- The interface is entirely neutral; color is concentrated inside photographs and films rather than spread across buttons or section fills. The pale #f7f7f7 canvas remains visible around media, including 170px side margins around the opening stage.
- Proof is staged as artwork, with unequal image widths and tiny gray labels: pair 764px and 546px media across a 10px gap, then vary the pace with centered 1100px widescreen and 880px portrait fields. Use a carefully art-directed product photograph or typographic poster when film is unavailable.
- A monumental identity graphic is a required visual anchor: the closing mark spans 1320×415px above a 16px utility strip. Translate this to the new identity as fitted SVG lettering or a custom typographic silhouette, not ordinary footer-sized branding.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, background | Primary text and the closing identity on the light canvas; full canvas only in the institutional variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Taxonomy gray | `#f1f1f1` | `--color-chip` | surface, action | Small taxonomy chip fills, not large card backgrounds. |
| Annotation gray | `#767773` | `--color-secondary` | text, link | Project titles, chip text and secondary prose; also subdued links on the dark canvas. |
| Warm muted gray | `#9b9c96` | `--color-muted` | text, link | Large inline proof links, closing contact links and compact supporting descriptions on the light canvas. |
| Frosted active tab | `#eaeaea` | `--color-active-tab` | surface, action | Visible active navigation fill on the pale canvas, using rgba(220,220,220,0.5); the same translucent fill appears darker over black. |
| Pale gray canvas | `#f7f7f7` | `--color-canvas` | background | Default marketing canvas and all surrounding negative space. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| institutional and company-information pages | Dark-theme separator | `#666666` | `--color-rule-dark` | border | Hairline divisions between institutional chapters and columns. |
| institutional and company-information pages | White ink | `#ffffff` | `--color-inverse` | text, border | Headings, identity graphic and clock outlines on the institutional black canvas. |

## Typography

- **Suisse BP Intl** — All text, from major statements to taxonomy and footer utilities. A compact neo-grotesk with a large lowercase presence; regular weight feels forceful through tight spacing rather than bold cuts. If unavailable, use **Inter**. Use weight 400 and preserve the compressed tracking and line heights; check wraps manually. Font stack: "Suisse BP Intl", "Inter", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Suisse BP Intl | 400 | 62px | 0.85 | -0.035em | Major headings, introductory declarations, inline proof links and closing contact lines. |
| header-mark | Suisse BP Intl | 400 | 44px | 0.88 | -0.03em | Compact text identity in the fixed header; a custom logo may occupy the same visual role. |
| navigation | Suisse BP Intl | 400 | 20px | 0.9 | -0.03em | Header navigation and contact action. |
| index-label | Suisse BP Intl | 400 | 20px | 0.88 | -0.03em | Filter titles and closely stacked category links. |
| card-copy | Suisse BP Intl | 400 | 20px | 1 | -0.03em | Square editorial card titles and short descriptions. |
| project-caption | Suisse BP Intl | 400 | 16px | 0.88 | -0.03em | Small project names below media. |
| footer-utility | Suisse BP Intl | 400 | 16px | 1 | -0.0375em | Footer links, copyright and short address lines. |
| taxonomy | Suisse BP Intl | 400 | 12px | 0.9 | -0.04em | Taxonomy chips underneath project names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| project and resource archives | archive-title | Suisse BP Intl | 400 | 34px | 1 | -0.04em | Restrained archive heading beside tall filter lists. |
| institutional and company-information pages | institutional-body | Suisse BP Intl | 400 | 20px | 1.2 | -0.03em | Information headings, prose, lists and contact details in ruled columns. |

**Notes:**

- Use weight 400 throughout; the large x-height and negative tracking supply density without a hierarchy of bold weights.
- The 62px statement is deliberately more tightly led than body prose. Let headings wrap into compact two-line blocks while long declarations stretch across the full field.
- The closing identity is vector artwork, not the 62px text recipe. Fit it as one graphic while preserving its silhouette and aspect ratio.

## Layout

**Density:** Airy at section scale and compressed within labels: large editorial pauses separate tightly stacked text and tiny chips.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Gap between taxonomy chips and wrapped chip rows. |
| 10px | Image-grid gutters and the gap above editorial-card descriptions. |
| 12px | Vertical separation between project captions and taxonomy. |
| 16px | Project media to caption spacing. |
| 18px | Square image to editorial-card title spacing. |
| 20px | Header top and bottom padding, media-row separation and footer utility offset. |
| 60px | Desktop page gutters and section-heading to square-card grid separation. |
| 80px | Opening media to introductory statement. |
| 90px | Vertical separation between institutional column rows. |
| 120px | Institutional chapter to following media spacing. |
| 160px | Editorial heading/filter row to selected imagery; also institutional chapter pauses. |
| 240px | Major pauses around the work collection, capability heading, editorial-card collection and contact section. |

### Containers and grids

- **page-field**: max width 2000px · side padding 60px. Centered page field; at a 1440px window the usable width is 1320px. The composition is edge-aligned, not a narrow centered reading column.
- **opening-stage**: max width 1100px. Centered widescreen film or campaign image, narrower than the main field.
- **editorial-pair**: 2 columns · gap 10px. Unequal columns: 764px and 546px in the first pairing; another pairing uses 437px and 873px. Align image tops rather than equalizing bottoms.
- **square-editorial-grid**: 4 columns · gap 10px. Four 323px square images with titles and descriptions, occupying the full field.
- **archive-grid** (only for project and resource archives): 3 columns · gap 10px. Three roughly 433px media-led cards with generous 120px row gaps; compact metadata lives outside the image.
- **institutional-columns** (only for institutional and company-information pages): 2 columns · gap 0px. The right half of the 1320px field contains two 330px columns; the left half remains empty or holds the chapter heading. Each column has 20px right padding and prose is capped at 340px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | tabs-and-tags | 2px |
|  | media | 4px |
| distributed-location information | clock | 50% |

## Surfaces and depth

### Surfaces

#### Pale canvas · level 0

**Use:** Default page background.

**CSS:** `background: #f7f7f7; color: #000000`

**Observed:** An uninterrupted pale field connects imagery and typography without alternating colored bands.

**Transfer:** Let media provide local color; retain the same canvas across the narrative.

#### Taxonomy tab · level 1

**Use:** Small linked classifications beneath media.

**CSS:** `background: #f1f1f1; border-radius: 2px; box-shadow: none`

#### Frosted navigation · level 2

**Use:** Compact header-link backing over passing content.

**CSS:** `border-radius: 2px; backdrop-filter: blur(10px)`

**Observed:** Default links are transparent; active links use rgba(220,220,220,0.5). Frosting belongs to individual links rather than an enclosing toolbar.

**Transfer:** Keep the header visually open while maintaining legibility over imagery.

#### Institutional black · level 0

**Only for:** institutional and company-information pages

**Use:** Long-form organizational narrative.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** White declarations alternate with gray body text and gray hairlines; media retains its original colors.

**Transfer:** Use as a complete page variant rather than random dark feature cards.

#### Ruled column · level 1

**Only for:** institutional and company-information pages

**Use:** Text groups and chapter divisions.

**CSS:** `border-top: 1px solid #666666; padding-top: 20px; padding-right: 20px`

**Observed:** No filled panel or outer border; the rule and whitespace establish grouping.

## Components

### Header mark

**Use:** Persistent identity link at the far left of the header.

**CSS:** `color: #000000`

**Text style:** `header-mark` — Suisse BP Intl 400 · 44px/0.88 · tracking -0.03em

**Observed:** A short identity anchors a 220px-wide left slot; navigation follows and contact is isolated at the far right. On the dark variant it is white.

**States:** Declared: hover opacity 0.5; focus-visible outline solid 2px with 2px offset.

### Navigation tab

**Use:** Primary navigation and the isolated contact action.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 10px 12px 8px; height: 36px; box-sizing: border-box; border-radius: 2px; backdrop-filter: blur(10px); color: #000000`

**Text style:** `navigation` — Suisse BP Intl 400 · 20px/0.9 · tracking -0.03em

**Observed:** Individual tabs sit in a fixed 79px header with 60px side gutters and 4px inter-tab gaps. The active item gains a translucent gray fill. In the dark variant inactive text is white, while the active tab has black text.

**States:** Declared: hover transform scale(0.985), color #000 and background-color #dcdcdc80; focus-visible outline solid 2px with 2px offset.

### Taxonomy chip

**Use:** Linked classifications below project captions.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 7.2px; background: #f1f1f1; border-radius: 2px; color: #767773`

**Text style:** `taxonomy` — Suisse BP Intl 400 · 12px/0.9 · tracking -0.04em

**Observed:** Chips wrap with 2px gaps and form a compact annotation layer, not a row of prominent CTAs.

**States:** Declared: hover transform scale(0.985) and color #000; focus-visible outline solid 2px with 2px offset.

### Project card

**Use:** Media-led proof in an editorial collection.

**CSS:** `position: relative; color: #767773`

**Text style:** `project-caption` — Suisse BP Intl 400 · 16px/0.88 · tracking -0.03em

**Observed:** A linked image or video leads, followed by its project name after 16px and taxonomy chips after another 12px. No enclosing colored card or shadow. Card dimensions and media aspect ratios vary between rows.

**Transfer:** Show the artifact, product or result at large scale; keep explanation in the tiny metadata below rather than overlaying a feature list.

### Square editorial card

**Use:** A compact collection of related products, resources or initiatives.

**CSS:** `color: #000000`

**Text style:** `card-copy` — Suisse BP Intl 400 · 20px/1 · tracking -0.03em

**Observed:** A square image with 4px corners leads; title follows after 18px, then a muted description after 10px. Text has 30px right padding. Four cards share a row without enclosing panels.

**Transfer:** Give each entry a distinct visual world but a consistent square frame and short description.

### Contact line

**Use:** Large, direct closing conversion action.

**CSS:** `position: relative; color: #9b9c96`

**Text style:** `statement` — Suisse BP Intl 400 · 62px/0.85 · tracking -0.035em

**Observed:** Two unboxed contact destinations stack directly under a black section heading. A 1px top rule with 15px top padding introduces the group. In the dark variant links use annotation gray and the rule uses dark-theme separator gray.

**States:** Declared: hover color #000; focus-visible outline solid 2px with 2px offset.

**Transfer:** Use a short real contact destination or direct next-step label; retain the oversized text-link treatment.

### Identity footer

**Use:** Monumental closing identity and compact practical links.

**CSS:** `padding: 0px 60px 20px; color: #000000`

**Text style:** `footer-utility` — Suisse BP Intl 400 · 16px/1 · tracking -0.0375em

**Observed:** A full-field identity SVG is 1320×415px at desktop. After 20px, a utility row places copyright at left, a three-link stack beginning around the midpoint, and an address in the right quarter. Dark pages invert the graphic and text to white. The archive ends directly with this component rather than adding a contact chapter.

**States:** Declared: hover opacity 0.5 on utility links; focus-visible outline solid 2px with 2px offset.

**Transfer:** Fit the new identity into an equally emphatic single silhouette. Keep utility content small and subordinate.

### Information column

**Only for:** institutional and company-information pages

**Use:** Detailed capabilities, process, resources and practical information.

**CSS:** `border-top: 1px solid #666666; padding: 20px 20px 0px 0px`

**Text style:** `institutional-body` — Suisse BP Intl 400 · 20px/1.2 · tracking -0.03em

**Observed:** White heading above gray prose or a list. Small groups occupy the right half of the page, leaving the left half available for a much larger chapter title.

**Transfer:** Break detailed explanations into compact pairs rather than spanning the full page with small text.

### Location clock

**Only for:** distributed-location information

**Use:** A distinctive functional graphic paired with location details.

**CSS:** `position: relative; width: 310px; height: 310px; border: 1px solid #ffffff; border-radius: 50%`

**Text style:** `institutional-body` — Suisse BP Intl 400 · 20px/1.2 · tracking -0.03em

**Observed:** A numeral-free circular dial with thin hands, location title and address above, gray digital time below. Most dials are 310px across, with one 320px variant.

**Transfer:** Use only where local time is meaningful; preserve the spare dial instead of introducing a decorative dashboard.

## Imagery and graphics

### Campaign film stage

**Use:** Dominant opening object and occasional centered proof interludes.

**Observed:** A 16:9 frame presents a grainy black-and-white runner in motion with vivid red campaign typography integrated into the artwork. The image fills the frame with no device mockup or external decorative backdrop; corners are 4px.

**Transfer:** Use an art-directed film of the product in use with confident in-frame graphics. The minimum version is a sharply composed still or custom typographic campaign poster, retaining a strong subject and one concentrated media accent.

### Editorial proof images

**Use:** Large unequal project pairs and isolated portrait-format proof.

**Observed:** A pale, soft-lit fashion portrait in dark tailoring sits beside a green glass product jar on a pale green backing. Other placements change scale dramatically: centered widescreen films, a small-left/large-right pair and a tall centered image. Photographic detail and embedded identity belong to the artwork; surrounding UI stays neutral.

**Transfer:** Pair human use with close material or product detail. Match the soft light, controlled backing and decisive crop, while allowing each artifact its own palette.

### Square editorial covers

**Use:** The four-column collection of related offerings.

**Observed:** Images mix a fine particle-like symbol on black, a red-neon architectural exterior, a restrained typographic cover on gray, and a softly lit portrait against black. Each fills a square with consistent 4px corners.

**Transfer:** Mix abstract identity, place, typographic cover and people when appropriate. A minimum set can use original type-led cover designs and one strong photograph; consistency comes from framing, not a shared color filter.

### Monumental identity silhouette

**Use:** Required identity anchor near the page ending.

**Observed:** A heavy, tightly fitted black letterform silhouette spans almost the whole width, 1320×415px at desktop, with no surrounding box. It reverses to white on black.

**Transfer:** Create an original short wordmark or initial composition with equivalent visual mass. If the identity is long, use a compact monogram or fitted word sculpture.

**Build:** Use an SVG with a viewBox matching the fitted lettering bounds. Convert a heavy neo-grotesk wordmark to paths, tighten adjacent forms into a dense silhouette and scale the SVG to the content width. Use solid black on the pale canvas or white on black; no texture, shadow or outline.

### Warm architectural interlude

**Only for:** institutional and company-information pages

**Use:** A wide photographic break between text-heavy chapters.

**Observed:** A 1320px-wide interior image shows warm cream curtains, wood detailing, a pale wall and a branching plant; a deep red wall adds local color. The framing is immersive and materially specific rather than a team headshot strip.

**Transfer:** Photograph a real place or environment connected to the product with soft daylight and tactile materials. Preserve the generous width and avoid generic office stock.

### Unnumbered time dial

**Only for:** distributed-location information

**Use:** Functional supporting graphic within location columns.

**Observed:** Thin white circular outlines and understated clock hands contrast with black; gray digital timestamps sit beneath.

**Transfer:** Rebuild as SVG or CSS tied to actual local time.

**Build:** Draw a 310px circle with a 1px white stroke and no fill. Pivot three narrow line elements at the center; use white for hour and minute hands and gray for the longer second hand. Leave the dial free of tick marks and numerals; place a 20px gray timestamp outside the circle below.

### Icons

**Observed:** The main interface is almost entirely typographic: navigation, chips and contact links have no prefixed icon. The strongest non-photographic forms are the identity graphic and location dials.

**Transfer:** Keep actions text-only rather than adding chevrons or a repeated feature-icon system.

## Section recipes

How recurring sections are built.

### First screen: Film-first opening

**Observed:** The pale canvas sits behind a fixed, open header: compact mark at left, a small navigation cluster just beyond it, contact at the right edge. A centered 1100×619px media stage begins 130px below the top, leaving 170px side margins at desktop and filling most of the first screen. Its image is the visual headline: monochrome running footage and red embedded campaign type, not a separate UI heading. After 80px, the full-width 62px introductory statement begins; within the first 900px only its first lines are visible. Supporting copy and inline proof destinations continue below the fold. There is no standalone hero button row.

**Transfer:** Lead with a film, photograph or original poster that demonstrates the new product's character, then place the concise positioning statement underneath. If no film exists, make a fully designed campaign still rather than an empty media well. Institutional pages instead open with a compact title on the left and a long 62px declaration whose first line begins in the right half before subsequent lines span the field; archives open with a 34px title beside text filters.

**Avoid:** Do not turn this into a centered slogan above two pill CTAs and a small mockup; the media is the opening's dominant object.

**Text style:** `statement` — Suisse BP Intl 400 · 62px/0.85 · tracking -0.035em

### Heading and index pair

**Observed:** A 62px heading forms a short stacked block at left. A small text action can sit beside it, while a category title and tightly stacked 20px filter list sit near the right edge. A 160px pause separates this header group from the proof images.

**Transfer:** Pair a broad promise or collection heading with a useful compact index, not a paragraph of equal visual weight.

**Text style:** `statement` — Suisse BP Intl 400 · 62px/0.85 · tracking -0.035em

### Variable-scale proof gallery

**Observed:** Project card components alternate unequal paired images, centered 1100px widescreen media, a 437px/873px pair and an 880px portrait. Gaps within pairs are 10px and row gaps are 20px; captions and chips sit outside the images.

**Transfer:** Choose ratios according to the content's strongest framing; use a few large compositional changes to make proof feel curated rather than tiled.

### Square editorial collection

**Observed:** A short stacked 62px heading sits 60px above the Square editorial card grid. Four 323px squares span the field, followed by black titles and muted descriptions.

**Transfer:** Use this for related resources, product families or complementary offerings; keep each description to a few short lines.

### Direct contact and monumental close

**Observed:** Contact line components begin under a 1px black rule with 15px top padding. A major 240px pause separates the contact content from the closing identity zone. The Identity footer supplies a 415px-high graphic and a small utility strip. Institutional pages use the same close in reverse; an archive moves from the last project row straight to the identity footer.

**Transfer:** Close a landing narrative with one or two direct next steps and an emphatic original identity graphic. Keep the archive ending shorter without inventing another sales section.

### Ruled institutional chapter

**Only for:** institutional and company-information pages

**Observed:** On Institutional black, a 1px gray rule precedes a 62px chapter title at left and a large declaration with an indented first line. Supporting Information column pairs occupy the right half with 90px between rows. Photographic interludes interrupt the text rather than appearing inside cards.

**Transfer:** Reserve this variant for deeper explanations and practical organization details; use a strong chapter-level statement before smaller supporting groups.

**Text style:** `statement` — Suisse BP Intl 400 · 62px/0.85 · tracking -0.035em

### Location information with live dials

**Only for:** distributed-location information

**Observed:** A large chapter heading occupies the left half. The right half pairs city/address text with Location clock components, then starts another ruled row below. The large black void at left makes the thin circles unusually prominent.

**Transfer:** Show equivalent operational context only when meaningful to the new organization, keeping the clocks functional.

## Page flow

**Storyline:** visual demonstration → positioning → curated proof → organizing perspective → adjacent value → direct next step → monumental identity

### Image-led marketing landing page

1. **Visual demonstration** — Large inset campaign film beneath persistent navigation.
2. **Positioning** — Full-width, tightly led declaration with muted inline proof links.
3. **Curated proof** — Heading/index pair followed by variable-scale project media.
4. **Capability framing** — Large heading against a compact list in the right half.
5. **Adjacent value** — Four square editorial cards.
6. **Closing action** — Ruled contact block and oversized text destinations.
7. **Identity reinforcement** — Monumental vector identity above tiny practical links.

**Transfer:** Adapt the proof and resource content to the new product; preserve media-led pacing and the strong closing identity without treating the exact section sequence as fixed.

### Institutional narrative and practical information

1. **Positioning** — White large-type declaration on black with first-line indentation.
2. **Practical orientation** — Right-half contact, capabilities and reference lists under a large chapter title.
3. **Method explanation** — Large statement followed by paired ruled text columns.
4. **Material context** — Wide architectural carousel.
5. **Broader value** — Large statement and compact paired descriptions.
6. **Operational reassurance** — Location information with large analog dials, then opportunities.
7. **Closing action** — Large contact lines followed by inverted monumental identity and utilities.

**Transfer:** Use the inverted variant for a substantive organizational story, not as the default appearance of an ordinary product landing page.

### Browsable project or resource archive

1. **Orientation** — Small archive title alongside two tall category lists.
2. **Evidence browsing** — Three-column grid of large media, tiny captions and linked chips.
3. **Identity reinforcement** — Final media row leads into the monumental identity footer without a separate contact chapter.

**Transfer:** Offer meaningful filters and a uniform grid when browsing matters more than editorial sequencing.

## Writing

Confident, culturally literate and declarative, with little sales pressure. Short organizational labels coexist with long, compressed sentences explaining a point of view.

**Do not copy:** Do not reuse the studio's names, initials, logo artwork, client roster, project identities, campaign slogans, addresses, email destinations, dates or claims of influence and tenure. Source examples illustrate cadence, not reusable claims.

- **Addressing the reader:** The organization usually names itself or uses we/our; the reader is rarely addressed directly. Actions use plain destination labels rather than persuasive second-person language.
- **Rhythm:** Section labels are usually one to four words; declarations are long sentences set as a dense visual paragraph. Card descriptions are one sentence, and practical lists use short noun phrases without promotional punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning declaration | Name the organization, define the practice and state its ambition in one sustained sentence. | About 25–45 words | “[Brand] is a design studio centered on new ideas and defining experiences, partnering with our generation’s leading brands and innovators to influence culture.” |
| Section heading | A compact noun phrase naming a collection or perspective. | 1–4 words | “Selected Work”<br>“A Holistic Approach”<br>“Our Ecosystem” |
| Supporting description | A concrete subject followed by its purpose; specific nouns do the work. | 12–25 words | “A dedicated space to explore new territories within art, design, and technology.” |
| Closing action | An ordinary invitation followed by direct contact destinations. | 2–4 words for the invitation | “Get in touch”<br>“View all” |
| Method description | Name the stage, then use a colon and active process verbs to explain its function. | 20–30 words | “The foundation: researching, questioning, and synthesizing insights into a clear, defensible position—grounding all creative decisions.” |

**Words and phrasing to use:** centered on; defining; approach; point of view; researching; work; explore; experiences

**Avoid:** game-changing; supercharge; unlock your potential; best-in-class; limited time; exclamation-heavy promises

**Rules:**

- Ground any ambitious claim in visible proof or a specific method.
- Use short destination labels for navigation and chips; let images carry emotion.
- Keep resource descriptions concrete and singular rather than stuffing each card with benefits.
- Use sentence case and ordinary punctuation; avoid an all-caps marketing label system.

## Do's and Don'ts

### Do

- Keep the default canvas #f7f7f7 and text black, with 60px desktop gutters.
- Set statements at 62px/0.85 with weight 400 and -0.035em tracking.
- Make opening media 1100px wide at a 1440px viewport, not full bleed.
- Use 10px gutters between major image columns and 2px gaps between taxonomy chips.
- Keep navigation tabs at 2px radius and media at 4px radius.
- Reserve 240px pauses for major editorial transitions rather than distributing all sections evenly.
- Keep project names at 16px and taxonomy at 12px so images remain dominant.
- Include a full-width fitted identity graphic above the small utility footer.

### Don't

- Do not introduce a bright interface accent; saturated color belongs inside media.
- Do not replace weight-400 declarations with a 700-weight heading hierarchy.
- Do not turn 2px navigation tabs into capsules or large filled conversion buttons.
- Do not add shadows or elevated card shells around the media-led project cards.
- Do not force selected proof into an equal-height three-column grid; that treatment belongs to archives.
- Do not make all copy 20px/1.2; that looser leading is reserved for institutional information.
- Do not scale the closing identity down to match the 44px header mark.
- Do not use the black institutional canvas as the default landing-page palette.

## Motion and responsive

### Motion

**Observed:**

- Navigation and taxonomy declare color and background transitions of .25s; text utility links declare opacity and text-decoration-color transitions of .25s.
- Navigation and chips declare hover scale(0.985); utility links declare opacity 0.5, and light-theme muted links turn black.
- Media declares opacity 0.2s linear. The opening is film-led and the institutional image section has carousel pagination.

**Transfer:**

- Keep hover changes small and concentrated on the individual text tab or link; do not animate an enclosing toolbar.
- When using a campaign film, keep its design self-contained inside the media frame.

**Unknown:**

- Opening reveal choreography, playback rules and carousel timing are not established.
- Other stylesheet easing curves are not assigned here to specific effects.

### Responsive

**Observed:**

- Stylesheet breakpoint boundaries include 768px, 1180px and 1920px, with additional intermediate thresholds.

**Transfer:**

- On narrower layouts, preserve the image-first opening and reduce gutters before shrinking the main object excessively.
- Stack unequal proof pairs and the right-half information columns in reading order. Let taxonomy wrap, and keep the closing identity fitted as one SVG rather than wrapping it like body text.

**Unknown:**

- Exact narrow-screen font sizes, gutter values, navigation transformation and media ordering are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
