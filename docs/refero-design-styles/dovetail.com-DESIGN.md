# Dovetail — pixelated machine theatre

## Overview

A nearly black, theatrical technology style with oversized grotesk lettering interrupted by pixel-serif words and playful, tactile objects. Electric blue punctuates a mostly monochrome world of floating dark interfaces, wireframe diagrams and human proof. It suits ambitious software and complex platforms that need both technical credibility and a mischievous human character; the reading experience is spacious even when the product imagery is dense.

### Essentials

- Headlines behave like word sculptures: Inter 600 at 160px/140px in the opening, with 96px/100px chapter headings and PP Mondwest 400 at 120px/100px interrupting selected words.
- The promise sits above the spectacle: a 534px-wide support block and compact action pair occupy the upper left, ratings balance the upper right, and a two-line headline plus a roughly 188×200px tactile object dominate the lower first screen.
- Actions are compact rounded rectangles, never capsules: 8px corners, 42px height, blue primary beside charcoal glass secondary; the monumental closing pair grows to 56px.
- Color behaves like a concentrated signal: #0a0a0a dominates the page, white and #a7a7a7 carry text, and #0044ff is reserved for actions, diagram nodes and emphatic proof. Saturated full-width bands are bounded events, not the default canvas.
- Interfaces emerge from darkness: stage multiple cropped dark panels with faint 1px edges, an 8px radius and black edge fades; pair them with a tactile object or a wireframe system diagram. When full product media is unavailable, create one legible workflow panel and a simple dimensional object rather than a generic dashboard mosaic.
- Proof and the closing line become artwork: pair a 760px blue quotation card with a 400px dark pixel-numeral card, and include a monumental stacked closing statement at 133.3px/1 surrounded by overlapping badges over a faint character field. Use original capability symbols when partner badges are unavailable.
- Small text reads like machine markings: JetBrains Mono at 14px/1.4 with 1px tracking and uppercase for section labels and at 12px/1 for terse announcements and badges.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0044ff` | `--color-blue` | action, accent, background | Primary conversion actions, diagram nodes and full-bleed proof scenes. |
| Proof blue | `#0238ce` | `--color-proof-blue` | surface | Wide quotation cards, deeper than the primary action blue. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#0a0a0a` | `--color-canvas` | background, text | Dominant canvas and inverse text on white actions. |
| Low charcoal | `#121212` | `--color-card` | surface | Stat and testimonial cards. |
| Faint edge | `#1e1e1e` | `--color-edge` | border, surface | Subtle card edge; also the visible result of white at 8% over the canvas. |
| Active charcoal | `#313131` | `--color-active` | surface | Visible white-at-16% surface on near black, used by announcement strips and active controls. |
| Strong hairline | `#454545` | `--color-rule` | border | Comparison rules and action outlines; white at 24% produces the same visible value over the canvas. |
| Muted silver | `#a7a7a7` | `--color-muted` | text | Secondary text; also the visible result of white at 64% over the canvas. |
| Soft white | `#fafafa` | `--color-headline` | text | Default sculptural headlines and blue-button labels. |
| White | `#ffffff` | `--color-white` | text, surface | Main text, white action fills and monochrome marks. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| expressive product launches | Launch purple | `#7d00d6` | `--color-purple` | background | A product-launch hero extending behind its navigation. |
| expressive product launches | Purple index | `#9c57ef` | `--color-purple-label` | text | Pixel-serif chapter numbers accompanying the purple product-launch theme. |
| structured product and pricing sections | Raised charcoal | `#212121` | `--color-panel` | surface | FAQ chevron backing and comparison-column fill; also the expanded-plan surface. |

## Typography

