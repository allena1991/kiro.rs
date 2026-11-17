# Proofmode — slab meets pixel field

## Overview

A civic-minded technical style that pairs an approachable slab serif with practical sans-serif text and monospaced action labels. Warm off-white, vivid spring green and pale mint support documentary photography, floating data labels and chunky pixel-cut transitions. Spacious marketing compositions give way to dense, readable technical stories, with a surprisingly bright pink-and-orange closing band.

### Essentials

- Editorial headlines meet utility markings: Montagu Slab at 60px/1.1, weight 400, normal tracking leads; Geist Mono at 16px/24px in capitals identifies actions.
- The opening is a centered statement over a photographic evidence strip: a two-line headline within 832px, 20px/28px support 20px below, then portrait media 240px wide with floating white metadata pills.
- Color works in chapters rather than confetti: off-white opens the page, a full-width spring-green capability field occupies roughly a third of a broad landing story, and pink plus orange are reserved for the compact closing pair above a forest-green footer.
- Actions are small capsules, not heavy rectangles: 40px height, 16px side padding and fully rounded ends; directional links separate their uppercase label from a 40px circular green arrow.
- Square-cut pixel shorelines interrupt otherwise smooth surfaces: full-width 336px SVG transition fields connect chapters. Include this geometric device even without product photography, using a tiled silhouette around an original product diagram.
- Media carries its own annotations: white 37px metadata capsules with separate icon cells overlap straight-edged pictures; larger capability cards use 40px corners, pale mint gradients and 64px insets.
- The ending is a color-block invitation followed by a technical map: two equal 248px-high pink and orange panels, then a 572px forest footer with white link columns and a low-contrast green halftone field on the right.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest | `#1e3834` | `--color-forest` | background, text, action, border | Footer, dark action capsules, compact section headings and outline controls. |
| Spring green | `#7ae377` | `--color-spring` | background, border, accent | Capability chapter fills, pixel transitions, social marks and news separators. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orange | `#f38536` | `--color-orange` | background, accent | Right closing subscription panel and negative-status capsules. |
| Signal green | `#51da4d` | `--color-signal` | action, surface, accent | Topic chips, positive indicators, subscribe button and gradient edges. |
| Orchid pink | `#ed9ef3` | `--color-pink` | background | Left closing invitation panel, not a general feature-card fill. |
| Pale mint | `#cdf5cc` | `--color-mint` | surface, background, border | Gradient ends and light action hover fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text | Default headings, body and arrow icons. |
| Secondary gray | `#3f3f3f` | `--color-muted` | text | Secondary service-invitation copy. |
| Stone gray | `#e3e3e1` | `--color-stone` | surface, border | Subtle card-gradient edging; a full band is reserved for technical-service closings. |
| Warm off-white | `#f4f4f2` | `--color-canvas` | background, surface | Primary page ground and the light start of gradients. |
| Soft white | `#f3f4f6` | `--color-footer-copy` | text | Small footer attribution text. |
| White | `#ffffff` | `--color-white` | surface, text, border | Metadata pills, FAQ surfaces and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product instructions | Instruction green | `#349d36` | `--color-instruction-link` | link | Bold underlined links embedded in procedural copy. |
| technical articles | Article slate | `#364153` | `--color-article-copy` | text | Long-form paragraphs. |
| technical articles | Article heading ink | `#101828` | `--color-article-ink` | text, link | Headings and underlined links in long-form technical prose. |
| technical demonstrations | Console slate | `#1e2939` | `--color-console` | surface | Transcript panels in technical demonstrations. |
| technical demonstrations | Console text | `#e5e7eb` | `--color-console-text` | text | Light text inside terminal demonstrations. |

## Typography

