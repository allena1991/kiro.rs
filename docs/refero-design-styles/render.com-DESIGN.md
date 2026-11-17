# Render — infrastructure in playful squares

## Overview

A bright technical style with airy, light grotesk headlines, matter-of-fact body copy and an exposed architectural grid. White and near-black carry most of the page; electric purple, lilac and occasional pastel color fields add a playful computational edge. Flat interface diagrams and pixel-like geometric ornaments suit developer tools, infrastructure and complex products that need to feel accessible rather than heavy.

### Essentials

- Headlines feel like spacious technical promises, not bold advertising: Roobert 300 at 80px/1 with -0.03em tracking for the opening, stepping to 64px/68px at -0.02em for major chapters.
- The opening balances a verbal promise against a working system: a 720px text area starts one 90px grid column in, a 630px-wide interface illustration extends off the right edge, and 24px/32px support copy leads to two 48px actions.
- Actions are hard-edged instruments: near-black filled rectangles and 1px near-black outlined rectangles, 0px radius, 24px horizontal padding and a small right-facing chevron on the primary action.
- Color lives in computational accents rather than the whole canvas: keep ordinary marketing sections predominantly white, use #8a05ff for links and pixel ornaments, #e7dbff for small fields, and a purple-to-ochre gradient for a short headline phrase.
- The square lattice is a signature device: 1px #e3e3e3 rules form 90px cells at desktop, broken into stepped clusters and filled with purple stripe/checker patterns. Include these around a hero or proof block and the ending; a simple SVG tile system is the fallback when no product artwork exists.
- Proof is staged as a lightweight schematic rather than a giant glossy device: thin white interface cards, fine purple connections, tiny status marks and edge fades sit directly on white. Finish with a substantial #141414 link directory offset over the square grid, with purple patterns visible along its left and bottom edges.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric purple | `#8a05ff` | `--color-purple` | accent, link, surface | Pixel ornaments, numbered badges, documentation links and the start of highlighted headline gradients. |
| Lilac | `#e7dbff` | `--color-lilac` | background, surface, accent | Announcement band, tile motifs and gentle washes. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender wash | `#f4f0ff` | `--color-lavender-wash` | background | Very pale atmospheric feature backdrops; also a support chapter fill. |
| Ochre | `#d67f2e` | `--color-ochre` | text, accent | Warm end of a short gradient phrase and one member of a colored capability list. |
| Teal | `#009e7a` | `--color-teal` | text | A second hue within the colored capability list, not a general action color. |
| Proof blue | `#c2eaff` | `--color-pale-blue` | background, accent | Text-sized attribution highlights and flat illustration fields. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, white panels and inverse action text. |
| Glow neutral | `#f0f0f0` | `--color-glow-neutral` | surface | Neutral end of the blurred lilac atmosphere. |
| Grid rule | `#e3e3e3` | `--color-rule` | border | Fine separators and square construction grid. |
| Muted text | `#6b6b6b` | `--color-muted` | text, link | Proof overlines, tertiary labels and footer links. |
| Secondary text | `#4d4d4d` | `--color-secondary` | text | Supporting paragraphs and section subheads. |
| Dark panel edge | `#272727` | `--color-dark-rule` | border | Subtle top edge within the closing directory. |
| Directory black | `#141414` | `--color-footer` | background | Large closing directory panel. |
| Primary ink | `#0d0d0d` | `--color-ink` | text, action, border | Primary text, filled actions and strong outlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| extended product overviews | Chapter off-white | `#fafafa` | `--color-chapter-canvas` | background | Backing for a long sequence of product story cards. |
| assurance chapters | Security blue wash | `#e0f4ff` | `--color-security-wash` | background | A full-width assurance chapter; also small pastel mosaic squares. |
| enterprise assurance chapters | Midnight blue | `#00102a` | `--color-deep-blue` | background | Inverse assurance chapter. |
| company stories and extended product overviews | Forest green | `#006d4c` | `--color-forest` | background, border | White-on-green mission opening or green outline for a product story card. |
| company stories | Bright blue | `#33acff` | `--color-blue` | background | Geometric backing for institutional proof artwork. |
| company stories and assurance chapters | Navy | `#002c6f` | `--color-navy` | background, border | Inset institutional proof panel and assurance card outlines. |
| extended product overviews | Mint field | `#b8ffd7` | `--color-mint` | background | Flat product-illustration backing. |
| extended product overviews | Peach field | `#f5dfcc` | `--color-peach` | background | Flat product-illustration backing. |
| extended product overviews | Pink field | `#fac7ff` | `--color-pink` | background | Flat product-illustration backing. |
| support chapters | Purple grid line | `#9b52fb` | `--color-purple-rule` | border | Colored lattice around a support chapter. |

