# Framer — electric canvas craft

## Overview

A black-on-black product showcase with rounded geometric headings, fine architectural divisions and small, practical controls. White and smoke-gray typography leaves almost all saturated color to vivid interface demonstrations, with electric blue as the functional accent. It suits creative tools and professional platforms that can show their output as well as their workflow; spacious chapters surround unusually detailed product scenes.

### Essentials

- Headlines feel drawn on a design canvas rather than typeset as corporate banners: GT Walsheim at 54px/1, weight 500 and -0.04em tracking, with 44px/1.1 section headings.
- The opening promises first and demonstrates immediately: a left-aligned headline about 744px wide, 18px support, compact actions and a 1200px-wide product stage beginning within the first 900px.
- Conversion controls stay tool-sized against monumental media: white primary and translucent charcoal secondary buttons, 34px high, 8px corners and 14px regular labels.
- Black is the architecture and color is the demonstration: #000000 canvas, #111111–#1a1a1a layers and #999999 support; electric #0099ff is concentrated in controls, tiny metrics and luminous product detail rather than broad page bands.
- Capabilities become a cutaway instrument panel: a shared 1200px frame, 1px dark rules, mixed-width cells and UI objects that fade into black above 18px arrow captions. Include this device with simplified but meaningful product artifacts when detailed UI is unavailable.
- The page invites use, not just purchase: marketing pages close with a centered 54px invitation above a 582px-wide charcoal task composer, short example chips and a discreet alternate path. For products without prompts, use a similarly compact task launcher or input-led activation card.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0099ff` | `--color-blue` | accent, action | Functional highlights and small numerical proof; the recommended pricing action uses a solid blue fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-primary` | text, action | Headlines, foreground labels and primary action fills. |
| Soft white | `#cccccc` | `--color-nav-text` | text | Navigation labels, rendered as white at 80% over black. |
| Smoke text | `#999999` | `--color-muted` | text | Paragraphs and secondary links; also white at 60% opacity over black. |
| Composer charcoal | `#1a1a1a` | `--color-raised` | surface | Task composer and secondary actions; secondary actions use white at 10% over black. |
| Frame edge | `#1a1a1a` | `--color-edge` | border | Fine outer frames and internal divisions; white at 10% over black is a related edge recipe. |
| Stage charcoal | `#171717` | `--color-stage` | surface | Inset demonstration backing, distinct from the black outer frame. |
| Chip charcoal | `#141414` | `--color-chip` | surface | Example task chips, white at 8% over black. |
| Panel charcoal | `#111111` | `--color-panel` | surface | Product windows and adjacent assistant panels. |
| Low-contrast hairline | `#0f0f0f` | `--color-hairline` | border | Subtle composer separators, white at 6% over black. |
| Black canvas | `#000000` | `--color-canvas` | background, text | Continuous page canvas and text on white actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| enterprise lead-generation pages | Input charcoal | `#121212` | `--color-input` | surface | White at 7% over black for lead-form fields. |

## Typography

- **GT Walsheim** — Hero and section headings, large paired statistics. Rounded geometric sans with broad lowercase forms, compact spacing and a friendly single-storey character. If unavailable, use **DM Sans**. Use weight 500 and preserve the tight display tracking. Font stack: "GT Walsheim", "DM Sans", sans-serif.
- **Inter Variable** — Body text, navigation, actions and captions. Regular-weight, neutral interface grotesk with clear small-size detail. Font stack: "Inter Variable", Inter, sans-serif.
- **Inter** — Example-task labels and form labels. Compact practical sans; medium weight for task suggestions. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GT Walsheim | 500 | 54px | 1 | -0.04em, features "ss02" | Default marketing hero and centered activation heading. |
| heading | GT Walsheim | 500 | 44px | 1.1 | -0.04em | Section leads and the smaller solution-page hero. |
| body | Inter Variable | 400 | 18px | 1.35 | -0.011em, features "cv01", "cv05", "cv09", "cv11", "ss03" | Support paragraphs, capability titles and arrow captions; title in white, support in smoke gray. |
| caption | Inter Variable | 400 | 15px | 1.35 | -0.007em, features "cv05", "cv11", "ss03" | Small capability summaries and supporting proof labels. |
| label | Inter Variable | 400 | 14px | 1.4 | -0.007em, features "cv01", "cv05", "cv09", "cv11", "ss03" | Navigation and footer links; compact feature lists. |
| button | Inter Variable | 400 | 14px | 1 | -0.02em, features "cv01", "cv05", "cv09", "cv11" | Primary and secondary button labels. |
| task-label | Inter | 500 | 12px | 1.4 | normal, features "cv01", "cv09", "tnum" | Example tasks beneath the activation composer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quantified capability demonstrations | stat-stack | GT Walsheim | 500 | 54px | 0.8 | -0.04em | Closely stacked metric and descriptor within capability artwork. |
| audience-specific testimonial openings | quote | Inter Variable | 400 | 24px | 1.2 | -0.0083em | Customer quotation beside a square interview video. |
| pricing pages | pricing-body | Inter Variable | 400 | 16px | 1.5 | -0.006em | Long-form answers in the narrow pricing FAQ. |
| enterprise lead-generation pages | form-label | Inter | 400 | 12px | 1.2 | normal | Labels above enterprise lead fields. |

