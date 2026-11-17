# Paste — warm device theatre

## Overview

A friendly, Apple-adjacent product style with bold system sans headlines, cool blue actions and expansive white and pale gray space. Warm amber device scenes and colorful interface collections supply most of the visual richness, with occasional near-black chapters creating a cinematic change of pace. It suits polished consumer software and cross-device tools whose everyday utility can be shown rather than diagrammed; the overall density is low even when the product imagery is full of detail.

### Essentials

- The promise reads like a confident two-line product label: centered system-ui at 60px/62px, weight 700 and 0.6px tracking, within an 840px text measure.
- The opening is a product stage rather than a split sales layout: 144px top space, 16px headline-to-lead gap, 32px to actions and 32px to a 1200×675px device composition that continues below the first screen.
- Actions look like native controls enlarged for a showroom: blue #0a84ff pills, 48px tall with 32px horizontal padding, paired with a 1.5px inset-outline pill and separated by 16px.
- Color belongs inside the demonstration: most page area is #ffffff or #f5f5f7, while warm amber fills device displays and selected 32px-radius media panels. Near-black #101010 is reserved for immersive capability chapters and the footer, not the default canvas.
- Oversized product proof is a signature device: a 1200px-wide rounded demonstration panel, an adjacent carousel slide peeking beyond a 24px gap, and a colorful edge-bleeding collection of product artifacts. Use representative outputs or documents if the new product has no device interface.
- The warm focal light interrupts the neutral rhythm: a golden sculptural object and restrained 135px-blurred amber halo sit within a dark capability chapter. Recreate it with a layered amber medallion if bespoke 3D art is unavailable.
- The ending returns to an uncomplicated invitation: 60px bold centered headline, 24px support line, blue pill action and 144px section padding, followed by a compact near-black multi-column footer. A company-story variant instead ends with a personal statement and handwritten sign-off.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#0a84ff` | `--color-action` | action, link | Main pill fills, outlined action text and focus outlines. |
| Golden light | `#ffb250` | `--color-gold` | accent, border | Amber outlined action and low-opacity glow in the dark sculptural capability chapter. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bright panel blue | `#2997ff` | `--color-bright-blue` | surface, action | Primary action hover and selected feature or offer panels; use the action blue as the default button fill. |
| Warm amber panel | `#feb85c` | `--color-amber-panel` | surface | Warm carousel media backing; warmth also carries through device imagery. |
| Amber shadow core | `#513705` | `--color-glow-core` | accent | Blurred dark gold beneath the central luminous object; not a flat panel color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#101010` | `--color-ink` | text, background | Primary text and immersive dark bands, including the footer. |
| Dark control fill | `#363636` | `--color-inverse-edge` | surface, border | Visible rgba(255,255,255,0.16) on near-black for segmented tracks and footer rules. |
| Secondary gray | `#707070` | `--color-secondary` | text | Visible result of rgba(16,16,16,0.6) on white for supporting copy; preserve the alpha when placed on other surfaces. |
| Inverse muted | `#9f9f9f` | `--color-inverse-muted` | text | Visible rgba(255,255,255,0.6) on near-black for footer navigation and social symbols. |
| Inverse support | `#cfcfcf` | `--color-inverse-secondary` | text | Visible rgba(255,255,255,0.8) on near-black for dark chapter support copy. |
| Light hairline | `#e2e2e2` | `--color-edge` | border | Visible rgba(16,16,16,0.12) over white; FAQ separators and lightly outlined demonstration frames. |
| Light control fill | `#ececec` | `--color-soft-control` | surface | Visible rgba(16,16,16,0.08) over white for neutral segmented controls and carousel arrows. |
| Cool pale gray | `#f5f5f7` | `--color-subtle` | background, surface | Alternating bands, product panels and testimonial cards. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, raised cards on pale bands and primary inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience chapters and trial explainer cards | Category blue | `#0088ff` | `--color-category-blue` | text, accent | Audience eyebrow and blue illustrative feature icons. |
| pricing pages | Offer orange | `#ff8d28` | `--color-offer-orange` | surface | Small contrasting offer badge above a blue plan card. |
| audience chapters | Category red | `#ff383c` | `--color-category-red` | text | Creative audience eyebrow. |
| audience chapters | Category purple | `#cb30e0` | `--color-category-purple` | text | Technical audience eyebrow. |
| audience chapters | Category green | `#34c759` | `--color-category-green` | text | Communication audience eyebrow. |
| audience feature mosaics | Purple panel start | `#541fa1` | `--color-purple-start` | surface | Start of a 135deg purple-to-magenta feature panel. |
| audience feature mosaics | Purple panel end | `#b343af` | `--color-purple-end` | surface | End of the purple feature-panel gradient. |
| audience feature mosaics | Violet charcoal | `#595667` | `--color-charcoal` | surface | A muted alternative to blue for a creative feature tile. |

## Typography

