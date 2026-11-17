# KÖPPEN — material rituals on cream

## Overview

A light, materially rich style that makes everyday products feel like considered objects. Cream and pale stone support charcoal text, tiny green signals, a flared serif for emotional statements and a compact grotesk for practical information. Cinematic still lifes, isolated material studies and intimate portraits carry the scale, while the text remains unusually small and the editorial layouts spacious. It suits premium physical products, personal rituals and systems whose construction deserves close attention.

### Essentials

- A cinematic object stage rather than a typographic billboard: a full-width 900px opening with reflective product photography, a left-aligned white 60px/62px flared-serif promise and a 280px support line beside a small action.
- Small controls stay deliberately rectilinear: 28px pale buttons with 12px horizontal padding, 24px black purchase strips with 8px padding, 12px/16px labels and 0px corners.
- Cream is the connective tissue: #fffcf3 surrounds editorial content, #f0efe5 backs catalog objects, and #dbefd4 is confined to 24px badges, narrow notices and hover fills. Strong color belongs primarily inside photography, not section backgrounds.
- A specimen-sheet rhythm makes products feel collectible: 8px outer gutters and an 8px-gap 24-column editorial grid coexist with four-column catalog rows separated by only 2px; text columns stay around 290px–350px while images take the remaining space.
- Material studies must carry the story: use unevenly sized 4:5 photographs with lettered callouts, thumbnail inventories and luminous grey-green studio backings. If there is no physical object, photograph or render a meaningful material, tool or physical manifestation of the product instead.
- The closing area is still a shop, not a slogan wall: a four-item object lineup has thin black price/action strips, then small customer-care links and a two-field newsletter form on the same cream canvas. A separate portrait-led proof panel uses 14px numbers above 10px uppercase captions instead of oversized statistics.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fresh pale green | `#dbefd4` | `--color-fresh` | surface, accent, action | Small merchandising badges, narrow announcement strip and button hover fill; never a dominant page field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#141313` | `--color-ink` | text, action, border | Main type, purchase-strip backgrounds and selected outlines. |
| Secondary grey | `#707070` | `--color-muted` | text, link | Secondary navigation, metadata, legal links and inactive explanatory copy. |
| Inactive index | `#a0a0a0` | `--color-inactive` | text | Unselected entries in the large specimen index and previous prices. |
| Fine grey rule | `#d9d7d7` | `--color-rule` | border | Section separators, row rules and field bottom edges. |
| Catalog wash | `#f0efe5` | `--color-catalog` | surface | Visible appearance of #eaeadf at 69.8% opacity over cream, used behind isolated catalog objects. |
| Pale control | `#f1f1e9` | `--color-control` | surface, action | Light buttons and newsletter fields. |
| Cream glass | `#f2f2ea` | `--color-glass` | surface | Visible appearance of #f1f1e9 at 95% opacity over cream; floating navigation and contextual commerce panels. |
| Warm cream | `#fffcf3` | `--color-canvas` | background, text | Continuous page canvas; warm reversed text on immersive product scenes. |
| Photo white | `#ffffff` | `--color-white` | text | Reversed headlines and supporting text over photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product detail galleries | Gallery stone | `#eaeadf` | `--color-stone` | surface | Solid product gallery and thumbnail backing. |
| product detail sections | Soft neutral | `#f5f5f1` | `--color-neutral` | surface | Demonstration media backing and hover variant for translucent set tabs. |

## Typography

