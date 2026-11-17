# Duties — angular type, tangible proof

## Overview

A light, gallery-like identity with eccentric condensed capitals and a matter-of-fact grotesk voice. Warm paper, charcoal and grey keep the architecture restrained while richly staged photography and graphic work carry the color. It suits design-led products and services that can show their value through tangible examples, with dense little labels separated by unusually long pauses.

### Essentials

- Headlines behave like cut-metal lettering: angular condensed capitals at 160px/0.8, weight 500, normal tracking, centered in a 675px-tall opening rather than stretched across the entire screen.
- The opening is a poster followed by an operating strip: a two-line promise about 926px wide, a 68px status rail beneath it, then the first media pair entering the first 900px. Navigation is a separate 40px-high dock fixed 20px above the bottom.
- Actions are small pieces of hardware, not oversized pills: neutral dock tiles have 6px corners and 12px horizontal padding with 14px/1 semibold labels; the dark brand tile leads the group.
- Color belongs to the work rather than the page: #f1f0ee remains the continuous canvas, #252525 and #646464 divide text roles, and bright interface color is confined to tiny selected controls and a 14px green availability dot.
- Proof is staged as objects in the world: pair a 476px portrait with a 904px landscape at equal 603px heights and a 20px gutter, reversing their order across examples. If no photography exists, create a real-material product mockup beside a flat graphic demonstration.
- Explanations keep heading and paragraph at the same visual rank: 32px/1.1 semibold, dark short lead immediately followed by grey explanatory lines, capped at 960px, with 160px pauses between topics.
- The closing identity is an illustration, not another sales banner: reserve a 900px paper-colored ending for a centered 320×342px black emblem, small status text above and four compact information columns below. Create an original rough-edged emblem when the product has no mascot.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#252525` | `--color-ink` | text, surface, action | Display lettering, section leads, primary actions and the brand navigation tile. |
| Explanatory grey | `#646464` | `--color-muted` | text, surface | Support statements and captions; also the dark header strips on structured service panels. |
| Translucent stone | `#dfded8` | `--color-control` | surface, action | Visible neutral navigation and tag fill; rgba(211,210,202,0.6) over warm paper. |
| Warm paper | `#f1f0ee` | `--color-canvas` | background, text | Continuous page canvas and inverse action labels. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Availability green | `#5fe37c` | `--color-available` | accent | 14px availability indicator beside a short status phrase. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interior-page navigation | Electric navigation blue | `#0800ff` | `--color-selected` | action, surface | Selected interior navigation tile only; not a section background. |
| portfolio filtering and case-study information | Pure selection blue | `#0000ff` | `--color-filter` | action, surface | Active category filter and the small information control. |
| case-study metadata | Solid metadata grey | `#dad9d8` | `--color-metadata` | surface | Small solid tags in the sticky project information rail. |
| service and offer explanations | Pale mauve grey | `#e7e4e4` | `--color-panel` | surface | Specification panels, process rows, tier bodies and client-logo tiles. |
| proof panels and service explanations | Clean white | `#ffffff` | `--color-white` | surface, text | Testimonial surface and inverse labels on grey panel headings. |

## Typography

- **AS Therma Medium Condensed** — Opening headlines. Very narrow, angular display lettering with faceted corners and irregular stencil-like counters. If unavailable, use **Teko**. Use weight 500; preserve the narrow proportions and tight line stacking, though the angular detailing will differ. Font stack: "AS Therma Medium Condensed", "Teko", sans-serif.
- **PP Neue Montreal** — Section statements, captions, navigation, tables and the live clock. Compact neo-grotesk, predominantly semibold, with a high x-height and economical line spacing. If unavailable, use **Inter**. Use weights 600 and 700; preserve normal tracking. Font stack: "PP Neue Montreal", "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | AS Therma Medium Condensed | 500 | 160px | 0.8 | normal, uppercase | Centered one- or two-line opening promise. |
| statement | PP Neue Montreal | 600 | 32px | 1.1 | normal, features "case", "cpsp" | Short section heading and its longer explanatory statement; use ink then muted grey. |
| body | PP Neue Montreal | 600 | 16px | 1.2 | normal | Media captions, project names, explanatory panel copy and footer information. |
| clock | PP Neue Montreal | 700 | 16px | 1 | normal, uppercase, features "ss07", "ss08" | Compact centered time readout within the operating strip. |
| control | PP Neue Montreal | 600 | 14px | 1 | normal | Navigation, action labels and ordinary category tags. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| service and offer explanations | offer-subheading | PP Neue Montreal | 600 | 25px | 1.1 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Paired heading introducing smaller engagements. |
| case-study metadata | case-tag | PP Neue Montreal | 600 | 12px | 1.1 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss04", "ss07", "ss08", "zero" | Compact sticky-rail project categories. |

