# PlanetScale — the technical ledger

## Overview

A light, deliberately utilitarian style that feels like an engineer's public notebook rather than a polished sales deck. System monospace, charcoal rules, blue hyperlinks and small orange actions sit on off-white, with a sharp yellow announcement strip. Dense explanations, customer marks, plain diagrams and interface charts carry the persuasion; the surrounding space stays unembellished.

### Essentials

- Headlines behave like document titles, not billboards: 16px monospace, 700 weight, 24px line height, normal tracking, with a 2px orange rule on the opening title.
- The opening is a technical brief followed by visible proof: a left-aligned 1088px content area, two explanatory paragraphs separated by 24px, then a flush five-column logo matrix beginning within the first 900px.
- Actions look like compact utility controls: square orange rectangles, 32px high in navigation with 8px horizontal padding, paired with a 2px orange-outline alternative; content conversion actions grow to 40px.
- Color is punctuation on a predominantly #fafafa page: #414141 prose and borders, #0b6ec5 inline links, #f35815 actions and title markers, and one 40px-high #fbca00 announcement strip. Customer artwork keeps its own colors inside the proof grid.
- Proof is arranged as a ledger, not floating cards: 1px charcoal shared edges, centered customer marks in 128px-high cells, a 2px pale-gray quote rule, and text-size numerical claims. When customer marks are unavailable, use truthful named integrations or compact labeled proof artifacts in the same matrix.
- Document furniture is a signature device: dotted chapter dividers, a monochrome box-drawing schematic, and a dashed compartmentalized footer. Recreate the schematic using the new product's actual process, with a simple labeled flow as the minimum version; keep the line-work vocabulary even without elaborate media.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal yellow | `#fbca00` | `--color-announcement` | background | The shallow full-width announcement strip, not a general section background. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Reference blue | `#0b6ec5` | `--color-link` | link, border, accent | Inline references and outlined information notices; selected calculator choices also use blue. |
| Utility orange | `#f35815` | `--color-action` | action, accent, border | Primary actions, secondary action outlines and opening title rules. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control white | `#ffffff` | `--color-white` | surface, text | Button labels and calculator control faces. |
| Off-white canvas | `#fafafa` | `--color-canvas` | background, text | Continuous page canvas and inverse tab text. |
| Quotation gray | `#c1c1c1` | `--color-quote-rule` | border | Low-emphasis vertical quote rules and text separators. |
| Secondary gray | `#737373` | `--color-muted` | text | Attributions, captions and explanatory calculator text. |
| Charcoal ink | `#414141` | `--color-ink` | text, border | Default prose, navigation, solid rules and dashed document edges. |
| Inverse charcoal | `#111111` | `--color-inverse` | background, text | Selected product tab, tiny announcement link backing and announcement text. |
| Title black | `#000000` | `--color-black` | text | Opening title and linked section labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Inset gray | `#ebebeb` | `--color-inset` | surface | Code fields, inactive architecture choices and the calculator total backing. |
| pricing pages | Help ice blue | `#f3fbff` | `--color-help` | surface | Pale blue assistance card in the side rail. |
| pricing pages | Price green | `#13862e` | `--color-price` | text | Right-aligned calculated amounts and included-cost labels. |

## Typography

- **ui-monospace** — All marketing text, headings, links, actions and plain-text diagrams. System fixed-width lettering with a practical terminal-document character; hierarchy changes weight rather than size. Font stack: "ui-monospace", SFMono-Regular, "SF Mono", Menlo, Consolas, "Liberation Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| title | ui-monospace | 700 | 16px | 1.5 | normal | Opening title and bold section headings; section headings are underlined, while the opening title carries the orange rule. |
| body | ui-monospace | 400 | 16px | 1.5 | normal | Paragraphs, lists, captions and ordinary blue links; captions change color rather than size. |
| semibold | ui-monospace | 600 | 16px | 1.5 | normal | Navigation labels, emphasized phrases, footer headings and tab labels. |
| compact-action | ui-monospace | 600 | 16px | 1 | normal | Compact filled and outlined navigation actions. |
| announcement | ui-monospace | 500 | 16px | 1.5 | normal | Centered announcement sentence. |
| diagram | ui-monospace | 500 | 16px | 1.25 | normal | Monochrome box-drawing technical diagrams. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| service and customer-story conversion sections | content-action | ui-monospace | 600 | 16px | 1.25 | normal | 40px-high in-content conversion buttons. |
| customer stories | attribution-italic | ui-monospace | 400 italic | 16px | 1.5 | normal | Muted quote attribution on long-form customer stories. |
| pricing pages | control | ui-monospace | 400 | 16px | 22px | normal | Calculator dropdown text. |

