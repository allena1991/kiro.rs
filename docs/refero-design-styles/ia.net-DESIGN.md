# iA — words take the stage

## Overview

A literate, product-led style that makes useful tools feel absorbing rather than complicated. Pale gray pages, black type and small flashes of cyan alternate with theatrical charcoal demonstrations. Humanist sans-serif typography carries the marketing, serif prose gives articles a bookish register, and oversized interfaces or tactile photographs do most of the explaining. The pacing is spacious even when the supporting proof becomes text-rich.

### Essentials

- Headlines behave like compact book titles, not billboards: a centered 57.8px bold product name with -0.02em tracking opens the page; chapter headings use 43.7px bold type at 1.08 line height.
- The opening is a working example, not a slogan collage: a 49px navigation strip, centered name and 570px-wide support line lead into a 1024px-wide demonstration, separated by 72px. Keep the main object visible in the first 900px.
- Actions look like soft physical keys: platform downloads use 67px-high pale pills with 20.9px bold labels and a small platform silhouette; compact uppercase actions use 30px radii.
- Color marks attention rather than painting the whole page: #00b2ff belongs to 17px uppercase chapter labels, cursors and compact actions. Most area remains #f7f7f7, #252525 or black; richly colored media stays inside its own frame.
- The product gets a theater: include an oversized, softly shadowed demonstration and a contrasting dark product stage. Use a genuine task view, or a carefully typeset before-and-after specimen when no interface is available.
- Proof reads like a small publication: 16px quotations in three narrow columns sit directly on the canvas, with centered publication marks or circular grayscale portraits rather than testimonial cards.
- The ending returns to useful things: a warm conversion invitation, a light newsletter panel with topic checkboxes and a long pill input, then compact footer columns and a small left-aligned credential strip.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Attention cyan | `#00b2ff` | `--color-cyan` | accent, action, text | Chapter kickers, compact actions and attention marks; not a general section fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep black | `#000000` | `--color-black` | background, text | Immersive demonstration field, editorial tile text and text-link hover. |
| Reading ink | `#222222` | `--color-ink` | text | Default headings, navigation and body copy. |
| Product theater | `#252525` | `--color-charcoal` | background | Full-width conversion stages with devices and pale text. |
| Hairline gray | `#dfdfdf` | `--color-rule` | border | Input outlines and lesson-row dividers. |
| Soft inverse ink | `#f0f0f0` | `--color-inverse` | text | Reading text and action labels on dark stages. |
| Pale paper | `#f7f7f7` | `--color-canvas` | background, surface | Default page and card canvas; the navigation uses this hue at 80% opacity over passing content. |
| White | `#ffffff` | `--color-white` | surface, text | Email input background, bright text and play glyph. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and physical-product purchase actions | Purchase black | `#070707` | `--color-button-black` | action | Purchase pills and dark download buttons on pale pricing panels. |
| physical-product directories | Directory gray | `#757575` | `--color-muted` | text | Secondary directory labels and addresses. |
| physical-product stories | Object backdrop | `#ededed` | `--color-object-gray` | background | Neutral backing for large physical-product compositions. |

## Typography

