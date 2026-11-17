# Current — human warmth, cartoon punch

## Overview

An airy, predominantly white marketing style pairs exceptionally light grotesk headlines with candid, sunlit people and exuberant cartoon collage. Black bands and rainbow-like edge glows give the otherwise restrained layout moments of theatrical contrast. It suits approachable consumer products that need both emotional optimism and plainly explained practical benefits.

### Essentials

- Headlines feel almost handwritten in their lightness, not their construction: the default display is soehne 90px/1, weight 100, -0.04em tracking; section headings step down to 48px/1.2 with -0.02em tracking.
- The opening is a human encounter rather than a dashboard: a two-line promise and single-line support occupy the left half, a sharp-cornered 486×604px lifestyle portrait occupies the right, and a 56px integrated signup pill sits below the copy.
- Actions look like small capsules inside a much larger world: 16px bold labels, 14px 24px padding, 48px black primary buttons and 52px white outlined secondary buttons, both with 9999px radii.
- Color belongs to pictures and luminous edges, not the prose: white dominates the default page, black anchors navigation and the closing band, and saturated green, pink, cyan and yellow live inside illustrations. Include a warm violet-to-orange-to-yellow 98px edge glow against black.
- Real life gets interrupted by flat cartoon optimism: stage rectangular photographs with black-outlined clouds, arrows, coins or analogous benefit symbols in saturated flat fills. Include at least one such collage; a simple photograph plus three bold SVG shapes is the minimum equivalent.
- Proof and capabilities are organized by rules rather than rounded boxes: 2px vertical rules and 24px inset copy support three-column testimonials or benefits; major sections breathe with 120px vertical padding and 24px grid gutters.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#5900f5` | `--color-violet` | accent, background | Central color of the warm closing glow and lower edge of cool transitions; also a calculator result accent. |
| Glow orange | `#f47635` | `--color-orange` | accent | Warm transition between gold and violet. |
| Glow gold | `#f4cb45` | `--color-gold` | accent | Lowest warm edge of the closing glow. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, border, action | Headlines, body copy, primary actions, rules and dramatic bands. |
| Field label gray | `#4e525e` | `--color-field-text` | text | Signup labels and light-navigation hover text. |
| Disclosure gray | `#737582` | `--color-muted` | text | Dense final disclosures, visually subordinate to the marketing story. |
| Pale edge | `#dfe5ec` | `--color-rule` | border | Footer separators and inactive instructional card outlines. |
| Cloud | `#ebeff2` | `--color-input` | surface, border | Signup field backing and pale comparison cell borders. |
| Trust tile | `#f9f9f9` | `--color-trust` | surface | Very faint backing behind external review widgets. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Dominant canvas, inverse text, secondary actions and forms on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| instruction-led product stories | Glow lime | `#a6f00c` | `--color-lime` | accent | Lime base of the benefit-summary glow. |
| extended product stories | Glow magenta | `#e437ff` | `--color-magenta` | accent | Upper saturated stop in the cool chapter boundary. |
| extended product stories | Glow periwinkle | `#5d7bf9` | `--color-blue` | accent | Middle stop in the cyan-and-magenta chapter boundary. |
| extended product stories | Glow cyan | `#5cd3dd` | `--color-cyan` | accent | Cool luminous boundary between major chapters. |
| comparison sections | Dark comparison edge | `#3d4049` | `--color-table-edge` | border | Dividers within the black highlighted table column. |
| calculators and comparison sections | Calculator mist | `#f3f6f8` | `--color-panel` | surface | Functional calculator backing and comparison header strip. |

## Typography

