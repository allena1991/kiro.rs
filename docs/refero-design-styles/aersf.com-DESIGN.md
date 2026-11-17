# Aer — urban utility in motion

## Overview

An image-led retail style with the toughness of everyday equipment and the polish of a city fashion editorial. White and pale gray architecture, black grotesk lettering and a thin turquoise signal surround tactile product photography. Oversized extended capitals provide the campaign voice, while compact catalog text and matter-of-fact technical descriptions keep the experience practical. It suits physical products with strong materials, purposeful details and a life beyond the studio.

### Essentials

- Campaign names behave like wide equipment markings: extended grotesk capitals at 80px/0.95, weight 900, normal tracking, centered over photography rather than isolated in a text column.
- The opening is a photographic environment, not a product cutout beside copy: a 768px-tall edge-to-edge scene under a 70px navigation row, with the headline, 22px support line and white action grouped near the bottom center.
- Actions are rectangular labels: the marketing button is 152×60px with 18px bold text, 18px 32px padding and square corners; purchase controls use a thin black outline rather than a colored fill.
- The interface stays almost entirely monochrome: white canvas, pale gray footer and black text, with turquoise confined to the 39px announcement strip. Strong orange, green and blue belong to photographed objects and environments, not decorative UI panels.
- Images carry the narrative at near-poster scale: 1330×887px editorial photographs inside 55px side margins, followed by a centered 18px caption about 30px below. Include this image-and-caption device on new pages; without lifestyle media, use a deliberately lit contextual still life.
- Alternate lived-in scenes with meticulous object proof: clean pale studio packshots, recognizable material close-ups and concise factual labels. Do not replace the tactile photographic character with generic vector feature icons.
- The ending returns to a practical pale gray utility band: horizontal support links, a left-aligned 30px bold newsletter heading and a 418×61px joined email form, then a long hairline and centered social marks.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Turquoise signal | `#0cc6cf` | `--color-signal` | background, accent | Announcement strip only; not a general button or heading accent. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, border, action | Default lettering, outlined controls and newsletter submit; solid editorial bands on brand-story pages. |
| Soft rule | `#dbdbdb` | `--color-rule` | border | Visible equivalent of rgba(112,112,112,0.25) over white; the same alpha rule becomes slightly darker over the utility gray footer. |
| Swatch edge | `#e3e3e3` | `--color-edge` | border | Fine outlines around small color swatches and inactive size controls. |
| Utility gray | `#f2f2f2` | `--color-footer` | background, surface | Shared footer band. |
| Pale media base | `#f7f7f7` | `--color-media-base` | surface | Underlying photographic stage base; the photograph remains the visible surface. |
| White | `#ffffff` | `--color-canvas` | background, text, action | Page canvas, light buttons and inverse text over dark photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical product storytelling | Charcoal stage | `#191919` | `--color-material-stage` | background | Dark material-detail chapter with white type. |
| technical product storytelling | Specification gray | `#ececec` | `--color-spec-stage` | background | Flat specification band behind facts and dimension drawings. |

## Typography

