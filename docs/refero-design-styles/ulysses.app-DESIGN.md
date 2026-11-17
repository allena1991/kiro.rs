# Ulysses — charcoal with a yellow wink

## Overview

A friendly, tool-loving style that pairs pale desktop still lifes with long, warm-charcoal product chapters. Humanist sans-serif lettering, white interface imagery and tiny flashes of yellow make capable software feel approachable rather than technical. The spacious compositions suit creative tools and focused productivity products; portraits and softly outlined paper panels supply a human finish.

### Essentials

- A bright shop window leads into a charcoal workshop: a 644px pale opening and 100px acquisition strip give way to broad #3e3d3c and #373635 chapters, which occupy most of the product story.
- Headlines sound sturdy rather than monumental: 48px Interstate, weight 700, normal tracking and 1.04 line height in feature chapters; centered use-case headings pair weight 400 and 700 at 48px/1.15.
- The product is a real object, not a dashboard tile: large white application windows or device arrangements occupy roughly two thirds of feature compositions, extend beyond section edges and alternate sides with a narrow text column.
- Yellow behaves like a helpful pencil mark: #ffcc00 appears in tiny illustrations, hand-drawn corrections, 2px action outlines and footer links, never as a full-width marketing fill. Include a small annotation or diagrammatic accent as a signature device.
- Actions are modest rectangular outlines: 36px high, 2px borders, 3px corners and 15px medium labels; white outlines belong on charcoal and yellow outlines on pale surfaces.
- Useful detail gets its own visual language: 190px dark circular illustration backings introduce four-column benefit rows; the ending returns to warm paper, white 25px rounded panels and fine offset outlines. Preserve both the illustrated detail device and paper-panel finish, adapting their content freely.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pencil yellow | `#ffcc00` | `--color-yellow` | accent, border, action, link | Sparse illustration details, outline actions, fine link underlines, active-navigation marker and footer links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link black | `#000000` | `--color-black` | text | Brand lettering and the underlined acquisition link. |
| Footer charcoal | `#262626` | `--color-footer` | background | Shared closing directory. |
| Text ink | `#27272b` | `--color-ink` | text | Primary text on pale canvases. |
| Inset charcoal | `#31302f` | `--color-quote-dark` | surface | Wide testimonial inset on dark chapters. |
| Deep charcoal | `#373635` | `--color-charcoal-deep` | background, surface | Alternating product chapters and circular illustration backings. |
| Warm charcoal | `#3e3d3c` | `--color-charcoal` | background | Default product-story canvas. |
| Soft charcoal | `#454342` | `--color-charcoal-soft` | background | A third closely related tone separates illustrated capability chapters. |
| Paper rule | `#e2dcda` | `--color-rule` | border | Thin separator above the closing reassurance. |
| Soft rose-gray edge | `#e9e2e2` | `--color-panel-edge` | border | Visible panel edge on white, using rgba(181,159,158,0.3); retain the subtle offset-outline appearance. |
| Warm paper | `#f7f7f5` | `--color-paper` | background | Pale opening gradient endpoint and closing bands. |
| Cool story panel | `#f8f9fa` | `--color-story` | surface | Portrait-and-story carousel backing. |
| White | `#ffffff` | `--color-white` | background, surface, text, border | Navigation, paper panels, bright product imagery and reversed text and outlines. |

## Typography

