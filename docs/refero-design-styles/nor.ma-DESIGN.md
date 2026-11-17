# nor.ma — material rituals, digital restraint

## Overview

An airy, object-led style that makes a digital tool feel like a considered piece of furniture. White and pale grey editorial space alternates with charcoal photographic stages, using a compact Swiss grotesk and softly rounded controls. Reflective metal, lived-in interiors and direct interface demonstrations supply the character; the writing is practical, short and reassuring. It suits premium tools whose value can be explained through a tangible action rather than a wall of features.

### Essentials

- The promise and its mechanism share one cinematic stage: a 1408×756px rounded media panel inside 16px outer margins, with a 56px/1.02 semibold two-line headline on the left and explanation plus compact actions on the right.
- Headlines distinguish setup from payoff through opacity, not a second font: 56px with -0.03em tracking, first line white at 55% and second line solid white; recurring section headings are 36px/1.1 at weight 600.
- Controls look like small polished capsules: 9999px radii, 36px opening actions with 14px medium labels, and 48px conversion actions with 16px semibold labels. Dark scenes use white primary actions and translucent outlined alternatives.
- The page shell is almost entirely achromatic: white, #f5f5f5, #111111 and #0a0a0a, with chromatic color confined to real media, interface demonstrations and one tiny blue light in the sculptural scene; never use a colored section fill.
- Materials do the emotional work: include a tightly framed material close-up and a softly lit lived-in context scene, framed at 28px radius. Without physical hardware, use tactile tools or environments associated with the product alongside a faithful interface demonstration.
- Proof becomes an object on the stage: 44px tabular numerals sit in 234×149px frosted tiles with 24px padding and 12px blur; review quotes form a single floating white tray rather than isolated colorful cards.
- A sculptural dark callout punctuates the practical content: a vast cropped charcoal sphere with faint curved grid lines, a tiny blue-lit marker and a centered 36px/1.05 promise above a white pill. Recreate the geometry in SVG when no 3D artwork is available.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Default canvas, cards and inverse text; also the source of translucent glass layers. |
| Pale grey | `#f5f5f5` | `--color-paper` | background, surface | Feature bands, explanatory panels, small tags and the commerce canvas. |
| Light hairline | `#e7e7e7` | `--color-rule` | border | Visible light-canvas result of ink at 10% alpha; use rgba(10,10,10,0.1) for the actual edge. |
| Muted ink | `#a1a1a1` | `--color-muted` | text | Attribution, light metadata and input prompts. |
| Secondary ink | `#6b6b6b` | `--color-secondary` | text, link | Supporting prose and inactive navigation on light backgrounds. |
| Sculpture charcoal | `#2b2b2b` | `--color-sculpture` | surface | Visual target for the oversized curved sculptural form; match the subdued charcoal tone rather than adding a glossy gradient. |
| Coal | `#111111` | `--color-coal` | background, surface | Dark capability bands and the highlighted comparison column. |
| Ink | `#0a0a0a` | `--color-ink` | text, action, border | Primary text, selected controls and dark conversion buttons. |
| Stage black | `#000000` | `--color-black` | background | Negative space around the sculptural closing artwork. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Device charcoal | `#1a1a1a` | `--color-device` | surface | Backing behind framed device demonstrations, not a replacement for the main dark section color. |
| sculptural callouts | Marker blue | `#4285ed` | `--color-light-blue` | accent | Tiny circular light and its soft beam within the sculptural artwork only; keep it well below 1% of the panel area. |

## Typography

