# Portal — painted horizons, tactile tools

## Overview

A welcoming software style that pairs literary, narrow serif headlines with compact sans-serif explanations. A pale gray page carries small, tactile interface illustrations, while a starry blue-and-pink landscape turns the opening into a little illustrated world. It suits creative tools and service products that need practical explanation without losing personality; the reading experience is narrow, airy and distinctly handmade around the edges.

### Essentials

- Literary promises rather than oversized tech slogans: Perfectly Nineties at 48px/1 for opening and closing, 36px/1 for section leads, all weight 400 with normal tracking.
- An illustrated world contains the product: a full-width blue-to-lilac twilight sky, tiny stars and painted hills surround a centered 900px-wide glass-framed interface; the headline starts after 180px of top space.
- Actions feel like small physical controls: 48px-high pills with 50px radii and 36px horizontal padding; the opening uses pale gray with violet text, while the closing uses electric blue with white text.
- Most of the story lives on #f7f7f7 in a 600px reading column: reserve saturated color for the opening scenery, miniature illustrations, blue process markers and the final action, rather than full-page colored bands.
- Capabilities are illustrated as objects, not boxed marketing cards: white UI fragments overlap, tilt and cast short soft shadows beside 18px semibold headings; include this tactile demonstration language even when it must be drawn from simplified interface fragments.
- The page has a human, illustrated aftertaste: a white memo sheet tilted -2deg, a centered serif closing invitation and a painted ridge along the bottom. Carry these devices into a new page with an original short letter and original landscape silhouettes.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric action blue | `#007aff` | `--color-blue` | action, accent, link | Closing action, process circles, comparison rule, price seal and link hover. |
| Twilight button ink | `#535398` | `--color-violet` | text | Opening action text on the pale pill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text | Serif headings, capability headings and inline links. |
| Soft charcoal | `#3e3e3e` | `--color-body` | text | Paragraphs; black at 75% opacity over the pale gray canvas. |
| Muted gray | `#636363` | `--color-muted` | text | Small explanatory notes; black at 60% over the canvas. |
| Subtle dark edge | `#dedede` | `--color-edge` | border, surface | Neutral equivalent of black at 10% over the canvas; the selected navigation pill uses this alpha recipe over the sky. |
| Pale gray canvas | `#f7f7f7` | `--color-canvas` | background, action | The long-form page ground and pale opening button. |
| Milky glass | `#fdfdfd` | `--color-glass` | surface | Visible neutral equivalent of white at 80% over the canvas; actual hero glass lets the colorful scene show through. |
| Paper and reverse | `#ffffff` | `--color-white` | text, surface, border | White memo paper, interface fragments, hero lettering and glass highlights. |

## Typography

- **Perfectly Nineties** — Opening, section leads and closing headlines. Narrow, high-contrast editorial serif with soft, slightly nostalgic curves. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **Instrument Serif**. Use regular 400; preserve narrow proportions and compact line breaks. Font stack: "Perfectly Nineties", "Instrument Serif", Georgia, serif.
- **Inter** — Body copy, navigation, buttons and capability titles. Compact contemporary sans-serif, regular for explanations and semibold for action and feature emphasis. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Perfectly Nineties | 400 | 48px | 1 | normal | Centered opening promise and final invitation. |
| heading | Perfectly Nineties | 400 | 36px | 1 | normal | Left-aligned editorial section leads. |
| feature-heading | Inter | 600 | 18px | 1.3 | -0.02em | Capability rows, process step titles and memo title. |
| body | Inter | 400 | 16px | 1.35 | -0.02em | Paragraphs, navigation, lists and inline links. |
| button | Inter | 600 | 16px | 1.3 | -0.02em | Conversion actions and occasional concluding emphasis. |
| note | Inter | 400 | 12px | 1.3 | -0.02em | Short qualifications beneath a commercial claim. |

**Notes:**

