# Heart Aerospace — engineering at horizon scale

## Overview

An expansive industrial style that makes ambitious technology feel tangible rather than speculative. White editorial space and black closing bands frame bold neo-grotesk type, cool gray technical material and sparing deep blue accents. Cinematic product imagery, isolated studio views and documentary photography carry most of the emotion; text remains economical and factual.

### Essentials

- A cinematic object leads, not a dashboard: a 900px full-bleed opening with an 80px white navigation bar, the product across the upper-middle field and a 129.6px/1 bold white headline anchored low left.
- Typography becomes scenery: a short product identifier expands to 489.6px/0.9 with -0.04em tracking, spanning nearly the full width behind an isolated product. Every new landing page needs this monumental type-and-object device; use a short category word and a clean product silhouette when no hero render exists.
- The interface is square and almost unadorned: 44px black action rectangles, 12px 16px padding, square outlined companion controls, no pill buttons or raised card shadows.
- Color belongs mainly to the world around the product: white dominates editorial sections, black anchors the footer, and blue #001489 is restricted to small labels, links and factual graphics. The one broad graphic wash runs from muted violet-gray #716e85 into white.
- Product views alternate between environmental scale and orthographic clarity: edge-to-edge 1440px imagery contrasts with isolated views inside a 1280px content width and 64px two-column gaps.
- Credibility stays open and unboxed: 50px/1.2 section headings, 18px/1.5 gray support text and monochrome marks in a three-column grid with 40px gaps; close with a substantial black directory rather than a promotional signup card.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet horizon | `#716e85` | `--color-horizon` | background | Broad transition between the cinematic opening and monumental product typography. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Engineering blue | `#001489` | `--color-blue` | text, link, accent | Eyebrows, editorial links and quantitative emphasis; not a page-wide brand fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Main editorial canvas and reversed text. |
| Pale panel | `#f7f8fa` | `--color-panel` | surface | Secondary media and portrait backing. |
| Media gray | `#eeeff2` | `--color-stage` | surface | Backing for full-width media; the image remains the visible content. |
| Card rule | `#e2e2e2` | `--color-card-rule` | border, accent | Milestone card edges, compact statistic rules and pale chart segments. |
| Cool rule | `#dcdee3` | `--color-rule` | border | Header edge, technical tables and framed publication material. |
| Footer label gray | `#999999` | `--color-footer-label` | text | Visible white at 60% opacity over black, used for directory labels. |
| Dark-section gray | `#949494` | `--color-muted-dark` | text | Supporting quotations on black; also a footer-link hover color. |
| Body gray | `#767676` | `--color-secondary` | text | Supporting paragraphs, captions and technical labels. |
| Footer rule gray | `#262626` | `--color-footer-rule` | border | Visible white at 15% opacity over black for the bottom directory divider. |
| Black | `#000000` | `--color-ink` | text, background, action, border | Primary headings, controls, dark chapters and footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical product and rationale pages | Analysis gray | `#eeefef` | `--color-analysis` | background | Broad factual comparison and explanatory bands. |
| technical product pages | Technical ink | `#14171b` | `--color-charcoal` | text, surface | Headings in analytical bands and dark portrait backing. |
| analytical sections | Slate | `#2f343d` | `--color-slate` | text, accent | Analytical prose and a dark neutral segment of comparison charts. |
| comparison graphics | Chart gray | `#888b8d` | `--color-chart-gray` | accent | Neutral category in stacked comparisons. |

## Typography

