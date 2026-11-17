# Resident — objects in open space

## Overview

An image-led editorial style with the restraint of a design catalogue and the warmth of lived-in architecture. White space and black grotesk typography frame natural-light photography, tactile materials and occasional hand-drawn studies. It suits considered physical products, creative practices and premium collections; the reading density is low between chapters but substantial within individual stories.

### Essentials

- The opening is a pair of editorial images, not a slogan billboard: two 689px square images separated by 21px, beneath a right-aligned 329×68px wordmark.
- Identity moves across the page: the wordmark sits at the upper right and returns at the lower left, at the same 329×68px scale, with an expansive white interval before small footer details.
- Typography behaves like catalogue annotation: sentence-case black MessinaSansWeb, 18.7px/24px weight 500 for editorial copy, 14px/1.4 weight 400 for product metadata, and 27.1px/35px titles with -1px tracking.
- Actions remain unboxed text; the only rounded controls are 24×24px carousel arrows with 50% radius. There is no filled primary-button hierarchy.
- Color belongs to the objects and their surroundings: page furniture is entirely black and white, while photography and artwork occupy almost all the opening's lower 694px.
- Image chapters breathe independently of copy: 21px side margins and gutters, square media in two-, three- and four-column arrangements, and 423px pauses between major landing-page chapters. Preserve a material or process image alongside finished-product imagery; use a photographed prototype or a simple drawn study when polished campaign media is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, link, action | All reading text and text actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Continuous page and navigation background; also the declared arrow hover background. |
| Charcoal arrow | `#333333` | `--color-arrow` | action | Small carousel chevrons, distinct from black text. |

## Typography

- **MessinaSansWeb** — All headings, editorial prose, navigation and product metadata. An open, contemporary grotesk with rounded bowls, generous counters and an unforced catalogue tone. If unavailable, use **DM Sans**. Use weights 300, 400 and 500; preserve the recipe-specific tracking. Font stack: "MessinaSansWeb", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| story-title | MessinaSansWeb | 500 | 27.1px | 35px | -1px | Titles underneath portrait-format case-study imagery. |
| editorial-body | MessinaSansWeb | 500 | 18.7px | 24px | normal | Default editorial captions, short section introductions and related-story links; the opening has no separate display headline. |
| navigation | MessinaSansWeb | 400 | 17.7px | 1.2 | -0.03em | Primary navigation and account/search links. |
| utility | MessinaSansWeb | 400 | 17.7px | 1.2 | normal | Cart and language controls. |
| product-meta | MessinaSansWeb | 400 | 14px | 1.4 | normal | Stacked product name, creator and price. |
| footer | MessinaSansWeb | 400 | 12px | 1.3 | normal | Footer contact details and service links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| profile directories | profile-heading | MessinaSansWeb | 400 | 56px | 1 | normal | Large person or studio names starting profile text. |
| profile directories | directory-index | MessinaSansWeb | 300 | 37.3px | 1.45 | normal | Vertical linked index of names. |
| profile directories | directory-intro | MessinaSansWeb | 300 | 24.3px | 1.4 | normal | Single introductory paragraph above directory imagery. |
| company narratives and profile directories | reading-body | MessinaSansWeb | 300 | 20.5px | 1.4 | normal | Long-form narrative and contextual product links. |

**Notes:**

- Keep sentence case throughout; large profile headings are regular, not bold.
- Only story titles and navigation tighten tracking. Long reading text retains normal tracking and a light weight.
- The prominent identity is artwork, not a display-font headline. Keep its aspect ratio intact and let images provide the first-screen emphasis.

## Layout

**Density:** Airy at chapter level, with closely grouped captions and metadata; the long intervals are as important as the narrow gutters.

### Spacing

| Value | Use |
| --- | --- |
| 10.5px | Half listing gutter. |
| 14px | Image-to-product-metadata spacing. |
| 21px | Page edges, image-column gutters and wordmark-to-opening-media gap. |
| 27.1px | Editorial image-to-caption spacing. |
| 46.7px | Profile heading-to-reading-column separation. |
| 56px | Space between the navigation zone and the identity row. |
| 70px | Narrative chapter separation and selected image captions. |
| 168px | Profile-chapter pause, only for profile directories. |
| 279.9px | Breathing room before the footer identity. |
| 423px | Large landing-page chapter intervals. |

### Containers and grids

