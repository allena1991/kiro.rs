# Real Food — monumental civic conviction

## Overview

A forceful editorial style that turns a public-facing message into a visual manifesto. Near-black brown alternates with warm ivory and pale butter, with red reserved for urgent proof and vivid color carried by tactile illustrations. Heavy grotesk headlines, compact supporting text, cinematic monochrome film and oversized painted objects create a spacious, persuasive experience suited to campaigns and mission-led products.

### Essentials

- Headlines feel like a verdict rather than a slogan: Die Grotesk D at 700, 170px/0.86 for the opening and 96px/0.95 for major declarations, with normal or zero tracking.
- The first impression is a centered dark poster with a film emerging below it: a two-line headline about 690px wide, a 600px-wide support paragraph at 21px/1.1, and a rounded monochrome media stage whose top is visible within the first 900px.
- Controls are soft capsules against uncompromising typography: primary actions are 60px tall with 40px radii and 18px 28px padding; the floating chapter navigator is a 42px-high translucent pill with dots around the current label.
- The page changes emotional register through whole fields, not decorative gradients: #110000 dominates the opening narrative and closing exhibit, #fdfbee backs illustrated explanations, and #f3f0d6 backs reassurance and conversion. Red is confined to a concentrated proof treatment rather than spread across the page.
- Objects become the demonstration: saturated, painterly cutouts overlap on bare ivory, occupy more area than the 360px-wide explanatory column and extend beyond the viewport. Recreate this with a few carefully isolated product objects when a large illustration library is unavailable.
- Include monumental reading and a collectible closing exhibit: centered 96px/0.96 word-by-word statements change from muted to full contrast, while a dark closing scene sandwiches a three-card object carousel between two 144px display lines. For intangible products, turn recognizable outputs into illustrated objects or editorial artifact cards.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brown black | `#110000` | `--color-ink` | text, background, action | Primary ink, dark narrative fields, primary buttons and the closing exhibit. |
| Butter sand | `#f3f0d6` | `--color-sand` | background, surface, action | Reassurance and conversion bands; secondary action fill. |
| Dark frosted glass | `#291a1a` | `--color-glass` | surface | Visible white at 10% over brown black; floating navigation uses the alpha recipe so underlying scenes remain visible. |
| Soft brown ink | `#4c3f3c` | `--color-secondary-ink` | text | Visible result of ink at 75% over ivory; explanatory paragraphs use the original ink with opacity 0.75. |
| Muted rose gray | `#8d7d7d` | `--color-dimmed` | text | Inactive words in oversized reading statements on dark fields. |
| Soft reversed ivory | `#c2bcb3` | `--color-secondary-reverse` | text | Visible result of ivory at 75% over brown black; hero supporting copy. |
| Warm hairline | `#e1ddd1` | `--color-rule` | border | Visible ink at 12% over ivory; separators inside the proof panel. |
| Exhibit gray | `#f5f5f5` | `--color-side-card` | surface | Smaller neighboring cards in the closing exhibit. |
| Warm ivory | `#fdfbee` | `--color-canvas` | background, surface, text | Illustration canvas, inset panels, FAQ rows and reversed display text. |
| Exhibit white | `#ffffff` | `--color-white` | surface, text | Active carousel card, circular play control and media-action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| urgent quantitative proof | Alert red | `#ff0101` | `--color-red-text` | text, accent | A few consequential words in proof captions; not ordinary links. |
| urgent quantitative proof | Strong proof red | `#d50000` | `--color-red-high` | surface | Tallest bar in the concentrated quantitative proof graphic. |
| urgent quantitative proof | Middle proof red | `#b50000` | `--color-red-mid` | surface | Middle bar in the concentrated quantitative proof graphic. |
| urgent quantitative proof | Deep proof red | `#920000` | `--color-red-low` | surface | Lowest bar in the concentrated quantitative proof graphic. |

## Typography

