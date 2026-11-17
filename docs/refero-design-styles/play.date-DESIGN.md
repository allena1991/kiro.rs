# Playdate — pocket-sized exuberance

## Overview

A cheerful, tactile style that makes a small product feel like a fascinating object worth picking up. Warm yellow and electric purple punctuate slate gray, charcoal and pale gray, with chunky grotesk headings and unusually readable conversational paragraphs. Cutout product renders, monochrome miniature artwork and brightly backed photography carry much of the story; the composition is spacious around objects and compact inside collections.

### Essentials

- Object before slogan: a centered 1100px-wide stage puts a warmly lit product above the fold, with the 57px/1.1 bold introduction only entering near the bottom of a 900px screen.
- Chapter titles sound like confident little declarations: 68.4px/1, weight 800, normal tracking, usually left-aligned in an 800px column with 30px before the paragraph.
- Color behaves like sheets of construction paper, not tiny decoration: yellow carries the longest capability chapters, purple carries offers and the final tableau, and charcoal grounds technical detail. Pale gray is the scoped default for utility and browsing pages.
- Actions feel like physical controls: rounded pills use bold 28.5px or 34.2px text; the main promotional action is an 81px-tall glossy purple capsule with inset highlights and a dark lower edge. Form submits instead use 6px corners.
- Products escape the text column: transparent cutouts, hand-held views and exploded assemblies extend into the side space, while miniature monochrome panels pack into a 1070px three-column grid with 10px gaps. Use an isolated interface composition when no physical object exists.
- Keep a playful graphic interruption and an object-led farewell: oversized stacked word artwork and a cloud-shaped thought callout interrupt the prose, and a purple closing stage shows multiple product views above centered identity details and compact link columns. Rebuild these with original words, overlapping SVG ellipses and interface views when necessary.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm yellow | `#ffc833` | `--color-yellow` | background, action, accent | Dominant capability bands, bright action fills and technical pictograms. |
| Electric purple | `#6c00ff` | `--color-purple` | background, action, link | Offer bands, the closing object tableau and prominent pills. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet highlight | `#9400ff` | `--color-gloss-top` | action | Upper stop of the glossy promotional capsule. |
| Violet lower edge | `#5c00ff` | `--color-gloss-bottom` | action | Lower stop of the glossy promotional capsule. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Text on purple, charcoal and slate; speech bubbles and resource cards. |
| Pale gray | `#efefef` | `--color-canvas` | background, surface | Collection interludes and email fields; full-page ground on utility and browsing pages. |
| Warm screen paper | `#e8e4da` | `--color-paper` | surface, border | Monochrome miniature art and information-card backs; email field edge. |
| Warm gray | `#b1afa8` | `--color-muted` | text, action | Technical category labels and secondary credits actions on charcoal. |
| Slate stage | `#7a8085` | `--color-stage` | background, surface | Opening object stage and thought-cloud backing. |
| Warm near-black | `#312f28` | `--color-ink` | text, background, border | Default text on yellow and pale surfaces, dark capability actions, fine tile edges. |
| Charcoal | `#212223` | `--color-charcoal` | background | Technical detail and the extended reassurance chapter. |
| Graphic black | `#000000` | `--color-black` | text, background | Hard-contrast graphic artwork and collection action fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| commerce pages | Store ink | `#222222` | `--color-utility-ink` | text | Store product names and descriptions. |
| utility and commerce pages | Cool secondary gray | `#64676c` | `--color-utility-muted` | text, border | Secondary currency, light-page footers and form outlines. |
| audience-specific campaigns | Aqua chapter | `#5ec3aa` | `--color-aqua` | background | A self-contained audience-specific chapter rather than the general capability theme. |
| developer resource pages | Tool blue | `#306fb6` | `--color-tool-blue` | surface | Developer download hero panel. |
| developer resource pages | Mint ground | `#9be4b6` | `--color-mint` | background | Full-width approachable-tool chapter ground. |
| developer resource pages | Tool green | `#60be83` | `--color-green` | surface | Inset tool panels within the mint chapter. |

## Typography

