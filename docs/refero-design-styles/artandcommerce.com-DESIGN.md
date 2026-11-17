# Art + Commerce — image-led editorial index

## Overview

A white-walled editorial style in which photographs do most of the speaking and typography behaves like a publication's credits. Warm, fine serif titles and prose sit against tiny bold grotesk labels, with black and grey interface furniture around richly varied photographic color. It suits visually led products, creative services and collections with substantial work to show; the viewing experience is expansive while the navigation and supporting information remain compact.

### Essentials

- The opening reads like an exhibition announcement, not a sales funnel: a 596px-wide portrait beside a vertically centered text column, a 56px/1.1 regular serif title with -1px tracking, and 16px/1.3 medium grotesk support.
- The interface is a thin masthead above a vast gallery: a fixed 44px white header with a 1px pale-grey bottom rule, 16px side padding and 10.1px bold uppercase navigation.
- Color belongs to the work, not the chrome: white canvas, black text and grey utility links throughout; saturated red, pink, green or blue can occupy most of a media block but never become decorative page bands.
- The signature spread alternates scale without changing material: square-cornered single images, 542px-wide paired portraits separated by 36px, and near-width films, with 80px or 160px breathing space. For products without campaign imagery, use carefully lit product studies and paired detail views.
- Credits carry two voices: names and announcements use a 20px/1.1 regular serif; contextual credits use a 10px/1.25 bold uppercase grotesk with 0.3px tracking, placed just below the work.
- Actions stay editorial rather than promotional: unboxed text links turn #767676 on hover; the only filled action is a secondary category chip with 8px corners, 5px 16px padding and a pale-grey ground.
- The closing device is an index, not a billboard: four columns of 16px/1.3 serif links, tiny uppercase category headings, 64px column gaps and 160px top space, followed by a low utility line. Recast this as a useful product, resource or capability directory.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, link, action | Primary titles, copy, navigation and credits. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-canvas` | background, surface | Continuous page ground and fixed navigation surfaces. |
| Masthead rule | `#e7e7e7` | `--color-rule` | border | Single thin divider beneath the main navigation. |
| Utility grey | `#767676` | `--color-muted` | text, link, action | Link hover color and secondary navigation text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detail-page category navigation | Category ground | `#f3f3f5` | `--color-chip-surface` | surface | Small category chips only. |
| detail-page category navigation | Category grey | `#6b6b6b` | `--color-chip-ink` | text, action | Category chip labels. |

## Typography

- **Adobe Garamond** — Editorial titles, announcements, long prose and directory links. Old-style serif with fine contrast and a literary, human scale; regular rather than emphatic. If unavailable, use **EB Garamond**. Use 400 for titles and prose; tune wrapping to preserve the airy title lines. Font stack: "Adobe Garamond", "EB Garamond", Georgia, serif.
- **Akzidenz Grotesk** — Masthead links, compact credits, category headings and opening support copy. Workmanlike grotesk; its very small bold capitals act as publication furniture against the serif. If unavailable, use **Libre Franklin**. Use 500 for opening copy and 700 for compact labels. Font stack: "Akzidenz Grotesk", "Libre Franklin", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Adobe Garamond | 400 | 56px | 1.1 | -0.0179em | Main editorial announcement title, generally wrapping into two lines. |
| announcement | Adobe Garamond | 400 | 20px | 1.1 | normal | Names beneath featured work, short announcements and object titles. |
| opening-support | Akzidenz Grotesk | 500 | 16px | 1.3 | normal | Opening preheading, short supporting paragraphs and dates. |
| body | Adobe Garamond | 400 | 16px | 1.3 | normal | Prose, text links and the closing directory. |
| navigation | Akzidenz Grotesk | 700 | 10.1px | 1 | 0.027em, uppercase | Compact masthead links and section-navigation tabs. |
| credit | Akzidenz Grotesk | 700 | 10px | 1.25 | 0.03em, uppercase | Project context beneath media and directory group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| portfolio and product-detail pages | detail-title | Adobe Garamond | 400 | 40px | 1.1 | normal | Centered title beneath a large lead image. |
| catalogue and informational pages | section-label | Akzidenz Grotesk | 700 | 18px | 1 | normal, uppercase | Left-edge category labels for grids and text chapters. |
| detail-page category navigation | category-link | Akzidenz Grotesk | 400 | 14px | 1.3 | normal | Labels inside soft category chips. |
| interior pages | breadcrumb | Akzidenz Grotesk | 400 | 11.3px | 1.3 | normal | Muted location trail below the main masthead. |
| catalogue grids | tile-caption | Akzidenz Grotesk | 700 | 11px | 1.25 | 0.044em, uppercase | Centered clickable captions beneath archive thumbnails. |
| portfolio and product-detail pages | detail-category | Akzidenz Grotesk | 700 | 10px | 1.25 | 0.048em, uppercase | Small centered descriptor beneath a detail title. |

