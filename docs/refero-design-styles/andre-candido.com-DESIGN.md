# André Cândido — elegant type, playful objects

## Overview

A light, editorial style with exceptionally tall, delicate serif headlines and matter-of-fact grotesk supporting text. White and near-black establish a gallery-like setting, punctuated by buttery yellow proof panels and vividly colored project imagery. It suits creative services and products whose value benefits from visual demonstration, balancing sparse reading surfaces with exuberant graphic objects.

### Essentials

- Headlines behave like an oversized book jacket: Editorial New at 160px/1.1, weight 200, normal tracking, left aligned across a 1296px desktop content span.
- The opening is a typographic poster above a color-rich stage: a 71px fixed white navigation, 112px headline top inset, two-line title, and full-bleed imagery beginning around 496px; a circular text seal overlaps the boundary.
- Small actions contrast with monumental type: the main action is a near-black 41px-high pill with 24px radius and 16px sans text; secondary pills are only 30px high with 12px text.
- Color lives in exhibits rather than the reading canvas: white dominates the text sections; vivid hues belong inside rectangular imagery, one warm #fef199 proof band provides a full-width interruption, and the closing band is #111118.
- Capabilities become physical typography: include a word sculpture of overlapping, rotated near-black capsules carrying white uppercase sans text, spanning about 1280px by 558px; use the new product's own short capability nouns.
- Proof and conversion receive architectural frames: center a 48px/1.2 serif quotation within extended gold rules, then use a 72px serif closing action in a 660px by 190px outlined capsule touching a separate 190px arrow circle.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric yellow | `#ffed00` | `--color-electric-yellow` | action, accent, surface | Primary-button hover and text selection; also the highlighted offer card on offer-comparison pages. |
| Golden frame | `#fbbf0d` | `--color-gold-rule` | border | Extended quotation rules and portrait ring on the butter band. |
| Butter yellow | `#fef199` | `--color-butter` | background, surface | Default full-width quotation band and small supporting invitation cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#111118` | `--color-ink` | text, background, border, action | Default text, graphic capsules, outlines, primary actions and closing canvas. |
| Navigation charcoal | `#222222` | `--color-nav-ink` | text | Resting navigation links. |
| Reverse action hover | `#2c2b31` | `--color-action-hover` | action | Hover fill for the small reversed footer action. |
| Muted gray | `#7c7c7c` | `--color-muted` | text, border | Secondary credits and copyright; subdued dashed metadata rules. |
| Soft gray rule | `#bdbdbd` | `--color-dashed-rule` | border | Dashed list separators. |
| Pale navigation edge | `#eaecee` | `--color-edge` | border | Visible navigation hairline, made with rgba(68,85,103,0.11) on white. |
| Warm paper | `#f7f5f1` | `--color-warm-paper` | surface, background | Navigation hover and selected-link fill; extended testimonial and related-content bands. |
| White | `#ffffff` | `--color-canvas` | background, surface, text, border | Default page and card canvas; reversed text and outlines on the closing band. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| project case studies | Case-study blue | `#2545d3` | `--color-case-blue` | background | Alternative quotation band with white text. |
| project case studies | Pale blue frame | `#b3caff` | `--color-blue-rule` | border | Quotation framing and portrait rings against blue. |

## Typography

