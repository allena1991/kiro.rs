# Shortverse — illustrated creative orbit

## Overview

A bright, creator-facing style with the energy of an illustrated science-fiction poster and the practical structure of a cultural directory. Extremely compressed display lettering meets heavy humanist sans headings and small uppercase monospace labels. White and pale gray dominate, with violet punctuation, pastel landscape illustration, cinematic imagery and floating interface collages; spacious marketing chapters contrast with compact browsing grids.

### Essentials

- Poster lettering opens onto an illustrated world: a centered 120px compressed uppercase headline, 0.8 line height and 0.01em tracking sits over a 600px panoramic scene beneath a 64px white navigation bar.
- Benefits have a violet hinge word: 53.9px CooperHewitt at weight 800, line height 1 and 0.6px tracking, with one upright word in #8a43ff; 18px light supporting copy sits below.
- Actions feel like small printed controls, not bubbles: 44px tall, 5px corners, 24px horizontal padding and 13.9px weight-800 uppercase mono labels with 1.1px tracking.
- Color is concentrated rather than washed across everything: white and #f1f1f1 carry the long explanation, violet marks key words and actions, and a full-width #a77eff callout occupies 320px near the close.
- Product proof is a floating assembly rather than a dashboard slab: roughly 590–630px-wide interface collages face a short text column across a 96px gap; use a small original specimen collage when no interface exists.
- An illustrated journey and a playful closing emblem anchor the identity: fine dark contours, pale blue/lilac landscape layers, a small human-scale figure, and a launch-like vertical motif recur around the opening and closing. Rebuild these with original contour-drawn scenery and a geometric product emblem rather than replacing them with generic gradients.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Launch lavender | `#a77eff` | `--color-lavender` | background, accent | Closing conversion band and emblem edge. |
| Action violet | `#6c00f4` | `--color-action` | action, text, link | Primary marketing action and inverse-button lettering. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Benefit violet | `#8a43ff` | `--color-emphasis` | text, accent | Single-word benefit emphasis and directory status text. |
| Light action violet | `#ede5ff` | `--color-action-tint` | surface | Header's pale violet action background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, inputs and inverse text or buttons. |
| Secondary control gray | `#f2f2f2` | `--color-subtle-control` | surface | Secondary or unavailable controls and featured tags. |
| Chapter gray | `#f1f1f1` | `--color-band` | background, surface | Alternating marketing chapters and portrait backing. |
| Footer gray | `#eaeaea` | `--color-footer` | background | Broad low-contrast footer field. |
| Hairline gray | `#e5e5e5` | `--color-rule` | border | Input outlines and directory row separators. |
| Slogan gray | `#b2b2b2` | `--color-faint` | text | Footer slogan and maker credit. |
| Metadata gray | `#999999` | `--color-muted` | text | Metadata, filters and billing annotations. |
| Charcoal ink | `#262626` | `--color-ink` | text, action | Main text and directory action fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| browsing directories | Count gray | `#cccccc` | `--color-count` | text, surface | Oversized inline collection counts and inactive pagination. |
| editorial discovery pages | Activity paper | `#fafafa` | `--color-activity` | surface | Small social activity blocks. |
| organization directories | Logo backing gray | `#eeeeee` | `--color-avatar` | surface | Backing behind directory organization logos. |
| editorial discovery pages | Cinema navy | `#090b17` | `--color-cinema` | background | Dark cinematic feature stage. |

## Typography

