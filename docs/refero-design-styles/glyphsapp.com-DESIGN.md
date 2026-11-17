# Glyphs — letterforms at play

## Overview

An exuberant editorial style for creative tools, combining confident serif headlines with friendly, workmanlike sans-serif explanations. A white canvas carries forest green and plum text, interrupted by acid lime, orange, cyan and golden yellow panels. Large live-looking product demonstrations, overlapping captions and a monumental typographic ending make the experience feel like a working designer’s specimen book rather than a conventional software brochure.

### Essentials

- Editorial promise, practical explanation: 80px/1 serif headlines contrast with 50px/55px sans-serif feature titles and 20px/1.25 body copy; tracking stays normal.
- The opening makes the output the hero: a left-aligned two-line promise above a 1440×500px unboxed demonstration, with the supporting sentence only reaching the bottom of the first 900px. Use a single oversized output specimen if no live demonstration exists.
- Actions are little blocks, not pills: the persistent header action is an 80×80px lime square; conversion panels use 160×160px squares with 5px corners, while ordinary buttons are 63px tall with 18px padding.
- White space remains the main material: most long-form content sits on white with roughly 100px desktop gutters; color is concentrated in 440–540px overlapping explanatory cards, lime proof bands and the closing plum panel, not spread as a uniform page tint.
- Demonstrations wear their captions on top: 1240×662px framed product images have 1px colored edges and 10px corners, with a solid caption card overlapping one side and extending toward the viewport edge. Include this graphic relationship even when the demonstration is a constructed diagram.
- Proof and the ending change scale dramatically: lime testimonial stages pair 280px monochrome portraits with thin 50px editorial quotes; the final plum panel carries an orange serif word sculpture at 479.9px/1, clipped by its edges. Retain both the bright proof device and monumental closing typography with new content.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Plum ink | `#42242e` | `--color-plum` | text, background, border | Default chapter headings, warm text, dark feature cards and the footer. |
| Forest ink | `#1e3219` | `--color-forest` | text, surface, action, border | Opening headline, navigation, lime-panel text and dark product panels. |
| Ochre ink | `#604900` | `--color-ochre-ink` | text | Text paired with cyan feature panels and educational cards. |
| Brown ink | `#4d2f1a` | `--color-brown-ink` | text | Text paired with golden feature panels and licensing actions. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid lime | `#9aff00` | `--color-lime` | action, surface, text, border | Persistent acquisition action, square purchase blocks and broad testimonial or closing-call panels. |
| Orange | `#f66a06` | `--color-orange` | surface, text, border, accent | Feature captions, carousel controls and oversized closing lettering. |
| Cyan | `#1ad1e6` | `--color-cyan` | surface, border, action | Feature captions and their matching media frames; occasional inline conversion action. |
| Golden yellow | `#f2ad0d` | `--color-gold` | surface, text, border, action | Feature captions, yellow text on plum, and licensing enquiry buttons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text | Main page canvas and reversed text. Header white at 50% opacity is visually white over the canvas and translucent over media. |
| Blush paper | `#f7eef1` | `--color-blush` | surface, text, border | Editorial recommendation panels, learning cards, handbook areas and reversed small footer controls. |
| Blue slate | `#243f42` | `--color-slate-ink` | text | Dense capability lists and chapter labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product choice and pricing sections | Mint paper | `#e9f3eb` | `--color-mint` | surface | Secondary product panel and comparison rows. |
| commerce and resource pages | Warm paper | `#f5f0ed` | `--color-warm-paper` | surface | Licensing information cards and saved-resource sidebar. |
| resource libraries | Ice paper | `#eef5f6` | `--color-ice-paper` | surface | Tutorial-card backing. |
| resource and commerce pages | Black | `#000000` | `--color-black` | text | Resource and commerce section headings. |
| reference indexes | Muted gray | `#6c6c6c` | `--color-muted` | text | Chapter-description links. |

## Typography

