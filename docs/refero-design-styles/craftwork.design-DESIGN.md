# Craftwork — curated abundance, human touch

## Overview

A bright, image-rich storefront aesthetic with rounded geometric sans lettering and a practical, human voice. White and pale gray framing lets vivid interface compositions, illustrations and dimensional objects carry the color, with punchy orange reserved for promotional moments. It suits creative tools, libraries and products with tangible outputs: spacious introductions give way to dense but carefully captioned galleries.

### Essentials

- A centered promise sits above a shelf of real outputs: 68px/1.04 semibold geometric sans, -0.035em tracking, two balanced lines, paired dark and pale actions, then 280×210px previews running beyond both viewport edges. Include this output shelf even for a service; use designed sample deliverables when no interface exists.
- The wrapper stays nearly monochrome while the work supplies the spectacle: white canvas, #f4f4f4 panels, #606060 support text and #999999 metadata. Most non-image area is neutral; orange #ff5f1f belongs to contained campaign panels rather than a page-wide theme.
- Buttons are compact rounded rectangles, not generic capsules: the ordinary action is 46px high, 10px radius, 20px side padding with 16px/22px medium text and a right arrow. Capsules are reserved for search, small badges and the campaign action.
- A gallery feels edited rather than uniformly tiled: two 552×414px lead previews above three 363×272px previews, 16px horizontal gaps and 32px row gaps. Names sit outside the images at 18px/22px, with subdued 14px price or count metadata opposite.
- Utility becomes a designed object: a 24px-radius pale panel pairs concise text with a hub-and-spoke graphic, rounded icon blocks and fine connectors. Include an equivalent relationship or workflow scene for the new product, using simple SVG nodes when bespoke illustration is unavailable.
- The ending contains useful visual invitations, not only links: a pale rounded directory and a pair of 240px-high metric cards with 44px/48px numerals, 28px padding and faint violet or blue light in the upper right. Keep the metric-card device somewhere in a new landing page, adapting its purpose and position to the narrative.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet light | `#e0c8ff` | `--color-violet-light` | accent | Pale visible source wash made with violet rgba(151,71,255,0.3), further softened by 0.5 opacity and blur in metric cards. |
| Blue light | `#cbe3ff` | `--color-blue-light` | accent | Pale visible source wash made with blue rgba(80,160,255,0.3), further softened by 0.5 opacity and blur in metric cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Main canvas, white inset surfaces and reversed button labels. |
| Search wash | `#fafafa` | `--color-search` | surface | Default search backing. |
| Preview backing | `#f9f9f9` | `--color-preview` | surface | Very light image backing and utility hover surfaces. |
| Pale plate | `#f4f4f4` | `--color-plate` | surface, background | Large rounded bands, steps, closing cards and directory. |
| Soft action | `#efefef` | `--color-secondary-action` | action, surface | Secondary button fill. |
| Hairline edge | `#e6e6e6` | `--color-edge` | border | Visible black-at-10% edges over white; use rgba(0,0,0,0.1) to retain the edge on gray. |
| Metadata gray | `#999999` | `--color-tertiary-text` | text | Prices, counts, small captions and subdued labels. |
| Secondary gray | `#606060` | `--color-secondary-text` | text, link | Support paragraphs, restrained navigation and secondary links. |
| Charcoal action | `#1e1e1e` | `--color-action` | action, background | Primary action fills. |
| Black ink | `#000000` | `--color-ink` | text | Headlines, item names and active text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Control wash | `#f5f5f5` | `--color-control-wash` | surface | Visible 4% black wash over white in segmented controls. |
| promotional sections and pricing offers | Campaign orange | `#ff5f1f` | `--color-orange` | background, accent, action | Contained promotional panel, recommended-plan frame and promotional action. |
| promotional sections and pricing offers | Warm campaign ink | `#140700` | `--color-campaign-ink` | text, background | Nearly black warm lettering and badges on orange. |
| time-limited campaigns | Announcement orange | `#ff6a2b` | `--color-announcement` | background | Thin announcement ribbon. |

## Typography