- **CooperHewitt** — Benefit headings, supporting copy, names and directory descriptions. Compact humanist sans with emphatic heavy headings and notably light body copy. If unavailable, use **Barlow**. Use 300 for prose and 700–800 for headings; preserve compact widths. Font stack: "CooperHewitt", "Barlow", Helvetica, Arial, sans-serif.
- **Neumatic-Compressed** — Panoramic opening headline. Extremely tall, tightly packed compressed block capitals. If unavailable, use **Antonio**. Use 700 and condense horizontally if needed to preserve the poster silhouette. Font stack: "Neumatic-Compressed", "Antonio", Impact, sans-serif.
- **JetBrainsMono** — Actions, navigation, metadata and footer labeling. Mechanical monospaced capitals with open tracking. If unavailable, use **JetBrains Mono**. Font stack: "JetBrainsMono", "JetBrains Mono", "Roboto Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| poster | Neumatic-Compressed | 700 | 120px | 0.8 | 0.01em, uppercase | Centered opening statement over illustrated scenery. |
| heading | CooperHewitt | 800 | 53.9px | 1 | 0.0111em | Benefit headlines; directory titles and inline collection counts use the same proportions. |
| callout-heading | CooperHewitt | 700 | 32px | 1.5 | 0.0187em | Closing callout and plan headings. |
| body | CooperHewitt | 300 | 18px | 1.3 | normal | Marketing explanations, hero support and closing support. |
| button | JetBrainsMono | 800 | 13.9px | 1.5 | 0.0805em, uppercase | Filled action labels. |
| navigation | JetBrainsMono | 800 | 13.9px | 1.3 | 0.0805em, uppercase | Header links. |
| footer-link | JetBrainsMono | 700 | 13.9px | 1.7 | 0.088em, uppercase | Footer menu links. |
| footer-marking | JetBrainsMono | 700 | 13.9px | 34px | 0.088em, uppercase | Stacked footer slogan and maker credit. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial discovery pages | shelf-heading | CooperHewitt | 800 | 54.4px | 48px | normal | Large shelf headings beside pastel square icons. |
| organization directories | row-title | CooperHewitt | 700 | 24px | 1.3 | normal | Organization listing names. |
| media catalogs | item-title | CooperHewitt | 700 | 18px | 1.2 | normal | Title beneath a landscape thumbnail. |
| people directories | person-name | CooperHewitt | 700 | 18px | 1.4 | normal | Name below circular portrait. |
| membership comparisons | plan-feature | CooperHewitt | 300 | 18px | 1.5 | normal | Plan feature list and access description. |
| organization directories | row-body | CooperHewitt | 300 | 16px | 1.25 | normal | Two-line organization listing descriptions. |
| browsing directories | filter-label | CooperHewitt | 500 | 16px | 1.25 | 0.01em | Filter control captions. |
| browsing directories | pagination | JetBrainsMono | 800 | 16px | 36px | 0.07em | Centered page numbers. |
| media catalogs | byline | CooperHewitt | 500 | 13.9px | 1.7 | 0.0115em | Creator or author beneath item title. |
| browsing directories and editorial shelves | metadata | JetBrainsMono | 300 | 12px | 1.4 | 0.012em, uppercase | Category, year, duration or location beneath cards. |

**Notes:**

- Compressed uppercase display is reserved for the illustrated opening; ordinary benefit titles stay in the heavy sans.
- The violet word remains upright, the same size and weight as its surrounding heading, not italic or a separate badge.
- Small mono labels use positive tracking; large sans headlines also retain slight positive tracking rather than fashionable negative spacing.
- The 54.4px shelf title is an editorial variant, not a replacement for the 53.9px marketing headline.

## Layout

**Density:** Airy benefit chapters with compact text and control clusters; directories tighten information within each item while retaining substantial separation between rows.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label and compact control gaps. |
| 12px | Listing content stacks, action icon gaps and activity padding. |
| 16px | Shelf card gaps and small text stacks. |
| 24px | Header item gaps, action side padding and plan feature spacing. |
| 32px | Listing row separation, callout support-to-action gap and footer side padding. |
| 48px | Marketing band outer padding and catalog row gaps. |
| 64px | Footer top padding and marketing row horizontal inset. |
| 80px | Marketing row top and bottom padding. |
| 96px | Gap between text and image columns. |
| 128px | Membership section top padding and larger chapter edges. |
| 144px | Gap between membership columns. |

### Containers and grids

