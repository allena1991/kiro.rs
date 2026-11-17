# Tailwind CSS — the ruled playground

## Overview

A light, developer-literate style that makes technical capability feel tangible and playful. Oversized regular-weight grotesk headlines sit on a faint ruled framework, with monospaced annotations, black pill actions, and restrained cyan and magenta accents. Dense interface demonstrations and colorful work samples supply the spectacle while the surrounding typography and canvas remain almost entirely monochrome. It suits tools, platforms, and products whose strongest pitch is showing what people can make with them.

### Essentials

- Headlines feel like enormous typesetting specimens rather than slogans in a box: Inter 96px/1, weight 400, -0.05em tracking, left aligned across nearly the entire content width.
- The opening is a working bench, not a centered poster: 40px outer rails, 8px text insets, a two-line headline, support limited to 768px, compact actions, then a dark input panel beside a light output object entering the first screen.
- The page shows its underlying construction: 1px low-contrast rules, 40px diagonally hatched side rails, and ghosted 12px/24px mono annotations accompany major text and media boundaries. Carry this technical notation into every new landing page with short, meaningful implementation or product labels.
- Actions are small black capsules against a vast white field: 40px height, 8px 16px padding, 32px radius, and 14px/24px semibold labels; search is a separate outlined 320px capsule rather than a competing filled action.
- Color belongs to demonstrations and tiny signposts, not the whole canvas: white and pale gray dominate; 12px uppercase mono eyebrows use cyan or fuchsia, while richer palettes remain contained inside product scenes and work imagery.
- Capability proof is a nested playground: white 16px rounded cards separated by 8px gray channels contain 32px padded introductions, thin isometric line illustrations, and 8px rounded dotted demo wells. Include a concrete input/output or before/after scene; if no product interface exists, construct a small diagram and its resulting artifact.
- The close earns its space with visual proof rather than a giant sales banner: a broad, tightly packed collage of varied outputs in a pale 8px frame leads into ruled resource columns and a low-key theme/legal strip. Adapt the collage to real work, artifacts, or use-case previews. 

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Technical cyan | `#00a6f4` | `--color-cyan` | accent, text, link | Core technical eyebrows and inline monospaced terms. |
| Proof fuchsia | `#e12afb` | `--color-fuchsia` | accent, text | A contrasting chapter signpost for output and proof sections. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page and card canvas; inverse action labels. |
| Demo well wash | `#f9f9f9` | `--color-demo-wash` | surface | Near-black at 2.5% over white inside demonstration wells. |
| Pale gray channel | `#f2f3f3` | `--color-channel` | surface, border | Visible result of near-black at 5% on white: card channels, hairlines, and subdued label backing. |
| Stronger edge | `#e6e6e7` | `--color-edge` | border | Near-black at 10% over white for control outlines. |
| Ghost annotation | `#cccccc` | `--color-ghost` | text | Black at 20% over white for unobtrusive construction labels. |
| Muted slate | `#6a7282` | `--color-muted` | text | Secondary text, testimony, keyboard hints, and the softer half of directory display copy. |
| Slate body | `#4a5565` | `--color-body` | text | Supporting paragraphs and explanatory copy. |
| Secondary ink | `#364153` | `--color-secondary-ink` | text | Legal strip and denser secondary information. |
| Near-black ink | `#030712` | `--color-ink` | text, background | Headlines, primary text, and dark demonstration shells. |
| Black action | `#000000` | `--color-action` | action, background | Primary conversion pills and monochrome proof marks. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| directories and partnership pages | Directory off-white | `#fafafa` | `--color-directory-canvas` | background | Unruled background supporting dense lists and square testimonial cards. |
| directories | Cyan badge wash | `#e6f8ff` | `--color-badge-wash` | surface | Visible cyan wash from #00bcff at 10% over white behind status badges. |
| work catalogs | Neutral catalog caption | `#525252` | `--color-catalog-caption` | text | Monospaced image category captions. |

## Typography