- **Inter** — Primary display, headings, paragraphs and actions. Contemporary grotesk with substantial 600-weight headlines and tightly set large forms. OpenType features: "liga". Font stack: "Inter", -apple-system, system-ui, Helvetica, Arial, sans-serif.
- **PP Mondwest** — Selected headline words, monumental statistics and small characterful introductory phrases. Low-resolution serif with visibly stepped contours; expressive rather than a generic terminal face. If unavailable, use **Pixelify Sans**. Use 400; preserves pixel construction but not the serif details, so keep its use to short phrases. Font stack: "PP Mondwest", "Pixelify Sans", Georgia, serif.
- **JetBrains Mono** — Uppercase eyebrows, numbering, ratings labels, badges and footer headings. Technical monospaced markings with deliberately open tracking. Font stack: "JetBrains Mono", "SF Mono", Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 600 | 160px | 140px | -0.0144em | fixed | Two-line sculptural opening statement. |
| closing | Inter | 600 | 133.3px | 1 | -0.3px | tracking -0.01736vw | Monumental stacked closing statement. |
| chapter-pixel | PP Mondwest | 400 | 120px | 100px | -0.0167em | fixed | One emphatic word or short phrase sharing the chapter headline baseline. |
| chapter | Inter | 600 | 96px | 100px | -0.0208em | fixed | Major mixed-style chapter headlines. |
| stat | PP Mondwest | 400 | 96px | 1 | normal | fixed | Oversized quantitative proof. |
| heading | Inter | 600 | 64px | 68px | -0.0313em | fixed | Proof-section titles and shorter closing-call variant. |
| feature-title | Inter | 600 | 32px | 1.25 | -0.0313em | fixed | Numbered workflow chapter titles. |
| intro-pixel | PP Mondwest | 400 | 25px | 28px | -0.01em | fixed | Short highlighted category phrase inline at the start of the opening explanation. |
| lead | Inter | 400 | 24px | 32px | -0.0104em | fixed | Main chapter support paragraphs. |
| quote | Inter | 500 | 24px | 32px | -0.021em | fixed | Quotation text in blue proof cards. |
| selector | Inter | 500 | 24px | 32px | -0.0104em | fixed | Text-only feature selector labels. |
| card-title | Inter | 600 | 20px | 1.2 | normal | fixed | Compact feature-grid headings. |
| intro | Inter | 400 | 20px | 1.4 | -0.0125em | fixed | Opening explanation and compact feature narrative. |
| item-title | Inter | 500 | 20px | 1.4 | -0.0125em | fixed | Story captions, FAQ questions and comparison labels. |
| button-closing | Inter | 600 | 18px | 24px | -0.014em | fixed | Enlarged actions beneath the closing word sculpture. |
| body | Inter | 400 | 16px | 1.5 | normal | fixed | Secondary descriptions below product scenes and small feature cards. |
| link | Inter | 500 | 16px | 1.5 | normal | fixed | Footer links, attributions and short stat labels. |
| eyebrow | JetBrains Mono | 400 | 14px | 1.4 | 0.0714em, uppercase | fixed | Section labels, footer headings and technical captions. |
| button | Inter | 600 | 14px | 18px | normal | fixed | Default conversion actions and navigation. |
| micro | JetBrains Mono | 400 | 12px | 1 | 0.083em, uppercase | fixed | Announcement, small status badge and rating-source labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| expressive product launches | launch-pixel | PP Mondwest | 400 | 84px | 68px | -0.0238em | fixed | Pixel-serif ending of the launch headline. |
| pricing pages | pricing-display | Inter | 600 | 80px | 84px | -0.025em | fixed | Two-line white-to-gray commercial promise. |
| expressive product launches | launch-display | Inter | 600 | 72px | 68px | -0.0278em | fixed | Contained multi-line product-launch headline. |
| solution, detailed product and pricing pages | compact-heading | Inter | 600 | 56px | 60px | -0.0357em | fixed | Contained hero, FAQ title and medium capability headings. |
| solution and detailed product pages | statement | Inter | 500 | 40px | 1.2 | -0.025em | fixed | Pain-point headings and large grid-backed testimonials. |
| expressive product launches | launch-index | PP Mondwest | 400 | 32px | 1 | -0.0313em | fixed | Purple two-digit chapter numbers. |
| solution, detailed product, pricing and proof-library pages | body-wide | Inter | 400 | 20px | 1.4 | normal | fixed | Centered supporting paragraphs and testimonial-wall quotations. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The pixel face is not an italic accent: it has stepped serif contours and often runs larger than the sans while sharing its line height.
- Use 600 for major Inter statements, 500 for quotations and link-like labels, and 400 for explanatory prose. At 56px and above, tracking is usually -2px; the very largest opening uses -2.3px.
- Large chapter headings can wrap around a small object. Preserve readable word groups rather than forcing every line into equal widths.
- The closing display has much looser relative tracking than chapter headings; retain its separate recipe instead of scaling the chapter treatment.

## Layout

**Density:** Airy composition around dense media: broad dark intervals separate large headlines, while controls and interface fragments remain compact.

### Spacing

**Spacing system:**

- **rhythm** 8px, vertical — Dominant vertical spacing rhythm; 12px and action-specific 10px padding remain independent exceptions.

| Value | Use |
| --- | --- |
| 8px | Paired actions, title-to-description gaps and footer-item margins. |
| 16px | Media-caption groups, paragraph separation and small horizontal groups. |
| 24px | Support-to-action spacing, selector-item gaps and navigation side padding. |
| 32px | Grid gutters, media-to-heading gaps and medium content grouping. |
| 48px | Proof-card interiors and category-grid gutters. |
| 64px | Headline-to-feature composition, feature-grid row gaps and footer top padding. |
| 96px | Major heading-to-media distance and spacious content stacks. |
| 120px | Default major-section vertical padding. |
| 160px | Opening chapter entrance and proof-section exit. |
| 200px | Long-form transition between distinct narrative groups. |

### Containers and grids

- **Main container**: max width 1512px · side padding 124px. Centered outer section shell. At 1440px the inner content is 1192px wide.
- **Twelve-column scaffold**: 12 columns · gap 32px. Underlying alignment for section content; six footer groups each span two columns.
- **Feature grid**: 3 columns · gap 32px. Three 376px-wide items within the desktop inner container; use 64px between rows.
- **Split chapter**: gap 140px. A 510px narrative and selector column beside a 542px media column.
- **Proof pair**: gap 32px. A 760px quotation card beside a 400px statistic card; align their heights.
- **Reading measure**: max width 640px. Centered support prose; headings can extend to 700px and media beyond that.
- **Navigation shell**: side padding 24px. Full-width horizontal navigation, independent of the narrower main-content shell.