- **interstate** — All marketing headings, paragraphs, navigation and actions. A humanist highway-sign sans with open forms, gently condensed proportions and a warm, sturdy bold. If unavailable, use **Overpass**. Use weights 300–700; retain normal tracking and test line breaks against the relatively narrow original. Font stack: "interstate", "Overpass", -apple-system, system-ui, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading-feature | interstate | 700 | 48px | 1.04 | normal | Short bold feature-chapter headlines on charcoal. |
| heading-light | interstate | 700 | 48px | 1.2 | normal | Opening promise, light social-proof headline and editorial introduction. |
| heading-pair-lead | interstate | 400 | 48px | 1.15 | normal | First line of a centered use-case heading. |
| heading-pair-emphasis | interstate | 700 | 48px | 1.15 | normal | Second line of the same centered use-case heading. |
| quote | interstate | 500 italic | 27px | 1.48 | normal | Centered press quotation in a white paper panel. |
| heading-small | interstate | 700 | 26.3px | 1.2 | normal | Story card title, conversion panel and closing reassurance; also names in a portrait directory. |
| body | interstate | 400 | 18px | 1.6 | normal | Opening support, illustrated benefit paragraphs and editorial body. |
| body-feature | interstate | 400 | 18px | 1.56 | normal | Narrow supporting paragraphs beside large product imagery. |
| navigation | interstate | 300 | 16px | 1.125 | normal | Small right-aligned header links; the current destination uses medium weight. |
| body-small | interstate | 400 | 15px | 1.6 | normal | Trial and story-card descriptions. |
| action | interstate | 500 | 15px | 1.334 | normal | Outline-button labels. |
| footer-link | interstate | 500 | 15px | 1.6667 | normal | Yellow directory links. |
| inline-action | interstate | 500 | 15px | 1.6 | normal | Black acquisition link with a yellow underline. |
| footer-label | interstate | 500 | 13px | 1.2 | 0.115em, uppercase | Spaced uppercase directory headings. |

**Notes:**

- Normal tracking is part of the character even at 48px; hierarchy comes from weight, line breaks and alignment rather than tightly compressed display text.
- Feature copy is slightly tighter than general body copy. Keep 1.56 for narrow feature paragraphs and 1.6 for editorial and illustrated benefits.
- The centered heading pair changes weight, not size. Do not turn its first line into an uppercase eyebrow.

## Layout

**Density:** Airy in the storytelling, compact in the navigation and footer; narrow paragraphs sit beside expansive media rather than filling the width.

### Spacing

| Value | Use |
| --- | --- |
| 15px | Paragraph separation and header vertical padding. |
| 20px | Desktop grid column gaps. |
| 25px | Portrait-to-name separation and dark inset padding. |
| 40px | Header side inset and footer label-to-link-list separation. |
| 45px | Paper-panel internal padding. |
| 50px | Feature heading-to-body and body-to-action gaps; wide-grid row rhythm. |
| 60px | Space after a portrait card. |
| 70px | Footer top and bottom padding. |
| 100px | Default major chapter top padding and light proof-section padding. |
| 120px | Illustrated chapter bottom padding. |

### Containers and grids

- **wide-story-grid**: max width 1190px · 12 columns · gap 20px. Centered desktop storytelling grid. A feature text block spans about four columns, approximately 383px, while its media occupies or spills beyond the other eight.
- **header-container**: max width 1920px · side padding 40px. Broad header with brand at left and compact navigation at right.
- **paper-content**: max width 960px · gap 20px. Centered press panels and narrower editorial compositions.
- **benefit-row**: max width 1190px · 4 columns · gap 0px. Four equal columns of about 298px; illustration and short left-aligned explanation within each column.
- **trial-panel**: max width 750px · 2 columns. Compact centered conversion panel; identity and acquisition badge at left, title and explanation at right.
- **portrait-directory** (only for team and company pages): max width 960px · 3 columns · gap 20px. Three square portraits across, about 307px wide, with names and roles beneath.

## Corner radius

| Element | Radius |
| --- | --- |
| outline-actions | 3px |
| story-and-inset-panels | 20px |
| paper-panels | 25px |
| illustration-discs | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation-halo | `0px 0px 34px 0px rgba(0,0,0,0.06)` | Only the white sticky header; broad and barely visible rather than a hard divider. |

### Surfaces

#### White canvas · level 0

**Use:** Navigation, human proof and editorial pages.

**CSS:** `background: #ffffff; color: #27272b`

#### Pale opening · level 0

**Use:** Bright opening stage.

**CSS:** `background: linear-gradient(221deg, #ffffff, #f7f7f5)`

**Observed:** Almost neutral, with no saturated gradient field.

**Transfer:** Keep the white-to-warm-paper difference subtle behind the product still life.

#### Charcoal chapters · level 0

**Use:** Main product storytelling.

**CSS:** `background: #3e3d3c; color: #ffffff`

**Observed:** Adjacent chapters alternate deep charcoal and occasionally soft charcoal without visible separator strokes.

**Transfer:** Use tonal steps to distinguish subjects, not a different chromatic theme for every feature.

#### Warm closing band · level 0