- **system-ui** — All marketing headings, paragraphs, actions and captions. Native UI sans serif with a sturdy bold display cut, open regular supporting copy and tightly set small controls. Font stack: "system-ui", -apple-system, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | system-ui | 700 | 60px | 62px | 0.01em | Hero promises, major proof headings and closing invitations. |
| chapter | system-ui | 700 | 54px | 52px | 0.0111em | Core product capability headings; deliberately denser than the display recipe. |
| heading | system-ui | 700 | 40px | 42px | 0.015em | Large carousel captions and compact technical section headings. |
| lead | system-ui | 400 | 24px | 1.25 | 0.0125em | Centered explanatory lines beneath large headings; also the prose in company-story tiles. |
| opening-quote | system-ui | 400 | 22px | 28px | -0.018em | A compact editorial endorsement below the opening product stage. |
| action | system-ui | 590 | 20px | 0.8 | -0.01em | Large pill labels, wordmark text and footer column headings. |
| body | system-ui | 400 | 18px | 26px | -0.028em | Feature descriptions, testimonial quotes and short prompt examples. |
| person | system-ui | 590 | 18px | 24px | -0.022em | Testimonial attribution names. |
| caption | system-ui | 400 | 16px | 1.5 | -0.022em | Attribution descriptions and secondary pricing notes. |
| menu | system-ui | 500 | 15px | 20px | -0.04em | Header and footer links, compact navigation CTA and segmented options. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience mosaics and pricing pages | tile-heading | system-ui | 700 | 32px | 1.125 | 0.0187em | Centered feature-tile headings and plan names. |
| feature grids, FAQs and technical detail pages | card-title | system-ui | 700 | 22px | 26px | -0.018em | Feature explanations, FAQ questions and copyable prompt titles. |
| FAQs and setup instructions | answer | system-ui | 400 | 18px | 30px | -0.033em | Expanded FAQ answers and inline setup resource links. |
| audience chapters | eyebrow | system-ui | 700 | 16px | 1.25 | 0.006em, uppercase | Short color-coded audience designation above the promise. |
| pricing pages | offer-caption | system-ui | 500 | 14px | 18px | -0.025em | Tiny promotional badge attached to an offer panel. |

**Notes:**

- Keep the system sans throughout rather than introducing a decorative display family. The contrast comes from weight, scale and the imagery.
- Large bold headings carry slightly positive tracking, including the unusually tight 54px/52px chapter recipe. Small navigation, quotes and card copy tighten instead.
- The 60px display recipe is also used late in the page; do not progressively shrink every section heading. The compact technical variant uses 40px section headings while retaining a 60px opening and closing.
- Keep lead paragraphs regular and muted. Bold text belongs to the promise, short card title or attribution, not entire explanatory paragraphs.

## Layout

**Density:** Airy: short centered copy is separated from broad product demonstrations by substantial vertical intervals; card interiors are comparatively compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card title-to-description gap and footer link-list gap. |
| 12px | Small badge horizontal padding and compact list rhythm. |
| 16px | Heading-to-lead gap and paired-action gap. |
| 20px | Container side padding, testimonial padding and compact CTA horizontal padding. |
| 24px | Default card-grid gutter and footer column title-to-list gap. |
| 32px | Copy-to-action and opening action-to-media gaps; compact feature-card padding. |
| 48px | Large card inner padding, footer top and bottom padding and carousel-to-controls interval. |
| 64px | Capability action-to-demonstration gap, large card bottom padding and artwork-to-action separation. |
| 96px | Major heading-to-content interval; alternate shorter chapter top padding. |
| 144px | Default major section top and bottom padding. |

### Containers and grids

- **page-container**: max width 1240px · side padding 20px. Centered outer container; at 1440px its content occupies 1200px with 120px visible margins.
- **text-measure**: max width 840px. Centered heading and lead blocks, FAQ lists, offer panels and compact technical grids.
- **feature-pair**: max width 840px · 2 columns · gap 24px. Two 408px feature cards per row; suitable for compact product capabilities and prompts.
- **proof-columns**: max width 1200px · 3 columns · gap 24px. 384px-wide independent testimonial columns, not rows of equal-height cards.
- **story-pair** (only for company-story pages): max width 1200px · 2 columns · gap 24px. Two 588px-wide company-story cards with a 480px minimum height.
- **text-feature-grid** (only for audience chapter details): max width 840px · 2 columns · gap 64px. Two 388px text features with icon, title and compact paragraph.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | feature-panels | 32px |
|  | testimonial-cards | 20px |
| integration detail openings | technical-badge | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | action-outline | `0px 0px 0px 1.5px #0a84ff inset` | Secondary pill action. |
| company-story pages | blue-story-glow | `0px 0px 100px 0px rgba(115,173,250,0.35)` | A diffuse cool halo behind company-story cards, without a dark drop shadow. |
| integration detail pages | fine-demo-outline | `0px 0px 0px 1px rgba(16,16,16,0.12)` | Subtle edge around a large integration demonstration frame. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and capability-section ground.

