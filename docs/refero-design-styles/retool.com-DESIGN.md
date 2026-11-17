# Retool — production in the spotlight

## Overview

A dark, product-led style that makes business software feel tangible and ambitious. Pale warm text and fine brown-gray rules sit against charcoal, with blue, rust and violet light concentrated around interfaces and sculptural glass artwork. Light grotesk headlines, compact technical captions and expansive demonstrations suit capable technical products without making the page feel like a dashboard. A softer cream-and-pastel editorial variant gives company stories a more human register.

### Essentials

- Headlines feel stretched open rather than heavy: Saans at 72px/1.05, weight 300 and -0.022em tracking for the main promise; 48px/1.05 and -0.01em for section leads.
- The opening is a working invitation inside a theater: a 1360px-wide inset media stage with 36px bottom corners, centered pale headline, and a 640×184px cream interaction panel in front of enlarged, dimmed product imagery.
- Actions are small capsules, not tiles: 40px height, 20px side padding and fully rounded ends; pale filled primary and 1px warm-gray outlined secondary. Dedicated product conversion sections scale them to 64px.
- Color behaves like illumination: most of the page remains #151515 with #e9ebdf text; rust, blue and violet occupy the announcement ribbon and media backdrops rather than ordinary paragraphs or feature-card fills.
- Interfaces are both evidence and scenery: include crisp, legible UI inside oversized 760px square or 880×660px media compositions, plus a dense edge-clipped gallery with 288×181px tiles and 16px gutters. If live UI is unavailable, construct a credible sample of the product's central task.
- Include a luminous sculptural interruption: translucent rectangular panes, discs and lens-like ripples behind a bright conversion panel; the minimum equivalent is layered iridescent SVG panes and rings, not a generic gradient blob.
- The ending becomes a typographic landmark: a dark ruled directory with 24px links, 12px uppercase category labels and an oversized pale brand lockup occupying roughly 960×188px beneath the directory.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Submit blue | `#518dd2` | `--color-submit` | action | Small circular submission control; not the general primary-button color. |
| Rust light | `#793325` | `--color-rust` | background, accent | Warm end of the announcement gradient and lower-right hero lighting. |
| Steel blue light | `#2d4c71` | `--color-blue` | background, accent | Cool announcement stop and lower-left hero lighting. |
| Plum light | `#3d163d` | `--color-plum` | background, accent | Dark violet end of the announcement ribbon. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm ivory | `#e9ebdf` | `--color-primary` | text, surface, action | Headlines, primary actions and the bright interactive panel; also the company-story canvas. |
| Black | `#000000` | `--color-black` | background, surface | Eyebrow chips and translucent navigation or media darkening layers. |
| Charcoal canvas | `#151515` | `--color-canvas` | background, text | Default marketing background and inverse text on pale controls. |
| Raised charcoal | `#242424` | `--color-raised` | surface | Results cards and dark filled secondary actions. |
| Faint ivory edge | `#2e2f2d` | `--color-faint-edge` | border, surface | Visible result of ivory at 12% over charcoal; gallery frames and quiet technical panels. |
| Brown charcoal rule | `#433e38` | `--color-rule` | border | Editorial cards, feature frames and accordion dividers. |
| Directory separator | `#3f403d` | `--color-strong-edge` | border | Visible result of ivory at 20% over charcoal; section and footer dividers. |
| Warm control edge | `#8b867f` | `--color-control-edge` | border | Outlined capsule actions. |
| Muted label gray | `#b6b8af` | `--color-subtle` | text | Directory labels and eyebrow text. |
| Soft gray | `#cbccc4` | `--color-muted` | text, background | Supporting copy on dark surfaces; solid gray bands in the company-story variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and customer-story pages | Pastel yellow | `#f6d6a0` | `--color-pastel-yellow` | surface | Photographic story cards. |
| company and customer-story pages | Pastel peach | `#f5c2b2` | `--color-pastel-peach` | surface | Photographic story cards. |
| company and customer-story pages | Pastel blue | `#b0ccea` | `--color-pastel-blue` | surface, background | Story cards and the company recruiting close. |
| pricing conversion sections | Closing blue glow | `#1b2e44` | `--color-closing-blue` | background | Low, wide blue light behind a centered conversion call. |
| company and customer-story pages | Pastel lilac | `#d0c1ea` | `--color-pastel-purple` | surface | Photographic story cards. |
| automation product conversion sections | Closing green glow | `#0e352c` | `--color-closing-green` | background | Low, wide green light behind a centered conversion call. |
| company stories and product media | Clean white | `#f7f8f4` | `--color-white` | surface | Testimonial paper and bright media surfaces. |

## Typography

