# Foodnoms — rounded everyday optimism

## Overview

A bright, approachable product style with rounded geometric sans-serif lettering and a clean white canvas. Warm orange actions and a vivid orange ending give otherwise restrained gray surfaces a cheerful pulse, while blue, violet and green distinguish capabilities. Large, realistic device presentations make the interface the main visual attraction; short marketing passages feel spacious, while comparison content becomes deliberately denser and more editorial.

### Essentials

- Friendly geometry without inflated type: Aquawax Pro uses 56px/1.1 bold display, 36px/1.2 section headings and normal tracking, with rounded letterforms doing the expressive work.
- A small promise above a very large product parade: center a two-line heading, orange first line and near-black second line, above 18px/1.6 support and one action; stage 330×675px upright product views with 24px gaps and clipped outer edges.
- Compact lozenge actions, not oversized conversion bars: 40px height, 20px radius, 12px 18px padding and 16px/1 semibold labels ending in ↗.
- Color is punctuation until the ending: keep the long page white, group demonstrations on #f2f2f2 cards, reserve blue/orange/violet/green for feature headings and small symbols, then finish with a broad orange 25px-radius panel.
- Proof is shown through usable interfaces rather than abstract art: pair 239px-wide product views with short colored headings inside 590×400px cards; if device media is unavailable, frame a polished working interface at the same scale and crop.
- A warm, inset sign-off is a signature device: an orange footer sits 32px inside the canvas with 40px padding, a compact stacked white identity on the left and four link groups on the right; legal links remain on white below.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brand orange | `#f8622e` | `--color-orange` | action, accent, surface, link | Primary actions, first hero line, identity, text links and the large footer fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Capability orange | `#f67724` | `--color-warm` | text | A warmer orange for feature headings, distinct from the action orange. |
| Capability blue | `#2196f2` | `--color-blue` | text | Short feature headings in demonstration cards. |
| Cloud cyan | `#1ba6d8` | `--color-cyan` | accent | Small filled reassurance symbol. |
| Capability violet | `#5856d6` | `--color-violet` | text, accent, surface | Capability headings and symbols; a solid reversed plan panel and plan status checks on subscription pages. |
| Peach hover | `#fba182` | `--color-hover` | link | Navigation and footer text-link hover color. |
| Capability green | `#4db04f` | `--color-green` | text | Short feature headings in demonstration cards. |
| Shield blue | `#7ca1c2` | `--color-slate` | accent | Small filled reassurance symbol. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Heading ink | `#0d0d0d` | `--color-ink` | text | Display, section and small headings. |
| Body charcoal | `#333333` | `--color-body` | text | Paragraphs, comparison content and legal links. |
| Support gray | `#666666` | `--color-muted` | text, link | Hero support, closing support and navigation links. |
| Divider gray | `#e6e6e6` | `--color-rule` | border | Fine horizontal separators in comparison content. |
| Soft gray | `#f2f2f2` | `--color-card` | surface | Feature cards, neutral plan card and secondary action backing. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Default canvas and reversed text on saturated surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| comparison and plan tables | Unavailable gray | `#cccccc` | `--color-disabled` | accent, border | Unavailable status circles and stronger table header separators. |

## Typography

- **Aquawax Pro** — All marketing headings, body copy, navigation and actions. Rounded geometric sans with open bowls, soft terminals and a friendly single-storey character; medium body weight keeps the small text substantial. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss01", "ss02", "ss03". If unavailable, use **Quicksand**. Use weights 500, 600 and 700; preserve normal tracking and tune line breaks to the measured widths. Font stack: "Aquawax Pro", "Quicksand", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Aquawax Pro | 700 | 56px | 1.1 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss01", "ss02", "ss03", "ss07" | Centered two-line marketing promise; orange lead line and near-black product line. |
| heading | Aquawax Pro | 700 | 36px | 1.2 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss01", "ss02", "ss03", "ss07" | Section leads, social proof and closing calls. |
| card-heading | Aquawax Pro | 700 | 28px | 1.2 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss01", "ss02", "ss03", "ss07" | Feature-card titles, plan titles and editorial subheadings. |
| small-heading | Aquawax Pro | 700 | 22px | 1.4 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss01", "ss02", "ss03", "ss07" | Reassurance headings and press-introduction label; violet product-tier eyebrow on subscription pages. |
| lead | Aquawax Pro | 500 | 18px | 1.6 | normal | Centered hero and final-call support. |
| group-label | Aquawax Pro | 700 | 17px | 1.4 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss01", "ss02", "ss03", "ss07" | Footer column headings; comparison-table column labels. |
| body | Aquawax Pro | 500 | 16px | 1.6 | normal | Card descriptions, reassurance text, editorial paragraphs and table rows. |
| action | Aquawax Pro | 600 | 16px | 1 | normal | Compact pill action labels. |
| navigation | Aquawax Pro | 500 | 15px | 1 | normal | Header and footer links and the small legal line. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial comparison pages | article-title | Aquawax Pro | 700 | 44px | 1.1 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11", "dlig", "ss01", "ss02", "ss03", "ss07" | Left-aligned, multi-line article title within an 800px reading column. |

