# Contra Labs — painted digital humanism

## Overview

An editorial, art-led identity where old-world painting meets contemporary tools. Warm ivory, sea-glass green and deep teal support finely drawn serif headlines and straightforward grotesk text. It suits ambitious technical products that want to feel culturally literate and human, with sparse text passages alternating with immersive illustrated scenes and unusually large typographic compositions.

### Essentials

- Fine serif statements behave like exhibition titles: Source Serif 4 at weight 400, 64px/1 with -0.04em tracking for the main promise, and 66px/1 for major chapters.
- The opening is an art stage rather than a software dashboard: a 900px-tall sea-glass field, a left-aligned 600px text zone with 24px gaps, and a full-bleed painted scene carrying the rest of the composition.
- Actions are understated capsules beside grand artwork: 48px height, 24px radius, 24px horizontal padding and 16px/1.5 grotesk labels; charcoal is primary and ivory secondary.
- Color arrives in whole scenes, not rainbow UI accents: long ivory passages dominate, sea-glass holds the capability gallery, and deep teal or olive fills isolated immersive chapters; vivid red and gold belong chiefly inside the paintings.
- Human craft and digital texture must meet: painterly figures, objects or tools are paired with black-and-ivory halftone surfaces. When bespoke painting is unavailable, use a tightly edited art collage with one contemporary object and a masked dot treatment.
- Include a monumental word sculpture and an illustrated ending: short serif words occupy roughly 200px-high rows among small portrait tiles, while the footer finishes with an edge-to-edge painted frieze beneath sparse columns.
- Proof feels like printed matter: overlapping square-edged testimonial sheets, plus a trio of 8px-radius neutral stat cards with 62px serif numbers placed across the foot of a teal illustration.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep teal | `#296a6c` | `--color-teal` | background | Immersive painted proof bands with ivory text. |
| Gallery teal | `#387478` | `--color-art-teal` | background | Backing behind painted capability artwork. |
| Bookmark green | `#83a5a0` | `--color-ribbon` | accent | The hanging navigation bookmark. |
| Muted sage | `#a5beba` | `--color-sage` | surface | Underpainting of capability cards. |
| Sea glass | `#c8e1dd` | `--color-sea-glass` | background, surface | Opening field, capability gallery and front testimonial sheet. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Antique olive | `#918f66` | `--color-olive` | background, surface | Testimonial sheet and isolated participation scene. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#2b2b29` | `--color-ink` | text, action | Default marketing text and filled primary actions. |
| Sheet taupe | `#c8bcae` | `--color-taupe` | surface | Exposed rear sheet in testimonial stack. |
| Sheet gray | `#918989` | `--color-mauve-stone` | surface | Darker rear sheet in testimonial stack. |
| Stat limestone | `#e4e2d9` | `--color-limestone` | surface | Last stat card. |
| Stat stone | `#eeede7` | `--color-stone` | surface | Middle stat card. |
| Veiled ivory | `#faf9f5` | `--color-header` | surface | Visible navigation veil; rgba(250,249,245,0.9) over ivory. |
| Warm ivory | `#fbfaf6` | `--color-canvas` | background, text, surface | Main paper ground, pale cards, secondary actions and reversed text. |
| Luminous ivory | `#fcfbf7` | `--color-footer` | background | Footer ground, subtly lighter than the page. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruitment pages | Blue gray | `#677084` | `--color-slate` | text | Supporting copy in recruitment information and FAQs. |
| recruitment pages | Role khaki | `#ddd9c2` | `--color-khaki` | surface | Alternating recruitment role tiles. |
| editorial reports | Report charcoal | `#333330` | `--color-report-ink` | text, border, action | Report text, chapter rules and report actions. |
| editorial reports | Warm gray | `#605a51` | `--color-report-muted` | text | Report deck, metadata and utility text. |
| editorial reports | Faded warm gray | `#9c968c` | `--color-caption` | text | Report figure captions and minor metadata. |
| editorial reports | Parchment edge | `#e9e5da` | `--color-rule` | border, surface | Report figure outlines and their underlying backing. |
| recruitment pages | Role cream | `#ece6d4` | `--color-cream` | surface | Third recruitment tile tone. |
| recruitment pages | Role sand | `#efe9dc` | `--color-sand` | surface | Default recruitment role tile. |
| recruitment pages | Fine gray rule | `#ebebeb` | `--color-faq-rule` | border | Recruitment information and accordion separators. |