**Notes:**

- Display tracking is consistently -0.04em at both heading sizes. Keep the medium weight rather than compensating with bold.
- Body and card titles share the same 18px recipe; white versus 60% white establishes the distinction, not an extra bold cut.
- There is no recurring uppercase eyebrow system. Lead most chapters directly with the heading.

## Layout

**Density:** Airy chapters contain dense tool demonstrations; small controls and closely paired title/support lines contrast with long black intervals.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Button pairs, product-panel gutters, example-chip spacing and inset frame padding. |
| 15px | Hero headline to support. |
| 20px | Page side safety padding and lead-form column gap. |
| 25px | Hero copy to actions and capability cell inset. |
| 30px | Inset demo captions and selected UI presentation margins. |
| 40px | Section heading to media; footer column gap. |
| 60px | Space between major demonstration panels and between expanded questions. |
| 100px | Opening top padding below the 64px navigation. |
| 120px | Default chapter top and bottom padding. |
| 150px | Bottom breathing room beneath the activation close. |

### Containers and grids

- **content**: max width 1200px · side padding 20px. Centered default for navigation, section headings and framed grids; at 1440px the main content starts 120px from either edge.
- **demo pair**: max width 1200px · 2 columns · gap 10px. Asymmetric 930px work area and 260px assistant panel.
- **capability grid**: max width 1200px · 3 columns · gap 0px. 400px base cells with selected artifacts spanning two cells; shared rules instead of detached cards.
- **solution grid**: max width 1200px · 2 columns · gap 0px. Equal 600px columns for illustrated capability explanations.
- **footer**: max width 1200px · 6 columns · gap 40px. Six actual columns with several stacked subgroups; a utility strip below. Preserve the six-column appearance rather than inferring columns from category count.
- **pricing questions** (only for pricing pages): max width 420px. Centered reading column for dense commercial questions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons and task chips | 8px |
|  | inset media and composer | 15px |
|  | large product window | 18px |
|  | demo shell and shared capability frame | 25px |
| enterprise lead-generation pages | lead fields | 10px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous page background.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** No alternating light marketing bands; black space joins chapters.

**Transfer:** Let output imagery, not page-wide paint, create shifts in mood.

#### Outlined frame · level 1

**Use:** Demonstration shells and connected capability grids.

**CSS:** `background: #000000; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 25px; overflow: hidden`

**Observed:** Thin perimeter and shared internal rules remain barely brighter than the canvas.

**Transfer:** Use a single perimeter around grouped cells, not a thick border on every object.

#### Inset stage · level 2

**Use:** Backing behind output previews.

**CSS:** `background: #171717; border-radius: 15px`

**Observed:** Large dark inset inside the black demo frame, with color carried by the output itself.

**Transfer:** Place two or three readable examples on this stage.

#### Product window · level 2

**Use:** Detailed interface presentations.

**CSS:** `background: #111111; border-radius: 18px; overflow: hidden`

**Observed:** Toolbars, content and small controls form a credible application window rather than a decorative card.

