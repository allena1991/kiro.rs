# komoot — playful field notes

## Overview

An outdoorsy, human marketing style that mixes warm paper, mossy greens and sunlit photography with the energy of a well-used adventure journal. Rounded geometric sans headings sit beside practical interface text, hand-lettered asides and flat cut-paper symbols. It suits products that connect useful tools to real experiences: spacious and image-led in its marketing, denser and more utilitarian in its discovery and detail views.

### Essentials

- A cinematic invitation rather than a dashboard introduction: edge-to-edge human activity imagery fills the first 900px, with a centered 72px/1.25 medium-weight headline in white and compact paired actions beneath.
- Headlines feel rounded, not heavy or compressed: Nohemi 500 at 48px/1.2 with 0.02em tracking for capability statements, and 40px/1.08 with 0.018em tracking for section leads.
- Paper carries most of the story: #f5f3ec is the dominant canvas, #ede9de groups selected moments, and #212512 anchors the ending. Orange and violet appear as small graphic punctuations, while olive green owns ordinary primary actions.
- Buttons are soft rectangles, not capsules: 16px corners, 12px 16px padding and 14px/1.35 bold labels by default; white is the primary-action treatment over the opening film.
- Product proof is an assembled field journal: rounded photographs and interface fragments overlap at small angles beside flat orange, violet and yellow-green symbols. Include this handmade layer even for a software-only product, using a real workflow image and a simplified interface fragment.
- Friendly marginalia interrupts the orderly grid: Boyrun notes at 24px or 36px, lightly rotated, accompany clean type; oversized flat symbols also become 250px square category tiles with 12px corners.
- The ending returns to experience: a green-toned photographic call-to-action with a compact row of cream silhouettes precedes a deep-olive four-column footer. Use the new product's own activity scene and simple purpose-related silhouettes rather than omitting this visual sign-off.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action green | `#4f6814` | `--color-action` | action, link, accent | Primary buttons, checkmarks and handwritten notes. |
| Sand action | `#e3d2b4` | `--color-sand` | action | Secondary buttons on paper and green-toned closing photography. |
| Forest olive | `#404823` | `--color-olive` | text, surface | Secondary-action labels, flat illustrations, inverted category tiles and footer selector. |
| Deep olive | `#212512` | `--color-footer` | background | Full-width footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Trail orange | `#ee6b17` | `--color-orange` | accent, text, action | Small graphic marks, numbered steps and highlighted phrases; solid action fills only in creator-tool sections. |
| Journal violet | `#8879e1` | `--color-violet` | accent, text, action | Flat doodles and handwritten interludes; paid-tier actions in their scoped band. |
| Soft orange | `#fce1d1` | `--color-peach` | action, surface | Small app shortcut background in navigation. |
| Pale sage | `#d8dab3` | `--color-sage` | surface | Small statistical proof tile. |
| Lavender paper | `#e7e3ff` | `--color-lavender` | surface, background | Tall proof tile; paid-tier promotional band. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Earth text | `#736554` | `--color-muted` | text | Secondary copy, captions and supporting prose. |
| Warm ink | `#1c1a18` | `--color-ink` | text | Primary text on light surfaces. |
| Divider | `#d1cdc4` | `--color-rule` | border | Tab separators and utility panel outlines. |
| Warm card edge | `#e0dbce` | `--color-border` | border, surface | Fine outlines on white cards and selected tabs; inset signup panels. |
| Paper shade | `#ede9de` | `--color-stone` | surface, background | Grouped promotional panels, interludes and category tiles. |
| Warm paper | `#f5f3ec` | `--color-canvas` | background, text | Dominant page canvas and labels on green actions. |
| Light cream | `#faf9f4` | `--color-cream` | text | Text over photographic cards and the closing scene. |
| White | `#ffffff` | `--color-white` | surface, text, action | Opening headline and white hero action; utility cards and panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| creator tools and integration pages | Instruction citron | `#dedd95` | `--color-citron` | background | Broad rounded how-it-works panel. |

## Typography

