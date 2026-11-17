# Rerun — prismatic engineering playground

## Overview

A bright technical style that pairs matter-of-fact system typography with luminous rainbow objects and real working interfaces. White space, near-black headings and restrained gray copy make complex developer products feel approachable rather than enterprise-heavy. The density shifts from spacious product promises to compact technical explanations, galleries and community voices.

### Essentials

- The promise is typographic, the spectacle is off-axis: centered 63.8px/1 display type at weight 450 sits above paired actions while a white object releases a spectrum of curved ribbons toward the right edge of an 830px stage.
- Technical labels act like equipment markings: JetBrains Mono, 18px/1.33, weight 500, uppercase with 0.0125em tracking; ordinary paragraphs remain system sans at 15px/1.5.
- Actions are small rectangular tools, not friendly pills: 38px high, 1.9px corners, 13.1px side padding, uppercase 15px mono, one dark fill beside a hairline outline.
- Color belongs to the phenomenon, not the page chrome: the canvas and almost all cards stay white with #0a0a0a ink and #d4d4d4 rules; concentrated rainbow art occupies a minority of the opening, while technical green and violet stay in small data marks.
- Include a luminous material device: white ceramic-like layers or a product-relevant neutral object with translucent spectral ribbons, fading into white. A simple SVG fan of curved colored sheets is the minimum equivalent when no rendered object is available.
- Proof is unusually tangible: small real-interface media, uppercase mono feature labels and a four-column community wall of 268px white cards with 15px corners and 18.8px padding balance the airy display sections.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Technical green | `#009966` | `--color-technical-green` | accent | Small repository markers and live-status dots; also data bars in explanatory diagrams, never a section fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0a0a0a` | `--color-ink` | text, action | Headlines, technical labels and filled primary actions. |
| Media black | `#000000` | `--color-black` | background, action | Base beneath the animated spectral meeting action and dark translucent overlays. |
| Working gray | `#525252` | `--color-muted` | text, link | Body copy, secondary heading clauses and navigation. |
| Hairline gray | `#d4d4d4` | `--color-rule` | border | 0.5px section rules, card outlines and control edges. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page, cards and reversed button labels; cards are separated by edges rather than darker fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical architecture explanations | Diagram violet | `#9810fa` | `--color-diagram-violet` | accent | Solid data marks and compact sample graphics. |

## Typography

- **-apple-system** — All prose, navigation, display and section headings. Native system grotesk with open counters and moderate width; restrained medium weights rather than heavy display cuts. Font stack: "-apple-system", system-ui, "Segoe UI", Roboto, "Helvetica Neue", "Noto Sans", Arial, sans-serif.
- **JetBrains Mono** — Uppercase feature headings, conversion actions and code. Explicitly technical, evenly spaced and compact enough for multiline labels. Font stack: "JetBrains Mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | -apple-system | 450 | 63.8px | 1 | -0.01em | Main promise, centered and usually broken into two balanced lines. |
| heading-lg | -apple-system | 500 | 45px | 1.1 | -0.02em | Major section headings and large gray-to-ink paired statements. |
| heading | -apple-system | 500 | 33.8px | 1.15 | -0.01em | Editorial features, catalog section pairs, product-card titles and stat values. |
| lead | -apple-system | 400 | 19px | 1.5 | normal | Hero and section support paragraphs, usually constrained to 630px. |
| technical-heading | JetBrains Mono | 500 | 18px | 1.33 | 0.0125em, uppercase | Feature names, project names and gallery titles; also reversed on recruiting cards. |
| body | -apple-system | 450 | 15px | 1.5 | normal | Main explanatory paragraphs, navigation and footer columns. |
| action | JetBrains Mono | 450 | 15px | 1.5 | normal, uppercase | Primary and secondary conversion buttons. |
| community-name | -apple-system | 500 | 15px | 1.25 | normal | Author names above handles in community cards. |
| small | -apple-system | 450 | 13.1px | 1.43 | normal | Gallery descriptions, documentation search and community handles. |
| code | JetBrains Mono | 400 | 12.9px | 1.6 | normal | Short installation commands in the light code control. |
| caption | -apple-system | 500 | 12.8px | 1.5 | normal | Category labels, language tabs, proof captions and filter chips. |

**Notes:**

