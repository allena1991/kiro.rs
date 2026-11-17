# Neuralink — the human frontier

## Overview

Human stories and almost clinical engineering share a spare, cinematic frame. Black and white dominate, with warm grainy backdrops, natural documentary color and a narrow pink-to-violet spectrum. Tightly spaced grotesk lettering, restrained pill actions and large photographic or three-dimensional scenes make the experience expansive rather than information-dense. It suits ambitious technical products that need both a tangible explanation and a human reason to exist.

### Essentials

- The promise sits inside lived experience, not above a dashboard: a full-bleed 900px opening scene with a lower-left two-line 48px/1 headline, weight 500 and -0.06em tracking, plus one white 58px pill action.
- Headings feel stretched across a single breath: the default section title is 44px/1, weight 300, -0.06em tracking; the engineering variant grows to 80px/1 without becoming bold.
- Conversion controls are small capsules against enormous scenes: 16px text, 16px 24px padding and 80px radius for primary actions; utility actions compress to 6px 12px padding and 16px radius.
- Color belongs to media and a thin signal strip, not the whole interface: black, white and #f5f5f5 carry the page; a 48px announcement band runs pink through muted blue to violet. Keep that spectral strip as a signature device rather than spreading gradients onto every heading.
- Human proof gets a tactile, warm stage: a centered 612px media-and-quote module on a softly mottled ivory field, with 56px circular arrows and 3px segmented progress marks. Include this intimate proof treatment; use a real process or use-case image if portraits are unavailable.
- The final invitation becomes artwork: paired 322px by 450px, 20px-radius image cards blend people with landscapes, white 32px labels and outlined capsule actions. Preserve the double-exposure or translucent layered-image device using product silhouettes and contextual imagery when people are not appropriate.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal pink | `#e486ab` | `--color-signal-pink` | background, accent | Left edge of the spectral announcement strip. |
| Signal lavender | `#7f80b3` | `--color-signal-lavender` | background, accent | Muted transition at 20% of the announcement strip. |
| Signal blue | `#435a93` | `--color-signal-blue` | background, accent | Center of the announcement strip. |
| Signal violet | `#6452d8` | `--color-signal-violet` | background, accent | Right end of the announcement strip, reaching its final hue at 95%. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-paper` | background, text, action, border | Editorial canvas, reversed type, white primary pills and bright outlines. Navigation also uses white at 0.592 alpha over the scene. |
| Pale gray | `#f5f5f5` | `--color-footer` | background, surface | Footer and light invitation bands; also the broad light panel and filter fields in the recruiting variant. |
| Caption gray | `#bababa` | `--color-muted` | text | Small footer group labels and secondary listing metadata. |
| Navigation gray | `#686868` | `--color-nav-muted` | text, action | Compact outlined navigation action in the overlay treatment; switch contrast with the background. |
| Black | `#000000` | `--color-ink` | text, background, border | Primary text on light ground and the uninterrupted canvas for cinematic engineering chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical detail and recruiting pages | Light rule | `#d9d9d9` | `--color-rule` | border | Fine section separators and listing-card outlines. |
| engineering explainers | Reading gray | `#888888` | `--color-reading-gray` | text | Word-by-word introductory explanation on white. |

## Typography

