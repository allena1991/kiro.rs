# Ko-fi — friendly paper playground

## Overview

A sunny, human-scale style with chunky retro serif headlines, approachable sans-serif copy and little cartoon companions. Cream paper, white panels and powder blue create a welcoming light environment, with pastel illustration stages supplying extra color. It suits products that promise independence, creative freedom or a less intimidating way to get something done; the pacing is spacious even when the information becomes practical.

### Essentials

- Headlines feel like a cheerful printed sign: a heavy, rounded Bogue Black serif at 72px/1 for the opening and 60px/1 for major chapters, with normal tracking rather than fashionable compression.
- The opening is a centered promise above a cartoon ensemble, not a dashboard splash: an 864px text column, 32px between content groups, a 167px by 68px blue action and a 700px by 375px illustration stage.
- Paper has a playful physical edge: include a white, 2px ink-outlined, 40px-radius editorial panel with a dotted cream duplicate offset 20px down and right. This device carries explanations, demonstrations or proof.
- Buttons distinguish invitation from exploration: the main blue action uses 24px corners and 20px 28px padding; secondary black actions are full pills with the same text size and padding.
- Color lives in large late-page bands and contained media stages: cream and white dominate the early reading experience; powder blue #c7dbfa surrounds objections and #aac9f7 carries the closing invitation through the footer. Keep body text dark rather than tinting headings.
- Illustration acts as a host: include outlined, flat-color organic characters or personified objects at the opening and near a conversion moment, using cream bodies, black details and small warm accents. If bespoke character art is unavailable, use a simple original SVG object with expressive eyes, hands and a useful prop.
- The last invitation is a real task, not just a slogan: a 60px serif promise sits above a white 576px by 84px pill form with a dark inset action; the white 24px-radius directory panel finishes the blue field.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Invitation blue | `#72a4f2` | `--color-action-blue` | action, surface | Primary invitation buttons and the expanded closing-action variant. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Closing blue | `#aac9f7` | `--color-closing-blue` | background, surface | Closing invitation and footer field; FAQ row fill in the blue theme. |
| Airy blue band | `#c7dbfa` | `--color-pale-blue` | background, surface | Objection-handling band and blue demonstration backdrops. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dot and portrait outline | `#000000` | `--color-black` | border, accent | Printed dots and the strongest portrait-card outlines; do not replace ordinary text ink with this. |
| Printed ink | `#202020` | `--color-ink` | text, border, action | All main text, panel outlines and dark buttons. |
| Unselected chip | `#e9dfd2` | `--color-tab` | surface, border | Quiet category chips before selection. |
| Dotted paper backing | `#ede6dd` | `--color-backing` | surface | Offset printed panel backing; also the tray behind capability chapters and neutral FAQ rows. |
| Warm paper | `#f4efe7` | `--color-canvas` | background, surface | Default page canvas and inset informational cards. |
| White paper | `#ffffff` | `--color-white` | surface, text | Editorial panels, footer directory, inputs and text on dark actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| capability walkthroughs | Demonstration pink | `#fecaca` | `--color-demo-pink` | surface | Pastel stage for a small cluster of connected tools. |
| capability walkthroughs | Demonstration lilac | `#e9d5ff` | `--color-demo-lilac` | surface | Contained illustrative stages, not a replacement for the cream page. |
| pricing pages | Commercial lilac | `#e5d8ff` | `--color-pricing-lilac` | background | Continuous FAQ, closing invitation and footer field. |
| capability walkthroughs | Demonstration stone | `#d6d3d1` | `--color-demo-stone` | surface | Neutral backing for colorful customization examples. |

## Typography