**Transfer:** Use simplified real workflow UI with a clear central result.

#### Black fade

**Use:** Merge product artifacts into capability cells.

**CSS:** `background: linear-gradient(90deg, rgba(0, 0, 0, 0) 0%, #000000 100%)`

**Observed:** UI edges, graphs and text disappear laterally or downward while the caption remains clear.

**Transfer:** Put a fade above the artifact only, never over its marketing caption.

## Components

### Navigation

**Use:** Persistent global orientation.

**CSS:** `position: fixed; height: 64px; top: 0px; z-index: 10; padding: 0px 20px; background: #000000`

**Text style:** `label` — Inter Variable 400 · 14px/1.4 · tracking -0.007em

**Observed:** A centered 1200px inner row: compact logo at left, short menu labels with tiny chevrons, then enterprise and pricing links; login and a small white sign-up control at the far right. The sign-up variant is 30px high.

**Transfer:** Keep the global row visually subordinate to the opening promise.

### Primary button

**Use:** Main self-serve conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #000000; border-radius: 8px; padding: 10px 14px; height: 34px; box-sizing: border-box; gap: 7px`

**Text style:** `button` — Inter Variable 400 · 14px/1 · tracking -0.02em

**Observed:** Text-only default, paired with a charcoal secondary action. The recommended plan uses blue in the upper pricing cards and white at the table's final action row.

**Transfer:** Use one clear verb and keep the label brief.

### Secondary button

**Use:** Read, browse or inspect supporting material.

**CSS:** `display: flex; align-items: center; justify-content: center; background: rgba(255, 255, 255, 0.1); color: #ffffff; border-radius: 8px; padding: 10px 14px; height: 34px; box-sizing: border-box; gap: 7px`

**Text style:** `button` — Inter Variable 400 · 14px/1 · tracking -0.02em

**Observed:** Usually aligned to the right of a section lead, or beside a primary hero action. Some solution and enterprise variants use white at 15%.

**Transfer:** Do not inflate these controls to compete with the section title.

### Demonstration shell

**Use:** A substantial workflow chapter.

**CSS:** `background: #000000; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 25px; padding: 10px; height: 640px; box-sizing: border-box`

**Text style:** `body` — Inter Variable 400 · 18px/1.35 · tracking -0.011em

**Observed:** Wide inset work surface above a lower caption, with a title, short smoke-gray explanation and right-aligned arrow action. A narrow dark assistant panel sits alongside rather than inside the caption.

**Transfer:** Show an input, useful output and editable working state, not a generic dashboard collage.

### Capability cell

**Use:** Explain one capability within a connected grid.

**CSS:** `background: #000000; padding: 25px; overflow: hidden; border-right: 1px solid #1a1a1a; border-bottom: 1px solid #1a1a1a`

**Text style:** `body` — Inter Variable 400 · 18px/1.35 · tracking -0.011em

**Observed:** The UI artifact occupies most of the cell; the link sits at the lower left. Large diagrams are deliberately cut off and faded; mixed-width cells give a composed rather than repetitive rhythm.

**Transfer:** Use one legible artifact per capability.

### Story ticker

**Use:** Quiet but substantial social proof.

**CSS:** `display: flex; gap: 10px; align-items: center`

**Text style:** `body` — Inter Variable 400 · 18px/1.35 · tracking -0.011em

**Observed:** A horizontal strip of black 360px by 460px cards with 18px corners, fine outlines, a centered white customer mark and a low-positioned story link. Partial cards continue beyond both viewport edges.

**Transfer:** Use verified customer marks or original project names; preserve the sparse card interior.

### Task composer

**Use:** Input-led activation near the end of marketing pages.

**CSS:** `background: #1a1a1a; border-radius: 15px; width: 582px; height: 186px; overflow: hidden`

**Text style:** `task-label` — Inter 500 · 12px/1.4

**Observed:** A spacious multiline input above a faint rule, with a small mode label at lower left and square upward-arrow submit at lower right; example tasks sit outside below.

**Transfer:** For a non-AI tool, make this a project starter, search or task launcher with equivalent usable affordances.

### Example task chip