- The largest type is only weight 450. Use weight 500 for section headings, not bold display lettering.
- Tighten tracking most at the 45px heading tier; keep body and action tracking normal. Uppercase is a technical-label convention, not a general prose treatment.
- A heading pair can share one size and weight while its introductory clause is gray and its decisive clause is ink. Both clauses have equal typographic rank.

## Layout

**Density:** Airy outer sections with compact technical interiors; the large vertical pauses make room for imagery while individual controls remain small.

### Spacing

| Value | Use |
| --- | --- |
| 7.5px | Paired-action gap and compact inline groups. |
| 11.3px | Feature-heading to paragraph spacing and avatar-header gaps. |
| 15px | Community-card gutters and paragraph separation. |
| 18.8px | Card padding and heading-to-lead spacing. |
| 22.5px | Desktop container side padding and feature column gaps. |
| 26.3px | Hero lead-to-actions gap. |
| 30px | Gallery grid gutters and comparison cell side padding. |
| 37.5px | Offer-card padding and footer bottom padding. |
| 45px | Editorial columns and section-heading to gallery gap. |
| 60px | Opening top inset beneath navigation and larger grouped-content gaps. |
| 75px | Catalog chapter padding and footer top padding. |
| 90px | Editorial section top padding. |
| 120px | Major product chapter separation and closing-call padding. |

### Containers and grids

- **page-container**: max width 1160px · side padding 22.5px. Centered navigation, broad feature rows and footer; the inner usable span is 1115px.
- **content-container**: max width 1080px · side padding 22.5px. Opening text composition and catalog content.
- **lead-column**: max width 630px. Centered support copy; narrower than the stage and wide headings.
- **technical-split**: max width 960px · 2 columns · gap 45px · side padding 22.5px. Large statement and install control on the left, three compact media-and-text rows on the right.
- **feature-row**: 4 columns · gap 22.5px. Unboxed capabilities below the centered infrastructure statement.
- **editorial-split**: max width 840px · 2 columns · gap 45px · side padding 22.5px. Portrait-format interface media beside compact editorial copy.
- **catalog-grid** (only for example and resource catalogs): max width 1080px · 3 columns · gap 30px · side padding 22.5px. 325px-wide media-first items with independent text beneath.
- **offer-pair** (only for product comparison pages): max width 840px · 2 columns · gap 0px. Two connected offer cards, the first taller and the second vertically centered beside it.
- **recruiting-grid** (only for recruiting pages): max width 1080px · 4 columns · gap 15px · side padding 15px. Portrait-format animated role cards in compact rows.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 1.9px |
|  | community-cards | 15px |
|  | install-control | 16px |
|  | media-thumbnails | 5.6px |
| product comparison pages | offer-cards | 22.5px |
| recruiting pages | recruiting-cards | 22.5px |
| example and resource catalogs | filter-chips | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default canvas and card material.

**CSS:** `background: #ffffff; color: #0a0a0a`

**Observed:** The page remains bright through every chapter, including the ending; interface imagery supplies most dark regions.

**Transfer:** Let whitespace and thin rules distinguish sections instead of alternating background colors.

#### Ruled band · level 0

**Use:** Infrastructure chapters and page endings.

**CSS:** `background: #ffffff; border-top: 0.5px solid #d4d4d4; border-bottom: 0.5px solid #d4d4d4`

**Observed:** Full-width rules bracket content while its inner grid stays centered.

**Transfer:** Use for a chapter that needs separation without visual elevation.

#### Outlined card · level 1

**Use:** Community proof.

**CSS:** `background: #ffffff; border: 0.5px solid #d4d4d4; border-radius: 15px; box-shadow: none`

**Observed:** Thin edges remain subordinate to text and avatars.

**Transfer:** Use rounded outlines for human proof, not every feature paragraph.

#### Frosted subnavigation · level 2

**Only for:** multi-part product pages

**Use:** Secondary navigation beneath the main header.

**CSS:** `background: rgba(255,255,255,0.8); border-bottom: 0.5px solid #d4d4d4; backdrop-filter: blur(12px)`

**Observed:** A 51px light translucent strip holds compact product tabs.

**Transfer:** Reserve translucency for a persistent navigational layer.

#### Recruiting media veil · level 1

**Only for:** recruiting pages

**Use:** Text legibility over animated heatmap media.