- **euclidCircularALightWebS** — All ordinary marketing headings, body copy, navigation and controls. Round geometric sans with a friendly circular construction; compact semibold headings balance light-looking regular paragraphs. OpenType features: "clig" 0, "liga" 0. If unavailable, use **DM Sans**. Use 400, 500 and 600; retain tight heading tracking and check line wrapping. Font stack: "euclidCircularALightWebS", "DM Sans", ui-sans-serif, system-ui, -apple-system, sans-serif.
- **SALE_DISPLAY** (only for promotional sections) — Oversized numerical offer. Heavy compressed display lettering with tightly packed numeral shapes. If unavailable, use **Anton**. Use the available heavy appearance; tune width to keep the number compact. Font stack: "SALE_DISPLAY", "Anton", Impact, sans-serif.
- **Instrument Serif** (only for promotional sections) — Italic line immediately beneath the enormous offer numeral. Narrow, high-contrast editorial italic. Font stack: "Instrument Serif", Georgia, serif.
- **ui-monospace** (only for technical setup instructions) — Copyable commands only. Plain system monospace. Font stack: "ui-monospace", SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | euclidCircularALightWebS | 600 | 68px | 1.04 | -0.035em | fixed | Default centered landing-page headline. |
| metric | euclidCircularALightWebS | 600 | 44px | 48px | -0.04em | fixed | Prominent number in closing invitation cards. |
| feature-title | euclidCircularALightWebS | 600 | 38px | 42px | -0.035em | fixed | Larger feature band and closing setup heading. |
| section-title | euclidCircularALightWebS | 600 | 26px | 32px | -0.03em | fixed | Gallery chapter title beside a view-all link. |
| item-name | euclidCircularALightWebS | 500 | 18px | 22px | -0.02em | fixed | Names beneath preview images and compact feature labels. |
| small-title | euclidCircularALightWebS | 500 | 17px | 24px | -0.012em | fixed | Closing invitation labels and question rows. |
| body | euclidCircularALightWebS | 400 | 16px | 1.5 | -0.02em | fixed | Ordinary explanatory text and proof labels. |
| navigation | euclidCircularALightWebS | 400 | 16px | 22px | -0.02em | fixed | Navigation, search text, footer links and view-all links. |
| action-label | euclidCircularALightWebS | 500 | 16px | 22px | -0.02em | fixed | Primary and secondary button text. |
| metadata | euclidCircularALightWebS | 500 | 14px | 20px | -0.02em | fixed | Price or count aligned opposite an item name. |
| caption | euclidCircularALightWebS | 400 | 14px | 20px | -0.007em | fixed | Review metadata, trust footnotes and quiet attribution. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| promotional sections | campaign-number | SALE_DISPLAY | 800 | 232px | 0.8 | 0.005em | size clamp(112px, 17vw, 232px) | Offer numeral; contrast with restrained ordinary headings. |
| pricing pages | conversion-display | euclidCircularALightWebS | 600 | 62px | 66px | -0.0387em | fixed | Pricing opening and repeated final conversion headline. |
| download landing pages | download-display | euclidCircularALightWebS | 600 | 62px | 66px | -0.04em | fixed | Centered acquisition promise and final download headline. |
| promotional sections | campaign-italic | Instrument Serif | 400 italic | 56px | 1 | -0.01em | size clamp(34px, 4vw, 56px) | Secondary offer line. |
| pricing, download and editorial pages | chapter-heading | euclidCircularALightWebS | 600 | 42px | 48px | -0.05em | fixed | Centered explanatory section title; left aligned for editorial opening and FAQ. |
| pricing pages | price | euclidCircularALightWebS | 600 | 40px | 44px | -0.04em | fixed | Plan price beside smaller period text. |
| editorial company pages | editorial-heading | euclidCircularALightWebS | 600 | 32px | 36px | -0.03em | fixed | Article section headings. |
| download landing pages | download-lead | euclidCircularALightWebS | 400 | 20px | 1.3 | -0.02em | fixed | Centered support and testimonial text. |
| pricing and editorial pages | lead | euclidCircularALightWebS | 400 | 18px | 26px | -0.02em | fixed | Support lines and editorial paragraphs. |
| pricing proof sections | review-body | euclidCircularALightWebS | 400 | 15px | 22px | -0.013em | fixed | Review-card quotation. |
| promotional sections | campaign-label | euclidCircularALightWebS | 600 | 14px | 1.5 | 0.08em, uppercase | fixed | Dark capsule labels above an offer. |
| pricing, download and editorial pages | eyebrow | euclidCircularALightWebS | 500 | 12px | 22px | 0.06em, uppercase | fixed | Small gray chapter marker above a heading. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the round sans consistent across copy and UI. Size produces the hierarchy more than a broad range of weights: regular 400, medium 500, semibold 600.
- Heading tracking tightens from -0.03em in 26px titles to -0.035em in the main headline; compact conversion chapter headings reach -0.05em. Ordinary body and action text use -0.02em.
- The dramatic display/italic pairing belongs to offers, not to the ordinary hero. In product previews, typefaces are part of the work being shown, not extra marketing fonts.

## Layout

**Density:** Airy introductions and chapter separations surround closely packed preview grids, caption rows and utility controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small label or icon grouping. |
| 10px | Preview-to-caption separation. |
| 12px | Action pairs, compact card grids and footer-to-final-card gap. |
| 16px | Gallery column gap and heading-row bottom padding. |
| 20px | Button side padding and proof-card padding. |
| 24px | Setup card padding and heading/support group separation. |
| 28px | Closing metric-card padding. |
| 32px | Gallery row gap and support-to-action separation in a feature band. |
| 40px | Desktop container side padding and offer-panel padding. |
| 48px | Feature panel inner padding. |
| 64px | Feature panel column gap. |
| 96px | Default chapter top space. |
| 120px | Explanatory chapter separation on conversion pages. |
| 144px | Late setup section and directory separation. |

