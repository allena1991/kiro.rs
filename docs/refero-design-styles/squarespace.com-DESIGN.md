# Squarespace — ambition on a stage

## Overview

An image-led, cinematic style that gives practical business software the feeling of a design studio. Light grotesk headlines and occasional fine serif accents sit against black, white and earthy brown, with rich photography and floating interface compositions supplying most of the color. Spacious storytelling surrounds compact, matter-of-fact copy; it suits creative tools, commerce platforms and products that turn personal ambition into tangible work.

### Essentials

- The promise sits inside the scene, not beside it: a centered two-line 64px/1.04 light headline with -0.06em tracking overlays full-bleed cinematic photography; overlapping output panels enter the bottom of the first screen.
- Headlines have the density of a wordmark without becoming bold: weight 300 at display sizes, weight 400 at 40px/1.08 section headings, and tightly negative tracking contrast with 15px/1.4 body copy.
- Conversion is a small architectural rectangle: white on black, 60px tall, 4px corners, 23px 28px padding and 14px uppercase medium labels; secondary actions use a 2px inset translucent edge.
- Color belongs primarily to the work: broad black and white chapters frame richly colored media. Keep ordinary interface chrome monochrome; earthy full-width bands belong to extended capability stories and blue is reserved for pricing emphasis.
- Product proof is art-directed, never a bare dashboard dump: use photographic or tactile backings, isolated interface fragments, 8px media corners and 40px gutters. When no product imagery exists, stage a credible sample output over warmly lit materials.
- A black theatrical interlude makes the system feel bigger than a grid: arrange floating work panels around a compact mixed-serif/sans title, and include a fine white particle sphere behind a conversion statement. Rebuild these as perspective cards and SVG dots when cinematic assets are unavailable.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-white` | background, text, action | Light capability chapters, primary buttons and text on dark stages. |
| Stage black | `#000000` | `--color-black` | background, text, action | Default dark stage, dark text on white and inverted actions. |
| Charcoal backing | `#2f2f2f` | `--color-card` | surface | Base backing for full-image capability cards, not a substitute for their imagery. |
| Dark edge | `#5a5a5a` | `--color-edge` | border | Outlined support cards on black. |
| Secondary gray | `#898989` | `--color-muted` | text, border | Footer links and secondary explanatory copy. |
| Light rule | `#dddddd` | `--color-soft-rule` | border, text | Fine media-control edges, soft text and primary-button hover fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| creative portfolio landing pages | Portfolio umber | `#34281d` | `--color-umber` | background | Brown foundation for a creative-product feature chapter. |
| extended service capability stories | Earth chapter | `#352b24` | `--color-earth` | background | Warm dark foundation under sustained photographic capability stories; keep the visual atmosphere earthy and subdued. |
| pricing pages | Recommendation blue | `#0072f0` | `--color-blue` | accent, text, surface | Small recommended-plan badge and annual savings line; not a general marketing accent. |
| AI entrypoint labels | Pearl sky | `#88bcd8` | `--color-sky` | accent | A narrow highlight passing through small editorial labels, surrounded by white. |
| creative portfolio closing scenes | Copper atmosphere | `#6e3822` | `--color-glow` | accent, background | Blurred light behind the final framed product image. |
| AI entrypoint labels | Pearl lemon | `#f3ffc1` | `--color-lemon` | accent | Pale yellow highlight within the same small pearlescent text sweep. |
| testimonial mosaics | Warm quote | `#221f1a` | `--color-quote-warm` | surface | First testimonial tile, tonally related to its portrait. |
| testimonial mosaics | Blue charcoal quote | `#19242e` | `--color-quote-blue` | surface | Dark blue testimonial tile paired with underwater photography. |
| testimonial mosaics | Olive quote | `#26271f` | `--color-quote-olive` | surface | Muted olive testimonial tile beside environmental photography. |

## Typography

