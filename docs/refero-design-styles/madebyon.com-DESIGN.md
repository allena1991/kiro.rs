# Made by ON — serif meets circuitry

## Overview

An editorial, technically minded style that pairs delicate serif statements with utilitarian monospace labels. Near-black and warm paper canvases carry electric green controls, while richly colored website imagery floats in the surrounding space. It suits ambitious product launches and consultative services: sparse at the level of each composition, but substantial in its long-form storytelling.

### Essentials

- An editorial voice inside a technical shell: 64px serif headlines at weight 300, 1.05 line height and -0.01em tracking meet 14px monospace labels and controls.
- The opening is an orbit, not a dashboard: a centered three-line promise occupies a 906px-wide text zone within a 900px-tall dark stage, surrounded by differently sized landscape media windows of roughly 203px, 320px and 437px width.
- Controls resemble compact instrument keys: 38px height, 4px corners, 14px monospace type and 7px 16px 8px padding; green-filled conversion controls contrast with green-outlined discovery controls.
- Color belongs to proof rather than page furniture: near-black and warm paper dominate the canvas; green appears in small labels, hairlines and buttons, while full saturation stays inside media windows rather than full-page accent fills.
- Rules act as the architecture: 1px separators and 16px left insets divide newsletter, footer and proof content; prose uses two equal columns with a 30px gutter rather than boxed feature tiles.
- Identity ends as an object: include an edge-to-edge dot-matrix word sculpture in a 282px closing zone, paired with the smaller dotted identity in the navigation. Rebuild the new product name as circular-dot lettering when bespoke artwork is unavailable.
- Proof stays visually alive: include a floating media constellation and an open horizontal media rail with 30px gaps and 4px media corners. If finished product imagery is unavailable, compose real workflow or outcome panels rather than substituting decorative empty rectangles.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal green | `#1fc742` | `--color-green` | action, accent, text, border | Primary control fill, dark-theme labels and focus rings. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Outline green | `#1ec140` | `--color-outline-green` | text, border | Secondary action outlines and labels on the dark canvas. |
| Paper green | `#19a336` | `--color-light-green` | text, link | Green labels on light surfaces; also the primary button hover fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control black | `#000000` | `--color-button-ink` | text | Primary green control text and solid identity dots on paper. |
| Near black | `#0a0a0a` | `--color-canvas` | background, text | Default marketing canvas and dark text on warm paper. |
| Lifted black | `#121212` | `--color-subtle-band` | surface, background | Low-contrast media backing and service transition bands. |
| Warm charcoal | `#1f1f1e` | `--color-nav-surface` | surface, border | Default menu and search surfaces. |
| Dark rule | `#292929` | `--color-dark-rule` | border | Hairlines on dark surfaces. |
| Silver gray | `#a3a3a3` | `--color-muted` | text, border | Secondary card descriptions and light-theme separators. |
| Soft control white | `#e1e0dc` | `--color-nav-ink` | text | Default menu text and navigation icons. |
| Warm paper | `#f5f4f0` | `--color-paper` | text, background | Default light text and the light destination of the marketing page's tonal change; also the editorial page canvas. |
| Bright white | `#ffffff` | `--color-white` | surface, text | Testimonial cards on paper and primary action hover text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| case-study media galleries | Charcoal mat | `#1f1f1f` | `--color-media-mat` | surface | Deep framing around large product presentations. |
| service landing pages | Service lead gray | `#666666` | `--color-lead-muted` | text | Subdued supporting lead in a service opening. |
| light editorial pages | Paper control gray | `#cccbc7` | `--color-light-nav` | surface, border | Menu and search backing in the light editorial theme. |

## Typography

