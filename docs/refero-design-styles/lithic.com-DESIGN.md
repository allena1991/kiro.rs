# Lithic — contours around infrastructure

## Overview

A confident infrastructure aesthetic that makes technical systems feel tangible and well supported. White space and compact grotesk typography alternate with cinematic black stages, pale mint, lilac and peach panels, and small flashes of orange. Fine looping contours, floating interface fragments and carefully lit product objects give the otherwise restrained layouts a sense of movement and depth.

### Essentials

- Compact words against expansive stages: headlines use a 64px/1 medium grotesk with -0.02em tracking; section headings drop decisively to 32px/1.2 rather than competing with the opening.
- A dark object procession behind a centered promise: the default opening is an inset 1392px-wide black stage with 24px corners beneath a 65px white navigation bar; text occupies a centered 960px measure while diagonal objects continue beyond its edges.
- Color lives in bounded chapters: white is the connective canvas, black carries dramatic hero and service scenes, and mint #ebfef6, lilac #f6f1fe and peach #fff2ed each fill a whole rounded panel rather than many little accents. Saturated #ff6600 is normally confined to compact actions.
- Actions are small capsules, not oversized banners: 32px rendered height, 160px radius, 14px medium labels, 24px horizontal padding and a 14px right arrow. Orange conversion and frosted secondary actions form a 16px-spaced pair.
- Continuous-line sculpture is the signature connective device: many thin, nested, off-center loops sweep behind objects and reappear in pale panels and the closing call. Every new page includes this device; without product art, the contours themselves become the main scene.
- Technical proof is made tactile: warm #f6f3ee proof tiles use 24px corners and 40px padding; interface fragments float over pastel fields, while dark service cards use 10% white glass, a 1px edge and 32px backdrop blur.
- The closing invitation is a designed object: a peach panel 282px high with cropped orange contour rings holds one 32px heading and one small action; the white six-column footer returns the page to an orderly, low-contrast directory.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion orange | `#ff6600` | `--color-orange` | action, accent, border | Primary conversion capsules and small active markers; not the default large-area fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale mint | `#ebfef6` | `--color-mint-panel` | surface | Developer and tooling chapters. |
| Pale lilac | `#f6f1fe` | `--color-lilac-panel` | surface | Interactive capability stage. |
| Pale peach | `#fff2ed` | `--color-peach-panel` | surface | Closing invitation panel. |
| Capability purple | `#5c2999` | `--color-purple` | text, accent | Tab labels and checks within the lilac capability stage. |
| Bronze copy | `#665233` | `--color-bronze` | text | Support details in warm proof tiles. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Connecting canvas, reversed type and white actions. |
| Near white | `#fafafa` | `--color-soft-card` | surface | Feature, resource and team-card surfaces. |
| Warm stone | `#f6f3ee` | `--color-warm-panel` | surface | Proof and testimonial panels; backing for resource images. |
| Accordion rule | `#e8e8e8` | `--color-rule` | border | Thin dividers between question rows. |
| Light card edge | `#e6e6e6` | `--color-soft-edge` | border | Visible result of 10% black over white on floating interface fragments. |
| Medium gray | `#888888` | `--color-muted` | text | Secondary copy on dark backgrounds and footer links on white. |
| Frosted action | `#333333` | `--color-frost` | surface | Visible result of 20% white over black in secondary action capsules. |
| Deep brown | `#261e12` | `--color-nav-brown` | surface | Utility dashboard capsule. |
| Black-stage glass | `#1a1a1a` | `--color-glass` | surface, border | Visible result of 10% white over black; contours remain visible through the alpha surface. |
| Black | `#000000` | `--color-ink` | text, background | Primary text and cinematic dark stages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company storytelling | Award blue wash | `#eef1ff` | `--color-award-tint` | surface | Broad recognition panel. |
| account infrastructure product pages | Deep cobalt backing | `#0c112a` | `--color-navy` | surface | Feature cards, quotation inset and conversion band. |
| account infrastructure product pages | Cobalt action | `#3f54bf` | `--color-cobalt` | action, accent | Category tag and local conversion capsule. |
| account infrastructure product pages | Periwinkle quotation | `#768cfa` | `--color-periwinkle` | text | Long quotation on navy. |
| full-bleed dark product openings | Light gray | `#aaaaaa` | `--color-dark-muted` | text | Support paragraphs in dark product chapters. |
| issuing product pages | Deep emerald backing | `#00291a` | `--color-forest` | surface | Local conversion band. |
| issuing product pages | Emerald action | `#00cc88` | `--color-emerald` | action, accent | Category tag, local conversion capsule and fine contours. |

## Typography

