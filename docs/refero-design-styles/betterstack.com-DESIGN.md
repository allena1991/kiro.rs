# Better Stack — interfaces emerging from midnight

## Overview

A near-black, blue-toned technical style with silver grotesk headlines and small violet conversion highlights. Product interfaces emerge from darkness through soft fades, shallow perspective and localized light rather than bright decorative illustrations. It suits developer platforms and complex software, balancing spacious marketing compositions with dense, practical feature and price information.

### Essentials

- Silver headlines, not neon slogans: the default opening uses Helvetica Now Display at 53px/1.1, weight 500, normal tracking, with a white-to-slate text gradient; chapter headings use 40px bold.
- A working product emerges beside the promise: a roughly 509px headline block faces an oversized, perspective-tilted interface with darkened edges; a 52px email field and 50px violet button sit beneath the copy.
- Violet is a small illuminated control, not the canvas: #0b0c14 and #0f101a occupy almost all large areas; #5b63d3 to #7c87f7 gradients concentrate on primary actions and small data accents.
- Buttons have two distinct silhouettes: primary actions use 10px corners and an inset white highlight; exploration actions are 39px-tall outlined pills with 13px text and a small right chevron.
- Capability chapters are cinematic shelves: 478px-high, 16px-radius cards alternate roughly 350px and 725px widths, separated by 20px, with interfaces above bottom-aligned 16px captions and side fades into the canvas.
- Proof is built into the atmosphere: use a muted, edge-faded logo ribbon and a data-backed closing scene with a faint quadrant or equivalent proof graphic. When brand or product media is unavailable, construct a truthful interface vignette and a small labeled evidence diagram with the same subdued lighting.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Periwinkle action | `#7c87f7` | `--color-violet` | action, link, accent | Upper end of primary button gradients and small marketing links; never a full-page fill. |
| Deep action violet | `#5b63d3` | `--color-violet-deep` | action, accent | Lower end of the illuminated primary-action gradient. |
| Soft periwinkle | `#98a4f7` | `--color-link-light` | link | Mentions inside customer quote cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue gray text | `#939db8` | `--color-body` | text | Main paragraph and secondary information color; lower contrast than headlines. |
| Pale slate | `#c9d3ee` | `--color-label` | text, link | Navigation and outlined exploration action labels. |
| Dim slate | `#646e87` | `--color-muted` | text | Card descriptions, helper copy, media captions and legal text. |
| Midnight canvas | `#0b0c14` | `--color-canvas` | background | Default page and footer background; also the opaque end of media fades. |
| Raised midnight | `#0f101a` | `--color-card` | surface | Capability card fill, only slightly lighter than the page. |
| Smoked glass | `#151621` | `--color-glass` | surface | Visible result of #171824 at 80% over the canvas; testimonial panels and framed product media. |
| Input wash | `#151722` | `--color-input-wash` | surface | Visible #727da1 at 10% over midnight; translucent email fields. |
| Pill slate | `#171926` | `--color-pill` | surface | Exploration links and round carousel controls. |
| Card hairline | `#191b24` | `--color-card-edge` | border | Visible #939db8 at 10% over the canvas; faint card boundaries. |
| Control hairline | `#262935` | `--color-control-edge` | border | Visible #939db8 at 20% over the canvas; outlines of exploration controls. |
| Silver white | `#ffffff` | `--color-white` | text | Headings, button labels and the light end of headline gradients. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Table rule | `#212432` | `--color-pricing-rule` | border | Pricing table perimeters and dashed row separators. |

## Typography

