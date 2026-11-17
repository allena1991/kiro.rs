# SavvyCal — cream, coils and candor

## Overview

A warm, lightly irreverent software-marketing style with the confidence of a printed editorial and the usefulness of a working interface. Cream and sand carry most of the page, punctuated by tomato red, forest green and electric lime. Condensed bold serif headlines sit above open, readable sans-serif copy; colorful interface tableaux, faint sweeping graphics and occasional paper ephemera keep the spacious layouts personable rather than corporate.

### Essentials

- Headlines feel like compact newspaper promises, with a red punch line: GT-Alpina-Condensed 700 at 88px/0.95, normal tracking, with upright #f54320 emphasis; section titles use 48px/1.05.
- The opening is a left-aligned promise above a substantial product stage, not a centered slogan: 1280px outer container with 40px side padding, 672px support measure, and an 80px gap before a 1200px-wide green demonstration.
- Actions are small, soft lozenges beside plain arrow links: 14px/26px medium sans, 10px 20px padding and 46px height; red on cream, lime on dark green or near-black.
- Color behaves like an exhibit backing: cream and sand dominate the reading surfaces; saturated green, coral and lime frame white interfaces in 4px-radius stages. One full-width forest chapter and a near-black closing field give the pale page deliberate contrast.
- Oversized looping strokes are a signature material, not decoration confined to a logo: faint cream-on-cream curves behind the opening, tone-on-tone curves inside media, and a 1.4× expanded coil behind the closing call. Use an original abstract loop when there is no suitable identity motif.
- Product proof has real depth without glossy spectacle: white panels with 8px top corners, a fine 10% dark edge and a 25px 50px -12px cast shadow sit offset inside colored stages; a small floating confirmation can overlap the main panel. If no interface exists, construct a legible miniature workflow with the same staging.
- The ending is an inhabited dark landscape, not a detached CTA card: a 576px-wide serif invitation, lime action and arrow link lead into six compact footer columns, with a hairline legal row, all sharing #0c0c09 and the enormous low-contrast loop.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Tomato | `#f54320` | `--color-red` | accent, action, text | Upright headline emphasis, primary light-surface actions and small numbered annotations. |
| Forest | `#0d542b` | `--color-forest` | background | Full-width capability chapter, with lime titles and pale text. |
| Sand | `#f4ebda` | `--color-sand` | background, surface | Full-width alternate reading bands and base hue of translucent proof cards. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral deep | `#d9381a` | `--color-coral-bottom` | background | Bottom of warm product-stage gradients. |
| Coral light | `#ff7a50` | `--color-coral-top` | background | Top of warm product-stage gradients, not the page canvas. |
| Lime shade | `#8ddf4a` | `--color-lime-bottom` | background | Bottom of light-green product-stage gradients. |
| Electric lime | `#b9ff78` | `--color-lime` | text, action, accent | Dark-surface actions, green-band headings and circular capability icons. |
| Lime light | `#c9ff96` | `--color-lime-top` | background | Top of light-green product-stage gradients. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive black | `#0c0c09` | `--color-ink` | text, background | Headlines, actions and the closing canvas; warmer than pure black. |
| Olive body | `#474739` | `--color-body` | text | Long-form marketing copy. |
| Olive secondary | `#5b5b4b` | `--color-secondary` | text | Guarantee notes and small supporting text. |
| Footer olive | `#abab9c` | `--color-muted` | text | Low-priority links on the near-black closing field. |
| Pale olive | `#d8d8d0` | `--color-reverse-body` | text | Supporting paragraphs in the dark closing field. |
| Warm hairline | `#e4e0d6` | `--color-edge` | border | Visible result of 10% olive black over oatmeal; rules and panel edges use the alpha recipe. |
| Translucent sand | `#f6efe0` | `--color-soft-card` | surface | Visible 70% sand over oatmeal, used for testimonials and captioned media cards. |
| Oatmeal | `#fcf7ed` | `--color-canvas` | background, text | Default page canvas and reversed closing titles. |
| Interface white | `#ffffff` | `--color-white` | surface, text | Product windows, paper objects and text on red actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Light plan wash | `#fefbf6` | `--color-plan-wash` | surface | White at 50% over oatmeal, the understated plan surface. |

## Typography

