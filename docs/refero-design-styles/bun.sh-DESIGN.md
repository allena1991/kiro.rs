# Bun — proof with punch

## Overview

A white, technically literate marketing style with compressed, heavyweight grotesk headlines, small monospaced annotations and flashes of hot pink. Ruled comparison graphics, executable examples and candid interview videos carry the argument rather than decorative hero art. The density alternates between spacious chapter introductions and compact grids, with a near-black typographic finale adding an emphatic change of register.

### Essentials

- Headlines feel packed rather than polished: Archivo 800 at 68px/0.92 with -0.02em tracking in the opening, 76px/0.92 for chapters, and selected words in pink or muted gray.
- The opening makes a claim and immediately puts it on trial: two nearly equal columns separated by 64px, a 515px text-and-command stack beside a 557px ruled demonstration, all inside a 1216px container with 40px inner gutters.
- Actions have a snipped corner, not a soft capsule: black 44px buttons with 20px side padding and a 9px top-right cut; command slabs are 60px tall with a 12px cut.
- Color behaves like a highlighter on a technical document: white dominates the long-form canvas, #e2e2e2 rules organize it, and #ff1f8f marks a few words, winning bars, prompts and interaction states rather than whole sections.
- Proof is a signature graphic: thin horizontal bars, black comparison marks, one pink result, monospace readings and explicit conditions. Include an inspectable comparison or working example even when the product has no interface imagery.
- A small comic interruption offsets the engineering: jagged, black-outlined claim stickers overlap the tops of otherwise square white capability cells; use original short labels and simple SVG shapes when no illustration is available.
- An emphatic dark typographic statement anchors the experience: #0d0a0c backing, Archivo 900 at 117px/0.86 with -0.01em tracking, off-white text and a pink concluding phrase, paired with a practical next step. This device need not determine the order of every page.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot pink | `#ff1f8f` | `--color-accent` | accent, action, text | Short headline emphasis, result bars, command prompts and hover/focus states. |
| Night pink | `#ff2e97` | `--color-night-accent` | accent, text, action | Dark-band concluding words and primary action. |
| Technical link pink | `#d60066` | `--color-api` | link, text | Monospaced API names in the capability directory. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main page and card backgrounds; reversed text on black controls. |
| Footer wash | `#fafafa` | `--color-footer` | background | Visible footer wash made with rgba(246,246,246,0.6) over white. |
| Code gray | `#f6f6f6` | `--color-subtle` | surface | Inline code, chart tracks and selected workflow backgrounds. |
| Off-white headline | `#eaeae8` | `--color-night-ink` | text | Headline text on the dark band. |
| Light rule | `#e2e2e2` | `--color-rule` | border | Card edges, section separators and table row divisions. |
| Night body | `#a8a8a5` | `--color-night-muted` | text | Dark-band supporting paragraph and inactive controls. |
| Annotation gray | `#707070` | `--color-faint` | text | Muted headline phrases, mono labels, conditions and metadata. |
| Body gray | `#525252` | `--color-muted` | text | Paragraphs, navigation and secondary series labels. |
| Night edge | `#3e3e42` | `--color-night-rule` | border | Dark-band top edge and subdued control outlines. |
| Dark rule | `#181818` | `--color-strong-rule` | border, accent | Opening demonstration frame, tab divisions and black comparison bars. |
| Command black | `#0c0c0c` | `--color-slab` | surface | Opening command slab and active demonstration tab. |
| Warm night | `#0d0a0c` | `--color-night` | background | Dark emphatic statement band. |
| Primary ink | `#0a0a0a` | `--color-ink` | text, action, background | Headings, primary actions and the narrow announcement strip. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Terminal backing | `#111114` | `--color-terminal` | surface | Terminal demonstration background. |

## Typography

