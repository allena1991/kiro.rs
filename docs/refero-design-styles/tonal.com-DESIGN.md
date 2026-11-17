# Tonal — architectural strength, expanded

## Overview

An athletic, architectural style that pairs calm domestic product photography with unusually wide, heavy grotesk headlines. White, warm off-white and charcoal divide the narrative into spacious chapters, with electric mint reserved for actions and small signals. Light standard sans-serif introductions, compact supporting copy and technical monospace links temper the muscular display type. It suits premium connected hardware and services that need both an aspirational setting and practical explanations.

### Essentials

- A soft-spoken opening precedes the muscular sales argument: a 600px split stage gives 40% to an off-white text panel and 60% to architectural product media, with a 38px/1.1 light headline.
- Headlines behave like broad athletic blocks, not tall condensed posters: GT Expanded at weight 900, uppercase, normal tracking and 0.9 line height; 40px for major promises and 32px for recurring section leads.
- Actions are cut rectangles, not capsules: mint #11ddc4 buttons use 16px/24px medium uppercase text, 8px 16px padding and a 1px matching edge; the opening uses black 40px-high buttons.
- The page is mostly neutral, alternating white and #1c1c1a full-width chapters; mint stays in short actions, fine outlines and 4px progress indicators rather than broad background bands.
- Product proof is staged as lived-in architecture: soft window light, cream walls, restrained greenery and black hardware, followed by edge-to-edge rectangular media in 395px-wide feature columns or 362px-wide sliding cards. Use a carefully lit real-world still when moving media is unavailable.
- Include the signature editorial devices: a horizontally clipped media rail with a glimpse of the next card, and a monumental reversal line that crosses out the lesser outcome and replaces it with a stronger one. The reversal uses 56px/0.9 expanded capitals on charcoal; it can punctuate any suitable point in the story.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mint | `#11ddc4` | `--color-mint` | action, border, accent, link | Conversion fills, proof-card outlines, progress tracks and restrained inline emphasis. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface, text | Default light sections and footer; reversed text on black opening actions. |
| Warm chalk | `#f6f6f1` | `--color-warm` | surface, background | Editorial card text panels and warm capability sections. |
| Navigation gray | `#f5f5f5` | `--color-nav` | surface | Light desktop navigation band. |
| Soft gray | `#f4f4f4` | `--color-soft` | surface, background, text, border | Opening copy panel, proof bands, light buttons and text on charcoal. |
| Pale rule | `#e5e7eb` | `--color-rule` | border | FAQ dividers, unselected option outlines and capability explorer rules. |
| Silver text | `#c6cacd` | `--color-reverse-muted` | text | Supporting copy under the dark reversal headline. |
| Input edge | `#6b7280` | `--color-input-edge` | border | Newsletter field outline. |
| Editorial gray | `#656668` | `--color-muted` | text | Secondary editorial descriptions and the quiet label above the reversal headline. |
| Footer rule | `#494948` | `--color-footer-rule` | border | Fine separator above the copyright row. |
| Warm charcoal | `#1c1c1a` | `--color-ink` | text, background, border | Primary dark text, dark narrative chapters and selected option edges. |
| Black | `#000000` | `--color-black` | action, text | Opening and navigation action fills; compact comparison text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interactive capability explorers | Inactive label gray | `#6e6e6e` | `--color-inactive` | text | Inactive capability explorer labels. |
| product comparison tables | Blue-gray stripe | `#e6ebef` | `--color-table-row` | surface | Alternating comparison rows. |
| product comparison tables | Pale blue label | `#ebf1f5` | `--color-table-label` | surface | Default comparison label column. |
| product comparison tables | Deeper blue label | `#d8e4eb` | `--color-table-label-alt` | surface | Alternating comparison label cells. |

## Typography

