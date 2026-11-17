# Sociotype — specimens at monumental scale

## Overview

An art-directed editorial style that treats a product as a cultural object rather than a dashboard. Monumental lettering and intimate, widely tracked captions share near-edge-to-edge neutral pages, punctuated by luminous abstract photography, printed matter and stark graphic demonstrations. The atmosphere moves between white, warm paper and black; the density is sparse in composition but substantive in its writing, with grotesk navigation and expressive product-specific display faces.

### Essentials

- The opening is a photographic cover, not a centered sales stack: a full 900px stage, 37px navigation, 40px feature title, a dotted divider and a white wordmark spanning the width within 12px gutters.
- Typography itself is an object: 250.4px regular-weight product names sit above a 1px rule, while explanatory text stays at 26px/31px and captions at 12px/16px with 0.08em tracking.
- An editorial rail replaces the feature-card wall: use a 12-column grid with 12px gaps, a two-column index and staggered 345px, 464px, 583px and 702px media plates.
- Color belongs to the work rather than the interface: keep the long reading field neutral, reserve concentrated cyan, yellow and pink for photographic artwork, and use peach only for pill hover states. The full-bleed opening can be entirely photographic; subsequent color is bounded by rectangular media.
- Actions remain typesetting: ordinary calls are dotted-underlined text with a right arrow at 26px; the scoped purchase toolbar uses paired 107px × 35px pills rather than oversized conversion buttons.
- Every page needs a monumental letter or word treatment, a materially rich image and a small technical caption: when product imagery is unavailable, use a lit translucent still life plus an original black-and-white word composition.
- The ending changes register to a white 175px newsletter strip: a 40px email-and-subscribe line above small gray utility links. A 300px photographic editorial band is the richer campaign variant, not a conventional multicolumn footer.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-paper` | background, surface, text, action | Default light reading canvas, proof plates and newsletter footer; reversed lettering on photography. |
| Warm specimen paper | `#f5f0ea` | `--color-cream` | background, surface | Warm reading-field variant for interactive demonstrations and long editorial product stories. |
| Soft reversed ink | `#e7e7e7` | `--color-reverse` | text, link | Display, explanatory copy and captions on the charcoal theme. |
| Paper hairline | `#e3e3e3` | `--color-rule` | border | Newsletter underline and light graphic guide lines. Dark specimen rules use rgba(241,241,241,0.286), appearing approximately #565656 on charcoal. |
| Utility gray | `#818181` | `--color-muted` | text, action | Newsletter entry, subscribe action and footer utility links. |
| Charcoal canvas | `#181818` | `--color-night` | background | Dark chapter canvas; alternate the whole reading field and its foreground, not individual floating cards. |
| Black ink | `#000000` | `--color-ink` | text, background, link | Text on light themes and solid graphic demonstration panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company information and warm demonstration pages | Studio stone | `#d1ccc8` | `--color-stone` | background, action | Whole-page warm gray on company information; also the warm demonstration Buy pill. |
| product purchase toolbars | Purchase gray | `#a8a7a6` | `--color-buy` | action | Secondary purchase pill beside a white trial pill. |
| product purchase toolbars | Peach hover | `#ffd9b2` | `--color-hover` | action | Declared hover fill shared by trial and purchase pills. |
| grotesk product stories | Workhorse charcoal | `#363534` | `--color-work-canvas` | background | Warmer dark reading-field variant. |
| grotesk product stories | Workhorse reversed ink | `#c7c7c7` | `--color-work-ink` | text | Reversed body and display text paired with the warmer dark reading field. |
| grotesk product stories | Toolbar dark edge | `#656462` | `--color-work-edge` | border | One-pixel bottom edge of the warm dark product toolbar. |
| expressive display product stories | Display charcoal | `#252524` | `--color-sharp-canvas` | background | Deep slightly warm chapter field. |
| expressive display product stories | Display reversed ink | `#d8d8d8` | `--color-sharp-ink` | text | Display and body text paired with the deep display charcoal. |

