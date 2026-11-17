# Stykka — lived-in modular modernism

## Overview

A photographic, Scandinavian editorial style that feels practical, tactile and inhabited rather than showroom-perfect. White and black framing, tightly set grotesk typography and small utilitarian labels leave room for sunlit wood, metal and muted color in the imagery. It suits considered physical products, systems and services with tangible evidence of craft; text is compact while images occupy generous space.

### Essentials

- The product is introduced as a place to inhabit, not a cutout to admire: a full-width photographic opening about 883px tall, with white 46px medium-weight type and a small outlined action anchored at the lower left.
- Headlines are compressed, not heavy: Inter 500, 46px/1 with -1.9px tracking for the opening and 30px/1.05 with -1.3px tracking for section leads; the main promise stays subordinate to the photograph.
- Controls have two distinct geometries: an 8px rounded outline over opening photography, versus 42px tall contact pills with 100px radii and a contrasting 40px circular arrow endcap.
- The graphic framework is monochrome: white occupies the ordinary page canvas, black supplies type and 1px rules, and color belongs to large photographs rather than marketing fills. A black photographic catalog is a separate editorial variant.
- Photo essays double as navigation and proof: 316×401px portrait images in four columns with 25px gaps, plus taller image links in three columns with 15px gaps and white 24px labels at the bottom.
- Small captions make the page feel like an architectural specification: 14px uppercase labels with 0.3px tracking sit beneath a 1px rule, followed by compact 14px/1.25 explanations. Every new landing page needs this image–rule–label device as well as the immersive opening; for intangible products use photographed work situations and concrete process artifacts.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, background, link | Primary type and thin rules; also the full canvas of the photographic catalog. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Carousel fill | `#e8e8ed` | `--color-control` | surface, action | Circular testimonial controls. |
| Quote gray | `#515154` | `--color-secondary` | text | Testimonial support paragraphs. |
| Carousel icon | `#6e6e73` | `--color-control-icon` | text, accent | Arrow marks inside pale carousel controls. |
| Footer gray | `#999999` | `--color-footer-muted` | text | Visible result of black text at 0.4 opacity over white; footer labels and provenance line. Reverse by using white at 0.4 opacity over black. |
| Proof gray | `#b8b8b8` | `--color-muted` | text | Low-emphasis social-proof heading and pricing qualifiers. |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Default canvas, reversed text over photography, white contact controls and inputs. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| contact and inquiry sections | Blue-black action ink | `#05080c` | `--color-action-ink` | text, action, surface | Contact typography, dark buttons and arrow endcaps. |
| pricing comparisons | Pricing outline | `#222222` | `--color-outline` | border | Thin pricing-card perimeter. |
| photographic catalogs | Gallery gray | `#808080` | `--color-gallery-copy` | text | Visible white at 0.5 opacity over black for project descriptions. |
| company stories | Aside label gray | `#8f8f8f` | `--color-aside-label` | text | Small label introducing the muted story aside. |
| photographic catalogs | Gallery caption gray | `#999999` | `--color-gallery-caption` | text | Visible white at 0.6 opacity over black for numbered image captions. |
| contact and inquiry sections | Contact gray | `#a3a3a3` | `--color-contact-muted` | text | Contact support lines. |
| company stories and supporting downloads | Aside gray | `#a6a6a6` | `--color-aside-muted` | text | Muted company-story aside and document-download introduction. |
| contact and inquiry sections | Contact panel | `#f5f5f5` | `--color-panel` | surface | Flat contact and form backgrounds. |

## Typography

