# THE1 — civic poster theatre

## Overview

A light, assertive editorial style with the scale of public signage and the warmth of a lived-in place. Dense grey and near-black grotesk typography is interrupted by grassy green, golden yellow, pink and coral blocks. Architectural cutouts, candid photography and expanding film windows give the otherwise sparse compositions a theatrical sense of movement. It suits destination brands, physical products and culture-led services with a strong visual world.

### Essentials

- Headlines behave like oversized posters rather than centered introductions: regular grotesk at 215px, 0.8 line height and -0.06em tracking, with short phrases alternating between right and left edges.
- The opening keeps the sales pitch in a corner: 20px page edges, a right-aligned two-line statement above a left-aligned changing descriptor, then a 336px support block and a four-column image strip entering within the first 900px.
- Controls are deliberately tiny against the typography: dark pills are 30px high with 6px 14px padding and 15px text; the fixed menu is a 42px dark circle.
- Grey is the continuous ground, not white: #d9d9d9 carries most narrative sections; #1f1f1f carries text. Green, pink, yellow and coral appear as hard-edged image backings and concentrated full-screen chapters, not a wash across every section.
- Proof becomes a numbered color spectacle: immense dark numerals occupy most of a 900px panel, while a narrow 284px explanation sits low beside them. Sliding panels retain colored slivers of their predecessors.
- Images break the grid without decorative frames: use color-backed cutouts, an edge-clipped 317px-wide captioned filmstrip, and a circular media aperture that expands toward full bleed. Without film, use still imagery in the same masks.
- The ending is a word sculpture, not merely a link list: a near-full-width dark wordmark is overlapped by unevenly sized color-backed product images, then resolves into five compact footer columns with 10px gaps.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sign yellow | `#fbb833` | `--color-yellow` | surface, background, accent | One numbered chapter, one product-image backing, and the practical information band. |
| Signal coral | `#fa4d43` | `--color-coral` | surface, background, accent | Product-image backings and a numbered chapter; keep text dark. |
| Entrance green | `#027b49` | `--color-green` | surface, background, accent | Product-image backings, a numbered chapter and small category markers. |
| Poster pink | `#f19ec8` | `--color-pink` | surface, background, accent | Product-image backings and a numbered chapter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Poster black | `#1f1f1f` | `--color-ink` | text, background, action, border | All main lettering, rules, active index rows and filled controls. |
| Concrete grey | `#d9d9d9` | `--color-canvas` | background, text | Continuous page ground and reversed text on dark controls. |

## Typography

- **KH Teka** — All narrative text, labels and controls; Regular is the main cut and Medium supplies restrained emphasis. Compact contemporary grotesk with open counters and emphatically tight setting, never a heavy display font. If unavailable, use **Inter**. Use 400 and 500; preserve negative tracking and tune line breaks to maintain the broad poster silhouette. Font stack: "KH Teka", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | KH Teka | 400 | 215px | 0.8 | -0.06em | Monumental narrative statements, major section titles and the second and third lines of the opening. |
| opening-line | KH Teka | 400 | 215px | 0.7 | -0.06em | The tightly stacked first line of the opening statement. |
| section-heading | KH Teka | 400 | 60px | 1 | -0.06em | Introductory proposition and the question introducing numbered chapters. |
| lead | KH Teka | 400 | 26px | 1.1 | -0.03em | Feature explanations, substantial narrative paragraphs and contact lead-ins. |
| lead-emphasis | KH Teka | 500 | 26px | 1.1 | -0.03em | Short benefit labels above explanatory paragraphs. |
| body | KH Teka | 400 | 18px | 1.1 | -0.03em | Supporting copy, addresses and direct contact links. |
| label | KH Teka | 500 | 18px | 1 | -0.03em | Product category, image-card titles and footer column labels. |
| caption | KH Teka | 400 | 15px | 1.2 | -0.03em | Buttons, image captions, small index rows and conversational action prompts. |

**Notes:**

- The scale jumps from 26px explanation to 60px proposition to 215px spectacle. Do not fill every gap with extra heading sizes.
- Negative tracking doubles proportionally for display and section-heading roles. Body text stays tightly set at -0.03em.
- Use sentence case throughout the narrative. Reserve large uppercase letterforms for the closing word sculpture.
- Medium is visual weight 500 even though the individually named font file uses a 400 CSS weight.

