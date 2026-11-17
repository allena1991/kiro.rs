# Serro — software as instrument panel

## Overview

An industrial dark style with soft-edged grotesk lettering and the markings of technical equipment. Warm white and putty text sit on charcoal, punctuated by practical blue rather than atmospheric gradients. Detailed software views, fine vertical linework, pixel lettering and oversized typographic plates give complex products a tangible, operational character. The pacing alternates spacious declarations with dense evidence.

### Essentials

- Soft lettering carries hard operational claims: medium-weight grotesk headings use -0.03em tracking, with 72px section titles, 104px chapter statements and 140px proof headlines.
- The opening is a centered product name, not an illustration-led billboard: a symbol and short title occupy roughly 841px together, followed by 24px support, a 60px pause and two 326×66px actions; a software window begins within the first 900px.
- Actions look like equipment controls: square corners, broad 18px 94px padding and 24px/1.25 medium labels; blue fill marks the primary action and a fine light outline marks its companion.
- Color behaves like a signal on a mostly neutral instrument: #272727 canvas, #303030 chapters and #faf9f5 text dominate; #3e77e8 appears in short labels, actions and one concentrated proof plate rather than whole-page washes.
- Software is staged as physical evidence: dark rectangular interfaces overlap offset #3f3f3e caption plates, with serial numbers, blue mono labels and circular fastener-like details.
- Fine vertical line fields and pixel-line lettering connect the page: retain both a ruled technical graphic and a monumental low-contrast closing word sculpture. If no product artwork exists, construct the linework in SVG and use a simplified real workflow panel.
- Proof becomes a bolted-on sign: a 164px/0.8 statistic sits in a blue rectangular plate with four 20px charcoal corner dots, accompanied by mono annotations and ruler-like ticks.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal blue | `#3e77e8` | `--color-blue` | text, accent, action, link, surface | Primary buttons, technical labels, pixel accents and the large proof plate. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep charcoal | `#202020` | `--color-closing-ground` | background | Closing conversion stage. |
| Warm graphite | `#262624` | `--color-case-ground` | background | Editorial audience matrix backing. |
| Charcoal canvas | `#272727` | `--color-canvas` | background, text | Default page ground and dark text on the blue proof plate. |
| Raised charcoal | `#303030` | `--color-chapter` | background, surface | Broad capability chapters and product staging. |
| Graphite plate | `#3f3f3e` | `--color-plate` | surface | Offset feature caption backing. |
| Muted rule | `#565655` | `--color-rule` | border | Visible 50% equipment gray over raised charcoal; rgba(124,123,119,0.5) is the construction. |
| Equipment gray | `#7c7b77` | `--color-muted` | text, accent | Serial numbers, minor copy, ticks and inactive pixel lettering. |
| Dim white | `#a9a9a6` | `--color-soft-text` | text | Visible 60% warm white over raised charcoal, using rgba(250,249,245,0.6). |
| Putty | `#dcd5ca` | `--color-support` | text | Supporting paragraphs and mono annotations. |
| Warm white | `#faf9f5` | `--color-text` | text, border | Headings, action labels and visible fine outlines. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Interface black | `#1f1f1f` | `--color-product-ground` | background | Dark software windows, separate from the marketing canvas. |
| Interface edge | `#454545` | `--color-product-edge` | border | Visible white at 14% over charcoal; software-window edge and technical line fields. |

## Typography

