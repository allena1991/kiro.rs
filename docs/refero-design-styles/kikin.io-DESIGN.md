# Kikin — forest-green poster optimism

## Overview

A bold, outdoorsy marketing style that gives serious products the energy of a campaign poster. Forest green and warm cream dominate, with electric green calls to action, cyan interludes and occasional yellow declarations. Heavy, tightly stacked display sans meets matter-of-fact grotesk copy, hand-drawn landscapes, collectible badges and photographic product collages; spacious chapters contain deliberately dense demonstrations.

### Essentials

- Headlines behave like stacked campaign posters: Deacon 900, uppercase, 136.8px/0.8 for the opening and 100.8px/0.8 for major declarations, both with -1.5px tracking.
- The opening is a landscape, not a floating software card: centered cream-and-green headline above a full-width illustrated scene, with a 547.2px support column and one 57px-high action visible in the first 900px.
- Conversion controls are bright rounded rectangles rather than pills: #55dd4a, 10px radius, 16px uppercase Graphik 500; quieter outlined controls share the shape.
- Color is allocated in chapters: forest and cream occupy most of the page, cyan becomes a full-width transition, and electric green punctuates headlines, actions and diagram feedback rather than washing every panel.
- Technical proof lives inside nature: 680px-wide, 8px-radius landscape photographs carry flat cream and forest interface overlays; keep a landscape-backed explanatory diagram even when a real interface is unavailable.
- Collectible badge graphics and a monumental illustrated closing call are signature devices: tilted circular or die-cut emblems frame statements, while a 100.8px cream-and-yellow closing headline rises above a landscape that fades into the forest footer. Use original symbols and a simplified hand-drawn environment when bespoke artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest | `#122315` | `--color-forest` | background, text, border, surface | Default dark canvas, dark type on cream, and structural rules. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric leaf | `#55dd4a` | `--color-green` | action, accent, text | Primary buttons, highlighted headline lines, numbered discs and live feedback. |
| Closing yellow | `#ffed52` | `--color-yellow` | text, accent | The second half of the monumental closing statement, with related accents in illustrated artwork. |
| River cyan | `#73d3eb` | `--color-cyan` | background, accent | Full-width logo and qualification bands and the frame around photographic collage. |
| Light leaf | `#77e46e` | `--color-hover-green` | border, action | Outline carousel controls and primary-button hover. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted forest | `#566053` | `--color-muted-forest` | text | Unhighlighted lines of the large dark-background manifesto. |
| Warm cream | `#f3ede4` | `--color-cream` | background, text, surface | Light chapters and text on forest; dark-surface supporting copy also uses this at 60% opacity. |
| White | `#ffffff` | `--color-white` | text | Footer utility links and hover arrows. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical product explainers | Technical signal | `#43de35` | `--color-technical-green` | accent, background, text, action | More saturated green; also fills a complete process chapter. |
| technical product explainers | Technical sky | `#9bd7e4` | `--color-technical-sky` | background | Cool full-width demonstration chapters. |
| technical product explainers | Technical ink | `#0a1f13` | `--color-technical-ink` | background, text | Dark chapters and primary ink. |
| technical product explainers | Technical forest | `#0d2213` | `--color-technical-dark` | background, surface | Technical opening, dark product window and closing. |
| technical product explainers | Technical body gray | `#333333` | `--color-technical-body` | text | Paragraphs on light technical chapters. |
| technical product explainers | Technical cream | `#f4f1e8` | `--color-technical-cream` | text | Dark-stage display text and translucent dividers. |
| technical product explainers | Technical paper | `#f7f6f2` | `--color-technical-paper` | background, text | Lighter, less beige alternate canvas. |
| technical product demonstrations | Sage edge | `#bed0c5` | `--color-demo-edge` | border | Thin product-window outlines and row separators. |
| technical product demonstrations | Demo paper | `#fbfbf9` | `--color-demo-card` | surface | Light product-window backing. |

## Typography

