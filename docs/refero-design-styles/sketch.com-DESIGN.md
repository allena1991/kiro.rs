# Sketch — tactile tools, editorial warmth

## Overview

An inviting, light product style that pairs bookish serif headlines with matter-of-fact grotesk text and polished, tactile controls. Pale pink, lilac, peach and golden light surround crisp interface compositions, while most reading happens on soft gray or white. It suits creative tools and products with a rich working environment: spacious at the chapter level, densely demonstrative inside the imagery.

### Essentials

- A welcome rather than a sales shout: medium-weight Reckless headlines at 76px/1 with -1.5px tracking, paired with Inter at 24px/32px in a split opening inside a 1200px container.
- Black controls feel like physical keys: 47px-high actions with 24px corners, an inset white highlight and dark lower edge; the principal conversion gets a 4px pink-to-lilac sleeve with 28px corners.
- Color is light, not paint: keep the long reading canvas #f5f5f5 and text #212123; spread pastel atmosphere across the opening, then concentrate richer color in demonstration tiles and small category pills.
- The product is the main object: a nearly full-width interface stage with 26px upper corners and a broad warm shadow enters the first screen and continues below it. Recreate a credible working composition when finished product media is unavailable.
- Capabilities are collectible demonstrations, not icon lists: use a four-column foundation with 24px gaps, 20px-rounded tiles, mixed single and double widths, 22px/24px sans titles and large edge-clipped interface details.
- Include a jewel-like trust card: translucent white, 30px backdrop blur, 20px corners and a thin pastel spectrum along the lower edge; pair a 44px/48px serif message with a faint geometric line illustration.
- End with an invitation rather than a hard sell: a dimensional product emblem, a compact serif closing line and a haloed dark action, followed by subdued proof marks and a practical newsletter-plus-four-column footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden sleeve | `#f7bd2f` | `--color-gold` | accent | Warm closing conversion sleeve. |
| Rose halo | `#fc7a9b` | `--color-pink` | accent | Opening conversion sleeve, blended toward lilac. |
| Peach sleeve | `#f8a57e` | `--color-peach` | accent | Second stop of the warm closing conversion sleeve. |
| Lilac halo | `#b47eee` | `--color-lilac` | accent | Cool end of the opening conversion sleeve and soft atmospheric light. |
| Category cream | `#f7e5c6` | `--color-cream` | surface | Warm end of the category pill. |
| Category blush | `#efd3d7` | `--color-blush` | surface | Cool end of the warm category pill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Button charcoal | `#151515` | `--color-button` | action, surface | Polished primary action base. |
| Pure black | `#000000` | `--color-black` | text, surface, border | Navigation text, black demonstration tiles and outlined controls. |
| Reading ink | `#212123` | `--color-ink` | text | Default headings, body and icon outlines. |
| Secondary text | `#585858` | `--color-secondary` | text, link | Visible 64% black on the gray canvas for small labels and footer links. |
| Quote gray | `#5c5c5c` | `--color-quote` | text | Testimonial text. |
| Soft separator | `#dddddd` | `--color-rule` | border | Visible 10% black rule on the gray canvas. |
| Input edge | `#e6e6e6` | `--color-input-edge` | border | One-pixel outer ring around newsletter inputs. |
| Soft gray canvas | `#f5f5f5` | `--color-canvas` | background | Default marketing canvas and footer interior. |
| Input porcelain | `#f9f9f9` | `--color-input` | surface | Recessed form controls. |
| Milk | `#fafafa` | `--color-near-white` | background, surface | Footer outer band and the visible result of 48% white glass over the soft gray canvas. |
| White | `#ffffff` | `--color-white` | surface, text, background | Feature cards, light page variant and reversed button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Golden light | `#ffd98c` | `--color-warm-light` | background | Diffuse yellow atmosphere behind pricing content. |
| product feature pages | Demo peach | `#ffdfcd` | `--color-demo-peach` | surface | Upper-middle of warm demonstration gradients. |
| product feature pages | Demo cream | `#f5e4c7` | `--color-demo-cream` | surface | Top of warm demonstration gradients. |
| product feature pages | Demo rose | `#f4d4d4` | `--color-demo-rose` | surface | Lower-middle of warm demonstration gradients. |
| pricing pages | Powder lilac light | `#e5d6ed` | `--color-purple-light` | background | Diffuse purple atmosphere behind pricing content. |
| product feature pages | Demo charcoal | `#1e1e1e` | `--color-dark-panel` | surface | Dark illustrated capability cards. |
| product feature pages | Demo linen | `#f6edeb` | `--color-demo-base` | surface | Warm backing for interface illustrations and lower gradient stop. |

## Typography