- **Restart Soft** — Product titles, section headings, paragraphs and action labels. Soft geometric grotesk with broad round bowls, compact spacing and a blunt, friendly texture. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **DM Sans**. Use 400 and 500; preserve tight display tracking and open body leading. Font stack: "Restart Soft", "DM Sans", Arial, sans-serif.
- **Proto Mono** — Technical labels, captions, serials and equipment-like annotations. Mechanical monospaced letters with distinctive squared construction; predominantly semibold. If unavailable, use **Space Mono**. Use 700 for the semibold marking role. Font stack: "Proto Mono", "Space Mono", ui-monospace, monospace.
- **Geist Pixel Line** — Short technical display words and start/end markers. Letterforms drawn as fine horizontal digital lines rather than solid strokes. Font stack: "Geist Pixel Line", monospace.
- **Inter** (only for product demonstrations) — Software interface text only. Compact neutral interface sans, visually distinct from the soft marketing type. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | Restart Soft | 400 | 164px | 0.8 | -0.03em | Oversized numeral on the blue proof plate. |
| matrix-display | Restart Soft | 500 | 160px | 1 | -0.03em | Oversized two-line introduction to the audience matrix. |
| display | Restart Soft | 500 | 140px | 0.9 | -0.03em | Large benefit or quantified-proof statement. |
| chapter | Restart Soft | 500 | 104px | 0.9 | -0.03em | Major chapter declaration; centered or flush left. |
| pixel-milestone | Geist Pixel Line | 400 | 100px | 0.9 | -0.03em | Start and outcome markers on the ruled proof graphic. |
| closing-heading | Restart Soft | 500 | 100px | 0.9 | -0.03em | Centered closing conversion statement. |
| pixel-marker | Geist Pixel Line | 400 | 80px | 0.9 | -0.03em | Short serial-like marker or rotated edge title. |
| heading | Restart Soft | 500 | 72px | 0.9 | -0.03em | Default capability section heading. |
| explanation-heading | Restart Soft | 500 | 72px | 1.08 | -0.03em | Multi-line problem statement alongside an explanatory graphic. |
| footer-link | Restart Soft | 500 | 56px | 0.9 | -0.03em | Large indexed navigation in the footer. |
| matrix-heading | Restart Soft | 500 | 40px | 1.1 | -0.02em | Outcome statements within audience rows. |
| card-title | Restart Soft | 500 | 32px | 1.2 | -0.03em | Feature caption plates and process-column titles. |
| body | Restart Soft | 400 | 24px | 1.5 | -0.02em | Hero support and major section introductions. |
| action | Restart Soft | 500 | 24px | 1.25 | normal | Main filled and outlined actions. |
| eyebrow | Proto Mono | 600 | 20px | 1 | -0.03em | Short section identifiers, visually set as technical markings. |
| body-small | Restart Soft | 400 | 20px | 1.5 | -0.02em | Process descriptions and muted footer positioning copy. |
| matrix-body | Restart Soft | 400 | 20px | 1.5 | normal | Explanatory right-hand column in audience rows. |
| navigation | Restart Soft | 500 | 16px | 1.5 | -0.02em | Compact fixed-header navigation. |

**Notes:**

- The soft sans has only a modest weight contrast: regular paragraphs and medium titles. Scale, tight tracking and compressed heading leading create the hierarchy.
- Use -0.03em throughout large headings, -0.02em for body and small navigation, and normal tracking for action labels.
- The opening title is a compact one-line category name with a symbol, visually about 128px at desktop; fit its combined block to roughly 841px rather than turning the longer proof headline into the hero.
- Mono identifiers read as uppercase equipment labels, while sentence-case headlines remain fluid and human. Pixel lettering is reserved for short codes, not full explanations.

## Layout

**Density:** Airy at chapter scale, dense within the software and equipment markings; long pauses frame emphatic text and compact proof.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight internal feature-label stacks. |
| 16px | Process title-to-description gap and compact footer link spacing. |
| 20px | Paired action gap. |
| 30px | Feature-grid gutters and plate left inset. |
| 32px | Eyebrow-to-heading gap. |
| 40px | Main side gutter, heading-to-support gap and footer column insets. |
| 60px | Opening support-to-action pause. |
| 80px | Chapter subgroups and footer vertical padding. |
| 96px | Large content-stack separation. |
| 100px | Centered chapter padding and heading-to-feature-grid pause. |
| 140px | Capability chapter top padding. |
| 160px | Problem section padding and conceptual chapter top padding. |
| 200px | Large transition into the audience chapter. |

### Containers and grids