- **Helvetica Now Display** — Headlines, chapter titles and compact capability-card titles. Clean contemporary grotesk with compact, rounded forms; opening headlines are medium rather than heavy. OpenType features: "ss01", "ss03", "ss04", "ss19". If unavailable, use **Inter**. Use 500 and 700; preserve widths and deliberate line breaks. Font stack: "Helvetica Now Display", "Inter", Arial, sans-serif.
- **Helvetica Now Text** — Paragraphs, controls, metadata and proof numerals. Highly readable grotesk, differentiated mainly by weight and blue-gray contrast. OpenType features: "ss01", "ss03", "ss04", "ss19". If unavailable, use **Inter**. Font stack: "Helvetica Now Text", "Inter", Arial, sans-serif.
- **Inter** (only for pricing numerals) — Large entry-price numerals. Crisp semibold numerals with a compact line box. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Helvetica Now Display | 500 | 53px | 1.1 | normal, features "salt", "ss02" | Default split opening headline, normally two lines. |
| heading | Helvetica Now Display | 700 | 40px | 1.08 | -0.01em | Gradient section headings, centered over detailed feature compositions or left-aligned beside proof. |
| shelf-title | Helvetica Now Display | 700 | 40px | 24px | normal | Short, single-line capability chapter labels; keep the shallow line box only on isolated one-line headings. |
| closing-title | Helvetica Now Display | 700 | 36px | 1.17 | normal | Left-aligned closing proof and conversion headline. |
| proof-title | Helvetica Now Text | 700 | 36px | 1.08 | -0.01em | Centered introduction to customer feedback. |
| stat | Helvetica Now Text | 700 | 28px | 1.17 | normal | Benefit multipliers and savings percentages. |
| comparison-value | Helvetica Now Text | 700 | 28px | 1.45 | normal | Three aligned quantity readouts inside a proof panel. |
| hero-support | Helvetica Now Text | 400 | 20px | 1.2 | normal | Two-line supporting statement in the split opening. |
| body | Helvetica Now Text | 400 | 16px | 1.5 | normal | Paragraphs and descriptions; use body color normally and muted color inside media-heavy shelf cards. |
| card-title | Helvetica Now Display | 500 | 16px | 1.5 | normal | Short labels at the bottom of capability shelf cards. |
| action | Helvetica Now Text | 500 | 16px | 1.5 | normal | Primary button labels, compact product feature subheads and FAQ questions. |
| footer-link | Helvetica Now Text | 400 | 14px | 1.55 | normal | Footer links and descriptive footer statement. |
| caption | Helvetica Now Text | 400 | 13px | 1.6 | normal | Exploration pills, migration helper copy and small price metadata. |
| navigation | Helvetica Now Text | 400 | 13px | 1 | normal | Top navigation links and compact pricing exploration labels. |
| signup-label | Helvetica Now Text | 500 | 13px | 1 | normal | Compact illuminated signup action in navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| dedicated product landing pages | product-display | Helvetica Now Display | 500 | 66px | 1.1 | normal, features "salt", "ss02" | Centered two-line opening above a large framed demonstration. |
| pricing pages | pricing-display | Helvetica Now Display | 700 | 56px | 1.15 | -0.01em | Centered pricing opening title. |
| pricing pages | faq-title | Helvetica Now Display | 700 | 44px | 1 | -0.01em | Centered heading above the bordered question list. |
| pricing pages | price | Inter | 600 | 36px | 1 | normal | Large entry price, with billing interval in smaller text alongside. |
| pricing pages | pricing-category | Helvetica Now Display | 400 | 32px | 1.15 | -0.01em | Major category separators above groups of price tables. |
| dedicated product landing pages | feature-title | Helvetica Now Display | 700 | 28px | 1.17 | normal | Larger left-column feature explanations paired with smaller right-column cards. |
| pricing pages | pricing-support | Helvetica Now Text | 400 | 20px | 1.5 | normal | Centered guarantee and FAQ introduction. |
| pricing pages | pricing-subhead | Helvetica Now Display | 600 | 18px | 24px | normal | Individual feature or charge category title. |
| pricing pages | pricing-feature | Helvetica Now Text | 400 | 14px | 1.3 | normal | Dense three-column check lists beneath pricing tables. |

**Notes:**

- Opening headlines use a medium cut with normal tracking; bold gradient section headings tighten to -0.01em. Do not make every heading the same heavy weight.
- Use sentence case, not tracked uppercase eyebrows. The primary hierarchy comes from scale, contrast and composition.
- Headline gradients shade white toward blue-gray without turning the letters violet. The display recipes use alternate glyph features distinct from the ordinary text settings.

## Layout

**Density:** Airy between chapters, compact inside product and pricing panels; broad darkness gives small captions and controls room to register.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small internal gaps and heading-support separation in the opening. |
| 12px | Form control gap, card-title-to-description gap and table vertical padding. |
| 16px | Secondary grid gaps and proof-panel outer padding. |
| 20px | Capability shelf gaps, testimonial padding and standard outer gutters. |
| 24px | Small card padding and heading-to-exploration spacing. |
| 32px | Bottom and side padding of capability shelf captions. |
| 40px | Heading-to-media spacing, proof readout padding and post-copy actions. |
| 64px | Feature group separation and pricing subcategory top spacing. |
| 128px | Major chapter separation and feedback-section top padding. |
| 192px | Large chapter trailing space and the default proof-close top padding. |