- **GT America** — Opening headlines, body copy, navigation and button labels. Direct neo-grotesk with a light introductory cut and unembellished regular body. If unavailable, use **Public Sans**. Use 300, 400, 500 and 700; preserve line breaks through width tuning. Font stack: "GT America", "Public Sans", Arial, sans-serif.
- **GT Expanded** — Broad uppercase section headings, card titles and reversal statements. Very wide grotesk with dense black strokes and tightly packed vertical rhythm. If unavailable, use **Archivo**. Use the variable width axis at 125 with weight 900; do not substitute a condensed sports face. Font stack: "GT Expanded", "Archivo", Arial, sans-serif.
- **GT Mono** — Directional discovery links and technical-feeling editorial labels. Light monospaced capitals that act as a counterpoint to the black expanded headings. If unavailable, use **Roboto Mono**. Use weight 300. Font stack: "GT Mono", "Roboto Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| reversal | GT Expanded | 900 | 56px | 0.9 | normal, uppercase | Monumental outcome statement with a struck-through alternative. |
| heading-lg | GT Expanded | 900 | 40px | 0.9 | normal, uppercase | Major centered promise and editorial chapter introductions. |
| opening | GT America | 300 | 38px | 1.1 | normal | Default split-stage introduction; sentence case and two compact benefit clauses. |
| heading | GT Expanded | 900 | 32px | 0.9 | normal, uppercase | Recurring section leads in either light or dark chapters. |
| body-lead | GT America | 400 | 20px | 1.2 | normal | Centered support, chapter introductions and quote-card copy. |
| card-title | GT Expanded | 900 | 18px | 0.9 | normal, uppercase | Portrait, capability and benefit-card titles. |
| feature-title | GT America | 500 | 18px | 0.9 | normal | Quieter feature titles directly below product photographs. |
| body | GT America | 400 | 16px | 1.2 | normal | Standard explanatory copy and product configuration descriptions. |
| button | GT America | 500 | 16px | 1.5 | normal, uppercase | All filled rectangular calls to action. |
| directional-link | GT Mono | 300 | 16px | 1.2 | normal, uppercase | Discovery links with a small right arrow. |
| navigation | GT America | 400 | 16px | 1.2 | normal, uppercase | Main navigation labels. |
| reversal-label | GT Expanded | 100 | 16px | 0.9 | normal, uppercase | Thin muted label preceding the black-weight reversal statement. |
| body-small | GT America | 400 | 14px | 1.2 | normal | Compact card descriptions and footer links. |
| footer-heading | GT Expanded | 900 | 14px | 0.9 | normal, uppercase | Small dense footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability and library landing pages | category-opening | GT Expanded | 900 | 48px | 0.9 | normal, uppercase | Centered title above support copy and a demonstration. |
| program or collection campaigns | campaign-opening | GT Expanded | 900 | 42px | 0.9 | normal, uppercase | Left-aligned white headline over a full-bleed studio photograph. |
| program or collection catalogs | catalog-heading | GT America | 500 | 32px | 0.9 | normal | Sentence-case section leads above tabs, proof and FAQ. |
| featured program or collection spotlights | featured-credit | GT Expanded | 200 | 32px | 0.9 | normal, uppercase | Light expanded credit line immediately under a heavy heading. |
| interactive capability explorers | explorer-label | GT Expanded | 900 | 24px | 0.9 | normal, uppercase | Stacked active and inactive capability selectors. |
| product purchase pages | product-title | GT Expanded | 900 | 24px | 1.333 | normal, uppercase | Compact product name beside the large gallery. |
| question-and-answer sections | faq-question | GT America | 700 | 20px | 1.2 | normal | Bold sentence-case disclosure labels. |
| capability and secondary conversion sections | body-medium | GT America | 400 | 18px | 1.2 | normal | Longer feature descriptions and closing choice copy. |
| product comparison tables | table-value | GT America | 400 | 14px | 1.37 | normal | Centered values beneath product images. |
| product purchase pages | configuration-heading | GT Expanded | 900 | 14px | 1.43 | normal, uppercase | Small section labels above grouped configuration choices. |
| product comparison tables | table-label | GT Expanded | 700 | 10px | 0.9 | normal, uppercase | Dense feature names in the tinted first column. |

**Notes:**

- Normal tracking is the default even at display sizes; the unusual width comes from the expanded face, not extra letter spacing.
- Keep the contrast between 300-weight sentence-case introductions and 900-weight uppercase chapter headings. Expanded headings use 0.9 line height while explanatory text uses 1.2.
- Use semantic heading levels independently of visual size. A recurring section title can be smaller than the opening and still carry the same expanded construction.

## Layout

**Density:** Airy sections with compact internal copy: long breathing spaces surround comparatively dense image-and-text cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title-to-description gap and button vertical padding. |
| 12px | Opening action separation and small control spacing. |
| 16px | Directional-link separation, FAQ vertical padding and option-card padding. |
| 24px | Column gutters, editorial panel padding and support-to-action gaps. |
| 32px | Quote-card horizontal padding and tab separation. |
| 36px | Default split-opening copy inset. |
| 40px | Heading-to-feature-grid gap and promotional stage inset. |
| 48px | Chapter heading-to-carousel gap. |
| 64px | Footer inset and product configuration grid gutter. |
| 80px | Standard section top padding and compact chapter bottom padding. |
| 96px | Centered proof and membership-band padding. |
| 120px | Long chapter bottom padding or major centered introduction top padding. |

### Containers and grids