- **Die Grotesk D** — Large headlines, declarations, chapter headings and numerical proof. Heavy, closely fitted grotesk with blunt terminals and very compact display leading. If unavailable, use **Inter Tight**. Use 700; retain compact leading and fit headlines by line breaks rather than extra tracking. Font stack: "Die Grotesk D", "Inter Tight", system-ui, -apple-system, "Segoe UI", Arial, sans-serif.
- **Die Grotesk B** — Supporting claims, compact card titles, proof captions and FAQ questions. Assertive bold grotesk that keeps small supporting text substantial. If unavailable, use **Inter Tight**. Use 700 for supporting claims and card titles. Font stack: "Die Grotesk B", "Inter Tight", system-ui, -apple-system, "Segoe UI", Arial, sans-serif.
- **Die Grotesk A** — Body text, actions, resource links and small credit text. Practical readable grotesk, primarily medium in the short body copy and regular in expanded explanations. If unavailable, use **Inter**. Use 400–500 for text and actions. Font stack: "Die Grotesk A", "Inter", system-ui, -apple-system, "Segoe UI", Arial, sans-serif.
- **Geist Mono** (only for institutional attribution strips) — Small uppercase institutional or ownership labels. Even monospaced capitals with deliberately open spacing. Font stack: "Geist Mono", ui-monospace, SFMono-Regular, Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Die Grotesk D | 700 | 170px | 0.86 | 0px | fixed | Two-line opening declaration, centered. |
| chapter-display | Die Grotesk D | 700 | 154.8px | 0.84 | 0px | size 10.75vw | Headline over the large illustrated overview. |
| exhibit-display | Die Grotesk D | 700 | 144px | 0.956 | normal | fixed | Closing exhibit's fixed phrase and changing object name. |
| closing-call | Die Grotesk D | 700 | 115.2px | 0.95 | 0px | size clamp(48px, 8vw, 120px) | Broad two-line conversion heading. |
| declaration | Die Grotesk D | 700 | 96px | 0.95 | normal | fixed | Major persuasive headings in dark or light fields. |
| reading-statement | Die Grotesk D | 700 | 96px | 0.96 | normal | fixed | Large centered prose with individual words changing contrast. |
| feature-heading | Die Grotesk D | 700 | 44px | 1.02 | normal | fixed | Compact headings alongside oversized illustration scenes. |
| utility-heading | Die Grotesk D | 700 | 44px | 1.04 | normal | fixed | Resource and FAQ section headings. |
| hero-support | Die Grotesk B | 700 | 21px | 1.1 | 0px | fixed | Dense centered paragraph below the opening headline. |
| section-support | Die Grotesk B | 700 | 21px | 1.2 | 0px | fixed | Centered support for proof and conversion sections, with reduced opacity. |
| body | Die Grotesk A | 500 | 16px | 1.18 | normal | fixed | Compact explanatory text alongside imagery and within proof rows. |
| expanded-body | Die Grotesk A | 400 | 16px | 1.5 | normal | fixed | Expanded FAQ answers. |
| small-heading | Die Grotesk B | 700 | 16px | 1.5 | normal | fixed | FAQ questions and compact labeled items. |
| action | Die Grotesk A | 500 | 16px | 1.5 | normal | fixed | Primary and secondary capsule actions. |
| download-link | Die Grotesk A | 500 | 14px | 1.4 | normal | fixed | Underlined document download rows. |
| eyebrow | Die Grotesk B | 700 | 14px | 0.92 | normal | fixed | Small sentence-case label above a persuasive heading. |
| credit | Die Grotesk A | 400 | 12px | 1.1 | -0.02em, uppercase | fixed | Single centered credit line in the footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| urgent quantitative proof | stat | Die Grotesk D | 700 | 48px | 0.92 | normal | fixed | Black percentages placed inside red proof bars. |
| urgent quantitative proof | stat-caption | Die Grotesk B | 700 | 24px | 0.95 | normal | fixed | Captions below proof bars, cream with selective red words. |
| institutional attribution strips | institutional-label | Geist Mono | 400 | 12px | 1.4 | 0.06em, uppercase | fixed | Attribution strip above the opening. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display hierarchy comes from size, heavy weight and unusually short leading, not increased letter spacing. Do not add a broad tracking treatment to the large headlines.
- Keep the 44px feature-heading and utility-heading roles distinct: the former is tighter for short multi-line labels, the latter slightly more relaxed.
- Supporting copy is bold but visually subordinate through narrow measure and opacity: 75% reversed ivory in the hero; 50% ink in the conversion support. Body paragraphs use 75% ink; expanded answers use 85% ink.

