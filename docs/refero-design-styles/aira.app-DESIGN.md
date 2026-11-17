# Aira — boardroom cinema meets paper

## Overview

An editorial serif voice meets cinematic product scenes and restrained, practical software detail. Black, warm ivory and charcoal alternate in broad chapters, with small green status marks rather than a dominant bright brand color. Realistic desktop and phone compositions, atmospheric photography and fine-lined diagrams give business software a tangible, executive feel; spacious framing surrounds relatively compact copy.

### Essentials

- Literary promises sit over tangible software: regular Gestura Headline at 54.9px/1 with -0.02em tracking, paired with Inter support and a realistic monitor scene occupying the right half of the opening.
- The opening is a dark, inset cinematic window, not a floating dashboard on a gradient: a 60px navigation bar sits above an 840px stage with 16px insets and an 8px image radius. Keep a product object and the headline, support and two actions visible together.
- Actions are compact lozenges with reversed contrast: 44px hero pills use 11px 20px padding; ordinary content actions are 40px tall with 13px 24px padding. A white primary and fine dark-outline secondary sit on dark imagery.
- Color belongs to imagery and tiny signals: structural surfaces stay #080808, #f0efed and #fbfaf8; green and red appear as small status marks, not broad brand fills. Dark photographic and black chapters occupy most of a long narrative landing page.
- Software is staged at two distances: a believable device in a softly lit setting, then a crisp, almost square-cornered interface or flow diagram inside a 4px-radius ivory panel. Include both modes; use a simple native-interface mockup if no production interface exists.
- Proof becomes a cinematic interlude: a dark atmospheric landscape or orbital scene carries a centered 48px serif statement and a ruled row of 72px Inter statistics. Preserve this visual device using truthful metrics and an abstract scale illustration when geographic imagery is irrelevant.
- The ending returns to warm paper and oversized editorial navigation: a 484px footer leaves the left half largely open, with 24px/1.2 serif links grouped on the right and small institutional details at the lower left.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Technical bronze | `#a06a32` | `--color-bronze` | text, accent | A sparse commercial product eyebrow; never a broad fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#2c2c2b` | `--color-ink` | text, action | Primary text on paper and dark content buttons. |
| Cinema black | `#080808` | `--color-night` | background, surface, text | Dark chapters, opening stage and light-button text. |
| Cool ink | `#1c1d1f` | `--color-article-ink` | text | Article headlines and light navigation text. |
| Dark outline | `#444444` | `--color-outline` | border | Secondary action outlines against cinematic black. |
| Institutional gray | `#70706f` | `--color-legal` | text | Small footer and institutional details. |
| Muted charcoal | `#80807f` | `--color-muted` | text | Secondary light-section text; charcoal at 0.6 alpha on near white. On ivory, allow the same alpha recipe to warm with its backing. |
| Fine neutral edge | `#e5e5e5` | `--color-edge` | border | Visible equivalent of black at 0.1 alpha on near white; use the alpha recipe for panel outlines. |
| Warm paper | `#f0efed` | `--color-paper` | background, text | Broad light chapters and reversed text on charcoal. |
| Soft ivory | `#f9f8f6` | `--color-footer` | background, surface | Footer, light navigation variant and tinted pricing sections. |
| Ivory panel | `#fbfaf8` | `--color-panel` | surface | Feature and technical demonstration panels. |
| Near white | `#fefefe` | `--color-canvas` | background | Underlying light page canvas. |
| White | `#ffffff` | `--color-white` | text, surface, border | Dark-section headlines and clean interface or commercial cards. Hero action fill uses white at 0.95 alpha. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Live green | `#5dcd37` | `--color-signal` | accent | Tiny moving or glowing live-data dots, not large decorative fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Included green | `#2c8a4a` | `--color-included` | text | Included and synced tags. |
| pricing pages | Included wash | `#e6f7e0` | `--color-included-wash` | surface | Visible light-green tag wash made with #5dcd37 at 0.15 alpha on near white. |

## Typography