- **nhgText** — Body text, navigation, section headings, statistics and monumental identifiers. Neutral neo-grotesk with sturdy bold forms and a compact, workmanlike rhythm. If unavailable, use **Inter**. Use 400–700; retain each recipe's tracking and line height. Font stack: "nhgText", "Inter", "Neue Haas Grotesk", system-ui, sans-serif.
- **nhgDisplay** — Opening headlines. Display neo-grotesk with closely fitted bold forms. If unavailable, use **Inter**. Use 700 and preserve the large-scale negative tracking. Font stack: "nhgDisplay", "Inter", "Neue Haas Grotesk Display", system-ui, sans-serif.
- **Arial** (only for unit-selection controls) — Compact two-option switches. Plain system sans, deliberately utilitarian. Font stack: "Arial", sans-serif.
- **Inter** (only for publication proof sections) — Publication section headings and italic quotations. Contemporary neutral sans with a clear small italic. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| monument | nhgText | 700 | 489.6px | 0.9 | -0.04em | fixed | Short identifier rendered as full-width scenery behind the product. |
| display | nhgDisplay | 700 | 129.6px | 1 | -0.02em | fixed | Primary cinematic opening headline. |
| heading | nhgText | 700 | 50px | 1.2 | normal | fixed | Default major editorial and credibility headings. |
| benefit | nhgText | 700 | 40px | 1.1 | -0.01em | size clamp(28px, 0.5rem + 2.5vw, 40px) | Short benefit titles paired with isolated product views. |
| body | nhgText | 400 | 18px | 1.5 | normal | fixed | Default supporting text and footer links. |
| editorial-body | nhgText | 400 | 18px | 1.556 | normal | fixed | Benefit support and longer editorial paragraphs. |
| navigation | nhgText | 400 | 14px | 2.286 | normal | fixed | Desktop navigation links. |
| button | nhgText | 400 | 14px | 1 | normal | fixed | Compact solid utility actions. |
| footer-label | nhgText | 500 | 12px | 1.5 | 0.125em, uppercase | fixed | Small directory column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| demonstration pages | product-display | nhgDisplay | 700 | 97px | 1 | -0.02em | size clamp(40px, 7vw, 97px) | Demonstration-led cinematic headline. |
| demonstration-to-product closing sections | stat-large | nhgText | 700 | 97px | 1 | -0.03em | fixed | Oversized numerical proof with units kept inline. |
| informational and technical detail pages | page-title | nhgDisplay | 700 | 56px | 1.1 | normal | fixed | White editorial introduction headline. |
| demonstration pages | product-heading | nhgText | 700 | 50px | 1 | -0.02em | size clamp(28px, 4vw, 50px) | Tighter section heading for media-rich product chapters. |
| demonstration pages | film-action | nhgText | 700 | 43.2px | 1 | -0.02em | size clamp(20px, 3vw, 50px) | Large unboxed watch action beside the opening copy. |
| technical and rationale pages | technical-heading | nhgText | 700 | 36px | 1.2 | normal | fixed | Analytical subsection titles. |
| technical product pages | stat | nhgText | 700 | 36px | 1.1 | -0.01em | fixed | Compact numerical product facts. |
| company history | milestone-date | nhgText | 700 | 36px | 1 | -0.01em, features "tnum" | fixed | Prominent time marker before an event title. |
| media-rich product pages | media-title | nhgText | 700 | 24px | 1.2 | -0.01em | fixed | Video and capability tile titles. |
| company history | milestone-title | nhgText | 600 | 24px | 1.25 | normal | fixed | Event title beneath a date. |
| demonstration pages | product-support | nhgText | 400 | 21.6px | 1.3 | normal | size clamp(16px, 1.5vw, 24px) | Product chapter support lines. |
| technical product sections | stat-label | nhgText | 400 | 18px | 1.3 | 0.08em, uppercase | fixed | Technical labels above large data. |
| people directories | portrait-name | nhgText | 700 | 18px | 1.3 | normal | fixed | White name over portrait foot. |
| unit-selection controls | unit-control | Arial | 400 | 14px | 1 | normal | fixed | Paired measurement switch labels. |
| people directories | portrait-role | nhgText | 400 | 14px | 1.4 | normal | fixed | Smaller role below a portrait name. |
| publication proof sections | publication-quote | Inter | 400 italic | 14px | 1.5 | normal | fixed | External quotation below a publication image. |
| informational and technical detail pages | eyebrow | nhgText | 500 | 12px | 2.667 | 0.08em | fixed | Small blue category above an editorial title. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use bold weight 700 for the visual hierarchy, regular 400 for support; 500 and 600 are reserved for small labels and milestone titles.
- Large display tracking tightens from -0.02em to -0.04em for monumental identifiers; ordinary body and default section headings keep normal tracking.
- The default heading is 50px/1.2. The compact 50px/1 variant belongs to demonstration chapters, not every editorial section.
- Keep measurement units in the same bold face and line as the number; labels are subordinate rather than competing badges.

## Layout

**Density:** Airy: long image-led passages and 64px–96px section breathing room contrast with tightly grouped labels and controls.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Footer link stack and statistic value-to-label spacing. |
| 8px | Tight headline-to-support and icon-to-label gaps. |
| 12px | Benefit title-to-body gap and caption separation. |
| 16px | Eyebrow-to-title gap; media title separation. |
| 24px | Media grid gaps and milestone card inset. |
| 32px | Heading-to-media spacing and technical grid gaps. |
| 40px | Credibility grid gaps and opening bottom inset. |
| 48px | Major heading-support groups, gallery groups and footer side inset. |
| 64px | Editorial column gap, credibility section padding and footer vertical padding. |
| 80px | White introduction and product chapter vertical padding; benefit-row separation. |
| 96px | Technical and editorial longform section vertical padding. |
| 120px | Dark portrait statement and history band vertical padding. |

