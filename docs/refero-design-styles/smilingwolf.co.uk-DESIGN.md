# Smiling Wolf — culture in the margins

## Overview

An assured, people-centred editorial style with near-black green, warm ivory and small, carefully contained moments of colour. Tightly set contemporary grotesk headlines sit beside tiny monospaced labels, while photography brings texture, activity and human warmth. It suits creative products, cultural services and design-led businesses with substantial visual proof; the overall pacing is spacious even when individual cards and lists are dense.

### Essentials

- Headlines sound like a belief, not a billboard slogan: left-aligned Bagoss Standard at 78.7px, weight 520, line-height 0.9 and -0.02em tracking, with a 26.2px supporting statement below.
- The opening leaves a whole side of the room unoccupied: a 260px top inset, 20px side margins, a two-line headline and support concentrated in the left half, followed by a photographic strip beginning at 638px.
- Tiny labels frame expansive statements: uppercase mono at 10.4px/1.6 with 0.1em tracking, enclosed by a 1px outline and 4px corners. Carry this device into every new page.
- Actions stretch rather than bulge: 42px-high, full-width text-and-arrow rows with a 1px baseline; no pill-shaped conversion buttons. Small carousel controls are 40px squares with 4px corners.
- The default is an uninterrupted near-black green canvas with ivory type; saturated colour lives inside photography and artwork, not throughout the interface. The light portfolio variant reverses ink and ivory, with peach reserved for an editorial closing band.
- Visual proof occupies entire bands: 14px media gutters, 4px corners, near-edge-to-edge images and occasional paired portraits. Include a human or material photographic sequence on every new page; if there is no finished product imagery, photograph its making, tools or use.
- Proof gets typeset, not logo-badged: use 59px names in columns or a compact mono ledger, and finish with a ruled arrow action. A new page needs both a typographic proof device and this restrained closing gesture, not a prescribed section order.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Green black | `#131713` | `--color-ink` | background, text | Default dark canvas and primary text in the light portfolio variant. |
| Raised green black | `#1e221f` | `--color-panel` | surface | Subtly lighter capability cards and broad quote panels on the dark canvas. |
| Middle neutral | `#858582` | `--color-muted` | text | Secondary prose: ivory at 50% over green black, or green black at 50% over ivory. |
| Warm ivory | `#f7f3f0` | `--color-paper` | text, background, border | Primary type and outlines on dark; page canvas for the light portfolio variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light portfolio editorial endings | Editorial peach | `#fed5c4` | `--color-peach` | background | Visible wash from rgb(255,210,191) at 0.9011 over ivory; confined to the editorial band. |
| scroll-linked story lists and dark-theme dividers | Receding dark neutral | `#4c4e4a` | `--color-receded` | text, border | Inactive timeline text and dark-theme rules, made with ivory at 25% over green black. |
| light portfolio capability lists | Receding light neutral | `#bebcb9` | `--color-soft-ink` | text | Inactive capability names, green black at 25% over ivory. |
| light portfolio sections | Light-theme hairline | `#d5d2cf` | `--color-rule` | border | Green black at 15% over ivory for long action baselines. |
| light portfolio cards | Ivory-grey chip | `#ece8e5` | `--color-chip` | surface | Category chip fill, green black at 5% over ivory. |

## Typography