- **ABC Monument Grotesk** — All marketing text, headings, navigation and labels. Compact contemporary grotesk with a high x-height and direct, unfussy shapes; medium rather than heavy headings. If unavailable, use **Inter**. Use 400 and 500; retain compact widths and negative heading tracking. Font stack: "ABC Monument Grotesk", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ABC Monument Grotesk | 500 | 64px | 1 | -0.02em | Primary promise, normally centered and balanced over two lines. |
| section-heading | ABC Monument Grotesk | 500 | 32px | 1.2 | -0.02em | Section leads, closing call and centered proof headings. |
| card-heading | ABC Monument Grotesk | 500 | 24px | 1.2 | -0.02em | Capability headings and proof-tile titles. |
| hero-support | ABC Monument Grotesk | 400 | 24px | 1.4 | normal | Broad centered opening support; also long quotations in the navy inset. |
| tab-label | ABC Monument Grotesk | 500 | 24px | 1.4 | -0.02em | Right-aligned vertical capability menu. |
| item-heading | ABC Monument Grotesk | 500 | 20px | 1.2 | -0.02em | Service-card titles and resource headlines. |
| quote | ABC Monument Grotesk | 400 | 20px | 1.4 | normal | Warm testimonial-slider quotation. |
| inline-lead | ABC Monument Grotesk | 500 | 20px | 1.4 | normal | Inline tooling invitation and emphatic support in dark chapters. |
| body | ABC Monument Grotesk | 400 | 16px | 1.4 | normal | Explanatory paragraphs and feature support. |
| body-medium | ABC Monument Grotesk | 500 | 16px | 1.4 | normal | Eyebrows, short inline links and author names. |
| action | ABC Monument Grotesk | 500 | 14px | 1.2 | normal | Button labels and navigation categories. |
| utility-action | ABC Monument Grotesk | 500 | 14px | 1 | normal | Compact utility labels within navigation actions. |
| footer-link | ABC Monument Grotesk | 400 | 14px | 1.4 | normal | Directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product and solution detail pages | question | ABC Monument Grotesk | 500 | 24px | 1.2 | normal | FAQ questions and narrative accordion headings. |
| company storytelling | recognition | ABC Monument Grotesk | 500 | 22.4px | 1.4 | normal | Centered award captions beneath small marks. |

**Notes:**

- Keep one family throughout. The hierarchy is created by the 64px → 32px → 24px → 20px steps, not extra display faces or heavy bold cuts.
- Headings share -0.02em tracking; body, action labels and questions retain normal tracking. Main headings use sentence case.
- Product-detail openings use the body recipe for their narrower support line; the default centered stage uses hero-support.
- Wrap headlines by meaning, using a balanced two-line silhouette rather than forced identical line lengths.

## Layout

**Density:** Airy section spacing with compact text and controls; content is grouped into generous panels rather than spread uniformly across the page.

### Spacing

**Spacing system:**

- **horizontal-step** 8px, horizontal — Dominant horizontal spacing increment; local component padding also uses 10px and 12px.

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gap and footer-link separation. |
| 12px | Resource title separation and tab-menu vertical gap. |
| 16px | Paired actions and small grid gaps. |
| 24px | Outer page gutters, card-grid gaps and grouped text spacing. |
| 32px | Opening content stack and service-grid gaps. |
| 40px | Proof cards, quotation side padding and closing-panel padding. |
| 48px | Inline tooling bar vertical padding. |
| 64px | Capability-stage side padding and closing heading-to-action gap. |
| 80px | Regular section top and bottom space; deep feature-card padding. |
| 120px | Dark service chapter top and bottom padding. |
| 160px | Major product and company-story chapter separation. |

### Containers and grids

- **outer-stage**: max width 1392px · side padding 24px. Inset cinematic and pastel bands; at 1440px they leave a slim white frame.
- **navigation-directory**: max width 1280px · side padding 24px. Centered header and footer content.
- **main-content**: max width 1184px · side padding 24px. Proof mosaic, capability module and standard chapter content.
- **detail-content**: max width 1040px · side padding 24px. Narrow product feature grids, resources and local conversion bands.
- **opening-copy**: max width 960px. Centered headline and support measure within the dark stage.
- **resource-grid**: 3 columns · gap 40px. 320px resource cards across the 1040px detail container.
- **directory-grid**: 6 columns · gap 16px. Six equal 200px footer columns within the 1280px container.
- **detail-grid** (only for product detail pages): 2 columns · gap 24px. Equal feature cards; a full-width card can alternate with paired cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | chapter-panels | 24px |
|  | action-capsules | 160px |
|  | dashboard-capsule | 100px |
|  | resource-images-and-team-cards | 12px |
|  | floating-ui | 21.6px |
| product detail pages | feature-cards | 16px |
| account infrastructure product pages | navy-quotation-inset | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| dark-glass | `0px 16px 32px 0px rgba(0, 0, 0, 0.5)` | Translucent service cards over black. |
| floating-ui | `0px 16px 32px 0px rgba(0, 0, 0, 0.1)` | Floating interface fragments in the lilac stage. |

### Surfaces

#### White canvas · level 0

**Use:** Connecting space between major bands.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** White surrounds the inset panels and carries the directory.

**Transfer:** Leave broad white breathing room between visually dense scenes.

#### Black stage · level 0

**Use:** Default opening and service chapters.

**CSS:** `background: #000000; color: #ffffff; border-radius: 24px; overflow: clip`

**Observed:** Contour art is clipped at rounded edges and remains subdued behind white text.