**Use:** Reduce uncertainty beneath the task composer.

**CSS:** `background: rgba(255, 255, 255, 0.08); border-radius: 8px; padding: 0px 10px; height: 25px; display: flex; align-items: center; color: #999999`

**Text style:** `task-label` — Inter 500 · 12px/1.4

**Observed:** Four short suggestions sit in one close-packed row, with no pill silhouette or oversized icon.

**Transfer:** Choose concrete first tasks rather than abstract feature names.

### Footer links

**Use:** Dense global directory below the conversion area.

**CSS:** `display: flex; flex-direction: column; gap: 5px; color: #999999`

**Text style:** `label` — Inter Variable 400 · 14px/1.4 · tracking -0.007em

**Observed:** White category labels, gray links and occasional tiny new badges. The final utility strip carries a small mark, language, social icons, compliance marks, blue status dot and copyright.

**Transfer:** Organize by user task; preserve the low-contrast directory and compact status strip.

### Lead field

**Only for:** enterprise lead-generation pages

**Use:** Sales inquiry form fields.

**CSS:** `background: rgba(255, 255, 255, 0.07); border-radius: 10px; padding: 10px 15px; height: 40px; box-sizing: border-box`

**Text style:** `form-label` — Inter 400 · 12px/1.2

**Observed:** Labels sit above fields. Two 230px fields share a 480px row with a 20px gutter; a full-width 190px-high textarea follows. The white action sits opposite a small compliance-mark cluster.

**Transfer:** Pair an efficient form with brief reassurance, not a large boxed questionnaire.

## Imagery and graphics

### Luminous working canvas

**Use:** Signature product stage in the default marketing opening.

**Observed:** A wide dark application demonstration contains a deep blue working area at left and an assistant conversation at right. Electric cyan and blue edge light focuses attention on selected regions; the outer stage remains almost black.

**Transfer:** Show the new product's defining operation. Minimum acceptable version is an original dark interface with one meaningful result, a selected region and restrained edge light.

**Build:** Use a black rounded 1200px frame. Within it, place a large dark working pane and a smaller right-side control stack. Add a 1px blue selection rectangle, a thin cyan horizontal highlight near its top, and two shadow layers such as 0px 0px 8px rgba(0,153,255,0.7) and 0px 0px 30px rgba(0,153,255,0.25). Keep bloom local to the selected edge; do not flood the page with a blue background.

### Masked capability artifacts

**Use:** Connected feature grids and technical proof.

**Observed:** Dark tables, branch lists, browser bars, small charts and performance meters are enlarged and partially clipped. Blue bars and occasional purple chart lines supply isolated color; heavy black fades suppress detail away from the point of interest.

**Transfer:** Create simplified UI fragments with real labels and a single highlighted result. Keep the lower caption independent from the mask.

**Build:** Render each artifact on a charcoal rounded pane inside a black cell. Overlay a transparent-to-black linear gradient at the right or bottom edge, and clip to the cell. For a metric sculpture, stack a white 54px value and a descriptor at 0.8 line height, fading the descriptor toward black; use an abstract curved dark horizon behind it.

### Output showcase rails

**Use:** Visual proof between capability chapters.

**Observed:** Full-color finished sites appear as large landscape and narrow portrait previews in dense horizontal rails, with rounded corners and small gutters. They extend beyond the text container and sometimes the viewport; photography and large editorial typography belong to the showcased work, not the surrounding page.

**Transfer:** Show the new product's finished output in a mix of wide and narrow formats; preserve native colors and avoid recoloring all examples blue.

### Floating output cards

**Only for:** interactive product demonstrations

**Use:** Show creative range or an interactive result inside a demo shell.

**Observed:** Small rounded image cards form a receding, tilted ring on black. Saturated cyan skies, green landscapes, flowers and motion-blurred figures provide the color, while a fine selection rectangle frames the composition.

**Transfer:** Use product-relevant original images or generated output thumbnails. Retain the skewed depth and saturated cool palette rather than scattering flat rectangles across the page.

