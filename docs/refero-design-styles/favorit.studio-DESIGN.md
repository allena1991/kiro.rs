# Favorit Studio — monumental type, tactile stages

## Overview

An austere black-and-white identity with the scale and pacing of an art-directed portfolio. Oversized contemporary grotesk lettering meets a sharp editorial serif, while warm studio portraits and tactile product photography carry nearly all the color. It suits design-led products and services that can make a strong visual case with very little copy; density alternates between immersive images, monumental words and small islands of text.

### Essentials

- The identity behaves like an editorial masthead rather than a navigation logo: regular serif at 178.6px, line height 1 and -0.025em tracking sits above an almost full-width photographic stage.
- Actions are typography, not colored capsules: the navigation is a tucked 23.1px text button with 16px padding, while closing contact links expand to 158.6px with no enclosing shape.
- Color belongs to the photographs: page backgrounds, text and 1px dividing rules use only #ffffff and #000000; warm beige, stone and wood appear within rectangular media rather than interface accents.
- Capability language becomes a wall of words: 135px regular grotesk, line height 1, -0.025em tracking and consecutive unspaced lines invert from black-on-white to white-on-black across a sharp section boundary.
- Images are treated as exhibition plates: 21.4px side gutters, square corners, no card shadow, and large studio-lit subjects backed by matte neutral fields or tactile materials. Use a carefully lit still life when people or finished product imagery are unavailable.
- A geometric closing statement interrupts the rectangular page: a giant black circle, clipped by a 900px-tall white stage, holds a single white monumental sentence; the final black screen reduces the interface to a centered upward arrow. Preserve both devices with new language.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-ink` | text, background, border | Primary lettering and rules on white; full dark chapters and the oversized circular statement. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute white | `#ffffff` | `--color-canvas` | background, text, border | Main page canvas; inverse lettering and rules on black. There is no intermediate interface neutral ramp. |

## Typography

- **TWKLausanne** — Capability lists, project titles, body copy, navigation and contact links. Clean contemporary grotesk, regular throughout, with rounded open forms and tightly joined large words. If unavailable, use **Inter**. Use 400; retain the tight display tracking and compare word widths. Font stack: "TWKLausanne", "Inter", "Helvetica Neue", Helvetica, sans-serif.
- **Favorit Times** — Opening identity masthead and its companion stripe. High-contrast editorial serif with sharp fine strokes, familiar Times construction and compact spacing. If unavailable, use **Libre Caslon Display**. Use 400 and tune width before changing the display size. Font stack: "Favorit Times", "Libre Caslon Display", "Times New Roman", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| masthead | Favorit Times | 400 | 178.6px | 1 | -0.025em | size calc(0.59949rem + 11.7347vw) | Opening identity line and companion identity stripe. |
| display | TWKLausanne | 400 | 158.6px | 1 | -0.025em | fixed | Large showcase titles and monumental contact links; also the visual scale for the circular closing statement. |
| capability | TWKLausanne | 400 | 135px | 1 | -0.025em | fixed | Tall stacks of short capability nouns. |
| body-label | TWKLausanne | 400 | 23.1px | 1.2 | -0.01em | size calc(0.89541rem + 0.61224vw) | Body statements, chapter labels, menu button and small contact information. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular weight creates the entire hierarchy; scale and placement replace bold emphasis.
- Display tracking is -0.025em; smaller copy relaxes to -0.01em. Chapter labels stay sentence case rather than becoming tiny tracked capitals.
- Large titles use optical negative margins and clipping wrappers so visible letter edges align closely with the media gutters.

## Layout

**Density:** Airy at chapter scale and tightly packed within type stacks; a short paragraph can occupy the center of an otherwise black screen.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 16px | Menu button padding. | fixed |
| 21.4px | Main media and text gutter, showcase title bottom padding and gap to image. | calc(0.65051rem + 0.76531vw) |
| 46.3px | General chapter and contact content vertical padding. | calc(1.79082rem + 1.22449vw) |
| 13.9px | Top inset of chapter labels. | fixed |
| 9.3px | Bottom inset of chapter labels. | fixed |

### Containers and grids

- **edge-to-edge container**: max width 1440px · side padding 21.4px. At the desktop reference width, content fills the window rather than sitting in a narrow centered shell. Borders span beyond the content gutters.
- **centered statement**: max width 463px. Small centered prose island inside the dark manifesto chapter.
- **contact grid**: 12 columns · gap 0px · side padding 21.4px. Small information columns occupy the left half; a 699px-wide portrait occupies the right half at desktop.

## Corner radius

| Element | Radius |
| --- | --- |
| rectangular media and controls | 0px |
| statement disc | 50% |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Opening, capability stage and showcase sequence.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Untextured white space; boundaries are single black rules, not shaded cards.

