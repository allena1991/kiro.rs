# Cassette — pasted-up electric attitude

## Overview

A dark, tactile agency style with the energy of a record sleeve and a handmade street poster. Acid yellow lettering and tiny uppercase monospace copy sit against charcoal, while regular-weight grotesk headlines keep the tone conversational. Photographic cutouts, halftone portraits and abrupt candy-colored bands suit creative services and products with a strong human point of view; the composition alternates sparse theatrical space with compact informational detail.

### Essentials

- The identity is the main object: an extremely wide, heavy yellow wordmark spans 1402px of a 1440px canvas, only 125px tall, and returns at the ending. Use an original extended word graphic even when no product imagery exists.
- The promise floats rather than shouts: regular Apercu Pro at 60.5px/1.2, scaling at 4.2vw, is right-aligned opposite a small navigation cluster in a 900px opening with 19.2px edges.
- Navigation looks like yellow adhesive tabs: 12.5px uppercase mono text, 32px-high pills, 900px radii, 8px gaps, arranged in two compact rows beside a rotating emblem.
- Charcoal dominates the long page: #19181a with #f5f4f0 text; yellow #f0e226 belongs to identity and actions. Pink, blue, coral and green arrive as a concentrated full-width band stack, not scattered accents.
- Editorial content sits on the right half while physical collage occupies the left: a 32px column gap, 480px prose measure, 37.1px/1.2 regular headings and 12.5px/1.3 uppercase mono paragraphs.
- The page feels printed, not polished: fine grain over dark grounds and flat colors, halftone photography, torn paper and tape-like overlays. Every new page needs this tactile device; a single cutout photo over two distressed paper rectangles is the minimum fallback.
- The ending is another poster: a 56px/1.2 centered two-line statement above outlined yellow contact pills, low-contrast radial art behind it, and the monumental word graphic along the bottom.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#f0e226` | `--color-yellow` | accent, action, link, surface, border | Identity graphics, navigation pills, action text and borders, and the first capability band. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Poster blue | `#2896f3` | `--color-blue` | surface | One full-width capability band; vivid collage color family. |
| Poster green | `#0db55b` | `--color-green` | surface | One full-width capability band and collage accents. |
| Poster coral | `#ff8461` | `--color-coral` | surface | One full-width capability band. |
| Poster pink | `#fac4f0` | `--color-pink` | surface | One full-width capability band and collage paper. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Printed black | `#000000` | `--color-ink` | text, accent | Text and solid icons on colored bands; navigation text. |
| Charcoal canvas | `#19181a` | `--color-canvas` | background, text | Dominant page ground and dark text on light labels and yellow actions. |
| Dark rule | `#272727` | `--color-rule` | border, surface | Subtle grid and accordion separators; navigation hover fill. |
| Muted cream | `#d9d7ce` | `--color-muted` | text | Small footer credit, subordinate to warm-white content. |
| Warm white paper | `#f5f4f0` | `--color-paper` | text, surface | Headings and copy on charcoal; small rectangular section labels. |

## Typography

- **Apercu Pro** — Headlines and names in information rows. Open, approachable grotesk with simple shapes; regular weight rather than a heavy display cut. If unavailable, use **DM Sans**. Use 400 for headings and names; preserve the relaxed line height. Font stack: "Apercu Pro", "DM Sans", Arial, sans-serif.
- **Apercu Mono Pro** — Body paragraphs, labels, navigation and actions. Compact monospaced lettering used like typeset liner notes, predominantly uppercase. If unavailable, use **IBM Plex Mono**. Use 400, with normal tracking. Font stack: "Apercu Mono Pro", "IBM Plex Mono", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Apercu Pro | 400 | 60.5px | 1.2 | normal | size 4.2vw | Right-aligned opening promise. |
| closing | Apercu Pro | 400 | 56px | 1.2 | normal | fixed | Centered closing statement. |
| heading | Apercu Pro | 400 | 37.1px | 1.2 | normal | fixed | Section leads and titles on colored bands. |
| row-label | Apercu Pro | 400 | 15px | 1.083 | normal | fixed | Names and role labels in expandable information lists. |
| mono-copy | Apercu Mono Pro | 400 | 12.5px | 1.3 | normal, uppercase | fixed | Body paragraphs, section labels, contact actions and capability support lines. |
| navigation | Apercu Mono Pro | 400 | 12.5px | 1 | normal, uppercase | fixed | Compact filled navigation tabs. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the distinction between light conversational headings and dense uppercase mono detail. Weight 400 and normal tracking are the default across both families.
- The monumental identity is vector artwork, not the ordinary heading face. Its very heavy extended letterforms must remain visually separate from the regular-weight promise.