- **Roobert** — All marketing headings, prose, actions and utility text. Rounded but sturdy grotesk with open counters, friendly curves and a particularly assertive extra-bold cut. If unavailable, use **DM Sans**. Use 300–800; preserve the broad headings and generous body size. Font stack: "Roobert", "DM Sans", Helvetica, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | Roobert | 800 | 68.4px | 1 | normal | Default chapter heading and closing help heading. |
| opening-introduction | Roobert | 700 | 57px | 1.1 | normal | Centered descriptive opening statement beneath the main object. |
| promotional-action | Roobert | 700 | 50.7px | 1.2 | normal | Glossy main promotional capsule. |
| help-action | Roobert | 700 | 39.9px | 1.2 | normal | Oversized purple help action on the dark closing chapter. |
| large-action | Roobert | 700 | 34.2px | 1.2 | normal | Dark capability pills with a leading pictogram. |
| newsletter-lead | Roobert | 700 | 34.2px | 1.3 | normal | Bold reassurance above the email field on the dark chapter. |
| body | Roobert | 400 | 28.5px | 1.3 | normal | Core explanatory prose, with inline bold emphasis and underlined links. |
| action | Roobert | 700 | 28.5px | 1.2 | normal | Yellow purchase pills and form submits. |
| thought | Roobert | 700 | 24.2px | 1.3 | normal | Short quote in the slate thought cloud. |
| tile-title | Roobert | 800 | 24.1px | 1 | normal | Title on the reverse of a miniature collection card. |
| navigation | Roobert | 700 | 21.9px | 1.2 | -0.0075em | Compact icon-led global navigation. |
| spec-label | Roobert | 400 | 21.4px | 2 | normal | Muted technical category labels. |
| spec-value | Roobert | 700 | 21.4px | 1.2 | normal | Compact bold factual values beside technical pictograms. |
| footer | Roobert | 400 | 21.4px | 1.2 | normal | White identity information and link columns in the purple farewell. |
| caption | Roobert | 400 | 18.5px | 1.2 | normal | Miniature-card creator credits; also light utility footer text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| commerce pages | store-heading | Roobert | 700 | 57px | 1 | normal | Major product name beside a gallery. |
| commerce pages | price | Roobert | 300 | 47px | 1 | normal | Light-weight major price with currency on the same baseline. |
| developer resource pages | resource-heading | Roobert | 700 | 42.8px | 1.1 | -0.0075em | Centered audience heading above tool groups. |
| developer resource pages | resource-card-heading | Roobert | 700 | 32.1px | 1 | normal | Card headings paired with small illustrative icons. |
| catalog and browsing pages | collection-caption | Roobert | 600 | 32.1px | 1.1 | -0.0075em | Centered title immediately below wide illustrated banners. |
| commerce pages | store-body | Roobert | 400 | 22.8px | 1.3 | normal | Product descriptions and factual purchase support. |
| developer resource pages | resource-body | Roobert | 400 | 21.4px | 1.3 | normal | Tool descriptions and resource summaries. |
| developer resource pages | resource-link | Roobert | 700 | 19.2px | 1.2 | normal, uppercase | Small capsule links to resources. |

**Notes:**

- The main hierarchy comes from size and weight, not aggressive negative tracking. Keep normal tracking on the 68.4px extra-bold titles and 28.5px prose.
- Inline strong phrases carry the useful distinction inside a paragraph; they do not become a second heading.
- The giant stacked word artwork is a graphic device, separate from the live-text scale. Give it broad heavy letters, tight stacked lines and roughly 630px of width at desktop rather than enlarging every heading.

## Layout

**Density:** Airy around hero objects and chapter changes; closely packed in art collections, navigation and technical rows.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Miniature collection grid gaps and resource-card top margin. |
| 10.7px | Technical-row vertical margins and resource heading-to-copy spacing. |
| 14.3px | Email input padding and commerce row spacing. |
| 21.4px | Resource-card vertical padding and resource grid gaps. |
| 26.7px | Resource-card horizontal padding. |
| 28.5px | Body paragraph margins and commerce column gap. |
| 30px | Chapter heading-to-copy gap and form-to-submit separation. |
| 60px | Chapter top margins and footer separation. |
| 120px | Opening stage top padding and generous thought-cloud breathing room. |

### Containers and grids

- **Reading column**: max width 800px · side padding 28.5px. Centered prose and chapter-title alignment; use the same left edge through a long colored band.
- **Object stage**: max width 1100px. Centered opening product scene and large demonstrations; art may overlap the adjacent text region.
- **Navigation rail**: max width 1300px · side padding 10px. Wordmark at left, compact icon-led links at right.
- **Miniature collection**: max width 1070px · 3 columns · gap 10px. 350px-wide artwork tiles arranged as a dense wall.
- **Resource grid** (only for developer resource pages): max width 800px · 2 columns · gap 21.4px. Wide tool hero and documentation cards span both columns; supporting cards split evenly.
- **Commerce grid** (only for commerce pages): max width 900px · 2 columns · gap 28.5px · side padding 28.5px. Major product rows pair square gallery and purchase copy; smaller items occupy a two-column listing.
- **Collection banners** (only for catalog and browsing pages): max width 800px · 2 columns · gap 40px. Wide 800px banners alternate with paired 380px cards; vertical gap is 20px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Capability pills | 34.2px |
|  | Purchase pills | 28.5px |
|  | Form controls | 6px |
|  | Miniature art | 2.9px |
| developer resource pages | Resource cards | 10px |
| catalog and browsing pages | Collection artwork | 10.7px |
| commerce pages | Commerce gallery | 11.4px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Glossy capsule | `rgba(255, 255, 255, 0.6) 0px 2.5px 2.5px 0px inset, rgba(0, 0, 0, 0.5) 0px -2.5px 4.1px 0px inset, rgba(255, 255, 255, 0.3) 0px -0.5px 25.4px 0px inset, rgba(0, 0, 0, 0.4) 0px 2.5px 5.1px 0px` | Main promotional capsule only. |
| catalog and browsing pages | Printed card stack | `rgba(0, 0, 0, 0.498) 5.3px 5.3px 0px 0px, rgba(0, 0, 0, 0.25) 10.7px 10.7px 0px 0px` | Selected collection bundles, not every individual item. |