**CSS:** `background: linear-gradient(rgba(0,0,0,0.5) 0%, rgba(0,0,0,0.1) 50%, rgba(0,0,0,0.7) 100%)`

**Observed:** Both the upper title and lower metadata receive dark backing while the middle retains color.

**Transfer:** Keep the veil as an overlay on actual artwork, not a replacement for it.

## Components

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: sticky; top: 0px; z-index: 20; height: 50px; background: #ffffff; box-shadow: 0px 0.5px 0px 0px #d4d4d4`

**Text style:** `body` — -apple-system 450 · 15px/1.5

**Observed:** A compact black wordmark sits left, text navigation follows, and small social icons plus Documentation search occupy the right. Content uses the page-container.

### Primary button

**Use:** Default highest-priority action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 7.5px; height: 38px; padding: 0px 13.1px; background: #0a0a0a; color: #ffffff; border-radius: 1.9px`

**Text style:** `action` — JetBrains Mono 450 · 15px/1.5 · uppercase

**Observed:** Usually paired with Secondary button. Labels stay short and no icon is necessary in the opening; deeper product actions can add a right chevron.

**States:** Declared: hover opacity 0.85; focus-visible solid 2px ink outline with 2px offset.

### Secondary button

**Use:** Low-friction alternative to the main action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 7.5px; height: 38px; padding: 0px 13.1px; background: transparent; color: #0a0a0a; border: 0.5px solid #d4d4d4; border-radius: 1.9px`

**Text style:** `action` — JetBrains Mono 450 · 15px/1.5 · uppercase

**Observed:** Same height and type as Primary button; the white interior makes the pair unequal in emphasis.

**States:** Declared: hover a 6% ink background wash; focus-visible solid 2px ink outline with 2px offset.

### Documentation search

**Use:** Compact navigation utility.

**CSS:** `display: inline-flex; align-items: center; gap: 7.5px; width: 210px; height: 34px; padding: 0px 7.5px; border: 0.5px solid #d4d4d4; border-radius: 1.9px; color: #525252`

**Text style:** `small` — -apple-system 450 · 13.1px/1.43

**Observed:** Search icon first, left-aligned label, then a tiny outlined slash key at the right.

**States:** Declared: hover border remains hairline gray and text becomes darker; focus-visible uses the same border with no outline.

### Install control

**Use:** Make the first implementation step tangible.

**CSS:** `position: relative; border: 0.5px solid #d4d4d4; border-radius: 16px; overflow: hidden`

**Text style:** `code` — JetBrains Mono 400 · 12.9px/1.6

**Observed:** A tabbed header with language icons, active-language text and right-aligned copy icon sits over a short command. The header has a bottom hairline; the whole control is about 104px tall. Syntax color is sparse and the field stays white.

**Transfer:** Use a real short installation command or equally concrete setup action, not a decorative code dump.

### Community card

**Use:** Human proof in a masonry wall.

**CSS:** `display: block; background: #ffffff; border: 0.5px solid #d4d4d4; border-radius: 15px; padding: 18.8px`

**Text style:** `body` — -apple-system 450 · 15px/1.5

**Observed:** Avatar, community-name and small handle form a compact header with a network glyph at the far right. Natural-length quotes follow; some include rounded interface media and a dark translucent circular play control. Heights vary rather than lining up into uniform rows.

**States:** Declared: hover border-color remains the hairline gray.

### Footer

**Use:** Shared substantial ending, not a dark conversion banner.

**CSS:** `background: #ffffff; border-top: 0.5px solid #d4d4d4; color: #525252`

**Text style:** `body` — -apple-system 450 · 15px/1.5

**Observed:** The page-container starts with 75px top padding. A 300px identity and release-notes subscription column sits left of four link columns, separated by a 60px gap. Below, a ruled centered backer-logo row precedes another ruled bottom line with copyright left and legal links right. Overall desktop height is 643px; the small subscription button is 30px tall and uses sans small text.

**Transfer:** End with a useful release/update subscription, navigation and a restrained monochrome affiliation row appropriate to the new product.

### Spectral meeting button

**Use:** High-touch conversion inside a capability chapter or closing call.

**CSS:** `position: relative; display: inline-flex; align-items: center; justify-content: center; height: 38px; padding: 0px 13.1px; background: #000000; color: #ffffff; border-radius: 1.9px; overflow: hidden`