- **Bogue** — Hero, chapter headings and closing promises. Very heavy rounded retro serif with soft terminals and generous, slightly bouncy forms. If unavailable, use **Fraunces**. Use 900 with soft, rounded forms; retain normal tracking and adjust line breaks to preserve breadth. Font stack: "Bogue", "Fraunces", Georgia, serif.
- **DM Sans** — Supporting copy, actions, navigation, labels and questions. Friendly geometric sans with clear open counters; regular prose and semibold controls. Font stack: "DM Sans", Nunito, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Bogue | 900 | 72px | 1 | normal | Opening promise, usually broken into two balanced lines. |
| heading-lg | Bogue | 900 | 60px | 1 | normal | Major narrative headings and the closing promise. |
| lead | DM Sans | 400 | 30px | 1.2 | normal | Opening support and spacious editorial panel paragraphs. |
| question | DM Sans | 600 | 30px | 1.2 | normal | FAQ questions and category-selector labels. |
| card-title | DM Sans | 600 | 24px | 32px | normal | Portrait names and compact benefit titles. |
| body | DM Sans | 400 | 20px | 1.4 | normal | Capability copy, proof metadata and footer links. |
| action | DM Sans | 600 | 20px | 1.4 | normal | Main buttons and footer column headings. |
| caption | DM Sans | 400 italic | 20px | 1.4 | normal | Centered contextual caption between category chips and the portrait gallery. |
| nav | DM Sans | 600 | 16px | 1.4 | normal | Compact navigation links. |
| nav-action | DM Sans | 600 | 16px | 1.5 | normal | Dark signup action in the header. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability walkthroughs | giant-action | DM Sans | 600 | 72px | 1 | normal | A closing action enlarged to the size of a section. |
| capability walkthroughs and editorial company pages | heading | Bogue | 900 | 48px | 1 | normal | Contained chapter headings and more intimate closing questions. |
| pricing pages | pricing-heading | Bogue | 900 | 48px | 1 | normal | Comparison panel title. |
| editorial company pages | quote | DM Sans | 600 | 36px | 40px | normal | Large personal testimony within a cream inset. |
| pricing pages | price | Bogue | 900 | 30px | 1.2 | normal | Centered monthly amounts inside white comparison cells. |
| editorial company pages | editorial-body | DM Sans | 400 | 24px | 32px | normal | Personal letters, principles and the company-page closing support. |
| editorial company pages | principle-title | DM Sans | 700 | 24px | 32px | normal | Named principles above explanatory paragraphs. |

**Notes:**

- The display family is already a black cut: its visual weight remains heavy even where the declared weight is regular. Keep it distinctly heavier and more characterful than the sans-serif.
- Normal tracking is part of the approachable voice at every size. Use line breaks and column width, not negative letter spacing, to shape headlines.
- Most large headlines use line height equal to their size, while prose opens to 1.2–1.4. Do not turn small functional labels into miniature serif headlines.

## Layout

**Density:** Airy narrative spacing with compact, practical card interiors and a denser footer directory.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer link rhythm, icon-label gaps and form shell padding. |
| 10px | Category chip row and column gaps. |
| 16px | Walkthrough tile interiors and heading-to-copy spacing. |
| 20px | Chapter heading-to-lead spacing and portrait-column gaps. |
| 24px | Directory columns and principle-card gaps. |
| 28px | Horizontal action padding. |
| 32px | Opening content groups and walkthrough row spacing. |
| 40px | FAQ shell padding, editorial paragraph blocks and explanation-to-media spacing. |
| 80px | Desktop side insets in large editorial panels and footer bands. |
| 96px | Major section vertical breathing room and editorial panel top/bottom padding. |
| 128px | Opening offset beneath the fixed header. |

### Containers and grids

- **Wide stage**: max width 1280px · side padding 80px. Centered portrait galleries and the footer directory at desktop.
- **Editorial column**: max width 864px. Narrow central paper panels and opening text; panel interior is 700px wide with 80px side padding and borders.
- **Navigation rail**: max width 1156px · gap 32px. Logo left, compact links and signup action right.
- **Category cluster**: max width 1024px · gap 10px. Centered wrapping chip rows above proof.
- **Portrait grid**: 3 columns · gap 20px. Three 400px-wide portrait-and-caption columns.
- **Walkthrough pair** (only for capability walkthroughs): max width 784px · 2 columns · gap 0px. Equal text and illustration tiles inside an 864px tray; reverse their order on alternating rows.
- **Principle grid** (only for editorial company pages): max width 780px · 2 columns · gap 24px. Four cream cards in an outlined editorial panel.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Primary actions and tiles | 24px |
|  | Editorial panels | 40px |
|  | Pills | 9999px (pill) |
| pricing pages | Comparison cells | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| capability walkthroughs | Floating demonstration strip | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | A tilted address strip floating over a demonstration; ordinary panels use printed offset backing instead. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default backdrop.

