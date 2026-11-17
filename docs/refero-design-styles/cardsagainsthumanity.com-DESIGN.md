# Cards Against Humanity — deadpan cardboard anarchy

## Overview

A blunt, funny, high-contrast style that feels like printed matter thrown into motion rather than polished software marketing. Black and white grotesk typography carries the argument, with acid yellow, pink, lavender and electric blue reserved for loud promotional islands. Oversized cutout products, scattered objects and cheap-looking stickers bring controlled disorder to otherwise spacious layouts. It suits tangible products and opinionated consumer brands with something genuinely entertaining to say.

### Essentials

- The product becomes the headline: a 900px black opening is crowded with overlapping, rotated product-sized planes, a 280×175px identity graphic at upper left and a compact 40px/42px mock endorsement at lower left. Recreate this object pile with original product fragments when there is no physical packaging.
- Headlines sound like blunt instructions and look like packaging: Helvetica Neue LT at 80px/1, weight 800, normal tracking for major section leads; 40px/42px, weight 800 for questions and product titles.
- Conversion controls are heavy capsules, not rectangular app buttons: black fill, white text, 64px height and 64px radius; 80px height and radius for oversized editorial actions. Borders and inset outlines are 2px.
- Color arrives as loud islands inside a predominantly black-and-white page: full-width white editorial bands alternate with black stages; 20px-radius promotional tiles carry flat cyan, lemon or pink, while yellow/red, lavender/purple and blue/gold form the story-card pairs.
- Objects interrupt the grid without making the reading column messy: isolate products on transparent backgrounds, enlarge and crop them at tile edges, and keep long prose in an 832px centered column within a 1600px maximum container with 90px desktop side padding.
- A deliberately low-rent sales flourish punctures the clean type: include a hard-edged starburst or outlined pointing sticker with a tiny blunt message. Pair it with a flat, cutout-led promotional card rather than replacing it with a sleek gradient or glow.
- The ending returns to utilitarian print: a white footer with 100px vertical padding, black identity, three narrow link columns, and an outlined email field; links are bold 20px/26px and visibly underlined.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement yellow | `#fadf0e` | `--color-announcement` | background | Narrow attention strip above the black navigation. |
| Feature lemon | `#fffd6d` | `--color-feature-lemon` | surface | Flat merchandising tile background. |
| Feature cyan | `#a0e9ff` | `--color-feature-cyan` | surface | Companion merchandising tile background. |
| Feature pink | `#ffa0f0` | `--color-feature-pink` | surface | Companion merchandising tile background. |
| Story yellow | `#fffe5b` | `--color-story-yellow` | surface, text | Story card background, paired with red titles and inverse red tags. |
| Story red | `#fe2f2f` | `--color-story-red` | text, surface, link | Titles, tags and read links on story-yellow cards. |
| Story lavender | `#ede5ff` | `--color-story-lavender` | surface, text | Story card background, paired with purple titles and inverse purple tags. |
| Story purple | `#7333f1` | `--color-story-purple` | text, surface, link | Titles, tags and read links on story-lavender cards. |
| Story blue | `#1b5bff` | `--color-story-blue` | surface, text | Story card background, paired with gold titles and inverse gold tags. |
| Story gold | `#d7b73b` | `--color-story-gold` | text, surface, link | Titles, tags and read links on story-blue cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper and reversed ink | `#ffffff` | `--color-white` | text, background, surface, border | Editorial bands, footer, white product planes and all reversed type. |
| Mid-gray rule | `#808080` | `--color-rule` | border | 2px accordion and navigation separators; not muted body text. |
| Black ink and night canvas | `#000000` | `--color-black` | text, background, surface, border, action | Default dark stage, light-band text, controls and outlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| family-oriented product details | Family product yellow | `#fffc6d` | `--color-family-yellow` | background | Full-width bright product-detail stage with black text. |

## Typography