- **Deacon** — Uppercase headlines, section titles, FAQ questions and emphatic numerals. Very heavy, broad, blunt sans with irregular human warmth; short ascenders and tightly packed capital lines. If unavailable, use **Archivo Black**. Use the heavy cut and preserve close line spacing; tune width before increasing tracking. Font stack: "Deacon", "Archivo Black", Graphik, system-ui, sans-serif.
- **Graphik** — Paragraphs, navigation, actions, quotes and captions. Restrained geometric grotesk, mostly regular with medium controls. If unavailable, use **DM Sans**. Use 400 and 500; maintain the compact x-height-to-line-height relationship. Font stack: "Graphik", "DM Sans", system-ui, sans-serif.
- **ui-monospace** (only for technical product explainers) — Tiny chapter markings and technical metadata outside dense interface details. Plain utilitarian monospace that contrasts with oversized poster lettering. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Deacon | 900 | 136.8px | 0.8 | -0.011em, uppercase | size 9.5vw | Default first-screen headline, centered with separately colored lines. |
| heading-lg | Deacon | 900 | 100.8px | 0.8 | -0.0149em, uppercase | size 7vw | Major statements, standard secondary-page hero, FAQ heading and closing call. |
| manifesto | Deacon | 900 | 72px | 0.8 | -0.0208em, uppercase | size 5vw | Multi-line dark-background statement surrounded by badges. |
| heading | Deacon | 700 | 57.6px | 0.85 | -0.026em, uppercase | size 4vw | Numbered capability and process chapters. |
| qualification-title | Deacon | 900 | 36px | 0.85 | -0.0417em, uppercase | size 2.5vw | Three-column cyan qualification strip. |
| faq-question | Deacon | 900 | 32px | 0.85 | normal, uppercase | fixed | Accordion questions. |
| quote | Graphik | 400 | 24px | 1.2 | -0.04em | fixed | Testimonial prose, clearly smaller than the adjacent display title. |
| body | Graphik | 400 | 16px | 1.4 | normal | fixed | Main support copy, usually two to four short lines. |
| action | Graphik | 500 | 16px | 1.25 | normal, uppercase | fixed | Main and secondary buttons. |
| caption | Graphik | 400 | 16px | 1.4 | -0.02em | fixed | Testimonial attribution. |
| number | Graphik | 500 | 15px | 17px | normal, uppercase | fixed | Two-digit chapter markers. |
| small-action | Graphik | 500 | 14px | 20px | normal, uppercase | fixed | Compact header actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| technical product explainers | technical-monument | Deacon | 900 | 122.4px | 0.88 | -0.035em, uppercase | size clamp(3.2rem, 8.5vw, 8rem) | Closing declaration or one huge product result. |
| technical product explainers | technical-heading | Deacon | 900 | 86.4px | 0.92 | -0.03em, uppercase | size clamp(2.6rem, 6vw, 5.7rem) | Tall left-aligned feature headlines. |
| technical product explainers | technical-display | Deacon | 900 | 64px | 0.9 | -0.03em, uppercase | size clamp(2rem, 4.5vw, 4rem) | Compact promise above a live product window. |
| story indexes | story-title | Deacon | 700 | 50.4px | 0.85 | -0.0298em, uppercase | size 3.5vw | Editorial customer-story headlines. |
| technical product explainers | technical-stat | Deacon | 900 | 36px | 40px | -0.02em, uppercase | fixed | Short word-valued metrics in the closing proof strip. |
| technical product explainers | technical-body | Graphik | 400 | 18px | 28px | normal | fixed | Explanatory paragraphs under tall feature headlines. |
| technical product explainers | technical-eyebrow | ui-monospace | 700 | 10px | 1.5 | normal, uppercase | fixed | Chapter marking above technical headlines. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headlines stack unusually tightly: 0.8 for the largest public-facing declarations, 0.85 for feature titles. Keep the weight, width and close leading together rather than substituting a narrow condensed face.
- The default display tracking stays -1.5px across several sizes. The technical variant instead uses proportional negative tracking and taller leading.
- Most explanatory text stays at 16px while headlines become monumental; do not enlarge every secondary role to match the title.
- Color changes follow complete headline phrases or lines, not individual decorative letters.

## Layout

**Density:** Airy chapter spacing surrounds compact prose and tightly packed display lines; interface demonstrations remain denser than the marketing canvas.

### Spacing

| Value | Use |
| --- | --- |
| 12px | Header action gaps and compact component spacing. |
| 16px | Footer grid gaps and small content grouping. |
| 20px | Header vertical padding and accordion vertical padding. |
| 24px | Support-to-action gap in the opening and testimonial grid gap. |
| 32px | Feature-row vertical padding, number-to-heading separation and FAQ row gaps. |
| 40px | Desktop page gutters, cyan collage frame and footer side padding. |
| 80px | FAQ chapter top and bottom breathing room. |
| 88px | Illustrated closing-call top padding. |
| 100px | Testimonial chapter vertical padding. |
| 120px | Bottom spacing after the light capability sequence. |
| 140px | Dark calculator chapter top padding. |
| 180px | Centered light manifesto chapter top padding. |
| 144px | Vertical chapter padding in technical explainers. |