- **Gestura Headline** — Marketing headlines, commercial numerals and footer links. High-contrast editorial serif, thin regular strokes and tightly joined headline rhythm. If unavailable, use **DM Serif Display**. Use regular weight and tune line breaks to preserve the broad editorial silhouette. Font stack: "Gestura Headline", "DM Serif Display", Georgia, 'Times New Roman', serif.
- **Inter** — Body copy, navigation, buttons and large proof numerals. Compact neutral grotesk with small negative tracking in prose. Font stack: "Inter", -apple-system, system-ui, 'Segoe UI', sans-serif.
- **SF Mono** — Small technical labels and commercial eyebrows. Matter-of-fact monospace; capitals are widely tracked while product labels stay compact. If unavailable, use **Roboto Mono**. Font stack: "SF Mono", "Roboto Mono", 'Haffer Mono', ui-monospace, 'Liberation Mono', monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat | Inter | 400 | 72px | 0.8 | -0.03em | fixed | Large proof numbers, with a tightly attached suffix. |
| display | Gestura Headline | 400 | 54.9px | 1 | -0.02em | fixed | Default cinematic opening headline. |
| heading-lg | Gestura Headline | 400 | 54px | 0.98 | -0.035em | fixed | Main heading introducing a paper feature chapter. |
| statement | Gestura Headline | 400 | 48px | 1 | -0.02em | fixed | Centered atmospheric proof statement and cultural section lead. |
| editorial-heading | Gestura Headline | 400 | 40px | 0.98 | -0.03em | fixed | Editorial strip section title. |
| price | Gestura Headline | 400 | 39px | 1 | -0.03em | fixed | Embedded commercial card starting price. |
| heading | Gestura Headline | 400 | 36px | 1 | -0.02em | fixed | Black-background capability chapters. |
| panel-heading | Gestura Headline | 400 | 27px | 1.08 | -0.025em | fixed | Ivory feature and technical panel headings. |
| footer-link | Gestura Headline | 400 | 24px | 1.2 | -0.01em | fixed | All footer destination links. |
| article-heading | Gestura Headline | 400 | 20px | 1.2 | -0.01em | fixed | Editorial card titles. |
| hero-support | Inter | 400 | 16.2px | 1.4 | -0.01em | fixed | Opening support line, white at 0.62 alpha. |
| body-lead | Inter | 400 | 16px | 1.6 | -0.009em | fixed | Paper chapter support; keep to about 620px measure. |
| body | Inter | 400 | 15px | 1.6 | -0.0096em | fixed | Default light feature-panel prose. |
| dark-body | Inter | 400 | 14.4px | 1.4 | -0.01em | fixed | Compact dark chapter paragraphs; white with 0.6 opacity. |
| button | Inter | 500 | 14px | 1.4 | -0.01em | fixed | Hero primary and outline actions. |
| content-button | Inter | 500 | 14px | 1 | -0.01em | fixed | Compact dark pills inside light panels. |
| navigation | Inter | 500 | 14px | 16px | -0.01em | fixed | Top-level navigation. |
| technical-label | SF Mono | 500 | 13px | 1.4 | 0.01em | fixed | Names above paired technical demonstrations. |
| eyebrow | SF Mono | 400 | 11px | 1.4 | 0.16em, uppercase | fixed | Commercial or technical category markings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | Gestura Headline | 400 | 62px | 1 | -0.03em | size clamp(34px, 6.5vw, 62px) | Paper opening with an explicit price in the headline. |
| integration landing pages | integration-display | Gestura Headline | 400 | 60px | 0.98 | -0.035em | fixed | Photo-backed integration promise. |
| integration landing pages | integration-heading | Gestura Headline | 400 | 44px | 1.02 | -0.03em | fixed | Problem and solution statement headings. |
| integration setup guides | step-number | Gestura Headline | 400 | 32px | 1.4 | -0.025em | fixed | Muted two-digit step numbers. |
| pricing pages | pricing-lead | Inter | 400 | 18px | 1.5 | normal | size clamp(15px, 2.2vw, 18px) | Plain-language pricing explanation. |
| pricing pages | included-tag | Inter | 600 | 11px | 1.4 | 0.04em, uppercase | fixed | Included and synced badges. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Serif display type stays regular rather than becoming bold at larger sizes. Tight tracking is strongest on the 54px chapter heading and integration display.
- Use 27px headings for the quiet light panels and 36px headings for the more immersive black chapters; these are separate compositions rather than one averaged size.
- Keep dense application typography subordinate to the marketing hierarchy. A large device mockup does not justify turning its internal labels into page headings.

## Layout