- **Inter** — Default headings, body, labels and navigation. Compact contemporary grotesk, mostly medium headings and regular text. Font stack: "Inter", Arial, sans-serif.
- **Geist** (only for contact sections and professional benefit cards) — Contact headings, actions, field labels and benefit titles. Clean utilitarian grotesk with tight negative tracking. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Geist", Arial, sans-serif.
- **Switzer** (only for photographic catalogs) — Catalog introduction, project headings and descriptions. Medium-weight neo-grotesk with slightly softer editorial texture. If unavailable, use **Inter**. Use weight 500 with -0.02em tracking. Font stack: "Switzer", "Inter", Arial, sans-serif.
- **Fragment Mono** (only for photographic catalogs) — Numbered image identifiers. Small uppercase monospace captions. Font stack: "Fragment Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 500 | 46px | 1 | -0.0402em | Lower-left opening title; also short page titles. |
| heading | Inter | 500 | 30px | 1.05 | -0.0417em | Section leads, large introduction paragraphs and testimonial lead. |
| tile-label | Inter | 500 | 24px | 1.2 | -0.0417em | White text at the lower edge of photographic navigation tiles. |
| heading-sm | Inter | 500 | 22px | 1.1 | -0.0227em | Proof headings and smaller card titles. |
| quote-support | Inter | 400 | 18px | 1.6 | -0.01em | Relaxed support below a testimonial lead. |
| footer-line | Inter | 500 | 16px | 1 | -0.0375em | Muted origin or craft statement beneath the footer identity. |
| eyebrow | Inter | 500 | 14px | 1.1 | 0.021em, uppercase | Image-card labels and introduction markers. |
| body | Inter | 400 | 14px | 1.25 | -0.036em | Descriptions beneath images and compact editorial paragraphs. |
| link | Inter | 500 | 14px | 1.25 | -0.036em | Navigation and footer links; opening outline action. |
| footer-label | Inter | 500 | 11px | 1 | normal, uppercase | Footer column categories. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| photographic catalogs | catalog-intro | Switzer | 500 | 29px | 1.1 | -0.02em | Narrow, multi-line opening statement. |
| contact and inquiry sections | contact-heading | Geist | 500 | 28px | 1.2 | -0.04em | Form and direct-contact titles. |
| company stories and supporting downloads | aside | Inter | 500 | 25px | 1 | -0.05em | Muted secondary statement beside larger black editorial paragraphs. |
| professional benefit cards | benefit-heading | Geist | 500 | 25px | 1.1 | -0.04em | Centered benefit title over blurred photographic material. |
| photographic catalogs | catalog-heading | Switzer | 500 | 24px | 1.1 | -0.02em | Project title and location. |
| contact and inquiry sections | contact-support | Geist | 400 | 18px | 1.2 | -0.02em | Muted support below contact titles. |
| professional benefit cards | benefit-support | Inter | 400 | 17px | 1 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Centered explanation beneath a benefit title, white at 0.65 opacity. |
| contact and inquiry sections | contact-action | Geist | 500 | 16px | 1.2 | -0.02em | Contact pills, submit labels and field labels. |
| photographic catalogs | catalog-body | Switzer | 500 | 14px | 1.1 | -0.02em | Muted project context. |
| company stories | aside-label | Inter | 500 | 12px | 1.1 | 0.025em, uppercase | Gray label above a story aside. |
| photographic catalogs | image-id | Fragment Mono | 400 | 11px | 1 | normal, uppercase | Project name and two-digit image index beneath each picture. |

**Notes:**

- Keep negative tracking even on compact 14px text; the distinctive density is not achieved by bold weights.
- Large explanatory passages use the same 30px recipe as section titles rather than a separate oversized display scale.
- The default is Inter. Geist and Switzer belong to their named functional or editorial variants, not arbitrary font mixing.

## Layout

**Density:** Airy image-led sections with compact text blocks; large photography does more work than long copy.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Rule-to-label gap and gallery image-to-caption gap. |
| 10px | Eyebrow-to-heading, small title-to-copy gap and catalog column gutter. |
| 15px | Photo navigation gutters and label-to-body separation. |
| 20px | Photo-to-caption block, small card padding and three-column content gutters. |
| 25px | Four-column gutters and section heading-to-image gap. |
| 30px | Contact panel padding and action separation. |
| 40px | Standard desktop side inset and footer top padding. |
| 50px | Default landing-page content inset and typical section top spacing. |
| 60px | Editorial split-section padding. |
| 90px | Catalog project chapter separation. |
| 100px | Breathing room before the residential introduction. |

### Containers and grids

