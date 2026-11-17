# beehiiv — midnight growth electric

## Overview

An assertive, creator-facing style that pairs midnight blue-black expanses with electric pink and indigo light. Heavy uppercase grotesk headlines sit above friendly, readable sans-serif explanations, while layered interfaces and human portrait mosaics make the product feel both capable and alive. It suits ambitious software platforms and growth-oriented services, with spacious section pacing and dense pockets of practical proof. Light editorial variants trade the midnight canvas for white, lavender and warm paper without losing the bold typographic voice.

### Essentials

- Headlines behave like stacked declarations: ClashGroteskFont 700, 60px/1 for the default opening and 48px/1 for section leads, uppercase with normal tracking; the final opening line turns from pale pink to hot pink.
- The opening balances a verbal stack against a floating product constellation: two 576px columns with a 32px gap, 96px vertical breathing room and a roughly 634px-wide layered interface scene fading into midnight.
- Actions are compact rectangles, not soft lozenges: 6px corners, indigo faces, 18px/28px bold labels and 8px 24px padding; pink backing layers sit beneath the main face.
- Darkness is the majority material: #060419 canvas and #0d0b28 panels carry nearly the whole default page; pink is concentrated in headline emphasis, metrics and links, indigo in actions and glows, white in exceptional decision cards.
- Proof becomes a moving human-and-number mosaic: 308px × 425px portrait and statistic tiles, 12px corners, 24px horizontal gaps, two staggered edge-faded lanes; use real people or outcome/artifact tiles when portraits are unavailable.
- Atmospheric light and a decisive closing billboard anchor the style: stage product panels on soft violet-pink glows and include a centered 48px uppercase closing declaration inside a blue-lit, 12px-corner panel with a single action. Recreate the light with blurred gradient layers when custom artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight ink | `#060419` | `--color-canvas` | background, text | Default page canvas; primary dark text on light variants. |
| Action indigo | `#2f39ba` | `--color-action` | action, link, border | Primary button face, light-theme text links and blue metrics. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal pink | `#ff5ec4` | `--color-pink` | accent, text, link, border | Gradient endpoint, outcome numerals, small labels and text actions; not the general page fill. |
| Pink light | `#ffdcff` | `--color-pink-light` | accent, background | Opening text-gradient start; full quote-band fill only in light product-detail layouts. |
| Periwinkle proof | `#b3b8f0` | `--color-stat` | text, border | Large numerals and captions in moving proof tiles; pale resource-card edge. |
| Deep pink backing | `#f092dd` | `--color-backing-pink` | surface | Rear action layer, subordinate to the button face. |
| Pale pink backing | `#ffc8eb` | `--color-backing-light` | surface | Second rear action layer. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action | Main dark-theme headings, white decision cards and inverse navigation action; light-theme canvas. |
| Porcelain | `#fcfcfd` | `--color-near-white` | surface, border | Secondary action outline; light-theme footer and feature-card fill. |
| Ethereal white | `#f7f5ff` | `--color-body` | text, background | Dark-theme support copy; lavender section background in light product-detail variants. |
| Soft lavender gray | `#c4c2d6` | `--color-secondary` | text | Attribution and small supporting text on dark surfaces. |
| Muted on midnight | `#9393a9` | `--color-muted` | text | Footer links, secondary explanations and source captions on dark backgrounds. |
| Strong gray violet | `#4e4e6c` | `--color-rule` | border, text | Accordion rules, testimonial outline and dark descriptive text inside white pricing cards. |
| Higher midnight | `#141230` | `--color-hover-panel` | surface | Hover fill for moving proof tiles and case-study cards. |
| Charcoal violet | `#131125` | `--color-secondary-button` | surface | Dark outlined secondary conversion button. |
| Backing ink edge | `#0b0d2a` | `--color-backing-edge` | border | Hairline around pink action backing layers. |
| Raised midnight | `#0d0b28` | `--color-panel` | surface | Product tiles, statistic cards, testimonial and closing panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light product-detail and company pages | Muted on white | `#6f6f8a` | `--color-light-muted` | text | Secondary footer text in light themes. |
| light product-detail and pricing modules | Lavender edge | `#d4d7f5` | `--color-card-edge` | border, surface | Light feature-card outline, pale resource-card surface and small commercial badges. |
| light product-detail pages | Electric blue | `#3843d0` | `--color-blue-band` | background, accent | Full-width instructional and closing bands. |
| company storytelling pages | Warm paper | `#f7f5f2` | `--color-paper` | background, surface | Company metric and press bands. |

## Typography

