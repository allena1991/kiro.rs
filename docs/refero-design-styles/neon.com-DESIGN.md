# Neon — phosphor signal machinery

## Overview

A dark, technical marketing style with the atmosphere of a live instrument rather than a conventional software brochure. Regular grotesk typography, terminal-like monospace banners and mint-green light sit against near-black, interrupted by pale green explanatory panels. Abstract signal footage, fine-line diagrams and grainy monochrome proof sculptures give complex products a tangible presence; text is sparse within expansive stages but compact inside functional panels.

### Essentials

- Headlines behave like a continuous spoken explanation: Inter 400, 56px/1.125 in the opening and 44px/1.125 in capability chapters, with -0.04em tracking and white statements flowing directly into gray elaboration.
- The opening is a low-anchored promise under a luminous signal field: a 64px black navigation bar, 32px side gutters, roughly 384px of art above the text, two 44px pill actions and a muted logo strip within the first 900px.
- Darkness carries the page; mint is a controlled signal rather than a blanket brand fill: black and #18191b dominate, #e4f1eb forms full-width explanatory relief, and #34d59a is reserved for a terminal action and small highlights.
- Technical chapter markings create a left rail: 12px uppercase monospace labels and 128px low-contrast monospace numerals sit beside an inset, 1024px-wide narrative column; retain this apparatus for new content.
- Proof becomes a staged machine object: square black 1px-outline stat or quote panels overlap grainy monochrome window trails, logo fields or wireframe forms. Include a sculptural proof scene; use repeated original text tiles and line geometry when equivalent imagery is unavailable.
- Terminal banners interrupt the sans-serif narrative: 52px/63px mint monospace lines sit on separate #0d221a rectangular strips, followed by 20px uppercase monospace support. Include this device alongside a pale-green statement with flat translucent marker highlights.
- The ending returns to active machinery: a full-width dark data-text scene supports a monumental 72px closing claim, a bottom-aligned 32px support line and a row of white, outlined and green command pills, followed by a dense black multi-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Terminal phosphor | `#cae6dc` | `--color-mint-text` | text | Monospace banner headings and their uppercase descriptions. |
| Terminal strip | `#0d221a` | `--color-strip` | surface | Dark rectangular backing behind each terminal headline line. |
| Mint tile | `#cddfd7` | `--color-tile` | surface | Flat benefit cards on pale mint paper. |
| Pale mint paper | `#e4f1eb` | `--color-pale` | background | Full-width explanatory and commercial relief bands. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Command green | `#34d59a` | `--color-accent` | action, accent | Terminal command action; maintain a small footprint relative to the dark canvas. |
| Mint marker | `#7dc3a9` | `--color-marker` | accent | Visible translucent marker on pale mint paper: rgba(57,165,125,0.6) over #e4f1eb. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal white | `#ffffff` | `--color-white` | text, action | Primary headings, active text and white conversion pills. |
| Pure black | `#000000` | `--color-canvas` | background, text | Default page canvas; dark text on pale bands and terminal action. |
| Closing graphite | `#151617` | `--color-closing` | background | Backing of the closing data scene. |
| Graphite band | `#18191b` | `--color-band` | surface, background, border | Technical proof bands, announcement strip and almost-black chapter numerals. |
| Button ink | `#1a1a1a` | `--color-button-ink` | text | Text on white primary actions. |
| Panel edge | `#242628` | `--color-edge` | border, surface | Subtle 1px outlines of black stat and quote panels. |
| Graphite rule | `#303236` | `--color-rule` | text, border, surface | Major dark separators, window title bars and dark card body text on mint. |
| Stat divider | `#494b50` | `--color-stat-edge` | border | Vertical separators in the institutional metric row. |
| Outline gray | `#61646b` | `--color-outline` | text, border | Secondary pill edges and paragraph text on pale backgrounds. |
| Narrative gray | `#797d86` | `--color-muted` | text, border | The explanatory half of large dark headings and pale-band separators. |
| Caption gray | `#94979e` | `--color-caption` | text | Compact capability descriptions. |
| Link gray | `#afb1b6` | `--color-footer` | link, text | Footer links and secondary attribution. |
| Light technical gray | `#c9cbcf` | `--color-body` | text, action | Dark-band paragraphs, compact labels and primary-button hover. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Live status green | `#00e599` | `--color-status` | accent | Tiny operational-status dot in the footer. |