- **saansFont** — Headlines, feature titles, paragraphs and large directory links. Open contemporary grotesk with broad, light headlines and a gently technical regular cut. If unavailable, use **Inter**. Use weights 300 and 400; preserve narrow line-height and negative display tracking. Font stack: "saansFont", "Inter", Arial, sans-serif.
- **pxGroteskFont** — Navigation, compact actions, metadata and uppercase directory labels. Compact, utilitarian grotesk; technical without being monospaced. If unavailable, use **Space Grotesk**. Use weight 400; check short-label widths against the compact capsule proportions. Font stack: "pxGroteskFont", "Space Grotesk", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | saansFont | 300 | 72px | 1.05 | -0.022em | size clamp(4rem, 2.76923rem + 1.92308vw, 4.5rem) | Primary immersive promise and flagship product headline. |
| heading-lg | saansFont | 300 | 60px | 1.05 | -0.02em | size clamp(3.25rem, 2.01923rem + 1.92308vw, 3.75rem) | Closing invitation; also standard pricing and product hero headline. |
| heading | saansFont | 300 | 48px | 1.05 | -0.01em | size clamp(2.5rem, 1.26923rem + 1.92308vw, 3rem) | Section headings and large split-layout chapter titles. |
| editorial-heading | saansFont | 300 | 32px | 1.05 | -0.01em | size clamp(1.5rem, 0.269231rem + 1.92308vw, 2rem) | Resource-grid title. |
| item-heading | saansFont | 380 | 24px | 1.2 | -0.01em | size clamp(1.25rem, 0.634615rem + 0.961538vw, 1.5rem) | Feature titles, result statements, resource titles and directory links. |
| body-lg | saansFont | 300 | 18px | 1.5 | 0.01em | fixed | Product hero support, trust captions and accordion questions. |
| body | saansFont | 300 | 16px | 1.5 | 0.01em | fixed | Default explanatory paragraphs. |
| prompt | saansFont | 380 | 16px | 1.5 | 0.0126em | fixed | Text within the pale interactive invitation. |
| caption | pxGroteskFont | 400 | 14px | 1.2 | 0.01em | size clamp(0.75rem, 0.442308rem + 0.480769vw, 0.875rem) | Short supporting labels, attribution and small utility text. |
| navigation | pxGroteskFont | 400 | 14px | 1.2 | normal | size clamp(0.75rem, 0.442308rem + 0.480769vw, 0.875rem) | Navigation and compact action containers. |
| string | pxGroteskFont | 400 | 12px | 1.2 | 0.01em, uppercase | fixed | Directory category labels, author metadata and short badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company pages | company-display | saansFont | 380 | 60px | 1.05 | -0.02266em | size clamp(3.25rem, 2.01923rem + 1.92308vw, 3.75rem) | Centered light-theme company promise. |
| company pages | company-heading | saansFont | 380 | 48px | 1.05 | -0.01133em | size clamp(2.5rem, 1.26923rem + 1.92308vw, 3rem) | Company narrative headings and recruiting close. |
| detailed product explanations | heading-sm | saansFont | 300 | 36px | 1.05 | -0.01em | size clamp(1.75rem, 0.519231rem + 1.92308vw, 2.25rem) | Large comparison-card titles and pull quotes. |
| company pages | company-body | saansFont | 380 | 18px | 1.5 | 0.0126em | fixed | Company narrative paragraphs. |
| product and pricing chapters | eyebrow | saansFont | 570 | 14px | 1.2 | 0.02em | fixed | Compact black category chips above section headings. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use weight 300 for the default dark-page hierarchy; reserve 380 for small titles and the light company variant. Headings stay pale and unadorned rather than using gradient-filled letters.
- Display tracking tightens more than section tracking. Body text opens slightly with positive tracking; labels are compact but not monospaced.
- The monumental footer lockup is vector artwork, not another body-font size. Set an equivalent custom wordmark to its width rather than enlarging a navigation label.

## Layout

**Density:** Airy at section scale, compact inside controls and product demonstrations. Long dark pauses separate dense, useful information.

### Spacing

**Spacing system:**

- **layout grid** 8px — Dominant layout rhythm for section gaps and padding; finer 4px adjustments serve controls and captions.

| Value | Use |
| --- | --- |
| 8px | Action-pair gap and inset image frame. |
| 12px | Small title-to-body gap and panel-to-utility-control gap. |
| 16px | Gallery tile gutters and input content padding. |
| 24px | Heading/support/action stacks and navigation link gaps. |
| 32px | Hero content separation and closing heading-to-actions gap. |
| 40px | Desktop side gutters, feature-column gaps and result-card padding. |
| 64px | Directory row gaps and large action height. |
| 80px | Section opening space and product-story separation. |
| 96px | Company-story section padding. |
| 120px | Major chapter separation and lower section padding. |
| 160px | Desktop directory top padding. |

