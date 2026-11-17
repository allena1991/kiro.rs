# Luma — cinema meets workbench

## Overview

A monochrome editorial shell makes vivid creative work feel like the main event. Tight medium-weight grotesk typography, small capsule actions and expansive white space frame cinematic imagery, angled interface compositions and occasional deep-black chapters. It suits ambitious creative tools and technically sophisticated products that can show their output, with airy storytelling that becomes dense only where comparison or selection demands it.

### Essentials

- A film stage, not a dashboard, makes the first promise: full-bleed 1440×900 media under a dark scrim, a centered 576px text column, 52px/1.2 medium grotesk with -0.04em tracking, and one white 48px capsule action.
- The workbench crosses the stage boundary: a 652×288px translucent prompt panel with 24px corners and 24px backdrop blur overlaps the hero by 160px. Carry this layered invitation into a relevant search, brief or task entry even when the product is not generative.
- Headlines compress while sections breathe: 48px/1.2 weight 500 headings at -0.04em, 22px/1.3 gray support lines, 20px between them, 80px before media and 160px between major chapters.
- Controls are small monochrome capsules rather than colored banners: 32px, 40px and 48px heights, 9999px radii and 12px, 24px or 32px side padding respectively.
- Color belongs to the work, not the shell: page surfaces, actions and text remain white, black and gray; vivid imagery occupies broad 1216×532px stages or rounded 16:9 tiles. Include a cinematic output scene and an atmospheric light image; use a staged object and procedural light particles when equivalent output media is unavailable.
- Light and dark chapters have distinct editorial jobs: a black full-width technical-depth chapter uses white headings and #8c8c8c support, then returns to white for timely or human material. The closing mood is human-scale portrait media followed by a spare ruled footer, not a giant sales billboard.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, action | Primary type, dark chapters and actions on light backgrounds. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Reading gray | `#737373` | `--color-secondary` | text, border | Support paragraphs and outlined editorial category labels on white. |
| Dark chapter gray | `#8c8c8c` | `--color-inverse-secondary` | text, border | Support paragraphs, dates and category outlines on black. |
| Section rule | `#b3b3b3` | `--color-rule` | border | Visible black at 30% over white for footer rules and accordion outlines. |
| Faint edge | `#e6e6e6` | `--color-edge` | border | Visible black at 10% over white around panels and media. |
| Panel gray | `#ededed` | `--color-elevated` | surface, background | Announcement capsule, pricing panels and broad neutral bands. |
| White | `#ffffff` | `--color-canvas` | background, text, action | Default canvas; headings and capsule actions reverse to white on dark media. Navigation uses white at 80% alpha with blur. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing comparison tables | Table grid | `#999999` | `--color-table-rule` | border | Visible black at 40% over white for tabular row and cell boundaries. |
| recruitment directories | Metadata gray | `#a6a6a6` | `--color-tertiary` | text | Location metadata and subdued filter affordances. |
| enterprise inquiry forms | Form outline | `#aeaeae` | `--color-input-edge` | border | Field outlines. |
| culture and recruitment pages | Soft gray | `#f2f2f2` | `--color-soft` | surface | Visible black at 5% over white for benefit cards; also used as a solid light fill. |

## Typography