- **InterVariable** — Body copy, navigation, actions, captions and compact feature headings. Clear contemporary sans with open counters and restrained medium weights. OpenType features: "cv11". If unavailable, use **Inter**. Font stack: "InterVariable", Inter, sans-serif.
- **GT-Alpina-Condensed** — Display promises, section titles and editorial quotations. Narrow, heavy editorial serif with pronounced contrast, lively terminals and compact word shapes. If unavailable, use **Roboto Serif**. Use 700 with the width axis near 75; preserve the condensed measure rather than widening headlines. Font stack: "GT-Alpina-Condensed", "Roboto Serif", Georgia, serif.
- **Caveat** (only for paper checklist illustrations) — Handwritten heading on a feature-index sheet. Informal, slanted marker-like handwriting. Font stack: "Caveat", Caveat, cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GT-Alpina-Condensed | 700 | 88px | 0.95 | normal | Primary promise, usually two lines with an upright red phrase. |
| heading | GT-Alpina-Condensed | 700 | 48px | 1.05 | normal | Section titles and closing invitation. |
| lead | InterVariable | 400 | 18px | 32px | normal | Opening support, kept to a 672px measure. |
| body | InterVariable | 400 | 16px | 28px | normal | Section explanations and FAQ question labels. |
| item-heading | InterVariable | 600 | 16px | 28px | normal | Feature-card headings and capability labels. |
| small-body | InterVariable | 400 | 14px | 26px | normal | Card descriptions, quotations and footer links. |
| caption | InterVariable | 400 | 14px | 24px | normal | Guarantee notes and secondary annotations. |
| action | InterVariable | 500 | 14px | 26px | normal | Buttons, navigation links and footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | InterVariable | 600 | 60px | 0.85 | -0.025em | Plan amount, aligned with smaller billing-unit text. |
| audience-specific landing pages | editorial-quote | GT-Alpina-Condensed | 700 | 36px | 1.15 | normal | A single substantial testimonial between hairlines. |
| pricing pages | plan-heading | GT-Alpina-Condensed | 700 | 36px | 40px | normal | Plan names inside the two large plan cards. |
| paper checklist illustrations | handwritten | Caveat | 700 | 36px | 1 | normal | Red handwritten sheet heading, rotated slightly counterclockwise. |
| product demonstrations | rule-statement | InterVariable | 500 | 28px | 1.6 | -0.025em | A sentence-size interactive rule demonstration, white with lime underlined variables. |
| pricing pages | table-heading | GT-Alpina-Condensed | 700 | 24px | 28px | normal | Centered plan labels in a sticky comparison header. |

**Notes:**

- Serif type supplies the expressive hierarchy; do not turn compact feature labels into more serif headlines.
- Large serif headings retain normal tracking. Negative tracking belongs to large sans numerals and the sentence demonstration, not to ordinary body text.
- Red emphasis is upright even when semantically marked as emphasis. Keep the emphasis a meaningful phrase, not scattered words.
- The display steps down to 76px and 56px in narrower layout variants; section titles step down to 40px. These are discrete size changes rather than a continuous viewport formula.

## Layout

**Density:** Airy at section scale, compact within proof: broad chapter padding surrounds tightly packed cards, table rows and miniature interfaces.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Gutters in testimonial and paired media-card grids; heading-to-description spacing in cards. |
| 12px | Action-to-guarantee gap and small inline clusters. |
| 16px | Action-row gaps and paragraph separation. |
| 24px | Headline-to-support grouping and testimonial padding. |
| 32px | Footer column gaps and internal plan-card groups. |
| 40px | Desktop container side padding, copy-to-text-link separation and plan-card padding. |
| 64px | Split-section column gap and section-heading-to-grid gap. |
| 80px | Opening copy-to-stage gap, FAQ padding and closing-field vertical padding. |
| 96px | Default major-section vertical padding. |

### Containers and grids

