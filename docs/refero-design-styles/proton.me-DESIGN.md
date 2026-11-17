# Proton — soft light, firm convictions

## Overview

A light, spacious technology style with an unusually editorial voice: fine serif headlines sit above practical sans-serif explanations. Deep purple text and vivid violet actions are surrounded by white, pale gray and lilac light. Product interfaces, softly lit device scenes and everyday photography make technical benefits tangible without making the page feel like a dashboard. It suits consumer tools and trust-led services, with a darker aubergine-and-cyan variant for business audiences.

### Essentials

- Editorial conviction rather than oversized tech slogans: regular serif headlines use 60px/1.06 with -0.04em tracking, followed by 16px sans-serif support; chapter headings retain the same fine serif construction at 36px.
- The opening is a centered promise above a luminous product constellation: a 768px text column, paired 50px pill actions, then a compact field of small capability tiles fading into white. Keep this visual device even for a single-purpose product by representing its capabilities rather than inventing a suite.
- Actions are friendly capsules, not hard-edged controls: violet fill or a 2px violet inset outline, 9999px radius, 12px 20px padding, 16px/26px semibold labels; compact chapter actions are 38px high.
- Color behaves like light at the margins: white dominates the ordinary page, deep purple carries headings, and violet concentrates in actions, icons and pale lilac gradients. Preserve a soft edge glow and a rounded gradient proof panel; reserve full aubergine bands with cyan actions for business-oriented variants.
- Product benefits are staged as objects, not raw interface dumps: alternate 592px-wide media and text columns across a 96px gutter; rounded 24px scenes combine device edges, selected interface fragments and restrained floating notification cards. Without device assets, use a focused interface vignette over lilac light.
- Trust gets both intimate and monumental treatments: compact avatar/rating/editorial proof near the opening, a centered 48px serif proof statement inside a 24px-radius pale gradient panel, and a spacious serif closing invitation accompanied by a row of small capability icons.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#6d4aff` | `--color-action` | action, link, accent | Primary actions, outlines, small badges and link text; not a full-page default fill. |
| Pressed violet | `#4a2dc5` | `--color-action-hover` | action, link | Declared hover color for violet actions and text links. |
| Purple ink | `#372580` | `--color-ink` | text | Headlines, navigation and selected body emphasis. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Purple glow | `#c5b7ff` | `--color-purple-light` | accent, surface, border | Lower-left light on the broad proof panel and fine legal link dividers. |
| Lilac light | `#e2dbff` | `--color-lilac` | surface, accent | Media gradient endpoints and soft rectangular badges. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate body | `#4b5563` | `--color-body` | text | Paragraphs, captions and ordinary explanatory text. |
| Soft gray edge | `#e1e3e7` | `--color-soft-rule` | border | Visible #9ca3af at 0.3 over white for accordion separators and small icon tile edges. |
| Footer column rule | `#e3e6e9` | `--color-footer-rule` | border | Visible #d1d5db at 0.6 over white for vertical footer separators. |
| Structural hairline | `#e5e7eb` | `--color-rule` | border | Table cell borders and full-width footer separator. |
| Control track | `#ebedef` | `--color-control-track` | surface | Visible #9ca3af at 0.2 over white for carousel timer tracks. |
| Translucent gray wash | `#f5f6f7` | `--color-wash` | surface | Visible result of #9ca3af at 0.1 over white; process cards, quote cards and slider controls. |
| Cool gray panel | `#f6f7f9` | `--color-panel` | surface | Broad editorial panels and gradient staging grounds. |
| Pale gray panel | `#f9fafb` | `--color-panel-light` | surface | Low-contrast feature cards. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas, interface cards and reverse text on violet actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| business-oriented sections and pages | Aubergine | `#1b1340` | `--color-business-dark` | background, text | Business hero, conversion panels and business footer; dark text on cyan actions. |
| business-oriented sections and pages | Luminous cyan | `#67e8f9` | `--color-business-action` | action, link, accent | Filled actions and outlined demo actions against aubergine. |
| consumer product and pricing pages | Lilac canvas | `#f7f5ff` | `--color-lilac-canvas` | background | Top and bottom gradient endpoints, tinted navigation and footer. |
| business-oriented dark sections | Reverse secondary text | `#d1d5db` | `--color-reverse-muted` | text | Secondary copy on aubergine. |
| pricing modules | Plan edge | `#d7dadf` | `--color-plan-edge` | border | Visible #9ca3af at 0.4 over white around standard pricing cards. |

## Typography

