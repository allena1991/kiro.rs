# Modern Treasury — money in fine lines

## Overview

An airy infrastructure aesthetic that makes complex systems feel tangible and approachable. White space, warm porcelain panels, mint markings and a deep forest-green ending surround light grotesk typography and small technical monospace labels. Diagrammatic product vignettes carry the story; natural workplace photography belongs to customer narratives. It suits technical platforms that need both developer credibility and an accessible commercial story.

### Essentials

- Headlines feel like plainspoken architectural signage: light grotesk at 71px/1.1, weight 450, normal tracking; centered two-line openings give way to 47px/1.25 section leads.
- The opening is a diagram stage, not a dashboard billboard: 90px top padding, an 896px headline measure, 672px support measure and paired 40px actions sit above a 1024×370px system illustration.
- Actions are compact rectangular instruments: 2px corners, black fill or 1px inset outline, 16px/24px semibold labels and small right arrows; the paired buttons are separated by 16px.
- Color behaves like an annotation: the main reading field is white, 576px-wide feature panels are warm #f8f5f4, and mint #bae0cf appears in tiny labels and controls rather than broad saturated bands. Deep #0c221d is reserved for the full-width ending.
- Product concepts float on porcelain: white interface fragments, faint connector lines, pale mint or mauve stamps and gentle edge shadows fill the lower half of cards. Every new page needs a fine-line system diagram; use labeled nodes and one meaningful object when no interface artwork exists.
- Proof is restrained and structural: 47px metrics over 16px captions sit between 1px rules, while quotations sit in low tinted horizontal bands rather than oversized quotation typography.
- The ending changes material, not volume: a 623px forest-green footer combines a newsletter row, mint 42px subscribe action, six small link columns and a ruled legal/social baseline.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest | `#0c221d` | `--color-forest` | background | Full-width shared footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Technical green | `#29735c` | `--color-green` | text, link, accent | Selected process states and documentation links. |
| Mint | `#bae0cf` | `--color-mint` | surface, action, accent | Newsletter action and diagram markings; keep concentrated in small objects. |
| Ice wash | `#f0f8f9` | `--color-ice` | surface | Short benefit cards; a pale blue-green wash rather than a saturated section. |
| Lilac mist | `#f9f6f8` | `--color-lilac` | surface | Quote band and compact conversion-call panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#151515` | `--color-ink` | text, action, border | Headings, primary actions and strong outlines. |
| Body charcoal | `#424242` | `--color-body-ink` | text | Visible 0.8-alpha #151515 body text over white; use rgba(21,21,21,0.8) when matching a tinted backing. |
| Muted gray | `#737373` | `--color-muted-ink` | text | Visible 0.6-alpha #151515 on white, used for opening support and technical eyebrows. |
| Soft forest white | `#9ea7a5` | `--color-footer-muted` | text | White at 0.6 alpha on forest for newsletter support and footer links. |
| Light charcoal rule | `#d0d0d0` | `--color-rule` | border | Visible 0.2-alpha #151515 over white; section dividers, metrics and ruled grids. |
| Input gray | `#dcdcdc` | `--color-input-edge` | border | Fine solid input outlines. |
| Warm porcelain | `#f8f5f4` | `--color-porcelain` | surface | Default illustrated capability cards and long product chapters. |
| Warm beige | `#f8f7f5` | `--color-beige` | background, surface | Announcement strip and conversion-form panel; underlying page ground. |
| White | `#ffffff` | `--color-white` | background, surface, text | Default visible reading canvas, interface fragments and inverse text. Navigation uses white at 0.9 alpha. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Clay | `#936c63` | `--color-rate-label` | text | Monospace uppercase rate labels. |
| pricing pages | Blue charcoal | `#152b37` | `--color-navy` | surface | Included-service cards with inverse copy and white diagrams. |
| deep product use-case chapters | Muted plum | `#543b4e` | `--color-plum` | surface | Immersive use-case cards with inverse text and tonal illustrations. |
| customer-story directories | Putty | `#ddd2cb` | `--color-tag` | surface | Small taxonomy labels under story photography. |

## Typography