## Layout

**Density:** Airy at section scale, compact within text blocks: monumental words and images are surrounded by long empty intervals, while paragraphs and captions are tightly packed.

### Spacing

**Spacing system:**

- **step** 10px — Main spacing rhythm; 20px, 30px, 40px, 100px and 130px are recurring multiples. Small control details use their own values.

| Value | Use |
| --- | --- |
| 10px | Small vertical stacks, gallery gaps and footer column gaps. |
| 20px | Page side inset, opening image-grid gap and panel bottom inset. |
| 30px | Narrative copy to action row and image-card content spacing. |
| 40px | Number-to-copy gap and section bottom breathing room. |
| 100px | Proposition-to-explanation separation. |
| 120px | Opening space before the contact chapter. |
| 130px | Question-heading top padding and practical-band internal separation. |
| 170px | Top inset of numbered full-screen panels. |

### Containers and grids

- **edge canvas**: side padding 20px. Fluid full-width composition; at 1440px the content spans 1400px rather than a centered narrow container.
- **opening image grid**: 4 columns · gap 20px. Four equal 335px image cards across the desktop canvas.
- **offset narrative**: max width 1050px. Proposition begins about one quarter into the page; the 525px explanation below occupies the right half of that proposition.
- **media index split**: 2 columns · gap 10px. A 340px left rail of text and compact navigation sits beside a 1050px photographic stage at desktop width.
- **practical stage**: max width 750px. Central information graphic with a narrow identifier column to the left and an explanatory column to the right.
- **footer columns**: 5 columns · gap 10px · side padding 20px. Five equal 272px columns on desktop; contact, direct links and compact legal explanation sit below the word sculpture.

## Corner radius

| Element | Radius |
| --- | --- |
| action pills | 30px |
| menu circle | 100px |
| media aperture | 50% |
| image cards and bands | 0px |

## Surfaces and depth

### Surfaces

#### Concrete canvas · level 0

**Use:** Continuous narrative ground.

**CSS:** `background: #d9d9d9; color: #1f1f1f`

**Observed:** Untextured flat grey persists across introductions, photo galleries, contact and footer.

**Transfer:** Let imagery and type supply material richness; keep the underlying canvas flat.

#### Solid color stage · level 0

**Use:** Numbered proof chapters and practical information.

**CSS:** `background: #fbb833; color: #1f1f1f; border-radius: 0px; box-shadow: none`

**Observed:** Yellow, coral, green and pink are separate opaque panel variants with dark lettering and sharp edges.

**Transfer:** Assign a stable color to each content category and repeat it in image backings and small markers.

#### Dark control · level 1

**Use:** Filled actions and selected index rows.

**CSS:** `background: #1f1f1f; color: #d9d9d9; box-shadow: none`

**Observed:** Dark elements are small functional anchors against much larger text and image fields.

**Transfer:** Use for selected state and action hierarchy rather than making a dark page theme.

## Components

### Corner navigation

**Use:** Persistent orientation without a conventional horizontal link bar.

**CSS:** `position: fixed; top: 20px; left: 20px; right: 20px; display: flex; justify-content: space-between; align-items: center; z-index: 10`

**Observed:** A compact dark wordmark sits at the left and the Circular menu at the right, floating directly over every section.

**Transfer:** Use the new identity as a small corner anchor; keep navigation visually subordinate to the poster.

### Circular menu

**Use:** Compact menu trigger.

**CSS:** `width: 42px; height: 42px; background: #1f1f1f; border-radius: 100px`

**Observed:** Two thin grey horizontal strokes are centered inside the dark disc. It stays at the upper-right edge.

**Transfer:** Keep the two-line glyph rather than replacing it with a text-heavy menu bar.

### Primary pill

**Use:** Short discovery and direct conversion actions.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #1f1f1f; color: #d9d9d9; border-radius: 30px; padding: 6px 14px; height: 30px; box-sizing: border-box`

**Text style:** `caption` — KH Teka 400 · 15px/1.2 · tracking -0.03em

**Observed:** Label only, without an arrow; often paired inline with a short conversational question. Width follows the label.

**Transfer:** Keep the action visibly small beside the headline; let the headline do the persuading.