- **page-width**: side padding 21px. Fluid page width; at 1440px the content spans 1398px rather than a centered narrow shell.
- **editorial-pair**: 2 columns · gap 21px. Equal 689px image columns with captions constrained more narrowly than their media.
- **editorial-trio**: 3 columns · gap 21px. Equal 452px square media tiles for short stories and related links.
- **product-row**: 4 columns · gap 21px. 334px square product images with compact text below.
- **narrative-column** (only for company narratives): max width 698px. Right-offset long-form text beginning around two fifths of the page width, balanced by left-aligned photography.
- **profile-reading** (only for profile directories): max width 739px. Reading column offset about 30% of the viewport from the left; the visible paragraph width is about 538px while large names remain near the left edge.

## Corner radius

| Element | Radius |
| --- | --- |
| media | 0px |
| carousel-controls | 50% |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** All ordinary page regions, including the footer.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Content is placed directly on the page, without alternating colored bands, card outlines or elevation.

**Transfer:** Group with alignment and space rather than filled containers.

#### Navigation strip · level 1

**Use:** Desktop navigation layer.

**CSS:** `background-color: #ffffff; padding: 21px; display: flex; justify-content: space-between; align-items: flex-start`

**Observed:** A full-width white toolbar separates primary categories at left from utilities at right; it has no shadow or lower rule.

**Transfer:** Preserve the thin catalogue-header character rather than making an app toolbar.

## Components

### Navigation link

**Use:** Primary section navigation.

**CSS:** `color: #000000; margin-right: 17.7px`

**Text style:** `navigation` — MessinaSansWeb 400 · 17.7px/1.2 · tracking -0.03em

**Observed:** Single horizontal run at the left; the current section is underlined.

**States:** Declared: hover opacity 0.6 and outline 0px; active outline 0px.

### Utility control

**Use:** Cart and language actions at the right of navigation.

**CSS:** `color: #000000; margin-left: 17.7px; text-align: center`

**Text style:** `utility` — MessinaSansWeb 400 · 17.7px/1.2

**Observed:** Plain text buttons; cart count appears inside parentheses and language choices follow it.

**States:** Declared: hover opacity 0.6.

### Identity anchor

**Use:** Prominent identity above the opening and again in the footer.

**CSS:** `width: 328.5px; object-fit: contain`

**Observed:** A wide black wordmark with a roughly 4.8:1 aspect ratio; the top version is right-aligned and the footer version is left-aligned.

**Transfer:** Use the new identity's own wordmark. If only a name exists, typeset it as simple black vector lettering in a similarly wide lockup.

### Editorial media tile

**Use:** Image-led announcements and stories.

**CSS:** `margin-right: 21px`

**Text style:** `editorial-body` — MessinaSansWeb 500 · 18.7px/24px

**Observed:** The linked image precedes an unboxed text caption with 27.1px separation. A two-column tile uses a 689px square image and about 507px of copy width; three-column versions use 452px squares.

**Transfer:** Let the entire image and caption form the entry point rather than adding a separate filled CTA.

### Product metadata

**Use:** Compact identification beneath catalogue media.

**CSS:** `margin-top: 14px; color: #000000`

**Text style:** `product-meta` — MessinaSansWeb 400 · 14px/1.4

**Observed:** Name, designer credit and price are stacked, left-aligned and visually equal; no rating stars or sale badges.

**Transfer:** For non-retail products, use name, maker or category, and a short factual specification.

### Carousel arrow

**Use:** Advance image galleries or case-study strips.

**CSS:** `width: 24px; height: 24px; border-radius: 50%; padding: 1px 6px; color: #333333`

**Observed:** An unfilled-looking circular control containing a 14px chevron, placed near the right edge below the images. Profile galleries pair previous and next controls.

**States:** Declared: hover background #ffffff and opacity 0.6; active opacity 0.6.

### Footer contact cluster

**Use:** Contact, service and subscription destinations.

**CSS:** `display: flex; justify-content: flex-start; padding-top: 28px`

**Text style:** `footer` — MessinaSansWeb 400 · 12px/1.3

**Observed:** A multiline address starts the cluster, followed by short service columns separated by about 42px. Subscription is a text link, not an exposed form; social icons occupy the distant lower right.

**States:** Declared: hover opacity 0.6 and outline 0px on links; active outline 0px.

### Profile product link

**Only for:** profile directories

**Use:** Connect an editorial profile to its associated collection.

**CSS:** `color: #000000; display: inline`