- **ABC Arizona Serif** — All editorial and interface lettering, with serif forms for major statements and sans forms for functional content. A variable sans-to-serif family: strong, high-contrast serif headlines; fine editorial quotation forms; open humanist sans-serif body and feature headings. OpenType features: "calt", "clig", "kern", "liga". If unavailable, use **Source Serif 4**. Use its display forms for editorial headlines and light cuts for quotations; pair with Source Sans 3 for functional roles. Font stack: "ABC Arizona Serif", "Source Serif 4", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| word-sculpture | ABC Arizona Serif | 400 | 479.9px | 1 | normal | fixed | Orange serif word sculpture across the bottom of the plum footer; deliberately wider than its clipping panel. |
| display | ABC Arizona Serif | 400 | 80px | 1 | normal | fixed | Bold-looking serif opening and major chapter headings. Use the serif end of the family, not the functional sans forms. |
| feature-heading | ABC Arizona Serif | 400 | 50px | 1.1 | normal | size clamp(1.75rem, 1.44rem + 1.47vw, 2.5rem) | Strong sans-serif titles inside feature cards and community introductions. |
| quote | ABC Arizona Serif | 400 | 50px | 1.1 | normal | size clamp(1.75rem, 1.44rem + 1.47vw, 2.5rem) | Thin serif quotations and light editorial calls; same dimensions as the feature heading but very different letterform texture. |
| lead | ABC Arizona Serif | 400 | 34px | 1.176 | normal | size clamp(1.5rem, 1.42rem + 0.39vw, 1.7rem) | Sans-serif support beneath major promises and chapter headings. |
| label | ABC Arizona Serif | 400 | 24px | 1.25 | normal | fixed | Sentence-case feature labels, card titles and secondary introductions in sans-serif forms. |
| body | ABC Arizona Serif | 400 | 20px | 1.25 | normal | fixed | Sans-serif feature explanations, product descriptions, lists and footer navigation. |
| small-body | ABC Arizona Serif | 400 | 18px | 1.4 | normal | fixed | Sans-serif action labels, image credits, attribution and long recommendation descriptions. |
| caption | ABC Arizona Serif | 400 | 14px | 1.43 | normal | fixed | Sans-serif navigation, topic tags, dates, helper text and footer notes. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| resource library openings | library-display | ABC Arizona Serif | 400 | 120px | 1 | normal | size clamp(4rem, 3.18rem + 3.92vw, 6rem) | Serif title of the resource catalogue. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The declared family carries contrasting optical voices: main serif headings look bold, serif quotations look extremely light, and feature headings look bold sans-serif even though the shared CSS weight is 400. Preserve these visual differences through the appropriate family variants; do not render every role with one regular serif cut.
- When using the free substitute pairing, use Source Serif 4 for display, quote and word-sculpture roles and Source Sans 3 for the functional roles. Tune visual weight to the intended appearance rather than applying the declared 400 blindly across different fonts.
- Keep tracking normal throughout. Hierarchy comes from letterform, size and color rather than uppercase eyebrows or squeezed spacing.
- Fluid formulas use a 20px root size; preserve that basis when translating rem values. Credit text can use italic emphasis within an otherwise upright body recipe.

## Layout

**Density:** Airy at section level and practical within cards: large white intervals surround compact explanatory paragraphs and strongly framed media.

### Spacing

**Spacing system:**

- **rhythm** 10px, vertical — Half-step vertical rhythm, with 20px, 40px, 50px, 60px and 80px recurring.
- **step** 20px, horizontal — Grid gaps and card spacing, most often doubled to 40px.

| Value | Use |
| --- | --- |
| 10px | Stacked action gaps and topic-filter gaps. |
| 18px | Ordinary button padding; a control-specific value rather than a layout step. |
| 20px | Label-to-title spacing, paragraph gaps and compact grid gaps. |
| 36px | Standard feature and editorial card top padding. |
| 40px | Card side and bottom padding, major grid gutters. |
| 50px | Feature title-to-description separation and opening media separation. |
| 60px | Testimonial and footer top padding; community-grid lead-in. |
| 80px | Major section separation and opening clearance beneath navigation. |
| 99.9px | Desktop content gutters and closing-call outer margins. |

### Containers and grids

- **page-frame**: max width 1440px · side padding 99.9px. Centered outer frame; leaves approximately 1240px for content at the desktop size.
- **editorial-grid**: 8 columns · gap 40px. Common underlying grid for major sections, overlapping media, footer and asymmetric closing call.
- **feature-stage**: max width 1240px. A wide demonstration around 662px tall with an overlapping 440–540px explanatory card; the card can bleed beyond the centered frame.
- **logo-wall**: 7 columns · gap 20px. 160px square community identities across the centered content area.
- **three-card-grid** (only for resource recommendations): 3 columns · gap 40px. Editorial recommendations, approximately 387px per card.
- **discount-grid** (only for commerce pages): 3 columns · gap 20px. 400px licensing information cards.
- **comparison-grid** (only for commerce comparisons): 2 columns · gap 40px. 600px parallel product columns with matching rows.

## Corner radius

