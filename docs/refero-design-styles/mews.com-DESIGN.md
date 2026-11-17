# Mews — notched panels, bold impact

## Overview

A punchy, people-friendly technology style that makes complex software feel tangible and commercially useful. Heavy grotesk capitals and warm conversational supporting text sit between crisp white space and substantial black chapters. Candy pink, icy blue and electric lime frame interface demonstrations, natural hospitality photography and compact proof graphics; the overall density is spacious at section level and practical inside cards.

### Essentials

- Headlines switch gears rather than simply shrink: the opening uses 48px/1.03 weight 900 capitals with -0.02em tracking, while chapter headings use 48px/1.1 weight 700 sentence case and -0.015em tracking.
- The first impression is a paired stage: two 627px-wide, 634px-high panels separated by 24px, with an 80px-padded black promise panel beside an oversized interface on a real-world photographic background.
- Panels have a bite taken out of their edge: small curved inward notches interrupt otherwise straight 6px-radius rectangles. Carry this device into the opening, selected feature panels and the bright newsletter strip; use SVG masks when no artwork exists.
- Color belongs to bounded objects, not a continuous pastel canvas: white and black dominate entire chapters; #ffc5ee, #d2f4ff and #e8ff5b back substantial demonstration cards, while #ff83da identifies compact actions and the newsletter band.
- Actions are small, confident pills: 40px high with 16px side padding, black 13px weight 700 uppercase text, 0.03em tracking and a fully rounded silhouette; outlined pills carry secondary actions.
- Interfaces act like physical objects: white UI with a dark rounded frame is enlarged beyond its panel edge or floated in fragments over flat color. Pair it with daylight photography, or use a simplified original interface with one unmistakable workflow when no product media exists.
- Proof and the farewell are graphic events: bottom-aligned colored statistic bars use 72px weight 900 numerals, and a black closing call uses a centered 96px/1 uppercase line above three numbered steps and a pink action. Preserve both devices with truthful new proof and an original closing promise.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Candy pink | `#ff83da` | `--color-action` | action, accent, surface, border | Primary actions, bright statistic bars, recommended-plan edges and newsletter strip. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft pink | `#ffc5ee` | `--color-pink` | surface, background | Large bounded demonstration panels, announcement band and lighter action hover. |
| Ice blue | `#d2f4ff` | `--color-blue` | surface | Demonstration backdrops and contained conversion panels. |
| Electric lime | `#e8ff5b` | `--color-lime` | surface, accent | High-energy proof cards, device backdrops and statistic bars. |
| Blush hover | `#f7e1f7` | `--color-hover-tint` | surface | Audience-card hover fill and some demonstration backdrops. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Default page canvas, interface framing and reversed type. |
| Warm question canvas | `#fffcf6` | `--color-cream` | background | Full-width FAQ chapter, distinct from white capability sections. |
| Cool card gray | `#f4f5f9` | `--color-card` | surface | Audience tiles, add-on panels and small badge backgrounds. |
| Section hairline | `#e6e6e6` | `--color-rule` | border | Visible black at 10% on white; separators use rgba(0,0,0,0.1), with reversed white-alpha rules on black. |
| Control edge | `#cccccc` | `--color-border` | border | Visible black at 20% on white; outlined pills and form edges use rgba(0,0,0,0.2). |
| Cool supporting gray | `#c4c9dd` | `--color-supporting` | text | Small category label within the black opening panel. |
| Open-row edge | `#8c8c8c` | `--color-active-rule` | border | Black at 45% on white; open FAQ rules use rgba(0,0,0,0.45). |
| Soft black text | `#333333` | `--color-body-muted` | text | Visible result of black at 80% on white; supporting copy uses rgba(0,0,0,0.8). |
| Charcoal | `#2d2c37` | `--color-charcoal` | surface | Dark proof cards and reversed demonstration panels. |
| Raised black | `#161616` | `--color-raised-dark` | surface | Dark feature cards on black; also portrait-card bodies. |
| Black | `#000000` | `--color-ink` | text, background, action | Primary ink, dramatic chapter backgrounds and dark selected pills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Recommended plan wash | `#fff6ff` | `--color-pricing-tint` | surface | Very pale pink interior behind the featured plan. |

## Typography