## Typography

- **Main Onsite** — Navigation, editorial copy, captions, chapter headings and utility actions. Regular utilitarian grotesk with open proportions; positive tracking becomes more conspicuous as text gets smaller. If unavailable, use **DM Sans**. Use 400 and retain the positive tracking. Font stack: "Main Onsite", "DM Sans", Arial, sans-serif.
- **Avec Sharp** — Expressive product-name specimens and serif-like display demonstrations. High-contrast serifless Roman with sharp flared terminals and calligraphic proportions. If unavailable, use **Bodoni Moda**. A high-contrast fallback; its serifs differ from the flared original. Font stack: "Avec Sharp", "Bodoni Moda", Georgia, serif.
- **Rework** (only for grotesk product stories) — Continuous introductory statements and giant comparison words. Broad, lightly squared geometric-humanist sans with compact headline spacing. If unavailable, use **DM Sans**. Use light weight for statements; regular for specimens. Font stack: "Rework", "DM Sans", Arial, sans-serif.
- **Ceno** (only for interactive specimen demonstrations) — Centered product-name opening and editable demonstration prose. Humanist sans with classical proportions, generous rounded forms and strongly differentiated weights. If unavailable, use **Lato**. Font stack: "Ceno", "Lato", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| specimen-name | Avec Sharp | 400 | 250.4px | 1.25 | 0.001em | Oversized single product-name specimen; use the displayed product's own expressive face. |
| feature-title | Main Onsite | 400 | 40px | 45px | 0.015em | Opening feature title, editorial banner title and newsletter entry/action line. |
| lead | Main Onsite | 400 | 26px | 31px | 0.025em | Catalog description and More Info action. |
| body | Main Onsite | 400 | 18px | 22px | 0.04em | Editorial paragraphs and left-rail links. |
| navigation | Main Onsite | 400 | 14px | 18px | 0.04em | Global navigation and compact opening support paragraph. |
| utility | Main Onsite | 400 | 13px | 18px | 0.05em | Footer links. |
| caption | Main Onsite | 400 | 12px | 16px | 0.08em | Centered media captions, specification labels and index metadata. |
| label | Main Onsite | 400 | 12px | 16px | 0.08em, uppercase | Newsletter label, credits headings and compact production specifications. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| interactive product comparisons | comparison-word | Rework | 400 | 241px | 1 | normal | Full-width word comparison with baseline rules and option labels. |
| interactive specimen demonstrations | demo-name | Ceno | 300 | 220px | 205px | -0.03em | Centered isolated product name on the white demonstration opening. |
| grotesk product stories | grotesk-statement | Rework | 300 | 75px | 88px | -0.024em | Product name followed inline by a continuous explanatory statement. |
| expressive display product stories | expressive-statement | Avec Sharp | 300 | 75px | 88px | -0.024em | Serifless Roman introductory statement, with selective italic words. |
| long product stories and company information | chapter-heading | Main Onsite | 400 | 26px | 31px | 0.02em | Editorial chapter headings and introductory paragraphs. |
| product purchase toolbars | toolbar | Main Onsite | 400 | 16px | 21px | 0.05em | Product navigation and paired purchase actions. |

**Notes:**

- The working grotesk is deliberately letterspaced: 0.04em for body/navigation and 0.08em for captions. Do not tighten all text to imitate the introductory display statements.
- The product's own face becomes the display object; the UI family stays stable. Display-family changes communicate product character, not arbitrary section decoration.
- The bottom cover wordmark is vector artwork, about 187px high across 1416px at desktop. Recreate its width and visual prominence with original lettering rather than treating the 40px feature title as the dominant graphic.
- Keep chapter headings modest at 26px: their authority comes from isolation, alignment and the 60px gap before body copy, not bold weight.

## Layout

