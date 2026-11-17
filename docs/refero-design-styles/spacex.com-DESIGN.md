# SpaceX — engineering at cinematic scale

## Overview

A black-ground, image-led style that makes complex engineering feel tangible and consequential. Narrow industrial sans-serif capitals sit over expansive photography and stark product renders, with cool white text and almost no decorative color. It suits ambitious hardware, infrastructure and technically substantial products: the atmosphere is monumental, while the reading density stays low.

### Essentials

- The product is an event, not a card: a full-bleed 900px opening places a 60px/0.9 uppercase headline in the lower-left over an operational scene, with a 16px monospace date above and one outlined action below.
- Headlines behave like industrial signage: D-DIN bold capitals, normally 48px/1 with 0.02em tracking; the opening uses -1px tracking and the larger mission statement uses 80px/0.95.
- The interface stays monochrome while the world supplies color: #000000 canvas and #f0f0fa text throughout; blues, amber light and natural terrain belong in imagery, not colored UI bands.
- Actions are small instruments against immense scenes: 50px-high rectangles with 4px corners, 1px translucent white borders, 20px horizontal padding, 12px uppercase text and a 16px right arrow.
- Every page needs a cinematic scale contrast: imagery fills the width while supporting copy stays near 416px and heading groups near 450px. Use a real product-in-use photograph, a carefully lit render, or a tightly framed material study when expansive footage is unavailable.
- Scenes dissolve into darkness rather than ending in containers: directional black gradients reach 80% opacity at the text edge, and bottom fades merge media into the black canvas; footer navigation compresses to a 72px strip.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool white | `#f0f0fa` | `--color-text` | text, action, link, surface | Main headings, body, icons and the rare filled conversion action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-canvas` | background, surface, text | Unbroken page canvas, media backing and dark text on light actions. |
| Social disc | `#181819` | `--color-social-fill` | surface | Social button fill; rgba(240, 240, 250, 0.1) over black. |
| Technical rule | `#48484b` | `--color-table-rule` | border | Specification row separators; rgba(240, 240, 250, 0.3) over black. |
| Action outline | `#545458` | `--color-action-edge` | border | Button outlines; rgba(240, 240, 250, 0.35) over black, remaining translucent over media. |
| Muted white | `#78787d` | `--color-muted` | text | Technical eyebrows and low-priority closing text; rgba(240, 240, 250, 0.5) over black. |
| Secondary white | `#c0c0c8` | `--color-secondary` | text | Supporting technical copy and stat labels; rgba(240, 240, 250, 0.8) over black. |
| Navigation white | `#d8d8e1` | `--color-navigation` | text, link | Navigation labels; rgba(240, 240, 250, 0.9) over black. |
| Diagram white | `#ffffff` | `--color-white` | text, border, accent | Technical diagrams, tab labels, selected tab underlines and the tall closing rule. |

## Typography

