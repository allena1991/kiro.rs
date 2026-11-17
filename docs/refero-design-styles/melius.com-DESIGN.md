# Melius — editorial image theatre

## Overview

An image-led creative technology style that pairs elegant editorial serif headlines with compact, tightly set sans-serif controls. Pale grey stages give way to warm near-black working canvases, with vermilion actions and small butter-yellow signals. Photography, saturated material studies and dark interface demonstrations carry most of the spectacle, while the language stays direct and practical. It suits ambitious creative tools and products with visually demonstrable outcomes, balancing immersive scenes with dense decision-making panels.

### Essentials

- Editorial promises sit above a receding gallery: regular serif display at 56px/1 with -0.02em tracking, centered over a full-width perspective ribbon of images on a 900px-tall pale stage.
- Colour belongs to the work, not the chrome: grey #e3e3e3 and warm black #1a1616 carry the large page fields; vivid photography and material art occupy whole demonstration scenes, while #f04e23 and #fff78b remain concentrated in actions, tags and narrow bands.
- Actions are small rectangular tools, not lifestyle pills: 6px corners, a 48px hero height, 16px tightly tracked regular sans text, and an orange primary paired with a pale secondary.
- The creative process is made visible: dark 8px-corner panels overlap edge-to-edge finished imagery, with fine dotted grids, tiny labels and orange connector lines. When finished media is unavailable, stage a real product result beside a simplified input-to-output diagram rather than leaving a generic dashboard.
- Information lives on tactile editorial cards: white or warm-grey panels, 8–12px corners, compact 12–32px padding and fine rules contrast with large 80–160px section breathing spaces.
- Every page has a monumental sign-off: a muted wordmark about 1037px wide rises behind a 1280px dark footer panel, partially concealed by the newsletter and five link columns. Use the new product's own typographic name at the same visual scale.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion action | `#f04e23` | `--color-orange` | action, accent, border, link | Primary actions, focus outlines, connection lines and a single emphasized plan; broad orange frames belong to company-story modules. |
| Butter yellow | `#fff78b` | `--color-yellow` | action, surface, accent | Secondary compact actions, narrow announcements and small benefit tags. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0e0e0e` | `--color-ink` | text, surface | Primary text on pale stages and deepest demonstration cards. |
| Warm off-black | `#1a1616` | `--color-offblack` | background, surface | Default dark narrative field, pricing background and closing canvas. |
| Navigation charcoal | `#202020` | `--color-nav` | surface, text | Navigation, floating tool panels and feature-card backing. |
| Raised charcoal | `#2a2a2a` | `--color-panel` | surface, border | Footer slab, nav hover and outlines on dark demonstration cards. |
| Dark rule | `#3e3e3e` | `--color-dark-rule` | border, accent | Dark field hairlines and monumental footer lettering. |
| Muted grey | `#676767` | `--color-muted` | text, border | Footer links, supporting labels and de-emphasized information. |
| Light secondary grey | `#b9b9b9` | `--color-secondary` | text, border | Support copy on dark stages; 40% opacity supplies restrained separators. |
| Silver edge | `#c0c0c0` | `--color-silver` | border | Thin outer navigation edges. |
| Inset grey | `#d9d9d9` | `--color-inset` | surface, border | Input outline and inset pricing summaries. |
| Grey stage | `#e3e3e3` | `--color-stage` | background, text | Default immersive opening stage; also pale text on dark cultural sections. |
| Paper white | `#fafafa` | `--color-paper` | surface, text, background | Cards, inputs and primary text on dark fields. |
| Bright white | `#ffffff` | `--color-white` | surface, text | Raised proof panel and secondary-button hover; brightest question text. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive status | `#778958` | `--color-status` | accent | 6px operational status dot in the footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company partner proof | Partner lime | `#e0e07b` | `--color-lime` | background | Full-field backing of the partner-card wall. |
| technical capability sections | Warm label grey | `#9c9996` | `--color-tag-grey` | text | Technical eyebrows and secondary labels. |
| feature detail and company storytelling | Warm grey paper | `#e5e3e3` | `--color-warm-paper` | background, surface | Feature-page background and cultural photo cards. |

## Typography

