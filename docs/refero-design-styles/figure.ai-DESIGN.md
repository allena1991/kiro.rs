# Figure — cinema meets machinery

## Overview

An image-led industrial style that makes advanced technology feel physically present and at home in everyday life. Cool white, black and soft gray frame muted photographic films, with technical display lettering paired with an unobtrusive grotesk. The pages are sparse and cinematic rather than dashboard-like, suited to ambitious hardware, applied AI and products whose behavior is best shown rather than explained.

### Essentials

- The photograph is the headline's stage, not its illustration: full-bleed 1440×900 media chapters carry a 452px-wide text block near the bottom, inset 48px from the side and 60px from the foot. Use an equally immersive still of the product in use when film is unavailable.
- Headlines behave like technical subtitles: regular 28px display lettering, 1.11 line height, normal tracking and uppercase, paired with 17px/1.6 grotesk support. Reserve monumental 122px names for the white product-portrait variant.
- Actions look like controls laid over film: transparent 49px-high outlines, 1px white edges, 12px corners and 20px horizontal padding; the black 46px-high pill belongs inside the newsletter field, not everywhere.
- Color belongs to the world being filmed: the marketing interface is overwhelmingly black, white and gray, with no broad chromatic fills. Tiny multicolor arrow details may punctuate links; muted natural color remains inside photography.
- End with a translucent directory rather than a small utility footer: 75% white with 10px backdrop blur, a prominent wordmark, a 452×58px email capsule and numbered 52px directory links separated by 1px rules.
- Alternate tactile close-ups with lived-in context: soft fabric, reflective dark surfaces and cool daylight fill the screen; text remains a small, grounded overlay. Preserve the monumental imagery and numbered closing directory on every new landing page, using original product photography or a carefully lit still-life as the minimum equivalent.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0c0c0c` | `--color-ink` | text, background, action | Primary text on light sections, solid newsletter action and dark product bands. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, border, surface | Light canvas, media-overlay text and outlined actions; also the footer veil at 75% opacity. |
| Separator gray | `#cecece` | `--color-rule` | border | Visible result of near-black at 20% over white; directory and listing separators. On the translucent footer the same alpha rule follows the underlying scene. |
| Field label gray | `#6e6e6e` | `--color-input-muted` | text | Email label, rendered with rgba(13,13,13,0.6) over white. |
| Secondary gray | `#6d6d6d` | `--color-secondary` | text, border | Visible result of near-black at 60% on white; specifications, subdued captions and legal links. |
| Media black | `#000000` | `--color-media-black` | background | Backing for edge-to-edge film and photographic chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| network participation pages | Map charcoal | `#1c1c1c` | `--color-map-charcoal` | background | Dark data-map stage. |
| app acquisition pages | Warm white | `#f6f6ef` | `--color-warm-white` | text, border | Download-stage headline, support text and badge edges. |

## Typography

