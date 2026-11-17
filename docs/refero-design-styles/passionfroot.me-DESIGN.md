# Passionfroot — storybook software theatre

## Overview

A friendly software brand with the atmosphere of an animated adventure: expressive rounded serifs, milky interfaces, and cinematic worlds in plum, peach and pink. Spacious cream pages alternate practical product demonstrations with soft rainbow proof cards and richly lit illustrated scenes. It suits products that want technical capability to feel human and approachable rather than corporate or mechanical.

### Essentials

- Bookish headlines sell futuristic tools: new-kansas at 64px/1.2, weight 500 and -0.01em tracking leads; 48px/1.2 section titles retain the same rounded, slightly eccentric serif character.
- The first screen is a night-sky product theatre: centered cream headline and two compact actions sit above a floating white interface, with a plum #190922 world behind them and warm light along the lower horizon.
- Actions are small padded rectangles, not capsules: the default light button is 38px tall with 12px corners, 16px bold Nunito Sans and an 8px icon gap; dark buttons carry conversion on cream sections.
- Color is scenery rather than navigation: most reading happens on #f8f7f2 with #1d1d1c text; saturated pink, violet, blue, cyan, orange and yellow appear as diffuse proof-card light or immersive illustrated bands.
- Product proof floats rather than fills a browser: layer white 10–16px rounded cards, small charts and one dominant task surface, with soft shadows and pale lower-edge fades. If a product has no finished interface, construct a focused task-and-result vignette instead.
- Human warmth must bookend the technical story: use a softly lit imaginary landscape in the opening and a full-width illustrated closing world. A simple original rounded object in an atmospheric landscape is the minimum equivalent; retain the large scenic ending rather than reducing it to a utility footer.
- Proof gets a pastel stage: 480px square quote cards with 24px gaps, serif quotes and bottom-pinned attribution, or broad two-column outcome panels; diffuse 100px-blurred color pools replace hard brand-color blocks.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Plum night | `#190922` | `--color-night` | background | Immersive opening backdrop beneath cinematic media. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Petal light | `#f788d2` | `--color-pink` | accent | Source hue for diffuse pink light; 0.7 opacity shapes inside a 0.55-opacity ivory layer produce pastel proof surfaces. |
| Violet light | `#b26bf5` | `--color-violet` | accent, background | Diffuse purple light and saturated utility-demo backdrops. |
| Sky blue | `#51b1fb` | `--color-blue` | accent, background | Blue proof-card light and creator-tool demonstration backdrops. |
| Aqua light | `#4ad5e8` | `--color-cyan` | accent | Cool light pools paired with pink or blue. |
| Apricot | `#ff9147` | `--color-orange` | accent, background | Warm proof-card lighting; solid gradient endpoint in creator conversion bands. |
| Sunlight | `#ffe747` | `--color-yellow` | accent | Soft yellow glow in warm proof cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Milk white | `#ffffff` | `--color-white` | surface, text, action | Interface cards and light actions; translucent white layers make glass. |
| Porcelain | `#fdfdfa` | `--color-page` | background, surface | Raised pale panels and outer page backing. |
| Ivory backing | `#fcfcf7` | `--color-media-base` | surface | Base under colored media and proof-card washes. |
| Warm foundation | `#f8f7f2` | `--color-foundation` | background | Dominant reading canvas. |
| Oat | `#f5f3ea` | `--color-brand-surface` | background | Hero surrounds and warm feature bands. |
| Cream lettering | `#f2f1ec` | `--color-inverse` | text, border | Headlines over dark imagery and subtle light-page row dividers. |
| Warm hairline | `#edeae4` | `--color-edge` | border | Card outlines and fine interface separators. |
| Stone edge | `#d8d6ce` | `--color-edge-strong` | border, text | Button rings, stronger rules and muted lettering on dark scenes. |
| Stone text | `#99978f` | `--color-muted` | text | Secondary labels and low-priority supporting text. |
| Olive charcoal | `#43423e` | `--color-secondary` | text, action, border | Supporting text and dark action edges. |
| Warm ink | `#1d1d1c` | `--color-ink` | text, background | Default text and dark interface anchors. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| creator-oriented and pricing pages | Creator charcoal | `#191a1a` | `--color-creator-ink` | text, background | Text and dark button endpoint. |
| creator-oriented and pricing pages | Footer slate | `#3b3d3d` | `--color-slate` | background | Upper stop of the dark utility footer and its buttons. |
| creator-oriented and pricing pages | Peach top light | `#ffa466` | `--color-peach` | background | Upper gradient stop on orange conversion panels. |
| pricing pages | Plan highlight | `#ffa366` | `--color-plan-edge` | border | Orange outline around the featured plan. |
| creator-oriented feature grids | Sky top light | `#69bcfc` | `--color-sky-top` | background | Upper gradient stop in blue feature illustrations. |
| creator-oriented feature grids | Lilac top light | `#c287f7` | `--color-violet-top` | background | Upper gradient stop in violet feature illustrations. |