- **content-wrapper**: max width 1272px · side padding 20px. Centered outer wrapper; its usable content spans 1232px at desktop, leaving 104px to each viewport edge.
- **reading-width**: max width 827px. Centered headline/support blocks; narrower than media grids.
- **feature-grid**: 3 columns · gap 24px. Three equal media columns, about 395px each, with images above text and no enclosing card edge.
- **media-rail**: gap 24px. Fixed 362px-wide slides overflow a 1232px viewing area; three complete cards and a glimpse of the next.
- **paired-conversion**: 2 columns · gap 24px. Two 604px-wide editorial destinations on charcoal.
- **product-configuration** (only for product purchase pages): max width 1272px · 12 columns · gap 64px · side padding 20px. Large persistent gallery on the left and a 476px configuration stack on the right; imagery occupies the larger share.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-media | 0px |
|  | quote-and-option-cards | 8px |
|  | newsletter-field | 8px |
|  | progress-track | 9999px (pill) |
| product purchase pages | purchase-summary | 4px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | quote-card | `0px 1px 3px 0px rgba(0, 0, 0, 0.1), 0px 1px 2px -1px rgba(0, 0, 0, 0.1)` | Very slight elevation under mint-outlined quote cards. |
| product purchase pages | purchase-summary | `0px 0px 20px 0px rgba(0, 0, 0, 0.1)` | Floating configuration total bar. |

### Surfaces

#### White canvas · level 0

**Use:** Default light chapters and the visible footer.

**CSS:** `background: #ffffff; color: #1c1c1a`

**Observed:** Flat full-width areas, not raised application panels.

**Transfer:** Use as the primary explanatory setting.

#### Charcoal chapter · level 0

**Use:** Immersive proof, capabilities and conversion sections.

**CSS:** `background: #1c1c1a; color: #f4f4f4`

**Observed:** Large uninterrupted dark bands alternate with light chapters.

**Transfer:** Switch the entire section theme rather than placing dark cards on a light page.

#### Soft panel · level 0

**Use:** Opening copy panel and quotation or comparison bands.

**CSS:** `background: #f4f4f4; color: #1c1c1a`

**Observed:** Low-contrast gray separates the calm introduction and editorial proof from white.

**Transfer:** Use sparingly to distinguish a change in narrative mode.

#### Warm editorial panel · level 0

**Use:** Text beneath portrait and article images; warm capability sections.

**CSS:** `background: #f6f6f1; color: #1c1c1a`

**Observed:** A subtle ivory cast, without texture, border or heavy shadow.

**Transfer:** Use warmth in neutral surfaces rather than adding a second brand hue.

#### Story image shade

**Use:** Readability behind bottom-aligned testimonial copy.

**CSS:** `background: linear-gradient(180deg, rgba(0, 0, 0, 0) 35%, rgba(0, 0, 0, 0.75) 100%)`

**Observed:** Portrait photography darkens toward its bottom while the face and setting remain visible.

**Transfer:** Match the dark lower fade to the copy height; keep the upper image legible.

#### Campaign scrim

**Only for:** full-bleed collection campaigns

**Use:** Readability on studio photography.

**CSS:** `background: linear-gradient(161deg, rgba(0, 0, 0, 0.4), rgba(2, 2, 2, 0) 100%)`

**Observed:** A directional dark veil supports white text without flattening the scene.

**Transfer:** Preserve the studio's atmospheric light and local contrast.

#### Purchase summary · level 2

**Only for:** product purchase pages

**Use:** Persistent total and action after leaving the configuration area.

**CSS:** `background: #ffffff; border-radius: 4px; padding: 24px 40px; box-shadow: 0px 0px 20px 0px rgba(0, 0, 0, 0.1)`

**Observed:** Inset 24px from viewport sides; line items on the left and total with a mint action on the right.

**Transfer:** Reserve for pages with an actual configured purchase, not ordinary storytelling.

#### Comparison striping

**Only for:** product comparison tables

**Use:** Long specification tables.

**CSS:** `background: #e6ebef`

**Observed:** Rows alternate with soft gray; first-column cells alternate pale blue and deeper blue, making the label column subtly stronger.

**Transfer:** Keep tinted colors confined to the table and avoid boxed cells.

## Components

### Navigation band

**Use:** Persistent brand and shopping navigation.

**CSS:** `background: #f5f5f5; padding: 8px 20px; height: 73px`

**Text style:** `navigation` — GT America 400 · 16px/1.2 · uppercase

**Observed:** A 33px charcoal announcement strip sits above the band. A compact wordmark anchors the left, four centered menu labels use small downward chevrons, and a black destination action plus cart sit right. The inner row is limited to 1248px.

**States:** Declared: hover on a menu ancestor adds a 1px underline.

**Transfer:** Keep the two-tier density and use the new product's own compact identity.

### Primary button