- **pp-neue-machina-plain** — Technical headlines, directory links, navigation and numerical displays. A mechanical display sans with distinctive engineered terminals and occasional slab-like details; not a conventional monospace. OpenType features: "ss12". If unavailable, use **Space Grotesk**. Use regular 400; preserve the open width and engineered letter shapes. Font stack: "pp-neue-machina-plain", "Space Grotesk", sans-serif.
- **neue-haas-grot-text** — Supporting prose, newsletter, action labels and listing details. Restrained neo-grotesk, regular for reading and medium for controls. If unavailable, use **Inter**. Use 400 and 500 with the specified tight tracking. Font stack: "neue-haas-grot-text", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| directory | pp-neue-machina-plain | 400 | 52px | 1.11 | normal, uppercase, features "ss12" | fixed | Large numbered navigation in the closing directory. |
| chapter-heading | pp-neue-machina-plain | 400 | 28px | 1.11 | normal, uppercase, features "ss12" | fixed | Default hero and image-chapter headline; typically one or two lines. |
| small-heading | neue-haas-grot-text | 400 | 22px | 1.1 | -0.01em, features "ss12" | fixed | Newsletter heading and concise centered support headings. |
| body | neue-haas-grot-text | 400 | 17px | 1.6 | -0.01em | fixed | Image-chapter supporting paragraphs. |
| body-small | neue-haas-grot-text | 400 | 16px | 1.5 | -0.01em | fixed | Newsletter description, compact explanatory paragraphs and subdued utility links. |
| action | neue-haas-grot-text | 500 | 14px | 1.2 | normal | fixed | Outline buttons, newsletter button and small contact action. |
| navigation | pp-neue-machina-plain | 400 | 14px | 1 | 0.02em, uppercase, features "ss12" | fixed | Compact labels in the top navigation. |
| field-label | neue-haas-grot-text | 400 | 14px | 1 | -0.01em | fixed | Email input label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| hardware detail pages | product-name | pp-neue-machina-plain | 400 | 122px | 1 | -0.01em, uppercase, features "ss12" | fixed | Monumental name beside a white-background product portrait. |
| network participation pages | proof-number | pp-neue-machina-plain | 400 | 100px | 1 | -0.01em, features "ss12" | fixed | Four-column numerical proof over a dark media mosaic. |
| app acquisition pages | download-heading | pp-neue-machina-plain | 400 | 85px | 1 | -0.01em, uppercase, features "ss12" | fixed | Large acquisition call beside a product device. |
| specification and app demonstration sections | spec-value | pp-neue-machina-plain | 400 | 52px | 1.11 | normal, features "ss12" | fixed | Right-aligned specifications; also centered app-benefit heading at the same scale. |
| recruitment and directory pages | listing-heading | pp-neue-machina-plain | 400 | 52px | 1.1 | normal, uppercase, features "ss12" | fixed | Expandable category heading with superscript count. |
| recruitment pages | listing-title | neue-haas-grot-text | 400 | 22px | 1.1 | -0.01em, uppercase, features "ss12" | fixed | Role title in an expanded category. |
| technical media libraries | media-title | neue-haas-grot-text | 400 | 19px | 1.6 | -0.01em, uppercase, features "ss12" | fixed | Bottom-aligned title on an editorial film tile. |
| hardware specifications | spec-label | neue-haas-grot-text | 500 | 14.4px | 1.2 | normal | size max(1vw, 1.4rem) | Small title above each specification value. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Weight stays regular even at monumental scale; size and placement, not boldness, establish hierarchy.
- The display face uses stylistic set ss12. Supporting grotesk text usually has -0.01em tracking; navigation instead opens to 0.02em.
- Default landing-page headings are deliberately smaller than closing-directory links. Do not promote every headline to the special product-name scale.

## Layout

**Density:** Airy at page scale, with nearly screen-height image chapters and compact caption-like content groups.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Newsletter heading to description and specification label/value gap. | max(0.5vw, 0.8rem) |
| 16px | Chapter headline to supporting paragraph. | fixed |
| 20px | Action groups, directory-row vertical padding and app badge gap. | fixed |
| 24px | Newsletter description to field and button label to arrow. | fixed |
| 40px | Text-to-action gap in text-led sections and recurring grid gap. | fixed |
| 48px | Desktop side gutters and editorial tile caption inset. | fixed |
| 56px | Top-navigation link spacing. | fixed |
| 60px | Media-chapter bottom inset and closing-directory column gap. | fixed |
| 80px | Wordmark to newsletter and social group to contact action. | fixed |
| 98px | Closing-directory top padding and navigation height. | fixed |
| 160px | Separation around recruitment listings and large technical artwork. | fixed |

### Containers and grids

- **full-bleed-stage**: max width 1440px · side padding 0px. Edge-to-edge media with a 900px desktop chapter height; the stage follows the viewport rather than a narrow content card.
- **content-inset**: max width 1344px · side padding 48px. Shared alignment for overlay captions, controls and directory edges at the desktop reference width.
- **chapter-caption**: max width 452px. Narrow text block placed on whichever side leaves the media subject unobstructed.
- **closing-directory**: 2 columns · gap 60px. Equal 642px columns within the content inset; identity and newsletter left, numbered links right.
- **listing-layout** (only for recruitment pages): max width 928px · side padding 48px. Right-hand category list with a narrow explanatory rail left; list starts about one third into the page.
- **phone-triptych** (only for app demonstration sections): max width 1006px · 3 columns · gap 60px. Three 295px-wide portrait devices centered beneath an introduction.
- **proof-grid** (only for network participation pages): 4 columns · gap 16px. Widely distributed automatic-width numerical columns over a darkened film mosaic.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | outline-actions | 12px |
|  | newsletter-field | 29px |
|  | newsletter-button | 24px |
| app acquisition pages | store-badges | 8px |
| technical media libraries | carousel-next | 50% |

