# Avoice — work framed in lime

## Overview

A businesslike grotesk identity with a sharp fluorescent edge, suited to substantial workflow software and professional services. White and pale gray catalog sections alternate with deep blue-black product chapters and a true-black closing area. Architectural photography, white interface vignettes and small technical diagrams make the product feel tangible; spacious marketing compositions contain deliberately dense demonstrations.

### Essentials

- The opening is a paired working exhibit, not a centered slogan: two 668px square panels separated by 16px, a dark chamfered promise on the left and a photographic product demonstration on the right.
- Headlines compress rather than shout through size alone: Aspekta at weight 650, 48px/0.95 and -0.025em for the uppercase opening, with sentence-case 56px/0.98 and -0.035em for dark chapters.
- Fluorescent lime behaves like a highlighter: #cdfe00 fills a 44px announcement strip and compact actions, with occasional diagram backing; white, gray and dark neutrals occupy most of the page.
- Conversion controls are smooth lozenges against hard-working content: 44px default height, 9999px radius, 14px/20px weight 550 type and 24px side padding; the opening action grows to 48px.
- Product imagery is always staged: a white working panel over environmental photography or a pastel field, with small statuses and selected rows. When no finished interface exists, construct a believable single-workflow vignette rather than substituting abstract blobs.
- Keep a visible engineered detail and a monumental ending: a 44px diagonal cut with a lime seam in the promise panel, plus a centered uppercase 72px closing line and lime action above a ruled, multi-column black footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fluorescent lime | `#cdfe00` | `--color-lime` | accent, action, background | Announcement ribbon, primary actions, selected controls and isolated diagram fields. |
| Pressed lime tone | `#b9e600` | `--color-hover-lime` | action | Hover background for lime primary actions. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool card hover | `#dfe9f5` | `--color-hover-card` | surface | Hover and focus-visible fill of feature catalog cards. |
| Powder-blue stage | `#dceaf8` | `--color-stage-blue` | surface | Pale backing for white product panels; used in dark capability chapters and product demonstrations. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, interface panels and headings on dark sections. |
| Working gray | `#f1f1f1` | `--color-card` | surface, background | Feature cards and alternate editorial bands. |
| Light hairline | `#e6e7e8` | `--color-rule` | border | Navigation edge, editorial grids and plan dividers. |
| Secondary on black | `#999999` | `--color-inverse-secondary` | text | Visible result of white at 60% on black, used for footer links; use the alpha recipe on other dark backgrounds. |
| Stone text | `#85898b` | `--color-muted` | text | Supporting copy, section labels and secondary details on white. |
| Faint on black | `#666666` | `--color-inverse-label` | text | Visible result of white at 40% on black for footer category labels and legal details. |
| Blue-black ink | `#0a1217` | `--color-ink` | text, background, action | Primary text on light surfaces; dark product chapters and the opening promise panel. |
| Closing black | `#000000` | `--color-black` | background | Closing call and footer; also the full canvas of executive-oriented landing pages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product-feature pages | Mint stage | `#d9efec` | `--color-stage-mint` | surface | Related-feature visual backings. |
| executive-oriented landing pages | Inset dark | `#071116` | `--color-capability-dark` | surface | Slightly lifted dark capability cards on black. |

## Typography