## Typography

- **Inter** — Marketing headings, paragraphs, navigation and button labels. Neutral grotesk, mostly regular weight, with tightly fitted large sizes. Font stack: "Inter", "Inter Fallback", ui-sans-serif, system-ui, sans-serif.
- **GeistMono** — Technical chapter markings, strip headlines and terminal actions. Straight monospaced forms that evoke terminal readouts rather than decorative coding. If unavailable, use **Geist Mono**. Use weights 400–500; preserve the untracked banner text. Font stack: "GeistMono", "Geist Mono", ui-monospace, SFMono-Regular, "Roboto Mono", Menlo, Monaco, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| chapter-number | GeistMono | 400 | 128px | 1 | -0.04em | Low-contrast chapter counters in the left rail. |
| stat | Inter | 400 | 80px | 1 | -0.02em | Default oversized number in a proof panel. |
| heading-closing | Inter | 400 | 72px | 1 | -0.04em | Monumental closing claim above the data scene. |
| heading-commercial | Inter | 400 | 64px | 1 | -0.04em | Commercial proposition on pale mint and institutional figures. |
| display | Inter | 400 | 56px | 1.125 | -0.04em | Two-line opening promise. |
| heading-light | Inter | 400 | 52px | 1.125 | -0.04em | Broad thesis on a pale band with marked phrases. |
| terminal-heading | GeistMono | 400 | 52px | 63px | normal | Large uppercase text on separate rectangular strips. |
| heading | Inter | 400 | 44px | 1.125 | -0.04em | Main capability chapter headings; white claim joined to muted explanation. |
| heading-compact | Inter | 400 | 36px | 1.125 | -0.04em | Technical and institutional chapter statements. |
| closing-support | Inter | 400 | 32px | 1.25 | -0.04em | Bottom-aligned closing support statement. |
| card-heading | Inter | 400 | 28px | 1.25 | -0.02em | Two-line benefit card titles. |
| quote | Inter | 400 | 24px | 1.5 | -0.02em | Customer quotation in an outlined black panel. |
| terminal-support | GeistMono | 400 | 20px | 1.125 | normal, uppercase | Short descriptions immediately below terminal strips. |
| body | Inter | 400 | 18px | 1.5 | -0.02em | Longer explanatory paragraphs. |
| body-compact | Inter | 400 | 16px | 1.375 | -0.025em | Benefit-card support. |
| button | Inter | 500 | 16px | 1 | -0.02em | Primary conversion labels. |
| button-secondary | Inter | 400 | 16px | 1 | -0.02em | Secondary outlined conversion labels. |
| command | GeistMono | 500 | 16px | 1 | -0.02em | Copyable command pill. |
| navigation | Inter | 400 | 15px | 1.5 | -0.01em | Main navigation labels. |
| footer-link | Inter | 400 | 15px | 1 | -0.02em | Compact footer column links. |
| eyebrow | GeistMono | 500 | 12px | 1 | normal, uppercase | Section labels and opening affiliation line. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| large quantified proof scenes | stat-hero | Inter | 400 | 98px | 1 | -0.02em | Single dominant percentage in a large proof sculpture. |

**Notes:**

- Keep the visual weight of large headings at 400; emphasis comes from white versus gray, not bold.
- Use -0.04em for narrative headings, -0.02em for most body and action text, and normal tracking for terminal banners.
- Headings often indent their first line by 96px within the main column; following lines return to the column edge.
- The 64px institutional figures share the commercial headline recipe; do not introduce a new heavy numeric face.

## Layout