- **iASansDay** — Marketing headings, paragraphs, navigation and controls. Open, humanist sans with an editorial texture; solid bold headings without geometric severity. OpenType features: "dlig". If unavailable, use **Source Sans 3**. Use 400, 500 and 700; retain the compact headline tracking. Font stack: "iASansDay", "Source Sans 3", system-ui, -apple-system, sans-serif.
- **iASansNight** — Inverse reading text within immersive feature demonstrations. Companion sans adjusted for light letters on dark grounds. OpenType features: "dlig". If unavailable, use **Source Sans 3**. Keep the same widths and hierarchy as the daytime setting. Font stack: "iASansNight", "Source Sans 3", system-ui, -apple-system, sans-serif.
- **iASerifDay** (only for long-form editorial articles) — Article prose and enlarged introductory paragraphs. Bookish text serif with clear italic contrast and a relaxed reading rhythm. OpenType features: "dlig". If unavailable, use **Source Serif 4**. Font stack: "iASerifDay", "Source Serif 4", Georgia, serif.
- **iAWriterMono** (only for learning indexes) — Oversized lesson numbers, not ordinary marketing body copy. Unadorned monospace with thin, conspicuous numerals. OpenType features: "dlig". If unavailable, use **IBM Plex Mono**. Font stack: "iAWriterMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | iASansDay | 700 | 57.8px | 1 | -0.02em | fixed | Centered product-name headline. |
| heading | iASansDay | 700 | 43.7px | 1.08 | -0.015em | fixed | Main marketing chapter and conversion headings; inverse color on charcoal. |
| heading-inverse | iASansNight | 700 | 43.7px | 1.08 | -0.015em | fixed | Heading within black immersive demonstration chapters. |
| support | iASansDay | 500 | 28.5px | 1.45 | normal | fixed | Centered supporting promise beneath a marketing heading. |
| support-inverse | iASansNight | 500 | 28.5px | 1.45 | normal | fixed | Support line within black immersive demonstration chapters. |
| body-feature | iASansDay | 400 | 24.8px | 1.5 | normal | fixed | Two-column explanations below major demonstrations; emphasize a short opening clause in bold. |
| body | iASansDay | 400 | 23px | 1.65 | normal | fixed | General explanatory prose, FAQs and learning introductions. |
| subheading | iASansDay | 700 | 23px | 1.65 | normal | fixed | Newsletter heading and small informational section labels. |
| download-label | iASansDay | 700 | 20.9px | 1 | normal | fixed | Platform names within download pills. |
| tile-title | iASansDay | 700 | 20.7px | 1.35 | normal | fixed | Editorial and promotional tile titles. |
| tile-body | iASansDay | 400 | 20.7px | 1.35 | normal | fixed | Short descriptions directly below tile titles. |
| newsletter-copy | iASansDay | 400 | 20.7px | 1.55 | normal | fixed | Newsletter invitation above topic selectors. |
| footer-link | iASansDay | 400 | 18.4px | 1.65 | normal | fixed | Footer destinations. |
| footer-heading | iASansDay | 700 | 18.4px | 1.65 | normal | fixed | Footer group labels. |
| navigation | iASansDay | 400 | 17.1px | 1.65 | normal | fixed | Compact breadcrumb and header links. |
| action | iASansDay | 700 | 17.1px | 1.65 | 0.029em, uppercase | fixed | Compact action pills. |
| eyebrow | iASansDay | 700 | 17px | 1.65 | 0.08em, uppercase | fixed | Cyan chapter labels above feature headings. |
| quotation | iASansDay | 400 | 16px | 1.6 | normal | fixed | Long review and customer quotations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| learning indexes | lesson-number | iAWriterMono | 400 | 66px | 1.65 | normal | fixed | Cyan numerals at the start of lesson rows. |
| pricing and learning pages | utility-title | iASansDay | 700 | 60.1px | 1.1 | -0.02em | fixed | Centered functional page title. |
| editorial article openings | article-title | iASansDay | 700 | 60.1px | 1 | -0.02em, uppercase | fixed | Centered uppercase news headline. |
| physical-product stories and learning libraries | heading-object | iASansDay | 700 | 57.8px | 1.1 | -0.015em | fixed | Large material-story and library section headings. |
| pricing pages | pricing-heading | iASansDay | 700 | 50px | 1.08 | -0.015em | size clamp(36px, 3.5vw, 50px) | Major explanatory and policy section titles. |
| editorial articles | article-heading | iASansDay | 700 | 29.1px | 1.3 | -0.015em | fixed | Centered article chapter titles. |
| editorial articles | article-lead | iASerifDay | 400 | 27.6px | 1.65 | normal | fixed | Enlarged opening paragraph. |
| physical-product FAQs | faq-question | iASansDay | 700 italic | 26.4px | 1.45 | normal | fixed | Open, always-readable FAQ questions. |
| pricing panels | plan-title | iASansDay | 800 | 23.8px | 1.2 | 0.03em | fixed | Centered payment and platform labels; the trial panel uses normal tracking. |
| editorial articles | article-body | iASerifDay | 400 | 23px | 1.65 | normal | fixed | Long-form narrative prose with underlined inline links and italic emphasis. |
| learning indexes | lesson-title | iASansDay | 700 | 19.8px | 1.65 | normal | fixed | Bold task title inside each row. |
| learning indexes | lesson-description | iASansDay | 400 | 19.8px | 1.65 | normal | fixed | Single explanatory line under the task title. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use sentence case for marketing headlines; uppercase is reserved for kickers, compact actions and the editorial news-title variant.
- Display tracking is -0.02em; chapter headings relax to -0.015em. Body copy has normal tracking rather than fashionable tight spacing.
- Keep the centered support line much narrower than its heading. The 570px measure gives 28.5px text a deliberate two- or three-line cadence.
- The product interface can contain monospaced or serif text, but those internal faces do not replace the marketing sans.

## Layout

**Density:** Airy product chapters, with compact navigation and comparatively dense quotation and resource sections.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 4px | Kicker-to-heading gap. | fixed |
| 5px | Heading-to-support gap; 6px also occurs. | fixed |
| 20px | Editorial card-grid gutters. | fixed |
| 22px | Two-column explanation and download-action gaps. | fixed |
| 31.1px | Newsletter side inset and image-to-tile-title separation. | fixed |
| 33px | Quotation-column gutter. | fixed |
| 44px | Information-grid gutters and explanation-block vertical padding. | fixed |
| 56px | Opening media-to-explanation gap and light-section bottom padding. | fixed |
| 66px | Major content separation and final bottom breathing room. | fixed |
| 72px | Heading group to product media. | clamp(40px, 5vw, 72px) |
| 100.8px | Feature chapter top padding. | clamp(64px, 7vw, 112px) |
| 115.2px | Dark conversion stage top and bottom padding. | clamp(64px, 8vw, 128px) |