## Layout

**Density:** Airy at the chapter scale and compact within text. Long visual pauses surround dense, tightly led declarations and small explanatory columns.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Question-to-answer and closely associated text gaps. |
| 12px | Gap between collapsed FAQ rows and inside secondary actions. |
| 16px | Eyebrow-to-heading and proof caption gaps. |
| 24px | Object-card padding and spacing before short target statements. |
| 28px | Opening content stack gap and action side padding. |
| 32px | Feature-heading-to-copy and conversion stack gap. |
| 40px | Resource content gaps and two-column grid gutter. |
| 80px | Proof grid gutter and space from heading group to proof panel. |
| 100px | FAQ heading-to-list pause and major chapter gap token. |
| 128px | Default major section vertical padding. |
| 144px | Desktop outer side padding. |
| 192px | Deeper lead-in or tail on reassurance and closing-call bands. |
| 256px | Deep opening space above the illustrated overview. |

### Containers and grids

- **main-container**: max width 1076px · side padding 144px. Centered desktop text and utility container. Full-bleed backgrounds extend beyond it; illustrated objects can exceed it.
- **hero-measure**: max width 800px. Centered headline measure, with a 600px-wide supporting paragraph below.
- **feature-copy**: max width 360px · gap 32px. Left-aligned short heading and body column beside artwork that dominates the remaining space.
- **resource-split**: max width 1076px · 2 columns · gap 40px. Two equal grid tracks, with a 340px text-and-links column within the left track and a layered artifact display on the right.
- **proof-grid**: max width 1076px · 3 columns · gap 80px. Three equal 305px proof columns, aligned on the bars' bottom edges.
- **proof-panel**: max width 600px. Narrow centered checklist panel under a broad heading and support paragraph.

## Corner radius

| Element | Radius |
| --- | --- |
| actions-and-faq | 40px |
| media-and-exhibit-cards | 24px |
| document-covers | 12px |
| floating-navigation | 9999px (pill) |
| play-capsule | 48px |
| play-control | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| proof-panel | `0px 4px 18.6px 0px rgba(0, 0, 0, 0.17)` | Soft lift for the single checklist panel. |
| document-cover | `0px 7.7px 7.7px 0px rgba(0, 0, 0, 0.05), -5px -7px 7.7px -4px rgba(0, 0, 0, 0.25)` | Dimensional paper edges on artifact covers. |
| exhibit-card | `0px 10px 40px 0px rgba(0, 0, 0, 0.1), 0px 20px 60px -10px rgba(0, 0, 0, 0.1)` | Closing exhibit object cards. |

### Surfaces

#### Ivory canvas · level 0

**Use:** Main explanatory and artifact stages.

**CSS:** `background: #fdfbee; color: #110000`

**Observed:** Flat warm paper color without a visible grain overlay.

**Transfer:** Let vivid objects carry the color; keep their backing uniform.

#### Dark manifesto · level 0

**Use:** Opening, persuasive reading scenes and closing exhibit.

**CSS:** `background: #110000; color: #fdfbee`

**Observed:** A warm brown-black field, not a cool charcoal gradient.

**Transfer:** Give it sustained chapter-scale coverage rather than making every other small row dark.

#### Sand band · level 0

**Use:** Reassurance, FAQ, manifesto recap and conversion.

**CSS:** `background: #f3f0d6; color: #110000`

**Observed:** A pale yellow change from ivory that unites several content blocks.

**Transfer:** Group utility and reassurance on this slightly deeper warm field.

#### Inset illustration sheet · level 1

**Use:** The transition from dark prose to the object-led demonstration.

**CSS:** `background: #fdfbee; border-radius: 12px 12px 0px 0px`

**Observed:** Rounded upper corners announce a light sheet opening within the dark chapter; it expands into the explanatory field.

**Transfer:** Use a physical sheet-like transition rather than a gradient crossfade.

#### Frosted navigation · level 2

**Use:** Floating chapter tracker.

**CSS:** `background: rgba(255, 255, 255, 0.1); backdrop-filter: blur(24px); border-radius: 9999px`