### Containers and grids

- **Landing container**: max width 1200px · side padding 40px. Centered shell yielding 1120px of content at desktop.
- **Edited gallery**: 6 columns · gap 16px. Lead items span three columns each; smaller items span two. Row gap is 32px.
- **Feature panel**: 2 columns · gap 64px · side padding 48px. Equal text and diagram columns, vertically centered.
- **Heading measure**: max width 640px. Limit supporting chapter headings; support paragraphs sit around 520px wide.
- **Closing cards**: max width 1110px · 2 columns · gap 12px. Two broad shallow metric invitations.
- **Directory columns**: 6 columns · gap 30px. Compact lists inside a centered 1110px pale panel.
- **Conversion container** (only for pricing pages): max width 920px. Narrower centered column for plans, proof, comparisons and FAQ.
- **Editorial column** (only for editorial company pages): max width 730px. Left-aligned article beside a 240px sidebar; body paragraphs use a narrower 635px measure.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Buttons and previews | 10px |
|  | Setup cards | 16px |
|  | Large pale panels | 24px |
|  | Search and badges | 9999px (pill) |
| promotional sections | Campaign panel | 28px |
| pricing proof sections | Proof cards | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Inset panel edge | `inset 0px 0px 0px 1px rgba(0,0,0,0.06)` | Closing cards and pricing proof panels. |
| pricing offers | Offer glow | `0px 18px 40px -22px rgba(255,95,31,0.6)` | Under the orange recommended-plan frame. |

### Surfaces

#### Canvas · level 0

**Use:** Default page surface.

**CSS:** `background: #ffffff; color: #000000`

#### Pale panel · level 1

**Use:** Contain a feature or useful utility rather than tinting a whole page.

**CSS:** `background: #f4f4f4; border-radius: 24px; padding: 48px; overflow: hidden`

**Observed:** Broad, flat and softly rounded; imagery and copy sit together without a floating card shadow.

**Transfer:** Use this for a diagram or a short workflow explanation.

#### Preview frame · level 1

**Use:** Frame product-output imagery.

**CSS:** `background: #f9f9f9; border: 1px solid rgba(0,0,0,0.1); border-radius: 10px; overflow: hidden`

**Observed:** A faint edge remains legible around light images; captions are outside this frame.

**Transfer:** Place actual outputs or composed examples inside, not explanatory paragraphs.

#### Metric light · level 1

**Use:** Subtle colored light in pale metric invitations.

**CSS:** `background: #f4f4f4; border-radius: 24px; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.06); overflow: hidden; isolation: isolate`

**Observed:** Violet or blue illumination stays near the upper right and does not compete with black numbers.

**Transfer:** Keep the light very faint and locally clipped.

#### Orange offer · level 1

**Only for:** promotional sections

**Use:** High-impact contained campaign interruption.

**CSS:** `background: #ff5f1f; color: #140700; border-radius: 28px; padding: 40px; overflow: hidden`

**Observed:** Warm black number and italic line on the left; dot-based dimensional art fills the right.

**Transfer:** Use an authentic offer or announcement as a self-contained visual event.

#### Review plate · level 1

**Only for:** pricing proof sections

**Use:** A dense wall of short reviews.

**CSS:** `background: #f4f4f4; border-radius: 20px; padding: 20px; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.06)`

**Observed:** Flat pale boxes have variable heights; metadata precedes the quote and avatar attribution follows it.

**Transfer:** Use three staggered columns of verified short proof rather than one oversized pull quote.

## Components

### Navigation bar

**Use:** Compact shared navigation above the spacious introduction.

**CSS:** `height: 60px; display: flex; align-items: center; gap: 16px; padding: 0px 12px 0px 20px; background: #ffffff`

**Text style:** `navigation` — euclidCircularALightWebS 400 · 16px/22px · tracking -0.02em

**Observed:** Logo at the left, three subdued category menus, central Search control, then pricing, theme, sign-in and a small dark utility action. The ordinary landing header is unboxed; conversion and editorial variants are sticky with a fine bottom rule.

**Transfer:** Keep navigation utilitarian so the gallery remains the visual focus.

### Search control

**Use:** Central catalog utility.

**CSS:** `width: 350px; height: 38px; display: flex; align-items: center; gap: 8px; padding: 0px 8px 0px 12px; background: #fafafa; border-radius: 9999px`

**Text style:** `navigation` — euclidCircularALightWebS 400 · 16px/22px · tracking -0.02em

