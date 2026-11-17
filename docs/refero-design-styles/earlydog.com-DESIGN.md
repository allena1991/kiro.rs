# EarlyDog — primary shapes, human promises

## Overview

A warm cream, ink-black and cobalt marketing style with the friendliness of a modernist playroom. Heavy rounded display sans headlines meet unusually open body leading, while flat geometric illustrations provide the energy instead of interface mockups. It suits technical products that want to feel personal and dependable, with sparse layouts, direct language and occasional natural portraits.

### Essentials

- Headlines act as two-color promises: degular-display at 116px/120px, weight 700 and 1px tracking, with a complete phrase in ink followed by a cobalt phrase.
- The opening pairs language with a geometric poster: two 584px columns separated by 32px, starting 120px down, with a square composition of circles, triangles, checkerboards and fine radial lines beside the headline.
- Cream owns most of the page: #fff9f0 under open text and unboxed illustrations; cobalt #0a65db marks headline phrases and fills the 307px closing footer. Red, yellow and pink remain concentrated in graphic artwork rather than general content panels.
- Actions have capsule silhouettes, not rounded rectangles: outlined cream buttons are 64px high with 20px 29.6px padding; the centered closing action reverses to ink with cream lettering.
- A narrow fixed brand rail makes the layout asymmetric: a 32×30px hamburger sits 40px from the left, above a vertical identity, while a short contact link with a blue triangle sits at the upper right.
- Geometric artwork recurs beyond the opening and punctuates the ending: a small cluster of rotated squares bridges cream and blue at the footer. Rebuild these devices in SVG when there is no equivalent product imagery.
- The closing promise is a typographic event, not a card: 80px/88px two-color text centered below a 1px warm-gray rule, with 96px above the headline and 56px before the dark pill.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cobalt | `#0a65db` | `--color-blue` | text, background, accent, link | Headline emphasis, contact arrow, geometric artwork and the full-width footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sunny yellow | `#ffd00d` | `--color-yellow` | accent, surface | Geometric illustration fills and colored list markers; a broad yellow band belongs only to the company-story variant. |
| Vermilion marker | `#ff491e` | `--color-red` | accent | Colored list dots and a warm red direction for geometric illustrations. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue-black ink | `#000609` | `--color-ink` | text, surface, action | All main text, illustration linework, the solid closing action and the quotation band. |
| Warm-gray rule | `#bab1a3` | `--color-rule` | border | Thin horizontal chapter separators. |
| Warm cream | `#fff9f0` | `--color-canvas` | background, surface, text | Dominant canvas, outlined button fill and reversed text on ink. |
| Footer white | `#ffffff` | `--color-white` | text | Navigation and legal links on cobalt. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detailed capability pages | Muted plum | `#b6869d` | `--color-plum` | accent | One color in the repeating list-marker cycle. |

## Typography

- **degular-display** — Headlines, chapter headings, small section titles and item headings. Broad, rounded display grotesk with compact counters and heavy, friendly lowercase forms. If unavailable, use **DM Sans**. Use 700 for display and 500 for item titles; preserve the broad measure and positive tracking. Font stack: "degular-display", "DM Sans", ui-sans-serif, system-ui, sans-serif.
- **usual** — Paragraphs, actions and footer text. Clean, readable sans with a warmer humanist texture than the display face. If unavailable, use **Nunito Sans**. Use 400 for prose and 700 for actions. Font stack: "usual", "Nunito Sans", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | degular-display | 700 | 116px | 120px | 1px | Two-line primary promise, with the second phrase in cobalt. |
| closing-display | degular-display | 700 | 80px | 1.1 | 1px | Centered final promise. |
| heading | degular-display | 700 | 52px | 64px | 1px | Main feature headings and chapter introductions. |
| body-lead | usual | 400 | 22px | 40px | normal | Opening explanation, editorial introductions and large capability lists. |
| body | usual | 400 | 18px | 32px | normal | Feature explanations and reading-column paragraphs. |
| action | usual | 700 | 18px | 1 | normal | Outlined pills, header contact and footer navigation. |
| closing-action | usual | 700 | 18px | 32px | normal | Text within the dark closing pill. |
| footer-meta | usual | 400 | 16px | 1 | normal | Compact legal and copyright row within the footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial, company-story and detailed capability pages | heading-small | degular-display | 700 | 32px | 1.25 | 1px | FAQ headings, biographies and centered quotation text. |
| editorial and detailed capability pages | item-heading | degular-display | 500 | 28px | 40px | normal | Short headings within stacked principles or process explanations. |

