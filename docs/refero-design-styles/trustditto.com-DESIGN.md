# Ditto — serious work, playful beads

## Overview

An optimistic editorial style for products that make complicated work feel more human. Pale green paper and inky purple text carry expressive regular-weight serif headlines, while lemon yellow, blue, pink and green punctuate the light canvas. Rounded illustrations, monochrome portraits and carefully staged interface scenes make the pages approachable without losing their businesslike clarity. Spacious sections alternate with compact, useful proof and comparison content.

### Essentials

- Editorial promises on a bright split stage: a yellow text panel takes 46% of the opening beside oversized white, ink-outlined art panels; the headline is 48px regular serif with 1.14 line height and -0.01em tracking.
- Colour behaves like tangible pieces, not ambient light: yellow #ffe228 anchors actions and occasional whole bands; pink #e261e5, green #59e25d and blue #3a93ff stay concentrated in media, portraits and overlapping bead graphics against a mostly #eff2e5 canvas.
- A chain of overlapping rounded shapes is the signature connective device: circles, capsules and rounded diamonds overlap with multiply blending, appearing as a large curved strand or a full-width ribbon. Rebuild it with CSS or SVG when no product artwork exists.
- Friendly typography stays sharp rather than quaint: Hedvig Letters Serif 400 leads at 46.1px/1.14 with -0.01em tracking; Inter 16px/1.6 supports it, and 14px/1.5 uppercase eyebrows use 0.1em tracking.
- Actions are compact lozenges rather than rectangular controls: 48px-high pills, 12px 22px padding, dark ink for the main page action and yellow for the navigation action.
- Pictures are staged like collectible cards: thin ink outlines, 16px–28px corners, bright flat backgrounds, and black-and-white people. Large illustrated scenes use cyan skies, pink terrain and yellow-green planting rather than subdued stock-photo colour.
- The finish stays light and useful: an expansive serif closing invitation, a colourful chain motif, then a pale newsletter capsule and fine-rule footer. The closing headline grows to 63.4px at desktop while footer columns use 13px uppercase labels.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Aubergine ink | `#130e30` | `--color-ink` | text, border, action | Primary text, key outlines and dark action fills. |
| Lemon yellow | `#ffe228` | `--color-yellow` | accent, background, action | Opening text panel, announcement strip, proof bands and selected controls. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orchid | `#e261e5` | `--color-pink` | accent, background | Rounded bead pieces and vivid media backings. |
| Spring green | `#59e25d` | `--color-green` | accent, background | Bead pieces, portrait backings and media panels. |
| Clear blue | `#3a93ff` | `--color-blue` | accent, background | Bead pieces and media backings; also editorial link hover decoration. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text | Art panels, interface stages, proof strips and hover lettering. |
| Light panel | `#f9fbf2` | `--color-panel` | surface | Light secondary panels and plan surfaces. |
| Light demonstration ground | `#f7f9f0` | `--color-demo-ground` | background | Near-white green ground distinguishing a process demonstration. |
| Pale green paper | `#eff2e5` | `--color-canvas` | background, text | Default page ground and reversed button lettering. |
| Olive paper band | `#e9ebd9` | `--color-band` | background | Contrast bands behind comparisons and audience proof. |
| Sage card | `#e8ebd9` | `--color-card` | surface, background | Newsletter capsule and editorial card backgrounds; also listing and article opening bands. |
| Olive hairline | `#d9ddbc` | `--color-rule` | border | Subtle separators, FAQ rules and light card borders. |
| Olive edge | `#b6ba95` | `--color-olive` | border | Newsletter lower edge and pricing rules; pricing uses rgba(182,186,149,0.35). |
| Secondary grey-purple | `#5f5c6e` | `--color-secondary` | text | Pricing explanations and secondary article credits. |
| Muted purple | `#4a4660` | `--color-muted` | text | Body support, eyebrows and footer headings. |
| Action black | `#000000` | `--color-black` | border, action | Dark button edge and declared button hover fill. |

## Typography