- **Geist Arrow** — Serif statements, section headings, article titles and large numbers. Fine, high-contrast editorial serif with light strokes and compact spacing. If unavailable, use **Newsreader**. Use weight 300 and preserve the thin serif construction. Font stack: "Geist Arrow", Newsreader, Georgia, serif.
- **Geist** — Supporting paragraphs, descriptions and ordinary navigation links. Neutral contemporary grotesk with a light variable weight. OpenType features: "ss03", "ss04", "ss08". Font stack: "Geist", Arial, sans-serif.
- **Geist Mono** — Utility controls, category markings and contact details. Small, even-width technical lettering; sentence case rather than shouted capitals. OpenType features: "ss03", "ss04", "ss08". Font stack: "Geist Mono", ui-monospace, SFMono-Regular, Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Geist Arrow | 300 | 64px | 1.05 | -0.01em, features "clig", "liga" | fixed | Opening promise and centered closing question. |
| statement | Geist Arrow | 300 | 64px | 1.05 | -0.0156em, features "clig", "liga" | fixed | Large testimonial and split contact heading. |
| centered-heading | Geist Arrow | 300 | 56px | 1.05 | -0.01em, features "clig", "liga" | fixed | Centered positioning statement above a logo rail. |
| section-heading | Geist Arrow | 300 | 40px | 1.05 | -0.01em, features "clig", "liga" | fixed | Section headings and newsletter title. |
| footer-statement | Geist Arrow | 300 | 40px | 1.05 | -0.0208em, features "ss03", "ss04", "ss08" | fixed | Identity descriptor above contact details. |
| card-heading | Geist Arrow | 300 | 32px | 1.15 | -0.0313em, features "clig", "liga" | fixed | Editorial card titles. |
| body-lead | Geist | 340 | 20px | 1.4 | normal | fixed | Narrative copy and main supporting sentences. |
| body | Geist | 340 | 16px | 1.4 | normal | size calc(1rem + clamp(0rem,(min(100vw, 2400px) - 1440px) * .001667,.1rem)) | Card descriptions, newsletter support and footer links. |
| utility | Geist Mono | 400 | 14px | 1.5 | normal | fixed | Buttons, footer labels and contact details. |
| eyebrow | Geist Mono | 400 | 14px | 1.35 | normal | fixed | Centered opening marker and compact metadata. |
| caption | Geist | 340 | 14px | 1.5 | normal | fixed | Metric captions and small secondary links. |
| card-tag | Geist Mono | 500 | 12px | 1.5 | normal | fixed | Green topic markers above article titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| quantified proof sections | proof-number | Geist Arrow | 300 | 120px | 0.45 | -0.06em, features "clig", "liga" | fixed | An isolated outcome figure with dedicated breathing room. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the serif light at every scale; the contrast comes from size and spacing, not bold headings. Grotesk copy uses weight 340 rather than matching the mono's 400.
- Use sentence case throughout. The tighter card and footer tracking are role-specific; do not apply the 120px figure's -0.06em to headlines.
- The 120px proof figure uses an unusually short line box. Give its enclosing figure enough space for the visible glyphs rather than clipping to that box.

## Layout

**Density:** Airy compositions with compact controls: broad pauses surround media and statements, while metadata and footer details remain closely grouped.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Label-to-heading and footer identity gaps. |
| 12px | Paragraph separation in long-form chapters. |
| 16px | Button side padding, ruled-column insets and headline-to-support gap. |
| 30px | Desktop page gutters and media-rail gaps. |
| 32px | Section-header separation, footer band padding and positioning-copy gap. |
| 64px | Editorial chapter top and bottom padding. |
| 80px | Default marketing section top and bottom padding. |
| 104px | Vertical internal mat padding around a desktop presentation. |
| 128px | Deep gallery and result breathing room. |
| 160px | Large testimonial inner top spacing. |
| 240px | Opening pause before the split inquiry section. |

### Containers and grids

- **wide stage**: max width 1860px · side padding 30px. Media-led marketing modules extend nearly edge to edge; the desktop visible content width is 1380px.
- **editorial container**: max width 1202px · side padding 30px. Centered narrative and inquiry modules; inner desktop width is 1142px.
- **editorial grid**: 12 columns · gap 30px. Split heading and narrative into two equal six-column fields; retain generous empty space under the short heading.
- **hero text**: max width 906px. Centered opening headline zone; visible serif lines occupy less than its full width.
- **copy measure**: max width 686px. Maximum paragraph measure; ordinary split-column text fits inside a 556px column.
- **media rail**: gap 30px. Horizontal overflow rail with roughly 547px-wide editorial cards and a partial next card visible.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls and media | 4px |
| testimonial attribution | portrait | 50% |

