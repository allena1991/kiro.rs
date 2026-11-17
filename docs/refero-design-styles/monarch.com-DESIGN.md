# Monarch — lived-in money clarity

## Overview

A warm, light editorial style that makes capable software feel at home in everyday life. Cream and butter neutrals support charcoal text, orange actions and occasional confident blocks of saturated color. Light grotesk text meets personable serif headlines, with sunlit lifestyle photography and carefully isolated interface fragments. The density is spacious in storytelling and deliberately more practical in comparison and help sections.

### Essentials

- A conversational headline changes voice mid-sentence: the opening uses ABC Oracle at 59.7px/1.15, weight 300, alongside ABC Otto at 61.9px/71.2px, weight 400; the serif phrase is upright, not italic.
- The first impression is people before machinery: an 800px-tall opening puts a 576px text column against a right-hand domestic photograph, with a broad cream fade joining them. Keep that human-use scene; stage a real task with a simple device or physical output when a product has no polished interface.
- Orange actions are soft capsules, not badges: 9999px radii, 40px compact buttons and a 54px opening action with 19px text and a trailing arrow.
- Warm paper owns most of the page: #fffaec canvas, #f3ecd7 chapter bands and white cards. Saturation is concentrated in small #f86713 actions, a #efb921 visual proof panel and a substantial #e64818 closing band rather than spread across every section.
- Product proof floats on the paper: a 912px-wide framed overview gives way to roughly 477px-wide isolated panels, overlapping widgets and device pairs, alternating with 40px serif headings and 18px body text. Rebuild a few legible task fragments if full product media is unavailable.
- Small orange markings and a generous final promise provide the signature rhythm: 14px uppercase mono labels with 0.03em tracking precede editorial chapters; a 12px-radius saturated band carries a centered 48px serif statement in a 685px measure and a white pill action. Both devices belong in the visual vocabulary of a new landing page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Tangerine action | `#f86713` | `--color-orange` | action, link, accent | Default filled buttons and interactive link emphasis. |
| Vermilion promise | `#e64818` | `--color-closing-red` | background | Default saturated closing band. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt orange marking | `#f35b16` | `--color-label-orange` | text, action | Eyebrow text and declared filled-button hover and active backgrounds. |
| Marigold proof | `#efb921` | `--color-proof-yellow` | background, accent | Integration illustration backing and gold review-star family. |
| Coral ribbon start | `#e5484d` | `--color-announcement-red` | background | Left stop of the thin promotional gradient ribbon. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter chapter | `#f3ecd7` | `--color-butter` | surface | Broad capability and editorial proof bands; active neutral interaction background. |
| Warm charcoal | `#2a2926` | `--color-ink` | text | Default headings, body and monochrome icons. |
| Warm secondary ink | `#65625d` | `--color-muted` | text | Review attribution and footer secondary text. |
| Soft outline | `#dcd9d6` | `--color-edge` | border | Fine outlined secondary actions and form controls. |
| Soft white | `#fbfaf8` | `--color-soft-white` | surface | Highlighted capability card and comparison table headers. |
| Cream paper | `#fffaec` | `--color-canvas` | background | Default marketing canvas and the opaque end of the hero photograph fade. |
| Warm white | `#fefcfb` | `--color-action-text` | text | Text on orange buttons. |
| White | `#ffffff` | `--color-white` | surface, text | Navigation, cards, footer, inverse actions and text on saturated bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| feature, audience and pricing pages | Coral orange | `#ff692d` | `--color-coral-action` | action, background, accent | Cool-theme buttons and the audience closing band. |
| pricing pages | Cyan close | `#00a2c7` | `--color-cyan-close` | background | Centered final promise band. |
| pricing proof sections | Rating gold | `#ffc53d` | `--color-rating-gold` | background | Bottom stop of the compact rating badge. |
| professional-audience pages | Orchid close | `#d6409f` | `--color-magenta-close` | background | Short centered final promise band. |
| pricing proof sections | Rating pale gold | `#f3d673` | `--color-rating-light` | background | Top stop of the compact rating badge. |
| feature-detail pages | Leaf green close | `#30a46c` | `--color-green-close` | background | Closing call paired with a cropped lifestyle photograph. |
| pricing comparisons | Peach check wash | `#fff1ea` | `--color-check-wash` | surface | Visible wash from rgba(255,215,196,0.36) over white behind orange checks. |
| feature, audience and pricing pages | Deep warm ink | `#22201d` | `--color-deep-ink` | text, surface | Text and selected tab fill in the cooler page theme. |
| feature, audience and pricing pages | Stone secondary ink | `#777573` | `--color-cool-muted` | text | Secondary prose and attributions in the cooler theme. |
| feature, audience and pricing pages | Stone rule | `#e4e1de` | `--color-divider` | border, surface | Comparison outlines, plan separators and unselected tabs. |
| feature, audience and pricing pages | Stone panel | `#efecea` | `--color-stone` | surface | FAQ rows, tabbed demonstrations and resource tiles. |
| feature, audience and pricing pages | Chalk canvas | `#f6f5f3` | `--color-cool-canvas` | background, border | Cooler page canvas and very faint comparison column rules. |

