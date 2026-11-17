# Josephmark — culture on a black stage

## Overview

A spare, art-directed studio language that pairs a black theatrical canvas with unusually light grotesk typography and vivid cultural imagery. White and warm stone chapters interrupt the darkness without turning the interface colorful. It suits ambitious creative products, technology studios and portfolios whose demonstrations can carry more personality than their navigation; the density is low in text and high in visual impact.

### Essentials

- The promise reads like a softly spoken manifesto, not a billboard slogan: light 300-weight grotesk at 70.4px/1.1 with -0.035em tracking, occupying roughly two thirds of the opening width.
- The opening has a deliberate long inhale: small name and Menu at opposite edges, 280px top padding before the left-aligned statement, then an edge-to-edge media stage beginning at 654px; the first action comes later.
- Color belongs to the work, not the controls: black carries most of the default landing experience, white creates a proof interlude and #a9a498 supports an editorial chapter. Saturated orange, pink and lime live inside images rather than button fills.
- Actions are fine outlines rather than blocks: 45px-high pills with 1px current-color borders, 8px 28px padding and 19px light text; compact category pills are 31px high.
- Proof is staged as artwork: large square-edged media, paired 669px-wide project panels with 16px gutters, same-size title and gray outcome line. Include a strong designed media montage; when no finished campaign exists, compose product details and human-use photography into an equally bold visual panel.
- Editorial proof has its own stone-colored gallery: 70.4px light heading, three columns of square images, white vertical hairlines and small 12px uppercase olive labels. Carry this device into a new page as a news, insight or evidence gallery.
- The closing stays conversational and architectural: black footer with a 36.1px invitation in a narrow left column, link columns in the middle and an underlined mailing-list field at right, separated from lower trust notes by 96px.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Editorial stone | `#a9a498` | `--color-stone` | background, text, border | Default editorial gallery background; muted oversized next-project link on off-white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-black` | background, text, border, action | Default landing canvas, inverse text on white chapters and dark outlines. |
| Muted olive | `#4e5449` | `--color-olive` | text, background | Small category labels on stone; full capability chapters on service-led pages. |
| Secondary gray | `#666666` | `--color-gray` | text | Outcome captions, footer labels and lower-priority footer notes. |
| Gallery white | `#ffffff` | `--color-white` | text, background, border, action | Type and hairlines on dark chapters; full-width proof and editorial-page canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| culture pages | Culture navigation charcoal | `#4e4e4e` | `--color-nav-charcoal` | text | Name and Menu on the culture-page white canvas. |
| light portfolio and service pages | Light-page navigation gray | `#8a8a8a` | `--color-nav-gray` | text | Name and Menu on light portfolio and service pages. |
| service-led pages | Capability beige | `#dddcd6` | `--color-beige` | background | Flat backing for a detailed capability matrix. |
| case studies and media panels | Warm off-white | `#f4f5ef` | `--color-off-white` | surface, background | Media backing and related-project closing band. |

## Typography