- **Editorial New** — Display titles, editorial statements, quotations and closing action. Very light high-contrast serif with narrow proportions, tall ascenders and expressive curved terminals. If unavailable, use **Instrument Serif**. Use regular weight; preserve the narrow silhouette rather than artificially boldening it. Font stack: "Editorial New", "Instrument Serif", Georgia, serif.
- **PP Mori** — Navigation, labels, body copy, buttons and typographic objects. Clean, rounded grotesk with a direct, contemporary voice, primarily regular weight. If unavailable, use **DM Sans**. Use regular and semibold cuts; keep tracking neutral except in uppercase labels. Font stack: "PP Mori", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Editorial New | 200 | 160px | 1.1 | normal | Default main title, usually one or two expansive lines. |
| closing-action | Editorial New | 200 | 72px | 1 | normal | Monumental outlined closing action. |
| editorial-statement | Editorial New | 200 | 70.4px | 1.1 | normal | Long editorial section statements and offer-card titles. |
| quotation | Editorial New | 200 | 48px | 1.2 | normal | Centered proof quotation and closing invitation question; also tall numbered-card titles. |
| body-large | PP Mori | 400 | 24px | 1.4 | normal | Outcome-card labels and introductory project narrative. |
| body | PP Mori | 400 | 18px | 1.4 | normal | Explanatory prose and card descriptions. |
| navigation | PP Mori | 400 | 18px | 1.2 | normal | Central navigation links. |
| button | PP Mori | 400 | 16px | 1.2 | normal | Primary navigation action. |
| small | PP Mori | 400 | 14px | 1.4 | normal | Marginal notes, item lists, credits, footer copy and author roles. |
| label | PP Mori | 400 | 14px | 1.2 | 0.107em, uppercase | Project captions, ruled marginal headers and metadata labels. |
| micro-action | PP Mori | 400 | 12px | 1 | normal | Compact outlined actions in marginal notes and footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| project case studies | case-display | Editorial New | 200 | 144px | 1.1 | normal | Long project-specific main titles. |
| detailed case studies, offering pages and profiles | chapter-heading | Editorial New | 200 | 120px | 1.1 | normal | Named chapters, offering details and major profile sections. |
| profiles | profile-intro | PP Mori | 400 | 48px | 1.2 | normal | Large personal introduction beside portrait. |
| profiles | testimonial-column | Editorial New | 200 | 20px | 1.5 | normal | Long-form endorsement columns. |

**Notes:**

- Keep the serif unusually light at every size; the hierarchy comes from scale and line length, not boldness.
- Normal tracking is the rule, even for the 160px display. The uppercase 14px label alone opens out to 1.5px tracking.
- Use the 70.4px editorial statement as the ordinary landing-page section voice; reserve 120px chapter titles for deeper explanatory page types.

## Layout

**Density:** Airy: long reading intervals and broad blank margins counterbalance image-dense exhibits.

### Spacing

**Spacing system:**

- **horizontal-step** 8px, horizontal — Dominant horizontal spacing increment; 16px, 24px, 32px and 40px support grids and card insets.

| Value | Use |
| --- | --- |
| 8px | Micro-action padding and navigation gaps. |
| 10px | List-row vertical padding and note-body gaps. |
| 16px | Caption separation, note padding and outcome-grid gaps. |
| 24px | Project-grid gaps, outcome-card padding and chapter top padding. |
| 32px | Offer-card side padding, footer-rule inset and offer-grid gap. |
| 40px | Heading-to-grid intervals and profile-card gaps. |
| 64px | Chapter heading-to-media interval. |
| 80px | Closing action group to footer information. |
| 112px | Default section top and bottom padding and main-title top inset. |
| 140px | Quotation-band vertical padding. |

### Containers and grids

- **main-container**: max width 1360px · side padding 72px. Centered desktop wrapper with a 1296px content span at 1440px; preserve broad side margins.
- **marginal-editorial**: 2 columns. A narrow note occupies 15% of the content width, a 15% open gutter separates it from a 70% statement column. Reverse the arrangement for the capability statement.
- **project-grid**: 2 columns · gap 24px. Equal project exhibits; imagery dominates each cell and ruled captions sit beneath.
- **outcome-grid**: 2 columns · gap 16px. Compact outcome cards within the wide editorial column.
- **quotation-container**: max width 940px. Centered quotation and compact portrait attribution inside a full-width band.
- **chapter-pair** (only for detailed case studies and offering pages): 2 columns · gap 24px. Two-thirds title and one-third explanation, each topped by its own rule.
- **offer-grid** (only for offering comparisons): 3 columns · gap 32px. Three equally tall paper-like offer cards.
- **profile-grid** (only for profiles): 4 columns · gap 40px. Four endorsement columns or numbered principle cards.