- **Archivo** — Marketing headlines and large numeric proof. Narrow, dense grotesk with forceful heavy cuts and compact counters. Font stack: "Archivo", ui-sans-serif, system-ui, sans-serif.
- **ui-sans-serif** — Body prose, navigation, actions and card headings. Unembellished system sans, lighter and more open than the display face. Font stack: "ui-sans-serif", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.
- **Martian Mono** — Commands, technical labels, readings and code names. Distinctively broad technical monospace, generally small and regular or medium. Font stack: "Martian Mono", ui-monospace, SFMono-Regular, Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-display | Archivo | 900 | 117px | 0.86 | -0.01em | size clamp(3rem, min(9vw, 13vh), 7.5rem) | Monumental dark-band statement. |
| heading-lg | Archivo | 800 | 76px | 0.92 | -0.02em | size clamp(2.6rem, 6vw, 4.75rem) | Main chapter headings; often larger than the opening headline. |
| display | Archivo | 800 | 68px | 0.92 | -0.02em | size clamp(2.5rem, 5vw, 4.25rem) | Opening headline, usually broken into three to five tightly packed lines. |
| metric | Archivo | 800 | 44.8px | 0.92 | -0.02em | size clamp(2rem, 4vw, 2.8rem) | Oversized values in ruled stat cells. |
| heading-pair | Archivo | 800 | 43.2px | 1.04 | -0.02em | size clamp(1.9rem, 3.6vw, 2.7rem) | Compact introduction to a capability grid, with a gray second phrase. |
| story-heading | ui-sans-serif | 600 | 20.5px | 1.375 | -0.015em | fixed | Customer proof card headlines. |
| closing-body | ui-sans-serif | 400 | 19.2px | 1.5 | normal | fixed | Support text beside the dark-band statement. |
| intro | ui-sans-serif | 400 | 17.9px | 1.55 | normal | fixed | Opening support paragraph. |
| body | ui-sans-serif | 400 | 17.6px | 1.55 | normal | fixed | Chapter introductions, usually constrained to about 620px. |
| card-heading | ui-sans-serif | 600 | 16.8px | 1.5 | -0.02em | fixed | Compact capability cell titles. |
| button | ui-sans-serif | 600 | 15px | 1.5 | -0.005em | fixed | Standard 44px actions. |
| command | Martian Mono | 400 | 15px | 1.5 | -0.01em | fixed | Single-line copyable commands. |
| story-body | ui-sans-serif | 400 | 14.5px | 1.625 | normal | fixed | Customer proof and feature-card paragraphs. |
| navigation | ui-sans-serif | 500 | 14.5px | 1.5 | normal | fixed | Header navigation labels. |
| footer-link | ui-sans-serif | 400 | 14.5px | 1.5 | normal | fixed | Footer navigation. |
| card-body | ui-sans-serif | 400 | 13.5px | 1.625 | normal | fixed | Compact capability descriptions. |
| search | ui-sans-serif | 400 | 13.5px | 1.5 | normal | fixed | Header search prompt. |
| api-name | Martian Mono | 400 | 13.5px | 1.5 | normal | fixed | Linked technical names in a capability directory. |
| caption | ui-sans-serif | 400 | 13px | 1.375 | normal | fixed | Benchmark conditions and short explanatory annotations. |
| eyebrow | Martian Mono | 500 | 11px | 1.5 | 0.04em, uppercase | fixed | Chapter labels and compact category markings. |
| wide-label | Martian Mono | 500 | 11px | 1.5 | 0.14em, uppercase | fixed | Release metadata and footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| focused product landing pages | feature-heading | ui-sans-serif | 600 | 18.4px | 1.5 | -0.015em | fixed | Larger standalone feature-card titles. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the dramatic contrast between narrow heavy display text and ordinary system-sans prose; do not use the display family for paragraphs.
- Large headings use negative tracking and line heights below 1. Keep gray continuations at the same size and weight as the black phrase.
- Monospaced labels are small functional markings, not broad decorative subtitles. Use wider tracking only for release and footer metadata.

## Layout

**Density:** Airy chapter spacing surrounds dense ruled grids and compact technical annotations.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Footer link stacks, label/icon groups and compact controls. |
| 12px | Small control gaps and the gap after card support headings. |
| 16px | Eyebrow-to-heading and heading-to-support rhythm; benchmark grid gaps. |
| 20px | Stat cell padding and standalone feature-grid gaps. |
| 24px | Capability and story card padding; story grid gutters. |
| 40px | Container side gutters and capability-grid offset below its heading. |
| 48px | Footer columns, closing columns and wide introduction-to-proof gaps. |
| 56px | Hero top padding and story/feature grid offsets. |
| 64px | Major split-column gaps and footer vertical padding. |
| 112px | Default vertical padding on major chapter sections. |
| 128px | More spacious standalone feature chapter padding. |

