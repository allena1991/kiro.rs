# Faire — the neighborhood atelier

## Overview

An editorial commerce style that pairs a cultivated serif with an unshowy grotesk and the warmth of real working spaces. Cream and white canvases alternate with aubergine, earthy olive, peach and pale citron, while natural-light photography supplies most of the detail and color. It suits products that want to feel useful, human and thoughtfully curated rather than technical or corporate; broad photographic chapters coexist with compact discovery rails.

### Essentials

- Bookish headlines, practical explanations: Nantes at 52px/64px and 38px/50px, weight 400 with normal tracking, sits above Graphik support at 18px/26px with 0.1px tracking.
- An inhabited world is the opening object: a full-width 547px-tall photographic stage carries left-aligned white copy inset 48px, rather than a floating interface or isolated logo. Use a real context-of-use photograph when video is unavailable.
- Actions are little rectangular labels, not oversized pills: main buttons are 48px high with 4px corners, 14px/20px text and a 1px edge; reserve 40px-high rounded chips for discovery.
- Color works in whole editorial chapters: keep the surrounding discovery canvas #fbf8f6 and navigation/footer white; contain #41252a, #595604, #f1f29f and #ffd0b6 in edge-to-edge bands of roughly 533–727px rather than scattering them through UI.
- Photography has the proportions of a printed catalog: square discovery images, broad documentary portraits and 437px-wide category tiles; the frame is the image itself, with only 0–4px rounding and no decorative card shell.
- A generous colored invitation punctuates the page: pair a 38px or 52px serif promise with small white actions and human-scale imagery. The peach collage version places uneven photographic rectangles around centered text; a restrained two-image band is the fallback when collage media is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep olive | `#595604` | `--color-olive` | background | Image-bracketed invitation and compact closing bands with white text. |
| Aubergine | `#41252a` | `--color-aubergine` | background | Dark editorial benefit chapter and enterprise invitation bands. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale citron | `#f1f29f` | `--color-citron` | background | Broad reassurance/proof chapter with charcoal text and a large photograph. |
| Apricot paper | `#ffd0b6` | `--color-peach` | background | Collage invitation backdrop with charcoal serif text and outlined topic chips. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#333333` | `--color-ink` | text, action, border | Default text, dark buttons and selected discovery controls. |
| Active black | `#000000` | `--color-active` | action, text | Declared hover fill and link emphasis; not the default paragraph color. |
| Warm gray text | `#6c6a6a` | `--color-subdued` | text | Secondary captions, attribution and inactive explanatory content. |
| Fine gray edge | `#dadada` | `--color-rule` | border | Navigation boundaries, search fields, pale button edges and discovery chips. |
| Warm porcelain | `#fbf8f6` | `--color-canvas` | background | Default discovery and editorial canvas; also the announcement strip. |
| White | `#ffffff` | `--color-white` | background, surface, text, action | Navigation, footer, white content chapters and buttons; inverse text on dark bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company storytelling and workflow demonstrations | Dusty sage | `#91957b` | `--color-sage` | background | Geographic proof band; also a muted backing for workflow illustration. |
| company storytelling | Dark khaki | `#595540` | `--color-khaki` | background | Mission statement and awards bands. |
| enterprise proof sections | Stat divider | `#8e8c8c` | `--color-stat-rule` | border | Single vertical separator between paired metrics. |
| integration and workflow pages | Cool demonstration gray | `#f7f7f7` | `--color-demo-canvas` | background | Alternating interface demonstration and testimonial chapters. |

## Typography