## Surfaces and depth

### Surfaces

#### Media stage · level 0

**Use:** Default landing-page canvas for cinematic chapters.

**CSS:** `background: #000000; position: relative; overflow: hidden`

**Observed:** Full-bleed media covers its backing; dark tonal falloff at the foot keeps white captions legible.

**Transfer:** Make media the surface rather than placing it inside a bordered panel.

#### White technical canvas · level 0

**Use:** Clean interruption for product anatomy, technical introductions and structured lists.

**CSS:** `background: #ffffff; color: #0c0c0c`

**Observed:** Flush white fields, no ornamental border, no raised-card shadows.

**Transfer:** Use for factual material that benefits from stillness between films.

#### Frosted closing directory · level 1

**Use:** Signature closing navigation and subscription area.

**CSS:** `background: rgba(255, 255, 255, 0.75); backdrop-filter: blur(10px); padding: 98px 48px 40px`

**Observed:** A large softened product silhouette remains visible through the veil. On informational or app pages the closing area reads as a flatter pale gray instead.

**Transfer:** Continue a product portrait behind the directory and soften it into atmosphere; use a subdued neutral backing for text-heavy page types.

#### Navigation haze · level 2

**Use:** Fixed top navigation backing.

**CSS:** `backdrop-filter: blur(16px); mask-image: linear-gradient(#000000, rgba(0, 0, 0, 0) 100%)`

**Observed:** A shallow dark-to-transparent top haze supports small white navigation without forming a solid toolbar.

**Transfer:** Keep the visual scene continuous beneath the header.

#### Dark acquisition stage · level 0

**Only for:** app acquisition pages

**Use:** Device render, download call and numerical proof.

**CSS:** `background: #0c0c0c; color: #f6f6ef`

**Observed:** Almost-black environment with a restrained physical floor reflection under the device.

**Transfer:** Light a single device as a physical object; keep the environment neutral.

#### Data map stage · level 0

**Only for:** network participation pages

**Use:** A geographic visualization with a live contribution counter.

**CSS:** `background: #1c1c1c; overflow: hidden`

**Observed:** Oversized dark globe/map artwork and small points of light sit behind edge-aligned caption and counter.

**Transfer:** Use authentic aggregate activity, not arbitrary decorative business metrics.

## Components

### Fixed navigation

**Use:** Global navigation over image chapters.

**CSS:** `position: fixed; height: 98px; width: 100%; padding: 28px 48px; display: flex; justify-content: space-between; align-items: center; color: #ffffff`

**Text style:** `navigation` — pp-neue-machina-plain 400 · 14px/1 · tracking 0.02em · uppercase

**Observed:** A small standalone symbol anchors the left, with six compact labels clustered right at 56px gaps. The Navigation haze is a separate backing layer.

**States:** Declared: hover text-decoration-color currentcolor; other interaction-state values are unspecified.

**Transfer:** Use a compact original symbol and short destination names rather than a bulky wordmark in the top bar.

### Outline action

**Use:** Primary action on a media chapter.

**CSS:** `display: inline-flex; align-items: center; height: 49px; padding: 0px 20px; border: 1px solid #ffffff; border-radius: 12px; color: #ffffff; background: transparent; gap: 24px`

**Text style:** `action` — neue-haas-grot-text 500 · 14px/1.2

**Observed:** Label first, small diagonal up-right arrow last. It commonly sits opposite the caption at the lower edge. A dark text and dark border variant belongs on white technical sections.

**Transfer:** Use a descriptive verb or destination; keep the button visually lighter than the scene.

### Newsletter button

**Use:** Submission control nested at the right end of the email capsule.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 46px; padding: 0px 32px; border: 1px solid #0c0c0c; border-radius: 24px; background: #0c0c0c; color: #ffffff`

**Text style:** `action` — neue-haas-grot-text 500 · 14px/1.2

**Observed:** A compact dark island inside the white field, not a standalone hero conversion style.