## Corner radius

| Element | Radius |
| --- | --- |
| Buttons and media cards | 8px |
| Small status badges | 4px |
| Proof badges and eyes | 50% |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default marketing-page field.

**CSS:** `background: #0a0a0a; color: #fafafa`

**Observed:** Sections usually merge into one continuous dark field rather than alternating light and dark bands.

**Transfer:** Use type, spacing and media to divide the narrative.

#### Charcoal card · level 1

**Use:** Low-rise stat and media grouping.

**CSS:** `background: #121212; border: 1px solid rgba(255,255,255,0.08); border-radius: 8px`

**Observed:** Edges are faint; there is no general-purpose drop shadow.

**Transfer:** Create separation with a small luminance change, not elevated white cards.

#### Blue proof · level 1

**Use:** Quotation emphasis within an otherwise dark section.

**CSS:** `background: #0238ce; border: 1px solid rgba(255,255,255,0.08); border-radius: 8px`

**Observed:** White quotation and attribution sit over a faint field of tiny characters, especially visible toward the lower edge.

**Transfer:** Keep text dominant; restrict texture to low opacity.

#### Square grid field · level 0

**Use:** Technical backdrop behind text or product fragments.

**CSS:** `background-color: #0a0a0a; background-image: linear-gradient(to right, rgba(255,255,255,0.08) 1px, rgba(0,0,0,0) 1px), linear-gradient(rgba(255,255,255,0.08) 1px, rgba(0,0,0,0) 1px); background-size: 48px 48px`

**Observed:** Grid lines disappear into black toward the scene edges and never compete with copy.

**Transfer:** Apply a fading mask to the grid layer, leaving the content layer unaffected.

#### Launch field · level 0

**Only for:** expressive product launches

**Use:** Distinct product-introduction hero.

**CSS:** `background: #7d00d6; color: #ffffff`

**Observed:** Extends behind navigation; a stepped pixel silhouette transitions into the dark product story below.

**Transfer:** Keep the theme localized to the launch introduction and its chapter accents.

#### Expanded plan · level 1

**Only for:** pricing pages

**Use:** Commercial plan emphasis.

**CSS:** `background: #212121; border: 1px solid #454545; border-radius: 8px; padding: 48px`

**Observed:** The expanded plan is twice the width of the entry plan and contains a two-column benefits list.

**Transfer:** Emphasize added breadth with width and fill, not a floating promotional ribbon.

#### Sticky comparison glass · level 2

**Only for:** pricing pages

**Use:** Persistent plan context while comparing features.

**CSS:** `background: rgba(10,10,10,0.8); border-bottom: 1px solid #454545; backdrop-filter: blur(48px)`

**Observed:** A 161px fixed comparison header carries names, prices and actions.

**Transfer:** Keep plan headings aligned to the comparison columns.

## Components

### Navigation item

**Use:** Primary menu triggers and direct navigation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 10px 16px; border: 1px solid transparent; border-radius: 8px; color: #ffffff`

**Text style:** `button` — Inter 600 · 14px/18px

**Observed:** Compact horizontal menu alongside a small symbol at left; login and a White action sit at far right. A 30px mono announcement strip precedes the 88px navigation on the default theme.

**States:** Declared: hover background rgba(255,255,255,0.08); focus-visible background rgba(255,255,255,0.16), 1px solid white outline with 1px offset.

### Primary button

**Use:** Default main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #0044ff; color: #fafafa; border-radius: 8px; padding: 12px 16px; height: 42px; transition: opacity 150ms`

**Text style:** `button` — Inter 600 · 14px/18px

**Observed:** Usually first in a pair with Secondary button. The closing variant uses button-closing text, 16px 24px padding and 56px height.

**States:** Declared: hover opacity 0.85.

### Secondary button

**Use:** Trial or alternative conversion beside the primary.

**CSS:** `display: flex; align-items: center; justify-content: center; background: rgba(30,30,30,0.85); color: #ffffff; border: 1px solid rgba(255,255,255,0.24); border-radius: 8px; padding: 11px 15px; height: 42px; backdrop-filter: blur(16px); transition: color 200ms, background 200ms, opacity 200ms`

**Text style:** `button` — Inter 600 · 14px/18px

**Observed:** Dark glass keeps the second action quieter. The closing variant grows to 56px with 15px 23px padding and button-closing text.

**States:** Declared: hover background rgba(255,255,255,0.16); focus-visible same background plus a 1px white outline with 1px offset.

### White action

**Use:** Navigation conversion and white-primary themed variants.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #0a0a0a; border: 1px solid transparent; border-radius: 8px; padding: 10px 16px; height: 40px; transition: 300ms`

**Text style:** `button` — Inter 600 · 14px/18px

**Observed:** Navigation always uses the light action; solution and launch themes also use it within content. Those content buttons use 14px/18px Inter 500 rather than 600.

**States:** Declared: hover background #cecece; focus-visible same background with a 1px near-black outline and 1px offset.