**Notes:**

- Keep tracking normal at every size; friendliness comes from the letter shapes, not loose spacing or condensed display cuts.
- Use weight 500 for body, 600 only for compact actions, and 700 for headings. The family’s Bold, Medium and DemiBold cuts belong to one visual family.
- Display is only moderately larger than section headings. Preserve the 56px to 36px relationship rather than turning the opening into a monumental typographic poster.

## Layout

**Density:** Airy between narrative blocks, compact within each block; product imagery occupies much more space than its supporting copy.

### Spacing

**Spacing system:**

- **horizontal-step** 8px, horizontal — Organizes outer gutters, common container gaps and wider horizontal separation; 20px card-grid gaps and 18px button padding are deliberate exceptions.

| Value | Use |
| --- | --- |
| 10px | Heading-to-description and compact stacked text gaps. |
| 16px | Plan-matrix row-to-rule separation. |
| 20px | Feature-card grid gap and footer link-group rhythm. |
| 24px | Support-to-action gap, phone-gallery gap and icon-to-heading gap. |
| 32px | Outer canvas inset and inner feature-card column gap. |
| 40px | Card and footer inner padding. |
| 48px | Device montage to closing text, and header item gaps. |
| 64px | Reassurance columns and footer-column separation. |
| 96px | Main page-stack rhythm and action-to-product-gallery separation. |
| 126px | Expanded separation between capability grid, reassurance strip and testimonial area. |

### Containers and grids

- **marketing-container**: max width 1200px · side padding 32px. Centered navigation and feature content; at 1440px the inner content begins 120px from the edge.
- **wide-ending**: max width 1400px · side padding 32px. Inset footer and broad proof area, extending beyond the main marketing column.
- **centered-copy**: max width 800px. Hero support and final call; compact section titles can narrow to 600px.
- **feature-grid**: max width 1200px · 2 columns · gap 20px. Equal 590px-wide demonstration cards, two across.
- **reassurance-grid**: max width 1200px · 3 columns · gap 64px. Centered 300px-wide icon-and-copy groups without card backings.
- **plan-matrix** (only for subscription pages): max width 1000px · 3 columns · gap 32px. Feature label takes 500px, each plan column 218px; a separate 800px-wide pair of summary cards precedes it.
- **reading-column** (only for editorial comparison pages): max width 800px. A single left-aligned article with no side rail.

## Corner radius

| Element | Radius |
| --- | --- |
| cards-and-footer | 25px |
| action-pills | 20px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** The continuous page backing.

**CSS:** `background: #ffffff`

**Observed:** No alternating colored section bands or atmospheric effects; whitespace connects the content.

**Transfer:** Let the interface media and the final orange panel carry the page’s color.

#### Soft demonstration card · level 1

**Use:** Capability demonstrations and neutral plan summaries.

**CSS:** `background: #f2f2f2; border-radius: 25px; box-shadow: none`

**Observed:** Flat, borderless and softly rounded; imagery can be clipped by the card’s lower edge.

**Transfer:** Use tone rather than elevation to group related copy and product proof.

#### Orange ending panel · level 1

**Use:** The signature footer surface.

**CSS:** `background: #f8622e; color: #ffffff; border-radius: 25px; padding: 40px; box-shadow: none`

**Observed:** Broad inset rectangle; identity and grouped navigation share one plane.

**Transfer:** Retain this concentrated block of saturated color even on otherwise text-heavy pages.

#### Premium plan panel · level 1

**Only for:** subscription pages

**Use:** Paid-tier summary beside a neutral entry tier.

**CSS:** `background: #5856d6; color: #ffffff; border-radius: 25px; padding: 40px`

**Observed:** Same shape and padding as its gray partner; violet fill, not a badge or outline, distinguishes the tier.