- **soehne** — All marketing headings, labels, paragraphs and controls. Compact contemporary grotesk with a sturdy x-height, blunt heavy capitals and approachable regular text. If unavailable, use **Inter**. Use 400, 600, 700 and 900; preserve tight display tracking and deliberate line breaks. Font stack: "soehne", "Inter", "soehne Fallback", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-display | soehne | 900 | 96px | 1 | -0.01em, uppercase | size clamp(3.125rem, 2.11268rem + 4.31925vw, 6rem) | Monumental centered closing call on black. |
| statistic | soehne | 900 | 72px | 0.8 | normal, uppercase | size clamp(2rem, 1.11972rem + 3.75587vw, 4.5rem) | Headline numerals within colored impact bars. |
| opening-headline | soehne | 900 | 48px | 1.03 | -0.02em, uppercase | size clamp(1.75rem, 1.30986rem + 1.87793vw, 3rem) | Black-panel opening promise, broken into short muscular lines. |
| heading | soehne | 700 | 48px | 1.1 | -0.015em | size clamp(1.875rem, 1.47887rem + 1.69014vw, 3rem) | Main chapter headings in sentence case. |
| quote-heading | soehne | 700 | 40px | 1.1 | -0.025em | size clamp(1.5rem, 1.14789rem + 1.50235vw, 2.5rem) | Testimonials, FAQ title and compact section leads. |
| feature-heading | soehne | 700 | 32px | 1.15 | -0.025em | fixed | Prominent headings inside wide feature cards. |
| card-heading | soehne | 700 | 28px | 1.2 | -0.01em | size clamp(1.5rem, 1.41197rem + 0.375587vw, 1.75rem) | Smaller capability and card titles. |
| tile-heading | soehne | 700 | 22px | 1.2 | -0.01em | size clamp(1.25rem, 1.20599rem + 0.187793vw, 1.375rem) | Audience tiles and newsletter lead. |
| question | soehne | 600 | 20px | 1.35 | -0.0125em | size clamp(1.125rem, 1.08099rem + 0.187793vw, 1.25rem) | FAQ question rows and compact person names. |
| body | soehne | 400 | 18px | 1.5 | 0.01em | size clamp(1rem, 0.955986rem + 0.187793vw, 1.125rem) | Opening support, chapter descriptions and FAQ answers. |
| body-small | soehne | 400 | 16px | 1.5 | 0.01em | size clamp(0.875rem, 0.830986rem + 0.187793vw, 1rem) | Feature-card support and tab controls. |
| navigation | soehne | 400 | 16px | 1.5 | normal | fixed | Main navigation links. |
| footer-link | soehne | 400 | 15px | 1.15 | 0.03em | fixed | Compact footer navigation. |
| label | soehne | 700 | 13px | 1.5 | 0.03em, uppercase | size clamp(0.6875rem, 0.643486rem + 0.187793vw, 0.8125rem) | Eyebrows, button text, feature links and statistic captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| product overviews and detail pages | centered-display | soehne | 900 | 64px | 0.96 | -0.02em, uppercase | size clamp(2rem, 1.29578rem + 3.0047vw, 4rem) | Centered product introduction and large contained conversion headline. |
| pricing pages | pricing-display | soehne | 900 | 56px | 0.96 | -0.02em, uppercase | size clamp(2rem, 1.47183rem + 2.25352vw, 3.5rem) | Left-column lead beside a quote form. |
| deep product and company-story pages | chapter-display | soehne | 700 | 54px | 1.08 | -0.03em | size clamp(2rem, 1.51584rem + 2.06573vw, 3.375rem) | Centered capability chapter headline or broad company mission statement. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use weight 900 and uppercase selectively for the opening, major conversion statements and numerals; ordinary capability chapters remain weight 700 and sentence case.
- Body text has slight positive tracking; larger headings tighten to -0.01em through -0.03em. Do not apply display tracking to paragraphs.
- Small uppercase category labels and primary actions share one recipe; their hierarchy comes from placement and surface rather than a separate font.
- White support text on black is softened to 80% opacity; retain full white for the main headline.

## Layout

**Density:** Airy between chapters, compact within controls and proof structures. The large gaps let dense interface imagery read as a single object.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight title-to-copy gaps and inline icon spacing. |
| 16px | Eyebrow-to-heading gaps and standard pill side padding. |
| 20px | Heading-to-support spacing, FAQ row vertical padding and statistic-card inner padding. |
| 21px | Footer link vertical rhythm. |
| 24px | Primary grid gutter, common stacked content gaps and tab-to-content spacing. |
| 32px | Paragraph-to-action gap and standard container side padding. |
| 40px | Contained-card padding and chapter-to-tabs spacing. |
| 48px | Feature-card internal offset and space before media. |
| 64px | Large stacked content gaps and footer bottom padding. |
| 80px | Opening text panel padding, feature-row separation and footer transitions. |
| 96px | Large contained demonstration panel vertical padding. |
| 128px | Major section padding and closing-call top breathing room. |
| 144px | FAQ and spacious white chapter padding. |
| 164px | Expanded section separation on long-form product and story pages. |