| Element | Radius |
| --- | --- |
| cards-and-media | 10px |
| buttons-and-tags | 5px |
| carousel-controls | 50% |
| header-acquisition-square | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| header-inset-light | `inset 0px 2px 0px 0px rgba(255,255,255,0.4), inset 0px 0px 20px 0px rgba(255,255,255,0.15)` | Subtle inset light only on the translucent sticky header; content cards remain flat. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff`

**Observed:** White space separates the colorful stages; it is not textured or shadowed.

**Transfer:** Leave the main page white even when a capability chapter uses saturated panels.

#### Translucent navigation strip · level 2

**Use:** Sticky navigation over white and passing media.

**CSS:** `background: rgba(255,255,255,0.5); border-bottom: 0.5px solid rgba(255,255,255,0.5); backdrop-filter: blur(8px) saturate(1.8); box-shadow: inset 0px 2px 0px 0px rgba(255,255,255,0.4), inset 0px 0px 20px 0px rgba(255,255,255,0.15)`

**Observed:** The strip softly blurs passing colored content without a heavy dividing rule.

**Transfer:** Keep this material confined to navigation, not cards.

#### Saturated caption · level 1

**Use:** Overlapping feature descriptions.

**CSS:** `background: #1ad1e6; color: #604900; border-radius: 10px; box-shadow: none`

**Observed:** Other pairings are plum with gold text, gold with brown text and orange with plum text. All are opaque, flat color fields.

**Transfer:** Choose one of these deliberate color pairings per capability; match its media-frame edge to the card.

#### Blush editorial panel · level 1

**Use:** Recommendations and learning teasers.

**CSS:** `background: #f7eef1; color: #42242e; border-radius: 10px`

**Observed:** A gentle backing for dense information or large lightweight editorial text; imagery can occupy a full edge.

**Transfer:** Use for supporting resources rather than another saturated feature claim.

#### Lime proof stage · level 1

**Use:** Testimonials and expressive conversion moments.

**CSS:** `background: #9aff00; color: #1e3219; border-radius: 10px 10px 0px 0px`

**Observed:** Broad lime fields contrast with grayscale portraits and thin serif quotes.

**Transfer:** Use as a decisive interruption to the white page.

#### Plum ending · level 1

**Use:** Shared footer ending.

**CSS:** `background: #42242e; color: #ffffff; border-radius: 10px 10px 0px 0px; overflow: hidden`

**Observed:** A deep matte panel with white functional content and huge orange lettering below.

**Transfer:** End with this dramatic color reversal rather than a pale utility strip.

#### Warm information card · level 1

**Only for:** commerce and resource pages

**Use:** Eligibility explanations and saved-resource help.

**CSS:** `background: #f5f0ed; color: #42242e; border-radius: 10px; padding: 40px`

**Observed:** No shadow or extra border; licensing variants pair with gold actions.

**Transfer:** Group practical conditions separately from primary product promises.

#### Mint comparison row · level 1

**Only for:** product comparison sections

**Use:** Parallel capability statements.

**CSS:** `background: #e9f3eb; color: #000000; border-radius: 10px; padding: 36px 40px 40px`

**Observed:** Rows are 114px high at desktop and separated by 20px.

**Transfer:** Match row heights across products without turning the section into a ruled spreadsheet.

## Components

### Navigation

**Use:** Persistent global wayfinding.

**CSS:** `position: sticky; top: 0px; z-index: 100; background: rgba(255,255,255,0.5); backdrop-filter: blur(8px) saturate(1.8)`

**Text style:** `caption` — ABC Arizona Serif 400 · 14px/1.43

**Observed:** Brand mark and name sit on the left; compact links, Header acquisition square and a small outlined language control sit on the right. The desktop strip is 94–96px high; link targets are 40px tall with 17.5px horizontal padding.

**States:** Declared: hover behavior varies by action; focus-visible uses a 2px solid currentColor outline with 5px offset.

**Transfer:** Keep the primary action visually larger than the quiet navigation links.

### Header acquisition square

**Use:** Always-visible primary destination.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 80px; height: 80px; padding: 3.5px; background: #9aff00; color: #1e3219; border: 1px solid #9aff00; border-radius: 0px`

**Text style:** `caption` — ABC Arizona Serif 400 · 14px/1.43

**Observed:** Sits within the right-hand navigation cluster, separate from the language control.

**States:** Declared: hover reverses to lime text on forest with forest border; focus-visible uses a 2px solid currentColor outline with 5px offset.

### Primary button

**Use:** Inline conversion, purchase and download actions.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #9aff00; color: #1e3219; border: 1px solid #9aff00; border-radius: 5px; padding: 18px; height: 63px`