### Containers and grids

- **desktop canvas**: max width 1440px · side padding 40px. Edge-to-edge colored bands with 1360px of usable width at a 1440px viewport.
- **opening support**: max width 547px. Centered narrow support paragraph beneath a much wider title.
- **feature split**: 2 columns · gap 80px. Left text approximately 598px wide, right media 680px wide within the desktop gutters; title and number sit high, paragraph sits near the bottom.
- **testimonial split**: 2 columns · gap 24px. Image takes approximately one third of the width; the title, quote, credit and arrow controls take the remaining two thirds.
- **cyan strip**: 3 columns · gap 0px. Equal cells with continuous top and bottom rules and vertical dividers.
- **footer grid**: 3 columns · gap 16px · side padding 40px. Proportions 2:1:1: impact/contact block, company information, and stacked utility links.
- **technical container** (only for technical product explainers): max width 1152px · side padding 40px. Centered content creates deeper desktop insets than the default layout; two-column demos use 80px or 96px gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 10px |
|  | media panels | 8px |
|  | number discs | 20px |
|  | carousel arrows | 50% |
|  | social links | 9999px (pill) |
| technical product demonstrations | technical subcards | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| technical product demonstrations | technical window | `0px 24px 70px -34px rgba(10,31,19,0.28)` | Soft low shadow under light product windows; not under ordinary editorial rows. |

### Surfaces

#### Forest canvas · level 0

**Use:** Default opening, calculator, manifesto and closing chapters.

**CSS:** `background: #122315; color: #f3ede4`

**Observed:** Flat uninterrupted dark green, not black; illustration merges into the same ground.

**Transfer:** Use long fields of this color to let cream type and bright actions carry the hierarchy.

#### Cream canvas · level 0

**Use:** Capabilities, testimonials, FAQs and story-index backgrounds.

**CSS:** `background: #f3ede4; color: #122315`

**Observed:** Warm matte paper with no texture overlay.

**Transfer:** Alternate whole chapters rather than surrounding every paragraph with a card.

#### Cyan band · level 0

**Use:** Logos, photographic collage frame and three-column qualification strip.

**CSS:** `background: #73d3eb; color: #122315`

**Observed:** A saturated flat band bounded by thin forest rules in the three-column treatment.

**Transfer:** Use this as a distinct chapter color, with 40px framing around a large picture.

#### Dark outlined panel · level 1

**Use:** Calculator and explanatory interactive panel on forest.

**CSS:** `background: #122315; border: 1px solid rgba(243,240,236,0.3); border-radius: 8px`

**Observed:** The interior stays on the surrounding dark canvas; a horizontal rule separates inputs from an oversized green result.

**Transfer:** Group a small number of meaningful inputs above one result rather than filling it with dashboard chrome.

#### Technical window · level 1

**Only for:** technical product demonstrations

**Use:** Auditable reports, charts and process demonstrations.

**CSS:** `background: #fbfbf9; border: 1px solid #bed0c5; border-radius: 8px; box-shadow: 0px 24px 70px -34px rgba(10,31,19,0.28)`

**Observed:** Thin sage rules subdivide light paper; compact metadata contrasts with a huge result or simplified chart.

**Transfer:** Show the anatomy and consequence of the product, without reproducing an entire application.

#### Technical signal chapter · level 0

**Only for:** technical product explainers

**Use:** A single high-energy process chapter.

**CSS:** `background: #43de35; color: #0a1f13; padding: 144px 40px`

**Observed:** Bright flat green carries headline, paragraph, a light demo and four numbered cells.

**Transfer:** Reserve this stronger treatment for a central mechanism, not every conversion block.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #55dd4a; color: #122315; border-radius: 10px; padding: 16px 24px 15px; min-height: 57px`

**Text style:** `action` — Graphik 500 · 16px/1.25 · uppercase

**Observed:** Single centered text label without an arrow; header variant uses 14px type, 9px 16px padding and a 44px height.

**States:** Declared: hover background #77e46e and color #122315; focus-visible not specified; active background #3b9b34. Transition 0.2s.

### Secondary button

**Use:** Quieter action on forest, including the illustrated closing call.

**CSS:** `background: #122315; color: #f3ede4; border: 1px solid rgba(243,240,236,0.3); border-radius: 10px; padding: 14px 24px; min-height: 50px`

**Text style:** `action` — Graphik 500 · 16px/1.25 · uppercase

**Observed:** Same blunt rounded-rectangle construction as the bright action; no appended chevron.