**Transfer:** Keep the comparison visually balanced instead of enlarging the paid card.

## Components

### Navigation

**Use:** Lightweight top-level navigation.

**CSS:** `max-width: 1200px; display: flex; align-items: center; gap: 48px; height: 40px`

**Text style:** `navigation` — Aquawax Pro 500 · 15px/1

**Observed:** Small orange icon-and-name lockup on the left, three muted links beside it, and Primary button pushed to the far right; no filled header bar.

**Transfer:** Use only a few utility links so the product opening stays dominant.

### Primary button

**Use:** Header and subscription opening conversion action.

**CSS:** `background: #f8622e; color: #ffffff; border-radius: 20px; padding: 12px 18px; height: 40px; display: flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `action` — Aquawax Pro 600 · 16px/1

**Observed:** Short verb-led text with a northeast arrow kept inline; width follows label length rather than a fixed wide column.

### Secondary button

**Use:** Default marketing closing action.

**CSS:** `background: #f2f2f2; color: #f8622e; border-radius: 20px; padding: 12px 18px; height: 40px; display: flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `action` — Aquawax Pro 600 · 16px/1

**Observed:** Centered beneath the closing support line; deliberately lower visual intensity than the header action.

### Utility link

**Use:** Header navigation and footer navigation.

**CSS:** `color: #666666; text-decoration: none; transition: color 0.4s cubic-bezier(0.44, 0, 0.56, 1)`

**Text style:** `navigation` — Aquawax Pro 500 · 15px/1

**Observed:** No icon container or underline. Footer variant is white on the orange panel; outbound destinations append ↗.

**States:** Declared: hover color color(display-p3 .984314 .631373 .509804), no underline; focus-visible not specified.

### Feature card

**Use:** Product capability plus a directly related interface view.

**CSS:** `background: #f2f2f2; border-radius: 25px; height: 400px; padding: 40px 40px 0px; display: flex; align-items: center; gap: 32px; overflow: clip`

**Text style:** `card-heading` — Aquawax Pro 700 · 28px/1.2

**Observed:** Short colored heading and Body description form a narrow left column; an upright device fills the right column and is cut off at the bottom. Headings cycle blue, warm orange, violet and green, while paragraphs remain charcoal.

**Transfer:** Keep one task per card and use an actual task screen rather than a decorative icon in place of proof.

### Reassurance item

**Use:** Compact statements of product principles or practical guarantees.

**CSS:** `max-width: 300px; display: flex; flex-direction: column; align-items: center; gap: 24px; text-align: center`

**Text style:** `small-heading` — Aquawax Pro 700 · 22px/1.4

**Observed:** A filled 40px symbol sits above a heading and a 16px paragraph; heading-to-paragraph gap is 10px. Three items sit directly on white.

### Footer panel

**Use:** Navigation-rich sign-off across all page types.

**CSS:** `background: #f8622e; color: #ffffff; border-radius: 25px; padding: 40px; display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-start`

**Text style:** `group-label` — Aquawax Pro 700 · 17px/1.4

**Observed:** A compact stacked white identity occupies the left; four link columns occupy the right with 64px separation. Links use Utility link in white. A centered charcoal copyright and legal row is outside the panel below it.

**Transfer:** Use the new identity as a simple two-line typographic lockup if no suitable compact logo exists.

### Plan summary

**Only for:** subscription pages

**Use:** Entry and paid tier summaries before detailed feature comparison.

**CSS:** `background: #5856d6; color: #ffffff; border-radius: 25px; padding: 40px; display: flex; flex-direction: column; gap: 10px`

**Text style:** `card-heading` — Aquawax Pro 700 · 28px/1.2

**Observed:** Title, one short benefit paragraph and a smaller regional-pricing note. The entry-tier partner uses Soft demonstration card with dark text; both cards have equal width and height.

**Transfer:** Keep pricing explanations compact; avoid a large price numeral when the buying flow supplies regional pricing.

### Plan comparison row

**Only for:** subscription pages

**Use:** Detailed, scannable availability matrix.

**CSS:** `display: flex; align-items: center; gap: 32px; max-width: 1000px`

**Text style:** `body` — Aquawax Pro 500 · 16px/1.6

**Observed:** Wide left label, two centered value columns. Each row is separated by a 1px divider with 16px clearance. Available features use 16px filled orange or violet check circles; unavailable features use gray cross circles. Some rows use short text instead of symbols.

**Transfer:** Preserve text equivalents for all availability symbols and align each plan’s statuses consistently.