**Notes:**

- Contrast comes from serif versus grotesk and very different sizes, not from a heavy display face. Only the 56px title tightens tracking; ordinary serif prose retains normal spacing.
- Keep the two caption systems distinct: editorial features use serif names with compact grotesk context, while catalogue thumbnails use centered bold uppercase labels.
- Long prose can use italic serif names of publications and bold serif subsection leads; neither treatment changes the 16px/1.3 body rhythm.

## Layout

**Density:** Airy around media and major chapters, compact in the persistent masthead and index-like supporting information.

### Spacing

**Spacing system:**

- **step** 8px — Declared spacing family: 8px, 16px, 24px, 32px, 48px, 64px, 80px and 160px.

| Value | Use |
| --- | --- |
| 8px | Breadcrumb separators. |
| 12px | Space below directory list items. |
| 16px | Navigation side padding and narrow page gutters. |
| 24px | Opening text-stack gap. |
| 32px | Archive grid gaps, prose paragraph separation and image-to-detail-title separation. |
| 36px | Paired-image gutter. |
| 48px | First catalogue section and informational opening inset. |
| 64px | Directory column gap and bottom space. |
| 80px | Opening inset and catalogue chapter top space. |
| 160px | Major media separation, inset spreads, biographies and directory top space. |

### Containers and grids

- **opening split**: 2 columns · gap 80px · side padding 80px. Portrait image to the left; a narrower text stack to the right, centered vertically against the image. Opening media is 596px wide and the text measure is 524px at desktop.
- **inset diptych**: 2 columns · gap 36px · side padding 160px. Two 542px-wide images within a 1120px span; bottoms align even where proportions differ.
- **near-width media**: side padding 12px. Wide film and landscape work may approach the viewport edges; preserve their intended proportions rather than making every section the same width.
- **closing directory**: max width 1306px · 4 columns · gap 64px · side padding 16px. Four 271px columns within a centered directory; shorter category lists stack within each column.
- **reading column** (only for biographies and informational pages): max width 873px · side padding 16px. Centered prose column with a section label left outside it. Biography variants add 16px internal side padding for an 841px text measure.
- **catalogue grid** (only for compact catalogue pages): 5 columns · gap 32px · side padding 16px. 256px thumbnail stages; portrait and landscape images keep their ratios and share a bottom alignment.
- **wide catalogue grid** (only for extended catalogue pages): 4 columns · gap 32px · side padding 16px. 328px image stages for a larger editorial archive and mixed film collection.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media | 0px |
| detail-page category navigation | category chip | 8px |

## Surfaces and depth

### Surfaces

#### Gallery canvas · level 0

**Use:** All main page content.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** An uninterrupted white ground; images and text are not enclosed in panels.

**Transfer:** Let white space separate stories rather than assigning each story a colored box.

#### Masthead strip · level 1

**Use:** Persistent top navigation.

**CSS:** `background: #ffffff; border-bottom: 1px solid #e7e7e7`

**Observed:** A thin opaque strip remains above the work rather than blending over photographs.

**Transfer:** Keep this as the one consistent rule across visually diverse media.

#### Soft category surface · level 0

**Only for:** detail-page category navigation

**Use:** Secondary category links after long prose.

**CSS:** `background: #f3f3f5; border-radius: 8px; box-shadow: none`

**Observed:** Small pale-grey islands on white, not a repeating card material.

**Transfer:** Reserve this treatment for taxonomy or back-to-category navigation.

## Components

### Fixed masthead

**Use:** Global identity and destination navigation.

**CSS:** `position: fixed; top: 0px; height: 44px; width: 100%; display: flex; align-items: center; justify-content: space-between; padding: 12px 16px; box-sizing: border-box; background: #ffffff; border-bottom: 1px solid #e7e7e7; z-index: 99`