**Density:** Airy stages with compact technical internals: long pauses between narrative chapters, tight labels and line-bound panels within each scene.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Micro-heading to description gap and icon-label separation. |
| 12px | Benefit title to support gap; command to copy-icon gap. |
| 16px | Repeated card grid gaps. |
| 20px | Adjacent hero and closing actions; footer link column rhythm. |
| 28px | Horizontal padding of 44px conversion pills. |
| 32px | Desktop page gutters and proof-panel padding. |
| 48px | Separation between stacked capability explanations. |
| 64px | Capability heading to content group; top inset of institutional proof. |
| 88px | Commercial heading group to benefit grid; desktop footer column gaps. |
| 96px | Technical band vertical padding and heading first-line indentation. |
| 128px | Major section separation and pale-band vertical padding. |

### Containers and grids

- **marketing container**: max width 1600px · side padding 32px. Wide centered marketing canvas, 1376px of usable width at a 1440px viewport.
- **chapter grid**: 2 columns · gap 0px. 352px left chapter rail and flexible narrative column; at 1440px the narrative begins 384px from the left edge.
- **technical grid**: 2 columns · gap 128px. 224px side navigation with a flexible technical story column, sharing the chapter content alignment.
- **commercial container**: max width 1280px · side padding 32px. Narrower centered pale-band content.
- **benefit grid**: 4 columns · gap 16px. Equal square-edged 292px-wide cards at desktop.
- **global frame**: max width 1856px · side padding 32px. Navigation, closing content and footer use the broadest shared frame.

## Corner radius

| Element | Radius |
| --- | --- |
| conversion pills | 9999px (pill) |
| marketing panels | 0px |
| navigation and link focus targets | 4px |

## Surfaces and depth

### Surfaces

#### Black canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Most of the page is pure black, allowing subtle outlined objects and low-contrast numbers to sit directly on the canvas.

**Transfer:** Use black as the resting field, not an elevated card surface over a gray page.

#### Graphite band · level 0

**Use:** Technical comparisons and institutional proof.

**CSS:** `background: #18191b; color: #ffffff`

**Observed:** Edge-to-edge matte charcoal with generous vertical padding; no cast shadows.

**Transfer:** Group adjacent technical arguments into one continuous band.

#### Mint paper · level 0

**Use:** Explanatory thesis and commercial relief.

**CSS:** `background: #e4f1eb; color: #000000`

**Observed:** A pale desaturated green inversion rather than white; diagrams and darker mint cards remain legible against it.

**Transfer:** Reserve this inversion for high-value explanation or decision support.

#### Black proof panel · level 1

**Use:** Floating stat and quote boxes.

**CSS:** `background: #000000; border: 1px solid #242628; border-radius: 0px; box-shadow: none`

**Observed:** Thin-edged rectangular panels overlap the proof artwork without lifting via shadows.

**Transfer:** Let an opaque panel interrupt and clarify a busier scene.

#### Mint benefit tile · level 1

**Use:** Commercial benefits.

**CSS:** `background: #cddfd7; border-radius: 0px; box-shadow: none`

**Observed:** Flat tonal blocks, darker than the mint paper backing.

**Transfer:** Use tonal separation instead of borders or elevation.

#### Marker emphasis

**Use:** Selected short phrases on mint paper.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0) 7.8px, rgba(57, 165, 125, 0.6) 7.8px); box-decoration-break: clone; padding-left: 5.2px; padding-right: 7.8px`

**Observed:** The first 7.8px stay clear; the remaining line box receives a flat green marker rectangle with square ends.

**Transfer:** Mark two or three meaningful noun phrases, not the whole statement.

#### Closing data backing · level 0

**Use:** Final conversion stage.

**CSS:** `background: #151617; color: #ffffff; overflow: hidden; position: relative`

**Observed:** Darkened table-like activity text and restrained green scan bands sit behind the foreground message.

**Transfer:** Keep the background substantially lower contrast than every action and line of text.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 0px 28px; background: #ffffff; color: #1a1a1a; border-radius: 9999px`

**Text style:** `button` — Inter 500 · 16px/1 · tracking -0.02em

**Observed:** Plain text with no leading icon. In the mint commercial band, the fill reverses to black with white text; navigation uses a smaller 36px version with 18px side padding.