**Density:** Airy framing around compact content: broad chapter pauses contrast with dense, useful interface demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Dark heading-to-body gap and small icon gaps. |
| 12px | Hero action gap and editorial card text rhythm. |
| 16px | Hero stage inset and gap between stacked feature panels. |
| 18px | Technical panel and commercial copy stack. |
| 22px | Paper chapter heading stack and feature panel content rhythm. |
| 24px | Hero headline/support/action stack. |
| 32px | Stat rule inset and footer group separation. |
| 40px | Dark capability copy-column padding. |
| 44px | Light feature-panel top and side padding. |
| 48px | Editorial heading-to-grid gap and commercial panel vertical padding. |
| 72px | Main paper introduction-to-panels gap; integration section vertical padding. |
| 80px | Paper chapter side padding and editorial strip vertical padding. |
| 112px | Paper product chapter opening padding. |
| 120px | Black chapter-to-chapter breathing space. |

### Containers and grids

- **outer frame**: max width 1920px · side padding 43.2px. Main editorial frame and navigation. At 1440px the inner guide width is 1354px; faint vertical rails align the long page.
- **paper chapter**: max width 1440px · side padding 80px. Feature chapter resulting in 1280px-wide panels at desktop.
- **dark capability split**: 2 columns · gap 0px. A copy column about 640px wide beside media about 706px wide, with 40px copy padding. Media has slightly more visual weight.
- **editorial cards**: 3 columns · gap 16px. Three 419px-wide unboxed articles on warm paper.
- **proof row**: 4 columns · gap 64px. Four equal stat columns with individual content measures capped at 256px.
- **integration content** (only for integration landing pages): max width 1300px · side padding 80px. 1140px content width inside a centered section.
- **pricing workspace** (only for pricing pages): max width 1180px · 2 columns · gap 24px · side padding 32px. A 756px detail card beside a 400px sticky summary.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | feature panels | 4px |
|  | cinematic window | 8px |
|  | signal cards | 12px |
| pricing pages | pricing cards | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | interface frame | `0px 8px 30px -12px rgba(0, 0, 0, 0.12)` | Large screenshot frames on ivory. |
|  | signal card | `0px 1px 3px 0px rgba(44, 44, 43, 0.05)` | Small floating output cards in a diagram. |
| pricing pages | estimate | `0px 16px 40px -12px rgba(0, 0, 0, 0.2)` | Black pricing summary. |

### Surfaces

#### Canvas · level 0

**Use:** Underlying page canvas.

**CSS:** `background: #fefefe`

#### Cinema · level 0

**Use:** Opening and immersive capability chapters.

**CSS:** `background: #080808; color: #ffffff`

**Observed:** Large contiguous black chapters rather than many independently rounded cards.

**Transfer:** Let photographic scenes emerge from the black ground.

#### Paper band · level 0

**Use:** Product explanation and editorial interruption.

**CSS:** `background: #f0efed; color: #2c2c2b`

#### Ivory feature panel · level 1

**Use:** Large explanatory demonstrations.

**CSS:** `background: #fbfaf8; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 4px; padding: 44px 44px 40px`

**Observed:** Wide low-relief panel with heading, muted support, demonstration and actions.

**Transfer:** Prefer one coherent demonstration to a decorative bento cluster.

#### Interface frame · level 2

**Use:** Large application images within panels.

**CSS:** `border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 4px; box-shadow: 0px 8px 30px -12px rgba(0, 0, 0, 0.12); overflow: hidden`

#### Footer paper · level 0

**Use:** Shared institutional ending.

**CSS:** `background: #f9f8f6; color: #2c2c2b`

#### Estimate surface · level 1

**Only for:** pricing pages

**Use:** The compact conversion summary beside an exhaustive detail list.

**CSS:** `background: #080808; color: #f0efed; border-radius: 16px; box-shadow: 0px 16px 40px -12px rgba(0, 0, 0, 0.2); overflow: hidden`

## Components

### Navigation

**Use:** Fixed brand and destination strip.

**CSS:** `height: 60px; background: #080808; padding: 0px 43.2px; display: flex; align-items: center; justify-content: space-between; border-bottom: 1px solid rgba(192, 192, 192, 0.1)`

**Text style:** `navigation` — Inter 500 · 14px/16px · tracking -0.01em

**Observed:** Small wordmark left, compact links right, plus symbols on expandable destinations, then sign-in and conversion pills. Text links are muted to 0.7 opacity. Light chapters and utility pages use ivory with dark text and a fine neutral bottom rule.

**States:** Declared: hover text links opacity 0.5 and transform scale(0.98); focus-visible expandable links use a blue 0.125rem outline with 0.125rem offset.

### Primary button

**Use:** Default opening action on dark imagery.