## Typography

- **Roobert** — Display headlines and feature titles. Rounded geometric grotesk with open counters and a light, approachable technical character. If unavailable, use **DM Sans**. Use 300 for display and 400 for compact titles; preserve tight tracking. Font stack: "Roobert", "DM Sans", sans-serif.
- **PPNeueMontreal** — Body copy, navigation, buttons, quotes and commercial information. Compact neutral grotesk that keeps dense technical content readable without competing with the display face. If unavailable, use **Inter**. Use predominantly 400; adjust wrapping to preserve short measures. Font stack: "PPNeueMontreal", "Inter", sans-serif.
- **PPNeueMontrealMono** — Proof captions, attribution labels and technical chapter overlines. Small utilitarian monospace, often uppercase with deliberate tracking. If unavailable, use **IBM Plex Mono**. Font stack: "PPNeueMontrealMono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Roobert | 300 | 80px | 1 | -0.03em | fixed | Default landing headline, including the short colored continuation. |
| chapter | Roobert | 300 | 64px | 68px | -0.02em | fixed | Large marketing chapter introductions and feature-grid leads. |
| heading-lg | Roobert | 300 | 64px | 1.05 | -0.02em | size clamp(36px, 6.5vw, 64px) | Process section headings and broad editorial headings. |
| closing | Roobert | 300 | 56px | 60px | -0.02em | fixed | Centered closing invitation. |
| heading-md | Roobert | 300 | 48px | 52px | -0.02em | fixed | Compact promotional chapter title. |
| feature-heading | Roobert | 300 | 40px | 1.1 | -0.015em | fixed | Large feature panels and flowing colored capability nouns. |
| step-heading | Roobert | 400 | 32px | 1.15 | -0.025em | fixed | Process-step titles. |
| support | PPNeueMontreal | 400 | 24px | 32px | normal | fixed | Hero and section support lines; large plainspoken testimonials. |
| feature-title | Roobert | 400 | 20px | 1.2 | -0.01em | fixed | Small unboxed feature-grid headings. |
| body-lg | PPNeueMontreal | 400 | 18px | 26px | 0.005em | fixed | Narrative paragraphs in larger feature panels. |
| process-body | PPNeueMontreal | 400 | 18px | 1.6 | 0.01em | fixed | Short process explanations beneath step titles. |
| body | PPNeueMontreal | 400 | 16px | 1.5 | 0.01em | fixed | Feature descriptions, short links and default buttons. |
| label | PPNeueMontreal | 400 | 16px | 1.25 | 0.01em | fixed | Navigation and footer links. |
| overline | PPNeueMontrealMono | 500 | 14px | 20px | 0.02em, uppercase | fixed | Trust labels and tinted testimonial attributions. |
| announcement | PPNeueMontreal | 400 | 14px | 1.375 | -0.01em | fixed | Narrow top announcement strip. |
| directory-label | PPNeueMontreal | 500 | 12px | 1.25 | 0.02em, uppercase | fixed | Footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| extended product overviews | platform-display | Roobert | 300 | 84px | 1 | -0.0229em | size clamp(48px, 7vw, 84px) | Centered text-first product overview opening. |
| extended product overviews | platform-heading | Roobert | 300 | 42px | 1.05 | -0.02em | fixed | Product story cards and technical chapters. |
| pricing pages | price | PPNeueMontreal | 400 | 31.7px | 0.75 | -0.012em | size clamp(24px, 2.2vw, 38px) | Monthly price figures aligned tightly with their suffix. |
| pricing and company pages | commercial-heading | PPNeueMontreal | 400 | 24px | 1.25 | normal | size clamp(20px, 2.5vw, 24px) | Plan names, editorial card names and FAQ questions. |
| recruitment pages | listing | PPNeueMontreal | 400 | 18px | 1.38 | 0.01em | fixed | Role titles, metadata and directory row content. |
| pricing pages | faq-body | PPNeueMontreal | 400 | 16px | 1.5 | normal | fixed | Long-form answers with inline underlined links. |
| extended product overviews | technical-body | PPNeueMontreal | 400 | 14px | 1.3 | normal | fixed | Dense supporting capability descriptions. |
| pricing pages | table-value | PPNeueMontreal | 400 | 14px | 20px | 0.01em | fixed | Compute tier rows. |
| extended product overviews | technical-eyebrow | PPNeueMontrealMono | 400 | 13px | 1.5 | 0.05em, uppercase | fixed | Chapter categories above technical headings. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the two grotesks distinct: the light geometric face makes promises; the neutral face explains and operates.
- Large display tracking is negative, but ordinary body and navigation tracking is slightly positive. Do not apply display tracking to paragraphs.
- Uppercase is reserved for small structural labels, not main headlines. Most headings use sentence case.
- Use chapter as the default 64px marketing recipe; heading-lg is the fluid editorial variant with a slightly tighter line height.

