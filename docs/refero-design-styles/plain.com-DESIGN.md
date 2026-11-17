# Plain — green circuitry, human ease

## Overview

An approachable technical style for flexible software and infrastructure products. Mostly white and cream, it pairs forest-green type with electric mint accents and occasional deep-green chapters. Regular-weight grotesk headlines, small monospaced labels, carefully staged interface fragments and lightly tinted workplace photography keep a long, information-rich story feeling open rather than corporate.

### Essentials

- Two-line promises split color rather than weight: 80px/80px regular grotesk, -0.02em tracking, mint first line and forest second line.
- The opening balances a narrow centered promise against a wide working product: a 624px headline measure, 24px supporting type, a 420px inline email form and a 1200px pale-green interface stage entering the first screen.
- Actions look like compact equipment controls, not bubbles: 6px corners, 13px uppercase Geist Mono labels, 34px navigation buttons and 41px conversion buttons.
- Green is a structural language: white dominates the long page, warm #f9f6f1 backs product fragments, #0a2414 creates substantial full-width chapters, and #1ad379 marks actions and graphic circuitry. Burgundy and pink belong to a featured customer-proof panel, not the everyday canvas.
- Product evidence is modular and physical: a roughly 793×480px demonstration pairs with a narrow text column, then 387×220px detail scenes sit in three columns with 20px gutters. When no finished interface exists, use believable task fragments on the same warm backing.
- Technical linework ties the story together: fine mint paths frame the opening product and an architectural grid surrounds the pale-green closing call. Recreate these with SVG curves and 1px rules even when there is no equivalent brand artwork.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mint | `#1ad379` | `--color-mint` | accent, action, link | Headline emphasis, primary buttons, diagram paths and discovery links. |
| Forest ink | `#0a2414` | `--color-ink` | text, background | Default marketing text and full-width dark chapters. |
| Pale green | `#f3fbe9` | `--color-pale` | surface, background, text | Opening stage and closing ground; reversed text on forest sections. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link green | `#17b267` | `--color-link` | link | Footer navigation and declared text-link hover color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Body black | `#000000` | `--color-black` | text | Supporting text and dense feature descriptions on white. |
| Form edge | `#e5e7eb` | `--color-rule` | border | Faint outline around the inline email form. |
| Warm demonstration ground | `#f9f6f1` | `--color-cream` | surface, border | Feature illustration backings, small testimonials and checklist cards; same-color edges stay almost invisible. |
| Cool interface shell | `#f7faf9` | `--color-cool` | surface | Outer shell of the large opening interface. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page ground and white interface layers; navigation uses white at 92% opacity. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| inline lead forms | Form action green | `#4ade80` | `--color-form-action` | action | Submit button inside the opening email form. |
| featured customer proof | Customer-story pink | `#ffbac3` | `--color-pink` | text, accent | Reversed quote text and a translucent conic wash over workplace photography. |
| featured customer proof | Customer-story burgundy | `#360003` | `--color-burgundy` | surface | One featured proof card gives the white page a contrasting editorial moment. |

## Typography

- **ABC Favorit** — Marketing headlines, paragraphs, navigation and card copy. Friendly grotesk with open counters and an unforced regular-weight display voice. If unavailable, use **Inter**. Use 400 and 500; preserve tight tracking and the compact headline measure. Font stack: "ABC Favorit", "Inter", Arial, sans-serif.
- **Geist Mono** — Section labels, discovery links and conversion controls. Small technical capitals with gently expanded tracking. OpenType features: "ss02", "ss06". Font stack: "Geist Mono", ui-monospace, monospace.
- **Inter** (only for inline lead forms) — The embedded form submit label. Compact semibold utility text. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ABC Favorit | 400 | 80px | 1 | -0.02em | Centered opening headline, typically split into two balanced lines. |
| heading | ABC Favorit | 400 | 48px | 50px | -0.02em | Section leads, feature chapter titles and closing invitation. |
| lead | ABC Favorit | 400 | 24px | 28px | -0.02em | Opening support and centered introductions to major chapters. |
| milestone | ABC Favorit | 500 | 24px | 28px | -0.02em | Timeline milestones and short concluding emphasis. |
| body | ABC Favorit | 400 | 18px | 24px | -0.01em | Feature explanations, dark-chapter prose and testimonial quotes. |
| card-title | ABC Favorit | 500 | 18px | 24px | -0.01em | Short benefit titles and comparison-row prompts. |
| small | ABC Favorit | 400 | 15px | 20px | -0.01em | Navigation, supporting card copy, checklist text and footer links. |
| label | Geist Mono | 500 | 13px | 19px | 0.015em, uppercase, features "ss02", "ss06" | Eyebrows, technical badges, buttons and directional links. |