- **Bagoss Standard** — All statements, headings, body copy and primary action labels. Contemporary grotesk with compact, softly characterful forms; medium headlines feel firm without becoming heavy. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **Inter**. Use variable weights 385 and 520; preserve tight display tracking. Font stack: "Bagoss Standard", "Inter", Arial, sans-serif.
- **General Grotesque Mono** — Navigation, outlined labels, category chips, dates and proof ledgers. Small, widely tracked uppercase monospace, functioning like editorial metadata. If unavailable, use **IBM Plex Mono**. Use weight 400 and 0.1em tracking. Font stack: "General Grotesque Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Bagoss Standard | 520 | 78.7px | 0.9 | -0.02em | Default opening belief statement, usually two lines. |
| display-list | Bagoss Standard | 520 | 59px | 1 | -0.02em | Typographic proof names and substantial capability lists; also the oversized statement in the light portfolio variant. |
| heading | Bagoss Standard | 520 | 39.4px | 1.1 | -0.01em | Split statements, capability card headings and proof-section introductions. |
| lead | Bagoss Standard | 520 | 26.2px | 1.2 | -0.01em | Opening support and chronological story titles. |
| action | Bagoss Standard | 520 | 19.7px | 1.15 | -0.01em | Full-width action rows and portfolio titles. |
| body | Bagoss Standard | 385 | 17px | 1.4 | normal | Reading prose in split statements and explanatory chapters. |
| caption | Bagoss Standard | 385 | 14.1px | 1.4 | 0.01em | Capability support, portrait roles and small image captions. |
| caption-title | Bagoss Standard | 520 | 14.1px | 1.4 | 0.01em | Portrait names and editorial-card titles. |
| eyebrow | General Grotesque Mono | 400 | 10.4px | 1.6 | 0.1em, uppercase | Outlined section labels, navigation, dates and proof-table text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| light portfolio sections | portfolio-support | Bagoss Standard | 385 | 19.7px | 1.15 | normal | One-line project descriptions under titles and capability introductory copy. |
| case studies | chapter-title | Bagoss Standard | 520 | 17px | 1.4 | normal | Small sentence-case headings attached directly to explanatory paragraphs. |
| light portfolio cards | category | General Grotesque Mono | 400 | 9px | 1.6 | 0.1em, uppercase | Small filled category chips beneath visual work. |

**Notes:**

- Keep the medium and regular cuts distinct: statements use 520, reading copy 385 and metadata 400.
- Display lines compress to 0.9–1; paragraphs open to 1.4. Tracking tightens to -0.02em at the two largest sizes; small captions loosen to 0.01em.
- Use sentence case for expressive language and uppercase only for metadata. Do not turn all headings into uppercase.

## Layout

**Density:** Airy at section scale, compact inside cards: large unoccupied fields contrast with tightly grouped labels and text.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Chip wrapping and internal action-row gaps. |
| 12px | Capability heading-to-description gap and media-to-details spacing. |
| 14px | Media gutters, list gaps and card side padding. |
| 20px | Page side padding and section label-to-grid spacing. |
| 36px | Opening headline-to-support gap. |
| 40px | Split heading-to-body gap and case-study text bottom padding. |
| 80px | Gap before proof tables and between capability introduction and list. |
| 100px | Common dark section top padding and case-study closing-action inset. |
| 120px | Common dark section bottom padding. |
| 140px | Case-study chapter top padding. |
| 200px | Opening-to-explanation breathing room on dark split sections. |
| 260px | Default opening top inset. |

### Containers and grids

- **edge-to-edge container**: side padding 20px. Fluid page width with 1400px usable width at a 1440px viewport; no fixed maximum-width cap.
- **editorial grid**: 4 columns · gap 20px. Shared alignment skeleton. Split statements use the right two columns; opening support uses the left two.
- **card grid**: 4 columns · gap 14px. Capability cards and portrait cards, each about 340px wide on desktop.
- **paired media** (only for portfolio and case-study sections): 2 columns · gap 14px · side padding 20px. Two 693px-wide images at desktop, alternating with 1400px-wide landscape media.
- **reading column** (only for case studies): max width 560px · side padding 20px. Short explanatory chapters stay at the left rather than occupying the full page.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media and labels | 4px |
| testimonial carousels | carousel controls | 4px |

## Surfaces and depth

### Surfaces

#### Dark canvas · level 0

**Use:** Default marketing-page field.

**CSS:** `background: #131713; color: #f7f3f0`

**Observed:** A flat green-black field continues across opening, statements, image groups and proof.

**Transfer:** Let content and photographs create contrast rather than changing background every section.

#### Quiet panel · level 1

**Use:** Capability cards and quote panels.

