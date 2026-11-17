# NaN — acid-green typographic playground

## Overview

An exuberant, workshop-like style where tiny monospaced controls sit beside enormous, unruly letterforms. Pale green carries most of the experience, with charcoal ink, electric green marks and small candy-colored gradient actions. It suits creative tools, design-led products and portfolios that can demonstrate their craft through specimens, moving graphics and real-world applications; the composition is dense in detail but expansive in scale.

### Essentials

- A statement becomes a scribbled notice rather than a conventional hero: 45px/1.2 light mono across nearly the full width, over an oversized electric-green line drawing, beneath a 48px navigation strip.
- Type is the main product object: contrast 216px/1 black grotesk specimens with 12px/1.5 mono controls and 24px/1.5 light mono chapter labels. Include a monumental word specimen even when the product is not a font; use a short product benefit as the material.
- Green is the paper, not just the accent: #b7ffb4 covers the continuous main page, #262626 supplies text and 1px rules, and #00ff00 is reserved for scribbles, small identifiers and focused demonstration panels. White is concentrated in the signup band and scoped proof cards; charcoal closes the page.
- Actions look like candy strips beside utilitarian equipment: the default centered action is 459×35px with 18px corners, a pink–lilac–blue gradient and 14.4px uppercase heavy mono. Signup uses the taller 63px, 29.4px-radius variant.
- Demonstrations occupy the page rather than floating above it: media spans 1392px inside 24px side gutters, or pairs in 686px columns with 20px gutters. Pair a polished application with a raw specimen; if no photography exists, stage a product diagram or word sculpture on a flat saturated backing.
- Keep the handmade interruptions and the lived-in ending: an electric-green ASCII ribbon, uneven SVG doodles around the signup field, then a charcoal directory with 13px mono links and a 315×236px workshop-view image. Use original line art and a real working-environment photograph for new content.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale acid green | `#b7ffb4` | `--color-canvas` | background, surface, text | Continuous marketing canvas and reversed footer text. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric green | `#00ff00` | `--color-electric` | accent, action, background | Handmade marks, logo tab, ASCII ribbon, action hover and occasional concentrated demonstration backing. |
| Candy blue | `#a2d1ff` | `--color-candy-blue` | action | Intermediate action-gradient stop; not a general section color. |
| Candy pink | `#ffa3b6` | `--color-candy-pink` | action | Repeating end stop of the action gradient. |
| Candy lilac | `#dda9ff` | `--color-candy-lilac` | action | Intermediate action-gradient stop. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#262626` | `--color-ink` | text, border, background | Primary text, hairline outlines, selected controls and the footer canvas. |
| Footer gray | `#999999` | `--color-muted` | text | Low-priority footer copyright and micro-signature. |
| Button undercoat | `#efefef` | `--color-button-base` | surface | Neutral undercoat beneath the large gradient signup button. |
| Signup white | `#ffffff` | `--color-white` | background, surface | Full-width signup band and feature-comparison cards. |

## Typography

