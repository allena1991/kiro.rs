# FlutterFlow — violet-lit visual machinery

## Overview

A near-black, violet-lit style that makes powerful software feel tangible and approachable. Rounded geometric sans headlines float above cinematic interface scenes, with restrained gray supporting copy and small, bright conversion controls. The pacing is spacious at section level but richly detailed inside product imagery, suited to technical platforms and visual tools.

### Essentials

- Geometric promises stretch across the dark stage: Urbanist 600 at 100px/1 for the opening and 72px/1 for major chapters, normally without tightened tracking.
- The opening sells through a real working surface: a centered headline, 20px/28px support, one violet action, then a 1288px-wide interface frame with 24px corners beginning within the first 900px.
- Violet is light and emphasis, not the entire canvas: #060311 dominates; #4b39ef appears in actions, fine illustrations, a highlighted number and localized glows. Broader purple fills are concentrated in proof cards.
- Conversion controls are soft rectangles rather than generic pills: 16px corners, a #4b39ef-to-#2b2189 gradient, Urbanist 600 with 0.03em tracking; the compact header action reverses to white.
- Feature chapters combine words with a small visual interruption: 72px headlines contain thin violet line drawings or overlapping circular portraits. Recreate the interruption with a simple relevant SVG symbol when original art is unavailable.
- Interfaces emerge from darkness: 20px card corners, 1px white edges at 0.06 alpha, upper-left gray radial illumination and lower-edge fades. Use a convincing simplified workflow panel if full product media is unavailable.
- The closing promise is monumental rather than a small banner: 72px text, a violet number enlarged to 100.8px/0.9 when quantified proof is available, a soft central glow and an 88px-high action; without a verified metric, retain the oversized promise and light.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#4b39ef` | `--color-primary` | accent, action, text, border | Action gradient start, eyebrow text, outlined graphics and emphasized numerals. |
| Deep violet | `#2b2189` | `--color-gradient-end` | action | Lower end of the primary action gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet highlight | `#6d5ef9` | `--color-progress` | accent | Active 3px feature progress line. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight violet | `#060311` | `--color-canvas` | background, text | Default page canvas and dark text on the white header action. |
| Faint separator | `#12101d` | `--color-rule` | border | Visible white at 0.05 alpha over the canvas; footer and large media edges. |
| Card edge | `#15121f` | `--color-card-edge` | border | Visible white at 0.06 alpha over the canvas; feature card outlines. |
| Media edge | `#1f1c29` | `--color-media-edge` | border | Visible white at 0.1 alpha over the canvas; hero frame and inactive progress tracks. |
| Inactive gray | `#6a6870` | `--color-dim` | text | Visible white at 0.4 alpha over the canvas; inactive feature descriptions. |
| Cool gray | `#9ba1ae` | `--color-muted` | text, link | Supporting paragraphs, footer links and secondary information. |
| Lavender gray | `#a8a7ac` | `--color-quote-text` | text | Visible white at 0.65 alpha over the canvas; testimonial copy sits on richer violet surfaces. |
| Soft white | `#b4b3b8` | `--color-nav-text` | text, link | Visible white at 0.7 alpha over the canvas; navigation text. |
| White | `#ffffff` | `--color-foreground` | text, action | Headlines, active copy and white header action. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#00c950` | `--color-status` | accent | Tiny operational-status indicator, not a general marketing accent. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical feature pages | Technical lavender | `#a99bff` | `--color-lavender` | text, accent | Index numbers and technical labels. |
| pricing comparisons | Soft row wash | `#100d1b` | `--color-row` | surface, border | Visible white at 0.04 alpha over the canvas; alternate comparison rows and their rules. |
| pricing and technical feature pages | Raised charcoal violet | `#161320` | `--color-card` | surface | Solid panels for denser content. |
| technical feature pages | Panel edge | `#1a1724` | `--color-panel-edge` | border | Visible white at 0.08 alpha over the canvas; technical panels and index dividers. |

## Typography