**States:** Declared: hover background-color #c9cbcf; focus-visible 2px solid #38a57d outline with 2px offset.

**Transfer:** Choose one concise verb-led conversion label.

### Secondary button

**Use:** Documentation or lower-commitment action beside the primary.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 0px 28px; border: 1px solid #61646b; border-radius: 9999px; background: transparent; color: #ffffff`

**Text style:** `button-secondary` — Inter 400 · 16px/1 · tracking -0.02em

**Observed:** The closing version has a very faint white wash; its hierarchy stays below the white pill.

**States:** Declared: hover border-color #ffffff; focus-visible 2px solid #38a57d outline with 2px offset.

### Command pill

**Use:** A direct technical-start action in the closing stage.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 0px 28px; gap: 12px; background: #34d59a; color: #000000; border-radius: 9999px`

**Text style:** `command` — GeistMono 500 · 16px/1 · tracking -0.02em

**Observed:** A shell prompt precedes the command; a small overlapping-square copy icon closes the pill.

**States:** Declared: hover background-color #47d18c; focus-visible 2px solid #38a57d outline with 2px offset.

**Transfer:** For non-developer products, use an equally direct one-step action while keeping this green pill distinct from the standard white primary.

### Navigation trigger

**Use:** Compact top navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 4px; padding: 0px 14px; border-radius: 4px; color: #ffffff; background: transparent`

**Text style:** `navigation` — Inter 400 · 15px/1.5 · tracking -0.01em

**Observed:** Dropdown categories carry a subdued small chevron. The enclosing black bar is 64px high, sticky, with logo left and community links plus two 36px account pills right.

**States:** Declared: hover color #ffffff; focus-visible 2px solid #38a57d outline with 2px offset.

### Terminal banner

**Use:** Proof-scene heading that feels like a terminal readout.

**CSS:** `position: relative; padding-left: 32px; color: #cae6dc; line-height: 63px`

**Text style:** `terminal-heading` — GeistMono 400 · 52px/63px

**Observed:** Each line has its own dark-green strip, 56px high within a 63px line box; strip widths step rather than forming one solid paragraph block. Uppercase support sits 14px below, aligned with the text inset.

**Transfer:** Write a short situational heading broken into two emphatic lines.

### Stat panel

**Use:** Quantified proof overlapping an artwork field.

**CSS:** `background: #000000; border: 1px solid #242628; padding: 32px 32px 0px; border-radius: 0px`

**Text style:** `stat` — Inter 400 · 80px/1 · tracking -0.02em

**Observed:** Large regular-weight number above a short paragraph. A larger percentage variant uses a thin gray title bar and greater top breathing room.

**Transfer:** Replace the figure with verified proof and make its unit immediately clear.

### Quote panel

**Use:** Human validation inside a large proof scene.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 32px; background: #000000; border: 1px solid #242628; border-radius: 0px`

**Text style:** `quote` — Inter 400 · 24px/1.5 · tracking -0.02em

**Observed:** Open quotation above a bottom attribution row with a square organization mark, person name and muted role; sits clear of the repeated window trail.

**Transfer:** Use a specific practical outcome, not generic praise.

### Benefit tile

**Use:** Scannable commercial or decision benefits.

**CSS:** `display: flex; flex-direction: column; min-height: 376px; padding: 32px 32px 28px; background: #cddfd7; color: #000000; border-radius: 0px`

**Text style:** `card-heading` — Inter 400 · 28px/1.25 · tracking -0.02em

**Observed:** A small black dot-matrix symbol occupies the upper left. Title and 16px support form a bottom-aligned text group separated by 12px; no per-card action.

**Transfer:** Keep titles brief and contrast distinct buying benefits, rather than making a miniature feature inventory.

### Footer link

**Use:** Dense navigation columns at the end.

**CSS:** `display: flex; align-items: center; padding: 1px 0px; border-radius: 4px; color: #afb1b6`

**Text style:** `footer-link` — Inter 400 · 15px/1 · tracking -0.02em

