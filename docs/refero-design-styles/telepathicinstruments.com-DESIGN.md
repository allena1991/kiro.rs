# Telepathic Instruments — tactile machines, digital magic

## Overview

A retro-futurist product style with the intimacy of a working studio and the spectacle of an equipment launch. Monumental product renders and lo-fi video sit beside unusually modest grotesk headings, technical monospace labels and occasional delicate serif statements. Black, warm ivory and white carry the long-form story, with hot orange stages and electric green actions punctuating an otherwise restrained palette.

### Essentials

- The object is the headline: a full-width 864px product stage beneath a 36px announcement strip puts a large three-quarter object on the left and a 472px translucent purchase panel on the right; the actual title stays at 20px/24px, weight 500.
- Technical labels temper the spectacle: Suisse Intl Mono at 12px/12px in uppercase for actions and 14px/20px for navigation and ticker text, paired with 16px grotesk paragraphs.
- Conversion looks like an illuminated control: the primary action is electric green #37fa16, 52px high with 64px corners; its outlined companion sits 8px below it.
- Color belongs to scenes rather than every container: orange dominates the opening product photography and the thin #ff6c2f ticker, while long reading sections alternate #151515, #191919, #efede6 and white. Green is concentrated in actions and active states, not broad page washes.
- Physical proof stays oversized and text stays small: product cutouts and videos take roughly three fifths of feature compositions; supporting columns are 320–400px wide, with 96px section padding and 40px outer gutters.
- Retain the digital-grain counterpoint to polished renders: include a pixel-stepped graphic or word sculpture and a real-use media moment. A thresholded two-tone silhouette and one carefully framed demonstration are the minimum equivalent when richer media is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff6c2f` | `--color-orange` | background, accent | Announcement strip; related warm orange hues belong in the product-stage imagery rather than flat reading panels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric green | `#37fa16` | `--color-purchase` | action | Primary purchase fill. |
| Active green | `#22d504` | `--color-active` | action, link, accent | Action hover fill, active navigation and product-title hover. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, border | Commerce canvas, reversed text and outlined actions. |
| Warm ivory | `#efede6` | `--color-ivory` | background, text | Human-use media bands and warm reversed lettering. |
| Demonstration gray | `#ecedec` | `--color-demo-gray` | background | Cool light ground for explanatory video chapters. |
| Technical gray | `#a3a3a3` | `--color-muted` | text, border | Footer labels and input outlines. |
| Glass edge | `#595959` | `--color-glass-edge` | border | Fine outline on the persistent purchase capsule. |
| Clay gray | `#4a4a4a` | `--color-model-gray` | surface | Monochrome product-update card base. |
| Charcoal | `#191919` | `--color-charcoal` | background, text | Supporting dark chapters and newsletter band. |
| Near-black stage | `#151515` | `--color-stage` | background | Continuous product anatomy stage. |
| Absolute black | `#000000` | `--color-black` | text, background, border | Primary ink on light bands, black media stages and the footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| community-focused brand storytelling | Garden green | `#305831` | `--color-community` | background | Full-width testimonial environment. |

## Typography

