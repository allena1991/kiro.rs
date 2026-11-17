# Dovetail — ink and human ingenuity

## Overview

An airy editorial style that pairs businesslike grotesk typography with eccentric, hand-drawn black illustrations. Butter yellow, salmon and periwinkle frame warm ivory content, while real-world photography supplies grounded proof. It suits relationship-led technology products and expert services that want to feel imaginative without becoming playful software dashboards.

### Essentials

- A low-slung promise beneath an oversized identity: the first 900px pairs a 72px regular headline on the left with a roughly 443px-wide ink illustration on the right, leaving the upper middle conspicuously open.
- Editorial hierarchy stays conversational rather than monumental: 48px/1.17 regular section statements, 22px/1.36 bold section labels and 20px/1.4 body copy, all in one grotesk family.
- Color behaves like book covers and endpapers: butter yellow opens and closes the default page, ivory carries the long reading middle, and a 400px charcoal footer reverses the identity. Salmon and periwinkle belong to specialist page types.
- Actions are small dark lozenges, not rectangular software controls: the main action uses a 24px radius and 28px semibold lettering; the navigation action uses a 16px radius and 20px lettering.
- Ink artwork supplies the memorable personality: unboxed black-and-transparent drawings combine elongated figures, solid shapes, fine hatching and starbursts. Include a bespoke metaphor illustration; a simplified SVG collage of human gestures, rays and interlocking forms is the fallback.
- Proof is staged as editorial media rather than cards: 16px-rounded photographs sit directly on the ivory canvas, with 24px gutters and captions below; 1px ink rules organize the surrounding text.
- The ending is a second brand moment: a pastel illustrated contact band leads into a charcoal footer with a small utility row above a near-full-width cream identity lockup. Re-create this oversized typographic sign-off with the new identity.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter yellow | `#f9e5b1` | `--color-cover` | background | Default opening, opening navigation and closing contact band. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#1d1e21` | `--color-ink` | text, background, border, action | Main lettering, rules, buttons, illustration tone and reversed footer. |
| Cream stone | `#ede5dc` | `--color-pill` | surface | Capability word lozenges. |
| Warm ivory | `#fef9f3` | `--color-canvas` | background, text | Long-form content canvas and reversed lettering on charcoal. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| case-study index pages | Salmon cover | `#f8b7aa` | `--color-salmon` | background | Opening, navigation at the bookends and closing contact band. |
| company and people pages | Periwinkle cover | `#b0c5f3` | `--color-periwinkle` | background | Opening, navigation at the bookends and closing contact band. |

## Typography

- **Lausanne** — All marketing text and controls. A clean, wide-open grotesk with rounded bowls; regular weights carry the large statements while bold is reserved for navigational emphasis. If unavailable, use **Inter**. Use 400, 600 and 700; preserve line wrapping and the slightly tight display tracking. Font stack: "Lausanne", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Lausanne | 400 | 72px | 1 | -0.01em | Opening promise, left-aligned and broken into two or three deliberate lines. |
| heading | Lausanne | 400 | 48px | 1.17 | -0.005em | Section statements, quotations, capability words and the closing two-line message. |
| attribution | Lausanne | 400 | 32px | 1.5 | -0.005em | Quotation attribution; also names in people listings. |
| action | Lausanne | 600 | 28px | 1 | 0.007em | Main contact button. |
| section-label | Lausanne | 700 | 22px | 1.36 | 0.005003636em | Section labels, emphatic text links and media captions. |
| body-lead | Lausanne | 400 | 22px | 1.36 | 0.005003636em | Introductory supporting paragraphs and expertise-column descriptions. |
| body | Lausanne | 400 | 20px | 1.4 | 0.01em | Long descriptions, secondary support and footer utilities. |
| action-compact | Lausanne | 600 | 20px | 1 | 0.01em | Contact action within the compact navigation. |
| navigation | Lausanne | 600 | 20px | 1.4 | 0.01em | Navigation labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| criteria and process sections | number | Lausanne | 700 | 20px | 1.4 | 0.01em | Two-digit indices above short criteria statements. |