- **Clarkson** — All core marketing text, navigation, numerals and actions. Clean contemporary grotesk; light display cuts, compact medium labels and very tight large-size spacing. If unavailable, use **Inter**. Use 300, 400 and 500; retain the tight display tracking. Font stack: "Clarkson", "Inter", Helvetica, sans-serif.
- **Clarkson Serif** — Editorial contrast in the floating-work interlude; chapter and closing titles in the AI product variant. Fine high-contrast editorial serif with compact proportions. If unavailable, use **Bodoni Moda**. Use the lightest available cut and tune width before changing size. Font stack: "Clarkson Serif", "Bodoni Moda", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Clarkson | 300 | 64px | 1.04 | -0.06em | fixed | Default centered cinematic opening promise. |
| closing | Clarkson | 300 | 56px | 1.08 | -0.04em | size clamp(56px, 0.125rem + 3.75vw, 74px) | Centered final conversion statement; also a compact light pricing opening. |
| heading | Clarkson | 400 | 40px | 1.08 | -0.04em | fixed | Section leads, broad accordion headings and compact proof statements. |
| editorial-accent | Clarkson Serif | 300 | 40px | 1.08 | -0.04em | fixed | Short first line of a mixed-serif/sans floating-work title. |
| subheading | Clarkson | 400 | 26px | 1.08 | -0.02em | fixed | Support card titles and footer tagline. |
| card-heading | Clarkson | 500 | 20px | 1.2 | -0.01em | fixed | Capability card titles and individual FAQ questions. |
| body | Clarkson | 400 | 15px | 1.4 | -0.001em | fixed | Support paragraphs, feature descriptions and tab labels. |
| body-medium | Clarkson | 500 | 15px | 1.4 | -0.001em | fixed | Brief reassurance beneath conversion statements. |
| action | Clarkson | 500 | 14px | 1 | normal, uppercase | fixed | Navigation labels and rectangular conversion actions. |
| footer | Clarkson | 400 | 13px | 1.4 | normal | fixed | Dense footer taxonomy headings and utility text. |
| caption | Clarkson | 400 | 12px | 1.4 | normal | fixed | Capability-card descriptions, stat labels and small attributions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and service overview pages | monumental-closing | Clarkson | 300 | 100px | 1.04 | -0.05em | size clamp(100px, 2.5rem + 4.16667vw, 120px) | Left-aligned two-line final invitation on a plain black band. |
| creative portfolio landing pages | flagship-display | Clarkson | 300 | 72px | 1.04 | -0.05em | fixed | Longer centered product promise and corresponding closing statement. |
| AI product launches | compact-logo-display | Clarkson | 300 | 72px | 0.88 | -0.055em | fixed | Stacked two-word product title at the center of the particle stage. |
| AI product launches | editorial-closing | Clarkson Serif | 300 | 72px | 1.04 | -0.05em | fixed | Short final invitation over an animated particle scene. |
| AI product launches | editorial-heading | Clarkson Serif | 300 | 64px | 1.04 | -0.06em | fixed | Large two-line capability chapter leads. |
| testimonial mosaics | quote | Clarkson | 400 | 22px | 1.2 | -0.02em | fixed | Readable testimonial quotations with small attribution anchored below. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The display is light, not heavy; tracking tightens from almost neutral body text to -0.04em through -0.06em on headings.
- Do not spread uppercase labels with fashionable wide tracking: the action recipe uses normal letter spacing.
- The serif supplies deliberate editorial contrast rather than replacing the default sans across the page. Keep body text sans even in serif-led chapters.

## Layout

**Density:** Airy section pacing with compact text and controls: media carries the area while prose stays short.

### Spacing

**Spacing system:**

- **gutter** 16px, horizontal — Declared grid gutter used by the four-plan comparison; other chapter grids use 40px.

| Value | Use |
| --- | --- |
| 8px | Card title-to-caption gap and footer link-list gap. |
| 12px | Compact flex groups and feature title-to-description spacing. |
| 16px | Pricing gutters, stat numeral-to-label gap and compact copy group spacing. |
| 24px | Capability-card padding, heading-to-body gap and footer group separation. |
| 32px | Quote tile padding and FAQ row vertical padding. |
| 40px | Default side inset, chapter column gutters and conversion stack gaps. |
| 56px | Flagship hero title-to-action spacing. |
| 80px | Section heading-to-media gap and chapter lower spacing. |
| 120px | Main section vertical padding and proof-stat spacing. |
| 240px | Default cinematic opening text top padding and deep transition breathing room. |

### Containers and grids