- **Suisse Intl** — Headings, descriptions and product names. Matter-of-fact neo-grotesk with compact medium headings and plain regular body text. If unavailable, use **Inter**. 400, 500 and 700; retain the small heading scale and tight tracking. Font stack: "Suisse Intl", "Inter", "Helvetica Neue", sans-serif.
- **Suisse Intl Mono** — Navigation, prices, metadata, button labels and footer links. Regular-width utilitarian mono, most often uppercase. If unavailable, use **Roboto Mono**. Font stack: "Suisse Intl Mono", "Roboto Mono", monospace.
- **Editorial Old** (only for community-focused brand storytelling) — Emotive editorial statements. Very light, high-contrast serif with narrow proportions and expressive joins. If unavailable, use **Cormorant Garamond**. 300; tune width before increasing size. Font stack: "Editorial Old", "Cormorant Garamond", Times, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| section-heading | Suisse Intl | 500 | 24px | 1.2 | -0.03em | Specifications, FAQ, recommendation and major section titles. |
| product-title | Suisse Intl | 500 | 20px | 1.2 | -0.02em | Opening purchase-panel title and medium chapter headings. |
| body | Suisse Intl | 400 | 16px | 1.4 | normal | General explanations, product-card titles and FAQ questions. |
| body-reading | Suisse Intl | 400 | 16px | 1.5 | normal | Longer feature descriptions alongside demonstrations. |
| price | Suisse Intl Mono | 400 | 16px | 1.2 | normal | Product-card prices. |
| detail | Suisse Intl | 400 | 14px | 1.4 | normal | Purchase-panel descriptions, bullet lists and specification entries. |
| navigation | Suisse Intl Mono | 400 | 14px | 20px | normal, uppercase | Navigation and repeating announcement text. |
| panel-price | Suisse Intl Mono | 400 | 14px | 1.2 | normal | Compact price opposite the opening title. |
| action | Suisse Intl Mono | 400 | 12px | 1 | normal, uppercase | Buttons and small utility links. |
| metadata | Suisse Intl Mono | 400 | 12px | 1.2 | normal, uppercase | Specification column labels and update metadata headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| community-focused brand storytelling | editorial | Editorial Old | 200 | 64px | 1 | -0.02em, features "calt", "dlig", "hlig", "liga" | A single expressive title in the testimonial environment. |
| community-focused brand storytelling | quotation | Suisse Intl | 400 | 24px | 1.25 | normal | Customer quotations in translucent scrolling cards. |
| scroll-led product anatomy demonstrations | anatomy-heading | Suisse Intl | 700 | 18px | 28px | normal | Labels beside illuminated product parts. |

**Notes:**

- The default hierarchy is deliberately compressed: titles are only 20–24px while the product image supplies scale. Do not enlarge all chapter headings to match the media.
- Negative tracking is confined to medium headings; mono labels and regular paragraphs retain normal tracking.
- Giant pixel lettering is graphic artwork, not the default heading font. Its stretched and stepped shapes can span a whole section without altering the text scale.

## Layout

**Density:** Airy at section scale and compact within controls: long media-led bands surround tightly grouped information.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Stacked purchase actions and compact action groups. |
| 12px | Commerce columns, media rails and small content groups. |
| 16px | Heading-to-description spacing and product-image-to-title separation. |
| 24px | Support-to-action spacing and specification label separation. |
| 28px | Purchase-panel inset. |
| 40px | Desktop outer gutter and explanatory media-grid gap. |
| 56px | Vertical surround for the update card. |
| 64px | Intro-to-media separation and specification heading-to-grid spacing. |
| 96px | Major section top and bottom padding. |

### Containers and grids

- **section-width**: side padding 40px. Full-bleed color bands with a 1360px content span at a 1440px viewport.
- **commerce-grid**: 4 columns · gap 12px. Equal 331px square product images and open captions beneath; also the specification grid.
- **demonstration-grid**: 5 columns · gap 40px. Two tracks for a short left explanation, three for an 800px right-hand video; reading copy itself is constrained to 320px.
- **anatomy-stage**: max width 1680px · 2 columns · gap 16px. A 3:2 product-to-copy split, with a 400px explanation centered in the narrower side.
- **portrait-rail**: 3 columns · gap 12px. Three 370px by 493px portrait videos centered within the ivory band.
- **intro-pair**: max width 700px · 2 columns · gap 12px. Compact centered two-column introduction, title left and 344px support/action group right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | purchase-panel | 28px |
|  | media-and-update-cards | 32px |
|  | purchase-actions | 64px |
|  | utility-actions | 9999px (pill) |
| community-focused brand storytelling | testimonial-cards | 24px |

## Surfaces and depth

### Surfaces

#### Light commerce canvas · level 0

**Use:** Specifications, FAQs and related products.

