# Nimble — routed lines, floating windows

## Overview

A bright, native-software aesthetic with fine multicolored routes threading around charcoal grotesk headlines. White and near-white expanses carry blue actions, hairline feature matrices and softly floating interface windows rather than photography. The feeling is capable and pleasantly lightweight, suited to focused productivity tools and technical products with a tangible workflow to demonstrate.

### Essentials

- Headlines feel like compact interface promises: Inter at 64px/1.04, weight 560, -0.04em tracking for the opening; 48px section headings retain the same moderate weight rather than becoming bold banners.
- The opening pairs a centered two-line promise with a floating working window: a 510px headline measure, about 671px support measure and a 1056px-wide interface that enters the first 900px but extends below the fold.
- Fine routed lines are a signature, not background noise: multicolored right-angle paths with softened bends and round endpoint dots surround the opening, then gather into a narrow left-margin rail. Use an abstract process map when the product has no branching metaphor.
- Actions look like native squircle controls, not ordinary capsules: 48px height, 24px horizontal padding, 12px between primary blue and secondary white controls; match the gently flattened corners.
- Color is concentrated in actions, small outline icons, routed lines and the product itself; the overwhelming majority of the page remains #ffffff or #fafafa with #282a2f headings and #5a5e66 support.
- Interface demonstrations float while feature lists stay flat: 24px-radius windows use a two-layer 40px/90px and 12px/28px shadow; feature cells instead share 1px hairline gutters with no rounding or elevation.
- A faint blue-lit closing panel anchors the ending: a 1120px-wide, 24px-radius outlined surface with centered 48px headline, paired actions and a restrained top-center radial wash, followed by a separate near-white directory footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#005bff` | `--color-blue` | action, accent, link | sRGB equivalent for the vivid display-P3 blue used by actions, feature icons and identity accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pressed blue | `#0049cc` | `--color-blue-hover` | action | Primary action hover fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#282a2f` | `--color-ink` | text | Headings, primary body text and secondary-button labels. |
| Support gray | `#5a5e66` | `--color-muted` | text, link | Supporting paragraphs, card descriptions and navigation. |
| Metadata gray | `#8a8d94` | `--color-faint` | text | Compatibility notes and directory labels. |
| Window edge | `#e0e0e0` | `--color-edge` | border | Visible result of black at 12% on white; window and purchase-panel edges. |
| Soft rule | `#ebebeb` | `--color-rule` | border | Visible result of black at 8% on white; grid gutters and section separators. |
| Control track | `#f2f3f5` | `--color-switch` | surface | Appearance-switch track. |
| Near-white band | `#fafafa` | `--color-band` | background, surface | Alternating sections, footer and closing-panel base. |
| Window porcelain | `#fbfbfc` | `--color-window` | surface | Primary interface-window backing. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, flat cells and inverse action text. |

## Typography

- **Inter** — All marketing headings, paragraphs, actions and navigation. Neutral grotesk with a tall x-height; intermediate variable weights keep headings and controls firm but not heavy. Font stack: "Inter", -apple-system, system-ui, "Segoe UI", Roboto, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 560 | 64px | 1.04 | -0.04em | Main marketing promise. |
| heading | Inter | 560 | 48px | 1.08 | -0.03em | Centered section headings and compact directory-page opening. |
| heading-split | Inter | 560 | 48px | 1.06 | -0.035em | Split-section headings and the main closing statement. |
| stat-word | Inter | 560 | 24px | 1.6 | -0.02em | Short qualitative performance labels. |
| cell-title | Inter | 540 | 20px | 1.6 | -0.01em | Feature titles and FAQ questions. |
| lede | Inter | 400 | 19px | 1.55 | normal | Opening and section support paragraphs. |
| action | Inter | 540 | 16px | 1 | normal | Main conversion controls. |
| small | Inter | 400 | 14px | 1.6 | normal | Feature descriptions, footer links and compatibility microcopy. |
| navigation | Inter | 460 | 14px | 1.6 | normal | Header links. |
| action-small | Inter | 540 | 14px | 1 | normal | Compact header conversion control. |
| directory-label | Inter | 540 | 13px | 1.6 | 0.04em, uppercase | Footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| purchase sections | price | Inter | 560 | 48px | 1.6 | -0.03em | Price amount with baseline-aligned qualifier. |