## Corner radius

| Element | Radius |
| --- | --- |
| small-cards | 8px |
| small-actions | 24px |
| navigation-links | 80px |
| closing-capsule | 150px |
| portrait | 800px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default reading background.

**CSS:** `background: #ffffff; color: #111118`

**Observed:** Flat and untextured, allowing type and framed media to carry the composition.

**Transfer:** Keep prose on white even when the product's media is highly colorful.

#### Butter proof band · level 0

**Use:** Signature full-width social-proof interruption.

**CSS:** `background: #fef199; position: relative`

**Observed:** Warm pale yellow, with gold lines running through the whole band rather than merely enclosing the text.

**Transfer:** Use the frame around a single strong proof statement.

#### Closing ink band · level 0

**Use:** Shared conversion and footer surface.

**CSS:** `background: #111118; color: #ffffff; overflow: hidden`

**Observed:** A flat, deep near-black slab, approximately 708px tall on desktop.

**Transfer:** Keep the ending graphically simple and strongly reversed.

#### Warm paper band · level 0

**Only for:** profiles and related-project sections

**Use:** Long endorsement collections and related-content browsing.

**CSS:** `background: #f7f5f1`

**Observed:** A faint warm neutral rather than a gray card fill.

**Transfer:** Use for editorial supporting material, not every other section.

#### Blue proof band · level 0

**Only for:** project case studies

**Use:** Project-specific proof interruption.

**CSS:** `background: #2545d3; color: #ffffff`

**Observed:** Same quotation composition as the warm band, but pale-blue framing and white text.

**Transfer:** Use as a project-scoped color variant, not the default landing-page theme.

## Components

### Fixed navigation

**Use:** Persistent orientation above the oversized opening.

**CSS:** `height: 71px; background: #ffffff; position: fixed; z-index: 1000; border-bottom: 1px solid rgba(68, 85, 103, 0.11)`

**Text style:** `navigation` — PP Mori 400 · 18px/1.2

**Observed:** Left-aligned two-line identity, three centrally grouped links and a right-aligned Primary button. Identity name is 18px with a 14px role below.

**Transfer:** Use a compact product identity plus short descriptor; keep the center links sparse.

### Navigation link

**Use:** Central page destinations.

**CSS:** `color: #222222; padding: 12px 18px 10px; border-radius: 80px; display: flex; align-items: center`

**Text style:** `navigation` — PP Mori 400 · 18px/1.2

**Observed:** Selected destinations use the same warm-paper capsule as hover.

**States:** Declared: hover background-color #f7f5f1, color #111118, text-decoration none; active outline 0px. Focus-visible styling is unknown.

### Primary button

**Use:** Main conversion action in the fixed header.

**CSS:** `background: #111118; color: #ffffff; border: 1px solid #111118; border-radius: 24px; padding: 10px 16px; height: 41px`

**Text style:** `button` — PP Mori 400 · 16px/1.2

**Observed:** Compact text-only pill at the far right; it does not compete with the display title.

**States:** Declared: hover background-color #ffed00 and color #111118; active outline 0px. Focus-visible styling is unknown.

### Micro outline action

**Use:** Links attached to marginal notes and offering explanations.

**CSS:** `border: 1px solid #111118; border-radius: 24px; padding: 8px; height: 30px`

**Text style:** `micro-action` — PP Mori 400 · 12px/1

**Observed:** A miniature pill positioned beneath small explanatory copy. Reversed footer version has white border and text, ink fill, and 8px 16px padding.

### Project caption

**Use:** Label beneath a large project image or gallery slide.

**CSS:** `border-top: 1px solid #111118; padding-top: 16px; margin-top: 16px; display: flex; justify-content: space-between`

**Text style:** `label` — PP Mori 400 · 14px/1.2 · tracking 0.107em · uppercase

