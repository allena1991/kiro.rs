# Deno — icy serif machinery

## Overview

An approachable technical style that pairs warm, rounded editorial serifs with workmanlike variable sans and mono text. Most of the experience is pale blue-gray, punctuated by sky-blue controls, mint signals and dark interface panels. Dimensional browser illustrations, fine drafting patterns and softly grained blue atmospheres make complex software feel tangible without making the page dense.

### Essentials

- Editorial language sits inside an engineering frame: Moranga headings at 72px/1.1, weight 400, -0.025em tracking; secondary headings use 44px/1.1 with the same tracking, with one meaningful phrase colored #0077cc.
- The opening is a product identity on an icy atmospheric stage, not a dashboard billboard: a centered 576px × 107px identity graphic, a 702px maximum support line, and stacked actions inside a 622px-tall band beneath the navigation. Use a 72px serif product name if no identity artwork exists.
- Buttons feel like small physical keys: #66c2ff fill, 2px #0077cc border, 8px corners and a hard 2px 4px blue shadow; labels are bold 18px serif rather than generic sans pills.
- Color is concentrated in language and machinery: #f1f3f9 occupies most marketing sections, #0077cc marks selected words, and blue or mint fills belong mainly to controls, small signals and illustrations. Broad blue atmosphere belongs at the opening and closing, not behind every section.
- The page has a drafting-paper skeleton: 1280px outer rails, 56px inner side padding, 1px #cbd1e1 rules, 144px section breathing room and 128px chapter gaps. Include fine hatching or dot-grid material as a recurring signature.
- Software is staged as a constructed object: 2px outlined browser panels, 8px corners, pale blue title bars and unblurred 2px 4px offset shadows. Include at least one such explanatory object; a simplified workflow diagram is the fallback for a product without polished interface media.
- The ending returns to the opening's blue grain and gives a large serif invitation before a charcoal utility footer. Proof receives its own contrasting scale: a 72px sans metric or a 48px semibold quotation, not another row of tiny feature cards.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep teal ink | `#002633` | `--color-button-ink` | text, border | Primary button lettering and restrained dark-theme vertical rails. |
| Label blue | `#004166` | `--color-label-ink` | text | Small blue chip lettering. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Working blue | `#0077cc` | `--color-blue` | text, border, action, accent | Selected heading phrases, primary control borders and their hard shadows. |
| Sky key | `#66c2ff` | `--color-action` | action, accent | Primary button fill; highlighted text and diagram strokes on dark pages. |
| Pale sky | `#b3e0ff` | `--color-pale-blue` | action, border, surface | Secondary buttons, primary hover fill and browser title bars. |
| Ice blue | `#e0f0ff` | `--color-ice` | text, surface | Eyebrow chip fill and secondary hover fill; main text on dark infrastructure pages. |
| Signal mint | `#70ffaf` | `--color-mint` | background, action, accent, text | Site announcement strip, footer headings and positive illustration signals; runtime pages also use mint action pills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text | Proof cards, navigation backing and high-contrast lettering. |
| Outer paper | `#f8f9fc` | `--color-outer-canvas` | background, surface | Outer page ground and case-study cards. |
| Icy canvas | `#f1f3f9` | `--color-canvas` | background, surface | Dominant marketing section fill. |
| Dot mist | `#eaedf5` | `--color-dot` | accent, background | Low-contrast dots and engineering paper patterns. |
| Drafting rule | `#cbd1e1` | `--color-rule` | border | Outer rails, panel edges, hatch lines and hard translucent shadows. |
| Silver text | `#c2c4c7` | `--color-muted-light` | text | Footer links and supporting text over the runtime opening. |
| Panel frame | `#a8b2c8` | `--color-frame` | border, text | Browser panel outlines and quiet band labels; supporting text on dark infrastructure pages. |
| Quiet gray | `#9ea0a5` | `--color-subtle` | text | Lowest-priority footer text and utility markings. |
| Slate text | `#475269` | `--color-body` | text | Supporting paragraphs on the light canvas. |
| Charcoal rule | `#25272b` | `--color-dark-rule` | border, surface | Footer separators and dark runtime controls. |
| Charcoal footer | `#121417` | `--color-footer` | background | Shared closing utility area. |
| Midnight ink | `#0a0e1c` | `--color-ink` | text, surface | Core text on light backgrounds; dark product panels in the infrastructure variant. |
| Near black media | `#0b0d11` | `--color-dark-media` | background, surface | Customer logo image fields and dark runtime sections. |
| Runtime black | `#000000` | `--color-black` | text | Global navigation text; runtime page headings. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Terminal charcoal | `#191b1f` | `--color-code-panel` | surface | Terminal and code demonstration backing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark infrastructure pages | Deep navy | `#020617` | `--color-deep-canvas` | background | Main dark canvas. |
| dark infrastructure pages and comparison tables | Navy edge | `#242d3e` | `--color-deep-edge` | border, surface | Dark panel outlines; table text on light pricing pages. |

## Typography

