# Aside — cloudlit working surfaces

## Overview

An airy, light software style that makes capable technology feel tangible and approachable. Black grotesk headlines and soft gray explanations sit inside faint architectural rules, while cyan skies, luminous blue atmosphere and pastel-backed interface illustrations supply the emotion. It suits product launches and capability-led marketing with spacious storytelling and compact, functional controls.

### Essentials

- A sky-lit product stage, not a text billboard: a 16px outer inset, 33.6px rounded scene, centered 48px/52px regular headline and a broad translucent application window beginning beneath the action.
- Headlines feel conversational rather than monumental: display sans at 48px weight 400 with -0.01em tracking, 44px/48px weight 450 for major promises and 30px/40px weight 500 for explanatory chapters.
- Actions look like small pieces of software: a black 40px pill in the opening, split by a 1px light divider into a download label and a 40px chevron target; repeated actions use 44px height and 16.8px corners.
- Color lives behind the product: keep the long reading canvas white or #fafafa; concentrate cyan and blue in the opening and closing atmosphere, and other pastel colors inside 383px × 320px demonstration images. Paragraphs remain neutral.
- Feature captions run together like explanatory notes: a 16px/24px medium black lead continues inline into regular gray text, 20px below the image, rather than becoming a separate large card heading.
- Make the ending glow: a 1248px × 468px rounded atmospheric blue panel with a centered 44px/48px two-line invitation and a black split action. Recreate its soft blue basin and fading dot field even when no product artwork is available.
- A faint frame holds the long story together: content sits between 1px black-at-6% vertical rules, with 96px desktop gutters and 64px or 96px chapter padding; illustrated cards are separated by 24px of open space.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cyan sky | `#8eeef3` | `--color-sky` | background, accent | Sky atmosphere behind the opening application stage; balance with soft white cloud masses. |
| Pale blue atmosphere | `#e2f7fc` | `--color-mist` | background | Outer light of the closing blue basin, fading toward white. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Luminous blue | `#1662fd` | `--color-blue` | accent, background | Small word shimmer and the concentrated center of atmospheric art; proof bars use a similarly vivid blue. |
| Shimmer cyan | `#38bdf8` | `--color-cyan` | accent | Blue highlight transitions and luminous illustration detail. |
| Blue-teal link | `#0086b3` | `--color-link` | link, text | Sentence-case chapter links and inline learn-more actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#090b0c` | `--color-ink` | text, action | Headlines, emphasized caption leads and dark action backgrounds. |
| Explanatory gray | `#737373` | `--color-muted` | text | Body explanations and supporting text. |
| Soft label gray | `#8f8f8f` | `--color-muted-label` | text | Footer group labels; visible result of #737373 at 80% over white. |
| Silver word highlight | `#d0d6d8` | `--color-shimmer-gray` | accent | Transient silver treatment within selected display words; not a static low-contrast headline color. |
| Footer rule | `#e5e5e5` | `--color-footer-rule` | border | Horizontal rule above the copyright row. |
| Frame hairline | `#f0f0f0` | `--color-edge` | border | Visible result of black at 6% over white; long vertical framing rules and proof-row separators. |
| Light tile gray | `#f5f5f5` | `--color-tile` | surface | Integration tiles, tab tracks and neutral illustration backing. |
| Near-white band | `#fafafa` | `--color-band` | background, text | Subtle section bands and light text on dark actions. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Main reading canvas and foreground application panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| split product spotlights | Charcoal media backing | `#222b2f` | `--color-dark-media` | background | A single contrasting inset product-art panel, not an alternate page theme. |

## Typography