**Observed:** A single uppercase descriptive line with a small upward arrow at the opposite edge.

### Dashed capability row

**Use:** A compact capability list in the margin.

**CSS:** `border-bottom: 1px dashed #bdbdbd; padding: 10px 0`

**Text style:** `small` — PP Mori 400 · 14px/1.4

**Observed:** Plain stacked text rows below an uppercase ruled header, ending in a Micro outline action. Offer-card variants add a small circled check at left and 32px left padding.

### Outcome card

**Use:** Short statements of customer progress.

**CSS:** `background: #ffffff; border: 1px solid #111118; border-radius: 8px; padding: 24px; display: flex; align-items: center; gap: 24px`

**Text style:** `body-large` — PP Mori 400 · 24px/1.4

**Observed:** A small outlined 35px circle precedes the label. Cards form a two-column set, with height following one or two lines of text; the circle must not imply an input unless interaction is implemented.

### Monumental closing action

**Use:** Dominant invitation in the closing band.

**CSS:** `background: #111118; color: #ffffff; border: 2px solid #ffffff; border-radius: 150px; height: 190px; padding: 40px 60px 30px; display: flex; align-items: center; justify-content: center`

**Text style:** `closing-action` — Editorial New 200 · 72px/1

**Observed:** A 660px text capsule touches a separate 190px circular arrow outline. Both are one invitation, centered below the smaller serif question.

### Footer information rail

**Use:** Practical navigation beneath the large closing action.

**CSS:** `border-top: 1px solid #ffffff; padding-top: 32px; display: flex; justify-content: space-between`

**Text style:** `small` — PP Mori 400 · 14px/1.4

**Observed:** Left column is a short identity description with muted copyright below; right group combines contact action and email with two sparse link columns. An 80px interval separates this rail from the invitation group.

### Numbered principle card

**Only for:** profiles and differentiation pages

**Use:** Articulate distinct working principles or product strengths.

**CSS:** `border: 1px solid #111118; border-radius: 8px; padding: 40px 24px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px`

**Text style:** `quotation` — Editorial New 200 · 48px/1.2

**Observed:** Roman numeral at top, centered multi-line serif title beneath, then a bottom-aligned 18px sans paragraph. Four 294px by 536px cards share a row.

### Notebook offer card

**Only for:** offering comparisons

**Use:** Compare concrete packages without a conventional pricing-table appearance.

**CSS:** `background: #ffed00; padding: 24px 32px 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 24px`

**Text style:** `editorial-statement` — Editorial New 200 · 70.4px/1.1

**Observed:** Default highlighted variant belongs to the middle offer; neighboring offers are white. A separate black-outlined top strip contains five circular binder notches, continuous with thin side and bottom borders. Inside: title, 18px promise, uppercase ruled Includes header, checked dashed rows and miniature examples action. A tilted circular Most Popular stamp marks the featured card.

**Transfer:** Retain the paper-cut top and one highlighted package; replace deliverables with genuinely comparable items.

## Imagery and graphics

### Color-rich project stages

**Use:** Full-bleed opening exhibit and paired project thumbnails.

**Observed:** Bright, rectangular compositions show web pages on phones and laptops, layered browser windows, printed decks and designed objects. Backdrops include deep blue, purple, coral gradients and vivid yellow; the surrounding reading canvas remains white. Thumbnails are roughly landscape 1.55:1 and opening media is 1440px by 675px.

**Transfer:** Show the new product's real interface or physical output in a coherent, saturated stage. Without finished media, compose one simplified browser or device showing a credible use case against a flat bold backdrop; do not use empty mockups.

### Circular text seal

**Use:** Signature overlap between opening headline and media.

**Observed:** A hollow ring of uppercase sans text, with dot separators and no filled disc, sits at the lower-right of the title and extends onto the imagery. Its SVG has a 280px square box; the lettering occupies a smaller circle inside.