- **Montagu Slab** — Headlines, section titles and small product-name lines. Broad, sturdy slab serif with editorial warmth and conspicuous serifs; regular rather than bold. Font stack: "Montagu Slab", Georgia, serif.
- **Public Sans** — Navigation, explanatory copy, metadata and small tags. Matter-of-fact open sans serif that remains legible beside ornate headlines. Font stack: "Public Sans", Arial, sans-serif.
- **Geist Mono** — Action labels, product categories and footer headings. Straight technical monospace, normally regular weight and uppercase. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Montagu Slab | 400 | 60px | 1.1 | normal | Primary marketing and article headline. |
| heading-lg | Montagu Slab | 400 | 46px | 1.1 | normal | News section titles and large photographic story headlines. |
| heading | Montagu Slab | 400 | 30px | 1.1 | normal | Centered capability, FAQ and service-invitation titles, usually forest green. |
| story-title | Montagu Slab | 400 | 30px | 1.5 | normal | News row titles and instructional step titles. |
| closing-title | Montagu Slab | 400 | 24px | 32px | normal | Short two-line invitations in the closing color pair. |
| product-category | Geist Mono | 400 | 22px | 1.5 | normal, uppercase | Functional name directly beneath the product-name line. |
| product-name | Montagu Slab | 400 | 20px | 1.4 | normal | Small product or family name above its monospaced category. |
| lead | Public Sans | 400 | 20px | 1.4 | normal | Hero support, capability-card descriptions and FAQ questions. |
| body | Public Sans | 400 | 16px | 1.5 | normal | Navigation, news summaries and instructional descriptions. |
| action | Geist Mono | 400 | 16px | 1.5 | normal, uppercase | Buttons, directional links, feature labels and footer column headings. |
| caption | Public Sans | 400 | 14px | 20px | normal | Metadata, dates and footer links; underline only actual links that need it. |
| tag | Public Sans | 400 | 14px | 20px | normal, uppercase | Topic chips, status values and subscribe label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| photographic case studies | case-label | Geist Mono | 400 | 30px | 1.5 | normal, uppercase | Large label above a full-bleed photographic story. |
| technical articles | article-heading | Montagu Slab | 400 | 30px | 40px | normal | Main chapters within prose. |
| technical articles | article-subheading | Montagu Slab | 400 | 30px | 1.6 | normal | Capability subsections within prose. |
| technical articles | article-body | Public Sans | 400 | 20px | 1.75 | normal | Sustained technical prose. |
| technical articles | article-link | Public Sans | 500 | 20px | 1.75 | normal | Underlined inline references in long-form prose. |
| product instructions | instruction-link | Public Sans | 700 | 16px | 1.5 | normal | Green underlined inline action within instructional copy. |

**Notes:**

- Keep normal tracking throughout; the contrast comes from family and size rather than tight letter spacing.
- Regular-weight slab headlines are the default. Reserve stronger sans weight for instructional links, not display headlines.
- A 30px title is deliberately context-dependent: compact centered titles use 33px leading, news titles 45px, article chapters 40px and article subheads 48px.

## Layout

**Density:** Airy at the chapter level, compact inside labels and navigation; dense only in long-form technical content.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Vertical spacing between floating metadata rows; header vertical inset. |
| 12px | Icon-to-label gaps within pills. |
| 16px | Button side padding, container inner gutter, news-grid gaps and title-to-summary spacing. |
| 20px | Hero heading-to-support gap, card text stack gaps and FAQ padding. |
| 40px | News-row vertical padding and closing-panel vertical insets. |
| 56px | Footer vertical padding and separation around instructional images. |
| 60px | Capability-grid gutters. |
| 64px | Default section vertical padding, card inner padding and gap before hero imagery. |
| 80px | Closing-panel horizontal insets and separation between grouped content blocks. |
| 96px | Footer gap above attribution copy. |

### Containers and grids

- **Marketing container**: max width 1280px · side padding 16px. Centered desktop wrapper; at 1440px the content spans 1248px with visible left and right edges at 96px.
- **Header**: side padding 40px. Full-width horizontal navigation, 84px tall, identity left and actions right.
- **Capability grid**: 2 columns · gap 60px. Two equal 594px cards within the marketing container, followed by full-width feature or service cards.
- **News grid**: 12 columns · gap 16px. Text takes the left half; author portrait, topics, date and arrow align across the remaining columns.
- **Closing pair**: 2 columns · gap 0px. Two equal, edge-to-edge invitation panels with no intervening gutter.
- **Instruction grid** (only for product instruction pages): 3 columns · gap 80px. Equal image-led steps with centered copy and 350px-wide media.
- **FAQ grid** (only for product instruction pages): 2 columns · gap 40px. Two columns of 604px-wide questions, with 20px row gaps.
- **Article column** (only for technical articles): max width 636px. Centered prose; media may widen to 836px, extending 100px beyond either side.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Capsules | 9999px (pill) |
|  | Capability cards | 40px |
| product instruction pages | FAQ panels | 20px |
| technical demonstrations | Transcript panels | 6px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default ground.