**Transfer:** Use a solid black base; make the scene dimensional through objects and thin lines, not a gray page wash.

#### Warm proof · level 1

**Use:** Proof and quotation cards.

**CSS:** `background: #f6f3ee; border-radius: 24px; padding: 40px`

**Observed:** Flat warm fill without a prominent outline or shadow.

**Transfer:** Reserve dimensional treatment for objects inside the panel.

#### Lilac capability stage · level 1

**Use:** Interactive capability chapter.

**CSS:** `background: #f6f1fe; border-radius: 24px; overflow: clip`

**Observed:** Purple labels, faint purple contours and white floating fragments share a broad field.

**Transfer:** Keep the pale background continuous across the whole module.

#### Mint tooling stage · level 1

**Use:** Developer invitation and tooling demonstration.

**CSS:** `background: #ebfef6; border-radius: 24px; overflow: clip`

**Observed:** Thin green contours sit behind text; dark technical media anchors the opposite side.

**Transfer:** Use mint to frame a practical product demonstration rather than general promotion.

#### Peach invitation · level 1

**Use:** Default closing call.

**CSS:** `background: #fff2ed; border-radius: 24px; padding: 40px; overflow: clip`

**Observed:** Orange fine-line rings are oversized and cropped above and below the panel.

**Transfer:** Keep the invitation simple enough that the line artwork remains visible.

#### Dark glass · level 2

**Use:** Service cards on the Black stage.

**CSS:** `background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 24px; backdrop-filter: blur(32px); box-shadow: 0px 16px 32px 0px rgba(0, 0, 0, 0.5)`

**Observed:** Low-contrast transparency preserves a trace of the contour background.

**Transfer:** Use only over dark artwork; do not turn all light cards into glass.

#### Near-white feature · level 1

**Only for:** product and solution detail pages

**Use:** Detailed capability cards and resource promotions.

**CSS:** `background: #fafafa; border-radius: 16px`

**Observed:** Feature tiles use 80px padding and large illustrative headroom; wider resource promotions use 24px corners.

**Transfer:** Create depth with a restrained illustration instead of a heavy panel shadow.

#### Recognition wash · level 1

**Only for:** company storytelling

**Use:** Recognition panel.

**CSS:** `background: #eef1ff; border-radius: 24px; padding: 80px`

**Observed:** Three centered recognition items share one surface.

**Transfer:** Present independent endorsements with equal visual weight.

#### Cobalt chapter · level 1

**Only for:** account infrastructure product pages

**Use:** Dark product cards and local invitation.

**CSS:** `background: #0c112a; color: #ffffff; border-radius: 16px; padding: 40px`

**Observed:** Category blue accents and pale periwinkle quotation text extend the black-stage vocabulary; local conversion band uses 24px corners.

**Transfer:** Use one coherent blue family throughout this product variant.

#### Emerald invitation · level 1

**Only for:** issuing product pages

**Use:** Local product conversion band.

**CSS:** `background: #00291a; color: #ffffff; border-radius: 24px; padding: 40px; overflow: clip`

**Observed:** Bright emerald action and emerald line art sit on forest green.

**Transfer:** Keep this local product variant distinct from the orange global action system.

## Components

### Navigation

**Use:** Global orientation above the main scene.

**CSS:** `background: #ffffff; height: 65px; padding: 0px 24px; display: flex; align-items: center`

**Text style:** `action` — ABC Monument Grotesk 500 · 14px/1.2

**Observed:** A compact mark and four categories group at left; text contact and a dark Dashboard capsule align right inside the navigation-directory container. Category toggles have 24px vertical and 16px horizontal padding. Full-bleed dark product openings reverse the navigation to white on black.

**Transfer:** Keep navigation visually quieter than the hero.

### Primary button

**Use:** Main conversion.

**CSS:** `background: #ff6600; color: #ffffff; border: 1px solid #ff6600; border-radius: 160px; height: 32px; padding: 10px 24px; display: flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — ABC Monument Grotesk 500 · 14px/1.2

**Observed:** Short label followed by a right arrow. The rendered capsule is compact. A blue local action belongs to account infrastructure bands, and an emerald local action belongs to issuing bands; global hero actions remain orange.

**States:** Declared: hover outline 0px; active outline 0px. Focus-visible treatment is not specified.

### Secondary button

**Use:** Companion exploration action over dark artwork.

**CSS:** `background: rgba(255, 255, 255, 0.2); color: #ffffff; border: 1px solid transparent; border-radius: 160px; height: 32px; padding: 10px 24px; backdrop-filter: blur(32px); display: flex; align-items: center; gap: 8px`

**Text style:** `action` — ABC Monument Grotesk 500 · 14px/1.2

**Observed:** Sits before the primary action in the centered opening pair. Light-background versions are white with a 1px 10% black border; inline documentation actions remove the fill.

**States:** Declared: hover outline 0px; active outline 0px. Focus-visible treatment is not specified.

### Dashboard capsule

**Use:** Utility destination in navigation.

**CSS:** `background: #261e12; color: #f6f3ee; border: 1px solid #261e12; border-radius: 100px; height: 32px; padding: 10px 16px; display: flex; align-items: center; justify-content: center`