- **inter** — All marketing headings, paragraphs, navigation, and action labels. High-x-height grotesk; regular display cuts with very tight spacing, medium and semibold small labels. OpenType features: "cv02", "cv03", "cv04", "cv11". Font stack: "inter", system-ui, sans-serif.
- **plexMono** — Technical annotations, chapter eyebrows, inline terms, and catalog captions. Distinctly mechanical monospace with a slashed zero and deliberate uppercase spacing. OpenType features: "ss02", "zero". If unavailable, use **IBM Plex Mono**. Use weights 400–600 with the stated tracking. Font stack: "plexMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | inter | 400 | 96px | 1 | -0.05em | Default landing headline and large work-catalog promise. |
| heading | inter | 500 | 40px | 1 | -0.05em | Chapter leads, often constrained to 512px and one or two lines. |
| feature-title | inter | 500 | 24px | 40px | normal | Capability card title beside a line illustration. |
| lead | inter | 500 | 18px | 28px | normal | Opening support copy. |
| inline-code | plexMono | 500 | 17px | 28px | normal | Highlighted technical terms within opening prose. |
| body | inter | 400 | 16px | 1.75 | normal | Chapter support paragraphs up to 768px wide. |
| small-body | inter | 400 | 14px | 2 | normal | Card explanations and resource links. |
| ui-label | inter | 400 | 14px | 24px | normal | Navigation, search, compact explanatory text, and legal information. |
| action-label | inter | 600 | 14px | 24px | normal | Primary action labels and named entries in text-led lists. |
| footer-heading | inter | 600 | 14px | 2 | normal | Resource column headings. |
| eyebrow | plexMono | 600 | 12px | 16px | 0.1em, uppercase | Colored chapter signposts, 16px above headings. |
| annotation | plexMono | 400 | 12px | 2 | normal | Ghosted construction annotations adjacent to major type. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| directories and partnership pages | directory-display | inter | 400 | 56px | 60px | -0.025em | A continuous statement whose short opening is dark and longer continuation is muted. |
| partnership pages | benefit-title | inter | 600 | 18px | 28px | normal | Headings of square benefit-and-testimonial cards. |
| work catalogs | catalog-name | inter | 500 | 14px | 24px | normal | Work titles immediately under thumbnails. |
| directories and partnership pages | directory-label | plexMono | 400 | 12px | 20px | 0.1em, uppercase | Small gray-backed title or numbered chapter marker. |
| directories | filter-label | inter | 500 | 12px | 20px | normal | Compact category controls. |
| directories | status-label | inter | 500 | 11px | 20px | normal | Tinted status badges in directory rows. |

**Notes:**

- The largest headline stays regular, not bold. The 40px chapter heading is slightly heavier but keeps the same -0.05em tracking; small text returns to normal tracking.
- Monospace is structural punctuation rather than the main voice. Reserve 0.1em tracking for uppercase labels; technical prose and captions retain normal spacing.
- Catalog captions use the annotation recipe in neutral gray rather than the ghosted treatment. Interface interiors retain their own smaller typography instead of becoming a second marketing scale.

## Layout

**Density:** Airy at chapter scale, compact within proof and product demonstrations; long neutral pauses contrast with closely packed media.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card frame padding, demo-to-frame spacing, and tight grid channels. |
| 16px | Eyebrow-to-heading spacing, action gaps, and resource link gaps. |
| 24px | Navigation gaps and smaller card introduction padding. |
| 32px | Desktop capability introductions, demo well padding, and testimonial card padding. |
| 40px | Headline-to-support and support-to-actions gaps; catalog gutters and footer column vertical padding. |
| 64px | Chapter introduction to capability grid. |
| 96px | Opening air beneath navigation and compact chapter separation. |
| 160px | Major landing chapter separation and the pause before resource columns. |

### Containers and grids

