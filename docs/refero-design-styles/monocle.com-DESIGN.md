# Monocle — worldly print intelligence

## Overview

A cultivated, information-rich editorial style with the confidence of a well-made magazine. White paper, black rules and bookish serif typography carry most of the page, with yellow signals, occasional cream panels and a concentrated burst of sky blue. Documentary photography, handsome objects and personable line illustration make it suitable for products with a rich human context, a considered catalogue or stories worth reading.

### Essentials

- A publication-like entrance rather than a billboard headline: a centered wide wordmark in a 154px masthead, small illustrated side notes, a 64px utility bar and a 46px category strip precede the content.
- Headlines have the authority of book typography, not advertising display: Plantin regular at 32px/1.2 for the lead, 20px/1.25 for cards and 28px/1.25 uppercase for ruled section headings.
- The page is assembled like columns on paper: a 1296px centered frame, 32px gutters, 300px four-up cards and 4px section rules; thin vertical dividers keep adjacent stories distinct.
- Actions look like printed labels: rectangular yellow buttons, 44px high with 16px side padding and 13px bold uppercase Helvetica Neue; the utility-bar version is 40px high.
- White and black do the structural work; yellow #ffc500 is concentrated in actions and 48–50px media badges, while cream panels and blue #64d5ff illustrated cards occupy discrete modules rather than tinting the whole page.
- Images are edited as seriously as text: sharp-edged 4:3 documentary frames, 3:4 object photographs and flat illustrated portraits. Include a human line-art device against pale cream; a simple original drawing of the product in use is the fallback.
- The closing signature is a black directory, not a giant slogan: a 425px desktop footer with a brand-and-action column, five compact link columns, gray links and a fine closing rule. A pale illustrated invitation gives long landing pages a warmer conversion moment.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal yellow | `#ffc500` | `--color-signal` | action, accent, surface | Primary actions, active pagination and circular media controls; also on-air status text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, text, border | Default canvas and reversed text or rules on dark surfaces. |
| Editorial cream | `#fdfcf3` | `--color-cream` | background | Contained long-form invitation or programme panels. |
| Invitation paper | `#fdfbe4` | `--color-invitation` | surface | Warm illustrated conversion panel. |
| Pale rule | `#d9d9d9` | `--color-rule` | border, text | Fine footer separator and reversed secondary metadata. |
| Directory gray | `#b3b3b3` | `--color-footer-link` | text, link | Footer links and copyright against black. |
| Editorial gray | `#6e6e6e` | `--color-muted` | text, border | Metadata, prices, secondary descriptions and understated outlines. |
| Broadcast charcoal | `#2a2929` | `--color-charcoal` | surface, background | Compact media sidebar; match the near-black charcoal appearance of full-width audio shelves. |
| Black ink | `#000000` | `--color-ink` | text, background, border | Primary text, structural rules, footer and inset media player. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| illustrated collections | Guide blue | `#64d5ff` | `--color-guide-blue` | surface | A concentrated row of illustrated guide cards. |

## Typography

