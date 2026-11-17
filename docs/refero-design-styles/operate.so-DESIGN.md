# Operate — punched paper machinery

## Overview

A green mechanical workbook with a surprisingly human voice. Pale sheets hang inside a textured, patterned green field, with punched edges, linking straps and fine drafting curves giving software the feeling of a well-arranged workshop. Grotesk headings and readable paragraphs sit beside technical labels and softly raised interface demonstrations; the composition is spacious at the top and becomes more editorial and information-rich below.

### Essentials

- The page is a physical sheet assembly, not an edge-to-edge software canvas: #ebebeb paper with 1px #29211e outlines sits inside a #005c00 patterned field, with punched holes, side rails and linking straps.
- Headlines feel useful rather than monumental: denim at 48px/56px, weight 600, normal tracking, wrapped into three left-aligned lines within 400px; the opening pairs equal-width text compartments above the demonstration.
- Green is both ink and machinery: #117025 carries headings, rules and actions; most reading area remains pale gray, with a single broad #94ba9d editorial insert and saturated green largely exposed around the sheets.
- Actions are compact rounded rectangles rather than pills: 36px height, 12px radius, 18px/20px regular text and 7px 15px padding; pair a filled green action with a fine green outline.
- Drafting marks organize the story: 1.3px green rules, 8px square endpoints and oversized quarter-circle sweeps frame content. Retain this device even when there is no product artwork.
- Product proof is a light working surface: a 1134px-wide, 12px-radius demonstration frame with 24px padding and an overlapping white detail panel. When no interface exists, create a legible workflow board in the same raised-paper treatment.
- The ending remains an object: a separate 317px-high paper footer carries a small green video card, stacked links and a repeat conversion action, with a diagonal folded strip at the outer edge.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Printed green | `#117025` | `--color-ink` | text, border, action, accent, link | Primary marketing ink, drafting rules, small registration squares and filled actions. |
| Machine green | `#005c00` | `--color-field` | background | Patterned outer field visible above, between and around the paper sheets. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pattern mint | `#85c093` | `--color-mint` | accent, surface | Dotted field pattern, archival label and video inner mat. |
| Video casing | `#77aa83` | `--color-video` | surface | Small footer video-card outer casing. |
| Sage insert | `#94ba9d` | `--color-insert` | surface | Broad editorial statement insert; keep green text on this pale green panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#29211e` | `--color-charcoal` | text, border | Sheet outlines, chapter rules and explanatory body text. |
| Metallic paper strip | `#dcdcdc` | `--color-strip` | surface | Navigation backing under the fine diamond lattice. |
| Pale action ink | `#e0e0e0` | `--color-button-label` | text, border | Filled-action label and its light border. |
| Workbook paper | `#ebebeb` | `--color-paper` | background, surface | Main reading sheet, footer sheet and secondary action fill. |
| Demo shell | `#fcfcfc` | `--color-demo-shell` | surface | Raised outer demonstration frame. |
| White | `#ffffff` | `--color-white` | surface | Action hover fill and translucent chapter-heading strips; 60% white over paper reads as a very pale gray. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Demo interior | `#f7f7f7` | `--color-demo-interior` | surface | Light gray inner application backing. |

## Typography

- **denim** — Marketing headlines, paragraphs, actions and chapter labels. Straightforward contemporary grotesk with open counters and a sturdy semibold cut. OpenType features: "liga" 0. If unavailable, use **Inter**. Use 400 and 600; retain normal tracking and deliberate line wrapping. Font stack: "denim", "Inter", Arial, sans-serif.
- **cinetype** — Navigation markings, outcome captions and footer video label. Compact technical sans with a typewritten, equipment-label feeling. OpenType features: "liga" 0. If unavailable, use **Space Grotesk**. Use 400 with the specified label tracking. Font stack: "cinetype", "Space Grotesk", Arial, sans-serif.
- **Courier New** — Archival subject and date markings inside the small document label. Conventional typewriter monospace. Font stack: "Courier New", monospace.
- **muoto** (only for product demonstrations) — Application text inside the staged interface. Soft, practical UI sans distinct from the marketing typography. If unavailable, use **DM Sans**. Font stack: "muoto", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | denim | 600 | 48px | 1.167 | normal | Opening headline; maximum text width 400px. |
| heading | denim | 600 | 32px | 1.125 | normal | Section introduction and broken-line editorial statement. |
| body | denim | 400 | 20px | 1.35 | normal | Opening explanation and chapter paragraphs; green in introductions, charcoal in the chapter list. |
| editorial-body | denim | 400 | 18px | 1.333 | normal | Multicolumn statement text on the sage insert. |
| action | denim | 400 | 18px | 1.11 | normal | Primary and secondary opening actions. |
| chapter-title | denim | 600 | 18px | 1.222 | normal | Short title in each numbered chapter strip. |
| footer-link | denim | 400 | 16px | 1.375 | normal | Vertical footer utility links. |
| outcome-caption | cinetype | 400 | 14px | 1.273 | normal | Three-part benefit caption next to the outcome label. |
| navigation | cinetype | 400 | 14px | 1.714 | 0.05em, uppercase | Left word label and right trial link on the narrow header strip. |
| small-action | denim | 400 | 14px | 1.143 | normal, uppercase | Compact contact action in the section introduction. |
| media-label | cinetype | 400 | 14px | 1.214 | 0.05em | Label above the small footer video. |
| tag | denim | 600 | 12px | 1.167 | normal, uppercase | Tiny outlined outcome label beneath a chapter paragraph. |
| archive-number | Courier New | 300 | 12px | 1.167 | normal | Small version number in the archival label. |