- **desktop-content**: max width 1360px · side padding 40px. Desktop working area within a 1440px viewport; full-bleed stages escape this inset. Treat this as the reference width rather than an unverified global maximum.
- **heading-pair**: 2 columns · gap 40px. Two equal 660px columns; heading on the left, body and optional outlined action on the right. Text within either column is usually limited to 543px.
- **capability-rail**: 4 columns · gap 40px. Four visible 310px by 420px image cards; further cards continue horizontally.
- **centered-conversion**: max width 660px · side padding 40px. Narrow centered headline, reassurance and action inside a full-width scene.
- **pricing-grid** (only for pricing pages): 4 columns · gap 16px · side padding 40px. Four equal 328px plan cards with aligned headings, prices, actions and capability groups.
- **testimonials** (only for testimonial mosaics): 3 columns · gap 40px. Three 427px columns alternating quotation and photograph in staggered heights.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | image cards | 8px |
|  | media controls | 50% |
| pricing pages | plan cards | 24px |
| pricing pages | segmented controls | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing pages | plan-card | `rgba(0, 0, 0, 0.03) 0px -1px 30px 0px, rgba(0, 0, 0, 0) 0px 225px 63px 0px, rgba(0, 0, 0, 0) 0px 144px 58px 0px, rgba(0, 0, 0, 0.02) 0px 81px 49px 0px, rgba(0, 0, 0, 0.03) 0px 36px 36px 0px, rgba(0, 0, 0, 0.03) 0px 9px 20px 0px` | Diffuse elevation on white, with stronger depth for the recommended plan. |

### Surfaces

#### Black stage · level 0

**Use:** Core page stage, media interludes, questions, conversion and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Pure black allows imagery to float without a visible panel boundary.

**Transfer:** Use as a theatrical canvas rather than a near-black application shell.

#### White gallery · level 0

**Use:** Light capability and browsing chapters.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Clean white interrupts the black narrative with clear product browsing.

**Transfer:** Give the light chapter a substantial area rather than scattering white cards on black.

#### Media card backing · level 1

**Use:** Backing beneath full-bleed product illustrations.

**CSS:** `background: #2f2f2f; border-radius: 8px; overflow: hidden`

**Observed:** Artwork covers the backing; text and a corner arrow overlay the artwork.

**Transfer:** Compose a photographic product scene that fills the panel.

#### Hero fade · level 1

**Use:** Blend full-bleed opening photography into the dark proof region.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0) 70%, #000000 100%)`

**Observed:** The fade occupies the photographic stage without becoming a separate decorative stripe.

**Transfer:** Keep the upper image legible and reserve the stronger black for its bottom edge.

#### Earth capability band · level 0

**Only for:** extended service capability stories

**Use:** Long-form capability chapters.

**CSS:** `background: #352b24; color: #ffffff`

**Observed:** Warm dark terrain continues beneath multiple editorial media grids; its visual tone shifts through subdued olive and taupe.

**Transfer:** Keep a low-luminance earth tone beneath warm materials and cream interface fragments.

#### Copper closing glow · level 1

**Only for:** creative portfolio closing scenes

**Use:** Atmosphere behind the last framed demonstration.

**CSS:** `background: #6e3822; border-radius: 700px; filter: blur(150px)`

**Observed:** A wide soft ellipse, 1440px by 545px, bleeds behind the top of the framed product image and fades into black.

**Transfer:** Place the glow behind the object rather than making the entire closing section orange.

## Components

### Global navigation

**Use:** Persistent site-level orientation and conversion.

**CSS:** `position: fixed; height: 80px; padding: 0px 40px; display: flex; justify-content: space-between; align-items: center; background: rgba(0, 0, 0, 0.52); color: #ffffff`

**Text style:** `action` — Clarkson 500 · 14px/1 · uppercase

**Observed:** Logo at left, three compact menu groups centered, login and Primary button at right. The black header reads solid over lower black chapters; pricing opens with a light treatment.

**Transfer:** Use a restrained wordmark and a short taxonomy; preserve the strong right-hand action.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; background: #ffffff; color: #000000; border-radius: 4px; padding: 23px 28px; height: 60px`

**Text style:** `action` — Clarkson 500 · 14px/1 · uppercase

**Observed:** Label is visually centered; a right arrow is reserved within the action and may reveal through label movement. Pricing plan cards invert to black fill and white text.

**States:** Declared: hover background-color #ddd; focus-visible outline 2px solid #087bb5 with outline-offset 3px on the pricing implementation.

### Secondary button

**Use:** Chapter exploration without competing with the main conversion.

**CSS:** `display: flex; justify-content: center; align-items: center; color: #ffffff; background: transparent; border-radius: 4px; padding: 23px 28px; height: 60px; box-shadow: rgba(255, 255, 255, 0.2) 0px 0px 0px 2px inset`

**Text style:** `action` — Clarkson 500 · 14px/1 · uppercase

**Observed:** Outline reads softly against dark scenes; the light-section variant uses a black translucent inset edge. Often aligned under support copy or at the right of a chapter heading.

### Capability card

**Use:** Clickable visual overview in a horizontal rail.

