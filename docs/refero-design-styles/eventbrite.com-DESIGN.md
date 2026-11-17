# Eventbrite — human energy, practical tools

## Overview

An upbeat, approachable marketing style that pairs warm off-white space with bursts of orange, pink and pale lime. Sturdy grotesk typography and compact pill actions make substantial product explanations feel direct rather than technical. Candid people photography and colorful interface collages bring social energy to otherwise orderly, moderately spacious layouts.

### Essentials

- A loud promise inside a calm inset stage: uppercase 57.6px/1.1 weight-600 headlines sit in a 16px-radius off-white panel, surrounded by a pink-to-orange gradient frame.
- Human outcomes share the stage with the product: a square image takes roughly half the opening panel, balanced against left-aligned copy and paired 48px-high actions. Use a candid customer-in-context photograph when no polished product artwork exists.
- Conversion looks like a small, solid lozenge, not a billboard: black primary and translucent gray secondary pills use 15px/1.33 weight-500 text, 12px 20px padding and a 16px pairing gap; orange pills concentrate in the 60px white navigation.
- Color is concentrated at moments of energy: most of a long page stays #f5f5f0 and white, while the opening frame and contained media carry saturated gradients. Preserve the gradient-framed stage and at least one colorful product-media panel rather than washing every section in color.
- Product proof is staged like a poster: square 400px or 514px panels hold oversized phones or overlapping white interface cards against orange-to-lime or orange-to-pink backing, followed by grounded, left-aligned explanations.
- The closing invitation returns to people rather than a giant slogan: a 48px sentence-case heading, short support line and paired pills face a 648px square photograph on off-white, immediately followed by a warm stone directory footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange | `#f05537` | `--color-orange` | action, accent | Small high-visibility navigation actions and fine accents; distinct from the brighter gradient endpoint. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Festival orange | `#ff5010` | `--color-gradient-orange` | background, accent | Bright right-hand endpoint of the opening gradient and a recurring product-art color. |
| Soft electric pink | `#ffbae9` | `--color-pink` | background | Left-hand endpoint of the default opening gradient; also a product-art backing color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#161719` | `--color-ink` | text, action | Headings, body emphasis, icons and primary action fills. |
| Slate body | `#3d3f43` | `--color-body` | text | Supporting paragraphs in capability rows and cards; also the active dark action fill. |
| Gray pill wash | `#e4e5e6` | `--color-secondary` | surface, action | Visible 20% #7a7c81 on white; secondary actions use that translucent gray over the local surface. |
| Soft hairline | `#e8e8e7` | `--color-rule` | border | Visible result of rgba(25,22,19,0.1) on white; use the alpha recipe for dividers so it adapts to warm surfaces. |
| Warm stone | `#eceae3` | `--color-footer` | background | Directory footer, slightly deeper than the main canvas. |
| Warm off-white | `#f5f5f0` | `--color-canvas` | background, surface | Default marketing canvas and quiet inset panels. |
| White | `#ffffff` | `--color-white` | surface, text, background | Inset content panels, navigation and reversed action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| feature openings and quantified proof bands | Pale lime | `#f0f9d8` | `--color-lime` | background | Counterweight to orange in proof bands and feature-page openings. |
| discovery portals | Deep violet | `#1e0a3c` | `--color-portal-ink` | text, background | Discovery headings, photographic-card overlays and the dark directory footer. |
| comparison sections | Muted slate | `#696c71` | `--color-muted` | text | Comparison-table labels and qualifications. |
| discovery portals | Cool discovery shelf | `#f8f7fa` | `--color-portal-canvas` | background | Browse and destination shelves, distinct from the warm marketing canvas. |

## Typography