- **Scto Grotesk A** — All marketing typography, navigation, labels and actions. A clean contemporary grotesk with open counters, substantial x-height and a notably light default weight; personality comes from scale and line breaks rather than multiple families. If unavailable, use **Inter**. Use weight 300 for the main voice, 500 for labels; retain the tight headline tracking. Font stack: "Scto Grotesk A", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Scto Grotesk A | 300 | 70.4px | 1.1 | -0.035em | size calc(-12.1px + 2.25rem + 3.22581vw) | Default manifesto heading, editorial gallery heading and oversized continuation link. |
| heading | Scto Grotesk A | 300 | 36.1px | 1.25 | -0.03em | size calc(-4.3px + 1.5rem + 1.13636vw) | Section headings, project names and paired outcomes, story leads and footer invitation. |
| card-heading | Scto Grotesk A | 300 | 28px | 1.2 | -0.02em | size calc(-3.2px + 1.1875rem + 0.847458vw) | News titles, journal titles and case-study explanatory paragraphs. |
| navigation | Scto Grotesk A | 300 | 20.4px | 1.5 | normal | fixed | Small name and Menu in the fixed header. |
| body | Scto Grotesk A | 300 | 19px | 1.5 | -0.02em | fixed | Body paragraphs, direct contact link and footer navigation. |
| button | Scto Grotesk A | 300 | 19px | 1.4 | normal | fixed | Outlined calls to action. |
| footer-label | Scto Grotesk A | 500 | 14px | 1.375 | -0.027em, uppercase | fixed | Footer contact, navigation and mailing-list column labels. |
| eyebrow | Scto Grotesk A | 500 | 12px | 1.375 | normal, uppercase | fixed | News category and compact chapter labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| editorial pages, testimonials and case studies | editorial-display | Scto Grotesk A | 300 | 50.5px | 1.2 | -0.035em | size calc(-7.2px + 1.875rem + 1.92308vw) | White-canvas page openings, centered testimonial and case-study service-summary heading. |
| portfolios and case studies | category | Scto Grotesk A | 300 | 19px | 1.5 | -0.025em | fixed | Compact project taxonomy and filter pills. |
| numbered capability and principle lists | number | Scto Grotesk A | 500 | 19px | 1.5 | -0.02em | fixed | Numeral centered inside black circular markers. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the principal voice at weight 300, including card titles and actions; medium weight is reserved for uppercase labels and numbered markers.
- Tracking tightens with scale: body -0.02em, section headings -0.03em, large displays -0.035em. Do not create hierarchy by making the biggest headline bold.
- Project title and outcome use the same heading recipe; color, not size or weight, distinguishes the outcome.
- For culture-page principle rows, the 36.1px heading becomes weight 400; this is a scoped emphasis, not the default heading weight.

## Layout

**Density:** Airy: long unoccupied bands frame concise text, while media fills wide grids without padded card shells.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small category-to-title gaps and button vertical padding. |
| 16px | Main grid gutter and footer label-to-content separation. |
| 20px | Intro paragraph-to-action gap and wrapped-list gaps. |
| 24px | Project image-to-title and footer invitation-to-email separation. |
| 28px | Journal image-to-heading gap and action horizontal padding. |
| 32px | Numbered row top padding and logo-grid horizontal gap. |
| 40px | Section-heading-to-journal-grid separation and number-to-title gap. |
| 43.2px | Desktop side gutter at 1440px; follows a 3% container inset. |
| 56px | Numbered row bottom padding. |
| 64px | Short chapter and journal-band vertical padding. |
| 96px | Default major-chapter vertical padding and footer upper-to-lower-row gap. |
| 112px | Footer top and bottom padding; large portfolio row gaps. |
| 128px | Deep breathing space in capability summaries and testimonial introductions. |
| 280px | Desktop text-opening top padding. |

### Containers and grids

- **main container**: max width 1900px · side padding 43.2px. Centered outer container with 3% side insets at desktop; visible content width is 1354px at 1440px.
- **structural grid**: 12 columns · gap 16px. Primary alignment system; opening copy spans eight columns, media commonly spans six, case-study body copy occupies the right six.
- **project pairs**: 2 columns · gap 16px. Two large portrait-leaning image panels, each 669px wide at desktop; 112px between rows.
- **journal grid**: 3 columns · gap 16px. Three equal articles with 441px-wide landscape media and no enclosing boxes.
- **opening text measure**: max width 902px. Left-aligned promise occupying roughly two thirds of the available width.
- **body measure**: max width 400px. Right-aligned descriptions in numbered rows.
- **logo grid**: 6 columns · gap 32px. Monochrome proof marks on white, each held within a 199px by 68px image area.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 9999px (pill) |
|  | media panels | 0px |
| numbered capability and principle lists | number markers | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default landing canvas and universal closing surface.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Flat uninterrupted black; media and type do the work, without shadows or raised panels.

**Transfer:** Use across the main promise and demonstrations so bright assets feel self-lit.

#### White gallery · level 0

**Use:** Proof interlude and light editorial-page canvas.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** An abrupt full-width tonal change rather than a floating white card.

**Transfer:** Use as a distinct evidence or explanation chapter.

#### Stone editorial band · level 0

**Use:** Expanded news and insight gallery.

**CSS:** `background: #a9a498; color: #ffffff; padding: 96px 0`

**Observed:** White hairlines divide columns; small olive categories sit beneath square media.

**Transfer:** Give editorial proof a warmer register without adding a saturated UI accent.

#### Off-white continuation · level 0

**Only for:** case-study summaries

**Use:** Capabilities delivered and next-item navigation.