- **marketing container**: max width 1720px · side padding 40px. Centered full marketing content; at 1440px the active width is 1360px.
- **split chapter**: 2 columns · gap 40px. Equal text and graphic columns, about 660px each at desktop.
- **feature grid**: 2 columns · gap 30px. Two-by-two compositions, each approximately 665×365px, pairing software art with a caption plate.
- **process rail**: max width 1800px · 4 columns · gap 0px. Full-width process columns divided by hairlines, each with 32px side padding.
- **centered statement**: max width 1200px · side padding 40px. Centered two-line chapter statement.
- **closing content**: max width 856px · side padding 40px. Centered final promise, short supporting paragraph and paired actions.
- **footer grid**: max width 1720px · 3 columns · gap 0px · side padding 40px. Brand context, indexed large navigation, then utility/contact material; use vertical dividing rules.

## Corner radius

| Element | Radius |
| --- | --- |
| marketing controls and plates | 0px |
| fastener details | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| software window | `0px 0px 0px 1px rgba(255,255,255,0.14), 0px 24px 60px 0px rgba(0,0,0,0.35)` | Only the large staged software window, not every marketing card. |

### Surfaces

#### Canvas · level 0

**Use:** Default page surface.

**CSS:** `background: #272727; color: #faf9f5`

#### Capability band · level 0

**Use:** Long technical chapters.

**CSS:** `background: #303030; border-top: 1px solid rgba(124,123,119,0.5); border-bottom: 1px solid rgba(124,123,119,0.5)`

**Observed:** The shift is subtle; sections remain matte and almost monochrome.

**Transfer:** Use broad bands to group related proof without introducing a different visual theme.

#### Caption plate · level 1

**Use:** Backing for numbered features.

**CSS:** `background: #3f3f3e; border-radius: 0px`

**Observed:** Offset behind the software artwork with circular fastener details at the far edge.

**Transfer:** Keep it flat and mechanically aligned rather than floating like a dashboard tile.

#### Signal plate · level 1

**Use:** Concentrated measurable proof.

**CSS:** `background: #3e77e8; color: #272727; border-radius: 0px`

**Observed:** The most forceful chromatic area is a horizontal sign carrying one giant result.

**Transfer:** Give a single substantiated result this treatment.

#### Audience ground · level 0

**Use:** Large type with ruled audience rows.

**CSS:** `background: #262624`

#### Closing stage · level 0

**Use:** Final conversion region.

**CSS:** `background: #202020; padding: 128px 40px 148px; overflow: hidden`

#### Software stage · level 1

**Use:** Large workflow demonstration.

**CSS:** `background: #303030; padding: 56px 24px; border-top: 1px solid rgba(124,123,119,0.5); border-bottom: 1px solid rgba(124,123,119,0.5)`

**Observed:** A centered desktop application is framed by a thin edge and deep shadow; fine vertical linework continues in the side margins.

**Transfer:** Present a coherent workflow window, not a collage of unrelated mini-cards.

## Components

### Fixed navigation

**Use:** Persistent orientation and compact conversion.

**CSS:** `position: fixed; top: 0px; height: 69px; width: 100%; z-index: 10; background: #272727`

**Text style:** `navigation` — Restart Soft 500 · 16px/1.5 · tracking -0.02em

**Observed:** Brand lockup on the left, central links separated by solid gray dots, sign-in and a thin blue-outlined demo action on the right; a fine bottom rule spans the bar.

**States:** Declared: hover changes navigation link text to #3e77e8; focus-visible is unknown.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #3e77e8; color: #faf9f5; border-radius: 0px; padding: 18px 94px; height: 66px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Restart Soft 500 · 24px/1.25

**Observed:** Plain centered label with no leading icon. Equal-width paired actions in the opening and closing; standalone variants stretch across the content width.

**Transfer:** Keep the wide, shallow rectangular silhouette and a short verb-led label.

### Secondary button

**Use:** Companion access action and full-width early-access link.