**Transfer:** Use a short truthful availability, release or invitation phrase belonging to the new product.

**Build:** Create an SVG with a 280px viewBox and a circular path of roughly 100px radius centered at 140px. Repeat a short uppercase phrase with dot separators on a textPath in regular sans at about 22px. Use ink fill, no disc or stroked outer border; place it above the title-media boundary with z-index 2. Match the open ring rather than filling the center.

### Capability capsule sculpture

**Use:** Signature playful object within an otherwise editorial page.

**Observed:** Two or more huge black capsules with white uppercase sans capability names overlap at opposing angles, like loose physical signs. The artwork spans 1280px by 558px and is partly cut by the lower edge of the section.

**Transfer:** Make the object from the new product's two or three shortest capability nouns. This is the minimum graphic substitute when sophisticated visual assets are unavailable.

**Build:** Use an SVG 1280 by 558 with rounded rectangles filled #111118 and centered #ffffff sans lettering. For a two-label version, use capsules about 780px by 170px and 560px by 170px with 85px ends; rotate the long one roughly -15deg and the shorter one roughly 35deg, letting them touch diagonally. Set uppercase lettering around 64px and clip overflow at the stage edge. Angles and individual lengths should follow the words while retaining the loose leaning silhouette.

### Extended proof frame

**Use:** Graphic architecture around the warm quotation band.

**Observed:** Gold vertical lines inset about 60px from either page edge cross full-width horizontal lines inset about 60px from the band's top and bottom. The frame extends past its intersections; an 80px round author portrait repeats the gold edge.

**Transfer:** Keep the quotation readable in the central 940px; use the intersecting rules even when the author is represented by initials.

**Build:** In a relatively positioned full-width butter surface, place two absolute horizontal 2px gold rules at top and bottom offsets of 60px, and two vertical 2px gold rules at left and right offsets of 60px. Let all lines reach the outer edges, forming projecting corners. Center the quote and attribution above the lines.

### Warm natural portraits

**Only for:** profiles and testimonial attribution

**Use:** Humanize editorial text and endorsements.

**Observed:** The main portrait is a vertical outdoor photograph in soft sunset light with dark trees and defocused foliage; it is a plain rectangle around 408px by 613px. Smaller quotation portraits are circular with fine colored rings.

**Transfer:** Use relaxed, authentic environmental portraits with natural light rather than studio cutouts or stock-team grids.

### Structured product collages

**Only for:** project case studies

**Use:** Explain process, output families and detailed feature work.

**Observed:** Large collages alternate with two-column crops and side-caption exhibits. Browser frames, outlined UI fragments, diagram bars and code snippets sit on colored gradients or in dark contact sheets. Some process boards use pale dot-grid backing. Purple-pink, orange-yellow and green-blue pairings are contained inside these artifacts, not applied to the editorial site.

**Transfer:** Build a coherent artifact family from the new product's own UI; vary wide overview, tight detail and annotated process board. Treat internal interface palettes as product-specific rather than expanding the marketing theme.

### Icons

**Observed:** Arrows are simple typographic marks rather than elaborate pictograms: upward for project captions, downward for marginal headers, rightward for the closing action. Lists use tiny circled checks; outcome cards begin with thin outlined circles.

**Transfer:** Use arrows to clarify reading direction and restrained circles to mark outcomes; avoid a decorative icon for every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Poster over project stage

**Observed:** The white canvas supports a fixed 71px navigation with identity left, three links centered and Primary button right. Below, the 160px display title begins with a 112px top inset and wraps into two lines across almost the whole content width, leaving open space at the lower right. The Circular text seal overlaps that space and the top of the full-bleed Color-rich project stage. Media begins about 496px down the page and continues for 675px. Within the first 900px, the full title, header action, circular seal and upper portion of the vivid project composition are visible; the introduction and project grid remain below. There is no hero paragraph or extra hero button cluster.