- **Nohemi** — Marketing headings, card titles and proof numbers. Rounded geometric sans with open counters and a friendly medium weight. If unavailable, use **Outfit**. Use 500; retain the positive tracking and uncompressed width. Font stack: "Nohemi", "Outfit", system-ui, sans-serif.
- **Satoshi** — Body text, navigation, labels and buttons. Clean geometric sans, matter-of-fact at medium weight with bold action labels. If unavailable, use **DM Sans**. Use 500 and 700; match the compact line spacing. Font stack: "Satoshi", "DM Sans", system-ui, sans-serif.
- **Boyrun** — Short handwritten notes around illustrations, headings and interludes. Uneven, narrow hand-drawn lettering, used as a personal annotation rather than body text. If unavailable, use **Caveat**. Use short phrases and 400–500 weights; keep the note visually secondary. Font stack: "Boyrun", "Caveat", Satoshi, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| hero | Nohemi | 500 | 72px | 1.25 | 0.01em | Centered first-screen promise on full-bleed imagery. |
| capability | Nohemi | 500 | 48px | 1.2 | 0.02em | Major capability statements; also split product-page opening headlines. |
| heading | Nohemi | 500 | 40px | 1.08 | 0.018em | Section headings, closing calls and prominent statistical values. |
| interlude-copy | Nohemi | 500 | 28px | 1.35 | 0.017em | Centered, several-line editorial statement in earth-colored text. |
| card-title | Nohemi | 500 | 24px | 1.3 | 0.03em | Photo-card and category-tile titles. |
| body-lead | Satoshi | 500 | 18px | 1.35 | normal | Capability paragraphs beside collages. |
| footer-heading | Nohemi | 500 | 18px | 1.3 | 0.03em | Footer column headings. |
| body | Satoshi | 500 | 16px | 1.35 | normal | Compact promotional prose and detail introductions. |
| button | Satoshi | 700 | 14px | 1.35 | normal | Default buttons, small action links and navigation actions. |
| small | Satoshi | 500 | 14px | 1.35 | normal | Navigation, card attribution and directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| discovery directories | directory-hero | Satoshi | 700 | 48px | 1.5 | normal | Centered title on a directory photo hero. |
| discovery directories | directory-heading | Satoshi | 700 | 36px | 1.5 | normal | Centered related-content and closing headings. |
| creator tools and editorial detail pages | subheading | Nohemi | 500 | 20px | 1.3 | 0.03em | Small benefit-card and detail-entry headings. |
| feature explanations and creator tools | button-expanded | Satoshi | 700 | 16px | 1.35 | normal | 54px feature-page actions and creator-tool actions. |
| creator tools and integration pages | tool-body | Satoshi | 500 | 16px | 1.4 | normal | Explanatory tool copy. |
| creator tools and integration pages | tool-eyebrow | Satoshi | 700 | 12px | 1.4 | 0.18em, uppercase | Orange labels above explanatory tool headings. |

**Notes:**

- Keep the display weight at 500: hierarchy comes from size, composition and line breaks, not extra-bold type.
- Positive display tracking is deliberate. Body and action text use normal tracking.
- Handwritten notes use Boyrun 400 at 24px with 0.03em tracking and normal line height; the interlude note uses Boyrun 500 at 36px with 1px tracking and normal line height. Keep them short, secondary and off-axis by approximately 5–8 degrees.
- Feature explanations can emphasize a short final phrase in orange while keeping the rest of the headline in warm ink. Discovery directories instead use bold Satoshi headings.

## Layout

**Density:** Airy marketing sections with compact controls and attribution; utility and directory variants become denser without changing the warm framing.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing and tight directory link stacks. |
| 12px | Paired action spacing, photo-card gaps within content, footer link rhythm and proof mosaic gutters. |
| 16px | Carousel gutters and small content-group spacing. |
| 24px | Standard card padding and headline-to-capability-copy separation. |
| 32px | Promotional heading-to-copy gaps and proof-tile padding. |
| 40px | Text-to-art separation and promotional copy-to-action spacing. |
| 48px | Capability copy-to-action separation and proof header-to-mosaic gap. |
| 80px | Gaps between capability chapters and footer vertical padding. |
| 120px | Default marketing section padding and desktop side gutters. |
| 224px | Broad vertical breathing room for an editorial interlude. |

### Containers and grids