**Notes:**

- Keep the almost flat type scale: the title, body, section heading and footer are all 16px. Weight, underlines, color, rules and spacing establish hierarchy.
- Use sentence case and normal tracking throughout; do not introduce oversized display type or uppercase eyebrow labels.
- Numerical proof remains in text-size prose or semibold calculator labels rather than becoming giant stat artwork.

## Layout

**Density:** Dense document content within a roomy outer frame; 24px paragraph and cell spacing makes the long technical reading flow deliberate.

### Spacing

**Spacing system:**

- **rhythm** 8px, vertical — Declared base spacing unit for paragraph gaps, cell padding and section separation.

| Value | Use |
| --- | --- |
| 8px | Small list gaps, control spacing and compact horizontal action padding. |
| 12px | Inset between a quote rule and its text. |
| 16px | Action-pair gap and title-rule inset. |
| 24px | Default paragraph margin, heading-to-copy gap and bordered-cell padding. |
| 32px | Space above navigation after the announcement strip. |
| 48px | Navigation-to-content gap, product-panel lead-in and desktop article-to-sidebar gap. |
| 80px | Footer's own top margin. |
| 96px | Desktop main-container side padding. |

### Containers and grids

- **main frame**: max width 1280px · side padding 96px. Centered outer main frame; at a 1440px viewport its usable content is 1088px wide.
- **navigation frame**: max width 1280px · side padding 40px. Navigation occupies 1200px within the wider outer frame and extends beyond the prose edges.
- **proof matrix**: 5 columns · gap 0px. Flush equal-width cells, approximately 219px wide including shared edges, 128px high; content is centered.
- **joined information grid**: 2 columns · gap 0px. Equal-width bordered cells for service steps, guides or expertise. Adjacent borders overlap rather than doubling.
- **footer compartments**: 5 columns · gap 0px. 1088px-wide dashed directory aligned to the main prose; five approximately 218px columns.
- **article with rail** (only for pricing pages and customer stories): 2 columns · gap 48px. 752px main article or calculator next to a 288px rail inside the 1088px content width.

## Corner radius

| Element | Radius |
| --- | --- |
| marketing controls and panels | 0px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing pages | calculator select | `0px 1px 2px 0px rgba(0, 0, 0, 0.05)` | Only the native-looking dropdown face has a faint raised edge. |

### Surfaces

#### Canvas · level 0

**Use:** The uninterrupted light page ground.

**CSS:** `background: #fafafa; color: #414141`

**Observed:** No alternating dark marketing bands or atmospheric backdrops.

**Transfer:** Let information density and line work create the composition.

#### Ruled panel · level 0

**Use:** Product explanation, joined information cells and closing conversion boxes.

**CSS:** `border: 1px solid #414141; border-radius: 0px; padding: 24px; box-shadow: none`

**Observed:** Panels retain the page ground and sit flush with neighboring cells.

**Transfer:** Group related text without turning every paragraph into a separate card.

#### Dashed document edge · level 0

**Use:** Footer compartments and their legal band.

**CSS:** `background-image: repeating-linear-gradient(0deg, #414141, #414141 12px, rgba(0, 0, 0, 0) 12px, rgba(0, 0, 0, 0) 16px), repeating-linear-gradient(90deg, #414141, #414141 12px, rgba(0, 0, 0, 0) 12px, rgba(0, 0, 0, 0) 16px), repeating-linear-gradient(0deg, #414141, #414141 12px, rgba(0, 0, 0, 0) 12px, rgba(0, 0, 0, 0) 16px), repeating-linear-gradient(270deg, #414141, #414141 12px, rgba(0, 0, 0, 0) 12px, rgba(0, 0, 0, 0) 16px); background-size: 1px 100%, 100% 1px, 1px 100%, 100% 1px; background-position: 0px 0px, 0px 0px, 100% 0px, 0px 100%; background-repeat: no-repeat`