- **container**: max width 1280px · side padding 40px. Centered outer width including padding; at 1440px, the inner 1200px span leaves 120px to either viewport edge.
- **opening copy**: max width 896px. Headline measure; supporting paragraph narrows to 672px and remains left aligned.
- **split chapter**: 2 columns · gap 64px. Equal 568px text and media tracks within the inner container, vertically centered; swap the media side between chapters.
- **proof grid**: 3 columns · gap 8px. Dense testimonial cards in a broad, otherwise airy chapter.
- **paired exhibits**: 2 columns · gap 8px. Large media-led cards and price plans; cards share an edge rhythm without broad gutters.
- **footer columns**: 6 columns · gap 32px. Compact link groups below the closing invitation; the invitation itself is constrained to 576px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | media stages | 4px |
|  | proof and plan cards | 6px |
| product demonstrations | interface windows | 8px |
| product demonstrations | floating confirmations | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| product demonstrations | floating interface | `0px 0px 0px 1px rgba(0,0,0,0.1), 0px 25px 50px -12px rgba(0,0,0,0.4)` | White interface windows over dark stages. |
| paper checklist illustrations | paper | `0px 18px 30px rgba(39,39,26,0.12)` | A soft, diffuse shadow under the tilted sheet. |

### Surfaces

#### Oatmeal canvas · level 0

**Use:** Default light reading ground.

**CSS:** `background: #fcf7ed; color: #0c0c09`

**Observed:** The warm page ground remains visible around every exhibit and proof grid.

**Transfer:** Keep most reading on this field rather than turning the entire page into colored cards.

#### Sand band · level 0

**Use:** Alternating full-width capability and objection-handling chapters.

**CSS:** `background: #f4ebda; padding: 96px 0px`

**Observed:** A fine mottled grain gives the sand a printed, not glossy, finish.

**Transfer:** Use to distinguish a substantial chapter without boxing its text.

#### Forest chapter · level 0

**Use:** High-contrast product capability chapter.

**CSS:** `background: #0d542b; color: #b9ff78; padding: 96px 0px; overflow: hidden`

**Observed:** Oversized tonal loops fill the band; body copy is pale green, titles are lime. Audience and feature variants use a top-to-bottom green gradient instead of the flat forest base.

**Transfer:** Reserve this treatment for a strong product argument rather than every other section.

#### Green exhibit · level 1

**Use:** Default backing for the main product scene.

**CSS:** `background: linear-gradient(oklch(0.448 0.119 151.328) 0%, oklch(0.266 0.065 152.934) 100%); border-radius: 4px; overflow: hidden`

**Observed:** A white interface sits inset from the top and left, often extending to the bottom or right edge; grain and looping shapes sit behind it.

**Transfer:** Use the backing to elevate one understandable product task.

#### Coral exhibit · level 1

**Use:** Warm contrast for secondary product demonstrations.

**CSS:** `background: linear-gradient(in oklab, #ff7a50 0%, #d9381a 100%); border-radius: 4px; overflow: hidden`

**Observed:** The surface is tonal and subtly textured, not luminous or glassy.

**Transfer:** Alternate with green or dark exhibits to separate related capabilities.

#### Lime exhibit · level 1

**Use:** Light backing against a forest chapter or sand band.

**CSS:** `background: linear-gradient(in oklab, #c9ff96 0%, #8ddf4a 100%); border-radius: 4px; overflow: hidden`

**Observed:** Broad translucent loops cross behind the white foreground window.

**Transfer:** Keep this bright fill contained in media rather than extending it behind paragraphs.

#### Soft proof card · level 1

**Use:** Testimonials and media-card caption areas.

**CSS:** `background: rgba(244,235,218,0.7); border-radius: 6px`

**Observed:** Flat translucent sand without a raised shadow.

**Transfer:** Distinguish grouped proof through a small surface shift, not strong borders.

#### Closing field · level 0

**Use:** Shared closing invitation and footer.

**CSS:** `background: #0c0c09; color: #fcf7ed; overflow: hidden`

**Observed:** An enormous low-contrast loop runs behind the call and all link columns, unifying them.

**Transfer:** Carry the same field through the legal row; do not cut the invitation off into a separate box.

## Components

### Sticky navigation

**Use:** Persistent orientation with a restrained conversion action.

**CSS:** `position: sticky; top: 0px; z-index: 30; height: 84px; background: rgba(252,247,237,0.29)`

**Text style:** `action` — InterVariable 500 · 14px/26px

**Observed:** A compact wordmark and three links align left; login and a smaller red sign-up pill align right. The navigation uses the container width. A fine lower rule appears against scrolled content; the pale backing becomes more substantial away from the opening.

**Transfer:** Keep the link count compact; retain a small red account action instead of a second full-size hero button.

### Primary button

**Use:** Main conversion on a light surface.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #f54320; color: #ffffff; border-radius: 9999px; padding: 10px 20px; height: 46px`

