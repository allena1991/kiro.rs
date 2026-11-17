# Tailscale — human-scale technical confidence

## Overview

Approachable infrastructure marketing with warm off-white space, charcoal typography and compact, practical controls. Medium-weight grotesk headlines sit beside tiny monospaced labels, while white product stages, blue demonstration panels and colorful grids make complex software tangible. It suits technical platforms that need both developer credibility and broad organizational trust; the overall density is spacious around the story and purposeful within the proof.

### Essentials

- Plainspoken monumental headlines, not heavy display bravado: Inter 64px/1.1, weight 500, -0.01em tracking, centered over a 768px support measure.
- A promise gives way to a working object: 64px desktop gutters, a centered action pair, then a five-part selector and a 1312px white product stage with 32px corners; the object is a legible interface or device, not abstract spectacle.
- Small rectangular actions keep the technology approachable: 36px height, 8px corners, 8px 12px padding, 16px/1 medium type; pills are reserved for filters.
- Warm paper carries most of the story: #f9f7f6 canvas, #ffffff cards, #eeebea hairlines and almost invisible 0px 4px 8px shadows at 2% ink. Color is concentrated in a selected tile, a blue demonstration chapter and the media, not every section.
- Proof is physical and repeatable: oversized 64px metrics in white cards, restrained customer marks, and a field of 72px icon tiles on a 12px gap interrupted by a larger editorial tile. Include this modular field; use platform symbols or genuine workflow categories when partner media is unavailable.
- Technical markings and a substantial closing invitation bookend the friendly prose: uppercase MD IO labels at 12–14px with 0.05em tracking, then a charcoal 32px-radius band with a white 48px/1.1 statement and inverted compact actions.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Selected product red | `#d04841` | `--color-red` | accent, surface, text | Active product category tile, matching eyebrow and geometric list bullets. |
| Demonstration blue | `#5a82de` | `--color-blue` | accent, text, background | Blue chapter top stop, technical icons and use-case eyebrows. |
| Demonstration blue deep | `#324994` | `--color-blue-deep` | background | Blue chapter bottom stop and institutional illustration panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action black | `#1f1e1e` | `--color-action` | action, text | Primary buttons, selected filters and text links. |
| Deep ink | `#181717` | `--color-ink` | text | Product-stage titles and pricing headings. |
| Charcoal | `#2e2d2d` | `--color-heading` | text, surface | Default headline ink, announcement bar and closing band. |
| Secondary gray | `#575555` | `--color-muted` | text | Visible secondary text on paper, using #2e2d2d at 80% opacity. |
| Caption gray | `#706e6d` | `--color-caption` | text | De-emphasized headline clauses, secondary marks and small notes. |
| Soft control edge | `#e3e1e0` | `--color-pill-edge` | border | Visible edge of 10% #1f1e1e over warm paper; controls use the alpha recipe. |
| Warm hairline | `#eeebea` | `--color-rule` | border | Card outlines, section rules and footer label extensions. |
| Warm paper | `#f9f7f6` | `--color-canvas` | background | Default marketing canvas and edge fades. |
| White | `#ffffff` | `--color-white` | surface, text | Cards, navigation, footer and inverted text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Advanced-plan ochre | `#bb5504` | `--color-plan-orange` | text, accent | Advanced tier's mono highlights. |
| pricing pages | Entry-plan green | `#09825d` | `--color-plan-green` | text, accent | First tier's mono highlights and geometric marker. |
| pricing pages | Enterprise purple | `#995fc3` | `--color-plan-purple` | text, accent | Enterprise tier's mono highlights. |
| institutional pages | Investor green | `#0d4b3b` | `--color-forest` | background | Investor proof band. |
| institutional pages | Institutional navy | `#19224a` | `--color-navy` | background | Full-width principles chapter. |
| institutional pages | Deep teal forest | `#082429` | `--color-forest-dark` | background | Candid team-photo chapter. |
| pricing and institutional pages | Institutional charcoal | `#232222` | `--color-panel-dark` | surface, text | Recommended-plan cap and institutional closing panels. |
| institutional pages | Institutional stone | `#afacab` | `--color-stone` | surface, text | Muted closing headline clause and lower demo-action panel. |