**Notes:**

- Use sentence case throughout; hierarchy comes from size, line breaks and weight rather than uppercase eyebrows.
- Large statements stay weight 400. Tracking tightens from 0.01em body to -0.005em section statements and -0.01em opening copy.
- Trim excess leading around lozenge text to retain the compact 48px and 32px button heights; preserve the nominal type recipes rather than shrinking the lettering.
- The huge identity lettering is artwork, not another heading level. Scale the new identity as a graphic rather than stretching a text font.

## Layout

**Density:** Airy: wide open cover compositions alternate with ruled editorial sections, with photography carrying much of the middle.

### Spacing

**Spacing system:**

- **gutter** 16px — Base gutter token; side padding is twice this and column gaps are one and a half times it.
- **rhythm** 8px, vertical — Dominant vertical rhythm for section padding and larger text gaps; compact controls have separate optical padding.

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps. |
| 16px | Space below criteria indices and padding above criteria text groups. |
| 24px | Grid gutters and photograph-to-caption gaps. |
| 32px | Outer side padding, ruled-section inner padding and headline-to-action spacing. |
| 40px | Lead-copy-to-text-link spacing and closing band bottom padding. |
| 48px | Section heading to longer support copy. |
| 72px | Section-label-to-main-statement gap. |
| 80px | Closing statement to main action. |
| 112px | Separation between selected major editorial chapters. |
| 160px | Top padding of the closing contact band and separation before deep criteria content. |

### Containers and grids

- **editorial container**: max width 1440px · side padding 32px. Centered desktop container, leaving 1376px of usable width at the main desktop size.
- **editorial grid**: 12 columns · gap 24px. Seven columns for the opening text, four at the far right for the illustration; five-column text blocks pair with six-column visual groups.
- **paired media**: 2 columns · gap 24px. Equal 676px-wide photography panels, or a text column on the left and a photograph on the right.
- **expertise columns** (only for company and capability pages): 3 columns · gap 24px. Equal 443px-wide ruled descriptions.
- **criteria grid** (only for criteria and process sections): 4 columns · gap 24px. Equal 326px-wide numbered statements.

## Corner radius

| Element | Radius |
| --- | --- |
| primary action | 24px |
| compact action and media | 16px |
| capability word | 91px |
| circle control | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Ivory reading canvas · level 0

**Use:** Main reading sections between colored bookends.

**CSS:** `background: #fef9f3; color: #1d1e21`

**Observed:** A flat warm ground, without card outlines or shadows around whole sections.

**Transfer:** Keep lengthy product explanations on this ground.

#### Pastel cover · level 0

**Use:** Default opening and closing contact surfaces.

**CSS:** `background: #f9e5b1; color: #1d1e21`

**Observed:** A solid butter-yellow field behind both text and transparent ink drawings.

**Transfer:** Treat the opening and closing as related endpapers, not separate campaigns.

#### Ruled chapter

**Use:** Section boundaries and repeated information groups.

**CSS:** `border-top: 1px solid #1d1e21; padding-top: 32px; padding-bottom: 32px`

**Observed:** The rule spans the inner container; labels sit below it rather than interrupting it.

**Transfer:** Use a single top rule in place of a boxed card.

#### Reversed identity base · level 0

**Use:** The footer revealed beneath the closing contact band.

**CSS:** `background: #1d1e21; color: #fef9f3; height: 400px`

**Observed:** A small utility row sits above an enormous cream identity graphic.

**Transfer:** Reserve this strongest contrast for the final brand signature.

#### Salmon cover

**Only for:** case-study index pages

**Use:** Alternative colored bookends.

**CSS:** `background: #f8b7aa; color: #1d1e21`

**Observed:** Same construction as Pastel cover, with a salmon ground.