## Typography

- **Source Serif 4 Variable** — Display promises, chapter titles, large numbers and quotations; also report prose. Literary, high-contrast serif with tapered strokes and a finely drawn regular cut. Font stack: "Source Serif 4 Variable", "Source Serif 4", Georgia, serif.
- **GT Standard L** — Marketing support copy, navigation, buttons, labels and report utilities. Unshowy contemporary grotesk; regular text with medium labels. If unavailable, use **Inter**. Use 400 and 500; preserve the generous body size and restrained tracking. Font stack: "GT Standard L", "Inter", Arial, sans-serif.
- **GT Standard** (only for recruitment information) — Recruitment supporting text and answers. Plain regular grotesk with slightly open tracking. If unavailable, use **Inter**. Font stack: "GT Standard", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading-lg | Source Serif 4 Variable | 400 | 66px | 1 | -0.04em | Large chapter headlines on pale or illustrated fields. |
| display | Source Serif 4 Variable | 400 | 64px | 1 | -0.04em | Default landing-page promise and centered major promise. |
| stat | Source Serif 4 Variable | 400 | 62px | 1 | -0.04em | Large proof numbers. |
| heading | Source Serif 4 Variable | 400 | 48px | 1 | normal | Supporting section title beside proof. |
| art-card-title | Source Serif 4 Variable | 400 | 44px | 1 | -0.05em | Lower-left card titles and short interstitial statements. |
| quote | Source Serif 4 Variable | 400 | 33px | 1 | normal | Testimonial sheet text. |
| body | GT Standard L | 400 | 22px | 1.3 | normal | Landing-page support copy and stat explanations. |
| button | GT Standard L | 400 | 16px | 1.5 | 0.01em | Primary and secondary action labels. |
| eyebrow | GT Standard L | 500 | 14px | 1.2 | 0.06em, uppercase | Upper-left capability card labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| recruitment openings | recruitment-display | Source Serif 4 Variable | 400 | 187.2px | 0.94 | -0.035em | Huge asymmetric three-line statement. |
| editorial reports | report-title | Source Serif 4 Variable | 400 | 72px | 0.98 | -0.025em | Article title. |
| recruitment role galleries | role-title | Source Serif 4 Variable | 400 | 48px | 1.02 | -0.03em | Role names at the upper left of tall tiles. |
| recruitment information | information-heading | Source Serif 4 Variable | 400 | 44px | 1.05 | -0.025em | Process, benefits and FAQ headings. |
| editorial reports | report-heading | Source Serif 4 Variable | 400 | 36px | 1.15 | -0.02em | Numbered chapter title. |
| recruitment FAQs | question | Source Serif 4 Variable | 400 | 22px | 1.3 | -0.015em | Accordion questions. |
| editorial reports | report-deck | Source Serif 4 Variable | 400 | 22px | 1.4 | -0.01em | Long descriptive subtitle. |
| editorial reports | report-body | Source Serif 4 Variable | 400 | 17px | 1.65 | -0.005em | Sustained reading paragraphs. |
| recruitment FAQs | answer | GT Standard | 400 | 16px | 1.6 | 0.01em | Expanded answer text. |
| editorial reports | caption | GT Standard L | 400 | 13px | 1.5 | normal | Figure explanations beneath wide media. |
| editorial reports | report-eyebrow | GT Standard L | 500 | 12px | 1 | 0.12em, uppercase | Publication, date and issue identifiers. |

**Notes:**

- Keep serif headings regular rather than bold; the contrast comes from scale and tightly packed lines.
- The 64px and 66px recipes serve different roles, not interchangeable size options: use 64px for the main promise and 66px for large chapter statements.
- Word sculptures use outlined serif lettering in roughly 200px-high rows. Rebuild with live serif text sized to fit each short word, rather than stretching a normal paragraph.
- Marketing copy uses a generous sans serif; sustained report prose switches to a smaller serif. Do not average them into one body style.