- **NaN Holo Mono** — Opening statement, section labels, project names, navigation, buttons, captions and footer directories. Open, eccentric monospace with a conspicuously light editorial cut and chunky heavy labels. OpenType features: "dlig" 0, "liga" 0. If unavailable, use **Space Mono**. Use regular for the light roles and bold for heavy labels; preserve the generous character width. Font stack: "NaN Holo Mono", "Space Mono", ui-monospace, monospace.
- **NaN Holo** — Body copy and proportional editorial passages. Warm geometric grotesk with rounded details; plain regular text balances the display experiments. If unavailable, use **DM Sans**. Font stack: "NaN Holo", "DM Sans", Arial, sans-serif.
- **NaNGothicBigStandardBlackPREVIEW** — Oversized word specimens, not navigation or body copy. Compact grotesk with a very large x-height and heavy, tightly packed black cut. If unavailable, use **Archivo**. Use weight 900 for monumental specimens and 500 for detail demonstrations. Font stack: "NaNGothicBigStandardBlackPREVIEW", "Archivo", Arial, sans-serif.
- **NaNGothicBigStandardMediumPREVIEW** (only for product detail demonstrations) — Centered feature-comparison specimens. Medium-weight compact grotesk used to make small shape differences legible. If unavailable, use **Archivo**. Use weight 500. Font stack: "NaNGothicBigStandardMediumPREVIEW", "Archivo", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental-specimen | NaNGothicBigStandardBlackPREVIEW | 900 | 216px | 1 | normal | Short word sculpture or interactive product specimen occupying most of a screen. |
| opening-statement | NaN Holo Mono | 300 | 45px | 1.2 | normal | Full-width, three-line opening statement; light and conversational rather than slogan-like. |
| project-title | NaN Holo Mono | 900 | 32px | 1.2 | normal | Compact bold names above media or at the left of an explanatory split. |
| project-support | NaN Holo Mono | 400 | 32px | 1.2 | normal | Large supporting explanation beside a project title. |
| section-label | NaN Holo Mono | 300 | 24px | 1.5 | normal | Chapter labels in ruled section bars. |
| signup-action | NaN Holo Mono | 400 | 19.6px | 3 | normal | Tall signup or download button. |
| body | NaN Holo | 400 | 16px | 1.5 | normal | Descriptions, signup invitation and ordinary reading copy. |
| strip-action | NaN Holo Mono | 800 | 14.4px | 2.25 | normal, uppercase | Default gradient action and smaller electric-green editorial actions. |
| caption | NaN Holo Mono | 400 | 13px | 1.5 | normal | Media credits, inline links and footer lists. |
| navigation | NaN Holo Mono | 500 | 12px | 48px | 0.075em, uppercase | Small centered links in the persistent top strip. |
| control-label | NaN Holo Mono | 400 | 12px | 1.5 | normal | Specimen control labels and fine metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product detail demonstrations | detail-specimen | NaNGothicBigStandardMediumPREVIEW | 500 | 72px | 1.5 | normal, features "calt" 0, "dlig" 0, "liga" 0, "salt" 0 | Centered demonstration inside a white comparison card. |
| company introductions | studio-lead | NaN Holo | 300 | 48px | 1.1 | normal | Full-width editorial introduction below the opening label. |
| case studies | case-lead | NaN Holo | 400 | 32px | 1.2 | normal | Broad introductory paragraphs and occasional narrative interludes. |
| product detail demonstrations | detail-caption | NaN Holo Mono | 400 | 13px | 1 | normal | Centered bottom caption inside the white comparison card. |

**Notes:**

- Most type uses normal tracking. The deliberately spaced navigation is an exception; do not apply its uppercase tracking to paragraph text.
- Scale contrast matters more than a long conventional heading ladder: light mono statement, tiny controls, then a huge black specimen.
- Display specimens can use different widths, slants and weights to expose the product's character. Keep the interface typography stable while the specimen changes.
- A variable-word demonstration uses a 144px size with a 10vw scaling rule and a 1.8 line height; treat this as a dedicated demonstration treatment rather than the general headline scale.

## Layout

**Density:** Comfortable at the chapter level, compact inside controls and directories; giant specimens provide the visual expansion.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Small block inset and half-gutter within column wrappers. |
| 16px | Card content inset and paragraph separation. |
| 20px | Column gutters and the gap below ruled section bars. |
| 24px | Main page side gutters. |
| 32px | Gap before centered action strips and specimen content padding. |
| 40px | Chapter-label top margin and editorial section separation. |
| 60px | Signup and footer inner padding. |
| 80px | Breathing room after a conversion strip and before the shared signup ending. |

### Containers and grids

- **main-canvas**: max width 1440px · side padding 24px. Nearly full-bleed composition with 1392px of usable width at desktop.
- **three-column-gallery**: 3 columns · gap 20px. Equal 451px-wide cards within the main canvas.
- **two-column-media**: 2 columns · gap 20px. Equal 686px-wide application images or videos.
- **editorial-split**: 3 columns · gap 20px. One 451px text column beside 921px of media, or a compact title beside a wide explanation.
- **top-menu**: max width 648px. Centered horizontal navigation between the left logo tab and right account utilities.
- **footer-directory**: 4 columns · gap 20px · side padding 60px. Four narrow 173px directory columns on the left; a separate workshop-view module sits at the far right.