**Text style:** `small-body` — ABC Arizona Serif 400 · 18px/1.4

**Observed:** Width follows the context: 280px tool-card actions or the full comparison column. A cyan conversion variant uses ochre text. Commerce tool cards also use a forest secondary action with lime text; licensing enquiries use gold with brown text.

**States:** Declared: hover on the comparison purchase action reverses to forest fill with lime text and forest border; other tool actions become transparent with forest text and border. Focus-visible uses a 2px solid currentColor outline with 5px offset.

### Square conversion button

**Use:** High-emphasis product selection inside closing and commerce panels.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 160px; height: 160px; padding: 18px; background: #9aff00; color: #1e3219; border: 1px solid #9aff00; border-radius: 5px`

**Text style:** `small-body` — ABC Arizona Serif 400 · 18px/1.4

**Observed:** A compact centered label occupies a deliberately oversized square beside the product name and benefit copy.

**States:** Declared: hover on the dark-panel version makes the fill transparent and text lime, retaining the lime border; focus-visible uses a 2px solid currentColor outline with 5px offset.

### Overlapping feature card

**Use:** Explain the capability visible in the large product image.

**CSS:** `position: relative; z-index: 2; background: #1ad1e6; color: #604900; border-radius: 10px; padding: 36px 40px 40px`

**Text style:** `feature-heading` — ABC Arizona Serif 400 · 50px/1.1

**Observed:** Sentence-case label precedes the headline; an explanation and occasional italic maker credit follow. Desktop edge-bleed variants increase the outer-side padding to 99.9px and use a negative outer margin. The card alternates sides but never becomes a detached mini tile.

**Transfer:** Use a 24px label, the feature title recipe and 20px body; retain a substantial title-to-body interval.

### Testimonial stage

**Use:** Human proof between capability chapters.

**CSS:** `display: grid; grid-template-columns: 280px 1fr; column-gap: 40px; padding-top: 60px; background: #9aff00; color: #1e3219; border-radius: 10px 10px 0px 0px; overflow: hidden`

**Text style:** `quote` — ABC Arizona Serif 400 · 50px/1.1

**Observed:** A square monochrome portrait anchors the left of a thin serif quotation, with an arrow-led attribution below. Neighboring portraits partially enter beyond the content frame, and plain arrow controls sit at the lower right.

**Transfer:** Use genuine portraits and a concise attributed benefit rather than star ratings or a corporate logo strip.

### Monumental footer

**Use:** Shared final identity and utility section.

**CSS:** `background: #42242e; color: #ffffff; border-radius: 10px 10px 0px 0px; padding-top: 60px; overflow: hidden`

**Text style:** `body` — ABC Arizona Serif 400 · 20px/1.25

**Observed:** Theme control and reversed brand lockup sit left; three navigation columns and small credits sit right. A huge orange serif name spans the bottom and exceeds the panel width; this is part of the ending, not a conventional tiny copyright bar.

**Transfer:** Use the new product’s name or a short brand-relevant word as the orange sculpture; preserve the small-to-huge scale contrast.

### Topic tag

**Only for:** resource libraries

**Use:** Dense category filtering.

**CSS:** `background: #f7eef1; color: #42242e; border: 1px solid #f7eef1; border-radius: 5px; padding: 5.6px 10px 4.9px`

**Text style:** `caption` — ABC Arizona Serif 400 · 14px/1.43

**Observed:** A horizontal row with 10px gaps, with a plum-filled all-topics control first.

**States:** Declared: hover clears the fill and changes border to plum; focus-visible uses a 2px solid currentColor outline with 5px offset.

### Tutorial card

**Only for:** resource libraries

**Use:** Scannable educational articles.

**CSS:** `display: flex; flex-direction: column; gap: 20px; position: relative; background: #eef5f6; color: #604900; padding: 36px 40px 40px; border-radius: 10px`

**Text style:** `label` — ABC Arizona Serif 400 · 24px/1.25

**Observed:** Small 80px preview above a sans-serif title; a short 14px explanation and date beneath; bookmark tucked into the upper-right corner. Cards form staggered heights within a three-column content area beside a sidebar.

### Search rule

**Only for:** resource libraries

**Use:** Search-first opening utility.

**CSS:** `display: grid; grid-template-columns: auto 1fr; gap: 10px; border-bottom: 1px solid #42242e; height: 63px`

**Observed:** A small magnifying glass precedes a large, lightly styled search prompt. There is no filled input box or enclosing rounded rectangle.

**Transfer:** Let the underline stretch the entire content width.

### Product panel