**Text style:** `utility-action` — ABC Monument Grotesk 500 · 14px/1

**Observed:** No trailing arrow; visually separated from the unfilled contact link.

**States:** Declared: hover outline 0px and box-shadow none; active outline 0px. Focus-visible treatment is not specified.

### Proof tile

**Use:** Concise trust statements and quantitative proof.

**CSS:** `background: #f6f3ee; border-radius: 24px; padding: 40px; position: relative; overflow: clip`

**Text style:** `card-heading` — ABC Monument Grotesk 500 · 24px/1.2 · tracking -0.02em

**Observed:** Headline is pinned near the upper left; supporting marks or a large concise metric occupy the lower area. Alternating wide and narrow tiles form a two-row mosaic. One metric is treated as a 24px title rather than an enormous counter; thin contour art enters from a corner.

**Transfer:** Use actual proof and small supporting marks, preserving uneven tile widths.

### Glass service card

**Use:** Explain modular service choices on black.

**CSS:** `background: rgba(255, 255, 255, 0.1); color: #ffffff; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 24px; padding: 40px 38.4px; display: flex; flex-direction: column; gap: 24px; backdrop-filter: blur(32px); box-shadow: 0px 16px 32px 0px rgba(0, 0, 0, 0.5)`

**Text style:** `item-heading` — ABC Monument Grotesk 500 · 20px/1.2 · tracking -0.02em

**Observed:** Small warm-toned icon precedes the title; descriptive paragraph and an unobtrusive learn-more action follow. Two broad cards sit above three smaller ones.

**States:** Declared: hover background-color rgba(255, 255, 255, 0.2) and outline 0px; active outline 0px. Focus-visible treatment is not specified.

**Transfer:** Use the larger cards for primary choices and smaller ones for supporting services.

### Capability tabs

**Use:** A single large interactive feature story.

**CSS:** `background: #f6f1fe; border-radius: 24px; padding: 0px 64px; display: grid; grid-template-columns: minmax(1px, 1fr) minmax(1px, 1fr) minmax(1px, 0.8fr); gap: 16px; align-items: center; overflow: clip`

**Text style:** `tab-label` — ABC Monument Grotesk 500 · 24px/1.4 · tracking -0.02em

**Observed:** Left text contains a compact heading, paragraph, three checks and white action; center holds a stack of floating interface fragments; the vertical menu is right-aligned. Purple active label is full strength and inactive labels are half opacity. The module is 500px tall at desktop.

**Transfer:** Let each tab replace the story and illustration together; do not place all detail paragraphs on screen at once.

### Testimonial card

**Use:** Human proof in a horizontally overflowing carousel.

**CSS:** `background: #f6f3ee; border-radius: 24px; padding: 32px 40px 40px; max-width: 576px`

**Text style:** `quote` — ABC Monument Grotesk 400 · 20px/1.4

**Observed:** Customer mark at top, quotation below, then circular avatar and name/role at bottom. Cards are separated by 64px, with the next card partially visible. The introduction is a separate narrow left block; arrow controls sit below.

**Transfer:** Keep quotations readable and attributed; use the quote as the main content rather than a giant decorative quotation mark.

### Resource card

**Use:** Editorial proof and further reading.

**CSS:** `display: flex; flex-direction: column; max-width: 320px; overflow: clip`

**Text style:** `item-heading` — ABC Monument Grotesk 500 · 20px/1.2 · tracking -0.02em

**Observed:** A 320px by 169px rounded image leads, with 12px corners and cover fitting. Title follows after 12px; a subdued metadata row follows beneath. Three cards share a row, with a centered white outlined Read more capsule below the collection.

**Transfer:** Use editorial thumbnails with the same contour language or restrained photography; keep the surrounding card unboxed.

### Footer directory

**Use:** Structured navigation and legal closure.

**CSS:** `background: #ffffff; padding: 24px; color: #888888`

**Text style:** `footer-link` — ABC Monument Grotesk 400 · 14px/1.4

**Observed:** Six columns within the navigation-directory container; small black group labels above gray links spaced by 8px. A lower strip places the small mark left, subdued legal copy centrally and social glyphs right. No dark footer slab.

**States:** Declared: hover color black and outline 0px; active outline 0px. Focus-visible treatment is not specified.

**Transfer:** Use the actual information architecture while retaining the modest scale and white background.

### Feature card

**Only for:** product detail pages

**Use:** Detailed capability explanation.

**CSS:** `background: #fafafa; border-radius: 16px; padding: 80px; display: flex; flex-direction: column; align-items: center`

**Text style:** `card-heading` — ABC Monument Grotesk 500 · 24px/1.2 · tracking -0.02em

**Observed:** Large illustration above a left-aligned heading, gray body paragraph and small Read more link with plus sign. Equal-width paired cards alternate with wider horizontal cards. Illustrations are compact white interface diagrams or isolated physical objects, not full application screens.

**Transfer:** Create one simple visual idea for each capability.

### FAQ row

**Only for:** product and solution detail pages