## Typography

- **inter** — All marketing headings, paragraphs and controls; institutional pages use the same Inter family under a generated family name. Modern, high-x-height grotesk; medium rather than bold display weights and compact counters. Font stack: "inter", ui-sans-serif, system-ui, sans-serif.
- **mdio** — Uppercase technical eyebrows, footer headings, announcement text and plan labels. Compact technical monospace that acts like an equipment marking rather than a code-heavy theme. If unavailable, use **IBM Plex Mono**. Use weight 500 and retain 0.05em tracking. Font stack: "mdio", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | inter | 500 | 64px | 1.1 | -0.01em | fixed | Default hero, major centered chapters and proof numerals. |
| heading-lg | inter | 500 | 48px | 1.1 | -0.01em | fixed | Product-stage title, split use-case hero and closing statement. |
| heading | inter | 500 | 36px | 1.1 | -0.01em | fixed | Capability-grid headings, FAQ titles and product-promotion titles. |
| heading-sm | inter | 500 | 32px | 1.1 | -0.01em | fixed | Split feature chapters and editorial tile headings. |
| title | inter | 500 | 20px | 1.2 | -0.01em | fixed | Hero support, feature-card titles and FAQ summaries. |
| body | inter | 400 | 16px | 1.5 | -0.01em | fixed | Paragraphs, testimonials and feature explanations. |
| button | inter | 500 | 16px | 1 | -0.01em | fixed | Compact conversion buttons and underlined action links. |
| navigation | inter | 500 | 14px | 1.5 | -0.01em | fixed | Primary navigation and footer links. |
| filter | inter | 500 | 14px | 1 | -0.01em | fixed | Audience filters and category pills. |
| eyebrow | mdio | 500 | 14px | 1 | 0.05em, uppercase | fixed | Product-stage labels and use-case identifiers. |
| micro-label | mdio | 500 | 12px | 1 | 0.05em, uppercase | fixed | Footer group headings and small technical markers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| institutional pages | institutional-display | inter | 500 | 72px | 1.18 | -0.03em | size calc(60.8px + 0.878904vw) | Editorial two-column opening. |
| institutional pages | institutional-heading | inter | 500 | 48px | 1.18 | -0.02em | size calc(40.5px + 0.585936vw) | Principles, people and closing chapters. |
| pricing pages | price | inter | 400 | 32px | 1.2 | -0.03em | fixed | Price amount and custom-price word. |
| pricing pages | plan-title | inter | 500 | 24px | 1.2 | -0.01em | fixed | Plan and extension-card titles. |
| institutional pages | institutional-subhead | inter | 500 | 24px | 1.4 | -0.02em | size calc(20.3px + 0.292968vw) | Editorial commitments and values subheads. |
| institutional pages | institutional-lead | inter | 400 | 20px | 1.35 | -0.02em | size calc(16.9px + 0.24414vw) | Long-form opening support. |
| pricing pages | plan-ribbon | mdio | 500 | 16px | 1 | 0.05em, uppercase | fixed | Recommended-plan cap. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Default tracking stays at -0.01em across Inter sizes; this is not an aggressively compressed display system. Headlines are sentence case and weight 500.
- Institutional typography has looser leading and tighter tracking than the default. Its root size follows calc(13.5px + 0.195312vw); the scoped size formulas preserve that relationship.
- A muted first clause paired with a dark conclusion gives large headings two voices without changing family or weight.

## Layout

**Density:** Airy around narrative sections, with tightly fitted controls and repeatable proof modules inside them.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Adjacent filters, product categories and tight control gaps. |
| 12px | Tile-grid gaps, title-to-body gaps and FAQ vertical padding. |
| 16px | Feature grids, heading/support separation and answer paragraph gaps. |
| 24px | Hero text/action separation and stat-card internal rhythm. |
| 32px | Default card padding and section inset. |
| 36px | FAQ column gutter and chapter padding. |
| 48px | Footer vertical padding and closing-band horizontal inset. |
| 64px | Desktop side gutters, major section padding and separation before the product selector. |
| 72px | Default opening top padding. |
| 96px | Breathing room after the modular icon field. |
| 160px | Long-form institutional editorial chapter padding. |
| 176px | Institutional opening padding and people-section lead-in. |