### Containers and grids

- **Navigation rail**: max width 1110px · side padding 20px. Centered fixed header with a fine bottom rule; logo and navigation on the left, account actions at right.
- **Split opening**: max width 1100px · 2 columns · side padding 20px. Text occupies one half; the product scene exceeds the right column and dissolves toward the viewport edge. Headline maximum is 509px.
- **Chapter rail**: max width 1126px · gap 20px · side padding 20px. Heading and controls align to a centered rail while the card shelf extends beyond it.
- **Feedback field**: max width 1320px · 4 columns · gap 16px · side padding 20px. Masonry-like quote columns with narrow, varied-height cards around 308px wide.
- **Closing rail**: max width 1000px · side padding 20px. Left-aligned conversion copy with a 500px headline maximum and supporting proof artwork on the right.
- **Product feature grid** (only for dedicated product landing pages): max width 960px · 2 columns · gap 16px · side padding 20px. A dominant tall left demonstration or unboxed visual beside two stacked right cards, followed when needed by a full-width card.
- **Pricing workspace** (only for pricing pages): max width 1156px · 2 columns · gap 80px · side padding 20px. A 230px side index beside an 806px main reading column. Tables and check lists share the main column width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Primary action | 10px |
|  | Capability and quote cards | 16px |
|  | Email field | 12px |
|  | Exploration control | 9999px (pill) |
|  | Proof outer frame | 26px |
|  | Compact signup | 8px |
| pricing pages | Pricing table | 12px |
| pricing pages | FAQ perimeter | 19px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Button inner light | `inset 0px 1px 3px 0px rgba(255,255,255,0.25)` | Primary conversion actions and compact signup. |
| Headline separation | `0px 2px 2px rgba(0,0,0,0.9)` | Drop-shadow filter on the opening gradient headline, not a floating panel shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous background including the visible footer.

**CSS:** `background: #0b0c14; color: #939db8`

**Observed:** Almost-black with a cool cast; sections are separated by space rather than alternating bright bands.

**Transfer:** Keep the continuous dark field across an entire landing page.

#### Capability card · level 1

**Use:** Large product shelves and detailed feature panels.

**CSS:** `background: #0f101a; border: 1px solid rgba(147,157,184,0.1); border-radius: 16px; overflow: hidden`

**Observed:** Very faint edges, no conspicuous cast shadow; interface imagery merges into the card fill. Product-page feature cards use a similarly subdued blue-gray edge.

**Transfer:** Give each card one focused product behavior and a bottom text zone.

#### Quote glass · level 1

**Use:** Customer feedback cards.

**CSS:** `background: rgba(23,24,36,0.8); border: 1px solid rgba(114,125,161,0.2); border-radius: 16px; backdrop-filter: blur(24px); padding: 20px`

**Observed:** Translucent smoked panels of unequal heights, not a perfectly aligned tile matrix.

**Transfer:** Use authentic customer feedback of varying lengths while retaining narrow column widths.

#### Silver headline

**Use:** Large opening and chapter headlines.

**CSS:** `background-image: linear-gradient(162deg, #ffffff 25.49%, #939db8 110.77%); background-clip: text; color: rgba(0,0,0,0); filter: drop-shadow(0px 2px 2px rgba(0,0,0,0.9))`

**Observed:** The opening has a gentle diagonal metal-like fade; section headings use a related layered white-to-slate gradient.

**Transfer:** Keep the gradient low contrast within the letters, not a rainbow effect.

#### Localized atmosphere

**Use:** Opening and closing product scenes.

**CSS:** `background: radial-gradient(ellipse at 65% 45%, rgba(91,99,211,0.1), rgba(11,12,20,0) 65%)`

**Observed:** Faint blue-violet illumination stays behind media, with black foreground fades retaining text contrast.

**Transfer:** Match the soft glow; exact stops are not essential. Keep most of the canvas unlit.

#### Pricing panel · level 1

**Only for:** pricing pages

**Use:** Entry plan and enterprise conversion panel.

**CSS:** `background: linear-gradient(rgba(23,24,36,1), #0b0c14); border: 1px solid #212432; border-radius: 12px`