### Containers and grids

- **editorial container**: max width 1280px · side padding 64px. Centered main content; at 1440px the content begins 80px from each edge.
- **navigation container**: max width 1440px · gap 32px · side padding 56px. Logo left, compact horizontal text navigation right.
- **benefit split**: 2 columns · gap 64px. Equal image and text columns, vertically centered; multiple rows form a loose stack.
- **credibility grid**: 3 columns · gap 40px. Open monochrome mark cells, 400px by 140px at desktop.
- **footer container**: max width 1440px · 3 columns · gap 64px · side padding 48px. Directory grid in a 1.5:1:1 ratio; a separate bottom identity bar spans all columns.
- **media grid** (only for media-rich product and company pages): 3 columns · gap 24px. Three landscape video, location or publication tiles.
- **history container** (only for company history): max width 1200px · side padding 32px. Alternating 552px cards with a centered vertical timeline.
- **people grid** (only for people directories): max width 1152px · 4 columns · gap 24px. Four 270px portrait cards per row, with 32px row separation.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls and cards | 0px |
| company history | timeline markers | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| company history | timeline marker ring | `0px 0px 0px 1px #ffffff` | White outer hairline around a black-ringed timeline point. |

### Surfaces

#### Editorial canvas · level 0

**Use:** Default page surface.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** White sections run directly into one another without panel framing.

**Transfer:** Use whitespace and typography, not elevated wrappers, to distinguish text chapters.

#### Horizon stage · level 0

**Use:** Monumental identifier and isolated product composition.

**CSS:** `background: linear-gradient(#716e85 0px, #ffffff 65%); position: relative`

**Observed:** A long vertical transition carries the cinematic palette into a white studio stage.

**Transfer:** Retain the muted violet-to-white atmosphere rather than a saturated brand gradient.

#### Media backing · level 0

**Use:** Backing behind edge-to-edge media.

**CSS:** `background: #eeeff2; overflow: hidden`

**Observed:** Normally covered by photographic or rendered product imagery.

**Transfer:** Keep the media visible and correctly fitted.

#### Black chapter · level 0

**Use:** Footer and occasional high-contrast narrative chapter.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat black, no texture, glow or drop shadow.

**Transfer:** Give black sections substantial vertical space and keep their hierarchy direct.

#### Analysis band · level 0

**Only for:** technical product and rationale pages

**Use:** Comparisons, geography and visual explanation.

**CSS:** `background: #eeefef; padding: 96px 64px`

**Observed:** Full-width gray bands hold charts and supporting columns, not floating cards.

**Transfer:** Use one consistent analytical backing for related evidence.

#### Publication frame · level 1

**Only for:** publication proof sections

**Use:** Tall external editorial image.

**CSS:** `background: #f7f8fa; border: 1px solid #dcdee3; overflow: hidden`

**Observed:** A lightly outlined portrait-oriented document frame sits above an italic quotation.

**Transfer:** Use legible editorial proof with a restrained edge rather than a decorative browser mockup.

#### Photo legibility veil · level 1

**Only for:** rationale backdrop chapters

**Use:** White copy over a detailed interior photograph.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0.75) 0px, rgba(0, 0, 0, 0.6) 30%, rgba(0, 0, 0, 0.6) 70%, rgba(0, 0, 0, 0.75) 100%)`

**Observed:** Darkened industrial imagery remains recognizable under white headings and three lower text columns.

**Transfer:** Preserve structural detail while suppressing highlights behind text.

## Components

### Navigation bar

**Use:** Persistent desktop orientation.

**CSS:** `height: 80px; background: #ffffff; border-bottom: 1px solid #dcdee3; position: fixed; z-index: 100`

**Text style:** `navigation` — nhgText 400 · 14px/2.286

**Observed:** Compact black logo on the left; a single line of links aligned right. The active link uses an underline and weight 500. Navigation content has 56px side inset and 32px gaps.

**States:** Declared: hover opacity 0.6 on links; focus-visible 2px solid black outline, 4px offset, opacity 0.8 and 2px radius; active opacity 0.7.

**Transfer:** Keep the chrome visually small against the cinematic opening.

### Utility button

**Use:** Download or other concrete secondary action.

**CSS:** `background: #000000; color: #ffffff; height: 44px; padding: 12px 16px; display: flex; align-items: center; justify-content: center; gap: 8px; border-radius: 0px`

**Text style:** `button` — nhgText 400 · 14px/1