**CSS:** `background: #1e221f; border-radius: 4px; box-shadow: none`

**Observed:** Only a slight tonal lift separates panels from the page; no shiny edge or elevation.

**Transfer:** Use for genuinely grouped content, not every paragraph.

#### Paper canvas · level 0

**Only for:** portfolio and case-study pages

**Use:** Light portfolio and case-study variant.

**CSS:** `background: #f7f3f0; color: #131713`

#### Editorial wash · level 0

**Only for:** light portfolio editorial endings

**Use:** A warm closing editorial collection.

**CSS:** `background: rgba(255, 210, 191, 0.9011); color: #131713`

**Observed:** The wash runs behind the whole asymmetric image grid and its closing action, rather than individual cards.

**Transfer:** Use a single editorial colour field within the light variant.

#### Hero navigation shade

**Only for:** case-study media openings

**Use:** Maintain small navigation legibility over media.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0.25) 0%, rgba(0, 0, 0, 0) 100%); height: 100px`

## Components

### Navigation

**Use:** Small identity, descriptor and page links at the top.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(50px, 1fr)); gap: 20px; padding: 14px 20px 16px; color: #f7f3f0`

**Text style:** `eyebrow` — General Grotesque Mono 400 · 10.4px/1.6 · tracking 0.1em · uppercase

**Observed:** Identity begins at the left; the descriptor begins one column in; a compact link group aligns to the far right. It reads as a line of metadata, not a separate toolbar. Reverse the text colour on paper.

### Outlined label

**Use:** Identify sections and enumerate capabilities.

**CSS:** `display: inline-flex; padding: 6px 10px 7px; border: 1px solid #f7f3f0; border-radius: 4px; color: #f7f3f0`

**Text style:** `eyebrow` — General Grotesque Mono 400 · 10.4px/1.6 · tracking 0.1em · uppercase

**Observed:** Labels closely hug their words. The same construction becomes a wrapping group at the bottom of capability cards. On paper the outline is green black at 50%.

### Ruled action

**Use:** Primary section action and final continuation.

**CSS:** `display: flex; flex-direction: column; height: 42px; gap: 6px; color: #f7f3f0; border-bottom: 1px solid rgba(247, 243, 240, 0.25)`

**Text style:** `action` — Bagoss Standard 520 · 19.7px/1.15 · tracking -0.01em

**Observed:** An inner row puts the label at the far left and a 23px right arrow at the opposite edge. A baseline spans the entire content width. The paper variant uses dark text and a 15% dark baseline; case-study endings pair 'Next' with a muted destination.

**Transfer:** Use the same full-width gesture for a next step, full collection or contact destination instead of introducing a filled CTA.

### Capability card

**Use:** Group distinct offerings or product strengths.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 10px 14px 14px; height: 400px; background: #1e221f; border-radius: 4px`

**Text style:** `heading` — Bagoss Standard 520 · 39.4px/1.1 · tracking -0.01em

**Observed:** A heading and short caption sit at the top, with 12px between them; outlined capability labels wrap along the bottom with 6px gaps. The generous empty middle makes the card feel like an editorial index.

**Transfer:** Replace disciplines with a few meaningful product capabilities; keep short explanatory sentences and bottom-aligned metadata.

### Proof ledger

**Use:** Present credentials as an editorial record.

**CSS:** `display: flex; flex-direction: column; color: #f7f3f0`

**Text style:** `eyebrow` — General Grotesque Mono 400 · 10.4px/1.6 · tracking 0.1em · uppercase

**Observed:** Full-width rows are about 58px high, with faint horizontal separators. Four aligned text fields carry name, distinction, project and right-aligned year; secondary fields are muted. This is marketing proof, not an embedded application interface.

**Transfer:** Replace awards with substantiated milestones, outcomes or deployments, preserving the ledger rather than inventing a dashboard.

### Portrait card

**Only for:** team or contributor sections

**Use:** Introduce real people with editorial restraint.

**CSS:** `position: relative; display: flex; flex-direction: column; overflow: hidden; border-radius: 4px; height: 453px`