- The expressive contrast comes from family, not extreme size: section serif headings are only twice the 18px feature titles.
- Keep serif tracking normal; Inter consistently uses -0.02em tracking. Body line height is 1.35, slightly looser than the 1.3 used for buttons and feature titles.
- Use sentence case and compact multi-line headings. The opening uses two stacked statements, not a bold all-caps word sculpture.

## Layout

**Density:** Airy around a compact reading core: short internal gaps and long pauses between illustrated chapters.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Capability title-to-paragraph gaps and compact internal stacks. |
| 12px | Paragraph separations and claim-to-qualification spacing. |
| 16px | Opening text stack and small horizontal alignments. |
| 20px | Section heading-to-body separation; process marker-to-text gap. |
| 36px | Horizontal padding inside conversion pills. |
| 40px | Major internal stacks, process row gaps and illustration-to-copy separation. |
| 45px | Memo sheet padding on every side. |
| 60px | Separation before process rows and around closing action areas. |
| 80px | Chapter padding and gaps between alternating capability rows. |
| 90px | Opening action area to the glass product stage. |
| 180px | Top space before the opening headline. |

### Containers and grids

- **reading column**: max width 600px. Centered desktop reading spine; headings and paragraphs align left within it.
- **opening copy**: max width 800px. Centered hero headline and action wrapper; paragraph stays narrower, near the reading column width.
- **capability stage**: max width 800px · 2 columns · gap 40px. Alternating illustration and copy rows. A 100px side inset alternates with the image direction; copy is approximately 330px wide.
- **benefit index**: max width 600px · 2 columns · gap 4px. Two compact columns of icon-and-label rows, each about 298px wide.
- **navigation**: side padding 60px. Full-width transparent header, with identity left and a compact three-link group right.
- **memo**: max width 660px. Slightly wider than the reading column to create the impression of a loose paper sheet.

## Corner radius

| Element | Radius |
| --- | --- |
| conversion buttons | 50px |
| navigation selection | 20px |
| hero outer glass | 50px |
| hero inner window | 40px |
| demonstration windows | 22px |
| memo sheet | 12px |
| floating UI fragments | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| opening pill | `inset 0px 1px 0px 0px rgba(255,255,255,1), 0px 0px 0px 1px rgba(0,0,0,0.15), 0px 3px 2px 0px rgba(0,0,0,0.06)` | Subtle tactile edge on the pale conversion action. |
| glass stage | `rgba(0, 0, 0, 0.03) 0px 0.6px 2.3px -0.4px, rgba(0, 0, 0, 0.04) 0px 2.3px 8.7px -0.8px, rgba(0, 0, 0, 0.08) 0px 10px 38px -1.3px` | Soft lift beneath the hero's translucent frame. |
| floating fragment | `2px 8px 2px 0px rgba(0,0,0,0.07)` | Short directional shadow that makes small UI pieces feel cut out. |

### Surfaces

#### Canvas · level 0

**Use:** The continuous background for the explanatory story.

**CSS:** `background: #f7f7f7; color: #000000`

#### Glass stage · level 1

**Use:** The main interface presentation over the illustrated opening.

**CSS:** `background: rgba(255,255,255,0.8); border: 1px solid #ffffff; border-radius: 50px; backdrop-filter: blur(10px); box-shadow: rgba(0, 0, 0, 0.03) 0px 0.6px 2.3px -0.4px, rgba(0, 0, 0, 0.04) 0px 2.3px 8.7px -0.8px, rgba(0, 0, 0, 0.08) 0px 10px 38px -1.3px`

**Observed:** A thick milky outer rim surrounds an inset window with rounded corners and luminous inner highlights. The scene continues inside the window.

**Transfer:** Use one generous frame around a real product view, with scenery visible around and behind it rather than a flat browser mockup.

#### Paper sheet · level 1