- **displayFont** — Headlines, editorial introduction, prices and small endorsement text. Smooth modern grotesk with open counters and a rounded, conversational regular weight. If unavailable, use **Inter**. Use weights 400, 450 and 500; retain the restrained size and headline tracking. Font stack: "displayFont", "Inter", Arial, sans-serif.
- **Geist** — Body explanations, actions, navigation and captions. Compact contemporary grotesk, neutral and highly legible at interface sizes. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | displayFont | 400 | 48px | 52px | -0.01em | Main opening promise, centered and usually broken into two balanced lines. |
| heading-lg | displayFont | 450 | 44px | 48px | normal | Major chapter promises and atmospheric closing invitation. |
| heading | displayFont | 500 | 30px | 40px | normal | Narrow explanatory chapter headings. |
| editorial | displayFont | 400 | 20px | 1.4 | normal | Problem-and-alternative introduction, with weight 450 black lead sentences. |
| body-lg | Geist | 400 | 18px | 28px | normal | Section introductions and hero support on white. |
| body | Geist | 400 | 16px | 1.5 | normal | Illustrated card explanations. |
| label | Geist | 500 | 16px | 1.5 | normal | Inline caption leads, blue chapter labels, proof values and repeated action labels. |
| hero-action | Geist | 450 | 16px | 1.5 | normal | Opening pill action label. |
| navigation | Geist | 500 | 14px | 20px | normal | Navigation, footer links and segmented controls. |
| endorsement | displayFont | 550 | 12px | 16px | 0.01em | Tiny sentence-case endorsement above the opening promise. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | displayFont | 450 | 48px | 52px | -0.01em | Pricing opening promise. |
| pricing pages | price | displayFont | 400 | 48px | 1 | normal | Price numerals; billing suffix is smaller and muted beside the baseline. |
| split product spotlights | spotlight-heading | displayFont | 500 | 30px | 1.2 | normal | Compact multi-line heading and muted continuation in a split product spotlight. |
| pricing pages | plan-name | displayFont | 500 | 18px | 28px | normal | Plan names and inline suitability descriptions. |
| integration and migration sections | tile-caption | Geist | 500 | 13px | 1.5 | normal | Small centered labels beneath integration icons. |

**Notes:**

- Do not enlarge the opening into an oversized typographic spectacle: its impact comes from the sky and the broad application stage.
- Only the 48px display recipes tighten tracking. Smaller headings retain normal spacing, with weight increasing gently to 500.
- Caption leads share their paragraph's 16px/24px metrics; contrast comes from weight 500 and near-black, not extra size.
- Use title and sentence case, not tracked uppercase eyebrow styling.

## Layout

**Density:** Airy sections with compact software-like controls; broad media and generous chapter padding do the work instead of oversized type.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Compact icon-label spacing in the opening action. |
| 8px | Repeated footer-link spacing and standard action icon gaps. |
| 12px | Heading-to-support gap in chapter introductions. |
| 16px | Opening outer inset and caption side padding. |
| 20px | Image-to-caption gap and feature hero headline-to-support gap. |
| 24px | Illustrated card-grid gaps and eyebrow-to-major-heading spacing. |
| 32px | Opening headline-to-action gap. |
| 40px | Navigation gaps, introduction-to-card spacing and proof-to-tabs gap. |
| 64px | Narrow chapter intro vertical padding. |
| 80px | Space above layered demonstration imagery in explanatory scenes. |
| 88px | Feature hero top padding. |
| 96px | Major chapter padding, desktop outer gutters and pre-closing space. |
| 128px | Closing banner vertical padding. |

### Containers and grids

- **outer container**: max width 1536px · side padding 96px. Centered long-form marketing frame. At 1440px the inner width is 1248px, bounded by faint vertical rules.
- **reading column**: max width 718px. Left-aligned chapter introduction nested centrally within the larger frame, using 264px side insets inside it.
- **major chapter column**: max width 958px. Wider promise blocks and comparison tables, using 144px side insets within the frame.
- **feature grid**: 3 columns · gap 24px · side padding 24px. Three equal illustration-and-caption items, each about 383px wide at desktop.
- **assurance grid**: 4 columns · gap 24px · side padding 24px. Four compact white illustration windows on a near-white band; media is 282px × 320px.
- **footer groups**: 5 columns · gap 12px. Four groups up to 240px wide and a narrower final utility group, rather than equal-width boxed cards.

## Corner radius

| Element | Radius |
| --- | --- |
| opening scene | 33.6px |
| large media and closing banner | 22.4px |
| split actions and integration tiles | 16.8px |
| illustration windows and selected tabs | 11.2px |
| opening action and endorsement | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| scene elevation | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Large opening frame and overlapping small application windows, not ordinary feature captions. |
| selected tab | `0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | White selected segment above a light gray track. |

### Surfaces

#### Reading canvas · level 0

**Use:** Long reading stretches.

**CSS:** `background: #ffffff; color: #090b0c`

#### Ruled chapter frame · level 0

**Use:** Continuity between chapters.

**CSS:** `border-left: 1px solid rgba(0,0,0,0.06); border-right: 1px solid rgba(0,0,0,0.06)`