### Containers and grids

- **main-container**: max width 1024px. Centered product media, card grids, newsletter and footer. At 1440px this leaves 208px at either side.
- **heading-container**: max width 968px. Centered chapter heading group, slightly inset from the main media edges.
- **support-measure**: max width 570px. Centered supporting promise; do not stretch to the full headline measure.
- **feature-explanation**: max width 1024px · 2 columns · gap 22px. Equal text columns below wide media.
- **editorial-grid**: max width 1024px · 3 columns · gap 20px. 328px-wide article tiles with aligned image tops.
- **quotation-columns**: max width 1024px · 3 columns · gap 33px. Long, independently flowing quotations rather than uniform boxed rows.
- **information-grid** (only for pricing and support information): max width 1024px · 3 columns · gap 44px. Unboxed icon, heading, explanation and action stacks.
- **purchase-pair** (only for pricing pages): max width 1024px · 2 columns · gap 16.5px. Two equal 504px panels, with the trial beside the purchase controls.
- **article-measure** (only for editorial articles): max width 922px. Single prose column with photographs spanning the same measure.
- **directory-measure** (only for physical-product specifications and retail directories): max width 800px · 2 columns · gap 72px. Narrower practical-information area after expansive photography.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | download-pills | 9999px (pill) |
|  | compact-actions | 30px |
|  | editorial-panels | 11px |
|  | demonstrations | 12px |
|  | email-field | 100px |
|  | play-control | 50% |
| pricing pages | pricing-panels | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| soft-panel | `rgba(0, 0, 0, 0.05) 0px 0px 10px 0px, rgba(0, 0, 0, 0.05) 0px 0px 15px 0px, rgba(0, 0, 0, 0.05) 0px 0px 20px 0px, rgba(0, 0, 0, 0.05) 0px 0px 25px 0px` | Newsletter and editorial tiles; edges emerge through soft ambient shadow rather than contrasting fills. |
| floating-demo | `rgba(0, 0, 0, 0.05) 5px 5px 10px 0px, rgba(0, 0, 0, 0.05) 10px 10px 20px 0px, rgba(0, 0, 0, 0.05) 20px 20px 40px 0px, rgba(0, 0, 0, 0.05) 40px 40px 80px 0px` | Large floating software demonstrations. |
| focused-demo | `rgba(0, 0, 0, 0.25) 0px 4px 44px 0px` | Comparison and selected editing demonstrations; corners vary between 6px and 12px. |

### Surfaces

#### Canvas · level 0

**Use:** Default page plane.

**CSS:** `background: #f7f7f7; color: #222222`

#### Charcoal stage · level 0

**Use:** Product-led conversion bands.

**CSS:** `background: #252525; color: #f0f0f0`

**Observed:** Runs edge to edge while the headline, product lineup and actions remain centered.

**Transfer:** Use for a consequential invitation backed by a visible product, not a decorative dark stripe.

#### Soft panel · level 1

**Use:** Newsletter, lesson-index wrapper and editorial tiles.

**CSS:** `background: #f7f7f7; border-radius: 11px; box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 10px 0px, rgba(0, 0, 0, 0.05) 0px 0px 15px 0px, rgba(0, 0, 0, 0.05) 0px 0px 20px 0px, rgba(0, 0, 0, 0.05) 0px 0px 25px 0px`

**Observed:** Almost the same tone as the surrounding canvas.

**Transfer:** Keep the elevation subtle, with content carrying the hierarchy.

#### Floating demonstration · level 1

**Use:** Large software task examples.

**CSS:** `border-radius: 12px; box-shadow: rgba(0, 0, 0, 0.05) 5px 5px 10px 0px, rgba(0, 0, 0, 0.05) 10px 10px 20px 0px, rgba(0, 0, 0, 0.05) 20px 20px 40px 0px, rgba(0, 0, 0, 0.05) 40px 40px 80px 0px`

**Observed:** The task view itself supplies the fill; no extra colored card is wrapped around it.

#### Immersive field · level 0

**Use:** A dramatic capability demonstration.

**CSS:** `background: #000000; color: #f0f0f0`

**Observed:** Tiny, subdued blue-white light points surround a large dark task view.

**Transfer:** Keep the atmosphere lower contrast than both text and product.

#### Object backdrop · level 0

**Only for:** physical-product stories

**Use:** Split object-and-copy compositions.

**CSS:** `background: #ededed; color: #222222`

**Observed:** Light object photography nearly merges into the backing, with soft directional shadows.

#### Purchase panel · level 1

**Only for:** pricing pages

**Use:** Payment and platform choices.