- **soehne** — All marketing headings, paragraphs, navigation and action labels. Neutral neo-grotesk with open, readable lowercase; extremely light display cuts contrast with bold compact interface labels. If unavailable, use **Inter**. Use weights 100, 300, 400, 500 and 700; preserve tight display tracking and check line breaks. Font stack: "soehne", "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | soehne | 100 | 90px | 1 | -0.04em | Default two-line opening promise and monumental checklist heading. |
| display-emphasis | soehne | 400 | 90px | 1 | -0.04em | A contrasting phrase inside the large checklist heading. |
| proof-heading | soehne | 300 | 72px | 1.2 | -0.0004em | Centered social-proof lead, notably more open than the display tracking. |
| heading | soehne | 100 | 48px | 1.2 | -0.02em | Default feature chapters and illustrated-grid section leads. |
| closing-heading | soehne | 300 | 48px | 1.1 | -0.02em | Default white closing promise on the black band. |
| card-heading | soehne | 700 | 24px | 1.2 | -0.02em | Reassurance features, benefit summaries and instructional titles. |
| quote | soehne | 100 | 24px | 1.4 | -0.02em | Customer quotations in vertical-rule columns. |
| illustrated-card-heading | soehne | 400 | 21.3px | 1.2 | -0.02em | Titles below the wide illustrated benefit thumbnails. |
| body-roomy | soehne | 300 | 20px | 1.6 | normal | Three-column illustrated benefit descriptions and reassurance text. |
| body | soehne | 400 | 18px | 1.6 | normal | Default feature support and uppercase category labels; labels use the same recipe with uppercase copy. |
| hero-support | soehne | 100 | 18px | 1.6 | normal | Single-line opening support. |
| button | soehne | 700 | 16px | 1.25 | -0.01em | All pill action labels. |
| navigation | soehne | 700 | 16px | 1.4 | -0.01em | Compact navigation labels and comparison header labels. |
| utility-link | soehne | 400 | 16px | 1.4 | -0.01em | Footer links and compact comparison values. |
| field-label | soehne | 400 | 12px | 1.1 | -0.013em | Signup field label; its resting presentation is scaled to 1.25. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| proof-led product stories | monumental-stat | soehne | 300 | 120px | 1 | -0.04em | Two-line centered audience or adoption statistic. |
| question-led product stories | faq-heading | soehne | 100 | 96px | 1 | -0.04em | Oversized FAQ title; also the centered white-canvas closing variant. |
| dedicated product pages | product-hero | soehne | 100 | 80px | 1 | -0.04em | Centered product-specific opening promise. |
| dedicated product pages | product-heading | soehne | 100 | 64px | 1.1 | -0.04em | Large alternating feature chapters. |
| object-led product closings | product-closing | soehne | 300 | 64px | 1.1 | -0.02em | White closing promise beside oversized product objects. |
| extended product stories | compact-heading | soehne | 100 | 40px | 1.1 | -0.02em | Capability-grid and process-section leads. |
| dedicated product pages | product-body | soehne | 100 | 16px | 1.6 | normal | Feature descriptions and FAQ answers. |
| FAQ sections | faq-question | soehne | 500 | 16px | 1.6 | normal | Questions in ruled disclosure rows. |
| proof-led product stories | stat-label | soehne | 700 | 16px | 1.6 | 0.08em, uppercase | Small centered preface above the monumental statistic. |

**Notes:**

- Keep the light display cut even when a heading is very large; boldness belongs mainly to small labels and feature titles.
- Display tracking is -0.04em, ordinary section and card headings use -0.02em, while body tracking remains normal. The centered proof heading is a deliberate open-tracking exception.
- Body copy is black rather than muted gray. Reserve gray for field labels and disclosures. Do not infer a fluid type formula; maintain the hierarchy when adapting to smaller widths.

## Layout

**Density:** Airy: the main content occupies a restrained inner grid while photographs and short copy blocks are separated by long stretches of white.

### Spacing

**Spacing system:**

- **horizontal-grid** 8px, horizontal — Side padding and gutters predominantly follow multiples of 8px.

| Value | Use |
| --- | --- |
| 8px | Small control and icon insets. |
| 16px | Feature title-to-description spacing and compact list gaps. |
| 24px | Main grid gutter, copy-stack gap, outlined-column inset and text-to-action gap. |
| 40px | Large internal card padding and heading-to-form spacing. |
| 48px | Desktop page side padding and image-to-title gap in illustrated cards. |
| 80px | Section lead-to-grid spacing and footer vertical padding. |
| 120px | Default major-section vertical padding. |
| 240px | Combined breathing room between alternating feature rows. |

### Containers and grids

- **page-grid**: max width 1440px · 12 columns · gap 24px · side padding 48px. Centered desktop framework; full content width is 1344px.
- **inner-story**: max width 1116px · side padding 0px. Default marketing rows occupy the inner ten columns, with content edges near 162px and 1278px at desktop.
- **three-up**: 3 columns · gap 24px. Illustrated benefits and reassurance items, each about 356px wide in the inner story.
- **feature-pair**: 2 columns · gap 24px. Photo and copy alternate sides. Default inner-story photographs are 512px wide; dedicated product variants use 660px square photographs within the wider grid.
- **form-limit**: max width 500px. Signup capsules never stretch across the entire text column.
- **faq-grid** (only for FAQ sections): 12 columns · gap 24px. Title occupies the left three columns; 888px question list starts at the fifth column.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons | 9999px (pill) |
| signup-field | 30px |
| editorial-media-and-panels | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default page material.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Untextured white with sharp rectangular media and unboxed copy.