**Transfer:** Keep all non-photographic light areas neutral and flat.

#### Black chapter · level 0

**Use:** Manifesto, contact section and return-to-top ending.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** True black extends edge to edge, interrupted by white text and thin white rules.

**Transfer:** Use full chapter inversions instead of introducing colored panels.

#### Statement disc · level 1

**Use:** Geometric closing assertion.

**CSS:** `background: #000000; color: #ffffff; border-radius: 50%`

**Observed:** A circle approximately the content width is centered inside a shorter white stage, clipping its upper and lower arcs.

**Transfer:** Use the disc as a dramatic typographic field, not a card.

## Components

### Tucked menu

**Use:** Persistent navigation affordance.

**CSS:** `color: #ffffff; padding: 16px; transform: translate(38.2px, 0px); transition: transform 0.6s cubic-bezier(0.165, 0.875, 0.02, 1)`

**Text style:** `body-label` — TWKLausanne 400 · 23.1px/1.2 · tracking -0.01em

**Observed:** Pinned at the upper-right inside an overflow-hidden fixed header with difference blending. At rest it reads as a single initial rather than a full horizontal navigation bar.

**States:** Declared: hover transform none; focus-visible unknown.

**Transfer:** Retain a compact edge-aligned text control; make the complete accessible name available.

### Chapter rail

**Use:** Persistent section identification above a long chapter.

**CSS:** `background: #000000; color: #ffffff; border-bottom: 1px solid #ffffff; position: sticky; padding: 13.9px 16.2px 9.3px 0px; z-index: 5`

**Text style:** `body-label` — TWKLausanne 400 · 23.1px/1.2 · tracking -0.01em

**Observed:** The label sits in an inner guttered container. A light variant reverses text, background and rule for the showcase chapter.

**Transfer:** Use short navigational nouns rather than repeating the giant headline.

### Showcase title band

**Use:** Name each image-led proof item.

**CSS:** `border-bottom: 1px solid #000000; padding-bottom: 21.4px; margin-bottom: 21.4px; overflow: hidden`

**Text style:** `display` — TWKLausanne 400 · 158.6px/1 · tracking -0.025em

**Observed:** A single enormous title sits above its wide image. Text is nonwrapping and can enter horizontally; the border crosses the whole page rather than stopping at the text gutter.

**Transfer:** Pair a short proof title with one persuasive plate rather than a grid of small thumbnails.

### Manifesto island

**Use:** Explain a point of view with very little text.

**CSS:** `max-width: 462.9px; text-align: center; color: #ffffff`

**Text style:** `body-label` — TWKLausanne 400 · 23.1px/1.2 · tracking -0.01em

**Observed:** A compact centered paragraph sits within a much larger black stage. Sentences flow continuously rather than becoming separate cards.

**Transfer:** State a handful of meaningful choices in parallel language.

### Monumental contact link

**Use:** Closing conversion and external destinations.

**CSS:** `color: #ffffff; font-size: 158.6px; line-height: 1; letter-spacing: -0.025em`

**Text style:** `display` — TWKLausanne 400 · 158.6px/1 · tracking -0.025em

**Observed:** Links run in a single oversized horizontal strip below the contact photograph. The strip extends beyond the right edge instead of wrapping into a conventional footer list.

**Transfer:** Use two or three short destination labels; keep all destinations reachable when the strip moves or scrolls.

### Portrait plate

**Use:** Human image in the contact chapter.

**CSS:** `max-width: 100%; object-fit: fill`

**Observed:** An unframed landscape image fills the right half of the contact grid; its approximately 699px by 466px rectangle has no caption or decoration.

**Transfer:** Use a monochrome portrait or a human-scale view of the product in use.

### Return-to-top stage

**Use:** Final interaction after the contact section.

**CSS:** `display: flex; align-items: center; background: #000000; color: #ffffff`

**Observed:** A full 900px-tall desktop black screen contains only a centered thin upward arrow, while the tucked menu remains in its corner.

**Transfer:** Make the central arrow a labelled back-to-top control, not another promotional message.

## Imagery and graphics

### Studio human stage

**Use:** Opening image and humanizing interludes.

**Observed:** A casually dressed seated person in black is centered against a seamless warm beige studio background. The opening is a rear view with substantial empty space around the upper body; subsequent views turn toward the viewer and shift to monochrome. Soft diffuse light, muted skin tones and unobtrusive stools or blocks avoid lifestyle clutter. The first image occupies almost all the screen below the masthead.

**Transfer:** Photograph a person using the new product against a warm neutral cyclorama. If that is impossible, stage the product alone at the same scale and with the same broad negative space; use a genuine still image rather than an empty animation panel.