## Typography

- **ABC Oracle** — Light opening headline, body, navigation, actions and functional labels. Open, unshowy grotesk with warm proportions; most text uses a light book weight rather than bold. If unavailable, use **DM Sans**. Use weights 300–500 and retain the light book feel. Font stack: "ABC Oracle", "DM Sans", Arial, sans-serif.
- **ABC Otto** — Default editorial section headings, quotes and the serif phrase in the opening. Upright literary serif with substantial brackets and a friendly, rounded reading texture. If unavailable, use **Libre Baskerville**. Use regular weight; check wrapping before changing the measured tracking. Font stack: "ABC Otto", "Libre Baskerville", Georgia, serif.
- **Beltram Mono** — Default orange uppercase chapter markings. Small mechanical mono letters contrast with humane editorial headings. If unavailable, use **IBM Plex Mono**. Font stack: "Beltram Mono", "IBM Plex Mono", ui-monospace, monospace.
- **Copernicus** (only for feature, audience and pricing pages) — Serif headings in the cooler page theme. Fine, tightly fitted editorial serif; noticeably tighter than the default heading family. If unavailable, use **Libre Baskerville**. Regular weight; preserve the tighter role-specific tracking. Font stack: "Copernicus", "Libre Baskerville", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display-serif | ABC Otto | 400 | 61.9px | 1.15 | normal | Upright emphasized phrase embedded in the opening headline. |
| display | ABC Oracle | 300 | 59.7px | 1.15 | -0.0205em | Default opening headline; mix with display-serif in one sentence. |
| heading-lg | ABC Otto | 350 | 48px | 1.2 | -0.02em | Centered product introduction, testimonial heading and final promise. |
| heading | ABC Otto | 350 | 40px | 1.2 | -0.02em | Capability chapter and split-section headings. |
| quote | ABC Otto | 350 | 32px | 1.2 | -0.02em | Large editorial endorsement in the butter band. |
| hero-body | ABC Oracle | 350 | 24px | 1.5 | normal | Opening support sentence. |
| card-title | ABC Oracle | 350 | 20px | 1.4 | normal | Capability and resource card titles. |
| hero-action | ABC Oracle | 350 | 19px | 1.15 | -0.01em | Wide opening action with arrow. |
| body | ABC Oracle | 350 | 18px | 1.4 | normal | Default paragraphs, review prose and chapter explanations. |
| inverse-action | ABC Oracle | 100 | 18px | 1.556 | normal | White action in the default closing band. |
| eyebrow | Beltram Mono | 500 | 14px | 1.3 | 0.03em, uppercase | Orange chapter label above a heading. |
| action | ABC Oracle | 350 | 14px | 1.43 | normal | Compact buttons and navigation links. |
| small-action | ABC Oracle | 100 | 14px | 1.43 | normal | Small outlined secondary actions. |
| footer | ABC Oracle | 350 | 14px | 1.3 | normal | Default footer links and secondary text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages and feature resource headings | detail-display | Copernicus | 350 | 48px | 1.2 | -0.0667em | Text-led pricing opening and larger closing promise. |
| feature, audience and pricing pages | detail-heading | Copernicus | 350 | 40px | 1.2 | -0.06em | Feature and audience opening and major section headings. |
| feature, audience and pricing pages | detail-heading-sm | Copernicus | 350 | 32px | 1.2 | -0.05em | Alternating feature chapter headings and selected oversized review quotes. |
| pricing pages | plan-title | Copernicus | 400 | 32px | 1.2 | -0.05em | Plan names. |
| pricing proof sections | rating | ABC Oracle | 500 | 30px | 1.2 | normal | Single rating number beside a star. |
| FAQ sections | question | ABC Oracle | 500 | 20px | 1.4 | normal | FAQ trigger text. |
| feature, audience and pricing pages | detail-body | ABC Oracle | 350 | 18px | 1.4 | -0.01em | Prose in the cooler theme. |
| pricing pages | comparison-body | ABC Oracle | 350 | 16px | 1.5 | normal | Feature descriptions in comparison rows. |
| pricing pages | plan-action | ABC Oracle | 500 | 16px | 1 | normal | Full-width trial action in each plan. |
| feature and audience openings | detail-eyebrow | ABC Oracle | 500 | 14px | 1.3 | 0.05em, uppercase | Sans-serif orange audience or feature marking. |
| tabbed demonstrations | tab-label | ABC Oracle | 350 | 14px | 1.3 | -0.01em | Functional tab names. |

**Notes:**

- The default heading system stays at -0.02em and weight 350; it is not a heavy display serif. The opening alone pairs a light sans sentence with a slightly larger serif phrase.
- The cooler theme is a complete scoped variant: Copernicus headings at much tighter tracking, sans rather than mono eyebrows, and -0.01em on body text. Do not mix its headline spacing into the default theme.
- Use paragraph width and intentional line breaks to produce two- or three-line benefits; do not shrink all headings to fit one line. No viewport-relative size rule is established for these recipes.