- **Helvetica Neue LT** — All marketing headings, paragraphs, navigation and controls. Matter-of-fact neo-grotesk with blunt, dense extra-bold headings and open regular body text. If unavailable, use **Roboto**. Use 400, 700 and 800; retain normal tracking and the compact heading leading. Font stack: "Helvetica Neue LT", "Roboto", -apple-system, system-ui, "Helvetica Neue", Helvetica, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Helvetica Neue LT | 800 | 80px | 1 | normal | Major marketing section headings, editorial opening statements and the monumental newsletter invitation. |
| feature-title | Helvetica Neue LT | 800 | 65px | 1 | normal | Short, chunky headlines on oversized merchandising tiles. |
| story-title | Helvetica Neue LT | 800 | 55px | 54px | normal | Colored story-card headlines, wrapping into compact three- or four-line blocks. |
| heading | Helvetica Neue LT | 800 | 40px | 42px | normal | FAQ questions, product titles, recommendation headings and short mock endorsements. |
| editorial | Helvetica Neue LT | 400 | 40px | 1.25 | normal | Big explanatory prose in white bands. |
| email-large | Helvetica Neue LT | 400 | 40px | 26px | normal | Vertically centered placeholder in the 104px-high newsletter field. |
| body | Helvetica Neue LT | 400 | 28px | 36px | normal | FAQ answers and longer dark editorial narratives. |
| label | Helvetica Neue LT | 800 | 28px | 30px | normal | Navigation, product-card titles and short read links. |
| button-xl | Helvetica Neue LT | 800 | 28px | 80px | normal | Oversized download or accordion utility actions. |
| button | Helvetica Neue LT | 800 | 24px | 64px | normal | Filled merchandising actions. |
| small-body | Helvetica Neue LT | 400 | 20px | 1.3 | normal | Product-card descriptions and footer email field text. |
| small-bold | Helvetica Neue LT | 800 | 20px | 1.3 | normal | Footer column headings, links and email invitation. |
| aside | Helvetica Neue LT | 400 italic | 20px | 1.3 | normal | Conversational reassurance under the main email field. |
| tag | Helvetica Neue LT | 800 | 16px | 38px | normal, uppercase | Capsule category labels on story cards. |
| announcement | Helvetica Neue LT | 800 | 16px | 1.25 | normal | Centered, underlined announcement link. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company stories | company-body | Helvetica Neue LT | 400 | 32px | 1.25 | normal | Plainspoken company narrative. |
| commerce controls | cart-label | Helvetica Neue LT | 700 | 28px | 60px | normal | Add-to-cart control label and right-aligned price. |
| long-form campaigns | campaign-question | Helvetica Neue LT | 800 | 28px | 36px | normal | Inline emphasis and always-expanded FAQ questions. |
| product detail pages | product-body | Helvetica Neue LT | 400 | 24px | 28px | normal | Description and bullets beside the hero product. |

**Notes:**

- Normal tracking is the rule even at 80px. Weight and almost closed-up display leading create the impact; do not imitate it with condensed type or extreme negative tracking.
- Headings remain sentence case. Uppercase belongs to announcement copy and small story tags, not ordinary section titles.
- The opening identity and text on physical objects are artwork, not a second web-font hierarchy. The ordinary heading recipe also supplies the short quote overlay.

## Layout

**Density:** Airy sections with dense, blunt text blocks: large black-and-white bands make the compact headlines feel louder.

### Spacing

**Spacing system:**

- **step** 10px — Dominant spacing rhythm for section padding, controls and content offsets; grid gutters use a separate 12px half-gutter.

| Value | Use |
| --- | --- |
| 10px | Title-to-description spacing in product cards. |
| 20px | Card padding, FAQ trigger vertical padding and title-to-copy gap. |
| 24px | Full grid gutter formed by two 12px column paddings. |
| 26px | Paragraph separation in editorial narratives. |
| 30px | Story-card padding, carousel gaps and product-copy-to-action separation. |
| 40px | Oversized feature-tile padding and primary button horizontal padding. |
| 50px | Major heading-to-prose spacing and media separation within product cards. |
| 60px | Product-stage vertical padding and oversized action horizontal padding. |
| 80px | Separation around company narrative and quote modules. |
| 90px | Dark section vertical padding and desktop container side padding. |
| 100px | Footer vertical padding. |
| 120px | Long-form campaign chapter separation. |
| 160px | White explanatory and newsletter band vertical padding. |

### Containers and grids