**CSS:** `background: #ffffff; color: #000000`

#### Ivory media band · level 0

**Use:** Real-use media and update-card surround.

**CSS:** `background: #efede6; color: #000000`

#### Dark product stage · level 0

**Use:** Product anatomy.

**CSS:** `background: #151515; color: #ffffff`

**Observed:** The background merges with the dark edges of the product rendering.

**Transfer:** Keep the object visibly lit without outlining the whole scene.

#### Charcoal chapter · level 0

**Use:** Software extension, interactive samples and newsletter.

**CSS:** `background: #191919; color: #efede6`

#### Purchase glass · level 1

**Use:** Opening conversion panel.

**CSS:** `background: rgba(53, 53, 53, 0.5); backdrop-filter: blur(80px); border-radius: 28px; padding: 28px; color: #ffffff`

**Observed:** The orange image underneath warms the panel into a translucent brown; over black it reads as dark gray. No drop shadow.

**Transfer:** Let the underlying scene set its visible tone rather than substituting an opaque brown card.

#### Clay update card · level 1

**Use:** An ongoing-product-support callout.

**CSS:** `background: #4a4a4a; border-radius: 32px; overflow: hidden; min-height: 500px; color: #ffffff`

**Observed:** A large monochrome product model crosses the center and right, under a black overlay at 0.2 alpha; compact white copy sits at left.

**Transfer:** Render the new product in the same gray material and keep metadata subordinate.

#### Testimonial glass · level 1

**Only for:** community-focused brand storytelling

**Use:** Customer remarks over a green environment.

**CSS:** `background: rgba(53, 53, 53, 0.3); backdrop-filter: blur(80px); border-radius: 24px; padding: 40px; color: #ffffff`

**Observed:** A narrow vertical column is clipped at the top and bottom of the green band.

## Components

### Floating navigation

**Use:** Shared top-level wayfinding.

**CSS:** `background: rgba(0, 0, 0, 0.5); backdrop-filter: blur(12px); border-radius: 0px 0px 24px 24px; width: 810px; height: 60px; margin: 0 auto; color: #ffffff`

**Text style:** `navigation` — Suisse Intl Mono 400 · 14px/20px · uppercase

**Observed:** Centered over the stage with a white logo at left, compact links across the middle, then locale icon and bag count. The current product turns green; the count is a small white square.

**Transfer:** Keep the navigation narrower than the viewport rather than stretching the glass across the whole page.

### Announcement ticker

**Use:** A thin repeating service or launch message above the opening stage.

**CSS:** `background: #ff6c2f; height: 36px; padding: 8px; overflow: hidden; color: #000000`

**Text style:** `navigation` — Suisse Intl Mono 400 · 14px/20px · uppercase

**Observed:** Repeated one-line messages have 32px side padding and run beyond both viewport edges; the strip persists while scrolling.

**Transfer:** Use one short truthful offer or availability message, repeated rather than several competing messages.

### Purchase panel

**Use:** Compact product identity and conversion over the hero.

**CSS:** `width: 472px; padding: 28px; background: rgba(53, 53, 53, 0.5); backdrop-filter: blur(80px); border-radius: 28px; color: #ffffff`

**Text style:** `product-title` — Suisse Intl 500 · 20px/1.2 · tracking -0.02em

**Observed:** Title and mono price share the first row. Financing or short reassurance follows, then a small description, optional bundle selector, stacked actions and five short square-bullet benefits.

**Transfer:** Preserve the compact retail hierarchy even if the product has no bundle or installment option.

### Primary purchase button

**Use:** Immediate conversion.

**CSS:** `height: 52px; width: 100%; padding: 12px 20px; border-radius: 64px; background: #37fa16; color: #000000`

**Text style:** `action` — Suisse Intl Mono 400 · 12px/1 · uppercase

**Observed:** The verb and price are centered in one line, occupying the full inner panel width.

**States:** Declared: hover background-color #22d504; focus-visible box-shadow is declared with a transparent ring.