**Build:** Arrange eight rounded rectangles in an elliptical group inside an approximately 870px-wide work area. Vary widths from about 104px to 174px, with 20px corners; overlap front cards over smaller back cards. Apply modest independent rotation and perspective rotation around the vertical axis. Give rear cards slight blur and lower contrast; use soft black shadows beneath front cards.

### Interview proof

**Only for:** audience-specific testimonial openings

**Use:** Lead with a credible practitioner rather than an interface.

**Observed:** A 1200px-wide frame splits into two 600px squares: black quotation panel on the left and naturally lit interview video on the right. A small logo sits above the gray quotation; a translucent circular play button overlays the video. Four compact proof cells sit below.

**Transfer:** Use a real speaker in their working environment, subdued natural light and an authentic short quotation. Keep the portrait documentary, not a cutout over a gradient.

### Icons

**Observed:** Small simple arrows and chevrons accompany links. Feature-grid symbols are compact white outline marks; social icons are solid monochrome, generally 18px. The language utility uses a 12px outline symbol with 1.5px rounded strokes.

**Transfer:** Choose a consistent thin outline set for capabilities and small directional arrows for actions. Keep native colored symbols confined to product artifacts.

## Section recipes

How recurring sections are built.

### First screen: Promise above the working canvas

**Observed:** A 64px fixed black Navigation leaves a 100px black interval before the left-aligned hero. The 54px display heading wraps into two compact lines across about three fifths of the 1200px content width; the right side remains open. An 18px gray support line occupies about 683px below it with a 15px gap. Actions follow after 25px: Primary button, Secondary button and a small announcement link at the far right of the same row. After 40px, a 1200px by 674px rounded product video begins. Back to front: continuous Canvas, dark frame, working interface, local blue selection light and readable controls. Within the first 900px, the navigation, entire text/action cluster and upper 464px of the product stage are visible; the rest of the stage and the logo strip fall below.

**Transfer:** Use an equally direct outcome promise and an original Luminous working canvas. A simplified working pane with one selected result is sufficient when no polished video exists. Solution pages can use the 44px heading with a full editor view; audience pages can substitute Interview proof. Pricing opens with the 54px promise, a billing toggle and plan columns; enterprise opens with benefits and an immediately usable inquiry form.

**Avoid:** Do not center the default hero, use giant billboard type, put the text beside a tiny floating laptop, or cover the opening with a generalized gradient.

**Text style:** `display` — GT Walsheim 500 · 54px/1 · tracking -0.04em

### Chapter heading pair

**Observed:** A 1200px row aligns a 44px white heading at left with a small Secondary button near its lower right. Headings usually wrap over two lines; media follows after 40px. Support, when present, uses body text directly below.

**Transfer:** Give each chapter one concrete benefit or argument and one supporting destination.

**Text style:** `heading` — GT Walsheim 500 · 44px/1.1 · tracking -0.04em

### Editable workflow chapter

**Observed:** Demonstration shell and adjacent assistant occupy the shared container in a 930px/260px split with a 10px gutter. Chapters are 640px tall with 60px between shells. The inset output dominates; 18px title/support and a discreet action anchor the lower area.

**Transfer:** Demonstrate how work changes, not just a still list of features.

### Connected capability atlas

**Observed:** An Outlined frame joins three 400px base columns, with wide two-cell spans among single cells. Masked capability artifacts occupy the upper area and Capability cell captions sit low. The hosting metric pairs a bright value with a fading descriptor; the chart is a large, nearly black instrument panel.

**Transfer:** Include a connected cutaway grid to make breadth tangible; map the cell emphasis to the new product's strongest capabilities.

### Outcome and trust rails

**Observed:** Output showcase rails make a colorful interruption in the dark page. A separate Story ticker restores black-on-black restraint, showing centered marks and low story links rather than dense testimonial paragraphs.

**Transfer:** Separate visual output proof from customer endorsement so each has one clear job.

### Text-led explanation

**Observed:** Solution workflows and questions use a split layout: 44px heading in the left column, approximately 760px of numbered steps or expanded questions at right. Fine rules divide the rows; questions and answers share the 18px recipe with white and gray roles.

**Transfer:** Use this quieter section for process and objections after rich demonstrations.

### Activation close