**Observed:** Vertical edges continue through text and image sections; full-width horizontal separators mark larger chapter boundaries.

**Transfer:** Keep the same framing across varied content rather than outlining each paragraph.

#### Near-white band · level 0

**Use:** Subtle grouping for assurance content or layered demos.

**CSS:** `background: #fafafa`

**Observed:** Some chapter backgrounds fade from white at 18% to near-white at the bottom; another fades near-white to white.

**Transfer:** Let the band remain almost indistinguishable from the white canvas.

#### Illustration window · level 1

**Use:** Backing for an individual explanatory product scene.

**CSS:** `background: #f5f5f5; border-radius: 11.2px; overflow: hidden`

**Observed:** The colored artwork fills the window. Captions sit outside on white, not inside a raised card shell.

**Transfer:** Use the neutral base beneath pastel art or a deliberately composed interface vignette.

#### Translucent application stage · level 2

**Use:** Opening product demonstration.

**CSS:** `background: rgba(255,255,255,0.64); border-radius: 22.4px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.8), 0px 0px 0px 0.5px rgba(9,11,12,0.2), 0px 20px 25px -5px rgba(0,0,0,0.1); overflow: hidden`

**Observed:** A broad translucent outer browser shell backs a more opaque white content area and compact chrome.

**Transfer:** Use layered white planes with a thin edge; preserve a glimpse of atmospheric color through the outer layer.

#### Blue basin banner · level 0

**Use:** Closing conversion atmosphere.

**CSS:** `background: radial-gradient(ellipse at 50% 115%, #1662fd 0%, rgba(56,189,248,0.65) 38%, #e2f7fc 76%); border-radius: 22.4px; overflow: hidden`

**Observed:** A soft blue field pools toward the lower center, with pale edges and a receding field of translucent dots.

**Transfer:** Match the soft light and spatial depth; exact gradient stops are not essential.

#### Contrasting media inset · level 0

**Only for:** split product spotlights

**Use:** A dark backing behind one product-art panel.

**CSS:** `background: #222b2f`

**Observed:** The surrounding text area stays white; only the image half becomes charcoal.

**Transfer:** Keep contrast local to a demonstration rather than introducing a dark page theme.

## Components

### Navigation

**Use:** Top-level orientation.

**CSS:** `display: flex; align-items: center; justify-content: space-between; height: 56px; padding: 0px 16px`

**Text style:** `navigation` — Geist 500 · 14px/20px

**Observed:** Logo at left, centered sentence-case links separated by 40px, compact split action at right. Initially sits directly over the sky; subsequent reading uses a white sticky bar with a faint bottom rule. The compact header action is 36px high.

**States:** Declared: hover footer-style links turn gray with a dotted underline; focus-visible navigation links turn gray.

**Transfer:** Keep a small number of short destinations and one conversion action.

### Opening split action

**Use:** Primary conversion in the atmospheric opening.

**CSS:** `display: inline-flex; align-items: center; background: #090b0c; color: #fafafa; height: 40px; border-radius: 9999px; border: 1px solid transparent; overflow: hidden`

**Text style:** `hero-action` — Geist 450 · 16px/1.5

**Observed:** Download icon, label, fine translucent divider, then a separate chevron target. The whole group is 242px wide; the chevron target is 40px wide. Interior icon-label gap is 6px.

**States:** Declared: hover each target gains a 10% white overlay; focus-visible border uses medium gray; active scale stays 1 1.

### Repeated split action

**Use:** Conversion below feature introductions and in the closing banner.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; background: #090b0c; color: #fafafa; height: 44px; border-radius: 16.8px; border: 1px solid transparent; overflow: hidden`

**Text style:** `label` — Geist 500 · 16px/1.5

**Observed:** A 266px group contains the main target, a 1px translucent divider and a separate 40px chevron target. Pricing uses a 48px high group stretched across each plan; all plans use dark actions.

**States:** Declared: hover each target gains a 10% white overlay; focus-visible border uses medium gray; active scale stays 1 1.

### Chapter link

**Use:** Blue sentence-case eyebrow before a major promise.

**CSS:** `display: inline-flex; align-items: center; gap: 2px; color: #0086b3`

**Text style:** `label` — Geist 500 · 16px/1.5

**Observed:** Short topic label followed by a small right chevron; it can be centered above a promise or left aligned in a wider text block.