- **marketing-container**: max width 1440px · side padding 120px. Centered outer frame giving 1200px of usable content at desktop.
- **capability-split**: 2 columns · gap 40px. Text occupies about 40% of the content width; an oversized collage occupies the other side. Alternate sides by chapter.
- **photo-rail**: gap 16px · side padding 120px. Horizontal overflow rail of 320px by 420px photo cards; retain a partial next card rather than squeezing all cards to fit.
- **footer-grid**: 4 columns · gap 28px. Equal footer columns within the marketing container.
- **tool-container** (only for creator tools and integration pages): max width 1440px · side padding 72px. Wider explanatory layout; the interactive generator expands to 1328px with a 380px settings column and 24px gap to preview.
- **faq-column** (only for creator tools and integration pages): max width 960px · gap 12px. Centered stack of disclosure rows.
- **detail-split** (only for editorial detail pages): 2 columns · gap 24px · side padding 24px. 640px narrative card column paired with an approximately 696px sticky map or equivalent contextual viewer.
- **directory-grid** (only for discovery directories): 4 columns · gap 1px · side padding 36px. Dense rectangular image mosaic inside a white content sheet inset 48px from the outer canvas.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 16px |
|  | marketing-panels-and-photo-cards | 24px |
|  | category-tiles | 12px |
|  | round-controls | 50% |
| creator tools and editorial detail pages | utility-cards | 20px |
| creator tools and integration pages | instruction-panel | 32px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| small-floating-control | `0px 1px 2px 0px rgba(0, 0, 0, 0.2)` | White circular carousel controls. |
| raised-control | `0px 4px 8px 0px rgba(0, 0, 0, 0.1)` | Raised previous controls and small utility overlays. |

### Surfaces

#### Paper canvas · level 0

**Use:** Ordinary marketing page background.

**CSS:** `background: #f5f3ec`

**Observed:** Warm and flat, with no paper grain texture.

**Transfer:** Let photographs and assembled graphics provide texture instead of texturing the canvas.

#### Inset paper panel · level 1

**Use:** Prominent product promotion and selected grouped content.

**CSS:** `background: #ede9de; border-radius: 24px; padding: 40px 60px`

**Observed:** A broad, borderless slab framed by the lighter canvas.

**Transfer:** Use for a meaningful conversion or explanation, not behind every chapter.

#### Lavender proof tile · level 1

**Use:** Emphasized statistic in a mixed photo-and-number mosaic.

**CSS:** `background: #e7e3ff; border-radius: 24px; padding: 32px`

**Observed:** Tall, flat and centered; paired with smaller stone and sage tiles.

**Transfer:** Give the leading metric vertical presence without enlarging it beyond the 40px heading scale.

#### Deep olive ending · level 0

**Use:** Footer background.

**CSS:** `background: #212512; color: #f5f3ec; padding: 80px 120px`

**Observed:** The stable dark ending contrasts with the light body rather than establishing a dark theme.

**Transfer:** Carry all navigation, support and legal content here without introducing a black footer.

#### White outlined card · level 1

**Only for:** feature overview and proof grids

**Use:** Capability jump cards and statistical proof cards.

**CSS:** `background: #ffffff; border: 1.5px solid #e0dbce; border-radius: 24px; padding: 24px`

**Observed:** Thin warm edge, no default heavy shadow.

**Transfer:** Use the outline to separate white from warm paper.

#### Citron instruction panel · level 1

**Only for:** creator tools and integration pages

**Use:** Contained how-it-works sequence.

**CSS:** `background: #dedd95; border-radius: 32px; padding: 56px`

**Observed:** Three white inset step cards and an orange action sit within one colored slab.

**Transfer:** Keep the tinted panel bounded by broad paper margins.

## Components

### Primary button

**Use:** Ordinary conversion action on paper.

**CSS:** `background: #4f6814; color: #f5f3ec; border-radius: 16px; padding: 12px 16px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `button` — Satoshi 700 · 14px/1.35

**Observed:** Content-width action, about 43px high. Feature explanations use the expanded label recipe and 16px padding for a 54px action.

**States:** Declared: hover changes primary fill and label through theme tokens; focus-visible uses a 3px rgba(66, 153, 225, 0.5) ring and 2px outline offset.

### Hero white button

**Use:** Primary conversion on full-bleed opening imagery.

**CSS:** `background: #ffffff; color: #1c1a18; border-radius: 16px; padding: 12px 16px`

**Text style:** `button` — Satoshi 700 · 14px/1.35

**Observed:** A compact white action paired with a green returning-user action, separated by 12px.

### Secondary button

**Use:** Alternative conversion or transfer action.

**CSS:** `background: #e3d2b4; color: #404823; border-radius: 16px; padding: 12px 16px; display: inline-flex; gap: 8px; align-items: center`

**Text style:** `button` — Satoshi 700 · 14px/1.35

**Observed:** May have a leading outline icon; also supplies the closing scene's conversion action.

### Fixed navigation

**Use:** Persistent global navigation.

**CSS:** `position: fixed; height: 66px; padding: 0px 16px; display: flex; justify-content: space-between; align-items: center; z-index: 600`

**Text style:** `small` — Satoshi 500 · 14px/1.35