**Observed:** Long 12px dashes with 4px interruptions form 1px edges, not a filled crosshatch. Shared internal edges appear only once.

**Transfer:** Keep the drafting-paper quality; use separate edge layers so dash lengths remain controlled.

#### Calculator help · level 0

**Only for:** pricing pages

**Use:** Small side-rail assistance panel.

**CSS:** `background: #f3fbff; border: 1px solid #414141; padding: 24px`

**Observed:** The only colored assistance-card fill is extremely pale.

**Transfer:** Reserve this treatment for contextual help rather than general feature cards.

#### Calculator inset · level 0

**Only for:** pricing pages

**Use:** Total backing and code or inactive control areas.

**CSS:** `background: #ebebeb`

**Observed:** Gray inset areas remain flat and square.

**Transfer:** Use a gray backing to distinguish an output or copyable field from descriptive prose.

## Components

### Navigation

**Use:** Compact global directory and actions above the opening brief.

**CSS:** `background: #fafafa; margin-top: 32px; margin-bottom: 48px`

**Text style:** `semibold` — ui-monospace 600 · 16px/1.5

**Observed:** A 32px brand mark at left precedes text menus with small down carets and pale vertical pipe separators. Sign-in and paired outlined/filled actions sit right. The desktop content spans 1200px; the header is in normal flow.

**Transfer:** Keep the navigation as a text directory rather than a floating capsule.

### Announcement strip

**Use:** A single high-signal product update above navigation.

**CSS:** `background: #fbca00; color: #111111; padding: 8px 24px; text-align: center`

**Text style:** `announcement` — ui-monospace 500 · 16px/1.5

**Observed:** A 40px strip spans the viewport. The short inline Learn more link has an inverse charcoal backing, white semibold text and 4px horizontal padding.

**Transfer:** Use one factual update, not a carousel of promotional messages.

### Primary button

**Use:** Default compact navigation conversion action.

**CSS:** `background: #f35815; color: #ffffff; height: 32px; padding: 0px 8px; border-radius: 0px; display: flex; align-items: center; justify-content: center`

**Text style:** `compact-action` — ui-monospace 600 · 16px/1

**Observed:** Text-only square control. Service and customer-story content actions use the content-action recipe with 8px 16px padding and 40px height; the pricing total uses a 40px action with compact-action type.

**States:** Declared: hover color #0b6ec5 on content conversion actions; focus-visible outline-style none and zero box-shadow on these actions.

**Transfer:** Size width to the label, not to an arbitrary uniform button width.

### Outline button

**Use:** Secondary trial or interactive-preview action beside the primary navigation action.

**CSS:** `border: 2px solid #f35815; color: #414141; height: 32px; padding: 0px 8px; border-radius: 0px; display: flex; align-items: center; justify-content: center`

**Text style:** `compact-action` — ui-monospace 600 · 16px/1

**Observed:** The canvas remains visible inside the outline; it is not a pale-orange filled button.

### Inline reference

**Use:** Specific supporting documentation and linked technical terms inside prose.

**CSS:** `color: #0b6ec5; text-decoration: none`

**Text style:** `body` — ui-monospace 400 · 16px/1.5

**Observed:** Blue text flows within sentences without icon badges or extra backing. Linked section labels instead use bold black underlined text.

**States:** Declared: hover color #0b6ec5; focus-visible outline-style none and zero box-shadow.

### Proof tile

**Use:** Customer or integration marks in the social-proof matrix.

**CSS:** `border: 1px solid #414141; height: 128px; margin: -0.5px; display: flex; align-items: center; justify-content: center`

**Observed:** Marks are centered at roughly three quarters of the cell width, with differing intrinsic aspect ratios. Their own colors remain intact and the backing stays off-white.

**Transfer:** Normalize optical weight, not each mark's exact width.

### Product tab

**Use:** Switching between related technical product explanations.

**CSS:** `background: #111111; color: #fafafa; padding: 16px 0px; border-right: 1px solid #414141; text-align: center`

**Text style:** `semibold` — ui-monospace 600 · 16px/1.5

