# reboot — prose with playful objects

## Overview

An airy white editorial style that reads like a personal note, with medium-weight grotesk sentences carrying nearly the entire page. Charcoal and pale gray prose are punctuated by tiny, saturated, tactile objects: glossy app tiles, stickers and miniature illustrations. It suits focused software and service landing pages whose promise can be explained conversationally, without a dense dashboard or conventional feature-card grid.

### Essentials

- The pitch is a continuous oversized paragraph, not a headline stack: Inter 40px, weight 500, line-height 1.6 and normal tracking carry the opening, capabilities, proof and closing.
- The opening behaves like a letter with a masthead: a centered 856px wrapper with 24px side padding, a small identity at the left and a 36px outlined status pill at the right, then prose beginning 300px down.
- Color lives inside objects rather than the canvas: white dominates almost the entire page, with charcoal and gray text; saturated cyan-to-blue appears in roughly 72px inline app tiles rather than broad colored sections.
- Images are punctuation with physical presence: insert glossy 16px-radius tiles and small die-cut objects at sentence boundaries, with soft stepped shadows and slight rotations. When product media is unavailable, use an original symbolic object with the same inline scale and material.
- Conversion has two distinct forms: a 40px underlined text invitation within the prose and a compact 148×40px dark floating pill with a circular plus control.
- The ending exhales rather than changes theme: the same 40px prose closes the argument, then about 340px of whitespace separates it from four muted 16px/1.8 footer lines. Retain the tiny illustrated punctuation and the floating discovery action.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gloss cyan | `#00c8fb` | `--color-cyan` | accent, surface | Top of the small glossy inline tile gradient, never a page-wide fill. |
| Electric blue | `#1a2ff7` | `--color-blue` | accent, surface | Bottom of the small glossy inline tile gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Floating charcoal | `#262626` | `--color-floating` | surface, action | Visible 85% black floating control over white; use rgba(0,0,0,0.85) for its translucent construction. |
| Utility black | `#000000` | `--color-black` | text, accent | Small status label and the strong underline beneath the closing invitation. |
| Charcoal | `#232323` | `--color-ink` | text | Main narrative and text invitation. |
| Raised gray disc | `#3c3c3c` | `--color-control-disc` | surface | Visible 10% white overlay on the floating charcoal control. |
| Muted gray | `#a7a7a7` | `--color-muted` | text, link | Footer text and small utility icons; visible result of rgba(35,35,35,0.4) over white. Footer link hover increases the source ink alpha to 0.8. |
| Pale narrative gray | `#c8c8c8` | `--color-inactive` | text | De-emphasized capability words and the pale reading-ahead appearance of the narrative. |
| Pill edge | `#e6e6e6` | `--color-edge` | border | Visible 10% black outline on white. |
| Soft white label | `#e9e9e9` | `--color-on-floating` | text | Visible 90% white label on the floating charcoal control. |
| White | `#ffffff` | `--color-canvas` | background, border | Unbroken page ground and white edges around small circular media. |

## Typography

- **__inter_d4f92f** — All narrative, actions and utility text. Contemporary neutral grotesk with open counters; medium weight makes conversational prose feel deliberate rather than decorative. If unavailable, use **Inter**. Use weights 500 and 600 with normal tracking. Font stack: "__inter_d4f92f", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| narrative | __inter_d4f92f | 500 | 40px | 1.6 | normal | Opening promise, supporting argument, capability words, inline quantities and closing text action. |
| footer | __inter_d4f92f | 500 | 16px | 1.8 | normal | Personal footer sentences and inline footer links. |
| floating-action | __inter_d4f92f | 600 | 16px | 1.5 | normal | Label in the dark floating discovery control. |
| status | __inter_d4f92f | 500 | 14px | 20px | normal | Small outlined masthead pill. |

**Notes:**

- Narrative hierarchy comes from paragraph breaks, reading emphasis and objects, not changing font families or headline sizes.
- Keep line-height unusually generous at 1.6 even for the headline. The opening promise is embedded in the same stream as its support, not isolated above a small body paragraph.
- Numbers use the surrounding narrative recipe; do not create oversized statistical counters.