### Containers and grids

- **container**: max width 1216px · side padding 40px. Centered outer container including side padding; usable desktop content width is 1136px.
- **opening split**: 2 columns · gap 64px. Text column and demonstration column in a 1:1.08 ratio, aligned near the top; the proof is lowered 64px relative to the column top.
- **workflow split**: 2 columns · gap 64px. Narrow text/step rail and wide terminal in a 0.8:1.2 ratio.
- **ruled capabilities**: 4 columns · gap 0px. Connected equal-width capability cells with shared rules.
- **proof grid**: 3 columns · gap 16px. Small benchmark cards; arrange additional scenarios into another row.
- **story grid**: 3 columns · gap 24px. Equal-width video proof cards.
- **directory grid**: 3 columns · gap 0px. Ruled category cells with several short technical links in each.
- **footer columns**: 5 columns · gap 48px. A 1.4fr brand introduction beside four equal link columns.

## Corner radius

| Element | Radius |
| --- | --- |
| ruled cards | 0px |
| inline code | 3px |
| demo panels | 4px |
| navigation hover and replay controls | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| terminal edge | `0px 0px 0px 1px rgba(255,255,255,0.06)` | Fine outer ring on the terminal demonstration; not a floating card shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Long-form marketing canvas.

**CSS:** `background: #ffffff; color: #0a0a0a`

**Observed:** Mostly uninterrupted white with full-width chapter boundaries.

**Transfer:** Let headings, rules and proof graphics carry the visual structure.

#### Ruled card · level 1

**Use:** Proof and feature grouping.

**CSS:** `background: #ffffff; border: 1px solid #e2e2e2; border-radius: 0px; box-shadow: none`

**Observed:** Square, flat cells; connected grids share edges, while story and benchmark cards have gutters.

**Transfer:** Treat cards like parts of a technical sheet, not raised dashboard tiles.

#### Subtle code backing

**Use:** Inline code, chart tracks and selected steps.

**CSS:** `background: #f6f6f6; border-radius: 3px`

**Observed:** Low-contrast inset planes within the white canvas.

**Transfer:** Reserve the pale gray for functional content and selection.

#### Terminal panel

**Use:** Working terminal demonstration.

**CSS:** `background: #111114; border: 1px solid rgba(0,0,0,0.8); border-radius: 4px; box-shadow: 0px 0px 0px 1px rgba(255,255,255,0.06); overflow: hidden`

**Observed:** A dark rectangular working surface, about 643px wide, with a narrow title strip and tiny status dots.

**Transfer:** Show real representative output instead of an ornamental code texture.

#### Dark statement band · level 0

**Use:** Emphatic typographic statement and conversion.

**CSS:** `background: #0d0a0c; color: #eaeae8; border-top: 1px solid #3e3e42`

**Observed:** A single broad dark interruption within a predominantly light experience.

**Transfer:** Keep the contrast concentrated, with pink words rather than gradients.

#### Footer wash · level 0

**Use:** Shared site ending.

**CSS:** `background: rgba(246,246,246,0.6); border-top: 1px solid #e2e2e2`

**Observed:** Pale, flat footer separated from the main content.

**Transfer:** Return to light utility after a dark statement.

## Components

### Site header

**Use:** Persistent navigation and utility access.

**CSS:** `background: #ffffff; border-bottom: 1px solid #e2e2e2; position: sticky; top: 0px; z-index: 40; height: 65px`

**Text style:** `navigation` — ui-sans-serif 500 · 14.5px/1.5

**Observed:** Brand mark and wordmark at left, four navigation links, a wide search control, small social icons and a compact cut-corner action. Inner content is 64px tall with 24px gaps.

**Transfer:** Use a compact original identity and a restrained set of destination links.