**Observed:** Three flush equal-width tabs form a 56px-high row above a Ruled panel. The selected tab is inverse; inactive tabs retain the page ground and ink labels.

**Transfer:** Use succinct product names and keep the explanatory diagram inside the panel.

### Quote

**Use:** Customer testimony inserted into technical prose.

**CSS:** `border-left: 2px solid #c1c1c1; padding-left: 12px; margin-top: 16px; margin-bottom: 16px`

**Text style:** `body` — ui-monospace 400 · 16px/1.5

**Observed:** No quote glyph sculpture, portrait card or colored background. Attribution is a separate muted line; customer stories use the attribution-italic recipe.

**Transfer:** Place a relevant operational observation next to the claim it substantiates.

### Information cell

**Use:** Joined benefits and process steps.

**CSS:** `border: 1px solid #414141; padding: 24px; margin: -0.5px; border-radius: 0px`

**Text style:** `body` — ui-monospace 400 · 16px/1.5

**Observed:** Bold text-size title, then a 24px gap to explanatory prose. Process cells use numbered linked headings; expertise cells use plain bold headings.

**Transfer:** Allow height to follow content while maintaining common row edges.

### Footer column

**Use:** The recurring compartmentalized directory at the end of every page.

**CSS:** `padding: 24px; min-height: 240px`

**Text style:** `body` — ui-monospace 400 · 16px/1.5

**Observed:** Uses Dashed document edge with semibold underlined heading, a 24px gap and stacked plain links at 24px line height. Five columns share edges; a full-width dashed legal compartment sits below, with a separate pipe-separated social row outside.

**Transfer:** Preserve the directory and legal-band construction even on short landing pages.

### Calculator select

**Only for:** pricing pages

**Use:** Region and resource configuration within the estimator.

**CSS:** `background: #ffffff; border: 1px solid #414141; height: 42px; padding: 0px 8px; display: flex; align-items: center; justify-content: space-between; gap: 8px; box-shadow: 0px 1px 2px 0px rgba(0, 0, 0, 0.05)`

**Text style:** `control` — ui-monospace 400 · 16px/22px

**Observed:** A gray outlined down chevron sits right. Resource choices can contain a dark compact identifier followed by capacity text; calculated prices align independently to the right in green.

**States:** Declared: hover unspecified; focus-visible outline-style none, border-color #1e9de7 and box-shadow 0px 1px 2px 0px rgba(0, 0, 0, 0.05).

**Transfer:** Use compact real inputs rather than a decorative pricing-card simulation.

## Imagery and graphics

### Proof matrix artwork

**Use:** The dominant opening visual proof.

**Observed:** A large flush grid of customer wordmarks and symbols on off-white, with black and saturated native-color marks centered behind thin charcoal edges. It is much larger than the opening text and extends well below the fold.

**Transfer:** Use legitimate customer or integration artwork. A text-only labeled proof matrix is the minimum equivalent when no mark library exists.

### Plain-text system schematic

**Use:** A technical explanatory object inside the product panel.

**Observed:** A centered monochrome box-drawing diagram uses rectangular primary and replica nodes, branching dashed connectors, arrowheads and shaded character fields. It is flat, black, and visually closer to terminal output than illustration.

**Transfer:** Diagram the new product's actual path from input through processing to output. Minimum version: a few named boxes and connected branches on the same canvas.

**Build:** Use a pre element in the diagram recipe with box-drawing Unicode, preserved whitespace and centered alignment. Draw one wide input box, split to three middle boxes, then paired smaller output boxes. If using SVG, retain square 1px charcoal strokes, dashed branching connectors, small triangular arrowheads and monospace labels; no gradients or perspective.

### Interface benchmark figure

**Use:** Visual substantiation within a capability chapter.

**Observed:** A light real interface chart is aligned to the prose left edge, with white plot panels, fine gray gridlines, a compact metric tab row and a purple latency trace. A muted caption beneath names what the chart demonstrates; the surrounding section stays off-white.

**Transfer:** Use a real measurement or product view with modest chart colors. Keep its native interface framing, with no device mockup, tilt, glow or ornamental scene.

### Dotted chapter rule

**Use:** A recurring divider between major prose chapters.