- **mt-neue-display** — Opening headlines, section leads and large metrics. Open, light neo-grotesk with unforced proportions and round counters. OpenType features: "cv10", "ss07", "ss08". If unavailable, use **Inter**. Use weight 450 and normal tracking; balance lines without condensing. Font stack: "mt-neue-display", "Inter", ui-sans-serif, system-ui, sans-serif.
- **mt-neue-text** — Card titles and intermediate headings. Regular neo-grotesk; broader and calmer than a bold UI heading. OpenType features: "cv10", "ss07", "ss08". If unavailable, use **Inter**. Use weight 400. Font stack: "mt-neue-text", "Inter", ui-sans-serif, system-ui, sans-serif.
- **mt-sans** — Body, navigation, controls and attribution. Low-contrast contemporary sans with light body weights and firm semibold controls. OpenType features: "cv10", "ss07", "ss08". If unavailable, use **Inter**. Retain weights 330, 360, 500 and 600 with a variable font. Font stack: "mt-sans", "Inter", ui-sans-serif, system-ui, sans-serif.
- **mt-mono** — Technical labels, process numerals, taxonomy and code. Compact utilitarian monospace, used in small doses rather than as the main voice. If unavailable, use **IBM Plex Mono**. Font stack: "mt-mono", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | mt-neue-display | 450 | 71px | 1.1 | normal | Default marketing and product opening; balanced over two lines. |
| heading-lg | mt-neue-display | 450 | 47px | 1.25 | normal | Section leads, large metrics and compact editorial or commercial openings. |
| heading | mt-neue-text | 400 | 32px | 1.25 | normal | Illustrated card titles, split feature headings and featured-story titles. |
| heading-sm | mt-neue-text | 400 | 21px | 1.3 | normal | Benefit cards, story titles and FAQ questions. |
| lead | mt-sans | 360 | 18px | 1.5 | normal | Centered opening support and major section explanations. |
| body | mt-sans | 360 | 16px | 1.5 | normal | Capability descriptions, quotations and product explanations. |
| control | mt-sans | 600 | 16px | 1.5 | normal | Medium actions and field labels. |
| small | mt-sans | 330 | 14px | 1.5 | normal | Footer links and small explanatory text. |
| navigation | mt-sans | 500 | 14px | 1.5 | normal | Navigation and announcement copy. |
| small-action | mt-sans | 600 | 14px | 1.5 | normal | Small buttons, card links and footer group headings. |
| eyebrow | mt-mono | 400 | 14px | 1.2 | normal | Product and editorial identifiers above headlines. |
| process-number | mt-mono | 500 | 11px | 1.5 | 0.06em | Small numerals beneath the dots of a lifecycle diagram. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| developer sections | code | mt-mono | 330 | 14px | 1.5 | normal | Readable developer example outside a miniature product interface. |
| customer-story directories | taxonomy | mt-mono | 330 | 12px | 1.5 | normal | Putty category labels below story images. |
| pricing pages | rate-label | mt-mono | 400 | 12px | 1 | 0.04em, uppercase | Short labels above rate figures. |

**Notes:**

- Use distinct light display and regular text-heading roles; semibold is for controls, not large titles.
- Normal tracking is the rule even at 71px. Letter spacing is introduced only in tiny technical markings.
- Body copy is visually lighter than its headings through weight 360 and alpha ink. Center only section introductions; card copy stays left aligned.

## Layout

**Density:** Airy at section scale, compact within technical objects; large blank intervals isolate each capability while 12px text gaps keep cards coherent.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer link rows and compact labels. |
| 12px | Headline-to-description gap and card text stacks. |
| 16px | Paired actions and form row gaps. |
| 20px | Story image-to-metadata gap and card link separation. |
| 24px | Form-panel padding, three-column gutters and support-to-action gap. |
| 32px | Action-to-hero-media gap and horizontal benefit-card padding. |
| 40px | Benefit-card vertical padding and story-directory row gap. |
| 48px | Desktop two-column gutters, illustrated-card text padding and heading-to-grid separation. |
| 60px | Default section top and bottom padding. |
| 80px | Footer opening padding. |
| 90px | Opening top padding and conversion-section bottom padding. |

### Containers and grids