- **ProtonSerif** — Display promises, chapter headings and editorial subheads. Fine, compact editorial serif with rounded forms and tight spacing; the tone is humane rather than ceremonial. If unavailable, use **Lora**. Use regular 400 and preserve the tight -0.04em tracking; verify line wraps. Font stack: "ProtonSerif", "Lora", Georgia, Cambria, "Times New Roman", serif.
- **ProtonSans** — Body, navigation, actions, captions and price numerals. Readable contemporary sans with open forms; regular prose is contrasted with compact semibold controls. If unavailable, use **Inter**. Use 400, 600 and 700; avoid imposing negative tracking on body copy. Font stack: "ProtonSans", "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ProtonSerif | 400 | 60px | 1.06 | -0.04em | Default centered opening promise and monumental standalone conviction statement. |
| heading-lg | ProtonSerif | 400 | 48px | 1.125 | -0.04em | Major proof statement, editorial chapter introduction and closing invitation. Also the opening headline size on focused product and pricing pages. |
| heading | ProtonSerif | 400 | 36px | 1.11 | -0.04em | Centered chapter headings and broad conversion panels. |
| split-heading | ProtonSerif | 400 | 36px | 1.16 | -0.04em | Left-aligned headings within alternating text/media chapters. |
| subheading | ProtonSerif | 400 | 30px | 1.13 | -0.04em | Unboxed editorial benefit grid titles and FAQ section introductions. |
| question | ProtonSans | 600 | 20px | 1.5 | normal | FAQ prompts and short benefit headlines above portrait media. |
| quote | ProtonSans | 400 | 18px | 1.55 | normal | Editorial endorsements and customer quotations. |
| footer-heading | ProtonSans | 700 | 18px | 1.55 | normal | Footer column titles. |
| body | ProtonSans | 400 | 16px | 1.5 | normal | Default descriptive paragraphs and footer links. |
| body-relaxed | ProtonSans | 400 | 16px | 1.625 | normal | Opening support line, editorial text and prose requiring additional breathing room. |
| action | ProtonSans | 600 | 16px | 1.625 | normal | Full-size and compact chapter buttons; product labels beside icons. |
| small-strong | ProtonSans | 600 | 14px | 1.57 | normal | Navigation, compact header actions, trust labels and discovery links. |
| small | ProtonSans | 400 | 14px | 1.57 | normal | Compact trust captions and secondary plan descriptions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing modules | price | ProtonSans | 400 | 30px | 1.13 | normal | Price amount, with billing interval in small text on the same baseline. |
| focused consumer product chapters | product-subheading | ProtonSerif | 400 | 30px | 1.16 | -0.04em | Alternating product benefit explanations. |
| card-rich product, business and pricing sections | card-heading | ProtonSerif | 400 | 24px | 1.16 | -0.04em | Feature cards, process cards and plan names. |
| consumer product feature modules | feature-heading | ProtonSans | 600 | 24px | 1.34 | normal | Practical feature carousel titles; a more utilitarian contrast to editorial serif chapters. |
| pricing modules | recommended | ProtonSans | 700 | 16px | 1.5 | 0.1em, uppercase | Centered recommendation strip above the highlighted plan. |
| process modules and status labels | step-label | ProtonSans | 700 | 12px | 1.5 | normal | Process step labels and compact status badges. |

**Notes:**

- The serif scale consistently uses -0.04em tracking at regular weight; do not simulate emphasis with bold display text.
- Keep sans-serif tracking normal except the recommendation strip. The large-number treatment is regular sans-serif, not the headline serif.
- Hierarchy is expressed through serif size and white space; ordinary prose remains 16px rather than ballooning into display-sized supporting copy.

## Layout

**Density:** Airy marketing chapters surround compact control groups and readable, moderately dense cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Action pair gap, small icon groups and tightly stacked feature list items. |
| 12px | Icon-to-label gap and full-size button vertical padding. |
| 16px | Headline-to-support gap and paragraph separation. |
| 24px | Small card padding, carousel spacing and footer column inset. |
| 28px | Typical support-copy to action distance. |
| 32px | Card-grid gutters and card text padding. |
| 48px | Chapter inner groups, section top padding and footer vertical padding. |
| 64px | Desktop page side inset and broad panel horizontal padding. |
| 96px | Main section separation, two-column gutter and proof panel vertical padding. |
| 176px | Long editorial pauses around conviction statements and between major narrative chapters. |

### Containers and grids

