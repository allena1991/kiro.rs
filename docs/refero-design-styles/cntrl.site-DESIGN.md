# cntrl — freehand meets terminal

## Overview

An experimental creative-tool aesthetic pairs stark white space with giant, tightly packed grotesk lettering and small terminal-like controls. Cool gray demonstration stages keep vivid editorial imagery contained, while an oversized serif text field adds an unexpected literary texture. The long, airy presentation finishes in black with luminous scan-lined symbols and monumental type; it suits visually expressive products whose work can speak louder than their explanations.

### Essentials

- The opening behaves like a typographic exhibition: a small corner mark, a centered 12px/16px uppercase manifesto and 24px-high controls sit above a solitary oversized black word sculpture on white. Keep this word-art device even when the product has no visual interface.
- Headlines feel compressed rather than heavy: Melange at 71px/76px, weight 500 and -3.6px tracking pairs black promise text with #a9a9a9 continuation text; the closing line grows to 146px/150px with -8.1px tracking.
- Actions look like tiny equipment labels, not app-store pills: square corners, 24px height, 20px horizontal padding and 12px/16px uppercase Favorit Mono. Electric #00eb40 marks conversion; cream and yellow distinguish learning actions.
- Most of the journey is white or cool #d2dcdd, with black reserved for the ending. Saturation is concentrated in small green controls, yellow symbols and the media itself rather than spread across every section.
- Demonstrations are objects inside generous flat stages: 1070×468px wide panels or paired 530×468px panels, 8px corners, centered colorful media and captions above rather than text buried inside cards.
- A giant text field and a glowing symbol field are signature graphic counterpoints: use 90px/85px Goudy Bookletter 1911 with -1.8px tracking behind a black-framed demonstration, and oversized white scan-lined pictograms behind the black closing scene. Use simplified original SVG symbols and a composed product example when custom footage is unavailable.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric green | `#00eb40` | `--color-conversion` | action | Compact conversion-button fills. |
| Tutorial yellow | `#ffdc4d` | `--color-learning` | action | Highlighted learning or exploration buttons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Default marketing background and brightest technical text on black. |
| Warm cream | `#f4f3ed` | `--color-cream` | surface, action | Learning-action fill and the editorial half of the showcase split. |
| Pale green | `#deeade` | `--color-login` | action | Subordinate account-action fill. |
| Dark-section white | `#e4e4e4` | `--color-dark-heading` | text | Readable headings and questions in the dark information section. |
| Cool gray stage | `#d2dcdd` | `--color-stage` | surface, background | Recurring demonstration panels and the full-width serif text field. |
| Closing silver | `#d2d2d2` | `--color-closing-text` | text | Monumental closing headline over black. |
| Terminal gray | `#c6c6c0` | `--color-terminal-text` | text, link | Small footer columns and utility links over black. |
| Text-field gray | `#bababa` | `--color-serif-text` | text | Low-contrast oversized serif lettering on the cool gray field. |
| Headline gray | `#a9a9a9` | `--color-headline-secondary` | text | The quieter continuation of a centered promise. |
| Fine-print gray | `#717171` | `--color-muted` | text | Tiny reassurance beneath the light-section conversion button. |
| Dark divider | `#4d4d4d` | `--color-divider` | border | One-pixel horizontal rules in the technical footer band. |
| Black ink | `#000000` | `--color-ink` | text, background, border | Primary lettering, thick media frames and the concluding dark canvas. |

## Typography