- **main-container**: max width 1600px · side padding 90px. Centered desktop outer container; at 1440px it gives a 1260px usable span.
- **reading-column**: max width 832px. Centered prose, download editorial and company narrative; align its heading and copy to the same left edge.
- **newsletter-column**: max width 920px. Centered, wider invitation and full-width email input.
- **three-card-grid**: 3 columns · gap 24px. Three equal portrait cards, 404px wide at the desktop reference width. Commerce card interiors are approximately 360px wide.
- **feature-carousel**: gap 30px. Oversized 830×600px tiles in an overflow-clipped track, with neighboring tiles visibly cropped.
- **footer-columns**: gap 20px. Identity on the left, three 180px link columns, and a 360px newsletter column on the right.
- **product-split** (only for product detail pages): 2 columns · gap 24px. A 578×578px image region on the left and a 460px maximum text column on the right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature-and-story-tiles | 20px |
|  | primary-capsules | 64px |
|  | oversized-capsules | 80px |
|  | email-fields | 10px |
|  | small-circular-controls | 32px |
|  | story-tags | 38px |
|  | hero-object-planes | 13px |
| commerce sections | commerce-cards | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| printed-button-outline | `rgb(0, 0, 0) 0px 0px 0px 2px inset` | Filled black merchandising capsules. This is a hard inset outline, not elevation. |

### Surfaces

#### Night stage · level 0

**Use:** Default marketing canvas and merchandising sections.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black, without gradients, texture or ambient light.

**Transfer:** Use white typography and high-contrast object silhouettes.

#### Paper band · level 0

**Use:** Explanatory passages, newsletter and footer.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Abrupt, full-bleed transition from black; the introductory explanation has 2px black top and bottom rules.

**Transfer:** Separate editorial reading from merchandise through a full inversion, not a pale-gray intermediate.

#### Feature tile · level 1

**Use:** Oversized merchandising canvas.

**CSS:** `background: #fffd6d; color: #000000; border-radius: 20px; overflow: hidden`

**Observed:** Companion tiles switch to cyan and pink. Objects are layered and deliberately clipped by the tile.

**Transfer:** Keep one flat, loud fill per product family.

#### Story poster · level 1

**Use:** Proof, past work and entertaining editorial cards.

**CSS:** `background: #fffe5b; color: #fe2f2f; border-radius: 20px; overflow: hidden`

**Observed:** Also lavender with purple and blue with gold. Each poster keeps title, tag and read link in one contrasting ink.

**Transfer:** Use the three defined pairs rather than inventing a rainbow of unrelated accents.

#### Outlined commerce panel · level 1

**Only for:** commerce sections

**Use:** Product recommendations and shop grids.

**CSS:** `background: #000000; color: #ffffff; border: 2px solid #ffffff; border-radius: 16px`

**Observed:** No drop shadow; a tall panel frames copy, isolated product and bottom capsule.

**Transfer:** Keep borders visible around dark packaging.

#### Bright product stage · level 0

**Only for:** family-oriented product details

**Use:** A child-friendly product detail variant.

**CSS:** `background: #fffc6d; color: #000000`

**Observed:** The whole product split sits on yellow while navigation and recommendations stay black.

**Transfer:** Use a full-stage hue only when a distinct product audience warrants it.

#### Quote frame · level 1

**Only for:** company stories

**Use:** A closing anti-testimonial carousel.

**CSS:** `border: 2px solid #000000; border-radius: 20px; padding: 60px 0; color: #000000; background: #ffffff`

**Observed:** 832×480px, with centered short quote, attribution below and circular side arrows.

**Transfer:** Use a disarmingly short, honest customer remark in a large empty frame.

## Components

### Navigation

**Use:** Persistent black top navigation.

**CSS:** `background: #000000; color: #ffffff; padding: 0 30px; height: 76px`

**Text style:** `label` — Helvetica Neue LT 800 · 28px/30px

**Observed:** Identity left; two short dropdown labels, small down chevrons and a basket/count icon right. Above the object-pile opening the identity is expanded into a stacked graphic; scrolling uses a compact single-line identity.

### Announcement strip

**Use:** Attention-grabbing global notice above navigation.

**CSS:** `background: #fadf0e; color: #000000; padding: 15px 20px; height: 50px; text-align: center`

**Text style:** `announcement` — Helvetica Neue LT 800 · 16px/1.25

**Observed:** Single underlined uppercase link centered, small close cross at the right.

**States:** Declared: hover text-decoration-color transparent; focus-visible outline none.

### Primary button

**Use:** Main action on colored merchandising tiles.

**CSS:** `background: #000000; color: #ffffff; border-radius: 64px; padding: 0 40px; height: 64px; box-shadow: rgb(0, 0, 0) 0px 0px 0px 2px inset`

**Text style:** `button` — Helvetica Neue LT 800 · 24px/64px

**Observed:** Content-sized capsule aligned under the tile headline. Editorial download actions use the button-xl recipe, 80px height/radius and 60px horizontal padding; the black FAQ utility reverses to white fill and black text.

**States:** Declared: hover background-color #ffffff and color #000000; focus-visible outline none.