- **suisse** — All marketing text, headings, labels and numerals. Compact Swiss grotesk with open counters, medium-to-semibold emphasis and little ornamental contrast. OpenType features: "cv01", "cv11", "ss01". If unavailable, use **Inter**. Use weights 400–600 with the same tracking; preserve compact line breaks. Font stack: "suisse", "Inter", "suisse Fallback", ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | suisse | 600 | 56px | 1.02 | -0.03em | fixed | Two-part headline over the opening media stage. |
| stat | suisse | 600 | 44px | 1 | -0.04em, features "lnum", "tnum" | size clamp(1.875rem, 1.1rem + 2.1vw, 2.75rem) | Large numerals on the photographic proof stage. |
| heading | suisse | 600 | 36px | 1.1 | -0.015em | fixed | Default section heading and commerce opening title. |
| closing-heading | suisse | 600 | 36px | 1.05 | -0.015em | fixed | Compact centered promise on the sculptural stage and image-led conversion panels. |
| card-heading | suisse | 600 | 22px | 1.5 | normal | fixed | Numbered explanatory cards. |
| body | suisse | 400 | 17px | 1.5 | normal | fixed | Default supporting paragraphs. |
| emphasis-body | suisse | 500 | 17px | 1.5 | normal | fixed | Opening explanation and FAQ question labels. |
| quote | suisse | 400 | 17px | 1.4 | normal | fixed | Customer quotes inside the floating review tray. |
| action | suisse | 600 | 16px | 1.5 | normal | fixed | Main conversion button labels. |
| small-body | suisse | 400 | 15px | 1.45 | normal | fixed | Short explanatory card descriptions. |
| control | suisse | 500 | 14px | 1.5 | normal | fixed | Navigation, feature tabs, opening actions and compact signup action. |
| small-link | suisse | 400 | 14px | 1.5 | normal | fixed | Footer links and secondary text links. |
| caption | suisse | 400 | 13px | 1.5 | normal | fixed | Attribution and subdued metadata. |
| step-number | suisse | 600 | 13px | 1.5 | normal, features "lnum", "tnum" | fixed | Small circled index in explanatory cards. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| software landing pages | software-display | suisse | 600 | 56px | 1.04 | -0.03em | fixed | Left-aligned text-first opening for a companion software product. |
| software landing pages | dark-feature-heading | suisse | 600 | 22px | 1.5 | -0.01em | fixed | Capability headings and compact software conversion band title. |
| software landing pages | feature-body | suisse | 400 | 16px | 1.5 | normal | fixed | Dark capability descriptions and compact conversion-band support. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The family stays constant across editorial and functional roles; hierarchy comes from scale and weight rather than serif or mono contrast.
- Display tracking tightens to -0.03em, recurring headings relax to -0.015em, and body copy remains untracked.
- Use sentence case and compact balanced headline wraps, usually with a period. Do not turn small section headings into uppercase eyebrows.
- Tabular lining numerals belong to statistics and indexes, not all prose.

## Layout

**Density:** Airy at section scale, compact inside controls; a narrow editorial column sits within much wider media panels.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-label gaps and close caption spacing. |
| 8px | Wrapping feature-control gaps. |
| 12px | Opening action gaps and statistic-grid gaps. |
| 16px | Outer media inset, heading-support gap and paired-card gap. |
| 20px | Three-card grid gap. |
| 24px | Stat tile padding and support-to-action spacing. |
| 28px | Numbered-card text padding. |
| 32px | Desktop container side padding and review-cell padding. |
| 48px | Heading groups to demonstrations, FAQ groups and editorial grids. |
| 56px | Explanatory split-panel padding and footer legal-row separation. |
| 64px | Default section padding and spacious grid separation. |
| 80px | Footer top and bottom padding. |
| 96px | Dark capability band padding and larger feature introductions. |
| 128px | Major instructional chapter padding and text-first opening top clearance. |

### Containers and grids

- **Editorial container**: max width 1040px · side padding 32px. Centered desktop wrapper yielding 976px of content at 1440px; align headings, tables, FAQ and footer to its edges.
- **Media container**: max width 1920px · side padding 16px. Near-full-width cinematic bands; 1408px visible content at 1440px.
- **Instruction grid**: 3 columns · gap 20px. Equal 312px-wide explanatory cards inside the editorial container.
- **Paired argument**: 2 columns · gap 16px. Equal 480px text and photographic panels with matched 600px height.
- **Statistic grid**: max width 480px · 2 columns · gap 12px. Four short metrics grouped on the right of a photographic panel.
- **Software capability grid** (only for software landing pages): 3 columns · gap 40px. Two rows of icon-led capabilities inside a wide dark band.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Controls | 9999px (pill) |
|  | Media panels | 28px |
|  | Instruction cards | 36px |
|  | FAQ and stat tiles | 16px |
|  | Review tray | 24px |
|  | Review stage | 32px |
| commerce pages | Commerce options | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Floating review tray | `0px 24px 60px -24px rgba(0,0,0,0.3)` | Lifts a unified white review tray above a material close-up; keep ordinary instructional cards flat. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and card base.

