# Whimsical — ideas in soft landscapes

## Overview

A light, welcoming software style that sets practical product demonstrations against grainy, dreamlike landscapes. Rounded bold display sans meets crisp geometric body text, with aubergine ink, lavender, pink skies and deep blue hills. Expansive opening and closing scenes surround a more restrained, readable middle, making it well suited to creative tools and collaborative products.

### Essentials

- Friendly, compressed headline silhouettes: Agrandir 700 at 64px/1.1 with -0.01em tracking for the opening, and 96px/1 with -0.01em tracking for expansive statements and the closing call.
- A product window embedded in a landscape, not a floating device mockup: a 1360px-wide, 80px-radius opening stage with a centered 680px headline, 480px support line and 1080px-wide interface demonstration rising into the first screen.
- Buttons are little mechanisms rather than pills: 48px tall with 12px corners, bold 16px/1 text and an opposing 32px rounded-square arrow inset at the right.
- Color lives in immersive bookends and selective illustrations: pink-lavender skies and blue-violet terrain fill the opening and closing stages; most intervening text and cards sit on #f7f7f8 with aubergine #220a33 ink.
- Fine grain and soft-edged terrain are signature materials: layered curved hills, warm pink light and cool blue shadows appear behind interface imagery and in a monumental closing scene. Recreate the landscape with SVG paths and noise when custom artwork is unavailable.
- The final action and the directory share one landscape: a centered 96px closing statement above a translucent white, 16px-radius four-column footer, all contained in a 40px-radius scene with 48px inner padding.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Aubergine ink | `#220a33` | `--color-ink` | text, action | Primary headings, default dark actions and dark icon tiles. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orchid link | `#9e39e5` | `--color-purple` | link, accent, action | Eyebrows and exploration links; a colored action on advanced pricing tiers. |
| Lilac sky | `#e9bded` | `--color-hero-sky` | background | Base of the opening landscape, shaded by a 16% aubergine overlay and colored terrain. |
| Terrain lavender | `#dbcbfd` | `--color-landscape-lavender` | background | Base color of rounded product chapter artwork. |
| Pink dawn | `#efe3ed` | `--color-dawn` | background | Alternate pale backdrop for product chapter artwork. |
| Fjord blue | `#bbcfe4` | `--color-closing-blue` | background | Cool sky base for the default closing landscape. |
| Clear blue | `#3981e5` | `--color-blue` | action, link | Exploration links for one capability; entry-tier pricing actions. |
| Electric indigo | `#4839e5` | `--color-indigo` | action, link | Exploration links for another capability; middle-tier pricing actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action | Cards, reversed scene text and light actions; navigation and footer use white at 88% opacity. |
| Cool off-white | `#f7f7f8` | `--color-canvas` | background | Default page canvas between landscape scenes. |
| Warm grey-lilac | `#f5f4f5` | `--color-inset` | surface | Recessed media wells within white cards. |
| Pale lilac | `#f0eef2` | `--color-wash` | background, surface | Feature fades; process cards and social-proof canvas. |
| Lavender edge | `#eae6ed` | `--color-rule` | border, surface | Hairlines and muted proof panels; also the inactive tone behind expressive statement lettering. |
| Dusty plum | `#8f8497` | `--color-muted` | text | Low-emphasis secondary metadata. |
| Muted plum | `#685c70` | `--color-body` | text | Supporting paragraphs and secondary labels. |
| Deep plum | `#443152` | `--color-strong-body` | text | Card descriptions and directory links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Overcast lilac | `#d2d1da` | `--color-pricing-sky` | background | Sky behind pricing plan panels. |
| pricing and customer-story pages | Bright magenta | `#e539d7` | `--color-magenta` | action, accent | Sales actions and enterprise tier differentiation. |

## Typography