**Observed:** Small charcoal dots run horizontally across the reading width, making a terminal-document separator rather than a heavy bar.

**Transfer:** Include this line-work device to punctuate technical chapters without introducing colored bands.

**Build:** Use a horizontal SVG with a 1px charcoal line, round line caps and a short dash array, or a repeated radial gradient of small charcoal dots on transparent. Keep the dots visually about 2px across at regular approximately 9.6px intervals; let the line span its parent prose column.

### Customer identity rail

**Only for:** customer stories

**Use:** Supplementary proof alongside a long-form article opening.

**Observed:** A customer mark sits above asterisk-led outcome statements, an update paragraph and a blue related-reading link. Figures stay at body size; the rail has no card backing.

**Transfer:** Use the featured organization's identity plus a few verified outcomes, leaving the article as the wider reading column.

### Icons

**Observed:** Very sparse functional icons: a 32px filled brand mark, 22px gray dropdown chevrons with 1px rounded strokes, and a 16px charcoal copy icon with 1px strokes. Asterisks, pipes and arrows do much of the visual signaling.

**Transfer:** Prefer typographic markers for lists and navigation separators. Add small thin outline icons only when they clarify a real control.

## Section recipes

How recurring sections are built.

### First screen: Technical brief opening

**Observed:** Back to front: uninterrupted Canvas, full-width Announcement strip, normal-flow Navigation, then a left-aligned title and explanatory text with no overlapping art. The content starts 48px below the 32px navigation. The title is a single 16px/24px bold line marked by a 2px orange left rule inset 16px outside the prose alignment. Two body paragraphs follow with 24px gaps and blue inline references; the first occupies four desktop lines and the second three. A short proof introduction precedes the five-column Proof tile matrix, beginning at 464px down the page. Within the first 900px, the entire brief and about three rows plus the start of another proof row are visible. The rest of the matrix, product panel and technical chapters lie below. Conversion actions are in the upper-right navigation rather than an oversized hero action cluster.

**Transfer:** Use a strong text-size category promise, a concrete explanation and a substantial verified proof matrix as the first-screen object. Without logos, use named integrations or compact proof artifacts in the same ruled structure. Service pages open with two shorter paragraphs and a 40px action plus blue text link, bringing a process grid into the first screen. Pricing opens with a blue-bordered information notice and calculator; customer stories open with a bold summary, quote and identity rail.

**Avoid:** Do not center a giant headline, add a large decorative hero render, or push all proof below an empty viewport-height opening.

**Text style:** `title` — ui-monospace 700 · 16px/1.5

### Technical chapter

**Observed:** A bold underlined 16px section heading introduces body paragraphs after 24px. Blue references stay inline; asterisk lists use 8px item gaps and modest left indentation. Dotted chapter rules separate major topics. A chart or Quote can substantiate a specific claim without changing the section background.

**Transfer:** Organize capabilities as readable technical chapters with concrete operating details, not a sequence of inflated promotional headlines.

**Text style:** `title` — ui-monospace 700 · 16px/1.5

### Tabbed explanation

**Observed:** Product tab row above a Ruled panel spanning 1088px. Explanation paragraphs precede a centered Plain-text system schematic and a supporting Quote.

**Transfer:** Let related product modes share one explanatory stage while preserving real differences in the content.

### Joined process or expertise grid

**Observed:** Information cell components meet on a two-column grid with shared 1px edges. Numbered process steps form a two-by-two group; expertise cells repeat across more rows. Longer guide cells can contain multiple paragraphs, bold sublabels and asterisk-linked lists.

**Transfer:** Use equal-width cells for peer steps or capabilities and preserve natural content height.

**Text style:** `body` — ui-monospace 400 · 16px/1.5

### Directory ending

**Observed:** All page types end with Footer column compartments over the same Canvas. Five joined dashed columns lead into a dashed legal band; pipe-separated social links sit outside below. The main marketing ending can be a final Quote, while a pricing ending remains explanatory prose and a contact reference rather than forcing another conversion banner.

**Transfer:** Retain the recognizable dashed directory device; choose the preceding closing beat according to the page's purpose.

### Resource estimator

**Only for:** pricing pages

