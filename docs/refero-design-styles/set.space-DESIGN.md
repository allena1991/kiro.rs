# Set Space — cinematic field notes

## Overview

An almost-black editorial world pairs literary serif headlines with tiny monospaced controls and field-note captions. Atmospheric landscape photography and carefully framed dark software views give practical tools a cinematic, tactile presence. Vermilion orange interrupts the darkness in a few emphatic panels and a monumental typographic ending; the overall pace is spacious while the information itself stays compact.

### Essentials

- Literary headlines, instrument-sized labels: regular Quadrant at 39px/1.15 for the opening and 26px/1 for chapter titles, contrasted with 13px Pressura Mono uppercase labels tracked 0.08em.
- The opening is a landscape, not a dashboard: a nearly full-width photograph inset 19.5px, fading into black, carries a centered two-line promise and a 390px support measure within a 900px-tall stage. Use real-world subject photography if there is no product-related landscape.
- Controls feel like small equipment keys: 23px-tall rectangular buttons, 3.3px corners, 13px lowercase mono text, and 4.2px 6.5px padding; the header conversion key alone is orange.
- Color arrives as punctuation: black dominates the long reading canvas, charcoal backs product views, and orange is concentrated in the header action, a bright proof panel and the full-width closing field rather than scattered across every section.
- Capabilities read like numbered chapters: 1px charcoal rules, muted 26px serif numbers, an indented title and short slab-serif description, then an oversized media stage and compact uppercase annotations.
- End with a split-name typographic field: black 144px/1.15 serif words at opposite edges of an orange band, scaling at 10vw, above a spacious interval and ruled contact area. Every new page retains this monumental closing device with its own name or short closing phrase.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5900` | `--color-accent` | background, surface, action, accent | Header conversion key, bright proof card and large closing band; also completed-status dots. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-canvas` | background, text | Main canvas and reverse text on orange. |
| Charcoal | `#1a1a1a` | `--color-panel` | surface | Product media backing, subdued buttons and secondary proof cards. |
| Charcoal hairline | `#1a1a1a` | `--color-rule` | border | Quiet 1px separators and panel edges on black. |
| Slate grey | `#5b6670` | `--color-muted` | text, border | Chapter numbers, explanatory uppercase captions, subdued details and pricing hover edges. |
| Warm grey | `#cfcec4` | `--color-control` | text, border | Navigation, small action labels and hover edges. |
| White | `#ffffff` | `--color-text` | text | Headlines and primary reading text on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| roadmap sections | Work blue | `#4a73ab` | `--color-progress` | accent | In-progress status dots. |
| roadmap sections | Ochre | `#8a653c` | `--color-upcoming` | accent | Upcoming-status dots. |

## Typography