## Layout

**Density:** Airy at the page scale, compact inside diagrams and tables. Large open intervals separate chapters while interfaces remain fine-grained.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small feature title-to-description gap. |
| 12px | Step heading-to-copy and compact icon/text grouping. |
| 15px | Commercial card and comparison cell padding. |
| 16px | Icon-to-feature title or title-to-support spacing. |
| 20px | Paired action gap and listing row padding. |
| 24px | Feature paragraph-to-link spacing and button horizontal padding. |
| 32px | Hero headline-to-support gap and process text-to-media gap. |
| 40px | Hero support-to-actions, feature column gutters and attribution separation. |
| 60px | Feature-grid row gaps. |
| 72px | Trust-strip vertical padding. |
| 80px | Process chapter vertical padding. |
| 90px | Desktop lattice cell, panel inner padding and main content inset. |
| 120px | Major feature-grid vertical padding. |
| 270px | Open vertical staging around the centered closing panel. |

### Containers and grids

- **site**: max width 1440px · 16 columns · gap 0px · side padding 0px. Centered architectural grid; each desktop column is 90px at the full width.
- **outer-content**: max width 1260px · side padding 90px. Broad chapters occupy fourteen grid columns with one column of whitespace at each side.
- **inner-content**: max width 1080px · side padding 180px. Text-heavy feature grids and technical chapters occupy the central twelve columns.
- **feature-grid**: 4 columns · gap 40px. Four 240px feature blocks across the inner content width, with 60px row gaps.
- **process-grid**: 3 columns · gap 180px. Three 300px-wide process stories with unusually wide gutters.
- **directory-grid**: 6 columns · gap 40px. Six narrow link columns inside the dark closing panel.
- **commercial-grid** (only for pricing pages): 4 columns · gap 0px. Four 270px commercial columns aligned to the lattice, preceded by a wide label gutter.
- **faq-grid** (only for pricing pages): 2 columns · gap 50px. Two 389px answer columns with 120px row gaps, shifted to the right of the section heading.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons and panels | 0px |
| status labels | tiny status highlight | 2px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default marketing page background.

**CSS:** `background: #ffffff; color: #0d0d0d`

#### Square lattice · level 0

**Use:** Architectural chapter framing and ending backdrop.

**CSS:** `background-color: #ffffff; background-image: linear-gradient(90deg, #e3e3e3 1px, rgba(0, 0, 0, 0) 0px), repeating-linear-gradient(#e3e3e3, #e3e3e3 1px, rgba(0, 0, 0, 0) 0px, rgba(0, 0, 0, 0) 90px); background-size: 90px auto, 100% auto; background-position: -1px 0%; border-bottom: 1px solid #e3e3e3`

**Observed:** Often partially masked to leave stepped outlines rather than a continuous engineering-paper background.

**Transfer:** Expose the lattice at margins and transitions; keep central text on clear white.

#### Ruled panel · level 1

**Use:** Feature chapters and closing invitation.

**CSS:** `background: #ffffff; border: 1px solid #e3e3e3; border-radius: 0px; box-shadow: none`

**Observed:** Adjacent panels share an edge; no floating-card elevation.

**Transfer:** Use dividers and merged outlines instead of separate rounded cards.

#### Lilac atmosphere · level 0

**Use:** Soft localized color behind a chapter lead.

**CSS:** `background: linear-gradient(177deg, #e7dbff 56.49%, #f0f0f0 12.68%); width: 400px; height: 400px; border-radius: 937px; filter: blur(102px)`

**Observed:** A large blurred patch is clipped at the left edge, behind rather than over the text.

**Transfer:** Match the soft glow; exact stops are not essential.

#### Directory panel · level 1

**Use:** Substantial final link directory.

**CSS:** `background: #141414; border-top: 1px solid #272727; border-radius: 0px`

**Observed:** A 1260px by 720px block starts two lattice columns from the left and reaches the right edge.

**Transfer:** Keep the offset silhouette and tall negative space below link groups.

#### Assurance blue band · level 0

**Only for:** assurance chapters

**Use:** A distinct trust-oriented chapter.

**CSS:** `background: #e0f4ff`

**Observed:** The grid continues through the band as an inset outline and two equal columns.

**Transfer:** Use one cohesive colored chapter rather than tinting every feature.

#### Inverse assurance band · level 0

**Only for:** enterprise assurance chapters

**Use:** High-contrast certification proof.