**CSS:** `background: rgba(255, 255, 255, 0.95); color: #080808; border: 1px solid #ffffff; border-radius: 9999px; padding: 11px 20px; height: 44px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Inter 500 · 14px/1.4 · tracking -0.01em

**Observed:** Placed first in a two-action row. Later black chapters use a 40px ivory pill with 8px 16px padding.

**Transfer:** Use a short concrete conversion verb phrase.

### Outline button

**Use:** Secondary action beside the opening primary.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid #444444; border-radius: 9999px; padding: 11px 20px; height: 44px`

**Text style:** `button` — Inter 500 · 14px/1.4 · tracking -0.01em

**Observed:** A visually quiet companion with no saturated fill.

### Content button

**Use:** Conversions in paper panels and compact commercial cards.

**CSS:** `background: #2c2c2b; color: #f0efed; border-radius: 9999px; padding: 13px 24px; height: 40px; display: flex; align-items: center; gap: 8px`

**Text style:** `content-button` — Inter 500 · 14px/1 · tracking -0.01em

**Observed:** Usually placed at the lower left of its panel. Commercial versions can include a right arrow.

**States:** Declared: hover background black; focus-visible not specified. Background transition 0.12s.

### Feature panel

**Use:** One substantial product explanation.

**CSS:** `background: #fbfaf8; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 4px; padding: 44px 44px 40px; display: flex; flex-direction: column; gap: 22px`

**Text style:** `panel-heading` — Gestura Headline 400 · 27px/1.08 · tracking -0.025em

**Observed:** Heading and a support paragraph precede a broad flow diagram or a large Interface frame. Stacked panels have 16px gaps.

### Signal card

**Use:** Small output callouts beside a product flow.

**CSS:** `background: #ffffff; border: 1px solid rgba(44, 44, 43, 0.12); border-radius: 12px; box-shadow: 0px 1px 3px 0px rgba(44, 44, 43, 0.05); padding: 16px 18px; display: flex; flex-direction: column; gap: 8px`

**Observed:** Compact outcome sentence on the left, small uppercase positive or risk badge on the right. Individual cards stack or cycle beside a single convergence node.

**Transfer:** Show a specific output of the new product rather than generic benefit names.

### Proof row

**Use:** Quantified proof inside the atmospheric scene.

**CSS:** `display: grid; grid-template-columns: repeat(4, 1fr); column-gap: 64px; row-gap: 48px; border-top: 1px solid rgba(255, 255, 255, 0.2); padding-top: 32px; margin-top: 64px`

**Text style:** `stat` — Inter 400 · 72px/0.8 · tracking -0.03em

**Observed:** Unboxed white numerals with tight suffixes and centered 18px supporting labels. The whole row shares one rule; columns do not become separate cards.

### Editorial card

**Use:** News or supporting proof in a paper band.

**CSS:** `display: flex; flex-direction: column; background: transparent`

**Text style:** `article-heading` — Gestura Headline 400 · 20px/1.2 · tracking -0.01em

**Observed:** Unrounded 419px by 271px image, then 16px inset above the text stack; headline, short gray paragraph and an arrow text link separated by 12px. No painted card shell.

### Footer navigation

**Use:** Shared final destination system.

**CSS:** `background: #f9f8f6; padding: 43.2px; display: grid; grid-template-columns: 1fr 1fr`

**Text style:** `footer-link` — Gestura Headline 400 · 24px/1.2 · tracking -0.01em

**Observed:** Left half holds a small wordmark at the top and small company details at the bottom. Right half is a two-by-two group of destination lists with 32px gaps, small sans labels and serif links separated by 4px. Overall footer height is 484px at desktop.

### Included tag

**Only for:** pricing pages

**Use:** Reassurance at the right of included-feature rows.

**CSS:** `background: rgba(93, 205, 55, 0.15); color: #2c8a4a; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 9999px; padding: 5px 11px; backdrop-filter: blur(20px); display: flex; align-items: center; gap: 6px`

**Text style:** `included-tag` — Inter 600 · 11px/1.4 · tracking 0.04em · uppercase

**Observed:** Repeated light-green status pill; a compact check is part of many labels. Never used as the primary conversion button.

### Estimate summary

**Only for:** pricing pages

**Use:** Sticky price and conversion summary.

**CSS:** `background: #080808; color: #f0efed; border-radius: 16px; max-width: 400px; overflow: hidden; box-shadow: 0px 16px 40px -12px rgba(0, 0, 0, 0.2)`

**Observed:** Small uppercase estimate label, large regular serif price and muted monthly unit; annual billing note, two itemized rows, a ruled annual total and full-width light pill action. Interior top area uses 28px padding; the surrounding aside is sticky.

**Transfer:** Expose the one pricing variable and show the annual total rather than adding multiple plan cards.