- **Nantes** — Display promises, section headings, category labels and quotations. Literary, gently modulated serif with soft wedge-like details; always regular in the marketing hierarchy. If unavailable, use **Lora**. Use 400; tune wrapping to preserve the broad, unhurried line lengths. Font stack: "Nantes", "Lora", Georgia, serif.
- **Graphik** — Explanations, navigation, actions, captions and small headings. Plain geometric grotesk with open forms and restrained weight contrast. If unavailable, use **DM Sans**. Use 400 for regular UI and 500 for emphasis; preserve 0.1px tracking. Font stack: "Graphik", "DM Sans", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Nantes | 400 | 52px | 64px | normal | Main photographic hero promise and large centered invitation. |
| heading-lg | Nantes | 400 | 38px | 50px | normal | Feature chapter, invitation and footer promise. |
| heading | Nantes | 400 | 30px | 38px | normal | Discovery rail headings, process groups and FAQ titles. |
| section-label | Graphik | 400 | 22px | 32px | 0.007em | Plainspoken benefit subheads and workflow selectors. |
| hero-support | Graphik | 500 | 22px | 32px | 0.007em | One strong support line on the photographic opening. |
| serif-caption | Nantes | 400 | 22px | 32px | normal | Category labels over photographs; also centered testimonial copy. |
| body | Graphik | 200 | 18px | 26px | 0.008em | Feature explanation and spacious editorial paragraphs. |
| eyebrow | Graphik | 500 | 18px | 26px | 0.008em | Sentence-case introductory label and compact process subheads. |
| accordion-label | Graphik | 400 | 18px | 26px | 0.008em | Question labels and expandable value statements. |
| body-small | Graphik | 200 | 14px | 20px | 0.011em | Compact card descriptions and small secondary actions. |
| ui | Graphik | 400 | 14px | 20px | 0.011em | Primary actions, utility links, footer links and announcement text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| integration testimonials | quote-mark | Nantes | 400 | 72px | 86px | normal | Oversized opening quotation mark centered above a testimonial. |
| company recognition sections | award-title | Graphik | 700 | 30px | 38px | 0.005em | Underlined external recognition titles, not general headings. |

**Notes:**

- The serif stays regular and naturally spaced at every size. Hierarchy comes from size, line breaks and the shift between serif headings and sans-serif explanations, not tight tracking.
- Graphik text uses a consistent 0.1px tracking across 14px, 18px and 22px roles. Light paragraph styles should remain legible and understated rather than hairline.
- Use sentence case, including eyebrows and actions. The small brand mark is the exception to the generally non-uppercase texture.

## Layout

**Density:** Airy editorial chapters with compact discovery rails; substantial photographs and section margins balance small navigation and caption text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Chip gaps, icon-to-label spacing and compact copy relationships. |
| 12px | Editorial image-to-caption spacing and footer list gaps. |
| 16px | Card gutters, title-to-support gaps and chip horizontal padding. |
| 20px | Opening content stack gaps and default button horizontal padding. |
| 24px | Benefit-item gaps, two-column feature gutter and action separation from support. |
| 32px | Question-group separation and workflow item spacing. |
| 40px | Major heading-to-benefit stack gap and demonstration-panel padding. |
| 48px | Default desktop section padding and gaps around discovery chapters. |
| 64px | Explanatory-page chapter spacing. |
| 80px | Footer side inset, enterprise page inset and spacious invitation padding. |
| 104px | Company-story side inset and staggered portrait spacing. |
| 120px | Workflow feature vertical padding and mission-band vertical space. |

### Containers and grids

- **wide-editorial**: max width 1440px · side padding 48px. Default full-width photographic and discovery chapters. At a 1440px window the inset content spans 1344px; colored backgrounds extend to both edges.
- **feature-pair**: 2 columns · gap 24px. Equal-width photo and copy regions in the default benefit chapter; constrain the explanation itself to 503px.
- **editorial-grid**: 4 columns · gap 16px. Four 324px-wide editorial cards with 324px by 216px images at desktop.
- **category-grid**: 3 columns · gap 16px. Three 437px by 312px image tiles in a horizontal rail.
- **workflow-container** (only for integration pages): max width 1168px. Centered workflow storytelling with a 584px square visual on one side and a shorter text block on the other.
- **enterprise-container** (only for enterprise pages): max width 1440px · 2 columns · gap 80px · side padding 80px. Alternating unequal photo/text pairs; image is about three fifths of the content width.
- **discovery-grid** (only for catalog discovery sections): 6 columns · gap 16px. Square product cards with compact metadata underneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-media | 4px |
|  | topic-chips | 40px |
|  | search | 9999px (pill) |
| testimonials | portrait-avatar | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| platform explanation openings | photo-annotation | `0px 2px 4px 0px rgba(0, 0, 0, 0.25)` | Small floating product identification cards over a photograph. |
| integration demonstrations | demonstration-panel | `0px 10px 15px -3px rgba(0, 0, 0, 0.1), 0px 4px 6px -4px rgba(0, 0, 0, 0.1)` | A white workflow panel overlapping contextual photography. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default editorial and discovery background.

**CSS:** `background: #fbf8f6`

**Observed:** Untextured, subtly warm paper tone. It continues between rails and photographs.

**Transfer:** Use it as a continuous base rather than giving each content item a new panel.

#### White utility surface · level 0

**Use:** Navigation, footer and explanatory chapters.

**CSS:** `background: #ffffff`

**Observed:** Flat white surfaces with occasional gray hairline boundaries and no general elevation system.

