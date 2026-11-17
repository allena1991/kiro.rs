# OLIPOP — soda-shop sunshine

## Overview

A cheerful, tactile consumer style pairing chunky retro serifs with friendly geometric sans-serif text. Cream, deep bottle green, candy pink and fresh mint surround saturated product photography, cutout objects and playful illustration. It suits tangible products and benefit-led commerce, with roomy storytelling bands and denser, easy-to-scan shopping controls.

### Essentials

- Headlines feel like soft, weighty soda-shop lettering: WindsorEF at 90px/0.95 for the opening, 48–52px for section leads, weights 800–900 and normal tracking.
- The default opening is an equal split of invitation and irresistible object: two 720px-wide halves in a 660px-tall band, centered copy on pink opposite a full-bleed photographic close-up.
- Actions are small capsules rather than banners: 48px height, 50px radius and 18px bold Ano; green is the general action color, with magenta reserved for the pink opening.
- Color belongs to whole scenes, not scattered UI accents: cream carries shopping areas, pink and coral carry feature bands, emerald closes the page. Roughly half the default landing experience is cream-led, with the rest in vivid image or color chapters.
- Products are staged as desirable physical objects: glossy, sharply lit packshots with condensation and soft contact shadows, about 308–312px square in shopping rows; at least one oversized photographic product scene anchors the story. Use a lit object rendering or carefully masked photo when elaborate photography is unavailable.
- Playfulness extends beyond the packaging: retain starbursts or outlined doodles around a scene and a broad, shallow wave into the emerald footer. A simple SVG starburst-and-wave system supplies the equivalent for products without illustration assets.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bottle green | `#14433d` | `--color-ink` | text, action, border | Default text, filled general actions and outlines. |
| Closing emerald | `#008168` | `--color-emerald` | background, accent | Full-width closing surface and small trust accents. |
| Commerce green | `#034638` | `--color-commerce-ink` | text, border | Navigation labels, product names and shopping controls. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Candy pink | `#ff9ec8` | `--color-pink` | background | Default split-opening copy panel and product selection scenes. |
| Berry ink | `#5a0c3c` | `--color-plum` | text | Headline and supporting text on the pink opening. |
| Sparkling magenta | `#e31a82` | `--color-magenta` | action | Opening action on the pink panel. |
| Soft coral | `#ffb8b3` | `--color-coral` | background | Editorial split feature band. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text | Purchase controls and subscription panels; select reversed text. |
| Editorial cream | `#fff7e5` | `--color-warm-cream` | background, text | General green-button lettering; broad editorial backgrounds on story and subscription pages. |
| Vanilla cream | `#fff6ea` | `--color-canvas` | background, text | Main shopping canvas, navigation and reversed display text. |
| Cream edge | `#f3e4cd` | `--color-rule` | border | Thin shopping-group separators. |
| Deep caption green | `#0a3128` | `--color-caption-ink` | text | Small category captions under product imagery. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| berry-themed product detail pages | Berry lilac | `#f7cbef` | `--color-lilac` | surface, border | Gallery backing, ingredient band and hard-offset selection shadow. |
| berry-themed product detail pages | Berry milk | `#ffe4fb` | `--color-pale-pink` | background | Continuous product detail and review canvas. |
| subscription pages | Pale mint | `#edf6f3` | `--color-mint-light` | background, surface | Subscription introduction, FAQ rows and testimonial cards. |
| subscription pages | Seafoam | `#a7d1c5` | `--color-mint-mid` | background | Testimonial chapter. |
| subscription pages | Sage teal | `#78baaa` | `--color-mint-strong` | background | FAQ band. |
| company storytelling pages | Leaf milk | `#d7eddf` | `--color-mission-mint` | background | Illustrated values chapter. |

## Typography