### Containers and grids

- **Marketing container**: max width 1440px · side padding 64px. Centered outer container yields 1312px usable width at desktop. Major proof and blue chapters sometimes inset another 32px.
- **Hero support measure**: max width 768px. Centered introductory support, subordinate to the headline.
- **Proof grid**: 3 columns · gap 8px. Three equally weighted stat cards; each about 411px wide.
- **Feature grid**: 3 columns · gap 12px. White capability cards with left-aligned text.
- **Split chapter**: 2 columns · gap 16px. Approximately equal media and text halves; media around 648px wide, text inset 32px.
- **FAQ columns**: 2 columns · gap 36px. Two independent vertical lists rather than one full-width accordion.
- **Plan grid** (only for pricing pages): 4 columns · gap 12px. 320px cards with shared row alignment and recommended cap.
- **Institutional prose** (only for institutional pages): max width 534px. Long-form text beside a small abstract symbol inside a centered editorial rail.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Buttons | 8px |
|  | Cards and media | 16px |
|  | Product stage and closing band | 32px |
|  | Audience filters | 9999px (pill) |
| institutional pages | Portraits | 50% |
| institutional pages | Institutional closing panels | 14px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Paper lift | `0px 4px 8px 0px rgba(24,23,23,0.02)` | White cards and product stages; separation is primarily supplied by the hairline. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing page.

**CSS:** `background: #f9f7f6; color: #2e2d2d`

#### White card · level 1

**Use:** Proof, feature, quote and integration modules.

**CSS:** `background: #ffffff; border: 1px solid #eeebea; border-radius: 16px; box-shadow: 0px 4px 8px 0px rgba(24,23,23,0.02)`

**Observed:** Thin warm edges rather than strong elevation.

**Transfer:** Use the same material for different categories of proof.

#### Product stage · level 1

**Use:** Wide opening demonstration panel.

**CSS:** `background: #ffffff; border: 1px solid #eeebea; border-radius: 32px; padding: 64px; box-shadow: 0px 4px 8px 0px rgba(24,23,23,0.02)`

**Observed:** Short left copy rail and oversized right-hand device composition.

#### Blue demonstration chapter · level 1

**Use:** A concentrated colored chapter within the light page.

**CSS:** `background: linear-gradient(in oklab, #5a82de 0%, #324994 100%); padding: 64px 64px 0px; color: #ffffff`

**Observed:** Inside a 16px rounded wrapper; the gradient runs down behind a large light interface collage, followed by a white three-column benefit shelf.

**Transfer:** Make the chapter a functional demonstration, not an atmospheric interlude.

#### Charcoal invitation · level 1

**Use:** Default closing conversion surface.

**CSS:** `background: #2e2d2d; color: #ffffff; border-radius: 32px; padding: 64px 48px`

#### White footer · level 0

**Use:** Final navigation and legal baseline.

**CSS:** `background: #ffffff; padding: 48px 0px; margin-top: 64px`

#### Institutional color bands · level 0

**Only for:** institutional pages

**Use:** Broad editorial chapters.

**CSS:** `background: #19224a; color: #ffffff; padding: 93px 0px 128px`

**Observed:** A blue inner panel sits on navy; the photo chapter uses deep teal and investor proof uses forest green. Unlike the default page these are full-bleed color bands.

**Transfer:** Reserve broad dark-color fields for organizational storytelling.

#### Institutional invitation panels · level 1

**Only for:** institutional pages

**Use:** Paired closing artwork and device panels.

**CSS:** `background: #232222; border-radius: 14px; overflow: hidden`

**Observed:** Two equal panels with a 24px gap; the left combines geometric neutral artwork and an offer, above a stone-colored demo strip. The right holds a cropped phone.

## Components

### Primary button

**Use:** Default conversion control.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 8px 12px; gap: 4px; border: 1px solid transparent; border-radius: 8px; background: #1f1e1e; color: #ffffff`

**Text style:** `button` — inter 500 · 16px/1 · tracking -0.01em

**Observed:** A modest label-sized rectangle, often paired with an underlined sales link. In the charcoal invitation it inverts to white with dark text. Pricing also uses an unfilled 1.5px dark-outline variant for sales-led actions.