- **Moranga** — Product marketing headings and blue physical-key labels. Soft, rounded, expressive serif with sturdy bowls and friendly terminals. OpenType features: "liga". If unavailable, use **Fraunces**. Use regular 400 and bold 700; tune optical size for a soft, sturdy rather than high-fashion result. Font stack: "Moranga", "Fraunces", "Georgia Pro", Georgia, serif.
- **Recursive** — Product marketing paragraphs, quotations, numerals, technical band labels and utility links. A slightly irregular technical variable family; sans-like in prose and mono-like in technical labels. Font stack: "Recursive", Inter, ui-sans-serif, system-ui, sans-serif.
- **Inter** — Shared navigation and footer; the runtime marketing variant uses it for headings and prose. Direct contemporary grotesk with a compact bold display cut. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **Menlo** (only for runtime documentation and code demonstrations) — Commands and terminal text. Conventional compact monospace. If unavailable, use **Roboto Mono**. Font stack: "Menlo", "Roboto Mono", Monaco, Consolas, "Liberation Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Moranga | 400 | 72px | 1.1 | -0.025em, features "liga" | Major product chapter headings, invitations and text-led openings. |
| metric | Recursive | 700 | 72px | 1.1 | -0.025em | Large standalone quantitative proof. |
| quotation | Recursive | 650 | 48px | 1.1 | -0.025em | Broad editorial customer quotation. |
| heading | Moranga | 400 | 44px | 1.1 | -0.025em, features "liga" | Feature headings and the compact video-led opening. |
| case-title | Recursive | 400 | 28px | 1.1 | -0.025em | Story-card titles. |
| body | Recursive | 400 | 18px | 28px | normal | Support lines and explanatory prose. |
| button | Moranga | 700 | 18px | 1 | normal, features "liga" | Primary action labels. |
| nav-category | Inter | 700 | 18px | 2 | normal | Main navigation category; ordinary links use regular weight at this size and line height. |
| utility | Recursive | 400 | 16px | 1.5 | normal | Underlined secondary links and compact technical text. |
| band-label | Recursive | 400 | 16px | 1.5 | normal, features "ss12" | Mono-like labels centered in hatched chapter bands. |
| button-small | Moranga | 700 | 14px | 1 | normal, features "liga" | Secondary actions and compact pricing controls. |
| eyebrow | Recursive | 650 | 14px | 1 | normal | Sentence-case status and category chips. |
| footer-heading | Inter | 700 | 14px | 1.25 | normal | Colored headings over footer link columns. |
| footer-link | Inter | 400 | 14px | 20px | normal | Footer utility links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| runtime marketing pages | runtime-display | Inter | 700 | 72px | 1.1 | -0.025em | Bold sans promise and chapter headings. |
| pricing pages | plan-name | Moranga | 400 | 30px | 1.2 | normal, features "liga" | Blue plan names over compact details. |
| FAQ sections | faq-question | Moranga | 400 | 28px | 1.1 | -0.025em, features "liga" | Full-width question controls. |
| runtime marketing pages | runtime-body | Inter | 400 | 18px | 28px | normal | Runtime feature prose. |
| runtime marketing pages | runtime-action | Inter | 400 | 16px | 1.5 | normal | Mint or charcoal pill labels. |
| runtime installation demonstrations | command | Menlo | 400 | 16px | 1.5 | normal, features "ss12" | Copyable single-line commands. |
| pricing and comparison tables | table-value | Recursive | 400 | 14px | 20px | normal | Numeric values and terse table descriptions. |

**Notes:**

- The core serif headings and large technical proof share -0.025em tracking; body text, chips, controls and navigation retain normal tracking.
- Color emphasizes words inside a sentence without changing their family, weight or size. This is not italic emphasis or gradient lettering.
- The opening identity is artwork with a 576px × 107px frame, not a 107px text recipe. A text-only identity uses display typography.
- Keep the sans runtime hierarchy a separate voice; do not blend its bold headline treatment into ordinary serif product chapters.

## Layout

**Density:** Airy chapters with compact controls: wide blank intervals separate explanations while links, labels and table details remain closely packed.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact heading support gaps, icon groups and FAQ bottom padding. |
| 12px | Footer link spacing and vertical primary-button padding. |
| 16px | Default text-stack gap and stacked action separation. |
| 24px | Navigation vertical inset and story-card horizontal padding. |
| 32px | Card padding, story grid gaps, chapter-band vertical inset and paragraph-to-action space. |
| 48px | Navigation group separation and closing action separation. |
| 56px | Main desktop inner side inset. |
| 64px | Footer top padding and intermediate breathing space. |
| 128px | Major chapter gaps and desktop feature-column separation. |
| 144px | Main chapter top and bottom padding. |

### Containers and grids