**CSS:** `background: #f4efe7; color: #202020`

#### Outlined paper · level 2

**Use:** Long explanations and product demonstrations.

**CSS:** `background: #ffffff; border: 2px solid #202020; border-radius: 40px; padding: 96px 80px; position: relative`

**Observed:** A narrow centered front sheet with a matching printed backing peeking out on the right and bottom. Pricing and editorial-company variants use 40px interior padding.

**Transfer:** Put one coherent reading chapter on each sheet; let its height follow content.

#### Dotted offset backing · level 1

**Use:** The physical print layer behind Outlined paper.

**CSS:** `background-color: #ede6dd; background-image: radial-gradient(circle, #000000 1px, rgba(0, 0, 0, 0) 0px), radial-gradient(circle, #000000 1px, rgba(0, 0, 0, 0) 0px); background-size: 8px 13.3px; background-position: 0px 0px, 11.8px 6.5px; border: 2px solid #202020; border-radius: 40px; position: absolute; inset: 20px -20px -20px 20px`

**Observed:** Dots are tiny and regular; nearly the whole layer is hidden beneath its front sheet.

**Transfer:** Keep this a printed edge, never a full-page noise texture.

#### White soft shell · level 1

**Use:** FAQ and directory containers.

**CSS:** `background: #ffffff; border-radius: 40px; padding: 40px`

**Observed:** FAQ shell has no outline; the rows inside supply the dark edges. The directory uses 24px corners and 16px padding.

**Transfer:** Use a borderless white grouping when each child is already strongly shaped.

#### Blue objection field · level 0

**Use:** A substantial late-page change of mood.

**CSS:** `background: #c7dbfa; padding: 96px`

**Observed:** Full-width blue surrounds the white FAQ shell; thin-line cartoon companions sit partly behind it.

**Transfer:** Keep the band broad and flat so questions remain the focus.

#### Blue closing field · level 0

**Use:** Conversion invitation and footer continuation.

**CSS:** `background: #aac9f7`

**Observed:** A slightly stronger blue continues without a dividing line from the call into the directory.

**Transfer:** Make the end of the page one inviting environment.

#### Walkthrough tray · level 1

**Only for:** capability walkthroughs

**Use:** Groups alternating text and media pairs.

**CSS:** `background: #ede6dd; border-radius: 40px; padding: 40px`

**Observed:** White text cards meet pastel media cards edge to edge within each pair; rows are separated by 32px.

**Transfer:** Use the outer neutral tray to unify several distinct pastel stages.

#### Lilac closing field · level 0

**Only for:** pricing pages

**Use:** Commercial-page FAQ, invitation and footer.

**CSS:** `background: #e5d8ff`

**Observed:** One uninterrupted lavender field; question rows remain neutral cream rather than blue.

**Transfer:** Use as a scoped commercial theme, not a second default palette.

#### Cream inset · level 1

**Only for:** pricing and editorial company pages

**Use:** Benefit grids, testimony and principles inside white panels.

**CSS:** `background: #f4efe7; border-radius: 24px; padding: 24px`

**Observed:** Cards rely on fill contrast rather than outlines; testimony enlarges padding to 40px.

**Transfer:** Keep secondary reading surfaces quieter than the outer paper silhouette.

## Components

### Fixed navigation

**Use:** Persistent orientation and signup.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 60px; backdrop-filter: blur(22px); z-index: 20; display: flex; align-items: center; justify-content: space-between`

**Text style:** `nav` — DM Sans 600 · 16px/1.4

**Observed:** A compact logo anchors the left of the Navigation rail. Three plain text links and a small black signup pill align right; the background lets the current section color remain visible.

### Primary button

**Use:** Main invitation in the opening and simple conversion blocks.

**CSS:** `background: #72a4f2; color: #202020; border-radius: 24px; padding: 20px 28px; text-align: center; transition: all 0.15s cubic-bezier(0.4, 0, 0.2, 1)`