**Notes:**

- Large text tightens from -0.01em on feature titles to -0.04em on the main promise; body and controls retain normal tracking.
- Use sentence case and terminal punctuation in major promises. The only systematic uppercase treatment is the small footer directory label.
- Use the centered heading recipe for introductory overview sections; the slightly tighter heading-split recipe belongs to alternating text/media chapters and the main closing line.

## Layout

**Density:** Airy marketing sections surround compact, credible interface demonstrations; lists inside the demonstrations are much denser than the surrounding page.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Feature-title to description gap and icon-to-control-label gap. | fixed |
| 12px | Paired-action gap and compact stacks; declared --space-3. | fixed |
| 16px | Feature icon to title and compact closing support gap; declared --space-4. | fixed |
| 20px | Section-heading support gap, FAQ vertical padding and microcopy separation. | fixed |
| 24px | Standard feature-cell padding and opening headline-to-support gap; declared --space-6. | fixed |
| 32px | Support-to-action separation and purchase-card padding; declared --space-8. | fixed |
| 40px | Footer bottom padding; declared --space-10. | fixed |
| 48px | Centered section-header separation before demonstration content. | fixed |
| 64px | Footer main-column gap and separation before copyright rule. | fixed |
| 80px | Split-section column gap. | clamp(32px, 6vw, 80px) |
| 96px | Closing-panel vertical padding. | clamp(48px,8vw,96px) |
| 108px | Standard major-section vertical padding. | fixed |

### Containers and grids

- **content**: max width 1120px. Centered primary content; leaves 160px on either side at a 1440px viewport.
- **wide**: max width 1320px. Navigation and expansive demonstration stages; leaves 60px desktop side margins.
- **prose**: max width 680px. Centered FAQ reading column.
- **section-support**: max width 646px. Typical centered support-paragraph measure; opening support expands to about 671px.
- **split**: 2 columns · gap 80px. Equal 520px text and media columns in the main content width; alternate which side holds the interface.
- **proof-grid**: 4 columns · gap 1px. Shared-rule feature strip, roughly 279px per cell.
- **catalog-grid** (only for feature directory pages): 3 columns · gap 1px. Long capability directory with roughly 373px-wide cells.

## Corner radius

| Element | Radius |
| --- | --- |
| windows-and-panels | 24px |
| action-visible-corners | 12px |
| appearance-track | 9999px (pill) |
| appearance-thumb | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating-window | `0px 40px 90px 0px rgba(16, 22, 38, 0.16), 0px 12px 28px 0px rgba(16, 22, 38, 0.08)` | Main interface window and smaller command or integration demonstrations. |
| purchase sections | purchase-card | `0px 24px 60px 0px rgba(16, 22, 38, 0.12), 0px 6px 16px 0px rgba(16, 22, 38, 0.06)` | Single raised purchase card. |

### Surfaces

#### Canvas · level 0

**Use:** Main page background.

**CSS:** `background: #ffffff; color: #282a2f`

#### Band · level 0

**Use:** Alternating chapter backgrounds and footer.

**CSS:** `background: #fafafa`

**Observed:** Full-width low-contrast changes separate chapters without thick rules.

**Transfer:** Use the band to organize several types of proof, not as a colored promotional banner.

#### Floating window · level 2

**Use:** Large product demonstrations.

**CSS:** `background: #fbfbfc; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 24px; box-shadow: 0px 40px 90px 0px rgba(16, 22, 38, 0.16), 0px 12px 28px 0px rgba(16, 22, 38, 0.08); overflow: hidden`