## Layout

**Density:** Airy storytelling with tightly organized functional groups: short 12px text gaps sit inside sections separated by 64px–96px breathing room.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small action pairs and tight title groups. |
| 12px | Eyebrow-to-heading and heading-to-paragraph gaps; navigation inset. |
| 16px | Grid gutters, review gaps, FAQ row separation and outer page inset. |
| 24px | Card padding and normal closing action separation. |
| 32px | Hero support-to-action gap, broad panel padding and distance around closing bands. |
| 40px | Vertical separation between paired capability descriptions. |
| 48px | Plan padding and heading-to-FAQ-list gap. |
| 64px | Default closing vertical padding and major section inset. |
| 80px | Alternating feature-row separation and closing horizontal inset. |
| 96px | Deep editorial section padding. |

### Containers and grids

- **Page grid**: max width 1440px · 12 columns · gap 16px · side padding 16px. Centered outer grid; nested insets produce 32px edges for major full-width bands.
- **Narrative interior**: max width 1144px · 2 columns · gap 64px. Centered alternating text and image chapters; roughly 477px-wide interface art paired with a similar text measure.
- **Review grid**: max width 1144px · 3 columns · gap 16px. Three equal columns of white review cards; rows align while prose lengths vary.
- **Opening text**: max width 576px. Left-hand hero sentence and support; preserve its visual weight against the photograph.
- **Closing measure**: max width 685px. Centered multi-line promise inside the saturated closing band.
- **Comparison stack** (only for pricing pages): max width 896px · gap 24px. Centered category panels; description column plus two 200px comparison columns.

## Corner radius

| Element | Radius |
| --- | --- |
| Actions and tabs | 9999px (pill) |
| Major bands and navigation | 12px |
| Reviews and product frame | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Floating navigation and footer | `0px 10px 15px -3px rgba(34,32,29,0.1), 0px 4px 6px -4px rgba(34,32,29,0.1)` | Soft warm elevation for the white navigation and footer slab. |
| Small resource card | `0px 4px 6px -1px rgba(34,32,29,0.075), 0px 2px 4px -2px rgba(34,32,29,0.075)` | Small white resource cards. |
| Product overview | `0px 0px 0px 1px rgba(34,32,27,0.075), 0px 20px 25px -5px rgba(34,32,29,0.1), 0px 8px 10px -6px rgba(34,32,29,0.1)` | Large product overview on cream. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #fffaec; color: #2a2926`

**Observed:** Warm paper remains visible between all major modules.

**Transfer:** Let the canvas link photography, product art and editorial sections.

#### Butter chapter · level 0

**Use:** Capability overview and editorial endorsement band.

**CSS:** `background: #f3ecd7; border-radius: 12px; padding: 32px`

**Observed:** Inset near-full-width panel; the quote variant uses 48px vertical padding instead.

**Transfer:** Use it to group a related set of benefits without turning the entire page into cards.

#### White split panel · level 1

**Use:** Broad supporting feature, pricing teaser or collaboration story.

**CSS:** `background: #ffffff; border-radius: 12px; overflow: hidden`

**Observed:** Text occupies one half and edge-to-edge photo or graphic occupies the other; no strong outline.

**Transfer:** Keep the graphic flush to the edge and text inset well clear of the seam.

#### Vermilion promise band · level 0

**Use:** Default final conversion statement.

**CSS:** `background: #e64818; border-radius: 12px; overflow: hidden; color: #ffffff`

**Observed:** One expansive flat field with no decorative gradient; the white action is the only raised object.

**Transfer:** Maintain a large saturated moment even when the rest of the page is mostly neutral.

#### Chalk theme · level 0

**Only for:** feature, audience and pricing pages

**Use:** Cooler functional page canvas.

**CSS:** `background: #f6f5f3; color: #22201d`

**Observed:** Stone panels and white modules sit on a cooler near-white background.

**Transfer:** Adopt this as an entire page theme rather than alternating cream and chalk arbitrarily.

#### Stone functional panel · level 1

**Only for:** feature, audience and pricing pages

**Use:** Tabs, FAQ groups and resource tiles.

**CSS:** `background: #efecea`

**Observed:** Many functional tiles have square corners despite the rounded outer storytelling bands.

**Transfer:** Reserve the flat stone surface for practical explanation and choice.

#### Frosted audience caption · level 1

**Only for:** photographic audience openings

**Use:** Text panel over a full-bleed human scene.

**CSS:** `background: rgba(255,255,255,0.75); backdrop-filter: blur(40px); border-radius: 12px; padding: 24px`

**Observed:** A low-left caption card floats over the photograph, keeping the faces unobscured.

**Transfer:** Use this only where a complete photo supplies the opening composition; do not apply glass to ordinary cards.

## Components

### Hero button

**Use:** Main first-screen conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #f86713; color: #fefcfb; border-radius: 9999px; padding: 16px 35.6px; height: 54px; box-shadow: 0px 1px 2px rgba(34,32,29,0.05)`

