# Umbrel — domestic computing cinema

## Overview

Consumer technology made tactile, personal and at home, with cinematic product scenes rather than enterprise abstractions. Mostly black compositions alternate with clean off-white demonstrations, while electric violet anchors the actions and a surprisingly expansive closing field. Rounded geometric sans headings, restrained interface-like body text and occasional handwritten emphasis soften the technical subject. Large photography, luminous software windows and carefully lit object renders carry the story at a low editorial density.

### Essentials

- A human word interrupts the technology headline: 61px medium geometric sans with -0.024em tracking, punctuated by 72px semibold script for one meaningful word.
- The opening is a domestic cinema, not a dashboard masthead: centered promise above a 1264×630px rounded scene, with a second, smaller argument embedded at its lower left and the product visibly in use.
- Small pills sit beneath oversized promises: 13.3px medium labels, 10px 20px padding, fully rounded ends; violet primary and translucent white secondary, not oversized rectangular sales buttons.
- Black owns most of the story; off-white provides a deliberate demonstration chapter. Saturated #5351f3 is concentrated in small actions and one full-width, approximately 900px-tall closing field rather than spread through every section.
- Proof has depth and warmth: 24px or 32px corners, dark edge gradients, luminous media and soft ambient halos. Include a lit product-in-context scene and a floating interface stage; when no physical product exists, show the interface on a real device in a lived-in setting.
- The ending changes the room: a violet reveal footer pairs a small white identity mark with a 39.1px two-line belief statement, then a deep pause before newsletter and link columns. Retain this saturated closing device on every page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#5351f3` | `--color-violet` | action, background, accent | Primary pills, selection tint and the closing footer. |
| Pressed violet | `#4543df` | `--color-violet-hover` | action | Primary action hover fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cinema black | `#000000` | `--color-canvas` | background | Default marketing canvas and dark image fades. |
| Near-black ink | `#09090b` | `--color-ink` | text | Main text on light chapters and inverse buttons. |
| Midnight panel | `#0b0a12` | `--color-panel` | surface | Media panels and announcement banners. |
| Dark hairline | `#1a1a1a` | `--color-dark-edge` | border, surface | Visible white at 10% over black; use the alpha recipe over changing media. |
| Glass edge | `#333333` | `--color-strong-edge` | border | Visible white at 20% over black on translucent action edges. |
| Slate body | `#52525b` | `--color-muted-ink` | text | Supporting copy on light chapters. |
| Slate label | `#71717a` | `--color-label-ink` | text | Eyebrows on light chapters. |
| Dim white | `#808080` | `--color-subtle` | text | Visible white at 50% over black for restrained labels and secondary notes. |
| Silver secondary | `#a1a1aa` | `--color-dark-muted` | text | Card descriptions on dark backgrounds. |
| Smoke white | `#cccccc` | `--color-support` | text | Visible white at 80% over black for supporting paragraphs. |
| Pale edge | `#e4e4e7` | `--color-light-rule` | border, text | Light-theme outlines and navigation text. |
| Cool pale panel | `#f4f4f5` | `--color-light-panel` | surface | Light media staging and the bottom of off-white gradients. |
| Off-white chapter | `#fafafa` | `--color-light` | background | Contrasting demonstration chapters. |
| Bright white | `#ffffff` | `--color-white` | text, surface | Main text on black and inverse action fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| hardware product heroes | Warm ivory | `#f7e3c3` | `--color-warm-line` | text | One contrasting line in the full-bleed hardware promise. |

## Typography

