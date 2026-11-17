# VanMoof — engineered for the street

## Overview

A cinematic industrial style that makes engineered objects feel desirable, tactile and slightly rebellious. Dark charcoal product chapters give way to pale grey editorial and buying sections, with regular-weight grotesk typography and tiny monospace equipment labels. Sculptural studio imagery, luminous details and grainy city footage carry most of the emotion; the interface stays sparse and rectangular.

### Essentials

- The product name becomes a typographic monument over a macro view: a centered 240px regular grotesk with 0.8 line height and -0.04em tracking, paired with a 96px silver-gradient descriptor, fills the opening 900px screen.
- Dark cinema meets a light buying desk: use #222222 for the main product narrative, #f7f7f7 for the practical tail and #ffffff for comparison panels and the footer. Chromatic color belongs inside imagery and small product swatches, not broad interface fills.
- Controls look like equipment, not soft app badges: 4px button corners, 8px media corners, 1px rules and 32px or 48px outlined square arrow controls. The primary hero action is a white 40px-high rectangle.
- A floating glass instrument bar stays over the story: 600px × 56px, 4px corners, 30px backdrop blur, a centered identity and menu/cart controls at opposite ends.
- Technical labels counterbalance cinematic imagery: 14px uppercase monospace at 1.2 line height precedes 32px benefit titles; 48px/1.1 chapter headings sit above 18px/28px support.
- Light is a signature device: include an illuminated edge, halo or focused beam against a dark physical object. Without bespoke film or 3D, use one sharply lit macro photograph with a white ring or soft blue-grey light field rather than a generic illustration.
- An image can punctuate a sentence: include a spacious pale interlude with a short 64px-scale closing phrase split around a small square moving-image panel. A still image of the product in use is the fallback; this device is independent of where the page closes.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action, border | Text over dark imagery, white purchase actions, comparison panels and the shared footer. |
| Black | `#000000` | `--color-black` | background | Deepest media and demonstration backings; keep distinct from the charcoal narrative canvas. |
| Charcoal | `#222222` | `--color-ink` | text, background, action, border | Default text on light surfaces and the main dark narrative canvas. |
| Graphite | `#313131` | `--color-edge-dark` | surface, border, text, action | Dark panel edges, flat destination tiles, footer utility links and dark hover fills. |
| Middle grey | `#808080` | `--color-muted` | text, border | Secondary numbers, inactive controls and diminished words in display statements. |
| Silver shade | `#b3b3b3` | `--color-silver-low` | text | Lower stop of the 45-degree gradient on the hero descriptor. |
| Silver highlight | `#cecece` | `--color-silver-high` | text | Upper stop of the hero descriptor's silver gradient. |
| Light rule | `#e0e0e0` | `--color-rule` | border, text | Light accordion edges, spec separators and subdued price text on dark imagery. |
| Pale grey | `#eeeeee` | `--color-panel` | surface | Product accessory backings and light feature panels. |
| Off white | `#f7f7f7` | `--color-canvas` | background, action | Light editorial and practical sections; light hover fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| physical-product finish selectors | Electric blue finish | `#5c88da` | `--color-finish-blue` | accent | 24px product-finish swatches and corresponding product imagery, never a general CTA color. |
| physical-product finish selectors | Pale mint finish | `#bfcec2` | `--color-finish-mint` | accent | 24px product-finish swatches. |
| physical-product finish selectors | Black finish | `#232222` | `--color-finish-black` | accent | 24px product-finish swatches; distinct from the interface charcoal. |

## Typography

