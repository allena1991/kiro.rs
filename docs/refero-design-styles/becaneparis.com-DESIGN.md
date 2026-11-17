# Bécane Paris — cutout runway index

## Overview

A light, fashion-editorial style that pairs an almost empty pale-grey stage with compact white control strips and wide, squared industrial sans lettering. Small isolated product figures carry the color, while immersive campaign photography offers a more confrontational, full-bleed alternative. The interface is exceptionally sparse and indexed; the closing statement is dense, emphatic and sculptural. It suits visually distinctive products, collections and image-led launches.

### Essentials

- A runway in miniature is the default opening device: a 1440px-wide pale stage holds a single horizontal line of isolated figures around its vertical midpoint, with objects only about 140px tall. For products without models, use clean cutout objects at the same restrained scale.
- Headlines behave like broad industrial nameplates, not oversized ad copy: Eurostile Becane 700, 30px/1, uppercase, normal tracking; the category and fraction above use 8px/1.1 with 0.04em tracking.
- Navigation is a floating instrument strip: a 350px-wide white panel inset 20px from the upper-left edge, with a compact wordmark above a row of 8px capital links and small counts.
- Actions are thin white rails rather than pills: 28px height, 3px corners, with a left label and right-aligned muted verb. Tiny 24px image selectors have 1px corners and a 0.5px active outline.
- The interface stays almost entirely neutral: #f6f6f6 canvas, #ffffff control rails, #0a0a0a lettering and #e6e6e6 hairlines. Color belongs to the isolated objects or edge-to-edge photographs, not decorative interface fills.
- A narrow manifesto closes the experience as a typographic sculpture: centered 30px/1.1 bold capitals in a 447px column, with 100px above and below; tiny split utility rails sit at the lower corners.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0a0a0a` | `--color-ink` | text, border | All main text and active selector outlines. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted control text | `#b2b2b2` | `--color-muted` | text, action | Secondary counts and action suffixes; declared hover text on links. |
| Hairline grey | `#e6e6e6` | `--color-rule` | border | Subtle divisions between utility links and the closing band. |
| Pale grey stage | `#f6f6f6` | `--color-canvas` | background | Continuous product stage and closing canvas. |
| White rail | `#ffffff` | `--color-control` | surface, text | Floating control strips; reversed editorial labels over dark photography. |

## Typography

- **Eurostile Becane** — All headings, manifesto text, metadata and navigation. Extended square industrial sans with broad capitals, flattened curves and tightly packed bold word shapes. If unavailable, use **Michroma**. Use its extended square construction; headings need a heavier visual treatment than its regular cut. Font stack: "Eurostile Becane", "Michroma", "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | Eurostile Becane | 700 | 30px | 1 | normal, uppercase | Compact left-aligned page title and next-category heading. |
| manifesto | Eurostile Becane | 700 | 30px | 1.1 | normal, uppercase | Centered multi-line closing statement. |
| label | Eurostile Becane | 400 | 8px | 1.1 | 0.04em, uppercase | Eyebrows, fractions, navigation, actions, credits and numbered entries. |
| detail | Eurostile Becane | 400 | 8px | 1.1 | normal, uppercase | Untracked metadata values and contact address. |

**Notes:**

- The two bold recipes have the same size and width character; alignment, column width and line height create the hierarchy.
- Small labels remain regular weight and tracked, rather than becoming a monospace substitute. Counts and contact text can use the untracked detail recipe.
- Use short headlines that fit the compact title area. The manifesto deliberately wraps into many short lines rather than becoming a wide paragraph.

## Layout

**Density:** Airy media stage with extremely compact controls: most of the screen is breathing room while labels and rails use tight internal spacing.

### Spacing

**Spacing system:**

- **gutter** 20px — Main layout gutter and repeated vertical metadata rhythm.
- **gap** 10px — Control padding and internal bar spacing.

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-title gap and gaps between navigation labels. |
| 10px | Control-strip side padding; top padding paired with 9px bottom padding. |
| 20px | Floating panel edge inset and metadata row rhythm. |
| 30px | Page title and metadata left inset. |
| 40px | Title group separation from metadata. |
| 100px | Space above and below the closing manifesto. |