- **Agrandir-0cfc125464d8d15e** — Display headlines, section headings and card titles. Broad, bold, friendly sans with distinctive curved shapes and a compact headline silhouette. If unavailable, use **DM Sans**. Use 700; preserve tight tracking and deliberately composed line breaks. Font stack: "Agrandir-0cfc125464d8d15e", "DM Sans", Avenir, Montserrat, Corbel, sans-serif.
- **Manrope-79d1da00e5f47c83** — Body, navigation, actions, labels and numeric prices. Clean geometric sans with open counters; medium body copy and notably bold small controls. Font stack: "Manrope-79d1da00e5f47c83", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| statement | Agrandir-0cfc125464d8d15e | 700 | 96px | 1 | -0.01em | fixed | Large idea statements and the closing call; also simple title-led openings. |
| hero | Agrandir-0cfc125464d8d15e | 700 | 64px | 1.1 | -0.01em | fixed | Default opening headline and major section leads. |
| heading | Agrandir-0cfc125464d8d15e | 700 | 48px | 1.1 | normal | fixed | Product chapters and capability-directory headings. |
| card-title | Agrandir-0cfc125464d8d15e | 700 | 24px | 1.1 | -0.01em | fixed | Capability card titles. |
| body | Manrope-79d1da00e5f47c83 | 500 | 16px | 1.4 | normal | fixed | Paragraphs and card descriptions. |
| body-strong | Manrope-79d1da00e5f47c83 | 600 | 16px | 1.4 | normal | fixed | Opening support text, short feature labels and FAQ questions. |
| action | Manrope-79d1da00e5f47c83 | 700 | 16px | 1 | normal | fixed | Buttons, exploration links and directory links. |
| eyebrow | Manrope-79d1da00e5f47c83 | 600 | 14px | 1.4 | 0.01em | fixed | Sentence-case section labels. |
| navigation | Manrope-79d1da00e5f47c83 | 700 | 13px | 1 | 0.009em | fixed | Compact header controls. |
| directory-label | Manrope-79d1da00e5f47c83 | 700 | 9px | 1.2 | 0.15em, uppercase | fixed | Tiny widely spaced headings above footer columns. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| customer-proof pages | proof-monument | Agrandir-0cfc125464d8d15e | 700 | 180px | 0.85 | -0.02em | size min(180px, 13vw) | Two-line social-proof declaration towering over a quote wall. |
| culture and recruiting pages | culture-monument | Agrandir-0cfc125464d8d15e | 700 | 128px | 1 | -0.02em | fixed | Large white heading within an isolated atmospheric scene. |
| pricing pages | price | Manrope-79d1da00e5f47c83 | 800 | 64px | 0.95 | -0.05em | fixed | Primary plan prices; currency and amount visually lock together. |
| process explanations | process-heading | Agrandir-0cfc125464d8d15e | 700 | 56px | 1.1 | -0.0114em | fixed | Centered introduction to the process grid. |
| focused product landing pages | compact-hero | Agrandir-0cfc125464d8d15e | 700 | 48px | 1.1 | -0.005em | fixed | Single-capability opening and paired promotional panel headings. |
| process explanations | process-title | Agrandir-0cfc125464d8d15e | 700 | 32px | 1.1 | normal | fixed | Short imperative titles beneath step illustrations. |
| pricing, culture and secondary promotional panels | lead | Manrope-79d1da00e5f47c83 | 500 | 24px | 1.4 | 0.01em | fixed | Expanded introductory paragraphs. |
| process explanations | process-body | Manrope-79d1da00e5f47c83 | 500 | 18px | 1.4 | normal | fixed | Process card descriptions. |
| pricing pages | comparison-copy | Manrope-79d1da00e5f47c83 | 500 | 14px | 1.4 | 0.01em | fixed | Feature allowances and comparison cells. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display hierarchy comes from bold scale and compact line spacing, not light-weight typography. Default display tracking stays near -0.01em; the largest proof declarations tighten to -0.02em.
- Body text stays at 500, short labels at 600 and actions at 700. Keep these weights distinct even when all are 16px.
- Expressive lettering can carry a moving landscape or violet-to-pink color treatment; use it on a short statement or capability name, not paragraphs.

## Layout

**Density:** Airy scenes and section transitions contrast with compact controls and practical 16px body text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small title-to-description gaps and control internals. |
| 16px | Opening headline-to-support gap and compact content groups. |
| 20px | Card-grid gutters and FAQ row gaps. |
| 24px | Capability-card padding and chapter copy-stack gaps. |
| 32px | Space beneath inset illustrations; eyebrow separation in feature intros. |
| 40px | Outer page gutters, process-card padding and section-to-section scene separation. |
| 42px | Closing headline-to-action gap. |
| 48px | Closing-scene and footer-panel inset. |
| 64px | Opening copy-block bottom padding and process-heading separation. |
| 120px | Major feature-section vertical padding and opening-stage top breathing room. |

### Containers and grids