**Text style:** `reading-body` — MessinaSansWeb 300 · 20.5px/1.4

**Observed:** Three-digit zero-padded count precedes the collection description; View sits on the next line. It is a modest continuation of the reading text, not a button.

**States:** Declared: hover opacity 0.6, outline 0px and background-image none; active outline 0px.

### Directory index link

**Only for:** profile directories

**Use:** Jump from a list of names to detailed chapters.

**CSS:** `position: relative; color: #000000`

**Text style:** `directory-index` — MessinaSansWeb 300 · 37.3px/1.45

**Observed:** One name per row in a right-offset column, with a right-arrow graphic associated with the link. Rows follow a 54.1px line rhythm.

**States:** Declared: hover outline 0px; active outline 0px.

## Imagery and graphics

### Material-led architectural photography

**Use:** Primary opening media and expansive editorial chapters.

**Observed:** Objects are shown in real interiors with concrete, timber, stone and views of green landscape. Directional daylight produces long soft-edged shadows; beige, olive, charcoal and weathered gray dominate. Images fill sharp rectangular frames without tinted overlays or text overprint.

**Transfer:** Photograph the new product in a believable setting that reveals scale, surface and use. If the product is digital, show its physical setting and human context as well as a clear working view; maintain daylight and tactile surroundings.

### Process study

**Use:** A contrasting editorial companion to finished-product photography.

**Observed:** The opening pairs a sunlit product scene with a black-line interior sketch on textured white paper. Loose translucent green, blue and yellow washes sit behind irregular architectural outlines.

**Transfer:** Pair a finished outcome with a drawn spatial or process study. A simple original diagram on subtly textured white is sufficient when bespoke illustration is impractical.

**Build:** Use a white paper base with very low-contrast gray grain. Draw the product's main planes as slightly irregular black SVG paths with no solid fill. Place translucent vertical watercolor-like rectangles behind them, allowing blue, green and yellow washes to overlap softly; keep most of the paper visible. Confine the artwork to the media frame, never the page background.

### Portrait and object triptych

**Only for:** profile directories

**Use:** Introduce each profile before its text chapter.

**Observed:** Three 547px square images run horizontally with about 20px gaps and partial images beyond the viewport edges. Monochrome portraits are paired with colored material details, finished objects, sketches or interiors.

**Transfer:** Use one human portrait between complementary evidence of work and process. Keep photographic contrast natural and allow offscreen continuation rather than reducing everything to small thumbnails.

### Landscape and built context

**Only for:** company narratives

**Use:** Counterbalance offset paragraphs with broad place imagery.

**Observed:** A left-aligned landscape image approximately 979×775px is followed later by a nearly page-wide 1398×945px architectural photograph. Dense coastal vegetation, timber buildings and overcast skies carry subdued natural colors.

**Transfer:** Show the product's origin or operating environment with an honest broad scene; preserve the asymmetry between narrow reading column and expansive image.

### Icons

**Observed:** Small charcoal filled SVG chevrons at 14×14px sit inside 24px gallery controls. Footer social marks are black, approximately 24×24px and 24×25px; iconography is otherwise sparse.

**Transfer:** Use only directional and utility symbols needed for interaction; keep decorative icon grids out of editorial chapters.

## Section recipes

How recurring sections are built.

### First screen: Paired editorial opening

**Observed:** A thin white navigation strip occupies about 63px at the top. After 56px of air, Identity anchor is placed at the upper right; its 329×68px box is the only headline-like mark. A 21px gap leads into two equal 689px square Editorial media tiles across the fluid content width. The back-to-front layers are simply white canvas, sharp-edged imagery, then captions below the images; there are no overlays. At 900px height the navigation, identity and almost all of both images are visible, while the 18.7px/24px editorial captions start just below the fold. Main actions are the navigation and linked media, not a hero button.

**Transfer:** Make the default landing page image-first: pair a finished-product or use-context scene with process, material or conceptual imagery. If there is no campaign photography, create an honest prototype photograph and original process drawing. Company narratives instead open with a right-offset reading paragraph and left-aligned contextual image; profile directories open with a 24.3px introductory paragraph, process image and linked index.

**Avoid:** Do not insert a centered oversized promise, overlay headline, floating pill CTA or full-bleed tinted hero over this composition.

**Text style:** `editorial-body` — MessinaSansWeb 500 · 18.7px/24px

### Image chapter grid