- **D-DIN** — All marketing headings, paragraphs, navigation and actions; bold cuts belong to the same family. Narrow industrial sans-serif with compact capitals, plain terminals and a utilitarian regular cut. If unavailable, use **Barlow Semi Condensed**. Use 400 for text and 700 for display; preserve compact widths and the separate tracking recipes. Font stack: "D-DIN", "Barlow Semi Condensed", Arial, Verdana, sans-serif.
- **Roboto Mono** — Date markings and technical chapter eyebrows. Regular monospaced lettering, used sparingly to distinguish metadata from prose. Font stack: "Roboto Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | D-DIN | 700 | 80px | 0.95 | 0.02em, uppercase | One dominant belief or benefit statement, broken into emphatic stacked lines. |
| opening-title | D-DIN | 700 | 60px | 0.9 | -1px, uppercase | Lower-left event or release title in the default cinematic opening. |
| heading | D-DIN | 700 | 48px | 1 | 0.02em, uppercase | Default capability and product chapter heading. |
| heading-open | D-DIN | 700 | 48px | 1.25 | 0.02em, uppercase | Airier multi-line capability headings beside full-bleed scenes. |
| body | D-DIN | 400 | 16px | 1.5 | normal | Default support paragraphs and short explanatory text. |
| date | Roboto Mono | 400 | 16px | 1.4 | normal, uppercase | Date or release marking immediately above an opening title. |
| navigation | D-DIN | 700 | 13px | 0.94 | 0.09em, uppercase | Compact top navigation. |
| action | D-DIN | 400 | 12px | 1 | normal, uppercase | Outlined and filled action labels. |
| footer | D-DIN | 400 | 12px | 2 | normal, uppercase | Utility links and copyright on the footer strip. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company proof bands | stat-number | D-DIN | 400 | 140px | 1 | normal | Oversized centered proof numerals. |
| experience overview pages | experience-title | D-DIN | 700 | 100px | 0.95 | -1px, uppercase | Centered immersive category opening. |
| heritage timelines | timeline-heading | D-DIN | 700 | 46px | 50px | 0.02em, uppercase | Centered closing history statement. |
| recruitment closings and equipment galleries | small-heading | D-DIN | 700 | 24px | 1 | 0.02em, uppercase | Centered recruitment close or equipment category title. |
| technical product explainers | feature-title | D-DIN | 700 | 20px | 1.2 | 0.02em, uppercase | Small icon-led feature headings. |
| company proof bands | stat-label | D-DIN | 400 | 20px | 1.2 | normal, uppercase | Secondary labels directly beneath proof numerals. |
| heritage timelines | timeline-year | D-DIN | 400 | 20px | 1.2 | 0.02em, uppercase | Year overlaid above a milestone caption. |
| editorial and specification-led pages | editorial-body | D-DIN | 400 | 16px | 26px | normal | Longer company-story or product-detail paragraphs. |
| technical product explainers | feature-body | D-DIN | 400 | 15px | 1.5 | normal | Secondary copy in compact feature grids. |
| technical product explainers | technical-eyebrow | Roboto Mono | 400 | 14px | 24px | 0.08em, uppercase | Muted technical chapter introduction. |
| specification-led pages | metric-label | D-DIN | 400 | 14px | 24px | normal, uppercase | Left-hand labels in technical specification rows. |

**Notes:**

- Bold display cuts have real visual weight 700; regular body and button labels remain 400. Do not use the narrowness of the face as a reason to inflate text size.
- Most display tracking is positive 0.02em, unlike the tight -1px opening and immersive category titles. Navigation is more widely tracked at 0.09em.
- Use line breaks to make compact blocks of capitals, not paragraphs stretched across the scene. Body text stays sentence case even when headings and actions are uppercase.

## Layout

**Density:** Airy at the scene level, compact inside text groups: almost-screen-height imagery surrounds short stacks of text and restrained controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small feature heading-to-copy gap. |
| 12px | Technical eyebrow bottom gap and footer top/bottom inset. |
| 15px | Main heading-to-description gap. |
| 16px | Icon-to-copy spacing and paired action gap. |
| 20px | Button side padding and specification row vertical padding. |
| 30px | Standard action separation from preceding copy and carousel slide gap. |
| 36px | Footer link spacing. |
| 48px | Feature grid row gap. |
| 60px | Opening and footer side inset. |
| 75px | Proof band vertical space and editorial closing separation. |
| 100px | Standard chapter side inset and compact explanatory band vertical padding. |
| 120px | Feature grid column gap and recruitment closing breathing room. |

### Containers and grids

- **cinematic-stage**: max width 1700px · side padding 100px. Centered overlay content on full-width media. Desktop chapters are commonly 941px high; media covers the full width outside the content container.
- **opening-overlay**: max width 802px · side padding 60px. Lower-left event opening; the visible title block occupies about half the width.
- **copy-column**: max width 450px. Default chapter heading group; paragraphs within it cap at 416px. Alternate the group between left and right to preserve the subject.
- **editorial-stage** (only for editorial and specification-led pages): max width 1400px · side padding 20px. Wide technical and editorial sections, with detail copy groups up to 520px.
- **feature-grid** (only for technical product explainers): 2 columns · gap 120px · side padding 100px. Two columns of icon-led features with 48px row gaps.
- **proof-band** (only for company proof bands): max width 940px · 3 columns. Three centered, equal-weight statistics on black.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action | 4px |
|  | social | 50% |
| technical constraint navigation | chapter-jump | 24px |

## Surfaces and depth

### Surfaces

#### Black canvas · level 0

**Use:** All page backgrounds and the backing for isolated objects.

**CSS:** `background: #000000; color: #f0f0fa`

**Observed:** No elevated panel system or drop shadows separates ordinary chapters.

**Transfer:** Let empty black space connect otherwise different scenes.

#### Directional media veil · level 1

**Use:** Protect text over full-bleed media.