**Use:** Press quotation, acquisition panel and final reassurance.

**CSS:** `background: #f7f7f5; color: #27272b`

#### Outlined paper · level 1

**Use:** Press and acquisition panels.

**CSS:** `background: #ffffff; border-radius: 25px; padding: 45px; position: relative`

**Observed:** Fine rose-gray outlines are layered slightly out of register with the white rounded panel, creating a lightly stacked paper appearance.

**Transfer:** Add two absolutely positioned, pointer-inert pseudo-elements with 1px solid rgba(181,159,158,0.3) borders and 25px corners; offset one subtly from the other. Keep the edge delicate, not a drop shadow.

#### Dark quotation inset · level 1

**Use:** Wide testimonial inside a dark chapter.

**CSS:** `background: #31302f; border-radius: 20px; padding: 25px 174px 25px 49px`

**Observed:** A circular author portrait precedes italic white text, with bold attribution below and a large muted quotation mark at the far side.

**Transfer:** Use a single concise quotation and reserve enough trailing room for the decorative mark.

#### Story backing · level 1

**Use:** Human proof card.

**CSS:** `background: #f8f9fa; border-radius: 20px; overflow: hidden`

#### Directory band · level 0

**Use:** Shared footer.

**CSS:** `background: #262626; padding: 70px 0px; color: #ffffff`

## Components

### Sticky navigation

**Use:** Persistent brand and a few destination links.

**CSS:** `height: 70px; position: sticky; top: 0px; background: #ffffff; padding: 15px 0px; box-shadow: 0px 0px 34px 0px rgba(0,0,0,0.06); z-index: 1020`

**Text style:** `navigation` — interstate 300 · 16px/1.125

**Observed:** A small yellow emblem and black wordmark sit at the left. Text-only links align right; the active destination is medium weight with a thin yellow bottom marker.

**Transfer:** Keep the number of links small and omit a conspicuous filled header conversion button.

### White outline button

**Use:** Primary action within dark feature chapters.

**CSS:** `color: #ffffff; background: transparent; border: 2px solid #ffffff; border-radius: 3px; padding: 6px 36px; height: 36px; box-sizing: border-box`

**Text style:** `action` — interstate 500 · 15px/1.334

**Observed:** A compact, centered label remains subordinate to the product demonstration.

**States:** Declared: hover keeps white text and border with rgba(255,255,255,0.1) background; active adds a white 50%-alpha outer ring and removes the outline. Focus-visible treatment is unknown.

### Yellow outline button

**Use:** Story links and the closing update action on pale backgrounds.

**CSS:** `color: #27272b; background: transparent; border: 2px solid #ffcc00; border-radius: 3px; padding: 6px 13.2px; height: 36px; box-sizing: border-box`

**Text style:** `action` — interstate 500 · 15px/1.334

**Observed:** Width follows the label, from a short story action to a longer feature-update invitation. In the dark directory, the newsletter variant starts with white text and a regular-weight label.

**States:** Declared: hover retains dark text and yellow border with rgba(255,204,0,0.1) background; active adds a yellow 50%-alpha outer ring and removes the outline. Focus-visible treatment is unknown.

### Illustrated benefit

**Use:** Explain concrete tasks in a four-column group.

**CSS:** `width: 190px; height: 190px; background: #373635; border-radius: 50%; display: flex; align-items: center; justify-content: center`

**Observed:** The disc contains a small white line illustration with one yellow detail. An 18px explanation sits below, with selected phrases bolded; no enclosing rectangular card surrounds the copy.

**Transfer:** Use an object metaphor specific to each task. Keep diagrams compact and the text outside the disc.

### Press quote panel

**Use:** A brief authoritative pause in the product story.

**CSS:** `background: #ffffff; border-radius: 25px; padding: 45px; max-width: 960px; text-align: center`

**Text style:** `quote` — interstate 500 italic · 27px/1.48

**Observed:** Uses Outlined paper on the Warm closing band; the quote itself is limited to an 800px measure.

**Transfer:** Keep one or two lines of meaningful external assessment rather than a dense quote grid.

### Portrait story card

**Use:** A detailed customer example after a centered social-proof headline.

**CSS:** `background: #f8f9fa; border-radius: 20px; overflow: hidden; max-width: 988px; display: grid; column-gap: 64px; row-gap: 20px`