**Observed:** Small translucent capsule, with light or dark contrast appropriate to the underlying chapter.

**Transfer:** Keep this localized to the navigator rather than turning all content into glass.

#### Raised proof panel · level 1

**Use:** Checklist of achieved outcomes.

**CSS:** `background: #fdfbee; border-radius: 24px; box-shadow: 0px 4px 18.6px 0px rgba(0, 0, 0, 0.17)`

**Observed:** One narrow rounded panel on the sand field, with inset hairlines separating rows.

**Transfer:** Use it to collect concrete evidence rather than generic feature blurbs.

## Components

### Chapter navigator

**Use:** Fixed, centered progress and section navigation during long-form reading.

**CSS:** `display: flex; align-items: center; height: 42px; padding: 0px 20px; background: rgba(255, 255, 255, 0.1); border-radius: 9999px; backdrop-filter: blur(24px)`

**Observed:** A single current chapter label sits among circular progress dots; noncurrent chapters collapse to dots rather than remaining a full link menu. The dark-field version uses white labels and translucent white dots; the light-field version changes contrast.

**Transfer:** Use the new page's chapter names and preserve the compact current-label-plus-dots model.

### Primary button

**Use:** Main conversion action on a light field.

**CSS:** `display: flex; align-items: center; height: 60px; padding: 18px 28px; background: #110000; color: #fdfbee; border-radius: 40px`

**Text style:** `action` — Die Grotesk A 500 · 16px/1.5

**Observed:** Text-only capsule centered below the conversion copy; width follows its short label.

**States:** Declared: hover color #fdfbee and background-color rgba(15, 0, 0, 0.85); focus-visible outline none.

### Secondary button

**Use:** Supporting watch or explore action within utility content.

**CSS:** `display: flex; align-items: center; gap: 12px; height: 60px; padding: 18px 22px 18px 28px; background: #f3f0d6; color: #110000; border-radius: 40px`

**Text style:** `action` — Die Grotesk A 500 · 16px/1.5

**Observed:** A short sentence-case label is followed by a small right arrow.

**States:** Declared: hover background-color #f4ffae; focus-visible outline none.

### Media play capsule

**Use:** Overlay action centered on the cinematic media preview.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; height: 66px; padding: 8px 8px 8px 24px; background: rgba(0, 0, 0, 0.25); color: #ffffff; border: 1px solid rgba(250, 250, 250, 0.2); border-radius: 48px; backdrop-filter: blur(17.5px)`

**Text style:** `body` — Die Grotesk A 500 · 16px/1.18

**Observed:** The label is followed by a separate white 48px circular control with a dark play glyph.

**States:** Declared: hover background rgba(0, 0, 0, 0.35) and transform scale(1.05); focus-visible outline none with outline-offset 2px.

### FAQ row

**Use:** Long-form objection handling on the sand field.

**CSS:** `display: flex; gap: 16px; padding: 18px 22px 18px 28px; min-height: 72px; background: #fdfbee; color: #110000; border-radius: 40px`

**Text style:** `small-heading` — Die Grotesk B 700 · 16px/1.5

**Observed:** Question at left, small downward arrow at far right. Rows are separated by 12px; the answer sits within the same capsule and uses expanded-body with 8px gaps.

**Transfer:** Keep collapsed questions short and let expanded answers remain readable prose rather than another oversized headline.

### Outcome panel

**Use:** Concrete proof collected into a single narrow card.

**CSS:** `max-width: 600px; background: #fdfbee; border-radius: 24px; box-shadow: 0px 4px 18.6px 0px rgba(0, 0, 0, 0.17); overflow: hidden`

**Text style:** `body` — Die Grotesk A 500 · 16px/1.18

**Observed:** Five stacked title-and-description rows, each with a green check at the right. Hairlines are inset 32px from both sides. Titles are bold and descriptions subordinate.

**Transfer:** Use a compact list of verified outcomes; row count should follow the content.

### Download row

**Use:** Links paired with a tangible editorial artifact display.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 24px; max-width: 340px; color: #110000; text-decoration: underline`

**Text style:** `download-link` — Die Grotesk A 500 · 14px/1.4

