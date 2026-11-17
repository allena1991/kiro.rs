# Atlas Motion — industrial romanticism

## Overview

An engineering-led style with the scale and atmosphere of a painted landscape. Cream grotesk typography, charcoal grounds, hairline drafting guides and sharply rectangular controls sit over cinematic close-ups, exploded technical drawings and warm pastoral imagery. It suits ambitious physical products and infrastructure, with sparse text held inside unusually expansive visual scenes.

### Essentials

- Headlines behave like parts on a drafting table: 64px SuisseIntl at weight 500, 0.906 line height and -0.03em tracking, uppercase, with separate phrases offset across the composition rather than a conventional centered stack.
- The opening is a full-window material encounter: a 900px-tall image stage, macro product imagery behind the headline, fixed navigation 32px from the sides and 16px from the top, and a small exploration cue near the bottom.
- Actions look like equipment labels: square corners, 1px cream outlines, 12px uppercase text and 28px navigation tabs; secondary reading links are compact 24px-high charcoal washes with a northeast arrow.
- Color belongs primarily to images, not UI: charcoal #181818 and cream #fffde0 organize the page, while muted peach, blue-green and copper occupy large media scenes. Vivid pink is restricted to selected parts of technical illustrations.
- Drafting guides and a technical object study are signature devices: faint paired rules cross the visual field, while a large exploded line drawing meets an oversized process verb. Use a simplified exploded SVG or layered system diagram when no physical object exists.
- The page resolves with landscape-scale language: a 150px, weight-500 sentence-case statement at 1.1 line height over painterly scenery, followed by a rectangular dark action and a 466px charcoal footer. The monumental statement, landscape treatment and restrained footer remain recognizable with new content.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#fffde0` | `--color-foreground` | text, border, action | Default marketing headings, navigation outlines and small high-contrast controls. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal canvas | `#181818` | `--color-canvas` | background | Default page ground and footer. |
| Graphite link wash | `#292929` | `--color-link-surface` | surface | Visible result of rgba(192,192,192,0.1) over charcoal, used for compact reading links. |
| Warm charcoal edge | `#2f2f2c` | `--color-hairline` | border | Visible result of cream at 0.1 opacity over charcoal; paired section and footer separators. |
| Warm graphite text | `#72726b` | `--color-muted` | text | Visible result of rgba(204,203,189,0.5) over the charcoal canvas; footer group labels, legal links and subdued identity treatment. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial pages | Editorial gray | `#999999` | `--color-editorial-heading` | text | Oversized lightweight article titles. |
| editorial pages | Soft editorial white | `#eee8e8` | `--color-editorial-foreground` | text, border, action | Navigation and foreground treatment in the editorial variant. |

## Typography

- **SuisseIntl** — All live headings, compact labels, paragraphs and navigation. Neutral Swiss grotesk with broad open counters and firmly tightened display spacing; light editorial titles contrast with medium marketing headlines. If unavailable, use **Inter**. Use 300 and 500; retain the tight display tracking and inspect headline width. Font stack: "SuisseIntl", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | SuisseIntl | 500 | 150px | 1.1 | -0.03em | Monumental two-line closing statement in sentence case. |
| display | SuisseIntl | 500 | 64px | 0.906 | -0.03em, uppercase | Split opening headline and major cinematic section titles. |
| caption | SuisseIntl | 500 | 14px | 1.1667 | normal, uppercase | Footer grouping, supporting utility labels and small directional cues. |
| navigation | SuisseIntl | 500 | 12px | 1 | -0.03em, uppercase | Outlined navigation tabs and compact reading actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial pages | editorial-display | SuisseIntl | 300 | 184px | 0.891 | -0.03em | Single-word article title, left aligned in gray. |

**Notes:**

- Use one grotesk throughout; the engineering character comes from scale, alignment and tracking rather than introducing a monospace.
- Display and navigation recipes share -0.03em tracking; the 14px utility tier returns to normal tracking.
- For explanatory prose, use sentence case and compact lines. Recommended construction: 16px/23px for narrow supporting columns and 24px/28px for the editorial reading column, without borrowing the uppercase label treatment.
- Technical process verbs are artwork-scale words beneath the drawing. Use a 144px/1 grotesk with -0.03em tracking as a construction target at 1440px, scaling near 10vw so the verb occupies most of the right-hand stage.