**States:** Declared: hover background-color transparent; color #0c0c0c; border-color #0c0c0c. Focus-visible and active values are unspecified.

### Newsletter field

**Use:** Single-line subscription form in the closing directory.

**CSS:** `display: flex; align-items: center; width: 452px; height: 58px; padding: 5px 5px 5px 24px; background: #ffffff; border: 1px solid #ffffff; border-radius: 29px`

**Text style:** `field-label` — neue-haas-grot-text 400 · 14px/1 · tracking -0.01em

**Observed:** Email label on the left, Newsletter button contained at the right; social icons sit below the whole field.

**Transfer:** Keep this one-field capsule distinct from outlined media actions.

### Numbered directory link

**Use:** Oversized closing navigation.

**CSS:** `display: flex; align-items: center; padding: 20px 0px; border-top: 1px solid rgba(12, 12, 12, 0.2); color: #0c0c0c`

**Text style:** `directory` — pp-neue-machina-plain 400 · 52px/1.11 · uppercase

**Observed:** Small two-digit index precedes a much larger uppercase label. The first row omits its top separator. The label has an animated underline rather than a painted button fill.

**Transfer:** Number meaningful destination groups; preserve the contrast between modest index and large label.

### Contact text action

**Use:** Secondary contact link beneath the subscription group.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; color: #0c0c0c; background: transparent`

**Text style:** `action` — neue-haas-grot-text 500 · 14px/1.2

**Observed:** Short label with a separate up-right arrow 12px away; the arrow carries a tiny warm multicolor highlight. A fine underline is the animation device rather than a permanent box.

### Specification row

**Only for:** hardware specifications

**Use:** Technical proof beside an oversized product image.

**CSS:** `display: flex; flex-direction: column; align-items: flex-end; justify-content: flex-end; gap: 8px; max-width: 633.6px; padding-bottom: 4.3px; border-bottom: 0.5px solid rgba(12, 12, 12, 0.6); color: #6d6d6d`

**Text style:** `spec-value` — pp-neue-machina-plain 400 · 52px/1.11

**Observed:** Small spec-label above the value, both right-aligned; rows stack with 56.2px clear gaps, leaving the image exposed at left.

**Transfer:** Use genuine concise specifications with units kept adjacent to the number.

### Category accordion

**Only for:** recruitment and directory pages

**Use:** Group a long list without turning it into cards.

**CSS:** `display: grid; grid-template-columns: 1fr 44px; align-items: center; gap: 20px; padding: 36px 0px`

**Text style:** `listing-heading` — pp-neue-machina-plain 400 · 52px/1.1 · uppercase

**Observed:** A ruled 152px category band contains an uppercase heading, a small superscript count and a 46×47px outlined circular plus control. Expanded entries use 85px rows with location, title and action; a narrow intro rail remains at left.

**Transfer:** Use for real categories and counts; allow long names to wrap without shrinking all headings.

### Editorial film tile

**Only for:** technical media libraries

**Use:** Horizontally browsable film collection.

**CSS:** `position: relative; display: flex; flex-direction: column; width: 540px; height: 676px; overflow: hidden; background: #000000`

**Text style:** `media-title` — neue-haas-grot-text 400 · 19px/1.6 · tracking -0.01em · uppercase

**Observed:** Portrait-like edge-to-edge image, darkened for legibility, bottom title and a small watch chip in a caption layer inset 48px. Tiles touch with no gap; the third is cut by the viewport. A 46px circular arrow overlays the right edge.

**Transfer:** Use behavior-oriented editorial stills, not abstract feature icons.

### Store badge

**Only for:** app acquisition pages

**Use:** Paired platform download links.

**CSS:** `width: 181px; height: 52px; border: 0.5px solid #f6f6ef; border-radius: 8px; background-size: contain; background-position: 50% 50%; background-repeat: no-repeat`

**Observed:** Official monochrome platform artwork; a pair sits in a two-column group with 20px gap. The light demonstration section uses solid dark badges.

**States:** Declared: hover box-shadow rgba(255, 255, 255, 0.36) 0px 0px 3.2rem; focus-visible and active values are unspecified.

**Transfer:** Use the platform's supplied badge artwork rather than typesetting a substitute.