**Transfer:** Keep the structural furniture neutral even where the editorial sections use strong color.

#### Aubergine chapter · level 0

**Use:** Benefit-led photographic chapter.

**CSS:** `background: #41252a; color: #ffffff; padding: 48px`

**Observed:** Full-bleed rectangular band with a large photo occupying about half the inset width.

**Transfer:** Use for a substantial benefit story, not a small accent card.

#### Olive invitation · level 0

**Use:** Image-bracketed invitation or a compact final action.

**CSS:** `background: #595604; color: #ffffff; padding: 48px`

**Observed:** Earthy high-contrast field; white actions remain visually small.

**Transfer:** Keep the typography and action neutral; let the band supply the color.

#### Citron reassurance · level 0

**Use:** Benefit proof paired with an attributed photograph.

**CSS:** `background: #f1f29f; color: #333333; padding: 48px`

**Observed:** Pale yellow-green field with dark text; image is about half the content width.

**Transfer:** Reserve for a memorable proof or reassurance chapter.

#### Peach collage field · level 0

**Use:** Expansive invitation with floating photographic rectangles.

**CSS:** `background: #ffd0b6; color: #333333; padding-bottom: 24px`

**Observed:** Centered text has an open middle; photography occupies irregular perimeter positions and a topic rail runs along the bottom.

**Transfer:** Create a playful but orderly photographic perimeter around a readable central promise.

#### Workflow chapter · level 0

**Only for:** integration pages

**Use:** Alternation between interface-led features and testimonial space.

**CSS:** `background: #f7f7f7`

**Observed:** Cool light-gray chapters alternate with white and accommodate large square demonstration scenes.

**Transfer:** Use a subtle neutral alternation rather than the richer discovery palette.

#### Company dark field · level 0

**Only for:** company storytelling

**Use:** Mission and recognition bands.

**CSS:** `background: #595540; color: #ffffff`

**Observed:** Muted khaki supports a centered mission and a separate three-column recognition grid.

**Transfer:** Let a substantial statement carry the space, without product UI.

#### Geographic proof field · level 0

**Only for:** company storytelling

**Use:** Statistics beside an understated geographic graphic.

**CSS:** `background: #91957b; color: #ffffff`

**Observed:** A sage band holds a two-by-two metric group beside a flat two-tone world map.

**Transfer:** Pair honest scope or scale metrics with one restrained diagram.

## Components

### Navigation

**Use:** Persistent discovery and account navigation.

**CSS:** `background: #ffffff; border-bottom: 1px solid #dadada; display: flex; flex-direction: column; height: 108px`

**Text style:** `ui` — Graphik 400 · 14px/20px · tracking 0.011em

**Observed:** An announcement strip sits above a two-row header: compact letterspaced brand mark, category menu, long central search field and utility actions on the first row; a centered line of categories below. The search consumes much more width than any individual link. Enterprise navigation uses a simpler 73px single row.

**Transfer:** Reduce categories to the new product's real information architecture while keeping the compact text density.

### White action

**Use:** Default marketing conversion over photography or colored bands.

**CSS:** `background: #ffffff; color: #333333; border: 1px solid #dadada; border-radius: 4px; height: 48px; padding: 0px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `ui` — Graphik 400 · 14px/20px · tracking 0.011em

**Observed:** Short centered label, normally without icon. Opening uses one button with a separate underlined secondary invitation below; the footer uses a pair side by side.

### Dark action

**Use:** Compact header conversion and dark-on-light action.

**CSS:** `background: #333333; color: #ffffff; border: 1px solid #333333; border-radius: 4px; height: 36px; padding: 0px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `body-small` — Graphik 200 · 14px/20px · tracking 0.011em

**Observed:** The header variant is compact. Integration and enterprise sections use a 48px-high version with the ui recipe; their sticky conversion bar uses a 40px-high version.

**States:** Declared: hover background-color #000000, border-color #000000, color #ffffff; focus-visible outline -webkit-focus-ring-color solid 2px with outline-offset 2px; active color #ffffff.

### Strong outline action

**Use:** White button with a more emphatic edge in invitation chapters.

**CSS:** `background: #ffffff; color: #333333; border: 1px solid #333333; border-radius: 4px; height: 48px; padding: 0px 23px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `body-small` — Graphik 200 · 14px/20px · tracking 0.011em

**Observed:** Used alone in the image-bracketed invitation and as paired audience actions in explanatory content.

**States:** Declared: hover background-color #000000 and color #ffffff; focus-visible outline -webkit-focus-ring-color solid 2px with outline-offset 2px.

### Discovery chip

**Use:** Topic or category selection above a visual rail.

**CSS:** `border: 1px solid #dadada; border-radius: 40px; height: 40px; padding: 0px 16px; display: inline-flex; align-items: center; justify-content: center; color: #333333`