## Layout

**Density:** Airy at the scene level and compact inside controls; full-window art alternates with very narrow text measures.

### Spacing

**Spacing system:**

- **rhythm** 8px, vertical — Dominant vertical spacing rhythm; keep small control internals separate from this rhythm.

| Value | Use |
| --- | --- |
| 16px | Navigation stack gap and tight content groups. |
| 20px | Desktop grid gutters; horizontal spacing is not an 8px grid. |
| 24px | Paragraph groups in narrow supporting copy and spacing before compact reading actions. |
| 36px | Space between gallery image and thumbnail strip. |
| 48px | Editorial paragraph separation and footer bottom padding. |
| 80px | Footer top padding. |
| 144px | Space above the footer's final utility row. |
| 200px | Gallery stage top padding. |

### Containers and grids

- **Content frame**: side padding 202px. At 1440px, the centered desktop content area is 1036px wide; this is a side-padded fluid frame, not a fixed maximum-width box.
- **Drafting grid**: 24 columns · gap 20px. Underlying desktop alignment grid for headlines, media and footer columns.
- **Image and argument**: gap 68px. A 930px-wide left image bleeds to the viewport edge; the right argument uses a 240px text measure with the outer 202px gutter retained.
- **Editorial measure** (only for editorial pages): max width 596px. Narrow reading column inset from the wider 772px editorial image; it is centered within the visual frame rather than aligned to the outer page gutter.

## Corner radius

| Element | Radius |
| --- | --- |
| Controls and media | 0px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Dark foundation for all scenes.

**CSS:** `background: #181818; color: #fffde0`

**Observed:** The page stays dark between media scenes; editorial pages switch the foreground to soft white.

**Transfer:** Let imagery supply broad color fields rather than changing the UI canvas per section.

#### Drafting field · level 1

**Use:** Persistent technical framing across image and dark scenes.

**CSS:** `background: transparent; pointer-events: none`

**Observed:** Thin paired vertical and horizontal guides overlay the imagery and continue across scene boundaries, much fainter than navigation borders.

**Transfer:** Use the guide construction in Drafting overlay; align important text and image edges to it.

#### Reading wash · level 1

**Use:** Compact in-text reading action.

**CSS:** `background: rgba(192,192,192,0.1); border-radius: 0px`

**Observed:** A subtle flat fill, not a raised card.

**Transfer:** Reserve this treatment for small links rather than large content panels.

#### Footer band · level 1

**Use:** Grounded ending beneath cinematic scenes or long-form text.

**CSS:** `background: #181818; border-top: 1px solid rgba(255,253,224,0.1); border-bottom: 1px solid rgba(255,253,224,0.1); padding-top: 80px; padding-bottom: 48px`

**Observed:** The edges are paired hairlines, with a second parallel line just inside the band. No radius or shadow.

**Transfer:** Finish both immersive and editorial experiences on the same flat, restrained surface.

## Components

### Fixed navigation

**Use:** Persistent identity and compact wayfinding over every scene.

**CSS:** `position: fixed; top: 16px; left: 32px; right: 32px; display: flex; justify-content: space-between; column-gap: 20px; z-index: 10`

**Observed:** Left side stacks a small identity mark over outlined navigation tabs with a 16px gap. A pale filled conversion label sits alone at the far right; no solid full-width header backdrop.

**Transfer:** Use a simple product identity and a short set of destinations; keep the image visible behind the header.

### Navigation tab

**Use:** Short destinations immediately beneath the identity.

**CSS:** `display: flex; height: 28px; border: 1px solid #fffde0; border-radius: 0px; color: #fffde0; background: transparent`

**Text style:** `navigation` — SuisseIntl 500 · 12px/1 · tracking -0.03em · uppercase

**Observed:** Tabs form a close-packed horizontal row with 6.4px gaps. Their width follows the label. Editorial variants use soft white borders and text.

**Transfer:** Keep words short; this is a compact control strip rather than a row of oversized buttons.

### Compact reading link