**CSS:** `background: #f7f7f7; border: 1px solid transparent; border-radius: 16px; padding: 34.1px 29.7px 29.7px; box-shadow: rgba(0, 0, 0, 0.05) 0px 8px 18px 0px, rgba(0, 0, 0, 0.05) 0px 18px 36px 0px, rgba(0, 0, 0, 0.075) 0px 0px 0px 1px`

**Observed:** The trial sibling has a dashed rgba(0,0,0,0.3) outline and a scissors detail, like a redeemable coupon; purchase has a faint continuous edge.

## Components

### Sticky navigation

**Use:** Persistent orientation without a heavy masthead.

**CSS:** `position: sticky; top: 0px; height: 49px; background: rgba(247, 247, 247, 0.8); backdrop-filter: blur(10px); z-index: 99`

**Text style:** `navigation` — iASansDay 400 · 17.1px/1.65

**Observed:** A centered main-width row puts the bold short brand name and slash breadcrumb on the left; a few text links and a compact action sit on the right.

### Header action

**Use:** Persistent acquisition shortcut.

**CSS:** `border-radius: 30px; color: #ffffff; padding: 10.3px 17.1px 6.8px`

**Text style:** `action` — iASansDay 700 · 17.1px/1.65 · tracking 0.029em · uppercase

**Observed:** A small cyan filled pill beside the navigation links; its physical-product variant is black and says Buy.

**States:** Declared: hover white text and brightness(1.2); focus-visible brightness(1.2); active brightness(1.2).

### Platform download

**Use:** Primary acquisition action on dark product stages.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 4.2px; background: #f7f7f7; color: #222222; border-radius: 9999px; padding: 23.1px 24.2px 22px; height: 67px; box-sizing: border-box`

**Text style:** `download-label` — iASansDay 700 · 20.9px/1

**Observed:** Platform silhouette precedes the label. Multiple pills form a centered wrapping row; a small subdued eligibility or payment note sits below each. On pale pricing panels the pill is near-black with inverse text.

**States:** Declared: hover scale(1.02); focus-visible scale(1.02); active scale(1.01).

### Compact action

**Use:** Contact and support destinations below explanations.

**CSS:** `display: inline-flex; align-items: center; gap: 8.4px; background: #00b2ff; color: #f0f0f0; border-radius: 30px; padding: 11.1px 17.1px 8.6px`

**Text style:** `action` — iASansDay 700 · 17.1px/1.65 · tracking 0.029em · uppercase

**Observed:** Often has a small line icon before the uppercase label. A course-start variant is cyan; the physical-product purchase variant is near-black.

**States:** Declared: hover and focus-visible scale(1.02) with unchanged cyan fill and inverse text; active scale(1.01). The course-start and physical-product closing variants instead scale(0.95).

### Editorial tile

**Use:** Related reading, resource libraries and a single wide closing promotion.

**CSS:** `border-radius: 11px; box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 10px 0px, rgba(0, 0, 0, 0.05) 0px 0px 15px 0px, rgba(0, 0, 0, 0.05) 0px 0px 20px 0px, rgba(0, 0, 0, 0.05) 0px 0px 25px 0px`

**Text style:** `tile-title` — iASansDay 700 · 20.7px/1.35

**Observed:** Image first, then bold title and regular tile-body description. Grid media is 328×207px; text has 20.7px side insets and 31.1px top separation. A wide promotional tile uses a 1024×683px photograph.

**Transfer:** Use actual editorial art or product detail images; keep descriptions brief enough for consistent rows.

### Newsletter panel

**Use:** A useful subscription invitation near the ending.

**CSS:** `border-radius: 11px; padding: 26.9px 31.1px 20.7px; box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 10px 0px, rgba(0, 0, 0, 0.05) 0px 0px 15px 0px, rgba(0, 0, 0, 0.05) 0px 0px 20px 0px, rgba(0, 0, 0, 0.05) 0px 0px 25px 0px`

**Text style:** `subheading` — iASansDay 700 · 23px/1.65

**Observed:** Left-aligned title, newsletter-copy invitation, a vertical topic-checkbox menu, then Email capsule. Selected boxes carry a cyan check; the default topic follows the surrounding product.

### Email capsule

**Use:** The final newsletter form row.

**CSS:** `display: flex; flex-wrap: wrap; background: #ffffff; border: 1px solid #dfdfdf; border-radius: 100px; padding: 9.3px`

**Observed:** A wide editable field and a cyan Subscribe pill share a single outlined capsule. At desktop the outer row is 970×82px and the submit pill is 150×61px.

### Footer link group

**Use:** Compact utility navigation at the bottom.

**CSS:** `color: #222222; padding-bottom: 18.4px`

**Text style:** `footer-link` — iASansDay 400 · 18.4px/1.65

**Observed:** Bold footer-heading labels sit over regular links. Six narrow columns share the main width, with secondary groups stacked within columns. A small row of credentials sits separately below, aligned to the left.

**States:** Declared: hover text becomes black.

### Play control