### Feature tile

**Use:** Large linked product-family promotion.

**CSS:** `background: #fffd6d; color: #000000; border-radius: 20px; overflow: hidden; padding: 40px`

**Text style:** `feature-title` — Helvetica Neue LT 800 · 65px/1

**Observed:** 830×600px tile with objects entering from above and the right; headline and Primary button grouped at lower left. Title column is limited to 420px. Other tiles use cyan or pink.

### Story card

**Use:** Colorful editorial proof poster.

**CSS:** `background: #fffe5b; color: #fe2f2f; border-radius: 20px; overflow: hidden; position: relative`

**Text style:** `story-title` — Helvetica Neue LT 800 · 55px/54px

**Observed:** 404×606px desktop card; 30px inset positions Story tag then bold headline. A large cutout or illustration grows from the lower-left edge; a short Read label and circled northeast arrow stay lower right. Lavender/purple and blue/gold variants retain the same construction.

### Story tag

**Use:** Small category or date marker on a Story card.

**CSS:** `background: #fe2f2f; color: #fffe5b; border-radius: 38px; padding: 0 20px; height: 38px; text-transform: uppercase`

**Text style:** `tag` — Helvetica Neue LT 800 · 16px/38px · uppercase

**Observed:** Content-sized capsule above the headline; its fill uses the title ink and its text uses the card background.

### Email field

**Use:** Footer newsletter collection; enlarged for the main invitation.

**CSS:** `border: 2px solid #000000; border-radius: 10px; height: 50px; position: relative`

**Text style:** `small-body` — Helvetica Neue LT 400 · 20px/1.3

**Observed:** Footer version is 360px wide with an in-field circular arrow on the right. Main invitation expands to 920×104px, uses email-large text and a 40px circular arrow. No separate rectangular submit button.

### FAQ trigger

**Use:** Compact collapsible questions in a black objection-handling band.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 20px 0; color: #ffffff`

**Text style:** `heading` — Helvetica Neue LT 800 · 40px/42px

**Observed:** Full-width row with a 20px plus at right; 2px mid-gray rules separate rows. Answers use body text, 30px left inset and 50px bottom padding. Expand All is a white oversized capsule aligned right below the list.

**States:** Declared: focus-visible outline currentcolor dotted 2px.

### Inline link

**Use:** Links woven into paragraphs without button treatment.

**CSS:** `color: #ffffff; text-decoration: underline; transition: text-decoration-color 0.2s`

**Text style:** `body` — Helvetica Neue LT 400 · 28px/36px

**Observed:** Same size and weight as surrounding prose; black on paper bands and bold when the linked product is emphasized.

**States:** Declared: hover text-decoration-color transparent; focus-visible outline none.

### Footer menu

**Use:** Dense but legible utility navigation in the white ending.

**CSS:** `color: #000000; max-width: 180px; margin-right: 20px`

**Text style:** `small-bold` — Helvetica Neue LT 800 · 20px/1.3

**Observed:** Column heading, 20px space, then underlined stacked links with approximately 10px gaps. Three menus sit between identity and email block. Locale capsule lower left, small legal links and copyright lower right.

### Cart capsule

**Only for:** commerce controls

**Use:** Direct purchase from hero or recommendation card.

**CSS:** `background: #000000; color: #ffffff; border: 2px solid #ffffff; border-radius: 64px; padding: 0 30px; height: 64px`

**Text style:** `cart-label` — Helvetica Neue LT 700 · 28px/60px

**Observed:** Action sits left, price sits right in the same button. A confirmation label replaces the action after adding. On the bright product stage the border is black.

**States:** Declared: hover background-color #ffffff and color #000000; focus-visible outline none.

### Product card

**Only for:** commerce sections

**Use:** A related item or directly purchasable offering.

**CSS:** `border: 2px solid #ffffff; border-radius: 16px; color: #ffffff; position: relative`

**Text style:** `label` — Helvetica Neue LT 800 · 28px/30px

**Observed:** Title and small-body description at top, isolated product centered in a roughly 360×325px media area, Cart capsule anchored at bottom. Inner padding is 20px; descriptions sit 10px below titles. New-item starbursts overlap the top-right outline.

**Transfer:** Keep equal card heights and align purchase controls despite unequal title lengths.

## Imagery and graphics

### Object pile

**Use:** Signature marketing first screen.