**Observed:** A compact label, optional file-size metadata and a downward arrow share one horizontal control.

**States:** Declared: hover opacity 0.85; focus-visible 2px solid #3a8fbd outline with 2px offset.

**Transfer:** Reserve solid controls for a specific utility, not a cluster of competing hero conversions.

### Credibility marks

**Use:** Institutional or customer proof without testimonial cards.

**CSS:** `display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 40px; align-items: center`

**Observed:** Monochrome marks are contained, centered and optically balanced in broad white cells rather than filling each slot.

**Transfer:** Normalize apparent visual weight, not just logo image dimensions.

### Directory footer

**Use:** Substantial common ending.

**CSS:** `background: #000000; color: #ffffff; padding: 64px 0px`

**Text style:** `body` — nhgText 400 · 18px/1.5

**Observed:** Three columns contain navigation, social links with small icons and a multiline address. Use footer-label for headings; link rows have 4px vertical padding and 4px stack gaps. After a 64px gap, a top rule of white at 15% opacity separates a lower logo-left, copyright-right bar with 24px top padding.

**States:** Declared: hover link opacity 0.8 and color #949494; focus-visible 2px solid white outline with 3px offset and opacity 0.8; active opacity 0.7.

**Transfer:** End with useful institutional information rather than inventing a final conversion panel.

### Unit switch

**Only for:** technical product sections

**Use:** Switch a group of facts between two measurement systems.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid #000000; height: 44px; padding: 12px 16px; border-radius: 0px`

**Text style:** `unit-control` — Arial 400 · 14px/1

**Observed:** Selected option is filled black; its white companion shares the seam and has black text with outer black edges. Usually aligned to the upper right of a data block.

**States:** Declared: hover on the unselected option uses color-mix(in srgb,#000000 10%,transparent); focus-visible 2px solid #3451ff outline with 2px offset.

### Carousel arrow

**Only for:** media and publication galleries

**Use:** Advance a horizontal media sequence.

**CSS:** `background: #000000; color: #ffffff; width: 44px; height: 44px; padding: 12px; display: flex; align-items: center; justify-content: center; border-radius: 0px`

**Observed:** A 16px white chevron is centered. Paired previous control becomes visibly subdued at the start; controls sit at the right below media, separated by 16px.

**States:** Declared: hover opacity 0.85; focus-visible 2px solid #3a8fbd outline with 2px offset.

### Compact statistic

**Only for:** technical product sections

**Use:** Small group of quantitative facts below a product view.

**CSS:** `display: flex; flex-direction: column; gap: 4px; border-left: 1px solid #e2e2e2; padding-left: 16px`

**Text style:** `stat` — nhgText 700 · 36px/1.1 · tracking -0.01em

**Observed:** Bold value above a regular descriptive label. Four-column grid uses 32px gaps; values retain units inline.

**Transfer:** Use measured, meaningful facts, not decorative counters.

### Media tile

**Only for:** media-rich product pages

**Use:** Video proof and capability material.

**CSS:** `display: flex; flex-direction: column; gap: 16px`

**Text style:** `media-title` — nhgText 700 · 24px/1.2 · tracking -0.01em

**Observed:** A square-edged 411px by 231px thumbnail sits above a bold title. Video variants place a small black play square over the image. Capability variants use square photographs and a regular gray paragraph below.

**Transfer:** Keep imagery documentary and titles descriptive; do not wrap the tile in a colored card.

### Milestone card

**Only for:** company history

**Use:** Dated evidence of progress.

**CSS:** `background: #ffffff; border: 1px solid #e2e2e2; padding: 24px; display: flex; flex-direction: column; gap: 24px; border-radius: 0px`

**Text style:** `milestone-title` — nhgText 600 · 24px/1.25

**Observed:** Landscape image first, then a prominent tabular date, event title, gray body and compact read/watch link with a small arrow or play icon. Cards alternate around a fine center line on black.

**Transfer:** Use genuine dated proof and let card height follow content.

### Portrait overlay

**Only for:** people directories

**Use:** Identify a person over a portrait.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.7)); padding: 16px 20px; display: flex; justify-content: space-between; align-items: flex-end; gap: 12px; position: absolute`

**Text style:** `portrait-name` — nhgText 700 · 18px/1.3

**Observed:** At the bottom of a grayscale 270px by 324px portrait, white name and smaller role sit left; a light plus glyph in a 32px action area sits right.

**Transfer:** Use the portrait-role recipe for the secondary line; keep the person's face unobscured.

### Film action

**Only for:** demonstration openings

**Use:** Prominent watch action over cinematic imagery.

**CSS:** `display: flex; align-items: center; gap: 12px; color: #ffffff`