## Imagery and graphics

### Cinematic physical product

**Use:** The defining image language for opening and capability chapters.

**Observed:** Extreme close-ups of fabric-covered hands and glossy dark surfaces alternate with full-body scenes in spacious homes. Cool daylight, pale concrete, glass and wood dominate; natural colors are muted, not removed. The object fills most of the image while captions occupy only a lower corner.

**Transfer:** Show the new product's most tactile or consequential interaction at architectural scale. For software, photograph a real person using the product in an uncluttered setting; a carefully art-directed still with the same light is sufficient when film is unavailable.

### Frosted closing portrait

**Use:** Atmosphere behind the closing directory.

**Observed:** An enormous front-facing product portrait continues behind the pale directory veil, reduced to a softly legible silhouette instead of a competing image.

**Transfer:** Enlarge an original product detail behind the footer; for a product without a recognizable physical shape use a soft photograph of its working environment.

**Build:** Use a full-width cover image behind the Frosted closing directory. Layer rgba(255,255,255,0.75) above it and apply backdrop-filter blur(10px). Maintain enough dark mass in the center to show through without reducing text contrast.

### White product anatomy

**Only for:** hardware detail pages

**Use:** Tall opening product portrait continuing into specifications.

**Observed:** A very large, sharply resolved product extends beyond the left and bottom edges on seamless white. Reflective black components and pale textured material give tonal contrast. A 122px name occupies the open right half; the image continues far below the first screen beside specifications.

**Transfer:** Use a high-resolution cutout or neutral studio render with believable surface detail. Reveal the physical form gradually rather than fitting the entire object into a small card.

### Soft technical particle sculpture

**Only for:** AI-system introductions

**Use:** Abstract counterpart to a physical product film on a white opening.

**Observed:** Dark rounded block-like particles form a loose twisting chain across the right two thirds; granular fuzzy edges and varied blur create depth. A crisp black wordmark and compact prose stay clear at left.

**Transfer:** Use an original abstract organization of the product's smallest meaningful units, with soft grayscale depth and clear text separation.

**Build:** Place 12–18 rounded charcoal rectangles in an SVG group following two loose diagonal or sinusoidal strands. Vary dimensions around 60–100px, apply Gaussian blurs of 8–24px, and add a low-opacity feTurbulence displacement texture. Layer a few sharper foreground units over paler blurred units on white; keep the left third mostly open.

### Human work documentary

**Only for:** recruitment and participation pages

**Use:** Openings and audience-use-case chapters.

**Observed:** People and products share real offices, homes and workspaces; wide shots communicate participation, while overhead or first-person views show tasks. Soft natural light, restrained saturation and dark lower overlays unify otherwise different locations.

**Transfer:** Photograph real work and the people involved, not celebratory stock-office poses.

### Globe and activity mosaic

**Only for:** network participation pages

**Use:** Show geographic reach and aggregate activity before acquisition.

**Observed:** A dark globe carries many fine lights with a large live counter near a lower edge. A separate 6×6 field of 240×150px video cells backs a four-number proof group; a dark tonal veil gives the numbers priority.

**Transfer:** Render a geographically meaningful activity field or a mosaic of real outputs; counters must represent actual data.

**Build:** For the map, use a charcoal sphere with a faint geographic dot mask and sparse white points at low opacity; brighter points indicate real locations. For the mosaic, use a gapless six-column CSS grid of muted landscape stills, then an rgba(12,12,12,0.5) lower gradient and four aligned proof columns.

### Device studio and triptych

**Only for:** app acquisition pages

**Use:** Download call followed by a clearer interface demonstration.

**Observed:** One upright phone is physically lit against near-black with a soft pool of reflected light at its base. A separate white section centers three realistic phones with equal 60px gaps; their screens contain muted photography and pale translucent UI.

**Transfer:** Use real screens in consistent device frames. Keep marketing typography outside the screens; do not turn the whole page into the interface.

**Build:** Place a front-facing device render at right on near-black; beneath it use a low-opacity white ellipse with a 30–50px blur to suggest bounced light, not a colored glow. For the triptych, align three equal portrait frames to a shared baseline.

### Icons