**Notes:**

- Headings stay at weight 400; contrast comes from size and color rather than heavy type.
- Tracking is -0.02em at display and lead sizes, tightening to a smaller absolute amount at the -0.01em body scale. Mono labels reverse the direction with 0.015em tracking.
- Use title or sentence case for expressive copy and uppercase only for the small mono utility layer.

## Layout

**Density:** Airy at the section level, compact within interface fragments and navigation.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer link stacks and close utility relationships. |
| 10px | Compact navigation and adjoining feature-stage columns. |
| 12px | Heading-to-body spacing and paired closing actions. |
| 20px | Three-column gutters and outer minimum side padding. |
| 24px | Card padding, eyebrow-to-heading gaps and media-to-caption gaps. |
| 40px | Section heading groups, comparison rows and larger internal groups. |
| 80px | Dark-section upper padding and spacious grouped content. |
| 120px | Major section padding and transitions between content regimes. |
| 140px | Opening content inset below the navigation. |
| 160px | Vertical separation between alternating feature chapters. |

### Containers and grids

- **main container**: max width 1200px · side padding 20px. Centered shared width for demonstrations, customer proof and footer; desktop content spans most of the page without going edge-to-edge.
- **opening headline**: max width 624px. Centered two-line headline; supporting copy can extend to 700px.
- **detail grid**: 3 columns · gap 20px. Three equal columns, each about 387px wide at full container width.
- **feature stage**: max width 1200px · 2 columns · gap 10px. Unequal columns: roughly 793px of demonstration beside about 397px of copy; alternate which side carries the media.
- **argument column**: max width 793px · 2 columns · gap 20px. Narrow centered dark-section rows, with a short reason and link on the left and a longer explanation on the right.
- **footer links**: 5 columns · gap 20px. Five approximately 183px link columns beside a separate identity block.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 6px |
| feature and quote cards | 9px |
| closing inset | 8px |
| opening interface | 10px |
| opening backdrop | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| opening interface | `0px 0.6px 0.6px -1.2px rgba(21, 38, 12, 0.55), 0px 2.3px 2.3px -2.3px rgba(21, 38, 12, 0.49), 0px 10px 10px -3.5px rgba(21, 38, 12, 0.24)` | Restrained depth under the large product shell, not the ordinary cream cards. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading environment.

**CSS:** `background: #ffffff; color: #0a2414`

#### Warm media panel · level 1

**Use:** Product detail illustrations and small proof cards.

**CSS:** `background: #f9f6f1; border-radius: 9px`

**Observed:** Low-contrast flat backing; no glossy elevation. Miniature UI floats within it rather than filling every edge.

**Transfer:** Keep surrounding ground visible around the meaningful product interaction.

#### Forest chapter · level 0

**Use:** Immersive product introduction and longer technical argument.

**CSS:** `background: #0a2414; color: #f3fbe9`

**Observed:** A full-width tonal change, not a dark floating card.

**Transfer:** Group related claims into one continuous dark field.

#### Pale green stage · level 0

**Use:** Opening product art and the closing conversion environment.

**CSS:** `background: #f3fbe9; color: #0a2414`

**Observed:** Fine green paths and architectural rules add structure without making the ground busy.

**Transfer:** Keep linework behind content with broad untouched areas around text.

#### Photographic forest fade

**Use:** Blend a real-world product scene into the dark chapter.

**CSS:** `background: linear-gradient(rgba(10, 36, 20, 0) 20%, #0a2414 100%)`

**Observed:** A desk-and-monitor image remains visible above, then disappears into forest green below; a radial forest vignette improves text contrast.

**Transfer:** Use subdued photographic lighting and the same green fade, not a black overlay.

#### Featured proof · level 1

**Only for:** featured customer proof

**Use:** A contrasting flagship testimonial.