- **Outer rails**: max width 1280px · side padding 56px. Centered desktop section frame with faint vertical edges; at 1440px the outer margin is 80px and the usable content width is about 1168px.
- **Support measure**: max width 702px. Centered support text beneath major headings; prevents long technical sentences from spanning the whole frame.
- **Feature split**: 2 columns · gap 128px. A 2:3 text-to-media ratio, reversible from row to row; approximately 415px of text beside 623px of media.
- **Stories**: 3 columns · gap 32px. Equal-width story cards inside the main content width.
- **Questions**: max width 672px. Narrow centered column with left-aligned questions and answers.
- **Pricing matrix** (only for pricing pages): max width 1280px · 5 columns · gap 0px. Feature-label column plus four equal plan columns, each about 256px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Physical keys and browser panels | 8px |
|  | Proof and story cards | 6px |
|  | Eyebrow chips | 9999px (pill) |
| runtime marketing pages | Runtime actions | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Blue physical key | `2px 4px 0px 0px #0077cc` | Primary action controls. |
|  | Pale physical key | `2px 4px 0px 0px #66c2ff` | Secondary action controls. |
|  | Paper relief | `2px 4px 0px 0px rgba(203, 209, 225, 0.4)` | Product browser panels, proof cards and story cards. |
| dark infrastructure pages | Dark relief | `2px 4px 0px 0px rgba(30, 37, 59, 0.4)` | Dark feature and proof cards. |

### Surfaces

#### Rail canvas · level 0

**Use:** Default product marketing chapter.

**CSS:** `background: #f1f3f9; border-left: 1px solid #cbd1e1; border-right: 1px solid #cbd1e1`

**Observed:** An outer full-width top rule meets the centered frame; long chapters share this continuous paper ground.

**Transfer:** Use the rails to unify mixed layouts rather than boxing every feature.

#### Dotted paper · level 0

**Use:** Outer ground and illustrative paper fields.

**CSS:** `background-color: #f8f9fc; background-image: radial-gradient(#eaedf5 1.5px, rgba(0, 0, 0, 0) 1.5px), linear-gradient(0deg, rgba(0, 0, 0, 0), #f1f3f9 30%, #f1f3f9); background-size: 16px 16px, cover; background-position: -8.5px -3.5px, 0px 0px`

**Observed:** The low-contrast dot field is subordinate to text and can fade into solid paper.

**Transfer:** Use this behind diagrams or at exposed edges of the frame.

#### Atmospheric stage · level 0

**Use:** Opening and closing identity bands.

**CSS:** `background-color: #f1f3f9; position: relative; overflow: clip`

**Observed:** A pale cyan, blue-gray and white grained wash extends edge to edge, stronger toward a corner and dissolving toward the content. Dark lettering stays crisp in front.

**Transfer:** Use the blue-grain construction in imagery; preserve the luminous paper effect rather than exact color stops.

#### Browser shell · level 1

**Use:** Explanatory interface objects.

**CSS:** `background: linear-gradient(to right, #b3e0ff, #e0f0ff); border: 2px solid #a8b2c8; border-radius: 8px; box-shadow: 2px 4px 0px 0px rgba(203, 209, 225, 0.4); overflow: clip`

**Observed:** The blue gradient is most visible in the title bar; the content area returns to paper or contains an actual interface.

**Transfer:** Frame a tightly selected workflow, not a full unreadable desktop.

#### Paper relief card · level 1

**Use:** Proof and stories.

**CSS:** `background: #f8f9fc; border: 2px solid #cbd1e1; border-radius: 6px; box-shadow: 2px 4px 0px 0px rgba(203, 209, 225, 0.4)`

**Observed:** Solid geometry and shallow offset depth rather than floating glass.

**Transfer:** Keep the outline visible even over patterned paper.

#### Utility footer · level 0

**Use:** Shared end-of-page navigation.

**CSS:** `background: #121417; border-top: 1px solid #25272b`

**Observed:** A compact charcoal slab after the spacious final invitation.

**Transfer:** Keep this utility ending visually distinct from the conversion section.

#### Dark infrastructure canvas · level 0

**Only for:** dark infrastructure pages

**Use:** Long technical platform narratives.

**CSS:** `background: #020617; color: #e0f0ff`

**Observed:** Pale blue serif text, muted slate prose and sky-blue emphasis replace the light theme's ink and working blue.

**Transfer:** Carry the same rails and hierarchy through an entire themed narrative.

#### Dark relief card · level 1

**Only for:** dark infrastructure pages

**Use:** Feature diagrams and proof.

**CSS:** `background: #0a0e1c; border: 2px solid #242d3e; border-radius: 6px; padding: 32px; box-shadow: 2px 4px 0px 0px rgba(30, 37, 59, 0.4)`

**Observed:** Circular technical emblems occupy the upper part of tall cards; text sits below.

**Transfer:** Use restrained blue-lit mechanisms on dark navy, not glowing neon tiles.

## Components

### Primary button

**Use:** Default conversion control.

**CSS:** `display: flex; align-items: center; gap: 16px; background: #66c2ff; color: #002633; border: 2px solid #0077cc; border-radius: 8px; padding: 12px 20px; box-shadow: 2px 4px 0px 0px #0077cc`

**Text style:** `button` — Moranga 700 · 18px/1