## Typography

- **new-kansas** — Headlines, feature headings and editorial quotes. Rounded, soft old-style display serif with friendly irregular details and broad lowercase forms. OpenType features: "calt", "kern", "liga". If unavailable, use **Fraunces**. Use 400–500, low optical size and restrained softness; preserve the broad serif silhouette. Font stack: "new-kansas", "Fraunces", Georgia, serif.
- **Nunito Sans** — Supporting copy, navigation, buttons, labels and product demonstrations. Humanist rounded sans with open counters; practical at small sizes and warm rather than austere. OpenType features: "kern", "liga". Font stack: "Nunito Sans", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | new-kansas | 500 | 64px | 1.2 | -0.01em | fixed | Default cinematic opening and illustrated chapter headlines. |
| heading | new-kansas | 500 | 48px | 1.2 | -0.013em | fixed | Section leads, proof, closing calls and FAQ introductions. |
| feature-heading | new-kansas | 500 | 28px | 1.2 | -0.023em | fixed | Focused product-demonstration chapters. |
| quote | new-kansas | 400 | 20px | 1.45 | normal | fixed | Editorial customer quotes in pastel square cards. |
| body | Nunito Sans | 400 | 18px | 28px | normal | fixed | Default support copy beneath feature headings and closing calls. |
| body-small | Nunito Sans | 400 | 16px | 1.5 | normal | fixed | Card descriptions and secondary explanatory paragraphs. |
| action | Nunito Sans | 700 | 16px | 1.5 | normal | fixed | Default light and dark buttons. |
| faq-label | new-kansas | 500 | 16px | 1.5 | normal | fixed | Question text inside default accordion rows. |
| caption | Nunito Sans | 400 | 14px | 1.625 | normal | fixed | Small supporting footer paragraph. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | new-kansas | 500 | 64px | 1.125 | -0.0178em | fixed | Left-aligned promise beside the featured plan. |
| creator-oriented pages | creator-display | new-kansas | 500 | 64px | 1.15 | -0.0178em | fixed | Centered opening headline amid peripheral product fragments. |
| managed-service landing pages | campaign-heading | new-kansas | 500 | 48px | 1.1 | -0.01em | size clamp(1.875rem, 3.6vw, 3rem) | Compact centered introduction after the cinematic hero. |
| creator-oriented and pricing pages | creator-heading | new-kansas | 500 | 48px | 1.15 | -0.0125em | fixed | Major light-page section and FAQ headings. |
| creator-oriented and pricing pages | footer-call | new-kansas | 500 | 40px | 1.15 | -0.015em | fixed | Orange conversion-box headline. |
| pricing pages | price | new-kansas | 400 | 40px | 1.2 | normal | fixed | Simple large price without a heavy sans treatment. |
| expanded outcome panels | case-heading | new-kansas | 500 | 34px | 1.15 | -0.023em | size clamp(1.75rem, 2.4vw, 2.125rem) | Outcome-led title in a wide proof panel. |
| creator-oriented feature grids | creator-feature | new-kansas | 500 | 24px | 1.15 | -0.025em | fixed | Bento-card benefit titles. |
| creator-oriented feature grids | creator-body | Nunito Sans | 400 | 18px | 1.4 | normal | fixed | Bento-card explanations. |
| new service announcements | announcement | Nunito Sans | 600 | 12px | 16px | 0.18em, uppercase | fixed | Small glass eyebrow above the cinematic promise. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use the serif for functional benefit headlines as well as emotional promises; reserve the sans for explanation and controls.
- The default 64px headline is lighter in texture than a bold grotesk. Keep the 500 weight and sentence case.
- Default section heads are 48px; internal capability titles step down to 28px. Creator-oriented cards use the tighter 24px variant rather than mixing both treatments in one grid.

## Layout

**Density:** Airy editorial sections around compact, layered product proof. Large scenic pauses contrast with dense but pale task surfaces.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label and paired-action gaps. |
| 12px | Card shells and tight text stacks. |
| 16px | Control padding, navigation link spacing and compact content gaps. |
| 24px | Card-grid gutters, quote-card padding and feature-stack gaps. |
| 32px | Wide proof-panel interiors and orange conversion-card padding. |
| 48px | Section heading to content and inset chapter-panel padding. |
| 64px | Illustrated chapter text inset and split-FAQ gutter. |
| 80px | Bottom padding of focused product chapters and footer text top inset. |
| 96px | Vertical padding around story grids and creator feature bands. |
| 128px | Default FAQ section top and bottom padding. |

### Containers and grids