**Notes:**

- Keep normal tracking throughout; the personality comes from the display letterforms and compressed 0.8 line height, not artificial negative letter spacing.
- Section explanations are headings in scale, not small body paragraphs. The lead and the following grey sentence share exactly the same recipe.
- The declared semibold text cut belongs to the same family as the clock; do not introduce a separate UI font. Keep decorative serif typography inside project artwork, not in the marketing hierarchy.

## Layout

**Density:** Airy at section level, compact inside labels and panels; large empty paper intervals make the small controls and photographic proof feel deliberate.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Navigation tile separation. |
| 5px | Tag separation and name-to-caption inline gap. |
| 10px | Media-to-caption spacing, panel stacking and compact offer-grid gutters. |
| 20px | Page edges, paired-media gutter and panel padding. |
| 40px | Space before closing actions and related-work cards. |
| 60px | Editorial card-grid column gutters. |
| 120px | Section-heading-to-content gap and card-grid row gaps. |
| 160px | Pause between the stacked explanatory topics. |
| 240px | Bottom breathing room after major proof and content sections. |
| 96px | Footer lower clearance for the floating dock. |

### Containers and grids

- **page frame**: max width 1440px · side padding 20px. Full-width paper composition with a 1400px usable desktop field.
- **statement column**: max width 960px. Left-aligned explanatory heading pairs, leaving the right side open or available for a supporting image.
- **panel text**: max width 560px. Body copy inside broader specification panels.
- **asymmetric media pair**: 2 columns · gap 20px. Equal-height portrait and landscape frames, 476px and 904px wide at desktop; reverse the narrow and wide positions across examples.
- **portfolio grid**: 4 columns · gap 60px. 305px-wide cards with 406px portrait imagery; row spacing is 120px.
- **service examples**: 3 columns · gap 60px. 427px-wide proof cards with roughly 533px-high images.
- **offer grid** (only for service and offer explanations): 4 columns · gap 10px. 343px-wide aligned tiers with a shared header, body and action construction.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | navigation and actions | 6px |
|  | media and service panels | 5px |
|  | category tags | 2px |
|  | availability dot | 50% |
| interior-page navigation | selected navigation | 16px |
| case-study metadata | case tags | 1px |
| testimonial proof | testimonial | 4px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Every page and ordinary section.

**CSS:** `background: #f1f0ee; color: #252525`

**Observed:** The same warm neutral continues behind images, explanations and the entire closing identity; no alternating dark page theme.

**Transfer:** Separate chapters with whitespace and occasional thin grey rules, not alternating colored bands.

#### Stone glass · level 1

**Use:** Navigation tiles and neutral controls.

**CSS:** `background: rgba(211, 210, 202, 0.6); border-radius: 6px; backdrop-filter: blur(16px)`

**Observed:** Low-opacity stone remains legible over imagery. Tags use the same fill without blur and with smaller corners.

**Transfer:** Use this modest glass treatment only for compact floating controls.

#### Specification panel · level 1

**Only for:** service and offer explanations

**Use:** Lists, deliverables, process rows, tier bodies and logo tiles.

**CSS:** `background: #e7e4e4; border-radius: 5px; padding: 20px; box-shadow: none`

**Observed:** Flat pale panels are paired with detached grey header strips; they are not outlined cards.

**Transfer:** Group factual content without adding elevation.

#### Proof paper · level 1

**Only for:** testimonial proof

**Use:** Quotation panel.

**CSS:** `background: #ffffff; border-radius: 4px; padding: 20px`

**Observed:** White distinguishes the quotation from the warmer page without a shadow or visible border.

**Transfer:** Keep testimonial emphasis in typography and scale rather than decorative effects.