- **Alliance No.1** — Body, controls, catalog labels, index and utility headings. Compact contemporary grotesk, mostly regular with medium emphasis and a dense practical cadence. If unavailable, use **Manrope**. Use 400 and 500; preserve compact line heights and the measured tracking. Font stack: "Alliance No.1", "Manrope", Arial, sans-serif.
- **ABC Arizona Flare** — Emotional hero promise, editorial lead and press quotation. Soft flared serif with a human, slightly sculptural shape; regular rather than high-contrast fashion styling. If unavailable, use **Lora**. Use 400 and 500 with -0.02em tracking; the flared original is not an exact match. Font stack: "ABC Arizona Flare", "Lora", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ABC Arizona Flare | 400 | 60px | 62px | -0.02em | White hero promise over the cinematic opening. |
| index | Alliance No.1 | 500 | 40px | 1 | -0.02em | Stacked interactive specimen names; selected ink and inactive grey. |
| editorial-lead | ABC Arizona Flare | 500 | 30px | 1.067 | -0.02em | Cream-canvas introductory statement beside a large still life. |
| quote | ABC Arizona Flare | 400 | 30px | 1.067 | -0.02em | Press quotation reversed over macro material video. |
| heading | Alliance No.1 | 500 | 20px | 1.2 | -0.015em | Utility section headings and benefit titles; also the restrained title on product-detail pages. |
| body | Alliance No.1 | 400 | 14px | 1.18 | 0.005em | Paragraphs, benefit descriptions, lettered lists and small proof numbers. |
| item-title | Alliance No.1 | 500 | 14px | 1.18 | 0.005em | Catalog names, set names and step labels. |
| eyebrow | Alliance No.1 | 500 | 12px | 1.333 | 0.02em | Section labels, category names and small section headings; usually title case rather than uppercase. |
| caption | Alliance No.1 | 400 | 12px | 1.333 | 0.02em | Actions, prices, ratings, navigation and secondary text. Underline only explicit inline links. |
| micro | Alliance No.1 | 400 | 10px | 1.2 | 0.02em, uppercase | Index captions, pagination and statistic qualifiers. |

**Notes:**

- Display and editorial serif share -0.02em tracking despite different sizes; body has slightly positive tracking and no exaggerated leading.
- The 40px grotesk is an interactive index role, not the default heading for every section. Most practical headings are only 20px.
- Keep small type and large media in tension. A 14px paragraph can sit beside an image 947px wide without enlarging the copy to fill space.
- No fluid type formula is prescribed; preserve these desktop recipes and adapt line wrapping deliberately.

## Layout

**Density:** Airy editorial composition with very compact text, controls and catalog gutters; large empty regions separate dense small information.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Catalog column gaps and seams between navigation panels. |
| 4px | Eyebrow-to-title gap and tight catalog text spacing. |
| 8px | Outer editorial gutters, main editorial grid gap, card text inset and ordinary stack spacing. |
| 12px | Light-button and input horizontal padding. |
| 16px | Heading-to-body separation, paragraph group spacing and hero support/action gap. |
| 24px | Larger local stacks, newsletter spacing and section-edge inset for the centered portrait. |
| 40px | Catalog section bottom clearance and medium editorial stacks. |
| 80px | Education-section bottom clearance and FAQ lead-in. |
| 120px | Closing product-lineup breathing room. |
| 200px | Long editorial lead-ins and large separation after detail galleries. |

### Containers and grids

- **Editorial grid**: 24 columns · gap 8px · side padding 8px. Full-width desktop grid. A six-column text lead sits against a sixteen-column image; other modules reserve eight columns for an inventory and distribute irregular image widths across the remainder.
- **Catalog grid**: 4 columns · gap 2px · side padding 2px. Four equal 358px-wide cards at a 1440px viewport; imagery is backed independently from text.
- **Reading column**: max width 290px. Long technical and narrative paragraphs; wider 350px leads accommodate the serif heading.
- **Floating control cluster**: max width 444px · gap 2px · side padding 8px. Two equal navigation panels fixed at the upper left, separate from the full-width page composition.
- **Newsletter form**: max width 511px · 2 columns · gap 2px. Two adjacent fields in the right half of the footer.
- **Portrait proof**: max width 708px · side padding 24px. Centered 4:5 human portrait with cream margins and white text near its lower edge.

## Corner radius

| Element | Radius |
| --- | --- |
| Controls and media | 0px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Base for all text-led sections and the ending.

**CSS:** `background: #fffcf3`

#### Catalog backing · level 0