- **Helvetica** — Body text, catalog labels, captions and controls. Direct neo-grotesk with familiar industrial proportions and minimal ornament. If unavailable, use **Inter**. Use regular and bold cuts; preserve compact text sizes. Font stack: "Helvetica", "Inter", "Helvetica Neue", Arial, sans-serif.
- **Helvetica Neue** — Navigation, section titles, newsletter heading and product-story headings; Medium, Bold and Bolder are family cuts. Even, broad neo-grotesk rhythm; stronger weights remain functional rather than decorative. If unavailable, use **Inter**. Use 500 for medium and 700 for bold; preserve normal tracking. Font stack: "Helvetica Neue", "Inter", Helvetica, Arial, sans-serif.
- **Helvetica Neue LT Std 93** — Extended campaign capitals and monumental editorial statements. Very wide, heavy sans-serif with blunt terminals and dense capital silhouettes. If unavailable, use **Archivo**. Use expanded width near 125% and weights 700–900; tune width before reducing size. Font stack: "Helvetica Neue LT Std 93", "Archivo", Helvetica, Arial, sans-serif.
- **Helvetica Now Display** — Campaign support and oversized brand-story paragraphs. Smooth contemporary grotesk with open counters and clean display spacing. If unavailable, use **Inter**. Use 500 for support and editorial paragraphs. Font stack: "Helvetica Now Display", "Inter", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| campaign-display | Helvetica Neue LT Std 93 | 900 | 80px | 0.95 | normal, uppercase | Default marketing opening headline over photography. |
| newsletter-heading | Helvetica Neue | 700 | 30px | 1.2 | normal | Left-aligned footer invitation. |
| collection-heading | Helvetica Neue | 500 | 28px | 1.2 | normal | Centered titles above product rails. |
| campaign-support | Helvetica Now Display | 500 | 22px | 1.4 | normal | One centered sentence below the campaign title. |
| marketing-action | Helvetica | 700 | 18px | 1.1 | -0.02em | White campaign action. |
| navigation | Helvetica Neue | 500 | 18px | 1.223 | normal | Main category navigation. |
| image-caption | Helvetica | 400 | 18px | 1.16 | normal | Single centered linked caption beneath a large editorial image. |
| catalog-label | Helvetica | 400 | 15px | 1.2 | normal | Product names, prices, announcement text and short newsletter support. |
| body | Helvetica | 400 | 15px | 1.5 | normal | Utility links and compact general text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| brand-story pages | manifesto | Helvetica Neue LT Std 93 | 700 | 105px | 1 | normal, uppercase | Multi-line statement filling the content width. |
| brand-story pages | editorial-heading | Helvetica Neue LT Std 93 | 700 | 90px | 1 | normal, uppercase | White headings beneath large photographs on black bands. |
| brand-story pages | editorial-closing | Helvetica Neue LT Std 93 | 500 | 90px | 1 | normal, uppercase | Broad left-aligned title over the final environmental photograph. |
| technical product storytelling | feature-heading | Helvetica Neue | 500 | 60px | 1.2 | normal | Centered technical chapter title; use this explicit 60px/1.2 recipe as the default for new technical sections. |
| brand-story pages | editorial-body | Helvetica Now Display | 500 | 50px | 1.1 | normal | Large full-width paragraphs with approximately three lines per thought. |
| brand-story pages | editorial-banner | Helvetica Neue | 500 | 50px | 1 | normal | Short lower-left title in a shallow photographic opening. |
| product detail pages | product-title | Helvetica Neue | 500 | 28px | 1.1 | normal | Compact title in the commerce purchase column. |
| technical product storytelling | feature-support | Helvetica | 400 | 27px | 1.407 | normal | Centered supporting copy over full-width product-use photographs. |
| technical product storytelling | spec-body | Helvetica | 400 | 23px | 1.304 | normal | Left-aligned specifications, dimensions and materials. |
| product detail pages | purchase-action | Helvetica | 700 | 15px | 1.4 | normal | Full-width outlined purchase action. |

**Notes:**

- Use width and weight, not extra tracking, to make campaign capitals imposing. Normal tracking is the rule; the marketing action alone tightens to -0.02em.
- The commerce title is deliberately modest beside the image gallery. Technical chapter headings grow to 60px, while brand-story statements use the much wider 90–105px extended face.
- Keep regular 15px product names and prices visually subordinate to photography. Do not promote every label into a heading.

## Layout

**Density:** Airy at the editorial level, compact inside commerce and utility controls; large uninterrupted images create most of the vertical scale.

### Spacing

| Value | Use |
| --- | --- |
| 7px | Newsletter heading-to-support separation and individual product-slide side padding. |
| 12px | Product photograph to product name. |
| 20px | Gap between technical feature panels. |
| 24px | Navigation side inset. |
| 30px | Editorial photograph to its centered caption. |
| 35px | Newsletter support to form; repeated specification-row separation. |
| 55px | Main desktop side inset and support-to-marketing-action spacing. |
| 58px | Breathing room after editorial image captions. |
| 60px | Opening collection section top inset and photographic hero bottom inset. |
| 63px | Collection heading to product images; footer top padding. |
| 72px | Technical feature heading to media row. |
| 80px | Brand-story image to extended chapter heading. |
| 86px | Technical chapter top padding. |
| 110px | Specification chapter bottom padding. |
| 200px | Monumental brand-story text section top padding. |