- **InterVariable** — Marketing body, navigation, controls and tile titles. Neutral, high-x-height grotesk with compact, legible small text. OpenType features: "calt", "liga". If unavailable, use **Inter**. Font stack: "InterVariable", Inter, system-ui, -apple-system, "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Reckless** — Default display and chapter headings. Expressive editorial serif with strong thick-thin contrast, compact spacing and soft, lively curves. OpenType features: "calt", "liga". If unavailable, use **DM Serif Display**. Use regular weight; tune line breaks to preserve the compact editorial silhouette. Font stack: "Reckless", "DM Serif Display", Georgia, serif.
- **Marfa** (only for company manifesto pages) — Heavy statements and light conversational paragraphs. Broad, friendly grotesk with emphatic heavy cuts and open light text. If unavailable, use **Inter**. Use 900 for statements and 300 for paragraphs. Font stack: "Marfa", "Inter", system-ui, -apple-system, "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Reckless | 500 | 76px | 1 | -0.0197em | Default opening headline and major capability chapter titles. |
| compact-heading | Reckless | 500 | 44px | 48px | -0.0227em | Trust card and centered closing invitation. |
| lead | InterVariable | 400 | 24px | 32px | normal | Opening support paragraph. |
| tile-title | InterVariable | 600 | 22px | 24px | normal | Default feature tile headings. |
| chapter-body | InterVariable | 400 | 20px | 1.4 | normal | Capability introductions and trust-card support. |
| testimonial | InterVariable | 500 | 20px | 1.4 | normal | Customer quotation. |
| utility-heading | InterVariable | 600 | 17px | 28px | normal | Newsletter heading. |
| promo-heading | InterVariable | 600 | 17px | 24px | normal | Short announcement heading. |
| body | InterVariable | 400 | 16px | 1.5 | normal | Feature descriptions and explanatory copy. |
| action | InterVariable | 600 | 16px | 1.5 | normal | Primary actions and footer column headings. |
| secondary-action | InterVariable | 500 | 16px | 1.5 | normal | Outlined actions and inline emphasis. |
| navigation | InterVariable | 600 | 16px | 1 | normal | Global navigation links. |
| footer-link | InterVariable | 400 | 15px | 1.6 | normal | Footer links and secondary lists. |
| eyebrow | InterVariable | 600 | 12px | 14px | normal, uppercase | Small gradient-backed category labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company manifesto pages | manifesto-display | Marfa | 900 | 160px | 134px | -3.2px | Monumental opening text. |
| product feature page openings | feature-display | Reckless | 500 | 120px | 106px | -0.0125em | Oversized two-line benefit statement. |
| company manifesto pages | manifesto-heading | Marfa | 900 | 88px | 1 | -0.0198em | Numbered principle statements. |
| pricing and product feature pages | section-heading | Reckless | 500 | 56px | 1 | -0.0268em | Pricing title, centered chapter headers and large left-aligned closing calls. |
| pricing pages | comparison-heading | Reckless | 500 | 48px | 52px | -0.0208em | Comparison and FAQ section titles. |
| company resource endings | press-heading | Marfa | 700 | 44px | 48px | -0.0227em | Centered press or resource heading. |
| product feature pages | feature-heading | Reckless | 500 | 40px | 1.2 | -0.025em | Alternating image-and-copy rows. |
| product feature pages | bento-heading | Reckless | 500 | 36px | 40px | -0.014em | Warm demonstration bento titles. |
| company manifesto pages | manifesto-body | Marfa | 300 | 36px | 44px | normal | Long, direct supporting paragraphs. |
| company manifesto pages | manifesto-lead | Marfa | 300 | 36px | 48px | normal | Opening introductory paragraph. |
| pricing and product feature pages | card-heading | Reckless | 500 | 32px | 1.25 | -0.0156em | Plan titles and dark illustrated feature-card headings. |
| product feature pages | feature-inventory | Reckless | 500 | 24px | 26px | -0.021em | Centered wrapping inventory of short capabilities. |
| pricing pages | question | InterVariable | 500 | 18px | 28px | normal | FAQ question rows. |
| company manifesto pages | culture-action | Marfa | 600 | 16px | 1.5 | normal | Flat, small-radius actions. |

**Notes:**

- Use serif for the promise and sans for explanation; do not make the default headline bold grotesk.
- Serif tracking tightens to -1.5px for the largest default headlines, then relaxes to -1px and -0.5px in smaller roles. Category labels are uppercase without extra tracking.
- Set the default welcome headline over two compact lines. The feature-page display is tighter vertically than the default; the manifesto is a separate heavy-sans system, not a substitute for either.
- The 76px display recipe also supplies large pricing numerals; keep the currency symbol visually subordinate rather than typesetting an entire price at one size.

## Layout

**Density:** Airy between chapters, compact within demonstrations and utility regions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tile title-to-description gap, footer link rhythm and input-to-button gap. |
| 12px | Small label and compact control spacing. |
| 20px | Trust heading-to-support gap and alternating feature-row text gaps. |
| 24px | Default tile gutters and chapter heading-to-support spacing. |
| 32px | Outer viewport padding and default tile top/side padding. |
| 40px | Footer navigation top padding and manifesto title-to-paragraph gap. |
| 52px | Testimonial card padding. |
| 56px | Chapter header-to-grid spacing. |
| 64px | Announcement-to-product-stage separation. |
| 88px | Split opening column gap. |
| 100px | Default capability chapter separation. |
| 128px | Default opening top padding and manifesto chapter vertical padding. |
| 180px | Alternating feature-row separation. |
| 200px | Large feature-page chapter separation. |

### Containers and grids