**CSS:** `background: #ffffff; color: #101010`

#### Pale band · level 0

**Use:** Carousel, closing-call and explanatory section backing.

**CSS:** `background: #f5f5f7; color: #101010`

**Observed:** Broad full-width bands alternate with white rather than every section becoming a separate card.

#### Dark theatre · level 0

**Use:** Immersive capability chapters and the footer.

**CSS:** `background: #101010; color: #ffffff`

**Observed:** Dark content uses white headings and 80% white support text; the footer dims navigation to 60% white.

**Transfer:** Switch the entire chapter, including the demonstration backing, instead of placing a small dark box in an otherwise light row.

#### Rounded media panel · level 1

**Use:** Large product demonstrations and feature cards.

**CSS:** `background: #f5f5f7; border-radius: 32px; overflow: hidden; box-shadow: none`

**Observed:** The default is pale on white; the carousel reverses to white on pale gray and includes a warm amber variant.

**Transfer:** Let realistic interface imagery provide texture; keep the outer material flat and restrained.

#### Story glow card · level 1

**Only for:** company-story pages

**Use:** Illustrated narrative tiles.

**CSS:** `background: #ffffff; border-radius: 32px; box-shadow: 0px 0px 100px 0px rgba(115,173,250,0.35); overflow: hidden`

**Observed:** The blue halo unifies white, dark illustrated and bright blue cards in a two-column narrative.

#### Integration atmosphere · level 0

**Only for:** integration detail openings

**Use:** Low-contrast colored light under a pale technical hero.

**CSS:** `background-color: #f5f5f7; background-image: radial-gradient(80% 54% at 5% 118%, rgba(255,236,214,0.6), rgba(0,0,0,0) 74%), radial-gradient(80% 54% at 95% 118%, rgba(216,227,251,0.42), rgba(0,0,0,0) 74%)`

**Observed:** Warm light enters from below left and cool light from below right; the heading area remains almost neutral.

#### Audience colored tile · level 1

**Only for:** audience feature mosaics

**Use:** A vivid capability card within a small two-column mosaic.

**CSS:** `background: linear-gradient(135deg, #541fa1, #b343af); border-radius: 32px; overflow: hidden; color: #ffffff`

**Observed:** Other mosaic tiles use bright blue, pale gray and violet charcoal. Contrast changes with the fill, not with the audience eyebrow color alone.

## Components

### Navigation

**Use:** Persistent brand, site routes and compact conversion action.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 72px; z-index: 50`

**Text style:** `menu` — system-ui 500 · 15px/20px · tracking -0.04em

**Observed:** Brand symbol and wordmark sit left, a six-link navigation group is centered with 32px gaps, and a compact blue CTA sits right. Its CTA is 32px tall with 20px horizontal padding. The bar takes a light appearance over light content and a dark appearance over the immersive audience chapter.

**States:** Declared: hover navigation text rgba(16,16,16,0.6), compact CTA background #2997ff; focus-visible 2px solid #0a84ff outline with 2px offset.

### Primary button

**Use:** Default conversion action in openings and closings.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; min-width: 180px; padding: 0px 32px; background: #0a84ff; color: #ffffff; border-radius: 9999px`

**Text style:** `action` — system-ui 590 · 20px/0.8 · tracking -0.01em

**Observed:** Text-only pill, usually first in a centered pair; a longer capability-specific label expands the width.

**States:** Declared: hover background #2997ff; focus-visible 2px solid #0a84ff outline with 2px offset.

### Secondary button

**Use:** Plans, setup or purchase alternative beside a main action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; min-width: 180px; padding: 0px 32px; color: #0a84ff; background: transparent; border-radius: 9999px; box-shadow: 0px 0px 0px 1.5px #0a84ff inset`

**Text style:** `action` — system-ui 590 · 20px/0.8 · tracking -0.01em

**Observed:** Outline pill matches the main action's footprint. In the golden dark capability chapter it changes to a gold outline with white text.

**States:** Declared: hover color #2997ff for blue variant; focus-visible 2px solid #0a84ff outline with 2px offset.

### Carousel panel

**Use:** Large focused demonstration of one benefit at a time.

**CSS:** `display: flex; flex-direction: column; height: 640px; background: #ffffff; border-radius: 32px; overflow: hidden`

**Text style:** `heading` — system-ui 700 · 40px/42px · tracking 0.015em

**Observed:** Product media fills the upper 500px of a 1200px-wide panel. A centered benefit title and body description sit below, with 8px between them and 64px bottom padding. Neighboring slides peek past the page edge, including an amber-backed slide. Below the track are 8px pagination dots and 40px circular arrow controls.

**Transfer:** Use one demonstrable outcome per slide, with legible media rather than an abstract illustration.

### Testimonial card

**Use:** Human proof in independent masonry columns.

**CSS:** `background: #f5f5f7; border-radius: 20px; padding: 20px; margin-bottom: 24px; break-inside: avoid`