### Containers and grids

- **editorial-container**: max width 1440px · side padding 55px. Centered desktop content frame producing 1330px-wide editorial images and footer content.
- **header-container**: max width 1440px · side padding 24px. Wide category navigation on the left, independently centered wordmark, search and cart on the right.
- **hero-copy**: max width 840px · side padding 20px. Centered campaign copy inset over a full-width image near its lower edge.
- **product-rail**: gap 14px. Horizontal strip of 448px slide cells with 7px internal side padding; 434px-wide images and a partial next item signal continuation.
- **feature-triptych** (only for technical product storytelling): 3 columns · gap 20px · side padding 55px. Three equal 426px-wide portrait media panels under a centered title.
- **commerce-split** (only for product detail pages): 2 columns · side padding 55px. Approximately two thirds of the content frame for a two-column image gallery and a 380px purchase column on the right.
- **overlay-support** (only for technical product storytelling): max width 1055px · side padding 20px. Centered support copy over large environmental product images.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-editorial-images | 0px |
| technical product storytelling | feature-media | 10px |
| customer review lists | review-avatars | 50% |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default background and breathing room between photographic chapters.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat, untextured and unshadowed.

**Transfer:** Use spacing and image scale rather than raised cards to divide content.

#### Photographic stage · level 0

**Use:** Campaign opening and full-width environmental storytelling.

**CSS:** `background-color: #f7f7f7; background-size: cover; background-position: 50% 50%; position: relative`

**Observed:** Photography covers the stage. The campaign opening uses a black overlay at opacity 0.1 to support white copy.

**Transfer:** Place the image beneath a separate rgba(0,0,0,0.1) scrim and the text above it; preserve natural contrast and detail.

#### Utility band · level 0

**Use:** Shared footer and newsletter ending.

**CSS:** `background: #f2f2f2; padding: 63px 55px 106px`

**Observed:** One continuous pale field, with a long low-contrast separator rather than a card around the newsletter.

**Transfer:** Keep the upper links and form left aligned, and the lower social row centered.

#### Charcoal detail band · level 0

**Only for:** technical product storytelling

**Use:** Material and construction proof.

**CSS:** `background: #191919; color: #ffffff; padding: 86px 55px 90px`

**Observed:** Dark backing connects the heading, close-up triptych and captions into one chapter.

**Transfer:** Use for a focused tactile proof moment, not every feature.

#### Specification band · level 0

**Only for:** technical product storytelling

**Use:** Practical facts paired with product dimensions.

**CSS:** `background: #ececec; padding: 0px 55px; color: #000000`

**Observed:** Flat gray background supports black type and neutral product drawings; content has 86px top and 110px bottom breathing room.

**Transfer:** Keep facts tabular and illustration-like product views on the same plane.

#### Black editorial band · level 0

**Only for:** brand-story pages

**Use:** Long-form image-and-statement chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Large inset photography leads into extended capitals and oversized paragraphs with no card edges.

**Transfer:** Carry a brand argument with full-bleed black continuity, rather than isolated dark boxes.

## Components

### Navigation row

**Use:** Persistent orientation and shopping utilities.

**CSS:** `height: 70px; padding: 0px 24px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — Helvetica Neue 500 · 18px/1.223

**Observed:** Three category links sit left, the compact wordmark is centered across the viewport, and thin search and cart icons sit right. The opening image uses white navigation with a transparent visual treatment; scrolling onto white content switches to black navigation. The header stack includes the announcement strip above it.

**States:** Declared: hover keeps the header text color at opacity 1; focus-visible uses a 2px solid black outline with 2px offset.

**Transfer:** Use a short category set; keep the logo visually centered even if the side groups differ in width.

### Announcement strip

**Use:** One practical service or availability message.

**CSS:** `background: #0cc6cf; height: 39px; color: #ffffff; text-align: center`

