# Little Amps — analog neighborhood energy

## Overview

A warm, music-loving storefront style with the familiarity of a neighborhood hangout. Cream paper, dark brown lettering, rusty red, ochre and faded blue surround candid photography and mischievous line drawings. Narrow, soft-edged serif headlines meet utilitarian monospace labels and friendly sans-serif paragraphs; dense little product details sit between generous photographic scenes. It suits tactile products, independent makers and service brands with real people behind them.

### Essentials

- An atmosphere comes before the sales pitch: a 1410×720px photographic stage inside a 15px apricot frame, with 22px corners and a 400px-wide stacked identity at upper left; use a close-up of a real making or using ritual when no film exists.
- Soft, compressed serif headlines feel like an independent record sleeve: Little Amps at weight 500, typically 44.8px/1 with -0.1em tracking; the photographic feature headline is 51px/0.8 with the same tracking.
- Actions look like tiny printed slips, not app buttons: uppercase Necto Mono at 13.6px/0.85, 0.05em tracking, 3px 6px padding, 20px height and 2px corners.
- Cream and brown carry the reading areas; color arrives as specific framing devices: a 32px blue announcement strip, an apricot opening frame, a blue split-panel band and a rust-red closing frame. Blue and ochre also pick out short serif phrases, never whole body paragraphs.
- Images alternate between lived-in warmth and orderly merchandise: room-scale process photographs with deep shadows, then centered isolated objects on pale oatmeal rectangles, with 36px cell padding and thin dividing rules.
- Hand-drawn personality and a social ending are signature devices: brown outlined mascots or object doodles accompany headings, and a red-backed strip of 91px square community pictures closes the page. Make new line art from the product's own tools and rituals; use real process thumbnails if community pictures are unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Roasted brown | `#522c25` | `--color-ink` | text, background, action | Default lettering, line art and dark action slips; also the backing beneath large photographic scenes. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt ochre | `#c46500` | `--color-ochre` | accent, action, link | Selected serif phrases and small actions, paired with cream lettering. |
| Rust red | `#c03001` | `--color-rust` | background, action, accent, link | Closing frame, selected heading phrases and alternating small action slips. |
| Apricot | `#febf6f` | `--color-apricot` | background, action | Opening frame and small alternate action slips. |
| Faded blue | `#89b4ca` | `--color-blue` | background, accent, action | Announcement strip, split-section frame and alternating action slips. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted brown | `#977e77` | `--color-muted` | text | Secondary footer links: brown at 60% alpha over cream, yielding this visible warm gray-brown. |
| Paper seam | `#e6dad4` | `--color-rule` | border | Single-pixel section and cell dividers. |
| Oatmeal paper | `#f6ede3` | `--color-oatmeal` | surface, text, action | Merchandise media backing, footer interior and pale actions over photographs. |
| Warm cream | `#fff9f2` | `--color-canvas` | background, text, surface | Main reading canvas, split-panel text field and light text on dark actions. |

## Typography