- **marketing-container**: max width 1320px · side padding 12px. Centered outer container; benefit rows add 64px inner side insets.
- **benefit-pair**: 2 columns · gap 96px. Unequal visual balance: approximately 458px text opposite a roughly 600px product collage, vertically centered.
- **hero-copy**: max width 880px. Centered poster headline and support above a 550px search field.
- **catalog-grid** (only for browsing directories): max width 1248px · 4 columns · gap 25px. Four 293px columns with 48px row gaps; column gap is 2% of the content width.
- **organization-list** (only for organization directories): max width 880px. Narrow centered list within the wider directory frame.
- **membership-pair** (only for membership comparisons): 2 columns · gap 144px. Two unboxed 256px feature columns centered in the page.
- **editorial-shelf** (only for editorial discovery pages): gap 16px · side padding 38px. Single horizontal row of 250px-wide landscape cards extending past the right edge.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-search | 5px |
| browsing directories | filter-controls | 4px |
| editorial discovery pages | activity-blocks | 8px |
| organization directories | organization-logo | 16px |
| people directories | portrait | 50% |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Base page and white proof chapters.

**CSS:** `background: #ffffff; color: #262626`

**Observed:** Flat, bright and largely unboxed.

**Transfer:** Let content and illustration define depth rather than panel borders.

#### Gray chapter · level 0

**Use:** Groups of related benefits.

**CSS:** `background: #f1f1f1; padding: 48px 0`

**Observed:** Full-bleed neutral band containing several spacious rows.

**Transfer:** Group related capabilities under one band rather than striping every individual row.

#### Launch band · level 0

**Use:** Shared conversion moment.

**CSS:** `background: #a77eff; color: #ffffff; height: 320px; padding: 24px`

**Observed:** A centered copy stack contrasts with a tall illustrated motif at the left.

**Transfer:** Use this concentrated color field as a visual payoff.

#### Footer field · level 0

**Use:** Identity, navigation and attribution.

**CSS:** `background: #eaeaea`

**Observed:** 420px gray base below the conversion band, with substantial empty space on the right.

**Transfer:** Keep the footer visually lower in contrast than the conversion moment.

#### Activity paper · level 1

**Only for:** editorial discovery pages

**Use:** Small attribution and activity clusters.

**CSS:** `background: #fafafa; border-radius: 8px; padding: 12px`

**Observed:** Small avatar and activity label sit together beneath a quote or media card.

**Transfer:** Use for genuine human activity, not all content cards.

#### Cinema stage · level 0

**Only for:** editorial discovery pages

**Use:** Featured media between white shelves.

**CSS:** `background: #090b17; color: #ffffff; height: 576px`

**Observed:** Right-side image blends into the left text area; the image mask reaches full opacity at 55%.

**Transfer:** Choose the stage color to continue the image's dark edge rather than framing the image in a card.

## Components

### Navigation bar

**Use:** Global wayfinding.

**CSS:** `display: flex; align-items: center; gap: 24px; height: 64px; padding: 16px 40px; background: #ffffff`

**Text style:** `navigation` — JetBrainsMono 800 · 13.9px/1.3 · tracking 0.0805em · uppercase

**Observed:** Compact violet wordmark on the left, three short links, a shallow search field, then account action and Light action button on the right. The bar is in document flow.

**Transfer:** Use a narrow wordmark and a concise set of destinations.

### Primary button

**Use:** Main marketing conversion on a neutral surface.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 12px; height: 44px; padding: 4px 24px; border-radius: 5px; background: #6c00f4; color: #ffffff`

**Text style:** `button` — JetBrainsMono 800 · 13.9px/1.5 · tracking 0.0805em · uppercase

**Observed:** Compact rectangular control; directory rows instead use charcoal, and secondary membership requests use a very pale gray fill.

**Transfer:** Choose the violet version for a new marketing page; reserve charcoal for repeated directory actions.

### Light action button

**Use:** Prominent header action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 12px; height: 44px; padding: 4px 24px; border-radius: 5px; background: #ede5ff; color: #6c00f4`

**Text style:** `button` — JetBrainsMono 800 · 13.9px/1.5 · tracking 0.0805em · uppercase