**Transfer:** Use this as a page-type identity, not an extra panel color on a normal landing page.

#### Periwinkle cover

**Only for:** company and people pages

**Use:** Alternative colored bookends.

**CSS:** `background: #b0c5f3; color: #1d1e21`

**Observed:** Same construction as Pastel cover, with a cool blue ground.

**Transfer:** Keep the middle ivory so the color remains a framing device.

## Components

### Navigation

**Use:** Persistent orientation and access to major destinations.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; z-index: 10; background: #f9e5b1`

**Text style:** `navigation` — Lausanne 600 · 20px/1.4 · tracking 0.01em

**Observed:** The opening has an oversized wordmark at the left and a separate symbol at the right, with two links between. On scroll it becomes a compact wordmark, a fine bottom rule and a visible compact contact action; its ground follows the current pastel or ivory region. Links have transparent 1px borders, 16px radii and 9px vertical by 12px horizontal optical padding; the current destination has a fine ink outline.

**States:** Declared: hover navigation links uses rgba(29, 30, 33, 0.1) background and transparent borders; focus-visible styling is unknown.

**Transfer:** Use the new identity in both an expanded wordmark and a compact symbol form.

### Primary button

**Use:** Main conversion in the opening and closing.

**CSS:** `display: inline-block; background: #1d1e21; color: #fef9f3; border-radius: 24px; padding: 14px 16px; height: 48px; box-sizing: border-box`

**Text style:** `action` — Lausanne 600 · 28px/1 · tracking 0.007em

**Observed:** Text only, without an arrow; the lettering is optically trimmed to fit the compact lozenge.

**States:** Declared: hover color rgba(254, 249, 243, 0.6); focus-visible styling is unknown.

### Compact contact button

**Use:** Conversion within the scrolled navigation.

**CSS:** `display: inline-block; background: #1d1e21; color: #fef9f3; border-radius: 16px; padding: 9px 12px; height: 32px; box-sizing: border-box`

**Text style:** `action-compact` — Lausanne 600 · 20px/1 · tracking 0.01em

**Observed:** Appears beside the destination links after the expanded identity contracts.

**States:** Declared: hover color rgba(254, 249, 243, 0.6); focus-visible styling is unknown.

### Arrow text link

**Use:** Secondary navigation from editorial sections.

**CSS:** `color: #1d1e21; border-bottom: 2px solid transparent; padding-bottom: 3px`

**Text style:** `section-label` — Lausanne 700 · 22px/1.36 · tracking 0.005003636em

**Observed:** A short bold text label followed by a small northeast arrow. External links in case descriptions use regular body lettering instead.

**States:** Declared: hover border-color currentcolor; focus-visible styling is unknown.

### Capability lozenge

**Use:** A compact visual taxonomy beside introductory copy.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #ede5dc; border-radius: 91px; padding: 15px 20px`

**Text style:** `heading` — Lausanne 400 · 48px/1.17 · tracking -0.005em

**Observed:** Five short words stack as individually sized, centered lozenges with 4px gaps. Some include small black pictograms; lettering is optically trimmed, producing roughly 64px-high shapes.

**Transfer:** Use a short set of complementary capabilities; retain differing word widths rather than forcing equal boxes.

### Media rail card

**Use:** Browsable visual proof.

**CSS:** `width: 520px; flex-shrink: 0`

**Text style:** `section-label` — Lausanne 700 · 22px/1.36 · tracking 0.005003636em

**Observed:** A 520px by 293px photograph with 16px corners sits above a bold caption separated by 24px. Cards run in a 24px-gap rail with the next card cut by the viewport; the card has no enclosing fill or border.

**Transfer:** Show real use contexts or customer environments, not miniature website screenshots.

### Circular control

**Use:** Rail navigation and small disclosure actions.

**CSS:** `width: 32px; height: 32px; border: 1px solid #1d1e21; border-radius: 9999px; padding: 7.2px; box-sizing: border-box`