- **UntitledSans** — All marketing headings, paragraphs, navigation and actions. Low-contrast contemporary grotesk with open forms; light large headings and much tighter spacing than ordinary body text. If unavailable, use **Inter**. Use weights 300, 400 and 500 with the specified tracking; reserve 700 for factual question labels. Font stack: "UntitledSans", "Inter", Arial, sans-serif.
- **SF Mono** (only for recruiting and culture narratives) — Chapter numbers, technical asides and small overlines. Small, widely tracked uppercase monospace, deliberately unlike the tightly spaced headlines. If unavailable, use **Roboto Mono**. Font stack: "SF Mono", "Roboto Mono", Menlo, Consolas, "Liberation Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | UntitledSans | 500 | 48px | 1 | -0.06em | fixed | Default cinematic opening headline; two short left-aligned lines in white. |
| heading | UntitledSans | 300 | 44px | 1 | -0.06em | fixed | Default section headings, centered above media or left-aligned in a split explanation. |
| image-card-title | UntitledSans | 400 | 32px | 1 | -0.0375em | fixed | Two-line audience labels inside the paired closing artwork. |
| body | UntitledSans | 400 | 18px | 1.2 | normal | fixed | Default explanatory paragraphs, usually in a narrow 350px column. |
| navigation | UntitledSans | 400 | 16px | 1.5 | normal | fixed | Header links and standard small interface labels. |
| action | UntitledSans | 400 | 16px | 1.5 | -0.03em | fixed | Main capsules and underlined directional links. |
| utility-action | UntitledSans | 400 | 16px | 1.15 | -0.02em | fixed | Compact navigation and footer pills. |
| footer-link | UntitledSans | 400 | 16px | 1.5 | -0.015em | fixed | Footer link stacks. |
| footer-label | UntitledSans | 400 | 12px | 1.5 | -0.02em | fixed | Muted labels above footer columns. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| recruiting campaigns | monumental-close | UntitledSans | 300 | 128px | 0.92 | -0.06em | size clamp(3.6rem, 10vw, 16rem) | Centered final invitation on black. |
| recruiting campaigns | recruiting-display | UntitledSans | 300 | 120px | 0.92 | -0.06em | size clamp(3.4rem, 9.2vw, 15rem) | Near-full-width sentence anchored to the bottom of the opening film. |
| engineering explainers | engineering-display | UntitledSans | 400 | 88px | 1 | -0.06em | fixed | Centered two-line opening over an isolated three-dimensional object. |
| engineering explainers | chapter-title | UntitledSans | 300 | 80px | 1 | -0.06em | fixed | Main object and part titles on black. |
| information pages and engineering closing invitations | editorial-title | UntitledSans | 300 | 72px | 1.1 | -0.06em | fixed | Factual page title and large split closing headings. |
| recruiting campaigns | campaign-heading | UntitledSans | 300 | 64px | 1 | -0.05em | size clamp(3.4rem, 5.5vw, 8rem) | Progress and culture section titles. |
| recruiting proof sections | stat | UntitledSans | 300 | 64px | 0.9 | -0.06em | size clamp(3.6rem, 5.5vw, 8rem) | Standalone quantities and a short challenge phrase, each followed by a small caption. |
| information pages and product experience sections | explanation-heading | UntitledSans | 400 | 40px | 1.1 | -0.05em | fixed | Mechanism heading or a paragraph-length lead above a demonstration. |
| recruiting directories | listing-heading | UntitledSans | 300 | 36px | 1.05 | -0.05em | size clamp(2.4rem, 3vw, 4.5rem) | Department headings inside translucent sticky accordion bars. |
| information pages | information-lead | UntitledSans | 300 | 30px | 1.35 | -0.05em | fixed | Introductory invitation beneath the page title. |
| information pages | tab | UntitledSans | 400 | 24px | 1.25 | -0.02em | fixed | Geographic or eligibility tabs with an underline on the active item. |
| recruiting campaigns | culture-card-title | UntitledSans | 400 | 22.4px | 1.1 | -0.03em | size clamp(2.2rem, 1.8vw, 2.8rem) | Short titles in a compact row of bordered culture cards. |
| information pages and product experience sections | detail-body | UntitledSans | 400 | 20px | 1.25 | -0.02em | fixed | Readable factual paragraphs and small section leads. |
| information pages | question | UntitledSans | 700 | 20px | 1.25 | -0.02em | fixed | Bold question labels directly above answers. |
| recruiting directories | listing-title | UntitledSans | 400 | 16.8px | 1.18 | -0.02em | size clamp(1.8rem, 1.4vw, 2.1rem) | Position titles in a three-column directory. |
| engineering explainers | chapter-copy | UntitledSans | 400 | 16px | 1.15 | -0.03em | fixed | Short descriptions beneath chapter titles; maximum width 320px. |
| recruiting campaigns | culture-card-body | UntitledSans | 400 | 14.4px | 1.45 | normal | size clamp(1.7rem, 1.2vw, 1.8rem) | Small descriptive paragraphs inside culture cards, white at 0.7 alpha. |
| recruiting directories | listing-meta | UntitledSans | 400 | 12.8px | 1.2 | -0.02em | fixed | Location text below position titles. |
| recruiting and culture narratives | eyebrow | SF Mono | 400 | 12px | 1.5 | 0.2em, uppercase | fixed | Section overlines and numbered disciplines; white at 0.5 alpha on black. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default is a compact 48px cinematic headline, not the 120px recruiting campaign treatment. Light 44px section headings supply most of the hierarchy on ordinary landing pages.
- Large titles use unusually tight -0.05em to -0.06em tracking and little leading. Body text relaxes toward normal tracking; the mono variant reverses this with 0.2em spacing.
- Use sentence case. Uppercase is limited to the small technical overline variant, not navigation or calls to action.

## Layout