**Text style:** `heading-small` — interstate 700 · 26.3px/1.2

**Observed:** A 357px square portrait anchors the left. A title, 15px description and Yellow outline button fill the right. Three small yellow-toned indicators sit below the carousel.

**Transfer:** Use a real person and a concrete outcome; keep the image and text panel approximately equal in visual weight.

### Trial paper panel

**Use:** Low-pressure conversion near the end.

**CSS:** `background: #ffffff; border-radius: 25px; max-width: 750px; padding: 45px; display: flex`

**Text style:** `heading-small` — interstate 700 · 26.3px/1.2

**Observed:** Uses Outlined paper. The left half stacks a 100px product icon and a black acquisition badge; a fine vertical divider separates a heading and small explanation on the right.

**Transfer:** For products without an app-store badge, substitute a compact brand tile and similarly sized acquisition action, keeping the split-panel construction.

### Yellow underline link

**Use:** Inline acquisition action inside explanatory copy.

**CSS:** `color: #000000; box-shadow: 0px 2px 0px 0px #ffcc00; text-decoration: none`

**Text style:** `inline-action` — interstate 500 · 15px/1.6

**Observed:** The underline is a separate yellow rule under black medium text, not a filled badge.

**States:** Declared: hover changes text to rgb(103,102,101) without text decoration; active removes the outline. Focus-visible treatment is unknown.

### Footer link column

**Use:** Compact navigational directory in the closing band.

**CSS:** `color: #ffcc00; padding: 0px 10px`

**Text style:** `footer-link` — interstate 500 · 15px/1.6667

**Observed:** Three destination columns and one utility column occupy equal widths. Uppercase white Footer-label headings precede lists; yellow links follow a 25px vertical cadence. Utilities include the outlined newsletter action and small white social marks.

**States:** Declared: hover changes link text to rgb(103,102,101) and removes text decoration; active removes the outline. Focus-visible treatment is unknown.

**Transfer:** Group destinations by purpose, keeping the fourth column for subscription and utilities.

### Portrait directory card

**Only for:** team and company pages

**Use:** Introduce individuals without boxed biography cards.

**CSS:** `margin-bottom: 60px`

**Text style:** `heading-small` — interstate 700 · 26.3px/1.2

**Observed:** A square studio portrait is followed after 25px by a bold first name, then after 5px by an 18px regular role. No border, radius or tinted card surrounds the unit.

**Transfer:** Allow personal poses and a few props while maintaining a consistent background and crop.

## Imagery and graphics

### Bright device still life

**Use:** Default opening product stage.

**Observed:** A slightly rotated tablet, phone and pale keyboard form a large diagonal still life on the right, extending beyond the upper and right edges. Screens are white and legible, device rims are dark, and lighting is soft with restrained contact shadows. The left remains clear for the promise.

**Transfer:** Render the new product on believable devices or show a similarly crisp application-window arrangement. If device art is unavailable, one large bright interface plane with a smaller companion detail is the minimum equivalent; preserve the diagonal, edge overflow and pale backing.

### Oversized interface chapters

**Use:** Large alternating media beside feature explanations.

**Observed:** White application windows, dark library details, fanned export pages and multi-device arrangements dominate the dark chapters. Some details fade into charcoal at the edges; others float with natural window shadows. Decorative handwriting, faint orbit lines and angular landscape linework live behind them.

**Transfer:** Show the product doing the described task, not an unrelated abstract illustration. A well-composed static interface is sufficient; use edge masks to blend dark UI and keep light windows sharply readable.

### Pencil annotations and faint diagrams

**Use:** Signature playful layer across otherwise sober product compositions.

**Observed:** Sparse gray and pale-yellow characters float in the opening; a yellow handwritten correction with a small arrow modifies one feature headline. Dark chapters add low-contrast dashed arcs, manuscript strokes or angular linework behind the media.

**Transfer:** Include a small product-relevant correction, annotation or diagram in the visual story. It should feel like a marginal note, not an illustrated wallpaper.

**Build:** Use an SVG overlay spanning the media stage. Draw a few 1px gray paths at 0.15–0.3 opacity, with occasional dashed arcs and loose angular segments. Add one small hand-lettered yellow note or two-stroke curved arrow beside a headline; use #ffcc00 sparingly. On the pale opening scatter a handful of 18–24px rotated characters in muted gray and pale yellow, leaving the reading column unobstructed.