- **Plantin** — Editorial headlines, paragraphs, categories, prices and navigation. Bookish old-style serif with sturdy small text, a friendly fullness and restrained contrast. If unavailable, use **Libre Baskerville**. Use regular weight; check wrapping because the substitute is wider. Font stack: "Plantin", "Libre Baskerville", "Book Antiqua", Georgia, "Times New Roman", serif.
- **Helvetica Neue** — Utility navigation, actions, directory links and selected collection titles. Neutral compact neo-grotesk, regular for secondary information and bold for commands. If unavailable, use **Arial**. Use 400 and 700 without added tracking except in utility navigation. Font stack: "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| lead | Plantin | 400 | 32px | 1.2 | normal | Lead editorial promise; sentence case, several lines within the wider column. |
| invitation-heading | Plantin | 400 | 32px | 1 | normal | Compact two-line question in an illustrated conversion panel. |
| section-heading | Plantin | 400 | 28px | 1.25 | normal, uppercase | Ruled collection headings; reverse to white on a dark shelf. |
| feature-title | Plantin | 400 | 24px | 1.25 | normal | Horizontal editorial list titles and programme entries. |
| card-title | Plantin | 400 | 20px | 1.25 | normal | Story titles, product names and compact collection labels. |
| body | Plantin | 400 | 18px | 1.444 | normal | Lead support and descriptive paragraphs in editorial grids. |
| category-navigation | Plantin | 400 | 16px | 1.5 | 0.01em, uppercase | Centered category navigation. |
| masthead-note | Plantin | 400 | 16px | 1.375 | normal | Two-line contextual note beside the wordmark. |
| directory-heading | Helvetica Neue | 700 | 16px | 1.5 | normal, uppercase | Footer column headings. |
| directory-link | Helvetica Neue | 400 | 16px | 1 | normal | Footer navigation links. |
| collection-action | Helvetica Neue | 700 | 14px | 1.285 | normal, uppercase | Right-aligned see-all links in section headers. |
| metadata | Plantin | 400 | 13px | 1.384 | normal, uppercase | Category, edition, reading time and medium labels; black for categories, gray for subordinate details. |
| action | Helvetica Neue | 700 | 13px | 1 | normal, uppercase | Yellow and outlined button labels. |
| utility-navigation | Helvetica Neue | 700 | 13px | 1.125 | 0.01em, uppercase | Small utility-bar links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company narratives | page-title | Plantin | 400 | 40px | 1.083 | normal | Plain sentence-case page heading above narrative media. |
| archives and category pages | archive-title | Plantin | 400 | 24px | 1.125 | normal, uppercase | White title inside a narrow black archive bar. |
| archives and category pages | pagination-number | Helvetica Neue | 700 | 24px | 1.375 | normal | Centered bold page numbers. |
| illustrated collections | illustrated-card-title | Helvetica Neue | 700 | 24px | 1.25 | normal | Bold place or collection name above square artwork. |
| company narratives | reading-body | Plantin | 400 | 20px | 1.444 | normal | Long-form introductory prose and closing editorial statements. |
| catalogue shelves | price | Plantin | 400 | 18px | 1.3 | normal | Gray price below product name. |

**Notes:**

- Keep serif headlines regular, with normal tracking; hierarchy comes from scale, placement and rules rather than weight.
- Use uppercase for categories and shelf headings, but sentence case for the actual stories and products.
- The masthead is a wordmark graphic, much wider and taller than the editorial type scale. Reproduce that identity-led proportion with original lettering rather than enlarging a content headline.
- In prose, reserve italics for publication or work titles; keep paragraph text upright.

## Layout

**Density:** Compact editorial density within broad outer margins: many small text groups and aligned pictures, separated by firm rules rather than expansive empty sections.

### Spacing

**Spacing system:**

- **grid** 8px — Main layout rhythm; 16px, 24px and 32px are its principal multiples. Use 4px for tight metadata and 12px for ruled-header padding.

| Value | Use |
| --- | --- |
| 4px | Metadata and product-caption micro-gaps. |
| 8px | Category-to-title and title-to-description grouping. |
| 12px | Vertical padding inside ruled section headings; pagination gaps. |
| 16px | Card inner padding, action side padding and image-to-copy separation. |
| 24px | Three-column grid gutters and footer column gaps. |
| 32px | Main four-column gutters and spacing between collections or narrative blocks. |
| 40px | Footer padding and archive-content separation. |
| 80px | Horizontal list gap and side padding of the illustrated invitation. |

### Containers and grids