**Observed:** A thin circle holds a simple arrow or plus. Rail buttons are about 34px across and a disabled previous button is faded to 0.2 opacity.

**States:** Declared: hover on a disclosure's parent changes its background to #1d1e21 and its icon to #fef9f3; focus-visible styling is unknown.

### Identity footer

**Use:** Utility access and final brand impression.

**CSS:** `background: #1d1e21; color: #fef9f3; height: 400px`

**Text style:** `body` — Lausanne 400 · 20px/1.4 · tracking 0.01em

**Observed:** Five utility groups run across the top: address, contact, policy links, social link and copyright. Beneath them the symbol and wordmark fill almost the entire available width. The footer sits behind the page and is revealed as the contact band moves away.

**States:** Declared: hover footer links opacity 0.4; focus-visible styling is unknown.

**Transfer:** Fit the new identity as a vector lockup; preserve the contrast between small utilities and huge lettering.

### Numbered criterion

**Only for:** criteria and process sections

**Use:** Short qualification or process statements.

**CSS:** `border-top: 1px solid #1d1e21; padding-top: 16px; margin-bottom: 24px`

**Text style:** `body` — Lausanne 400 · 20px/1.4 · tracking 0.01em

**Observed:** A bold two-digit index in the number recipe appears 16px above regular paragraph text. Four unboxed columns align along their top rules.

**Transfer:** Use concise criteria, not large KPI numerals or dashboard metrics.

### People disclosure row

**Only for:** company and people pages

**Use:** Compact biographies and contact access.

**CSS:** `border-top: 1px solid #1d1e21; padding-top: 24px; padding-bottom: 20px; position: relative`

**Text style:** `attribution` — Lausanne 400 · 32px/1.5 · tracking -0.005em

**Observed:** A roughly 93px-high row aligns a name left, a body-size role in the middle and a contact link plus Circular control on the right. The last row also has a bottom rule. More biography text is associated with the disclosure.

**Transfer:** Keep this roster-like rather than replacing it with portrait cards.

## Imagery and graphics

### Human ingenuity ink drawings

**Use:** Signature artwork in the opening, quotation chapter and closing band.

**Observed:** Black-and-transparent editorial illustrations float directly on the page ground. Elongated, angular people interact with giant hands, modular panels and radiating stars. Broad solid-black shapes contrast with narrow contour strokes, stripes and restrained rough ink texture. The opening drawing is 443px wide, the quotation drawing 559px wide and the closing drawing about 449px wide.

**Transfer:** Create an original visual metaphor for people making the new product useful. Maintain the black-only line-and-silhouette language and transparent backing. Minimum acceptable artwork is a simple but intentional SVG collage rather than an unrelated stock icon.

**Build:** Use an SVG viewBox of 0 0 450 460. Layer two asymmetrical interlocking shapes across the lower half, one filled charcoal and one transparent with a 2px charcoal outline. Add two or three elongated gesture figures using circles, angular torso paths and curved limbs, with 1px parallel hatching on selected clothing. Place five irregular eight-point stars around the upper edges using alternating long and short radial points. Keep the background transparent, use only charcoal, and concentrate solid fill in one lower corner; do not use shadows or gradients.

### Working-world photography

**Use:** Proof rails and case-study detail rows.

**Observed:** Full-color documentary scenes show factory aisles, shipping work, heavy machinery, offices and logistics. Cool neutral settings with localized color, natural light and practical work replace glamorous brand scenes. Photos fill rounded rectangles without overlays; rail media is 16:9, while detail rows use approximately 676px-wide images.

**Transfer:** Photograph the product's actual working environment or the people it serves. Favor recognizable activity and believable light over dramatic color grading.

### People and working details

**Use:** Human proof on a landing page and expanded company stories.

**Observed:** A straight-on team portrait in a bright working studio pairs with a close overhead scene of hands, a laptop and coffee. Two 676px by 451px images sit side by side with 16px corners; the broader company-story image is 793px by 528px.