**Transfer:** Keep the price attached to the purchase verb where there is a single purchasable configuration.

### Secondary purchase button

**Use:** Alternative cart action immediately under the primary action.

**CSS:** `height: 52px; width: 100%; padding: 12px 20px; border: 1px solid #ffffff; border-radius: 64px; background: transparent; color: #ffffff`

**Text style:** `action` — Suisse Intl Mono 400 · 12px/1 · uppercase

**Observed:** Same width and label alignment as the primary purchase control.

**States:** Declared: hover border-color #22d504, background-color #22d504 and color #000000; focus-visible box-shadow is declared with a transparent ring.

### Utility pill

**Use:** Media, community and browse actions outside the purchase panel.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; padding: 14px 16px; height: 44px; border-radius: 9999px; background: #000000; color: #ffffff`

**Text style:** `action` — Suisse Intl Mono 400 · 12px/1 · uppercase

**Observed:** Often ends in a small right arrow or chevron. A companion light-band action uses a black 1px outline and transparent ground; compact shop controls are 40px high.

**States:** Declared: hover background-color #22d504 and color #000000.

### FAQ row

**Use:** Right-column objection handling.

**CSS:** `border-top: 1px solid #000000; opacity: 0.6; padding: 16px 0px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `body` — Suisse Intl 400 · 16px/1.4

**Observed:** Question left, tiny down chevron right; rows are about 55px tall within a 674px-wide column. There is no rounded outer accordion card.

**States:** Declared: hover opacity 1.

### Product card

**Use:** Related-product rails and shop grids.

**CSS:** `display: flex; flex-direction: column; gap: 16px; width: 331px; color: #000000`

**Text style:** `body` — Suisse Intl 400 · 16px/1.4

**Observed:** Square edge-to-edge image first, title second, mono price third with 8px between title and price. The card has no enclosing border or shadow. Some bundles show a small translucent accessory inset over the image.

**States:** Declared: hover title color #22d504.

**Transfer:** Use distinct staged photographs per item rather than giving every product an identical gray tile.

### Persistent purchase capsule

**Use:** A continuing conversion affordance after leaving the opening.

**CSS:** `background: rgba(53, 53, 53, 0.5); border: 1px solid #595959; border-radius: 32px; backdrop-filter: blur(15px); width: 437px; padding: 24px; display: flex; flex-direction: column; gap: 12px`

**Observed:** Fixed near the lower-right edge, with compact product identity, an optional bundle line and a green buy action. The software variant is a shorter horizontal capsule.

**Transfer:** Keep this subordinate to the main page and avoid covering active demo controls.

### Footer link

**Use:** Policies and social destinations in the shared ending.

**CSS:** `color: #a3a3a3; text-decoration: none`

**Text style:** `action` — Suisse Intl Mono 400 · 12px/1 · uppercase

**Observed:** Two narrow link columns at the right, with 12px vertical spacing. Payment marks sit beneath them.

**States:** Declared: hover text-decoration-line underline.

### Email input

**Only for:** newsletter closing sections

**Use:** Compact signup form beside oversized lettering.

**CSS:** `height: 40px; width: 250px; padding: 0px 12px; border: 1px solid #a3a3a3; background: transparent; color: #efede6`

**Text style:** `navigation` — Suisse Intl Mono 400 · 14px/20px · uppercase

**Observed:** Square input paired with a dark submit pill; a pair of region radio choices precedes the email row.

**Transfer:** Keep the form small relative to the graphic, using one field rather than a tall lead-generation form.

## Imagery and graphics

### Sculptural product stage

**Use:** Opening and commerce imagery.

**Observed:** A warm beige and graphite physical device is shown in a low three-quarter view, casting a dark contact shadow on saturated orange. It occupies roughly the left two thirds of the opening, with no containing frame. Subsequent images zoom into tactile knobs, buttons and rear ports.

**Transfer:** Photograph or render the new object with directional studio light, a warm saturated ground and a low grounded shadow. If no 3D model exists, use a high-resolution cutout with a convincingly shaped contact shadow, not a tiny icon.