**Use:** Isolated object plates, including small inventory thumbnails.

**CSS:** `background: rgba(234, 234, 223, 0.698); border-radius: 0px`

**Observed:** A pale warm-grey rectangle with the object centered and ample breathing room; text sits outside the backing.

**Transfer:** Maintain an unbroken 4:5 plate around each isolated object.

#### Floating cream panel · level 1

**Use:** Navigation and image-overlaid contextual commerce controls.

**CSS:** `background: rgba(241, 241, 233, 0.95); backdrop-filter: blur(12px); border-radius: 0px`

**Observed:** Nearly opaque cream-green panels separated by narrow seams, not outlined cards.

**Transfer:** Use local translucency only where controls overlap imagery.

#### Ruled content · level 0

**Use:** Information rows, section boundaries and explanatory indexes.

**CSS:** `border-top: 1px solid #d9d7d7`

**Observed:** Fine rules separate content without raising it off the canvas.

**Transfer:** Divide technical information with hairlines rather than enclosing every group.

#### Gallery backing · level 0

**Only for:** product detail galleries

**Use:** Large product-detail image stage.

**CSS:** `background: #eaeadf; border-radius: 0px`

**Observed:** A broad right-hand image area balanced against a narrow purchase column.

**Transfer:** Give the object a calm solid backing before introducing dramatic macro imagery.

## Components

### Floating navigation

**Use:** Persistent compact navigation over both imagery and cream sections.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); gap: 2px; max-width: 444px; position: fixed; top: 8px; left: 8px`

**Text style:** `caption` — Alliance No.1 400 · 12px/1.333 · tracking 0.02em

**Observed:** Two cream-glass blocks: the left combines a small wordmark, account/cart utilities and vertically stacked links; the right is one centered shop destination. A narrow pale-green notice sits below the pair. Each panel has an 8px content inset.

**Transfer:** Use a small original identity and two or three useful destinations; retain the compact upper-left cluster rather than a conventional full-width masthead.

### Light button

**Use:** Default marketing action, including the hero and editorial modules.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 28px; padding: 0px 12px; background: #f1f1e9; color: #141313; border-radius: 0px`

**Text style:** `caption` — Alliance No.1 400 · 12px/1.333 · tracking 0.02em

**Observed:** A text-width pale rectangle. Set-purchase variants can include a muted struck-through price beside the current price.

**States:** Declared: hover background-color #dbefd4 and color #141313.

**Transfer:** Keep action labels brief enough that the control remains visually subordinate to the object.

### Purchase strip

**Use:** Direct purchase action attached to a product lineup or contextual commerce panel.

**CSS:** `display: flex; align-items: center; justify-content: space-between; height: 24px; padding: 0px 8px; background: #141313; color: #ffffff; border-radius: 0px`

**Text style:** `caption` — Alliance No.1 400 · 12px/1.333 · tracking 0.02em

**Observed:** Action left, prices right, spanning the item width. Product-detail primary purchase controls use a 32px-high variant with 12px horizontal padding.

**States:** Declared: hover background-color #dbefd4 and color #141313.

### Secondary link

**Use:** Navigation and compact footer destinations.

**CSS:** `color: #141313; background: transparent`

**Text style:** `caption` — Alliance No.1 400 · 12px/1.333 · tracking 0.02em

**Observed:** Plain text without a box. Footer destinations are stacked with 4px gaps; subdued inline detail links use secondary grey.

**States:** Declared: hover color #707070.

### Catalog card

**Use:** Best-seller, catalog and related-object grids.

**CSS:** `display: flex; flex-direction: column; gap: 4px; border-radius: 0px`

**Text style:** `item-title` — Alliance No.1 500 · 14px/1.18 · tracking 0.005em

**Observed:** A 4:5 Catalog backing precedes category, medium product name, one benefit line and star/rating metadata. Text is inset 8px. At desktop a plate is 358px by 447px inside a card about 536px high. Badges occupy the plate’s upper-left corner.