- **aspekta** — All marketing headings, copy, labels, actions and interface demonstrations. Contemporary compact grotesk with open counters, low-weight body copy and tightly tracked, heavier headlines. If unavailable, use **Inter**. Use variable weights 350–650 and preserve tracking; reserve 900 for oversized capability ordinals. Font stack: "aspekta", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-headline | aspekta | 650 | 72px | 1.5 | -0.025em, uppercase | size clamp(2.5rem, 6vw, 4.5rem) | Centered monumental final promise. |
| chapter-heading | aspekta | 650 | 56px | 0.98 | -0.035em | size clamp(2.25rem, 4.2vw, 3.5rem) | Dark capability chapter lead, wrapping into a compact two-line block. |
| opening-headline | aspekta | 650 | 48px | 0.95 | -0.025em, uppercase | size clamp(2rem, 3.5vw, 3rem) | Default paired-panel opening headline. |
| section-heading | aspekta | 650 | 48px | 1.5 | -0.025em | size clamp(2rem, 3.6vw, 3rem) | Light catalog heading below a small eyebrow. |
| card-heading | aspekta | 550 | 24px | 1.2 | -0.01em | fixed | Feature catalog card title. |
| lead | aspekta | 350 | 18px | 1.625 | normal | fixed | Opening supporting paragraph; white at 75% on dark or stone on white. |
| card-copy | aspekta | 350 | 18px | 1.5 | normal | fixed | One-sentence feature card benefit. |
| body | aspekta | 350 | 16px | 1.625 | normal | fixed | Explanatory copy and editorial card descriptions. |
| navigation | aspekta | 400 | 15px | 1.5 | normal | fixed | Main navigation labels. |
| action | aspekta | 550 | 14px | 20px | 0.025em, uppercase | fixed | Lime conversion buttons. |
| footer-link | aspekta | 350 | 14px | 20px | normal | fixed | Dense footer directory links. |
| eyebrow | aspekta | 450 | 12px | 16px | 0.1em, uppercase | fixed | Light-section label, separated from the heading by 12px. |
| media-tab | aspekta | 450 | 11px | 1.5 | 0.08em, uppercase | fixed | Media-stage category selector. |
| footer-label | aspekta | 450 | 11px | 1.5 | 0.1em, uppercase | fixed | Footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company-story pages | letter-art | aspekta | 450 | 144px | 1 | -0.08em | size clamp(5rem, 10vw, 9rem) | Single oversized initial in a lime graphic column. |
| executive-oriented landing pages | executive-headline | aspekta | 650 | 73.4px | 0.96 | -0.065em | size clamp(3rem, 5.1vw, 5.35rem) | Sentence-case business outcome in an unboxed black opening. |
| pricing pages | pricing-headline | aspekta | 650 | 72px | 0.9 | -0.035em, uppercase | fixed | Centered two-line plan introduction. |
| executive-oriented landing pages | metric | aspekta | 650 | 72px | 0.9 | -0.06em | size clamp(2.5rem, 5vw, 5rem) | Four-column numerical proof. |
| company-story pages | editorial-headline | aspekta | 450 | 64.8px | 0.93 | -0.05em, uppercase | size clamp(3rem, 4.5vw, 4.25rem) | Lighter, tightly compressed opening statement. |
| executive-oriented landing pages | ordinal | aspekta | 900 | 64px | 1 | normal | fixed | Lime two-digit ordinals anchored low in capability cards. |
| executive-oriented landing pages | executive-section | aspekta | 650 | 60.5px | 1 | -0.055em | size clamp(2.2rem, 4.2vw, 4.5rem) | Large benefit statements above rails and metrics. |
| product-feature pages | feature-headline | aspekta | 650 | 51px | 1.1 | -0.015em | size clamp(42px, 3.54vw, 51px) | Short problem-solving opening on white. |
| product-feature pages | related-heading | aspekta | 650 | 47.5px | 0.98 | -0.055em | size clamp(2.15rem, 3.3vw, 3.2rem) | Related-capabilities rail heading. |
| pricing pages | plan-heading | aspekta | 650 | 32px | 1 | -0.025em, uppercase | fixed | Plan names at the top of comparison columns. |
| product-feature pages | related-card-heading | aspekta | 650 | 25.9px | 1.05 | -0.04em | size clamp(1.4rem, 1.8vw, 1.72rem) | Compact title above related-feature demonstrations. |
| company-story pages | editorial-card-heading | aspekta | 400 | 24px | 1.25 | normal | fixed | Principle-card headings. |
| pricing pages | plan-action | aspekta | 550 | 14px | 20px | normal | fixed | Full-width dark pricing action. |
| product-feature pages | related-card-copy | aspekta | 350 | 13.4px | 1.55 | normal | fixed | Two- or three-line rail descriptions. |
| executive-oriented landing pages | metric-caption | aspekta | 600 | 11px | 1.3 | 0.025em, uppercase | fixed | Compact explanatory labels under metrics. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use one sans family across marketing and demonstrations; there is no contrasting editorial serif or marketing monospace.
- Weight 650 is the normal visual display weight even where CSS class names suggest black. Keep body copy notably lighter at 350.
- Uppercase belongs to the main paired opening, pricing introduction, closing line, labels and actions; sentence case dominates benefit chapters and product-feature openings.
- Preserve the unusually loose 1.5 line box for the light catalog and closing heading; do not substitute the tighter dark-chapter leading everywhere.

## Layout

