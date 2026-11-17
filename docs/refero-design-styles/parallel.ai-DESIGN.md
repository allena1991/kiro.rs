# Parallel — ruled grids, luminous machinery

## Overview

An airy technical identity that pairs modest grotesk headlines and tiny monospace labels with expansive, tactile graphics. White and warm gray dominate, punctuated by utility orange, sky blue atmospheres and colored proof cards. Simplified interfaces, printed textures and striped data-like artwork give complex software a tangible presence without making the surrounding page dense. It suits infrastructure, developer tools and products whose value is best explained through working examples.

### Essentials

- The headline is a label for a much bigger stage, not a billboard: 36px/40px medium grotesk, normal tracking, left aligned above a 1296px-wide atmospheric media frame with 4px corners.
- A ruled technical folio holds the page together: 48px outer gutters, another 24px inset to content, 1px pale vertical rules and a 12-column grid with 48px gaps. Keep the rules intermittent, aligned to content blocks rather than boxing every section.
- Actions look like compact equipment controls: 34px high, 4px radius, 13px monospace capitals, 9px 16px 7px padding, with orange primary, charcoal utility and white outlined secondary variants.
- Color is contained in objects rather than spread across the canvas: white and gray carry text sections; large blue stages, textured orange illustrations and 380px × 520px colored proof cards provide concentrated chromatic moments.
- Interfaces float inside material: white 6px-radius cards with hairline edges sit on warm gray, grainy print fields or hazy blue planetary light. Include an atmospheric stage and a tactile striped graphic; use CSS/SVG light fields and original geometric line art when bespoke media is unavailable.
- The ending retains an engineered afterimage: a spacious ruled directory footer gives way to a full-width dark striped relief, with repeated vertical line segments forming larger abstract shapes. Recreate this with original geometry rather than ending at the last text link.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Utility orange | `#fb631b` | `--color-orange` | action, accent, link | Primary conversions, highlighted words and selected data marks. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft orange | `#f4793f` | `--color-orange-soft` | surface, action | Orange button hover and warm proof-card variant. |
| Announcement blue ink | `#0d6ea5` | `--color-notice-ink` | text, link | Announcement copy and link. |
| Closing blue | `#548fd1` | `--color-closing-blue` | background | Closing atmospheric action stage. |
| Atmospheric sky | `#6fa2e8` | `--color-sky` | background | Opening atmospheric media backing. |
| Green proof card | `#5fa96c` | `--color-proof-green` | surface | Green proof-card variant. |
| Blue proof card | `#8fb6cc` | `--color-proof-blue` | surface | Dusty blue proof card. |
| Peach highlight | `#fcddcf` | `--color-peach` | surface, accent | Inline answer highlights and promotional strips. |
| Announcement blue wash | `#e9f0f5` | `--color-notice` | surface, border | Announcement strip and fine light rules on proof cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#181818` | `--color-ink` | text | Headings and primary text. |
| Utility charcoal | `#434343` | `--color-charcoal` | surface, action | Dark utility actions and the dark ground beneath terminal artwork. |
| Warm gray text | `#858483` | `--color-secondary` | text, link | Support copy, navigation and technical captions. |
| Earth proof card | `#a8a497` | `--color-proof-earth` | surface | Muted olive-gray proof card. |
| Structural rule | `#d6d6d6` | `--color-rule` | border | Section rules and outlined action borders. |
| Column edge | `#e5e5e5` | `--color-column-edge` | border | Footer and comparison column divisions. |
| Warm demonstration ground | `#ebe9e3` | `--color-warm-stage` | surface | Broad backing for floating interface illustrations. |
| Card edge | `#eeeeee` | `--color-card-edge` | border, surface | Fine interface card borders and muted chips. |
| Pale warm ground | `#f5f4f1` | `--color-art-ground` | surface | Product overview art and pale demonstration panels. |
| Utility gray wash | `#f6f6f6` | `--color-row` | surface | Alternating comparison rows, paper and utility controls. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, interface cards and reversed text. |

## Typography