- **Unica77LLWeb** — All primary headings, paragraphs and action labels. Neutral neo-grotesk with open, unfussy letterforms; almost everything is regular rather than bold. If unavailable, use **Inter**. Use 400 throughout; preserve the compressed hero tracking rather than adding bold weight. Font stack: "Unica77LLWeb", "Inter", system-ui, sans-serif.
- **Unica77Mono** — Uppercase technical eyebrows, small section labels and feature numbering. Compact utilitarian monospace that reads like a marking on equipment. If unavailable, use **IBM Plex Mono**. Font stack: "Unica77Mono", "IBM Plex Mono", monospace.
- **PPEditorialNew** (only for product model comparison qualifiers) — A parenthetical qualifier beside a sans-serif model name. Fine, high-contrast editorial serif; a very small exception to the grotesk system. If unavailable, use **Bodoni Moda**. Font stack: "PPEditorialNew", "Bodoni Moda", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Unica77LLWeb | 400 | 240px | 0.8 | -0.04em | Short product name in the centered cinematic opening. |
| display-descriptor | Unica77LLWeb | 400 | 96px | 1 | -0.04em | Second line of the hero title, rendered in a silver gradient rather than solid white. |
| heading | Unica77LLWeb | 400 | 48px | 1.1 | normal | Chapter introductions, major tile titles, FAQs and large editorial statements. |
| heading-small | Unica77LLWeb | 400 | 32px | 1.1 | normal | Benefit titles, feature cards, plan names and the footer community heading. |
| compact-heading | Unica77LLWeb | 400 | 24px | 1.1 | normal | Newsletter invitation and compact service process titles. |
| tagline | Unica77LLWeb | 400 | 20px | 1.1 | normal | Hero promise and structured technical-list text. |
| body | Unica77LLWeb | 400 | 18px | 28px | normal | Chapter support, quotations, larger descriptions and accordion questions. |
| body-small | Unica77LLWeb | 400 | 16px | 1.5 | normal | Feature card paragraphs and compact descriptive copy. |
| action | Unica77LLWeb | 400 | 14px | 20px | normal | Visible button labels, compact links, prices and footer navigation. |
| eyebrow | Unica77Mono | 400 | 14px | 1.2 | normal, uppercase | Technical labels, feature numbers and footer group names. |
| utility | Unica77LLWeb | 400 | 12px | 16px | normal | Footer social, legal and locale controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| multi-offer marketing homepages | portal-display | Unica77LLWeb | 400 | 280px | 1 | normal | Oversized short product name anchored left over a linked promotional image. |
| product comparison sections | comparison-heading | Unica77LLWeb | 400 | 96px | 1 | normal | Monumental heading above a white product comparison panel. |
| multi-offer marketing homepages | feature-panel-title | Unica77LLWeb | 400 | 80px | 1 | normal | Centered headline of a pale feature showcase. |
| editorial pages and product comparisons | editorial-title | Unica77LLWeb | 400 | 64px | 1 | normal | Plain editorial page title and model names in comparison panels. |
| subscription landing pages | service-title | Unica77LLWeb | 400 | 64px | 1 | -0.04em | Left-aligned title over a black technical service illustration. |
| product model comparison qualifiers | model-qualifier | PPEditorialNew | 400 | 32px | 1.1 | normal | Parenthetical suffix beside a large sans model name. |

**Notes:**

- Use regular weight to create the entire hierarchy; size and framing do the work normally assigned to bold.
- Only the cinematic title and subscription title tighten to -0.04em. Ordinary 48px and 32px headings retain normal tracking.
- Keep 18px/28px chapter copy distinct from 16px/24px feature-card copy and 14px/20px controls.
- For longer product names, reduce the display scale enough to retain a short centered title, rather than wrapping a marketing sentence into the monumental-name role.

## Layout

**Density:** Airy at the chapter level, compact inside controls and grids; imagery gets uninterrupted breathing room while adjacent media nearly touch.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Grid gutters, neighboring media tiles and accordion-row separation. |
| 12px | Footer navigation row gaps. |
| 16px | Chapter heading to support text; eyebrow and supporting-copy rhythm. |
| 24px | Image-to-caption gap, ordinary card content spacing and narrow-layout side padding. |
| 32px | Hero content-group gaps, accordion inner padding and smaller plan-card padding. |
| 40px | Overlay content inset on destination tiles. |
| 48px | Media-to-detail separation, carousel-controls offset and spec-row padding. |
| 64px | Footer community top padding and two-column subscription-card insets. |
| 80px | Chapter heading-to-film separation and panel top padding. |
| 120px | Large narrative pauses and comparison-panel top inset. |
| 160px | Major chapter separation on light and dark pages. |
| 200px | Extra-deep pauses between immersive capability chapters. |

### Containers and grids

- **Master grid**: max width 1920px · 12 columns · gap 8px. Centered page-wide grid. Standard content occupies the inner ten columns: 1199px wide at a 1440px viewport, leaving roughly 121px on each side.
- **Narrative column**: max width 720px. Six central grid columns hold chapter introductions and long display statements; their desktop width is 716px.
- **Media band**: gap 8px · side padding 8px. Near-edge-to-edge cinematic panels and paired square images. Inner chapter films occupy 1183px × 665px at desktop.
- **Two-column detail**: 2 columns · gap 8px. Equal 595px image/caption columns inside the ten-column container; a split editorial row may instead use a 716px image and a narrower text column.
- **Three-column grid**: 3 columns · gap 8px. 394px process, accessory or plan cards within the standard desktop content width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Action buttons | 4px |
|  | Media and panels | 8px |
|  | Square arrow controls and swatches | 2px |
| subscription feature demonstrations | Demonstration stages | 24px |