- **__graphik_7126cf** — All marketing typography, navigation and controls. Matter-of-fact grotesk with compact proportions, open counters and firm medium-weight headings. If unavailable, use **Inter**. Use weights 400–700 and retain negative tracking; balance line breaks rather than widening the display. Font stack: "__graphik_7126cf", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | __graphik_7126cf | 500 | 52px | 1.2 | -0.04em | Centered opening promise and the large standalone manifesto. |
| heading | __graphik_7126cf | 500 | 48px | 1.2 | -0.04em | Major section headings. |
| heading-sm | __graphik_7126cf | 500 | 32px | 1.2 | -0.04em | Feature names, portrait-card links and compact comparison headings. |
| card-title | __graphik_7126cf | 500 | 22px | 1.4 | -0.03em | Editorial links, use-case titles and accordion questions. |
| support | __graphik_7126cf | 500 | 22px | 1.3 | -0.04em | Hero support and section introductions; normally gray. |
| body | __graphik_7126cf | 400 | 18px | 1.4 | -0.03em | Feature descriptions below media. |
| hero-action | __graphik_7126cf | 500 | 18px | 1.556 | -0.022em | 48px conversion capsules; also the numeric table-body treatment. |
| action | __graphik_7126cf | 500 | 16px | 1.5 | -0.025em | 40px action capsules and announcement text. |
| caption | __graphik_7126cf | 400 | 16px | 1.4 | -0.03em | Editorial dates and secondary short notes. |
| compact-action | __graphik_7126cf | 500 | 14px | 1.43 | -0.0286em | 32px actions, sign-in and small story links. |
| nav | __graphik_7126cf | 500 | 14px | 1 | normal, uppercase | Compact navigation labels. |
| label | __graphik_7126cf | 600 | 14px | 1 | -0.03em, uppercase | Outlined categories and reversed small badges. |
| footer-link | __graphik_7126cf | 400 | 14px | 1.714 | -0.0286em | Small footer directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| recruitment pages | culture-display | __graphik_7126cf | 500 | 52px | 1.2 | -0.05em | More tightly tracked recruitment promise. |
| recruitment pages | culture-heading | __graphik_7126cf | 500 | 48px | 1.2 | -0.05em | Recruitment section headings. |
| technical-depth chapters | technical-title | __graphik_7126cf | 700 | 32px | 1.2 | -0.04em | Model or technical initiative names within the dark chapter. |
| pricing pages | price | __graphik_7126cf | 600 | 32px | 1.333 | -0.025em | Plan prices with a smaller inline billing suffix. |
| pricing comparison tables | table-heading | __graphik_7126cf | 500 | 20px | 1.4 | -0.02em | Centered table header and model name. |
| pricing pages | plan-body | __graphik_7126cf | 500 | 16px | 1.4 | -0.03em | Feature lists and billing switch. |
| recruitment directories | directory-meta | __graphik_7126cf | 400 | 12px | 1.333 | -0.033em | Right-aligned location metadata. |

**Notes:**

- Use one grotesk throughout; the authority comes from medium weights and compressed tracking rather than a second display family.
- Display and section headings share a 1.2 line height. Balance headlines into deliberate lines; the default opening is two lines, not an edge-to-edge word sculpture.
- The 22px support recipe is denser vertically than the 22px card-title recipe. Preserve that distinction.
- The dark chapter alone gives 32px technical titles weight 700; ordinary feature titles remain 500.

## Layout

**Density:** Airy chapter-level spacing with compact controls and tightly organized editorial captions; tables and directories are deliberately denser.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Metadata row gaps, accordion stack gaps and numbered-process icon separation. |
| 10px | Feature title to description and repeated pricing features. |
| 16px | Navigation link gaps, social icon gaps and announcement contents. |
| 20px | Heading-to-support gap, media-to-caption gap and three-column grid gutters. |
| 24px | Standard capsule horizontal padding. |
| 32px | Container side padding, benefit-card padding and form grid gap. |
| 40px | Two-column media grid gutter and smaller row separation. |
| 80px | Section introduction to main media; footer rule to directory. |
| 160px | Chapter spacing and broad-band vertical padding; hero workbench overlap. |

### Containers and grids

- **main-container**: max width 1280px · side padding 32px. Centered desktop container, yielding 1216px of content and 112px visual side margins at 1440px.
- **hero-copy**: max width 576px. Centered balanced promise and support over full-bleed media.
- **section-intro**: max width 768px. Left-aligned headline and short support, leaving room for an action on the right.
- **feature-pair**: 2 columns · gap 40px. Equal 588px media-and-copy columns for major features and portrait destinations.
- **editorial-grid**: 3 columns · gap 20px. Equal 392px editorial and use-case columns; a lead item may span the full width.
- **form-container** (only for enterprise inquiry forms): max width 896px · 2 columns · gap 32px · side padding 32px. 832px usable inquiry form with paired name fields and full-width remaining fields.
- **directory-layout** (only for recruitment directories): 2 columns · gap 30px. 148px category rail beside a 1038px results column within the main container.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | media-and-feature-panels | 24px |
|  | prompt-input-and-plan-panels | 16px |
|  | category-labels | 8px |
| enterprise inquiry forms | form-fields | 6px |
| recruitment process sections | process-number | 5px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | workbench-glass | `0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)` | Subtle separation of translucent prompt panel from the media. |
|  | prompt-input | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Raised white input within glass, not ordinary content cards. |
| enterprise inquiry forms | field | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Restrained form-field edge. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading surface.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Most of the long-form page is white; imagery provides its color.