**CSS:** `background: #f4f4f2; color: #000000`

**Observed:** Warm light ground, without texture or elevation.

**Transfer:** Let typography and original media provide detail.

#### Green chapter · level 0

**Use:** Capability field.

**CSS:** `background: #7ae377`

**Observed:** A broad continuous fill connected to neighboring chapters by pixel shorelines.

**Transfer:** Group a coherent capability story inside this field rather than coloring every section independently.

#### Mint card · level 1

**Use:** Capability and horizontal service cards.

**CSS:** `background-image: linear-gradient(to right bottom, #f4f4f2, #cdf5cc), linear-gradient(to right, #cdf5cc, #e3e3e1); background-clip: padding-box, border-box; border: 2px solid transparent; border-radius: 40px; box-shadow: none`

**Observed:** Soft pale face with a barely visible gradient edge, set directly on green.

**Transfer:** Keep the material subtle; use layout and imagery rather than a drop shadow to separate cards.

#### Mint wash · level 0

**Use:** News chapter backing.

**CSS:** `background: linear-gradient(to right bottom in oklab, #f4f4f2 0%, #cdf5cc 100%)`

**Observed:** A broad, restrained diagonal wash. Instructional chapters use a vertical version; technical news uses plain paper.

**Transfer:** Use to soften a long text-led chapter without creating a panel around every row.

#### Closing pink · level 0

**Use:** First closing invitation.

**CSS:** `background: #ed9ef3; color: #000000`

**Transfer:** Pair with Closing orange, not as an isolated accent card.

#### Closing orange · level 0

**Use:** Second closing invitation.

**CSS:** `background: #f38536; color: #000000`

**Transfer:** Keep the same geometry as Closing pink.

#### Forest footer · level 0

**Use:** Site-ending navigation and attribution.

**CSS:** `background: #1e3834; color: #ffffff`

**Observed:** Flat dark field with faint green halftone art behind the right-hand actions.

**Transfer:** Use the halftone as decoration below the links, never as a foreground competing with them.

#### Service gray · level 0

**Only for:** technical article closings

**Use:** Two-column developer and integration invitation.

**CSS:** `background: #e3e3e1`

**Observed:** Pixel-edged top, centered titles and short supporting copy.

**Transfer:** Use for a restrained professional-services invitation after a dense article.

#### Transcript · level 1

**Only for:** technical demonstrations

**Use:** Real code-session examples.

**CSS:** `background: #1e2939; color: #e5e7eb; border-radius: 6px; padding: 12px 16px`

**Observed:** Long dark preformatted panels in an otherwise light prose column.

**Transfer:** Include authentic legible output only when it supports a technical explanation.

## Components

### Navigation

**Use:** Shared desktop site header.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 10px 40px; height: 84px`

**Text style:** `body` — Public Sans 400 · 16px/1.5

**Observed:** Identity on the left, four plain-text menu groups with small downward chevrons in the middle, two capsule actions on the right. Navigation links have 20px padding.

**Transfer:** Keep the header utilitarian and shallow; do not turn menu links into filled tabs.

### Dark capsule

**Use:** Primary installation or adoption action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; gap: 12px; border-radius: 9999px; background: #1e3834; color: #ffffff`

**Text style:** `action` — Geist Mono 400 · 16px/1.5 · uppercase

**Observed:** A compact all-caps action paired with a lighter utility action in the header.

**States:** Declared: hover background-color #235134; focus-visible unknown.

### Gradient capsule