**Transfer:** Let whitespace, typography and imagery establish the hierarchy.

#### Black band · level 0

**Use:** Navigation and conversion anchors; larger feature chapters on dedicated product pages.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** True black, without a gray card floating on top. White type and luminous edge color provide the contrast.

**Transfer:** Use a deliberate dark chapter rather than tinting every section.

#### Warm horizon · level 1

**Use:** Signature lower edge of a black conversion band.

**CSS:** `height: 98px; background: linear-gradient(0.62deg, #f4cb45 0.27%, #f47635, #5900f5 50.25%, rgba(0, 0, 0, 0) 100.22%)`

**Observed:** A continuous soft horizontal strip, darkest at the upper edge and golden at the bottom; flush with the panel edges.

**Transfer:** Keep it low in the composition, behind content, not as a headline fill.

#### Trust backing · level 1

**Use:** External review widget in the footer.

**CSS:** `background: #f9f9f9; padding: 16px 8px 0px`

**Observed:** Subtle rectangular backing, not a decorative testimonial card.

**Transfer:** Use only where a real third-party trust asset needs separation.

#### Cool horizon · level 1

**Only for:** extended product stories

**Use:** Transition out of a black feature chapter.

**CSS:** `height: 196px; background: linear-gradient(to top, #5900f5 0.23%, #5cd3dd, rgba(0, 0, 0, 0) 100.27%)`

**Observed:** Additional white-canvas boundaries blend cyan through periwinkle and magenta into transparent white. The instruction-led variant blends lime through cyan.

**Transfer:** Use a chapter-specific colorway, not a rainbow around every box.

#### Functional panel · level 1

**Only for:** calculators and comparison sections

**Use:** A practical interactive tool within the editorial page.

**CSS:** `background: #f3f6f8; padding: 40px; border-radius: 0px; box-shadow: none`

**Observed:** Pale square backing separates inputs from the open result area.

**Transfer:** Group the actual controls, leaving results on the page canvas.

## Components

### Navigation

**Use:** Persistent desktop orientation.

**CSS:** `position: fixed; height: 74px; background: #000000; color: #ffffff; border-bottom: 2px solid #ffffff; z-index: 11`

**Text style:** `navigation` — soehne 700 · 16px/1.4 · tracking -0.01em

**Observed:** Product links align left, wordmark sits in the center, and supporting links plus a white Primary button align right. Inner navigation uses 48px side padding and 24px link gaps. Dedicated product pages invert to white with a black bottom rule and black action.

**Transfer:** Keep the central identity optically separate from the two link groups.

### Primary button

**Use:** Main conversion action, standalone or inset into signup.

**CSS:** `background: #000000; color: #ffffff; border-radius: 9999px; padding: 14px 24px; height: 48px`

**Text style:** `button` — soehne 700 · 16px/1.25 · tracking -0.01em

**Observed:** A compact text-only capsule. The black-navigation variant reverses to white with black text. In a form it sits at the right with a 4px inset.

**States:** Declared: hover background-color #24262e; focus-visible outline solid 2px, outline-offset 0.3ch, background-color #24262e, box-shadow inset 0 0 0 4px #000000. The white variant hovers to #ebeff2 and adds an inset 2px #8e94a0 focus shadow.

### Secondary button

**Use:** Lower-commitment feature navigation.

**CSS:** `background: #ffffff; color: #000000; border: 2px solid #000000; border-radius: 9999px; padding: 14px 24px; height: 52px`

**Text style:** `button` — soehne 700 · 16px/1.25 · tracking -0.01em

**Observed:** Small outlined capsule under a paragraph, rather than an inline arrow link.

**States:** Declared: hover text-decoration none, background-color #24262e, border 2px solid #dfe5ec; focus-visible outline solid 2px, outline-offset 0.3ch, background-color #24262e, box-shadow inset 0 0 0 2px #dfe5ec, border 2px solid #dfe5ec.

### Signup capsule