### Containers and grids

- **main container**: max width 1278px · side padding 32px. Centered shared content width; at 1440px the visible content edges sit 81px in from either side. Preserve alignment across light and dark chapters.
- **paired opening**: 2 columns · gap 24px. Equal text and media panels; each is 627px wide at desktop.
- **capability mosaic**: 6 columns · gap 24px. Wide four-column feature beside a two-column device tile, followed by two equal three-column panels; vertical gap 80px.
- **audience grid**: 4 columns · gap 24px. A heading occupies the first cell, with audience tiles filling the remaining cells and the next row.
- **faq column**: max width 841px. Centered question-and-answer stack; answer text narrows further to 730px.
- **footer columns**: max width 1041px · 5 columns · gap 24px. Five link groups alongside a separate identity/social column.
- **catalog rail** (only for long product catalogs): max width 922px · gap 48px. Main capability column beside a 272px sticky chapter rail within the shared container.

## Corner radius

| Element | Radius |
| --- | --- |
| actions and tabs | 9999px (pill) |
| feature panels and inputs | 6px |
| audience tiles | 8px |
| newsletter and stat tops | 4px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default content field.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Open white space surrounds panels rather than boxing every paragraph.

**Transfer:** Keep the canvas clean; let bounded media and black chapters create contrast.

#### Black chapter · level 0

**Use:** Capability showcase, testimonials and the ending.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Full-width black areas form substantial chapters, not thin decorative bands.

**Transfer:** Use for a coherent product story or proof moment.

#### Notched promise panel · level 1

**Use:** Opening text stage.

**CSS:** `background: #000000; color: #ffffff; border-radius: 6px; padding: 80px`

**Observed:** One curved inward bite in the left edge aligns near the category label; the rest is a restrained rectangle.

**Transfer:** Apply the edge-notch construction to the panel without shrinking the text inset.

#### Soft pink stage · level 1

**Use:** Large interface demonstration.

**CSS:** `background: #ffc5ee; border-radius: 6px; overflow: hidden`

**Observed:** A flat pink field supports a sharply framed white interface; no ambient shadow cloud.

**Transfer:** Use as the default colored software stage, with ice blue or lime for neighboring objects.

#### Raised dark card · level 1

**Use:** Dark feature panel or portrait-card body.

**CSS:** `background: #161616; border-radius: 6px`

**Observed:** A modest tonal step from black, without a drop shadow.

**Transfer:** Separate dark cards by fill and space rather than luminous borders.

#### Cream questions · level 0

**Use:** FAQ chapter.

**CSS:** `background: #fffcf6; padding-top: 144px; padding-bottom: 144px`

**Observed:** The faint warm canvas differentiates practical questions from the preceding white narrative.

**Transfer:** Reserve this warm neutral for objection handling.

#### Featured plan wash · level 1

**Only for:** pricing pages

**Use:** Recommended commercial plan.

**CSS:** `background: #fff6ff; border: 2px solid #ff83da; border-radius: 6px`

**Observed:** Full-width featured plan with a compact popularity tag; two simpler outlined plans sit beneath it.

**Transfer:** Use emphasis through pale fill and edge, not elevation.

## Components

### Primary button

**Use:** Main conversion action in navigation, opening and closing.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ff83da; color: #000000; height: 40px; padding: 0px 16px; border-radius: 9999px; gap: 10px`

**Text style:** `label` — soehne 700 · 13px/1.5 · tracking 0.03em · uppercase

**Observed:** A compact text-only pill; it does not expand to fill the hero. Pricing forms use a full-width 44px-high version.

**Transfer:** Keep one clear action label and use the same pill across light and dark sections.

### Secondary button

**Use:** Explore, study and integration links.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; color: #000000; height: 40px; padding: 0px 16px; border: 1px solid rgba(0,0,0,0.2); border-radius: 9999px; gap: 10px`

**Text style:** `label` — soehne 700 · 13px/1.5 · tracking 0.03em · uppercase

**Observed:** An outline pill on the surrounding canvas; in dark sections its ink and border reverse.

**Transfer:** Keep the outline light so it remains secondary.

### Sticky navigation

**Use:** Persistent access to site categories and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 50; background: #ffffff; height: 81px; border-bottom: 1px solid rgba(0,0,0,0.082595)`

**Text style:** `navigation` — soehne 400 · 16px/1.5

**Observed:** Identity left, six simple category links across the middle and Primary button right. A separate 41px utility row precedes it; a 40px announcement strip can sit above that.