- **Melange** — Headlines, short explanatory paragraphs and the header manifesto. A compact contemporary grotesk whose tight spacing makes large lines feel drawn as a single shape. If unavailable, use **Inter**. Use 400 and 500; preserve the unusually tight large-type tracking. Font stack: "Melange", "Inter", Arial, sans-serif.
- **Favorit Mono** — Buttons, footer prose, utility links and fine-print reassurance. Small, matter-of-fact monospaced capitals, contrasting sharply with the large grotesk. If unavailable, use **IBM Plex Mono**. Use regular weight; keep labels compact. Font stack: "Favorit Mono", "IBM Plex Mono", ui-monospace, monospace.
- **Goudy Bookletter 1911** — The oversized background text field. Old-style book serif with expressive curves and a visibly literary tone. Font stack: "Goudy Bookletter 1911", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | Melange | 500 | 146px | 150px | -0.0555em | Two centered lines occupying most of the closing scene's width. |
| marquee | Melange | 400 | 102.2px | 0.7 | -0.0147em | Oversized, clipped horizontal statement introducing the capability chapter. |
| text-field | Goudy Bookletter 1911 | 400 | 90px | 85px | -0.02em | Edge-to-edge text texture behind the framed product demonstration. |
| heading | Melange | 500 | 71px | 76px | -0.0507em | Centered promise beneath the opening artwork; black lead and gray continuation share one recipe. |
| editorial-heading | Melange | 500 | 71px | 70px | -0.0507em | Narrow, left-aligned headline in the cream showcase split. |
| information-heading | Melange | 500 | 36px | 38px | -0.0167em | Two-line heading beside the dark question list. |
| body | Melange | 400 | 16px | 21px | -0.0375em | Short capability captions, usually two lines above the media. |
| editorial-body | Melange | 400 | 14px | 20px | 0.014em | Compact supporting paragraph in the cream showcase split. |
| action | Favorit Mono | 400 | 12px | 16px | normal, uppercase | All small rectangular action labels. |
| manifesto | Melange | 400 | 12px | 16px | normal | Centered uppercase prose in the top strip; capitalization is written into the copy. |
| terminal | Favorit Mono | 400 | 10px | 12px | 0.02em, uppercase | Footer support columns, technical-strip prose and utility links. |
| reassurance | Favorit Mono | 400 | 9px | 12px | 0.022em, uppercase | Small muted note directly beneath a conversion action. |

**Notes:**

- Large grotesk type uses negative tracking aggressively; the headline is medium, not bold. Keep its black and gray spans at identical size and weight.
- The serif field is a graphic surface, not a replacement body font. It can wrap densely and run beyond the edges while the foreground demonstration stays legible.
- Small uppercase mono labels carry utility rather than becoming conventional eyebrows above every heading. The scale jumps deliberately from tiny controls to very large display type.

## Layout

**Density:** Airy at section scale, compact at control scale: demonstrations have generous surrounds while labels and short paragraphs remain unusually small.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 20px | Action side padding and recurring layout gaps. | fixed |
| 28.8px | Gap and end padding between repeated marquee statements. | fixed |
| 62px | Separation between the centered promise and its conversion action. | fixed |
| 130px | Top offset of the dark question list. | 9.02778vw |
| 172.8px | Top and bottom breathing room around the large marquee. | fixed |

### Containers and grids

- **feature-stage**: max width 1070px · side padding 0px. Centered desktop demonstration lane, leaving 185px on each side at a 1440px viewport. This is a transferable width cap rather than a universal site container.
- **paired-demonstrations**: 2 columns · gap 10px. Two 530px-wide stages fit the same 1070px lane; captions sit directly above their respective stages.
- **showcase-split**: 2 columns · gap 0px. Full-bleed 900px-tall editorial split: a 665px cream copy field on the left and an overflowing gallery on the right.
- **dark-utility-lane**: max width 1248px · side padding 0px. Inset technical band bounded by horizontal rules; desktop side insets are 96px.

## Corner radius

| Element | Radius |
| --- | --- |
| action | 0px |
| demonstration-stage | 8px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Opening and main capability narrative.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** A flat background without decorative gradients or raised containers.

**Transfer:** Let white space and oversized text establish hierarchy.

#### Cool demonstration stage · level 1

**Use:** Repeated large media panels.

**CSS:** `background: #d2dcdd; border-radius: 8px; box-shadow: none`

**Observed:** Wide or paired panels hold a smaller, centered visual, with generous backing visible on all sides.

**Transfer:** Keep the backing consistent while the embedded media supplies visual variety.

#### Serif field · level 0

**Use:** Full-width typographic demonstration backdrop.

**CSS:** `background: #d2dcdd; color: #bababa; overflow: hidden`

**Observed:** Dense giant serif phrases and small yellow symbols extend behind an independently framed demonstration.

**Transfer:** Use a field of concrete capabilities or expressive product vocabulary.

#### Cream editorial field · level 0

**Use:** Copy half of a full-bleed showcase.

**CSS:** `background: #f4f3ed; color: #000000`

**Observed:** A warm flat panel makes a clean edge against the busy gallery beside it.

**Transfer:** Give one section an editorial, poster-like contrast without introducing another brand color.

#### Black closing canvas · level 0

**Use:** Questions, technical information and final conversion scene.

**CSS:** `background: #000000; color: #c6c6c0`

**Observed:** The information section leads into a monochrome luminous-symbol scene; controls remain green.