- **wide-shell**: max width 1400px · side padding 32px. Global navigation, footer and full-width feature-page staging.
- **editorial-container**: max width 1200px · side padding 32px. Default split opening and capability chapters; centered within the wider shell.
- **capability-grid**: max width 1200px · 4 columns · gap 24px. Single-width tiles around 282px and double-width tiles around 588px; two 512px-high rows.
- **split-opening**: max width 1200px · 2 columns · gap 88px. Headline at left; support, conversion and compatibility note at right, aligned at the top.
- **feature-pairs** (only for product feature pages): max width 1400px · 2 columns · gap 70px. Equal media-and-copy columns or warm bento cards. Copy is inset within its half.
- **plan-grid** (only for pricing pages): 4 columns · gap 32px. Equal 286px-wide cards with aligned action baselines.
- **manifesto-column** (only for company manifesto pages): max width 894px. Statement headings sit to the right of monumental left-side numbers; supporting copy narrows to 690px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary controls | 24px |
|  | conversion sleeves | 28px |
|  | default tiles | 20px |
|  | product stage upper corners | 26px |
|  | newsletter input | 16px |
| product feature pages | feature demonstration cards | 28px |
| product feature pages | atmospheric feature panels | 80px |
| pricing pages | pricing wrapper | 56px |
| pricing pages | pricing cards | 28px |
| company manifesto pages | manifesto controls | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | product stage | `0px 40px 200px 0px rgb(200, 171, 173)` | Broad warm reflected light beneath the main interface. |
|  | glass trust card | `0px 0px 4px 0px rgba(0,0,0,0.08), 0px 4px 8px 0px rgba(0,0,0,0.02), 0px 1px 2px 0px rgba(0,0,0,0.08)` | Subtle layered edge rather than an obvious drop shadow. |
| pricing pages | pricing glass | `0px 0px 1px 0px rgba(74,21,39,0.2), 0px 12px 24px 0px rgba(74,21,39,0.1)` | Warm soft lift under white plan cards. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing page field.

**CSS:** `background: #f5f5f5; color: #212123`

**Observed:** Continuous pale neutral ground connects separate chapters.

**Transfer:** Let atmosphere fade back into this field rather than assigning every chapter a colored band.

#### White tile · level 1

**Use:** Default demonstration card.

**CSS:** `background: #ffffff; border-radius: 20px; overflow: hidden`

**Observed:** White and black tiles alternate with pale image-backed tiles; most have no visible outer border.

**Transfer:** Choose contrast to suit the demonstrated workflow, not a rainbow sequence.

#### Glass trust card · level 1

**Use:** A compact trust or positioning interlude.

**CSS:** `background: rgba(255,255,255,0.48); border-radius: 20px; backdrop-filter: blur(30px); box-shadow: 0px 0px 4px 0px rgba(0,0,0,0.08), 0px 4px 8px 0px rgba(0,0,0,0.02), 0px 1px 2px 0px rgba(0,0,0,0.08)`

**Observed:** A pale spectrum strip hugs the bottom edge; a very soft radial overlay adds depth without obvious texture.

**Transfer:** Keep the card nearly white, with color revealed at its edge rather than throughout its text field.

#### Warm demo gradient · level 1

**Only for:** product feature pages

**Use:** Backing for large interface fragments.

**CSS:** `background: linear-gradient(197deg, #f5e4c7 0%, #ffdfcd 27%, #f4d4d4 56%, #f6edeb 99%); border-radius: 28px; overflow: hidden`

**Observed:** Peach and rose gradients hold large pink interface objects with soft shadows.

**Transfer:** Use a restrained tonal family behind an equally coherent product example.

#### Dark illustrated card · level 1

**Only for:** product feature pages

**Use:** Technical capability carousel.

**CSS:** `background: #1e1e1e; border: 1px solid rgba(0,0,0,0.08); border-radius: 16px; box-shadow: 0px 4px 15px 0px rgba(0,0,0,0.2); color: #ffffff`

**Observed:** Colorful isometric diagrams occupy the upper area and serif explanation sits below.

**Transfer:** Reserve this treatment for technical proof within an otherwise light page.

#### Pricing atmosphere · level 0

**Only for:** pricing pages

**Use:** Broad backing behind the plan family.

**CSS:** `background: linear-gradient(255deg, rgba(240,201,235,0.3) 0%, rgba(181,175,161,0.15) 51%, rgba(221,190,115,0.2) 78%, rgba(255,207,90,0.15) 100%); border-radius: 56px`

**Observed:** Cards rise above the top edge; large diffuse golden and lilac lights continue behind the title.

**Transfer:** Group offers in one shared light field instead of strongly coloring one recommended card.

#### Pricing glass · level 1

**Only for:** pricing pages

**Use:** Plan offer surface.

**CSS:** `background: rgba(255,255,255,0.9); border-radius: 28px; backdrop-filter: blur(40px); box-shadow: 0px 0px 1px 0px rgba(74,21,39,0.2), 0px 12px 24px 0px rgba(74,21,39,0.1)`

**Observed:** Almost opaque white with warmer light visible around, not through, the copy.

**Transfer:** Maintain readable neutral offers above a colored ambient backdrop.

## Components

### Navigation

**Use:** Global orientation and persistent access to conversion.

**CSS:** `display: flex; max-width: 1400px; height: 80px; padding: 0px 32px`

**Text style:** `navigation` — InterVariable 600 · 16px/1

**Observed:** Small outline emblem at the far left, category menus beside it, sign-in and Primary button at the far right. Starts transparent over the atmosphere. A compact white chapter navigation appears while scrolling long marketing content.

**Transfer:** Use a small symbol rather than a large wordmark; keep the hierarchy shallow.

### Primary button