### Containers and grids

- **page frame**: max width 2240px. Overall page shell; center the content and clip horizontal media overflow.
- **content grid**: max width 1440px · side padding 40px. Default desktop wrapper, yielding 1360px of usable space. Fine subgrid alignment ties copy, media and footer together.
- **feature columns**: 3 columns · gap 40px. Three equal 427px feature columns; six-item versions form two rows.
- **split demonstration**: max width 1440px · side padding 40px. Copy takes roughly 440px; the main media takes 760–880px, sometimes overlapping the midpoint. Keep text narrow beside very large imagery.
- **body measure**: max width 540px. Default upper limit for explanatory text; compact feature descriptions use about 407px.
- **interactive measure**: max width 640px. Bright prompt or central product task panel.
- **company container** (only for company pages): max width 1280px · side padding 40px. Centered 1200px inner content, with four 282px story cards separated by 24px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsule actions | 9999px (pill) |
|  | gallery tiles | 4px |
|  | interactive panel | 20px |
|  | interactive outer edge | 24px |
|  | hero bottom corners | 36px |
| pricing pages | plan frame | 12px |
| company pages | story and testimonial cards | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | interactive invitation | `0px 68px 116px 0px rgba(0,0,0,0.35)` | Separates the pale foreground task from its atmospheric media stage. |
| company pages | testimonial paper | `0px 6px 18px 2px rgba(0,0,0,0.08)` | Subtle lift on pale quote cards. |

### Surfaces

#### Dark canvas · level 0

**Use:** Default landing-page ground.

**CSS:** `background: #151515; color: #e9ebdf`

**Observed:** Large sections share a continuous flat ground; their boundaries are often spacing rather than boxes.

**Transfer:** Let demonstrations supply most visual texture.

#### Immersive stage · level 1

**Use:** Inset opening media theater.

**CSS:** `background-color: rgba(0,0,0,0.45); background-image: radial-gradient(at 0% 100%, rgba(45,76,113,0.75) 0%, rgba(0,0,0,0) 55%), radial-gradient(at 100% 100%, rgba(121,51,37,0.65) 0%, rgba(0,0,0,0) 50%); border-radius: 0px 0px 36px 36px; overflow: hidden`

**Observed:** Enlarged interface imagery sits behind the darkened foreground and colored lower corners; the top fades into the canvas.

**Transfer:** Keep the image dim enough for pale display text and a bright working panel to lead.

#### Raised results · level 1

**Use:** Quantified proof tiles.

**CSS:** `background: #242424; border: 1px solid #433e38`

**Observed:** Flat, square adjoining blocks; no floating-card shadow.

**Transfer:** Mix result statements with human photography at the same grid scale.

#### Quiet frame · level 1

**Use:** Gallery and technical illustration frames.

**CSS:** `border: 1px solid rgba(233,235,223,0.12); border-radius: 4px; overflow: hidden`

#### Company paper · level 0

**Only for:** company pages

**Use:** Light editorial canvas with dark text.

**CSS:** `background: #e9ebdf; color: #151515`

**Observed:** Alternates with #cbccc4 narrative bands and an occasional dark media band; the directory still returns to dark.

#### Testimonial paper · level 1

**Only for:** company pages

**Use:** Scrolling or stacked customer quotations.

**CSS:** `background: #f7f8f4; border-radius: 8px; padding: 36px; box-shadow: 0px 6px 18px 2px rgba(0,0,0,0.08)`

**Observed:** Quote cards sit in a tall masked column, with faint oversized quotation marks and attribution below.

#### Low conversion glow · level 0

**Only for:** automation product conversion sections

**Use:** Wide atmospheric closing band.

**CSS:** `background-image: radial-gradient(50% 130% at 50% 130%, #0e352c 0%, rgba(0,0,0,0) 95%)`

**Observed:** The green light rises from below the bottom edge; pricing uses a blue version.

**Transfer:** Leave the heading area mostly dark and keep the glow subordinate to the action pair.

## Components

### Primary button

**Use:** Default compact conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 20px; border-radius: 9999px; background: #e9ebdf; color: #151515`

**Text style:** `navigation` — pxGroteskFont 400 · 14px/1.2

**Observed:** Text-only capsule paired with an outlined action; label movement is contained inside the button. Product heroes and closing bands use a 64px version with 36px side padding and 16px Saans text.

**States:** Declared: hover background-color #fff and color #151515; focus-visible unspecified; active matches hover.

**Transfer:** Keep one dominant action and one complementary action.

### Secondary button