- **Little Amps** — Serif headings, editorial introduction and merchandise names. Narrow, irregularly friendly serif with soft terminals and an analog printed character. If unavailable, use **Bree Serif**. Use 400; narrow the composition by line wrapping rather than adding bold weight. Font stack: "Little Amps", "Bree Serif", Georgia, serif.
- **Inclusive Sans** — Descriptions, forms and supporting paragraphs. Open, unpretentious sans serif with conversational texture. Font stack: "Inclusive Sans", Arial, sans-serif.
- **Necto Mono** — Navigation, announcement, section labels, dates and action slips. Light utilitarian monospace, usually spaced capitals. If unavailable, use **Roboto Mono**. Use 400 with 0.05em tracking. Font stack: "Necto Mono", "Roboto Mono", ui-monospace, monospace.
- **Roboto Mono** — Prices and slide counters. Even-width numerals, lightly tightened for prices. Font stack: "Roboto Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| feature-display | Little Amps | 500 | 51px | 0.8 | -0.1em | fixed | Compact two-line headline over a large photographic feature; the opening identity is artwork rather than live text. |
| heading | Little Amps | 500 | 44.8px | 1 | -0.1em | fixed | Default section headings and split-panel headline pairs. |
| statement | Little Amps | 500 | 41px | 1 | -0.1em | fixed | Large editorial paragraph with individual colored phrases. |
| product-title | Little Amps | 500 | 20px | 1 | -0.1em | fixed | Names beneath merchandise images. |
| body | Inclusive Sans | 400 | 16px | 1.1 | normal | fixed | Main supporting paragraphs, kept in short columns. |
| footer-heading | Necto Mono | 400 | 16px | 1 | 0.05em, uppercase | fixed | Footer link-group headings. |
| navigation | Necto Mono | 400 | 14px | 1.1 | 0.05em, uppercase | fixed | Navigation labels. |
| small-body | Inclusive Sans | 400 | 14px | 1.1 | normal | fixed | Footer links, form labels and compact benefits copy. |
| price | Roboto Mono | 400 | 13.7px | 1.1 | -0.02em | fixed | Small prices aligned alongside names or immediately below them. |
| action | Necto Mono | 400 | 13.6px | 0.85 | 0.05em, uppercase | fixed | Primary and secondary action slips. |
| excerpt | Inclusive Sans | 400 | 13px | 1.1 | normal | fixed | Truncated editorial and merchandise descriptions. |
| date | Necto Mono | 400 | 13px | 1.1 | 0.05em, uppercase | fixed | Dates above editorial titles. |
| label | Necto Mono | 400 | 12px | 1.1 | 0.05em, uppercase | fixed | Announcement text, product origin or category labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| story and business-service pages | interior-hero | Little Amps | 500 | 57.6px | 1 | -0.1em | size clamp(56px, 4vw, 68px) | Live cream headline over an edge-to-edge photographic opening. |
| business-service pages | benefit-heading | Little Amps | 500 | 28.8px | 1 | -0.1em | fixed | Titles beneath illustrated benefits. |
| directories | directory-title | Little Amps | 500 | 18px | 1 | -0.1em | fixed | Compact entity names in a ruled listing grid. |
| directories | directory-address | Inclusive Sans | 400 | 12px | 1.5 | normal | fixed | Addresses beneath directory titles. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The serif is visibly much more expressive than the sans; keep its -0.1em tracking across headline and small title roles rather than replacing it with a neutral bold grotesk.
- Uppercase mono has 0.05em tracking; prices instead use -0.02em. Supporting sans paragraphs retain normal tracking and compact 1.1 line height.
- Opening and footer identities are stacked artwork. Their scale comes from widths of 400px and 385px respectively, not from inflating every live heading.

## Layout

**Density:** Airy photographic chapters with compact, information-rich merchandise and editorial cells.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Tiny action horizontal padding and inline content gaps. |
| 12px | Navigation link padding and compact text-stack gaps. |
| 15px | Outer frame inset for hero, split panel and footer. |
| 16px | Media-to-editorial-text gap and footer heading separation. |
| 20px | Headline-to-support spacing and directory cell padding. |
| 24px | Declared main-padding token and separation between form fields. |
| 30px | Footer interior padding and merchandise media-to-title space. |
| 36px | Primary content side padding and product cell padding. |
| 48px | Editorial statement vertical padding and section transitions. |
| 100px | Major merchandising and editorial chapter breathing room. |

### Containers and grids

- **reading container**: side padding 36px. Full-width desktop composition with 1368px usable space at a 1440px viewport; avoid a narrow centered blog column.
- **merchandise grid**: 4 columns · gap 0px. Equal ruled columns; a photographic feature spans three columns beside one product, with individual products continuing below.
- **split contact**: 2 columns · gap 15px · side padding 15px. Nearly equal photo and text halves, each about 698px wide and 720px tall.
- **support measure**: max width 450px. Short text column inside the larger split-panel field.
- **benefits grid** (only for business-service pages): 4 columns · gap 72px · side padding 36px. Four illustrated benefit columns with roughly 288px-wide content areas.

## Corner radius

| Element | Radius |
| --- | --- |
| action slips and fields | 2px |
| product media and feature scene | 8px |
| opening and split panels | 22px |
| footer paper | 7px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default page reading surface.