**Observed:** Four columns of links, some with small gray social icons; short uppercase white column headings sit above them. A separate bottom row contains a live-status dot and legal links.

**States:** Declared: hover color #ffffff; focus-visible 2px solid #38a57d outline with 2px offset.

### Institutional metric cell

**Use:** A small set of large scale or credibility facts.

**CSS:** `display: flex; flex-direction: column; padding: 0px 16px 8px; border-left: 1px solid #494b50; min-height: 337px; color: #ffffff`

**Text style:** `heading-commercial` — Inter 400 · 64px/1 · tracking -0.04em

**Observed:** Small light-gray explanation at the top, large figure or partner lockup pinned to the bottom; the first cell is roughly twice as wide as its neighbors.

**Transfer:** Use two or three verified facts, letting the vertical empty space make them feel substantial.

## Imagery and graphics

### Phosphor signal field

**Use:** The opening's full-bleed primary artwork.

**Observed:** Soft-focus vertical green and cyan light bars form irregular waves across a black field, brightest toward the upper and right areas. Tiny dot texture, optical bloom and occasional pale yellow edges suggest a filmed electronic display. The artwork spans beyond the content width; a black fade protects the low-left headline.

**Transfer:** Create an abstract signal shaped by the new product's activity; no literal product render is needed. A layered SVG of luminous bar clusters is the minimum acceptable substitute.

**Build:** On black, arrange clusters of thin vertical SVG strokes with varying heights and 10–18px spacing, tracing several rising and falling envelopes. Use command green and mint-text strokes at varied alpha with a few cyan offsets; duplicate the strokes beneath with 4–12px Gaussian blur. Add a very faint repeating 2px dot mask and a black vertical gradient over the lower third. Keep broad irregular black gaps and the lower-left text zone dark.

### Technical miniatures and branching scene

**Use:** Capability tiles and deeper workflow explanation.

**Observed:** Cropped dark product-like panels use tiny white or gray text, mint activity pixels and fine connection lines. A branching workflow uses a centered tree of thin green curves, white capsule nodes and faint vertical guides beside a separate chat-style panel.

**Transfer:** Show one intelligible operation per miniature. For a full demonstration, pair a clean relationship diagram with a short contextual interface, rather than reproducing an entire application.

**Build:** Use SVG paths with 1px muted green strokes on black, branching from a central upper capsule into two lower nodes. Put subtle vertical guide lines beneath at low opacity; back interface panels with near-black and a fine gray edge. Keep readable marketing copy outside these details.

### Monochrome proof sculptures

**Use:** Large proof stages paired with Terminal banner, Stat panel or Quote panel.

**Observed:** Three related constructions appear: a dim logo field with a retro initialization window; a sweeping diagonal procession of overlapping desktop windows containing grainy monochrome marks; and a giant cropped wireframe globe wrapped in striped grayscale organization names. Artwork is substantially larger than the accompanying copy and often bleeds outside the viewport.

**Transfer:** Preserve the repeated, spatially staged proof-object language using original customer marks or product artifacts. When those are unavailable, use meaningful category labels in repeated small windows and a wireframe form, not generic stock photography.

**Build:** Construct square black SVG window tiles with 1px gray outlines and a dark title bar; place monochrome content inside and overlay feTurbulence noise at low opacity. Duplicate along a curved diagonal path with 12–32px offsets and overlap heavily. For a globe, clip fine vertical stripes to an ellipse, draw latitude arcs and longitude curves in light gray, then wrap text along curved bands. Place an opaque Black proof panel in the foreground.

### Engineering diagrams and load plots

**Use:** Pale explanatory and graphite comparison bands.

**Observed:** The pale architecture graphic is an orthogonal system diagram with outlined mint modules, fine black arrows, hatched inactive areas and tiny orange connector markers. The dark comparison plot places a red failure peak beside a green adaptive area graph, with hairline grids and small terminal tooltips.

**Transfer:** Explain a genuine cause-and-effect relationship. Simplify to a small number of labeled modules or two comparative traces; retain the fine technical drafting rather than glossy dashboard styling.