### Feature selector

**Use:** Choose one capability and reveal its paired demonstration.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 24px; color: rgba(255,255,255,0.64); transition: color 150ms`

**Text style:** `selector` — Inter 500 · 24px/32px · tracking -0.0104em

**Observed:** Text-only rows occupy the narrative column. The active row turns soft white and gains a thin progress underline; the media and descriptive caption update alongside it.

**States:** Declared: hover color #fafafa.

**Transfer:** Use short outcome labels, not icon-filled boxed tabs.

### Blue quote card

**Use:** Named customer proof beside a metric.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 64px; background: #0238ce; border: 1px solid rgba(255,255,255,0.08); border-radius: 8px; padding: 48px; overflow: hidden`

**Text style:** `quote` — Inter 500 · 24px/32px · tracking -0.021em

**Observed:** Quotation above, portrait and name at lower left, company mark lower right. A faint character texture backs the lower part; the whole card links to a story.

**Transfer:** Pair a specific attributed experience with the adjacent measured result.

### Stat card

**Use:** Quantitative partner to the quotation.

**CSS:** `background: #121212; border: 1px solid rgba(255,255,255,0.08); border-radius: 8px; overflow: hidden`

**Text style:** `stat` — PP Mondwest 400 · 96px/1

**Observed:** An inner layer has 48px padding and space-between alignment: pixel-serif numeral at top with a tiny blue sparkle, then a short 16px label and quieter explanation near the bottom.

**Transfer:** Use one metric, its unit and a plain explanation; keep the numeral the visual center.

### Story media card

**Use:** Human proof in horizontal strips or story libraries.

**CSS:** `position: relative; border: 1px solid rgba(255,255,255,0.08); border-radius: 8px; overflow: hidden`

**Text style:** `item-title` — Inter 500 · 20px/1.4 · tracking -0.0125em

**Observed:** Default media frame is 402×440px with a darkened interview still and centered white company mark; its caption sits outside the frame, 24px below. Horizontal strips have 32px gaps and masked outer edges. Library variants use brighter 376×414px images and place marks near the lower left.

**Transfer:** Keep photographs substantial; avoid enclosing the caption in another raised card.

### FAQ question

**Use:** Objection handling on longer product and commercial pages.

**CSS:** `display: inline-flex; justify-content: space-between; align-items: center; color: #ffffff`

**Text style:** `item-title` — Inter 500 · 20px/1.4 · tracking -0.0125em

**Observed:** A 886px question column sits beside a separate title column. Thin rules separate spacious rows; each trigger carries a 24px charcoal square with 4px corners and a chevron. Rules have 32px spacing before the next question.

**States:** Declared: hover color #a7a7a7; focus-visible color #a7a7a7.

### Footer link

**Use:** Dense but orderly site navigation below the closing artwork.

**CSS:** `position: relative; color: #ffffff; transition: color 200ms ease-out`

**Text style:** `link` — Inter 500 · 16px/1.5

**Observed:** Six columns under mono headings, headings separated from lists by 24px; items have 8px vertical margins. Small rectangular mono status badges sit directly after selected labels. Legal controls and social symbols occupy a separate bottom row.

**States:** Declared: hover color #ffffff; focus-visible color #ffffff; a white pseudo-element supplies the link accent.

### Comparison row

**Only for:** pricing pages

**Use:** Detailed feature availability across plans.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); column-gap: 32px; border-bottom: 1px solid #454545; height: 73px`

**Text style:** `item-title` — Inter 500 · 20px/1.4 · tracking -0.0125em

**Observed:** Label occupies the left third, followed by two centered plan values or square-ended checks. The entry-plan value column has a continuous charcoal fill. Comparison labels are underlined.

**Transfer:** Group rows beneath 56px capability headings rather than one undifferentiated table.

### Testimonial tile

**Only for:** proof-library pages

**Use:** An extensive wall of user voices.

**CSS:** `display: flex; flex-direction: column; gap: 96px; background: #121212; border: 1px solid #1e1e1e; border-radius: 8px; padding: 32px`

**Text style:** `body-wide` — Inter 400 · 20px/1.4

**Observed:** Three independent stacks of 376px-wide tiles, varied heights, quotation at top and small portrait/name/organization near the bottom. The wall ends in a black fade.

**Transfer:** Let text length create a masonry rhythm; do not force equal-height testimonial tiles.

## Imagery and graphics

### Tactile headline objects

**Use:** A signature interruption inside or beside oversized words.

**Observed:** Small retro or office-like objects rendered with physical volume: a gray printer with toy eyes, a brimming file folder, a keycap with flame, a magnifier and a globe. Neutral plastic, chrome and paper textures contrast with occasional bright details; each object is isolated directly on black without a containing card.

**Transfer:** Make an original physical metaphor for the product's job. The minimum version is a clean cutout of a simple modeled object with convincing directional light and a compact shadow, about one headline line tall.

**Build:** Combine simple shaded cuboids, cylinders or a photographed cutout; light from upper left, add a restrained underside shadow, and position the object in a deliberate word gap. Use tiny spherical white eyes with dark pupils for a single playful detail, not a cast of cartoon mascots.