## Surfaces and depth

### Surfaces

#### Light canvas · level 0

**Use:** Practical buying sections and editorial page base.

**CSS:** `background: #f7f7f7; color: #222222`

#### Dark narrative · level 0

**Use:** Default product storytelling chapters and service explanations.

**CSS:** `background: #222222; color: #ffffff`

**Observed:** Dark chapters connect without visible card boundaries; the pale practical tail is a deliberate change of environment.

**Transfer:** Use dark space to unify the product story, then change to light when the visitor evaluates options.

#### White desk · level 1

**Use:** Product comparison and specifications; the footer uses the same fill without rounded outer corners.

**CSS:** `background: #ffffff; color: #222222; border-radius: 8px`

#### Pale product panel · level 1

**Use:** Accessory image backing and light feature showcases.

**CSS:** `background: #eeeeee; border-radius: 8px`

**Observed:** Low contrast, flat and shadowless; the object or image supplies depth.

#### Glass navigation · level 2

**Use:** Floating navigation over both light and dark content.

**CSS:** `background: linear-gradient(135deg, rgba(34, 34, 34, 0.5) 9.74%, rgba(34, 34, 34, 0.3) 90.26%); backdrop-filter: blur(30px); border-radius: 4px`

**Observed:** A masked 1px gradient edge fades from translucent white to transparent and back; it is not an opaque border.

**Transfer:** Keep the bar translucent so the scene beneath contributes to its color.

#### Media scrim · level 1

**Use:** Maintain legibility on photographic linked panels.

**CSS:** `background: linear-gradient(rgba(34, 34, 34, 0) 0%, rgba(34, 34, 34, 0.2) 100%); border-radius: 8px`

**Observed:** A lateral version shades the text side on service hero compositions.

#### Demonstration black · level 1

**Only for:** subscription feature demonstrations

**Use:** Large sticky capability stages.

**CSS:** `background: #000000; border-radius: 24px; color: #ffffff`

**Observed:** Black stages layer over the charcoal page, with a large capability icon at upper left and luminous interface fragments to the right.

## Components

### Floating navigation

**Use:** Persistent orientation over cinematic and editorial sections.

**CSS:** `width: 600px; min-height: 56px; position: fixed; top: 16px; left: 50%; transform: translateX(-50%); border-radius: 4px; backdrop-filter: blur(30px); background: linear-gradient(135deg, rgba(34, 34, 34, 0.5) 9.74%, rgba(34, 34, 34, 0.3) 90.26%); color: #ffffff`

**Observed:** A centered identity sits between a small menu glyph and a shopping-bag glyph. No desktop row of text links competes with the imagery.

**Transfer:** Use the new identity in the center; retain the compact instrument-bar composition.

### Primary button

**Use:** Main purchase action on the cinematic opening.

**CSS:** `background: #ffffff; color: #222222; height: 40px; padding: 0px 32px; border-radius: 4px; display: flex; align-items: center`

**Text style:** `action` — Unica77LLWeb 400 · 14px/20px

**Observed:** Label is centered. A nested label wrapper contributes 24px horizontal inset; the desktop example is 166px wide. A smaller version repeats in the sticky purchase strip.

**States:** Declared: hover background-color #f7f7f7.

### Outline button

**Use:** Secondary actions on light sections and newsletter signup.

**CSS:** `background: transparent; color: #222222; border: 1px solid #222222; border-radius: 4px; height: 48px; padding: 0px 24px`

**Text style:** `action` — Unica77LLWeb 400 · 14px/20px

**Observed:** Text and a 16px diagonal arrow sit in a centered row with an 8px gap. The dark plan variant reverses the border and text to white and expands to the card's content width.

**States:** Declared: hover background-color #313131; color #ffffff. Dark plan variant hover border-color #f7f7f7; background-color #f7f7f7; color #222222.

### Square arrow link

**Use:** Low-noise editorial and photographic calls to action.

**CSS:** `width: 48px; height: 48px; display: flex; align-items: center; justify-content: center; border: 1px solid #ffffff; border-radius: 2px; background: transparent; color: #ffffff`

**Text style:** `action` — Unica77LLWeb 400 · 14px/20px