**Notes:**

- Display headings retain positive 1px tracking across 116px, 80px, 52px and 32px sizes; do not replace this with fashionably tight negative tracking.
- Color changes occur within one heading and retain the same recipe. Body copy stays ink rather than stepping down to gray.
- The prose is visually light and spacious against heavy headings: 22px/40px for introductions and 18px/32px for explanations.

## Layout

**Density:** Airy, with large separations between illustrated chapters and unusually generous paragraph leading.

### Spacing

**Spacing system:**

- **horizontal-step** 16px, horizontal — Container inset, column spacing and media padding; column gutters are two steps.

| Value | Use |
| --- | --- |
| 8px | Small item heading to explanation gap. |
| 16px | Editorial heading to paragraph gap and inner container inset. |
| 24px | Feature heading to body gap and lead-paragraph separation. |
| 32px | Column gutter, opening support gap and stacked list spacing. |
| 48px | Body to feature action gap. |
| 56px | Closing headline to dark action gap. |
| 96px | Closing rule to headline and editorial chapter entry padding. |
| 120px | Opening top inset and space before the footer. |
| 128px | Major feature chapter separation. |

### Containers and grids

- **content-shell**: max width 1680px · side padding 104px. Outer desktop content margins; a further 16px inner inset on each side yields a 1200px content width at 1440px.
- **chapter-grid**: 12 columns · gap 32px. Main alignment system; half-width blocks occupy six columns, and some artwork occupies five columns.
- **opening-pair**: 2 columns · gap 32px. Two equal 584px columns within the desktop content area, text left and artwork right.
- **reading-column** (only for detailed capability pages): max width 687px. Detailed capability copy offset two columns into the main grid rather than centered on the whole viewport.
- **editorial-column** (only for company-story pages): max width 789px. Longer company prose in an eight-column measure offset from the brand rail.

## Corner radius

| Element | Radius |
| --- | --- |
| action-capsules | 9999px (pill) |
| bands-and-images | 0px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default background and continuous backing for illustrated chapters.

**CSS:** `background-color: #fff9f0; color: #000609`

**Observed:** A flat warm field without texture, elevation or panel borders.

**Transfer:** Use empty space to separate ideas instead of introducing cards.

#### Cobalt footer · level 0

**Use:** Shared terminal band.

**CSS:** `background-color: #0a65db; color: #ffffff; padding-top: 40px`

**Observed:** Full viewport width, 307px tall on desktop; no rounded top corners.

**Transfer:** Keep the terminal field saturated even when the preceding content is editorial.

#### Yellow story band · level 0

**Only for:** company-story pages

**Use:** An emphatic statement paired with geometric art.

**CSS:** `background-color: #ffd00d; color: #000609; padding: 80px 0; border-radius: 0px`

**Observed:** Starts at the content's left edge and bleeds to the right viewport edge; followed directly by the ink quotation band.

**Transfer:** Use for a substantial human or product philosophy statement, not every feature.

#### Ink quotation band · level 0

**Only for:** company-story pages

**Use:** Personal testimony below the yellow band.

**CSS:** `background-color: #000609; color: #fff9f0; padding: 128px 0 96px; border-radius: 0px`

**Observed:** A broad rectangular field with a centered quote in an offset eight-column area; quotation marks are yellow.

**Transfer:** Use a real attributed statement and preserve the hard seam between bands.

## Components

### Brand rail

**Use:** Persistent desktop identity and menu access.

**CSS:** `position: fixed; margin-left: 40px; padding-top: 44px; z-index: 50`

**Observed:** Three horizontal ink bars form a 32×30px menu icon. A narrow vertical identity below it occupies a 32×162px rail; the main content begins to its right.