**States:** Declared: hover navigation-link opacity 0.65.

**Transfer:** Keep the primary header visible while utility material scrolls away.

### Audience tile

**Use:** Route readers to the relevant use case.

**CSS:** `display: flex; flex-direction: column; position: relative; background: #f4f5f9; border-radius: 8px; padding: 48px 44px`

**Text style:** `tile-heading` — soehne 700 · 22px/1.2 · tracking -0.01em

**Observed:** Small icon, title, brief benefit and bottom uppercase arrow link. An inward bite interrupts the left edge near the icon.

**States:** Declared: hover background-color #f7e1f7.

**Transfer:** Use role or scale categories rather than a grid of generic feature names.

### Impact bar

**Use:** A graphic proof comparison with one expanded case.

**CSS:** `display: flex; background: #ff83da; color: #000000; border-radius: 4px 4px 0px 0px; padding: 20px 12px 20px 16px`

**Text style:** `statistic` — soehne 900 · 72px/0.8 · uppercase

**Observed:** Narrow bars share a baseline but differ in height. Large numerals sit above small uppercase result captions. The selected bar expands to a broad photo-and-story card; other bars use lime, blue and charcoal.

**Transfer:** Use real outcome metrics and allow one case to be visually expanded without turning every metric into an equally sized card.

### FAQ row

**Use:** Practical questions in the centered FAQ stack.

**CSS:** `padding: 20px 8px; border-top: 1px solid transparent; border-bottom: 1px solid rgba(0,0,0,0.1)`

**Text style:** `question` — soehne 600 · 20px/1.35 · tracking -0.0125em

**Observed:** Question on the left and a small rounded-square plus on the right. The first answer is open, its control becomes a pink minus, top padding grows to 32px and both horizontal edges darken to black at 45%. Answers use body text within 730px.

**Transfer:** Use details/summary behavior and preserve the simple ruled-list appearance.

### Text input

**Use:** Newsletter email and sales enquiry forms.

**CSS:** `background: #ffffff; height: 50px; border: 1px solid rgba(0,0,0,0.2); border-radius: 6px; padding: 12px 20px; box-shadow: none`

**Observed:** Plain rectangular fields, not pills; longer forms pair name fields then use full-width fields. Form rows are separated by 12px.

**Transfer:** Keep field structure practical and align action width with the form where appropriate.

### Newsletter strip

**Use:** Bright final engagement inside the black footer.

**CSS:** `display: flex; align-items: center; justify-content: space-between; background: #ff83da; color: #000000; border-radius: 4px; padding: 38px 0px; row-gap: 32px`

**Text style:** `tile-heading` — soehne 700 · 22px/1.2 · tracking -0.01em

**Observed:** A left-edge inward bite, bold sentence on the left, white Text input and black subscribe pill on the right. The strip spans the shared container.

**Transfer:** Retain the bright full-width interruption even when the secondary engagement is a resource subscription rather than news.

### Footer link

**Use:** Dense grouped navigation in the black ending.

**CSS:** `display: flex; align-items: center; color: #ffffff; column-gap: 10px`

**Text style:** `footer-link` — soehne 400 · 15px/1.15 · tracking 0.03em

**Observed:** Links sit in five columns with uppercase group labels and 21px row gaps, adjacent to identity and social controls.