- **Quadrant** — Headlines, chapter numbers and monumental closing type. Regular editorial serif with sturdy proportions and expressive, open letterforms. If unavailable, use **Libre Baskerville**. Use regular 400; preserve the moderate headline size rather than adding weight. Font stack: "Quadrant", "Libre Baskerville", Georgia, serif.
- **Quadrant Slab** — Paragraphs, small pricing titles and occasional italic asides. Compact slab-serif text with a typewritten texture. If unavailable, use **Roboto Slab**. Use regular 400 and the small measured text sizes. Font stack: "Quadrant Slab", "Roboto Slab", Georgia, serif.
- **Pressura Mono** — Navigation, buttons, feature captions and status labels. Narrow, utilitarian monospaced lettering, widely tracked in uppercase captions. If unavailable, use **IBM Plex Mono**. Use regular 400; keep labels compact. Font stack: "Pressura Mono", "IBM Plex Mono", ui-monospace, monospace.
- **Quadrant Mono** — Small header name link. Serif monospace identity lettering. If unavailable, use **Courier Prime**. Font stack: "Quadrant Mono", "Courier Prime", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-name | Quadrant | 400 | 144px | 1.15 | normal | size 10vw | Separated name or phrase at opposite edges of the closing band. |
| opening-headline | Quadrant | 400 | 39px | 1.15 | normal | fixed | Centered opening promise and the large FAQ heading. |
| statement | Quadrant | 400 | 39px | 1 | normal | fixed | Left-aligned introductory statements and major section titles; wrapped word lines have a 6px gap. |
| chapter | Quadrant | 400 | 26px | 1 | normal | fixed | Chapter titles, muted chapter numbers and secondary editorial statements. |
| small-heading | Quadrant | 400 | 19.5px | 1.2 | normal | size clamp(1.3rem, 2.8vw, 1.5rem) | FAQ questions, proof-card headlines and the closing contextual statement. |
| body | Quadrant Slab | 400 | 13.3px | 1.4 | 0.015em | fixed | Short supporting paragraphs, descriptions and biographies. |
| aside | Quadrant Slab | 400 italic | 13.3px | 1.4 | 0.015em | fixed | A brief parenthetical emphasis inside a support sentence. |
| label | Pressura Mono | 400 | 13px | 1.4 | 0.08em, uppercase | fixed | Feature captions, footer links, pricing values and status labels. |
| action | Pressura Mono | 400 | 13px | 1 | 0.05em, lowercase | fixed | Compact buttons and time readout. |
| navigation | Pressura Mono | 400 | 13px | 1 | 0.05em | fixed | Short header text links. |
| identity | Quadrant Mono | 400 | 13px | 1 | 0.01em | fixed | Small brand-name header link. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company and roadmap sections | editorial-heading | Quadrant | 400 | 26px | 1.15 | normal | fixed | Multiline lead beside a dense roadmap list. |
| pricing sections | plan-name | Quadrant Slab | 400 | 13.3px | 1.4 | 0.078em, uppercase | fixed | Small plan titles in horizontal subscription rows. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The main hierarchy is serif, not grotesk: keep weight 400 even when the type becomes monumental.
- Tracking is normal in display serif, 0.05em in controls and 0.08em in uppercase mono. Do not carry label tracking into headlines.
- Body text remains unusually small and textured. Give it a narrow measure rather than enlarging it to compete with the headline.
- The closing name is the only routine 144px text; ordinary opening promises stay at 39px.

## Layout

**Density:** Airy between chapters, compact within them: long black intervals separate densely labelled media and narrow text blocks.

### Spacing

**Spacing system:**

- **rhythm** 13px — Primary spacing unit; half and quarter subdivisions serve compact controls.

| Value | Use |
| --- | --- |
| 3.3px | Gap between adjacent action keys. |
| 6.5px | Small control gaps and footer link spacing. |
| 13px | Caption-grid gaps, pricing-row spacing and compact padding. |
| 19.5px | Header side padding, footer padding and stacked content gaps. |
| 26px | Chapter padding and two-column grid gutters. |
| 39px | Top padding in the product media stage and start of main reading content. |
| 52px | Main content side padding and larger internal group gaps. |
| 182px | Fourteen rhythm units between major chapters and before the closing band. |

### Containers and grids

- **reading-container**: max width 1560px · side padding 52px. Centered main content area; 1336px usable width at a 1440px viewport.
- **statement-measure**: max width 1040px. Broad left-aligned serif statements, leaving a substantial right-side void.
- **support-measure**: max width 520px. Short chapter explanations nested below the title; opening support uses 390px.
- **chapter-grid**: 12 columns · gap 26px. A narrow number column followed by eleven columns for the heading; product views occupy the inner ten columns.
- **caption-grid**: 4 columns · gap 13px. Four small annotation columns beneath media; text-only assurance groups use two columns with 26px gaps.
- **paired-columns**: 2 columns · gap 26px. FAQ title beside question list, and parallel biographical text.
- **closing-grid**: 4 columns · gap 13px · side padding 19.5px. Three occupied footer link/contact columns and one empty column; contextual statement spans three columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Controls and compact cards | 3.3px |
|  | Media stages | 6.5px |
| roadmap sections | Status dots | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Inset product view | `0px 0px 13px 0px rgba(0, 0, 0, 0.5)` | Soft dark edge around the product image inside a charcoal stage. |