### Surfaces

#### Slate object stage · level 0

**Use:** Default marketing opening.

**CSS:** `background-color: #7a8085; background-image: radial-gradient(rgba(255, 255, 255, 0.5) 0px, rgba(255, 255, 255, 0) 50%, rgba(255, 255, 255, 0) 100%)`

**Observed:** A soft white pool of light sits behind a freestanding product rather than inside a rectangular card.

**Transfer:** Keep a cool neutral ground and broad diffused illumination behind the focal object.

#### Yellow chapter sheet · level 0

**Use:** The primary long-form capability canvas.

**CSS:** `background-color: #ffc833; color: #312f28; padding-top: 20px; padding-bottom: 20px`

**Observed:** Several chapters share one uninterrupted full-width color field.

**Transfer:** Let the shared sheet connect related demonstrations without boxing each paragraph.

#### Purple offer sheet · level 0

**Use:** Price presentation and closing object tableau.

**CSS:** `background-color: #6c00ff; color: #ffffff`

**Observed:** White prose and yellow action controls sit directly on the saturated field.

**Transfer:** Make offers and the farewell visually decisive, not pale tinted panels.

#### Charcoal reassurance sheet · level 0

**Use:** Technical details, origin story, signup and help.

**CSS:** `background-color: #212223; color: #ffffff; padding-top: 20px; padding-bottom: 20px`

**Observed:** A continuous dark chapter contains varied factual and friendly blocks.

**Transfer:** Use the darker ground to make practical details feel like the back of a thoughtfully designed package.

#### Pale interlude · level 0

**Use:** Collection demonstration and utility-page ground.

**CSS:** `background-color: #efefef; color: #312f28`

**Observed:** Bright multicolor artwork is allowed to dominate against the neutral ground.

**Transfer:** Use this treatment for browsing and functional reading, not as the default replacement for the colored marketing chapters.

#### Resource panel · level 1

**Only for:** developer resource pages

**Use:** Helpful grouped links and descriptions.

**CSS:** `background-color: #ffffff; border-radius: 10px; padding: 21.4px 26.7px`

**Observed:** Flat white cards sit on pale gray without soft floating shadows.

**Transfer:** Use a full-width card for the primary resource and paired cards for supporting destinations.

#### Blue tool hero · level 1

**Only for:** developer resource pages

**Use:** Technical download presentation.

**CSS:** `background-color: #306fb6; color: #ffffff; border-radius: 10px`

**Observed:** A text-and-download column is paired with overlapping application windows.

**Transfer:** Give the tool a clear, colored object-like panel rather than a generic dashboard mockup.

#### Mint tool chapter · level 0

**Only for:** developer resource pages

**Use:** Approachable creation-tool presentation.

**CSS:** `background-color: #9be4b6; padding-top: 85.5px; padding-bottom: 42.8px`

**Observed:** Darker green cards form a wide hero followed by two supporting resources.

**Transfer:** Preserve the two-tone green relationship inside this tool-specific theme.

#### Green tool panel · level 1

**Only for:** developer resource pages

**Use:** Cards on the mint tool chapter.

**CSS:** `background-color: #60be83; border-radius: 10px; padding: 21.4px 26.7px`

#### Aqua campaign sheet · level 0

**Only for:** audience-specific campaigns

**Use:** A distinct audience benefit chapter.

**CSS:** `background-color: #5ec3aa; color: #000000`

**Transfer:** Keep this as a clearly bounded thematic variation rather than adding aqua throughout the default page.

## Components

### Global navigation

**Use:** Persistent brand orientation and access to shop and resources.

**CSS:** `position: fixed; top: 0px; height: 59px; width: 100%; z-index: 101010`

**Text style:** `navigation` — Roobert 700 · 21.9px/1.2 · tracking -0.0075em

**Observed:** A broad wordmark sits at left and a tightly packed row of pictogram-plus-label destinations sits at right. A purple shop capsule caps the row. The rail follows the active chapter color, with white text on dark colors and dark text on yellow or pale gray.