**Text style:** `action` — InterVariable 500 · 14px/26px

**Observed:** Text-only rounded lozenge; paired with a quieter arrow action, not a second filled button. The header version uses 4px 14px padding and a 34px height.

**Transfer:** Use a short verb-led invitation and put any reassurance underneath.

### Lime button

**Use:** Conversion on dark fields and the emphasized plan.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #b9ff78; color: #0c0c09; border-radius: 9999px; padding: 10px 20px; height: 46px`

**Text style:** `action` — InterVariable 500 · 14px/26px

**Observed:** The same lozenge construction reverses the emphasis on dark backgrounds.

**Transfer:** Keep the dark text; do not use white on this luminous fill.

### Arrow action

**Use:** Secondary conversion and capability-detail links.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 10px 20px; border-radius: 9999px; color: #0c0c09; background: transparent`

**Text style:** `action` — InterVariable 500 · 14px/26px

**Observed:** An unboxed label ends with a small right arrow. Inline chapter variants remove the generous button padding; dark-surface variants reverse the text.

**Transfer:** Let the arrow distinguish navigation from the primary commitment.

### FAQ row

**Use:** Objection handling in a narrow question column.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 24px; padding: 16px 0px; color: #0c0c09; border-bottom: 1px solid rgba(12,12,9,0.1)`

**Text style:** `body` — InterVariable 400 · 16px/28px

**Observed:** A native disclosure question has a small plus at the far right and no browser marker. The answer is small-body text below; the plus becomes a diagonal cross when open. Rows share top and bottom hairlines rather than individual cards.

**Transfer:** Pair with a left-aligned heading and one conversational support link.

### Testimonial card

**Use:** Compact, readable customer proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 40px; padding: 24px; background: rgba(244,235,218,0.7); border-radius: 6px; color: #0c0c09`

**Text style:** `small-body` — InterVariable 400 · 14px/26px

**Observed:** Quote above, attribution below with a 48px circular portrait, semibold name and quieter role. Hanging opening quotation marks sit just outside the text. Three columns use an 8px gutter.

**Transfer:** Use specific first-person observations and keep attribution anchored even when quote lengths vary.

### Product stage

**Use:** Large product proof and smaller capability illustrations.

**CSS:** `background: linear-gradient(oklch(0.448 0.119 151.328) 0%, oklch(0.266 0.065 152.934) 100%); border-radius: 4px; overflow: hidden`

**Observed:** A white foreground interface is layered over a textured tonal coil. The opening uses a broad landscape stage; split chapters use approximately square or landscape stages, usually 568px wide. Foreground panels intentionally meet or pass the lower and right clipping edges.

**Transfer:** Show one coherent task, with enough controls and realistic labels to be believable, rather than many unrelated windows.

### Footer directory

**Use:** Closing navigation integrated into the final dark field.

**CSS:** `display: grid; grid-template-columns: repeat(6, minmax(0px, 1fr)); gap: 32px`

**Text style:** `small-body` — InterVariable 400 · 14px/26px

**Observed:** Small medium-weight light headings lead muted link lists spaced by 8px. The directory follows the closing call with a 64px gap; the legal row sits below a white 10% hairline with the wordmark at left and small links at right.

**Transfer:** Use only meaningful link groups, retaining the dense directory character and common dark backing.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side plan choice.

**CSS:** `background: rgba(255,255,255,0.5); padding: 40px; border-radius: 6px; overflow: hidden`

**Text style:** `plan-heading` — GT-Alpina-Condensed 700 · 36px/40px

**Observed:** Name and explanation precede the large sans price, billing note, full-width action, guarantee and divided inclusions. The emphasized plan changes to a forest gradient with lime name, lime action and a small recommendation badge; the light plan uses a translucent white action with a fine inset edge.

**Transfer:** Give each plan equal space while assigning only one the strong dark surface.

### Comparison row

**Only for:** pricing pages

**Use:** Detailed, scannable feature comparison.

**CSS:** `border-bottom: 1px solid rgba(12,12,9,0.05)`

**Observed:** A 1200px-wide table allocates about 40% to labels and the rest to two centered plan columns. Rows are about 50px high; category labels create larger pauses. Sticky oatmeal headers show serif plan names and small price captions; red outline checks and muted dashes replace verbose availability text.