**CSS:** `width: 310px; height: 420px; padding: 24px; border-radius: 8px; background: #2f2f2f; color: #ffffff; position: relative; overflow: hidden`

**Text style:** `card-heading` — Clarkson 500 · 20px/1.2 · tracking -0.01em

**Observed:** Full-panel art behind a top-left title and caption; a 22px right arrow sits bottom-right. Caption uses caption type. Four visible cards are separated by 40px, with dots centered and circular arrow controls below.

**Transfer:** Show one distinctive product benefit per illustrated scene, not a generic icon and paragraph.

### Chapter accordion

**Use:** Compact access to long educational and reassurance content.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 40px; background: #000000; color: #ffffff`

**Text style:** `heading` — Clarkson 400 · 40px/1.08 · tracking -0.04em

**Observed:** Full-width row with a far-right plus and a thin translucent separator. Closed single-line rows are 123px high; this is a large section-level control, not an individual question.

### Support card

**Use:** Two broad destinations for help or learning.

**CSS:** `border: 1px solid #5a5a5a; border-radius: 8px; padding: 30px; height: 299px; color: #ffffff; display: flex; flex-direction: column`

**Text style:** `subheading` — Clarkson 400 · 26px/1.08 · tracking -0.02em

**Observed:** Title and short body align at the top-left; large empty breathing room precedes a bottom-right arrow. Two equal cards span the inset content area.

**States:** Declared: hover border-color #fff; focus-visible outline 2px solid #087bb5 with outline-offset 3px.

### Footer columns

**Use:** Dense navigation after the conversion scene.

**CSS:** `display: grid; grid-template-columns: repeat(4, 1fr); column-gap: 40px; color: #898989`

**Text style:** `footer` — Clarkson 400 · 13px/1.4

**Observed:** Four 190px columns sit to the right of a wider brand-and-tagline area. White category headings have 16px space before gray links; link lists use 8px gaps. A 1px translucent divider separates the lower language and legal row.

**Transfer:** Use actual product taxonomy; retain the wide identity area and compact directory rather than an oversized closing logo.

### Question row

**Only for:** detailed FAQ sections

**Use:** Individual question within a right-column FAQ list.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 32px 0px; color: #ffffff`

**Text style:** `card-heading` — Clarkson 500 · 20px/1.2 · tracking -0.01em

**Observed:** A 16px plus anchors the far right; thin horizontal rules separate questions. Single-line rows are about 88px, with extra height for wrapping. Answers use body type when open.

**Transfer:** Keep the section heading isolated in the left column; do not turn each question into a rounded card.

### Plan card

**Only for:** pricing pages

**Use:** Parallel comparison of subscription tiers.

**CSS:** `background: #ffffff; color: #000000; border-radius: 24px; padding: 32px 32px 40px; display: grid; gap: 40px`

**Text style:** `card-heading` — Clarkson 500 · 20px/1.2 · tracking -0.01em

**Observed:** Tier name, concise positioning, 40px price, black Primary button, then grouped icon-and-text features. The recommended tier receives a small blue pill and stronger diffuse shadow. Align corresponding content across all four columns.

**Transfer:** Use only truthful tier distinctions; preserve the visual alignment rather than the original card length.

### Billing toggle

**Only for:** pricing pages

**Use:** Annual/monthly pricing selection.

**CSS:** `display: flex; padding: 4px; border-radius: 9999px; background: rgba(0, 0, 0, 0.05); height: 61px`

**Text style:** `body` — Clarkson 400 · 15px/1.4 · tracking -0.001em

**Observed:** Two nearly equal options inside a gray pill; active option is a white 53px-high pill with a compact soft shadow. The pricing accent stays in the savings line and recommended badge.

### Search field

**Only for:** search-led acquisition sections

**Use:** One focused discovery task within a black chapter.

**CSS:** `width: 660px; height: 62px; border-radius: 8px; background: rgba(255, 255, 255, 0.2)`

**Text style:** `body` — Clarkson 400 · 15px/1.4 · tracking -0.001em

**Observed:** Centered beneath a 40px heading with a search icon at left and an action at right; a small underlined alternative follows below.

**Transfer:** Use this only when the product has a meaningful search or lookup task.

### Quote tile

**Only for:** testimonial mosaics

**Use:** Customer proof paired with real portrait or place photography.

**CSS:** `background: #221f1a; border-radius: 8px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 80px; color: #ffffff`

**Text style:** `quote` — Clarkson 400 · 22px/1.2 · tracking -0.02em