**Use:** Default conversion action within narrative chapters.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #11ddc4; color: #1c1c1a; border: 1px solid #11ddc4; border-radius: 0px; padding: 8px 16px; height: 42px`

**Text style:** `button` — GT America 500 · 16px/1.5 · uppercase

**Observed:** Text-led and compact, with an occasional right arrow. Multiple centered actions have 24px gaps. A purchase-form version grows to 48px high.

**States:** Declared: hover mixes the accent at 60% with white at 40% for both background and border.

**Transfer:** Keep intrinsic widths for narrative actions; use full width only inside a purchase stack.

### Contrast button

**Use:** Opening and high-contrast actions.

**CSS:** `background: #000000; color: #ffffff; border-radius: 0px; padding: 8px 16px; height: 40px`

**Text style:** `button` — GT America 500 · 16px/1.5 · uppercase

**Observed:** Paired tightly in the opening. On charcoal promotional and reversal bands, the inverse variant uses soft-gray fill and edge with charcoal text, at 42px high.

**States:** Declared: hover mixes the accent at 60% with white at 40% for background and border.

### Directional link

**Use:** Feature discovery and article navigation.

**CSS:** `display: inline-flex; color: #1c1c1a; text-transform: uppercase`

**Text style:** `directional-link` — GT Mono 300 · 16px/1.2 · uppercase

**Observed:** Monospaced text is followed by a small right arrow; it reads as a technical annotation rather than a filled action. A light variant sits on charcoal.

**Transfer:** Use short destination labels and leave space between copy and link.

### Editorial media card

**Use:** People, articles and feature rails.

**CSS:** `background: #f6f6f1; padding: 24px; border-radius: 0px`

**Text style:** `body-small` — GT America 400 · 14px/1.2

**Observed:** This is the text-panel recipe below edge-to-edge media. Portrait cards use a square image and expanded card title; article cards use 4:3 media, sentence-case title, muted description and a Directional link. Whole cards are about 362px wide.

**Transfer:** Keep photography dominant and make the lower panel only as tall as its concise copy needs.

### Quote card

**Use:** Press and text-only customer proof.

**CSS:** `background: #f4f4f4; border: 1px solid #11ddc4; border-radius: 8px; padding: 24px 32px; box-shadow: 0px 1px 3px 0px rgba(0, 0, 0, 0.1), 0px 1px 2px -1px rgba(0, 0, 0, 0.1)`

**Text style:** `body-lead` — GT America 400 · 20px/1.2

**Observed:** A centered carousel emphasizes its middle card while neighboring cards scale to 0.8. The smaller visible cards are about 323px by 236px; the centered card is about 404px by 295px. Attribution uses small black expanded capitals.

**Transfer:** Use a small number of substantial quotations instead of star-filled review tiles.

### Story overlay

**Use:** Photo-led customer proof.

**CSS:** `position: absolute; bottom: 0px; padding: 24px; color: #f4f4f4`

**Text style:** `body-small` — GT America 400 · 14px/1.2

**Observed:** Over a 362px by 483px portrait, a small quotation mark precedes the text; a bold expanded attribution closes it. Story image shade separates the lettering from the photograph.

**Transfer:** Prefer a real person in their environment to an isolated avatar.

### Newsletter field

**Use:** Email signup in the footer.

**CSS:** `background: #ffffff; border: 1px solid #6b7280; border-radius: 8px; padding: 8px 44px 8px 12px; width: 226px; height: 42px`

**Observed:** A mint Primary button sits beside the field, below a short expanded heading and one small sentence. Contact and social links sit below the form.

**Transfer:** Retain the compact field-and-button pairing rather than a large standalone subscription banner.

### Capability selector

**Only for:** interactive capability explorers

**Use:** A vertical set of topics paired with changing media.

**CSS:** `border-left: 2px solid #e5e7eb; padding-left: 16px; color: #1c1c1a`

**Text style:** `explorer-label` — GT Expanded 900 · 24px/0.9 · uppercase

**Observed:** The active item reveals 20px supporting copy below the title. Inactive labels are gray with no visible explanatory copy. Each row has 16px vertical breathing room; the adjacent media stage is about 616px by 720px. The media can sit on either side.

**Transfer:** Keep one clear active topic and a readable column of alternatives rather than turning this into a compact horizontal tab bar.

### FAQ row

**Only for:** question-and-answer sections

**Use:** Resolve practical objections after capabilities and proof.

**CSS:** `border-bottom: 1px solid #e5e7eb; padding: 16px 0px`

**Text style:** `faq-question` — GT America 700 · 20px/1.2

**Observed:** A wide question sits left and a simple plus or minus sits at the far right. Open answers use 16px body copy under the label; the background is soft gray and the row is not a rounded card.

