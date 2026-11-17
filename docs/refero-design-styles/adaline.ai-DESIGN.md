# Adaline — pastoral machines

## Overview

A technical marketing style with the feeling of an optimistic landscape painting. Pale green paper, forest-colored text and small monospaced controls frame expansive, softly lit imaginary worlds and intricate software views. Regular grotesk typography gives way to delicate editorial serifs at emphatic moments, while the ending descends into a nocturnal forest. It suits complex tools that want to feel thoughtful and humane rather than aggressively futuristic.

### Essentials

- A restrained promise beside a field of machine marks: a 53px regular grotesk headline with -0.04em tracking sits in a 640px text column opposite a roughly 400px-wide pale ASCII graphic; customer marks sit along the opening's lower edge.
- Controls feel like tiny instrument labels: 14px monospace with 0.02em tracking, 40px-high paired actions, 20px corners and a forest-green primary fill; navigation uses a compact 32px-high variant.
- Color belongs mainly to worlds, not widgets: pale #fbfdf6 covers the main canvas, muted green text carries hierarchy, and broad pastel lavender-and-gold landscapes occupy 1280px-wide media stages. Keep saturated interface colors confined to product demonstrations.
- Technical chapters have painterly scale: 30px regular headings and 18px support copy introduce 7:5 landscape stages with 8px corners, separated from their introductions by 40px. Include atmospheric landscape art even when no product footage exists.
- A manifesto changes the register: a full-width #2a332a band pairs stacked 108px Newsreader at weight 300 with a thin outlined pill diagram. Recreate this large serif statement and connected process graphic with new language.
- The ending becomes a place rather than a strip: an expansive dark teal atmosphere, 104px Instrument Serif closing invitation and a large dark software panel lead into wooded hills and water that overlap the footer; use a layered landscape silhouette when detailed art is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep meadow | `#203b14` | `--color-action` | action, text | Primary action fills and announcement text. |
| Deep teal haze | `#193238` | `--color-cloud-bottom` | background | Lower atmospheric closing gradient. |
| Night water | `#050e11` | `--color-night` | background | Closing atmosphere base and footer. |
| Dark teal sky | `#0f2024` | `--color-cloud-top` | background | Upper atmospheric closing gradient. |
| Woodland | `#2a332a` | `--color-manifesto` | background | Full-width serif manifesto band. |
| Pale meadow | `#ecf2df` | `--color-announcement` | surface | Small announcement capsule. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive text | `#2b390a` | `--color-quote-ink` | text | Testimonial copy, names and monochrome customer marks. |
| Forest ink | `#0a1d08` | `--color-ink` | text | Primary headings and strong text. |
| Secondary forest | `#2e3b28` | `--color-secondary-ink` | text | Outlined action text. |
| Pebble text | `#6b7860` | `--color-body-muted` | text | Supporting paragraphs and restrained labels. |
| Meadow outline | `#c5ccb6` | `--color-outline` | border | Secondary action edges and subtle navigation rule. |
| Sage stone | `#e1e6df` | `--color-proof` | surface, border | Testimonial cards and certification medallion edges. |
| Landscape ground | `#eff2e8` | `--color-stage` | surface | Backing beneath landscape media. |
| Green paper | `#fbfdf6` | `--color-canvas` | background, text | Main page canvas and inverse action text. |
| Porcelain | `#fdfefb` | `--color-inverse` | text, border | Manifesto text, dots and outlined process pills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Interface charcoal | `#1d2226` | `--color-ui-dark` | surface | Dark software window at the closing stage. |
| product demonstrations | Interface paper | `#f8f9f5` | `--color-ui-paper` | surface | Light product windows. |

## Typography