### Surfaces

#### Black canvas · level 0

**Use:** Continuous reading background.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Text chapters usually have no enclosing card; only a hairline marks their beginning.

**Transfer:** Keep the reading field continuous across different content types.

#### Charcoal media stage · level 1

**Use:** Broad backplate for product demonstrations.

**CSS:** `background: #1a1a1a; border-radius: 6.5px; padding: 39px 13px 0px; overflow: hidden`

**Observed:** The dark interface sits centered inside the stage and terminates flush at its lower edge.

**Transfer:** Frame a real working product view, not an abstract collection of floating UI pieces.

#### Ruled black panel · level 1

**Use:** Quiet grouping for plan rows and structured lists.

**CSS:** `background: #000000; border: 1px solid #1a1a1a; border-radius: 3.3px`

**Observed:** Extremely low-contrast edges carry structure without a raised-card effect.

**Transfer:** Use hairlines instead of tinted fills for dense choices.

#### Orange field · level 0

**Use:** High-impact closing band and occasional proof card.

**CSS:** `background: #ff5900; color: #000000`

**Observed:** Flat saturated color without texture or glow; all content reverses to black.

**Transfer:** Concentrate orange into a few intentional blocks.

#### Photographic fade · level 0

**Use:** Blend an opening photograph into the black reading canvas.

**CSS:** `background-image: linear-gradient(to bottom, rgba(0, 0, 0, 0.08) 0%, rgba(0, 0, 0, 0.35) 48%, #000000 100%)`

**Observed:** A cool sky and detailed horizon remain visible while the foreground dissolves into black.

**Transfer:** Match the gradual tonal fade; exact stops are not essential.

## Components

### Utility navigation

**Use:** Persistent top bar.

**CSS:** `position: fixed; top: 0px; left: 0px; width: 100%; display: flex; justify-content: space-between; align-items: center; gap: 13px; padding: 5.2px 19.5px; z-index: 11; box-sizing: border-box`

**Text style:** `navigation` — Pressura Mono 400 · 13px/1 · tracking 0.05em

**Observed:** A tiny emblem, small name link and two text links sit left; a local time readout and two action keys sit right. The bar reads as a black strip about 41px tall.

**Transfer:** Keep navigation sparse, with identity much smaller than editorial titles.

### Subdued button

**Use:** Default actions in the opening and body.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #1a1a1a; color: #cfcec4; border: 1px solid #1a1a1a; border-radius: 3.3px; padding: 4.2px 6.5px; gap: 6.5px`

**Text style:** `action` — Pressura Mono 400 · 13px/1 · tracking 0.05em · lowercase

**Observed:** Compact content-width keys occur in close pairs; they do not expand into large promotional pills.

**States:** Declared: hover border-color warm grey; focus-visible unknown; active border-color and text orange.

**Transfer:** Use this subdued variant for body conversion actions as well as secondary utilities.

### Orange button

**Use:** Prominent header conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ff5900; color: #000000; border: 1px solid #ff5900; border-radius: 3.3px; padding: 4.2px 6.5px; gap: 6.5px`

**Text style:** `action` — Pressura Mono 400 · 13px/1 · tracking 0.05em · lowercase

**Observed:** Same key-like construction as the subdued action, placed beside a dark sign-in key.

**States:** Declared: hover border-color and text white; focus-visible unknown; active border-color and text orange.

**Transfer:** Reserve the orange action for the top-level conversion instead of coloring every CTA.

### Numbered chapter lead

**Use:** Introduce a benefit or capability.

**CSS:** `display: grid; grid-template-columns: 1fr 11fr; gap: 26px; border-top: 1px solid #1a1a1a; padding: 26px 0px`