**Use:** Resolve purchase and implementation objections.

**CSS:** `border-bottom: 1px solid #e8e8e8; padding-bottom: 26px; position: relative; overflow: hidden`

**Text style:** `question` — ABC Monument Grotesk 500 · 24px/1.2

**Observed:** Question and orange downward chevron share a full-width toggle. Later rows add 40px above the heading; toggle has 14px below. A 16px body answer sits underneath when expanded. The section title occupies the narrow left column and questions occupy 640px or 736px at right.

**Transfer:** Use native accessible disclosure semantics; keep the visual row flat and unboxed.

## Imagery and graphics

### Contour sculpture

**Use:** Required connective artwork across the opening, at least one capability or proof chapter, and a conversion invitation.

**Observed:** Thin nested loops are offset and stretched into flowing toroidal bands. On black they resemble low-lit bronze wire; on pastel fields they are faint tonal lines. They extend well outside their panel and never become a dense patterned texture behind body copy.

**Transfer:** Recreate the line system with different loop geometry tailored to the new product. When no physical product exists, a single dimensional contour sculpture is the minimum main artwork.

**Build:** Create an SVG in a 1440px-wide viewBox. Draw 24–40 closed cubic-Bezier loops with no fill, each varying its horizontal radius and center; use a 1px stroke. Rotate the group diagonally for the opening and let it overscan the panel by 200px. Use rgba(238,192,122,0.2) over black, rgba(92,41,153,0.12) over lilac, or rgba(0,204,136,0.14) over mint. Keep text on a separate foreground layer. For the peach call use orange at roughly 0.25 alpha, nested ellipses with centers progressively shifted toward the right-hand action.

### Dark product procession

**Use:** Default opening main artwork and large service-chapter object.

**Observed:** A diagonal procession of charcoal cards moves from lower left toward upper right behind the central copy. Objects have nearly black faces, thin reflective edges and fine loop graphics; black-on-black staging keeps them subordinate to white type. A separate service scene uses a large cropped black phone with a gold card, angled in perspective from the upper right.

**Transfer:** Replace cards with the new product's meaningful object or a dimensional representation of its workflow. Minimum version: several dark rounded planes, perspective-transformed and edge-lit, floating above the contour sculpture.

**Build:** Arrange 5–8 dark rounded rectangles in an ascending diagonal track with rotate(-35deg) and perspective transforms. Add thin rgba(255,255,255,0.15) edge highlights and faint contour lines on their faces; reduce face contrast and clip the procession at the panel edge. Keep the brightest detail away from the headline.

### Floating interface fragments

**Use:** Capability tabs and product feature illustrations.

**Observed:** Small white status lists, one metric strip and a bar-chart strip stack over lilac, with soft downward shadows and thin edges. Other feature cards use sparse transaction slips, branching diagrams and arrows with selective green, orange or purple detail. Tooling chapters use dark code and dashboard panels, overlapping and cropped at the right edge of a mint field.

**Transfer:** Show only enough interface to explain one capability. Use genuine product labels and diagram connections; keep the fragment composition separate from the marketing typography system.

**Build:** Stack three white panels of unequal widths around 280px–340px, with 12px vertical gaps, a 1px rgba(0,0,0,0.1) border, 21.6px corners and 0px 16px 32px rgba(0,0,0,0.1) shadow. Keep their internal UI minimal; back them with one oversized contour loop rather than a screenshot wall.

### Orange atmospheric people

**Only for:** solution campaign openings

**Use:** Warm photographic alternative to the default black object stage.

**Observed:** Indistinct people in a shared working environment sit behind a strong orange veil, with milky bloom at the left edge and soft peach haze at the bottom. White text is left-aligned; the scene fills a 1392px by 597px rounded panel.

**Transfer:** Use low-detail contextual human photography with warm diffusion and ample text-negative space. Match the soft glow; exact stops are not essential.

**Build:** Place a full-cover photograph under a translucent orange layer, then add blurred white radial blooms at the left edge and a peach linear fade rising from the bottom. Keep people as silhouettes rather than crisp portraits; use a white primary capsule in this warm variant.

### Context photography tiles

**Only for:** solution detail pages

**Use:** Application scenarios and a large accordion-side image.

**Observed:** Photography shows monumental concrete architecture, a plane wing through a window, night-lit infrastructure, blurred pedestrian reflections and warehouse racks. Images are full-bleed within rounded tiles; application tiles carry bottom-left white copy over a darkened lower area. Unequal widths alternate across two rows.

**Transfer:** Choose real environments that imply the outcome, not literal people pointing at screens. Preserve cinematic lighting, strong geometry and restrained overlays.

### Human portraits

**Only for:** company storytelling

**Use:** Leadership directory.

**Observed:** Small square portraits on warm pale backgrounds sit to the left within near-white horizontal cards. Names, muted roles and a small social icon occupy the right. A three-column grid uses 20px gaps.

**Transfer:** Use consistent head-and-shoulder crops and soft neutral lighting; preserve the compact, directory-like scale rather than a large lifestyle gallery.

### Icons