**CSS:** `background: #360003; color: #ffbac3; border-radius: 9px; padding: 24px`

**Observed:** Equal text and photo halves; the quote sits low beneath the logo and story link.

**Transfer:** Pair a real quote with a credible human scene rather than another interface image.

## Components

### Navigation bar

**Use:** Persistent site orientation and compact conversion.

**CSS:** `background: rgba(255, 255, 255, 0.92); backdrop-filter: blur(6px); height: 70px; padding: 0px 20px`

**Text style:** `small` — ABC Favorit 400 · 15px/20px · tracking -0.01em

**Observed:** Sticky bar with a centered 1200px inner row: identity left, text navigation in the middle, outlined sign-in and filled action right. Some items have small chevrons.

### Primary button

**Use:** Default marketing conversion control.

**CSS:** `background: #1ad379; color: #f3fbe9; border-radius: 6px; padding: 11px 16px; height: 41px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `label` — Geist Mono 500 · 13px/19px · tracking 0.015em · uppercase

**Observed:** Compact rectangular filled control. The navigation version uses 8px 10px 7px padding and a 34px height.

### Secondary button

**Use:** Self-serve alternative beside the main conversion.

**CSS:** `color: #1ad379; background: transparent; border: 1px solid #1ad379; border-radius: 6px; padding: 11px 16px; height: 41px`

**Text style:** `label` — Geist Mono 500 · 13px/19px · tracking 0.015em · uppercase

**Observed:** Mint outlined companion, sharing baseline and corner shape with Primary button; separated by 12px.

### Inline email form

**Use:** Low-friction conversion immediately under the opening promise.

**CSS:** `background: #ffffff; border: 1px solid #e5e7eb; border-radius: 10px; padding: 10px 10px 10px 4px; width: 420px; height: 64px`

**Observed:** One horizontal field with a light work-email prompt on the left and Form submit button nested on the right.

**Transfer:** Ask for one meaningful field rather than presenting a multi-field form.

### Discovery link

**Use:** Move from a benefit chapter into product detail.

**CSS:** `display: inline-flex; align-items: center; gap: 12px; color: #1ad379`

**Text style:** `label` — Geist Mono 500 · 13px/19px · tracking 0.015em · uppercase

**Observed:** Uppercase text followed by an unusually long, fine outlined arrow about 56×18px; not a small solid arrow glyph.

### Quote card

**Use:** Compact secondary social proof.

**CSS:** `background: #f9f6f1; border-radius: 9px; padding: 24px`

**Text style:** `body` — ABC Favorit 400 · 18px/24px · tracking -0.01em

**Observed:** Green quotation mark above the quote, followed by a small avatar and compact author details. Two equal-width cards support the larger Featured proof panel.

**Transfer:** Keep quotes as readable prose with a clear named attribution.

### Closing invitation

**Use:** Large final conversion panel.

**CSS:** `background: #f3fbe9; border-radius: 8px; padding: 40px 60px; max-width: 1136px`

**Text style:** `heading` — ABC Favorit 400 · 48px/50px · tracking -0.02em

**Observed:** Centered logo proof above a two-line invitation; two controls below. The panel merges visually into a wider architectural green grid instead of appearing as a raised card.

### Footer link

**Use:** Dense but easy-to-scan destination columns.

**CSS:** `color: #17b267; text-decoration: none; transition: color 0.4s cubic-bezier(0.44, 0, 0.56, 1)`

**Text style:** `small` — ABC Favorit 400 · 15px/20px · tracking -0.01em

**Observed:** Green links under dark column headings on the pale-green footer, with 8px gaps between 20px text rows.

**States:** Declared: hover color #17b267 and text-decoration-line underline; focus-visible unknown.

### Form submit button

**Only for:** inline lead forms

**Use:** Submit the opening lead form.

**CSS:** `background: #4ade80; color: #ffffff; border-radius: 6px; padding: 12px 20px; height: 42px`

**Observed:** Title-case Inter at 15px, weight 600, with normal tracking and natural line height distinguishes the embedded form from the mono marketing controls.

## Imagery and graphics

### Circuit-backed product stage

**Use:** Primary opening product proof.

**Observed:** A wide desktop workspace appears inside a very light cool shell, inset roughly 35px from a pale-green stage. Thin green curves and dashed paths sit behind the shell; the scene is broad, crisp and more dominant than the narrow copy above.