**Only for:** product choice sections

**Use:** Side-by-side purchase decisions or stacked alternatives beside a closing call.

**CSS:** `display: flex; flex-direction: column; background: #1e3219; color: #ffffff; padding: 40px`

**Text style:** `body` — ABC Arizona Serif 400 · 20px/1.25

**Observed:** An oversized app symbol at the top leaves room before a Square conversion button beside the name and description. Commerce panels are 620px square, paired flush with a mint version using forest text. Thin top rules separate upgrade and download links below; system requirements remain adjacent to download actions.

**Transfer:** Distinguish product breadth with dark and light panels, not an added floating recommended badge.

### Comparison row

**Only for:** commerce comparisons

**Use:** Aligned benefits for two products.

**CSS:** `background: #e9f3eb; color: #000000; border-radius: 10px; padding: 36px 40px 40px; height: 114px`

**Text style:** `small-body` — ABC Arizona Serif 400 · 18px/1.4

**Observed:** Broad softly rounded rows align across the two columns. Important phrases are emphasized within each statement. Lime actions span each column beneath the rows.

## Imagery and graphics

### Oversized output specimen

**Use:** The opening’s main object.

**Observed:** An enormous forest-green calligraphic specimen sits isolated on white, spanning most of the page width within a 500px-high unboxed stage. Three understated sliders run beneath it; the object has no decorative device mockup or background gradient.

**Transfer:** Show the new product’s most expressive output, not a full dashboard. Minimum version: one large original vector specimen, transformation diagram or artifact with three restrained labeled controls.

**Build:** Use a full-width 500px stage with an SVG viewBox matching 1440×500. Center a single forest-filled or forest-stroked artifact across roughly two thirds of the width, leaving white around it. Beneath it place three evenly spaced neutral slider rails and short labels; keep controls subordinate to the artifact.

### Framed working demonstrations

**Use:** Capability chapters and longer workflow explanations.

**Observed:** Large pale application views show editing handles, curves, glyphs and floating tool windows. The marketing frame is 1px cyan, orange, gold or plum with 10px corners; native window shadows belong inside the image. Images dominate the section while opaque caption cards overlap their edges.

**Transfer:** Show real detailed work with enough visible controls to explain the feature. If the UI is unavailable, construct a pale SVG workspace with a relevant artifact, small editing handles and one compact inspector; do not fill it with arbitrary dashboard charts.

### Monochrome people

**Use:** Lime testimonial stages.

**Observed:** Square tightly framed black-and-white portraits contrast with vivid lime backing; neighboring slides can show partial portraits at the viewport sides.

**Transfer:** Use similarly direct grayscale photographs of actual people with consistent square framing and no colored duotone.

### Editorial media and objects

**Use:** Resource recommendations and supporting learning sections.

**Observed:** A photographed tablet held in one hand sits beside a blush quotation card; course covers and videos use full-width landscape thumbnails, while books use square cover photos and long blush-backed descriptions. The image colors remain authentic rather than recolored to a uniform brand tint.

**Transfer:** Use believable physical or digital resource covers, warm neutral photography and edge-to-edge thumbnails. Let third-party art retain its identity.

### Community identity wall

**Use:** Dense social proof near the end of marketing and commerce content.

**Observed:** A seven-column wall of 160px squares with 20px gutters contains diverse colorful logos and marks. Some fill their squares, some sit on white; the wall is not forced into grayscale uniformity.

**Transfer:** Use authentic partner or user identities at a consistent tile size. Allow varied original colors and optically center the artwork.

### Giant closing word sculpture

**Use:** The signature footer graphic.

**Observed:** A very wide high-contrast orange serif word is centered inside a plum panel and clipped at both sides. Its lower mass fills much of the ending while utility content remains small above.

**Transfer:** Use a short original product name or meaningful closing word. Preserve scale and overspill even with a different word length.

**Build:** Place a centered, single-line orange serif text element at 479.9px with line-height 1 inside the overflow-hidden plum footer. Give it enough intrinsic width to exceed the approximately 1240px panel; keep normal tracking, no stroke, no gradient and no shadow. Maintain a 40px separation from the utility area; tune font size for new word lengths so letters still clip at the sides.

### Icons

**Observed:** Small functional SVGs are mostly solid silhouettes: bookmarks about 20×30px, download arrows around 15×18px and compact play or search marks. Color follows the surrounding text; large arrows can be text glyphs rather than pictograms. Carousel controls are either plain 48px arrow targets or orange circles 48px across.

