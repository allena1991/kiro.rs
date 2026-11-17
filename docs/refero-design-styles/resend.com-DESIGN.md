# Resend — sculpted midnight machinery

## Overview

A cinematic black-on-black identity for developer tools and technically sophisticated products, with editorial serif promises and tightly tracked grotesk capability headings. Silver-edged sculptures, restrained interface demonstrations and near-invisible panel boundaries make the spacious composition feel engineered rather than decorative. Color arrives as isolated light, syntax and occasional vivid proof cards, never as the general canvas.

### Essentials

- Editorial promises above technical machinery: Domaine at 96px/1, weight 400 and -0.01em tracking contrasts with 56px/1.2 grotesk section titles at -0.05em.
- The opening is a dark product stage, not a dashboard billboard: a 480px text column faces a 648×550px sculptural scene within a 1280px container, under a 58px navigation bar.
- Actions feel like textured black hardware: 48px height, 16px corners, 2px translucent edges and a 25px backdrop blur; the secondary action is unfilled gray text.
- Black remains the dominant field: #000000 canvas, #f0f0f0 titles and #a1a4a5 support. Chromatic light stays local to small graphics or a single emphasized word; saturated flat panels belong to customer-story variants.
- Demonstrations emerge from darkness: 24px rounded frames, cool hairline edges, a faint top light and black gradient fades rather than opaque screenshot cards.
- A monumental typographic sign-off is part of the identity: a centered 76.8px serif closing promise and an oversized, extremely low-contrast wordmark clipped at the footer horizon. Use the new product's own lettering as SVG artwork when no sculptural media exists.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Purple gradient end | `#9a54dc` | `--color-purple` | accent | End of the isolated purple heading word, not a page background. |
| Violet emphasis | `#9281f7` | `--color-violet` | accent, text | Beginning of the isolated purple word gradient and selected technical accents. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Highlight white | `#ffffff` | `--color-white` | text, action, accent | Action lettering and the bright end of silver text and light gradients. |
| Absolute black | `#000000` | `--color-canvas` | background, surface, text | Continuous canvas and black text on the brightest proof panels. |
| Softly lit graphite | `#111111` | `--color-gradient-top` | surface | Top of capability panels fading toward black. |
| Recessed edge | `#1f2225` | `--color-edge-subtle` | border | Visible rgba(217,237,254,0.145) for low-emphasis cards. |
| Cool panel edge | `#292d30` | `--color-edge` | border | Visible rgba(214,235,253,0.19) outlines over black. |
| Support gray | `#a1a4a5` | `--color-muted` | text, link | Descriptions, secondary actions and navigation. |
| Cool link gray | `#abafb4` | `--color-link` | text, link | Footer lettering; rgba(241,247,254,0.71) over black. |
| Silver lettering | `#ecedef` | `--color-silver` | text | Visible result of rgba(252,253,255,0.937) over black; small display titles and card labels. |
| Soft white | `#f0f0f0` | `--color-ink` | text | Main headings and readable foreground text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer-story showcases | Story orange | `#f55b22` | `--color-story-orange` | surface | One full-color customer proof panel. |
| customer-story showcases | Story acid yellow | `#efff80` | `--color-story-lime` | surface | Bright proof panel with black lettering. |
| pricing and sales pages | Graphite panel | `#141517` | `--color-panel` | surface | Filled question rows. |
| forms and pricing controls | Smoke glass | `#151619` | `--color-glass` | surface | Visible rgba(24,25,28,0.88) input and selected-tab fill over black. |
| pricing and sales pages | Graphite boundary | `#212629` | `--color-panel-edge` | border | Question rows and sales form boundaries. |
| customer-story showcases | Story charcoal | `#2e2e2e` | `--color-story-charcoal` | surface | Neutral member of the customer-story panel series. |

## Typography