**Use:** Main conversion and chapter exploration.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: linear-gradient(rgba(0,0,0,0) 0%, rgba(255,255,255,0.05) 50%, rgba(255,255,255,0.15) 100%), #151515; color: #ffffff; border-radius: 24px; padding: 11px 24px 12px; height: 47px; box-shadow: 0px 1px 1px 0px rgba(0,0,0,0.05) inset, 0px 1px 4px 0px rgba(255,255,255,0.5) inset, 0px -2px 4px 0px rgba(0,0,0,0.94) inset, 0px 1px 4px 0px rgba(0,0,0,0.2)`

**Text style:** `action` — InterVariable 600 · 16px/1.5

**Observed:** A subtle domed highlight and dark lower edge make it feel pressed from a material. Download variants add a right-hand 24px icon, 8px gap and reduce right padding to 16px.

**States:** Declared: hover translateY(-1px) with outer shadow alpha reduced to 0.05; active translateY(0px), white text at 0.75 alpha and no outer shadow.

**Transfer:** Give the main verb a short, specific label.

### Conversion sleeve

**Use:** Frame the principal opening and closing action.

**CSS:** `display: inline-block; background: linear-gradient(104deg, #fc7a9b 0%, #b47eee 100%); border-radius: 28px; padding: 4px; box-shadow: 0px 0.5px 1px 0.5px rgba(0,0,0,0.1) inset`

**Observed:** Primary button sits inside the colored sleeve. The closing variant changes to gold-to-peach; the pricing closing variant is pale yellow-to-lilac.

**Transfer:** Keep the color outside the black key rather than filling the button itself.

### Category pill

**Use:** Label a capability chapter.

**CSS:** `display: inline-flex; background: linear-gradient(191deg, #f7e5c6 0%, #efd3d7 100%); border-radius: 9999px; padding: 8px 12px 7px; color: rgba(0,0,0,0.64)`

**Text style:** `eyebrow` — InterVariable 600 · 12px/14px · uppercase

**Observed:** Warm peach is one category, mint another, and ice-blue/lavender another. All are small and low contrast, not status indicators.

**Transfer:** Map a restrained pastel family to each major capability.

### Feature tile

**Use:** A self-contained visual demonstration.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 32px 32px 0px; overflow: hidden; height: 512px`

**Text style:** `tile-title` — InterVariable 600 · 22px/24px

**Observed:** Title and brief body sit above or beside a much larger product detail. Mix 282px and 588px widths on a common grid. Dark variants use white text. Small white circular arrow controls appear near lower corners.

**Transfer:** Show one user outcome per tile, using a credible product fragment rather than a decorative icon.

### Announcement banner

**Use:** One timely release or product news item near the opening.

**CSS:** `display: flex; max-width: 792px; background: #ffffff; border-radius: 20px; overflow: hidden`

**Text style:** `promo-heading` — InterVariable 600 · 17px/24px

**Observed:** A 238px-wide pastel illustration sits left of a vertically centered text area, separated by a faint rule; heading, short support and inline action form a compact 134px-high unit.

**Transfer:** Keep this subordinate to the welcome and main product stage.

### Newsletter input

**Use:** Email collection at the page ending.

**CSS:** `background: #f9f9f9; border-radius: 16px; height: 48px; padding: 12px 14px; box-shadow: 0px 0px 0px 1px #e6e6e6, 0px 1px 2px 0px rgba(0,0,0,0.04) inset`

**Observed:** Wide email field beside a compact Primary button, with a separate consent checkbox beneath. The empty-form submit is at 0.4 opacity. Company manifesto forms use 6px corners instead.

**Transfer:** Keep consent visible and the field treatment recessed rather than outlined heavily.

### Footer link group

**Use:** Practical secondary navigation.

**CSS:** `color: rgba(0,0,0,0.64); margin-bottom: 8px; width: 180px`

**Text style:** `footer-link` — InterVariable 400 · 15px/1.6

**Observed:** Four widely spaced columns below a hairline rule. Column headings use the action recipe; links remain light, without decorative cards.

**States:** Declared: hover and active color rgba(0,0,0,0.8).

### Secondary button

**Only for:** pricing and product feature pages

**Use:** Contact sales or deeper feature exploration.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; color: #000000; border: 1.5px solid #000000; border-radius: 24px; padding: 11px 24px 12px; height: 50px`

**Text style:** `secondary-action` — InterVariable 500 · 16px/1.5

**Observed:** Transparent interior with a thin dark perimeter; directional variants add a small right arrow.

**States:** Declared: hover translateY(-1px), rgba(0,0,0,0.05) background and 0px 1px 4px rgba(0,0,0,0.25) shadow; active translateY(0px), text at 0.75 black alpha and inset 1.5px dark edge.

### Plan card

**Only for:** pricing pages

**Use:** Compare commercial offers.

**CSS:** `display: flex; flex-direction: column; background: rgba(255,255,255,0.9); border-radius: 28px; padding: 36px 36px 52px; width: 286px; backdrop-filter: blur(40px); box-shadow: 0px 0px 1px 0px rgba(74,21,39,0.2), 0px 12px 24px 0px rgba(74,21,39,0.1)`

**Text style:** `card-heading` — Reckless 500 · 32px/1.25 · tracking -0.0156em

**Observed:** Title, audience description, oversized serif price, small billing line, checkmarked benefits, bottom-aligned action. Self-serve offers use Primary button; contact-led offers use Secondary button. A small yearly/monthly selector straddles the first card’s upper edge.

**Transfer:** Align benefits and actions across equal offers without a loud recommended-plan badge.

### Question row

**Only for:** pricing pages