**CSS:** `background: #00102a; color: #ffffff; padding: 80px 0px`

**Observed:** A left title faces outlined certification cards.

**Transfer:** Reserve the inverse blue for a concentrated trust statement.

#### Support lattice · level 0

**Only for:** support chapters

**Use:** Centered expertise statement.

**CSS:** `background-color: #f4f0ff; border-bottom: 1px solid #9b52fb`

**Observed:** Purple 90px grid lines frame a wide solid pale-lavender text panel.

**Transfer:** Use the same square-lattice construction with purple-rule lines.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #0d0d0d; color: #ffffff; height: 48px; padding: 0px 24px; border-radius: 0px; display: flex; align-items: center; justify-content: space-between; gap: 10px`

**Text style:** `body` — PPNeueMontreal 400 · 16px/1.5 · tracking 0.01em

**Observed:** A short label precedes a slim right chevron. The header uses a taller 66px edge-attached action; text-first product openings use 70px actions with 20px copy.

**Transfer:** Prefer a concrete low-friction action over an abstract invitation.

### Outline button

**Use:** Secondary commercial or editorial action.

**CSS:** `color: #0d0d0d; border: 1px solid #0d0d0d; height: 48px; padding: 0px 24px; border-radius: 0px; display: flex; align-items: center; justify-content: space-between; gap: 10px`

**Text style:** `body` — PPNeueMontreal 400 · 16px/1.5 · tracking 0.01em

**Observed:** Transparent backing beside the filled action; editorial jump links can end in a down chevron.

**States:** Declared: hover color #fff; focus-visible color #fff; active color #fff.

**Transfer:** Retain a strong outline rather than a pale filled secondary button.

### Navigation link

**Use:** Desktop site navigation.

**CSS:** `display: inline-flex; padding: 23px 20px; color: #0d0d0d`

**Text style:** `label` — PPNeueMontreal 400 · 16px/1.25 · tracking 0.01em

**Observed:** The white 66px navigation bar has a brand mark at left, primary links following it and account/conversion controls at right. A hairline closes its bottom edge; the active commercial page has a short black underline.

### Announcement strip

**Use:** One concise timely offer above navigation.

**CSS:** `background: #e7dbff; min-height: 40px; padding: 0px 12px; display: flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `announcement` — PPNeueMontreal 400 · 14px/1.375 · tracking -0.01em

**Observed:** A single centered statement ends in a small underlined action.

**Transfer:** Keep it slim and informational, not an oversized promotion.

### Documentation link

**Use:** Feature-specific onward reading.

**CSS:** `color: #8a05ff; display: grid; grid-template-columns: auto auto; column-gap: 6px`

**Text style:** `body` — PPNeueMontreal 400 · 16px/1.5 · tracking 0.01em

**Observed:** Plain purple words with a fine right arrow; placed beneath a paragraph rather than inside a filled control.

### Step badge

**Use:** Number a short process.

**CSS:** `background: #8a05ff; color: #ffffff; width: 32px; height: 32px; display: flex; align-items: center; justify-content: center`

**Text style:** `listing` — PPNeueMontreal 400 · 18px/1.38 · tracking 0.01em

**Observed:** A square number above a step title, not a connected timeline.

**Transfer:** Use a local sans number at 18px/24.8px; the listing recipe supplies the same type metrics.

### Feature item

**Use:** Unboxed capability collections.

**CSS:** `display: flex; flex-direction: column; gap: 8px; max-width: 240px`

**Text style:** `feature-title` — Roobert 400 · 20px/1.2 · tracking -0.01em

**Observed:** A 24px icon sits above the heading with 16px separation; the description uses body in secondary gray. Items sit directly on white rather than in independent tiles.

### Directory link

**Use:** Dense closing navigation.

**CSS:** `color: #6b6b6b`

**Text style:** `label` — PPNeueMontreal 400 · 16px/1.25 · tracking 0.01em

**Observed:** Links stack with 16px gaps beneath white uppercase directory-label text. Six columns sit within the dark panel.

**States:** Declared: hover color rgb(255 255 255/1); focus-visible not specified; active color rgb(255 255 255/1).

### Listing row

**Only for:** recruitment pages

**Use:** Browsable opportunities grouped by discipline.

**CSS:** `display: flex; align-items: center; justify-content: space-between; border: 1px solid #0d0d0d; padding: 20px; border-radius: 0px`

**Text style:** `listing` — PPNeueMontreal 400 · 18px/1.38 · tracking 0.01em

**Observed:** Title and location form two internal columns, followed by a right arrow. Rows are 960px wide, commonly 67px tall, expanding to 92px for wrapped content; siblings are separated by 16px.