**Observed:** Thin up-right arrows accompany actions: 12×13px at 1px stroke on media controls, 14×15px at 1.5px stroke on contact/list actions. Carousel next uses a simple horizontal arrow inside a 46px circle. Social symbols are small solid black marks, not boxed badges.

**Transfer:** Choose sparse utility arrows with squared or butt line caps. Do not add an illustrated icon to every chapter; the imagery does the explanatory work.

## Section recipes

How recurring sections are built.

### First screen: Cinematic subtitle opening

**Observed:** A 900px-tall full-width Media stage starts behind the Fixed navigation. Back to front: black backing, cover film of a dramatically enlarged tactile product detail, subtle dark foot shading, then white text and outlined control. The main object occupies most of the central and right field. The uppercase chapter-heading is only 28px and wraps within a 452px caption block at lower left, followed by a 17px support paragraph with a 16px gap. The Outline action is anchored at lower right, aligned to the same 60px bottom inset. Within the first 900px the navigation, main object, full promise, support and action are all visible; the next media chapter starts below the fold.

**Transfer:** Use an original hero film or strong full-bleed still demonstrating a tactile or meaningful interaction; preserve the small subtitle and opposite-corner action rather than compensating with giant text. Hardware-detail openings instead use White product anatomy with a 122px name. AI-system introductions use Soft technical particle sculpture and a compact left text stack; recruitment opens with people at work; app campaigns may introduce a product wordmark above the caption.

**Avoid:** Do not split the default opening into a centered giant slogan plus a contained video rectangle, or place the action directly beneath the headline when the scene has room for the opposite-corner composition.

**Text style:** `chapter-heading` — pp-neue-machina-plain 400 · 28px/1.11 · uppercase

### Alternating media chapter

**Observed:** A full-screen Media stage follows another without a card gap. Caption stays within 452px, 48px from a side, 60px above the bottom. Left and right placements alternate to protect the subject; the action may occupy the opposite corner or be absent when the chapter simply demonstrates behavior.

**Transfer:** Give each chapter one visible behavior and one explanatory sentence; choose caption side according to image composition.

**Text style:** `chapter-heading` — pp-neue-machina-plain 400 · 28px/1.11 · uppercase

### Portrait closing call

**Observed:** A final 900px photographic stage carries a small lower-left chapter-heading, support copy and a single Outline action. It flows into the Frosted closing directory, whose softer portrait echoes the image above.

**Transfer:** Finish the narrative with a human invitation or forward-looking promise, not another dense feature grid. Keep the same original photographic world as the rest of the page.

**Text style:** `chapter-heading` — pp-neue-machina-plain 400 · 28px/1.11 · uppercase

### Translucent numbered ending

**Observed:** The Frosted closing directory is about 817px high at desktop. Two equal columns are separated by 60px. Left: a prominent wide wordmark around 462×69px, 80px breathing room, small newsletter heading, description, Newsletter field, social symbols and Contact text action. Right: six numbered directory rows at 52px with fine separators. A final utility line sits near the foot with copyright left and underlined legal links right.

**Transfer:** Always provide the numbered, oversized directory and prominent identity as a memorable ending. Use your own destination structure and wordmark; preserve the hierarchy even when the link count changes.

**Text style:** `directory` — pp-neue-machina-plain 400 · 52px/1.11 · uppercase

### Anatomy and ruled proof

**Only for:** hardware detail pages

**Observed:** White product anatomy spans a long continuous section. The opening name is on the right; farther down, Specification rows occupy the right side beside the enlarged left image. A compact 28px heading and body pair closes the anatomy section at the lower right before film resumes.

**Transfer:** Let the image establish form, then attach concise measurable attributes; avoid building a separate boxed card for each specification.

**Text style:** `product-name` — pp-neue-machina-plain 400 · 122px/1 · tracking -0.01em · uppercase

### Technical invitation and film library

**Only for:** AI-system and technical library pages

**Observed:** A 28px technical invitation on white spans up to 690px, followed 40px later by two dark Outline actions. A broad animated graphic separates the invitation from the edge-to-edge Editorial film tile carousel. The carousel uses touching 540×676px tiles with bottom captions and a circular next control.

**Transfer:** Connect a short technical claim to deeper resources, then offer tangible examples in a browsable film strip.