**Observed:** Editorial media tiles form equal pairs or trios, using the editorial-pair and editorial-trio layouts on White canvas. Short copy remains below the media; major landing chapters pause for 423px before the next group.

**Transfer:** Alternate scales to distinguish major stories from secondary updates, without requiring the same number or order of chapters.

**Text style:** `editorial-body` — MessinaSansWeb 500 · 18.7px/24px

### Catalogue proof

**Observed:** A short left-aligned introduction precedes a four-column product-row. Square images lead to Product metadata with 14px separation. Another arrangement places a large left product image beside a two-by-two cluster of small product tiles.

**Transfer:** Show a small curated set of real products, outcomes or concrete capabilities with factual labels; keep the media hierarchy rather than adding card shells.

**Text style:** `product-meta` — MessinaSansWeb 400 · 14px/1.4

### Panoramic story

**Observed:** A 1398×933px image occupies the full content width, followed by a 70px gap and a narrow editorial caption. It is surrounded by the same long chapter pauses as the smaller grids.

**Transfer:** Use a large contextual image as a breath between denser comparison or catalogue blocks.

**Text style:** `editorial-body` — MessinaSansWeb 500 · 18.7px/24px

### Portrait case-study strip

**Observed:** Portrait imagery about 506×763px sits in a horizontally continuing strip. Story-title follows after 27.1px and editorial-body follows after 13.5px. A Carousel arrow sits below at the right.

**Transfer:** Use tall contextual scenes for deeper stories and let the next item continue offscreen, rather than shrinking every story to fit.

**Text style:** `story-title` — MessinaSansWeb 500 · 27.1px/35px · tracking -1px

### Identity-led ending

**Observed:** Related media or the final narrative yields to about 279.9px of white space before Identity anchor returns at the left. A roughly 342px footer combines that identity with Footer contact cluster, leaving about 148px between the identity image and the first text. Social icons are isolated at the lower right. There is no closing colored band or giant conversion slogan.

**Transfer:** Close with the new identity, practical routes to contact or explore, and a restrained subscription link. Keep the asymmetrical distribution and the white interval rather than manufacturing a new campaign finale.

**Text style:** `footer` — MessinaSansWeb 400 · 12px/1.3

### Profile chapter

**Only for:** profile directories

**Observed:** Portrait and object triptych comes first, followed by right-aligned Carousel arrows. A 56px regular profile-heading is anchored left; reading-body is offset about 30% across the viewport, with 46.7px separation from the heading. Paragraphs end in Profile product link, and chapters are separated by about 168px.

**Transfer:** Adapt for makers, specialists or partners with substantial narratives. Preserve the split between names on the left and prose further right.

**Text style:** `profile-heading` — MessinaSansWeb 400 · 56px/1

### Offset narrative

**Only for:** company narratives

**Observed:** Reading-body occupies a 698px column offset to the right. Paragraph gaps are about 20.5px, while large left-aligned or full-width contextual photographs punctuate the text; there is no conventional giant page title.

**Transfer:** Explain a product philosophy, origin or operating approach with a few substantial paragraphs and material context rather than a values-card grid.

**Text style:** `reading-body` — MessinaSansWeb 300 · 20.5px/1.4

## Page flow

**Storyline:** Visual invitation → curated outcomes → context and making → deeper stories → practical identity-led close.

### An editorial marketing landing page that mixes discovery and catalogue access

1. **Visual invitation** — Right-aligned identity above paired finished-product and conceptual media.
2. **Discovery** — Three-column editorial updates and a compact four-product row.
3. **Contextual proof** — Paired stories, one expansive image chapter and a short material-production introduction.
4. **Product exploration** — Asymmetrical large-and-small product grouping.
5. **Deeper proof** — Portrait case-study carousel and three related media links.
6. **Practical close** — Left identity, small contact/service columns and distant social icons.

**Transfer:** Use the default image-led approach for a new product landing page; select only the chapter types supported by meaningful content, preserving varied image scales and the identity-led ending.

### A long directory that turns collaborators into editorial proof

1. **Context** — Identity, offset introduction and process photograph.
2. **Wayfinding** — Large linked name index.
3. **Credibility chapters** — Repeated triptych galleries, left names, offset biographies and counted collection links.
4. **Practical close** — The same white identity-led footer after the final profile.

**Transfer:** Use for people, partners or specialists, with chapters sized to the material rather than forced equal heights.

### A concise long-form narrative about approach and origin