**Observed:** A soft fill distinguishes the action from bare navigation links.

### Inverse button

**Use:** Conversion on the lavender band.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 4px 24px; border-radius: 5px; background: #ffffff; color: #6c00f4`

**Text style:** `button` — JetBrainsMono 800 · 13.9px/1.5 · tracking 0.0805em · uppercase

**Observed:** Single centered action below the support line; no pill silhouette or glow.

### Underlined text link

**Use:** Secondary explanation within the closing support.

**CSS:** `display: inline-flex; align-items: center; color: #ffffff; border-bottom: 1px solid #ffffff`

**Text style:** `body` — CooperHewitt 300 · 18px/1.3

**Observed:** Follows the support sentence inline and ends in a small right chevron; neutral information areas use a charcoal underline.

### Hero search

**Use:** A direct exploration action within the opening.

**CSS:** `width: 550px; height: 64px; padding: 10.8px 14.4px 10.8px 21.6px; background: #ffffff; border: 1px solid #e5e5e5; border-radius: 5px`

**Observed:** One broad white field under the support line with a gray magnifying glass at the right. A smaller 256px by 38px version lives in navigation.

**Transfer:** For a product without search, preserve the centered white action footprint with an appropriately simple entry control.

### Footer columns

**Use:** Identity-led final navigation.

**CSS:** `display: grid; grid-template-columns: 25% 15% 15% 15% 1fr; max-width: 1320px; padding: 64px 32px 16px`

**Text style:** `footer-link` — JetBrainsMono 700 · 13.9px/1.7 · tracking 0.088em · uppercase

**Observed:** Large triangular emblem at left, a faint stacked slogan beside it, two short menu columns, and open space to the right. Links occupy 34px rows; the low-contrast maker line sits beneath.

**Transfer:** Create an original geometric emblem and a short stacked promise; retain the left-heavy composition.

### Filter control

**Only for:** browsing directories

**Use:** Faceted discovery.

**CSS:** `display: flex; align-items: center; gap: 8px; height: 42px; padding: 8px 10px 8px 12px; background: #ffffff; border: 1px solid #e5e5e5; border-radius: 4px; color: #999999`

**Text style:** `filter-label` — CooperHewitt 500 · 16px/1.25 · tracking 0.01em

**Observed:** Gray category icon, caption, then plus sign; controls wrap into rows above sort and result count.

### Media tile

**Only for:** media catalogs

**Use:** Image-first catalog results or editorial shelves.

**CSS:** `width: 293px; color: #262626`

**Text style:** `item-title` — CooperHewitt 700 · 18px/1.2

**Observed:** Unboxed landscape thumbnail at 293px by 164px, followed after 13px by a bold title, a smaller byline and muted mono metadata. Shelf variant is 250px by 140px. Release-status labels sit over media on a translucent dark tab.

**Transfer:** Keep the image near 16:9; preserve a strong difference between title, creator and metadata.

### Organization row

**Only for:** organization directories

**Use:** Comparable entries with a repeated action.

**CSS:** `max-width: 880px; padding-bottom: 32px; border-bottom: 1px solid #e5e5e5`

**Text style:** `row-title` — CooperHewitt 700 · 24px/1.3

**Observed:** A 160px logo with 16px corners and white 2px edge leads a 464px information column. The last column right-aligns violet status above a charcoal Primary button. Description is limited to two lines, with optional qualification tags below.

**Transfer:** Use the same hierarchy for partners, services or opportunities without wrapping the whole row in a raised card.

### Person tile

**Only for:** people directories

**Use:** Community browsing.

**CSS:** `width: 293px; color: #262626`

**Text style:** `person-name` — CooperHewitt 700 · 18px/1.4

**Observed:** Large circular 293px portrait precedes a left-aligned name after 24px, with optional role and small mono location. Portraits include candid photos, illustrations and letter avatars.

**Transfer:** Use authentic, varied images; clip consistently to a circle rather than imposing one photographic treatment.

### Activity block

**Only for:** editorial discovery pages