**Transfer:** Use simple filled bookmarks and download marks with text-colored paint; preserve plain textual arrows for directional copy. Avoid a large decorative line-icon library.

## Section recipes

How recurring sections are built.

### First screen: Output-led opening

**Observed:** A 94–96px translucent navigation strip anchors the top. After 80px of white clearance, the 80px serif promise sits left in the centered content frame, broken into two short lines and occupying roughly half the width. About 50px below it, the main output specimen expands into an unboxed full-width 500px stage. Back to front: white canvas, large forest artifact, understated controls, sticky frosted navigation. Within the first 900px the headline and almost all of the artifact and controls are visible; the 34px support line only begins at the lower edge, with its full text, maker credit and proof stage below. The only prominent initial action is the lime Header acquisition square; there is no centered pair of hero buttons.

**Transfer:** Use one impressive output or original vector artifact in place of the calligraphic specimen, retaining the left editorial promise and oversized white stage. Resource pages instead open with Search rule, a 120px catalogue title and category tags; commerce pages open directly with paired Product panels.

**Avoid:** Do not replace this with a centered SaaS slogan, gradient backdrop and tiny laptop image or force the support line and multiple buttons above the fold.

**Text style:** `display` — ABC Arizona Serif 400 · 80px/1

### Chapter heading pair

**Observed:** A left-aligned 80px plum serif headline leads the centered frame, sometimes followed after 20px by a 34px sans-serif supporting sentence. Major chapter changes leave 80px of breathing room.

**Transfer:** Use a short human benefit as the headline, then a practical one-sentence explanation.

**Text style:** `display` — ABC Arizona Serif 400 · 80px/1

### Overlapping capability stage

**Observed:** A 1240px-wide demonstration around 662px high wears a 1px matching colored border with 10px corners. An Overlapping feature card 440–540px wide sits vertically centered over either side, sometimes reaching the viewport edge. Inside: 24px sentence-case label, 50px sans-serif title, roughly 50px pause before 20px body copy, then an optional italic maker credit. Stages are separated by 80px.

**Transfer:** Change the capability and demonstrated artifact, preserving the relationship of large practical image and bold opaque caption. Alternate sides for visual cadence rather than making a uniform card grid.

**Text style:** `feature-heading` — ABC Arizona Serif 400 · 50px/1.1

### Persistent workflow chapters

**Observed:** A narrow colored chapter card on the left carries a serif chapter name above a large internal pause and a short practical explanation. Small tutorial links and a square tutorial action sit below. The right column carries a vertical sequence of approximately 760×442px framed demonstrations separated by 40px; left text remains an orienting anchor.

**Transfer:** Use for explaining a multi-stage workflow with a stable chapter label beside several worked examples, without making the empty space the subject.

### Bright testimonial interruption

**Observed:** The Lime proof stage uses Testimonial stage with a 280px monochrome portrait, 50px thin serif quote, 18px attribution and lower-right arrows. The centered lime panel contrasts with partial adjacent portraits extending outside the content width.

**Transfer:** Insert a genuinely human benefit quote wherever the story needs relief from product detail.

**Text style:** `quote` — ABC Arizona Serif 400 · 50px/1.1

### Editorial learning invitation

**Observed:** An 80px chapter title and 34px support introduce a large warm image on the left, paired with a blush panel containing lightweight 50px editorial text and arrow-led resource links.

**Transfer:** Connect the promise to useful supporting material, using a real object or cover image rather than another interface view.

**Text style:** `quote` — ABC Arizona Serif 400 · 50px/1.1

### Community mosaic

**Observed:** A 50px sans-serif heading and 24px invitation introduce the seven-column Community identity wall after a 60px gap. Colorful individual marks provide an energetic counterpoint to the orderly grid.

**Transfer:** Show a genuine ecosystem at consistent visual size; retain variety within the strict geometry.

**Text style:** `feature-heading` — ABC Arizona Serif 400 · 50px/1.1

### Asymmetric closing call

**Observed:** A lime 800px-wide, 800px-high editorial panel sits beside two stacked 440×400px Product panels in forest and mint. The left has a light 80px serif closing statement broken into short lines near its upper-left corner; the right contains 160px square actions. The composite keeps 10px outer corners and sits about 100px away from surrounding sections.

**Transfer:** Make a short emotional close beside practical choices. For one product, use the second panel for a distinct access route or helpful next step rather than inventing a second tier.

**Text style:** `display` — ABC Arizona Serif 400 · 80px/1

### Monumental identity ending