## Layout

**Density:** Airy at section scale, compact at text and control scale: large dark fields surround tiny liner-note copy.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Navigation gaps, icon-to-label gaps and band heading-to-copy gap. |
| 12px | Wrapped contact action gaps. |
| 19.2px | Opening and closing side margins. |
| 24px | Section-label top inset and information-grid gaps. |
| 32px | Primary column gap, capability band top and left padding, and heading-to-proof-grid spacing. |
| 35.2px | Space above and below explanatory prose and above accordion lists. |
| 48px | Closing statement to contact cluster. |
| 64px | Capability band bottom padding before overlap. |
| 192px | Dark breathing space below the proof grid. |

### Containers and grids

- **Full-width poster**: max width 1440px · side padding 19.2px. Opening and ending identity graphics stretch almost edge to edge; backgrounds bleed fully.
- **Editorial split**: 2 columns · gap 32px. Equal underlying halves with collage on the left and copy on the right; artwork can be narrower than its half.
- **Prose measure**: max width 480px. Explanatory copy and its heading align to the start of the right half.
- **Proof matrix**: 4 columns · gap 0px. Edge-to-edge logo matrix; desktop cells are 360px wide by 150px tall.

## Corner radius

| Element | Radius |
| --- | --- |
| Pills | 900px |
| Paper and bands | 0px |

## Surfaces and depth

### Surfaces

#### Printed charcoal · level 0

**Use:** Continuous dark ground.

**CSS:** `background-color: #19181a; color: #f5f4f0`

**Observed:** Fine dust, rubbed edges and subtle scratches interrupt the otherwise flat charcoal.

**Transfer:** Use the Grain overlay above this ground; keep contrast subordinate to text.

#### Paper label · level 1

**Use:** Small pasted section markers.

**CSS:** `background-color: #f5f4f0; color: #19181a; border-radius: 0px`

**Observed:** Each short line has its own tight rectangular backing; stacked lines have unequal widths.

**Transfer:** Keep tags content-sized rather than stretching them into a badge.

#### Colored poster band · level 1

**Use:** Concentrated capability chapter.

**CSS:** `background-color: #f0e226; color: #000000; border-radius: 0px; box-shadow: none`

**Observed:** Flat yellow, blue, pink, coral and green strips touch or overlap; grain unifies them with the dark page.

**Transfer:** Use these colors as a single compact chapter of full-bleed strips, not as the page's default ground.

## Components

### Navigation cluster

**Use:** Persistent anchor navigation.

**CSS:** `display: flex; max-width: 385.4px; gap: 32px`

**Observed:** A roughly 67px emblem sits beside two wrapped rows of pills with 8px gaps. It starts beside the hero promise, then stays at the upper left during later sections.

**Transfer:** Use an original simple emblem and short section names.

### Navigation pill

**Use:** Section anchors in the navigation cluster.

**CSS:** `display: flex; align-items: center; justify-content: center; background-color: #f0e226; color: #000000; border-radius: 900px; padding: 10px 13px 9px; height: 32px; box-sizing: border-box`

**Text style:** `navigation` — Apercu Mono Pro 400 · 12.5px/1 · uppercase

**Observed:** Content-sized pills form a compact two-row grouping rather than a conventional top navigation bar.

**States:** Declared: hover background-color #272727 and color #f0e226; active outline 0px. Transition 0.2s.

### Filled action

**Use:** Secondary narrative conversion beneath explanatory copy.

**CSS:** `display: flex; background-color: #f0e226; color: #19181a; border: 1px solid #f0e226; border-radius: 900px; padding: 8.8px 13px`

**Text style:** `mono-copy` — Apercu Mono Pro 400 · 12.5px/1.3 · uppercase

**Observed:** A small content-width action ends the right-hand prose column.

**States:** Declared: hover color #f0e226 and background-color rgba(240, 226, 38, 0); active outline 0px. Transition 0.2s.

### Outline contact pill

**Use:** Direct contact and external destinations in the ending.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #f0e226; border: 1px solid #f0e226; border-radius: 900px; padding: 10px 13px 9px`