**Transfer:** Keep labels verb-led and fit the control to its text.

### Navigation item

**Use:** Primary navigation within a white 75px row beneath a 54px charcoal utility strip.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 10px 12px; border-radius: 8px; color: #181717`

**Text style:** `navigation` — inter 500 · 14px/1.5 · tracking -0.01em

**Observed:** Brand at left, centered menu, login and compact primary action at right; expandable menu labels end with a small plus rather than a chevron.

### Underlined action

**Use:** Secondary conversion and proof detail.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; padding: 4px 0px; color: #1f1e1e; text-decoration: underline; text-underline-offset: 4px`

**Text style:** `button` — inter 500 · 16px/1 · tracking -0.01em

**Observed:** Quiet text action without a surrounding outline; inverted to white in dark sections.

### Audience filter

**Use:** Change role-specific demonstrations or capability groups.

**CSS:** `background: #ffffff; color: #1f1e1e; border: 1px solid rgba(31,30,30,0.1); border-radius: 9999px; padding: 8px 12px; height: 36px`

**Text style:** `filter` — inter 500 · 14px/1 · tracking -0.01em

**Observed:** Centered wrapping row with 8px gaps. Selected state is charcoal with white text; it is not distinguished by accent color alone.

### Product category selector

**Use:** Connect the opening promise to a specific working demonstration.

**CSS:** `border-radius: 16px; padding: 24px; background: #d04841; color: #ffffff`

**Text style:** `body` — inter 400 · 16px/1.5 · tracking -0.01em

**Observed:** Five adjacent categories at desktop, each 256px by 150px. A small icon precedes a semibold label and a smaller explanatory line. Only the active category has a colored fill; the others rest directly on paper.

**Transfer:** Use short product modes or audience jobs; connect every mode to corresponding stage content.

### Metric card

**Use:** Quantified customer proof.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 32px; background: #ffffff; border: 1px solid #eeebea; border-radius: 16px; box-shadow: 0px 4px 8px 0px rgba(24,23,23,0.02)`

**Text style:** `display` — inter 500 · 64px/1.1 · tracking -0.01em

**Observed:** Customer mark, oversized result, concise explanation in title type and an Underlined action anchored low. All text is left aligned.

### Integration tile

**Use:** Dense but orderly ecosystem field.

**CSS:** `width: 72px; height: 72px; background: #ffffff; border: 1px solid #eeebea; border-radius: 16px; overflow: hidden; box-shadow: 0px 4px 8px 0px rgba(24,23,23,0.02)`

**Observed:** Full-color symbols are centered in square white cells; a larger four-cell-span editorial card interrupts the field.

### FAQ row

**Use:** Objection handling in independent columns.

**CSS:** `border-top: 1px solid #eeebea; padding: 12px 0px`

**Text style:** `title` — inter 500 · 20px/1.2 · tracking -0.01em

**Observed:** Native summary/details pattern, question left and 24px dark circular down-arrow affordance right. Final row has a bottom rule. Answers use body type and paragraph spacing, not new cards.

### Footer group

**Use:** Final resource navigation.

**CSS:** `display: flex; flex-direction: column; gap: 4px`

**Text style:** `navigation` — inter 500 · 14px/1.5 · tracking -0.01em

**Observed:** Four narrow link columns to the right of a separate brand-symbol area. Each column starts with Micro-label type and an extending hairline; links have 12px padding. A faint bottom baseline separates copyright from the legal notes.

### Plan card

**Only for:** pricing pages

**Use:** Comparable offers with vertically aligned content.

**CSS:** `display: grid; background: #ffffff; border: 1px solid #eeebea; border-radius: 16px; width: 320px; box-shadow: 0px 4px 8px 0px rgba(24,23,23,0.02)`

**Text style:** `plan-title` — inter 500 · 24px/1.2 · tracking -0.01em

**Observed:** 30px padded upper offer area contains title and geometric marker, description, price and action; a ruled lower area contains colored mono highlights and feature bullets. The recommended tier gains a charcoal ribbon and bottom endorsement, not a colored card body.

## Imagery and graphics

### Working product collage

**Use:** Primary working object in product stages and blue chapters.