**States:** Declared: hover adds a dotted underline.

### Illustrated feature item

**Use:** Explain one concrete benefit with visible product behavior.

**CSS:** `display: flex; flex-direction: column`

**Text style:** `body` — Geist 400 · 16px/1.5

**Observed:** An Illustration window holds 383px × 320px art. Under it, a paragraph has 20px vertical and 16px horizontal padding; a medium black lead continues inline into gray regular explanation. No border or shadow wraps the combined item.

**Transfer:** Show one task or mechanism per item, with captions that explain what the image proves.

### Segmented control

**Use:** Switch proof datasets or billing cadence.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 4px; background: #f5f5f5; border-radius: 16.8px; height: 40px`

**Text style:** `navigation` — Geist 500 · 14px/20px

**Observed:** Segments are 32px high with 2px 12px padding and 11.2px corners. A white selected plate carries a small shadow; inactive labels are muted. Proof switches sit below the chart; billing switches sit above plans.

**States:** Declared: hover segment text becomes near-black; focus-visible adds a 1px solid medium-gray outline and matching border.

### Proof row

**Use:** Present quantified comparison without a heavy chart shell.

**CSS:** `display: flex; align-items: center; gap: 16px; height: 56px; border-top: 1px solid rgba(0,0,0,0.06)`

**Text style:** `label` — Geist 500 · 16px/1.5

**Observed:** Each row has a compact monochrome logo and name, a horizontal rectangular bar, then a right-aligned percentage. The leading bar is vivid blue; other bars are light gray. Rows span a 958px comparison column.

**Transfer:** Keep values modestly sized and aligned; let bar lengths, not giant numerals, carry the proof.

### Footer group

**Use:** Final utility navigation.

**CSS:** `max-width: 240px`

**Text style:** `navigation` — Geist 500 · 14px/20px

**Observed:** Muted group label above black links spaced 8px apart; external links receive small northeast arrows. Five groups sit on white with no enclosing boxes. A separate rule precedes copyright at left and 20px social icons at right.

**States:** Declared: hover links turn gray and gain a dotted underline.

### Integration tile

**Only for:** integration and migration sections

**Use:** Reassure readers about compatibility or switching.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 16px; width: 160px; height: 160px; background: #f5f5f5; border-radius: 16.8px`

**Text style:** `tile-caption` — Geist 500 · 13px/1.5

**Observed:** A centered 56px product icon sits above the small muted label. Six evenly distributed tiles occupy a desktop row.

**Transfer:** Use relevant recognizable integration symbols; the backing remains neutral even when the symbols are colorful.

### Plan column

**Only for:** pricing pages

**Use:** Side-by-side subscription comparison.

**CSS:** `display: flex; flex-direction: column; min-height: 500px; padding: 1px 40px 0px 40px; border-right: 1px solid rgba(0,0,0,0.04)`

**Text style:** `plan-name` — displayFont 500 · 18px/28px

**Observed:** Plan name and muted suitability statement lead into a 48px price, compact check-mark list and bottom-aligned dark split action. The last column has no right rule. No plan is raised or surrounded by a saturated recommendation card.

**Transfer:** Make price and capability differences legible through alignment and whitespace, not decorative badges.

## Imagery and graphics

### Cloudlit opening scene

**Use:** The signature first impression for a marketing landing page.

**Observed:** Bright cyan sky with large soft white clouds surrounds a broad front-facing application window. The headline remains black and uncluttered above it. The window occupies nearly the full scene width and is cut off by the lower viewport edge.

**Transfer:** Stage a credible interface or simplified functional mockup of the new product against the same airy sky. If no production UI exists, show a small set of realistic controls and a legible result rather than an abstract empty rectangle.

**Build:** Use a cyan base with layered irregular cloud silhouettes made from overlapping white SVG ellipses. Blur their edges by 16px–32px, varying white opacity from 0.55 to 0.9; cluster large clouds toward the right and lower edges and leave the headline zone calm. Add the Translucent application stage in front. Keep the 16px inset and 33.6px outer rounding.

### Pastel workflow vignettes

**Use:** Recurring illustrated feature grids.

**Observed:** Cropped real-looking interface fragments float over luminous pastel pink, cyan, mint, lime, lavender, orange or yellow backdrops. Small prompt bubbles introduce tasks; white menus, sheets, messages or file rows show the result. Soft shadows and occasional translucent diagonal planes add depth without photographic realism.