## Layout

**Density:** Airy: a compact single reading column is surrounded by extensive white margins and a long pause before the footer.

### Spacing

**Spacing system:**

- **rhythm** 16px, vertical — Primary vertical padding rhythm; 32px paragraph separators and 128px footer padding.
- **step** 8px, horizontal — Horizontal padding, especially 16px pill insets and 24px wrapper insets.

| Value | Use |
| --- | --- |
| 16px | Horizontal status-pill padding. |
| 24px | Content side padding inside the centered wrapper. |
| 32px | Desktop padding on each side of paragraph break spacers, making a 64px blank line. |
| 80px | Desktop masthead top offset and footer clearance from the page end. |
| 128px | Footer block top padding. |
| 300px | Desktop narrative start offset from the top of the page. |
| 340px | Pause between the narrative ending and first footer sentence. |

### Containers and grids

- **reading-wrapper**: max width 856px · 1 column · side padding 24px. Centered desktop wrapper. Its inner text measure is 808px; both masthead ends and the footer align to this text edge.
- **footer-lines**: max width 380px · 1 column · side padding 24px. Narrow, left-aligned conversational footer under the main reading column; no multi-column sitemap.

## Corner radius

| Element | Radius |
| --- | --- |
| inline-tiles | 16px |
| utility-pills | 9999px (pill) |
| control-disc | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| tactile-object | `0px 1px 1px -0.5px rgba(0,0,0,0.06), 0px 3px 3px -1.5px rgba(0,0,0,0.06), 0px 6px 6px -3px rgba(0,0,0,0.06), 0px 12px 12px -6px rgba(0,0,0,0.06), 0px 24px 24px -12px rgba(0,0,0,0.06)` | Small inline objects feel suspended just above the white paper. |

### Surfaces

#### White paper · level 0

**Use:** The entire marketing canvas.

**CSS:** `background: #ffffff; color: #232323`

**Observed:** No alternating background bands or large bordered panels.

**Transfer:** Let prose, whitespace and tiny illustrated objects organize the page.

#### Gloss tile · level 1

**Use:** Saturated inline product-symbol object.

**CSS:** `background: linear-gradient(#00c8fb, #1a2ff7); border-radius: 16px; box-shadow: 0px 1px 1px -0.5px rgba(0,0,0,0.06), 0px 3px 3px -1.5px rgba(0,0,0,0.06), 0px 6px 6px -3px rgba(0,0,0,0.06), 0px 12px 12px -6px rgba(0,0,0,0.06), 0px 24px 24px -12px rgba(0,0,0,0.06)`

**Observed:** A white geometric mark sits on a cyan-to-blue rounded square with slight tilt and layered edges.

**Transfer:** Use a simple product-relevant symbol, maintaining the glossy miniature scale.

#### Floating dark glass · level 2

**Use:** Discovery action above the page.

**CSS:** `background: rgba(0,0,0,0.85); border-radius: 9999px; backdrop-filter: blur(8px)`

**Observed:** A compact charcoal capsule with a softly lit circular icon area.

**Transfer:** Reserve this dark surface for the single floating discovery affordance.

## Components

### Minimal masthead

**Use:** Identity and one secondary announcement.

**CSS:** `position: relative; max-width: 856px; padding: 0px 24px`

**Observed:** A small identity, about 99×23px, sits opposite Status pill. Both share a top alignment at 80px on desktop; there is no row of navigation links.

**Transfer:** Keep the identity modest and use the opposite corner for one timely secondary action.

### Status pill

**Use:** Secondary announcement in the masthead.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 36px; padding: 0px 16px; border: 1px solid rgba(0,0,0,0.1); border-radius: 9999px; color: #000000`

**Text style:** `status` — __inter_d4f92f 500 · 14px/20px

**Observed:** Primary status precedes a centered dot and a lower-emphasis descriptor. Width follows the label; the original is 173px.