### Search control

**Use:** Documentation-oriented utility search.

**CSS:** `background: #ffffff; border: 1px solid #e2e2e2; height: 36px; max-width: 416px; padding: 0px 12px; display: flex; align-items: center; gap: 10px; color: #707070`

**Text style:** `search` — ui-sans-serif 400 · 13.5px/1.5

**Observed:** Magnifier at left, text in the middle and a small outlined slash key at right.

**States:** Declared: hover border-color #181818; focus-visible outline 2px solid #ff1f8f, outline-offset 2px, border-radius 4px.

### Primary button

**Use:** Main chapter action.

**CSS:** `background: #0a0a0a; color: #ffffff; height: 44px; padding: 0px 20px; display: inline-flex; align-items: center; justify-content: center; gap: 10px; border-radius: 0px; clip-path: polygon(0px 0px, calc(100% - 9px) 0px, 100% 9px, 100% 100%, 0px 100%)`

**Text style:** `button` — ui-sans-serif 600 · 15px/1.5 · tracking -0.005em

**Observed:** Short label followed by a right arrow. Compact navigation versions are 36px tall, with 14px side padding and a 7px cut. Secondary actions use an outlined version of the same geometry.

**States:** Declared: hover background-color #ff1f8f and color #ffffff; focus-visible outline 2px solid #ff1f8f, outline-offset 2px, border-radius 4px.

### Command slab

**Use:** A direct executable next step in the opening and conversion areas.

**CSS:** `background: #0c0c0c; color: #ffffff; height: 60px; display: flex; clip-path: polygon(0px 0px, calc(100% - 12px) 0px, 100% 12px, 100% 100%, 0px 100%)`

**Text style:** `command` — Martian Mono 400 · 15px/1.5 · tracking -0.01em

**Observed:** Pink prompt at left, horizontally scrollable single-line command, then a 32px-wide copy region separated by a translucent rule. Below are a small rectangular operating-system switch and a script-inspection link. Dark-band version uses a slightly lighter charcoal slab.

**Transfer:** For a non-command product, preserve the actionable readout format with an inspectable input, configuration or copyable starter.

### Capability cell

**Use:** Compact overview of related capabilities.

**CSS:** `background: #ffffff; border-right: 1px solid #e2e2e2; border-bottom: 1px solid #e2e2e2; padding: 24px; display: flex; flex-direction: column`

**Text style:** `card-heading` — ui-sans-serif 600 · 16.8px/1.5 · tracking -0.02em

**Observed:** Small outlined icon tile, title, muted mono replacement line, short description, and bottom-aligned pale command strip. A jagged claim sticker overlaps the upper-right edge.

**States:** Declared: hover background-color rgba(246,246,246,0.7); focus-visible outline 2px solid #ff1f8f, outline-offset 2px, border-radius 4px.

**Transfer:** Use parallel descriptions and comparable starter actions so the cells remain a system.

### Video proof card

**Use:** Human testimony linked to a specific capability.

**CSS:** `background: #ffffff; border: 1px solid #e2e2e2; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `story-heading` — ui-sans-serif 600 · 20.5px/1.375 · tracking -0.015em

**Observed:** A 16:9 interview poster above 24px-padded text. The poster includes a circular white play control and a dark lower-third with name and role. Below it: mono customer label, factual headline, story-body paragraph and a compact cut-corner action.

**Transfer:** Use testimony about one concrete workflow rather than generic praise.

### Benchmark panel

**Use:** Immediate quantified proof in the opening.

**CSS:** `background: #ffffff; border-right: 1px solid #181818; border-bottom: 1px solid #181818; border-left: 1px solid #181818`

**Text style:** `caption` — ui-sans-serif 400 · 13px/1.375

**Observed:** Four ruled tabs cap a horizontal bar comparison; active tab is black. A compact title and conditions precede the plot, a replay link sits at the top right, and a fine methodology footer closes it. Smaller repeated proof cards omit tabs and use the lighter Ruled card frame.

**Transfer:** Choose one defensible result, show comparison conditions and expose methodology instead of presenting an unexplained hero number.

### Technical directory row