**Density:** Airy cinematic sections alternate with compact factual stacks; media has much more area than supporting copy.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 6.4px | Tight title-to-metadata and question-to-answer separation. | fixed |
| 12px | Carousel arrow gap and small label separation. | fixed |
| 16px | Paragraph separation in information sections. | fixed |
| 20px | Directory and campaign-card gutters. | clamp(1.5rem, 2vw, 2.5rem) |
| 24px | Action-to-support spacing and ordinary stack gaps. | fixed |
| 32px | Footer outer padding and media-to-content breathing room. | fixed |
| 40px | Editorial heading-to-lead spacing and split-section gutters. | clamp(3rem, 3vw, 5rem) |
| 46px | Default opening headline-to-action gap. | fixed |
| 64px | Technical and campaign side gutters and major grid gaps. | clamp(2rem, 5vw, 8rem) |
| 70px | Space between the two closing image cards. | fixed |
| 80px | Information section vertical padding. | fixed |
| 115.2px | Directory side gutters. | clamp(2rem, 8vw, 18rem) |
| 120px | White introductory band vertical padding. | fixed |
| 160px | Deep closing invitation top padding. | fixed |
| 240px | Engineering experience section padding and closing invitation bottom space. | fixed |

### Containers and grids

- **split introduction**: max width 1152px · 2 columns · gap 40px · side padding 140px. Centered wrapper with two widely separated 350px text columns; the heading is on the left and two short paragraphs on the right.
- **human proof**: max width 612px · side padding 32px. Centered image, quotation and metadata on a full-width atmospheric field.
- **paired invitations**: max width 960px · 2 columns · gap 70px. Centered pair of 322px-wide portrait cards; empty area around them is part of the composition.
- **editorial column** (only for information pages): max width 1120px · side padding 80px. Outer centered container includes 80px side padding, leaving a 960px reading width.
- **technical close** (only for engineering explainers): 2 columns · gap 128px · side padding 144px. Large heading left, compact support and underlined link right.
- **directory** (only for recruiting directories): 3 columns · gap 20px · side padding 115.2px. Equal-width 390px listing cards at desktop; full-width sticky category bars precede each group.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary capsules | 80px |
|  | utility capsules | 16px |
|  | image cards | 20px |
|  | carousel arrows | 50% |
| recruiting pages | directory and culture cards | 9.6px |
| culture narratives | values panel | 12.8px |
| recruiting resource sections | resource cards | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| recruiting directories | floating directory action | `0px 8px 32px 0px rgba(0, 0, 0, 0.25)` | White floating jump-to-listing capsule; not a general card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Reading bands and information-led sections.

**CSS:** `background: #ffffff; color: #000000`

#### Black stage · level 0

**Use:** Full-bleed films and isolated product scenes.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** An uninterrupted field, not a collection of dark cards.

**Transfer:** Let the silhouette, not a panel edge, define the product scene.

#### Pale utility band · level 0

**Use:** Footer and restrained conversion bands.

**CSS:** `background: #f5f5f5; color: #000000`

#### Spectral strip · level 1

**Use:** Thin announcement above navigation.

**CSS:** `background-image: linear-gradient(90deg, #e486ab, #7f80b3 20%, #435a93 50%, #6452d8 95%); color: #ffffff`

#### Warm atmospheric field · level 0

**Use:** Human proof and closing image invitations.

**CSS:** `background-color: #ffffff`

**Observed:** A warm ivory, almost paper-like image field with low-contrast mottling and fine grain; the invitation variant has a stronger pale yellow-olive wash.

**Transfer:** Use the tactile field recipe in Atmospheric grain; keep local variation faint enough for black type.

#### Values inset · level 1

**Only for:** culture narratives

**Use:** Light explanatory panel interrupting a black story.

**CSS:** `background: #f5f5f5; color: #000000; border-radius: 12.8px; padding: 64px 48px`

**Observed:** Nearly full width with 32px outer gutters; left heading and right vertical list with tiny outline icons and short guide rules.

**Transfer:** Use for a compact set of operating principles or technical criteria, not as a generic feature-card background.

#### Sticky category glass · level 2

**Only for:** recruiting directories

**Use:** Category heading bars above position cards.

**CSS:** `background: rgba(255, 255, 255, 0.72); backdrop-filter: blur(12px); border-top: 1px solid #d9d9d9`

**Observed:** 118px-high bars with large left title and a minimal collapse control at the far right.

**Transfer:** Keep transparency confined to the sticky heading rather than washing out every listing.

## Components

### Navigation

**Use:** Persistent compact header over both cinematic and reading sections.

**CSS:** `display: flex; align-items: center; justify-content: space-between; height: 48px; padding: 0px 12px; background-color: rgba(255, 255, 255, 0.592)`

**Text style:** `navigation` — UntitledSans 400 · 16px/1.5