- **editorial-container**: max width 1296px · side padding 20px. Centered desktop content frame; at a 1440px viewport its edges sit 72px from the window. Side padding is a minimum, not an additional inset at that width.
- **opening-grid**: 12 columns · gap 32px. Lead occupies six tracks, secondary story stack three and media sidebar three: rendered widths 632px, 300px and 300px.
- **four-up-shelf**: 4 columns · gap 32px. Four 300px cards aligned across the content frame.
- **three-chapters**: 3 columns · gap 24px. Three equal 416px editorial chapters, each with its own ruled heading.
- **reading-column** (only for company narratives and programme panels): max width 800px · gap 32px. Centered prose and paired photographs within the wider frame.
- **portrait-pair** (only for company narratives): max width 800px · 2 columns · gap 24px. Two equal 388px documentary photographs.
- **archive-list** (only for category archives): max width 932px · gap 32px. Horizontal story rows alongside a narrower promotional rail; each row pairs 552px text and 300px media with an 80px gap.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons-and-editorial-images | 0px |
| special-panels | 8px |
| media-badges-and-current-page | 50% |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default page and ordinary card background.

**CSS:** `background: #ffffff; color: #000000; box-shadow: none`

**Observed:** Ordinary stories sit directly on the page, without a separate card fill.

**Transfer:** Separate editorial groups with rules and alignment, not elevation.

#### Broadcast panel · level 1

**Use:** Compact media sidebar and dark audio shelf.

**CSS:** `background: #2a2929; color: #ffffff; border-radius: 8px; padding: 16px`

**Observed:** Sidebar has softened corners and a black inset live module; full-width shelves are flat-edged with white rules.

**Transfer:** Use a contained dark module for an ongoing service or a full-bleed dark shelf for media.

#### Cream programme · level 0

**Use:** Contained invitation or programme listing.

**CSS:** `background: #fdfcf3; padding: 32px`

**Observed:** A narrow centered text-and-picture list sits inside a broad pale panel.

**Transfer:** Create a slower editorial interlude with useful detail rather than a conventional promotional banner.

#### Illustrated invitation · level 1

**Use:** Warm conversion moment on long landing pages.

**CSS:** `background: #fdfbe4; border-radius: 8px; padding: 10px 80px; display: grid; grid-template-columns: 1fr 1fr; gap: 32px`

**Observed:** Illustration fills the left half, two-line question and a short paragraph are vertically centered on the right.

**Transfer:** Pair original human line art with a specific reason to stay connected.

#### Black directory · level 0

**Use:** Page ending.

**CSS:** `background: #000000; color: #ffffff; padding: 40px 20px`

**Observed:** A low, dense directory closes every page rather than a separate oversized conversion scene.

**Transfer:** Keep useful destinations and compact actions together in this closing band.

## Components

### Primary button

**Use:** Subscription or main conversion action.

**CSS:** `background: #ffc500; color: #000000; height: 44px; padding: 0px 16px; border: 1px solid transparent; border-radius: 0px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Helvetica Neue 700 · 13px/1 · uppercase

**Observed:** Label is centered; utility navigation uses a shorter 40px variant. A small play triangle precedes the live-audio label.

**States:** Declared: hover underline, 1px decoration thickness and 1px underline offset; focus-visible 2px solid black outline with 2px offset.

### Inverse outline button

**Use:** Secondary actions within dark panels and footer.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid #ffffff; border-radius: 0px; height: 44px; padding: 0px 16px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Helvetica Neue 700 · 13px/1 · uppercase

**Observed:** Sits beside a yellow primary button in the footer, or spans the compact media panel.

**States:** Declared: hover underline; focus-visible 2px solid black outline with 2px offset.

### Category navigation

**Use:** Publication-like navigation below the masthead.

**CSS:** `background: #ffffff; display: flex; justify-content: center; gap: 24px; padding: 10px 0px; color: #000000`

**Text style:** `category-navigation` — Plantin 400 · 16px/1.5 · tracking 0.01em · uppercase

**Observed:** Single centered row bounded by fine horizontal rules, with vertical separators between labels.