**Density:** Airy editorial composition with compact navigation and captions; long quiet intervals separate relatively narrow text and media.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Media-to-caption separation. |
| 12px | Outer side padding and intercolumn gap. |
| 24px | Inset above large specimen text. |
| 30px | Catalog lead-to-action gap. |
| 60px | Chapter heading-to-body gap. |
| 120px | First reading section after the full-screen cover and initial media separation. |
| 220px | Separation between editable specimen blocks. |
| 240px | Large story-chapter spacing and closing media bottom padding. |

### Containers and grids

- **editorial-grid**: 12 columns · gap 12px · side padding 12px. Viewport-wide desktop grid; 1416px usable width at 1440px. Each column is 107px; a two-column rail spans 226px, six-column media 702px.
- **catalog-rail**: 2 columns · gap 12px. A 226px sticky index beside the remaining ten columns; introductions start after the index and occupy six global columns.
- **story-pair**: 2 columns · gap 12px. Unequal editorial pairs: 583px text in five columns beside 702px media in six, leaving one column of breathing room. Reverse the side across chapters.
- **closing-focus**: max width 702px · side padding 12px. Centered download explanation and document preview; not the maximum width of the entire site.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media-and-panels | 0px |
| product purchase toolbars | purchase-pills | 1000px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default light editorial reading field and white closing strip.

**CSS:** `background-color: #ffffff; color: #000000`

**Observed:** Flat and borderless, with no elevation effects. Warm paper is a whole-field alternate.

**Transfer:** Use a single neutral field through a chapter instead of nesting tinted containers.

#### Dark chapter · level 0

**Use:** Inverse long-form chapter or dramatic graphic stretch.

**CSS:** `background-color: #181818; color: #e7e7e7`

**Observed:** Foreground and canvas change together. Product-story variants use warmer charcoal pairs.

**Transfer:** Let one chapter turn dark as a complete composition; keep media rectangular.

#### Proof plate · level 1

**Use:** Typography, product details and technical comparisons.

**CSS:** `background-color: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** A square or tall rectangular white sheet sits flush within the grid, with a caption outside below. Inverted black sheets also occur.

**Transfer:** Show an actual result, original word graphic or enlarged product detail, not a floating dashboard shell.

#### Warm reading field · level 0

**Use:** Long demonstration and archival story backgrounds.

**CSS:** `background-color: #f5f0ea; color: #000000`

**Transfer:** Pair warm paper with black imagery, white proof plates and restrained document captions.

#### Studio field · level 0

**Only for:** company information

**Use:** Contact, service, credits and cultural editorial content.

**CSS:** `background-color: #d1ccc8; color: #000000`

**Transfer:** Keep the company story on one continuous stone-gray field.

## Components

### Global navigation

**Use:** Persistent lightweight orientation across page types.

**CSS:** `position: sticky; padding: 8px 12px; height: 37px; z-index: 999`

**Text style:** `navigation` — Main Onsite 400 · 14px/18px · tracking 0.04em

**Observed:** Category trigger at left, small brand name centered, four plain utility actions aligned right. White text over the cover; black text on light fields. The bar can slide out as the reader scrolls.

**Transfer:** Preserve the three-way alignment instead of introducing a heavy filled header.

### More info link

**Use:** Default in-flow marketing action.

**CSS:** `font-size: 26px; line-height: 31px; letter-spacing: 0.7px; position: relative`

**Text style:** `lead` — Main Onsite 400 · 26px/31px · tracking 0.025em

**Observed:** Dotted underline on the words, followed by a right arrow; sits below the lead paragraph without a filled container.

**Transfer:** Use a short literal destination with a directional arrow.

### Specimen strip

**Use:** Monumental name or phrase paired with tiny controls.

**CSS:** `border-bottom: 1px solid rgba(241, 241, 241, 0.286); margin-bottom: 55px`

**Text style:** `specimen-name` — Avec Sharp 400 · 250.4px/1.25 · tracking 0.001em