- **ClashGroteskFont** — Uppercase major headings and outcome numerals. Broad, heavy grotesk with assertive geometric forms and tightly packed lines. If unavailable, use **Clash Grotesk**. Use 700; preserve width and the compact uppercase block. Font stack: "ClashGroteskFont", "Clash Grotesk", Arial, sans-serif.
- **SatoshiFont** — Body copy, navigation, button labels, card titles, quotations and pricing numerals. Clean rounded geometric sans with a friendly readable texture at medium weight. If unavailable, use **DM Sans**. Use 500–700; retain the generous 28px paragraph line height. Font stack: "SatoshiFont", "DM Sans", system-ui, -apple-system, 'Segoe UI', sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| metric | ClashGroteskFont | 700 | 64px | 66px | normal, uppercase | Standalone quantitative proof. |
| proof-metric | ClashGroteskFont | 700 | 64px | 68px | normal, uppercase | Periwinkle numerals in moving proof tiles. |
| display | ClashGroteskFont | 700 | 60px | 1 | normal, uppercase | Default opening declaration, including its gradient final line. |
| heading | ClashGroteskFont | 700 | 48px | 1 | normal, uppercase | Section leads and default closing billboard. |
| quote | SatoshiFont | 500 | 30px | 1.2 | normal | Centered testimonial statement. |
| card-title | SatoshiFont | 700 | 24px | 32px | normal | Capability titles and plan names. |
| body | SatoshiFont | 500 | 20px | 1.4 | normal | Hero support and main section explanations. |
| question | SatoshiFont | 600 | 20px | 1.4 | normal | Accordion questions and compact feature titles. |
| body-small | SatoshiFont | 500 | 18px | 28px | normal | Tile descriptions, metric captions and attribution roles. |
| action | SatoshiFont | 700 | 18px | 28px | normal | Main conversion labels. |
| nav | SatoshiFont | 600 | 14px | 20px | normal | Navigation links and small header actions. |
| caption | SatoshiFont | 500 | 14px | 20px | normal | Footer links and plan explanations. |
| label | SatoshiFont | 700 | 14px | 20px | normal | Footer column headings and small bold commercial labels. |
| eyebrow | SatoshiFont | 700 | 14px | 20px | 0.08em, uppercase | Trust-strip descriptor and structured section markers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing, light product-detail and company openings | large-title | ClashGroteskFont | 700 | 64px | 66px | normal, uppercase | Larger centered or split opening declaration. |
| pricing closings | closing-large | ClashGroteskFont | 700 | 56px | 64px | normal, uppercase | Two-line closing promise above support copy. |
| pricing modules | price | SatoshiFont | 700 | 48px | 1 | normal | Prices and custom-plan value. |
| audience-specific business landing pages | case-metric | ClashGroteskFont | 700 | 36px | 40px | -0.025em, uppercase | Compact case-study metrics. |
| light product-detail pages | light-quote | SatoshiFont | 500 | 24px | 32px | normal | Quote on a flat pink band. |
| business case studies and light footers | body-compact | SatoshiFont | 500 | 16px | 1.5 | normal | Compact explanatory copy. |

**Notes:**

- Clash headings are uppercase blocks; body, quotations, navigation and card titles stay mixed case. Default display tracking is normal, not artificially tightened.
- Keep the final hero line in the same recipe as the white lines; its gradient supplies emphasis rather than a size change.
- The 64px metric recipe and 64px large-title recipe share geometry but have different roles. Pricing numerals use Satoshi rather than the display face.

## Layout

**Density:** Airy section pacing with compact information inside panels; long dark pauses separate dense proof, product and decision modules.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card-title-to-description gap and inline icon spacing. |
| 12px | Paired action gap and footer-link rhythm. |
| 16px | Heading-to-support gap and four-column pricing gutters. |
| 20px | Stat-grid gutters and pricing-card side inset. |
| 24px | Action offset after support, capability gutters and tile heading inset. |
| 32px | Hero column gap, three-column card gutter and resource-card inset. |
| 40px | Compact section-group separation. |
| 64px | Section heading group to major media; footer vertical inset and closing outer inset. |
| 96px | Default major-section vertical padding and inner closing-panel breathing room. |
| 128px | Desktop page side padding. |

### Containers and grids

- **Page container**: max width 1280px · side padding 128px. Centered max-width wrapper inside the page gutters; at 1440px the usable content span is 1184px.
- **Opening split**: 2 columns · gap 32px. Equal text and media columns, vertically centered; each column is 576px at desktop.
- **Capability pair**: 2 columns · gap 24px. Alternating roughly two-thirds and one-third media tiles, about 773px and 387px wide.
- **Proof statistics**: 4 columns · gap 20px. Four evenly sized dark statistic cards.
- **Reading column**: max width 768px. Long quotations, company narrative and right-hand FAQ column.
- **Plan grid** (only for pricing modules): 4 columns · gap 16px. Equal-width white plans with aligned prices and actions.
- **Feature grid** (only for light product-detail pages): 4 columns · gap 32px. Eight text-led cards arranged in four columns.
- **Case grid** (only for business landing pages): 3 columns · gap 16px. Three compact case-study cards beneath a left-aligned declaration.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions | 6px |
|  | Statistic cards | 8px |
|  | Media and closing panels | 12px |
|  | Testimonial controls | 50% |
| pricing modules | Billing switch | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing modules | Recommended plan inset | `inset 0px 0px 0px 2px #ff5ec4, inset 0px 0px 0px 4px #060419` | Double inset outline singles out the recommended plan without lifting it above its neighbors. |