### Task line illustrations

**Use:** Illustrated benefit discs.

**Observed:** Simple white outline objects such as a drawer, notebook, clipboard, folder or progress ring are centered on dark circles, with a single yellow line or fill detail. Icons are substantially smaller than their 190px backings.

**Transfer:** Create an equivalent set using simple task-relevant objects, not generic colored app icons.

**Build:** Draw 65–85px SVG objects with roughly 2–3px white strokes, rounded joins and no shaded fills. Use one #ffcc00 stroke or small filled polygon inside each. Center each on a 190px #373635 circular backing.

### Output gallery

**Use:** Concrete evidence within an illustrated capability chapter.

**Observed:** A shelf-like row of colorful finished works shares a baseline on charcoal. The largest central item is flanked by progressively smaller pieces, producing a shallow arc and soft shared shadow.

**Transfer:** Show finished work or outputs in varied sizes rather than repeating equal product cards. Use real output thumbnails when available, retaining the shared baseline and restrained shadow.

### Human portraits

**Use:** Customer stories and company introductions.

**Observed:** Customer proof uses a candid color portrait cropped square. The company directory uses consistent waist-up, square studio portraits on pale cool-gray backgrounds, with relaxed poses, ordinary clothes and occasional personal props.

**Transfer:** Keep natural color and approachable expressions; use a consistent studio treatment for directories, not for every customer image.

### Waving hand accent

**Only for:** team and company pages

**Use:** Human editorial opening beside the introduction.

**Observed:** A large pale-yellow waving hand with a bright yellow edge, soft white highlights and loose motion strokes balances the text column.

**Transfer:** Use one friendly greeting object rather than a full product scene.

**Build:** Create a simple hand silhouette as SVG, pale yellow fill, a narrow bright-yellow offset edge and one white highlight shape. Add three curved gray and yellow movement lines outside the palm. Keep it on unboxed white space.

### Icons

**Observed:** Navigation uses a small solid brand emblem. Benefits use larger white line drawings with yellow details. Footer social and utility symbols are compact, mostly white, around 20–25px; they do not sit in colored rounded tiles.

**Transfer:** Keep utility icons monochrome and reserve two-tone white/yellow diagrams for explanatory content.

## Section recipes

How recurring sections are built.

### First screen: Bright product opening

**Observed:** A 70px Sticky navigation sits above a 644px Pale opening stage. The text occupies roughly the left two fifths of the viewport inside the centered content area: a bold 48px multiline promise above a short 18px support paragraph, with a generous gap. The right half is filled by Bright device still life, rotated diagonally and cut by the top and right edges. Back-to-front layers are the almost-white gradient, sparse Pencil annotations and faint diagrams, text, then crisp device art. The action is not a large hero button: a separate 100px white acquisition strip follows, pairing a black store badge and small trial note at left with muted award proof at right. Within the first 900px the complete headline, support, device stage, acquisition strip and the top of the charcoal story are visible; detailed feature content falls below.

**Transfer:** Start a new landing page with a concrete promise and a tangible product scene. Without device photography, compose a large bright interface plane and one supporting detail on the right, keeping the left reading zone and separate acquisition strip. Company or editorial pages use the same navigation but open on white with a left-aligned title, two short paragraphs and one friendly accent illustration.

**Avoid:** Do not center everything over a colorful gradient, place the main action in a pill inside the hero, or shrink the product to an equal-size thumbnail card.

**Text style:** `heading-light` — interstate 700 · 48px/1.2

### Alternating feature theater

**Observed:** Charcoal chapters use a 1190px wide-story-grid. A roughly 383px text column pairs Heading-feature with Body-feature and, where needed, White outline button. Heading-to-body and body-to-action gaps are about 50px. Large interface art takes the remaining width and may overflow the grid; media and text alternate sides. Top padding varies from 130px to 170px in these chapters.

**Transfer:** Give each major benefit a concrete demonstration; vary the media composition while preserving the narrow text measure and dark tonal family.

### Centered use-case heading and illustrated row

