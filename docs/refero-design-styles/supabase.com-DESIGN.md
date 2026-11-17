# Supabase — open toolkit optimism

## Overview

A bright, developer-minded style that makes substantial infrastructure feel approachable and immediately usable. Near-white space, charcoal and grey type, and restrained forest-green accents surround fine-lined interface illustrations and real product demonstrations. Rounded geometric sans headings sit above compact grotesk body text, with monospace reserved for technical labels and prices. The overall feel is spacious between chapters but deliberately dense inside useful cards and comparison tables.

### Essentials

- A promise is split into two plainspoken lines, not a giant slogan: Manrope 46px/1 at weight 500, black first and forest green second, with normal tracking.
- The opening is a working toolkit rather than a cinematic poster: a 1088px content area pairs headline left with 16px/24px support right, then reveals a fine-edged capability mosaic within the first 900px.
- Actions resemble small polished controls: the default pair is 38px high with 8px 16px padding, 9.3px corners, a green primary and a white secondary, with delicate inset edges rather than pill silhouettes.
- Most of the page stays near-white: #fdfdfd canvas, #ffffff panels, #696969 supporting text and faint 1px edges. Green colors actions and one promise line; concentrated multicolor belongs to a bounded proof panel rather than whole-page atmosphere.
- Technical imagery is nearly drawn into the paper: grey wireframes, ghosted rows, fine grids and softly fading diagrams sit inside 16px-corner panels. Include a product demonstration; when no interface exists, draw a small truthful workflow with the same fine grey lines.
- Proof has a graphic identity: include a concentrated colored story panel and a green dot-matrix metric device. The former uses an 8px-corner frame and white text; the latter forms a genuine number or short word from rounded cells fading into the surrounding paper.
- The close returns to a compact two-tone promise: 34px/1.2 Manrope at weight 600, grey lead-in and black payoff, paired actions and 128px vertical breathing room. The footer continues the light canvas with a slim trust strip, newsletter and link columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest action green | `#0e7e4e` | `--color-green` | text, action, link | Primary actions, promise emphasis, security links and the dark cells of graphic metrics. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Story orange | `#ff8f1b` | `--color-story-orange` | background | Lower end of the story-panel gradient. |
| Story red | `#fa1f41` | `--color-story-red` | background | Middle of the story-panel gradient. |
| Story magenta | `#fd49a8` | `--color-story-pink` | background | Upper end of the concentrated story-panel gradient. |
| Story deep teal | `#002533` | `--color-story-teal` | surface | Alternate collapsed story rail; not a general canvas. |
| Story midnight | `#0c0f24` | `--color-story-navy` | surface | Collapsed story rail; not a dark page theme. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#030303` | `--color-ink` | text | Primary headings, emphasized body phrases and active control outlines. |
| Secondary charcoal | `#464646` | `--color-body-strong` | text | Supporting text that needs more presence than the muted grey. |
| Supporting grey | `#696969` | `--color-muted` | text, border | Descriptions, muted headline halves, logos and recommended-plan outline. |
| Control outline | `#d8d8d8` | `--color-control-edge` | border | Visible near-black at about 14.6% over the canvas, used for fields and avatar edges. |
| Paper hairline | `#e9e9e9` | `--color-edge` | border | Visible edge produced by near-black at about 8.1% over the canvas; card outlines and section rules. |
| Soft grey wash | `#f6f6f6` | `--color-wash` | surface | Visible near-black at 2.7% over the canvas; logo tiles and inset quotations. |
| Field wash | `#f9f9f9` | `--color-field` | surface | Visible black at 1.5% over near-white; input backgrounds. |
| Green-tinted white | `#fafcfb` | `--color-on-green` | text | Text on filled primary controls. |
| Near-white canvas | `#fdfdfd` | `--color-canvas` | background | Continuous page and footer background. |
| White panel | `#ffffff` | `--color-panel` | surface, text | Card interiors, secondary buttons and reversed story copy. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| enterprise lead-generation pages | Technical label green | `#097c4f` | `--color-enterprise-green` | text | Uppercase solution-opening label. |

## Typography

