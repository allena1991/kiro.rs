# Topology — prismatic relief, dark index

## Overview

An immersive, sculptural style that pairs pale iridescent landscapes with a near-black editorial interior. Light grotesk headlines, small technical monospace and fine architectural rules make ambitious ideas feel both imaginative and disciplined. It suits research-led products and frontier technology brands, with sparse copy, monumental imagery and carefully indexed proof rather than dense interface demonstrations.

### Essentials

- The opening is an environment, not a banner: edge-to-edge pearlescent relief fills the 1440×900 first screen, with a two-line light headline anchored low left and a short supporting statement low right.
- Headings act as oversized chapter markers: Magnetik 300 at 120px/0.9 contrasts with 48px/0.9 subheads and tiny 9px uppercase mono descriptors.
- Color belongs to the sculpture, not the interface: cyan, lilac, green and warm spectral fringes appear in the immersive opening and closing artwork; the long reading interior stays #151515 with #e4e2d8 text.
- Actions are unboxed inscriptions: 10.5px lightweight uppercase grotesk with 0.1em tracking, transparent backgrounds and 2.3px bottom padding; no pill-button silhouette.
- Proof looks like a technical specimen index: zero-gap 330×247 logo cells, 12px mono numbers, tiny diagonal arrows and 1px translucent rules rather than raised cards.
- Frames have small detached curved corner brackets: pale 1px quarter-arcs terminate dim straight rules around proof grids, strips and the footer. Carry this device into every new page.
- The artwork returns as a luminous full-screen ending: a pale raised contour mound occupies most of the 900px closing stage while contact, navigation and a return arrow sit in a shallow frame at its foot. A static layered SVG relief is the minimum equivalent when bespoke 3D is unavailable.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Prismatic cyan | `#b7eeef` | `--color-prismatic-cyan` | accent | Soft luminous cyan within the refracted contour edges, paired with lilac, green and warm spectral fringes. Confine this hue to artwork rather than interface controls. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mid gray | `#9b9b9b` | `--color-secondary` | text | Explanatory paragraphs, quotations, indexes and technical descriptors. |
| Charcoal canvas | `#151515` | `--color-canvas` | background | The uninterrupted dark reading canvas. |
| Dim cool rule | `#525456` | `--color-edge` | border | Visible result of rgba(224,232,236,0.3) over the charcoal canvas; thin frame and grid separators. |
| Blue gray | `#a7b4ba` | `--color-cool` | text, link | Supporter names, contact prefixes and secondary social marks. |
| Soft gray | `#dbdbdb` | `--color-role` | text | Short role labels beneath portrait names. |
| Warm chalk | `#e4e2d8` | `--color-primary` | text, accent, link | Headlines, primary prose, monochrome marks, icons and bright bracket tips. |
| Pearl light | `#ffffff` | `--color-pearl` | background, text | The luminous peaks of the sculptural artwork and lettering over the light scene; use spectral hues within the artwork rather than as interface tokens. |

## Typography

- **Magnetik** — Chapter headings and item titles. Light, rounded grotesk with broad open counters and an unusually delicate monumental presence. If unavailable, use **Manrope**. Use 300; preserve the open width and tight leading. Font stack: "Magnetik", "Manrope", system-ui, sans-serif.
- **LazareGrotesk** — Readable editorial prose, navigation, names and contact text. Clean contemporary grotesk, mainly light weight with modest contrast between text roles. If unavailable, use **Inter**. Use 300 and 400; avoid heavy UI weights. Font stack: "LazareGrotesk", "Inter", system-ui, sans-serif.
- **Space Mono** — Technical explanations, indexes, roles and tiny uppercase labels. Distinctively mechanical monospaced letters; more personality than a neutral code font. Font stack: "Space Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Magnetik | 300 | 120px | 0.9 | normal | Oversized chapter titles; also the base recipe for the immersive opening statement. |
| heading | Magnetik | 300 | 48px | 0.9 | normal | Editorial statements and repeated feature headings. |
| numbered-heading | Magnetik | 300 | 48px | 0.9 | -0.0125em | Numbered explanatory blocks. |
| row-title | Magnetik | 300 | 36px | 1 | -0.0167em | Names within full-width resource rows. |
| name | LazareGrotesk | 400 | 22.5px | 1.1 | normal | Portrait names. |
| body | LazareGrotesk | 300 | 18px | 1.2 | normal | Short editorial supporting statements. |
| support-name | LazareGrotesk | 300 | 16.5px | 1.3 | normal | Names or credentials inside framed endorsement strips. |
| technical-body | Space Mono | 400 | 14.3px | 1.5 | normal | Compact factual paragraphs below numbered headings. |
| centered-explanation | Space Mono | 400 | 14.3px | 1.4 | normal | Muted centered conceptual explanations. |
| quote | LazareGrotesk | 300 | 14.3px | 1.5 | normal | Secondary quotation beneath an editorial statement. |
| role | Space Mono | 400 | 12px | 1.3 | 0.025em | Centered job labels and prior affiliations. |
| index | Space Mono | 400 | 12px | 1.5 | normal | Two-digit numbers followed by a period at row and cell corners. |
| contact | LazareGrotesk | 300 | 12px | 1 | normal | Contact prefix and email link. |
| attribution | Space Mono | 400 | 10.5px | 1.5 | 0.043em, uppercase | Small credit below a quotation. |
| navigation | LazareGrotesk | 300 | 10.5px | 1 | 0.1em, uppercase | Header links and return-to-top action. |
| footer-navigation | LazareGrotesk | 300 | 10.5px | 1 | 0.043em, uppercase | Compact stacked footer navigation. |
| micro-label | Space Mono | 400 | 9px | 1.5 | 0.08em, uppercase | Resource format labels and endorsement-strip caption. |