- **content-container**: max width 1280px · side padding 48px. Centered default section container; at 1440px, an 80px outer margin surrounds it and the inner content spans 1184px.
- **hero-copy**: max width 1080px · side padding 16px. Centered cinematic headline group; support paragraphs narrow to about 702px.
- **navigation-rail**: max width 1320px. Two detached navigation islands aligned to opposing edges, fixed 20px from the top.
- **story-grid**: 3 columns · gap 24px. Three equal-width story cards.
- **capability-pair**: 2 columns · gap 48px. Paired benefit headings over interface vignettes in an inset chapter panel.
- **faq-split**: 2 columns · gap 64px. Narrow 1fr introduction beside 1.5fr accordion.
- **creator-bento** (only for creator-oriented feature grids): 2 columns · gap 24px. White cards in alternating unequal-width pairs; the first feature row uses 1.25fr beside 1fr.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-card-shells | 12px |
|  | quote-and-media-cards | 10px |
|  | wide-proof-shell | 16px |
|  | glass-prompt-halo | 24px |
| creator-oriented and pricing pages | creator-actions | 8px |
| new service announcements | announcement-chip | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | paper-card | `0px 0px 0px 1px #edeae4, 0px 1px 1px -0.5px rgba(29,29,28,0.04), 0px 3px 3px -1.5px rgba(29,29,28,0.04), 0px 6px 6px -3px rgba(29,29,28,0.04), 0px 12px 12px -6px rgba(29,29,28,0.02)` | Fine edge and dissipating elevation on white cards. |
| pricing pages | plan-halo | `0px 0px 0px 4px rgba(255,154,87,0.2), 0px 2px 1px -1px rgba(25,26,26,0.1), 0px 2px 4px rgba(25,26,26,0.06)` | Featured pricing card. |

### Surfaces

#### Reading canvas · level 0

**Use:** Dominant light background.

**CSS:** `background: #f8f7f2; color: #1d1d1c`

**Observed:** Warm rather than pure white, continuous across most editorial sections.

**Transfer:** Keep the practical story on this canvas between scenic interruptions.

#### Paper panel · level 1

**Use:** White cards and raised functional groups.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: 0px 0px 0px 1px #edeae4, 0px 1px 1px -0.5px rgba(29,29,28,0.04), 0px 3px 3px -1.5px rgba(29,29,28,0.04), 0px 6px 6px -3px rgba(29,29,28,0.04), 0px 12px 12px -6px rgba(29,29,28,0.02)`

**Observed:** Edges remain very faint; the large scenes provide the drama rather than heavy borders.

**Transfer:** Use for task cards, story links and accordion shells.

#### Pastel light field · level 1

**Use:** Backing for testimonials, case outcomes and story thumbnails.

**CSS:** `background: #fcfcf7; overflow: hidden; position: relative; border-radius: 10px`

**Observed:** Colored circular pools soften into an ivory center, leaving black text readable.

**Transfer:** Layer the diffuse-light recipe below inside a clipped pale backing.

#### Night stage · level 0

**Use:** Cinematic opening.

**CSS:** `background: #190922; color: #f2f1ec; overflow: hidden`

**Observed:** Deep plum and navy scenery with pink cloud edges, tiny stars and warm horizon light.

**Transfer:** Supply an original landscape with a calm dark region behind the headline.

#### Inset chapter · level 1

**Use:** Focused product walkthroughs inside a scenic frame.

**CSS:** `background: #f8f7f2; border-radius: 12px; padding: 48px`

**Observed:** A 1216px pale panel overlaps the lower part of a 1280px illustrated chapter; blurred color survives around its sides.

**Transfer:** Let the demonstration read as paper laid over a storybook scene.

#### Blue demo backing · level 1

**Only for:** creator-oriented feature grids

**Use:** Feature media stage.

**CSS:** `background: linear-gradient(#69bcfc 0%, #51b1fb 100%); border-radius: 6px`

**Observed:** Miniature white interfaces float at the center; wide image areas precede the card text.

**Transfer:** Group acquisition or discovery benefits on blue.

#### Violet demo backing · level 1

**Only for:** creator-oriented feature grids

**Use:** Operational feature media stage.

**CSS:** `background: linear-gradient(#c287f7 0%, #b26bf5 100%); border-radius: 6px`

**Observed:** Calendar, forms and messaging surfaces sit on flat luminous purple.

**Transfer:** Use one consistent hue for a whole capability family.

#### Orange conversion panel · level 1

**Only for:** creator-oriented and pricing pages

**Use:** Utility-footer conversion box.

**CSS:** `background: linear-gradient(#ffa466 0%, #ff9147 100%); border-radius: 8px; padding: 32px; color: #191a1a`

**Observed:** A warm block against a dark footer, with headline, two checked benefits and a low-positioned dark action.

**Transfer:** Make this the concentrated color payoff of the utilitarian page variant.

#### Utility footer · level 0

**Only for:** creator-oriented and pricing pages

**Use:** Compact dark page ending.

**CSS:** `background: linear-gradient(#3b3d3d 0%, #191a1a 100%); padding: 64px 0px 56px`

**Observed:** Logo and two link columns left; Orange conversion panel right; legal row below.

**Transfer:** Use for pricing and audience-specific utility pages rather than the scenic default ending.

## Components

### Navigation islands

**Use:** Persistent site navigation.