- **domaine** — Opening promises and monumental closing lines. High-contrast editorial serif with sculptural curves and fine hairlines. OpenType features: "ss01", "ss04", "ss05", "ss11". If unavailable, use **Instrument Serif**. 400; preserve short line lengths and tight tracking. Font stack: "domaine", "Instrument Serif", Georgia, serif.
- **aBCFavorit** — Capability titles, compact headings and stats. Regular-weight grotesk, tightly packed at display sizes. OpenType features: "ss01", "ss04", "ss05", "ss11". If unavailable, use **Inter**. 400; retain the strongly negative heading tracking. Font stack: "aBCFavorit", "Inter", ui-sans-serif, system-ui, sans-serif.
- **inter** — Body text, navigation, controls and quotes. Neutral, compact interface sans with regular descriptions and semibold actions. Font stack: "inter", ui-sans-serif, system-ui, sans-serif.
- **commitMono** (only for technical product demonstrations) — Code and API feedback. Evenly spaced, sober developer typography. If unavailable, use **Commit Mono**. Font stack: "commitMono", "Commit Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | domaine | 400 | 96px | 1 | -0.01em | Default landing-page promise, usually two short lines. |
| display-secondary | domaine | 400 | 76.8px | 1 | -0.01em | Closing promise and secondary page openings. |
| heading | aBCFavorit | 400 | 56px | 1.2 | -0.05em | Default major capability headings. |
| quote | inter | 500 | 24px | 1.5 | normal | Standalone centered customer quotations. |
| card-title | aBCFavorit | 400 | 20px | 1.3 | normal | Titles under illustrated feature cards. |
| body | inter | 400 | 18px | 1.5 | normal | Lead paragraphs beneath headings. |
| tab-title | aBCFavorit | 400 | 16px | 1.5 | -0.05em | Small selectors above a large demonstration. |
| label | inter | 400 | 16px | 1.5 | normal | Sentence-case chapter labels and question text. |
| action | inter | 600 | 16px | 1.5 | normal | 48px marketing actions. |
| body-small | inter | 400 | 14px | 1.6 | normal | Card descriptions, compact explanations and quote cards. |
| action-small | inter | 600 | 14px | 20px | normal | 40px actions in navigation and compact panels. |
| navigation | inter | 500 | 14px | 20px | normal | Navigation and small directional links. |
| link | inter | 400 | 14px | 20px | normal | Footer links and compact descriptive labels. |
| caption | inter | 400 | 12px | 16px | normal | Small photo captions, metadata and operational status. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| feature and sales pages | heading-tight | aBCFavorit | 400 | 56px | 1 | -0.05em | More compact multiline chapter headings. |
| sales proof sections | stat | aBCFavorit | 400 | 48px | 1 | normal | Large proof metrics between labels and explanations. |
| pricing, sales questions and company editorial sections | heading-compact | aBCFavorit | 400 | 36px | 1.3 | -0.05em | Utility and editorial section titles. |
| pricing cards | price | inter | 400 | 36px | 1.7 | -0.025em | Monthly prices and the custom-plan name. |
| customer-story showcases | story-title | inter | 500 | 32px | 1.3 | -0.025em | Low-anchored result statements on colored panels. |
| feature and sales capability grids | suite-title | inter | 400 | 20px | 28px | normal | Titles on smaller icon-led cards. |
| technical demonstrations | code | commitMono | 400 | 14px | 20px | normal | Code samples with subdued line numbers. |

**Notes:**

- The serif owns the promise; the grotesk owns explanation. Neither becomes bold to create hierarchy.
- Silver headings use a white-to-half-transparent diagonal text gradient, bright through the first 30%; support text stays flat gray.
- Use -0.05em tracking for large grotesk titles, but normal tracking for 20px illustrated-card titles. Body paragraphs remain normally tracked.
- The oversized closing wordmark is artwork, not another heading in the reading hierarchy.

## Layout

**Density:** Airy marketing chapters surround compact technical demonstrations; substantial darkness separates narrative ideas.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support spacing and small icon gaps. |
| 16px | Copy stacks, action-row gap and footer link-list rhythm. |
| 24px | Container side padding and plan-card padding. |
| 32px | Main grid gaps and the gap before actions. |
| 48px | Larger internal separations and compact section padding. |
| 64px | Utility-page opening padding and chapter-to-grid separation. |
| 96px | Default major section top and bottom padding. |
| 128px | Closing conversion sections. |
| 144px | Footer top and bottom padding. |

### Containers and grids

- **container**: max width 1280px · side padding 24px. Centered outer box; gives 1232px usable content on desktop.
- **detail container**: max width 1024px. Comparison tables, code examples, proof metrics and long question lists.
- **lead copy**: max width 480px. Hero description and narrow editorial reading measure.
- **feature pair**: 2 columns · gap 32px. Two large illustrated capabilities, equal width.
- **capability grid**: 3 columns · gap 32px. Small icon-led capabilities or demonstration selectors.
- **footer columns**: 5 columns · gap 32px. Link groups to the right of a separate 300px identity and status column.
- **plans** (only for pricing pages): 4 columns · gap 12px. Equal-height, equal-emphasis plan columns.