**Use:** Low-emphasis action below a narrow explanatory argument.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 6px 7.2px; height: 24px; box-sizing: border-box; margin-top: 24px; background: rgba(192,192,192,0.1); color: #fffde0; border-radius: 0px`

**Text style:** `navigation` — SuisseIntl 500 · 12px/1 · tracking -0.03em · uppercase

**Observed:** Label and northeast arrow occupy opposite ends of a short rectangular wash.

**Transfer:** Adapt to a deeper explanation, specification or case study without making it compete with the main conversion.

### Gallery thumbnail strip

**Use:** Material proof through a large image and a small image selector.

**CSS:** `display: flex; gap: 13px`

**Observed:** Six 67px by 48px thumbnails sit beneath a 1036px-wide image, aligned to its right edge with 36px separation. The active thumbnail is bright while the others are visibly dim.

**Transfer:** Use a tight set of real process, detail or product images; keep the main photograph dominant.

### Footer columns

**Use:** Useful destinations after the main story.

**CSS:** `display: grid; grid-template-columns: repeat(24, 1fr); column-gap: 20px; padding-left: 202px; padding-right: 202px; color: rgba(204,203,189,0.5)`

**Text style:** `caption` — SuisseIntl 500 · 14px/1.1667 · uppercase

**Observed:** A wide muted identity block sits left; destination groups, social links and stacked contact roles occupy the remaining columns. Group headings are muted and actual links are bright.

**Transfer:** Group by purpose, not decorative card boundaries; adapt contact roles to the new organization.

### Footer utility row

**Use:** Low-emphasis legal and final utility navigation.

**CSS:** `display: grid; grid-template-columns: repeat(24, 1fr); column-gap: 20px; padding-top: 144px; padding-left: 202px; padding-right: 202px; color: rgba(204,203,189,0.5)`

**Text style:** `caption` — SuisseIntl 500 · 14px/1.1667 · uppercase

**Observed:** A widely distributed single row closes the band; the year is placed at the far right.

**Transfer:** Retain the long breathing space above this row rather than squeezing the footer to its content.

### Scroll progress rail

**Use:** A spare positional signal on the far right edge.

**CSS:** `position: absolute; right: 0px; width: 10px; height: 200px; background: #fffde0`

**Observed:** The solid vertical marker advances through the long visual story; editorial pages use soft white.

**Transfer:** Keep it subordinate to the scene and separate from the drafting guides.

## Imagery and graphics

### Material encounter

**Use:** Opening scene and close-up proof images.

**Observed:** A tightly cropped motor held by textured white work gloves fills the screen. Shallow depth of field, low saturation, warm gray shadows and a dark veil let cream text remain legible. Later close-ups reveal glossy copper windings against cool translucent workshop trays.

**Transfer:** Photograph the new product's material or making process at close range. For a digital product, use a tactile hardware context or a closely framed, materially lit system artifact instead of a generic laptop mockup.

### Painted world

**Use:** Broad atmospheric scenes, argument imagery and the monumental closing statement.

**Observed:** Painterly mountains, expansive cloud formations and a low industrial building share peach sunset light, dusty blue-green shadows and visible brush or canvas grain. Images either fill the viewport or appear as crisp unrounded rectangles; they are not blurred gradients.

**Transfer:** Create a believable world around the product using landscape or architecture with the same warm-cool balance. A high-quality still with a subtle painted texture is the minimum acceptable alternative to a moving scene.

**Build:** Start from a landscape photograph or original illustration with a low horizon. Grade highlights toward peach and shadows toward muted blue-green, lower saturation, then overlay an SVG feTurbulence grain layer at low opacity and a subtle woven canvas texture. Keep cloud silhouettes and terrain recognizable; do not replace them with radial blobs.

### Exploded technical study

**Use:** Signature explanation of process or capability.

**Observed:** A large cream wireframe assembly tilts diagonally from lower left to upper right on charcoal. Separated parts reveal internal construction; selected pieces become vivid pink in the final innovation state. Tiny annotations flank the drawing and a huge uppercase process verb anchors its base.

**Transfer:** Create an exploded view of the new object or system, using recognizable functional layers. For software, separate data, processing and output planes in the same isometric language.