- **scene-wrapper**: max width 1360px · side padding 40px. Centered immersive bookends at desktop, with the pale page visible around them.
- **content-container**: max width 1320px · side padding 40px. Shared wide alignment for navigation and feature grids.
- **hero-copy**: max width 680px. Centered two-line opening heading; supporting copy narrows further to 480px.
- **hero-demonstration**: max width 1080px. Large flat interface window centered below the opening action.
- **capability-grid**: max width 985px · 3 columns · gap 20px. Compact centered directory of 315px-wide cards; a partial last row remains left aligned.
- **feature-grid**: max width 1320px · 3 columns · gap 0px. Open illustrated feature matrix with 440px-wide cells, not separate floating cards.
- **process-grid** (only for process explanations): max width 1320px · 3 columns · gap 40px. Equal numbered process cards.
- **faq-grid** (only for FAQ sections): max width 1200px · 2 columns · gap 20px · side padding 120px. Two columns of 590px question panels.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 12px |
|  | navigation-and-directory-cards | 16px |
|  | hero-stage | 80px |
|  | chapter-art | 120px |
|  | closing-scene | 40px |
|  | inset-media | 8px |
| FAQ sections | faq-panel | 10px |
| pricing pages | plan-panels | 40px |
| pricing pages | comparison-groups | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | action-lift | `0px 12px 16px -4px rgba(37, 8, 53, 0.2)` | Primary dark and white scene actions. |
|  | directory-card | `0px 16px 32px -4px rgba(37, 8, 53, 0.06)` | Subtle lift beneath capability cards. |
|  | navigation | `0px 8px 16px -4px rgba(37, 8, 53, 0.04)` | Barely visible shadow below the floating header. |
| pricing pages | plan-card | `0px 20px 40px 0px rgba(17, 17, 17, 0.1)` | Translucent plan panels above landscape art. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #f7f7f8; color: #220a33`

#### Landscape stage · level 0

**Use:** Immersive opening scene.

**CSS:** `background-color: #e9bded; border-radius: 80px; overflow: hidden; position: relative`

**Observed:** A large pink-lilac sky above blue, violet and coral terrain; the artwork fills the stage rather than sitting as a separate image. A 16% aubergine overlay unifies it.

**Transfer:** Use the Grain landscape construction for a new terrain composition, preserving light space behind white copy.

#### Chapter art well · level 1

**Use:** Cropped interface details within alternating chapters.

**CSS:** `background-color: #dbcbfd; border-radius: 120px; overflow: hidden`

**Observed:** Landscape beneath the interface is subdued by an 8% plum overlay; the alternate version has a pink-dawn base.

**Transfer:** Keep the background visible above and alongside a large interface detail.

#### Inset media · level 1

**Use:** Quiet backing for small capability illustrations.

**CSS:** `background: #f5f4f5; border-radius: 8px; overflow: hidden`

#### Closing landscape · level 0

**Use:** Shared closing action and footer environment.

**CSS:** `background-color: #bbcfe4; border-radius: 40px; padding: 48px; overflow: hidden`

**Observed:** Grainy cool hills frame a warm pink central light. Secondary page types use a paler sky and blue-coral rolling dunes.

**Transfer:** Keep the art continuous behind both the call and the directory rather than ending it at the action.

#### Footer glass · level 1

**Use:** Readable directory embedded inside the closing landscape.

**CSS:** `background: rgba(255, 255, 255, 0.88); border-radius: 16px; backdrop-filter: blur(20px); outline: 1px solid rgba(255, 255, 255, 0.88); outline-offset: -1px; padding: 48px 48px 40px`

**Observed:** An additional white edge is softened with a low-opacity vertical mask. Terrain colors gently bleed through the white panel.

**Transfer:** Use actual translucency over the scene; preserve readable contrast.

#### Process panel · level 1

**Only for:** process explanations

**Use:** Large numbered instructional cards.

**CSS:** `background: #f0eef2; border-radius: 40px; padding: 40px`

#### Comparison group · level 1

**Only for:** pricing pages

**Use:** A category of aligned feature allowances.

**CSS:** `background: #ffffff; border: 1px solid #eae6ed; border-radius: 20px`

**Observed:** Section headers sit above equal-width cells with fine vertical and horizontal rules, circular tinted checks and understated unavailable marks.

## Components

### Floating navigation

**Use:** Persistent product and conversion navigation.

**CSS:** `background: rgba(255, 255, 255, 0.88); height: 48px; max-width: 1320px; border-radius: 16px; backdrop-filter: blur(10px) saturate(5); box-shadow: 0px 8px 16px -4px rgba(37, 8, 53, 0.04)`

**Text style:** `navigation` — Manrope-79d1da00e5f47c83 700 · 13px/1 · tracking 0.009em

**Observed:** Fixed header with a 36px top inset; identity at left, compact menu centered, sales and account actions at right. Internal controls are 40px high; sign-in uses a faint plum tint and sign-up is dark with an inset arrow tile.

**Transfer:** Keep the bar slim even when the page scene is monumental.

### Primary button

**Use:** Default marketing conversion.