### Illuminated anatomy

**Use:** Scroll-led capability storytelling.

**Observed:** A stable three-quarter product floats against near-black; specific controls flash white with a soft glow while the matching explanation changes at right. Beige edges, black controls and fine surface texture remain visible.

**Transfer:** Keep the product angle fixed and highlight only the part relevant to each explanation. For a digital service, use a stable interface view and illuminate one functional area at a time.

**Build:** Place the object in the left 3/5 of a dark stage. Trace the current feature with a white SVG mask; layer a sharp white fill at low alpha beneath a duplicate blurred 16–24px at 0.25 alpha. Limit the glow to the active part, not the full object.

### Digital grain and word sculpture

**Use:** A required counterpoint to polished product imagery, placed within a demonstration or editorial chapter.

**Observed:** Pixel-stepped monumental lettering backs a wide performance video; elsewhere a low-resolution two-tone organic silhouette fills a sampler backdrop. The newsletter uses extremely tall ivory pixel lettering across the left portion of a charcoal band.

**Transfer:** Use a short content-relevant word or an abstract product silhouette as a graphic, not a new default typeface. A single high-quality two-tone pixel motif is enough to carry the device.

**Build:** Draw narrow uppercase letter outlines in SVG, rasterize to a small grid, then scale with nearest-neighbor edges to create square stair steps. Stretch vertically and crop at the section edges. For a silhouette, threshold a grayscale image into black and charcoal blocks at roughly 8–12px visual cells. Keep text controls above it on a separate layer.

### Real-use portrait rail

**Use:** Human proof within warm light bands.

**Observed:** Three portrait videos show hands operating hardware and people making work in lived-in studios. Natural room color, clutter and plants remain; 32px corners soften the frames. Small translucent handle labels sit near the bottom.

**Transfer:** Show actual use in credible workspaces, including hand-level close-ups. Avoid uniformly lit corporate portraits; a still sequence is an acceptable substitute for video.

### Monochrome support model

**Use:** Update or continued-support callout.

**Observed:** An oversized gray clay model tilts diagonally through a rounded dark-gray card, with soft material shading, no saturated colors and white text over the quieter left region.

**Transfer:** Use a neutral clay render or desaturated product close-up, leaving the new headline and version/date data over low-detail space.

### Software hologram stage

**Only for:** software product launches

**Use:** Alternative opening product media.

**Observed:** A large crisp dark interface floats at left over iridescent vertical slabs on black. Cyan, lilac, pink and warm reflected edges have a fuzzy analog-video halo; the interface remains legible.

**Transfer:** Pair an authentic interface view with an abstract light sculpture rather than recoloring the whole page purple.

**Build:** Behind the interface, layer three tall skewed translucent rectangles with narrow cyan and magenta edge gradients, variable white alpha and a small blur. Add faint noise over the slabs, keep the surrounding ground black and preserve the interface's sharp silhouette.

### Icons

**Observed:** Small functional arrows, chevrons and globe marks use 16px outlines, usually 1–1.3px strokes with round caps. Play triangles are solid white and larger social/service marks retain their own shapes.

**Transfer:** Choose sparse functional icons, matching the current text color; use 42px circular outlined previous/next controls beneath media and avoid decorative feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Object-led retail opening

**Observed:** The first 900px contains the entire orange product stage below a 36px ticker. Floating navigation sits centered at the top; the large three-quarter object owns approximately the left two thirds, with substantial orange air above. A Purchase panel is centered vertically on the right, inset 24px from that side. Back-to-front layers are orange photographic ground, object and contact shadow, navigation, then Purchase glass and its actions. The title uses product-title rather than monumental display type, with the price opposite; a short support paragraph, both purchase controls and benefit bullets are visible above the fold. More close-up product views and the anatomy chapter fall below.