**Observed:** White and black portrait cards overlap on a pure black field, tipped in opposing directions. Large edge-clipped white cards form the rear layer; one black card with a thin white edge sits in front near center. Objects fill nearly the whole viewport while identity and a mock laurel quote occupy left-side pockets.

**Transfer:** For a different product, pile original packaging panels, printed outcomes, swatches or product fragments. If only a digital product exists, create tangible monochrome cards with short sample outputs; avoid a conventional laptop mockup.

**Build:** Use an overflow-hidden 900px stage. Layer six to eight absolute portrait planes about 300–340px wide and 420–460px tall, with 13px corners and 2px opposite-color borders; rotate rear planes roughly -15deg to 12deg and let several exceed the top and bottom. Put a black plane in the central foreground, slightly tilted, with bold white short text at its top. These dimensions and rotations are a construction guide; preserve overlap and silhouette rather than exact coordinates.

### Isolated product packs

**Use:** Feature tiles, commerce hero and product cards.

**Observed:** Realistic printed boxes and foil packs shown at a slight three-quarter angle, crisply cut out. Packaging carries its own color and gloss, but the site adds no environmental shadow or room scene. Detail stages give the object about half the width; commerce cards center a smaller whole pack between copy and action.

**Transfer:** Use a high-resolution transparent cutout or a simple physically plausible package render. Preserve printed texture and hard silhouette; allow dramatic cropping only on feature tiles, not in comparison cards.

### Sales stickers

**Use:** Signature irreverent annotation near a conversion or card corner.

**Observed:** Jagged outlined seals, tilted tiny announcements and a crudely outlined pointing arrow interrupt the otherwise clean layout. New-item seals overlap card borders; an editorial download band has a starburst and a pink directional sticker.

**Transfer:** Write a short, original aside or factual new-item label and keep the treatment closer to a discount-store sticker than a polished badge.

**Build:** Draw a 20–28-point SVG polygon with alternating inner and outer radii, solid white or a palette accent fill, and a 2px black outline. Place a two-line bold black message inside; rotate the whole badge slightly and overlap a panel corner. For a pointing sticker, use an outlined rectangle ending in a triangular arrowhead, a palette accent fill and short centered black text. No blur or glow.

### Cutout story illustrations

**Use:** Proof posters on the default marketing page.

**Observed:** Heterogeneous artwork is intentional: a photographic chair-and-sign montage, a hand-drawn seated person and a realistic excavator. Each emerges from the bottom edge against a flat paired-color background; the top half remains dominated by a colored headline.

**Transfer:** Use a relevant original cutout or simple editorial illustration with a strong silhouette. A single well-cut object on a flat color is preferable to a weak elaborate montage.

**Build:** Back a 20px-radius poster with a flat palette pair. Put type in a 30px inset at top, then anchor a transparent image or simple SVG illustration at bottom left, clipped by the poster. Keep the lower-right Read label free of the image.

### Campaign evidence banners

**Only for:** long-form campaigns

**Use:** Break up narrative chapters with wide proof or announcement media.

**Observed:** 1260×550px landscape panels with rounded corners: before/after land imagery, satellite-map labeling, warm yellow-green wildlife photography with a centered black diamond seal, and a dense product arrangement on yellow. These are much wider than the 832px text column.

**Transfer:** Alternate readable prose with real documentary imagery, annotated maps or a product spread. Keep any overlaid graphic central and high-contrast; use the campaign's subject rather than generic lifestyle photography.

### Scattered company collage

**Only for:** company stories

**Use:** A broad playful visual chapter after plain narrative.

**Observed:** Loose rows of independently rotated cutouts on white: packaging, a portrait rectangle, a machine, novelty objects, a cookie and printed ephemera. Sizes and angles vary, outer objects clip beyond page edges, and no tile backgrounds unify them.

**Transfer:** Gather original artifacts that reveal the business's actual personality. Use transparent cutouts and a few photographic rectangles; leave enough white around each to read its silhouette.

**Build:** Create a full-width relative white area below the prose. Arrange 12–16 independent image elements in staggered rows with generous uneven gaps, alternating upright objects and small rotations; clip outermost elements at the viewport. Avoid repeated uniform cells.

### Icons

**Observed:** Small monochrome utility graphics: filled down chevrons around 14×9px, 20px plus signs, 18×16px arrow glyphs, circular 32px outline controls and a 54×25px basket/count mark. Small black pictograms scatter around white editorial bands.

**Transfer:** Choose blunt monochrome arrows, pluses and chevrons, with 2px control outlines. Decorative pictograms should be sparse and relevant; reserve mixed-color icons for colored editorial posters.