**Use:** Browsable capability names with short descriptions.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 12px; padding: 8px; border-radius: 3px`

**Text style:** `api-name` — Martian Mono 400 · 13.5px/1.5

**Observed:** Pink monospaced name above a muted small sans description; a small arrow can sit at the far right. Rows are grouped beneath uppercase mono category labels.

**States:** Declared: hover background-color #f6f6f6; focus-visible outline 2px solid #ff1f8f, outline-offset 2px, border-radius 4px.

### Footer link

**Use:** Low-key navigation at the site ending.

**CSS:** `color: #525252; display: block; width: fit-content`

**Text style:** `footer-link` — ui-sans-serif 400 · 14.5px/1.5

**Observed:** Links stack at 10px gaps under widely tracked mono labels. The brand column carries a short description and four small social icons; a bottom rule separates the fine-print row.

**States:** Declared: hover color #0a0a0a; focus-visible outline 2px solid #ff1f8f, outline-offset 2px, border-radius 4px.

## Imagery and graphics

### Ruled performance graphics

**Use:** Signature proof imagery in the opening and supporting chapters.

**Observed:** Horizontal bar plots on white or very pale gray tracks. Comparators are near-black, the featured result pink, with mono measurements at the ends. Compact conditions, axis ticks and methodology text make the graphic feel reproducible. Tiny friendly identity markers add humor without becoming the main visual.

**Transfer:** Render original comparisons as HTML or SVG. If numbers are unavailable, show a real step-by-step working trace with comparable technical clarity, not invented statistics.

**Build:** Use a square 1px ruled frame; stack labeled horizontal tracks with 10–16px vertical gaps. Draw comparator rectangles in #181818 and a featured rectangle in #ff1f8f, scaled to a shared axis. Align mono readings at right; put units and conditions above, source/method link below. Keep all surrounding space white.

### Jagged claim stickers

**Use:** Playful punctuation on otherwise austere capability grids.

**Observed:** Small starburst badges overlap cell tops, each with a black outline, slight rotation and two compact lines of uppercase copy. The set uses pink, pale blue, bright green and pale yellow fills; their footprint is roughly 77px square.

**Transfer:** Use original short outcome labels in a small coordinated set. Keep the minimum version a flat, outlined SVG starburst with type; no illustration is needed.

**Build:** Draw an SVG starburst with alternating outer and inner radii, about 16 teeth, centered in a roughly 77px square. Use a thin black outline, flat pastel fill, compact centered uppercase text and a slight rotation around 6deg. Place partly above the card edge and add only a tiny dark offset shadow.

### Candid interview posters

**Use:** Customer and practitioner proof.

**Observed:** Seated speakers in domestic or studio interiors, framed at medium distance with natural light, plants, furniture and muted earthy colors. Landscape posters fill the card width; one extended story uses a tall portrait beside text and code. Black translucent lower-thirds hold white speaker attribution.

**Transfer:** Prefer real practitioners in lived-in work spaces, with subdued color and consistent framing. If video is unavailable, use a still portrait with a factual attribution rather than a nonfunctional play control.

### Working product demonstrations

**Use:** Capability explanations and workflow chapters.

**Observed:** Terminal output, syntax-highlighted code and a split editor/browser example are shown as working rectangular panels. They occupy roughly half or more of a split section, with plain light or dark backing and minimal 4px rounding; no perspective mockups or atmospheric backgrounds.

**Transfer:** Show a short realistic task with legible input and output. A static annotated panel is the minimum equivalent when live media is unavailable.

### Icons

**Observed:** Mostly 14px and 16px outline SVGs with 1.8px strokes and square caps; 20px capability icons use a 1.6px rounded stroke inside 40px outlined tiles. Arrows, checkmarks, copy symbols and tiny status dots are functional rather than decorative.

**Transfer:** Choose a consistent sparse outline set. Keep navigation and action symbols small and inline; use the pink accent for status and emphasis rather than multicolor icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Claim beside inspectable proof