- **gerstnerProgramm** — Headlines, narrative text and product descriptions. Compact, matter-of-fact grotesk with a sturdy medium weight; small scale changes establish hierarchy rather than dramatic display typography. If unavailable, use **Inter**. Use 400 and 500; retain normal headline tracking. Font stack: "gerstnerProgramm", "Inter", Arial, sans-serif.
- **ftSystemMono** — Navigation, controls, eyebrows, footer directories and numeric prices. Small utilitarian monospaced lettering, with uppercase reserved for controls and category headings. If unavailable, use **IBM Plex Mono**. Use 400, 500 and 700; keep labels compact. Font stack: "ftSystemMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | gerstnerProgramm | 500 | 36px | 1.11 | normal | Opening promise; one restrained headline above the media stage. |
| closing-title | gerstnerProgramm | 500 | 36px | 1.111 | normal | White title in the blue closing action stage. |
| heading-lg | gerstnerProgramm | 500 | 32px | 1.125 | normal | Major section titles and comparison-page headline. |
| heading | gerstnerProgramm | 500 | 26px | 1.23 | normal | Feature headings, large support lines and black/gray heading pairs. |
| card-title-and-quote | gerstnerProgramm | 500 | 20px | 1.4 | normal | Product card names, selectable capability titles and proof quotations. |
| body | gerstnerProgramm | 500 | 16px | 1.5 | 0.01em | Default explanatory copy, usually secondary gray. |
| faq-question | gerstnerProgramm | 500 | 16px | 1.5 | 0.0094em | Question labels in the broad FAQ list. |
| label | ftSystemMono | 400 | 13px | 1.23 | 0.012em | Navigation, directory links and technical captions in mixed case. |
| control | ftSystemMono | 400 | 13px | 1.23 | 0.012em, uppercase | Action labels and footer category headings. |
| eyebrow | ftSystemMono | 500 | 13px | 1.23 | 0.012em | Small mixed-case section identifier above the heading. |
| quote-credit | gerstnerProgramm | 500 | 13px | 1.385 | 0.0115em | Two-line attribution beneath a quotation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing comparisons | price | ftSystemMono | 700 | 16px | 1.5 | 0.01em | Prices as compact bold numbers, not giant promotional numerals. |
| editorial manifesto pages | paper-text | ftSystemMono | 400 | 12px | 1.333 | -0.02em | Dense numbered prose on a narrow continuous-paper sheet. |

**Notes:**

- Headlines stay medium and normally tracked; hierarchy is 36px, 32px, 26px, 20px, then 16px prose. Do not turn the opening into oversized display lettering.
- The 26px heading recipe can form a sentence split between primary ink and secondary gray with no gap between the two lines.
- Monospace is part of the marketing identity, not merely code decoration: use it in navigation, labels, buttons and directory links.
- Price-table prose uses a lighter 400 weight while narrative feature copy defaults to 500.

## Layout

**Density:** Airy at section scale, compact within controls and demonstrations; large white pauses surround small technical content.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Feature heading-to-description gap. |
| 8px | Action-group gaps, icon gaps and closely stacked interface cards. |
| 12px | Eyebrow-to-title spacing and compact heading stacks. |
| 16px | Opening headline-to-support and support-to-actions spacing. |
| 24px | Paragraph-to-action spacing, section inner horizontal inset and proof-card gaps. |
| 40px | Footer groups and larger local stacks. |
| 48px | Structural grid gaps, main outer gutters and opening text-to-media gap. |
| 80px | Standard section vertical padding. |
| 120px | Deeper technical and FAQ section entrances. |
| 160px | Major chapter entrances and large footer separation. |

### Containers and grids

- **outer-folio**: max width 1600px · side padding 48px. Centered outer folio. At a 1440px viewport the main content receives another 24px inset, giving 1296px of working width.
- **section-grid**: 12 columns · gap 48px · side padding 24px. Base grid for heading blocks, media and intermittent vertical guides.
- **feature-pair**: gap 48px. A 328px narrative column alongside a 920px media panel at desktop; alternate the narrow copy column from left to right.
- **product-grid**: 3 columns · gap 48px. 400px-wide art-led cards in two rows with 60px vertical separation.
- **proof-track**: gap 24px. Horizontal track of 380px-wide tall cards, extending beyond the right edge to expose another card.
- **manifesto-sheet** (only for editorial manifesto pages): max width 700px. Centered continuous-paper artifact; inner numbered text is 313px wide rather than spanning the sheet.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls-and-media | 4px |
|  | floating-interface | 6px |
| interactive atmospheric demonstrations | glass-prompt | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| interface-stack | `rgba(0, 0, 0, 0.03) 0px 1.5px 0.8px 0px, rgba(0, 0, 0, 0.02) 0px 3px 0.5px 0px, rgba(0, 0, 0, 0.01) 0px 5px 0.5px 0px` | Shallow layered shadow for interface fragments. |
| proof-card | `rgba(0, 0, 0, 0.07) 0px 83.3px 66.6px 0px, rgba(0, 0, 0, 0.05) 0px 34.8px 27.8px 0px, rgba(0, 0, 0, 0.04) 0px 18.6px 14.9px 0px, rgba(0, 0, 0, 0.04) 0px 10.4px 8.3px 0px, rgba(0, 0, 0, 0.03) 0px 5.5px 4.4px 0px, rgba(0, 0, 0, 0.02) 0px 2.3px 1.8px 0px` | Long soft grounding shadow beneath tall proof cards. |

