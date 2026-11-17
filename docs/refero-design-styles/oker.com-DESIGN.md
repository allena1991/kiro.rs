# Oker — showreel meets ledger

## Overview

An image-led editorial style with the restraint of an index and the scale of an exhibition. White space, near-black geometric sans typography and pale grey annotations surround richly varied photography, product renders and moving identity studies. It suits visually differentiated products and creative services, balancing sparse navigation with immersive proof. A red, text-heavy institutional variant adds a more declarative register.

### Essentials

- The first impression is a showreel, not a sales headline: a 64px navigation band sits above a near-full-width 1408×873px media stage with 16px side margins; the verbal introduction comes afterward.
- Headlines behave like light, oversized editorial type: 80px NextBook at weight 300, 80px or 90px line height and -0.02em tracking; small annotations stay at 16px/20px with -0.01em tracking.
- Actions are unboxed words: 16px navigation and underlined contact links, without filled buttons, pill outlines or elevated containers.
- The interface stays monochrome while the work supplies color: white canvas, #101010 text, #a0a0a0 metadata and #dcdcdc rules; saturated fields belong inside media, not across the ordinary page canvas.
- Proof is staged as an exhibition: square-edged paired landscape or portrait images, 16px gutters, split title-and-description captions and 120px pauses between project rows.
- A monumental wordmark closes the experience: a 900px-tall ruled footer carries tiny contact columns above a 1408×204px bottom-aligned word graphic. Use the new identity as the graphic, set as fitted live type or SVG when no wordmark exists.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background | Default marketing canvas and the space around media. |
| Hairline grey | `#dcdcdc` | `--color-rule` | border | Thin separators on white. |
| Annotation grey | `#a0a0a0` | `--color-muted` | text, link | Supporting descriptions, service lists, footer labels and contact-link hover. |
| Near black | `#101010` | `--color-ink` | text, link, border | Main typography and links; strong rules on the red institutional variant. |
| Graphic black | `#000000` | `--color-graphic-black` | accent | Solid identity graphics and the small navigation emblem. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| institutional and about pages | Vermilion canvas | `#d74435` | `--color-institutional-red` | background | Continuous red canvas, including the footer. |
| institutional and about pages | Muted ink on red | `#742a23` | `--color-red-muted` | text | Visible result of rgba(16,16,16,0.5) over the red canvas; used for labels and secondary lists. |

## Typography

- **NextBookRegular** — Paragraphs, captions, navigation and regular-cut introductions. Geometric sans with circular bowls, open spacing in small text and a light display cut. If unavailable, use **DM Sans**. Use weights 300 and 400; retain the tight display tracking and geometric proportions. Font stack: "NextBookRegular", "DM Sans", sans-serif.
- **NextBookLight** — Light display headings and standalone counts. Light geometric sans with circular bowls and broad, open forms. If unavailable, use **DM Sans**. Use weight 300 with the specified negative tracking. Font stack: "NextBookLight", "DM Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | NextBookLight | 300 | 80px | 1.125 | -0.02em | Post-showreel identity heading and short project propositions. |
| section-heading | NextBookLight | 300 | 80px | 1 | -0.02em | Single-word section titles beside a small support line. |
| intro | NextBookRegular | 300 | 32px | 1.125 | -0.02em | Substantial introductory paragraph and related-content heading. |
| project-title | NextBookRegular | 400 | 24px | 1.125 | -0.02em | Linked titles beneath featured project media. |
| body | NextBookRegular | 400 | 16px | 1.25 | -0.01em | Body copy, metadata, timestamps, contact details and labels. |
| navigation | NextBookRegular | 400 | 16px | 1 | -0.01em | Navigation links and compact news titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case-study pages | case-title | NextBookLight | 300 | 160px | 1.125 | -0.02em | Project name above the lead film. |
| case-study and institutional pages | chapter-statement | NextBookLight | 300 | 80px | 1 | -0.04em | Long, multi-line editorial statements between visual chapters. |
| institutional proof sections | stat | NextBookLight | 300 | 80px | 1 | -0.002em | Standalone count aligned to a dense supporting roster. |
| case-study testimonials | quotation | NextBookRegular | 400 | 32px | 1.125 | -0.02em | A substantial quote beneath a full-width photograph. |

**Notes:**