**CSS:** `background: #f4f5ef; color: #000000; padding: 128px 0`

**Observed:** A flat warm closing chapter; its oversized continuation text is stone colored.

**Transfer:** Use after immersive demonstrations to return to practical details.

#### Olive capability band · level 0

**Only for:** service-led pages

**Use:** Breadth-of-expertise chapter.

**CSS:** `background: #4e5449; color: #ffffff`

**Observed:** A subdued green-gray full-width field with white horizontal rules and large list labels.

**Transfer:** Reserve for a long capability list rather than use as a general accent color.

#### Beige capability matrix · level 0

**Only for:** service-led pages

**Use:** Detailed categories and service lists.

**CSS:** `background: #dddcd6; color: #000000`

**Observed:** Flat stone-like neutral with thin black rules; category text sits in the middle and right thirds, leaving a strong empty left rail.

**Transfer:** Use a ruled matrix for detailed offerings instead of icon cards.

## Components

### Minimal header

**Use:** Persistent identity and navigation entry.

**CSS:** `position: fixed; z-index: 30; width: 100%; padding: 43.2px 0; color: #ffffff`

**Text style:** `navigation` — Scto Grotesk A 300 · 20.4px/1.5

**Observed:** Small text identity at left and a single Menu control at right within the main container. No visible filled bar or row of desktop links. Light-page variants use navigation gray or culture charcoal.

**Transfer:** Keep the new identity typographic and navigation compressed into one entry.

### Outline action

**Use:** Primary and editorial calls to action.

**CSS:** `display: inline-block; background: transparent; color: #ffffff; border: 1px solid #ffffff; border-radius: 9999px; padding: 8px 28px; text-align: center`

**Text style:** `button` — Scto Grotesk A 300 · 19px/1.4

**Observed:** A slim capsule whose width follows its label. White-canvas versions invert both text and border to black; actions remain visually lighter than nearby headings.

**States:** Declared: hover background #ffffff and color #000000; light variant hover background #000000 and color #ffffff.

**Transfer:** Use short plain-language labels and preserve the outline as the resting state.

### Project panel

**Use:** Large visual proof units in a paired grid.

**CSS:** `position: relative; border-radius: 0px`

**Text style:** `heading` — Scto Grotesk A 300 · 36.1px/1.25 · tracking -0.03em

**Observed:** Square-edged image first, then title, gray outcome at the same scale, then compact taxonomy. Image-to-title gap is 24px. Panels have no filled outer wrapper; imagery can use its own color field.

**Transfer:** Pair an artifact or interface scene with one concrete outcome, rather than stack feature bullets.

### Stone news article

**Use:** Editorial proof inside the Stone editorial band.

**CSS:** `border-right: 1px solid #ffffff; padding: 0 12px 96px`

**Text style:** `card-heading` — Scto Grotesk A 300 · 28px/1.2 · tracking -0.02em

**Observed:** Square media, small uppercase category, light title and Outline action. The division is a vertical rule, not a card border; repeated rows share the same columns.

**Transfer:** Mix project news, independent recognition and useful insights in a single visual register.

### Journal article

**Use:** Compact three-column editorial continuation.

**CSS:** `border-radius: 0px`

**Text style:** `card-heading` — Scto Grotesk A 300 · 28px/1.2 · tracking -0.02em

**Observed:** Landscape image at approximately 12:7, 28px to the title and 24px to an Outline action. The shared section heading includes a rightward arrow. No category label is needed in this compact variant.

**Transfer:** Use useful follow-on reading with images that remain legible as wide thumbnails.

### Footer text link

**Use:** Contact and grouped navigation in the closing chapter.

**CSS:** `display: block; color: #ffffff`

**Text style:** `body` — Scto Grotesk A 300 · 19px/1.5 · tracking -0.02em

**Observed:** Simple stacked text links beneath muted uppercase labels; direct email sits below the invitation.

**States:** Declared: hover opacity 0.8 for navigation; email hover underline.

**Transfer:** Separate site navigation, related destinations and social links into distinct narrow columns.

### Mailing list field

**Use:** Quiet subscription action in the footer's right third.

**CSS:** `background: transparent; border-bottom: 1px solid #ffffff; border-radius: 0px; padding: 12px 0; width: 100%`

**Observed:** A single underlined input with a small right-facing submit arrow; the uppercase label sits above it. No surrounding form panel or filled submit button.