### Character field

**Use:** Subtle atmosphere behind the opening, proof cards and monumental closing.

**Observed:** Faint gray characters and symbols fall in uneven vertical clusters, bending into waves across black. The scene remains overwhelmingly dark; the texture is most visible around the headline's lower edges.

**Transfer:** Create a very low-contrast field using neutral characters relevant to the new product; preserve broad black areas.

**Build:** Generate an SVG text grid in JetBrains Mono at 8–12px, columns spaced 12–18px with irregular blank runs. Use white at 3–8% alpha; displace columns with a sinusoidal vertical offset. Mask to a broad wave with soft black edges and place behind all readable content.

### Floating product collage

**Use:** Show the product as an interconnected working system.

**Observed:** Dark interface fragments overlap at different scales: task cards, chat windows, charts, source previews and small video portraits. Thin edges, occasional slight rotations and black lower-edge fades make panels emerge from the canvas. A large collage can span 1192px; smaller chapter scenes are around 542×352px.

**Transfer:** Use two or three authentic workflow fragments with one readable focal panel. Preserve the dark surroundings, restrained local color and generous negative space rather than reproducing every control.

**Build:** Layer 8px-radius panels with 1px white-at-8% edges, offset by 24–64px; rotate only secondary scraps a few degrees. Cover the lower third with a transparent-to-near-black gradient. Restrict any violet or blue glow to a localized blurred pool behind the active control.

### Orbital machine diagram

**Use:** Signature technical spectacle within a capability chapter.

**Observed:** A polished silver stacked cylinder sits in a blue halo, surrounded by tilted dotted elliptical paths, tiny blue square nodes and floating mono glass labels. The diagram occupies the full 1192px content width and follows the centered chapter introduction after 96px.

**Transfer:** Represent the new product's process with an equally simple central object and orbiting stage labels. A CSS/SVG cylinder and path diagram is an acceptable minimum.

**Build:** Use an SVG viewBox about 1192×587. Draw three thin elliptical paths tilted in opposing directions with white at 16% and short dash patterns. Place 4px electric-blue squares along them. Build a central metallic cylinder from stacked ellipses and gray linear gradients, backed by a blue-at-25% radial glow blurred about 32px; place 8px-radius dark glass mono labels near the paths.

### Wireframe globe

**Use:** Large companion to a numbered workflow narrative.

**Observed:** A thin gray spherical longitude/latitude mesh is partially clipped beyond the left viewport edge; electric-blue dots and a few larger nodes sit on its surface. The right side holds a small interface scene, a blue two-digit index, a 32px title and muted body copy.

**Transfer:** Use a spherical or curved network diagram to suggest system-wide reach while the adjacent text explains one concrete operation.

**Build:** Draw an approximately 804px SVG circle with 1px white-at-16% longitude ellipses and latitude arcs. Rotate the group slightly, add blue nodes at intersections, and clip one side outside the section. Keep the wireframe unfilled and the canvas near black.

### Human story stills

**Use:** Proof cards and case-study libraries.

**Observed:** Natural-color interview portraits in workplace settings, usually medium close-ups; occasional buildings or landscape views supply variety. Rounded media, subtle bottom fades and white marks tie the images to dark page furniture.

**Transfer:** Choose real people or real operating environments with neutral daylight. Keep skin tones natural; do not apply the saturated blue treatment to every thumbnail.

### Closing badge constellation

**Use:** Signature finish around a stacked short statement.

**Observed:** Circular and shaped badges overlap the margins of four giant words on a character-field backdrop. Badges use their own vivid colors and asymmetrical placement, but the white headline stays dominant.

**Transfer:** Use legitimate partner symbols or original capability badges; when those are unavailable, make original geometric token illustrations. Keep this celebratory constellation in the design.

**Build:** Stack a short four-beat sentence in the closing recipe, then distribute about eight 128–184px badges around the outer contours. Vary circles and one or two shaped silhouettes, allow selective overlap with word margins, and keep the action pair clear below.

### Blue story theatre

**Only for:** featured case studies

**Use:** Full-width immersive proof interruption.

**Observed:** Video or interview footage is strongly washed in electric blue behind centered white headline, supporting copy and white action. A small company badge can be bracketed inline within the headline. Numbered controls sit above; blocky black pixel steps cut into the top or bottom boundary.

**Transfer:** Use original customer footage, or a genuine product-in-use photograph if video is unavailable; retain the single blue wash and stepped transition.

**Build:** Place cover media under an electric-blue overlay strong enough to reduce the image to supporting texture. Overlay centered copy with a roughly 700px measure. Form the lower boundary with a black SVG path built from uneven rectangular steps on a 48px module.

### Anonymous story duotones

**Only for:** proof-library pages

**Use:** Editorial thumbnails when the organization is unnamed.

**Observed:** Industry photographs and patterned symbols are converted to intense blue-and-black halftone or pixel textures, with large centered white industry descriptors.

**Transfer:** Use an image tied to the relevant sector, not invented company marks.

**Build:** Convert to grayscale, apply a blue/black duotone with a stepped contrast curve, then add a fine dot or pixel screen. Center a short white sans descriptor over the high-contrast image.