**CSS:** `display: flex; align-items: center; background: #220a33; color: #ffffff; height: 48px; padding: 8px 40px 8px 20px; border-radius: 12px; box-shadow: 0px 12px 16px -4px rgba(37, 8, 53, 0.2)`

**Text style:** `action` — Manrope-79d1da00e5f47c83 700 · 16px/1

**Observed:** Label sits beside a white rounded-square arrow inset at right. The closing scene reverses the construction: white outer button, dark arrow tile and dark text. Width grows with the label rather than becoming a full-row bar.

**Transfer:** Preserve the contrasting arrow mechanism on the main conversion.

### Exploration link

**Use:** Low-pressure discovery below chapter copy and inside capability cards.

**CSS:** `display: flex; align-items: center; gap: 2px; color: #9e39e5; height: 24px`

**Text style:** `action` — Manrope-79d1da00e5f47c83 700 · 16px/1

**Observed:** A small right chevron follows the label; blue and indigo variants distinguish capabilities without adding filled backgrounds.

### Capability card

**Use:** Linked directory of product capabilities.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; padding: 24px; border-radius: 16px; box-shadow: 0px 16px 32px -4px rgba(37, 8, 53, 0.06); overflow: hidden`

**Text style:** `card-title` — Agrandir-0cfc125464d8d15e 700 · 24px/1.1 · tracking -0.01em

**Observed:** Inset media at top, title and compact description underneath, Exploration link aligned toward the bottom. Desktop cards are 315px by 464px; a 267px by 240px well clips an intentionally oversized interface illustration.

**Transfer:** Keep illustration, title, one useful sentence and destination link; do not turn it into a dense feature checklist.

### Footer directory

**Use:** Detailed navigation after the closing conversion.

**CSS:** `display: flex; justify-content: space-between; gap: 24px; padding: 24px 0px 34px`

**Text style:** `action` — Manrope-79d1da00e5f47c83 700 · 16px/1

**Observed:** Four link columns within Footer glass; tiny uppercase Directory-label headings above 38px link rows. Identity and copyright occupy a ruled top strip; a second rule separates the bottom row of AI discovery icons, social links and legal navigation.

**Transfer:** Use the actual information architecture while retaining the four-column rhythm and unusually small column headings.

### FAQ question

**Only for:** FAQ sections

**Use:** Compact objection handling.

**CSS:** `background: #ffffff; border-radius: 10px; border: 1px solid transparent`

**Text style:** `body-strong` — Manrope-79d1da00e5f47c83 600 · 16px/1.4

**Observed:** Question button fills the panel with 20px top, bottom and left padding and 60px right padding for a down chevron; collapsed outer height is 64px. Answer text uses Body. Panels are arranged in two columns.

**Transfer:** Use concise literal questions, keeping the chevron clear of long labels.

### Plan panel

**Only for:** pricing pages

**Use:** Side-by-side purchasing choices.

**CSS:** `background: rgba(255, 255, 255, 0.88); border-radius: 40px; padding: 20px 20px 24px; backdrop-filter: blur(8px); box-shadow: 0px 20px 40px 0px rgba(17, 17, 17, 0.1)`

**Text style:** `price` — Manrope-79d1da00e5f47c83 800 · 64px/0.95 · tracking -0.05em

**Observed:** Small tinted plan tag, price with compact unit, one audience line, colored action and a short included-features list. Three equal panels sit over rolling terrain; blue, indigo and orchid actions distinguish increasing tiers, with a magenta sales action beside the highest tier.

**Transfer:** Keep financial numbers in Manrope rather than the display face.

### Plan action

**Only for:** pricing pages

**Use:** Conversion within plan panels.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 48px; background: #3981e5; color: #ffffff; padding: 5px 20px; border-radius: 12px; box-shadow: 0px 12px 16px -4px rgba(37, 8, 53, 0.2)`

**Text style:** `action` — Manrope-79d1da00e5f47c83 700 · 16px/1

**Observed:** Centered label without the inset arrow used by the main marketing button. Indigo and orchid variants follow tier identity; later compact plan summaries use dark actions.

### Process card

**Only for:** process explanations

**Use:** Show a small number of steps as tangible product moments.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #f0eef2; border-radius: 40px; padding: 40px; overflow: hidden`

**Text style:** `process-title` — Agrandir-0cfc125464d8d15e 700 · 32px/1.1

**Observed:** Number tile and a thin rule at top, a restrained UI vignette in the middle, imperative title and Process-body copy anchored below. Equal-height desktop cards are 497px tall.

## Imagery and graphics

### Grain landscape