### Outline pill

**Use:** Secondary contact and external-information actions.

**CSS:** `color: #1f1f1f; background: transparent; border: 1px solid #1f1f1f; border-radius: 30px; padding: 6px 14px; height: 30px; box-sizing: border-box`

**Text style:** `caption` — KH Teka 400 · 15px/1.2 · tracking -0.03em

**Observed:** Same compact silhouette as the filled pill, but a delicate outline allows the underlying grey or yellow surface to remain visible.

### Color backed image card

**Use:** Opening product-family strip and repeated identity imagery.

**CSS:** `background: #027b49; width: 335px; height: 385px; position: relative; overflow: hidden; border-radius: 0px`

**Text style:** `label` — KH Teka 500 · 18px/1 · tracking -0.03em

**Observed:** A photographic building cutout rises from the bottom, with its upper silhouette against a flat color. Title and availability appear beneath the image rather than inside a padded card. Pink, yellow and coral are sibling variants.

**Transfer:** Use different product views against category colors; for intangible products use a sharply isolated artifact or typographic object.

### Numbered proof panel

**Use:** Transform a short benefit into a full-screen chapter.

**CSS:** `display: flex; align-items: flex-end; gap: 40px; height: 900px; padding: 170px 0px 20px 20px; box-sizing: border-box; background: #fbb833; color: #1f1f1f; overflow: hidden`

**Text style:** `lead` — KH Teka 400 · 26px/1.1 · tracking -0.03em

**Observed:** An enormous numeral fills the left side. A low, narrow explanatory stack has a fine top rule, a Medium label and a regular paragraph. Successive colored panels overlap from the right, leaving old panels as vertical strips.

**Transfer:** Use ordinal numerals for a small set of genuine differentiators, not invented statistics.

### Captioned filmstrip

**Use:** Ambient visual proof between major chapters.

**CSS:** `display: flex; align-items: center; gap: 10px; overflow: hidden`

**Text style:** `caption` — KH Teka 400 · 15px/1.2 · tracking -0.03em

**Observed:** Five images around 317px wide cross the viewport with unequal heights and clipped edge items. Tiny captions sit below; a circled marker or several colored markers precede the caption.

**Transfer:** Mix product details, surroundings and human use rather than repeating the same view.

### Feature index

**Use:** Compact navigation paired with a dominant media stage.

**CSS:** `color: #1f1f1f; display: flex; flex-direction: column; gap: 10px`

**Text style:** `caption` — KH Teka 400 · 15px/1.2 · tracking -0.03em

**Observed:** The index is anchored low in the left rail beneath narrative copy. Fine rule above, compact text rows below; active row reverses to grey on black. Colored circular category markers align at row ends.

**Transfer:** Pair capability names with meaningful category dots; make the selected image the primary proof rather than expanding cards.

### Footer columns

**Use:** Practical closure beneath the monumental identity scene.

**CSS:** `display: flex; gap: 10px; padding: 40px 20px 20px; color: #1f1f1f`

**Text style:** `body` — KH Teka 400 · 18px/1.1 · tracking -0.03em

**Observed:** Five open columns without boxed backgrounds. Medium labels precede direct contact and legal links; the final column contains a smaller explanatory paragraph.

**Transfer:** Keep the footer functional and compact after the oversized art; adapt column contents to the new service.

## Imagery and graphics

### Color cutout architecture

**Use:** Opening strip, contact hero and closing collage.

**Observed:** Low-angle red-brick architecture is sharply isolated against opaque green, pink, yellow and coral skies. Buildings anchor to lower edges and are often intentionally larger than their rectangular frames. There are no shadows, frames or gradients.

**Transfer:** Isolate a real product, tool or artifact against the same flat color fields, preserving natural texture and a strong recognizable silhouette.

**Build:** Use a transparent PNG or masked photographic layer inside an overflow-hidden rectangular div. Fill the div with one palette accent; anchor the subject bottom-right and enlarge until part of it crosses the side edge. Keep the upper portion as uninterrupted flat color.

### Lived in photographic world

**Use:** Immersive proof stage and captioned galleries.

**Observed:** Daylit interiors with plants, timber, copper, glass and people are interspersed with industrial waterfront views. Natural light, warm-neutral grading and believable use replace glossy synthetic renders. Large scenes fill about three quarters of a viewport; small gallery images retain varied aspect ratios.