- **Ruled page frame**: max width 1536px · side padding 40px. Central expanding content flanked by 40px hatched rails at the desktop width; text is inset another 8px from the content boundary.
- **Paragraph measure**: max width 768px · side padding 8px. Left-aligned introduction paragraphs leave the right half of the page mostly open.
- **Chapter heading measure**: max width 512px · side padding 8px. Short section leads break deliberately without becoming full-width banners.
- **Capability mosaic**: 2 columns · gap 8px · side padding 8px. A dense 30-track spanning grid yields full-width cards, half-width pairs, and compact thirds; use unequal spans where a demonstration needs more room.
- **Proof and catalog grid**: 4 columns · gap 40px. Four open ruled columns; proof marks sit in 310px by 120px cells, while image catalogs use taller thumbnail-and-caption cells.
- **Resource columns**: 3 columns · gap 32px. Three equal ruled columns spanning the central frame.
- **Directory split** (only for directories and partnership pages): 2 columns · gap 80px · side padding 40px. A 3:7 split: left introduction and numbered marker, right 896px list or testimonial grid.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Primary action | 32px |
|  | Search and status | 9999px (pill) |
|  | Capability frame | 16px |
|  | Demo well | 8px |
| work catalogs | Catalog thumbnail | 12px |
| directories | Directory control | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Fine frame edge | `0 0 0 1px rgba(3,7,18,0.05)` | Very soft outlines around white demo frames; not floating marketing-card elevation. |
|  | Search inner edge | `inset 0 0 0 1px rgba(3,7,18,0.08)` | The empty search capsule. |
| product demonstrations | Floating demo artifact | `0 25px 50px -12px rgba(0,0,0,0.25)` | Select transformed artifacts inside product scenes, never the entire card grid. |

### Surfaces

#### White ruled canvas · level 0

**Use:** Default landing canvas.

**CSS:** `background: #ffffff; color: #030712`

**Observed:** Faint horizontal rules extend across text and media boundaries; vertical lines establish the central frame and repeated columns.

**Transfer:** Keep the framework visible but subordinate to text. Use 1px rgba(3,7,18,0.05) rules at meaningful content boundaries.

#### Hatched rails · level 0

**Use:** Technical texture at page edges and beside input/output stages.

**CSS:** `background-image: repeating-linear-gradient(315deg, rgba(0,0,0,0.05) 0px, rgba(0,0,0,0.05) 1px, rgba(0,0,0,0) 0px, rgba(0,0,0,0) 50%); background-size: 10px 10px; border-left: 1px solid rgba(0,0,0,0.05); border-right: 1px solid rgba(0,0,0,0.05)`

**Observed:** The narrow rails run down the long landing and catalog canvases; larger hatched areas can back a demonstration output.

**Transfer:** Use the same restrained drafting-paper material, not a contrasting decorative stripe.

#### Capability tray · level 1

**Use:** Shared backing that visually joins the capability mosaic.

**CSS:** `background: rgba(3,7,18,0.05); padding: 8px; gap: 8px`

**Observed:** The backing is exposed as thin channels around white cards.

**Transfer:** Treat the mosaic as one assembled tray rather than unrelated floating cards.

#### White capability frame · level 2

**Use:** Explanatory title and demo grouped as one unit.

**CSS:** `background: #ffffff; border-radius: 16px; outline: 1px solid rgba(3,7,18,0.05); padding: 8px; overflow: hidden`

**Observed:** Introduction and inset demo are stacked; corners and fine edge remain legible against the tray.

**Transfer:** Retain the nested frame even when the inner demonstration is only a simple interactive diagram.

#### Dotted demo well · level 3

**Use:** Backing for tangible product examples.

**CSS:** `background-color: rgba(3,7,18,0.025); background-image: radial-gradient(rgba(3,7,18,0.05) 1px, rgba(0,0,0,0) 0px); background-size: 10px 10px; border-radius: 8px; padding: 32px; overflow: hidden`

**Observed:** The dotted field sits behind artifacts rather than behind marketing paragraphs. Typical capability wells are 448px tall.

**Transfer:** Stage an artifact large enough to be clipped by the well rather than showing a tiny centered thumbnail.

#### Dark demonstration shell · level 2

**Use:** Input/output explanations and the opening product stage.

**CSS:** `background: #030712; border-radius: 12px; overflow: hidden`

**Observed:** Window dots and inset translucent white panels give a dark code-workbench effect. Panels use 8px radii, white at 10%, and faint inset white edges.

**Transfer:** For non-code products, show source material, settings, or a process on the left and the result on the right without changing the surrounding light page.

#### Directory field · level 0

**Only for:** directories and partnership pages

**Use:** Dense directory and benefits canvas.

**CSS:** `background: #fafafa; color: #030712`