**Transfer:** Keep structural UI neutral even when the product has a bright identity.

#### Black chapter · level 0

**Use:** Immersive media and a substantial technical-depth chapter.

**CSS:** `background: #000000; color: #ffffff; padding: 160px 0px`

**Observed:** Runs across the viewport rather than appearing as one isolated black card; secondary text shifts to dark chapter gray.

**Transfer:** Give technical credibility a distinct visual register, then return to white for editorial or human material.

#### Neutral band · level 0

**Use:** A full-width break containing real-world proof.

**CSS:** `background: #ededed; padding: 160px 0px`

**Observed:** Supports an image ribbon; in culture content it also supports numbered process cards.

**Transfer:** Use for a contrasting proof chapter, not as a fill on every section.

#### Navigation veil · level 2

**Use:** Reading navigation over scrolled content.

**CSS:** `background: rgba(255,255,255,0.8); backdrop-filter: blur(24px); height: 64px`

**Observed:** The opening navigation sits directly over dark imagery; light reading sections use the translucent white veil, and dark sections use black at 80% alpha.

**Transfer:** Switch the navigation contrast with the underlying chapter.

#### Workbench glass · level 1

**Use:** Interactive invitation crossing from media into the page.

**CSS:** `background: linear-gradient(to bottom right, rgba(255,255,255,0.5), rgba(0,0,0,0.5)); backdrop-filter: blur(24px); border-radius: 24px; outline: 1px solid rgba(0,0,0,0.2); box-shadow: 0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)`

**Observed:** Neutral diagonal glass with a brighter upper-left edge; the white input inside is opaque.

**Transfer:** Use translucency for a foreground tool, not as the dominant card material.

#### Culture utility card · level 1

**Only for:** culture and recruitment pages

**Use:** Benefits and compact organization facts.

**CSS:** `background: rgba(0,0,0,0.05); border-radius: 24px; padding: 32px`

**Observed:** Facts are centered in 289×144px cards with 32px values and 22px labels; benefits are left-aligned in 598×200px panels with small black badges.

**Transfer:** Separate quantitative facts from benefit explanations instead of forcing both into one card format.

## Components

### Navigation

**Use:** Persistent brand and product directory.

**CSS:** `height: 64px; padding: 0px 32px; display: flex; align-items: center; gap: 16px`

**Text style:** `nav` — __graphik_7126cf 500 · 14px/1 · uppercase

**Observed:** Compact mark at the left, links grouped at the right, then Compact action. A fine rule separates the header from light content; over media, links and mark are white.

**States:** Declared: hover opacity 0.7 on links; focus-visible outline-offset 4px.

**Transfer:** Keep the navigation visually subordinate to the media.

### Hero button

**Use:** The single immediate conversion on dark media.

**CSS:** `height: 48px; padding: 0px 32px; border: 1px solid transparent; border-radius: 9999px; background: #ffffff; color: #000000; display: flex; align-items: center; justify-content: center`

**Text style:** `hero-action` — __graphik_7126cf 500 · 18px/1.556 · tracking -0.022em

**Observed:** Text-only and centered. Recruitment and inquiry contexts reverse the same silhouette to black on white.

**States:** Declared: hover background-color hsl(0 0% 85%); focus-visible outline-offset 4px.

### Section button

**Use:** Actions beside section headings or below feature descriptions.

**CSS:** `height: 40px; padding: 0px 24px; border: 1px solid transparent; border-radius: 9999px; background: #000000; color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — __graphik_7126cf 500 · 16px/1.5 · tracking -0.025em

**Observed:** Usually aligned right on a white section; dark chapters reverse to white with black lettering. Plan actions expand to the available card width.

**States:** Declared: hover background-color hsl(0 0% 15%); focus-visible outline-offset 4px.

### Compact action

**Use:** Sign-in, suggested tasks and small contextual links.

**CSS:** `height: 32px; padding: 0px 12px; border: 1px solid transparent; border-radius: 9999px; background: #ffffff; color: #000000`