**Observed:** Small family/style labels on the left of the top line, size and reset control on the right. The large text starts beneath, using nearly the full content width; light themes use a subdued dark separator.

**Transfer:** A new product can show its name or an original short output phrase, with a compact mode label and scale annotation.

### Editorial rail link

**Use:** Subfamily or product variant index alongside long catalog chapters.

**CSS:** `position: relative; font-size: 18px; line-height: 22px; letter-spacing: 0.7px`

**Text style:** `body` — Main Onsite 400 · 18px/22px · tracking 0.04em

**Observed:** Dotted-underlined title above a 12px count and a tiny bullet; the containing rail stays sticky while the media moves.

**Transfer:** Use model, material, capability or edition labels, with useful counts only when meaningful.

### Media caption

**Use:** Name or explain the pictured object without a card body.

**CSS:** `text-align: center; font-size: 12px; line-height: 16px; letter-spacing: 1px`

**Text style:** `caption` — Main Onsite 400 · 12px/16px · tracking 0.08em

**Observed:** Centered under the media, with 6px separation. Some examples place tiny mode switches or sequence letters at the right edge.

**Transfer:** Caption the exact detail shown; keep commentary outside the image.

### Newsletter line

**Use:** Shared closing conversion on a white strip.

**CSS:** `display: inline-flex; align-items: center; border-bottom: 1px solid #e3e3e3; height: 46px; width: 701px`

**Text style:** `feature-title` — Main Onsite 400 · 40px/45px · tracking 0.015em

**Observed:** Uppercase newsletter label above. A 498px email entry and 191px gray Subscribe action share a single underline, separated by 12px; the form occupies roughly half the page.

**Transfer:** Keep the field and action typographic rather than boxing them separately.

### Footer utility link

**Use:** Final navigation baseline beneath the newsletter.

**CSS:** `color: #818181; font-size: 13px; line-height: 18px; letter-spacing: 0.7px`

**Text style:** `utility` — Main Onsite 400 · 13px/18px · tracking 0.05em

**Observed:** A sparse left-aligned row; small uppercase copyright is pushed to the far right. No sitemap columns.

### Trial pill

**Only for:** product purchase toolbars

**Use:** Try or obtain a sample before purchase.

**CSS:** `background-color: #ffffff; color: #000000; border-radius: 1000px; width: 107px; height: 35px; padding: 6px 0px 8px`

**Text style:** `toolbar` — Main Onsite 400 · 16px/21px · tracking 0.05em

**Observed:** White pill precedes a gray Buy pill on the toolbar's right side.

**States:** Declared: hover background-color #ffd9b2 and color #000000; focus-visible unknown.

**Transfer:** Keep it compact and pair it with a distinct purchase action rather than using it as a giant hero button.

### Buy pill

**Only for:** product purchase toolbars

**Use:** Purchase action beside the trial.

**CSS:** `background-color: #a8a7a6; color: #000000; border-radius: 1000px; width: 107px; height: 35px; padding: 6px 0px 8px`

**Text style:** `toolbar` — Main Onsite 400 · 16px/21px · tracking 0.05em

**Observed:** Secondary tonal fill; warm paper uses stone gray and expressive display themes use a closely related gray.

**States:** Declared: hover background-color #ffd9b2 and color #000000; focus-visible unknown.

### Product toolbar

**Only for:** product detail and demonstration pages

**Use:** Variant navigation with trial and purchase actions.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 60px; padding: 12px; background-color: #363534; border-bottom: 1px solid #656462`

**Text style:** `toolbar` — Main Onsite 400 · 16px/21px · tracking 0.05em

**Observed:** Variant links cluster left; paired pills sit right. Starts beneath the opening and stays available during product reading. Light paper and deep charcoal themes change the field and edge together.

**Transfer:** Use only for pages with meaningful product modes and direct acquisition.

## Imagery and graphics