**CSS:** `background: #fff9f2; color: #522c25`

**Observed:** Flat warm paper with single-pixel seams between chapters.

**Transfer:** Use the same warm base behind text and ruled grids.

#### Oatmeal media well · level 0

**Use:** Backing for isolated product pictures and illustrations.

**CSS:** `background: #f6ede3; border-radius: 8px; box-shadow: none`

**Observed:** Subtle contrast against the cream page; the object remains the focal point.

**Transfer:** Center a tangible object or simple drawn representation with generous internal breathing room.

#### Blue split frame · level 0

**Use:** Large human invitation chapter.

**CSS:** `background: #89b4ca; padding: 15px`

**Observed:** Blue is only a narrow surrounding frame and central seam, not the text field.

**Transfer:** Pair one warm process image with one Cream canvas panel.

#### Rust closing frame · level 0

**Use:** Footer and social picture strip.

**CSS:** `background: #c03001; padding: 15px 15px 0px`

**Observed:** The large pale footer interior leaves a red rim; the subsequent social strip stays red.

**Transfer:** Make the ending feel like a printed community noticeboard rather than a dark corporate sitemap.

## Components

### Navigation bar

**Use:** Main browsing controls beneath the opening scene.

**CSS:** `display: flex; align-items: center; height: 69px; padding: 0px 36px; background: #fff9f2; border-bottom: 1px solid #e6dad4`

**Text style:** `navigation` — Necto Mono 400 · 14px/1.1 · tracking 0.05em · uppercase

**Observed:** Small outlined identity at left; grouped links, search and account/cart controls separated into cells by vertical rules. Link hit areas use 12px padding. Interior photographic openings place this bar over the image instead.

**States:** Declared: hover opacity 0.7 on navigation links; focus-visible outline .2rem solid rgba(82, 44, 37,.5), outline-offset -0.2rem and box-shadow 0 0 .2rem rgba(82, 44, 37,.3).

**Transfer:** Keep the segmented utility-bar feel even when the new product has fewer destinations.

### Announcement strip

**Use:** A single useful operational promise between image and navigation.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 32px; background: #89b4ca; color: #522c25`

**Text style:** `label` — Necto Mono 400 · 12px/1.1 · tracking 0.05em · uppercase

**Observed:** One centered line, not a large promotional banner.

### Action slip

**Use:** Default contact or conversion link.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; height: 20px; padding: 3px 6px; border-radius: 2px; background: #522c25; color: #fff9f2`

**Text style:** `action` — Necto Mono 400 · 13.6px/0.85 · tracking 0.05em · uppercase

**Observed:** Label-sized rectangle. Pale oatmeal is the inverse variant on photography; small repeated actions alternate blue, rust, ochre and apricot, with cream lettering on rust/ochre and brown on blue/apricot.

**States:** Declared: hover on colored quick-view ancestors inverts background and lettering, with opacity 1; focus-visible outline .2rem solid rgba(82, 44, 37,.5), outline-offset 0.3rem and box-shadow 0 0 .2rem rgba(82, 44, 37,.3).

**Transfer:** Keep the slip-sized visible treatment; choose verbs specific to the next step.

### Product card

**Use:** Merchandise or a purchasable offering.

**CSS:** `padding: 36px; background: #fff9f2`

**Text style:** `product-title` — Little Amps 500 · 20px/1 · tracking -0.1em

**Observed:** Oatmeal media well first, then title and small mono price, uppercase metadata, compact descriptive details and an Action slip. At desktop a 360px cell contains 288×374px media. Pale rules define the larger grid, not a shadow around each card.

**Transfer:** Retain the image-to-name-to-factual-detail-to-action order; replace tasting details with concise attributes appropriate to the product.

### Slider control

**Use:** Manual browsing of image features and horizontal card rails.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 34px; height: 28px; background: #fff9f2; color: #522c25; border-radius: 2px 0px 0px 2px`

**Observed:** Two adjoining previous/next rectangles; next reverses the corner treatment. Fine 8×14px arrow strokes; optional mono current/total counter sits to their left. Oatmeal variant appears on plain-page rails.