**Use:** Demos, galleries and supporting conversion paths.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 20px; border: 1px solid #8b867f; border-radius: 9999px; color: #e9ebdf; background: transparent`

**Text style:** `navigation` — pxGroteskFont 400 · 14px/1.2

**Observed:** A quiet outline beside the pale primary. A dark filled variant uses raised charcoal; the light company variant reverses the text to charcoal.

**States:** Declared: hover border-color #433e38 and color #e9ebdf; focus-visible unspecified; active matches hover.

### Global navigation

**Use:** Persistent wayfinding over long product stories.

**CSS:** `position: fixed; height: 80px; width: 100%; background: rgba(0,0,0,0.792); padding: 0px 40px; z-index: 2000`

**Text style:** `navigation` — pxGroteskFont 400 · 14px/1.2

**Observed:** Small brand lockup at left, grouped links with discreet down chevrons, then search; sign-in and paired capsules sit far right. A 40px announcement strip sits above the opening state and leaves as the page scrolls. The company version uses a translucent pale background.

### Interactive invitation

**Use:** Primary first-screen task and repeated conversion invitation.

**CSS:** `display: flex; flex-direction: column; max-width: 640px; height: 184px; background: #e9ebdf; border-radius: 20px; backdrop-filter: blur(6px); box-shadow: 0px 68px 116px 0px rgba(0,0,0,0.35)`

**Text style:** `prompt` — saansFont 380 · 16px/1.5 · tracking 0.0126em

**Observed:** Text sits in the upper area with 16px padding; a compact preset menu occupies the lower left and a circular blue submission control the lower right. A separate 2px translucent dark outline surrounds the panel with a 24px radius. Small import/alternate-mode controls sit 12px beneath it.

**Transfer:** For a product without text prompting, use the same bright task panel for its most direct starting action, such as a sample lookup or configuration.

### Submit control

**Use:** Single action inside the interactive invitation.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 40px; height: 40px; border-radius: 9999px; background: #518dd2; margin-right: 8px`

**Observed:** A pale right-arrow icon, 28px, occupies the blue circle; it aligns to the panel's bottom toolbar.

**States:** Declared: hover opacity 0.9; focus-visible solid 1px outline.

### Gallery tile

**Use:** Dense proof of product range.

**CSS:** `width: 288px; height: 181px; border: 1px solid rgba(233,235,223,0.12); border-radius: 4px; overflow: hidden`

**Observed:** An 8:5 application view fills the tile. Two parallel rows extend beyond both viewport edges with 16px gutters; there is no title overlay.

**Transfer:** Show distinct realistic outcomes rather than repeating the same interface.

### Result tile

**Use:** Concise quantified proof linked to a story.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #242424; padding: 40px 40px 32px; min-height: 272px`

**Text style:** `item-heading` — saansFont 380 · 24px/1.2 · tracking -0.01em

**Observed:** A two- or three-line result is anchored at the upper left and a pale customer mark near the lower left. Numbers stay in the sentence at the same scale rather than becoming giant numerals.

**Transfer:** Use a genuine operational outcome and mix tiles with full-height editorial photographs.

### Accordion row

**Use:** Detailed objection handling without a wall of copy.

**CSS:** `border-top: 1px solid #433e38; padding: 24px 0px; text-align: left`

**Text style:** `body-lg` — saansFont 300 · 18px/1.5 · tracking 0.01em

**Observed:** Question at left, thin plus at far right; expanded answers use muted body text below. The final row also closes with a bottom rule. The group occupies a 680px right column opposite a large section title.

### Resource card

**Use:** Editorial updates after the main conversion story.

**CSS:** `display: flex; flex-direction: column; border: 1px solid #433e38; background: transparent`

**Text style:** `item-heading` — saansFont 380 · 24px/1.2 · tracking -0.01em

**Observed:** One large image-led item occupies half the section; two smaller items stack beside it with copy and image side by side. Images have an additional 8px inset frame and metadata uses uppercase string text.

**States:** Declared: hover background-color #242424; focus-visible unspecified.

### Directory footer

**Use:** Substantial final navigation and brand landmark.

**CSS:** `background: #151515; border-top: 1px solid rgba(233,235,223,0.2); padding: 160px 40px 40px`

**Text style:** `item-heading` — saansFont 380 · 24px/1.2 · tracking -0.01em

**Observed:** Four wide directory columns sit beside a narrower company/action/legal rail. Uppercase category labels contrast with large links and fine vertical rules. Beneath the links, the huge pale vector lockup spans most of the first four columns, with legal links remaining at right.

### Eyebrow chip

**Only for:** product and pricing chapters

**Use:** Short category above a major section lead.