**Transfer:** Keep the low, compact rail; use a modest number of useful destinations rather than spacious enterprise-style tabs.

### Glossy promotional capsule

**Use:** The most emphatic conversion action.

**CSS:** `background-color: #6c00ff; background-image: linear-gradient(#9400ff, #5c00ff); color: #ffffff; border-radius: 152.2px; padding: 5.1px 25.4px 15.2px; box-shadow: rgba(255, 255, 255, 0.6) 0px 2.5px 2.5px 0px inset, rgba(0, 0, 0, 0.5) 0px -2.5px 4.1px 0px inset, rgba(255, 255, 255, 0.3) 0px -0.5px 25.4px 0px inset, rgba(0, 0, 0, 0.4) 0px 2.5px 5.1px 0px`

**Text style:** `promotional-action` — Roobert 700 · 50.7px/1.2

**Observed:** Centered beneath the giant stacked word artwork; emphatic italic punctuation hugs the label.

**States:** Declared: hover unspecified; focus-visible unspecified; active reverses the light direction with a darker upper gradient and inverted inset shadows.

### Capability pill

**Use:** A strong action after a capability paragraph.

**CSS:** `background-color: #312f28; color: #ffffff; border-radius: 34.2px; padding: 8.6px 23.9px 12px`

**Text style:** `large-action` — Roobert 700 · 34.2px/1.2

**Observed:** Usually centered below left-aligned prose and prefixed by a white pictogram. Black is used for the collection-store action. The closing help variant is purple with the help-action recipe, 39.9px radius and 10px 27.9px 14px padding.

### Yellow purchase pill

**Use:** Conversion on the saturated offer band.

**CSS:** `background-color: #ffc833; color: #000000; border-radius: 28.5px; padding: 7.1px 19.9px 10px`

**Text style:** `action` — Roobert 700 · 28.5px/1.2

**Observed:** A simple flat capsule with no icon; it sits beside or below practical purchase copy rather than floating over the product.

### Email submit

**Use:** Newsletter or availability signup.

**CSS:** `background-color: #ffc833; color: #312f28; border-radius: 6px; padding: 4.3px 28.5px 7.1px`

**Text style:** `action` — Roobert 700 · 28.5px/1.2

**Observed:** Right-aligned beneath the full-width field on the dark marketing chapter; utility signup panels center a smaller version. The final exclamation mark is italic.

### Email field

**Use:** A clearly labelled single-field signup.

**CSS:** `background-color: #efefef; border: 2px solid #e8e4da; border-radius: 6px; padding: 14.3px; width: 100%; box-sizing: border-box`

**Observed:** Label sits outside and above the input. On light utility panels the field is white with a cool gray outline; the whole signup group has a fine yellow outer keyline.

### Speech toggle

**Use:** A friendly aside before a content reveal.

**CSS:** `background-color: #ffffff; color: #000000; border-radius: 10px; padding: 10px 15px; position: relative`

**Text style:** `body` — Roobert 400 · 28.5px/1.3

**Observed:** A small triangular speech tail projects from the lower-left edge; one phrase is bold and underlined.

**Transfer:** Use for a reader choice or aside, not for every feature label.

### Miniature flip tile

**Use:** Dense proof of variety through small artwork panels.

**CSS:** `background-color: #e8e4da; border: 1px solid #312f28; border-radius: 2.9px; background-size: cover`

**Text style:** `tile-title` — Roobert 800 · 24.1px/1

**Observed:** Front is monochrome title art. Reverse contains a bold title and smaller creator credits on warm paper, within the same 350px by 155px footprint. Tiles form a tight three-column wall.

**Transfer:** Create original high-contrast miniature posters or cropped outcomes rather than ordinary feature cards.

### Technical row

**Use:** Human-readable product specifications.

**CSS:** `display: grid; grid-template-columns: 2fr 3fr; align-items: center; margin-top: 10.7px; margin-bottom: 10.7px`

**Text style:** `spec-value` — Roobert 700 · 21.4px/1.2

**Observed:** Muted category label and yellow pictogram precede short bold white values. Two vertical groups sit side by side, with subtle engineering drawings outside their edges.

**Transfer:** Present genuine specifications in compact lists instead of oversized isolated statistic numerals.

### Closing footer

**Use:** Identity, practical links and a final object impression.

**CSS:** `background-color: #6c00ff; color: #ffffff; padding-bottom: 60px; margin-top: 60px; position: relative`

**Text style:** `footer` — Roobert 400 · 21.4px/1.2

**Observed:** A large multi-view product arrangement leads into a centered maker emblem and compact identity details, followed by left-aligned link columns within the reading column. Utility pages omit the large artwork, use pale gray and cool secondary text at the caption size.

**States:** Declared: hover ordinary footer links become yellow on purple and blue on pale gray; focus-visible unspecified.