## Components

### Dock link

**Use:** Persistent page navigation.

**CSS:** `background: rgba(211, 210, 202, 0.6); color: #252525; height: 40px; padding: 0px 12px; border-radius: 6px; backdrop-filter: blur(16px); display: flex; align-items: center; justify-content: center`

**Text style:** `control` — PP Neue Montreal 600 · 14px/1

**Observed:** A compact four-tile dock sits fixed at bottom center with 2px gaps and 20px bottom clearance. It has no enclosing capsule. Interior selected links become electric blue with 16px corners and paper-colored lettering.

**Transfer:** Use three short destinations plus a brand tile; keep the dock visually separate from the top status rail.

### Brand tile

**Use:** Leading home action in the floating dock.

**CSS:** `background: #252525; height: 40px; padding: 0px 12px; border-radius: 6px; backdrop-filter: blur(24px)`

**Observed:** A small light wordmark is centered inside the dark tile, approximately 41px wide, rather than repeated as a large conventional header logo.

**Transfer:** Use a compact wordmark or short brand name.

### Category tag

**Use:** Right-aligned metadata under large media pairs.

**CSS:** `background: rgba(211, 210, 202, 0.6); color: #252525; height: 28px; padding: 2px 10px 3px 10px; border-radius: 2px; display: flex; align-items: center; justify-content: center`

**Text style:** `control` — PP Neue Montreal 600 · 14px/1

**Observed:** Two to four tags sit in a row with 5px gaps. Case-study rail variants use solid metadata grey, 8px padding, 1px corners and the case-tag recipe. Portfolio filters use this ordinary tag construction with a pure-blue, rounded selected control.

**Transfer:** Keep labels short and categorical rather than sentence-like.

### Operating strip

**Use:** A slim identity, time and availability rail separating the opening poster from content.

**CSS:** `display: flex; align-items: center; gap: 20px; padding: 20px; background: #f1f0ee; height: 68px`

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

**Observed:** Three equal zones: small dark dot and identity left, compact live clock centered, status at right. A thin grey lower line defines the rail, which stays at the top during the main content. A green 14px circle with a 5px gap accompanies the status. Case-study variants replace time with tags and status with an information button.

**Transfer:** Use a truthful operating signal such as availability, release status or local time.

### Media caption

**Use:** One-line editorial annotation below paired imagery.

**CSS:** `display: flex; align-items: center; gap: 20px`

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

**Observed:** An ink project name and muted description share the left half, separated by 5px; Category tags align to the far right. The row follows imagery by 10px. In smaller grids the name and muted descriptor stack.

**Transfer:** Name the example, then give a concise outcome, without a boxed card wrapper.

### Footer information

**Use:** Compact practical information below the closing emblem.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(1px, 1fr)); gap: 20px; padding: 20px 20px 96px 20px`

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

**Observed:** Four left-aligned groups carry establishment, location, social links and reach. Muted labels precede darker information; there is no large legal sitemap.

**Transfer:** Use four concise groups appropriate to the new product, preserving open space above.

### Primary action

**Only for:** case-study conversion and offer selection

**Use:** Discovery action or tier selection.

**CSS:** `background: #252525; color: #f1f0ee; height: 40px; padding: 8px 12px; border-radius: 6px; backdrop-filter: blur(30px); display: flex; align-items: center; justify-content: center`

**Text style:** `control` — PP Neue Montreal 600 · 14px/1

**Observed:** Closing conversion rows use a content-width dark action beside a neutral secondary action, with 10px separation. Tier actions stretch to the panel width; none becomes a large promotional pill.

**Transfer:** Use an equally short verb-and-object action appropriate to the product.

### Panel heading strip

**Only for:** service and offer explanations

**Use:** Detached header for specifications and tier bodies.

**CSS:** `background: #646464; color: #ffffff; padding: 10px 20px; border-radius: 5px`

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

**Observed:** The short grey header is separated from its pale body by 10px. Offer headers use 20px padding, with the same flat geometry.

**Transfer:** Use one plain label; distinguish included details from outcomes in parallel columns.

### Process row

**Only for:** service and offer explanations

**Use:** A numbered delivery or implementation phase.