**Observed:** Action arrows are 14px filled SVGs aligned after the label with 8px gaps. Capability checks are 18px purple circles; service icons are around 20px and warm-toned. Product-detail chapters use small category-colored symbols; FAQ chevrons are orange. Social icons are small gray silhouettes.

**Transfer:** Use a coherent simple SVG set with crisp filled arrows and restrained outlined feature symbols. Keep icons small enough to read as navigation or notation, not decorative badges.

## Section recipes

How recurring sections are built.

### First screen: Dark procession opening

**Observed:** A 65px white Navigation sits above a black stage inset 24px from both sides, 1392px wide and 804px tall at desktop, with 24px corners. From back to front: black fill, broad bronze contour sculpture, dim diagonal object procession, then centered white copy and actions. The 64px display headline occupies about two thirds of the page width and balances over two lines within a 960px measure. A two-line 24px support line follows after 32px, then the Secondary button and Primary button after another 32px, separated by 16px. The scene is centered vertically and the objects cross behind it toward opposing corners. Within the first 900px the navigation, full headline, support, both actions and almost the whole object stage are visible; customer proof begins below.

**Transfer:** Create equally strong depth using the Contour sculpture and one product-relevant dimensional motif; if no product object exists, use dark planes representing modules. Other opening types retain the display recipe: company storytelling uses black text over very pale loops fading to white; solution campaigns use the Orange atmospheric people treatment with left-aligned copy; full-bleed product detail pages use a category pill, black navigation, 16px support and a single orange action, then continue into proof within the same dark field.

**Avoid:** Do not use a conventional white split hero with a small dashboard on the right, a giant orange fill, or busy high-contrast objects crossing through the text.

**Text style:** `display` — ABC Monument Grotesk 500 · 64px/1 · tracking -0.02em

### Heading and supporting pair

**Observed:** Section-heading appears centered above grids or aligned left in split chapters. Body support follows at 24px where present. Company-story sections add a body-medium eyebrow 16px above the heading; a separate right column holds longer prose. Regular sections use 80px vertical space, major chapters 160px.

**Transfer:** Choose either concise centered framing or a left-title/right-explanation composition according to content length.

**Text style:** `section-heading` — ABC Monument Grotesk 500 · 32px/1.2 · tracking -0.02em

### Proof mosaic

**Observed:** A centered heading and horizontally distributed customer marks introduce a Warm proof mosaic in the main-content container. Two rows of 220px-high Proof tiles have 24px gaps; the wider tile changes sides between rows. Marks and short metrics are embedded inside the tiles rather than isolated in a large-number strip.

**Transfer:** Mix endorsement, reliability and operational proof in a deliberately asymmetric layout.

### Capability theater

**Observed:** A centered heading sits above Capability tabs. The lilac module gives separate zones to explanation, interface fragments and the right-aligned vertical menu. Pale contours wrap around the center illustration; a small circular progress indicator sits near the lower right.

**Transfer:** Give a complex product a limited set of clearly named capabilities, each with one compact illustration.

### Dark service chapter

**Observed:** Black stage spans nearly the page width, with 120px vertical padding. Upper-left heading and support face a large cropped object at upper right. A second centered heading introduces Glass service cards below, with 32px gaps. Contour sculpture binds both parts of the chapter.

**Transfer:** Use this dramatic change of material for implementation or service complexity, not another identical feature grid.

### Testimonial rail

**Observed:** A narrow left introduction faces a horizontal rail of Testimonial cards. One full 576px card and part of the next are visible; previous and next arrows below preserve the horizontal reading direction. The rail is surrounded by white space.

**Transfer:** Use two or more genuinely distinct attributed stories; retain the invitation to continue horizontally.

### Tooling invitation

**Observed:** Mint tooling stage has a left-aligned 32px heading, 16px paragraph and two small arrow links. Dark code and dashboard media overlap on the right and clip beyond the panel. A compact related variant is a 124px-high mint inline bar with one 20px lead and three links.

**Transfer:** Show an actionable technical entry point such as documentation, a test environment or an integration example.

### Closing contour invitation

**Observed:** Peach invitation is inset 24px, 282px high and surrounded by 24px top and bottom space. One section-heading and Primary button share a centered horizontal row with a 64px gap. Orange contour rings sweep across the panel and converge near the action. Footer directory follows. Product-detail variants place a shorter 1040px by 157px navy or forest invitation before resources and FAQ; those pages then end directly in the white directory.

**Transfer:** Carry the contour device into a final invitation wherever conversion makes sense; use a local dark band for detailed product pages without forcing another call after the FAQ.

**Text style:** `section-heading` — ABC Monument Grotesk 500 · 32px/1.2 · tracking -0.02em

### Detail capability chapters

**Only for:** product detail pages

**Observed:** A centered section-heading introduces Near-white feature cards in a 1040px container. Account-oriented pages use a two-column grid with 24px gaps; issuing pages mix wide text-and-illustration cards with paired smaller cards. Oversized faint contour art flows behind the whole collection, including white interstitial space.

**Transfer:** Select the grid according to the amount of explanation; keep each visual focused on one capability.

### Nested quotation

**Only for:** account infrastructure product pages