**Notes:**

- Marketing typography uses normal tracking at every headline size; do not import the tight negative tracking typical of oversized software sites.
- Semibold headings sit beside regular paragraphs, and chapter paragraphs begin with a short semibold sentence. Keep the title strip smaller than the body copy.
- Technical labels are not a replacement for the body font: use the 0.05em tracking only for navigation and media labels.

## Layout

**Density:** Airy sheet-level composition with compact controls and densely useful editorial chapters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Registration-square size and small decorative spacing. |
| 16px | Paragraph-to-outcome-caption separation. |
| 24px | Demonstration-frame padding and stacked introductory spacing. |
| 28px | Inner side padding within ruled content compartments. |
| 30px | Vertical gap between numbered chapters. |
| 44px | Gap between separate paper assemblies. |
| 51px | Opening support-copy to action-row gap. |
| 53px | Opening text block to product demonstration. |
| 56px | Editorial column gap. |
| 64px | Separation before the editorial insert. |
| 74px | Desktop sheet side inset around the internal content grid. |
| 96px | Product demonstration to chapter-section separation. |

### Containers and grids

- **outer assembly**: max width 1474px · side padding 38px. Centered paper assembly within the patterned field. At 1440px the sheet is 1364px wide.
- **sheet content**: max width 1214px · side padding 28px. Main ruled content width inside the paper's 74px side inset.
- **opening pair**: 2 columns · gap 0px. Equal-width ruled text compartments; left headline, right support and actions.
- **chapter assembly**: 3 columns · gap 0px. 280px introduction rail, flexible 654px middle rail at desktop, and 280px ruled notes rail. The middle rail has 28px inner padding on each side.
- **editorial columns**: 4 columns · gap 56px. Narrow newspaper-like text columns with a small archive label attached at the top right.
- **demonstration**: max width 1168px · side padding 24px. Raised product frame centered beneath the opening; actual desktop frame width 1134px.

## Corner radius

| Element | Radius |
| --- | --- |
| main actions | 12px |
| contact action | 8px |
| outcome label | 3px |
| video casing | 6.5px |
| archive label | 4px |
| demonstration frame | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| demonstration lift | `0px 4px 4px -4px rgba(0,0,0,0.14), 0px 1px 1px -0.5px rgba(0,0,0,0.08), 0px 12px 24px -6px rgba(0,0,0,0.08), 0px 8px 16px -4px rgba(0,0,0,0.1)` | Lift the product demonstration above the flat paper; no equivalent shadow on the large marketing sheet. |

### Surfaces

#### Patterned machine field · level 0

**Use:** Outer background behind all sheet assemblies.

**CSS:** `background-color: #005c00`

**Observed:** Vertical dotted mint tracks, scattered outlined rings and small asterisks sit over a grainy green field. Paper rails run down both sides.

**Transfer:** Keep the field visibly exposed at the top, edges and sheet breaks; use the mechanical field artwork recipe.

#### Punched paper · level 1

**Use:** Main content and separate footer assembly.

**CSS:** `background-color: #ebebeb; border: 1px solid #29211e; border-radius: 0px`

**Observed:** Flat rectangular paper with paired punched openings along the sides; short pale straps connect through the holes to the outer rails.