- **landing-container**: max width 2000px · side padding 50px. Default landing content, fluid across the viewport within broad outer margins.
- **four-image-grid**: 4 columns · gap 25px. Equal-width portrait proof and process cards, 316px wide within the landing layout.
- **photo-navigation-grid**: 3 columns · gap 15px. Equal portrait links, approximately 437×594px at desktop.
- **introduction-measure**: max width 681px. Left-aligned introductory heading-sized paragraph, leaving the other half open.
- **contact-measure**: max width 1120px. Centered contact stack and large embedded video.
- **detail-container** (only for audience and product detail pages): max width 2000px · side padding 40px. Slightly wider detail-page content and footer alignment.
- **three-content-grid** (only for pricing and technical proof sections): 3 columns · gap 20px. 440px wide comparison or technical-media cards.
- **catalog-grid** (only for photographic catalogs): 3 columns · gap 10px · side padding 65px. 430px-wide images alternating square and portrait proportions, with a taller middle image.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | proof-images | 8px |
|  | image-links | 10px |
|  | carousel-controls | 20px |
| contact and inquiry sections | contact-panels | 10px |
| inquiry forms and professional benefit cards | forms-and-benefits | 16px |
| contact and inquiry sections | contact-pills | 100px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default marketing surface.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Continuous white ground with almost no raised-card treatment.

**Transfer:** Use layout, images and small rules to organize information rather than colored containers.

#### Quiet logo backing · level 1

**Use:** Subtle backing for proof marks.

**CSS:** `background: rgba(255, 255, 255, 0.03); border-radius: 16px; backdrop-filter: blur(6px)`

**Observed:** Effect is almost invisible on white; the gray logos carry the visual weight.

**Transfer:** Retain the near-invisible backing, not a conspicuous glass-card aesthetic.

#### Black editorial canvas · level 0

**Only for:** photographic catalogs

**Use:** Immersive long-form picture collections and their footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Photography sits directly on black, with no card perimeter or shadows.

**Transfer:** Keep this as a coherent page-wide theme rather than scattered dark cards.

#### Contact panel · level 1

**Only for:** contact and inquiry sections

**Use:** Direct-contact box and form backing.

**CSS:** `background: #f5f5f5; border-radius: 10px; box-shadow: none`

**Observed:** Flat pale gray panels; the larger professional form uses 16px corners.

**Transfer:** Reserve pale filled surfaces for practical conversion tasks.

#### Photo legibility veil

**Only for:** audience-page photographic openings

**Use:** Light top-to-bottom shading over a 600px hero.

**CSS:** `background: linear-gradient(rgba(84, 84, 84, 0.2) 0%, rgba(0, 0, 0, 0) 100%)`

**Observed:** A restrained neutral veil leaves the photographic color intact.

**Transfer:** Use only enough shading to keep white navigation and title readable.

## Components

### Fixed navigation

**Use:** Persistent page orientation.

**CSS:** `position: fixed; top: 0px; height: 77px; width: 100%; z-index: 9; padding: 22px 40px 20px`

**Text style:** `link` — Inter 500 · 14px/1.25 · tracking -0.036em

**Observed:** Four compact links at left, identity centered independently, globe and language selector toward the right, and a plain text conversion link at the far right. White on the photographic opening; black on an opaque white bar after scrolling. A translucent white variant also exists.

**Transfer:** Keep the middle identity visually centered even when left and right groups differ in width.

### Opening outline action

**Use:** Low-pressure exploration over the main photograph.

**CSS:** `color: #ffffff; background: transparent; border: 1px solid rgba(255, 255, 255, 0.5); border-radius: 8px; padding: 10px 36px; height: 38px`

**Text style:** `link` — Inter 500 · 14px/1.25 · tracking -0.036em

**Observed:** Small rounded rectangle beneath the lower-left title, not a filled primary pill.

**Transfer:** Use one short invitation whose weight stays secondary to the scene.

### Image rule card

**Use:** Core proof, capability and process explanation.

**CSS:** `display: flex; flex-direction: column; gap: 20px; overflow: hidden`

**Text style:** `body` — Inter 400 · 14px/1.25 · tracking -0.036em