**Text style:** `body-small` — Graphik 200 · 14px/20px · tracking 0.011em

**Observed:** Single-line labels form a close horizontal rail. The active item reverses to white on charcoal. The peach invitation's topic links use a charcoal edge and 10px vertical padding.

### Category image tile

**Use:** Large photographic entry into a topic.

**CSS:** `position: relative; overflow: hidden; width: 437px; height: 312px; background-image: linear-gradient(22.18deg, rgba(0, 0, 0, 0.5) 1.86%, rgba(0, 0, 0, 0) 31.23%)`

**Text style:** `serif-caption` — Nantes 400 · 22px/32px

**Observed:** A photograph fills the tile; the subtle diagonal dark overlay sits above it and the white serif label sits over the lower-left corner, inset 16px. The row has small carousel controls at the edges.

**Transfer:** Choose a tactile, tightly framed context image rather than a symbolic icon.

### Editorial card

**Use:** Guides, education and customer-story links.

**CSS:** `display: flex; flex-direction: column; gap: 12px; width: 324px`

**Text style:** `body-small` — Graphik 200 · 14px/20px · tracking 0.011em

**Observed:** A 324px by 216px image with 4px corners leads directly into a compact text title. No surrounding border, fill or shadow. Larger two-column story versions add a short description and underlined text link.

**Transfer:** Keep the image primary and the text directly on the page canvas.

### Question row

**Use:** Objection handling and expandable practical questions.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 8px; padding: 12px 16px; min-height: 56px`

**Text style:** `accordion-label` — Graphik 400 · 18px/26px · tracking 0.008em

**Observed:** Full-width native disclosure rows have fine horizontal separators and a small right-aligned downward chevron, rather than separate rounded boxes. Explanatory content also uses a 58px row with 16px 24px padding and the body recipe.

**Transfer:** Keep the questions specific and concise; let the answer carry detail.

### Footer columns

**Use:** Utility ending after the final editorial invitation.

**CSS:** `display: flex; flex-direction: column; gap: 12px; margin-top: 12px; min-width: 140px`

**Text style:** `ui` — Graphik 400 · 14px/20px · tracking 0.011em

**Observed:** A wide white footer places a 420px-wide serif promise and two small white actions on the left, two compact link columns and social icons on the right, then a low legal strip. Outer desktop padding is 48px vertically and 80px horizontally. Company storytelling instead places the small brand mark above its promise and omits the action pair.

**Transfer:** Preserve the asymmetric emphasis: an editorial statement, not an enormous logo or a wall of navigation.

### Search field

**Only for:** search-led products

**Use:** Prominent catalog search in the utility header.

**CSS:** `background: #ffffff; border: 1px solid #dadada; border-radius: 9999px; height: 40px; padding: 0px 16px 0px 0px; display: flex; align-items: center; gap: 8px`

**Text style:** `ui` — Graphik 400 · 14px/20px · tracking 0.011em

**Observed:** A small outline magnifier precedes subdued placeholder text. The field spans 595px at desktop, with room for the input and icon.

**Transfer:** Use only where search is a real discovery path, not as a decorative landing-page input.

### Floating photo annotation

**Only for:** platform explanation openings

**Use:** Connect a product in a scene with a short identity label.

**CSS:** `background: #ffffff; border-radius: 4px; box-shadow: 0px 2px 4px 0px rgba(0, 0, 0, 0.25); padding: 8px 32px 8px 8px; display: flex; gap: 8px; height: 80px`

**Text style:** `ui` — Graphik 400 · 14px/20px · tracking 0.011em

**Observed:** A 64px square thumbnail sits beside a two-line product and maker label. Several small annotations occupy different places over a broad store photograph.

**Transfer:** Use a few real item or feature labels anchored to the pictured subject, never a swarm of abstract tooltips.

## Imagery and graphics

### Inhabited photographic stage

**Use:** Opening and major benefit chapters.

**Observed:** Real people entering, stocking and working in independent spaces. Warm daylight, painted shelves, wood, fabric, ceramics and foliage create tactile detail. Images are full-bleed in the opening, rectangular in chapters, and occupy roughly half a split feature. The opening video is softly darkened behind white type, without looking cinematic or heavily graded.

**Transfer:** Photograph the product being used in a convincing lived-in environment. If there is no video, use a single strong daylight still with a quiet area for the headline.