**Observed:** Only the arrow is boxed; its label sits outside the square with an 8px gap. The diagonal arrow commonly points down-right. Compact variants use 32px squares and a charcoal outline on light backgrounds.

**Transfer:** Use this instead of turning every link into a filled button.

### FAQ row

**Use:** Objection handling in the practical tail.

**CSS:** `border: 1px solid #e0e0e0; border-radius: 8px; color: #222222; padding: 32px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `body` — Unica77LLWeb 400 · 18px/28px

**Observed:** Question left, small plus at far right, 94px closed height and 8px between rows. The dark service variant uses graphite borders and white text.

**Transfer:** Keep each question in its own outline, not in a single ruled list.

### Feature caption

**Use:** Explain a detail below a large image in pairs or horizontal rails.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding-right: 40px; color: #ffffff`

**Text style:** `heading-small` — Unica77LLWeb 400 · 32px/1.1

**Observed:** An uppercase Eyebrow sits 8px above a benefit title; a 16px/24px paragraph follows. Images sit 24px above the caption. Rails show two full 599px cards and a clipped next card, with 32px arrow controls below.

### Footer navigation

**Use:** Quiet, useful final destination on every page.

**CSS:** `display: flex; flex-direction: column; gap: 12px; color: #222222`

**Text style:** `action` — Unica77LLWeb 400 · 14px/20px

**Observed:** Mono group labels sit 24px above compact link lists. Newsletter copy forms a larger left column while three navigation groups occupy the right half. Utility links sit in a separate bottom row.

### Destination tile

**Only for:** editorial and multi-offer page endings

**Use:** Related next steps near the end of editorial and multi-offer pages.

**CSS:** `background: #313131; border-radius: 8px; overflow: hidden; padding: 40px; color: #ffffff; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `heading` — Unica77LLWeb 400 · 48px/1.1

**Observed:** Large title at the top; support at bottom left and a Square arrow link at bottom right. Flat graphite and image-backed variants share the same construction. A tall left tile can sit beside two stacked right tiles.

### Plan card

**Only for:** service and subscription pricing

**Use:** Compare included capability with paid options or subscription lengths.

**CSS:** `border: 1px solid #313131; border-radius: 8px; padding: 64px; display: flex; flex-direction: column; justify-content: space-between; gap: 24px; color: #ffffff`

**Text style:** `heading-small` — Unica77LLWeb 400 · 32px/1.1

**Observed:** Small outlined mono badge pinned at upper right, large line icon, plan name, ruled benefit rows, then price and full-width Outline button. Two-column subscription cards use 64px insets; three-column service plans use 32px. Discounts show the old price smaller, grey and struck through.

**Transfer:** Use equal visual weight for the options; do not invent a brightly colored recommended tier.

### Finish swatch

**Only for:** physical-product finish selectors

**Use:** Choose a material color in the product viewer or comparison.

**CSS:** `width: 28px; height: 28px; background: #ffffff; border-radius: 2px; display: flex; align-items: center; justify-content: center`

**Observed:** A 24px colored square nests inside a white frame. The selected blue example includes a tiny centered white square; the finish name appears in a neighboring uppercase mono label.

**Transfer:** Use the actual new product's finishes, not arbitrary interface accent colors.

## Imagery and graphics

### Sculptural studio product

**Use:** Hero, paired detail images, viewer and feature chapters.

**Observed:** Glossy dark metal and rubber are photographed or rendered close enough to cut beyond the frame. Large white-to-charcoal studio light fields reveal curved edges; low angles, spokes, seams and lenses feel monumental. Full scenes alternate with paired square details. Blue and mint finishes remain relatively restrained while white lamps and red rear lights become concentrated highlights.

**Transfer:** Photograph the new object as a sculpture: one macro edge or functional detail for the opening, one full-object beauty view and two closely framed details. The minimum is a genuine sharp product photograph against a gradient-lit neutral studio backdrop, not a stock mockup collage.

### Urban motion film

**Use:** Emotional interludes between capability explanations.

**Observed:** Street-level riders, blurred cars and trams, concrete, wet pavement and twilight city skylines. Color is muted and grainy, with occasional yellow transit, red hair or blue product paint. Footage occupies almost a whole viewport, with a short centered line rather than a paragraph.

**Transfer:** Show real use in a specific lived-in environment with motion blur, available light and imperfect city texture. A full-bleed documentary still is a valid fallback.

### Functional light field

**Use:** Signature illumination in the opening or a capability demonstration.