**Use:** User-initiated product films.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 60px; height: 60px; background: rgba(32, 32, 32, 0.5); border-radius: 50%; backdrop-filter: saturate(1.8) blur(17.5px)`

**Observed:** A centered solid white triangular glyph sits over the actual film poster, not an empty black rectangle.

**States:** Declared: focus-visible 2px solid white at 88% opacity, with 2px outline offset.

### Lesson row

**Only for:** learning indexes

**Use:** A scannable ordered course outline.

**CSS:** `height: 110px; border-bottom: 1px solid #dfdfdf`

**Text style:** `lesson-title` — iASansDay 700 · 19.8px/1.65

**Observed:** Inside a Soft panel, each row places a cyan lesson-number in a 72.6px leading track, title above lesson-description, and small time/media indicators toward the far right. The final row omits the rule.

**States:** Declared: hover text #222222, no shadow and no text decoration.

### Purchase choice

**Only for:** pricing pages

**Use:** Explain payment and choose a platform.

**CSS:** `background: #f7f7f7; border-radius: 16px; padding: 34.1px 29.7px 29.7px; box-shadow: rgba(0, 0, 0, 0.05) 0px 8px 18px 0px, rgba(0, 0, 0, 0.05) 0px 18px 36px 0px, rgba(0, 0, 0, 0.075) 0px 0px 0px 1px`

**Text style:** `plan-title` — iASansDay 800 · 23.8px/1.2 · tracking 0.03em

**Observed:** Centered heading, compact platform rows with icon, label, toggle and price, then a cyan total-price pill with a tiny payment qualifier. A separate coupon-like trial panel contains product devices and dark Platform download controls.

**Transfer:** Keep numbers practical and integrated with the controls rather than inflating them into giant promotional statistics.

## Imagery and graphics

### Task specimen

**Use:** The opening and major capability explanations.

**Observed:** A huge, minimally framed task view shows actual work. Pale surfaces almost merge into the page, while shadows lift their right and lower edges. In focus demonstrations one passage stays dark while surrounding content fades; a cyan insertion point gives a single accent. Media is normally 1024px wide, commonly 16:9 or a slightly taller desktop proportion.

**Transfer:** Show the new tool doing one clear job. Without a real interface, typeset a believable output specimen and distinguish the active region through contrast, not an invented dashboard.

**Build:** Create a 1024px-wide responsive panel with 12px corners and the Floating demonstration shadow. Center a restrained task specimen with ample empty space inside the panel; set inactive material at low ink opacity and the active result at full ink, adding a narrow cyan caret only if editing is relevant.

### Device ensemble

**Use:** Dark acquisition stages.

**Observed:** Front-facing and gently elevated laptops, phones, tablets and monitors appear as isolated objects across a 950px-wide field. Black hardware and subdued screen content blend into charcoal, leaving aluminum surfaces and silhouettes readable. There is no bright decorative backdrop.

**Transfer:** Use clean product cutouts or one convincing hero object on charcoal. For a service, use a small family of real output formats instead of unrelated hardware.

### Distant light field

**Use:** Atmosphere around a pivotal dark demonstration.

**Observed:** A sparse blue-white star field on pure black surrounds a dark floating document. Points are tiny, unevenly spaced and mostly dim; the heading and demonstration remain the foreground.

**Transfer:** Preserve one immersive dark interlude but tie the contents to the new product's most consequential capability.

**Build:** Build an SVG tile 1024×1024px with irregularly distributed circles of 1–2px radius, using white and cyan at roughly 0.1–0.4 opacity. Give only a few points a 2–3px blur halo. Repeat the tile centered over black behind the main content; avoid connecting lines, large flares and uniform dot grids.

### Human and publication proof

**Use:** Reviews and customer-story columns.

**Observed:** Publication marks are monochrome and centered above the quote. Customer headshots are grayscale circular portraits, around 115px in their display region. The surrounding quotations remain unboxed.

**Transfer:** Use only legitimate attribution and replace portraits with compact text attribution where photography is unavailable.

### Tactile object photography

**Only for:** physical-product stories

**Use:** Full-bleed material chapters, split closing scenes and packaging sequences.

**Observed:** White paper objects are photographed on pale seamless grounds, blond wood or muted green woven mats. Raking soft light reveals embossing, fibers, curved pages and binding. Close views of hands at work use shallow depth of field and dark clothing; broader object photographs retain natural low-saturation color. Images expand to 1440px width, often at 3:2 or 5:4 proportions.

**Transfer:** Photograph the equivalent material truth: texture, joining, handling and packaging. Use one real close-up rather than synthetic glossy renderings when budgets are limited.

### Editorial collage

**Only for:** resource libraries and related articles

**Use:** Thumbnail art within Editorial tiles.

**Observed:** Historical engravings, cutout figures, oversized letterforms, photographed objects and real interface fragments share clean rectangular compositions. Each thumbnail can have its own muted or bold backing; those colors do not spread into the surrounding page.