**Observed:** A right chevron follows the label. Width follows content; the standard control is 46px tall.

**States:** Declared: hover background-color #b3e0ff.

**Transfer:** Use one leading conversion and keep supporting links visibly lighter.

### Secondary button

**Use:** Documentation, pricing or alternate entry.

**CSS:** `display: flex; align-items: center; background: #b3e0ff; color: #0a0e1c; border: 2px solid #66c2ff; border-radius: 8px; padding: 12px 20px; box-shadow: 2px 4px 0px 0px #66c2ff`

**Text style:** `button-small` — Moranga 700 · 14px/1

**Observed:** Placed under or beside the primary action. A compact variant uses 8px 12px padding; pricing conversion controls use the primary blue construction with the small label.

**States:** Declared: hover background-color #e0f0ff.

### Text link

**Use:** Secondary documentation and cross-reference actions.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 4px; color: #0a0e1c; text-decoration-line: underline`

**Text style:** `utility` — Recursive 400 · 16px/1.5

**Observed:** Can include a small external-link mark. In closing rows, two links are separated by a vertical bar.

### Navigation

**Use:** Shared sticky product navigation.

**CSS:** `position: sticky; top: 0px; z-index: 50; background: rgba(255, 255, 255, 0.9); height: 96px`

**Text style:** `nav-category` — Inter 700 · 18px/2

**Observed:** Logo at left; category and ordinary links across the middle; a compact outlined search field with keycap at right. Inner content uses Outer rails, 24px vertical inset and 48px main group gap. Categories are bold, ordinary links regular. Dark infrastructure pages use a near-black bar and a second product-navigation row.

**Transfer:** Keep the wordmark smaller than the hero identity; collapse category groups rather than squeezing them.

### Eyebrow chip

**Use:** Small status or section-context marker.

**CSS:** `background: #e0f0ff; color: #004166; border: 1px solid #b3e0ff; border-radius: 9999px; padding: 4px 10px`

**Text style:** `eyebrow` — Recursive 650 · 14px/1

**Observed:** Sentence-case capsule, centered over the opening or left-aligned over an explanatory statement.

### Chapter band

**Use:** A labeled transition between narrative chapters.

**CSS:** `background-color: #f1f3f9; background-image: linear-gradient(45deg, #cbd1e1 12.5%, #f1f3f9 12.5%, #f1f3f9 50%, #cbd1e1 50%, #cbd1e1 62.5%, #f1f3f9 62.5%, #f1f3f9 100%); background-size: 5.7px 5.7px; border-top: 1px solid #cbd1e1; padding: 32px 0px; text-align: center; color: #a8b2c8`

**Text style:** `band-label` — Recursive 400 · 16px/1.5

**Observed:** A plain horizontal center strip interrupts the fine hatching behind the centered label; the full band is about 89px tall.

**Transfer:** Use short narrative signposts rather than repeating the next heading.

### Story card

**Use:** Linked customer or outcome story.

**CSS:** `display: grid; background: #f8f9fc; border: 2px solid #cbd1e1; border-radius: 6px; box-shadow: 2px 4px 0px 0px rgba(203, 209, 225, 0.4); overflow: hidden`

**Text style:** `case-title` — Recursive 400 · 28px/1.1 · tracking -0.025em

**Observed:** A near-black logo field occupies roughly the top half; below it a left-aligned title and small blue reading link sit in 32px 24px padding. Three equal cards form one row; the dark variant changes the lower field to navy.

**States:** Declared: hover border-color #0077cc.

**Transfer:** Use a recognizable outcome identity or restrained product artifact in the upper field.

### Metric card

**Use:** A single large piece of quantitative proof.

**CSS:** `background: #ffffff; border: 2px solid #cbd1e1; border-radius: 6px; padding: 32px; box-shadow: 2px 4px 0px 0px rgba(203, 209, 225, 0.4)`

**Text style:** `metric` — Recursive 700 · 72px/1.1 · tracking -0.025em

**Observed:** Large number followed by a 16px explanatory caption; positioned beside a serif proof heading, not buried among many metrics.

### Footer link

**Use:** Shared utility navigation.

**CSS:** `display: block; color: #c2c4c7`

**Text style:** `footer-link` — Inter 400 · 14px/20px

**Observed:** Links form four columns beside the identity, with 12px gaps and a 16px separation below colored category headings. A bottom ruled row holds social icons, legal text and a green-dot status badge.

**States:** Declared: hover color #f5f5f5 and text-decoration-line underline.

### FAQ row

**Only for:** FAQ sections

**Use:** Question and expandable answer.

**CSS:** `border-bottom: 1px solid #0a0e1c; padding-bottom: 8px; margin-bottom: 32px`

**Text style:** `faq-question` — Moranga 400 · 28px/1.1 · tracking -0.025em

**Observed:** An unboxed, full-width left-aligned question with a rule directly below. Answers use compact utility text and links in a centered 672px column.

**Transfer:** Favor real implementation objections over promotional questions.

### Pricing cell