- Use light display type against regular small type; do not introduce a bold heading tier.
- The display-to-label contrast is 80px to 16px. Long editorial statements tighten tracking to -0.04em; short titles use -0.02em.
- The closing wordmark is artwork fitted to its frame, not a 160px live heading. Preserve its broad silhouette and 204px graphic height at desktop.

## Layout

**Density:** Airy at section level, compact within captions and index rows; long pauses separate tightly packed information.

### Spacing

**Spacing system:**

- **rhythm** 8px, vertical — Underlying vertical increments for most non-fluid spacing.
- **column-step** 16px, horizontal — Side margins, media gutters and caption subdivisions.

| Value | Use |
| --- | --- |
| 8px | Minor inset adjustments. |
| 16px | Page edges, media gaps, caption separation and rule-to-content padding. |
| 40px | Index-row bottom spacing and supporting section clearance. |
| 48px | Title-to-gallery separation. |
| 60px | Institutional text-block clearance. |
| 64px | Navigation band and start of the main media. |
| 120px | Featured-project row pauses and introductory section breaks. |
| 240px | Major editorial chapter breaks and space before the closing area. |

### Containers and grids

- **page-frame**: max width 1440px · side padding 16px. Broad desktop frame with 1408px of usable width; content nearly meets the viewport edges.
- **editorial-grid**: 4 columns · gap 16px. Four 340px tracks at desktop; titles occupy the first track, explanatory text begins on the second, and wide media spans two or four.
- **featured-pair**: 2 columns · gap 16px. Equal landscape or portrait media pairs. Use 696px image widths within the 1408px frame; captions divide again into title and description.
- **reading-column**: max width 607px. Introductory 32px copy occupies under half the desktop width, leaving a deliberate open right side.
- **archive-grid** (only for catalogue and portfolio index pages): 4 columns · gap 16px. 340px-wide small images and 696px-wide featured images, generally 4:3. A large item spans two columns and establishes a taller shared row.

## Corner radius

| Element | Radius |
| --- | --- |
| media and interface edges | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default page material.

**CSS:** `background-color: #ffffff; color: #101010`

**Observed:** The surface is flat and untextured; visual depth comes from photography rather than interface elevation.

**Transfer:** Let images carry material, color and lighting.

#### Ruled editorial plane · level 0

**Use:** Information sections and footer boundaries.

**CSS:** `border-top: 1px solid #dcdcdc; padding-top: 16px`

**Observed:** A single fine line divides broad content bands without boxing the entire section.

**Transfer:** Use for clear changes of information, not around every image.

#### Red institutional canvas · level 0

**Only for:** institutional and about pages

**Use:** A continuous alternate page theme.

**CSS:** `background-color: #d74435; color: #101010`

**Observed:** The red extends through text, photography surrounds, index and footer. Rules become near black; secondary text becomes half-opacity ink.

**Transfer:** Keep the entire institutional narrative on one field rather than alternating red promo cards.

## Components

### Navigation band

**Use:** Persistent visual identity at the top of the document.

**CSS:** `position: absolute; top: 0px; padding: 16px; height: 64px; box-sizing: border-box; z-index: 10`

**Text style:** `navigation` — NextBookRegular 400 · 16px/1 · tracking -0.01em

**Observed:** Brand name begins at the left; a live elapsed-time-style readout aligns with the second grid track; four plain links start around the middle; a small circular identity emblem is pinned to the far right.

**Transfer:** Use a compact product name and a meaningful status or short metadata readout in the second track. Keep the interface visually light.

### Navigation link

**Use:** Primary page navigation.

**CSS:** `color: #101010; background: none; text-decoration: none; font-size: 16px; line-height: 16px`

**Text style:** `navigation` — NextBookRegular 400 · 16px/1 · tracking -0.01em

**Observed:** Links are bare text without surrounding button geometry. Current-page treatments use underline or muted text in the institutional theme.

**States:** Declared: hover text-decoration underline; focus-visible not specified.

### Contact link

**Use:** Direct conversion and social destinations.

**CSS:** `color: #101010; text-decoration: underline; background: none`

**Text style:** `body` — NextBookRegular 400 · 16px/1.25 · tracking -0.01em

**Observed:** Email and social links are stacked as short lines under muted labels; the phone is presented as plain text rather than requiring an underline.