**Text style:** `chapter` — Quadrant 400 · 26px/1

**Observed:** Muted two-digit serif number at left, white title at right; a small body paragraph aligns under the title rather than under the number.

**Transfer:** Give each chapter one concrete verb and one supporting sentence.

### Product window

**Use:** Large visual proof inside a media stage.

**CSS:** `border-top: 1px solid #1a1a1a; border-right: 1px solid #1a1a1a; border-left: 1px solid #1a1a1a; border-radius: 6.5px 6.5px 0px 0px; box-shadow: 0px 0px 13px 0px rgba(0, 0, 0, 0.5); object-fit: cover`

**Observed:** A roughly 1087px-wide dark software view sits within a 1336px backing; image-rich work content supplies color while chrome remains black.

**Transfer:** Show a coherent screen with meaningful work visible, centered and large enough to read as a real application.

### Proof card

**Use:** A strong partner or eligibility highlight.

**CSS:** `display: grid; grid-template-columns: 3fr 2fr; gap: 26px; background: #ff5900; color: #000000; border-radius: 3.3px; padding: 16.3px`

**Text style:** `small-heading` — Quadrant 400 · 19.5px/1.2

**Observed:** The wider orange card pairs short text and a black action key with a partner mark. A narrower charcoal companion card uses white text and the same small-radius shell.

**Transfer:** Use verifiable proof or an offer; a short black typographic seal can replace a partner mark.

### FAQ row

**Use:** Answer common objections in a two-column section.

**CSS:** `display: flex; flex-direction: column; border-top: 1px solid #1a1a1a; padding-top: 26px`

**Text style:** `small-heading` — Quadrant 400 · 19.5px/1.2

**Observed:** A serif question and small right-aligned expand glyph form each approximately 74px row. The section title occupies the left half and the question stack the right.

**Transfer:** Keep initial questions concise and keep the all-questions action below the list.

### Split-name closing

**Use:** Distinctive page ending and contact directory.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 26px; background: #ff5900; color: #000000`

**Text style:** `closing-name` — Quadrant 400 · 144px/1.15

**Observed:** Two huge name fragments pull to opposite edges. The 678px-tall field leaves a large orange void before a black top rule, contextual serif statement, three occupied mono link columns, copyright and a tiny corner emblem.

**Transfer:** Use the new identity or a two-part closing phrase; retain the opposing alignment, empty color field and compact utility base.

### Plan row

**Only for:** pricing sections

**Use:** Compact subscription comparison.

**CSS:** `display: flex; flex-direction: column; gap: 13px; padding: 13px; border: 1px solid #1a1a1a; border-radius: 3.3px`

**Text style:** `plan-name` — Quadrant Slab 400 · 13.3px/1.4 · tracking 0.078em · uppercase

**Observed:** Full-width horizontal rows: name left, uppercase mono price right, muted body description underneath; no oversized price numerals.

**States:** Declared: hover border-color slate grey; focus-visible unknown.

**Transfer:** Keep choices comparable through aligned rows, not elaborate tier towers.

### Roadmap row

**Only for:** roadmap sections

**Use:** Compact public progress list.

**CSS:** `display: flex; justify-content: space-between; gap: 13px; border-top: 1px solid #1a1a1a; padding-top: 13px`

**Text style:** `body` — Quadrant Slab 400 · 13.3px/1.4 · tracking 0.015em

**Observed:** Small body title at left, muted uppercase mono status at right followed by a 10px dot. Ochre means upcoming, blue means in progress, orange means completed; rows are separated by a 9.8px gap.

**Transfer:** Pair status words with dots rather than relying on color alone.

## Imagery and graphics

### Atmospheric landscape

**Use:** Default marketing opening.

**Observed:** A broad rocky mountain range beneath a blue-grey clouded sky fills almost the whole first viewport. The horizon passes behind centered white type; dim earthy foreground rocks fade completely into black. A modest rounded top edge and 19.5px side inset keep it integrated with the page.