**Use:** Attribution beneath community comments and liked items.

**CSS:** `display: flex; align-items: flex-start; gap: 8px; padding: 12px; background: #fafafa; border-radius: 8px`

**Observed:** A small round avatar with a tiny colored activity mark sits beside actor, verb and timestamp. These blocks remain visually subordinate to the comment.

**Transfer:** Use real activity; keep the cluster compact and low contrast.

## Imagery and graphics

### Illustrated horizon

**Use:** Opening world-building and a closing scenic bridge.

**Observed:** Wide hand-drawn science-fiction landscape with fine irregular charcoal contours, pale blue sky, white wind-shaped clouds, lilac ground and pink launch smoke. A small backpacked viewer at the bottom establishes scale. The closing scene uses a mint-blue basin, rock spires and two travelers, with its upper edge fading into white.

**Transfer:** Invent a world around the new product's idea of progress. Minimum equivalent: an original layered SVG landscape with contour lines, one small human-scale silhouette and a vertical tool-like object; keep central sky open for lettering.

**Build:** Use a 1440-by-600 SVG viewBox. Layer a pale blue sky, long irregular white cloud paths, distant triangular ridge paths and a darker foreground across the lower fifth. Draw sparse broken contour strokes in charcoal at low opacity. Add three slender vertical silhouettes at differing heights with curled pastel-pink plume paths beneath; place a small rear-facing figure near the lower center. For the closing bridge, raise rock silhouettes at both edges, leave the top center white, and place two figures at the right. Use flat pastel fills rather than glossy 3D or blurred neon.

### Floating product collage

**Use:** Visual evidence opposite each benefit headline.

**Observed:** Isolated interface fragments occupy about half the row: overlapping page windows, a credit sheet, a poster, media stills and small honors. White cards carry soft gray image-local shadows; purple action markers and a large cursor dramatize the useful interaction. Other collages use a central video surrounded by people and organization circles, three colored message bubbles, or a profile panel.

**Transfer:** Use two to four legible original fragments showing one concrete outcome per scene. If no interface exists, combine a finished artifact, one process card and a simple annotation with the same floating silhouette.

**Build:** Arrange two or three rectangular HTML or SVG panels in a roughly 600px-wide transparent stage, offset vertically and overlapping by about one quarter. Put the largest result behind, a narrower evidence strip in front and one violet action marker at the intersection. Apply a restrained soft gray shadow only to these floating fragments; leave the surrounding chapter flat.

### Launch vignette and emblem

**Use:** Signature conversion illustration and footer identity.

**Observed:** A tall slender rocket rises above a pink smoke pile on the left of the violet band; the art is 321px by 352px and projects 24px above the band. Beneath it, a 217px by 153px triangular badge has a lavender rim, dark center and a simple white/violet symbol.

**Transfer:** Create an original upward-moving tool, seed, beacon or vehicle with a contour-drawn plume, paired with an original emblem. Retain the whimsical scale contrast and broad empty space.

**Build:** In a 321-by-352 SVG, draw a very narrow vertical object in the upper two thirds, a winding exhaust contour below and a broad scalloped cloud at its base. Use pale lilac and pink fills with thin charcoal contours. Construct a separate rounded triangular badge using a thick lavender outer path, dark inset and a two-shape product glyph with a tiny four-point sparkle.

### Cinematic stills

**Only for:** editorial discovery pages and media catalogs

**Use:** Featured stage and thumbnail grids.

**Observed:** Full-color film stills retain their own diverse lighting and embedded title art. Feature stages fill the viewport width and blend imagery from the right into a solid left-side copy field; smaller cards use rectangular landscape framing without decorative mats.

**Transfer:** Use actual customer work, product outcomes or documentary-style scenes with comparable visual richness. Do not recolor every thumbnail to violet.

### Human portraits

**Only for:** people directories

**Use:** Community grid.

**Observed:** Oversized circular images mix monochrome headshots, colorful candid photography, illustrations and solid-color initial avatars against a white page.