**Text style:** `action` — DM Sans 600 · 20px/1.4

**Observed:** A single compact action beneath the support line, rather than a row of competing actions.

### Secondary pill

**Use:** Deeper explanations and editorial routes.

**CSS:** `background: #202020; color: #ffffff; border-radius: 9999px; padding: 20px 28px; text-align: center`

**Text style:** `action` — DM Sans 600 · 20px/1.4

**Observed:** Left aligned within the white editorial sheet, before the demonstration or illustration.

### Header signup

**Use:** Compact conversion action within the navigation.

**CSS:** `background: #202020; color: #ffffff; border-radius: 9999px; padding: 12px 20px; text-align: center`

**Text style:** `nav-action` — DM Sans 600 · 16px/1.5

**Observed:** Smaller than content actions; its round silhouette ends the horizontal menu.

### Category chip

**Use:** Playful segmentation of proof or use cases.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #e9dfd2; color: #202020; border: 2px solid #e9dfd2; border-radius: 9999px; padding: 10px 20px`

**Text style:** `question` — DM Sans 600 · 30px/1.2

**Observed:** Small illustrated icon before the label; chips wrap into centered rows. The selected chip is white with a 2px ink outline.

### Portrait caption

**Use:** Names and concise quantified context beneath customer portraits.

**CSS:** `background: #ffffff; border: 2px solid #000000; border-radius: 9999px; padding: 20px 28px; width: 400px`

**Text style:** `card-title` — DM Sans 600 · 24px/32px

**Observed:** A two-line capsule immediately below a square, 40px-radius outlined portrait. Name first, 20px regular metadata second.

**Transfer:** Use a real person or artifact and a short verifiable detail rather than invented audience counts.

### FAQ row

**Use:** Objection handling inside White soft shell.

**CSS:** `display: flex; align-items: center; position: relative; background: #aac9f7; color: #202020; border: 2px solid #202020; border-radius: 24px; padding: 20px 40px 20px 28px; transition: all 0.15s cubic-bezier(0.4, 0, 0.2, 1)`

**Text style:** `question` — DM Sans 600 · 30px/1.2

**Observed:** Question left, small plus at the far right. Longer questions wrap naturally; blue is the default, while pricing and walkthrough pages use the backing-paper neutral.

### Inline claim form

**Use:** Low-friction final conversion.

**CSS:** `display: flex; justify-content: space-between; background: #ffffff; border-radius: 9999px; padding: 8px; width: 576px`

**Text style:** `action` — DM Sans 600 · 20px/1.4

**Observed:** An editable name sits after a fixed domain prefix; a dark pill action is inset at the right. The shell is 84px tall and the inner action 68px tall.

**Transfer:** For products without a public handle, substitute a short email or workspace-name task while preserving the single-field, inset-action construction.

### Footer directory

**Use:** The closing navigation panel.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 16px; max-width: 1280px`

**Text style:** `body` — DM Sans 400 · 20px/1.4

**Observed:** Five columns: a small brand mark and social links, then four link groups. Semibold 20px headings, regular 20px links at 8px intervals; a tiny centered copyright line sits outside below. Blue is the default outer field; lilac belongs to pricing, while editorial and walkthrough endings retain cream.

### Walkthrough text tile

**Only for:** capability walkthroughs

**Use:** One step or capability paired with a visual example.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 24px; padding: 16px; width: 392px`

**Text style:** `heading` — Bogue 900 · 48px/1

**Observed:** Serif title above 20px explanatory copy. The adjacent pastel tile is equally sized, with alternating left/right placement across rows.

### Comparison cell

**Only for:** pricing pages

**Use:** Monthly amount and fee detail.

**CSS:** `display: flex; flex-direction: column; justify-content: center; background: #ffffff; border-radius: 12px; text-align: center`