### Surfaces

#### White folio · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #ffffff; color: #181818`

**Observed:** Thin vertical rules mark selected section edges and column boundaries, with ample unpainted space between chapters.

**Transfer:** Carry structural guides across unrelated content without making a continuous graph-paper background.

#### Warm demonstration panel · level 1

**Use:** Backing for interface explanations.

**CSS:** `background: #ebe9e3; border-radius: 4px; overflow: hidden`

**Observed:** A broad flat warm-gray stage centers a small group of white interface cards.

**Transfer:** Keep the stage spacious and the illustrated workflow legible at a glance.

#### Floating interface card · level 2

**Use:** Illustrated answers, prompts and compact workflow outputs.

**CSS:** `background: #ffffff; border: 1px solid #eeeeee; border-radius: 6px; padding: 16px 20px; box-shadow: rgba(0, 0, 0, 0.03) 0px 1.5px 0.8px 0px, rgba(0, 0, 0, 0.02) 0px 3px 0.5px 0px, rgba(0, 0, 0, 0.01) 0px 5px 0.5px 0px`

**Observed:** Small cards stack in 8px gaps, often with an input card above an output and source detail below.

**Transfer:** Show a meaningful input/output interaction, not a complete application dashboard.

#### Atmospheric stage · level 1

**Use:** Luminous opening object.

**CSS:** `background: #6fa2e8; border-radius: 4px; overflow: hidden`

**Observed:** Soft cyan-white planetary light blooms across blue; the media itself is atmospheric rather than a flat gradient.

**Transfer:** Use layered blurred light arcs and grain as described in Atmospheric horizon.

#### Closing atmosphere · level 1

**Use:** Large conversion stage.

**CSS:** `background: #548fd1; border-radius: 4px; overflow: hidden`

**Observed:** The luminous object fills the right side while the left remains calm enough for white text and actions.

**Transfer:** Let the same visual world return without duplicating the opening interaction.

#### Comparison wash · level 1

**Only for:** pricing comparisons

**Use:** Alternating broad table bands.

**CSS:** `background: #f6f6f6`

**Observed:** White and gray rows are crossed by fine column rules, not individual rounded plan cards.

**Transfer:** Organize comparable facts in aligned rows and keep price labels visually compact.

#### Continuous paper · level 1

**Only for:** editorial manifesto pages

**Use:** A single long editorial artifact.

**CSS:** `background: #f6f6f6; box-shadow: rgba(0, 0, 0, 0.07) 0px 3px 6px 0px, rgba(0, 0, 0, 0.06) 0px 10px 10px 0px, rgba(0, 0, 0, 0.04) 0px 23px 14px 0px, rgba(0, 0, 0, 0.01) 0px 42px 17px 0px`

**Observed:** Tractor-feed holes, faint distressed grain and shaded paper edges frame narrow monospaced prose.

**Transfer:** Reserve the physical-document metaphor for a sustained editorial argument.

## Components

### Primary button

**Use:** Default marketing conversion.

**CSS:** `background: #fb631b; color: #ffffff; border: 1px solid transparent; border-radius: 4px; height: 34px; padding: 9px 16px 7px; box-sizing: border-box`

**Text style:** `control` — ftSystemMono 400 · 13px/1.23 · tracking 0.012em · uppercase

**Observed:** Inline label may end in a small square keyboard-shortcut badge. Sits beside an outlined action rather than spanning the section.

**States:** Declared: hover background-color #f4793f; focus-visible unknown; active background-color #fb631b and scale 0.98.

**Transfer:** Use a short verb-led action appropriate to the new product.

### Outlined button

**Use:** Secondary conversions and documentation access.

**CSS:** `background: #ffffff; color: #181818; border: 1px solid #d6d6d6; border-radius: 4px; height: 34px; padding: 9px 16px 7px; box-sizing: border-box`

**Text style:** `control` — ftSystemMono 400 · 13px/1.23 · tracking 0.012em · uppercase

**Observed:** Shares the primary control silhouette; label remains compact and can include a keyboard badge.

**States:** Declared: hover background-color #ffffff and color #858483; focus-visible unknown; active color #181818 and scale 0.98.

### Utility button

**Use:** Contact and technical actions; primary conversion variant on product-detail and comparison pages.