**Use:** Objection handling in grouped accordions.

**CSS:** `display: flex; justify-content: space-between; padding: 20px 0px; border-bottom: 1px solid rgba(0,0,0,0.08)`

**Text style:** `question` — InterVariable 500 · 18px/28px

**Observed:** Question at left and a small plus at right, inside a 787px-wide answer column. Uppercase category labels separate groups. A large serif section title occupies the left column.

**Transfer:** Use real purchasing objections and leave the closed rows visually flat.

### Manifesto button

**Only for:** company manifesto pages

**Use:** Resource download and company-page conversion.

**CSS:** `display: inline-flex; background: #000000; color: #ffffff; border-radius: 6px; padding: 11px 15px; height: 48px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.1)`

**Text style:** `culture-action` — Marfa 600 · 16px/1.5

**Observed:** A flatter, squarer control than the default polished key; the resource ending places it beside a selector.

**States:** Declared: hover background rgba(0,0,0,0.85); active white text at 0.7 alpha over black.

## Imagery and graphics

### Pastel atmosphere

**Use:** Signature light across the opening and at selected conversion moments.

**Observed:** Soft pink pools at lower left, pale lilac toward the right, and warm off-white across the top. Light is broad, cloudy and nearly textureless, not a sharply bounded mesh. It sits behind text and the main interface, extending beyond the viewport.

**Transfer:** Recreate the light field even without a product image; pair it with a simple working-state composition. Match the soft glow; exact stops are not essential.

**Build:** Layer oversized radial gradients over Canvas: a rose rgba(252,122,155,0.2) ellipse below the left half, a lilac rgba(180,126,238,0.18) ellipse above the right half, each roughly 1000px–1800px wide with transparent outer halves. Blur the layers around 100px and clip at the page edge. Keep the headline area pale.

### Main interface stage

**Use:** Primary visual proof after the opening copy.

**Observed:** A large desktop editor window occupies almost the full content width; light native chrome surrounds a saturated example project. Sidebars remain visible while the canvas supplies the visual interest. The upper corners are rounded and a diffuse mauve shadow separates the window from the atmospheric ground.

**Transfer:** Use the new product’s actual working environment with readable structure and an attractive completed outcome. Minimum version: build a believable shell with one carefully art-directed example, not a blank device mockup.

### Capability closeups

**Use:** Within Feature tile and alternating feature rows.

**Observed:** Magnified portions of real workflows, overlapping floating panels, cursor paths and selection handles. Pastel pink, violet and mint detail sits against cream, pale blue or black. Imagery often bleeds to two or three card edges and is larger than the accompanying text.

**Transfer:** Enlarge the part that proves the benefit. Recreate a small task faithfully in HTML or SVG if full media is unavailable; use coherent UI, not arbitrary charts.

### Spectrum trust edge

**Use:** Signature lower edge of Glass trust card.

**Observed:** A thin band of soft rose, lilac, blue and mint peeks under a nearly white panel; a faint geometric wireframe emblem sits beside the text.

**Transfer:** Use a simple geometric abstraction of the new product’s idea, drawn as barely visible construction lines. Preserve the colored edge.

**Build:** Add a bottom-aligned 20px-high pseudo-element, clipped by the 20px card corners. Use a horizontal rose-to-lilac-to-blue-to-mint gradient at low opacity. Draw an approximately 316px-wide SVG of straight 1px lines in rgba(33,33,35,0.12), fading toward the perimeter. A layered polygon or folded outline is sufficient.

### Dimensional product emblem

**Use:** Closing invitation and compact product announcement.

**Observed:** A jewel-like faceted app symbol sits on a softly rounded white tile, with a subtle edge shadow. The default centered ending uses a 120px emblem; larger feature and pricing endings use 200px.

**Transfer:** Give the new product a polished, simple emblem on a porcelain tile. Minimum version: an original faceted geometric symbol with two or three tonal faces and a soft contact shadow.

**Build:** Use a rounded white square with a subtle inset edge and soft shadow. Center an original SVG polygon composed of light, mid and dark facets; use warm gold or the product’s own restrained accent. Size the symbol to about two thirds of the tile.

### Subdued proof marks

**Use:** Between the closing invitation and utility footer.

**Observed:** A horizontal row of customer wordmarks rendered in pale gray, equalized optically rather than forced into identical shapes.

**Transfer:** Use legitimate proof marks or concise verified proof statements, with uniform low visual emphasis.

### Warm feature world

**Only for:** product feature pages

**Use:** Oversized product-feature opening and broad demonstration panels.

**Observed:** White fades into golden yellow and coral light, with barely visible diagonal faceted planes. Pink media frames have pale thick edges and warm shadows. Large rounded panels can contain both editorial copy and a contrasting dark working-state card.

**Transfer:** Keep the atmosphere warm and luminous, with geometry subordinate to the product.

**Build:** Place a broad golden radial light at the left and a rose light at the upper right over white. Add two translucent polygon planes using clip-path with rgba(255,255,255,0.15) fills at opposing diagonals. Keep 80px outer corners on large interior panels and 28px on nested demonstration cards.

### Technical diagrams and inventory

**Only for:** product feature pages

**Use:** Dark capability carousel and the typographic proof field beneath it.

**Observed:** Isometric line diagrams, stacked shapes, arrows and bright small color chips sit on charcoal cards. Beneath them, short serif capability names wrap into centered rows separated by tiny golden dots; the list reads like a typographic texture rather than a table.