### Containers and grids

- **Full-width stage**: max width 1440px · side padding 0px. At desktop the opening fills the 900px viewport height and the entire available width; no boxed central site container.
- **Title column**: max width 447px · side padding 30px. Title group anchored to the left, below the floating navigation; actual short title groups occupy roughly 280–325px.
- **Manifesto column**: max width 447px · side padding 0px. Centered narrow statement, surrounded by open canvas.
- **Catalog matrix** (only for catalog browsing): 6 columns · gap 0px · side padding 0px. Full-width square-cell product matrix; at 1440px the cells are about 240px square, with faint cell divisions and small lower-left numbers.

## Corner radius

| Element | Radius |
| --- | --- |
| Control rails | 3px |
| Media selectors | 1px |

## Surfaces and depth

### Surfaces

#### Pale stage · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #f6f6f6`

**Observed:** Seamless pale field behind isolated figures and metadata.

**Transfer:** Let objects define depth; keep the underlying canvas flat.

#### White rail · level 1

**Use:** Navigation, context selectors, action strips and utility groups.

**CSS:** `background: #ffffff; border-radius: 3px; box-shadow: none`

**Observed:** White is only slightly brighter than the page; the strip is read through its silhouette rather than elevation.

**Transfer:** Group related labels in shallow rectangles rather than large cards.

#### Closing band · level 0

**Use:** Manifesto ending.

**CSS:** `background: #f6f6f6; border-top: 0.5px solid #e6e6e6`

**Observed:** Full-width pale band, 756px tall in the desktop composition, with a centered statement and split utilities.

**Transfer:** Use the statement's natural height plus generous vertical margins; do not force a fixed height on shorter screens.

## Components

### Floating navigation

**Use:** Persistent brand and primary browsing controls.

**CSS:** `position: fixed; top: 20px; left: 20px; width: 350px; background: #ffffff; border-radius: 3px; z-index: 2000`

**Text style:** `label` — Eurostile Becane 400 · 8px/1.1 · tracking 0.04em · uppercase

**Observed:** Two stacked lines: a small italic wordmark above navigation. The top row is 30px tall and the lower row 28px. First links align left, cart aligns right; counts are subdued.

**Transfer:** Use the new identity's compact wordmark with a similarly short set of destinations.

### Counted navigation link

**Use:** Index navigation and cart destination.

**CSS:** `display: flex; color: #0a0a0a; background: transparent`

**Text style:** `label` — Eurostile Becane 400 · 8px/1.1 · tracking 0.04em · uppercase

**Observed:** A terse noun followed by a small muted count; adjacent destinations are separated by 8px.

**States:** Declared: hover on ancestor changes text to #b2b2b2; active outline none.

### Context rail

**Use:** Collection position and alternate visual views.

**CSS:** `display: flex; width: 233px; height: 28px; background: #ffffff; border-radius: 3px; overflow: hidden`

**Text style:** `label` — Eurostile Becane 400 · 8px/1.1 · tracking 0.04em · uppercase

**Observed:** Sits at the upper-right edge with 20px inset. A name and pale fraction occupy the leading space; tiny media selectors terminate the strip.

**Transfer:** Show a chapter, range or view state that is meaningful for the new product.

### Media selector

**Use:** Compact visual switcher inside the context rail.

**CSS:** `width: 24px; height: 24px; border-radius: 1px; outline: 0.5px solid #0a0a0a; overflow: hidden`

**Observed:** A tiny actual image or video, not a large icon button. The current item is outlined; inactive editorial selectors are subdued to 0.4 opacity.

**States:** Declared: active outline none.

**Transfer:** Use recognizable object silhouettes or image details.

### Discovery rail

**Use:** Primary route from the visual stage to deeper browsing.

**CSS:** `display: flex; width: 350px; height: 28px; background: #ffffff; border-radius: 3px; overflow: hidden`