**Transfer:** Pair a candid but composed group portrait with a tactile detail of the work. Keep clothing and surroundings restrained, with daylight and no text baked into the photography.

### Oversized identity lockup

**Use:** Expanded opening identity and monumental footer signature.

**Observed:** The opening wordmark spans roughly a third of the page width, separate from a far-right symbol. The footer joins a cream symbol and wordmark into a nearly edge-to-edge horizontal sign.

**Transfer:** Use the new brand's own wordmark and symbol; if there is no symbol, create a simple abstract mark with the same visual weight and use it consistently.

**Build:** Place vector wordmark and symbol in an SVG or flex lockup. For the opening, keep the wordmark near 500px wide at a 1440px viewport and place the symbol separately at the far right. In the footer, fit both to the 1376px inner width with a shared optical height near 220px, coloring all paths warm ivory. Keep proportions intact rather than stretching the lettering.

### Icons

**Observed:** Sparse black pictograms, northeast text-link arrows, outlined circular arrow controls and 16px plus symbols. Small capability pictograms are about 24px; rail arrow artwork is about 32px.

**Transfer:** Use simple solid or clean line symbols with no multicolor fills. Keep arrows as directional punctuation and avoid adding an icon to every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Low-slung illustrated cover

**Observed:** A flat Pastel cover fills the first 900px. Back to front: colored ground, expanded identity and sparse Navigation at the top, then a bottom-aligned twelve-column composition. The display headline occupies seven columns on the left but its visible lines span about half the page; it begins around the lower middle and runs over three lines. The Primary button sits 32px below. A transparent 443px by 464px ink drawing occupies the final four columns, aligned to the lower right with 32px breathing room below. The upper middle remains largely empty. Within 900px the identity, full headline, action and full drawing are visible; section labels and explanatory paragraphs begin below the fold. There is no support paragraph in the opening.

**Transfer:** Write one short durable promise and pair it with a bespoke metaphor drawing. Without product media, use Human ingenuity ink drawings rather than an empty visual slot. Case-study and company openings use the scoped pastel cover, omit the main action and end the main hero around 786px so the first section label can appear within the first screen.

**Avoid:** Do not center the headline over the illustration, fill the open upper region with badges or introduce a dense support paragraph beside the action.

**Text style:** `display` — Lausanne 400 · 72px/1 · tracking -0.01em

### Ruled editorial introduction

**Observed:** Ruled chapter carries a section label, then a 72px gap to a heading. A five-column text block pairs with a six-column visual at the far right. Supporting body-lead copy sits 48px below the heading, then an Arrow text link; Capability lozenges supply a word-based visual alternative to photography.

**Transfer:** Use this pattern to explain the offer's complementary strengths with compact words rather than a feature-card matrix.

**Text style:** `heading` — Lausanne 400 · 48px/1.17 · tracking -0.005em

### Proof rail

**Observed:** A section label and 48px heading introduce the Media rail cards. An Arrow text link sits opposite two Circular controls above the media; 24px-gap cards continue beyond the right edge.

**Transfer:** Use for customer stories, applications or examples, with concise captions.

**Text style:** `heading` — Lausanne 400 · 48px/1.17 · tracking -0.005em

### Illustrated quotation

**Observed:** A ruled, roughly 699px-tall chapter gives a 559px-wide drawing the left side and a five-column quotation the right. The quotation uses heading type; attribution uses attribution type with an Arrow text link beneath. The composition has about 120px of breathing room above and below the main content.

**Transfer:** Use one substantive human statement and a related conceptual drawing, not a logo wall or a testimonial card.

**Text style:** `heading` — Lausanne 400 · 48px/1.17 · tracking -0.005em

### Paired human proof

**Observed:** Below a section label, a large heading sits left and a short body paragraph sits right. An Arrow text link appears under the heading, followed by two equal 3:2 photographs across the full width.

**Transfer:** Give the new offer a human context through a portrait and a working detail.