**Observed:** Portrait photograph with 8px corners, then a full-width 1px black rule, an uppercase eyebrow 8px beneath the rule, and body copy 15px beneath the label. The card itself has no fill or perimeter.

**Transfer:** Use real product details or process images and make the heading name one concrete advantage.

### Photographic navigation tile

**Use:** Image-led destinations for audiences, product paths or editorial collections.

**CSS:** `position: relative; border-radius: 10px; overflow: hidden; color: #ffffff`

**Text style:** `tile-label` — Inter 500 · 24px/1.2 · tracking -0.0417em

**Observed:** Tall photograph fills the tile. A bottom overlay row holds the label with 20px inner padding; there is no separate caption panel.

**Transfer:** Choose a different, destination-specific image for each tile.

### Carousel arrow

**Use:** Testimonial navigation beneath the quote block.

**CSS:** `width: 40px; height: 40px; border-radius: 20px; background: #e8e8ed; color: #6e6e73; display: flex; align-items: center; justify-content: center`

**Observed:** Two circular controls sit together below the left-aligned quote; each contains a 24px arrow.

**Transfer:** Keep controls visibly smaller than the quote and separate from the attribution.

### Footer columns

**Use:** Quiet informational ending shared across page types.

**CSS:** `background: #ffffff; color: #000000; padding: 40px 40px 20px; display: flex; gap: 10px`

**Text style:** `link` — Inter 500 · 14px/1.25 · tracking -0.036em

**Observed:** A broad identity-and-origin block at left, four compact category columns, and a small credential mark at far right. Uppercase 11px labels and the 16px origin line are muted with 0.4 opacity. Social icons sit below the identity; copyright sits near the lower left. The whole footer is about 297px tall. Catalog pages reverse it to black.

**Transfer:** End with useful information and restrained proof rather than an oversized final sales slogan.

### Contact arrow pill

**Only for:** contact and inquiry sections

**Use:** Direct human contact action.

**CSS:** `background: #ffffff; color: #05080c; border-radius: 100px; height: 42px; padding: 1px 1px 1px 24px; display: flex; align-items: center; gap: 16px`

**Text style:** `contact-action` — Geist 500 · 16px/1.2 · tracking -0.02em

**Observed:** A dark 40px circular arrow forms the right endcap. A download variant reverses the pill to dark with a white circular down arrow.

**Transfer:** Retain the contrasting endcap rather than appending a loose icon outside the pill.

### Submit pill

**Only for:** inquiry forms

**Use:** Complete a contact form.

**CSS:** `background: #05080c; color: #ffffff; border-radius: 100px; padding: 14px 24px; height: 47px`

**Text style:** `contact-action` — Geist 500 · 16px/1.2 · tracking -0.02em

**Observed:** Compact dark pill, left aligned below the fields; no arrow endcap.

### Inquiry field

**Only for:** inquiry forms

**Use:** Name, company, email and message entry.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 10px 20px; min-height: 50px`

**Text style:** `contact-action` — Geist 500 · 16px/1.2 · tracking -0.02em

**Observed:** Labels stand above white fields with a 10px gap; stacked fields have 20px spacing. Message area is 100px tall. The form sits on the Contact panel with 30px padding and a 16px outer radius.

**Transfer:** Use persistent labels and preserve the broad, simple field geometry.

### Price indication card

**Only for:** pricing comparisons

**Use:** Compare concrete configurations rather than abstract subscription tiers.

**CSS:** `border: 1px solid #222222; border-radius: 10px; padding: 20px; display: flex; flex-direction: column; gap: 10px`

**Text style:** `heading-sm` — Inter 500 · 22px/1.1 · tracking -0.0227em

**Observed:** A large fine-line isometric drawing precedes the title. Muted subheads divide concise specifications and price ranges. Three equal cards share the row; no featured-plan color fill.

**Transfer:** Show the physical or functional contents behind each price, using diagrams rather than checkmark lists.

### Blurred benefit card

**Only for:** professional benefit sections

**Use:** Turn operational benefits into a photographic atmosphere.

**CSS:** `border-radius: 16px; overflow: hidden; padding: 150px 50px; display: flex; align-items: center; justify-content: center; color: #ffffff`