**States:** Declared: hover background rgb(32, 47, 34); focus-visible not specified; active background rgb(45, 60, 47); border remains 1px solid rgba(243,240,236,0.3).

### Fixed navigation

**Use:** Persistent site identity, compact navigation and conversion controls.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 86px; padding: 20px 40px; background: #122315; color: #f3ede4; z-index: 5`

**Text style:** `small-action` — Graphik 500 · 14px/20px · uppercase

**Observed:** Wordmark left, small uppercase links centered, outlined login and green conversion action right with 12px gap. The cream-background variant reverses the wordmark and text to forest; navigation links use 0.3px tracking.

**Transfer:** Keep the public-facing navigation short enough to preserve the large central opening.

### Number disc

**Use:** Anchor capability chapters and connect process steps.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 40px; height: 40px; background: #55dd4a; color: #122315; border-radius: 20px; margin-bottom: 32px`

**Text style:** `number` — Graphik 500 · 15px/17px · uppercase

**Observed:** Two digits centered in a green circle above the heading. In a dark process timeline, inactive discs are muted and a thin vertical line connects them.

### Capability row

**Use:** One benefit paired with a substantial demonstration.

**CSS:** `display: flex; justify-content: space-between; background: #f3ede4; border-bottom: 1px solid rgba(18,35,21,0.48); padding: 32px 0px`

**Text style:** `heading` — Deacon 700 · 57.6px/0.85 · tracking -0.026em · uppercase

**Observed:** Number disc and title at the top of the left column, support at its bottom, landscape-backed media across the right half. The media has 8px corners.

**Transfer:** Write one concise benefit and demonstrate one mechanism per row.

### FAQ row

**Use:** Objection handling in a cream chapter.

**CSS:** `background: #f3ede4; border-bottom: 1px solid rgba(18,35,21,0.48); padding: 20px 32px 20px 0px; min-height: 88px`

**Text style:** `faq-question` — Deacon 900 · 32px/0.85 · uppercase

**Observed:** Uppercase question left, thin plus sign right; rows are separated by 32px. A vertical category menu occupies the left side of the section, while the question column is 770px wide.

**Transfer:** Keep answers below their own question instead of replacing the column with cards.

### Carousel arrow

**Use:** Testimonial navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 64px; height: 64px; border: 1px solid #77e46e; border-radius: 50%`

**Observed:** Two separate small arrow glyphs inside generously sized outline circles, aligned below the quote area.

**States:** Declared: hover color rgb(255, 255, 255), background #55dd4a and border-color #55dd4a; focus-visible not specified. Transition 0.3s.

### Footer columns

**Use:** Practical contact and navigation beneath the illustrated call.

**CSS:** `display: grid; grid-template-columns: 2fr 1fr 1fr; gap: 16px; padding: 0px 40px 40px; color: #f3ede4`

**Text style:** `body` — Graphik 400 · 16px/1.4

**Observed:** The widest cell holds a compact outlined impact strip and a large contact link beside a green symbol. Company details occupy the middle; utility links and two outlined social pills occupy the right. A final horizontal rule precedes low-contrast legal text.

**Transfer:** Keep contact, entity details and navigation separate; use only substantiated impact data.

### Story tile

**Only for:** story indexes

**Use:** Editorial customer or project stories.

**CSS:** `padding: 20px 20px 32px 40px; border-right: 1px solid rgba(18,35,21,0.48); border-bottom: 1px solid rgba(18,35,21,0.48)`

**Text style:** `story-title` — Deacon 700 · 50.4px/0.85 · tracking -0.0298em · uppercase

**Observed:** Large photo above an uppercase headline, short summary and small uppercase date. Tiles form a two-column ruled grid rather than isolated floating cards; the featured story becomes a full-width dark image/text split.

### Technical proof strip

**Only for:** technical product explainers