### Icons

**Observed:** Small interface-like marks rather than decorative pictograms: 24px outline symbols with 2px square-ended strokes, 16–18px filled arrows, and occasional deliberately pixel-stepped navigation arrows. Most are white; blue marks identify system nodes.

**Transfer:** Use simple monochrome geometry for controls and reserve pixel-stepped arrows for expressive navigation. Do not mix a colorful outlined icon family into every feature title.

## Section recipes

How recurring sections are built.

### First screen: Word sculpture opening

**Observed:** Canvas and Character field form the back layer; navigation and a slim announcement sit above. Within the 1192px inner width, an upper-left 534px explanation starts with an inline pixel-serif category phrase, then muted 20px prose and the Primary button/Secondary button pair 24px below. Three compact star-rating groups balance it on the right. A broad dark interval separates this utility row from the lower two-line display at 160px/140px. A roughly 188×200px Tactile headline object occupies a word gap, visually punctuating the first line. The statement spans most of the content width; a muted logo strip sits beneath. Within the first 900px, navigation, explanation, actions, ratings, headline, object and logo strip are visible. The large Floating product collage continues below the fold.

**Transfer:** Write a short physical-metaphor promise and give it the same two-line scale; create an original dimensional object if no product artwork exists. Keep the explanatory row above the headline rather than moving everything into a centered generic hero. Solution pages instead use a centered 56px problem statement over Square grid field; product launches use a left-aligned 72px statement on Launch field; pricing uses an 80px white/gray promise with plan tops visible; proof libraries open with a 96px first-person quotation and a playful object.

**Avoid:** Do not shrink the statement into a conventional heading beside a large dashboard, and do not put the support paragraph beneath the headline by default.

**Text style:** `display` — Inter 600 · 160px/140px · tracking -0.0144em

### Mixed-type chapter entrance

**Observed:** A 96px chapter headline gains one 120px pixel-serif word and a tactile object in a deliberate gap. It can be left aligned above Split chapter or centered above an Orbital machine diagram. Support uses lead text, then compact paired actions; major sections have 120px vertical padding.

**Transfer:** Use the pixel face for the idea being emphasized, not every noun. Let the object illustrate the action or transformation.

**Text style:** `chapter` — Inter 600 · 96px/100px · tracking -0.0208em

### Selectable capability split

**Observed:** Split chapter places support and Feature selector in the left column, with Floating product collage, body caption and a text link on the right. Selector rows have 24px gaps; headline and split body are separated by 64px. Blue quote card and Stat card form a full-width proof pair below.

**Transfer:** Use one coherent capability family per split, and provide a short corresponding scene for each selector item.

### Numbered system walkthrough

**Observed:** A sticky 900px stage pairs Wireframe globe with a right-side media fragment and numbered narrative. The workflow title is 32px/40px, body 20px/28px, index blue and pixel-serif. A launch variant keeps narrative at left with 56px headings and purple 32px chapter numbers, swapping product scenes at right.

**Transfer:** Explain an end-to-end workflow through a few decisive stages without turning the whole page into tiny disconnected cards.

### Governance feature grid

**Observed:** A mixed-style chapter lead precedes a three-column, two-row Feature grid. Each item has a 376×217px dark product image, 32px to its card-title, and 8px to muted body copy; row gap is 64px.

**Transfer:** Use small demonstrations of constraints, settings or controls to support trust claims, rather than decorative shield icons.

### Grid-backed testimonial

**Observed:** A 1260×560px grid-backed scene holds a large 40px quotation, a small portrait inline near the beginning, then a company mark and uppercase mono attribution. The grid fades toward its edges. Some variants have two-digit slider controls and a small line/square progress indicator.

**Transfer:** Set one detailed human statement as a substantial section, keeping attribution visually precise rather than relegating it to tiny gray text.

**Text style:** `statement` — Inter 500 · 40px/1.2 · tracking -0.025em

### Story strip

**Observed:** A 64px proof heading and small light action share a row; Story media cards follow after 96px. The horizontal strip escapes the content shell, with 32px gaps and soft masks at the viewport edges.

**Transfer:** Create a continuous proof gallery that feels larger than the page, without shrinking images to fit four complete cards.

**Text style:** `heading` — Inter 600 · 64px/68px · tracking -0.0313em

### Structured solution chapter

**Observed:** Within the Twelve-column scaffold, a 376px text block alternates sides with 682×659px composite media. Eyebrow, 40px statement, 16px muted explanation and White action pair are vertically grouped; section padding is 80px top and bottom.

**Transfer:** Use a real operational frustration as the headline and the adjacent scene to show its resolution.

**Text style:** `statement` — Inter 500 · 40px/1.2 · tracking -0.025em

### Blue assurance call

**Observed:** A bounded 840px electric-blue field surrounds centered 64px heading, 20px support and White action pair. A few concise check-mark assurances sit below, while low-contrast square-grid fragments gather at the perimeter.

**Transfer:** Use this emphatic band to lower adoption risk or resolve a major objection; keep the checklist short.