- **content**: max width 1200px · side padding 48px. Centered content for sections, forms and footer; at 1440px the content edges sit 120px from the viewport sides.
- **navigation**: max width 1440px · side padding 32px. Full-width sticky header with brand left, links centered and actions right.
- **opening copy**: max width 896px. Headline measure; narrow support independently to 672px.
- **section introduction**: max width 672px. Centered heading and explanation.
- **illustrated pair**: 2 columns · gap 48px. Equal 576px cards, not an asymmetrical bento.
- **benefits**: 3 columns · gap 24px. Equal 384px short cards.
- **feature matrix** (only for deep product capability sections): 4 columns · gap 24px. 282px ruled feature columns with icons.
- **story directory** (only for customer-story directories): 3 columns · gap 24px. 384px photographic story columns with 40px vertical gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 2px |
|  | cards | 8px |
|  | carousel arrows | 50% |
| customer-story directories | story media | 4px |
| long product chapters | chapter panel | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| control outline | `0px 0px 0px 1px #151515 inset` | Primary and outlined marketing actions. |
| navigation haze | `0px 20px 25px -5px rgba(0,0,0,0.04), 0px 8px 10px -6px rgba(0,0,0,0.04)` | Soft elevation below the sticky header; not a general card shadow. |

### Surfaces

#### Reading canvas · level 0

**Use:** Main marketing content.

**CSS:** `background: #ffffff; color: #151515`

**Observed:** White dominates the visible page; warm beige is a secondary ground rather than the entire reading field.

**Transfer:** Keep long-form content on white.

#### Porcelain card · level 1

**Use:** Illustrated capabilities and product chapter backing.

**CSS:** `background: #f8f5f4; border-radius: 8px; overflow: hidden; box-shadow: none`

**Observed:** The outer shell is flat; elevation belongs to the white objects illustrated inside it.

**Transfer:** Put a simplified product scene in the lower portion.

#### Ice card · level 1

**Use:** Short benefits.

**CSS:** `background: #f0f8f9; border-radius: 8px`

**Observed:** A very pale cool wash distinguishes concise benefits from illustrated capability cards.

**Transfer:** Keep the content brief enough to preserve the low horizontal proportions.

#### Lilac band · level 1

**Use:** Customer quotations and concise conversion calls.

**CSS:** `background: #f9f6f8; border-radius: 8px`

**Observed:** Long horizontal quote panel; compact conversion variation has 16px corners and 48px 32px padding.

**Transfer:** Use for a single persuasive statement, not a miscellaneous content bucket.

#### Form panel · level 1

**Use:** Conversion forms.

**CSS:** `background: #f8f7f5; border: 1px solid rgba(255,255,255,0.2); border-radius: 8px; padding: 24px`

**Observed:** Warm fill distinguishes white controls; no pronounced elevation.

**Transfer:** Keep labels outside and above each input.

#### Navigation glass · level 2

**Use:** Sticky navigation.

**CSS:** `background: rgba(255,255,255,0.9); backdrop-filter: blur(40px); box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.04), 0px 8px 10px -6px rgba(0,0,0,0.04)`

**Observed:** A translucent white strip rather than a floating rounded island.

**Transfer:** Keep the bar edge-to-edge.

#### Forest ending · level 0

**Use:** Shared site footer.

**CSS:** `background: #0c221d; color: #ffffff`

**Observed:** An opaque dark material change after a white breathing interval.

**Transfer:** Use as the principal dark anchor.

#### Plum use-case panel · level 1

**Only for:** deep product use-case chapters

**Use:** Immersive illustrated use cases.

**CSS:** `background: #543b4e; color: #ffffff; border-radius: 8px; overflow: hidden`

**Observed:** Tonal mauve interface fragments and fine pale lines fill the picture region; illustrations and text alternate their vertical order.

**Transfer:** Keep the illustration tonal rather than importing bright dashboard colors.

#### Navy inclusion panel · level 1

**Only for:** pricing pages

**Use:** Included-service explanations.

**CSS:** `background: #152b37; color: #ffffff; border-radius: 8px; overflow: hidden`

**Observed:** White UI fragments contrast against dark blue charcoal, with restrained lists of light text.

**Transfer:** Explain what a buyer receives, without inventing a recommended-plan treatment.

## Components

### Sticky navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: sticky; top: 0px; height: 65px; z-index: 50; background: rgba(255,255,255,0.9); backdrop-filter: blur(40px)`

**Text style:** `navigation` — mt-sans 500 · 14px/1.5

**Observed:** Wordmark left, six central destinations with small chevrons where expandable, then three compact actions. Header actions use 33px height, 6px 12px padding and the small-action recipe; the primary is black.