**States:** Declared: hover color #a0a0a0; focus-visible not specified.

**Transfer:** Prefer direct contact or a short textual conversion action over a prominent filled CTA.

### Featured project caption

**Use:** Identify a large visual and describe its relevance.

**CSS:** `display: flex; justify-content: space-between; padding-right: 8px`

**Text style:** `project-title` — NextBookRegular 400 · 24px/1.125 · tracking -0.02em

**Observed:** The title sits on the left half beneath the media. The right half contains one short black descriptive sentence, then muted disciplines; both begin after a 16px vertical separation.

**Transfer:** Use a product or use-case name on the left and its outcome plus category list on the right.

### News slide

**Use:** A lateral stream of recent activity.

**CSS:** `width: 336px; margin-right: 16px`

**Text style:** `navigation` — NextBookRegular 400 · 16px/1 · tracking -0.01em

**Observed:** Each slide has a 336×420px portrait visual, then a compact title and small metadata. The strip extends past both viewport edges and reveals partial neighboring items.

**Transfer:** Show useful launches, updates or stories with editorial imagery rather than icon tiles.

### Monumental footer

**Use:** Contact close and identity punctuation.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; height: 900px; box-sizing: border-box; padding: 16px; border-top: 1px solid #dcdcdc`

**Text style:** `body` — NextBookRegular 400 · 16px/1.25 · tracking -0.01em

**Observed:** Contact and social groups occupy the first two tracks, copyright begins on the third, and year range aligns right. A very broad wordmark sits along the bottom, with a long empty interval above. On the red theme the footer inherits red and uses an ink rule.

**Transfer:** Give the new identity an equally decisive bottom graphic; keep contact details small and at the top rather than centering a sales message.

### Index row

**Only for:** related-content and institutional indexes

**Use:** Dense cross-links after long narratives.

**CSS:** `padding-bottom: 40px`

**Text style:** `body` — NextBookRegular 400 · 16px/1.25 · tracking -0.01em

**Observed:** A full-width ruled row splits into year, name, stacked disciplines, elapsed-time-style number and underlined destination. The content starts 16px below a fine top rule; row heights follow the length of the lists.

**Transfer:** Use dates, titles, categories and a destination as an editorial index rather than turning related content into oversized cards.

### Roster count

**Only for:** institutional proof sections

**Use:** Quantified proof linked to a complete roster.

**CSS:** `margin-top: 8px; color: #101010`

**Text style:** `stat` — NextBookLight 300 · 80px/1 · tracking -0.002em

**Observed:** An isolated light count in the first column is balanced by a narrow, dense list of names in the next column and a small establishment date farther right. The numeral is not a metric card.

**Transfer:** Pair a true count with the names or items it summarizes, retaining the extreme scale contrast.

## Imagery and graphics

### Opening showreel montage

**Use:** The dominant first-screen object and visual promise.

**Observed:** A single broad film shows an identity system as a multi-panel montage: logo, red tonal swatches, dark industrial overhead photography, a warm portrait, a device in hand and large type specimens. Softly rounded panels belong inside the film, surrounded by a pale backing; the web frame itself is square-edged.

**Transfer:** Create a coherent montage of the new product's object, people, interface and graphic language. If film is unavailable, use a carefully composed still contact sheet with the same varied scale and density.

**Build:** Within one 1408×873px media composition, arrange three unequal columns with narrow pale gutters: short identity and color panels across the top, taller human/product panels below, one tall typographic panel at the right. Use real product photographs, a self-authored word sample and a tonal strip of the product's own accent. Clip the complete composition as one rectangular image; internal soft corners do not become page card radii.

### Exhibition media pairs

**Use:** Recurring visual proof throughout landing and case-study pages.

**Observed:** Large hardware details, garments, books, transport products, signage and digital applications appear as close, art-directed images. Landscape pairs alternate with tall portrait pairs; soft peach, lilac, concrete and natural foliage vary by project. Caption text occupies little space compared with the image.

**Transfer:** Show product material at close range and the result in use; preserve a consistent lighting language within each paired story. A well-lit photograph of a real artifact is an acceptable replacement for a sophisticated render.

### Closing word graphic

**Use:** Signature identity device at the end of every page type.