**Observed:** A thin magnifier comes before muted text; a small keyboard-hint capsule sits at the far right. Other page types use the preview backing gray.

**States:** Declared: hover background-color #edededb2; focus-visible not specified.

### Primary button

**Use:** Main conversion action.

**CSS:** `height: 46px; padding: 0px 20px; border-radius: 10px; background: #1e1e1e; color: #ffffff; display: flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `action-label` — euclidCircularALightWebS 500 · 16px/22px · tracking -0.02em

**Observed:** A right arrow follows the label. The header utility uses a smaller 30px-high, 8px-radius variant. A download closing action grows to 56px high; the ordinary default remains compact.

**States:** Declared: hover background-color #383838; focus-visible solid 2px #000 outline with 2px offset; active background-color #000.

### Secondary button

**Use:** Adjacent browsing or explanation action.

**CSS:** `height: 46px; padding: 0px 20px; border-radius: 10px; background: #efefef; color: #000000; display: flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `action-label` — euclidCircularALightWebS 500 · 16px/22px · tracking -0.02em

**Observed:** Sits beside the dark action without competing in contrast. Labels are short and sentence case.

**States:** Declared: hover background-color #e0e0e0; focus-visible solid 2px #000 outline with 2px offset; active background-color #b3b3b3.

### Output tile

**Use:** Show the product through a concrete artifact.

**CSS:** `background: #f9f9f9; border-radius: 10px; overflow: hidden; aspect-ratio: 4 / 3`

**Text style:** `item-name` — euclidCircularALightWebS 500 · 18px/22px · tracking -0.02em

**Observed:** The image fills its frame with an overlaid fine edge. Below it, outside the rounded frame, a name appears on the left and price or count on the right after 10px. Wide lead previews and smaller supporting previews share the same ratio.

**Transfer:** Use a composed example of what the customer gets; the caption is not a feature-card paragraph.

### Gallery heading row

**Use:** Introduce a collection without a bulky section header.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; padding-bottom: 16px; border-bottom: 1px solid rgba(0,0,0,0.1)`

**Text style:** `section-title` — euclidCircularALightWebS 600 · 26px/32px · tracking -0.03em

**Observed:** Title stays left; a gray 16px view-all link with a small chevron stays right. Preview grid starts 12px below the rule.

### Setup step

**Use:** Make activation feel short and achievable.

**CSS:** `background: #f4f4f4; border-radius: 16px; padding: 24px`

**Text style:** `item-name` — euclidCircularALightWebS 500 · 18px/22px · tracking -0.02em

**Observed:** Three equal cards, each with a small circular step number, a short task title, muted explanation and a miniature relevant control or result. A command uses a white inset code bar and copy icon.

**Transfer:** Use three real steps or a similarly concise task grouping; show one tangible action per card.

### Metric invitation

**Use:** A useful final path paired with quantified proof.

**CSS:** `background: #f4f4f4; border-radius: 24px; padding: 28px; height: 240px; display: flex; flex-direction: column; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.06); overflow: hidden; position: relative; isolation: isolate`

**Text style:** `metric` — euclidCircularALightWebS 600 · 44px/48px · tracking -0.04em

**Observed:** Number and subdued qualifier sit upper left, with overlapping avatars or a white link/copy chip upper right. The lower group has a small outline icon, a 17px title, quiet explanatory text and an arrow anchored to the right.

**Transfer:** Use real measured value or a meaningful quantity; adapt lower labels to two secondary user journeys.

### Directory footer

**Use:** A substantial pale destination map.

**CSS:** `max-width: 1110px; background: #f4f4f4; border-radius: 24px; padding: 50px 45px`

**Text style:** `navigation` — euclidCircularALightWebS 400 · 16px/22px · tracking -0.02em

**Observed:** Six compact link columns above a spacious utility zone. Rating and badges sit left; theme controls, attribution and policy links sit right. A fine divider introduces a low-contrast tail of topic links.

**Transfer:** Scale the directory to the product's real destinations; keep legal and discovery material visually subordinate.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side free and paid decision.

**CSS:** `background: #f4f4f4; border-radius: 18px; padding: 32px; display: flex; flex-direction: column`

**Text style:** `price` — euclidCircularALightWebS 600 · 40px/44px · tracking -0.04em

**Observed:** Paid default sits inside a 2px orange, 20px-radius frame with a campaign strip and soft orange shadow. Order is plan name, price with old-price and period, billing note, divider, benefit checks and a full-width orange action at the bottom. Free alternative is white with a 1px translucent black edge, 20px radius and pale action.

**Transfer:** Separate monthly equivalent from actual billing. Use tiny circular check marks and keep the action baselines aligned.

### Billing switch

**Only for:** pricing pages

**Use:** Choose a billing interval above plans.

**CSS:** `height: 42px; padding: 2px; display: flex; gap: 2px; background: rgba(0,0,0,0.04); border-radius: 12px`