- **wide-panels**: max width 1536px · side padding 64px. Broad cards and panels within the page; at 1440px the visible panel width is 1312px.
- **chapter**: max width 1280px · side padding 64px. Centered alternating benefit chapters. Treat the maximum as the inner content width; the page side inset provides a separate outer boundary.
- **split**: 2 columns · gap 96px. Equal text and media columns; each is 592px within the 1280px chapter.
- **opening-copy**: max width 768px. Centered default promise, support and actions; concentrated rather than full-width.
- **statement**: max width 896px. Centered proof and standalone conviction headings.
- **reading-column**: max width 540px. Reusable upper limit for descriptive text blocks.
- **benefit-grid**: 3 columns · gap 48px. Unboxed principles or benefit explanations.
- **card-grid** (only for card-rich product and business sections): 3 columns · gap 32px. Rounded explanatory cards.
- **business-feature-grid** (only for business product pages): 4 columns · gap 32px. Eight illustrated capabilities in two rows.
- **plans** (only for pricing modules): max width 1152px · 3 columns · gap 16px. Aligned price comparison cards; the highlighted plan rises above its neighbors.
- **faq** (only for FAQ sections): max width 1152px · gap 32px. Single-column questions, or two 560px columns on a consumer product page.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | media-and-panels | 24px |
|  | badges | 6px |
| pricing modules | plan-cards | 16px |
| business explainer video | video | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| outline-action | `inset 0 0 0 2px #6d4aff` | Secondary action edge without adding to button dimensions. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #ffffff`

**Observed:** Mostly unboxed; the opening is softened by light at its outer edges.

**Transfer:** Let whitespace separate chapters instead of outlining every block.

#### Edge light · level 0

**Use:** Opening atmosphere around centered copy and capability tiles.

**CSS:** `background: radial-gradient(ellipse at 0% 70%, rgba(197,183,255,0.65), rgba(255,255,255,0) 38%), radial-gradient(ellipse at 100% 65%, rgba(226,219,255,0.8), rgba(255,255,255,0) 38%), #ffffff`

**Observed:** The middle stays white and legible; lilac light is concentrated at the sides, with a faint warmer blush toward the right.

**Transfer:** Match the soft edge glow; exact gradient stops are not essential. Do not put a colored disc immediately behind the text.

#### Cool panel · level 1

**Use:** Editorial story blocks and broad feature grouping.

**CSS:** `background: #f6f7f9; border-radius: 24px; overflow: hidden`

**Observed:** Flat, low-contrast framing with no marketing-card drop shadow.

**Transfer:** Use the panel edge and light fill as the grouping mechanism.

#### Light card · level 1

**Use:** Explanatory feature cards.

**CSS:** `background: #f9fafb; border-radius: 24px; overflow: hidden`

**Observed:** Cards can sit in a spacious three-column grid without visible outlines.

**Transfer:** Keep the fill only a small step from white.

#### Gray wash · level 1

**Use:** Process and testimonial cards, compact slider controls.

**CSS:** `background: rgba(156,163,175,0.1); border-radius: 24px`

**Observed:** The translucent surface reads as pale cool gray over the page.

**Transfer:** Preserve its translucency when nested over another light panel.

#### Proof light panel · level 1

**Use:** Prominent social-proof conversion statement.

**CSS:** `background: linear-gradient(to right top, #c5b7ff, #f6f7f9 40%); border-radius: 24px; padding: 96px 64px; overflow: hidden`

**Observed:** Purple light pools in the lower-left while most of the panel remains almost neutral.

**Transfer:** Keep the statement central and the light off-center.

#### Media light panel · level 1

**Use:** Interface video or still vignette backing.

**CSS:** `background: linear-gradient(to right top, #f6f7f9 40%, #e2dbff 100%); border-radius: 24px; overflow: hidden`

**Observed:** The lilac endpoint is concentrated at the upper-right, not spread uniformly.

**Transfer:** Use this behind a real interface vignette, not as a substitute for the object.

#### Lilac ending · level 0

**Only for:** consumer product and pricing pages

**Use:** FAQ-to-footer transition.

**CSS:** `background: linear-gradient(#ffffff 0%, #f7f5ff 100%)`

**Observed:** The questions begin on white and descend into the tinted footer without a hard band.

**Transfer:** Carry the final gradient endpoint through the footer.

#### Business dark panel · level 1

**Only for:** business-oriented sections and pages

**Use:** Business opening, migration and conversion modules.

**CSS:** `background: #1b1340; color: #ffffff; border-radius: 24px`

**Observed:** Inset modules are rounded; the business opening and footer are full-bleed with square outer boundaries.

**Transfer:** Pair with cyan actions, pale secondary copy and a dark interface scene.

## Components

### Navigation

**Use:** Persistent low-profile access to product categories and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 40; height: 48px; background: #ffffff; padding: 0px 64px; color: #372580`

**Text style:** `small-strong` — ProtonSans 600 · 14px/1.57

**Observed:** Small brand mark at left, category controls in the middle, language and account actions at right. Category pills use 6px 16px padding and 4px gaps; compact account actions are 30px high. The consumer product variant uses a lilac background; the business variant uses aubergine with white text.

**States:** Declared: hover category background rgba(109,74,255,0.1); focus-visible category background rgba(109,74,255,0.1).

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #6d4aff; color: #ffffff; border-radius: 9999px; padding: 12px 20px; height: 50px; gap: 8px`

**Text style:** `action` — ProtonSans 600 · 16px/1.625