## Layout

**Density:** Airy, with long editorial pauses between dense painted stages and compact utility clusters.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Tightly joined capability grid and word-sculpture rows. |
| 8px | Small tag rows and icon group spacing. |
| 12px | Action pair gap and stat number-to-label separation. |
| 18px | Recruitment tile grid gaps. |
| 24px | Default headline, support and action-group separation. |
| 30px | Default marketing stat-card padding. |
| 32px | Footer content grouping. |
| 40px | Capability card horizontal padding. |
| 48px | Capability card vertical padding and report figure margins. |
| 56px | Report internal side padding. |
| 120px | Major marketing section padding and desktop side inset. |
| 200px | Top and bottom breathing room around the monumental word composition. |

### Containers and grids

- **Marketing frame**: max width 1200px · side padding 120px. Broad centered editorial composition at 1440px; full-bleed artwork can escape it.
- **Promise column**: max width 600px · gap 24px. Opening title and actions; support text itself is about 430px wide.
- **Capability grid**: 2 columns · gap 5px. Two almost-touching painted cards per row, each 578px by 520px at desktop.
- **Proof trio**: max width 1600px · 3 columns · gap 10px · side padding 20px. Three equal neutral cards stretched across the bottom of an illustrated band.
- **Role gallery** (only for recruitment pages): 4 columns · gap 18px · side padding 60px. Staggered four-column gallery of 317px by 396px roles and art, with intentionally open grid positions.
- **Information frame** (only for recruitment information): max width 1100px · 2 columns · gap 64px · side padding 60px. Small left title column beside a roughly twice-as-wide answer column.
- **Report frame** (only for editorial reports): max width 1200px · side padding 56px. Title, contents and closing utilities in a broad centered frame.
- **Reading column** (only for editorial reports): max width 820px · side padding 56px. 708px reading measure inside the padded article; figures break outward to 928px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Action capsules | 24px |
|  | Marketing cards | 8px |
| recruitment pages | Role tiles | 18px |
| recruitment role galleries | Circular arrow | 50% |
| editorial reports | Figure utilities | 4px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default background.

**CSS:** `background: #fbfaf6; color: #2b2b29`

**Observed:** A faint fibrous, mottled paper texture unifies both pale and colored areas.

**Transfer:** Use subtle monochrome grain rather than a visibly repeating paper photograph.

#### Sea-glass stage · level 0

**Use:** Opening and capability gallery.

**CSS:** `background: #c8e1dd`

**Observed:** A broad uninterrupted field carries large art and narrowly set text.

**Transfer:** Keep it a scene backing, not a collection of individually tinted UI controls.

#### Teal illustrated band · level 0

**Use:** Immersive promise or quantified proof.

**CSS:** `background: #296a6c; color: #fbfaf6; overflow: hidden`

**Observed:** Painted subjects fill the right and lower areas while the upper-left remains legible.

**Transfer:** Prepare artwork with text-safe negative space.

#### Olive participation stage · level 0

**Use:** Closing participation invitation.

**CSS:** `background: #918f66; color: #fbfaf6`

**Observed:** Centered serif invitation above a small pale comparison panel, followed by support and a dark action.

**Transfer:** Use a compact interactive sample or two contrasting outcomes to make the invitation tangible.

#### Header veil · level 2

**Use:** Fixed navigation backing.

**CSS:** `background: rgba(250, 249, 245, 0.9); backdrop-filter: blur(5px)`

**Observed:** The illustration softly shows through a narrow pale strip.

**Transfer:** Keep blur confined to navigation; the page is not a glass-card interface.

#### Footer paper · level 0

**Use:** Ending information and illustration.

**CSS:** `background: #fcfbf7; padding-top: 80px; overflow: hidden`

**Observed:** Light columns float above an edge-to-edge illustrated frieze.

**Transfer:** Keep a broad area of paper between text and the bottom art.

#### Report figure backing · level 0

**Only for:** editorial reports

**Use:** Wide charts, annotated examples and video frames.

**CSS:** `background: #e9e5da; border: 1px solid #e9e5da`

**Observed:** Square media frames; the chart or annotation artwork often has its own near-white ground.