- **Urbanist Variable** — Display headlines, feature titles and conversion labels. Rounded geometric sans with open circular forms, a single-storey a and a friendly but substantial semibold. Font stack: "Urbanist Variable", ui-sans-serif, system-ui, sans-serif.
- **Inter Variable** — Supporting prose, navigation and metadata. Compact neutral sans that keeps detailed explanations subordinate to geometric headlines. Font stack: "Inter Variable", ui-sans-serif, system-ui, sans-serif.
- **ui-monospace** (only for technical feature pages) — Numbered indexes, documentation paths and commands. Functional system monospace, used sparingly as technical annotation. Font stack: "ui-monospace", SFMono-Regular, Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | Urbanist Variable | 600 | 100.8px | 0.9 | normal | One emphasized quantity embedded in a 72px closing sentence. |
| display | Urbanist Variable | 600 | 100px | 1 | normal | Default opening promise. |
| heading | Urbanist Variable | 600 | 72px | 1 | normal | Major capability chapters and monumental closing promise. |
| feature-title | Urbanist Variable | 500 | 24px | 1.3 | normal | Sentence-like captions at the top of feature cards. |
| resource-title | Urbanist Variable | 600 | 24px | 1.333333 | normal | Short resource card names. |
| closing-button | Urbanist Variable | 600 | 24px | 1 | 0.03em | Oversized final action. |
| lead | Inter Variable | 400 | 20px | 1.4 | normal | Opening support line and concise explanations below major headings. |
| chapter-kicker | Inter Variable | 600 | 20px | 1.4 | 0.6em, uppercase | Widely spaced statement introducing the first capability chapter; use once rather than on every heading. |
| button | Urbanist Variable | 600 | 18.1px | 1 | 0.03em | Primary hero conversion label. |
| body-relaxed | Inter Variable | 400 | 18px | 1.625 | normal | Tabbed feature explanations and longer introductory support. |
| body | Inter Variable | 400 | 16px | 1.5 | normal | Feature explanations and ordinary supporting paragraphs. |
| header-button | Urbanist Variable | 600 | 16px | 1 | 0.03em | Compact reversed navigation action. |
| quote | Inter Variable | 400 | 14.4px | 1.625 | normal | Customer quotation text in rich violet cards. |
| resource-copy | Inter Variable | 400 | 14px | 1.625 | normal | Resource card descriptions. |
| eyebrow | Inter Variable | 600 | 14px | 20px | 0.1em, uppercase | Trust labels and concise section context. |
| nav | Inter Variable | 500 | 14px | 20px | normal | Top-level navigation. |
| small | Inter Variable | 400 | 14px | 20px | normal | Footer links and compact supporting details. |
| footer-heading | Urbanist Variable | 600 | 14px | 20px | normal | Footer group titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical feature pages | technical-display | Urbanist Variable | 600 | 96px | 1 | -0.015em | Named suite opening, paired with numbered jump links. |
| technical feature pages | technical-closing | Urbanist Variable | 600 | 60px | 1.08 | normal | Left-aligned final promise above documentation index. |
| gallery pages | case-title | Urbanist Variable | 700 | 48px | 1 | normal | Featured project title over imagery. |
| technical feature pages | technical-heading | Urbanist Variable | 600 | 48px | 1.1 | normal | Technical capability chapters and FAQ heading. |
| pricing pages | price | Urbanist Variable | 700 | 36px | 40px | normal | Plan price with smaller billing qualifier. |
| pricing comparisons | comparison-category | Urbanist Variable | 600 | 18px | 28px | 0.2em, uppercase | Category labels dividing feature tables. |
| technical feature pages | question | Urbanist Variable | 600 | 18px | 1.35 | normal | Accordion question. |
| technical feature pages | index-label | Inter Variable | 400 | 17px | 1.5 | normal | Documentation index link title. |
| technical feature pages | answer | Inter Variable | 400 | 15.5px | 1.65 | normal | Accordion answer. |
| technical feature pages | index-path | ui-monospace | 400 | 12.5px | 1.5 | normal | Muted path at the far end of an index row. |
| technical feature pages | index-number | ui-monospace | 400 | 12px | 1.5 | normal | Two-digit documentation index number. |

**Notes:**

- The default display face is rounded and semibold, not condensed or grotesk-heavy. Keep normal tracking on the 100px and 72px default roles.
- Buttons add 0.03em tracking while eyebrows expand much more. The 0.6em chapter kicker is a distinctive introductory accent, not the normal label recipe.
- Only the technical suite opening tightens tracking to -0.015em; its 48px chapter headings are a scoped, denser alternative to the default 72px chapters.
- The closing number is 1.4 times its surrounding headline size. Keep it inline with the sentence rather than turning it into a separate dashboard KPI.

## Layout

**Density:** Airy chapter pacing with dense, highly detailed interface scenes; compact controls and metadata remain secondary.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight label and metadata relationships. |
| 12px | Inline headline symbol gaps and resource-title separation. |
| 16px | Three- and four-column card grid gaps. |
| 20px | Gallery tile gaps and testimonial row gaps. |
| 24px | Headline-to-support gap, bento gutters and pricing grid gaps. |
| 32px | Support-to-hero-action gap and standard card padding. |
| 36px | Testimonial card inner padding. |
| 40px | Resource padding, feature selector gutters and closing action separation. |
| 48px | Hero action-to-interface gap and technical index column gap. |
| 64px | Heading-to-chapter-content separation and trust band vertical padding. |
| 96px | Product-detail chapter and desktop footer vertical padding. |
| 128px | Default large-section vertical padding. |

### Containers and grids