### Dot-matrix symbols

**Use:** Top-left marks in mint Benefit tiles.

**Observed:** Black circular dots grow and shrink across small geometric clusters, each occupying a 56px square. The mark is isolated above a large empty interval before the text.

**Transfer:** Use simple abstract glyphs tied to the benefit rather than multicolor illustrative icons.

**Build:** Create a 7×7 SVG circle grid inside 56px, with 5–7px pitch. Vary circle radii from 0.5–2.5px to form a diagonal wedge, burst or ring; fill black and leave the surrounding square transparent.

### Live data closing scene

**Use:** The full-width final conversion stage.

**Observed:** Columns of faint monospace activity rows extend edge to edge with occasional horizontal green scan highlights and a small connection-status readout. The scene is nearly black so foreground support and pills remain dominant.

**Transfer:** Use the new product's plausible activity vocabulary as ambient texture. The minimum version is an original table-like SVG texture with a few dim green row bands.

**Build:** Fill a wide dark backing with tightly spaced 12–14px mono text columns at low white alpha. Vary row opacity and add 2–3 green rectangles at roughly 0.06–0.12 alpha across selected rows. Add a dark scrim over the entire layer and place all foreground text and actions above it.

### Icons

**Observed:** Small utility icons are mostly 14–18px monochrome outlines or simple silhouettes, with 1–1.5px strokes. Social marks sit directly beside navigation and footer labels; the command uses a small copy glyph. Commercial dot symbols are a separate 56px illustration system.

**Transfer:** Use restrained utility SVGs matched in weight; keep functional icons compact and reserve dot-matrix art for benefit markers.

## Section recipes

How recurring sections are built.

### First screen: Signal field opening

**Observed:** A 36px announcement strip sits above a sticky 64px black navigation bar. Below it, the Phosphor signal field occupies most of the upper screen, fading to black behind a low-left text group. A 12px monospace affiliation line precedes a regular 56px two-line white headline by 20px. The headline spans about four fifths of the available width; one technical noun receives a subtle dotted underline. Primary button and Secondary button sit 32px below with a 20px gap. A thin rule and horizontally spaced gray customer marks finish the screen. Within 900px, navigation, the luminous main object, full headline, actions and logo strip are visible; numbered capability chapters start below.

**Transfer:** Stage a dark abstract signal above a low-anchored promise, using the SVG bar-field substitute when no motion artwork exists. Keep the affiliation line only if there is a meaningful trust cue. Other product or campaign openings can shorten the artwork but should preserve the black stage, low-left promise and paired pills.

**Avoid:** Do not turn this into a centered headline over a gradient blob, or put a bright screenshot card immediately above the actions.

**Text style:** `display` — Inter 400 · 56px/1.125 · tracking -0.04em

### Numbered capability chapter

**Observed:** Chapter grid pairs a small uppercase technical label and almost-black 128px numeral on the left with a 44px white-and-gray heading on the right. The first line is indented 96px. Below, either five bottom-aligned capability miniatures fill the page width at 16px gaps, or a left explanation stack sits beside a large branching diagram and narrow interface panel.

**Transfer:** Use numbering to structure a few major arguments, not every small component. Lead with an affirmative white sentence and continue in gray with the mechanism.

**Text style:** `heading` — Inter 400 · 44px/1.125 · tracking -0.04em

### Terminal proof theater

**Observed:** Terminal banner heads a large black artwork stage. A grainy window trail, low-contrast mark field or wireframe sculpture is interrupted by an opaque Stat panel or Quote panel. Banner lines have different widths and can begin at the chapter column or farther left when the sculpture requires it.

**Transfer:** Use the apparatus to make proof feel like a physical scene; substitute original text tiles and line forms when there is no customer artwork.

**Text style:** `terminal-heading` — GeistMono 400 · 52px/63px

### Marked thesis and engineering explanation

**Observed:** Mint paper starts with a broad 52px black statement and several flat marker-highlighted phrases. A full-width hairline separates the thesis from a left section index and a large engineering diagram. The graphic remains technical, with pale modules and fine connectors rather than decorative blobs.