**Notes:**

- Keep the large headings at weight 300 rather than compensating for their scale with boldness. Headlines use 0.9 leading; prose expands to 1.2–1.5.
- Use normal tracking for monumental chapter type, negative tracking only on the numbered headings and resource titles, and positive tracking on the smallest labels.
- The opening statement reads slightly larger than a chapter heading: tune it toward 132px with about 124px between baselines at a 1440px width, preserving two short lines rather than shrinking it into a conventional hero.
- Root sizing follows min(max(12px, 0.833333vw), 28px); rem-based typography and spacing scale with that root rather than remaining fixed across wide viewports.

## Layout

**Density:** Airy at the page scale, tightly indexed within proof blocks; large dark intervals separate compact pockets of information.

### Spacing

**Spacing system:**

- **horizontal step** 6px, horizontal — The common horizontal spacing step behind 18px, 24px and 30px insets.

| Value | Use |
| --- | --- |
| 6px | Name-to-role spacing and small icon separation. |
| 18px | Navigation separation, grid-cell insets and space below portrait media. |
| 24px | Container side padding and heading-to-copy spacing. |
| 30px | Resource-row column gaps and endorsement-strip side padding. |
| 33px | Resource-row vertical padding. |
| 60px | Transition spacing around the small conceptual graphic. |
| 90px | Separation between editorial statement groups. |
| 120px | Separation between numbered explanatory blocks. |
| 262.5px | Large section breaks and separation after the centered conceptual explanation. |

### Containers and grids

- **reading container**: max width 1366px · side padding 24px. Centered outer container, producing 1318px of content and roughly 61px visible side margins at 1440px.
- **immersive container**: side padding 24px. Full-width opening, fixed navigation and closing stage use narrow edge insets rather than the reading column.
- **explanation column**: max width 488px. Centered mono explanation. Numbered text blocks narrow further to 427.5px and sit off-center.
- **editorial split**: 2 columns · gap 0px. A huge chapter title fills the left half; a 453px stack of statements occupies the right with a broad intervening void.
- **proof grid**: 4 columns · gap 0px. Contiguous logo cells across the reading container, two rows in the full example.
- **portrait grid**: 3 columns · gap 57px. Centered 247px profile columns with 198px media, leaving broad dark margins.

## Corner radius

| Element | Radius |
| --- | --- |
| portrait media | 3.8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| grid separators | `rgba(224, 232, 236, 0.3) 1px 0px 0px 0px, rgba(224, 232, 236, 0.3) 0px 1px 0px 0px` | Paint cell edges without adding gutters or elevated card shadows. |

### Surfaces

#### Dark reading field · level 0

**Use:** All text-led sections and indexed proof.

**CSS:** `background: #151515; color: #e4e2d8`

**Observed:** A continuous flat field; sections are distinguished by spacing and alignment rather than alternating fills.

**Transfer:** Keep the reading interior visually continuous.

#### Bracketed frame · level 1

**Use:** Proof blocks, supporter strips and shallow footer.

**CSS:** `background: transparent; border-top: 1px solid rgba(224, 232, 236, 0.3); border-bottom: 1px solid rgba(224, 232, 236, 0.3); position: relative`