**Use:** Required visual identity across immersive opening, product chapters and closing scene.

**Observed:** Softly shaded abstract hills resemble folded dunes or river valleys rather than literal photography. Lilac skies and coral-pink horizons meet saturated blue and near-dark violet slopes. Fine visible grain roughens the gradients; broad curves and atmospheric fading keep it soft rather than glossy.

**Transfer:** Create a distinct abstract landscape with the same warm-center/cool-edge balance. The minimum equivalent is layered curved SVG terrain with gradient shading and fine noise, not a stock mountain photo.

**Build:** Fill the stage with a lilac sky. Overlay three broad SVG paths with curved ridgelines: a low pink hill behind, a lavender-blue slope entering from the left, and a dark plum-to-indigo slope from the right. Let the side hills occupy the lower half and leave the upper center calm. Shade each with linear and radial gradients using the palette's sky, dawn, blue, indigo and ink colors; add soft low-opacity white light near the horizon. Overlay an SVG feTurbulence noise layer at low opacity, clipped to the stage. Use restrained blur at distant ridges but retain visible grain. For the closing variant, raise the side hills around a broad pink central glow and cool blue sky; exact gradient stops are not essential.

### Flat product demonstration

**Use:** The dominant object in the opening and alternating capability chapters.

**Observed:** A large, flat, front-facing application window with a thin white top bar, subtle 12px corners, a 1px translucent white edge and a soft shadow. It shows real editing content, colorful objects, connections, collaborator avatars and toolbars. Chapter views enlarge a useful detail until some interface extends beyond the rounded art well.

**Transfer:** Use a real task-oriented interface for the new product. If unavailable, construct a plausible editable working state with a toolbar and meaningful content; prioritize recognizable activity over decorative dashboard charts.

### Feathered feature vignettes

**Use:** Compact feature explanations on the pale middle canvas.

**Observed:** Keyboard keys, collaborator cursors, comment bubbles and small interface windows sit over localized colored terrain. Artwork occupies roughly 400px of a 563px cell; the edges fade into the page so these are illustrations, not heavily bordered cards.

**Transfer:** Choose a concrete visual metaphor for each feature and combine one UI fragment with a small atmospheric backing. A simplified fragment over two softly masked color shapes is sufficient.

**Build:** Place a crisp UI fragment in front of two or three overlapping elliptical or curved terrain shapes in blue, dawn and purple. Mask the surrounding group with a radial white-to-transparent edge so it dissolves into the canvas; keep the foreground UI sharp and the outer backing softened.

### Customer portraits and proof wall

**Only for:** customer-proof pages

**Use:** Human proof near the opening and social validation further down.

**Observed:** Three narrow 233px by 360px portrait cards descend diagonally across the right half, with colored brand tiles near the top and white identity/story text over a bottom tint. Below, a full-width 80px grainy purple-to-pink logo ribbon precedes a monumental statement and three columns of compact social quotes. A final three-panel rating row uses muted lilac backgrounds and stars.

**Transfer:** Use genuine customer portraits and attributed quotes, retaining stepped placement and colored lower overlays. Keep the giant declaration as the visual anchor rather than enlarging every quote.

**Build:** For the ribbon, layer a horizontal ink-to-purple-to-magenta gradient with fine SVG noise and white partner marks. For portrait cards, clip cover-fit photos to softly rounded vertical rectangles and add a bottom-weighted plum gradient; keep faces unobscured.

### Diamond culture collage

**Only for:** culture and recruiting pages

**Use:** People-led opening.

**Observed:** A left-aligned heading and short lead sit beside an oversized composition of rounded diamond-shaped team photos. A pale lavender diamond with colorful cursor arrows interlocks with the photographs; the large upper photo extends beyond the viewport edge.

**Transfer:** Use candid people and place photographs from the new organization, not polished headshot tiles.

**Build:** Rotate rounded-square clipping wrappers 45 degrees and counter-rotate the photos inside. Combine one dominant photo and two smaller diamonds with a lilac filled diamond carrying a handful of small colored SVG pointer arrows.

### Isolated atmospheric monument

**Only for:** culture and recruiting pages

**Use:** A focused availability or participation statement.

**Observed:** A narrow 810px scene fades to the page on all sides. White 128px type sits over turquoise light, a pink hill and a dark blue horizontal fold, with a warm pale reflection underneath.

**Transfer:** Use this art-led treatment for a meaningful human invitation or status, rather than a general feature list.

**Build:** Center a tall SVG or masked gradient field. Layer a turquoise vertical glow, one coral rounded ridge, a dark blue horizontal band and a pale warm reflection below; use a soft outer mask and fine noise. Keep the white heading and support text within the darker upper-middle region.