- **googleSans** — Headings and larger media captions. Friendly geometric sans with open circular forms and rounded, unaggressive medium-weight silhouettes. If unavailable, use **Google Sans**. Use weights 400–600 with the negative tracking preserved. Font stack: "googleSans", "Google Sans", Inter, ui-sans-serif, system-ui, sans-serif.
- **inter** — Body copy, navigation, actions, metadata and the footer belief statement. Compact neutral sans that gives the marketing page the familiarity of well-made software. Font stack: "inter", Inter, ui-sans-serif, system-ui, sans-serif.
- **dancingScript** — Single-word emphasis in the opening headline. Connected, buoyant handwritten lettering, slightly larger than the surrounding sans. If unavailable, use **Dancing Script**. Font stack: "dancingScript", "Dancing Script", cursive.
- **playfair** — Brief italic emphasis within a manifesto sentence. High-contrast editorial italic used as a momentary tonal change. If unavailable, use **Playfair Display**. Font stack: "playfair", "Playfair Display", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display-script | dancingScript | 600 | 72px | 1 | -0.0203em | One integrated word within the display. |
| display | googleSans | 500 | 61px | 1.04 | -0.024em | Centered opening promise. |
| heading | googleSans | 500 | 61px | 1.25 | -0.024em | Major chapter headings; typically one or two balanced lines. |
| heading-small | googleSans | 500 | 39.1px | 1.25 | -0.02em | Announcement headings and expanded feature rows. |
| manifesto | googleSans | 500 | 39.1px | 1.22 | -0.01em | Short rhetorical sentence or word-by-word narrative. |
| manifesto-italic | playfair | 500 italic | 39.1px | 1.22 | -0.01em | The final emphatic phrase inside a manifesto. |
| closing-belief | inter | 500 | 39.1px | 1.375 | -0.025em | The footer's large belief statement. |
| card-title | googleSans | 500 | 31.2px | 1.25 | -0.018em | Product option names. |
| scene-heading | googleSans | 500 | 31.2px | 1.375 | -0.018em | Argument embedded over the opening scene. |
| media-caption | googleSans | 400 | 31.2px | 1.375 | -0.018em | Top-left text over cinematic highlight media. |
| body-lead | inter | 400 | 20px | 1.4 | -0.014em | Chapter support text. |
| eyebrow | inter | 500 | 16px | 1.6 | -0.011em | Sentence-case category or release labels. |
| body | inter | 400 | 16px | 1.6 | -0.011em | Embedded scene description and short product descriptions. |
| card-body | inter | 400 | 16px | 1.5 | -0.011em | Option card descriptions. |
| quote | inter | 400 | 16px | 1.75 | -0.011em | Customer posts in the proof collage. |
| action | inter | 500 | 13.3px | 1.45 | -0.004em | Action labels and compact comparison text. |
| navigation | inter | 400 | 13.3px | 1.45 | -0.004em | Navigation and footer links; do not force an underline on every navigation item. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| culture and recruiting pages | culture-body | googleSans | 400 | 20px | 1.625 | -0.014em | Longer philosophy copy beside image accordions. |

**Notes:**

- The main sans headline and chapter heading share size and tracking but not leading: the opening is 1.04, chapters 1.25.
- Body and action typography stay much smaller than chapter headings. Medium rather than bold is the characteristic headline weight.
- Script is an inline change of voice, not a second headline stacked underneath. Keep sentence case throughout; uppercase is reserved for very small status badges.

## Layout

**Density:** Airy at chapter level and compact within controls; broad media carries more area than copy.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gap and compact action internals. |
| 12px | Sibling action gap and scene heading-to-description gap. |
| 16px | Eyebrow-to-heading separation and compact grid gaps. |
| 20px | Heading-to-support gap and option-card grid gutter. |
| 24px | Page container side padding and ordinary card insets. |
| 32px | Copy-to-action separation and proof-column gaps. |
| 40px | Headline-to-opening-media separation and highlight caption insets. |
| 48px | Opening-scene text insets and heading-to-card separation. |
| 56px | Section heading-to-carousel gap. |
| 80px | Proof heading-to-collage separation. |
| 112px | Default major-section vertical padding. |
| 144px | Opening top padding beneath fixed navigation. |

### Containers and grids

- **page container**: max width 1312px · side padding 24px. Centered outer container; at 1440px, its inner media width is 1264px.
- **heading block**: max width 768px · side padding 24px. Centered, balanced major heading groups; support copy narrows further to 576px or 672px.
- **option grid**: 3 columns · gap 20px. Equal-width 408px product-choice cards with aligned actions and specification rows.
- **proof collage**: max width 1152px · 3 columns · gap 32px · side padding 24px. Independent masonry-like columns of customer posts rather than equal-height rows.
- **comparison table** (only for hardware comparison sections): max width 1024px. Two product columns plus a slim left label column.
- **culture split** (only for culture and recruiting pages): max width 1152px · 2 columns · gap 48px. Wide visual accordion beside narrower text; alternate sides by chapter.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 9999px (pill) |
| cards and proof posts | 24px |
| cinematic media and banners | 32px |
| interface stage | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| dark glass | `inset 0px 1px 0px rgba(255,255,255,0.08), 0px 22px 70px rgba(0,0,0,0.3)` | Raised product cards and interface stages. |
| proof post | `0px 30px 90px rgba(0,0,0,0.55), inset 0px 1px 0px rgba(255,255,255,0.12)` | Floating dark customer posts. |
| light interface | `0px 34px 120px rgba(24,24,27,0.14)` | White framed interface art on off-white chapters. |