**CSS:** `background-image: linear-gradient(90deg, rgba(0, 0, 0, 0) 50%, rgba(0, 0, 0, 0.8) 100%)`

**Observed:** The dark edge follows the copy: reverse to 270deg for left-side text. The subject remains clearer on the opposite half.

**Transfer:** Place this layer above media and below copy, never over the text itself.

#### Bottom dissolve · level 1

**Use:** Merge a scene into the Black canvas.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0) 50%, #000000 100%)`

**Observed:** The top half stays clear; the lower half darkens to solid black.

**Transfer:** Use a continuous dissolve instead of a hard frame or rounded image boundary.

#### Navigation veil · level 2

**Use:** Keep the fixed navigation legible without an opaque bar.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0.6) 0%, rgba(0, 0, 0, 0) 95%)`

**Observed:** A shallow dark-to-clear header treatment is complemented by a broader top shadow over the scene.

**Transfer:** Keep navigation visually part of the media stage.

## Components

### Fixed navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; height: 74px; padding: 24px 40px; display: flex; align-items: center; column-gap: 30px; z-index: 100`

**Text style:** `navigation` — D-DIN 700 · 13px/0.94 · tracking 0.09em · uppercase

**Observed:** Wordmark at left, a single compact line of uppercase categories in the middle, and a small outlined status selector at right. Category links have an 18px gap; small chevrons indicate expandable groups.

**Transfer:** Use the new identity and a short category vocabulary; maintain the low, technical profile.

### Outlined action

**Use:** Default action on cinematic and black sections.

**CSS:** `display: inline-flex; align-items: center; height: 50px; padding: 0px 20px; background: rgba(0, 0, 0, 0.5); color: #f0f0fa; border: 1px solid rgba(240, 240, 250, 0.35); border-radius: 4px; transition: background-color 0.5s cubic-bezier(0.19, 1, 0.22, 1)`

**Text style:** `action` — D-DIN 400 · 12px/1 · uppercase

**Observed:** Label precedes a thin right arrow. Width follows the label rather than stretching to the copy column. A product-launch variant pairs it with a cool-white filled action and dark text, separated by 16px.

**States:** Declared: hover background-color #f0f0fa; focus-visible not specified.

**Transfer:** Keep one decisive verb; use the filled companion only for a second, higher-commitment conversion.

### Utility footer

**Use:** Shared understated page ending.

**CSS:** `display: flex; justify-content: space-between; align-items: center; margin: 12px 60px; color: #f0f0fa`

**Text style:** `footer` — D-DIN 400 · 12px/2 · uppercase

**Observed:** A 72px black strip contains Social disc at left, a centered line of utility links spaced 36px apart, and copyright at right. It follows the last scene directly on general landing pages.

**Transfer:** Keep it a single utility strip rather than expanding it into a directory.

### Social disc

**Use:** Single social destination at the footer's left edge.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; width: 48px; height: 48px; background: rgba(240, 240, 250, 0.1); border-radius: 50%; color: #f0f0fa`

**Observed:** One tiny 12px solid social mark sits at the center.

**Transfer:** Use one relevant social symbol without a text label inside the disc.

### Specification row

**Only for:** specification-led pages

**Use:** Compare technical attributes without card chrome.

**CSS:** `padding: 20px 0px; border-bottom: 1px solid rgba(240, 240, 250, 0.3); color: #f0f0fa`

**Text style:** `metric-label` — D-DIN 400 · 14px/24px · uppercase

**Observed:** Uppercase attribute at left, sentence-case value aligned right, sometimes wrapping to a short explanation. Rows sit in a 420px–450px column directly under category controls; values use regular body type.

**Transfer:** Use few meaningful specifications and preserve units rather than turning each number into an isolated tile.

### Inline tabs

**Only for:** interactive technical galleries

**Use:** Switch technical scene or configuration.

**CSS:** `color: #ffffff; opacity: 0.3; margin: 0px 10px; transition: opacity 0.3s; font-weight: 600; line-height: normal; text-transform: uppercase`

**Text style:** `body` — D-DIN 400 · 16px/1.5

**Observed:** Unselected labels are dim; the selected label is bright with a 1px underline. Another technical variant uses the Outlined action geometry, filling the selected rectangle in cool white.

**States:** Declared: hover opacity 1; focus-visible not specified.

**Transfer:** Use the inline form for editorial galleries and the rectangular form for product modes.

### Icon feature

**Only for:** technical product explainers