**States:** Declared: hover underline with 1px thickness and 1px offset; focus-visible currentcolor solid 2px outline with 2px offset.

### Utility links

**Use:** Top navigation beside the menu icon.

**CSS:** `display: flex; gap: 8px; align-items: center; color: #000000`

**Text style:** `utility-navigation` — Helvetica Neue 700 · 13px/1.125 · tracking 0.01em · uppercase

**Observed:** Small bold labels sit left; search, login, yellow action and shopping controls sit right. After scrolling, a compact centered wordmark appears in the utility bar.

**States:** Declared: hover underline with 1px thickness and 1px offset; focus-visible currentcolor solid 2px outline with 2px offset.

### Ruled section header

**Use:** Introduce a collection and its see-all link.

**CSS:** `border-top: 4px solid #000000; padding: 12px 0px; display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap`

**Text style:** `section-heading` — Plantin 400 · 28px/1.25 · uppercase

**Observed:** Serif heading left, compact bold sans collection action right. White rule and white text reverse the same structure on dark shelves.

### Collection link

**Use:** All-items action aligned with a shelf heading.

**CSS:** `height: 44px; display: flex; align-items: center; justify-content: center; color: #000000`

**Text style:** `collection-action` — Helvetica Neue 700 · 14px/1.285 · uppercase

**Observed:** No filled background; white variant belongs on the broadcast shelf.

**States:** Declared: hover underline with 1px thickness and 1px offset; focus-visible currentcolor solid 2px outline with 2px offset.

### Editorial story card

**Use:** Reusable story, capability or proof unit.

**CSS:** `display: flex; flex-direction: column; gap: 16px; position: relative; color: #000000`

**Text style:** `card-title` — Plantin 400 · 20px/1.25

**Observed:** Sharp-edged image first, then category and title with an 8px internal gap, optional paragraph, and muted icon-plus-duration metadata at the bottom. Thin vertical separators sit in the gutters between adjacent cards.

**States:** Declared: title hover underline with 1px thickness and 0.187rem offset.

**Transfer:** Use real benefits or customer stories with specific descriptive titles, not one-word feature tiles.

### Directory column

**Use:** Footer destination groups.

**CSS:** `display: flex; flex-direction: column; gap: 16px; color: #b3b3b3`

**Text style:** `directory-link` — Helvetica Neue 400 · 16px/1

**Observed:** White uppercase bold heading above regular gray links with 8px list gaps. Five destination groups sit beside the wider brand column; the shared frame ends in a pale hairline.

**States:** Declared: link hover underline with 1px thickness and 1px offset; focus-visible currentcolor solid 2px outline with 2px offset.

### Illustrated guide card

**Only for:** illustrated collections

**Use:** Colorful collectible guide or topic series.

**CSS:** `background: #64d5ff; border-radius: 8px; padding: 16px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `illustrated-card-title` — Helvetica Neue 700 · 24px/1.25

**Observed:** Small uppercase serif series label over a black hairline; bold sans title; square artwork below. Four cards form a concentrated blue row.

**States:** Declared: hover underline; focus-visible underline.

**Transfer:** Make a consistently illustrated series of use cases, places or product families.

### Pagination

**Only for:** archives and category pages

**Use:** End of a long collection before the footer.

**CSS:** `width: 50px; height: 50px; border-radius: 50%; background: #ffc500; color: #000000; display: flex; align-items: center; justify-content: center`

**Text style:** `pagination-number` — Helvetica Neue 700 · 24px/1.375

**Observed:** Current number is a yellow disc. Other bold numbers and ellipsis are unfilled; an outlined circular arrow ends the row. Items have 12px gaps.

**States:** Declared: inactive page link hover underline and 4px solid black border.

## Imagery and graphics

### Editorial documentary photography

**Use:** Lead story, supporting cards and proof chapters.