### Surfaces

#### Cinema canvas · level 0

**Use:** Default long-form marketing background.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Black sections merge through faded media edges rather than obvious horizontal boxes.

**Transfer:** Let each chapter emerge from the same darkness.

#### Light chapter · level 0

**Use:** A deliberate contrast chapter for a broad ecosystem or software demonstration.

**CSS:** `background: linear-gradient(#fafafa 0%, #fafafa 50%, #f4f4f5 100%); color: #09090b`

**Observed:** Whole chapter switches polarity, including labels, buttons and outlines.

**Transfer:** Use for a complete proof moment, not scattered white cards in every black section.

#### Midnight media · level 1

**Use:** Cinematic highlight cards and wide announcement banners.

**CSS:** `background: #0b0a12; border: 1px solid rgba(255,255,255,0.1); border-radius: 32px; overflow: hidden`

**Observed:** Imagery fills the panel; gradients protect the copy without a separate opaque text box.

**Transfer:** Keep one dominant image, one short heading and restrained controls.

#### Dark glass · level 1

**Use:** Product choices and translucent information panels.

**CSS:** `background: rgba(255,255,255,0.075); border: 1px solid rgba(255,255,255,0.16); border-radius: 24px; backdrop-filter: blur(24px); box-shadow: inset 0px 1px 0px rgba(255,255,255,0.08), 0px 22px 70px rgba(0,0,0,0.3)`

**Observed:** Black product imagery meets a subtly lighter information area.

**Transfer:** Use depth sparingly; the photograph or render remains the focal point.

#### Violet closing field · level 0

**Use:** Shared final footer.

**CSS:** `background: #5351f3; color: #ffffff; padding: 64px 24px`

**Observed:** A full-height violet plane revealed underneath the end of the dark page.

**Transfer:** Give this field enough height for a belief statement, a large pause, and useful navigation.

## Components

### Global navigation

**Use:** Thin persistent site identity and navigation.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 45px; z-index: 50; background: rgba(0,0,0,0.5); border-bottom: 1px solid rgba(255,255,255,0.1); backdrop-filter: blur(40px)`

**Text style:** `navigation` — inter 400 · 13.3px/1.45 · tracking -0.004em

**Observed:** Small identity mark left, centered link cluster, compact utility icons right. Product and culture pages add a 57px secondary bar with a page title and local anchors. Light chapters use a light-toned navigation variant.

**Transfer:** Keep the bar visually subordinate to the scene.

### Primary button

**Use:** The main product conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; padding: 10px 20px; border-radius: 9999px; background: #5351f3; color: #ffffff`

**Text style:** `action` — inter 500 · 13.3px/1.45 · tracking -0.004em

**Observed:** Width follows the label; small standalone or paired action. Larger section variants use 12px 24px padding.

**States:** Declared: hover scale 1.02 and background-color #4543df; focus-visible outline-style none and a zero box-shadow stack.

### Glass button

**Use:** Secondary exploration, media viewing and platform actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; padding: 10px 20px; border-radius: 9999px; background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.2); backdrop-filter: blur(24px); color: #ffffff`

**Text style:** `action` — inter 500 · 13.3px/1.45 · tracking -0.004em

**Observed:** May include a small play or platform symbol before the label. Shares the primary's compact scale.

**States:** Declared: hover scale 1.02 and white background at 20%; focus-visible outline-style none and a zero box-shadow stack.

### Inverse button

**Use:** Newsletter submission and selected inverse calls to action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; padding: 10px 20px; border-radius: 9999px; background: #ffffff; color: #09090b`

**Text style:** `action` — inter 500 · 13.3px/1.45 · tracking -0.004em

**Observed:** Solid white against violet or black; local-bar variants are smaller, with 6px 12px padding.