**Transfer:** Use the new product's own compact symbol and vertical name, preserving the slim rail.

### Header contact

**Use:** Opening screen conversion without a hero button stack.

**CSS:** `color: #000609; text-align: right; margin-top: 4px`

**Text style:** `action` — usual 700 · 18px/1

**Observed:** Upper-right text followed by a 12×14px cobalt right-pointing triangle; visually aligned with the menu rather than the headline.

**States:** Declared: hover color #0a65db and no text decoration; focus-visible unknown.

**Transfer:** Keep one conversational action in this location.

### Outline pill

**Use:** Local navigation and next-step actions in illustrated chapters.

**CSS:** `background-color: #fff9f0; color: #000609; border: 3px solid #000609; border-radius: 9999px; padding: 20px 29.6px; height: 64px; box-sizing: border-box`

**Text style:** `action` — usual 700 · 18px/1

**Observed:** A visibly firm dark outline wraps a short bold label; width follows the copy. Usually left-aligned under paragraphs.

**States:** Declared: hover color #000609, border-color #000609, background-color rgba(240,234,224,1), text-decoration none; focus-visible unknown.

### Dark pill

**Use:** Primary conversion beneath the centered closing promise.

**CSS:** `background-color: #000609; color: #fff9f0; border-radius: 9999px; padding: 14.4px 29.6px; height: 67px; box-sizing: border-box`

**Text style:** `closing-action` — usual 700 · 18px/32px

**Observed:** A compact filled capsule centered below the statement rather than stretched across the container.

**States:** Declared: hover color #000609, border-color #0a65db, background-color rgba(240,234,224,1), text-decoration none; focus-visible unknown.

### Footer navigation

**Use:** Shared end-of-page wayfinding.

**CSS:** `color: #ffffff; border-bottom: 1px solid transparent; text-decoration: none`

**Text style:** `action` — usual 700 · 18px/1

**Observed:** Eight short links are distributed across one horizontal row inside the Cobalt footer. A smaller legal and copyright row sits near the lower right, separated by 96px.

**States:** Declared: hover color #ffffff, border-color rgba(255,255,255,1), text-decoration none; focus-visible unknown.

**Transfer:** Use equivalent destinations, keeping the single-row spread and subordinate metadata.

### Chapter rule

**Use:** Separate a closing statement or a detailed capability chapter.

**CSS:** `background-color: #bab1a3; height: 1px; border: 0px`

**Observed:** Spans either the 1200px content width or the 687px reading column; never becomes a boxed border.

### Capability dot row

**Only for:** detailed capability pages

**Use:** Scannable inventory without tiles.

**CSS:** `display: flex; margin-top: 32px; column-gap: 20px`

**Text style:** `body-lead` — usual 400 · 22px/40px

**Observed:** A 12px filled circular marker is vertically centered against the first 40px line. Colors cycle red, blue, muted plum and yellow. Copy wraps naturally; occasional small geometric art sits outside the reading measure.

**Transfer:** Use capability phrases with enough detail to remain useful; preserve the colored dot rhythm instead of adding pictogram badges.

### Stacked explanation

**Only for:** editorial and detailed capability pages

**Use:** Principles, process steps and service explanations.

**CSS:** `margin-top: 32px`

**Text style:** `item-heading` — degular-display 500 · 28px/40px

**Observed:** A medium-weight item heading precedes 18px/32px prose by 8px or 16px. The stack is unboxed and aligned to one reading column.

**Transfer:** Keep each heading a short noun or parallel verb phrase and explain it in ordinary prose.

### Attributed quotation

**Only for:** company-story pages

**Use:** First-person proof of purpose.

**CSS:** `color: #fff9f0; text-align: center`

**Text style:** `heading-small` — degular-display 700 · 32px/1.25 · tracking 1px

**Observed:** A compact multiline quotation with yellow curly quotation marks sits in the Ink quotation band. Bold attribution and a regular role line follow beneath.

**Transfer:** Keep the attribution human and visually subordinate; do not turn the quotation into a rounded testimonial card.

## Imagery and graphics

### Geometric poster system

**Use:** The main opening image and recurring feature illustrations.