### Comparison cell

**Only for:** pricing pages

**Use:** Aligned feature and plan comparisons.

**CSS:** `background: #ffffff; border-left: 1px solid #e3e3e3; padding: 20px 15px; text-align: center`

**Text style:** `label` — PPNeueMontreal 400 · 16px/1.25 · tracking 0.01em

**Observed:** Plan cells are 270px wide and typically 64px tall; horizontal rules separate rows. The first column is left aligned, with indented subfeatures. Checks are simple black strokes, absent features use pale dashes, and the enterprise column header has a gray fill.

### FAQ answer

**Only for:** pricing pages

**Use:** Visible objection handling without collapsed accordions.

**CSS:** `display: flex; flex-direction: column; gap: 20px`

**Text style:** `commercial-heading` — PPNeueMontreal 400 · 24px/1.25

**Observed:** A regular-weight question sits over faq-body copy with underlined inline links; two open columns have ample vertical separation.

## Imagery and graphics

### Working-system schematic

**Use:** Main hero object and smaller capability illustrations.

**Observed:** A bright, flat arrangement of white service cards with very fine gray outlines, tiny line graphs, purple connector lines and restrained green status checks. The main object is 630px wide and clipped by the right edge; a dark command chip floats above it. Secondary illustrations are roughly 450px by 180px and fade into their white surroundings.

**Transfer:** Show the new product's meaningful objects and relationships, not an entire dashboard. The minimum version is three white outline cards joined by purple elbow connectors, with one status row and one simple graph per card.

**Build:** Use an SVG viewBox around 630 by 591. Draw white rectangles with 1px pale-gray rules, small gray labels and purple 1px polylines. Connect cards with orthogonal paths. Layer a dark rectangular input chip above, place two purple patterned 90px tiles on the lattice, and mask the outer edge with a white gradient.

### Pixel lattice ornaments

**Use:** Signature framing at openings, proof moments and the closing directory.

**Observed:** Purple and pale-lilac squares contain stepped bars, checker fragments and offset horizontal stripes. They occupy only a handful of 90px grid cells, leaving most of the grid white; the closing panel hides their center so they peek around its edges.

**Transfer:** Create original computational patterns on the same square module. These ornaments remain part of the page even when product media is unavailable.

**Build:** Create 90px SVG tiles. Divide them into 6 or 8 equal subcells. Alternate electric-purple and lilac rectangles into checker corners, stepped diagonals or 6px-to-12px horizontal stripe groups. Assemble irregular clusters of 1–4 tiles on grid intersections; keep edges square and patterns unblurred.

### Soft lilac glow

**Use:** A small atmospheric counterpoint to the hard grid.

**Observed:** A diffuse lavender patch enters from the left behind a major capability headline; it has no visible boundary or glossy highlights.

**Transfer:** Use one restrained local wash to soften a technical chapter, not a page-wide neon fog.

**Build:** Place the Lilac atmosphere surface absolutely behind the chapter, with its left edge at -100px and overflow clipped by the section. Keep text and panels above it.

### Flat colored story illustrations

**Only for:** extended product overviews

**Use:** Large sequential product-story cards.

**Observed:** Each 1080px by 541px card splits into a white text half and a square pastel illustration half. Blue, lilac, mint, peach and pink backings carry cropped oversized browser, runtime or service motifs. The artwork is flat, rectilinear and tonal, not photographic or volumetric.

**Transfer:** Use one simplified product concept per square, built from nested rectangles, small utility labels and cropped geometric motifs.

**Build:** Split a two-column card equally. On the colored half, layer two or three large rectangles in darker and lighter versions of its hue; add a white floating status strip and a few square edge bars. Clip overflowing shapes at the panel edge.

### Company photography

**Only for:** company and recruitment pages

**Use:** Human context, culture and leadership.

**Observed:** Daylit office scenes with plants, sofas and candid working conversations have natural color and sharp rectangular edges. Company collages combine 360px and 180px squares on the 90px lattice. Portraits are square and front-facing; recruitment uses a looser wall of rectangular team and offsite images around centered text.

**Transfer:** Use real workplace and team imagery with natural light; preserve modular framing and avoid rounded portraits or dramatic studio grading.

### Icons

**Observed:** Feature icons are mostly 24px outline drawings in purple or black. Assurance and culture sections also use compact square pixel pictograms. Actions use narrow chevrons; comparison checks are 24px stroke SVGs with roughly 2.2px butt-ended strokes.

**Transfer:** Use simple technical line icons with consistent optical size. Reserve the pixel treatment for selected chapter markers and keep arrows visually lightweight.

## Section recipes

How recurring sections are built.

### First screen: Working-system opening