**Text style:** `price` — Bogue 900 · 30px/1.2

**Observed:** Two plan columns sit to the right of a feature-description column, on a cream row surface. A small fee line sits below each serif amount; tall shared cells span grouped capabilities.

### Giant closing action

**Only for:** capability walkthroughs

**Use:** An entire closing section becomes one clickable invitation.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #72a4f2; color: #202020; border-radius: 9999px; padding: 20px 28px; overflow: hidden; width: 854px; height: 384px`

**Text style:** `giant-action` — DM Sans 600 · 72px/1

**Observed:** Oversized sans-serif text is centered inside a wide capsule; cartoon figures peek in from its two curved edges.

## Imagery and graphics

### Friendly object companions

**Use:** Opening ensemble, panel edges and conversion moments.

**Observed:** Rubber-hose-like figures have irregular flower, heart or blob silhouettes, cream bodies, fine dark outlines, oval eyes and cartoon gloves or shoes. Flat pastel props and small warm red-orange details punctuate mostly unfilled drawings. The opening art spans 700px beneath the text, with visible ground shadows and abundant surrounding paper.

**Transfer:** Draw original objects relevant to the new product as helpful companions. Minimum version: two or three simple expressive SVG silhouettes sharing a task, with a prop and a black oval ground shadow.

**Build:** Use an SVG viewBox 0 0 700 375. Group two or three cream-filled organic paths along the bottom, with dark 2px outlines, oval eyes and bent-line limbs. Add a blue or pale-yellow work prop, one tiny warm accent and black elliptical floor shadows. Stipple only a few interior patches; do not add gradients or realistic lighting.

### Printed dot edge

**Use:** Signature dimensional backing for editorial sheets.

**Observed:** A cream duplicate sheet offset down-right shows fine black staggered dots along the exposed edge; there is no soft cast shadow.

**Transfer:** Use Dotted offset backing behind a useful explanatory chapter, even when the product has no visual assets.

**Build:** Duplicate the front sheet with the same 40px corner radius and 2px outline, offset it 20px horizontally and vertically, and put two staggered 1px radial-dot layers on its cream fill. Keep the front white sheet above it.

### Contained product vignette

**Use:** Demonstrations in editorial panels and capability chapters.

**Observed:** Simplified white interface cards sit on flat cream, lilac, blue, gray, pink or yellow stages. A card may tilt slightly or be paired with a floating rounded input strip, oversized cursor or small feature badges. The product is edited down to a few clear controls rather than shown as a dense full browser.

**Transfer:** Show one understandable task in each vignette. Use a real interface excerpt or a simplified faithful mockup, surrounded by flat pastel space; use the same treatment for a physical product diagram.

**Build:** Place a rounded white card within a 24px-radius pastel stage. Include a compact identity area, one main content block and one clear control; add a slightly rotated floating strip only when it explains the task. Keep internal UI colors local to the demonstration.

### Human proof portraits

**Use:** Wide proof gallery under category selectors.

**Observed:** Three tightly framed square photographs show real people in varied creative settings. Natural photographic color is retained, with 2px black outlines and 40px corners; white pill captions provide a more graphic base.

**Transfer:** Use authentic customer or maker images with varied expressions and environments. Keep the square framing and simple graphic border rather than applying a uniform color wash.

### Letter ornaments

**Only for:** editorial company pages

**Use:** Personal origin stories and an encouraging closing illustration.

**Observed:** A small envelope and winding dashed line share the edge of a long letter; the final illustration shows a bright organic character holding a short encouraging sign.

**Transfer:** Use an original lightweight marginal drawing to make a long first-person narrative feel personal, and finish with a direct visual gesture toward the reader.

**Build:** Draw a thin outlined envelope or message object near a panel corner; trail a dashed curved SVG path down an empty margin. For the ending, use one flat-colored original figure beside a cream outlined sign with a short serif encouragement.

### Icons

**Observed:** Functional plus and check marks are small, dark and plain. Category icons are 36px illustrated miniatures with black contours and tiny colored fills; benefit icons use the same hand-drawn object language.