**Transfer:** Keep individual personality and variation; use a letter avatar for missing portraits rather than an empty image slot.

### Icons

**Observed:** Navigation and filters use compact functional symbols, generally 20–24px. Feature shelves pair headings with 48px colored symbols on 64px pastel rounded squares. Tiny colored location or activity icons live in 16px backing squares. The closing inline chevron is 18px by 24px.

**Transfer:** Choose a coherent simple icon set for controls; reserve stronger color and larger square backing for editorial section markers.

## Section recipes

How recurring sections are built.

### First screen: Illustrated poster opening

**Observed:** A 64px Navigation bar sits above a 600px edge-to-edge Illustrated horizon. Behind the copy are layered sky, distant ridges, launch trails and a foreground viewer. Center the 120px poster headline across an approximately 880px block in the upper-middle of the scene, followed by the 18px support sentence and Hero search. The headline reads as one dense horizontal black silhouette; the white field is the only large control on the illustration. Within the first 900px, the entire navigation, illustration, headline, support and search are visible, then the gray first benefit chapter begins and its product collage starts to enter. Most benefit text and the remainder of that collage fall below the fold.

**Transfer:** For any new marketing landing page, create an original illustrated world with a large open sky and one human-scale anchor, then fit a short compressed headline and direct entry action into it. Use a simple SVG landscape when bespoke illustration is unavailable. Directory openings instead use a left-aligned two-line sans title with a pale inline total and filter toolbar; editorial discovery can open on a cinematic image stage.

**Avoid:** Do not substitute an all-white centered SaaS hero, a giant rounded dashboard container or a gradient blob behind regular-width type.

**Text style:** `poster` — Neumatic-Compressed 700 · 120px/0.8 · tracking 0.01em · uppercase

### Benefit and floating proof

**Observed:** Gray chapter or White canvas holds a centered benefit-pair layout. Each row uses 80px top and bottom padding, 64px side insets and 96px column gap. A short 53.9px heading highlights one violet word, with 18px light copy beneath; the Floating product collage is roughly 600px wide and vertically centered opposite. Groups change background and can reverse which side holds text.

**Transfer:** Assign one outcome to each row and demonstrate that outcome with a focused artifact rather than a full dashboard. Group related rows on the same background.

**Text style:** `heading` — CooperHewitt 800 · 53.9px/1 · tracking 0.0111em

### Illustrated conversion and identity close

**Observed:** Launch band carries a centered 32px white heading, 496px-wide light support text, an Underlined text link and one Inverse button. The Launch vignette sits left and extends beyond the upper edge. Footer field then supplies a 420px identity zone with Footer columns, a large emblem, faint stacked slogan and lower maker line. A marketing story can lead into this with the Illustrated horizon's closing scenic bridge.

**Transfer:** Preserve the illustrated upward gesture, centered invitation and left-heavy emblem footer with original art and a concise product promise. Let this shared close unify different content types.

**Text style:** `callout-heading` — CooperHewitt 700 · 32px/1.5 · tracking 0.0187em

### Unboxed membership comparison

**Only for:** membership comparisons

**Observed:** White canvas with 128px top padding and two centered 256px columns separated by 144px. A 32px heading incorporates the price inline for the self-serve plan; violet distinguishes it from the charcoal access-by-request plan. Small billing support precedes compact actions, then 18px feature lines with small emoji-like markers and 24px spacing. A scenic illustration rises beneath the final guidance text rather than enclosing the plans in cards.

**Transfer:** Keep plan names, cost and access model easy to compare; use open columns and an illustrated bottom edge rather than pricing-card chrome.

**Text style:** `callout-heading` — CooperHewitt 700 · 32px/1.5 · tracking 0.0187em

### Directory title and controls

**Only for:** browsing directories

**Observed:** Within a 1248px content area, the 53.9px heading wraps to two short lines and ends with a #cccccc total at the same scale. Filters sit beneath, followed by sort on the left and range/count on the right. The first row of results appears within the initial 900px.

**Transfer:** Give a search or catalog page a task-oriented verb headline and a real count; keep controls shallow enough that results remain visible.