**Use:** Human commentary or a short editorial letter.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 45px; transform: rotate(-2deg)`

**Observed:** A lightly lifted sheet interrupts the otherwise unboxed story; the shadow extends softly down and left.

**Transfer:** Keep the contents typographic and personal, with a compact title, paragraphs and a signer.

## Components

### Opening button

**Use:** Single conversion action against the colorful opening.

**CSS:** `background: #f7f7f7; color: #535398; height: 48px; padding: 0px 36px; border-radius: 50px; display: flex; align-items: center; justify-content: center; box-shadow: inset 0px 1px 0px 0px #ffffff, 0px 0px 0px 1px rgba(0,0,0,0.15), 0px 3px 2px 0px rgba(0,0,0,0.06)`

**Text style:** `button` — Inter 600 · 16px/1.3 · tracking -0.02em

**Observed:** A text-only pill centered below the support paragraph. It is the opening variant, not a pair of competing actions.

### Closing button

**Use:** Final conversion action on the neutral canvas.

**CSS:** `background: #007aff; color: #ffffff; height: 48px; padding: 0px 36px; border-radius: 50px; box-shadow: rgba(140,194,255,1) 0px 1px 0px 1px inset; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Inter 600 · 16px/1.3 · tracking -0.02em

**Observed:** The same small pill silhouette becomes saturated blue to punctuate the final invitation.

### Navigation pill

**Use:** Selected link in the transparent opening navigation.

**CSS:** `background: rgba(0,0,0,0.1); color: #ffffff; height: 36px; padding: 0px 16px; border-radius: 20px; backdrop-filter: blur(7px); display: flex; align-items: center`

**Text style:** `body` — Inter 400 · 16px/1.35 · tracking -0.02em

**Observed:** The active item has a translucent dark backing; neighboring links are unfilled and softly reversed. The group sits opposite a small white identity mark.

### Inline link

**Use:** Links woven into the conversational footer paragraph.

**CSS:** `color: #000000; text-decoration-line: underline; transition: color 0.4s cubic-bezier(0.44, 0, 0.56, 1)`

**Text style:** `body` — Inter 400 · 16px/1.35 · tracking -0.02em

**Observed:** Ordinary underlined text within running prose, not an isolated arrow CTA.

**States:** Declared: hover color #007aff with underline; focus-visible not specified.

### Process marker

**Use:** Numbered guidance beside a step title and paragraph.

**CSS:** `width: 36px; height: 36px; background: #007aff; color: #ffffff; border-radius: 50px; border: 1px solid rgba(0,0,0,0.15); display: flex; align-items: center; justify-content: center`

**Text style:** `body` — Inter 400 · 16px/1.35 · tracking -0.02em

**Observed:** The marker sits slightly below the title's top edge. A 20px gap separates it from the text, and successive rows use a 40px gap.

### Memo card

**Use:** A personal explanation that changes the page's emotional register.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 45px; transform: rotate(-2deg); display: flex; flex-direction: column; gap: 24px`

**Text style:** `body` — Inter 400 · 16px/1.35 · tracking -0.02em

**Observed:** A semibold title leads several paragraphs, followed by a small portrait and signer. It is a standalone sheet, not one tile in a grid.

**Transfer:** Use an honest note on the product's purpose, signed by a real person.

### Comparison rule

**Use:** A concise commercial contrast beneath the main pricing explanation.

**CSS:** `width: 4px; height: 65px; background: #007aff; border-radius: 9px`

**Observed:** A short vertical blue bar sits to the left of an unboxed paragraph with a 16px gap; it does not form a surrounding border.

**Transfer:** Pair with a short, substantiated contrast; allow bar height to follow the paragraph.

### Benefit index