**Transfer:** Make art specific to the article's idea, with one focal subject and one graphic gesture.

**Build:** On a 328×207px SVG or image canvas, place one high-contrast cutout or engraving off-center and one oversized cropped word or numeral behind it. Use a restrained flat ground; keep enough negative space to read the subject at thumbnail size.

### Icons

**Observed:** Platform silhouettes lead download labels. Supporting information uses small black outline symbols, often around 24px, above its heading. Video play glyphs are solid white inside a 60px translucent circle. Lesson rows use tiny document and video indicators beside duration labels.

**Transfer:** Choose plain functional silhouettes for platforms and lightly drawn outline symbols for explanatory content; keep icons subordinate to words.

## Section recipes

How recurring sections are built.

### First screen: Working-product opening

**Observed:** Behind everything is Canvas. Sticky navigation occupies the top 49px with a main-width inner row. After 86.4px of breathing room, a compact app mark and bold centered product name share one line in display type. The support recipe sits 5px below in a 570px measure. After 72px, a 1024×576px Task specimen begins, filling most of the remaining first screen and extending slightly below the 900px fold. The header's small Get action is the visible acquisition shortcut; there is no oversized CTA row between promise and demonstration. Explanatory columns begin 56px below the media, out of the first screen.

**Transfer:** Keep this as the default landing-page opening: compact identity, one human benefit, one convincing working specimen. If no app exists, stage a tangible output or photographed tool with the same hierarchy. Pricing and learning pages instead open with utility-title, a short introduction or label and immediate choices; editorial pages use article-title, date/read metadata and a photograph. Physical-product stories can open with a full-width 16:9 film poster and centered Play control.

**Avoid:** Do not replace the working object with a huge abstract slogan, a busy browser chrome mockup, or a cluster of feature badges. Do not put a large button stack into the promise-to-media gap.

**Text style:** `display` — iASansDay 700 · 57.8px/1 · tracking -0.02em

### Capability chapter

**Observed:** A cyan eyebrow, heading and support form a centered group within heading-container. The support is narrower than the title. Floating demonstration follows after 72px; a feature-explanation pair follows below, often with one bold opening sentence per column. Feature tops use 100.8px padding; light chapter bottoms commonly use 56px or 66px.

**Transfer:** Give each chapter one outcome that can be demonstrated. Use the media to show the mechanism and the lower columns to explain the tradeoff.

**Text style:** `heading` — iASansDay 700 · 43.7px/1.08 · tracking -0.015em

### Immersive demonstration

**Observed:** Immersive field and Distant light field turn one capability into a black interlude. Cyan label, heading-inverse and support-inverse remain centered above a full main-width film or demonstration. Product content, rather than atmospheric effects, occupies the center.

**Transfer:** Use the dark interlude for a capability that merits a change in attention, keeping the signature theater even if the demonstration is a static specimen.

### Conversion theater

**Observed:** Charcoal stage uses 115.2px top and bottom padding. A centered heading and support lead to a 950px Device ensemble after about 72px, then a centered Platform download row after about 88px. The closing version uses a warm invitation and a slightly longer supporting paragraph.

**Transfer:** Return to the product at decision points, varying the scene and invitation rather than repeating identical sales copy. Keep one such dark stage on a new landing page.

**Text style:** `heading` — iASansDay 700 · 43.7px/1.08 · tracking -0.015em

### Unboxed proof columns

**Observed:** A chapter heading and support introduce three narrow quotation columns with 33px gutters. Monochrome publication marks or circular portraits precede 16px quotation text; attribution is bold within the same reading block. The quantified claim is written as prose, not giant isolated digits.

**Transfer:** Use detailed, attributable proof when available. Fewer genuine statements are preferable to filling the full column count with weak blurbs.

**Text style:** `quotation` — iASansDay 400 · 16px/1.6

### Editorial library

**Observed:** A centered heading pair introduces Editorial tiles in three columns with 20px gutters. Images align across the row; titles and short descriptions sit beneath. Related reading uses the same construction on a smaller collection.

**Transfer:** Use for supplementary knowledge after the core product story, or as the primary content of a learning library.

### Useful ending

**Observed:** The default landing ending follows the final Conversion theater with Newsletter panel, then a wide Editorial tile promotion. Footer link group columns remain on Canvas, followed by three small credential marks at the left and 66px bottom space. Pricing ends with practical contact blocks then the newsletter. Learning and editorial pages move from their content libraries directly to the footer and credentials; the physical-product story uses its split object close before the newsletter.

**Transfer:** Include the compact footer and credential-strip construction, using real trust marks or a small textual credential treatment when no marks apply. Choose the appropriate preceding invitation for the page's job rather than forcing every page to end with the same promotion.

### Practical purchase explanation

**Only for:** pricing pages

**Observed:** A utility-title and small uppercase product label lead to a purchase-pair: trial coupon on the left and Purchase choice on the right, followed by platform-store panels. Unboxed three-column information groups and two-column policy explanations follow under pricing-heading titles.