## Surfaces and depth

### Surfaces

#### Dark stage · level 0

**Use:** Default marketing page field.

**CSS:** `background: #0a0a0a; color: #f5f4f0`

**Observed:** A flat near-black field with no grain, vignette or card shadows.

**Transfer:** Let the media supply the texture and color.

#### Paper destination · level 0

**Use:** Closing inquiry and footer tone.

**CSS:** `background: #f5f4f0; color: #0a0a0a`

**Observed:** The dark marketing journey changes into warm paper near the inquiry; editorial stories instead begin in paper and close in dark.

**Transfer:** Use the opposite monochrome tone to make the ending feel like a new chapter, with green unchanged as the action signal.

#### Ruled field · level 1

**Use:** Newsletter, identity and information groups.

**CSS:** `border-left: 1px solid #292929; padding-left: 16px`

**Observed:** Vertical rules partition content without enclosing boxes. On paper the rule changes to silver gray.

**Transfer:** Use a left rule to anchor a group and a top rule to separate major footer bands.

#### Media backing · level 1

**Use:** Backing beneath editorial card media and quiet transition bands.

**CSS:** `background: #121212; border-radius: 4px`

**Observed:** A nearly invisible lift from the dark canvas; content is not wrapped in a raised card.

**Transfer:** Preserve the tonal distinction without introducing shadow.

#### Presentation mat · level 1

**Only for:** case-study media galleries

**Use:** Large desktop and mobile product demonstrations.

**CSS:** `background: #1f1f1f; border-radius: 4px; padding: 104px 176px`

**Observed:** A wide charcoal rectangle surrounds a smaller, centered desktop view; a three-mobile-view variant uses 16px gaps.

**Transfer:** Frame the actual product or result as a designed exhibit rather than placing it directly beside dense prose.

#### White quote panel · level 1

**Only for:** light case-study narratives

**Use:** Customer testimony interludes.

**CSS:** `background: #ffffff; border-radius: 4px; box-shadow: none`

**Observed:** A white panel sits within the narrower editorial container on warm paper.

**Transfer:** Keep the distinction material and understated, without a colored border.

## Components

### Navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 30; height: 70px; max-width: 1440px`

**Observed:** A three-part bar places Menu and a square search key left, a small dotted identity in the true center and Primary button right. The inner bar uses 16px padding and a 1fr auto 1fr grid.

**Transfer:** Use the new product's short dotted wordmark, preserving the balanced center rather than distributing a long row of links.

### Primary button

**Use:** Main conversion and subscription action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #1fc742; color: #000000; border: 1px solid #1fc742; border-radius: 4px; height: 38px; padding: 7px 16px 8px`

**Text style:** `utility` — Geist Mono 400 · 14px/1.5

**Observed:** A compact text-only rectangle; its width follows the label. It anchors the far right of navigation and the main closing action.

**States:** Declared: hover background and border #19a336, text #ffffff; focus-visible outline #1fc742 solid 2px with 3px offset; active scale(0.97), background and border #14802a, text #000000.

### Secondary button

**Use:** Discovery actions below proof and beside section headings.

**CSS:** `display: flex; align-items: center; justify-content: center; background: transparent; color: #1ec140; border: 1px solid #1ec140; border-radius: 4px; height: 38px; padding: 7px 16px 8px`

**Text style:** `utility` — Geist Mono 400 · 14px/1.5

**Observed:** A thin right arrow follows the text. The smaller quote action is 36px tall with 12px text.

**States:** Declared: hover background and border #1fc742, text #000000; focus-visible outline #1fc742 solid 2px with 3px offset; active scale(0.97), background and border #14802a, text #000000.

### Menu key

**Use:** Compact navigation controls.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; background: #1f1f1e; color: #e1e0dc; border: 1px solid #1f1f1e; border-radius: 4px; height: 38px; padding: 0px 15px`