**Observed:** No hatched side rails; white rectangular benefit panels stand directly on the off-white field.

**Transfer:** Keep this text-led variant separate from the nested rounded playground used on a general landing page.

## Components

### Fixed navigation

**Use:** Persistent low-profile orientation.

**CSS:** `position: fixed; top: 0px; height: 57px; width: 100%; z-index: 10; background: #ffffff; border-bottom: 1px solid rgba(0,0,0,0.05)`

**Text style:** `ui-label` — inter 400 · 14px/24px

**Observed:** Brand and compact version capsule are left aligned; search shortcut, plain text links, a lightly outlined premium label, and repository icon align right. Inner row is 56px high with 24px horizontal padding and 24px link gaps.

**Transfer:** Use a restrained identity and only useful utility destinations; keep the bar visually lighter than the hero.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-block; background: #000000; color: #ffffff; border-radius: 32px; padding: 8px 16px; height: 40px; box-sizing: border-box`

**Text style:** `action-label` — inter 600 · 14px/24px

**Observed:** The opening version is text only; sponsorship and contact versions append a small right arrow.

**States:** Declared: hover background-color lab(16.1051% -1.18239 -11.7533).

### Search capsule

**Use:** Secondary discovery route beside the primary action.

**CSS:** `display: grid; grid-template-columns: auto 1fr auto; align-items: center; gap: 4px; width: 320px; height: 40px; padding: 8px 16px; box-sizing: border-box; border-radius: 9999px; color: rgba(3,7,18,0.5); box-shadow: inset 0 0 0 1px rgba(3,7,18,0.08)`

**Text style:** `ui-label` — inter 400 · 14px/24px

**Observed:** A 16px search glyph precedes the label and a small keyboard shortcut sits at the far right. It is an action opening search rather than a visibly editable field.

### Capability card

**Use:** A capability explained through a real example.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 8px; background: #ffffff; border-radius: 16px; outline: 1px solid rgba(3,7,18,0.05); overflow: hidden`

**Text style:** `feature-title` — inter 500 · 24px/40px

**Observed:** A 32px padded introduction pairs an isometric line illustration with title and small-body copy; the Dotted demo well follows. Wider cards use a horizontal intro with 32px between illustration and text; compact cards stack it.

**Transfer:** Write a short capability name and show the actual outcome rather than a decorative dashboard unrelated to the claim.

### Resource column

**Use:** Quiet resource navigation near the ending.

**CSS:** `padding: 40px 0px 40px 8px; border-right: 1px solid rgba(3,7,18,0.05)`

**Text style:** `footer-heading` — inter 600 · 14px/2

**Observed:** A semibold heading precedes plain small-body links in a grid with 16px gaps; columns share the page rails. Links are not styled as buttons.

**States:** Declared: hover text-decoration-line underline on resource links.

### Catalog tile

**Only for:** work catalogs

**Use:** A repeatable work or customer output specimen.

**CSS:** `border-left: 1px solid rgba(3,7,18,0.05); border-right: 1px solid rgba(3,7,18,0.05)`

**Text style:** `catalog-name` — inter 500 · 14px/24px

**Observed:** An 8px padded thumbnail region contains a 292px by 215px image with 12px corners and a fine outline. A separate 8px padded caption region follows with 8px separation, name above mono category. Optional tiny cyan template badge sits beside the name.

**Transfer:** Preserve each work's own colors inside the thumbnail; captions and surrounding structure remain neutral.

### Directory row

**Only for:** directories

**Use:** A compact, whole-row link with structured metadata.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr 1fr auto; align-items: center; gap: 16px; padding: 20px 8px 20px 16px; border-top: 1px solid rgba(3,7,18,0.05)`

**Text style:** `action-label` — inter 600 · 14px/24px

**Observed:** A small monochrome logo and semibold name lead, followed by a status badge, regular-weight category, and muted trailing action with an arrow. The parent grid aligns columns across all rows; rows are about 66px high.

**States:** Declared: hover background-color color-mix(in oklab, lab(1.90334% .278696 -5.48866) 2.5%, transparent).

### Filter chip

**Only for:** directories

**Use:** Category selection above a directory.

**CSS:** `border-radius: 6px; padding: 4px 12px; color: #030712; box-shadow: 0 0 0 1px rgba(3,7,18,0.1)`