**Text style:** `mono-copy` — Apercu Mono Pro 400 · 12.5px/1.3 · uppercase

**Observed:** Text precedes a tiny northeast arrow. A centered wrapped group places direct contact above social destinations.

**States:** Declared: hover color #19181a and background-color #f0e226; active outline 0px. Transition 0.2s.

### Section label

**Use:** Editorial chapter markers.

**CSS:** `background-color: #f5f4f0; color: #19181a; padding: 4px 4.8px`

**Text style:** `mono-copy` — Apercu Mono Pro 400 · 12.5px/1.3 · uppercase

**Observed:** One or two short lines sit on separate paper rectangles at the beginning of the right column.

### Proof cell

**Use:** Social proof in a continuous matrix.

**CSS:** `display: flex; justify-content: center; align-items: center; border: 1px solid #272727; padding: 22.4px 44.8px; height: 150px; box-sizing: border-box`

**Observed:** Restrained cream monochrome logos sit at varied intrinsic sizes in equal cells; the grid has no gutters.

**Transfer:** Use real authorized proof marks, maintaining visual rather than identical numerical size.

### Expandable information row

**Use:** People or other compact expert detail lists.

**CSS:** `border-bottom: 1px solid #272727`

**Text style:** `row-label` — Apercu Pro 400 · 15px/1.083

**Observed:** A 674px-wide list has approximately 46px collapsed rows. Each row pairs a yellow circular arrow plus a name on the left with a role on the right. The open row exposes uppercase mono detail beneath; the arrow points down and fills yellow.

**Transfer:** Use this for meaningful details that can expand, keeping the header in two columns.

### Capability band

**Use:** A concise benefit or service in the colored chapter.

**CSS:** `display: flex; position: relative; justify-content: space-between; align-items: flex-start; background-color: #f0e226; padding: 32px 0px 64px 32px; margin-bottom: -32px; overflow: hidden`

**Text style:** `heading` — Apercu Pro 400 · 37.1px/1.2

**Observed:** A small black symbol anchors the far left; title and uppercase support align at the right-half start. Bands are 156–172px high before their overlap. Successive variants use blue, pink, coral and green.

**Transfer:** Give each strip one distinct benefit and a single short support line.

### Monumental word graphic

**Use:** Identity bookend at opening and ending.

**CSS:** `display: flex; overflow: hidden`

**Observed:** An extended, ultra-heavy uppercase SVG fills 1402×125px on desktop, rendered in acid yellow with dark printed speckles.

**Transfer:** Create original extended lettering fitted to nearly the full width, preserving the low, wide silhouette instead of imitating the letter shapes.

## Imagery and graphics

### Grain overlay

**Use:** Required tactile continuity across dark grounds, identity and flat color.

**Observed:** Fine black flecks in yellow areas and faint pale scratches on charcoal create an aged printed surface, with slightly stronger wear near edges.

**Transfer:** Keep it fine enough that tiny mono text remains readable.

**Build:** Make a transparent SVG texture using feTurbulence fractalNoise with baseFrequency 0.75 and 3 octaves. Use feColorMatrix to produce a low-opacity monochrome mask, then layer at roughly 0.06 opacity over dark surfaces and 0.12 over flat paper. Add sparse 1px broken strokes near the perimeter. These are construction settings; tune the texture to remain barely perceptible.

### Pasted photographic collage

**Use:** Required editorial image language alongside explanation; portraits use the same method.

**Observed:** A hand holding a transparent cassette against bright blue sky is a hard rectangular image on the left, overlapped by pink halftone paper, a green strip, yellow typography and small tape scraps. The people chapter uses a large black-and-white halftone portrait with vertical blue name tape, translucent yellow marks and torn white strokes. Neither uses rounded image cards.

**Transfer:** Choose a physical gesture or person related to the new product. Minimum version: one high-contrast cutout photograph, two flat distressed paper blocks and a narrow original text strip, anchored to the left edge.

**Build:** Place the main image at about 37–41% of desktop width. Layer square-edged paper rectangles behind and below it in pink, yellow or blue; rotate a narrow strip slightly and use an irregular SVG clipPath for one torn edge. Convert portraits to grayscale and overlay a 2px halftone dot pattern with multiply blending; finish with Grain overlay.

### Dark radial ending

**Use:** Atmospheric backing for the closing call.