### Surfaces

#### Midnight canvas · level 0

**Use:** Default landing-page foundation.

**CSS:** `background: #060419; color: #ffffff`

**Observed:** Nearly uninterrupted darkness unifies the default marketing story.

**Transfer:** Let panels and light, rather than alternating generic white sections, subdivide the page.

#### Raised panel · level 1

**Use:** Feature and numeric proof containers.

**CSS:** `background: #0d0b28; border: 1px solid rgba(255,255,255,0.06); border-radius: 8px; box-shadow: none`

**Observed:** The edge is barely brighter than the fill; different module families use 12px media corners.

**Transfer:** Use the same subtle separation for new capabilities and proof.

#### Gradient headline

**Use:** One short payoff line in the opening.

**CSS:** `background-image: linear-gradient(to right, #ffdcff, #ff5ec4); background-clip: text; -webkit-text-fill-color: transparent`

**Observed:** Pale pink starts at the left and intensifies to hot pink at the right.

**Transfer:** Apply to a compact concluding phrase, leaving the preceding lines white.

#### Testimonial stage · level 1

**Use:** Wide quote panel.

**CSS:** `background: #0d0b28; border: 1px solid #4e4e6c; border-radius: 8px; padding: 80px 64px; overflow: hidden`

**Observed:** Subtle angled illumination and fine soft-light grain sit behind centered text; the interior is mostly dark.

**Transfer:** Add a very low-opacity noise layer and a broad dim violet glow below the quote.

#### Closing lightbox · level 1

**Use:** Final conversion billboard.

**CSS:** `background: #0d0b28; border: 1px solid rgba(47,57,186,0.5); border-radius: 12px; overflow: hidden`

**Observed:** A broad blue-violet light field is clipped within the panel while centered white type and the primary action remain crisp.

**Transfer:** Use the atmospheric-light build behind the content; preserve dark edges.

#### Lavender chapter · level 0

**Only for:** light product-detail pages

**Use:** Text-led features and learning resources.

**CSS:** `background: #f7f5ff; color: #060419; border-bottom: 2px solid #060419`

**Observed:** Flat pale lavender, separated from adjacent bands by a hard dark rule.

**Transfer:** Use for a dedicated educational chapter, not as the default dark landing background.

#### Electric chapter · level 0

**Only for:** light product-detail pages

**Use:** Instructional steps and closing conversion band.

**CSS:** `background: #3843d0; color: #ffffff; border-bottom: 2px solid #060419`

**Observed:** Solid electric blue carries white text; the closing version adds faint oversized hexagonal outlines.

**Transfer:** Use the solid band for process explanation and the outlined variant for its final action.

#### Pink quote band · level 0

**Only for:** light product-detail pages

**Use:** A testimonial interlude.

**CSS:** `background: #ffdcff; color: #060419; border-bottom: 2px solid #060419`

**Observed:** Flat pink instead of the default dark illuminated quotation panel.

**Transfer:** Center a short quote within a 768px reading width.

#### Paper chapter · level 0

**Only for:** company storytelling pages

**Use:** Metrics and press modules.

**CSS:** `background: #f7f5f2; color: #060419; border-top: 1px solid rgba(6,4,25,0.12); border-bottom: 1px solid rgba(6,4,25,0.12)`

**Observed:** Warm paper supports white inset cards without atmospheric effects.

**Transfer:** Keep company storytelling photographic and editorial.

## Components

### Sticky navigation

**Use:** Persistent global navigation.

**CSS:** `position: sticky; top: 0px; z-index: 50; background: #060419; border-bottom: 1px solid rgba(255,255,255,0.12); padding: 20px 128px`

**Text style:** `nav` — SatoshiFont 600 · 14px/20px

**Observed:** Logo at left, compact category links in the middle; login, an outline demo action and a white signup action at right. The total desktop height is 77px. Light themes invert the background and text and use an indigo signup face.

**Transfer:** Keep the brand small relative to the display headlines.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #2f39ba; color: #ffffff; border: 1px solid #2f39ba; border-radius: 6px; padding: 8px 24px; height: 46px; position: relative`

**Text style:** `action` — SatoshiFont 700 · 18px/28px

**Observed:** A crisp indigo face sits above two inset pink backing layers, each with a dark hairline. The opening provider variant is 50px tall and adds a 32px white square around its provider icon; its backing layers do not read as separate extra buttons.

**States:** Declared: hover scale(1.02) on the outer action; focus-visible not specified.

**Transfer:** Use a single face and two absolutely positioned inset backing layers; do not turn the backing into a large resting drop shadow.

### Secondary button