**Observed:** A 40px lilac Announcement strip sits above the 66px white navigation. Beneath it, the hero is about 615px tall. On white, a light 80px display headline takes roughly the left half and wraps across three lines including a purple-to-ochre outcome phrase. It begins one lattice column in and has a 720px measure; support copy is constrained to 540px, 32px below the heading. Primary button and Outline button follow after 40px with a 20px gap. At right, a 630px-wide Working-system schematic sits over a stepped gray lattice and purple patterned squares, extending beyond the viewport. By 900px the entire headline, support, actions, system object and start of the trust strip are visible; the process explanation lies below.

**Transfer:** Keep the left-promise/right-system balance for an ordinary landing page. Without product media, build the minimal schematic and Pixel lattice ornaments rather than leaving the right side empty. A text-first overview can center platform-display with two 70px actions and lattice corners; commercial pages use a 64px promise above aligned plan columns; company pages can use the green mission/photo split; recruitment centers the promise inside a photo wall.

**Avoid:** Do not replace the airy diagram with a dark full-width dashboard, center the default hero, or let support copy stretch to the full headline width.

**Text style:** `display` — Roobert 300 · 80px/1 · tracking -0.03em

### Trust strip

**Observed:** Centered overline text sits above a monochrome logo matrix, five columns by two rows. The chapter has 72px vertical padding and a lower hairline; a purple Documentation link style carries onward proof.

**Transfer:** Use verified proof appropriate to the product, preserving monochrome marks and a compact tracked caption rather than a wall of colorful badges.

### Three-step explanation

**Observed:** A heading-lg lead sits above Process-grid columns with 32px Step badges, step-heading titles, process-body text and 300px-wide interface fragments. The chapter has 80px top and bottom padding; titles and descriptions align across the row.

**Transfer:** Explain a brief real workflow. Use small, task-specific interface fragments under each step instead of repeating a full product screen.

### Capability chapter

**Observed:** A chapter lead with a short gradient-emphasized phrase precedes a joined Ruled panel composition. Panels alternate two equal columns and full-width text/media splits, with 90px inner padding, 40px feature-heading titles, body-lg paragraphs and Documentation links. Occasional Soft lilac glow washes sit behind the structure.

**Transfer:** Group capabilities by outcome and alternate visual density while retaining shared panel edges.

### Feature inventory

**Observed:** A chapter title and support line separated by 16px introduce a central 1080px grid of Feature items. Four columns use 40px gutters and 60px row gaps; a trust-oriented variant uses three wider columns and pixel pictograms. The chapter uses 120px vertical padding.

**Transfer:** Use short noun-led feature titles and one concrete explanatory sentence, keeping the whitespace between items rather than adding card backgrounds.

### Plainspoken proof

**Observed:** A support-size quote occupies a broad white stage among stepped lattice fragments. Attribution is an uppercase mono overline with a pale-blue text-sized background and roughly 40px separation. An overview variant pairs a larger quote panel with a square portrait and a mint attribution highlight.

**Transfer:** Use a genuine testimonial or a clearly attributed factual proof statement. Keep the quote typography conversational, not oversized decorative serif.

### Centered closing invitation

**Observed:** A roughly 818px-wide Ruled panel is staged within about 270px of vertical space above and below. Its inner padding is 90px; a centered closing headline, one short support line and a Primary button form the content. Pastel square ornaments extend around the panel.

**Transfer:** End a landing story with a short direct invitation and the same lattice vocabulary. A commercial variant uses a left-aligned 64px heading, lower support line and a 70px filled action aligned to the right edge.

### Offset directory ending

**Observed:** Square lattice fills a 901px-high frame. The Directory panel starts two 90px columns in and one row down, reaching the right edge; its six link columns have 40px gutters, 40px side padding and 90px top padding. Purple pixel clusters remain visible to the left and below. A white bottom strip places social links left and copyright right. This is the shared final treatment, whether preceded by a conversion panel, portrait proof, leadership cards or a listings notice.

**Transfer:** Retain the dark offset block, visible patterned edge and separate white utility strip. Reorganize link categories to match the new product rather than changing the silhouette.

### Mission and people

**Only for:** company pages

**Observed:** The opening pairs a 630px by 720px forest-green panel with a 64px white headline at top and 24px explanatory copy near the bottom, against a square-lattice field and a 540px by 630px office photo on the right. Later sections mix left editorial text with square photo fragments, a blue institutional-proof artwork field and three-column portrait cards. Leadership flows directly into the shared directory ending.

**Transfer:** Use this editorial variant to tell a company story with real people and credible institutional proof; keep the green hero localized.

### Culture and opportunities

**Only for:** recruitment pages