### Catalog and category photography

**Use:** Discovery rails, category tiles and editorial cards.

**Observed:** Square product or maker imagery mixes studio still life and real spaces. Category tiles use tighter material details such as fabric, vessels and food. Color remains natural but is allowed to be lively within the image; there is no universal desaturation filter.

**Transfer:** Mix authentic context photographs with clean product still lifes; hold consistent aspect ratios within each rail.

### Perimeter photo collage

**Use:** Signature expansive invitation.

**Observed:** Uneven portrait and landscape photo rectangles float around a centered serif phrase on peach. The images show intimate domestic product scenes; some blend softly into the peach. A thin rail of outlined topics grounds the bottom edge.

**Transfer:** Use four context images of different sizes around an open center. The minimum equivalent is two strong photographs flanking the invitation in the olive band.

**Build:** Make a position:relative, overflow:hidden peach section about 727px tall. Place four rectangular image wrappers around the perimeter, mixing portrait and landscape proportions around 200–340px wide; offset their top and bottom edges rather than making a grid. Center a roughly 632px-wide text group above them. Where needed, blend edge images with a peach overlay or linear mask; keep text fully opaque. Anchor a 40px-high chip rail near the bottom.

### Enterprise product constellation

**Only for:** enterprise openings

**Use:** A product-led opening with centered sales copy.

**Observed:** Small rectangular still-life photographs of personal-care products orbit a clear center on a deep aubergine ground with very subtle grain. The left pair overlaps; the right pair is spaced farther apart. Warm beige, coral and amber materials complement the background. Small carousel dots sit below the centered action.

**Transfer:** Use 3–4 finished product/context images around a centered quantified benefit, not floating icons.

**Build:** Use the aubergine field with a low-opacity monochrome noise texture. Position portrait rectangles in the upper and lower left with slight overlap, a smaller portrait at upper right and a landscape at lower right. Keep the central copy column about 450px wide and clear of imagery; use only 4px corner softening.

### Workflow demonstration collage

**Only for:** integration pages

**Use:** Illustrate a specific operation beside benefit copy.

**Observed:** Real workspace photography backs a white interface panel. A 392px by 304px panel with 40px padding and 4px corners overlaps the photo edge; other features use a large square interface illustration on sage or light neutral backing. Product thumbnails, simplified rows and one active operation make the function readable.

**Transfer:** Show one genuine operation in a simplified but coherent panel; keep interface colors inside the demonstration rather than turning them into the marketing palette.

**Build:** Use a 584px square photograph or muted backing. Place a white 4px-radius panel over it, offset beyond one edge by 48px where space permits. Add a compact header and three clearly differentiated data rows with product thumbnails. Use the demonstration-panel shadow, with no glow.

### Company documentary portraits

**Only for:** company storytelling

**Use:** Mission narrative, workplace and people chapters.

**Observed:** Tall 528px by 643px scenes show a storefront, hands lighting a candle and a softly lit lounge. Portraits and copy alternate sides with broad negative space. A wide shelf still life creates a photographic interlude between proof and company information.

**Transfer:** Use tactile working details and natural workplace photography, not formal executive headshots.

### Geographic proof graphic

**Only for:** company scale stories

**Use:** Visual counterweight to a two-by-two metric group.

**Observed:** A flat world-map silhouette in two restrained light/dark tones rests directly on sage, about 566px wide. There are no outlines, pins, labels, gridlines or dashboard chrome.

**Transfer:** Use a simple diagram that expresses reach or connectedness; keep geography only when it is meaningful to the product.

**Build:** Place a simplified SVG silhouette in the right half of the sage band, filled with translucent white; distinguish relevant regions with translucent khaki. Keep it flat and unlabelled. On the left, use four white serif metrics with small sans explanations.

### Icons

**Observed:** Most utility icons are 16px outline SVGs with a 1px rounded stroke in charcoal or inverse white. Smaller rating stars are 12px solid shapes; social icons are compact solid marks. Chevrons, search and globe controls remain subordinate to text.

**Transfer:** Choose restrained outline icons at 16px with round caps. Do not replace photographic storytelling with a large illustrated icon set.

## Section recipes

How recurring sections are built.

### First screen: Inhabited opening

**Observed:** A 44px warm announcement strip and 108px white two-row Navigation lead into a 547px-tall, edge-to-edge photographic stage. Back to front: context video filling the rectangle, a subtle darkening treatment, then a left-aligned text stack inset 48px and centered vertically. The regular 52px/64px serif headline is one line of about two fifths of the width; a 22px/32px medium sans support line sits below, followed by White action and a small underlined secondary audience invitation. The person and doorway remain recognizable behind the type. Within the first 900px, the entire opening and the next rail heading, chips and tops of square images are visible; the rail's complete cards fall below.