**Text style:** `caption-title` — Bagoss Standard 520 · 14.1px/1.4 · tracking 0.01em

**Observed:** A full-bleed portrait underlies a 14px inset text layer. Name and role sit at the top, a mono biography link at the bottom. Four cards form a row.

**Transfer:** Use consistent environmental portraits with the same framing and lighting.

### Portfolio card

**Only for:** light portfolio sections

**Use:** Visual proof linked to a deeper story.

**CSS:** `display: flex; flex-direction: column; gap: 12px; overflow: hidden`

**Text style:** `action` — Bagoss Standard 520 · 19.7px/1.15 · tracking -0.01em

**Observed:** Media is first, then a row of tiny filled categories, then a medium title and muted regular tagline. Square and landscape cards share columns; some images span both columns. There is no enclosing card background.

**Transfer:** Use customer outcomes, product deployments or campaigns as stories.

### Category chip

**Only for:** light portfolio cards

**Use:** Compact classification beneath media.

**CSS:** `display: inline-flex; padding: 4px 8px; background: rgba(19, 23, 19, 0.05); color: #131713; border-radius: 4px`

**Text style:** `category` — General Grotesque Mono 400 · 9px/1.6 · tracking 0.1em · uppercase

**Observed:** Filled chips use a smaller mono recipe than outlined section labels, and sit in a row with 6px gaps.

### Editorial card

**Only for:** editorial collections

**Use:** Link to an article or update.

**CSS:** `display: flex; flex-direction: column; padding-bottom: 40px; overflow: hidden`

**Text style:** `caption-title` — Bagoss Standard 520 · 14.1px/1.4 · tracking 0.01em

**Observed:** An image leads; a mono date sits 10px below, followed by a title and short caption after a 20px gap. A featured half-width card sits alongside two quarter-width cards.

## Imagery and graphics

### Human and material sequence

**Use:** The principal visual language, including a photographic band within the first screen.

**Observed:** Warm, natural photographs show people at work, book-filled interiors, planted corners and physical objects in use. Rich shadows, timber, leather, fabric and paper supply texture. Photographs occupy entire strips or half-page frames; they are not small floating decorations.

**Transfer:** Photograph the new product in real spaces, show its making or show people using it. Without polished campaign assets, a coherent set of close-ups of tools, hands and materials is the minimum equivalent.

### Environmental portraits

**Only for:** team or contributor sections

**Use:** Consistent people grid.

**Observed:** Waist-up portraits use a shared shelf-lined interior; clothes retain their colour, faces are warmly lit and backgrounds remain recognisable. Full-bleed frames have restrained 4px corners.

**Transfer:** Use one believable work setting with consistent camera distance and soft directional light, rather than isolated cutouts.

### Applied identity proof

**Only for:** portfolio and case-study sections

**Use:** Large media sequences demonstrating work in the world.

**Observed:** Graphic artwork alternates with photographed brochures, windows, street posters and phones on timber or leather. One case-study treatment uses teal, emerald and red with architectural curves; another uses pink, yellow and mint geometric figures. These are separate artwork palettes, not marketing-interface colours.

**Transfer:** Pair a clean flat presentation with its real-world use. For a digital product, show a credible screen in a real hand or setting as well as an isolated product view; retain the page's neutral frame.

### Stacked story photographs

**Only for:** chronological story sections

**Use:** A scroll-linked visual beside chronological text.

**Observed:** A near-square image occupies the left half, while the right half lists dated story titles and body copy. A few preceding image edges peek above the current photograph like a shallow stack; inactive text recedes while the current title stays bright.

**Transfer:** Use a chronological sequence of product milestones or applications. If scroll linking is unavailable, retain paired images and text as separate chapters.

**Build:** Create three absolutely positioned image layers in a relative frame about 690px wide. Use 4px corners; centre the rear layers at progressively narrower widths and offset their top edges by about 20px. Keep the active image at full width in front, without shadows or rotation.

### Icons