**Observed:** A 38px black announcement strip sits above the 65px white Site header. The opening fills most of the remaining first screen with a two-column composition inside the container: a narrow release label, tightly stacked display headline and muted intro on the left; Benchmark panel on the right, lowered slightly to align with the headline. The headline spans roughly half the content width and about three lines, inserting a pink benefit word and gray conjunction into otherwise black text. A version label, Command slab, platform controls and an underlined quickstart link complete the left stack. Layers are white canvas, faint vertical registration rules, black text and frames, then small pink highlights. Within 900px, all of that plus a 101px ruled customer-logo strip is visible; capability cards begin below the fold.

**Transfer:** Pair a concise category statement with one working comparison, inspectable output or short product trace at the same scale. Without interface media, construct Ruled performance graphics. Focused product pages open with a mono category label and pink product/command line above a longer display claim, retain the split proof panel and command slab, and use paired documentation/migration actions.

**Avoid:** Do not replace the measured proof with a giant decorative mascot, centered slogan or abstract gradient. Do not stretch the headline across both columns or bury the usable next step below the fold.

**Text style:** `display` — Archivo 800 · 68px/0.92 · tracking -0.02em

### Two-tone heading into connected cells

**Observed:** A heading-pair introduction uses a black proposition and equally heavy gray continuation. A small explanatory line can align at the right. After 40px, Capability cells share a zero-gap four-column ruled frame with overlapping Jagged claim stickers.

**Transfer:** Group related functions under one compact promise; each cell should carry a distinct outcome and a concrete starter.

**Text style:** `heading-pair` — Archivo 800 · 43.2px/1.04 · tracking -0.02em

### Working workflow chapter

**Observed:** A 112px-padded ruled section pairs a narrow text and numbered-step rail with Terminal panel across a 64px gap. Eyebrow, heading-lg and support text lead into short steps; the active step has pale backing and a thin pink progress line. Tiny replay and arrow controls sit beneath the output.

**Transfer:** Demonstrate a small complete task. Explain what changes at each step, and show actual output in the wide panel.

**Text style:** `heading-lg` — Archivo 800 · 76px/0.92 · tracking -0.02em

### Release and stat ledger

**Observed:** A large left headline and release paragraph face a compact 2×2 stat grid. Each ruled stat cell combines a tracked mono label, metric value and a small explanatory line. A compact list of linked changes follows the grid, while a cut-corner action sits below the prose.

**Transfer:** Use for a launch, major improvement or measured result. Distinguish large measured values from the smaller explanation of what was tested.

**Text style:** `metric` — Archivo 800 · 44.8px/0.92 · tracking -0.02em

### Human proof chapter

**Observed:** A left-aligned eyebrow, heading-lg and body introduction precede a three-column Video proof card grid after 56px. A wider follow-up story pairs a tall interview portrait with capability explanation and a code example.

**Transfer:** Tie each story to a concrete use, then offer the relevant capability link rather than only a customer quote.

**Text style:** `story-heading` — ui-sans-serif 600 · 20.5px/1.375 · tracking -0.015em

### Scenario comparison chapter

**Observed:** A large heading and support paragraph lead into a 3×2 proof grid at 16px gaps. Each card describes one scenario and compares the same competitors on a shared metric. Methodology and a reproduction link sit beneath. A related chapter uses three connected memory comparison cells and a black/gray heading pair.

**Transfer:** Organize proof by situations readers recognize. Keep comparison conditions visible and distinguish each scenario without inventing a new card style.

**Text style:** `heading-lg` — Archivo 800 · 76px/0.92 · tracking -0.02em

### Capability explorer and directory

**Observed:** An eyebrow and heading-lg introduce a two-column explorer: a 300px vertical tab rail with small status dots beside a wider pale code panel and documentation link. A compact follow-up heading introduces a 3×2 connected directory grid of Technical directory rows.

**Transfer:** Combine one understandable worked example with a browsable index; do not force all details into the lead paragraph.

**Text style:** `heading-lg` — Archivo 800 · 76px/0.92 · tracking -0.02em

### Compatibility ledger

**Observed:** A heading-lg sits above a full-width lightly bordered table with 4px corners. The wide left column holds linked features and short descriptions; narrow competitor columns carry small circular yes/partial/no symbols in pale green, amber and neutral washes. Group headers are pale gray with tracked mono labels. A ruled white reveal area closes the shortened table with a small pill control.