**Text style:** `filter-label` — inter 500 · 12px/20px

**Observed:** Chips wrap with 8px gaps. Selected chip is near-black with white type, not a colored pill.

**States:** Declared: hover background-color color-mix(in oklab, lab(1.90334% .278696 -5.48866) 5%, transparent).

### Status badge

**Only for:** directories

**Use:** Small tier or status notation in a directory row.

**CSS:** `border-radius: 9999px; padding: 2px 10px; background: rgba(0,188,255,0.1); color: #00a6f4`

**Text style:** `status-label` — inter 500 · 11px/20px

**Observed:** Cyan is the primary tier; muted gray and pink distinguish other tiers. Badges stay visually smaller than the row name.

### Benefit testimony card

**Only for:** partnership pages

**Use:** A benefit supported by a named person's account.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; padding: 32px`

**Text style:** `benefit-title` — inter 600 · 18px/28px

**Observed:** Square-edged panels in a two-column grid with 8px gaps. Benefit heading and paragraph occupy the top; quote sits low after a generous internal pause, followed by semibold attribution, lighter role, and a monochrome logo aligned right.

**Transfer:** Pair each commercial benefit with a relevant real testimony instead of collecting disconnected quotes.

## Imagery and graphics

### Input and tangible output

**Use:** The opening's main object and deeper explanatory chapters.

**Observed:** A dark window with subtle gray window dots and syntax-colored text occupies roughly two thirds of the opening media stage. A small white card containing richly colored album-like artwork sits to its right on a hatched backing, creating a direct code-to-object relationship. Later, the same dark window expands to a full-width split editor and terminal.

**Transfer:** Use one meaningful input and one polished result. For a non-code product, a compact settings or source-material panel beside an output artifact is sufficient; retain the contrast between dark process and light result.

**Build:** Construct a 12px rounded near-black shell, a narrow top row with three muted circular dots, and 8px rounded panels filled with white at 10%. In a roughly 2:1 split, place the panel on the left and a white 16px rounded artifact card on the right; back the right area with Hatched rails texture. Use original product content inside both.

### Isometric capability drawings

**Use:** Signature visual labels at capability introductions.

**Observed:** Small monochrome exploded planes, devices, layers, and motion trails are drawn in thin dark outlines with white faces and faint gray secondary lines. They read as miniature technical diagrams, never colorful sticker illustrations.

**Transfer:** Create a small diagram of each new capability using a shared isometric projection. The minimum version is two offset rounded rectangular planes and one simple symbolic detail.

**Build:** Use SVG paths for a flattened diamond-like rounded rectangle, duplicate it 4px lower to suggest thickness, and connect corners with thin ink strokes. Add offset copies, dotted connectors, or fading outlines to express stacking, movement, or containment; keep white fills and restrained 1px–2px line weight.

### Demonstration artifacts

**Use:** Large, deliberately clipped objects inside capability wells.

**Observed:** Examples include a property-photo grid, a split light/dark financial card with a cyan divider, vibrant color swatches, easing diagrams, gradient performance bars, and a tilted portrait card. Photography is specific and naturalistic; effects demonstrate the feature rather than decorating the surrounding page.

**Transfer:** Show one visible property changing per demonstration. Use original real product objects, and isolate rich hues or photographic texture within the Dotted demo well.

### Output collage

**Use:** The broad visual proof device near the landing ending.

**Observed:** A nearly full-width 980px-tall panel assembles varied web designs into tightly spaced masonry-like vertical strips with unequal widths and lengths, small rounded corners, and edge clipping. Bright pink, neutral interfaces, landscape imagery, editorial typography, and dark panels retain their own identity; the frame stays pale.

**Transfer:** Assemble real outputs or realistic use-case previews with comparable diversity. If there is no library of customer work, create several distinct product artifacts at different shapes and scales rather than repeating one mockup.

**Build:** Inside White capability frame, make five flex columns with 8px gaps and unequal widths; stack preview images with 8px vertical gaps and 8px corners. Let large central previews anchor the composition and let narrow edge columns clip at the frame. Populate every visible preview with intentional content.