**Text style:** `body` — system-ui 400 · 18px/26px · tracking -0.028em

**Observed:** A 60px circular avatar or publication mark sits beside person and caption text, followed by the quote with 16px top separation. Card heights vary with the quote; three columns form a clipped wall with a subtle fading lower edge.

### Segmented switch

**Use:** Change the audience demonstration without leaving the chapter.

**CSS:** `display: flex; position: relative; padding: 4px; height: 44px; border-radius: 9999px; background: rgba(255,255,255,0.16); overflow-x: auto`

**Text style:** `menu` — system-ui 500 · 15px/20px · tracking -0.04em

**Observed:** A white pill sits behind the active dark label; options are 36px tall with 8px vertical and 20px horizontal padding. Inactive labels use 80% white. Light-context plan selection uses a translucent black track instead.

**States:** Declared: hover inactive dark-context label #ffffff; focus-visible 2px solid #0a84ff outline with 2px offset.

### Footer

**Use:** A compact navigational landing after the final statement.

**CSS:** `background: #101010; color: #ffffff; padding: 48px 0px`

**Text style:** `menu` — system-ui 500 · 15px/20px · tracking -0.04em

**Observed:** Within the page container, a small muted brand symbol anchors the left, followed by three link columns and a social column. Column headings use the action recipe; links are 60% white with 8px gaps. A 1px 16%-white rule separates the columns from a small two-sided legal row.

**States:** Declared: hover footer links and social symbols #ffffff; focus-visible 2px solid #0a84ff outline with 2px offset.

### FAQ row

**Only for:** pricing and integration detail pages

**Use:** Objection handling in a narrow list.

**CSS:** `border-bottom: 1px solid rgba(16,16,16,0.12); max-width: 840px`

**Text style:** `card-title` — system-ui 700 · 22px/26px · tracking -0.018em

**Observed:** Native disclosure row with left-aligned bold question and right-aligned gray down chevron. Summary has 24px vertical padding and 24px gap; most closed rows are 81px tall. Expanded answers use the answer recipe, 24px bottom padding and underlined inline links; last row omits its rule.

**States:** Declared: hover inline link #2997ff and remove underline; focus-visible summary and links use 2px solid #0a84ff outline with 2px offset.

### Offer panel

**Only for:** pricing pages

**Use:** One dominant selectable offer instead of a dense comparison table.

**CSS:** `display: flex; flex-direction: column; align-items: center; max-width: 840px; gap: 32px; padding: 32px 48px 64px; border-radius: 32px; background: #2997ff; color: #ffffff; text-align: center`

**Text style:** `tile-heading` — system-ui 700 · 32px/1.125 · tracking 0.0187em

**Observed:** Centered plan icon, plan title and short descriptor lead into a segmented billing switch, 40px bold price, subdued billing note and two pills. The primary purchase pill is white with blue text; the trial pill is 16% white. A contrasting offer badge straddles the upper edge.

**Transfer:** Make one current offer easy to understand; keep billing qualifications visually subordinate to price.

### Offer badge

**Only for:** pricing pages

**Use:** Short value annotation attached to a plan.

**CSS:** `display: inline-flex; padding: 4px 12px; background: #ff8d28; color: #ffffff; border-radius: 9999px`

**Text style:** `offer-caption` — system-ui 500 · 14px/18px · tracking -0.025em

**Observed:** Centered across the top edge of the blue offer panel, rather than floating in the page margin.

### Copyable prompt card

**Only for:** integration detail pages

**Use:** Show practical example requests the user can reuse.

**CSS:** `position: relative; padding: 32px 80px 32px 32px; background: #f5f5f7; border-radius: 32px; text-align: left`

**Text style:** `card-title` — system-ui 700 · 22px/26px · tracking -0.018em

**Observed:** Short bold title, an 18px example request and a small circular copy affordance at lower right. Four cards form a two-column grid with 24px horizontal and 32px vertical gaps.

**States:** Declared: hover transform translateZ(0px) scale(1.02); focus-visible 2px solid #0a84ff outline with 2px offset.

### Setup panel

**Only for:** integration detail pages

**Use:** Explain activation with numbered steps next to a real settings view.

**CSS:** `display: flex; gap: 24px; padding: 48px; max-width: 840px; border-radius: 32px; background: #ffffff`

**Text style:** `answer` — system-ui 400 · 18px/30px · tracking -0.033em

**Observed:** Left column is a compact ordered list with 40px pale circular step numbers; supported tool links nest beneath the relevant step. Right column is a 360×348px settings image backed by warm orange light. Both sit within a single pale-band section.

## Imagery and graphics

### Warm device stage

**Use:** Dominant opening proof and large capability demonstrations.

**Observed:** A front-facing laptop is the central large object, with tablet and phone overlapping its lower sides. Orange and gold folded-ribbon wallpapers back crisp application windows; dark bezels and silver hardware keep the bright scene grounded. The 1200×675px stage is much larger than the text above and extends beyond the first fold.