**CSS:** `background: #ffffff; color: #0a0a0a`

**Observed:** Broad clear margins separate functional chapters.

**Transfer:** Let white space carry the rhythm instead of outlining every section.

#### Pale material panel · level 0

**Use:** Explanatory splits and feature chapters.

**CSS:** `background: #f5f5f5; border-radius: 28px`

**Observed:** Can join adjacent sections through a shared pale backing; some joined bands round only their outer ends.

**Transfer:** Use for calm instructional material between photographic stages.

#### Dark stage · level 0

**Use:** Photography, sculptural art or focused capability content.

**CSS:** `background: #111111; color: #ffffff; border-radius: 28px; overflow: hidden`

**Observed:** Nearly full-bleed within the outer inset, while text stays aligned to the editorial container.

**Transfer:** Keep dark panels discrete rather than turning the whole site dark.

#### Hairline card · level 1

**Use:** Instructional content and grouped information.

**CSS:** `background: #ffffff; border: 1px solid rgba(10,10,10,0.1); border-radius: 36px; overflow: hidden`

**Observed:** Light borders define objects without general-purpose shadows.

**Transfer:** Reserve the deepest corners for large explanatory cards.

#### Frosted proof glass · level 1

**Use:** Numeric proof layered over darkened photography.

**CSS:** `background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.15); border-radius: 16px; backdrop-filter: blur(12px)`

**Observed:** Photography remains visible through the tile; the blur is local, not a blur of the whole stage.

**Transfer:** Place over detailed low-saturation imagery so the glass has material to refract.

## Components

### Floating navigation

**Use:** Persistent wayfinding over both media and white sections.

**CSS:** `display: flex; align-items: center; height: 40px; padding: 4px; border-radius: 9999px; background: rgba(255,255,255,0.343039); backdrop-filter: blur(24px)`

**Text style:** `control` — suisse 500 · 14px/1.5

**Observed:** Three separated islands: wordmark on the left, centered icon-and-label navigation, locale plus order at right. The header follows the editorial alignment and stays fixed. Over light content, islands become white at 80% alpha with a faint ink edge and dark labels.

**Transfer:** Keep branding, navigation and conversion visually separate rather than enclosing them in a solid full-width bar.

### Primary button

**Use:** Default conversion action on light surfaces.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 10px; height: 48px; padding: 0px 28px; border-radius: 9999px; background: #0a0a0a; color: #ffffff`

**Text style:** `action` — suisse 600 · 16px/1.5

**Observed:** A small right arrow follows the label. In dark photographic and sculptural panels, the primary button reverses to white with ink text; a split explanatory card uses the full available text-column width.

**States:** Declared: hover background-color color-mix(in oklab, #0a0a0a 90%, transparent); active scale 0.99.

**Transfer:** Use a direct transaction or activation verb.

### Compact stage action

**Use:** Primary action in the opening media composition.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 16px; border-radius: 9999px; background: #ffffff; color: #0a0a0a`

**Text style:** `control` — suisse 500 · 14px/1.5

**Observed:** Sits beneath the right-hand explanation beside a translucent secondary control; smaller than lower-page conversion buttons.

**States:** Declared: hover background-color color-mix(in oklab, #fff 90%, transparent).

### Glass secondary button

**Use:** Supporting action on photographic panels.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 16px; background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.3); border-radius: 9999px; color: #ffffff; backdrop-filter: blur(12px)`

**Text style:** `control` — suisse 500 · 14px/1.5

**Observed:** Opening version is compact; lower photographic stages use a 48px-high version with 24px horizontal padding and the action recipe.

**States:** Declared: hover background-color color-mix(in oklab, #fff 20%, transparent).

### Instruction card

**Use:** Explain a short concrete sequence.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid rgba(10,10,10,0.1); border-radius: 36px; overflow: hidden`

**Text style:** `card-heading` — suisse 600 · 22px/1.5

**Observed:** A 28px circled index precedes a title and short small-body description in a 28px padded top compartment. A hairline separates it from a 310×239px image compartment. Three equal cards form one row.

**Transfer:** Show a different action in each image, not three decorative variations.

### Stat tile

**Use:** Compact quantified proof over photography.

**CSS:** `padding: 24px; background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.15); border-radius: 16px; backdrop-filter: blur(12px); color: #ffffff`

**Text style:** `stat` — suisse 600 · 44px/1 · tracking -0.04em

**Observed:** Numeral first, compact metric name beneath, then a quieter frequency or qualifier. Four tiles make a 2×2 group separate from the left-hand heading.

**Transfer:** Use few credible metrics with short labels; keep qualifiers visually subordinate.

### Review tray

**Use:** Social proof over a close-up material backdrop.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); height: 268px; background: #ffffff; border: 1px solid rgba(10,10,10,0.1); border-radius: 24px; overflow: hidden; box-shadow: 0px 24px 60px -24px rgba(0,0,0,0.3)`