**Text style:** `heading` — CooperHewitt 800 · 53.9px/1 · tracking 0.0111em

### Catalog or community grid

**Only for:** browsing directories

**Observed:** Four columns of 293px Media tiles or Person tiles, 25px horizontal spacing and 48px row gaps on White canvas. The organization variant uses Organization rows in a centered 880px list instead. Pagination follows the final results with a dark current square and pale gray subsequent squares, white mono numerals and chevron controls.

**Transfer:** Choose rectangular media, circular people or comparable rows according to the subject; preserve the common title/control structure and shared conversion ending.

### Editorial shelves and activity

**Only for:** editorial discovery pages

**Observed:** White shelves pair a large 54.4px heading with a pastel 64px icon block and a small uppercase see-all link. Landscape cards continue horizontally beyond the right edge, 250px wide with 16px gaps. A comments shelf instead uses roughly 312px text columns with 32px gaps and Activity blocks beneath; a Cinema stage can interrupt the shelves.

**Transfer:** Alternate curated work and real community response. Keep the shelf format for a discovery portal rather than forcing it onto every marketing page.

**Text style:** `shelf-heading` — CooperHewitt 800 · 54.4px/48px

## Page flow

**Storyline:** Invitation into a creative world → tangible outcomes or browsable work → human or practical proof → access decision where needed → illustrated invitation and identity close.

### Flagship product explanation

1. **Promise** — Illustrated poster opening with a broad entry field.
2. **Capability chapters** — Gray and white benefit groups with violet hinge words and floating product proof.
3. **Human proof** — Audience, feedback and connection scenes turn capabilities into personal outcomes.
4. **Access decision** — Unboxed two-column membership comparison.
5. **Closing call** — Scenic bridge, lavender invitation, then emblem-led footer.

**Transfer:** Use as the default landing-page narrative; choose benefit groups appropriate to the new product rather than reproducing a fixed sequence.

### Editorial discovery portal

1. **Featured work** — Full-width cinematic stage with concise text and a watch action.
2. **Community proof** — Latest comments in horizontal text columns with activity attributions.
3. **Discovery** — Curated horizontal media shelves, interspersed with another image-led feature.
4. **Closing call** — Shared lavender invitation and emblem footer.

**Transfer:** Use for products whose output is best discovered through a changing collection of work.

### Organization and opportunity directory

1. **Task framing** — Two-line action title with a pale oversized collection total.
2. **Selection** — Filters and sort precede centered, ruled organization rows.
3. **Decision support** — Logo, concise description, qualifications and right-aligned status/action.
4. **Continuation** — Centered pagination before the shared illustrated invitation and footer.

**Transfer:** Adapt for resource, supplier or opportunity lists with repeated comparable information.

### People and community discovery

1. **Task framing** — Heavy sans title with inline pale count and faceted filters.
2. **Human discovery** — Four-column grid of large circular portraits and compact names.
3. **Continuation** — Pagination after the final portrait row.
4. **Closing call** — Shared launch illustration, centered invitation and gray identity footer.

**Transfer:** Use for a real community where identity and personality are primary.

### Searchable media catalog

1. **Task framing** — Two-line viewing promise, collection total and wrapping filter controls.
2. **Browsable proof** — Four-column landscape thumbnail grid with title, creator and mono metadata.
3. **Continuation** — Status tabs distinguish unreleased items; pagination follows the last row.
4. **Closing call** — Shared illustrated conversion band and footer.

**Transfer:** Use for collections of projects or outcomes whose visual previews are the main selection tool.

## Writing

Enthusiastic and practical, like a fellow creator explaining useful tools. Imaginative framing surrounds concrete descriptions of what someone can make, manage, discover or share.