**Use:** Alternative opening action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #131125; color: #ffffff; border: 1px solid #fcfcfd; border-radius: 6px; padding: 8px 24px; height: 50px`

**Text style:** `action` — SatoshiFont 700 · 18px/28px

**Observed:** Sits beside the provider action and shares the layered backing construction. On light product-detail openings the alternate action becomes white with an indigo outline and text.

**States:** Declared: hover scale(1.02); focus-visible not specified.

### Header conversion

**Use:** Small high-contrast navigation action.

**CSS:** `background: #ffffff; color: #060419; border: 1px solid #ffffff; border-radius: 6px; padding: 8px 12px; height: 36px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `nav` — SatoshiFont 600 · 14px/20px

**Observed:** The adjacent demo action is transparent with a 20% white outline; its hover uses a 10% white fill.

**States:** Declared: hover background #060419 and text #ffffff; focus-visible not specified.

### Capability tile

**Use:** Large media-led capability summary.

**CSS:** `background: #0d0b28; border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; overflow: hidden; position: relative`

**Text style:** `card-title` — SatoshiFont 700 · 24px/32px

**Observed:** Top-left mixed-case title, one explanatory sentence and a pink arrow link; a 44px square plus control sits at the top right. Oversized bright interface artwork fills the lower area and is clipped at the edges. Pairs alternate wide and narrow emphasis.

**Transfer:** Use actual or simplified functional UI rather than a stock illustration.

### Statistic card

**Use:** Outcome proof with oversized numbers.

**CSS:** `background: #0d0b28; border: 1px solid rgba(255,255,255,0.06); border-radius: 8px; padding: 32px 28px; display: flex; flex-direction: column; justify-content: space-between; gap: 64px`

**Text style:** `metric` — ClashGroteskFont 700 · 64px/66px · uppercase

**Observed:** Pink numeral at the top and an 18px explanatory caption near the bottom; default four-up cards are 281px wide and 252px tall. Audience-specific diagnostic cards use white numerals and include a muted source note.

**Transfer:** Keep each number tied to one concrete outcome.

### Moving proof tile

**Use:** Customer proof mosaic.

**CSS:** `background: #0d0b28; border-radius: 12px; width: 308px; height: 425px; padding: 32px 24px; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `proof-metric` — ClashGroteskFont 700 · 64px/68px · uppercase

**Observed:** Alternate logo-plus-metric tiles with edge-to-edge portraits carrying a bottom dark fade, name and publication caption. Metrics and their captions use periwinkle; portrait text stays white.

**States:** Declared: hover background #141230 for metric tiles; focus-visible not specified.

**Transfer:** When portraits are unavailable, alternate outcome numerals with product artifacts or customer-work imagery.

### Accordion row

**Use:** Objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; border-top: 2px solid #4e4e6c; padding: 24px 16px; color: #ffffff`

**Text style:** `question` — SatoshiFont 600 · 20px/1.4

**Observed:** Native disclosure rows place a question at left and a small chevron at right. The default FAQ occupies a 768px right column beside a narrower uppercase title. Light product-detail FAQ uses the full content width and dark text; pricing uses a 1px rule with 20px vertical padding.

**Transfer:** Let answers expand below their question rather than adding a separate card surface.

### Footer link

**Use:** Dense but subordinate footer navigation.

**CSS:** `color: #9393a9; border-radius: 6px; text-decoration: none`

**Text style:** `caption` — SatoshiFont 500 · 14px/20px

**Observed:** Five column groups follow a wider email-subscription column; links are separated by 12px. A fine rule separates legal links and copyright beneath. The light variant uses muted violet-gray text on porcelain.

**States:** Declared: hover white text and underline; focus-visible not specified.

### Plan card

**Only for:** pricing modules

**Use:** Comparable commercial options.

**CSS:** `background: #ffffff; color: #060419; border-radius: 12px; padding: 24px 20px 20px 20px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-title` — SatoshiFont 700 · 24px/32px

**Observed:** Plan name and description lead into a large price, billing note, full-width action and a fine-separated feature list. Four equal 284px cards align in a row. The recommended card uses the Recommended plan inset and a small dark popularity pill. Entry action is white with an indigo outline, paid tiers use indigo and enterprise uses midnight.

**Transfer:** Keep comparable information in the same vertical slots.

### Light feature card

**Only for:** light product-detail pages

**Use:** Text-led capability grid.

**CSS:** `background: #fcfcfd; color: #060419; border: 2px solid #d4d7f5; border-radius: 8px; padding: 24px`

**Text style:** `question` — SatoshiFont 600 · 20px/1.4

**Observed:** A blue icon in a 56px pale lavender circle leads a title and substantial paragraph. Cards share row height but remain top aligned.

**Transfer:** Reserve for detailed product education rather than replacing the default media tiles.

## Imagery and graphics

### Floating interface constellation

**Use:** Default opening product demonstration.