**Text style:** `hero-action` — ABC Oracle 350 · 19px/1.15 · tracking -0.01em

**Observed:** A single benefit-led label followed by a thin right arrow. It stands alone beneath the support sentence.

**States:** Declared: hover background-color #f35b16; focus-visible transparent 2px outline with 2px offset and the small shadow; active background-color #f35b16.

**Transfer:** Keep the label a short outcome phrase and the arrow separate from the text.

### Compact orange button

**Use:** Small next steps in capability and resource modules.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #f86713; color: #fefcfb; border-radius: 9999px; height: 40px; padding: 0px 20px; box-shadow: 0px 1px 2px rgba(34,32,29,0.05)`

**Text style:** `action` — ABC Oracle 350 · 14px/1.43

**Observed:** Content-width capsule; navigation uses a 36px-high version with 16px side padding. The cooler theme changes the fill to coral orange, and larger section actions use 48px height with 24px side padding.

**States:** Declared: hover background-color #f35b16; focus-visible transparent 2px outline with 2px offset; active background-color #f35b16.

### White button

**Use:** Inverse conversion on colored bands and outlined secondary navigation action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #2a2926; border-radius: 9999px; height: 48px; padding: 0px 24px; box-shadow: 0px 1px 2px rgba(34,32,29,0.05)`

**Text style:** `inverse-action` — ABC Oracle 100 · 18px/1.556

**Observed:** Default is the unoutlined closing action. Small secondary actions use small-action text, a 1px soft-outline border and 36px height with 16px side padding; resource links use 40px height and 20px side padding.

**States:** Declared: hover border-color #bebbb5; focus-visible transparent 2px outline with 2px offset; active background-color #f3ecd7.

### Floating navigation

**Use:** Persistent wayfinding above the opening and while reading.

**CSS:** `display: flex; align-items: center; justify-content: space-between; background: #ffffff; border-radius: 12px; padding: 8px 12px; height: 52px; box-shadow: 0px 10px 15px -3px rgba(34,32,29,0.1), 0px 4px 6px -4px rgba(34,32,29,0.1)`

**Text style:** `action` — ABC Oracle 350 · 14px/1.43

**Observed:** A fixed white bar is inset 12px from the window. Identity at left, five compact links in the middle and two small capsule actions at right. A 32px promotional ribbon can sit above it; without that ribbon the bar begins at a 12px top inset. Navigation links have 8px 12px padding and a small dropdown chevron.

**States:** Declared: hover background-color #f3ecd7 and color #2a2926 on navigation links; active uses the same colors.

**Transfer:** Retain the slim bar and clear three-part balance rather than enlarging the logo or header.

### Review card

**Use:** Repeated social proof.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 8px; padding: 24px`

**Text style:** `body` — ABC Oracle 350 · 18px/1.4

**Observed:** Five small gold stars lead, then a plain-language quote, then muted attribution pinned to the bottom. Cards share row height. Professional proof uses a narrow adjacent portrait and a wider quote card; pricing proof mixes ordinary prose with selected 32px serif quotes.

**Transfer:** Use genuine varied-length testimony and preserve the contrast between informal prose and the occasional editorial pull quote.

### Resource card

**Use:** Small community or learning destinations.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 24px; box-shadow: 0px 4px 6px -1px rgba(34,32,29,0.075), 0px 2px 4px -2px rgba(34,32,29,0.075)`

**Text style:** `card-title` — ABC Oracle 350 · 20px/1.4

**Observed:** Title, body paragraph and outlined white action; two cards sit beside a portrait-format lifestyle image. Detail-page resource tiles instead use flat stone backing and a small media-type label.

**Transfer:** Use for two clear paths into further learning, not a dense article feed.

### Footer slab

**Use:** Complete ending with practical navigation.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 24px; box-shadow: 0px 10px 15px -3px rgba(34,32,29,0.1), 0px 4px 6px -4px rgba(34,32,29,0.1)`

**Text style:** `footer` — ABC Oracle 350 · 14px/1.3

**Observed:** A 16px outer inset frames the white slab. Identity is left of six compact link columns. A generous lower area holds social icons at left, store badges at right and copyright below; an additional centered terms line sits outside the slab on the page canvas. The pricing ending allows a longer multiline terms block.

**Transfer:** Keep the footer broad and shallow rather than ending with a bare legal strip.

### FAQ row

**Only for:** FAQ sections

**Use:** Late-page objection handling.

**CSS:** `background: #efecea; padding: 12px 32px`

**Text style:** `question` — ABC Oracle 500 · 20px/1.4

**Observed:** Full-width flat row with a 60px trigger padded 16px vertically, a medium-weight question at left and a 22px thin plus at right. Rows are separated by 16px; the group follows its serif heading after 48px.

**Transfer:** Keep the questions comfortably readable; answer content should expand in the same row rather than a separate modal.

### Demonstration tabs

**Only for:** tabbed feature or audience demonstrations

**Use:** Choose between related approaches or audiences.

**CSS:** `background: #22201d; color: #ffffff; border-radius: 9999px; padding: 8px 20px`