**Text style:** `chapter-heading` — pp-neue-machina-plain 400 · 28px/1.11 · uppercase

### Ruled category directory

**Only for:** recruitment and directory pages

**Observed:** Following the photographic opener, a white content area has a compact 28px heading and 16px explanation in a left rail, with a 928px-wide Category accordion at right. Categories are uppercase 52px with superscript counts and circular plus marks; legal or contextual prose sits beneath the list before the shared closing directory.

**Transfer:** Use this structure for a genuine long categorized inventory; the left rail explains how to choose, while the right gives access.

**Text style:** `listing-heading` — pp-neue-machina-plain 400 · 52px/1.1 · uppercase

### Network proof and acquisition

**Only for:** app acquisition and participation pages

**Observed:** A dark geographic field and live counter establish scale. Audience scenes use either paired half-width films or full-width chapters. A dark media mosaic carries four 100px numbers. The acquisition stage pairs an 85px call and store badges at left with one upright device at right; a white demonstration follows with a centered 52px heading, 22px support line and three phones.

**Transfer:** Show who participates, what they do and why it matters before asking for a download. Use only the proof and device arrangements suited to the product.

**Text style:** `download-heading` — pp-neue-machina-plain 400 · 85px/1 · tracking -0.01em · uppercase

## Page flow

**Storyline:** Visible promise → behavior in context → supporting capability or quantified proof → invitation → oversized directory ending.

### Broad marketing landing page

1. **Promise** — Immersive product-detail film with small lower-left promise and opposite-corner action.
2. **Capability demonstration** — Successive edge-to-edge scenes shift between the intelligence of the product and its everyday behavior.
3. **Closing invitation** — A human-centered portrait chapter with one action.
4. **Persistent wayfinding** — Frosted identity, subscription and numbered directory.

**Transfer:** Let the visual narrative introduce an unfamiliar product with very little text; use the shared ending as the stable destination.

### Recruitment or categorized opportunity page

1. **Shared mission** — Full-screen workplace film and a short invitation.
2. **Available paths** — Left introductory rail, right category accordions with counts and detailed rows.
3. **Context and assurance** — Compact policy or eligibility prose below the list.
4. **Persistent wayfinding** — Pale numbered closing directory with subscription.

**Transfer:** Pair an emotional opening with a highly practical structured list, not another long lifestyle story.

### Hardware product detail

1. **Product identity** — Seamless white oversized portrait with monumental name on the open side.
2. **Quantified proof** — Right-aligned ruled specifications beside the continuing product form.
3. **Capability demonstration** — Compact interaction statement followed by full-screen contextual films.
4. **Closing invitation** — Portrait call leading into the frosted directory.

**Transfer:** Use a studio anatomy sequence when physical form and specifications are central, then prove behavior in the real world.

### Technical system introduction

1. **Concept introduction** — Crisp left wordmark and short prose against a fuzzy grayscale particle sculpture.
2. **Product demonstration** — Full-width real-world film with a lower-corner technical statement.
3. **Deeper explanation** — White invitation, paired resource links and broad animated graphic.
4. **Case evidence** — Touching editorial video tiles in a horizontally browsable strip.
5. **Closing invitation** — Portrait call and frosted numbered ending.

**Transfer:** Balance abstract system identity with concrete demonstrations and optional-depth resources.

### App acquisition and participation campaign

1. **Introduction** — Human task film with an introducing label and large original wordmark.
2. **Scale and participation** — Dark geographic activity field, then split and full-width audience scenes.
3. **Quantified proof** — Gapless video mosaic with four large statistics.
4. **Conversion** — Dark device stage and platform download badges.
5. **Product demonstration** — White three-device presentation with a centered benefit heading.
6. **Future promise** — Final film statement followed by pale directory and newsletter.

**Transfer:** Make participation comprehensible before conversion; use devices and verified network activity as scoped proof tools.

## Writing

Confident, plainspoken and forward-looking. Complex engineering is described through recognizable actions and environments rather than exuberant startup language.