**Density:** Airy marketing fields contain compact, credible working interfaces. Large section transitions coexist with 6px icon gaps and closely ruled directories.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Inline icon/label gaps and inset media-control padding. |
| 8px | Card heading-to-benefit spacing. |
| 12px | Eyebrow-to-section-heading spacing. |
| 16px | Paired opening panel gap and related-feature rail gap. |
| 24px | Container side padding and catalog grid gap. |
| 32px | Support-to-action separation and opening top padding. |
| 36px | Catalog card inset. |
| 40px | Catalog heading-to-grid separation and major navigation grouping. |
| 56px | Opening promise panel inset and footer directory vertical padding. |
| 64px | Light catalog section vertical padding. |
| 80px | Pricing content vertical padding and company-page horizontal inset. |
| 96px | Closing-call top padding and company editorial section vertical padding. |
| 112px | Dark capability chapter vertical padding. |
| 160px | Product-feature deep-dive chapter breathing room. |

### Containers and grids

- **marketing-container**: max width 1400px · side padding 24px. Centered default shell. At 1440px, content extends from 44px to 1396px.
- **paired-opening**: 2 columns · gap 16px. Equal-width square promise and product stage; 668px each at desktop.
- **feature-catalog**: 3 columns · gap 24px. Equal-width tall cards arranged in rows; card width 435px at desktop.
- **footer-directory**: 5 columns · gap 24px. Five directory columns to the right of a 200px identity block, separated from that block by 40px.
- **pricing-comparison** (only for pricing pages): max width 840px · 2 columns · gap 0px. Narrow, centered shared comparison enclosure.
- **editorial-container** (only for company-story pages): max width 1600px · side padding 80px. Thin vertical frame rules and full-width joined-cell grids.
- **product-detail-container** (only for product-feature pages): max width 1328px · side padding 24px. Slightly narrower split narratives, with 1280px usable width at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | catalog-cards | 8px |
|  | hero-media | 35.2px |
|  | chamfer-surface | 24px |
|  | demo-panels | 12px |
| product-feature pages | related-cards | 6px |
| executive-oriented landing pages | capability-cards | 24px |
| pricing pages | comparison-bottom | 28.8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-demo | `0px 18px 44px 0px rgba(10, 18, 23, 0.1)` | White demonstration panel over a pale stage. |
| hero-overlay | `0px 24px 80px 0px rgba(0, 0, 0, 0.34)` | Large white working panel over environmental photography. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #ffffff; color: #0a1217`

**Observed:** Light outer space separates substantial framed content.

**Transfer:** Keep the default light even when a page includes dark chapters.

#### Dark chapter · level 0

**Use:** Capability deep dives.

**CSS:** `background: #0a1217; color: #ffffff`

**Observed:** A broad uninterrupted band holds pale-blue feature blocks, diagrams and unboxed explanatory text.

**Transfer:** Use for the detailed proof portion rather than making every card dark.

#### Closing ground · level 0

**Use:** Final action and full directory.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** True black differs subtly from the blue-black product chapter; hairlines are white at 10%.

**Transfer:** Maintain one continuous closing ground through the legal row.

#### Chamfered promise · level 1

**Use:** Left opening panel.

**CSS:** `background: #0a1217; border-radius: 24px; clip-path: polygon(44px 0px, 100% 0px, 100% 100%, 0px 100%, 0px 44px)`

**Observed:** The upper-left corner is cut diagonally; a short lime seam sits along that edge. Other corners remain rounded.

**Transfer:** Build the cut on a separate background layer so copy remains unclipped.

#### Catalog card · level 1

**Use:** Capability catalog.

**CSS:** `background: #f1f1f1; border-radius: 8px; padding: 36px`

**Observed:** Matte, flat and unoutlined; title above a short benefit, a miniature working scene lower down.

**Transfer:** Use sparse text and a visibly purposeful demonstration.

#### Glass media controls · level 2

**Use:** Controls inside photographic product stages.

**CSS:** `background: rgba(0, 0, 0, 0.4); border: 1px solid rgba(255, 255, 255, 0.15); border-radius: 28.8px; backdrop-filter: blur(12px); padding: 6px`

**Observed:** A low horizontal rail hugs the bottom of the media panel; pause is in a separate matching circle.

**Transfer:** Limit glass to media controls, not ordinary content cards.

#### Pastel demonstration stage · level 1

**Use:** Support a white interface against a colored field.

**CSS:** `background: #dceaf8; border-radius: 20px; padding: 40px`

**Observed:** Powder-blue backing is restrained; a white panel does most of the visual work. Product-feature treatments also use mint and pale lavender.

**Transfer:** Choose a desaturated backing and keep shadows soft and localized.

## Components

### Primary button