**Transfer:** Treat several content sections as one continuous physical sheet rather than individual floating cards.

#### Sage document insert · level 2

**Use:** Editorial point-of-view panel.

**CSS:** `background-color: #94ba9d; color: #117025`

**Observed:** Broad flat insert inset within paper; small circular cutouts flank a center rule. Vertical green rules continue beyond the fill.

**Transfer:** Use one substantial tinted statement area rather than tinting every feature block.

#### Raised demonstration · level 2

**Use:** Product-proof stage.

**CSS:** `background-color: #fcfcfc; border-radius: 12px; padding: 24px; box-shadow: 0px 4px 4px -4px rgba(0,0,0,0.14), 0px 1px 1px -0.5px rgba(0,0,0,0.08), 0px 12px 24px -6px rgba(0,0,0,0.08), 0px 8px 16px -4px rgba(0,0,0,0.1)`

**Observed:** A fine edge and dark top/bottom outline segments define a light application frame. A floating white panel projects past its right edge.

**Transfer:** Keep the marketing sheet flat and reserve this physical lift for working-product proof.

## Components

### Navigation strip

**Use:** Minimal header with identity and a single trial action.

**CSS:** `height: 58px; border: 1px solid #29211e; background-color: #dcdcdc; position: relative`

**Text style:** `navigation` — cinetype 400 · 14px/1.714 · tracking 0.05em · uppercase

**Observed:** Diamond-lattice backing and end punches surround a translucent inner strip with green top/bottom rules. Left identity, small centered mark, right trial link; the inner strip is 24px high with 22px side padding.

**Transfer:** Replace the center mark with a small original symbol; preserve the spare three-anchor composition.

### Primary button

**Use:** Opening and footer conversion action.

**CSS:** `background-color: #117025; color: #e0e0e0; border: 1px solid #e0e0e0; border-radius: 12px; padding: 7px 15px; height: 36px`

**Text style:** `action` — denim 400 · 18px/1.11

**Observed:** Text-only compact action, placed before the outlined video button in the opening and repeated alone at the footer's upper right.

**States:** Declared: hover background #ffffff, border-color #117025, color #117025; focus-visible border-radius 6px, outline none and zero visible box-shadow.

### Secondary button

**Use:** Video action alongside the main conversion.

**CSS:** `background-color: #ebebeb; color: #117025; border: 1px solid #117025; border-radius: 12px; padding: 7px 15px; height: 36px`

**Text style:** `action` — denim 400 · 18px/1.11

**Observed:** Text only; same baseline and height as the primary action, with a 4px gap between buttons.

**States:** Declared: hover background #ffffff; focus-visible border-radius 6px, outline none and 4px green ring using color-mix(in srgb, lab(40.4038% -46.3181 39.9606) 60%, transparent).

### Contact button

**Use:** Low-emphasis action within an explanatory rail.

**CSS:** `color: #117025; border: 1px solid #117025; border-radius: 8px; padding: 3.8px 6.8px; height: 26px`

**Text style:** `small-action` — denim 400 · 14px/1.143 · uppercase

**Observed:** Small uppercase outlined rectangle below the introduction, not a full-width CTA.

**States:** Declared: hover background #ffffff; focus-visible border-radius 6px, outline none and zero visible box-shadow.

### Chapter strip

**Use:** Title row for a numbered implementation or capability chapter.

**CSS:** `display: flex; align-items: center; column-gap: 14px; background-color: rgba(255,255,255,0.6); border-top: 1px solid #29211e; border-bottom: 1px solid #29211e; padding: 1.5px 6px 0.5px 3px; height: 26px`

**Text style:** `chapter-title` — denim 600 · 18px/1.222

**Observed:** Regular charcoal ordinal precedes a semibold green title; an outlined circular indicator aligns at the far right. Paragraph and outcome row follow below.

**Transfer:** Use short chapter nouns and a numbered sequence appropriate to the new story.

### Outcome tag

**Use:** Label the result of a chapter before a technical caption.

**CSS:** `color: #117025; border: 1px solid #117025; border-radius: 3px; padding: 0px 3px`

**Text style:** `tag` — denim 600 · 12px/1.167 · uppercase

**Observed:** Tiny outlined uppercase label, then a small right-pointing separator and a three-part caption divided with middle dots.

**Transfer:** Name a tangible result rather than a technology category.

### Footer link

**Use:** Utility and social links in a short vertical list.