## Section recipes

How recurring sections are built.

### First screen: Object pile opening

**Observed:** The first 900px is a black, viewport-filling product composition, not a centered headline-and-button hero. Back to front: black field; enlarged white card planes clipped at upper and lower edges; stacked 280×175px white identity at upper left; a central black card with reversed short copy; navigation at upper right; compact laurel-flanked quote at lower left using heading type. The product planes dominate roughly two thirds of the visible width and overlap the identity's lower region. A 50px announcement strip spans the top. The headline function belongs to the identity and product copy; there is no standalone explanatory heading or primary conversion button in this first screen. Explanatory prose and purchase tiles begin below the fold.

**Transfer:** Give a new product an equally oversized physical language: original product panels or cards carrying sample results, with the product name prominent at upper left and real utility navigation kept clear. Recreate planes in CSS/SVG when no pack photography exists. Product-detail pages instead open with the product split, a 40px heading and immediate Cart capsule; campaign and company pages use a centered 80px statement over a narrow prose column.

**Avoid:** Do not reduce this to a small centered pack floating below a generic oversized slogan, or add a stack of pill CTAs across the foreground. Do not treat embedded card copy as a giant web heading.

**Text style:** `heading` — Helvetica Neue LT 800 · 40px/42px

### Blunt explanation on paper

**Observed:** Paper band with 160px vertical padding, centered 832px reading column, editorial type and 20px paragraph gap. The product name is bold within the opening sentence. Small black pictograms occupy surrounding white space rather than the reading path.

**Transfer:** Explain what the thing is and how it works in two oversized, unpretentious paragraphs. Let a bold inline name begin the explanation; no eyebrow is needed.

**Text style:** `editorial` — Helvetica Neue LT 400 · 40px/1.25

### Oversized merchandise track

**Observed:** Night stage, display heading on left and two small circular navigation controls on right. A 50px heading-to-track gap leads into Feature tiles, 830×600px with 30px track gaps and partial neighboring tiles.

**Transfer:** Promote product families or use cases through short headlines and oversized cutouts; maintain visible overflow as the browsing cue.

**Text style:** `display` — Helvetica Neue LT 800 · 80px/1

### Editorial giveaway or offer

**Observed:** Paper band uses display heading, 50px gap to editorial prose, then a centered oversized action. A Sales sticker floats near the heading and a pointing sticker annotates the action.

**Transfer:** Present a useful free sample, guide or low-friction offer with a frank explanation and a small ridiculous visual nudge.

**Text style:** `display` — Helvetica Neue LT 800 · 80px/1

### Three proof posters

**Observed:** Night stage with display lead, then three Story cards in a 24px-gutter grid. Tags precede colored headlines and cutout art fills the bottom. One starburst overlaps the upper-right area of the group.

**Transfer:** Turn genuine milestones, experiments or evidence into entertaining editorial posters rather than a monochrome logo wall.

**Text style:** `story-title` — Helvetica Neue LT 800 · 55px/54px

### Monumental newsletter invitation

**Observed:** Paper band, 160px vertical padding and 920px centered column. A three-line 80px invitation includes a changing absurd example, then a 50px gap to the enlarged Email field and a 30px gap to italic reassurance.

**Transfer:** Ask for the email address with a specific, amusing reason and an honest frequency/privacy reassurance. Keep the form quieter than the invitation.

**Text style:** `display` — Helvetica Neue LT 800 · 80px/1

### Questions then utility ending

**Observed:** Night stage with display heading and full-width FAQ triggers separated by gray rules. Expand All sits right below the list. A sharp switch to the white footer closes the page: 100px vertical padding, identity at left, Footer menus and Email field across the width, locale and legal utilities below.

**Transfer:** Use objection handling as the last substantial content when useful, then land on the same practical white footer. Other page types can lead directly from recommendations or a final short remark to this ending.

**Text style:** `heading` — Helvetica Neue LT 800 · 40px/42px

### Product split and recommendations

**Only for:** product detail pages

**Observed:** A roughly 700px high stage has 60px vertical padding, a 578px square media region left, a 460px copy column right, heading type, product-body prose and bullets, then Cart capsule. Small scattered monochrome marks and a 100px thumbnail provide visual texture. Standard product uses black; the family variant uses Bright product stage. A 40px recommendation lead introduces three outlined Product cards on black before the white footer.

**Transfer:** Keep pack, factual description, a few useful bullets and purchase control visible together within the first desktop screen. Differentiate an audience-specific product with the scoped bright stage, not a new type system.