**Observed:** The main window is solid porcelain. Smaller overlays use white at 96% with 24px backdrop blur, or porcelain at 78% with blur(20px) saturate(1.1); the same outline and elevation connect them.

**Transfer:** Use the solid version for the main product and translucent material only for genuinely floating utility panels.

#### Shared-rule matrix · level 0

**Use:** Flat feature and assurance collections.

**CSS:** `display: grid; gap: 1px; background: rgba(0, 0, 0, 0.08); border-top: 0.5px solid rgba(0, 0, 0, 0.08); border-bottom: 0.5px solid rgba(0, 0, 0, 0.08)`

**Observed:** White cell faces leave only thin shared gutters visible; there are no individual rounded cards.

**Transfer:** Let the amount of content determine row height.

#### Blue-lit closing panel · level 1

**Use:** Final conversion invitation.

**CSS:** `background-color: #fafafa; background-image: radial-gradient(120% 140% at 50% 0%, rgba(0, 91, 255, 0.08), rgba(0, 0, 0, 0) 55%); border: 1px solid rgba(0, 0, 0, 0.08); border-radius: 24px`

**Observed:** A barely blue top-center wash fades into near-white; the panel has no floating-window shadow.

**Transfer:** Keep the blue wash gentle enough that black text and solid-blue buttons carry the emphasis.

## Components

### Sticky navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; height: 60px; z-index: 100; display: flex; align-items: center; background: rgba(255, 255, 255, 0.434); backdrop-filter: saturate(1.44469) blur(8.9px); box-shadow: 0px 0.6px 0px 0px rgba(0, 0, 0, 0.043)`

**Text style:** `navigation` — Inter 460 · 14px/1.6

**Observed:** Brand sits left, text navigation toward the right, then an appearance switch and compact blue action. The inner row uses the wide container; it remains visible while scrolling.

**Transfer:** Retain the sparse row and compact action rather than making a large navigation bar.

### Primary button

**Use:** Main trial or purchase action.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 8px; height: 48px; padding: 0px 24px; background: #005bff; color: #ffffff; border-radius: 12px`

**Text style:** `action` — Inter 540 · 16px/1

**Observed:** Visible geometry is a smooth squircle with long straight edges. A download icon precedes the opening label, while the final pair can omit icons. The header variant is 38px high with 16px side padding and action-small typography.

**States:** Declared: hover background #0049cc and 0 16px 40px blue shadow at 24%; focus-visible outline none and 3px blue ring at 55% with 12px radius; active white text at 60% opacity.

**Transfer:** Use a squircle mask if available; the 12px rounded rectangle is the minimum visual fallback.

### Secondary button

**Use:** Alternative conversion alongside the primary action.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 48px; padding: 0px 24px; background: #ffffff; color: #282a2f; border-radius: 12px; box-shadow: 0px 0px 0px 1px rgba(0, 0, 0, 0.12) inset`

**Text style:** `action` — Inter 540 · 16px/1

**Observed:** Same squircle silhouette and height as the primary, placed 12px away; the purchase-card version stretches to full available width.

**States:** Declared: hover background #fafafa with inset 1px outline using metadata gray at 45%; focus-visible outline none and 3px blue ring at 55%, radius 12px; active charcoal text at 55% opacity.

### Navigation link

**Use:** Short header destinations.

**CSS:** `padding: 8px 12px; border-radius: 12px; color: #5a5e66`

**Text style:** `navigation` — Inter 460 · 14px/1.6

**Observed:** Current destination changes to charcoal; neighboring links are separated by 8px.

**States:** Declared: hover color #282a2f and background rgba(0, 0, 0, .04); focus-visible outline none and 3px blue ring at 55%, radius 12px.

### Feature cell

**Use:** Assurance strip and capability directory.

**CSS:** `background: #ffffff; padding: 24px; border-radius: 0px; box-shadow: none`