- **recklessStandard** — Display promises, section leads and editorial card titles. High-contrast editorial serif with fine strokes and a light, literary regular cut. If unavailable, use **Bodoni Moda**. Use 400; preserve tight display tracking and check line breaks. Font stack: "recklessStandard", "Bodoni Moda", Georgia, serif.
- **easeStandard** — Body copy, navigation, buttons, captions and interface-facing marketing text. Compact neutral grotesk, regular weight with distinctly tight negative tracking. If unavailable, use **Inter**. Use 400; keep -0.03em tracking for compact text. Font stack: "easeStandard", "Inter", Arial, sans-serif.
- **futurist** — Plan names and technical markings. Crisp geometric sans with tight display proportions; not a code font. If unavailable, use **Manrope**. Use 400 with the role-specific tracking. Font stack: "futurist", "Manrope", Arial, sans-serif.
- **ui-sans-serif** — Opening support paragraph. Plain system sans, deliberately less stylized than the surrounding serif and controls. Font stack: "ui-sans-serif", system-ui, sans-serif.
- **ui-serif** (only for pricing interludes) — Repeated uppercase text behind sculptural objects. Traditional serif with a poster-like repetitive rhythm. Font stack: "ui-serif", Georgia, Cambria, 'Times New Roman', serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | recklessStandard | 400 | 56px | 1 | -0.02em | fixed | Default opening promise and major section heading. |
| card-editorial | recklessStandard | 400 | 36px | 1 | normal | fixed | Audience cards and image-backed benefit titles. |
| minor-heading | recklessStandard | 400 | 27.2px | 1 | normal | fixed | Proof-panel heading, newsletter lead and small editorial titles. |
| question | easeStandard | 400 | 19px | 1.4 | -0.04em | fixed | FAQ questions, answers and larger plan descriptions. |
| body | easeStandard | 400 | 16px | 1.4 | -0.03em | fixed | Standard support copy and hero actions. |
| opening-support | ui-sans-serif | 400 | 16px | 1.5 | normal | fixed | Centered opening paragraph. |
| navigation | easeStandard | 400 | 13.6px | 1.2 | -0.03em | fixed | Navigation and footer links; uppercase for footer column titles. |
| caption-action | easeStandard | 400 | 12.8px | 1.2 | -0.03em | fixed | Compact buttons, editorial card descriptions and feature lists. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing interludes | poster-repeat | ui-serif | 400 | 56px | 1.25 | -0.025em, uppercase | size clamp(3.5rem, 3vw, 6rem) | Vertical repeated promise behind falling objects. |
| technical product pages | technical-heading | recklessStandard | 400 | 48px | 1 | -0.01em | fixed | Technical page chapter headings. |
| feature detail pages | feature-heading | recklessStandard | 400 | 44px | 56px | -0.02em | fixed | Centered demonstration and feature-grid headings. |
| feature detail openings | feature-display | recklessStandard | 400 | 43px | 1 | -0.02em | fixed | Short feature name in a dark shaped hero panel. |
| company photo essays | photo-title-italic | recklessStandard | 400 italic | 42px | 1 | -0.0091em | fixed | Italic noun paired with a roman introductory word on photo cards. |
| pricing modules | plan-title | futurist | 400 | 32px | 1 | -0.04em | fixed | Plan names. |
| technical capability cards | technical-card-title | easeStandard | 400 | 24px | 1.25 | -0.01em | fixed | Short capability statements below diagrams. |
| technical capability sections | technical-eyebrow | futurist | 400 | 12px | 1 | 0.1em | fixed | Uppercase category labels above technical card headings. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Most text stays at weight 400. Hierarchy comes from serif/sans changes, scale and framing rather than heavy headings.
- Large default serif headings use -0.02em tracking; compact sans generally uses -0.03em, tightening to -0.04em for questions and plan names.
- Keep the opening headline on a clean centered line when possible; subsequent display headings may balance across two or three lines. The changing word uses pixel-like interruption, not a different headline font.

## Layout

**Density:** Airy stages surround compact controls and information cards; media gets room while interface-facing text stays tightly grouped.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Tight chip and icon group gaps. |
| 8px | Small title-to-description gaps and navigation vertical padding. |
| 12px | Hero action gap, technical copy stack and small card padding. |
| 16px | Card-grid gutters and footer link rhythm. |
| 20px | Pricing gutters and card horizontal padding. |
| 24px | Support-to-action separation and regular flex gaps. |
| 32px | Technical card padding and FAQ heading separation. |
| 40px | Major internal column stacks. |
| 43.2px | Broad desktop content side padding. |
| 80px | Default section spacing and proof-panel overlap depth. |
| 120px | Large chapter separation and pricing side gutters. |
| 160px | FAQ top breathing space. |

### Containers and grids

- **wide content**: max width 1352px · side padding 43.2px. Broad proof and media composition with narrow margins.
- **dark chapters**: max width 1312px · side padding 43.2px. Centered technical chapters, image grids and integration splits.
- **reading column**: max width 896px · side padding 43.2px. FAQ and concentrated editorial text, left aligned inside a centered column.
- **hero support**: max width 480px. Centered three-line support paragraph beneath the image ribbon.
- **footer slab**: max width 1280px · side padding 36px. Newsletter block at left, five link groups at right, final ruled status/legal row.
- **pricing grid** (only for pricing modules): max width 1200px · 3 columns · gap 20px. Equal-height light plan cards in a dark field.
- **capability grid** (only for technical capability sections): 2 columns · gap 16px. Image or diagram-led cards in balanced pairs.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 6px |
|  | panels and input | 8px |
|  | editorial cards | 12px |
|  | proof panel | 24px |
| feature demonstrations | showcase frame | 16px |
| company storytelling | story frame | 20px |
| pricing controls | segment track | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing modules | recommended plan glow | `0px 0px 14.1px rgba(240,78,35,0.22), 0px 0px 24px rgba(240,78,35,0.12)` | Soft orange halo on one recommended plan, reinforced by a diffuse 16px-blurred orange layer. |