**Transfer:** Use an actual working screen or a simplified, believable workspace with navigation, content list and a contextual panel. Retain the green circuit backing even with a simpler product.

**Build:** Create a 1200px-wide pale-green panel with 12px corners. Put several oversized SVG Bézier curves behind the interface using 1px mint strokes at 25–45% opacity; mix solid paths with short dashes. Inset the interface by about 35px horizontally and 33px at the top, with 10px corners and the opening-interface shadow.

### Warm task miniatures

**Use:** Repeated feature demonstrations and three-card detail strips.

**Observed:** Cream panels hold small white interface cards, thin mint connectors, discreet icons and selected green nodes. Wide scenes show one meaningful interaction, while smaller scenes isolate an assignment, suggestion, summary or status. Some feature scenes use tilted application tiles, but ordinary UI remains front-facing.

**Transfer:** Show the new product doing one clear thing per panel; use sparse task fragments with generous cream margins, not decorative dashboard noise.

### Physical monitor scene

**Use:** Immersive transition into the first dark product chapter.

**Observed:** A real desktop monitor on a neutral desk, with subdued warm-gray ambient light. Centered pale text overlays the upper monitor area; the photograph fades to forest at the bottom.

**Transfer:** Photograph a real context of use with a clear central object and enough low-detail space for the heading. If photography is unavailable, use a restrained monitor mockup against a neutral softly lit background, retaining the forest fade.

### Architectural closing grid

**Use:** Signature final conversion backdrop.

**Observed:** Pale green fills the full closing area. Thin mint rules extend beyond the main container, marking its edges and a shallow lower band with occasional vertical divisions; faint green proof marks hover above the heading.

**Transfer:** Use the new identity and credible proof marks inside the same expansive drafting-board structure. If no proof logos exist, use a small set of descriptive mono labels.

**Build:** On pale green, draw 1px SVG rules in mint at about 35% opacity. Place two vertical rules at the main container edges; continue two horizontal rules across the viewport to form a 60px lower band. Divide that band once near the center and leave the central headline field mostly unmarked.

### Pink-washed customer scene

**Only for:** featured customer proof

**Use:** Human counterpoint to product diagrams.

**Observed:** A candid overhead office discussion occupies the right half of a burgundy card. A broad translucent pink sweep softens the scene; a small monochrome author portrait accompanies the quote on the left.

**Transfer:** Use natural team or customer context, not a stock handshake. Preserve recognizably human detail beneath the pink tint.

**Build:** Clip the photo into a softly rounded rectangle. Add an overlay using conic-gradient(rgba(255,186,195,0.83) 182.489deg, rgba(255,186,195,0) 339.654deg, rgba(255,186,195,0.83) 360deg), adjusted so one corner stays relatively clear and the opposite side carries the wash.

### Icons

**Observed:** Small single-color glyphs in forest or mint, usually 20×20px; category badges pair an icon with a mono label. Directional actions use much wider 56×18px fine-line arrows. Checklists use green circled checks.

**Transfer:** Choose a coherent compact icon set, reserving partner colors for actual integrations. Keep navigation chevrons tiny and discovery arrows long.

## Section recipes

How recurring sections are built.

### First screen: Centered promise over working product

**Observed:** A 40px forest announcement strip precedes Navigation bar. The white hero begins with a generous 140px top inset, a centered 624px headline in two 80px lines, mint above forest, then a two-line 24px lead about 700px wide. Inline email form sits below with a broad breathing gap. The 1200px Circuit-backed product stage enters around the lower third of the first 900px viewport: the headline, lead, complete form and upper working interface are visible; most of the interface continues below the fold. Layers run white canvas, pale circuit panel, cool interface shell, crisp UI. A compact proof-logo treatment follows the product.

**Transfer:** Keep the promise narrow and the working object wide. If there is no finished product screen, construct a truthful three-part task interface rather than replacing the stage with an abstract blob. A narrower product-detail opening can use the same regular headline and stage relationship with a shorter lead.

**Avoid:** Do not make a split-screen hero, enlarge the form into a large signup card, or shrink the product to a tiny decorative thumbnail.

**Text style:** `display` — ABC Favorit 400 · 80px/1 · tracking -0.02em