**Text style:** `action` — JetBrains Mono 450 · 15px/1.5 · uppercase

**Observed:** A moving spectral video is enlarged fivefold and clipped to the small rectangle, giving a concentrated blue-green or warm rainbow fill beneath the white label. It contrasts with an adjacent dark self-service action.

**States:** Declared: focus-visible solid 2px ink outline with 2px offset.

**Transfer:** Reuse the luminous material language inside one compact high-touch action, rather than coloring the whole action system.

### Gallery item

**Only for:** example and resource catalogs

**Use:** A browsable, technically labeled proof unit.

**CSS:** `display: block; width: 100%; border-radius: 11.3px`

**Text style:** `technical-heading` — JetBrains Mono 500 · 18px/1.33 · tracking 0.0125em · uppercase

**Observed:** A 4:3 thumbnail has a 0.5px outline and 5.6px corners, followed after 15px by the mono uppercase title, then a small paragraph and tiny inline metadata tags. The outer item is not a filled card. Live items have a dark translucent badge on the image.

### Filter chip

**Only for:** example and resource catalogs

**Use:** Compact catalog filtering beneath the opening.

**CSS:** `display: inline-flex; align-items: center; gap: 5.6px; padding: 3.8px 9.4px; border: 0.5px solid #d4d4d4; border-radius: 9999px; color: #525252`

**Text style:** `caption` — -apple-system 500 · 12.8px/1.5

**Observed:** Chips sit in a sticky white filter strip beside a 200px by 34px filter field with 7.5px corners. A green status dot identifies the live filter; other chips use tiny tag glyphs.

**States:** Declared: hover border stays hairline gray and text becomes ink.

### Offer card

**Only for:** product comparison pages

**Use:** Explain two complementary product modes.

**CSS:** `display: flex; flex-direction: column; justify-content: center; background: #ffffff; border: 0.5px solid #d4d4d4; border-radius: 22.5px; padding: 37.5px`

**Text style:** `heading` — -apple-system 500 · 33.8px/1.15 · tracking -0.01em

**Observed:** Category caption, title, paragraph, setup control where relevant, concise arrow-led feature list and actions. The first card is taller; the adjoining card is shorter with rounded outer right corners and no competing shadow.

### Role card

**Only for:** recruiting pages

**Use:** Present open roles as vivid media objects.

**CSS:** `display: flex; position: relative; flex-direction: column; aspect-ratio: 3 / 4; overflow: hidden; border-radius: 22.5px`

**Text style:** `technical-heading` — JetBrains Mono 500 · 18px/1.33 · tracking 0.0125em · uppercase

**Observed:** A full-bleed abstract heatmap video sits beneath Recruiting media veil. White uppercase title is pinned near the top, while department, location and employment metadata sit near the bottom with small outline icons. Inner padding is 22.5px.

## Imagery and graphics

### Spectral object stage

**Use:** Signature opening visual for a new landing page.

**Observed:** A softly lit white robot arm with dark joints anchors the lower center; thin translucent rainbow sheets emerge beside it and sweep upward toward the right edge. Blue, cyan, green, yellow and rose remain distinct at the base, then become misty and dissolve into white at their upper ends. The art occupies the lower/right stage without a frame, leaving the centered headline readable.

**Transfer:** Use a neutral object that represents the new product's transformation, with the same spectral outflow and white-on-white lighting. If a polished 3D object is unavailable, use a simple white layered geometric form and a carefully drawn ribbon fan.

**Build:** Create an SVG spanning the stage: draw 6–8 adjacent closed cubic-Bezier sheets from a common lower-center origin, bending upward and outward to the right. Give each a blue-to-rose spectrum position, translucent edge shading, and a mask that fades the upper tips to zero alpha. Place a white/gray SVG or 3D neutral object above the shared origin, adding only soft local occlusion at joints; retain clean white around the text.

### Floating layer sculpture

**Use:** Signature luminous material repeated at a capability chapter.

**Observed:** Three small isometric rounded square slabs float apart on white. The upper slabs are off-white with shaded gray sidewalls, while the bottom slab has a warm spectral top and mint, yellow and coral edges. The actual sculpture is compact within an 840px by 210px stage.