**Observed:** Crisp flat geometry on the same cream as the page: primary red, cobalt and yellow shapes with pale pink accents, black checkerboards, hairline radial bursts, circles, semicircles and triangular subdivisions. The opening square is 584×584px; later arrangements are looser and smaller. There is no 3D lighting, grain, perspective or enclosing card.

**Transfer:** Create an original abstract assembly suggesting the product's organizing idea. Even without product media, use this geometric system at hero scale and repeat its vocabulary later; a simple circle, divided square, triangle and radial burst composition is the minimum version.

**Build:** Use an SVG viewBox of 600 600 on a cream backing. Divide the composition into a loose 3×3 modular field; combine filled circles and semicircles, diagonal half-squares, a small black-and-cream checkerboard, and 16–20 ink spokes around one center with approximately 1px strokes at display size. Use cobalt and yellow plus warm red and pale pink fills, with hard edges and no shadows. Keep some modules empty so the background participates. Rearrange shapes for secondary chapters instead of repeating the same complete poster.

### Footer diamond punctuation

**Use:** Small graphic bridging the final cream area and cobalt footer.

**Observed:** A loose cross of blue, pink and red diamonds near the right edge straddles the color seam, much smaller than the hero art.

**Transfer:** Retain a small geometric bridge into the footer using the same shape vocabulary, independent of the narrative order above it.

**Build:** Place a roughly 170px square SVG near the right side of the footer seam. Arrange five small squares rotated 45 degrees around a shared cross-shaped rhythm, with cobalt at top and bottom and lighter pink plus warm red across the middle. Let the bottom blue diamond be interrupted by a cream or white inner diamond so it remains legible on cobalt.

### Natural leadership portrait

**Only for:** company-story and team pages

**Use:** Humanize biographies near the end of long editorial pages.

**Observed:** A rectangular 481×361px photograph sits left of biography text. Natural indoor light, recognizable surroundings, candid clothing and a friendly expression; no cutout treatment, tinted overlay, rounded frame or studio color backdrop.

**Transfer:** Use authentic environmental portraits with the same relaxed framing, not glossy headshot circles.

### Icons

**Observed:** The interface vocabulary is very small: an ink hamburger made from filled bars, a solid blue triangular arrow beside the header action, and 12px colored dots for capability lists.

**Transfer:** Prefer primitive geometric SVG shapes. Avoid introducing a full outlined feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Two-color geometric opening

**Observed:** On Cream canvas, the Brand rail sits at the far left and Header contact occupies the upper right. The main composition starts 120px down, inset 120px from the viewport edge at desktop. Text and a square geometric poster share two equal 584px columns with a 32px gutter. The left headline is 116px/120px, weight 700, 1px tracking: ink first line and cobalt second line. A 22px/40px paragraph follows after 32px and fits in the same left measure. The right poster reaches the full 584px column height. Within the first 900px the headline, support paragraph, header action and entire poster are visible; the first feature chapter starts below the fold. There is no large action button directly beneath the hero paragraph.

**Transfer:** Pair a short possessive or reader-oriented promise with an original modular geometric composition of comparable visual mass. The poster must remain a major object even without literal product imagery. Editorial openings can shorten the image to 584×438px and put a 52px blue reassurance line under a single ink display heading; detailed offerings use a two-line display and a lead paragraph.

**Avoid:** Do not substitute a centered SaaS headline above a dashboard, stack two hero CTA buttons, or shrink the geometric poster into a decorative corner icon.

**Text style:** `display` — degular-display 700 · 116px/120px · tracking 1px

### Alternating illustrated chapter

**Observed:** Chapter grid alternates image-left/text-right and text-left/image-right arrangements. Feature illustrations occupy five or six columns and are vertically centered beside a 52px/64px heading, 18px/32px paragraph and Outline pill. Text follows the heading after 24px; actions follow prose after 32px or 48px. Major chapters are separated by 128px.

**Transfer:** Use the alternation to explain a few substantial benefits. Keep the art on Cream canvas and vary its internal geometry, not the surrounding panel treatment.

**Text style:** `heading` — degular-display 700 · 52px/64px · tracking 1px