**Text style:** `action-label` — euclidCircularALightWebS 500 · 16px/22px · tracking -0.02em

**Observed:** Three equal segments in a 460px-wide control. Selected segment is white with a subtle inset/drop edge; a tiny outlined saving badge sits beside its label.

**States:** Declared: hover inactive text color #000; focus-visible solid 2px #000 outline with 2px offset.

### Question row

**Only for:** pricing pages

**Use:** Objection handling near the end.

**CSS:** `padding: 20px 0px; display: flex; align-items: center; gap: 16px; border-bottom: 1px solid rgba(0,0,0,0.1)`

**Text style:** `small-title` — euclidCircularALightWebS 500 · 17px/24px · tracking -0.012em

**Observed:** Question text occupies the row; a pale circular plus sits at the right. Open state replaces plus with a dark minus and reveals smaller gray copy beneath. Questions form a 572px column beside a compact heading/contact block.

**States:** Declared: hover not specified; focus-visible solid 2px #000 outline with 2px offset.

## Imagery and graphics

### Curated output shelf

**Use:** Signature opening rail and recurring product galleries.

**Observed:** Richly art-directed interface compositions, device mockups, typographic specimens and illustration collections alternate light and dark backings. Wide rectangular images are cropped cleanly with soft corners; the UI around them stays monochrome. The opening rail overflows the page with softened side edges and a small round pause control.

**Transfer:** Create distinct sample outputs for the new product. At minimum use three carefully composed real examples, each with a deliberate backing and clear focal point; avoid repeating the same dashboard in every tile.

### Connection diagram

**Use:** Signature utility feature scene inside Pale panel.

**Observed:** A white 96px rounded central app block floats between two columns of four smaller 60px icon blocks. Thin gray curves converge through the center; small labels sit under each icon. Soft pastel source blocks contrast with recognizable app icons and one darker animated-looking connector.

**Transfer:** Represent inputs, product and destinations using simple original icons and short labels, preserving the spatial clarity and soft depth.

**Build:** In an SVG around 460×396px, place four nodes down each side and a 96px center block with 22px corners. Draw cubic Bézier paths behind them in black at 10% opacity, 1px stroke. Put 60px rounded source tiles at left, destination icons at right and labels underneath in 13px sans. Add a low dark shadow only to the center tile; use a short black path segment to suggest flow.

### Metric-card light

**Use:** Signature local glow on final invitation cards.

**Observed:** Extremely soft violet and blue washes gather near the upper-right corners of otherwise flat gray cards.

**Transfer:** Use the same faint local light for two complementary paths, not a full-page gradient.

**Build:** Behind card content, add a 224×224px circle positioned 48px beyond the right edge and 64px above the top. Fill with rgba(151,71,255,0.3), filter blur(64px), opacity 0.5. Use rgba(80,160,255,0.3) for the neighboring card. Clip within the rounded parent.

### Halftone orbital object

**Only for:** promotional sections

**Use:** Right half of the orange offer panel.

**Observed:** Warm-black square dots form broken orbital rings around a faceted dimensional object. The ring field is much larger than the central object and clips at panel edges; all art remains monochrome against orange.

**Transfer:** Keep the low-resolution sculptural treatment with a new abstract object rather than a generic decorative gradient.

**Build:** Use a canvas or SVG dot lattice across a 720px field. Project several concentric tilted ellipses into irregular bands; retain 2–4px square cells where bands intersect the lattice. In the center, shade a roughly 282px faceted sphere or torus using dot density rather than smooth gradients. Fill marks with campaign ink, leave gaps orange and clip the field inside the panel. A static halftone sphere plus three broken elliptical bands is the minimum version.

### Floating collection previews

**Only for:** download landing pages

**Use:** Mid-page demonstrations and scroll-led resource showcase.

**Observed:** A small dark file-box illustration carries bright folders; a yellow folder silhouette sits behind an inline headline count. Large browser-like resource boards are stacked, while individual showcase cards float off-center with a broad soft shadow and small corners. The cards contain their own brand palettes; they are not site-wide colors.

**Transfer:** Use a folder or package metaphor for the deliverable and real browsable contents for proof. A few carefully spaced boards are enough to communicate abundance.

**Build:** For the inline count, draw a rounded folder rectangle with a short raised tab behind black numerals, using a bright yellow graphic fill. For demonstrations, layer three original 705×408px browser boards with small offsets and a fine edge; show one 614×322px resource card at a time with a soft multi-layer downward shadow.

### Playful team collage

**Only for:** editorial company pages

**Use:** Single broad photograph beneath the introduction.

**Observed:** A candid, sunlit office group portrait fills a 730×490px rounded rectangle. Circular white-edged stickers mix a smiling yellow face, a personal portrait and a vivid pink digital texture; a bright lime badge adds a final playful mark.