**Observed:** Dim straight rules terminate in tiny brighter detached quarter-curves; this is not a rounded card border.

**Transfer:** Use separate corner pseudo-elements with 1px chalk strokes and 75% corner radii; leave a small break before the straight rules.

#### Closing legibility veil · level 1

**Use:** Behind the compact footer over luminous art.

**CSS:** `background: linear-gradient(0deg, #151515 5%, rgba(0, 0, 0, 0) 100%); opacity: 0.5`

**Observed:** A shallow dark fade softens the bottom of the artwork without turning it into a solid footer band.

**Transfer:** Apply the fade on an independent layer so footer text remains fully opaque.

## Components

### Fixed navigation

**Use:** Persistent orientation above both the light artwork and dark reading field.

**CSS:** `position: fixed; top: 0px; width: 100%; padding-top: 24px; padding-bottom: 48px; z-index: 10`

**Text style:** `navigation` — LazareGrotesk 300 · 10.5px/1 · tracking 0.1em · uppercase

**Observed:** A small wordmark sits left; six compact links form a single right-aligned line. The header has no opaque bar.

**Transfer:** Use a short set of section anchors and maintain the same delicate appearance over the artwork.

### Inscription link

**Use:** Default action treatment for navigation and lightweight calls to explore.

**CSS:** `background: transparent; color: #e4e2d8; padding: 0px 0px 2.3px; position: relative; text-decoration: none; overflow: hidden`

**Text style:** `navigation` — LazareGrotesk 300 · 10.5px/1 · tracking 0.1em · uppercase

**Observed:** A small underline treatment reinforces the active or interactive label; no filled button, enclosing border or rounded shell.

**Transfer:** Make the primary action a deliberate text inscription, not a conversion-colored button.

### Numbered explanation

**Use:** Short method or capability descriptions.

**CSS:** `max-width: 427.5px; margin-bottom: 120px; color: #e4e2d8`

**Text style:** `technical-body` — Space Mono 400 · 14.3px/1.5

**Observed:** The index hangs left of a light 48px heading, with a compact mono paragraph below; content is offset from the main container edge.

### Editorial statement

**Use:** A belief, benefit or operating principle with supporting detail.

**CSS:** `max-width: 453px; margin-bottom: 90px`

**Text style:** `heading` — Magnetik 300 · 48px/0.9

**Observed:** Heading, short sans support statement, subdued smaller quotation, then uppercase mono attribution. It is unboxed.

### Sculptural profile

**Use:** Introduce people where personal expertise is part of the proposition.

**CSS:** `width: 247px; text-align: center; color: #e4e2d8`

**Text style:** `name` — LazareGrotesk 400 · 22.5px/1.1

**Observed:** A 198px pale bust rises directly from the dark canvas, followed by name, mono role, muted affiliation and paired social icons. No enclosing card.

**Transfer:** Use consistent bust-like portraits and only relevant credentials.

### Indexed logo cell

**Use:** Proof through partners, integrations or selected work.

**CSS:** `height: 247px; display: flex; position: relative; align-items: center; justify-content: center; box-shadow: rgba(224, 232, 236, 0.3) 1px 0px 0px 0px, rgba(224, 232, 236, 0.3) 0px 1px 0px 0px`

**Text style:** `index` — Space Mono 400 · 12px/1.5

**Observed:** A monochrome logo sits centrally; a small index occupies the upper left and a dim outbound arrow the upper right. Some marks carry an asterisk explained outside the grid.

**Transfer:** Normalize logos by visual weight rather than forcing identical widths; preserve qualifiers when necessary.

### Resource row

**Use:** A browsable list of useful outputs, tools or documents.

**CSS:** `display: grid; grid-template-columns: 48px 1fr auto; align-items: baseline; row-gap: 9px; column-gap: 30px; padding: 33px 18px; border-bottom: 1px solid rgba(224, 232, 236, 0.3); color: #e4e2d8; text-decoration: none`

**Text style:** `row-title` — Magnetik 300 · 36px/1 · tracking -0.0167em

**Observed:** Index at left, generous light title in the middle, tiny uppercase format and diagonal arrow at right. The complete list is bracket-framed.

### Supporter strip

**Use:** Concise endorsements or credentials beneath a human proof section.

**CSS:** `padding: 27px 30px; text-align: center; color: #a7b4ba`