**Transfer:** Preserve legibility and fine edges instead of applying marketing-card rounding.

## Components

### Fixed navigation

**Use:** Persistent site orientation and two conversion paths.

**CSS:** `position: fixed; top: 0px; height: 72px; width: 100%; z-index: 8; padding-left: 120px; padding-right: 80px; display: flex; align-items: center; background: rgba(250, 249, 245, 0.9); backdrop-filter: blur(5px)`

**Observed:** A narrow hanging green bookmark sits left of the wordmark; a small group of plain links follows it, while a pale and dark action pair align at the far right. Links use 17px grotesk text with 20px line height and -0.01em tracking.

**Transfer:** Use the new identity's mark in a simple bookmark silhouette, keeping the protrusion below the header.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 12px 24px 13px; border-radius: 24px; background: #2b2b29; color: #fbfaf6; overflow: hidden`

**Text style:** `button` — GT Standard L 400 · 16px/1.5 · tracking 0.01em

**Observed:** Text-only capsule paired with a pale secondary action. Recruitment uses a separate thin outlined Apply capsule; report conversion actions are roomier.

**Transfer:** Keep labels short and consultative rather than salesy.

### Secondary button

**Use:** Exploration alongside the main action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 12px 24px 13px; border-radius: 24px; background: #fbfaf6; color: #2b2b29`

**Text style:** `button` — GT Standard L 400 · 16px/1.5 · tracking 0.01em

**Observed:** Pale fill contrasts with colored stages; on paper the header and footer version reads as a faintly outlined capsule.

### Painted capability card

**Use:** Introduce a capability through a visual metaphor.

**CSS:** `position: relative; display: flex; flex-direction: column; justify-content: space-between; padding: 48px 40px; border-radius: 8px; background: #a5beba; color: #fbfaf6; overflow: hidden`

**Text style:** `art-card-title` — Source Serif 4 Variable 400 · 44px/1 · tracking -0.05em

**Observed:** Full-card art over a teal backing, a small uppercase label at the upper left and a two-line serif title at the lower left; labels and titles sit in front of all art.

**Transfer:** Choose one concrete metaphor per capability and reserve clear corners for text.

### Stat card

**Use:** Quantified proof at the foot of an illustrated scene.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 30px; border-radius: 8px; background: #fbfaf6; color: #2b2b29`

**Text style:** `stat` — Source Serif 4 Variable 400 · 62px/1 · tracking -0.04em

**Observed:** Large serif number above a 22px sans explanation. The three cards progress from ivory to stone to limestone, without shadows; the recruitment version increases padding to 40px.

### Testimonial sheet

**Use:** Human proof beside a compact section introduction.

**CSS:** `position: relative; background: #c8e1dd; color: #2b2b29; border-radius: 0px; box-shadow: none`

**Text style:** `quote` — Source Serif 4 Variable 400 · 33px/1

**Observed:** A portrait-format front sheet in a stack of roughly 542px-wide, offset gray, taupe, olive and charcoal sheets. Large quotation marks bracket a narrow serif paragraph; a small sans attribution sits beneath it.

**Transfer:** Use actual customer language; build depth with offset flat sheets, not cast shadows.

### Illustrated footer

**Use:** Persistent closing identity and secondary navigation.

**CSS:** `background: #fcfbf7; padding-top: 80px; overflow: hidden`

**Observed:** Three loose desktop columns: identity and two-line description, a short vertical navigation list, then stacked pale/dark capsules and four social icons. Below, a full-width painted crowd rises from the bottom edge, with no enclosing card.

**Transfer:** End with a custom frieze of people, tools or artifacts connected to the new product; keep the silhouette varied and the upper background transparent.

### Role tile

**Only for:** recruitment role galleries

**Use:** Browse a role and reach its application.

**CSS:** `display: flex; flex-direction: column; position: relative; padding: 28px; border-radius: 18px; background: #efe9dc; overflow: hidden; box-shadow: none`

**Text style:** `role-title` — Source Serif 4 Variable 400 · 48px/1.02 · tracking -0.03em

**Observed:** Tall 317px by 396px tile with the role at top left and a 40px outlined circular arrow at bottom right. Alternate sand, khaki and cream tiles with painted portraits.