**Observed:** A centered 80px promise sits among candid team photographs, with a receding grid near the top. A staggered lattice of 361px-wide outlined principle cards follows; each has a square pixel icon, bold short title and paragraph. Four benefits columns precede a large heading and right-shifted grouped Listing rows. A short safety notice sits before the shared directory ending.

**Transfer:** Use the same progression for a community or talent proposition: emotional context, behavioral specifics, practical terms and a browsable action directory.

### Technical overview chapters

**Only for:** extended product overviews

**Observed:** A centered platform-display opening leads to sequential Flat colored story illustrations on Chapter off-white, then a 64px transition statement. Ruled technical chapters use 42px headings, 13px mono overlines, compact feature lists and line diagrams. An inverse assurance band, pale-blue control chapter and paired monitoring/integration panels vary the cadence. A lavender support lattice and attributed portrait quote lead into the shared directory ending.

**Transfer:** Use the long-form variant when a system needs multiple conceptual explanations, preserving distinct chapter materials rather than flattening them into a uniform card grid.

### Commercial comparison

**Only for:** pricing pages

**Observed:** A 64px left-aligned promise occupies a grid-backed opening above four plan columns. Shared ruled edges carry names, descriptions, tight price figures, filled actions and included features. Compute sections use 55px rows, small labels and a fading preview above an outlined expansion action. The full comparison uses aligned 270px columns, sticky plan names, checks, dashes and category headings. Open two-column FAQ answers precede a compact split closing call and the shared directory ending.

**Transfer:** Separate subscription terms from metered units, keep plan comparisons tabular, and answer practical objections in visible prose.

## Page flow

**Storyline:** Promise → approachable demonstration → credible proof → capability depth → practical reassurance → relevant action → architectural directory ending.

### General product landing

1. **Promise** — Asymmetric headline and working-system schematic with paired actions.
2. **Social proof** — Tracked trust line, monochrome marks and onward proof link.
3. **Product demonstration** — Three numbered steps and small interface fragments.
4. **Capability depth** — Compatibility band, joined capability panels, testimonial and unboxed feature inventories.
5. **Closing call** — Centered invitation framed by pastel squares.
6. **Directory** — Offset dark panel over patterned lattice.

**Transfer:** Lead with a clear outcome, reduce perceived effort through a simple process, then deepen the technical story.

### Company narrative

1. **Mission** — Green statement panel facing a daylit workplace photograph.
2. **Human context** — Editorial team paragraph and modular photo collage.
3. **Institutional proof** — Blue geometric backing and proof artwork.
4. **Credibility** — Square leadership portraits with simple name and role captions.
5. **Directory** — Shared dark offset ending, without an added conversion section.

**Transfer:** Prioritize people and credibility, using the same grid to hold warmer imagery.

### Talent and community recruitment

1. **Invitation** — Centered headline framed by candid team images.
2. **Behavioral proof** — Staggered outlined cards with pixel icons.
3. **Practical reassurance** — Four text-heavy benefit columns.
4. **Action directory** — Grouped outlined opportunity rows with locations and arrows.
5. **Reassurance** — Short safety notice.
6. **Directory** — Shared patterned dark ending.

**Transfer:** Move from aspiration to specific lived practices, then to opportunities and practical details.

### Deep product overview

1. **Promise** — Centered light headline and two large actions.
2. **Concept demonstration** — Sequential two-tone illustration cards.
3. **Capability depth** — Bordered technical chapters with diagrams and small labeled feature groups.
4. **Assurance** — Midnight and pale-blue trust chapters.
5. **Enablement** — Paired operational chapters and lavender support statement.
6. **Social proof** — Quote panel, tinted attribution and square portrait.
7. **Directory** — Shared offset ending, directly after proof.

**Transfer:** Let materials distinguish conceptual, operational and assurance content while preserving the grid.

### Commercial decision support

1. **Promise** — Grid-backed pricing headline.
2. **Pricing** — Four aligned plans with descriptions, figures and filled actions.
3. **Usage explanation** — Repeated compute summaries and expandable ruled tables.
4. **Comparison** — Long feature matrix with persistent plan headers.
5. **Objection handling** — Visible two-column FAQ.
6. **Closing call** — Compact split invitation and large action.
7. **Directory** — Shared offset ending.

**Transfer:** Expose units, inclusions and exceptions clearly instead of relying on decorative plan cards.

## Writing

Direct, technically literate and optimistic. Benefits are stated plainly, then supported with concrete mechanisms rather than theatrical claims.

**Do not copy:** Do not reuse Render names, logos, interface identifiers, customer marks, employee names, proprietary artwork, quotations, pricing, scale claims or funding figures. Examples illustrate verbal structure only.