**Observed:** Broad, almost-black curved radial ribs fan across the full ending behind the centered message. Contrast is extremely low; the lettering and yellow identity remain dominant.

**Transfer:** Use abstract dimensional rhythm rather than a literal product illustration.

**Build:** Create an oversized SVG centered behind the closing message. Draw 10–14 broad curved tapered ribs radiating from above center to the lower edges, using black at 0.12–0.22 alpha over charcoal. Clip to the 900px section and apply the Grain overlay. Exact rib shapes are not essential.

### Icons

**Observed:** Tiny 1px-stroke arrows use yellow, about 11×12px in contact pills and 14×12px in list controls. Circular list controls are 24px across. Capability symbols are solid black silhouettes with a maximum dimension near 32px. The navigation emblem is a chunky irregular star-like shape.

**Transfer:** Use simple solid, slightly idiosyncratic pictograms for benefits and thin arrows for action. Keep these two languages separate; create an original navigation emblem.

## Section recipes

How recurring sections are built.

### First screen: Identity poster opening

**Observed:** A full 900px dark printed stage with 19.2px edge padding. The top is dominated by a low, wide yellow Monumental word graphic spanning almost the full width, with four tiny mono location labels spread beneath it. Around the upper-middle, Navigation cluster occupies the left while the 60.5px regular-weight promise sits on the right in a single right-aligned line. Layers run from charcoal and Grain overlay to identity, metadata, navigation and promise. The lower half remains mostly open with a small distressed yellow strip near the lower left. The first 900px contains the whole identity, navigation and headline, with no support paragraph, product mockup or conversion form; editorial explanation begins below.

**Transfer:** Use a new full-width original word graphic and a short promise that can sit comfortably on the right half. The identity itself is the main object when no product media exists. More informational page types can use the same poster header with a more specific promise and move detail immediately below it.

**Avoid:** Do not turn this into a centered headline, paragraph, two large buttons and floating device mockup; do not fill the open lower area with invented content.

**Text style:** `display` — Apercu Pro 400 · 60.5px/1.2

### Collage and editorial explanation

**Observed:** Editorial split places Pasted photographic collage against the left edge and Section label above the right column. A 37.1px heading leads into a 480px mono prose block with 35.2px top and bottom space, followed by Filled action.

**Transfer:** Explain the product's point of view using a tactile physical metaphor and short readable paragraphs.

**Text style:** `heading` — Apercu Pro 400 · 37.1px/1.2

### Proof matrix chapter

**Observed:** A small right-half Section label precedes a left-aligned heading spanning the page. Proof cells form a four-column matrix with no gutters, 32px beneath the heading, with ample dark space below.

**Transfer:** Use verified customer, partner or publication marks; keep proof modest and monochrome.

**Text style:** `heading` — Apercu Pro 400 · 37.1px/1.2

### People and expandable detail

**Observed:** A large left portrait collage sits opposite a multi-line heading and Expandable information rows on the right. One open detail uses a two-column name/detail structure while other rows remain compact.

**Transfer:** Use for experts, process stages or other topics where short headers can reveal deeper context.

**Text style:** `heading` — Apercu Pro 400 · 37.1px/1.2

### Bright capability chapter

**Observed:** A dark introductory area uses Section label and a right-half heading; beneath it a full-width stack of Capability bands sharply interrupts the charcoal. Yellow, blue, pink, coral and green strips keep titles aligned to the same right-half column while icons sit far left.

**Transfer:** Concentrate several concrete benefits into this poster-like chapter. Adapt the number of strips to the content, retaining the shared alignment and abrupt color changes.

**Text style:** `heading` — Apercu Pro 400 · 37.1px/1.2

### Poster closing call

**Observed:** A 900px ending uses Dark radial ending behind a centered 56px two-line statement. Outline contact pills wrap in two centered rows 48px below it. Navigation remains upper-left; a small Section label sits above the message. Monumental word graphic fills the bottom width, with a tiny copyright at left and muted credit at right beneath it.

**Transfer:** End with a strong experiential promise and direct next steps, not a conventional sitemap. Keep the identity bookend and atmospheric backing even if there are fewer contact destinations.

**Text style:** `closing` — Apercu Pro 400 · 56px/1.2

## Page flow

**Storyline:** Identity-led promise → point of view → credible proof → human expertise → concrete capabilities → direct invitation.

### A creative-service landing page that makes a strong identity feel human and credible