**Text style:** `navigation` — Akzidenz Grotesk 700 · 10.1px/1 · tracking 0.027em · uppercase

**Observed:** Compact black wordmark on the left, a right-aligned horizontal destination list and a small search icon at the far end. Destination links are spaced by 23px.

**Transfer:** Use a restrained text identity at the left and a short destination list rather than a central oversized logo.

### Masthead link

**Use:** Primary destinations without button styling.

**CSS:** `color: #000000; text-decoration: none; text-transform: uppercase`

**Text style:** `navigation` — Akzidenz Grotesk 700 · 10.1px/1 · tracking 0.027em · uppercase

**Observed:** All links have equal emphasis; there is no filled conversion button.

**States:** Declared: hover color #767676; focus-visible unknown.

### Editorial feature link

**Use:** A large linked image-and-copy announcement.

**CSS:** `display: block; padding: 80px 0px; color: #000000; text-decoration: none`

**Text style:** `display` — Adobe Garamond 400 · 56px/1.1 · tracking -0.0179em

**Observed:** The entire opening feature is linked; its portrait and vertically centered copy form one destination. Short sans support paragraphs sit beneath the serif title, with no separate CTA capsule.

**Transfer:** Link the feature as one editorial destination, with supporting copy explaining the subject rather than selling the click.

### Credit pair

**Use:** Editorial information immediately below large media.

**CSS:** `display: grid; padding: 13px 16px 16px; gap: 16px; align-items: end`

**Text style:** `announcement` — Adobe Garamond 400 · 20px/1.1

**Observed:** A serif name or sentence occupies the left; an uppercase Credit label often sits at the right. On paired portraits, the context can sit above the serif name at the left.

**Transfer:** Use a maker, product or project name paired with a concise edition, date or application.

### Directory link

**Use:** Closing navigation and direct inline text actions.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `body` — Adobe Garamond 400 · 16px/1.3

**Observed:** Unboxed serif links appear as a vertical list. Each directory list item has 12px space below it; compact uppercase category labels distinguish groups.

**States:** Declared: hover color #767676; focus-visible unknown.

### Closing directory

**Use:** Substantial ending shared by all page types.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; padding: 160px 0px 64px`

**Text style:** `body` — Adobe Garamond 400 · 16px/1.3

**Observed:** Four columns group many links under small uppercase headings, with variable column lengths. A final 44px utility row spans the page, social icon left and compact legal destinations right. There is no closing promotional panel.

**Transfer:** Build a meaningful navigable index of offerings or resources; preserve category grouping even when the list is shorter.

### Archive tile

**Only for:** catalogue grids

**Use:** Linked visual proof grouped by category.

**CSS:** `color: #000000; text-align: center; text-decoration: none`

**Text style:** `tile-caption` — Akzidenz Grotesk 700 · 11px/1.25 · tracking 0.044em · uppercase

**Observed:** Unframed media sits inside a square staging area, centered horizontally and aligned to the bottom; a caption begins 9px below. Narrow images are not stretched to fill the tile. Four-column stages are 328px; compact five-column stages are 256px.

**States:** Declared: hover color #767676 on the link and its linked ancestor; focus-visible unknown.

**Transfer:** Present a collection of real examples, respecting each asset's native aspect ratio.

### Category chip

**Only for:** detail-page category navigation

**Use:** Return from a biography or detail to a broader category.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 5px 16px; height: 34px; box-sizing: border-box; border-radius: 8px; background: #f3f3f5; color: #6b6b6b; text-decoration: none`

**Text style:** `category-link` — Akzidenz Grotesk 400 · 14px/1.3

**Observed:** One or two understated chips appear after the contact block, separated by 16px; they are not the main conversion action.

**States:** Declared: hover color var(--darkGrey) and text-decoration none; focus-visible unknown.

### Interior navigation strip

**Only for:** interior pages

**Use:** Location trail and chapter navigation beneath the masthead.

**CSS:** `position: fixed; top: 44px; height: 34px; width: 100%; box-sizing: border-box; padding: 0px 16px; display: flex; align-items: center; justify-content: space-between; background: #ffffff; z-index: 99`

**Text style:** `breadcrumb` — Akzidenz Grotesk 400 · 11.3px/1.3

**Observed:** A grey breadcrumb trail with 8px separators sits left. Tiny bold uppercase chapter links sit right, using the Navigation recipe; current text is black and other tabs grey.