- **Hedvig Letters Serif** — Promises, section headings, quotes, major numbers and short names. Literary, open serif with lively details; mostly regular rather than bold. Font stack: "Hedvig Letters Serif", Georgia, 'Times New Roman', serif.
- **Inter** — Body, navigation, actions, labels and interface text. Clear compact grotesk, usually regular with slightly negative tracking. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing | Hedvig Letters Serif | 400 | 63.4px | 1.08 | -0.01em | size clamp(44px, 4.4vw, 64px) | Large centred closing invitation. |
| display | Hedvig Letters Serif | 400 | 48px | 1.14 | -0.01em | fixed | Default split-opening headline, broken into short sentence-like statements. |
| heading | Hedvig Letters Serif | 400 | 46.1px | 1.14 | -0.01em | fixed | Default marketing section heading. |
| stat | Hedvig Letters Serif | 400 | 43.2px | 1 | normal | fixed | Large outcome metrics, with small explanatory captions. |
| quote | Hedvig Letters Serif | 400 | 34px | 1.26 | -0.01em | fixed | Prominent quotation in a yellow proof band. |
| proof-number | Hedvig Letters Serif | 400 | 34px | 1 | normal | fixed | Compact aggregate proof and rating numbers. |
| tagline | Hedvig Letters Serif | 400 | 22px | 1.2 | normal | fixed | Footer positioning line. |
| closing-support | Inter | 400 | 18px | 1.55 | -0.02em | fixed | Centred closing support paragraph. |
| body | Inter | 400 | 16px | 1.6 | -0.02em | fixed | Marketing explanatory paragraphs. |
| compact | Inter | 400 | 16px | 1.25 | -0.02em | fixed | Navigation, main action lettering and compact card summaries. |
| action-medium | Inter | 500 | 16px | 1.25 | -0.02em | fixed | Navigation conversion action. |
| label | Inter | 600 | 16px | 1.25 | -0.02em | fixed | Newsletter prompt and bold category labels. |
| question | Inter | 400 | 16px | 1.4 | -0.02em | fixed | Default FAQ questions and short checklist lines. |
| eyebrow | Inter | 600 | 14px | 1.5 | 0.1em, uppercase | fixed | Section labels, separated from serif headings by 16px–18px. |
| small | Inter | 400 | 14px | 1.5 | normal | fixed | Footer links and dense feature lists. |
| footer-heading | Inter | 600 | 13px | 1.5 | 0.1em, uppercase | fixed | Footer column titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| story index and manifesto openings, and secondary-page closing calls | editorial-display | Hedvig Letters Serif | 400 | 64px | 1.1 | -0.01em | fixed | Centred statement heading. |
| articles, manifesto sections and pricing openings | editorial-heading | Hedvig Letters Serif | 400 | 48px | 1.15 | -0.01em | fixed | Longer editorial chapter and split-story headings. |
| editorial cards and article subheadings | card-heading | Hedvig Letters Serif | 400 | 32px | 1.2 | -0.01em | fixed | Two-line story titles, pull quotes and article subsections. |
| pricing pages | plan-name | Hedvig Letters Serif | 700 | 28px | 1.1 | normal | fixed | Compact bold names within plan cards. |
| editorial and pricing introductions | lead | Inter | 400 | 22px | 1.25 | -0.02em | fixed | Short introduction under the headline. |
| long-form articles | article-body | Inter | 400 | 22px | 1.45 | -0.0145em | fixed | Long reading paragraphs with 16px paragraph spacing. |
| pricing pages | plan-description | Inter | 400 | 15px | 1.25 | -0.021em | fixed | Short plan summary. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use regular serif as the principal expressive voice; reserve bold serif for plan names.
- Serif headings generally use -0.01em tracking; uppercase sans labels move the opposite way to 0.1em.
- Keep compact text and paragraph recipes distinct: the same 16px Inter becomes 1.25 for controls and card summaries, but 1.6 for explanatory paragraphs.
- Default section headings remain slightly smaller than the opening; large centred editorial statements are a separate variant, not the universal hero size.

## Layout

**Density:** Airy at section level, compact inside cards and controls; long pages alternate spacious storytelling with useful dense proof.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon gaps and stacked selector gaps. |
| 12px | Card title-to-summary gaps and tight control padding. |
| 16px | Eyebrow-to-heading gap and compact grid gutters. |
| 20px | Portrait gutters and footer column gaps. |
| 24px | Editorial card padding and opening paragraph/action separation. |
| 28px | Closing content gaps and quote-card padding rhythm. |
| 32px | Section heading-to-content gap and newsletter horizontal gap. |
| 48px | Global side padding, editorial grid gutters and large split-content gaps. |
| 80px | Default section top and bottom padding. |
| 96px | Editorial section breathing room and secondary-page closing padding. |

### Containers and grids

- **container**: max width 1280px · side padding 48px. Centred desktop content inside full-width bands; at 1440px its edges sit 80px from the viewport.
- **heading measure**: max width 760px. Section heading and introductory copy remain narrower than the content grid.
- **closing measure**: max width 1000px. Centred closing stack, with support text held to 640px.
- **capability grid**: 3 columns · gap 16px. Landscape-led cards spanning the main container.
- **people grid**: 4 columns · gap 20px. Equal portrait columns with names and short biographies below images.
- **tool grid**: 4 columns · gap 24px. Tall media-led capability tiles; remaining cards continue on another row.
- **faq measure**: max width 720px. Centred, left-aligned question list; pricing uses a wider 880px version.
- **footer grid**: 5 columns · gap 20px. Five equal 240px desktop navigation columns.
- **editorial grid** (only for story indexes and related resources): 3 columns · gap 48px. Equal sage cards after one full-width featured story.
- **article split** (only for long-form articles): max width 1280px · gap 48px. 932px main reading area beside a 300px sidebar containing contents and a resource promotion.
- **plan grid** (only for pricing pages): 4 columns · gap 16px. Four equal 308px plan cards across the main container.