**CSS:** `background: #434343; color: #ffffff; border: 1px solid transparent; border-radius: 4px; height: 34px; padding: 9px 16px 7px; box-sizing: border-box`

**Text style:** `control` — ftSystemMono 400 · 13px/1.23 · tracking 0.012em · uppercase

**Observed:** Charcoal rather than pure black; paired with an outlined supporting action.

**States:** Declared: hover background-color #5c5b59 and opacity 0.8; focus-visible unknown; active background-color #434343 and scale 0.98.

### Navigation link

**Use:** Compact navigation and directory items.

**CSS:** `color: #858483; background: transparent`

**Text style:** `label` — ftSystemMono 400 · 13px/1.23 · tracking 0.012em

**Observed:** Mixed-case mono text; menu triggers add a small down chevron. Navigation aligns right of a compact bold wordmark with 24px between groups.

**States:** Declared: hover color #fb631b; focus-visible unknown; active color #181818 for ordinary links.

### Announcement strip

**Use:** Single short update above the main navigation.

**CSS:** `background: #e9f0f5; border-radius: 4px; padding: 2px 16px; min-height: 28px; display: flex; justify-content: center; align-items: center`

**Observed:** Tiny blue underlined copy and a learn-more link are centered; a dismiss icon sits at the far right.

**Transfer:** Use one concise announcement, not a stack of campaign bars.

### Product overview card

**Use:** An art-led capability or product inventory.

**CSS:** `background: transparent; color: #181818`

**Text style:** `card-title-and-quote` — gerstnerProgramm 500 · 20px/1.4

**Observed:** A 400px × 255px warm pale art panel sits above an icon and title, then a compact gray description. No outer enclosing border; artwork can be clipped at the right and bottom edges.

**Transfer:** Make each panel explain a different interaction while retaining the same light backing.

### Proof card

**Use:** Credible customer or practitioner testimony.

**CSS:** `background: #a8a497; border-radius: 4px; width: 380px; height: 520px; position: relative; overflow: hidden`

**Text style:** `card-title-and-quote` — gerstnerProgramm 500 · 20px/1.4

**Observed:** White quotation and smaller attribution occupy the upper portion with a fine left rule; a white logo and occasional case-study link anchor the bottom. Earth, dusty blue, orange and green variants carry a faint square grid and long soft shadows.

**Transfer:** Use authenticated testimony; keep the large quiet lower area rather than filling every inch with copy.

### FAQ question

**Use:** A broad low-chrome objection-handling list.

**CSS:** `background: transparent; color: #181818; text-align: left`

**Text style:** `faq-question` — gerstnerProgramm 500 · 16px/1.5 · tracking 0.0094em

**Observed:** Questions stack 32px apart in the wider right column. The first answer can be expanded; the section label sits in a narrow left column. Product-detail variant uses plus/minus glyphs and a narrower list.

**States:** Declared: hover color #5c5b59; focus-visible unknown.

### Footer directory column

**Use:** Grouped navigation in the site ending.

**CSS:** `border-right: 1px solid #e5e5e5; padding-right: 24px; display: flex; flex-direction: column; gap: 40px`

**Text style:** `label` — ftSystemMono 400 · 13px/1.23 · tracking 0.012em

**Observed:** A wider contact-and-updates column takes about two fifths of the width, followed by three slim directory columns. Uppercase category headings use Control; mixed-case gray links use Label. Social links and service status sit near the bottom opposite certification and legal identity.

**Transfer:** Retain the spacious ruled directory structure even when there are fewer categories.

### Updates input

**Use:** Email subscription within the footer.

**CSS:** `background: rgba(246, 246, 246, 0.7); border-radius: 4px; height: 40px; max-width: 384px; padding: 8px 8px 8px 12px; box-sizing: border-box`

**Observed:** A pale field has a right-aligned arrow submit control instead of an adjacent full button.

**Transfer:** Keep the field quiet and aligned with the contact block.

### Comparison cell

**Only for:** pricing comparisons

**Use:** Technical plan and capability comparison.

**CSS:** `border-right: 1px solid #e5e5e5; padding: 14px 24px; min-height: 60px; display: flex; align-items: flex-start`

**Text style:** `body` — gerstnerProgramm 500 · 16px/1.5 · tracking 0.01em

**Observed:** A 132px row-label column precedes seven comparable offerings in the wide overview. Inputs use gray chips, outputs peach chips, and a peach full-width incentive strip precedes per-column actions.

**Transfer:** Use fewer columns when needed but preserve aligned factual rows, explicit units and compact bold monospace prices.

## Imagery and graphics

### Atmospheric horizon