**Build:** Draw three to five separated SVG groups along a diagonal axis, with 1px cream outline strokes, no default fill, and repeated offset paths for lamination or hatching. Place the assembly across roughly 600px by 640px of a 1440px stage. Highlight only one functional group with rgba(246,88,147,1), keeping the surrounding diagram monochrome.

### Drafting overlay

**Use:** Signature framing on cinematic and technical scenes.

**Observed:** Faint paired rules divide the view into broad drafting bays; extremely subdued organic contour lines texture dark scenes behind the straight guides.

**Transfer:** Carry the paired-line structure and low-contrast topographic texture into new scenes without turning the page into a dense graph-paper pattern.

**Build:** Use an SVG overlay spanning the stage: paired 1px vertical strokes separated by 8–10px at major content divisions, plus paired horizontal strokes around the headline or illustration bands. Set strokes to rgba(255,253,224,0.1). Behind them add a few irregular nested contour paths at rgba(255,253,224,0.025), over a darkened image or charcoal field.

### Dark system portrait

**Use:** A dramatic chapter transition into a system overview.

**Observed:** A near-black robotic head and upper torso emerge centrally from a textured dark background; the uppercase section title is arranged around its face. Below it, transparent text panels use thin outlines and small bright square corner markers.

**Transfer:** Use a centrally lit product silhouette or abstract system assembly with the same very low contrast. Keep the subject secondary to the cream title; adapt the corner-marked panels to a few meaningful capability explanations.

**Build:** Place a grayscale product cutout centrally on charcoal, lower its opacity and add a dark bottom gradient. Arrange title fragments around the subject. Construct transparent panels with 1px rgba(255,253,224,0.15) outlines and 4px cream squares at each corner; stagger their vertical placement instead of creating a uniform dashboard.

### Painted editorial frontispiece

**Only for:** editorial pages

**Use:** A visual metaphor before the long-form argument.

**Observed:** A classical figure bearing a globe is painted in warm peach and muted green, presented as a 772px by 432px unrounded image below a gray title.

**Transfer:** Choose an original historical, material or cultural metaphor appropriate to the new argument; keep the painted texture and warm subdued palette rather than literal product advertising.

### Icons

**Observed:** Very few icons: a northeast arrow on reading and conversion actions, small process-position dots and fine technical annotations. Marks share the cream or soft-white foreground.

**Transfer:** Use text and sparse directional arrows rather than a library of filled feature icons.

## Section recipes

How recurring sections are built.

### First screen: Material stage opening

**Observed:** A full-bleed macro photograph occupies the entire first 900px. From back to front: material image, warm darkening veil, faint Drafting overlay, split cream headline, then Fixed navigation and the far-right Scroll progress rail. The 64px uppercase headline occupies the middle of the view: its first phrase is a two-line block left of center and its concluding phrase sits lower and farther right. The main object is much larger than the text and runs behind it. Within the first screen the identity, outlined destination tabs, small pale top-right conversion control and bottom-right exploration cue are visible. A longer support statement and scenic continuation appear after scrolling, not as a conventional hero paragraph-and-button stack.

**Transfer:** Use a tight image of the new product or its making; without motion assets, create an equally immersive still with a strong focal detail. Break the promise into two meaningfully offset fragments. Editorial pages instead open with a 184px gray title above a painted frontispiece on the dark Drafting field.

**Avoid:** Do not shrink the main image into a rounded card, put the headline in a centered text column, or stack a large pair of CTA buttons directly beneath it.

**Text style:** `display` — SuisseIntl 500 · 64px/0.906 · tracking -0.03em · uppercase

### Cinematic application scene

**Observed:** A painted mountain environment fills the stage; a product floats prominently near the center, with a short uppercase headline above and compact sentence-case supporting text below. A small central statement can also stand alone against the scenery.

**Transfer:** Show the product in its larger operating world and explain one practical benefit; keep the setting coherent with Painted world rather than inserting unrelated stock photographs.

**Text style:** `display` — SuisseIntl 500 · 64px/0.906 · tracking -0.03em · uppercase

### Technical process chapter

**Observed:** The Exploded technical study dominates a charcoal stage. A small chapter number and dot sequence sit left, a compact process heading sits above, annotations frame the drawing, narrow support copy occupies the left margin and an artwork-scale verb runs across the lower right.