**CSS:** `background: #272727; color: #faf9f5; border: 1px solid #faf9f5; border-radius: 0px; padding: 18px 94px; height: 66px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Restart Soft 500 · 24px/1.25

**Observed:** Visually outlined on all four sides; the opening pair uses the same dimensions and emphasis in typography as the filled action.

### Feature assembly

**Use:** Pair one concrete capability demonstration with a numbered caption.

**CSS:** `display: flex; position: relative; overflow: hidden; height: 365px`

**Text style:** `card-title` — Restart Soft 500 · 32px/1.2 · tracking -0.03em

**Observed:** Software art occupies the left half and starts above the caption surface. The right plate begins 50px lower and carries a muted serial, blue mono label, then the soft sans title. A same-color plate extends behind the art.

**Transfer:** Use a small readable workflow, object diagram or data panel rather than a generic illustration.

### Feature caption

**Use:** Text half of the feature assembly.

**CSS:** `background: #3f3f3e; padding: 40px 48px 30px 30px; margin-top: 50px; display: flex; flex-direction: column; gap: 10px`

**Text style:** `card-title` — Restart Soft 500 · 32px/1.2 · tracking -0.03em

**Observed:** The sequence number is detached near the top; the label and title sit lower, while circular dark details align along the far edge.

### Process column

**Use:** Explain a mechanism in a connected rail.

**CSS:** `padding: 40px 32px 56px; border-left: 1px solid rgba(124,123,119,0.5); display: flex; flex-direction: column`

**Text style:** `card-title` — Restart Soft 500 · 32px/1.2 · tracking -0.03em

**Observed:** Four equal-width columns share top and bottom rules. A small visual or diagram sits above a title and short dim-white explanation.

**Transfer:** Make each column a step in one mechanism, not an unrelated feature list.

### Proof plate

**Use:** Emphasize one measurable outcome.

**CSS:** `background: #3e77e8; color: #272727; padding: 28px 20px; display: flex; gap: 30px; position: relative`

**Text style:** `stat` — Restart Soft 400 · 164px/0.8 · tracking -0.03em

**Observed:** Huge numeral at left, tiny mono descriptor toward the top right and four circular corner dots. The plate rests at the end of a vertical ruled graphic.

**Transfer:** Use a true product result; adjust the numeral width while retaining the sign-like proportion.

### Audience row

**Use:** Translate capabilities into outcomes for different readers.

**CSS:** `border-top: 1px solid rgba(255,255,255,0.1); padding: 30px 0px 80px`

**Text style:** `matrix-heading` — Restart Soft 500 · 40px/1.1 · tracking -0.02em

**Observed:** A serial and large abbreviated audience label occupy the left zone, a blue uppercase role label and outcome occupy the center, and supporting copy occupies the right. A small gray dot terminates the row.

**Transfer:** Use audiences, workflows or responsibilities appropriate to the new product.

### Indexed footer link

**Use:** Large navigational anchors at the page ending.

**CSS:** `color: #faf9f5; display: flex; justify-content: space-between; padding-bottom: 16px; text-decoration: none`

**Text style:** `footer-link` — Restart Soft 500 · 56px/0.9 · tracking -0.03em

**Observed:** Large soft-sans links stack between rules; small muted mono numerals are right aligned.

**States:** Declared: hover changes large footer link text to #7c7b77; focus-visible is unknown.

## Imagery and graphics

### Working software evidence

**Use:** Primary demonstration below the opening and smaller capability compositions.

**Observed:** A large dark desktop application shows navigation, a schedule, connected work and an assistant panel. Thin neutral edges, dense small text and restrained status colors make it feel usable rather than glossy. Capability views are smaller black rectangular fragments on offset gray plates. There is no lifestyle photography.

**Transfer:** Use a real coherent workflow with a few legible signals. The minimum version is a simplified interface showing one input, an evolving state and a useful output; retain dark chrome and fine rules.

### Ruled instrument graphics

**Use:** Technical chapter transitions, explanatory graphics and measurable proof.

**Observed:** Fine vertical gray lines form fields, ticks and rails. A problem graphic uses thin rising white, blue and gray curves; the proof graphic uses tall rails, small slider-like rectangles, start/end pixel markers and a bright outcome sign.

**Transfer:** Keep a ruled graphic as a signature device, adapting curves and rails to an actual product mechanism.