**States:** Declared: focus-visible outline .2rem solid rgba(246, 237, 227,.5), outline-offset 0.3rem and box-shadow 0 0 .2rem rgba(246, 237, 227,.3).

### Editorial card

**Use:** A rail of people, process notes or recent stories.

**CSS:** `display: flex; flex-direction: column; padding: 36px; background: #fff9f2`

**Text style:** `excerpt` — Inclusive Sans 400 · 13px/1.1

**Observed:** Portrait-like 271×325px photo, a date, small expressive serif title, clipped short excerpt and colored Action slip. Content rail continues beyond the right edge; controls sit beside the chapter heading.

**Transfer:** Use real people and details, not generic category icons.

### Footer paper

**Use:** Shared closing information panel.

**CSS:** `display: grid; grid-template-columns: 1.5fr 1fr 1fr 1fr; background: #f6ede3; border-radius: 7px; margin: 15px 15px 0px`

**Text style:** `footer-heading` — Necto Mono 400 · 16px/1 · tracking 0.05em · uppercase

**Observed:** A large stacked identity and lower contact block occupy the left third. Two small link groups sit in the center; an embedded playlist occupies the right. Interior padding is 30px; secondary links are 60% brown. A red social strip and brown legal strip follow.

**Transfer:** Keep a meaningful cultural or community module at right; when audio is inappropriate use a similarly sized editorial or maker feature, not a generic newsletter box.

### Inquiry field

**Only for:** business inquiry pages

**Use:** Long-form contact collection.

**CSS:** `height: 45px; padding: 12px 16px; border: 1px solid rgba(82, 44, 37, 0.25); border-radius: 2px`

**Text style:** `small-body` — Inclusive Sans 400 · 14px/1.1

**Observed:** Visible label above each full-width field; six single-line fields followed by a taller message field and full-width Action slip. Form occupies the left half beside a tall process portrait.

**Transfer:** Ask only the operational questions needed to start a human conversation.

## Imagery and graphics

### Analog ritual photography

**Use:** Opening scene, feature image and full-width offer chapter.

**Observed:** Warm wood, vinyl, hands, practical machinery, tattoos, brick and real interiors. The opening is a close-up of a hand at a turntable; process scenes allow deep brown-black shadows and naturally vivid orange equipment. Media occupies most of the frame; text sits on an uncluttered or dark patch rather than a white overlay box.

**Transfer:** Photograph a tactile ritual of making or using the new product in a real environment, with warm directional light and a clear hand/tool interaction. A single carefully lit still is the minimum replacement for film.

### Isolated merchandise

**Use:** Product cells and small offer cards.

**Observed:** Straight-on centered bags, caps and vessels on flat oatmeal backing, without decorative pedestals or dramatic floating shadows. Graphic packaging supplies most of the saturated detail.

**Transfer:** Show one object at consistent scale on the Oatmeal media well; if intangible, use a simple flat illustration of its output rather than a glossy device mockup.

### Hand-drawn companions

**Use:** Section heading accents, offer cards and social-strip invitation.

**Observed:** Whimsical brown line drawings: a walking mug, a swan, a bicyclist and stacked amplifiers. Small heading doodles interrupt the rectilinear grid; a larger object pile anchors the lower-right of the contact panel.

**Transfer:** Create an original character or object cluster from the new product's tools. Minimum version: one imperfect outlined tool with expressive motion marks, repeated in a different pose near the ending.

**Build:** Draw SVG paths with no fill or cream fill, rounded brown strokes around 2px, irregular contours and sparse hatch marks. Combine one recognizable object with 2–4 short radiating strokes or limbs; keep heading companions around 100px wide and the larger panel drawing around 200px wide. Do not add glossy shading.

### Community filmstrip

**Use:** The final social band.

**Observed:** A continuous row of 91×91px candid square photos with 14px gaps over rust red; a cream outlined character and speech bubble introduce it. Storefronts, people, objects, events and workspaces mix freely.

**Transfer:** Use small genuine behind-the-scenes images from the new organization, or process details if no social library exists.

**Build:** Use a horizontal nonwrapping flex row with 14px gap and 91px square object-fit-cover images; place a cream line-art character and speech-bubble invitation before the row. Clip overflow at the page edge over the rust surface.