**Observed:** Clean front-facing laptop, browser or app windows rather than perspective-heavy renders. A large application view is overlapped by a smaller status panel or login window, with soft local shadows. Device scenes occupy roughly two thirds of a wide white stage; the blue chapter surrounds a light multi-window composition.

**Transfer:** Show a real task with one main view and one meaningful supporting state. Without polished device art, use a crisp browser frame plus one cropped detail window on the same white stage; retain readable visual hierarchy.

### Modular ecosystem field

**Use:** Signature breadth-of-platform proof.

**Observed:** A dense rectilinear field of colorful app and platform symbols in white rounded tiles, 15 columns at desktop with 72px cells and 12px gaps; a 324px square text card replaces several cells toward the right.

**Transfer:** Use genuine integrations, compatible tools or illustrated workflow categories. Preserve the interruption by an editorial tile rather than presenting only a logo strip.

**Build:** Use CSS grid with repeat(15,72px), 72px rows and 12px gap. Place individual SVG symbols in White card tiles. Give the editorial tile a four-column and four-row span with 32px padding and a bottom-aligned Primary button. Reflow the field to fewer columns on narrow screens.

### Social proof rail

**Use:** Community endorsement chapter.

**Observed:** White quote cards about 400px wide with author/avatar and a small social-network mark; two-tone large heading above. The horizontal rail extends beyond the viewport, with 50px paper-colored edge fades.

**Transfer:** Use authentic customer language and attribution. Keep the clipping intentional and the cards readable, rather than shrinking them all to fit.

### Dark interface on blue backing

**Only for:** product-specific feature pages

**Use:** Split benefit chapters and broad product detail figures.

**Observed:** Flat dark dashboard or logs interface inset into a rounded deep-blue rectangular mat, with a soft brighter blue pool near the lower edge. Hero artwork overlaps one dark window over a light window with small blue geometric pieces and a fine perspective grid behind them.

**Transfer:** Use product-specific views rather than generic charts. A flat dark UI panel on a deep-blue mat with a subtle blue lower glow is the minimum equivalent.

**Build:** Create a 16px rounded mat with a navy-blue base and a bottom-centered radial blue glow. Inset the app rectangle on all sides, keeping the top and bottom margin visible. For the hero, layer two front-facing panels, offset the lighter panel up and right, add a few circles, squares and quarter-circles in blue, and a low-opacity SVG perspective grid beneath. Match the restrained glow; exact stops are not essential.

### Geometric institutional symbols

**Only for:** institutional pages

**Use:** Values, principles and closing offer artwork.

**Observed:** Simple circles, open rings, bars, quarter-circles and dot-matrix pictograms. On blue they are subdued pale gray and dark blue; editorial symbols use muted warm and green dots. Closing artwork uses oversized neutral circles and quarter-circles against charcoal.

**Transfer:** Choose small geometric metaphors appropriate to the new organization; keep the geometry sparse and matte.

**Build:** Construct SVG circles and rectangles on an equal-cell grid. For dot pictograms, repeat equal-radius circles at regular center spacing and omit cells to form a silhouette. For closing art, stack two circles beside quarter-circle blocks, using stone and caption gray on charcoal; clip the sculpture at the panel edge.

### Human photography

**Only for:** institutional pages

**Use:** Team culture and named-person proof.

**Observed:** Candid, naturally lit group photographs in a varied-height mosaic against deep teal, with modest rounded corners. Formal directories use 150px circular portraits, centered names and roles; small affiliation marks can overlap the upper-right edge.

**Transfer:** Mix real social scenes and individual portraits. Preserve natural color and varied settings rather than applying a uniform dramatic grade.

### Icons

**Observed:** Mostly 16px outline icons with 2px round strokes; navigation plus signs are 14px with approximately 1.2px strokes. Feature icons are 24px and often blue. Small geometric bullets use the active category accent.

**Transfer:** Choose simple rounded outline symbols for actions and features; keep full-color solid logos confined to proof fields and integration tiles.

## Section recipes

How recurring sections are built.

### First screen: Promise to working object