**Transfer:** Use only when there is a meaningful comparable set of capabilities. Preserve text labels for the symbols and provide a way to inspect the full comparison.

**Text style:** `heading-lg` — Archivo 800 · 76px/0.92 · tracking -0.02em

### Dark practical invitation

**Observed:** Dark statement band uses an approximately 1.25:1 split with 48px gap. The left is a four-line closing-display statement, off-white with its final phrase pink. Right-aligned to its lower portion are closing-body text, Command slab, platform controls and two 52px cut-corner actions with 24px side padding and 11px cuts. The primary action is pink; the secondary is dark with a fine off-white outline.

**Transfer:** End a broad marketing story with a direct, low-risk invitation tied to the reader's existing work. Preserve the monumental text device and practical action, even when the product's next step is not installation.

**Text style:** `closing-display` — Archivo 900 · 117px/0.86 · tracking -0.01em

### Shared utility ending

**Observed:** Footer wash spans 378px at desktop. A 64px-padded grid places a brand description/social group next to four link columns with 48px gaps; wide-label headings precede Footer links. A lower hairline separates small copyright and location text. Focused product pages can finish with a centered heading, a 3×2 standalone feature grid at 20px gaps and a row of underlined related links directly before this footer.

**Transfer:** Keep the ending useful and low-key. A shorter product page can resolve objections through feature cards and related resources instead of repeating a full conversion band.

**Text style:** `footer-link` — ui-sans-serif 400 · 14.5px/1.5

## Page flow

**Storyline:** category promise → inspectable product proof → capabilities and real workflows → human or quantified validation → objection handling → practical next step and utility links

### Broad product marketing with several entry points

1. **Promise and immediate proof** — Split headline/command opening beside a tabbed benchmark, followed by a monochrome customer-logo strip.
2. **Capability overview** — Connected capability cells with playful stickers and compact command starters.
3. **Product demonstration** — A numbered workflow with real terminal output.
4. **Current momentum** — Release story and a small stat ledger.
5. **Social proof** — Interview cards and a larger practitioner story.
6. **Quantified proof** — Scenario comparison cards and a related resource-usage chapter.
7. **Capability depth** — Interactive example rail, categorized directory and a split editor/browser demonstration.
8. **Objection handling** — A linked compatibility table with an expandable set of rows.
9. **Closing call** — Dark monumental invitation, actionable command and paired actions, then a light multi-column footer.

**Transfer:** Use a broad story when the product needs several kinds of proof; adapt the number and order of chapters to the argument rather than repeating every block.

### Focused product landing with stronger scenario detail

1. **Promise and immediate proof** — Category label, pink technical name, narrow stacked headline, command and paired actions beside a benchmark.
2. **Capability assurance** — Three compact columns of checked links explain compatibility and familiar workflows.
3. **Quantified proof** — A six-scenario comparison grid with conditions, methodology and reproduction link.
4. **Objection handling** — Centered large heading above six square feature cards.
5. **Resource handoff** — Underlined related-topic links lead straight into the shared light footer.

**Transfer:** For a single capability, shorten the story, give its scenarios more room, and close with practical resources rather than duplicating every broad-marketing chapter.

## Writing

Direct, technically specific and confidently conversational. Speed and convenience are argued through real workflows, compatibility details and inspectable measurements, with small flashes of dry friendliness.