**Transfer:** Keep the product identifiable at modest scale, and give each card one concrete benefit rather than a paragraph.

### Fresh badge

**Use:** Small merchandising flags and narrow announcements.

**CSS:** `display: flex; align-items: center; height: 24px; padding: 0px 8px; background: #dbefd4; color: #141313; border-radius: 0px`

**Text style:** `caption` — Alliance No.1 400 · 12px/1.333 · tracking 0.02em

**Observed:** Text-width labels sit 4px inside an image plate. The announcement variant spans the navigation cluster and includes a small dismiss icon.

### Specimen index

**Use:** Interactive list connecting material or feature names to one image and explanation.

**CSS:** `display: flex; flex-direction: column; gap: 0px`

**Text style:** `index` — Alliance No.1 500 · 40px/1 · tracking -0.02em

**Observed:** Large closely stacked names sit left. One entry is ink while the others are inactive grey. A portrait object study and short body explanation sit at the far right, leaving an expansive empty center.

**Transfer:** Use concrete materials, technologies or capabilities as the entries; keep one selected at a time.

### Newsletter input

**Use:** Footer signup fields.

**CSS:** `height: 32px; padding: 0px 12px; background: #f1f1e9; border-bottom: 1px solid #d9d7d7; border-radius: 0px`

**Text style:** `caption` — Alliance No.1 400 · 12px/1.333 · tracking 0.02em

**Observed:** Email and phone fields are adjacent in a two-column form. A short incentive sits above; tiny grey consent text and a Light button sit below.

### Question row

**Only for:** product detail objection handling

**Use:** Compact question-and-answer accordion.

**CSS:** `display: flex; align-items: flex-start; justify-content: space-between; padding: 16px 0px; text-align: left; color: #141313`

**Text style:** `body` — Alliance No.1 400 · 14px/1.18 · tracking 0.005em

**Observed:** Rows are around 410px wide with a small plus/minus control at the right. Fine grey rules separate subsequent rows; answers use the same small body recipe.

## Imagery and graphics

### Reflective studio stage

**Use:** Opening and immersive product interludes; a signature visual device.

**Observed:** Amber and clear glass, dark green packaging, copper, silver metal and pale stone are staged on reflective glass against a grey-green studio atmosphere. A bright center falls to darker edges; the objects cluster across the center and lower half, with believable liquid, fine texture and reflections. The opening includes a thin horizontal glass shelf.

**Transfer:** Use original product photography or a realistic render with controlled soft light, one reflective plane and a restrained material palette. Minimum acceptable version: a carefully lit object photograph on a cool grey seamless with a real contact shadow, never a generic abstract blob.

**Build:** For a low-cost stage, place an isolated object image above a horizontal plane occupying the lower 22% of the frame. Back it with layered elliptical radial gradients using rgba(241,241,233,0.85) at the center and rgba(20,19,19,0.85) at the edges. Duplicate the object below the plane, flip vertically, lower opacity to 0.18 and mask to transparent within 180px. Add two 1px low-opacity horizontal rules to suggest the glass shelf. These are staging guidance; favor photographic reflections when available.

### Lettered material atlas

**Use:** Editorial feature chapters and component inventories.

**Observed:** Unequal rectangular images float across cream: a large suspended tool, a much smaller stone study, a close-up pour and a texture detail. Neutral-to-dark grey-green gradients back copper and metallic objects; liquids can be luminous yellow-green. Small letter labels sit just outside image corners, matching an alphabetic list in the left inventory.

**Transfer:** Show the whole object, its material and one physical action at different scales. Preserve unequal widths and generous intervening space rather than making a uniform tile grid.

**Build:** Use the 24-column grid with a left eight-column inventory. Distribute three or four 4:5 image plates through the other sixteen columns at unequal widths, align their top edges selectively and stack one detail underneath another. Position 14px alphabetic labels outside each plate’s upper-left edge and repeat those letters in the inventory.

### Catalog object plates

**Use:** Repeated browsing grids and the closing lineup.