**Use:** Signature blue visual stage in the opening and recurring closing call.

**Observed:** A blurred cyan-white horizon or partial globe rises into a clear blue field. The opening places a translucent prompt near the center; the closing moves the luminous mass to the right of white text. Light is soft and expansive, with subtle grain rather than glossy hard-edged 3D.

**Transfer:** Use an original soft planetary or field-like light composition. The minimum equivalent is a layered hazy arc with a credible product input floating above it, not stock cloud photography.

**Build:** Fill a 4px-rounded clipped stage with sky blue. Place a very wide elliptical cyan-white radial light layer below center so only its upper arc is visible; combine several lower-opacity elliptical wisps along the arc, blur 30px–60px, then overlay fine low-opacity SVG turbulence grain. In a closing variant shift the arc to the right and leave the left third mostly uniform. Match the soft glow; exact gradient stops are not essential.

### Printed signal fields

**Use:** Signature tactile illustration behind selected workflow and cost/onboarding explanations.

**Observed:** Orange or blue rectangular ink fields sit on grainy warm paper. Dense vertical bars of unequal lengths overlap in pale and dark inks like a coded print or relief. A small clean white interface card floats over the pattern, creating a deliberate analog/digital contrast.

**Transfer:** Produce original bars from the new product's workflow or data; retain the screen-printed material, limited inks and calm white overlay.

**Build:** Use a warm pale rectangular ground with SVG feTurbulence grain. Layer a slightly inset orange or blue ink rectangle; draw evenly spaced 2px–6px vertical bars with stepped, unequal endpoints and grouped lengths. Mix pale bars at low opacity with darker bars, then add sparse paper flecks. Place a 6px-rounded white input or output card across the middle with the Interface-stack shadow.

### Interface vignettes

**Use:** Recurring feature demonstrations and product overview artwork.

**Observed:** Small HTML-like cards demonstrate prompts, answer highlights, source chips, confidence indicators, tabular results and stacked outputs. White cards sit on flat warm-gray grounds; text is selectively readable while secondary content fades into pale lines. Oversized fragments clip naturally at panel edges.

**Transfer:** Choose one meaningful input and one useful output per scene. Use authentic short text and abstract only the lower-priority lines.

### Proof-card grid

**Use:** Material overlay across colored testimony cards.

**Observed:** Fine darker square grids cover tall muted colored cards; a subtle diagonal sheen and soft grounding shadow make them feel like printed plates.

**Transfer:** Keep the grid subordinate to the quotation and use the curated proof colors.

**Build:** Overlay two repeating-linear-gradients at 0deg and 90deg with 1px dark lines at low alpha, about 28px apart. Add a white-to-transparent diagonal sheen at 8% alpha and the Proof-card shadow; inset quotation and credit beside a thin light vertical rule.

### Technical proof plots

**Use:** Measured-performance chapters.

**Observed:** A large white dot-field scatter plot uses tiny mono labels, orange square markers for the featured series and neutral marks for comparators. A narrow right-hand methodology column is separated by a hairline rule; explanatory prose stays visually secondary.

**Transfer:** Use real measurements, explicit axes and units, compact labels and readable methodological context rather than decorative statistics.

**Build:** Draw a pale evenly spaced dot lattice in SVG, map real data to axes, use small orange squares and neutral circles, and place labels beside points without giant numerals.

### Terminal striped relief

**Use:** Full-width visual after the footer on every page type.

**Observed:** A dark charcoal band reveals repeated abstract shapes built from many thin vertical strokes with stepped changes in length and value. It has the density of a woven or engraved panel, not a text-heavy final banner.

**Transfer:** Create an original recurring striped emblem or geometric field; retain the low-contrast dark material and edge-to-edge finish.

**Build:** Create an SVG tile of closely spaced vertical lines on charcoal, varying line endpoints with a coarse stepped wave or abstract emblem mask. Repeat the tile at roughly one quarter of the viewport width; use several dark alpha values to produce relief. Expose about 240px beneath the white footer and allow it to read as a continuous field.

### Tractor-feed manifesto

**Only for:** editorial manifesto pages

**Use:** A company or product philosophy presented as a physical document.

**Observed:** A long pale sheet has continuous rows of circular feed holes on both sides, faint distressed text, small title/date metadata, a centered emblem, numbered narrow prose and a bottom location/date stamp above ruled lines. It ends directly before the directory footer, without the blue conversion stage.

**Transfer:** Present a sustained original argument with numbered short passages. Keep the document as the dominant object rather than adding a conventional hero and card grid.