**Text style:** `cell-title` — Inter 540 · 20px/1.6 · tracking -0.01em

**Observed:** Blue outline icon, then title, then small gray description. Icon-to-title spacing is 16px, title-to-description is 8px. Outer edge cells align their text to the content boundary by dropping the corresponding outer padding.

**Transfer:** Use four cells for a compact proof strip and three columns for a directory; keep descriptions concrete.

### Word stat

**Use:** Qualitative performance proof without oversized invented metrics.

**CSS:** `padding: 24px; display: flex; flex-direction: column; gap: 4px; border-right: 0.5px solid rgba(0, 0, 0, 0.08); border-bottom: 0.5px solid rgba(0, 0, 0, 0.08)`

**Text style:** `stat-word` — Inter 560 · 24px/1.6 · tracking -0.02em

**Observed:** A two-by-two flat matrix uses a small blue icon above a short word and a small gray qualifier. Cells are about 260px by 153px, not giant numerical billboards.

**Transfer:** Use truthful compact performance qualities with one clarifying line.

### FAQ row

**Use:** Practical objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; padding: 20px 0px`

**Text style:** `cell-title` — Inter 540 · 20px/1.6 · tracking -0.01em

**Observed:** Question at left and a small muted chevron at right sit in a 680px-wide native details list. Each enclosing row has a 1px soft bottom rule. Answers use regular 16px/1.65 gray text.

**States:** Declared: focus-visible outline none and 3px blue ring at 55%, radius 12px.

### Closing invitation

**Use:** Final call to act.

**CSS:** `display: flex; flex-direction: column; align-items: center; padding: 96px 24px; text-align: center`

**Text style:** `heading-split` — Inter 560 · 48px/1.06 · tracking -0.035em

**Observed:** Uses Blue-lit closing panel: heading, support after 16px, paired actions after 32px and optional compatibility line after 20px. A compact directory-page version uses 72px vertical padding and heading typography.

### Footer directory

**Use:** Site ending and secondary navigation.

**CSS:** `background: #fafafa; border-top: 1px solid rgba(0, 0, 0, 0.08); padding: 80px 0px 40px`

**Text style:** `directory-label` — Inter 540 · 13px/1.6 · tracking 0.04em · uppercase

**Observed:** Within the content container, a brand/description column sits left of three visible navigation columns. Group labels are uppercase gray; links use small text. A separate copyright area follows a top rule, 64px top margin and 32px top padding.

**Transfer:** Preserve the short brand description, sparse groups and distinct low-emphasis bottom row.

### Appearance switch

**Use:** Compact header appearance control.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; align-items: center; width: 64px; height: 32px; background: #f2f3f5; border-radius: 9999px`

**Observed:** Sun and moon icons share the track; the selected light side has a 26px white circular thumb inset by 3px.

**States:** Declared: hover blends track 88% with metadata gray; focus-visible outline none, no shadow, radius 12px and track mixed 82% with blue.

### Purchase card

**Only for:** purchase sections

**Use:** Single-offer conversion panel.

**CSS:** `width: 380px; padding: 32px; background: #ffffff; border: 0.5px solid rgba(0, 0, 0, 0.12); border-radius: 24px; box-shadow: 0px 24px 60px 0px rgba(16, 22, 38, 0.12), 0px 6px 16px 0px rgba(16, 22, 38, 0.06)`

**Text style:** `price` — Inter 560 · 48px/1.6 · tracking -0.03em

**Observed:** Amount and one-time qualifier share a baseline; terms follow, then stacked full-width primary and secondary actions, a guarantee with a check and tiny checkout reassurance.

**Transfer:** Keep one clear offer when the product has one; do not turn this into a many-tier comparison by default.

## Imagery and graphics

### Routed process lines

**Use:** Signature opening artwork and left-margin chapter rail.

**Observed:** Thin blue, teal, green, purple, magenta, amber and charcoal paths enter from page edges, turn through rounded right angles, terminate in solid round nodes and pass behind the copy/actions. Below the opening they collect into closely spaced vertical lines at the far left. They are crisp and flat, without glow or texture.