**Only for:** pricing pages

**Use:** Dense comparable plan values.

**CSS:** `border-right: 1px solid #cbd1e1; border-bottom: 1px solid #cbd1e1; height: 97px`

**Text style:** `table-value` — Recursive 400 · 14px/20px

**Observed:** Values sit inside padded wrappers. The plan header stays sticky below the navigation and shows blue serif plan names, recurring prices, short descriptions and compact physical-key actions. Hatched category dividers span the matrix.

**Transfer:** Use a common label column, equal plan widths and no floating rounded plan-card layout.

### Runtime pill

**Only for:** runtime marketing pages

**Use:** Documentation and installation entry points.

**CSS:** `background: #70ffaf; border-radius: 9999px; padding: 2px; overflow: hidden`

**Text style:** `runtime-action` — Inter 400 · 16px/1.5

**Observed:** An inner pill carries 16px 24px padding, a 16px icon gap and a trailing chevron; the full control is 60px tall. Dark hero controls reverse the fill to charcoal with white lettering; a traced mint rim animates around the outside.

**Transfer:** Keep this distinct from blue physical-key product controls.

## Imagery and graphics

### Blue grain atmosphere

**Use:** Signature light field for the opening and closing.

**Observed:** Soft cyan blooms and pale steel-blue cloudy layers, with fine paper-like grain; the left side is more saturated while the center remains light enough for dark text. There is no discrete scene or hard horizon.

**Transfer:** Recreate a luminous printed atmosphere behind a strong typographic identity; the minimum is layered cyan washes plus fine grain, not a flat blue rectangle.

**Build:** Over #f1f3f9 layer two oversized radial gradients: rgba(102,194,255,0.35) near the upper left and rgba(179,224,255,0.45) through the middle, both fading to transparent. Add a full-size SVG turbulence layer at low opacity for fine grain. Blur only the color layers, not the grain or lettering. Reverse the vertical emphasis for the closing band; exact stops are not essential.

### Constructed browser diagrams

**Use:** Signature explanatory media beside feature text.

**Observed:** Pale browser frames carry tiny traffic-light dots, simple connection lines, boxed choices and blue raised controls. Some contain live-looking dashboards or browser previews; others simplify the interface into a diagram. They typically occupy the wider three-fifths side of a split row.

**Transfer:** Show one mechanism, input-to-outcome or decision flow. The minimum acceptable version is a clean outlined browser shell with three labeled objects and a connected success result.

**Build:** Use Browser shell with a shallow blue title bar and three small colored dots. Set the inner field to Dotted paper; arrange simple rectangular nodes on a grid. Connect nodes with 1px solid blue and muted dashed lines; give active nodes a 2px blue outline and a shallow offset shadow. Reserve a mint rectangular strip for the successful result.

### Engineering patterns

**Use:** Signature texture under chapter transitions, proof and story fields.

**Observed:** Fine diagonal hatching, subdued 16px dot fields and pale square grids fade into the surrounding paper. Patterns reinforce rails without competing with content.

**Transfer:** Vary the pattern by narrative purpose while keeping the same low-contrast blue-gray material.

**Build:** Use Chapter band for hatching. For a square grid layer perpendicular repeating-linear-gradients with 1px #eaedf5 lines every 16px, then cover their edges with a radial gradient fading into #f1f3f9. For proof, overlay a diagonal solid-to-transparent paper gradient on the hatching.

### Dark infrastructure mechanisms

**Only for:** dark infrastructure pages

**Use:** Technical hero backdrop, architecture diagrams and feature emblems.

**Observed:** Rows of dim isometric navy cubes sit behind the left-aligned hero; other scenes use thin sky-blue connectors and schematic boxes. Tall feature cards carry concentric circular mechanisms with a small blue icon and a narrow luminous arc.

**Transfer:** Translate the product's modular structure into cubes or connected nodes. Keep most of the field nearly black, with blue used for legible relationships.

**Build:** For cubes, repeat SVG hexagons split into three shaded rhombi using #171c2b and #242d3e with low-opacity blue edges; fade the field behind text. For emblems use a 224px outer ring, a 156px navy disk, a 124px conic blue arc ring and an 88px shaded center. Keep the blue arc narrow and the center icon small.

### Demonstration video

**Only for:** video-led product pages

**Use:** Opening demo and implementation explanations.

**Observed:** The opening video uses a roughly 724px × 407px wide frame with an 8px radius and hard blue shadow. The presenter scene is warm, natural and indoor; the surrounding marketing surface stays icy and technical. A small underlined full-video caption sits below.

**Transfer:** Use a real demonstration or presenter video; preserve the physical blue frame and restrained caption rather than recoloring the footage.

### Runtime illustration and terminal world

**Only for:** runtime marketing pages

**Use:** Dark opening, code walkthroughs, proof charts and a warmer closing vignette.

**Observed:** The opening has dark horizontal blurred light streaks behind a vertical list with one mint highlighted item. White browser-code panels alternate with dark terminal demonstrations and benchmark cards. Small black outline character gestures add warmth; the closing pairs text with a square, thick-outlined illustrated desk scene in muted warm colors.