### Offset reading chapter

**Observed:** An inset reading column carries a 52px heading and open prose. Company storytelling uses a 789px measure with 22px/40px introductions; detailed offerings use a 687px measure with Stacked explanation items and 18px/32px prose. A small radial or starburst illustration can sit in the left margin.

**Transfer:** Move from the broad opening into a calmer inset reading measure for explanations that need attention rather than imagery.

### Centered closing promise

**Observed:** Chapter rule spans the content area; the 80px/88px closing line sits 96px below it, with an ink setup and cobalt payoff. Dark pill follows after 56px. Cream space below leads into Cobalt footer, with Footer diamond punctuation crossing the seam at the right.

**Transfer:** Restate the relationship or outcome in one short sentence; retain the scale, two-color emphasis and small geometric bridge instead of adding another explanatory paragraph.

**Text style:** `closing-display` — degular-display 700 · 80px/1.1 · tracking 1px

### Color-seam testimony

**Only for:** company-story pages

**Observed:** Yellow story band starts at the main content's left edge and bleeds right. Geometric artwork at left balances a 52px heading and 18px body at right. The Ink quotation band attaches below without a gap; Attributed quotation occupies an offset eight-column region.

**Transfer:** Use this scoped treatment for a meaningful philosophy statement backed by a real human voice, preserving the asymmetric bleed and hard color seam.

**Text style:** `heading` — degular-display 700 · 52px/64px · tracking 1px

### Capability inventory and next step

**Only for:** detailed capability pages

**Observed:** A Chapter rule precedes a 52px heading with its final word in blue. Capability dot row items use 22px/40px text and 32px vertical separation. The list gives way to two short 32px/40px explanatory headings with 18px prose, then an Outline pill aligned to the reading column, followed by 120px of cream before the footer.

**Transfer:** Turn a detailed offering into a readable inventory, then answer the practical collaboration and starting questions. Keep the final action local and left-aligned.

### Biographical ending

**Only for:** company-story and team pages

**Observed:** Two portrait-and-prose rows use rectangular photographs at left and 32px headings with 18px/32px prose at right, with 128px top spacing. After the last biography, the cream area ends in the shared Cobalt footer without a centered conversion statement.

**Transfer:** Let an editorial or team page finish on people rather than forcing the marketing closing promise onto every page type.

## Page flow

**Storyline:** Reader promise → tangible explanation → deeper capability or human proof → a fitting next step → saturated shared footer.

### Broad product or service landing page

1. **Promise** — Two-color display headline, large modular poster and one lead paragraph.
2. **Benefit explanation** — Alternating illustrated chapters with short headings, paragraphs and local capsule links.
3. **Closing call** — Wide rule, centered two-color promise, dark capsule and geometric punctuation.
4. **Wayfinding** — Cobalt footer with distributed links and small legal row.

**Transfer:** Choose the few benefits that make the new offer understandable; use geometry to create continuity from opening to ending.

### Long-form company and human credibility page

1. **Promise** — Large ink heading, smaller blue reassurance and a field of circles and radial forms.
2. **Context and principles** — Inset lead prose followed by short stacked headings and explanations.
3. **Human proof** — Yellow statement band and attached ink quotation band.
4. **Culture and people** — Illustrated editorial chapter followed by two environmental portrait biographies.
5. **Wayfinding** — Direct transition from people to the shared blue footer.

**Transfer:** Use this variant for values, team or origin storytelling, with genuine principles and human attribution rather than a generic feature catalogue.

### Detailed offering and practical evaluation page

1. **Promise** — Two-line display, supporting paragraph and airy geometric art.
2. **Method explanation** — Inset column of parallel verb headings and short explanations.
3. **Capability detail** — Hairline separator, blue-accented heading and colored-dot inventory with small geometric motifs.
4. **Objection handling** — Plain headings answer how the relationship works and what happens next.
5. **Closing call** — Left-aligned outlined contact capsule, cream breathing room and shared blue footer.

**Transfer:** Use greater textual depth while keeping the same warm canvas, geometric language and sparse action hierarchy.

## Writing