**Use:** Opening and closing conversion form.

**CSS:** `background: #ebeff2; border-radius: 30px; height: 56px; padding-left: 24px; max-width: 500px; position: relative; overflow: hidden`

**Text style:** `field-label` — soehne 400 · 12px/1.1 · tracking -0.013em

**Observed:** One field and a right-inset Primary button read as one object. The label rests at scale 1.25. The black-band version uses a white field backing and retains the black inset action.

**Transfer:** Use one genuinely useful signup datum and retain its accessible label; do not expand this into a multi-field boxed form.

### Ruled testimonial

**Use:** Human proof without heavy card chrome.

**CSS:** `border-left: 2px solid #000000; padding: 0px 24px`

**Text style:** `quote` — soehne 100 · 24px/1.4 · tracking -0.02em

**Observed:** Five black stars, a short quotation and a source/store attribution stack vertically. Three columns are visible, with small outlined circular previous/next controls below at the right.

**Transfer:** Use attributable customer words, keeping the black-rule structure and open white backing.

### Ruled benefit

**Use:** Concise capability or reassurance summary.

**CSS:** `border-left: 2px solid #000000; padding-left: 24px`

**Text style:** `card-heading` — soehne 700 · 24px/1.2 · tracking -0.02em

**Observed:** Small icon above bold title, then a short paragraph. Three or four columns share the page grid. Dark variants use white rules, 40px left padding and colorful square illustrations.

**Transfer:** Keep each benefit independently legible rather than joining them into one dense list.

### Footer links

**Use:** Support and company navigation beneath the conversion band.

**CSS:** `color: #000000; display: block`

**Text style:** `utility-link` — soehne 400 · 16px/1.4 · tracking -0.01em

**Observed:** Two sparse columns with bold 16px/24px headings and links in 40px rows. Brand mark is isolated left, trust widgets sit at the far right.

**States:** Declared: hover text-decoration underline; focus-visible outline solid 2px, outline-offset 0.3ch.

### Footer utility strip

**Use:** Separate policy and social navigation from the long disclosure tail.

**CSS:** `border-top: 1px solid #dfe5ec; border-bottom: 1px solid #dfe5ec; padding: 24px 0px; display: flex; justify-content: space-between; flex-wrap: wrap; column-gap: 80px; row-gap: 24px`

**Observed:** Copyright and small policy links align left; six 40px social targets sit right with 16px gaps. The strip spans the wider page grid. Dense gray 12px/1.4 disclosures follow 40px below.

**Transfer:** Keep necessary policy copy after the navigational footer, not mixed into the main story.

### FAQ row

**Only for:** FAQ sections

**Use:** Compact objection handling.

**CSS:** `border-top: 2px solid #000000; padding: 24px 0px; display: flex; justify-content: space-between; align-items: center; transition: background 0.25s`

**Text style:** `faq-question` — soehne 500 · 16px/1.6

**Observed:** Question left, small 24px chevron area right, with a bottom rule closing the entire list. Default rows are about 76px high; expanded answer copy uses product-body.

**Transfer:** Use semantic disclosure controls and let longer questions increase row height.

### Instruction card

**Only for:** instruction-led product stories

**Use:** A staged explanation beside a large illustration.

**CSS:** `border: 2px solid #000000; padding: 40px; border-radius: 0px; transition: 0.15s ease-in-out`

**Text style:** `card-heading` — soehne 700 · 24px/1.2 · tracking -0.02em

**Observed:** Number and short title share a line, description sits 8px below. Three cards stack with 20px gaps; inactive cards use pale #dfe5ec outlines rather than black.

**Transfer:** Pair the current step with a flat outlined illustration, not a dense app mockup.

### Comparison cell

**Only for:** comparison sections

**Use:** Plain feature comparison with one strongly differentiated column.

**CSS:** `border: 2px solid #ebeff2; padding: 12px 16px; border-radius: 0px`

**Text style:** `utility-link` — soehne 400 · 16px/1.4 · tracking -0.01em

**Observed:** Equal-width columns and pale header strip. The featured offering is a continuous black column with white text and #3d4049 dividers; row labels are bold. Desktop cells are about 224px wide and 74px high.

**Transfer:** Highlight one column through inversion instead of colored checks or floating pricing cards.

## Imagery and graphics

### Candid lifestyle photography

**Use:** Opening portrait and alternating feature rows.