**Text style:** `tab-label` — ABC Oracle 350 · 14px/1.3 · tracking -0.01em

**Observed:** Selected tab is dark with white text; unselected tabs have stone-rule fill and deep ink text. A centered wrapping row with 16px gaps sits above one substantial image-and-text demonstration. Labels render inside the button rather than inheriting its generic text styling.

**Transfer:** Switch a whole demonstration, not just the tab color; keep labels concise.

### Plan card

**Only for:** pricing pages

**Use:** Direct comparison of subscription choices.

**CSS:** `display: grid; background: #ffffff; padding: 48px`

**Text style:** `plan-title` — Copernicus 400 · 32px/1.2 · tracking -0.05em

**Observed:** Two equal white plan columns share a straight 1px divider; a 300px-wide lifestyle image stands alongside the pair. Each plan orders serif name, short sans promise, price and billing cadence, a ruled checklist, full-width coral trial pill and compact terms. Both plans use the same action color. Trial pills are 44px high with 16px/1 medium text.

**Transfer:** Keep price, billing cadence and trial terms explicit rather than adding a floating promotional badge.

### Comparison panel

**Only for:** pricing pages

**Use:** Detailed category-by-category capability comparison.

**CSS:** `background: #ffffff; border: 1px solid #e4e1de; border-radius: 12px; overflow: hidden; box-shadow: 0px 3px 6px rgba(34,32,29,0.1)`

**Text style:** `comparison-body` — ABC Oracle 350 · 16px/1.5

**Observed:** A soft-white header has category icon and title at left, then two plan columns. The left description column is roughly 494px wide; each plan column is 200px. Rows use 1px horizontal rules, very pale vertical rules and peach circular check backings. Separate category panels are stacked 24px apart.

**Transfer:** Break a long comparison into readable category panels; use dashes for unavailable capabilities.

### Rating badge

**Only for:** pricing proof sections