**Text style:** `catalog-label` — Helvetica 400 · 15px/1.2

**Observed:** A single line spans the viewport above the navigation, with 11px top and 10px bottom text padding.

**Transfer:** Keep this the only saturated interface band.

### Marketing button

**Use:** Default campaign conversion action.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid transparent; border-radius: 0px; padding: 18px 32px; height: 60px`

**Text style:** `marketing-action` — Helvetica 700 · 18px/1.1 · tracking -0.02em

**Observed:** A compact white rectangle centered beneath the supporting line; no arrow or rounded treatment.

**States:** Declared: hover retains black text and white background; focus-visible uses a 2px solid black outline with 2px offset.

**Transfer:** Use a direct short verb phrase over the image rather than multiple competing actions.

### Product card

**Use:** Collection and related-product rails.

**CSS:** `position: relative; padding: 0px 7px; width: 448px; border-radius: 0px`

**Text style:** `catalog-label` — Helvetica 400 · 15px/1.2

**Observed:** A 434×614px pale-backed product photograph leads; the left-aligned linked name starts 12px below, then the price, then small color swatches. The wrapper has no visible card border or shadow. The rail extends beyond the viewport.

**States:** Declared: product-name hover changes text to #404040; focus-visible uses a 2px solid black outline with 2px offset.

**Transfer:** Keep neutral isolated objects large and descriptions sparse; use the same camera and backing across the rail.

### Editorial caption link

**Use:** Connect a large photographic campaign tile to its destination.

**CSS:** `margin-top: 30px; text-align: center; color: #000000`

**Text style:** `image-caption` — Helvetica 400 · 18px/1.16

**Observed:** A single plain line beneath the image, without a button container; approximately 58px of space follows before the next image.

**States:** Declared: hover changes text to #404040; focus-visible uses a 2px solid black outline with 2px offset.

**Transfer:** Name the release, collection or benefit in a compact descriptive phrase.

### Newsletter input

**Use:** Email entry in the shared footer.

**CSS:** `background: #ffffff; border: 1px solid #000000; border-radius: 0px; padding: 20px 23px; height: 61px; width: 359px`

**Observed:** The input and adjacent Newsletter submit form a 418px-wide joined rectangle, left aligned beneath the invitation. There is no gap between them.

**Transfer:** Retain a visible label or accessible name and the simple single-field construction.

### Newsletter submit

**Use:** Submit the joined email form.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid transparent; border-radius: 0px; padding: 20px 23px; width: 59px; height: 61px; display: flex`

**Observed:** An 11×18px white right chevron is centered in a black square-like terminal segment; its accessible label is Submit.

**States:** Declared: hover retains white foreground and black background; focus-visible uses a 2px solid black outline with 2px offset.

**Transfer:** Keep the icon-only terminal segment instead of adding a second wide text button.

### Footer utility links

**Use:** Support, company and policy destinations.

**CSS:** `color: #000000; padding: 0px; text-decoration: none`

**Text style:** `body` — Helvetica 400 · 15px/1.5

**Observed:** A loose horizontal list at the top of the Utility band, with 37px right padding and 10px bottom padding on list items; the list wraps rather than becoming boxed columns.

**States:** Declared: hover remains black; focus-visible uses a 2px solid black outline with 2px offset.

### Purchase button

**Only for:** product detail pages

**Use:** Primary commerce action within the purchase column.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #000000; border-radius: 0px; padding: 18px; height: 59px; width: 380px`

**Text style:** `purchase-action` — Helvetica 700 · 15px/1.4

**Observed:** Full purchase-column width, beneath size and color controls; payment options follow below.

**States:** Declared: hover retains black text, white background and black border; focus-visible uses a 2px solid black outline with 2px offset.

**Transfer:** Preserve the outlined treatment even when this is the most important action.

### Feature media panel

**Only for:** technical product storytelling

**Use:** Show mechanisms and material details in a three-column proof chapter.

**CSS:** `width: 426px; height: 604px; border-radius: 10px; object-fit: cover`