**Observed:** A bright white ring encircles a physical lens; other scenes use a soft blue-grey bubble around an object, elongated light trails or a narrow overhead beam. The glow belongs to the object and does not tint the whole interface.

**Transfer:** Attach one luminous detail to the new product's function: an edge, aperture, operating zone or protected volume. Keep most of the composition charcoal or black.

**Build:** Place a thin white SVG ellipse over the functional detail, duplicate it underneath with 8px and 24px blur and rgba(255,255,255,0.25) opacity. Add a larger offset radial-gradient ellipse in rgba(150,180,210,0.18) fading to transparent; mask its center to reveal the product. For a focused beam, use a narrow vertical translucent blue-grey cone above the object and blur its edges. Match the soft glow; exact gradient stops are not essential.

### Image-punctuated phrase

**Use:** A spacious visual refrain within the marketing story.

**Observed:** After clouds and a dark reflective architectural image, a pale field holds a small square street-film panel with a short black sentence split to its left and right. The words align toward the picture, turning it into punctuation.

**Transfer:** Split a short new promise into two balanced fragments around a square image of the product in use. Keep the image around 232px square at desktop and the text around 64px; use a static documentary image if motion is unavailable.

**Build:** Use a centered three-column flex or grid composition: right-aligned two-line phrase, 232px square image with 8px corners, left-aligned two-line phrase. Set a 48px gap and ample pale space above and below. Let the image, not a decorative symbol, join the sentence.

### Technical service diagram

**Only for:** service and subscription openings

**Use:** Replace physical beauty footage when the offer is an invisible capability.

**Observed:** The subscription opening is almost black, with thin white horizontal and vertical construction lines forming a tall capsule at the right and a white emblem centered within it. Another service opening places layered translucent circular discs and a location-pin contour over a dark full-product studio view.

**Transfer:** Create a simple capability emblem using the new product's geometry and build a restrained engineering diagram around it.

**Build:** Use an SVG with 1px white lines at low opacity across the full scene. Intersect two verticals with two horizontals around a 300px-wide, 456px-high capsule on the right; center a simple 140px outline emblem. For the protection variant, layer three concentric translucent grey discs, approximately 160px, 240px and 340px in diameter, over a pin outline. Keep copy clear on the left.

### Sound field artwork

**Only for:** sensory or audio feature demonstrations

**Use:** A dedicated listening or sensory experience panel.

**Observed:** Black space with a sparse regular field of tiny white dots, a fine glowing circular outline and a vertical blurred band that shifts between cool green and violet. The effect is optical and restrained, not a neon dashboard.

**Transfer:** Use only when the new product has an equivalent sensory capability; represent that sensation with one diagram rather than a decorative background for text.

**Build:** Draw 2px white SVG dots on a widely spaced staggered grid at low opacity. Center a roughly 260px circular white outline with a dim blurred duplicate. Behind it, layer two narrow vertical blurred ellipses in rgba(120,200,180,0.18) and rgba(120,80,220,0.18), extending beyond the panel. Add a tiny white central point.

### Engineering editorial

**Only for:** company and design-story pages

**Use:** Support a sequence of large narrative statements.

**Observed:** Transparent cutaway product imagery, hand-annotated design sketches, archival riding video and paired city photographs alternate with narrow large-type paragraphs on pale grey.

**Transfer:** Use process sketches, real prototypes and in-use material from the new organization. Keep annotations inside the media rather than adding a second ornamental handwriting system.

### Icons

**Observed:** Action arrows are mostly solid 16px SVGs. Menu and shopping controls are about 24px. Larger capability illustrations use 64px monochrome icons; some are 2px or 3px butt-cap outlines. Plus signs and chevrons stay small and unadorned.

**Transfer:** Use monochrome, simple geometric icons that remain legible at 16px; use larger line drawings only as capability emblems. Avoid colorful icon containers.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product opening

**Observed:** A full 1440px × 900px scene fills the first viewport. A giant macro product detail enters from the left and bottom, with a bright ring and soft grey studio field behind a centered narrow title stack. The layers are product image, legibility treatment, white 240px Display name, 96px silver Display-descriptor, 20px Tagline, a small price-and-reassurance row and the white Primary button. The title group occupies the middle third of the scene; 32px separates its major groups and 16px separates the promise from the price. Floating navigation sits above everything near the top. The object is intentionally incomplete, larger than the viewport; all title, support, price and main action are visible within 900px. The charcoal introductory chapter starts below the fold.