**Text style:** `support-name` — LazareGrotesk 300 · 16.5px/1.3

**Observed:** A tiny uppercase centered caption sits above three equal names or credentials separated by fine vertical rules; the entire strip uses the Bracketed frame.

### Closing footer

**Use:** Contact and site orientation at the end of the visual journey.

**CSS:** `display: flex; justify-content: space-between; padding: 15px; margin-bottom: 24px; position: relative`

**Text style:** `footer-navigation` — LazareGrotesk 300 · 10.5px/1 · tracking 0.043em · uppercase

**Observed:** Within a shallow wide frame, wordmark and email anchor the left, six stacked links occupy the middle, social icons sit upper right and a return link sits lower right. It overlays art rather than replacing it.

### Return link

**Use:** Return from the long reading journey to the opening.

**CSS:** `display: flex; align-items: center; padding: 4.5px 0px 2.3px; color: #e4e2d8; text-decoration: none`

**Text style:** `navigation` — LazareGrotesk 300 · 10.5px/1 · tracking 0.1em · uppercase

**Observed:** A narrow upward arrow follows the text with a 6px gap; it is integrated into the footer rather than floated in a circular control.

## Imagery and graphics

### Prismatic contour relief

**Use:** The signature immersive opening, narrative visual interludes and luminous closing stage.

**Observed:** An immense landscape of nested, irregular oval terraces fills the viewport. It resembles layered white paper or porcelain with soft occlusion shadows, fine grain and rainbow refraction on the raised edges. Cyan, lilac, mint and warm yellow-red bands become stronger during the middle visual passages. The ending reverses the cavity into a pale raised island, offset toward the upper right. No image card or browser frame contains it.

**Transfer:** Create an abstract dimensional metaphor for the new product rather than a literal stock technology illustration. Preserve the layered white relief, oblique perspective, dark recesses and restrained spectral edges. A carefully lit static SVG or raster relief is the minimum acceptable substitute.

**Build:** Construct 20–30 nested irregular closed SVG paths around an off-center oval. Offset successive layers by 8–18px and compress the vertical axis to suggest an oblique surface; let outer paths extend beyond the viewport. Fill mostly with pearl and chalk, placing blurred dark strokes beneath each ledge using rgba(0,0,0,0.25). Offset thin duplicate edge paths in rgba(100,230,240,0.5), rgba(185,135,220,0.4), rgba(150,215,145,0.4) and rgba(245,195,100,0.4). Add a subtle grain filter, broad white illumination and a dim lower gradient. Reverse path ordering for a raised closing mound; match the soft glow rather than rigidly repeating gradient stops.

### Monochrome proof marks

**Use:** Indexed proof cells.

**Observed:** Warm chalk logos and wordmarks appear as flat silhouettes on the unpainted dark background; their visual widths vary, generally around 92–198px.

**Transfer:** Use authentic product-relevant marks, optically normalized and rendered in one neutral color.

### Porcelain bust portraits

**Only for:** people-led proof sections

**Use:** Human expertise presented as a small sculptural gallery.

**Observed:** Front-facing head-and-shoulder likenesses are monochrome pale gray with a matte clay or plaster finish. Fine facial and hair details catch soft light; silhouettes are cut out against the dark field. Each occupies a 198px square rather than a full photographic scene.

**Transfer:** Use consistent grayscale cutout portraits with soft dimensional lighting. If sculptural rendering is unavailable, use neutral-lit grayscale cutouts with reduced background detail, not colored headshot tiles.

### Icons

**Observed:** Social marks are solid 15×15px silhouettes. Outbound arrows are 15–17px with 1px strokes and butt caps; the upward return arrow is narrower at 6×9px. They use chalk or subdued blue gray and remain much smaller than titles.

**Transfer:** Choose restrained geometric arrows and recognizable social silhouettes. Keep navigation mostly typographic rather than giving every label a pictogram.

## Section recipes

How recurring sections are built.

### First screen: Immersive relief opening

**Observed:** The first 900px is an edge-to-edge sculptural scene with a transparent Fixed navigation above it. The relief fills the upper two thirds, its crater centered toward the right; the lower portion darkens into a legibility gradient. A huge light two-line statement occupies approximately the left half of the lower third. A two-line support statement is aligned beside its second line in the right half. A near-full-width fine rule with curved bracket tips closes the screen, with a tiny identity line below it at left and an Explore inscription at right. Headline, support, main object and exploration action all fit above the fold; the factual reading content begins much later.