**Transfer:** Use a concise product promise whose line breaks create a broad first line and an open corner on the second. Replace the project scene with a saturated product-output composition, using a single credible interface if needed. Profile and offering pages open with a shorter one-line title above portrait content or offer cards; case studies use the 144px case-display title above a full-bleed output collage.

**Avoid:** Do not turn the first screen into a centered SaaS headline, explanatory paragraph and two-button stack, or shrink the typography to fit an isolated floating dashboard.

**Text style:** `display` — Editorial New 200 · 160px/1.1

### Statement with marginal note

**Observed:** A 70.4px editorial statement fills the wide side of the marginal-editorial layout. The narrow note is aligned low, containing a ruled uppercase heading, downward arrow, small portrait or explanatory copy, and Micro outline action. The introduction adds a low-contrast logo strip beneath the statement; edge fades soften the strip.

**Transfer:** Pair a meaningful long-form promise with a compact contextual note or verified proof strip. Alternate the note to the opposite side for a capability statement.

**Text style:** `editorial-statement` — Editorial New 200 · 70.4px/1.1

### Paired visual proof

**Observed:** Project-grid holds broad Color-rich project stages in two equal columns with 24px gaps. Project caption supplies a hairline and uppercase label beneath each image; no heavy card body surrounds the exhibit.

**Transfer:** Use a small curated set of contrasting product outputs or customer applications; let each image explain a different capability.

### Capability statement and word sculpture

**Observed:** A wide editorial statement is paired with a right marginal list of Dashed capability rows. The Capability capsule sculpture fills the lower part of the section, creating an oversized graphic interruption.

**Transfer:** Combine a substantive benefit statement with a short catalog and make the catalog's key nouns into leaning capsules.

**Text style:** `editorial-statement` — Editorial New 200 · 70.4px/1.1

### Framed quotation

**Observed:** Butter proof band carries Extended proof frame, centered 48px serif text within 940px and compact author attribution with 80px portrait below. Vertical padding is 140px. The project variant uses Blue proof band with pale-blue rules and white text.

**Transfer:** Use a single credible quote of enough substance to read as editorial proof, not a tiny carousel card.

**Text style:** `quotation` — Editorial New 200 · 48px/1.2

### Outcome matrix

**Observed:** A wide statement sits above a two-column outcome-grid with 16px gaps and Outcome cards. The marginal note aligns near the bottom of the group, containing a compact contact prompt.

**Transfer:** Translate features into concise user progress statements; maintain the simple circle-plus-label construction.

**Text style:** `editorial-statement` — Editorial New 200 · 70.4px/1.1

### Monumental invitation and practical footer

**Observed:** Closing ink band centers a 48px serif question above the Monumental closing action, with approximately 50px between question and capsule. The Footer information rail sits below an 80px group gap. Its 1296px white top rule divides the theatrical invitation from practical identity, contact and navigation information. All four page types use this same ending.

**Transfer:** Always retain the large capsule-and-arrow invitation, adapting the words to the product's primary next step. Keep ordinary footer links subordinate.

**Text style:** `closing-action` — Editorial New 200 · 72px/1

### Ruled chapter and exhibit

**Only for:** detailed case studies and offering pages

**Observed:** A 120px chapter title occupies two thirds of a paired heading row; 18px explanatory copy occupies the remaining third. Case-study columns have individual top rules with 24px top padding. A 64px interval leads into a broad image exhibit, followed by details or a side-caption layout.

**Transfer:** Repeat the chapter grammar for problem, approach and outputs, varying exhibit format instead of changing typography.

**Text style:** `chapter-heading` — Editorial New 200 · 120px/1.1

### Notebook comparison and galleries

**Only for:** offering pages

**Observed:** A one-line 160px title introduces three Notebook offer cards with 32px gaps; only the middle card is yellow. Later, offering chapters combine a 120px title, right-column prose and small action, then a horizontal image gallery with 54px circular previous/next controls and Project captions.