**Text style:** `heading` — Lausanne 400 · 48px/1.17 · tracking -0.005em

### Illustrated contact and identity reveal

**Observed:** A 553px-tall pastel contact band uses 160px top and 40px bottom padding. A two-line 48px statement sits left, with a Primary button around 80px beneath it; a 449px-wide transparent drawing anchors the right. The statement visibly names complementary disciplines first and then gives the short synthesis line. Identity footer follows on charcoal, revealing the utility row and oversized cream lockup.

**Transfer:** Close with two complementary ideas and a concise synthesis in the new voice, then repeat the main contact action. Carry the same illustration language and identity scale through the final moment.

**Text style:** `heading` — Lausanne 400 · 48px/1.17 · tracking -0.005em

### Case-study rows

**Only for:** case-study index pages

**Observed:** Each broad ivory row begins with a 1px top rule and 32px top padding. A logo, 20px body description and a small row of regular Arrow text links sit on the left; a 676px-wide rounded documentary photograph occupies the right. Rows are separated by generous open space rather than filled cards.

**Transfer:** Give each example a clear identity, what it does, who benefits and links to learn more; preserve text-left and image-right alignment.

### Expertise and criteria

**Only for:** company and capability pages

**Observed:** Three equal ruled columns combine 48px titles with 22px descriptions. A later criteria chapter uses Numbered criterion in four columns, followed by a large quotation set apart with substantial vertical space.

**Transfer:** Separate broad capabilities from specific qualification or process criteria; retain the distinction between large titles and small numbered statements.

**Text style:** `heading` — Lausanne 400 · 48px/1.17 · tracking -0.005em

## Page flow

**Storyline:** Durable promise → explanation of complementary strengths → tangible proof → human conviction → invitation → oversized identity sign-off.

### A relationship-led marketing landing page

1. **Promise** — Pastel illustrated cover with one concise statement and a contact action.
2. **Capabilities** — Ruled introduction paired with capability words.
3. **Proof** — Horizontal photographic story rail.
4. **Human conviction** — Illustrated quotation followed by paired people and working-detail photography.
5. **Closing call** — Pastel illustrated contact band and reversed identity footer.

**Transfer:** Replace the subject matter with the product's promise, expertise and proof; preserve the visual devices without treating the exact sequence as compulsory.

### An index of customer stories or applications

1. **Promise** — Salmon cover with headline and ink illustration.
2. **Proof chapters** — An index label introduces five spacious ruled text-left/photo-right rows with logos and outbound links.
3. **Closing call** — Salmon contact band followed by the common charcoal identity footer.

**Transfer:** Let the repeated examples do the persuading; do not add unrelated pricing or feature panels to this editorial index.

### A company, people or expertise story

1. **Positioning** — Periwinkle cover with a people-led promise and ink drawing.
2. **Capabilities** — Three ruled expertise columns.
3. **Human proof** — Narrative beside a large team photograph and compact disclosure roster.
4. **Qualification** — Four numbered criteria and a spacious human quotation.
5. **Closing call** — Periwinkle contact band and the same reversed identity footer.

**Transfer:** Use real people, meaningful operating principles and concise criteria suited to the new organization.

## Writing

Assured, collaborative and plain-spoken, with just enough conceptual language to make expertise feel imaginative. Confidence comes from explaining a practical approach rather than superlatives.

**Do not copy:** Do not reuse the Dovetail name, symbol, wordmark, commissioned artwork, company names, contact details, investment criteria, financial claims or attributed quotations. Source examples illustrate tone only.