**Transfer:** Keep this secondary conversion integrated into the footer grid, not a separate promotional card.

### Category pill

**Only for:** portfolios and case studies

**Use:** Project classification and filtering.

**CSS:** `display: inline-block; color: #000000; border: 1px solid #000000; border-radius: 9999px; padding: 0 16px; overflow: hidden`

**Text style:** `category` — Scto Grotesk A 300 · 19px/1.5 · tracking -0.025em

**Observed:** Compact 31px pills, grouped horizontally; selected filter is black with white text. On dark galleries the outline and label reverse to white.

**States:** Declared: hover background #000000 and color #ffffff.

**Transfer:** Use a small taxonomy that helps browse evidence, not a badge on every paragraph.

### Numbered row

**Only for:** capability and principle chapters

**Use:** Explain a short series without boxed feature cards.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; gap: 20px; border-top: 1px solid #000000; padding: 32px 0 56px`

**Text style:** `body` — Scto Grotesk A 300 · 19px/1.5 · tracking -0.02em

**Observed:** Black circular numeral at left, large title beside it and a short description at far right, limited to 400px. The number and title group has a 40px gap.

**Transfer:** Use for a small number of substantial principles or offerings.

### Number marker

**Only for:** capability and principle chapters

**Use:** Anchor each numbered row.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 48px; height: 48px; border-radius: 9999px; background: #000000; color: #ffffff`

**Text style:** `number` — Scto Grotesk A 500 · 19px/1.5 · tracking -0.02em

**Observed:** A solid disk with one medium-weight numeral; no illustration or decorative stroke.

**Transfer:** Keep numbering sequential and visually smaller than the row title.

## Imagery and graphics

### Designed media stage

**Use:** Large lead demonstration and repeated project panels; a defining device of the default landing style.

**Observed:** A wide reel moves between finished visual identities and digital experiences. Bold typography, photographic cutouts, interfaces and archival fragments sit on purposeful black, off-white or saturated project-colored backings. Panels are square-edged and occupy far more area than explanatory copy.

**Transfer:** Produce an art-directed montage from actual product views, physical artifacts and human-use photography. Minimum version: one strong interface on a contrasting flat backing paired with a close detail and a typographic brand fragment, not a generic laptop floating on a gradient.

**Build:** Use a full-width media canvas around 1440px by 1000px. Within it, place a sharp rectangular demonstration with roughly 10% inset on a flat neutral or product-colored backing. For collage scenes, anchor one dominant image at center and layer 4–6 smaller photographic or interface fragments at differing sizes with slight rotation; let some overlap the composition edges. Keep the UI outside the artwork monochrome.

### Human story film

**Use:** Split story chapter on black.

**Observed:** Candid close portraits in ordinary working spaces, soft natural light and subdued warm-gray color. A nearly square film fills the left half while text sits on the right. Faces and foreground shoulders create intimacy rather than corporate staging.

**Transfer:** Film or photograph people actually using or making the product; preserve real environments, mild background softness and natural expressions.

### Monochrome proof wall

**Use:** White social-proof interlude.

**Observed:** A six-column by four-row field of black client marks, widely spaced and optically balanced on white; short label and heading above.

**Transfer:** Use authorized partner or customer marks, normalized by perceived visual weight rather than stretched to identical dimensions.

### Editorial thumbnail collection

**Use:** Stone news gallery and black journal band.

**Observed:** Square gallery images and landscape journal thumbnails mix photographic portraits, designed award objects, colorful identity artwork and abstract digital imagery. Original color remains intact; backing is chosen per image, not globally tinted.

**Transfer:** Use relevant artifacts and original editorial images, with enough negative space or a strong central subject to survive the smaller format.

### Immersive case-study demonstrations

**Only for:** case studies

**Use:** Long-form proof alternating with white text chapters.

**Observed:** Large desktop interfaces on charcoal or pale backing alternate with split image pairs, black-and-white archival photography and device views on white. A circular image aperture appears in the demonstrated experience; this belongs to the project artwork, not the studio's global UI.

**Transfer:** Show both the product in use and close details. Let the demonstrated product retain its own visual system, while the surrounding page keeps the light grotesk, white margins and right-hand commentary.

### Culture photo juxtaposition

**Only for:** culture pages