**Build:** Use an SVG with 1px vertical strokes in rgba(124,123,119,0.5) at roughly 10px intervals for dense fields; use fewer widely spaced rails for the proof. Draw three thin cubic curves with small arrowheads in warm white, signal blue and gray. Place tiny mono legends beside their origins. Add short solid gray slider rectangles on selected rails, a horizontal tick strip below, and the Signal plate at the outcome.

### Monumental ruled word sculpture

**Use:** Closing brand artwork below the functional footer.

**Observed:** An oversized lowercase word spans almost the entire width, around 335px tall inside a 423px ending. It appears as charcoal letter-shaped interruptions in a low-contrast field of fine vertical gray lines, with line tips tracing the curved silhouettes. The effect is carved or machined, not luminous.

**Transfer:** Retain a monumental word sculpture using the new product's short name or a single relevant word. Scale and mask it to the width while keeping the contrast subdued.

**Build:** Create a full-width SVG with a dark canvas, 1px vertical gray strokes spaced about 10px apart and opacity around 0.5. Mask the lines with the inverse of very heavy lowercase text so the word is dark negative space. Fit the word into a roughly 1360×335px inner area, then extend the line field beyond it and clip to the section.

### Muted trust marks

**Use:** Compact credibility strips and footer credentials.

**Observed:** Customer marks use monochrome putty masks at half opacity; they sit in a centered horizontal strip with a small mono introduction. Footer seals are similarly desaturated.

**Transfer:** Unify authorized marks into one neutral tone, preserving their original proportions. Use text-only proof if no logos or credentials are available.

### Icons

**Observed:** Marketing integrations use compact 40×40px image icons; technical plate details are simple 20px circles. Small software controls use mostly thin 16px outline icons rather than large decorative pictograms.

**Transfer:** Keep branded service marks within integration context; choose simple monochrome line icons for functional controls and use circles or rules for marketing decoration.

## Section recipes

How recurring sections are built.

### First screen: Centered category opening

**Observed:** The Canvas carries Fixed navigation above a centered symbol-and-category title. The combined title occupies about three fifths of the page width and is visually about 128px tall in type, with a circular symbol comparable to the capital height. The content begins after 168px of top padding. A short body line follows with a 40px gap; the Primary button and Secondary button follow after 60px, with 20px between equal 326×66px controls. A subdued trust strip occupies the lower opening. Within the first 900px, the entire title, support and actions are visible, followed by the top of the large Software stage beginning around 719px. Most of the software lies below the fold. Back-to-front layers are matte canvas, restrained edge linework, title and support, then flat rectangular actions; no large illustration competes with the name.

**Transfer:** Use a short product category or two-word promise with a simple product symbol. Fit the combined lockup to the same visual width and use the display lettering vocabulary without forcing long copy onto one line. A product without finished interface artwork should still reveal the top of a simplified workflow window below the trust strip. For narrower-purpose pages, shorten the introduction but retain the symbol/title, operational support line and rectangular actions.

**Avoid:** Do not replace the compact identity-led first screen with a split photographic hero, a huge gradient blob, or a many-line manifesto.

**Text style:** `display` — Restart Soft 500 · 140px/0.9 · tracking -0.03em

### Problem and technical diagram

**Observed:** A split chapter uses 160px vertical padding, a blue eyebrow, 32px to the 72px explanation-heading, then 40px to a narrow body paragraph. A thin-line chart balances the text rather than sitting inside a separate card.

**Transfer:** Pair one clear operational friction with a restrained mechanism diagram; keep the text side dominant.

**Text style:** `explanation-heading` — Restart Soft 500 · 72px/1.08 · tracking -0.03em

### Technical capability chapter

**Observed:** The Capability band starts with a centered 104px chapter declaration and can lead into a Process column rail. A subsequent flush-left heading and right-aligned support paragraph introduce the Feature assembly grid after a 100px pause. A pixel-marker and annotated outlined action form a report-like lower edge.

**Transfer:** Choose a small set of concrete capabilities and show how each operates, using the process rail and overlapping assemblies where they fit the narrative.