### Illustrated collection banner

**Only for:** catalog and browsing pages

**Use:** Primary visual destination in an art-led listing.

**CSS:** `border-radius: 10.7px; background-size: cover; background-position: 50% 50%; padding: 0px 10.7px; margin-bottom: 5.3px`

**Text style:** `collection-caption` — Roobert 600 · 32.1px/1.1 · tracking -0.0075em

**Observed:** Wide artwork is 800px by 240px, with a fine dark alpha edge overlay and centered caption immediately below. Paired smaller variants use 380px by 228px. Creator names remain regular weight beside the title. Selected bundles use Printed card stack.

### Resource card

**Only for:** developer resource pages

**Use:** Documentation, community links and supporting tools.

**CSS:** `display: grid; background-color: #ffffff; border-radius: 10px; padding: 21.4px 26.7px`

**Text style:** `resource-card-heading` — Roobert 700 · 32.1px/1

**Observed:** A small colorful illustrative icon accompanies the heading, then a short resource-body paragraph and compact uppercase capsule links. Wide documentation cards contain full-width rounded link rows. Resource links use a pale-gray fill that turns yellow.

**States:** Declared: hover resource-link background becomes yellow; focus-visible unspecified.

## Imagery and graphics

### Tactile object render

**Use:** Opening scene and capability demonstrations.

**Observed:** A yellow handheld object floats on slate with a faint white pool behind it. Front-facing views reveal small screws, screen texture, button relief and metallic side hardware; exploded assemblies spread into the right gutter. A hand-held cutout bridges polished rendering with human scale.

**Transfer:** For hardware use a transparent high-resolution render or clean cutout with believable materials and soft directional shadows. For software isolate a few real interface views into one coherent object-like assembly, not a whole browser frame.

**Build:** Place a transparent object over a centered radial white-to-transparent halo, roughly 1100px wide. Keep the main silhouette around 600px wide at desktop, with soft shadow below. Use a large original tilted black-and-white announcement card near its upper-left side; keep the yellow object dominant.

### Stacked word sculpture

**Use:** A bold graphic interruption in the opening story.

**Observed:** Two tightly stacked heavy lowercase words form a broad yellow block on slate, about 630px wide and 400px tall. The lower line is warmer; its scale is much larger than the live headings.

**Transfer:** Set an original short product name or two-word promise in an extra-bold grotesk and treat it as artwork. The minimum version is live heavy text converted into a tightly composed two-line block.

**Build:** Use two SVG text lines or two block spans, near-touching line boxes and heavy rounded grotesk letters. Center the block; use yellow on the upper line and a warmer yellow on the lower. Tune letter spacing by eye so the two lines make a single compact silhouette.

### Monochrome miniature wall

**Use:** Collection proof inside the yellow chapter.

**Observed:** Warm off-white and dark ink game illustrations, pixel art and hand-drawn title treatments form tightly edged landscape tiles. The shared palette binds otherwise wildly different art styles.

**Transfer:** Reduce varied original outcomes to a two-tone warm-paper/ink treatment. Give each tile an individual visual identity while preserving the common frame.

### Bright product photography

**Use:** A small gallery after technical detail and inside commerce galleries.

**Observed:** Square or nearly square photos mix close material detail, hands, packaging and overhead arrangements. Backdrops are unapologetically purple, green, blue or natural wood; objects remain crisply lit, not desaturated lifestyle haze.

**Transfer:** Photograph details and real use with clear light and saturated solid grounds. Keep the product recognizable in small thumbnails.

### Application window ensemble

**Use:** Capability demonstrations and developer tool panels.

**Observed:** Several real application windows overlap, with the important editor in front and supporting windows offset behind. Screens remain small enough to read as evidence of a tool rather than a full-page UI clone.

**Transfer:** Use real windows or realistic simplified previews from the new product. Preserve the layered arrangement, visible title bars and clear front-to-back hierarchy.

### Technical edge drawings

**Use:** Peripheral decoration around the specification block.

**Observed:** Fine low-contrast engineering outlines show front and side elevations on charcoal, partially clipped at the outer page edges. Yellow pictograms and white values are far stronger than these drawings.

**Transfer:** Use original product outlines or simplified wireframes as faint perimeter art.

**Build:** Draw several front/side silhouettes in SVG with thin warm-gray strokes at low opacity, no fills. Position one partly outside each edge of the charcoal band; keep the 800px central text area clear.

### Thought cloud

**Use:** A short human motivation quote within the dark chapter.

**Observed:** A slate cloud assembled from overlapping rounded lobes carries bold white copy; two small detached circles rise toward its upper-right side.

**Transfer:** Put one candid question or motivation inside a similarly playful cloud; keep it short enough to read at a glance.