**Text style:** `compact-action` — __graphik_7126cf 500 · 14px/1.43 · tracking -0.0286em

**Observed:** Small text-only capsules; story cards use an outlined transparent version, and light headers use a black sign-in capsule.

**States:** Declared: hover background-color hsl(0 0% 85%); focus-visible outline-offset 4px.

### Announcement capsule

**Use:** A compact release or timely update below the opening.

**CSS:** `height: 56px; padding: 0px 24px; display: flex; align-items: center; gap: 16px; border: 1px solid rgba(0,0,0,0.1); border-radius: 9999px; background: #ededed`

**Text style:** `action` — __graphik_7126cf 500 · 16px/1.5 · tracking -0.025em

**Observed:** Content-sized and centered; one short update with two Compact actions on the same baseline.

**Transfer:** Keep the update bounded rather than making a full-width alert bar.

### Prompt workbench

**Use:** A tangible way to begin a task directly from the promise.

**CSS:** `max-width: 652px; min-height: 288px; padding: 32px 40px; margin-top: -160px; display: flex; flex-direction: column; gap: 10px; border-radius: 24px; backdrop-filter: blur(24px); background: linear-gradient(to bottom right, rgba(255,255,255,0.5), rgba(0,0,0,0.5))`

**Text style:** `card-title` — __graphik_7126cf 500 · 22px/1.4 · tracking -0.03em

**Observed:** Uses Workbench glass: centered question, white 16px-radius input with a 44px submit arrow at its right, then three Compact action suggestions. The input is 572×128px, padded 14px with extra right space for the arrow.

**Transfer:** Adapt the entry to a search, task brief or product selector; keep it demonstrably useful rather than decorative.

### Editorial category

**Use:** Small metadata before editorial card titles.

**CSS:** `padding: 6px 12px; border: 1px solid #737373; border-radius: 8px; color: #737373; display: inline-block`

**Text style:** `label` — __graphik_7126cf 600 · 14px/1 · tracking -0.03em · uppercase

**Observed:** Outlined rounded rectangle followed by a Caption date with 8px gap. The dark variant changes both outline and text to dark chapter gray; a new badge is solid white.

**Transfer:** Use categories as compact editorial metadata, not as colorful status chips.

### Footer directory

**Use:** The common end of every page.

**CSS:** `max-width: 1280px; padding: 0px 32px 160px; display: flex; flex-direction: column; gap: 80px`

**Text style:** `footer-link` — __graphik_7126cf 400 · 14px/1.714 · tracking -0.0286em

**Observed:** A single 1px black-at-30% rule precedes a two-column region: 32px wordmark and five 40px circular social icons on the left; three columns of small links on the right. Links use black at 0.7 opacity and 24px line height.

**States:** Declared: hover opacity 1 on directory links; focus-visible outline-offset 4px.

**Transfer:** Close with useful navigation and ample bottom space rather than another oversized pitch.

### Plan card

**Only for:** pricing pages

**Use:** Subscription and business-plan comparison.

**CSS:** `background: #ededed; border: 1px solid rgba(0,0,0,0.1); border-radius: 16px; padding: 32px 20px 56px; display: flex; flex-direction: column`

**Text style:** `plan-body` — __graphik_7126cf 500 · 16px/1.4 · tracking -0.03em

**Observed:** Small muted plan name, Price with billing suffix, full-width white action, a thin divider and check-mark feature list. Three 392×434px cards form the individual tier row; the emphasized middle tier is black with white text and a white action. Business plans use two wider panels.

**Transfer:** Highlight one tier through inversion, not an accent-color ribbon.

### Testimonial card

**Only for:** enterprise proof sections

**Use:** Human proof with an attributed story.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.1); border-radius: 24px; padding: 20px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `body` — __graphik_7126cf 400 · 18px/1.4 · tracking -0.03em

**Observed:** Quote first, then a fine divider, portrait with name and small gray role, and an outlined Compact action. Four cards alternate wider and narrower spans across two rows; the lead quote uses 22px regular text while others use 18px.

**Transfer:** Let quote length create varied spans while aligning attribution toward card bottoms.

### Inquiry field

**Only for:** enterprise inquiry forms

**Use:** Enterprise contact details and qualification.