**Transfer:** Photograph the product in real use and show its surrounding culture. Keep natural material texture and occasional human motion rather than a uniformly posed studio library.

### Expanding media aperture

**Use:** Immersive narrative transition through oversized statements.

**Observed:** A central circular film window floats over giant dark words on grey, grows until it reaches the screen edges, then becomes a full-bleed scene. Other passages use rectangular stills floating at uneven scales over the typography.

**Transfer:** Use a documentary clip or a single detailed still that can sustain enlargement; preserve the image-to-type overlap even without video.

**Build:** Place a centered media layer above a display-text layer. Start with a circle around 520px wide on a 1440px canvas using clip-path: circle(50%); enlarge the aperture with scroll until the media covers the viewport. Use object-fit: cover. For the collage passage distribute three to five rectangular images around the edges, leaving major words legible.

### Closing word sculpture

**Use:** Memorable identity-scale ending before functional links.

**Observed:** A dark custom wordmark spans almost the entire 1400px content width on grey. Uneven green, pink, yellow and coral photo tiles overlap its strokes, with some extending beyond the viewport. The result is graphic and architectural rather than a standard footer logo.

**Transfer:** Create a broad typographic sculpture from the new product's short name or a brief promise. Keep oversized dark letterforms and overlapping color-backed images even if the product has no custom identity artwork.

**Build:** Set a short uppercase word in a heavy grotesk, convert to SVG paths and fit it across a 1400px stage. Let visible letter height approach 400px at desktop scale. Layer three to four sharp rectangular photo tiles of roughly 200px–320px width over separate strokes, at deliberately unequal vertical positions. Use the same cutout treatment as the opening.

### Monochrome practical diagram

**Only for:** location or wayfinding information

**Use:** The bright practical information band.

**Observed:** A central yellow-on-yellow map uses dark labels and simple circular or square markers, with a small overview map in the left column and concise directions on the right.

**Transfer:** For non-location content use a workflow, coverage or system diagram, retaining the tonal single-color ground and simple dark annotations.

**Build:** Draw a central SVG diagram up to 750px wide. Use the yellow stage as the base, low-opacity ink for structural lines and opaque ink for labels. Differentiate nodes with circles and squares rather than adding new hues.

### Icons

**Observed:** Sparse utilitarian marks: a menu made of two 24px by 1px grey strokes, small circled numerals, colored category discs, and basic dot/square map markers. Icons sit with captions and indexes rather than inside decorative feature-card badges.

**Transfer:** Use elementary geometry and typographic numerals. Retain a consistent category-color mapping and always accompany color markers with readable text.

## Section recipes

How recurring sections are built.

### First screen: Corner pitch poster opening

**Observed:** The Concrete canvas fills the first screen. Corner navigation floats above the composition. The first two headline lines are right-aligned and span roughly the right two thirds, at 215px with tightly stacked 0.7 and 0.8 line heights; the changing one-word descriptor occupies the left half beneath them. A 336px block low on the right contains a Medium category label, a two-line 18px support sentence and a conversational prompt beside Primary pill. The four Color backed image cards enter around 715px, so the first 900px shows their upper architectural silhouettes, not their full captions. Complete cards and availability information continue below the fold.

**Transfer:** Write a short audience-focused statement and a vivid descriptor that fit this alternating-edge composition. Use four isolated product views or typographic artifacts on color fields when architectural media is unavailable. Detail or informational pages can open with a single monumental title and the same corner pitch alignment.

**Avoid:** Do not center the headline over a large CTA pair or place a dashboard mockup above the opening words. Do not replace the bottom color strip with a generic rounded hero photograph.

**Text style:** `opening-line` — KH Teka 400 · 215px/0.7 · tracking -0.06em

### Offset proposition

**Observed:** A 60px proposition starts one quarter into the content width, spanning about 1050px. After a 100px vertical interval, a 525px right-aligned column contains tightly set 26px explanation; a small conversational prompt and Outline pill close it.

**Transfer:** Use for the core explanation and one concrete piece of context. Keep it visually asymmetric rather than turning it into a centered manifesto.

**Text style:** `section-heading` — KH Teka 400 · 60px/1 · tracking -0.06em