**Text style:** `benefit-heading` — Geist 500 · 25px/1.1 · tracking -0.04em

**Observed:** Centered title and compact 17px support with 6px separation float over heavily blurred, warm product photography. A dark overlay at 0.15 opacity improves contrast. Cards form a three-column grid with 30px horizontal and 40px vertical gutters.

**Transfer:** Blur contextual images until material colors remain but literal details disappear; do not substitute neon gradients.

## Imagery and graphics

### Inhabited product photography

**Use:** Signature opening, proof cards and navigation tiles.

**Observed:** Architectural room views and close details show pale timber, steel, cream surfaces, burgundy and muted mustard fronts. Natural window light gives directional shadows and warm highlights; books, plants, cups and open doors suggest use without clutter. Images dominate the opening and card grids; type is modest. Full-bleed openings are square-cornered, while inset proof images have 8px corners and navigation images 10px.

**Transfer:** Photograph the new product in a believable environment with warm daylight and visible material texture. For software or services, show people, tools and artifacts in an actual work setting; pair this with a legible product detail rather than a floating dashboard collage.

### Blurred material fields

**Only for:** professional benefit sections

**Use:** Atmospheric backing for benefit cards.

**Observed:** Olive-gray, sandy beige, rust and plum photographic masses are heavily defocused beneath centered white copy. The fields preserve uneven organic color distribution rather than geometric gradients.

**Transfer:** Derive fields from the new product's own materials and photography.

**Build:** Place a contextual photograph absolutely behind the text, enlarge it beyond the card edges, apply blur(35px), and clip to a 16px rounded rectangle. Add a full-size rgba(5,8,12,0.15) overlay, then white copy above it. Keep the title and support within a centered narrow measure; exact blur strength may be tuned to remove identifiable details.

### Technical material studies

**Only for:** professional product explanations and pricing comparisons

**Use:** Make construction and configuration legible.

**Observed:** Black-backed macro and exploded-component videos contrast pale plywood edges with dark surfaces. Pricing instead uses delicate gray isometric line drawings on white, occupying most of the upper half of each outlined card.

**Transfer:** Use a simple exploded diagram, material cross-section or parts drawing of the new product. Keep fine lines, neutral backing and generous image area; avoid glossy decorative 3D.

### Numbered photographic essay

**Only for:** photographic catalogs

**Use:** Long-form case-study browsing.

**Observed:** Three tightly spaced columns on black mix 430px square and 430×537px portrait views. The taller center image creates an uneven lower edge within a row. Small uppercase mono project-and-index captions sit 8px below the pictures; compact view toggles sit above the grid at right.

**Transfer:** Mix establishing views, close details and evidence of daily use. Keep square and portrait framing deliberate and keep captions out of the images.

### Monochrome people row

**Only for:** company and team stories

**Use:** Human proof near the end of an editorial company page.

**Observed:** Five evenly distributed vertical black-and-white portraits with soft corners show people naturally at work or in direct portrait poses. Names appear in compact black text below, roles in gray.

**Transfer:** Use actual contributors with varied natural poses and consistent monochrome treatment, not uniform avatar circles.

### Icons

**Observed:** Small monochrome utility marks: an 18px globe and 12px chevron in the header, 24px social symbols, small quotation marks, simple arrows and a plus beside the proof heading. Arrows in contact endcaps are about 18×14px; the header chevron uses a 1.5px round stroke.

**Transfer:** Use plain utility icons, black on white or white on imagery. Reserve enclosing circles for arrow controls rather than placing every icon in a badge.

## Section recipes

How recurring sections are built.

### First screen: Immersive photographic opening

**Observed:** An approximately 883px-high edge-to-edge photograph fills nearly the entire first 900px. The scene is the background and primary object; there is no floating product card. A transparent Fixed navigation overlays the top with a centered identity. At the lower left, roughly 40px in from the side, a small uppercase invitation sits above a one-line white display title at 46px/1. An Opening outline action follows below. Short segmented slide indicators sit at the bottom center and a down arrow at lower right. The title occupies about a third of the screen width while the environment occupies everything else. Within the first 900px the entire scene, navigation, title and action are visible; the next white content section only begins at the bottom edge, and its heading falls below the fold.