**Observed:** A centered display heading sits above the Task composer with a 40px gap. Four Example task chips hug the bottom of the composer; a small alternate-path link sits below. The black section has 120px top and 150px bottom padding. It is followed by the six-column Footer links directory, not an oversized wordmark.

**Transfer:** Carry this input-led invitation into ordinary marketing pages. Enterprise instead repeats its inquiry form with benefit cells; pricing ends after expanded FAQ and a help link rather than adding an activation composer.

**Text style:** `display` — GT Walsheim 500 · 54px/1 · tracking -0.04em

### Commercial comparison

**Only for:** pricing pages

**Observed:** Four equal 300px plan columns occupy a shared 1200px frame. Small 18px plan names, descriptions and prices sit above 14px feature lists; actions align along the bottom. The recommended action is blue. A deeper three-plan comparison uses a descriptor column, fine ruled rows and persistent compact plan headers; category headings are 24px. Final actions repeat before a centered 420px FAQ column.

**Transfer:** Keep pricing legible and comparative without introducing a new bright card theme.

### Enterprise reassurance and inquiry

**Only for:** enterprise lead-generation pages

**Observed:** A shared frame places a two-by-two benefit matrix across half the width and a 480px lead form in the other half. White 18px benefit labels and gray explanations sit beneath small outline icons. Later chapters use two-column illustrated proof, a five-column compact feature matrix and a two-column security grid; the closing inquiry reverses the form/benefit emphasis.

**Transfer:** Bring sales conversion into the opening and repeat it only after specific reassurance.

## Page flow

**Storyline:** Promise → tangible working or outcome proof → capability chapters → credible adoption → low-friction next step → directory; comparison and lead-generation pages adapt the emphasis.

### Introduce a broad creative platform

1. **Promise** — Left-aligned promise, supporting explanation and compact paired actions above luminous product media.
2. **Workflow proof** — Logo strip, three large editable workflow chapters and an external-tool connection demonstration.
3. **Capability breadth** — Connected, masked capability atlas.
4. **Outcome and adoption proof** — Colorful output rails, black customer-story ticker and an ecosystem interface.
5. **Activation** — Centered task composer and example suggestions, then directory and status utilities.

**Transfer:** Lead with a result, prove the work and then show breadth; use the ecosystem chapter only when there is a genuine ecosystem.

### Explain a product category to an evaluating user

1. **Promise** — Smaller 44px hero, concise support and a full editor view.
2. **Value and capability** — Three-column text benefits, then a two-by-two illustrated grid.
3. **Process** — Split heading and numbered workflow rows.
4. **Proof and discovery** — Customer-story rail and four-column related-use grid.
5. **Objection handling and activation** — Expanded split-layout FAQ, centered composer and directory.

**Transfer:** Favor explanation over spectacle while retaining the dark product-led grammar.

### Make the product relevant to a specific professional audience

1. **Promise and proof** — 54px outcome promise followed by split quotation/video and four compact result cells.
2. **Outcome range** — Large colorful project rails and a six-cell use-case matrix with small corroborating marks.
3. **Workflow and capability** — Large workflow demonstrations and the connected capability atlas.
4. **Credibility and next step** — Three project examples, audience-discovery grid, task composer and directory.

**Transfer:** Replace generic claims with the audience's actual workflows and authentic practitioner evidence.

### Enable plan selection and resolve commercial uncertainty

1. **Selection** — 54px promise, billing toggle and four plan columns.
2. **Comparison** — Logo strip followed by a long ruled comparison with grouped categories and repeated plan headers.
3. **Decision** — Repeated plan actions and billing explanation.
4. **Objection handling** — Narrow expanded FAQ and help link; directly into the shared directory without a composer.

**Transfer:** Preserve the restrained density and make inclusions, limits and billing explicit.

### Convert larger organizations through technical reassurance

1. **Promise and inquiry** — 54px heading, four benefit cells and paired-column lead form.
2. **Adoption proof** — Compact customer outcomes and output showcase rails.
3. **Capability and assurance** — Two-by-two illustrated grid, compact feature inventory and security detail grid.
4. **Credibility** — Black customer-story ticker.
5. **Sales conversion** — Repeated inquiry form and reassurance matrix, then directory.