**Observed:** Quotation above a 12px attribution; alternate dark olive and blue-charcoal fills echo adjacent photographs. Three staggered columns alternate image and quote order.

**Transfer:** Pair each quotation with its own subject and related tone rather than making a uniform row of identical testimonial cards.

## Imagery and graphics

### Cinematic human work

**Use:** Default opening scene and category storytelling.

**Observed:** Warm low-key footage of people absorbed in work: a reader, makers at a table, plants, movement, tactile interiors. Framing is intimate and editorial, with directional light, soft shadows and subdued cream, olive, rust and black. The scene fills the viewport while text occupies a small central portion.

**Transfer:** Photograph a credible user doing the activity the new product enables. If original film is unavailable, use a single high-quality still with the same directional light and a strong quiet center for text.

### Floating output panels

**Use:** Opening proof and black theatrical work interludes.

**Observed:** Opening output panels overlap the lower photo, the central 660px panel larger and brighter than cropped side panels. A later black stage surrounds a small two-line title with a room-like field of finished work, angled toward the viewer and faded at the edges.

**Transfer:** Create original representative outputs and stage them as planes. For a nonvisual product, use a finished report, workflow result or customer deliverable rather than a wall of navigation chrome.

**Build:** Use a perspective container on black with roughly three rows of rectangular output planes; keep a clear center for the title, rotate side planes inward around the Y axis, scale far planes down and darken their opacity. Add transparent-to-black top and bottom overlays. The opening version uses three overlapping flat panels, a centered 660px main panel and smaller 593px side panels with 8px corners.

### Tactile interface composites

**Use:** Capability cards, split media grids and wide product demonstrations.

**Observed:** Cream forms, receipts, editor windows and small status cards float above photographs of stone, fabric, ceramics, warm wood and people. Some compositions use sculptural copper or folded material backdrops. Main grids use 660px-wide images or one 1360px-wide panorama; content is more image than text.

**Transfer:** Choose two or three believable UI fragments demonstrating one outcome, then layer them over a real material or use-context image. Retain generous negative space and coherent shadows; minimum acceptable version is a well-lit still plus one crisp output panel.

### Particle sphere

**Use:** Signature atmospheric conversion scene; expanded into a product identity stage for AI launches.

**Observed:** Thousands of tiny white points describe a loose spherical volume on pure black, with uneven brightness and denser overlapping front/back edges. The centered closing statement remains the brightest and sharpest layer; the object occupies roughly the central half of the page width.

**Transfer:** Keep the sphere as a neutral field of possibility, independent of product-specific iconography. Use a static SVG sphere if real-time art is impractical.

**Build:** Generate SVG circles distributed on a 3D sphere, project to an approximately 760px circular field at desktop, and vary radius around 0.5px–1.5px and white opacity from 0.15 to 0.85 by depth. Slightly perturb positions for an organic cloud; avoid latitude lines. Place white text and the Primary button above the dots, leaving black margins. For the AI launch variant surround it with a few perspective output cards and translucent tool strips.

### Pearlescent label sweep

**Only for:** AI entrypoint labels

**Use:** Small editorial accent within black image-entrypoint cards.

**Observed:** A narrow sky-blue and pale-lemon sheen passes through otherwise white 12px text; it is not a large gradient headline.

**Transfer:** Restrict the colored sweep to a short label so the media remains dominant.

**Build:** Clip a 90deg linear gradient to text: white at 29.4%, sky at 40%, lemon at 61%, white at 71.6%; set background-size to 300% auto. The base stays white and the colored band stays narrow.

### Customer portrait mosaic

**Only for:** testimonial mosaics

**Use:** Proof with individual personality and environment.

**Observed:** Portrait against terracotta texture, a warmly lit venue and an underwater swimmer alternate with dark quotation tiles. Images retain natural rich color, 8px corners and discreet 12px corner captions.

**Transfer:** Use real people, places or outcomes tied to each quote; let the images vary in subject and height while keeping three aligned column tracks.

### Icons

**Observed:** Small filled SVG shapes provide restrained functional cues: 16px navigation chevrons and FAQ plus signs, 22px right arrows on image cards, and 30px circular play/pause or carousel controls. White on dark and gray in pricing feature lists.

**Transfer:** Choose simple monochrome directional and utility symbols; avoid colorful illustrated feature icons outside the product scenes.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise opening