**Transfer:** Stage the new product on the fewest relevant devices. Without hardware renders, layer a large desktop window with a smaller companion view over an amber ribbon backdrop; retain accurate UI and convincing object shadows.

**Build:** Use a 1200×675px stage. Place a broad central rounded dark device frame, a smaller vertical frame at the right and a medium frame at the left, all bottom-aligned. Inside, layer curved amber SVG bands from pale gold to burnt orange, then actual product views; use fine light inner edges and subtle dark contact shadows rather than large floating card shadows.

### Workflow window composition

**Use:** Capability chapters and audience-specific product proof.

**Observed:** A recognizable working application occupies most of a 1200px-wide scene. The featured product overlays it at the lower edge, while an offset amber rounded rectangle supplies backing. Some scenes omit the surrounding hardware; others show the laptop itself. The interface content is colorful and detailed but the page typography stays outside it.

**Transfer:** Show the product during one familiar task in another application. Preserve the depth order: warm backing, task window, foreground product interaction.

**Build:** Place a 32px-radius amber backing across most of a wide stage. Offset the main application window upward by roughly 64px, then overlap a horizontal product strip across its lower third. Give the windows restrained edge highlights and realistic small shadows; clip only at the media stage boundary.

### Artifact field

**Use:** A wide visual proof of many saved or produced items.

**Observed:** Rows of small colorful cards span an 1840×740px image and overflow both sides of the viewport. Red, blue, green, yellow and magenta category strips unify assorted links, images, documents and notes. Several muted cards carry bright green lock symbols; the white field stays airy around the collection.

**Transfer:** Make a field of the new product's real artifacts, including a few representative protected or special-state examples. The minimum equivalent is three offset rows of varied thumbnail cards extending beyond both edges.

**Build:** Create an overflow-hidden full-width stage containing an 1840px-wide inner grid centered on the page. Use three offset rows of roughly 196px square cards with 20px–24px gutters, rounded corners, colored narrow headers and mixed image/text bodies. Overlay a small circular state badge on selected cards. Keep decorative saturation within the artifacts, not the surrounding band.

### Golden focal sculpture

**Use:** Signature focal artwork in the dark immersive chapter; enlarged in a technical demonstration opening.

**Observed:** A glossy irregular amber object has a translucent gold body, molten orange edges and bright creamy specular highlights. In the dark chapter it sits between app icons connected by faint fine circuit traces; beneath it is a dark translucent prompt card over a barely visible warm pool of light. Its warm center stands out against near-black without turning the whole background orange.

**Transfer:** Use a distinctive new-product token with the same warm, tactile light. The minimum acceptable equivalent is a layered SVG amber medallion with an asymmetrical contour and believable rim highlights, not an emoji or a generic flat circle.

**Build:** Draw an irregular rounded six-lobed SVG contour in a 196×196px viewBox. Layer radial amber gradients, a darker orange rim, narrow cream highlight arcs at upper left and a translucent inner contour. Behind the small object place a 197×52px #513705 ellipse blurred 135px. Behind the prompt composition place a 680×300px rgba(255,178,80,0.08) ellipse blurred 135px. Route thin low-opacity gold SVG connectors outward to surrounding rounded app tiles; retain restrained glow rather than a broad neon outline.

### Illustrated story tiles

**Only for:** company-story pages

**Use:** A personal visual history in a two-column card narrative.

**Observed:** 588×480px rounded cards combine 24px prose with simple large imagery: a half-lit globe against dark blue-black, a monochrome platform symbol on white, product history imagery and a bright blue statement tile. A pale blue halo surrounds the grid. Some prose is top-aligned above the art, other prose is centered near the foot.

**Transfer:** Use a few meaningful objects from the new team's story, not a conventional team-headshot wall. Keep each tile to a single idea and one large visual; a simple vector object over a restrained tonal field is sufficient.

**Build:** For the globe-like tile, place an SVG circle with dark blue radial shading near the top center of a dark card and scatter tiny dim points along curved land-like paths. Fade the lower edge into the card background and reserve the lower third for centered white prose. Apply the Story glow card surface to neighboring light tiles.

### Handwritten sign-off

**Only for:** company-story endings

**Use:** A human conclusion in place of a sales CTA.

**Observed:** A large centered two-line statement is followed after 64px by a delicate 240×120px handwritten team signature image, then white space before the dark footer.

**Transfer:** Use a genuine handwritten team or founder sign-off, or a simple custom SVG monoline signature. Keep it fine, gray and much smaller than the statement.

### Icons

**Observed:** Feature and disclosure icons use simple native-looking outlines; FAQ chevrons are 32px with 2px round strokes in secondary gray. Audience feature symbols occupy 48px and trial explainer icons 64px. Header dropdown chevron is 10px with 1.4px rounded strokes. Footer social marks are 24px solid silhouettes at 60% white.