### Trust illustration band

**Only for:** pricing and assurance sections

**Use:** Make operational reassurance visually substantial.

**Observed:** A 1320px by 658px landscape panel has 20px corners, large left-aligned dark text and a row of three white credential cards on the right. The backdrop is more vivid than normal middle sections: warm orange-pink folded terrain, deep cool shadows and grain.

**Transfer:** Replace credential illustrations with real assurances or verified standards relevant to the product; retain the contrast between colorful terrain and small white evidence panels.

### Icons

**Observed:** Small chevrons and utility marks use 16px SVGs with 1.5px round strokes; feature icons use 24px SVGs with 2px round strokes in purple, blue or indigo. Conversion arrows live in contrasting rounded-square tiles; social marks are compact filled silhouettes.

**Transfer:** Use simple round-ended outline icons for functional cues, preserving the different scale of inline chevrons and feature symbols.

## Section recipes

How recurring sections are built.

### First screen: Landscape product opening

**Observed:** A floating navigation bar occupies a slim strip near the top. Below a 124px page-top allowance, a 1360px-wide Landscape stage sits within 40px gutters. Its top corners are 80px. Back to front: grainy lilac-and-pink sky, low cool terrain, a subtle dark unifying tint, centered white copy and Primary button, then a large flat application window. The headline spans about half the stage in two lines at 64px/1.1, with a 680px limit; the 480px-wide support line follows at a 16px gap. The dark action sits clearly below the support. The 1080px demonstration starts near the lower third of the first 900px viewport, showing enough working content to explain the product while its lower portion and the logo proof row fall below the fold.

**Transfer:** Use an equally large task-oriented interface or a simplified working prototype over a newly composed Grain landscape. Keep the headline and action above the main object. Focused product pages use Compact-hero type with the same composition. Proof pages instead open with a left-aligned 96px title and stepped portraits; culture pages pair 64px left-aligned text with Diamond culture collage; pricing pages center a 96px title over translucent plan choices.

**Avoid:** Do not reduce the opening to a text-only pastel banner, place a tiny laptop at the bottom, or turn the terrain into a glossy 3D pedestal.

**Text style:** `hero` — Agrandir-0cfc125464d8d15e 700 · 64px/1.1 · tracking -0.01em

### Expressive statement

**Observed:** A 1080px-wide block of 96px/1 bold display text sits directly on the pale canvas. Violet and pink colored lettering provides an emphatic typographic bridge without cards or buttons.

**Transfer:** Choose one concise benefit statement and let its words carry a large, naturally wrapped composition. Keep the landscape color language inside the lettering if no artwork belongs here.

**Text style:** `statement` — Agrandir-0cfc125464d8d15e 700 · 96px/1 · tracking -0.01em

### Alternating capability chapter

**Observed:** A 680px by 640px Chapter art well sits beside a roughly 400px copy stack. The art and text switch sides in the following chapter. Heading uses 48px type with landscape-filled lettering, followed by Body and an Exploration link at 24px intervals.

**Transfer:** Give each chapter one concrete task and one enlarged interface detail. Alternate visual balance rather than squeezing several capabilities into the same block.

**Text style:** `heading` — Agrandir-0cfc125464d8d15e 700 · 48px/1.1

### Illustrated feature matrix

**Observed:** Centered sentence-case eyebrow, 64px bold section statement, then an open three-column matrix of Feathered feature vignettes. Short 16px semibold titles and 16px body descriptions sit beneath the art; major section padding is 120px.

**Transfer:** Present practical improvements in compact, parallel phrases. Maintain the feathered illustration treatment rather than adding heavy card surfaces.

### Capability directory

**Observed:** A 48px two-line heading above a centered Capability-grid. Each Capability card has a muted illustration well, 24px title, short description and colored Exploration link; 20px gutters retain a tidy browsing rhythm.

**Transfer:** Use for adjacent product paths or use cases, keeping a partial final row aligned to the grid start.

### Monumental closing and directory

**Observed:** Closing landscape contains a 552px-high centered call area above Footer glass. The 96px statement wraps into two lines within 820px, then a reversed Primary button follows at 42px. Beneath, the translucent 1264px-wide directory has an identity strip, four link columns, and separated lower utility rows. The scene retains 40px outside gutters and rounds off the entire page ending.

**Transfer:** End with a short change-oriented invitation appropriate to the new product, then nest the real navigation inside the same continuous terrain. This landscape-and-glass ending is a defining device across page types.

**Text style:** `statement` — Agrandir-0cfc125464d8d15e 700 · 96px/1 · tracking -0.01em