**Text style:** `quote` — suisse 400 · 17px/1.4

**Observed:** Three cells share a single tray; each has stars, a quote, then bottom-aligned name and verified-buyer tag. Vertical rules divide cells. Tray is inset 56px from the 976px stage edges and placed near its bottom.

**Transfer:** Keep quote lengths varied but align attribution baselines.

### Feature pills

**Use:** Switch a product demonstration between capabilities.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; padding: 8px 16px; border: 1px solid #0a0a0a; background: #0a0a0a; color: #ffffff; border-radius: 9999px`

**Text style:** `control` — suisse 500 · 14px/1.5

**Observed:** The selected pill is dark; inactive pills are white with a faint edge and secondary ink. A small outline icon precedes each label. Controls wrap with 8px gaps, above a separate text explanation.

**Transfer:** Keep this a product explainer rather than a general navigation pattern.

### FAQ row

**Use:** Resolve functional and purchase objections.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 20px 32px; background: #ffffff`

**Text style:** `emphasis-body` — suisse 500 · 17px/1.5

**Observed:** A muted 21px pictogram and question sit on the left; an 18px fine-stroke plus sits at right. Rows are about 67px high including separators, enclosed in one 16px-radius hairline group.

**Transfer:** Use a compact list of real objections rather than marketing slogans.

### Footer link

**Use:** Grouped secondary navigation.

**CSS:** `color: #6b6b6b`

**Text style:** `small-link` — suisse 400 · 14px/1.5

**Observed:** Four narrow link columns sit beside a broader brand-and-signup column. Small semibold group labels precede regular links, with 10px list spacing.

**States:** Declared: hover color #0a0a0a.

### Capsule signup

**Use:** Small subscription form in the footer.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 6px 6px 6px 20px; max-width: 384px; border: 1px solid rgba(10,10,10,0.1); border-radius: 9999px`

**Text style:** `control` — suisse 500 · 14px/1.5

**Observed:** An unboxed email input occupies the left; a compact dark 36px pill is embedded at right. A separate locale selector sits below, not inside the form.

**Transfer:** Keep signup subordinate to purchase; the footer remains a utility surface.

### Selected purchase option

**Only for:** commerce pages

**Use:** Choose a quantity or package before checkout.

**CSS:** `position: relative; padding: 16px 20px; border: 1px solid #0a0a0a; border-radius: 20px; background: rgba(10,10,10,0.03); box-shadow: 0px 0px 0px 1px #0a0a0a`

**Text style:** `emphasis-body` — suisse 500 · 17px/1.5

**Observed:** Quantity is left-aligned, price and circular check right-aligned. Unselected alternatives use the faint edge, with savings and shipping as smaller secondary lines. A 28px-radius white purchase panel contains the option stack and a 56px-high checkout button.

**Transfer:** Distinguish selected state by edge and check, not a saturated fill.

## Imagery and graphics

### Macro material cinema

**Use:** Opening stage, review backdrop and product punctuation.

**Observed:** Extreme close-ups of reflective steel and a clock face create silver, grey and almost-black planes; oversized details run beyond the frame. The moving opening is a background rather than a separate object card, with a dark top wash protecting the headline. Review art shows brushed concentric metal, cropped heavily to the right.