**Transfer:** Choose a real landscape or working environment tied to the product's world. Without bespoke photography, use one well-composed licensed environmental photograph rather than a collage or synthetic dashboard.

**Build:** Use a cover-fit image in a 900px-tall stage with 19.5px side insets and 6.5px top corners. Overlay the Photographic fade surface; preserve sky detail in the upper third and darken the central text zone gently.

### Image-rich product proof

**Use:** Large capability demonstrations and walkthrough poster.

**Observed:** Black application chrome surrounds bright photographs of landscapes, buildings and leisure spaces. Wide coherent screens sit on charcoal backplates; the walkthrough uses a large dark poster with a small centered play control. A compact search chapter instead pairs left annotations with a tightly framed interface detail on the right.

**Transfer:** Use real work artifacts with comparable color richness inside your own dark UI. If the product has no interface, show a single detailed output or process artifact on the same charcoal stage.

### Documentary company photographs

**Only for:** company storytelling pages

**Use:** Image-led company opening and team story.

**Observed:** The opening shows a close, candid gathering with hands, printed ephemera, food, candles and green glass; its lower edge fades into black. Farther down, an 891px square architectural portrait places people small within a light stairwell and glass-block wall, followed by a muted uppercase credit and two compact biographies.

**Transfer:** Use candid evidence of the people and physical environment behind the product. Keep natural light and environmental context rather than circular headshots or a corporate team grid.

### Icons

**Observed:** Sparse symbols: a slender 11×17px warm-grey header emblem, a 28×42px white opening emblem, 16px expand glyphs and a small corner footer mark. Icons act as punctuation rather than feature illustrations.

**Transfer:** Use a distinct simple brand-independent emblem or restrained geometric mark, plus small functional expand and play symbols. Keep the main feature explanations typographic.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise

**Observed:** A 41px utility bar caps a 900px photographic stage, inset 19.5px on either side. Back to front: mountain photograph with cloudy sky, dark foreground fade, small white emblem, centered two-line 39px/1.15 serif promise, a short 390px-wide support line with an italic parenthesis, and two subdued action keys. The promise occupies only about a quarter of the width, around the middle of the landscape; the emblem sits just above it. The support is separated from the headline by about 58px, then the action pair follows about 33px later. All of this is visible within the first 900px; the explanatory statement begins below the fold.

**Transfer:** Use an environmental photograph to make the product's world tangible, even without original art. Keep the foreground typography modest and centered rather than increasing it to fill the image. Company stories instead open with a 630px-high documentary photograph and place the statement below, left aligned.

**Avoid:** Do not replace the scene with a blank black hero, huge sans-serif slogan, floating dashboard collage or orange hero fill.

**Text style:** `opening-headline` — Quadrant 400 · 39px/1.15

### Editorial thesis

**Observed:** A 39px serif statement wraps within 1040px, aligned to the 52px content inset. It has no card or decorative eyebrow. In the company variant a secondary 26px serif paragraph follows about 58px below.

**Transfer:** Explain the product's organizing idea in one direct sentence; use the smaller follow-on paragraph for company context.

**Text style:** `statement` — Quadrant 400 · 39px/1

### Numbered capability chapter

**Observed:** Numbered chapter lead introduces a large Charcoal media stage with Product window, followed by four-column uppercase annotations. A 13px uppercase preface can introduce the first chapter. Heading and support are indented one narrow grid column; inter-chapter space is 182px.

**Transfer:** Mix large-screen chapters with concise text-only assurance chapters and a split text/interface-detail chapter. Keep the number and rule construction stable while changing the supporting work examples.

**Text style:** `chapter` — Quadrant 400 · 26px/1

### Walkthrough stage

**Observed:** A left-aligned 39px serif invitation sits above a wide black video poster with dark software imagery and centered play symbol; the video occupies most of the section width.