**States:** Declared: hover scale 1.02 and pale neutral background; focus-visible outline-style none and a zero box-shadow stack.

### Announcement banner

**Use:** A release or major news item beneath the opening scene.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 32px; background: #0b0a12; border: 1px solid rgba(255,255,255,0.1); border-radius: 32px; overflow: hidden`

**Text style:** `heading-small` — googleSans 500 · 39.1px/1.25 · tracking -0.02em

**Observed:** Left text stack has an app icon, release label and small gold NEW badge, heading, short paragraph and Glass button. A smaller rounded video still sits at right; desktop text has 40px insets.

**Transfer:** Use for genuinely newsworthy content; maintain the hierarchy rather than repeating hero-scale copy.

### Product choice card

**Use:** Explain several ways to adopt the product.

**CSS:** `display: flex; flex-direction: column; background: rgba(255,255,255,0.075); border: 1px solid rgba(255,255,255,0.16); border-radius: 24px; overflow: hidden; backdrop-filter: blur(24px)`

**Text style:** `card-title` — googleSans 500 · 31.2px/1.25 · tracking -0.018em

**Observed:** A black-backed object render occupies the upper 356px. Below it, name and compact price share a row, then hairline-separated attributes, a best-for paragraph and actions. Desktop cards are 408px wide with 28px information insets.

**Transfer:** Use a few meaningful choices, not an exhaustive pricing spreadsheet.

### Customer post

**Use:** Credible, personal proof in a floating collage.

**CSS:** `background: linear-gradient(rgba(39,39,42,0.92), rgba(24,24,27,0.97) 60%, rgba(24,24,27,0.92)); border: 1px solid rgba(255,255,255,0.12); border-radius: 24px; box-shadow: 0px 30px 90px rgba(0,0,0,0.55), inset 0px 1px 0px rgba(255,255,255,0.12); transform: perspective(1400px) translate(0px,6px) rotate(-3deg)`

**Text style:** `quote` — inter 400 · 16px/1.75 · tracking -0.011em

**Observed:** Avatar and author metadata above a naturally sized quote, followed by optional attached media. About 350–377px wide; neighboring posts use differing slight tilts. Light-chapter variant uses white cards with pale borders and softer shadows.

**Transfer:** Use authentic short statements with variable heights and actual work or usage images.

### Email field

**Use:** Newsletter entry within the violet closing field.

**CSS:** `height: 44px; min-width: 0px; padding: 0px 16px; border-radius: 9999px; background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.1)`

**Text style:** `navigation` — inter 400 · 13.3px/1.45 · tracking -0.004em

**Observed:** Flexible input beside an Inverse button in a 448px-wide form with an 8px gap.

### Feature carousel

**Use:** Short, cinematic product highlights.

**CSS:** `width: 928px; height: 580px; background: #0b0a12; border-radius: 32px; overflow: hidden`

**Text style:** `media-caption` — googleSans 400 · 31.2px/1.375 · tracking -0.018em

**Observed:** A full image or film with top-left caption, 40px insets and a top dark gradient. Next card peeks beyond the right edge. Below: active 40×8px progress pill, inactive 8px dots, pause control and separate 44px circular previous/next buttons.

**Transfer:** Show one real behavior per card; preserve the partial next-card invitation.

### FAQ row

**Only for:** culture and recruiting pages

**Use:** Final practical objection handling.

**CSS:** `border-bottom: 1px solid rgba(255,255,255,0.1); padding: 20px 0px; display: flex; align-items: center; justify-content: space-between; gap: 16px`

**Observed:** An 896px-wide question list below a centered chapter heading. Questions are Inter 20px medium with 31px line height and -0.3px tracking; a small downward chevron is right-aligned. Final row has no bottom rule.

## Imagery and graphics

### Domestic cinema

**Use:** Opening and emotional product-in-use chapters.

**Observed:** Warm natural light, quiet desks, plants, wood and ceramic objects surround black hardware and screens. A laptop or monitor is the main visual mass, smaller devices establish scale. Shallow focus and low-key edge shading create a premium, lived-in atmosphere, not a sterile studio.

**Transfer:** Photograph the new product in an attractive but plausible daily setting. For software, use one real screen in a domestic workspace rather than a collage of detached dashboard rectangles.