### Inline problem sculpture

**Observed:** A centered 48px heading is interrupted by a compact run of overlapping application tiles and a red notification counter. An 18px explanatory paragraph and a short medium-weight pivot sit below; the visual frustration is embedded in the sentence rather than in a separate illustration.

**Transfer:** Insert a compact visual shorthand for the reader’s fragmented workflow between two short pieces of headline text. Use relevant small symbols and one legible count, not a full dashboard.

### Immersive introduction

**Observed:** Physical monitor scene fills a wide band behind a centered heading and lead; Photographic forest fade connects it to a six-item capability grid on Forest chapter. The grid uses three columns, mint diagrams and pale body copy.

**Transfer:** Use a human-scale context scene to introduce the new system, then translate its promise into a few compact capabilities.

### Alternating capability chapter

**Observed:** Within the main container, a roughly 793×480px Warm media panel sits beside a one-third text column aligned toward its lower edge. The column carries an icon badge, heading, 18px explanation and Discovery link. A 20px gap leads to a three-column strip of 387×220px miniatures, each followed by card-title and small copy. The next chapter reverses the large media and copy sides; chapters are separated by 160px.

**Transfer:** Repeat this construction only for genuinely distinct benefits. Keep the large scene focused on the overall capability and the small scenes on specific tasks.

**Text style:** `heading` — ABC Favorit 400 · 48px/50px · tracking -0.02em

### Dark reasons table

**Observed:** A centered heading and 24px lead introduce a narrow 793px argument area on Forest chapter. Two-column rows place a medium-weight reason and green link on the left and 18px explanatory prose on the right, with 40px row gaps. A short centered closing line caps the chapter.

**Transfer:** Use this for substantive differentiators and objections, not a second repeated card grid.

### Customer proof feature

**Observed:** A centered mono eyebrow and 48px heading lead into Featured proof: logo and story link at the top, a low-positioned quote and author on the left, Pink-washed customer scene on the right. Quote cards form a quieter two-column row beneath.

**Transfer:** Choose one visually prominent customer story, then reinforce it with shorter independent voices.

### Time-to-value milestones

**Observed:** A playful mono eyebrow sits above a centered two-line 48px heading. Three 24px medium time labels connect across the row with faint horizontal lines; below each is a cream checklist card with green checks and 15px text. The demonstration uses short minute-based milestones rather than giant KPI numerals.

**Transfer:** Turn adoption or workflow progress into three credible stages, using verified timing or named phases when exact timing cannot be supported.

### Trust reassurance

**Observed:** Two mint security marks precede a centered two-line heading and a 24px supporting paragraph within a narrower measure. Wide white space and a fine green separator make it feel reassuring rather than badge-heavy.

**Transfer:** Use relevant verified trust evidence and explain the operating principle behind it.

### Grid invitation and pale footer

**Observed:** Architectural closing grid carries Closing invitation with small proof marks and paired Primary button and Secondary button. The pale-green environment continues into a spacious footer: identity and small company details left, five columns of green links to the right. It ends as a useful sitemap, not a giant wordmark or a dark legal strip.

**Transfer:** Carry the final color environment through the whole ending. Adapt the column count to real destinations while preserving the distinct identity block and clear link hierarchy.

**Text style:** `heading` — ABC Favorit 400 · 48px/50px · tracking -0.02em

## Page flow

**Storyline:** promise → working product → shared problem → new approach → capability demonstrations → reasons to choose → human proof → adoption reassurance → trust → final invitation and useful sitemap

### A long-form product marketing landing page that makes a flexible technical platform feel usable and credible

1. **Promise** — Two-color centered headline, explanatory lead and a single-field conversion above a broad working interface.
2. **Social proof** — Compact monochrome customer marks and a small uppercase assurance.
3. **Problem framing** — A sentence interrupted by app tiles visualizes fragmentation.
4. **New approach** — Real-world monitor scene dissolves into a forest-green capability overview.
5. **Capability chapters** — Alternating two-thirds media and one-third copy stages with three supporting miniatures each.
6. **Differentiation** — Dark two-column argument rows explain performance, extensibility and ease of working together.
7. **Human proof** — Burgundy photographic flagship story with two quieter cream testimonials.
8. **Adoption reassurance** — Connected time milestones, compact checklist cards and a restrained trust statement.
9. **Closing call** — Green architectural grid, centered invitation, paired actions and a continuous pale-green sitemap footer.