**Use:** A visual pause between principles and recruitment copy.

**Observed:** A tall natural-color photograph of food and outdoor gathering at left, with a smaller stack of candid social photographs centered vertically at right on white. The unequal scales and large gaps feel editorial rather than tiled.

**Transfer:** Choose a tactile detail and an authentic group moment relevant to the new team. Keep a tall dominant image against a smaller layered pair.

**Build:** Use two equal layout columns with 16px gutter; fill the left with one tall image. Center a narrower landscape pair in the right column; place the rear image slightly wider and offset behind the foreground image. Use square edges and no added drop shadow.

### Icons

**Observed:** Sparse filled arrow SVGs: 20px in small actions and mailing-list submission, 36px beside the journal section link. Black or white follows the chapter contrast.

**Transfer:** Use a plain directional arrow where movement is implied; do not introduce a library of feature pictograms.

## Section recipes

How recurring sections are built.

### First screen: Manifesto and media opening

**Observed:** Black stage behind a Minimal header, with small identity and Menu at opposite edges. The display statement starts after 280px of open space, sits at the left container edge and spans roughly eight of twelve columns. At desktop it is 70.4px/1.1, weight 300, with four loose sentence lines and substantial empty space at right. The text chapter ends at 654px; the upper part of an edge-to-edge Designed media stage is visible within the first 900px. Supporting studio description and Outline action occur after the media, below the first screen; there is no hero button cluster.

**Transfer:** Give a different product one confident sentence with similarly deliberate line breaks, then a designed demonstration that can carry the emotional color. Without a showreel, use the montage recipe. Editorial pages instead open on white with editorial-display at the same 280px top offset; a case study can open with full-bleed media before revealing its proposition.

**Avoid:** Do not center the promise over a background image or pull a bright conversion button and feature cards into the opening; this destroys the text-first pause and the subsequent visual reveal.

**Text style:** `display` — Scto Grotesk A 300 · 70.4px/1.1 · tracking -0.035em

### Paired proof gallery

**Observed:** Project panel components form two columns on Black stage, with 16px gutters and generous 112px row spacing. Images dominate; the heading and gray outcome sit directly below each image before the small category pill. The final row can remain intentionally unpaired.

**Transfer:** Use a sequence of demonstrations or customer outcomes sized as visual work, allowing an odd final item rather than forcing a filler.

### White proof interlude

**Observed:** White gallery provides a sharp tonal break. A compact uppercase label and light heading precede the Monochrome proof wall; the desktop arrangement is six columns with 32px gaps.

**Transfer:** Use compact external proof between visual demonstrations and human explanation; avoid making every proof item a separate card.

### Split human story

**Observed:** Human story film on the left at roughly half the content width; on the right a small uppercase label, light multi-line heading, short body and Outline action. Black stage and 96px vertical padding make the film and text feel like one chapter.

**Transfer:** Explain the people, process or belief behind the product using an intimate visual and one clear idea rather than a feature inventory.

### Stone editorial gallery

**Observed:** Stone editorial band carries a display heading followed by three columns of Stone news article components. A thin white horizontal introduction rule and vertical article dividers organize the gallery. A centered text-only expansion action follows the final row.

**Transfer:** Use this signature gallery for insights, milestones or proof artifacts; the number of rows should follow the material, not a fixed sequence.

### Journal and conversational close

**Observed:** A black journal band uses a heading with right arrow, three Journal article components and 64px vertical padding. The shared black footer follows with 112px padding: invitation in the left three columns, grouped links across the middle five and Mailing list field in the right four. Upper and lower rows are separated by 96px; subdued notes sit below. The expanded editorial landing variant transitions directly from stone news to this footer without repeating the compact journal band.

**Transfer:** End with useful continuation and a human invitation. Keep contact, navigation and subscription visible as parts of the same architectural grid rather than adding an oversized sales banner.

### Ruled capability chapters

**Only for:** service and culture pages

**Observed:** On White gallery, a 12px uppercase chapter label precedes Numbered row components. Service pages extend into Olive capability band with 36.1px list items and 28px row padding, then Beige capability matrix with paired detailed lists across the middle and right thirds.

**Transfer:** Make a compact set of meaningful offerings, then use the olive list for breadth and the beige matrix for detailed taxonomy only when the content warrants those layers.

### Centered testimonial