- **Addressing the reader:** Speak to the reader as you and your. Use we for company commitments and the product name when explaining what the system does.
- **Rhythm:** Short sentence-case headlines mix with one- or two-sentence support blocks. Parallel phrases and compact lists create momentum; longer prose is reserved for practical explanations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name a fast path to a useful outcome; optionally end with a short highlighted object phrase. | 6–12 words | “Your fastest path to production for”<br>“Predictable pricing that scales with you.” |
| Chapter headline | Use a compact outcome, a plainspoken reassurance or a rhythmic phrase. | 3–9 words | “Click, click, done.”<br>“Stay secure and resilient by default” |
| Supporting line | Connect a capability to a reader outcome with a concrete range or reduction in effort. | 10–24 words | “Intuitive infrastructure to scale any app or agent from your first user to your billionth.”<br>“Ship software faster with integrated primitives that just work.” |
| Primary action | Start with a verb and say what happens next; remove perceived commitment when truthful. | 2–6 words | “Start for free”<br>“Explore open roles” |
| Feature description | State the mechanism and its operational benefit in one sentence. | 10–25 words | “Keep internal traffic off the public internet without VPC complexity.” |
| Practical question | Ask the reader's literal operational question, without a teaser. | 4–16 words | “How does billing work?” |

**Words and phrasing to use:** build; ship; deploy; scale; fully managed; by default; without complexity; from prototype to production; reliable; control

**Avoid:** revolutionary magic; disrupt everything; limitless possibilities; synergy; unparalleled excellence

**Rules:**

- Lead with what the reader accomplishes; explain the technical mechanism immediately afterward.
- Keep feature titles noun-led and action labels verb-led.
- Use specialist vocabulary when it increases specificity, but do not pack the headline with acronyms.
- Use numerical claims only when they can be substantiated for the new product.
- Let warmth come from reduced effort and approachable rhythm, not jokes or exclamation marks.

## Do's and Don'ts

### Do

- Keep the default hero at 80px/1 and weight 300 with a short colored continuation.
- Use 1px #e3e3e3 separators to join panels into one structure.
- Stage ordinary feature text in a 1080px inner area with 40px column gutters.
- Use 48px square-cornered actions with 24px horizontal padding.
- Give major feature inventories 120px vertical padding and 8px title-to-body gaps.
- Include crisp 90px lattice-based pixel ornaments and a dark offset directory ending.
- Keep product diagrams white, fine-lined and smaller than a full dashboard.
- Use 14px uppercase mono labels for compact proof and attribution.

### Don't

- Do not turn light geometric headlines into bold condensed display type.
- Do not round the standard buttons or panels into pills or soft tiles.
- Do not add floating-card shadows; depth comes from overlap, rules and restrained atmosphere.
- Do not use electric purple as the default large page background or primary button fill.
- Do not apply the forest-green company opening to an ordinary product landing.
- Do not turn the technical overview's pastel illustration fields into every section's background.
- Do not wrap each feature inventory item in its own bordered card.
- Do not replace the tall dark directory with a shallow centered footer bar.

## Motion and responsive

### Motion

**Observed:**

- Declared action color transitions use 0.3s cubic-bezier(0.4, 0, 0.2, 1); navigation uses 0.15s with the same curve.
- Button label transforms declare 0.3s cubic-bezier(0.4, 0, 0.2, 1). Some transforms declare 0.35s cubic-bezier(0.8, 0.01, 0.11, 0.98).
- The extended product overview declares sticky chapter headings and sequential story cards. Footer links declare white hover and active text.
- Reduced-motion utility classes set button-label transform duration to 0s.

**Transfer:**

- Use the declared brief color transitions for hard-edged controls; keep the resting square geometry unchanged.
- For long overview stories, use sticky card staging to focus on one concept at a time rather than animating every feature.

**Unknown:**

- The exact headline-continuation animation, runtime sequencing and scroll timing are not established.

### Responsive

**Observed:**

- CSS includes 640px, 768px and 1024px layout breakpoints among others.
- The hero action group declares a vertical stack below the medium breakpoint. Feature grids declare two columns at medium widths and four at larger widths.
- Commercial tables declare a minimum width of 800px; product-story cards declare one column before their two-column desktop layout.

**Transfer:**

- On narrow layouts, place the hero schematic after the promise and actions; preserve a few edge tiles rather than shrinking the whole desktop composition.
- Reduce feature collections to two columns then one, preserving unboxed items and joined-panel edges.
- Keep commercial data aligned and horizontally scrollable rather than squeezing every plan into narrow cells.

**Unknown:**

- Mobile rendering, exact small-screen grid-cell sizes and navigation behavior have not been visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