### Tactile showcase plates

**Use:** Large proof imagery beneath each title band.

**Observed:** Wide image plates show architectural wood and lamp details, black packaging on rough concrete, printed matter under directional light, and pale cartons leaning on travertine blocks. Beige and brown stone, wood grain, black paper and pale gray studio grounds provide subdued color. Objects are cropped boldly, with enough surface detail to make material and print finishes legible.

**Transfer:** Show the new product on real stone, paper or matte studio surfaces. For a digital product, stage a single interface on a physical display or a clean neutral plane; preserve directional light and material restraint rather than adding a colorful dashboard collage.

### Clipped black disc

**Use:** Signature visual punctuation for a short closing assertion.

**Observed:** A black circular field is larger than its 900px-tall white stage. White corners remain visible around the clipped arcs, with one enormous white sentence across its center.

**Transfer:** Use one short statement about the new product's outcome; the silhouette and scale should remain more prominent than any decorative detail.

**Build:** Create a white overflow-hidden stage. Center a black circle approximately 1397px in diameter at the 1440px desktop width using border-radius:50%. Place white regular grotesk text at the circle's center, using the display recipe and a single line that fits the field. Keep it flat: no texture, gradient, border or shadow.

### Icons

**Observed:** The ending uses a thin white upward arrow with straight open diagonal arms, roughly 85px wide by 120px tall at desktop. No decorative icon set accompanies the copy.

**Transfer:** Draw the arrow as three simple SVG line segments with a consistent thin stroke. Do not surround it with a circular button.

## Section recipes

How recurring sections are built.

### First screen: Masthead and photographic opening

**Observed:** The white first screen begins with a left-aligned serif identity line at 178.6px, occupying a roughly 162px-high stripe. A small tucked menu lives at the upper-right, with a vertical scroll cue below it. Behind and below the stripe, a warm studio image spans roughly 1397px by 717px, inset 21.4px from both sides and the bottom. A seated figure is centered in the photograph, with the head below the masthead and the body extending toward its lower edge. Within the first 900px are the masthead, menu, scroll cue and complete photographic stage; there is no support paragraph or filled CTA. A second serif identity stripe and the next image follow below the fold.

**Transfer:** Open with the new identity or a very short defining phrase as an editorial masthead, then a confident full-width human or product scene. Without bespoke video, use a still photograph with the same framing. Supporting page types can shorten the media stage while retaining the masthead-to-image relationship.

**Avoid:** Do not substitute a centered SaaS headline, two pill buttons and a floating interface card; do not overlay body copy across the portrait.

**Text style:** `masthead` — Favorit Times 400 · 178.6px/1 · tracking -0.025em

### Capability wall

**Observed:** A left-aligned stack of three two-word capabilities uses the capability recipe, one word per line, at 135px with no added line gap. Most of the width remains empty. A sharp black field crosses the lower portion, causing letters over it to invert to white.

**Transfer:** Turn the new product's strongest capability nouns into a typographic wall. Preserve the crossing black/white boundary and text inversion without requiring six particular words.

**Text style:** `capability` — TWKLausanne 400 · 135px/1 · tracking -0.025em

### Dark point of view

**Observed:** Chapter rail introduces a black chapter; the Manifesto island is centered in the stage beneath it. The paragraph has a maximum width of 462.9px and uses the body-label recipe, surrounded by much more empty space than text.

**Transfer:** Distill the product's operating philosophy into a small text island, not a list of feature tiles.

**Text style:** `body-label` — TWKLausanne 400 · 23.1px/1.2 · tracking -0.01em

### Image-led proof chapter

**Observed:** A light Chapter rail precedes repeated Showcase title bands and large Tactile showcase plates. Titles use the display recipe; full-width dividing rules and 21.4px inset imagery give each item the feeling of a separate exhibition plate.

**Transfer:** Adapt the repetition to the amount of real proof available, with each plate presenting a different material, application or outcome.

**Text style:** `display` — TWKLausanne 400 · 158.6px/1 · tracking -0.025em

### Circular assertion

**Observed:** The Statement disc fills and overflows a 900px stage; a single large white sentence sits centrally across the black circle.

**Transfer:** Give a concise outcome claim its own geometric pause before conversion.

**Text style:** `display` — TWKLausanne 400 · 158.6px/1 · tracking -0.025em

### Contact and final return

**Observed:** A black Chapter rail leads into a 12-column contact grid: three compact text groups on the left and the Portrait plate on the right, with 46.3px vertical padding. Monumental contact links occupy a horizontally overflowing strip underneath. A separate full-screen Return-to-top stage ends the experience.

**Transfer:** Replace the compact information with relevant contact or next-step details and retain both the outsized link strip and spare arrow ending.