**Transfer:** Use a friendly product-adjacent drawing and genuine command or workflow examples. A simple warm desk illustration can replace a complex character scene.

**Build:** For the opening, layer thin horizontal cyan and mint gradients on near-black, blur them by 8px, and place a dark left-to-right scrim under text. Add a vertical stack of short mono labels with fading outer items and one mint rounded rectangle selected in the middle.

### Icons

**Observed:** Controls commonly use 14px filled chevrons, 16px external-link marks and compact monochrome navigation glyphs. Social marks are 24px or 28px; framework and partner marks are much larger at 64px. Technical diagrams use blue strokes and simple geometric forms.

**Transfer:** Use consistent small directional glyphs in actions, larger recognizable ecosystem marks only as proof, and simple line geometry for explanatory connections.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric identity opening

**Observed:** A 68px mint announcement precedes a 96px translucent white Navigation. Beneath it, the Atmospheric stage is 622px tall inside Outer rails. Back to front: icy paper, edge-to-edge blue grain wash, faint vertical rails, then a centered Eyebrow chip, a 576px × 107px serif identity graphic, an 18px support line and stacked actions. The identity occupies about two-fifths of the viewport width, not the entire screen. The chip sits 16px above the identity; support sits 16px below it. The action group starts after 32px additional space: Primary button followed by Text link. The first 900px contain the entire opening, its actions and the 89px Chapter band; the substantive feature chapter begins below.

**Transfer:** For a new product, use its own typographic identity or a short 72px serif product-name line, keeping the compact centered group against a wide luminous field. Without artwork, the type itself is the main object. A pricing opening uses a centered two-line promise with a blue lead phrase; a video-led page uses a 44px serif promise on the narrower left side beside a wide framed video. A dark infrastructure opening switches to left alignment over a dim geometric field.

**Avoid:** Do not insert a huge dashboard beneath the hero copy, enlarge the small identity to fill the viewport, or replace the grained paper field with a hard saturated gradient.

**Text style:** `display` — Moranga 400 · 72px/1.1 · tracking -0.025em

### Chapter heading pair

**Observed:** A centered display heading highlights one phrase in blue and follows with body text within Support measure. A Chapter band can introduce the topic; there is 128px separation before substantial feature rows.

**Transfer:** Use the blue span to name the central benefit or capability, not every noun.

**Text style:** `display` — Moranga 400 · 72px/1.1 · tracking -0.025em

### Alternating feature mechanism

**Observed:** Feature split pairs a heading, one or two short paragraphs and an occasional action with a Constructed browser diagram or framed interface. The text occupies two-fifths, the media three-fifths, separated by 128px. Rows alternate sides while sharing rail alignment.

**Transfer:** Organize around one understandable outcome per row. A diagram can stand in for a product interface when it better explains the mechanism.

**Text style:** `heading` — Moranga 400 · 44px/1.1 · tracking -0.025em

### Definition statement

**Observed:** A small chip introduces a broad left-aligned serif definition at 60px/1.1 with -0.025em tracking. A blue product phrase and underlined platform reference sit within the statement, with a bold clarifying sentence and compact prose below.

**Transfer:** Use for an unfamiliar category or complex concept; say what the product is before listing capabilities.

### Proof spotlight

**Observed:** A large serif heading sits opposite Metric card; beneath, a broad quotation uses quotation typography, an oversized hanging opening mark, a blue leading claim and dark continuation. Attribution is small at left with a customer mark at right. Engineering patterns back the section.

**Transfer:** Give one verified result room to breathe. If no quotation is available, use an equally large independently supportable result statement.

**Text style:** `quotation` — Recursive 650 · 48px/1.1 · tracking -0.025em

### Story row

**Observed:** A centered display heading introduces three Story cards separated by 32px; a faint square drafting grid becomes more visible toward the lower field.

**Transfer:** Use three distinct outcomes, with comparable title length and a consistent reading action.

**Text style:** `case-title` — Recursive 400 · 28px/1.1 · tracking -0.025em

### FAQ column

**Observed:** A 44px heading with a blue final word sits above Questions. FAQ rows are separated by 32px and use rules rather than boxes. The visible question-only state is compact; answer text expands below.

**Transfer:** Use the objections that prevent implementation or purchase, with direct answers and useful links.

**Text style:** `faq-question` — Moranga 400 · 28px/1.1 · tracking -0.025em

### Pricing comparison

**Observed:** The pricing promise is a centered display heading with blue lead text, followed by a support line and small explanatory note. Chapter band leads into Pricing matrix; plan header remains visible while category bands and ruled rows scroll beneath. The ending is a quiet note and stacked product and documentation actions, not a second enormous sales pitch.

**Transfer:** Retain equal comparison columns and explicit units; adapt categories to actual buyer decisions.

**Text style:** `plan-name` — Moranga 400 · 30px/1.2

### Atmospheric closing invitation