**Text style:** `utility` — Geist Mono 400 · 14px/1.5

**Observed:** Three fine horizontal strokes precede the label. A separate 38px square search key sits 4px away. Light editorial controls use a paper-gray backing.

**States:** Declared: hover mixes the page's monochrome canvas tones; focus-visible outline #1fc742 solid 2px with 3px offset; active background and border #19a336, text #000000, scale(0.97).

### Editorial media card

**Use:** Insights and linked proof within an open horizontal rail.

**CSS:** `display: flex; flex-direction: column; gap: 16px; max-width: 800px; border-radius: 4px`

**Text style:** `card-heading` — Geist Arrow 300 · 32px/1.15 · tracking -0.0313em

**Observed:** Landscape media sits above a green topic marker, serif title and muted sans description. The text sits directly on the page, not inside a padded box; the information stack uses 8px gaps, with the final excerpt tucked 4px closer.

**Transfer:** Use one real workflow, demonstration or editorial image per card and concise outcome-led titles.

### Newsletter band

**Use:** Recurring low-friction subscription at the end of the journey.

**CSS:** `border-top: 1px solid #292929; padding: 32px 0px`

**Text style:** `section-heading` — Geist Arrow 300 · 40px/1.05 · tracking -0.01em

**Observed:** Two equal zones each begin with a vertical rule: title and short explanatory paragraph on the left, bottom-aligned email field and Primary button on the right. On the light destination all separators become silver gray.

### Email field

**Use:** Inline newsletter entry.

**CSS:** `background: #0a0a0a; border: 1px solid transparent; border-bottom: 1px solid #292929; padding: 8px 0px; height: 39px`

**Observed:** A long underline rather than a box. A 16px gap separates the field from the subscription key; the light version uses paper and a silver-gray underline.

### Footer identity column

**Use:** Identity and contact information within the ending.

**CSS:** `display: flex; flex-direction: column; gap: 8px; border-left: 1px solid #292929; padding-left: 16px`

**Text style:** `footer-statement` — Geist Arrow 300 · 40px/1.05 · tracking -0.0208em

**Observed:** A green mono identity marker precedes a serif descriptor. Contact rows sit much lower, with short location codes beside mono address and email lines. Two narrower link columns occupy the right half.

**Transfer:** Retain the descriptor/contact contrast; adapt the number of locations to real content.

### Outcome figure

**Only for:** quantified proof sections

**Use:** One result presented as a typographic object.

**CSS:** `display: flex; flex-direction: column; gap: 40px; border-left: 1px solid #a3a3a3; padding-left: 16px`

**Text style:** `proof-number` — Geist Arrow 300 · 120px/0.45 · tracking -0.06em

**Observed:** A small sans caption precedes an enormous light serif number. A case-study figure is aligned in the right half with the left half intentionally open; a service opening can place a dark-theme figure between image cards.

**Transfer:** Use an auditable metric with a short baseline or context line, keeping the number out of a colored badge.

### Testimonial panel

**Only for:** light case-study narratives

**Use:** Customer voice as a pause between media chapters.

**CSS:** `background: #ffffff; border-radius: 4px; max-width: 1142px; overflow: hidden`

**Text style:** `section-heading` — Geist Arrow 300 · 40px/1.05 · tracking -0.01em

**Observed:** The quote occupies an inset 751px-wide text area with 160px of top breathing room. Beneath it, a small round portrait sits beside name and role, with the customer's mark below; the remaining card space stays open.

**Transfer:** Let a specific quoted outcome carry the panel rather than adding stars or rating decoration.

## Imagery and graphics

### Orbiting proof windows

**Use:** Signature opening media constellation.

**Observed:** Six differently scaled landscape views surround the headline: smaller bright windows near the edges, a dark panel above the center, and a larger photographic window below-left. Images retain the identity and colors of the work, with subtle 4px corners; they do not become uniform device mockups.