**CSS:** `display: flex; align-items: center; gap: 8px; border-radius: 12px; padding: 5px 6px 5px 5px; box-shadow: 0px 2px 8px rgba(0,0,0,0.1)`

**Observed:** Logo plus audience menus form the left island; careers, login and a small access action form the right. The islands are dark translucent glass on the cinematic opening and milky white over reading sections.

**Transfer:** Keep the open center; adapt the menus to the product's audiences instead of building a full-width header bar.

### Light button

**Use:** Primary action on dark scenery, secondary action on cream.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #ffffff; color: #1d1d1c; border: 1px solid transparent; border-radius: 12px; padding: 10px 16px; height: 38px; box-sizing: border-box`

**Text style:** `action` — Nunito Sans 700 · 16px/1.5

**Observed:** Usually paired with a glass trailer action on the opening; labels remain short and centered.

**States:** Declared: hover background #f9f8f5; focus-visible transparent border and a #d8d6ce shadow ring.

### Glass button

**Use:** Secondary media action on dark scenes.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; background: rgba(255,255,255,0.08); color: #f2f1ec; border-radius: 12px; padding: 10px 14px; height: 38px; box-sizing: border-box; backdrop-filter: blur(12px); box-shadow: 0px 0px 0px 1px rgba(255,255,255,0.2), 0px 1px 1px rgba(255,255,255,0.06) inset, 0px 2px 6px rgba(0,0,0,0.12)`

**Text style:** `action` — Nunito Sans 700 · 16px/1.5

**Observed:** Label precedes a small outlined play triangle.

**States:** Declared: hover white at 12% opacity with white text; focus-visible white 20% ring and no outline; active scale 0.985 and white at 20% opacity.

### Dark button

**Use:** Primary conversion on light sections.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; background: #43423e; color: #f2f1ec; border: 1px solid #43423e; border-radius: 12px; padding: 10px 16px; height: 38px; box-sizing: border-box`

**Text style:** `action` — Nunito Sans 700 · 16px/1.5

**Observed:** Subtle vertical tonal gradient gives a gently convex charcoal finish; wider than the paired consultation action.

**States:** Declared: hover text #ffffff; focus-visible transparent border; active scale 0.985.

### Quote card

**Use:** Horizontal customer-proof carousel.

**CSS:** `position: relative; background: #ffffff; border-radius: 10px; width: 480px; height: 480px; overflow: hidden`

**Text style:** `quote` — new-kansas 400 · 20px/1.45

**Observed:** Pastel light field behind a logo, roomy serif quote, and bottom-pinned portrait, bold name and sans role. Inner content has 24px padding. Neighboring cards clip at the viewport edges; small square arrow controls sit below.

**Transfer:** Use an authentic quote or an outcome narrative, keeping the low attribution anchor.

### Story card

**Use:** Three-column related stories.

**CSS:** `display: flex; flex-direction: column; gap: 16px; background: #ffffff; border-radius: 12px; padding: 12px; overflow: hidden`

**Text style:** `body-small` — Nunito Sans 400 · 16px/1.5

**Observed:** A 200px-high pastel logo thumbnail precedes a 20px serif title and a short sans summary. Cards are about 379px wide in the desktop grid.

**Transfer:** Use a centered symbol or original customer mark on diffuse color rather than a generic photograph.

### FAQ trigger

**Use:** Default FAQ accordion.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 16px; width: 100%; text-align: left; color: #1d1d1c`

**Text style:** `faq-label` — new-kansas 500 · 16px/1.5

**Observed:** A 56px trigger sits in a pale raised shell; 1px cream separators divide rows and a muted plus sits at the far edge. Creator-oriented pages instead use two columns of freestanding serif questions with small dark circular chevrons.

### Outcome panel

**Only for:** expanded outcome panels

**Use:** Detailed customer proof.

**CSS:** `background: #fdfdfa; border-radius: 16px; padding: 6px`

**Text style:** `case-heading` — new-kansas 500 · 34px/1.15 · tracking -0.023em

**Observed:** An inset 1172×640px Pastel light field with 32px padding divides into narrative and a 380px social-post artifact, separated by 96px. Logo, outcome title, brief paragraph and large serif numbers sit left. Tiny uppercase sans captions label the numbers. Panels stack with previous colored edges showing above.

**Transfer:** Place verified outcomes beside a relevant artifact such as a report, review or delivered result.

### Featured plan

**Only for:** pricing pages

**Use:** One prominent, simple plan.

**CSS:** `background: #ffffff; border: 2px solid #ffa366; border-radius: 12px; width: 464px; box-shadow: 0px 0px 0px 4px rgba(255,154,87,0.2), 0px 2px 1px -1px rgba(25,26,26,0.1), 0px 2px 4px rgba(25,26,26,0.06)`

**Text style:** `price` — new-kansas 400 · 40px/1.2

**Observed:** Orange uppercase ribbon above plan name, price and qualifier. A thin rule separates checked benefit rows; each benefit may have a muted replacement-tool chip underneath. A full-width dark action anchors the bottom.