**Text style:** `spec-body` — Helvetica 400 · 23px/1.304

**Observed:** Tall close-ups sit in equal columns with 20px gutters. Captions sit about 25px below, centered and narrower than the media; video panels have a small circular playback control at the lower right.

**Transfer:** Show one concrete detail per panel, not a collage of unrelated benefits.

## Imagery and graphics

### Contextual campaign photography

**Use:** Opening visual and large image-and-caption chapters; a defining device on new marketing pages.

**Observed:** Real products are large and recognizable in architectural environments: tiled walls, metal lockers, concrete sidewalks and transit spaces. Cropped people and asymmetrical object arrangements create fashion-editorial energy. Cool greens and gray neutrals dominate, with warm accents inside the photographs. The opening is edge-to-edge; later images sit inside 55px white margins.

**Transfer:** Photograph the new object in its actual use environment with directional daylight or direct flash, tactile surfaces and a restrained wardrobe. If no lifestyle shoot exists, stage a product still life against a real textured wall or work surface with one use-context prop; retain scale, shadows and material detail.

### Studio product portraits

**Use:** Catalog rails and commerce galleries.

**Observed:** Isolated front, rear, side and open views on very pale gray backing. Soft grounded shadows, clean cutout-like silhouettes and consistent camera height make dark nylon and hard shells legible. Rail imagery is portrait; the purchase gallery uses square images.

**Transfer:** Use the same lighting and neutral backing for every variant; keep the object filling most of the frame without cutting off functional parts.

### Material and mechanism close-ups

**Only for:** technical product storytelling

**Use:** Feature triptychs and wide demonstration videos.

**Observed:** Macro views show woven mesh, zipper teeth, ripstop grids, molded controls and fasteners in near-monochrome light. Portrait panels are 426×604px with 10px rounding; the wide demonstration spans 1330×770px. Objects and hands, not graphical diagrams, explain interaction.

**Transfer:** Shoot actual joints, finishes and mechanisms with enough depth and side light to reveal construction; a still image of the mechanism is the minimum version when video is unavailable.

### Dimensional product plate

**Only for:** technical product storytelling

**Use:** Specification band.

**Observed:** Front and side product views share a pale gray field with thin dimension brackets and compact black measurements; the full plate is approximately 492×551px.

**Transfer:** Use orthographic-like views of the new object and truthful measurements rather than an oversized decorative numeral.

**Build:** Arrange two transparent-background product views side by side in an SVG viewBox of 492 551. Draw thin neutral dimension brackets beneath each and a vertical bracket beside the right view; set black measurement labels parallel to their bracket, with the vertical label rotated 90 degrees. Leave the Specification band visible through the artwork.

### Motion-blur editorial portrait

**Only for:** seasonal campaign tiles

**Use:** A high-energy photographic variation within the image-and-caption format.

**Observed:** A sharply readable black product and central model sit against an orange circular light field, with ghosted silhouettes at the sides. The effect is photographic, grainy and warm rather than a smooth interface gradient.

**Transfer:** Keep the new product sharp and the energy in its surroundings; a single crisp portrait with a warm projected backdrop is an acceptable simpler version.

**Build:** Use a base portrait photograph with the object masked sharply above all effects. Duplicate only the person/background layer twice at low opacity, offset each horizontally by roughly 40px and blur by 12px. Place a broad warm circular light behind the figure in the photographic composite and add restrained grain; do not place this effect behind page text.

### Icons

**Observed:** Search is an approximately 28×24px outline and cart is 22×25px, both with 1.5px strokes in the navigation text color. Footer social marks are compact black filled silhouettes around 17–21px. The newsletter uses a white 2px-stroke chevron.

**Transfer:** Use simple unadorned outline utility icons and solid social marks. Do not add a colorful icon system to editorial content.

## Section recipes

How recurring sections are built.

### First screen: Photographic campaign opening