**Transfer:** Use actual product workflows, outcomes or campaign panels. With no finished media, compose legible, restrained panels using the new product's own content and relevant photography.

**Build:** Place a relative 900px-tall stage on near-black. Arrange six landscape image elements at about 203px, 320px and 437px widths around a protected central headline area; anchor small windows to upper left and upper right, one medium window above the heading, one medium at right and the largest below-left. Use object-fit: cover and 4px corners. At narrower widths move these into an ordered horizontal rail instead of overlapping the text.

### Dot-matrix identity sculpture

**Use:** Signature small navigation identity and monumental closing word sculpture.

**Observed:** Round dots form widely spaced capital letters, with the footer lettering nearly spanning the full viewport. The dots are solid black on paper or paper-white on dark; a localized cluster softens into blurred, displaced dots.

**Transfer:** Render the new product name or a short proprietary phrase as dot lettering. If an interactive canvas is unavailable, a static SVG with a small softened dot cluster is the minimum acceptable treatment.

**Build:** Use an SVG viewBox spanning 1440 by 282. Plot circular dots on a regular letter grid, using roughly 22px circles and 40px center spacing for the footer version; leave generous word gaps and scale the complete word to the width. Use near-black or warm paper according to the field. Duplicate a few circles in one cluster with 2px–5px Gaussian blur and slight displacement. Use a smaller, denser grid for the navigation mark.

### Monochrome logo rail

**Use:** Quiet recognition proof between positioning and conversion.

**Observed:** A single line of customer or partner marks is reduced to one foreground tone, with varied natural wordmark widths and broad spacing.

**Transfer:** Use only relevant authorized identities, keeping the same optical height rather than forcing equal widths.

### Product exhibit gallery

**Only for:** case-study narratives

**Use:** Large proof media alternating with editorial text chapters.

**Observed:** The first desktop demonstration is centered inside Presentation mat; later media becomes almost full-width, or two tall adjacent windows. A three-mobile-view exhibit uses equally tall narrow panels. Each project keeps its own world: sports photography with cream and violet graphics, or glass-like script against blue cloud skies and a lilac dusk scene.

**Transfer:** Preserve the distinction between the outer marketing system and the showcased product. Use a coherent product-specific visual world across desktop, mobile and motion views; do not adopt that world's UI fonts or palette as the page system.

### Human documentary rail

**Only for:** culture and company stories

**Use:** Early human context after a centered editorial opening.

**Observed:** Natural-color candid photographs show people collaborating, presenting and visiting exhibitions. A large central landscape image is flanked by partially visible images; color shifts naturally from cool projection light to warm interior light.

**Transfer:** Photograph real people engaged in the work. Use environmental framing rather than isolated studio headshots or stock meeting smiles.

### Icons

**Observed:** Utility icons are fine 1px outline SVGs with round caps. Navigation glyphs are 21px square; right arrows inside discovery actions are 18px square. Icons inherit subdued text or green rather than sitting in colorful circles.

**Transfer:** Choose simple single-stroke search, menu and directional shapes; keep icons out of headings and body paragraphs.

## Section recipes

How recurring sections are built.

### First screen: Orbit opening

**Observed:** A near-black 900px stage sits behind Navigation. At its center, a green 14px mono marker introduces three stacked 64px light serif promise lines, with 1.05 line height and centered alignment. The text zone is 906px wide but the visible lines span about two fifths of the viewport. Orbiting proof windows form an irregular outer constellation, keeping the central copy unobstructed. A small square down-arrow control is centered near the bottom. The first 900px contains the complete headline, marker, main image constellation, navigation conversion and scroll cue; ordinary explanatory sections fall below it. On continued scroll, the sticky stage isolates each promise with three concise supporting columns, an outlined discovery action and short pager marks.

**Transfer:** Write three parallel outcome promises for the new product and surround them with its real demonstrations; retain the orbit even if its media must be assembled from workflow panels. A service-specific opening can instead use one centered promise with a two-line support and an overflowing mixed media/metric rail. Editorial stories use a centered paper opening with compact category metadata and a large framed exhibit beneath; company stories pair the paper headline with a candid photo rail.