### Translucent material cover

**Use:** Signature full-screen cover and a related rectangular editorial plate.

**Observed:** Extreme close-up translucent curved sheets with droplets, black-green edges, misty pale cyan, acid yellow and muted pink. Backlighting makes the folded forms glow; some planes are sharp and finely stippled while others fall out of focus. The opening uses the image edge-to-edge, not inside a mockup.

**Transfer:** Photograph layered colored film, glass or a product material under strong backlight. The minimum equivalent is a high-resolution translucent still life with one dark edge and soft optical overlap, not a generic gradient.

**Build:** Create an original 1440px × 900px composition with three overlapping curved translucent sheets: a cyan back plane, a yellow oval sheet rotated about 25 degrees and a pink narrow fold. In SVG, clip blurred color fields into curved paths, add a black edge with 0.6 alpha, scatter tiny translucent droplets, and overlay fine monochrome turbulence at 0.08 opacity. Use blur between 8px and 35px on distant layers; keep one narrow fold crisp. Export as a full-bleed image and place white type above it.

### Monumental lettering

**Use:** Required brand-scale word graphic and recurring oversized proof objects.

**Observed:** A thin-to-regular white uppercase wordmark spans almost the entire cover bottom. Elsewhere, enormous black or white letters and short words behave like posters, sometimes filling a white plate or crossing delicate baseline guides.

**Transfer:** Use the new brand's name or original short phrase; if it is long, design a two-line composition with equal visual force. Retain a full-width cover word treatment and at least one isolated graphic proof.

**Build:** Set original uppercase grotesk lettering in SVG, fit it within a 1416px-wide viewBox and align its lower edge about 19px above the stage bottom. For proof graphics, place one black letter or two short lines on a white rectangle, then add 1px guide lines and a 12px caption outside the plate.

### Printed object still life

**Use:** Editorial case-study imagery and compact closing campaign band.

**Observed:** Books, loose printed pages and type specimens are photographed on improvised supports: concrete blocks, metal strips, plastic stools and shelving. Light reveals paper edges, ink, stone grain and reflective metal. Color can be vivid within the object scene, while the surrounding page remains neutral.

**Transfer:** Stage a real product artifact or printed explanation among ordinary tactile materials; retain honest shadows and physical scale. Use an original packaging or document mockup if the product is digital.

### Archival and technical plates

**Only for:** long product stories

**Use:** Evidence of origins and close inspection of construction.

**Observed:** Historic posters, inscriptions and printed alphabets alternate with extreme letter details, vector contours, thin measurement rules and before/after sheets. Plates vary from 345px-wide portraits to 1416px-wide panoramas; white backing is flat and captions are small.

**Transfer:** Use archival references relevant to the new product, then pair them with an enlarged mechanism or output comparison. The minimum technical plate is one authentic detail with thin guide lines, not decorative charts.

**Build:** Lay out one enlarged original detail in black on white, add 1px baseline or outline guides and a few small callouts. For comparisons, align two states on identical baselines and place compact state labels below.

### Working studio context

**Only for:** company information

**Use:** Humanize the service and editorial story without a portrait grid.

**Observed:** Wide views of a working room, shelving and pinned prints; neutral daylight, real books and work in progress. Smaller custom-work animations appear as white presentation sheets.

**Transfer:** Show the actual environment and tools of making, with warm neutral light and unstyled evidence of ongoing work.

### Icons

**Observed:** Icons are scarce: 15px reset controls, smaller filled arrows and literal arrow or plus glyphs. Thin rules and small state labels do more work than icon badges.

**Transfer:** Use a small monochrome reset, directional arrow or plus only when it performs a real operation; match the surrounding text color.

## Section recipes

How recurring sections are built.

### First screen: Photographic cover opening