### Numbered color chapters

**Observed:** A 60px question on grey introduces Numbered proof panels. The 900px stages stack sideways in coral, yellow, green and pink; dark numerals almost fill the height and short ruled explanations sit low beside them.

**Transfer:** Compress a set of proof points into a bold numbered device. Preserve the numeral-versus-small-copy contrast wherever the device appears; the number of chapters can change.

**Text style:** `lead-emphasis` — KH Teka 500 · 26px/1.1 · tracking -0.03em

### Immersive sentence landscape

**Observed:** Long statements are broken into huge 215px fragments across grey, alternating left and right alignment with unusually broad intervals. Captioned filmstrips, scattered rectangular stills and Expanding media aperture interrupt the text; full-bleed media carries oversized light-grey words near its lower edge.

**Transfer:** Turn a short product story into a spatial sentence with real visual proof between clauses. Use still media and clipping if film production is impractical.

**Text style:** `display` — KH Teka 400 · 215px/0.8 · tracking -0.06em

### Indexed capability stage

**Observed:** A monumental section title introduces a 900px media composition. A 340px rail holds a 26px lead and 15px supporting paragraph above a low Feature index. A large sharp-edged photograph occupies the remaining 1050px; selected index rows reverse to black as scenes change.

**Transfer:** Use for tangible capabilities or use cases, keeping text concise enough that the image remains the argument.

**Text style:** `display` — KH Teka 400 · 215px/0.8 · tracking -0.06em

### Direct contact chapter

**Observed:** A full-width rule and 215px invitation lead into sparse copy on the left, direct contact details in a narrow adjacent stack, and a large green-backed cutout image on the right. A small Primary pill serves a practical action rather than competing with the title.

**Transfer:** Close the sales narrative with a human next step, one direct action and credible contact routes.

**Text style:** `display` — KH Teka 400 · 215px/0.8 · tracking -0.06em

### Bright practical band

**Observed:** A yellow edge-to-edge stage has 20px side padding and 40px bottom padding. An oversized chapter title gives way to a three-part composition: identifier and action on the left, central diagram up to 750px wide, and ruled explanatory text on the right.

**Transfer:** Use for implementation, access or getting-started information. Keep the bright band distinct from the grey narrative.

**Text style:** `display` — KH Teka 400 · 215px/0.8 · tracking -0.06em

### Identity finale and utility footer

**Observed:** Closing word sculpture sits on grey with color-backed photographic tiles moving across its dark letters. The final settled scene reveals Footer columns immediately beneath the artwork: five compact columns, not a second large CTA band.

**Transfer:** Use a short new identity or promise as the sculpture, repeat the opening's image language, and end with straightforward practical links.

**Text style:** `label` — KH Teka 500 · 18px/1 · tracking -0.03em

## Page flow

**Storyline:** audience promise → concrete proposition → numbered differentiation → immersive visual proof → indexed capabilities → direct invitation → practical guidance → identity finale

### A flagship marketing landing page that makes a place or product feel culturally distinctive before presenting practical conversion information

1. **Audience promise** — Alternating-edge giant words, a corner pitch and four color-backed product views.
2. **Core proposition** — Offset 60px summary with a dense, narrower 26px explanation below.
3. **Differentiation** — Huge numbered colored panels carrying short benefit explanations.
4. **Experiential proof** — Monumental sentence fragments intercut with photography strips, floating stills and an expanding circular film scene.
5. **Capability demonstration** — A persistent compact index drives a dominant photo stage.
6. **Closing call** — Oversized invitation, direct contact information and one small practical action.
7. **Objection handling** — A bright practical band makes access or next steps concrete.
8. **Brand recall** — Giant word sculpture repeats the color-backed images before five open footer columns.

**Transfer:** Adapt the narrative length and arrangement to the new product while retaining the signature contrast between poster-sized language, small functional controls and staged visual proof.

## Writing

Confident, sociable and lightly playful, with the directness of a poster and the conversational warmth of a host. Concrete descriptions anchor more expansive language about creativity and belonging.

**Do not copy:** Do not reuse the THE1 identity, its wordmark artwork, property names, addresses, contact details, tenant names, availability numbers, energy claims or source-specific promises. Examples illustrate sentence structure only.