**Do not copy:** Do not reuse Shortverse's name, wordmark, emblem, illustrations, film titles, creator names, quotes, collection totals, prices, partner logos or performance claims. Replace these with original assets and truthful product-specific facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader with you and your. Describe actions in plain verbs and refer to the community as people doing real work.
- **Rhythm:** Short benefit headlines usually contain 2–8 words; supporting paragraphs use one to three compact sentences. Directory descriptions are denser and truncated, while controls remain one to three words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | An expansive invitation into a shared world. | 6–10 words | “Explore the Universe of Short Film” |
| Benefit headline | A direct outcome with one meaningful noun or verb emphasized. | 2–8 words | “All the details in one place”<br>“Get your film seen”<br>“Make new connections” |
| Supporting line | Name the intended audience or describe a practical action and its benefit. | 12–40 words | “Filmmakers, industry professionals, and fans of short film—all in one place.”<br>“Keep your film private to build buzz and send out private screeners while your film tours festivals. Premiere your film to the public when you're ready.” |
| Primary action | A short verb phrase with a concrete object or access level. | 1–3 words | “Get Pro”<br>“Add a Film”<br>“Submit Now” |
| Closing invitation | Invite participation, then list several simple benefits with active verbs. | 6–8 word title and one short support sentence | “Join the Universe of Short Film”<br>“Share your film, Follow top filmmakers, Discover new festivals, Make new connections.” |

**Words and phrasing to use:** Make; Build; Share; Discover; Connect; your work; all in one place; when you're ready

**Avoid:** enterprise-grade synergy; disruptive ecosystem; unparalleled solution; revolutionary AI-powered platform

**Rules:**

- Emphasize the one word that carries the benefit, not decorative filler.
- Explain what the tool changes in someone's workflow before listing technical implementation.
- Use task-oriented titles for directories and inviting world-building language for broad marketing.
- Keep status, sort and metadata literal; let illustration carry most of the whimsy.

## Do's and Don'ts

### Do

- Keep the opening poster face compressed at 120px/0.8 on desktop, distinct from the 53.9px benefit sans.
- Use weight 300 at 18px/1.3 for ordinary marketing paragraphs.
- Keep action controls at 44px with 5px corners and positively tracked uppercase mono.
- Use a 96px text-to-collage gap and 80px vertical row padding for benefit chapters.
- Concentrate the largest violet fill in the 320px conversion band.
- Keep product fragments around 600px wide and let them float without a surrounding panel.
- Preserve 48px row gaps in four-column catalogs and a clear title/byline/metadata hierarchy.
- Carry the original illustrated journey into the closing vignette and emblem footer.

### Don't

- Do not turn 5px action corners into full pills; the controls should feel compact and printed.
- Do not set body copy at the same heavy weight as the 800-weight benefit headings.
- Do not use tightly negative tracking on the heavy sans; its measured heading tracking is positive.
- Do not fill every chapter with violet; neutral bands and white are the dominant canvas.
- Do not add drop shadows to the full page's ordinary tiles or ruled rows; depth belongs inside product collages.
- Do not replace the 293px circular community portraits with tiny avatars inside bordered cards.
- Do not flatten item titles, bylines and 12px mono metadata into one text style.
- Do not center all footer columns symmetrically; retain the large left emblem and open right side.

## Motion and responsive

### Motion

**Observed:**

- The editorial feature stages have carousel position dots and a current item; the defined image mask blends to full opacity at 55%.
- No action transitions or animations are established.

**Transfer:**

- Retain the static layered scene and readable copy even when implementing a rotating feature stage.

**Unknown:**

- Carousel timing, autoplay behavior, hover and focus treatments, and illustration animation are unspecified.

### Responsive

**Observed:**

- Desktop composition uses a 1320px outer container; catalogs use four columns with a 2% column gap.
- Illustrated backgrounds use cover sizing and bottom-center positioning.

**Transfer:**

- Recommended adaptation: keep the landscape horizon and small scale-giving figure visible while allowing the poster headline to wrap on narrow screens.
- Recommended adaptation: stack benefit copy and collage without enclosing them in cards; reduce catalog columns while retaining landscape media and circular portraits.

**Unknown:**

- No verified mobile layouts or breakpoint values; desktop text sizes are not established as fluid formulas.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