**Observed:** People, streets, interiors and working environments photographed in natural light with full, believable color. Images are sharp rectangular 4:3 frames, 632×474px for the lead and 300×225px in four-up shelves; text lives outside the picture.

**Transfer:** Photograph real use, material details and people around the new product. If access is limited, use a coherent small set of documentary stills rather than unrelated lifestyle stock.

### Human line illustration

**Use:** Masthead side notes, author portraits and the illustrated invitation; a recurring human counterpoint to photography.

**Observed:** Black contour drawings with expressive angular faces, few flat fills and generous unpainted space. The closing invitation uses muted yellow, cream and black figures around a box; portraits have simple neutral backing.

**Transfer:** Draw a small original scene about receiving, making or using the product; minimum version is one expressive person and one recognizable object in clean black line art.

**Build:** Use an original SVG with irregular closed paths, black 2–4px contours at a roughly 550px-wide drawing size, cream negative space and a few muted yellow fills. Layer two or three simple figures around a central product-shaped object, with no gradients or blur.

### Publication masthead

**Use:** Large identity device at the entrance.

**Observed:** A wide black serif wordmark is centered between small illustrated editorial notes; the wordmark SVG occupies an 832×85px box inside the 154px header.

**Transfer:** Use the new identity as an original wide wordmark with confident serif lettering, flanked by a small operational note and a useful invitation.

**Build:** Set the original product name as a high-resolution SVG text or outlined serif lockup, centered in the middle grid track. Keep the artwork black with transparent backing and an approximately 10:1 wide box; retain generous clear space and smaller flanking drawings.

### Illustrated guide covers

**Only for:** illustrated collections

**Use:** Square art inside blue collection cards.

**Observed:** Dense flat vector-like scenes show architecture, water, people and transport. Strong silhouettes and warm building colors contrast with teal water and dark blue skies; square artwork occupies most of each blue card.

**Transfer:** Create consistent square scenes for product use cases with clear foreground, middle ground and background; a simplified architectural or object vignette is sufficient.

**Build:** Compose square SVG scenes from flat polygons: a dark upper sky, warm rectangular structures in the middle, teal foreground planes, a few outlined windows and small human silhouettes. Keep hard edges, restrained detailing and no soft shadows; inset the square by 16px within the blue card.

### Object and publication photography

**Only for:** catalogues and product shelves

**Use:** Portrait-oriented product shelves and issue grids.

**Observed:** 300×400px frames show objects in hand or against warm off-white studio backgrounds. Books are photographed straight-on with visible thickness and directional real shadows. Covers remain intact in archive grids, with title and issue metadata underneath.

**Transfer:** Use tactile, carefully lit product photographs; for digital goods, show the actual artifact as a readable framed object rather than an invented glossy device render.

### Narrative photo pairs

**Only for:** company narratives

**Use:** Proof between prose passages.

**Observed:** Two 388px-wide images share an 800px column: a clean artifact shot beside a lived-in shop window, interiors or a live recording. Warm wood, reflections and daylight make the world feel inhabited; paired heights match within each row.

**Transfer:** Pair the product with its real context: artifact and workshop, interface and person, finished result and making process.

### Icons

**Observed:** Compact solid black or gray reading, audio and video symbols; most are 24px, secondary metadata icons 20px. Yellow circular audio or play badges are 48–50px; carousel arrows use a 45px outlined circle. Menu and search controls use 32px targets.

**Transfer:** Choose simple publication and media symbols, not a decorative icon for every feature. Keep utility symbols monochrome; reserve yellow discs for actionable media.

## Section recipes

How recurring sections are built.

### First screen: Editorial front opening