**Build:** Center a 700px paper panel, shade its right edge with a faint gray-to-transparent strip and add soft paper shadow. Cut or simulate repeated small white circular holes near both edges using radial-gradient masks or SVG circles. Overlay sparse gray noise, constrain prose to 313px and add several thin horizontal rules plus an original small stamp at the bottom.

### Icons

**Observed:** Mostly small 14px–18px monochrome glyphs or SVGs. Outline controls commonly use 1.5px round strokes at 16px; technical product glyphs can be filled. Icons sit beside labels, and small square keyboard badges reinforce the instrument-panel feeling.

**Transfer:** Choose compact utilitarian symbols, keep them close to the text baseline and avoid large decorative icon circles.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric product opening

**Observed:** A white first screen begins with a 28px pale announcement strip and compact navigation. A large white pause precedes the left-aligned 36px headline; a 26px gray support line follows after 16px, then a row of 34px actions after another 16px. The primary is orange; the secondary is a copy/onboarding control. After 48px comes a 1296px × 566px blue Atmospheric stage with 4px corners and narrow vertical guides outside its edges. Its blurred luminous horizon fills the frame; a small segmented mono control floats above a translucent prompt card around the visual center. Within the first 900px, the headline, support, actions and most of the main visual are visible; the stage bottom and centered social-proof block continue below the fold. The headline stays on white rather than over the blue media.

**Transfer:** For a new product, pair a concise destination-like promise with a broad description and one real product input on an original Atmospheric horizon. Preserve the imbalance between modest typography and expansive object. Product-detail openings use a mono category label, a 36px headline with an orange changing word, charcoal and outline actions, then a pale workflow demonstration. Comparison openings use a 32px headline and 26px support above a factual table. Editorial openings foreground Continuous paper instead of a conventional hero.

**Avoid:** Do not center a giant headline over the horizon, turn the whole first screen blue, or replace the luminous stage with a dense dashboard.

**Text style:** `display` — gerstnerProgramm 500 · 36px/1.11

### Feature and demonstration pair

**Observed:** Use Feature-pair with 80px vertical padding: a narrow top-aligned heading, 6px to gray body copy and 24px to an Outlined button, beside a broad Warm demonstration panel or Printed signal field. Alternate the copy side; white space and a vertical guide separate copy from media.

**Transfer:** Give each pair one distinct capability, expressed as an input/output illustration instead of a list of generic benefits.

**Text style:** `heading` — gerstnerProgramm 500 · 26px/1.23

### Chapter heading pair

**Observed:** A 26px primary-ink statement is completed by a secondary-gray line in the same recipe. Short product chapters use 80px padding above and below; supporting demonstrations follow as their own broad sections.

**Transfer:** Split a claim and its mechanism or qualification into two tones without changing font or adding oversized emphasis.

**Text style:** `heading` — gerstnerProgramm 500 · 26px/1.23

### Art-led inventory

**Observed:** An Eyebrow, 32px heading and gray paragraph introduce the Product-grid. Product overview cards use pale cropped art above unboxed title-and-description blocks, with 48px horizontal and 60px vertical spacing.

**Transfer:** Use for a capability inventory of an appropriate size rather than requiring a particular number of products.

**Text style:** `heading-lg` — gerstnerProgramm 500 · 32px/1.125

### Proof and methodology

**Observed:** A 32px heading and 26px gray support lead to compact actions and benchmark tabs. A large Technical proof plot takes the broad left area, with methodology in a narrow ruled column on the right.

**Transfer:** Show a genuinely useful comparison and expose measurement context; compact numeric annotation is more characteristic than oversized stat tiles.

### Colored testimony track

**Observed:** A restrained section title and Outlined button sit above a horizontal Proof-track. Small previous/next controls align at the title edge. Colored Proof cards extend beyond the right viewport boundary, leaving room below for their long soft shadows.

**Transfer:** Use the same printed-grid material for trustworthy practitioner testimony in the new domain.

### Objection handling

**Observed:** A muted section label occupies the narrow left column beside a wide FAQ question list. Product-detail variant pairs striped monochrome artwork on the left with plus/minus FAQ controls on the right.

**Transfer:** Write practical questions that resolve implementation or buying uncertainty; choose the broad narrative or compact technical variant to suit the page.

### Atmospheric closing call

**Observed:** A 1296px × 604px Closing atmosphere returns to the opening visual world. White 36px copy sits around the vertical center of the left area, with orange and outlined actions below; a large hazy luminous object occupies the right.

**Transfer:** Restate the promise in a few words and return to the signature light field; this is a conversion stage rather than a second feature explanation.

**Text style:** `closing-title` — gerstnerProgramm 500 · 36px/1.111