**Transfer:** Represent a new product's underlying layers with the same suspended stack, rather than using a generic flat icon.

**Build:** Draw three identical rounded-square SVG planes in an isometric projection, separated vertically. Add shallow extruded sidewalls and soft gray contact shading to the upper white planes. Color only the bottom plane with a warm-to-cool multistop gradient and luminous rim; preserve ample white around it.

### Working interface media

**Use:** Feature rows, editorial spotlights and catalog thumbnails.

**Observed:** Real interfaces show point clouds, depth maps, plots, cameras and annotated scenes. Dark application panels and false-color scientific graphics are retained rather than harmonized into a pastel marketing palette. Tiny square previews are 120px; catalog thumbnails are 4:3; the editorial spotlight is tall and combines a scene above two heatmaps.

**Transfer:** Use authentic task outputs from the new product. Keep scientific or application color inside the media; a minimum version is a legible mini-interface with one meaningful visualization, not a generic dashboard montage.

### Architecture loop diagram

**Only for:** technical product explanations

**Use:** Explain how capabilities and infrastructure connect.

**Observed:** A broad white diagram uses thin black orthogonal connectors, a top feedback loop, four process boxes and lower rows of miniature media/table blocks. A left label rail uses uppercase mono headings. Green and violet marks animate the otherwise monochrome data field.

**Transfer:** Map the new product's lifecycle using the same thin-line engineering grammar and compact data marks.

**Build:** Use SVG 1px orthogonal paths and arrowheads around a row of four outlined process boxes. Below, arrange small 1px-radius thumbnail frames and repeated gray line clusters like records; highlight a small minority with green bars or violet squares. Keep labels in a separate left rail.

### Heatmap role media

**Only for:** recruiting pages

**Use:** Animated backing for portrait role cards.

**Observed:** Soft blue and teal fields carry horizontal red-orange light nodes, occasionally a yellow-green periodic grid. The result resembles blurred scientific simulation data, not office photography.

**Transfer:** Create abstract signals related to the work, with darkened edges so reversed labels remain readable.

**Build:** Layer a desaturated blue/teal field with repeated radial orange cores and a red horizontal wave, blur the pattern about 12px and stretch it to fill each portrait card. Add Recruiting media veil; vary wave phase or node spacing across cards.

### Dotted team globe

**Only for:** culture and recruiting pages

**Use:** A distinctive closing visual before the shared Footer.

**Observed:** A huge monochrome globe of tiny gray dots rises from below and is cut off by the section edge. White oceans nearly disappear into the page. Small black activity bubbles, pins and occasional emoji reactions sit over the globe.

**Transfer:** Show distributed activity or community presence with monochrome geographic or network dots; avoid a colorful map dashboard.

**Build:** Project evenly spaced longitude/latitude sample points onto a sphere, retaining land points in gray with depth-based opacity. Render as SVG circles or canvas dots against white. Place compact black rounded speech bubbles over a few pins, and clip the sphere to a 720px-high overflow-hidden band.

### Icons

**Observed:** Small outline utility icons use 2px rounded strokes at 14px, 16px or 18px. Social icons occupy 18px boxes; gallery metadata uses tiny 10px filled tag glyphs. Color follows adjacent gray or reversed white text.

**Transfer:** Choose one rounded-stroke outline family for actions and utilities. Reserve solid mini-glyphs for tags and identity marks rather than enlarging them into colorful feature badges.

## Section recipes

How recurring sections are built.

### First screen: Spectral promise opening

**Observed:** A 50px Navigation tops an 830px white stage. The centered display starts 60px below the header and occupies a narrow two-line block about 563px wide. A 630px lead follows after 18.8px, then Primary button and Secondary button after 26.3px with a 7.5px gap. Behind and below these sits Spectral object stage: the neutral object anchors the lower center, the ribbon fan rises toward and beyond the right edge. Back-to-front layers are white canvas, luminous object scene, then crisp text and actions. Within the first 900px, the complete promise, support, actions and main object are visible; only the beginning of the next technical chapter peeks at the bottom.

**Transfer:** Keep the headline-to-object scale relationship and asymmetry for a different product, using the SVG ribbon fallback if necessary. Catalog pages instead open with a two-line display, lead and filter strip; technical overview pages use a text-only promise plus a compact proof strip; recruiting pages use a centered aspirational display and explanatory prose before role media.