**Observed:** Width follows the label. The chapter variant uses 6px 20px padding and 38px height; the header uses a 14px label and 30px height. Business dark modules replace violet with cyan and use aubergine text.

**States:** Declared: hover background #4a2dc5 and white text; focus-visible text-decoration none and box-shadow 0 0 #0000, 0 0 #0000, 0 0 #0000; active transform remains identity.

### Outline button

**Use:** Peer comparison or secondary conversion beside the primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; color: #6d4aff; background: transparent; border-radius: 9999px; padding: 12px 20px; height: 50px; box-shadow: inset 0 0 0 2px #6d4aff`

**Text style:** `action` — ProtonSans 600 · 16px/1.625

**Observed:** Placed 8px from its filled partner. On dark business modules, the demo variant has a cyan inset outline and white label.

**States:** Declared: hover background #4a2dc5 and white text; focus-visible keeps inset 0 0 0 2px #6d4aff and removes text decoration.

### Discovery link

**Use:** Low-pressure detail action beneath an explanation.

**CSS:** `color: #6d4aff; padding: 4px 0px`

**Text style:** `small-strong` — ProtonSans 600 · 14px/1.57

**Observed:** Inline label followed by a small right chevron; no filled background. Chapter-level exploration also appears as a transparent pill aligned with the compact primary button.

**States:** Declared: hover underline and color #4a2dc5; focus-visible text-decoration none and box-shadow 0 0 #0000, 0 0 #0000, 0 0 #0000.

### Carousel controls

**Use:** Browse product scenes or testimonials without making the controls prominent.

**CSS:** `display: flex; align-items: center; background: rgba(156,163,175,0.1); border-radius: 9999px; height: 48px; padding: 0px 20px; gap: 16px`

**Observed:** A small pill groups 8px dots or a 60px by 8px timer track. Adjacent 48px circular previous/next or play controls use the same faint fill; the group sits 24px below media. Active marks are darker than inactive marks.

**States:** Declared: hover and focus-visible arrow control background rgba(156,163,175,0.3); inactive dot hover background rgba(156,163,175,0.6).

### Footer column

**Use:** Finish with a comprehensive resource directory.

**CSS:** `border-left: 1px solid rgba(209,213,219,0.6); padding-left: 24px`

**Text style:** `body` — ProtonSans 400 · 16px/1.5

**Observed:** Bold 18px heading above 16px links. A brand/address/social column precedes the directory, and the products group spans two link columns. A horizontal rule separates utility links and language control from the directory; small legal links and copyright sit below. Default footer is white; consumer product and pricing footers are lilac, and the business footer is aubergine with lighter dividers.

**Transfer:** Organize real destinations by purpose; retain the vertical-rule directory treatment even with a smaller catalog.

### Feature card

**Only for:** card-rich product and business sections

**Use:** Group one practical benefit with an illustration or small emblem.

**CSS:** `background: #f9fafb; border-radius: 24px; overflow: hidden`

**Text style:** `card-heading` — ProtonSerif 400 · 24px/1.16 · tracking -0.04em

**Observed:** Text is left aligned, with a small illustration or icon above the title and one explanatory paragraph below. Business capability cards instead use the Cool panel with a dark illustration occupying the top 222px and 24px serif titles beneath.

**Transfer:** Use one benefit per card and equalize card rows by layout, not by padding each paragraph with filler.

### Plan card

**Only for:** pricing modules

**Use:** Present comparable purchase tiers.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 16px 8px; border: 1px solid rgba(156,163,175,0.4)`

**Text style:** `card-heading` — ProtonSerif 400 · 24px/1.16 · tracking -0.04em

**Observed:** Name, short description, price with interval, full-width action, checked features and billing note read top-to-bottom. Internal content rows add 16px horizontal and 8px vertical padding. The recommended plan has a violet outer shell and a 40px uppercase strip, with white content below and a filled action; neighboring plans use outline actions.

**Transfer:** Align equivalent rows across plans. Use a single highlighted recommendation rather than making every tier look selected.

### FAQ row

**Only for:** FAQ sections

**Use:** Resolve purchase or usage objections.

**CSS:** `border-top: 1px solid rgba(156,163,175,0.3); padding: 16px 0px`

**Text style:** `question` — ProtonSans 600 · 20px/1.5

**Observed:** Question at left, 48px circular hit area containing a violet plus at right; first row lacks the top rule. Rows are about 81px high. Business questions use 18px semibold labels; consumer FAQ can be split into two columns.

**Transfer:** Keep the answer subordinate and the closed state visually light.

### Status badge

**Only for:** status labels and pricing promotions

**Use:** Small new-feature or promotion marker.

**CSS:** `display: inline-block; background: #e2dbff; color: #6d4aff; border-radius: 6px; padding: 4px 12px`

**Text style:** `step-label` — ProtonSans 700 · 12px/1.5