**Observed:** Three overlapping dark interface windows show a rear template chooser, a smaller revenue panel on the left and a larger analytics foreground panel on the right. Thin violet-gray edges, pink chart fills and a small cursor tag make the scene tangible; right and bottom edges dissolve into the canvas. The scene occupies roughly half the hero.

**Transfer:** Rebuild three simplified panels around a core workflow and one output or result. If no interface exists, use framed artifacts or documents with equivalent overlap, strong front/back hierarchy and selective pink accents.

**Build:** Create three absolutely positioned rectangles within a roughly 634px-wide stage. Place the rear panel high and right, a smaller panel left and lower, and the foreground panel lower-right. Use midnight panel fills, 1px white borders at 12% opacity and 8px corners; add a pink SVG area chart in front. Place a broad violet blurred ellipse behind them and mask the stage's bottom and right edges toward transparency.

### Atmospheric light

**Use:** Product-tile backdrops, the opening stage and the closing lightbox.

**Observed:** Soft indigo-violet and pink illumination appears behind or below crisp UI. The closing panel is an abstract cloud of blue-violet light with dim corners rather than a hard gradient stripe.

**Transfer:** Keep the light subordinate to text and interface edges; exact gradient stops are not essential.

**Build:** On a midnight base, layer two or three oversized radial-gradient ellipses using rgba(47,57,186,0.6), rgba(56,67,208,0.35) and rgba(255,94,196,0.15). Blur separate layers by 64px–96px, with the strongest indigo near the upper-left or lower-right and pink below the product. Clip them to the parent; place all content above the light and optionally add fine noise at very low opacity.

### Cropped capability demonstrations

**Use:** Large capability tiles and smaller workflow cards.

**Observed:** Bright white editor and dashboard panels sit on violet illuminated backing; popover menus and overlapping UI panes reveal one feature at a time. Media runs off the bottom or side of its container instead of shrinking to fit. Business variants use dark redrawn interface details with pink charts on blue-violet top rims.

**Transfer:** Stage one understandable operation per image, allowing menus and key controls to remain readable. Use the product's true theme rather than recoloring every interface to match the marketing canvas.

### Human proof portraits

**Use:** Moving proof lanes.

**Observed:** Full-color portraits fill tall rounded cards, cropped close enough to recognize faces. A black bottom fade protects name and affiliation text; adjacent statistic cards act as visual rests.

**Transfer:** Use naturally lit customer imagery with varied framing, paired with authentic outcome cards rather than applying a uniform duotone treatment.

### Integration ribbon

**Use:** Ecosystem proof.

**Observed:** Two horizontal lanes of small square app marks sit in dark faintly outlined tiles, with edge fades; the marks keep their native colors.

**Transfer:** Use real compatible-tool marks or neutral integration-category glyphs, with a disciplined repeated tile size and the same dark edge fade.

### Editorial company photography

**Only for:** company storytelling pages

**Use:** Founding narrative and team culture.

**Observed:** A wide warm-neutral studio portrait follows a centered headline; the team chapter uses a wide outdoor group photo and an irregular mosaic of candid travel and gathering images. Color remains natural, with simple rounded frames and small centered bold captions.

**Transfer:** Use genuine people and places. Lead with a coherent group image, then vary mosaic sizes and aspect ratios; keep the white surround.

### Hexagonal closing field

**Only for:** light product-detail pages

**Use:** Full-width electric closing band.

**Observed:** Oversized faint rounded hexagonal outlines form a low-contrast field behind the centered white declaration.

**Transfer:** Use subtle geometric structure, not a loud honeycomb illustration.

**Build:** Tile SVG rounded hexagon outlines approximately 180px wide across an electric-blue background, with 1px–2px strokes in white at 3%–6% opacity. Fade the pattern toward the top behind the text.

### Icons

**Observed:** Utility icons are mostly 20px outline SVGs with 2px round strokes; accordion chevrons use subdued gray. Card links use pink arrows, and capability expansion uses a prominent pink plus in a dark square. Light feature modules use blue symbols on pale circular discs.

**Transfer:** Choose a consistent rounded outline family for controls; reserve solid marks for product or partner identities. Keep utility symbols subordinate to the heavy heading typography.

## Section recipes

How recurring sections are built.

### First screen: Constellation opening

**Observed:** A 77px sticky navigation bar sits above a midnight split hero. The content uses 96px vertical padding, equal columns with a 32px gap and 128px desktop gutters. The left half carries a 60px/1 uppercase declaration stacked into four compact lines: three white topic phrases and a pink-gradient payoff. Support copy follows after 16px, then a compact rating/avatar proof row, paired 50px conversion actions and a small reassurance line. At right, the Floating interface constellation is approximately 634px wide and 475px tall, slightly exceeding its column, on atmospheric violet light. Within the first 900px the full headline, support, proof, actions and main object are visible, followed by an uppercase trust descriptor and an edge-faded logo ribbon; the next major capability chapter begins below that screen.