**Observed:** A 39px turquoise Announcement strip caps the page. Beneath it, the Navigation row visually overlays a 1440px-wide, 768px-tall photographic stage. The scene fills nearly the entire first screen: tactile architecture behind large suspended or staged objects, a subtle dark scrim, then white campaign copy near the bottom center. The extended 80px headline spans roughly half the viewport width; a 22px support sentence follows closely and the Marketing button sits 55px below the support. The group ends about 60px above the image bottom. Within the first 900px the navigation, complete title, support, action and main objects are visible; the next centered collection heading just enters at the bottom, while its products remain below.

**Transfer:** Make the new object the protagonist of a full photographic environment with room for centered lower copy. Without source-quality lifestyle art, use a sharply lit still life on a real architectural surface, with the object enlarged and the lower text area protected. A brand-story page instead opens with a 560px-tall image and a 50px lower-left title. A commerce detail page opens with a pale two-column gallery and a compact purchase column, not this campaign layout.

**Avoid:** Do not turn this into a split-screen SaaS hero, float a small cutout in empty white space, or put the headline at the top where it competes with navigation.

**Text style:** `campaign-display` — Helvetica Neue LT Std 93 900 · 80px/0.95 · uppercase

### Product discovery rail

**Observed:** A collection-heading is centered 60px below the preceding section, followed by 63px before the Product card rail. Images are large enough that roughly three cards plus the start of another appear on desktop. Names, prices and swatches are compact and left aligned.

**Transfer:** Use this for related objects, variants or a tightly edited family of offerings; preserve the oversized object-to-label ratio.

**Text style:** `collection-heading` — Helvetica Neue 500 · 28px/1.2

### Editorial poster and caption

**Observed:** A 1330×887px contextual image occupies the editorial-container with square corners. The Editorial caption link follows about 30px below; about 58px separates the caption from the next chapter. The image communicates almost everything, without a superimposed paragraph.

**Transfer:** Use one compelling use-case image per chapter and a concise link underneath; chapter number and order can vary with the new story.

**Text style:** `image-caption` — Helvetica 400 · 18px/1.16

### Utility ending

**Observed:** The Utility band is 643px tall at desktop. Footer utility links lead, then the newsletter-heading and a short support line 7px below. The joined Newsletter input and Newsletter submit follow 35px later, with a long alpha hairline beneath the newsletter area. A centered row of social marks and a tiny uppercase legal line complete the bottom.

**Transfer:** Keep the ending functional and spacious. Replace the invitation and destinations with relevant ones while retaining the left-aligned form above centered social and legal details.

**Text style:** `newsletter-heading` — Helvetica Neue 700 · 30px/1.2

### Feature proof chapter

**Only for:** technical product storytelling

**Observed:** The feature-heading is centered within approximately 85% of the content width, with 86px top padding and 72px before a Feature media panel triptych. A white version presents exterior mechanisms; the Charcoal detail band presents interior construction. Captions sit 25px below media. A related single-feature variant uses a 1330×770px video with a centered caption.

**Transfer:** Group complementary details into a readable proof set, and reserve a wide demonstration for a behavior needing more context.

**Text style:** `feature-heading` — Helvetica Neue 500 · 60px/1.2

### Immersive use chapter

**Only for:** technical product storytelling

**Observed:** A 1200–1500px-tall full-width product-use photograph places white feature-heading and feature-support text near the top center. The photo continues far below the copy, allowing hands, product and environment to carry the rest of the chapter.

**Transfer:** Use long photographic pacing for a major capability or range of variants; keep text to a heading and one short paragraph.

**Text style:** `feature-heading` — Helvetica Neue 500 · 60px/1.2

### Specifications with dimension plate

**Only for:** technical product storytelling

**Observed:** The Specification band has a centered 60px heading, then left-aligned label/value rows on the left and the Dimensional product plate on the right. Values use spec-body, with approximately 35px separation between fact groups. Content starts 86px into the band and ends with 110px of bottom space.

**Transfer:** Present practical purchasing facts at readable scale; replace dimensions with an equally concrete diagram if the new product is not a physical container.

**Text style:** `spec-body` — Helvetica 400 · 23px/1.304

### Monumental brand statement

**Only for:** brand-story pages