**Use:** Secondary header action and circular directional controls.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; border: 1px solid transparent; border-radius: 9999px; background-image: linear-gradient(to right, #7ae377, #cdf5cc), linear-gradient(to right, #cdf5cc, #51da4d); background-clip: padding-box, border-box; color: #000000`

**Text style:** `action` — Geist Mono 400 · 16px/1.5 · uppercase

**Observed:** The circular variant is 40px square with no horizontal padding and a centered 20px arrow.

**States:** Declared: hover background-color #235134; focus-visible unknown.

### Directional link

**Use:** Actions inside cards and service invitations.

**CSS:** `display: flex; align-items: center; height: 40px; color: #000000`

**Text style:** `action` — Geist Mono 400 · 16px/1.5 · uppercase

**Observed:** Transparent label cell with 16px right padding touches a separate Gradient capsule circle. The photographic variant reverses the label to white.

**Transfer:** Keep label and arrow distinct, rather than placing both inside one wide filled button.

### Capability card

**Use:** Present one product function beside a visual.

**CSS:** `padding: 64px 64px 0px 64px; border: 2px solid transparent; border-radius: 40px; overflow: hidden; background-image: linear-gradient(to right bottom, #f4f4f2, #cdf5cc), linear-gradient(to right, #cdf5cc, #e3e3e1); background-clip: padding-box, border-box`

**Text style:** `lead` — Public Sans 400 · 20px/1.4

**Observed:** Small serif product-name over uppercase mono category, a narrow description, then Directional link on the left. An image or device occupies the right half and can terminate at the card's lower edge. A horizontal variant spreads the name, explanation and arrow across one row.

**Transfer:** Use one strong original visual per card and keep copy short enough to preserve its narrow column.

### Metadata capsule

**Use:** Attach contextual facts to media.

**CSS:** `display: flex; align-items: center; height: 37px; padding: 0px 16px; gap: 12px; border: 1px solid transparent; border-radius: 9999px; background: #ffffff; color: #000000`

**Text style:** `caption` — Public Sans 400 · 14px/20px

**Observed:** Separate white circular icon cell touches a white text capsule; rows stack with 10px gaps and overlap picture edges. Status values append a green or orange pill with a white border.

**Transfer:** Attach meaningful product facts such as source, date, author or state; retain the independent icon, label and value cells.

### Topic chip

**Use:** Small taxonomy and subscribe action.

**CSS:** `display: flex; align-items: center; height: 37px; padding: 0px 16px; border: 1px solid transparent; border-radius: 9999px; background: #51da4d; color: #000000`

**Text style:** `tag` — Public Sans 400 · 14px/20px · uppercase

**Observed:** Short uppercase sans labels; news chips and the photographic read-more label can be 40px high. The subscription action stands alone rather than exposing a large inline input.

### News row

**Use:** Editorial updates and related reading.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 16px; padding: 40px 0px; border-bottom: 1px solid #7ae377`

**Text style:** `story-title` — Montagu Slab 400 · 30px/1.5

**Observed:** Headline and body summary occupy the left half. A small round author image, Topic chips, white date capsule and circular arrow run along the upper right. No enclosing card fill.

**Transfer:** Keep summaries at body size and tags secondary; use rows rather than a thumbnail-card gallery.

### Closing invitation

**Use:** Paired final engagement prompts.

**CSS:** `background: #ed9ef3; color: #000000; padding: 40px 80px; min-height: 248px`

**Text style:** `closing-title` — Montagu Slab 400 · 24px/32px

**Observed:** Left panel uses pink and a compound chip/link action; the right uses orange and a green Subscribe button. The title takes roughly two thirds of the inner width and the action sits 64px below it.

**Transfer:** Use complementary participation and stay-informed invitations, retaining the equal-width color pairing.

### Footer columns

**Use:** Site navigation after the closing pair.

**CSS:** `position: relative; background: #1e3834; color: #ffffff; padding: 56px 40px`

**Text style:** `caption` — Public Sans 400 · 14px/20px

**Observed:** Compact icon at left, four columns of links under action-style uppercase headings, and right-aligned green social marks above pale download capsules. Attribution copy sits below with 96px separation; background halftone remains on the right.

**Transfer:** Preserve useful link hierarchy and a deliberate dark landing after the bright closing pair.

### Download capsule

**Use:** Platform-specific links in the footer.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; gap: 12px; border: 1px solid transparent; border-radius: 9999px; background-image: linear-gradient(#f4f4f2, #ffffff), linear-gradient(to right, #cdf5cc, #51da4d); background-clip: padding-box, border-box; color: #000000`

**Text style:** `action` — Geist Mono 400 · 16px/1.5 · uppercase

**Observed:** Platform mark at the end of each label; vertically stacked and right-aligned in the footer.

**States:** Declared: hover background-color #cdf5cc; focus-visible unknown.

### FAQ panel

**Only for:** product instruction pages

**Use:** Compact disclosure questions.

**CSS:** `position: relative; background: #ffffff; border-radius: 20px; padding: 20px`

**Text style:** `lead` — Public Sans 400 · 20px/1.4

**Observed:** Native details/summary construction; question reserves 40px at the right for a plus symbol, which becomes minus when open. Two columns with 20px row spacing.

**Transfer:** Use questions that remove practical adoption obstacles, not promotional headlines.

## Imagery and graphics

### Annotated documentary strip

**Use:** Default marketing opening.

**Observed:** A horizontal row of straight-edged, richly colored documentary photographs: street scenes, natural phenomena, crowds and a photographer. Portraits are 240px wide, usually 360px tall, with one shorter 320px image; 20px gaps and staggered heights prevent a rigid gallery. The strip bleeds beyond both viewport edges. White Metadata capsules overlap selected pictures.

**Transfer:** Show varied real situations where the product matters. If no equivalent photographs exist, use original product artifacts or diagrams in the same portrait rhythm, annotated with genuine facts; do not substitute unrelated stock scenery.

### Pixel shoreline

**Use:** Signature chapter boundaries and media cutouts.

**Observed:** Hard-edged square steps and isolated checkerboard holes connect light paper, green chapters and photographic sky. The full-width SVG field is 1440px by 336px; its center is relatively level while irregular activity concentrates near the sides.

**Transfer:** Include a square-grid cut edge somewhere in every new page. Reuse the grammar across section boundaries or media masks without repeating an exact silhouette.

**Build:** Create an SVG viewBox 0 0 1440 336. Start with a filled lower rectangle and add or subtract axis-aligned square tiles, using a roughly 45px grid as a construction guide. Step the outline by one or two rows near each edge, retain a long calm center, and cut several isolated square holes. Fill with spring green or the adjoining surface color; for a media edge apply the same path as an SVG mask. No blur, strokes or rounded corners.

### Capability media

**Use:** Inside Capability card and full-width photographic cards.

**Observed:** One card shows a dark-edged smartphone framing a vivid rocket launch, with a green app icon overlapping its lower corner. Another uses a vertical warm sunlit street image with floating metadata. A wider developer card uses a darkened real workspace photograph and white text.

**Transfer:** Use original product screens inside a simple believable device frame or a tightly cropped relevant photograph. Keep the picture large relative to the narrow text column and clip at the outer card boundary; for software without device imagery use a clear artifact or workflow view.

### Photographic story

**Use:** Full-width case-study chapters.

**Observed:** A large city panorama fills an approximately 1165px-tall stage, with generous sky above and white title/action content in the lower left. A black gradient darkens the lower image from transparent at 56.4% to 60% black at 83.2%; a pixel shoreline joins its top to the preceding field.

**Transfer:** Choose a broad real environment tied to an actual use story, retaining sufficient calm space for the headline and a legible darkened lower portion.

### Footer halftone

**Use:** Signature texture behind footer actions.

**Observed:** A low-contrast field of small green squares forms irregular larger patches on forest green, strongest at the right edge and fading toward the link columns. It is decoration, not a chart.

**Transfer:** Always give the dark closing field this restrained technical texture; it can be generated geometrically without a recognizable picture.

**Build:** Generate an SVG grid of small square marks across a right-anchored field up to 1017px wide and 572px high. Use spring green with varied low alpha over forest; modulate square size or opacity in broad irregular patches, then fade left with an SVG linear-gradient mask. Keep full opacity out of text areas and place below all controls. Match the subtle texture rather than requiring exact cell counts.

### Technical artifacts

**Only for:** technical articles

**Use:** Article opener and explanatory figures.

**Observed:** Opening splits a left-aligned slab headline from a 712px by 574px terminal photograph on the right, whose lower edge is pixel-cut into the canvas. Within the article, genuine app settings, analysis screens and terminal images expand to 836px beyond the narrower prose column. Some include direct red annotation.

**Transfer:** Use real figures that demonstrate the explanation, not an aspirational dashboard. Maintain their own content proportions, and use the pixel mask on the opening media rather than rounding every figure.

### Icons

**Observed:** Actions use 20px black arrows with 1px outline strokes and butt caps; metadata uses mostly solid 24px black symbols in separate white cells. Small benefit checks are 24px forest outlines at 1.5px. Footer social marks are 36px spring-green solids.

**Transfer:** Choose simple recognizable utility symbols. Keep fine outlined arrows separate from filled metadata and social icons, and avoid bulky enclosing squares except for the identity mark.

## Section recipes

How recurring sections are built.

### First screen: Annotated strip opening

**Observed:** Paper canvas supports an 84px Navigation bar. After 64px of space, a centered 60px/66px slab headline spans about two thirds of the content width and wraps to two lines; the support line follows 20px later at 20px/28px. Another 64px leads into the full-bleed Annotated documentary strip, about 360px high, with staggered 240px portrait tiles and floating Metadata capsules. Layers are paper, pictures, then annotation cells, followed by the rising green Pixel shoreline at the bottom. Within the first 900px the navigation, complete headline, support, media strip and beginning of the green boundary are visible. Capability cards begin below the fold. Actions are in the header rather than a centered hero-button stack.

**Transfer:** Start with a succinct product outcome and stage varied real artifacts below it, retaining the annotation grammar even without photography. Product-list openings keep the centered headline and support but introduce the green capability field sooner, without the photo strip. Technical articles instead use a left headline beside a large pixel-cut artifact image.

**Avoid:** Do not replace the first screen with a huge rounded dashboard card, a dark gradient hero or a centered pile of CTA buttons; the first impression depends on the light editorial statement and wide annotated media.

**Text style:** `display` — Montagu Slab 400 · 60px/1.1

### Capability field

**Observed:** Green chapter follows a Pixel shoreline. A centered heading recipe is constrained to roughly half the container, with a row of small mono benefit labels and outline checks below. Capability cards appear in a two-column grid with 60px gutters; wider media and horizontal service cards extend across both columns. A compact monochrome partner-logo row can finish the field.

**Transfer:** Present distinct functions with short descriptions and one visible artifact each. Use authentic affiliations only where they exist; preserve the green chapter and pixel geometry regardless of partner content.

**Text style:** `heading` — Montagu Slab 400 · 30px/1.1

### Photographic case study

**Observed:** Photographic story surface with Pixel shoreline at the top. A case-label in white precedes a 46px/1.1 white slab title constrained to two thirds of the content width. Content sits low in the image; a bright compound tag-and-circle action follows.

**Transfer:** Translate a meaningful customer or field story into one immersive photographic chapter rather than adding a conventional testimonial carousel.

**Text style:** `heading-lg` — Montagu Slab 400 · 46px/1.1

### Editorial rows

**Observed:** Mint wash with 64px chapter padding, heading-lg on the left and a small forest-outline See more capsule on the right. News row repeats underneath, with green separators and a restrained metadata rail. The article variant uses Paper canvas instead of Mint wash.

**Transfer:** Use related reading, releases or substantive proof stories. Keep the row format and do not require a particular number of entries.

**Text style:** `story-title` — Montagu Slab 400 · 30px/1.5

### Chromatic closing and technical footer

**Observed:** Closing invitation forms a full-width pink/orange equal pair, 248px high with 40px vertical and 80px horizontal insets. Short slab titles sit above green actions. Immediately below, Footer columns create a 572px forest field with a compact identity at left, four link groups, pale platform capsules and green social icons at right. Footer halftone stays behind the right side; small attribution text anchors the bottom left. This ending is shared by all page types.

**Transfer:** Retain the contrasting twin invitations and dark textured information footer even when the main content is editorial or instructional. Adapt both invitations to useful next steps instead of turning the whole end into a single oversized sales statement.

**Text style:** `closing-title` — Montagu Slab 400 · 24px/32px

### Instruction and objections

**Only for:** product instruction pages

**Observed:** Vertical pale-mint wash holds a centered heading, then three image-led steps with 80px column gaps. Each has a 350px by 266px figure, small step label, 30px slab title and 16px body description with green instructional links. An 80px separation introduces the FAQ heading and FAQ panel grid.

**Transfer:** Explain an actual workflow in a small number of steps and follow it with practical objections; step count follows the product, not a fixed template.

**Text style:** `heading` — Montagu Slab 400 · 30px/1.1

### Long-form technical explanation

**Only for:** technical articles

**Observed:** A 636.3px prose column uses article-body with 25px paragraph separation. Article-heading chapters have 60px top and 30px bottom margins; article-subheading distinguishes nested capabilities. Wider figures project 100px outside each prose edge. Underlined article-link references and Transcript panels provide direct technical proof. The prose ends with a conversational multi-question invitation and contact link before Editorial rows.

**Transfer:** Develop the argument as problem, opportunity, implementation and worked examples. Keep extended output in the technical variant, not the ordinary marketing page.

**Text style:** `article-body` — Public Sans 400 · 20px/1.75

### Service invitation

**Only for:** product instruction and technical article closings

**Observed:** Compact centered heading, secondary gray body and Directional link. Instruction pages use one centered column on the mint wash; technical articles use two columns on Service gray beneath a pixel boundary.

**Transfer:** Offer a clear expert-help route as an alternate action to self-service.

**Text style:** `heading` — Montagu Slab 400 · 30px/1.1

## Page flow

**Storyline:** Outcome promise → visible artifacts → capability or explanatory chapters → practical proof and useful next steps → paired participation invitations → navigable dark close.

### Broad brand and capability landing page

1. **Promise** — Centered slab statement and one-line explanation above annotated media.
2. **Capabilities** — Pixel-edged green chapter with paired capability cards, wide feature cards and affiliation marks.
3. **Applied proof** — Immersive photographic story with lower-left title and action.
4. **Continued learning** — Editorial news rows with topics and dates.
5. **Closing call** — Equal pink/orange invitations followed by forest navigation, download links and textured backdrop.

**Transfer:** Use this as the default broad landing narrative, adapting emphasis and order to the product while retaining the distinctive media annotations and closing devices.

### Product-family overview with adoption guidance

1. **Promise** — Centered headline and support open directly toward a green chapter.
2. **Product choices** — Paired illustrated capability cards followed by a horizontal expert-help card.
3. **Process** — Image-led sequential instructions on a pale wash.
4. **Objection handling** — Two-column white FAQ disclosures.
5. **Alternate conversion** — Centered specialist invitation.
6. **Closing call** — Shared bright invitation pair and forest footer.

**Transfer:** Prioritize choosing and using the product rather than adding a decorative photo strip that delays the options.

### Technical position and implementation article

1. **Promise** — Split slab headline and pixel-cut terminal artifact.
2. **Problem framing** — Narrow readable paragraphs with linked references and clear chapter headings.
3. **Implementation** — Nested capability explanations with oversized real figures.
4. **Worked proof** — Authentic extended terminal sessions in dark panels.
5. **Discussion invitation** — Conversational questions and a direct contact link.
6. **Continued learning** — Related editorial rows.
7. **Expert help** — Pixel-edged gray service invitation pair.
8. **Closing call** — Shared pink/orange invitations and forest footer.

**Transfer:** Use the denser prose, slate text and figure overflow only for substantive technical content; preserve the common identity through the opening geometry and ending.

## Writing

Plainspoken, collaborative and technically literate. The confidence comes from describing specific capabilities and showing work, with warmth appearing in invitations to participate or ask for help.

**Do not copy:** Do not reuse the Proofmode name, logo, product names, partner marks, proprietary artwork, event stories, dates, sponsor relationships or claims about open-source licensing, privacy, provenance or verification unless they are independently true of the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct verbs for actions and instructions, 'you' for practical questions, and 'we' for the team's work and invitations. Describe the product by what it does rather than speaking in grand abstractions.
- **Rhythm:** Headlines are short outcome statements, often 4–8 words. Support is usually one sentence. Card copy explains one capability in a few narrow lines; articles can sustain longer, qualified paragraphs. Action labels are typically 2–4 words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the desired outcome in plain nouns and verbs; a compact final qualifier gives closure. | 4–8 words | “Media and reality, verified.”<br>“Tools to capture and verify reality” |
| Supporting line | Explain the operations or how the tools relate, without repeating the headline. | 8–16 words | “Capture, notarize and verify media with open, decentralized, and privacy-focused tools.”<br>“Open-source apps and web tools that work together” |
| Primary action | Literal verb plus useful object. | 2–4 words | “INSTALL APP”<br>“Get the app” |
| Practical heading | A simple functional title or direct reader question. | 2–7 words | “How it Works?”<br>“Are you a developer?” |
| Discussion invitation | Several human questions instead of an inflated sales slogan. | Up to three short questions | “Have thoughts? Want to learn more? Need help running this yourself?” |
| Closing invitation | Participation request paired with a specific stay-informed invitation. | 7–12 words | “Help us document the reality of our world.”<br>“Subscribe to get [Brand] updates in your inbox” |

**Words and phrasing to use:** document; inspect; share; build; tools; work together; learn more; get in touch; what is known; step

**Avoid:** revolutionary; magic; game-changing; unparalleled; unlock limitless potential; guaranteed trust

**Rules:**

- State the concrete operation before its broader benefit.
- Use technical terminology when it explains a real mechanism; link to further detail rather than crowding marketing copy with definitions.
- Qualify capabilities honestly and distinguish what is known from what is not.
- Keep uppercase a visual treatment for utility labels, not a tone for body copy.
- Let article invitations sound like a knowledgeable team welcoming collaboration.

## Do's and Don'ts

### Do

- Set primary slab headlines at 60px/1.1 with weight 400 and normal tracking.
- Use 40px capsules and separate 40px arrow circles for actions.
- Keep paired capability cards 60px apart and use their 64px inset to establish the text column.
- Attach 37px white metadata pills to selected media, not every picture.
- Use full-width green chapters bounded by square pixel cuts rather than gradients alone.
- Keep news on open rows with 1px spring-green bottom rules and 40px vertical padding.
- Preserve the equal pink/orange closing pair above the forest footer.
- Use 20px/35px slate prose and a 636.3px column for technical articles.

### Don't

- Do not make the primary headline a bold geometric sans; the regular slab face carries the character.
- Do not tighten tracking into a compressed tech aesthetic; the type recipes use normal spacing.
- Do not add drop shadows to mint capability cards; their 2px gradient edge is enough.
- Do not spread pink and orange across feature grids; their large-fill role belongs to the closing pair.
- Do not round every photograph to 40px; hero strip pictures are straight-edged, while outer capability cards are rounded.
- Do not turn news into floating white tiles; it relies on open rows and green separators.
- Do not turn the footer into pure black or an empty legal strip; forest green, link groups and subdued halftone form a substantial ending.
- Do not promote dark console surfaces into the default marketing background; they belong to technical examples.

## Motion and responsive

### Motion

**Observed:**

- Actions and label surfaces declare .15s transitions with cubic-bezier(.4,0,.2,1) across color, border, opacity and transform-related properties.
- Dark and green capsule controls declare a #235134 background-color hover; pale download and outline actions declare a #cdf5cc hover.
- No keyframe animations are declared in the reviewed styles.

**Transfer:**

- Apply the brief transition to the compact capsule system; keep the pixel shoreline as crisp geometry rather than blurring it during interaction.

**Unknown:**

- Actual menu opening behavior, focus-visible styling, gallery movement and scroll animation timing are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Headline classes specify 48px below the 1024px desktop override of 60px; the same 1.1 line-height relationship is retained.
- Capability layouts declare a column-first arrangement that becomes row-based when space permits; footer columns change from five to eight tracks at desktop.

**Transfer:**

- On narrow screens, stack capability cards and the two closing invitations, preserving the pink/orange distinction. Keep the annotated media strip horizontally clipped rather than squeezing every portrait into one row.
- Reduce the pixel pattern's span while retaining square cells and clear chapter color; prevent annotation labels from becoming unreadable.
- Keep technical prose within the viewport, and allow wide figures to lose their desktop overhang before reducing text legibility.

**Unknown:**

- Exact mobile navigation, pixel-mask scaling, footer order and narrow-screen line breaks are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