**Observed:** A black horizontal wordmark spans 1408px and occupies a 204px-high graphic frame near the bottom edge of a viewport-height footer.

**Transfer:** Fit the new name into a similarly wide silhouette; use a carefully spaced live-type wordmark if custom artwork is unavailable.

**Build:** Use a single-line SVG with viewBox matched to the new name's proportions; fit it to the available width without distortion. Align its baseline visually to the footer's lower inset, using solid black letterforms and no shadow or decorative container.

### Warm integration study

**Only for:** warm technology case studies

**Use:** Product, contextual and application chapters.

**Observed:** Dark textured hardware is enlarged against peach light; sunset landscapes, concrete interiors, warm fabric, brown packaging and black devices create a tactile, domestic atmosphere. Full-width scenes alternate with half-width images and text-led explanation.

**Transfer:** Use warm directional lighting on the new object and connect it to real environments. Keep colors inside the photography and designed applications, not in the navigation.

### Comic identity study

**Only for:** playful consumer case studies

**Use:** A lively visual system demonstrated across real touchpoints.

**Observed:** Direct-flash food and worker photography alternates with green hand-drawn mishap illustrations on warm off-white, saturated green product backdrops and green duotone halftone film panels. The color is emphatic inside the media but the editorial frame remains white.

**Transfer:** Translate the product's own humor into one-color drawings and tactile photography rather than importing a generic mascot.

**Build:** Draw a small set of irregular SVG paths with rounded ends, sparse motion marks and one or two solid shapes, grouped low or centrally on a warm pale panel. Use one product accent for all strokes. Pair each drawing with a tightly framed real photo; for a halftone study, convert a photo to monochrome, tint it with that accent and overlay a fine regular dot pattern.

### Documentary workplace photography

**Only for:** institutional and about pages

**Use:** Human context between declarative text sections.

**Observed:** Unposed office scenes, reading, daylight, greenery and architectural texture; two 518px square photographs sit to the right of a narrow section-label column. Captions include time, date and photographer credit at 16px/20px.

**Transfer:** Photograph genuine work environments in available light, using observational framing instead of matching corporate headshots.

### Icons

**Observed:** Navigation ends with a 32×32px black circular identity emblem containing small white geometric marks. General marketing sections do not rely on a repeated feature-icon language.

**Transfer:** Use a compact identity symbol in that position; keep product icon systems confined to the relevant product demonstration.

## Section recipes

How recurring sections are built.

### First screen: Showreel opening

**Observed:** White canvas behind a 64px-high Navigation band, followed by a 1408×873px rectangular media stage inside 16px side margins. The montage dominates everything below the header. At 900px viewport height, navigation and most of the film are visible, while the stage continues 37px below the fold. There is no separate overlay headline, supporting paragraph or CTA button: the media itself is linked. The 80px light identity heading and small facts arrive 16px after the film and therefore below the first screen. Rounded shapes and large words occur within the artwork, not as interface layers.

**Transfer:** Lead with a film or authored still montage of the new product's material, interface and human context; let it establish the promise before a short live introduction. A detail page instead opens with the case-title recipe, then a full-width film; an index opens with small introductory lines and a grid; an institutional page opens with metadata and a chapter-statement on red.

**Avoid:** Do not replace the dominant media with a centered slogan-and-button hero or place unrelated feature cards above the fold.

**Text style:** `display` — NextBookLight 300 · 80px/1.125 · tracking -0.02em

### Identity and introduction

**Observed:** A light display heading sits left with small facts at the far right. After a 120px pause, an ink introduction uses the intro recipe in a 607px reading width, while smaller purpose and service lists align to the remaining tracks; a fine rule ties the row together.

**Transfer:** Name the product briefly, then explain what it enables in a short, substantial paragraph balanced by concise attributes.

**Text style:** `intro` — NextBookRegular 300 · 32px/1.125 · tracking -0.02em

### Heading and gallery

**Observed:** The section-heading recipe occupies the first grid track with a small muted explanation and underlined destination on the next track. After 48px, either News slides run horizontally or paired media fills the width. Featured project captions sit below, and project rows have 120px breaks.

**Transfer:** Use a plain category heading to introduce evidence, updates or use cases. Vary image aspect ratio by story rather than forcing all content into the same box.

**Text style:** `section-heading` — NextBookLight 300 · 80px/1 · tracking -0.02em