**Transfer:** Lead with an outcome in a real environment. Replace unavailable video with one strong context photograph rather than a UI mockup. For a platform explanation, use a white text-led introduction with a small eyebrow, 52px serif promise and broad annotated photograph below. Enterprise openings center the promise within Enterprise product constellation; workflow openings split white copy and an edge-to-edge portrait with an overlapping panel; company storytelling opens with a centered mission on Company dark field.

**Avoid:** Do not center the default hero in a generic pastel panel, shrink the photography into a small card, or increase the headline to a monumental tightly tracked sans-serif.

**Text style:** `display` — Nantes 400 · 52px/64px

### Benefit and documentary pair

**Observed:** Aubergine chapter holds two equal regions separated by 24px. The left has a heading-lg title, 40px pause, then three section-label and body pairs with 4px internal gaps and 24px between benefits. White action follows after another 40px pause. The right is a 660px by 542px documentary photograph. Light variants alternate image side and use heading at 30px with compact process text.

**Transfer:** Group a small number of related benefits under one editorial idea, then use a contextual image that makes the benefit tangible.

**Text style:** `heading-lg` — Nantes 400 · 38px/50px

### Discovery rail

**Observed:** A 30px serif heading leads a compact chip rail and then a horizontal photo-led row. Six square brand images use 8px gaps; denser product cards use 16px gaps and small metadata. Category image tile uses a three-wide row; Editorial card uses four. The canvas is continuous and rows can extend beyond the viewport.

**Transfer:** Use a rail for actual choices, examples or resources, keeping metadata compact and leaving richer explanation to full-width chapters.

**Text style:** `heading` — Nantes 400 · 30px/38px

### Image-bracketed invitation

**Observed:** Olive invitation places a 370px-wide centered copy column between two 437px-square documentary images, with 48px perimeter padding. Heading-lg, a short body-small support line and Strong outline action form the center. A compact closing variant removes the photos and uses about 91px vertical padding.

**Transfer:** Use two complementary scenes to frame a single outcome and small action. This is the minimum-media expression of the colored invitation device.

**Text style:** `heading-lg` — Nantes 400 · 38px/50px

### Bright reassurance pair

**Observed:** Citron reassurance places a 38px serif headline, 18px support and White action beside a 648px by 495px photograph. A small white attribution is pinned over a darkened lower image edge.

**Transfer:** Tie a reassurance or reduced-risk claim to a real person's experience; make any conditions explicit in the text.

**Text style:** `heading-lg` — Nantes 400 · 38px/50px

### Peach invitation collage

**Observed:** Peach collage field supports a centered 52px serif phrase with one underlined product word, a small signup link and Perimeter photo collage. Discovery chip links form a bottom rail. Its 727px height makes the invitation feel like a full editorial scene, not a thin CTA strip.

**Transfer:** Give the new product a concise, personal invitation with one variable or linked object word. Maintain the open center and surrounding lived-in imagery.

**Text style:** `display` — Nantes 400 · 52px/64px

### Practical ending

**Observed:** Question row groups sit under a 30px serif title with 24–32px before the first row. Enterprise pages then close with a 324px aubergine invitation and one White action, followed by Footer columns. Integration pages place a neutral conversion call before a three-step gray process band, questions and the footer. Explanatory content ends with two groups of 40px topic pills and a 324px olive closing call, without a separate footer.

**Transfer:** Choose the ending appropriate to the reader's next decision: discovery topics for self-service, explicit consultation for sales-led products, practical questions for setup-heavy products.

**Text style:** `heading` — Nantes 400 · 30px/38px

### Workflow feature and quote

**Only for:** integration pages

**Observed:** A centered 1168px container alternates a 584px square demonstration and a heading-lg plus body text, with 120px top and bottom space. A selectable-benefit version pairs three 504px-wide copy blocks with a square demo; the active item has a charcoal vertical marker while inactive text is subdued. A testimonial follows on the same surface: a 72px opening quote, centered 22px serif statement and small circular portrait with an 18px attribution.

**Transfer:** Demonstrate one task per scene and follow with a brief human consequence. Keep the rendered task meaningful, not abstract gray skeleton rows.

**Text style:** `heading-lg` — Nantes 400 · 38px/50px

### Scale proof