**Transfer:** Illustrate relationships between the product’s primitives in a consistent isometric language, then use real short capability names below.

**Build:** Use thin gray SVG wireframes of stacked rectangles in a consistent oblique projection. Highlight only a few faces in muted bright accents. Construct the inventory as a centered wrapping flex list with 32px row gaps and 64px column gaps; place a small warm dot between entries.

### Typography specimen field

**Only for:** text-centric feature demonstrations

**Use:** A centered focused demonstration with surrounding visual vocabulary.

**Observed:** A dark stylized word specimen and floating adjustment panel occupy the middle; oversized multilingual glyphs and typographic terms fade almost to white at both sides. The centered headline and paragraph remain crisp.

**Transfer:** Substitute a representative output specimen and a small authentic control panel; use related technical marks as pale peripheral art.

**Build:** Arrange large SVG or text glyphs in two side columns, tint them rgba(33,33,35,0.04), and overlay a broad white radial mask toward the central copy. Keep the central specimen dark and the small floating panel white with a soft shadow.

### Manifesto numbering and photo type

**Only for:** company manifesto pages

**Use:** Company opening and repeated principle chapters.

**Observed:** The opening ends in a heavy word filled with candid people photography. Chapters have enormous pale gradient numerals clipped by the left edge and a vertical rail of pastel dots, with the active dot extended into a short pill. Text is heavy black sans above a light-weight paragraph.

**Transfer:** Use authentic people or process photography inside one short word, with real principles supported by readable copy. Numbering is a navigation device, not a business metric.

**Build:** Clip an original people photograph into heavy text using background-clip:text. For chapters, place an oversized 900-weight numeral behind the far-left margin at low opacity, filled with a horizontal pastel-to-transparent gradient. Stack small colored circles in a fixed left rail and stretch the current marker vertically. Size the numeral to occupy most of a chapter’s height; keep it clear of the reading column.

### Icons

**Observed:** Mostly 24px outline SVGs with 1.5px round strokes. Smaller navigation chevrons are 17px with 1px strokes; download arrows use lighter white outlines. Pricing uses small circled checks, dashes and information marks.

**Transfer:** Use simple rounded line icons in ink; reserve larger 68px outline symbols for centered feature-page chapter headers. Avoid filled multicolor icon packs outside product media.

## Section recipes

How recurring sections are built.

### First screen: Split welcome and product stage

**Observed:** An 80px transparent Navigation sits above a split welcome inside the 1200px editorial container. After 128px top breathing room, a two-line 76px serif headline fills the left half; a 24px/32px support paragraph occupies the right, followed by the sleeved Primary button and a faint compatibility note. Layers run from Canvas through Pastel atmosphere to copy, controls, a centered Announcement banner, and the Main interface stage. The announcement is 792px wide and 134px high, with 64px before the stage. Within the first 900px, the headline, support, action, note, announcement and top of the nearly full-width interface are visible; the detailed working canvas continues below the fold.

**Transfer:** Keep the headline a warm audience-oriented invitation, and place an equally concrete product promise in the right column. Without finished media, create a believable working-state shell and one attractive output. Pricing opens with a smaller 56px title and offer cards entering immediately; feature pages use a 120px two-line serif display and warm media stage; company manifestos use heavy photographic text instead of serif.

**Avoid:** Do not center all opening content into one narrow stack, turn the atmosphere into a saturated banner, or shrink the interface to a small floating illustration.

**Text style:** `display` — Reckless 500 · 76px/1 · tracking -0.0197em

### Capability chapter header

**Observed:** Category pill, display headline and chapter-body support form the left part of a two-column header; a Primary button anchors the lower right. Gaps are 24px and the Feature tile grid starts 56px below. The support stays around one column wide.

**Transfer:** Use benefit-led chapter names and one concrete explanation; align the action to the end of the reading block rather than alongside the eyebrow.

**Text style:** `display` — Reckless 500 · 76px/1 · tracking -0.0197em

### Demonstration mosaic

**Observed:** Feature tile cards share 512px height on a four-column, 24px-gutter foundation. Double-width demonstrations sit beside narrow vertical details; dark, white and pastel media surfaces alternate. A related variant becomes a horizontally clipped row of 588px-wide cards with circular navigation controls.

**Transfer:** Vary tile width according to the demonstration, keeping the visual baseline and text treatment consistent. Let one adjacent card peek into view for horizontal collections.

### Quotation interlude

**Observed:** A 792px-wide white card with 20px corners and 52px padding carries a 20px medium-weight gray quotation, a pale oversized quote mark and compact attribution. The adjacent slide is subdued and arrow controls sit beneath.

**Transfer:** Use one complete, credible customer observation instead of several short anonymous endorsements.

**Text style:** `testimonial` — InterVariable 500 · 20px/1.4

### Glass positioning card

**Observed:** Glass trust card is centered at 996px wide with 100px upper padding and a generous text-and-emblem split. Compact-heading leads, chapter-body supports, and a short text link closes. Spectrum trust edge supplies the restrained chromatic finish.

**Transfer:** Use this for a product philosophy, assurance or differentiator that benefits from a pause in the demonstrations.

**Text style:** `compact-heading` — Reckless 500 · 44px/48px · tracking -0.0227em

### Centered closing invitation

**Observed:** A 120px Dimensional product emblem sits over a centered compact-heading, short support and warm Conversion sleeve. The section has about 110px top and bottom breathing room, then Subdued proof marks precede the newsletter footer.