**CSS:** `background: #e7e4e4; border-radius: 5px; padding: 20px; display: flex; align-items: flex-start; gap: 20px`

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

**Observed:** Rows align number, phase title, goal and slash-prefixed deliverables in four equal columns. A shared Panel heading strip labels the columns. Rows are separated by 10px and grow to fit their content.

**Transfer:** Use short ordered phases and concrete outputs instead of a decorative timeline.

### Quotation panel

**Only for:** testimonial proof

**Use:** Substantial customer quotation with attribution.

**CSS:** `background: #ffffff; border-radius: 4px; padding: 20px; display: flex; align-items: flex-start; gap: 20px`

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

**Observed:** A large black quotation glyph occupies the left portion; quote and bottom attribution sit in the wider right column. The panel fills roughly three quarters of the field; two stacked stone arrow buttons occupy the remainder, each about 348×155px.

**Transfer:** Use an approved customer quote with compact name and role; preserve the unusually generous arrow-button targets.

## Imagery and graphics

### Tangible product proof

**Use:** Dominant media chapters after the opening.

**Observed:** Devices on pink tables, brushed metal, terracotta and wooden floors sit beside outdoor billboards, print spreads and dimensional signs. Close portrait framing contrasts with wider environmental views. Directional daylight, soft reflections, real grain and occasional hard shadows keep polished work tactile; color lives mainly within these frames. Images fill their frames with small 5px corners, not heavy device-window chrome.

**Transfer:** Pair one close product detail with one environmental application: for software, a real screen on a desk and a larger workflow or usage scene. Minimum acceptable version is a carefully lit device mockup on a textured physical surface beside a crisp full-frame product demonstration.

### Closing black emblem

**Use:** Signature identity artwork within the closing paper section.

**Observed:** A rough-edged black cartoon emblem, about 320×342px, floats centrally in a much larger field. Blocky opposing faces inside a skewed frame and boot-like legs create a handmade stamp character rather than a glossy mascot.

**Transfer:** Create an original emblem that compresses the new product's personality into a single black silhouette. A custom initial or simple object with imperfect edges is an acceptable minimum; it must still serve as a substantial closing artwork.

**Build:** Draw an original silhouette in SVG with a 320×342 viewBox. Use ink-filled closed paths, a slightly tilted frame or main body, a few generous paper-colored cutouts and irregular 1–2px edge deviations. Keep all shapes flat, with no gradient, shadow or 3D extrusion. Center within a tall paper field, leaving substantially more space around it than its own width.

### Dithered identity studies

**Only for:** monochrome case-study artwork

**Use:** Graphic companions to photographed brand applications.

**Observed:** Grayscale portraits, ships and overlapping circular forms become coarse square-pixel dithers on charcoal or pale grounds; white marks overlay some compositions. The surrounding page remains warm paper.

**Transfer:** Use this only when the project's identity supports a monochrome archival texture; it is not a global background.

**Build:** Convert an original grayscale image to a low-resolution bitmap, apply ordered or diffusion dithering, then enlarge with nearest-neighbor sampling so square dots remain visible. Mask into two overlapping circles for an abstract study, or keep a full portrait frame. Use a charcoal and grey two-tone range with a light mark on top.

### Playful pastel identity studies

**Only for:** illustrative case-study artwork

**Use:** Flat graphic counterparts to tactile photographs.

**Observed:** Cream-backed compositions carry thin dark outlines, lilac and lime cartoon objects and editorial serif lettering. Pink street media and warm sunlit objects extend that project's palette; these are artwork styles rather than the site's text system.

**Transfer:** Let each showcased product own its own illustration language while the surrounding layout remains neutral.

**Build:** For a similarly playful project, draw a few original outlined objects as SVG paths with flat pastel fills, sparse black detail and no soft gradient. Combine one dominant object with two small accent shapes on a cream field; keep marketing typography outside the artwork unchanged.

### Studio detail

**Only for:** company introduction sections

**Use:** Small supporting image beside a broad statement column.

**Observed:** A 335×420px portrait of an ordinary studio interior with a poster, doorway and kitchen gives the organization a physical setting, captioned with a small dark dot.

**Transfer:** Choose a real workplace or product-making detail with natural light rather than a staged corporate team portrait.