**Build:** Use a wide photograph within 32px corners. Add a bottom linear gradient from rgba(0,0,0,0.75) to transparent over the lower 70%, plus a subtle vignette. Place a blurred enlarged copy of the image behind the panel to spill its warm neutral light into the black canvas.

### Floating interface stage

**Use:** A required visual proof device within software and capability storytelling.

**Observed:** Large browser or desktop views float over black, sometimes with a shallow perspective tilt. Scenic wallpapers and dark translucent windows give the interface rich blue, violet and warm sunset light. The image often spans roughly 974px; a broad, low halo supports it.

**Transfer:** Use a real, legible interface with a single principal task. Minimum treatment is a clean browser frame, a coherent scenic or abstract backing and a soft halo, not invented tiny UI detail.

**Build:** Center an approximately 974×540px image, round it 16px and add the dark glass shadow. Behind it use an absolute 1440×640px radial-gradient(82% 60% at 50% 36%, rgba(251,146,60,0.5) 0%, rgba(244,114,182,0.26) 45%, rgba(0,0,0,0) 78%). Let the media's own blue tones remain vivid; match the soft glow rather than making a hard neon border.

### Light interface showcase

**Use:** Broad ecosystem demonstrations within Light chapter.

**Observed:** An oversized dark application view sits on a bright landscape wallpaper inside a milky white rounded frame, filling most of the lower chapter. Text is centered above it and visually much smaller than the media.

**Transfer:** Keep the interface useful and readable; a single large view is stronger than many equally small windows.

**Build:** Use a 1280px-wide outer frame with 10px padding, 32px corners, rgba(255,255,255,0.5) fill, 1px rgba(255,255,255,0.75) edge, blur(24px) backdrop and the light interface shadow.

### Object studies

**Use:** Product selection, specifications and hardware closing scenes.

**Observed:** Black or graphite objects emerge from black with narrow white rim light and restrained warm reflections. Rotating views and close-ups reveal ports, texture, wood trim and internal components. A hand-held view communicates size. The closing scene moves from an enormous detail to a centered whole object.

**Transfer:** Use accurate, softly lit renders or carefully masked photographs. A service can substitute a tangible tool or a physical device running it, with the same black backing and edge lighting.

### Detail poster fan

**Only for:** software detail chapters

**Use:** A theatrical proof of small interaction quality.

**Observed:** Overlapping portrait panels, about 368×468px, tilt independently over black. Soft green, purple, cyan and peach light sits behind small interface demonstrations; a short editorial serif phrase is embedded in the artwork above each demo.

**Transfer:** Turn several fine-grained benefits into art-directed posters rather than generic feature cards. Keep the serif lettering inside the poster artwork, not as the main page font.

**Build:** Make five 24px-radius panels with near-black bases and 1px white-at-14% edges. Overlap them by about 43px, alternate shallow positive and negative rotations, and layer broad blurred colored ellipses behind each central UI fragment. Add a low-opacity fine dot texture, inner highlight and deep shadow. Minimum version uses three accurately composed static posters.

### Culture visual accordion

**Only for:** culture and recruiting pages

**Use:** Illustrate working principles and product craft.

**Observed:** A wide 390×480px image panel sits alongside three collapsed strips about 87px wide, numbered in their top corners. A black fade anchors a small caption at the bottom; images include product details, interface views and real environments.

**Transfer:** Use work artifacts or environment photography to substantiate principles, not a decorative team headshot wall.

### Atmospheric invitation

**Only for:** culture and recruiting pages

**Use:** Application or participation callout.

**Observed:** A 1264×734px rounded panel shifts from almost black at top to diffuse navy and pale gray light at bottom. Three translucent numbered cards sit over the backdrop below the heading and paragraph.

**Transfer:** Use an approachable, text-led invitation with a clearly bounded next step.

**Build:** Clip the scene at 32px corners. Layer a dark-to-transparent top gradient over a blurred blue-gray photographic or abstract background; place a broad pale blurred ellipse below the lower edge. Use 24px-inset glass cards in a three-column row. Keep the top dark enough for white type.

### Icons

**Observed:** Functional arrows and chevrons use 16–20px round-ended strokes, commonly 1.8px. Play and platform symbols are compact filled forms. Category graphics are colorful, dimensional app-like objects rather than a uniform outline icon grid.