**Observed:** Front or slightly three-quarter views of freestanding objects and coordinated sets, softly lit and isolated on warm pale-grey fields. Objects are centered, do not touch the frame and have modest contact shadows. Closing lineup objects appear directly on cream rather than on colored cards.

**Transfer:** Keep camera height and lighting coherent across products; use transparent cutouts or a matching seamless backing, not inconsistent lifestyle thumbnails.

### Material specimens

**Use:** Index and technical education.

**Observed:** White porous mineral clusters and translucent pale cubes appear as sculptural specimens centered in 4:5 pale plates. Their texture provides interest without diagrams or intense color.

**Transfer:** Make a credible, close material study of the new product’s constituent or mechanism. If there is no literal ingredient, use a physical test piece or tool instead of inventing a scientific-looking molecular graphic.

### Human ritual portraits

**Use:** Emotional proof and editorial contrast to object studies.

**Observed:** Close, candid smiling faces fill tall 4:5 frames with natural skin texture. One portrait is dark and cool with white text near its bottom; another is warm sunlit orange against a cool background. The portrait-led proof panel is centered and only half the desktop width.

**Transfer:** Choose real use or a human consequence with intimate framing; retain directional light and tangible skin rather than polished stock wellness poses.

### Workshop timeline

**Only for:** company-history storytelling

**Use:** Development history and process credibility.

**Observed:** A large portrait workshop video is paired with a low row of small chronological thumbnails. Informal hands, prototypes and production details contrast with polished product still lifes. Small year labels, an italic micro-caption and a thin progress rule anchor the arrangement.

**Transfer:** Use genuine making-of imagery with dates and short process descriptions; keep informal media local to this narrative variant.

### Icons

**Observed:** Utility icons are mainly 16px, with 1px butt-ended strokes in charcoal or secondary grey. Stars are small solid marks; plus/minus and benefit indicators are about 13px. Account and cart utilities stay beside the compact identity.

**Transfer:** Choose a restrained thin-stroke set, avoid colored icon circles, and reserve filled forms for small stars or simple utility silhouettes.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise opening

**Observed:** A full-bleed 1440px by 900px Reflective studio stage fills the first screen. The layered order is studio backdrop and glass plane, product assembly, readable white promise and support/action row, then Floating navigation at the upper left. Objects occupy the middle and lower frame, roughly half its width, extending down into reflections. The 60px/62px flared-serif headline runs left from the 8px gutter across about half the screen at mid-height. Beneath it, a 280px-wide support line sits beside a Light button with a 16px gap. The entire promise, supporting line, action, object group and reflections are visible inside the first 900px; the catalog begins below the fold.

**Transfer:** Create a similarly weighted original object assembly, or a meaningful physical manifestation of a nonphysical product, leaving readable space on the left. Detail pages instead open with a 444px purchase column and a broad right-hand gallery, using the 20px heading. Editorial company pages open on cream with a 30px serif introduction opposite a large square still life. Catalog pages use a small 12px heading and immediate product grid after a spacious lead-in.

**Avoid:** Do not replace the atmospheric assembly with a centered giant headline, a rounded image card or an oversized hero button; the main visual is the object stage, not the CTA.

**Text style:** `display` — ABC Arizona Flare 400 · 60px/62px · tracking -0.02em

### Small heading and expansive image

**Observed:** An eyebrow sits 4px above an editorial lead, followed by body text at 16px separation and a Light button. A 350px lead occupies roughly one quarter of the desktop composition; a 947px-square top-down product arrangement fills the right two thirds. Cream and 8px gutters tie both halves together.

**Transfer:** Explain the product’s organizing idea in a small anchored column and let one carefully composed image carry its breadth.

**Text style:** `editorial-lead` — ABC Arizona Flare 500 · 30px/1.067 · tracking -0.02em

### Lettered product chapter

**Observed:** A sticky left inventory combines a 2px-gap strip of 85px by 106px thumbnails, an item title, one benefit, a lettered list and a Light button. Lettered material atlas images of unequal widths span the right area; top lead-in can be 112px and the images end at different heights.