**Transfer:** Make a short stack of product-relevant declarations ending in a unifying payoff. Rebuild the product scene from simplified workflow panels or tangible output artifacts when polished media is unavailable. Pricing openings center a 64px declaration over controls and white plans; light product-detail openings use a 64px left-hand declaration beside a bright interface; company stories center the title over a broad natural photograph. Audience-specific business openings retain the dark split but use a 48px problem statement, a small pill label and one sales action.

**Avoid:** Do not center the default hero, enlarge the headline into a full-bleed word sculpture or replace the layered right-hand object with an isolated icon.

**Text style:** `display` — ClashGroteskFont 700 · 60px/1 · uppercase

### Heading pair and media chapter

**Observed:** A small pink label sits over a 48px uppercase heading at left; support copy and a Primary button occupy the other half, aligned toward the bottom. A 64px gap introduces Capability tiles in an alternating wide/narrow pair with 24px gutters.

**Transfer:** Give each chapter one claim and demonstrate it with a small number of large functional scenes.

**Text style:** `heading` — ClashGroteskFont 700 · 48px/1 · uppercase

### Proof mosaic

**Observed:** A centered heading, short support and Primary button lead into two staggered lanes of Moving proof tiles. Each lane extends past the viewport; a gradient mask fades its first and last 8%. The lanes are 28px apart and alternate portraits with periwinkle quantitative cards.

**Transfer:** Mix human credibility with measurable outcomes, retaining the moving edge-faded device even when using artifact tiles instead of portraits.

**Text style:** `heading` — ClashGroteskFont 700 · 48px/1 · uppercase

### Numeric declaration

**Observed:** A centered uppercase section heading sits 64px above four Statistic cards. Pink 64px numerals lead; white short captions explain the outcome. Diagnostic business variants use three cards with white 48px numerals, a muted category and a citation.

**Transfer:** Choose a few high-signal metrics instead of a dense dashboard. Keep cited diagnostic proof visually distinct from product results.

**Text style:** `metric` — ClashGroteskFont 700 · 64px/66px · uppercase

### Wide testimonial

**Observed:** The Testimonial stage spans the 1184px desktop content width. A centered 755px text group uses the 30px quote recipe, then a small circular portrait, bold name, muted role and an outline pill story action. Two circular 48px previous/next controls sit below the panel.

**Transfer:** Use one specific operational benefit, not a generic compliment; make the attribution part of the visual hierarchy.

**Text style:** `quote` — SatoshiFont 500 · 30px/1.2

### Questions beside a declaration

**Observed:** A 48px uppercase prompt occupies the left third; Accordion rows occupy a 768px right column. The light product-detail variant centers the title above full-width rows, while business questions use a narrower right column and 18px labels.

**Transfer:** Write questions as genuine purchase objections; preserve the rule-led list rather than filling each answer with its own card.

**Text style:** `heading` — ClashGroteskFont 700 · 48px/1 · uppercase

### Illuminated closing and utility footer

**Observed:** The Closing lightbox sits inside the normal content gutters with 64px outer vertical inset and 96px inner vertical padding. A centered white declaration and one Primary button float over blue-violet light; the default panel is 312px tall. The footer follows as a separate midnight band with a faint top rule, 64px vertical padding, an email form on the left, five link columns at right, and legal links plus a small brand symbol below another rule. Light product-detail pages close with an electric hexagonal band and a porcelain footer. Company stories end after press cards directly in the light footer, without inserting the illuminated sales panel.

**Transfer:** Give a new landing page a clear last invitation and a real utility footer. Use the light or editorial ending only for its corresponding page type.

**Text style:** `heading` — ClashGroteskFont 700 · 48px/1 · uppercase

### Decision module

**Only for:** pricing modules

**Observed:** A centered declaration and support precede a row of compact outlined inclusion tags, a subscriber control with a 6px track and pink current value, and a pill-shaped billing switch. Four Plan cards follow with 16px gutters. A separate dark feature comparison aligns four plan columns beside a label column, using faint rules, checkmarks and expandable category rows.

**Transfer:** Map the controlling variable to the new product's actual billing model; maintain aligned cards and a separate granular comparison.

**Text style:** `price` — SatoshiFont 700 · 48px/1

### Business comparison and workflow

**Only for:** audience-specific business landing pages

**Observed:** Pink uppercase eyebrows label left-aligned 48px declarations. A dark comparison table uses 24px 32px cell insets, white-alpha rules and small status dots; a brighter row distinguishes the product. Workflow follows in four narrow dark cards with image tops, pink sequence numbers, mixed-case titles and explanatory paragraphs. Larger two-column benefit cards combine pink ordinal numbers with dark charts or UI diagrams.

**Transfer:** Compare meaningful alternatives, then explain the transition with operational steps. Restrict status colors to the table's factual semantics.

**Text style:** `heading` — ClashGroteskFont 700 · 48px/1 · uppercase

### Light learning chapters

**Only for:** light product-detail pages