### Surfaces

#### Pale dotted stage · level 0

**Use:** Default immersive opening and audience-card field.

**CSS:** `background-color: #e3e3e3; background-image: radial-gradient(circle, rgba(0,0,0,0.08) 1px, transparent 1px); background-size: 15px 15px`

**Observed:** Faint rounded dots under cinematic media; texture is subordinate to the images.

**Transfer:** Continue the dot field across the stage rather than using visible graph-paper lines.

#### Dark dotted canvas · level 0

**Use:** Working demonstrations and closing field.

**CSS:** `background-color: #1a1616; background-image: radial-gradient(circle, rgba(255,255,255,0.07) 1px, transparent 1.5px); background-size: 15px 15px`

**Observed:** Warm near-black with a very faint repeated dot field; darker panels sit above it.

**Transfer:** Use for product process and closure, not as a universal dark-mode dashboard.

#### Light card · level 1

**Use:** Audience and pricing content on contrasting stages.

**CSS:** `background: #fafafa; border-radius: 12px; box-shadow: none`

**Observed:** Flat, almost paper-like backing; corners are modest rather than heavily rounded.

**Transfer:** Make content hierarchy and image staging do the work instead of elevation.

#### Footer slab · level 1

**Use:** Shared closing panel over the monumental wordmark.

**CSS:** `background: #2a2a2a; border-radius: 8px; padding: 32px 36px`

**Observed:** Solid and flat; its upper edge hides the lower part of the giant lettering.

**Transfer:** Keep the panel darker than paper but lighter than the closing canvas.

#### Dark diagram card · level 1

**Only for:** technical capability sections

**Use:** Self-contained technical demonstrations.

**CSS:** `background: #0e0e0e; border: 1px solid #2a2a2a; border-radius: 12px`

**Observed:** Internal diagrams have a warmer dot-grid inset with slim connector paths.

**Transfer:** Show one meaningful transformation per card.

#### Warm feature field · level 0

**Only for:** feature detail pages

**Use:** Light framing around dark demonstration panels.

**CSS:** `background: #e5e3e3`

#### Atmospheric technical backing · level 0

**Only for:** technical capability grids

**Use:** Low-contrast coloured atmosphere behind near-black diagram cards.

**CSS:** `background-color: #1a1616; background-image: linear-gradient(#1a1616 0%, rgba(26,22,22,0.3) 28%, rgba(26,22,22,0.3) 70%, #1a1616 100%)`

**Observed:** Blurred photographic blue, teal and rust appear around card edges and fade into the dark field above and below.

**Transfer:** Use a heavily defocused product-related photograph under this overlay; match the soft atmosphere rather than exact colour stops.

## Components

### Main navigation

**Use:** Compact persistent top-level orientation.

**CSS:** `height: 56px; background: #202020; border-left: 1px solid #c0c0c0; border-right: 1px solid #c0c0c0; padding: 0px 24px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — easeStandard 400 · 13.6px/1.2 · tracking -0.03em

**Observed:** Inset 16px from page edges. Small white mark at left, grouped text menus with down chevrons, utility and primary actions at right. Other page types close the bar with a bottom hairline and 6px lower corners.

### Navigation item

**Use:** Dropdown triggers and text destinations.

**CSS:** `color: #fafafa; padding: 8px 12px; border-radius: 6px; display: flex; align-items: center; gap: 8px`

**Text style:** `navigation` — easeStandard 400 · 13.6px/1.2 · tracking -0.03em

**Observed:** Regular text, no bold active tab; chevron follows menu labels.

**States:** Declared: hover background #2a2a2a; focus-visible solid 2px outline #f04e23 with 2px offset.

### Primary button

**Use:** Main opening conversion.

**CSS:** `background: #f04e23; color: #fafafa; border-radius: 6px; height: 48px; padding: 0px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `body` — easeStandard 400 · 16px/1.4 · tracking -0.03em

**Observed:** Pairs with Secondary button. Compact navigation and chapter variant is 40px high with 14px padding and caption-action text; plan CTAs stretch to card width.

**States:** Declared: hover uses the orange background at 0.8 alpha; focus-visible solid 2px outline #f04e23 with 2px offset.

### Secondary button

**Use:** Companion setup or connection action.

**CSS:** `background: #fafafa; color: #0e0e0e; border: 1px solid rgba(185,185,185,0.4); border-radius: 6px; height: 48px; padding: 0px 20px; display: flex; align-items: center; gap: 10px; box-shadow: none`

**Text style:** `body` — easeStandard 400 · 16px/1.4 · tracking -0.03em