### Numbered process

**Only for:** process explanations

**Observed:** A centered 56px heading with a 720px copy width leads into the Process-grid with 64px separation. Process cards use a number tile, thin rule, small UI moment and bottom-anchored title/description.

**Transfer:** Explain a short workflow through visible input, transformation and useful output rather than abstract benefit icons.

**Text style:** `process-heading` — Agrandir-0cfc125464d8d15e 700 · 56px/1.1 · tracking -0.0114em

### Proof monument

**Only for:** customer-proof pages

**Observed:** A two-line 180px/0.85 declaration with -0.02em tracking towers over a short 24px lead and a three-column quote wall. Rounded white social cards stay much smaller; a muted three-panel ratings row follows.

**Transfer:** Let one big statement establish confidence and use real attributed material beneath it.

**Text style:** `proof-monument` — Agrandir-0cfc125464d8d15e 700 · 180px/0.85 · tracking -0.02em

### Culture chapters

**Only for:** culture and recruiting pages

**Observed:** A white 64px statement over localized grainy artwork introduces wide white 20px-radius carousel panels. Each panel pairs a small position counter, bold 64px title and 24px supporting paragraph with pale oversized illustration. Dark square previous/next controls sit above. A compact three-column benefits grid follows, and the Isolated atmospheric monument provides a separate final invitation before the shared closing scene.

**Transfer:** Use for editorial principles or a people-led narrative; keep this carousel treatment out of ordinary capability directories.

### Pricing comparison

**Only for:** pricing pages

**Observed:** Centered 96px title and 24px lead above a glass billing selector and three Plan panels on rolling terrain. A large comparison introduction precedes a sticky tier-label strip and stacked Comparison groups with aligned allowances. Compact plan summaries repeat the purchase choices after the table; Trust illustration band and two-column FAQ question panels resolve final concerns.

**Transfer:** Maintain clear row alignment and tier identity across the long comparison, while separating persuasive art from dense purchasing detail.

## Page flow

**Storyline:** clear promise → tangible product or human proof → focused capability or value chapters → useful detail and reassurance → monumental closing invitation with embedded directory

### Broad product marketing

1. **promise and product demonstration** — Centered white headline and large working interface over a rounded landscape.
2. **benefit statement** — Oversized colored text creates a standalone pause.
3. **capability chapters** — Alternating art wells and concise task-oriented copy.
4. **functional depth** — Open illustrated feature matrix followed by linked capability cards.
5. **closing call** — Monumental invitation and glass directory inside continuous terrain.

**Transfer:** Move between immersive proof and calm practical explanation; adapt the number of chapters to the product.

### Customer confidence and advocacy

1. **human proof** — Left title paired with three descending portrait story cards.
2. **social proof** — Grainy colored partner-logo ribbon.
3. **community validation** — Oversized declaration above compact social quotes.
4. **independent reassurance** — Three muted review panels with stars.
5. **closing call** — Shared landscape invitation and embedded directory.

**Transfer:** Combine recognizable people, organizations and attributed validation without making every proof item equally loud.

### People and culture recruitment

1. **invitation** — Left-aligned promise beside interlocking photo diamonds.
2. **principles** — Atmospheric heading and oversized editorial carousel.
3. **practical value** — Small white benefit cards in three columns.
4. **participation status** — An isolated fading landscape carries monumental white text and concise availability information.
5. **closing call** — Shared landscape invitation and directory.

**Transfer:** Balance candid people imagery with concrete working conditions and a clear current participation path.

### Focused capability landing

1. **promise and demonstration** — Compact centered headline with a full working interface on terrain.
2. **process explanation** — Three numbered, illustrated steps.
3. **capability breadth** — Four compact interface vignettes and a conversion action.
4. **objection handling** — Two-column question panels.
5. **adjacent discovery** — Capability directory followed by paired promotional panels, one landscape-backed and one white.
6. **closing call** — Shared terrain invitation and glass directory.

**Transfer:** Begin with the actual output, show how little effort creates it, then offer adjacent paths without competing with the main task.

### Plan selection and detailed evaluation

1. **pricing choice** — Centered title and billing control over three translucent plan cards.
2. **detailed comparison** — Monumental introduction followed by sticky tier labels and grouped ruled feature tables.
3. **decision recap** — Compact prices and actions repeat below the comparison.
4. **risk reduction** — Colorful assurance band followed by practical FAQs.
5. **closing call** — Shared terrain invitation and glass directory.

**Transfer:** Make the top choices easy to scan and let detailed evaluators continue into disciplined tables; preserve the expressive bookend.