1. **Positioning** — Right-offset introductory paragraphs, followed by a left landscape photograph.
2. **Rationale** — A second group of paragraphs develops materials, production and ownership.
3. **Contextual proof** — A page-width architectural image.
4. **Practical close** — White interval and shared identity-led footer.

**Transfer:** Use for philosophy or provenance narratives; communicate through prose and contextual photography instead of cards or numerical stats.

## Writing

Cultured, descriptive and materially specific, with confident but unhurried enthusiasm. Products and projects are discussed as considered objects in real places, with credit given to their makers.

**Do not copy:** Do not reuse Resident's identity artwork, product names, designer names, addresses, prices, anniversaries, origin claims or project descriptions. Source examples illustrate sentence construction, not claims to transplant.

- **Addressing the reader:** Mostly third-person descriptions of the brand, product or collaborator; we and our introduce collective beliefs. Direct second-person persuasion is uncommon.
- **Rhythm:** Short functional labels alternate with substantial descriptive paragraphs. Story titles are usually proper names; supporting text often uses two or three sentences, rather than a stack of slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Announcement | A brief classification followed by an introduction naming the object and its maker. | Label plus a short paragraph | “New Release. [Brand] is proud to introduce the Avant Lounge Chair by NOTE (design studio).” |
| Story title | A project or place name, with credit when useful. | 2–7 words | “RK Residence by Seear-Budd Ross”<br>“The Cloisters” |
| Narrative support | Connect conceptual intent to materials, use and lived experience. | One substantial paragraph | “We are dedicated to creating pieces that elevate the living experience for the design-conscious, fostering an environment of enlightened, modern living.” |
| Action | Plain destination or literal verb, without urgency. | 1–5 words | “Meet the Designers”<br>“View”<br>“Subscribe to our emails” |

**Words and phrasing to use:** materiality; form; considered; craftsmanship; enduring; contemporary; refined; collaboration

**Avoid:** game-changing; 10x; disrupt; hurry; unlock your potential; best ever

**Rules:**

- Name a concrete material, setting or process when describing quality.
- Give makers and collaborators credit as part of the product story.
- Use sentence case and restrained punctuation; action labels should describe the destination.
- Substantiate longevity and craft with actual construction or process information rather than repeating luxury adjectives.

## Do's and Don'ts

### Do

- Keep the desktop canvas fluid with 21px side padding rather than centering it in a narrow frame.
- Use paired 689px square images for the opening at 1440px.
- Keep product metadata at 14px/1.4 and let images do the selling.
- Use 18.7px/24px editorial captions beneath, not over, photographs.
- Retain 24px circular arrow controls with 14px chevrons.
- Give the footer its own 329×68px identity anchor at the left.
- Reserve the 56px regular headings for profile-style content.
- Maintain long chapter pauses instead of filling every viewport with copy.

### Don't

- Do not introduce a brand accent color into navigation, page bands or action fills; color is carried by media.
- Do not round photo corners or add card shadows; media edges are square.
- Do not convert the text-link system into solid pill buttons.
- Do not give prices a larger or bolder style than product names.
- Do not replace the right-offset narrative column with centered promotional text.
- Do not apply negative tracking to long-form reading text; it remains normal.
- Do not populate the layout with decorative feature icons; utility symbols are sparse.
- Do not force every section into the same image aspect ratio; squares, tall case studies and broad context scenes have distinct roles.

## Motion and responsive

### Motion

**Observed:**

- Action hover states commonly reduce opacity to 0.6.
- Declared transitions include transform 0.5s, transform 0.8s with background-color 0.8s, and opacity 0.5s with a 0.5s delay.
- Carousel controls expose previous and next navigation; horizontal galleries allow imagery to continue beyond the viewport.

**Transfer:**

- Keep interaction visually lightweight: opacity feedback on text actions and horizontal continuation for image collections.

**Unknown:**

- Exact transition-to-component mapping, carousel travel timing and scroll-header behavior are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 430px, 667px, 668px, 767px, 768px, 959px, 1150px, 1493px, 1494px, 1706px and 1707px.

**Transfer:**

- On narrow layouts, preserve readable captions and square media by reducing column count; do not miniaturize the desktop opening.
- Reduce the large narrative-column offset when it would squeeze prose; keep its contrast with broader contextual imagery.
- Keep the identity's aspect ratio and the direction change from upper-right opening to left-aligned ending.

**Unknown:**

- Mobile navigation construction, exact column-collapse rules and mobile type sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