**Use:** Main conversion action in navigation, opening and closing.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 6px; height: 44px; padding: 0px 24px; border: 1px solid transparent; border-radius: 9999px; background: #cdfe00; color: #0a1217`

**Text style:** `action` — aspekta 550 · 14px/20px · tracking 0.025em · uppercase

**Observed:** Navigation includes a small right arrow. Opening uses a 48px height; closing uses 28px side padding and no arrow.

**States:** Declared: hover background #b9e600; focus-visible border-color #0a1217; active translate 0 0.

**Transfer:** Repeat one primary action consistently rather than inventing competing conversion styles.

### Main navigation

**Use:** Persistent top-level wayfinding.

**CSS:** `height: 81px; border-bottom: 1px solid #e6e7e8; background: #ffffff; position: sticky; top: 0px; z-index: 50`

**Text style:** `navigation` — aspekta 400 · 15px/1.5

**Observed:** Wordmark on the left, six modest links in a horizontal group, lime action pushed to the far right. Dropdown triggers carry small chevrons. A 40px utility strip sits above it on entry; that strip is not retained during scrolling. Executive-oriented pages invert the header to black and white.

**States:** Declared: hover opacity 0.6 on navigation labels; focus-visible underline with 6px underline offset on ordinary navigation links.

**Transfer:** Use a compact identity mark and a small navigation vocabulary.

### Feature catalog card

**Use:** Make multiple capabilities equally scannable.

**CSS:** `display: flex; flex-direction: column; position: relative; background: #f1f1f1; border-radius: 8px; padding: 36px; min-height: 400px`

**Text style:** `card-heading` — aspekta 550 · 24px/1.2 · tracking -0.01em

**Observed:** Heading, benefit, substantial open middle, then a white working vignette; a small right arrow sits at the bottom right. Whole card is a link.

**States:** Declared: hover background #dfe9f5; focus-visible background #dfe9f5.

**Transfer:** Keep title and benefit outside the demonstration so the marketing hierarchy stays readable.

### Media selector

**Use:** Switch the working demonstration in the opening.

**CSS:** `padding: 8px 14px; border: 1px solid transparent; border-radius: 22.4px; color: rgba(255, 255, 255, 0.75); background: transparent`

**Text style:** `media-tab` — aspekta 450 · 11px/1.5 · tracking 0.08em · uppercase

**Observed:** Four categories share Glass media controls. Selected category becomes white with dark text; a separate pause control is aligned beside the rail.

**States:** Declared: hover background white at 15% and color #ffffff.

**Transfer:** Use a few short categories, not a dense application tab bar.

### Footer link

**Use:** Deep product directory.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; color: rgba(255, 255, 255, 0.6)`

**Text style:** `footer-link` — aspekta 350 · 14px/20px

**Observed:** Links are left-aligned under small tracked category headings; 10px spacing separates list items.

**States:** Declared: hover color #ffffff.

**Transfer:** Group the new product's real information architecture rather than presenting a decorative link cloud.

### Announcement ribbon

**Use:** Thin highlighted research or launch hook above the header.

**CSS:** `height: 44px; background: #cdfe00; color: #0a1217; display: flex; align-items: center; justify-content: center`

**Observed:** Single compact centered sentence with an underlined claim, short report link and a tiny dark NEW badge.

**Transfer:** Present one useful timely item; keep the strip much shallower than the navigation.

### Plan action

**Only for:** pricing pages

**Use:** Conversion inside each plan column.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 0px 24px; border: 1px solid transparent; border-radius: 9999px; background: #0a1217; color: #ffffff`

**Text style:** `plan-action` — aspekta 550 · 14px/20px

**Observed:** Both plan columns receive the same dark, full-width pill with a small right arrow; lime is reserved for the switcher and badges.

**States:** Declared: hover ink background at 90%; focus-visible border-color #0a1217; active translate 0 0.

### Plan comparison

**Only for:** pricing pages

**Use:** Compare two related offers.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); max-width: 840px; border: 1px solid #e6e7e8; border-radius: 0px 0px 28.8px 28.8px`

**Text style:** `plan-heading` — aspekta 650 · 32px/1 · tracking -0.025em · uppercase

**Observed:** A centered three-way lime audience selector overlaps the top width. Each column has name, explanation, billing chip, Plan action, then ruled expandable inclusions; the more complete offer has a faint gray wash and small lime popularity badge.

**Transfer:** Preserve the shared enclosure instead of floating independent price cards.

### Related feature card

**Only for:** product-feature pages

**Use:** Horizontal cross-navigation rail.