**Text style:** `label` — Eurostile Becane 400 · 8px/1.1 · tracking 0.04em · uppercase

**Observed:** Anchored at the lower-left of the stage, inset 20px. A 2px inner wrapper leaves a 24px clickable interior; label is left-aligned and muted action verb is pushed to the far right. Editorial variants join multiple item links with tiny product thumbnails.

**Transfer:** Replace the count with an honest range or object label and use one low-pressure verb.

### Utility link

**Use:** Legal, help and contact actions within the split bottom rails.

**CSS:** `display: flex; padding: 10px 10px 9px 10px; height: 28px; box-sizing: border-box; color: #0a0a0a; border-right: 0.5px solid #e6e6e6`

**Text style:** `label` — Eurostile Becane 400 · 8px/1.1 · tracking 0.04em · uppercase

**Observed:** Adjacent links share a white outer rail. The final link has no separator; the contact address uses the detail recipe. One group sits left and a separate contact/social group sits right.

**States:** Declared: hover on ancestor changes text to #b2b2b2; active outline none.

### Manifesto block

**Use:** Emphatic brand-position ending.

**CSS:** `max-width: 446.7px; margin: 100px auto; color: #0a0a0a; text-align: center`

**Text style:** `manifesto` — Eurostile Becane 700 · 30px/1.1 · uppercase

**Observed:** A tall tightly wrapped mass of broad capitals; it is the main closing object, not subordinate footer copy.

**Transfer:** Write a genuine product philosophy with enough substance to create a column of short lines.

## Imagery and graphics

### Cutout runway

**Use:** Signature default visual stage.

**Observed:** A single evenly spaced line of about eleven isolated full-body figures in varied poses on the pale canvas. Their feet share a baseline and their heights are around 140px within a 900px-tall stage. Apparel colors are natural and subdued: black, cream, olive, pale blue and small pink accents; there are no scenery frames or graphic plinths.

**Transfer:** Use a series of isolated product views, objects or people at consistent perceived scale. For an intangible product, make a concise set of transparent-background artifacts or feature silhouettes rather than filling the space with a dashboard.

**Build:** Arrange transparent PNG/WebP silhouettes in one centered flex row spanning roughly four fifths of the width. Align their lower edges, use even spacing, constrain visual height near 140px at desktop and leave the field above and below empty. Use clean alpha edges with no card backgrounds or added shadow.

### Catalog cutouts

**Only for:** catalog browsing

**Use:** Fast visual comparison across a large range.

**Observed:** Small garment-only cutouts centered inside square pale cells. Each object occupies roughly a third of the cell height; a tiny two-digit number sits in its lower-left corner. Rows remain even despite very different object silhouettes.

**Transfer:** Normalize perceived scale and use short entry numbers rather than long descriptions. Keep products uncropped and the cell canvas continuous.

### Immersive campaign photography

**Only for:** editorial campaigns and stories

**Use:** Image-led narrative alternative to the pale miniature stage.

**Observed:** Edge-to-edge fashion photographs alternate hard daylight in industrial locations with dark studio scenes and close-up accessory details. Extreme foreground cropping, low angles, articulated bodies, windblown hair and tactile leather create energy. Olive, burgundy, black, cream and pink come from the subjects; photographic color fills the screen rather than becoming UI decoration. Image blocks span 1440px and are commonly 960px tall; the final portrait is much taller.

**Transfer:** Commission similarly assertive product-in-use photography with strong directional light and material detail. Alternate wide context and intimate detail; preserve image aspect ratios and let small controls float over it. A minimum equivalent is one strong contextual photograph and one material close-up, not a generic gradient.

### Icons

**Observed:** The interface relies on tiny product/media thumbnails, counts and plain words more than a decorative icon system. Selectors are 24px squares, with a thin active outline.

**Transfer:** Prefer useful miniature images to stock pictograms. Any necessary view switch should stay tiny and monochrome.

## Section recipes

How recurring sections are built.

### First screen: Miniature runway opening