**States:** Declared: hover navigation-item background rgba(21,21,21,0.05); focus-visible background rgba(21,21,21,0.13).

### Primary button

**Use:** Main conversion in openings and compact calls.

**CSS:** `display: flex; align-items: center; gap: 4px; height: 40px; padding: 8px 14px; border-radius: 2px; background: #151515; color: #ffffff; box-shadow: 0px 0px 0px 1px #151515 inset`

**Text style:** `control` — mt-sans 600 · 16px/1.5

**Observed:** A right arrow follows the label in the default opening. Form submissions use a 42px bordered variant with 8px 16px padding; story actions use the 33px small-action variant.

**Transfer:** Choose one short human conversion verb phrase.

### Secondary button

**Use:** Self-service action alongside the primary.

**CSS:** `display: flex; align-items: center; gap: 4px; height: 40px; padding: 8px 14px; border-radius: 2px; color: #151515; background: transparent; box-shadow: 0px 0px 0px 1px #151515 inset`

**Text style:** `control` — mt-sans 600 · 16px/1.5

**Observed:** An equal visual peer in shape, but without the black fill. Paired actions wrap and are centered.

### Arrow text link

**Use:** Capability navigation within cards.

**CSS:** `display: flex; align-items: center; gap: 4px; color: #151515`

**Text style:** `small-action` — mt-sans 600 · 14px/1.5

**Observed:** Bare semibold label followed by a right arrow. Documentation links use technical green; inverse cards use white.

**Transfer:** Name the destination rather than repeating a generic CTA.

### Illustrated capability card

**Use:** Explain one major capability through copy and a scene.

**CSS:** `display: flex; flex-direction: column; background: #f8f5f4; border-radius: 8px; overflow: hidden`

**Text style:** `heading` — mt-neue-text 400 · 32px/1.25

**Observed:** Title, one short paragraph and Arrow text link sit in a 48px padded upper block. A 576×324px image occupies the lower block. Equal-width pairs have independent content but aligned outer edges.

**Transfer:** Show an outcome with a few legible fragments, not a full application screen.

### Ruled metric

**Use:** Concise quantitative proof.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 24px 0px; border-top: 1px solid rgba(21,21,21,0.2); border-bottom: 1px solid rgba(21,21,21,0.2); text-align: center`

**Text style:** `heading-lg` — mt-neue-display 450 · 47px/1.25

**Observed:** Three equal cells separated by 48px open gutters, each pairing a large numeral or short noun phrase with a body-sized muted caption.

**Transfer:** Mix numbers and a concise qualitative benefit only when each carries distinct proof.

### Conversion field

**Use:** Labeled contact inputs within Form panel.

**CSS:** `height: 42px; background: #ffffff; border: 1px solid #dcdcdc; border-radius: 2px; display: flex; align-items: center`

**Text style:** `control` — mt-sans 600 · 16px/1.5

**Observed:** Labels above inputs use control typography, with a 4px label-to-field gap and 16px between rows. First and last name share a row; remaining fields span the panel. Select controls are 44px high.

**Transfer:** Ask only qualification questions appropriate to the new product.

### Newsletter action

**Use:** Footer subscription.

**CSS:** `height: 42px; padding: 8px 16px; background: #bae0cf; border: 1px solid #bae0cf; border-radius: 2px; color: #151515`

**Text style:** `control` — mt-sans 600 · 16px/1.5

**Observed:** Beside a white email input, with a 16px gap. The form is right aligned opposite a short title and support line.

### Footer link group

**Use:** Dense navigation in the forest ending.

**CSS:** `display: grid; row-gap: 8px; column-gap: 24px; color: rgba(255,255,255,0.6)`

**Text style:** `small` — mt-sans 330 · 14px/1.5

**Observed:** Small-action white group labels lead subdued links; six columns share the desktop container. Longer labels wrap within their column.

**States:** Declared: hover link color #ffffff.

### FAQ row

**Only for:** pricing and objection-handling sections

**Use:** Resolve purchase objections.

**CSS:** `padding: 24px 0px; border-bottom: 1px solid rgba(21,21,21,0.2)`

**Text style:** `heading-sm` — mt-neue-text 400 · 21px/1.3

**Observed:** Full-width question button with 48px right padding and a plus at the far edge; only the first row adds a top rule. Collapsed rows are about 76px high.