**Transfer:** Use an authentic relaxed photograph with a few original personal stickers. Keep the natural room light and imperfect social energy rather than a formal corporate headshot wall.

**Build:** Place the photo in a gently rounded clipping frame. Overlay two or three circular cutouts near corners with white borders, plus one small solid badge. Keep stickers smaller than faces and avoid covering essential people.

### Icons

**Observed:** Mostly 16px and 20px outline SVGs, 1.5px strokes and round caps in neutral gray or black. Actions use arrows or chevrons; 12px checks use heavier 2.5px strokes inside pale circles. Logos and rating stars are solid exceptions.

**Transfer:** Choose simple round-capped outline icons, preserve light stroke weight and use filled marks only for app identities or ratings.

## Section recipes

How recurring sections are built.

### First screen: Promise above the output shelf

**Observed:** A white first screen has a 60px utility navigation band, with a 32px orange announcement strip during campaigns. A centered two-line 68px display occupies roughly two thirds of the viewport width below generous top air. A short gray support line sits underneath, followed by Primary button and Secondary button. About 80px below the introduction group, 280×210px Output tiles form a full-width shelf extending beyond both sides, with captions beneath, faded side edges and a circular pause control at lower right. Layers are white canvas, text/actions, then individually art-directed preview images. Within the first 900px the full promise, support, both actions, shelf images and captions are visible; company-logo proof and the next large panel fall below.

**Transfer:** Lead with the product's concrete output and human benefit, then show varied examples. If no interface exists, design sample deliverable covers, before/after artifacts or finished-work compositions. Pricing opens instead with a 62px conversion headline, interval switch and plan tops; acquisition pages use a count/folder motif and one download action; editorial pages open left-aligned beside a navigation rail.

**Avoid:** Do not replace the shelf with a single giant dashboard, a split hero, or a full-bleed gradient. Do not add a colored badge above every ordinary landing headline.

**Text style:** `display` — euclidCircularALightWebS 600 · 68px/1.04 · tracking -0.035em

### Edited gallery chapter

**Observed:** Gallery heading row after 96px top spacing, then a 12px gap to the Edited gallery. Two lead previews sit above three supporting previews, all with captions and subdued metadata outside their frames.

**Transfer:** Group capabilities by visible outcomes; vary image scale to create editorial priority rather than giving every output identical importance.

**Text style:** `section-title` — euclidCircularALightWebS 600 · 26px/32px · tracking -0.03em

### Utility feature band

**Observed:** Pale panel combines a compact introductory label, Feature title, a restrained paragraph, paired actions and Connection diagram in equal columns. The panel is padded 48px with a 64px column gap.

**Transfer:** Use the scene to explain how the product fits into an existing workflow, not to add another generic feature list.

**Text style:** `feature-title` — euclidCircularALightWebS 600 · 38px/42px · tracking -0.035em

### Activation close

**Observed:** A heading/support pair sits left and Primary button right above a thin rule; 24px bottom padding separates it from three Setup steps in a row with 16px gaps. The chapter gets 144px of top space.

**Transfer:** Close the main story by showing the short route from interest to first result.

**Text style:** `feature-title` — euclidCircularALightWebS 600 · 38px/42px · tracking -0.035em

### Directory and useful afterword

**Observed:** Directory footer is a large rounded pale island, followed just 12px later by two Metric invitations. Each card combines a big number, top-right utility, lower icon/title/support and arrow; the page ends with a small outer margin.

**Transfer:** Keep a practical metric-backed afterword for secondary audiences. It can sit before or after the directory, but should remain visually distinct from legal links.

**Text style:** `metric` — euclidCircularALightWebS 600 · 44px/48px · tracking -0.04em

### Campaign interruption

**Only for:** promotional sections

**Observed:** Orange offer panel is 1120px wide and 558px high. Two dark capsules precede the oversized offer number and italic line on the left. Small support copy and a dark pill action sit below; Halftone orbital object fills the right and clips into the rounded edge.

**Transfer:** Use a limited announcement or real offer, with short copy and one action. Preserve the numerical mass and serif contrast without making them the ordinary headline style.

**Text style:** `campaign-number` — SALE_DISPLAY 800 · 232px/0.8 · tracking 0.005em

### Centered conversion chapters

**Only for:** pricing and download pages

**Observed:** A 12px uppercase eyebrow introduces a 42px centered title and gray support with a 12px gap. Content below takes a denser form: four-by-two output tiles, two-by-two workflow demonstrations, a four-item comparison tray, or a staggered three-column Review plate wall. Chapters separate by 120px.

**Transfer:** Choose the proof structure that answers the next decision; retain the compact heading measure and image-led argument.

**Text style:** `chapter-heading` — euclidCircularALightWebS 600 · 42px/48px · tracking -0.05em