**Observed:** A 752px bordered calculator and 288px explanatory rail are separated by 48px. Each calculator chapter has 24px padding, text-size underlined heading, muted support and Calculator select or numeric controls. Costs align right in green. The gray total area has a second inner border and an orange action; expertise grid and detailed plan prose follow.

**Transfer:** Expose meaningful configuration and billing factors before explaining commercial tiers. Keep the estimator part of the marketing document rather than a separate dark application.

### Long-form customer narrative

**Only for:** customer stories

**Observed:** A 752px reading column with a 288px Customer identity rail opens with text-size title, semibold summary and Quote. Subsequent short underlined headings organize paragraphs and asterisk lists with semibold lead-ins. Quotes recur throughout; attribution is muted italic.

**Transfer:** Tell a concrete before, decision, implementation and after story, with relevant testimony distributed through the article.

### Closing invitation

**Only for:** service and customer-story pages

**Observed:** A short bold heading, 24px-separated support paragraph and orange 40px action beside a blue text link. The service version is unboxed; the customer-story version is a 752px Ruled panel after a back-to-index link. Both leave a substantial pause before the directory.

**Transfer:** Offer a specific next step and a lower-commitment reference without introducing a giant closing slogan.

## Page flow

**Storyline:** Specific promise → concrete proof or task → technical explanation → operational reassurance → appropriate next step → compartmentalized directory.

### Broad product marketing with deep technical credibility

1. **Promise** — Compact ruled title and explanatory paragraphs.
2. **Social proof** — Extensive flush logo matrix followed by a quote.
3. **Product explanation** — Tabbed technical explanation and box-drawing diagram.
4. **Capability chapters** — Underlined labels, prose, a benchmark figure, asterisk lists and relevant quotes.
5. **Detailed specification** — Dense feature groups with inline references.
6. **Closing proof** — Final customer quote and attribution, then dashed directory rather than an extra CTA band.

**Transfer:** Lead with credible proof and support each capability with operating details; adapt the amount of detail to the new audience.

### Price discovery and commercial objection handling

1. **Task framing** — Small title and blue-bordered catalog-access notice.
2. **Configuration** — Stacked ruled calculator with explanatory side rail and help box.
3. **Price output** — Green amount and compact action in gray double-framed total area.
4. **Service proof** — Joined two-column expertise grid.
5. **Commercial explanation** — Base and enterprise prose, billing factors, eligibility lists and contact link.
6. **Directory** — Dashed footer without an additional large sales call.

**Transfer:** Provide usable pricing mechanics first, then explain what requires a conversation.

### Turn a high-risk service decision into a clear assisted process

1. **Reassurance** — Text-size title, two short paragraphs and paired action/reference.
2. **Process** — Numbered two-by-two information grid.
3. **Objection handling** — Short eligibility, cost and self-service chapters divided by rules.
4. **Options** — Joined guide cells with linked methods.
5. **Closing call** — Unboxed invitation, consultation action and documentation link.
6. **Directory** — Shared dashed footer.

**Transfer:** Make the process and alternatives explicit before repeating a specific assistance offer.

### Validate the product through a detailed customer outcome

1. **Outcome** — Compact title, semibold summary, opening quote and customer proof rail.
2. **Context and problem** — Underlined chapters and bold-led challenge lists.
3. **Decision and implementation** — Plain paragraphs and interleaved operational quotes.
4. **Results** — Text-size numerical outcomes and benefit lists.
5. **Partnership** — Support chapter and final relationship summary.
6. **Closing call** — Back-to-index link, boxed conversion invitation, then dashed directory.

**Transfer:** Use the customer's practical experience as the narrative spine, keeping results integrated with prose rather than detached oversized stat cards.

## Writing

Confident engineering prose, explicit about architecture, tradeoffs and practical help. Persuasion comes from mechanisms and operational proof, with occasional dry humor rather than glossy aspiration.