**Observed:** Compact logo at left, short text links and two highlighted actions at right. It is visually transparent over the opening film with cream labels; on light content it becomes paper-colored with ink labels. App shortcut is peach with an orange icon; authentication is green.

**Transfer:** Use a small product mark and a short capability navigation rather than a sprawling mega-menu.

### Photo story card

**Use:** Curated stories, recommendations and browsable content.

**CSS:** `background-color: #404823; border-radius: 24px; width: 320px; height: 420px; padding: 24px; display: flex; flex-direction: column; justify-content: flex-end; position: relative; overflow: hidden`

**Text style:** `card-title` — Nohemi 500 · 24px/1.3 · tracking 0.03em

**Observed:** Cover photography fills the card; a warm dark gradient supports bottom-aligned cream title, smaller content-type and creator lines, plus a bold diagonal arrow at bottom right. Some activity cards add a small status badge at top left.

**Transfer:** Use case studies or examples as photographic stories with short attribution, not flat generic feature boxes.

### Category symbol tile

**Use:** Graphic browsing by category.

**CSS:** `background: #ede9de; color: #404823; border-radius: 12px; width: 250px; height: 250px; padding: 16px 20px; display: flex; flex-direction: column; justify-content: flex-end; gap: 12px`

**Text style:** `card-title` — Nohemi 500 · 24px/1.3 · tracking 0.03em

**Observed:** Large flat pictogram fills the upper portion; short label and diagonal arrow share the bottom. The emphasized tile inverts to olive with cream content and appears enlarged and tilted.

**States:** Declared: hover switches to green fill with white content and transform rotate(-2deg) scale(1.1); focus-visible uses a 3px rgba(66, 153, 225, 0.5) ring.

**Transfer:** Create chunky category silhouettes with meaningful negative space rather than adding stock line icons at oversized scale.

### Statistic tile

**Use:** Large-scale proof adjacent to an experience photograph.

**CSS:** `background: #e7e3ff; border-radius: 24px; padding: 32px; display: flex; flex-direction: column; justify-content: center; align-items: center; gap: 16px; text-align: center`

**Text style:** `heading` — Nohemi 500 · 40px/1.08 · tracking 0.018em

**Observed:** A 40px number sits over compact 16px explanation. One tall tile is paired with two stacked smaller stone and sage tiles; numbers remain unadorned apart from a plus suffix.

**Transfer:** Use verified measures with short human-readable explanations.

### Footer columns

**Use:** Shared final navigation and support region.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 28px; color: #f5f3ec`

**Text style:** `small` — Satoshi 500 · 14px/1.35

**Observed:** Small cream mark above four link columns with display-family headings. Beneath: app badges on the left, social icons toward the right, then copyright and a compact legal row with an olive language selector. Links have roughly 12px vertical gaps.

**Transfer:** Preserve the generous dark field and modest text sizes while adapting the information architecture.

### Feature jump card

**Only for:** feature overview pages

**Use:** Short visual index linking to capability chapters.

**CSS:** `background: #ffffff; border: 1.5px solid #e0dbce; border-radius: 24px; padding: 24px; display: flex; flex-direction: column; gap: 20px; transition: transform 200ms, box-shadow 200ms`

**Text style:** `card-title` — Nohemi 500 · 24px/1.3 · tracking 0.03em

**Observed:** Illustration above a short title and one supporting line, arranged in an overflowing horizontal row.

**States:** Declared: hover translateY(-4px) and box-shadow 0px 8px 20px rgba(0, 0, 0, 0.1); focus-visible uses a 3px rgba(66, 153, 225, 0.5) ring.

### FAQ disclosure

**Only for:** creator tools and integration pages

**Use:** Resolve specific implementation objections.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 20px; max-width: 960px`

**Text style:** `button` — Satoshi 700 · 14px/1.35

**Observed:** Question aligned left, small plus aligned right; default rows are about 60px high with 12px gaps. Expanded answers use small earth-colored prose and inline code where needed.

**Transfer:** Use concrete user questions and native disclosure semantics.

### Tool action

**Only for:** creator tools and integration pages

**Use:** Begin or return to an interactive generator.

**CSS:** `background: #ee6b17; color: #ffffff; border-radius: 16px; padding: 16px 24px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button-expanded` — Satoshi 700 · 16px/1.35

**Observed:** Orange is reserved for the tool's start actions; the rest of the page retains the green global controls.

## Imagery and graphics

### Human experience film

**Use:** Full-bleed opening scene.

**Observed:** Immersive close-to-the-action footage: a walker passing mossy rocks and tree trunks, deep green shadows and tactile natural detail. The image is darkened enough for white center text; it fills the viewport rather than appearing inside a device frame.