- **Founders Grotesk R** — All marketing headings, prose, navigation and actions. A sturdy, compact grotesk with blunt uppercase shapes and personable lowercase forms; the same family carries bold promises and utilitarian detail. If unavailable, use **DM Sans**. Use weights 400–600; preserve compact line breaks and near-neutral tracking. Font stack: "Founders Grotesk R", "DM Sans", -apple-system, system-ui, Roboto, Helvetica Neue, Helvetica, Tahoma, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| quote-mark | Founders Grotesk R | 900 | 96px | 1 | normal | Oversized opening quotation mark in testimonial cards. |
| display | Founders Grotesk R | 600 | 57.6px | 1.1 | -0.0017em, uppercase | Main promise, left-aligned in the default two-column stage; centered in a text-only pricing opening. |
| heading | Founders Grotesk R | 500 | 48px | 1.1 | -0.002em | Section headings and closing invitations, normally sentence case. |
| card-heading | Founders Grotesk R | 500 | 24px | 1.1 | normal | Feature, resource and editorial card titles. |
| quote | Founders Grotesk R | 400 | 24px | 1.5 | 0.004em | Testimonial text. |
| lead | Founders Grotesk R | 400 | 21px | 1.33 | 0.005em | Hero support and section introductions. |
| subheading | Founders Grotesk R | 500 | 21px | 1.25 | normal | Capability-row titles and sentence-case eyebrows immediately above section headings. |
| body | Founders Grotesk R | 400 | 18px | 1.33 | 0.0056em | Detailed explanations in split capability sections. |
| question | Founders Grotesk R | 500 | 18px | 1.25 | normal | Accordion questions and footer group headings. |
| card-body | Founders Grotesk R | 400 | 15px | 1.33 | 0.007em | Compact card explanations. |
| action | Founders Grotesk R | 500 | 15px | 1.33 | 0.01em | Buttons and inline actions. |
| directory | Founders Grotesk R | 400 | 15px | 1.33 | 0.013em | Footer links and breadcrumbs. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quantified proof sections | metric | Founders Grotesk R | 600 | 96px | 1 | normal, uppercase | Large centered quantitative proof. |
| quantified proof sections | metric-label | Founders Grotesk R | 600 | 32px | 1 | normal, uppercase | Label directly under each large metric, without a vertical gap. |
| discovery portals | browse-heading | Founders Grotesk R | 600 | 24px | 32px | 0.0104em | Compact shelf headings in deep violet. |

**Notes:**

- Use uppercase for the opening promise and large metric labels, not for all section titles. Section headings are nearly as prominent as the hero but lighter and sentence case.
- Tracking remains almost neutral: -0.1px for large headings and slight positive tracking for prose and actions. Do not imitate a tightly compressed display face.
- A 21px lead is distinct from 18px explanatory prose and 15px card prose; use these changes to manage density instead of shrinking all text.

## Layout

**Density:** Airy at section scale, compact within practical feature lists and navigation.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Navigation action gaps and small icon relationships. |
| 12px | Directory link gaps and action vertical padding. |
| 16px | Paired-action gap and card heading-to-copy rhythm. |
| 24px | Grid gutters, lead offset below headings, and capability-row separation. |
| 32px | Small feature-card inner padding. |
| 40px | Support block to action row. |
| 48px | Outer section inset, large card padding and heading-block to main content gap. |
| 80px | Capability-panel inner padding and major split-column gap. |

### Containers and grids

- **marketing frame**: max width 1440px · side padding 48px. Center the overall composition; inset primary panels by 48px on desktop, leaving 1344px for their outer width.
- **split stage**: 2 columns · gap 24px. Balanced copy and square media in the opening and final invitation. Vertically center the copy against the image.
- **capability split**: 2 columns · gap 80px. A 514px square illustration opposite a wider explanatory list, inside 80px panel padding.
- **three-card grid**: 3 columns · gap 24px. Three 400px-wide media-led benefits in a 1248px inner content span.
- **compact capability grid**: 4 columns · gap 24px. Four 318px cards across the wider 1344px section span.
- **directory container**: max width 1280px · 3 columns · gap 24px. Three columns of grouped footer links, with several short groups stacked within each column.
- **discovery container** (only for discovery portals): max width 1272px · 4 columns · gap 0px. Four listing cells, each with 16px inset around a 286px-wide image and details.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | major inset panels | 16px |
|  | cards and media | 8px |
| discovery portals | destination image tops | 40px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| comparison sections | raised comparison column | `rgba(25, 22, 19, 0.06) 0px 0px 0px 1px, rgba(25, 22, 19, 0.03) 0px 4px 12px 0px, rgba(25, 22, 19, 0.06) 0px 8px 16px 0px, rgba(255, 255, 255, 0.09) 0px 1px 0px 0px inset` | Subtle continuous lift on the highlighted comparison column, not on ordinary feature cards. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default long-form marketing background.