**Text style:** `heading` — Inter 600 · 64px/68px · tracking -0.0313em

### Commercial plan comparison

**Observed:** Pricing-display opens over a fading technical grid. Entry and expanded-plan cards occupy one-third and two-thirds of the 1192px content width, separated by 32px, with 48px interiors. An extended comparison follows with Sticky comparison glass, 73px Comparison rows and 56px section headings; the entry column is filled charcoal.

**Transfer:** Use hierarchy, width and continuous column shading to make the plan difference intelligible.

**Text style:** `pricing-display` — Inter 600 · 80px/84px · tracking -0.025em

### Proof-library depth

**Observed:** A large quotation entrance leads to compact wrapping category chips, then three-column story media. A monochrome six-column logo wall leads into Blue story theatre, a mixed sans/pixel trust headline, award captions and the Testimonial tile wall.

**Transfer:** Adapt the density to the amount of authentic proof available; preserve the variation between photographic stories, marks and quoted voices rather than copying the extreme length.

### FAQ split

**Observed:** A 56px title occupies the left quarter; the 886px question list occupies the rest. FAQ question triggers align with horizontal rules and small square chevrons. Pricing adds a short support link beneath the title.

**Transfer:** Address concrete product, access and commercial questions in plain language.

**Text style:** `compact-heading` — Inter 600 · 56px/60px · tracking -0.0357em

### Monumental closing and footer

**Observed:** A 900px Canvas scene centers the Closing badge constellation and four-beat statement at 133.3px/1. A 56px Primary button/Secondary button pair anchors it. A top fade joins this to the preceding story; the following footer is 782px high with 64px top padding, six columns, mono headings and a separate legal/social bottom row. The solution variant instead uses a 560px perspective-grid call with a centered 64px heading and 40px white/glass actions before the same footer.

**Transfer:** End on a short confident idea rather than another paragraph. Include the word sculpture and original badges in the default theme; the solution variant trades the badges for a receding wireframe chamber.

**Text style:** `closing` — Inter 600 · 133.3px/1 · tracking -0.3px

## Page flow

**Storyline:** bold promise → staged product explanation → capability chapters with embedded proof → trust and practical objections → memorable closing call → navigable footer

### Broad platform marketing

1. **Promise** — Explanation and ratings above a giant object-interrupted statement.
2. **Product demonstration** — Large dark collage followed by mixed-type capability chapters and selectors.
3. **Quantified proof** — Blue quotation and dark pixel-stat pairs embedded near relevant claims.
4. **Workflow explanation** — Wireframe system walkthrough and operational feature grid.
5. **Social proof** — Human story strip.
6. **Closing call** — Stacked statement, badge constellation, enlarged actions and six-column footer.

**Transfer:** Use the strongest visual metaphor as the invitation, then alternate explanation, working scenes and specific proof.

### Problem-focused solution landing

1. **Problem framing** — Centered problem statement on fading square grid with action pair and reassurance line.
2. **Social proof** — Mono caption and monochrome logo row.
3. **Capability chapters** — Alternating narrow pain-point copy and larger dark demonstrations; concise integration categories.
4. **Validation** — Large grid-backed quotation.
5. **Risk reduction** — Blue assurance band with checklist and trial action.
6. **Objection handling** — Split FAQ list.
7. **Closing call** — Perspective-grid call and shared multi-column footer.

**Transfer:** Let the reader recognize the problem before explaining the technical system; keep this variant more contained than the broad platform opening.

### Expressive individual-product launch

1. **Promise** — Purple hero, mixed 72px sans and 84px pixel type, large overlapping product scene.
2. **Social proof** — Ratings and mono-captioned logos.
3. **Product explanation** — Centered argument and playable demonstration, followed by a grid-backed quote.
4. **Capability chapters** — Purple numbered sticky chapters, voice demonstration and finely divided use-case matrix.
5. **Control and trust** — Configuration carousel and another large quotation.
6. **Social proof** — Full-width blue video story with stepped pixel boundary.
7. **Objection handling** — Split FAQ.
8. **Closing call** — Shared monumental statement and footer.

**Transfer:** Localize the launch color to the opening, then return to black for substance and proof.

### Commercial comparison

1. **Promise** — Two-line white-to-gray display above asymmetric plan cards.
2. **Social proof** — Monochrome logos.
3. **Pricing detail** — Grouped comparison rows with persistent plan actions and shaded entry column.
4. **Objection handling** — FAQ and direct support route.
5. **Closing call** — Shared monumental statement and footer.

**Transfer:** Prioritize differences and purchase reassurance; avoid introducing a new visual theme for the tables.

### Proof and customer-story library

1. **Emotional proof** — Giant rotating first-person quote with playful object and arrow controls.
2. **Proof discovery** — Compact category filters and three-column photographic or blue-duotone stories.
3. **Breadth** — Extensive monochrome logo matrix.
4. **Featured proof** — Blue video story with stepped edges.
5. **Independent validation** — Mixed-type trust headline, awards and varied-height quote wall.
6. **Closing call** — Shared monumental closing and footer.

**Transfer:** Use a spectrum of proof forms rather than repeating identical quote cards throughout.