### Icons

**Observed:** The interface is largely icon-free: small filled brand artwork, dark or green circular markers, a bold quote glyph and restrained left/right arrows around 17×14px. No recurring feature-icon grid.

**Transfer:** Use simple arrows for direction and dots for status. Keep illustrative objects inside media, not beside every heading.

## Section recipes

How recurring sections are built.

### First screen: Poster opening

**Observed:** A 675px-tall Paper canvas holds a centered two-line condensed-capital promise, about two thirds of the desktop width. Display lettering is 160px/0.8, with the visible glyph mass concentrated in the middle of the poster and broad empty paper above and below. Layers are paper, dark headline, then the separate Operating strip at the poster's lower edge; the Dock link group floats independently near the viewport bottom. Within the first 900px the complete headline, operating rail and top of a portrait/landscape media pair are visible. There is no support paragraph or hero conversion button. Media begins around 763px and its caption lies below the fold.

**Transfer:** Write a compact two-line product promise with equally strong silhouette, then let concrete product proof enter at the bottom. Without photography, stage an original flat product demonstration beside a textured device scene. Case studies open with a short outcome headline and project metadata; collection and service pages retain the same poster scale but lead into their own content rather than forcing a media pair.

**Avoid:** Do not turn the opening into a left-aligned SaaS split hero with a paragraph, oversized CTA and screenshot floating beside the headline.

**Text style:** `display` — AS Therma Medium Condensed 500 · 160px/0.8 · uppercase

### Paired proof chapter

**Observed:** Asymmetric media pair spans the 1400px content field at 603px height with a 20px gutter. A Media caption follows by 10px; the section then leaves 240px below. Narrow/wide placement alternates across chapters. Case-study galleries reduce the chapter separation to 20px and add full-width images or three 453px portraits.

**Transfer:** Show complementary evidence of one outcome per pair. Use larger pauses between different examples and tighter continuity within one extended case study.

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

### Heading and explanation

**Observed:** A short ink lead sits immediately above a muted sentence, both using statement typography in a left-aligned 960px column. Repeated topics have 160px vertical gaps. A smaller right-side image can support the text without turning it into equal columns.

**Transfer:** Use this device for benefits, fit, timing, cost or product principles, selecting only the topics needed by the new narrative.

**Text style:** `statement` — PP Neue Montreal 600 · 32px/1.1

### Emblem ending

**Observed:** A 900px Paper canvas begins with a fine rule and small version/status labels at opposite ends. Closing black emblem is centered in the broad upper-middle field, about 207px below the top. Footer information occupies the lower band with 96px bottom clearance; the floating dock remains visible. All five page types share this ending, with no giant sales headline replacing the artwork.

**Transfer:** Always conclude with original identity artwork and compact practical information. Keep the quiet scale contrast between the isolated emblem and the small four-column text.

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

### Portfolio collection

**Only for:** example libraries and related-work sections

**Observed:** Four columns of 305×406px portrait images use 60px column gaps and 120px row gaps. Name and muted description stack below with a 10px image gap. Related-work sections use two such cards clustered on the left below a statement heading, leaving the right field open. A centered category selector lives in the sticky rail on collection pages.

**Transfer:** Use consistent portrait frames for comparable examples; keep a smaller left-clustered selection for onward discovery.

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

### Specification chapter

**Only for:** service and offer explanations

**Observed:** Heading and explanation introduces a 120px pause before two equal-width panels. Panel heading strip sits above each Specification panel, one for included work and one for outcomes. A three-column image proof row follows. The Process row treatment extends the same construction into a four-column table.

**Transfer:** Explain what is delivered and what changes for the buyer, then demonstrate the result rather than adding another abstract feature list.

**Text style:** `statement` — PP Neue Montreal 600 · 32px/1.1

### Engagement comparison

**Only for:** service and offer explanations

**Observed:** Four equal tiers use 10px gutters, separate grey headers, pale bodies and full-width Primary action footers. Descriptions sit high in the bodies; compact price and duration lines sit at the bottom, all using body rather than giant price numerals. A 120px gap introduces smaller options in a left-heading/right-list composition.

**Transfer:** Compare offers with equal visual weight; align common facts so the reader can scan without a highlighted oversized plan.