**CSS:** `height: 36px; padding: 4px 10px; border: 1px solid #aeaeae; border-radius: 6px; background: transparent; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Observed:** Visible labels above controls; paired first and last names, then full-width inputs and selects. Product-interest checkboxes precede a tall message area and full-width black 48px submit capsule.

**Transfer:** Keep fields utilitarian and shorter than conversion buttons; do not apply the capsule shape to inputs.

### Question accordion

**Only for:** recruitment question sections

**Use:** Objection handling after recruitment process details.

**CSS:** `border: 1px solid rgba(0,0,0,0.3); border-radius: 24px; padding: 12px 0px; overflow: hidden`

**Text style:** `card-title` — __graphik_7126cf 500 · 22px/1.4 · tracking -0.03em

**Observed:** Full-width 1216×89px closed rows stacked 8px apart. Inner question button uses 16px 28px padding and a 20px gray plus at the right.

**Transfer:** Use concise questions and preserve the roomy single-line row where possible.

## Imagery and graphics

### Cinematic output stage

**Use:** Opening and major product proof.

**Observed:** The opening is a moving full-bleed creative workspace with fashion output at monumental scale, dimmed so white copy stays dominant. The enterprise variant stages a sculptural sneaker on a marble pedestal in a cool smoky room. Main product proof is a tilted white work surface densely populated with output thumbnails, backed by black and clipped into a 1216×532px rounded stage.

**Transfer:** Show finished work at cinematic scale. Without a suitable video, photograph or render one representative object with directional light and a darkened environment; for software, create one angled composition of authentic interface content rather than a browser-window collage.

### Neutral work canvases

**Use:** Capability and use-case media tiles.

**Observed:** Pale gray rounded stages contain floating image sheets, prompt capsules, document fragments and video frames. Subtle dotted grids and fine shadows give depth without thick device frames. Media is 16:9; titles and descriptions sit outside the tile.

**Transfer:** Create a sparse tableau of two or three relevant artifacts, with one clearly dominant output and restrained perspective.

**Build:** Use a 24px-radius pale canvas with a repeating radial-gradient of black at 5% alpha, 1px dots on a 20px lattice. Place one dominant rectangular artifact and two smaller offset artifacts, with white 4px edges and low-alpha black shadows; keep perspective gentle and all functional product colors inside the artifacts.

### Atmospheric light and human pair

**Use:** A warm closing editorial counterpoint to the technical chapter.

**Observed:** Two 588×784px portrait images pair a candid indoor gathering in warm brick-and-lamp light with hands beneath luminous gold particles on a dark charcoal backing. Both have 24px rounded corners; the imagery is much larger than its short captions.

**Transfer:** Pair a real human activity with a poetic depiction of the product's possibility. Preserve warmth, darkness and points of light even when the subject changes.

**Build:** For the atmospheric counterpart, create a dark portrait SVG with two broad curved particle ribbons sweeping diagonally upward. Scatter small warm gold and cream circles of varied opacity along the paths; layer a blurred low-alpha amber copy beneath sharp points, concentrating brightness near the center and tapering at the edges. Add a dark foreground silhouette only when it clarifies the interaction.

### Documentary ribbon

**Only for:** enterprise enablement and culture pages

**Use:** Broad gray proof bands.

**Observed:** Enterprise material shows rounded 384×216px workshop photographs in an edge-clipped horizontal ribbon. Culture material alternates 450×300px and 450×600px candid images centered on one horizontal axis: people, office architecture, outdoor life and informal details. Color is natural and lighting unpolished.

**Transfer:** Use real documentary images, keeping unequal aspect ratios for culture and uniform landscape frames for enablement.

### Flowing energy field

**Only for:** culture mission sections

**Use:** Wide atmospheric mission media.

**Observed:** A 1216×501px rounded landscape is filled by winding golden filaments on deep red-black, with bright knots, wispy branches and a luminous upper-right edge.

**Transfer:** Make a metaphor for the organization's ambition rather than another product interface.

**Build:** Layer several SVG cubic Bézier paths across a dark red-black field, varying fine amber strokes with brighter cream cores. Duplicate paths with Gaussian blur for glow; add branching thin paths and a soft warm radial bloom near the upper-right. Keep this confined to the media frame, not the page background.

### Icons

**Observed:** Functional icons are compact monochrome SVGs: 16px checks or chevrons, 20px gray accordion plus signs with 2px round strokes, and a 44px filled submit arrow. Footer social marks are white silhouettes in black 40px circles.

**Transfer:** Use plain rounded-stroke utility icons with no colored badge backgrounds; reserve solid silhouettes for submit and social destinations.

## Section recipes

How recurring sections are built.

### First screen: Cinematic workbench opening

**Observed:** Back to front: a viewport-filling 1440×900px media stage, a dark scrim, transparent 64px navigation, centered white promise and action, then Prompt workbench crossing the bottom boundary. The display sits in a 576px column around the middle of the scene, balanced into two lines at 52px/1.2 weight 500 and -0.04em. A 22px support sentence and Hero button follow with 20px gaps. Within the first 900px the viewer sees the media subject, all headline/support/action content and the upper part of the glass workbench beginning near the lower fifth; its suggestions and the Announcement capsule fall below the fold. The complete opening including overlap is 1028px tall.

**Transfer:** Use this as the default marketing opening. If there is no video, stage an object or authentic output sheet with cinematic lighting and use a useful foreground entry tool. Enterprise openings use a compact identity badge, wider centered promise and a team-contact action over a still image. Recruitment and pricing openings are white, with the headline beginning 160px below the 64px navigation: recruitment adds support, two 48px actions and wide human media; pricing adds savings copy and a billing switch before plan cards.

**Avoid:** Do not replace the opening with a split text-and-card dashboard, enlarge the headline to fill the viewport width, or put the foreground tool fully above the main action.

**Text style:** `display` — __graphik_7126cf 500 · 52px/1.2 · tracking -0.04em

### Manifesto and trust strip

**Observed:** A centered 52px statement occupies a broad white section with 144px vertical padding. A short gray trust line precedes an edge-clipped row of monochrome partner marks by 40px; the strip is about 133px tall.

**Transfer:** Use one conviction and a restrained proof strip. Genuine logos can be replaced by text-only verified endorsements without changing the monochrome rhythm.

### Heading pair and media proof

**Observed:** Heading and Support sit 20px apart in a 768px introduction; a Section button can align right. Main media begins 80px later. A 1216×532px lead stage or equal 588px pair is followed by title, 10px gap and body; captions sit outside imagery.

**Transfer:** Use for product chapters with one broad visual claim followed by supporting detail.

**Text style:** `heading` — __graphik_7126cf 500 · 48px/1.2 · tracking -0.04em

### Technical-depth chapter

**Observed:** Black chapter holds a white heading and gray support, then a wide rounded initiative image, a paired media row with bold technical names, and a three-column editorial row. White Section buttons reverse against black; Editorial category and dates stay gray.

**Transfer:** Use the inversion for technical substance appropriate to the new product. The device is a substantial alternate reading environment, not a requirement to discuss models or research.

**Text style:** `heading` — __graphik_7126cf 500 · 48px/1.2 · tracking -0.04em

### Editorial lead and grid

**Observed:** A white Heading pair introduces a wide lead image with metadata and a 22px title, followed by three 392px landscape cards with 20px gutters and 40px row separation. There is no painted card wrapper around the caption.

**Transfer:** Use for releases, customer work or relevant learning material; lead with one story and give the rest a consistent small format.

### Portrait destinations and footer

**Observed:** Heading pair introduces two tall rounded images with an 80px gap above them; 32px destination links and 18px descriptions follow. After 160px of separation the Footer directory closes on white. All page types share that footer; pricing proceeds to it after utility tables, enterprise after the submit action, and recruitment after a centered 22px gray question with a black 48px contact capsule.

**Transfer:** End a broad marketing story on people and possibility, but let transactional pages finish their task cleanly before the same restrained directory.

### Plan comparison and cost ledger

**Only for:** pricing pages

**Observed:** Centered display, savings note and 257×60px billing switch lead to three Plan cards and then two business panels. Monochrome trust strip separates plans from detailed cost tables. Tables use 32px centered headings, 40px heading-to-table spacing, 16px outer corners, a 1px black perimeter, black header rows and merged cells. Rows are about 69px with 20px cell padding; groups alternate white and panel gray, with black-at-40% internal rules. Video, image, audio and utility ledgers continue to the footer without a sales CTA.

**Transfer:** Keep the polished overview and dense reference ledger as two different reading modes; retain group striping and merged labels for complex comparisons.

### Enterprise proof and inquiry

**Only for:** enterprise landing pages

**Observed:** Two-column media capabilities lead to Neutral band documentary proof, then a three-column use-case gallery. Testimonial cards use alternating wide/narrow spans. A centered Heading pair precedes an 832px usable form, with 32px grid gaps and a full-width submit capsule before Footer directory.

**Transfer:** Move from capabilities through people-backed proof into an explicit contact task instead of adding a generic final banner.

### Culture facts and benefits

**Only for:** recruitment pages

**Observed:** Small black labels introduce tight Culture headings and gray support. Wide mission media leads into four 289×144px centered fact panels. Benefits use two 598px columns, 32px padding and small black upper-right badges. Process panels invert to white on a gray band and begin with a 21×21px black number tile with 5px corners.

**Transfer:** Use ordinary-scale 32px statistics rather than giant numerals; convert tangible benefits and process steps into distinct card constructions.

### Directory and questions

**Only for:** recruitment pages

**Observed:** A 48px listing heading and support precede search and filters. A sticky pale toolbar sits above a 148px category rail and results; rows are 46px tall with 10px 6px padding, faint top rules, 18px titles and 12px right-aligned locations. A light fallback-application panel follows the list, then a gray process band, Question accordion stack and the small centered contact close.

**Transfer:** Keep selection interfaces much denser than narrative chapters, and offer a useful fallback path after results rather than treating the directory as the page ending.

## Page flow

**Storyline:** Promise → visible work → reasons to trust → deeper capability or practical detail → human context or direct task → restrained directory.

### Broad product and brand landing

1. **Promise** — Immersive output stage with centered copy and overlapping task entry.
2. **Positioning and social proof** — Compact update, broad conviction statement and monochrome logo strip.
3. **Product demonstration** — Heading pair and wide angled work surface.
4. **Technical credibility** — Substantial black chapter with lead, paired features and editorial grid.
5. **Freshness and human context** — White editorial lead/grid, then tall human and atmospheric destination pair.
6. **Ending** — Ruled white directory with wordmark, social circles and three link columns.

**Transfer:** Keep the alternation between image-led promise, concrete output, technical depth and human warmth; adapt the number and order of chapters to the story.

### Plan selection and detailed usage reference

1. **Selection** — White centered headline, savings note, capsule billing switch and inverted highlighted plan.
2. **Business option** — Two wider contact-oriented plan panels.
3. **Social proof** — Monochrome partner strip.
4. **Practical detail** — Successive grouped cost ledgers with black headers and gray group bands.
5. **Ending** — Utility ledger ends directly above the common white footer.

**Transfer:** Separate simple buying decisions from exhaustive accounting details rather than squeezing both into plan cards.

### Organizational adoption and lead generation

1. **Promise** — Cinematic object stage, identity badge and team-contact capsule.
2. **Capability and trust** — Logo strip and two-column capability media.
3. **Enablement proof** — Gray documentary ribbon.
4. **Use cases and social proof** — Three-column output gallery and asymmetric testimonial cards.
5. **Conversion** — Centered invitation and labeled inquiry form.
6. **Ending** — Full-width submit then the same ruled white directory.

**Transfer:** Tie the adoption promise to output, human support and proof before asking for qualification information.

### Recruitment and role discovery

1. **Invitation** — White centered promise, dual actions and wide candid media.
2. **Belief and practical value** — Mission media, compact fact cards and benefit panels.
3. **Human context** — Unequal-format documentary photo ribbon.
4. **Selection** — Search, category rail and dense role rows; fallback application callout.
5. **Objection handling** — Numbered process panels and rounded question accordion.
6. **Closing call** — Small centered contact prompt, then common directory.

**Transfer:** Alternate ambition with concrete practical information, and complete the selection journey with questions and a human fallback.

## Writing

Confident, expansive about possibility and concrete about getting work done. Technical ambition is expressed in plain language, while practical sections become candid, direct and helpful.

**Do not copy:** Do not reuse Luma names, logos, model names, partner marks, proprietary imagery, employee or customer identities, quotations, numerical achievements, prices or unverified comparative claims. Source examples illustrate phrasing only.

- **Addressing the reader:** Speak directly to the reader as you and your; use we for the team and the product name when explaining what it does.
- **Rhythm:** Short headline clauses, one or two support sentences, then specific descriptions. Mix fluent sentences with terse fragments that make workflow benefits feel immediate.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Position the product as an enabling partner, or invite the reader into a consequential task. | 5–10 words | “[Brand] is your creative partner”<br>“Build the future of imagination” |
| Support | Begin with the reader's intent and make the next outcome sound attainable. | 10–30 words | “You have the idea. [Brand] helps make it real.” |
| Section heading | A plain-language transition from intent to visible output. | 3–7 words | “Where ideas become the work”<br>“Ready for professional workflows” |
| Feature description | Explain capability in context, then end on a crisp operational benefit. | 20–55 words | “Create image, video, and sound in one place—developed together, in context. From campaigns to product stories, everything stays connected from brief to delivery. No tool sprawl. No broken handoffs.” |
| Action | Short verb phrase with a clear destination or low-commitment next step. | 2–5 words | “Try for free”<br>“Talk to our team”<br>“Apply anyway” |
| Reassurance | State what happens next, respectfully and without ceremony. | 12–30 words | “We review every application carefully. Expect to hear back within a week.” |

**Words and phrasing to use:** make; build; work; ideas; your team; in context; from brief to delivery; what's next

**Avoid:** synergize; disruptive ecosystem; magical one-click everything; excessive exclamation marks; abstract adjective stacks

**Rules:**

- Lead with the reader's intended work, then explain the mechanism.
- Use concrete workflow nouns and verbs instead of relying on superlatives.
- Let technical passages be substantive without changing to academic syntax.
- Keep functional labels literal; save expressive language for the promise and section headings.
- Pair broad ambition with specific, verifiable practical detail.

## Do's and Don'ts

### Do

- Keep the default 52px headline centered in a 576px column over media.
- Use 48px section headings with 20px support gaps and 80px media separation.
- Keep ordinary feature headings weight 500; reserve 700 for technical names.
- Use 24px corners for media and 16px for plan panels and prompt inputs.
- Make all conversion capsules monochrome at the 32px, 40px or 48px size appropriate to their role.
- Include the overlapping useful workbench and a substantial dark technical chapter.
- Keep colored output inside media; include a warm atmospheric image to balance the interface work.
- Finish with the 80px-separated ruled footer and 160px bottom padding.

### Don't

- Do not give every media caption an enclosing painted card; the editorial default is open on the page.
- Do not add a brand-colored CTA or gradient headline to the monochrome shell.
- Do not turn the 32px fact values into oversized decorative counters.
- Do not apply workbench shadows to the full card grid; ordinary panels rely on fill or a faint edge.
- Do not use 24px capsule-like rounding for 36px form inputs; keep their 6px utility corners.
- Do not make a technical name's 700 weight the default for all headings.
- Do not replace candid culture photography with uniformly lit corporate headshots.
- Do not append a giant closing sales banner after a completed ledger or inquiry form.

## Motion and responsive

### Motion

**Observed:**

- Declared opacity transitions use .15s cubic-bezier(.4,0,.2,1); action color and background transitions use 0.15s with the same curve.
- Some media transforms declare 0.3s cubic-bezier(0,0,.2,1). Hero media changes while the foreground copy and invitation remain legible.
- Named accordion and hero-search keyframes exist, but no matched running animations establish their playback.

**Transfer:**

- Retain short opacity changes for navigation and brief neutral fill transitions for capsules.
- Treat moving output media as the cinematic backdrop; keep the task entry visually stable enough to use.

**Unknown:**

- Exact hero playback, scroll choreography and accordion durations are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 500px, 640px, 768px, 1024px, 1280px and 1536px.
- Layout class declarations distinguish single-column bases from two-column media and three-column editorial desktop grids. Major vertical gaps use 80px on smaller layouts and 160px at larger layouts.

**Transfer:**

- On narrow layouts stack media cards and captions while retaining the cinematic stage and foreground invitation as a layered composition.
- Let prompt suggestions wrap, preserve the primary promise/action above them, and keep directory metadata subordinate when moved below a title.
- Reduce the number of footer link columns rather than shrinking 14px link text.

**Unknown:**

- Exact mobile navigation behavior, hero framing and narrow-screen type sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