**Avoid:** Do not turn this into a conventional left-text/right-laptop split or cover the central promise with floating objects. Do not add a second large filled hero button when navigation already carries the main conversion.

**Text style:** `display` — Geist Arrow 300 · 64px/1.05 · tracking -0.01em

### Heading and discovery rail

**Observed:** Within the wide stage, a 40px Section heading sits at the left edge and Secondary button at the right. After 32px, Editorial media cards form a horizontal overflow rail with 30px gaps and a partially visible next card. Sections have 80px top and bottom space.

**Transfer:** Use this construction for product examples, resources or customer outcomes rather than compressing everything into a uniform three-column feature grid.

**Text style:** `section-heading` — Geist Arrow 300 · 40px/1.05 · tracking -0.01em

### Editorial split chapter

**Observed:** The editorial container divides into equal halves with a 30px gutter. A short 40px serif heading occupies the left; 20px/1.4 prose and 8px–16px paragraph gaps occupy the right. Chapters commonly have 64px vertical padding and alternate with Product exhibit gallery media.

**Transfer:** Use the left column for a capability or problem statement and the right for the mechanism and consequence. Let text length determine the chapter height.

**Text style:** `section-heading` — Geist Arrow 300 · 40px/1.05 · tracking -0.01em

### Centered statement and recognition

**Observed:** A 56px serif statement is centered in a 672px measure, followed after 32px by 20px centered supporting copy. A Monochrome logo rail follows, with a deep pause before the inquiry.

**Transfer:** Pair a concise position with independent recognition or compatibility marks rather than creating another dense feature list.

**Text style:** `centered-heading` — Geist Arrow 300 · 56px/1.05 · tracking -0.01em

### Open accordion chapter

**Observed:** Within a split chapter, the right column stacks entries anchored by left rules. A green mono prompt precedes a light serif title; a thin up/down arrow aligns at the far right. The expanded item changes its rule and arrow to green and reveals a short paragraph separated by a pronounced pause. The same device carries capability explanations, principles and pre-purchase questions.

**Transfer:** Use this for progressive disclosure where an introductory left column can stay short. Reuse the 16px ruled-column inset and the existing serif/sans/mono hierarchy; do not build enclosed dashboard accordions.

### Split inquiry

**Observed:** The marketing journey moves onto Paper destination. A 64px Statement and one 20px supporting sentence occupy the left half of the editorial container. The right holds a vertical series of numbered form rows, each with a fine left rule and outlined square number, followed by consent and a compact submit action. The module begins with 240px top space.

**Transfer:** Ask only the information needed for the next meaningful conversation, using numbered rows instead of a heavy form card. A shorter story ending replaces the form with a centered 64px question and Primary button 16px below.

**Text style:** `statement` — Geist Arrow 300 · 64px/1.05 · tracking -0.0156em

### Ruled footer and dotted finale

**Observed:** Newsletter band precedes the identity/link area and a thin utility-link strip. Top rules and vertically ruled columns organize the footer at 30px side gutters. The left half carries Footer identity column, with grouped navigation on the right. The final 282px zone contains Dot-matrix identity sculpture edge to edge. Marketing journeys finish on paper; paper-led stories finish on dark, with rules, text and dots switching tone together.

**Transfer:** Preserve the newsletter, ruled information hierarchy and monumental dotted closing device while adapting link groups to the new product. Keep the ending substantial rather than reducing it to a legal bar.

**Text style:** `footer-statement` — Geist Arrow 300 · 40px/1.05 · tracking -0.0208em

### Typographic people index

**Only for:** culture and company stories

**Observed:** A centered row of compact rectangular topic filters sits above a wide, centered field of first names set in large light serif type. Names wrap in loose rows with variable spacing, rather than appearing on portrait cards.

**Transfer:** Use this only for a human or contributor directory. Set the names to the visual scale of the opening serif and let real name lengths shape the wrapping.

## Page flow

**Storyline:** Outcome promise → visible proof → explanation of how it works → independent confidence → questions or invitation → ruled information and monumental identity.