### Monochrome proof field

**Use:** Open social-proof grids.

**Observed:** Black customer and partner marks are centered in four columns of ruled cells, with substantial whitespace and varied but optically balanced mark sizes.

**Transfer:** Use legitimate customer marks or concise monochrome proof statements; balance their apparent visual weight, not their bounding-box dimensions.

### Catalog previews

**Only for:** work catalogs

**Use:** A large browseable collection of examples.

**Observed:** Four columns of landscape website previews retain original light, dark, photographic, and saturated themes. The 672:494 aspect ratio, 12px corners, and fine edge unify them without imposing a color treatment.

**Transfer:** Use consistently framed previews of real examples; avoid recoloring them to the marketing palette.

### Icons

**Observed:** Small navigation glyphs are solid at 16px or 20px; trailing action arrows are about 10px. Theme controls use thin 1px strokes in 28px boxes. Capability illustrations are a separate, larger isometric line-drawing system.

**Transfer:** Use simple monochrome utility SVGs for actions and navigation. Keep conceptual isometric drawings distinct from ordinary interface icons.

## Section recipes

How recurring sections are built.

### First screen: Ruled workbench opening

**Observed:** A fixed white 57px navigation sits above the ruled canvas. A 96px high breathing zone with ghosted annotation leads into the display headline, nearly full-width and two lines at 96px/1. The left-aligned 768px lead paragraph sits 40px below it, followed after another 40px by Primary button and Search capsule separated by 16px. Below a 96px pause, the Input and tangible output stage starts: dark editor on the left, hatched backing and white artifact on the right. Within the first 900px, the headline, complete support, actions, and upper part of both main objects are visible; the lower media continues below the fold. Layers read white canvas, faint rules and annotation, black text/actions, then the framed demonstration.

**Transfer:** Match the hierarchy and visible media entry rather than the original headline length. Use an original input/result pair or a simple source-to-outcome diagram if the product has no interface. Work catalogs open with the same large display and a short, witty paragraph before four preview columns; directories use a 56px continuous dark-to-muted statement, a compact label, and one action on an unruled off-white field.

**Avoid:** Do not center the entire composition, put a large illustration behind the headline, or shrink the workbench to a tiny device floating in an empty hero.

**Text style:** `display` — inter 400 · 96px/1 · tracking -0.05em

### Annotated chapter lead

**Observed:** Colored eyebrow above a heading with 16px separation; heading uses the 40px recipe within 512px. Ghosted mono notation occupies the gap before a 768px body paragraph, with 40px between heading and support. An optional action follows with the same gap. Rules run through the wider canvas rather than ending at the text measure.

**Transfer:** Use concise chapter labels and one practical promise per lead. Keep supporting explanation narrower than the page and let proof occupy the broad area below.

**Text style:** `heading` — inter 500 · 40px/1 · tracking -0.05em

### Ruled proof field

**Observed:** Annotated chapter lead and compact action introduce four open columns of black marks. Cells are around 310px wide and 120px high with 40px horizontal column separation and faint structural boundaries.

**Transfer:** Scale the field to available proof; keep the marks monochrome and large enough to feel intentional without turning each into a boxed card.

### Capability playground

**Observed:** A Capability tray begins 64px below the introductory paragraph. Capability cards span the dense grid in full-width, pairs, and thirds. Each introduces a thin isometric drawing, a feature-title, small-body support, and a Dotted demo well with a generously scaled artifact.

**Transfer:** Choose spans according to the demonstration, not the number of benefits. Mix broad demonstrations with compact conceptual cards while retaining the 8px assembly channels.

**Text style:** `feature-title` — inter 500 · 24px/40px

### Mechanism workbench

**Observed:** Annotated chapter lead precedes a full-width Dark demonstration shell. A large source panel and terminal stack on the left; a narrower result panel sits on the right. Small file tabs and window dots make the mechanism legible while the light canvas remains continuous around it.

**Transfer:** Use a process-to-result explanation relevant to the new product; retain the wide joined panel instead of three unrelated feature boxes.

### Visual proof close