**Text style:** `film-action` — nhgText 700 · 43.2px/1 · tracking -0.02em

**Observed:** Bold unboxed sentence with a larger right-arrow glyph, aligned to the lower-right edge of the opening text strip.

**States:** Declared: hover opacity 0.7; focus-visible 2px solid white outline with 4px offset and opacity 0.8; active opacity 0.7.

## Imagery and graphics

### Cinematic environmental product

**Use:** Opening and large visual release between textual chapters.

**Observed:** A pale physical product occupies most of the width against blue sky, clouds, terrain or a runway. Light feels photographic, materials retain soft reflections and shadow, and the horizon provides scale. The opening is full-bleed; later media often uses a 16:9 field. Warm sunset color belongs to demonstration imagery, not interface chrome.

**Transfer:** Photograph or render a new object in a believable operating environment with substantial open atmosphere. For software, show a real use environment and one clear physical or screen focal point rather than many floating UI panels.

### Monumental type and object

**Use:** Signature brand-scale graphic on every new landing page.

**Observed:** Huge white product lettering spans almost edge to edge over a violet-gray-to-white stage. An isolated top-down object overlaps the lettering in front, centered and nearly full width, with pale silver surfaces and fine dark detail. The type remains readable as a shape even when partially occluded.

**Transfer:** Choose a short product identifier or category word. Put a clean cutout or high-quality silhouette of the new product in front; when no 3D asset exists, use a carefully lit cutout photograph or a simplified orthographic SVG with modest tonal shading.