### Plan decision and objections

**Only for:** pricing pages

**Observed:** A 62px centered promise and 18px support lead to Billing switch, then two Plan cards separated by 12px. A team-plan strip and refund note sit beneath. The complete decision block returns near the end, followed by a two-column FAQ with a 300px intro, 48px gap and Question rows. The ending is a slim 61px full-width footer with attribution left and navigation/theme controls right, not the large directory.

**Transfer:** Let product breadth and use-case proof justify the price before repeating the decision. Keep billing facts readable and objections close to the final action.

**Text style:** `conversion-display` — euclidCircularALightWebS 600 · 62px/66px · tracking -0.0387em

### Download acquisition and reassurance

**Only for:** download landing pages

**Observed:** A small provenance-style badge, a centered 62px headline with a yellow folder-backed quantity, 20px support and dark download action establish the offer. A two-by-two contents list leads into Floating collection previews. Three 255px feature cards use thin borders and 15px corners; a later benefit group uses 2px dashed capsule outlines. Near the end a 62px closing headline repeats the action, followed by two unboxed star-rated testimonials and Directory footer.

**Transfer:** Demonstrate the actual contents, explain practical time saved, then repeat the same action with a short no-friction reassurance.

**Text style:** `download-display` — euclidCircularALightWebS 600 · 62px/66px · tracking -0.04em

### Editorial story and personal signoff

**Only for:** editorial company pages

**Observed:** A 240px left navigation rail persists beneath the top bar; the main 730px column opens with breadcrumb, 42px title, 18px introductory copy and Playful team collage. Subsequent 32px headings and gray prose alternate with directory-like category links and fine dividers. The ending stays in the article: principles, a divider, a conversational wrap-up, an underlined contact link and a short farewell. Sidebar attribution and social links remain separate.

**Transfer:** Use this for human context and an approachable editorial read. End with a personal invitation rather than inserting a sales grid.

**Text style:** `editorial-heading` — euclidCircularALightWebS 600 · 32px/36px · tracking -0.03em

## Page flow

**Storyline:** Concrete promise → visible outputs → breadth and workflow fit → proof of value → easy first action → useful secondary paths.

### Image-led product or library landing page

1. **Promise** — Centered two-line claim, short support, paired actions and overflowing output shelf.
2. **Social proof** — Muted trust sentence and a row of recognizable company names.
3. **Campaign** — Contained orange offer with monumental number and dot sculpture.
4. **Capability chapters** — Edited galleries interrupted by a pale workflow diagram band.
5. **Activation** — Short setup section with three task cards.
6. **Closing paths** — Directory island and metric-backed secondary invitations.

**Transfer:** Let actual output do most of the persuasion; adapt chapter order and number to the product's breadth.

### Plan selection and purchase confidence

1. **Pricing** — Centered promise, billing switch, paired plans and team strip.
2. **Quantified proof** — Four-cell outlined stats band with large numerals and smaller qualifiers, then muted company logos.
3. **Product breadth** — Compact four-by-two category preview gallery.
4. **Workflow fit** — Two-by-two illustrated task demonstrations and small license/usage reassurance cards.
5. **Value comparison** — Four output examples in a pale tray with a white savings/action strip.
6. **Social proof** — Three staggered columns of short review plates.
7. **Closing call** — Repeat the plan decision block.
8. **Objection handling** — Split FAQ and slim attribution footer.

**Transfer:** Answer what is included, how it is used and why it is worth paying before the repeated decision.

### Acquire users through a concrete free deliverable

1. **Promise** — Count-led centered headline, folder motif and single download action.
2. **Contents** — Two-by-two categorized bullet list and stacked browser boards.
3. **Benefits** — Three bordered feature cards, then dashed benefit capsules.
4. **Demonstration** — Floating preview cards emphasize the contents.
5. **Closing call** — Repeat the promise/action with no-friction reassurance.
6. **Social proof** — Two unboxed star-rated testimonials before the directory.

**Transfer:** Keep the deliverable tangible and the action unchanged; demonstrate contents rather than inventing unrelated capabilities.

### An approachable company or editorial story

1. **Context** — Breadcrumb and simple title beside an institutional sidebar.
2. **Human proof** — Short introduction and candid sticker-decorated team photograph.
3. **Purpose** — Editorial headings, paragraphs and a compact two-column link directory.
4. **Credibility** — A substantial typographic claim separated with fine rules.
5. **Closing invitation** — Principles, personal wrap-up, contact link and friendly farewell.

**Transfer:** Use an article-like rhythm and real people, keeping commercial actions secondary.

## Writing

Practical and welcoming, with confidence grounded in visible work and concrete benefits. Headlines feel conversational rather than corporate; the human craft behind the product matters as much as its efficiency.