**Do not copy:** Do not reuse Figure, Figure 03, Helix or Index names, logos, photographs, proprietary claims, team credentials, dataset totals, job counts or numerical specifications. Replace all claims and proof with the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader's world; we for invitations and service commitments. Refer to the product by name when explaining what it can do.
- **Rhythm:** Headlines tend to be short declarative phrases of 5–10 words. Support is usually one or two direct sentences. Actions are two to five words. Longer technical explanation is kept in a small reading block, not inflated into a slogan.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Announce an everyday change in a matter-of-fact sentence. | 5–10 words | “The future of home help is here” |
| Capability headline | Describe an understandable behavior using a familiar comparison. | 5–10 words | “Understands your home like you do”<br>“Made to move through our world” |
| Supporting paragraph | Name the product, explain its job, and connect it to an ordinary setting. | One or two sentences | “Talk, ask, or delegate—[Brand] understands and takes action.” |
| Action | Name the destination or the thing to watch rather than offering a generic start. | 2–5 words | “Full Video”<br>“See All Open Roles” |
| Closing invitation | Use direct, unceremonious language to keep the relationship open. | 3–6 words | “Keep up with us” |
| Forward promise | Contrast a useful present with a plausible next step. | Two short parallel clauses | “TODAY, SERVICES ON DEMAND. SOON, ROBOTS ON DEMAND.” |

**Words and phrasing to use:** every day; real world; learns; understands; takes action; explore; join; designed to; engineered for

**Avoid:** revolutionary game-changer; magic; supercharge; 10x everything; disrupt; limitless possibilities

**Rules:**

- Lead with a visible behavior, then explain the mechanism only when useful.
- Keep technical specificity in short support paragraphs and deeper-resource links.
- Use uppercase as visual treatment, not as an excuse for a shouting tone.
- Pair forward-looking promises with current concrete capability.

## Do's and Don'ts

### Do

- Use 28px regular display headlines over films, with 17px/1.6 support.
- Align desktop media captions and controls to 48px side gutters and a 60px bottom inset.
- Keep overlay text within a 452px measure so the scene dominates.
- Retain 12px outlined action corners and reserve the 24px pill for newsletter submission.
- Make the closing directory's 52px links more prominent than its 22px newsletter heading.
- Keep separators thin: 1px for directory rows and 0.5px for hardware specification rules.
- Use a mix of intimate material detail and wider contextual footage.
- Provide a large original identity mark and numbered navigation in the ending.

### Don't

- Do not apply the 122px hardware-name recipe to ordinary chapter headlines.
- Do not make media chapters into rounded cards with gutters; their edges meet the viewport.
- Do not fill marketing bands with bright brand-color gradients; the interface stays neutral.
- Do not add elevation shadows to the ruled listing and directory structures.
- Do not treat the newsletter's 29px field radius as a universal panel radius.
- Do not use bold grotesk headings as a replacement for the regular mechanical display face.
- Do not let a busy image run unshaded behind the lower white caption.
- Do not reproduce fine-grained app interface styling as the marketing website's component system.

## Motion and responsive

### Motion

**Observed:**

- Action color, background and border transitions are declared at 0.3s ease-in-out.
- Directory underline background-size and contact underline transitions are declared at 0.3s ease-in-out.
- Newsletter label top, transform, color and font-size transitions are declared at 0.3s ease-in-out.
- Video chapters, a horizontal film carousel and an animated technical graphic are present; a map counter tick is declared at 1s ease.

**Transfer:**

- Keep control feedback restrained and short; let the large moving imagery carry the expressive motion.
- Preserve continuous full-bleed framing while films move, and keep overlay captions readable.

**Unknown:**

- Exact film playback behavior, scroll synchronization and animated graphic choreography are unspecified.
- Focus-visible and active styling are not established for most controls.

### Responsive

**Observed:**

- Styles declare width thresholds around 370px, 480px, 768px, 1024px, 1280px and 1440px.
- Specification labels use max(1vw, 1.4rem); tight specification gaps use max(0.5vw, 0.8rem).

**Transfer:**

- On narrow screens, retain the cover-image stage and a protected caption area; choose a portrait crop that keeps the meaningful interaction visible.
- As a layout adaptation, stack identity/newsletter before numbered directory links and collapse phone demonstrations without shrinking screen content to illegibility.

**Unknown:**

- Only the desktop composition is established; narrow-screen gutter sizes, navigation replacement and exact reflow rules are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