## Imagery and graphics

### Cinematic device scene

**Use:** Opening signature and selected capability chapters.

**Observed:** A thin black desktop monitor on a warm wood desk, keyboard and peripheral at the bottom, against out-of-focus dark greenery and gray sky. The bright interface is legible within the monitor while the left side of the room becomes dark negative space for text. Later scenes mix phones, floating white interface notes, pale blue-gray light and soft shadows.

**Transfer:** Use a believable device carrying the new product in a low-lit working environment. Minimum version: a carefully framed monitor with a simple original interface over a dark, softly defocused room photograph.

**Build:** Compose a full-cover desaturated room photograph behind a monitor occupying roughly the right half. Keep the desk near the lower fifth. Add a left-to-right overlay linear-gradient(90deg, rgba(8,8,8,0.62) 0%, rgba(8,8,8,0.42) 34%, rgba(8,8,8,0) 56%) and a top fade from rgba(8,8,8,0.5) to transparent over 96px. Clip the entire stage to 8px, with 16px black margins.

### Converging data diagram

**Use:** Signature light-panel explanation of inputs becoming useful outputs.

**Observed:** Six narrow white source rows on the left converge through faint curved lines into one compact destination node; green dots punctuate the paths. Two white output notices sit to the right. Icons are small gray outlines, not large illustrations.

**Transfer:** Use the product's real inputs and resulting outputs. Preserve the sparse network and one clearly identified destination.

**Build:** Use an SVG viewBox about 738 by 326 for the input network. Stack six approximately 262px by 48px white rectangles with thin black-at-0.1 borders and 4px corners. Draw six 1px cubic Bézier paths from their right centers to one shared node, using charcoal at 0.16 alpha. Place 4–6px green circles along selected paths and give only the live node a subtle green halo. Position 12px-radius Signal cards to the right on the same ivory ground.

### Atmospheric scale scene

**Use:** Signature proof interlude behind the Proof row.

**Observed:** A large curved Earth seen at night tilts diagonally through the composition, with a dim blue atmospheric rim and tiny warm city lights. Black fades at top and bottom merge the picture into the surrounding page; the image covers the full 900px section.

**Transfer:** Show the product's scale through a relevant landscape, infrastructure or abstract network, with a large dark field for centered text. Minimum version: a dark curved horizon with a restrained blue edge and sparse warm points, never a bright sci-fi planet.

**Build:** Place a very large circular horizon partly off-canvas so its edge runs from lower left to upper center. Use a dark blue-gray image or filled ellipse, a narrow low-opacity cyan rim and sparse warm pinpoints. Layer a 0.5-alpha black veil, then a vertical gradient from #080808 through rgba(8,8,8,0.6) at 25% and 74% back to #080808. Put type and the shared stat rule above all imagery.

### Product interface proof

**Use:** Full-width demonstrations within light panels and device displays.

**Observed:** Pale, dense business interfaces with fine row rules, compact tables, light sidebars and occasional small semantic color. Large standalone interfaces have 4px corners and a restrained shadow.

**Transfer:** Show enough real detail to communicate utility. Keep colorful application accents inside the interface rather than extending them into the marketing shell.

### City-backed integration scene

**Only for:** integration landing pages

**Use:** Integration-specific opening and dark signal feature.

**Observed:** A desaturated aerial city scene at dusk fills the stage. Heavy left black shading supports a three-line serif promise while a large bright company record floats on the right, without a device enclosure.

**Transfer:** Use a relevant real-world setting and one convincing integration output card. Keep the photograph contextual, not a stock-photo banner.

**Build:** Use a full-cover dusk photograph positioned near 50% 58%. Overlay linear-gradient(90deg, rgba(8,8,8,0.93) 0%, rgba(8,8,8,0.8) 36%, rgba(8,8,8,0.42) 66%, rgba(8,8,8,0.12) 100%) and a bottom fade. Place an approximately 556px-wide white 4px-radius output panel on the right.

### Human-world gallery

**Only for:** community or event storytelling

**Use:** A human, photographic ending before the paper footer.

**Observed:** Natural-color photos of conversations, gatherings and venues in a tight three-column masonry-like arrangement, 8px gutters, rounded images and translucent pale caption pills at upper corners. The surrounding black makes warm interior light feel rich.

**Transfer:** Use authentic images of people using or discussing the new product, with candid framing rather than uniformly posed headshots.

### Icons

**Observed:** Utility icons are small 15px outlines, generally 1.5px with rounded ends, gray on pale circular backings. Navigation uses small plus marks and directional arrows; checks are thin and green. Icons remain subordinate to text.