**States:** Declared: hover background-color rgba(0,0,0,0.03); focus-visible not specified.

**Transfer:** Use one short status and a concise descriptor rather than turning it into the main conversion.

### Narrative text link

**Use:** Primary conversion at the end of the argument.

**CSS:** `position: relative; color: #232323; background: transparent`

**Text style:** `narrative` — __inter_d4f92f 500 · 40px/1.6

**Observed:** An underlined text invitation on its own line, at exactly the scale of the preceding sentence. A small yellow die-cut gesture overlaps the right end. The underline is a separate 4px black bar.

**Transfer:** Keep the invitation inside the paragraph rhythm and append a small friendly symbolic object.

### Floating discovery pill

**Use:** Persistent access to work or a product demonstration.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 148px; height: 40px; border-radius: 9999px; background: rgba(0,0,0,0.85); backdrop-filter: blur(8px); color: rgba(255,255,255,0.9)`

**Text style:** `floating-action` — __inter_d4f92f 600 · 16px/1.5

**Observed:** Viewport-centered near the bottom edge, above the content. Label sits to the left of a translucent circular plus. It is fully visible near the ending.

**Transfer:** Use a short discovery label and one circular expansion affordance; keep the closing text invitation as a separate action.

### Inline object tile

**Use:** Interrupt prose with a small tactile product symbol.

**CSS:** `display: inline-flex; position: relative; width: 72px; height: 72px; border-radius: 16px; background: linear-gradient(#00c8fb, #1a2ff7); transform: rotate(5deg)`

**Observed:** Inserted between sentences, raised above the text baseline and layered over the reading stream. Several rounded tiles stack behind the front symbol.

**Transfer:** Use the Gloss tile surface and an original white SVG symbol; give the object enough inline width to avoid colliding with words.

### Conversational footer

**Use:** Low-key contact and identity information.

**CSS:** `padding: 128px 24px 0px; color: rgba(35,35,35,0.4)`

**Text style:** `footer` — __inter_d4f92f 500 · 16px/1.8

**Observed:** Four short left-aligned lines: origin, contact, social or listening links, then copyright. Small icons are embedded mid-sentence; the block does not span the text width.

**Transfer:** Use natural sentences and a small number of useful links rather than a formal sitemap.

### Footer inline link

**Use:** Small destinations embedded in footer sentences.

**CSS:** `display: inline-flex; align-items: center; color: rgba(35,35,35,0.4)`

**Text style:** `footer` — __inter_d4f92f 500 · 16px/1.8

**Observed:** A 16px icon precedes the word without a surrounding button surface.

**States:** Declared: hover color rgba(35,35,35,0.8); focus-visible not specified.

**Transfer:** Preserve the sentence flow and brighten the ink on hover.

## Imagery and graphics

### Tactile inline punctuation

**Use:** Signature visual language throughout the narrative, including the closing invitation.

**Observed:** Small colorful objects sit directly inside the text: a glossy tilted app tile, a calendar miniature, a green score badge and a yellow outlined hand sticker. They have crisp silhouettes, rounded or die-cut edges, soft contact shadows and bright local color. They occupy far less area than the prose; there is no large hero photograph.

**Transfer:** Make original miniature symbols for the new product's promise and proof. Include at least one glossy symbol and one sticker-like punctuation object. A clean vector object with dimensional shading is the minimum acceptable replacement for elaborate 3D artwork.

**Build:** For the tile, stack two 72px rounded squares with 16px radii behind a front cyan-to-blue gradient square, rotate the front by 5deg, and center a white geometric SVG symbol. Add the tactile-object shadow. For a sticker, use an SVG outline of a product-relevant object, a thick white inner outline, a saturated outer silhouette and a subtle gray drop shadow. Keep the visible artwork around one narrative line tall and position it inline at a sentence boundary.

### Icons

**Observed:** Footer icons are restrained gray glyphs around 15–16px; outline examples use 1.5px rounded strokes. The floating control uses a small plus in a translucent circular disc. Large white tile symbols are graphic marks, not a repeated feature-icon system.

**Transfer:** Choose simple 16px utility glyphs that can live inside sentences; reserve illustrated color for the tactile inline objects.

## Section recipes

How recurring sections are built.

### First screen: Letterlike opening

**Observed:** White paper supports a narrow centered reading composition, not a split hero. Minimal masthead occupies the two ends of the text measure near the top; the Narrative begins 300px down inside the 856px wrapper with 24px insets. The 40px/1.6 promise wraps to two lines, with a roughly 72px Gloss tile inserted after the sentence. Supporting prose continues at the very same size, appearing pale gray behind the current dark reading emphasis. Within the first 900px, the identity, Status pill, promise, inline tile, several lines of support and the first capability paragraph are visible. The invitation and complete footer fall below the fold; the discovery pill is a floating layer rather than a hero button row.

**Transfer:** Open with a plain-language promise and continue immediately into its explanation at the same scale. For other page purposes, use a similarly short thesis and explanatory prose. Without product media, create a white-symbol gloss tile and one original vector punctuation object rather than a large illustration.

**Avoid:** Do not turn this into a centered slogan over a screenshot, a two-column hero, or a stack of headline, tiny support text and filled primary buttons.

**Text style:** `narrative` — __inter_d4f92f 500 · 40px/1.6

### Prose capability chapter

**Observed:** The narrative continues with the same recipe, separated by blank-line spacers. A lead sentence introduces a run of short capability nouns ending in periods; text remains left aligned, with pale gray capability words rather than a grid of bordered cards.

**Transfer:** Use a short explanatory sentence followed by a compact vocabulary of capabilities or benefits. Let the words and inline objects carry the hierarchy.

**Text style:** `narrative` — __inter_d4f92f 500 · 40px/1.6

### Inline quantified proof

**Observed:** Experience and delivery quantities remain embedded in sentences at 40px rather than enlarged stat counters. Small symbolic objects, including a calendar and score badge, provide visual punctuation.

**Transfer:** State only relevant proof in ordinary sentences, and attach an original miniature object representing the type of proof.

**Text style:** `narrative` — __inter_d4f92f 500 · 40px/1.6

### Personal closing and distant footer

**Observed:** The last promise and Narrative text link retain the 40px narrative scale. A yellow sticker-like gesture sits at the link's end. White space of about 340px precedes the first Conversational footer line, which uses muted 16px/1.8 text. The Floating discovery pill stays near the viewport bottom.

**Transfer:** End with a direct reader benefit and a short conversational action. Retain the illustrated punctuation and long visual pause before a compact sentence-based footer.

**Text style:** `narrative` — __inter_d4f92f 500 · 40px/1.6

## Page flow

**Storyline:** Plain promise → human explanation → complexity or need → focused solution → concise proof → personal invitation → small conversational footer.

### A compact narrative landing page that converts through explanation and craft rather than a broad catalogue

1. **Promise** — An oversized plain-language sentence and glossy inline object introduce the offer.
2. **Credibility** — The same prose stream establishes the team or product's experience without a separate testimonial wall.
3. **Problem framing** — A short capability vocabulary and explanatory paragraphs make the complexity legible.
4. **Solution** — Direct we-and-you sentences explain what is taken off the reader's plate.
5. **Quantified proof** — A small number of facts appear inline, punctuated by symbolic illustrations.
6. **Closing call** — One reader-focused sentence leads to an underlined invitation and friendly sticker.
7. **Contact** — After a long white pause, four small muted lines finish the page while a discovery capsule floats nearby.

**Transfer:** Treat this as a prose-led argument, adapting the number and order of paragraphs to the offer. Preserve the single-scale narrative, miniature objects, dual action treatment and personal ending rather than forcing conventional feature sections.

## Writing

Confident, direct and personal, with craft expressed through plain claims rather than elaborate terminology. Warmth comes from conversational phrasing and tiny playful visual interruptions.

**Do not copy:** Do not reuse the reboot identity, its symbols, contact details, location, service claims, experience figures, timing promises or performance scores. Replace them with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak as we to you and your team; describe a concrete outcome for the reader rather than an abstract category.
- **Rhythm:** Full sentences carry the argument, interrupted by short period-ended capability words and a three-word action. Paragraphs are short enough to remain readable at display scale; contractions keep them conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | We + concrete verb + quality or outcome + audience. | About 8–12 words | “We build world-class marketing sites for software startups.” |
| Problem framing | A simple declarative sentence names the cost or distraction. | About 7–12 words | “Your team should never stop shipping.” |
| Capability vocabulary | Short nouns as discrete sentences rather than bullets. | One word per item | “Design. Engineering. Branding. Copywriting. Video. 3D. Interaction.” |
| Closing promise | Your + subject + deserves + better outcome. | About 7–9 words | “Your product deserves a better site.” |
| Primary action | Short conversational verb phrase. | 2–4 words | “Book a call” |
| Footer | Human sentence that gives context or invites contact. | One short line | “Designed in Barcelona for a global audience.” |

**Words and phrasing to use:** we; your; build; helping; craft; detail; performance; deserves

**Avoid:** synergize; disruptive ecosystem; unleash limitless potential; revolutionary platform

**Rules:**

- Let each paragraph advance one part of the argument.
- Place practical proof close to the promise it supports.
- Use contractions and ordinary verbs instead of corporate abstractions.
- Keep discovery labels short enough for the compact floating capsule.

## Do's and Don'ts

### Do

- Keep narrative text at 40px/1.6 and weight 500 on desktop.
- Align masthead, prose and footer to the 24px inset of the 856px wrapper.
- Use 72px inline objects as sentence punctuation rather than separate hero media.
- Maintain the 16px radius and stepped 6% black shadows on glossy tiles.
- Keep the secondary status pill 36px high with a 1px low-contrast outline.
- Preserve the contrast between a large text invitation and a 148×40px floating capsule.
- Give the footer a long white pause and use 16px/1.8 muted sentences.

### Don't

- Do not tighten the narrative to a conventional 1.1 display line-height; the 64px line box is part of its reading rhythm.
- Do not turn inline numbers into a row of oversized statistic cards.
- Do not use cyan or blue as large background bands; they belong to small objects.
- Do not apply the 16px media radius to every section or wrap prose in panels.
- Do not enlarge the utility label to compete with the 40px narrative.
- Do not replace the sentence-based footer with dense navigation columns.
- Do not use black glass for broad page surfaces; reserve it for the small floating action.

## Motion and responsive

### Motion

**Observed:**

- Narrative word elements declare all 0.5s cubic-bezier(0.4,0,0.2,1) transitions; pale and dark text coexist in the opening reading state.
- Status-pill color properties transition over 0.3s with cubic-bezier(0.4,0,0.2,1).
- The small floating icon declares all 0.15s cubic-bezier(0.4,0,0.2,1); miniature media declares a 0.5s shadow transition.
- The invitation uses a separate underline bar with a group-hover width change.

**Transfer:**

- Use the pale-to-ink reading emphasis as the principal narrative animation, keeping the words in stable line boxes.
- Keep object animation local to sentence punctuation; the page should still read as a letter, not an animated presentation.

**Unknown:**

- Exact scroll trigger thresholds, object choreography and discovery-panel behavior are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1200px, 1280px, 1340px and 1536px.
- The narrative declares a 30px base size and 40px desktop size, both at 1.6 line-height; its starting margin changes from 200px to 300px.
- The reading wrapper declares a 508px base maximum and 856px desktop maximum. The status descriptor and dot are hidden below the medium breakpoint.

**Transfer:**

- On narrow screens, retain the one-column prose and 24px insets. Use the declared 30px narrative size and 200px opening offset rather than scaling the whole desktop scene.
- Keep inline objects attached to meaningful phrase boundaries and simplify the status pill to its short first label.

**Unknown:**

- Mobile line wrapping, object overlap behavior and exact floating-control bottom clearance are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