**Build:** Layer 8–10 overlapping slate SVG ellipses into a low 720px-wide cloud silhouette around a 600px text block. Add two detached circular dots above the right half. Keep the text on top at 24.2px/1.3 with comfortable inset space.

### Closing multi-view tableau

**Use:** The marketing farewell before footer identity and links.

**Observed:** Front, back, side and bottom views of the product create a large yellow arrangement against purple. The artwork is much taller than the link area and rewards the end of the scroll.

**Transfer:** Create an original set of complementary views of the product. For a nonphysical service use a coherent arrangement of interface states or outputs, retaining the warm-object/purple-ground contrast.

**Build:** Arrange transparent product views in a horizontal SVG or CSS composition about 1100px wide. Keep a large central face, thinner edge views to the left and bottom, and a broad reverse view to the right. Leave a clear purple interval before the centered maker emblem.

### Icons

**Observed:** Navigation uses compact filled pictograms beside bold labels; technical rows use larger flat yellow symbols. Small tool cards use charming colorful illustrative symbols rather than one uniform outline-icon library.

**Transfer:** Choose simple filled silhouettes that remain legible near 22px. Use larger yellow symbols for factual rows and a few original illustrative icons for resource headings.

## Section recipes

How recurring sections are built.

### First screen: Object-first opening

**Observed:** The Slate object stage fills the first screen behind the 59px Global navigation. Back to front: cool slate, broad diffused white halo, a centered front-facing product roughly 600px wide with warm highlights and a dark screen, then a tilted black-and-white announcement card near its upper-left. The object occupies most of the vertical space below the rail; the 57px bold centered introduction begins at about 820px, so only its first line is visible within 900px. There is no conventional text-led headline-and-button pair above the object. The full introduction, Stacked word sculpture and Glossy promotional capsule continue below the fold.

**Transfer:** Lead with one convincing, memorable object or isolated interface assembly. Keep enough room to read its silhouette before the descriptive sentence enters. Commerce opens instead with a compact yellow product primer and availability signup; browsing opens with a graphic masthead, category strip and artwork; developer resources open with a smaller centered audience heading and colored tool card.

**Avoid:** Do not replace the opening with a split SaaS headline on the left and a framed dashboard on the right, or force the main capsule above the fold.

**Text style:** `opening-introduction` — Roobert 700 · 57px/1.1

### Capability chapter

**Observed:** On Yellow chapter sheet, left-aligned heading and body share an 800px column, separated by 30px. Cutout product art can extend outside that column, and the next heading can begin while a large image still occupies the outer gutter. Other capability chapters place a centered Capability pill followed by an 800px-wide Application window ensemble.

**Transfer:** Explain one concrete distinction at a time, using tactile or visible proof rather than a row of abstract benefits.

**Text style:** `heading` — Roobert 800 · 68.4px/1

### Dense art proof

**Observed:** A heading and two conversational paragraphs lead into Speech toggle and the Miniature collection layout. Monochrome miniature wall tiles use a common warm-paper ground and 1px edge. A simple underlined text action closes the group.

**Transfer:** Show breadth with original examples, outputs or use cases that can genuinely hold up as small posters; retain the shift from leisurely prose to tightly packed art.

### Neutral collection interlude

**Observed:** Pale interlude interrupts the yellow run. A large centered graphic title sits above body copy and a dark Capability pill; brightly illustrated collection cards spread across the lower area beyond the central reading width.

**Transfer:** Use one neutral interlude to show a broader ecosystem without making the whole marketing page a pale-gray card grid.

### Offer sheet

**Observed:** Purple offer sheet carries a 68.4px white heading, an isolated product image and practical purchase explanation, with Yellow purchase pill beneath. A secondary related object gets its own short heading and a wide product demonstration within the same band.

**Transfer:** Present price and included value directly. Keep product imagery physically specific and the action flat yellow rather than adding a pricing-comparison table.

### Technical back-of-package

**Observed:** Charcoal reassurance sheet starts with a large white heading and two groups of Technical row. Muted category labels, flat yellow symbols and bold white values create a compact specification diagram. Technical edge drawings flank the block, and a six-image photographic gallery follows.

**Transfer:** Use real factual specifications or operational details, then bring back human-scale photography so the darker chapter never feels sterile.

### Human reassurance and contact

**Observed:** Within the same dark ground, Thought cloud gives way to a short origin paragraph, newsletter heading, newsletter-lead copy, Email field and right-aligned Email submit. A large help heading and purple Capability pill provide a friendly practical exit.

**Transfer:** Combine a candid motivation, low-pressure signup and genuinely useful support route. Keep the large heading treatment even near the end of the page.

### Object-led farewell

**Observed:** Closing footer starts with Closing multi-view tableau on purple. Centered maker identity follows, then compact link columns in the 800px reading area, with 60px bottom padding. The artwork, not another giant CTA slogan, is the final visual memory.