**Transfer:** Choose a consistent thin-outline set at 15–16px for diagrams and rows, preserving small monochrome marks rather than oversized multicolor feature icons.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product opening

**Observed:** A fixed Navigation strip occupies the first 60px. Beneath it an 840px black stage contains a 1408px by 808px inset scene with 8px corners. Back to front: softly blurred room and wood desk, physical monitor and bright interface on the right, left-biased dark overlay, then a left-aligned serif promise, muted support and Primary button plus Outline button. The headline is 54.9px/1 with -0.02em tracking, spans roughly half the stage and wraps into three lines; the monitor fills nearly the other half. The copy sits around the central height, slightly above the desk; support and actions follow at 24px intervals. Within the first 900px the whole promise, both actions, monitor, keyboard and desk edge are visible. The next paper chapter starts below the fold.

**Transfer:** Recreate the same visual weight with a believable monitor or device bearing an original, simplified product interface. Protect dark negative space for the text rather than shrinking the product to a thumbnail. Integration pages instead open with the City-backed integration scene and a single light action; pricing pages open directly on paper with a price-led headline and calculator.

**Avoid:** Do not replace the scene with a centered text stack, a bright abstract gradient or several floating generic cards. Do not enlarge the headline until it competes with the monitor.

**Text style:** `display` — Gestura Headline 400 · 54.9px/1 · tracking -0.02em

### Paper product chapter

**Observed:** Paper band with 112px top, 80px side and 96px bottom padding. A heading-lg title and 620px-wide muted support line lead into compact coverage chips. After 72px, stacked Feature panels use 16px gaps; one contains the Converging data diagram, another a broad Interface frame.

**Transfer:** Move from broad product promise to concrete mechanics; chips can express compatible tools, supported categories or coverage rather than countries.

**Text style:** `heading-lg` — Gestura Headline 400 · 54px/0.98 · tracking -0.035em

### Paired technical access

**Observed:** A single 4px panel is split into equal columns by a 1px black-at-0.1 rule. Each half has 44px side/top and 40px bottom padding, a compact mono label, 27px serif heading, a distinct technical demonstration and a Content button. One demonstration is a dark code block with 8px corners; the other is a charcoal prompt and white response bubble.

**Transfer:** Use two adjacent ways of accessing the same capability, keeping the demonstrations materially different while the framing stays shared.

**Text style:** `panel-heading` — Gestura Headline 400 · 27px/1.08 · tracking -0.025em

### Embedded commercial offer

**Observed:** White 4px-radius panel with 48px 52px padding. Left column: bronze mono eyebrow, 34px serif title, muted prose, 39px serif price, billing note and Content button. Right column: included-benefit rows divided by faint hairlines and a subdued partner-logo strip. Integration variants use a 16px-radius 1140px panel and a 56px price.

**Transfer:** Offer a concise buying route beside concrete inclusions; make the offer comprehensible without a large pricing matrix.

**Text style:** `price` — Gestura Headline 400 · 39px/1 · tracking -0.03em

### Cinematic quantified proof

**Observed:** Atmospheric scale scene fills a 900px black chapter. A centered statement within about 992px sits above support and paired actions. Proof row follows after 64px with a single rule, four unboxed metrics and short centered labels.

**Transfer:** Use verified scale, throughput, coverage or reliability metrics appropriate to the new product. Keep the same contrast between serif statement and regular grotesk numerals.

**Text style:** `statement` — Gestura Headline 400 · 48px/1 · tracking -0.02em

### Dark capability chapter

**Observed:** Two-column ruled rows align within the outer frame. Left copy has 40px padding, a small two-digit number, a 36px serif title, body at an 8px gap and a light pill anchored near the bottom. Right-side media fills about 706px by 528px, showing a device or purposeful interface scene. Rows are separated by very faint rules; black pauses between groups reach 120px.

**Transfer:** Tell one outcome per row and make the adjacent scene prove it. Group or reorder chapters to fit the product's story.

**Text style:** `heading` — Gestura Headline 400 · 36px/1 · tracking -0.02em

### Editorial interruption

**Observed:** Paper band with 80px vertical and 76px side padding. Small uppercase category above a 40px serif title; an all-items arrow aligns at the far right. After 48px, three Editorial cards sit in a 16px-gutter grid.

**Transfer:** Use recent proof, case stories or substantive articles as a warm-paper interruption within darker product storytelling.