**Observed:** A short chapter lead introduces the Output collage, framed in the same pale tray language as the capability sections. After the collage, about 160px of breathing room leads to Resource columns. There is no additional oversized conversion banner.

**Transfer:** Close a general landing page with breadth of possible outcomes and a quiet route to deeper resources. The proof device can appear elsewhere too; its function is to make variety visible.

### Utility ending

**Observed:** Resource columns use 40px top/bottom padding and fine vertical rules. Beneath a horizontal separator, a 170px strip has 40px top and 96px bottom padding: a three-option theme capsule sits left, copyright and a policy link sit right in 14px/24px text.

**Transfer:** Keep practical controls and legal content low in the visual hierarchy; do not introduce a new bold visual motif at the last moment.

### Catalog collection

**Only for:** work catalogs

**Observed:** A display promise and an 18px/32px explanatory paragraph lead to four columns of Catalog tiles with 40px gutters. Titles and mono category captions remain attached to their previews. The long collection ends with the same resource columns and legal strip, not a load-more sales card.

**Transfer:** Use the catalog variant for a portfolio, ecosystem, or example library with a clear taxonomy.

### Directory and benefit close

**Only for:** directories and partnership pages

**Observed:** A 3:7 left/right composition places numbered gray-backed labels and concise introductory copy in the narrow column. On the right, Filter chips precede aligned Directory rows. A later section repeats the split, with contact copy and a Primary button left and a two-by-two grid of Benefit testimony cards right. The final section is a simple theme/legal strip without resource columns.

**Transfer:** Use this variant for partner programs, integrations, or structured provider lists, and close with concrete mutual benefits rather than the landing collage.

## Page flow

**Storyline:** Promise → tangible demonstration → proof of adoption → capability and mechanism explanations → breadth of outcomes → practical next destinations.

### Product landing that makes a technical tool feel immediately useful

1. **Promise** — Expansive regular-weight display, concise support with colored technical terms, compact action and search.
2. **Product demonstration** — Dark source panel beside a tangible light output.
3. **Social proof** — Short annotated lead and a broad monochrome mark field.
4. **Capability chapters** — A nested mosaic of illustrated, example-led capability cards.
5. **Mechanism explanation** — A wide joined source/result workbench.
6. **Breadth of outcomes** — A tightly packed, colorful output collage.
7. **Resource ending** — Three ruled resource columns, then theme and legal controls.

**Transfer:** Adapt the sequence to the product's strongest evidence; preserve the ruled framework, tangible demonstration, and broad visual proof without reproducing a fixed section count.

### Browsable proof catalog showing many distinct applications

1. **Promise** — Two-line display and a self-aware support paragraph.
2. **Proof collection** — Four columns of image-led tiles with a short name and mono category.
3. **Resource ending** — Resource columns and theme/legal strip after the last item.

**Transfer:** Keep descriptive context short so the examples carry the argument; let the inventory determine page length.

### Text-led ecosystem directory and partnership conversion

1. **Invitation** — Large continuous statement starts dark and continues in muted gray; one contact action follows.
2. **Structured proof** — Numbered left introduction accompanies filters and aligned metadata rows.
3. **Objection handling** — Contact invitation beside a two-by-two benefit/testimony grid.
4. **Utility ending** — Simple theme/legal strip with no extra resource grid.

**Transfer:** Use the split layout and off-white field for a dense integration or commercial-program page; reserve colored badges for meaningful status distinctions.

## Writing

Confident, practical, and openly enthusiastic about making things. Technical specificity is balanced with conversational asides and a little dry humor rather than enterprise grandiosity.

**Do not copy:** Do not reuse the Tailwind name, logo, class-name artwork, customer identities, product claims, performance numbers, or testimonial quotations as claims for another product. Source examples illustrate tone only.