- **WindsorEF** — Opening and section headlines, quotes, footer headings and small product-detail titles. Heavy, soft old-style serif with irregular rounded bowls, sloped stems and a nostalgic, almost hand-lettered silhouette. If unavailable, use **Fraunces**. Use 800–900 weights, soft rounded forms and normal tracking; preserve broad letter shapes. Font stack: "WindsorEF", "Fraunces", Georgia, serif.
- **Ano** — Paragraphs, navigation, commerce labels, captions and editorial subheadings. Friendly geometric sans with circular counters and open, approachable lowercase. If unavailable, use **Outfit**. Use 400–700 weights; do not tighten the tracking. Font stack: "Ano", "Outfit", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | WindsorEF | 800 | 90px | 0.95 | normal | Default opening invitation, usually two centered lines. |
| quote | WindsorEF | 800 | 54px | 1 | normal | Large centered endorsement on a colored illustrated band. |
| heading-lg | WindsorEF | 800 | 52px | 1 | normal | Centered shopping and recommendation section titles. |
| heading | WindsorEF | 800 | 48px | 1.1 | normal | Split editorial feature headings and large closing invitation. |
| scene-heading | WindsorEF | 800 | 48px | 62px | normal | Centered heading above the full-width photographic proof scene. |
| footer-heading | WindsorEF | 800 | 24px | 1.1 | normal | Footer navigation column headings. |
| body-lead | Ano | 400 | 20px | 1.4 | normal | Centered explanatory copy above large photography. |
| body | Ano | 400 | 18px | 1.4 | normal | Opening and editorial feature support text. |
| action | Ano | 700 | 18px | 28px | normal | General conversion buttons. |
| opening-action | Ano | 700 | 18px | 1 | normal | Magenta opening button. |
| body-small | Ano | 400 | 16px | 1.5 | normal | Detailed descriptions and footer links. |
| label | Ano | 700 | 16px | 1.4 | normal | Navigation labels and product tile titles. |
| caption | Ano | 400 | 14px | 1.8 | normal | Product category line below the rating. |
| filter | Ano | 600 | 14px | 1.2 | normal | Compact outlined category pills. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling pages | mission-display | WindsorEF | 800 | 96px | 1 | normal | Large illustrated chapter title. |
| catalog pages | catalog-display | WindsorEF | 800 | 80px | 1.1 | normal | Left-aligned collection opening title. |
| subscription pages | subscription-display | WindsorEF | 900 | 80px | 1 | normal | Benefit-led subscription opening. |
| company storytelling pages | editorial-heading | Ano | 700 | 50px | 1.4 | normal | Narrative chapter headings and values subheads. |
| product detail pages | product-title | WindsorEF | 900 | 40px | 1.1 | normal | Centered title above a product purchase form. |
| catalog pages | catalog-heading | WindsorEF | 800 | 40px | 1.1 | normal | Centered group headings above product grids. |
| subscription pages | compact-heading | WindsorEF | 900 | 32px | 1 | normal | Flavors, benefits and FAQ headings beside a sticky purchase panel. |
| company storytelling pages | editorial-body | Ano | 400 | 25px | 1.6 | normal | Long-form narrative paragraphs. |
| subscription pages | question | Ano | 600 | 20px | 1.2 | normal | FAQ questions and benefit labels. |

**Notes:**

- Normal tracking is integral at every size; the heavy serif supplies expression without compressed letterspacing or uppercase styling.
- Most marketing headings are WindsorEF, while the company narrative deliberately switches its subheadings to bold Ano. Do not spread that sans-serif hierarchy across ordinary landing sections.
- Use one semantic heading hierarchy even when the visual title treatment is shared with quotes or smaller footer headings.

## Layout

**Density:** Airy image-led bands with compact commerce labels and controls; large photographs do most of the work between short copy blocks.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Filter pill gaps and purchase-choice stacking. |
| 16px | Heading-to-support spacing and gallery gaps. |
| 20px | Filter horizontal padding, FAQ inner padding and row gaps. |
| 24px | Grid gaps and copy-to-action spacing. |
| 32px | Button side padding and detailed paragraph separation. |
| 35px | Small section-spacing token. |
| 55px | Site gutter and default section-spacing tokens. |
| 60px | Opening vertical padding and footer desktop side margin. |
| 80px | Opening side padding and catalog section padding. |
| 86px | Collection carousel top and bottom padding. |
| 96px | Illustrated story chapter vertical padding. |
| 100px | Subscription chapter padding. |
| 22px | Mobile site-gutter token. |

### Containers and grids