1. **Promise** — Sparse identity poster with a right-aligned one-line promise.
2. **Point of view** — Left collage and right editorial statement with compact mono prose.
3. **Social proof** — Full-width ruled matrix of monochrome marks.
4. **Human expertise** — Halftone portrait opposite expandable people details.
5. **Capabilities** — Abrupt stack of bright full-width benefit bands.
6. **Closing call** — Centered statement and contact pills above a repeated monumental identity.

**Transfer:** Use the narrative functions that fit the new product; preserve the identity bookends, tactile imagery and concentrated color chapter without treating this sequence as a fixed template.

## Writing

Confident, human and culturally fluent, with the tone of a creative who knows the work. Short contrasts and occasional colloquial bite replace corporate qualification.

**Do not copy:** Do not reuse Cassette's name, wordmark, emblem, customer marks, people, contact details, claims, biographies or original collage assets. Examples illustrate voice, not reusable claims.

- **Addressing the reader:** Speak as we to you; tie the offer to your space or experience rather than describing abstract market categories.
- **Rhythm:** Brief, sentence-case headlines sit above dense uppercase support. Mix punchy paired sentences with compact explanatory paragraphs; capability lines are often only one sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short sensory benefit addressed directly to the reader. | 4–8 words | “Sound that speaks for you.” |
| Point of view | Contrast the default approach with a confident human alternative. | Two short sentences | “Algorithms play it safe. We play it right.” |
| Capability support | A practical reassurance in plain language, sometimes with a dry aside. | 5–16 words | “Legit for business. No legal headaches.”<br>“Proprietary tech, built to sound incredible. Reliable, seamless, and smooth as hell.” |
| Action | Short direct phrase or literal contact destination. | 2–5 words | “WHY WE DO IT” |
| Closing statement | Connect the product's medium to the reader's broader experience. | 7–12 words | “The experience starts with what people hear.” |

**Words and phrasing to use:** handcrafted; shaped by humans; set the tone; your space; built to; we tweak, refine, repeat

**Avoid:** revolutionary platform; unlock synergies; AI-powered everything; best-in-class solutions; corporate superlatives without proof

**Rules:**

- Use specific verbs about what the work changes for people.
- Let the headline sound spoken; uppercase is a visual treatment for detail, not a reason to shout.
- Keep benefit titles concrete and put the practical reassurance directly beneath them.

## Do's and Don'ts

### Do

- Keep the main canvas charcoal and text warm white, reserving pure black for light grounds.
- Keep ordinary headlines at weight 400 and normal tracking.
- Use 12.5px uppercase mono for prose, tags and controls, with 1.3 line height except navigation.
- Align editorial titles and band copy to the same right-half edge.
- Use 1px #272727 rules for matrices and expanding lists.
- Repeat the original wide yellow identity graphic at the end.
- Retain 8px internal control gaps and 48px between the closing line and actions.

### Don't

- Do not turn ordinary headings into the ultra-heavy identity lettering; they are separate typographic voices.
- Do not replace warm white #f5f4f0 with stark white throughout the dark page.
- Do not distribute all five band colors across random buttons or navigation.
- Do not put rounded corners on photographic collages or proof cells; pills alone carry the soft shape.
- Do not add raised-card shadows, glossy gradients or glass panels.
- Do not enlarge body paragraphs into conventional 18px mixed-case SaaS copy.
- Do not use uniform outline icon sets for the bold black capability symbols.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.2s transitions.
- The emblem has a rotate-left animation declared at 8s linear, repeating infinitely.
- Navigation remains visible at the upper left through later sections; sections use pinned/overlapping presentation.

**Transfer:**

- Keep the emblem rotation as the small recurring kinetic gesture, not a page-wide spectacle.
- Use the declared color inversions on yellow pills to make small controls legible as interactive.

**Unknown:**

- Exact scroll choreography, accordion animation timing and transition easing beyond the declared values are unknown.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 768px, 991px and 1195px.
- The opening headline uses 4.2vw at desktop.

**Transfer:**

- On narrow layouts, preserve the wide identity silhouette while stacking collage and editorial text; keep a compact pill cluster rather than replacing it with a generic full-width navigation bar.
- Reduce the proof matrix column count and let contact pills wrap, preserving square cells and tiny mono labeling.

**Unknown:**

- Narrow-screen layouts and exact breakpoint-specific sizes are not established; the stacking behavior is guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