**Transfer:** Make the same routed network express the new product's connections or steps. Even without product media, keep the routed motif and pair it with a simplified working-state panel.

**Build:** Use an absolute SVG behind the content. Draw orthogonal paths with quadratic rounded bends of about 20px, about 2px stroke, no fill, and 5px-radius endpoint circles separated from the stroke by a white halo. Use blue plus restrained green, teal, purple, pink and amber strokes via rgba colors. Route paths around a clear central text area, merge several toward the action band and gather 4–6 paths into a narrow left rail below. Keep text and windows on opaque foreground layers.

### Working interface stages

**Use:** Main product proof and focused workflow chapters.

**Observed:** The main view is a broad desktop application window with three-pane navigation, file list and content area. Later scenes isolate a command palette, a compact commit window and service/issue panels. All face front without perspective; pale native chrome, fine separators and soft gray shadows make the interface feel usable rather than cinematic.

**Transfer:** Show a believable working state for the new product at similar scale. If there is no finished interface, create a simple two- or three-pane workflow with real labels and one meaningful selected state; do not substitute unrelated photography.

### Floating integration tiles

**Use:** Small peripheral accents around integration demonstrations.

**Observed:** Dark, blue, green or warm square app tiles tilt slightly and tuck partly behind the main pale window. Larger tiles are about 95px with 18px corners; smaller integration tiles are about 72px with 15px corners. They occupy far less area than the interface and copy.

**Transfer:** Use relevant product-tool symbols, or original simple glyphs, on restrained colored tiles; keep the interface as the focal object.

**Build:** Create 72px square tiles with 15px corners, centered monochrome 36px glyphs, a faint inset edge and the purchase-card shadow. Place two near opposite panel edges, rotate slightly in opposing directions and partially occlude them behind the panel. Use 95px tiles with 18px corners for a larger centered demonstration.

### Icons

**Observed:** Marketing feature icons are predominantly blue 26px SVG outlines with about 1.5px strokes and rounded details; stat icons are 24px. Actions use 16–18px download/check strokes, and factual benefit lists use small green checks.

**Transfer:** Choose a single fine-outline family; use small recognizable action symbols and reserve filled tiles for integration artwork.

## Section recipes

How recurring sections are built.

### First screen: Routed product opening

**Observed:** A 60px Sticky navigation crowns a white first screen. Center the two-line display promise in a compact roughly 510px measure, with the first heading beginning about 105px beneath the navigation. Follow with a roughly 671px-wide lede after 24px, paired Primary button and Secondary button after 32px, then a muted small compatibility line after 20px. Routed process lines frame the sides and pass behind the action level. The Floating window begins roughly 63px below the microcopy, spans 1056px and is 614px tall. Within the first 900px, the complete copy and actions plus the upper half of the window are visible; the rest of the application continues below. Layers run from white canvas to routed artwork to text/actions to the raised window.

**Transfer:** Lead with a focused promise and a real working-state object, not a catalogue of features. With no finished product image, build a credible simplified workflow panel while retaining the routed frame. Directory pages instead open compactly with the 48px heading recipe, 72px top padding and one centered support line before the flat matrix.

**Avoid:** Do not shrink the interface into a small card beside the headline, or let the routed artwork cross readable letterforms.

**Text style:** `display` — Inter 560 · 64px/1.04 · tracking -0.04em

### Centered demonstration chapter

**Observed:** A heading and lede sit centered above a single broad Working interface stage, within a white or Band section padded 108px vertically. The heading uses heading typography, support follows after about 20px and the heading group leaves 48px before the stage.

**Transfer:** Give one high-value workflow its own large, legible demonstration instead of compressing several into thumbnail cards.

**Text style:** `heading` — Inter 560 · 48px/1.08 · tracking -0.03em

### Alternating workflow split