**Observed:** On white, an extended 105px uppercase manifesto occupies the 1330px content width with 200px top breathing room, then 60px before a 50px paragraph. On the Black editorial band, a large photograph is followed 80px later by a 90px extended heading and 44px later by the same paragraph scale.

**Transfer:** Use for a focused brand point of view, not ordinary feature paragraphs. Keep each thought short enough to hold at this scale.

**Text style:** `manifesto` — Helvetica Neue LT Std 93 700 · 105px/1 · uppercase

### Environmental closing action

**Only for:** long-form product and brand stories

**Observed:** A large full-width street photograph carries the closing promise and white rectangular action at the left. Technical product storytelling uses a 60px mixed-case title in a narrow stacked column; brand storytelling uses 90px extended capitals and a broad 50px paragraph over the lower image. Both maintain the recognizable product in the scene.

**Transfer:** End the persuasive story by returning the object to real use, with one direct action. Related items or customer proof can follow before the shared utility ending.

**Text style:** `feature-heading` — Helvetica Neue 500 · 60px/1.2

### Customer proof list

**Only for:** product detail pages

**Observed:** A compact centered review introduction and black rectangular review action lead into a full-width list of customer entries. Small circular initial avatars sit left; author, stars, title and review text form a compact stack. Dates sit far right and faint horizontal rules separate rows.

**Transfer:** Use real buyer language and a restrained list structure instead of large decorative quotation cards.

## Page flow

**Storyline:** Photographic promise → product discovery or practical purchase → visual use and construction proof → renewed action or related offerings → shared utility ending.

### Image-led marketing and collection discovery

1. **Promise** — Full-bleed photographic campaign with a wide uppercase product name, one support line and white action.
2. **Product discovery** — Centered heading and oversized pale-backed product rail.
3. **Use-case chapters** — Large inset editorial photographs, each followed by a small centered linked caption.
4. **Utility ending** — Pale gray support navigation, newsletter, divider and centered social row.

**Transfer:** Default to this campaign-first composition for a new marketing landing page; vary the number and order of photographic chapters to fit the offering.

### Explain a brand's point of view through image-led editorial storytelling

1. **Orientation** — Shallow photographic banner with a lower-left title.
2. **Positioning** — Monumental extended capitals and a large paragraph on white.
3. **Context** — Full-width environmental image.
4. **Values and credibility** — Black-backed inset photographs, wide uppercase statements and large explanatory paragraphs.
5. **Closing call** — Full-width street image with lower overlay copy and white action.
6. **Utility ending** — The same pale newsletter and support footer.

**Transfer:** Use the editorial scale for a small number of meaningful brand arguments supported by specific images.

### Support a purchase with clear choices, visual demonstrations and practical proof

1. **Purchase** — Two-column square image gallery beside a narrow title, price, ratings, size/color controls and outlined purchase button; description and details continue below.
2. **Promise** — Long full-width environmental photo with centered benefit copy.
3. **Capability proof** — Three-panel detail set, wide mechanism demonstration, immersive use image and charcoal material-detail triptych.
4. **Fit and objection handling** — Colorway use image followed by specifications and dimension plate.
5. **Closing call** — Full-width contextual photograph with a left-aligned promise and white action.
6. **Related discovery** — Pale product rail with compact names, prices and swatches.
7. **Customer proof** — Review invitation, rating summary and ruled review list with a further-reviews action.
8. **Utility ending** — The shared support and newsletter footer.

**Transfer:** Keep buying controls near the start, then alternate atmospheric use with tangible proof. Preserve the visual closing call even when reviews or related offerings follow it.

## Writing

Confident, functional and design-literate. Benefits are stated plainly, then supported with materials, mechanisms and everyday situations rather than exuberant sales language.