### Editorial comparison table

**Only for:** editorial comparison pages

**Use:** A concise factual comparison embedded in prose.

**CSS:** `display: table; width: 800px`

**Text style:** `body` — Aquawax Pro 500 · 16px/1.6

**Observed:** Three columns with unequal widths; cells use 12px 16px padding and 1px light-gray bottom rules. Header uses a gray fill and a stronger 2px bottom rule. No outer card, shadow or rounded table frame.

**Transfer:** Compare equivalent capabilities in plain language and allow wrapped multi-line cells.

## Imagery and graphics

### Upright product parade

**Use:** Primary visual demonstration beneath the opening promise.

**Observed:** Five equally scaled upright phones, 330×675px each with about 24px gaps; central phone is fully visible horizontally while outer phones run beyond the viewport. Black and metallic device edges surround light interfaces. Screens show real tasks, charts and camera input; the page behind them stays pure white. Subscription openings use a contained three-phone row.

**Transfer:** Show distinct workflows at the same scale, front-facing and level. If physical devices are irrelevant, use tall rounded application panels with a thin dark bezel and real interface content; retain the wide, edge-clipped parade.

**Build:** Lay out five 330px-wide media panels in a centered flex row with 24px gap and no shrink. Clip horizontal overflow at the section, not at each panel’s screen. Use dark rounded device frames, a fine metallic inner edge, and light UI interiors; keep all tops on one baseline.

### Task demonstration closeups

**Use:** Inside Feature card.

**Observed:** A 239×489px phone view stands in a roughly 360px-high clipping window, so the card cuts off its lower portion. The media begins above the copy block’s center and occupies approximately half the card width. Camera imagery stays inside the product interface rather than becoming a page background.

**Transfer:** Choose one legible task state tied to the adjacent heading; keep device scale consistent from card to card.

### Cross-device closing montage

**Use:** Above the main marketing closing call.

**Observed:** An 800×347px montage presents a laptop behind a tablet, with phone and watch stepping down toward the right. Front-facing screens show the same light product family; colored desktop wallpaper is confined to the laptop. All objects sit on white with a shared low baseline and no decorative pedestal.

**Transfer:** Show the product’s genuinely supported formats as an overlapping size hierarchy. Without multiple devices, use one wide polished interface view with a smaller related view overlapping its right edge.

### Monochrome press marks

**Use:** Compact credibility row after the main product parade.

**Observed:** Muted gray publisher marks sit in two centered rows under a 22px bold label, with ample white surrounding space.

**Transfer:** Use verified partner or publication marks at balanced optical sizes and one neutral color.

### Icons

**Observed:** Simple filled silhouettes, not thin outlined pictograms: reassurance symbols are 40×40px in muted blue, cyan and violet. Availability symbols are 16×16px filled circles with white checks or crosses. Outbound actions use a small inline northeast arrow.

**Transfer:** Choose solid, rounded symbols with few details. Use icon color to label a capability, not a different colored container behind every symbol.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and product parade

**Observed:** White canvas, then Navigation at a 32px top inset within 1200px. After 96px of breathing room, a compact centered two-line Display promise begins: warm orange task line over near-black product line, about 410px wide for the short wording. Lead support follows at 10px and a black platform-download badge at 24px, about 120×40px. A further 96px gap introduces Upright product parade, extending past both edges. Within the first 900px, the whole navigation, headline, support, action and upper portions of the phones are visible; full phone bottoms and the press row fall below. There is no hero card, gradient or background scene.

**Transfer:** Keep the promise short and center it above a visually much wider product stage. Without native device artwork, use the framed interface-panel construction in Upright product parade. Subscription openings add a violet Small-heading eyebrow, use an all-dark 56px promise and Primary button, then three contained phone views. Editorial openings retain the header but switch to an 800px left-aligned Article-title and prose rather than a product stage.

**Avoid:** Do not turn this into a split text/image hero, full-bleed photograph or giant background headline; the contrast is a small centered text stack above an oversized horizontal interface parade.

**Text style:** `display` — Aquawax Pro 700 · 56px/1.1

### Capability demonstration grid

**Observed:** Feature-grid holds equal Feature cards in two columns with 20px gutters. Each card pairs a colored Card-heading and a short Body paragraph with a clipped Task demonstration closeup. No section banner or repeated eyebrow is added above each card.

**Transfer:** Use the same card proportions for the strongest tasks, keeping copy concise enough for the narrow left column.

**Text style:** `card-heading` — Aquawax Pro 700 · 28px/1.2