**CSS:** `color: #117025; position: relative; width: fit-content`

**Text style:** `footer-link` — denim 400 · 16px/1.375

**Observed:** Links are stacked with 2px gaps and have fine dotted underlining, not large navigation columns.

**States:** Declared: focus-visible border-radius 6px, outline none and zero visible box-shadow.

### Video card

**Use:** Small media invitation in the closing sheet.

**CSS:** `display: block; width: 276px; background-color: #77aa83; border-radius: 6.5px; padding: 14px 18px 12px; text-align: left`

**Text style:** `media-label` — cinetype 400 · 14px/1.214 · tracking 0.05em

**Observed:** Green status dot and tracked technical label sit above a mint inner mat enclosing a pale textured thumbnail. The complete casing is 203px high.

**Transfer:** Show an original process or working scene in subdued mint monochrome rather than a brightly colored poster.

### Archive label

**Use:** Document-like annotation attached to the editorial insert.

**CSS:** `background-color: #85c093; color: #29211e; border-radius: 4px; padding: 11px 8px 4px; width: 161px`

**Text style:** `archive-number` — Courier New 300 · 12px/1.167

**Observed:** A small identity/version header, subject line and date/index cells are separated by thin charcoal rules; the label is 95px high.

**Transfer:** Use truthful release or document metadata, with a typewritten subject and small technical field names.

## Imagery and graphics

### Mechanical field artwork

**Use:** Signature backing visible throughout the page.

**Observed:** Deep green grain is overprinted with closely spaced vertical mint dotted tracks, scattered hollow circles, occasional solid rings and small starbursts. It reads like patterned machine stock rather than a circuit-board photograph.

**Transfer:** Recreate the patterned field even without product media; keep it outside the reading sheet.

**Build:** Use #005c00 as a base. Tile an SVG 23.5px wide by 4.5px high containing a 1.5px square in #85c093 at the origin. Layer a larger sparse SVG repeat with thin mint circles of varied sizes and occasional eight-ray asterisks, at reduced opacity. Add fine monochrome noise at opacity 0.2 with mix-blend-mode: overlay. Keep the dot tracks stronger than the grain.

### Paper hardware and drafting curves

**Use:** Signature framing around the header, main sheet and ending.

**Observed:** Narrow pale rails, repeated oval punches and short horizontal straps attach the sheets to their backing. Inside, thin green straight rules flow into large quarter-circle sweeps, terminated by square registration points. The footer has a skewed lattice-covered fold at the right edge.

**Transfer:** Retain the hardware silhouette and drafting geometry for any subject. A simple SVG version is sufficient; it must still feel like connected paper rather than a browser window.

**Build:** Draw flat #ebebeb sheets with 1px #29211e outlines. Place paired 18px-wide round-ended punch outlines near both side edges and cut their interiors to reveal the green backing. Connect selected punches to 12px-wide outer pale rails with short rectangular straps. Use unfilled SVG paths with 1.3px #117025 strokes for long rules and quarter ellipses; anchor them with 8px square green marks. Create a narrow skewed paper polygon at the footer edge, with fine diagonal lattice lines and one punched circle. Scale curves with each compartment; never run them through text.

### Working interface demonstration

**Use:** Dominant product-proof image immediately below the opening text.

**Observed:** A broad off-white desktop application shows a quiet sidebar and central conversation/workflow area; an enlarged rounded white detail panel overlaps the lower-right area. Small colored integration symbols provide the main non-green accents. This scene is much wider than either text compartment.

**Transfer:** Stage a genuine task in the new product with one overlapping detail panel. If there is no finished UI, draw an honest conceptual workflow board with readable labels, low-contrast gray panels and green active states; avoid fabricated performance statistics.

### Editorial document details

**Use:** Small-scale character within the sage statement panel.

**Observed:** Multicolumn text is accompanied by archival labeling, date markings, punched circles and a tiny hand-drawn bouncing-ball-like flourish; these are document details, not photographic content.

**Transfer:** Use an original small line doodle or technical marginal mark, subordinate to the text.

**Build:** Keep the archival label mint with charcoal fine rules. Add one small charcoal circle with two curved motion paths and a short scribbled landing mark; use thin irregular SVG strokes. Limit the illustration to a marginal annotation, not a hero object.

### Icons

**Observed:** Marketing framing uses square endpoints, round status dots and small circular indicators. Interface icons are mostly 15–18px, with 1px round-cap outlines in muted gray-green; integration logos appear as tiny colored exceptions.