### Ruled directory and relief ending

**Observed:** After 80px of entrance space, a white ruled directory uses a broad contact-and-updates block plus slim grouped link columns. Deep blank space separates this from the bottom social/status and legal line. The white folio then reveals Terminal striped relief across the full browser width. Product-detail, editorial and comparison pages also use this ending even when they omit the atmospheric closing call.

**Transfer:** Scale the directory to the new information architecture while preserving its wide left block, narrow link columns and dark patterned afterimage.

### Comparison and conversion

**Only for:** pricing pages

**Observed:** A compact heading leads into a wide ruled comparison table with alternating Comparison wash rows. An enterprise support band, a compute/cost selector and another factual table deepen the decision. The closing is a two-column offer: compact text and utility actions plus monochrome striped artwork on the left, a secondary incentive and outlined action on the right.

**Transfer:** Use precise comparable facts and explicit units, then offer self-service and assisted paths rather than imposing a generic three-plan card layout.

### Continuous-paper editorial

**Only for:** editorial manifesto pages

**Observed:** One centered Continuous paper artifact begins beneath navigation and carries the full argument. Numbered 12px mono paragraphs run in a narrow inner column with 30px chapter gaps; tiny metadata and a bottom stamp complete the document before the standard directory and relief ending.

**Transfer:** Use for a focused editorial argument, preserving the contrast between a long physical sheet and the airy surrounding canvas.

**Text style:** `paper-text` — ftSystemMono 400 · 12px/1.333 · tracking -0.02em

## Page flow

**Storyline:** Promise → working example → capability explanations → credible proof → practical adoption or buying details → objection handling → action or directory → patterned afterimage.

### Broad platform marketing

1. **Promise** — Modest headline and actions above an expansive atmospheric product stage.
2. **Social proof** — A centered introduction to trusted users and a restrained logo field.
3. **Capability chapters** — Industry/example selector, alternating feature vignettes, art-led inventory and architecture explanation.
4. **Measured and practitioner proof** — A technical benchmark with methodology, followed by colored testimony and trust credentials.
5. **Adoption** — Cost control, setup prompt and integration availability.
6. **Objection handling and closing** — FAQ, blue atmospheric conversion stage, ruled directory and dark striped relief.

**Transfer:** Adapt the number and order of capability chapters to the new product; preserve contrasts between working demonstrations, evidence and calm narrative space.

### Detailed technical product landing

1. **Promise and demonstration** — Category label, compact headline with orange changing word, actions and broad pale workflow illustration.
2. **Capability chapters** — Black/gray heading pairs alternate with workflow diagrams and interface fragments.
3. **Quantified proof** — Large dot-field benchmark and narrow methodology column.
4. **Implementation** — Flexible output demonstrations and a dark code panel beneath a compact instructional heading.
5. **Trust and objection handling** — Field-level validation explanation, use-case selector and FAQ paired with striped artwork.
6. **Ending** — Standard directory and striped relief, without a repeated blue call-to-action stage.

**Transfer:** Center the page on how the specific tool works and is implemented, not on repeating every platform-level chapter.

### Editorial company or product philosophy

1. **Argument** — A single long tractor-feed paper artifact with small metadata and numbered monospaced paragraphs.
2. **Resolution** — Closing prose and an understated location/date stamp on the paper.
3. **Ending** — Ruled directory and full-width dark striped relief.

**Transfer:** Use a coherent written thesis as the main object; the document's physicality replaces product demonstrations.

### Pricing and procurement decision

1. **Commercial promise** — Small label, restrained heading and gray support introducing usage pricing.
2. **Comparison** — Wide ruled table with functional descriptions, highlighted outputs, units and per-column actions.
3. **Assisted path** — Enterprise support band with a compact demo action.
4. **Cost explanation** — Selector/slider and detailed striped pricing table.
5. **Conversion** — Two-column self-service and incentive offers with monochrome striped art.
6. **Ending** — Standard directory and dark patterned relief.

**Transfer:** Retain factual comparison and cost transparency, adapting columns and units to the new offer.

## Writing

Confident, technically literate and direct. The tone makes ambitious claims in practical terms, then explains the mechanism, cost or verification behind them.

**Do not copy:** Do not reuse the brand name, wordmark, proprietary artwork, customer logos, testimonials, performance claims, benchmarks, credit offers or numerical allowances. Source examples illustrate syntax and tone, not content to transplant.