**Observed:** Monumental footer occupies a centered 1240px panel about 799px tall. A small theme switch and reversed lockup occupy the left; three utility columns occupy the right with 14px credits underneath. The Giant closing word sculpture fills the lower portion. Resource and commerce endings use the same treatment; commerce reaches it after the community wall, while the product narrative places the asymmetric closing call before it.

**Transfer:** Keep the dramatic dark ending and huge clipped lettering consistent across page types. Adapt the utility links without reducing the final identity to a small logo.

**Text style:** `word-sculpture` — ABC Arizona Serif 400 · 479.9px/1

### Resource catalogue

**Only for:** resource libraries

**Observed:** Search rule precedes a 120px serif title, Topic tags and an asymmetric layout: a 280px saved-items sidebar beside a 920px article area. An orange recommended-starting panel anchors the article grid; ice-backed Tutorial cards continue with varied heights and bookmark controls.

**Transfer:** Distinguish a recommended entry path from the full catalogue rather than treating every article as equal.

**Text style:** `library-display` — ABC Arizona Serif 400 · 120px/1

### Reference index and recommendation shelves

**Only for:** resource libraries

**Observed:** An 80px title precedes a broad blush chapter index with a narrow plum online-reading rail and orange download rail to the right. Descriptive chapter links pair slate labels with gray explanations. Following shelves use three landscape-image blush course cards with 40px gaps, then a horizontally extending row of 280px book cards with 20px gaps and orange circular controls.

**Transfer:** Separate structured reference, guided instruction and external resources into visually distinct formats while retaining the serif chapter hierarchy.

**Text style:** `display` — ABC Arizona Serif 400 · 80px/1

### Commerce decision panels

**Only for:** commerce pages

**Observed:** Two flush 620px square Product panels open the page below the header: forest and mint, each with a prominent symbol, Square conversion button, product summary, ruled alternative action and download information. Subsequent 80px serif chapters introduce a three-column warm-card eligibility grid, a four-column tool grid and a two-column comparison with Mint comparison rows and full-width lime actions.

**Transfer:** Make the buying decision concrete first; handle eligibility and supporting tools in separate subordinate chapters rather than inflating the primary choice into many pricing tiers.

**Text style:** `display` — ABC Arizona Serif 400 · 80px/1

## Page flow

**Storyline:** expressive promise → demonstrated usefulness → human proof → deeper capability or decision support → ecosystem → decisive branded ending

### Long-form product marketing

1. **Promise** — Two-line serif statement above an oversized output specimen.
2. **Social proof** — Lime portrait-and-quote interruption.
3. **Capability chapters** — Colored overlapping cards paired with large framed demonstrations.
4. **Practical reassurance** — Dense capability lists, an inline action and longer workflow chapters.
5. **Education and ecosystem** — Editorial learning invitation, resource promotion, extension showcase and identity wall.
6. **Closing call** — Asymmetric lime statement beside stacked product choices.
7. **Identity ending** — Plum utility panel and giant orange word sculpture.

**Transfer:** Let a creative product tell its story through tangible output, detailed examples and people. Adapt chapter count and sequence to the product, keeping the signature visual devices.

### Searchable learning and reference hub

1. **Find a starting point** — Search underline, monumental catalogue title, tags, saved-items sidebar and orange recommendations.
2. **Browse practical help** — Ice-backed article cards with dates and bookmarks.
3. **Reference depth** — Blush chapter index with contrasting reading and download rails.
4. **External learning** — Landscape course cards and a horizontal book shelf.
5. **Identity ending** — Shared plum footer with oversized orange lettering.

**Transfer:** Prioritize finding and progressing through information; use the same expressive typography without adding a product-marketing hero.

### Purchase and product comparison

1. **Immediate choice** — Flush dark and light product panels with square purchase actions.
2. **Objection handling** — Warm eligibility cards with gold enquiry buttons.
3. **Supporting ecosystem** — Open four-column tool grid with paired dark and lime actions.
4. **Decision support** — Two parallel columns of mint capability rows and lime actions.
5. **Social reassurance** — Lime human quote and colorful identity wall.
6. **Identity ending** — Shared plum footer with monumental orange lettering.

**Transfer:** Lead with concrete choices and purchasing routes, then resolve conditions and comparisons before the shared branded close.

## Writing

Warm, capable and designer-to-designer. Emotional enjoyment leads the story, but explanations are specific, operational and comfortable with technical vocabulary.

**Do not copy:** Do not reuse the brand’s name, logos, specimens, customer identities, attributed quotes, prices, licensing terms or product-performance claims. Source examples illustrate cadence only.

