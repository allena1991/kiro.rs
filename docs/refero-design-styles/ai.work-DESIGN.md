# ai.work — alpine operational theater

## Overview

A dark enterprise style that pairs cinematic alpine light with restrained, warm-gray grotesk typography and tiny machine-like labels. Atmospheric landscape imagery gives way to low-contrast interface diagrams, thin-edged cards and spacious technical chapters. It suits ambitious software and infrastructure products that need both emotional scale and operational credibility, with sparse editorial composition around denser demonstrations.

### Essentials

- The promise has two tonal registers: regular 64px/1 grotesk with -0.02em tracking, warm #d4d0c9 for the introduction and a 60%-opacity continuation; the final invitation expands to 96px/1.
- A landscape becomes a product theater: an 8px-inset, 8px-radius photographic stage starts beneath a 64px navigation zone, with centered text above a compact 504px-wide working interface. Preserve atmospheric photography even when the product must be represented by a simple task-to-result diagram.
- Controls stay smaller than the ambition: conversion buttons are 40px-high warm-gray pills with 15px/20px medium text; navigation uses separate 32px-high, 4px-radius tabs rather than oversized pills.
- Color is a signal, not a page theme: #141414 and warm-gray translucent layers dominate the long page; green, blue, orange and violet are confined to 10px mono chips, thin proof markers and segmented performance marks. Full-color photography is reserved for the main stage and editorial thumbnails.
- Technical proof looks like lightly illuminated equipment: 1px translucent edges, 8px card corners, 24px padding and gutters, dark process diagrams, plus tiny 10px uppercase mono labels in 16px-high chips.
- The ending becomes a typographic object: numbered footer links occupy the right while a small symbol holds the left, above a warm-gray wordmark artwork spanning the viewport minus 48px and approximately 363px tall at desktop. Use the new identity at monumental scale, not merely a conventional footer logo.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Learning blue | `#00a8f0` | `--color-blue` | text, accent | Small chapter labels and proof markers. |
| Automation orange | `#ff9634` | `--color-orange` | text, accent | Small chapter labels and proof markers. |
| Execution green | `#1fe274` | `--color-green` | text, accent | Small chapter labels and proof markers. |
| Performance violet | `#a454ff` | `--color-performance` | accent | Active segmented performance bars; not a general button color. |
| Conversation violet | `#cf70ff` | `--color-violet` | text, accent | Small chapter labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm mineral text | `#d4d0c9` | `--color-text` | text, action | Headings, main body copy and primary button fill. |
| Near-black canvas | `#141414` | `--color-canvas` | background, text | Main background and dark text on the light conversion button. |
| Navigation glass | `#151515` | `--color-nav-glass` | surface | Visible #242424 at 7% opacity over the canvas; default navigation backing. |
| Mineral panel | `#1c1c1b` | `--color-panel` | surface | Visible warm mineral 4% wash over the canvas; large bands and subtle tiles. |
| Mineral hairline | `#232322` | `--color-edge` | border | Visible warm mineral 8% edge over the canvas; 1px dividers and card outlines. |
| Mineral chip | `#272726` | `--color-chip` | surface | Visible warm mineral 10% wash over the canvas; label chips and small dark controls. |
| Inactive performance marks | `#444443` | `--color-graph-inactive` | accent | Inactive bars within segmented performance proof. |
| Technical gray | `#615f5c` | `--color-muted` | text | Visible result of warm mineral at 40% opacity over the canvas; footer indices and metadata. |
| Secondary mineral | `#878581` | `--color-secondary` | text | Visible result of warm mineral at 60% opacity over the canvas; second headline clauses and secondary descriptions. |
| Link hover white | `#ffffff` | `--color-white` | text | Footer navigation hover and bright diagram details. |

## Typography