**Transfer:** Close on one clear next step and a concrete benefit. Preserve the product-object, headline and haloed-action relationship.

**Text style:** `compact-heading` — Reckless 500 · 44px/48px · tracking -0.0227em

### Newsletter and utility ending

**Observed:** A two-column band pairs a small utility-heading and restrained explanatory paragraph with an email form and consent line. It uses 32px vertical padding and a 60px column gap. A thin rule separates the four Footer link group columns below, with 40px top padding and 8px link spacing.

**Transfer:** Keep the ending useful and readable; adapt the column topics to the new product and make the frequency promise specific.

**Text style:** `utility-heading` — InterVariable 600 · 17px/28px

### Feature chapters and alternating rows

**Only for:** product feature pages

**Observed:** Centered 56px serif chapter titles with large outline icons introduce paired warm demo cards. Later rows alternate a 653px-wide illustration with a narrow inset text column, 40px serif heading, body and optional Secondary button. Rows are separated by 180px. Technical diagrams and inventory provide a denser proof interlude.

**Transfer:** Use the spacious rows for capabilities needing explanation and the mosaics for benefits best understood visually.

**Text style:** `feature-heading` — Reckless 500 · 40px/1.2 · tracking -0.025em

### Large luminous closing call

**Only for:** pricing and product feature pages

**Observed:** A broad white, faintly ruled section holds golden light at the left, a 200px product emblem, a 56px serif invitation, 24px support and Conversion sleeve. Content is left aligned, leaving substantial open space to the right. Newsletter and four-column footer follow on white.

**Transfer:** Use this larger ending when a long, detailed page needs a strong release into a simple action.

**Text style:** `section-heading` — Reckless 500 · 56px/1 · tracking -0.0268em

### Offers to comparison to questions

**Only for:** pricing pages

**Observed:** Four Plan cards overlap the upper edge of Pricing atmosphere. A shallow translucent one-time offer follows beneath. A large comparison matrix has a left label column, four centered plan columns and compact floating offer headers during scroll. Groups are separated by 56px. Paired neutral resource cards lead into the split FAQ with Question row controls.

**Transfer:** Separate the initial choice from detailed comparison and objections. Retain visible billing units and use a wider horizontal offer for a structurally different purchase option.

**Text style:** `comparison-heading` — Reckless 500 · 48px/52px · tracking -0.0208em

### Manifesto chapters

**Only for:** company manifesto pages

**Observed:** Heavy 88px sans statements sit right of pale monumental numerals, followed after 40px by 36px light paragraphs in a 690px measure. Each chapter has 128px vertical padding; a pastel progress rail remains at left. The opening uses 160px photo-filled display type and 36px introductory copy. The ending becomes a centered press/resource block with a selector and Manifesto button, then subdued proof marks and the newsletter footer.

**Transfer:** Use the same contrast of monumental assertion and human explanation for authentic product principles, not a feature checklist.

**Text style:** `manifesto-heading` — Marfa 900 · 88px/1 · tracking -0.0198em

## Page flow

**Storyline:** Welcoming promise → tangible product proof → capability demonstrations → reassurance → simple next step → useful utility ending.

### Broad product introduction

1. **promise** — Split editorial welcome with pastel atmosphere, a sleeved action and compact announcement.
2. **product demonstration** — Near-full-width working interface followed by a customer quotation.
3. **capability chapters** — Benefit-led headers introduce mixed-width demonstration mosaics and a clipped card row.
4. **reassurance** — Glass positioning card with faint geometric artwork and spectrum edge.
5. **closing call** — Centered product emblem, short serif invitation, haloed action and subdued proof marks.
6. **utility ending** — Newsletter with consent, then four link columns.

**Transfer:** Use the main object to establish credibility before breaking the product into user outcomes.

### Commercial decision support

1. **promise** — Compact serif title and plain trial explanation over diffuse golden and purple light.
2. **pricing** — Four equal glass offers and a separate shallow alternative-purchase panel.
3. **comparison** — Long grouped matrix with compact plan controls following the reader.
4. **objection handling** — Paired assistance resources and grouped accordion questions.
5. **closing call** — Large left-aligned product emblem and invitation on a golden luminous field.
6. **utility ending** — Newsletter and four-column navigation.

**Transfer:** Make the initial choice easy, then provide detailed comparisons and honest answers without making every visitor read the matrix.

### Deep product capability landing page

1. **promise** — Monumental serif statement with a small warm underline accent, paired actions and a large pink interface stage.
2. **capability chapters** — Centered icon-led introductions, warm bento demonstrations, a specimen field and a luminous split-use panel.
3. **technical proof** — Dark illustrated cards followed by a centered serif capability inventory.
4. **workflow detail** — Alternating image-and-copy rows with generous chapter spacing.
5. **closing call** — Left-aligned emblem, serif invitation and warm sleeved action.
6. **utility ending** — Newsletter and four link columns.

**Transfer:** Choose a few visually strong workflow chapters, then use shorter alternating rows for breadth; the exact chapter sequence can change.

### Company principles and positioning

1. **identity promise** — Heavy sans opening with people photography clipped into a word and faint geometric art at the edge.
2. **principles** — Repeated oversized pale numbers, progress rail, heavy assertions and light conversational paragraphs.
3. **resource ending** — Centered press contact and resource selector with flat dark download action.
4. **social proof** — Subdued horizontal marks.
5. **utility ending** — Newsletter and compact four-column navigation within a narrower container.