**Transfer:** Keep utility marks simple and let illustrated objects provide warmth. Avoid mixing glossy app icons into marketing labels; third-party marks belong inside demonstrations or integration groups.

## Section recipes

How recurring sections are built.

### First screen: Promise and companions opening

**Observed:** A 60px fixed navigation overlays the warm canvas. The main content begins at 128px in an 864px-wide centered column: two balanced lines of 72px black serif promise, a 30px regular sans supporting sentence, then Primary button. Content groups are separated by 32px. Beneath the button, a 700px by 375px cartoon ensemble occupies the lower part of the first screen. Layers are simply paper, type/action, then flat outlined illustration with black ground shadows. Within the first 900px the headline, support, action and almost all the main illustration are visible; the first Outlined paper chapter begins below the fold.

**Transfer:** Replace the promise with the new product's human benefit and the figures with original personified tools performing that benefit. Keep the centered vertical stack as the default. Capability, pricing and editorial-company pages instead open with a left-aligned 72px title and 30px support in the same narrow central territory, with a smaller illustration to the right or perched on the next panel; pricing and capability openings retain the blue action.

**Avoid:** Do not replace the lower illustration with a huge browser frame, add an eyebrow above the headline, or fill the opening background with saturated blue.

**Text style:** `display` — Bogue 900 · 72px/1

### Paper explanation chapter

**Observed:** Outlined paper sits in the Editorial column above Dotted offset backing. A 60px serif title leads a 30px support paragraph at a 20px gap. Secondary pill follows, then a 700px-wide product vignette or small drawing separated by 40px. Longer editorial prose uses the same sheet and larger paragraph intervals.

**Transfer:** Use the sheet for a complete explanatory thought; allow text, proof or a demonstration to determine its height.

**Text style:** `heading-lg` — Bogue 900 · 60px/1

### Category-led proof

**Observed:** A centered 60px headline and 30px support line introduce Category chip rows within a 1024px cluster. A centered 20px italic caption separates selectors from the three-column portrait gallery; each square image ends in Portrait caption.

**Transfer:** Segment proof by user need, discipline or workflow. Keep selectors broad enough to read as playful labels rather than filter-toolbar controls.

**Text style:** `heading-lg` — Bogue 900 · 60px/1

### Illustrated FAQ band

**Observed:** Blue objection field surrounds a centered white shell about 728px wide, padded 40px. FAQ row uses a 30px semibold question and a small plus. Cartoon companions peek from behind the shell. The walkthrough variant introduces a 48px serif FAQ heading on cream; the commercial variant substitutes Lilac closing field and cream rows.

**Transfer:** Use a small set of genuine pre-purchase questions, letting long questions wrap while preserving the plus alignment.

**Text style:** `question` — DM Sans 600 · 30px/1.2

### Task-based close and directory

**Observed:** Blue closing field carries a centered 60px serif promise and Inline claim form. A roughly 294px by 320px companion sits at the lower left and is partly hidden behind Footer directory. The directory remains white and wide, with five columns, 24px gaps and a small centered copyright below. The commercial version keeps the form but uses lilac; the walkthrough uses Giant closing action; the editorial-company version uses a 48px question, 24px support, Primary button and a 672px-wide encouraging drawing before the directory.

**Transfer:** End with a tangible first step adapted to the new product and preserve the sense that the illustration welcomes the user into the footer.

**Text style:** `heading-lg` — Bogue 900 · 60px/1

### Alternating capability pairs

**Only for:** capability walkthroughs

**Observed:** Walkthrough tray contains equal 392px by 384px white text and pastel media tiles, with no gap inside each pair and 32px between rows. Heading is 48px serif; copy is 20px sans. Each successive pair reverses text and media.

**Transfer:** Explain one task per pair; vary the pastel stages while keeping all text tiles white.

**Text style:** `heading` — Bogue 900 · 48px/1

### Comparison with useful extras

**Only for:** pricing pages