- **Manrope** — Display lines, section headings, capability titles and footer group headings. Rounded geometric sans with open counters; medium displays and semibold section leads. Font stack: "Manrope", system-ui, "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Inter** — Default marketing body, navigation, controls and descriptions. Compact, highly legible grotesk; body weight 450 and control weight 500. Font stack: "Inter", system-ui, "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Source Code Pro** — Technical labels, prices and code demonstrations. Straightforward monospaced texture that makes plan labels and numbers feel like tooling. Font stack: "Source Code Pro", "Office Code Pro", Menlo, monospace.
- **ui-sans-serif** (only for enterprise and corporate supporting content) — Supporting copy and some quotations on solution and corporate pages. System sans; keep it subordinate to Manrope headings. Font stack: "ui-sans-serif", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Manrope | 500 | 46px | 1 | normal | Default opening promise, split into two lines. Also the centered corporate opening. |
| heading | Manrope | 600 | 34px | 1.111 | normal | Default chapter heading, often with black and grey phrases across two lines. |
| closing-heading | Manrope | 600 | 34px | 1.2 | normal | Centered final promise; also standalone solution and corporate section leads. |
| story-quote | Manrope | 450 | 22px | 1.375 | normal | White quotation within the featured colored story. |
| card-heading | Manrope | 600 | 16px | 1.5 | normal | Capability and customer-card titles. |
| body | Inter | 450 | 16px | 1.5 | normal | Opening support and regular explanatory paragraphs. |
| footer-heading | Manrope | 600 | 15px | 1.5 | normal | Footer navigation group labels. |
| community-copy | Inter | 450 | 15px | 1.5 | normal | Short community testimonials. |
| small | Inter | 450 | 14px | 1.43 | normal | Card descriptions, footer links and understated text links. |
| action | Inter | 500 | 14px | 1.43 | normal | Default marketing action pair. |
| compact-action | Inter | 500 | 12px | 1.333 | normal | Header conversion controls and newsletter submit. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Source Code Pro | 450 | 46px | 1 | normal | Primary numeric plan price; recurring billing unit stays much smaller alongside it. |
| pricing and demo-request pages | pricing-opening | Manrope | 500 | 34px | 1.2 | normal | Centered pricing introduction or final demo-request title. |
| enterprise lead-generation pages | solution-opening | Manrope | 500 | 34px | 1.111 | -0.0044em | Two-line opening beside the lead form. |
| pricing pages | pricing-heading | Manrope | 600 | 28px | 1.2 | normal | Centered explanatory chapter headings. |
| corporate proof pages | corporate-stat | Manrope | 500 | 28px | 1.2 | normal | Four-column metric strip. |
| pricing pages | plan-name | Source Code Pro | 450 | 22px | 1.333 | normal, uppercase | Plan headings above description and conversion action. |
| enterprise lead-generation pages | solution-label | Source Code Pro | 450 | 16px | 1.5 | normal, uppercase | Green category label above the opening. |
| enterprise capability chapters | technical-eyebrow | Source Code Pro | 450 | 12px | 1.333 | 0.05em, uppercase | Small labels 8px above the section heading. |

**Notes:**

- Normal tracking is the default even for the 46px display; the character comes from Manrope and line breaks, not compressed spacing.
- Do not promote card titles to oversized headlines: the 16px title and 14px description make room for technical artwork.
- Chapter headings use 34px with a tighter line height than the 34px closing promise. Keep these roles distinct.
- Grey and black phrases belong to one semantic heading. Preserve visual reading order rather than placing the grey phrase first by default.

## Layout

**Density:** Airy between chapters and compact within controls, cards and comparison content.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Action-pair gap, tight stacks and technical label-to-heading gap. |
| 12px | Capability mosaic gutters. |
| 16px | Heading-to-description gap and enterprise card gutters. |
| 24px | Community-card and lead-form inner padding. |
| 32px | Opening copy-to-action gap and story-card inset. |
| 64px | Opening bottom space and chapter heading-to-proof separation. |
| 96px | Typical chapter vertical padding and desktop container side padding. |
| 128px | Closing-call vertical padding and pricing explanatory chapter top padding. |
| 160px | Default opening top space beneath navigation. |

### Containers and grids