**Observed:** A full-width 1440px by 900px photographic stage sits on Black stage with Hero fade at its base. Global navigation overlays the top 80px. Center a compact two-line display promise in the upper-middle, beginning after 240px of top breathing room; use display type in white. A Primary button follows 32px below the headline, with one body reassurance 24px below the button. The image remains visible all around the text. Floating output panels enter near the lower third: central 660px by 412px work panel flanked by dimmer 593px by 383px panels that extend off both edges. Within the first 900px the navigation, complete promise, action, reassurance and upper output panels are visible; the proof sentence and three statistics continue below the fold.

**Transfer:** Make the main scene about the new customer's activity, then overlap original outputs that make the promise tangible. Without film, combine an editorial still and three staged sample outputs. A pricing page instead opens compactly on white with a 56px headline, savings line and billing toggle; a creative flagship uses a 72px promise and framed demonstration; an AI launch uses a centered particle identity stage.

**Avoid:** Do not replace the image stage with a generic left-text/right-dashboard split, a giant bold slogan, or a flat gradient background.

**Text style:** `display` — Clarkson 300 · 64px/1.04 · tracking -0.06em

### Proof numerals

**Observed:** A centered proof sentence bridges the opening media to three light 64px stat values on black. Each has a small caption 16px below, with 120px between stat groups and 120px lower padding. Numeric suffixes stay attached and the large values share a baseline.

**Transfer:** Use independently verifiable measures of scale, output or reach. Preserve the uncluttered typographic treatment even when only two meaningful metrics exist.

**Text style:** `display` — Clarkson 300 · 64px/1.04 · tracking -0.06em

### Section heading pair

**Observed:** Within desktop-content, a heading-pair places a 40px heading left and 15px support copy right, both top-aligned. Heading and body measure about 543px within 660px columns; media follows after 80px. Centered gallery introductions instead stack a heading and support with 24px separation.

**Transfer:** Explain a customer outcome on the left and the concrete mechanism on the right; follow with Capability cards or Tactile interface composites.

**Text style:** `heading` — Clarkson 400 · 40px/1.08 · tracking -0.04em

### Gallery capability browsing

**Observed:** White gallery carries a centered heading, short support, compact category tabs and a wide photographic carousel with partially visible neighbors. Another version uses the heading-pair over four Capability cards and circular controls beneath.

**Transfer:** Use tabs for genuine categories, and keep adjacent content visible to suggest breadth without shrinking the main example.

### Light to dark entrypoints

**Observed:** A centered 40px heading opens on white; a soft photographic earth-toned atmosphere transitions downward into black. Two 427px-wide black cards with 8px corners contain media above centered small labels, muted body copy and short directional links. A short recognition line sits below.

**Transfer:** Use for two meaningful paths into a product, such as guided creation versus starting from an example; keep the paths in the same visual family.

### Work theater

**Observed:** A full-width 820px black scene arranges floating output panels around a centered mixed-serif/sans two-line title. Darkened media and top/bottom fades keep the title legible.

**Transfer:** Make this an immersive proof pause, not another feature grid. Use original deliverables and a short statement of what customers can make.

**Text style:** `editorial-accent` — Clarkson Serif 300 · 40px/1.08 · tracking -0.04em

### Objections and assistance

**Observed:** Chapter accordion provides broad closed learning/support rows. Detailed variants place a 40px left heading opposite a 660px question list; Support cards follow as two outlined destinations with an 80px heading-to-card gap.

**Transfer:** Use the broad accordion for optional deep reading, or the two-column FAQ for a more decision-heavy page; preserve a clear path to human or educational support.

### Atmospheric closing and directory

**Observed:** The default ending is a 900px Black stage with Particle sphere behind a centered closing headline limited to 660px, brief medium reassurance, and Primary button at 40px intervals. Footer columns then sit beside a wide identity area, with a fine divider and compact legal/language row. The creative flagship ending uses a 72px centered invitation over Copper closing glow and a framed demonstration emerging below. The AI launch closes with a short 72px serif invitation and orbiting media. Pricing and service overviews use a plain black, left-aligned 100px two-line invitation, action and inline reassurance.

**Transfer:** Choose the closing variant by page purpose, keeping a strong final invitation and the dense directory. The atmospheric sphere and floating-work device belong in the overall new-page composition even when the final action itself uses the plain variant.

**Text style:** `closing` — Clarkson 300 · 56px/1.08 · tracking -0.04em

### Earth chapter bento

**Only for:** extended service and creative capability stories

**Observed:** Earth capability band or the umber variant supports repeated chapters with a heading and Secondary button above paired media. Layouts alternate two equal 660px panels, a tall 845px panel beside two 402px panels, and one 1360px by 600px panorama. Copy overlays the top of the image or sits below it; gaps remain 40px.