**Transfer:** Keep marketing symbols geometric and sparse. Choose consistent thin round-cap UI icons inside demonstrations only; do not turn every chapter into a large illustrated icon card.

## Section recipes

How recurring sections are built.

### First screen: Ruled pair opening

**Observed:** A textured green field and pale side rails establish the background. A 58px-high lattice navigation strip floats above the main rectangular paper, separated by 44px. The main sheet begins around 210px down the desktop view; its opening content has a 97px top inset and 74px side insets. Two equal 607px compartments fill a 1214px-wide grid. The left holds a green 48px/56px semibold headline in three lines within 400px; the right holds a 20px/27px support paragraph within 488px, followed after 51px by Primary button and Secondary button. Thin rules, 8px square endpoints and opposing quarter-circle sweeps frame these compartments. The Raised demonstration begins 53px below the text area and is visible from roughly 622px down: the first 900px include the full header, headline, support, actions and upper part of the application, with the rest of the demo below the fold.

**Transfer:** Keep the field, sheet hardware and two-compartment promise. Replace the interface with an original task board if needed, maintaining the same broad object scale and overlap. A narrower-purpose page can open with a shorter headline and a task-specific explanation while preserving the ruled pair.

**Avoid:** Do not center the headline above a giant floating dashboard, enlarge it into a full-width typographic billboard, or remove the mechanical outer frame.

**Text style:** `display` — denim 600 · 48px/1.167

### Raised proof stage

**Observed:** Working interface demonstration fills the inner sheet width inside Raised demonstration, with one overlapping detail panel at the right. Small carousel dots and a pause control sit just below; the main frame remains calm and pale.

**Transfer:** Demonstrate one complete job rather than showing a collage of unrelated feature tiles.

### Numbered working chapters

**Observed:** A 32px/36px introduction occupies the left 280px rail, with 20px/27px supporting copy and Contact button. The central rail holds four Chapter strip entries separated by 30px, each followed by a paragraph with a semibold opening sentence and Outcome tag plus outcome-caption. A right-hand 280px notes rail is filled with faint dotted horizontal ruling. Vertical green rules and square endpoints define all three rails.

**Transfer:** Use the chapter-list construction for capabilities, onboarding or a service method. Adjust the number of entries to the story while retaining the ruled notes rail as an intentional workbook motif.

**Text style:** `heading` — denim 600 · 32px/1.125

### Sage editorial statement

**Observed:** A Sage document insert spans 1270px within the paper. Narrow columns separated by 56px gaps carry a broken-line 32px/36px assertion, then 18px/24px conversational paragraphs, selected semibold phrases and a dated team signoff. Archive label attaches at the top right; small punched holes and extended green rules preserve the physical-document impression.

**Transfer:** State a product philosophy through a concise contrast between an old way of working and a better environment. Keep the column rhythm and marginal details, without making this a testimonial or metrics strip.

**Text style:** `editorial-body` — denim 400 · 18px/1.333

### Detached folded footer

**Observed:** A separate Punched paper assembly is 317px high with 48px vertical and 74px horizontal padding. Two equal compartments repeat the opening geometry: Video card at the left with a broad quarter-circle sweep, stacked Footer link items and Primary button at the upper right, and a small identity/copyright line at the bottom. A diagonal lattice fold closes the outer right edge; patterned green continues below.

**Transfer:** Close with a compact media invitation and practical links rather than a second oversized sales headline. Preserve the folded edge and green-field breathing room.

## Page flow

**Storyline:** Promise and working proof → practical capability chapters → human point of view → compact media and conversion close.

### A product-and-service marketing landing page that makes an unfamiliar working model feel tangible

1. **Promise** — Equal ruled headline and explanation compartments with two small actions.
2. **Product demonstration** — Large light application stage with an overlapping task-detail panel and compact playback controls.
3. **Capability chapters** — Numbered ruled entries beside an introduction rail and dotted notes column.
4. **Point of view** — Sage multicolumn editorial insert with a short contrarian assertion and document annotations.
5. **Closing call** — Separate folded paper footer combining video, utility links and a repeat action.

**Transfer:** Adapt the narrative depth to the offering; preserve the paper assembly, drafting geometry, broad working-proof stage and distinctive physical ending without treating the section count as fixed.

## Writing

Practical, collaborative and gently opinionated. Technical ability is explained through human work, clear next actions and familiar places rather than mystical AI language.