**Transfer:** Use process verbs and one clear explanation per state. The technical-study device is essential, but its number of states and position in the story can follow the new content.

### Image and argument

**Observed:** A 930px by 525px painted image bleeds off the left edge. The adjacent 240px text column is separated by 68px and holds two short paragraphs, then Compact reading link. The composition sits in a dark Drafting field.

**Transfer:** Pair a world-building image with the product's larger rationale. Use the short link to lead to the complete argument rather than expanding the scene into an essay.

### Material proof gallery

**Observed:** A large unrounded manufacturing image fills the 1036px content frame. Gallery thumbnail strip sits below it, right aligned; the surrounding dark textured field stays visible.

**Transfer:** Show concrete workmanship, product detail or operational proof. Let the images carry the section without a thick title and caption stack.

### System reveal and corner-marked panels

**Observed:** A Dark system portrait backs a centered split uppercase title. The following capability explanations form transparent outlined panels with square corner markers, with a taller middle panel and generous dark space around them.

**Transfer:** Adapt the content to the new system's architecture, operational advantages or organization; preserve the silhouette-to-panel transition without requiring any specific topics.

**Text style:** `display` — SuisseIntl 500 · 64px/0.906 · tracking -0.03em · uppercase

### Monumental closing call

**Observed:** An 890px scenic band shows peach clouds above a blue-green landscape. A centered two-line statement uses closing-display and spans most of the frame. Beneath it is a dark square-cornered rectangular action with an uppercase label and northeast arrow, visually about 266px by 85px. Footer band follows directly.

**Transfer:** Use two short parallel assurances grounded in the product's real value. Preserve the large language, painted scenery and solitary action, with the exact section placement guided by the new story.

**Text style:** `closing-display` — SuisseIntl 500 · 150px/1.1 · tracking -0.03em

### Grounded footer

**Observed:** The 466px Footer band starts with 80px padding and contains Footer columns followed by Footer utility row. Bright links, muted headings and a large subdued identity give the ending a low, horizontal silhouette.

**Transfer:** Keep the same footer construction after either cinematic or editorial content; replace groups and contact roles to fit the new product.

**Text style:** `caption` — SuisseIntl 500 · 14px/1.1667 · uppercase

### Editorial argument and terse ending

**Only for:** editorial pages

**Observed:** The gray editorial-display title precedes a 772px image with 24px separation. The 596px reading column begins with 84px top padding; paragraphs are separated by 48px. The argument ends in a sequence of very short standalone statements, finishing with a one-word imperative before the shared Footer band. There is no scenic conversion band on this page type.

**Transfer:** For essays or manifestos, keep the argument linear and visually sparse; shorten the final paragraphs into an unmistakable ending instead of appending unrelated marketing modules.

**Text style:** `editorial-display` — SuisseIntl 300 · 184px/0.891 · tracking -0.03em

## Page flow

**Storyline:** Material promise → contextual demonstration → technical explanation → deeper rationale and proof → system view → decisive ending → practical navigation.

### Immersive product or company landing experience

1. **Promise** — Full-window macro scene with offset headline fragments and persistent compact navigation.
2. **Contextual demonstration** — Painterly operating environment introduces a recognizable product and concise practical promise.
3. **Technical explanation** — Numbered exploded drawing states pair huge process verbs with narrow explanatory copy.
4. **Rationale** — A broad painted architectural image is paired with a small argument and reading link.
5. **Material proof** — Large photographic gallery with a small right-aligned selector.
6. **System overview** — Dark central silhouette leads into corner-marked explanatory panels.
7. **Closing call** — Monumental sentence-case statement over painted scenery with one dark action, then a flat charcoal footer.

**Transfer:** Use the cinematic material-to-system arc for products that benefit from a sense of physical consequence; combine or reorder explanatory beats while retaining the distinctive technical study, atmospheric imagery and emphatic closing language.

### Long-form positioning or manifesto

1. **Framing** — Oversized lightweight gray title and painted metaphor image on a textured dark ground.
2. **Argument** — Narrow, offset reading measure with short paragraphs and unusually generous paragraph spacing.
3. **Resolution** — Paragraphs contract into short directives and a final one-word imperative.
4. **Practical navigation** — Shared charcoal footer without the scenic conversion scene.