**Transfer:** Use rounded, uncomplicated system-style symbols. Reserve colored icon emphasis for explanatory grids, while navigation and disclosures stay monochrome; do not replace the tactile hero sculpture with a line icon.

## Section recipes

How recurring sections are built.

### First screen: Centered device-stage opening

**Observed:** A fixed 72px Navigation floats over the White canvas. The centered text block begins after 144px of top space, occupies an 840px measure and carries a bold two-line display promise. A muted two-line lead follows at 16px; a centered Primary button and Secondary button follow at 32px with a 16px gap. Another 32px leads into the 1200×675px Warm device stage. Back-to-front layers are white canvas, warm screen imagery, laptop/tablet/phone frames and crisp product UI; the text does not overlap the devices. Within the first 900px, the complete headline, support and action pair are visible along with the upper and middle device composition. The bottoms of the devices and the opening endorsement and rating cluster continue below the fold.

**Transfer:** Write a short outcome promise and build an equally large task or output scene if hardware is irrelevant; keep the centered scale and warm visual mass. Pricing opens with the same display-and-lead pairing above a selector and blue Offer panel. Company stories use a shorter text-only opening above illustrated tiles. Audience pages add a colored eyebrow and one large workflow scene. Integration detail openings use a small product badge, Pale band atmosphere and a rounded demonstration instead of the multi-device arrangement.

**Avoid:** Do not substitute a left-copy/right-thumbnail hero, a full-bleed orange gradient behind the headline, or a small dashboard card that leaves the lower first screen empty.

**Text style:** `display` — system-ui 700 · 60px/62px · tracking 0.01em

### Capability heading pair

**Observed:** Centered chapter heading over a muted lead in the text-measure container; 16px separates them, 32px introduces an optional action, and 64px–96px separates the copy from a full-width demonstration. Default section padding is 144px. White canvas and Pale band alternate; Dark theatre is a chapter-level change.

**Transfer:** Give each capability one outcome headline and one explanatory sentence, then prove it in a large Workflow window composition.

**Text style:** `chapter` — system-ui 700 · 54px/52px · tracking 0.0111em

### Bleeding carousel chapter

**Observed:** A centered chapter heading sits 96px above the Carousel panel track on a Pale band. A full card dominates the content width with the next card visibly peeking past a 24px gap; small dots and circular arrows sit below.

**Transfer:** Use the carousel for a small collection of substantial, separately demonstrable benefits rather than tiny text-only cards.

**Text style:** `chapter` — system-ui 700 · 54px/52px · tracking 0.0111em

### Immersive warm chapter

**Observed:** Dark theatre contains the Golden focal sculpture with related app tiles, a centered white chapter heading and inverse lead, a dark prompt-like demonstration and a gold-outlined Secondary button. The chapter uses 96px top and 144px bottom padding, with 64px between the major demonstration and action elements.

**Transfer:** Make a warm, tactile emblem the focal point of an important capability and surround it with a restrained demonstration. The sculpture and halo can express connectivity, intelligence or transformation without reproducing the original subject.

**Text style:** `chapter` — system-ui 700 · 54px/52px · tracking 0.0111em

### Human proof wall

**Observed:** A 60px centered heading sits 96px above three independent columns of Testimonial cards. The wall is clipped rather than allowed to dominate the page indefinitely; a subtle neutral fade softens the lower edge.

**Transfer:** Use genuine short quotes with attribution and allow varied heights. Preserve the person-first card construction and dense proof inside an otherwise airy section.

**Text style:** `display` — system-ui 700 · 60px/62px · tracking 0.01em

### Simple closing invitation

**Observed:** A centered 60px display line, 24px muted lead and Primary button repeat the opening hierarchy with 16px and 32px gaps. The default closing sits on a Pale band with 144px top and bottom padding and may pair the action with a Secondary button. Pricing and audience variants include a small product icon above the headline; the integration variant uses white. The Footer begins immediately after the band.

**Transfer:** Restate the core benefit or low-risk next step without introducing a new feature list. Use the same conversion label as earlier and keep the footer visually separate.

**Text style:** `display` — system-ui 700 · 60px/62px · tracking 0.01em

### Audience capability chapter

**Only for:** audience pages

**Observed:** Color-coded eyebrow, 60px display promise and 24px lead introduce a 1200px-wide workflow scene after 96px. Supporting content is either a two-column icon-and-text grid or an 840px-wide two-by-two mosaic of 408×480px rounded cards. The technical audience uses Dark theatre; other chapters use white or pale gray.

**Transfer:** Scope a chapter to a real user situation. Keep the colored eyebrow distinct from the larger illustration palette, and use a mosaic only where each benefit has clear visual proof.

**Text style:** `display` — system-ui 700 · 60px/62px · tracking 0.01em

### Trial and FAQ explanation

**Only for:** pricing and integration detail pages