- **akkurat** — Marketing headings, paragraphs, proof cards and footer links. Plainspoken grotesk with open counters; regular weight rather than heavy display cuts. OpenType features: "calt", "kern". If unavailable, use **Inter**. Use weight 400 and preserve tight heading tracking. Font stack: "akkurat", Inter, system-ui, sans-serif.
- **fragmentMono** — Actions, navigation, announcement labels and process diagram. Light mechanical monospace that reads as small technical markings. OpenType features: "calt", "kern". If unavailable, use **Fragment Mono**. Font stack: "fragmentMono", "Fragment Mono", ui-monospace, monospace.
- **Newsreader** — Monumental stacked manifesto. Fine, lightly weighted editorial serif with soft modulation. OpenType features: "calt", "kern". Font stack: "Newsreader", Georgia, serif.
- **Instrument Serif** — Closing invitation. Tall, expressive contrasting serif that makes a single sentence feel ceremonial. OpenType features: "calt", "kern". Font stack: "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| manifesto | Newsreader | 300 | 108px | 0.98 | -0.032em | Short stacked lines in a dark thesis band. |
| closing | Instrument Serif | 400 | 104px | 0.95 | -0.02em | Centered closing invitation. |
| headline | akkurat | 400 | 53px | 64px | -0.04em | Opening promise and major reassurance heading. |
| heading | akkurat | 400 | 30px | 1.157 | -0.02em | Capability chapter introductions. |
| diagram-label | fragmentMono | 400 | 28px | 0.5 | 0.04em | Process pill text; center within the pill rather than using line height for its height. |
| body | akkurat | 400 | 18px | 1.444 | normal | Supporting marketing paragraphs. |
| quote | akkurat | 400 | 16px | 1.5 | -0.015em | Default testimonial text. |
| action | fragmentMono | 400 | 14px | 1 | 0.02em | Navigation and action labels; present as small capitals visually. |
| label | fragmentMono | 400 | 14px | 1 | 0.05em | Announcement and trust labels. |
| footer-link | akkurat | 400 | 14px | 1.286 | normal | Footer navigation. |
| attribution | akkurat | 400 | 12px | 1.333 | normal | Testimonial role and organization. |
| footer-label | fragmentMono | 400 | 11px | 1.273 | 0.1em, uppercase | Footer column labels. |

**Notes:**

- Keep the main grotesk regular: hierarchy comes from scale, spacing and ink density, not boldness.
- Headings tighten from -0.02em at 30px to -0.04em at 53px; body paragraphs remain normally tracked.
- The two serif families have different jobs: light Newsreader for stacked statements, Instrument Serif for a centered closing sentence.
- Small monospaced controls read as capitals while normal prose remains sentence case.

## Layout

**Density:** Airy marketing composition around unusually dense technical imagery; compact proof cards provide a deliberate contrast.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Proof grid gutters. |
| 12px | Action pair gaps and inline diagram dot gaps. |
| 16px | Chapter heading to supporting paragraph; certification badge gaps. |
| 20px | Proof card padding and announcement-to-headline gap. |
| 24px | Headline-to-body gap and horizontal action padding. |
| 40px | Introduction-to-media and body-to-actions gaps. |
| 48px | Outer container side padding. |
| 64px | Footer column separation. |
| 96px | Standard chapter vertical padding and manifesto column separation. |

### Containers and grids

- **marketing container**: max width 1280px · side padding 48px. Centered wrapper; at 1440px the content edges land 80px from the viewport sides.
- **opening text**: max width 640px. Left-aligned promise, body and actions; the right side is reserved for generative marks.
- **chapter introduction**: max width 747px. Keep chapter text much narrower than its full-width media stage.
- **proof grid**: 3 columns · gap 8px. Equal-height quote cards; a preceding expandable logo row mixes narrow logo tiles with one wide open quote.
- **manifesto split**: 2 columns · gap 96px. A 1.4fr statement column opposite a 1fr diagram column; diagram width 400px.
- **closing media grid**: max width 2048px · 12 columns · gap 24px · side padding 48px. Dark product window spans the inner ten columns, 1116px wide at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 20px |
|  | announcement and diagram | 9999px (pill) |
|  | landscape stages | 8px |
|  | proof cards | 10px |
|  | medallions | 50% |
| product demonstrations | product windows | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| product demonstrations | light window edge | `0px 0px 0px 1px rgba(52,79,49,0.07), 0px 1px 0px 0px rgba(255,255,255,0.9) inset, 0px 12px 32px -16px rgba(0,0,0,0.2)` | A restrained edge and soft depth treatment for light software windows. |