**Transfer:** Keep wayfinding separate from the media, using destination names instead of decorative badges.

## Imagery and graphics

### Editorial photographic spread

**Use:** The dominant storytelling material, including the opening and recurring linked features.

**Observed:** Fashion portraits, still life, architecture and landscapes appear as finished photographic works with square edges. The opening pairs a strongly art-directed portrait poster with plain white copy space. Later works range from washed daylight and natural greens to saturated crimson, deep blue and high-contrast monochrome. Large images commonly reach 797px in height, greatly outweighing their captions.

**Transfer:** Commission or select polished product photography with a clear point of view. Pair a full object study with a close detail or a contextual scene; retain the light and palette of each work instead of applying one site-wide tint. Without campaign assets, the minimum is a carefully lit, high-resolution object study on a controlled neutral ground.

### Paired portrait spread

**Use:** Signature editorial contrast between single large images and two-image chapters.

**Observed:** Two tall images sit side by side with white between them, not within cards. One spread contrasts a saturated red mirrored scene with a blurred, glittering black-and-white portrait; another pairs publication covers. The pair is about 1120px wide, with a 36px gutter.

**Transfer:** Use two views that share a story but vary in distance, lighting or color. Their framing must be deliberate; keep square edges and align the image bottoms.

### Film as exhibited work

**Use:** Landscape and portrait media features between still photographs.

**Observed:** Films range from intimate pale portraits to outdoor campaign scenes and floating publication objects. They sit directly on white with captions below, at near-width landscape scale or narrower centered portrait scale. Titles within the films are part of the work, not page UI.

**Transfer:** Use concise footage of the product, its making or its environment. Provide a strong still poster with the same framing whenever video is unavailable.

### Object and publication shelf

**Only for:** catalogue and detail pages

**Use:** Book, project and portfolio collections.

**Observed:** Covers and rectangular images are displayed frontally, at native ratios within a common square stage, bottom-aligned. White backing remains visible around narrower objects; some images include their own soft studio background. Book collections can use 20px serif titles and a second tiny uppercase metadata line rather than the normal uppercase tile title.

**Transfer:** Photograph packaging, editions or product outputs frontally; preserve the full object. Keep any shadow or textured ground inside the image, not on the HTML tile.

### Icons

**Observed:** Sparse functional graphics: a black 13px search icon at the far right of the masthead, small grey 15px grid/view controls on catalogue headings, and a roughly 24px social mark at the lower left. No decorative feature-icon vocabulary.

**Transfer:** Choose plain compact search and view controls with minimal visual weight. Let photographs, not icon badges, identify capabilities.

## Section recipes

How recurring sections are built.

### First screen: Exhibition announcement opening

**Observed:** Gallery canvas behind a Fixed masthead; the first feature begins 80px below it. A 596px by 794px portrait sits at the left with an 80px outer inset. The copy starts well into the right half and occupies a 524px measure, vertically centered against the portrait: 16px medium sans preheading, two-line 56px regular serif title, then short sans support and a date. Text-stack gaps are 24px. The image carries its own vivid poster lettering; page copy is black on white. Within the first 900px the masthead, nearly all the portrait, full title and support are visible; the lower edge of the portrait and the following story fall below. Editorial feature link makes the whole composition actionable; there is no separate button row.

**Transfer:** Stage a hero product photograph or composed product study beside a specific editorial title and factual support. Keep a tall image and two-line serif title as the primary contrast even without a poster. Detail pages instead lead with a centered landscape image and a 40px title underneath; informational pages begin with a left-edge chapter label and the Reading column.

**Avoid:** Do not replace the split with a centered slogan over a full-bleed image, a colored hero panel or a pair of oversized conversion buttons.

**Text style:** `display` — Adobe Garamond 400 · 56px/1.1 · tracking -0.0179em

### Single-work chapter

**Observed:** A large centered image or film sits directly on Gallery canvas. Width changes with the work: roughly 638px for a portrait, 797px for a square and up to 1417px for a wide film. Credit pair follows immediately; major chapters use 160px top space while some adjoining works meet with only caption space between.

**Transfer:** Let media ratio determine the width. Alternate intimate and expansive views to create pacing without changing the page background.

**Text style:** `announcement` — Adobe Garamond 400 · 20px/1.1

### Two-image editorial chapter