**Observed:** Relaxed, diverse adults in ordinary outdoor, home and retail settings; warm natural skin tones, daylight, tactile clothing and candid gestures. Photos are hard-edged rectangles with no shadow or rounded frame. The default opening portrait is 486×604px; feature photographs range from 512px-wide landscape scenes to 660px squares.

**Transfer:** Show the emotional outcome of using the new product, with real people and believable surroundings rather than a floating generic interface. If people are unsuitable, photograph the product in actual use with the same natural light and close framing.

### Pop cartoon collage

**Use:** A signature expressive device in feature media and illustrated benefit thumbnails.

**Observed:** Photographic hands, phones and faces combine with flat neon-green arrows, pink clouds, yellow tokens and thick black outlines on cyan or periwinkle backing. Drawings overlap and run beyond the rectangular frame; media contains the saturation while surrounding copy remains black on white.

**Transfer:** Translate the benefit into a small family of simple symbols and layer them around a real photograph. Minimum version: one clean photo cutout, three oversized outlined SVG symbols and one saturated flat backing.

**Build:** Use a square or 512×325px overflow-hidden stage. Place the photo or cutout centrally at 60–85% of stage height. Draw 3–5 irregular cloud, arrow or token paths in SVG with flat green, pink and yellow fills and black strokes around 2–3px at a 512px stage width. Put one shape behind the subject, two in front near opposing corners, and let their edges clip. Avoid gradients within the cartoons.

### Luminous horizon strip

**Use:** Required chromatic punctuation at a major conversion or chapter boundary.

**Observed:** A full-width soft stripe transitions from near-black through violet, orange and gold; it hugs the bottom of a black band instead of filling the whole background. Cool product-story variants replace the warm base with cyan or lime.

**Transfer:** Carry the warm strip into the default new page even when no equivalent physical product imagery exists.

**Build:** Apply Warm horizon as an absolutely positioned bottom layer, full panel width and 98px high. Keep text and forms above it. Use the continuous gradient itself for softness; no grain, particles or extra card shadow is needed.

### Oversized product objects

**Only for:** object-led product closings

**Use:** A dramatic dark conversion panel.

**Observed:** Two tall black physical cards cross on steep diagonals at the left, extend beyond the panel edges and have subtle reflective edge highlights. White product markings and a tiny rainbow edge connect them to the larger Warm horizon. Copy and signup sit in the right half.

**Transfer:** Use the new product's physical object or two restrained dark interface slabs. If neither is meaningful, use the default text-and-form Black band rather than unrelated financial objects.

**Build:** Place two transparent product renders over black, each approximately 432px wide and tall enough to clip at top and bottom. Rotate in opposing directions to create one crossing diagonal. Keep low-contrast highlights on the object edges, and place the glow behind them, never over the text.

### Illustrated proof mural

**Only for:** quantified product stories

**Use:** A full-bleed visual pause that turns one key result into artwork.

**Observed:** A 1440×810px flat illustration centers a huge outlined number amid interlocking green and pink people, plants, vehicles and aspiration symbols on pale aqua. Thick black linework and edge-clipped figures make it feel like a poster rather than a chart.

**Transfer:** Use a verified result relevant to the new product. Minimum version is a large outlined numeral surrounded by four simple, black-stroked benefit symbols on a pale aqua field.

**Build:** Create a 16:9 SVG composition. Leave the middle half relatively clear for thin outlined numerals; mass flat green and pink organic shapes along all four edges, add black 3–5px outlines at 1440px width, and overlap some shapes across the numeral edge. Keep the numeral readable.

### Portrait proof rail

**Only for:** proof-led product stories

**Use:** Humanize the scale claim before the testimonial group.

**Observed:** 352×469px daylight portraits form a horizontal strip with 24px gaps and partial images clipped at both viewport edges. No captions or card framing interrupt the faces.

**Transfer:** Use varied real customer or practitioner portraits; preserve the tall crop and edge-to-edge rhythm without turning it into a team directory.

### Icons

**Observed:** Small black or white filled utility SVGs typically occupy 24px boxes; social targets are 40px. Feature illustrations use black outlines and vivid flat green, yellow, cyan or pink fills, ranging from 60px icon scenes to 120px reassurance artwork. Checklists use simple checkmarks rather than colored badges.

**Transfer:** Choose one consistent simple utility icon family for controls, and separately draw playful benefit icons with flat fills and visible black outlines. Keep disclosure icons small and adjacent to the relevant claim.