**Observed:** A sticky two-tier header occupies 129px, charcoal utility strip behind white navigation. On warm paper the centered 64px Display headline is arranged in two balanced lines across most of the content width, starting after 72px of top space. A 768px centered support paragraph follows after 24px, then the compact Primary button and Underlined action after another 24px. After 64px of breathing room, the five-part Product category selector spans the width. Immediately beneath it sits the White Product stage: text left, large laptop and floating status view right. Within the first 900px the headline, full support, actions, selector and top of the main object are visible; most of the device and detailed benefits continue below the fold.

**Transfer:** Preserve the promise-to-selector-to-working-object relationship without requiring the same number of product modes. Substitute a front-facing browser and meaningful detail panel if there is no device illustration. Product-specific pages instead open with a left eyebrow, 48px headline, body, action and small logo row beside overlapping interfaces. Pricing opens with a two-tone 64px heading above comparable offers. Institutional stories open on white with a 72px left statement and a right prose column.

**Avoid:** Do not replace the working object with a giant abstract orb, center everything inside a dark full-screen hero, or enlarge the compact buttons into pill-shaped banners.

**Text style:** `display` — inter 500 · 64px/1.1 · tracking -0.01em

### Quantified proof

**Observed:** Two-line centered Display heading, often a muted introductory clause over a dark conclusion. Metric cards in a three-column Proof grid follow, then low-contrast customer marks in 193px by 72px outlined cells.

**Transfer:** Use a few independently meaningful outcomes and cite their context; combine a numerical result with an explanation, not a naked dashboard of counters.

**Text style:** `display` — inter 500 · 64px/1.1 · tracking -0.01em

### Colored working chapter

**Observed:** Blue demonstration chapter inside an inset rounded wrapper: white Display heading and support, Audience filters, broad light product collage, then a white shelf of three icon-led benefits.

**Transfer:** Give the accent chapter a specific task to explain. Use tabs to change meaningful use contexts and carry the product story into the benefit shelf.

**Text style:** `display` — inter 500 · 64px/1.1 · tracking -0.01em

### Capability matrix

**Observed:** Centered 36px heading and support, Audience filters after 32px, then a three-column Feature grid. White cards use 32px padding, 20px titles and 16px body, with no oversized decorative numerals.

**Transfer:** Group capabilities by actual audience needs and keep title and explanation together.

**Text style:** `heading` — inter 500 · 36px/1.1 · tracking -0.01em

### Community and ecosystem proof

**Observed:** Social proof rail combines conversational quotes with a two-tone Display heading. Modular ecosystem field makes a denser visual counterpoint and contains its own 32px heading and Primary button.

**Transfer:** Use testimony for lived experience and the symbol field for breadth; they need not be adjacent.

**Text style:** `display` — inter 500 · 64px/1.1 · tracking -0.01em

### Questions in two columns

**Observed:** 36px section title, sometimes a left-aligned category heading, then two 638px FAQ lists separated by 36px. Each FAQ row expands in place, retaining its thin ruled construction.

**Transfer:** Use buyer questions in plain language and group long FAQ collections by topic.

**Text style:** `heading` — inter 500 · 36px/1.1 · tracking -0.01em

### Closing invitation and footer

**Observed:** Charcoal invitation is 1312px wide and about 234px tall, with a left-aligned 48px statement spanning roughly half the width and inverted actions at right. White footer follows after 64px: brand-symbol area, four columns with mono labels and links, then small copyright and legal notes on a faint baseline. Pricing substitutes a centered 32px final question and underlined sales sentence for the charcoal band.

**Transfer:** Close the narrative with a concrete next step before the resource navigation. Keep the pricing ending lighter and service-oriented.

**Text style:** `heading-lg` — inter 500 · 48px/1.1 · tracking -0.01em

### Split feature explanation

**Only for:** product-specific feature pages

**Observed:** Alternating text and media halves, 16px gutter, 32px section padding. Text has a small blue icon, 32px heading, body and compact Primary button. Media is a Dark interface on blue backing. A broad centered 36px heading and full-width detail figure can punctuate the splits.

**Transfer:** Alternate the media side to avoid a monotonous stack; each split should answer one concrete user problem.

**Text style:** `heading-sm` — inter 500 · 32px/1.1 · tracking -0.01em

### Offer and comparison

**Only for:** pricing pages