**Transfer:** Photograph the new product's defining surface at macro scale with broad soft reflections. For software, use a tactile related tool or workspace detail rather than a generic abstract gradient.

**Build:** Use a full-cover image or video inside the 28px media mask; overlay a vertical black alpha wash from 0.55 at the top through 0.25 at the midpoint to transparent at the bottom. Keep the subject oversized and the text in an independent foreground layer.

### Lived-in editorial stills

**Use:** Explanatory split panels, contextual carousel and photographic conversion stage.

**Observed:** Natural rooms with stainless tables, ceramics, books, dark glass, warm wood, a lamp and a cat. The object is small and plausibly placed, not dramatically spotlighted. Soft daylight and restrained saturation retain beige, brown and grey tones. Split-panel photographs are portrait 480×600px; carousel images are 340×425px with short captions below.

**Transfer:** Show believable environments and incidental possessions associated with the new product. Avoid empty showroom staging; keep the product discoverable rather than filling the frame.

### Context label glass

**Use:** Labels centered on the contextual carousel imagery.

**Observed:** A 37px-high white-translucent capsule contains a 15px semibold use-case label and a smaller darker count capsule. The glass sits near the visual center rather than as a bottom caption; explanatory prose remains below the photo.

**Transfer:** Name a real situation and attach a short relevant qualifier.

**Build:** Place an absolutely centered pill over each portrait image with rgba(255,255,255,0.15) fill, rgba(255,255,255,0.25) 1px border, blur(12px), and padding 6px 6px 6px 16px. Nest the qualifier in a smaller rgba(0,0,0,0.35) pill.

### Device demonstrations

**Use:** Instruction cards and companion-product explanation.

**Observed:** Real interface sequences are shown in carefully masked phone shapes and desktop windows, with actual screen colors retained. In the paired demonstration the desktop occupies about three quarters of the row, the phone about one fifth, and their bottom edges align. The phone floats without an oversized hardware bezel.

**Transfer:** Use a readable faithful demonstration of the new workflow. Keep screenshots about actions, and do not export interface colors into the marketing palette.

### Orbital sculpture

**Use:** Signature dark promise callout.

**Observed:** A huge charcoal globe-like surface dominates a black stage. Faint meridians and shallow curved latitude lines reveal volume. A small silver-rimmed blue marker above and left of the centered copy casts a diffuse triangular blue beam diagonally down-left. The globe is cropped by the upper and side boundaries, with its lower arc visible against black.

**Transfer:** Retain the contrast between immense curved geometry and one tiny activated point. The point can represent an action or state for any product; the centered promise stays independent of the art.

**Build:** Create an SVG clipped to a 1408×702px rounded stage. On black, draw a charcoal ellipse wider than the stage with its center above the visible midpoint and lower arc inside the frame. Clip several thin curved longitude and latitude paths to the ellipse, using rgba(255,255,255,0.04) strokes. Add a roughly 70px pale ring with a roughly 40px blue inner circle above-left of the copy; behind it draw a widening triangular blue beam at 20% alpha with 12px blur, pointing down-left. Match the soft volume and faint grid; exact shading stops are not essential.

### Icons

**Observed:** Small neutral SVG pictograms, mostly 15–22px with round caps and 1.4–2.2px strokes. Navigation uses tiny icons before labels; FAQ uses muted category icons and fine plus signs. Checkmarks are firmer than the surrounding line work.

**Transfer:** Choose compact rounded outline icons with consistent optical weight; use solid fills for stars, checks and small status dots only.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A 1408×756px media stage inside 16px top and side insets rounds at 28px. Back to front: tightly framed macro video, a top-heavy black wash, fixed Floating navigation, and the editorial copy layer. Within the 976px content width, the headline takes a little over half the row and the explanation takes the remaining right-hand column, separated by 32px. An understated shipping capsule sits above the left headline; the row starts well below navigation. Display text is 56px/1.02 with -0.03em tracking: setup in white at 55%, payoff solid white on the next line. Right-hand copy is 17px medium, with Compact stage action and Glass secondary button 24px beneath it. A centered translucent stock-status capsule sits near the media bottom. All text, both actions, the macro scene and status are visible in the first 900px; the next pale trust strip starts below the stage and shows its heading near the fold, with logo detail continuing below.