**Transfer:** Keep the economic model understandable in one card instead of inventing a three-tier comparison.

### Creator feature card

**Only for:** creator-oriented feature grids

**Use:** Bento capabilities.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 16px; background: #ffffff; border-radius: 12px`

**Text style:** `creator-feature` — new-kansas 500 · 24px/1.15 · tracking -0.025em

**Observed:** Blue demo backing or Violet demo backing occupies most of the upper card. Beneath it are a gray uppercase 14px category label, serif benefit title and 18px support paragraph.

**Transfer:** Make each miniature interface show one action or result; retain the shared color across a capability group.

## Imagery and graphics

### Cinematic dreamworld

**Use:** Opening scene, scenic chapter transitions and the illustrated closing world.

**Observed:** Soft 3D animation aesthetic: a rounded purple character with glossy eyes and leaves stands in starry violet landscapes, peach-lit clouds and rolling vegetation. The closing scene becomes a pink-blossomed park with a warm wooden bench and hazy city skyline. These are large environments, not small stickers.

**Transfer:** Create an original approachable object or character in a product-relevant imaginary world. Preserve soft rounded volumes, cinematic depth, warm rim light and quiet space for typography. If no character is appropriate, use a rounded tool-like object as the focal point.

**Build:** Minimum scene: an SVG or rendered landscape with three overlapping curved hill silhouettes, blurred peach and pink cloud masses near the horizon, a deep plum upper sky and tiny low-opacity cream stars. Put an original rounded object low to one side, lit with peach rim gradients. For the ending, frame a lighter horizon with two tall organic silhouettes and a central resting object; retain the warm pink canopy and depth layers.

### Diffuse proof lighting

**Use:** Quote cards, customer-story media and broad outcome panels.

**Observed:** Blue-cyan-pink, pink-violet, or peach-yellow pools blend into ivory, with no crisp gradient seams. Cards remain light enough for ink serif text.

**Transfer:** Keep different proof items in related two- or three-hue families; leave at least one quiet ivory area.

**Build:** Inside a clipped #fcfcf7 panel, absolutely position 240–384px rounded color shapes near opposing corners. Apply blur(100px) and opacity 0.7 to shapes; for quote cards wrap the whole color layer at opacity 0.55. Pair #f788d2 with #b26bf5, #51b1fb with #4ad5e8, or #ff9147 with #ffe747. Scale shapes up for wide proof panels.

### Floating product vignettes

**Use:** Opening task surface and capability demonstrations.

**Observed:** White UI pieces overlap like paper cards. The opening has three tilted mini-charts over a larger prompt panel and three small task chips below; a violet glow separates the prompt from the dark scene. Later vignettes fade into the cream canvas at the bottom.

**Transfer:** Design one dominant task surface around 640px wide with two or three smaller result cards. Use purposeful data rather than reproducing a whole application.

**Build:** Layer a 16px-radius white task panel below three small 12px-radius result cards, with restrained opposing rotations. Add a 24px-radius outer halo using rgba(168,85,247,0.3) at 15px blur and rgba(168,85,247,0.5) at 30px blur. Keep the task panel itself 95% white with an 8px backdrop blur. For light sections use a cream-to-transparent mask at the lower edge.

### Orbit proof diagram

**Use:** A relationship or network capability illustration.

**Observed:** Fine concentric arcs connect small portrait chips around a central product symbol and an orange speech bubble; paired serif multiplier stats sit above the arcs.

**Transfer:** Represent the new product's network of inputs or collaborators with a few authentic nodes rather than a dense technical graph.

**Build:** Draw four thin low-contrast semicircular SVG paths centered below the copy; space 40px rounded avatar tiles around the paths. Place a compact warm-orange message near the center and a dark rounded product tile beneath. Keep the diagram mostly cream negative space.

### Creator portrait mosaic

**Only for:** creator-community pages

**Use:** Human proof grid.

**Observed:** Black-and-white cutout portraits on bright cyan, green or orange squares alternate with cream logo tiles outlined in charcoal. Dark bottom gradients support white serif names; a small white circular plus sits near the lower corner. A violet quotation tile spans two columns.

**Transfer:** Use permissioned customer or community portraits; keep natural expressions, monochrome people and saturated flat backings.

### Community parade

**Only for:** creator-community conversion sections

**Use:** Warm closing conversion band before FAQs.

**Observed:** Cream transitions to orange below a centered serif promise and dark button. Two offset rows of small translucent profile cards extend beyond the viewport; a continuous brown line-art crowd rises across the bottom.

**Transfer:** Use original customer cards and a continuous hand-drawn visual metaphor for the product's community.

**Build:** Use a vertical gradient from #f5f3ea through #ffa466 to #ff9147. Place two horizontal card rails with 16px gaps and pale fading lower edges. Along the bottom, draw repeated irregular rounded bodies and waving arms in SVG with thick warm-brown strokes, varying rotation and height; make the silhouette overlap the lower rail.