**Use:** Compact technical reassurance between large media chapters.

**CSS:** `display: flex; align-items: flex-start; gap: 16px`

**Text style:** `feature-title` — D-DIN 700 · 20px/1.2 · tracking 0.02em · uppercase

**Observed:** A small 32px technical icon sits beside a heading and secondary paragraph. Four items form two columns, with no containing card or border; the paragraph uses feature-body.

**Transfer:** Express engineering advantages with literal, restrained icons rather than badges.

### Milestone slide

**Only for:** heritage timelines

**Use:** Visual proof at the end of a long narrative.

**CSS:** `position: relative; width: 550px; height: 300px; margin-right: 30px; background: #000000`

**Text style:** `timeline-year` — D-DIN 400 · 20px/1.2 · tracking 0.02em · uppercase

**Observed:** A darkened edge-to-edge documentary photograph carries a year and short lower-left caption. A partial next slide remains visible; white chevrons sit near the outer edges and a centered row of small pagination dots sits below.

**Transfer:** Use a real progression of evidence and a short factual caption for each milestone.

### Proof numeral

**Only for:** company proof bands

**Use:** Quantified credibility without charts.

**CSS:** `display: flex; flex-direction: column; text-align: center; color: #f0f0fa`

**Text style:** `stat-number` — D-DIN 400 · 140px/1

**Observed:** A regular-weight monumental number sits directly above a stat-label in secondary white. Three statistics are centered in one horizontal band with 75px vertical space.

**Transfer:** Use verified totals and concise noun labels; the contrast is size rather than weight or color.

### Closing rule

**Only for:** company-story closings

**Use:** Quiet lead-in to email signup and practical contact details.

**CSS:** `width: 1px; height: 160px; background: #ffffff; margin-bottom: 20px`

**Observed:** A centered vertical hairline descends into black space above a brief signup invitation, a horizontal email field and compact submit action. Muted supplier and legal contact copy sits below.

**Transfer:** Use the same vertical pause before a single low-pressure way to stay informed, not a multi-field lead form.

## Imagery and graphics

### Operational cinema

**Use:** Opening and recurring full-bleed capability chapters.

**Observed:** Real machines and people are shown in action: aerial launch infrastructure, sea horizons, bright exhaust, helmet close-ups and night facilities. Subjects are large or dramatically dwarfed by their environment; natural blue, orange and earth tones remain inside the image. Text occupies one side while imagery covers the entire stage.

**Transfer:** Photograph the product doing real work at an unusual scale or angle. The minimum equivalent is a high-resolution, purposeful process photograph with usable negative space; treat it with Directional media veil and Bottom dissolve rather than a decorative collage.

### Dark product monument

**Use:** Signature contrast to operational scenes, including a large aspirational statement and final capability scene.

**Observed:** A planet, satellite, capsule or metallic structure emerges from near-black backing. Surfaces are cool silver or deep blue, with narrow rim light and occasional warm sunlight. Objects dominate one half or span diagonally across the full stage while their edges fade into the page.

**Transfer:** Stage the new product as one substantial object, not a floating collection of UI cards. For software, a single sharply framed interface or a close view of the physical system it enables can carry the same scale contrast.

**Build:** Use one clean alpha-masked product render on black, enlarged to roughly half the stage or crossing it diagonally. Add a soft backlight behind one edge with a radial-gradient from rgba(240,240,250,0.2) to rgba(0,0,0,0), plus a narrow brighter rim painted into the render. Mask the bottom with Bottom dissolve. Preserve real material texture; a flat silhouette alone is insufficient.

### Technical line diagrams

**Only for:** technical and experience explainers

**Use:** Explain systems, routes or relationships as a change of pace from photography.

**Observed:** Fine white and gray arcs, dashed trajectories, sparse uppercase callouts and simple white silhouettes sit directly on black. A destination diagram uses nested orbit circles and strongly contrasting globe shapes; a process diagram uses a sweeping trajectory with small stage markers.

**Transfer:** Translate the product's own process into a readable spatial diagram rather than borrowing astronomical subjects.

**Build:** Create an SVG with no panel fill, 1px white strokes at reduced opacity for secondary paths, dashed arcs for guides, and bright simple silhouettes at key nodes. Use thin elbow leaders to small uppercase labels and leave substantial empty black space between nodes.

### Isolated equipment gallery

**Only for:** equipment and experience overview pages

**Use:** Detail inspection and alternating product chapters.