**Observed:** A two-line centered heading uses Heading-pair-lead followed by Heading-pair-emphasis, both 48px. Beneath it, four Illustrated benefit units carry small task explanations with bolded phrases. Chapters use 100px top and 120px bottom padding; one chapter adds an Output gallery and a short underlined reading link on a darker inset strip.

**Transfer:** Group capabilities around a recognizable situation, not a list of internal feature names. The illustration discs and regular-to-bold heading pair provide continuity across subjects.

### Press and personal proof

**Observed:** After dark demonstrations, a Warm closing band contains a Press quote panel. A white section then uses a centered 48px heading and one Portrait story card beneath it, separated by substantial breathing room.

**Transfer:** Pair a concise external opinion with a specific human story rather than filling the page with anonymous logo tiles.

### Paper conversion and reassurance ending

**Observed:** Warm closing band holds the centered Trial paper panel. Beneath it a 1190px thin Paper-rule separator precedes a smaller centered Heading-small, an approximately 787px-wide 18px paragraph and Yellow outline button. The reassurance block is about 465px tall with roughly 100px of air above and below its content. This is a calm maintenance-and-trust message, not an enormous final slogan.

**Transfer:** Finish with a tangible low-pressure next step, followed by a brief reason to trust the product over time. Keep the final reassurance device even when its subject changes.

### Shared compact directory

**Observed:** Directory band closes both page types with 70px top and bottom padding. Four equal columns hold three link groups and utilities; headings are 13px uppercase with 1.5px tracking, links are 15px yellow on a 25px cadence. Small social icons, a subdued centered emblem and copyright finish the page.

**Transfer:** Close with practical routes and a quiet identity mark, preserving the yellow-on-charcoal contrast.

### Human editorial directory

**Only for:** team and company pages

**Observed:** A 960px white composition begins 100px below navigation with a 48px left-aligned title, two 18px paragraphs in a roughly 470px column and the Waving hand accent opposite. A three-column Portrait directory follows after about 95px. The final incomplete row remains left aligned, followed by substantial white space and the Shared compact directory.

**Transfer:** Use this lighter variant for people-led content. Let the natural final row remain incomplete; do not add a product conversion band merely to fill it.

## Page flow

**Storyline:** Concrete promise → tangible demonstrations → task-based capabilities → external and human proof → low-pressure next step and reassurance → practical directory; editorial pages shorten this to introduction → human detail → directory.

### Product marketing landing page

1. **Promise** — Bright product still life beside a multiline headline, followed by acquisition and award proof.
2. **Product demonstration** — Alternating dark feature theaters, with a testimonial inset among the demonstrations.
3. **Capability chapters** — Centered regular/bold heading pairs and four illustrated task columns; tangible outputs support one chapter.
4. **Context of use** — A final multi-device scene demonstrates continuity beyond a single workspace.
5. **Social proof** — Paper quotation panel, then a personal portrait-and-story carousel.
6. **Closing call** — Small split paper conversion panel followed by a separate trust-over-time message.
7. **Directory** — Dark four-column footer with yellow links, newsletter action, social marks and subdued identity.

**Transfer:** Choose the demonstrations and proof that fit the new product. Preserve the bright-to-charcoal-to-paper contrast, explanatory illustration device and reassuring finish without requiring the same number or order of chapters.

### Company and people introduction

1. **Human introduction** — White two-column editorial opening with a greeting headline, brief origin copy and a pale-yellow hand accent.
2. **Human detail** — Consistent square studio portraits in three columns, each followed by a first name and role.
3. **Directory** — An incomplete final portrait row gives way to white breathing room and the shared dark footer; there is no intervening conversion panel.

**Transfer:** Use the editorial variant for people-led pages, retaining its natural photo grid and direct directory ending.

## Writing

Warm, confident and practical, with occasional small jokes and vivid metaphors. Claims explain how work feels and what the tool does rather than adopting enterprise superlatives.