**Observed:** Sparse directional iconography: 23px filled SVG arrows at the far edge of long links. Testimonial navigation uses 40px ivory squares with dark directional glyphs and 4px corners.

**Transfer:** Use simple directional arrows; avoid decorative feature icons competing with the typography.

## Section recipes

How recurring sections are built.

### First screen: Belief-led opening

**Observed:** Dark canvas is the back layer; Navigation sits along its top edge. A 260px top inset lets the left-aligned two-line display statement occupy roughly the left half of the screen, with its text box extending no farther than about three fifths of the width. The 26.2px lead follows after 36px and remains in a 690px column. The right half stays open. The opening text section ends at 638px, where a horizontally overflowing strip of 500px square photographs begins, with 14px gaps. Within the first 900px, navigation, the entire headline, all support copy and the upper 262px of the photographic strip are visible. There is no hero button; the next explanatory statement is below the fold.

**Transfer:** Lead with the new product's human belief or benefit, then a concise explanation. Make the strip from its process, environment or use if campaign art is unavailable. Case-study pages instead open with an 837px media field and a slim metadata line; the light portfolio variant introduces its main statement after the media.

**Avoid:** Do not centre a slogan over a glowing product mockup, insert a pair of pill CTAs, or fill the open right half with generic decoration.

**Text style:** `display` — Bagoss Standard 520 · 78.7px/0.9 · tracking -0.02em

### Split editorial statement

**Observed:** An Outlined label anchors the left edge while a heading and muted body occupy the right half. The dark version uses 200px top and 100px bottom padding, a 39.4px heading and 40px between heading and body.

**Transfer:** Use this to explain why a product matters, how it works or what distinguishes it; keep the two halves visibly unequal in density.

**Text style:** `heading` — Bagoss Standard 520 · 39.4px/1.1 · tracking -0.01em

### Capability index

**Observed:** An Outlined label sits above a four-column grid of Capability cards with 14px gutters. The section uses 100px top and 120px bottom padding. The paper variant replaces cards with a small sticky visual at left and a 59px list at right; current content darkens while inactive names recede.

**Transfer:** Choose the card form as the default. Use the list form only for a light portfolio-style capability overview.

### Names as proof

**Observed:** An Outlined label occupies the left quarter, while two columns of names use display-list typography, no individual boxes and little vertical separation. The dark canvas continues behind all three areas.

**Transfer:** Use substantiated customer names, compatible systems or a meaningful set of contexts. If none are available, typeset verifiable use cases rather than fabricating logos.

**Text style:** `display-list` — Bagoss Standard 520 · 59px/1 · tracking -0.02em

### Chronological story pair

**Observed:** A short heading introduces the section, then Stacked story photographs occupy the left half against dated narrative entries on the right. The active title is ivory; past and upcoming entries recede to 25% ivory.

**Transfer:** Use the paired treatment to show an evolving product or multiple applications without making a conventional card grid.

### Broad testimonial rail

**Observed:** An Outlined label precedes a horizontal rail of dark Quiet panels. The leading panel occupies about three quarters of the content width; the next is clipped at the right edge and visually subdued. Quotes use a heading-scale sans treatment, with small square previous and next controls below.

**Transfer:** Use real, attributed customer language with enough space to read as a statement, not a compact rating widget.

### Proof ledger closing

**Observed:** An Outlined label and 39.4px heading occupy the left portion of a dark section. After 80px, the Proof ledger extends across the full content width. Another 80px separates it from the final Ruled action. The last content is the action and its baseline, not a giant closing slogan.

**Transfer:** Close with credible proof and a useful continuation, adapting the ledger's columns to the new product.

**Text style:** `heading` — Bagoss Standard 520 · 39.4px/1.1 · tracking -0.01em

### Case-study visual chapters

**Only for:** case studies

**Observed:** On Paper canvas, project title, short proposition and year form a slim uppercase metadata line below the opening media. A 39.4px introduction begins one column in. Explanatory chapters use a 560px reading column with 140px top and 40px bottom padding, small chapter-title headings and muted body copy. Media follows as 1400px-wide landscapes or paired 693px portraits with 14px bottom gaps. After the last media, a Ruled action begins beneath 100px of breathing room.