**Observed:** One Outlined paper panel groups a 48px serif title, a 30px introductory sentence, and a three-column comparison: description left, two white plan cells right, on cream rows with 12px corners. A second 48px title introduces a two-column cream benefit grid with small outlined illustrations, 24px semibold titles and 20px copy.

**Transfer:** Compare only meaningful plan differences and follow the table with shared benefits; keep price text serif rather than oversized sans numerals.

**Text style:** `pricing-heading` — Bogue 900 · 48px/1

### Personal letter and principles

**Only for:** editorial company pages

**Observed:** An asymmetric illustrated opening leads to a long white outlined letter with 24px/32px prose and cream testimony insets carrying 36px/40px semibold quotations. A separate paper chapter introduces a two-column grid of cream principle cards with illustrated symbols, 24px bold titles and 24px regular descriptions.

**Transfer:** Tell the actual product's origin through a named human voice, then connect its decisions to concrete principles rather than generic corporate slogans.

**Text style:** `editorial-body` — DM Sans 400 · 24px/32px

## Page flow

**Storyline:** Human promise → understandable mechanism → relatable proof or useful detail → reassurance → tangible invitation → compact directory.

### General product introduction

1. **Promise** — Centered serif benefit, friendly ensemble and one blue action.
2. **Product demonstration** — Outlined paper explains the mechanism and contains an edited product vignette.
3. **Social proof** — Category chips lead to real-person portrait cards.
4. **Point of view** — Another paper chapter states the human alternative to an impersonal status quo.
5. **Objection handling** — White FAQ shell on pale blue, flanked by companions.
6. **Closing call** — Stronger blue continues through a task form and white directory.

**Transfer:** Use the balance of human promise, visible mechanism and reassurance; shorten or rearrange chapters to match the product's maturity.

### Guided capability explanation

1. **Promise** — Left-aligned serif introduction with a small character beside the next chapter.
2. **Capability chapters** — Alternating white text and pastel illustration pairs inside a cream tray.
3. **Objection handling** — Serif-led white FAQ shell on the warm canvas.
4. **Closing call** — An enormous blue capsule action with characters entering at its edges, followed by the white directory.

**Transfer:** Use for setup guides or feature tours where a single task per illustrated row makes the product approachable.

### Commercial decision support

1. **Promise** — Left-aligned benefit and blue action with an illustration resting on the comparison panel.
2. **Pricing** — Two plan columns alongside descriptions inside an outlined paper sheet.
3. **Capability proof** — Shared extras in a two-column cream benefit grid within the same sheet.
4. **Objection handling** — A white FAQ shell on a full-width lilac band.
5. **Closing call** — Serif promise and claim form continue the lilac field through fee notes and the white directory.

**Transfer:** Keep commercial detail practical and readable; use the lilac theme only for this decision-support mode.

### Trust through a personal narrative

1. **Identity** — Left-aligned serif statement with two friendly figures perched on the letter panel.
2. **Origin story** — First-person letter, small marginal drawing and embedded personal testimony.
3. **Principles** — Separate outlined paper chapter with four cream illustrated cards.
4. **Closing call** — Centered invitation, blue action and a character holding an encouraging sign; cream surrounds the final white directory.

**Transfer:** Replace the origin and principles with genuine decisions and experiences. Keep the personal pace without turning every product page into a company manifesto.

## Writing

Friendly, encouraging and plainspoken, with a little wordplay. Practical explanations sit beside emotional benefits without sounding like enterprise software or a motivational speech.

**Do not copy:** Do not reuse Ko-fi names, logos, characters, creator identities, testimonials, founding story, fee claims, prices or audience counts. Examples illustrate the voice, not facts available to another product.