**Observed:** A full 900px stage is occupied by Translucent material cover, with Global navigation overlaid at the top. Above the image sit a left-aligned 40px feature title and a matching right-aligned fractional slide count around 100px from the top, followed by a full-width dotted rule and a compact 14px support paragraph occupying about one third of the width. Monumental lettering anchors the bottom and spans nearly all the width within 12px gutters, about 187px high. The artwork remains the dominant layer between the small top copy and the enormous word graphic. All of these are visible within the first 900px; catalog content begins below. Actions are plain navigation links rather than a filled central hero CTA.

**Transfer:** Create an original material still life or the SVG equivalent described in Translucent material cover; overlay the new brand's giant word treatment, a featured product title and a concise technical description. Product-detail pages instead open on white with an inline 75px statement and a product toolbar below; demonstration pages use a centered 220px name; company information opens with a 40px title and left text/right contact composition.

**Avoid:** Do not replace the visual cover with a centered headline, a rounded software screenshot and two large buttons. Do not omit the bottom word graphic when original photography is unavailable.

**Text style:** `feature-title` — Main Onsite 400 · 40px/45px · tracking 0.015em

### Catalog specimen and rail

**Observed:** Specimen strip spans all 12 columns after a 120px breathing interval. Beneath the rule, Editorial rail link occupies two columns while a 702px lead and More info link begin in the next column group. The illustrated essay continues as staggered rectangular media with Media caption outside each image.

**Transfer:** Use the product name as the typographic object, then organize variants in the rail and distribute tangible proof across unequal plates.

**Text style:** `specimen-name` — Avec Sharp 400 · 250.4px/1.25 · tracking 0.001em

### Editorial chapter pair

**Observed:** A 26px chapter title is centered within its text column, followed 60px later by 18px body text. A five-column text block is paired with a six-column image column. Text can stay sticky while a vertical image sequence advances. Other chapters switch text to the right or use a centered narrower block, with 240px intervals between major passages.

**Transfer:** Explain one characteristic with genuine depth, then prove it in adjacent media. Alternate sides and scale to make a long page read like an illustrated essay.

**Text style:** `chapter-heading` — Main Onsite 400 · 26px/31px · tracking 0.02em

### White newsletter ending

**Observed:** A 175px white strip starts with a 12px uppercase label, followed by Newsletter line at 40px. The last baseline carries Footer utility link at the left and small uppercase copyright at the right. There is no oversized final slogan. Product demonstration pages can precede this with a 40px specification row and a plus; company pages lead directly from the final essay.

**Transfer:** Use one low-friction subscription line and a short utility baseline; preserve the abrupt return to white even after a black chapter.

**Text style:** `feature-title` — Main Onsite 400 · 40px/45px · tracking 0.015em

### Technical proof gallery

**Only for:** product detail pages

**Observed:** An Editorial chapter pair expands into a sequence of Proof plate sheets. Large output words, single symbols, outlines and alternate states fill 702px-wide white rectangles; caption and tiny state control sit below. Full-width comparison words can replace plates, with thin guide lines and compact option labels.

**Transfer:** Show material, output or mode differences on matched scales; make actual product distinctions visible instead of converting them into generic benefits.

### Centered document close

**Only for:** long product stories

**Observed:** A centered 702px block combines a modest chapter title, 60px gap, download link integrated into body copy and a document preview beneath. The preview is about 703px × 497px and leaves 240px below before the closing band or footer. The surrounding chapter can turn black.

**Transfer:** Offer a genuinely useful guide, sample or specification artifact and show its inside pages rather than a decorative cover.

**Text style:** `chapter-heading` — Main Onsite 400 · 26px/31px · tracking 0.02em

### Editorial photo band

**Only for:** campaign-rich marketing and selected product stories

**Observed:** A full-width 300px photographic band shows a printed object in a tightly framed physical scene. Its white 40px title sits at the upper left; 12px uppercase production information sits low at the left. It touches the white newsletter strip directly.

**Transfer:** Feature a related publication, case study or tangible release with a bold material image and a concise factual caption.