**Observed:** The text can wrap in a 266px measure. A small right arrow sits in a pale circular backing at the far edge; link rows are spaced 20px apart.

**States:** Declared: focus-visible outline none with outline-offset 2px.

### Exhibit card

**Use:** Active object in the signature closing carousel.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 300px; height: 300px; padding: 24px; background: #ffffff; border-radius: 24px; box-shadow: 0px 10px 40px 0px rgba(0, 0, 0, 0.1), 0px 20px 60px -10px rgba(0, 0, 0, 0.1); overflow: hidden`

**Observed:** A single isolated object fills the active square. Two neighboring squares overlap behind it, reduced to 201px and backed with exhibit gray. The large object-name line below tracks the active item.

**Transfer:** Use tangible outputs or illustrated product objects, keeping the center card dominant and side cards partially hidden.

### Credit strip

**Use:** Restrained final line below the closing exhibit.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 60px; padding: 16px 144px; background: #110000; color: #fdfbee; border-top: 0.5px solid rgba(253, 251, 238, 0.25)`

**Text style:** `credit` — Die Grotesk A 400 · 12px/1.1 · tracking -0.02em · uppercase

**Observed:** One centered uppercase credit, not a multi-column sitemap.

**Transfer:** Use a short ownership or production credit appropriate to the new project.

### Proof bar

**Only for:** urgent quantitative proof

**Use:** Simple quantified argument on a dark field.

**CSS:** `position: relative; width: 305px; height: 181px; background: #920000; overflow: hidden`

**Text style:** `stat` — Die Grotesk D 700 · 48px/0.92

**Observed:** Square-corner bars share a bottom baseline. Three examples rise from 181px to 271px to 325px and brighten from deep to strong red. Black numerals sit at the top left with 24px inset; short cream captions sit below, with selected consequence words in alert red.

**Transfer:** Base height relationships on real values; retain the ascending intensity and unrounded bar construction.

## Imagery and graphics

### Monochrome cinematic portrait

**Use:** Opening media stage below the headline and support copy.

**Observed:** A tightly framed black-and-white human face fills a wide rounded preview. The visible upper frame emphasizes eyes and skin texture; the image has deep contrast and a faint diffuse halo against the dark field. It spans roughly 1150px at desktop and carries a central play capsule farther down.

**Transfer:** Use a similarly intimate human or product-detail film still with strong texture and monochrome grading. A single excellent still is the minimum acceptable substitute for film; keep it wide and dramatically framed.

**Build:** Place the image in a 24px-radius overflow-hidden frame. Behind it duplicate the image, enlarge it slightly, apply blur around 40px and low opacity, and mask the duplicate to a soft edge so the halo borrows the media's color rather than becoming a bright decorative glow.

### Painted object collection

**Use:** Illustrated overview, capability chapters and closing object cards.

**Observed:** Recognizable foods and packages are individually painted with visible tonal texture, natural saturated color, soft contact shadows and no drawn outline. They overlap as a coherent collection on ivory: first an inverted triangular overview, then enormous cropped closeups around a small left text column. The objects occupy the majority of the visual field and extend off the right edge.

**Transfer:** Commission or assemble painterly isolated objects representing the product's inputs, outputs or tools. For a digital product, illustrate a few physical metaphors or output artifacts rather than inserting a generic dashboard. Minimum version: three consistent cutout objects with tactile texture, distinct scales and shared soft grounding shadows.

**Build:** Use separate transparent image layers for each object; group them into a wide cluster with larger objects at the back and smaller objects toward the base. Keep the ivory backing flat. Add low-opacity brown-black elliptical contact shadows beneath the objects, blurred 8px–16px; do not add rectangular photo backgrounds. Reuse these same object layers at larger scale in feature chapters and singly in the closing carousel.

### Editorial artifact stack

**Use:** Resource or supporting-materials chapter.

**Observed:** Tall document covers with large stacked grotesk titles become physical objects, about 285px wide. Ivory, dark and green covers rotate slightly and overlap vertically with soft edge shadows; the explanatory column stays visually stable beside the moving stack.

**Transfer:** Turn reports, guides, templates or product outputs into designed covers. Keep cover interiors as artwork, not a separate marketing palette or UI system.