## Corner radius

| Element | Radius |
| --- | --- |
| marketing actions | 16px |
| large demonstrations | 24px |
| quote and plan cards | 16px |
| inputs and icon tiles | 12px |
| status badge | 9999px (pill) |
| small utility controls | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| action depth | `0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | Subtle action depth; outlines and light do more work than drop shadows. |

### Surfaces

#### Canvas · level 0

**Use:** All page backgrounds.

**CSS:** `background: #000000; color: #f0f0f0`

#### Silver text

**Use:** Display and section headings.

**CSS:** `background-image: linear-gradient(to right bottom, #ffffff 30%, rgba(255,255,255,0.5)); background-clip: text; -webkit-text-fill-color: transparent`

**Transfer:** Keep gradients neutral except for an isolated emphasized word.

#### Emergent frame · level 1

**Use:** Large illustrated capabilities.

**CSS:** `background: #000000; border: 1px solid rgba(214,235,253,0.19); border-bottom-width: 0px; border-radius: 24px`

**Observed:** The lower boundary disappears into the page; illustration and caption remain in one vertical composition.

**Transfer:** Fade a real product detail into the surrounding black rather than putting every detail on an opaque rectangle.

#### Fading quote · level 1

**Use:** Horizontal customer proof cards.

**CSS:** `background: linear-gradient(rgba(80,80,80,0.15) 0%, rgba(0,0,0,0) 70%); border: 1px solid rgba(217,237,254,0.145); border-bottom-width: 0px; border-radius: 16px`

#### Capability wash · level 1

**Only for:** feature and sales capability grids

**Use:** Compact icon-led panels.

**CSS:** `background: radial-gradient(29.48% 34.97% at 0% 58.67%, rgba(255,255,255,0.05) 0%, rgba(255,255,255,0.02) 50%, rgba(255,255,255,0) 100%), linear-gradient(#111111 0%, rgba(0,0,0,0.5) 100%); border: 0.5px solid rgba(217,237,254,0.145); border-radius: 24px`

#### Question panel · level 1

**Only for:** pricing and sales pages

**Use:** Objection-handling accordion rows.

**CSS:** `background: #141517; border: 1px solid #212629; border-radius: 16px`

#### Letter window

**Only for:** company narrative panels

**Use:** Personal authored statements presented as small desktop windows.

**CSS:** `background-image: linear-gradient(#000000,#000000), linear-gradient(0deg,#000000 25%,rgba(255,255,255,0.15)); background-clip: padding-box, border-box; border: 2px solid transparent; border-radius: 16px`

**Observed:** Alternating slight angles and blue, purple or cyan top glows enliven otherwise black windows.

**Transfer:** Use for an authored point of view, not a generic benefit grid.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; height: 58px; z-index: 40`

**Text style:** `navigation` — inter 500 · 14px/20px

**Observed:** Logo at left, compact menu group near center, login and compact primary action at right; tiny downward chevrons identify menus. The background visually merges into the stage.

### Primary button

**Use:** Main conversion action.

**CSS:** `height: 48px; padding: 0px 20px; border-radius: 16px; border: 2px solid rgba(255,255,255,0.05); background-image: linear-gradient(104deg, rgba(253,253,253,0.05) 5%, rgba(240,240,228,0.1) 100%); backdrop-filter: blur(25px); color: #ffffff; box-shadow: 0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `action` — inter 600 · 16px/1.5

**Observed:** Fine texture overlays the translucent face. Compact variant uses 40px height, 16px horizontal padding and action-small type; arrows accompany some product-page actions.