- **NB International Pro** — All marketing prose, headings and controls; Light, Regular and CG Medium cuts form one visual family. Understated contemporary grotesk with open shapes and closely fitted spacing; regular display, light body, medium controls. If unavailable, use **Inter**. Use 300, 400 and 500; retain the tight tracking and check headline wraps. Font stack: "NB International Pro", "Inter", Arial, sans-serif.
- **NB International Pro Mono** — Uppercase chips, technical captions, indices and dates. Small, utilitarian monospaced markings with normal tracking. If unavailable, use **IBM Plex Mono**. Font stack: "NB International Pro Mono", "IBM Plex Mono", ui-monospace, monospace.
- **Inter** (only for product demonstrations) — Interface conversations and action rows, distinct from the marketing text. Compact, neutral interface sans. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | NB International Pro | 400 | 96px | 1 | -0.02em | Monumental closing invitation, mixing full-tone and secondary-tone clauses. |
| display | NB International Pro | 400 | 64px | 1 | -0.02em | Default first-screen headline and large centered section statements. |
| testimonial | NB International Pro | 300 | 64px | 1 | -0.02em | Centered, full-width customer quotation. |
| heading | NB International Pro | 400 | 32px | 1.25 | -0.02em | Left-aligned section leads and narrative feature chapters. |
| card-heading | NB International Pro | 400 | 24px | 32px | -0.02em | Benefit cards and compact editorial section titles. |
| feature-heading | NB International Pro | 400 | 20px | 1.2 | -0.02em | Technical feature-grid titles. |
| body | NB International Pro | 300 | 16px | 1.5 | -0.02em | Main paragraphs, support lines and footer navigation. |
| editorial-title | NB International Pro | 400 | 16px | 1.5 | -0.02em | Article titles and person names. |
| button | NB International Pro | 500 | 15px | 20px | -0.02em | Primary conversion control; use the CG Medium cut when available. |
| body-small | NB International Pro | 300 | 14px | 24px | -0.02em | Technical feature explanations. |
| navigation | NB International Pro | 400 | 14px | 16px | normal | Small top navigation tabs. |
| eyebrow | NB International Pro Mono | 400 | 10px | 9px | normal, uppercase | Text inside compact rounded category chips. |
| caption | NB International Pro Mono | 400 | 10px | 1.2 | normal, uppercase | Unbacked card labels, numbered groups, dates and technical annotations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| compact platform landing pages | platform-display | NB International Pro | 400 | 48px | 1.1 | -0.02em | Left-aligned headline beside a compact product object. |

**Notes:**

- Use the Light cut for paragraph texture, not a smaller version of the heading weight. Display and headings remain 400, with no bold emphasis.
- The sans system holds -0.02em tracking across sizes; mono captions use normal tracking rather than widely spaced luxury lettering.
- Headline hierarchy comes from size, line breaks and opacity. A secondary clause stays the same size as its primary clause.
- The giant footer identity is vector artwork fitted to width, not the 96px text recipe.

## Layout

**Density:** Airy narrative spacing surrounds compact controls and information-rich product diagrams.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Outer inset for full-width rounded stages; small footer-link gaps. |
| 10px | Small control and icon grouping gaps. |
| 16px | Card label-to-title spacing and compact content groups. |
| 24px | Default content gap, grid gutter and card padding. |
| 48px | Feature copy-to-illustration separation. |
| 56px | Section introduction-to-content gap. |
| 64px | Top navigation zone and generous action separation in the closing invitation. |
| 112px | Standard major-section vertical padding. |
| 160px | Large narrative-band and closing-section vertical breathing room. |

### Containers and grids

- **page shell**: max width 1920px · side padding 8px. Nearly full-bleed rounded stages inside a thin dark page rim.
- **main container**: max width 1032px · side padding 24px. Centered narrative and grid content; at 1440px the content begins around 204px from the left.
- **section introduction**: max width 504px. Half-width left-aligned heading and supporting paragraph within the main container.
- **feature grid**: max width 1032px · 3 columns · gap 24px. 328px-wide modules, with selected technical stories spanning two columns.
- **footer span**: side padding 24px. Near-full-width identity artwork and legal row; link columns align to the right.
- **benefit grid** (only for compact platform landing pages): max width 1032px · 2 columns · gap 24px. 504px-wide cards in a two-by-two arrangement.
- **editorial column** (only for company and people pages): max width 680px. Narrow left-aligned prose and photography; three portrait columns fit inside it.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | stages and cards | 8px |
|  | navigation tabs | 4px |
|  | conversion pills and chips | 100px |
| product demonstrations | foreground interface panels | 16px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page foundation.