**Transfer:** Use restrained monochrome functional controls and richer tactile category illustrations. Keep expressive graphics out of the navigation.

## Section recipes

How recurring sections are built.

### First screen: Domestic scene opening

**Observed:** Cinema canvas behind Global navigation. A centered, approximately 896px-wide promise begins after 144px top padding, set in display with a single display-script word. After 40px comes a 1264×630px, 32px-rounded domestic scene occupying nearly the whole remaining viewport. Back-to-front: soft ambient spill, photograph or film, subtle vignette and lower dark gradient, then a lower-left 576px-wide scene-heading with a 512px-wide body paragraph 12px below it, all inset 48px. The first 900px shows the headline, the complete main object scene and its argument; no hero CTA is forced above the image. The Announcement banner and its action start just below this first screen.

**Transfer:** Give a different product a similarly concrete scene and one human-scale headline word; without a physical object, show the software on a real device in an attractive workspace. Software-focused pages can instead open on off-white with centered text, two actions and an oversized fan of browser views. Culture pages use a smaller centered text-led opening with a faint violet halo and a white action.

**Avoid:** Do not turn this into a left-text/right-dashboard SaaS hero, or replace the large lived-in scene with a tiny isolated logo.

**Text style:** `display` — googleSans 500 · 61px/1.04 · tracking -0.024em

### Chapter heading pair

**Observed:** Eyebrow in muted sentence case, 16px gap to heading, 20px gap to body-lead; centered within a 768px block with narrower support text. Actions follow at 32px and major media at 56px. Major chapters commonly have 112px vertical padding.

**Transfer:** State a single benefit or argument per chapter; let the image substantiate the heading.

**Text style:** `heading` — googleSans 500 · 61px/1.25 · tracking -0.024em

### Manifesto and object shelf

**Observed:** A 39.1px manifesto line gains a brief italic ending; a four-column shelf of 304px square object images follows, with names, restrained descriptions and small pills below rather than inside each image.

**Transfer:** Use to reframe the problem and then introduce a small set of concrete offerings or entry points.

### Capability selector

**Observed:** A centered heading and support line sit over a broad atmospheric background. Six compact 112×96px category tiles lead into a horizontally extended demonstration panel. Dark variant uses translucent near-black tiles; light variant uses milky white tiles with a faint dark edge.

**Transfer:** Use for distinct user goals, pairing each category with real examples. Keep the category row compact relative to the media.

### Feature chapter rail

**Observed:** Left-aligned heading above a horizontal rail with 56px separation. Each item has 620×440px rounded media, then a 20px gap to body-lead copy with a bold opening phrase. Two items and part of a third are visible; 20px gutters, dots left and 44px arrows right.

**Transfer:** Use this denser light-theme recipe for explanatory software chapters with several related behaviors.

**Text style:** `heading` — googleSans 500 · 61px/1.25 · tracking -0.024em

### Choice and comparison

**Observed:** Centered heading above Product choice card in a three-column 20px-gap grid. Hardware detail pages also use a quieter 1024px table: two image-led product summaries above rows separated by white-at-10% hairlines, not boxed cells.

**Transfer:** Choose between a narrative card comparison and a factual table based on the decision's complexity.

### Floating social proof

**Observed:** Centered heading and body-lead followed after 80px by three 32px-gap columns of Customer post. Slight alternating tilts, mixed lengths and attached photos create a wall of lived experiences, not a perfectly aligned testimonial slider.

**Transfer:** Mix concise and longer genuine proof. Preserve the informal personal quality.

### Violet reveal ending

**Observed:** Every page ends on Violet closing field. At desktop it occupies 900px with a 1312px inner width. A white identity mark sits left while a 672px-wide closing-belief statement sits on the right. A large vertical pause separates this from a lower grid: newsletter at left and three link columns at right. Email field and Inverse button share one row; locale pill below. A white-at-15% rule separates the bottom copyright and social icons. The main page scrolls away above the sticky footer, revealing the violet plane.

**Transfer:** Close with the product's own brief belief, useful navigation and one low-pressure subscription action. Keep the large empty middle as intentional emphasis, not a place for more promotional cards.

**Text style:** `closing-belief` — inter 500 · 39.1px/1.375 · tracking -0.025em

### Hardware closing object

**Only for:** hardware product pages