## Corner radius

| Element | Radius |
| --- | --- |
| outlined-tiles | 20px |
| strip-actions | 18px |
| signup-actions | 29.4px |
| specimen-controls | 2px |

## Surfaces and depth

### Surfaces

#### Green paper · level 0

**Use:** Default marketing page canvas.

**CSS:** `background: #b7ffb4; color: #262626`

**Observed:** One uninterrupted colored sheet carries labels, text, demonstrations and transparent outlined tiles.

**Transfer:** Let the common canvas connect unlike media instead of alternating generic background bands.

#### Outline tile · level 1

**Use:** Collections and related-product choices.

**CSS:** `background: transparent; border: 1px solid #262626; border-radius: 20px; box-shadow: none`

**Observed:** The green sheet remains visible inside; the outline is as dark as the text.

**Transfer:** Use an oversized product name or an expressive diagram, with a small count pinned low.

#### White signup band · level 0

**Use:** Shared closing signup invitation.

**CSS:** `background: #ffffff`

**Observed:** A full-width 283px band interrupts the green before the charcoal directory.

**Transfer:** Keep this ending visibly distinct from all main-page content.

#### Charcoal directory · level 0

**Use:** Shared footer.

**CSS:** `background: #262626; color: #b7ffb4; padding: 60px`

**Observed:** Flat and shadowless; a tall directory is balanced by a small live-workspace view, with gray metadata near the bottom.

**Transfer:** Retain the combination of information density and a personal workshop glimpse.

#### White proof panel · level 1

**Only for:** product detail demonstrations