**States:** Declared: hover color color-mix(in oklab,#fff 65%,transparent).

**Transfer:** Organize by reader task, with concise labels rather than paragraph-length links.

### Feature tab

**Only for:** multi-capability product pages

**Use:** Switch or navigate between related workflows.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 36px; padding: 4px 16px; border: 1px solid rgba(0,0,0,0.2); border-radius: 9999px; color: #000000`

**Text style:** `body-small` — soehne 400 · 16px/1.5 · tracking 0.01em

**Observed:** Sentence-case pills arranged in a wrapping row with 12px gaps; selected tabs are black with white text, while inactive text is softened.

**States:** Declared: hover border-color color-mix(in oklab,#000 80%,transparent).

**Transfer:** Use compact human-readable workflow labels.

## Imagery and graphics

### Interface in the real world

**Use:** Opening media panel and larger product introductions.

**Observed:** A bright garden, pool or terrace supplies the full-bleed background. A large white desktop interface with a dark rounded outline floats above it and is clipped at the panel edge; the interface dominates while the place remains visible around it. Small dark category pills sit along the lower edge and a pause control at the top right.

**Transfer:** Pair a relevant daylight environment with one legible product workflow. For a nonvisual service, create an original dashboard or process view and stage it at the same object-like scale.

### Flat-color workflow objects

**Use:** Capability panels throughout the page.

**Observed:** White interface fragments, payment terminals and phones float on soft pink, ice blue or electric lime. Some are centered with ample breathing room, others enlarge past the lower or right edge. UI detail stays mostly neutral with a few small pink accents.

**Transfer:** Use original screens or a simplified workflow specimen, not a rainbow of decorative widgets. Keep dark device outlines crisp and backdrops flat.

**Build:** Create a 6px-radius overflow-hidden panel with a palette fill. Insert a white rounded interface rectangle with a 3px black outline; center a compact workflow card or enlarge the full view until it clips at one edge. Layer two or three smaller white task cards at different vertical offsets for fragmented workflows. Avoid diffuse elevation effects.

### Edge-notch construction

**Use:** Signature panel silhouettes in the opening, selected capability cards and newsletter.

**Observed:** A narrow inward cusp cuts a short section of a straight panel edge, with smooth shoulders and a rounded inner tip. It reads as a bite or ticket-like interruption, not as a circular perforation or a jagged tear.

**Transfer:** Repeat the same silhouette at different scales while matching the cutout to the immediate surrounding surface.

**Build:** Use an SVG mask with a white rounded rectangle and a black notch path touching the left edge. For the opening, allocate roughly 36px depth and 40px height; draw two smooth cubic shoulders that converge on a small rounded inward tip. The newsletter uses roughly 24px depth and 26px height. Mirror it for opposite edges on paired media-caption panels. Place the notch near a label or the media-to-caption seam, never through text.

### Proof photography

**Use:** Expanded impact cards and customer stories.

**Observed:** Warm, naturally lit interiors and architecture are presented in clean rectangular windows with minimal rounding. Photos occupy roughly half an expanded card, paired with a vivid lime or charcoal story field; they are neither duotoned nor darkened into background texture.

**Transfer:** Show a real user environment or completed result with the same warm daylight and straightforward framing.

### Human-use photo skyline

**Only for:** deep product storytelling

**Use:** Human-centered contrast inside a black chapter.

**Observed:** Five natural-color photos show hands and people using phones, tablets or terminals. Four small 167px by 198px views flank a central 282px by 335px portrait, all bottom-aligned; a fine rule and centered explanatory line sit below.

**Transfer:** Create an analogous five-image skyline of people carrying out the new product's work. Keep the central image taller, photography warm and the surrounding field black.

### Company documentary imagery

**Only for:** company-story pages

**Use:** History, leadership and cultural principles.

**Observed:** Candid daylight archive photos pair with oversized white years on black. Leadership uses consistently framed waist-up portraits on pale neutral backgrounds above dark text bodies. A principles section contrasts a black typographic booklet and staggered color photos with a ruled values list.

**Transfer:** Use genuine team and process photography with consistent portrait scale. A simple original editorial cover and two documentary photos can replace the booklet collage.

### Icons

**Observed:** Compact functional arrows, plus/minus controls and chevrons accompany text. Feature categories use bold black pictograms in small pink or gray square badges; action arrows are about 13px–14px, social controls about 28px and feature badges about 36px. Fine utility strokes contrast with solid category marks.

**Transfer:** Choose simple monochrome category silhouettes and thin utility arrows. Keep the icon vocabulary compact; do not replace category badges with elaborate multicolor illustrations.

## Section recipes

How recurring sections are built.

### First screen: Paired product-stage opening

**Observed:** The white first screen begins with a 40px pink announcement, a 41px utility row and an 81px Sticky navigation. The 1278px shared content area then divides into equal 627px by 634px panels across a 24px gap. Back to front: white canvas; Notched promise panel left and real-world photograph right; a huge outlined interface over the photograph; small category pills and pause control over the media. The left panel has 80px inset and vertically centered content: a small icon/category label, a three-line uppercase opening-headline, body support after 20px, then Primary button after 32px. The media has equal visual weight and deliberately clips the interface. Within the first 900px the complete paired stage, all opening copy and actions, and the beginning of the centered customer-proof line are visible; the logo row follows below.

**Transfer:** Use a short category label, a three- or four-line outcome promise and one original workflow illustration with environmental context. Recreate the interface object if photography or video is unavailable. Product overviews instead open with centered 64px capitals and a pink action on white; detail pages place a wide interface scene below that center stack. Pricing opens with 56px capitals and benefits beside a form; company introductions pair a 64px headline and narrative with a documentary media panel.

**Avoid:** Do not substitute a centered text-only masthead, a full-bleed dark photo with text overlay, or two small floating cards in a mostly empty hero. Keep the equal-sized panels and strong cropped object.

**Text style:** `opening-headline` — soehne 900 · 48px/1.03 · tracking -0.02em · uppercase

### Eyebrow and chapter lead

**Observed:** A 13px uppercase label precedes a sentence-case heading by 16px, followed by 18px support after about 20px. Left-aligned chapters often reserve action controls at the right; centered variants narrow the copy to about 628px.

**Transfer:** Name the capability with the label, then state its practical outcome in the heading. Maintain one dominant statement per chapter.

**Text style:** `heading` — soehne 700 · 48px/1.1 · tracking -0.015em

### Audience routing grid

**Observed:** A four-column grid with 24px gutters puts a short heading in the first cell and Audience tiles in subsequent cells, continuing onto the next row. Tiles are approximately 302px square, with icon and benefit text rather than pictures.

**Transfer:** Use when the product serves distinct reader groups; allow the heading to participate in the grid instead of placing it above another centered section.

### Black capability mosaic

**Observed:** Black chapter begins with a white sentence-case heading and an 80px gap to media. A six-column Capability mosaic combines a broad pink workflow panel and narrow lime device image, then two equal-width dark and blue panels. Feature-heading and body-small sit near the top of the wide card, while the interface grows from the bottom edge.

**Transfer:** Vary panel proportions to distinguish system-wide capabilities from compact tools, keeping the 24px gutter and coordinated flat fills.

### Centered testimonial pause

**Observed:** A long black section centers a weight 700 quote at 40px/1.1 within an 848px width. Attribution is much smaller, followed by a white customer pill and subtle carousel dots. Generous black space surrounds the quote.

**Transfer:** Use a genuine specific testimonial with a short attribution; let the words, rather than a decorative quotation card, dominate.

**Text style:** `quote-heading` — soehne 700 · 40px/1.1 · tracking -0.025em

### Impact chart made of stories

**Observed:** A white chapter has heading and support left, circular previous/next controls right, and a bottom-aligned set of Impact bars below. Pink, lime, ice blue and charcoal make distinct columns. One expands into a broad story-plus-photo composition; numerals remain enormous and captions small uppercase.

**Transfer:** Turn verified outcomes into a set of visually different heights, with one selected case expanded. Use an original result photograph or concrete deliverable in the expanded card.

**Text style:** `statistic` — soehne 900 · 72px/0.8 · uppercase

### Integration capsule and recognition row

**Observed:** A left copy column pairs an eyebrow, heading, support and Secondary button with a rounded horizontal capsule of overlapping colorful app marks and a plus. Beneath it, five compact recognition cells use 96px badge images, ruled edges and tiny year pills. Centered product-page variants combine overlapping 40px marks, uppercase action and pink circle arrow into one 66px-high outline capsule.

**Transfer:** Use real compatible tools or simple original symbol disks for the capsule. Recognition can be adapted to verifiable certifications or measurable trust signals without changing the compact ruled presentation.

### Cream FAQ

**Observed:** Cream questions frames an 841px centered column. A 40px title leads the stack by roughly 73px. FAQ rows are ruled rather than carded, with one expanded answer and small right-aligned plus/minus controls.

**Transfer:** Answer purchase and adoption objections in plain terms; keep paragraphs readable and the first useful answer visible.

**Text style:** `quote-heading` — soehne 700 · 40px/1.1 · tracking -0.025em

### Monumental closing and full footer

**Observed:** The black closing call occupies about 457px, with 128px top breathing room and a centered closing-display. Three small white numbered circles sit inline with short steps, followed by Primary button. The upper black silhouette rises with broadly rounded shoulders before it merges into the footer. The footer adds an identity/social area, five link groups, a four-column recognition matrix, the bright Notched Newsletter strip, a subdued certification row and a thin ruled legal line. Footer padding begins at 72px and ends at 64px.

**Transfer:** Keep the oversized closing statement, three small steps and bright action, then retain a substantial functional footer. Adapt proof density to the project's actual credentials rather than inventing badges.

**Text style:** `closing-display` — soehne 900 · 96px/1 · tracking -0.01em · uppercase

### Workflow catalog with chapter rail

**Only for:** long product catalogs

**Observed:** A 272px sticky left rail uses ruled uppercase chapter links, a pink active dot and thin pink progress line. The 922px main column progresses through chapter heading, 36px Feature tabs and media. Large notched color panels alternate with two-column tiles and photo-plus-copy rows separated by hairlines.

**Transfer:** Organize a large product around the user's working journey instead of a flat feature inventory. Release the rail when the catalog ends and return to full-width closing sections.

### Commercial plan and enquiry layout

**Only for:** pricing pages

**Observed:** The opening pairs a 56px black uppercase promise and three checkmarked benefits with a 546px-wide form. A Featured plan wash then spans the container: short plan pitch on the left, nine compact capability summaries in a three-column matrix to the right. Two quieter outlined plan cards sit below; add-on cards, quantified results, a blue conversion panel, a photographic testimonial, a repeated enquiry form and Cream FAQ provide further decision support.

**Transfer:** Use the hierarchy to recommend a clear plan and explain how pricing is obtained. Adapt the form length and commercial claims to the actual buying process.

**Text style:** `pricing-display` — soehne 900 · 56px/0.96 · tracking -0.02em · uppercase

### Company timeline and principles

**Only for:** company-story pages

**Observed:** A black narrative chapter uses a broad white mission statement, a left contextual column and right chronological rows with documentary photos, enormous years and compact captions. Leadership follows as horizontally scrolling 302px-wide Raised dark cards with consistent portraits. A white section switches to a two-column layout: editorial collage left, five numbered and ruled principle rows right, followed by a careers invitation before the shared closing.

**Transfer:** Give history a readable chronology and principles a restrained editorial treatment; use real milestones and people, not software illustrations in every section.

**Text style:** `chapter-display` — soehne 700 · 54px/1.08 · tracking -0.03em

## Page flow

**Storyline:** Outcome promise → tangible product demonstration → credible users and results → capability chapters → adaptability and adoption → practical objections → monumental closing call → deep functional footer.

### Broad marketing landing page; default composition

1. **Promise and demonstration** — Equal black promise and photographed product-stage panels.
2. **Social proof and audience fit** — Centered customer statement, monochrome logos and notched routing tiles.
3. **Capability chapters** — Black mosaic of colored interface and device panels.
4. **Trust and quantified proof** — Centered testimonial followed by an expandable colored impact chart.
5. **Adaptability and objection handling** — Integration capsule, recognition row and cream FAQ.
6. **Closing call and onward navigation** — Monumental black call, numbered steps and shared deep footer.

**Transfer:** Use the paired opening as the default for a new product, then select the most useful proof and capability blocks rather than repeating a fixed section count.

### Commercial enquiry and plan selection

1. **Offer and enquiry** — Benefits and uppercase promise beside an enquiry form.
2. **Plan comparison** — One featured broad plan above two quieter alternatives.
3. **Value justification** — Add-ons, large results and blue conversion panel.
4. **Trust and buying process** — Photo testimonial and repeated form with three next steps.
5. **Objection handling and closing call** — Cream FAQ then the shared black close and footer.

**Transfer:** Use for consultative or custom-priced products; show how the quote process works as clearly as the capabilities.

### Explain a broad product suite through a working journey

1. **Promise** — Centered uppercase introduction and compact action.
2. **Capability journey** — Sticky chapter rail with colored demonstration cards, tabs and photo rows.
3. **Social proof** — Testimonials interrupt the long product sequence.
4. **Adaptability** — Centered integration action capsule.
5. **Closing call** — Shared black close and full footer.

**Transfer:** Group related capabilities by user moment and use the rail only while the catalog is relevant.

### Deep explanation of a flagship product

1. **Promise and demonstration** — Centered uppercase headline above a wide photographed interface scene.
2. **Proof** — Customer-type tabs and a vivid lime case study.
3. **Capability chapters** — Pink system stage, practical split feature rows, black human-use skyline and tabbed dark demos.
4. **Quantified value** — Slim pink calculator invitation, result chart and horizontally scrolling growth cards.
5. **Adoption and adaptability** — Blue onboarding panel and centered integration capsule.
6. **Objection handling and closing call** — Long cream FAQ, black close and shared footer.

**Transfer:** Balance deep features with human-use imagery and adoption support so a long technical page does not become an uninterrupted interface gallery.

### Company narrative and cultural credibility

1. **Introduction** — Split company promise and documentary media with a short statistics row.
2. **History** — Black mission chapter and chronological image/year rows.
3. **Human proof** — Dark portrait-card leadership carousel.
4. **Principles and invitation** — White editorial collage beside numbered principles, then a careers invitation.
5. **Closing call** — Shared black close and deep footer.

**Transfer:** Let documentary people and milestone imagery take the place of product demonstrations, while retaining typography, notch language and the shared ending.

## Writing

Confident and commercially direct, but friendly enough to sound like a helpful operator rather than an enterprise procurement document. Benefits are framed as everyday work becoming easier, with occasional dry warmth and short conversational turns.

**Do not copy:** Do not reuse Mews names, logos, product names, customer identities, testimonials, award artwork, proprietary imagery or numerical performance claims. Create original copy and use only substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; the product is an active helper. We appears in company or support contexts rather than dominating the sales promise.
- **Rhythm:** Headlines usually take four to nine words, with short clauses and occasional two-part sentences. Supporting copy is generally one or two clear sentences; long explanations belong in FAQs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | State the product's category and the user's modern working context in a compact declarative promise. | 5–9 words | “The operating system for modern hotels” |
| Capability heading | Lead with an action and the practical relief it creates; pair two outcomes when useful. | 4–9 words | “Automate the routine, focus on the guest”<br>“Make stays memorable. And profitable.” |
| Supporting line | Connect the capability to a recognizable workflow and reduce perceived complexity. | 1–2 sentences | “Plug into 1,000+ hospitality apps and create a platform that fits your property like a glove.” |
| Primary action | Short verb-led invitation with no hype or punctuation. | 2–4 words | “Book a demo”<br>“Get pricing” |
| Objection handling | Use an actual buyer question rather than an abstract topic label. | 5–13 words | “What if I want to keep parts of my current tech stack?” |
| Closing call | A brief question that moves from tools to the reader's intended result. | 3–5 words | “Ready for impact?” |

**Words and phrasing to use:** run smoothly; built for; one system; simplify; your way; get up and running; make the most of; less time; more control

**Avoid:** synergize; paradigm shift; revolutionary ecosystem; unlock limitless possibilities; best-in-class without support; technical acronym chains

**Rules:**

- Put the practical outcome before the mechanism.
- Use contractions and an occasional parenthetical aside to keep substantial product detail human.
- Support performance claims with attribution and a clear scope; do not make metrics sound universal.
- Use uppercase as visual styling for labels and display lines, not as a shouting tone throughout the prose.
- Name a concrete task or working moment in support text rather than repeating the heading in longer words.

## Do's and Don'ts

### Do

- Keep the default paired opening balanced across a 24px gutter.
- Use 80px of breathing room inside the black opening panel.
- Preserve weight 900 capitals for display moments and weight 700 sentence case for chapter leads.
- Stage white interfaces against flat pink, ice blue or lime with crisp dark object frames.
- Use 6px card corners and fully rounded action pills as separate shape families.
- Align impact bars to one baseline and let one proof story expand wider than the others.
- Carry the curved edge-notch into multiple meaningful panels.
- Give the footer its pink 134px newsletter interruption rather than ending in uninterrupted black.

### Don't

- Do not turn the whole page into a soft-pink background; color is primarily held inside objects.
- Do not replace the black chapter fields with navy gradients or gray-tinted panels.
- Do not apply 24px rounding to every feature card; the normal card radius is 6px.
- Do not inflate every button to a 56px-high rectangle; the default action is a compact 40px pill.
- Do not use weight 400 for major headings or a contrasting serif for quotations.
- Do not add floating-card drop shadows across the marketing layout; flat fills and spacing separate layers.
- Do not render all proof as identical bordered KPI tiles; preserve the graphic height and width contrast.
- Do not use multicolor outline icons in place of the solid badge-and-utility icon vocabulary.

## Motion and responsive

### Motion

**Observed:**

- The customer/logo marquee declares marquee-scroll 30s linear infinite.
- Navigation opacity and many color interactions declare 0.3s cubic-bezier(.4,0,.2,1); footer links use 0.2s with the same curve.
- FAQ border-color and padding declare 0.3s cubic-bezier(.4,0,.2,1). Impact-card padding declares 0.5s with that curve.
- Product media includes a pause control; carousel controls use circular progress treatments.

**Transfer:**

- Keep the product stage as one coordinated demonstration with a visible pause affordance.
- Use the declared short color transitions for compact controls and the slower panel transitions only for expanded media or proof cards.

**Unknown:**

- Exact playback, scroll-reveal sequence and carousel autoplay timings are not established.

### Responsive

**Observed:**

- CSS width breakpoints include 393px, 400px, 600px, 640px, 768px, 1024px, 1279px, 1280px and 1536px.
- The paired opening declares two columns at the large-layout breakpoint. Audience routing declares two, three and four columns across progressively wider layouts.
- Viewport-dependent type formulas are supplied with their respective typography recipes.

**Transfer:**

- On narrow layouts, place the notched promise before its media panel, preserve a clear notch and reduce insets before shrinking copy excessively.
- For long catalogs, replace the desktop side rail with compact chapter navigation and let tab rows scroll rather than compressing every pill.
- Stack footer groups and the newsletter form while keeping the pink strip and black chapter identity distinct.

**Unknown:**

- Narrow-screen layouts and mobile navigation behavior are not visually established; stacking guidance is a recommended adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