**Transfer:** State a durable product principle and then reveal why it works; use the contrasting band to slow the narrative.

**Text style:** `heading-light` — Inter 400 · 52px/1.125 · tracking -0.04em

### Technical comparison band

**Observed:** Graphite band uses Technical grid, an inset 36px white-and-gray statement, compact square comparison tabs, a wide finely gridded chart and a thin terminal-style counter strip beneath it. Supporting explanation and plot legend sit in two columns below. The institutional continuation replaces the graph with Institutional metric cells under a top rule.

**Transfer:** Compare outcomes on a shared baseline and label the trade-off; use the metric-cell continuation when organizational trust is the more appropriate proof.

**Text style:** `heading-compact` — Inter 400 · 36px/1.125 · tracking -0.04em

### Commercial mint relief

**Observed:** Mint paper with 128px vertical padding and Commercial container. A 12px eyebrow, 64px black headline and 18px gray paragraph lead to a black Primary button. An 88px pause precedes four Benefit tiles in a 16px-gap grid. Dot-matrix symbols sit high while titles and support sit low.

**Transfer:** Make the cost, access or adoption model legible in plain language, then summarize a few concrete benefits without turning this into a dense plan table.

**Text style:** `heading-commercial` — Inter 400 · 64px/1 · tracking -0.04em

### Live machinery close

**Observed:** A 708px full-width Closing data backing supports a 72px white closing claim near its top. At the base, 32px two-line support sits left and Primary button, Secondary button and Command pill align right. The text/action row is separate from the ambient data texture. A black footer follows immediately, with a brand affiliation area on the left and four compact link columns on the right. The footer ends with a fine-rule status/legal row and a 6px green status dot.

**Transfer:** Close with a strong destination statement, a practical final invitation and direct ways to begin. Use original activity text behind the message and adapt the footer categories to the new product.

**Text style:** `heading-closing` — Inter 400 · 72px/1 · tracking -0.04em

## Page flow

**Storyline:** promise → capability chapters → staged proof → underlying mechanism → economic rationale → final invitation and utility navigation

### A flagship product landing page that explains breadth, establishes trust and makes technical adoption feel immediate

1. **Promise** — Full-bleed luminous signal artwork above a low-left two-line claim, paired pills and subdued customer marks.
2. **Capability chapters** — Numbered side rail and continuous white-to-gray headings, followed by miniatures and a larger workflow demonstration.
3. **Social and quantified proof** — Terminal strips introduce spatial monochrome proof sculptures with overlapping quote or number panels.
4. **Mechanism** — A mint-paper thesis with marker phrases gives way to engineering diagrams and dark comparative performance evidence.
5. **Institutional trust** — Sparse large metrics sit at the base of tall left-ruled cells.
6. **Decision support** — A pale commercial argument and bottom-aligned benefit tiles clarify adoption.
7. **Closing call** — Active data texture, large final claim, bottom action row, then dense utility columns and operational status.

**Transfer:** Adapt the narrative to the product's strongest proof and objections; preserve the signal opening, terminal markings, sculptural proof, mint relief and live-machinery ending without fixing a section count or rigid order.

## Writing

Confident and technically literate, with plain assertions followed by concrete mechanisms. The tone is direct and ambitious without jokey developer slang or a conversational sales pitch.