**Transfer:** Keep the same visual language but replace self-serve activation with a useful, concise sales form.

## Writing

Confident, practical and designer-literate, with occasional colloquial contrast to keep technical detail human. Claims are paired with visible workflows or specific outcomes rather than ceremonial brand language.

**Do not copy:** Do not reuse Framer names, logos, customer marks, artwork, model names, quotations, product claims, prices, compliance claims or performance figures. Replace them with the new product's verified content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Product descriptions can name the product in third person, while actions start with a verb.
- **Rhythm:** Short sentence-case headings often form two lines; supporting copy uses one or two compact sentences. Concrete lists are welcome, but slogans are followed quickly by specifics.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product category or audience outcome, then a sharp differentiator. | 7–15 words | “Deliver client sites faster with agents, without sacrificing craft” |
| Supporting line | State what the user can do and remove one familiar friction. | 12–30 words | “Create a free website visually — with AI, CMS, and hosting. No engineering handoff.” |
| Chapter headline | Use a plain benefit or a conversational contrast, not a category label alone. | 4–10 words | “Not just vibes, a full platform”<br>“Agents that work alongside you, not instead of you” |
| Primary action | Verb plus immediate outcome; specify the low-risk entry where true. | 2–5 words | “Get started for free”<br>“Talk to us” |
| Closing invitation | A direct, optimistic invitation toward the reader's next task. | 4–7 words | “Your next idea starts here” |

**Words and phrasing to use:** build; ship; canvas; editable; refine; publish; your team; built in; without handoff

**Avoid:** revolutionary; unparalleled; unlock your potential; synergy; the future of everything

**Rules:**

- State what stays under the user's control when describing automation.
- Use technical terms only where they explain an actual mechanism or buying requirement.
- Keep task suggestions concrete and outcome-shaped.
- Follow conversational claims with tangible details rather than stacking more slogans.

## Do's and Don'ts

### Do

- Keep display headings medium at 54px with -0.04em tracking.
- Use 44px headings to introduce substantial chapters without an eyebrow.
- Keep the main desktop composition within 1200px while letting proof rails exceed it.
- Pair 18px white titles with 18px smoke-gray support instead of adding multiple bold weights.
- Use 34px buttons with 8px corners against much larger media.
- Preserve shared 1px rules and mixed-width cells in the capability atlas.
- Place color inside output and selected controls, with black space between major scenes.
- End ordinary marketing pages with the input-led activation device and compact directory.

### Don't

- Do not turn the default black canvas into alternating white and gray bands.
- Do not use broad electric-blue marketing section fills; blue belongs to focused functional emphasis.
- Do not replace 8px action corners with full pills.
- Do not make every capability a detached light-gray card with a drop shadow.
- Do not scale ordinary paragraphs down to the 12px demonstration UI size.
- Do not make all output previews equal aspect ratio; the proof rails mix wide and portrait formats.
- Do not invent a giant closing wordmark; the ending is a usable task interface and directory.
- Do not turn the pricing FAQ into a colorful marketing-card grid; it is a narrow reading column.

## Motion and responsive

### Motion

**Observed:**

- Horizontal proof strips show translated rails and partial cards at the viewport edges.
- A 5s linear infinite shimmer is declared, along with input-blink and editor-spinner keyframes.
- Some text links declare a white hover color; selected pricing links declare an underline with 1px thickness and 0.25em offset. Button hover and focus appearances are not established.

**Transfer:**

- Keep rail motion and selection light subordinate to the readable product result; a static rail with partial neighbors preserves the composition.

**Unknown:**

- Rail speed, scroll choreography, most transition durations and focus/active appearances are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px and 1200px; pricing also declares a breakpoint around 1352px.

**Transfer:**

- Recommended adaptation: stack the 930px work area and narrow assistant panel below one another, prioritizing the output before commentary.
- Recommended adaptation: retain connected capability cells in fewer columns, wrap task chips and bound the composer to the available width.
- Recommended adaptation: stack enterprise form and benefit matrix while preserving label/field pairs and a full-width message field.

**Unknown:**

- Narrow-screen type sizes, navigation transformation and exact grid reflow are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