**Only for:** enterprise and company pages

**Observed:** Enterprise proof uses two centered 52px serif metrics with small captions, 32px horizontal metric padding and one thin vertical divider. Company proof uses four 38px white serif metrics in two columns with 64px between columns, supported by the Geographic proof graphic on sage.

**Transfer:** Use only substantiated metrics; keep numbers literary and calm rather than dashboard-like.

**Text style:** `display` — Nantes 400 · 52px/64px

### Company story and recognition

**Only for:** company storytelling

**Observed:** A centered 52px white serif mission on khaki opens the story; alternating tall portraits and 38px narrative headings follow on the warm canvas. Sage metrics, a wide photographic interlude, expandable values and workplace imagery lead to a khaki three-column by two-row recognition band. Recognition titles use the 30px bold sans recipe with underlining, followed by smaller publisher lines. The final white footer uses a serif promise without the action pair.

**Transfer:** Translate this to a substantiated origin, principles, people and external validation narrative rather than borrowing company facts.

**Text style:** `heading-lg` — Nantes 400 · 38px/50px

## Page flow

**Storyline:** Inhabited promise → tangible choices or explanation → benefit chapters → human and quantified proof → practical reassurance → editorial invitation and utility ending.

### Broad discovery-led marketing landing page

1. **Promise** — Full-width photographic opening with outcome, support and one main action.
2. **Product discovery** — Square-image brand rail with category chips.
3. **Reassurance** — Dark benefit chapter with documentary portrait.
4. **Choice and belonging** — Product rail, image-bracketed olive invitation, category tiles and values-led image/text pair.
5. **Proof** — Citron reassurance with attributed photograph.
6. **Education** — Four compact editorial cards.
7. **Closing invitation** — Peach photo collage, linked serif phrase and topic chips.
8. **Utility ending** — White asymmetric promise-and-links footer.

**Transfer:** Alternate compact browseable material with broad photographic chapters so the page feels both useful and editorial.

### Explain a two-sided service and how to begin

1. **Orientation** — Eyebrow, serif promise, support, two audience actions and broad annotated scene.
2. **Process explanation** — Three illustrated stages followed by alternating audience-specific photo/text chapters.
3. **Social proof** — Two horizontal documentary customer rails.
4. **Objection handling** — Questions, press quotations and two success-story cards.
5. **Self-service routing** — Two groups of outlined topic pills.
6. **Closing call** — Centered white invitation and paired actions on olive; this is the page ending.

**Transfer:** Separate participant paths clearly while keeping the photography and typographic hierarchy shared.

### Sales-led landing page for a complex buyer

1. **Promise** — Centered quantified promise inside aubergine product constellation.
2. **Social proof** — Short customer-logo strip on the same dark ground.
3. **Capabilities** — Two alternating broad photos and compact benefit lists with dark actions.
4. **Quantified proof** — Paired serif metrics divided by one vertical line.
5. **Objection handling** — Wide questions and concise conditions.
6. **Closing call** — Centered aubergine consultation invitation followed by white footer.

**Transfer:** Use fewer discovery controls and more operational specificity, with a repeated consultation action.

### Explain a workflow integration and convert a setup-ready user

1. **Outcome promise** — Split white headline and contextual portrait with partner marks and overlapping demonstration panel.
2. **Capability chapters** — Alternating gray/white square demos, editable-benefit selector and centered testimonials.
3. **Conversion** — Neutral centered outcome and dark action.
4. **Process** — Three numbered steps on gray.
5. **Objection handling** — Questions and help link.
6. **Utility ending** — White promise-and-links footer; sticky conversion bar persists during the story.

**Transfer:** Keep workflow demonstrations tied to real tasks and alternate them with readable human proof.

### Company mission and trust narrative

1. **Mission** — Centered serif statement on dark khaki.
2. **Origin and belief** — Alternating tall documentary photographs and editorial narrative.
3. **Scale proof** — Sage metric band and quiet world map.
4. **Visual interlude** — Wide shelf still life.
5. **Principles and people** — Expandable values, portrait and workplace/city list.
6. **External validation** — Bold underlined award titles on khaki.
7. **Utility ending** — White brand promise and link columns without action pair.

**Transfer:** Keep the same serif/sans voice while replacing conversion pressure with origin, people and verifiable recognition.

## Writing

Warm, capable and commercially specific. The tone champions independent people while explaining practical outcomes without technical bravado.