**Transfer:** Compose product-specific before-and-result fragments at readable scale. A minimum version is one white interface card and one short prompt bubble over a softly lit colored background; do not reduce the art to unrelated icons.

**Build:** Within a 383px × 320px rounded window, blend two or three pastel radial gradients, add a diagonal translucent white polygon, then overlap a white UI panel and smaller white task bubble. Clip some panel edges at the frame boundary and use a low-opacity black shadow. Keep bright color confined to this image window.

### Perspective capability field

**Use:** Broad capability promise illustration.

**Observed:** Rows of colorful app-like rounded tiles recede into a tilted plane beneath a centered heading. The nearest row fades into white at the bottom; the field reads as broad reach rather than a conventional flat logo strip.

**Transfer:** Use product-relevant category symbols or original simple app tiles. Retain the receding grid and white fade, even when recognizable external icons are not appropriate.

**Build:** Create a grid of roughly three rows of rounded-square SVG symbols; apply perspective with rotateX around 45deg, keep columns evenly spaced, and mask the lower edge with a white linear fade. Use modest soft shadows beneath tiles, not thick 3D extrusions.

### Layered context windows

**Use:** Explain continuity between a request and its result.

**Observed:** A small gray request bubble sits to the left of overlapping white browser-history and response windows. The rear window is reduced to 60% opacity; the front is crisp. Both are about 432px wide with rounded top corners and soft shadows, clipped at the section bottom.

**Transfer:** Pair a recognizable input surface with an outcome surface. Leave enough negative space for the request, and show only the meaningful portion of each interface.

### Blue basin and dot field

**Use:** Signature closing atmosphere on every page type.

**Observed:** Pale icy blue edges surround a deeper cyan-to-blue lower center. A translucent field of small dots grows more visible toward the bottom center, giving the panel a sense of receding space behind the black invitation and action.

**Transfer:** Recreate this luminous spatial finish rather than ending on an unadorned generic CTA strip.

**Build:** Use the Blue basin banner surface. Overlay an SVG dot grid with approximately 3px circles at 20px intervals, white at 0.15 opacity; apply a perspective transform so rows recede upward and a radial opacity mask centered low in the panel. Add broad blurred white ellipses near both lower corners to wash out the edges. Keep text and action on an untransformed foreground layer.

### Monochrome assurance diagrams

**Use:** Four-item assurance band.

**Observed:** White image windows show pale gray menus, layered technical slabs and a central symbol surrounded by smaller symbols on a dotted orbit. Most of the illustration is very light; the essential control or central mark stays dark.

**Transfer:** Use grayscale diagrams of actual mechanisms, not colorful security clip art. Keep the effect diagrammatic and lightly dimensional.

**Build:** For a layered mechanism, stack three light-gray rhombi with vertical offsets and a soft shadow, adding short edge labels. For an ecosystem diagram, place a dark central product symbol inside a dotted circular orbit of muted category glyphs.

### Inspectable application view

**Only for:** technical feature detail pages

**Use:** Demonstrate transparency or detailed product control.

**Observed:** A wide front-facing desktop window shows dense neutral multi-column navigation and a detail pane. Its 1120px width and 22.4px corners give it presence; the lower UI is clipped into the section rather than miniaturized to fit.

**Transfer:** Show the product's actual inspection or control surface. Keep interface text as product UI, not as a second marketing typography system.

### Icons

**Observed:** Mostly compact filled SVG glyphs rather than a conspicuous outline icon family: 14px–18px in actions, 16px chevrons, 20px social icons, and 28px comparison logos. Illustration and product UI icons can retain their own colors; marketing controls remain monochrome.

**Transfer:** Choose compact, visually light symbols aligned to label centers. Reserve multicolor symbols for compatibility illustrations and product scenes.

## Section recipes

How recurring sections are built.

### First screen: Cloudlit product opening

**Observed:** A 16px white perimeter encloses a cyan cloud scene with 33.6px corners. A 56px Navigation sits within the scene. Below it, a tiny outlined endorsement precedes a centered two-line display headline, about half the viewport width, then the Opening split action with a 32px gap. There is no separate support paragraph in this default opening. The application stage begins beneath the action after generous breathing room, spans about nine tenths of the viewport and fills the lower half of the first 900px. Layers run sky, clouds, translucent browser shell, white content pane, then compact UI details. Within 900px the navigation, endorsement, whole promise, action and upper product demonstration are visible; the bottom of the application and next narrative block fall below the fold.