**Text style:** `body` — PP Neue Montreal 600 · 16px/1.2

### Recognition and client proof

**Only for:** credential-heavy service explanations

**Observed:** Two broad columns pair a compact list of recognitions with a status statement. Names are muted and inline counts such as 'x 11' are dark, both 32px/1.1, with no stat-card decoration. The next split section puts an explanatory heading on the left and a three-column grid of 223×137px pale logo tiles with 10px gaps on the right.

**Transfer:** Use only relevant verified credentials and monochrome customer marks; distinguish the recognition list from the customer's logo wall.

**Text style:** `statement` — PP Neue Montreal 600 · 32px/1.1

### Closing invitation

**Only for:** case-study conversion

**Observed:** An ink question and muted invitation share a 960px statement column. A pair of compact actions follows after 40px, with 10px between dark and neutral controls. The section has 20px top inset and 240px bottom breathing room before the emblem ending.

**Transfer:** Offer a low-pressure next step that acknowledges fit, not a high-volume promotional banner.

**Text style:** `statement` — PP Neue Montreal 600 · 32px/1.1

## Page flow

**Storyline:** Poster promise → tangible evidence → plain-language explanation → relevant proof or decision support → distinctive identity ending.

### Introduce a design-led offer through demonstrated outcomes

1. **Promise** — Centered two-line poster above the operating rail.
2. **Demonstration** — Large alternating portrait/landscape proof pairs with compact captions and tags.
3. **Decision support** — Stacked dark-lead/grey-statement topics explain benefit, fit, timing and terms.
4. **Human context** — Broad introduction beside one small workplace detail.
5. **Identity ending** — Isolated black emblem, operating status and four practical information columns.

**Transfer:** Lead with persuasive evidence before lengthy explanation; use the same devices for a different product without preserving the original number of examples.

### Present a monochrome identity system as an extended case study

1. **Outcome promise** — Short poster headline and project metadata rail.
2. **Context** — Opening media pair then a 960px information statement with 240px vertical padding.
3. **System demonstration** — Environmental signs, print, device scenes and dithered artwork in paired, full-width and three-column formats.
4. **Onward discovery** — Two related portrait cards clustered left.
5. **Conversion** — Low-pressure invitation with dark and neutral actions.
6. **Identity ending** — Shared emblem ending.

**Transfer:** Use coherent project-specific material and texture while retaining the neutral page architecture.

### Present a colorful illustrative identity as an extended case study

1. **Outcome promise** — Two-line poster headline and metadata strip.
2. **Context** — Device and illustration pair followed by the broad information statement.
3. **System demonstration** — Pastel illustration, sunlit street applications, printed objects and interface demonstrations alternate at matching heights.
4. **Onward discovery** — Two compact related examples on the left.
5. **Conversion** — Question, candid fit statement and paired actions.
6. **Identity ending** — Shared emblem ending.

**Transfer:** Let the showcased product's own palette and art direction change inside imagery, not the overall marketing typography or background.

### Help visitors browse a body of examples

1. **Collection promise** — Large centered two-line poster.
2. **Discovery** — Sticky category filters above a four-column portrait grid.
3. **Social proof** — White quote panel beside two large stacked arrow controls.
4. **Identity ending** — Shared emblem ending without an extra conversion banner.

**Transfer:** Use a consistent card format and a small vocabulary of filters, then substantiate the work with a real quotation.

### Explain capabilities, delivery and buying options

1. **Promise** — Three-part outcome phrase set as a two-line poster.
2. **Audience fit** — Dark heading followed immediately by a grey statement.
3. **Capability chapters** — Broad statements, paired specification/outcome panels and three-column recent examples.
4. **Delivery clarity** — Numbered process table with flat pale rows.
5. **Offer comparison** — Four equally weighted tiers, then smaller options.
6. **Credentials** — Recognition counts and status in two columns, then a right-side client-logo grid.
7. **Identity ending** — Shared emblem ending.

**Transfer:** Use the structured panel language only where detailed purchase decisions need it; preserve generous gaps between dense factual groups.

## Writing

Direct, commercially aware and candid. Confidence comes from specificity about work, outcomes and fit rather than inflated adjectives; the tone is approachable without becoming chatty.