**Observed:** Paired portrait spread occupies the Inset diptych layout. A shared Credit pair sits beneath the images, and 160px surrounding space sets the pair apart from near-width films.

**Transfer:** Use a contextual view and detail, two related artifacts or color and monochrome versions as an editorial comparison rather than two feature cards.

### Directory ending

**Observed:** Closing directory starts after 160px of white space within a 1306px container. Four columns carry serif links and compact uppercase labels; shorter groups stack within columns. The last line is a sparse utility strip with a social icon to the left. The same white ground continues to the page edge.

**Transfer:** End with a genuinely useful taxonomy of destinations. Preserve the scale contrast between the substantial index and the tiny utility line rather than adding a large closing slogan.

**Text style:** `body` — Adobe Garamond 400 · 16px/1.3

### Catalogue chapter

**Only for:** catalogue pages

**Observed:** An 18px uppercase section label sits against the 16px left page gutter; compact view controls sit at the opposite edge. After 32px, Archive tiles form five 256px stages or four 328px stages with 32px gaps. Later chapters begin after 80px; the first uses 48px. Portraits and landscapes share bottom alignment rather than a forced uniform crop.

**Transfer:** Divide a broad product range or proof library into named categories. Keep density in the thumbnails, not in container decoration.

**Text style:** `section-label` — Akzidenz Grotesk 700 · 18px/1 · uppercase

### Editorial text and contact chapter

**Only for:** biographies and informational pages

**Observed:** A left-edge section label accompanies a centered Reading column. Prose uses 16px/1.3 serif and 32px paragraph separation. Biographies have 160px top and bottom space, then a plain social link, contact details and Category chips. Informational openings use 48px top space; bold serif subsection labels introduce stacked descriptions and addresses. Dense supporting lists retain the same body recipe.

**Transfer:** Use this for origin, method, specifications or practical contact information. A left label and centered prose can carry serious detail without turning it into cards.

**Text style:** `body` — Adobe Garamond 400 · 16px/1.3

### Object shelf variant

**Only for:** object collections and publications

**Observed:** A catalogue heading introduces a five-column row of bottom-aligned covers. Titles below use Announcement rather than Tile-caption; tiny uppercase publisher/date metadata can follow. A single exhibition object uses the same small stage and leaves the remainder of its row open.

**Transfer:** Use for editions, downloadable outputs or physical deliverables. A short collection need not be padded with invented items.

**Text style:** `announcement` — Adobe Garamond 400 · 20px/1.1

## Page flow

**Storyline:** editorial introduction → exhibited work → grouped breadth → contextual depth and direct contact → navigable index

### A visual marketing landing page that establishes taste by showing work before explaining it

1. **Editorial introduction** — A split announcement pairs a tall image and regular serif title with concise factual support.
2. **Demonstration** — Large stills and films alternate between broad landscape stages, centered objects and paired portraits, each with compact credits.
3. **Breadth** — A four-column row gathers smaller examples with names and context.
4. **Closing navigation** — A substantial grouped directory ends in a thin utility row.

**Transfer:** Lead with one current, specific product story, show varied evidence at varied scales and let an index carry onward navigation.

### A categorized detail portfolio that makes one body of work easy to scan

1. **Identity and proof** — A large landscape image precedes a centered serif name and tiny category.
2. **Capability chapters** — Five-column categories collect recent work, environments, journeys, commissioned examples, publications and films.
3. **Context and contact** — Serif biography prose leads into social and contact links and a category chip.
4. **Closing navigation** — The shared directory provides the full breadth of destinations.

**Transfer:** Use categories meaningful to the new product, then explain context only after the visual proof.

### An extended multimedia portfolio with editorial and object variants

1. **Identity and proof** — A wide paired campaign image introduces a centered name.
2. **Browse paths** — A short five-column row offers different routes into the collection.
3. **Depth of proof** — A long four-column archive is followed by mixed-ratio films.
4. **Tangible outcomes** — A five-object shelf and a single exhibition object provide a distinct slower-paced proof format.
5. **Context and contact** — A biography, practical contact block and two category chips precede the shared directory.

**Transfer:** For a large collection, vary the type of proof while retaining the same unframed staging and caption discipline.

### An information page for organizational explanation and practical next steps