**Text style:** `heading` — Restart Soft 500 · 72px/0.9 · tracking -0.03em

### Industrial quantified proof

**Observed:** A 140px multi-line display statement occupies the left half. Three compact mono metric rows beneath it are separated by thin rules. The right half is a tall ruled instrument graphic terminating in the Proof plate; pixel milestones and a dense tick strip connect the halves. A full-width Secondary button closes the block.

**Transfer:** Connect one major business outcome to a few credible operational details; keep the bolted sign and ruler treatment even if the result is not a percentage.

**Text style:** `display` — Restart Soft 500 · 140px/0.9 · tracking -0.03em

### Conceptual operating layer

**Observed:** A blue eyebrow introduces a 104px left-aligned chapter statement. Two body paragraphs sit below in adjacent columns; a broad blue action, compact mono markings and a schematic symbol occupy the supporting zone.

**Transfer:** Explain how the product fits into the reader's existing world after demonstrating its mechanics.

**Text style:** `chapter` — Restart Soft 500 · 104px/0.9 · tracking -0.03em

### Audience operating matrix

**Observed:** The Audience ground opens with a 160px two-line title, small blue mono context and a rotated 80px pixel label at the right edge. Audience row repeats create a ruled editorial table with generous bottom padding, short outcome headlines and explanatory copy.

**Transfer:** Use the matrix for meaningful audiences or operating modes, keeping labels short and benefits concrete.

**Text style:** `matrix-display` — Restart Soft 500 · 160px/1 · tracking -0.03em

### Integration statement

**Observed:** A centered 48px statement is supported by a horizontal row of 40px integration marks separated by 24px; the section has 180px top and 200px bottom padding.

**Transfer:** Use a succinct compatibility claim and a restrained row of actual ecosystem marks, or short text names if marks are unavailable.

### Closing conversion and engraved ending

**Observed:** The Closing stage uses a centered 100px statement constrained to 586px, body copy with a 40px gap and paired rectangular actions after 50px. The functional footer returns to Canvas with 80px vertical padding and three columns: identity and credentials, Indexed footer link stack, utility links and contact. Beneath that, the Monumental ruled word sculpture gives the page a second, purely graphic ending.

**Transfer:** End the sales argument with a short operational promise and clear action, then provide a useful editorial footer. Keep the final word sculpture as a distinct brand-scale device rather than another call to action.

**Text style:** `closing-heading` — Restart Soft 500 · 100px/0.9 · tracking -0.03em

## Page flow

**Storyline:** category promise → working product → operational friction → mechanism and capabilities → measurable return → broader fit → audience outcomes → closing action → functional footer and monumental word

### A technical product landing page that turns an abstract category into concrete operational confidence

1. **Promise** — Centered category lockup, brief support, paired actions and subdued trust strip.
2. **Product demonstration** — Large dark application window staged below the fold.
3. **Problem framing** — Split explanation and fine-line divergence graphic.
4. **Mechanism** — Large chapter statement and a connected process rail.
5. **Capability proof** — Two-column grid of software fragments and offset caption plates.
6. **Quantified proof** — Oversized outcome statement, mono metric rows and a blue fastened sign.
7. **Broader product fit** — Large conceptual statement, paired explanatory paragraphs and technical diagram.
8. **Audience outcomes** — Oversized title followed by a ruled multi-column outcome matrix.
9. **Ecosystem fit** — Centered claim and compact integration marks.
10. **Closing call** — Deeper charcoal stage with a concise promise and paired actions.
11. **Ending** — Three-column indexed footer followed by a monumental line-masked word sculpture.

**Transfer:** Adapt the sequence to the new product's buying questions rather than preserving its section count. Alternate spacious declarations with tangible mechanisms and concentrated proof, and preserve the equipment-marking vocabulary through the ending.

## Writing

Direct, operational and technically fluent, with the confidence of a tool already doing useful work. Human collaboration and practical outcomes matter more than theatrical AI language.

**Do not copy:** Do not reuse Serro's name, logos, proprietary artwork, customer marks, contact information, product codes, claims, result figures or credentials. Source copy examples illustrate tone, not claims available to another product.