**Observed:** A pale full-width stage occupies the entire first 900px. Back to front: flat Pale stage, a centered row of small Cutout runway figures, then left-aligned title metadata and floating White rail controls. Floating navigation sits upper-left, Context rail upper-right; the title group starts well below the navigation, around 144px from the top, using an indexed eyebrow, 8px gap, 30px bold title, then a count row after 40px. The figures cross the middle of the viewport and occupy only about 140px of its height, leaving substantial space around them. Discovery rail sits lower-left, 20px from the bottom. Everything needed to browse is visible above the fold; the Manifesto block begins below the stage.

**Transfer:** Create a miniature procession of the new product's most recognizable forms, maintaining a shared baseline and generous empty field. Use a short collection or product-family title rather than a paragraph pitch. Catalog variants open with the same title shell above a six-column matrix; editorial variants open on a full-bleed photograph with reversed title and credit metadata.

**Avoid:** Do not turn the scene into a conventional split hero with an enormous headline, paragraph and filled conversion button.

**Text style:** `heading` — Eurostile Becane 700 · 30px/1 · uppercase

### Indexed heading and metadata

**Observed:** A small uppercase type-and-fraction eyebrow sits above the compact title; metadata rows follow in a narrow left-aligned column. Labels and values are separated into two aligned fields, with 20px vertical row rhythm. Editorial overlays reverse to white on dark imagery and return to black on light scenes.

**Transfer:** Use range, chapter, specification or credit information appropriate to the product; keep the data concise.

**Text style:** `label` — Eurostile Becane 400 · 8px/1.1 · tracking 0.04em · uppercase

### Manifesto and split utilities

**Observed:** Closing band follows the visual content on every page type. Manifesto block occupies a centered 447px column with 100px upper and lower margins, wrapping into about sixteen short lines in the longer statement. Utility links form separate white rails at the lower-left and lower-right edges, inset 20px, while the floating navigation remains available above.

**Transfer:** Retain the monumental narrow-column closing device on every new page, using original positioning language rather than a repeated CTA headline.

**Text style:** `manifesto` — Eurostile Becane 700 · 30px/1.1 · uppercase

### Numbered catalog field

**Only for:** catalog browsing

**Observed:** Catalog matrix follows an approximately 280px-tall title zone. Six columns of square cells carry small centered cutouts and lower-left entry numbers. A later category changes the title and count; a final Next label with a bold destination title bridges into the ending.

**Transfer:** Organize a broad range as a visual index with grouped categories, retaining consistent scale and minimal text.

**Text style:** `heading` — Eurostile Becane 700 · 30px/1 · uppercase

### Edge-to-edge editorial sequence

**Only for:** editorial campaigns and stories

**Observed:** Consecutive full-width photographs have almost no inter-image gap. Compact title and credit metadata hold the upper-left area; Context rail persists upper-right, and item-specific Discovery rail variants connect the pictured objects to detail views near the lower-left. The sequence includes both wide scenes and a tall final close-up before the pale ending.

**Transfer:** Use a short visual essay rather than alternating generic feature cards. Keep contextual item links attached to the imagery they explain.

## Page flow

**Storyline:** Indexed identity → visual exploration → contextual route deeper → concentrated positioning statement with split utilities.

### Image-led product-family landing

1. **Orientation** — Compact title, collection fraction and range count beneath floating navigation.
2. **Product demonstration** — A miniature procession of isolated figures on an otherwise open pale stage.
3. **Deeper exploration** — A shallow lower-left discovery strip.
4. **Closing position** — Tall central manifesto and corner utility strips.

**Transfer:** Present a family of forms as one visual system and let users choose depth without lengthy explanatory sales sections.

### Range comparison and category browsing

1. **Orientation** — Indexed category title and count with a tiny visual view switch.
2. **Product comparison** — Six-column numbered cutout matrix grouped by category.
3. **Continuation** — Next-category destination after the object field.
4. **Closing position** — The same narrow manifesto ending and split utilities.

**Transfer:** Use for collections where visual recognition is more useful than descriptions; separate categories through concise title changes.