**Transfer:** Maintain the sparse staggered gallery rather than filling every grid position.

### FAQ row

**Only for:** recruitment information

**Use:** Practical objection handling.

**CSS:** `border-bottom: 1px solid #ebebeb; padding: 24px 0px; display: flex; justify-content: space-between; gap: 24px`

**Text style:** `question` — Source Serif 4 Variable 400 · 22px/1.3 · tracking -0.015em

**Observed:** A small blue-gray plus sits opposite a serif question. Answers are blue-gray sans text below; the first row has an additional top rule.

### Wide report figure

**Only for:** editorial reports

**Use:** Support prose with inspectable visual proof.

**CSS:** `margin: 48px -110px; max-width: 928px`

**Text style:** `caption` — GT Standard L 400 · 13px/1.5

**Observed:** Square-edged image or video breaks out of the reading column; an 820px-wide caption is centered below with 14px top separation. A tiny utility strip offers download and social sharing beneath it.

**Transfer:** Use real charts or annotated product outputs. Keep chart colors local to the figure, not global marketing accents.

## Imagery and graphics

### Painted digital tableaux

**Use:** Signature art throughout openings, capability cards, full-bleed promises and the footer.

**Observed:** Renaissance-like figures in cream drapery, red and teal garments, golden objects and antique furnishings interact with laptops and phones. Warm skin and soft directional light retain a painted, slightly grainy texture. Teal skies and curtains contrast with black-and-ivory patterned devices; figures are tightly cropped or isolated on paper.

**Transfer:** Commission or collage culturally resonant craft imagery around the new product's real tool or outcome. Minimum version: one well-masked painted object or figure, teal backing, and one patterned contemporary artifact rather than a generic stock office photo.

**Build:** Layer a teal rectangle behind a high-resolution painted cutout; add a contemporary tool silhouette in charcoal. Clip a repeating SVG pattern of tiny ivory dots or crosses to the tool, using a 3px to 5px repeat. Add a subtle monochrome SVG turbulence layer over the composition at low opacity; preserve the warm skin and gold highlights. Keep background detail away from the title.

### Dot veil and paper grain

**Use:** Unifying digital-print material on capability art and pale backgrounds.

**Observed:** Faint clusters of small square dots float over the teal images, while fine irregular grain coats the whole surface. Patterned devices have a much stronger black-and-white density than the background veil.

**Transfer:** Use pattern as a deliberate meeting of tactile and digital materials, not as an all-over tech grid.

**Build:** Create an SVG pattern with 2px squares on a 6px grid, in ivory at roughly 0.12 opacity, and mask it through broad irregular shapes over the art. For paper, overlay monochrome fractal turbulence at roughly 0.03 opacity. Keep both layers pointer-events:none; do not blur the text.

### Word sculpture

**Use:** Monumental editorial interruption on marketing pages.

**Observed:** Huge outlined serif words form a staggered multi-line composition with small painted portrait tiles in the surrounding gaps and a compact sea-glass support card. Word rows are about 200px high and sit only 5px apart; the composition has 200px top and bottom padding.

**Transfer:** Use a short original benefit phrase split into individual words; make the words the artwork and let their varying widths create asymmetry.

**Build:** Lay out short live serif words in an eight-column CSS grid with 5px gaps and 20px side padding. Fit each word to its allocated span; at 1440px, the widest word spans roughly 777px and a 200px-high row. Use portrait art in approximately 170px-wide tiles with 8px corners. Place one small sea-glass copy-and-action tile in a lower corner.

### Floating portrait constellation

**Use:** Sparse narrative interludes and human-centered promise sections.

**Observed:** Small rectangular painted portraits float at different heights around a centered serif sentence on ivory; some images cross the viewport edges. A later composition enlarges the collective portrait beside a stacked word statement.

**Transfer:** Use a small consistent set of meaningful subjects rather than unrelated decorative thumbnails.

**Build:** Place five to seven portrait cutouts on an ivory field, mixing widths around 70px, 120px and 180px. Keep the center text zone clear and let two outer images extend beyond the section boundary. Use no visible frames or drop shadows.