**Transfer:** Use this composition for a family of parts, a workflow or a small collection. Tie every detail plate to the inventory with a matching letter.

**Text style:** `body` — Alliance No.1 400 · 14px/1.18 · tracking 0.005em

### Specimen education

**Observed:** The Specimen index pairs 40px names on the left with a 469px by 587px specimen on the far right, an 8px-gap explanation and a Light button. A technical variant uses a 20px lead at left, ruled exclusion rows and two 350px by 438px specimen cards at right, with pagination low in the section.

**Transfer:** Give readers one clear material or mechanism at a time; use the two-card variant for deeper technical comparisons.

**Text style:** `index` — Alliance No.1 500 · 40px/1 · tracking -0.02em

### Immersive commerce interlude

**Observed:** A 900px full-width reflective product scene carries a small reversed heading at bottom left. At upper right a 444px Floating cream panel contains three 32px tabs, a compact set description, a thumbnail and a Purchase strip.

**Transfer:** Use an immersive scene to reconnect a technical story to a purchasable collection; keep the commerce panel compact rather than covering the object.

**Text style:** `heading` — Alliance No.1 500 · 20px/1.2 · tracking -0.015em

### Quiet quantified portrait

**Observed:** A centered 708px by 885px portrait sits within 24px vertical inset. Three small 14px statistics with 10px uppercase qualifiers run across its lower region, above a short white body paragraph and Light button. Numbers are not treated as display headlines.

**Transfer:** Use relevant substantiated frequency, longevity or impact measures, tied to a human consequence rather than a large dashboard.

**Text style:** `body` — Alliance No.1 400 · 14px/1.18 · tracking 0.005em

### Material-backed recognition

**Observed:** A full-width macro material video supports a 30px white serif quotation, 10px role caption and small fraction/Next pagination. Text hugs the lower portion of the frame rather than sitting in a separate testimonial card.

**Transfer:** Use a real expert statement or independent recognition with readable contrast and a materially relevant background.

**Text style:** `quote` — ABC Arizona Flare 400 · 30px/1.067 · tracking -0.02em

### Commerce-led ending

**Observed:** A four-item product lineup rests directly on cream with 2px seams and Purchase strips above the titles, benefits and ratings. Below it, the left half holds customer-care and social link stacks; the right half holds a 511px Newsletter form. A small seal, grey legal links, copyright and credits sit at the bottom. The whole ending remains cream, not a dark footer block.

**Transfer:** End with a concise selection of real offerings or bundles and practical follow-up destinations. Keep objects, purchase strips and the lightweight form as the signature closing construction.

**Text style:** `caption` — Alliance No.1 400 · 12px/1.333 · tracking 0.02em

### Detail proof and questions

**Only for:** product detail pages

**Observed:** Benefits pair a compact two-column text grid with a 708px by 885px video. Reviews use a narrow score/count summary beside a longer column of ruled small-text entries. Related items return to Catalog cards. The FAQ splits into a small heading/action lead, 410px Question rows and a 529px by 661px still life.

**Transfer:** Move from capabilities to substantiated experience and then concrete usage questions; preserve the small typographic scale throughout.

**Text style:** `heading` — Alliance No.1 500 · 20px/1.2 · tracking -0.015em

### Process and philosophy editorial

**Only for:** company-story pages

**Observed:** A Workshop timeline alternates a large portrait media plate and a bottom-aligned thumbnail strip. Later sections use a small 20px heading and 290px prose column beside a 589px portrait and a 350px material image; a final note pairs compact prose with a 589px founders portrait before the shared ending.

**Transfer:** Give provenance, philosophy and people separate image-led moments without turning them into a corporate values-card grid.

**Text style:** `heading` — Alliance No.1 500 · 20px/1.2 · tracking -0.015em

## Page flow

**Storyline:** Sensory promise → browsable objects → organizing idea → material and capability chapters → human or expert proof → practical purchase choices and follow-up.