### Icons

**Observed:** Small round-ended outline icons, usually 14–20px with 1.5–2px strokes, in warm gray or cream. Play triangles, arrows, pluses and platform marks are compact and secondary to copy.

**Transfer:** Choose a consistent rounded outline set. Use filled marks only for familiar platform logos or circular checked benefits.

## Section recipes

How recurring sections are built.

### First screen: Night-sky product theatre

**Observed:** A full-width Night stage begins behind two Navigation islands fixed 20px from the top. A centered two-line display headline occupies the upper third, starting after 112px top padding; cream lettering sits above a narrow two-line sans support statement. Light button and Glass button form an 8px-gap pair. Below, a Floating product vignette spans roughly the middle half of the screen: three mini-charts float above a large prompt and task chips. The purple character enters from the lower right while peach clouds fill the bottom edge. Within the first 900px the full promise, support, actions and principal task object are visible; the character's lower body, trust-logo band and subsequent editorial story lie below the fold.

**Transfer:** Use the same centered hierarchy over an original dark imaginary world and a task-result vignette. Without finished media, build the minimum Cinematic dreamworld and Floating product vignettes recipes. Pricing opens instead with a left promise beside Featured plan; audience-specific creator pages use a cream centered promise with peripheral UI fragments; a managed-service opening uses a 664px-high scenic panel inset 40px and a single action.

**Avoid:** Do not substitute a plain dark gradient with only text, or push the main product object entirely below the first screen. Do not let scenery compete with the cream headline.

**Text style:** `display` — new-kansas 500 · 64px/1.2 · tracking -0.01em

### Scenic chapter to paper demonstration

**Observed:** A 1280px-wide illustrated chapter carries 64px cream serif type with 64px top/left inset. An Inset chapter panel overlaps beneath it, leaving softly colored scenery visible around the edges. Centered 28px feature title and 18px support lead into a focused UI scene; paired benefits follow on the same paper stage.

**Transfer:** Use a scenic bridge to introduce a major capability family, then switch to legible cream-backed demonstrations. Chapter titles describe outcomes, not internal module names.

**Text style:** `feature-heading` — new-kansas 500 · 28px/1.2 · tracking -0.023em

### Focused heading pair

**Observed:** A centered serif lead and support paragraph use about 702px of width, with a visible gap near 14px. The demonstration follows with 24–48px separation. Paired features align text left and keep each paragraph above its illustration.

**Transfer:** Let a short benefit title set up one concrete mechanism; vary centered overview and left-aligned paired details.

### Network proof

**Observed:** Centered capability heading and two-line support precede paired serif multiplier stats and the Orbit proof diagram. Small sans comparison captions are subdued and sometimes italic.

**Transfer:** Show a trustworthy comparison with a short baseline caption; use the diagram to make the product's relationships tangible rather than decorative.

### Pastel testimonial rail

**Observed:** A centered 48px heading sits 48px above the Quote card rail. Cards have 24px gaps and adjacent cards clip at the viewport edges. Two small light square arrow actions sit centered below.

**Transfer:** Use a horizontally browsable set of customer narratives with different diffuse color families.

**Text style:** `heading` — new-kansas 500 · 48px/1.2 · tracking -0.013em

### Quiet conversion clearing

**Observed:** A centered two-line 48px serif statement on cream contrasts an old behavior with a better one. An 18px support line and Dark button plus Light button sit below. Very diffuse violet and orange light and small floating profile chips surround the copy without creating a filled band.

**Transfer:** State the shift in the reader's working life; retain an uncluttered clearing within the longer visual story.

**Text style:** `heading` — new-kansas 500 · 48px/1.2 · tracking -0.013em

### Story grid

**Observed:** A centered section heading precedes three Story cards with 24px gaps; the section has 96px vertical padding.

**Transfer:** Use concise outcome-led editorial proof rather than a generic wall of logos.

### Default objections

**Observed:** 128px vertical padding around FAQ-split: 48px serif heading and small contact prompt left, a single pale rounded accordion shell right. Rows are 56px plus fine separators.

**Transfer:** Group common objections into a calm, compact block; keep contact assistance near the heading.

**Text style:** `heading` — new-kansas 500 · 48px/1.2 · tracking -0.013em

### Scenic footer descent

**Observed:** The page ends in a 1200px-tall full-width illustrated world with 12px upper corners. White brand mark, small supporting copy, social icons and three navigation columns occupy the upper part over a dark-to-transparent 500px overlay. The scene continues far below the links to reveal the central character resting on a bench beneath pink trees.

**Transfer:** End a default marketing page with a scenic resolution, not just link columns. Place navigation in the dark upper atmosphere and let a large original world remain beneath it; use the minimum landscape recipe when bespoke 3D is unavailable.

### Numbered service chapters

**Only for:** managed-service landing pages