**Observed:** Atmospheric stage returns with its wash vertically reversed. A centered display invitation, Primary button, then two underlined utility links form a spacious closing group in a roughly 774px band. Utility footer follows. The video-led variant closes with a serif invitation, support copy, three small ecosystem entry tiles and a documentation button. The dark variant closes with a two-line scale-oriented invitation and paired documentation/pricing actions.

**Transfer:** Echo the opening material while reducing the decision to one next action. Preserve a visually substantial closing even when the page's middle is brief.

**Text style:** `display` — Moranga 400 · 72px/1.1 · tracking -0.025em

### Utility ending

**Observed:** Utility footer is about 418px tall at desktop. An identity sits left of four small link columns; footer-heading is mint, or blue on dark infrastructure pages. Content starts after 64px top padding. A ruled row beneath holds social marks on the left, quiet legal text centrally and a green-dot status control on the right.

**Transfer:** Use a compact navigational finish after the invitation rather than extending the marketing narrative.

**Text style:** `footer-link` — Inter 400 · 14px/20px

## Page flow

**Storyline:** Identity and promise → category or compatibility reassurance → mechanisms and capabilities → credible outcomes → decision support → a focused invitation → compact utilities.

### Broad runtime adoption page

1. **Promise** — Dark light-streak opening, bold sans promise and highlighted capability list.
2. **Activation** — Copyable installation command and alternative assisted setup.
3. **Capability chapters** — Alternating code panels, tooling demonstration and standards narrative.
4. **Risk reduction** — Dark security chapter with a terminal demonstration and three layered explanations.
5. **Quantified proof** — Performance cards and benchmark bars with small methodological captions.
6. **Expansion and trust** — Related platform inset, new product capability, usage metrics and logo proof.
7. **Closing call** — Short invitation beside a warm illustrated vignette, then the shared charcoal footer.

**Transfer:** Use the bold runtime variant for a broad developer adoption story, bringing activation unusually early.

### Plan evaluation and comparison

1. **Promise** — Centered serif statement with blue opening phrase.
2. **Pricing** — Hatched chapter divider, sticky four-plan header and a common feature column.
3. **Decision detail** — Ruled matrix grouped by practical resource and support categories.
4. **Closing call** — Small usage caveat and stacked learn-more/documentation buttons, followed by the shared footer.

**Transfer:** Keep plan evaluation compact and persistent; spend space on meaningful comparison rather than decorative plan cards.

### Default flagship product landing page

1. **Identity** — Centered serif identity on a grained blue stage with one primary action.
2. **Reassurance** — Broad compatibility statement, ecosystem marks and capability chips.
3. **Capability chapters** — Alternating browser mechanisms and interface demonstrations, grouped by hatched signposts.
4. **Choice** — Architecture diagram beside a short explanation of operating options.
5. **Social proof** — Large metric and quotation, followed by three story cards.
6. **Closing call** — Blue atmosphere returns behind a serif invitation and stacked actions; compact charcoal utilities finish the page.

**Transfer:** Adapt the middle to a new product's mechanisms while retaining editorial headings, constructed media and the atmospheric bookends.

### Focused technical product introduction

1. **Promise and demonstration** — Compact serif promise beside a wide warm presenter video.
2. **Activation** — Short numbered getting-started steps with ecosystem entry tiles and interface examples.
3. **Definition** — Large editorial explanation followed by practical capability demonstrations.
4. **Capability chapters** — Code paired with diagrammatic network objects, then an outcome-oriented transition.
5. **Decision support** — Compact usage pricing and a narrow ruled FAQ column.
6. **Closing call** — Large serif invitation above ecosystem entry tiles and documentation action, then shared footer.

**Transfer:** Teach a new category with early setup, a plain-language definition and concrete objections before the final invitation.

### Infrastructure platform sales page

1. **Promise** — Dark geometric field under a left-aligned pale serif statement and paired actions.
2. **Category and trust** — Large definition with blue emphasis plus a small customer proof strip.
3. **Mechanisms** — Architecture, SDK entry tiles, interoperability and observability diagrams.
4. **Capabilities and comparison** — Three tall mechanical-emblem cards followed by a restrained ruled comparison.
5. **Social proof** — Three outcome story cards on a subtle drafting grid.
6. **Closing call** — Scale-oriented serif invitation, documentation and pricing actions, small follow-up links and the common footer.

**Transfer:** Use the dark variant consistently for an infrastructure narrative, keeping the same editorial proportions and physical blue controls.

## Writing

Confident technical usefulness with a friendly, lightly opinionated edge. Benefits are concrete and quickly followed by mechanisms, compatibility details or a practical next step.