**Transfer:** Stage a functional detail of the new product at similarly monumental scale and reserve a calm area for the centered type. With no film or 3D, use one well-lit macro still plus Functional light field. An editorial page instead opens with a 64px left title on pale grey and an inset wide image below; a service page opens with a 48px or 64px left title and an engineering diagram or full-product image to the right.

**Avoid:** Do not reduce the object to a small catalog cutout beside a left-aligned SaaS headline, and do not use a long slogan at 240px.

**Text style:** `display` — Unica77LLWeb 400 · 240px/0.8 · tracking -0.04em

### Centered chapter introduction

**Observed:** Dark narrative holds a centered 716px column: Heading at 48px, then Body at 18px/28px with a 16px gap. A 120px pause can precede it; the wide film follows after 80px. Short quotations and mono attribution labels can add proof below an introductory promise.

**Transfer:** Use this heading-and-support pair to introduce a capability in terms of what the user feels, then prove it with imagery.

**Text style:** `heading` — Unica77LLWeb 400 · 48px/1.1

### Wide demonstration and offset detail

**Observed:** A nearly 16:9 film fills the inner ten-column width. A 48px separation leads to an explanation aligned to the right half: Eyebrow, 32px benefit heading and Body, each separated by 16px. Further detail appears in paired image/caption columns or a clipped horizontal rail using Feature caption.

**Transfer:** Alternate immersive evidence with one compact explanation; the offset prevents every section becoming a centered stack.

### Display statement

**Observed:** A 716px central column contains a left-aligned 48px/1.1 sentence built from separate word spans, with approximately 10px word/line gaps. Dark services reverse it to white; editorial narratives use charcoal on pale grey. Words can progress through dim grey to full contrast as the reader advances.

**Transfer:** Use a concise connected argument rather than a list of isolated slogans. Keep it narrower than the surrounding media.

**Text style:** `heading` — Unica77LLWeb 400 · 48px/1.1

### Split editorial proof

**Observed:** A 716px × 534px image occupies the left of the standard container, while a narrower right column centers vertically around an Eyebrow, 48px heading, 16px/24px paragraph and Square arrow link. Imagery can be an understated map or documentary partnership image.

**Transfer:** Use for supporting context, availability or an ecosystem relationship without creating another full-width cinematic chapter.

### Objection handling

**Observed:** A light rule starts a two-part header: 48px heading on the left, a short 18px explanation and compact Square arrow link on the right. Below, FAQ rows fill the 1199px content width with 8px gaps. Dark services retain the same geometry with dark borders and reversed text.

**Transfer:** Answer practical questions after the product and options are clear; use authentic buyer concerns rather than feature repetition.

### Community and utility closing

**Observed:** Every page ends on a 724px-tall white footer. A 32px community heading occupies the left of the first band; three 64px square photos and a fourth arrow tile sit at the right. A light rule separates this from the newsletter and navigation. The newsletter has an uppercase mono label, 24px invitation and Outline button; three compact navigation groups sit opposite. The bottom utility row uses 12px/16px links with locale aligned right. Footer top and bottom insets are 64px and 48px.

**Transfer:** End with a real community or editorial image strip and a restrained subscription invitation, then useful navigation. Keep this white closing even after an entirely dark service story.

### Service capability stack

**Only for:** subscription landing pages

**Observed:** Three viewport-scale Demonstration black panels layer during scrolling. Each has a large line icon at upper left, a small progress marker on the far left, then a three-digit Eyebrow number, 32px heading, Body and Square arrow link near the lower left. The right half is dominated by an interface visualization.

**Transfer:** Use one stage per significant capability; replace screen internals with authentic new-product examples and preserve the large areas of black.

### Comparison desk

**Only for:** product selection and technical buying sections

**Observed:** White desk sits inside the light canvas with 8px corners and 120px top space. A centered 96px heading and 18px support precede equal model columns, isolated product views, 64px model names and Finish swatches. Fine rules separate comparable characteristics. A related specifications panel uses a 48px left heading, 20px list rows and 48px vertical row insets.

**Transfer:** Keep choice data calm and aligned after the sensory product story. Compare the new product's real options without turning the section into a brightly emphasized pricing table.

**Text style:** `comparison-heading` — Unica77LLWeb 400 · 96px/1

### Service plans and process

**Only for:** service landing pages

**Observed:** Dark narrative supports a three-column process row with 24px titles, grey numbers, thin translucent top and vertical rules and 16px/24px copy. Plan cards follow in two or three columns, using outlined badges, benefit separators and full-width Outline buttons.