**Transfer:** Use this scoped variant for a focused written argument, retaining the shared navigation and drafting material while reducing visual scene changes.

## Writing

Declarative, technically literate and quietly ambitious. Concrete making and operational language gives large claims weight; the tone is direct rather than chatty.

**Do not copy:** Do not reuse the Atlas name, logo, product or platform names, distinctive slogans, contact details, manufacturing claims, compliance assertions, team credentials or performance promises. Write original claims supported by the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The product or organization is usually the subject. Supporting copy uses we and your when describing collaboration; actions use direct imperatives.
- **Rhythm:** Headlines are short and compressed, often split into two balanced phrases. Supporting paragraphs are compact; longer arguments alternate explanation with sharply abbreviated standalone statements.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A category-defining noun phrase that locates the product's role in a larger system. | 5–8 words | “The physical layer of autonomy” |
| Context headline | A practical promise shaped as a short statement, often in two lines. | 4–7 words | “Built to ramp with you” |
| Closing statement | Two parallel fragments with matched cadence and concrete operational assurances. | 6–10 words | “Built to spec. Ready to scale.” |
| Primary action | A direct verb naming the relationship or next step. | 2–4 words | “Become a partner”<br>“Order Now” |
| Argument ending | Reduce the final thought to a plain imperative. | 1–5 words | “Move.” |

**Words and phrasing to use:** build; design; systems; physical; requirements; scale; make; process

**Avoid:** magic; game-changing; delightful; supercharge; all-in-one; effortless

**Rules:**

- Make each claim about a real capability or operational consequence.
- Use sentence case for prose even when headings and utility labels are uppercase.
- Let a large statement stand alone; do not append a second abstract slogan underneath it.
- Use parallel constructions to connect specification, making and expansion.
- Keep action labels literal and brief; reserve expansive language for the scenes.

## Do's and Don'ts

### Do

- Set marketing display text at 64px/0.906 with -0.03em tracking and weight 500.
- Keep the header detached from any full-width opaque band, with 32px side offsets.
- Use 1px outlines and square corners for navigation tabs.
- Align media, footer groups and split titles through a 24-column grid with 20px gutters.
- Carry paired low-opacity drafting rules across visual scene changes.
- Give the closing statement its own 150px/1.1 sentence-case treatment.
- Keep gallery selectors small at 67px by 48px so the main image dominates.
- Use the 184px weight-300 gray title only for editorial content.

### Don't

- Do not turn every capability into a rounded, shadowed SaaS card; transparent panels use fine edges and square corner markers.
- Do not apply cream as a full-page light background; it is primarily foreground and small-control color.
- Do not use pink as a general CTA color or broad background; it belongs to selective technical-art emphasis.
- Do not add a monospace font merely to signal engineering; the label tier is the same grotesk.
- Do not flatten the 150px closing line into the ordinary 64px uppercase heading treatment.
- Do not brighten inactive gallery thumbnails to match the selected one.
- Do not eliminate the 144px breathing space above the footer utility row.
- Do not decorate feature paragraphs with a repeated set of large filled icons.

## Motion and responsive

### Motion

**Observed:**

- Compact actions and related surfaces declare opacity transitions of 0.2s ease-in-out.
- The long visual narrative uses sticky section interiors and scroll-linked scene changes; process numbers, exploded parts and large verbs change with progression.
- Some link labels use a flipping treatment.

**Transfer:**

- Preserve the sense of a continuous staged scene rather than isolated card animations.
- Let process-state changes update drawing, verb and annotation together; a static implementation can present the same states as coherent individual scenes.

**Unknown:**

- Exact scroll interpolation, scene timing and label-flip choreography are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 420px, 600px, 768px, 992px and 1200px; neighboring max-width rules use 600px, 768px, 992px and 1200px.

**Transfer:**

- On narrow layouts, reduce the scenic headline scale while keeping its two offset fragments legible over one focal object.
- Collapse the wide image-and-argument pairing into image followed by the narrow argument, keeping square image edges.
- Keep the technical drawing recognizable before retaining all its marginal annotations; prioritize the process verb and one explanation.

**Unknown:**

- Mobile typography, navigation arrangement and scene heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