**Use:** Three compact word-valued benefits beneath a monumental closing statement.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); gap: 1px; max-width: 896px; border-radius: 8px; overflow: hidden; background: rgba(244,241,232,0.15)`

**Text style:** `technical-stat` — Deacon 900 · 36px/40px · tracking -0.02em · uppercase

**Observed:** Dark cells with 36px 24px padding sit over a translucent grid backing, making fine vertical separators. Green display words sit above muted explanatory captions.

**Transfer:** Use short time, effort or frequency outcomes rather than three unrelated large numbers.

## Imagery and graphics

### Hand-drawn landscape

**Use:** Signature opening scene and illustrated closing call.

**Observed:** An edge-to-edge woodcut-like mountain, river and pine-tree environment on forest green. Irregular cream/cyan mountain marks, green trees, blue water and warm coral clouds are cut into the dark ground; small human activity brings an optimistic scale. In the opening it occupies the lower half of the first screen; at the end a large yellow sun and animal silhouette rise above the landscape.

**Transfer:** Make a new environment tied to the product's promise, retaining rough linework, flattened depth and a dark ground. Minimum acceptable version is a layered original SVG landscape, not a stock photo or glossy 3D scene.

**Build:** Use a full-width SVG viewBox of 1440 by 600. Layer irregular mountain silhouettes behind a winding river and foreground tree clusters. Cut short uneven highlight paths into mountain faces and tree branches; use forest as negative space. Scatter elongated two-tone cloud shapes above the horizon, then place one warm disc near the horizon. Fade the lower 450px toward the forest canvas for the closing version; keep the upper center open for type.

### Collectible emblems

**Use:** Signature accent around openings, manifestos and selected section headings.

**Observed:** Circular seals, arched labels, polygonal tokens and rounded-square badges, typically 130–230px across, tilted and sometimes partly outside the page. Bright cyan, green, yellow and coral back a dark illustration, short curved slogan or simple symbol; the emblems stay at the edges of the text composition.

**Transfer:** Create product-specific badges with original motifs and concise values. Preserve the tactile, printed-patch feel and visual variety rather than using generic line icons.

**Build:** Construct SVG emblems with a colored base, two concentric dark keylines inset 6px and 10px, a bold central silhouette and uppercase text on circular paths. Mix circles with one arch and one polygon. Rotate each between roughly -15 and 15 degrees and place them around, not behind, the main text. A minimal version uses two-color geometric stamps with custom labels.

### Landscape-backed product proof

**Use:** Capability and process demonstrations.

**Observed:** Soft daylight photographs of hills, mountains, flowers and trees fill approximately 680 by 405px panels with 8px corners. Cream interface cards, forest result blocks, thin white charts and vivid green progress feedback float over the photograph. Nature is slightly subdued so the diagrams stay legible.

**Transfer:** Back a simplified diagram of the new product with a real, softly lit environmental photograph. Show one result or interaction; do not depend on tiny full-app text.

### Photographic collage

**Use:** A cyan-framed audience or use-case statement.

**Observed:** A large valley photograph fills a 1360 by 679px rectangle inside a 40px cyan frame. A tilted rectangular photo of hands meeting sits centrally over it; cream display type is pinned at upper right and small support copy sits at lower left.

**Transfer:** Pair a wide environmental context with a smaller human or object detail, retaining distinct rectangular edges and slight rotation.

### Editorial people and products

**Only for:** story indexes and testimonials

**Use:** Human proof and story navigation.

**Observed:** Natural-color photographs of people outdoors, product packaging, retail teams and lifestyle details; wide story pictures retain rectangular framing. The index opening scatters smaller mixed-aspect photos around a centered title, with some cut off at the outer edges. Testimonials pair one large product photo with a cream text panel.

**Transfer:** Use authentic scenes and products with warm daylight and varied distance; do not homogenize the imagery into portrait headshots.

### Technical demonstration windows

**Only for:** technical product explainers

**Use:** Proof-heavy chapters in the technical variant.

**Observed:** Paper-colored reports, sparse green trend lines, chat bubbles and tables sit directly on cream, sky blue or forest sections. Giant numerals and tiny monospace metadata make the output feel auditable rather than decorative.

**Transfer:** Stage one legible product outcome in a thin-bordered window. Keep charts and row contents specific to the new product; use compact captions and one dominant result.

### Icons

**Observed:** Public-facing categories use solid forest symbols about 28–32px; accordion plus signs are thin and unboxed. Carousel arrows are small within 64px circles. Technical windows use 12–16px outline SVGs with 2px rounded strokes.

**Transfer:** Use solid functional symbols for public category navigation and fine round-stroke icons only inside technical demonstrations; avoid mixing large multicolored app-icon tiles into the marketing layout.

## Section recipes

How recurring sections are built.

### First screen: Illustrated poster opening

**Observed:** A forest canvas fills an approximately 907px first chapter beneath the fixed 86px navigation. The centered two-line headline begins after generous top space, spans about half the page width and uses display type: cream first line, green second line. A two-line support paragraph sits in a 547.2px column, followed by a Primary button with 24px separation. Back to front: flat forest ground, full-width hand-drawn landscape rising around the lower sides, title/support/action layer, then navigation. Within the first 900px the complete title, support and action are visible; mountains, river, trees and small people fill the lower half and run beyond the bottom. The next chapter begins below the fold.

**Transfer:** Create an original illustrated scene that makes the new promise tangible. If detailed art is unavailable, use the layered SVG construction in Hand-drawn landscape with a few distinctive silhouettes. A process page opens with a smaller heading-lg title and edge badges on forest; a story index uses a cream opening, heading-lg title and scattered photos.

**Avoid:** Do not replace this opening with a left-text/right-dashboard SaaS hero, a pale gradient, or a full-bleed photograph that removes the dark negative space.

**Text style:** `display` — Deacon 900 · 136.8px/0.8 · tracking -0.011em · uppercase

### Centered declaration

**Observed:** Cream canvas, 180px top and 120px bottom spacing, centered heading-lg in a roughly 778px-wide block; 32px separates the title, narrow body copy and Primary button. Collectible emblems float near the edges.

**Transfer:** Make one strong value proposition or change of perspective; keep prose secondary to the typographic mass.

**Text style:** `heading-lg` — Deacon 900 · 100.8px/0.8 · tracking -0.0149em · uppercase

### Numbered capability chapter

**Observed:** Capability rows sit on Cream canvas within 40px gutters. Each uses Number disc, heading and body on the left and Landscape-backed product proof on the right, with 32px vertical row padding and a continuous hairline divider.

**Transfer:** Pair one benefit with one explanatory mechanism; let the number, title and bottom-aligned support create a full-height left column.

**Text style:** `heading` — Deacon 700 · 57.6px/0.85 · tracking -0.026em · uppercase

### Connected process

**Observed:** Forest version of the capability split: numbered discs run down a thin vertical progress line at left, cream heading and body follow them, and large photographic demonstrations sit at right. Thin ruled expandable detail links sit below the prose.

**Transfer:** Use this variant for onboarding or workflow instruction; the timeline should describe actual user progression rather than arbitrary feature numbering.

**Text style:** `heading` — Deacon 700 · 57.6px/0.85 · tracking -0.026em · uppercase

### Interactive outcome

**Observed:** Forest canvas with 140px top padding and 40px gutters. A stacked heading-lg and overlapping badges occupy the left, with support and action below. A Dark outlined panel takes the right half: a few slider rows, selectable stamps and one oversized green total beneath a divider.

**Transfer:** Let readers explore one consequence of their inputs. If a calculator is unsuitable, use a compact configurable demonstration with an explicit outcome.

**Text style:** `heading-lg` — Deacon 900 · 100.8px/0.8 · tracking -0.0149em · uppercase

### Cyan collage and criteria

**Observed:** Cyan band frames Photographic collage with 40px padding, followed by a three-cell ruled qualification strip. Each cell contains a solid icon and short uppercase qualification-title; central cell has vertical forest rules.

**Transfer:** Use an environmental image plus human detail to introduce a category, then clarify three kinds of audience or use case.

**Text style:** `qualification-title` — Deacon 900 · 36px/0.85 · tracking -0.0417em · uppercase

### Badge manifesto

**Observed:** Forest canvas, centered tightly stacked manifesto type with a green highlighted line and muted-forest remaining lines. Large circular and square emblems surround the block, partly clipped by section edges.

**Transfer:** Use a short product principle or consequential promise, with original visual tokens for its themes. Keep badge placement irregular but the text block rigorously centered.

**Text style:** `manifesto` — Deacon 900 · 72px/0.8 · tracking -0.0208em · uppercase

### Testimonial split

**Observed:** Cream canvas with 100px vertical padding; an approximately 1:2 image/text split and 24px gap. Large heading-lg precedes quote text, an attribution and paired Carousel arrows. Badge accents overlap the lower picture edge.

**Transfer:** Use a real customer or practitioner voice with a product or contextual photograph rather than a fabricated quote.

**Text style:** `quote` — Graphik 400 · 24px/1.2 · tracking -0.04em

### Categorized objections

**Observed:** Cream canvas with 80px top spacing and heading-lg at the upper left. Beneath it, a left category menu uses small solid symbols while FAQ rows fill a wide right column; the question column begins well to the right of the heading edge.

**Transfer:** Keep categories few and questions direct; retain the asymmetry and thin dividers instead of a centered stack of rounded cards.

**Text style:** `faq-question` — Deacon 900 · 32px/0.85 · uppercase

### Illustrated closing and footer

**Observed:** Forest canvas with 88px top padding. A centered heading-lg splits a cream command from a yellow consequence; Secondary button follows after 32px. A 1440px-wide illustrated landscape about 606px high sits beneath and around it, fading to forest at the bottom. Footer columns overlap the lower landscape region, then a horizontal rule and subdued legal line finish the page.

**Transfer:** End with one monumental promise plus one action and an original illustrated scene. The landscape must resolve into the same dark ground as the practical footer; keep the close emotionally bold but the information below it plain.

**Text style:** `heading-lg` — Deacon 900 · 100.8px/0.8 · tracking -0.0149em · uppercase

### Technical chapter and monumental close

**Only for:** technical product explainers

**Observed:** Alternate cream, muted sky, forest and one green signal chapter with 144px vertical padding and a 1152px centered content width. A 10px mono eyebrow sits 20px above a tall technical-heading, with 28px before support. Split demonstrations show reports, chat, trend charts, configurable outcomes and monitoring tables. The closing switches to centered technical-monument type, a Technical proof strip, a short final statement and bright action; the forest footer retains contact, company, links and social pills without the large landscape.

**Transfer:** Use this scoped variant for deep product explanation. Preserve readable demonstration windows, strong color chapters and collectible emblems; simplify the prose and chapter count to the new product.

**Text style:** `technical-heading` — Deacon 900 · 86.4px/0.92 · tracking -0.03em · uppercase

### Ruled editorial index

**Only for:** story indexes

**Observed:** Cream opening with a centered heading-lg and support surrounded by mixed photo rectangles and bright badges. A dark full-width featured story pairs image and story-title; a two-column ruled grid of Story tiles follows. The illustrated closing and footer return at the end.

**Transfer:** Use for customer, project or editorial collections where the imagery and headline carry the navigation.

**Text style:** `story-title` — Deacon 700 · 50.4px/0.85 · tracking -0.0298em · uppercase

## Page flow

**Storyline:** Promise → tangible mechanism → benefits and audience fit → human or quantified proof → objections → monumental closing call and practical footer.

### Broad public-facing marketing landing page

1. **Promise** — Illustrated poster opening and a cyan logo band.
2. **Positioning** — Centered declaration framed by badge accents.
3. **Capability chapters** — Numbered cream rows with landscape-backed demonstrations.
4. **Interactive proof** — Dark calculator and one dominant green result.
5. **Audience fit** — Cyan photographic collage and three-column criteria.
6. **Principle and social proof** — Badge manifesto followed by a photographic testimonial.
7. **Objection handling** — Categorized FAQ rows.
8. **Closing call** — Cream/yellow declaration above a landscape fading into contact and utility columns.

**Transfer:** Use the illustrated public-facing look by default; adapt the number and order of proof blocks to the new product.

### Workflow explanation and conversion

1. **Promise** — Centered cream-and-green title on forest with floating emblems.
2. **Process demonstration** — Connected numbered steps, concise explanations, expandable details and nature-backed product images.
3. **Differentiation** — A substantial split mechanism explanation followed by a cyan three-column benefit strip.
4. **Objection handling** — Cream categorized FAQs.
5. **Closing call** — The same illustrated declaration and complete practical footer.

**Transfer:** Describe what the user actually does, then explain the system supporting the result.

### Customer-story or editorial collection

1. **Community promise** — Centered cream opening framed by scattered people, product and outdoor photos.
2. **Featured proof** — One large dark image/headline feature.
3. **Proof collection** — Two-column ruled story grid with dates and short summaries.
4. **Closing call** — Illustrated landscape, monumental declaration, contact and legal footer.

**Transfer:** Let genuine stories supply specificity while the layout remains campaign-like and bold.

### Deep technical product narrative

1. **Promise and output** — Compact centered cream/green headline, badge edges and dark live-result window.
2. **Mechanism** — Sky-blue process map and a dark report chapter.
3. **Capability proof** — Light large-result panel, green recursive-process chapter, conversation, trend and configurable-outcome demonstrations.
4. **System and ongoing value** — Dark architecture stack followed by light monitoring tables.
5. **Quantified closing** — Monumental two-color declaration, three word-valued stats, final action.
6. **Practical footer** — Dark contact, entity details and utility links with a small impact strip and legal separator.

**Transfer:** Use the scoped technical typography and windows rather than mixing them indiscriminately into the public-facing illustration-led default.

## Writing

Optimistic, direct and purposeful. Big assertions are expressed in plain language, then grounded in practical explanations of how the product works.

**Do not copy:** Do not reuse Kikin names, logos, badge artwork, certification marks, customer names, quotations, proprietary technology labels, financial figures, environmental impact counts or funding claims. Replace them with original assets and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Public-facing copy speaks to you and your business, with we for the team. Technical passages can name the product and explain its behavior in the third person.
- **Rhythm:** Short, forceful headlines often break a thought into two clauses. Support prose is compact and explanatory, with occasional contractions and a concrete contrast instead of a string of superlatives.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category or action, then add an ambitious consequence on its own colored line. | 3–9 words | “Financing the future”<br>“How to get funded With kikin” |
| Capability headline | Plain benefit or contrast, often two short sentences. | 4–9 words | “Grow with the flow.”<br>“FAST FUNDS. FULL EQUITY.”<br>“Recurse, not repeat.” |
| Supporting line | Start with an immediate practical benefit, then explain what the system does. | 20–45 words | “Growth looks different for every business. Your funding adapts to whatever shape it takes.” |
| Primary action | Verb plus the concrete thing the reader receives. | 2–4 words | “Get funding”<br>“calculate your funding” |
| Closing headline | An imperative followed by a much bigger consequence. | 4–8 words | “GET FUNDING. CHANGE THE WORLD.” |
| Question | Ask what a prospective user would actually need to know. | 6–12 words | “How quickly can I access the funds?” |

**Words and phrasing to use:** grow; built for; your business; real time; flexible; only what you need; not just; good; together

**Avoid:** revolutionary ecosystem; unparalleled synergies; disrupt everything; effortless guaranteed success; overly academic explanations

**Rules:**

- Make headline contrast specific: what changes, and what constraint disappears.
- Explain the mechanism immediately after a large promise.
- Use sentence-case prose even though display titles and controls are rendered uppercase.
- Keep claims proportionate and qualified where eligibility or outcomes vary.
- Use concrete verbs for controls; avoid vague invitation labels.

## Do's and Don'ts

### Do

- Use 136.8px/0.8 uppercase display type for the default desktop opening and preserve the separate cream and green lines.
- Keep support prose near 16px/1.4 and constrain the opening support to 547.2px.
- Use 10px corners for primary and secondary actions, with 57px and 50px default heights respectively.
- Retain 40px desktop gutters and 32px vertical capability-row padding.
- Give photographic product panels 8px corners and enough width to explain one mechanism.
- Include original collectible emblems and a landscape-backed closing declaration.
- Let cyan occupy an entire transition band rather than scattered tiny accents.
- Use the same forest ground under the closing illustration and the practical footer.

### Don't

- Do not turn the broad display lettering into a condensed industrial face or a thin geometric headline.
- Do not loosen large default headlines to 1.2 line height; their near-touching stack is part of the poster character.
- Do not make every action a capsule; pills belong to small social or status controls.
- Do not put drop shadows under editorial story tiles or ordinary feature rows; they are ruled compositions.
- Do not tint every section cyan or green; cream and forest must remain the dominant page fields.
- Do not replace the nature-backed diagrams with many tiny application windows tiled across the page.
- Do not make body paragraphs uppercase merely because headings and buttons are.
- Do not carry tiny technical monospace labels into every public-facing section; they belong to the scoped technical variant.

## Motion and responsive

### Motion

**Observed:**

- Primary buttons declare a 0.2s transition and carousel controls a 0.3s transition.
- Technical actions declare 0.15s opacity/color transitions with cubic-bezier(0.4,0,0.2,1), and some transforms use 0.3s or 0.5s.
- Technical status dots declare a 2s repeating pulse; a separate rotating element declares 28s linear spin.
- The manifesto visually differentiates a vivid active line from progressively muted lines.

**Transfer:**

- Keep button feedback a color change rather than a large positional jump.
- For a line-highlight manifesto, preserve a legible muted base and move emphasis through the text rather than moving the whole text block.

**Unknown:**

- The exact public-facing scroll choreography and manifesto timing are unspecified; do not invent animation curves or durations for them.

### Responsive

**Observed:**

- Public-facing styles declare breakpoints including 479px, 767px, 991px and 1440px; technical styles include 600px, 640px, 768px, 1024px and 1280px.
- Headline sizes use the viewport formulas in their typography recipes.

**Transfer:**

- On narrow screens, preserve the two-color poster title and one obvious action; simplify the landscape silhouettes rather than shrinking detailed artwork to illegibility.
- Stack capability text and media, keep the numbered marker attached to its heading, and reposition badges to the outer edges so they cannot cover copy.
- Turn the three-column cyan strip and footer into readable vertical groups while retaining their rules.

**Unknown:**

- Narrow-screen compositions and exact breakpoint-specific rearrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