**Observed:** Small integration icon precedes text and a down chevron closes it; visually broad enough to balance the shorter primary action.

**States:** Declared: hover background #ffffff and no shadow; focus-visible solid 2px outline #f04e23 with 2px offset.

### Yellow utility button

**Use:** Compact secondary action on dark navigation or a technical opening.

**CSS:** `background: #fff78b; color: #0e0e0e; height: 40px; padding: 14px; border-radius: 6px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `caption-action` — easeStandard 400 · 12.8px/1.2 · tracking -0.03em

**Observed:** Short label with no ornamental icon; paired with a compact orange action.

**States:** Declared: hover uses the yellow background at 0.8 alpha; focus-visible solid 2px outline #f04e23 with 2px offset.

### FAQ row

**Use:** Objection handling in a narrow reading column.

**CSS:** `border-top: 1px solid rgba(185,185,185,0.4); color: #ffffff; padding: 16px 0px; display: flex; justify-content: space-between; align-items: center; gap: 16px`

**Text style:** `question` — easeStandard 400 · 19px/1.4 · tracking -0.04em

**Observed:** Native details/summary construction; plus sign at the far right. Answer copy follows beneath the question and has 32px bottom padding. Last item also closes the list with a bottom rule. Light feature-page variant uses dark text, 880px width and finer dark separators.

**States:** Declared: hover is unspecified; focus-visible solid 2px outline #f04e23 with 2px offset.

### Newsletter input

**Use:** Email signup in the closing panel.

**CSS:** `background: #fafafa; border: 1px solid #d9d9d9; border-radius: 8px; height: 42px; width: 360px; display: flex; align-items: center`

**Text style:** `navigation` — easeStandard 400 · 13.6px/1.2 · tracking -0.03em

**Observed:** Single unsegmented field with muted placeholder and a black right arrow submit action embedded at the end. The action has an accessible Subscribe label.

### Footer link

**Use:** Dense link groups in the closing panel.

**CSS:** `color: #676767; border-radius: 6px; display: flex; align-items: center`

**Text style:** `navigation` — easeStandard 400 · 13.6px/1.2 · tracking -0.03em

**Observed:** Five groups beneath uppercase pale-grey column labels; links are separated by 16px, with 24px from group title to first link.

**States:** Declared: hover color #fafafa and opacity 0.8; focus-visible solid 2px outline #f04e23 with 2px offset.

### Plan card

**Only for:** pricing modules

**Use:** Convert feature breadth into a specific plan choice.

**CSS:** `background: #fafafa; color: #0e0e0e; border: 1px solid transparent; border-radius: 12px; padding: 32px 20px 12px 20px; display: flex; flex-direction: column`

**Text style:** `plan-title` — futurist 400 · 32px/1 · tracking -0.04em

**Observed:** Title and one-line positioning at top, oversized current price with crossed-out former price, tiny billing tags, grey allowance inset, ruled feature list and bottom-aligned full-width CTA. Cards are 387px wide and 775px tall in the desktop composition. One plan has an orange outline and soft breathing glow; the advanced card has a sculpted side indentation revealing a coin and a spectral gradient action.

**Transfer:** Keep commercial content honest and comparable. Use one highlighted plan, not a halo on every card.

### Technical capability card

**Only for:** technical capability sections

**Use:** Explain one operation with a simple diagram before its benefit.

**CSS:** `background: #0e0e0e; border: 1px solid #2a2a2a; border-radius: 12px; padding: 32px; display: flex; flex-direction: column; gap: 32px; overflow: hidden`

**Text style:** `technical-card-title` — easeStandard 400 · 24px/1.25 · tracking -0.01em

**Observed:** Diagram inset above, then a small tracked uppercase category, a sans headline and support copy. The text stack uses 12px gaps. At desktop the card is 648px by 462px.

**Transfer:** Replace complex product internals with a legible miniature input/process/result diagram.

## Imagery and graphics

### Perspective outcome ribbon

**Use:** Signature opening media, across the full stage behind the promise.

**Observed:** A continuous gallery of vivid photography, fashion, objects and abstract renders shrinks toward the middle, with large outward-angled panels cut off at both viewport edges. The small central panels form a horizontal horizon; the larger side panels lean like a curved exhibition wall. There is no browser frame.

**Transfer:** Use original product outputs or art-directed use-context photographs. Without a media library, make a coherent set of six result studies using the product's real objects, documents or before/after transformations; preserve the spatial gallery rather than substituting a single laptop.

**Build:** Create a centered flex strip in a perspective container, repeating enough images to run beyond both edges. Give central panels about 80px height, progressively grow toward 300–550px at the sides, and rotate panels on the Y axis toward the center. Keep images edge-adjacent with small rounded corners; put copy in a clear layer above and below the horizon. A static CSS 3D ribbon is the minimum acceptable version.

### Finished world with working canvas

**Use:** Large capability scenes and interactive category demonstrations.