**Observed:** White opening gives way to lavender text-led cards, a flat pink testimonial, a dark video chapter, and an electric-blue process band. The process uses four stacked left-border steps beside a product preview; active step border is white and inactive borders are 40% white. Three resource cards later step from indigo through periwinkle to pale lavender.

**Transfer:** Use these contrasting bands to organize a detailed feature explanation, keeping the common display face and 96px chapter insets.

**Text style:** `heading` — ClashGroteskFont 700 · 48px/1 · uppercase

### Editorial people and press

**Only for:** company storytelling pages

**Observed:** A centered 64px title introduces a 1024px-wide founder photograph and small bold caption. Narrative paragraphs sit in a narrower column. Warm-paper metric bands use white cards with blue numerals; team content uses an asymmetric photo mosaic, then paper-backed press cards with images, mixed-case 24px titles, dates and small arrows.

**Transfer:** Tell the organization's origin and human texture through real photography and selective facts; end with external credibility and the utility footer.

**Text style:** `large-title` — ClashGroteskFont 700 · 64px/66px · uppercase

## Page flow

**Storyline:** Bold promise → functional demonstration → human and quantified proof → practical decision support → objections → decisive invitation and utility footer; emphasis shifts with page purpose.

### Broad platform landing page

1. **Promise** — Split declaration and floating interface constellation with a trust ribbon.
2. **Capability chapters** — Heading pair followed by alternating wide/narrow media tiles.
3. **Social proof** — Moving portrait-and-statistic mosaic.
4. **Decision support** — White plan cards on midnight.
5. **Confidence** — Wide testimonial, pink outcome statistics and an integration ribbon.
6. **Objection handling** — Split heading and disclosure list.
7. **Closing call** — Illuminated billboard and dark subscription/navigation footer.

**Transfer:** Balance emotional ambition with functional product demonstrations; reuse the signature light, mosaic and closing device without requiring the same section order.

### Commercial evaluation page

1. **Promise and pricing** — Centered title above shared controls and four white plans.
2. **Social proof** — Compact creator/brand imagery.
3. **Comparison** — Dark multi-column feature matrix with expandable categories.
4. **Value reinforcement** — Three-column product demonstration cards.
5. **Objection handling** — Plan-specific question list.
6. **Closing call** — Blue-lit panel with larger declaration, support and a free-start action, then dark footer.

**Transfer:** Make the commercial choice easy before explaining every feature; keep granular comparison visually quieter than the plan cards.

### Detailed product capability page

1. **Promise** — White split opening with pink label and bright interface.
2. **Capabilities** — Blue trust band and lavender text-led feature grid.
3. **Social proof** — Flat pink quote band.
4. **Demonstration** — Large framed video on midnight.
5. **Process** — Electric-blue step list beside a preview.
6. **Enablement** — Resource cards in a graduated blue palette.
7. **Objection handling** — Full-width rule-led questions on white.
8. **Closing call** — Blue hexagonal invitation band and porcelain footer.

**Transfer:** Scope the lighter, chaptered appearance to feature education; retain the main brand's uppercase weight and action construction.

### Audience-specific business landing page

1. **Problem framing** — Dark split opening, pink pill label, analytical product graphic and single sales action.
2. **Quantified problem** — Logo grid and three cited diagnostic cards.
3. **Differentiation** — Comparison table with highlighted product row.
4. **Process** — Four illustrated transition steps.
5. **Benefits** — Numbered two-column cards with dark diagrams.
6. **Social proof** — Compact metric-first case-study cards.
7. **Objection handling** — Audience-specific split FAQ.
8. **Closing call** — Large illuminated invitation and dark footer.

**Transfer:** Tie claims to operational and economic outcomes while keeping the consumer-friendly directness.

### Organization and culture story

1. **Origin** — Centered headline, warm studio portrait and narrow narrative.
2. **Quantified proof** — Paper band with blue numerals on white cards.
3. **Human connection** — Team introduction, candid photographic mosaic and culture metrics.
4. **External credibility** — Paper-backed press cards.
5. **Utility ending** — Porcelain subscription/navigation footer.

**Transfer:** Use natural photography, human first-person writing and warmer neutral surfaces instead of forcing sales-page glows into every chapter.

## Writing

Confident, plainspoken and impatient with unnecessary complexity. Ambition is expressed through direct benefits, short declarations and concrete proof, with occasional conversational humor rather than corporate ceremony.

**Do not copy:** Do not reuse the brand name, logos, customer identities, portraits, product artwork, proprietary claims, plan details, metrics, testimonial quotations or press headlines. The source examples illustrate cadence only; new claims must belong to the new product and be substantiated.