- **main-container**: max width 1280px · side padding 96px. Centered desktop wrapper; at 1440px the useful inner content is 1088px wide, shared by navigation, chapters and footer.
- **opening-pair**: 2 columns · gap 16px. Two equal 536px columns: promise on the left, supporting paragraph aligned toward its lower edge on the right.
- **capability-mosaic**: 12 columns · gap 12px. Underlying grid for a double-width lead card with two narrow companions, then four equal cards; narrow cards are 263px and the wide one 538px.
- **story-accordion**: gap 8px. A 752px expanded proof panel beside four 76px rails in a 1088px-wide stage; all 480px high.
- **pricing-plans** (only for pricing pages): max width 1120px · 4 columns · gap 0px. Joined 280px plan columns with the recommended column raised above and below the others.
- **enterprise-proof** (only for enterprise pages): 3 columns · gap 16px. Three 352px customer-story cards, followed by four smaller outcome summaries with 32px gutters.
- **corporate-directory** (only for corporate pages): 4 columns · gap 20px. Simple 257px text entries or compact press cards; avoid elaborate portrait layouts.

## Corner radius

| Element | Radius |
| --- | --- |
| marketing-buttons | 9.3px |
| compact-controls | 8px |
| feature-panel | 16px |
| panel-interior | 15px |
| community-and-demo-frame | 21.3px |
| small-example-card | 10.7px |
| tabs-and-badges | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| control-edge | `0px 1px 3px 0px rgba(0,0,0,0.04), 0px 1px 0px 0px rgba(0,0,0,0.027) inset, 0px 0px 0px 1px rgba(0,0,0,0.067) inset` | Subtle button construction; use instead of a heavy floating shadow. |
| demo-frame | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | Large browser-like product demonstration, not every card. |

### Surfaces

#### Canvas · level 0

**Use:** Default page and footer material.

**CSS:** `background: #fdfdfd; color: #030303`

#### Gradient edge panel · level 1

**Use:** Capability, press and selected explanatory panels.

**CSS:** `background: linear-gradient(rgba(3,3,3,0.0812725), rgba(3,3,3,0.0406362)), #ffffff; padding: 1px; border-radius: 16px`

**Observed:** A separate white interior with 15px corners leaves a delicate edge that weakens toward the bottom. The outline is more apparent than any elevation.

**Transfer:** Nest a white interior within the gradient frame rather than applying a dark uniform border.

#### Demo stage · level 2

**Use:** Large product demonstration.