**Observed:** The split layout pairs a 520px copy column with a 520px demonstration across an 80px gap. Copy contains heading-split, lede and small check-mark benefit lines. Successive chapters reverse the text/media side and alternate Canvas and Band.

**Transfer:** Use the alternating composition for distinct capabilities, keeping each focused on one action or user outcome.

**Text style:** `heading-split` — Inter 560 · 48px/1.06 · tracking -0.035em

### Qualitative proof matrix

**Observed:** A two-by-two Word stat matrix faces a heading and paragraph across the split layout, all on Band. Blue icons and short labels stand in for giant numbers.

**Transfer:** Use qualities or honest compact metrics to support a product-experience claim.

**Text style:** `stat-word` — Inter 560 · 24px/1.6 · tracking -0.02em

### Flat capability collection

**Observed:** Shared-rule matrix holds four Feature cells beneath a centered heading/support pair. A directory-page variant opens with a compact heading then a three-column, multirow matrix; row heights follow content at roughly 175–220px.

**Transfer:** Use a short strip to establish assurance and a scoped directory for breadth; keep the same icon/title/body sequence.

**Text style:** `cell-title` — Inter 540 · 20px/1.6 · tracking -0.01em

### Single offer and objections

**Observed:** Band holds a split purchase promise and Purchase card with a 48px column gap. A separate white, 680px-wide FAQ section follows, with a centered 48px heading and ruled FAQ rows.

**Transfer:** Separate the commercial offer from the practical answers so neither becomes fine print.

**Text style:** `heading-split` — Inter 560 · 48px/1.06 · tracking -0.035em

### Lit closing and directory ending

**Observed:** Closing invitation sits inside Blue-lit closing panel with substantial outer whitespace. The main version is 413px tall inside a 108px-padded Band; the directory version is 323px tall with 72px inner vertical padding and 96px separation before Footer directory. Both endings retain a real footer rather than stopping at the buttons.

**Transfer:** Repeat the primary conversion pair with a brief final promise and then finish with the sparse directory and copyright row.

**Text style:** `heading-split` — Inter 560 · 48px/1.06 · tracking -0.035em

## Page flow

**Storyline:** Focused promise → tangible workflow proof → capability and assurance → commercial clarity or breadth → final invitation → utility directory.

### Flagship product landing page

1. **Promise** — Routed product opening with centered promise, paired actions and a broad working window.
2. **Product demonstration** — Centered stages isolate key workflows before alternating integration splits.
3. **Experience proof** — Qualitative stat matrix and flat assurance strip support the product's everyday value.
4. **Commercial clarity** — Single purchase card alongside a short offer statement.
5. **Objection handling** — Narrow ruled FAQ list.
6. **Closing call** — Blue-lit invitation with paired actions, followed by a directory footer.

**Transfer:** Choose the demonstrations and proof types that matter for the new product; retain the routed signature, floating working panels and softly lit close without treating the section order as fixed.

### Capability directory

1. **Scope promise** — Compact centered heading and short plain-language introduction.
2. **Capability breadth** — Three-column ruled matrix of icon, title and short explanation.
3. **Closing call** — Compact blue-lit invitation followed by the shared footer.

**Transfer:** Use the restrained directory variant for comprehensive capabilities; do not repeat the full flagship hero on every supporting page.

## Writing

Direct, practical and lightly opinionated. Confidence comes from naming actual actions and removing specific friction, not from visionary or enterprise language.

**Do not copy:** Do not reuse Nimble, SwiftLab, its identity artwork, exact product claims, platform guarantees, integration promises, pricing, trial terms or source copy as claims for another product. Examples illustrate structure only.