## Corner radius

| Element | Radius |
| --- | --- |
| action pills | 9999px (pill) |
| editorial cards and large panels | 24px |
| capability cards | 16px |
| portrait frames | 20px |
| opening art panels | 28px |
| tool tiles and selectors | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | navigation | `rgba(19, 14, 48, 0.07) 0px 2px 10px 0px` | Soft separation beneath the sticky navigation. |
|  | demonstration stage | `rgba(64, 58, 45, 0.16) 0px 24px 56px 0px, rgba(64, 58, 45, 0.08) 0px 4px 12px 0px` | Raise a white interface example above a pale panel. |
| pricing pages | featured plan | `rgba(60, 50, 20, 0.28) 0px 24px 64px -28px` | Soft concentrated elevation beneath the recommended plan. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #eff2e5; color: #130e30`

#### Olive band · level 0

**Use:** Alternate section ground for audience proof and before/after comparisons.

**CSS:** `background: #e9ebd9`

**Observed:** Runs edge-to-edge without framing the whole section as a card.

**Transfer:** Use to distinguish a chapter while retaining the light-paper feeling.

#### Yellow band · level 0

**Use:** Opening promise panel and high-energy testimonial or resource moments.

**CSS:** `background: #ffe228; color: #130e30`

**Observed:** Colour carries the emphasis without gradients or texture.

**Transfer:** Reserve broad yellow for a few decisive moments, leaving most of the page pale.

#### Demonstration ground · level 0

**Use:** Process explanation chapter.

**CSS:** `background: #f7f9f0`

#### Outlined panel · level 1

**Use:** Large pale panel housing explanatory text and a product scene.

**CSS:** `background: #eff2e5; border: 1px solid #d9ddbc; border-radius: 24px; padding: 28px 30px`

#### White demonstration · level 2

**Use:** Readable product example within a larger pale panel.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: rgba(64, 58, 45, 0.16) 0px 24px 56px 0px, rgba(64, 58, 45, 0.08) 0px 4px 12px 0px`

**Observed:** A larger white interface slab floats above the pale backing; its internals remain subordinate to the marketing headline.

**Transfer:** Show only enough authentic interface to make one task understandable.

#### Proof strip · level 0

**Use:** Compact logos and aggregate metrics.

**CSS:** `background: #ffffff; border-top: 1px solid #d9ddbc; border-bottom: 1px solid #d9ddbc; padding: 24px 48px`

#### Frosted interface overlay · level 3

**Only for:** product demonstrations

**Use:** Small status and metric overlays on photography.

**CSS:** `background: rgba(255,255,255,0.7); border: 1px solid rgba(255,255,255,0.75); border-radius: 14px; backdrop-filter: blur(14px) saturate(1.3); box-shadow: rgba(27, 36, 44, 0.14) 0px 4px 14px 0px`

**Observed:** Translucency belongs inside the staged interface scene, not to page-wide navigation.

**Transfer:** Layer a few readable metrics over a photo, not a wall of glass.

#### Light plan · level 1

**Only for:** pricing pages

**Use:** Ordinary plan surfaces.

**CSS:** `background: #f9fbf2; border: 1px solid rgba(182,186,149,0.35); border-radius: 24px`

## Components

### Navigation

**Use:** Persistent main navigation.

**CSS:** `position: sticky; top: 0px; z-index: 100; height: 80px; background: #eff2e5; box-shadow: rgba(19, 14, 48, 0.07) 0px 2px 10px 0px`

**Text style:** `compact` — Inter 400 · 16px/1.25 · tracking -0.02em

**Observed:** Logo left, compact centred navigation with small downward chevrons, language globe and login to the right, then Yellow button. A 42px yellow announcement strip precedes it; the navigation remains at the top during reading.

### Primary button

**Use:** Main conversion in opening and closing content.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 12px 22px; background: #130e30; color: #eff2e5; border: 2px solid #000000; border-radius: 9999px; box-sizing: border-box`

**Text style:** `compact` — Inter 400 · 16px/1.25 · tracking -0.02em

**Observed:** Short text-only dark pill, usually isolated below explanatory copy.

**States:** Declared: hover background and border black, text white, outline 0px; focus-visible unknown; active outline 0px.

### Yellow button

**Use:** Navigation conversion and secondary content actions.

**CSS:** `height: 48px; padding: 12px 22px; background: #ffe228; color: #130e30; border: 2px solid #ffe228; border-radius: 9999px; box-sizing: border-box`

**Text style:** `action-medium` — Inter 500 · 16px/1.25 · tracking -0.02em

**Observed:** Navigation uses medium lettering; content versions use regular lettering. Content labels may lead to stories, alternate capabilities or resources.

**States:** Declared: hover navigation variant becomes black with white text and black border; focus-visible unknown; active outline 0px. Content variant hover uses #efd624 with ink lettering.

### Opening art panel

**Use:** Oversized graphic cards beside the opening promise.