**Transfer:** Group related capabilities into a coherent customer task, using different panel proportions to sustain a long story rather than an endless identical card grid.

### Editorial AI capabilities

**Only for:** AI product launches

**Observed:** Black stage stays continuous. A 64px serif heading faces body copy and a Secondary button across the heading-pair, followed by a 1360px-wide demonstration. Paired 660px media panels use 20px sans titles and 15px descriptions below; small final capability notes sit beneath thin top rules.

**Transfer:** Use the serif contrast to express creative authorship while concrete demonstrations explain the actual assistance.

**Text style:** `editorial-heading` — Clarkson Serif 300 · 64px/1.04 · tracking -0.06em

### Pricing comparison

**Only for:** pricing pages

**Observed:** Compact centered white introduction leads to Billing toggle and four aligned Plan cards with a 16px gutter. Only the recommended tier has a blue badge and stronger shadow. A secondary feature-list action precedes the transition to Black stage for objections, support and conversion.

**Transfer:** Give each tier a plain-language purpose, consistent feature groups and comparable price baselines; do not import the warm media band into this utilitarian comparison.

## Page flow

**Storyline:** Immersive promise → tangible outputs → breadth of capabilities → focused demonstrations → human or quantified proof → objections and assistance → confident invitation → compact directory.

### Broad platform introduction

1. **Promise** — Human cinematic scene with centered action and overlapping work panels.
2. **Quantified proof** — Three large light numerals beneath a short adoption statement.
3. **Capability breadth** — White browsing gallery, category tabs and illustrated capability rail.
4. **Activation** — Two visual starting paths and a focused lookup task.
5. **Social proof** — Compact portraits and a black floating-work theater.
6. **Objection handling** — Large closed learning, FAQ and support rows.
7. **Closing call** — Particle-backed centered invitation followed by a four-column directory.

**Transfer:** Use when a new product needs both an emotional promise and an overview of a broad ecosystem.

### Commercial plan selection

1. **Offer framing** — Compact white headline, trial line and blue savings cue.
2. **Pricing** — Billing toggle and four tall aligned plan cards, with one recommended tier.
3. **Comparison depth** — Expandable full-feature action.
4. **Objection handling** — Black two-column FAQ and two outlined support destinations.
5. **Closing call** — Monumental left-aligned invitation and standard dark directory.

**Transfer:** Prioritize comparable details and a light purchasing environment before returning to the theatrical dark close.

### Launch a creative technology capability

1. **Product identity** — A particle sphere and orbiting creative fragments surround a compact two-line title.
2. **Positioning** — The same scene develops a short creative philosophy and invitation.
3. **Product demonstration** — Large serif-led heading pair and wide guided demonstration.
4. **Capability chapters** — Paired illustrated tools with concise below-image explanations.
5. **Objection handling** — Serif FAQ heading opposite compact question rows.
6. **Closing call** — Short serif invitation over the returning particle scene, then dark directory.

**Transfer:** Connect an unfamiliar technology to craft and user control, then prove the concrete operations it enables.

### Explain an end-to-end workflow for a customer category

1. **Promise** — Centered benefit over a tiled photographic world of people at work.
2. **Orientation** — Three compact benefit summaries and a large text selector facing an illustrated example.
3. **Audience breadth** — Horizontal photographic category rail.
4. **Capability chapters** — Long earth-tone bento story, alternating paired, asymmetric and panoramic product composites.
5. **Social proof** — Staggered three-column customer quote and photograph mosaic.
6. **Objection handling** — Detailed FAQ and outlined support cards.
7. **Closing call** — Plain black monumental invitation and dark directory.

**Transfer:** Tell a connected workflow rather than listing unrelated tools; vary the media proportions while maintaining the same gutters.

### Promote a creative output use case

1. **Promise** — Warm human photography, serif category label, centered 72px promise and white action above framed output.
2. **Inspiration** — White template/output carousel with a guided-creation alternative.
3. **Capability chapters** — Umber band with asymmetric project tools, paired marketing examples and capability cards.
4. **Activation** — Black floating creative-tool scene with a centered guided-creation invitation.
5. **Objection handling** — Broad learning, FAQ and support accordions.
6. **Closing call** — Centered invitation over copper atmosphere and a rising framed demonstration, followed by dark directory.

**Transfer:** Lead with the quality of the end result and then explain the tools needed to publish, promote and sustain it.

## Writing