**Transfer:** Lead with a visual material or mechanism belonging to the new product. If no video exists, use a strong still macro composition with the same dark wash and split copy hierarchy. Commerce pages instead open with a 36px title on pale grey above two white purchase panels; software landing pages open with the software-display recipe on white, support and two actions above a paired device demonstration.

**Avoid:** Do not replace the stage with a centered giant headline above a dashboard, a full black page, or a detached product render on a blank gradient.

**Text style:** `display` — suisse 600 · 56px/1.02 · tracking -0.03em

### Heading and support

**Observed:** Left-aligned heading at 36px/1.1, followed by 17px/1.5 secondary ink prose with a 16px gap; copy is kept to a readable short measure. Major content follows 48px or 64px below rather than immediately touching the support.

**Transfer:** Use headings that name an outcome or answer a question, with a brief practical explanation.

**Text style:** `heading` — suisse 600 · 36px/1.1 · tracking -0.015em

### Tactile split argument

**Observed:** Paired argument layout: a Pale material panel with 56px internal padding beside an equally tall portrait interior photo. Heading and explanation sit at the top; a full-width Primary button anchors the bottom.

**Transfer:** Use one strong reason to believe, paired with a credible real-world scene rather than a collage.

### Numbered workflow

**Observed:** Heading and support precede the Instruction grid by 64px. Three Instruction cards share equal height and bottom image compartments. A short centered alternatives line and Primary button can follow beneath the row.

**Transfer:** Explain a simple workflow through setup, action and visible result without forcing every product into the same number of steps.

### Interactive capability chapter

**Observed:** A near-full-width Pale material panel holds heading and wrapping Feature pills on the left, then a low-positioned explanatory heading and paragraph. A 280×607px phone demonstration occupies the right, separated by 64px.

**Transfer:** Make each control reveal one concrete behavior with its own short explanation; maintain the asymmetry between broad text and slender device.

### Photographic numeric proof

**Observed:** Dark stage with a cover interior photograph and a left-to-right black wash: strongest behind the left title, lighter over the right. Heading sits upper left, a 480px Stat tile group upper right, and paired white primary plus glass secondary actions lower left. The frame is 756px tall at desktop.

**Transfer:** Use evidence directly related to the product's problem or benefit, with enough image space between the data and actions.

### Highlighted comparison column

**Observed:** A 976px-wide hairline rounded table has a pale header and mostly white rows about 56px tall. The featured product occupies one continuous #111111 column, including header, checks, material and price; other columns use faint negative marks. A centered Primary button follows.

**Transfer:** Compare meaningful decision criteria and let the continuous dark column guide the eye rather than coloring individual checkmarks.

### Material-backed reviews

**Observed:** A 976×610px stage with 32px corners contains a cropped metal close-up, rating and heading at upper left, then Review tray across the lower portion. Review action is a small white capsule.

**Transfer:** Combine emotional material photography with compact genuine testimony; retain a shared tray rather than separate testimonial cards.

### Context carousel

**Observed:** Heading and support align left, with two 44px circular arrow controls right. Portrait context photos start 48px below, at 340×425px with 16px gaps. The rail extends beyond the editorial edge so the next card is partially visible. Context label glass sits on each photo and a short secondary-ink caption below it.

**Transfer:** Show distinct situations where the product belongs, with natural variation in light and furnishings.

### Product interlude

**Observed:** A full-width 1440×900px product video uses an expansive white field and a floating reflective object, with a simple 36px order heading and Primary button as conversion companions.

**Transfer:** Use a brief clean product-motion or still-life interlude to separate dense explanations, without turning its breathing space into an empty content section.

### Sculptural promise

**Observed:** A 1408×702px Dark stage contains Orbital sculpture. A centered closing-heading is constrained to about 382px and followed by an inverse Primary button. The enormous curved form and tiny light surround the copy without competing with it.

**Transfer:** Use a compact reassurance or commercial promise, not another feature list; preserve the sculpture wherever this punctuation best fits the new narrative.

**Text style:** `closing-heading` — suisse 600 · 36px/1.05 · tracking -0.015em