- **Addressing the reader:** Headlines often omit the subject and lead with a verb. Explanations alternate product-name statements with direct 'you' language; 'we' is not the main narrator.
- **Rhythm:** Short emphatic headlines, then one or two explanatory sentences. Longer conceptual headlines are broken into tightly led lines; mono labels are terse, almost like labels on equipment.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Category title | Short literal category name rather than a poetic slogan. | 2–4 words | “TPM Agents” |
| Support line | One human outcome stated without qualifiers. | 5–12 words | “Build cohesively, as a team” |
| Section headline | Identify an operational cost or promise in plain language. | 5–10 words | “Staying aligned is time-consuming and expensive”<br>“Pays for itself on day one” |
| Technical label | A terse chapter marker or system noun. | 2–5 words | “The bottleneck changed”<br>“PROGRAM MEMORY” |
| Mechanism description | State what the system does, then name what the reader controls. | 15–35 words | “It reads signals across your tools and surfaces the work you are running. You name it, own it, and decide what is shared.” |
| Closing promise | A compact benefit with a constraint that matters. | 4–7 words | “Move faster without drift” |
| Primary action | A concrete access or sales action. | 2–4 words | “Book a Demo”<br>“Get Early Access” |

**Words and phrasing to use:** shared; state; memory; signals; current; owners; controls; execution; outcomes; without

**Avoid:** magical; revolutionary; game-changing; limitless; supercharge everything; AI-powered everything

**Rules:**

- Describe a mechanism before making the larger category argument.
- Tie every outcome to what changes in the reader's day-to-day work.
- Keep technical nouns concrete and related to the product; labels should help orientation, not merely decorate.
- Reserve numerals and strong return claims for substantiated proof.
- Use sentence case for human statements and uppercase for equipment-style labels.

## Do's and Don'ts

### Do

- Use 500-weight soft grotesk with -0.03em tracking for major headings.
- Keep 40px desktop page gutters and 32px eyebrow-to-heading spacing.
- Use 66px square-cornered main actions with 24px labels.
- Pair a real software fragment with an offset graphite caption plate.
- Make the proof plate blue with dark numerals and four 20px corner dots.
- Keep the page mostly charcoal and warm white; concentrate blue into labels, controls and proof.
- Finish with the indexed footer and a subdued full-width ruled word sculpture.

### Don't

- Do not substitute pure black and cool white for the warm #272727 and #faf9f5 foundation.
- Do not use blue as the background of every chapter; it loses its signaling function.
- Do not round marketing controls into pills or feature plates into soft dashboard cards.
- Do not replace the regular/medium type hierarchy with bold text everywhere.
- Do not add colorful icon medallions to each capability; use serials, fine rules and software instead.
- Do not apply the software-window shadow to flat caption plates or audience rows.
- Do not promote pixel lettering into paragraph text or long headlines.
- Do not compress chapter pauses into a uniform 24px spacing pattern.

## Motion and responsive

### Motion

**Observed:**

- Navigation color transitions use 0.2s cubic-bezier(0.44, 0, 0.56, 1). Other text links also have 0.15s transitions with the same curve.
- Navigation and utility links turn blue on hover; large footer links turn equipment gray.

**Transfer:**

- Preserve color-only link feedback rather than adding floating or springy button movement.
- Keep technical graphics readable in their settled state; line fields should remain a visual structure rather than a motion-dependent explanation.

**Unknown:**

- Timing and behavior of scrolling artwork and interface animation are not established.

### Responsive

**Observed:**

- Styles contain width breakpoints at 810px, 1200px and 1440px; only the desktop composition is established.

**Transfer:**

- On narrow screens, stack the split chapters and feature assemblies while preserving software-before-caption reading order.
- Turn the process rail and audience matrix into vertical ruled entries; keep serials and blue labels attached to their content.
- Scale the opening symbol/title as one lockup, stack paired actions when needed, and fit the final word sculpture to the viewport rather than allowing horizontal overflow.

**Unknown:**

- Exact mobile typography, spacing, navigation behavior and rearrangements are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