**Build:** Create portrait cover images with oversized flush-left typography and small corner metadata. Put them in rounded wrappers, use the document-cover shadow, offset their vertical positions and alternate shallow rotations so the stack feels handled rather than perfectly tiled.

### Closing object triptych

**Use:** The signature end-of-page exhibit.

**Observed:** Three clean square cards overlap on dark brown black; the full-size central white card reveals a textured isolated object while smaller pale-gray cards peek out on both sides. Giant cream text above and below turns the object into a readable sentence.

**Transfer:** Preserve the sentence-plus-object construction with the new product's recognizable outputs. When objects are unavailable, design three illustrated editorial artifacts rather than empty cards.

**Build:** Center a 300px square with 24px radius and padding. Place two equivalent cards behind it at scale 0.67 and offsets roughly 190px to either side, with lower stacking order. Use the exhibit-card shadow and a short 144px display phrase above, plus an equally large active-item name below.

### Icons

**Observed:** Tiny filled dark arrows at 12px in actions and 14px at FAQ row ends; the play glyph is 20px inside a white 48px circle. Proof rows use larger green checks. Navigation uses 8px circular dots rather than pictograms.

**Transfer:** Use simple arrows, play and check marks only where they communicate an action or verified outcome. Preserve the small action-arrow scale instead of adding a large decorative icon library.

## Section recipes

How recurring sections are built.

### First screen: Dark poster opening

**Observed:** A narrow 41px attribution strip precedes the dark poster. The headline is a centered two-line 170px/0.86 declaration, roughly half the viewport width; the shorter second line tucks directly under the first. A compact 21px/1.1 supporting paragraph sits below in a 600px measure. Layers are brown-black canvas, centered ivory type, soft media halo, then a wide 24px-radius monochrome film preview. Within the first 900px the full headline and support are visible and the upper part of the media enters from below; the centered Media play capsule lies farther down in the media, not alongside the headline. Floating chapter navigation does not compete with the initial poster.

**Transfer:** Write a two-line declarative promise and use one cinematic human or material closeup as the anchor. Without film, use a tightly framed monochrome still with texture and the same wide staging. Utility-oriented pages can open with a 44px heading and compact text column, but retain the warm surfaces and bold grotesk hierarchy.

**Avoid:** Do not replace this with a conventional left headline/right dashboard hero, a pair of immediate CTA buttons, or a full-screen background photo behind the text.

**Text style:** `display` — Die Grotesk D 700 · 170px/0.86 · tracking 0px

### Urgent proof chart

**Observed:** Dark manifesto surface, a small Eyebrow above a two-line Declaration, with 16px between them. An 80px pause leads into the three-column Proof grid. Proof bars share a baseline, with captions 16px beneath them.

**Transfer:** Use a few truthful metrics and color intensity to make the argument visible. Keep this concentrated quantitative device in the chapter where urgency belongs.

**Text style:** `declaration` — Die Grotesk D 700 · 96px/0.95

### Monumental reading passage

**Observed:** Centered 96px/0.96 prose in a measure near 1076px, broken into large balanced lines. Words progress from muted rose gray to cream on dark fields, or from subdued ink to full ink on sand. The passage is its own visual scene rather than body copy beneath a heading.

**Transfer:** Use one concise high-stakes statement that rewards sequential reading. Retain a fully readable settled state even when the reveal is not animated.

**Text style:** `reading-statement` — Die Grotesk D 700 · 96px/0.96

### Illustrated overview and closeup

**Observed:** Inset illustration sheet opens with a 154.8px chapter display and a centered inverted-triangle collection of painted objects. Subsequent closeup chapters use a 360px-wide Feature copy column, 44px headings, 32px heading-to-copy gap and small bold target labels. Artwork becomes much larger than the text column and continues off the right edge.

**Transfer:** Show a compact collection to explain the whole, then reuse its objects at enlarged scale to explain parts. Keep explanatory labels short and the same painted material language throughout.

**Text style:** `chapter-display` — Die Grotesk D 700 · 154.8px/0.84 · tracking 0px

### Artifact library