- **Addressing the reader:** Speak directly to you and your; use we when explaining the product's intentions or responsibilities. Keep agency with the reader.
- **Rhythm:** Headlines are short, often rhythmic or lightly rhyming. Supporting copy uses one or two clear sentences; longer editorial paragraphs remain conversational. Exclamation marks occur in invitations but are not attached to every claim.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Pair the activity the reader cares about with a desirable outcome; sound good aloud. | 4–12 words | “Love what you do and make money too”<br>“Payday your way!” |
| Supporting line | Name the reader's options and reassure them about control. | One or two sentences | “Get paid directly, on your own terms!” |
| Action | Use a short, familiar verb phrase rather than a clever campaign label. | 1–4 words | “Get started”<br>“Sign up free” |
| Capability title | Start with a verb and explain one achievable task. | 3–7 words | “Make it your own”<br>“Share with your audience” |
| Reassurance | Explain the real mechanism, then remove a specific worry in everyday language. | One brief paragraph | “Receive your earnings directly in your own PayPal or Stripe account. No waiting, no fuss.” |
| Closing invitation | Return to the human aspiration, or ask a warm direct question. | 6–12 words | “Make money doing what you love”<br>“Sound like something you want to be part of?” |

**Words and phrasing to use:** your own; on your terms; at your pace; get started; make it your own; directly; no fuss; show the love

**Avoid:** maximize monetization; leverage synergies; disruptive ecosystem; dominate; crush your goals; unlock unprecedented potential

**Rules:**

- Prefer concrete verbs to abstract platform language.
- Explain who controls the task and what happens next.
- Let one playful headline carry the charm; keep commercial details literal.
- Make reassurance specific to the actual product rather than promising universal success.
- Use simple question phrasing for objections; avoid formal support-center jargon.

## Do's and Don'ts

### Do

- Keep the opening headline at 72px/1 and major narrative headings at 60px/1 with normal tracking.
- Preserve the contrast between a black-cut serif and regular 30px sans leads.
- Include a 20px-offset dotted backing behind at least one 40px-radius outlined paper chapter.
- Use 24px corners on blue invitations and full pills on black exploration actions.
- Give the main reading sheets 80px horizontal and 96px vertical padding at desktop.
- Keep proof photographs square, naturally colored and paired with white capsule captions.
- Carry the blue closing environment through the footer instead of inserting a separate dark footer.
- Keep FAQ outlines at 2px and their questions at 30px semibold.

### Don't

- Do not use all-caps tracked eyebrows as a universal section-heading system; these headings stand on their own.
- Do not flatten every text role into DM Sans; the rounded black serif supplies the personality.
- Do not use full-pill rounding for the ordinary blue invitation; its measured corner treatment is 24px.
- Do not put soft shadows on all white cards; the signature depth is a printed, outlined duplicate.
- Do not turn the early page into a rainbow of full-width bands; reserve broad color for late reassurance and conversion.
- Do not grayscale all portraits or tint them blue; their natural color supplies human variety.
- Do not make the footer a dense dark utility slab; it is a wide white rounded directory on a light field.
- Do not use 12px body copy to fit more benefits; keep functional marketing prose at 20px/28px.

## Motion and responsive

### Motion

**Observed:**

- Primary actions, category chips and FAQ surfaces declare 0.15s transitions with cubic-bezier(0.4, 0, 0.2, 1).
- The blue FAQ band declares opacity 0.6s ease-in-out and transform 0.3s ease-in; the commercial FAQ band declares opacity 0.6s ease-in-out.

**Transfer:**

- Preserve short control transitions and the gentle arrival of large illustrated chapters; the static composition must remain fully readable.

**Unknown:**

- Hover and focus-visible appearance changes are not established.
- The detailed playback and timing of product demonstrations and decorative character movement are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1536px.
- Opening type classes switch from 48px to 72px at the medium tier; major 60px chapter headings have 30px smaller-screen counterparts. Walkthrough pair classes switch from columns to alternating rows at the medium tier.
- Editorial sheet classes use 20px horizontal and 28px vertical padding below the desktop treatments; directory and category groups are designed to wrap or stack.

**Transfer:**

- On narrow layouts, stack text before its demonstration and preserve each pastel stage as one coherent scene.
- Reduce paper insets before reducing readable copy; keep the dotted edge subordinate so it does not force horizontal overflow.
- Let the form shrink to its container while retaining its inset pill action and a usable editable field.

**Unknown:**

- Narrow-screen compositions were not visually verified.
- Exact mobile illustration scaling, menu behavior and footer column wrapping are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