**Transfer:** Use straightforward questions with concise explanatory answers.

### Purchase option

**Only for:** product purchase pages

**Use:** Payment, accessory and protection choices.

**CSS:** `display: flex; flex-direction: column; gap: 10px; border: 1px solid #1c1c1a; border-radius: 8px; padding: 16px`

**Text style:** `body` — GT America 400 · 16px/1.2

**Observed:** The selected choice has the dark edge; alternatives have pale rules. A 20px circular radio with a mint selected center sits left, label and right-aligned price follow, and optional detail appears below. Some choices reserve 40px of left padding for the control.

**Transfer:** Keep configuration utilitarian and distinct from the unboxed narrative cards.

### Comparison label cell

**Only for:** product comparison tables

**Use:** Feature labels in a three-column comparison.

**CSS:** `background: #ebf1f5; padding: 8px 0px 8px 10px; position: sticky`

**Text style:** `table-label` — GT Expanded 700 · 10px/0.9 · uppercase

**Observed:** Label column occupies one third of the 1280px-wide table; two centered value columns follow under product cutouts. Rows are commonly 46px high, increasing for wrapped details. Alternating label cells use the deeper blue tint.

**Transfer:** Let alignment and striping carry the table, not a grid of heavy rules.

## Imagery and graphics

### Architectural product scene

**Use:** Default opening and product demonstrations.

**Observed:** Black hardware is shown with real depth against cream plaster, pale curtains, window light and occasional greenery. A side-on view makes the object slender and sculptural; the opening image occupies the right 60% of the stage. Light is soft and directional, with restrained warm neutrals rather than saturated scenery.

**Transfer:** Photograph the new object in an uncluttered, credible environment with a visible wall or architectural plane. A still with soft side light, a grounded shadow and a small natural detail is the minimum equivalent.

### Human product proof

**Use:** Benefits, portraits and story rails.

**Observed:** People actively use the product in domestic or controlled studio spaces. Feature images are 4:3; coach portraits are square with gray backdrops; customer stories are tall environmental portraits. Images run flush to rectangular edges and are neither collaged nor enclosed in device frames.

**Transfer:** Use context appropriate to the new product, natural skin tones and direct physical interaction. Show the person and the relevant product detail in the same frame.

### Technical demonstration media

**Use:** Explain adaptive or intelligent capabilities.

**Observed:** Black UI plates carry white numerals and thin green traces, or UI fragments and phone cutouts sit on photographic turquoise backdrops. These are bounded pictures within neutral marketing sections, not an alternate page-wide UI palette.

**Transfer:** Show one real capability at a time with a faithful interface detail. Keep interface colors inside the media and avoid reproducing a complex dashboard as surrounding page decoration.

### Reversal typography

**Use:** A signature graphic statement within the narrative.

**Observed:** A short phrase is stacked in broad white capitals on charcoal. The lower line contains a crossed-out weaker word immediately followed by the stronger replacement, with a thin muted label above.

**Transfer:** Write an authentic before-to-after contrast for the new offer, preserving the theatrical replacement rather than the original wording.

**Build:** Use live centered text in the reversal recipe, constrained to about 639px. Wrap the weaker term in an inline span with text-decoration-line: line-through; place the stronger term beside it. Keep the earlier lines short enough to form a compact stacked block, with soft-gray lettering against charcoal.

### Studio campaign scene

**Only for:** program or collection campaigns

**Use:** Full-bleed collection introductions and catalog cards.

**Observed:** An athlete and product occupy a theatrical blue-gray studio with a glossy dark floor and a luminous rectangular architectural frame. White text overlays the spacious left side. Catalog squares repeat the same studio lighting so the collection feels coherent.

**Transfer:** Use a product-appropriate human demonstration on a cool studio set with one simple illuminated frame; preserve open copy space and a tangible floor.

**Build:** Construct a practical or rendered rectangular light frame behind the subject, rotated slightly in perspective; use a white emissive inner rim with a subtle cool-blue spill along the floor. Keep the wall blue-gray and the floor dark and softly reflective; the frame must support a real photographed or rendered subject, not replace it with abstract neon.

### Icons

**Observed:** Navigation uses small downward chevrons, a black cart and compact social marks. Carousel arrows sit in 40px square controls or appear bare beside progress numbers. Supporting value and closing-choice icons are approximately 59px square, simple black-and-white pictograms backed by light squares.

**Transfer:** Use sparse monochrome functional symbols and straightforward pictograms; reserve mint for selected states and progress rather than coloring every icon.

## Section recipes

How recurring sections are built.

### First screen: Architectural split opening