## Section recipes

How recurring sections are built.

### First screen: Human split opening

**Observed:** A 74px Black band navigation sits above a white two-column stage, about 804px tall including the header area. Inside the 1116px inner story, the left half holds a 90px/1 weight-100 two-line promise with -0.04em tracking, then 18px support after 24px; the 486×604px right portrait is taller than the copy group. The Signup capsule sits well below support, remaining within the left column. Layers are white canvas, rectangular photograph, headline/support, then form and fixed navigation. Within the first 900px the complete portrait, promise, support and action are visible, followed by a row of monochrome press marks; the first feature section begins below the fold.

**Transfer:** Lead with a compact, confident promise and one emotionally legible real-use image; preserve the large white field and portrait-to-copy imbalance. Without people, use a daylight photograph of the new product being used. Dedicated product pages instead center an 80px two-line heading and 18px support above an edge-to-edge 1440×810px photo or collage, beginning after an 80px gap; the image continues below the first screen and there is no hero form.

**Avoid:** Do not replace this with a centered dashboard floating on a gradient, a full-bleed photo with text over it, or an oversized cluster of competing buttons.

**Text style:** `display` — soehne 100 · 90px/1 · tracking -0.04em

### Illustrated benefit triptych

**Observed:** A heading introduces three 356px-wide open columns, 80px below the lead. Each starts with a wide 356×182px Pop cartoon collage, followed by a regular illustrated-card-heading, body-roomy paragraph and Secondary button. Columns share 24px gutters and sit inside the inner story with 120px vertical padding.

**Transfer:** Use three independently understandable benefits, keeping picture, claim, explanation and action in that order.

### Alternating feature chapter

**Observed:** A 512px-wide picture pairs with a vertically centered copy stack: uppercase category label, heading, short body and Secondary button at 24px intervals. Rows switch image side. Dedicated product variants expand to 660px square media and product-heading with product-body; some copy blocks begin below a 2px top rule.

**Transfer:** Alternate concrete outcomes and explanations, not just the image position. Use Black band for a purposeful contrasting chapter rather than every other row.

### Proof without boxes

**Observed:** A centered proof-heading leads into three Ruled testimonial columns; stars and store/source attribution stay monochrome. The proof-led variant precedes the quotes with Portrait proof rail and a small stat-label over a two-line 120px monumental-stat.

**Transfer:** Pair scale proof with actual human attribution. Use the monumental statistic only when a true adoption or impact measure warrants that much space.

### Monumental checklist

**Observed:** A narrow left column sets a large two-phrase 90px heading, mixing display-emphasis with display. The right column holds four illustrated practical benefits with 24px light text and small colorful icons.

**Transfer:** Use for service reach, support or ease-of-use proof; maintain the contrast of monumental language and modest list entries.

### Reassurance trio

**Observed:** Three open columns follow a 48px heading with an 80px gap. Each holds a 120px cartoon icon, a bold 24px title 40px below, then body-roomy copy after 16px.

**Transfer:** Make the reassuring mechanics tangible, keeping illustrations small relative to the white field.

### Warm closing conversion

**Observed:** Default closing is a roughly 384px Black band with a 48px closing-heading left and white-backed Signup capsule right, aligned within the inner story. Warm horizon finishes the bottom. The object-led variant is an inset 1344×640px black stage with oversized crossing product objects left and a 64px product-closing plus form right.

**Transfer:** End the main story with a short outcome-oriented promise and the same action as the opening; use the object-led variant only when the object itself matters.

### Editorial footer and disclosure tail

**Observed:** After the main conversion, white returns with 80px vertical padding and 48px sides. A small brand mark sits far left, Footer links occupy the middle, trust widgets the far right. Footer utility strip follows after 64px, then gray disclosure paragraphs at 12px/1.4 with 16px vertical gaps. The long-form variant ends with many topic-specific disclosures; the instruction-led variant has a much shorter, product-specific tail.

**Transfer:** Separate brand navigation, utility navigation and required legal detail into three visual levels. Let actual disclosure needs determine the final height.

### Calculator and result field

**Only for:** calculators and comparison sections

**Observed:** A left-aligned 64px heading and 16px support introduce a two-part tool. A 432px-wide Functional panel holds amount and duration controls; four open result rows occupy the wider right side, with an 8px pale track, short colored fill, rate label and bold currency result aligned right. Explanatory small print follows the full tool.