**Transfer:** Show the mechanism before asking the reader to pick a plan; separate reassurance from the price.

### Related destination mosaic

**Only for:** editorial and multi-offer page endings

**Observed:** Destination tiles form a tall 595px × 794px left panel beside two 595px × 393px right panels, separated by 8px. Large titles sit at the top; support and arrows pin to the bottom. Service endings can use two equal landscape photographic tiles instead.

**Transfer:** Offer a small set of genuinely different next steps: explore, experience or get help.

## Page flow

**Storyline:** Sensory promise → evidence of the product → capability chapters → evaluation and reassurance → useful next steps → community and utility.

### Flagship product landing

1. **Promise** — Full-screen macro product scene with monumental name, short promise, price and purchase action.
2. **Credibility** — Centered product argument and brief editorial quotations.
3. **Product demonstration** — Large beauty views, paired macro details and a finish/model viewer.
4. **Capability chapters** — Repeated short benefit introduction, wide demonstration, offset explanation and image-caption rail.
5. **Emotional refrain** — Full-screen real-use films and a pale image-punctuated phrase reconnect engineering to experience.
6. **Evaluation** — Light comparison desk, technical sheet, ecosystem proof and accessory grid.
7. **Objection handling** — Outlined FAQ rows.
8. **Closing** — White community, newsletter and utility footer.

**Transfer:** Make the new product feel tangible before presenting its specification and buying choices; adapt chapter count to the product.

### Multi-offer marketing home

1. **Promise** — A linked photographic launch panel with a left monumental name and a compact right explanation.
2. **Benefit** — Another full-width cinematic panel with a 48px heading and arrow action.
3. **Product ecosystem** — Pale showcase panel with a large centered heading, four icon explanations and a wide product-use image.
4. **Identity** — Documentary motion panel with a short statement.
5. **Social proof** — Press quote row with publisher identity and compact carousel controls.
6. **Next steps** — Asymmetric destination mosaic.
7. **Closing** — White shared community and navigation footer.

**Transfer:** Curate offers as large linked image scenes, not a wall of equally sized cards.

### Assurance service landing

1. **Promise** — Dark full-product image with a layered protective emblem and left-aligned copy.
2. **Reassurance** — Large narrow-column statement and three-step process.
3. **Emotional proof** — Near-full-width documentary product-use image.
4. **Pricing** — Three equal outlined cards distinguishing included capability and paid terms.
5. **Objection handling** — Two concise explanatory columns, light availability split and outlined FAQs.
6. **Next steps** — Two landscape photographic destination tiles.
7. **Closing** — White shared community footer.

**Transfer:** Explain the mechanism and concrete conditions of a less tangible offer before pricing; retain the dark-to-light practical transition.

### Capability subscription landing

1. **Promise** — Black engineering-diagram hero with left title and trial action.
2. **Demonstration** — Centered 48px statement and large illustrative video.
3. **Argument** — Narrow 48px paragraph explaining the extra layer of value.
4. **Capability chapters** — Sticky black stages with large icons, numbered captions and interface demonstrations.
5. **Breadth** — Three compact ruled feature columns.
6. **Evaluation** — Base-versus-upgrade explanation followed by two equal outlined term cards.
7. **Objection handling** — Dark accordion section.
8. **Closing** — White shared community footer without an intervening destination mosaic.

**Transfer:** Use diagram-led visuals for invisible functionality while keeping benefits readable outside the interface demos.

### Editorial company or design story

1. **Orientation** — Plain 64px title on pale canvas, followed by a large cutaway product image.
2. **Narrative** — Alternation of narrow 48px statements and wide archival, process or documentary media.
3. **Renewal** — Further display statements supported by paired photography and product-engineering films.
4. **Next steps** — Asymmetric three-tile destination mosaic.
5. **Closing** — White shared community footer.

**Transfer:** Use large statements as an editorial voice, with real process material as proof rather than a generic timeline.

## Writing

Confident, sensory and direct, with understated wit. Engineering is expressed as a feeling in everyday use, then supported with concrete mechanism and conditions.