**Do not copy:** Do not reuse Craftwork names, logos, product artwork, creator names, customer affiliations, quoted testimonials, prices, discount deadlines, audience totals or revenue claims. Substitute the new product's own verifiable facts and assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you in task and benefit copy; use we for the people making or curating the product. Product references are plain, not ceremonious.
- **Rhythm:** Short noun-led catalog labels contrast with plain-language promise headlines and one or two support sentences. Conversion copy uses compact reassuring fragments; editorial prose is warmer and looser.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the useful output and qualify who makes it or why it is trustworthy. | 8–12 words | “UI kits, templates and fonts made by real designers” |
| Conversion headline | Two short clauses move from low-risk exploration to the fuller offer. | 7–10 words | “Browse for free. Go Pro to use it all.” |
| Section heading | Say what changes for the user in ordinary speech. | 5–9 words | “Your AI agent can use it too”<br>“Designers keep coming back” |
| Supporting line | Explain a concrete workflow and the practical result, without abstract superlatives. | One or two sentences | “Free with any [Brand] account. Takes about a minute” |
| Primary action | Verb plus the thing received or the next task. | 3–5 words | “Get the Free Collection”<br>“Connect your agent” |
| Reassurance | Brief friction-removing statements beside the action. | 2–3 short fragments | “Pick a plan and start downloading in a minute. Cancel anytime.” |

**Words and phrasing to use:** made by real people; hand-picked; ready for; client work; one plan; start building; connect; browse; save hours

**Avoid:** revolutionary ecosystem; unleash limitless potential; synergize; disruptive excellence; next-generation paradigm

**Rules:**

- Prefer explicit formats, outputs and tasks over broad platform language.
- Keep catalog labels short; reserve complete sentences for persuasion and explanation.
- Pair meaningful numbers with a plain qualifier; explain billing or usage limits in adjacent copy.
- Use low-friction reassurance close to the action, not buried in a separate paragraph.
- Allow a personal, lightly playful signoff in editorial writing while keeping purchase copy literal.

## Do's and Don'ts

### Do

- Use 68px semibold centered type for the default promise and keep it to a balanced two-line block.
- Place the image shelf below paired 46px rounded-rectangle actions.
- Keep preview frames at 4:3 with captions 10px below.
- Mix two wide and three smaller previews to establish editorial priority.
- Use #606060 for support and #999999 for metadata instead of lowering all text opacity.
- Separate ordinary chapters with 96px top space; reserve 144px for the late activation/footer transition.
- Use 24px rounded pale panels as contained islands on white.
- Retain the useful metric-card device with 44px numerals and faint local light.

### Don't

- Do not turn every button into a pill; the default radius is 10px.
- Do not apply the campaign serif or compressed numeral face to ordinary marketing headlines.
- Do not spread orange across every section or use it as the standard navigation fill.
- Do not put long feature descriptions inside the preview-image frame; keep captions outside.
- Do not give every gallery image a dramatic drop shadow; ordinary frames use fine translucent edges.
- Do not expand footer metadata to headline contrast or size; it remains subordinate gray text.
- Do not imitate colorful preview typography as additional site fonts.
- Do not use the 240px editorial sidebar as the default landing-page composition.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary actions declare all 0.3s cubic-bezier(0,0,0.2,1); hover changes the fill without scaling.
- Navigation/search color transitions declare 0.15s cubic-bezier(0.4,0,0.2,1).
- The opening output shelf has a visible pause control; adjacent gallery images can change.
- Feature reveal declarations use opacity and filter 0.5s, transform 0.6s with cubic-bezier(0.2,0.9,0.25,1).
- Closing metric light declares opacity 0.7s cubic-bezier(0.4,0,0.2,1), increasing toward 0.9 on desktop group hover.

**Transfer:**

- Keep action feedback mostly tonal; preserve the pause affordance if the output shelf advances automatically.
- Use subtle reveal behavior on large panels rather than bouncing individual captions.

**Unknown:**

- Carousel speed, orbital-object timing and scroll-linked card sequencing are not established.

### Responsive

**Observed:**

- Declared layout classes reduce container side padding from 40px to 16px.
- Gallery markup switches between narrow-screen horizontal snap rows and the desktop six-column grid; item widths include 78% and 46% narrow variants.
- Feature panel declares a one-column default and equal columns at a wider breakpoint; padding grows through 24px, 32px and 48px.
- Conversion headlines declare a 32px/36px compact variant; desktop is 62px/66px. Directory classes move from two to three to six columns.

**Transfer:**

- Preserve a partially visible next tile on small screens so the shelf still communicates abundance.
- Stack feature copy above its diagram, and stack plan/metric cards when their labels no longer fit.
- Keep the offer numeral's clamp formula and reduce art intrusion before compressing offer text.

**Unknown:**

- Exact rendered mobile composition, sidebar collapse behavior and all intermediate viewport states are unverified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