**Use:** A skimmable overview after the introductory explanation.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(50px, 1fr)); gap: 4px; padding-top: 20px; max-width: 600px`

**Text style:** `body` — Inter 400 · 16px/1.35 · tracking -0.02em

**Observed:** Small colored circular icons precede sentence-case labels. Rows stay unboxed; a little handwritten annotation points to a newly added capability.

**Transfer:** Use concise capability names and one small handwritten pointer, rather than turning every item into a large card.

## Imagery and graphics

### Twilight product world

**Use:** Signature opening environment.

**Observed:** A painted landscape fills the opening: cornflower-blue sky becomes lavender and pink at the horizon, with tiny luminous stars above dark teal hills. A small warm-colored character and vegetation ground the interface scene. The world occupies the whole width, while the pale interface floats prominently in front.

**Transfer:** Create an original illustrated environment with the same twilight light and painterly edges. The minimum version is layered vector terrain, a star field and a small original focal object behind a simplified but legible product panel.

**Build:** Layer a vertical blue, lavender and pink gradient behind several irregular SVG hill paths. Put darker teal ridges in front and cooler blue ridges behind, with thin broken contour strokes and subtle SVG turbulence texture. Scatter small white circles across the upper third at varied opacity, adding soft halos to only a few. Place the glass-framed product view centrally over the terrain, leaving an open sky behind the headline.

### Tactile interface fragments

**Use:** Alternating capability illustrations through the neutral body.

**Observed:** Small white project cards, notifications, file objects and signature panels float in overlapping stacks. Rounded corners, slight opposing tilts, edge highlights and short directional shadows make them resemble physical objects. Illustrations are roughly the same visual width as their adjacent text column.

**Transfer:** Choose one recognizable task per illustration. Reconstruct a few UI fragments with original labels, one meaningful accent and a tiny symbolic object; keep the outer canvas visible instead of putting the whole vignette in a large colored card.

**Build:** Use two to four rounded white rectangles around 300px wide, offset by 10px–30px, with small rotations in opposing directions. Apply short low-opacity black shadows and a white inset top highlight. Keep labels subdued; reserve a saturated icon or status for the focal action.

### Overlapping window fan

**Use:** Proof that the product can carry diverse visual identities.

**Observed:** Four landscape interface windows overlap horizontally. The first is nearly fully visible, with later windows peeking out to the right. Art ranges from warm painted mountains to cool blue scenes; each has a luminous rim, 22px outer corners and a roughly 416px by 273px front face.

**Transfer:** Show several real use cases or visual configurations in one compact fan. The minimum version is original artwork behind simplified product content, not four repeated empty panels.

**Build:** Stack four landscape panels in one relative wrapper with successive horizontal offsets, keeping the first above all others. Add a 5px canvas-colored outer ring and white inset highlights to separate edges. Round the artwork inside to 21px.

### Painted closing ridge

**Use:** Signature bottom edge beneath the footer.

**Observed:** A broad landscape silhouette rises from the page bottom, spanning 1152px at desktop. Pink and blue distant ridges sit behind deep blue mountains and a sunlit yellow-green foreground; the uneven painted upper edge blends into the pale canvas without a rectangular image boundary.

**Transfer:** Echo the opening's world with a different original ridge or terrain fragment. Keep it below the functional footer, so the last impression is art rather than a dark legal band.

**Build:** Draw three or more wide irregular SVG ridge paths rising toward the center. Layer a thin pink distant edge, light blue and deep blue middle ridges, then a smaller green foreground with yellow-lit patches. Add sparse contour marks and grain; clip the lower portion at the page edge.

### Icons

**Observed:** The index uses 36px circular colored pictograms with simple white glyphs. Feature areas also use 48px icons and miniature illustrated app-like objects; the closing emblem has a tactile blue rim.

**Transfer:** Use friendly simple pictograms in colored discs for the index, and a small original dimensional emblem above the closing invitation. Keep visual complexity in illustrations rather than in navigation icons.

## Section recipes

How recurring sections are built.

### First screen: Illustrated product opening

**Observed:** A transparent 80px navigation overlays the full-width Twilight product world. After 180px of top space, two centered 48px serif statements occupy roughly half the viewport width, followed by white 16px support copy in a narrower column. The Opening button sits below with about 36px of visible separation. After a 90px pause, a 900px-wide Glass stage begins in the lower half of the first screen. Behind it, stars give way to a pink horizon and hills; the illustrated world and product share the same scenery. Within the first 900px, navigation, all copy, action and the upper part of the product are visible; the lower product window extends below the fold.

**Transfer:** For another product, keep the paired promise and journey statement, one action and a generous framed demonstration set in an original twilight world. If no polished interface exists, build a small meaningful task panel in that world. A focused editorial or commercial page can open with the same serif heading and narrow reading spine rather than repeating all the long-form chapters.

**Avoid:** Do not replace the environment with a plain blue rectangle or shrink the product into a tiny card beside a left-aligned headline.

**Text style:** `display` — Perfectly Nineties 400 · 48px/1

### Editorial section lead

**Observed:** A 600px centered column uses a left-aligned 36px serif heading, then 20px to 16px charcoal body copy. Paragraph breaks use 12px. Faint horizontal dividers separate some major chapters.

**Transfer:** Lead with a benefit or contrast in a full sentence; keep explanation grounded in concrete tasks.

**Text style:** `heading` — Perfectly Nineties 400 · 36px/1

### Alternating object chapter

**Observed:** Within an 800px stage, Tactile interface fragments alternate left and right of a 330px copy column. A 40px gap separates art and copy, a 10px gap separates the 18px title and paragraph, and successive rows are separated by 80px.

**Transfer:** Show one task per row and vary the silhouette of the object stack, preserving the narrow text measure.

**Text style:** `feature-heading` — Inter 600 · 18px/1.3 · tracking -0.02em

### Process walkthrough

**Observed:** An Editorial section lead introduces a single column of Process markers and text. The list begins after 60px; 40px gaps separate rows. Each row has a compact title above a paragraph, without a surrounding card.

**Transfer:** Use as many steps as the actual workflow needs; preserve the clear blue marker and unboxed reading path.

**Text style:** `feature-heading` — Inter 600 · 18px/1.3 · tracking -0.02em

### Conversational commercial answer

**Observed:** A brief question-and-answer serif heading introduces an unboxed explanation. A blue scalloped seal carries a small percentage beside the main paragraph, a 12px note qualifies it, and a Comparison rule introduces the contrasting paragraph 40px later. The section has 80px vertical padding.

**Transfer:** Use a short factual figure in a blue seal and honest qualification below it; the device also works for a concise measured proof point.

**Text style:** `heading` — Perfectly Nineties 400 · 36px/1

### Human paper interruption

**Observed:** A Memo card slightly wider than the reading spine interrupts the regular chapters. Its -2deg tilt, white surface and signer make it feel like correspondence placed on the page.

**Transfer:** Use a concise signed viewpoint rather than an anonymous testimonial wall.

### Invitation and landscape ending

**Observed:** A small dimensional emblem sits above a centered 48px serif invitation, then 20px to centered support. A Closing button follows after a generous 60px separation. Below it, the 600px footer pairs a conversational paragraph with underlined links on the left and a small vertical utility menu on the right. A location sign-off and muted copyright lead into the Painted closing ridge; the page ends in illustration, not a dark band.

**Transfer:** Close with a direct outcome and invitation, a human sign-off and an original illustrated terrain edge. Keep utility navigation small and secondary.

**Text style:** `display` — Perfectly Nineties 400 · 48px/1

## Page flow

**Storyline:** Atmospheric promise → plain-language explanation → illustrated capabilities → workflow clarity → commercial reassurance → human viewpoint → invitation and illustrated farewell.

### A product marketing landing page that makes an administrative tool feel creative and approachable

1. **Promise** — Centered paired serif statements over an illustrated sky and large glass-framed demonstration.
2. **Product explanation** — Narrow editorial paragraphs and a two-column icon index.
3. **Capability chapters** — Alternating small object scenes and compact feature explanations, with broader editorial leads between themes.
4. **Visual proof** — An overlapping fan of customized interface windows.
5. **Workflow clarity** — An unboxed numbered walkthrough with blue circular markers.
6. **Commercial reassurance** — Conversational pricing explanation, blue seal, qualification and comparison rule.
7. **Human viewpoint** — Tilted signed memo sheet.
8. **Closing call** — Dimensional emblem, serif invitation, blue pill, conversational footer and painted terrain.

**Transfer:** Adapt the narrative to the new product's real objections and tasks. Preserve the contrast between immersive art, compact editorial explanation and tactile object demonstrations without treating the original chapter count as a template.

## Writing

Warm, practical and lightly playful. Benefits are explained through everyday frustrations and specific tasks, with occasional conversational asides rather than corporate positioning language.

**Do not copy:** Do not reuse Portal's name, artwork, character, logos, customer or founder identities, partner names, quoted wording, fee percentages, payment counts, file limits, regional availability or performance claims. Supply original assets and verified facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. The product is named in explanatory sentences; we appears sparingly in conversational opinions.
- **Rhythm:** Short declarative promises sit above fuller explanatory paragraphs. Feature titles often read as complete action phrases; questions, gentle jokes and occasional exclamation points loosen the longer story.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A personal possessive plus an attractive description of the tool, followed by a from-to journey. | 5–10 words per statement | “Your beautiful freelance toolkit.”<br>“From sending proposals to getting paid” |
| Section lead | Name the frustration, then offer a plainspoken alternative. | 10–20 words | “Stop chasing clients for payments. Instead, make paying dead simple.” |
| Support | Explain the action and the benefit in direct everyday language. | 20–60 words | “Going from sending your first proposal with [Brand] to getting paid only takes a few smooth steps. Smooth like butter.” |
| Commercial heading | Ask the reader's likely question and answer it conversationally. | 3–6 words | “Pricing? Glad you asked.” |
| Primary action | A short verb plus an immediate destination or stage. | 2–3 words | “Join beta” |

**Words and phrasing to use:** beautiful; easy; your; with style; no more; instead; give it a spin; a small conversational aside

**Avoid:** enterprise transformation; revolutionary ecosystem; synergize; unmatched excellence; aggressive scarcity

**Rules:**

- Connect attractive presentation to a concrete practical outcome.
- Use specific workflow verbs before abstract claims.
- Explain qualifications plainly beneath commercial promises.
- Let one small joke or affectionate sign-off carry warmth; keep action labels direct.

## Do's and Don'ts

### Do

- Keep serif headings at weight 400 and line height 1.
- Use the 600px reading spine to make the long story feel intimate.
- Pair 18px semibold capability titles with 16px regular explanations.
- Keep conversion pills 48px high with 36px horizontal padding.
- Let small UI illustrations overlap and tilt against the continuous pale canvas.
- Use electric blue for small high-information accents and the final action.
- Preserve a short signed paper note and an illustrated lower edge.
- Keep meaningful product content visible in the large glass stage.

### Don't

- Do not turn every capability into a bordered bento tile; the feature story is mostly unboxed.
- Do not use bold geometric sans headlines in place of the narrow regular serif.
- Do not expand ordinary paragraphs to the full 800px art stage.
- Do not make the opening action blue on blue; its pale material is part of the contrast.
- Do not apply 50px corners to the memo; its 12px corners should read as paper.
- Do not use heavy black drop shadows on the floating white fragments.
- Do not add a multi-column enterprise sitemap where the footer uses intimate prose and a short utility stack.
- Do not make blue the default background for explanatory chapters.

## Motion and responsive

### Motion

**Observed:**

- Inline link color transitions are declared at 0.4s with cubic-bezier(0.44, 0, 0.56, 1); hover turns the link blue while retaining underline.
- No matched keyframe animations are specified.

**Transfer:**

- Use the declared color transition for inline links; retain the static tilts and overlaps as part of the composition rather than assuming they require animation.

**Unknown:**

- Entrance timing, scroll choreography and button hover or focus treatments are not established.

### Responsive

**Observed:**

- Styles declare width boundaries at 809px, 810px, 1199px, 1200px and 1727px.

**Transfer:**

- On narrower layouts, preserve the sky-to-product hierarchy and the illustrated bottom edge. Reduce the art stage to available width and stack object scenes with their explanations; keep the reading measure capped at 600px. These are adaptation rules, not alternate measured type recipes.

**Unknown:**

- Mobile font sizes, navigation behavior and exact stacking arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