- **Addressing the reader:** Address the reader through 'your' and short imperatives; name the product when explaining what it does. Use first-person plural sparingly.
- **Rhythm:** Major headings are usually one compact sentence or a pair of blunt fragments. Support paragraphs explain a workflow, then often finish with short friction-removal statements. No exclamation-driven sales tone.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product category and its distinguishing purpose in one sentence. | 6–10 words | “The Mac Git client built for AI.” |
| Capability heading | A familiar workflow or action followed by a simple outcome. | 5–9 words | “Your entire workflow, one command palette.”<br>“Turn Linear issues into branches.” |
| Assurance | Short ownership promise supported by concrete exclusions. | 4–14 words | “Your code stays yours.”<br>“No account. No cloud. Your repositories never leave your Mac.” |
| Directory description | Start with an action and specify its useful granularity. | 12–30 words | “Stage and unstage individual hunks, split one file’s changes across several commits.” |
| Action | Literal action plus a clear commercial qualifier. | 2–6 words | “Download free trial”<br>“Buy for $49” |

**Words and phrasing to use:** built for; your workflow; without leaving; built in; just; no clutter; one simple; local-first

**Avoid:** revolutionary; game-changing; unlock limitless potential; enterprise-grade synergy; the future of everything

**Rules:**

- Describe the actual operation before asserting convenience.
- Use short 'No …' statements only when a concrete limitation really is absent.
- Keep prerequisites and terms close to conversion controls in compact dot-separated microcopy.
- Feature titles name capabilities; descriptions explain the action or safeguard rather than repeating the title.

## Do's and Don'ts

### Do

- Keep the opening display at weight 560 and -0.04em tracking, rather than using a heavy display cut.
- Use 108px major-section padding to let the compact demonstrations breathe.
- Keep the main working window broad at 1056px within the 1120px content system.
- Pair 48px conversion controls with a 12px gap and distinct blue/white emphasis.
- Use 1px shared gutters and square corners for feature matrices.
- Reserve 24px radii and broad layered shadows for windows and raised purchase panels.
- Use 14px/1.6 gray descriptions to contrast with 20px feature titles.
- Finish with the blue-lit outlined invitation and a separate directory footer.

### Don't

- Do not fill whole chapters with saturated blue; its role is actions, icons and fine artwork.
- Do not replace charcoal heading text with gradient-filled lettering.
- Do not apply the floating-window shadow to every feature cell.
- Do not turn the performance matrix into 100px numerical typography; its labels are 24px.
- Do not introduce a second marketing display family or monospace headlines.
- Do not use thick 3px card borders where 0.5–1px alpha rules belong.
- Do not make every neutral identical: white cells, near-white bands and porcelain windows have different jobs.
- Do not convert the lightly blue-lit closing panel into a dark high-contrast campaign banner.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background, border-color, color and transform transitions of 0.15s, with box-shadow at 0.2s.
- Navigation declares background, box-shadow and backdrop-filter transitions of 0.25s.
- Reveal groups declare opacity and transform over 0.6s with cubic-bezier(0.16, 1, 0.3, 1).
- Peripheral tiles declare chip-float animations lasting 6.5–8s, ease-in-out, infinite, with staggered negative delays.
- Routed artwork declares a tree-follow-scroll animation with linear timing.

**Transfer:**

- Keep floating motion on peripheral integration tiles, not on the readable working window.
- Use the declared restrained reveal language for whole groups so headings and panels settle as coherent compositions.

**Unknown:**

- Exact tile displacement, scroll-driven route progression and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 560px, 600px, 601px, 720px, 768px, 799px, 800px, 860px, 861px, 900px and 1200px across the two page types.
- Split gaps use clamp(32px, 6vw, 80px); closing vertical padding uses clamp(48px,8vw,96px).

**Transfer:**

- On narrow layouts, stack split copy and working panels, preserving the original content order and a useful visible portion of the interface.
- Simplify routed artwork to a few side paths before it competes with text; retain the rounded bends and endpoint nodes.
- Reduce the flat matrix column count while preserving shared rules, rather than switching to a stack of floating cards.

**Unknown:**

- Exact mobile heading sizes, navigation collapse and grid-switch thresholds are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