### Illustrated frieze

**Use:** Signature bottom edge of the footer.

**Observed:** A dense horizontal gathering of painted figures holding patterned laptops rises from the bottom of the page; warm red, cream and gold clothing creates a scalloped upper silhouette against ivory.

**Transfer:** Use a new gathering of product-related people or objects. A minimum version is a row of individually masked painterly artifacts with alternating heights, connected by a shared palette.

**Build:** Compose six to twelve overlapping transparent cutouts in a bottom-aligned flex row. Vary widths and heights, overlap neighbors slightly and extend the outermost subjects beyond the viewport. Keep the highest silhouettes below the footer links so paper still separates content from art.

### Annotated report plates

**Only for:** editorial reports

**Use:** Explain findings and compare real outcomes.

**Observed:** Wide pale plates contain charts, product photographs or interface outputs. Thin curved arrows connect white annotation notes to specific details; panels are square-edged and captioned outside. Color comes from the content and local chart series.

**Transfer:** Use actual outputs and clear comments with restrained arrows; do not borrow the example product interfaces as the site's own visual system.

### Icons

**Observed:** Small monochrome social marks and simple arrows; report utility icons are 13px to 14px, with round-capped 1.5px or 2px strokes. Marketing social marks are 24px within 48px targets. Role arrows sit in 40px outlined circles.

**Transfer:** Choose simple monochrome glyphs at their native small size. Reserve decorative emblems for the bookmark; do not add colorful feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Painted promise opening

**Observed:** A full-width sea-glass scene occupies the first 900px. The fixed navigation floats above it. A left text column begins well below the header with a 64px serif promise spanning about 600px, a 430px-wide sans support line and a dark/pale action pair; vertical grouping uses 24px gaps and the action pair uses 12px. A full-bleed painted media layer sits behind the text and carries the central and right-hand visual weight. The headline, support, actions and main art all belong within the first screen; the capability introduction begins below it.

**Transfer:** For a different product, stage one painted human/tool encounter with a clear left text-safe area; if no custom scene exists, combine one art cutout with a patterned product object on sea glass. Recruitment openings instead use the asymmetric giant serif statement on ivory with a single outlined action; reports open with a publication label, title, deck and byline before the wide art.

**Avoid:** Do not turn the opening into a centered SaaS headline above a floating dashboard, or make a loading emblem the permanent hero.

**Text style:** `display` — Source Serif 4 Variable 400 · 64px/1 · tracking -0.04em

### Capability gallery

**Observed:** Sea-glass stage continues behind a large serif section introduction and a two-column grid of Painted capability cards. Cards are nearly joined by 5px gutters; the upper label and lower title stay aligned across the grid.

**Transfer:** Use a small set of distinct capabilities with tangible visual metaphors; adapt the number to the content.

**Text style:** `heading-lg` — Source Serif 4 Variable 400 · 66px/1 · tracking -0.04em

### Editorial pause

**Observed:** A short centered serif sentence sits in a mostly empty ivory field, then a Floating portrait constellation adds human presence without turning the passage into a dense grid.

**Transfer:** Use one meaningful shift in the story, such as what makes the product's work different, rather than repeating its feature list.

**Text style:** `art-card-title` — Source Serif 4 Variable 400 · 44px/1 · tracking -0.05em

### Stacked proof sheets

**Observed:** An ivory section pairs a narrow left introduction with Testimonial sheets stacked toward and beyond the right edge. The front quotation reads like a printed page rather than a compact review card.

**Transfer:** Use the offset stack to communicate multiple perspectives while showing only one quotation fully.

**Text style:** `quote` — Source Serif 4 Variable 400 · 33px/1

### Illustrated proof band

**Observed:** A Teal illustrated band combines a left 504px text column, small outlined category tags and a large cropped hand/tool painting. A Proof trio stretches across the lower edge with 20px outer insets.

**Transfer:** Pair a human-centered claim with three defensible numbers and plain-language labels.

**Text style:** `heading-lg` — Source Serif 4 Variable 400 · 66px/1 · tracking -0.04em

### Monumental benefit composition