### Broad marketing entrance

1. **Promise** — Sticky orbit stage presents three complementary outcomes, then gives each its own supporting moment.
2. **Visible proof** — Open work rail, large rotating customer quotation and editorial media rail.
3. **Positioning** — Centered statement and monochrome recognition rail.
4. **Conversion** — Tone changes to paper for a split numbered inquiry.
5. **Ending** — Newsletter, ruled identity and link columns, then dotted word sculpture.

**Transfer:** Start with outcomes, keep proof visible early, and use a tactile monochrome change to distinguish the invitation.

### Editorial case study for an institution or mission-led product

1. **Outcome framing** — Paper hero with category metadata and centered serif headline above a charcoal-matted desktop exhibit.
2. **Context** — Category links left and narrative right, followed by a three-mobile-view exhibit.
3. **Mechanism** — Alternating split text chapters and full or paired media explain architecture, trust and interaction.
4. **Result** — A final concise text chapter describes what changed.
5. **Continuation** — Related work rail, opposite-tone centered invitation, newsletter, ruled footer and dotted identity.

**Transfer:** Let each chapter explain a design or engineering decision and show its consequence immediately.

### Product transformation story with measurable proof

1. **Outcome framing** — Centered paper headline followed by a large framed product presentation.
2. **Context and method** — Split context, mobile triptych and simplification chapter.
3. **Independent confidence** — Inset white customer quotation interrupts the chapter sequence.
4. **Demonstration** — Large moving product scenes and pairs of tall media alternate with short explanatory chapters.
5. **Quantified proof** — Result statement, second testimonial and isolated 120px outcome figure in the right column.
6. **Ending** — Related work and opposite-tone invitation lead into the common ruled footer and dotted finale.

**Transfer:** Use the gallery to make the product tangible and one meaningful result to close the argument.

### Human and organizational story

1. **Belief** — Centered paper statement with a green-emphasized phrase and candid photo rail.
2. **Substance** — Split explanatory text and editorial rail connect the belief to practice.
3. **People** — Filterable typographic name field replaces a conventional headshot grid.
4. **Working principles** — Open ruled accordion and partner recognition rail.
5. **Credibility** — Spacious proof rows combine a mark, short outcome and figure.
6. **Ending** — The page darkens into a centered invitation and full ruled footer with dotted word sculpture.

**Transfer:** Show people, working habits and outcomes as separate kinds of proof rather than repeating a manifesto.

### Focused service or product landing page

1. **Promise and proof** — Single centered dark serif promise, subdued two-line support and an overflowing rail mixing imagery with a large metric.
2. **Capability chapters** — Split explanatory introductions, open accordions and editorial or project rails build the offering.
3. **Next step** — A subtle lifted-black band connects the initial engagement to ongoing value.
4. **Objection handling** — Split introduction and ruled questions answer practical concerns.
5. **Conversion and ending** — The page turns to paper for a numbered inquiry, newsletter and dotted footer.

**Transfer:** Use the same sparse chapter grammar for a focused offering; select proof and questions appropriate to the new purchase.

## Writing

Confident, senior and collaborative, with editorial elegance but little theatrical hype. Creative ambition is consistently connected to practical performance, operational clarity and business outcomes.

**Do not copy:** Do not reuse the brand's name or wordmark artwork, client identities, addresses, proprietary project descriptions, customer quotations or claimed results. Examples illustrate voice, not facts available to the new product.

- **Addressing the reader:** Use we for the maker and you or your for the reader, especially when inviting a conversation. Narrative case studies use third-person context before explaining what we changed.
- **Rhythm:** Short verb-led promise lines contrast with substantive explanatory paragraphs. Supporting sentences usually carry one clear idea; questions soften conversion moments. Ampersands appear in compact paired concepts.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A verb plus a concise consequential outcome; parallel lines can form a triptych. | 3–4 words per line | “Launch for impact”<br>“Optimise for success”<br>“Scale for tomorrow” |
| Case-study headline | Describe the transformation as a match between ambition and the delivered experience. | 9–13 words | “A web presence that matches the software behind it” |
| Section heading | A concise action or concrete area of inquiry, not an abstract benefit slogan. | 2–5 words | “Prototyping the brand in motion”<br>“What we do” |
| Supporting line | State the next action and the human follow-through plainly. | One sentence | “Share your brief or project goals, and a senior lead will follow up within 24 hours.” |
| Primary action | Direct verb and object; discovery controls use View or Explore. | 2–4 words | “Start a project”<br>“View field notes” |
| Closing question | Invite the reader to imagine a concrete next step rather than demand a sale. | 7–10 words | “What would you like to make next?” |