**Transfer:** Expose a useful input and legible output without importing the product's full interface into the marketing page.

### Instruction and comparison chapters

**Only for:** instruction-led product stories

**Observed:** A centered 64px heading introduces a stack of three Instruction cards at left and a large flat outlined illustration at right. A later chapter uses a left-aligned 64px heading over a six-column table built from Comparison cell, with the featured offering inverted to black.

**Transfer:** Explain the workflow before asking the reader to evaluate alternatives; compare on a small number of meaningful criteria.

### Asymmetric FAQ

**Only for:** question-led product stories

**Observed:** An oversized 96px title anchors the left, while the 888px right column stacks FAQ row components. The panel stays white and open, with 120px surrounding section padding.

**Transfer:** Use short, genuine user questions and keep the question list visually stronger than its container.

### White monumental closing

**Only for:** instruction-led product stories

**Observed:** An all-white 842px closing area centers a 96px two-line promise and a cloud-backed Signup capsule. Large empty margins above and below make the action feel unhurried; no dark object panel is used here.

**Transfer:** Use this variant for a practical, instruction-heavy story that needs a calmer final invitation. Retain a luminous boundary elsewhere in the story.

## Page flow

**Storyline:** Human promise → concise benefits → visual capability chapters → human or quantified proof → reassurance and objections → focused conversion → navigation and disclosures.

### Broad consumer-product marketing overview

1. **Promise** — Human split opening followed by a monochrome credibility-mark rail.
2. **Capability overview** — Illustrated benefit triptych leads into alternating picture-and-copy chapters.
3. **Social proof** — Large centered audience claim and ruled customer quotations.
4. **Practical reassurance** — Monumental checklist, additional feature rows and a small illustrated reassurance grid.
5. **Closing call** — Black conversion band and warm horizon.
6. **Navigation and compliance** — White footer, utility strip and long muted disclosure tail.

**Transfer:** Use the default airy inner-story grid for an overview that ranges across several capabilities; vary the chapter order to fit the new product.

### Detailed capability story balancing emotional appeal and practical explanation

1. **Promise** — Centered two-line heading above a full-width human image.
2. **Benefit summary** — Three ruled columns and a cool luminous boundary.
3. **Capability chapters** — Alternating square photographs, large light headings and black-band chapters; outlined cartoons enrich selected images.
4. **Practical guidance** — Four ruled instructional columns explain everyday use.
5. **Objection handling** — Asymmetric FAQ.
6. **Closing call** — Inset black product-object stage, form and warm horizon.
7. **Navigation and compliance** — White footer with utility strip and long disclosures.

**Transfer:** Use for a product whose value needs multiple grounded explanations and a clear workflow.

### Outcome-led product story with an interactive quantitative proof point

1. **Promise** — Centered headline and support above full-width photo collage.
2. **Quantified proof** — Calculator with pale input panel, open result rows and compact methodology.
3. **Visual punctuation** — Full-bleed outlined-number illustration mural.
4. **Capability chapters** — Alternating square photos explain outcomes and automation, followed by an asymmetric black photo chapter.
5. **Objection handling** — Wide ruled FAQ list.
6. **Closing call** — Crossing dark product objects beside a signup form and warm horizon.
7. **Navigation and compliance** — White footer followed by the long disclosure tail.

**Transfer:** Use when a user can meaningfully explore a result; make the tool useful and the mural about one verified outcome.

### Instruction-led product story with comparison and substantial human proof

1. **Promise** — Centered light headline over an edge-to-edge illustrated portrait.
2. **Benefit summary** — Three ruled benefits followed by a lime-and-cyan boundary.
3. **Product explanation** — Three outlined instructional cards beside a cartoon, then a structured comparison table.
4. **Human and scale proof** — Clipped portrait rail, monumental adoption statistic and ruled quotations.
5. **Objection handling** — Asymmetric FAQ.
6. **Closing call** — White centered monumental promise with cloud-backed signup capsule.
7. **Navigation and compliance** — Common footer structure with a shorter product-specific disclosure tail.

**Transfer:** Use for a concept that needs qualification, steps and alternatives explained before the final invitation.

## Writing

Warm, direct and upbeat, with practical confidence rather than institutional formality. Benefits are phrased as everyday improvements; quantitative promises are qualified close to the claim.