**Observed:** White paper is the back layer. A centered promotional banner sits above a 64px utility bar; below it a 154px ruled masthead places a wide 832×85px black wordmark between two small illustrated notes. The 46px category strip follows. Main content begins after a 32px gap in a 1296px frame: a 632px lead column, a 300px story stack and a 300px Broadcast panel. The lead category is small uppercase serif, followed by a regular 32px/1.2 headline, an 18px support sentence and reading metadata. Within the first 900px the banner, navigation, identity, headline, support, secondary story photograph and top of the live panel are visible; the large 632×474px lead photograph begins just below the fold. Actions are in the utility bar and media sidebar rather than a centered hero button cluster.

**Transfer:** Use a compact promotional strip, original wordmark and small contextual side notes to establish an editorial world. Lead with one substantial product promise, adjacent proof story and useful service module. If there is no live media, use a compact dark product briefing with a yellow action. Category and catalogue pages use an Archive title bar before the grid; company narratives use a plain 40px title and wide introduction media.

**Avoid:** Do not replace the layered masthead and column opening with a full-screen centered slogan, giant sans headline or photographic text overlay.

**Text style:** `lead` — Plantin 400 · 32px/1.2

### Ruled editorial shelf

**Observed:** Ruled section header above four Editorial story cards in a 32px-gutter grid; images are 300×225px. A carousel arrow overlaps the right edge of the last image. Vertical rules separate columns and metadata aligns low in the row.

**Transfer:** Use this for capabilities told through specific examples, articles, customer stories or selected resources.

**Text style:** `section-heading` — Plantin 400 · 28px/1.25 · uppercase

### Dark media shelf

**Observed:** Broadcast panel expands to a full-width flat-edged charcoal band, with 32px vertical padding, a white 4px heading rule and a four-up picture row. Yellow circular audio icons sit over the upper-left of each image; titles and metadata reverse to white and pale gray.

**Transfer:** Give demos, interviews or explainers a distinct broadcast chapter without turning the whole page dark.

### Portrait contributors

**Observed:** A ruled heading introduces six roughly 189px square illustrated portraits, each followed by a 20px serif name and a small gray sans role. The column rhythm stays aligned with 32px gaps.

**Transfer:** Use experts, makers or customers as an editorial cast; keep illustrated portraits consistent in framing and line quality.

### Programme interlude

**Observed:** Cream programme contains an 800px-wide centered list, beginning with a small centered serif label. Each row pairs descriptive text and a 300×225px image, separated by fine horizontal rules; a centered underlined all-items link closes the panel.

**Transfer:** Use detailed invitations, release notes, appointments or community opportunities where a compact CTA card would omit useful context.

**Text style:** `feature-title` — Plantin 400 · 24px/1.25

### Illustrated closing invitation

**Observed:** Illustrated invitation pairs a 552×307px human drawing with invitation-heading and body copy, the content vertically centered. It sits within the content frame, separated from the Black directory by 32px.

**Transfer:** Make a specific, friendly invitation to continue the relationship. Keep any form or next action compact and subordinate to the illustration and question.

**Text style:** `invitation-heading` — Plantin 400 · 32px/1

### Directory ending

**Observed:** Black directory is 425px tall at desktop. Within the 1296px frame a wider identity column carries a short serif line, Primary button and Inverse outline button; five Directory columns carry grouped destinations. Copyright sits beneath the brand; the whole group ends with a pale 1px rule.

**Transfer:** Close every page with this practical editorial directory; vary destinations to suit the product without changing its compact character.

### Illustrated collection row

**Only for:** illustrated collections

**Observed:** Ruled section header, four Illustrated guide cards and one understated gray attribution line below. Each 300×365px blue card contains a square 268px illustration.

**Transfer:** Create a collectible visual family for related offerings rather than scattering bright cards among ordinary stories.

### Archive title and grid

**Only for:** archives and category pages

**Observed:** A small breadcrumb precedes a 43px black bar with 8px vertical and 12px horizontal padding. Catalogue archives continue into a four-column portrait cover grid with 32px gutters; category archives use a split lead and supporting four-up stories.

**Transfer:** Use this compact title treatment when the offering is already understood and the reader mainly needs to browse.