**Words and phrasing to use:** ambition; built to grow; real problems; outcomes; discovery; prototyping; clarity; together; launch; optimise; scale

**Avoid:** revolutionary; game-changing; best-in-class; seamless solutions; unlock limitless potential; crush the competition

**Rules:**

- Tie every broad creative claim to a mechanism, behavior or measurable consequence.
- Use specific implementation details where they explain why the outcome is credible, not as a jargon list.
- Keep button language literal; reserve editorial phrasing for headings.
- Use British spelling consistently and warm, plain questions at moments of commitment.

## Do's and Don'ts

### Do

- Keep primary display type at 64px/1.05, weight 300, paired with 14px mono utility lettering.
- Use a 38px primary key with 4px corners and green fill rather than a large pill.
- Protect the center of the orbit so all three promise lines remain readable.
- Use 30px outer gutters for media and the 1202px container for long-form chapters.
- Anchor footer groups with 1px rules and 16px left insets.
- Let colorful product media contrast with the monochrome page furniture.
- Give significant results a dedicated 120px serif figure rather than bold body type.
- Make the final dotted identity span the viewport within its 282px stage.

### Don't

- Do not replace the light serif system with bold geometric sans headings.
- Do not spread electric green across whole hero or feature backgrounds.
- Do not put every paragraph and image inside a padded, shadowed card.
- Do not normalize the floating opening media to identical sizes.
- Do not use pill corners for buttons or gallery windows; the default is 4px.
- Do not make ordinary metadata all caps with wide tracking; it is mostly sentence-case mono with normal tracking.
- Do not carry a showcased product's cloud skies, violet panels or UI typography into the outer marketing system.
- Do not reduce the footer to a small link strip or replace the dotted lettering with plain oversized text.

## Motion and responsive

### Motion

**Observed:**

- The opening uses a sticky full-height stage that changes from three promises into individual promise presentations during scrolling.
- Page tone changes between near-black and paper toward the ending; navigation and footer colors follow the tonal change.
- Declared media-card transform transition is .8s cubic-bezier(.16, 1, .3, 1). Declared proof entry opacity and transform transitions are .9s cubic-bezier(.165, .84, .44, 1).
- Declared ordinary link background-size transition is .3s cubic-bezier(.22, 1, .36, 1); quote pager fill uses 7s linear. Logo rails declare continuous linear marquee motion.

**Transfer:**

- Preserve the orbit-to-focused-promise storytelling and tonal destination rather than applying independent generic reveal effects everywhere.
- Keep the dot identity's localized softening small enough that the word remains legible.

**Unknown:**

- Exact scroll distances for each visual transition and the complete spring-like control easing are not specified.
- Pointer behavior of the dotted footer and complete reduced-motion behavior are unknown.

### Responsive

**Observed:**

- Desktop composition uses 12 columns. Styles declare width breakpoints at 320px, 352px, 425px, 480px, 576px, 768px, 845px, 1024px, 1280px and 1440px.
- Body copy remains 16px at 1440px and grows gently above that width through its stated formula.

**Transfer:**

- On narrow screens, move the orbit windows into a rail and keep the promise unobstructed; stack the split text and inquiry sections in reading order.
- Retain compact rectangular controls, left-rule groupings and the dotted closing identity as the layout narrows.

**Unknown:**

- Mobile layouts, navigation expansion and narrow-screen headline formulas are not established. These stacking rules are design guidance, not a measured mobile layout.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