### Questions and utility ending

**Observed:** A 36px heading precedes a unified FAQ group by 48px. The ending returns to White canvas: 80px vertical footer padding, a brand summary and Capsule signup on the left, four Footer link columns to the right, and a separate legal row 56px lower with 24px top padding above a hairline. Locale control sits below the form.

**Transfer:** End with practical answers and uncluttered navigation, even when the preceding callout is cinematic.

### Editorial bridge

**Only for:** content-rich marketing pages

**Observed:** A heading/support pair and small read-all link introduce a two-column article area. One feature story uses a 541×338px image with 24px corners, compact category and reading-time capsules, a 22px title and short synopsis; the other column is a stack of four smaller stories with 96px thumbnails and hairline separators.

**Transfer:** Use practical guidance that helps buyers make a decision; keep editorial depth separate from the main conversion message.

### Software capability band

**Only for:** software landing pages

**Observed:** Dark stage with 96px vertical padding and Software capability grid. Each item starts with a 44px outline-icon box at 12px radius, then a 22px title and 16px support. A later interactive chip demonstration is followed by a compact dark conversion band with left-aligned title and two actions at right.

**Transfer:** Answer compatibility and behavior questions with concise functional statements, not decorative feature cards.

## Page flow

**Storyline:** Promise → tangible mechanism → workflow demonstration → proof and differentiation → contextual benefits → objections → reassuring conversion → utility ending.

### Broad product introduction and persuasion

1. **Promise** — Cinematic opening over macro material detail, followed by a pale employer-logo trust strip.
2. **Mechanism** — Tactile split argument and numbered visual workflow explain a concrete action.
3. **Capability chapters** — Interactive feature demonstration, photographic numeric proof and continuous dark-column comparison.
4. **Social proof and context** — Material-backed review tray, contextual portrait carousel and clean product-motion interlude.
5. **Objection handling** — Companion demonstration, FAQ and an editorial bridge provide practical depth.
6. **Closing call** — Orbital sculpture frames a short reassurance and white conversion pill, followed by the shared utility footer.

**Transfer:** Borrow the alternation between tangible imagery, practical explanation and proof, not a fixed section count.

### Focused purchase decision

1. **Purchase configuration** — Pale opening with short title and reassurance, image gallery left and package selector right; delivery and assurance rows follow.
2. **Proof** — Material-backed reviews, numeric photographic stage and comparison table reinforce value.
3. **Conversion** — Large darkened interior photograph carries a lower-left heading and white order pill.
4. **Objection handling and ending** — Purchase FAQ gives way to the shared white signup-and-links footer.

**Transfer:** Keep commerce controls concentrated near the opening; use the richer media panels for confidence rather than distracting from configuration.

### Explain a companion software capability and activate installation

1. **Promise and activation** — Text-first white opening with 56px headline, download and purchase actions, then aligned desktop and phone demonstrations.
2. **Workflow** — Numbered setup cards explain linking, selection and activation.
3. **Capability proof** — Dark icon grid explains behavior; interactive chips let readers try a small selection.
4. **Conversion and objections** — Compact dark action band, focused software FAQ and shared white utility footer.

**Transfer:** Use the text-first opening and software-specific recipes for products whose behavior must be demonstrated on screen; keep the same capsules, editorial width and matter-of-fact voice.

## Writing

Plainspoken and materially specific, with confidence grounded in an action the reader can understand. Warmth comes through everyday circumstances rather than hype or a chatty narrator.

**Do not copy:** Do not reuse Norma's name, logos, product imagery, customer names, employer logos, testimonial quotes, prices, statistics, shipping promises or device-compatibility claims. Examples demonstrate structure only; substitute verified facts and original assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you and your. The product is named when needed, while the company rarely speaks as we.
- **Rhythm:** Short sentence-case headlines, often with a period. Support usually takes one or two compact sentences; paired clauses use repetition to make a mechanism memorable. Actions are terse verbs rather than slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Outcome first, then the small action that makes it possible. | 3–8 words per clause | “Cut your screen time. In one scan.” |
| Supporting explanation | State the setup and repeat the action to explain both directions. | 1–2 short sentences | “Pick your apps once. Scan to block them, scan again to get them back.” |
| Section heading | Name the thing being explained without an ornamental eyebrow. | 2–8 words | “How it works.”<br>“Choose the sites to block.” |
| Instruction | An imperative naming a concrete step. | 2–5 words | “Build a preset”<br>“Link your Mac” |
| Reassurance | Short factual fragments; make cost or prerequisites unambiguous. | 2–3 compact statements | “One payment. No subscription.”<br>“The Mac app is free. You need a Norma disc to scan.” |
| Primary action | Direct transaction or activation verb, with platform only when useful. | 1–4 words | “Order”<br>“Download for Mac” |