**Observed:** Small abstract mark at left, three plain links and one outlined utility capsule at right, with 20px link gaps. Type reverses over dark media and becomes black over white content. The announcement adds another header-height row.

**Transfer:** Use a small original product mark, not a giant wordmark; retain the exceptionally slim header.

### Announcement

**Use:** Single linked product announcement at the top.

**CSS:** `height: 48px; padding: 0px 16px; display: flex; align-items: center; justify-content: center; background-image: linear-gradient(90deg, #e486ab, #7f80b3 20%, #435a93 50%, #6452d8 95%); color: #ffffff`

**Text style:** `action` — UntitledSans 400 · 16px/1.5 · tracking -0.03em

**Observed:** Centered underlined sentence with a close control at the far right; no badge or second call to action.

### Primary button

**Use:** Default main action over a photograph or dark scene.

**CSS:** `display: inline-flex; align-items: center; background: #ffffff; color: #000000; border: 1px solid #ffffff; border-radius: 80px; padding: 16px 24px; height: 58px`

**Text style:** `action` — UntitledSans 400 · 16px/1.5 · tracking -0.03em

**Observed:** Label followed by a small northeast arrow; width follows the label rather than filling its column. On white information pages the same construction becomes transparent with a black outline.

**States:** Declared: hover background-color rgba(255, 255, 255, 0.85) for the filled version; background-color rgba(0, 0, 0, 0.05) for the black-outline version.

### Image outline button

**Use:** Actions over the layered closing artwork.

**CSS:** `display: inline-flex; align-items: center; background-color: rgba(255, 255, 255, 0.05); color: #ffffff; border: 1px solid #ffffff; border-radius: 80px; padding: 16px 24px; height: 58px`

**Text style:** `action` — UntitledSans 400 · 16px/1.5 · tracking -0.03em

**Observed:** Same label-and-northeast-arrow construction as Primary button, but the media remains visible through the capsule.

**States:** Declared: hover background-color rgba(255, 255, 255, 0.15).

### Utility button

**Use:** Small footer and header actions.

**CSS:** `border: 1px solid #000000; border-radius: 16px; padding: 6px 12px; color: #000000`

**Text style:** `utility-action` — UntitledSans 400 · 16px/1.15 · tracking -0.02em

**Observed:** Footer version is approximately 32px high; header version is 35px high and reverses its outline on dark scenes. These do not replace the larger primary capsules.

**States:** Declared: hover background-color #000000 and color #ffffff on the light version; background-color #ffffff and color #000000 on the reversed header version.

### Directional text link

**Use:** Editorial back links and compact section exits.

**CSS:** `color: #000000; text-decoration: underline; display: inline-flex; align-items: center`

**Text style:** `action` — UntitledSans 400 · 16px/1.5 · tracking -0.03em

**Observed:** Back navigation has a left arrow before the label; onward links use a small northeast arrow after it. Engineering chapters use a white underlined skip link near the bottom edge.

### Audience image card

**Use:** Two visually rich closing destinations.

**CSS:** `position: relative; width: 322px; height: 450px; border-radius: 20px; overflow: hidden`

**Text style:** `image-card-title` — UntitledSans 400 · 32px/1 · tracking -0.0375em

**Observed:** Full-card layered portrait artwork, title and Image outline button gathered near the lower edge. No separate white text panel; use the artwork's darker lower portion for legibility.

**States:** Declared: hover transform scale(1.01) and box-shadow 0px 0px 28px 5px rgba(0, 0, 0, 0.08).

**Transfer:** Change the audiences to two genuine pathways into the product; the visual distinction should come from imagery, not unrelated card colors.

### Carousel arrow

**Use:** Human proof carousel navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 56px; height: 56px; border: 1px solid #000000; border-radius: 50%; padding: 1px 6px; color: #000000`

**Observed:** Two circles sit beside the quote area, 12px apart, using simple 16px line arrows. A separate segmented progress rail sits beneath the metadata.

**States:** Declared: hover background-color #000000.

### Footer

**Use:** Shared utility ending after the final narrative section.

**CSS:** `background: #f5f5f5; color: #000000; display: flex; flex-direction: column; padding: 32px; min-height: 527px`

**Text style:** `footer-link` — UntitledSans 400 · 16px/1.5 · tracking -0.015em

**Observed:** Three compact link groups at upper left, muted Footer-label headings, a Utility button at upper right, then a broad empty field. Small mark bottom left and copyright bottom right finish the composition. Link stacks use 1.6px row gaps and the upper grid uses 64px gutters.

**Transfer:** Keep the ending infrastructural and spacious; do not turn it into another sales hero.

### Listing card

**Only for:** recruiting directories