**Text style:** `display` — TWKLausanne 400 · 158.6px/1 · tracking -0.025em

## Page flow

**Storyline:** identity and human presence → capabilities and point of view → visual proof → distilled outcome → direct contact → visual return

### An image-led marketing landing page that establishes taste, capability and a direct route to contact

1. **Identity** — Editorial serif masthead over a near-full-screen studio portrait, followed by another identity stripe and image.
2. **Capability chapters** — Huge stacked nouns cross an inverted black/white boundary.
3. **Point of view** — A dark chapter contrasts its small centered prose with the preceding huge type.
4. **Proof** — Repeated giant title bands introduce wide material-rich photographs.
5. **Outcome** — A clipped circular statement provides geometric punctuation.
6. **Closing call** — Small contact details and a half-width portrait lead to monumental destination links.
7. **Return** — A lone arrow in an otherwise empty black stage offers the final interaction.

**Transfer:** Borrow the alternating scales and the typographic and geometric devices; let the quantity of evidence determine how many proof plates or chapters the new page needs.

## Writing

Declarative, pared back and taste-led. Confidence comes from naming things directly and making crisp comparisons, not from elaborate selling language.

**Do not copy:** Do not reuse the studio name, its project and client names, contact details, affiliations, portraits, logos, exact manifesto or closing claim. Write new claims that the new product can support. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal noun labels and short first-person plural assertions; the reader is not repeatedly addressed as you.
- **Rhythm:** One- or two-word labels alternate with short parallel sentences. The main prose runs as a compact paragraph, with full stops rather than exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening identity | A name and a short category word split across separate stripes. | One word per stripe | “Favorit”<br>“Studio” |
| Capability | Two-word professional nouns split into stacked words. | Two words | “Creative Direction”<br>“Product Design” |
| Point of view | A preferred quality over its less desirable alternative. | Three to five words per sentence | “Curiosity over routine.”<br>“Make over talk.” |
| Navigation and action | Plain destination noun, without promotional embellishment. | One word | “Menu”<br>“Mail” |
| Closing assertion | Short first-person plural outcome claim. | Four words | “We create value.” |

**Words and phrasing to use:** Concrete capability nouns; Short destination names; Active verbs; Parallel contrasts using over

**Avoid:** Revolutionary; Game-changing; Unlock limitless potential; Long benefit-stuffed button labels

**Rules:**

- Let imagery establish credibility before adding explanation.
- Use one clear noun for a chapter label.
- Keep the large closing sentence short enough to read as a single graphic line.

## Do's and Don'ts

### Do

- Keep all main text at weight 400; hierarchy comes from the jump between 23.1px labels and 135–178.6px display type.
- Align media and body containers to the 21.4px side inset.
- Extend 1px chapter and title rules across the full width.
- Use true #000000 for the long dark chapters.
- Make the first media plate almost screen-filling beneath the masthead.
- Use matte tactile objects and muted studio color inside images.
- Preserve the giant clipped circle and spare arrow ending.

### Don't

- Do not add a colored interface accent to compensate for monochrome type.
- Do not make the menu into a filled pill or oversized hamburger icon.
- Do not soften the media into rounded cards or add drop shadows.
- Do not replace the narrow centered manifesto with a wide body-text column.
- Do not introduce bold weights into the capability wall.
- Do not reduce proof imagery to a dense three-column thumbnail grid.
- Do not turn the ending into a conventional sitemap with many small columns.

## Motion and responsive

### Motion

**Observed:**

- The tucked menu declares a transform transition of 0.6s cubic-bezier(0.165, 0.875, 0.02, 1), returning to transform:none on hover.
- Scroll-linked title translations use transform 0.1s; manifesto spans use opacity 0.1s. The opening canvas declares opacity 1s linear.
- Sticky identity stripes and chapter labels persist while their respective chapters move; proof titles and closing links are horizontally translated.

**Transfer:**

- Use motion to reveal typographic edges and change black/white relationships rather than to animate decorative ornaments.
- Maintain legible settled states for the manifesto and reachable links in the horizontal strip.

**Unknown:**

- Exact scroll interpolation, circle scaling timing and return-arrow interaction implementation are not established.

### Responsive

**Observed:**

- Declared CSS width boundaries include 600px, 900px, 1200px, 1500px and 2560px, with adjacent fractional max-width values.
- Masthead, body-label size and main gutter have fluid formulas.

**Transfer:**

- Retain the fluid masthead and gutter formulas, but allow new names to fit without truncating essential words.
- On narrow screens, stack contact information and portrait while preserving the black chapter; keep the large destination strip usable through wrapping or deliberate horizontal navigation.

**Unknown:**

- Narrow-screen layouts and mobile motion behavior are not established; the stacking guidance is an adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