**Transfer:** Default to this object-plus-retail-panel composition for a new product landing page. Without custom renders, use a strong product cutout on a warm photographic ground with a real shadow. Software launches use Software hologram stage with the same panel. Brand-led introductions can instead use an atmospheric collage, an emotive serif promise and one small white pill action.

**Avoid:** Do not turn this into a centered oversized sans headline over a small product thumbnail, or detach the purchase panel into an opaque white pricing card.

**Text style:** `product-title` — Suisse Intl 500 · 20px/1.2 · tracking -0.02em

### Feature illumination chapter

**Observed:** Dark product stage uses a 3:2 split: object at left, a centered 400px copy block at right. Each feature changes the illuminated area while keeping the object's angle steady. Feature labels use anatomy-heading and descriptions use body-reading.

**Transfer:** Use this for a product whose physical or functional parts benefit from sequential inspection; match each highlighted part with a single plain-language benefit.

**Text style:** `anatomy-heading` — Suisse Intl 700 · 18px/28px

### Explanation and demonstration

**Observed:** A 96px-padded band places a short heading and 320px explanation left, with an 800px-wide video at right on the five-track Demonstration grid. A small mono slide count sits below the media, opposite 42px circular arrow buttons. Variants use cool gray, black or charcoal grounds.

**Transfer:** Pair an actual demonstration with explanatory copy rather than expanding the paragraph to fill the whole left grid area.

**Text style:** `product-title` — Suisse Intl 500 · 20px/1.2 · tracking -0.02em

### Ruled information

**Observed:** Specifications use four equal columns with 12px gutters, metadata headings and repeated 1px top rules over 14px detail copy. FAQs use a heading in the left half and FAQ rows in the right half. Both have 96px upper breathing room and open white backgrounds; software specifications invert to white rules on black.

**Transfer:** Separate detailed facts from promotional media and use rule-based grouping instead of boxed feature cards.

**Text style:** `section-heading` — Suisse Intl 500 · 24px/1.2 · tracking -0.03em

### Ongoing support card

**Observed:** Ivory media band wraps Clay update card with 56px vertical space and 40px side gutters. A restrained product-title, short detail text and underlined link occupy the left; version and release date appear as a pair of metadata/value groups beneath.

**Transfer:** Use for software updates, maintenance, evolving capability or product care, retaining the monochrome product model.

**Text style:** `product-title` — Suisse Intl 500 · 20px/1.2 · tracking -0.02em

### Interactive sampler

**Observed:** A pixelated black-and-charcoal image backs a 96px-padded section. Section-heading sits left and short body copy at upper right. Three equal columns each contain an uppercase category label and five 57px ruled audio rows, number first, name second, solid play triangle last. Hover swaps the row to white with black text.

**Transfer:** For another product, make this a compact interactive proof library: audio, before/after states or short demo clips. Keep the technical row language and pixel-art ground.

**Text style:** `metadata` — Suisse Intl Mono 400 · 12px/1.2 · uppercase

### Human proof rail

**Observed:** Ivory media band contains Intro pair above Portrait rail, separated by 64px. Short medium heading left, compact body and two Utility pills right; portrait media fill most of the section below.

**Transfer:** Use authentic demonstrations or outcomes with short attribution, not a conventional logo wall.

**Text style:** `product-title` — Suisse Intl 500 · 20px/1.2 · tracking -0.02em

### Commerce continuation

**Observed:** A white band puts section-heading at left and a compact black browse pill at right. Product cards begin 40px beneath, four across with 12px gaps. A longer variant extends beyond the right edge and adds previous/next controls below.

**Transfer:** Offer adjacent products, editions or add-ons in square editorial product images rather than a second pricing table.

**Text style:** `section-heading` — Suisse Intl 500 · 24px/1.2 · tracking -0.03em

### Graphic signup and shared ending

**Observed:** The newsletter variant uses a 662px charcoal band with giant ivory pixel lettering across the left seven of twelve tracks and a 344px-wide form group to the right. The shared ending is a 400px black footer: small white brand mark upper left, two muted mono link columns upper right, payment marks beneath, locale and short closing phrase low left, copyright and small credit low right. Product landings move from Commerce continuation directly into this footer.