**Transfer:** End a marketing page with an original product-view arrangement and modest useful links. Utility pages use the smaller pale-gray identity-and-columns variant.

### Utility resource chapter

**Only for:** developer resource pages

**Observed:** A centered resource-heading introduces an 800px grid. Blue tool hero combines short copy and downloads with layered application imagery; white Resource cards follow in full-width and paired formats. A later Mint tool chapter changes the ground and panel colors together. Signup and the compact pale footer close the page.

**Transfer:** Organize resources by reader confidence or intended task. Preserve colored tool panels and small bold capsule links rather than using the marketing heading scale everywhere.

### Commerce product row

**Only for:** commerce pages

**Observed:** A 900px two-column layout pairs a 436px square gallery and 68px thumbnails with bold store-heading, light price, availability pill, concise description, bullet facts and underlined detail links. Major bundles get a white rounded surface; smaller products form a two-column catalog. Shipping reassurance, centered help and a compact pale footer finish the page.

**Transfer:** Keep the item itself and its purchase facts together; reserve the bright full-width yellow treatment for the introductory primer, not every product row.

### Artwork-led browsing

**Only for:** catalog and browsing pages

**Observed:** A centered graphic masthead precedes a horizontally clipped category strip and small filter pills. Illustrated collection banner alternates wide and paired artwork with tight centered captions. Selected groups get the hard offset Printed card stack. A modest white submission capsule precedes the pale identity footer.

**Transfer:** Let original artwork differentiate destinations; use captions as compact title-and-credit lines rather than long card descriptions.

## Page flow

**Storyline:** Object-led promise → tangible distinctions → breadth of possibilities → practical offer → factual reassurance → human contact → memorable object farewell.

### Introduce an unfamiliar product and make its small physical details desirable

1. **Promise** — Large isolated object, descriptive introduction, oversized word artwork and glossy conversion capsule.
2. **Capability chapters** — Yellow chapters combine short bold titles, conversational explanations and cutout demonstrations.
3. **Breadth proof** — Dense monochrome examples and a neutral illustrated collection interlude.
4. **Expansion** — Additional capability demonstrations and a distinct audience-specific color chapter.
5. **Offer** — Purple purchase presentation with yellow pills and related-object imagery.
6. **Reassurance** — Charcoal technical rows, photographic detail, thought cloud and human backstory.
7. **Closing contact** — Newsletter and help precede the purple multi-view object footer.

**Transfer:** Adapt the narrative to the product while preserving the contrast between tactile spectacle, readable chapters and compact practical detail.

### Help someone compare objects and understand purchase conditions

1. **Orientation** — Compact yellow primer introduces the product.
2. **Availability** — White signup panel gives an honest next step.
3. **Purchase detail** — Square galleries, prices, availability controls and factual copy form long product rows and smaller paired listings.
4. **Objection handling** — Shipping and coverage assurances precede a centered help heading and purple actions.
5. **Closing navigation** — Compact pale footer with maker identity and practical columns.

**Transfer:** Use the neutral commerce variant for inventories and purchase tasks; keep the expressive color in the primer, product photography and actions.

### Encourage exploration of a visually diverse collection

1. **Orientation** — Graphic masthead, illustrated categories and small filter capsules.
2. **Discovery** — Wide featured art interspersed with paired smaller destinations.
3. **Collection proof** — Bundle banners use bold art and occasional offset stacked edges.
4. **Contribution** — A modest submission action closes the collection.
5. **Closing navigation** — Pale compact identity footer.

**Transfer:** Give art the space normally given to prose; captions remain compact and aligned to the artwork.

### Make tools approachable for readers with different experience levels

1. **Audience routing** — Small secondary tabs and a centered audience heading.
2. **Primary tool** — Blue download panel and overlapping application windows.
3. **Practical resources** — White documentation and community cards.
4. **Alternative route** — Mint chapter with darker green panels for a more approachable tool.
5. **Cross-cutting help** — Paired resource cards and newsletter signup.
6. **Closing navigation** — Pale compact identity footer.

**Transfer:** Separate routes by task and confidence; use colored tool panels to make resource navigation feel inviting rather than bureaucratic.

## Writing

Warm, candid and delighted by small details. The voice has enough confidence to admit limitations, answer silly questions plainly and let an occasional joke sit beside useful technical information.

**Do not copy:** Do not reuse the product name, wordmarks, proprietary art, specific prices, quantities, performance claims, creator names, educational offers or quoted origin story. Source examples illustrate tone only.