- **marketing-container**: max width 1352px · side padding 32px. Centered outer container, including side padding; at 1440px the usable content spans 1288px with 76px total side margins.
- **feature-grid**: 3 columns · gap 16px. Equal-width feature cards, about 419px each; text sits above dark floating interface fragments.
- **bento-grid**: 2 columns · gap 24px. One tall feature panel on the left beside two stacked panels on the right.
- **resource-grid**: 4 columns · gap 16px. Compact equal resource cards, about 310px each.
- **closing-container**: max width 896px. Centered, limited-width final promise and action.
- **footer-grid**: 6 columns · gap 32px. Brand/social column followed by five link groups; 96px vertical padding.
- **detail-rail** (only for long product detail pages): 2 columns · gap 24px. A 200px left section-navigation rail beside a 1064px content area.
- **plan-grid** (only for pricing pages): 4 columns · gap 24px. Equal 304px plan columns with aligned actions.
- **gallery-grid** (only for gallery pages): 4 columns · gap 20px. Portrait project tiles about 307px by 409px; featured project sits above at 896px by 560px.
- **technical-index** (only for technical feature pages): 2 columns · gap 48px. Two columns of compact numbered documentation links.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 16px |
|  | feature-cards | 20px |
|  | media-frames | 24px |
| gallery pages | featured-project | 35.2px |
| technical feature pages | technical-actions | 10px |
| technical feature pages | technical-panel | 16px |
| pricing controls and gallery awards | toggle-and-badge | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| technical feature openings | technical-deck-front | `0px -30px 100px 0px rgba(0,0,0,0.55), 0px 0px 0px 1px rgba(75,57,239,0.35)` | Front frame of the layered interface deck; ordinary cards rely on gradients and edges, not drop shadows. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous background between chapters.

**CSS:** `background: #060311; color: #ffffff`

#### Violet atmosphere · level 0

**Use:** Localized illumination behind an opening or important statement.

**CSS:** `background: radial-gradient(60% 50% at 50% 0px, rgba(75,57,239,0.35), rgba(0,0,0,0) 70%)`

**Observed:** A soft top-centered purple haze disappears into the dark canvas; it is not a hard-edged colored band.

**Transfer:** Keep the glow behind the promise and away from supporting text contrast.

#### Feature glass · level 1

**Use:** Default feature-card material.

**CSS:** `background: radial-gradient(circle farthest-side at 0px 0px, rgba(87,87,87,0.4), rgba(6,3,17,0) 44%), #060311; border: 1px solid rgba(255,255,255,0.06); border-radius: 20px; backdrop-filter: blur(8px); overflow: hidden`

**Observed:** Gray light catches the upper-left corner while the rest blends into the canvas.

**Transfer:** Retain a dark lower half so the interface fragment can fade into its backing.

#### Media frame · level 1

**Use:** Large product video or interface scene.

**CSS:** `border: 1px solid rgba(255,255,255,0.1); border-radius: 24px; overflow: hidden`

**Observed:** The opening frame has a slightly stronger edge than later frames, which use white at 0.05 alpha.

**Transfer:** Let the product fill the frame without a thick mock-browser surround.

#### Violet proof · level 1

**Use:** Customer quotation cards.

**CSS:** `background: linear-gradient(145deg, rgba(15,10,45,0.97) 0%, rgba(30,20,80,0.95) 35%, rgba(55,30,160,0.75) 70%, rgba(80,50,200,0.6) 100%); border: 1px solid rgba(90,60,210,0.35); border-radius: 20px`

**Observed:** One of the few substantial saturated areas: deep indigo at the upper-left becoming brighter violet at the lower-right.

**Transfer:** Reserve this richer material for human proof or another major credibility moment.

#### Closing glow · level 0

**Use:** Behind the monumental final call.

**CSS:** `background: radial-gradient(rgba(75,57,239,0.15), rgba(0,0,0,0) 70%)`

**Observed:** Subtle centered illumination spans the full closing band.

**Transfer:** Keep the large text white and the glow subordinate.

#### Solid technical panel · level 1

**Only for:** pricing and technical feature pages

**Use:** Dense information groups.

**CSS:** `background: #161320; border: 1px solid rgba(255,255,255,0.08); border-radius: 16px`

**Observed:** Pricing uses 20px corners and a 0.06-alpha white edge; resource panels on detailed product pages use 24px corners and a 0.05-alpha edge.

**Transfer:** Use solid charcoal for reading-heavy content instead of the more atmospheric default feature material.

#### Recommended plan · level 1

**Only for:** pricing pages

**Use:** One recommended tier.

**CSS:** `background: linear-gradient(rgba(75,57,239,0.4), rgba(75,57,239,0.05)); border: 1px solid #4b39ef; border-radius: 20px`

**Observed:** The violet wash is strongest at the top and nearly disappears at the bottom.

**Transfer:** Highlight only one tier and pair it with the filled action.

## Components

### Navigation

**Use:** Persistent global navigation.

**CSS:** `position: fixed; top: 0px; height: 68px; width: 100%; z-index: 50; background: rgba(6,3,17,0.8); backdrop-filter: blur(12px)`

**Text style:** `nav` — Inter Variable 500 · 14px/20px

**Observed:** Brand mark at left, primary destinations centered, search with a small keyboard hint and login at right, followed by Header action. Links have 8px vertical and 16px horizontal padding.

**States:** Declared: hover links turn white; focus-visible uses a 2px violet outline with 2px offset.

### Primary button