**CSS:** `width: 544px; height: 696px; background: #ffffff; border: 1.5px solid #130e30; border-radius: 28px; overflow: hidden`

**Observed:** A row extends beyond the viewport, with one main card and a partial next card; an identifying label sits near the top and overlapping rounded shapes curve through the interior.

**Transfer:** Use a short category label plus a bead construction describing connection, progress or reuse. Preserve the oversized framing rather than filling it with dense dashboard details.

### Capability card

**Use:** Browsable illustrated entry points.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid #130e30; border-radius: 16px; overflow: hidden`

**Text style:** `eyebrow` — Inter 600 · 14px/1.5 · tracking 0.1em · uppercase

**Observed:** Landscape art occupies a 414px by 207px upper area. A white lower area has a top ink rule, an uppercase label with right arrow and a short muted 14px support line. A white logo capsule is centred over the picture.

**Transfer:** Use distinct coloured environments for each capability while maintaining the same art framing.

### FAQ row

**Use:** Lightweight objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; padding: 17px 0px; border-top: 1px solid #d9ddbc; color: #130e30`

**Text style:** `question` — Inter 400 · 16px/1.4 · tracking -0.02em

**Observed:** Full-width question with a small chevron at the far right; the list is 720px wide. Pricing uses an 880px list, 17px semibold questions, 20px vertical padding and plus signs; answers use Body text.

**Transfer:** Keep the control a ruled row on the page ground, not a separate rounded tile.

### Newsletter capsule

**Use:** Useful low-pressure conversion before footer links.

**CSS:** `display: flex; align-items: center; gap: 32px; padding: 12px 20px 12px 32px; background: #e8ebd9; border-radius: 9999px; max-width: 947px`

**Text style:** `label` — Inter 600 · 16px/1.25 · tracking -0.02em

**Observed:** Prompt left and white email capsule right. The white wrapper is 396px by 56px with 4px inset padding and a fine olive bottom edge; an input and dark Subscribe pill share the same capsule.

**Transfer:** Offer useful material in concrete nouns rather than a generic newsletter pitch.

### Footer columns

**Use:** Comprehensive, restrained site ending.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); gap: 20px; padding-top: 24px; border-top: 1px solid #d9ddbc`

**Text style:** `small` — Inter 400 · 14px/1.5

**Observed:** Uppercase Footer-heading labels, followed by compact links with 6px gaps. Below another fine rule: logo and serif Tagline left, rating and accreditation marks right, social circles, then a final small legal row.

**Transfer:** Preserve the five-column desktop rhythm, practical link density and light ground even for a shorter site.

### Audience selector

**Use:** Switch between audience-specific proof stories.

**CSS:** `display: flex; background: #ffffff; border: 1px solid #d9ddbc; border-radius: 12px; overflow: hidden`

**Observed:** A vertical stack of 53px-high rows with 8px gaps; line icon left, serif 18px label, and a separate arrow segment for the active row. Active row is yellow with an ink border. The adjacent large card pairs a colourful illustration with a yellow quotation panel.

**States:** Declared: hover background transitions over 180ms; focus-visible inset 0 0 0 2px #130e30.

**Transfer:** Use buyer roles, workflows or sectors only when the proof changes meaningfully.

### Outcome metrics

**Use:** Prominent measurable proof alongside a customer account.

**CSS:** `border-top: 1px solid #d9ddbc; border-bottom: 1px solid #d9ddbc; padding: 22px 0px`

**Text style:** `stat` — Hedvig Letters Serif 400 · 43.2px/1

**Observed:** Two large serif metrics sit side by side, separated by a hairline, with small muted captions below. A white 24px-radius quote card follows; the adjacent illustrated timeline has white numeric milestone cards on a thin ink axis with yellow nodes.

**Transfer:** Pair verified quantities with plain-language units and context instead of decorative percentages.

### Story card

**Only for:** editorial indexes and related resources

**Use:** Linked customer or resource summaries.

**CSS:** `display: flex; flex-direction: column; background: #e8ebd9; border-radius: 24px; padding: 24px; max-width: 416px`

**Text style:** `card-heading` — Hedvig Letters Serif 400 · 32px/1.2 · tracking -0.01em

**Observed:** Rounded 347px by 231px artwork, then a bold dot-led category, 24px below the image. Title and compact summary follow with 12px gaps; title is limited to two lines, summary to three. The featured version spans the grid, uses yellow, and places text left of a large outlined image.

**States:** Declared: hover background #ffe228; focus-visible unknown; active outline 0px.

**Transfer:** Use a specific transformation as the title; keep summaries concise enough to scan across a row.

### Plan card

**Only for:** pricing pages

**Use:** Compare service depth before the detailed matrix.

**CSS:** `display: flex; flex-direction: column; background: #f9fbf2; border: 1px solid rgba(182,186,149,0.35); border-radius: 24px; padding: 28px 24px`

**Text style:** `plan-name` — Hedvig Letters Serif 700 · 28px/1.1