**CSS:** `width: 372px; height: 520px; background: #f1f1f1; border-radius: 6px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `related-card-heading` — aspekta 650 · 25.9px/1.05 · tracking -0.04em

**Observed:** Small category, compact title, light description and uppercase explore link occupy the upper region. A pastel-backed white interface fills the lower region and is clipped at the bottom. Cards are separated by 16px and the last card bleeds past the right edge.

**Transfer:** Show neighboring capabilities, each illustrated with one focused action.

### Numbered capability card

**Only for:** executive-oriented landing pages

**Use:** Explain outcomes alongside a photographic demonstration in a rail.

**CSS:** `background: #071116; border-radius: 24px; padding: 28px; width: 470px; height: 360px; display: flex; flex-direction: column`

**Text style:** `ordinal` — aspekta 900 · 64px/1

**Observed:** Small lime slash-number at top, white benefit title, muted short paragraph, then an oversized lime ordinal at the bottom. Black surrounds the cards.

**Transfer:** Use the large number as a chapter marker rather than a decorative statistic.

## Imagery and graphics

### Environmental product stage

**Use:** Signature opening media and selected capability scenes.

**Observed:** Contemporary buildings, transit spaces and interiors are photographed in natural or evening light. A large rounded white working interface overlays the photograph, nearly filling it; the environment remains visible at the edges. The background is darkened especially near the bottom control rail.

**Transfer:** Use photography of the new product's real working environment, with a focused white interface or process artifact floating in front. Minimum version: one good contextual photograph and a carefully typeset single-task card.

**Build:** Fill a square rounded media frame with object-fit cover photography. Add a black overlay fading from about 15% at top through 10% in the middle to 45% at bottom. Center a white rounded panel at roughly four-fifths of the frame width with a 0px 24px 80px rgba(0,0,0,0.34) shadow; place Glass media controls below it.

### Miniature working scenes

**Use:** Feature catalog cards, related-feature rails and pale demonstration stages.

**Observed:** Small white panels show believable task lists, document clauses, progress bars, message rows or fee summaries. Status chips and tiny images give context; surfaces are softly rounded, with pale blue, mint or lavender behind them. Most color inside the interface is low saturation.

**Transfer:** Construct one recognizable workflow with a few legible rows and a single highlighted state. Keep marketing text outside the UI; do not enlarge all interface labels to body-copy size.

**Build:** Use a white panel with 12px radius, a faint rgba(10,18,23,0.09) edge and restrained shadow. Stack a title row, 3–5 ruled content rows, short gray metadata, small pastel chips and one dark or lime action. Place it over a flat desaturated field; clip the bottom in rail cards.

### Technical artifact and diagram

**Use:** Signature proof device within a dark capability chapter.

**Observed:** A black-and-white plan is mounted on bright lime, while a pale-blue adjacent block contains white diagram panels linked by fine lines. The artifacts read as work being inspected or kept in sync, not general decoration.

**Transfer:** Use the new product's equivalent technical artifact: a schematic, annotated document, structured record or dependency graph. The minimum is a crisp monochrome diagram on lime paired with a white linked-record diagram on powder blue.

**Build:** Create an SVG with a white central document and thin #0a1217 strokes; surround it with #cdfe00 side fields. For the linked diagram, use three or four white rounded rectangles on #dceaf8, connect them with 1px rgba(10,18,23,0.12) orthogonal lines and accent one successful result with a compact dark chip.

### Outcome data art

**Only for:** pricing pages

**Use:** Large quantified proof carousel.

**Observed:** A dark rounded slab is split between a written outcome and giant lime percentage on the left and a fine square-grid diagram on the right. The diagram uses muted gray versus lime blocks and a curved lime arrow. A four-cell metric selector anchors the bottom; its active cell is solid lime.

**Transfer:** Turn a substantiated outcome into a simple before/after diagram. Keep the numerical statement dominant, not a complex dashboard.

**Build:** Split a #0a1217 slab into two columns. On the right, draw a subtle 48px SVG square grid in rgba(255,255,255,0.06), with an inset dark rectangle. Add short rows of equal-width gray and lime blocks plus one curved arrow. Use a 128px lime numerical display as a design target, keeping the small uppercase caption beneath it.

### Vertical editorial collage

**Only for:** company-story pages

**Use:** Right half of the company opening.

**Observed:** Three narrow columns sit on ink: an outdoor tower photograph, a warm reflective interior photograph and a solid lime column with a giant dark initial. Their tops are staggered and their bottoms run into the panel edge.