**Transfer:** Summarize distinct offers first, then show tangible examples in galleries rather than repeating benefit tiles.

**Text style:** `chapter-heading` — Editorial New 200 · 120px/1.1

### Profile editorial proof

**Only for:** profiles

**Observed:** A one-line 160px greeting leads into a vertical portrait left and a 48px sans introduction right, with two smaller text columns beneath. Warm paper band hosts four long endorsement columns using 20px/1.5 serif text and small portrait attribution. A white section follows with a 120px heading and four Numbered principle cards.

**Transfer:** Use a human or team introduction, substantial third-party endorsements and clearly differentiated principles without turning the page into a résumé table.

**Text style:** `profile-intro` — PP Mori 400 · 48px/1.2

### Related-project bridge

**Only for:** project case studies

**Observed:** A warm-paper section before the closing band presents two horizontal related-project links with top and bottom rules, thumbnail images and directional arrows. A small yellow capabilities invitation and compact collaborator credits precede this bridge.

**Transfer:** End a detailed story with credit and a route to adjacent examples before the shared invitation.

## Page flow

**Storyline:** Editorial promise → tangible visual proof → context and capabilities → human endorsement → customer progress → monumental invitation; deeper pages expand the proof into chapters.

### Broad introduction and conversion-oriented portfolio landing

1. **Promise** — Oversized two-line title and overlapping circular seal above vivid full-bleed imagery.
2. **Credibility** — Marginal introduction beside large serif statement and restrained logo strip.
3. **Visual proof** — Paired project exhibits with ruled uppercase captions.
4. **Capabilities** — Editorial statement, narrow catalog and oversized capsule word sculpture.
5. **Social proof** — Warm framed quotation with human attribution.
6. **Customer progress** — Statement plus outlined outcome matrix.
7. **Closing call** — Ink band with capsule-and-circle action and information rail.

**Transfer:** Use enough visual demonstrations to make the promise concrete, retaining the playful typography and architectural proof treatment wherever they best support the story.

### Long-form project or product implementation story

1. **Result-led promise** — 144px serif title followed by full-bleed collage.
2. **Context** — Small ruled metadata beside three large sans narrative paragraphs.
3. **Approach** — Audit and process chapters with broad process boards and annotated details.
4. **Social proof** — Blue framed quotation.
5. **Output chapters** — Repeated ruled heading pairs, large overview images, two-column crops and marginal explanations across output families.
6. **Credits and continuation** — Compact collaborators, yellow invitation card and paired related-project bridge.
7. **Closing call** — Shared monumental ink ending.

**Transfer:** Build chapters around the new project's actual challenges and outputs, avoiding exhaustive galleries with no explanatory purpose.

### Human profile and differentiated approach

1. **Introduction** — Large greeting above natural portrait and substantial sans introduction.
2. **Social proof** — Warm-paper endorsement collection in four serif columns.
3. **Differentiation** — Large heading above Roman-numbered principle cards.
4. **Closing call** — Shared monumental ink ending.

**Transfer:** Adapt to a founder, team or company story while preserving personal warmth and editorial depth.

### Explain and compare service or productized offerings

1. **Orientation** — One-line serif title above three notebook-like offer summaries.
2. **Comparison** — White and highlighted-yellow cards with deliverable lists.
3. **Capability chapters** — Large title and right-side explanation for each offer, followed by output galleries and circular controls.
4. **Closing call** — Shared monumental ink ending.

**Transfer:** Compare understandable packages and support each with concrete visual examples rather than inventing prices or feature counts.

## Writing

Warm, personal and assured. Design and business value are connected in plain language, with craft described through concrete outputs rather than aggressive sales claims.