**CSS:** `background: #141414`

#### Mineral band · level 1

**Use:** Long capability chapters and technical grids.

**CSS:** `background: rgba(212, 208, 201, 0.04); border: 1px solid rgba(212, 208, 201, 0.04); border-radius: 8px`

**Observed:** Only a slight warm lift separates the band from the page; it remains a broad field rather than a visibly elevated white card.

**Transfer:** Group a family of related capabilities in one low-contrast field.

#### Gradient card · level 1

**Use:** Benefit and skill cards.

**CSS:** `background: linear-gradient(rgba(212, 208, 201, 0) 0%, rgba(212, 208, 201, 0.04) 100%); border-radius: 8px; border-top: 1px solid rgba(212, 208, 201, 0.08)`

**Observed:** The top blends into the background while the lower copy area receives a slightly brighter wash.

**Transfer:** Keep the illustration or process above the title; use a divider to distinguish supporting detail.

#### Technical outline · level 2

**Use:** Feature modules inside Mineral band.

**CSS:** `background: transparent; border: 1px solid rgba(212, 208, 201, 0.08); border-radius: 8px`

**Observed:** An edge, not a shadow, defines each module.

**Transfer:** Use for diagrams and explanations that belong to the same technical layer.

#### Photographic stage · level 1

**Use:** Atmospheric first-screen media.

**CSS:** `border-radius: 8px; overflow: hidden; background: linear-gradient(rgba(20, 20, 20, 0) 0%, rgba(20, 20, 20, 0.4) 100%)`

**Observed:** A dark lower veil binds the landscape into the page; the image itself carries muted amber sunlight and deep green terrain.

**Transfer:** Place the gradient over cover-fit photography and beneath headline and interface layers.

## Components

### Navigation rail

**Use:** Persistent compact site orientation.

**CSS:** `height: 48px; padding: 8px 16px; background: rgba(36, 36, 36, 0.07); border-radius: 8px; backdrop-filter: blur(6px); display: flex; gap: 10px`

**Observed:** Inset from the page edges and fixed above the content. A small identity sits left; two compact tabs and a simple symbol sit right. On dark scrolled content the glass reads more strongly.

**Transfer:** Keep the identity and route choices small enough that the media stage remains dominant.

### Navigation tab

**Use:** Top-level route choices.

**CSS:** `background: rgba(212, 208, 201, 0.04); color: #d4d0c9; padding: 8px 12px; height: 32px; border-radius: 4px; backdrop-filter: blur(6px)`

**Text style:** `navigation` — NB International Pro 400 · 14px/16px

**Observed:** Adjacent individual rectangular tabs, not one enclosed segmented control.

### Primary button

**Use:** Direct conversion at the closing invitation and compact platform opening.

**CSS:** `background: #d4d0c9; color: #141414; padding: 10px 30.5px; height: 40px; border-radius: 100px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — NB International Pro 500 · 15px/20px · tracking -0.02em

**Observed:** Text-only pill with medium-weight label. The compact platform variant pairs it with a dark secondary action; the cinematic opening instead lets the product interface dominate.

**Transfer:** Use one concise request verb; let the label determine width.

### Category chip

**Use:** Section eyebrows and semantic chapter markers.

**CSS:** `background: rgba(212, 208, 201, 0.1); color: rgba(212, 208, 201, 0.6); padding: 3.5px 7.5px; height: 16px; border-radius: 100px`

**Text style:** `eyebrow` — NB International Pro Mono 400 · 10px/9px · uppercase

**Observed:** Tiny labels sit above headings. Colored chapter variants use green, blue, orange or violet text with a 10% wash of the same hue.

**Transfer:** Assign color to a meaningful chapter category, not to every miscellaneous label.

### Skill card

**Use:** Demonstrate a concrete repeatable capability.

**CSS:** `width: 504px; height: 560px; background: linear-gradient(rgba(212, 208, 201, 0) 0%, rgba(212, 208, 201, 0.04) 100%); border-radius: 8px; display: flex; flex-direction: column; gap: 24px; overflow: hidden`

**Text style:** `card-heading` — NB International Pro 400 · 24px/32px · tracking -0.02em

**Observed:** A process illustration occupies the upper half, followed by mono category, title, divider, muted explanation and a small integration-logo row. Cards continue horizontally beyond the main container; a side index and circular arrow mark the carousel.

**Transfer:** Replace the process with three tangible steps for the new product. For compact platform pages, use 426px-high cards in a two-column grid rather than the horizontal track.

### Feature module

**Use:** Dense but legible technical capability proof.

**CSS:** `width: 328px; height: 416px; padding: 24px; border: 1px solid rgba(212, 208, 201, 0.08); border-radius: 8px; display: flex; flex-direction: column; gap: 48px`

**Text style:** `feature-heading` — NB International Pro 400 · 20px/1.2 · tracking -0.02em

**Observed:** Title and small explanation form the upper group; a restrained diagram or interface vignette sits beneath. Some modules widen across two columns.

**Transfer:** Use one explanatory mechanism per module rather than a generic icon.

### Performance segments

**Use:** Visualize comparative or longitudinal proof.

**CSS:** `width: 4px; height: 32px; background: #a454ff; border-radius: 100px`