**Words and phrasing to use:** once; choose; scan; pick; start; free; your; until; no subscription; set it up

**Avoid:** revolutionary; supercharge; unlock your potential; seamless ecosystem; game-changing; ultimate productivity

**Rules:**

- Describe what the reader does and what visibly happens next.
- Keep the mechanism concrete: name the object, action or interface instead of promising abstract transformation.
- Make purchase and compatibility qualifications visible in supporting prose.
- Use everyday situations for contextual labels; use functional names for feature tabs.
- Reserve expressive language for genuine customer testimony; the brand voice stays factual.

## Do's and Don'ts

### Do

- Keep the default 36px headings semibold with -0.015em tracking.
- Use a 1040px wrapper with 32px side padding for desktop editorial alignment.
- Inset cinematic bands by 16px and clip them with 28px corners.
- Keep 48px conversion capsules distinct from the opening's 36px compact controls.
- Use 12px blur only on localized glass layers and 24px blur on the floating navigation.
- Maintain 20px gaps between equal numbered instruction cards.
- Use a unified 24px-radius review tray with one low diffuse shadow.
- Give major explanations 64px or 128px vertical breathing room rather than enlarging all text.

### Don't

- Do not introduce a saturated brand button color; primary actions stay ink or white.
- Do not make every card 28px radius: instructional cards use 36px and proof tiles use 16px.
- Do not use display tracking on body text; supporting paragraphs remain untracked.
- Do not replace thin neutral separators with thick black card outlines except for the selected commerce option.
- Do not spread broad shadows over every card; elevation belongs mainly to the floating review tray and device staging.
- Do not make the tiny blue marker a recurring link or heading accent.
- Do not turn photographic context into oversaturated studio advertising; keep subdued daylight and real belongings.
- Do not use monospaced counters or a second display font for statistics; use the same grotesk with tabular lining numerals.

## Motion and responsive

### Motion

**Observed:**

- Compact color changes use 0.15s cubic-bezier(.4,0,.2,1). Main conversion buttons declare background-color and transform transitions at 0.2s cubic-bezier(.22,1,.36,1), with active scale 0.99.
- Instruction-card colors transition over 0.3s cubic-bezier(.22,1,.36,1). Review entry declares 0.6s with the same curve; stock rise declares 0.6s after a 0.9s delay.
- Macro video, product movement and interface sequences provide the major motion; the controls themselves remain small.

**Transfer:**

- Keep conversion feedback to the declared subtle scale and neutral color shift.
- Let a material video or concise workflow demonstration carry motion rather than animating every headline.

**Unknown:**

- Exact playback sequences, scroll choreography and all 3D interaction behavior are not established.

### Responsive

**Observed:**

- Styles declare breakpoints at 640px, 768px, 1024px, 1280px and 1536px.
- The instruction grid changes from one column to three at the small breakpoint; the split argument and opening copy become side-by-side at the large breakpoint.
- Container side padding changes from 24px to 32px at the small breakpoint. The center navigation is hidden below the small breakpoint.
- Software capability grids declare one column, then two at the small breakpoint, then three at the large breakpoint.

**Transfer:**

- On narrow widths, preserve headline-before-explanation order over the media and stack the instruction cards without changing their text/image compartment logic.
- Retain a small outer inset and rounded cinematic stage instead of removing its mask.
- Keep a partial next card visible in contextual rails when space permits, rather than squeezing four portraits into one row.

**Unknown:**

- Mobile rendered compositions, exact small-screen type sizes and narrow-header replacement behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