**Observed:** A 106px two-tier Navigation band precedes a 600px-high stage. The left 40% is Soft panel with a vertically centered, left-aligned copy group inset 36px. The right 60% is Architectural product scene: curtains and a plant establish scale while a tall dark object sits toward the right side in natural light. Layers are flat neutral panel and full-height media first, then live text, two Contrast buttons and a small eligibility annotation. The headline uses opening, taking two lines across most of the text panel, with 20px before the actions. Within the first 900px the entire stage, headline, buttons and product are visible; the next white chapter begins at 706px and its large centered promise is visible, while its feature images fall below the fold.

**Transfer:** Use an equally strong side-lit product still if no video exists; the media must communicate physical quality and scale. Keep the opening conversational rather than automatically using the expanded display face. Library pages instead open with a centered 48px expanded promise and support; technology variants use charcoal and then a large inset demonstration. Collection campaigns use a full-bleed scene and 42px overlay headline. Purchase pages open with a gallery and configuration column.

**Avoid:** Do not center a giant expanded headline over the default image, turn the scene into a floating cutout on a gradient, or introduce a long support paragraph that displaces the product and actions.

**Text style:** `opening` — GT America 300 · 38px/1.1

### Centered chapter introduction

**Observed:** Use heading-lg for the strongest promise or heading for recurring chapters, centered over body-lead in a reading-width block. Heading-to-copy gap is 8px; action groups follow with 24px separation. White canvas and Charcoal chapter provide the two primary themes.

**Transfer:** State a single outcome before explaining it. Shorter chapters can omit the action and flow directly into media.

**Text style:** `heading` — GT Expanded 900 · 32px/0.9 · uppercase

### Three-column feature proof

**Observed:** Feature-grid uses 24px gutters and about 395px by 296px images. Titles begin 24px below media, descriptions 8px below titles and Directional links 16px after copy. A major chapter uses 80px top and 120px bottom padding. White and charcoal variants keep the same alignment.

**Transfer:** Show one distinct capability per column using media, a short benefit and a compact explanation; use feature-title for quieter cards and card-title for emphatic capability chapters.

### Heading pair and clipped rail

**Observed:** A left-aligned heading shares its row with support copy or a mint action on the right. After 48px, a media-rail exposes three full cards and the next card's leading edge. Editorial media card or Story overlay supplies the card treatment. Controls sit beneath; one variant has a 4px mint progress fill on a neutral track with two-digit current and total numbers and arrows.

**Transfer:** Include this horizontal editorial device in the narrative, choosing capabilities, people, resources or customer proof to suit the new product.

### Centered quote theater

**Observed:** Soft panel supports an expanded section heading and a carousel of Quote cards. The center card is full scale, neighbors are reduced to 0.8 and spaced apart; small arrows sit beneath. Text rather than portrait imagery carries this proof.

**Transfer:** Use independently credible quotes with attribution. Retain the center-versus-neighbor scale contrast instead of making a uniform testimonial grid.

### Reversal conversion statement

**Observed:** Charcoal chapter centers Reversal typography, a thin muted label, body-lead in silver and two light Contrast buttons. The statement is about 639px wide, uses 56px type and occupies a 513px band with 80px top and bottom padding. The action row is noticeably separated from the support line.

**Transfer:** Make the transformation memorable with a crossed-out lesser outcome and a positive replacement; the device can appear wherever the argument earns it.

**Text style:** `reversal` — GT Expanded 900 · 56px/0.9 · uppercase

### White utility footer

**Observed:** The visible footer is White canvas, about 614px tall. A wide newsletter/contact column sits beside five narrower link columns. Content has 64px top and side insets, small expanded headings, 14px body links and 24px group gaps. A thin dark rule separates the bottom copyright and privacy row. A soft-gray fine-print band can precede it.

**Transfer:** End even a dark chapter with this light, dense utility area. Keep the footer functional and compact relative to the large storytelling sections.

### Vertical capability explorer

**Only for:** capability and product detail pages

**Observed:** A heading and vertical Capability selector occupy one half of a 1232px area, with a tall media stage on the other. Active copy expands beneath one 24px title and a fine vertical rule marks its edge; alternatives remain compact gray labels.

**Transfer:** Use for a family of closely related features whose media can change without changing the section structure.

### Featured editorial spotlight

**Only for:** program or collection campaigns

**Observed:** An inset dark stage with 40px outer padding pairs a broad copy area and a 382px by 680px vertical video. A small light tag precedes a 32px black-weight heading and a 32px light expanded credit. Body copy and a thin divider lead into a short cadence or specification graphic.

**Transfer:** Spotlight one flagship use case, creator or collection with a visibly different heavy/light expanded heading pair.

### Catalog with goal tabs

**Only for:** program or collection catalogs