- **Addressing the reader:** Address the reader directly as you and your. The product can speak in we when explaining how it helps; descriptions stay concrete about what the reader can do.
- **Rhythm:** Long but plainspoken opening promises contrast with short chapter headings and compact action labels. Support usually takes one or two sentences; contractions and an occasional em dash keep explanations conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Lead with a direct action and the friction it removes. | 8–15 words | “Rapidly build modern websites without ever leaving your HTML.” |
| Chapter heading | A short benefit or confident statement, with a period. | 3–8 words | “Ship faster and smaller.”<br>“Built for the modern web.” |
| Supporting line | Explain the mechanism in ordinary language; a lightly skeptical aside can lower the temperature of a technical claim. | One or two sentences | “Okay, it’s not exactly cutting edge, but just throw a screen size in front of literally any utility to apply it at a specific breakpoint.” |
| Primary action | A familiar verb names the next step without embellishment. | 2–4 words | “Get started”<br>“Become a partner”<br>“Get in touch” |
| Proof introduction | Promise breadth and connect it to things the audience already recognizes. | One or two sentences | “Some of your favorite sites are built with Tailwind, and you probably had no idea.” |

**Words and phrasing to use:** build; ship; directly; your; just; works; whatever you want; in front of

**Avoid:** revolutionize your business; unparalleled synergy; best-in-class solutions; seamless digital transformation

**Rules:**

- Explain a claim through a visible mechanism or example nearby.
- Use humor as a brief aside, not as the main argument.
- Name capabilities plainly; keep labels shorter than the explanation they introduce.
- Use actual numbers only where they are verifiable and relevant to the new product.

## Do's and Don'ts

### Do

- Keep the default display at 96px/1, weight 400, with -0.05em tracking at desktop.
- Retain 40px outer rails and an additional 8px text inset in the ruled variant.
- Use 12px uppercase mono labels with 0.1em tracking to distinguish chapters.
- Let rich color live inside demos and output imagery while white remains the dominant canvas.
- Assemble capability cards with 16px outer corners, 8px inner wells, and 8px channels.
- Use a 768px maximum measure for chapter support and a 512px measure for short chapter leads.
- Stage input and result at visibly different scales, with the dark panel taking roughly twice the width of the output area.
- End with fine rules, 14px utility text, and generous bottom padding rather than another attention-grabbing motif.

### Don't

- Do not replace regular display type with a 700-weight headline; the tight, light letterforms carry the identity.
- Do not make cyan the default primary-button fill; conversion buttons are black.
- Do not use 24px rounded floating cards for every proof mark; the mark field is open and ruled.
- Do not apply heavy drop shadows to capability frames; their edges are only near-black at 5%.
- Do not turn the 12px mono annotation system into full-width paragraphs of code-styled marketing copy.
- Do not tint or desaturate all catalog previews to match the neutral canvas; their variety is the proof.
- Do not apply the directory's square white testimonial panels to the default nested capability playground.
- Do not enlarge status chips into major badges; their type is 11px and their horizontal padding is 10px. 

## Motion and responsive

### Motion

**Observed:**

- Declared color transitions use 0.15s cubic-bezier(.4, 0, .2, 1); opacity transitions use the same timing.
- A demonstration declares a 0.35s border-radius transition and another a 0.3s multi-property transition. A small ping uses 1s cubic-bezier(0, 0, .2, 1) infinitely.

**Transfer:**

- Keep utility feedback short and color-based. Reserve visible transformations and animated comparisons for explanatory demo objects, not the whole page frame.

**Unknown:**

- Actual playback sequences and scroll-trigger behavior are not established.
- Focus-visible and active appearance for primary controls is not established.

### Responsive

**Observed:**

- Declared responsive widths include 320px, 600px, 640px, 712px, 768px, 877px, 1024px, 1280px, and 1536px.
- The landing headline declares stepped sizes rather than fluid viewport scaling; it gains medium weight below the large breakpoint. Catalog classes declare one column, then two, then more columns at larger widths.
- Directory classes declare one stacked column before the 3:7 split, and list metadata is reduced at narrow widths.

**Transfer:**

- On narrow screens, remove the wide hatched side rails before sacrificing readable text; stack source and result with the input first.
- Collapse capability spans while preserving the 8px tray/frame relationship. Keep artifacts large and clip their wells rather than shrinking all demo text to illegibility.
- Use a smaller stepped headline, retain its tight tracking, and allow its line breaks to change naturally.
- Collapse directory introductions above lists and hide secondary metadata before truncating the primary name.

**Unknown:**

- Exact rendered mobile compositions and intermediate headline sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