**Transfer:** Group rows by decision area and keep descriptions left aligned; use actual table semantics.

### Paper checklist

**Only for:** feature-index openings

**Use:** A tactile illustrated index beside an opening promise.

**CSS:** `background: #ffffff; padding: 28px 32px 36px 32px; mask-image: radial-gradient(6px at 50% 100%, rgba(0,0,0,0) 97%, rgb(0,0,0))`

**Text style:** `handwritten` — Caveat 700 · 36px/1

**Observed:** A slightly clockwise-tilted sheet has a red handwritten heading, dark underline, checked feature rows, dashed dividers and a scalloped torn bottom edge. The surrounding wrapper carries the soft paper shadow.

**Transfer:** Use short linked capability labels on the sheet; keep the handwriting confined to its heading.

## Imagery and graphics

### Oversized tonal coil

**Use:** A recurring signature behind the opening, product exhibits, forest chapter and closing field.

**Observed:** Huge flat looping ribbon strokes extend beyond their frames, creating broad directional curves rather than a repeated small pattern. The opening is very low-contrast sand on cream; green exhibits carry lighter or darker green loops. The closing loop is white at 3.5% over olive black, enlarged to 1.4× its containing field.

**Transfer:** Create an original looping shape related to the new identity, or a simple two-turn ribbon when no motif exists. Preserve its scale, low contrast and edge clipping.

**Build:** Draw an SVG with two or three sweeping open elliptical paths, rounded caps and a broad stroke about 140px on a 1440px-wide field. Rotate the combined paths roughly -30deg and scale beyond the container so no complete emblem is visible. On cream use sand at low opacity; on dark use rgba(255,255,255,0.035). Clip to the field and keep the layer behind text. These path proportions are a construction recipe, not a fixed logo.

### Fine print grain

**Use:** Subtle material on colored exhibit backings and sand bands.

**Observed:** Fine monochrome noise sits over broad gradients; it never obscures the white product panels. Exhibit noise uses 0.25 opacity with overlay blending; sand-band noise uses 0.1 opacity, inverted and multiplied.

**Transfer:** Aim for a lightly printed surface rather than coarse film grain.

**Build:** Use an SVG turbulence filter with baseFrequency 1.4, one octave, seed 2 and stitchTiles enabled, convert to monochrome, then tile it behind the foreground interface. Apply mix-blend-mode overlay at opacity 0.25 on exhibits; use invert(1), multiply and opacity 0.1 on sand.

### Layered interface tableaux

**Use:** Main product demonstration and recurring capability chapters.

**Observed:** Crisp white booking, payment, message and chat panels use realistic avatars, fine rules and restrained controls. One dominant window occupies most of its colored frame, often offset 48px from the top and left in smaller exhibits, with a compact notification overlapping in front. Light comes from the white interface rather than from glows or glossy effects.

**Transfer:** Show the new product's recognizable task and result. A minimum version is one clean HTML interface panel plus one small output card on a tonal stage; keep internal UI colors subordinate to the marketing palette.

### Human attribution

**Use:** Customer quotations and believable interface personas.

**Observed:** Small, natural-color headshots appear as circles, not large editorial photographs; testimonial portraits are 48px and sit beside names and roles.

**Transfer:** Keep photography functional and intimate. Use real people only with appropriate permission; initials can fill product-demo avatars.

### Paper ephemera

**Only for:** feature-index and team administration illustrations

**Use:** A tangible alternative to another application window.

**Observed:** The feature index resembles a slightly tilted packing sheet with checkboxes and a scalloped foot. A separate billing illustration resembles a small receipt with dashed rules and compact mono numerals; these are miniature objects, not the page's body typography.

**Transfer:** Use a checklist, receipt or job ticket to make an otherwise abstract capability tangible.

**Build:** Place a white sheet within a 448px-wide wrapper, rotate the wrapper 1.5deg, and apply a diffuse 0px 18px 30px rgba(39,39,26,0.12) shadow. Cut a repeating 6px scallop into its bottom using a radial-gradient mask. Add a 2px dark rule under a red Caveat heading and 1px dashed low-opacity dividers between rows.

### Icons

**Observed:** Small rounded outline SVGs, usually 14px or 16px with 1.5px–1.8px strokes. Arrow links use 14px icons; capability symbols can be 20px inside lime circles. Red 20px outline checks mark plan comparisons, and small red numbered dots connect explanation rows to details inside a demonstration.