**Use:** Clickable position or opportunity summary.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 24px; padding: 22.4px; border: 1px solid #d9d9d9; border-radius: 9.6px; min-height: 130px`

**Text style:** `listing-title` — UntitledSans 400 · 16.8px/1.18 · tracking -0.02em

**Observed:** Title then smaller muted location with 6.4px separation; small northeast arrow at the lower right. Long titles can extend the card to 150px high.

**States:** Declared: hover background-color #000000, border-color #000000, color #ffffff and transform translateY(-4.8px).

### Culture card

**Only for:** recruiting campaigns

**Use:** Compact row of reasons to join or principles of work.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 28px 24px; border: 1px solid rgba(255, 255, 255, 0.15); border-radius: 9.6px`

**Text style:** `culture-card-title` — UntitledSans 400 · 22.4px/1.1 · tracking -0.03em

**Observed:** Five equal cards in one desktop row, using Culture-card-body for the short paragraph; the black stage continues through them rather than giving each a filled background.

### Information tab

**Only for:** information pages

**Use:** Switch between geographic or eligibility detail sets.

**CSS:** `border-bottom: 2px solid #000000; padding: 4px 0px; color: #000000; height: 40px`

**Text style:** `tab` — UntitledSans 400 · 24px/1.25 · tracking -0.02em

**Observed:** Only the active tab has the rule. Tabs are plain text, 32px apart, with wrapping and 8px row gaps; content starts 24px beneath them.

## Imagery and graphics

### Documentary immersion

**Use:** Default opening film and intimate human proof.

**Observed:** Full-bleed footage shows a person using the technology in an ordinary interior, with the working device foregrounded and people allowed to enter at the edges. Natural ambient color, imperfect everyday surroundings and a wide viewpoint make the promise tangible. Smaller proof media is centered, rounded and substantially wider than its supporting text.

**Transfer:** Film a real task being made possible, including the person and their environment. A full-bleed still with the same action and framing is the minimum substitute for film; do not substitute a glossy abstract interface montage.

### Atmospheric grain

**Use:** Signature backing for human proof and closing invitations.

**Observed:** Pale ivory with soft, uneven yellow-gray clouds and fine fibrous grain; nearly white behind proof, warmer behind the paired artwork. There are no obvious gradient rings or bright hotspots.

**Transfer:** Create an original subtle paper-like field rather than placing modules on flat gray.

**Build:** Start on white. Layer three very broad radial gradients of rgba(168,158,85,0.12), rgba(205,194,120,0.10) and rgba(110,110,80,0.04), with centers around the upper left, lower right and middle. Use an SVG feTurbulence layer with fine noise, low contrast and approximately 0.04 opacity over the full section; soften cloud edges with a 60px blur. Keep the result pale enough that black type reads without a backing plate.

### Double exposure invitation

**Use:** Signature paired closing card artwork.

**Observed:** Opposing side-profile portraits merge with mountain and forest scenes. Teal light hangs through the head and shoulder; the lower landscape darkens toward olive in one card and dusty rose in the other. Color is translucent and atmospheric, not a saturated flat duotone.

**Transfer:** Combine original silhouettes of people, tools or product forms with the world they enable. Minimum version: a masked side-profile or object silhouette over a subdued contextual landscape plus a soft localized light layer.

**Build:** Clip each composition to a 20px rounded portrait rectangle. Use a neutral beige photographic base, mask a second landscape into the silhouette, then blend a translucent teal radial light around the neck or object center with screen compositing. Darken the bottom third with a transparent-to-black gradient at approximately 0.45 alpha; let a muted olive or rose photograph supply the hue. Place the white title and outlined action above all image layers.

### Isolated engineering object

**Only for:** engineering explainers and recruiting capability chapters

**Use:** Hero object and long-form part demonstrations.

**Observed:** Large gray-white three-dimensional forms float on pure black without a pedestal, frame or visible horizon. Exploded layers reveal metallic rims, dark casing, circuitry and ribbon-like connections. Objects occupy approximately the right half in explanatory chapters, then enlarge beyond the viewport for detailed part views. The central opening object has localized icy blue-white illumination along its working region.

**Transfer:** Use a softly lit exploded view or a sequence of product close-ups on black. For software, isolate a few meaningful interface layers with the same dimensional separation rather than showing a whole dashboard.

**Build:** Render or photograph the object against black, using broad soft key light and dark side falloff. To communicate an active region, draw a small network of curved SVG strokes following its form: a narrow white core over a wider translucent blue stroke, with a blurred 24px to 48px halo. Limit the light to the working region rather than outlining the whole object.

### Framed experience demonstration

**Only for:** engineering product experience sections

**Use:** Transition from internal mechanism to daily use.