**Do not copy:** Do not reuse Bun's name, mascot, logos, customer identities, interview quotations, benchmark numbers, performance claims, release versions or proprietary product facts. Replace them with truthful equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your when reducing adoption anxiety. Name the product plainly when explaining behavior; use commands and API names literally where they help.
- **Rhythm:** Short declarative headlines alternate with denser explanatory paragraphs. Sentences often contrast a practical benefit against an expected trade-off; labels and actions stay terse, while methodology can be precise and compact.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | State the category clearly, then land the benefit in a short emphatic phrase. | 8–16 words | “[Brand] is a JavaScript runtime toolkit. All in one.”<br>“The npm-compatible package manager that finishes first.” |
| Chapter headline | Use a concrete promise or compact contrast rather than an abstract slogan. | 4–12 words | “One binary for the whole workflow.”<br>“Everything built in. Nothing weighing it down.” |
| Supporting line | Explain what stays familiar and what becomes easier; name the mechanisms. | 20–50 words | “Install, develop, run, test and ship with the same tool. Every step below is a real command with real output.” |
| Action | Name the destination or the actual operation. | 2–5 words | “Read the release notes”<br>“Migrate from npm” |
| Proof annotation | Name the conditions and explain how to interpret the metric. | A short line plus a separate detailed methodology note | “warm cache · seconds (lower is better)” |
| Closing invitation | Make the next step feel immediate and compatible with work already underway. | 8–14 words | “Try it on the repo you have open right now.” |

**Words and phrasing to use:** as-is; built in; single; real output; your project; works with; keep shipping; reproduce; measured; no configuration

**Avoid:** revolutionary; game-changing; unleash; magical platform; seamless synergy; limitless possibilities

**Rules:**

- Pair strong comparative language with conditions and an inspectable method.
- Prefer a literal example, command or named workflow over a broad adjective.
- Reduce switching anxiety by saying what the reader keeps, not only what they gain.
- Use a little playful language around a factual core; the technical explanation should remain unambiguous.

## Do's and Don'ts

### Do

- Keep the default chapter rhythm at 112px vertical padding, with fine full-width boundaries.
- Preserve 64px gaps in major split sections and 40px container gutters.
- Use shared 1px rules and 0px gaps for connected capability and directory grids.
- Set command readouts at 15px in Martian Mono and keep their 60px slab intact.
- Use the 44.8px heavy display recipe for stat cells rather than inflating every chart reading.
- Keep a 16px eyebrow/heading/support rhythm within chapter introductions.
- Use the pale footer with 64px vertical padding to return the experience to utility.
- Concentrate pink on a result, a phrase or an action, so white remains the dominant field.

### Don't

- Do not apply 16px or 24px radii to the square ruled cards.
- Do not make standard primary actions pill-shaped; preserve the 9px cut.
- Do not add diffuse floating shadows to proof cards; their hierarchy comes from rules.
- Do not set prose in Archivo 800 or Martian Mono; reserve those voices for display and technical markings.
- Do not replace the gray half of a heading pair with a smaller subtitle.
- Do not turn the whole page dark to imitate the single emphatic statement band.
- Do not use photographic backgrounds behind the main headline; human imagery belongs in framed proof.
- Do not hide measurement conditions inside an inaccessible tooltip when a 13px caption can carry them.

## Motion and responsive

### Motion

**Observed:**

- Declared: common color, background, border and decoration transitions use 0.15s cubic-bezier(.22,1,.36,1).
- Declared: the opening proof panel changes height over 0.38s cubic-bezier(0.2,0.9,0.25,1).
- Working demonstrations expose replay controls and describe hover-to-pause behavior; the header remains sticky through the page.

**Transfer:**

- Keep interaction emphasis local: pink hover, a small arrow shift, progress line or changing readout rather than moving whole marketing sections.
- Provide pause and replay affordances when showing the same kind of terminal or benchmark sequence.

**Unknown:**

- Exact demonstration cycle duration, scroll-reveal timing and whether every declared animation runs.

### Responsive

**Observed:**

- Declared width breakpoints include 580px, 640px, 767px, 768px, 1024px, 1280px and 1536px.
- Display and chapter type use clamped viewport-relative sizing. Capability and story rows declare horizontal snapping at narrow widths before becoming desktop grids.
- Desktop navigation/search are hidden below their medium layout; the wide terminal presentation is limited to the large layout.

**Transfer:**

- Keep horizontal snap rows for capability or story cards rather than squeezing four columns into narrow widths.
- Stack the claim and proof for smaller layouts while retaining their reading order and direct next step.
- Preserve readable single-line command scrolling instead of wrapping the slab into a paragraph.

**Unknown:**

- Complete mobile navigation construction, exact narrow gutter values and all intermediate layout behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