**Observed:** Full-bleed fashion portraits, cosmetic product use, lush foliage, glossy drink advertising and surreal chrome nature supply the background. A near-black node canvas occupies roughly the right half, with small bordered media nodes and vermilion wires; a compact category/prompt panel floats over the left. Final output and editable process appear together.

**Transfer:** Art-direct one convincing finished outcome per capability, then overlay a simplified working trace. Keep the background cinematic and avoid making every scene the same aspect ratio or hue.

**Build:** Place an object-fit cover result image across the section. Add an 8px-radius near-black panel over approximately half its width; use a faint 15px dot field, thin warm-grey outlines on small media rectangles and SVG cubic curves in orange with circular endpoint sockets. Fit real populated content to the panel rather than adding empty boxes.

### Dot field and pixel word

**Use:** Ambient connective graphic across editorial stages and within the opening headline.

**Observed:** Fine low-contrast dots make the light and dark scenes feel like working canvases. One word in the opening serif sentence changes through a coarse blocky pixel treatment while the rest stays sharply typeset.

**Transfer:** Retain a subtle dot field and restrict pixel interruption to one meaningful variable word; surrounding copy stays fully readable.

**Build:** Use a 15px repeating radial-dot background. For the word, render the same serif text into a small offscreen canvas and scale it up with image-rendering: pixelated, then crossfade to sharp text; retain an accessible full text heading behind the visual layer.

### Monumental closing name

**Use:** Required closing identity sculpture on the dark field.

**Observed:** A huge low-contrast charcoal mark and name spans about 1037px by 186px, partially buried behind the footer slab. It feels architectural rather than like an ordinary footer logo.

**Transfer:** Use the new product's own wordmark, or set its name as custom-width sans lettering; maintain the oversized silhouette and partial occlusion.

**Build:** Place an SVG or large text name centered in #3e3e3e above the footer panel, about four-fifths of the available width. Translate it upward so roughly 83% of its height projects above the slab; layer the panel in front, hiding the lower edge.

### Saturated material benefits

**Only for:** technical product benefit grids

**Use:** Image-backed use-case proof.

**Observed:** Glossy rainbow spheres, radiating gradient petals, a fan of thin coloured slices and translucent green bottles on coral. Images fill 648px by 460px tiles; a dark caption card with a tiny yellow audience tag sits inside the lower corner.

**Transfer:** Use bold material and colour studies tied to the product outcome, keeping large uninterrupted image fields around compact dark captions.

**Build:** For an abstract substitute, arrange repeated circles or elongated rounded petals radially in SVG, fill with vivid opposing linear gradients, add a narrow dark rim and soft inner highlight. Place on a flat contrasting field; keep saturated colours inside the artwork, not the page chrome.

### Culture photo essay

**Only for:** company storytelling

**Use:** Human proof and recruiting.

**Observed:** Candid office, dog and group photos alternate with large portrait cards on warm-grey mounts. A sticky left-aligned serif lead anchors a loosely scattered two-column photo stream. Card titles mix roman introductory words with italic nouns. Portrait rows extend past the viewport.

**Transfer:** Use genuine workplace or customer photographs with mixed portrait/landscape framing; avoid a uniform corporate headshot mosaic.

### Fluid editorial band

**Only for:** company manifesto sections

**Use:** A short philosophical interlude over moving material art.

**Observed:** A pale pinched band with bulbous ends spans a warm orange liquid photograph transitioning from monochrome halftone. Serif phrases sit at opposite ends and a loose black drawn line stretches between them.

**Transfer:** Connect two short conceptual statements through an organic graphic, with original macro material imagery behind it.

**Build:** Draw a closed SVG silhouette with two rounded lobes and inward-curving top and bottom edges, filled warm grey. Place two 36px serif statements in the lobes; draw a thin black cubic-path squiggle between them. Back with a macro photograph and a masked monochrome halftone layer.

### Coin and typographic interlude

**Only for:** pricing interludes

**Use:** Playful relief between dense comparison and objections.

**Observed:** A white 900px field carries a centered vertical repeat of an uppercase promise while rough metallic medallions fall and collect across the bottom. Silver, brass and bronze look irregular and embossed rather than clean flat currency icons.

**Transfer:** Use an original embossed product-related object or token as a physical metaphor, with a repeated short promise; do not turn this into another sales card.

**Build:** Repeat two alternating uppercase lines at 56px/70px down a clipped white stage. Overlay irregular SVG disks with metallic multi-stop gradients, grain and an inset embossed symbol; vary rotation and stack them densely along the bottom. Keep one isolated object above the pile.

### Partner wall

**Only for:** company partner proof

**Use:** Collective credibility before the closing identity.

**Observed:** Four columns of white cards move behind a centered serif headline. Each card has a tiny monochrome portrait, name and compact affiliation; a lime backing shows through narrow gaps. Broad soft white glows veil the middle so the heading remains legible.