### Index and identity close

**Observed:** Long detail narratives end with an intro-sized related-content heading and Index rows. The Monumental footer follows on white; index and institutional pages also finish with the same contact columns and enormous bottom word graphic, with red inherited on the institutional variant.

**Transfer:** Offer relevant next destinations before the contact close. Preserve the contrast between tiny actionable details and enormous identity instead of adding a conventional conversion banner.

**Text style:** `body` — NextBookRegular 400 · 16px/1.25 · tracking -0.01em

### Case-study chapter

**Only for:** case-study pages

**Observed:** A 160px project name precedes a broad lead film. A short 80px proposition sits below it with small client, date, disciplines and credits at the right. Introductory 32px copy gives way to full-width 16:9 or 4:3 media, paired 696px portraits and long chapter-statement passages separated by 240px top pauses and 16px before the next image.

**Transfer:** Move from premise to concept to visible applications. Use chapter statements to explain why the following evidence matters, and weave small captions into selective half-width studies.

**Text style:** `chapter-statement` — NextBookLight 300 · 80px/1 · tracking -0.04em

### Photograph and testimonial

**Only for:** case-study testimonials

**Observed:** A broad contextual photograph is followed after 16px by a 32px quote on the left, with smaller attribution farther right; the quote column is about 623px wide and the section clears the next chapter by 240px.

**Transfer:** Attach a credible, specific testimonial to a concrete image of the product in context, not a floating quote card.

**Text style:** `quotation` — NextBookRegular 400 · 32px/1.125 · tracking -0.02em

### Institutional editorial bands

**Only for:** institutional and about pages

**Observed:** On Red institutional canvas, ink rules and small half-opacity labels introduce long 80px chapter statements. Compact paragraphs begin on the second track; documentary image pairs and the Roster count interrupt the text before a full project index.

**Transfer:** Alternate a clear thesis with documentary proof, compact explanation and a verifiable roster. Keep the strong color continuous.

**Text style:** `chapter-statement` — NextBookLight 300 · 80px/1 · tracking -0.04em

## Page flow

**Storyline:** Visual promise → concise positioning → editorial evidence → deeper applications or proof → relevant next destinations → contact and monumental identity.

### Image-led marketing landing page

1. **Visual promise** — Linked showreel fills the first screen beneath small navigation.
2. **Positioning** — Light identity heading, small facts and a substantial left-aligned introduction.
3. **Freshness and proof** — Lateral news stream followed by paired featured projects.
4. **Closing contact** — Viewport-height contact footer ending in fitted wordmark artwork.

**Transfer:** Lead with authored visual evidence and use concise editorial copy to give it meaning.

### Playful consumer case study

1. **Introduction** — Oversized project name, film, proposition and metadata.
2. **Concept** — Compact introduction and large statements explaining the visual idea.
3. **Application proof** — Alternating flash photography, illustrated panels, ordering experience, physical space and packaging.
4. **Continuation and contact** — Related-content index followed by the shared monumental footer.

**Transfer:** Use the consumer product's own personality inside media while preserving the neutral editorial shell.

### Warm technology case study

1. **Introduction** — Oversized name, sunrise film, short proposition and project details.
2. **Design rationale** — Introductory copy, product close-ups and small logo/icon explanation studies.
3. **Credibility** — Contextual photography and a substantial attributed quote.
4. **Applications** — Color, type, campaign, digital and packaging studies separated by large statements.
5. **Continuation and contact** — Related-content ledger and shared wordmark footer.

**Transfer:** Connect technical quality to tactile materials, real use and a coherent light palette.

### Browsable visual index

1. **Orientation** — Two short introductory lines beneath navigation, with a fine rule.
2. **Breadth of proof** — Four-column media index with occasional two-column highlights and compact titles.
3. **Closing contact** — Shared contact columns and giant bottom wordmark.

**Transfer:** Let imagery and varied scale do the categorization rather than adding dashboard-like controls.

### Institutional story and credentials

1. **Orientation** — Small establishment and availability lines on red.
2. **Thesis** — Large light statements, ink rules and compact labeled explanations.
3. **Human proof** — Documentary workplace imagery and timestamped credits.
4. **Quantified proof** — Isolated count paired with a dense roster and establishment date.
5. **Breadth and contact** — Long ruled index leading into the same monumental footer on red.