**Observed:** A 60px heading and lead introduce three white 384×304px explainer cards on a Pale band, with large blue icons above 22px titles and body descriptions. The FAQ follows as an 840px list of FAQ rows with a 96px heading-to-list interval. The integration variant reduces section headings to 40px.

**Transfer:** Explain access or onboarding in short cards, then answer practical concerns in disclosures rather than adding a comparison table.

**Text style:** `display` — system-ui 700 · 60px/62px · tracking 0.01em

### Personal story conclusion

**Only for:** company-story pages

**Observed:** After the glowing two-column story grid, a centered two-line 60px statement closes on white. The Handwritten sign-off sits 64px below, with 144px lower section space before the shared Footer; no conversion button interrupts the signature.

**Transfer:** End a team or company narrative with an authentic statement of motivation and a personal mark rather than forcing the sales closing into it.

**Text style:** `display` — system-ui 700 · 60px/62px · tracking 0.01em

### Practical integration sequence

**Only for:** integration detail pages

**Observed:** An 840px two-column grid of Copyable prompt cards is followed by a Pale band with the Setup panel. A short white reassurance section uses a 40px heading and lead before the FAQ; the final invitation returns to the 60px scale.

**Transfer:** Move from example results to concrete activation and control details. Keep each phase distinct instead of mixing documentation text into the hero.

**Text style:** `heading` — system-ui 700 · 40px/42px · tracking 0.015em

## Page flow

**Storyline:** Outcome promise → large product proof → focused capability or audience chapters → trust and practical reassurance → simple final invitation → compact dark navigation.

### Flagship product landing page

1. **Promise and demonstration** — Centered two-line headline and paired pills above warm multi-device proof, followed by an editorial endorsement and small rating cluster.
2. **Capability chapters** — Pale carousel, large intelligent-workflow scene, warm sculptural dark chapter and edge-bleeding artifact field.
3. **Audience fit** — Dark chapter with a segmented audience switch and a large working-context demonstration.
4. **Social proof** — Clipped three-column wall of attributed quotes.
5. **Closing call** — Pale centered invitation with two actions, then compact dark footer.

**Transfer:** Alternate expansive demonstrations with a few contrasting chapters; preserve the tactile warm focal artwork and broad artifact proof without tying them to a fixed feature sequence.

### Offer selection and purchase reassurance

1. **Offer** — Shared centered heading above personal/team selection and one bright blue plan panel, orange badge, billing options and price.
2. **Risk reduction** — Three trial explanation cards on pale gray.
3. **Objection handling** — Narrow FAQ disclosures continue on the pale ground.
4. **Social proof** — Attributed quote masonry on white.
5. **Closing call** — Product icon and low-risk invitation on pale gray followed by the shared footer.

**Transfer:** Make the selected offer dominant and its billing qualifications clear, then answer purchase concerns before repeating the conversion.

### Personal company and product-origin story

1. **Mission** — Short centered title and one-line mission with no hero action.
2. **Origin and progress** — Two-column glowing illustrated tiles carry chronological prose, product history and recognition.
3. **Human conclusion** — Oversized statement and delicate handwritten team sign-off on white.
4. **Navigation** — Shared dark footer without a preceding trial band.

**Transfer:** Tell the new team's story through a few meaningful illustrated objects and candid prose; retain the non-sales ending.

### Demonstrate relevance to different working situations

1. **Broad promise** — Colored audience eyebrow, two-line display promise and warm workflow-window scene.
2. **Audience chapters** — Distinct light, dark and pale chapters repeat the heading-and-scene construction; details use icon grids or colored feature mosaics.
3. **Social proof** — Large centered proof heading and masonry quotes.
4. **Closing call** — Product icon, compact benefit reminder and blue pill on pale gray, then shared footer.

**Transfer:** Organize around genuinely different tasks and demonstrations, not merely different persona labels pasted onto the same scene.

### Explain and activate a focused integration capability

1. **Promise and demo** — Small integration badge, centered display promise, paired actions and a large rounded video with warm sculptural opening art over a pale atmospheric ground.
2. **Practical examples** — Four copyable request cards under a compact heading.
3. **Activation** — Numbered steps and a real settings view in one white panel on pale gray.
4. **Control and objections** — Short white reassurance section then narrow FAQ list.
5. **Closing call** — Product icon and 60px invitation on white, then shared dark footer.

**Transfer:** Stay welcoming rather than adopting a terminal-like developer aesthetic; show usable example requests and a concrete setup path.

## Writing

Confident, practical and warm, with the polish of native consumer software. Benefits are expressed as small daily reliefs, then explained plainly; the tone is neither enterprise-heavy nor aggressively playful.