**Observed:** Many narrow vertical marks create long horizontal rows. Active violet marks contrast with #444443 inactive marks and very faint outlined marks; a small mono label anchors each row.

**Transfer:** Map filled segments to real measurements and retain the long, instrument-like rhythm.

### Editorial teaser

**Use:** Fresh proof and reading material before the footer.

**CSS:** `width: 328px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `editorial-title` — NB International Pro 400 · 16px/1.5 · tracking -0.02em

**Observed:** Two unboxed article links share a centered 680px row, each with a wide image above a short title and uppercase mono date. Photography here can be much more saturated than the surrounding interface diagrams.

**Transfer:** Use product-relevant reporting or stories, not another grid of sales features.

### Footer link group

**Use:** Secondary navigation in the monumental ending.

**CSS:** `width: 212px; display: flex; flex-direction: column; gap: 8px; color: #d4d0c9`

**Text style:** `body` — NB International Pro 300 · 16px/1.5 · tracking -0.02em

**Observed:** A faint mono number sits above each link group with a larger gap than the link-to-link spacing; two groups sit to the right of an isolated identity symbol. Small social icons sit below.

**States:** Declared: hover color #fff; focus-visible unknown.

**Transfer:** Keep the index and sparse columns even when route names change.

## Imagery and graphics

### Alpine product theater

**Use:** Signature emotional counterweight to the technical page.

**Observed:** A wide mountain valley at low sun: warm light enters from the left, dark ridges rise to the right, green foreground slopes frame the center and cloud or mist softens the distance. The image fills almost the whole opening beneath the navigation. A centered light interface stack floats in front, making the landscape feel like a stage rather than a banner.

**Transfer:** Use an equally expansive, naturally lit landscape with dark foreground and a clear central reading area. For a nonvisual product, place a compact request-to-result interface over it; preserve the scenic light and depth.

**Build:** Use a cover-fit landscape layer in an 8px-radius clipped container. Add a #141414 translucent veil for legibility and the Photographic stage bottom gradient. Place a 504px-wide stack of light rounded interface panels in front, with a small request row, a short action list and an outcome/composer panel. Use soft depth in the photograph rather than synthetic neon glow.

### Dark process miniatures

**Use:** Proof graphics inside Skill card and Feature module.

**Observed:** Dark UI snippets show action rows, a supervisor branching to smaller nodes, dashed connections, a small radial activity symbol and compact approval forms. The diagrams are mostly warm gray with faint fading at the edges; third-party logos are tiny points of color.

**Transfer:** Create a legible diagram of the new product's actual mechanism. The minimum is labeled nodes, an explicit connection and one visible output; it must explain more than a decorative icon.

**Build:** Within a 280px-wide SVG or HTML scene, arrange one left node and three vertically spaced right nodes; connect them with curved dashed paths in rgba(212,208,201,0.3). Use #272726 rounded labels, 10px mono captions and small #d4d0c9 endpoint circles. For action scenes, stack compact dark rows and fade lower rows using a transparent-to-#141414 overlay.

### Monumental identity artwork

**Use:** Signature closing visual on every page type.