**Transfer:** Show the user's real activity, craft or working environment. If film is unavailable, use one strong documentary still with a quiet central text zone; retain the full-bleed experiential scale.

### Assembled product journal

**Use:** Capability chapters and product promotion.

**Observed:** Natural-light experience photos mix with pale maps, phones and small interface cards. Elements overlap and tilt slightly; white or cream edges, dark hand-drawn outlines, low soft shadows and colored symbols create a tactile scrapbook effect on the paper canvas. Artwork commonly occupies half the section, about 600px across.

**Transfer:** Combine one authentic use-context photograph with one recognizable output or interface fragment. Minimum version: one rounded photograph, one offset white mini-panel, one flat symbol and a small handwritten label.

**Build:** Compose a relative 600px square stage. Put a rounded photograph over a larger cream interface rectangle; rotate the two in opposite directions by a few degrees. Add a narrow ink-outline label, a violet SVG wave or burst at one exposed corner, and an orange or green marker near another. Keep shadows low-opacity and leave substantial paper visible between the collage and text.

### Flat field symbols

**Use:** Marginal decoration, category browsing and the closing silhouette row.

**Observed:** Bold imperfect cut-paper forms: multi-rayed sunbursts, four-petal leaves, angular peaks, tents and repeated waves. Marks are single-color violet, orange or yellow-green; browsing tiles use olive and cream. They are flat, without gradients or bevels.

**Transfer:** Develop an equivalent small family of chunky shapes related to the new product. Repeat the same shapes at annotation, category and closing scales.

**Build:** Use SVG polygons and compound paths with uneven angles and generous negative-space cutouts. Build a burst from 12–16 narrow radial rectangles or triangular rays, a leaf mark from four pointed oval paths, and waves from three parallel round-ended paths. Use palette fills at full opacity; rotate individual marks slightly and place them outside the main text block, never as an all-over pattern.

### Warm shaded photo cards

**Use:** Horizontal story rails.

**Observed:** Vivid but natural landscapes and people, cover-framed into rounded portrait cards. The bottom is shaded warm brown-black rather than a cool blue overlay, with cream text anchored low.

**Transfer:** Choose photographs with enough atmosphere and lower-half visual simplicity to carry titles. Preserve real color above the shaded area.

**Build:** Place an absolute cover image behind content and a linear-gradient(rgba(39,35,21,0.5) 0%, rgba(39,35,21,0) 40.87%, rgba(39,35,21,0.7) 60.44%, rgba(39,35,21,0.7) 82.21%) layer. Clip all layers to the Photo story card radius.

### Green photographic sign-off

**Use:** Emotional closing call before the footer.

**Observed:** Wide woodland cycling scene treated as a muted olive-green duotone. A row of five cream cutout silhouettes sits above a centered two-line cream heading and sand action; the photo runs edge to edge and is about 658px tall.

**Transfer:** Use an authentic image of the new product in action with an olive wash, then repeat its flat symbol family above the closing line.

**Build:** Cover-fill a wide section with a documentary image, desaturate it and layer a semi-transparent olive color wash until midtones read green while texture remains visible. Center a roughly 458px by 120px SVG symbol strip above the 40px heading. Match the muted duotone by eye; exact color stops are not essential.

### Editorial gallery and contextual viewer

**Only for:** editorial detail pages

**Use:** Long-form story and repeated activity entries.

**Observed:** Wide uncropped-feeling destination photo follows a dense title introduction. Repeated entries combine one large photo with two smaller stacked photos in a rounded gallery, while a pale topographic route map stays visible alongside the scrolling narrative.

**Transfer:** Use project galleries with a persistent contextual diagram, timeline or location viewer appropriate to the content; do not impose map imagery on unrelated products.

### Icons

**Observed:** Interface icons are mostly 20px outline SVGs with 1.5px strokes and round caps, in earth, ink or cream. Solid 20px symbols and orange circles appear for activity markers; social icons are about 28px. Graphic category symbols are deliberately much larger and chunkier than UI icons.

**Transfer:** Use a coherent round-capped outline set for controls. Keep the custom flat silhouette family separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Cinematic invitation

**Observed:** A viewport-filling activity scene is the back layer, followed by a dark translucent treatment, compact navigation, then a centered stack: a bright flat emblem, the white hero headline within a 640px measure, paired Hero white button and Primary button actions 12px apart, and a short handwritten question below. At desktop the headline is two lines at 72px/1.25; the core stack uses approximately 32px gaps. In the first 900px the navigation, emblem, headline, both actions and handwritten note are visible, while the next paper promotion remains below the fold. There is no boxed hero content or competing side panel.