## Writing

Warm, assured and product-literate. Concrete verbs and useful outcomes do most of the persuasion; occasional expansive lines add optimism without turning the whole page into hype.

**Do not copy:** Do not reuse the brand name, logo, proprietary artwork, customer identities or quotes, partner marks, plan prices, allowances, employment benefits, certifications or unsupported product claims. Source examples illustrate tone only.

- **Addressing the reader:** Use you and your for the user's work, imperatives for actions, and we for culture and organizational commitments. Name the product only where it clarifies the sentence.
- **Rhythm:** Headlines are usually short, composed noun phrases or direct outcomes. Support often uses one or two compact sentences; a three-sentence opening can connect distinct tasks. Keep labels brief and FAQs literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the tool category and the people or outcome it serves. | 5–10 words | “The whiteboard for product builders”<br>“Free AI wireframe generator” |
| Section statement | Confident benefit phrased in everyday language, with a small turn of phrase. | 4–12 words | “The essentials, done right”<br>“Everything you need to ship faster” |
| Supporting copy | Start with a concrete verb, then connect the capability to a practical outcome. | One or two short sentences | “Explore new product ideas and iterate quickly to ship the right solution on your first release, not the third.” |
| Primary action | Direct verb plus a clear destination or low-friction qualifier. | 2–5 words | “Get started free”<br>“Generate a wireframe”<br>“View all openings” |
| Process title | Short imperative with no technical preamble. | 1–3 words | “Describe it”<br>“Refine” |
| Closing invitation | One simple statement about changing how work feels. | 5–9 words | “It’s time to work differently.” |

**Words and phrasing to use:** organize; share; shape; build; refine; flow; ideas; shared understanding; in seconds; make it yours

**Avoid:** revolutionary platform; unleash limitless potential; enterprise-grade synergy; disrupt everything; best ever

**Rules:**

- Pair each broad promise with a visible task or concrete example.
- Use sentence case for headings and controls; reserve capitals for tiny directory or plan labels.
- Describe speed through fewer steps or quicker outcomes rather than piling on superlatives.
- Answer practical questions directly before adding qualifications.

## Do's and Don'ts

### Do

- Keep the default opening at 64px/1.1 and limit its heading to 680px for a confident two-line shape.
- Maintain 40px outer gutters around the immersive bookends.
- Give the primary conversion its 48px height, 12px corners and contrasting arrow tile.
- Use 16px/1.4 medium body text so the oversized scenes remain easy to read.
- Let feature artwork fade into the canvas while capability directories retain white 16px-radius cards.
- Keep 20px gutters through directory and purchasing grids.
- Finish with a 96px closing line and a translucent directory inside the same landscape.

### Don't

- Do not replace aubergine typography with neutral black; the plum cast connects the interface to the artwork.
- Do not use pill buttons as the default; 12px rounded rectangles are the control language.
- Do not fill every middle section with saturated purple; reserve broad chromatic coverage for terrain and selected proof treatments.
- Do not render all display type with Manrope; the broad display face and compact body face have different jobs.
- Do not give every illustrated feature a pronounced card shadow; the open matrix relies on fading edges and almost invisible divisions.
- Do not round comparison tables to 80px; their practical panels use 20px corners.
- Do not make tiny footer group labels the same size as body copy; their 9px uppercase treatment is deliberately subordinate.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions include background-color .1s and box-shadow .2s cubic-bezier(.3, .1, 0, 1).
- Declared exploration-link color transitions use .2s cubic-bezier(.3, .1, 0, 1); landscape-filled chapter headings transition background-position over 1.2s with the same curve.
- Logo/graphic streams declare 140s linear infinite animation; one background declares an 18s ease infinite reversing animation.

**Transfer:**

- Use subtle color and shadow changes on compact controls rather than making them bounce.
- Let terrain and clipped headline art drift slowly while foreground copy and the working interface remain visually stable.

**Unknown:**

- Actual motion playback, scroll choreography and interaction-state colors are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 375px, 479px, 720px, 860px, 992px, 1100px, 1280px and 1440px.
- The largest social-proof heading uses min(180px, 13vw).

**Transfer:**

- On narrow layouts, preserve the centered copy-over-terrain relationship and show a meaningful portion of the interface rather than shrinking it to illegibility.
- Stack alternating chapters, numbered cards and purchasing choices while keeping the terrain behind their associated content.
- Reduce the four-column footer to a compact multi-row directory while retaining the surrounding continuous landscape.

**Unknown:**

- Exact mobile typography, gutter sizes, menu mechanics and table overflow behavior are not established; these transfers are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