**Text style:** `feature-title` — Main Onsite 400 · 40px/45px · tracking 0.015em

## Page flow

**Storyline:** Visual cover → concise product definition → illustrated evidence and capability chapters → useful artifact or editorial extension → shared subscription baseline.

### Present a family of products as an art-directed catalog

1. **Visual promise** — Full-bleed material cover, feature index and monumental lower word graphic.
2. **Product definition** — Large name specimen, sticky variant rail, technical lead and text action.
3. **Capability proof** — Unevenly staggered product art, typographic output and physical publications.
4. **Editorial extension** — Photographic printed-object band.
5. **Closing action** — White newsletter strip and sparse utilities.

**Transfer:** Give each product its own voice and imagery while repeating the same rail, caption and specimen construction.

### Explain the organization, service and cultural perspective

1. **Introduction** — 40px title above a broad 26px introduction and narrow right contact column.
2. **Context** — Wide working-studio film.
3. **Service proof** — Narrow explanation beside large custom-work presentations.
4. **Credibility** — Small uppercase credit labels and plain text client/team lists beside studio imagery.
5. **Point of view** — Editorial explanation in the right half of the page.
6. **Closing action** — Direct transition to the white newsletter strip.

**Transfer:** Use the studio-field variant for an organization story; let actual work and a reasoned point of view carry credibility.

### Let visitors inspect and try a product directly

1. **Product identification** — One centered monumental name on white.
2. **Orientation** — Product toolbar above compact about copy and paired upright/italic style list.
3. **Interactive proof** — Alternating huge editable phrases, alphabet runs and smaller two-column prose samples on warm paper.
4. **Specification** — Collapsed specification heading with a plus.
5. **Closing action** — White newsletter strip without the editorial photo band.

**Transfer:** Let mode and scale variation demonstrate breadth; keep the warm neutral testing field free of decorative marketing cards.

### Explain a versatile product through an extended illustrated essay

1. **Definition** — 75px inline grotesk name and explanatory statement on white, with product toolbar.
2. **Origin proof** — Narrow introductory prose followed by wide material photography and archival sheets.
3. **Capability chapters** — Sticky text paired with oversize details, alternate-state plates and interactive word comparisons.
4. **Useful artifact** — Centered downloadable specimen and inside-page preview.
5. **Editorial extension** — 300px printed-object photographic band.
6. **Closing action** — White newsletter strip.

**Transfer:** Choose the grotesk statement variant for technical products with many meaningful scales, settings or formats.

### Explain an expressive product through cultural context and fine detail

1. **Definition** — 75px serifless Roman statement with selected italic terms on white.
2. **Sensory promise** — Wide translucent material photograph.
3. **Origin proof** — Archival posters and references in asymmetric media groups.
4. **Capability chapters** — Small chapter headings, prose, letter construction, matched variants and tall proof plates.
5. **Useful artifact** — Centered download explanation and preview in a black closing chapter.
6. **Closing action** — White newsletter strip directly after the preview; no photographic campaign band.

**Transfer:** Choose the expressive statement variant when form and construction are central to the product's appeal.

## Writing

Design-literate, specific and culturally curious. Confident claims are grounded in construction, use and history; occasional wordplay keeps technical explanation personable.

**Do not copy:** Do not reuse Sociotype or Socio names, typeface names as new product names, proprietary wordmarks or artwork, journal titles, client lists, historical attribution passages, production quantities, glyph/style counts or performance claims. Examples illustrate voice only.