**Transfer:** Use a short outcome promise and a real activity photograph or film with enough dark central space. Replace the emblem with a simple product-relevant flat silhouette. Feature-led pages can instead open as a paper split with 48px headline and a three-device collage; creator tools use a shorter paper split and bring the generator into the first viewport. Editorial details lead with title, attribution and metadata; directories lead with photo, title and search.

**Avoid:** Do not replace the immersive scene with a small floating device on an empty colored background, or add a long body paragraph to the centered film composition.

**Text style:** `hero` — Nohemi 500 · 72px/1.25 · tracking 0.01em

### Capability and collage

**Observed:** Marketing-container with Capability-split: a 48px capability headline, 18px supporting paragraph after 24px, and a compact action pair after 48px. Oversized assembled artwork sits opposite and alternates sides in successive chapters; chapter gaps are 80px. Feature explanations use 40px section heads with an orange phrase and short checkmark lists.

**Transfer:** Explain one job or benefit per chapter and let the collage show the use context plus the functional proof.

**Text style:** `capability` — Nohemi 500 · 48px/1.2 · tracking 0.02em

### Promotion in paper

**Observed:** Inset paper panel spanning the content width, with 40px heading and compact prose on the left, black store badges and a sand action beneath, and a 540px square overlapping-phone collage on the right. The section has 120px outer padding and the panel has 24px corners.

**Transfer:** Translate badges into genuine distribution or access actions and use two complementary product views rather than decorative device duplication.

**Text style:** `heading` — Nohemi 500 · 40px/1.08 · tracking 0.018em

### Curated browsing rail

**Observed:** Heading left, short support text toward the middle and white circular previous/next controls on the right. Photo story cards sit below in a horizontally scrolling rail with 16px gutters; the last visible card is clipped by the viewport. Category browsing substitutes Category symbol tiles with 24px gutters and an accompanying small symbol cluster beneath.

**Transfer:** Offer curated examples, customer outcomes or categories with distinct visuals. Maintain editorial hierarchy instead of making every item an equal plain text card.

**Text style:** `heading` — Nohemi 500 · 40px/1.08 · tracking 0.018em

### Handwritten editorial pause

**Observed:** Full-width stone band about 599px tall. A rotated violet hand-interlude note sits above centered earth-colored interlude-copy within a 720px measure; two flat violet silhouettes sit diagonally away from the copy. Broad breathing room separates this statement from action-heavy chapters.

**Transfer:** Use one short belief about the user's experience, followed by a few lines of warm supporting copy. Keep this as a tonal pause, not another feature list.

**Text style:** `interlude-copy` — Nohemi 500 · 28px/1.35 · tracking 0.017em

### Photo and proof mosaic

**Observed:** A 40px claim pairs ink and olive phrases, with signup and distribution actions below and a small rating treatment opposite. A 706px by 472px photograph fills the left of the proof grid; on the right a 235px-wide tall lavender Statistic tile aligns with two smaller stone and sage tiles. Gutters are 12px and corners 24px.

**Transfer:** Use a human image beside a small set of verified metrics. Keep numbers at the heading scale rather than turning the region into giant infographic typography.

**Text style:** `heading` — Nohemi 500 · 40px/1.08 · tracking 0.018em

### Closing scene and footer

**Observed:** Green photographic sign-off supplies a centered cream silhouette strip, 40px two-line closing heading and Secondary button. It joins directly to Deep olive ending with a small logo, Footer columns, distribution badges, social icons, legal links and language selector. Feature-focused pages close with Promotion in paper instead of the scene; creator tools close with a 32px-radius stone conversion panel, and directory pages use a simple centered heading and green action.

**Transfer:** For a new ordinary landing page, resolve the story with the experiential sign-off and dark olive utility ending. Choose the scoped closing alternative only when the page's purpose is instructional or directory-like.

**Text style:** `heading` — Nohemi 500 · 40px/1.08 · tracking 0.018em

### Instruction slab

**Only for:** creator tools and integration pages

**Observed:** Citron instruction panel with a centered heading and short support line, followed by three white rounded cards. Each card begins with a small orange numbered circle, then a 20px subheading and compact prose; Tool action is centered below.

**Transfer:** Break a real workflow into a short finite sequence; use the large colored boundary to distinguish instructions from the live tool.

**Text style:** `heading` — Nohemi 500 · 40px/1.08 · tracking 0.018em

### Searchable directory