**Text style:** `editorial-heading` — Gestura Headline 400 · 40px/0.98 · tracking -0.03em

### Human proof and paper ending

**Observed:** The long narrative ends with a black community area: 48px serif lead on the left, ruled event rows with 144px thumbnails on the right, then a close-packed three-column photographic gallery. After a black pause, Footer navigation switches to ivory for 484px. Integration pages instead finish with a compact coverage-chip section and small sales action; pricing finishes with its dataset list. All share the same generous, serif-link footer rather than a giant final slogan.

**Transfer:** Let each page's last proof section suit its purpose, but keep the paper footer and its distinctive empty-left/destination-right hierarchy. The human gallery belongs only where real community content exists.

**Text style:** `footer-link` — Gestura Headline 400 · 24px/1.2 · tracking -0.01em

### Setup strip

**Only for:** integration landing pages

**Observed:** Four 264px-wide steps across a 1140px content area, with 28px gaps. Each has a top rule, 22px top inset, a pale 32px serif number, 17px medium sans title and compact explanatory paragraph. A section label and compact action precede the row.

**Transfer:** Reduce setup friction through short procedural steps rather than feature claims.

**Text style:** `step-number` — Gestura Headline 400 · 32px/1.4 · tracking -0.025em

### Pricing workspace

**Only for:** pricing pages

**Observed:** Warm paper opening with a 62px price-led serif headline, 18px support and 44px gap before a 1180px workspace. A 756px white 16px-radius detail card contains a volume slider, included-feature accordion and dataset rows; a 400px Estimate summary sits beside it at a 24px gap. Long rows use quiet bottom rules and right-aligned Included tags. The detail list ends before an 80px paper pause and the shared footer; there is no additional oversized closing pitch.

**Transfer:** Explain one meaningful pricing variable, with exhaustive inclusions in the light column and one concise conversion summary.

**Text style:** `pricing-display` — Gestura Headline 400 · 62px/1 · tracking -0.03em

## Page flow

**Storyline:** Promise → tangible product proof → capability explanation → quantified reassurance → useful supporting proof → buying route → institutional ending.

### A broad product narrative that earns attention through tangible scenes and alternating materials

1. **Promise** — Dark photographic device stage, serif outcome statement and paired conversion routes.
2. **Product demonstration** — Paper chapter with coverage chips, a converging input diagram and large interface demonstration.
3. **Buying route** — Paired technical access panels and a concise commercial inclusion card.
4. **Quantified proof** — Dark atmospheric scene with a shared-rule four-stat row.
5. **Capability chapters** — Ruled black copy-and-media rows, interrupted by a paper editorial strip.
6. **Human proof** — Community listings and a candid photo gallery.
7. **Institutional ending** — Warm-paper footer with generous negative space and serif links.

**Transfer:** Retain the alternation of tangible proof, paper explanation and black cinematic chapters without treating the section sequence as fixed.

### A targeted integration story that explains the improvement over the existing workflow

1. **Promise** — City photograph, integration label, serif promise and a bright output record.
2. **Problem framing** — Stale or incomplete record beside a plain-spoken problem statement.
3. **Solution** — Two-column capability list, then large in-context interface views.
4. **Capability proof** — Dark photo-backed signal panel with compact outcome cards.
5. **Objection handling** — Four numbered setup steps.
6. **Buying route** — White commercial panel with price and inclusions.
7. **Coverage reassurance** — Ruled coverage section and compact chips with a small sales action.
8. **Institutional ending** — Shared paper footer.

**Transfer:** Keep the problem-to-solution argument practical and demonstrate the output inside the target workflow.

### A transparent purchase calculator rather than a multi-plan comparison page

1. **Commercial promise** — Price appears directly in the large serif headline on warm paper.
2. **Pricing choice** — Volume slider beside the sticky black estimate summary.
3. **Inclusion reassurance** — Long expandable included-feature list with small green pills.
4. **Data detail** — A second quiet row list documents what gets synced.
5. **Institutional ending** — Detail card ends, then a paper pause and shared footer.

**Transfer:** Use the true pricing lever; preserve one summary and an explicit total instead of inventing tier competition.

## Writing

Confident, operational and commercially literate, with a human editorial cadence. Promises are grounded in specific inputs, outputs and places the work happens, not abstract AI superlatives.