**Transfer:** Tell a specific product or customer story through concept, applications and human context. Use the visual sequence only when there is enough substantive proof.

**Text style:** `chapter-title` — Bagoss Standard 520 · 17px/1.4

### Asymmetric editorial band

**Only for:** light portfolio editorial endings

**Observed:** Editorial wash backs an Outlined label, one half-width feature and two quarter-width Editorial cards. Their tops align; images dominate and dates, titles and captions sit below. A Ruled action spans the base.

**Transfer:** Use for useful articles or product stories in the light variant, not as a repeated accent card style.

## Page flow

**Storyline:** belief or visual hook → positioning → tangible demonstrations → capabilities and people → substantiated proof → quiet continuation

### Broad portfolio-led introduction

1. **Visual hook** — A full-height moving-image stage precedes navigation and a large, offset positioning statement.
2. **Demonstration** — A two-column mixed-aspect portfolio grid alternates paired stories with a wide visual.
3. **Capabilities** — A small visual and caption sit beside a large changing capability list.
4. **Editorial continuation** — An asymmetric peach article band ends in a full-width ruled link.

**Transfer:** Use when the product has a substantial body of visual applications; keep the paper variant and reserve peach for the editorial ending.

### Explain a sophisticated identity or product system through atmosphere and applications

1. **Visual hook** — Full-width architectural media carries small navigation; a metadata strip follows.
2. **Positioning** — A medium-scale introductory statement explains the work and a small service list supplies context.
3. **Concept** — A short left-column chapter explains the central idea.
4. **Demonstration** — Wide media and paired portraits alternate, joining people, physical artifacts and digital applications.
5. **Continuation** — A next-story label and muted destination share the final ruled arrow link.

**Transfer:** Use atmospheric context to explain why the system looks as it does, then show varied real applications rather than endless text.

### Show a colourful transformation and its usable digital expression

1. **Visual hook** — A full-width geometric artwork field leads into a slim project metadata line.
2. **Positioning** — A medium-scale introduction names the human purpose.
3. **Concept** — A small chapter explains the visual principle.
4. **Demonstration** — Media moves between flat artwork, physical print, signage and people.
5. **Product demonstration** — A later chapter introduces the digital experience, followed by screen compositions and a phone in context.
6. **Continuation** — The final image is followed by a ruled next-story link.

**Transfer:** Keep colourful campaign art inside media frames while the surrounding case study remains on paper.

### Default belief-led marketing and organisational introduction

1. **Promise** — A dark, left-weighted belief statement and support lead directly into environmental photography.
2. **Positioning** — A left label and right-hand heading with supporting prose articulate the approach.
3. **Capabilities** — Four understated panels make the offering legible.
4. **Social proof** — Customer names become a large two-column typographic field.
5. **People** — Consistent full-bleed portraits humanise the organisation.
6. **Applications and history** — Stacked photographs and chronological entries tell a wider story.
7. **Endorsement** — Broad quote panels introduce external voices.
8. **Credentials and continuation** — A concise introduction, proof ledger and ruled link conclude the content.

**Transfer:** Use the dark belief-led composition for a new marketing page, substituting product benefits, real users and verifiable credentials. These are narrative options, not a required section sequence.

## Writing

Thoughtful, warm and culturally literate, with confidence expressed through direct sentences and concrete work rather than swagger. It balances strategic language with human feeling and a lightly conversational turn of phrase.