**Observed:** A sentence-case catalog-heading leads a row of small goal tabs, a fine horizontal separator and a short introduction. Three square image cards follow, with a compact title, creator line, description and cadence metadata on soft-gray panels.

**Transfer:** Group a substantial collection by reader intent. Keep the same studio treatment across each card rather than designing unique decorative backgrounds.

### Practical purchase chapter

**Only for:** product purchase pages

**Observed:** A large square gallery stays visually present while the configuration column progresses through payment, accessories, protection, delivery and total. Purchase option cards and configuration-heading create the rhythm. Later chapters use a three-column comparison table and a delivery section pairing a wide room diagram with three numbered explanatory steps.

**Transfer:** Separate narrative persuasion from configuration detail. Explain physical setup or service onboarding with a concrete diagram and sequential steps.

### Secondary closing choices

**Only for:** capability and collection landing pages

**Observed:** A dark closing band offers three equal columns with square monochrome pictograms, 18px expanded titles, 18px copy and light Directional links. A library variant instead has two 604px-wide 4:3 images over titles, descriptions and mint actions.

**Transfer:** Offer distinct next steps for readers at different levels of commitment, without repeating one generic CTA three times.

## Page flow

**Storyline:** Human promise → tangible demonstration → capability chapters → credible proof → practical reassurance → a clear next step → utility footer.

### Broad brand and product landing page

1. **promise** — Calm split photographic opening with light benefit headline and paired dark actions.
2. **capability proof** — Large expanded promise over a three-column image grid, followed by a promotional scene and dark service-benefit chapter.
3. **human credibility** — Light portrait rail followed by dark environmental customer stories and a light text-quote carousel.
4. **continued discovery** — Editorial resources rail with compact panels and directional links.
5. **closing call** — Dark reversal statement, paired light actions, a fine-print band and white newsletter/link footer.

**Transfer:** Use as the default narrative model, preserving the contrast between calm product staging, athletic headings and editorial proof without requiring the same number of chapters.

### Structured collection or program catalog

1. **promise** — Full-bleed studio campaign scene with white expanded headline.
2. **fit** — Three icon-supported benefits explain suitability for different needs.
3. **featured offering** — Dark spotlight pairs heavy/light headline cuts with vertical demonstration media.
4. **selection** — Goal tabs and a three-card catalog lead into mint-outlined member quotes.
5. **objection handling** — A split cross-link chapter and long ruled FAQ clarify adjacent offerings and practical questions.
6. **closing choices** — Three dark icon-led destinations lead directly into the white utility footer.

**Transfer:** Use when a product includes a curated library or structured service plans; make filtering and suitability more explicit than on a broad landing page.

### Explain a varied capability library

1. **promise** — Breadcrumbs, centered white expanded introduction, support and paired mint actions.
2. **product demonstration** — Tall media paired with a long vertical capability selector.
3. **capability chapters** — A dark collection rail and a light personalization rail explain breadth and control.
4. **service reassurance** — Centered soft-gray membership statement and a mono discovery link.
5. **closing choices** — Two photographic destinations on charcoal, then the white utility footer.

**Transfer:** Make breadth navigable with an active selector rather than a wall of equal feature tiles.

### Make intelligent hardware feel understandable

1. **promise** — Breadcrumbs precede a centered charcoal headline and support.
2. **product demonstration** — Large architectural video sits inset within the dark chapter.
3. **capability proof** — Warm three-column technical imagery explains adaptation, followed by a dark three-column guidance chapter.
4. **service reassurance** — Centered white membership statement and mono link.
5. **closing choices** — Dark three-column icon destinations, followed by the white utility footer.

**Transfer:** Show material quality before interface detail; then explain technical benefits in paired light and dark chapters.

### Support a considered configurable purchase

1. **purchase** — Breadcrumbs and a large architectural gallery accompany a compact configuration stack; a floating summary carries total and action during later reading.
2. **social proof** — A centered review module establishes customer credibility before deeper feature content.
3. **capability chapters** — Dark hardware-detail rail and a light accessories explorer.
4. **comparison** — A soft-gray comparison chapter uses product cutouts, tinted label cells and alternating rows.
5. **practical reassurance** — Room diagram and numbered delivery/setup steps explain the commitment.
6. **service value** — A final dark benefit rail explains ongoing value before the white utility footer.

**Transfer:** Use the compact commerce opening only when the reader needs to choose options; keep the rest of the narrative visually consistent with marketing chapters.

## Writing

Confident and encouraging, with an athletic sense of progress balanced by practical explanations. Benefits sound personal and attainable; technology is described through the work it removes rather than jargon alone.