- **Addressing the reader:** Use 'you' and 'your' for workflows and outcomes. Refer to the product by its name when explaining mechanisms; use 'we' sparingly for commitments and methodology.
- **Rhythm:** Headlines are often 3–9 words, followed by one explanatory sentence or a short paragraph. Use parallel verbs and compact clauses; avoid exclamation marks and sprawling promotional introductions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact destination or outcome statement rather than a slogan full of adjectives. | 4–8 words | “Where agents find answers” |
| Supporting line | Name the infrastructure or mechanism, then use a parallel verb sequence to establish breadth. | 12–22 words | “Web infrastructure for AI to search, extract, monitor, and reason over the world's information” |
| Feature heading | State a concrete advantage with a short operational phrase. | 3–8 words | “Designed to compose”<br>“More signal per token” |
| Commercial heading | Use a terse contrast to clarify the charging model or trade-off. | 4–8 words | “Pay for answers, not tokens”<br>“Scale with predictable cost” |
| Action | A short verb plus destination or task; visible capitalization is handled by Control typography. | 1–5 words | “Start building for free”<br>“Create a task” |
| Implementation heading | A sequence of terse operational verbs. | 3–5 words | “Program, run, repeat” |

**Words and phrasing to use:** built for; structured; repeatable; production-grade; programmable; confidence; per request; workflow; scale; real-time

**Avoid:** magical; game-changing; revolutionary solution; supercharge everything; effortlessly transform your world

**Rules:**

- Tie an advantage to a mechanism: explain what the product does differently and what that changes for the user.
- Express trade-offs in plain operational terms such as speed, depth, quality and cost.
- When presenting proof, include units, conditions and methodology rather than leaving a claim unsupported.
- Use a gray continuation line to qualify a short headline instead of packing every detail into the headline.

## Do's and Don'ts

### Do

- Keep the opening headline at 36px medium with normal tracking, and let the media stage provide the scale.
- Use 48px structural gutters/gaps and 24px inner section insets at desktop.
- Pair 26px feature headings with 16px/24px gray explanatory text.
- Make controls 34px tall with 4px corners and 13px uppercase monospace labels.
- Concentrate saturated color in framed media, selected marks and proof cards while leaving narrative sections white.
- Include a tactile striped illustration and an expansive soft blue atmosphere, with original geometric alternatives when needed.
- Use fine 1px gray vertical divisions in footer and comparison layouts.
- End the folio with the dark striped relief after the spacious white directory.

### Don't

- Do not use weight 700 grotesk headlines to manufacture hierarchy; reserve bold mono for compact prices.
- Do not turn 34px equipment-like actions into tall pill buttons.
- Do not use a pure black background for ordinary narrative sections; charcoal belongs to utility actions and terminal art.
- Do not apply the proof-card grid across the entire white canvas.
- Do not give every capability an enclosing bordered card; overview titles and descriptions sit outside their art panel.
- Do not make all images glossy 3D objects; the imagery combines blur, grain, printed bars and simplified interface fragments.
- Do not enlarge prices into giant billboard figures; comparisons use 16px bold mono amounts.
- Do not import the continuous-paper metaphor into an ordinary feature landing page; it is an editorial variant.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color/background/border/scale transitions with cubic-bezier(0,0,.2,1); the opening orange action uses 0.15s and outlined/utility actions use 0.4s. Active scale is 0.98.
- FAQ color transition is 0.15s. Proof cards declare shadow and transform transitions of 0.35s with cubic-bezier(.3,.7,.2,1).
- Declared ambient behaviors include a 48s linear marquee, a 1.1s step-end blinking cursor and a 4s tab-progress cycle.

**Transfer:**

- Keep interaction motion small and instrument-like; preserve pressed scale and compact tab progress rather than animating large marketing text.
- Use slow ambient movement for signal fields or the atmosphere so the foreground workflow remains readable.

**Unknown:**

- The full choreography and timing of video media and scroll entrances are not established.

### Responsive

**Observed:**

- Desktop navigation is declared visible at widths of at least 1160px.
- The opening stage declares a portrait 1:1.5 aspect before the medium breakpoint and a 1336:583 aspect at the medium breakpoint.
- Editorial paper padding declares 28px on narrow screens and 32px at medium widths; its inner content starts after 50px on narrow screens versus 120px at medium widths.

**Transfer:**

- On narrow pages, preserve the opening's white headline area above the atmospheric object and stack controls without changing their compact silhouette.
- Stack the narrow feature narrative before its broad media stage; keep the striped material legible rather than shrinking the entire desktop illustration.
- Keep the paper artifact centered and its feed holes visible while allowing the prose column to fit the available width.

**Unknown:**

- Rendered mobile layouts, exact breakpoint mappings for all grids and narrow comparison-table behavior are not established; stacking guidance is a design recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