**Transfer:** For another product, use a short invitation or spatial metaphor and a factual one-sentence category statement. Render a product-relevant abstract relief using Prismatic contour relief, even when no product media exists. A shorter detail page can open on a still version of the same scene with less scroll travel; retain the low anchored typography and bracketed exploration line.

**Avoid:** Do not replace the scene with a small centered illustration above a centered CTA stack, or place a dashboard mockup in a rounded browser card.

**Text style:** `display` — Magnetik 300 · 120px/0.9

### Immersive phrase interlude

**Observed:** The sculpture expands through full-screen scroll chapters while short white phrases such as “You jump...” and “We jump...” sit centered over the cavity. The artwork carries nearly all the visual information.

**Transfer:** Use brief linked phrases to shift from visitor ambition to product partnership. The number of interludes should follow the story, not determine it.

### Concept to method

**Observed:** A small centered animated graphic introduces a narrow muted mono explanation. A 262.5px interval separates it from off-center numbered explanatory blocks with Numbered explanation components. The two method blocks are separated by 120px.

**Transfer:** Translate a conceptual idea into plain-language method and concrete scope. Let empty space make the transition from immersive art to factual prose readable.

### Monumental title and editorial stack

**Observed:** A 120px title occupies the left half while three Editorial statement groups form a narrow right column. Each group uses a 48px heading, 18px support, muted quotation and small uppercase credit. The large title remains anchored as the statements progress.

**Transfer:** Use this asymmetry for differentiators, commitments or product principles. Keep the individual paragraphs short enough to preserve the dark void.

### Sculptural human proof

**Observed:** A centered 120px title leads a three-column Sculptural profile gallery. Names and technical roles form compact centered stacks; social icons complete each column. A narrower Supporter strip sits below the group in a Bracketed frame.

**Transfer:** Use when expertise needs to be visible. Substitute concise expert credentials or real endorsements for general prestige claims.

### Indexed proof matrix

**Observed:** A large chapter heading is followed by a broad interval and a zero-gap four-column matrix of Indexed logo cell components. Fine outer brackets and inner separators create one shared frame. A tiny asterisk note sits beneath the grid.

**Transfer:** Apply the matrix to integrations, customers, examples or selected outputs; adapt row count to truthful proof.

### Resource index

**Observed:** A left-aligned 120px title sits above four 103px Resource row components. Full-width rules and small bracket tips enclose the list, with format labels pinned right.

**Transfer:** Offer useful artifacts or deeper reading in a compact catalog rather than creating a set of promotional cards.

### Relief reprise ending

**Observed:** A 900px luminous stage restores the pearlescent sculpture after the dark reading sections. A pale mound sweeps up and toward the right with rainbow fringes near the top edges. The Closing footer occupies roughly the bottom 162px in a wide Bracketed frame, backed by the Closing legibility veil. There is no oversized closing sales headline.

**Transfer:** End by returning to the visual metaphor and offering direct contact, navigation and a return action. Preserve the expansive art above the shallow footer instead of adding a generic CTA banner.

## Page flow

**Storyline:** immersive invitation → shared ambition → explanation → method and differentiation → human and organizational proof → useful outputs → visual reprise and contact

### An immersive brand landing page that moves from imagination to credible partnership

1. **Promise** — A full-screen sculptural environment carries an invitation and a short factual category description.
2. **Emotional bridge** — Centered paired phrases make the art feel like a journey shared with the visitor.
3. **Explanation** — A narrow conceptual note gives way to numbered method blocks.
4. **Differentiation** — A monumental left title balances a right-hand stack of editorial statements.
5. **Social proof** — Sculptural profiles and a framed credential strip establish human expertise.
6. **Organizational proof** — A numbered monochrome logo matrix presents selected relationships.
7. **Useful outputs** — Large resource titles are indexed in thin ruled rows.
8. **Closing contact** — The pale relief returns behind a minimal framed footer and direct email.

**Transfer:** Borrow the alternation of immersive atmosphere, compact factual explanation and indexed proof. Change the sequence and number of chapters to fit the product while keeping the relief, delicate framing and visual closing reprise.

## Writing

Ambitious, cerebral and personally committed. It pairs imaginative language with specific descriptions of what the organization actually does, without the breathless tone of a growth funnel.