**Build:** Create a full-width relative stage with linear-gradient(#716e85 0px, #ffffff 65%). Place the white identifier on a sticky centered layer using monument typography, 48px vertical inset, then layer the isolated product above it on the center axis. Keep the product's broadest dimension close to the stage width. Use subtle internal silver-gray gradients on an SVG fallback, not an external glow or drop shadow.

### Orthographic benefit views

**Use:** Concise benefit comparisons and specification sections.

**Observed:** Front and side product profiles are isolated on white, softly shaded and given no decorative frame. The object sits in one equal column beside a short black title and gray sentence; a larger profile can span the full content width.

**Transfer:** Use consistent scale and lighting across two diagnostic views; a clean product detail or cutaway is preferable to unrelated stock imagery.

### Documentary process photography

**Only for:** capability, facility and history pages

**Use:** Demonstrate that the product is engineered and built.

**Observed:** Real workshops, test equipment, structural details, working people and operational locations appear in square or landscape fields with straight edges. Color is natural and generally muted, retaining local workshop lighting.

**Transfer:** Show specific work, tools and stages of validation. Avoid generic office lifestyle images.

### Analytical diagrams

**Only for:** technical product and rationale pages

**Use:** Explain comparisons, reach and structural opportunities.

**Observed:** Flat diagrams sit directly on pale gray bands: gray and deep blue stacked bars, desaturated maps with translucent blue coverage circles, and black schematic pictograms. Labels are compact and factual, without decorative legends or glossy chart effects.

**Transfer:** Translate real data into a simple flat diagram. Keep axes and sourcing subordinate to one clear comparison.

**Build:** Use SVG rectangles for stacked comparisons at 32px height, with #888b8d, #e2e2e2, #2f343d and #001489 segments. For reach diagrams, use a low-contrast geographic outline with overlapping circles filled rgba(0,20,137,0.18) and thin blue strokes; place small black labels at centers. For non-geographic subjects, reuse the same circle-and-label logic for coverage or capacity.

### People imagery

**Only for:** company and people pages

**Use:** Human introduction and leadership directories.

**Observed:** The opening collage is a dense edge-to-edge matrix of naturally colored, consistently framed portraits. Leadership uses separate grayscale chest-up portraits on light backgrounds with dark foot gradients and white labels.

**Transfer:** Keep the collage and leadership treatments distinct; use consistent eye height and framing within each group.

### Icons

**Observed:** Small functional arrows and chevrons use 14px–16px forms, 1.5px rounded strokes and black or white paint. Social symbols are solid white at 20px in the footer. Play symbols sit in black squares; portrait disclosure uses a thin plus.

**Transfer:** Choose a restrained line icon set for actions and solid brand-neutral social marks. Avoid large decorative feature icons.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** The first 900px is one edge-to-edge media stage beneath an 80px white Navigation bar. A pale product spans roughly four fifths of the image width in the upper-middle field, surrounded by blue atmosphere. Behind the lower text, a transparent-to-black veil gradually resolves into the violet horizon tone. A two-line white display headline sits low left, using 129.6px size, line height 1 and -0.02em tracking; its block occupies about two thirds to four fifths of the width with an 80px content inset and 40px bottom inset. The image, headline and navigation are visible within the first screen. There is no support paragraph or CTA in the default opening; the monumental product stage begins below the fold.

**Transfer:** Lead with one clear product in an atmospheric environment and a short transformational promise. Without cinematic media, use a high-resolution photograph or restrained render with the same object-to-empty-space balance. Informational pages instead open with an 80px-padded white category-and-title block and a wide image below; demonstration pages use the smaller product-display headline with support and a Film action low in the scene.

**Avoid:** Do not turn the default opening into a centered text stack with two pill CTAs, or place the object inside a rounded inset card.

**Text style:** `display` — nhgDisplay 700 · 129.6px/1 · tracking -0.02em

### Monument stage

**Observed:** Horizon stage carries a near-full-width white identifier and an isolated product in front. Monument type is 489.6px/0.9, -0.04em tracking; its sticky centered layer gives way to the large top view as the background fades into white.

**Transfer:** Use the Monumental type and object device at a suitable point in the story; adapt the short word and silhouette to the new product.

### Benefit pairs

**Observed:** Editorial canvas holds two equal columns with a 64px gap. Isolated front and side views occupy the left; benefit titles and one gray sentence sit vertically centered on the right. Rows are 80px apart, inside 96px vertical section padding.

**Transfer:** Pair each diagnostic product view with one distinct customer consequence.

**Text style:** `benefit` — nhgText 700 · 40px/1.1 · tracking -0.01em

### Credibility field

**Observed:** A left-aligned heading and gray support line precede Credibility marks. The heading, support and grid use 48px vertical gaps; the white section uses 64px vertical padding. Marks have no visible card shells.

**Transfer:** Group proof by its function, using short explanatory prose and optically balanced marks.

**Text style:** `heading` — nhgText 700 · 50px/1.2

### Directory close

**Observed:** Directory footer is a substantial 685px black ending with three useful information columns. White reversed identity at bottom left and muted copyright at bottom right follow a full-width faint divider. There is no closing CTA headline.

**Transfer:** Allow the preceding section to finish its own narrative: it can be a proof grid, a final photograph, an analytical argument or a people directory. Then close with the same institutional footer.

### White editorial introduction

**Only for:** informational and technical detail pages

**Observed:** An 80px-padded white block below navigation contains a small blue eyebrow, a 56px bold title after 16px, and, when needed, a short gray support line. A full-width image strip follows: 360px high for product or rationale imagery, taller for a people collage.

**Transfer:** State the page's purpose plainly before a panoramic visual; do not force a cinematic hero onto every page type.

**Text style:** `page-title` — nhgDisplay 700 · 56px/1.1

### Product specifications

**Only for:** technical product pages

**Observed:** A left-aligned title and support introduce an isolated side profile. Two concise benefit paragraphs sit above it; a Unit switch and Compact statistic grid sit below. The grid is four columns with 32px gaps and subtle left rules.

**Transfer:** Give the product room before data. Present only comparable facts with clearly associated units.

### Media proof chapter

**Only for:** demonstration pages

**Observed:** A product-heading and one product-support line sit over a three-column Media tile row or a large 1280px by 720px gallery image. Gallery captions follow after 12px; small thumbnails and the Utility button sit below, with count and Carousel arrow controls at the right.

**Transfer:** Use real demonstrations and editorial captions to establish credibility rather than a decorative carousel.

### Backdrop pillars

**Only for:** rationale pages

**Observed:** A 720px industrial photograph is covered by Photo legibility veil. White headline sits at the upper left and three text columns sit near the lower edge; each has a faint top rule, a bold title and regular support. The section uses 96px vertical padding and 48px column gaps.

**Transfer:** Use this for a small set of causal mechanisms or principles, backed by a relevant process image.

### Analytical proof band

**Only for:** technical product and rationale pages

**Observed:** Analysis band holds a 36px heading and support, then either broad comparison bars, two maps with blue titles, or three schematic evidence columns. Source links sit beneath the illustration; concluding notes use fine top rules.

**Transfer:** Choose one visual grammar per argument and make the data explain a decision rather than merely decorate the page.

**Text style:** `technical-heading` — nhgText 700 · 36px/1.2

### Publication proof

**Only for:** rationale pages

**Observed:** Three tall Publication frames sit in a 24px-gap row, each with a small italic quote and uppercase publication attribution below. A compact paired navigation sits under the row.

**Transfer:** Use external proof that supports the argument, keeping the quotation much shorter than the document.

### History timeline

**Only for:** company history

**Observed:** A black band begins with a centered white heading. Milestone cards alternate left and right of a thin vertical axis in a 1200px container. Each is 552px wide with 24px inset; 16px white-centered, black-ringed markers have a white outer hairline. Cards are separated by 56px vertically.

**Transfer:** Show a curated progression of verified events; preserve the alternating rhythm without copying the original number of milestones.

### Portrait statement

**Only for:** demonstration pages

**Observed:** A black section with 120px vertical padding places a large natural portrait left and a bold white thesis right. Gray paragraphs, uppercase speaker name and attribution form a restrained endorsement, without oversized quotation marks.

**Transfer:** Use a responsible expert's statement to connect demonstrated capability with the broader product promise.

### Quantified bridge

**Only for:** demonstration-to-product closing sections

**Observed:** A white product-heading and support lead to a three-column, two-row grid with 48px column gaps. Gray uppercase labels sit above 97px bold values; an expansive environmental product image follows. The visual ends before the black directory begins.

**Transfer:** Bridge proof to the next offering with meaningful facts and a final image, not a generic sales CTA.

**Text style:** `stat-large` — nhgText 700 · 97px/1 · tracking -0.03em

### People directory

**Only for:** company pages

**Observed:** White sections return after the long dark history. Section titles precede four-column portrait grids, 270px by 324px per portrait, 24px column gaps and 32px row gaps. Portrait overlay identifies each person and provides a plus action.

**Transfer:** Separate executive and advisory groups when that distinction helps the reader.

## Page flow

**Storyline:** Transformational promise → tangible product → concise benefits → evidence at the appropriate depth → institutional directory.

### Broad brand and product landing

1. **Promise** — Cinematic full-width product scene and monumental low-left headline.
2. **Product identification** — Huge identifier with a top-down object crossing it on a fading horizon stage.
3. **Benefits** — Two isolated product views paired with short consequence-led statements.
4. **Demonstration** — Full-bleed operational media.
5. **Social proof** — Two open monochrome mark fields, each with an explanatory heading and paragraph.
6. **Ending** — Black directory with navigation, social links, address and bottom identity bar.

**Transfer:** Use the atmospheric-to-orthographic contrast as the core story, with proof appropriate to the new product.

### Detailed product evaluation

1. **Introduction** — White category label and direct title, then a panoramic product image.
2. **Value explanation** — Benefits, isolated profile, measurement controls and compact specifications.
3. **Quantified proof** — Stacked comparison graphics on gray.
4. **Applicability** — Two visual coverage examples on the same analytical backing.
5. **Visual conclusion** — Full-bleed product in an expansive landscape.
6. **Ending** — Common black directory.

**Transfer:** Move from practical value to data and real-world fit; preserve visual breathing room between arguments.

### Demonstrate a technical achievement and connect it to an offering

1. **Promise** — Cinematic sunset scene with headline, supporting claim and large watch action.
2. **Demonstration** — Video row, product scale, controlled performance facts and editorial photo gallery.
3. **Capability proof** — Five-column process grid showing the work behind the achievement.
4. **Interpretation** — Black portrait statement connects proof to a larger thesis.
5. **Product bridge** — Oversized six-fact grid and broad landscape image.
6. **Ending** — White space after the final contained image, then black directory.

**Transfer:** Use the demonstration-led variant when real evidence is the strongest opening asset, not for every landing page.

### Explain the rationale behind a product direction

1. **Thesis** — White editorial introduction and panoramic product image.
2. **Purpose** — Left heading beside longer gray explanatory prose.
3. **Mechanism** — Darkened process photograph with three causal pillars.
4. **External proof** — Publication imagery and small italic excerpts.
5. **Opportunity** — Three diagram-based arguments on gray.
6. **Stakes** — Final two-column text and sourced line chart.
7. **Ending** — Black directory directly after the analytical conclusion.

**Transfer:** Use evidence to support an ambitious thesis without adding a forced conversion panel.

### Establish organizational substance

1. **Human introduction** — White heading over an edge-to-edge portrait collage.
2. **Orientation** — Who, what and how statements arranged as heading/prose splits.
3. **Operational proof** — Three facility photographs with names and locations.
4. **Track record** — Long black timeline with alternating dated white cards.
5. **Accountability** — White leadership and board portrait directories with disclosure controls.
6. **Ending** — Final partial portrait row gives way to the common black directory.

**Transfer:** Adapt the history depth to meaningful milestones; organization pages can be much longer and denser than landing pages.

## Writing

Confident, engineering-led and economically grounded. Ambition is expressed through concrete changes to an established system, then supported with physical evidence, mechanisms and numbers.

**Do not copy:** Do not reuse Heart Aerospace names, marks, aircraft identifiers, partner logos, proprietary imagery, quotations, performance numbers, dates, funding totals or claims. Source examples illustrate voice only.

- **Addressing the reader:** Mostly impersonal product statements or first-person plural for purpose; very little direct second-person address. Product names recur instead of conversational nicknames.
- **Rhythm:** Short declarative headings, often with a period, followed by one economical supporting sentence. Longer rationale sections use complete factual paragraphs; no exclamations or rhetorical question chains.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A concrete transformation expressed as an active promise. | 4–8 words | “Electrifying regional air travel”<br>“The future of flight takes off.” |
| Editorial title | Name the purpose or introduce the subject directly. | 3–13 words | “Introducing the ES-36.”<br>“We use technology to reduce the cost of air travel.” |
| Benefit support | One consequence, not a list of adjectives. | 6–18 words | “A fundamentally lower-cost model for aviation.” |
| Technical heading | A quantified result or clear evaluative frame. | 5–10 words | “Cutting regional aircraft operating costs by 40+%” |
| Action | Verb plus a specific artifact or event; informational rather than urgent. | 2–6 words | “Watch the first flight.”<br>“Read article”<br>“Download Press Kit” |

**Words and phrasing to use:** designed to; lower-cost; full-scale; validated; operating; systems; first principles; entry into service; demonstration; technology

**Avoid:** magical; game-changing; supercharge; unlock your potential; revolutionary solution; hurry; limited-time

**Rules:**

- Tie aspirational statements to a specific mechanism or observable proof nearby.
- Use numbers only when they are defensible and keep units explicit.
- Keep technical vocabulary precise but explain its consequence in ordinary language.
- Prefer a short noun label for an interface control and a plain sentence for a narrative action.

## Do's and Don'ts

### Do

- Keep the default opening headline at weight 700 with line height 1 and -0.02em tracking.
- Use the monumental identifier as a layered graphic with -0.04em tracking, not as another ordinary heading.
- Keep editorial content centered within 1280px and preserve the 64px two-column gap.
- Use 18px gray body copy and 50px bold section headings as the default editorial relationship.
- Balance credibility marks in open 400px by 140px cells with 40px gaps.
- Use straight-edged 44px controls and crisp 1px rules for functional structure.
- Let photographs carry warm or saturated hues while interface accents remain deep blue and sparse.
- Close with 64px-padded black institutional navigation and a faint bottom divider.

### Don't

- Do not use soft shadows to elevate ordinary cards; depth comes from photographs and overlap.
- Do not make blue a large CTA band or a repeated colored card fill.
- Do not round video thumbnails, portrait tiles or specification controls.
- Do not replace isolated product profiles with unrelated lifestyle illustrations.
- Do not style technical labels as colorful chips; use compact text and fine rules.
- Do not make all headings uppercase; capitals belong mainly to small labels and technical metadata.
- Do not turn the monochrome credibility field into a dense colored-logo ticker.
- Do not import the company timeline's long dark treatment into every ordinary landing page.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares transform 0.3s; header backing and border declare 0.2s color transitions.
- Navigation links declare opacity 0.15s; utility and gallery controls declare opacity 0.18s; footer links declare color 0.2s.
- Milestone cards declare transform 0.24s. The monumental identifier uses a sticky layer while the product moves through a long stage.

**Transfer:**

- Keep interactions subdued: opacity and color changes should not compete with cinematic media.
- Preserve the layered scroll relationship between monumental lettering and the isolated product rather than adding unrelated motion to every section.

**Unknown:**

- Exact scroll-linked animation timing and interpolation are not established.
- Playback behavior, reduced-motion treatment and the complete header hide/reveal trigger are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 320px, 375px, 425px, 430px, 767px, 768px, 1023px, 1024px, 1025px, 1280px and 1440px.
- Demonstration headline, chapter title, support copy and film action use the clamp formulas listed with their typography recipes.
- Credibility marks use auto-fit with 350px minimum columns. Benefit titles use a clamp formula.

**Transfer:**

- Recommended: preserve the product silhouette and low-left headline hierarchy when recropping the opening for narrow screens.
- Recommended: scale monumental text to the available width so its short identifier still reads as scenery; stack image and benefit text rather than compressing both columns.
- Recommended: collapse the footer into readable groups while retaining its distinct bottom identity bar.

**Unknown:**

- Mobile navigation structure, exact grid-collapse rules and mobile opening heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