**Observed:** An enormous warm-gray lowercase wordmark fills a 1392px by 363px artwork area with 24px side margins at desktop. It follows a field of sparse navigation rather than competing with it.

**Transfer:** Fit the new brand's own wordmark or a typographic rendering of its name into an equally broad artwork region. Preserve the scale relationship to the small links above it.

**Build:** Use an SVG viewBox sized to the chosen lettering, with outlined paths or fitted sans text in #d4d0c9. Scale it to the available width while preserving proportions; tune the viewBox so excess internal whitespace does not shrink the visible letters.

### Warm people photography

**Only for:** company and people pages

**Use:** Opening company image and leadership or board directories.

**Observed:** The lead photograph is a 680px-wide horizontal image of people in a pale architectural interior. Portraits are chest-up, with black clothing and warm beige backgrounds, gently rounded corners and no decorative frames. Names are 16px regular sans; roles are tiny muted uppercase mono, with small social marks aligned beside the name.

**Transfer:** Use consistent lighting, crop and backing for a real team; keep names outside the image. A three-column portrait grid sits within the narrow editorial column.

### Icons

**Observed:** Small filled SVG marks, mostly 16px, 20px and 24px. Simple arrows and monochrome symbols accompany controls; authentic app marks appear in product processes. Technical diagrams use small dots and radial activity shapes rather than a large colorful outline-icon library.

**Transfer:** Use compact monochrome navigation and action glyphs; reserve full-color app logos for actual integrations. Keep icons subordinate to text and process graphics.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product stage

**Observed:** The first screen is a thin dark navigation zone above an almost edge-to-edge rounded photographic stage. The stage starts below 64px, spans the viewport minus 16px and extends to about 984px total page height. Layers run landscape, dark veil, centered headline and support, then a light product interface. The 64px display occupies about two-thirds of the width in two lines near the upper third: the first line is warm mineral and the second is lower contrast. A short centered 16px support line follows with 24px separation. A 504px-wide interface stack anchors the lower center; the landscape remains visible around it. Within the first 900px, navigation, headline, support and the main interface are visible; the stage bottom and subsequent content are below the fold. The opening does not have a prominent filled hero CTA row; a small dark floating demo pill serves the longer scroll.

**Transfer:** Preserve the theater, tonal headline split and compact foreground demonstration for a new landing page. Without a polished demo, build a real three-part task/action/outcome vignette rather than a mock dashboard wall. Compact platform pages instead open with a left-aligned 48px headline, support and paired actions beside a small dark product object in a 544px-high Mineral band. Company pages use a 680px editorial column, 64px heading and wide people photograph.

**Avoid:** Do not replace the stage with a generic centered headline on flat black, a full-width dashboard, or a giant pair of bright conversion buttons.

**Text style:** `display` — NB International Pro 400 · 64px/1 · tracking -0.02em

### Section introduction

**Observed:** A Category chip leads a left-aligned 32px heading and 16px light support line within a roughly 504px measure. The grouping uses 24px gaps; the next major card group begins after 56px. Large transitions use a centered 64px heading and a tiny centered chip.

**Transfer:** Alternate compact left-aligned explanations with occasional centered statements to change narrative pace.

**Text style:** `heading` — NB International Pro 400 · 32px/1.25 · tracking -0.02em

### Proof triptych

**Observed:** A centered large heading introduces three equal, thin-edged cards in the 1032px container with 24px gutters. Each card begins with a short colored vertical rule beside a compact multiline result statement: number and outcome in warm text, contextual continuation in secondary text. A divider separates the spacious upper claim from the smaller explanation below.

**Transfer:** Use three verifiable outcomes, each with its own unit, benefit and explanatory context; retain the narrow color marker rather than coloring the whole card.

### Performance and testimony

**Observed:** A half-width introduction leads long rows of Performance segments across the full main container. A quiet rule separates the chart from a centered uppercase caption, 64px light-weight quotation and smaller attribution. The enclosing rounded region uses 160px vertical breathing room.

**Transfer:** Pair quantitative evidence with one concise human observation. Use an honest comparison or progress measure rather than ornamental random segments.

**Text style:** `testimonial` — NB International Pro 300 · 64px/1 · tracking -0.02em

### Capability chapters