- **Addressing the reader:** Use 'we' for the team and 'you' or 'your business' when describing collaboration. Descriptions of examples are factual third person.
- **Rhythm:** Headlines are short sentence-case statements, often balancing two ideas. Support paragraphs explain concrete work in complete sentences; the ending uses short fragments followed by a synthesis line.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct statement of what we enable, with a durable outcome. | 7–12 words | “We invest in tech‑enabled companies that last” |
| Section statement | Two complementary forces joined in a balanced sentence. | 6–10 words | “Driven by people, enabled by technology” |
| Supporting explanation | Name the resources combined, then state the practical benefit. | One substantial sentence or a short paragraph | “Combining capital with hands-on experience in technology, design, strategy and finance, [Brand] enables ambitious businesses to reach their highest potential in the digital landscape.” |
| Primary action | Short, human invitation rather than a transactional command. | 3–4 words | “Get in touch” |
| Section label | Plain descriptive noun phrase. | 2–4 words | “What we look for”<br>“Our portfolio companies” |
| Closing message | Pair concrete disciplines, then conclude with a memorable synthesis. | Two short lines | “Finance and strategy. Tech and design.”<br>“[Brand] puts two and two together.” |

**Words and phrasing to use:** hands-on; enabled by; partners with; long-term; together; potential; build; practical discipline names

**Avoid:** disrupt everything; 10x; game-changing; revolutionary; crush the competition; exclamation-led sales language

**Rules:**

- Explain who benefits and how before adding abstract ambition.
- Balance human intent with concrete technical or operational competence.
- Keep section labels literal even when the larger headline is conceptual.
- Use quotations as substantive statements of approach, not unsupported praise.

## Do's and Don'ts

### Do

- Keep the opening headline at 72px/1 and weight 400, with deliberate line breaks.
- Use 32px side padding and 24px grid gutters at the main desktop width.
- Make 48px/1.17 regular statements the dominant editorial heading size.
- Use 1px top rules to organize ivory chapters and repeated rows.
- Preserve 16px corners on rectangular photographs, with captions outside the image.
- Keep the main action a dark 48px-high lozenge with 28px semibold lettering.
- Give the closing identity a 400px charcoal field and near-full-width cream lockup.
- Retain both bespoke ink artwork and real-world photographic proof in the visual language.

### Don't

- Do not turn 22px bold section labels into tiny uppercase mono eyebrows.
- Do not promote weight 700 into the 48px and 72px headline roles.
- Do not spread all three pastel themes through a single default landing page; yellow is the default bookend color.
- Do not use pure white as the reading ground; keep the warm ivory character.
- Do not surround the proof rail with raised panels, drop shadows or nested card borders.
- Do not put white text over documentary photography; keep captions below the media.
- Do not make all action controls 48px high; the navigation action is 32px high.
- Do not reduce the footer to a small logo and link list; its oversized identity is a defining device.

## Motion and responsive

### Motion

**Observed:**

- Declared action color transitions use 0.15s cubic-bezier(0.4, 0, 0.2, 1); opacity transitions use the same duration and curve.
- The expanded opening identity becomes compact on scroll, and the contact action and bottom navigation rule become visible.
- The photographic rail is draggable. Disclosure controls have declared transform transitions; open states reveal additional biography content.
- The footer is fixed behind the main page with a 400px reveal space.

**Transfer:**

- Carry the identity contraction and footer reveal into the new implementation; keep both endpoints fully legible.
- Use the declared short transitions for color and opacity changes rather than giving the ink artwork continuous decorative animation.

**Unknown:**

- Scroll interpolation, exact identity scaling timing and disclosure easing are not established.
- No specific focus-visible design is established.

### Responsive

**Observed:**

- Declared width breakpoints are 520px, 640px, 768px, 1024px, 1280px and 1536px.
- Wide navigation is declared for desktop; narrower layouts declare stacked content and a rail-card basis of eleven twelfths of the available width.

**Transfer:**

- On narrow screens, stack promise then illustration, preserving the open pastel stage and the independent visual silhouette.
- Collapse paired photography and text/image rows into a reading-order stack; keep horizontal proof browsing rather than miniaturizing all cards into a row.
- Fit the footer identity proportionally to the viewport, preserving its unusually large share of the ending.

**Unknown:**

- Exact mobile typography, header expansion, menu behavior and final spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