**Transfer:** Keep a substantial dark ending, not merely a thin copyright strip.

## Components

### Primary button

**Use:** Trial, start and main conversion actions.

**CSS:** `background: #00eb40; color: #000000; height: 24px; padding: 0px 20px; border-radius: 0px; display: inline-flex; justify-content: center; align-items: center; overflow: hidden; box-shadow: none`

**Text style:** `action` — Favorit Mono 400 · 12px/16px · uppercase

**Observed:** Text-only rectangular control sized to its label. It appears in the top-right corner and repeats within centered conversion scenes.

**States:** Declared: hover and focus-visible retain token-driven background, text and border colors, with no visible shadow; focus-visible outline is none. Active uses the same token-driven colors. Label transform, opacity and top transitions are 250ms.

**Transfer:** Keep one unmistakable green action rather than multiple equally bright options.

### Learning button

**Use:** Subordinate viewing and learning actions next to a demonstration caption.

**CSS:** `background: #f4f3ed; color: #000000; height: 24px; padding: 0px 20px; border-radius: 0px; display: inline-flex; justify-content: center; align-items: center; overflow: hidden`

**Text style:** `action` — Favorit Mono 400 · 12px/16px · uppercase

**Observed:** A cream control aligns to the right of the caption row rather than sitting in the media panel.

**Transfer:** Use for secondary supporting content.

### Highlighted learning button

**Use:** Emphasized exploration actions.

**CSS:** `background: #ffdc4d; color: #000000; height: 24px; padding: 0px 20px; border-radius: 0px; display: inline-flex; justify-content: center; align-items: center`

**Text style:** `action` — Favorit Mono 400 · 12px/16px · uppercase

**Observed:** Yellow distinguishes this action from both the green conversion and the cream viewing action; the two learning treatments can sit side by side.

**Transfer:** Reserve for an active next step associated with a particular capability.

### Account button

**Use:** Subordinate account access in the opening strip.

**CSS:** `background: #deeade; color: #000000; height: 24px; padding: 0px 20px; border-radius: 0px; display: inline-flex; justify-content: center; align-items: center`

**Text style:** `action` — Favorit Mono 400 · 12px/16px · uppercase

**Observed:** A pale green action sits immediately before the brighter trial action. It recedes later while the trial action remains visible.

### Demonstration panel

**Use:** Main capability-proof container.

**CSS:** `background: #d2dcdd; border-radius: 8px; height: 468px; overflow: hidden; box-shadow: none`

**Observed:** The default wide panel holds roughly 640px-wide media inside a 1070px backing. Paired variants use 530px backings and smaller visuals. Captions and actions live outside, above.

**Transfer:** Show a real output, workflow or visual transformation; do not fill the entire panel with explanatory text.

### Framed foreground demo

**Use:** Foreground product proof over the serif field.

**CSS:** `border: 5px solid #000000; border-radius: 8px; object-fit: cover; overflow: hidden`

**Observed:** A roughly half-page-width screen floats over background type. The settled view is horizontal even though the moving presentation can rotate.

**Transfer:** Compose one rich example of the product at work; preserve the thick black frame.

### Terminal utility link

**Use:** Footer contact, community and legal navigation.

**CSS:** `color: #c6c6c0; text-transform: uppercase`

**Text style:** `terminal` — Favorit Mono 400 · 10px/12px · tracking 0.02em · uppercase

**Observed:** Links are arranged as tiny stacks over the closing art, without enclosing buttons. Inline outreach links in the upper support columns turn vivid green.

**Transfer:** Group legal links to one side and community/contact links farther across the composition.

### Header manifesto

**Use:** Central identity statement in the sparse opening strip.

**CSS:** `width: 352px; color: #000000; text-align: center`

**Text style:** `manifesto` — Melange 400 · 12px/16px

**Observed:** Three small lines of uppercase prose sit between a tiny left mark and right-aligned actions; the wording is a playful philosophy rather than a navigation menu.

**Transfer:** Write a compact product-specific credo with human verbs and a slightly eccentric turn.

## Imagery and graphics

### Opening word sculpture

**Use:** Dominant first-screen identity artwork.

**Observed:** A single black grotesk word is isolated in an enormous white field. Its visible letterform silhouette spans roughly 530×135px, about a third of the viewport width, and sits above the large demonstration area.

**Transfer:** Use the new product's short name or a defining verb as original live lettering or SVG. For a long name, compose a compact two-word lockup with the same visual mass instead of shrinking it to navigation scale.