**Do not copy:** Do not reuse Aira's names, wordmark, interface records, customer identities, prices, market counts, database statistics, rankings, listing claims, event names or source photographs. Replace all claims with truthful facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your; name the product in explanatory sentences. Use direct imperative actions and occasional reader-like quoted requests.
- **Rhythm:** Headlines are often full outcome statements of roughly 8–15 words, with short declarative follow-ups. Support uses one to three practical sentences; a terse sentence can punctuate a longer explanation. Buttons are two to four words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Active verb + valuable outcome + scope or workflow. | 9–15 words | “Surface opportunity and risk for every company in your CRM”<br>“Enrich every HubSpot company with verified financial data” |
| Capability title | A reader-like request or a precise job to be done. | 6–14 words | “Find more companies like our best customers”<br>“Deep research on any company, on demand.” |
| Supporting line | State the input and resulting work, then anchor it in the reader's existing environment. | One to three sentences | “Connect verified financial data, contacts, and signals to every company in your HubSpot or Salesforce.” |
| Problem statement | Plain observation with a sting, rather than fear-driven rhetoric. | 8–12 words | “Your CRM only knows what you typed into it.” |
| Pricing reassurance | Explicit inclusions, then short exclusions of common pricing friction. | Two or three short sentences | “Everything is included in the base price. No add-ons, no upsells.” |
| Primary action | Concrete next step, not a slogan. | 2–4 words | “Book a demo”<br>“Talk to sales”<br>“Get started” |

**Words and phrasing to use:** verified; current; every; inside; connected; on demand; automatically; included; one click; your existing workflow

**Avoid:** revolutionary; magical; game-changing; unlock limitless potential; AI-powered everything; hype-heavy exclamations

**Rules:**

- Explain what becomes possible and where the result arrives.
- Use numbers as proof only when they are defensible; accompany each with an intelligible label.
- Name the practical mechanism in support copy instead of stuffing the headline with technical vocabulary.
- Treat commercial transparency as part of the voice: say what is included and what the reader chooses.

## Do's and Don'ts

### Do

- Keep the opening serif regular at 54.9px with a 1 line height and -0.02em tracking.
- Maintain the 16px cinematic inset and 8px image corners against a black surround.
- Use 4px corners and 44px side padding for broad ivory feature panels.
- Reserve 72px regular Inter for the large proof numerals, not for ordinary benefit cards.
- Keep dark capability text compact at 14.4px/1.4 with 40px column padding.
- Use 24px serif links in the footer, with small sans group labels.
- Let semantic greens occupy tiny dots, checks and badges while the shell stays neutral.
- Keep paper editorial cards unboxed with 16px gutters and rectangular image tops.

### Don't

- Do not replace the serif hierarchy with bold geometric sans headlines.
- Do not round every panel to 16px; that softness belongs mainly to pricing and selected application surfaces.
- Do not turn the four proof metrics into individual white cards or color-filled tiles.
- Do not use bright green as a page background or primary CTA fill.
- Do not give news cards heavy shadows, outer borders or pill-shaped image corners.
- Do not stretch navigation into a tall, spacious header; the desktop strip is 60px.
- Do not center all body copy; feature chapters and technical explanations are predominantly left aligned.
- Do not add a monumental closing slogan to every page; the broad shared ending is the warm-paper destination footer.

## Motion and responsive

### Motion

**Observed:**

- Declared navigation transitions are transform 0.2s and opacity 0.2s, with hover scale(0.98) and opacity 0.5 on text links.
- Content-button background changes use 0.12s; editorial text-link color and gap changes use 0.15s.
- Live indicator animations declare 2.4s ease-in-out infinite pulses. Diagram signals and product scenes also use animated composition.

**Transfer:**

- Use subtle activity in the convergence diagram and small live signals; keep the diagrams intelligible when motion is stopped.
- Let interaction feel compact and tactile through the declared small scale change rather than adding springy large translations.

**Unknown:**

- Full scene timelines, scroll choreography and all animation keyframe values are not established.

### Responsive

**Observed:**

- The root size declares calc(0.812695rem + 0.208117vw), so rem-based dimensions vary with the viewport.
- Pricing headline uses clamp(34px, 6.5vw, 62px), and its lead uses clamp(15px, 2.2vw, 18px).
- Declared width breakpoints include 479px, 640px, 767px, 991px, 1024px, 1440px and 1920px, with additional component-specific thresholds.

**Transfer:**

- Recommended adaptation: stack cinematic copy above the device rather than squeezing both into two narrow columns; preserve the dark stage and tangible object.
- Recommended adaptation: reduce the proof row to fewer columns while retaining the shared hairline treatment; stack pricing detail and summary without obscuring the total.

**Unknown:**

- Exact narrow-screen navigation, stacking order, scene framing and sticky-summary behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