- **Addressing the reader:** Product descriptions usually speak about the product in the third person. Organization prose uses we; you appears mainly in practical help and invitations.
- **Rhythm:** Short chapter titles lead into substantial explanatory paragraphs. Several paragraphs run consecutively without card headings; small captions stay factual. Actions are terse and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening feature title | A simple feature marker followed by the product name. | 2–4 words | “Featured: Avec” |
| Chapter heading | A compact, lightly playful phrase that names a real construction idea. | 2–6 words | “Part man, part machine”<br>“Sweeping Curves & Sharp Points”<br>“From miniscule to monumental” |
| Product lead | Define the category, then explain its range or distinguishing construction. | One substantial sentence or two short sentences | “Ceno is a modern humanist sans grounded in the classic proportions of Roman and Renaissance humanist calligraphy and the pioneering early 20th Century rationalism of Edward Johnston’s Underground lettering.” |
| Action | Literal next step, sometimes with a directional glyph. | 1–6 words | “More Info →”<br>“Download a PDF specimen”<br>“Get in touch” |
| Caption | Identify the object or comparison; use a middle dot to separate mode and detail. | 3–10 words | “Humanist construction – varied angle of stress”<br>“Rework Subhead: Regular + Italic” |

**Words and phrasing to use:** construction; character; proportions; contrast; detail; shaped; available; optically adjusted; text and display

**Avoid:** revolutionary; game-changing; unlock your potential; seamless solutions; best-in-class; exclamation-led hype

**Rules:**

- Describe what changes and why it matters at a real use scale.
- Let chapter-title wordplay arise from the characteristic being explained.
- Use concrete materials, processes and formats instead of abstract superiority.
- Keep captions informative enough to justify their small size.
- Use truthful specifications only where the reader can inspect the corresponding proof.

## Do's and Don'ts

### Do

- Keep the cover's support copy compact at 14px/18px while the 40px title and full-width word graphic handle hierarchy.
- Use 12px side gutters and 12px column gaps rather than a centered narrow marketing container.
- Place 12px/16px captions 6px beneath rectangular media.
- Give chapter headings 60px of separation before their 18px/22px explanation.
- Preserve 240px breathing intervals where a new idea needs an editorial pause.
- Use white proof plates with 0px corners and no shadow.
- Keep ordinary actions as 26px text; reserve 107px × 35px pills for acquisition toolbars.
- End on the shared 175px white newsletter strip.

### Don't

- Do not make every heading bold: the working hierarchy uses weight 400 and the statement variants use 300.
- Do not apply negative tracking to the 12px captions; their 0.08em spacing is characteristic.
- Do not stretch 702px proof plates into full-width cards by default; their placement within the 12-column field is part of the composition.
- Do not put shadows, glass blur or rounded shells around editorial media.
- Do not make peach a static hero background; it is an action hover color.
- Do not place color-coded feature icons above every paragraph; this vocabulary relies on text and inspected objects.
- Do not normalize every image to one aspect ratio; portraits, squares and panoramic plates coexist.
- Do not add a dense sitemap footer after the sparse newsletter baseline.

## Motion and responsive

### Motion

**Observed:**

- Color, background and several rule changes declare 0.5s transitions.
- The navigation declares color, opacity, transform and visibility transitions at 0.5s.
- Purchase pills declare background-color transitions at 0.5s and a peach hover fill.
- Product comparisons include animated vector or video material; the cover is a slide presentation.

**Transfer:**

- Keep theme changes coordinated between the field, text and toolbar edge.
- Use moving proof only where it reveals a construction or state difference; retain the same captioned plate framing.

**Unknown:**

- Autoplay timing, carousel advance behavior and exact scroll triggers are not established.
- No specific focus-visible or active-state treatment is established.

### Responsive

**Observed:**

- Declared width breakpoints include 375px, 767px, 768px, 1023px, 1024px, 1439px, 1440px, 1999px and 2000px.

**Transfer:**

- On narrow layouts, carry the editorial rail above its related text, then stack the proof plates while preserving the compact captions.
- Fit the cover word treatment to the available width; preserve the top feature/index relationship and the full-bleed material image rather than shrinking the entire desktop layout.

**Unknown:**

- Mobile compositions and fluid type formulas are not established; the stacking rules are implementation guidance, not measured breakpoint behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