**Observed:** Small rectangular tag with softened corners, distinct from the pill-shaped buttons. Promotional wording may be uppercase; process labels use the same type without the fill.

## Imagery and graphics

### Capability constellation

**Use:** Signature product object beneath the opening promise and compact icon echo near the close.

**Observed:** Small outlined white tiles form staggered horizontal rows. Glossy folded-looking icons sit above short gray labels, with purple as the anchor and occasional cyan, blue or green. The tile field is about 768px wide and 283px high, with the outer and lower rows fading into white.

**Transfer:** Represent the new product's meaningful capabilities in this tile field. If no icon assets exist, make simple folded geometric symbols with a shared purple-light palette; do not replace the field with a single stock laptop.

**Build:** Use three staggered flex rows of roughly 80px square tiles with 20px gaps, 1px pale gray edges and small softened corners. Place 28px–36px SVG symbols above short labels. Mask the group with a white-to-transparent fade at its sides and bottom; place the Edge light surface behind it. Show actual labeled capabilities in the center rather than empty tiles.

### Device and interface scenes

**Use:** Primary imagery in alternating benefit chapters.

**Observed:** Half-width, often square 592px scenes: close-cut laptop or phone edges, legible selected interface areas, soft lilac backing and occasional floating utility cards. Portrait carousel panels can be 360px by 560px. Device edges can run outside the media boundary while the outer scene remains clipped to 24px corners.

**Transfer:** Show one real workflow and one useful result. The minimum version is a carefully composed interface fragment with a colored backing and one floating summary card, not a full application recreated at tiny scale.

**Build:** Inside a 24px clipped light panel, position an interface layer over a lilac gradient and offset a small white or translucent result card across its front. Use restrained, soft purple ambient shading only around the illustrated objects; keep the surrounding marketing surface flat.

### Everyday photography with utility overlays

**Use:** Humanize technical benefits and team usage.

**Observed:** People using phones, talking together or working at laptops, cropped close enough that hands and devices matter more than posed faces. Muted blue, lilac and warm clothing tones harmonize with the palette. A selected notification or credential card floats over the photograph; business scenes may add certification badges.

**Transfer:** Use believable task-oriented photography with one relevant interface result. Keep overlays small enough that the photograph still reads as a human moment.

### Soft peripheral glow

**Use:** Signature atmosphere in the opening and proof panel.

**Observed:** Broad lilac haze comes in from the edges; the background remains essentially white at the center. The proof panel places a stronger light pool at its lower-left corner.

**Transfer:** Recreate the light as a spatial effect around content, not an ornamental rainbow or a wallpaper texture.

**Build:** Layer oversized elliptical radial gradients behind the content using rgba(197,183,255,0.65) and rgba(226,219,255,0.8), fading to transparent over about 38% of the stage. Keep the center white. Use the exact Proof light panel gradient for the inset proof block.

### Documentary and editorial collage

**Use:** Long-form credibility or origin stories.

**Observed:** A wide photographic panel pairs cool-gray explanatory text space with an architectural or scientific location image carrying a subtle purple cast. A separate collage uses overlapping editorial snippets and a video still, all with white backing and soft pale edges.

**Transfer:** Use a real place, process or independently published material relevant to the product's credibility. Prefer an honest single documentary image over invented press clippings.

### Luminous dark product stage

**Only for:** business product openings

**Use:** Large demonstration beneath the business promise.

**Observed:** A dark desktop interface floats in front of a broad translucent folded silhouette; cyan and violet light lift its upper edges. A larger message preview overlaps the right side and proof badges overlap the lower left. The media spans a 1312px region and continues below the first viewport.

**Transfer:** Stage the new product's dark interface with one enlarged outcome and earned proof, keeping the center readable and the light peripheral.

**Build:** Use an aubergine stage; behind a centered dark interface, draw two large angular SVG wings in translucent violet with 24px softened corners. Add a blurred cyan ellipse behind the upper-right edge and violet behind the upper-left. Layer one semitransparent dark preview card over the interface edge. Without a dark application, use a few faithful dark task panels rather than recoloring the entire marketing page.

### Photographic conversion banner

**Only for:** business conversion sections

**Use:** Dark, compact final call before questions.

**Observed:** A wide rounded photograph of people at laptops carries a dark purple tint, centered white serif text and cyan action. Broad variants are 1280px by 310px or 1312px by 382px.

**Transfer:** Choose a work-in-context photograph with a calm central area for the message; use a dark purple overlay to establish reliable contrast.

**Build:** Clip the photo to 24px corners, cover with an aubergine overlay at roughly half opacity and center a short white heading above cyan actions. Keep the image identifiable through the tint.

### Icons

**Observed:** Utility SVGs are predominantly 20px or 24px, with 1.5px rounded strokes. Small inclusion checks are 16px white strokes on green circles in comparison tables. Product emblems are richer gradient symbols, usually 48px in lightly outlined softened-square tiles; small suite rows use smaller versions.