**Observed:** Name and small scope pill share the top line, followed by a short bold promise and muted Plan-description. A thin divider introduces checkmarked features. The recommended plan uses canvas fill, 2px ink border, a soft shadow and a small yellow badge crossing the upper edge. Pricing is requested through a single action above the grid rather than repeated price numerals.

**Transfer:** Express increasing responsibility or scale; do not add four competing conversion buttons if one shared quote action suffices.

## Imagery and graphics

### Bead chain

**Use:** Signature connecting graphic in the opening and as a full-width punctuation band.

**Observed:** Flat lemon, orchid, green and blue circles and rounded capsules touch and overlap, producing darker mixed-colour intersections. The opening strand curves through a white outlined card; the horizontal band runs beyond both viewport edges.

**Transfer:** Always retain this tangible rounded-shape language. When there is no equivalent media, construct a simple bead strand rather than substituting generic abstract gradients.

**Build:** In an isolated SVG or CSS layer, alternate circles and capsules in #ffe228, #e261e5, #59e25d and #3a93ff. Use multiply blending for overlaps. Vary width and height roughly between 70px and 150px in an opening card; rotate a few capsules and include rounded diamonds. Overlap neighbours by about a quarter of their width, arranging centres along a broad arc. For a ribbon, use the same forms in a straight horizontal chain about 96px–147px high, clipped edge-to-edge. Keep fills crisp, with no blur or shadows.

### Chromatic landscape illustration

**Use:** Capability images, proof timelines and audience stories.

**Observed:** Detailed line-drawn landscapes and architecture: coastline, vineyards, wetland, forest river and bright glass interiors. Cyan skies and water meet pink rock, yellow ground and lime foliage; fine dark contour lines preserve structure. Images are vivid but not glossy, and are clipped into ink-outlined rounded frames.

**Transfer:** Commission or create a clean illustrated environment related to the new product. Minimum acceptable version is an original, flat vector landscape or interior with fine contours and the same cyan/pink/yellow/green colour balance.

**Build:** Construct a horizon and broad flat regions in SVG, add diagonal perspective lines or closely spaced contour strokes, then layered foliage or architectural planes. Use blue and green masses, yellow lit surfaces and pink secondary planes; keep the darkest lines thin. Back a short logo or topic label with a white capsule rather than drawing it directly on busy detail.

### Monochrome people on colour

**Use:** Human expertise and team introduction.

**Observed:** Four chest-up black-and-white cutout portraits on individual yellow, blue, pink and green backgrounds. Each image is approximately 303px by 357px, with a 20px rounded ink outline; names and factual biographies sit outside below.

**Transfer:** Use real people, consistent eye-level framing and grayscale cutouts against flat colour. Preserve warmth through expressions rather than adding filters over the entire card.

### Interface theatre

**Use:** Process demonstration and capability tiles.

**Observed:** A large white interface slab sits inside a pale rounded panel; smaller tall tiles alternate bright flat backings with candid workplace photography. Document stacks, progress chips and metric cards float in front. Photographic scenes stay natural while crisp UI carries the explanation.

**Transfer:** Stage one real workflow per scene. If no interface exists, use a simplified document, task list or chart with realistic labels; keep it readable and subordinate to the marketing copy.

### Overlapping logo fields

**Only for:** story indexes and customer article openings

**Use:** Consistent visual identity for varied customer stories.

**Observed:** A central white capsule holds a dark customer logo over two huge intersecting circles or rounded colour fields. Blue-green and yellow-pink pairings create darker overlap regions. Regular thumbnails are landscape format; the lead article uses a much larger outlined version.

**Transfer:** Replace customer logos with authorised marks or short project names; keep the abstract colour fields consistent across the collection.

**Build:** Clip a pale rectangle to 24px corners. Position two large circles or capsules partly outside opposite edges using the accent palette and multiply blending. Overlay a centred white pill around a dark mark; leave sufficient white padding for irregular logo proportions.

### Belief illustration and careers overlap

**Only for:** manifesto and culture pages

**Use:** Visualise values and invite team participation.

**Observed:** Alternating 600px-square illustrated scenes sit beside serif statements, backed by offset yellow and orchid rounded shapes. A separate careers composition overlaps a 449px square team photo with an enormous yellow capsule containing text; the photo has an 80px radius and ink outline.

**Transfer:** Use illustrated environments for ideas and a real team image for recruitment, preserving the overlapping physical-piece composition.

**Build:** Place two offset rounded rectangles behind a square illustration, partly hidden below and left, in yellow and orchid with multiply intersections. For recruitment, align a rounded square photograph in front of the left edge of a wide yellow pill and reserve the pill's right half for text.

### Icons

**Observed:** Small dark chevrons and arrows support navigation. Most utility icons are 16px–20px with rounded strokes around 1.8px–2px; feature checks are small, thin and green. Icons sit beside labels rather than inside oversized decorative badges.

**Transfer:** Use simple outlined utility symbols with round ends; retain solid arrows or chevrons for navigation and avoid bulky multicolour icon libraries.

## Section recipes