- **Addressing the reader:** Speak to the reader as you; use we for the organization and a recurring short phrase for the product. Questions invite identification rather than demanding a sale.
- **Rhythm:** Headlines can be one-word descriptors or very short invitations. Longer brand statements unfold as clauses across multiple oversized lines. Support text is compact, with occasional three-part conversational cadence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Audience framing followed by an identity or temperament descriptor. | Short framing phrase plus one descriptor | “For the one who is”<br>“Driven” |
| Section question | Ask why the product is a fitting choice, then answer through proof. | 5–7 words | “Why are we the one?” |
| Benefit label | Plain first-person assertion with a single clear quality. | 3–7 words | “We are colorful”<br>“We have a lot of space” |
| Supporting line | Connect two concrete characteristics in one sentence. | One compact sentence | “Where industrial heritage seamlessly blends with modern architecture.” |
| Primary action | Brief verb-led instruction without hype. | 2 words | “Learn more”<br>“View Route” |
| Closing invitation | Direct human invitation followed by relaxed practical reassurance. | 3-word title and one short support line | “Get in touch”<br>“Then let’s touch base offline. Call us today, tomorrow, anytime.” |

**Words and phrasing to use:** you; we; at the heart of; step in; get in touch; today, tomorrow, anytime; creative; colorful

**Avoid:** revolutionary platform; 10x your business; disruptive ecosystem; limited-time offer; enterprise-grade synergy

**Rules:**

- Give every abstract quality a tangible supporting detail.
- Let a short question sit beside the action; avoid a paragraph of persuasion inside the button.
- Use clear feature nouns in indexes and descriptive captions rather than slogans.
- Keep the large type linguistically simple so its spatial arrangement remains readable.

## Do's and Don'ts

### Do

- Keep display lettering regular at 215px with -0.06em tracking, letting scale create emphasis.
- Use the 20px outer inset consistently across text, image stages and footer.
- Repeat category colors across large stages, small discs and image backings.
- Keep primary actions at 30px visual height with 15px labels.
- Let 317px gallery items extend past the viewport edges with 10px gaps.
- Use sharp rectangular media alongside the one deliberately circular expanding aperture.
- Keep explanatory stacks narrow, around 284px within numbered panels.
- End with the large dark word sculpture and five unboxed utility columns.

### Don't

- Do not turn the grey ground into pure white or a cream editorial paper.
- Do not use soft gradients to blend the four opaque accent fields.
- Do not apply 12px rounded corners or drop shadows to the photographic cards.
- Do not bold the 215px narrative headlines; Medium belongs to compact labels.
- Do not inflate every CTA into a 50px-high conversion button.
- Do not put all content inside a centered 1200px container; the poster compositions use almost the full width.
- Do not replace the caption markers with a full colorful icon library.
- Do not make every photograph the same height in the ambient filmstrips.

## Motion and responsive

### Motion

**Observed:**

- The opening descriptor changes between short qualities.
- Numbered panels slide horizontally over one another while the scene remains pinned; earlier colors survive as narrow strips at the left.
- Media grows from a circular window to full bleed; floating images and enormous words overlap through the long narrative.
- The capability stage holds its text rail while the selected row and photograph progress through scenes.
- No action transition timing or easing is established.

**Transfer:**

- Make scroll movement change composition and image scale rather than adding ornamental micro-interactions.
- Keep a readable static poster, complete proof copy and all practical actions available when the animated treatment is reduced.

**Unknown:**

- Exact scroll interpolation, animation durations and easing curves.
- Menu-open composition and interactive focus treatment.

### Responsive

**Observed:**

- Width boundaries are declared at 399px, 400px, 809px, 810px, 1199px and 1900px.

**Transfer:**

- On narrow layouts preserve alternating-edge headline intent while reducing type to avoid horizontal overflow.
- Reflow the four image cards into an accessible horizontal strip or stacked composition; retain their stable color identities.
- Stack index and image stage when the 340px rail can no longer fit beside meaningful media.
- Collapse utility columns and the practical three-part band into readable vertical groups while keeping the word sculpture as the closing visual anchor.

**Unknown:**

- Rendered mobile type sizes, side padding and exact column-collapse behavior.
- Whether all pinned desktop narrative scenes remain pinned on small screens.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