**Observed:** A broad Mineral band contains successive text-and-media stories: 328px-wide text groups pair tiny colored Category chips and 32px headings with larger working interface scenes. The technical overview then uses Feature module in a three-column grid, with some double-width stories.

**Transfer:** Explain a small number of differentiated mechanisms, moving from plain-language benefit to concrete technical proof. Change the number and order to match the product.

### Closing invitation

**Observed:** The default invitation uses a 1032px centered measure, 96px text with a full-tone lead and a secondary-tone continuation, a light 16px support line and Primary button. The section has 156px top and 160px bottom padding. Compact platform pages use a 64px two-tone statement with support and a pill instead.

**Transfer:** End the sales narrative with one direct action and a lower-risk next step, without introducing a new feature list.

**Text style:** `closing-display` — NB International Pro 400 · 96px/1 · tracking -0.02em

### Editorial monumental footer

**Observed:** Two Editorial teaser links in a centered 680px row precede the legal and navigation area. The legal row spans the page; a small symbol sits left and numbered Footer link group columns sit right. A broad field of dark space leads to Monumental identity artwork with 24px side and bottom margins. This same ending follows both product and company narratives.

**Transfer:** Preserve the editorial pair, spare numbered navigation and oversized identity as one recognizable ending, replacing article topics and routes with relevant equivalents.

### People and institutional proof

**Observed:** A narrow 680px editorial column progresses from company photograph and light prose to a stronger 24px mission statement, three-column portrait directories and a three-column set of muted logo tiles. Portrait names use editorial-title and roles use caption. Thin page-wide rules separate major groups before the common footer.

**Transfer:** Use for company or organization stories only; let real people and external affiliations provide proof instead of adding product-style diagrams.

## Page flow

**Storyline:** promise → concrete demonstration → outcome proof → mechanism chapters → technical confidence → closing invitation → editorial bridge → monumental identity

### Flagship marketing narrative combining an emotional promise with concrete operating proof

1. **Promise** — Cinematic product stage with an introductory two-tone headline and working interface.
2. **Capability sampling** — A horizontally continuing row of illustrated Skill cards.
3. **Quantified and human proof** — Centered outcome triptych, segmented performance rows and a large light-weight testimonial.
4. **Mechanism chapters** — Colored micro-labels introduce text-and-media explanations within a long Mineral band.
5. **Technical confidence** — Integration imagery and a thin-edged Feature module grid.
6. **Closing call** — 96px two-tone invitation and one light pill.
7. **Editorial bridge and identity** — Two article teasers, sparse numbered navigation and giant identity artwork.

**Transfer:** Make the scenic opening and monumental ending the anchors; choose intervening proof and mechanism blocks according to the new product's buying questions.

### Company narrative centered on people and institutional trust

1. **Identity and mission** — A narrow editorial opening, wide people photograph, prose and a more emphatic mission statement.
2. **Human proof** — Three-column portrait directories with external name captions and tiny role labels.
3. **Institutional proof** — Muted partner or investor marks in subtle dark tiles.
4. **Editorial bridge and identity** — The same article pair and monumental footer, without a forced product-conversion section.

**Transfer:** Keep the narrower measure and documentary photography for a people-led page; the common footer maintains continuity.

### Compact platform explanation with a direct conversion path

1. **Promise and demonstration** — Split Mineral band: 48px two-tone headline and paired actions left, compact dark product scene right.
2. **Benefit overview** — Two-column gradient cards with plain-language titles and short descriptions.
3. **Technical confidence** — A section introduction and the shared thin-edged technical grid.
4. **Closing call** — Centered 64px two-tone statement, support and light pill.
5. **Editorial bridge and identity** — Shared article pair, numbered footer and large identity artwork.

**Transfer:** Use this scoped opening when the product needs explanation before atmosphere; retain technical depth and the shared ending.

## Writing

Matter-of-fact enterprise confidence with a human product presence. Headlines make direct promises; supporting text explains the actual work and the controls around it rather than piling up adjectives.

**Do not copy:** Do not reuse ai.work, Henry, ServiceNow, source customer identities, portraits, logos, testimonials, acquisition news or unverified numerical claims. All source examples illustrate tone and structure only.