**Transfer:** Keep the question complete; do not turn the accordion into separate raised cards.

### Taxonomy tag

**Only for:** customer-story directories

**Use:** Identify a story category.

**CSS:** `display: flex; padding: 2px 8px; background: #ddd2cb; border-radius: 2px; color: #151515`

**Text style:** `taxonomy` — mt-mono 330 · 12px/1.5

**Observed:** A fitted putty label under each photograph, followed by a 21px story title with an 8px gap.

## Imagery and graphics

### Fine-line system stage

**Use:** Signature opening graphic and recurring explanatory diagrams.

**Observed:** A central black square anchors a loose horizontal network. Thin gray orthogonal paths connect pale mint rectangular labels, with occasional green emphasis and extensive white space. Behind the opening, a faint square grid is most visible in the upper-right and fades toward the text. The scene is shallower than the copy stack plus surrounding air.

**Transfer:** Make a central product object connect to the entities it organizes. Even without UI assets, draw one credible system scene with labeled nodes and clear relationships.

**Build:** Use an SVG viewBox of 1024 by 370 with 1px rgba(21,21,21,0.13) paths, rounded 90-degree bends and edge opacity fades. Place a 76px near-black central tile with a simple white product symbol; distribute six to eight mint label rectangles around it. Add a separate 36px square CSS background grid using rgba(21,21,21,0.04), masked to fade from the upper-right toward the center. Keep the labels short and monospace; this is a construction recipe, not a requirement to duplicate the subject.

### Porcelain product vignettes

**Use:** Lower portions of capability cards and split product chapters.

**Observed:** Small white account cards, transaction lists and payment objects float over warm off-white fields. Mint and dusty mauve chips, hairline dividers and subdued text supply detail. Some scenes extend off the card edge or use repeated tiny objects fading into the background. Shadows are soft and localized to objects, never heavy on the enclosing shell.

**Transfer:** Use two or three meaningful interface fragments, with one focal object. The minimum version is a white summary card over fine connectors, a short state list and a small mint symbol.

**Build:** Within a 576×324px illustration area, position one white object around 360px wide with 4px corners and a soft rgba(21,21,21,0.08) shadow. Add thin rgba(21,21,21,0.13) separators, a small mint icon block and 1px connectors to secondary chips. Fade repeated background fragments with an opacity mask; avoid decorative gradients on the focal object.

### Monochrome proof marks

**Use:** Logo strip and customer proof grid.

**Observed:** Black and gray marks centered with generous breathing room; the strip is bounded by fine horizontal rules and soft faded ends. The extended directory is a three-column ruled table with roughly 400×164px cells.

**Transfer:** Normalize visual mass rather than stretching every logo to the same width. Keep the long table confined to a proof-focused page.

### Tonal plum systems

**Only for:** deep product use-case chapters

**Use:** Use-case cards with inverse copy.

**Observed:** Mauve ledger panels, branching paths, account hierarchies and translucent stacked planes sit inside muted plum. White labels are softer than the bright white fragments of the default theme.

**Transfer:** Recast the same product logic in close plum values, keeping the image region distinct from the copy.

**Build:** Use the plum backing, white paths at 0.2 alpha, rectangular white overlays at 0.08–0.15 alpha and white labels at 0.8 alpha. For a stack, draw five shallow rhombi with 10px vertical offsets and a soft white glow at 0.12 alpha; connect three small chips above them with 1px paths.

### Customer photography

**Only for:** customer stories and proof directories

**Use:** Featured story video and editorial story thumbnails.

**Observed:** Natural-light workplaces, consumer activities and hands using devices; wide 384×216px thumbnails have a subtle dark lower gradient with a white customer mark at bottom-left. The feature uses a taller 564×423px video alongside a large wordmark and story title on warm beige.

**Transfer:** Use real customer environments and calm, contextual moments. Place an authorized identity mark over the lower shadow, not a centered marketing headline.

### Icons

**Observed:** Small black 16px navigation chevrons, simple right arrows, 20px inverse carousel arrows and 22px subdued-white social marks. Product feature icons appear as 40px image assets on pale mint squares; developer library icons are 36px.

**Transfer:** Use economical financial or system symbols with consistent simple silhouettes. Put feature symbols on mint tiles, not colorful circular badges.