How recurring sections are built.

### First screen: Split promise and bead stage

**Observed:** A 42px yellow announcement strip precedes the 80px Navigation. The opening below is 756px tall with a 46:54 split: flat yellow copy panel left, pale canvas and sliding white Opening art panels right. The text aligns with the main 80px desktop inset and occupies about two fifths of the screen. A small uppercase Eyebrow precedes a 48px regular serif Display, formed from three short statements wrapping into about five lines; Body support follows after 24px, then a Primary button after another 24px. The art panels are 544px by 696px, inset vertically from the stage, with a curved Bead chain and a top label. The art lane clips at the viewport edge to reveal a partial next panel. Within the first 900px the announcement, navigation, headline, support, action and main artwork are all visible; only the top of the following proof strip appears.

**Transfer:** Lead with a practical promise in three connected statements and build a colourful bead scene around a category or outcome label when no artwork exists. Editorial indexes instead open with a centred 64px statement and filter capsule; case studies use a 48px split text-and-logo-field opening; manifesto pages use a centred 64px belief and chain ribbon; pricing uses a compact centred 48px title above plan cards.

**Avoid:** Do not replace the bright split with a centred SaaS headline over a small dashboard, or put a giant gradient slogan across both halves.

**Text style:** `display` — Hedvig Letters Serif 400 · 48px/1.14 · tracking -0.01em

### Eyebrow heading pair

**Observed:** Eyebrow above Heading with 16px–18px separation, support text roughly 14px–18px below; content begins about 32px later. Stack aligns left within a 760px measure, usually inside 80px section padding.

**Transfer:** Use the eyebrow to name the chapter and the serif headline to make a concrete claim, not repeat the category label.

**Text style:** `heading` — Hedvig Letters Serif 400 · 46.1px/1.14 · tracking -0.01em

### Human proof chapter

**Observed:** A two-column introduction puts the Heading and Body left and a white rounded checklist right. Four portrait columns follow with 20px gutters, names and short credentials below. A yellow testimonial band can pair the Quote recipe with an image and a white accreditation column.

**Transfer:** Explain the human service with real responsibilities and people, then support it with an attributed customer statement.

### Process demonstration

**Observed:** On Demonstration ground, a serif heading leads into a pale pill tab rail with numbered stages, active stage yellow. An Outlined panel below gives roughly 30% to a short explanation and 70% to White demonstration. Previous/Next pills sit beneath copy; small dots sit below the panel.

**Transfer:** Show a small number of meaningful tasks with one clear active stage. Keep the interface view simple enough to explain in one paragraph.

### Illustrated capability collection

**Observed:** Heading pair followed by a three-column Capability card grid with 16px gutters. Colourful landscape illustrations occupy the larger upper half of each card. A yellow action and quiet explanatory line follow below.

**Transfer:** Use the illustrations to make abstract categories memorable without forcing a literal product mockup into each tile.

### Before and after

**Observed:** An Olive band carries a Heading pair then two white 24px-radius panels with fine olive borders. Uppercase Before/After labels lead compact lists with small symbols and three statements per side.

**Transfer:** Contrast old effort with the new working pattern in parallel phrases, avoiding unsupported numerical claims.

### Tool theatre grid

**Observed:** Heading pair above a four-column grid with 24px gutters. Tall, approximately 302px by 378px media tiles contain photo/UI composites or vivid flat colour stages, followed by sans tool names and small muted descriptions.

**Transfer:** Choose a single useful action per tile and vary media backing while preserving tile dimensions.

### Quantified story

**Observed:** Two-column composition: narrative and Outcome metrics take the wider side, and a 470px by 590px illustrated timeline takes the other. A white rounded quotation card and yellow story action complete the narrative side. Milestone values use compact white cards over bright landscape art.

**Transfer:** Turn a verified before-and-after into a legible timeline; use real elapsed time and units, plus a small caveat where comparison depends on changing thresholds.

### Audience-specific proof

**Observed:** On Olive band, a Heading pair leads to a narrow stack of Audience selectors and a wide split illustration/quotation card. The selected row and quotation backing are yellow; an outlined all-audiences action aligns toward the lower right.

**Transfer:** Offer proof relevant to distinct buyers without multiplying landing pages unnecessarily.

### Ruled objections

**Observed:** A centred narrow chapter with Heading and FAQ rows on Canvas. The default list is 720px wide; pricing widens it to 880px and uses plus signs and a smaller serif heading.

**Transfer:** Use direct buyer questions; reveal answers without changing the overall restrained row construction.

### Closing invitation and useful ending

**Observed:** Default centred Closing heading, 640px support measure, Primary button and a secondary outlined story action under a fine rule. An edge-to-edge chain band punctuates the transition to the Newsletter capsule and Footer columns. Secondary-page closing calls instead arrange a 64px heading, 22px support and action across the container with the chain beneath, using 96px vertical padding. Story indexes finish directly with the newsletter/footer after the card grid rather than adding a full closing call.