**CSS:** `background: #f5f5f0`

**Observed:** Broad untextured warm fields alternate with inset white panels.

**Transfer:** Let the neutral canvas occupy most of the page.

#### White inset panel · level 1

**Use:** Group substantial capabilities, resources or comparisons.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 48px; box-shadow: none`

**Observed:** A flat panel separated by fill rather than a visible outline. Some detailed split panels increase inner padding to 80px.

**Transfer:** Use one panel around a meaningful chapter, not a nested card around every paragraph.

#### Gradient opening frame · level 0

**Use:** Signature energetic surround for the first impression.

**CSS:** `background: linear-gradient(270deg, #ff5010 0%, #ffbae9 100%); padding: 152px 48px 48px`

**Observed:** The color shows as a broad top band and narrow side and bottom frame around the off-white stage.

**Transfer:** Keep the interior calm so the color feels like an invitation rather than a reading surface.

#### Stone footer · level 0

**Use:** Concluding directory and practical navigation.

**CSS:** `background: #eceae3; padding: 32px 48px`

**Observed:** Warm, flat and darker than the body canvas; contains black links, social circles and repeated actions.

**Transfer:** Make this a useful end matter region rather than a dramatic dark conversion banner.

#### Lime-orange proof field · level 0

**Only for:** feature openings and quantified proof bands

**Use:** Full-width numeric proof or a direct feature opening.

**CSS:** `background: linear-gradient(270deg, #ff5010 0%, #f0f9d8 100%)`

**Observed:** A simple edge-to-edge horizontal color transition, with black typography rather than reversed white text.

**Transfer:** Use a single broad color sweep, not a mesh of many glows.

#### Cool browse shelf · level 0

**Only for:** discovery portals

**Use:** Discovery shelves and related browse links.

**CSS:** `background: #f8f7fa; padding-top: 80px`

**Observed:** Cool pale gray supports imagery and dense white browse chips.

**Transfer:** Keep this variant separate from warm product storytelling.

## Components

### Primary button

**Use:** Main conversion action in content.

**CSS:** `background: #161719; color: #ffffff; border: 2px solid #161719; border-radius: 9999px; padding: 12px 20px; height: 48px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Founders Grotesk R 500 · 15px/1.33 · tracking 0.01em

**Observed:** Content-width lozenge; usually paired with a gray secondary action. Text stays compact and centered.

**States:** Declared: hover background and border #25272b with white text; focus-visible box-shadow 0 0 0 2px #f5f5f0, 0 0 0 4px #161719; active background and border #3d3f43.

### Secondary button

**Use:** Sales contact, further information and lower-priority downloads.

**CSS:** `background: rgba(122, 124, 129, 0.2); color: #161719; border: 2px solid rgba(0, 0, 0, 0); border-radius: 9999px; padding: 12px 20px; height: 48px`

**Text style:** `action` — Founders Grotesk R 500 · 15px/1.33 · tracking 0.01em

**Observed:** Filled translucent gray rather than an outlined ghost. Sits beside the black action with equal height; navigation uses a 40px-high variant.

**States:** Declared: hover gray alpha increases to 0.3 and text becomes #25272b; focus-visible box-shadow 0 0 0 2px #f5f5f0, 0 0 0 4px #161719; active gray alpha increases to 0.4 and text becomes #3d3f43.

### Orange navigation button

**Use:** High-visibility conversion within the navigation.

**CSS:** `background: #f05537; color: #ffffff; border: 2px solid #f05537; border-radius: 9999px; padding: 12px 20px; height: 40px`

**Text style:** `action` — Founders Grotesk R 500 · 15px/1.33 · tracking 0.01em

**Observed:** Shorter than content actions; two orange actions can flank a gray contact action in the right-hand navigation cluster.

**States:** Declared: hover retains orange fill and border with white text; focus-visible box-shadow 0 0 0 2px #f5f5f0, 0 0 0 4px #161719; active retains orange fill and border.

### Marketing navigation

**Use:** Persistent orientation above long marketing pages.

**CSS:** `background: #ffffff; height: 60px; padding: 8px 24px; display: flex; align-items: center`

**Text style:** `action` — Founders Grotesk R 500 · 15px/1.33 · tracking 0.01em

**Observed:** Fixed at the top. A compact orange identity sits at left, short category links follow, and conversion pills cluster at the far right. Breadcrumbs belong below the bar rather than inside it.

**Transfer:** Use a concise identity and a few useful categories; preserve the low white bar and compact action cluster.

### Inline arrow link

**Use:** Editorial and capability detail actions.

**CSS:** `color: #161719; display: flex; align-items: center`

**Text style:** `action` — Founders Grotesk R 500 · 15px/1.33 · tracking 0.01em

**Observed:** Text followed by a small right-facing chevron, without a colored fill or resting underline.

**States:** Declared: hover color #25272b; focus-visible color #3d3f43, box-shadow 0 0 0 2px #161719 and 2px radius; active color #3d3f43.

### Compact capability card

**Use:** A short title, explanation and action in a row of related tools.

**CSS:** `background: #f5f5f0; border-radius: 8px; padding: 32px; display: flex; flex-direction: column; gap: 24px; max-width: 700px`

**Text style:** `card-heading` — Founders Grotesk R 500 · 24px/1.1

**Observed:** Heading and body form an upper group; the action is held at the bottom across equal-height siblings. The resource variant reverses the fill to white on the warm canvas.

**Transfer:** Keep explanations in card-body type and use a secondary pill or inline arrow link appropriate to the section.

### Testimonial card

**Use:** Human proof between capability chapters.

**CSS:** `background: #f5f5f0; border-radius: 8px; padding: 48px; display: flex; flex-direction: column; gap: 24px; max-width: 700px`

**Text style:** `quote` — Founders Grotesk R 400 · 24px/1.5 · tracking 0.004em

**Observed:** Large quote-mark type starts the card; a roomy quote follows, then a small circular identity image and attribution. Two cards sit across a white band with a 48px gutter.

**Transfer:** Use actual customer language; keep the mark visibly larger than the quote rather than adding decorative stars.

### Question row

**Use:** Accordion-based objection handling.

**CSS:** `height: 96px; border: 1px solid rgba(0, 0, 0, 0); border-radius: 8px`

**Text style:** `question` — Founders Grotesk R 500 · 18px/1.25

**Observed:** A full-width question trigger aligns the text left and a small downward chevron right. Thin horizontal dividers separate consecutive rows. The surrounding section can be warm canvas or a white inset panel.

**Transfer:** Use full-sentence questions and keep the collapsed rows visually plain.

### Directory link

**Use:** Grouped navigation in the footer.

**CSS:** `color: #161719`

**Text style:** `directory` — Founders Grotesk R 400 · 15px/1.33 · tracking 0.013em

**Observed:** Simple unboxed text links in vertical groups, under question-weight headings, separated by 12px gaps.

**States:** Declared: focus-visible 2px radius, box-shadow 0 0 0 2px #eceae3, 0 0 0 4px #161719, and underline.

### Comparison cell

**Only for:** comparison sections

**Use:** Decision-support tables with a highlighted own-product column.

**CSS:** `border-bottom: 1px solid rgba(25, 22, 19, 0.1); padding: 24px 12px; max-width: 580px`

**Observed:** Wide left feature labels face centered provider columns; rows use prominent black checks and dashes. The featured column is white with a continuous soft shadow and rounded top and bottom corners; the rest stay flat.

**Transfer:** Highlight one column without turning the whole table into separately floating cards.

## Imagery and graphics

### Candid human square

**Use:** Default opening image and the closing invitation; also audience-oriented benefit stories.

**Observed:** People are caught enjoying a shared activity rather than formally posing. The opening uses bright natural light and warm skin tones; the ending can use club color, red neon or purple haze. Square photographs occupy about half the split stage, with 8px corners and no heavy frame or text overlay.

**Transfer:** Photograph customers experiencing the real-world benefit of the new product, with eye-level proximity, expressive faces and believable context. If product artwork is unavailable, this people-led square remains the primary opening object.

### Color-backed product posters

**Use:** Concrete product demonstrations within capability chapters and media-led benefit grids.

**Observed:** Phones are enlarged until they almost fill or extend beyond a square panel; floating white interface cards overlap in shallow layers, sometimes slightly rotated. Backings move from vivid orange at the top to pale lime or pink below; some artwork uses violet-blue above pale lime. Soft local shadows separate white UI from the backing, while the marketing panel itself stays flat.

**Transfer:** Show one recognizable task or outcome per poster, not a full unreadable dashboard. Minimum version: a clean white interface card with one meaningful image or chart on the same saturated-to-pale square backing.

**Build:** Use a square clipped container with 8px corners and a vertical linear gradient from #ff5010 to #ffbae9, or from #ff5010 to #f0f9d8. Center a phone silhouette at about 80% of panel height, or overlap three white UI cards with 12–24px offsets and small opposing rotations. Apply a restrained soft shadow to the foreground objects only; allow one phone to be clipped at the panel bottom.

### Energetic gradient frame

**Use:** The signature surround to the opening stage.

**Observed:** A smooth horizontal pink-left to orange-right gradient remains visible outside a large off-white rounded panel. It is graphic and flat, without grain, blur blobs, light streaks or 3D depth.

**Transfer:** Preserve the contrast between a colorful invitation and a neutral readable interior for any product category.

**Build:** Paint a full-width wrapper with linear-gradient(270deg, #ff5010 0%, #ffbae9 100%). Add 48px side and bottom padding, reserve the upper band for navigation clearance and breadcrumbs, and place a #f5f5f0 panel with 16px corners above it.

### Editorial thumbnails

**Use:** Learning resources and audience-specific offerings.

**Observed:** Authentic performance, food, crowd and community photographs use square framing in horizontal offering cards and 2:1 framing in three-column editorial grids. Images retain varied local color rather than a uniform duotone.

**Transfer:** Use real situations tied to the resource's benefit, maintaining strong subject recognition at small sizes.

### Discovery destination cards

**Only for:** discovery portals

**Use:** Horizontal browse carousel.

**Observed:** 336px-wide landscape images show scenic cities with a 40px rounded top, square lower corners, white 32px names near the lower left and an 8px orange baseline. The last card fades under an edge mask.

**Transfer:** Use a vivid location or category image, retain the bottom orange rule and legible white label without tinting the entire image purple.

**Build:** Clip a landscape photograph into a container with border-radius:40px 40px 0 0. Add a lower dark transparent gradient for white text contrast, pin the label near the lower left, and add an 8px #f05537 strip across the bottom. Mask the overflow edge of the carousel with a fade to its local canvas.

### Icons

**Observed:** Small monochrome filled SVG symbols accompany actions at 16px or 20px; chevrons are simple and unobtrusive. Comparison tables use large confident black checks and dashes. Discovery category symbols are larger, around 48px, inside thin circular outlines.

**Transfer:** Choose simple solid utility symbols in the surrounding text color. Keep playful category illustration confined to browse interfaces; avoid a multicolor icon on every marketing paragraph.

## Section recipes

How recurring sections are built.

### First screen: Gradient-framed human opening

**Observed:** A fixed 60px white Marketing navigation sits above a broad pink-to-orange field. Breadcrumbs sit within the upper color band. An off-white 16px-radius panel is inset 48px from the sides, beginning below that band and using 48px internal padding. Two balanced columns place the uppercase display promise at left and a 612px square candid photograph at right, with a 24px gutter. The text is vertically centered against the image: a strong multi-line headline, 24px to the lead, then 40px to paired Primary button and Secondary button. Within the first 900px the navigation, breadcrumbs, headline, support, actions, entire square image and nearly the whole colored surround are visible; the next capability chapter starts below the fold.

**Transfer:** Use this as the default marketing opening. Change the promise and photograph to the new product's customer outcome, maintaining equal visual weight between words and image. A feature-detail opening can put copy and a square product poster directly on a lime-to-orange field, with paired download actions. A pricing opening uses a centered text-only promise on warm canvas, allowing the first inset benefit panel to enter the first screen.

**Avoid:** Do not replace the square people image with a tiny floating device in an otherwise empty panel, or stretch the hero into a dark full-bleed cinematic masthead.

**Text style:** `display` — Founders Grotesk R 600 · 57.6px/1.1 · tracking -0.0017em · uppercase

### Centered section heading pair

**Observed:** A heading in heading type sits above a lead with 24px separation. A sentence-case subheading eyebrow can sit directly above the title without a separate gap. Optional actions follow after 40px; the main grid or split follows after 48px.

**Transfer:** Introduce one benefit chapter with a short promise and one explanatory sentence; keep the alignment centered even when the detailed content below is left-aligned.

**Text style:** `heading` — Founders Grotesk R 500 · 48px/1.1 · tracking -0.002em

### Split capability chapter

**Observed:** A centered section heading pair leads into a two-column composition with an 80px gap: a 514px square Color-backed product poster and a vertically centered stack of three capability explanations. Each item has a subheading, body paragraph, and thin divider before the next item. The chapter alternates between Warm canvas and White inset panel; media placement can reverse.

**Transfer:** Group related functions under one outcome. Alternate image placement or surface only when it helps pacing, rather than producing endless identical cards.

### Media-led benefit grid

**Observed:** Three 400px square posters sit in a 24px-gutter grid. Each image is followed after 24px by a card-heading and after 16px by card-body prose. A white inset panel contains the group; a centered introduction and compact action may precede it.

**Transfer:** Give each poster a distinct task while using the same backing and framing language. For editorial resources use 2:1 photographs instead of square product art.

### Human proof pair

**Observed:** A centered heading leads into two Testimonial cards across a white band. The oversized quote mark and roomy quote type provide the main graphic weight; compact circular identity pictures anchor the attribution row.

**Transfer:** Use two concise, credible customer outcomes with enough visual breathing room to interrupt denser capabilities.

### Monumental numeric proof

**Observed:** Three centered metric blocks span the width. Each has a short body-sized preface, 96px metric and a 32px uppercase metric-label without a gap. It appears either on Warm canvas or on Lime-orange proof field, with a centered heading and optional actions.

**Transfer:** Use relevant verified numbers for the new product. Keep the digits typographically dominant and the units terse; this device can occur wherever scale or trust needs emphasis.

**Text style:** `metric` — Founders Grotesk R 600 · 96px/1 · uppercase

### Decision and objections

**Observed:** A comparison table within a White inset panel uses Comparison cells and a single softly raised column. A separate question section uses Question rows, a centered heading, and 48px between the title block and list.

**Transfer:** Keep comparison proof and questions distinct so each can be scanned quickly. Use plain labels and only meaningful decision criteria.

### Human closing invitation

**Observed:** A 744px-tall warm band contains 48px outer padding and two columns with a 24px gap. The left text is vertically centered, with a short 48px heading, 21px lead and paired actions. A 648px square Candid human square fills the right. It ends directly against Stone footer rather than another promotional stripe.

**Transfer:** Close on the desired human experience and a concise action invitation, not a feature recap. Use an authentic person or group enjoying the outcome, in natural or colorful contextual light.

**Text style:** `heading` — Founders Grotesk R 500 · 48px/1.1 · tracking -0.002em

### Useful directory ending

**Observed:** Stone footer uses three broad columns of stacked link groups, then paired actions at left and five 40px social circles at right. A fine divider precedes small utility links and copyright; a compact identity sits at bottom left and a locale pill at bottom right. The discovery variant instead uses a deep-violet footer with four compact link columns and a dense utility row.

**Transfer:** End with useful pathways and account or locale controls. Keep the warm three-column version for ordinary marketing pages; reserve the denser dark version for discovery portals.

### Discovery browse opening and shelves

**Observed:** A wide inset photographic campaign banner carries short stacked colored headline strips and a white pill action. Eight circular category symbols follow; a compact location heading and underlined tabs lead into a four-column listing grid. Lower shelves use scenic destination cards, white browse chips and a cool gray canvas.

**Transfer:** For a marketplace, open with a single seasonal promotion and quickly hand off to browsing. Replace cities, categories and listings with the new catalog's organizing concepts rather than importing the marketing-page display scale.

**Text style:** `browse-heading` — Founders Grotesk R 600 · 24px/32px · tracking 0.0104em

## Page flow

**Storyline:** Outcome promise → concrete capabilities → human or quantified proof → decision support and resources → human closing invitation → useful directory.

### Broad product platform landing page

1. **Promise** — Gradient-framed split stage with a bold uppercase promise and lively customer photograph.
2. **Capability chapters** — Alternating neutral split sections explain ease of use, reach and operational outcomes through product posters and short divided lists.
3. **Breadth** — Compact tool cards and audience-oriented photo offerings show applicability without changing the visual system.
4. **Social proof** — Paired quotations and a large creator portrait story humanize the benefits.
5. **Decision support** — Editorial resource grid, checklist invitation, tailored-sales split and support cards provide next steps for different levels of readiness.
6. **Closing call** — Warm two-column human-photo invitation flows directly into the stone directory with actions, socials and utility navigation.

**Transfer:** Use the broadest customer outcome to open, then select only the capability chapters and proof needed for the new product.

### Pricing and purchase-confidence page

1. **Promise** — Centered uppercase text-only opening states the accessible entry point on warm canvas.
2. **Value before cost** — Three substantial product posters and feature lists establish included value.
3. **Quantified proof** — A full-width lime-to-orange band carries three oversized metrics.
4. **Pricing** — A white inset split pairs a product collage with plain fee explanations, followed by a sales-support block.
5. **Expansion** — A split add-on explanation and three media-led plan summaries show ways to grow.
6. **Confidence** — Quote pair, highlighted-column comparison table and plain accordion rows answer doubts.
7. **Closing call** — A large joyful human photograph faces a concise invitation, then the full stone directory ends the page.

**Transfer:** Explain entry cost plainly and establish what it buys; use the same airy media rhythm instead of introducing an unrelated pricing-table aesthetic.

### Focused feature and download landing page

1. **Promise** — Direct split hero on a lime-to-orange field balances an uppercase promise with a phone poster and paired download pills.
2. **Product demonstration** — Three square product posters explain concrete uses, followed by a focused comparison table.
3. **Instruction and adoption** — Introductory text beside a video region leads into a divided platform-download split.
4. **Resources and scale** — Three white resource cards and large metrics broaden confidence.
5. **Conversion and objections** — A checklist invitation, tailored-sales photo split and accordion provide alternate routes.
6. **Closing call** — A square colorful crowd photograph anchors the warm final invitation, followed by the same stone directory.

**Transfer:** Keep task explanations more literal than on the platform page and make the acquisition action specific to the feature.

### Consumer discovery marketplace

1. **Campaign hook** — A wide inset live-performance photograph with stacked colored copy strips and a light pill action.
2. **Orientation** — Eight outlined category circles, location selector and underlined time filters.
3. **Catalog discovery** — Four-column listings combine varied 2:1 images, title, urgency badge, date, venue and price.
4. **Broader exploration** — A cool pale shelf carries destination-image carousel and dense browse chips.
5. **Directory ending** — Four compact columns of muted links on deep violet finish with utility navigation and locale selection; there is no extra large closing call.

**Transfer:** Use this denser, cooler scoped variant only when browsing is the primary task, retaining varied imagery and compact hierarchy.

## Writing

Positive, practical and encouraging. The language promises growth or smoother work, then supports it with specific functions, understandable costs and straightforward next steps.

**Do not copy:** Do not reuse Eventbrite names, logos, campaign artwork, customer quotes, proprietary product labels, audience counts, fees or performance claims. Examples illustrate voice only; supply the new product's own substantiated facts and assets.

- **Addressing the reader:** Speak directly to the reader as you and your. Use we and our for helpful support and offerings, and product names when an explanation needs clarity.
- **Rhythm:** Short benefit headings alternate with one- or two-sentence explanations. Main promises can be longer and explicit; card titles stay compact. Actions start with a verb and name the next step.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name the product category and connect it to a desirable outcome. | 8–12 words | “Online Event Management Software to Grow Your Events”<br>“The Event Check In App for a Smooth Guest Experience” |
| Section heading | An active benefit in everyday language, often a compact two-part phrase. | 3–7 words | “Get paid, earn more”<br>“Reach the right people”<br>“Add what you need” |
| Supporting line | Explain how the benefit works with concrete product functions. | One or two sentences | “Grow your community on a marketplace where millions of people look for things to do.”<br>“Our event pricing is simple and flexible. Event ticket fees are paid by your buyers by default, or you can choose to absorb them when you set up your ticket types.” |
| Primary action | A clear verb plus destination or low-friction entry point. | 2–5 words | “Get started for free”<br>“Discover our plans”<br>“Watch the demo” |
| Objection handling | Ask the question a reader would naturally say aloud. | One direct question | “What’s included when I use [Brand]?”<br>“Do you offer special pricing for nonprofits?” |
| Closing invitation | A short, optimistic outcome line with an explanatory support sentence. | 2–6 words for the heading | “Grow eventfully”<br>“Where event organizers grow” |

**Words and phrasing to use:** grow; get started; discover; built-in; all-in-one; tools; support; simple; flexible; your

**Avoid:** disruptive; paradigm-shifting; revolutionize everything; synergy; exclusive elite access; unexplained technical jargon

**Rules:**

- Lead with the benefit, then name the function that makes it believable.
- Use clear costs, limits and practical qualifications when discussing commercial terms.
- Make each card about one concrete job rather than a cluster of abstract advantages.
- Keep lower-priority actions explicit: explore, learn, discover, watch or contact followed by a useful object.

## Do's and Don'ts

### Do

- Keep the opening promise at 57.6px/1.1, weight 600 and uppercase; use 48px/1.1 weight 500 for the next tier.
- Pair 48px black and translucent-gray content pills with a 16px gap.
- Use 48px outer panel insets and 16px panel corners to make the warm canvas visible.
- Give square product posters enough area to read as objects: 400px in grids and 514px in detailed splits.
- Separate three-column media cards with 24px gutters and use 15px supporting prose.
- Keep human photographs large and expressive, especially in the half-width closing invitation.
- Use a single highlighted comparison column with soft layered shadow rather than lifting every column.
- Retain the warm stone directory, 12px link rhythm and compact repeat actions at the end.

### Don't

- Do not use a serif, mono or ultra-condensed face for the main marketing promise.
- Do not substitute outlined rectangular actions for the black and gray 9999px-radius pills.
- Do not promote the orange navigation button into every content action; content primaries are near-black.
- Do not add heavy shadows or thick borders to ordinary 8px-radius feature cards.
- Do not turn the smooth two-color opening gradient into noisy mesh blobs, metallic 3D or neon-glow scenery.
- Do not render all media as full-width cinematic rectangles; the marketing system is anchored by square human and product scenes.
- Do not apply the discovery portal's violet footer and cool shelves to the default warm marketing page.
- Do not shrink proof metrics to ordinary heading size: use 96px digits with 32px uppercase labels when that section is present.

## Motion and responsive

### Motion

**Observed:**

- Declared action and surface transitions include 0.24s cubic-bezier(0.4, 0, 0.3, 1), with other controls using 0.2s.
- Discovery listing cards declare a 0.3s scale-in-left animation with cubic-bezier(0.215, 0.61, 0.355, 1).

**Transfer:**

- Keep the product-marketing stage visually stable; use the declared short transitions for surface and action feedback, not a new cinematic entrance sequence.
- Restrict the listing-card entrance treatment to browse interfaces.

**Unknown:**

- Exact scroll-triggered behavior and timing assignments for individual marketing sections are not established.

### Responsive

**Observed:**

- Marketing styles declare width breakpoints including 600px, 792px, 960px, 1200px and 1280px; the documented composition is desktop.

**Transfer:**

- On narrow screens, preserve the gradient surround and neutral stage as nested layers while reducing their insets; stack promise and square media rather than shrinking the uppercase heading to fit desktop line breaks.
- Let paired actions wrap and keep their lozenge shape. Reduce grid columns while retaining the 24px relationship between related cards.
- For comparisons, preserve provider-to-feature associations rather than compressing every column to illegible width.

**Unknown:**

- Exact mobile typography sizes, padding values, navigation replacement and table reflow are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