**Observed:** An 1184px-wide Warm proof panel contains a large customer mark on the left and a navy quotation inset on the right. The inset has 8px corners, 40px padding, a 24px/1.4 periwinkle quotation and a small avatar attribution below.

**Transfer:** Use for a deeper technical endorsement that merits more room than a carousel card.

**Text style:** `hero-support` — ABC Monument Grotesk 400 · 24px/1.4

### Editorial bridge

**Only for:** product and solution detail pages

**Observed:** A near-white rounded promotion pairs a tangible report cover on the left with a small category pill, 24px title, 16px summary and Download arrow link on the right. Fine contours back the cover. A later Resource card row uses three columns and 40px gaps.

**Transfer:** Use a useful guide, research artifact or practical resource to bridge product education and conversion.

### Narrative accordion

**Only for:** solution detail pages

**Observed:** A large architectural photograph occupies one side; four 24px accordion headings stack on the other. The expanded heading has an orange top rule, a short paragraph and orange bullet points; inactive headings and rules are gray.

**Transfer:** Pair a contextual image with a small set of outcome explanations rather than a long list of disconnected claims.

**Text style:** `question` — ABC Monument Grotesk 500 · 24px/1.2

### Objection handling

**Only for:** product and solution detail pages

**Observed:** Left-aligned section title occupies roughly one third of the layout while the FAQ row stack occupies the wider right side. The gap is 80px. Closed rows show only their 24px question and orange chevron; thin rules create rhythm without card backgrounds.

**Transfer:** Use customer questions that resolve remaining barriers; reveal answers on demand.

**Text style:** `question` — ABC Monument Grotesk 500 · 24px/1.2

### Company recognition and people

**Only for:** company storytelling

**Observed:** A long two-column narrative is followed by Recognition wash, a separate row of monochrome investor marks, and a three-column compact portrait directory. Recognition captions use 22.4px medium text. The ending returns to the peach contour invitation with a recruiting action and then the white Footer directory.

**Transfer:** Use the format for institutional credibility and people, not as extra product feature cards.

**Text style:** `recognition` — ABC Monument Grotesk 500 · 22.4px/1.4

## Page flow

**Storyline:** Promise → credibility → capabilities made tangible → service or application depth → human or editorial proof → objection handling or practical entry point → invitation and directory.

### Broad platform marketing

1. **Promise** — Centered dark object stage with a two-action pair.
2. **Credibility** — Customer marks and asymmetric warm proof tiles.
3. **Capability demonstration** — Mint inline developer links and a lilac interactive theater.
4. **Service depth** — Black object chapter with translucent modular cards.
5. **Human proof** — Warm quotation rail.
6. **Practical entry point** — Mint technical-media invitation.
7. **Closing call** — Peach contour invitation and white six-column directory.

**Transfer:** Alternate dramatic dark scenes with bounded pastel chapters and white pauses; choose only the proof and demonstrations relevant to the new platform.

### Company credibility and recruiting

1. **Promise** — Centered black headline on pale contour artwork that fades into white.
2. **Origin and purpose** — Short left heading and long right-hand narrative.
3. **Independent credibility** — Pale-blue recognition panel and separate monochrome marks.
4. **Human proof** — Compact three-column portrait directory.
5. **Closing call** — Peach contour recruiting invitation and white directory.

**Transfer:** Favor readable story and compact people over dark product theater.

### Explain a new application category

1. **Promise** — Orange atmospheric photography with a left-aligned display headline.
2. **Credibility** — Customer-mark row.
3. **Benefits** — Three soft cards followed by image-and-accordion explanation.
4. **Capability depth** — Near-white technical summary with category rules and small icons.
5. **Applications** — Alternating wide and narrow photographic scenario tiles.
6. **Education** — Report promotion and relevant resource cards.
7. **Objection handling** — Wide FAQ stack beside a small section title.
8. **Closing call** — Peach contour invitation and white directory.

**Transfer:** Use context imagery to make a new category legible while preserving compact text and clear technical boundaries.

### Deep technical product explanation

1. **Promise** — Full-bleed black and cobalt contour opening with a category pill.
2. **Outcome proof** — Three navy benefit cards continue the dark field.
3. **Capability chapters** — Two-by-two near-white illustrated feature grid.
4. **Human proof** — Warm outer quotation with navy inset.
5. **Education** — Tangible report-cover promotion.
6. **Conversion** — Short navy contour band with a blue capsule.
7. **Further reading** — Three unboxed resource cards.
8. **Objection handling and closure** — FAQ rows lead directly into white directory; no second terminal conversion panel.

**Transfer:** Use a scoped accent family for a deep infrastructure product, while keeping the overall black-to-white transition.

### Product-led growth and capability explanation

1. **Promise** — Full-bleed black opening, emerald category pill and orange demo action.
2. **Product demonstration** — Centered phone in front of a wide horizontal object procession.
3. **Benefits** — Three concise icon-led columns on black.
4. **Capability chapters** — Wide and paired near-white cards with sparse UI diagrams.
5. **Conversion** — Forest contour invitation with emerald capsule.
6. **Further reading** — Three resource cards.
7. **Objection handling and closure** — FAQ then white directory, without a peach terminal invitation.