**Text style:** `heading` — Helvetica Neue LT 800 · 40px/42px

### Campaign letter with wide evidence

**Only for:** long-form campaigns

**Observed:** Centered 80px opening statement on black, 832px body column in 28px/36px, 26px paragraph gaps, and 1260×550px media panels between chapters. Narrative ends with a personal sign-off before large support headings, commerce grids and an always-expanded FAQ. The final answer is a short deadpan conclusion before the shared white footer.

**Transfer:** Make a case, show tangible evidence, invite participation, then answer objections openly. Use the campaign-question recipe for questions rather than the default accordion.

**Text style:** `display` — Helvetica Neue LT 800 · 80px/1

### Company story and anti-testimonial

**Only for:** company stories

**Observed:** White field, centered 80px title, a small object mark, then 832px-wide company-body prose. A loose Scattered company collage follows. The ending before the shared footer is a Quote frame containing a very short irreverent remark, attribution and circular previous/next arrows.

**Transfer:** Tell the origin in ordinary language, show artifacts rather than corporate portraits, and puncture self-importance with a brief honest quote.

**Text style:** `company-body` — Helvetica Neue LT 400 · 32px/1.25

## Page flow

**Storyline:** object-led hook → plain explanation → offer or merchandise → entertaining proof → invitation → objections → practical white footer

### A broad marketing landing page that introduces the product and routes people to offerings

1. **Hook** — Full-screen monochrome object pile with graphic identity and mock endorsement.
2. **Explanation** — Large plain-language paragraphs on white.
3. **Offer** — Black merchandising stage with colored overflow tiles, followed by a white free-offer editorial band.
4. **Proof** — Three colored cutout posters.
5. **Invitation** — Monumental email ask with one outlined field.
6. **Objection handling** — Long collapsed FAQ and right-aligned expansion control.
7. **Utility ending** — White multi-column footer with another compact email field.

**Transfer:** Use the default expressive marketing treatment; choose the relevant offers and evidence without copying a fixed section count.

### A playful audience-specific product detail page

1. **Product demonstration** — Yellow split stage, large isolated package and plain factual bullets.
2. **Purchase** — Black filled cart capsule with inline price.
3. **Related offers** — Three white-outlined dark product cards.
4. **Utility ending** — Shared white footer.

**Transfer:** Use the scoped bright product variant for a genuinely differentiated audience while preserving the commerce construction.

### A direct flagship product purchase page

1. **Product demonstration** — Black split stage with isolated package and white descriptive copy.
2. **Purchase** — White-outlined cart capsule with action and price.
3. **Related offers** — Three dark outlined recommendations with compact descriptions.
4. **Utility ending** — Shared white footer.

**Transfer:** Keep this concise structure for buyers who already know the category; use the object-pile opening for broader marketing instead.

### A long persuasive campaign that turns a story into participation and purchases

1. **Provocation** — Centered extra-bold statement above regular prose on black.
2. **Evidence** — Text chapters alternate with wide documentary and product banners.
3. **Personal connection** — Letter-style sign-off before the purchase area.
4. **Participation** — Large chapter headings and two three-column commerce grids.
5. **Objection handling** — Always-open question-and-answer sequence in the narrow reading column, ending on a terse joke.
6. **Utility ending** — Shared white footer.

**Transfer:** Borrow the letter cadence and wide-evidence/narrow-prose contrast for an original cause or launch story.

### An informal company origin story

1. **Identity** — Centered extra-bold title on white.
2. **Explanation** — Large regular paragraphs in the narrow reading column.
3. **Character proof** — Loose artifact collage without uniform tiles.
4. **Closing proof** — Outlined anti-testimonial carousel.
5. **Utility ending** — Shared white footer.

**Transfer:** Keep the white company-story variant separate from the default black marketing stage.

## Writing

Confident, profane, conversational and aggressively unimpressed with itself. Useful facts are stated plainly, then undercut with an absurd aside; the humor is closer to a friend heckling a sales pitch than a brand trying to sound inspirational.