**Transfer:** Keep transactional choice first, then explain ownership, eligibility and returns in plain language. Use Compact action only where it resolves a specific question.

### Learning index

**Only for:** learning pages

**Observed:** A utility-title, centered 23px introduction and Start Course pill precede the Soft panel course outline after 66px. Lesson rows use large cyan numbers, two-line task text and right-aligned duration indicators. A large selected lesson film and a three-column thumbnail library continue the page.

**Transfer:** Give the reader a clear finite path before offering the larger resource collection.

### Material story and object close

**Only for:** physical-product stories

**Observed:** Full-bleed photographs carry much more area than text. Small category label, heading-object and 23px support sit on a readable part of the image, inset about 72px. The closing Object backdrop splits a centered text/action group on the left from a 648px-wide object image on the right; a 48px near-black purchase pill sits beneath the promise.

**Transfer:** Move between material detail, handling and finished object. End the physical-product story with a calm object-and-action composition rather than importing the software device lineup.

### Open FAQ

**Only for:** physical-product FAQs

**Observed:** A centered section label introduces fully expanded questions in faq-question, with ordinary body answers. Each answer is separated from the next question with roughly 44px of breathing room; no accordion controls are shown.

**Transfer:** Use the italic questions to create a conversational register while keeping the answers immediately readable.

### Long-form article

**Only for:** editorial articles

**Observed:** An uppercase article-title and small date/read-time/previous-next row sit above a large product photograph. A 922px prose measure uses article-lead then article-body; centered article-heading titles punctuate left-aligned subheads and narrative. Product detail photographs and a two-small-plus-one-wide image grouping interrupt the text. The ending moves from an inline purchase link to a topic chip and Related Articles, not a newsletter.

**Transfer:** Treat the story as reading material with demonstrable details; do not apply serif body text or uppercase news headlines to ordinary landing-page chapters.

## Page flow

**Storyline:** Promise → visible product experience → capability and tradeoff explanations → credible proof → invitation to try or buy → useful follow-up and compact navigation.

### Flagship software landing page

1. **promise** — Compact centered product identity, human benefit and oversized working specimen.
2. **acquisition** — Dark device stage with platform-specific download pills.
3. **capability chapters** — Comparison, immersive demonstration and pale task specimens alternate with two-column explanations.
4. **social proof** — Full-width event photograph, publication quotations and customer columns; years and adoption appear in prose.
5. **closing call** — Warm dark invitation, visible product lineup and repeated platform actions.
6. **follow-up** — Newsletter preferences, wide related-product tile, footer columns and small credential strip.

**Transfer:** Adapt the number and order of chapters to the product while retaining large demonstrations and a distinct dark invitation.

### Editorial announcement or product-design essay

1. **news hook** — Uppercase title, date/read metadata, previous-next links and a product photograph.
2. **context** — Enlarged serif lead and narrative background.
3. **substantiation** — Design principles, development story, documentary image and material close-ups.
4. **next step** — Forward-looking conclusion with inline purchase and retailer links.
5. **further reading** — Packaging gallery, topic chip, related article grid, footer and credential strip.

**Transfer:** Use long-form narrative to explain why the product deserves attention without converting the page into a landing-page CTA ladder.

### Pricing and purchase guidance

1. **decision** — Centered utility title above paired trial and one-time-purchase panels, followed by platform-store options.
2. **eligibility** — Unboxed assistance columns for discounts, volume needs and license recovery.
3. **objection handling** — Ownership and platform explanations, return-policy steps and detailed refund instructions.
4. **human assistance** — Contact, response-hours and privacy blocks.
5. **follow-up** — Newsletter panel, compact footer and credential strip.

**Transfer:** Make choice and cost visible before supplying detailed policy prose; keep assistance close to the relevant objection.

### Learning hub

1. **orientation** — Finite course promise and a single start action.
2. **guided path** — Numbered lesson list with short descriptions and media durations.
3. **demonstration library** — Selected film followed by thumbnail grid.
4. **further learning** — Large curated editorial tile collection.
5. **navigation ending** — Footer columns and credential strip without a newsletter interruption.

**Transfer:** Separate the prescribed path from the browseable reference collection.

### Physical-product story

1. **sensory introduction** — Full-width film poster, then split promise and enlarged object.
2. **product demonstration** — Photographic details, handling and a before/after optical comparison.
3. **craft proof** — Full-bleed material and manufacturing scenes with small supporting text.
4. **social proof** — Packaging sequence, founder explanation and unboxed customer quotations.
5. **practical reassurance** — Specifications, shipping, tabbed retail directory and open FAQs between large detail images.
6. **closing call** — Split gray object-and-purchase scene, newsletter, footer and credentials.

**Transfer:** Let actual material qualities drive the photography and story, then reduce scale for practical purchasing information.

## Writing