- **Addressing the reader:** Speak to the reader as 'you' or 'your team' when describing effort and results; refer to the product by name or by its functional category. Company prose may use an institutional third-person voice.
- **Rhythm:** Short declarative headlines, often 4–9 words, followed by one explanatory sentence. Feature descriptions are compact but specific; periods and occasional ampersands provide a brisk cadence without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Introduce a named product, then identify its category or consequential job in a second clause. | Two short lines | “Introducing Henry. The first AI Worker for IT” |
| Benefit heading | Combine readiness or speed with a concrete work outcome. | 5–10 words | “Skilled, pre-trained & ready for work.”<br>“Text to resolution” |
| Supporting line | Name the work, then explain a practical result or time to value. | One sentence | “Henry handles core IT work and shows value within days after deployment.” |
| Technical explanation | Explain the mechanism with subject, action and governance or output. | One or two compact sentences | “Work is split across specialized agents, with a supervisor coordinating handoffs to deliver complete outcomes.” |
| Closing invitation | An imperative first clause and a lower-risk starting point in the second. | Two short sentences | “Onboard Henry.”<br>“Start with one ticket type now.” |
| Primary action | A short request verb plus the object of the next step. | 2–4 words | “Request a Demo”<br>“Request access” |

**Words and phrasing to use:** real work; ready for work; handles; connect; execute; learn; under policy; control; visibility; from request to resolution

**Avoid:** magical; revolutionary; supercharge everything; limitless; game-changing; effortless transformation

**Rules:**

- Tie each benefit to an actual task, mechanism or measurable outcome.
- Use technical vocabulary in technical modules, but let introductory headings remain readable without it.
- Reduce perceived commitment in the closing support line with a concrete starting scope.
- Keep labels categorical and terse; reserve full sentences for explanation.

## Do's and Don'ts

### Do

- Use regular 64px/1 headlines and retain the lower-contrast continuation at the same size.
- Keep the main content at 1032px with 24px gutters while scenic bands extend to an 8px page inset.
- Make the foreground demonstration about 504px wide so the landscape remains the dominant field.
- Use 10px uppercase mono labels and preserve the compact 16px chip height.
- Separate technical cards using 1px translucent edges, not elevated shadows.
- Give the final invitation 160px-scale breathing room and let its 96px type carry the emphasis.
- Retain the near-full-width identity artwork after sparse footer navigation.
- Show task-specific diagrams and authentic outputs instead of treating every feature as an icon.

### Don't

- Do not turn the warm #d4d0c9 text into cold pure white across the page; white is a limited detail or hover color.
- Do not spread violet or green into large marketing section backgrounds; chromatic signals remain small.
- Do not use 600–700 weight display headings; weight 400 and opacity establish the hierarchy.
- Do not round technical modules into 24px-radius soft consumer cards; their default corner is 8px.
- Do not add substantial drop shadows to marketing cards; subtle edges define their layers.
- Do not enlarge top navigation to match the 40px conversion pill; its tabs remain 32px high.
- Do not set paragraph copy in mono or use uppercase for sentences; mono belongs to 10px markings.
- Do not compress the ending into a dense conventional sitemap with a tiny bottom logo.

## Motion and responsive

### Motion

**Observed:**

- Declared color transitions use 0.3s cubic-bezier(0.44, 0, 0.56, 1).
- Footer navigation declares white hover text; legal links brighten from 40% warm mineral to full warm mineral.
- The interface illustrations include activity/status representations and carousel navigation.

**Transfer:**

- Use the declared color transition for understated footer-link brightening; preserve the diagrams' information hierarchy if animated states change.

**Unknown:**

- Scroll-reveal timing, carousel movement, activity-loop duration and action focus or active states are not established.

### Responsive

**Observed:**

- Stylesheet width boundaries occur around 810px and 1440px.

**Transfer:**

- For narrow layouts, preserve the scenic stage and compact centered demonstration but fit the interface within the side insets.
- Stack technical and benefit cards when their text measures no longer fit; preserve the contrast between tiny labels and large statements.
- Fit the identity artwork proportionally rather than keeping a fixed desktop height.

**Unknown:**

- Exact mobile font sizes, navigation transformation, column changes and spacing behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