## Section recipes

How recurring sections are built.

### First screen: Diagram stage opening

**Observed:** A 65px Sticky navigation and 49px beige announcement precede a white opening with 90px top padding. The centered 71px headline is balanced across two lines within 896px; the visible words occupy roughly the central two-thirds of that measure. A 672px, two-line support block follows after 12px, then paired Primary button and Secondary button after 24px. Back-to-front layers are white canvas, faint upper-right grid, text and actions, then the Fine-line system stage. That 1024×370px scene begins 32px below the actions, spreading toward both sides with a black hub and mint labels. Within the first 900px the entire headline, support, actions and diagram are visible; the proof strip begins just below the opening.

**Transfer:** Use a concise two-line promise and diagram the new product's relationships rather than substituting a giant dashboard. Product-specific openings can add a mono eyebrow and replace the network with a code-to-interface scene at 1200×400px. Pricing opens with the 47px recipe, three rates and an early form; story directories use a 47px title and a split featured-story panel.

**Avoid:** Do not let the diagram crowd or overlap the copy, stretch the headline into a single very wide line, or turn the faint right-hand grid into a full-contrast page texture.

**Text style:** `display` — mt-neue-display 450 · 71px/1.1

### Centered heading pair

**Observed:** Heading-lg above a short support line, both centered in a 672px measure. Text gaps range from 16px for body support to 24px for larger lead support; grids follow after 48px. Sections usually use 60px top and bottom padding.

**Transfer:** Give each major chapter one short claim and one clarifying sentence; left-align only when a neighboring demo makes a split composition.

**Text style:** `heading-lg` — mt-neue-display 450 · 47px/1.25

### Capability gallery

**Observed:** Centered lead followed by Illustrated capability cards in a two-column 48px-gutter grid. Short Ice cards use three columns with 24px gutters and 40px 32px internal text padding.

**Transfer:** Separate major illustrated capabilities from short benefits instead of forcing both into one card system.

### Lifecycle demonstration

**Observed:** Centered heading and lead precede a four-stage horizontal process. Tiny tracked mono numerals and 16px semibold labels sit below 16px dots; the selected dot has a thick green ring. A bordered white demonstration panel follows, with a warm 44px toolbar and request/response halves.

**Transfer:** Show the new product's sequence as connected steps, with a selected stage linked to one concrete example. Keep the interface detail subordinate to the chapter explanation.

### Ruled proof and testimonial

**Observed:** Ruled metric cells or a monochrome logo strip establish credibility. A Lilac band then places a logo on the left, body-sized quotation and attribution in the middle, and a small black story action to the right. Circular 32px carousel arrows sit above the band at the right.

**Transfer:** Use specific, verifiable proof in small typographic gestures; a quote should read like practical testimony, not a manifesto.

### Conversion close

**Observed:** Centered heading-lg and brief support lead into a Form panel after 48px. The panel spans the 1200px container; name inputs share a row while other fields stack. The black action aligns left and is separated from the final question by 40px. Section bottom padding is 90px.

**Transfer:** Close a marketing or product page with a practical next step and a form suited to the offering. A proof directory can end with a quote instead; commercial pages can finish with objections.

### Forest newsletter footer

**Observed:** Forest ending spans the page, with a 1200px inner container. The top row has 80px top and 32px bottom padding, short newsletter text left and email plus Newsletter action right. A translucent white rule introduces six Footer link groups padded 48px vertically. Another rule separates legal text on the left from four social icons on the right; the bottom has 24px breathing room.

**Transfer:** Preserve the newsletter-plus-directory structure and dark material across page types, adapting the link taxonomy to the new product.

### Long product chapter

**Only for:** deep product explanations

**Observed:** A single 1200px-wide Porcelain card variation with 16px corners contains four 450px-tall rows. Each row pairs a 600×450px scene on the left with a heading and brief paragraph on the right; the backing remains continuous.

**Transfer:** Use a continuous panel to connect related technical guarantees; preserve the strong text/image halves rather than splitting every row into an independent box.

**Text style:** `heading` — mt-neue-text 400 · 32px/1.25

### Developer workbench

**Only for:** developer sections

**Observed:** Two 576px columns separated by 48px: mono eyebrow, heading-lg, five 57px ruled explanation rows and a green documentation link on the left; a warm code panel on the right. A shallow porcelain shelf underneath holds four white 276×62px library actions.