Confident, literate and direct, with the occasional dry joke. Benefits are framed as removal of friction, and explanations admit limits instead of hiding them behind superlatives.

**Do not copy:** Do not reuse iA names, logos, product artwork, proprietary interface content, awards, adoption numbers, founding dates, customer quotations or purchase promises as claims for another brand. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you; use we when explaining product decisions and responsibility. Product names are used plainly, not personified as magical assistants.
- **Rhythm:** Short outcome headlines, a one- or two-sentence support line, then fuller explanatory prose. Parallel clauses and contrasts carry the rhythm; occasional conversational questions lighten the authority.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product promise | A tangible action connected to a mental or practical benefit. | One short sentence | “Keep your hands on the keys and your mind in the text.” |
| Chapter heading | A compact contrast, imperative or plain outcome. | 3–7 words | “Cut noise, think clearly”<br>“One thing at a time” |
| Capability support | Name what happens, then state what the user controls. | 1–2 sentences | “Style Check flags clichés, fillers, and clutter.”<br>“You decide what to cut and what to keep.” |
| Conversion invitation | A warm invitation followed by the practical terms. | Short heading plus supporting sentence | “Make yourself at home”<br>“Download now. No credit card required.” |
| Policy explanation | Use an everyday analogy or a candid distinction. | A short heading plus a factual paragraph | “One-Time ≠ Lifetime” |
| Editorial voice | Self-aware first-person storytelling with specific process details. | Varied paragraph-length prose | “Prototype, test, and redesign until it works.” |
| Action label | Literal verb or destination rather than a persuasive slogan. | 1–2 words | “Start Course”<br>“Contact Us” |

**Words and phrasing to use:** focus; plain; write first; made to; nothing distracts; try it; you decide; built for; care; works

**Avoid:** revolutionary ecosystem; unlock your potential; seamless synergy; game-changing solution; AI-powered everything; unlimited lifetime value

**Rules:**

- Explain a feature through the work it makes easier, not the size of its feature list.
- Use specific exclusions to clarify focus: what has been left out, and why.
- Keep pricing qualifiers and eligibility notes close to their action.
- Let honest limitations and concrete production details carry credibility.
- Reserve jokes for headlines or transitions; keep purchasing instructions literal.

## Do's and Don'ts

### Do

- Keep the main product media at 1024px and its centered supporting text at 570px.
- Pair 43.7px bold chapter headings with 28.5px medium support, not two competing display styles.
- Use 17px cyan uppercase kickers with 0.08em tracking for chapter orientation.
- Set download pills at 67px high and preserve the icon-label construction.
- Allow roughly 72px between chapter heading group and its product demonstration.
- Keep long proof at 16px/1.6 in narrow unboxed columns.
- Use the 11px ambient-shadow panel for newsletter and editorial content.
- Keep final credentials small and left-aligned beneath the compact footer.

### Don't

- Do not make the entire page white-on-black; charcoal is a deliberate product stage against a pale reading canvas.
- Do not enlarge ordinary headlines to 100px or give every chapter the utility-page 60.1px title size.
- Do not turn testimonial prose into a wall of rounded colored cards.
- Do not use cyan as a full-page background outside self-contained media artwork.
- Do not apply 16px pricing-panel corners to every element; editorial panels use 11px and actions are pills.
- Do not promote mono lesson numerals into the site's default body face.
- Do not turn practical pricing amounts into giant isolated hero statistics.
- Do not add saturated glow halos behind every interface; the pale task specimen relies on soft neutral shadows.

## Motion and responsive

### Motion

**Observed:**

- Platform-download controls declare transform 0.24s, growing to scale(1.02) on hover/focus-visible and scale(1.01) on active.
- Text links declare color 0.2s ease-in-out; editorial tile shadows declare box-shadow 0.3s.
- Physical-product closing actions declare transform 0.2s ease-in-out and scale(0.95) on hover, focus-visible and active.
- Product film posters use explicit centered play controls; demonstration content includes moving task examples and a comparison slider.

**Transfer:**

- Preserve the gentle physical-key response of pills instead of sweeping gradients or large bounces.
- Keep demonstration motion inside the product stage so the reading hierarchy remains stable.

**Unknown:**

- The full choreography and timing of scroll-driven product scenes are not established.

### Responsive

**Observed:**

- Feature top padding follows clamp(64px, 7vw, 112px); dark-stage vertical padding follows clamp(64px, 8vw, 128px).
- Heading-to-media separation follows clamp(40px, 5vw, 72px).
- Pricing section type follows clamp(36px, 3.5vw, 50px). Download action rows declare wrapping.

**Transfer:**

- On narrow screens, retain the promise-above-specimen relationship and scale the specimen to the available width.
- Stack explanation columns and card grids without changing their reading order; keep platform labels intact as pills wrap.
- For physical objects, move the object below the copy rather than shrinking both into an unreadable side-by-side scene.

**Unknown:**

- Exact narrow-screen composition, navigation behavior and most type-size interpolation are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