**Do not copy:** Do not reuse Aer names, logos, slogans, partnership marks, award badges, customer quotes, prices, review counts, dates, specifications or warranty claims. Substitute truthful details and original assets for the new offering. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Product descriptions use the product name or an impersonal construction; support copy occasionally addresses you. Brand-story copy uses we and we're without sounding conversationally chatty.
- **Rhythm:** Short noun phrases and two-to-five-word benefit headings alternate with one explanatory sentence. Period-separated triads give longer headings a deliberate cadence. Longer detail paragraphs stay factual.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Campaign headline | A short product or release name in uppercase. | 2–4 words | “TRAVEL KIT 3” |
| Supporting line | Name the practical function, with a concrete use distinction. | 7–14 words | “Smart toiletries storage that stands or hangs.” |
| Feature heading | A concise benefit or a set of parallel noun phrases. | 2–9 words | “Packing Simplified”<br>“Smart Organization. Premium Materials.” |
| Detail caption | Specific component plus mechanism or measurable advantage. | 10–24 words | “Triangular trolley system with 4 height settings for optimal stability and mobility” |
| Editorial statement | Period-separated assertions, each grounded in design or durability. | 3 short clauses | “CLEAN LINES. SMART FEATURES. BUILT TO LAST.” |
| Primary action | Literal shopping verb; no clever metaphor. | 2–4 words | “Shop Now”<br>“Add to Bag” |
| Campaign caption | Availability or seasonal context followed by the release name. | 4–10 words | “Now Available: Travel 4” |

**Words and phrasing to use:** smart; thoughtful; clean lines; durable; materials; designed for; organized; seamless; premium

**Avoid:** revolutionary without proof; game-changing; magical; unparalleled; hurry!!!; vague lifestyle superlatives

**Rules:**

- Pair a benefit with the detail that makes it credible.
- Use technical names and measurements only when they materially help the decision.
- Let photography establish aspiration; keep interface copy practical.
- Use direct availability language in campaign captions, not paragraph-length promotional copy.

## Do's and Don'ts

### Do

- Use extended 80px uppercase campaign type with 0.95 line height and normal tracking.
- Keep desktop editorial imagery inside 55px margins and captions about 30px below.
- Let the 39px turquoise strip be the primary interface color signal.
- Keep the marketing action white, rectangular and 60px tall.
- Give catalog images far more space than their 15px names and prices.
- Use 20px gutters and 10px media corners for technical triptychs only.
- Finish with the pale gray utility band and the 418px joined email form.
- Balance atmospheric scenes with concrete close-up proof of construction.

### Don't

- Do not apply the 90–105px manifesto scale to catalog labels or routine navigation.
- Do not round campaign buttons into pills; square edges are part of the equipment-label character.
- Do not make turquoise the default purchase button or use it as a full-screen background.
- Do not add drop shadows around the product cards; the layout is flat.
- Do not turn the product rail into small thumbnail cards with long descriptions.
- Do not import seasonal orange photographic effects into every section background.
- Do not use a generic feature-icon grid in place of material photography.
- Do not spread letter spacing across the extended headlines; their width comes from the typeface.

## Motion and responsive

### Motion

**Observed:**

- Action and surface CSS includes 0.3s transitions; some controls declare background-color and color transitions at 0.25s with cubic-bezier(0.86, 0, 0.07, 1).
- Product feature videos have circular play/pause controls. The overall header is sticky.
- Focus-visible actions consistently declare a 2px solid black outline with 2px offset.

**Transfer:**

- Keep motion subordinate to the object: demonstrate actual mechanisms in short controlled videos rather than animating unrelated interface decorations.
- Retain visible media playback controls and the persistent header.

**Unknown:**

- Exact video playback timing, scroll-trigger behavior and motion-reduction variants are not established.

### Responsive

**Observed:**

- Desktop compositions use a 1440px frame. Stylesheets declare many breakpoints, including 749/750px and 989/990px boundaries.

**Transfer:**

- On narrow screens, preserve the campaign's image-first character and lower copy grouping; resize the extended headline to fit without substituting a condensed face.
- Keep product rails horizontally browsable with a partial next item. Stack commerce purchasing information and technical proof panels when their labels no longer fit; these are adaptation recommendations.
- Allow the utility link list to wrap and constrain the joined email form to available width.

**Unknown:**

- Exact mobile font sizes, navigation collapse behavior and image focal-point changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