**Do not copy:** Do not reuse VanMoof names, identity artwork, proprietary feature names, partner names, prices, awards, quotations, theft statistics, warranty promises or service guarantees. Source examples below illustrate voice only; replace them with verified claims and language for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use 'we' for the maker's intent and responsibility. Give the product agency in short metaphors without losing factual meaning.
- **Rhythm:** Headlines are usually two to six words, often two clipped clauses. Support alternates a short emotional sentence with a practical explanation. Longer display paragraphs remain conversational rather than ceremonial.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A short assertion of a distinctive experience. | 3–6 words | “Ride like no other” |
| Chapter heading | Benefit first, with a repeated syntactic hook or two-beat contrast. | 3–7 words | “Worry less. Ride more.”<br>“Eyes lock. You roll.” |
| Supporting line | A human analogy followed by the specific capability. | 1–3 sentences | “Riding the S6 series is like having a co-pilot, minus the small talk.” |
| Detail title | Wordplay turns a mechanism into a benefit. | 2–7 words | “Connection, no exception”<br>“Forget turbulence” |
| Primary action | Short literal verb phrase, with a clear commitment. | 2–5 words | “Buy now”<br>“Start 14-day free trial” |

**Words and phrasing to use:** built in; flow; glide; reimagined; more; no compromises; your; in seconds

**Avoid:** synergy; revolutionary solution; leverage; unlock your potential; best-in-class platform; excessive exclamation marks

**Rules:**

- Introduce the lived benefit before naming its mechanism.
- Use small moments of dry humor, not a joke in every paragraph.
- Pair evocative language with concrete conditions in service and pricing copy.
- Keep action labels literal even when nearby headlines are playful.
- Use repetition as a chapter rhythm, not as identical filler across every section.

## Do's and Don'ts

### Do

- Keep the cinematic name at regular weight, 240px/0.8 with -0.04em tracking for short names.
- Keep body copy in a narrow 716px narrative column rather than stretching it across the full media width.
- Use 8px gutters so adjacent product images read as a connected contact sheet.
- Separate major chapters with 120px–200px of unadorned canvas.
- Use a white 40px-high purchase button and 48px outlined secondary actions.
- Keep capability labels at 14px uppercase monospace and ordinary chapter headings at 48px/1.1.
- Let studio reflections and a localized luminous detail give the object depth.
- Retain the white community footer with a compact image strip, newsletter and utility navigation.

### Don't

- Do not replace regular grotesk headings with heavy bold display type.
- Do not convert 4px-corner action buttons into rounded pills.
- Do not turn blue or mint product finishes into broad navigation or pricing fills.
- Do not add floating-card shadows to every product image or FAQ row; the panels are flat.
- Do not make ordinary labels widely letter-spaced; their tracking is normal.
- Do not give every chapter a different colored card background; the charcoal narrative is continuous.
- Do not use uniformly bright, sanitized stock photography in place of low-light studio and lived-in street imagery.
- Do not inflate the footer into a giant slogan-only ending; it is an organized white utility space.

## Motion and responsive

### Motion

**Observed:**

- Product imagery alternates with full-width video; subscription capability panels are sticky and layer as the reader scrolls.
- Declared action or surface transitions include all 0.6s cubic-bezier(.4,0,.2,1) and all 0.5s cubic-bezier(.4,0,.2,1).
- A declared slideUpFadeInDesktop animation uses 0.4s ease-out with a 1s delay and forwards fill.
- Destination-tile images declare a 700ms ease-in-out transition and scale to 1.05 on group hover.
- Large narrative statements visibly mix dim and full-contrast words.

**Transfer:**

- Use motion to move between product scale and lived experience, not to animate every small control.
- Keep sticky demonstration chapters tied to one capability at a time; provide a readable static frame when motion is unavailable.

**Unknown:**

- Exact scroll-linked interpolation, film timing, statement-reveal thresholds and complete focus-visible behavior are not defined.

### Responsive

**Observed:**

- Declared width breakpoints include 400px, 425px, 426px, 476px, 530px, 550px, 600px, 640px, 768px, 896px, 1024px, 1280px and 1920px.
- Layout classes switch the full-width narrow navigation to a 600px bar at tablet sizes, use 24px narrow-layout text padding, and move paired desktop captions into different narrow-layout treatments.
- Feature rails declare 90% card width in narrow layouts and 50% at tablet sizes; service plan cards declare a narrow-layout minimum width of 80vw.

**Transfer:**

- On narrow screens, keep the product detail oversized and the title legible without pushing the main action behind the fold.
- Preserve a visible next-card sliver in horizontally scrolling feature and plan rails rather than shrinking three columns to fit.
- Stack the image-punctuated phrase around its square image when a horizontal sentence no longer fits; retain the image as punctuation.

**Unknown:**

- Exact rendered mobile type sizes, mobile film framing and expanded menu composition are not defined.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