**Transfer:** Use a short demonstration of real work or a narrated process with a meaningful poster frame.

**Text style:** `statement` — Quadrant 400 · 39px/1

### Compact conversion and proof

**Observed:** A muted uppercase line introduces a 39px serif conversion title. Plan rows stack with 13px gaps, followed by a 3:2 pair of Proof cards in orange and charcoal. Choice data stays small; proof is the colored interruption.

**Transfer:** Use horizontal choices for offers or packages and a bright proof card for a genuine reason to act, regardless of whether the product has subscription tiers.

**Text style:** `statement` — Quadrant 400 · 39px/1

### Objection split

**Observed:** Large serif heading occupies the left half; three ruled FAQ rows occupy the right half with a subdued action below. Gutters are 26px; the section is followed by 182px of black before the closing field.

**Transfer:** Address the most consequential objections without turning the section into a dense help center.

**Text style:** `opening-headline` — Quadrant 400 · 39px/1.15

### Monumental orange ending

**Observed:** Split-name closing is shared across page types: full-bleed orange, 10vw serif fragments aligned to opposite sides, a large empty color field and a ruled lower directory. The lower statement spans three of four columns, followed by small uppercase links and address; copyright is bottom left and an emblem bottom right.

**Transfer:** Retain this ending as the page's graphic release after a dark reading journey, using the new identity and relevant contextual and contact content.

**Text style:** `closing-name` — Quadrant 400 · 144px/1.15

### Documentary story and progress

**Only for:** company storytelling pages

**Observed:** A faded candid opening photograph leads to a large serif belief statement and secondary serif paragraph. A centered square environmental portrait, uppercase credit and two small biography columns follow. The later progress section puts a narrow 26px serif lead left, leaves a middle gap, and places a long Roadmap row list in the right half.

**Transfer:** Separate human context from operational transparency; use real biographies and meaningful progress information.

**Text style:** `editorial-heading` — Quadrant 400 · 26px/1.15

## Page flow

**Storyline:** Atmospheric world → clear organizing idea → tangible work evidence → trust and practical detail → compact action → monumental identity ending.

### Product marketing and conversion

1. **Promise** — Centered serif outcome over a fading environmental photograph with two small actions.
2. **Explanation** — Broad left-aligned statement defines what the tool organizes.
3. **Capability chapters** — Numbered, ruled chapters alternate large product screens, detail views and compact assurance copy.
4. **Product demonstration** — Large walkthrough poster with a restrained heading.
5. **Conversion and proof** — Horizontal offer rows and a bright proof card alongside a muted companion.
6. **Objection handling** — Two-column heading and question list.
7. **Identity ending** — Orange split-name field and compact directory.

**Transfer:** Adapt the number and arrangement of chapters to the product's actual story while keeping photographic context, numbered proof, compact controls and the orange typographic ending.

### Company story and public progress

1. **Human context** — Candid documentary photograph fades into the reading field.
2. **Point of view** — Large serif belief statement followed by a smaller editorial paragraph.
3. **Credibility** — Square environmental portrait, credit and two biography columns.
4. **Transparency** — Narrow lead and request action beside a ruled status list.
5. **Identity ending** — The same monumental orange name field and directory.

**Transfer:** Lead with people and physical context rather than a product claim; retain the shared type, black spacing and closing treatment.

## Writing

Considered, practical and quietly personal. The copy explains useful work in plain terms, with occasional thoughtful asides rather than exaggerated technological promises.

**Do not copy:** Do not reuse Set Space's name, emblem, partner marks, founder identities, photographs, industry-specific claims, geographic acknowledgements, plan prices, capacity numbers or eligibility offers. Source quotations illustrate tone only.