- **main-container**: max width 1320px · side padding 60px. Centered desktop navigation, shopping groups and footer interior.
- **opening-split**: max width 1440px · 2 columns · gap 0px. Equal-width edge-to-edge copy and photographic halves.
- **shopping-grid**: max width 1320px · 4 columns · gap 24px. Four object-led cards across on desktop; a final partial row is centered. Three-item bundles use a centered three-column row.
- **feature-split**: max width 1280px · 2 columns · gap 64px. About 506px of text balanced by a 560px image; vertically centered.
- **scene-copy**: max width 740px. Centered explanatory copy above a large product lineup.
- **product-detail-grid** (only for product detail pages): max width 1440px · 2 columns · gap 40px · side padding 40px. A 65:35 gallery-to-buybox split, with a sticky purchase column.
- **subscription-split** (only for subscription pages): 2 columns · gap 120px. Scrolling content on the left and a sticky 560px purchase panel on the right.
- **story-rows** (only for company storytelling pages): max width 1200px · 2 columns. Alternating text and illustration rows; four-person portrait row uses 250px circles and 80px gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 50px |
|  | category-pills | 9999px (pill) |
|  | media-and-panels | 16px |
| people and circular lifestyle collages | portrait | 50% |
| subscription pages | faq-row | 10px |
| product detail pages | dropdown | 48px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | pill-outline | `0px 0px 0px 1.5px #14433d` | Fine category-pill edge rather than a drop shadow. |
| berry-themed product detail pages | selected-choice | `4px 4px 0px 0px #f7cbef` | Hard, unblurred colored offset on selected purchase controls. |

### Surfaces

#### Vanilla canvas · level 0

**Use:** Primary shopping and general page surface.

**CSS:** `background: #fff6ea; color: #14433d`

**Observed:** Broad uninterrupted cream surrounds isolated objects rather than enclosing each in a card.

**Transfer:** Let product colors carry the variety against one stable warm canvas.

#### Pink opening · level 0

**Use:** Default split hero text half.

**CSS:** `background: #ff9ec8; color: #5a0c3c`

**Observed:** Flat color backed by sparse cream starbursts, not a gradient.

**Transfer:** Retain the flat confectionery color and dark berry text relationship.

#### Coral feature · level 0

**Use:** Illustrated editorial feature.

**CSS:** `background: #ffb8b3; color: #14433d`

**Observed:** Full-width surface connects text to a large circular collage.

**Transfer:** Use as a distinct story chapter, not a small accent card.

#### Emerald closing · level 0

**Use:** Closing invitation and footer.

**CSS:** `background: #008168; color: #fff6ea`

**Observed:** A shallow asymmetric wave meets the previous section; content remains flat and spacious.

**Transfer:** Carry the wave across the full browser width.

#### Berry detail canvas · level 0

**Only for:** berry-themed product detail pages

**Use:** Gallery and review world.

**CSS:** `background: #ffe4fb; color: #14433d`

**Observed:** A stronger lilac gallery square and ingredient band sit against pale pink.

**Transfer:** Choose a comparable two-tone product-color family for a different variant.

#### Lilac product stage · level 1

**Only for:** berry-themed product detail pages

**Use:** Featured gallery square and detailed product facts band.

**CSS:** `background: #f7cbef; border-radius: 16px`

**Observed:** The large gallery stage has rounded corners; the full-width facts band is square-edged and wave-separated.

**Transfer:** Use the rounded form only for contained media.

#### White purchase panel · level 1

**Only for:** subscription pages

**Use:** Persistent purchase configuration.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 10px 20px`

**Observed:** A 560px-wide panel is visually independent of the changing colored bands behind it.

**Transfer:** Keep the purchase task stable as explanatory chapters change.

#### Mint chapters · level 0

**Only for:** subscription pages

**Use:** Introduction and objection handling.

**CSS:** `background: #edf6f3; color: #14433d`

**Observed:** The introduction uses pale mint; FAQ outer band uses sage teal with pale-mint rows; testimonial band uses seafoam.

**Transfer:** Progress through distinct related flat greens, keeping the same dark text.

#### Leaf story chapter · level 0

**Only for:** company storytelling pages

**Use:** Illustrated principles and narrative.

**CSS:** `background: #d7eddf; color: #14433d`

**Observed:** Full-width background with a wavy top and alternating illustration rows.

**Transfer:** Let the illustrations float without individual card frames.

## Components

### Navigation

**Use:** Persistent site wayfinding.

**CSS:** `background: #fff6ea; height: 70px; color: #034638`

**Text style:** `label` — Ano 700 · 16px/1.4

**Observed:** Centered arched wordmark, three links at left, store/account/cart tools at right. A separate 40px dark-green announcement strip with centered text and end chevrons makes the combined header 110px tall.

**States:** Declared: hover bottom border becomes bottle green; focus-visible bottom border becomes bottle green.

**Transfer:** Use the new brand's compact wordmark in the center, keeping the balanced left and right groups.

### Primary button

**Use:** General conversion action beneath support copy.

**CSS:** `background: #14433d; color: #fff7e5; border-radius: 50px; padding: 10px 32px; height: 48px`