**Transfer:** Lead with one convincing lived-in scene and a short invitation for the new product; if there is no equivalent room or object, photograph a real work environment and make the process artifact the visual anchor. Audience pages use a shorter 600px photographic band with a lower-left title and an optional outline download action. Company narratives open on white with an uppercase marker and a 46px thesis above full-width documentary media. Catalogs open on black with a narrow 29px statement above the first photo essay.

**Avoid:** Do not replace the immersive scene with a centered headline above a small mockup, a split-screen sales panel or an oversized typographic billboard.

**Text style:** `display` — Inter 500 · 46px/1 · tracking -0.0402em

### Introduction marker and statement

**Observed:** A left-aligned uppercase eyebrow leads a 30px heading-sized explanation by 10px. Text stays within about 681px, leaving the right half of the white canvas empty. Audience pages use 40px side insets and 50px to 100px upper breathing room.

**Transfer:** Explain the system or offer in a few direct clauses, not a dense full-width paragraph.

**Text style:** `heading` — Inter 500 · 30px/1.05 · tracking -0.0417em

### Four-part photographic proof

**Observed:** A 30px section heading sits 25px above a four-column Image rule card grid. Portrait images are about 316×401px, separated by 25px gutters. Captions align to their images and remain on the white canvas.

**Transfer:** Use the same construction for capabilities, people using the product, or stages of a process; vary the subjects, not the frame geometry.

**Text style:** `heading` — Inter 500 · 30px/1.05 · tracking -0.0417em

### Left-aligned testimonial pause

**Observed:** A quotation mark introduces a 30px testimonial lead, followed by 18px gray support and an underlined attribution. Two Carousel arrow controls sit below. The whole block reads as a short editorial interlude on white, not a filled quote card.

**Transfer:** Let one concrete user statement interrupt the photo grid; keep attribution human and brief.

**Text style:** `heading` — Inter 500 · 30px/1.05 · tracking -0.0417em

### Photographic path grid

**Observed:** Six Photographic navigation tiles form a three-column, two-row composition with 15px gutters. Labels sit inside the bottom of tall pictures. The grid carries far more visual weight than surrounding copy.

**Transfer:** Use image destinations to separate audience needs, product families or useful next steps without introducing a new visual system.

**Text style:** `tile-label` — Inter 500 · 24px/1.2 · tracking -0.0417em

### Low-contrast proof field

**Observed:** A small plus and muted 22px proof heading sit above six gray logos in a spacious three-column field. Quiet logo backing stays almost invisible; 70px outer padding and wide 250px column gaps make the marks feel lightly distributed.

**Transfer:** Keep proof visually secondary and use only a few clearly legible marks or short verified proof statements.

**Text style:** `heading-sm` — Inter 500 · 22px/1.1 · tracking -0.0227em

### Informational close

**Observed:** Footer columns concludes every page with compact useful links, a small identity, muted origin line, social marks and a credential at the far right. It does not enlarge the identity or introduce a new display headline.

**Transfer:** Close in the same restrained information hierarchy after either proof, people or conversion content.

**Text style:** `footer-label` — Inter 500 · 11px/1 · uppercase

### Editorial split story

**Only for:** company narratives

**Observed:** A 60px-padded white section splits into two near-equal columns with a 20px gap. A gray 12px label and 25px aside occupy the left; the right carries several black 30px paragraphs and a short concluding maxim. A Monochrome people row follows before Footer columns.

**Transfer:** Pair a succinct guiding idea with substantial narrative on the right; end with real people rather than another sales hero.

**Text style:** `heading` — Inter 500 · 30px/1.05 · tracking -0.0417em

### Configuration comparison

**Only for:** pricing comparisons

**Observed:** A 30px lead and muted 22px qualifiers introduce three Price indication cards with 20px gutters. Fine-line drawings, descriptive names, configuration details and ordinary price ranges create a practical specification-sheet feeling.

**Transfer:** Reveal what changes between configurations, with exclusions and conditions stated before the cards.