- **Addressing the reader:** Speak directly to you and your team; use we for the organization and name the product when explaining how it works.
- **Rhythm:** Short declarative headline fragments, often split by full stops; one or two readable sentences of support. Buttons begin with verbs. Longer operational explanations are reserved for benefit cards and FAQ answers.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening declaration | Stack categories, then resolve them into a compact unified promise. | 2–8 words per phrase | “NEWSLETTERS. PODCASTS. COMMUNITY. ONE PLATFORM.” |
| Section headline | State an outcome as an assertive sentence, not a feature inventory. | 4–10 words | “Everything you need to turn attention into growth.”<br>“Keep your workflow. Upgrade your infrastructure.” |
| Supporting copy | Name the practical capabilities and then remove a familiar frustration. | 1–2 sentences | “Publish your best work, grow your audience, unlock new revenue, and understand what's working. [Brand] brings it all together, no digital duct tape required.” |
| Action | Verb plus immediate benefit or clear destination; free is used where genuinely true. | 3–5 words | “Get started free”<br>“Talk to sales →” |
| Closing declaration | A direct invitation or brief imperative, with one clear next step. | 5–7 words | “WHAT ARE YOU WAITING FOR?”<br>“START BUILDING. KEEP GROWING.” |
| Human narrative | First-person concrete history with a lightly informal aside. | 2–4 sentences per paragraph | “We're 100% remote, spread across 12 countries, and genuinely like each other.” |

**Words and phrasing to use:** build; grow; earn; your way; get started; no coding required; keep your workflow; built for; turn attention into outcomes

**Avoid:** synergize; revolutionary ecosystem; unlock unprecedented synergies; best-in-class solutions; passive abstract noun chains

**Rules:**

- Name the user's intended outcome before listing mechanisms.
- Use numerals for proof, with a short explanation of what each number means.
- Let headings be emphatic without making paragraphs all caps.
- Reassurance belongs directly under conversion actions when it removes a real barrier.
- Use comparison copy to clarify a job or workflow, not merely to insult alternatives.

## Do's and Don'ts

### Do

- Keep default section leads at 48px/1 in uppercase ClashGroteskFont 700.
- Keep a 16px gap between major headings and their support copy.
- Stage crisp functional media above dim violet light rather than blurring the UI itself.
- Use 6px action corners, 8px stat-card corners and 12px media-panel corners distinctly.
- Leave 64px between a heading group and its major demonstration.
- Use white pricing cards as a deliberate interruption within the midnight canvas.
- Preserve the 308px × 425px portrait/metric rhythm in the moving proof device.
- Finish landing pages with the illuminated conversion panel and a separate utility footer.

### Don't

- Do not turn every button into a pill; pills belong to switches, small tags and testimonial controls.
- Do not replace the midnight canvas with neutral black; the blue-violet undertone matters.
- Do not apply negative tracking globally to the 48px and 60px display recipes; their tracking is normal.
- Do not use neon pink as a full-page background in the default theme.
- Do not add thick bright outlines or elevated material shadows to ordinary dark panels; their border is 6% white.
- Do not recolor customer photography into purple duotone; portraits retain natural color.
- Do not give all numeric proof the pricing font: metrics use the display face while prices use Satoshi.
- Do not use the warm-paper company bands as a universal alternating background for product landing pages.

## Motion and responsive

### Motion

**Observed:**

- Primary layered actions declare transform 0.125s ease-out with hover scale(1.02).
- Proof tiles declare color/background transitions of 0.15s cubic-bezier(0.4,0,0.2,1).
- Proof lanes declare 100s linear infinite movement; trusted-logo marquees declare 85s linear infinite movement.
- Capability tiles declare flex-grow 0.35s cubic-bezier(0.65,0,0.35,1), with related opacity changes.
- The opening media declares a repeating 9.05s fade/blur animation with a 3.4s delay.

**Transfer:**

- Retain the slow edge-faded proof movement and compact button scale response; product surfaces should feel staged rather than springy.
- Keep repeated lanes continuous, with duplicated content only for a seamless loop.

**Unknown:**

- Exact live sequence of hero media changes, flip interactions and all intermediate animation poses.
- Focus-visible and active appearance for most actions; no custom values established.

### Responsive

**Observed:**

- Shared section wrappers declare 20px narrow gutters, 32px medium gutters and 128px wide gutters; vertical padding steps through 40px, 64px and 96px.
- Default hero declares 42px/44px narrow type before larger size steps.
- Stat grids declare one column, then two, then four; light feature grids declare one, two and four columns.
- Proof tiles declare 220px × 300px on narrow layouts and 308px × 425px at medium widths.
- Business comparison uses horizontal overflow and a minimum-width internal table.

**Transfer:**

- Stack the opening text above its product constellation on narrow layouts while retaining overlapping panels and the gradient payoff.
- Retain cropped, edge-faded horizontal proof lanes rather than squeezing every tile into the viewport.
- Let the comparison matrix scroll while decision cards stack; keep the pricing information aligned within each card.

**Unknown:**

- Exact mobile menu behavior, mobile footer composition and breakpoint-specific interaction states.
- Only desktop layout is visually established; narrow-layout composition guidance extends the declared rules.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