**Do not copy:** Do not reuse Current's name, wordmark, card artwork, press or trust logos, customer quotations, adoption totals, rates, fee promises, approval criteria or performance claims. Replace all such assets and facts with the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' for what the provider makes easier. Name a feature only when it helps the reader understand a concrete action.
- **Rhythm:** Short two-part hero promises, often two lines; feature headlines generally contain one clear outcome. Supporting copy is one or two plain sentences, and actions are terse title-case labels.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Everyday progress expressed through repetition or a familiar phrase with a helpful twist. | 4–8 words | “Get ahead. Get [Brand].”<br>“Now any day can be payday” |
| Feature heading | Begin with an active verb and put the outcome before the mechanism. | 5–12 words | “Earn up to 4.00% on your savings”<br>“Get paid up to 2 days faster” |
| Support | Explain the mechanism in conversational language after stating the benefit. | One or two sentences | “Save automatically with Round-Ups, set your goals, and more.”<br>“We're making credit simpler, safer, and seamless.” |
| Action | Two-word action with no rhetorical embellishment. | 2 words | “Get Started”<br>“Learn More” |
| Question | Ask the real practical question in the user's own language. | 5–14 words | “How much does Paycheck Advance cost?” |

**Words and phrasing to use:** get; build; grow; your; easy; automatically; goals; everyday; up to; when you need it

**Avoid:** revolutionary ecosystem; disruptive synergy; exclusive elite access; guaranteed results; institutional jargon

**Rules:**

- Lead with the useful outcome, then explain what the reader must do.
- Keep qualifications next to numerical claims through concise support or a disclosure control.
- Use compact uppercase category labels for orientation, not slogans.
- Let photography and cartoon art supply the exuberance; keep prose calm and intelligible.

## Do's and Don'ts

### Do

- Keep the default display at weight 100, 90px/1 and -0.04em tracking.
- Use the inner 1116px story width inside the 1440px framework for ordinary marketing rows.
- Give major sections 120px vertical padding and grids 24px gutters.
- Preserve the 4px inset relationship between a 48px action and a 56px signup field.
- Keep image edges square and photographic lighting natural.
- Combine a real-use photograph with black-outlined flat cartoon shapes in at least one expressive scene.
- Anchor a meaningful boundary with the 98px warm luminous strip.
- Use 2px black rules to organize proof, and 1px pale rules for footer utilities.

### Don't

- Do not turn the 48px light section headings into bold SaaS-style headings.
- Do not spread the violet accent into ordinary body text or primary button fills.
- Do not put rounded pastel cards behind every feature; open white columns are the default.
- Do not add soft elevation shadows to media or panels; separation comes from rules and composition.
- Do not use glossy 3D cartoons in place of flat black-outlined illustration.
- Do not crop every photograph into a circle or place it inside a device frame.
- Do not stretch signup controls to the full 1344px page width; cap them at 500px.
- Do not make all proof headings use the tightly tracked display recipe; the 72px proof lead has nearly neutral tracking.

## Motion and responsive

### Motion

**Observed:**

- Signup surfaces and labels declare 0.2s transitions.
- FAQ question rows declare background 0.25s; instructional cards declare 0.15s ease-in-out.
- Other actions and surfaces declare transform 0.25s cubic-bezier(0.4, 0, 0.2, 1), and some widths declare 0.5s with the same curve.
- Header and horizon layers participate in translated scroll compositions; opening copy has layered alternate text treatments.

**Transfer:**

- Keep the opening portrait and promise readable in a settled state; animation should reveal the composition, not replace it.
- Preserve a continuous horizontal luminous boundary when animating chapter transitions rather than animating many isolated colored boxes.

**Unknown:**

- Exact scroll trigger positions, choreography and complete durations for the opening scene are not established.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- Styles declare width boundaries including 479px, 480px, 600px, 768px, 769px, 800px, 1024px and 1440px; some variants also use 960px, 1200px and 1700px.
- Layout classes distinguish desktop grid content from alternate narrow-screen content, including the instruction cards and comparison table.

**Transfer:**

- As design guidance, stack portrait and copy on narrow screens while preserving the short promise, accessible form and square media edges.
- Reduce the number of simultaneous proof columns rather than compressing quotation text; retain the vertical-rule treatment.
- Keep the glow continuous across the available width, and preserve the featured-column inversion when reformatting comparisons.

**Unknown:**

- Actual mobile compositions, mobile type sizes and navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