## Writing

Confident and technically specific, with short mischievous turns of phrase against otherwise practical explanations. The product sounds capable because it explains what happens, where information goes and what the reader can do next.

**Do not copy:** Do not reuse Dovetail's name, product names, customer logos, quotations, proprietary objects, exact claims, customer counts, savings figures, awards or trial terms as assets or assertions for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team. Name the product as the actor when explaining a mechanism; let actual customer quotations use first person.
- **Rhythm:** Punchy short hero promises alternate with fuller explanatory paragraphs. Chapters often pair an action with its outcome; lists of familiar artifacts build recognition, then a short sentence lands the point.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short imperative that turns an abstract system into a physical action. | 4–7 words | “Feed the facts machine” |
| Chapter headline | Direct verb plus concrete transformation; emphasize a key phrase typographically. | 5–10 words | “Turn raw data into rich context”<br>“Put the customer in every prompt” |
| Pain-point headline | Speak the reader's frustration in their own first-person language. | 8–14 words | “Leadership wants one answer. I have five dashboards.” |
| Benefit contrast | Replace a familiar weak approach with a concrete stronger one. | 5–9 words | “Build from evidence, not vibes” |
| Supporting explanation | Start with inputs or a mechanism, then explain the usable outcome. | 25–55 words | “From support tickets to call center conversations, [Brand] runs pre-inference on every customer interaction and pulls it into a live, context-rich system of record.” |
| Action | Plain verb with an explicit next step, no metaphor. | 2–6 words | “Book a demo”<br>“Start a 60-day free trial” |
| Closing statement | A terse conviction split into a monumental stack. | 4–6 words | “The best never guess” |

**Words and phrasing to use:** build; ask; turn; connect; every; your team; real; context; traceable; from … to …; not …

**Avoid:** revolutionary ecosystem; unparalleled synergy; unlock limitless potential; effortlessly transform everything; vague AI magic without an explanation

**Rules:**

- Use concrete work artifacts and recognizable situations to explain a complex system.
- Pair each broad benefit with a mechanism or a real proof item nearby.
- Allow one playful metaphor in a major headline; keep buttons and explanatory text literal.
- Use spoken customer language for objections, then answer directly.
- Keep adoption assurances specific and verifiable instead of vague promises of ease.

## Do's and Don'ts

### Do

- Keep the ordinary canvas near black and the main text soft white; use #a7a7a7 for supporting detail.
- Pair 96px/100px Inter chapter type with 120px/100px pixel-serif emphasis.
- Maintain the 1192px desktop inner width and 32px grid gutters.
- Use 8px corners consistently across buttons, panels and photographic media.
- Stage at least one tactile headline object and one technical diagram or dark workflow collage.
- Use 48px interiors for large proof cards and a clear 760:400 width relationship in proof pairs.
- Retain 14px uppercase mono labels with 1px tracking, rather than replacing them with tiny sans captions.
- Give the default closing artwork a full 900px scene and 56px action pair.

### Don't

- Do not turn every section into a separate light or gray background band; the dark field should remain continuous.
- Do not replace the pixel-serif accent with smooth Georgia styling or an italic display face.
- Do not round 8px action rectangles into 9999px pills.
- Do not put a colored icon badge above every feature; product fragments carry most feature imagery.
- Do not make all proof monochrome: natural portraits and vivid closing badges are deliberate exceptions.
- Do not apply a global neon glow to cards; edges are usually just 1px and faint.
- Do not make both conversion buttons electric blue; preserve the quiet glass alternative.
- Do not compress long-form comparisons into a decorative card grid; retain aligned 73px rows and a persistent plan context.

## Motion and responsive

### Motion

**Observed:**

- Primary blue actions declare opacity 150ms and hover opacity 0.85; glass actions declare color 200ms, background 200ms, opacity 200ms.
- Footer links declare color 200ms ease-out; navigation actions declare 300ms transitions.
- Capability narratives use sticky 900px stages and changing product scenes; story strips move through a horizontally masked field.
- Long-running linear animations of 60s and 170s are declared on product-page elements.

**Transfer:**

- Preserve the relationship between sticky system art and the current narrative stage.
- Keep button feedback short and subdued; do not animate every visual layer with the same effect.
- Use soft edge masks on horizontally moving proof or logo fields so movement disappears into the canvas.

**Unknown:**

- Exact choreography and timing for 3D objects, character fields and scroll-linked scene changes.
- Whether declared long-running animations correspond to all visible moving proof fields.

### Responsive

**Observed:**

- Declared width breakpoints include 588px, 799px, 800px, 1185px, 1280px, 1281px, 1512px and 1513px; some pages additionally use 600px or 1023px.

**Transfer:**

- On narrow layouts, preserve the headline/object relationship by reducing the object with the text and allowing deliberate line breaks.
- Stack the split media after its narrative, retain the blue quotation before its dark metric partner, and turn six footer columns into readable grouped rows.
- Treat giant typography and media as compositions that scale together; do not merely retain 124px side padding on narrow screens.

**Unknown:**

- Exact narrow-screen typography, column changes, menu behavior and spacing recipes.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