**Do not copy:** Do not reuse the Operate identity, logo, product names, customer/example names, dates, performance claims or proprietary interface content. Source quotations below illustrate voice, not reusable claims.

- **Addressing the reader:** Use you and your team for the reader, we for the maker. Give the reader agency; the product supports judgment rather than replacing the person.
- **Rhythm:** Headlines are compact noun phrases or short contrasts. Paragraphs mix short declarative sentences with fuller explanations; chapter copy opens with a terse benefit sentence before explaining the method.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the working model and the audience in one direct phrase. | 6–10 words | “Collaborative AI for frontier sales organizations” |
| Supporting explanation | Explain the connection between the reader's material, a clear next step and a collaborative outcome. | 2 sentences | “Your team brings the relationships and the judgment. We bring everything they need to act on it.” |
| Chapter benefit | Begin with an imperative benefit, then describe the practical work behind it. | 4–7 words before explanation | “See your pipeline clearly.”<br>“Keep every deal moving.” |
| Editorial assertion | A short negative statement followed by a shorter human-centered correction. | 2 short sentences | “Software doesn't close deals. You do.” |
| Action | Plain verb-led invitation; no clever conversion language. | 2–4 words | “Get started”<br>“Watch the video”<br>“Talk to us” |

**Words and phrasing to use:** your team; together; judgment; what's next; workshop; prepared; arranged; where to focus

**Avoid:** revolutionary; 10x everything; autonomous magic; unleash; disrupt; AI-powered future

**Rules:**

- Translate a technical capability into what the reader can see, decide or do.
- Keep the human responsible for relationships and judgment.
- Use physical-work metaphors sparingly but concretely: materials, tools, rooms and places.
- Make three-part caption lists parallel and separate them with middle dots.

## Do's and Don'ts

### Do

- Keep the desktop opening headline at 48px/56px and weight 600 with normal tracking.
- Use 1px charcoal outlines on flat paper assemblies, not drop shadows.
- Repeat green 8px square registration points at the ends of fine drafting rules.
- Give chapter strips a 26px-high fine-rule construction with paragraphs below, not inside heavy cards.
- Keep the main buttons at 36px high and 12px radius; repeat the filled action in the footer.
- Use the 56px editorial column gap to keep the sage insert airy despite its narrow columns.
- Reserve layered shadows and overlapping white panels for the broad product demonstration.
- Carry the outer patterned field past the detached footer so the final sheet reads as a physical object.

### Don't

- Do not use a black or dark-green reading canvas: the large content sheet is #ebebeb.
- Do not make all marketing headings 48px; secondary introductions are 32px/36px and chapter titles 18px/22px.
- Do not apply negative headline tracking or heavy 800–900 weights.
- Do not replace the 12px action corners with fully pill-shaped buttons.
- Do not spread saturated blue, purple or orange across marketing bands; colored integration symbols belong inside demonstrations.
- Do not apply 16–24px rounded corners to every sheet or chapter; the paper edges remain square.
- Do not use a large photographic thumbnail or autoplay poster as the whole closing section; the video casing is only 276px wide.
- Do not promote tiny archival type into body copy; 12px typewriter markings are document annotations.

## Motion and responsive

### Motion

**Observed:**

- Primary, secondary and contact actions declare color/background/border transitions lasting 0.15s with cubic-bezier(0, 0, .2, 1).
- The working demonstration exposes a pause control and dot selectors; the selected dot becomes an elongated dark mark.

**Transfer:**

- Keep action changes small and material-like: fill and ink inversion rather than large translation.
- If the working scene cycles, retain the compact dot controls and explicit pause action beneath the stage.

**Unknown:**

- Scene-transition choreography and timings are not established.

### Responsive

**Observed:**

- Opening typography declares a smaller 36px/42px headline and 16px/22px support text below the medium layout.
- The opening and footer declare two columns at the medium layout; the chapter region declares a 280px introduction rail plus flexible content, adding its third rail at a wider layout.
- Main action classes declare a smaller 16px/19px label and 10px radius outside the desktop variant.

**Transfer:**

- On narrow layouts, stack the ruled compartments and preserve the green endpoint vocabulary. Prioritize headline, explanation, actions and then the working scene.
- Keep the chapter body readable before preserving the decorative notes rail; simplify the hardware to the sheet edge when space is tight.

**Unknown:**

- Exact mobile hardware placement, overlapping demonstration behavior and breakpoint-specific final geometry are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