**Observed:** Four Plan cards on a 12px gap, tier-specific colored geometric emblems and mono highlights. Further extension and add-on cards use four or five columns. A comparison section follows with centered 36px title, category pills, repeated offer headers, 16px row text and warm hairlines; it is a table on paper rather than a pile of cards.

**Transfer:** Align descriptions, amounts and actions across offers. Add detail only after the reader can understand the broad choices.

**Text style:** `plan-title` — inter 500 · 24px/1.2 · tracking -0.01em

### Institutional editorial chapters

**Only for:** institutional pages

**Observed:** White two-column introduction gives way to a full-bleed navy chapter with a blue three-column geometric-symbol panel. Narrow illustrated prose returns to white with 160px vertical padding, followed by a deep-teal candid-photo mosaic and forest investor band. People directories have centered 48px headings, 150px circular portraits and 70px column gaps.

**Transfer:** Use these materials to explain an organization's worldview and people, not as default product-feature decoration.

**Text style:** `institutional-heading` — inter 500 · 48px/1.18 · tracking -0.02em

### Institutional paired ending

**Only for:** institutional pages

**Observed:** After the portrait directories, two 668px charcoal panels separated by 24px present an offer and a cropped phone. The left panel pairs a muted/white 48px headline with oversized neutral geometry, a white button, then a stone lower strip with a demo action. A four-mark customer row precedes the standard white footer.

**Transfer:** Pair the primary offer with one tangible product artifact and offer a human-assisted path beneath it; keep geometry subordinate to the message.

**Text style:** `institutional-heading` — inter 500 · 48px/1.18 · tracking -0.02em

## Page flow

**Storyline:** promise → working demonstration → concrete proof → capability depth → confidence and objections → next step → resource navigation

### Broad platform introduction

1. **Promise** — Centered statement, support and two actions.
2. **Product demonstration** — Category selector linked to a large working-device stage.
3. **Quantified proof** — Three metric cards and subdued customer marks.
4. **Capability depth** — Blue role-filtered demonstration and benefit shelf.
5. **Social proof** — Conversational quote rail and modular ecosystem field.
6. **Closing call** — Rounded charcoal invitation followed by white resource footer.

**Transfer:** Let a broad product story alternate spacious claims and tangible modules rather than enumerating every feature.

### Help a buyer choose and resolve commercial uncertainty

1. **Offer framing** — Two-tone audience-oriented headline above four comparable plans.
2. **Social proof** — Muted customer-mark grid.
3. **Expanded choices** — Product promotion, extensions and add-on cards.
4. **Detailed comparison** — Categorized table with persistent offer context.
5. **Procurement** — Marketplace options with clear actions.
6. **Objection handling** — Topic-grouped two-column FAQ lists.
7. **Closing call** — Centered final question and sales link, then white footer.

**Transfer:** Keep high-level choice first and long-form commercial detail later; retain the light, low-pressure ending.

### Explain one product or use case with direct functional proof

1. **Promise** — Split eyebrow, headline, action and trusted marks beside layered interfaces.
2. **Capability chapters** — Alternating UI-and-copy explanations, then a broad detail figure.
3. **Capability summary** — Audience-filtered three-column card matrix.
4. **Objection handling** — Two-column questions and answers.
5. **Closing call** — Shared charcoal invitation and white footer.

**Transfer:** Replace broad platform breadth with increasingly specific task views while preserving the shared shell and conversion language.

### Explain the people and principles behind a technical product

1. **Worldview** — Large left statement balanced by right-hand prose.
2. **Principles** — Navy and blue geometric three-column chapter.
3. **Commitments** — Narrow illustrated long-form text.
4. **Human proof** — Candid photo mosaic on teal, then investor proof on forest.
5. **Credibility** — Spacious portrait directories.
6. **Closing call** — Paired charcoal offer/device panels, customer marks and white footer.

**Transfer:** Use longer prose and authentic people photography while keeping institutional color and type variants scoped.

## Writing

Technically fluent, direct and reassuring without sounding militaristic. Confident claims are followed by practical tasks, tangible results or a candid explanation of how the product works.