**Transfer:** Keep utility icons monochrome and functional. Reserve folded gradients and glossy depth for capability emblems; keep the outline and optical weight consistent across all new emblems.

## Section recipes

How recurring sections are built.

### First screen: Luminous promise opening

**Observed:** A 48px sticky Navigation sits above a centered 768px-wide text column. The opening has 64px top padding; the 60px display promise occupies two lines, followed after 16px by a single 16px support line, then after 28px by paired Primary button and Outline button with an 8px gap. Beneath them, the Capability constellation forms a compact 768px by 283px object. White is the base, peripheral lilac Edge light is behind everything, tiles sit above it, and text/actions are the sharpest foreground layer. Within the first 900px, the headline, support, both actions, full main object and compact three-part trust strip are visible. The first detailed benefit chapter begins below that screen.

**Transfer:** For a different product, turn its core workflows into a coherent constellation of icons and short labels rather than copying an existing suite. Keep the promise and object distinct, so both read immediately. Focused consumer pages use a 48px heading over a pale lilac-to-white opening, trust strip and a larger device scene; pricing pages open with the 48px title followed directly by category/billing selectors and plans. Business pages use the dark stage, a 48px white heading and cyan actions, with the demonstration continuing below the fold.

**Avoid:** Do not turn the opening into a left-aligned SaaS split hero, enlarge the support copy to compete with the serif promise, or replace the constellation with empty decorative boxes.

**Text style:** `display` — ProtonSerif 400 · 60px/1.06 · tracking -0.04em

### Alternating benefit chapter

**Observed:** The split layout places vertically centered text opposite a 592px media stage. A 36px split-heading introduces one theme, followed by small capability icon/label groups, 16px prose and compact 38px actions. Media and text swap sides in later chapters. Carousel controls sit beneath the stage rather than inside a heavy navigation frame.

**Transfer:** Group related benefits around one human outcome and alternate the side of the media without changing the type language.

**Text style:** `split-heading` — ProtonSerif 400 · 36px/1.16 · tracking -0.04em

### Standalone conviction

**Observed:** A centered 896px text area uses display type and one filled action. About 176px of vertical section padding on both sides makes the statement feel like an editorial pause, not a card.

**Transfer:** Use a strong product belief or outcome that deserves a pause; keep the statement shorter than the surrounding explanatory chapters.

**Text style:** `display` — ProtonSerif 400 · 60px/1.06 · tracking -0.04em

### Broad proof invitation

**Observed:** The Proof light panel sits inside 64px page insets, with 96px internal vertical padding, a small identity mark, a centered 48px serif statement and paired conversion actions. A number is integrated into the sentence instead of isolated as a giant dashboard statistic.

**Transfer:** Use a substantiated proof point or result; retain the sentence-like monumental treatment and off-center light.

**Text style:** `heading-lg` — ProtonSerif 400 · 48px/1.125 · tracking -0.04em

### Unboxed benefit matrix

**Observed:** Three columns with 48px gaps carry 30px serif titles, 16px/26px prose and small Discovery links. A second row is separated by 48px. No card fill or icon container is needed for these editorial explanations.

**Transfer:** Let titles and text do the work when the content explains principles rather than discrete UI features.

**Text style:** `subheading` — ProtonSerif 400 · 30px/1.13 · tracking -0.04em

### Illustrated card chapter

**Observed:** Centered 36px chapter heading precedes Feature cards. Business capabilities use four columns with 32px gutters and dark miniature interface illustrations above pale text areas; supporting assurances use three columns with smaller emblems. Consumer feature carousels use 490px-wide gradient cards, 24px gaps and semibold sans-serif titles.

**Transfer:** Choose the grid for breadth and the carousel for focused product details; keep each illustration specific to its title.

**Text style:** `heading` — ProtonSerif 400 · 36px/1.11 · tracking -0.04em

### Editorial story panel

**Observed:** A Cool panel pairs a roughly half-width documentary image with a text column. Short serif story titles are followed by readable 16px/26px paragraphs and a Discovery link; a secondary story can appear as an accordion row below.

**Transfer:** Use this for origin, method or responsibility content only when it advances trust. It need not always sit near the end.

### Closing invitation and endorsement

**Observed:** A small capability-icon row precedes a centered 48px serif invitation, a 16px support line and one filled action. Independent editorial endorsements form three 416px columns below, with muted publication marks and 18px quotations; a substantial white-space pause precedes the directory footer.

**Transfer:** Echo the opening constellation in miniature, resolve the promise into one action, and use independent proof where available rather than inventing testimonials.

**Text style:** `heading-lg` — ProtonSerif 400 · 48px/1.125 · tracking -0.04em

### Questions into directory