**Build:** Set a regular grotesk word in a responsive SVG viewBox; tighten letter spacing and fit its visible contours into a roughly 530×135px art area at 1440px width. Center horizontally, with substantial white space before and after. Keep it black and untextured.

### Editorial product demonstrations

**Use:** Main visual proof throughout the capability narrative.

**Observed:** Embedded interface demonstrations combine expressive portfolio-like layouts, cropped photography, strong typography and small editing toolbars. Bright yellow, lavender, blue, red and green belong inside these self-contained examples, centered on cool gray backing. Wide media is often about 640px across; paired media is around 400px across.

**Transfer:** Show the new product producing something visually specific. If no interface exists, use a carefully typeset output board, document or before-and-after composition. Keep interface internals subordinate to the overall image.

### Serif text and symbol field

**Use:** Immersive backdrop to the black-framed product demonstration.

**Observed:** Large low-contrast book-serif phrases form a continuous, nearly edge-to-edge paragraph. Small golden symbols such as a lightning bolt, hash, letter pair and sparkle interrupt the text. The framed screen sits visibly in front.

**Transfer:** Use concrete actions relevant to the new product and original simple symbols rather than a conventional feature grid.

**Build:** Lay out centered inline phrases in the text-field recipe over the cool gray stage. Insert approximately 61px SVG symbols between phrases, using a warm yellow fill. Allow the text to overflow the viewport edges; place the framed foreground demo on a separate centered layer.

### Showcase collage

**Use:** Visual half of the cream editorial split.

**Observed:** An oversized moving gallery of desktop website compositions and narrow phone views is clipped by the section edges. Black device outlines, white and pale editorial layouts, occasional photographs and refined type make it feel like a wall of finished work.

**Transfer:** Create a grid of original product outputs at different scales, with a few narrow-format versions overlapping larger ones. The minimum version is three convincing finished examples, not repeated empty device shells.

### Scan-lined symbol field

**Use:** Signature background of the final dark conversion scene.

**Observed:** Large white-gray pictograms—type mark, brackets, sun, hash, eye, bolt, sparkle, cursor and phone—form two loose horizontal rows on black. Their horizontal scan lines and soft luminous edges sit behind crisp silver display lettering and a sharp green action.

**Transfer:** Replace the subjects with a small original symbol vocabulary relevant to the product, while retaining monochrome light, exaggerated scale and scan-line treatment.

**Build:** Draw 8–10 simple white SVG silhouettes across two irregular rows, each roughly 120–220px in visual size. Apply a mask of repeating horizontal opaque and transparent bands about 2–4px tall. Duplicate behind with 4–10px blur and low-opacity white to form a halo. Clip the field at section edges; keep foreground text unblurred. Match the soft glow; exact stops are not essential.

### Icons

**Observed:** The most prominent small icons are 61×61px symbolic glyphs inserted in the serif text field, not conventional feature-card badges. The dark question list uses small plus signs at the far right.

**Transfer:** Choose simple, recognizable silhouettes that can work both as small yellow punctuation and oversized monochrome glowing art. Avoid adding an icon to every caption.

## Section recipes

How recurring sections are built.

### First screen: Word sculpture opening

**Observed:** The first 900px is a white exhibition-like stage. A small abstract mark occupies the upper left, the Header manifesto is centered at the top, and Account button plus Primary button sit at upper right with a 24px top inset. The large black Opening word sculpture is centered in the upper-middle white field and occupies roughly a third of the width. A substantial media area begins lower in the first screen. Layers are white canvas, identity lettering and demonstration media, then the sparse header controls. The explanatory heading uses the heading recipe, but sits below the first screen in a centered 710px-wide block; its black lead turns gray mid-thought, followed by a green action and tiny reassurance. The first-screen action is the header conversion, not a conventional row under a hero paragraph.

**Transfer:** Keep the monumental word-art opening and replace its subject with an original product name or decisive verb. Put a real product demonstration in the lower media area; when footage is unavailable, compose a polished output board using the same editorial media treatment. Secondary marketing pages can shorten this stage and bring their 71px heading forward while retaining the sparse corner controls and oversized identity artwork.

**Avoid:** Do not replace the opening with a standard left-copy/right-dashboard layout, a row of navigation links, or a centered paragraph-and-pill hero.

**Text style:** `heading` — Melange 500 · 71px/76px · tracking -0.0507em

### Centered promise