**Observed:** The Word sculpture fills an ivory field with staggered word rows, portrait tiles and a small copy/action tile; it is much larger than a normal heading.

**Transfer:** Give the new product one memorable original sentence that can work as a typographic object.

### Full-bleed thesis

**Observed:** A full-width painted tabletop scene frames a centered two-part serif statement in ivory, support text beneath it and a Primary button. Large hands and patterned devices flank the message.

**Transfer:** Compose symmetrical visual pressure around an uncluttered text-safe center.

**Text style:** `heading-lg` — Source Serif 4 Variable 400 · 66px/1 · tracking -0.04em

### Participation close

**Observed:** Olive participation stage holds a centered two-line serif invitation, a pale side-by-side comparison panel, a short support sentence and a dark capsule. The Illustrated footer follows as a separate light ending.

**Transfer:** Make the visitor's next step concrete with a small sample of the experience, not just another generic conversion banner.

### Recruitment gallery and practical details

**Only for:** recruitment pages

**Observed:** A monumental asymmetric title leads to staggered Role tiles and art. A centered serif appeal, pale horizontal testimonial strip, two-column process/benefits rows and FAQ rows bring the narrative back to practical detail before the illustrated proof band and footer.

**Transfer:** Balance expressive invitation with concrete eligibility, process, ownership and compensation information.

**Text style:** `recruitment-display` — Source Serif 4 Variable 400 · 187.2px/0.94 · tracking -0.035em

### Report chapter and figure

**Only for:** editorial reports

**Observed:** A small numbered chapter marker sits beside a 36px serif title; later chapters begin with a dark top rule and 32px top padding. Serif paragraphs use a 708px measure, 20px paragraph separation and Wide report figures breaking out to 928px. Italic pull quotes use a 2px left rule and 28px inset.

**Transfer:** Structure long explanations into numbered arguments and show inspectable proof at the point it matters.

**Text style:** `report-heading` — Source Serif 4 Variable 400 · 36px/1.15 · tracking -0.02em

### Report ending

**Only for:** editorial reports

**Observed:** The final prose chapter leads to a prominent partnership action, a separate outlined appendix action, then a widely spaced top-ruled row for return-to-top and all-articles navigation. The same Illustrated footer completes the page.

**Transfer:** Separate conversion, supporting documentation and onward reading rather than compressing them into one link cluster.

## Page flow

**Storyline:** Promise → expressive capability framing → human and quantified proof → deeper thesis or explanation → tangible invitation → illustrated identity ending.

### Art-led product or organization landing page

1. **Promise** — Painted stage with a short promise, support and two actions.
2. **Capabilities** — Painted capability gallery with exhibition-like labels.
3. **Differentiation** — Sparse editorial interludes and portraits explain the human basis of the work.
4. **Social and quantified proof** — Stacked testimonial sheets followed by an illustrated stat band.
5. **Memorable thesis** — Monumental word sculpture and full-bleed painted statement.
6. **Participation and closing** — Small comparison experience on olive, then a light footer with a painted frieze.

**Transfer:** Use the narrative devices to vary tempo; place proof and explanation where the new product needs them rather than repeating every chapter.

### Recruitment or expert-network invitation

1. **Invitation** — Enormous asymmetric serif statement and small outlined action.
2. **Opportunity discovery** — Staggered role tiles mixed with painted imagery.
3. **Trust** — Centered appeal and horizontally arranged member quotations.
4. **Objection handling** — Plain two-column process and benefit explanations followed by FAQs.
5. **Scale and ending** — Shared illustrated proof band and light illustrated footer.

**Transfer:** Keep the expressive title but provide actual role requirements and process details before the final action.

### Long-form research or technical editorial

1. **Context and thesis** — Back link, publication metadata, serif title, deck, byline and wide cover art.
2. **Reading orientation** — Contents links and a compact citation area.
3. **Explanation and proof** — Numbered chapters alternate narrow serif prose with wider charts, annotated examples and video.
4. **Qualification** — Limitations, implications and future directions maintain the same reading format.
5. **Closing action and onward reading** — Conversion action, appendix, top and index links, then the shared illustrated footer.

**Transfer:** Use the report variant when the argument needs sustained reading; keep figures wider than prose and preserve the common ending.