**CSS:** `background: #fdfdfd; border: 1px solid rgba(3,3,3,0.0812725); border-radius: 21.3px; padding: 8px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Observed:** A shallow browser header sits above a wide interface, clipped by the section edge at the bottom.

**Transfer:** Use an actual workflow view with a few meaningful controls rather than an entire tiny dashboard.

#### Concentrated story color · level 1

**Use:** Featured proof, the major saturated exception to the neutral page.

**CSS:** `background: linear-gradient(#fd49a8 0%, #fa1f41 30%, #ff8f1b 100%); border-radius: 8px; box-shadow: 0px 0px 0px 1px rgba(255,255,255,0.12) inset`

**Observed:** Vertical magenta through red to orange, contained within the active story rectangle; neighboring rails use very dark or saturated partner colors.

**Transfer:** Keep the color concentrated in a single proof stage, with white foreground content and plenty of space around it.

#### Soft inset · level 1

**Use:** Logo cells and short inset quotes.

**CSS:** `background: rgba(3,3,3,0.027)`

**Observed:** Barely darker than the surrounding paper; no elevated shadow.

**Transfer:** Use for secondary proof rather than a high-contrast band.

## Components

### Sticky navigation

**Use:** Persistent lightweight site navigation.

**CSS:** `height: 65px; position: sticky; top: 0px; z-index: 40; background: rgba(253,253,253,0.9); border-bottom: 1px solid rgba(3,3,3,0.0812725); backdrop-filter: blur(4px)`

**Observed:** Brand at left, compact text menus with small downward chevrons in the middle, then repository count, sign-in and compact green conversion control. Navigation follows the main container.

**Transfer:** Use a small number of short product, audience and resource labels; keep conversion controls visually smaller than the opening pair.

### Primary button

**Use:** Default main conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 38px; padding: 8px 16px; border-radius: 9.3px; background-color: #0e7e4e; background-image: linear-gradient(rgba(255,255,255,0.016), rgba(0,0,0,0.01)); color: #fafcfb; box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.04), 0px 1px 0px 0px rgba(0,0,0,0.027) inset, 0px 0px 0px 1px rgba(0,0,0,0.067) inset`

**Text style:** `action` — Inter 500 · 14px/1.43

**Observed:** Sits first in the action pair. Text-only, centered, with a lightly polished face; the pricing variant is 42px high and fills the plan column.

### Secondary button

**Use:** Adjacent assisted conversion or supporting action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 38px; padding: 8px 16px; border-radius: 9.3px; background: #ffffff; color: #030303; box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.04), 0px 1px 0px 0px rgba(0,0,0,0.027) inset, 0px 0px 0px 1px rgba(0,0,0,0.067) inset`

**Text style:** `action` — Inter 500 · 14px/1.43

**Observed:** White face with a delicate edge; paired with green at an 8px gap, never competing as another saturated action.

### Compact button

**Use:** Header conversion and newsletter submit.

**CSS:** `height: 26px; padding: 4px 10px; border-radius: 8px; background-color: #0e7e4e; background-image: linear-gradient(rgba(255,255,255,0.016), rgba(0,0,0,0.01)); color: #fafcfb`

**Text style:** `compact-action` — Inter 500 · 12px/1.333

**Observed:** Small rectangular control below the email field; the same scale keeps the sticky header unobtrusive.

### Capability card

**Use:** Core product capabilities in the opening mosaic.

**CSS:** `background: #ffffff; border-radius: 15px; padding: 24px 16px; overflow: hidden`

**Text style:** `card-heading` — Manrope 600 · 16px/1.5

**Observed:** Sits inside Gradient edge panel. Icon and title lead, a compact description follows, and low-contrast technical art fills the lower or right-hand region. The double-width lead card can carry a short checklist at the bottom.

**Transfer:** Use one practical capability per card and make each illustration specific to its action.

### Community card

**Use:** Short user testimony in an edge-to-edge wall.

**CSS:** `width: 288px; padding: 24px; background: #ffffff; border: 1px solid rgba(3,3,3,0.0812725); border-radius: 21.3px; filter: drop-shadow(0px 1px 1px rgba(0,0,0,0.05))`

**Text style:** `community-copy` — Inter 450 · 15px/1.5

**Observed:** 40px circular avatar and handle above multiline copy, with a 12px gap before the quotation. Cards vary in height and sit in five tightly spaced columns fading at the wall boundaries.

**Transfer:** Keep actual short voices, uneven text lengths and compact identity rows rather than matching every card height.

### Story accordion

**Use:** Prominent customer or outcome proof.

**CSS:** `display: grid; grid-template-columns: 1fr 76px 76px 76px 76px; gap: 8px; min-height: 480px`

**Text style:** `story-quote` — Manrope 450 · 22px/1.375

**Observed:** One expanded Concentrated story color panel and four narrow logo-only rails. Active content places an identity and short context near the top, then quotation, small attribution and understated underlined story link near the bottom.

**Transfer:** If customer stories are unavailable, use a real documented project outcome and its own identity; preserve the expanded-versus-rail contrast.

### Text field

**Use:** Newsletter and lead-generation inputs.

**CSS:** `height: 34px; padding: 8px 12px; border-radius: 8px; border: 1px solid rgba(3,3,3,0.146418); background: rgba(0,0,0,0.015)`

**Observed:** Visible label above each lead-form input; names share a row, email spans the width, and a 100px multiline message field precedes the full-width green submit. Newsletter uses one compact email field.

**Transfer:** Keep forms utilitarian, with a white 16px-corner outer panel and 24px inset on lead-generation pages.

### Footer columns

**Use:** Navigation-rich ending shared by all page types.

**CSS:** `display: grid; grid-template-columns: repeat(6, minmax(0px, 1fr)); column-gap: 16px; row-gap: 48px`

**Text style:** `footer-heading` — Manrope 600 · 15px/1.5

**Observed:** Six narrow link groups beside a wider identity/newsletter column. Links are 14px/20px muted grey. A preceding trust strip mixes a brief security statement, green text link and three checkmarked credentials; a fading horizontal line separates it from the footer. The bottom closes with a thin rule, copyright on the left and theme icon on the right.

**Transfer:** Let information depth determine footer height. Keep the footer near-white instead of introducing a dark last band.

### Plan card

**Only for:** pricing pages

**Use:** Joined plan comparison with an emphasized default choice.

**CSS:** `background: #ffffff; border: 2px solid #696969; border-radius: 16px; margin-top: -32px; margin-bottom: -32px`

**Text style:** `plan-name` — Source Code Pro 450 · 22px/1.333 · uppercase

**Observed:** The recommended card rises above and below adjacent cards and gets a dark small popularity tag. Interior order is name, audience description, full-width action, large monospaced price with small billing unit, separator and compact checkmarked inclusions. Ordinary plans use 1px faint edges and only the outside group corners are rounded.

**Transfer:** Emphasize one choice structurally rather than making its whole background green.

### FAQ row

**Only for:** pricing pages

**Use:** Readable objection handling beneath comparison content.

**CSS:** `border-bottom: 1px solid rgba(3,3,3,0.0812725); padding: 8px 0px`

**Observed:** An 864px-wide centered list. Each inner question control is 56px high with 16px vertical padding, 16px/24px Inter at weight 500 and a small down chevron on the far right. The wrapper adds breathing room without boxed accordion cards.

**Transfer:** Use questions in the reader's own language; keep individual rows visually flat.

## Imagery and graphics

### Paper technical illustrations

**Use:** Capability cards and small example panels.

**Observed:** Fine grey database rows, line-drawn objects, wireframe globes, node networks and small interface fragments sit on white. They are partially clipped by card edges and soften into the backing rather than appearing as dark standalone diagrams.

**Transfer:** Illustrate the new product's mechanisms with a simple schema, workflow or object outline. The minimum is a clean SVG with a few meaningful nodes and labels, not generic ornamental geometry.

**Build:** Use SVG strokes of 1px in grey at low alpha, white or near-white fills, and a few small dark terminal dots. Layer a white-to-transparent gradient over distant edges; keep the title and description region unobstructed. Place the drawing in the lower half or right half of a 400px-high feature card.

### Product demonstration

**Use:** A substantial chapter proving how the product works.

**Observed:** A broad, pale browser frame holds a real table-editing workflow. A small row of window dots and a narrow control header establish the frame; the content remains light with fine outlines. A separate split chapter pairs a heading with a bordered code panel and framework tabs.

**Transfer:** Show a single useful action at a readable scale. For a non-software product, use a truthful annotated process panel in the Demo stage; retain the pale backing and restrained controls.

### Dot-matrix proof

**Use:** Signature graphic metric or short proof word, balanced against explanatory text.

**Observed:** A green number made of small rounded square cells occupies a 720px-wide field beside text. Pale green and grey cells surround the numeral and dissolve outward into the near-white canvas. The result looks like lit pixels on paper rather than a neon screen.

**Transfer:** Use a genuine metric or short meaningful word. If no public metric exists, render a short product principle in the same cell system rather than inventing a number.

**Build:** Create an SVG cell lattice about 720px by 372px. Use roughly 8px rounded rectangles on a 10px pitch; assemble the central glyphs on a simple bitmap grid in forest green with varied opacity. Scatter pale green and grey cells behind them, then apply an elliptical alpha mask that fades all background cells to transparent near the edges. Keep foreground glyph cells crisp and unblurred.

### Monochrome logo proof

**Use:** Trust bands and corporate proof matrices.

**Observed:** Customer identities are grey and optically balanced rather than full-color advertisements. A horizontal band has two rows with faint surrounding rules. The corporate variant uses eight columns of soft grey tiles with narrow white gutters.

**Transfer:** Use real permissioned customer or ecosystem identities, normalize their optical size, and retain original proportions.

### Growth curve

**Only for:** enterprise performance chapters

**Use:** Quantified proof with a broad atmospheric chart behind the copy.

**Observed:** A thin grey curve rises gently from the lower left toward the upper right, with a barely visible grey area underneath. The right side has a small outlined floating metric card with a vertical guide, while the left carries a heading, paragraph and two plain numeric metrics.

**Transfer:** Use a real trend or clearly illustrative progression; retain the almost-paper contrast rather than turning it into a saturated analytics dashboard.

**Build:** Draw a smooth upward SVG Bézier across a 1280px by 595px stage with a 1px grey stroke. Fill beneath it with grey at low opacity fading to zero downward. Add an elliptical near-white edge mask. Place a small white rounded metric panel above the right-hand curve with a hairline guide and circular anchor; keep the left text area clear.

### Icons

**Observed:** Small outline utility icons use 16px boxes, 2px round strokes and neutral colors; chevrons are 12px. Capability icons can be 18–24px. Social and customer marks use filled silhouettes, while green checks provide compact proof.

**Transfer:** Use one coherent thin-stroke icon set for utilities and simple monochrome marks for identities. Place icons beside titles or inside small controls, not in oversized decorative circles.

## Section recipes

How recurring sections are built.

### First screen: Toolkit opening

**Observed:** The light Canvas begins beneath a 65px Sticky navigation. The centered main-container gives 160px of top breathing room before a two-column text row. A two-line 46px/1 promise occupies the left half, black then forest green; a three-line 16px/24px paragraph occupies the right half, aligned toward the headline's lower edge. Primary button and Secondary button sit 32px below the text row at the left, 8px apart. After 64px, the capability mosaic begins: one 538px-wide lead card beside two 263px cards, each 400px tall. Within the first 900px, the entire promise, support, actions and first card row are visible, with the next row just beginning. Layers are paper canvas, lightly edged white cards, pale mechanism drawings, then crisp text and controls; there is no full-bleed hero artwork.

**Transfer:** Write a two-part achievable promise and place a concise explanation beside it. Give the strongest capability double width and draw its mechanism if no polished media exists. Pricing opens with a centered 34px introduction above joined plans; enterprise lead-generation opens with text and customer marks left and a white form panel right; corporate pages open with a centered 46px statement and a plain metric strip.

**Avoid:** Do not center the default opening into a giant billboard, fill it with a dark dashboard, or push all product evidence below the first screen.

**Text style:** `display` — Manrope 500 · 46px/1

### Two-tone chapter heading

**Observed:** A left-aligned 34px heading combines a black claim with a grey continuation or the reverse, usually on two lines. A small underlined resource link can align at the far right. Typical chapter top padding is 96px and separation from heading to large media is 64px.

**Transfer:** Split the sentence by meaning, not by an arbitrary highlighted keyword. Use the grey phrase as context and the black phrase as the decisive idea.

**Text style:** `heading` — Manrope 600 · 34px/1.111

### Demonstration chapter

**Observed:** A Two-tone chapter heading sits above a three-pill selector and the Demo stage. The selected pill has a black outline while unselected pills are faint. A companion pattern places a short heading in the left half and a 544px bordered code panel with tabs in the right half.

**Transfer:** Select one or a few concrete tasks and let the view prove them. Keep the visible task more prominent than the surrounding application chrome.

### Examples mosaic

**Observed:** Two broad example cards carry small identities, 14px titles, descriptions and pale browser-framed previews; four smaller text-first cards sit beneath. Gutters are 12px and small cards use 10.7px corners.

**Transfer:** Mix substantial worked examples with a compact row of additional starting points. Preserve the contrast in card sizes rather than repeating uniform feature tiles.

### Proof stage

**Observed:** A Two-tone chapter heading and understated archive link introduce Story accordion. The 480px-high saturated active story is balanced by dark narrow identity rails; community proof uses a separate centered heading and compact action above a full-width, five-column wall of Community cards masked at the sides and bottom.

**Transfer:** Use concentrated authored proof and varied first-person testimony as complementary forms, not as a single repetitive grid.

### Graphic proof split

**Observed:** A short heading, paragraph and compact white repository action sit on the left while Dot-matrix proof occupies the right. The section is about 373px tall, with the graphic dissolving directly into Canvas.

**Transfer:** Pair an important principle with a truthful visual measure or short bitmap word. Preserve the asymmetric text-versus-data balance.

### Closing call and light footer

**Observed:** A centered 34px/1.2 heading joins a grey lead-in to a black payoff; paired actions sit beneath with 128px vertical section padding. The closing call is followed by the slim credential strip and Footer columns. Enterprise pages instead close their argument with a repeated two-column demo form and testimonial before the same credential strip and footer.

**Transfer:** Reprise the core promise in a shorter form, then offer self-service and assisted paths. For lead-generation pages, make the form the final action instead. Keep the trust strip and navigation-rich footer distinct from the conversion block.

**Text style:** `closing-heading` — Manrope 600 · 34px/1.2

### Enterprise capability chapters

**Only for:** enterprise pages

**Observed:** Small uppercase monospaced labels precede 34px standalone headings by 8px. Customer cards use three columns, outcome summaries four, and a support chapter uses three text columns with small icons and top rules. A centered large quotation then adds a personal voice and a monospaced role caption.

**Transfer:** Use compact outcome summaries, service details and one strong attributed quotation to address purchase risk, without turning every chapter into a heavy card.

### Pricing explanation and comparison

**Only for:** pricing pages

**Observed:** A centered 34px introduction leads to joined Plan cards. Subsequent explanations use 28px centered headings, 16px support and white outlined panels for configuration and cost controls. The long comparison uses a label column and four plan columns with fine horizontal rules, compact 12px details, category icons and persistent plan actions; FAQ row follows in a narrower 864px list.

**Transfer:** Separate choice, calculation and detailed comparison. Keep dense numbers aligned and put plain-language uncertainty handling near the end.

### Corporate directory

**Only for:** corporate pages

**Observed:** A centered 46px statement leads to four 28px metrics with slim vertical dividers, a muted logo matrix, an institutional proof grid and a four-column text directory. Press content uses small rounded cards with uppercase type labels; a later recruiting strip places prose left and one small action right.

**Transfer:** Use objective organizational proof and compact editorial entries. Do not substitute a large lifestyle-photo wall for this text-led composition.

## Page flow

**Storyline:** Achievable promise → concrete capability proof → working examples → independent validation → reduced risk → conversion reprise → trust and navigation.

### Product-led marketing landing page

1. **promise** — Split promise and support with paired actions, directly above the capability mosaic.
2. **social proof** — Muted two-row identity band.
3. **product demonstration** — Large workflow frame followed by a split integration/code chapter.
4. **starting points** — Broad example previews and smaller supporting cards.
5. **independent validation** — Expanded colored story, community card wall and graphic metric split.
6. **closing call** — Two-tone centered promise, action pair, trust strip and full light footer.

**Transfer:** Move from possibility to tangible use before asking the reader to accept social proof; keep a graphic proof device and a clear conversion reprise.

### Pricing and purchase evaluation

1. **choice** — Centered introduction above four joined plans with one structurally emphasized choice.
2. **cost explanation** — Configuration panel, numerical breakdown and practical add-on cards.
3. **detailed comparison** — Long ruled matrix with plan actions retained at the top.
4. **objection handling** — Flat FAQ rows and direct support route.
5. **closing call** — Shared promise reprise, trust strip and full footer.

**Transfer:** Offer a quick plan decision first, then let evaluators descend into calculation and detailed entitlements.

### Enterprise lead generation

1. **promise and conversion** — Audience label, two-line heading and customer marks beside a compact lead form.
2. **customer outcomes** — Three stories and four compact outcome summaries.
3. **operational proof** — Pale growth curve with metrics, security assurances and three service columns.
4. **personal validation** — Centered quotation with attribution and role caption.
5. **closing call** — Repeated lead form beside a testimonial, then shared trust strip and full footer.

**Transfer:** Make contact immediately available but earn it with measurable outcomes, operational detail and credible human proof.

### Corporate credibility and recruiting

1. **invitation** — Centered statement above four simple metrics.
2. **institutional proof** — Muted logo tiles, backer grid and compact individual directory.
3. **editorial proof** — Press and podcast cards with small uppercase content labels.
4. **recruiting** — Short text strip and a small green action.
5. **closing call** — Shared product promise reprise, trust strip and full footer.

**Transfer:** Keep organizational storytelling factual and compact, using directories and editorial cards rather than spectacle.

## Writing

Practical, optimistic and developer-literate. Confidence comes from naming what the product does and showing useful outcomes, with occasional friendly invitations rather than promotional theatrics.

**Do not copy:** Do not reuse Supabase's name, lightning mark, customer identities, numerical claims, funding totals, certifications, testimonials or proprietary product assertions. Use the source quotations below only as examples of sentence structure and tone. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader's work; use we for support, principles and operational commitments. Refer to the product directly when naming capabilities.
- **Rhythm:** Short imperative or benefit-led headlines, often two linked clauses. Support is usually one or two concrete sentences, with compact noun-led card titles and brief action labels.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Fast first outcome followed by a much larger future outcome. | Two clauses of about 3–5 words each | “Build in a weekend”<br>“Scale to millions” |
| Supporting line | Start with the core mechanism, then name concrete additions. | One or two sentences | “Start your project with a Postgres database. Add Authentication, Data APIs, Edge Functions, Realtime Data, Storage, and Vector embeddings.” |
| Chapter heading | An action or result followed by a practical qualifier. | 5–12 words | “Stay productive and manage your app without leaving the dashboard”<br>“Get expert help, whenever you need it” |
| Primary action | Verb plus the reader's immediate object, or a direct request. | 2–4 words | “Start your project”<br>“Request a demo” |
| Pricing reassurance | Describe how cost behaves rather than merely claiming cheapness. | Short headline and one supporting sentence | “Predictable pricing, designed to scale”<br>“Choose a plan, add projects, and see your total cost” |
| Objection handling | Use the reader's actual first-person concern. | One direct question | “Can I cap my usage so my bill doesn't run over?” |

**Words and phrasing to use:** build; start; scale; your project; integrated; production ready; open; control; learn; support

**Avoid:** revolutionary; game-changing; unleash; magic; best-in-class without proof; vague transformation promises

**Rules:**

- Lead with a useful action and clarify its mechanism immediately afterward.
- Keep technical terminology where it is genuinely useful; pair it with a plain-language outcome.
- Attach numerical outcomes to specific proof instead of scattering unqualified statistics through headlines.
- Use direct low-pressure actions and descriptive resource links.
- For enterprise content, name reliability, support and risk concerns concretely; for community content, allow a warmer first-person voice.

## Do's and Don'ts

### Do

- Keep the default opening at 46px/1 weight 500 with a deliberate green second line.
- Use 34px two-tone chapter headings rather than escalating every section to display scale.
- Align chapters to the 1088px useful inner width within the 1280px wrapper.
- Preserve the 12px mosaic gutters and mix double-width and single-width cards.
- Use white 15px interiors inside 16px gradient-edge panel frames.
- Keep marketing action pairs at 38px high and 8px apart.
- Give proof a concentrated color moment and a crisp green dot-matrix device.
- Let the closing call breathe with 128px vertical padding before the slim trust strip.

### Don't

- Do not turn the near-white default into a charcoal developer-tool theme.
- Do not replace the small polished rectangular actions with oversized 56px pills.
- Do not use forest green as a broad section background; it belongs to actions, short emphasis and graphic cells.
- Do not apply the demo frame's 10px shadow to every capability card.
- Do not set all body copy in monospace; reserve it for technical labels, prices and code.
- Do not make customer identities full-color billboards in the muted trust band.
- Do not flatten joined pricing cards into equally spaced floating boxes; the raised recommended column is the key distinction.
- Do not cap a long information-rich footer with a heavy dark band or giant closing logo.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains sticky while the document scrolls. The proof stage has one expanded story and narrow selectable rails; product demonstration chapters use selectors.
- No matched transition or animation declarations establish reliable component timings or easing.

**Transfer:**

- Keep text and controls stable while changing the active demonstration or story; preserve the strongly differentiated expanded panel and compact rails.

**Unknown:**

- Hover and focus-visible colors, exact animation timing, autoplay behavior and story-panel transition choreography are not established.

### Responsive

**Observed:**

- The desktop composition uses a two-column opening, a twelve-column capability grid, five community columns and six footer link columns.
- Responsive classes indicate single-column opening content at narrow widths, capability cards moving through one and two columns, and footer groups moving through two and three columns.

**Transfer:**

- Stack the support paragraph below the two-line promise while retaining its black/green distinction.
- Reduce card columns before shrinking descriptions; allow the double-width lead capability to become a full-width card.
- Replace narrow story rails with a compact selector and one readable active card. Keep the dot-matrix graphic visible in a separate row rather than reducing its cells to illegibility.

**Unknown:**

- Only desktop geometry is established; exact breakpoint widths, mobile navigation behavior and narrow-screen spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