**Observed:** A centered heading mixes black and gray spans at 71px/76px. Its narrow measure creates a compact multi-line shape; the Primary button follows after 62px, with 9px uppercase reassurance directly beneath.

**Transfer:** State the product category first and the human benefit second, letting color rather than font size distinguish the clauses.

**Text style:** `heading` — Melange 500 · 71px/76px · tracking -0.0507em

### Immersive capability field

**Observed:** The Serif field fills the width with 90px book-serif phrases and yellow pictographic punctuation. Framed foreground demo floats over the middle, leaving text visible around its edges.

**Transfer:** Turn a dense capability inventory into a visual environment, with one tangible example in front.

**Text style:** `text-field` — Goudy Bookletter 1911 400 · 90px/85px · tracking -0.02em

### Marquee chapter introduction

**Observed:** A clipped horizontal statement uses the marquee recipe, repeating across the width with 28.8px gaps. Its wrapper gives 172.8px breathing room above and below.

**Transfer:** Use a concise chapter-level claim with repetition as a graphic device rather than a normal paragraph.

**Text style:** `marquee` — Melange 400 · 102.2px/0.7 · tracking -0.0147em

### Caption over demonstration

**Observed:** Within the 1070px feature-stage lane, a short 16px caption sits above the Demonstration panel; Learning button and Highlighted learning button align on the right. Alternate full-width stages with paired stages, leaving large white intervals between groups.

**Transfer:** Use each caption to name a visible outcome, and let the media prove it. Vary one wide proof with two related smaller proofs rather than making every capability identical.

**Text style:** `body` — Melange 400 · 16px/21px · tracking -0.0375em

### Cream editorial split

**Observed:** A full-width 900px section combines Cream editorial field on the left with Showcase collage on the right. A narrow left-aligned 71px/70px headline stacks into several lines; a 14px paragraph and green action sit well below it.

**Transfer:** Use for a library, examples, outcomes or ready-to-use resources. The collage supplies density while the copy panel stays sparse.

**Text style:** `editorial-heading` — Melange 500 · 71px/70px · tracking -0.0507em

### Dark question index

**Observed:** The Black closing canvas begins with a two-column information layout: a 36px two-line heading to the left, and a 590px-wide question list on the right, offset 130px from the top. Nine compact rows are about 55px high, separated by faint rules, with a small plus at the far right. Questions are small light grotesk text rather than large editorial headlines.

**Transfer:** Address purchase or adoption objections in a restrained accordion. Preserve the contrast between a generous empty left field and a compact right index.

**Text style:** `information-heading` — Melange 500 · 36px/38px · tracking -0.0167em

### Technical band and monumental ending

**Observed:** A 1248px-wide technical band is bounded by 1px dark-gray rules. Beneath it, four small terminal-style support columns lead into the Scan-lined symbol field. A two-line 146px silver headline dominates the center, with Primary button placed between the two lines. Tiny legal and community links are distributed along the bottom over the art rather than enclosed in a conventional footer card.

**Transfer:** Make the ending a strong visual payoff: practical assistance in small mono type, then a short outcome-led line over glowing original symbols. Keep utility links legible but secondary to the final action.

**Text style:** `closing-display` — Melange 500 · 146px/150px · tracking -0.0555em

## Page flow

**Storyline:** identity spectacle → clear promise → immersive demonstration → capability proofs → finished-output showcase → objections and assistance → monumental final action

### A long-form marketing landing page for a creative product

1. **Identity hook** — Sparse top strip and oversized black word artwork on white.
2. **Promise** — Centered black-and-gray category statement with a tiny green conversion action.
3. **Product demonstration** — Framed working example floats over a dense serif capability field.
4. **Capability chapters** — A large repeating statement introduces alternating wide and paired media stages with compact captions.
5. **Outcome proof** — Cream editorial copy faces a full-bleed collage of finished examples.
6. **Objection handling** — Black question index and compact technical-assistance strip.
7. **Closing call** — Mono support columns give way to giant silver type over glowing symbols, with legal and community links along the bottom.

**Transfer:** Borrow the alternation of spectacle, plain explanation and tangible proof. Adapt the number and order of demonstrations to the product while retaining the word-art hook, immersive typographic field and luminous dark payoff.

## Writing

Confident, hands-on and slightly irreverent, like creatives talking directly to other creatives. Short practical benefits are mixed with playful asides, occasional fragments and a human rather than corporate assurance.