### Surfaces

#### Paper canvas · level 0

**Use:** Main marketing background.

**CSS:** `background: #fbfdf6; color: #0a1d08`

#### Landscape stage · level 1

**Use:** Large painterly capability media.

**CSS:** `background: #eff2e8; border-radius: 8px; overflow: hidden; aspect-ratio: 7 / 5`

**Observed:** The art fills the frame without a visible outline; image edges extend slightly past the clipped stage.

**Transfer:** Use a panoramic landscape with a strong horizon and soft atmospheric depth.

#### Sage proof card · level 1

**Use:** Quotes and expandable logo tiles.

**CSS:** `background: #e1e6df; border-radius: 10px; box-shadow: none`

#### Woodland band · level 0

**Use:** Serif statement and explanatory diagram.

**CSS:** `background: #2a332a; color: #fdfefb; padding: 96px 0px`

#### Atmospheric ending · level 0

**Use:** Immersive transition into the closing call.

**CSS:** `background: linear-gradient(#0f2024, #193238)`

**Observed:** Cloud-like masking softens the transition; the lower scene resolves to night water.

**Transfer:** Blend cloud texture into a dark teal field instead of making a hard rectangular color switch.

#### Night footer · level 0

**Use:** Final navigation and brand signature.

**CSS:** `background: #050e11; color: #fbfdf6`

#### Glass navigation backing · level 2

**Use:** Sticky header backing over scrolling content.

**CSS:** `background: rgba(251,253,246,0.85); backdrop-filter: blur(12px)`

**Observed:** A faint bottom rule and translucent fill preserve continuity with the paper canvas.

#### Light software window · level 2

**Only for:** product demonstrations

**Use:** Technical detail layered within a landscape stage.

**CSS:** `background: #f8f9f5; border-radius: 12px; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(52,79,49,0.07), 0px 1px 0px 0px rgba(255,255,255,0.9) inset, 0px 12px 32px -16px rgba(0,0,0,0.2)`

**Observed:** A compact application chrome, left sidebar and dense data region sit within a 785px-wide window.

#### Dark software window · level 2

**Only for:** product demonstrations

**Use:** Closing product proof.

**CSS:** `background: #1d2226; border-radius: 12px; overflow: hidden`

**Observed:** Large dark application view fades downward into the night landscape rather than ending at a hard bottom edge.

## Components

### Sticky navigation

**Use:** Persistent lightweight site orientation.

**CSS:** `position: sticky; top: 0px; height: 64px; z-index: 50`

**Observed:** A small wordmark sits at the left of the marketing container; two plain mono links and a compact primary action align right. The header becomes translucent over imagery.

**Transfer:** Keep the navigation sparse and retain the compact action rather than adding a large menu bar.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0px 24px; border-radius: 20px; background: #203b14; color: #fbfdf6; gap: 12px`

**Text style:** `action` — fragmentMono 400 · 14px/1 · tracking 0.02em

**Observed:** Pairs with the outlined secondary button. The header variant is 32px high with 14px horizontal padding; the dark closing scene reverses the primary fill to paper and text to forest.

**States:** Declared: hover background-color color-mix(in oklab,rgb(32 59 20) 90%,transparent); focus-visible outline-offset 4px, outline-color rgb(10 29 8), outline-style none.

### Secondary button

**Use:** Documentation or lower-commitment action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0px 24px; border-radius: 20px; border: 1px solid #c5ccb6; background: transparent; color: #2e3b28`

**Text style:** `action` — fragmentMono 400 · 14px/1 · tracking 0.02em

**Observed:** Same height as the primary with no elevation. In the dark closing scene the label becomes paper-colored.