**Use:** Close-up comparison or feature proof.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 16px; box-shadow: none`

**Observed:** White, borderless panels contrast with the surrounding green and center one example above a caption.

**Transfer:** Show one concrete change per panel, not a generic icon and benefit paragraph.

## Components

### Top navigation

**Use:** Persistent orientation across page types.

**CSS:** `position: sticky; top: 0px; height: 48px; display: flex; justify-content: space-between; padding-left: 80px; background-image: linear-gradient(#b7ffb4 80%, rgba(183, 255, 180, 0) 100%)`

**Text style:** `navigation` — NaN Holo Mono 500 · 12px/48px · tracking 0.075em · uppercase

**Observed:** A compact centered menu, logo tab at the far left and account/cart controls plus tiny theme dots at the far right. The current category has a short underline.

### Logo tab

**Use:** Brand anchor at the top-left edge.

**CSS:** `background: #00ff00; color: #262626; height: 48px; padding: 14.3px 24px 0px; position: absolute`

**Observed:** A hard-edged electric-green rectangle carries a short, black heavy wordmark; it is not a pill.

**Transfer:** Use a short original wordmark or monogram in the same compact tab.

### Section bar

**Use:** Introduce each chapter and expose a secondary destination.

**CSS:** `display: flex; justify-content: space-between; align-items: baseline; border-bottom: 1px solid #262626; margin-top: 40px; margin-bottom: 20px`

**Text style:** `section-label` — NaN Holo Mono 300 · 24px/1.5

**Observed:** A tiny outlined smiley precedes the light left label. A small mono destination and arrow can sit at the right edge.

### Gradient strip action

**Use:** Default main-page action below a demonstration or gallery.

**CSS:** `background-image: linear-gradient(270deg, #ffa3b6, #dda9ff 33%, #a2d1ff 66%, #ffa3b6); background-size: 200% 200%; color: #262626; border-radius: 18px; padding: 2.9px 28.8px 0px; width: 459px; height: 35px; text-align: center`

**Text style:** `strip-action` — NaN Holo Mono 800 · 14.4px/2.25 · uppercase

**Observed:** Centered as a thin horizontal strip rather than attached to the text column. Editorial read-more variants use a shorter electric-green pill.

**States:** Declared: hover background lime and color #262626, with a 1px solid bottom border; focus-visible styling is unknown.

### Signup action

**Use:** Conversion inside the shared white signup band and selected download offers.

**CSS:** `background-color: #efefef; background-image: linear-gradient(270deg, #ffa3b6, #dda9ff 33%, #a2d1ff 66%, #ffa3b6); background-size: 200% 200%; color: #262626; border-radius: 29.4px; padding: 3.9px 49px 0px; height: 63px`

**Text style:** `signup-action` — NaN Holo Mono 400 · 19.6px/3

**Observed:** A taller, regular-weight pill sits beside the scribbled input. Loose green arrow strokes point toward it.

**States:** Declared: hover background lime and color #262626; focus-visible styling is unknown.

### Outlined product tile

**Use:** Browse related items or a compact collection.

**CSS:** `position: relative; border: 1px solid #262626; border-radius: 20px; height: 340px; overflow: hidden`

**Observed:** An expressive product name occupies the upper-left with 16px inner inset; a 12px count sits at the lower-left. The whole surface is a link. Names can wrap over two or three lines and vary in width and slant.

**Transfer:** Replace the font sample with a product-specific word mark or simple expressive diagram; preserve the empty lower field and corner metadata.

### Dotted text link

**Use:** Inline metadata, credits and contextual navigation.

**CSS:** `color: #262626; border-bottom: 1px dotted #262626`

**Text style:** `caption` — NaN Holo Mono 400 · 13px/1.5

**Observed:** No filled container or icon badge; the underline is the affordance.

**States:** Declared: hover changes the bottom border to 1px solid #262626; focus-visible styling is unknown.

### Specimen alignment control

**Use:** Small grouped tools above a live demonstration.

**CSS:** `background-color: #262626; color: #b7ffb4; border: 1px solid #262626; border-radius: 2px 0px 0px 2px; width: 30px; height: 27px; padding: 1.5px 7.5px 1px`

**Observed:** Selected alignment is reversed; adjoining unselected cells retain the green canvas. Small glyphs depict text alignment, with neighboring selectors, sliders and an OT toggle.

**States:** Declared: hover background #262626 and color #b7ffb4; focus-visible styling is unknown.

**Transfer:** Expose a small meaningful product adjustment using the same utilitarian construction, rather than copying a font-specific control.

### Scribble email input

**Use:** Email entry in the closing signup invitation.

**CSS:** `background-color: #ffffff; width: 340px; height: 82px; padding: 29.4px 17px 29.4px 34px`

**Text style:** `caption` — NaN Holo Mono 400 · 13px/1.5

**Observed:** The field is surrounded by an irregular electric-green oval drawn independently of the input, not a standard rounded border. A small floating off-white pebble adds a playful accent.

**Transfer:** Use a real accessible input under a pointer-events-none SVG oval.

### Footer directory

**Use:** Dense final navigation and human proof.

**CSS:** `background-color: #262626; color: #b7ffb4; padding: 60px`

**Text style:** `caption` — NaN Holo Mono 400 · 13px/1.5

**Observed:** Uppercase bold group labels sit over ordinary mono links. Four narrow columns cluster left, while a workspace image and green status dot sit right. Copyright and a tiny hand-drawn signature anchor the bottom.

**States:** Declared: footer links turn lime on hover; focus-visible styling is unknown.

### Detail comparison card

**Only for:** product detail demonstrations

**Use:** Explain a small but meaningful product difference.

**CSS:** `background-color: #ffffff; border-radius: 20px; height: 288px; padding: 16px; display: flex; flex-direction: column; justify-content: center; align-items: center; overflow: hidden`

**Text style:** `detail-specimen` — NaNGothicBigStandardMediumPREVIEW 500 · 72px/1.5

**Observed:** A single prominent example is centered with the detail-caption pinned near the bottom. Rows alternate equal thirds and equal halves.

**Transfer:** Use enlarged before/after details, a product setting or a tiny working example; keep the label short.

## Imagery and graphics

### Oversized green scribble

**Use:** Opening backdrop and recurring handmade accents.

**Observed:** A thin, bright-green, irregular geometric word drawing spans almost the whole opening width behind the dark statement. Angular peaks and triangles extend beyond the text block; the stroke has a slight soft halo rather than a polished vector-logo finish.

**Transfer:** Draw an original geometric shorthand for the new product behind its opening statement. The minimum version is three or four connected angular strokes with deliberately uneven proportions.

**Build:** Use an absolutely positioned SVG behind the text, spanning the content width and about 291px tall. Draw open polylines with no fill and a 3px #00ff00 stroke; duplicate beneath with a 3px Gaussian blur at 0.35 opacity. Keep readable text above it and allow the drawing to extend below the statement.

### Monumental word specimen

**Use:** Signature product demonstration.

**Observed:** Huge charcoal letters on the pale-green canvas, often wrapping a very short phrase into abrupt lines. A tiny control row above heightens the contrast between interface and specimen; there is no hero card behind it.

**Transfer:** Make a short benefit or product behavior into the visual object. Minimum version: an original two-to-four-word phrase at 216px with compact black grotesk construction, plus one useful interactive adjustment.

**Build:** Place editable or selectable display text in a full-width overflow-hidden region. Set the monumental-specimen recipe and keep 32px vertical padding; put compact mono labels, hairline range tracks and grouped 27px controls above it.

### ASCII ribbon

**Use:** Signature transition between major content chapters.

**Observed:** An 86px-high edge-to-edge ribbon repeats green monospaced slash, underscore and bracket constructions, with letter-spaced words woven into the pattern.

**Transfer:** Encode a short original product phrase in a repeatable text pattern rather than substituting a standard logo marquee.

**Build:** Use a preformatted four-line tile in 14.4px mono with 21.6px line height and #00ff00 text; combine underscores, diagonal slashes, parentheses and vertical bars. Repeat tiles horizontally inside an overflow-hidden full-width track.

### Application showcase

**Use:** Polished visual proof and case-study media.

**Observed:** Large square-edged photographs, specimen boards, campaign compositions and moving demonstrations occupy most of a screen. Typical stages are 1392×783px or paired 686×858px portraits. Embedded client palettes remain local to their artwork; selected main promotional media has a softly deforming lower silhouette.

**Transfer:** Show the product functioning at real scale: a physical application, a working screen, a diagram or a simple rendered object. Keep its own palette inside the media rectangle, with green gutters outside.

### Electric object stage

**Use:** Focused promotional proof within the main green page.

**Observed:** A pale wireframe-and-halftone globe or a halftone bag floats on an electric-green field. Black-and-white labels sit around the object; the image's lower edge bends into a shallow wave.

**Transfer:** Stage an original product-relevant object with a restrained monochrome treatment on the same saturated field. Minimum version is a clean outlined SVG diagram with several white labels and black annotation tags.

**Build:** Create a #00ff00 media backing, center a white-and-charcoal object over it, overlay a fine dot texture clipped to the object's silhouette, then place small outlined white labels and dark caption pills around it. Use an SVG clip path with rounded lower corners and a shallow central wave; retain a straight upper edge.

### Signup doodles

**Use:** Handmade detail around the closing action.

**Observed:** An uneven green oval encircles the email field and three short arrow-like strokes point toward the gradient button. A small softly shaded off-white pebble floats above the form.

**Transfer:** Use sparse original annotation marks to make the otherwise practical form feel hand-touched.

**Build:** Overlay a no-fill SVG oval using a 1px electric-green stroke, with an offset partial second stroke near the top. Draw three two-segment chevrons around the action. Add one small vertically oval neutral object with a soft radial shading; keep it subordinate to the field.

### Workspace view

**Use:** Humanizing proof in the footer.

**Observed:** A small, slightly low-resolution overhead image of a cluttered working studio appears at the far right, labeled as a live feed and accompanied by an electric-green status dot.

**Transfer:** Use a genuine working-environment view, not stock team photography. If live video is unavailable, use an honest still and label it as such.

### Studio character portraits

**Only for:** team and company pages

**Use:** People grid.

**Observed:** Six narrow portrait columns use whimsical neon-green caricatures instead of conventional headshots, with grainy peach, yellow and green grounds. Names, roles and dense biographies sit directly below.

**Transfer:** Commission original illustrated portraits with a consistent limited palette and visible texture; keep the six-column editorial rhythm at desktop rather than turning them into generic white profile cards.

### Icons

**Observed:** Icons are functional and tiny: simple text-alignment glyphs at 15px inside 30×27px controls, outlined smileys beside chapter labels, small arrows on destination links and 10px theme dots. They use charcoal or reversed pale green.

**Transfer:** Choose minimal line or solid utility symbols with the same visual size; keep playful drawing separate from the functional icon set.

## Section recipes

How recurring sections are built.

### First screen: Statement and specimen opening

**Observed:** Green paper fills the screen beneath Top navigation. The opening-statement spans almost all 1392px of the content width, wrapping into three lines within a roughly 202px-high block. Oversized green scribble sits behind it and extends below it. A Section bar follows, then a tiny demonstration toolbar and a monumental-specimen aligned left. Within the first 900px, the reader sees the complete statement, chapter label, controls and the first two enormous specimen lines; the final specimen line and collection tiles continue below. The opening has no conventional pair of hero CTA buttons; the first large conversion strip appears after the specimen and tiles.

**Transfer:** Use a full-sentence product introduction above a dramatic original word specimen, maintaining the small-interface/huge-object contrast even without source artwork. Company pages open with a short playful mono title and a broad proportional introduction; case studies use a short title then a near-full-screen application stage; detailed product pages can open with a full-screen specimen slideshow before explanatory text.

**Avoid:** Do not turn this into a centered SaaS slogan with two buttons and a floating dashboard, or shrink the specimen to fit every element above the fold.

**Text style:** `opening-statement` — NaN Holo Mono 300 · 45px/1.2

### Ruled chapter gateway

**Observed:** Section bar pairs a 24px light mono left label and small right-side destination over a single dark hairline, with 20px to the following block.

**Transfer:** Name a useful chapter such as latest release, practical proof or product details; keep its destination terse.

### Collection and action

**Observed:** Outlined product tile appears in three equal columns with 20px gutters, followed after 32px by Gradient strip action. More chapters can follow after an 80px release of space.

**Transfer:** Group comparable items without adding pictogram badges or long card paragraphs.

### Large demonstration with split explanation

**Observed:** Application showcase spans the full main canvas. Below it, project-title occupies the left third and project-support the right two thirds. A centered Gradient strip action can complete the unit.

**Transfer:** Let a working example carry the proof; use the split text to explain the result, not repeat everything visible in the media.

### Editorial story feature

**Observed:** A Section bar introduces a 32px heavy title. A narrow column of 16px description and electric-green read-more action sits beside a 921px-wide media stage; the left/right placement can reverse.

**Transfer:** Use for a process story, opinion, release explanation or special offer while keeping image and text visibly unequal.

### Detail laboratory

**Observed:** White proof panel and Detail comparison card alternate rows of thirds and halves. Each holds one enlarged example with a tiny bottom caption; surrounding paragraphs and long specimens remain directly on green.

**Transfer:** Use the white treatment only for isolated comparisons or proof, not for the whole landing-page feature grid.

### Case-study visual essay

**Observed:** A short mono title precedes a wide application stage. A one-third/two-thirds introduction uses a heavy category label and 32px proportional copy. Full-width 16:9 media alternates with paired portrait applications, interrupted by very few explanatory passages. Compact production credits precede the shared ending.

**Transfer:** Demonstrate the work through distinct scales and real applications; keep client-specific colors inside media and avoid restyling the marketing shell to match each client.

### Offer or experimental closing insert

**Observed:** A catalog can end its main content with an 8px-radius white offer panel, followed by free-use entries and an electric-green experimental quotation board with a small label and monumental text.

**Transfer:** For catalog or experimental content, add a practical offer or a playful specimen near the close; keep such inserts subordinate to the shared signup and directory ending.

### Handwritten signup and directory ending

**Observed:** After an 80px gap, White signup band spans the viewport: centered invitation at left, Scribble email input in the middle and Signup action at right, with loose annotation marks. Charcoal directory follows immediately, extending 872px with 60px padding. Dense lists cluster left and Workspace view sits right; muted metadata and a tiny green signature finish the bottom.

**Transfer:** Preserve both the playful form and the useful, personal directory. Adapt the directory groups to the new product rather than replacing the entire ending with a giant sales slogan.

## Page flow

**Storyline:** Conversational introduction → tangible specimen → browsable range → application proof → practical explanation or offer → playful signup → workshop-like directory.

### Broad marketing overview with a strong product demonstration

1. **Introduction** — Light mono statement over a green scribble.
2. **Product demonstration** — Huge interactive word specimen, outlined collection tiles and a centered action strip.
3. **Range and proof** — Additional collections, broad application media and split explanatory copy.
4. **Practical reassurance** — Pricing explanation, free sample, real-world gallery and editorial stories.
5. **Closing action** — Special offer, handwritten signup band and charcoal directory.

**Transfer:** Use the specimen-led overview as the default landing-page grammar; select only the proof chapters relevant to the new product.

### Company introduction and collaborator credibility

1. **Introduction** — Playful short title, ruled label and a broad 48px proportional statement.
2. **Context** — Paired early/current work images, contact information and service description.
3. **Human proof** — Six-column illustrated people grid followed by three directory-like contributor and client columns.
4. **Closing action** — Colophon leads into the shared signup and footer.

**Transfer:** Explain a working culture with concrete people, practices and contact details rather than generic values cards.

### Deep visual proof of a commissioned project

1. **Hook** — Short title over a large colorful application stage.
2. **Scope** — Compact category label beside broad introductory paragraphs.
3. **Product demonstration** — A long sequence of full-width and paired application media with occasional narrative interludes.
4. **Attribution** — Small production credits.
5. **Closing action** — Shared signup and charcoal directory.

**Transfer:** Show a project from overview to craft detail to implementation; keep media visually dominant.

### Detailed product evaluation and purchase

1. **Hook** — Full-screen specimen slideshow with subtle slide controls.
2. **Explanation** — About text and three system tiles.
3. **Product demonstration** — Many giant and small live specimens, multilingual examples and variable previews.
4. **Capability proof** — White comparison cards, sample rows and dense style listing.
5. **Conversion** — Trial signup followed by a two-part selection and license form with a persistent dark cart bar.
6. **Continuation** — Related-product tiles precede the shared signup and directory.

**Transfer:** Reserve the extended laboratory and purchase configurator for products that genuinely need hands-on evaluation; do not reproduce the length on a general landing page.

### Browsable product catalog

1. **Introduction** — A light mono description and playful line-art character above a compact product index.
2. **Comparison** — Ruled family labels followed by repeated 126px-high sample rows with 12px metadata and 72px specimens.
3. **Offer** — White special-offer panel, free-use options and an ASCII ribbon.
4. **Personality** — An electric-green experimental text board.
5. **Closing action** — Shared signup and charcoal directory.

**Transfer:** Favor direct comparison and jump links over a sea of identical marketing cards; let each product show its own output.

## Writing

Technically knowledgeable and confidently informal, with conspicuous wordplay and a willingness to be a little silly. Concrete craft and service claims coexist with affectionate, conversational asides.

**Do not copy:** Do not reuse NaN's name, wordmark, typeface names, client identities, illustrations, specimen quotations, pricing, release counts or project claims. Write original examples and use only the new product's verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the makers, you for invitations and offers. Describe the product directly rather than through corporate abstractions.
- **Rhythm:** Short chapter labels and one-to-three-word actions contrast with full-sentence introductions and substantial explanatory paragraphs. Parentheses, em dashes, arrows and occasional playful punctuation are part of the rhythm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | An unhurried sentence that names the practice and reveals its personality, often with an aside or alliterative contrast. | 20–30 words | “[Brand] is an exploratory and service-driven type design practice, creating for (and collaborating with) the weird, the wise and the wonderful ☻” |
| Section label | Plain editorial signposting with a conversational turn rather than a benefit slogan. | 2–7 words | “You Might Have Missed”<br>“How It Started → How It’s Going”<br>“If You Liked X You May Like Y?” |
| Supporting explanation | State what was made, why it matters and the practical scope; specific facts do the persuading. | 1–3 sentences | “Three custom typefaces for the world’s largest marketplace: Amazon.” |
| Primary action | Direct short verbs, with a looser colloquial variant for low-friction downloads. | 1–4 words | “Discover more”<br>“Get it for free”<br>“Gimme” |
| Signup invitation | An honest, gently self-deprecating promise of useful updates and personality. | One sentence | “Join our nantastic mailing list for more fonts, bad puns and typographic curiosities.” |

**Words and phrasing to use:** exploratory; little; curiosities; get in touch; for (and with); plain practical terms; playful contrasts

**Avoid:** revolutionary platform; unlock limitless potential; enterprise-grade everything; relentless superlatives; generic luxury language

**Rules:**

- Let the humor live in one memorable aside or label, while functional choices remain understandable.
- Explain the work with real processes and verified scope; use specific numbers only when meaningful.
- Use short editorial labels to organize long pages instead of making every section a new sales pitch.
- Keep product demonstrations linguistically varied and lively, but make navigational labels unambiguous.

## Do's and Don'ts

### Do

- Keep pale green continuous through the main page and use charcoal for both text and 1px outlines.
- Preserve the 45px light-mono statement versus 216px black-specimen contrast.
- Set desktop content inside 24px gutters and use 20px gaps for paired or tripled media.
- Place 24px light mono chapter labels on dark hairline rules.
- Center the 459×35px gradient action after a major demonstration rather than beside every paragraph.
- Keep outline tiles transparent with 20px corners and small lower-left metadata.
- Use a white 283px signup band and a tall charcoal directory as the shared ending.
- Pair polished application proof with a raw, hands-on specimen and an original handmade annotation.

### Don't

- Do not make the main canvas white and reduce pale green to a button accent.
- Do not apply the candy gradient to headings, whole sections or media backdrops; its role is action surfaces.
- Do not use soft gray card borders in place of the charcoal 1px outlines.
- Do not introduce drop-shadow elevation, glass blur or glossy dashboard cards into the flat page shell.
- Do not make the default CTA a tall black rectangle; black fill belongs to selected tools and the footer.
- Do not standardize all display examples to one width and weight; keep variation inside the demonstrations.
- Do not inflate the 12px navigation into oversized desktop menu labels.
- Do not replace the footer's small workspace view and dense links with a generic centered logo-and-socials block.

## Motion and responsive

### Motion

**Observed:**

- Gradient actions declare a repeating chromatic animation of 3s linear with a 200% background size.
- The strip action declares opacity 0.2s ease-out; the large signup action declares 0.2s ease-out.
- Live demonstrations include sliders and play/pause controls; horizontal ASCII ribbons and deforming media edges are visible signature treatments.

**Transfer:**

- Animate the action gradient independently from text so its compact candy-strip character remains intact.
- Use motion to reveal product range or a working adjustment, and retain the explicit play/pause affordance for looping specimen demonstrations.

**Unknown:**

- Exact timing and geometry of the media-edge deformation and ribbon movement are not established.
- Focus-visible styling and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The desktop composition uses a 48px top strip, 24px main gutters, three-column galleries, paired media and one-third/two-thirds editorial splits.
- Stylesheets contain many width breakpoints, including 600px, 768px, 1024px and 1280px; their exact layout effects are not established.

**Transfer:**

- As a design adaptation, stack the specimen toolbar into useful groups and keep the large word specimen as the dominant object rather than shrinking the entire desktop screen.
- Collapse galleries and split stories into fewer columns while retaining hairline chapter bars and the green sheet.
- Stack the three signup elements and preserve the independent scribbled field outline; keep the footer directory readable rather than proportionally scaling its tiny desktop links.

**Unknown:**

- Mobile layout, navigation replacement, exact breakpoint mapping and touch interactions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