### Illustrated benefits

**Only for:** business-service pages

**Use:** Four parallel benefits under an introductory heading.

**Observed:** Brown outlined editorial drawings on oatmeal wells, with restrained dusty pink, faded blue, apricot and olive fills. Scenes show hands, tools and friendly gestures; each image is about 253×211px within a 283×241px well.

**Transfer:** Use one simple human gesture per benefit, consistent line weight and no 3D rendering.

**Build:** Compose square SVG scenes using brown 2px outlines, cream negative space and one muted flat color per scene. Use hands and a central symbolic tool, with broad wavy background rays rather than gradients.

### Icons

**Observed:** Tiny utilitarian arrow marks: 10×7px dropdown chevrons with 1.5px strokes and 8×14px slider arrows with 1px strokes. Social marks are solid brown at about 20px, separate from the playful illustrations.

**Transfer:** Keep interface icons small, single-color and functional; let custom doodles carry personality instead of oversized icon badges.

## Section recipes

How recurring sections are built.

### First screen: Ritual film opening

**Observed:** The first 750px is an apricot-backed stage, inset 15px on all sides. A 1410×720px object-fit-cover video fills a clipped 22px-radius rectangle. Above the image sits a two-line serif identity graphic, 400×161px, aligned upper left with 40px internal padding; warm pale lettering and a small line-drawn object read as one lockup. The close-up human action dominates the center and right. There is no separate sales paragraph or conversion button in this stage. Within the first 900px, the whole scene, 32px Announcement strip and 69px Navigation bar are visible; only the beginning of the editorial introduction reaches the lower edge. The detailed statement and merchandise begin below the fold.

**Transfer:** Default new marketing openings should lead with an atmospheric ritual image or film and a similarly compact stacked identity or promise lockup. Without film, use a high-quality warm process still. Story and business-service pages instead open with an edge-to-edge 868px photo beneath the announcement, overlaid navigation and a live interior-hero headline; supporting copy is a narrow left column, top-aligned for narrative or low-aligned for conversion.

**Avoid:** Do not replace this first impression with a centered SaaS headline, two giant buttons and a floating product render. Do not place an ordinary navigation bar above the default photographic stage.

**Text style:** `feature-display` — Little Amps 500 · 51px/0.8 · tracking -0.1em

### Colored editorial statement

**Observed:** A Cream canvas chapter uses 48px vertical and 36px horizontal padding, a roughly 860px-wide statement and a small line-art companion toward the opposite edge. Individual phrases are rust, blue or ochre within the same serif sentence; a single Paper seam closes the block.

**Transfer:** Write a compact point of view, emphasizing a few concrete phrases rather than decorating every word.

**Text style:** `statement` — Little Amps 500 · 41px/1 · tracking -0.1em

### Photo feature inside a merchandise grid

**Observed:** The four-column Merchandise grid begins with a three-column 1008×599px photograph and one Product card beside it. The feature has 8px corners, 36px interior spacing, a cream feature-display headline at top left, Action slip at bottom left and Slider control with counter at bottom right. More Product cards continue on the next row.

**Transfer:** Pair an experiential promise with a small set of objects or offering variants; preserve the oversized image-to-small-card contrast.

**Text style:** `feature-display` — Little Amps 500 · 51px/0.8 · tracking -0.1em

### Immersive offer chapter

**Observed:** A full-width process image about 943px tall carries a cream label, a roughly 50px serif headline and a short 16px body column at upper left. Two pale offer cards sit below the introduction over the same photograph, with an inverse Action slip beneath.

**Transfer:** Use the image as one coherent environment; set a small family of recurring offers against it without dividing the photograph into tiles.

### Blue human invitation

**Observed:** Blue split frame surrounds a left process portrait and right Cream canvas panel, both with 22px corners. Each half is about 698×720px. The text panel has 37.5px padding, a small eyebrow, a two-line heading with a colored phrase, and a short 450px-wide body block. The tiny Action slip is held at the lower left, with Hand-drawn companions at the lower right and abundant unfilled paper between.

**Transfer:** Use this device for a partnership, assisted purchase or contact invitation; keep the human photo and the unusually spacious text card together.