**Do not copy:** Do not reuse Deno names, logos, mascot artwork, customer identities, quotations, performance figures, prices or product claims. Replace them with the new product's own verified assets and facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the makers when discussing work already done. Prefer active product verbs to impersonal abstractions.
- **Rhythm:** Headings are short sentence fragments, often with one emphasized phrase. Support is usually one or two plain sentences; paired clauses and semicolons create an occasional brisk contrast. Technical paragraphs can name real tools without explaining every term.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Promise | Name a practical improvement in compact, memorable language. | 3–8 words | “Better, faster JavaScript”<br>“The platform for platform builders” |
| Feature heading | Benefit plus a precise capability; often a small reversal of an old burden. | 4–9 words | “A data layer built for simplicity”<br>“Stop redeploying; start layering” |
| Support | Explain what the reader can do, then name the mechanism or removal of friction. | 1–2 sentences | “Seamlessly integrate with your production database, and get an isolated clone with every PR!”<br>“One binary, every platform. Drop [Brand] into your existing container, serverless function, or VM. No rewrites, no extra tooling.” |
| Primary action | Direct verb and a clear destination; documentation is a legitimate conversion. | 2–5 words | “Get started now”<br>“See pricing” |
| Chapter signpost | Brief conversational label bracketed by em dashes. | 2–4 words | “— What’s new —”<br>“— Compare [Brand] Deploy plans —” |
| Closing invitation | Simple readiness question or two concise promises joined by a period. | 5–12 words | “Ready to try the new [Brand] Deploy?”<br>“Get started for free. Scale to millions.” |

**Words and phrasing to use:** built for; out of the box; simple; first-class; your project; bring your existing; no extra tooling; get started; runs; manage; observe

**Avoid:** revolutionary ecosystem; unlock limitless possibilities; game-changing synergy; magical transformation; enterprise-grade everything

**Rules:**

- Lead with what changes for the reader, then show how it works.
- Use real compatibility names and units where they help a decision.
- Make a contrast specific: less setup, fewer moving parts or a clearer operational boundary.
- Keep blue-highlighted words meaningful when the heading is read without color.
- Keep explanatory captions factual and small; do not turn every caption into another slogan.

## Do's and Don'ts

### Do

- Keep major serif headings at 72px/1.1 and weight 400, with -0.025em tracking.
- Retain the 2px outline and 2px 4px hard shadow on blue conversion keys.
- Use 1280px rails and 56px desktop inner side insets to align unrelated sections.
- Alternate 2:3 feature splits with centered chapter headings instead of making every section a card grid.
- Give diagrams the same 8px browser corners and pale title-bar material as interface demonstrations.
- Use a restrained 16px dot field or fine diagonal hatch as the recurring technical texture.
- Let one 72px metric or 48px quotation carry proof at editorial scale.
- Finish with a spacious invitation and then the compact dark utility footer.

### Don't

- Do not use bold Inter as the default product display face; it belongs to the runtime variant.
- Do not turn physical-key actions into borderless 9999px pills on an ordinary product page.
- Do not saturate every section with sky blue; keep most of the long-form canvas #f1f3f9.
- Do not replace hard paper relief with heavy diffuse drop shadows or glass cards.
- Do not apply negative display tracking to body copy or small navigation labels.
- Do not enlarge utility chips into big uppercase section banners; their text is 14px sentence case.
- Do not reduce proof to many tiny numerical badges when one editorial-scale statement would be clearer.
- Do not substitute generic lifestyle stock photography for technical browser scenes and working diagrams.

## Motion and responsive

### Motion

**Observed:**

- Declared: primary and secondary color transitions use 0.15s cubic-bezier(.4,0,.2,1). Story borders use the same timing.
- Declared: repeated section entrances use fadeInSlideUp at 0.8s cubic-bezier(0.075,0.82,0.165,1); opening items also use a 0.75s slide-up with staggered delays.
- Declared: dark circular mechanisms pulse on a 4s cubic-bezier(0.86,0,0.07,1) loop. Runtime pill rims use paired 0.3s custom-property transitions.

**Transfer:**

- Limit controls to quick color or border changes so their physical silhouette remains stable.
- Use staged entrance of chip, identity, support and action rather than animating the whole opening as one panel.
- Keep the dark mechanism loop subtle; it should read as a working instrument, not a spinning loader.

**Unknown:**

- Full playback and scroll-linked progress behavior; reduced-motion behavior; keyboard focus styling beyond the provided declarations.

### Responsive

**Observed:**

- Declared width breakpoints include 384px, 440px, 640px, 768px, 1024px, 1080px, 1280px and 1536px.
- Feature-row classes switch between one column and split grids; row gaps progress through 32px, 64px and 128px. Story grids switch from stacked to three columns. Desktop navigation is replaced below its large-width mode.
- The desktop pricing matrix is hidden below the medium-width mode; its alternate narrow-screen presentation is not specified here.

**Transfer:**

- On narrow screens, preserve the centered identity and blue atmosphere while fitting its width to the available measure.
- Stack feature text and constructed media, keeping one explanatory mechanism per viewport-width panel and reducing the 128px gap through the smaller declared gap steps.
- Keep FAQ rules full-width within the narrow measure; do not shrink question text to make long questions stay on one line.

**Unknown:**

- Exact narrow-screen typography sizes, menu behavior, alternate pricing design and complete mobile page compositions.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