**Transfer:** Adapt the length and grouping to the complexity of the new offer. Preserve the changes of register—working interface, human context, dark reasoning and pale closing—without treating every beat as a required separate section.

## Writing

Direct, capable and conversational. Technical flexibility is explained through practical work, with brief flashes of dry humor rather than breathless futurism.

**Do not copy:** Do not reuse Plain’s name, product names, customer identities, logos, quotations, security assertions, adoption timings or growth claims as assets or claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Talk directly to the reader as you and your team; use we sparingly for candid explanations. Name the product when explaining its concrete role.
- **Rhythm:** Short benefit headlines, often two to five words, followed by compact explanations with active verbs. Longer argument paragraphs earn their length by explaining mechanics; occasional paired sentences create a memorable finish.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An active verb and familiar job, followed by a personal-control phrase. | 5–8 words | “Build support your own way” |
| Capability heading | A short practical outcome rather than a feature taxonomy. | 2–4 words | “Automate everything”<br>“Learn from customers” |
| Supporting explanation | Describe what the system lets the reader do and what remains in their control. | One to three short sentences | “[Brand] is completely open, so you orchestrate your workload across any number of AI agents.” |
| Technical argument | Start with a reader need, then answer it in plain language. | Short prompt plus one paragraph | “When you demand complete extensibility” |
| Playful eyebrow | An occasional deadpan aside above a useful practical section. | One short line | “Time is money. Money is pizza.” |
| Action | Specific verb plus destination or next step. | 2–4 words | “Book a demo”<br>“Discover Workflows” |

**Words and phrasing to use:** build; your own way; connect; orchestrate; open; work; get smarter; start fast; scale; when you need

**Avoid:** revolutionary; unparalleled; magic; disrupt the future; synergize; one-size-fits-all superlatives

**Rules:**

- Make the headline about a result and the paragraph about how it works.
- Use concrete verbs and recognizable tasks before technical abstractions.
- Balance automation claims with human choice and control.
- Keep humor scarce and subordinate to useful information.
- Support quantified promises with defensible product facts.

## Do's and Don'ts

### Do

- Keep 80px display and 48px section headings regular, with -0.02em tracking.
- Set technical labels at 13px/19px in Geist Mono, uppercase with 0.015em tracking.
- Use a 1200px centered container with 20px card gutters.
- Keep ordinary media grounds warm cream and controls at 6px corners.
- Let the large interface enter the first 900px without squeezing out the promise and form.
- Use dark forest as an extended chapter and pale green as an extended ending.
- Make miniature product interactions legible and surround them with spare cream ground.
- Maintain the long outlined arrow after discovery labels.

### Don't

- Do not turn every heading bold or use heavy geometric display type.
- Do not use black as the default dark section fill; the dark field is forest #0a2414.
- Do not turn the 41px mono action controls into oversized pill buttons.
- Do not spread burgundy and pink across routine feature cards; they distinguish customer proof.
- Do not give every cream panel a drop shadow; opening interface depth is the exception.
- Do not use a dense all-over neon grid behind paragraphs; linework stays fine and peripheral.
- Do not make adoption milestones into enormous finance-style KPI numbers.
- Do not switch the ending to a generic charcoal footer; the pale-green conversion environment continues.

## Motion and responsive

### Motion

**Observed:**

- Footer text links declare color 0.4s cubic-bezier(0.44, 0, 0.56, 1), with an underline on hover.
- Product demonstrations include video-led scenes; detailed playback behavior is not specified.

**Transfer:**

- Keep link feedback subtle and let demonstrations communicate the actual task rather than adding ornamental motion.

**Unknown:**

- Video timing, scroll sequencing, full interaction states and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Width breakpoints include boundaries near 799px, 960px, 1070px, 1200px, 1249px and 1272px.

**Transfer:**

- For a narrow layout, keep the promise centered, put each large task scene above its explanation and stack detail cards so interface text remains usable. Preserve the pale closing grid with fewer peripheral divisions; let paired actions wrap rather than compressing their labels.

**Unknown:**

- Exact narrow-screen typography, navigation behavior and column transitions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