**Observed:** Ivory canvas with Resource split: a 44px Utility heading, compact paragraph, Secondary button and underlined Download rows on the left; the Editorial artifact stack on the right. The left content remains steady as the artifacts move and overlap.

**Transfer:** Use for material that makes the product credible or useful: reports, templates, guides or sample outputs. Design those materials as physical editorial objects rather than a row of generic thumbnails.

**Text style:** `utility-heading` — Die Grotesk D 700 · 44px/1.04

### Outcomes and reassurance

**Observed:** Sand band with a centered 96px heading, narrow 21px support and the Raised proof panel below. Elsewhere in the same field, a left-aligned 44px FAQ heading leads to the wide FAQ rows after a 100px pause.

**Transfer:** Move from broad claims to verified outcomes and clear answers. Use one checklist card and wide calm accordions rather than a dense collection of unrelated cards.

**Text style:** `declaration` — Die Grotesk D 700 · 96px/0.95

### Conversion clearing

**Observed:** A 900px-tall sand field centers the 115.2px two-line Closing call, a 528px-wide support paragraph and Primary button. The main stack uses 32px gaps with extra separation before the button and generous empty space around the group.

**Transfer:** Make one short invitation, explain participation in one paragraph and offer one decisive action. Let the light field and typography do the work.

**Text style:** `closing-call` — Die Grotesk D 700 · 115.2px/0.95 · tracking 0px

### Collectible closing exhibit

**Observed:** A dark chapter follows the conversion clearing, with an Exhibit display phrase above the Closing object triptych and a changing object name below. The central card is 300px square and the side cards 201px; 144px cream display type gives the composition a poster-like ending. A 60px Credit strip separated by a faint hairline is the final element.

**Transfer:** End with a memorable tangible expression of the promise, not another sales paragraph. Preserve the large phrase/object/name relationship and minimal final credit, whether the illustrated items are products, tools or outputs.

**Text style:** `exhibit-display` — Die Grotesk D 700 · 144px/0.956

## Page flow

**Storyline:** declarative promise → stakes and quantified proof → reframing statement → illustrated explanation → useful artifacts → outcomes and objections → invitation → memorable object exhibit

### A persuasive long-form campaign or mission-led product landing page

1. **Promise** — Dark centered poster and cinematic media preview.
2. **Quantified stakes** — A small label, enormous two-line claim and three ascending red bars.
3. **Reframing** — A contextual image and large reading passages establish the change in direction.
4. **Product explanation** — Light sheet transition into an object collection, followed by enlarged illustrated feature chapters.
5. **Practical credibility** — A stable resource column paired with a moving stack of designed artifacts.
6. **Outcome proof** — A centered heading and narrow checklist panel on the sand field.
7. **Objection handling** — Wide pill-shaped FAQ rows followed by a large manifesto recap.
8. **Closing call** — Spacious sand clearing with one capsule action.
9. **Brand memory** — Dark object-card exhibit and minimal credit strip.

**Transfer:** Adapt the narrative length to the product. Retain the shifts between dark conviction, ivory demonstration and sand reassurance, along with the large reading device and object-based ending; combine or rearrange blocks to fit the available argument.

## Writing

Confident, declarative and public-minded. The language moves from blunt stakes to plain explanations and ends with a collective invitation, rather than sounding playful or technically ornate.

**Do not copy:** Do not reuse government attribution, flags, agency seals, political endorsements, institutional affiliations, brand slogans, food-policy claims, health statistics, artwork or source-specific promises. Replace all facts and examples with claims the new product can substantiate. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Uses collective we for commitments and occasional direct imperatives for the reader; explanations often use impersonal factual sentences. The closing invitation asks people to participate in a shared outcome.
- **Rhythm:** Opening claims are very short, often three to seven words. Paired sentences use contrast and repetition. Supporting paragraphs are compact and information-dense; buttons stay at two to five words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A short noun phrase plus an unqualified outcome verb. | 3–5 words | “[Brand] Wins” |
| Stakes heading | Two blunt sentences: a problem followed by a statement of clarity. | 6–10 words | “America is sick. The data is clear.” |
| Explanatory copy | A clear principle followed by its contrast; concrete nouns instead of abstraction. | 2–4 sentences | “Whole grains are encouraged. Refined carbohydrates are not.” |
| Closing call | Repeat a compact imperative, then invite people to extend its impact. | 5–9 words | “Eat [Brand]. Spread the Word.” |
| Action | Plain verb-led label naming the next step. | 2–5 words | “Get Involved”<br>“Watch the press release” |
| Question | The reader's practical question written without marketing flourish. | 4–12 words | “Why does this matter?” |