**Transfer:** Use two richly specific photographs tied to the new organization's work plus one typographic column based on its own initial.

**Build:** On an ink half-width panel, inset a three-column grid in 0.85fr 1fr 0.7fr proportions with 12px gaps. Use tall object-fit cover images, translate the first and last columns downward, and fill the final column lime. Set its initial in the letter-art recipe.

### Icons

**Observed:** Small functional outline SVGs with round caps, normally 2px strokes. Navigation chevrons are 12px; action arrows are 16px; feature glyphs are about 20px, often on small tinted squares. Dark text and inverse white are the default paints.

**Transfer:** Use a consistent Lucide-like outline set for arrows, chevrons, pause, globe and workflow symbols; keep icon emphasis below the headline and product scene.

## Section recipes

How recurring sections are built.

### First screen: Paired working exhibit

**Observed:** The first screen starts with a 44px lime ribbon, a 40px utility row and an 81px navigation band. Under 32px of white space, two equal 668px square panels sit in the marketing-container with a 16px gap. Back-to-front on the left: Chamfered promise, short lime seam, then vertically centered copy inset 56px; the uppercase headline occupies about four compact lines, followed after 24px by a light support paragraph at 448px maximum width and after 32px by Primary button at 48px height. On the right, Environmental product stage layers photography, a white working panel, a dark lower scrim and Media selector. The headline, complete support, action and entire main object fit within the first 900px; social proof begins below.

**Transfer:** Make the same two-panel promise-and-working-proof composition for a new product, using its environment and a self-contained demonstration. If no media exists, build a credible single-task white panel over contextual photography. Pricing pages instead open with centered two-line capitals and a comparison beneath; company pages split lower-aligned white copy and Vertical editorial collage; product-feature pages use a white text column beside a pastel working stage; executive pages use unboxed sentence-case copy on black beside a powder-blue demo.

**Avoid:** Do not turn the default opening into centered text above a small browser mockup, stretch the copy across the whole dark card, or replace the chamfer with an arbitrary decorative blob.

**Text style:** `opening-headline` — aspekta 650 · 48px/0.95 · tracking -0.025em · uppercase

### Catalog heading pair

**Observed:** Eyebrow sits above section-heading by 12px, aligned to the left container edge; the feature grid follows after 40px. White surrounds flat Catalog cards in three columns with 24px gaps.

**Transfer:** Group a product's capabilities under one clear platform-level statement; let demonstrations supply detail.

**Text style:** `section-heading` — aspekta 650 · 48px/1.5 · tracking -0.025em

### Dark pain-to-capability chapter

**Observed:** Dark chapter begins with chapter-heading limited to 820px and 112px vertical inset. Below it, asymmetrical blocks pair pale-blue explanation-and-diagram surfaces with lime-backed technical artifacts and unboxed white benefit text.

**Transfer:** Introduce the familiar problem, then demonstrate distinct ways the product changes the work. Include Technical artifact and diagram rather than generic icon tiles.

**Text style:** `chapter-heading` — aspekta 650 · 56px/0.98 · tracking -0.035em

### Monumental closing and directory

**Observed:** On Closing ground, a centered closing-headline starts after 96px top padding, followed by Primary button after 32px and 80px lower padding. A white-at-10% top rule introduces the footer: identity, social link, outlined language lozenge and compact backing marker on the left; five columns of Footer link on the right. Directory padding is 56px vertically. A second rule separates the 32px-padded legal row, with copyright left and legal links right.

**Transfer:** Always retain the strong short closing line, single lime action and substantial directory. Adjust link counts and credibility details to the new product, without shrinking the ending into a generic one-line footer.

**Text style:** `closing-headline` — aspekta 650 · 72px/1.5 · tracking -0.025em · uppercase

### Ruled editorial grid

**Only for:** company-story pages

**Observed:** The opening gives way to a joined three-cell positioning strip. A long dark narrative band uses thin horizontal rules, small lime slash ordinals, left-side titles, occasional small photographs and longer paragraphs on the right. Later, a three-column by two-row backing grid and a five-column principle grid use 1px light rules and 28px cell padding.

**Transfer:** Use this editorial grammar for an organization's origin, credibility and operating principles, adapting the number of cells to the content.

### Pricing decision and reassurance

**Only for:** pricing pages

**Observed:** A centered pricing-headline has 0.9 leading and 28px separation before support. Plan comparison follows beneath its lime switcher. A wider outcome carousel then presents Outcome data art. Objection handling uses a narrow 900px outer container with 80px vertical padding, a short question-style heading and seven thin-ruled rows with lime circular plus controls.