### Broad brand and collection landing

1. **Promise** — Full-screen reflective product assembly with serif promise and compact action.
2. **Product discovery** — Four-object best-seller row, then a small editorial lead beside a broad arrangement.
3. **Capability chapters** — Lettered inventories and asymmetrical material-detail studies.
4. **Education** — Immersive human-scale product scene followed by a selectable specimen index.
5. **Independent and quantified proof** — Material-video quotation and centered portrait with small frequency statistics.
6. **Closing choice** — Four-object purchase lineup and cream utility/newsletter footer.

**Transfer:** Use this as the default marketing character; select and rearrange chapters to suit the new product rather than reproducing every block.

### Catalog browsing

1. **Orientation** — Small collection heading after a spacious cream lead-in; filters and sort occupy a compact upper-right panel.
2. **Product comparison** — Four-column isolated-object grid with categories, one-line benefits and ratings.
3. **Closing choice** — Shared object lineup, care links, social links and newsletter form.

**Transfer:** Keep this variant direct and commercially dense, without adding the cinematic opening required by the general landing-page look.

### Focused product-set conversion

1. **Purchase decision** — Restrained product title, compact introduction, rating, purchase bar and included-item details beside a large gallery.
2. **Capabilities** — Benefits beside demonstration video.
3. **Mechanism and education** — Material specimens, ruled information and a contextual portrait still life.
4. **Collection expansion** — Immersive scene with floating set selector and purchase strip.
5. **Social proof** — Small score summary and long ruled review column.
6. **Objection handling** — Related-product row then three-part FAQ layout.
7. **Closing choice** — Shared lineup and cream newsletter footer.

**Transfer:** Use when a product needs usage and material explanation before purchase, keeping technical copy subordinate to the imagery.

### Integrated system conversion

1. **Purchase decision** — Compact title and integrated-system description beside a large gallery, with included components below the purchase action.
2. **System benefits** — Three complementary benefits paired with a tall demonstration.
3. **Material credibility** — Two specimen cards plus a short material-integrity explanation.
4. **Framework explanation** — Small educational lead and tall image explain how the parts cooperate.
5. **Purchase reinforcement** — Immersive set selector, reviews and related offerings.
6. **Objection handling and close** — FAQ followed by the shared lineup and utility footer.

**Transfer:** Explain cooperation between parts without enlarging the heading scale or inventing a pricing-table aesthetic.

### Company and process editorial

1. **Positioning** — Small serif introduction beside a large square object arrangement.
2. **Organizing idea** — Ruled numbered explanation with a narrow supporting image.
3. **Credibility** — Material education and exclusions in a specimen-card layout.
4. **Origin** — Large workshop media with chronological thumbnail rail.
5. **Philosophy and people** — Warm human portrait, material detail and short personal note beside a formal portrait.
6. **Closing choice** — The same commercial lineup and cream footer used throughout.

**Transfer:** Keep this an editorial variant with authentic process media, not the default content checklist for a product page.

## Writing

Considered, explanatory and sensorial without becoming ornate. Practical benefits sit beside a broader systems perspective; technical claims are stated with mechanisms rather than shouted as transformation.

**Do not copy:** Do not reuse KÖPPEN names, logos, seal artwork, proprietary product names, quotations, discounts, ratings, frequency figures, clinical or environmental claims. Replace all such content with original, substantiated equivalents. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the everyday benefit, we for an intentional design decision, and the product name for technical explanations.
- **Rhythm:** Short title-case headings and verb-led actions interrupt longer explanatory paragraphs. Compact catalog benefits often use an ampersand; emotional statements use plain human language rather than exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Care-oriented benefit for the whole experience rather than one specification. | 4–7 words | “Care For Your Whole Mouth” |
| Supporting line | Name the product category, then contrast the broader benefit with the narrow conventional approach. | One short sentence | “An oral care system designed for your whole mouth, not just your teeth.” |
| Catalog benefit | Two practical outcomes or a benefit plus a formulation constraint. | 3–7 words | “Gently Whitens & Fluoride-Free”<br>“Oral pH Support & Alcohol-Free” |
| Educational heading | Name a meaningful phase or mechanism with ordinary language. | 3–7 words | “A Pre-Clean Ritual”<br>“Ingredient Integrity & Material Sustainability” |
| Action | A direct verb and object; purchase actions can carry price separately. | 1–3 words | “Create Routine”<br>“Learn More”<br>“Buy Set” |
| Human editorial line | A brief reflective sentence that connects function to lived experience. | One sentence | “The mouth is the first language we ever learn.” |