**Text style:** `heading` — Inter 500 · 30px/1.05 · tracking -0.0417em

### Professional material proof

**Only for:** professional product pages

**Observed:** A wide inset project photograph with a 14px credit gives way to Blurred benefit cards. A three-column row of black-backed construction videos follows with 22px titles and 14px explanatory text; a centered 1120×630px presenter video gives the system a human explanation.

**Transfer:** Move between evidence at room scale, operational benefits and close construction detail. Use an expert explanation when complexity calls for it.

**Text style:** `benefit-heading` — Geist 500 · 25px/1.1 · tracking -0.04em

### Practical contact ending

**Only for:** audience and inquiry pages

**Observed:** The Contact panel supports either a centered stack or a broad form beside a narrower direct-contact card. Use contact-heading, a muted support line and Contact arrow pill. Professional forms use 30px padding, white fields and a Submit pill. The residential version adds a separate gray download introduction and reversed arrow pill before Footer columns.

**Transfer:** Make the ending a useful next conversation, with a named human where relevant and supporting documentation kept separate from the main contact action.

**Text style:** `contact-heading` — Geist 500 · 28px/1.2 · tracking -0.04em

### Black photographic chapters

**Only for:** photographic catalogs

**Observed:** A narrow introductory statement begins around 200px down the black canvas. Project headings and gray context precede Numbered photographic essay grids; chapters have 90px top spacing. The final photographs lead directly into a black version of Footer columns with generous breathing room and no separate promotional banner.

**Transfer:** Organize a portfolio into repeatable named chapters and let the last set of images be the closing proof.

**Text style:** `catalog-heading` — Switzer 500 · 24px/1.1 · tracking -0.02em

## Page flow

**Storyline:** immersive invitation → tangible proof → practical explanation or pathways → trust → useful next step → informational close

### Broad marketing landing page

1. **invitation** — Full-screen inhabited photograph with low-left title and outlined exploration link.
2. **capability proof** — Four portrait image–rule–label cards.
3. **social proof** — Editorial testimonial with small carousel controls.
4. **path selection** — Tall photographic destination grid.
5. **trust and close** — Muted logo field followed by the compact column footer.

**Transfer:** Introduce the experience first, substantiate it with material detail, then offer distinct ways forward.

### Company narrative

1. **thesis** — White opening with small marker and tightly set 46px statement.
2. **context** — Full-width documentary video.
3. **principles** — Gray aside beside large black editorial paragraphs.
4. **human proof and close** — Monochrome people row followed by the shared footer.

**Transfer:** Make the company argument specific, then give it human authorship.

### Consumer audience detail

1. **orientation** — 600px photographic title band and a narrow introduction.
2. **proof** — Four real-use portraits or spaces.
3. **process explanation** — Four numbered photographic process cards.
4. **objection handling** — Configuration drawings and indicative price ranges.
5. **conversion and close** — Contact form, direct-call panel, supporting document download and shared footer.

**Transfer:** Answer who it is for, how it works and what it costs before inviting contact.

### Professional product detail

1. **orientation** — Photographic title band with a download action and concise introduction.
2. **project proof** — Large credited installed-project photograph.
3. **operational value** — Centered benefits on blurred photographic cards.
4. **technical explanation** — Construction studies and a presenter video.
5. **conversion and close** — Broad inquiry form beside a named direct-contact card, then shared footer.

**Transfer:** Support professional decisions with project evidence, operational consequences and technical detail rather than consumer lifestyle copy alone.

### Editorial case-study catalog

1. **framing** — Narrow white introductory paragraph on black.
2. **repeated proof chapters** — Project-and-location headings, short gray descriptions and mixed-aspect numbered photography.
3. **close** — Last image chapter resolves into the black informational footer.

**Transfer:** Let multiple real examples provide the argument; keep description subordinate to images.

## Writing

Matter-of-fact, materially specific and gently optimistic. Confidence comes from explaining how things work over time, with occasional warm first-person recommendation rather than promotional superlatives.