**Transfer:** Choose simple rounded-stroke functional icons; keep the arrow, check and plus vocabulary consistent. Use color to connect an annotation to its corresponding interface detail.

## Section recipes

How recurring sections are built.

### First screen: Promise above product stage

**Observed:** An 84px sticky navigation overlays a pale patterned field. The centered container aligns all content to its left inner edge. After 96px of opening space, an 88px/0.95 bold condensed serif promise occupies roughly the left two thirds, breaking into a dark first line and upright tomato-red second phrase. A two-line 18px/32px support paragraph sits within 672px; the red Primary button and Arrow action follow, with a small guarantee 12px below. After an 80px gap, a 1200px-wide Green exhibit holds a large white interface inset by about 64px. Within the first 900px the navigation, full headline, support, both actions, guarantee and upper part of the interface are visible; the stage's full depth and proof strip continue below. Layers run from cream, to oversized faint coil, to green textured stage, to white interface and small foreground UI details.

**Transfer:** Lead with the new product's benefit and show one actual task in the stage. Without finished product media, make a simplified but credible HTML workflow with a distinct result. Audience-specific pages retain the stacked promise and broad demo; pricing opens with a red emphasized price and plan pair; feature-index pages use a vertically centered split hero with a paper index on the right.

**Avoid:** Do not center the opening, shrink the main exhibit into a thumbnail beside the headline, or force the entire product window above the fold.

**Text style:** `display` — GT-Alpina-Condensed 700 · 88px/0.95

### Split capability chapter

**Observed:** A heading and body group sits beside Product stage in two equal columns with a 64px gap, vertically centered within 96px section padding. Heading-to-support spacing is 24px; a plain detail action follows after 40px. Cream and Sand band variants alternate which side holds the media.

**Transfer:** Make each chapter explain one benefit and let the demonstration prove the mechanism. Keep text shorter than the adjacent exhibit.

**Text style:** `heading` — GT-Alpina-Condensed 700 · 48px/1.05

### Numbered explanation

**Observed:** Below the chapter introduction, compact benefit rows use red circular numbers, semibold lead-ins and small-body explanations separated by faint hairlines. Matching red number pins appear in the interface; a plain arrow link concludes the text stack.

**Transfer:** Use when a task has a few distinct controls or steps. Ensure every pin has a corresponding explanation rather than scattering decorative badges.

### Paired media cards

**Observed:** A standalone serif heading precedes two nearly touching cards with an 8px gutter. Each uses a large colored Product stage above a sand caption area with a 16px semibold title, 14px/26px copy and a small arrow link. The card has a 6px outer radius and an 8px inset around its media.

**Transfer:** Compare two complementary capabilities without turning them into separate full-width chapters.

### Forest exhibit chapter

**Observed:** Forest chapter pairs a lime heading and pale explanatory text with a Lime exhibit. Beneath, a three-column capability strip uses white 15% top, bottom and vertical rules, about 40px internal spacing, lime circular icons, small sans headings and compact pale descriptions.

**Transfer:** Use the dark chapter to articulate a broader product system. The lower strip can stand on its own as a concise shared-benefits section.

**Text style:** `heading` — GT-Alpina-Condensed 700 · 48px/1.05

### Customer proof grid

**Observed:** A 48px serif title sits 64px above Testimonial cards in three columns with 8px gutters. Quotes remain small sans rather than oversized display text. An audience-specific variant is one 36px/1.15 serif quotation across an 896px measure between full-width hairlines.

**Transfer:** Choose grid proof for multiple concise observations and editorial proof for one substantial endorsement; retain the appropriate typographic variant.

### Split objection handling

**Observed:** An 80px-padded chapter puts a serif title and brief support with an underlined contact link on the left, and a stack of FAQ rows on the right. The FAQ track is about 580px wide; the pricing variant has a sand background and a longer list.

**Transfer:** Use real buying concerns and short, concrete answers. Keep the question stack visually lightweight.

**Text style:** `heading` — GT-Alpina-Condensed 700 · 48px/1.05

### Dark invitation and directory

**Observed:** Closing field begins with 80px padding, a 576px-wide two-line heading, pale 16px/28px support 16px below, and a Lime button plus reversed Arrow action after 32px. Footer directory follows after 64px. The same huge tonal coil spans both; a lower hairline and compact identity/legal row complete the field. All page types share this ending, including the feature-index page, which proceeds directly from its last capability without a FAQ chapter.