**Transfer:** Use the same broad, airy stage for a new marketing landing page, composing a meaningful interface mockup if finished product media is unavailable. Feature-detail pages instead open on white with 88px top padding, the same 48px display recipe, a support line after 20px, then a Repeated split action after about 32px; the next chapter can enter the first screen. Pricing opens with a centered promise, support and billing switch before the plan columns.

**Avoid:** Do not replace the scene with a dark gradient, enormous text or a small floating dashboard thumbnail; do not insert a dense paragraph between the default opening promise and action.

**Text style:** `display` — displayFont 400 · 48px/52px · tracking -0.01em

### Problem and alternative introduction

**Observed:** A wide ruled frame contains a blue Chapter link in a narrow left column and editorial-size prose in a larger right column, with 64px between them. Black medium lead sentences continue into gray regular text; two paragraphs are separated by 32px.

**Transfer:** State a familiar limitation and the more useful alternative in compact, concrete language.

**Text style:** `editorial` — displayFont 400 · 20px/1.4

### Major promise and capability field

**Observed:** Centered Chapter link, 24px gap, then a balanced two-line heading-lg above the Perspective capability field. A narrow 18px explanatory paragraph follows in its own spacious white block.

**Transfer:** Show the breadth of the new product through a coherent field of symbols or outputs, with a concise explanation below.

**Text style:** `heading-lg` — displayFont 450 · 44px/48px

### Narrow chapter introduction

**Observed:** The heading and 18px support align left within the central reading column. Use 64px vertical padding and a 12px heading-to-copy gap. Some headings have a short silver or blue shimmer word inline; it resolves into the normal phrase rather than acting as a separate badge.

**Transfer:** Introduce one mechanism, outcome or proof claim before showing it.

**Text style:** `heading` — displayFont 500 · 30px/40px

### Illustrated benefit grid

**Observed:** Three Illustrated feature items use 24px gaps. Feature detail pages place them about 40px below a narrow introduction; major landing chapters allow a larger 96px lead-in. The image is the card's mass; captions remain short and unboxed.

**Transfer:** Choose three distinct, concrete behaviors or outcomes, each with an interface vignette.

**Text style:** `body` — Geist 400 · 16px/1.5

### Quantified comparison

**Observed:** A narrow heading and support introduce Proof rows inside a wider 958px column. Five horizontal rows use logos, bars and right-aligned values; a Segmented control sits 40px below. No oversized standalone statistics interrupt the restrained type scale.

**Transfer:** Use validated comparative measures or replace the chart with an equally aligned evidence table.

**Text style:** `heading` — displayFont 500 · 30px/40px

### Integration and comparison

**Observed:** A narrow introduction leads to six Integration tiles. A later comparison uses a wide text-label column and three compact icon-headed result columns, 50px rows and faint 8%-black bottom rules; green checks, gray crosses and occasional amber warnings communicate outcomes.

**Transfer:** Use this pattern to reduce switching friction and explain compatibility or feature differences without a heavy boxed table.

**Text style:** `heading` — displayFont 500 · 30px/40px

### Split product spotlight

**Observed:** A 1248px framed row splits explanatory text and a large media inset. Text has roughly 64px horizontal and 48px vertical padding; a compact 30px heading can continue in muted gray, followed by details and a small neutral action. The media half can be charcoal or near-white according to the illustration.

**Transfer:** Give one distinctive capability more space than a grid item, using a controlled local backdrop instead of changing the whole page theme.

**Text style:** `spotlight-heading` — displayFont 500 · 30px/1.2

### Assurance band

**Observed:** A Near-white band holds a centered Chapter link, heading-lg and a short 18px support line, followed by four white illustration windows in a 24px-gap grid. Captions retain the inline black-lead and gray-explanation construction.

**Transfer:** Explain practical mechanisms or commitments with pale diagrams rather than decorative badges.

**Text style:** `heading-lg` — displayFont 450 · 44px/48px

### Atmospheric closing and utility footer

**Observed:** After 96px of separation, the Blue basin banner spans the inner frame with 22.4px corners and 128px vertical padding. Its centered two-line heading-lg is followed by a Repeated split action after 40px. The footer begins 96px later, presents five Footer groups, then a horizontal rule and copyright/social row. This ending is shared across the page types.