**Text style:** `heading` — Little Amps 500 · 44.8px/1 · tracking -0.1em

### Ruled story rail

**Observed:** A two-part 44.8px serif heading combines an ochre introductory phrase and brown main line. Slider controls align right; Editorial cards follow in ruled cells, with the next card partially visible at the edge.

**Transfer:** Show useful process stories, recent work or people as a browsable rail rather than a packed news dashboard.

**Text style:** `heading` — Little Amps 500 · 44.8px/1 · tracking -0.1em

### Cultural closing

**Observed:** Rust closing frame holds Footer paper: large brown stacked identity left, contact details below, small central link groups and a playlist at right. Community filmstrip follows directly on red, then a 33px brown legal strip with tiny uppercase cream text. The same ending serves all page types.

**Transfer:** Retain a warm identity, useful contact routes, a culturally specific editorial module and a candid image strip. The ending should feel like a place with people, not just a conversion funnel.

### Practical directory

**Only for:** directories

**Observed:** A heading and short introduction sit above small uppercase radio filters. Each region has a narrow left label rail and four listing columns to the right. Thin 15%-brown borders form a continuous table-like grid. Each listing has a roughly 250×197px photograph, a directory-title, muted address and alternating colored Action slip.

**Transfer:** Use for locations, partners or compatible providers. Preserve the label rail and orderly image-first listings; leave short final rows naturally short rather than inventing filler.

**Text style:** `directory-title` — Little Amps 500 · 18px/1 · tracking -0.1em

### Location chapter

**Only for:** physical-location pages

**Observed:** A ruled row places practical information in the left third and a 912×428px image slider in the right two thirds. Underlined 44.8px colored serif names precede address, uppercase mono hours, a lower descriptive paragraph and compact filled/outline map and menu actions.

**Transfer:** Separate operational facts from the descriptive paragraph and let real place photography provide proof.

**Text style:** `heading` — Little Amps 500 · 44.8px/1 · tracking -0.1em

## Page flow

**Storyline:** atmosphere → point of view → tangible offerings or capabilities → human invitation → useful community proof → cultural closing

### A broad product-and-brand landing page

1. **Atmosphere** — Framed ritual film and stacked identity before practical navigation.
2. **Positioning** — Colored serif statement with a playful drawing.
3. **Product demonstration** — Large lifestyle feature joined to ruled merchandise cells.
4. **Recurring offer** — Immersive process photograph with two offer cards.
5. **Assisted conversion** — Blue human invitation with process portrait and small contact action.
6. **Deeper engagement** — Additional merchandise and an editorial people-and-process rail.
7. **Closing** — Pale footer in a red frame, cultural module, community filmstrip and legal strip.

**Transfer:** Alternate immersive scenes with factual object grids, then end with genuine people and culture; choose only the narrative beats the new offering needs.

### A business-service conversion and discovery page

1. **Promise** — Full-height working portrait with a low-left headline, concise benefits and directory jump link.
2. **Capabilities** — Introductory heading and four illustrated benefit columns.
3. **Conversion** — Long labeled inquiry form beside a tall maker portrait.
4. **Practical proof** — Filterable, region-labeled directory with photographs and tiny map actions.
5. **Closing** — Shared cultural footer and social filmstrip.

**Transfer:** Make professional credibility feel personal through real work photography, tangible benefits and an approachable form; use a directory only when discovery is a real user need.

### A narrative, places and contact page

1. **Origin** — Live serif heading and short story over a dark candid performance photograph.
2. **Practical orientation** — Brief illustrated section introduction followed by two large location rows.
3. **Human invitation** — Blue split-panel contact chapter with direct email routes.
4. **Closing** — Shared cultural footer and social filmstrip.

**Transfer:** Move from an origin story to concrete ways to visit or connect; use equivalent practical chapters when the new organization has no physical locations.

## Writing

Conversational, enthusiastic and rooted in real craft. Expertise sounds like an experienced friend offering help, with musical turns of phrase and a little irreverence rather than luxury mystique.