**Observed:** White garments, capsules and metallic cutaways are isolated on black, sometimes with faint gray floor light. One tall centered object or a large half-width object is paired with sparse specifications; no rounded image frame surrounds it.

**Transfer:** Use front, side or cutaway views consistently and light them like engineered artifacts, not colorful retail packshots.

### Documentary proof strip

**Only for:** heritage timelines

**Use:** Closing milestone carousel.

**Observed:** Wide real-world photographs are dimmed behind year labels and short captions. Multiple frames sit side by side with a clipped next item, black gaps and no outer card radius.

**Transfer:** Use dated product launches, deployments or independent demonstrations as the photographic evidence.

### Icons

**Observed:** Navigation chevrons are tiny white 9px outline marks; action arrows fit 16px squares. Standalone carousel arrows use 2px round strokes in 25px × 30px boxes. Feature icons are 32px technical line drawings, not colorful pictograms.

**Transfer:** Use a consistent small monochrome set with thin strokes and round caps where appropriate. Reserve large icons for diagram content; keep action arrows subordinate to the label.

## Section recipes

How recurring sections are built.

### First screen: Operational opening

**Observed:** A full-width 900px media stage fills the first screen. Back to front: Black canvas, an aerial operational scene with a large central subject, Bottom dissolve, a low-left title stack, and Fixed navigation above. The title group is inset 60px from the left and occupies about half the width; the date sits around the lower third boundary, then the 60px capital headline and a separated Outlined action. At 900px, navigation, date, title, action and the main object are all visible. There is no supporting paragraph in this opening and no preview of the next chapter above the fold.

**Transfer:** Lead with a launch, release or product-in-action image that earns the scale. Without footage, use an equally strong still or Dark product monument with the same asymmetric text staging. A product-specific launch may instead use a 48px heading, one support sentence and paired actions at mid-left; an experience overview centers the 100px experience-title over a dimmed human scene; a company story can open with a centered short quotation over an expansive horizon.

**Avoid:** Do not replace the scene with a centered SaaS headline, dashboard card and colorful gradient background, or add a paragraph that crowds the date/title stack.

**Text style:** `opening-title` — D-DIN 700 · 60px/0.9 · tracking -1px · uppercase

### Aspirational monument

**Observed:** A nearly screen-height black stage pairs a large object on the right with the 80px statement on the left. The heading stacks in short lines, body copy stays at 416px and one Outlined action follows with 30px separation.

**Transfer:** State the larger benefit in a few strong words and pair it with one convincing visual metaphor grounded in the product.

**Text style:** `statement` — D-DIN 700 · 80px/0.95 · tracking 0.02em · uppercase

### Alternating capability scene

**Observed:** Full-bleed media chapters are commonly 941px high. A 450px text group sits about 100px from a side and roughly 120px below the top, switching sides to match the clear image area. A heading, short paragraph and Outlined action sit over Directional media veil; some lower compositions use Bottom dissolve instead.

**Transfer:** Let each scene explain one capability, choosing the text side from the image composition rather than enforcing a mechanical zigzag.

**Text style:** `heading` — D-DIN 700 · 48px/1 · tracking 0.02em · uppercase

### Technical inspection

**Only for:** technical product explainers

**Observed:** Black canvas holds a left 420px text column, compact rectangular mode selectors and Specification rows; a large isolated technical render occupies the right half. Successive modes show whole-object, thermal and surface-detail views without changing the surrounding visual language.

**Transfer:** Use a small number of genuinely different product views, keeping text, units and controls stable while the main object changes.

### Engineering reassurance band

**Only for:** technical product explainers

**Observed:** A short black band with 100px vertical padding contains the two-column Icon feature grid, 120px column gaps and 48px row gaps. Another short band pairs a compact constraint statement with three outlined 50px-high chapter-jump pills with 24px corners.

**Transfer:** Use this denser interlude to explain underlying strengths or let readers jump into a few difficult problems; keep it visually secondary to the media chapters.

### Diagram and comparison chapter

**Only for:** editorial and specification-led pages

**Observed:** A centered 48px heading and short explanation introduce a large white-on-black technical diagram with inline category tabs. Elsewhere, a square operational video occupies slightly more than half the stage beside a compact prose column.

**Transfer:** Make the mechanism comprehensible with a simple diagram or comparison, retaining the sparse black backing rather than adding a dashboard.

### Experience gallery

**Only for:** experience overview pages