**Transfer:** Make the code demonstrate the selected task. Use only supported integrations and avoid filling the shelf with unrelated badges.

### Customer proof directory

**Only for:** customer-story directories

**Observed:** Featured-story panel leads to a three-column grid of 16:9 photographs, Taxonomy tag and heading-sm title. A centered 32px heading then introduces a long three-column ruled logo table, followed by a compact quote band before the footer.

**Transfer:** Give stories visual priority and keep the extended mark table as secondary evidence.

**Text style:** `heading-sm` — mt-neue-text 400 · 21px/1.3

### Commercial explanation

**Only for:** pricing pages

**Observed:** A 47px centered opening leads to three rate blocks with 32px figures and tiny uppercase clay labels, divided by vertical hairlines. An 896px form panel is brought into the opening. Below proof, three Navy inclusion panels mix lists with UI fragments, followed by a Lilac band conversion call and full-width FAQ rows.

**Transfer:** Lead with understandable commercial units, then inclusions and objections. This is not a tier-card comparison template.

**Text style:** `heading-lg` — mt-neue-display 450 · 47px/1.25

## Page flow

**Storyline:** Promise → tangible system explanation → credible proof → capability chapters → practical next step → shared dark resource ending; adapt emphasis to the reader's task.

### Broad platform landing page

1. **Promise** — Centered two-line statement, paired actions and fine-line system stage.
2. **Social proof** — Ruled monochrome logo strip.
3. **Capability chapters** — Two-column porcelain illustrated cards.
4. **Quantified proof** — Three restrained ruled metrics.
5. **Product demonstration** — Numbered lifecycle with request/response example.
6. **Benefit summary** — Three pale ice cards.
7. **Customer proof** — Horizontal testimonial carousel.
8. **Closing call** — Centered introduction and warm contact form.
9. **Resource ending** — Forest newsletter footer.

**Transfer:** Move from broad promise to an understandable system, then evidence and a concrete conversation.

### Deep technical product landing page

1. **Promise** — Mono product label, large heading and code-to-interface scene.
2. **Customer proof** — Compact quotation followed by ruled logos.
3. **Capability chapters** — Continuous warm split-feature panel.
4. **Use cases** — Pale benefit rail followed by tonal plum illustrated cards.
5. **Developer enablement** — Task list, code workbench and integration shelf.
6. **Feature depth** — Four-column, two-row ruled feature matrix with mint icons.
7. **Closing call** — Warm contact form under a short invitation.
8. **Resource ending** — Forest newsletter footer.

**Transfer:** Use continuous chapters for technical guarantees and distinct tonal cards for applications.

### Commercial evaluation page

1. **Commercial promise** — Compact centered headline, rate figures and early form.
2. **Social proof** — Ruled logo strip.
3. **Inclusions** — Three navy explanation cards with white UI fragments.
4. **Closing call** — Short lilac conversion band.
5. **Objection handling** — Full-width ruled FAQ list.
6. **Resource ending** — Forest newsletter footer immediately after the FAQ section.

**Transfer:** Answer cost and scope early, reserving the long lower section for purchase questions rather than repeating feature marketing.

### Customer proof directory

1. **Featured proof** — Mono eyebrow and compact title above a split video/story panel.
2. **Story discovery** — Long three-column photographic directory with category tags.
3. **Breadth of adoption** — Centered heading and extended ruled monochrome mark table.
4. **Customer proof** — Short horizontal testimonial and story action.
5. **Resource ending** — Forest newsletter footer; no large contact form.

**Transfer:** Let stories dominate, then broaden credibility with a mark table and finish with one human voice.

## Writing

Confident and concrete, with an engineer's preference for explicit capabilities and an approachable commercial tone. Benefits are expressed as things a reader can build or stop doing, not as abstract disruption.

**Do not copy:** Do not reuse Modern Treasury's name, wordmark, customer marks, customer quotations, named integrations, financial volumes, uptime claims, prices or product-specific promises. Source examples illustrate syntax only; replace them with verified facts for the new product.