**Only for:** service-led pages

**Observed:** White gallery with 128px top padding; centered uppercase attribution above a 50.5px/1.2 light quote, approximately 1128px wide, followed by a black-outline action 40px below.

**Transfer:** Use a real customer statement with enough substance to span several balanced lines; keep the attribution small and let the quote carry the section.

**Text style:** `editorial-display` — Scto Grotesk A 300 · 50.5px/1.2 · tracking -0.035em

### Case-study visual essay

**Only for:** case studies

**Observed:** Full-bleed media opening, white proposition and metadata chapter, then alternating full-width or inset demonstrations with commentary confined to the right half. Commentary uses heading or card-heading rather than dense small body. A ruled strategy chapter pairs a heading at left with three arrow-led explanations at right.

**Transfer:** Sequence visual evidence and the decisions behind it. Vary full-width demonstrations with paired detail scenes while keeping prose aligned to the same right rail.

### Case-study continuation

**Only for:** case studies

**Observed:** Off-white continuation contains a large service-summary heading, ruled service lists and Outline action; an oversized stone next-project link centers below. The page then returns to the black journal band and shared footer.

**Transfer:** After the emotional proof, summarize the practical contribution and offer one clearly related next example.

## Page flow

**Storyline:** Promise → visually immersive proof → credibility and human context → editorial continuation → conversational contact.

### Default studio or product landing page

1. **Promise** — Light manifesto on black with a deliberately delayed action.
2. **Product demonstration** — Full-width reel followed by a concise explanation and paired visual proof gallery.
3. **Social proof** — White monochrome mark wall.
4. **Human context** — Split candid film and belief-led story.
5. **Editorial proof** — Expanded stone-colored news gallery.
6. **Closing call** — Black contact invitation, grouped links and mailing-list line.

**Transfer:** Let the product's demonstrations supply the visual richness; keep the landing interface neutral and spare.

### Long-form case study

1. **Immersion** — Full-screen visual teaser before text.
2. **Context** — White proposition, category and metadata.
3. **Demonstration and explanation** — Alternating expansive demonstrations and right-rail commentary.
4. **Strategic reasoning** — Ruled two-column explanation with arrow-led points.
5. **Practical summary** — Off-white contribution list and related-project continuation.
6. **Closing call** — Compact black journal band then shared contact footer.

**Transfer:** Use a visual essay to explain a product transformation rather than a uniform succession of feature cards.

### Browsable proof collection

1. **Positioning** — White text-led introduction.
2. **Navigation** — Ruled filter bar with compact pills.
3. **Proof collection** — Two-column visual projects with same-scale gray outcome lines.
4. **Continuation** — Centered Show More text action.
5. **Closing call** — Black journal band and shared contact footer.

**Transfer:** Keep the collection visually generous and the filtering quiet; evidence imagery should lead browsing.

### Explain capabilities and earn an inquiry

1. **Promise** — White statement and black-outline action.
2. **Capability explanation** — Numbered horizontal rows.
3. **Breadth** — Olive ruled list.
4. **Detail** — Beige category matrix.
5. **Social proof** — Centered light-weight customer quote.
6. **Closing call** — Black journal band and shared contact footer.

**Transfer:** Move from a few clear offerings to broader expertise and detailed delivery, using tonal chapters rather than individual feature cards.

### Humanize an organization and support recruitment

1. **Belief** — White concise opening statement.
2. **Credibility** — Multi-column narrative with a right-hand stack of outlined links.
3. **Human context** — Black split film and story chapter.
4. **Principles** — Numbered ruled rows on white.
5. **Culture** — Asymmetrical candid photo juxtaposition.
6. **Invitation** — Right-aligned recruitment copy and outline action.
7. **Closing call** — Black journal band and shared contact footer.

**Transfer:** Pair a brief belief with real history and lived culture; use the same visual discipline as the product-facing pages.

## Writing

Confident and culturally literate without sounding remote. Ambition is paired with human warmth; the language moves comfortably between making things, practical outcomes and future-facing belief.