**States:** Declared: hover background-color color-mix(in oklab, #fff 90%, transparent), color #000; focus-visible uses the same background and text inversion.

**Transfer:** Use one prominent action per decision point; reproduce the texture with faint procedural grain.

### Secondary action

**Use:** Documentation or a lower-commitment alternative.

**CSS:** `height: 48px; padding: 0px 20px; border: 1px solid transparent; border-radius: 16px; color: #a1a4a5; background: transparent`

**Text style:** `action` — inter 600 · 16px/1.5

**Observed:** Sits beside Primary button without a visible filled surface; small arrows appear in feature chapters.

**States:** Declared: hover color #f0f0f0; focus-visible outline-style none with zero box-shadow.

### Illustrated feature card

**Use:** Paired demonstrations with compact explanation.

**CSS:** `display: flex; flex-direction: column; gap: 16px; border: 1px solid rgba(214,235,253,0.19); border-bottom-width: 0px; border-radius: 24px`

**Text style:** `card-title` — aBCFavorit 400 · 20px/1.3

**Observed:** Upper portion contains a large working-product vignette; below it sit a small icon, title, muted body-small paragraph and text link. Captions are inset from the outer frame.

**Transfer:** Choose a meaningful operation, not an abstract feature symbol, for the large vignette.

### Quote card

**Use:** Broad horizontal proof rail.

**CSS:** `width: 450px; padding: 24px 32px; border-radius: 16px; background-image: linear-gradient(rgba(80,80,80,0.15) 0%, rgba(0,0,0,0) 70%); border: 1px solid rgba(217,237,254,0.145); border-bottom-width: 0px`

**Text style:** `body-small` — inter 400 · 14px/1.6

**Observed:** Quote above a paired circular avatar/company mark, then person and role. Cards vary in height; the rail overflows the page edges with 32px gaps.

### Footer link

**Use:** Five compact groups in the closing utility area.

**CSS:** `padding: 2px 4px; border-radius: 6px; color: rgba(241,247,254,0.71)`

**Text style:** `link` — inter 400 · 14px/20px

**Observed:** Group labels are brighter than links. The separate identity column holds small address text, circular social icons and a status pill.

**States:** Declared: hover color #fcfdffef; focus-visible color #fcfdffef with zero box-shadow.

### Plan card

**Only for:** pricing pages

**Use:** Equal-weight commercial options.

**CSS:** `display: flex; flex-direction: column; padding: 24px; border: 1px solid rgba(214,235,253,0.19); border-radius: 16px; text-align: center`

**Text style:** `price` — inter 400 · 36px/1.7 · tracking -0.025em

**Observed:** Small plan label, generous space around price, quota between horizontal rules, left-aligned inclusion list with green ring checks, then a full-width compact Primary button aligned to the bottom. No brightly filled recommended tier.

### Question row

**Only for:** pricing and sales pages

**Use:** Collapsed objection handling.

**CSS:** `background: #141517; border: 1px solid #212629; border-radius: 16px; margin-bottom: 16px`

**Text style:** `label` — inter 400 · 16px/1.5

**Observed:** A full-width 56px inner trigger uses 16px padding and a small leading chevron. The complete bordered row is 58px high.

**Transfer:** Keep questions literal and commercially useful; do not turn the row into a promotional card.

### Capability card

**Only for:** feature and sales capability grids

**Use:** Compact suite or logic capabilities.

**CSS:** `padding: 32px 32px 24px; border: 0.5px solid rgba(217,237,254,0.145); border-radius: 24px; background-image: radial-gradient(29.48% 34.97% at 0% 58.67%, rgba(255,255,255,0.05) 0%, rgba(255,255,255,0.02) 50%, rgba(255,255,255,0) 100%), linear-gradient(#111111 0%, rgba(0,0,0,0.5) 100%)`

**Text style:** `suite-title` — inter 400 · 20px/28px

**Observed:** A 40px outlined icon tile precedes the title, muted description and small directional link.

### Story panel

**Only for:** customer-story showcases

**Use:** High-impact customer outcomes.

**CSS:** `min-height: 512px; padding: 40px; border-radius: 24px; background: #2e2e2e; border: 1px solid rgba(217,237,254,0.145); overflow: hidden; display: flex; flex-direction: column`

**Text style:** `story-title` — inter 500 · 32px/1.3 · tracking -0.025em

**Observed:** Customer logo sits high; outcome and Read story link sit low. Orange and acid-yellow variants accompany charcoal; yellow switches to black type. A 7%-opacity oversized graphic is clipped beyond the lower-right corner.

**Transfer:** Use real customer visual identities, with strong contrast and restrained watermark graphics.

### Sales textarea

**Only for:** sales inquiry forms

**Use:** Context gathering inside the outlined inquiry panel.

**CSS:** `height: 120px; padding: 12px; border: 1px solid rgba(176,199,217,0.145); border-radius: 12px; background: rgba(24,25,28,0.88); resize: none`

**Text style:** `link` — inter 400 · 14px/20px

**Observed:** The same smoke material is used for 32px single-line fields. Labels sit above fields; the form panel uses 32px padding and 16px corners. Submission is visibly disabled until ready.

## Imagery and graphics

### Black material sculpture

**Use:** Signature opening object and smaller chapter emblems.

**Observed:** A floating segmented cube balances the serif promise. Its surfaces alternate brushed metal, polished black, grain and perforated mesh. Hard silver highlights reveal edges while most faces disappear into the background. It occupies roughly the right half of the stage.

**Transfer:** Create a simple product-specific mechanical form or extruded symbol with convincing grazing light. The minimum is a few beveled dark geometric solids with distinct roughness, not an unrelated colorful illustration.

**Build:** Arrange a 3×3 group of beveled cuboids in three depth layers in a perspective SVG or 3D scene. Rotate the group slightly around its vertical axis; vary front-face gradients from black to near-black, add thin white edges at 10–25% opacity and fine noise masks to selected faces. Back it with a broad white radial light at 3–6% opacity above-right, and a low diagonal floor reflection blurred 20px. Keep the object within a 648×550px stage.

### Luminous seam

**Use:** Signature top-edge illumination on demonstration frames and transitions.

**Observed:** A fine horizontal highlight peaks in the center and fades at both ends, with a wider soft halo. Some seams carry a tiny violet or warm tint; the overall effect remains nearly monochrome.

**Transfer:** Use the seam to make one edge feel machined and lit rather than outlining an entire card brightly.

**Build:** Layer a 600×1px transparent-to-white-to-transparent gradient at the top center of a panel. Duplicate with blur(3px) and blur(10px) beneath it; lower opacity until only the center reads. Place a black-to-transparent fade over the lower media edge.

### Product demonstrations

**Use:** Large evidence scenes after capability introductions.

**Observed:** Code editors, email previews, analytic charts and workflow nodes are shown on black with tiny gray labels and controlled status color. Rounded frames occupy much more width than the introductory text. Lower portions often fade into the canvas.

**Transfer:** Show real, readable product operations. For a non-developer product, use its actual workflow or output in the same dark framing; small status color stays inside the demonstration.

### Monumental wordmark horizon

**Use:** Signature large-scale typographic artwork near the final conversion and footer.

**Observed:** Wide dark lettering spans the 1232px content width within a 265px-high artwork region. The lower letterforms are clipped by the footer edge, with an extremely faint neutral glow behind the horizon.

**Transfer:** Use the new product name or a short owned phrase. Construct vector lettering that feels physically present even at very low contrast; keep it decorative and separate from the accessible closing heading.

**Build:** Fit bold SVG word shapes across a 1232×265 viewBox and fill white at approximately 5% opacity over black. Enlarge until ascenders and bowls dominate the region; mask the bottom with the footer plane. Put a 1px white line at 10% opacity across the horizon and a broad white radial glow at 3% opacity beneath it.

### Feature emblem stage

**Only for:** individual product feature openings

**Use:** Centered compact alternative to the split sculpture opening.

**Observed:** A 130px rounded black emblem with metal rose highlights floats above the serif headline. Subtle grid lines and a faint halo sit behind it; the surrounding page still reads black, not purple.

**Transfer:** Use a compact sculptural glyph derived from the feature's operation.

**Build:** Create a 130px black rounded-square tile with 26px corners, a hairline silver rim and an extruded simple symbol. Add a diffuse 200px violet halo using rgba(101,101,236,0.125), plus a very faint rectilinear grid masked to fade outward.

### Human editorial photography

**Only for:** company and culture pages

**Use:** Founders and team chapters.

**Observed:** Natural-color candid people photos are centered around 810px wide against black, with small rounded corners and understated 12px captions. Investor portraits become grayscale 48px circles; photos remain warmer and more human than the metal art.

**Transfer:** Use genuine environmental team photography, not glossy stock portraits.

### Authored window stack

**Only for:** company narrative panels

**Use:** Personal principles or authored editorial statements.

**Observed:** Roughly 704px-wide black letter windows stagger with slight opposing rotations. A top toolbar carries three tiny window dots and a date; a pill author chip precedes a 36px title and 16px relaxed paragraph. Faint cyan, blue or magenta light enters at the top.

**Transfer:** Use for a handful of substantive statements by real people, retaining the browser-letter metaphor.

**Build:** Use Letter window surfaces with a 1px toolbar separator at 5% white, three 10px outlined circles and a right-aligned date. Add an absolute top radial glow in blue, cyan or purple at 8% opacity, fading by the bottom. Alternate small clockwise and counterclockwise rotations; preserve readable text.

### Icons

**Observed:** Mostly compact filled SVG symbols, not a uniform line-icon library: 14px menu chevrons, 16–18px interface symbols, 24px capability symbols and 32px language marks. Marketing icons are white or muted gray; dark 40px icon tiles have fine cool edges.

**Transfer:** Choose compact, optically balanced silhouettes with similar density. Keep chevrons small and subordinate; use status color only for state-bearing marks.

## Section recipes

How recurring sections are built.

### First screen: Sculptural promise stage

**Observed:** A 58px sticky Navigation precedes a 900px dark stage within the 1280px container. The text occupies a narrow left column, inset an additional 64px; a two-line 96px serif title spans roughly one third of the viewport. A small announcement pill sits above; the 18px support paragraph is capped at 480px, followed by Primary button and Secondary action with a 16px gap. Opposite it, the 648×550px Black material sculpture occupies the right half. Layers run black canvas, dim floor and diagonal light, sculpture, then text and controls. The first 900px show the complete promise, support, actions and object, with ample dark space below; social proof starts after the opening.

**Transfer:** Default new landing pages retain the split promise/object tension. Without elaborate media, build a beveled extrusion of the new product's symbol on the same dark stage. Feature pages center a compact Feature emblem stage over display-secondary type; pricing opens directly with centered serif title and controls; sales pages pair a serif promise and concise proof rows with a form; company pages center an emblem and mission.

**Avoid:** Do not replace the stage with a full-bleed colorful gradient, a bright dashboard collage or a centered text-only hero on an ordinary landing page.

**Text style:** `display` — domaine 400 · 96px/1 · tracking -0.01em

### Heading and demonstration

**Observed:** Use 96px section padding, a small sculptural chapter emblem when present, a centered heading and 18px support line separated by 8px. Actions sit 32px later. A large framed working demonstration follows, often within the 1024px detail container.

**Transfer:** Give each chapter one operation and one visible output; alternate centered demonstration chapters with left-aligned paired capabilities.

**Text style:** `heading` — aBCFavorit 400 · 56px/1.2 · tracking -0.05em

### Paired illustrated capabilities

**Observed:** A left-aligned heading and support introduce a two-column grid with a 32px gap. Illustrated feature cards are about 600px wide; their upper media fades away before the icon, title, description and link.

**Transfer:** Pair related but distinct operations, giving each comparable visual weight.

**Text style:** `card-title` — aBCFavorit 400 · 20px/1.3

### Unboxed capability field

**Observed:** A broad left-aligned heading sits over a three-column, three-row field of small icons, 20px labels and 14px explanations. Columns have about 80px separation; generous row spacing replaces filled boxes.

**Transfer:** Use this treatment for breadth after the main demonstrations, not for the primary promise.

### Evidence interlude

**Observed:** Standalone quotes use 24px medium text centered in a 520px measure, with small attribution below. The alternate Quote card rail uses 450px cards at 32px gaps, runs beyond viewport edges and fades toward black.

**Transfer:** Let one credible voice interrupt the technical chapters; choose either intimate centered proof or a broad moving rail.

**Text style:** `quote` — inter 500 · 24px/1.5

### Metric triptych

**Observed:** Three equal columns within 1024px use right-hand hairline dividers, 40px horizontal inset and 36px top/48px bottom padding. Each has a small label, a 48px metric and muted explanation. A dotted background fades toward the center and boundaries.

**Transfer:** Use distinct, verifiable measures; retain neutral silver numerals instead of chart-like accent colors.

**Text style:** `stat` — aBCFavorit 400 · 48px/1

### Commercial comparison

**Observed:** A centered 76.8px serif utility title precedes segmented controls and a restrained quota slider. Four Plan cards follow. Detailed comparisons narrow to 1024px, use 36px section headings, 44px rows and a subdued 36px tier-header strip; all options remain aligned.

**Transfer:** Adapt the number of options to actual choices; maintain factual row labels and equally legible columns.

### Sales proof and conversion

**Observed:** A split serif-and-form opening leads to metrics, a monochrome line chart with an italic 14px caption, compliance medallions, Story panels, an instructional video and Capability cards. The closing form centers beneath a 56px title with 128px section padding.

**Transfer:** Replace technical proof with the new audience's real risk reducers. Keep the same form language at opening and closing.

### Company editorial chapters

**Observed:** A narrow 480px origin story follows the emblem-led serif opening. Centered 36px chapter titles introduce wide natural-color photography; Authored window stack adds personal voice. A grayscale portrait directory, compact recruiting invitation and three-column article thumbnails lead into the shared footer.

**Transfer:** Preserve the alternation of narrow prose, human image and authored statement without requiring any particular company topic.

### Monumental closing

**Observed:** The default closing returns to a centered two-line 76.8px serif promise with a single Primary button 32px beneath. Monumental wordmark horizon bridges to the footer. Utility and feature variants instead use a small brand tile, a 56px sans title, support and signup action. Company variants end with recruiting and articles, while sales variants end with the inquiry form.

**Transfer:** Every new landing page needs the monumental typographic device somewhere in its closing composition; it can accompany a short promise rather than duplicate a long headline.

**Text style:** `display-secondary` — domaine 400 · 76.8px/1 · tracking -0.01em

### Utility footer

**Observed:** 144px vertical padding in the shared container; a separate identity/status column sits beside five link columns at 32px gaps. Small circular social buttons and a low-profile operational badge add useful details without competing with the closing promise.

**Transfer:** Scale the actual link taxonomy to the product while preserving the low contrast, small type and spacious closing field.

## Page flow

**Storyline:** Promise → credible adoption → working demonstrations → capability breadth → human proof → commitment → spacious utility ending.

### Broad product landing page

1. **Promise** — Split serif statement and dark material sculpture.
2. **Social proof** — Restrained monochrome customer-logo field.
3. **Product demonstration** — Integration code, editor and template-preview chapters interleaved with paired illustrated features.
4. **Capability breadth** — Unboxed icon field and a large dashboard with compact selectors.
5. **Human proof** — Centered quote and wide customer quote rail.
6. **Closing call** — Serif promise, action and giant low-contrast lettering above the shared footer.

**Transfer:** Move from one simple promise to tangible operations, then expand scope and close with a strong typographic impression.

### Self-serve commercial evaluation

1. **Pricing** — Compact centered serif opening, controls and equal-height plan cards.
2. **Expansion** — Usage-based cards and add-on explanations.
3. **Comparison** — Narrow, repeated ruled comparison tables grouped by concern.
4. **Objection handling** — Customer logos and question rows.
5. **Closing call** — Quote rail, centered signup invitation and utility footer.

**Transfer:** Favor comparable facts over a hard-sell highlighted tier; retain a warm final invitation.

### High-consideration sales conversion

1. **Promise and action** — Serif headline, three short proof rows and inquiry form.
2. **Quantified proof** — Neutral metric triptych and line-chart adoption proof.
3. **Risk reduction** — Compliance medallions and large colored customer stories.
4. **Implementation confidence** — Video, migration-oriented links and suite grid.
5. **Objection handling** — Compact question panels.
6. **Closing call** — Centered inquiry form and shared footer.

**Transfer:** Use proof to address implementation and trust before asking for the same contact details again.

### Focused feature explanation

1. **Promise** — Centered sculptural emblem, serif title and two actions.
2. **Product demonstration** — Large workflow canvas.
3. **Capability chapters** — Code-and-copy split, three capability cards and operational detail demonstration.
4. **Human proof** — Centered customer quote.
5. **Use cases** — Three selectors above a second workflow demonstration.
6. **Pricing and closing call** — Split free-start offer, centered signup block and utility footer.

**Transfer:** Show the feature operating before explaining its internal concepts; follow detail with recognizable use cases.

### Company credibility and affinity

1. **Mission** — Centered metal emblem and serif purpose statement.
2. **Origin** — Narrow prose and candid founder photograph.
3. **Point of view** — Authored window stack.
4. **Human proof** — Team photograph and grayscale supporter directory.
5. **Participation** — Recruiting invitation followed by three article previews.
6. **Ending** — Shared utility footer, without an extra product signup banner.

**Transfer:** Use real people and specific editorial statements to soften the technical visual world.

## Writing

Direct, builder-to-builder and quietly confident. Technical specificity is paired with human outcomes and occasional warm, immediate phrasing.

**Do not copy:** Do not reuse Resend's name, wordmark, artwork, customer identities, quotations, prices, metrics, certifications or performance claims. Source examples illustrate voice only; replace them with truthful product-specific content.

- **Addressing the reader:** Use you and your for the reader's work; we for the people building the product. Name concrete tools and operations without inflated abstraction.
- **Rhythm:** Short sentence-case headlines, usually 3–8 words, followed by one or two compact explanatory sentences. Action labels are brief verbs; urgency comes from immediacy rather than exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Product category plus audience, or a next-scale outcome. | 3–7 words | “Email for developers”<br>“Your next billion emails” |
| Capability heading | Plain active verb tied to a tangible result. | 3–8 words | “Write using a delightful editor”<br>“Trigger actions via custom events” |
| Supporting line | Explain what happens and why it helps, using concrete nouns. | 1–2 sentences | “Send emails based on custom event triggers. Build multi-step workflows powered by your data.” |
| Primary action | A direct, low-friction verb phrase. | 2–4 words | “Get started”<br>“Sign up for free” |
| Closing promise | A concise reframe followed by present-tense availability. | 4–7 words | “Email reimagined. Available today.”<br>“Start sending tonight” |
| Sales reassurance | Specify the useful next step rather than a generic sales process. | 1–2 sentences | “Tell us more about your company. We will come back with a migration plan, not a discovery call.” |

**Words and phrasing to use:** build; integrate; start; your; simple; in minutes; visibility; control; craft; without the friction

**Avoid:** revolutionary; synergy; game-changing; unlock limitless possibilities; excessive exclamation marks

**Rules:**

- Lead with the reader's work, then name the mechanism.
- Use actual technical terms when they make the claim testable.
- Keep a supporting paragraph narrower than its section headline.
- Write FAQs as questions a buyer would genuinely ask.
- Let a closing line feel immediate without inventing urgency or scarcity.

## Do's and Don'ts

### Do

- Keep the default stage black and make the object legible through grazing highlights.
- Set the main serif promise at 96px, weight 400 and -0.01em tracking.
- Preserve 56px regular grotesk headings with -0.05em tracking.
- Give major chapters 96px vertical padding and grids 32px gaps.
- Use 16px action corners and the translucent textured face, not flat bright pills.
- Let lower demonstration edges dissolve into the canvas.
- Include the oversized dark lettering device with an accessible closing heading.
- Keep pricing options equally weighted and their actions bottom-aligned.

### Don't

- Do not substitute dark navy for the absolute-black canvas.
- Do not make regular display headings semibold or bold to compensate for weak hierarchy.
- Do not apply purple to every heading; it is a localized word accent.
- Do not turn faint 1px cool outlines into luminous full-perimeter neon borders.
- Do not distribute orange and acid-yellow fills throughout ordinary capability sections; they are story-panel variants.
- Do not use the blue button inside a product preview as the marketing CTA style.
- Do not make every section a filled-card grid; retain unboxed capability fields and intimate proof interludes.
- Do not turn natural company photography monochrome merely because the rest of the page is dark.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare all-property transitions at 0.2s cubic-bezier(.4, 0, .2, 1); navigation and footer color transitions use 0.15s with the same curve.
- Customer proof rails declare scroll-x 180s linear infinite and pause on group hover.
- Hero text declares hero-text-slide-up-fade 1s ease-in-out; sculptural and interface media provide additional animated detail.

**Transfer:**

- Keep action inversion brisk and local; motion should reveal material or demonstrate an operation rather than bounce the entire layout.
- Use slow linear proof rails with hover pause when there are enough authentic quotes.

**Unknown:**

- Exact sculpture playback, scroll reveal triggers and media sequencing are not established.

### Responsive

**Observed:**

- Desktop hero uses a split row and left-aligned text; declared smaller-screen classes switch to a column and centered text.
- The main serif title declares 64px before the desktop 96px variant; section grotesk titles declare 48px before 56px.
- Feature pairs and plan grids declare single-column defaults; footer link groups declare two columns before five at larger widths.

**Transfer:**

- On narrow screens keep the promise and sculpture as separate readable blocks; avoid shrinking the whole desktop stage.
- Retain the dark material treatment and gradient fades while reducing demonstration complexity.
- Use the 48px section-padding variant and keep comparison data navigable rather than squeezing all columns into illegible text.

**Unknown:**

- Rendered mobile compositions, precise breakpoint-to-component mapping and touch interactions are not fully established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