**Observed:** Large photographic slides with short lower-left headings lead into a black-ground destination diagram, tabbed Specification rows beside human imagery, and an isolated equipment display. The equipment title is only 24px, leaving the object to supply the spectacle.

**Transfer:** Move from the human experience to choices, measurable detail and physical equipment without giving every chapter another oversized title.

### Recruitment close

**Only for:** recruitment-oriented product pages

**Observed:** After a final image scene, 120px of breathing room surrounds a centered small-heading, a support sentence 14px below it and one Outlined action 21px below the sentence. Utility footer follows.

**Transfer:** Offer a specific way to contribute; let the closing invitation shrink in size after the monumental scenes.

**Text style:** `small-heading` — D-DIN 700 · 24px/1 · tracking 0.02em · uppercase

### Company contact close

**Only for:** company-story pages

**Observed:** The last full-bleed capability image gives way to Black canvas, Closing rule, a centered email signup and muted practical contact text, then Utility footer. The form is visually compact and horizontal, with an outlined field and separate submit rectangle.

**Transfer:** End an editorial narrative with a low-pressure ongoing connection rather than a sales pitch.

### Heritage close

**Only for:** heritage and experience overview pages

**Observed:** A shallow panoramic horizon precedes the centered timeline-heading. A broad black pause separates it from the Milestone slide carousel; chevrons and pagination dots sit below the images, then Utility footer ends the page.

**Transfer:** Close with demonstrated progress rather than automatically appending a conversion banner.

**Text style:** `timeline-heading` — D-DIN 700 · 46px/50px · tracking 0.02em · uppercase

## Page flow

**Storyline:** Spectacle or conviction → tangible capability → technical credibility → wider consequence → a purposeful, restrained ending.

### Broad marketing landing page

1. **Immediate relevance** — A dated operational event and one viewing action.
2. **Ambition** — An oversized statement beside an isolated monumental object.
3. **Capability chapters** — Alternating full-bleed image scenes, each with one compact text group and action.
4. **Forward-looking close** — A final future-facing product scene dissolves directly into the utility strip.

**Transfer:** Use a few strong scenes to establish breadth; each scene should earn its own image rather than becoming a card in a grid.

### Technical product launch and recruitment

1. **Promise** — Product name and one-sentence benefit over a cinematic render with paired actions.
2. **Product demonstration** — Large isolated object with mode selectors and a stable specification column.
3. **Mechanism** — Close-up media explains how the system works, followed by an unboxed icon feature band.
4. **Feasibility** — Production-scale imagery and compact constraint navigation lead into detailed capability scenes.
5. **Objection handling** — A final responsibility or safety scene addresses consequences.
6. **Closing call** — Small centered recruitment invitation, one action and the utility strip.

**Transfer:** Treat difficult engineering questions as the story's substance, then invite participation only after establishing credibility.

### Company mission and credibility narrative

1. **Conviction** — Centered quotation over a large horizon rather than a sales headline.
2. **Quantified proof** — Three monumental regular-weight statistics on black.
3. **Ambition and history** — Large documentary and rendered scenes with compact explanatory prose.
4. **Mechanism** — Square operational video beside text, followed by an annotated process diagram.
5. **Real-world presence** — A final dramatic location photograph and action.
6. **Ongoing relationship** — Tall closing hairline, email signup, practical contact notes and utility strip.

**Transfer:** Tie a belief to tangible proof and explain the breakthrough before the understated contact ending.

### Immersive experience and offering overview

1. **Aspiration** — Centered monumental category title over human experience photography.
2. **Experience preview** — Large media carousel with short captions and audio/video controls.
3. **Choice architecture** — Spatial diagram leads to tabbed mission specifications.
4. **Product confidence** — Isolated equipment gallery and alternating technical product chapters.
5. **Participation** — A compact proposal or contribution chapter extends the offering beyond purchase.
6. **Historical proof** — Panoramic transition and milestone carousel lead straight to utility navigation.

**Transfer:** Start with what the experience feels like, then show choices, equipment and evidence; preserve the history-led ending when chronology matters.

## Writing

Declarative, technically grounded and future-facing. Large ambitions are expressed plainly, then supported by concrete systems, constraints, units and operational facts rather than lifestyle adjectives.