**Only for:** discovery directories

**Observed:** White content sheet inset within paper. A 594px-tall photographic hero carries a centered bold 48px title, a short green rule and an overlapping white search slab. Filter controls lead to a four-column image mosaic with near-touching 1px gutters, white centered titles and dark overlays. Pagination precedes 800px-wide editorial prose, paired wide photos, related categories and a centered closing action.

**Transfer:** Use for a genuine resource catalog with search and filtering, not as the default marketing-page grid.

**Text style:** `directory-hero` — Satoshi 700 · 48px/1.5

### Narrative with persistent context

**Only for:** editorial detail pages

**Observed:** A 48px title and creator attribution sit over metadata and compact 16px introductory paragraphs. A wide photograph leads into a two-column body: repeated 640px gallery-and-copy entries at left, sticky contextual viewer at right. Small conversion cards interrupt the long list. Comments and grouped statistics conclude the narrative, followed by a Photo story card recommendation rail and the shared footer.

**Transfer:** Pair a long sequence of practical content with context that stays useful while scrolling; maintain small metadata and clear entry numbering.

**Text style:** `capability` — Nohemi 500 · 48px/1.2 · tracking 0.02em

## Page flow

**Storyline:** Experiential promise → useful product proof → capability chapters → curated examples and human reassurance → credible scale → renewed invitation → practical navigation.

### Broad brand and product landing page

1. **promise** — Immersive film and compact centered signup actions.
2. **product demonstration** — Inset promotion followed by alternating text-and-collage capabilities.
3. **discovery** — Curated photo rails, handwritten pause and symbol-based categories.
4. **quantified proof** — Human photograph beside pastel metric tiles and a rating treatment.
5. **navigation** — Tabbed directory of destinations with restrained link columns.
6. **closing call** — Green photographic invitation, then deep-olive footer.

**Transfer:** Balance useful tools with real-world outcomes; adjust the number and order of chapters without losing the handmade imagery and experiential ending.

### Feature-focused product explanation

1. **promise** — Paper split with orange-emphasized headline, phone triptych and QR/download card.
2. **orientation** — Horizontal illustrated capability index.
3. **capability chapters** — Alternating collage sections with checkmarked benefit lists and green actions; one lavender paid-tier offer interrupts the rhythm.
4. **social proof** — Ratings, award laurels, white statistical cards and muted partner-logo rail.
5. **activation** — Three orange numbered steps and green conversion action.
6. **closing call** — Inset paper app promotion followed by shared footer.

**Transfer:** Use this more explicit structure when visitors need to understand a complete workflow and its distinct benefits.

### Creator tool and implementation landing page

1. **promise** — Short split headline, orange eyebrow and embed collage.
2. **product demonstration** — Selectable content types, settings column, large live preview and copyable output.
3. **benefits** — Three white cards with practical implementation reassurance.
4. **activation** — Citron instruction slab and orange start action.
5. **social proof** — Publisher and partner logo grid.
6. **objection handling** — Centered white FAQ disclosures.
7. **closing call** — Rounded stone panel with orange action, then shared footer.

**Transfer:** Bring the actual usable tool forward; let lower sections answer technical doubts rather than over-selling the concept.

### Long-form curated editorial detail

1. **context** — Breadcrumb, creator, large title, metadata and practical introductory prose.
2. **immersion** — Wide destination photograph.
3. **detailed demonstration** — Numbered gallery-and-copy entries alongside persistent map context, with small signup interruptions.
4. **community proof** — Comments and summary statistics.
5. **continuation** — Related photo-card rail followed by shared footer.

**Transfer:** Use for substantive guides, project narratives or multi-part resources rather than a standard sales page.

### Search-oriented resource discovery

1. **orientation** — Photographic title hero with prominent search and filter controls.
2. **discovery** — Dense four-column photo grid and pagination.
3. **education** — Narrow long-form prose and paired landscape photographs.
4. **continuation** — Compact category rows and related activity-photo tiles.
5. **closing call** — Centered heading, short green rule and signup action followed by shared footer.

**Transfer:** Use a denser white-sheet variant when the visitor's main task is browsing many resources.

## Writing

Warm, direct and encouraging, with practical competence beneath the sense of possibility. Benefits are expressed as experiences the reader can have, while technical sections become crisp and reassuring.