**Transfer:** Use verified partner or customer identities and affiliations, not invented endorsements.

**Build:** Build four 340px card columns with 16px gutters on #e0e07b. Overlay a centered 1100px by 300px white veil at 50% opacity with 80px blur plus a warm-grey 844px by 432px blurred shape. Keep the headline above both veils.

### Icons

**Observed:** Marketing controls use small filled SVG arrows and chevrons, typically 16px; submit arrows are 24px. Connection dots and tiny feature marks are about 10px. Detailed 1.5px round-stroke utility symbols are confined to product demonstrations.

**Transfer:** Prefer restrained white or ink arrows, chevrons, plus signs and tiny endpoint circles. Avoid oversized colourful outline icons in marketing cards.

## Section recipes

How recurring sections are built.

### First screen: Perspective gallery opening

**Observed:** The first 900px is a complete pale dotted stage: inset dark Main navigation at the top, a narrow yellow announcement band beneath, a regular 56px serif promise centered in the upper quarter, and the Perspective outcome ribbon crossing the middle. Headline width is about 752px, with a single pixel-changing word. The gallery's outer images enlarge and leave the frame while small central outcomes sit below the headline. A centered 480px support paragraph occupies three lines beneath the horizon, followed 24px later by Primary button and Secondary button with a 12px gap. Those actions end around 730px, leaving open pale space beneath. The next white proof panel begins to overlap near the bottom of this first screen; most of its contents follow below. Back-to-front layers are dot field, gallery imagery, headline, support/actions and navigation.

**Transfer:** Default new landing pages should make their first promise above a spatial gallery of original outcomes. A static perspective ribbon with six carefully made result studies preserves the effect without custom 3D. Technical pages use a narrower curved photographic strip below centered copy and paired compact actions; pricing pages open directly into plans on a dark field; feature-detail pages use a left dark title panel against a large right-hand interface; company pages put a bowed pale text band over a full-bleed photograph.

**Avoid:** Do not replace the immersive horizon with a centered laptop mockup or a conventional two-column text-and-dashboard hero. Do not let side images obscure the central promise or the actions.

**Text style:** `display` — recklessStandard 400 · 56px/1 · tracking -0.02em

### Editorial proof island

**Observed:** A white 24px-corner proof panel overlaps the pale stage by 80px. Its 27.2px centered serif lead sits over a split layout: a dark video case-study card at left and a four-column, three-row customer-mark matrix with thin horizontal rules at right.

**Transfer:** Use a real customer story beside a restrained logo or proof matrix; scale the number of marks to the available credible proof.

**Text style:** `minor-heading` — recklessStandard 400 · 27.2px/1

### Cinematic process chapter

**Observed:** Finished world with working canvas spans the page: vivid result photography behind a dark node workspace and a floating category prompt. Media nodes have tiny labels, orange tags and curved wires. Chapters use little conventional headline copy; the imagery explains the capability.

**Transfer:** Show a result and the steps that produce it. Choose an image palette per chapter instead of adding new brand colours to the navigation.

### Audience card constellation

**Observed:** Light editorial cards float on the Pale dotted stage. A central image-and-serif-title card is surrounded by small 160–200px image tiles with yellow labels; a compact horizontal audience selector sits below.

**Transfer:** Use this for multiple audiences or outcomes, keeping one readable central story and surrounding it with supporting examples.

**Text style:** `card-editorial` — recklessStandard 400 · 36px/1

### Dark decision stage

**Observed:** An 80px-padded dark field starts with a centered display lead, then a segment selector and billing switch above the three-column Plan card grid. Whitespace between the lead and cards is about 120px. One card receives the warm orange glow.

**Transfer:** Put comparable choices into a single dark decision field. Full pricing pages can follow it with a wide comparison table: pale header cells, dark rows, fine horizontal separators and one small Show more action.

**Text style:** `display` — recklessStandard 400 · 56px/1 · tracking -0.02em

### Technical diagram chapters

**Observed:** Centered serif chapter headings and muted support introduce a logo ticker, followed by paired Technical capability cards over Atmospheric technical backing. A later benefit grid places dark caption plaques over large saturated artworks. The last chapter is an asymmetric copy/interface split with setup action and two integration selectors.

**Transfer:** Separate how it works, what it enables and where it fits. Keep diagrams dark and economical while outcome illustrations stay vivid.

**Text style:** `technical-heading` — recklessStandard 400 · 48px/1 · tracking -0.01em

### Feature demonstration spread

**Observed:** Warm feature field frames a centered 44px serif heading and a dark 1193px showcase with a subtly pinched side edge, large video and four thumbnail selectors. A following bento uses one tall left image card, two upper cards and one wide lower card; captions sit low over dark gradients. After a light FAQ, three white related-feature cards show large interface images above short titles.

**Transfer:** For a single feature, prioritize a playable or sequential demonstration, then a small set of visual controls and related capabilities rather than a long abstract benefit list.