**Transfer:** Keep the footer spacious and utilitarian. For a newsletter-driven brand page, precede it with the giant-word/form contrast instead of a generic centered CTA strip.

**Text style:** `action` — Suisse Intl Mono 400 · 12px/1 · uppercase

### Editorial testimonial environment

**Only for:** community-focused brand storytelling

**Observed:** A 720px green band places a 384px text block in the left two fifths and translucent quotation cards in a clipped vertical column on the right. The heading is a 64px delicate serif, support is compact and a white pill supplies the action.

**Transfer:** Reserve this warmer expressive variant for a community or customer-story emphasis rather than applying green to every feature chapter.

**Text style:** `editorial` — Editorial Old 200 · 64px/1 · tracking -0.02em

## Page flow

**Storyline:** Product spectacle → inspect how it works → demonstrate the benefit → substantiate details → remove objections → show real use → offer a next purchase or connection → utilitarian close.

### Flagship physical-product landing page

1. **Promise and conversion** — Full-bleed object stage with translucent purchase panel, followed by macro detail views.
2. **Capability chapters** — Stable product anatomy with individual controls illuminated beside changing explanations.
3. **Product demonstration** — Light-ground video carousel followed by ruled feature descriptions.
4. **Continued value** — Monochrome update card, interactive sample library and complementary software demonstration.
5. **Objection handling** — Four-column specifications and two-column FAQ.
6. **Human proof and continuation** — Portrait real-use videos, a square-product rail and the black utility footer.

**Transfer:** Use the longer anatomy story only when there are several meaningful parts to inspect; keep the immediate conversion and quieter fact sections regardless of product category.

### Software-product landing page

1. **Promise and conversion** — Interface over iridescent light slabs with the shared purchase panel.
2. **Orientation** — Centered short explanation on ivory followed by a large embedded demonstration.
3. **Capability proof** — Dark explanation/video carousel and compact inverted specification grid.
4. **Objection handling** — Update card then a white FAQ section.
5. **Context and continuation** — Full-width real-use footage with a left-side dark blur gradient, related-product rail and black footer.

**Transfer:** Trade physical anatomy for a crisp interface and a demonstration; retain the small-title hierarchy and panel construction.

### Brand and multi-product discovery page

1. **Emotive promise** — Grainy cosmic collage with product above an expressive serif line and a large human portrait below.
2. **Brand world** — Full-bleed montage with a central television-style play tile, then two large square product features.
3. **Product philosophy** — Black four-column image-and-copy chapter with a small medium-weight statement.
4. **Human proof** — Ivory portrait rail and wide performance video over monumental pixel lettering.
5. **Commerce and belonging** — Square product rail then green editorial testimonials.
6. **Connection and close** — Charcoal giant-word signup band followed by the same 400px black footer.

**Transfer:** Use a more expressive opening for a brand story, then alternate tangible product proof and real people; do not make every section another hero.

## Writing

Plainspoken and technically fluent, with a dry, self-aware sense of humor. Product capabilities are described concretely, then softened with an occasional conversational aside rather than grandiose promises.

**Do not copy:** Do not reuse the brand or product names, artist associations, trademarked mechanisms, prices, shipping offers, release dates, customer quotes or specific performance claims. Examples demonstrate tone and structure only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the makers. Product names act as straightforward subjects in factual explanations.
- **Rhythm:** Short functional headings, one or two compact explanatory paragraphs, and brief verb-first actions. Longer technical sentences are balanced by a short colloquial payoff or a parenthetical joke.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product title | Name plus model or product category, without an inflated slogan. | 2–4 words | “Orchid ORC—1”<br>“Pistil Plugin” |
| Capability heading | Name the actual mechanism or useful behavior. | 2–5 words | “Bi-Directional Control”<br>“Polyphonic Chord Generation” |
| Playful section lead | A practical statement followed by a dry parenthetical reversal. | 4–10 words | “More features. (Because sometimes more is more.)” |
| Supporting explanation | Explain what it does and how the reader uses it, with specific controls or actions. | 20–65 words | “A single-octave, velocity-sensitive keyboard, used to determine the root note of chords.” |
| Primary action | Direct verb and optional price; no persuasion clause. | 2–5 words | “Buy Now $99 USD”<br>“Watch on Youtube” |
| Closing invitation | Short friendly invitation with knowingly old-fashioned administrative language in support. | 2–4 word title; one sentence support | “Stay Telepathic.”<br>“Input your electronic mail address here to receive the latest dispatches from our Corporate Headquarters.” |