**Do not copy:** Do not reuse the Tailscale or Aperture names, logos, customer marks, proprietary interface artwork, claims, prices, metrics, testimonials or people identities. Source phrases are examples of tone only, not copy for a new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for user outcomes, we for organizational intent, and the product name when describing mechanisms. Speak to practitioners as capable peers.
- **Rhythm:** Headlines are sentence-case statements, often 5–12 words. Support ranges from a concise sentence to a technical paragraph; short emphatic fragments can follow a quantified claim. Actions are generally 2–4 words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category and promise in one declarative statement. | 8–12 words | “The best secure connectivity platform for the AI era” |
| Capability heading | Describe the reader's gain, not a vague feature category. | 5–10 words | “Cut through the blur of fragmentation and sprawl” |
| Supporting line | Tie the product mechanism to a concrete, intelligible outcome. | 15–35 words | “The unified AI governance solution that gives a clear picture of how you’re using AI and what it costs.” |
| Proof explanation | A result with its operational context. | 5–15 words | “hours saved with fewer connectivity issues.” |
| Primary action | Start with a task verb and a specific object where useful. | 2–4 words | “Start connecting devices”<br>“See all integrations” |
| Institutional statement | A human belief stated simply, then explained without grandiosity. | 3–8 words | “Small is beautiful”<br>“Real people solving concrete problems” |
| Question | Ask the actual buyer question in ordinary language. | 7–18 words | “Does [Brand] offer a free trial?” |

**Words and phrasing to use:** get started; connect; identity; in minutes; your team; works; without; clear; concrete; at scale

**Avoid:** military-grade; disruptive revolution; unleash limitless potential; synergize; effortless magic; fear-based threat slogans

**Rules:**

- Explain a technical term through a task or outcome instead of removing all technical specificity.
- Pair each large claim with a working view, a concrete result or a clear explanation.
- Write honest FAQ answers with operational details, including limitations and changes.
- Use conversational warmth in proof and organizational prose; keep navigation and actions utilitarian.

## Do's and Don'ts

### Do

- Use 500-weight Inter for major headings rather than bold display cuts.
- Keep the default page on warm #f9f7f6 with white modules and #eeebea edges.
- Retain the 36px compact action height and 8px corners.
- Use 64px desktop gutters and a 768px support measure.
- Keep numerical proof as prominent as the 64px heading scale.
- Use uppercase mono at 0.05em tracking as a technical counterpoint.
- Show the modular 72px tile field with its larger editorial interruption.
- Finish ordinary landing narratives with the rounded charcoal invitation and a separate white footer.

### Don't

- Do not turn conversion buttons into pills; the 9999px shape belongs to filters.
- Do not substitute heavy shadows for 1px warm card edges.
- Do not use a saturated accent as the default button fill.
- Do not make every section a dark full-bleed band; navy and forest chapters belong to institutional storytelling.
- Do not flatten the 32px product-stage corners to the ordinary 16px card radius.
- Do not apply mono to long body paragraphs.
- Do not turn comparison tables into highly elevated isolated feature cards.
- Do not gray out the colorful ecosystem symbols just because the customer-logo grid is subdued.

## Motion and responsive

### Motion

**Observed:**

- Declared color, background-color, border-color, text-decoration-color, fill and stroke transitions use 0.2s cubic-bezier(0.4,0,0.2,1); one uses 0.3s.
- A continuous scroll animation is declared at 150s linear infinite.
- The two-tier navigation remains present during scrolling.

**Transfer:**

- Use restrained color changes for compact controls and a slow-moving proof rail rather than dramatic section entrances.

**Unknown:**

- Exact animated rail displacement, hover treatments beyond the stated declarations and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Marketing CSS includes width breakpoints at 420px, 480px, 769px, 1024px, 1440px and 1920px.
- Layout classes specify single-column small layouts, two-column intermediate grids and twelve-column desktop grids; base container padding is 24px and desktop padding is 64px.
- The institutional root font size is viewport-relative.

**Transfer:**

- Stack split product stages while preserving copy before its associated media. Reflow the ecosystem field rather than scaling its symbols into illegibility.
- Use the single-column FAQ layout on narrow screens; retain independent question rows. Keep the product object substantial rather than squeezing desktop UI beside narrow text.

**Unknown:**

- Exact mobile navigation behavior, rendered mobile type sizes and overflow handling have not been established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