**Observed:** FAQ row groups occupy a 1152px region. Consumer and pricing endings fade to the Lilac ending surface; the business ending stays white through questions and then changes to an aubergine footer. The Footer column directory finishes with social/contact context, utility links, language control and a fine legal row.

**Transfer:** Keep questions and navigation as distinct closing functions. Do not end abruptly at the conversion banner.

**Text style:** `question` — ProtonSans 600 · 20px/1.5

### Migration process

**Only for:** onboarding and switching sections

**Observed:** A broad Gray wash group with 24px outer corners contains a centered 36px heading and three columns separated by 32px. Step labels precede 24px serif titles and 16px prose; selected interface images anchor the lower parts. A centered filled action closes the group.

**Transfer:** Describe a genuinely short process with meaningful intermediate states, then offer the next action.

**Text style:** `heading` — ProtonSerif 400 · 36px/1.11 · tracking -0.04em

### Plans and comparison

**Only for:** pricing pages and embedded pricing modules

**Observed:** A centered 48px title or 36px section heading precedes capsule selectors. Three Plan cards share row alignment with 16px gutters; the violet recommended shell rises above its neighbors. A detailed comparison uses four equal 328px columns, 1px rules, 8px 16px cell padding and 80px pale category bands.

**Transfer:** Keep plan choice scannable before exposing the denser specification matrix. Use real prices and comparable units.

**Text style:** `heading` — ProtonSerif 400 · 36px/1.11 · tracking -0.04em

## Page flow

**Storyline:** Promise → tangible product experience → benefit chapters → trust and differentiation → next-step invitation → practical reassurance and resource directory.

### Introduce a broad product family and its point of view

1. **Promise** — Centered editorial promise, capsule action pair, luminous capability constellation and compact trust strip.
2. **Capability chapters** — Alternating text/media chapters combine related tools into human outcomes.
3. **Differentiation** — A standalone conviction statement leads into explanatory editorial text and documentary media.
4. **Quantified proof** — Broad gradient invitation treats a proof number as part of a sentence, followed by an unboxed benefit matrix.
5. **Credibility** — A cool story panel presents origin and independent context.
6. **Closing call** — Capability icons, centered invitation and one action are followed by three editorial endorsements.
7. **Resource directory** — White multi-column footer with vertical rules, social/contact block, utility and legal rows.

**Transfer:** Use breadth without making a tile directory the entire page: select a few outcome-led chapters and preserve the change of pace between demonstration, conviction and proof.

### Help readers choose a subscription and understand tradeoffs

1. **Promise** — Compact centered title on a lilac-to-white opening.
2. **Pricing** — Category and billing capsules precede three plans with one recommendation.
3. **Audience routing** — Two pale cards route readers to other use cases.
4. **Comparison** — Long categorized four-column matrix with subtle borders and green inclusion marks.
5. **Closing call** — Wide purple-tinted work photograph and cyan action.
6. **Objection handling** — Single-column FAQ fades into a lilac directory footer with utility and legal rows.

**Transfer:** Make the initial plan choice brief and readable; put exhaustive details later. End with practical questions rather than another oversized slogan.

### Sell a trusted tool to organizations

1. **Promise** — Dark centered hero with white serif headline, cyan filled action, outlined demo action and trust copy.
2. **Product demonstration** — Dark luminous interface stage with overlapping result preview and earned badges, followed by press marks.
3. **Capability chapters** — Four-column illustrated capabilities, explainer video and three-column assurance cards.
4. **Adoption reassurance** — Rounded dark migration panel and a suite/workflow split chapter.
5. **Social proof** — Organization-focused heading and horizontally browsable quote cards.
6. **Closing call** — Wide purple-tinted photograph with centered promise and two cyan-themed actions.
7. **Objection handling** — Single-column questions on white, then full aubergine directory footer and utility/legal rows.

**Transfer:** Keep the business tone confident but approachable; reserve the darker palette for opening, reassurance and conversion rather than darkening every card.

### Explain one consumer product and make adoption feel easy

1. **Promise** — Lilac-to-white hero, action pair and trust strip above a large phone/interface composition.
2. **Benefit chapters** — Centered chapter question followed by alternating photo/UI explanations.
3. **Adoption reassurance** — Three-step process panel with interface fragments and a closing action.
4. **Pricing** — Small supporting benefit grid precedes three aligned plans.
5. **Social proof** — An editorial trust chapter pairs text with a collage, then practical feature cards form a carousel.
6. **Closing call** — Pale split invitation, miniature capability row and an aubergine business-audience conversion panel.
7. **Objection handling** — Two-column questions fade into a lilac directory footer, utility links and legal row.

**Transfer:** Lead with the product's concrete experience, handle switching cost before a plan decision, and route secondary audiences without replacing the primary call.

## Writing