**Observed:** A restrained dark top glow, sometimes backed by a faint abstract line graphic; ordinary tables remain almost flush with the page.

**Transfer:** Make plans readable as information rather than colorful promotional tiles.

## Components

### Fixed navigation

**Use:** Persistent site orientation and compact conversion.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 52px; z-index: 40; background: rgba(11,12,20,0.8); display: flex; justify-content: center`

**Text style:** `navigation` — Helvetica Now Text 400 · 13px/1

**Observed:** The Navigation rail contains a small wordmark, horizontal links with tiny dropdown chevrons, then sign-in and Compact signup. The bottom rule belongs to the rail, not the full viewport.

**Transfer:** Use concise top-level categories; preserve the small header relative to the main scene.

### Primary button

**Use:** Default marketing conversion beside Email field.

**CSS:** `background: linear-gradient(353deg, #5b63d3 17.51%, #7c87f7 183.08%); color: #ffffff; border: 1px solid rgba(255,255,255,0.14); border-radius: 10px; box-shadow: inset 0px 1px 3px 0px rgba(255,255,255,0.25); height: 50px; padding: 0px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Helvetica Now Text 500 · 16px/1.5

**Observed:** Short unadorned label; the opening version aligns centrally with a slightly taller field. Closing and dedicated-product variants are 48px high. Pricing uses a darker 44px-high, 8px-radius action instead of the default violet treatment.

**Transfer:** Keep one clear conversion in the form row.

### Email field

**Use:** Single-field signup in opening and closing scenes.

**CSS:** `background: rgba(114,125,161,0.1); border: 1px solid rgba(114,125,161,0.2); border-radius: 12px; backdrop-filter: blur(40px); height: 52px; width: 324px; padding: 0px 20px; color: #ffffff`

**Observed:** Placeholder is subdued, and the field sits before Primary button with a 12px gap. Closing forms use the same visual treatment at 48px height.

**Transfer:** Use a single useful input rather than a full registration form.

### Explore pill

**Use:** Low-emphasis chapter navigation and product discovery.

**CSS:** `background: #171926; border: 1px solid rgba(147,157,184,0.2); border-radius: 9999px; padding: 8px 12px 8px 16px; color: #c9d3ee`

**Text style:** `caption` — Helvetica Now Text 400 · 13px/1.6

**Observed:** A right-pointing 16px chevron follows the label. Shelf controls place two circular arrows and a faint divider before this action; the unavailable arrow is dimmed. Compact pricing-exploration variants use 13px/1 labels, 37px height and 12px horizontal padding.

**States:** Declared: hover background-color #222330; focus-visible unknown.

**Transfer:** Use verbs such as Explore, Watch or Learn with a specific object.

### Compact signup

**Use:** Small conversion anchor in the fixed header.

**CSS:** `background: linear-gradient(353deg, #5b63d3 17.51%, #7c87f7 183.08%); border: 1px solid rgba(255,255,255,0.11); border-radius: 8px; box-shadow: inset 0px 1px 3px 0px rgba(255,255,255,0.25); height: 27px; padding: 0px 8px; color: #ffffff; display: flex; align-items: center`

**Text style:** `signup-label` — Helvetica Now Text 500 · 13px/1

**Observed:** An intentionally miniature counterpart to the main action, placed after a plain sign-in link.

### Capability shelf card

**Use:** Clickable image-led explanation inside a horizontal chapter.

**CSS:** `background: #0f101a; border: 1px solid rgba(147,157,184,0.1); border-radius: 16px; height: 478px; position: relative; overflow: hidden; flex-shrink: 0`

**Text style:** `card-title` — Helvetica Now Display 500 · 16px/1.5

**Observed:** Wide and narrow cards alternate rather than dividing into equal thirds. Media fills the card behind a bottom-aligned caption stack inset 32px; a muted body paragraph follows its title by 12px.

**Transfer:** Show one workflow moment, not a whole collage of unrelated features.

### Customer quote

**Use:** Trust-building feedback wall.

**CSS:** `background: rgba(23,24,36,0.8); border: 1px solid rgba(114,125,161,0.2); border-radius: 16px; backdrop-filter: blur(24px); padding: 20px`

**Text style:** `body` — Helvetica Now Text 400 · 16px/1.5

**Observed:** Quote comes first, then a circular portrait, bold author name and muted handle, with a small violet social mark. Mentions within the quote are soft periwinkle.

**Transfer:** Let authentic quote length determine the card height.

### Footer link

**Use:** Dense but low-emphasis site directory.

**CSS:** `color: #939db8; padding: 0px 4px; margin-top: 12px; display: inline-block`

**Text style:** `footer-link` — Helvetica Now Text 400 · 14px/1.55

**Observed:** Four desktop groups with brighter medium-weight group labels; the editorial/resource group is wider. A separate lower rail holds wordmark and proposition at left, contact and social icons at right, then legal links and status.

### Price row

**Only for:** pricing pages

**Use:** Repeated per-unit charge or included allowance.

**CSS:** `display: flex; justify-content: space-between; gap: 12px; padding: 12px 16px; border-bottom: 1px dashed #212432`

**Text style:** `caption` — Helvetica Now Text 400 · 13px/1.6

**Observed:** Label at left, price or included quantity right-aligned; secondary units can sit beneath the price. Rows live inside a 12px-radius outlined table, and the last row drops its separator.

**Transfer:** Keep each unit and billing period adjacent to its amount.

### FAQ group

**Only for:** pricing pages

**Use:** Late-page objection handling.

**CSS:** `border: 1px solid rgba(114,125,161,0.2); border-radius: 19px; margin-top: 44px`

**Text style:** `action` — Helvetica Now Text 500 · 16px/1.5

**Observed:** A single outlined container holds eight question rows, with 24px side insets and fine dividers. First answer is expanded, others show right chevrons; answers use body text with violet inline links.

**Transfer:** Group real buying objections rather than repeating benefits as questions.

## Imagery and graphics

### Emerging product interfaces

**Use:** Main opening object and capability media.

**Observed:** Dark application views with sidebars, code, graphs, messages and floating contextual controls. The opening panel is tilted in shallow perspective and pushed beyond the right half; lower cards show tightly framed behavior fragments. Foreground and edge fades sink details into midnight, leaving the product legible at the focal point.

**Transfer:** Stage real interface fragments for the new product. If no finished UI exists, create a credible diagrammatic interface with rows, a small chart and one meaningful highlighted state; retain the dark backing and soft fade rather than using stock photography.

**Build:** Place a dark UI panel in a perspective container, rotate it gently around the vertical axis, and layer transparent-to-#0b0c14 gradients over the bottom and outer edges. Put a broad rgba(91,99,211,0.1) blurred ellipse behind it. Use #939db8 labels and a few #7c87f7 data marks; keep the foreground text independent and fully sharp.

### Faded trust ribbon

**Use:** Social proof near an opening or before a close.

**Observed:** A horizontally traveling, monochrome slate customer-logo row crosses a broad strip. Ends fade and blur into the canvas; the middle stays clearer. Some dedicated-product placements add a centered 16px introduction.

**Transfer:** Use permissioned customer, integration or certification marks in one restrained tone. An equivalent factual proof ribbon can use short neutral labels.

**Build:** Duplicate a horizontal SVG or flex strip for seamless translation; surround it with left and right 140–220px overlays fading #0b0c14 to transparent. Add a masked blur(2px) layer at the outer edges and keep marks subdued.

### Proof constellation close

**Use:** Signature proof-backed conversion scene.

**Observed:** Left-hand headline, form and secondary demo link face a faint right-hand quadrant chart. Small dark rounded logo tiles float across thin axes, with one violet tile drawing the eye; an extremely faint violet haze sits behind it. The diagram is quieter than the copy, not a large bright infographic.

**Transfer:** Recreate the data-backed atmosphere using genuine proof appropriate to the new product: a labeled outcome map, workflow diagram or benchmark field. Preserve the tiny illuminated focal tile and wide darkness even when a market-position chart is inappropriate.

**Build:** Use a roughly 520px-wide SVG field with a fine rgba(147,157,184,0.1) rounded boundary and two central axes. Scatter small #171926 rounded tiles carrying neutral symbols, with one #5b63d3-to-#7c87f7 tile. Label axes in #646e87 and apply a broad canvas fade over outer edges.

### Flare and woven data horizon

**Only for:** dedicated product landing pages

**Use:** Atmosphere behind a centered headline and large video demonstration.

**Observed:** A diffuse diagonal blue-violet flare shines down from above the title. Beneath it a large framed application video rises from a dark lower field, with a fine violet dotted wave or woven mesh curving upward at the sides.

**Transfer:** Use a neutral product demo inside the frame and build the atmosphere separately; keep the mesh peripheral so it never obscures the interface.

**Build:** Behind a 946px-wide rounded frame, place a long blurred ellipse in rgba(124,135,247,0.12), rotated diagonally. Draw a low-opacity SVG dot lattice on a curved wave at the lower sides; color it #98a4f7 and mask it into #0b0c14 toward the center. Keep the frame at 21px radius and its inner view at 11px.

### Icons

**Observed:** Small restrained SVG symbols, usually 16px, with 11–12px dropdown marks and chevrons; muted slate in navigation and proof labels, pale slate beside exploration actions. Pricing feature checks are violet. Social glyphs remain small rather than becoming decorative illustrations.

**Transfer:** Choose one consistent simple icon set. Use compact chevrons, circular arrow controls and technical outline symbols; do not interpret black SVG path defaults as a requirement for black icons on dark backgrounds.

## Section recipes

How recurring sections are built.

### First screen: Split product stage

**Observed:** A Fixed navigation rail caps the continuous Canvas. The left half of a 1100px composition carries a two-line 53px medium Silver headline, about 509px maximum width, followed by a 20px support statement. The form follows after 28px with Email field and Primary button, then a two-line 13px helper statement and an underlined consultation link. Back to front: faint localized atmosphere, oversized perspective product interface at right, dark edge masks, independent sharp copy and controls. The 875px-wide media exceeds its column and includes a tiny centered media label, dot indicators and round previous/next arrows below it. Within the first 900px, the complete headline, support, form, helper, main product object and faded trust ribbon are visible; the quantitative proof and capability chapters begin below.

**Transfer:** Default new marketing pages to this split composition. Make the right-hand object a meaningful product behavior, using the Emerging product interfaces construction if no polished artwork exists. Dedicated product pages instead center a 66px headline over the form and begin a large video panel within the first screen; pricing pages open with a centered 56px title, guarantee line and billing switch before the dense workspace.

**Avoid:** Do not replace the product stage with a centered giant slogan, a full-bleed bright image or a generic abstract orb. Do not let the right-hand media fade cover the form or turn readable UI into an empty dark rectangle.

**Text style:** `display` — Helvetica Now Display 500 · 53px/1.1

### Quantified comparison

**Observed:** A roughly 356px text block faces a 641px framed comparison with an 80px column gap. The left uses heading, body and Explore pill, then two compact 28px benefit figures. The right has a 26px outer frame with 16px padding, three aligned 28px quantity readouts above two cost rows, a dashed separator, and a small violet comparison marker. Fine-print assumptions sit below.

**Transfer:** Use defensible, like-for-like quantities and units; carry over the compact dashboard construction rather than making unqualified giant percentage claims.

**Text style:** `heading` — Helvetica Now Display 700 · 40px/1.08 · tracking -0.01em

### Capability shelf chapter

**Observed:** A single-line shelf-title sits left on the Chapter rail; circular controls and Explore pill sit right. About 40px below, Capability shelf cards form a horizontally overflowing snap shelf, alternating narrow and wide widths. Canvas-colored side masks soften off-rail cards. A small right-aligned replacement or compatibility caption can sit beneath. Chapters have broad 128–192px breathing space.

**Transfer:** Group benefits into independently browsable chapters, with a small mix of different media widths; choose the number of chapters to suit the new story.

**Text style:** `shelf-title` — Helvetica Now Display 700 · 40px/24px

### Proof-backed conversion

**Observed:** The Closing rail uses closing-title, a short supporting paragraph 12px below, an email form 40px below on the default composition, then a plain demo alternative. Proof constellation close occupies the right half. The section uses 192px top and 144px bottom padding; the dedicated-product close tightens the top to 130px and action gap to 24px.

**Transfer:** Close on an outcome and a credible proof image, not just another feature list. Preserve a secondary route for buyers who need a conversation.

**Text style:** `closing-title` — Helvetica Now Display 700 · 36px/1.17

### Customer feedback field

**Observed:** A centered proof-title introduces supporting copy, then Faded trust ribbon and a four-column Customer quote field. Cards vary in height and use Quote glass; portraits and handles close each card. The entire field is broader than the primary reading rail.

**Transfer:** Let authentic short and long endorsements create the uneven silhouette; do not force a fixed quote length.

**Text style:** `proof-title` — Helvetica Now Text 700 · 36px/1.08 · tracking -0.01em

### Directory ending

**Observed:** The visible ending stays on Canvas with a faint top rule, not a bright band. Four link groups occupy a centered 1110px rail with 56px top padding; the final resource column is wider. Below a rule, a compact wordmark and two-line value statement face contact details and small social icons. Another thin rule divides legal links and a tiny status indicator from copyright at the far right.

**Transfer:** Finish with practical navigation and a compact brand reminder. Keep the footer smaller in type than the content and visually continuous with the preceding section.

**Text style:** `footer-link` — Helvetica Now Text 400 · 14px/1.55

### Centered heading and asymmetric detail

**Only for:** dedicated product landing pages

**Observed:** A centered 40px Silver headline with a 12px gap to a restrained 16px paragraph leads a 960px two-column composition. A large unboxed product scene and 28px explanation occupy one column while two 16px-title Capability cards stack in the other. Another variant makes the left card tall and closes with a full-width panel.

**Transfer:** Use a broad promise over each capability cluster, then show one deep example and two supporting details. Keep paragraph widths restrained rather than filling the entire grid.

**Text style:** `heading` — Helvetica Now Display 700 · 40px/1.08 · tracking -0.01em

### Pricing workspace and reassurance

**Only for:** pricing pages

**Observed:** A centered title and 20px guarantee line precede a monthly/annual switch with a tiny violet savings note. The Pricing workspace pairs a slim icon index with an 806px column: entry plan, compact price summary, category headings, outlined Price rows and three-column check lists. Bundle choices use a two-by-two layout of compact 12px-radius cards with a small savings pill and separated allowance columns. After categories comes a short enterprise panel with demo action, then a centered FAQ title, FAQ group and contact invitation.

**Transfer:** Use this denser variant for detailed unit-based pricing, not as the default landing-page layout. Preserve the navigable category structure and visible billing units.

**Text style:** `pricing-display` — Helvetica Now Display 700 · 56px/1.15 · tracking -0.01em

## Page flow

**Storyline:** Promise and working-product scene → trust and quantified value → browsable capability proof → reassurance and conversion → practical directory.

### Broad platform or multi-capability marketing landing

1. **Promise** — Split product stage with immediate single-field conversion.
2. **Social proof** — Muted moving trust ribbon.
3. **Quantified value** — Compact side-by-side benefit and cost comparison.
4. **Capability chapters** — Repeated image-led horizontal shelves with exploration links.
5. **Closing call** — Proof-backed conversion with a faint data diagram.
6. **Customer proof** — Centered introduction and uneven quote-card field.
7. **Directory** — Four-column footer, contact rail and legal strip.

**Transfer:** Choose only the chapters needed for the new product while preserving the visual alternation between atmosphere, focused interface demonstrations and compact proof.

### Detailed pricing and purchasing explanation

1. **Reassurance** — Centered pricing title, guarantee and billing cadence switch.
2. **Entry offer** — Outlined free plan followed by concise starting-price summary.
3. **Pricing detail** — Sidebar index, categorized charge tables, feature checks and bundle cards.
4. **Sales path** — Small enterprise callout with a dark demo action.
5. **Objection handling** — Large FAQ panel with one expanded answer and contact line.
6. **Directory** — Shared dark footer and legal ending.

**Transfer:** Make charges scannable by unit and category; do not convert a usage-based offer into three generic equal-height plans.

### Focused product landing with deeper demonstrations

1. **Promise** — Centered large headline, form and framed video over a woven data horizon.
2. **Value proof** — Trust ribbon and quantified comparison.
3. **Capability depth** — Centered heading pairs above asymmetric interface grids.
4. **Reassurance** — Repeated trust ribbon before the final decision.
5. **Closing call** — Outcome-led form beside a faint proof diagram and demo alternative.
6. **Directory** — Shared dark footer and compact legal rail.

**Transfer:** Make each capability chapter answer a distinct user problem through a specific interface scene, not a repeated feature icon.

## Writing

Confident, technically specific and commercially direct, with occasional human reassurance. Benefits are stated plainly and immediately supported by mechanisms, units or workflow detail.

**Do not copy:** Do not reuse Better Stack names, logos, customer marks, endorsements, competitive comparisons, savings figures, market-position claims, guarantees or technical capabilities as claims for another product. Source examples illustrate sentence structure only.

- **Addressing the reader:** Address the reader as you and your; use we sparingly for care, process and reassurance. Give the reader control rather than presenting automation as magic.
- **Rhythm:** Short headline fragments pair with one or two practical explanatory sentences. Three clipped promises can share a support line; technical paragraphs become longer only when needed to explain the mechanism.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the category and a concrete change in how it works. | 5–8 words | “The AI SRE observability stack”<br>“Tracing reimagined with eBPF & OpenTelemetry” |
| Support line | A quantified value proposition followed by two short confidence statements. | 10–14 words | “30x cheaper than Datadog. Predictable pricing. Exceptional customer support.” |
| Capability headline | Outcome plus mechanism, with the obstacle removed. | 6–12 words | “Instrument clusters without code changes thanks to eBPF” |
| Card title | A compact capability stated in plain terms. | 2–8 words | “Collaboration built-in”<br>“Don’t get billed for useless logs” |
| Primary action | Verb plus low-friction entry or named destination. | 2–5 words | “Start for free”<br>“Explore pricing”<br>“Book a demo” |
| Reassurance | Address risk or control directly without vague superlatives. | 4–15 words | “You’re always in charge.”<br>“Try [Brand] today risk‑free with our 60‑day money-back guarantee.” |

**Words and phrasing to use:** built-in; out-of-box; in seconds; you’re in charge; no code changes; predictable; explore; monitor; query; automatically

**Avoid:** revolutionary magic; unlock infinite possibilities; world-changing synergy; effortless everything; exclamation-heavy hype

**Rules:**

- Lead with the practical outcome, then name the concrete mechanism.
- Pair numerical claims with clear units, scope and assumptions.
- Keep button labels literal; reserve personality for occasional reassuring phrases.
- Use technical nouns when they help the buyer choose, not as decorative jargon.

## Do's and Don'ts

### Do

- Keep nearly all large surfaces within the #0b0c14 to #0f101a range.
- Use 500 weight for the opening headline and 700 for major chapter headings.
- Give image-led shelf cards 16px corners and 32px bottom caption insets.
- Pair a 324px email field with the main action using a 12px gap.
- Keep silver text gradients within the white-to-#939db8 range.
- Use narrow 13px outlined exploration pills for secondary actions.
- Retain faded proof media and the data-backed conversion scene even for a shorter page.
- Use 128px and 192px chapter spaces to contrast with compact 12–24px interior spacing.

### Don't

- Do not make all actions pills: the violet primary control has 10px corners.
- Do not wash an entire section in saturated periwinkle; keep it on controls, links and small proof accents.
- Do not brighten every card edge to white; use low-alpha blue-gray rules.
- Do not substitute a large monospace headline for the medium grotesk opening.
- Do not turn every image card into an equal-width three-column grid; the 350px/725px alternation is characteristic.
- Do not add large offset card shadows; separation comes from faint borders and localized light.
- Do not apply the shelf title’s 24px line box to multiline 40px headings.
- Do not render the footer as a solid lighter-slate band; its visible surface remains near-black.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use 150ms cubic-bezier(0.4, 0, 0.2, 1) across color, background, borders, opacity, shadows and transforms.
- Declared reveal transitions use opacity and transform over 1s ease.
- The repeated trust strips declare translateLeft at 50s linear, infinite.
- Capability shelves use horizontal scrolling and snap alignment; arrow and dot controls accompany the opening scene.

**Transfer:**

- Keep drifting motion concentrated in the faded proof ribbon and controlled product scenes.
- Use the short declared transition on exploration controls; let media reveals settle to the same dark composition.

**Unknown:**

- Exact carousel autoplay timing, reveal distances and choreography are not established.

### Responsive

**Observed:**

- Narrow-layout classes center opening text and stack its columns; the email form switches between stacked and horizontal arrangements.
- Smaller declared type variants include 36px for the centered product opening, 28px for chapter titles and 24px for closing and feedback headings.
- Feedback columns progress from one to two, three and four; full navigation links are progressively hidden.

**Transfer:**

- On narrow screens, center and stack the promise, form and product scene without shrinking text into the media.
- Maintain the shelf’s peek of adjacent content and keep captions readable; convert asymmetric feature chapters to a single reading sequence.
- Collapse the pricing index and table workspace without separating amounts from their billing units.

**Unknown:**

- Exact breakpoint widths and the fully rendered mobile navigation are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