**Text style:** `archive-title` — Plantin 400 · 24px/1.125 · uppercase

### Horizontal archive list

**Only for:** category archives

**Observed:** A 932px list sits beside a promotional rail. Rows pair 552px text with a 300×225px image across an 80px gap; titles use feature-title above body copy, metadata rests low, fine rules divide rows, and Pagination ends the list.

**Transfer:** Use for a substantial searchable editorial inventory, not the default short landing-page feature set.

### Company narrative

**Only for:** company narratives

**Observed:** Plain 40px page title above wide introductory media, followed by an 800px prose column. Paragraphs use reading-body with 32px block separation and alternate with equal-width documentary photo pairs. The ending narrows to a plain closing sentence, then a pale rule and the Black directory.

**Transfer:** Explain what the organization believes through tangible places, artifacts and working people rather than a wall of mission statements.

**Text style:** `reading-body` — Plantin 400 · 20px/1.444

## Page flow

**Storyline:** identity and orientation → lead proposition with context → curated evidence and specialist chapters → invitation or continued browsing → practical directory

### Rich editorial landing page for a broad product world

1. **Identity and orientation** — Promotional banner, utility bar, large illustrated masthead and category strip.
2. **Lead proposition** — Asymmetric lead story, stacked secondary proof and compact live-service sidebar.
3. **Capability and proof chapters** — Dark media shelf, curated story grids, contributor portraits, illustrated collection and product shelves.
4. **Relationship invitation** — Cream detailed programme followed by a pale illustrated signup question.
5. **Closing navigation** — Black directory with compact actions.

**Transfer:** Choose enough editorial chapters to reveal a rich product world; preserve the masthead, ruled collections, human art and directory without duplicating the number of shelves.

### Browsable catalogue or release archive

1. **Orientation** — Shared masthead, breadcrumb and compact reversed title bar.
2. **Inventory** — Four-up portrait artifact grid with titles and small uppercase edition details.
3. **Continued browsing** — Bold pagination with yellow current-page disc.
4. **Closing navigation** — Shared black directory, without an extra signup panel.

**Transfer:** Use for editions, resources or physical product collections; let artifact imagery do most of the selling.

### Specialist topic or capability hub

1. **Orientation** — Shared identity and black category title strip.
2. **Lead proof** — Split editorial lead with large image and supporting four-up stories.
3. **Media depth** — Dark audio shelf and a compact promotional interval.
4. **Ongoing evidence** — Horizontal story list beside an image-led promotional rail.
5. **Continued browsing and closing** — Pagination followed directly by black directory.

**Transfer:** Use for a product domain with enough detail to justify an ongoing index; keep the lead selective and the list utilitarian.

### Organization narrative and credibility

1. **Introduction** — Shared masthead, plain page title and wide media introduction.
2. **Positioning** — An 800px introductory prose column.
3. **Tangible proof** — Alternating paragraphs and paired artifact, place and people photographs.
4. **Editorial conclusion** — Short plain closing statement and a light separator.
5. **Closing navigation** — Shared black directory.

**Transfer:** Use a narrower reading rhythm and paired contextual photography to show a coherent way of working.

## Writing

An informed, observant editor speaking with worldly curiosity and practical optimism. Confidence comes through concrete people, places, objects and useful judgments, not inflated sales language.

**Do not copy:** Do not reuse the Monocle name, wordmark, drawings, publication titles, editorial claims, dates, prices, quotations or reported facts as the new product's assets or claims. Source examples illustrate language patterns only.