**Avoid:** Do not center a giant rainbow blob behind the letters, put the whole opening inside a rounded card, or substitute a full-bleed dark dashboard for the white object stage.

**Text style:** `display` — -apple-system 450 · 63.8px/1 · tracking -0.01em

### Toolchain split

**Observed:** A 960px technical-split places a 45px gray-to-ink statement and body text above Install control on the left. On the right, three 120px media previews pair with technical-heading and body paragraphs. Small repository contribution rows provide additional activity proof.

**Transfer:** Translate a broad promise into concrete operations and a real first step; use compact examples rather than three generic feature cards.

**Text style:** `heading-lg` — -apple-system 500 · 45px/1.1 · tracking -0.02em

### Luminous capability band

**Observed:** Ruled band combines Floating layer sculpture, a small outlined product label, a centered heading-lg and lead. Four unboxed feature columns each carry a small sans category, technical-heading and body. A Spectral meeting button closes the band.

**Transfer:** Use the luminous layer device to give an abstract underlying service a tangible form; choose capabilities that describe what the reader can actually do.

**Text style:** `heading-lg` — -apple-system 500 · 45px/1.1 · tracking -0.02em

### Editorial spotlight

**Observed:** An 840px editorial-split pairs 375px-wide tall interface media with an eyebrow, heading, body and Secondary button. Copy is vertically centered beside the image rather than stretched across the page.

**Transfer:** Make one detailed story or demonstration feel like an editorial feature instead of another card in a grid.

**Text style:** `heading` — -apple-system 500 · 33.8px/1.15 · tracking -0.01em

### Community proof field

**Observed:** A centered heading-lg and lead introduce a four-column row of compact project endorsements with mono labels. Below, Community cards form a four-column masonry field with 15px gutters, capped as a long visual wall. Text and authentic small media dominate instead of oversized quote marks.

**Transfer:** Use genuine varied-length user or practitioner proof; preserve natural card heights and compact author headers.

**Text style:** `heading-lg` — -apple-system 500 · 45px/1.1 · tracking -0.02em

### Useful institutional ending

**Observed:** Footer combines identity, social utilities, a release-update subscription, four navigation columns, a centered monochrome backer strip and restrained legal baseline. White material, thin horizontal rules and small type continue the page rather than switching to a dark closing scene.

**Transfer:** Make the ending operational and credible. Include equivalent affiliations only when relevant; preserve the multi-level ruled layout.

### Catalog chapter

**Only for:** example and resource catalogs

**Observed:** Each chapter has 75px vertical padding and a bottom hairline. A 630px text block puts a gray category and black outcome heading at the same 33.8px scale, then body after 15px. Gallery items begin after 45px in three columns with 30px gutters. A sticky filtering strip persists under Navigation.

**Transfer:** Group demonstrations by user task, letting titles and short metadata support scanning without enclosing every item in a painted box.

**Text style:** `heading` — -apple-system 500 · 33.8px/1.15 · tracking -0.01em

### Proof strip and engineering chapter

**Only for:** technical product pages

**Observed:** A compact three-part strip follows the promise: a number, a row of language/tool icons, and a short scope phrase. Values use heading, captions use caption; 1px vertical dividers and 30px side insets separate cells. A centered two-tone heading-lg and lead introduce Architecture loop diagram below.

**Transfer:** Use only meaningful proof and a concrete system model; a qualitative capability can occupy one proof cell alongside numbers.

**Text style:** `heading` — -apple-system 500 · 33.8px/1.15 · tracking -0.01em

### Paired modes and comparison

**Only for:** product comparison pages

**Observed:** A centered heading-lg pair and lead precede Offer cards in an 840px pair. Below, a centered heading and lead introduce a wide hairline comparison table: short row labels at left and two columns of concise check-marked content.

**Transfer:** Explain complementary ways to use one system, then resolve what changes and what stays the same; do not imply competing price tiers unless that is the actual model.

**Text style:** `heading-lg` — -apple-system 500 · 45px/1.1 · tracking -0.02em

### Recruiting invitation and activity ending

**Only for:** recruiting pages

**Observed:** A centered two-line display and long-form support precede a four-column Role card grid. A later centered culture paragraph introduces Dotted team globe, clipped above Footer. There is no extra sales CTA between globe and footer.