**Transfer:** Move from offer fit to concrete value to practical buying questions; show the reader how to choose without relying on a giant price numeral.

**Text style:** `pricing-headline` — aspekta 650 · 72px/0.9 · tracking -0.035em · uppercase

### Product-feature deep dive

**Only for:** product-feature pages

**Observed:** A short feature-headline and explanation occupy the left side of a white opening; a tall lavender-backed working panel fills the right. Later chapters use 160px breathing room, a broad pale process scene, then split text/checklist and white-panel demonstrations backed by powder blue. Related feature card forms an overflow rail before the closing call.

**Transfer:** Explain one workflow in depth, then offer adjacent capabilities. Use diagrams for multi-step concepts and split rows for specific actions.

**Text style:** `feature-headline` — aspekta 650 · 51px/1.1 · tracking -0.015em

### Executive outcome rail and proof

**Only for:** executive-oriented landing pages

**Observed:** Black canvas carries executive-section headings above a horizontally clipped rail: a wide environmental demonstration, then Numbered capability card panels. A later four-column metric row has top and bottom white-at-12% rules, 72px figures and 11px uppercase captions.

**Transfer:** Pair operational demonstrations with business consequences; include only defensible numbers and let the ordinal cards carry qualitative benefits.

**Text style:** `executive-section` — aspekta 650 · 60.5px/1 · tracking -0.055em

## Page flow

**Storyline:** Promise → tangible working proof → capability or credibility chapters → decision support → monumental closing call and directory.

### Broad product marketing landing page

1. **promise** — Paired working exhibit with environment-backed demonstration.
2. **social proof** — Short trust statement beside four low-contrast logo tiles.
3. **capability catalog** — Eyebrow, platform heading and a three-column working-vignette grid.
4. **capability chapters** — Dark pain-to-capability chapter with asymmetric technical artifacts.
5. **closing call** — Monumental closing and directory on black.

**Transfer:** Start wide, make the product tangible, then deepen into a few concrete workflows.

### Company-story and trust page

1. **promise** — White lower-aligned manifesto beside a staggered photo-and-initial collage.
2. **positioning** — Three joined label-and-statement cells.
3. **origin narrative** — Long dark ruled rows with titles, paragraphs and small media.
4. **credibility** — Joined backing logo grid.
5. **operating principles** — Five narrow numbered cards on a gray band.
6. **closing call** — Shared black closing and full directory.

**Transfer:** Tell the organization's story through concrete work and commitments, using editorial framing rather than a conventional team-photo hero.

### Plan selection and buying reassurance

1. **promise** — Centered compressed uppercase invitation to find a suitable plan.
2. **pricing** — Audience switcher and two-column shared comparison.
3. **quantified proof** — Dark outcome panel with lime number, data art and metric tabs.
4. **objection handling** — Thin-ruled FAQ with small lime plus circles.
5. **closing call** — Shared black closing and directory.

**Transfer:** Explain offer structure and proven value before resolving purchasing questions.

### Audience-specific business outcome landing page

1. **promise** — Large sentence-case outcome on black, white chat-and-financial vignette on powder blue.
2. **capability demonstration** — Environmental working scene alongside dark numbered outcome cards.
3. **quantified proof** — Four white numerals in a ruled row with small uppercase labels.
4. **closing call** — Black closing and full directory continue the page's dark ground.

**Transfer:** Translate product work into audience-level outcomes without losing tangible operational proof.

### Single-feature product narrative

1. **promise** — Problem-solving text on white beside a tall pastel-backed workflow vignette.
2. **process demonstration** — Broad pale scene showing shared records and a connected process.
3. **capability chapters** — Split explanation/checklist and focused interface panels.
4. **cross-navigation** — Overflowing related-feature rail with tinted mini demonstrations.
5. **closing call** — Shared black closing and directory.

**Transfer:** Give one workflow room to explain itself, then bridge back to the larger platform.

## Writing

Confident and practically empathetic. The product speaks like a capable colleague who understands tedious professional work and can explain the relief in concrete terms.

**Do not copy:** Do not reuse Avoice's name, wordmark, proprietary interface contents, architectural assets, partner logos, customer counts, numerical performance claims or exact promotional slogans. Source examples illustrate phrasing, not claims available to a new product.