**Do not copy:** Do not reuse Topology's name, logo, team identities, company relationships, investment claims, portfolio marks, email address, quoted authorities or proprietary artwork. Replace them with truthful material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use “we” for commitments and actions. Occasional “you” creates a direct invitation; factual explanations otherwise remain declarative.
- **Rhythm:** Very short invitation headlines and chapter labels give way to compact explanatory paragraphs. Repeated statement headings run about two to four words; support usually fits one or two sentences. No exclamation-heavy sales language.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening invitation | A brief invitation built around a spatial or action metaphor. | 4–8 words | “Meet us at the edge.” |
| Narrative bridge | Parallel second-person and first-person phrases with an ellipsis. | 2–3 words | “You jump...”<br>“We jump...” |
| Section title | A plain noun phrase that names the chapter rather than selling a benefit. | 1–3 words | “Select investments”<br>“Public goods” |
| Editorial heading | An active imperative expressing a durable commitment. | 2–4 words | “Execute with Vision”<br>“Lead with Curiosity” |
| Support | A concrete belief expressed in one balanced sentence. | 10–20 words | “The greatest impact emerges when wild imagination meets calculated execution.” |
| Utility action | Plain directional instruction without added persuasion. | 1–3 words | “Explore”<br>“Back to top” |

**Words and phrasing to use:** partner; build; curiosity; ambition; discovery; insights; long term; imagination; execution

**Avoid:** 10x; game-changing; crush it; supercharge; limited time; the ultimate solution

**Rules:**

- Pair abstract ambition with a concrete statement of method or focus.
- Let the invitation be lyrical and the technical paragraph be literal.
- Use quotations only when relevant and accurately attributed; put attribution below in small capitals.
- Name useful outputs directly; the format label can carry the technical classification.

## Do's and Don'ts

### Do

- Keep the reading canvas at #151515 and primary type at #e4e2d8.
- Use 120px/0.9 weight-300 chapter headings against tiny 9px mono descriptors.
- Align resource titles within a 48px 1fr auto grid with 30px column gaps.
- Use 33px vertical row padding for a deliberate catalog rhythm.
- Make logo proof one contiguous four-column frame with no gutters.
- Keep portrait media at 198px and profile names at 22.5px/1.1.
- Let section breaks reach 262.5px rather than filling every void with content.
- Use separate bright curved bracket tips to finish dim 1px rules.

### Don't

- Do not carry rainbow hues into navigation fills, resource rows or logo cells; chromatic light belongs to the art.
- Do not make 120px chapter titles bold; weight 300 is central to their airy form.
- Do not turn the 330×247 proof cells into individually rounded, shadow-elevated tiles.
- Do not use a white reading section between dark chapters; the neutral interior is continuous.
- Do not make all explanatory copy proportional sans; the 14.3px Space Mono paragraphs are a deliberate contrast.
- Do not replace the pale sculptural people with saturated square headshots.
- Do not make utility labels as prominent as titles; retain the 9–12px technical tier.
- Do not turn the framed 162px footer into a multi-screen sitemap or a filled conversion panel.

## Motion and responsive

### Motion

**Observed:**

- The art changes framing and relief shape through the long opening scroll sequence, with centered phrases appearing in successive scenes.
- Navigation declares color 0.3s ease-out transitions; other actions and surfaces declare background-color 0.3s and opacity/transform 0.3s transitions.
- The small return arrow declares a 2s ease infinite arrow-loop-reversed animation.
- The editorial split includes a pinned title treatment.

**Transfer:**

- Treat the relief as one continuous environment whose viewpoint changes, not unrelated decorative images.
- Keep utility motion subordinate to the monumental scene; retain the small directional arrow motif.
- A static relief still can preserve the composition when an animated scene is unavailable.

**Unknown:**

- Exact WebGL camera paths, scene timing, phrase transitions and reduced-motion implementation.
- Specific hover and focus-visible visual end states.

### Responsive

**Observed:**

- Declared width breakpoints are 375px, 768px, 1024px, 1366px, 1536px and 1921px.
- Root sizing follows min(max(12px, 0.833333vw), 28px). Desktop navigation is breakpoint-controlled; the portrait group permits wrapping.

**Transfer:**

- On narrow screens retain the edge-to-edge relief but move the supporting statement below the invitation, preserving a low-anchored group.
- Stack the editorial split with a strong title above narrow text; reduce proof columns while retaining contiguous cells and bracket framing.
- Keep each resource's index and title together; allow the tiny format label to wrap rather than compressing the title into microtype.

**Unknown:**

- Rendered mobile layouts, menu construction and exact narrow-screen typography changes.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