**CSS:** `display: inline-block; padding: 4px 6px; background: #000000; color: #b6b8af; border-radius: 6px`

**Text style:** `eyebrow` — saansFont 570 · 14px/1.2 · tracking 0.02em

**Observed:** The chip is only as wide as its label and precedes the heading by 24px.

### Pastel story card

**Only for:** company and customer-story pages

**Use:** Human stories on the pale editorial canvas.

**CSS:** `background: #f6d6a0; border-radius: 8px; overflow: hidden; width: 282px`

**Text style:** `prompt` — saansFont 380 · 16px/1.5 · tracking 0.0126em

**Observed:** A portrait-oriented photograph takes about 347px above the colored text panel; a category capsule overlays the image, then a customer mark, short paragraph and occasional understated underlined link follow. Blue, lilac and peach are sibling variants.

## Imagery and graphics

### Enlarged working interface

**Use:** Opening theater and oversized split demonstrations.

**Observed:** The opening background magnifies and tilts a pale task panel with a cursor, then defocuses and darkens it. Later media becomes crisp: chat panes, terminal/code windows and dashboards float on softly tinted pale backing or dark blue-green working canvases. Media is considerably larger than the accompanying text.

**Transfer:** Stage the central product operation, not a decorative laptop mockup. Use a real interface or a carefully constructed representative one; keep secondary UI dim and bring one active panel forward.

### Iridescent lens sculpture

**Use:** Signature luminous conversion interruption.

**Observed:** A diagonal procession of translucent rectangular panes and circular lens forms travels across the lower scene. Cool blue, lilac and peach reflections rim the glass; concentric distortions suggest optical ripples. A warm sculptural hand reaches toward a small orb at the right, while the bright task panel floats above.

**Transfer:** Use a sculptural metaphor for the new product's act of transformation. The minimum version retains intersecting translucent panes, circular ripples and iridescent edges, even without a rendered hand.

**Build:** Create an SVG scene spanning the section width: stagger 3–5 tall outlined rectangles along an ascending diagonal, skew their planes slightly, and overlap with 2–3 large circles. Fill with near-transparent blue and plum gradients, use pale blue/lilac/peach strokes at low alpha, and add duplicate blurred strokes for reflected edges. Draw concentric elliptical rings inside selected panes with progressively lower opacity. Keep black visible through the centers and place all artwork behind the pale task panel.

### Announcement light ribbon

**Use:** Thin chromatic signal at the top of the opening.

**Observed:** A full-width 40px gradient ribbon runs rust through steel blue into plum, with tiny pale and black capsule labels aligned to the left content edge.

**Transfer:** Use one short announcement rather than a second navigation bar.