**Observed:** Large sticky panels with 28px rounded upper corners and faint top/side outlines accumulate slim numbered headers above the active panel. Small coral uppercase number/category labels lead a left-aligned 48px serif benefit with short 16px support; the right half shows a faded task vignette. Low-opacity multicolor washes connect both halves.

**Transfer:** Use for a sequential process. Keep the sticky stack comprehensible with a visible active chapter; pair each step with a distinct result.

### Expanded outcome stack

**Only for:** managed-service and proof-heavy pages

**Observed:** A left-aligned 48px section lead introduces Outcome panels. Narrative and serif statistics sit left and a white social-post artifact sits right; previous pastel panel edges remain visible as the stack advances.

**Transfer:** Use a short series of verified outcomes with their artifacts; the panel is a case narrative rather than a dashboard.

### Artifact marquee call

**Only for:** managed-service landing pages

**Observed:** A centered 48px call, 18px support and dark action are surrounded above and below by offset rows of small social-content cards, tilted and extending past the screen with pale edge fades.

**Transfer:** Use real output artifacts to show reach or multiplicity, keeping the central call clear.

### Pricing promise and plan

**Only for:** pricing pages

**Observed:** A 680px left text block with a two-line 64px serif promise, 20px support and a small company-mark cluster faces a 464px-wide Featured plan. The cream gradient hero has about 160px top space before its content. A colorful 208×261px profile-card rail follows, then two columns of freestanding FAQ questions and Utility footer.

**Transfer:** Make the price model visually immediate; use the plan's benefit checks and replacement chips to explain value without a dense comparison table.

**Text style:** `pricing-display` — new-kansas 500 · 64px/1.125 · tracking -0.0178em

### Creator benefit bento

**Only for:** creator-oriented pages

**Observed:** A cream opening centers the 64px promise and dark 47px-high action amid cropped peripheral UI panels. Subsequent sections use blue-backed acquisition cards, a centered payout proof call, then violet-backed operations cards. Major section titles are 48px and card titles 24px.

**Transfer:** Separate getting value from managing work into visibly different color families. Show one task per card.

**Text style:** `creator-display` — new-kansas 500 · 64px/1.15 · tracking -0.0178em

### Creator community and utility ending

**Only for:** creator-oriented pages

**Observed:** Creator portrait mosaic follows a centered heading and support line. Community parade then provides a warm conversion climax. A two-column freestanding FAQ precedes Utility footer with Orange conversion panel. Pricing uses the same footer without the parade.

**Transfer:** Use the community-rich variant when people are central to the product; keep the more compact pricing ending for economic decisions.

**Text style:** `creator-heading` — new-kansas 500 · 48px/1.15 · tracking -0.0125em

## Page flow

**Storyline:** promise → tangible task proof → capability families → human and quantified proof → renewed action → objections → emotionally resolved ending

### Flagship product landing page

1. **Promise** — Night-sky product theatre with floating task and result cards.
2. **Problem recognition** — Large serif first-person quote becomes an editorial transition.
3. **Capability chapters** — Illustrated bridges lead to pale demonstrations, paired benefits, platform proof and a network comparison.
4. **Social proof** — Pastel testimonial rail followed by a spacious conversion clearing.
5. **Customer outcomes** — Three concise story cards.
6. **Objection handling** — Split FAQ with contact help.
7. **Emotional resolution** — Scenic footer descent from navigation into a complete illustrated world.

**Transfer:** Adapt the number and placement of capability chapters to the product; preserve the contrast between cinematic promise and practical paper proof.

### Managed-service campaign landing page

1. **Promise** — Inset night landscape with announcement chip, one main action and a quiet secondary access link.
2. **Social proof** — Trusted marks and a slim horizontal result ticker.
3. **Process** — Centered introduction then numbered sticky service chapters.
4. **Quantified proof** — Stacked wide outcome panels pair editorial claims with social artifacts.
5. **Closing call** — Centered action amid offset rows of output cards.
6. **Objection handling** — Compact split FAQ.
7. **Emotional resolution** — Scenic footer descent.

**Transfer:** Use process chapters and outcome artifacts to explain a service rather than duplicating the flagship's longer walkthrough.

### Simple pricing decision page

1. **Economic promise** — Two-column opening with a large serif value promise and one emphasized plan.
2. **Social proof** — Colorful profile-card rail.
3. **Objection handling** — Two columns of serif questions with circular chevrons.
4. **Closing call** — Dark utility footer with orange conversion box.

**Transfer:** Lead with a comprehensible economic proposition and keep supporting material short.

### Audience-specific product landing page

1. **Promise** — Centered cream hero framed by peripheral product fragments.
2. **Capability overview** — Compact benefit mosaic with miniature task illustrations.
3. **Capability families** — Blue feature bento, centered proof call, then violet operations bento.
4. **Human proof** — Portrait-and-logo mosaic with spanning quote card.
5. **Closing call** — Orange community parade with two rails of customer cards.
6. **Objection handling** — Two-column FAQ.
7. **Final action** — Utility footer with warm conversion panel.