Principled, plainspoken and protective. Confidence comes from explaining mechanisms and consequences in everyday language, with warmth conveyed through direct invitations rather than jokes or hype.

**Do not copy:** Do not reuse Proton names, logos, product emblems, proprietary interface art, quotations, customer counts, institutional endorsements, certifications, legal assurances or privacy claims. Replace them with the new product's verified capabilities, evidence and earned marks. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for beliefs and accountability. Name the product when explaining an operation rather than speaking in abstract corporate language.
- **Rhythm:** Short benefit headlines often join a practical verb with a one-word emotional payoff. Support lines are usually one sentence; explanatory passages use two short paragraphs. Actions are concise verb-led phrases, with little punctuation and no exuberant exclamations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Frame a better outcome as a direct benefit or a simple conviction. | 6–11 words | “A better internet starts with privacy and freedom”<br>“Secure email that protects your privacy” |
| Chapter heading | Pair concrete actions with a short emphatic qualifier, or state an unwanted problem in plain words. | 4–9 words | “Store, share, collaborate. Securely.”<br>“No more trackers in your inbox” |
| Supporting line | Name the benefit and the mechanism without a string of superlatives. | One sentence | “Take control of your data with end-to-end encryption.” |
| Primary action | Use a verb and an explicit next step; state a meaningful low-friction condition when true. | 2–5 words | “Create a free account”<br>“Request a demo” |
| Trust heading | Put the proof into an ordinary sentence rather than a detached oversized counter. | One or two display lines | “Over 100 million people and businesses have signed up for [Brand]” |
| FAQ question | Use the reader's natural first-person purchase or usage concern. | 5–12 words | “What payment methods can I use?”<br>“Can I switch to a new plan at any time?” |

**Words and phrasing to use:** your; take control; protect; private by default; easy-to-use; keep; switch; trusted; one account; secure; no ads; built for

**Avoid:** revolutionary; game-changing; 10x everything; military-grade as unexplained praise; magic as a technical explanation; exclusive club language; relentless exclamation marks

**Rules:**

- Tie every strong promise to a concrete product mechanism, support policy or demonstrable result.
- Use contrast sparingly: explain how the product differs, then return to what the reader gains.
- Separate action intent: a filled button starts or buys, an outline compares, and a discovery link explains.
- Write card titles as benefits, not internal feature codenames.
- Use absolute language only where it is supportable; concise does not mean legally careless.

## Do's and Don'ts

### Do

- Keep the main serif promise at regular 400 with -0.04em tracking.
- Keep the opening text constrained to 768px and its support at 16px.
- Use 50px capsules for primary conversion and 38px capsules within benefit chapters.
- Preserve the white center and lilac edges of the opening light.
- Use the 96px split gutter to let media breathe beside explanatory text.
- Integrate a proof number into a 48px serif sentence inside the rounded gradient panel.
- Echo the capability field with a compact icon row at a closing invitation.
- Use flat 24px-radius panels and subtle separators instead of floating every content group.

### Don't

- Do not substitute bold geometric sans headlines for the fine regular serif hierarchy.
- Do not make the whole ordinary page violet; concentrate saturation in actions and staged objects.
- Do not turn 6px rectangular status badges into button-like pills.
- Do not apply interface-style drop shadows to all marketing cards; keep depth concentrated in illustrated objects.
- Do not use a giant isolated statistic counter where the proof is meant to read as a sentence.
- Do not give every plan a filled violet action and recommendation strip.
- Do not make footer groups borderless floating islands; retain their subtle vertical-rule organization.
- Do not use cyan actions on ordinary light consumer chapters as a second competing primary palette.

## Motion and responsive

### Motion

**Observed:**

- Actions declare color, background-color, border-color and box-shadow transitions of 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- Navigation declares top and background-color transitions with the same duration and easing.
- Product scenes use carousel dots, timer tracks and play/pause controls. No running animation was established for the individual scenes.

**Transfer:**

- Keep interaction feedback compact and color-led rather than adding bounce to capsules.
- Preserve the understated timer/dot treatment when multiple demonstrations share a stage.

**Unknown:**

- Carousel autoplay intervals, scene animation timelines and precise video motion are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px and 1280px.
- Opening headline classes progress through 36px, 48px and 60px sizes. Page inset classes use 16px, 32px and 64px.
- Split chapters declare one column before the two-column layout; business card grids declare one, two and four-column arrangements in their respective modules.

**Transfer:**

- On narrow screens, keep the centered promise and tile constellation relationship, reducing tile field breadth rather than making all icons a single unbroken row.
- Stack paired text/media chapters while preserving their chapter heading and local action group. Reduce the side glow so it frames rather than floods the copy.
- Let card carousels retain visible continuation while keeping the text inset readable.

**Unknown:**

- Exact mobile scene arrangements, crop positions, navigation drawer behavior and observed small-screen line wraps are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