**States:** Declared: hover border-color rgb(224 229 213), color color-mix(in oklab,rgb(80 92 71) 80%,transparent); focus-visible outline-offset 4px, outline-color rgb(10 29 8), outline-style none.

### Announcement capsule

**Use:** One short editorial link above the opening promise.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; padding: 6px 12px; border-radius: 9999px; background: #ecf2df; color: #203b14`

**Text style:** `label` — fragmentMono 400 · 14px/1 · tracking 0.05em

**Observed:** Small text followed by a fine diagonal arrow; align to the left text edge, not centered over the hero.

**States:** Declared: hover background-color rgb(215 232 181), color rgb(10 29 8); focus-visible outline-offset 4px, outline-color rgb(10 29 8), outline-style none.

### Navigation link

**Use:** Sparse text navigation.

**CSS:** `display: inline-flex; align-items: center; padding: 8px 12px; color: rgba(10,29,8,0.85)`

**Text style:** `action` — fragmentMono 400 · 14px/1 · tracking 0.02em

**Observed:** No filled tab or decorative container; small uppercase-looking mono lettering.

**States:** Declared: hover color rgb(10 29 8); focus-visible outline-offset 4px, outline-color rgb(10 29 8).

### Testimonial card

**Use:** Compact customer evidence.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #e1e6df; border-radius: 10px; padding: 20px; min-height: 250px; color: #2b390a`

**Text style:** `quote` — akkurat 400 · 16px/1.5 · tracking -0.015em

**Observed:** Monochrome organization mark at the top, quote below, attribution anchored near the bottom; a small circular play control occupies the lower right. Expandable logo tiles use the same material.

**Transfer:** Use concise authentic quotes and allow the attribution to stay aligned across a row.

### Process pill

**Use:** Steps in the large connected loop illustration.

**CSS:** `display: flex; align-items: center; gap: 12px; width: 320px; height: 54px; padding: 12px 24px; border: 1px solid #fdfefb; border-radius: 9999px; color: #fdfefb; box-sizing: border-box`

**Text style:** `diagram-label` — fragmentMono 400 · 28px/0.5 · tracking 0.04em

**Observed:** Each outlined pill contains a small white dot before the label; the pills overlay a larger green return path.

**Transfer:** Use short process verbs or nouns rather than explanatory sentences.

### Footer link

**Use:** Resource, company and connection columns.

**CSS:** `display: inline-block; color: rgba(251,253,246,0.8); border-radius: 4px`

**Text style:** `footer-link` — akkurat 400 · 14px/1.286

**Observed:** Links are grouped below letterspaced mono headings, with 10px list gaps and 64px between columns.

**States:** Declared: hover color rgb(251 253 246); focus-visible color rgb(251 253 246), outline-offset 4px, outline-style none.

### Trust medallion