**Do not copy:** Do not reuse the brand name, logo, card jokes, packaging artwork, campaign targets, insults about identifiable people, press/customer quotations, proprietary product names, numbers, donation promises or legal claims. Write original humor and substantiate every commercial fact. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak as we to you. Address ordinary practical questions directly and refer to the product in plain nouns rather than elevated abstractions.
- **Rhythm:** Most section titles are two to five words, sentence case and often punctuated with a period. Body paragraphs run in conversational bursts; a brief sentence can abruptly puncture a longer explanation. Actions remain literal even when surrounding copy is ridiculous.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Section headline | Short imperative or blunt noun phrase, often deliberately undercutting a conventional sales promise. | 2–5 words | “Buy the game.”<br>“Steal the game.”<br>“Your dumb questions.” |
| Supporting line | Real practical information followed by a dry, oddly specific joke. | One short sentence or a compact bullet | “Sorry, not as fun as Xbox.”<br>“This is the main game. Buy this first.” |
| Primary action | Literal verb plus tangible object; price is separate within commerce controls. | 2–4 words | “Download Files”<br>“Buy Family Edition” |
| FAQ answer | Answer the actual question before elaboration; a one-line refusal can be the whole joke. | One sentence to two short paragraphs | “No. We need to make money somehow.”<br>“No! We don't want to.” |
| Reassurance | A casually phrased concrete promise instead of legalistic comfort language. | One sentence | “We’ll only email you like twice a year and we won’t share your info with anybody else.” |
| Company narrative | Describe the enterprise almost childishly literally, then puncture it. | 2–4 sentences per paragraph | “[Brand] is a game made of cards. You put the cards together to make jokes. It’s pretty stupid!” |

**Words and phrasing to use:** we; you; stuff; here; buy; free; dumb; plain product nouns; oddly specific concrete asides

**Avoid:** revolutionary; seamless; unlock your potential; world-class; elevate; empower; generic mission language

**Rules:**

- Keep purchase instructions clearer than the jokes.
- Use profanity as a tonal accent, not a replacement for an actual observation.
- Make the business itself a frequent target of the humor.
- Keep facts and limitations visible; blunt honesty is part of the entertainment.
- Use specific absurdity rather than a stream of random internet slang.

## Do's and Don'ts

### Do

- Keep major headings at 80px/80px, weight 800, with normal tracking.
- Use 40px/50px regular prose for the big white explanatory bands.
- Preserve the 90px desktop margins and 832px reading column inside a 1600px maximum container.
- Pair each colored story background with its defined contrasting title/tag ink.
- Make merchandising actions 64px capsules and editorial utility actions 80px capsules.
- Stage large cutout objects with hard silhouettes and deliberate edge clipping.
- Use 2px outlines for commerce panels, rules and form controls.
- Close with a white, 100px-padded utility footer and a compact outlined email field.

### Don't

- Do not add soft card-elevation shadows; the inset button outline is not a drop shadow.
- Do not use gray body text as the default hierarchy; type is black or white at full contrast.
- Do not make all merchandise tiles the same small dashboard-card size; the feature track uses 830×600px canvases.
- Do not turn ordinary section headings into spaced-out uppercase labels.
- Do not apply lavender, pink or blue as a uniform page tint; keep them as bounded merchandising and editorial islands.
- Do not put rounded rectangular submit buttons outside the email field; the arrow lives inside it.
- Do not place the action and price in separate disconnected controls.
- Do not force the company collage, campaign letter or yellow product-detail stage onto every new landing page.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions use background-color and color over 0.2s; filled merchandising buttons also transition box-shadow over 0.2s.
- Inline links transition text-decoration-color over 0.2s.
- Product portrait image animations are declared as 15s linear infinite loops.
- The opening contains transformed card planes and the main newsletter invitation contains changing example text.

**Transfer:**

- Keep hover behavior a simple black/white inversion rather than a glow or scale pop.
- Use the object-pile layering and cropped product imagery as the motion subjects; keep reading copy stable.

**Unknown:**

- Exact opening animation sequence, carousel autoplay behavior and newsletter text timing are unknown.

### Responsive

**Observed:**

- Declared width boundaries cluster at 360px, 400px, 600px, 760px, 1000px, 1200px and 1349px.
- The main merchandising title declares 32px, 48px and 65px sizes across responsive classes; FAQ question classes declare 20px and 40px. Major section titles declare 40px and 80px variants.

**Transfer:**

- On narrow layouts, preserve the cropped-object opening rather than shrinking every object into a small centered thumbnail.
- Use horizontal browsing for oversized merchandise tiles and stack the product split when two readable columns no longer fit.
- Reduce outer padding before compromising readable paragraph width; retain black/white section inversions and in-field email arrows.

**Unknown:**

- Mobile column counts, exact breakpoint-to-layout mappings and narrow-screen footer behavior are not established. Responsive transfer statements are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