**Do not copy:** Do not reuse SpaceX names, wordmarks, vehicle designs, imagery, proprietary claims, mission dates, performance numbers, quotations or assertions of leadership. Replace them with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly third-person product and company statements; 'we' appears in technical explanations. Direct address is reserved for invitations such as joining, reserving or proposing work.
- **Rhythm:** Headlines are usually two to six words or a compact noun phrase. Support is typically one factual paragraph; longer editorial chapters may use several short paragraphs. Actions are brief uppercase verbs or verb phrases, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | Name the event, product or experience directly; let imagery provide drama. | 1–4 words | “Starship Flight 14”<br>“STARMIND” |
| Capability heading | Active verb plus a consequential outcome, or a direct technical noun phrase. | 2–6 words | “Revolutionizing space technology”<br>“Laser Connectivity” |
| Technical support | Describe a mechanism and its practical consequence in one factual statement. | 1–3 sentences | “We are AI chip vendor agnostic. Our system architecture supports compute modules from any provider.” |
| Primary action | A terse verb tied to the next actual destination. | 1–4 words | “RESERVE YOUR RIDE”<br>“Open Roles” |
| Closing invitation | Offer a concrete contribution to the larger goal. | 1 short sentence | “Help develop a truly scalable solution for the future of AI” |

**Words and phrasing to use:** develop; build; capable of; reusable; integrated; at scale; architecture; reliable; designed to; next generation

**Avoid:** magical; delightful; game-changing; effortless everything; your new best friend; emoji-led enthusiasm

**Rules:**

- Separate current capability from plans: use 'is capable of' for demonstrated facts and 'plans to' or 'is being designed' for future work.
- Use units and mechanisms to substantiate ambitious claims.
- Keep technical acronyms where useful and explain them on first introduction.
- Let headings establish direction and supporting paragraphs explain how; avoid repeating the heading as the first sentence.

## Do's and Don'ts

### Do

- Keep the default chapter title at 48px, bold, uppercase and 0.02em tracking.
- Keep default support at 16px/24px in a column near 416px.
- Preserve the 50px action height and restrained 4px corners.
- Use 60px side insets for the event opening and footer, and 100px for ordinary chapter overlays at desktop.
- Darken the text side of media with an 80% black edge while keeping the main object visible.
- Use 15px heading-to-body gaps and 30px separation before ordinary chapter actions.
- End broad landing pages with the final media scene and the compact 72px utility strip.
- Keep technical rows on black with 1px rules instead of turning their values into cards.

### Don't

- Do not introduce a brand-colored button or colored marketing band; interface color remains monochrome.
- Do not replace #000000 with a blanket charcoal or navy canvas; it weakens the seamless media dissolves.
- Do not use giant rounded corners on photographs or ordinary actions; 24px corners belong only to scoped chapter-jump pills.
- Do not make body copy bold or uppercase throughout; regular 16px sentence-case paragraphs supply the counterpoint to signage headings.
- Do not force all section headings into a single line across the screen; keep their compact 450px grouping.
- Do not add drop shadows or elevated gray feature cards to the icon grid.
- Do not make every action full-width or oversized; label-driven 50px controls are deliberately small beside the scenes.
- Do not replace the small utility strip with a multi-column sitemap or a large closing logo.

## Motion and responsive

### Motion

**Observed:**

- Outlined actions declare background-color 0.5s cubic-bezier(0.19, 1, 0.22, 1).
- Inline category controls and header declare opacity transitions of 0.3s.
- Additional declarations include opacity 0.4s ease-out, title and button reveals, and a 3s scroll indicator animation.

**Transfer:**

- Use the declared action transition for the light-fill hover change.
- Keep cinematic media and reveal effects subordinate to the readable title stack; preserve a useful still composition.

**Unknown:**

- The exact reveal sequence, video playback behavior, scroll triggers and durations of unlisted animations are not established.
- Focus-visible styling is not established; add an accessible treatment consistent with the monochrome controls.

### Responsive

**Observed:**

- Width breakpoints are declared near 600px, 960px, 1280px, 1350px and 1500px; the technical product page also declares 399px.

**Transfer:**

- On narrow screens, preserve the subject and dark text zone rather than merely center-cropping every scene.
- Reflow side-by-side detail columns into object plus text, retaining the specification row structure and the visual priority of the main object.
- Keep the distinction between the low-left event title, the centered experience title and the mid-left product-launch title.

**Unknown:**

- Exact mobile font sizes, side insets, navigation replacement and footer wrapping are not established; these reflow rules are design guidance, not fixed mobile measurements.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