**Observed:** A large video appears inside a heavy dark-gray device-like frame on white. The frame has a 32px edge and 16px corner radius, while the demonstration itself remains mostly monochrome.

**Transfer:** Show a task in context after explaining the machinery; use a simple substantial device frame, not a floating collage of miniature screens.

### Icons

**Observed:** Icons are sparse and monochrome: northeast arrows in actions, left/right arrows in 56px circles, small outline symbols beside principles and a tiny abstract brand mark. Directional SVGs are generally 12px to 16px, with fine 0.8px to 1.5px strokes; listing arrows are 18px.

**Transfer:** Use simple line geometry and preserve the text-first hierarchy. Avoid colorful filled feature-icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Lived experience opening

**Observed:** A 900px-high edge-to-edge documentary scene forms the complete first screen. The Spectral strip and Navigation sit over its upper edge, taking 96px together. The scene remains the dominant object across the entire width; a two-line Display headline occupies roughly one third of the width in the lower-left region, with a Primary button 46px below. There is no separate support paragraph. Layers are black stage, full-cover film or still, legibility darkening where needed, headline/action, then header. Within the first 900px the media, complete headline, action and both header rows are visible; the white explanatory band begins below the fold.

**Transfer:** Use one meaningful real-world scene with a clear task and place the benefit in a darker, visually calm lower corner. If film is unavailable, use an original documentary still with the same full-screen presence. An engineering explainer instead centers Engineering-display over an isolated object with a small bottom-left scroll link; an information page opens on white with Editorial-title, Information-lead, back link and outlined action; a recruiting campaign uses Recruiting-display along the bottom of a film.

**Avoid:** Do not default to a centered giant slogan on a generic gradient, a left-text/right-dashboard SaaS hero, or a stack of multiple competing calls to action.

**Text style:** `display` — UntitledSans 500 · 48px/1 · tracking -0.06em

### Split promise explanation

**Observed:** White canvas with 120px vertical padding. Split introduction places Heading in a narrow left column and Body in a narrow right column. The heading ends in an animated changing word with a visible cursor; each text block has ample empty space around it.

**Transfer:** Explain what the product converts into what outcome, then add a human consequence. Preserve the tight narrow columns rather than filling the center with a long paragraph.

**Text style:** `heading` — UntitledSans 300 · 44px/1 · tracking -0.06em

### Intimate human proof

**Observed:** Warm atmospheric field with a centered Heading, a 612px-wide documentary module, then a first-person quotation, name and compact context metadata. Carousel arrow controls sit to the right of the lower text. Segmented 3px progress lines stretch across the module; active black is longer than each faint inactive segment.

**Transfer:** Use a short credible testimony tied to a visible person or real use case; include contextual details instead of a wall of logos. One such tactile proof moment gives the page its human counterweight.

### Layered closing invitation

**Observed:** Warm atmospheric field, centered Heading and Paired invitations using Audience image card. Titles and Image outline button sit in the lower portion of each artwork. The field continues generously beneath the pair before the Footer begins.

**Transfer:** Give two audiences or intentions two concrete next steps; keep both inside the same visual world rather than giving each a separate theme.

### Pinned engineering chapter

**Observed:** Black stage with an 80px Chapter-title and compact Chapter-copy at left, large isolated object at right, 2px by 44px vertical progress ticks near the far left and a small underlined skip action near the bottom. Scroll progression moves from overview to enlarged parts while the explanatory arrangement remains stable.

**Transfer:** Use for a product whose internal structure rewards inspection. Tell one part or capability at a time and keep the descriptions short. A static sequence of overview and detail renders can carry the same hierarchy.

**Text style:** `chapter-title` — UntitledSans 300 · 80px/1 · tracking -0.06em

### Experience bridge and split exits

**Observed:** White canvas interrupts the dark engineering story. A small 20px section lead precedes a 40px paragraph-like Explanation-heading, then Framed experience demonstration. Closing invitations use Technical close: 72px left title, right support and Directional text link, 160px top and 240px bottom padding, with thin separators. Footer follows the final invitation.

**Transfer:** Move from how it is built to what daily use feels like, then offer relevant deeper paths without adding a second full-screen hero.

### Factual information page

**Observed:** Editorial column begins 80px beneath a 48px Navigation. Back link, Editorial-title and Information-lead are separated by 40px; Primary button becomes a black outline and sits 24px below support. Wide embedded documentary video precedes Information tab and a factual question/answer stack. Questions use Question; answers use Detail-body with 6.4px separation. A Pale utility band repeats the invitation. The final white section uses Explanation-heading, four short paragraphs, another outlined action and a back link before Footer.