**Transfer:** Let physical product presentation lead, then explain controls and implementation through small diagrams rather than more hero renders.

## Writing

Confident, technically literate and reassuring. Complex infrastructure is translated into direct benefits without losing specific mechanisms; warmth comes from conversational turns rather than jokes.

**Do not copy:** Do not reuse Lithic or related brand names, customer logos, artwork, executive identities, testimonials, compliance certifications, uptime numbers, transaction volumes, funding claims or proprietary product claims. Examples illustrate voice, not facts available to another product.

- **Addressing the reader:** Address the reader as you and your team. The company speaks as we in origin stories and practical explanations, while headlines usually foreground the reader's outcome.
- **Rhythm:** Headlines are compact sentence-case promises, often 5–12 words. Support usually fits one or two sentences; technical paragraphs may be longer. Short parallel clauses supply momentum without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Combine a concrete capability with an outcome or reassurance. | 5–12 words | “Programmable card issuing and money movement”<br>“Instantly issue cards and confidently power growth” |
| Supporting line | Explain the benefit through concrete operating advantages. | 10–25 words | “Launch, manage, and scale your custom card program.”<br>“Manage accounts and settlement on a single platform that keeps balances consistent and reporting clean.” |
| Section headline | Name the reader's problem, then defuse it with a plain assurance. | 6–13 words | “Payments are complex. Your programs don’t need to be.”<br>“Fast, flexible, and fool-proof? Not an issue.” |
| Capability description | Lead with a command or outcome; follow with the mechanism. | 1–3 sentences | “Set the rules. Define the limits. Enforce them in real time.” |
| Primary action | Brief direct verb phrase; no aspirational slogan. | 2–3 words | “Contact us”<br>“Request a demo”<br>“Explore Sandbox” |
| Closing invitation | Ask whether the reader is ready, or invite a concrete next step. | 6–11 words | “Ready to build on infrastructure you can count on?” |

**Words and phrasing to use:** build; launch; scale; control; reliable; real time; flexible; your team; peace of mind; source of truth

**Avoid:** revolutionary magic; game-changing ecosystem; effortless everything; unlimited guarantees; excessive AI superlatives

**Rules:**

- Pair a broad promise with a specific mechanism in the next paragraph.
- Use parallel verbs to express operational momentum.
- Name technical details only where they clarify a benefit or boundary.
- Keep actions literal and brief; use documentation and implementation language where appropriate.
- Treat reassurance as earned by proof, not by repeated adjectives.

## Do's and Don'ts

### Do

- Use 64px medium display type with -0.02em tracking and a 32px section-heading counterpart.
- Preserve the 24px white frame around major rounded stages.
- Keep contour lines fine and subordinate to type, with nested loops rather than filled blobs.
- Use 32px capsules and 14px labels for conversion actions.
- Give warm proof cards 40px padding and a 24px radius.
- Let dark service cards retain a 1px translucent edge and 32px backdrop blur.
- Use 80px regular section space and 160px for major chapter transitions.
- Place resource titles below 12px-rounded media instead of enclosing the whole resource in another panel.

### Don't

- Do not add a second serif or monospace marketing font; technical media can contain code without changing the page typography.
- Do not make section headings nearly as big as the 64px hero; the deliberate 32px step matters.
- Do not recolor every card orange; the default orange is an action accent against pale fields.
- Do not add broad drop shadows to flat warm proof tiles; reserve shadows for floating fragments and glass.
- Do not turn the modest 24px proof metric into an oversized dashboard counter.
- Do not combine cobalt and emerald category accents on an ordinary new page; they belong to separate product variants.
- Do not add opaque white card fills over the dark service scene; preserve the 10% white glass.
- Do not finish with a black multi-column footer or a giant wordmark; the directory is small, gray and white-backed.

## Motion and responsive

### Motion

**Observed:**

- Customer-logo marquees declare a 45s linear infinite horizontal animation.
- Footer links declare opacity 0.2s transitions.
- Navigation toggles declare color and box-shadow transitions of 0.3s with cubic-bezier(0.215, 0.61, 0.355, 1).
- Capability menu labels declare opacity 0.25s; service cards declare background-color 0.2s.

**Transfer:**

- Use slow continuous movement for a logo rail and short state changes for capability navigation; keep the central promise stable while artwork supplies movement.

**Unknown:**

- Object-scene animation timing, tab autoplay duration, accordion animation timing and scroll-reveal choreography are unspecified.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 768px, 991px and 1470px.
- Resource-list classes identify a mobile horizontal-scroll treatment.

**Transfer:**

- On narrow layouts, preserve the inset rounded-stage idea, keeping type above dim contour art and allowing the diagonal object procession to clip.
- Stack capability explanation, illustration and tab navigation without losing the pale continuous backdrop; retain horizontally scrollable resource and quotation rails where useful.

**Unknown:**

- Exact mobile type sizes, gutters, navigation behavior and panel heights are unspecified; narrow-screen composition guidance is a recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