**Do not copy:** Do not reuse the komoot name, logo, proprietary pictograms, route names, creator identities, quoted endorsements, ratings, audience statistics or product claims. Replace them with truthful content and original assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use active imperatives and occasional inclusive invitations. The product is a helpful companion rather than an abstract platform.
- **Rhythm:** Short verb-led headings, compact explanatory paragraphs, and brief action labels. Handwritten asides can use an exclamation mark; technical explanations favor short clauses and concrete reassurance over excitement.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct invitation that expands the user's sense of possibility. | 4–8 words | “Explore beyond the map” |
| Capability heading | Verb plus a useful outcome; on feature explanations, emphasize the outcome phrase in orange. | 3–6 words | “Plan the perfect route”<br>“Navigate with confidence” |
| Supporting line | Explain the benefit in ordinary language and connect tools to confidence or freedom. | 1–3 short sentences | “Even off the beaten track, [Brand] keeps you on course.” |
| Primary action | Start with a verb, name the next step, and add a free-access reassurance only when true. | 2–6 words | “Sign up for free”<br>“Plan your first route” |
| Handwritten aside | A small personal invitation or energetic question. | 3–9 words | “Step into the wild!”<br>“Ready to explore?” |
| Tool reassurance | Short parallel fragments that remove effort and clarify control. | 3 brief clauses | “Three steps. Two minutes. One snippet you control.” |

**Words and phrasing to use:** explore; discover; your next; with confidence; get started; made for you; share; no account needed when true

**Avoid:** revolutionary ecosystem; synergize; unprecedented disruption; enterprise-grade everywhere; vague superlatives without proof

**Rules:**

- Lead with the user's activity and desired outcome, then name the mechanism.
- Use contractions and everyday words in explanatory copy.
- Pair a broad promise with concrete details such as offline access, customization or a specific next step.
- Technical objections deserve literal answers and compatibility details, not lifestyle metaphors.
- Use short human-readable captions and attribution beneath curated examples.

## Do's and Don'ts

### Do

- Keep ordinary page sections on warm #f5f3ec paper.
- Use Nohemi 500 and positive tracking for headings rather than simulating a heavy grotesk.
- Give capability text roughly 40% of a split and let the art remain oversized.
- Use 16px button corners and content-width 12px 16px actions by default.
- Repeat the flat symbol vocabulary across collages, category tiles and the closing strip.
- Use 120px marketing gutters and 80px chapter separation on desktop.
- Keep proof numbers around 40px and give them pastel tile surfaces rather than giant numerical type.
- Anchor the final utility region in #212512 with four modest link columns.

### Don't

- Do not turn the warm paper canvas into pure white across ordinary marketing chapters.
- Do not use full orange or violet backgrounds for every section; these accents punctuate the olive-and-paper system.
- Do not make every button a 9999px capsule; the default is a 16px rounded rectangle.
- Do not replace 1.5px warm card edges with cold gray borders and heavy elevation.
- Do not style handwritten notes like a second bold headline; preserve their 24px or 36px secondary role.
- Do not turn every functional icon into a colorful illustration; keep controls near 20px with 1.5px round strokes.
- Do not normalize photo rails into tiny fit-to-width thumbnails; preserve the 320px by 420px story-card presence.
- Do not spread the directory's 1px-gutter image mosaic into ordinary feature chapters.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares 0.2s ease-in-out transitions; photo cards declare 0.3s ease-in-out.
- Feature jump cards declare transform 200ms and box-shadow 200ms, with a -4px hover lift.
- Category tiles declare a rotate(-2deg) scale(1.1) hover transform and color inversion.
- Section entrances declare opacity and transform transitions of 700ms cubic-bezier(0.16, 1, 0.3, 1), with some 100ms, 150ms and 200ms delays.
- A partner-logo marquee declares a 30s linear infinite animation.

**Transfer:**

- Use motion to reinforce the tactile card vocabulary: slight tilt or lift on appropriate graphic tiles, not across all text.
- Keep entrance effects subordinate to the still composition; content should read completely when settled.

**Unknown:**

- Exact trigger thresholds and playback behavior of the opening film are unspecified.
- Resolved hover colors behind theme-token names are not known.

### Responsive

**Observed:**

- Declared width breakpoints include 380px, 540px, 720px, 1024px, 1280px, 1440px, 1680px and 1920px.
- Desktop uses horizontally overflowing rails and a sticky contextual viewer on editorial details.

**Transfer:**

- On narrow layouts, stack text and journal artwork while keeping the assembled collage intact as one visual unit.
- Keep photo and symbol rails horizontally browsable instead of compressing every card into the viewport.
- Move contextual viewers into the editorial reading flow when a side-by-side view would crowd the text.

**Unknown:**

- Narrow-screen font sizes, navigation behavior and exact stacking breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