**Transfer:** Combine an aspirational invitation with concrete roles and a visual expression of how people work together.

**Text style:** `display` — -apple-system 450 · 63.8px/1 · tracking -0.01em

### Closing action

**Only for:** product and catalog landing pages

**Observed:** A centered heading-lg and 19px lead sit over two compact actions on white. Catalog closings use 75px padding and a dark/outline pair; product closings use 120px padding and pair Primary button with Spectral meeting button. Footer follows across a hairline.

**Transfer:** Restate the practical next step with both self-service and human assistance where appropriate, without introducing a new visual theme.

**Text style:** `heading-lg` — -apple-system 500 · 45px/1.1 · tracking -0.02em

## Page flow

**Storyline:** promise → tangible product model → concrete operations → detailed proof → human or ecosystem validation → practical next step → useful institutional ending

### Broad product marketing landing page

1. **promise** — Centered promise over the luminous off-axis object stage and paired actions.
2. **concrete operations** — Split statement, installation control and small feature demonstrations.
3. **capability chapter** — Floating layer sculpture, centered explanation and four technical feature columns.
4. **detailed proof** — One editorial media spotlight.
5. **community validation** — Project endorsements followed by a long masonry wall of authentic practitioner voices.
6. **institutional ending** — Direct transition from community proof to the shared white footer, subscription, affiliation row and legal line.

**Transfer:** Use an evocative opening but earn trust quickly with a working entry point and evidence of actual usage. A separate final CTA is not necessary when the page already provides actions throughout.

### Recruiting and culture invitation

1. **aspiration** — Two-line centered invitation with a longer explanatory paragraph.
2. **available opportunities** — Portrait heatmap role cards with practical metadata.
3. **culture proof** — A distributed-work paragraph and large dotted activity globe.
4. **institutional ending** — Globe ends immediately above the common white footer.

**Transfer:** Show how people work and what roles are available instead of repurposing a sales funnel.

### Deep browsable demonstration library

1. **orientation** — Centered display and lead followed by sticky search and chips.
2. **categorized proof** — Repeated gray-category/ink-outcome heading pairs and media-first three-column grids across several task families.
3. **next step** — A compact centered install invitation and two actions after the last gallery item.
4. **institutional ending** — The same white subscription-and-link footer completes the long catalog.

**Transfer:** Allow library length to follow the actual content. Retain category introductions, consistent media ratios and filters instead of inventing a fixed number of sections.

### Explain a technical product architecture and its delivery modes

1. **promise** — Text-first centered promise and paired actions beneath a secondary navigation strip.
2. **compact proof** — Three cells mix a usage number, implementation ecosystem and scope statement.
3. **system model** — Two-tone headline and broad thin-line lifecycle diagram.
4. **offering explanation** — Asymmetric connected product cards with feature lists and setup control.
5. **objection handling** — A concise comparison table explains which underlying infrastructure changes.
6. **closing call** — Centered practical outcome with self-service action and spectral meeting button.
7. **institutional ending** — The shared white footer, backer row and legal baseline.

**Transfer:** Explain the system before selling the variants, then settle deployment or usage questions with a plain comparison.

## Writing

Technically fluent, direct and confident without sounding grandiose. Product prose explains operations and constraints; warmth comes from reader-focused phrasing and real community voices rather than marketing enthusiasm.

**Do not copy:** Do not reuse Rerun names, wordmarks, product names, customer or investor identities, repository names, numerical claims, quoted testimonials or proprietary artwork. Source examples illustrate syntax and tone only; replace them with truthful material for the new product.

- **Addressing the reader:** Speak to the reader as you and your when explaining a task; describe the product in plain declarative sentences. Use we mainly for company and culture language.
- **Rhythm:** Short outcome headlines alternate with denser, specific explanatory sentences. Support copy often uses two sentences: the mechanism first, the range or benefit second. Actions are terse verbs; technical lists are intentionally compact.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product's underlying category and who or what it serves. | 5–9 words | “The Data Layer for Physical AI” |
| Section heading | Use an operational outcome or a paired setup and conclusion. | 4–10 words | “Infrastructure that powers your data loop”<br>“One data layer.”<br>“Two parts.” |
| Capability heading | Verb-led technical action, uppercase through styling. | 2–7 words | “Visualize everything”<br>“Refine your data without copies” |
| Support | Explain a real mechanism, then describe how it fits into the reader's work. | 15–40 words | “A flexible framework to build with rather than a platform you can't change.”<br>“Install the SDK in one line, log a few things, and open the viewer.” |
| Primary action | Short verb plus object or destination. | 2–4 words | “Get started”<br>“Read the docs”<br>“Book a meeting” |
| Recruiting invitation | Invite the reader to make something consequential, then ground the invitation in the work. | 8–12 words | “Make the tools the future will be built with” |