**Do not copy:** Do not reuse PlanetScale product names, customer marks, customer quotations, benchmark outcomes, pricing amounts, availability claims or security certifications as claims for another product. Replace them with independently valid content and assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the team and you or your for the reader's practical needs. Name the product directly when explaining a mechanism.
- **Rhythm:** Short sentence-case section labels punctuate substantial explanatory paragraphs. Lists use compact factual clauses; actions are direct verbs. Plain language can sit beside precise specialist terminology.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | State the product category and its defining operating advantage directly. | About 8–12 words | “The world’s fastest and most scalable cloud databases” |
| Section label | A short noun or a practical question, not a miniature campaign slogan. | 1–7 words | “Performance”<br>“How it works”<br>“Want to migrate on your own?” |
| Support | Acknowledge a real concern, then explain who does what. | One or two substantive sentences | “Database migrations don't have to be scary. Our migration specialists handle the entire process for you, from assessment to cutover, so you can focus on building.” |
| Action | Verb plus a specific practical next step. | 2–5 words | “View sandbox”<br>“Start your migration”<br>“Schedule a migration consultation” |
| Testimony | Specific first-person operational observation, allowing understated humor. | One short paragraph | “The actual cutover was almost comically boring, which is exactly where I wanted to be after all the upfront work we put in.” |

**Words and phrasing to use:** fully online; no downtime; requirements; workload; custom; built for; run; manage; view documentation; reach out

**Avoid:** revolutionary journey; magical experience; unlock your potential; limitless possibilities; effortless everything

**Rules:**

- Pair an advantage with its mechanism, limits or supporting documentation.
- Name alternatives and supported paths when that makes the reader's decision easier.
- Keep commercial invitations candid and concrete rather than creating urgency.
- Use bold lead-ins for scan-friendly technical lists and link the exact noun a reader needs explained.

## Do's and Don'ts

### Do

- Keep title and body at 16px with 24px line height; distinguish them with 700 versus 400 weight.
- Align prose to the 1088px desktop reading frame and let navigation extend to 1200px.
- Use 24px cell padding and shared 1px charcoal edges for peer information.
- Keep the 40px yellow strip shallow and its message centered.
- Use blue text references inside explanatory sentences instead of detached link badges.
- Repeat the dashed footer compartments, legal band and external social row.
- Keep quote text at body size with a 2px gray rule and separate muted attribution.
- Give diagrams square nodes, visible labels and genuine branching relationships.

### Don't

- Do not substitute a proportional sans for the all-monospace marketing document.
- Do not enlarge numeric results into 80px stat callouts; they remain 16px prose or semibold labels.
- Do not add 16px rounded card corners, soft ambient shadows or glass effects to the ruled panels.
- Do not wash every chapter with orange or blue; page-level color is concentrated in links, compact controls and the announcement.
- Do not replace the flush proof matrix with separated floating logo pills.
- Do not turn the footer into a dark full-bleed band; its dashed compartments remain on #fafafa.
- Do not shrink captions and attributions to 12px to manufacture hierarchy; change to muted gray instead.
- Do not convert the practical asterisk lists into oversized illustrated feature tiles.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare all-property transitions of .15s cubic-bezier(.4, 0, .2, 1); calculator controls declare the same duration and easing for color, border, shadow and related properties.
- No matched keyframe animations. Hover is primarily text-color change; dropdown chevrons declare rotation for the open state.

**Transfer:**

- Keep the document composition steady; use the declared short transitions for utility controls rather than animating prose or proof cells.

**Unknown:**

- Whether any declared transitions were triggered and whether tab changes animate.

### Responsive

**Observed:**

- Declared width breakpoints: 640px, 768px, 801px, 1024px, 1280px and 1536px.
- Main container classes specify 24px side padding at base, 40px from the small breakpoint, and 96px at the large breakpoint.
- Proof matrix declares two columns at base and five at the medium breakpoint. Joined information cells declare one then two columns; footer declares one, two and five columns.
- The text schematic declares hidden below medium, 12px/16px at medium and 16px/20px at large. Product tabs declare a vertical stack below medium.
- The outlined sandbox action declares hidden below the small breakpoint.

**Transfer:**

- Preserve the ledger on narrow screens by reducing column counts rather than scaling the whole page down.
- For a narrow-screen replacement of the hidden wide schematic, use a compact vertical labeled flow so its explanatory function remains available.
- Stack the article and rail with the declared 24px gap and maintain text-size headings.

**Unknown:**

- Mobile navigation interaction and actual narrow-screen rendering were not observed.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