**Do not copy:** Do not reuse Duties names, project identities, emblem artwork, customer quotations, addresses, prices, recognition counts or proprietary claims. Source examples illustrate cadence only; replace them with truthful content for the new product.

- **Addressing the reader:** Use 'we' for the maker and 'you' or 'your' for the buyer. Descriptions can be neutral fragments, while explanations speak directly about the buyer's situation.
- **Rhythm:** Short noun-like labels lead longer explanatory sentences. Opening lines are compact enough for one or two centered lines; support statements often run two to four lines. Short declarative fragments break up practical explanations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the outcome and the intended audience, or use a compact three-part transformation. | 4–9 words | “BRANDS and websites for BRAVE companies”<br>“Your brand: defined, designed, deployed” |
| Section lead | Plain topic or direct buyer question; no abstract editorial flourish. | 1–4 words | “What we do”<br>“When to engage”<br>“Proof” |
| Support statement | Explain the practical business benefit and remove ambiguity. | 1–3 short sentences | “We work on a fixed-price basis, scoped to your project. No hourly billing, no surprises. Just a clear price for a defined outcome.” |
| Media descriptor | Compact positioning phrase immediately after a name. | 4–9 words | “The talent partner for ambitious companies”<br>“Decisions for the physical world” |
| Action | Concrete verb plus the next step; low commitment and explicit. | 2–5 words | “Book a discovery call”<br>“View all work”<br>“View tier” |
| Closing invitation | Ask about readiness, then explain what the conversation will resolve. | One question plus a brief invitation | “Ready to invest in how your company is perceived?” |

**Words and phrasing to use:** defined outcome; ready to invest; trust; clear; scoped; launch; your team; the right fit

**Avoid:** revolutionary; game-changing; unlock limitless potential; best-in-class; disrupt everything; excessive exclamation marks

**Rules:**

- State deliverables and results separately when practical details matter.
- Use candid exclusions or fit criteria to build trust.
- Keep navigation literal and short; avoid clever labels that obscure the destination.
- Use numerals for real quantified proof, not decorative invented statistics.

## Do's and Don'ts

### Do

- Keep the hero at 160px/0.8 with centered condensed capitals on paper.
- Keep ordinary prose and captions semibold at 16px/1.2.
- Use the same 32px/1.1 recipe for dark section leads and grey support.
- Anchor the small 40px navigation dock 20px from the lower edge.
- Stage proof at equal image heights with 20px gutters and small 5px corners.
- Give major chapters 240px of lower breathing room.
- Retain the original black-emblem ending and the compact four-column information band.
- Use flat 5px panels and detached grey headers for detailed comparisons.

### Don't

- Do not use the illustrative serif fonts inside showcased work as the page's heading family.
- Do not expand selected-control blue into broad brand-colored sections.
- Do not turn neutral 6px navigation tiles into a single giant enclosing pill.
- Do not reduce explanatory statements to 16px body copy beneath oversized section headings.
- Do not add card shadows to the flat pale specification panels.
- Do not make prices into oversized hero numerals; they remain compact factual lines.
- Do not wrap every photographic example in a bordered text-heavy card.
- Do not add decorative feature icons throughout an otherwise almost icon-free interface.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains fixed at the lower center while the operating rail sticks to the top as content scrolls.
- A live clock changes in the operating rail; several proof frames contain video.
- No action-specific hover, focus-visible or transition recipes are established.

**Transfer:**

- Keep the two navigation layers independent: the upper operating signal and lower destination dock.
- If proof uses video, preserve its frame dimensions and editorial pairing with still imagery.

**Unknown:**

- Durations, easing assignments, hover/focus transformations and media-reveal behavior are not established.

### Responsive

**Observed:**

- Styles include width boundaries around 810px, 1199px and 1679px.

**Transfer:**

- On narrow layouts, preserve the centered poster and short line count while reducing display size to fit; this is adaptation guidance, not a fixed fluid formula.
- Stack portrait/landscape proof pairs and factual panels while retaining their small gutters and caption hierarchy.
- Reflow information columns without removing the emblem ending or the compact bottom navigation; reserve clearance so the dock does not cover final information.

**Unknown:**

- Exact narrow-screen type sizes, spacing, card column counts and rail behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