**Transfer:** End with one short invitation and the same primary action, then a sparse white utility footer; preserve the blue basin and dot field as the visual release.

**Text style:** `heading-lg` — displayFont 450 · 44px/48px

### Pricing comparison

**Only for:** pricing pages

**Observed:** A centered two-line pricing-display heading and support line lead into a billing Segmented control. Three Plan columns begin 72px below the switch. Below the plans a dashed separator introduces a left-aligned team offering, compact dark sales action and six short check-mark lines.

**Transfer:** Retain equal plan treatment and bottom-aligned actions; use the secondary offering for a different purchase path.

**Text style:** `pricing-display` — displayFont 450 · 48px/52px · tracking -0.01em

## Page flow

**Storyline:** Promise → concrete product behavior → explanatory capability chapters → proof and reassurance → atmospheric invitation → utility navigation.

### Broad product landing page

1. **Promise** — Cloudlit product opening with a large working application stage.
2. **Problem framing** — Two-column problem and alternative introduction.
3. **Product breadth** — Centered capability promise, perspective symbol field and illustrated workflow grid.
4. **Quantified proof** — Compact heading followed by restrained horizontal comparison bars.
5. **Capability chapters** — Layered context scene, illustrated benefit grid and split product spotlight.
6. **Reassurance** — Pale assurance band with four mechanism diagrams.
7. **Closing call** — Blue basin invitation and white utility footer.

**Transfer:** Use a long-form sequence when several mechanisms must become credible; reorder chapters to suit the product without losing the contrast between atmosphere, concise text and tangible demonstrations.

### Subscription decision page

1. **Promise** — Centered white opening with a compact upgrade proposition.
2. **Pricing** — Billing switch, three aligned plan columns and bottom-aligned actions.
3. **Alternate purchase path** — Left-aligned team offering with short check-mark benefits and sales action.
4. **Closing call** — Shared blue basin invitation and five-group footer.

**Transfer:** Let the offer structure carry this page; avoid importing the broad product scene above the prices.

### Trust-sensitive feature detail

1. **Promise** — White centered feature opening with support and split action.
2. **Mechanism explanation** — Narrow intro and three pastel-backed illustrated benefits.
3. **Switching reassurance** — Six neutral compatibility tiles.
4. **Comparison** — Icon-headed feature matrix with lightweight rules.
5. **Closing call** — Shared atmospheric invitation and utility footer.

**Transfer:** Use for a feature that must overcome friction, risk or switching objections; pair every assurance with a visible mechanism.

### Continuity and context feature detail

1. **Promise** — White centered feature opening with one support sentence and split action.
2. **Product demonstration** — Layered request, history and result windows on a subtle gradient.
3. **Capability explanation** — Three vivid illustrated behaviors with inline captions.
4. **Transparency** — Wide inspectable application view under a narrow explanatory heading.
5. **Closing call** — Shared atmospheric invitation and utility footer.

**Transfer:** Use for a feature whose value grows through use; make the relationship between input, retained information and outcome explicit.

### Performance-led feature detail

1. **Promise** — Short white feature opening with support and split action.
2. **Practical behavior** — Narrow introduction and three workflow vignettes.
3. **Quantified proof** — Blue leading bar, neutral comparison bars and dataset switch.
4. **Advanced capability** — Split explanation and a large cropped control-menu illustration.
5. **Closing call** — Shared atmospheric invitation and utility footer.

**Transfer:** Lead with understandable behavior before the performance proof, then explain the advanced capability that makes the proof relevant.

## Writing

Confident, practical and slightly provocative about familiar product limitations. The language describes work getting done rather than presenting a lofty future; warmth comes from directness and everyday tasks.