**Words and phrasing to use:** build; understand; improve; log; query; transform; inspect; stream; your; same; without; from … to …

**Avoid:** revolutionary; game-changing; unlock limitless potential; seamless synergy; best-in-class; effortlessly magical

**Rules:**

- Name operations and implementation surfaces before abstract benefits.
- Contrast freedom with lock-in using concrete constraints, not vague superiority.
- Use category labels to orient, outcome headings to persuade, and paragraphs to explain.
- Keep exuberance and emoji in attributed human voices rather than the product narrator.
- For new domains, replace specialist vocabulary with equally specific terms from the actual workflow.

## Do's and Don'ts

### Do

- Keep display at 63.8px/1 and weight 450; balance lines rather than emboldening the promise.
- Keep the surrounding canvas white and isolate spectral color in art, small marks and the meeting action.
- Use 38px mono actions with 1.9px corners and a 7.5px gap.
- Use 0.5px neutral rules for section boundaries and card outlines.
- Use 18px uppercase mono labels for capabilities and technical examples.
- Stage small demonstrations at 120px while giving editorial media a distinct larger format.
- Preserve the luminous object/ribbon and floating-layer material language even with simplified SVG artwork.
- Keep footer subscription, affiliation and legal levels separated by white space and thin rules.

### Don't

- Do not turn every button into a pill; full rounding belongs to filter chips and tiny media controls.
- Do not introduce elevated gray cards or drop-shadow stacks in place of the white outlined material.
- Do not color navigation links with green or violet; those hues identify small technical marks.
- Do not use uppercase sans for all headings; large promises remain mixed-case system grotesk.
- Do not stretch community quotes into equal-height testimonial slides; their natural height is part of the proof field.
- Do not recolor real interface outputs into a coordinated pastel palette.
- Do not enlarge proof numbers beyond the 33.8px heading tier into a competing hero.
- Do not turn the shared ending into a black mega-footer; keep its white 643px desktop structure.

## Motion and responsive

### Motion

**Observed:**

- Controls declare color/background/border transitions of 0.15s with cubic-bezier(.4,0,.2,1); opacity transitions also use 0.15s.
- Technical loop media declares linear marquee motion; its duration is not specified here.
- Recruiting word reveals declare 2s cubic-bezier(0.16,1,0.3,1) and grouped fade-up reveals declare 0.9s with the same curve.
- Globe activity words declare 0.32s cubic-bezier(0.2,0.8,0.2,1); bubbles declare 0.22s and reactions use a 0.32s overshooting curve.
- The spectral meeting action uses moving video clipped behind its text; luminous art also supplies movement without shifting the surrounding layout.

**Transfer:**

- Keep interface responses short and subordinate; let the spectral material and miniature demonstrations carry the distinctive motion.
- Animate culture activity within the globe rather than making the whole page bounce.

**Unknown:**

- Exact timing and trajectories of the opening 3D scene and video loops are unspecified.
- Whether all declared entrance effects run in every navigation path is unknown.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1100px, 1280px and 1536px.
- The opening desktop art container is hidden below the medium breakpoint; at desktop its height follows clamp(740px, calc(56.25vw + 20px), 920px).
- Opening text switches from left alignment to centered at the medium breakpoint. The technical split uses a column layout before its larger breakpoint.
- Catalog grids declare two columns at the small breakpoint and three at the large breakpoint; community columns increase with width.

**Transfer:**

- On narrow screens keep the promise and compact actions legible first; use a small static spectral device within the content if the desktop stage is hidden.
- Stack the technical split and offer pair, keeping the install control next to its explanation; retain gallery media ratios and technical labels.

**Unknown:**

- Rendered mobile spacing, type sizes, menu behavior and globe framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