- **Addressing the reader:** Speak to the reader as you or your team. Use we for the organization's commitments and the product name as the actor doing specific work.
- **Rhythm:** Short benefit headlines alternate with compact explanatory paragraphs. Lists of concrete work create momentum; contrast pairs and three-part statements carry business benefits. Capitals are visual treatment, not an excuse for excited punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Define the category and audience, or name the repetitive problem to remove. | 3–10 words | “The AI operating system for architecture practices”<br>“Stop chasing status” |
| Capability benefit | Specific work noun plus a plain-language improvement, often with a time or friction contrast. | 4–9 words | “Specs that stay in sync”<br>“More work, same team” |
| Supporting line | Name real tasks, then explain the practical result rather than describing a technology stack. | One or two sentences | “Compliant specs, in an afternoon.”<br>“Handle every workflow with the attention to detail the profession demands.” |
| Primary action | Short verb-and-object instruction; repeat it consistently. | 2–3 words | “Book a demo”<br>“Get pricing” |
| Objection handling | A direct question the buyer would actually ask. | 5–14 words | “Can I add or remove seats?”<br>“Who owns our project data, and is it used to train AI?” |

**Words and phrasing to use:** work; team; built for; keep; protect; clear; one place; without; before; busywork

**Avoid:** revolutionary; magical; game-changing; unleash limitless potential; frictionless synergy

**Rules:**

- Lead with work the user recognizes, then the relief or outcome.
- Prefer active verbs and named artifacts to vague productivity language.
- Use concrete contrasts: fewer handoffs, before issue, same team, one source.
- Treat privacy, pricing and professional care plainly; do not hide them behind enthusiasm.
- Keep short card descriptions independent from tiny demonstration text.

## Do's and Don'ts

### Do

- Use 48px/0.95 uppercase type for the default opening and weight 650 rather than an extra-heavy substitute.
- Keep the paired opening at a 16px gap and the capability catalog at a 24px gap.
- Inset the dark opening copy by 56px and limit its support paragraph to 448px.
- Make primary actions lime pills at 44px height, with a 48px opening variant.
- Use flat #f1f1f1 cards with 8px radii around white working vignettes.
- Introduce a deep #0a1217 chapter with pale technical demonstrations and lime highlighting.
- Keep directory text at 14px/20px and category labels at 11px with 0.1em tracking.
- End with the 72px uppercase closing line, one lime action and a continuous black directory. 

### Don't

- Do not make lime the default page canvas; its broad fills belong to shallow banners and bounded proof devices.
- Do not give all marketing cards the hero's 35.2px corners; catalog cards stay at 8px.
- Do not use shadow-heavy floating cards for the light catalog; elevation belongs to staged interfaces.
- Do not replace the 350-weight supporting copy with the same 650 weight as the headings.
- Do not introduce a serif or monospace eyebrow system; the identity uses one grotesk throughout.
- Do not use rainbow icons or bright illustration sets to compete with the lime controls.
- Do not apply glassmorphism to pricing or editorial cards; blur is concentrated in media controls.
- Do not turn footer headings into bright white body-size links; their subdued 11px capitals preserve the directory hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions include all .15s cubic-bezier(.4, 0, .2, 1); navigation color and opacity use 0.5s cubic-bezier(0.4, 0, 0.2, 1).
- Feature catalog fill changes use 0.2s cubic-bezier(0, 0, .2, 1).
- The opening media includes a pause control and category switching. Working scenes declare short draw/pop entrances, progress-line movement and slow photographic zooms.
- Header transition classes include a reduced-motion transition-none variant.

**Transfer:**

- Keep motion concentrated in demonstrations: reveal a record, draw a connection, change a selected state. Preserve a still, readable headline and action.
- For rotating hero demonstrations retain explicit category controls and pause.
- Use the declared short color transitions for buttons and cards rather than elastic whole-page effects.

**Unknown:**

- Exact slideshow interval, scroll-trigger sequence and choreography are not established.

### Responsive

**Observed:**

- Shared CSS includes 640px, 768px and 1024px breakpoints; the opening media declares a portrait 3/5 aspect below 641px and square above it.
- The catalog declares one column by default, two at medium widths and three at large widths. The desktop navigation appears at large widths.
- Footer directory declares two columns by default, three at small widths and five at large widths.

**Transfer:**

- Stack promise and working proof on narrow screens while preserving the chamfer and lime seam; let the media become portrait without squeezing its interface.
- Use the supplied clamped headline recipes, and reduce columns before shrinking card content.
- Keep related-feature rails horizontally navigable instead of crushing every card into a narrow grid.

**Unknown:**

- Mobile menu construction, exact narrow-screen spacing and touch behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