1. **Explanation** — A left uppercase label accompanies central prose and bold inline division names.
2. **Practical information** — Stacked location and contact details continue in the same reading column.
3. **Detailed opportunity** — Text introductions, bold subsection leads and compact bullet lists describe roles and requirements.
4. **Direct action** — An inline email instruction supplies the application route without a form or promotional button.
5. **Closing navigation** — The same four-column directory closes the information-heavy page.

**Transfer:** Apply the text-led variant to company, service, support or specification pages; preserve the distinction between marginal chapter labels and central prose.

## Writing

Editorial, factual and culturally assured. Confidence is carried by named work, specific context and restrained descriptions rather than conversion language.

**Do not copy:** Do not reuse the brand's wordmark, artist names, campaign artwork, publication covers, client relationships, addresses, dates, representation claims or company history as assets or claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly third-person and impersonal. The organization names itself in announcements; reader address is reserved for practical instructions and contact routes.
- **Rhythm:** Titles are names or concise noun phrases, not promises. Captions are compressed credits; support is one or two factual sentences, while biographies and practical information allow longer paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | Name the subject, then its category or role. | 2–6 words | “Rafael Pavarotti, Photographer” |
| Announcement | State a concrete development in one composed sentence. | One sentence | “[Brand] is pleased to announce representation of Shayne Laverdière.” |
| Credit | Publication or application, followed by issue, season or date. | Short metadata phrase | “W Magazine, Volume 4: The Fashion Issue, 2026” |
| Section label | Plain categorical noun or brief noun phrase. | 1–4 words | “New Work”<br>“Interiors, Architecture & Design” |
| Navigation action | Name the destination directly instead of persuading the reader. | 1–3 words | “About”<br>“Photographers” |

**Words and phrasing to use:** new work; available; edition; series; contact; represents; published; exhibition

**Avoid:** revolutionary; supercharge; unlock your potential; game-changing; don't miss out; best-in-class

**Rules:**

- Let the featured work establish desirability; support copy supplies verifiable context.
- Use dates, editions and descriptive categories where relevant instead of generic benefit slogans.
- Keep action wording destination-led; use direct contact language for practical tasks.
- Use publication-style capitalization in prose and let CSS create uppercase utility labels.

## Do's and Don'ts

### Do

- Set the opening serif at 56px/1.1, weight 400 and -1px tracking.
- Preserve the 44px masthead and its 1px #e7e7e7 divider.
- Give major media transitions 160px space while leaving captions close to their images.
- Keep 36px between paired portraits and 32px between catalogue stages.
- Use 20px serif names with 10px uppercase contextual credits for editorial features.
- Allow saturated photographic color against an otherwise white-and-black interface.
- End with four grouped columns of 16px serif links rather than a conversion panel.
- Keep catalogue images bottom-aligned within 256px or 328px square stages.

### Don't

- Do not substitute a bold geometric sans for the regular serif display.
- Do not give media rounded corners, drop shadows or raised-card framing.
- Do not turn the neutral canvas into a succession of tinted feature bands.
- Do not promote the 8px-radius category chip into a large pill-shaped hero CTA.
- Do not force mixed portrait and landscape thumbnails into identical edge-to-edge crops.
- Do not enlarge tiny uppercase masthead links to the same scale as body copy.
- Do not make every media chapter the same width; that erases the publication-like pacing.
- Do not introduce colorful feature-icon badges into the sparse functional icon system.

## Motion and responsive

### Motion

**Observed:**

- Text links declare a hover change to #767676; category chips declare a dark-grey hover with no underline.
- No action or surface transitions or animations are established. The masthead and interior wayfinding remain fixed while content scrolls.

**Transfer:**

- Use immediate restrained text-color feedback rather than animated button transformations. Preserve fixed white navigation above the gallery.

**Unknown:**

- Film playback controls, autoplay behavior, scroll animation timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The desktop system uses flexible image widths, wrapping catalogue groups and a wrapping closing directory.
- Width-rule boundaries include 769px, 1024px and 1280px; their complete layout behavior is not established.

**Transfer:**

- On narrow screens, stack the opening image before its copy, keeping their editorial relationship and natural media ratio.
- Reduce the catalogue column count while retaining bottom-aligned image stages and captions; stack directory groups without losing the uppercase category labels.
- Keep the identity visible and provide a compact navigation alternative rather than squeezing the desktop destination row.

**Unknown:**

- Mobile navigation, exact breakpoint-to-layout mapping and smaller-screen typography sizes are not established; the narrow-screen adaptations are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