**Transfer:** Use for eligibility, programs or detailed participation information. Preserve straightforward factual reading and repeated access to the same action rather than importing theatrical engineering scenes.

**Text style:** `editorial-title` — UntitledSans 300 · 72px/1.1 · tracking -0.06em

### Campaign proof and culture

**Observed:** Black stage uses small Eyebrow labels over large Campaign-heading. A split proof block pairs vertically stacked 64px Stat values and understated captions with a near-half-width documentary film. Culture card appears in a five-column row; a centered wide video follows. Values inset provides a broad light interruption, followed by a restrained large quotation on black with a faint oversized opening quote mark.

**Transfer:** On recruiting campaigns, make technical challenge, demonstrated progress and working conditions concrete. Keep statistics unboxed and captions subordinate; the light panel can hold decision principles rather than an arbitrary card grid.

**Text style:** `campaign-heading` — UntitledSans 300 · 64px/1 · tracking -0.05em

### Directory and monumental coda

**Observed:** A centered light heading and horizontally moving discipline labels introduce a white directory. Search and two filter fields share one row. Sticky category glass headings open groups of Listing card in three columns. After the last category, black returns for a centered resource heading, wide video, three 8px-radius outlined resource links and circular social links. Monumental-close supplies the final 128px sentence with a small support line and underlined email action; Footer ends the page.

**Transfer:** Keep the searchable directory as a functional middle act on recruiting pages, then restore the cinematic scale for a decisive human invitation. The coda is a campaign variant, not the default ending of every marketing page.

**Text style:** `monumental-close` — UntitledSans 300 · 128px/0.92 · tracking -0.06em

## Page flow

**Storyline:** human promise → plain-language mechanism → tangible proof → relevant next steps → spacious utility ending; technical and recruiting variants deepen the middle rather than changing the brand vocabulary.

### Broad product or mission landing page

1. **promise** — Full-screen lived-experience film, short lower-left benefit and one white capsule.
2. **explanation** — White two-column introduction with a changing outcome word.
3. **human proof** — Warm textured field, centered documentary carousel and personal quotation.
4. **closing invitation** — Paired double-exposure artwork cards present two audience paths.
5. **utility ending** — Pale footer with compact link groups, small action and widely separated bottom marks.

**Transfer:** Lead with a visible outcome and earn the explanation through real use; end with two meaningful paths instead of a generic newsletter form.

### Detailed participation or program information

1. **orientation** — Back link, large light title, direct explanatory lead and outlined capsule on white.
2. **human proof** — Wide embedded film establishes the personal context.
3. **objection handling** — Plain tabs, bold questions, concise answers and nested eligibility lists.
4. **conversion reminder** — Pale full-width band repeats the same action.
5. **mechanism explanation** — White reading section, short paragraphs, final action and back link.
6. **utility ending** — Shared pale footer.

**Transfer:** Prioritize comprehension and qualification; keep the visual language but replace spectacle with readable detail.

### Deep technical product explanation

1. **promise** — Centered two-line title over a glowing isolated object on black.
2. **explanation** — White introductory text with word-based emphasis.
3. **capability chapters** — Pinned black scenes dissect the object and its supporting machinery.
4. **product demonstration** — White experience lead and substantial framed video.
5. **closing invitation** — Two spacious split rows point to participation and opportunities.
6. **utility ending** — Shared pale footer.

**Transfer:** Use chapters to reveal internal structure, then return to everyday usability and relevant next steps.

### Recruiting campaign with an actionable directory

1. **promise** — Full-screen film with a monumental lower-edge sentence and floating directory action.
2. **mission** — Large centered word statement on black.
3. **capability chapters** — Three image-led engineering challenges with numbered mono labels.
4. **quantified proof** — Unboxed large stats beside a human demonstration.
5. **working context** — Compact culture cards, wide film, broad light principle panel and quotation.
6. **opportunity discovery** — White introduction, discipline ticker, filters and categorized listing grid.
7. **closing invitation** — Black resource coda, oversized invitation sentence and direct email action.
8. **utility ending** — Shared pale footer.

**Transfer:** Move from meaningful work to concrete work, then make opportunities easy to find; reserve the grandest closing typography for this campaign form.

## Writing

Calm, declarative and ambitious, grounding an extraordinary future in tangible mechanisms and real people. Information-led copy is careful and explanatory; recruiting copy is more challenging and direct.