**Do not copy:** Do not reuse the brand name, wordmark, amplifier and mascot artwork, product names, addresses, email addresses, historical dates, years-of-experience claims, prices, shipping thresholds, source stories or playlist titles as new-product content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the makers; speak directly to you and your place or business. Invitations sound like a person starting a conversation.
- **Rhythm:** Short punchy headings, often 3–7 words or a paired question; compact supporting paragraphs supply the practical details. Exclamation marks and occasional emphatic capitals are part of the warmth, not a requirement on every sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Feature headline | Pair a sensory benefit with a relaxed emotional payoff. | 4–7 words | “Tasty Coffee and Chill Vibes.”<br>“Amp Up Your Mornings” |
| Invitation heading | Ask a plain-language question that helps the reader recognize their need. | 4–10 words | “Got a Coffee Shop?”<br>“Need Coffee in Bulk?” |
| Supporting line | Make the next step feel human and easy, then add a concrete operational benefit. | 1–3 short sentences | “Drop us a line below to start the conversation. We’re pumped to connect and bring [Brand]’ coffee vibes to your business!” |
| Action | Use a direct everyday verb with a short object. | 2–3 words | “Get in touch”<br>“Shop All”<br>“Go to Map” |
| Editorial heading | Frame useful stories as things happening in a shared world. | 4–8 words | “What's Happening in Our World” |

**Words and phrasing to use:** friends; chill; tasty; hit us up; drop us a line; pumped; super; our community

**Avoid:** revolutionary ecosystem; unparalleled excellence; disruptive solution; exclusive luxury; synergize

**Rules:**

- Use informal enthusiasm alongside verifiable specifics, not in place of them.
- Let headings carry the playful phrase while the support explains what is actually offered.
- Use the new product's own cultural vocabulary instead of forcing coffee or music metaphors into unrelated claims.
- Keep metadata factual and terse; keep invitations warm.

## Do's and Don'ts

### Do

- Keep core headings at 44.8px/1, weight 500 and -0.1em tracking.
- Give the default opening a 15px apricot frame and 22px clipped corners.
- Use 36px side padding for reading chapters and ruled product cells.
- Make visible action slips 20px high with 2px corners and uppercase spaced mono.
- Alternate warm full-scene photography with oatmeal-backed isolated objects.
- Preserve the blue-framed photo-and-paper invitation with its lower-left action.
- Finish with a red frame, a pale information panel and 91px community thumbnails.
- Use thin warm rules and flat surfaces rather than shadows.

### Don't

- Do not substitute black-on-pure-white for brown-on-cream throughout.
- Do not turn the 2px action rectangles into rounded 48px pill buttons.
- Do not apply -0.1em tracking to body sans or monospace text.
- Do not cover every chapter in saturated color; protect the cream reading fields.
- Do not add floating drop shadows, glass cards or glossy 3D stages to flat media wells.
- Do not force isolated merchandise to fill its entire image well; leave the pale backing visible.
- Do not make interface arrows as expressive or oversized as the hand-drawn companions.
- Do not reduce the closing to a sparse copyright line; its cultural module and community band carry the final impression.

## Motion and responsive

### Motion

**Observed:**

- Product title links declare all .25s linear and hover opacity 0.7.
- Product media declare transform .5s ease, opacity .5s ease.
- Slider controls, manual image counters and horizontal card rails are present; the opening uses video.

**Transfer:**

- Use a restrained media transition and lightweight opacity response so the tiny printed-slip actions retain their crispness.
- Preserve manual browsing controls when adapting image scenes and editorial rails.

**Unknown:**

- Autoplay behavior, video loop timing and scroll-trigger choreography are not established.

### Responsive

**Observed:**

- Desktop compositions use four merchandise columns, two-panel invitation scenes and image-first listing grids.
- Styles include width breakpoints at 575/576px, 749/750px and 989/990px among others.

**Transfer:**

- On narrow screens, keep the photographic ritual and identity lockup dominant, reduce text line lengths, and preserve a visible colored frame.
- Stack the split scene photo above its paper invitation; keep the small action near the end of the paper panel.
- Turn multi-column rails into browsable narrow-screen sequences rather than shrinking 20px action slips further.

**Unknown:**

- Exact mobile navigation, stacking breakpoints and mobile typography are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