### Immersive editorial proof of product character

1. **Context** — Full-bleed opening photograph with small overlaid title and a two-column credits list.
2. **Product in use** — Continuous image sequence moving between action scenes and intimate material details.
3. **Contextual action** — Compact item links and image selectors accompany the relevant scenes.
4. **Closing position** — Pale manifesto band restores the common brand ending.

**Transfer:** Let a visual story provide proof and atmosphere, with lightweight paths from images to relevant objects.

## Writing

Self-possessed, physical and editorial. Functional labels are almost catalog-like; the manifesto shifts into assertive, rhythmic statements about freedom and character.

**Do not copy:** Do not reuse the Bécane wordmark, collection and product names, contributor names, collection counts, contact details, proprietary photographs or the manifesto's claims and wording. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Controls are impersonal nouns and verbs. Positioning uses our and your to connect product qualities with personal agency.
- **Rhythm:** Titles are usually one to three words. Actions are single verbs. The closing statement is a compact paragraph with sentence fragments, contrast and repeated phrasing, visually broken into very short lines.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Title | Short category noun or credited editorial name. | 1–3 words | “Collection”<br>“Lou Escobar” |
| Index eyebrow | Content type followed by a zero-padded current / total fraction. | One label and one fraction | “Collection 01 / 01”<br>“Story 01 / 04” |
| Action | Plain low-pressure exploration verb, often paired with an object count or name. | 1 word | “Discover”<br>“View” |
| Closing statement | Origin-versus-destination contrast, product attributes, then a statement of agency. | About 35–45 words | “Born on the road, made for the city. Technical, protective and unapologetically feminine, our pieces give women the confidence to move freely. A call to carve your own path, with no compromise and no concession.” |

**Words and phrasing to use:** collection; category; story; discover; view; made for; technical; protective; move; your own path

**Avoid:** revolutionary solution; unlock limitless potential; game-changing; act now; friendly exclamations

**Rules:**

- Let objects and photographs do most of the explaining.
- Keep counts factual and index labels systematic.
- Reserve the strongest rhetoric for the closing statement; keep interface language strictly functional.

## Do's and Don'ts

### Do

- Keep the default stage #f6f6f6 and controls #ffffff so objects supply the color.
- Use extended square 30px bold capitals for titles, with normal tracking.
- Keep interface text at 8px/1.1 with 0.04em tracking in the desktop composition.
- Inset floating rails 20px from viewport edges and title content 30px from the left.
- Use 28px-high rails and 24px visual selectors with 3px and 1px corners respectively.
- Retain the narrow 447px centered manifesto and 100px vertical margins.
- Normalize object scale and align cutouts by their feet or lower edge.

### Don't

- Do not replace the squared extended face with a narrow neo-grotesk; the broad word shapes are essential.
- Do not add drop shadows to the floating rails; their difference from the canvas is enough.
- Do not use colored action fills or gradient backgrounds to compete with the objects.
- Do not enlarge the tiny selectors into rounded thumbnail cards.
- Do not add product names, prices and descriptions below every catalog object; preserve the numbered visual-index character.
- Do not widen the manifesto into a conventional long-line paragraph or multi-column footer.
- Do not add stock icon clusters around the sparse stage.

## Motion and responsive

### Motion

**Observed:**

- Links declare a text-color change to #b2b2b2 on ancestor hover and outline removal on active.
- A header shine keyframe and easing definitions exist, but no action or surface transitions are specified here.

**Transfer:**

- Keep any visual browsing behavior subordinate to the miniature object lineup and compact media selectors.

**Unknown:**

- Actual animation timing, trigger behavior and carousel or canvas interactions are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 900px and 901px.

**Transfer:**

- On narrow screens, preserve the contrast between tiny controls and generous media space; adapt the miniature lineup to a browsable strip rather than shrinking objects beyond recognition.
- Keep the manifesto narrow relative to the viewport and allow utility groups to reflow without colliding with its text.

**Unknown:**

- Mobile column count, exact header arrangement and mobile typography sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