## Writing

Confident and culturally informed, but concrete about what the work does. Marketing makes crisp contrasts; research allows nuance and openly distinguishes certainty from interpretation.

**Do not copy:** Do not reuse Contra's names, logos, artwork, customer quotations, network sizes, earnings, research findings or superiority claims. Replace them with the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly declarative product descriptions, with direct imperatives in actions. Recruitment speaks plainly to the reader using you and your; research uses an explanatory, less personal register.
- **Rhythm:** Headlines are often two to eight words or two short contrasted sentences. Support is one compact sentence or a short paragraph; actions are two or three words. Long-form prose defines distinctions carefully.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name the governing idea in a compact noun phrase. | 2–5 words | “Creative intelligence.” |
| Supporting line | State the category and the practical improvement in one sentence. | 12–25 words | “A frontier human data and evaluation lab making AI better for creativity.” |
| Thesis | Contrast what has become easy with what remains valuable. | Two short sentences | “Execution is free. Now, judgment is everything.” |
| Primary action | Consultative verb plus concrete next step. | 2–3 words | “Request partnership”<br>“Explore research” |
| Practical explanation | Use short active clauses and specific benefits. | One compact paragraph | “Apply, get reviewed by a current Labs team member, and ship.” |
| Editorial framing | Name a distinction before explaining why it changes evaluation. | One descriptive sentence | “This distinction matters because creative work has no ground truth.” |

**Words and phrasing to use:** judgment; expertise; real-world; workflows; craft; signal; quality; understand; shape; build

**Avoid:** 10x everything; magic; revolutionary; crush it; hustle; endless exclamation marks

**Rules:**

- Make abstract ideas tangible with a person, a tool or a real workflow.
- Use contrast to clarify a position, not to disparage the reader.
- Pair important claims with a defensible fact or a specific explanation.
- Let research acknowledge limits; let conversion labels stay plain.

## Do's and Don'ts

### Do

- Keep default display type at 64px/1, weight 400 and -0.04em tracking.
- Use 24px gaps to connect heading, support and actions into one unit.
- Make primary capsules 48px high with 24px corners and 16px labels.
- Use 5px gutters for the tightly joined painted capability grid.
- Stage three proof cards with 10px gaps and 20px outer insets.
- Preserve the 62px serif number over a plain sans explanation.
- Create depth with offset flat testimonial sheets rather than shadow.
- Include both a word sculpture and a full-width illustrated footer ending.

### Don't

- Do not replace regular serif headlines with bold geometric sans.
- Do not use electric purple or blue gradients as the main atmosphere; the broad fields are ivory, sea glass, teal and olive.
- Do not round report plates to the 18px role-tile radius.
- Do not add elevation shadows to flat marketing cards.
- Do not distribute saturated color across every UI element; keep strong red and gold primarily in art.
- Do not set ordinary support paragraphs in the 17px report serif recipe.
- Do not make the footer a dark legal bar; it is light paper with a substantial art frieze.
- Do not fill the recruitment gallery's open positions with generic feature cards.

## Motion and responsive

### Motion

**Observed:**

- The experience includes video-backed art scenes and scroll-linked changes in image placement and scale.
- A horizontal testimonial marquee is declared for recruitment.
- No action or surface transition durations are established.

**Transfer:**

- Let the painted scene be the moving layer while labels and actions remain readable.
- Use the portrait constellation and expanding painted scenes as the main motion language instead of adding bouncing interface ornaments.

**Unknown:**

- Precise scroll interpolation, marquee speed, action timing and easing are unspecified.

### Responsive

**Observed:**

- Width breakpoints cluster around 810px, 1200px, 1440px and 1600px.

**Transfer:**

- On narrow layouts, keep the opening's text-safe zone and move the main art below or behind the support rather than shrinking the whole desktop scene.
- Reduce the capability gallery and proof trio to stacked units while preserving their distinct image, label and number hierarchy.
- Scale the word sculpture to fit its words and reduce portrait count without losing the monumental phrase.
- Constrain wide report figures to the viewport and keep captions attached to their media.

**Unknown:**

- Exact narrow-screen typography, navigation behavior and column changes are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