- **Addressing the reader:** Use you and your for benefits and control; we for intentions and company beliefs. Refer to the product plainly by name when clarification is needed.
- **Rhythm:** Short verb-led chapter titles, a gently conversational opening sentence and one-sentence support paragraphs. Compact uppercase labels summarize technical detail; longer editorial sentences belong in company statements.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a familiar fragmentation problem and resolve it with a warm final clause. | 6–10 words | “All your locations, together at last.” |
| Support | State the product category, design attitude and intended user in one sentence. | 10–18 words | “A designed location management system for the screen industry.” |
| Chapter title | Concrete action verb plus a useful object. | 3–5 words | “Grow your library”<br>“Present and collaborate” |
| Action | Plain verb phrase; lowercase presentation. | 3–5 words | “Create a free account”<br>“Request a feature” |
| Assurance | A short principle followed by specific reader control. | 2–5 word label, one sentence explanation | “PRIVATE BY DEFAULT”<br>“Location data is only visible to people you explicitly invite. Fine tune who can see what.” |
| Company belief | First-person belief connecting thoughtful work to a concrete change. | 15–25 words | “We believe that thoughtfully designed software has the power to transform how we work.” |

**Words and phrasing to use:** thoughtfully; together; your; gather; organise; showcase; crafted; in control; private by default

**Avoid:** revolutionary; game-changing; 10x; unleash; synergy; dominate; effortless magic

**Rules:**

- Anchor every chapter in an observable action, then explain its consequence.
- Use technical specifics for assurance rather than absolute superlatives.
- Let one parenthetical word add humanity; keep the surrounding sentence useful.
- Use short uppercase phrases for annotations, not long promotional paragraphs.

## Do's and Don'ts

### Do

- Keep ordinary display headlines at 39px and regular weight; reserve 10vw type for the closing field.
- Use 52px content side padding and 26px two-column gutters on desktop.
- Retain 182px intervals between major narrative groups.
- Align chapter support to the title column, not to its muted number.
- Frame broad product views on #1a1a1a backplates with 6.5px corners.
- Use 13px uppercase mono annotations with 0.08em tracking beneath media.
- Keep action keys content-width, with 3.3px corners and compact padding.
- Put black text on the orange closing field and maintain the large empty area above the directory.

### Don't

- Do not turn the default body into a 16px sans-serif interface; retain the small slab-serif texture.
- Do not give each feature its own bright colored card; the main chapters live on continuous black.
- Do not replace tiny rectangular keys with 48px-tall pills.
- Do not introduce frosted glass, colorful drop shadows or gradient borders around content.
- Do not center every section: only the photographic product opening uses the centered promise.
- Do not enlarge pricing numerals into display type; prices are compact uppercase mono.
- Do not make the footer a shallow dark link strip; the orange word field is a major composition.
- Do not add large feature illustrations where short uppercase annotations provide the detail.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color transitions without a usable duration on the button rule.
- Plan rows declare a 0.25s transition and a slate-grey hover border.
- Other elements declare opacity transitions of 0.25s, 0.75s and 1.5s; headline words use clipped wrappers.

**Transfer:**

- If revealing chapter headings word by word, preserve the final natural serif line arrangement and compact word spacing.
- Use edge and text-color changes for action feedback instead of scaling the small keys.

**Unknown:**

- Exact timing and easing assignments for the opening scene and scroll reveals are unknown.
- Expanded FAQ behavior and video playback states are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 500px, 550px, 760px, 768px, 950px, 1000px and 1200px.
- The closing name scales at 10vw; small serif headings use clamp(1.3rem, 2.8vw, 1.5rem).
- Header markup contains shorter alternate action wording and mobile-hide elements.

**Transfer:**

- On narrow layouts, preserve the environmental image, dark fade and centered short promise; reduce the reading inset before crowding the text.
- Stack two-column reading sections and reduce four-column caption groups to fewer columns while retaining the 13px rhythm.
- Keep the two closing name fragments pulled apart and allow the directory to stack below its rule.

**Unknown:**

- Exact narrow-screen layouts, image focal points and breakpoint-to-component assignments are unknown; the stacking rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