**Transfer:** Use the chain as a distinctive connective mark and let the invitation answer the page's central promise. Keep the ending pale, readable and practical rather than switching to a dark conversion block.

**Text style:** `closing` — Hedvig Letters Serif 400 · 63.4px/1.08 · tracking -0.01em

### Editorial index

**Only for:** customer stories and resource collections

**Observed:** A sage opening band holds a centred Editorial-display heading, Lead text, and a white pill containing three dropdown filters. Below, one yellow featured story has text left and art right; the regular Story cards follow in a three-column grid with 48px gutters.

**Transfer:** Make one story the entry point and let the grid support browsing; filters should correspond to meaningful reader choices.

### Long-form case study

**Only for:** customer articles

**Observed:** Sage split opening with category label, Editorial-heading, Lead and a large outlined logo-field image; three pale summary cards follow for context, challenge and impact. Main chapters use dot-led labels, 48px serif headings, 32px subsections and 22px/1.45 text. A 300px sidebar holds contents and a yellow resource promotion. Inset pull quotes have yellow quote marks and a small portrait attribution. Yellow rounded calls interrupt and close the article.

**Transfer:** Organise around situation, constraints, method, outcomes and next steps. Keep the side rail secondary to long reading.

### Belief and culture narrative

**Only for:** manifesto and culture pages

**Observed:** Centred Editorial-display opening and chain band, then a centred chapter title and alternating square illustration/text splits. A large overlapping yellow recruitment capsule breaks the rhythm. A sage commitment carousel shows light cards with small logos, serif titles and sans copy, edge arrows and pill pagination; an investor introduction follows.

**Transfer:** Link beliefs to concrete practices and partnerships; let original illustrated scenes carry the emotional argument.

### Plans and comparison

**Only for:** pricing pages

**Observed:** Centred Editorial-heading and Lead, then one dark pricing action with a yellow circular arrow. Four Plan cards begin in the first screen. Below a 32px centred comparison title, a full-width matrix uses thin olive row rules, serif column names and a pale highlight down the recommended column. Small uppercase group labels separate feature families; checks and dashes make availability scannable.

**Transfer:** Present service depth first and detailed availability second, preserving the light table instead of building a heavy boxed spreadsheet.

## Page flow

**Storyline:** Practical promise → tangible demonstration and human reassurance → relevant proof → capabilities and outcomes → objections → invitation and useful footer.

### Full product marketing narrative

1. **Promise** — Split yellow statement beside oversized bead artwork.
2. **Social proof** — White logo and rating strip followed by named human experts.
3. **Method** — Numbered process demonstration and illustrated capability cards.
4. **Product breadth** — Before/after comparison and tall tool theatre tiles.
5. **Outcome proof** — Quantified story and audience-specific testimonials.
6. **Objection handling** — Narrow ruled FAQ.
7. **Closing call** — Large centred invitation, chain punctuation, newsletter and footer.

**Transfer:** Adapt the chapter sequence to the decision being made; alternate concrete mechanisms with proof rather than stacking feature claims.

### Browse a proof collection

1. **Proof promise** — Centred large statement and short introduction on sage.
2. **Selection** — White capsule of filters.
3. **Featured proof** — One wide yellow story.
4. **Proof library** — Three-column story-card collection.
5. **Useful ending** — Newsletter capsule and standard footer, without another large conversion section.

**Transfer:** Replace customer segments with meaningful resource taxonomy; preserve the featured-versus-grid hierarchy.

### Explain a customer transformation in depth

1. **Outcome promise** — Split long headline, introduction and logo-field art.
2. **Summary** — Three context/challenge/impact cards.
3. **Context and challenge** — Large editorial chapters with sidebar contents and attributed quotes.
4. **Method** — Numbered practical steps and a yellow resource call.
5. **Impact** — Specific results, follow-on benefits and another quote.
6. **Next step** — Future outlook and yellow conversion panel.
7. **Continued discovery** — Three related story cards, shared closing call, chain and standard footer.

**Transfer:** Use actual constraints and actions as the narrative substance, not a long sales testimonial.

### Express company beliefs and credibility

1. **Belief promise** — Centred statement with chain ribbon.
2. **Principles** — Alternating illustrated square scenes and short serif-led arguments.
3. **Participation** — Overlapping team photo and yellow recruitment capsule.
4. **Institutional proof** — Commitment carousel and investor introduction on sage.
5. **Closing call** — Shared invitation, chain, newsletter and footer.

**Transfer:** Make beliefs specific to how the organisation works, with visuals warmer than the prose.

### Help buyers choose the right engagement level

1. **Choice framing** — Centred title, support and one pricing request action.
2. **Plan overview** — Four compact cards with one recommended option.
3. **Comparison** — Fine-rule feature matrix with a highlighted column.
4. **Objection handling** — Wide FAQ rows with plus signs.
5. **Social proof** — Sage logo band and small rating.
6. **Closing call** — Shared invitation, chain, newsletter and footer.

**Transfer:** Sell the appropriate amount of support and scope before detailing feature differences.