**Do not copy:** Do not reuse the agency name, wolf illustration, customer identities, project slogans, dates, awards, longevity claims or testimonials as assets or claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Primarily 'we' for the maker, 'people' for the audience, and occasional 'you' when discussing a felt benefit. Actions address the reader without sales pressure.
- **Rhythm:** Brief belief statements and chapter titles contrast with explanatory paragraphs of two or three sentences. Em dashes introduce a human clarification; three-part lists are common. Navigation and action labels stay short.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening belief | A plain statement about the better experience the organisation believes in. | 4–8 words | “We believe in life made better.” |
| Supporting statement | Begin with values or motivation, then describe the people and outcome. | 20–30 words | “Rooted in culture and driven by curiosity, we work with people who are determined to make great things and enjoy the journey along the way.” |
| Project proposition | Name the human effect, not a catalogue of deliverables. | 3–12 words | “The feeling that stays with you after the final note.”<br>“Every story matters.” |
| Capability support | A practical action followed by a purposeful consequence. | 10–16 words | “Preparing the ground – setting out a plan that’s purposeful and effective.” |
| Proof introduction | Acknowledge a limit, then explain why the proof matters. | 12–20 words | “Awards aren’t everything, but they’re a great way to celebrate creative benchmarks.” |
| Action | Short, literal destination or continuation. | 1–3 words | “View All”<br>“View Bio” |

**Words and phrasing to use:** people; purposeful; crafted; feeling; curiosity; everyday; make; bring to life; connect

**Avoid:** revolutionary; 10x; disrupt; unparalleled; synergy; unlock limitless potential

**Rules:**

- Tie abstract principles to a concrete application or a felt human benefit.
- Use a restrained conversational phrase rather than an inflated superlative.
- Keep metadata factual and terse; let the larger statement carry personality.
- Avoid pressuring the reader with urgency language; offer a clear next destination.

## Do's and Don'ts

### Do

- Keep the default canvas #131713 and primary text #f7f3f0.
- Use the 78.7px/0.9 display recipe with -0.02em tracking for a short, left-aligned promise.
- Preserve 20px side padding and the distinction between 20px editorial gutters and 14px media gutters.
- Make 4px corners consistent across labels, photographs and panels.
- Pin wrapping mono capability labels to the bottom of 400px panels.
- Use a 42px full-width ruled row as the concluding action.
- Mix real materials and people with graphic demonstrations rather than showing only flat artwork.
- Typeset a proof device in 59px names or 10.4px mono ledger rows.

### Don't

- Do not turn the green black into pure black or the ivory into bright white.
- Do not introduce 16px or 24px rounded-card corners; the edge language is 4px.
- Do not add drop shadows or glass blur to the flat tonal panels.
- Do not use saturated artwork colours for navigation, body text or every section background.
- Do not replace the tiny 10.4px mono labels with bold sans headings.
- Do not place all portfolio imagery in equal square tiles; keep mixed aspect ratios and wide interruptions.
- Do not enlarge explanatory case-study chapter headings to the display size; their 17px scale is intentionally modest.
- Do not present names-as-proof as a wall of bordered logo badges.

## Motion and responsive

### Motion

**Observed:**

- Navigation colour and capability panel background transitions use 400ms declarations; some colour transitions use 650ms.
- Hero media is sticky; capability imagery and chronological image stacks also use sticky positioning.
- Text and image sequences change emphasis as the page progresses. Skip navigation declares a focus-visible transform of none.

**Transfer:**

- Keep a stable editorial grid while the active story or capability changes emphasis.
- Use the stacked-image metaphor for chronological content rather than adding unrelated parallax effects.

**Unknown:**

- Complete spring-like linear easing curves are unavailable; exact hover colours and motion choreography are not specified.
- Video content and timing for the broad portfolio opening remain unspecified.

### Responsive

**Observed:**

- Declared width thresholds include 810px, 1200px, 1440px, 1500px, 1920px and 2560px.

**Transfer:**

- On narrow screens, preserve label-before-statement reading order and stack the split halves; retain the difference between intimate captions and strong statements.
- Reduce the four-column capability and portrait grids to fit readable card widths; keep image and text associations intact.
- Keep a visible hint of the next photograph or quote in horizontal rails instead of squeezing all items into one row.

**Unknown:**

- Mobile layouts, exact font-size changes, navigation collapse and reduced-motion behaviour are not established. These narrow-screen adaptations are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