**Transfer:** Use this as a distinct editorial manifesto system when the content genuinely concerns commitments and point of view.

## Writing

Warm, candid and opinionated without sounding grandiose. Benefits are stated confidently, then grounded in practical workflow details and small conversational asides.

**Do not copy:** Do not reuse Sketch’s name, diamond or app artwork, interface projects, customer logos, quotations, audience claims, pricing, trial terms, longevity claims or company commitments. Replace them with original assets and verified facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; speak as we when explaining choices. Product descriptions remain plain rather than institutionally impersonal.
- **Rhythm:** Short, often three-to-six-word benefit headlines. Supporting paragraphs mix direct sentences with fragments, contractions, parenthetical remarks and occasional em dashes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A welcoming address to a specific audience, or a tool promise ending in a personal benefit. | 3–6 words | “Designers, welcome home.”<br>“Design tools, made for you” |
| Chapter headline | An active benefit that removes friction rather than names a technology. | 3–6 words | “Design without distractions”<br>“Take your work further”<br>“Sweat the details” |
| Feature support | Describe the action and its payoff, with a lightly human aside when justified. | 1–3 short sentences | “Create a working prototype in less than 10 clicks. Seriously. We’ve counted.”<br>“Work offline without compromise — on your own and in private. Save your files locally or anywhere you choose.” |
| Primary action | Direct verb plus the destination or low-friction next step. | 2–5 words | “Get started for free”<br>“Get in touch” |
| Principle statement | Declare a choice and contrast it with the alternative, then explain why it matters to the reader. | 7–14 words | “We make decisions for designers, not outside investors”<br>“We believe your data is just that — yours” |
| Utility reassurance | A practical promise about what happens next, not another sales pitch. | 1–2 sentences | “We’ll rarely send more than one email a month.” |

**Words and phrasing to use:** you and your work; made for you; without compromise; get started; the choice is yours; save time; keep the creative work; plain verbs: create, share, test, start

**Avoid:** revolutionary platform; unlock limitless potential; synergy; disrupt; enterprise-grade everything; empty superlatives

**Rules:**

- Lead with what the reader can do, then name the mechanism.
- Allow personality through precise observations and contractions rather than exclamation marks.
- State exclusions and trade-offs plainly when they help a decision.
- Keep the compatibility or billing caveat close to the action it qualifies.
- Support strong claims with real examples; playful certainty only works when the detail is true.

## Do's and Don'ts

### Do

- Keep ordinary landing-page headlines in the 76px medium serif recipe, with compact line breaks.
- Use the 1200px editorial container inside the 32px-padded wider shell.
- Pair 20px card corners with 24px gutters and 32px internal text padding.
- Give the principal conversion a 4px colored sleeve around the dark 47px key.
- Keep most paragraphs at 16px/24px or chapter introductions at 20px/28px.
- Make product closeups fill most of their tiles and clip cleanly at the edges.
- Preserve the spectrum-edge glass interlude as a tactile counterpoint to the product grid.
- Use the heavy 88px sans and 36px light body only for the manifesto variant.

### Don't

- Do not replace the polished charcoal controls with flat colored pills; their inset highlight and lower edge are part of the material language.
- Do not make the entire page dark because some demonstration cards are black.
- Do not apply 80px panel radii to ordinary feature cards; keep those at 20px by default.
- Do not add letter-spaced uppercase slogans above every heading; the small 12px category labels have normal tracking.
- Do not turn the pricing offers into a saturated recommended-card competition; keep equal white glass surfaces.
- Do not use giant marketing numbers as supposed statistics when the oversized numerals are chapter navigation.
- Do not fill the footer with decorative tile backgrounds; it is a thin-rule, four-column utility area.
- Do not reduce all product illustrations to generic flat icons; the style depends on enlarged working details.
- Do not move manifesto typography into the default navigation or body system.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary controls declare a 0.25s cubic-bezier(0.4,0,0.2,1) transition and a -1px hover lift.
- Footer links declare color 0.125s cubic-bezier(0.455,0.03,0.515,0.955).
- Entry effects include fadeInDown and scaleInDown at 0.8s cubic-bezier(0.19,1,0.22,1); the main stage uses tiltInUp at 0.8s cubic-bezier(0.785,0.135,0.15,0.86).
- Marquee animation is declared at 100s linear infinite; pricing lights declare 8s and 13s ease-in-out pulses.

**Transfer:**

- Use the tiny control lift to reinforce the physical-key treatment.
- Keep atmosphere slow and broad, while chapter reveals settle into a fully readable static layout.

**Unknown:**

- Exact scroll trigger positions, carousel autoplay behavior and complete keyframe trajectories are unspecified.
- Focus-visible treatments were not established.

### Responsive

**Observed:**

- The established composition is a 1440px-wide desktop layout; no reliable width breakpoints are specified.

**Transfer:**

- Recommended adaptation: stack the split welcome in reading order, keeping the serif headline above support and the sleeved action.
- Recommended adaptation: reduce the four-column mosaic to fewer columns while preserving one large product demonstration and clearly clipped horizontal card collections.
- Recommended adaptation: scale the manifesto’s pale numbers into the margin and keep its progress rail clear of paragraph text.

**Unknown:**

- Mobile headline sizes, navigation collapse, horizontal table handling and exact breakpoint values are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