**Do not copy:** Do not reuse Aside names, logos, proprietary artwork, endorsement, benchmark rankings or percentages, prices, customer identities, security assertions or quoted product claims as facts about another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Refer to the product by name as an active subject, using concrete verbs rather than corporate we.
- **Rhythm:** Mostly short sentence-case promises, followed by one or two explanatory sentences. Card leads are short noun phrases or compact benefits; actions are literal and consistent. Use periods and occasional contrast, not exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar category reframed by an unexpectedly useful capability. | 5–12 words | “Your browser should remember your work”<br>“The most intelligent AI assistant, but it’s a browser.” |
| Chapter heading | Plain claim about a behavior, often phrased as a concrete change. | 4–9 words | “Built for how work actually happens”<br>“Your browsing history becomes memory” |
| Supporting explanation | Name the mechanism, then its practical consequence for the reader. | 1–3 sentences | “After each task, [Brand] saves what matters. It gets better at your work over time.” |
| Caption lead | Brief behavior or assurance followed inline by an explanation. | 2–6 words before the explanation | “Secrets stay invisible to AI”<br>“Human approval at the edge” |
| Primary action | Literal action with useful platform specificity. | 2–4 words | “Download for macOS”<br>“Contact sales” |
| Closing invitation | A short crafted-for statement followed by an immediate invitation. | Two brief clauses or sentences | “Crafted for both human and agent. Start using today.” |

**Words and phrasing to use:** your work; just like you; keeps; remembers; sign in; get work done; see; start; built for; without

**Avoid:** revolutionary ecosystem; unlock limitless potential; synergize; next-generation paradigm; magical transformation

**Rules:**

- Use concrete tasks or interfaces to ground broad promises.
- Explain what happens and what the reader no longer has to do.
- Pair a sharp contrast with a practical mechanism instead of piling up superlatives.
- Keep action wording stable as it repeats down the page.
- Use technical terms only when they explain a visible control, mechanism or verified assurance.

## Do's and Don'ts

### Do

- Keep the default opening display at 48px/52px, weight 400 and -0.01em tracking.
- Use a 16px perimeter around the atmospheric opening and 96px desktop gutters for the long reading frame.
- Give three-item illustration grids 24px gaps and 320px-high media windows.
- Set caption leads at 16px/24px weight 500 inline with regular gray explanations.
- Keep the black opening action at 40px high and repeated split actions at 44px.
- Use 1px black-at-6% rules for chapter framing and proof rows.
- Include the blue basin and dot field as a recognizable visual finish.
- Make comparison values 16px medium text aligned to the right of their bars.

### Don't

- Do not turn every 16px caption lead into a separate 24px card heading.
- Do not wrap illustration-plus-caption items in thick outlines or floating shadowed shells.
- Do not apply the charcoal media-panel color to the whole website.
- Do not give one pricing plan a giant colored promotional card; the three columns are comparably treated.
- Do not use tracked uppercase section labels; the blue links are sentence-case at 16px.
- Do not use the temporary silver word highlight as the final color of an entire heading.
- Do not sprinkle strong shadows across ordinary text blocks; elevation belongs to UI planes and selected controls.
- Do not make all actions pills: the opening is a pill, repeated actions use 16.8px corners and compact header targets use 11.2px inner corners.

## Motion and responsive

### Motion

**Observed:**

- Actions and surfaces declare 0.15s transitions with cubic-bezier(.4, 0, .2, 1), including all-property transitions and targeted color/background/border transitions.
- Selected words use a blue-cyan-silver text-clipped gradient with 400% background width; other heading words pass through silver during emphasis.
- A selected white tab plate is positioned under the active segment; source declarations include subscription-marquee and thinking-gradient keyframes.

**Transfer:**

- Use brief color and surface feedback on compact controls, not oversized hover movement.
- If reproducing heading shimmer, keep it local to one short phrase and resolve to legible near-black.
- Keep any moving interface demonstration inside its illustration window so the reading layout stays stable.

**Unknown:**

- Exact triggering, playback duration and easing of the larger product scenes and word shimmer are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1536px, with additional scene-specific thresholds.
- Feature items use fixed-width snap-start behavior before becoming a three-column grid; pricing uses a horizontal snap layout before becoming three columns.
- Footer classes define two columns at the smallest layout, three at the intermediate layout and a flexible desktop row.
- The opening headline region becomes left-aligned at the small breakpoint; the full desktop navigation links are hidden below the medium layout.

**Transfer:**

- Preserve the atmospheric first impression on narrow screens, but make the promise left-aligned and shorten the visible application viewport rather than shrinking every control into illegibility.
- Use horizontal snap rows for illustrated features and pricing where multiple full-width columns will not fit.
- Reduce outer gutters while retaining the faint framing rules and clear distinction between text and media.

**Unknown:**

- Exact mobile type sizes, menu behavior and tested narrow-screen scene composition are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