- **Addressing the reader:** Address the reader as you and your. Use direct imperatives for tasks and the product name when explaining what the tool does; reserve first-person language for genuine attributed quotations.
- **Rhythm:** Short, punchy headlines often use two clauses or a sequence of tiny sentences. Explanations become conversational paragraphs with concrete verbs, occasional em dashes and parenthetical technical details.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Task plus emotional reward, split into two short sentences. | 5–9 words | “Create fonts. Love the process.” |
| Feature headline | A practical benefit with a playful turn or direct command. | 4–10 words | “Stop thinking. Build visually.”<br>“Massive families, zero friction.”<br>“Colors, blends, gradients. You got it.” |
| Supporting explanation | Describe the action, available control and resulting benefit in that order. | 25–65 words | “Pick caps and corners for your monoline strokes, batch-edit with ease. Enjoy the many more options at your fingertips.” |
| Primary action | Plain verb with destination, often preceded by a textual arrow. | 2–6 words | “→ Get [Brand] 4”<br>“Download App” |
| Resource heading | Short literal nouns, no invented category metaphors. | 1–3 words | “Tutorials”<br>“Handbook”<br>“Courses” |
| Closing call | A rhythmic chain of very short sentences. | 4–8 words | “Love it. Get it. Here.” |

**Words and phrasing to use:** create; love; draw; control; pick; try; right here; with ease; at your fingertips

**Avoid:** revolutionize your business; enterprise-grade synergy; unlock limitless potential; AI-powered everything; disruptive platform

**Rules:**

- Pair enjoyment with a visible practical capability; keep unsupported superlatives out of new claims.
- Keep eyebrows in sentence case and name the feature directly.
- Use arrows as part of concise destination links, not as decorative punctuation in every sentence.
- Technical detail belongs in explanations and references, not in the emotional opening line.
- State eligibility, system requirements and access routes plainly beside the relevant action.

## Do's and Don'ts

### Do

- Keep the main canvas white and reserve the strongest color for distinct caption and proof blocks.
- Use 80px serif promises against 20px sans-serif explanations rather than a single typographic texture.
- Keep desktop content within the 1440px frame with about 100px side gutters.
- Use 10px corners for content and 5px corners for actions; preserve the square header CTA.
- Stage one large demonstration per capability with its 1px color-matched frame.
- Retain 40px card gutters and 80px chapter intervals as the main long-page cadence.
- Use 280px grayscale portraits against lime for human proof.
- Give the ending a deep plum panel and a huge orange serif word, not just utility links.

### Don't

- Do not apply the family’s serif forms to navigation, body copy or the bold sans-serif feature titles.
- Do not tighten tracking across the board; normal tracking is part of the open editorial character.
- Do not turn the 80px header square or 160px product action into a pill.
- Do not add drop shadows to the flat colored captions and pale cards; shadows belong only to the header material or pictured application windows.
- Do not replace the 1px colored media edges with thick dark device bezels.
- Do not flatten the varied original logos into a uniform gray strip.
- Do not turn the two-column mint comparison into a dense ruled spreadsheet.
- Do not use uppercase micro-eyebrows where the design uses 24px sentence-case labels.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use 0.166s cubic-bezier(0.25, 0.46, 0.45, 0.94) for color, background-color and border-color; some image and arrow interactions use opacity on the same timing.
- Plain carousel arrows declare hover opacity 0.5 and active opacity 0.33. Orange circular controls declare a hover mix of 70% orange with blush and an active plum border.
- The sticky header declares a padding-block transition on the same 0.166s curve. Interactive demonstrations and carousels accompany the output-led storytelling.

**Transfer:**

- Use the declared short transitions for block-action reversals; keep the interaction readable as a flat color change.
- If a product supports meaningful direct manipulation, put it in the oversized output stage rather than adding decorative background animation.

**Unknown:**

- Timing and behavior of the output demonstration, giant-word hover effect and scroll-linked workflow changes are not fully specified.

### Responsive

**Observed:**

- Declared width boundaries include 374/375px, 499/500px, 799/800px, 999/1000px, 1199/1200px and 1439/1440px, plus 420px.
- Feature, lead and catalogue title recipes include viewport-relative clamp formulas.

**Transfer:**

- On narrow layouts, preserve the serif/sans contrast, strong square action motif and clipped footer word. As a design adaptation, place an overlapping caption below or partly across its image rather than shrinking the text into a narrow desktop arrangement.
- As a design adaptation, stack product choices and reference rails when their content can no longer remain readable; retain dark/light pairing and direct access to the actions.

**Unknown:**

- Exact small-screen layout changes, navigation replacement and responsive media cropping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