**Do not copy:** Do not reuse Paste names, logos, the signature mark, proprietary product art, third-party icons as endorsements, customer identities or quotes, awards, review counts, trial duration, pricing, savings, platform coverage or privacy claims. Replace these with truthful new-product content and original assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Use the product name for direct functional statements; reserve we and our for the personal company narrative.
- **Rhythm:** Headlines are short declarative promises, often balanced across two lines. Support usually takes one or two sentences; feature copy uses direct verbs and concrete examples. Conversational fragments and contractions are welcome, exclamation marks are rare outside customer quotes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Describe the useful outcome in ordinary words; repeat a simple grammatical shape for memorability. | 6–12 words | “Everything you copy on every device”<br>“Do what you love. Do it faster with [Brand].” |
| Capability headline | Turn a technical property into a reassuring everyday benefit. | 3–9 words | “A clipboard that thinks ahead”<br>“Private by design”<br>“You stay in control” |
| Supporting line | Explain what happens, where it works and why the result is useful without jargon. | One or two short sentences | “One app for Mac, iPhone, and iPad. Subscribe or pay once.”<br>“Seven days, every feature, all your devices.” |
| Primary action | Short verb phrase that names the next step or lowers the commitment. | 2–4 words | “Try for free”<br>“Set up MCP” |
| Feature explanation | Start with an action or a familiar frustration, then give a specific scenario. | A short title plus 1–3 sentences | “No more accidental deletions”<br>“Try first, decide later” |
| Company conclusion | A simple, heartfelt reason for doing the work rather than a corporate mission slogan. | One short sentence | “Because, after all, that’s what we love to do” |

**Words and phrasing to use:** everything; your; saved; works; find; keep; simple; daily; workflow; no more; try first; you decide

**Avoid:** revolutionary; disruptive; unlock unprecedented potential; synergy; enterprise-grade solutions; 10x everything; AI-powered magic

**Rules:**

- Use concrete tasks and artifacts as examples rather than broad productivity superlatives.
- Pair a confident headline with a plain explanation of the mechanism or limitation.
- State reassurance in direct language, but only make claims the new product can substantiate.
- Keep FAQ questions in the reader's language and answers explicit about billing, setup or control.
- Allow company-story prose to feel personal; keep ordinary feature sections focused on the reader.

## Do's and Don'ts

### Do

- Keep the flagship opening centered inside an 840px text measure above a 1200px-wide product scene.
- Use the 60px/62px bold display recipe for both opening and closing promises.
- Keep major demonstration panels at 32px radius and smaller testimonial cards at 20px.
- Use 24px grid gutters and the 144px major section padding to preserve the showroom scale.
- Set primary actions to 48px high with 32px side padding and pair them at a 16px gap.
- Place high saturation within product scenes and selected feature panels, leaving the main canvas white or #f5f5f7.
- Use three independently flowing 384px quote columns instead of equal-height proof boxes.
- Give an important dark chapter a warm tactile focal object and a restrained blurred amber halo.

### Don't

- Do not apply negative tracking to every heading; the large bold recipes use positive 0.6px tracking.
- Do not turn the blue action color into the default background of the entire site; large blue panels are selected feature or offer surfaces.
- Do not give all cards dark drop shadows; most are flat, and the diffuse blue halo belongs to the company-story variant.
- Do not use 48px pills inside the header; its compact action is 32px tall.
- Do not add monospace type or terminal chrome to ordinary technical marketing copy; it remains system sans.
- Do not shrink media to the 840px text measure when it is intended as a flagship 1200px product demonstration.
- Do not make FAQ disclosures into separate rounded white cards; they are simple hairline-divided rows.
- Do not replace the personal company ending with the standard trial invitation; keep its fine handwritten sign-off. 

## Motion and responsive

### Motion

**Observed:**

- Declared action color transitions last .15s with cubic-bezier(.4,0,.2,1).
- Declared card transforms last 0.2s with cubic-bezier(0.4,0,0.2,1); the copyable prompt hover scales to 1.02.
- Declared segmented indicator transitions animate left and width over 0.2s ease-out.
- Declared section entrances combine rise-in-fade .9s and rise-in-move .7s with cubic-bezier(.4,0,.2,1), backwards fill.

**Transfer:**

- Keep interactions small and control-like: color feedback on pills and a slight lift on interactive cards, not large scene-wide hover movement.
- Use the segmented indicator to visibly connect a chosen audience to its product demonstration.

**Unknown:**

- The exact scroll triggers, entrance distances, device-settle choreography and sculptural animation sequence are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1000px, 1280px and 1536px.
- Desktop navigation is hidden below its large-layout variant; company-story grids become two columns at the small-layout variant, while trial explainer cards become three columns at the large-layout variant.
- Setup composition declares a stacked layout before its large-layout horizontal variant.

**Transfer:**

- On narrow screens keep the centered promise and scale the device group as one composition rather than detaching its companion devices into unrelated cards.
- Stack the company story, prompt and feature grids while retaining their rounded panels and content hierarchy; allow segmented options to scroll horizontally.
- Retain the edge-bleeding artifact field and carousel peek through clipped media stages rather than squeezing all artifacts into the viewport.

**Unknown:**

- Exact narrow-screen type sizes, side margins, navigation-menu behavior and device arrangement have not been established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