**Use:** Compact numeric introduction to reviews.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 4px; background: linear-gradient(#f3d673, #ffc53d); border-radius: 9999px; padding: 8px 24px`

**Text style:** `rating` — ABC Oracle 500 · 30px/1.2

**Observed:** A single large number and star sit in a 121px by 52px gold capsule; a muted review-count line follows below, then the serif review heading.

**Transfer:** Use a verifiable aggregate metric rather than turning the badge into a decorative score.

## Imagery and graphics

### Sunlit everyday life

**Use:** Opening scene and selected supporting split panels.

**Observed:** Candid people using a phone together, talking across a table or reviewing a device over coffee. Warm natural window light, ordinary furnishings, authentic skin tones and close human framing; the default opening lets the scene occupy the right half and bleed behind the fade.

**Transfer:** Photograph the new product in an ordinary moment of use, with attention directed between people and a task rather than at the camera. If there is no app, show the physical output or tool in use.

### Cream photograph dissolve

**Use:** Signature joining treatment in the default opening.

**Observed:** The photograph meets an opaque cream text field through a broad soft horizontal fade, not a sharp split or a dark overlay. Faces stay fully visible at the far right.

**Transfer:** Preserve the dissolve and warm exposure with new imagery; keep the text entirely within the solid-paper portion.

**Build:** Place an object-fit:cover photograph in an absolute right-hand layer spanning roughly 60% of an 800px scene. Above it, use a full-scene linear-gradient(90deg, #fffaec 0%, #fffaec 38%, rgba(255,250,236,0.85) 46%, rgba(255,250,236,0) 65%). Put text above this layer. Adjust stops to the subjects; exact stops are not essential.

### Floating interface fragments

**Use:** Core product introduction and alternating capability chapters.

**Observed:** A large white desktop overview has an 8px frame and soft multilayer shadow; subsequent art isolates only the useful rows, lists or graphs on white cards. Panels overlap gently and remain nearly front-facing rather than tilting in perspective. Avatar chips and smaller widgets can float above a larger panel. Device pairs combine a thin dark laptop or tablet outline with a phone.

**Transfer:** Reconstruct a legible representative task with a few meaningful rows or a chart. Keep surrounding cream visible and do not reproduce an entire application's internal typography system.

### Marigold integration constellation

**Use:** Signature visual proof panel paired with explanatory text.

**Observed:** A saturated yellow right half contains a central orange rounded square, concentric fine rings and an orderly scatter of circular integration marks with soft shadows. The adjoining white text half makes the rare strong color feel intentional.

**Transfer:** Use approved ecosystem symbols or simple category pictograms. If there are no integrations, represent compatible inputs, outputs or task categories; retain the central hub, circular satellites and yellow field.

**Build:** Use a #efb921 rectangular backing clipped by the split panel's 12px outer radius. Center an orange rounded square about one sixth of the panel width. Draw three or four concentric SVG circles around it with rgba(42,41,38,0.04) 1px strokes. Arrange small circular marks in staggered rows around the hub, leaving its center clear; add soft downward shadows with rgba(34,32,29,0.1).

### Layered professional scene

**Only for:** professional-audience openings

**Use:** Business-oriented opening proof.

**Observed:** A warm collaborative table photograph sits behind a large white client-list interface, offset down and left. The combined media mass is about 801px wide and balances a narrow text column on chalk.

**Transfer:** Pair an authentic work scene with one believable workflow panel; keep the photograph visible enough to establish the human setting.

### Icons

**Observed:** Functional icons are spare outlined symbols, commonly 24px in orange beside feature bullets. FAQ plus marks are 22px with a thin 1px round stroke; navigation chevrons are 12px with 2px stroke. Review stars are compact 20px filled gold shapes; comparison checks are 16px orange strokes with round caps on peach circles.

**Transfer:** Choose one thin rounded outline family for functional symbols, keep star ratings filled, and place icons as quiet cues rather than large illustrations.

## Section recipes

How recurring sections are built.

### First screen: Human promise opening

**Observed:** An 800px scene on Cream canvas, underneath Floating navigation and a thin promotional ribbon. Back to front: warm domestic photograph concentrated on the right, Cream photograph dissolve across the middle, then a left 576px text block. The two-line headline starts in light grotesk at 59.7px and ends with a slightly larger upright serif phrase on the second line; the text occupies roughly two fifths of the width. A two-line 24px support sentence follows after about 18px, then Hero button after 32px. Within the first 900px the complete headline, support, action and human scene are visible; the four-part accolade strip begins at the lower edge. The large product overview and its centered introduction are below the fold.

**Transfer:** Give a different product an equally human task scene and a short promise with one serif-emphasized outcome phrase. If no polished media exists, stage a person using the tool or its output in natural light and keep the broad cream dissolve. Feature pages open with a narrow 40px serif text column and a large interface image; professional pages layer UI over a work photograph; photographic audience pages use a 500px full-width image with Frosted audience caption; pricing starts with a 48px text-led trial promise above the plans.

**Avoid:** Do not replace this default with a centered all-bold SaaS headline, a floating dashboard on a gradient, or a hard 50/50 photo seam. Do not move the first action below a huge device mockup.

**Text style:** `display` — ABC Oracle 300 · 59.7px/1.15 · tracking -0.0205em

### Centered product introduction

**Observed:** Orange mono marking, heading-lg and an 18px explanatory paragraph are centered over a 912px-wide product overview. Label and heading are separated by 12px; the major section has a 64px upper inset. Product overview uses the dedicated frame shadow.

**Transfer:** Explain what the whole product does before zooming into fragments; keep a clear overview rather than a collage of unrelated UI.

**Text style:** `heading-lg` — ABC Otto 350 · 48px/1.2 · tracking -0.02em

### Capability stage

**Observed:** Butter chapter holds a centered heading and short support above a three-part composition: stacked descriptions on both sides of a narrow vertical product demonstration. The active description receives Soft white backing, 12px radius and 24px padding; other descriptions are visually quieter. Each has a mono label, card-title, body copy and Compact orange button.

**Transfer:** Map several related capabilities to one central task scene; let the active description and demonstration correspond.

**Text style:** `heading` — ABC Otto 350 · 40px/1.2 · tracking -0.02em

### Alternating feature chapter

**Observed:** A centered narrative interior pairs a roughly 477px interface fragment with an editorial text column, reversing sides in successive chapters. The text stack is orange eyebrow, 40px serif heading and 18px body with 12px separations. Chapters are separated by 80px; cooler-theme variants use 32px headings and three orange-icon benefit lines.

**Transfer:** Give each chapter one benefit and one focused piece of product proof rather than repeating the whole dashboard.

**Text style:** `heading` — ABC Otto 350 · 40px/1.2 · tracking -0.02em

### Split proof panel

**Observed:** White split panel joins a generous left text block to a flush right visual. One version uses the Marigold integration constellation; others use a lifestyle photograph or a device close-up. Text starts with an orange label and heading, followed by a paragraph and an action when needed.

**Transfer:** Make one proof point feel substantial with a half-panel visual; preserve the clean seam and clipped outer corners.

**Text style:** `heading` — ABC Otto 350 · 40px/1.2 · tracking -0.02em

### Reviews and editorial endorsement

**Observed:** A centered 48px heading introduces the three-column Review grid on cream. A separate Butter chapter endorsement uses a vertical stack of publication marks at left and a 32px serif quote plus attribution at right. The cooler pricing variant introduces its grid with Rating badge and deliberately mixes body quotes with large serif pull quotes; professional proof uses three wide portrait-and-quote rows.

**Transfer:** Use varied proof formats for different kinds of credibility without changing the basic white-card material.

**Text style:** `quote` — ABC Otto 350 · 32px/1.2 · tracking -0.02em

### Saturated promise and complete ending

**Observed:** Vermilion promise band is a near-full-width 373px-tall closing device with 64px vertical padding. A centered 685px measure holds a three-line white heading-lg and White button 24px below. After a 32px gap, Footer slab provides full navigation and a separate terms line. Scoped endings preserve this construction: an orange audience band at 388px, a 316px magenta professional band, a 397px cyan pricing band, and a 396px green feature band with left-aligned text and a right-hand café photograph.

**Transfer:** Restate the emotional outcome in one generous serif promise, then supply a single low-friction action and a complete footer. The saturated device can move or recur according to the story; it is not a requirement to copy a fixed section sequence.

**Text style:** `heading-lg` — ABC Otto 350 · 48px/1.2 · tracking -0.02em

### Tabbed demonstration band

**Only for:** feature and professional-audience pages

**Observed:** Stone functional panel spans nearly the whole page. A centered optional heading and explanation lead into Demonstration tabs; below, a substantial product illustration sits beside a narrow benefit stack or paragraph. The selected tab is dark, not orange.

**Transfer:** Use to compare a small number of approaches or audiences while preserving a single shared product narrative.

**Text style:** `detail-heading-sm` — Copernicus 350 · 32px/1.2 · tracking -0.05em

### Pricing decision

**Only for:** pricing pages

**Observed:** A text-led detail-display opening introduces a contiguous Plan card pair alongside a tall human-use photograph. Later, a centered serif heading and paragraph lead into the narrower Comparison stack. Between these, a left rationale heading balances a two-by-two white benefit-card grid.

**Transfer:** Separate immediate plan choice, reasons to pay and detailed feature comparison instead of merging everything into one large table.

**Text style:** `detail-display` — Copernicus 350 · 48px/1.2 · tracking -0.0667em

### Practical help cluster

**Only for:** feature, audience and pricing pages

**Observed:** FAQs use a 40px serif heading above flat stone FAQ rows in an approximately 1151px-wide group. Learning sections pair a narrow left heading with a right stack of stone resource tiles carrying a media-type label, title and small action. Professional pages add a centered 32px contact heading with a 400px white pill selector beside an orange submission action, and a four-column process strip with orange icons.

**Transfer:** Choose the relevant help formats for the reader's remaining uncertainty; maintain the quieter square-edged stone vocabulary.

**Text style:** `detail-heading` — Copernicus 350 · 40px/1.2 · tracking -0.06em

## Page flow

**Storyline:** Human promise → whole-product clarity → focused capability proof → confidence and social proof → practical next steps → saturated final promise and full footer.

### Broad product landing page

1. **Promise** — Human photo opening, mixed-font headline, outcome action and four-part accolade strip.
2. **Product demonstration** — Centered product explanation and large overview, then butter capability stage.
3. **Capability chapters** — Alternating interface fragments and short editorial benefits, with a bright split proof panel.
4. **Social proof** — Review grid and separate publication endorsement band.
5. **Next steps** — Lifestyle image beside resource cards, then a white pricing teaser.
6. **Closing call** — Vermilion centered promise, white action, complete footer slab and external terms.

**Transfer:** Start with an everyday outcome, progressively reveal product detail, and close with assurance rather than additional features.

### Single-feature explanation

1. **Promise** — Narrow serif feature introduction and large interface visual.
2. **Capability chapters** — Three alternating product fragments with icon-led benefits.
3. **Product demonstration** — Stone tabbed comparison of two approaches.
4. **Education** — Learning resource tiles.
5. **Objection handling** — Three flat stone FAQ rows.
6. **Closing call** — Green promise band with a right-hand lifestyle photo, followed by the full footer.

**Transfer:** Explain one capability deeply, demonstrate meaningful alternatives and answer implementation questions.

### Human audience use case

1. **Promise** — Wide candid photo with a frosted low-left caption.
2. **Capability chapters** — Three alternating interface chapters with short icon-led benefits.
3. **Extended value** — White photo-and-text collaboration panel.
4. **Social proof** — Stone editorial publication endorsement.
5. **Objection handling** — Three FAQ rows.
6. **Closing call** — Centered coral-orange promise, white action and full footer.

**Transfer:** Lead with recognizable lived experience and translate shared capabilities into audience-specific benefits.

### Professional audience acquisition

1. **Promise** — Narrow serif introduction beside layered work photo and workflow UI.
2. **Audience fit** — Tabbed stone demonstration for several professional roles.
3. **Social proof** — Three portrait-and-quote rows.
4. **Process** — Four flat numbered steps with orange icons.
5. **Pricing and contact** — White pricing teaser, then a centered contact selector and action.
6. **Objection handling** — FAQ rows and stacked learning resources.
7. **Closing call** — Short magenta promise band and full footer.

**Transfer:** Balance workflow specificity with expert testimony; put process and contact mechanics after credibility.

### Subscription decision and value defense

1. **Pricing** — Text-led trial promise above a photo and two contiguous white plan columns.
2. **Value rationale** — Editorial left column with a two-by-two white benefit grid.
3. **Detailed comparison** — Centered introduction followed by seven narrow category panels.
4. **Social proof** — Gold rating capsule and review grid mixing body prose with serif pull quotes.
5. **Objection handling** — Three FAQ rows.
6. **Closing call** — Cyan promise band, white action, full footer and a longer terms block.

**Transfer:** Offer an immediate decision first, then progressively disclose reasons, capabilities, proof and terms.

## Writing

Warm, direct and reassuring without sounding precious. Product utility is translated into everyday relief, with concrete verbs and a little conversational looseness.

**Do not copy:** Do not reuse Monarch's name, logo, interface content, partner marks, publication endorsements, customer quotations, audience facts, review totals, rating, connectivity numbers, discounts, trial terms or pricing claims. Supply truthful equivalents belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your; use together when shared participation is relevant. The product is named plainly when explaining how it works; we appears sparingly in educational or community contexts.
- **Rhythm:** Headlines are usually short benefit phrases, sometimes extended by a conversational second clause. Support is one or two plain sentences; feature lists use short parallel verb-led lines. Parentheses, an em dash or a brief aside add humanity rather than hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a modern, easier way to handle a familiar task; emphasize the personal outcome. | 6–10 words | “The modern way to manage your money” |
| Support | Three concrete actions followed by a unifying simplification. | 12–24 words | “Budget, track your progress, and plan for the future—all in one app.” |
| Chapter heading | A recognizable capability framed as a simple benefit. | 4–8 words | “All your accounts, in one place”<br>“Go further, together” |
| Conversational feature promise | A practical principle followed by an everyday aside. | 6–10 words | “Budgeting should be flexible, because…life” |
| Action | Either a plain next step or an outcome-led invitation; keep low commitment. | 2–5 words | “Unlock better money habits”<br>“Learn more” |
| Closing promise | A sequence of helpful verbs ending in an emotional benefit and a supportive relationship. | 12–20 words | “Track, budget, and feel good about your money with [Brand] in your corner.” |

**Words and phrasing to use:** clear view; feel confident; fits your life; together; on track; in one place; flexible; progress; get started

**Avoid:** revolutionary; disruptive; dominate; crush the competition; unprecedented; enterprise-grade everything; effortless wealth

**Rules:**

- State what the reader can do before explaining the mechanism.
- Make reassurance concrete: name the task, the view or the decision that becomes easier.
- Use concise functional names for labels and tabs; keep emotional language in headings and promises.
- Let occasional conversational asides soften practical material, but keep billing, permissions and terms literal.

## Do's and Don'ts

### Do

- Keep default serif section headings at 40px/1.2, weight 350 and -0.02em tracking.
- Pair the 59.7px light sans opening with the slightly larger upright serif phrase.
- Keep 16px gutters and 24px card padding consistent across repeated modules.
- Use 12px radii for broad bands and 8px for review cards.
- Give isolated product fragments about 477px of desktop width and enough cream around their silhouettes.
- Keep the strong closing promise within a 685px centered text measure.
- Use white inverse capsules on saturated bands, not the orange action fill.
- Treat the cooler chalk-and-Copernicus system as a scoped page variant.

### Don't

- Do not turn the default cream canvas into pure white; white is a distinct raised material.
- Do not give every benefit a saturated card; yellow belongs to a concentrated proof visual and vermilion to the promise band.
- Do not set ordinary body text at weight 600; 18px weight 350 carries the editorial tone.
- Do not apply Copernicus's -0.06em tracking to the default serif family.
- Do not make every control a 12px rounded rectangle; actions and tabs are full capsules.
- Do not add dark outlines or hard black drop shadows to the white cards; elevation uses warm low-opacity shadows.
- Do not turn FAQ rows into individual floating pill cards; they use flat stone rectangular backing.
- Do not use italic serif emphasis in the opening; the contrasting phrase is upright.
- Do not reduce the footer to a narrow copyright bar; the white navigation slab is part of the ending. 

## Motion and responsive

### Motion

**Observed:**

- Actions declare color and background transitions at 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- Reveal layers declare transform and opacity transitions at 2s cubic-bezier(.075, .82, .165, 1); selected fade-only objects use 1.5s or 3s.
- The capability stage declares an opacity transition of 0.3s cubic-bezier(0.4, 0, 0.2, 1). Pricing trial actions declare background-color 150ms ease-in-out.

**Transfer:**

- Keep tiny control changes quick and scene reveals slow; the interface should settle into a legible paper composition rather than remain in motion.
- Use opacity changes to coordinate the active capability description with its central demonstration.

**Unknown:**

- Exact scroll triggers, reveal displacement, stagger delays and intermediate animation frames are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 767px, 768px, 1024px, 1200px and 1280px among others.
- The opening headline has center-alignment rules below the desktop layout; the middle navigation is hidden below its desktop breakpoint. Source grids declare four-column and twelve-column variants.

**Transfer:**

- On narrow layouts, preserve the complete human scene and cream fade while stacking the text and media; keep the action associated with the promise.
- Stack alternating chapters and split proof panels; keep isolated interface art legible rather than shrinking a full dashboard into a thumbnail.
- Wrap demonstration capsules and simplify comparison presentation without losing plan labels or billing cadence.

**Unknown:**

- Mobile compositions, exact responsive typography and menu behavior are not visually established. These stacking rules are recommendations, not verified mobile layouts.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