**Do not copy:** Do not reuse Faire's name, wordmark, partner logos, proprietary photography, customer identities or quotations, metrics, offers, financing/return terms, awards or factual claims. Replace them with original, verified material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your business. Use we for concrete help or service commitments, and the product name when orienting a new visitor.
- **Rhythm:** Headlines are usually short sentence-case promises; support is one or two plain sentences. Benefit groups use a brief action-led subhead followed by one explanation, with no exclamatory sales cadence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct invitation toward a desirable outcome, or removal of a tedious task. | 4–8 words | “Find your next bestseller”<br>“Say goodbye to manual data entry” |
| Supporting line | Explain the product's practical use and who benefits. | One or two sentences | “Whether you buy for a clothing boutique or a grocery store, find all the products you need on [Brand].” |
| Benefit subhead | State an action, saved effort or concrete operating advantage. | 3–9 words | “Only pay for what works”<br>“Test small, launch big” |
| Primary action | Plain verb plus clear destination or intent; audience-specific when needed. | 2–5 words | “Sign up to buy”<br>“Talk to our team” |
| Closing invitation | An approachable question or personalized direction, not a slogan shouted in capitals. | 4–11 words | “Ready to get started?”<br>“Want to see how this works for your business?” |
| Process label | Two-digit step number, em dash and a concrete verb phrase. | 3–6 words after number | “01 — Connect and configure” |

**Words and phrasing to use:** find; discover; your business; all in one place; get started; save hours; community; independent; with confidence

**Avoid:** disruptive; revolutionary; 10x; hypergrowth; best-in-class; unlock your potential; frictionless ecosystem

**Rules:**

- Lead with the reader's next useful outcome, then explain the mechanism.
- Attach reassurance to specific conditions rather than absolute, unqualified guarantees.
- Use human stories and names when permission and accuracy permit; keep attribution compact.
- Keep procedural copy concrete enough that the reader can anticipate the next step.

## Do's and Don'ts

### Do

- Keep the main serif promise at 52px/64px and weight 400.
- Use 38px/50px serif headings for substantial benefit chapters, not a bold sans replacement.
- Hold default desktop editorial insets at 48px and footer insets at 80px.
- Keep marketing buttons 48px high with 4px corners and compact 14px labels.
- Use 16px gutters between category and editorial cards.
- Let full-width earthy or pastel chapters create contrast against #fbf8f6.
- Keep interface elevation local: the small photo annotation uses a 2px/4px shadow, not a site-wide card treatment.
- Give category photographs a lower-left white 22px serif label with 16px inset.

### Don't

- Do not round large photographs or colored bands into 24px-radius dashboard cards; media corners remain 0–4px.
- Do not turn the warm canvas into a monochrome beige site: retain the aubergine, olive and pale-color chapter contrast.
- Do not style primary actions as 40px-radius pills; that shape belongs to discovery chips.
- Do not apply negative display tracking or heavy serif weights; the display is regular with normal tracking.
- Do not enlarge every body paragraph to 22px; that size belongs to subheads and the opening support line.
- Do not scatter workflow badge colors or interface highlights across marketing text.
- Do not place a shadow beneath every editorial card; titles and images sit directly on the canvas.
- Do not make footer navigation visually compete with its 38px serif promise.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares background 0.1s linear; some links declare color 0.1s linear.
- Action variants declare 0.2s background-color/border transitions, and some surfaces use background-color 300ms ease-out.
- Horizontal brand and customer rails declare 40s linear infinite animation. Other looping elements declare 25s linear with a 20s delay.
- The opening uses contextual video; workflow scenes and a product-image opening have changing content.

**Transfer:**

- Keep documentary motion subordinate to readable stationary type.
- Use long linear movement for discovery rails rather than a fast ticker; preserve clear still frames for the important product operation.

**Unknown:**

- Playback timing, autoplay conditions and reduced-motion behavior are not established.
- Animation triggers and the timing of workflow state changes are unknown.

### Responsive

**Observed:**

- Desktop uses wide horizontal rails, split feature rows and full-width colored chapters.
- Declared width thresholds include 767px/768px, 1023px/1024px and 1280px; the opening's layout classes distinguish portrait mobile framing from the wide desktop stage.

**Transfer:**

- On narrow screens, retain the inhabited photograph and left-aligned action stack; use a portrait frame with copy over a readable lower region.
- Stack photo/text feature pairs while preserving colored chapter identity, and keep discovery cards in horizontally scrollable rails rather than shrinking six columns to unreadable tiles.
- Collapse perimeter collage images away from the central promise before reducing the serif to illegibility.

**Unknown:**

- Exact mobile typography, navigation construction, crop positions and breakpoint-specific spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