**Use:** Default primary conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 16px 32px; border-radius: 16px; background: linear-gradient(in oklab, #4b39ef 0%, #2b2189 100%); color: #ffffff`

**Text style:** `button` — Urbanist Variable 600 · 18.1px/1 · tracking 0.03em

**Observed:** A single label with no compulsory arrow; centered below hero support. Technical pages use 10px corners and may pair it with a transparent outlined secondary action. Secondary actions use a 1px white border at 0.2 alpha and invert to white on hover.

**States:** Declared: hover and active filter values are unspecified; focus-visible uses a 2px #4b39ef outline with 2px offset.

### Header action

**Use:** Compact high-contrast action at the end of navigation.

**CSS:** `display: flex; padding: 10px 20px; border-radius: 16px; background: #ffffff; color: #060311; height: 36px; align-items: center; justify-content: center`

**Text style:** `header-button` — Urbanist Variable 600 · 16px/1 · tracking 0.03em

**Observed:** Visually pill-like because its height is short relative to its rounded corners; it is the only default white filled conversion control.

**States:** Declared: hover white background becomes 90% opaque; focus-visible uses a 2px #4b39ef outline with 2px offset; active background becomes 80% opaque.

### Closing action

**Use:** Large action below a monumental final statement.

**CSS:** `display: inline-flex; padding: 32px 64px; border-radius: 16px; background: linear-gradient(in oklab, #4b39ef 0%, #2b2189 100%); color: #ffffff; align-items: center; justify-content: center`

**Text style:** `closing-button` — Urbanist Variable 600 · 24px/1 · tracking 0.03em

**Observed:** Standalone, centered and deliberately much larger than the hero action; 88px total height.

**States:** Declared: hover and active filter values are unspecified; focus-visible uses a 2px #4b39ef outline with 2px offset.

### Feature card

**Use:** Explain one capability with a visual fragment.

**CSS:** `position: relative; overflow: hidden; border-radius: 20px; border: 1px solid rgba(255,255,255,0.06); background: radial-gradient(circle farthest-side at 0px 0px, rgba(87,87,87,0.4), rgba(6,3,17,0) 44%), #060311; backdrop-filter: blur(8px)`

**Text style:** `feature-title` — Urbanist Variable 500 · 24px/1.3

**Observed:** Inner wrapper has 32px padding for equal cards and 40px for tall bento panels. Sentence title sits above a dark interface fragment; media fades into the lower portion. Equal cards are about 419px square; the tall bento variant spans two rows.

**Transfer:** Show a single recognizable operation rather than a full tiny dashboard.

### Resource card

**Use:** Compact next-step navigation.

**CSS:** `display: flex; flex-direction: column; padding: 40px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.06); background: radial-gradient(circle farthest-side at 0px 0px, rgba(87,87,87,0.25), rgba(6,3,17,0) 50%), #060311`

**Text style:** `resource-title` — Urbanist Variable 600 · 24px/1.333333

**Observed:** Thin violet illustration upper-left, small outlined circular northeast arrow upper-right, title below, then Resource-copy. Four cards form an equal-height row. Detailed product pages use a solid charcoal variant with 32px padding and 24px corners.

**States:** Declared: hover border becomes rgba(75,57,239,0.3); focus-visible uses a 2px #4b39ef outline with 2px offset.

### Testimonial card

**Use:** Human credibility in a wide moving wall.

**CSS:** `display: flex; flex-direction: column; flex-shrink: 0; width: 520px; padding: 36px; border-radius: 20px; border: 1px solid rgba(90,60,210,0.35); background: linear-gradient(145deg, rgba(15,10,45,0.97) 0%, rgba(30,20,80,0.95) 35%, rgba(55,30,160,0.75) 70%, rgba(80,50,200,0.6) 100%)`

**Text style:** `quote` — Inter Variable 400 · 14.4px/1.625

**Observed:** Organization name above the quote; person's name and smaller job title anchored at the bottom. Two staggered horizontal rows extend beyond both viewport edges; no stars or portrait are required.

**Transfer:** Use authentic short accounts of concrete work; keep varied quote length without losing bottom alignment.

### Footer link

**Use:** Low-emphasis destination in grouped footer navigation.

**CSS:** `color: #9ba1ae`

**Text style:** `small` — Inter Variable 400 · 14px/20px

**Observed:** Stacked in lists with 10px gaps below small semibold group headings. Footer keeps the dark page canvas and a faint full-width top rule; brand, four social marks and compact copyright occupy the first column. A 10px green dot identifies operational status.

**States:** Declared: hover turns white; focus-visible uses a 2px #4b39ef outline with 2px offset.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side tier selection.

**CSS:** `display: flex; flex-direction: column; padding: 32px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.06); background: #161320`

**Text style:** `price` — Urbanist Variable 700 · 36px/40px

**Observed:** Plan name, price and billing qualifier, short audience description, action, then violet-check feature list. Keep the introductory block tall enough to align actions across all tiers. Recommended plan uses Recommended plan surface and Primary button; other tiers use outlined actions.

**Transfer:** Treat prices and limits as the new product's facts; preserve the balanced equal-column construction.

### Comparison cell

**Only for:** pricing comparisons

**Use:** Dense feature comparisons below plan cards.

**CSS:** `padding: 16px 20px; border-bottom: 1px solid rgba(255,255,255,0.04)`

**Text style:** `body` — Inter Variable 400 · 16px/1.5

**Observed:** Wide feature-name column followed by four centered tier columns. Alternating rows have white at 0.04 alpha; most rows are 57px high. Violet checks, muted unavailable marks and short quantities communicate status. Category labels have 56px top padding and a violet rule; plan-price and action headers remain visible while reading the table.

**Transfer:** Separate categories through spacing and fine rules, not independent rounded cards for each row.

### FAQ question

**Only for:** technical feature pages

**Use:** Expandable objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 18px; padding: 20px; border-radius: 12px`

**Text style:** `question` — Urbanist Variable 600 · 18px/1.35

**Observed:** Question left, lavender plus in a dark violet circular chip right. Rows sit inside one 896px-wide Solid technical panel with 6px inset padding, rather than separate floating cards. Expanded content uses Answer with inline documentation links.

**States:** Declared: hover background rgba(255,255,255,0.03); focus-visible uses a 2px #4b39ef outline with -2px offset.

### Documentation index row

**Only for:** technical feature pages

**Use:** Practical closing navigation into documentation.

**CSS:** `display: grid; grid-template-columns: 40px minmax(0px, 1fr) auto; align-items: baseline; gap: 16px; padding: 18px 0px; border-bottom: 1px solid rgba(255,255,255,0.08)`

**Text style:** `index-label` — Inter Variable 400 · 17px/1.5

**Observed:** Lavender two-digit number, white feature name, a dotted leader, then a muted monospace documentation path. Two columns use 48px separation; rows are about 63px tall.

**States:** Declared: hover unspecified; focus-visible uses a 2px #4b39ef outline with 2px offset and 4px radius.

## Imagery and graphics

### Working product stage

**Use:** Opening and major capability demonstrations.

**Observed:** Large dark application interfaces with readable structural hierarchy: sidebars, canvas, selected objects and a central mobile preview. The opening is broad and frontal; later scenes isolate panels, menus and code windows. Background UI is dimmed while one operation stays legible. White and mint inside the software belong to its own interface, not the marketing palette.

**Transfer:** Use actual interface media or a simplified believable working scene with a sidebar, main artifact and inspector. Keep a single operation in focus; use fewer readable controls instead of tiny decorative noise.

**Build:** Compose a 1288px-wide dark rectangular scene inside Media frame. Put a narrow rail at left, one central artifact and a darker inspector at right. Layer a larger operation panel above it; overlay rgba(6,3,17,0.55) only on background planes, then add a bottom gradient from transparent to the canvas.

### Atmospheric violet light

**Use:** A signature supporting layer behind openings and the final call.

**Observed:** Soft, broad purple light near the upper center of the opening; the closing light is weaker and centered behind text. No sharp spotlights or rainbow beams.

**Transfer:** Recreate with gradients rather than requiring elaborate 3D artwork.

**Build:** Place an absolute full-section layer behind content. For the opening use a radial ellipse 60% wide and 50% high centered at 50% 0px, rgba(75,57,239,0.35) fading to transparent by 70%. For the closing use rgba(75,57,239,0.15) at center with the same fade; retain the #060311 base.

### Headline interruptions

**Use:** Signature visual punctuation in major benefit headlines.

**Observed:** Fine violet symbols such as sliders, a code window, a rocket or an outlined heart sit between words at the scale of the type. One collaboration treatment inserts three overlapping 80px circular portraits and adds outlined cursors with small black/white name labels nearby.

**Transfer:** Include a relevant simple line drawing within a headline. For collaborative products, circular team portraits can replace the symbol; do not turn every heading into an emoji line.

**Build:** Create a 64px to 80px SVG viewBox with simple open paths in #4b39ef, approximately 1px stroke and no fill. Keep 12px inline gaps and align to the heading's visual center. Portrait alternative: three 80px circles overlapping by 24px, with a small outlined cursor and a 14px label positioned just outside the word line.

### Multi-device outcome

**Use:** A broad visual payoff after explaining capabilities.

**Observed:** Phone, tablet and laptop display the same finished application; the phone is tallest, the landscape devices sit lower on either side. Hardware edges are subtle silver/black and the application imagery is more photographic and warm than the marketing canvas.

**Transfer:** Show the same output across relevant formats, or pair a large finished artifact with smaller contextual variants. Preserve the unequal silhouettes and open dark backing.

**Build:** Layer three transparent device renders across the stage. Give the portrait central object the strongest height, align smaller landscape objects to a lower baseline, and leave space around the silhouettes rather than putting each in a card.

### Portrait output gallery

**Only for:** gallery and customer-output pages

**Use:** Visual proof through many finished products.

**Observed:** Colorful portrait interfaces run edge-to-edge within rounded tiles; a four-column grid uses 20px gaps. A separate full-width phone strip uses 300px by 650px images with 28px gaps and clipped side items. Featured work is an 896px by 560px tile with a stronger bottom black fade and overlaid title/award.

**Transfer:** Keep each project's own palette intact; arrange finished outputs consistently rather than tinting them all violet. A featured piece can use photography or a close-up of the artifact.

### Layered interface deck

**Only for:** technical suite openings

**Use:** Suggest multiple tools within a single product family.

**Observed:** Four dark interface windows stack vertically in depth, the front about 1152px wide with 20px top corners. Rear windows narrow progressively to about 1100px, 1048px and 996px, with 2px, 4px and 6px blur and lower brightness. Small label chips follow the depth treatment; the foreground label reverses to white.

**Transfer:** Stack genuine workflow scenes or three simplified panels with distinct structures, keeping one crisp active item rather than several competing demos.

**Build:** Center successive panels behind the front window, reducing width by about 52px per layer. Use blur(2px), blur(4px), blur(6px), brightness(0.8), brightness(0.65), brightness(0.5), and opacity 0.85, 0.65, 0.45 respectively. Place soft black shadows above each panel and a thin violet edge on the front.

### Icons

**Observed:** Small controls use simple rounded outline SVGs, usually 16px with 2px strokes. Pricing checks are 24px with a stronger 3px rounded violet stroke. Resource illustrations are much thinner, violet, and more expressive than the functional icons; footer social marks are muted solid 20px icons.

**Transfer:** Separate functional icons from headline drawings: use a consistent rounded outline set for controls and sparse custom line symbols for expressive moments.

## Section recipes

How recurring sections are built.

### First screen: Working-surface opening

**Observed:** A 68px Navigation overlays a near-black stage with a broad violet haze behind the upper center. The single-line 100px/1 Urbanist promise spans about five-sixths of the page; the support sits centered below with 24px separation and a single Primary button follows after 32px. Media frame begins 48px below the action, about halfway down the 900px screen, and spans the 1288px content width. Layers read as canvas, light, promise/support/action, then the dark working interface with a bright central artifact. The first 900px contains the complete promise, support and action plus the upper majority of the interface; the frame's bottom and trust material fall below the fold.

**Transfer:** Keep the same scale and promise-to-demonstration relationship for another product. Without full media, construct a credible simplified operation with one bright artifact inside dark tool panels. Gallery openings reduce the title to 72px and show a featured output below; detailed product pages use a left-aligned 100px promise beside angled interface art and a section rail; pricing opens with centered promise and segmented controls; technical suites use Technical-display, numbered jump links, two actions and Layered interface deck.

**Avoid:** Do not substitute a small text-left/image-right generic SaaS hero for the default. Do not place a bright decorative illustration above the promise or hide the product demonstration entirely below the first screen.

**Text style:** `display` — Urbanist Variable 600 · 100px/1

### Illustrated chapter heading

**Observed:** Centered 72px heading, often split into two verbal parts with Headline interruptions between them. An introductory chapter adds Chapter-kicker 24px above. Major sections use 128px top/bottom padding and usually 64px between the heading group and content.

**Transfer:** Write a strong capability phrase and place one small, relevant symbol where a natural pause occurs. Allow wrapping by phrase rather than shrinking the entire title.

**Text style:** `heading` — Urbanist Variable 600 · 72px/1

### Feature bento and triptych

**Observed:** Feature card appears as a 2-column bento with one tall panel and two stacked neighbors, or as three equal cards with 16px gaps. Titles sit high and isolated interface fragments occupy the remainder, fading toward the bottom.

**Transfer:** Choose the bento when one capability needs a taller explanation; use the triptych for comparable operations.

### Tabbed demonstration

**Observed:** Illustrated chapter heading above three explanatory selectors separated by 40px. Inactive copy is white at 0.4 alpha, active copy white; each selector has a 3px white-at-0.1 progress track with a violet active segment. A broad product scene follows below.

**Transfer:** Pair a small set of distinct promises with corresponding interface scenes; use brightness and the thin progress line to show which is active.

### Finished-output proof

**Observed:** Large chapter heading gives way to either unequal device silhouettes on the dark canvas or a viewport-wide horizontal strip of tall finished outputs. Media supplies the color while surrounding text stays white and gray.

**Transfer:** Present the result of using the product, not another list of features.

### Violet quotation wall

**Observed:** Centered 72px headline with a fine line-art interruption above two offset rows of Testimonial card. Rows use 20px gaps and extend beyond the viewport boundaries.

**Transfer:** Use this as a strong credibility moment; on a shorter page one carefully composed row can carry the same rich material.

### Resource runway

**Observed:** Centered multiline 72px invitation above four Resource cards in a row. Cards pair a violet line illustration and northeast arrow with a short heading and muted description.

**Transfer:** Offer practical ways to begin or get help, adapted to the new product rather than copying a fixed list.

### Quantified closing call

**Observed:** Closing glow behind an 896px centered text block, a 72px promise with a violet 100.8px inline quantity, then Closing action after 40px. Band uses 128px vertical padding. Gallery variants omit the number and use a belonging-oriented promise with 32px action separation.

**Transfer:** Make one last confident invitation. Use a verified metric as part of a grammatical sentence, or retain the monumental sentence without a number.

### Six-column footer

**Observed:** A faint white-at-0.05 top rule separates the close from a 525px-tall footer. Marketing-container has 96px vertical padding; six columns use 32px gaps. First column contains brand, muted social marks and compact copyright; five link groups use Footer-heading and Footer link. Operational status has one tiny green light.

**Transfer:** Keep footer typography small and functional. Group real destinations instead of introducing another promotional card.

### Detailed capability chapter

**Only for:** long product detail pages

**Observed:** A 200px side rail stays separate from the content. Left-aligned 72px chapter heading, 40px gap to three or four columns of 16px/24px support, then a large dark media frame with floating UI panels and violet light along the bottom. Chapters use 96px vertical padding.

**Transfer:** Use the rail for genuine navigable chapters, and keep multiple paragraphs aligned as peers rather than long body text.

### Pricing decision and comparison

**Only for:** pricing pages

**Observed:** Centered 100px opening, short support, audience segmented control and monthly/annual toggle. Four Plan cards appear below. A 72px comparison heading introduces a long table with repeated plan headers, Comparison cells, violet category labels and alternating faint row washes. A trust-logo band and Quantified closing call lead to the shared footer.

**Transfer:** Separate quick tier selection from exhaustive detail; make one tier visually recommended.

### Technical chapter and objection panel

**Only for:** technical feature pages

**Observed:** Eyebrow, 48px heading, 18px relaxed explanatory copy, then a large interface scene. Chapters alternate centered introductions and split heading/support pairs. Setup instructions use numbered rows with dark command boxes; FAQ question groups into one narrow solid panel.

**Transfer:** Explain where the feature runs and what the user does before showing the interface. Keep commands and setup details subordinate to the capability promise.

### Technical closing index

**Only for:** technical feature pages

**Observed:** Technical-closing sits left with an eyebrow; a smaller violet-tinted action panel sits right with primary/secondary buttons and direct installer links. Documentation index row forms two columns below, using dotted leaders, two-digit numbers and paths. The shared footer follows.

**Transfer:** For developer-focused products, let the close offer both a conversion and direct access to implementation details.

## Page flow

**Storyline:** Promise → visible working proof → capability chapters → finished outcomes and credibility → practical next steps → strong invitation → structured footer.

### Broad marketing landing page

1. **Promise** — One oversized geometric statement, short support, violet action and working interface.
2. **Social proof** — Muted monochrome customer marks in a horizontal trust strip.
3. **Capability chapters** — Illustrated heading pairs, bento panels, tabbed demonstrations and equal feature cards.
4. **Outcome proof** — Multi-device results, ownership-oriented demonstration and portrait output strip.
5. **Credibility** — Rich violet quotation wall.
6. **Enablement** — Four illustrated resource cards.
7. **Closing call** — Monumental invitation with enlarged inline metric, then six-column footer.

**Transfer:** Use the narrative arc to move from promise to believable working detail and then confidence; a new page can shorten or rearrange the chapters.

### Customer-output gallery

1. **Invitation** — Centered 72px title, concise community-oriented support and outlined submission action.
2. **Featured proof** — Large landscape hero project with award/title overlay.
3. **Breadth** — Four-column portrait gallery with occasional dark award chips.
4. **Closing call** — Large belonging-oriented line, filled oversized action and shared footer.

**Transfer:** Let actual finished work carry the story; replace capability prose with consistent visual comparisons.

### Detailed product exploration

1. **Promise** — Left-aligned oversized headline, action, angled product art and chapter rail.
2. **Capability chapters** — Repeated 72px heading, parallel support paragraphs and large layered UI scene.
3. **Ecosystem proof** — Four-column integration tiles with small category tags and monochrome marks.
4. **Enablement** — Solid resource-card row.
5. **Closing call** — Quantified invitation and shared footer.

**Transfer:** Use the rail when the new product has enough real depth to warrant navigable chapters.

### Purchase decision

1. **Promise** — Large centered headline, audience selector and billing toggle.
2. **Plan selection** — Four aligned cards with one violet recommended plan.
3. **Detailed comparison** — Long categorized matrix with persistent plan context and clear inclusion marks.
4. **Social proof** — Trusted-by and featured-in logo bands.
5. **Closing call** — Quantified invitation and shared footer.

**Transfer:** Keep quick selection and exhaustive evaluation as distinct layers of information.

### Technical feature suite

1. **Orientation** — Named-suite headline, numbered tool jump links, paired actions and stacked demonstration deck.
2. **Capability chapters** — Smaller 48px headings with location labels, compatibility chips, actual UI demonstrations and setup commands.
3. **Objection handling** — Narrow single-panel FAQ.
4. **Closing call** — Split promise/action panel and numbered documentation index before shared footer.

**Transfer:** Use this denser variant for expert tools that need setup instructions and direct documentation routes.

## Writing

Confident, practical and encouraging. The promise is ambitious, but most supporting language explains a recognizable action rather than claiming abstract transformation.

**Do not copy:** Do not reuse FlutterFlow names or logos, customer identities, quotations, product screenshots, proprietary artwork, adoption statistics, prices, request limits or performance claims. Source examples illustrate voice only; all claims and assets must belong to the new product.

- **Addressing the reader:** Speak directly to the reader through you and your. The product name appears in explanatory support; we appears mainly in welcoming help-oriented statements.
- **Rhythm:** Headlines favor short active phrases, sometimes paired with full stops. Supporting lines are usually one sentence; feature captions can be longer, sentence-like benefits. Ampersands and contractions make technical content feel approachable.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Two concise outcome statements with parallel verbs. | 4–8 words | “Build Better. Launch Faster.”<br>“Rethink how you build” |
| Chapter headline | Active verb plus a tangible capability, often split around a visual symbol. | 2–10 words | “Customize everything”<br>“Own your code” |
| Supporting line | State what the product lets the reader do and how simply. | 10–25 words | “Export your code with the click of a button. No vendor lock-in.” |
| Action | Low-friction verb phrase, optionally naming the cost. | 2–5 words | “Start for Free”<br>“Submit your App” |
| Technical explanation | Concrete input, actual operation and observable result. | 15–35 words | “Write tests in plain English. An agent taps through a real build of your app and shows you, step by step, where it failed.” |
| Final invitation | A confident inclusive statement followed by one action. | 6–12 words | “You belong among the best” |

**Words and phrasing to use:** build; launch; customize; connect; your; quickly; with a few clicks; full control; get started

**Avoid:** revolutionary paradigm; unprecedented synergy; mysterious AI magic; luxury editorial language; aggressive scarcity

**Rules:**

- Lead with an action and its outcome; explain the mechanism in support.
- Use specific operations to substantiate easy and fast.
- Keep technical nouns in explanations and labels rather than filling every headline with jargon.
- Let help-oriented sections sound welcoming, not like documentation tables of contents.
- Use a verified number only when it strengthens a readable sentence.

## Do's and Don'ts

### Do

- Keep the default opening at 100px/1 Urbanist 600 and major chapters at 72px/1.
- Stage the working interface across 1288px of usable desktop content, with 24px frame corners.
- Use #060311 continuously between sections and localize violet light.
- Pair 20px feature-card corners with 1px white-at-0.06 edges and upper-left gray light.
- Include thin violet graphic punctuation in a major headline, with 12px inline gaps.
- Use 128px chapter padding and 16px card gutters to contrast spacious pacing with tight groups.
- Make the default final action 88px high through 32px vertical padding around a 24px label.
- Give long expert pages direct numbered documentation paths rather than only another sales action.

### Don't

- Do not replace the rounded Urbanist display with a condensed or heavy grotesk.
- Do not tighten default 100px or 72px headlines; negative tracking belongs to the technical suite variant.
- Do not make every action a 9999px pill; default buttons have 16px corners.
- Do not spread mint, green or multicolor product-interface accents into the marketing palette; green is reserved for the tiny status light.
- Do not add heavy drop shadows to ordinary feature cards; their depth comes from a faint edge and corner illumination.
- Do not use the saturated testimonial material as the background of every capability chapter.
- Do not enlarge 14px navigation and footer text to compete with the headline hierarchy.
- Do not turn the inline 100.8px closing metric into a row of independent statistic cards.

## Motion and responsive

### Motion

**Observed:**

- Declared common link and color transitions use 0.15s cubic-bezier(.4,0,.2,1); primary actions use all 0.25s with the same curve.
- Declared marquee animation uses 30s linear infinite; trust strips and quotation rows extend beyond viewport edges.
- Technical deck transitions declare top and transform at 0.75s cubic-bezier(0.22,0.8,0.2,1), with opacity and filter changes.
- Operational status includes a declared 1s infinite ping.

**Transfer:**

- Keep the long horizontal proof strips smooth and continuous rather than snapping between isolated cards.
- Use depth, blur and brightness together when changing the active technical-deck panel.
- Preserve the thin active progress line in tabbed demonstrations.

**Unknown:**

- Exact playback timing of product video and selector progress is not specified.
- Scroll-triggered choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Shared CSS declares width breakpoints at 640px, 768px, 1024px, 1280px and 1536px; technical pages add finer breakpoints.
- Container classes use 24px side padding below the 32px desktop padding. Large shared sections use 96px padding before increasing to 128px.
- Navigation destination and account groups are hidden below the 1024px desktop mode.
- Pricing grid declares one column, then two at 768px, then four at 1024px. Footer declares two columns, then three at 768px, then six at 1024px.
- Technical display declares 44px, then 64px at 768px, then 96px at 1024px; technical section headings declare 44px before 48px.

**Transfer:**

- As a design adaptation, stack feature panels while preserving the headline interruption and product-first hierarchy.
- Keep one front product scene crisp on narrow screens and reduce the prominence of rear deck panels.
- Allow gallery tiles to reflow without distorting their portrait aspect; retain each output's native color.
- Provide an accessible narrow-screen comparison presentation rather than compressing four tier columns into unreadable text.

**Unknown:**

- Mobile renderings, exact shared headline reductions and menu behavior are not established.
- The comparison table declares an 800px minimum width with an overflow-clipped wrapper; the intended narrow-screen interaction is uncertain.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