**Do not copy:** Do not reuse the source brand name, emblem, product icon, device artwork, customer identities, quotations, award claims, founding dates, longevity claims or platform compatibility statements. Replace them with the new product's substantiated facts and assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you and your. Use the product name in explanatory paragraphs and we for human commitment or company context.
- **Rhythm:** Headlines are short, often four to eight words, broken into two or three sturdy lines. Supporting paragraphs usually contain two or three conversational sentences. Contractions, a colon, an em dash and a sparing emoji can add warmth.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product category and where it fits in the reader's life, without an abstract slogan. | About 8–12 words | “The Ultimate Writing App for Mac, iPad and iPhone” |
| Feature headline | Make a concrete benefit memorable through a compact metaphor or plain action. | 4–8 words | “Like 12 Fingers, 25 Hours a Day”<br>“Let Your Words Shine” |
| Use-case heading | A repeated general lead followed by a bold task phrase. | Two short lines | “The Ultimate Tool for Writing Your Book” |
| Support | Lead with the reader's situation, then explain a mechanism or outcome. | Two or three sentences | “Write with confidence: [Brand]’ built-in grammar and style check helps you avoid mistakes and meet the right tone.” |
| Action | Use direct verbs, or a low-pressure invitation to try or read. | 2–7 words | “Get [Brand]”<br>“Read Her Story”<br>“Try [Brand] for Free” |
| Closing reassurance | A lightly playful title introduces a practical commitment. | Short title and one compact paragraph | “Improving with Age ✨” |
| Human introduction | Friendly greeting followed by plain first-person context. | Short greeting and two paragraphs | “Nice to Meet You!” |

**Words and phrasing to use:** focused; well thought-out; at your fingertips; with ease; put it to the test; companion; your work

**Avoid:** revolutionary ecosystem; 10x everything; disruptive; synergy; unparalleled innovation; limited-time urgency

**Rules:**

- Tie each promise to a visible capability or concrete task.
- Emphasize a few useful phrases inside benefit paragraphs rather than making every sentence a headline.
- Use humor as a small marginal note, not as a stream of puns.
- Close with reassurance and a practical next step rather than pressure.

## Do's and Don'ts

### Do

- Keep feature headlines at 48px bold with normal tracking and 1.04 line height.
- Pair 48px regular and bold lines in centered use-case headings.
- Let media occupy about two thirds of feature compositions while copy stays near 383px wide.
- Use 36px outline actions with 2px borders and 3px corners.
- Put simple two-tone task drawings on 190px charcoal discs.
- Use 45px padding and 25px corners for white closing panels.
- Give directory headings 13px uppercase lettering with 1.5px tracking.
- Return to warm paper for the conversion and reassurance finish.

### Don't

- Do not make yellow the background of entire feature sections; it is a small marking and action color.
- Do not tighten large headings with negative tracking or substitute a wide geometric display face.
- Do not turn outline actions into oversized 56px filled pills.
- Do not use the header's soft shadow on every panel; the paper panels rely on fine offset edges.
- Do not wrap the illustrated benefit paragraphs inside uniform rounded rectangular cards.
- Do not replace the task illustrations with multicolor stock app icons.
- Do not add heavy frames, rounded corners or gradients around the square team portraits.
- Do not enlarge the final reassurance into another 48px hero; it uses the smaller 26.3px heading tier.

## Motion and responsive

### Motion

**Observed:**

- Links and outline actions declare color, opacity, translate and background-color transitions of 0.15s.
- Other elements declare opacity and transform transitions of 0.3s and some opacity transitions of 0.6s. Product scenes include layered background and foreground elements.

**Transfer:**

- Keep interaction color changes brief and subtle so the product scenes, not button animation, lead the experience.
- If using layered scene motion, keep diagram overlays separate from text and product planes.

**Unknown:**

- Exact scene movement distances, timing and easing by element, carousel autoplay behavior and reduced-motion treatment are not established.

### Responsive

**Observed:**

- Declared width boundaries occur at 576px, 768px, 1040px and 1200px, with adjacent max-width rules.
- The desktop composition uses a 12-column internal grid and a header that declares small-screen expansion.

**Transfer:**

- On narrow screens, preserve the bright opening, charcoal demonstration and paper ending contrast; stack copy before media and keep the small acquisition strip distinct.
- Reduce the four-column benefit row and three-column portrait directory as space demands, preserving the illustration-to-copy relationship and square portraits.
- Recompose device art rather than simply shrinking the whole desktop scene into illegibility.

**Unknown:**

- Actual narrow-screen font sizes, stacking order, side padding and navigation controls are not established; these transfers are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