Confident, design-aware and practical. The promise is expansive but the supporting language is concrete, warm and focused on work the reader can accomplish.

**Do not copy:** Do not reuse Squarespace names, logos, proprietary product names, customer artwork, quotes, adoption figures, revenue claims, awards, trial terms or pricing. Substitute the new product's own verified facts and assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; name the product when clarifying a capability. The reader remains the author and owner of the result.
- **Rhythm:** Short declarative headlines, often four to nine words. Support is usually one or two compact sentences; short imperative actions and clipped reassurance keep the cadence direct.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An enabling outcome stated simply; broader than a feature name. | 5–10 words | “A website makes it real”<br>“Run your entire business from one place” |
| Section headline | A direct customer benefit, sometimes paired with a short qualifying clause. | 4–9 words | “Everything you need on one platform”<br>“Better results, by design” |
| Supporting line | Explain the task and value in everyday verbs; avoid abstract positioning jargon. | One or two sentences | “You deserve a website that can do it all.”<br>“Ask the right questions upfront so you get the details you need without the back-and-forth.” |
| Primary action | Brief imperative; exploration actions name their destination. | 2–5 words | “Get started”<br>“Build your own with AI” |
| Reassurance | Two factual, clipped statements immediately near an action. | 5–9 words | “No credit card required. Cancel anytime.” |

**Words and phrasing to use:** make; create; your; get started; stand out; in one place; designed; customize; grow; built-in; control

**Avoid:** revolutionary; 10x; disrupt; unlock limitless possibilities; game-changing; enterprise-grade synergy

**Rules:**

- Name the user's task before naming the mechanism.
- Frame automation as assistance that preserves the reader's authorship.
- Keep image captions specific and practical rather than poetic.
- Use facts for reassurance; avoid exclamation marks and urgency tricks.
- Keep section titles in sentence case and reserve uppercase for navigation and rectangular actions.

## Do's and Don'ts

### Do

- Keep default opening type at 64px, weight 300 and -0.06em tracking.
- Use 40px side insets and 40px gutters in editorial chapters.
- Let a main output panel overlap the lower photographic opening rather than isolating it on a separate plain section.
- Use 8px corners on image cards and 4px on rectangular actions.
- Keep body paragraphs at 15px/1.4 and restrict their desktop measure to about 543px.
- Retain a black work-theater moment and fine particle field as signature scenic devices.
- Pair customer quotes with real photography, 32px tile padding and small attribution.
- Use 120px section breathing room while keeping card interiors compact.

### Don't

- Do not substitute heavy 700-weight headings for the light display hierarchy.
- Do not make the main conversion buttons pill-shaped; pills belong to toggles and media-local navigation.
- Do not use recommendation blue as the general page background or primary marketing-button color.
- Do not treat a charcoal card backing as finished artwork; the scene must carry the visual argument.
- Do not add soft card shadows throughout dark chapters; diffuse elevation belongs mainly to pricing on white.
- Do not use the AI variant's serif for ordinary body copy or every section heading.
- Do not inflate captions to body size: image-card details use 12px/1.4.
- Do not turn the footer into a giant wordmark poster; preserve compact columns and the wider identity block.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions include color and background-color over 0.2s using cubic-bezier(0.645, 0.045, 0.355, 1).
- Support card borders declare a 0.3s border-color transition.
- The pricing opening declares 1.3s translate reveals with cubic-bezier(0.23, 1, 0.32, 1), one starting after 0.2s.
- Scenes contain video, scrolling photographic mosaics, animated numerals and carousel play/pause controls.

**Transfer:**

- Keep motion concentrated in the staged media and output planes; let surrounding copy and rectangular controls remain stable.
- Use static SVG dots and perspective work cards as the faithful minimum version of the black theater; retain play/pause affordances for moving demonstrations.

**Unknown:**

- Exact video loops, camera paths, scroll-scrub timing and particle simulation are unspecified.

### Responsive

**Observed:**

- Desktop reference is 1440px by 900px. Pricing CSS declares thresholds including 600px, 744px, 1020px, 1280px, 1440px and 1920px.
- Display and closing typography include the explicit clamp formulas given in their recipes.

**Transfer:**

- Recommended: on narrow screens stack heading-pair copy and media, preserve the image-led opening and keep the headline over a deliberate clear area.
- Recommended: let capability rails retain horizontal overflow instead of reducing four cards to unreadable miniatures; reduce the particle field to the available width while keeping text above it.

**Unknown:**

- Narrow-screen navigation, exact mobile paddings, stacking thresholds and mobile type sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