**Text style:** `action` — Ano 700 · 18px/28px

**Observed:** Centered text only. Width follows label except in larger scene CTAs, where it expands to 274px.

**States:** Declared: hover background rgb(24 49 42 / 1), color rgb(255 247 229 / 1); focus-visible not specified; active matches hover.

### Opening button

**Use:** Single action in the pink opening.

**CSS:** `background: #e31a82; color: #fff6ea; border-radius: 50px; padding: 15px 32px; height: 48px`

**Text style:** `opening-action` — Ano 700 · 18px/1

**Observed:** The only bright magenta conversion button in the default landing composition; aligned to the centered text group.

### Category pill

**Use:** Collection switching and anchored group navigation.

**CSS:** `border-radius: 9999px; box-shadow: 0px 0px 0px 1.5px #14433d; padding: 8px 20px 6px; color: #14433d; display: flex; align-items: center; justify-content: center`

**Text style:** `filter` — Ano 600 · 14px/1.2

**Observed:** Single horizontal row with 8px gaps. Active pill reverses to green fill and light text; the whole category row persists below the main header during catalog browsing.

### Product tile

**Use:** Carousel, catalog grid and recommendations.

**CSS:** `display: grid; position: relative`

**Text style:** `label` — Ano 700 · 16px/1.4

**Observed:** Unboxed product on cream, square 308–312px image area with contain sizing, soft photographic contact shadow, optional scalloped burst near its upper-right edge. Below: tiny rating stars, 14px category caption, then bold 16px title. Caption area has 16px top, 20px side and 24px bottom padding.

**Transfer:** Use consistent image scale across variants; show a multi-object arrangement for bundles rather than a generic box.

### Footer link

**Use:** Help and company columns.

**CSS:** `color: #fff6ea`

**Text style:** `body-small` — Ano 400 · 16px/1.5

**Observed:** Plain text links below serif column headings, no enclosing buttons; each column reads as a vertically spaced list.

### FAQ row

**Only for:** subscription pages

**Use:** Compact objection handling beside the sticky purchase panel.

**CSS:** `background: #edf6f3; border-radius: 10px; padding: 20px; border: none; max-width: 600px`

**Text style:** `question` — Ano 600 · 20px/1.2

**Observed:** Question aligned left with a small downward chevron at right; closed rows are 64px high with 20px gaps.

### Product dropdown

**Only for:** product detail pages

**Use:** Variant and delivery-frequency selection.

**CSS:** `background: #ffffff; border: 1.5px solid #14433d; border-radius: 48px; height: 51px; overflow: hidden`

**Text style:** `label` — Ano 700 · 16px/1.4

**Observed:** Wide capsule trigger with a thumbnail or label at left and chevron at right; label typography is smaller inside the actual product form.

**Transfer:** Keep the entire row operable, not only the chevron.

### Purchase choice

**Only for:** berry-themed product detail pages

**Use:** One-time versus recurring purchase selection.

**CSS:** `background: #ffffff; border: 1.5px solid #034638; border-radius: 16px; box-shadow: 4px 4px 0px 0px #f7cbef`

**Text style:** `caption` — Ano 400 · 14px/1.8

**Observed:** Radio and plan name on left, price on right. Selected row has a strong edge and hard lilac offset; unselected row has a lighter lilac edge. Radio is 20px with a 2px green border and inset dot.

### Sticky purchase panel

**Only for:** subscription pages