**Text style:** `feature-heading` — recklessStandard 400 · 44px/56px · tracking -0.02em

### Company editorial sequence

**Observed:** A bowed light band overlays an edge-to-edge photograph, then a sticky serif lead accompanies staggered candid cards. The Fluid editorial band provides an art interlude. Portrait cards lead into a two-part orange-framed culture carousel with one photo and one pale text panel, a ruled role list and the Partner wall.

**Transfer:** Scope this expressive treatment to company or community storytelling. Reuse the editorial mechanisms with authentic people and places, not the same subjects.

**Text style:** `display` — recklessStandard 400 · 56px/1 · tracking -0.02em

### Ruled objections

**Observed:** A centered 896px reading column on the dark field uses a left-aligned display heading, 32px separation and stacked FAQ rows. Section padding is 160px above and 80px below. Closed rows are short and unboxed; pale feature-page variants retain this ruled construction.

**Transfer:** Answer concrete buying and usage concerns; let answers expand in place rather than turning the section into a card grid.

**Text style:** `display` — recklessStandard 400 · 56px/1 · tracking -0.02em

### Monumental newsletter close

**Observed:** The Dark dotted canvas supports the Monumental closing name and Footer slab. The closing composition is about 648px tall, with 200px reserved above the panel and 72px beneath. A 27.2px serif newsletter lead and Newsletter input occupy the left; five uppercase-led link groups sit to the right. A lower hairline separates status and copyright from legal links. There is no additional giant sales CTA after this panel.

**Transfer:** Preserve the oversized identity behind a useful, compact closing utility layer. Adapt the link groups and signup invitation to the new product, keeping the low-contrast lettering architectural.

**Text style:** `minor-heading` — recklessStandard 400 · 27.2px/1

## Page flow

**Storyline:** Immersive promise → credible results → visible process → audience or capability fit → decision support → objections or integration → monumental utility close.

### Broad product marketing and discovery

1. **Promise** — Perspective gallery stage with concise creative promise and paired actions.
2. **Social proof** — Overlapping white case-study and logo panel.
3. **Product demonstration** — Cinematic result scenes with dark process overlays.
4. **Audience fit** — Card constellation with selectable audience labels.
5. **Decision support** — Light plan cards on dark stage.
6. **Objection handling** — Narrow ruled FAQ.
7. **Closing utility** — Giant muted name behind newsletter and links.

**Transfer:** Demonstrate the breadth of results before asking readers to compare options.

### Explain and activate one feature

1. **Feature promise** — Shaped dark title panel left of an enlarged working interface.
2. **Product demonstration** — Centered video stage with selectable thumbnails.
3. **Capability detail** — Dark image-led bento on warm grey.
4. **Objection handling** — Light ruled FAQ.
5. **Further discovery** — Three related-feature cards.
6. **Closing utility** — Shared monumental name and newsletter slab.

**Transfer:** Keep a single feature focused on demonstration and concrete controls, then offer adjacent capabilities.

### Help users compare and choose

1. **Decision promise** — Centered serif lead on dark field with plan and billing controls.
2. **Pricing** — Equal light plan cards with one highlighted recommendation.
3. **Comparison** — Wide ruled matrix with pale plan header cells.
4. **Emotional relief** — Repeated typographic promise and tactile falling objects.
5. **Objection handling** — Ruled commercial questions.
6. **Closing utility** — Shared giant identity and newsletter panel.

**Transfer:** Alternate dense practical comparison with one playful material interlude before final questions.

### Explain extensibility without losing visual appeal

1. **Promise** — Centered serif copy on pale stage over a bowed photographic strip.
2. **Breadth proof** — Centered support and a thin model/integration ticker.
3. **Capability explanation** — Paired dark diagram cards over blurred colour.
4. **Outcome proof** — Saturated image grid with dark inset captions.
5. **Integration** — Copy beside a conversational product example and setup CTA.
6. **Closing utility** — Shared wordmark and footer panel.

**Transfer:** Connect technical mechanisms to concrete outcomes, then show the point of integration.

### Express culture and attract collaborators

1. **Mission promise** — Full photograph crossed by a bowed pale headline band.
2. **Human proof** — Sticky editorial lead and staggered candid photo cards.
3. **Belief** — Organic pale statement band over changing material art.
4. **Team proof** — Wide portrait-card procession.
5. **Culture** — Orange-framed split photo and statement carousel.
6. **Opportunity** — Compact bordered role rows.
7. **Institutional proof** — Lime partner-card wall veiled behind a centered heading.
8. **Closing utility** — Shared monumental name and newsletter slab.

**Transfer:** Use authentic human material and expressive editorial framing while keeping practical opportunities easy to scan.

## Writing

Confident, visually literate and practical. The voice makes ambitious creative possibilities feel usable through plain verbs, specific artifacts and short, matter-of-fact promises.