## Writing

Practical, confident and reassuring, with warmth supplied by human help and concrete work. Complexity is acknowledged without making the reader feel behind.

**Do not copy:** Do not reuse Ditto's name, logo, proprietary artwork, customer identities, quotes, accreditation marks, ratings, performance numbers or product claims. Supply the new product's own authorised material and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we sparingly for beliefs and service commitments. Describe the product through actions and responsibility rather than abstract positioning.
- **Rhythm:** Short sentence-like headlines often use a three-part parallel rhythm. Body copy explains a mechanism then names the relief it creates; editorial stories can use longer factual paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Three short linked statements moving from reader ownership to assistance to compounding benefit. | Three statements, roughly 3–5 words each | “Your work, your evidence. Checked by your coach. Reused for every framework.” |
| Section headline | Contrast software's task with the human or business result. | Roughly 5–13 words | “Software gets you organised. Your coach gets you the medal.”<br>“Same effort the first time. Far less the second.” |
| Supporting line | Name the practical mechanism, then explain the repeated work it removes. | One or two sentences | “One evidence base for EcoVadis, CDP, VSME, ISO 14001, and your carbon footprint. So you stop answering the same questions twice.” |
| Primary action | Short invitation or concrete next step. | 2–4 words | “Let's talk”<br>“Get personalized pricing” |
| Proof title | Specific subject plus a visible transformation and timeframe. | About 10–18 words | “Niedax went from Bronze to Platinum EcoVadis in 2 years.” |
| Objection | Ask the plain buyer question, with no cleverness. | One direct question | “Can I start with one framework and add more later?” |

**Words and phrasing to use:** your work; your team; checked; reuse; together; one source; at your pace; what comes next; with an owner and a date

**Avoid:** revolutionary ecosystem; unparalleled excellence; seamless synergy; disrupt everything; effortless magic

**Rules:**

- Lead with the reader's workload or desired outcome rather than a category definition.
- Name who does the work, who checks it and who keeps control.
- Use contrast and parallel syntax to compress complex benefits.
- Quantify only when the quantity has context, units and a defensible basis.
- Use matter-of-fact explanations in long stories; keep headings more compressed than paragraphs.

## Do's and Don'ts

### Do

- Keep the default opening at a 46:54 text/art split with the yellow side carrying the promise.
- Use 48px regular serif for the opening and 46.1px for ordinary section headings.
- Let 80px vertical section padding create the narrative breathing room.
- Keep the main desktop container at 1280px with 48px outer padding.
- Use 1px ink frames for illustrated cards and quieter #d9ddbc rules for reading structure.
- Give portraits individual flat-colour backings and keep people in grayscale.
- Use 48px action pills and reserve the dark fill for decisive conversion.
- Keep a crisp overlapping-bead graphic as a recognisable connective device.

### Don't

- Do not turn the pale green canvas into white everywhere; it is the main visual atmosphere.
- Do not set the principal serif headlines in bold; the 700-weight serif belongs to plan names.
- Do not spread pink, blue and green over every section background; concentrate them within media and rounded art pieces.
- Do not add glow, grain or glossy gradients to the crisp flat beads.
- Do not apply glassmorphism to the whole navigation or footer; translucent panels belong inside product scenes.
- Do not replace the thin-rule pricing matrix with dark heavy grid boxes.
- Do not use square or slightly rounded rectangular buttons instead of full pills.
- Do not enlarge footer links to body-lead size; retain the compact 14px/1.5 link rhythm.

## Motion and responsive

### Motion

**Observed:**

- Main button backgrounds declare 0.2s ease-in-out transitions; story cards declare 0.25s ease-in-out.
- Audience controls declare background and border transitions of 180ms.
- The opening contains a horizontally translated art row, and process/sector content has explicit selection controls. Logo and testimonial scrolling, bead-related keyframes and a spinner are declared.

**Transfer:**

- Keep hover emphasis primarily a flat fill change, not a scale or glow effect.
- Use selected yellow tabs and visible progress dots to make changes of demonstration state understandable.

**Unknown:**

- Autoplay timing, exact bead trajectories, scroll triggers and carousel dwell times are not established.

### Responsive

**Observed:**

- CSS contains breakpoint families near 480px, 600px, 720px, 768px, 992px and 1024px.
- Some heading/content grids use auto-fit with minimum columns of 300px or 380px; footer columns auto-fit from 150px.
- The closing headline explicitly scales with clamp(44px, 4.4vw, 64px).

**Transfer:**

- On narrow screens, preserve the yellow copy block and a substantial readable bead panel by stacking them rather than shrinking the whole desktop stage.
- Collapse editorial and capability grids without reducing portraits or art into tiny thumbnails; keep dark outlines and rounded clipping.
- Retain the recommended pricing column's distinction when adapting the comparison to horizontal scrolling or grouped rows.

**Unknown:**

- Exact mobile navigation, art-panel dimensions and stacking order are not established; narrow-screen guidance is a design recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