Warm, technically literate and matter-of-fact. Confidence comes from describing responsibilities, working relationships and concrete outcomes rather than using superlatives.

**Do not copy:** Do not reuse EarlyDog's name, logo, exact geometric artwork, attributed quotations, personnel biographies, infrastructure claims, tenure or service guarantees. Source examples illustrate voice only; replace them with true statements about the new product.

- **Addressing the reader:** Address the reader as you and your; the provider speaks as we, our and us. Make the product feel like an accountable partner rather than an impersonal platform.
- **Rhythm:** Headlines are usually short conversational phrases. Support copy uses complete, moderately long sentences; process headings often use parallel groups of three verbs. Contractions soften the technical detail.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the reader's relationship to the offer, splitting setup and payoff into two color phrases. | 4–7 words | “Your Cloud Ops Team”<br>“What we do for you” |
| Reassurance | A direct relational promise without marketing jargon. | 4–6 words | “you’ll never outgrow us” |
| Feature heading | A concrete capability or a concise benefit framed around the reader. | 2–5 words | “Your own Ops Team”<br>“We’re your success partner” |
| Process heading | Three parallel active verbs explain the work. | 3–6 words | “Assess, architect, and implement”<br>“Collaborate, partner, and empower” |
| Supporting explanation | State what the team does, who it works with and the reader's benefit. | One to three complete sentences | “We learn your application, take responsibility for your operations, work with your developers, and help your business succeed.” |
| Action | Short, ordinary language about a conversation or learning the next thing. | 2–4 words | “Talk to us”<br>“What we do”<br>“Work with us” |

**Words and phrasing to use:** your; we; help; learn; partner; understand; responsibility; trust; grow; tailored; work with

**Avoid:** revolutionary; disruptive; unleash; 10x; magic; best-in-class; frictionless everything

**Rules:**

- Explain the actual work behind each outcome.
- Use technical terms where they clarify responsibility, then connect them to a human or business benefit.
- Keep action labels conversational, not transactional or urgent.
- Write headings that remain understandable when separated from the paragraph beneath them.

## Do's and Don'ts

### Do

- Use the 116px display recipe for the primary promise and preserve its ink-to-blue phrase change.
- Hold the 32px desktop gutter between equal opening columns.
- Keep 18px body copy at 32px leading and opening prose at 22px/40px.
- Let major illustrated chapters breathe with 128px separation.
- Use 9999px capsules for actions and square edges for images and broad bands.
- Repeat the geometric vocabulary at hero scale, chapter scale and the footer seam.
- End the main landing treatment with an 80px centered promise and one compact dark action.
- Keep the footer full-width cobalt with bold white links.

### Don't

- Do not turn the cream content area into a grid of elevated white cards; there are no card shadows.
- Do not use blue for whole paragraphs; reserve text color emphasis for short headline phrases and links.
- Do not apply negative tracking to the display face; the heading recipes use 1px.
- Do not fill every chapter with yellow; the broad yellow and ink pairing belongs to company storytelling.
- Do not put photography into pill or circular frames; biography media uses square corners.
- Do not replace the colored list dots with large bordered icon containers.
- Do not make footer metadata as prominent as its 18px bold navigation.
- Do not add gradients, glass, grain or modeled lighting to the flat geometric art.

## Motion and responsive

### Motion

**Observed:**

- No action transitions or element animations are established. Declared hover changes are immediate color, border and background changes on links and capsules.

**Transfer:**

- Preserve the flat poster character and let interaction feedback rely on the established color changes.

**Unknown:**

- Menu-open appearance, focus-visible treatment, animation triggers, durations and easing assignments are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 300px, 768px, 992px, 1200px and 1920px.
- The layout uses one-column bases with wider multi-column variants; the vertical identity is hidden below its desktop variant.

**Transfer:**

- On narrower screens, stack the promise and geometric poster while preserving the ink/blue phrase split; retain a substantial poster rather than reducing it to an icon.
- Collapse alternating feature rows to a single reading order and retain cream space between chapters. Keep a horizontal identity when the fixed rail no longer fits.

**Unknown:**

- Exact mobile type sizes, margins, artwork ordering and footer wrapping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