**Do not copy:** Do not reuse the studio's name, project identities, artwork, client marks, awards, founding history, audience numbers, quotes or claims. Replace them with the new organization's authorized assets and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The organization speaks as we; you and your appear when explaining value or inviting participation. Contact language is direct and personal rather than procedural.
- **Rhythm:** Long sentence-led promises contrast with short emphatic fragments. Paragraphs are concise but substantive, while actions usually take two to five words. Headings use sentence case; uppercase is reserved for tiny structural labels.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Connect a future-facing ambition to active making verbs and a human outcome. | 12–22 words | “We help brands imagine and build digital products and experiences that people truly love.”<br>“We believe a better future happens by design. We're leading it.” |
| Outcome caption | A compact transformation statement beneath the project identity. | 3–12 words | “Honouring the past. Amplifying the present.”<br>“A new digital home for a global icon.” |
| Action | Plain invitation or directional next step, not a pressure tactic. | 2–5 words | “See what we do”<br>“Get in touch”<br>“Read more” |
| Closing invitation | An optimistic shared horizon expressed conversationally. | 6–10 words | “Let's peer over the horizon together” |
| Capability explanation | Name what is made, why it matters and how it feels to use. | 20–40 words | “Your website is your digital flagship. We design and build sites that are intuitive, beautiful and built to perform.” |

**Words and phrasing to use:** imagine; build; evolve; future; people; culture; endure; connect; together; beautiful

**Avoid:** disrupt everything; 10x guaranteed; best-in-class solutions; limited time; revolutionary synergy; click here

**Rules:**

- Prefer active making verbs to strings of abstract service nouns.
- Pair ambitious statements with concrete demonstrations or real outcomes nearby.
- Let warmth appear in invitations and human descriptions, not excessive exclamation marks.
- Use a short outcome beneath a project name rather than repeat the project category as its description.

## Do's and Don'ts

### Do

- Keep the primary display at weight 300 and -0.035em tracking.
- Preserve the 280px desktop top pause before a text-led opening.
- Use the 16px gutter to align media, article columns and footer structure.
- Keep actions outlined with 1px borders and fully rounded ends.
- Put vivid color inside square-edged media while the surrounding canvas stays neutral.
- Give editorial proof a stone band with white hairlines and 12px uppercase categories.
- Keep project names and outcomes at the same 36.1px scale, distinguishing them by color.
- Carry the narrow conversational invitation, link groups and single-line form into the black footer.

### Don't

- Do not replace the light grotesk with a heavy geometric headline face.
- Do not turn the project gallery into rounded shadowed cards; media corners are 0px.
- Do not use olive or project colors as the default CTA fill; resting actions are transparent.
- Do not compress the broad 96px chapter rhythm into a dense dashboard layout.
- Do not put icon illustrations beside every offering; numbered lists use 48px black disks.
- Do not shrink outcome captions to small metadata while leaving the project title oversized.
- Do not restyle the mailing-list input as a boxed white form on black.
- Do not treat the demonstrated product's circular apertures or condensed logo lettering as the global marketing system.

## Motion and responsive

### Motion

**Observed:**

- Outlined actions declare 0.3s transitions with cubic-bezier(0.4, 0, 0.2, 1); their hover state swaps background and text contrast.
- Footer navigation declares 0.15s transitions and hover opacity 0.8.
- Editorial articles declare 0.5s transitions with vertical reveal transforms and opacity changes.
- Large media scenes use video; the header has a declared transform transition.

**Transfer:**

- Let media provide the expressive movement while navigation and actions retain restrained contrast changes.
- Reveal visual proof as coherent panels rather than animating every word or adding decorative bouncing controls.

**Unknown:**

- Exact media choreography, scroll thresholds and header hide/show logic.
- Focus-visible and active appearance beyond the declared hover rules.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1792px.
- Container classes use 6% horizontal padding below the medium breakpoint and 3% above it.
- Text-led opening classes use 240px top padding below medium and 280px above; opening copy expands from full width to ten and then eight of twelve columns.
- Numbered row titles switch from vertical to horizontal grouping at medium; expanded news moves from one column to three. Compact journal grids declare two columns before three at the large breakpoint.

**Transfer:**

- Retain the text-first pause and media reveal on small screens, using the fluid display formulas rather than a fixed desktop font size.
- Stack the large proof pairs and split story chapters when the outcome lines lose their reading measure; retain sharp media edges and outlined controls.
- Allow the numbered row's description to fall beneath the title while preserving the numeral as its anchor.

**Unknown:**

- Exact rendered mobile line breaks, image choices and menu-open composition.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