**Do not copy:** Do not reuse the Control or cntrl names, logos, proprietary artwork, customer identities, contact details, product claims, availability promises or source-specific examples as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we conversationally when offering help. Product descriptions use concrete active verbs rather than abstract mission language.
- **Rhythm:** Headlines are compact spoken statements; support copy is usually one or two short sentences. Fragments such as three clipped clauses can precede a fuller explanation. Uppercase is reserved for the top manifesto, controls and terminal-like footer text.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Category promise | Name the product category, then add a human audience or point of view. | About 8–12 words | “Freehand website builder for creatives by creatives.” |
| Capability caption | Start with an action or outcome, then explain the mechanism in everyday language. | About 10–20 words | “Animate. Intuitively. With Ease. Use keyframes or timed animations for kick and precision.”<br>“No more boring sliders. Organize your photos into interactive galleries that work.” |
| Editorial headline | A conversational admission followed by an enthusiastic qualification. | About 7–12 words | “Oh yes, we've got templates. A beautiful ones.” |
| Primary action | Direct verb plus immediate next step; very little qualification. | 2–3 words | “TRY FREE”<br>“GET STARTED”<br>“START NOW” |
| Closing line | A short imperative about making the desired outcome real. | 4–6 words | “Make Your Website Happen” |

**Words and phrasing to use:** make; create; experiment; intuitively; your; with ease; stand out; real people

**Avoid:** enterprise-grade synergy; revolutionary ecosystem; seamless end-to-end transformation; unlock limitless potential

**Rules:**

- Tie each short benefit to what is visibly demonstrated nearby.
- Let occasional playful punctuation and parenthetical asides create warmth, but keep most captions plain.
- Use natural conversational confidence without repeating grammatical slips as a brand device.
- Keep footer prose direct and human even when it is set like technical documentation.

## Do's and Don'ts

### Do

- Keep the default headline at weight 500 with -3.6px tracking rather than compensating with bold weight.
- Make the main demonstration lane 1070px wide at the desktop reference size.
- Use 8px corners on media stages and square corners on all 24px action chips.
- Keep caption copy at 16px/21px and outside the demonstration backing.
- Use electric green for compact conversion controls, with cream and yellow for supporting actions.
- Give the dark ending enough room for the 146px two-line call and luminous background symbols.
- Retain the 90px serif field as an intentional graphic contrast to the grotesk headings.
- Use tiny 10px/12px mono utility text to counterbalance monumental display lettering.

### Don't

- Do not turn the neon green into a full-page brand wash; its impact comes from small action rectangles.
- Do not add soft elevation shadows to the flat cool-gray demonstration stages.
- Do not round controls into pills or enlarge their visible face into conventional 48px marketing buttons.
- Do not use the book serif for ordinary paragraphs or every section headline.
- Do not move all learning actions into the lower corners of media cards; their role belongs in the caption row.
- Do not apply glow or scan lines to the foreground closing headline; it remains crisp over the softened art.
- Do not replace the final composition with a dense multi-column sitemap occupying the entire dark ending.
- Do not make every supporting sentence larger than 16px; the deliberate tiny-text/giant-type contrast is essential.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 250ms transitions for color, background-color, border-color, transform, box-shadow and backdrop-filter.
- Rolling button labels declare 250ms transform, opacity and top transitions.
- Two horizontally repeating statement animations are declared with linear timing.
- The framed foreground demonstration uses sticky positioning and a rotation transform; its settled visual is horizontal.

**Transfer:**

- Use a clipped rolling-label construction on the compact buttons rather than making them inflate on hover.
- Keep the large repeating statement moving as a continuous typographic band, and keep the foreground demonstration independent of its text backdrop.

**Unknown:**

- Marquee duration, full scroll choreography and exact glow animation timing are unknown.

### Responsive

**Observed:**

- Declared width breakpoints divide 0–1023px and 1024px upward; only the desktop arrangement is established.
- The framed demonstration declares a 0.555556vw corner radius, corresponding to 8px at desktop width.

**Transfer:**

- On narrow screens, retain the word sculpture and sparse conversion control, reduce the media width to the available space and stack paired demonstrations.
- Stack the cream copy field before its collage and the dark question heading before its list. Keep the scan-lined ending but reduce symbol count before sacrificing headline legibility.
- Treat these narrow-screen arrangements as adaptation guidance rather than a fixed additional template.

**Unknown:**

- Exact mobile type sizes, header behavior, section heights and art choreography are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