**Do not copy:** Do not reuse Neuralink names, marks, product names, participant identities, clinical claims, eligibility requirements, study identifiers, numerical achievements or attributed quotations. Replace all with verified facts and original language appropriate to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we or our when explaining the work, you when inviting participation, and people when describing outcomes. First-person testimony belongs to a named speaker, not the corporate narrator.
- **Rhythm:** Short sentence-case headlines, usually a compact phrase or one direct sentence. Support is one or two brief paragraphs; longer information sections use clear questions and short factual answers. Enthusiasm comes from the substance, not exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Connect the underlying capability to a meaningful change in life. | 6–10 words | “From neural signals to life-changing impact” |
| Section title | Plain invitation or active description, not a clever category pun. | 3–8 words | “Meet our pioneers”<br>“See it for yourself.” |
| Explanation | State what the system translates or enables, then give an observable use. | One or two short sentences | “Our brain-computer interface translates neural signals into actions.” |
| Action | Verb plus a specific destination or participation path. | 3–6 words | “Explore our clinical trials”<br>“Join the Patient Registry” |
| Technical challenge | Direct imperative plus a concrete engineering constraint. | 4–8 words | “Build a coin-sized computer.”<br>“Decode intent in milliseconds.” |
| Closing line | A direct invitation with a broader sense of consequence. | 4–7 words | “Make history with us.” |

**Words and phrasing to use:** build; restore; enable; control; independence; designed to; learn more; work; people; experience

**Avoid:** game-changing solution; unlock synergies; effortlessly magical; 10x everything; disrupt your workflow; !!!

**Rules:**

- Explain the mechanism before stacking additional promises.
- Keep factual limitations and qualifications legible in information-led sections.
- Use one clear destination per action and repeat that destination consistently.
- Write short labels that can sit in tight capsules without shrinking the type.
- Let proof captions provide human context; keep testimonials brief and specific.

## Do's and Don'ts

### Do

- Keep the ordinary opening headline at 48px, weight 500; use 44px, weight 300 for its surrounding section titles.
- Give documentary media full-width presence and retain the 900px desktop opening scale.
- Preserve 58px primary capsules and their fine 1px outline.
- Use 120px vertical padding for the white split introduction, not a compressed feature strip.
- Center the human proof module at 612px and keep its 56px circular controls visible.
- Use the 48px spectral strip as the concentrated interface color accent.
- Keep footer groups compact at 16px/24px while allowing the footer itself 527px of depth.
- In technical chapters, pair 80px titles with only 320px-wide compact explanatory copy.

### Don't

- Do not make all headlines weight 600 or 700; the large light grotesk is essential.
- Do not replace the 80px primary capsule radius with rectangular software-style buttons.
- Do not treat the 9.6px recruiting-card radius as the default for the 20px image artwork cards.
- Do not extend the spectral palette to large solid page fills or gradient body text.
- Do not add elevated shadows to every content block; most edges are plain, photographic or 1px rules.
- Do not put proof quantities in colorful statistic tiles; their campaign treatment is unboxed 64px light type.
- Do not enlarge the footer mark into a giant decorative wordmark; its scale stays small and infrastructural.
- Do not add a generic six-card feature grid to replace the centered human proof and paired artwork invitations.

## Motion and responsive

### Motion

**Observed:**

- Primary filled action declares background-color 0.2s ease-in-out; outlined image actions declare background-color 0.2s.
- Audience image cards declare 0.3s linear for the subtle hover scale and shadow change.
- Carousel arrow backgrounds declare 0.3s; footer links declare color 0.1s.
- Listing cards declare background-color, border-color and transform at 0.25s; their hover lift is 4.8px.
- The changing outcome word includes a blinking cursor with a declared 0.8s animation. The recruiting discipline ticker declares 120s linear infinite movement.
- Engineering chapters use sticky or pinned object scenes and scroll-driven progression; the announcement declares height 0.5s.

**Transfer:**

- Use motion to expose one part or one human story at a time, not to animate every sentence independently.
- Keep hover changes restrained: background inversion, tiny card scale or a short upward lift according to component.
- For a static implementation, retain the full overview and representative part views rather than a long empty scrolling interval.

**Unknown:**

- Exact scroll interpolation, video playback behavior and most reveal easing assignments are not established.
- Focus-visible and active designs are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 500px, 751px, 900px, 901px, 1100px, 1399px, 1400px, 1700px and 1920px; the recruiting variant also includes 360px.
- Campaign typography and some campaign spacing use the clamp formulas specified in their recipes.

**Transfer:**

- As a design adaptation, stack split explanations and the paired invitations on narrow screens while retaining the media-first hierarchy.
- Let the main scene remain dominant, but choose a deliberate narrow framing that preserves both the person or product and the headline.
- Reduce directory column count rather than compressing 16.8px job titles into tiny type.

**Unknown:**

- Exact mobile menu construction, mobile ordering and breakpoint-specific measurements are not established.
- The default 48px headline has no confirmed fluid formula.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