**Build:** Apply linear-gradient(90deg, #793325 0%, #2d4c71 20%, #3d163d 100%) to a 40px band. Place a pale compact label and a dark compact action inline with an 8px gap.

### Human operational photography

**Use:** Customer proof and company narrative.

**Observed:** Natural color photographs show people doing actual work: industrial settings, customers, delivery and an everyday desk with laptop and external screen. Portrait story cards crop closely; wider company images show enough environment to explain the work.

**Transfer:** Choose plausible working contexts and unpolished human moments. On dark pages use photography as occasional large proof-grid cells; on company pages pair it with pastel caption panels.

### Monumental brand lockup

**Use:** Final visual anchor below the directory.

**Observed:** A single pale vector wordmark and emblem span 960×188px on charcoal, aligned to the left content edge; it is markedly larger than every normal heading.

**Transfer:** Use the new product's own typographic identity at an equivalent broad proportion. If no elaborate mark exists, draw a clean custom word lockup with a simple geometric emblem.

**Build:** Set the product name as a single SVG word shape, pair it with a compact geometric emblem and scale the combined viewBox to about 960px wide at a 1440px viewport. Use a single ivory fill with no texture, gradient or shadow.

### Illuminated technical field

**Only for:** detailed product demonstrations

**Use:** Explain integrations, generation and automated processes.

**Observed:** Fine orthogonal connector lines cross a dark canvas, punctuated by small luminous violet nodes and dark circular service symbols. Automation scenes shift to deep green and blue with floating white workflow blocks; a gridded technical plane continues below the active illustration.

**Transfer:** Map the product's actual inputs, transformation and output using a small number of blocks, connectors and one illuminated active area.

**Build:** Use SVG right-angle 1px paths on charcoal, circles at selected junctions and a low-opacity blurred violet glow behind each active node. Add a large radial blue-green or plum wash under the active white UI panel. For the technical plane, repeat faint horizontal and vertical 1px lines on a regular grid and mask their outer edges into the background.

### Icons

**Observed:** Mostly small monochrome SVGs: 16–24px utility icons, 36px feature symbols, fine outlined plus/minus and chevrons. Pale or muted gray paint dominates; colorful service marks are confined to product demonstrations.

**Transfer:** Use restrained outline or simple solid symbols with matching visual weight; pin them above feature titles or at the trailing edge of controls, not inside colorful decorative badges.

## Section recipes

How recurring sections are built.

### First screen: Immersive working opening

**Observed:** A thin 40px light ribbon sits above a compact dark navigation. The inset Immersive stage fills almost all the first 900px, with 40px side margins and rounded bottom corners. Back-to-front layers are enlarged tilted product media, a dark top fade and blue/rust lower light, centered pale display text spanning about two thirds of the viewport, a tiny new-feature support line, and the Interactive invitation. The 72px headline is one broad line when copy permits; the 640×184px task panel sits immediately below it, followed by two small alternate-mode controls. A small film capsule sits near the bottom center and pause control at lower left. The headline, short support, working panel and main background object are all visible within 900px; the gallery begins below the first screen.

**Transfer:** Make the promise one confident outcome and put the product's most direct task in the foreground panel. Without video, enlarge and tilt a static interface behind it, darken it, and retain the luminous corner wash. Standard product pages can instead open with a left 60px heading and 720×640px demonstration on the right; flagship generation pages use 72px left copy over a deep plum technical scene. Pricing opens directly into plan comparison; company pages use a centered pale editorial opening.

**Avoid:** Do not replace this with a generic centered headline over an empty gradient, or let sharp background UI compete with the foreground invitation.

**Text style:** `display` — saansFont 300 · 72px/1.05 · tracking -0.022em

### Overspilling outcome gallery

**Observed:** Centered heading, 40px gap, two edge-clipped tile rows with 16px gutters, then a centered Secondary button. Gallery tile frames are thin and nearly square-cornered.

**Transfer:** Show breadth through different outcomes, not additional marketing copy.

**Text style:** `heading` — saansFont 300 · 48px/1.05 · tracking -0.01em

### Oversized split chapter

**Observed:** A narrow left copy or chapter selector sits opposite a 760px square product scene; the 40px page gutter anchors both. The media exceeds half the usable width. Related product chapters use 440px copy opposite an 880×660px illustration, with thin ruled selectors and compact numbering.

**Transfer:** Keep one main working state per chapter. Alternate the media side for long-form explanations; reserve animation focus for the active state.

**Text style:** `heading` — saansFont 300 · 48px/1.05 · tracking -0.01em

### Unboxed feature columns

**Observed:** A large left-aligned heading sits above three open columns, separated by 40px gutters rather than card backgrounds. Small muted symbols lead 24px titles and 16px muted descriptions with a 12px gap. Major sections use 120px lower space.

**Transfer:** Use three differentiated benefits or six concrete capabilities; keep titles short and descriptions specific.

**Text style:** `item-heading` — saansFont 380 · 24px/1.2 · tracking -0.01em

### Results mosaic

**Observed:** A ruled monochrome logo strip leads into adjoining Result tiles mixed with 453px-wide photography cells. Results read as sentence-sized claims, not giant statistics. Small frosted category captions can sit over photography.

**Transfer:** Combine measurable outcomes and recognizable working contexts without turning the whole section into badges.

### Split questions

**Observed:** A short Eyebrow chip and 48px heading occupy the left side; a 680px ruled Accordion row stack occupies the right. Expanded answers remain narrow, muted and subordinate; groups can be separated by 120px.

**Transfer:** Group real objections by decision type rather than repeating the product pitch.

**Text style:** `heading` — saansFont 300 · 48px/1.05 · tracking -0.01em

### Sculptural working close

**Observed:** A centered 60px short invitation and small caption sit above the repeated Interactive invitation; the Iridescent lens sculpture occupies the lower and side regions behind it. Product-specific closes can use a left headline and a right task panel. A simpler scoped close uses Low conversion glow, a centered 48px heading and two 64px capsules with a 32px gap above them.

**Transfer:** Reintroduce the same starting task in a more expressive setting. Carry the luminous sculpture somewhere on the page even when a simpler conversion band is used.

**Text style:** `heading-lg` — saansFont 300 · 60px/1.05 · tracking -0.02em

### Editorial resource assembly

**Observed:** A 32px section title introduces a bordered asymmetric resource composition: one large half-width image card and two stacked smaller articles. Titles use 24px; author lines use 12px uppercase metadata.

**Transfer:** Use complementary resources rather than three equal blog cards.

**Text style:** `editorial-heading` — saansFont 300 · 32px/1.05 · tracking -0.01em

### Directory landmark ending

**Observed:** Directory footer finishes every page variant, including the light editorial treatment. The 160px upper breathing room, large links and monumental pale lockup make it a designed final destination rather than a compact legal strip.

**Transfer:** Group links by the new product's real information architecture and retain the outsized brand anchor.

### Company editorial narrative

**Only for:** company pages

**Observed:** Centered 60px medium-light heading on a gray band with 172px top and 96px bottom padding. Four portrait story cards sit on ivory, followed by a dark media/podcast band, a split testimonial-and-copy section, a gray team-image split, then a blue recruiting close. The final Directory footer returns to the universal dark treatment.

**Transfer:** Translate the beats into purpose, real-world proof, company perspective, human practice and invitation; use everyday photography and restrained pastel panels.

**Text style:** `company-display` — saansFont 380 · 60px/1.05 · tracking -0.02266em

### Plan comparison

**Only for:** pricing pages

**Observed:** A left-aligned 60px heading leads directly into four adjoining plan columns. The final commercial tier is wider, raised above the common top edge and framed with a 2px pale outline and 12px corners; subtle low blue and olive light differentiates its near-black surface. Capsules span each column. A dense ruled comparison matrix below aligns features and plans, with a search input and repeated plan actions.

**Transfer:** Preserve aligned units, billing context and availability marks. Emphasize one commercially important tier through frame and proportion, not a saturated fill.

**Text style:** `heading-lg` — saansFont 300 · 60px/1.05 · tracking -0.02em

## Page flow

**Storyline:** Outcome promise → visible working proof → capability chapters → operational credibility → decision support → renewed starting action → directory landmark.

### Broad product marketing landing page

1. **Promise and activation** — Immersive working opening puts a task panel directly in the hero.
2. **Outcome range** — Overspilling application gallery.
3. **Capability chapters** — Oversized split demonstrations spanning creation, integration and control.
4. **Credibility** — Open feature columns, logo strip and result/photo mosaic.
5. **Renewed action** — Sculptural working close repeats the starting task.
6. **Continued exploration and ending** — Asymmetric editorial resources then the directory landmark.

**Transfer:** Lead with a task, prove the range visually, and let explanation support the demonstrations rather than replacing them.

### Pricing and purchase evaluation

1. **Choice** — Plain headline and aligned plan-summary columns.
2. **Detailed comparison** — Long grouped feature matrix with repeated plan actions.
3. **Pricing rationale and trust** — Three explanatory columns, logos and compliance marks.
4. **Objection handling** — Several split-question groups.
5. **Closing action and ending** — Blue low-glow conversion band followed by directory landmark.

**Transfer:** Make comparison the main object; keep the marketing atmosphere concentrated at the close.

### Category education and flagship capability explanation

1. **Promise** — Left-aligned 72px headline, support, action pair and large plum-backed generation scene.
2. **Category framing** — Two large outlined conceptual cards compare the familiar category with a stronger approach.
3. **Differentiation** — Oversized technical scene with overlapping capability cards, followed by a ruled comparison.
4. **Fit and use cases** — Open benefit columns and a large selector-driven demonstration.
5. **Decision support** — Questions, logo/compliance strip and a split task-panel conversion.
6. **Ending** — Shared dark directory landmark.

**Transfer:** Explain the distinction visually before listing features; close with the same practical starting task.

### Technical product landing page

1. **Promise** — 60px left headline and action pair opposite a large workflow canvas; compact in-page links sit above.
2. **Mechanism** — Numbered selectors and a large active demonstration.
3. **Application breadth** — Long split use-case chapter with grid-backed technical media.
4. **Capability detail** — Alternating media-and-copy scenes.
5. **Credibility and completeness** — Large customer quotation and a six-item open feature grid.
6. **Closing action and ending** — Green low-glow conversion band and shared directory landmark.

**Transfer:** Show trigger, transformation and output through specific examples, then answer reliability concerns.

### Company identity and recruiting narrative

1. **Purpose** — Centered medium-light headline on a gray opening band.
2. **Real-world proof** — Four pastel photographic story cards.
3. **Perspective** — Centered dark media/podcast band.
4. **Trust and human practice** — Pale testimonial split followed by a gray text-and-workplace-photo section.
5. **Invitation and ending** — Blue recruiting band and dark directory landmark.

**Transfer:** Use human work and actual outcomes to support company purpose; preserve the shared ending while changing the page's emotional temperature.

## Writing

Practical, assured and developer-literate, with occasional pointed contrasts. Confidence comes from naming the work, the constraint and the operational result rather than grandiose adjectives.

**Do not copy:** Do not reuse Retool's name, wordmark, customer identities, proprietary feature names, quotations, claimed customer counts, savings or performance figures. Examples illustrate cadence only; use the new product's real assets and verifiable claims.

- **Addressing the reader:** Address the reader as you or your team; use we for company purpose. The product can speak by name in explanatory contrasts, but most headings begin with an action or result.
- **Rhythm:** Short declarative headlines often break into two contrasting sentences. Support paragraphs usually run two or three compact sentences. Actions use plain verbs, and detailed lists supply technical specifics.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Direct outcome, sometimes followed by an operational condition. | 4–10 words | “Secure your vibe-coded apps”<br>“Build automations. Deploy to production. Governed by default.” |
| Section headline | Plainspoken contrast or an outcome framed as a practical promise. | 5–12 words | “Generating apps is easy. Governing them is not. Until now.” |
| Supporting line | Name the mechanism, the actual work and the reliability condition. | 20–45 words | “Connect to any database, API, or service. Write logic in code, queries, or AI, and deploy production-ready automations from one governed platform.” |
| Primary action | Verb plus clear commitment level. | 2–5 words | “Start for free”<br>“Book a demo” |
| Result statement | Customer plus concrete improvement, written as a compact sentence. | 5–12 words | “Ramp saved $8M and 20,000+ hours” |
| Closing headline | Stop the wasteful activity; start the valuable outcome. | 7–12 words | “Stop prototyping apps. Start shipping them.” |

**Words and phrasing to use:** build; ship; from day one; by default; on your data; production-ready; connect; deploy; governed

**Avoid:** revolutionary; magical; limitless possibilities; unlock your potential; effortless everything; excessive exclamation marks

**Rules:**

- Pair an ambitious promise with a concrete mechanism or constraint.
- Use technical terms when they resolve a buyer question, not as atmosphere.
- Explain security, deployment or reliability as built-in conditions rather than distant add-ons.
- Keep proof statements compact enough to fit two or three lines at 24px.
- Use natural questions for objections and straightforward answers rather than sales copy disguised as an FAQ.

## Do's and Don'ts

### Do

- Keep ordinary dark-page headings at weight 300 and 1.05 line height.
- Align major content to the 40px desktop side gutters.
- Use 24px stacked text gaps and 12px feature-title-to-body gaps.
- Make product demonstrations larger than their neighboring copy, often 760px square or 880×660px.
- Keep 40px capsule actions compact; use the 64px scale only for major product conversion pairs.
- Let 1px brown-gray or low-alpha ivory rules organize dense material.
- Retain both a luminous sculptural scene and a monumental pale brand anchor.
- Use inline 24px result sentences to make quantified proof feel editorial rather than dashboard-like.

### Don't

- Do not default to bold 600–700 headlines; the light grotesk silhouette is central.
- Do not make all cards rounded 20px panels; that radius belongs to the interactive invitation, while gallery tiles use 4px and result cells remain square.
- Do not use electric blue as the universal primary-action fill; the primary is warm ivory and blue is a small submission accent.
- Do not spread pastel story-card colors across ordinary dark marketing sections.
- Do not render the gallery as three large cards with descriptive text beneath each; it is a dense, edge-clipped field.
- Do not turn the footer into 14px links and a small logo; its 24px directory and oversized vector lockup carry the ending.
- Do not put drop shadows under every panel; most dark-page depth comes from light, scale and fine edges.
- Do not inflate the results into isolated 100px numerals; the measured treatment keeps figures inside 24px statements.

## Motion and responsive

### Motion

**Observed:**

- Declared action color transitions commonly use 0.3s cubic-bezier(.72,0,.12,1); prompt controls use 0.2s with the same curve.
- Declared opacity transitions range from 0.4s to 0.6s. Product and logo scenes expose small pause controls.
- Declared prompt text shimmer runs 6s linear infinite. Gallery and logo strips use horizontal scrolling animations.

**Transfer:**

- Keep motion within the product theater, gallery and optical scene rather than adding unrelated floating decorations.
- Maintain a pause control for ambient scenes and let the active technical selector coordinate the adjacent illustration.

**Unknown:**

- Exact scene choreography, scroll-linked timings and autoplay behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 544px, 768px, 1024px, 1280px and 1440px; typography uses the clamp formulas listed in the recipes.
- The wide-page shell is capped at 2240px; main content wrappers are capped at 1440px.

**Transfer:**

- For narrow layouts, stack the working panel below the headline and keep the optical artwork behind or below it rather than shrinking a whole desktop composition.
- Stack split demonstrations with copy first and a readable media detail after it; let the gallery preserve horizontal clipping.
- Reflow the directory into fewer columns while retaining a broad final word lockup.

**Unknown:**

- Narrow-screen layout outcomes, menu behavior and exact breakpoint-specific spacing are not established; the stacking rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