- **Addressing the reader:** Address builders as you or your, often through imperative verbs. Product explanations use the product name or an impersonal capability statement; conversion copy uses a conversational let's.
- **Rhythm:** Short four-to-nine-word headlines, often balanced into two lines. One-sentence explanations carry concrete nouns; benefits can use two clipped clauses. Short actions remain conversational rather than urgent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Build + meaningful outcome; or product category + purpose. | 4–9 words | “Build Products That Move Money”<br>“The Ledger for Money Movement” |
| Section lead | Two short clauses that move from capability to breadth or next step. | 4–9 words | “Get Live. Keep Building.”<br>“One Ledger. Every Transaction.” |
| Capability explanation | Concrete verb, object and operational benefit. | 10–24 words | “Collect money from customers and pay sellers, contractors, borrowers, or vendors.” |
| Action | Human invitation or direct building verb. | 2–4 words | “Talk to us”<br>“Start building”<br>“Explore docs →” |
| Commercial headline | Pair reassurance with scale; parallel sentence structure. | 6–10 words | “Build with confidence. Scale without surprises.” |
| Objection question | Ask the buyer's actual operational concern in plain language. | 6–15 words | “How does pricing change as we scale?” |

**Words and phrasing to use:** build; launch; track; move; scale; one; real-time; in control; built-in; without rebuilding; let's talk

**Avoid:** revolutionary; magical; unleash; 10x everything; the ultimate solution; hurry; !!!

**Rules:**

- Connect each benefit to a concrete operation, not a vague feeling.
- Use technical terminology when it names a real capability; explain its user consequence in the same paragraph.
- Prefer capability → consequence sentences and short parallel headings.
- Treat numeric proof as factual reporting, never decorative hyperbole.
- Use title case selectively for major campaign headings and sentence case for controls and compact benefits.

## Do's and Don'ts

### Do

- Keep the opening at 71px/1.1 and section leads at 47px/1.25, both weight 450.
- Limit centered support to 672px so paragraphs do not become banners.
- Keep illustrated pairs equal at 576px with 48px gutters at the desktop reference width.
- Use 2px action corners and 8px card corners as separate shape families.
- Stage white product fragments on warm #f8f5f4 rather than placing every screenshot directly on white.
- Use 1px alpha-charcoal rules to structure stats, FAQs and proof tables.
- Keep 12px gaps inside text groups, 24px between support and action, and 48px before major grids.
- Retain the forest footer and small mint subscription action as the final material change.

### Don't

- Do not make the light grotesk display bold at 700 or tighten it into a compressed tech headline.
- Do not color all CTA buttons mint; black is the marketing default and mint belongs to the footer subscription.
- Do not replace the equal two-column capability grid with a dense multicolor bento.
- Do not apply the header's 40px blur or shadow to every card.
- Do not use full-saturation green section backgrounds for ordinary capability content.
- Do not enlarge taxonomy into pill-shaped promotional badges; keep 12px mono and 2px corners.
- Do not carry the plum or navy product variants across the whole ordinary landing page.
- Do not turn restrained 47px proof numbers into giant gradient text or illustrated counters.

## Motion and responsive

### Motion

**Observed:**

- Most action color and border transitions are declared at 0.15s cubic-bezier(.4, 0, .2, 1); navigation color transitions use 0.2s.
- Navigation chevrons have a declared 0.2s transform transition and rotate when their popup opens.
- Carousel arrow hover background is #464646; footer links brighten to white. Hero media and process demonstrations contain moving system content.

**Transfer:**

- Keep interaction changes localized to labels, borders and selected states; preserve the fine-line system scene's legibility during transitions.
- Use movement to explain connections or progression rather than adding large decorative entrances.

**Unknown:**

- Hero video loop timings and scroll-trigger sequencing are not established.
- Presence of named keyframes does not establish their actual use on these sections.

### Responsive

**Observed:**

- Declared width breakpoints include 375px, 600px, 900px, 1024px, 1200px, 1300px and 1440px.
- Section classes specify side padding of 20px, then 24px, then 48px; illustrated pairs shift from one column to two, benefit grids to three, and story directories through two to three columns.

**Transfer:**

- As implementation guidance, stack copy above the diagram on narrow screens, retain one focal object and wrap peripheral labels rather than shrinking all technical labels into illegibility.
- Stack illustrated pairs while retaining each card's copy-to-image relationship; turn the long logo table into fewer columns and let the newsletter form wrap.

**Unknown:**

- Exact mobile font sizes, navigation-menu composition and video reframing are not established by the desktop views.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