**Transfer:** Use the lighter utility-led variant for a specific audience while keeping the serif voice and human proof.

## Writing

Optimistic and direct, combining ambitious positioning with everyday relief from tedious work. Technical mechanisms are explained through outcomes, while customer voices add warmth and credibility.

**Do not copy:** Do not reuse Passionfroot or Zest names, wordmarks, mascot, customer logos, proprietary artwork, testimonials, payout totals, growth multiples, network size, prices or other brand-specific claims. Replace them with original assets and substantiated product facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. The product acts as a helpful operator; service pages use we for the work being done on the reader's behalf.
- **Rhythm:** Headlines usually form one compact thought over one or two lines. Support copy is one or two clear sentences; contrasts and em dashes make the promise memorable. Actions are short verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a new category or a strongly felt outcome. | 6–12 words | “The Agentic Marketing OS for the AI era”<br>“Make your biggest moments impossible to miss.” |
| Capability title | Verb plus concrete result, often removing a familiar frustration. | 6–11 words | “Run campaigns at scale, not in spreadsheets.”<br>“Win sponsors with your verified media kit” |
| Support | Explain what happens, then name what no longer requires work. | 15–35 words | “See reach, engagement, spend, and ROI for every creator and post from your campaigns or external sources. Automatically synced, no spreadsheets.” |
| Action | Short starting verb; qualify access or ownership when useful. | 3–5 words | “Start for free”<br>“Amplify my launch →” |
| Proof headline | State a specific change with a verifiable outcome. | 7–12 words | “From zero creator presence to 31M impressions.” |
| Closing call | Restate the reader's future, not a generic contact request. | 5–10 words | “Let’s grow your creator business” |

**Words and phrasing to use:** in minutes — not weeks; without the manual work; at scale; one source of truth; finally simple; keep moving; what actually works

**Avoid:** revolutionary synergy; enterprise-grade ecosystem as filler; excessive AI jargon; unqualified superlatives; aggressive urgency or countdown language

**Rules:**

- Name the old friction before claiming relief.
- Use a concrete mechanism in each supporting paragraph rather than repeating the headline.
- Let customer outcomes carry numbers; keep benefit headings human-readable.
- Use specific verbs such as plan, discover, run, track and grow rather than generic learn more language.

## Do's and Don'ts

### Do

- Keep default cinematic headlines at 64px, weight 500 and -0.01em tracking.
- Make the dominant reading surface warm #f8f7f2, with white reserved for raised functional groups.
- Keep paired actions compact at 38px with an 8px gap.
- Use 24px gutters between proof or story cards.
- Retain 100px-blurred color pools and a pale center in proof graphics.
- Pin quote attribution near the lower edge of 480px cards.
- Give default FAQs 128px vertical padding and a 64px split gutter.
- Carry the illustrated ending substantially below its navigation content.

### Don't

- Do not turn all serif headings into a bold geometric sans; that loses the friendly editorial character.
- Do not make every action a 9999px capsule; default actions have 12px corners.
- Do not spread saturated purple across the reading canvas; put it in scenes, light fields or scoped demo media.
- Do not use heavy gray drop shadows on paper panels; their outlines are fine and elevation dissipates softly.
- Do not present miniature demos as dense full-screen dashboards; isolate a task and a few results.
- Do not mix blue acquisition and violet operations media indiscriminately within the creator variant.
- Do not replace serif outcome numerals with oversized monospaced data art.
- Do not collapse the default scenic ending into the compact orange utility footer; those are different page variants.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions use 0.2s cubic-bezier(.4,0,.2,1); navigation islands use 0.3s with the same curve.
- Declared glass and dark actions scale to 0.985 when active.
- Word-reveal, blur-up, scale and floating-card animations are present; service outcome panels and chapter headers use sticky stacking.
- The result ticker declares a 135s linear infinite animation; message arrivals declare 0.5s cubic-bezier(.34,1.56,.64,1).

**Transfer:**

- Reveal headlines and proof pieces as separate layers, retaining a readable settled composition.
- Use slow rails for breadth of proof and sticky layers for process or outcome narratives, not for every section.

**Unknown:**

- Exact timing of scenic video loops and most scroll-linked entrances is unspecified.

### Responsive

**Observed:**

- Declared layout changes include 640px, 768px, 1024px and 1280px thresholds among a wider breakpoint set.
- Layout classes switch centered chapter copy to left alignment on narrow screens; paired opening actions become a column.
- Quote-card width changes from 480px desktop to 320px on narrow layouts; height changes from 480px to 500px.

**Transfer:**

- Stack paired capabilities and FAQ columns, preserving the benefit-before-demo order.
- Retain the scene's focal object and quiet copy area when trimming landscape width; keep the floating product task legible instead of shrinking the entire desktop collage.
- Keep the two-island idea at wide widths; consolidate navigation for narrow screens.

**Unknown:**

- Exact mobile navigation behavior, scenic object positions and all mobile spacing were not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