**Transfer:** Use the alternate theme for a sustained organizational narrative, not as the default product landing appearance.

## Writing

Confident and matter-of-fact, with an editorial interest in how ideas become tangible work. Personality comes from a precise metaphor or an understated turn of phrase rather than superlatives.

**Do not copy:** Do not reuse the studio or client names, logos, illustrations, project claims, establishment dates, counts, contact details or testimonial wording. Replace them with the new product's own identity, facts and permissioned quotes. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The organization speaks as we; projects and products are described in the third person. Direct reader address is uncommon; actions name destinations plainly.
- **Rhythm:** Short section nouns and three-to-seven-word propositions sit beside substantial explanatory sentences. Captions are compact; long display paragraphs are reserved for editorial chapter transitions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Proposition | Compress the concept into a memorable, plain phrase. | 3–7 words | “Power in simplicity.”<br>“Burgers with a side of slapstick” |
| Section heading | One everyday noun, without a promotional qualifier. | 1–2 words | “Feed”<br>“Work” |
| Action | A direct destination or an understated invitation. | 2–3 words | “Browse more”<br>“View all”<br>“Reach out” |
| Explanation | Link a visible design decision to its intended effect. | One or two sentences | “The icons translate the logo’s principles into a unified system, recognizable even in the smallest applications.” |
| Editorial chapter | An explanatory sentence enlarged to carry the next chapter. | 20–40 words | “The identity carries through into the ordering experience, taking convenience seriously without taking ourselves too seriously.” |

**Words and phrasing to use:** forms; clarity; focused; crafted; identity; experience; integration; simplicity

**Avoid:** revolutionary; game-changing; unlock your potential; best-in-class; limited time; supercharged

**Rules:**

- Describe what the product does before claiming its importance.
- Keep service or capability metadata as plain compact lists.
- Use wit only when it follows the product's concept; keep interface labels literal.
- Let chapter text explain a decision or result, not repeat the section name.

## Do's and Don'ts

### Do

- Keep the desktop frame at 16px side margins and align annotations to four underlying tracks.
- Set short display headings at 80px, weight 300 and -0.02em tracking.
- Keep ordinary metadata at 16px/20px with -0.01em tracking.
- Use 1px grey rules to structure white editorial sections.
- Separate major project rows by 120px and editorial chapters by 240px.
- Preserve 16px image gutters and square outer media edges.
- Finish with small contact columns and a 204px-high fitted identity graphic.

### Don't

- Do not turn 16px text actions into filled 48px pill buttons.
- Do not introduce shadows or rounded containers around project captions.
- Do not use the red institutional canvas as the ordinary landing-page default.
- Do not promote image-internal fonts, colors or panel corners into global UI tokens.
- Do not set long editorial statements in heavy bold type or all capitals.
- Do not shrink every proof image into a uniform four-column card grid on a landing page.
- Do not replace the broad identity footer with a short centered CTA strip.

## Motion and responsive

### Motion

**Observed:**

- Word-wrapped display text declares transform 0.6s cubic-bezier(0.77, 0, 0.18, 1) 0.1s and opacity 0.6s cubic-bezier(0.77, 0, 0.18, 1) 0.2s transitions.
- Project title links declare color 0.3s cubic-bezier(0.645, 0.045, 0.355, 1).
- The news stream uses a horizontally translated, overflow-hidden slide track. Opening and project media include video.

**Transfer:**

- Keep display reveals word-based and clipped by wrappers rather than animating whole cards.
- Use movement primarily to reveal identity work and to move the editorial strip; retain a strong still composition.

**Unknown:**

- Video playback rules, trigger thresholds, slider timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop composition uses a 1440px frame with 16px side padding.
- Styles declare width breakpoints including 501px, 751px, 752px, 1001px, 1040px and 1424px.

**Transfer:**

- On narrow screens, retain a media-first opening and move its introduction below rather than overlaying it.
- Reduce paired media to a single reading sequence when needed; keep each title with its image and description.
- Scale the closing word graphic to available width without distortion and keep contact groups above it.

**Unknown:**

- Exact mobile type sizes, breakpoint-specific navigation and reflow rules are not established; these adaptations are design guidance rather than fixed mobile measurements.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