**Words and phrasing to use:** find; play; ideas; sounds; built; control; explore; directly; to taste; a short parenthetical aside

**Avoid:** revolutionary ecosystem; unleash your limitless potential; game-changing solution; enterprise-grade synergy; excessive exclamation marks

**Rules:**

- Lead with an actual function before adding a creative benefit.
- Technical detail can be exact without becoming impersonal; explain what the control lets the reader do.
- Keep button labels literal, uppercase through styling rather than shouting in prose.
- One small joke can close a dense explanation; do not turn every label into a pun.

## Do's and Don'ts

### Do

- Keep purchase titles at 20px/24px and major section headings at 24px/28.8px.
- Use the 52px green purchase action above its matching outlined companion with an 8px gap.
- Maintain 40px desktop side gutters through both dark and light content bands.
- Give major chapters 96px vertical padding while keeping their descriptive columns around 320–400px.
- Use 12px mono uppercase labels for actions and metadata, with normal tracking.
- Stage square commerce images at 331px in four-column rails with 12px gaps.
- Let glass panels take color from the imagery beneath them; keep purchase glass at 0.5 alpha with 80px blur.
- Include a pixel-stepped graphic and a credible real-use demonstration as counterweights to clean product renders.

### Don't

- Do not set all headings in 64px serif; that recipe belongs to the expressive testimonial variant.
- Do not spread electric green across large background bands; concentrate it in controls and active states.
- Do not add card drop shadows to product rails, specifications or FAQ rows.
- Do not round the commerce image tiles just because portrait videos use 32px corners.
- Do not use wide tracking on mono labels; the technical character comes from the face and uppercase treatment.
- Do not replace the sparse black footer with a dense colorful sitemap or a giant centered sales slogan.
- Do not give specification facts individual floating cards; 1px top rules carry their grouping.
- Do not treat iridescent software-stage colors as a site-wide gradient palette.

## Motion and responsive

### Motion

**Observed:**

- Color and opacity interactions use .15s cubic-bezier(.4,0,.2,1) transitions.
- The testimonial column declares scroll-vertical 30s linear infinite.
- Product anatomy changes highlighted parts while the explanation advances through viewport-height chapters.
- Navigation declares a .15s transform transition; the announcement strip repeats horizontally.

**Transfer:**

- Keep product orientation stable while attention moves between parts.
- Use continuous slow motion only for ambient repeated material such as the quote column; preserve readability of the main explanation.

**Unknown:**

- Exact scroll-to-render interpolation and highlight sequencing are unknown.
- The horizontal ticker's timing is not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px, 1440px and 1680px.
- Purchase-panel classes specify 16px inner padding and 24px corners at smaller sizes, changing to 28px padding and 28px corners.
- The desktop anatomy grid is hidden below its medium breakpoint; the demonstration grid has a one-column base layout.

**Transfer:**

- On narrow layouts, keep the object and purchase content in a readable vertical stack rather than shrinking the 472px panel.
- Convert wide rails to horizontal browsing and preserve square commerce images and portrait real-use proportions.
- Reduce the graphic's width before reducing form legibility; keep pixel-stepped lettering as a separate art layer.

**Unknown:**

- The exact mobile anatomy replacement, mobile navigation and small-screen hero framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