**Observed:** Centered eyebrow, two-line heading and paired Primary button and Glass button float over an enormous rim-lit object detail. As the scene progresses the full product becomes centered and smaller; black continues into the footer reveal.

**Transfer:** Use a final tactile close-up and a simple ownership promise, followed by a complete object view.

**Text style:** `heading` — googleSans 500 · 61px/1.25 · tracking -0.024em

### Recruiting chapters and invitation

**Only for:** culture and recruiting pages

**Observed:** Alternating culture split sections pair Culture visual accordion with a heading and culture-body text marked by a 2px violet left rule and 20px left inset. An Atmospheric invitation follows, then an 896px FAQ row list.

**Transfer:** Explain concrete principles with artifacts, ask for a direct response, then resolve practical concerns.

## Page flow

**Storyline:** Personal promise → tangible experience → capability chapters → adoption choices → lived proof → practical next step → expansive belief-led ending.

### Brand and product-family introduction

1. **Promise** — Centered humanized headline above a domestic product scene, then a release banner.
2. **Reframing** — Short manifesto and a shelf of product entry points.
3. **Product demonstration** — Floating interface stage, cinematic highlights and selectable use cases.
4. **Breadth** — A contrasting off-white ecosystem chapter followed by a cross-device benefit panel.
5. **Adoption choices** — Three image-led comparison cards.
6. **Social proof** — A tilted wall of authentic user posts.
7. **Closing belief** — Full-height violet reveal footer.

**Transfer:** Use this as the default landing-page grammar, varying the number and order of capability chapters to suit the new product.

### Software platform explanation and adoption

1. **Promise** — Off-white centered claim with script emphasis, paired actions and oversized layered browser images.
2. **Product demonstration** — Black cinematic highlight rail and cross-device panel.
3. **Capability chapters** — Light ecosystem demonstration and multiple media rails with short explanatory copy.
4. **Craft proof** — Dark portrait poster fan demonstrates fine interaction details.
5. **Trust** — Light asymmetric bento with one dark data-art panel and smaller supporting claims.
6. **Adoption choices** — Dark three-card product choice grid.
7. **Social proof** — Light customer-post collage and tutorial video rail.
8. **Closing action** — Black centered action pair above a four-column resource strip, then violet reveal footer.

**Transfer:** Use polarity changes to distinguish demonstration, craft and trust rather than alternating color mechanically at every section.

### Hardware desirability, practicality and purchase

1. **Promise** — Full-bleed warm domestic scene with left-aligned two-line heading, ivory second line and compact purchase row.
2. **Use cases** — Split software benefit then expanding capability rows with media cards.
3. **Ease** — Two-step setup demonstration with cable and device close-ups.
4. **Product demonstration** — Floating software stage and film highlight rail.
5. **Emotional proof** — Full-width warmly lit living-room scene.
6. **Technical proof** — Rotating internal object study, small 2×2 detail cards and a restrained specifications table.
7. **Comparison** — Two-product factual comparison followed by customer collage and video rail.
8. **Closing action** — Monumental object close-up resolves into a full-object purchase scene before violet reveal footer.

**Transfer:** Combine emotional scenes with enough physical detail to make the object credible; keep specifications subordinate to the experience.

### Recruiting and culture

1. **Invitation** — Centered headline, support line and white action over black with a faint violet halo.
2. **Mission** — Word-by-word manifesto beside a square product film.
3. **Principles** — Alternating visual accordion and left-rule text chapters.
4. **Direct response** — Atmospheric invitation with three numbered prompts and email action.
5. **Objection handling** — Minimal FAQ list.
6. **Closing belief** — The same full-height violet reveal footer.

**Transfer:** Replace job-list bureaucracy with clear principles, concrete work artifacts and an approachable contact route when appropriate.

## Writing

Warmly opinionated and consumer-friendly, with technical confidence expressed through ordinary daily actions. It can be playful for a moment, but the supporting copy explains exactly what the product does.

**Do not copy:** Do not reuse Umbrel names, identity marks, product artwork, source testimonials, prices, storage capacities, app counts, release dates, claims or proprietary slogans. Examples below illustrate cadence only.