### Reassurance strip

**Observed:** Three Reassurance items span the main column on white, with 64px gaps and 300px text widths. Each has a 40px filled symbol, 24px gap to the text group and 10px between heading and paragraph.

**Transfer:** Express three genuinely distinct sources of confidence using specific short statements.

**Text style:** `small-heading` — Aquawax Pro 700 · 22px/1.4

### Human proof strip

**Observed:** A centered 36px heading sits above a broad horizontal collection of pale-gray rounded review cards. Each visible card opens with orange stars, then a compact dark quote and small attribution. Outer cards are clipped by the page edge; proof feels like many individual voices rather than one oversized testimonial.

**Transfer:** Use verified short reviews with the same stars-to-quote-to-attribution hierarchy. Keep the row broad and visually subordinate to the heading; never leave a large empty proof region.

**Text style:** `heading` — Aquawax Pro 700 · 36px/1.2

### Low-pressure final call

**Observed:** The main marketing ending places Cross-device closing montage above centered copy with a 48px gap. Heading and Lead support are separated by 10px; Secondary button follows at 24px. Subscription endings omit the montage but retain the same 800px centered copy and action. Editorial endings instead use a left-aligned heading, paragraph and orange inline download link. All lead into Footer panel after 96px.

**Transfer:** Restate the practical benefit and remove one adoption concern. Keep the action modest and let the orange ending panel provide the visual finish.

**Text style:** `heading` — Aquawax Pro 700 · 36px/1.2

### Plan differentiation

**Only for:** subscription pages

**Observed:** Two equal Plan summary cards sit in an 800px grid with a 20px gap: gray entry tier and violet paid tier. After 96px, a 1000px-wide matrix presents Group-label column headings and Plan comparison rows with hairline rules.

**Transfer:** Use the pair to explain the basic distinction, then let the matrix resolve detailed availability questions.

**Text style:** `card-heading` — Aquawax Pro 700 · 28px/1.2

### Editorial answer chapters

**Only for:** editorial comparison pages

**Observed:** An 800px reading column uses a 44px title, italic updated-date line, 16px/1.6 paragraphs, 36px chapter headings and 28px subheadings. Paragraphs sit about 20px apart; new topics receive about 40px separation. Bullet lists have 10px item gaps and bold lead phrases. Editorial comparison table appears within this same column. FAQ questions are full visible subheadings and answers, not accordion cards.

**Transfer:** Lead with a useful answer, support with facts and equivalent comparisons, then handle objections in plain text. Keep long-form density scoped to decision-support pages.

**Text style:** `article-title` — Aquawax Pro 700 · 44px/1.1

## Page flow

**Storyline:** Simple promise → concrete product demonstration → capability and trust proof → decision support → low-pressure action → saturated navigational sign-off.

### General product landing page

1. **Promise** — Centered two-tone headline, one support sentence and platform download badge.
2. **Product demonstration** — Edge-clipped phone parade followed by muted press marks.
3. **Capability proof** — Colored task headings and clipped interface demonstrations in a neutral two-column card grid.
4. **Trust proof** — Unboxed reassurance strip and a broad collection of small review cards.
5. **Closing call** — Cross-device montage, practical reassurance and Secondary button.
6. **Sign-off** — Inset orange Footer panel and legal row on white.

**Transfer:** Use concrete product proof early, then alternate dense visual objects with short readable text blocks; the exact number and order of proof modules can change.

### Long-form comparison and switching guide

1. **Promise** — Left-aligned article title and updated date.
2. **Decision summary** — Opening answer, concise rating proof, price explanation and feature lists.
3. **Structured comparison** — Three-column table followed by capability chapters with bold-led bullets.
4. **Objection handling** — Free-versus-paid explanation and an extended set of visible questions and answers.
5. **Closing call** — Short invitation with inline orange action, then the shared orange footer.

**Transfer:** Answer real buying questions directly and retain the plain reading column instead of forcing every point into marketing cards.

### Subscription feature and tier explanation

1. **Promise** — Violet tier eyebrow, centered display title, support and orange pill.
2. **Product demonstration** — Three equal upright phone views.
3. **Tier differentiation** — Matched gray and violet summaries.
4. **Decision support** — Wide feature matrix with orange entry-tier checks, violet premium checks and gray exclusions.
5. **Closing call** — Centered reassurance and Secondary button, then shared orange footer.

**Transfer:** Make upgrades understandable through capabilities, equal-sized summaries and a detailed matrix rather than an aggressive pricing centerpiece.