- **Addressing the reader:** Use we for the organization and you when making a useful invitation; keep descriptive editorial headlines mostly impersonal. Readers are treated as curious, capable adults.
- **Rhythm:** Headlines can be long and specific, often a proposition followed by a question or a colon-led explanation. Support is usually one or two complete sentences; utility labels stay very short. Invitations are warm without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Lead headline | Specific premise, then a question that introduces a tension worth exploring. | About 15–25 words | “Singaporean politicians receive some of the world’s best paycheques. So why should they earn more?” |
| Supporting line | One factual sentence that supplies mechanism or context. | About 15–30 words | “To attract highly skilled workers, the city-state offers salaries that rival private sector jobs.” |
| Section heading | Brief editorial shelf name, often a noun phrase. | 1–5 words | “MEET OUR COLUMNISTS”<br>“LONGER READS” |
| Invitation | Conversational question followed by a clear description of the benefit. | A short question plus one sentence | “Want more stories like these in your inbox?” |
| Primary action | Direct verb or plain service label. | 1–3 words | “Subscribe”<br>“Listen Live” |
| Closing statement | A compact editorial image that sums up the point of view. | One short sentence | “[Brand]: keeping an eye and an ear on the world.” |

**Words and phrasing to use:** Discover; Meet; Inside; a new chapter; our guide to; the people behind; Join us; recommendations; craft; community

**Avoid:** revolutionary; game-changing; 10x; unlock your potential; seamless ecosystem; disrupt; hurry!

**Rules:**

- Name the concrete thing before describing its virtue.
- Use questions to expose a meaningful trade-off, not to manufacture urgency.
- Make each card title useful even when read without its image.
- Allow descriptive subtitles and colons where they add specificity.
- Keep commands practical and editorial; let the surrounding story do the persuasion.

## Do's and Don'ts

### Do

- Keep lead headlines at 32px regular serif with 1.2 line height.
- Use a 1296px frame with 32px gutters for four-up collections.
- Give section headings a 4px top rule and 12px vertical padding.
- Reserve 8px corners for special filled panels and illustrated cards.
- Keep primary actions yellow, square-edged and 44px high; use 40px in the utility bar.
- Align small 13px uppercase metadata at the foot of editorial cards.
- Stage documentary photographs at 4:3 and object shelves at 3:4.
- Close with white headings and #b3b3b3 links on black.

### Don't

- Do not turn the editorial serif hierarchy into bold geometric sans typography.
- Do not introduce pill-shaped primary buttons; circles belong to media controls and pagination.
- Do not give ordinary white story cards 8px radii, tinted fills or floating shadows.
- Do not spread blue across the canvas; keep it concentrated in an illustrated collection.
- Do not use yellow for large body-copy panels; its normal role is the small action signal.
- Do not remove metadata and fine vertical dividers in favor of isolated spacious tiles.
- Do not enlarge the 425px directory into a full-screen slogan ending.
- Do not apply a uniform sepia filter to editorial images; natural color and varied real settings carry the character.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color, border-color and box-shadow transitions at 0.25s ease-in.
- Utility controls declare reduced opacity on hover; menu and search reach 0.5.
- The header changes to a compact centered wordmark while scrolling; the lead editorial feature is sticky within its column.
- Media shelves expose next-slide controls; no autoplay behavior is established.

**Transfer:**

- Keep motion subordinate to reading: use the compact identity change and restrained action feedback rather than large entrance effects.
- Use sticky behavior only within a long lead-and-secondary-story composition.

**Unknown:**

- Carousel timing, autoplay, mobile interactions and animation playback are not established.

### Responsive

**Observed:**

- Desktop layout uses four-up shelves, a six-portrait row and a wide asymmetric opening.
- Declared CSS includes 600px, 768px, 1024px and 1280px among several width thresholds.

**Transfer:**

- On narrow layouts, prioritize the lead story before secondary stories and the compact service module.
- Keep collection imagery readable by reducing columns or using horizontal shelves, not by shrinking four cards indefinitely.
- Retain the identity and small utility actions while allowing category navigation to scroll; stack the illustrated invitation and narrative photo pairs when needed.

**Unknown:**

- Exact narrow-screen typography, navigation behavior, column changes and breakpoint-specific padding are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