**Do not copy:** Do not reuse Tonal names, logos, proprietary program or feature names, coach identities, testimonials, performance claims, prices, membership terms, counts or eligibility claims. Use independently supportable facts and original wording for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to “you” and “your.” Refer to the product by name in explanatory copy and use “our” sparingly for people or service support.
- **Rhythm:** Short benefit headlines, often two parallel clauses, contrast with one or two compact explanatory sentences. Strong verbs open actions; sentence fragments are acceptable for headlines and labels.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Repeat a short benefit structure to connect a practical gain with an emotional one. | 8–12 words | “Get your time back. Get your strength back.” |
| Section lead | A strong capability and its user benefit in a compact phrase. | 4–9 words | “Making progress, made easier”<br>“Variety to keep you motivated” |
| Supporting explanation | Explain what happens automatically, then why it helps the reader. | 20–40 words | “[Brand] learns your strength and sets the optimal resistance for every rep, increasing in as little as one-pound increments to keep you challenged as you get stronger.” |
| Action | An imperative verb plus a concrete destination or experience. | 2–5 words | “Meet the Coaches”<br>“Explore Workouts” |
| Closing prompt | A forward-looking personal question followed by an encouraging invitation. | 12–20 words | “Where could you be in six months? Join the [Brand] community and start your strong.” |
| Objection handling | Ask the plain-language question the reader would actually use. | 5–12 words | “How are [Brand] programs different from individual workouts?” |

**Words and phrasing to use:** your; progress; built for; adapts; guidance; get more out of; without the guesswork; unlock; fit your life; start

**Avoid:** revolutionary ecosystem; disruptive synergy; elite-only; effortless perfection; miracle; guaranteed transformation

**Rules:**

- Lead with the reader's desired outcome, then reveal the mechanism.
- Tie each technical capability to a specific reduction in effort, uncertainty or friction.
- Use parallel phrasing for related benefits without making every heading a slogan.
- Place commercial conditions close to the relevant action and keep them matter-of-fact.
- Keep proof in the speaker's own language and separate it visually from the brand's explanation.

## Do's and Don'ts

### Do

- Pair 38px light sentence-case introductions with 32px or 40px weight-900 expanded chapter headings.
- Use 0.9 line height for expanded display text and 1.2 for most explanatory copy.
- Keep 24px media gutters and preserve the next-card glimpse in horizontal rails.
- Give major feature chapters 80px top padding and up to 120px below.
- Use mint in compact 42px-high actions, thin proof outlines and 4px progress fills.
- Stage products with soft side light, cream architecture and real scale cues.
- Keep card descriptions compact at 14px/1.2 and use 24px text-panel insets.
- End with a white utility footer even after an immersive charcoal closing chapter.

### Don't

- Do not use condensed athletic fonts in place of the broad expanded grotesk.
- Do not letter-space display headings to imitate width; tracking stays normal.
- Do not round conversion buttons to 8px or pills; those radii belong to fields and special proof or option cards.
- Do not spread the mint accent into large solid marketing backgrounds.
- Do not give every image card a border and shadow; most narrative media is flat and square-edged.
- Do not make customer-story quotations float outside their photographs; anchor them at the shaded bottom.
- Do not apply the blue-gray comparison striping to ordinary feature grids.
- Do not make the footer charcoal merely because the surrounding final chapter is dark.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color, background-color, border-color and opacity transitions of 0.3s with cubic-bezier(0.4, 0, 0.2, 1).
- Editorial elements declare easedSlideUp at 1.2s with cubic-bezier(0.4, 0, 0, 1), once and forwards.
- Editorial card headings declare 0.5s transforms with opposite vertical movement on hover and focus-within.
- The purchase-summary surface declares all-property transitions at 0.5s with cubic-bezier(0.4, 0, 0.2, 1); the mint progress fill declares 0.3s duration.

**Transfer:**

- Let product footage and editorial rail movement supply energy while the surrounding architecture stays visually stable.
- Keep the declared mint-to-white button hover and restrained editorial heading movement, rather than adding bounce to the rectangular controls.

**Unknown:**

- Autoplay cadence, exact scroll triggers and reduced-motion variants are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 960px, 1024px, 1200px and 1440px.
- The opening declares a column layout below the medium breakpoint; its narrow copy panel uses 24px horizontal and 16px vertical padding.
- The newsletter form declares a stacked narrow layout, and the desktop navigation declares a hidden narrow state.

**Transfer:**

- On narrow layouts, stack the opening media and text while preserving the contrast between light copy and architectural scene.
- Retain horizontal browsing for editorial rails instead of shrinking four portraits into tiny columns.
- Keep the comparison's label column readable and allow horizontal overflow when all values cannot fit.

**Unknown:**

- Exact mobile type sizes, media order, navigation interaction and all breakpoint-specific layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