**Do not copy:** Do not reuse the Stykka identity, wordmark, proprietary photography, customer names, quotations, project names, phone numbers, credentials, prices, origin claims or environmental and durability claims. Replace all examples with truthful content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the maker and you or your for practical reader needs. Product explanations can be impersonal; contact language is direct and welcoming.
- **Rhythm:** Short functional headings alternate with compact explanatory paragraphs. Occasional parallel three-part statements give an editorial finish; avoid exclamation-heavy persuasion.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening invitation | Short imperative that invites exploration rather than demanding purchase. | 3–5 words | “Explore our kitchens” |
| Thesis | Contrast the usual category assumption with a better alternative. | Two short sentences | “The world doesn’t need more furniture. It needs better furniture.” |
| Capability label | Plain material or functional advantage, set as a compact label. | 2–4 words | “Superior build quality”<br>“Design for Disassembly” |
| Explanation | Name the mechanism, then explain the practical consequence. | 1–3 sentences | “Every joint, screw, and panel is designed to come apart cleanly—so repairs take minutes and upgrades don’t create waste.” |
| Human conversion | Direct contact verb followed by a low-pressure invitation. | 3–8 words | “Call us directly”<br>“Get in touch to discuss your ideas” |
| Editorial conclusion | Parallel short clauses with active verbs. | Three brief sentences | “Buy less. Keep more. Leave better.” |

**Words and phrasing to use:** designed to; materials; repair; adapt; built for; over time; get in touch; your ideas; real projects

**Avoid:** revolutionary; game-changing; ultimate luxury; unlock limitless possibilities; hurry; buy now before it's gone

**Rules:**

- Prefer a physical mechanism or service detail to an unsupported adjective.
- Keep process labels numbered and concrete when sequence matters.
- State pricing exclusions plainly near the comparison introduction.
- Use personal stories to explain choices and use, not to manufacture celebrity endorsement.

## Do's and Don'ts

### Do

- Keep the opening photograph edge-to-edge and the title low left, with a 40px side inset.
- Set primary section headings at 30px/1.05, weight 500 and -1.3px tracking.
- Use 14px/1.25 body copy beneath image proof instead of expanding every paragraph into display text.
- Preserve the 1px rule and uppercase 14px label beneath portrait proof images.
- Use 25px gutters for four-part proof and 15px gutters for photographic destinations.
- Keep contact arrow endcaps at 40px inside a 42px pill.
- Keep the footer's category labels at 11px and visually muted.
- Let natural daylight, timber, metal and real-use objects provide warmth within the neutral framework.

### Don't

- Do not apply a saturated brand color to buttons, section bands and headings; the marketing framework is monochrome.
- Do not turn 500-weight grotesk headings into 700-weight bold display type.
- Do not give every white content block a shadow or pale rounded card fill; most content sits directly on the canvas.
- Do not use the 100px contact-pill radius for the photographic opening action; its rounded rectangle is distinct.
- Do not round full-bleed hero media just because inset photographs have 8px or 10px corners.
- Do not style the logo field as prominent bordered sponsor cards; its backing is nearly invisible.
- Do not scatter Switzer, Geist and mono labels throughout ordinary landing sections; keep their editorial and functional scopes.
- Do not center all body text; centered copy belongs to benefit cards and the compact direct-contact stack.

## Motion and responsive

### Motion

**Observed:**

- The opening includes segmented slideshow indicators and a down arrow; the testimonial includes paired arrow controls.
- No action transition durations or running marketing animations are established.
- The testimonial attribution declares a hover text color of rgba(0,0,0,0.5) while retaining its underline.

**Transfer:**

- Preserve manual navigation affordances for image-led slides and testimonials rather than adding conspicuous animated decoration.

**Unknown:**

- Slideshow timing, scroll-trigger behavior, easing and autoplay rules are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px and 1200px; the documented composition is desktop.

**Transfer:**

- On narrower layouts, preserve the order photograph → rule → label → explanation when reducing grid columns.
- Keep opening text near the lower edge of the scene, with room for its outlined action; do not transform it into a separate centered card.
- For the catalog, retain mixed image proportions and external captions as columns reduce.

**Unknown:**

- Exact mobile typography, side insets, navigation collapse and grid changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