- **Addressing the reader:** Speak directly to you and your things; use we for beliefs and working principles. Name the product when explaining how an action happens.
- **Rhythm:** Headlines are commonly 3–9 words, often two short sentences or a compact contrast. Supporting paragraphs explain one concrete benefit in one to three sentences. Periods and contractions are natural; avoid a breathless exclamation-driven pitch.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Make a personal ownership or proximity claim with a human final word. | 5–9 words | “Your cloud, in your home.” |
| Benefit heading | Short paired phrases; the second resolves the first. | 3–7 words | “Feature-rich. Friction-free.”<br>“Small body. Solid numbers.” |
| Explanation | Name a familiar action, then explain the mechanism without administration jargon. | 20–45 words | “Photos back up on their own, your [Brand] shows up in Finder and File Explorer, and it all works from home or anywhere.” |
| Action | Direct verb with a concrete destination or object. | 1–5 words | “Explore umbrelOS”<br>“Watch the keynote”<br>“Join us” |
| Closing belief | Reject an accepted assumption, then offer a simpler personal alternative. | 10–18 words | “Because the cloud doesn't have to be somewhere else. It can be home.” |

**Words and phrasing to use:** your; own; right here; one click; just; on their own; built in; closer; simple action verbs

**Avoid:** enterprise-grade solutions; unlock limitless potential; revolutionary ecosystem; seamless synergy; admin-first jargon; excessive superlatives

**Rules:**

- Lead with what becomes easier or more personal, then show the mechanism.
- Use exact technical detail in supporting text, not as a substitute for a benefit headline.
- A playful word or graphic is a small interruption in an otherwise clear explanation.
- For culture copy, make principles falsifiable through actual practices rather than abstract virtues.

## Do's and Don'ts

### Do

- Keep chapter headings at 61px, weight 500 and -0.024em tracking on desktop.
- Use the tighter 1.04 line height for the opening and 1.25 for chapters.
- Give cinematic media 32px corners and proof cards 24px corners.
- Keep ordinary action labels at 13.3px with 10px 20px pill padding.
- Use 112px vertical chapter padding and a 768px heading block to control the long-page rhythm.
- Preserve a visible fragment of the next item in 928px-wide highlight rails.
- Stage object renders on black and let edge light reveal their form.
- Finish with the spacious violet belief-led footer rather than a small utility strip.

### Don't

- Do not turn medium geometric headings into heavy 700-weight grotesk shouting.
- Do not use script for paragraphs or several unrelated words in each section.
- Do not replace rounded pills with squared 56px-tall conversion bars.
- Do not distribute violet as the fill of every card; its largest field belongs at the ending.
- Do not flatten the proof collage into equal-height corporate quote boxes.
- Do not render every surface with the same glass opacity; media panels, product cards and customer posts have distinct materials.
- Do not put thick light borders around black media; use 1px alpha edges.
- Do not set specifications in huge display numerals; the factual rows stay compact.

## Motion and responsive

### Motion

**Observed:**

- Hero entrance is declared at 0.8s cubic-bezier(.16,1,.3,1); a hero cover animation is declared at 1.6s with the same curve.
- Primary and secondary action transitions are all 0.3s cubic-bezier(.4,0,.2,1), with a 1.02 hover scale.
- Highlight indicators declare width and background-color transitions of 0.5s cubic-bezier(.16,1,.3,1).
- Accordion expansion declares flex-grow 0.7s cubic-bezier(.16,1,.3,1).
- The footer is sticky beneath the main page and revealed by scrolling rather than appended as a visually continuous black strip.

**Transfer:**

- Keep motion attached to revealing objects, showing an interaction or clarifying the current rail item. Preserve pause and directional controls for cinematic highlights.
- Use the reveal-footer layering as the signature page-ending movement.

**Unknown:**

- Exact scroll timelines, playback timing, and all 3D camera paths are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- The global link cluster is hidden below the medium breakpoint. The outer content uses 20px side padding before 24px at wider widths.
- The highlight rail uses min(86vw, 928px) cards; proof columns become a vertical stack, and product shelves progress from stacked to two and then four columns.

**Transfer:**

- Keep the full-bleed media and partial-next-card relationship on narrow screens instead of shrinking a complete desktop rail into view.
- Let the script word wrap with the phrase it qualifies. Stack footer belief, subscription and link groups while preserving their strong separation.

**Unknown:**

- Mobile image focal points, exact narrow-screen headline sizes and full menu behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