## Writing

Friendly and practical, with confidence grounded in specific behaviors rather than grand promises. Marketing copy is brief and encouraging; decision-support prose is frank about tradeoffs and limitations.

**Do not copy:** Do not reuse the brand name, logo artwork, product-specific feature names, platform badges without authorization, review quotations, ratings, user counts, prices, competitor claims or privacy guarantees as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; name the product clearly in opening and closing passages. Use we sparingly for factual commitments.
- **Rhythm:** Short verb-led headings and one-sentence card descriptions. Longer prose uses short paragraphs and bold-led bullets; occasional contractions and brief answers such as Yes! keep it human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A direct task or improvement followed by the product context. | 4–8 words | “Track Nutrition with [Brand]”<br>“Level Up Your Nutrition Tracking” |
| Support | A plain description of usefulness, without stacking superlatives. | 8–16 words | “A simple, clear nutrition tracker for building healthy habits.” |
| Capability heading | Verb plus a concrete task, optionally naming the mechanism. | 3–6 words | “Effortlessly Scan Food”<br>“Log Meals Faster with AI” |
| Capability description | One sentence describing what the reader can do. | 8–14 words | “Snap a pic or type a short summary of your food.” |
| Action | Direct verb, product noun, optional low-friction qualifier and northeast arrow. | 3–6 words | “Get the App ↗”<br>“Try [Brand] for Free ↗” |
| Closing reassurance | State availability and remove one practical barrier. | 1–2 sentences | “You can start without an account.” |
| Objection answer | Answer directly, then qualify honestly. | 2–4 sentences | “Direct import isn't currently supported.” |

**Words and phrasing to use:** simple; clear; your; start; free; track; log; helpful; you decide

**Avoid:** revolutionary; disruptive; unparalleled; unlock your potential; enterprise-grade synergy

**Rules:**

- Tie each benefit to an action or visible product behavior.
- Use feature language a reader can verify; separate included features from paid ones plainly.
- Keep card descriptions to one sentence and avoid repeating the heading in the first clause.
- For comparisons, acknowledge where another option may suit a different reader.
- Use adoption reassurance only when the new product can actually support it.

## Do's and Don'ts

### Do

- Keep main display at 56px/1.1, section leads at 36px/1.2 and tracking normal.
- Use 16px/1.6 medium-weight copy in cards and 18px/1.6 muted support for centered calls.
- Preserve 40px-tall actions with 20px radii and 12px 18px padding.
- Maintain the 20px feature-grid gutter and 25px card radius.
- Keep the opening phone views level, upright and consistently 330px wide.
- Use 96px narrative separation and tighter 10px heading-to-copy spacing.
- Give the final orange panel a 32px outer inset and 40px inner padding.
- Keep detailed plan matrices at 1000px and editorial comparison prose at 800px.

### Don't

- Do not add negative tracking or ultra-heavy condensed display fonts; rounded letterforms carry the personality.
- Do not make every action orange: the main closing action is gray-backed with orange text.
- Do not apply drop shadows to marketing cards; their pale fill supplies separation.
- Do not use violet as a general page background; the large violet fill belongs to a subscription summary.
- Do not introduce gradients, glass panels or dark-mode bands into the white marketing canvas.
- Do not recolor every paragraph with its card heading; body copy remains charcoal.
- Do not replace 16px filled availability circles with oversized outlined badges.
- Do not enclose the legal row inside the orange footer or expand the footer color to the viewport edges.

## Motion and responsive

### Motion

**Observed:**

- Text links declare color 0.4s cubic-bezier(0.44, 0, 0.56, 1). Navigation and footer links turn peach on hover without underlining.
- No marketing animation behavior is established.

**Transfer:**

- Keep link feedback to the measured color transition; the broad product parade should remain understandable as a static composition.

**Unknown:**

- Product-gallery movement, review-strip movement and button focus/active appearance are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px and 1200px; the desktop composition is defined at 1440px.

**Transfer:**

- At narrower widths, preserve the centered promise and intentional gallery edge clipping rather than shrinking all phone screens into unreadable thumbnails.
- As a layout adaptation, stack Feature cards and tier summaries when their measured column widths no longer fit; keep each task’s copy and interface adjacent in reading order.
- Let Footer panel groups wrap while retaining the separate legal row. Keep comparison tables readable with horizontal scrolling when necessary.

**Unknown:**

- Exact mobile type sizes, gutters, navigation behavior and table overflow implementation are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