**Do not copy:** Do not reuse the brand name, logo, proprietary product and model names, customer or partner identities, funding claims, plan prices, credits, performance numbers or endorsements. Source examples illustrate voice only; replace them with accurate claims and original assets for the new product.

- **Addressing the reader:** Speak directly to you and your work. Use we sparingly for the people building the product; use the product name when explaining a mechanism.
- **Rhythm:** Short headline clauses often come in pairs, with full stops creating a crisp cadence. Support copy expands into one or two practical sentences, while FAQ answers can be longer and explanatory.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A broad creative verb plus an unconstrained outcome, or a concrete capability followed by a compressed simplifying clause. | 5–10 words | “Create any campaign you imagine”<br>“Run any generative AI model. One API.” |
| Capability headline | Parallel brief sentences that connect repeatability with an outcome. | 4–9 words | “Build it once. Run it forever.”<br>“Every model. No extra integrations.” |
| Supporting line | Name a real task, then describe what changes for the reader. | 12–35 words | “Got an ad that's working? Make 50 versions and see which one wins.”<br>“Select specific qualities to tune your video” |
| Action | Direct verb with a useful destination or immediate next step. | 2–5 words | “Get started for free”<br>“Read the docs”<br>“Join the team” |
| Question | Use a buyer's plain question, not a marketing subheading. | 4–12 words | “Can I cancel or change plans anytime?”<br>“Do I have to write the script myself?” |

**Words and phrasing to use:** build; make; create; your; one; every; workflow; finished; together; choose; run

**Avoid:** revolutionary; unparalleled; unlock your potential; synergy; game-changing; excessive exclamation marks

**Rules:**

- Connect a broad promise to visible outputs and concrete operations.
- Use the reader's actual artifact names rather than abstract productivity language.
- Allow a short philosophical sentence in an art interlude, but keep controls literal.
- State pricing, availability and operational conditions plainly in answers.

## Do's and Don'ts

### Do

- Keep default serif leads at 56px/1, weight 400 and -0.02em tracking.
- Pair 48px orange hero actions with pale 6px-corner companion controls.
- Use a 15px low-contrast dot field to connect the immersive and working stages.
- Keep FAQ content within 896px and separate rows with 1px hairlines.
- Give paired technical cards a 16px gutter and 32px internal padding.
- Reserve a 1037px-scale muted identity silhouette behind the 1280px footer slab.
- Use 80px section breathing space as a baseline, expanding to 120–160px for decisions and objections.
- Let saturated artwork occupy large fields while text plaques remain neutral.

### Don't

- Do not set editorial leads in a heavy grotesk; regular serif is the organizing voice.
- Do not round every CTA into a pill; pills belong to compact pricing selectors, not hero actions.
- Do not wash the default page in orange; broad vermilion belongs to framed company-story treatments.
- Do not put a drop shadow on every light card; most surfaces are flat and the plan halo is exceptional.
- Do not replace fine 1px separators with thick borders or boxed FAQ tiles.
- Do not enlarge 12–14px labels to body scale; their smallness makes the product scenes feel like working tools.
- Do not use neon purple or blue as general navigation or body-link colours; vivid hues belong inside artwork.
- Do not render the closing identity as a small logo beside copyright; its oversized partial concealment is a central device.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare 0.2s background, border, colour and opacity transitions using cubic-bezier(0.37, 0, 0.63, 1). Navigation colour transitions use 0.2s cubic-bezier(.4, 0, .2, 1).
- Recommended plans declare a 3.5s repeating glow-breathe animation with cubic-bezier(.37, 0, .63, 1).
- Ambient noise declares 3s steps(5) repeating motion. A thin marquee declares 60s linear infinite motion; a mark cycle declares 4s cubic-bezier(.45, 0, .55, 1).
- The opening word uses a pixelated changing treatment; cinematic scenes and cultural bands change with scrolling.

**Transfer:**

- Concentrate expressive movement in the gallery, variable headline word and material interludes; keep compact actions on the declared short transitions.
- Retain a legible static perspective composition and sharp accessible heading when the animated gallery cannot be implemented.

**Unknown:**

- Exact gallery trajectory, pixel-word timing and scroll-scrub relationships are unspecified.

### Responsive

**Observed:**

- Root text uses clamp(16px, 1vw, 20px), so rem-based values grow on wide screens.
- Styles declare width breakpoints at 480px, 640px, 767px, 768px, 992px, 1024px, 1280px, 1440px, 1536px, 1700px and 1900px.
- Hero actions declare a column arrangement before the small-screen row variant. Desktop navigation is hidden outside its large-screen variant; paired capability cards become a two-column grid at desktop.

**Transfer:**

- On narrow screens, preserve the central gallery horizon and clip peripheral images rather than shrinking the entire desktop scene into a thumbnail.
- Stack hero actions and diagram cards, keeping text and actions outside the moving media layer. Keep the giant closing name partially hidden behind the stacked footer content.

**Unknown:**

- Exact mobile navigation construction, mobile gallery geometry and small-screen heading sizes are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