- **Addressing the reader:** Speak to the reader as you; use we for the makers. The product is a tangible companion, not an abstract platform.
- **Rhythm:** Chapter titles are often two or three words with a full stop or a question mark. Explanations alternate short fragments with longer informative sentences; rhetorical questions get immediate plain answers. Exclamation marks are used selectively and playfully.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening description | Say what the object is in everyday language, then give a short human reason it exists. | One descriptive sentence plus a short follow-up. | “It's a new, tiny handheld game system with a bunch of brand-new games. We made [Brand] just for fun.” |
| Chapter title | Use a definite noun, a candid question or a short useful promise. | 2–4 words | “The System.”<br>“Big Screen Optional.”<br>“Your games?” |
| Explanation | Anticipate a real doubt, answer directly and then explain the useful distinction. | A short paragraph of varied sentence lengths. | “Yes, the crank. Is it a gimmick? Nah. Does it charge [Brand]'s battery? Nope. Is it really fun? Yes yes yes.” |
| Primary action | Plain active verb, sometimes a cheerful invitation. | 2–5 words | “Shop Now”<br>“Grab some games!”<br>“Notify Me” |
| Reassurance | Acknowledge that someone may need help and offer a human next step. | One or two short sentences. | “We're here. Head on over and we'll get you sorted.”<br>“Sign up to get [Brand] news. Only the important stuff.” |
| Commerce description | Begin with a few vivid fragments, then state the practical inclusion. | Short lead plus factual details. | “Here it is. Fun. Yellow. Fits in your pocket.” |

**Words and phrasing to use:** tiny; little; fun; surprise; handy; friends; we've got that covered; only the important stuff; plain yes/no answers

**Avoid:** revolutionary platform; unlock unparalleled potential; enterprise-grade synergy; seamless ecosystem; vague superlatives

**Rules:**

- Describe what a detail feels like or does before listing its technical name.
- Let a bold inline phrase carry the key distinction within a readable paragraph.
- Admit real limitations without defensive fine print.
- Give support and availability copy the same friendly attention as the main pitch.
- Use jokes sparingly and keep purchase requirements factual.

## Do's and Don'ts

### Do

- Keep chapter titles at 68.4px/1 and weight 800, with normal tracking.
- Anchor long prose to an 800px reading column while allowing object art to reach the 1100px stage.
- Use 28.5px/1.3 prose and reserve compact 21.4px text for specifications and resource summaries.
- Keep the long yellow chapter sheet uninterrupted across related demonstrations.
- Make miniature artwork dense: three columns, 10px gaps, thin dark edges and nearly square corners.
- Reserve the glossy 81px-tall capsule for the emphatic promotional moment.
- Give the closing purple scene enough room for multiple complementary product views.
- Use 6px form corners and a visible external email label, distinct from rounded action pills.

### Don't

- Do not tighten the main headings into fashion-editorial negative tracking; their default tracking is normal.
- Do not turn every section into a white rounded card; the core marketing canvas is made of full-width color sheets.
- Do not use soft elevation shadows on resource cards; their white-on-gray construction is flat.
- Do not colorize each miniature proof tile differently; keep the warm-paper monochrome wall coherent.
- Do not inflate technical values into giant KPI numerals; they are compact bold 21.4px lists with category icons.
- Do not use the green developer-tool theme as an all-purpose landing-page palette.
- Do not apply the main capsule's glossy bevel to email fields, cards or ordinary text links.
- Do not make the utility footer as tall and theatrical as the marketing farewell; it uses a compact pale identity-and-links treatment. 

## Motion and responsive

### Motion

**Observed:**

- Declared: miniature artwork uses background-position 250ms ease-in-out and backface-visibility 150ms ease-in-out; reverse faces use a 180-degree Y rotation.
- Declared: navigation background-color transitions over 250ms ease-in-out.
- Declared: the glossy capsule has a pressed gradient and inverted inset-shadow state.
- Declared keyframe names include a pulsing object treatment and scrolling collection banner; their full timing and playback behavior are not established.

**Transfer:**

- Use the miniature tile's reverse face for useful title and creator detail rather than gratuitous flipping of all page panels.
- Keep the changing navigation color tied to chapter contrast, so the fixed rail stays visually integrated.

**Unknown:**

- Exact scroll-linked object choreography, animation durations beyond the stated transitions and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared marketing width breakpoints include 620px, 670px and 1100px; utility layouts additionally declare 800px and 860px breakpoints.
- The desktop composition uses distinct 800px reading, 1070px collection and 1100px object widths.

**Transfer:**

- As design guidance, reduce the object stage and stacked word artwork together so the product remains dominant; do not shrink the descriptive sentence into a tiny caption.
- As design guidance, move overflowing cutouts below their associated prose and reduce three-column miniature collections to fewer columns while retaining the tight 10px spacing.
- As design guidance, stack gallery-and-copy commerce rows and wide tool panels before they become cramped.

**Unknown:**

- Exact narrow-screen type sizes, column counts and navigation collapse behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