**Words and phrasing to use:** simple; clear; real; whole; prioritize; results; guidance; choose; partner with us

**Avoid:** revolutionary platform; unlock limitless potential; seamlessly leverage; delightful magic; next-generation ecosystem

**Rules:**

- Make the headline a claim that can stand alone in enormous type.
- Support urgent statements with specific, attributable proof rather than rhetorical escalation.
- Use repeated sentence structures to give the long reading passages cadence.
- Separate the promise, explanation and action instead of forcing them into every paragraph.
- Name downloadable artifacts and actions literally.

## Do's and Don'ts

### Do

- Keep opening display type at 700 with 0.86 leading and deliberately balanced line breaks.
- Use the 1076px content measure and 144px desktop outer padding for utility sections.
- Keep explanatory copy near 360px wide while its painted objects dominate the field.
- Reserve the red ramp for one concentrated quantitative argument.
- Use 60px capsule actions with 40px radii rather than angular controls.
- Make the 96px reading passage a visual chapter, not a long paragraph styled as body copy.
- Repeat the same painted objects across the overview, closeups and closing exhibit.
- Keep the final credit to one centered 12px uppercase line beneath a subtle rule.

### Don't

- Do not use pure black as the large dark canvas; preserve the warm #110000 brown-black.
- Do not turn the ivory canvas into a gray dashboard background or a heavily textured paper effect.
- Do not spread translucent glass across cards and content panels; it belongs to the compact navigator and media control.
- Do not round the red proof bars to match the capsule actions.
- Do not enlarge body text to 24px throughout; the explanatory chapters depend on compact 16px text beside enormous objects.
- Do not give every feature an identical rectangular image card; the illustrated field relies on cutouts, overlap and edge overflow.
- Do not add letter spacing to the bold display scale; open tracking is reserved for the small institutional mono label.
- Do not replace the minimal credit strip with a dense multi-column sitemap after the object exhibit.

## Motion and responsive

### Motion

**Observed:**

- The chapter navigator changes its current text label while other sections are represented by dots.
- Large reading passages use sequential contrast changes; some transition moments include blur.
- Declared media-control transition: transform 0.2s, background 0.2s; hover scale(1.05).
- Declared primary-action transition: background-color 0.2s cubic-bezier(0.23, 1, 0.32, 1), color 0.2s cubic-bezier(0.23, 1, 0.32, 1).
- Declared FAQ answer transition: grid-template-rows 0.12s cubic-bezier(0.2, 0.8, 0.4, 1).
- Resource content uses a sticky viewport-height stage while portrait artifacts change stacking and position.

**Transfer:**

- Use scroll progress to move emphasis through the monumental passage and update the compact chapter pill.
- Let the artifact stack and closing carousel animate the same objects used elsewhere, rather than introducing unrelated effects.
- Keep blurred words as a transition only; the settled statement must be readable.

**Unknown:**

- Exact scroll interpolation, reveal durations, carousel cadence and timing of chapter activation are not established.

### Responsive

**Observed:**

- The illustrated overview heading uses 10.75vw; the conversion heading uses clamp(48px, 8vw, 120px).
- Styles include width breakpoints at 768px, 1024px and 1280px among many component-specific breakpoints.

**Transfer:**

- On narrow screens, retain the centered poster and line hierarchy while reducing display size to avoid horizontal text clipping.
- Stack short explanatory copy above the object collection; preserve deliberate object overlap without letting artwork obscure the paragraph.
- Keep the current-label-and-dots navigator compact and centered; do not expand it into a persistent full-width link row.
- Scale the central and side exhibit cards together so their overlapping hierarchy survives.

**Unknown:**

- Mobile layouts, actual narrow-screen type sizes and behavior of the sticky illustration and resource scenes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