**Words and phrasing to use:** designed to; support; whole; system; ritual; material; balance; foundation; gentle; precision-engineered

**Avoid:** miracle; game-changing; crush it; biohack everything; revolutionary breakthrough; ALL CAPS sales pressure

**Rules:**

- Explain what an object does before listing its parts.
- For technical claims, connect material or mechanism to a specific outcome and qualify appropriately.
- Use short benefit descriptions in catalog cards and reserve explanatory paragraphs for editorial chapters.
- Let small labels orient the reader; avoid promotional headlines in every section.
- Keep actions functional rather than witty.

## Do's and Don'ts

### Do

- Keep default hero type at 60px/62px with -0.02em tracking and a modest 28px action.
- Use 8px outer editorial gutters and 2px seams in four-item shop rows.
- Pair 14px/16.5px body copy with images several times wider than the reading column.
- Use 1px #d9d7d7 rules to organize detailed information.
- Make specimen plates 4:5 and preserve space around isolated objects.
- Use #dbefd4 as small labels or interaction feedback, while cream remains the main canvas.
- Keep proof numbers at 14px with 10px uppercase qualifiers when they overlay a human portrait.
- Close with product objects, 24px black purchase strips and a compact two-field newsletter form.

### Don't

- Do not introduce pill controls or rounded media corners; the system uses 0px radii.
- Do not turn the cream ending into a black multi-column corporate footer.
- Do not make every heading 40px; that size belongs to the selectable specimen index.
- Do not use green as a full-section brand wash; it is a small merchandising and hover signal.
- Do not attach drop shadows to catalog cards or information panels; depth comes from photographed materials.
- Do not replace the irregular detail atlas with equal square feature tiles.
- Do not inflate portrait statistics into 100px dashboard numerals.
- Do not stretch long paragraphs across the full grid; keep them around 290px–350px wide.

## Motion and responsive

### Motion

**Observed:**

- Buttons and text links declare 0.1s color/background transitions with cubic-bezier(0, 0, .58, 1).
- Floating navigation panels declare 0.3s color transitions with cubic-bezier(.85, 0, 0, 1).
- Transform transitions of 0.3s cubic-bezier(.85, 0, 0, 1) are declared; some surfaces also declare opacity transitions. No page-level animation sequence is established.

**Transfer:**

- Let material video provide most of the expressive movement; keep control feedback brief and localized.
- Use the declared pale-green hover on light and dark purchase controls rather than scaling or lifting them.

**Unknown:**

- Exact slide sequencing, autoplay behavior and scroll choreography are not specified.
- Focus-visible and active appearance are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 500px, 640px, 700px, 768px, 1000px, 1024px, 1280px, 1536px and 2000px.
- Layout rules include column-reverse editorial stacks below desktop and horizontally flowing product rails in place of four fixed columns. Footer rules place newsletter content before link stacks on narrow layouts.

**Transfer:**

- On narrow screens, keep product imagery visually primary, then stack the small explanatory lead below; preserve letter-to-image associations in detail chapters.
- Turn the closing four-item lineup into a horizontal rail rather than shrinking all four purchase strips to unreadable widths.
- Keep the cream canvas, rectilinear controls and compact type relationships rather than introducing a separate mobile visual language.

**Unknown:**

- Actual mobile compositions and type sizes are not established; the breakpoint-specific stacking guidance is not a complete mobile specification.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