**Do not copy:** Do not reuse the designer's name, contact details, client logos, proprietary artwork, project titles, career duration, customer claims or testimonial wording as assets or claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First-person singular for the maker and direct you/your for the reader; invitations often use let's. A product team can use we while retaining the same conversational directness.
- **Rhythm:** Short, memorable titles sit beside longer, flowing editorial statements. Small support text is practical; deeper chapters explain context, challenge and response in calm paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A compact quality-led promise or a transformation phrased as a simple result. | 4–9 words | “Thoughtful design for brilliant brands”<br>“Turning code into clarity for AssemblyAI” |
| Editorial statement | First-person active sentence connecting expertise with the reader's next stage. | 20–35 words | “I can help drive your next phase, whether you're launching a startup or evolving an established brand.” |
| Marginal prompt | Friendly question followed by a brief encouraging sentence. | 10–18 words | “Have a project in mind? Big ideas start with a simple hello.” |
| Section title | Literal noun phrase for detailed chapters; warmer language for human proof. | 1–5 words | “Love letters”<br>“Brand Audit” |
| Action | Direct, collaborative and low-pressure invitation. | 2–4 words | “Work with me”<br>“Start a project”<br>“Let's work together” |
| Outcome | Active verb followed by a concrete customer benefit. | 3–6 words | “Build trust and credibility”<br>“Streamline marketing efforts” |

**Words and phrasing to use:** thoughtful; clarity; connecting the dots; cohesive; adaptable; meaningful; bring ideas to life; your next phase

**Avoid:** revolutionary; disrupt everything; 10x guaranteed; unlock limitless potential; enterprise-grade synergy

**Rules:**

- Connect the capability to its practical role in the customer's work.
- Use labels to identify the artifact or subject, not to add another sales slogan.
- Keep the small marginal text conversational and useful.
- Allow substantial explanations on deep pages; do not force every paragraph into a slogan.

## Do's and Don'ts

### Do

- Use the 160px light serif display as the opening's main object.
- Keep ordinary editorial statements at 70.4px/1.1 and normal tracking.
- Separate image captions with a 1px ink rule and 16px spacing.
- Give major reading sections 112px vertical breathing room.
- Use the 24px project-grid gap and 16px outcome-grid gap distinctly.
- Build the warm proof frame with extended 2px gold rules.
- Retain the miniature 30px secondary pills alongside the oversized closing action.
- Make the typographic sculpture a genuine graphic object, not a conventional tag list.

### Don't

- Do not introduce drop shadows to lift marketing cards; use 1px borders on the flat canvas.
- Do not set the serif in bold or tighten its normal tracking into a dense fashion logotype.
- Do not apply the project artwork's purple-pink or green-blue palette to ordinary body sections.
- Do not round all project-image corners into large app-style tiles; rectangular exhibits dominate.
- Do not promote the 120px chapter style to every landing-page paragraph heading.
- Do not replace dashed list separators with solid heavy bars or filled icon chips.
- Do not enlarge the header action to match a typical 56px software CTA; its compact 41px scale is intentional.
- Do not make Roman-numbered 536px profile cards the default feature layout for a marketing page.

## Motion and responsive

### Motion

**Observed:**

- Primary and compact actions declare background-color transitions of 0.3s; navigation links declare 0.2s transitions.
- A horizontally sliding strip declares a 40s linear infinite animation.
- The circular opening seal appears at a rotated orientation; a spin keyframe is declared.

**Transfer:**

- Keep color changes on small actions rather than using dramatic button movement.
- Preserve the circular seal as an independent rotating graphic when motion is implemented; its static arrangement must still read clearly.

**Unknown:**

- Seal rotation duration and easing are not established.
- Scroll-reveal timing, gallery autoplay behavior and focus-visible presentation are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 768px and 991px.

**Transfer:**

- On narrow screens, reduce the poster type while preserving its light weight and deliberate line breaks; stack marginal notes with their statements instead of squeezing the 15% column.
- Reflow offer and profile grids into readable stacks; preserve notebook notches and Roman numerals.
- Scale the closing capsule and adjoining arrow together so the two-part invitation remains recognizable.

**Unknown:**

- Mobile type sizes, navigation collapse, gallery widths and exact breakpoint-specific spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