**Transfer:** Close with a low-pressure invitation and a specific next step, then retain useful directory navigation on the same dark ground.

**Text style:** `heading` — GT-Alpina-Condensed 700 · 48px/1.05

### Use-case directory

**Only for:** audience-specific landing pages

**Observed:** A sand chapter places a short title and support on the left and a broader linked list on the right. Each row combines a 16px semibold use-case name, a small explanatory sentence and a right arrow, with 20px vertical padding and fine separators.

**Transfer:** Present different applications of the same product without making a rainbow grid of audience cards.

### Plan selection and comparison

**Only for:** pricing pages

**Observed:** A serif opening emphasizes the price phrase in red. A small pill billing switch sits at the end of the support row. Two Plan cards follow with an 8px gutter: a translucent light card and a dark green emphasized card. Below, a broad comparison table uses an 80px sticky header under the navigation and about 50px rows, organized by category.

**Transfer:** Lead with the charging model, then make plan differences scannable; keep shared benefits in a separate forest chapter instead of repeating them in every plan.

**Text style:** `display` — GT-Alpina-Condensed 700 · 88px/0.95

## Page flow

**Storyline:** Plainspoken promise → tangible product proof → benefit chapters and trust → decision support → low-pressure dark invitation and useful directory.

### Broad product landing page

1. **Promise** — Two-tone left-aligned serif headline above a broad green demonstration.
2. **Social proof** — A narrow hairline-bounded strip of small customer and rating endorsements.
3. **Capability chapters** — Alternating split exhibits, a numbered explanation, paired media cards and a full-width forest chapter.
4. **Trust and expansion** — Compact testimonial grid and a further product-use demonstration.
5. **Objection handling** — Split FAQ with a short contact invitation.
6. **Closing call** — Dark patterned invitation flows into the six-column directory and legal row.

**Transfer:** Choose a few benefits that can be shown concretely; use the varied exhibit formats to change pace without changing the brand vocabulary.

### Audience-specific landing page

1. **Audience promise** — Red punch-line headline above a broad relevant workflow.
2. **Social proof** — One editorial serif quotation between hairlines.
3. **Capability chapters** — Split proof, a three-card capability group, a dark administrative chapter and paired miniature objects.
4. **Application breadth** — A ruled use-case directory instead of another media grid.
5. **Objection handling** — Audience-specific questions beside a contact line.
6. **Closing call** — The shared dark invitation, directory and legal ending.

**Transfer:** Tie the opening and demonstrations to one audience's working conditions; keep the same visual grammar rather than inventing a sub-brand.

### Pricing and purchasing decision

1. **Price promise** — Large serif charging-model statement with red price phrase and a compact billing toggle.
2. **Plan choice** — Two spacious equal-height plans, one light and one forest with lime emphasis.
3. **Detailed comparison** — Categorized full-width table with sticky plan headers and red checks.
4. **Shared value** — Forest shared-benefits strip followed by compact testimonials.
5. **Objection handling** — Longer FAQ list on sand.
6. **Closing call** — The shared dark invitation, directory and legal ending.

**Transfer:** Use the structure for transparent comparison; replace all commercial terms with the new product's actual model.

### Feature exploration and product breadth

1. **Product inventory** — Split opening with a tangible checked paper index.
2. **Capability chapters** — Forest overview then alternating cream and sand split exhibits; numbered callouts and a large sentence demonstration vary the proof.
3. **Advanced application** — A conversational interface scene closes the feature argument.
4. **Closing call** — Direct transition into the shared dark invitation, directory and legal ending.

**Transfer:** Let the index orient readers and link to benefit-led chapters; preserve the paper treatment as a scoped illustration rather than applying handwriting throughout the page.

## Writing

Conversational, capable and lightly wry. The product sounds useful because it explains the awkward work it removes, not because it piles on superlatives.

**Do not copy:** Do not reuse SavvyCal's name, logo, proprietary coil artwork, customer identities or quotations, customer totals, pricing, guarantees, discounts, integration claims or other product-specific promises. Source examples below illustrate cadence, not claims for a new product.