**Use:** Persistent configuration alongside explanatory chapters.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 10px 20px; max-width: 560px`

**Text style:** `label` — Ano 700 · 16px/1.4

**Observed:** Rating, serif product name, current and struck-through prior price, small savings tag, many 60px circular variant thumbnails, frequency selector, quantity control and green cart action. Sticks through the selection, benefits and FAQ chapters, then yields to full-width testimonials.

## Imagery and graphics

### Sensory hero photography

**Use:** Default opening and major product proof scenes.

**Observed:** The opening right half is a tight, full-height product portrait with visible condensation, fruit in the foreground and warm festive bokeh behind it. Another scene places five vivid cans on oversized translucent ice against a bright cloudy blue sky; objects occupy the lower half beneath centered copy.

**Transfer:** Photograph the new product with relevant tactile materials and a strong light source. Minimum equivalent: a clean cutout or realistic render, two physical props, contact shadows and a deliberately lit background; retain a large recognizable silhouette.

### Packshot shelf

**Use:** Shopping rows, bundles and related products.

**Observed:** Upright, front-facing cans isolated on cream with soft gray-green shadows, saturated labels and crisp metallic edges. Bundles arrange multiple objects in a compact cluster, while individual items preserve comparable apparent size.

**Transfer:** Use transparent-background photography or renderings; align object baselines and leave air around them. Do not turn each image into a differently colored card.

### Sparkle and doodle frame

**Use:** Opening decoration and endorsement band.

**Observed:** Cream needle-like starbursts float around the pink hero copy. On green, small irregular outlined circles, dots and stars enter from the edges; they support rather than compete with the big serif quote.

**Transfer:** Retain a restrained hand-drawn or starburst accent vocabulary around at least one scene.

**Build:** Create SVG stars with 8 alternating long and short points, fill with the cream token, and vary sizes around 20–90px near panel edges. Add a few 8–24px circles and five-point stars with irregular 2–3px dark outlines in the colored quote scene. Keep the text's central rectangle clear.

### Circular lifestyle collage

**Use:** Coral feature and subscription introduction.

**Observed:** A candid outdoor drinker fills a large roughly circular window, outlined in black and topped with radiating candy-color strips and tiny stars. The subscription version combines a circular photo of friends with product and splash cutouts overlapping the edge and green outline doodles.

**Transfer:** Use candid product-use photography with a circular mask and one or two overlapping contextual objects; the minimum is one photo plus a few radial SVG wedges.

**Build:** Mask a 560px square photo with a slightly irregular circular clip path. Add a thin dark outline. Overlay triangular radial wedges from a shared center near the upper middle, alternating pink, cream, emerald and sky-toned art colors, with narrow dark strokes; keep the person's face and product unobscured.

### Wavy section boundary

**Use:** Signature chapter transitions and every footer entrance.

**Observed:** Broad shallow organic waves, not zigzags or tight scallops. Footer transition spans 1440px and uses a 98px-high wave region; subscription transitions use 41–60px-high wave strips.

**Transfer:** Require a wavy entrance into the closing green surface, regardless of what section precedes it.

**Build:** Use a full-width SVG with viewBox 0 0 1440 98 and preserveAspectRatio none. Draw one smooth asymmetric cubic curve across the top, descending gently near the right-center then rising to the edge; close the path to the bottom and fill with emerald. Overlap by 1px to avoid seams.

### Fruit-sticker closing scene

**Use:** Final location or availability call before the footer.

**Observed:** Cream background with oversized flat fruit stickers entering from the edges, white sticker rims and a clear central heading-and-button area. The fruit artwork continues toward the footer wave.

**Transfer:** Replace fruit with simplified colorful objects relevant to the new product, keeping a clear central invitation.

**Build:** Make 4–6 simple SVG silhouettes with saturated flat fills, limited internal lines and thick cream-white perimeter strokes. Rotate them slightly and partly clip them at the outside edges of a 660px-tall cream band.

### Editorial people and principles

**Only for:** company storytelling pages

**Use:** Origin, expertise and values chapters.

**Observed:** Founders shown in a relaxed rectangular studio portrait on a neutral backing; expert portraits appear in 250px circles with individually colored backgrounds. Values use flat cut-paper-like figures, potted plants and everyday objects on mint, with no shadows or frames.

**Transfer:** Use real team photography for credibility; illustrate the new company's principles through simple human scenes rather than literal diagrams.

**Build:** For values art, assemble flat vector leaves, rounded limbs, clothing polygons and simple vessels with a small warm-and-green palette; use sparse dots and leaf-vein strokes, no gradients. Alternate illustration and text sides.

### Pastel product theater

**Only for:** catalog and company storytelling openings

**Use:** Multi-product introductory scene.

**Observed:** Saturated cans and filled glasses on stepped mint plinths, directional daylight shadows and a mint backdrop fading lighter near the floor. The story title is centered above the group; catalog copy sits to the left of a right-heavy arrangement.

**Transfer:** Group a few objects at different heights on a monochrome pastel stage; maintain empty space for dark-green title text.

### Icons

**Observed:** Commerce tools are compact green outline icons around 28px; chevrons use rounded 2px strokes, usually 7–16px. Ratings under tiles use 10px stars. Social marks reverse to light on green at 24px; benefits combine thin line drawings with circles.

**Transfer:** Choose rounded, simple outlines for functional controls. Keep colorful illustrated badges separate from the small utility icon system.

## Section recipes

How recurring sections are built.

### First screen: Split invitation opening

**Observed:** A 40px green announcement strip and 70px cream sticky navigation sit above a 660px equal split. Back-to-front on the left: flat Pink opening surface, sparse cream starburst artwork, centered two-line display headline in plum, support paragraph at 18px/1.4 within 463px, then Opening button separated by 20px. The headline group is at most 521px wide, with 16px before support. Right: full-bleed sensory photograph, with an upright product dominating the frame and a small burst badge near its top. The hero ends at 770px, so the complete headline, description, action and main object are visible within the first 900px, along with the start of the next cream section and its centered title; product rows fall below.

**Transfer:** Use a short invitation and one unmistakable object, keeping equal visual weight between word panel and photo. Without elaborate photography, build a lit render or cutout still life with props in the right half. Product detail opens instead with a 65:35 gallery/buybox; subscription opens with left benefits and right circular lifestyle collage; catalog and company narratives use the pastel product theater.

**Avoid:** Do not replace the equal split with a centered SaaS headline over a tiny product image, or stretch the hero so the action falls below the first screen.

**Text style:** `display` — WindsorEF 800 · 90px/0.95

### Cream shopping shelf

**Observed:** Vanilla canvas with centered heading-lg, Category pill row 20px below, then an object-led Product tile carousel with side items clipped by the viewport. The section uses 86px vertical padding. Catalog variants use a centered catalog-heading, small practical label and support line above four-column grids, separated by 1px cream edges.

**Transfer:** Let visitors compare variants through object colors and short labels. For few items, center the row instead of stretching cards.

**Text style:** `heading-lg` — WindsorEF 800 · 52px/1

### Photographic proof scene

**Observed:** An 806px full-width photographic band places scene-heading and body-lead at the top center, within 740px, followed by Primary button after 24px. Oversized chilled products fill the lower half with no card border.

**Transfer:** Make one desirable setting prove the promise; reserve a naturally low-detail area above the object lineup for text.

**Text style:** `scene-heading` — WindsorEF 800 · 48px/62px

### Big endorsement band

**Observed:** A full-width green image-backed chapter centers a cream 54px serif quote within 1024px, with small publication marks as slide selectors above and outlined doodles at outer edges.

**Transfer:** Feature one short, credible endorsement at display scale and use a compact attribution or source-selector treatment. Let its content determine the band's depth.

**Text style:** `quote` — WindsorEF 800 · 54px/1

### Paired choices

**Observed:** Cream heading over two side-by-side 632px square lifestyle images, followed by centered 32px serif option names, 16px explanatory text and green capsule actions. The image corners are softly rounded.

**Transfer:** Use for two meaningful formats or use cases, not a general feature-card grid.

### Coral editorial split

**Observed:** Coral feature holds a left text column about 506px wide with heading, short body and Primary button, balanced by Circular lifestyle collage around 560px across on the right. The band is 672px high with 54px top and 56px bottom padding.

**Transfer:** Use one human-scale benefit and show the product in actual use; retain the asymmetry between restrained copy and exuberant art.

**Text style:** `heading` — WindsorEF 800 · 48px/1.1

### Wavy closing invitation

**Observed:** The availability call uses a 660px cream scene, centered 48px heading and green pill action amid oversized sticker illustrations. Emerald closing enters through a shallow full-width wave. Footer interior spans 1320px with 60px sides: 540px-wide invitation at left in 48px serif, social icons immediately below, and two narrower link columns at right under 24px serif headings. A small certification mark sits low on the left; copyright and inline legal links finish the bottom row. The green footer itself is 583px high.

**Transfer:** End with a concrete next step, then a large friendly invitation and useful footer links. Keep the wave and the contrast between oversized invitation and small navigation; use only genuine accreditation marks.

**Text style:** `heading` — WindsorEF 800 · 48px/1.1

### Facts and real reviews

**Only for:** product detail pages

**Observed:** Lilac full-width facts chapter separates description and storage guidance from a compact ruled facts label, then a row of monochrome certification marks. Waves frame the chapter. Reviews continue on pale pink: large serif heading, 48px numeric score, rating histogram and outline review action, followed by separated horizontal rows with author at left, rating and serif review title in the center, date at right and small helpfulness pills below. Pagination precedes a cream related-product shelf.

**Transfer:** Replace the facts label with the category's actual specs or ingredients. Keep verified facts and customer opinion visually distinct, without putting each review in a floating card.

### Persistent subscription explanation

**Only for:** subscription pages

**Observed:** Pink product selection, light-pink descriptive panel, cream benefits and sage-teal FAQ run down the left side while Sticky purchase panel stays at right. Benefit content uses a two-by-two icon grid; FAQ row components stack below a 32px heading. Full-width seafoam testimonials follow, with two pale-mint 400px cards, portrait strips, stars, centered quotes and linked product context. A pale-green eight-icon trust strip leads into a cream recommendation section with four pastel purchase cards.

**Transfer:** Use this variant when users need a configurable recurring offer. Keep the purchase panel stable through changing explanation, then release the layout into social proof.

### Illustrated editorial chapter

**Only for:** company storytelling pages

**Observed:** After the pastel theater, a cream origin split uses bold sans editorial-heading and 25px/1.6 narrative beside a large real portrait. A centered expertise introduction leads to four circular portraits with names, institutions and underlined biography links. Leaf story chapter then uses a 96px serif title over three alternating text/illustration rows in a 1200px container.

**Transfer:** Use a real origin narrative and credible people, then express a few relevant principles through human illustrations; vary the number of rows with the material.

**Text style:** `editorial-heading` — Ano 700 · 50px/1.4

## Page flow

**Storyline:** Invitation → explore choices → desirable product demonstration → proof and explanation → lower-friction next step → generous wavy closing.

### Broad consumer marketing landing

1. **Promise** — Equal pink invitation and sensory product photograph.
2. **Explore choices** — Cream carousel and category pills.
3. **Product demonstration** — Oversized products on ice beneath concise explanation.
4. **Social proof** — Display-scale endorsement on a doodled green scene.
5. **Choice clarification** — Two photographic option tiles with separate actions.
6. **Benefit explanation** — Coral split with circular human collage.
7. **Closing call** — Sticker-framed availability action, then wavy emerald invitation and footer.

**Transfer:** Balance immediate desire with practical comparison and a low-friction final action; adapt the sequence to the product.

### Single-product purchase and validation

1. **Purchase** — Tinted gallery beside sticky buybox with variant, pack, frequency and quantity controls.
2. **Product facts** — Wave-separated lilac description and compact ruled facts label with trust marks.
3. **Product demonstration** — Wide image strip before review content.
4. **Social proof** — Aggregate rating and histogram followed by long horizontal review rows and pagination.
5. **Alternative choices** — Cream four-product recommendation shelf.
6. **Closing call** — Shared wavy emerald footer.

**Transfer:** Lead with the actual purchase task, then facts and transparent opinion; keep related options after validation.

### Recurring offer conversion

1. **Promise** — Pale-mint benefits opening with short checked list, action and lifestyle collage.
2. **Configuration** — Large product on pink beside sticky white purchase panel.
3. **Benefit explanation** — Flavor description and two-by-two benefits on alternating pastel bands.
4. **Objection handling** — Pale FAQ rows on sage teal while configuration remains available.
5. **Social proof** — Two large portrait-and-quote cards on seafoam.
6. **Quantified proof** — Compact icon-and-label trust strip.
7. **Alternative choices** — Cream invitation and four pastel recommendation cards.
8. **Closing call** — Shared wavy emerald footer.

**Transfer:** Make repeat-purchase convenience explicit and keep configuration visible while resolving doubts.

### Company narrative and credibility

1. **Promise** — Oversized centered serif statement over mint product theater.
2. **Origin** — Cream split of long-form sans text and founder portrait.
3. **Authority** — Centered introduction and four circular expert portraits with biography links.
4. **Principles** — Large serif chapter title and alternating illustrated narrative rows on pale mint.
5. **Closing call** — Shared wavy emerald footer directly after the last illustrated row.

**Transfer:** Use this expanded sans narrative only for editorial company material; do not force a product-selection ending.

### Complete assortment discovery

1. **Promise** — Short left title and support over a right-heavy pastel product stage.
2. **Wayfinding** — Sticky row of compact category pills.
3. **Choice comparison** — Repeated centered group introductions with four-column unboxed packshot grids, partial rows centered and hairline separators.
4. **Broader choices** — Smaller formats, limited items and finally a three-item bundle row.
5. **Closing call** — Wavy emerald footer directly after the assortment.

**Transfer:** Group by meaningful buying criteria; retain consistent object size and repeatable labels across long grids.

## Writing

Warm, playful and sensory, with a pragmatic commerce layer underneath. Benefits are framed as everyday pleasures rather than clinical lectures, while ingredients and practical information are stated plainly.

**Do not copy:** Do not reuse OLIPOP names, logos, proprietary blend names, package illustrations, certification marks, customer quotations, flavor descriptions, discount amounts or health and nutrition claims. Write equivalent content from the new product's verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your; use we and our for the maker. Invitations are conversational, and support language reassures rather than pressures.
- **Rhythm:** Short, often 3–6 word headlines; one compact support paragraph; simple verb-led actions. Longer editorial paragraphs are reserved for origin and principles. Contractions, gentle puns and an occasional ellipsis keep the voice informal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A warm invitation or compact everyday metaphor. | 3–5 words | “Come sip with us”<br>“Soda on Tap” |
| Supporting copy | Pair sensory pleasure with a concrete benefit in plain language. | 1–2 sentences | “An unforgettable blackberry & smooth vanilla combination.” |
| Primary action | Verb plus a personally relevant destination or choice. | 2–4 words | “Find Your Flavor”<br>“Subscribe Today” |
| Reassurance headline | A friendly question with a small topical wordplay. | 5–7 words | “Trust your gut... or ours?” |
| Category support | Short practical instruction followed by a light playful line when appropriate. | 1–2 short sentences | “Store anywhere. Chill to enjoy.”<br>“Here for a good time, not a long time. Grab these flavors before they sip away!” |
| Closing invitation | State a tangible reason to stay connected, without elaborate brand philosophy. | One short headline | “Sign up to get 15% off your first order” |

**Words and phrasing to use:** your favorite; real; crisp; smooth; refreshing; crafted; no worries; swap, skip, or cancel; enjoy

**Avoid:** revolutionary ecosystem; disruptive platform; biohacking miracle; luxury exclusivity; aggressive scarcity language

**Rules:**

- Lead with the experience, then support it with concrete product facts.
- Use playful language in headings and category support, not in ingredient lists or purchase terms.
- Make recurring-order reassurance direct and specific.
- Keep actions understandable outside their surrounding paragraph.
- Tie any benefit, discount or trust badge to a substantiated fact.

## Do's and Don'ts

### Do

- Keep the default hero at equal text/photo widths with a 90px heavy serif invitation.
- Set ordinary section leads at 48–52px with normal tracking and deep-green ink.
- Preserve the 48px capsule action and compact 18px bold label.
- Use 308–312px square image areas and 24px gaps for consistent shopping shelves.
- Keep product category captions at 14px/1.8 beneath tiny rating stars.
- Retain the full-width wave into the green footer and its 48px invitation.
- Use 16px corners for contained media and purchase panels, not every page band.
- Pair an exuberant image with a short text column rather than making both sides visually dense.

### Don't

- Do not use a thin elegant fashion serif in place of the weight-800 rounded display face.
- Do not apply negative tracking to the geometric sans or headline recipes.
- Do not enclose the cream shopping grid in white cards with gray drop shadows.
- Do not distribute magenta through every button; it belongs to the pink opening action.
- Do not turn the shallow wave into a repeating scalloped or jagged border.
- Do not use soft elevation shadows for selected purchase rows; their offset is 4px and unblurred.
- Do not make utility icons colorful stickers; keep green functional outlines distinct from decorative badges.
- Do not use 25px editorial paragraphs throughout a product landing; ordinary support is 18–20px.

## Motion and responsive

### Motion

**Observed:**

- Common actions declare 0.25s ease-in-out transitions.
- Gallery backing declares background-color 0.35s ease-in; product dropdown declares box-shadow 0.2s; selected choice declares border-color 0.2s, box-shadow 0.2s.
- Sticky navigation, catalog category navigation and purchase columns remain available during scrolling.

**Transfer:**

- Keep state changes focused on fill, outline and the hard offset selection shadow.
- Let the subscription buybox persist only through the explanatory chapters, releasing before full-width social proof.

**Unknown:**

- Carousel autoplay intervals, entry-animation choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- A 22px mobile site-gutter token is declared alongside a 55px desktop gutter token.
- CSS contains numerous breakpoints, including 640px, 768px, 990px and 1024px; desktop is the established composition.

**Transfer:**

- On narrow screens, preserve the strong relationship between colored invitation and large object by stacking the two hero panels rather than shrinking both into columns.
- Convert four-column object grids into fewer columns while retaining uniform image scale; keep category pills horizontally scrollable.
- Release sticky side purchase panels into normal flow and keep their configuration groups intact.
- Keep the closing wave shallow and full-width when footer columns stack.

**Unknown:**

- Exact mobile font sizes, ordering and breakpoint-specific sticky behavior are not established; the narrow-screen adaptations are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