**Use:** Reassurance marks below the main promise or in the ending.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 52px; height: 52px; border: 1px solid rgba(251,253,246,0.2); background: rgba(251,253,246,0.03); border-radius: 50%`

**Observed:** The footer uses three muted circular seals. The light reassurance section enlarges them to 80px and uses sage outlines and muted green artwork.

**Transfer:** Use legitimate assurance marks or concise capability emblems; keep all marks monochrome.

## Imagery and graphics

### Machine-mark field

**Use:** Right-hand opening visual counterweight.

**Observed:** A tall, roughly 400px-wide rectangle of extremely faint monospaced symbols sits above and beside the promise. Dense rows of punctuation evoke a computational image without becoming a screenshot.

**Transfer:** Generate a subtle abstract symbol field related to the new product; its texture should balance the text without competing with it.

**Build:** Use about 30 rows of 10px monospace at 12px line height, colored with rgba(46,59,40,0.42). Clip the rows into a tall 400px-wide rectangle. Vary punctuation density using a simple noise or silhouette mask; keep the entire field pale against the paper.

### Pastoral future landscapes

**Use:** Signature large media stages throughout capability storytelling.

**Observed:** Painted panoramic worlds combine mountain valleys, snowy peaks, reflective water and distant slender architecture. Pale peach sunlight and lavender shadows create low-contrast, textured depth; trees and foreground terrain provide darker anchors. These images dominate their sections, not small thumbnail cards.

**Transfer:** Create new places that metaphorically express the product's value. Minimum acceptable treatment is an original landscape photograph or illustration with a lavender shadow wash, warm diffuse sky and subtle grain; retain the large stage rather than substituting generic interface tiles.

**Build:** Compose foreground silhouettes, a middle-distance water or valley plane and pale distant mountains. Add slender architectural accents sparingly. Overlay a warm peach light layer from the horizon and a translucent lavender wash in shadows, then fine noise at low opacity. Keep detail in the image, not as separate decorations around the frame.

### Nocturnal forest threshold

**Use:** Signature transition from final product panel to footer.

**Observed:** Dark wooded hills rise from both sides, leaving a low valley at center; still water reflects the foliage. The terrain overlaps and partially conceals the application panel, then dissolves into the near-black footer.

**Transfer:** Use a similarly immersive landscape appropriate to the new product. Minimum version is layered textured hill silhouettes, a central opening and a very dark reflected duplicate below.

**Build:** Place two wide irregular SVG hill silhouettes at opposing lower corners, with forest texture clipped inside. Use dark green shading over a night-water base. Mirror the hills vertically below a horizontal waterline with reduced opacity and a soft blur. Add a bottom gradient to the night base; overlap the panel above rather than enclosing the hills in a card.

### Software proof scenes

**Only for:** product demonstrations

**Use:** Dense technical evidence within landscape stages and the dark closing scene.

**Observed:** Light windows have compact chrome, multiple columns, tiny mono identifiers, tables, graphs and restrained colored status marks. The closing view is a wider charcoal application window with sidebar and side-by-side revision content. It fades into the scene below.

**Transfer:** Use the real product's workflows at believable density. Do not promote the tiny interface type into the marketing scale; let the surrounding prose explain the outcome.

### Icons

**Observed:** Tiny functional outline symbols generally use rounded caps and 1.7–1.8px strokes at 11–14px. Play buttons use small solid triangles; larger assurance seals remain monochrome and low contrast.

**Transfer:** Choose spare rounded outline icons for controls and keep them subordinate to labels. Preserve the contrast between tiny utility symbols and the large scenic artwork.

## Section recipes

How recurring sections are built.

### First screen: Split computational opening

**Observed:** The 64px sticky navigation tops a paper-colored first screen. A 1280px centered container carries a left 640px copy block and a tall pale symbol field on the right, roughly 400px wide and 582px high. The copy is vertically centered in the upper main region: Announcement capsule, a single-line 53px regular headline, a three-line 18px supporting paragraph, then Primary button and Secondary button with a 12px gap. Spacing is 20px from capsule to headline, 24px from headline to body and 40px from body to actions. Back-to-front layers are paper, faint symbol graphic, then copy and controls. A small centered trust label and monochrome customer row sit toward the bottom. Within the first 900px the headline, support, both actions, complete symbol field and trust row are visible; capability art begins below the fold.

**Transfer:** Keep the left promise compact and give the right half an original machine-mark silhouette or procedural field when no product media exists. For a focused product or editorial landing page retain this asymmetric opening and change the promise and symbol subject, rather than inflating the headline.

**Avoid:** Do not replace the faint right-hand texture with an enormous high-contrast dashboard, centered slogan or full-bleed hero photograph.

**Text style:** `headline` — akkurat 400 · 53px/64px · tracking -0.04em

### Scenic capability chapter

**Observed:** A 96px-padded chapter uses a narrow left-aligned heading and support pair with a 16px gap. After 40px, Landscape stage spans the full marketing container. The visible artwork is an expansive pastel world; technical proof belongs within the same framed media system.

**Transfer:** Use one outcome per chapter with an equally generous scenic image and concise mechanism explanation. Vary the landscape, not the framing or heading hierarchy.

**Text style:** `heading` — akkurat 400 · 30px/1.157 · tracking -0.02em

### Dense human proof wall

**Observed:** An expandable logo row precedes a three-column Testimonial card grid with 8px gutters. One expanded upper tile becomes a wide quote while neighboring tiles remain centered logos. Lower cards use uniform heights and bottom-aligned attribution.

**Transfer:** Use a compact evidence wall to interrupt the airy chapters; fewer strong quotes are preferable to stretching weak quotes into empty tall cards.

**Text style:** `quote` — akkurat 400 · 16px/1.5 · tracking -0.015em

### Serif thesis and loop

**Observed:** Woodland band uses a 1.4fr/1fr split with a 96px gap. Four very short Newsreader lines fill the left side; a 400px connected loop diagram occupies the right. Process pill rows are separated by 28px, with a thin green return arrow outside them.

**Transfer:** Turn the core product philosophy into a stacked statement and a connected process illustration. Preserve the editorial/technical contrast even if the process has a different number of steps.

**Text style:** `manifesto` — Newsreader 300 · 108px/0.98 · tracking -0.032em

### Open reassurance block

**Observed:** Paper canvas with 96px vertical padding, a 53px heading constrained to roughly half the container, three 80px Trust medallions with 16px gaps, and one subdued support paragraph. The right side remains open.

**Transfer:** Use concise, verifiable reassurance and monochrome seals rather than a large checklist.

**Text style:** `headline` — akkurat 400 · 53px/64px · tracking -0.04em

### Atmospheric closing invitation

**Observed:** Atmospheric ending creates a long scenic descent. A centered 104px serif invitation appears above paired inverse actions with a 40px gap. The invitation region has 320px upper and 288px lower padding. A large Dark software window occupies the inner ten columns of a twelve-column grid and fades toward the bottom.

**Transfer:** Give the final invitation the same ceremonial serif scale and environmental depth. Use a dark editorial proof panel if the new product has no application interface; keep the landscape threshold and paired actions.

**Text style:** `closing` — Instrument Serif 400 · 104px/0.95 · tracking -0.02em

### Landscape footer

**Observed:** Nocturnal forest threshold overlaps the panel and Night footer. Within the 1280px container the brand signature and short tagline sit left, three compact navigation columns sit right, and small seals and copyright sit below the brand. Column headings use 11px mono capitals; links use 14px sans. The dark ground continues to the page edge without a separate footer card.

**Transfer:** Keep the final navigation utilitarian beneath the cinematic transition, using the new product's own mark and a restrained short tagline.

**Text style:** `footer-link` — akkurat 400 · 14px/1.286

## Page flow

**Storyline:** promise → scenic capability explanation → human proof → product philosophy → reassurance → atmospheric invitation → navigational ending

### Marketing landing page for a complex technical product

1. **Promise** — Asymmetric paper opening with small announcement, regular sans promise, paired actions, pale computational art and customer row.
2. **Capability chapters** — Repeated narrow introductions above full-width painterly worlds and detailed software proof.
3. **Social proof** — Compact expandable logo tiles and a dense quote wall.
4. **Product philosophy** — Large light serif statement on woodland paired with an outlined process loop.
5. **Objection handling** — Open paper reassurance area with three monochrome seals.
6. **Closing call** — Long dark atmospheric transition, centered serif invitation and paired actions above a large dark proof panel.
7. **Navigational ending** — Forested hills and water overlap the panel and lead into brand signature, small seals and three resource columns.

**Transfer:** Adapt the number and order of capability and proof blocks to the new story while preserving the contrast between paper, expansive scenery, compact evidence and a cinematic night ending.

## Writing

Calm but ambitious technical confidence. Concrete mechanisms are connected to the relief and confidence a user gains, with occasional conversational phrasing rather than corporate abstraction.

**Do not copy:** Do not reuse Adaline's name, logos, distinctive slogans, customer marks, testimonials, certification claims, numerical results or product-specific assertions. Source examples illustrate cadence only.

- **Addressing the reader:** Speak directly to teams as you and your; use the product name to explain mechanisms and we sparingly for reassurance.
- **Rhythm:** Short three-to-seven-word outcome headlines followed by one or two medium-length explanatory sentences. Thesis statements use fragments and periods; actions stay terse.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact imperative expressing an enduring outcome. | 3–5 words | “Never stop learning” |
| Capability heading | An outcome or transformation, sometimes phrased conversationally. | 4–7 words | “Evals that write themselves”<br>“From edge cases to test data” |
| Supporting explanation | Product name plus concrete action and mechanism, ending in practical benefit. | 20–35 words | “[Brand] generates evals from detected behaviors and user feedback, so regressions are caught before agent changes ship.” |
| Manifesto | Two compact imperatives split into emphatic fragments. | 4–6 words | “Ship Once. Improve Forever.” |
| Action | Familiar verb-object utility labels. | 2 words | “Get Started”<br>“Read Docs” |

**Words and phrasing to use:** understand; improve; grounded; real signals; before; confidence; while you sleep

**Avoid:** revolutionary; unleash; game-changing; 10x everything; seamless magic

**Rules:**

- Lead with an outcome, then explain the actual mechanism.
- Use technical vocabulary where it conveys meaning, not as ornamental jargon.
- Make reassurance concrete and verifiable.
- Let a short emotional phrase punctuate otherwise practical prose.

## Do's and Don'ts

### Do

- Keep primary marketing headings at weight 400 and 53px/64px.
- Constrain opening copy to 640px while scenic stages stretch to 1280px.
- Use 40px-high action pairs with 12px gaps and 20px radii.
- Separate chapter introductions from their art by 40px.
- Keep proof cards close together with 8px gutters and 20px internal padding.
- Make the serif thesis substantially larger than the grotesk headings: 108px against 53px.
- Use tiny monochrome utility icons and let the landscape supply visual richness.
- Carry dark wooded imagery into the footer rather than stopping it above the navigation.

### Don't

- Do not turn the pale green canvas into pure white and black; preserve forest-tinted neutrals.
- Do not use bold geometric display typography in place of the regular grotesk promise.
- Do not make every section a rounded card; reserve 8px corners for media and 10px for compact proof.
- Do not color each testimonial tile differently; keep the sage material consistent.
- Do not enlarge the navigation action to the 40px hero height; its compact variant is 32px.
- Do not use bright purple or neon blue as general marketing accents; those would overpower the muted scenery.
- Do not turn the loop diagram into filled rectangular feature cards; it needs outlined 320px pills.
- Do not replace the final serif invitation with another ordinary 30px capability heading.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions are declared at 0.15s cubic-bezier(.4,0,.2,1).
- Footer links declare color and opacity transitions at 0.24s cubic-bezier(0.32,0.72,0,1).
- Process pills declare opacity and transform transitions at 0.35s cubic-bezier(0.32,0.72,0,1).
- Opening rise animation is declared at 0.68s cubic-bezier(0.22,1,0.36,1) with a 0.3s delay; navigation has its own 0.52s entrance with a 0.58s delay.

**Transfer:**

- Use the distinct slower diagram entrance and short control color changes rather than applying one spring effect to everything.
- Preserve the subdued visual weight of the opening symbol field while moving it.

**Unknown:**

- Exact scroll synchronization of the landscape and software layers, and the procedural canvas animation, are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px and 1024px.
- Landscape framing changes from a 3:4 aspect ratio to 7:5 at the medium layout.
- Proof grid declarations change from one column to three.
- Manifesto grid declarations change from one column to a 1.4fr/1fr split at the large layout.
- Closing serif declarations include 52px, 88px and 104px sizes.

**Transfer:**

- On narrow screens place the thesis above its diagram, retain the full scenic frame and stack proof cards.
- Reduce closing type using its declared smaller sizes rather than shrinking the entire atmospheric scene proportionally.
- Keep opening copy first and move the symbol field behind or below it without reducing text contrast.

**Unknown:**

- Exact small-screen navigation behavior, symbol-field positioning and footer overlap heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