- **Addressing the reader:** Speak directly to you and your team; use we for the makers and occasional they for the recipient or customer whose experience also matters.
- **Rhythm:** Headlines are usually short clauses, often paired with a second punchy clause. Support uses one or two full sentences; card copy is concise but not telegraphic. Familiar idioms add levity without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the familiar task, then give it a fresh or relieving turn; isolate the benefit phrase for red emphasis. | 6–12 words | “The fresh way to find a time to meet.”<br>“Herding calendars, handled.” |
| Section title | A concrete benefit stated as an imperative or two compact clauses. | 4–9 words | “Leave a lasting impression”<br>“One brand. One bill.”<br>“Your time is valuable. Charge accordingly.” |
| Supporting line | Explain the mechanism and the human payoff in ordinary language. | 20–45 words | “[Brand] lines up your team’s calendars and only offers the times that work, so nobody has to play calendar Tetris again.” |
| Primary action | Short action with a low-risk qualifier; put the fuller commercial reassurance underneath. | 3–5 words | “Try [Brand] risk-free”<br>“Get started free” |
| Detail link | A clear verb plus the thing the reader will find, paired with an arrow. | 3–6 words | “See a live booking page”<br>“Explore workflows” |
| Closing invitation | Use an easygoing idiom and let the reader control when to commit. | 9–14 words | “Kick the tires for free and upgrade when you’re ready” |

**Words and phrasing to use:** plain English; handled; share the load; front and center; when you’re ready; busywork; keep it sane; no back-and-forth

**Avoid:** revolutionary ecosystem; synergize; unleash unprecedented potential; enterprise-grade excellence; hurry, last chance; effortless everything

**Rules:**

- Anchor each benefit in a concrete interaction or control.
- Acknowledge the inconvenience before presenting the fix.
- Use restrained humor in headlines and support, not in transactional details.
- Address both the operator's experience and the person on the receiving end when relevant.
- Keep FAQs direct about limits, pricing and requirements instead of answering with another sales pitch.

## Do's and Don'ts

### Do

- Keep the primary display at 88px/0.95 with normal tracking and a coherent red phrase.
- Use 48px/1.05 serif section titles and 16px/28px sans explanations as the standard chapter pairing.
- Align chapter content to the same 1200px inner desktop span.
- Use 96px chapter padding and 64px split-column gaps to leave room around dense product proof.
- Keep saturated coral and lime mainly inside 4px-radius exhibit backings.
- Use 46px pill actions beside plain arrow links; switch the filled action to lime in dark fields.
- Keep testimonials flat, with 24px padding and only 8px between cards.
- Repeat the oversized low-contrast loop at multiple scales, including the shared dark ending.

### Don't

- Do not use pure white as the default page canvas; preserve the oatmeal and sand distinction.
- Do not replace the condensed serif display with a neutral sans or widely tracked slab.
- Do not italicize the red headline phrase; its emphasis is color, not slant.
- Do not apply 16px or 24px rounding to all marketing panels; stages are 4px and proof cards 6px.
- Do not give testimonials the heavy 25px cast shadows reserved for layered interface demonstrations.
- Do not spread bright demo-interface blues or purples into the marketing palette.
- Do not turn every support paragraph into 14px text; reserve that size for cards, captions and dense proof.
- Do not enlarge footer headings into another display tier; their 14px medium hierarchy is deliberately compact.

## Motion and responsive

### Motion

**Observed:**

- The presentation uses a sticky navigation that changes its pale backing over scrolled content.
- FAQ plus icons change orientation for the open disclosure. Product demonstrations show variable states within otherwise stable frames.

**Transfer:**

- Keep the dominant product stage and background coil composition stable while any demonstration changes its internal state.

**Unknown:**

- Transition timing, easing and triggering rules are not established; no animation duration is prescribed.

### Responsive

**Observed:**

- The display has 56px, 76px and 88px size variants; section titles have 40px and 48px variants.
- Layout variants reduce split chapters to one column, testimonials from three to two to one, and footer columns from six to three to two. Container side padding changes from 40px to 24px.
- The full desktop navigation link group has a narrow-layout hidden variant.

**Transfer:**

- Stack text and its product exhibit without losing their shared chapter; scale the scene within its colored frame rather than exposing an unreadably small whole application.
- Keep the paper index as one coherent sheet beneath the promise on narrow screens; preserve the scalloped edge and restrained handwriting.

**Unknown:**

- Exact viewport thresholds and the narrow-screen navigation replacement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