**Do not copy:** Do not reuse Neon or Databricks names, logos, proprietary artwork, customer identities, quotations, platform affiliations, market-share claims, customer counts or commands. Replace every claim and metric with substantiated material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for practical consequences; use the product name for declarative capability statements. First-person plural is uncommon outside a customer quotation.
- **Rhythm:** Short declarative hooks flow into one-sentence explanations, often within the same heading. Longer thesis headings remain grammatical sentences; buttons are brief imperative phrases. Terminal headlines and labels use uppercase, while ordinary headings use sentence case.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category, the audience and the durable technical foundation in one sentence. | About 12–18 words | “The backend for apps and agents, built to scale on Postgres.” |
| Capability hook | A short affirmative claim followed by a concrete mechanism. | Hook of 3–6 words; explanation of 15–25 words | “Ready for coding agents.”<br>“Create and branch environments the way you work with PRs, with full access via MCP, CLI, and SDK.” |
| Commercial headline | Contrast the useful outcome with waste or unnecessary obligation. | About 12–18 words | “Pay for what you use, not for the infrastructure you might need.” |
| Support | Explain exactly what the system does and why it matters. | One or two compact sentences | “Infrastructure that responds instantly. Agents don't wait for servers, tickets, or manual provisioning.” |
| Action | Unadorned verb plus object or destination. | 2–3 words | “Get started”<br>“Read the docs”<br>“View Pricing” |

**Words and phrasing to use:** build; start; scale; instant; isolated; reliable; full access; pay for what you use; ready for; without

**Avoid:** magic; 10x everything; game-changing; revolutionize; supercharge; delightful journey; excessive exclamation marks

**Rules:**

- Pair ambitious promises with a named mechanism or verified proof.
- Use specific technical nouns when they explain the product, not as decorative jargon.
- Let a short white hook and a gray continuation form one coherent thought.
- Keep commercial claims about what is included or charged rather than abstract value rhetoric.

## Do's and Don'ts

### Do

- Keep large narrative type regular at 400 with -0.04em tracking.
- Use 32px desktop gutters and maintain the shared inset narrative-column alignment.
- Make conversion pills 44px high with 28px horizontal padding.
- Use 1px panel edges and square corners for proof cards.
- Separate 52px terminal headlines into individually sized green strips.
- Give mint Benefit tiles 32px top/side padding and bottom-aligned text.
- Keep the proof artwork monochrome and grainy so white foreground panels remain legible.
- Use pale mint #e4f1eb rather than white for full-width explanatory relief.

### Don't

- Do not use bold 700 marketing headlines; their emphasis comes from color and scale.
- Do not round proof panels like the conversion pills; the square/pill contrast is essential.
- Do not spread #34d59a across every button or background; ordinary primary actions are white.
- Do not add floating drop shadows to the flat mint tiles or black proof panels.
- Do not convert technical diagrams into colorful isometric illustrations.
- Do not use a uniform card grid for every argument; retain the rail, open diagrams and spatial proof scenes.
- Do not render supporting technical text in pure white at every hierarchy level; preserve the gray ramp.
- Do not make terminal-style body text the default for the whole page; Inter carries ordinary reading.

## Motion and responsive

### Motion

**Observed:**

- Declared action color, background and border transitions use 0.2s cubic-bezier(.4, 0, .2, 1).
- A logo-style continuous strip declares infinityScroll for 60s linear infinite.
- Navigation submenu height declares a 0.3s cubic-bezier(0.4, 0, 0.2, 1) transition.
- The visual language includes video-backed signal and data scenes.

**Transfer:**

- Use restrained color changes on pills rather than scale or bounce.
- Keep ambient signal movement subordinate to the low-left promise; retain a legible static bar-field composition.
- Use steady continuous drift for a logo strip, not a sequence of attention-grabbing entrances.

**Unknown:**

- Exact video timing, scroll orchestration, shader behavior and reduced-motion variants are not established.

### Responsive

**Observed:**

- The declared stylesheet includes width boundaries at 640px, 768px, 1024px and 1280px among several finer adjustments.
- Responsive rules reduce heading sizes and strip heights, hide desktop navigation, shift the four benefit columns to two, and stack the closing text/action group.

**Transfer:**

- At narrow widths, reduce the chapter rail to a compact label/number above the heading while preserving its technical marking role.
- Keep separate terminal strips but shorten copy and scale down the monospace lines before allowing awkward word breaks.
- Reflow proof panels into the text flow when their overlap would obscure the artwork or quotation; retain a cropped sense of the larger sculpture.
- Use 20px side gutters on narrow screens and keep all foreground actions above the ambient closing data scene.

**Unknown:**

- Exact narrow-screen layouts, menu behavior and art cropping have not been visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
