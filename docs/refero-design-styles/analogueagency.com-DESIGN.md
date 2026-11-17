# Analogue — emotional light, tangible worlds

## Overview

An image-led, cinematic style that pairs cool grey editorial space with a dark, luminous opening. Tightly set grotesk typography and dot-matrix navigation give it a contemporary studio character, while tactile product photography, sculptural renders and human portraits supply warmth. It suits design-led products and creative services with a strong visual story, balancing sparse text with expansive media and a concentrated electric-blue accent.

### Essentials

- A modest sentence sits inside an enormous optical event: the opening uses 40px/42px medium grotesk with -2px tracking, centered over a full 900px dark field of converging blue-white light. Include this atmospheric device even when no product render exists; an SVG light field is the fallback.
- Navigation is a floating instrument rather than a full-width masthead: a centered 470px × 53px frosted bar, 20px corners and 10px backdrop blur, with two 20px uppercase dot-matrix links flanking a compact identity.
- Big text behaves like a continuous thought, not a stack of slogans: primary statements use 60px/60px Graphik at weight 500 and -3px tracking; secondary statements use 40px/42px and -2px tracking.
- Color belongs to worlds, not to the whole interface: #ededed and #1c1c1c carry the default page; saturated color fills the large media panels, small badges and one concentrated blue conversion panel about 460px wide, not broad alternating accent bands.
- Actions are either words at headline scale or little capsules embedded in imagery: use a grey second line for the main text action, pill-shaped project labels, and a softly rounded rectangular form button rather than a repeated fleet of large CTA pills.
- Proof is staged as tangible, near-edge-to-edge imagery: 20px side gutters, roughly 10px between panels, 10px–15px corners and very little overlaid copy. A product without physical assets gets a clean device scene on a textured, directionally lit backing.
- The close has two different scales at once: a compact vivid signup object suspended in open grey space, then a 60px two-line invitation and action anchored low and left. Preserve both the bright object and the oversized text close on a new landing page.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0038ff` | `--color-blue` | accent, surface | Small informational badges; use this electric-blue family for the isolated signup object, keeping its exact hue subordinate to the vivid effect. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool grey canvas | `#ededed` | `--color-canvas` | background, text | Default editorial canvas and reversed text on dark imagery. |
| Frosted grey | `#e7e7e7` | `--color-glass` | surface | Visible light-canvas result of rgba(224,224,224,0.45); the translucent navigation changes appearance over media. |
| Action grey | `#7a7a7a` | `--color-secondary` | text, link | Secondary action lines, inline project references and subordinate role labels. |
| Near-black ink | `#1c1c1c` | `--color-ink` | text, background | Primary text and vertical rules; also dark testimonial surfaces in the dark variant. |
| Media black | `#000000` | `--color-black` | background | Backing beneath the opening light field. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalogue layouts and photographic frames | Gallery white | `#ffffff` | `--color-white` | background, surface | White frames and the catalogue canvas. |
| capability and credibility chapters | Chapter black | `#050505` | `--color-night` | background | Full dark editorial canvas. |
| catalogue captions | Subdued caption grey | `#a2a2a2` | `--color-caption` | text | Visible rgba(122,122,122,0.7) over white for catalogue descriptors. |

## Typography

- **Graphik** — All editorial statements, titles, descriptions and actions. Compact contemporary grotesk with a high x-height, medium strokes and very tight headline spacing. If unavailable, use **Inter**. Use weight 500 and preserve negative tracking; tune line breaks to maintain the compact silhouette. Font stack: "Graphik", "Inter", Arial, sans-serif.
- **LCDDot TR** — The two navigation labels. Dot-matrix capitals, like a tiny electronic readout. If unavailable, use **DotGothic16**. Use weight 400; retain the 20px line box and airy 0.5px tracking. Font stack: "LCDDot TR", "DotGothic16", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Graphik | 500 | 60px | 1 | -0.05em | Editorial lead paragraphs, proof headings, section/action pairs and the final invitation. |
| hero-statement | Graphik | 500 | 40px | 1.05 | -0.05em | Centered sentence over the optical opening; also secondary editorial statements and chapter links. |
| navigation | LCDDot TR | 400 | 20px | 1 | 0.025em, uppercase | Short left and right links in the floating bar. |
| label | Graphik | 500 | 18px | 1.1 | -0.04em | Section rail labels, project titles and person name/role pairs. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability and credibility chapters | quote | Graphik | 500 | 24px | 1.1 | -0.021em | Testimonial statements inside the dark proof cards. |
| catalogue layouts | caption | Graphik | 500 | 13px | 1.25 | -0.031em | Short descriptive line beneath catalogue titles. |

**Notes:**

- The primary size ladder is 18px → 40px → 60px; lengthy positioning copy can occupy the largest tier instead of using a conventional small body paragraph.
- Keep primary display tracking at -0.05em and line boxes almost closed. Maintain sentence case rather than uppercase display headlines.
- The grey action line shares the heading's size, weight and tracking. It is not a smaller link beneath a heading.
- Use the medium visual cut for captions even where a text declaration requests regular weight.

## Layout

**Density:** Airy at the section scale, compact within labels and text pairs; long visual holds contrast with nearly touching headline lines.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Catalogue title-to-caption gap and tiny badge adjacency. |
| 10px | Repeated media gaps and compact flex groups. |
| 15px | Catalogue image-to-title group gap. |
| 20px | Default page gutters, navigation side padding and directory row gaps. |
| 40px | Wide editorial gutters and section heading-to-media separation. |
| 50px | Inset after a directory divider and generous close grouping. |
| 100px | Bottom breathing room for major sections and catalogue top/side padding. |
| 110px | Both catalogue grid gaps. |
| 150px | Dark recognition chapter vertical padding. |
| 200px | Dark editorial opening top space and proof chapter inset. |

### Containers and grids

- **media canvas**: gap 10px · side padding 20px. Near-full-width media panels occupy 1400px at a 1440px desktop width.
- **editorial rail**: side padding 40px. Small left-hand section label separated by a thin vertical rule from a dominant right-hand statement or list.
- **catalogue grid** (only for catalogue pages): 4 columns · gap 110px · side padding 100px. Four equal project columns; each desktop tile is 228px wide with a square image.
- **split directory** (only for people and partner directories): 2 columns · side padding 20px. Two roughly 700px halves divided by a 2px rule; sticky 560px statement on the left, 638px profile rows inset on the right.
- **proof columns** (only for capability and credibility chapters): max width 450px. Two staggered streams of quote cards with substantial central negative space.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media panels | 10px |
|  | navigation and signup object | 20px |
|  | project capsules | 9999px (pill) |
| catalogue pages | catalogue thumbnails | 15px |
| people directories | profile row | 13px |
| people directories | metadata badge | 30px |

## Surfaces and depth

### Surfaces

#### Editorial canvas · level 0

**Use:** Default page surface.

**CSS:** `background: #ededed; color: #1c1c1c`

**Observed:** Untextured cool grey extends through editorial sections and the close.

**Transfer:** Let imagery provide material richness instead of adding grain to the whole page.

#### Optical stage · level 0

**Use:** Opening atmosphere.

**CSS:** `background: #000000; overflow: hidden`

**Observed:** Blue-white rays and a small bright focal point sit over an almost black field.

**Transfer:** Use the Convergent light field recipe for the luminous layer.

#### Frosted navigation · level 2

**Use:** Floating navigation over light or dark content.

**CSS:** `background: rgba(224, 224, 224, 0.45); border-radius: 20px; backdrop-filter: blur(10px)`

**Observed:** Content behind the bar contributes to its tone; no border or drop shadow is needed.

**Transfer:** Maintain translucent grey rather than choosing a separate opaque nav for every section.

#### Blue conversion object · level 1

**Use:** Small, isolated signup area.

**CSS:** `background: #0038ff; color: #ededed; border-radius: 20px`

**Observed:** A concentrated vivid rectangular object shares the horizontal center of the navigation, with a short promise and one-line form.

**Transfer:** Keep the surrounding page neutral so the single color object carries the conversion emphasis.

#### Dark chapter · level 0

**Only for:** capability and credibility chapters

**Use:** Long-form capability and credibility content.

**CSS:** `background: #050505; color: #ededed`

**Observed:** The page remains black through text, capabilities, quotes, recognition and the chapter exit.

**Transfer:** Use as a coherent page theme, not as randomly alternating cards.

#### Quote card · level 1

**Only for:** capability and credibility chapters

**Use:** Proof cards on the dark canvas.

**CSS:** `background: #1c1c1c; color: #ededed; border-radius: 15px`

**Observed:** Matte charcoal rectangles with no visible border or shadow; a quote sits high and attribution low.

**Transfer:** Preserve the quiet contrast and large interior void.

## Components

### Floating navigation

**Use:** Persistent, compact global orientation.

**CSS:** `width: 470px; height: 53px; padding: 0px 20px; border-radius: 20px; background: rgba(224, 224, 224, 0.45); backdrop-filter: blur(10px); color: #1c1c1c; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — LCDDot TR 400 · 20px/1 · tracking 0.025em · uppercase

**Observed:** Two short links flank a compact centered identity; the entire unit floats near the top center and stays above the page's media.

**Transfer:** Use two meaningful destination labels and the new product's identity, keeping the same three-part balance.

### Heading action pair

**Use:** Introduce a proof area and its onward route.

**CSS:** `display: flex; flex-direction: column; gap: 0px; color: #1c1c1c`

**Text style:** `display` — Graphik 500 · 60px/1 · tracking -0.05em

**Observed:** A sentence-case heading is immediately followed by a same-size grey text action. The proof-area pair is centered; the final invitation version is left aligned.

**Transfer:** Make the second line a real action, not another slogan.

### Project capsule

**Use:** Identify and open a large media panel.

**CSS:** `border-radius: 9999px; display: flex; align-items: center; gap: 10px; background: #000000; color: #ededed`

**Observed:** A small circular identity thumbnail, a short project name and a subdued uppercase action sit in a capsule at the lower center of a panel. Some capsules borrow a hue from their image.

**Transfer:** Keep the capsule visually tiny against the artwork; use a flat colored disc when no identity thumbnail exists.

### Closing invitation

**Use:** Main landing-page conversion close.

**CSS:** `height: 900px; padding-bottom: 100px; background: #ededed; color: #1c1c1c`

**Text style:** `display` — Graphik 500 · 60px/1 · tracking -0.05em

**Observed:** An isolated blue signup object sits high and centered; far below it a small identity and the two-line invitation sit low and left. The catalogue version adds a shallow contextual note beneath the close.

**Transfer:** Retain the asymmetry between centered color object and left-aligned invitation.

### Signup object

**Use:** Concentrated newsletter conversion.

**CSS:** `width: 460px; border-radius: 20px; background: #0038ff; color: #ededed`

**Observed:** A compact identity/navigation row tops a tall rounded rectangle; a two-line promise is centered vertically above one horizontal email input and pale rounded rectangular Submit button. It feels like the floating bar has unfolded into an object.

**Transfer:** Use a brief benefit statement and one input. Match the soft translucent input and restrained button; do not introduce a full contact form.

### Project tile

**Only for:** catalogue pages

**Use:** Compact browsable catalogue item.

**CSS:** `width: 228px; display: flex; flex-direction: column; align-items: center; gap: 15px; color: #1c1c1c`

**Text style:** `label` — Graphik 500 · 18px/1.1 · tracking -0.04em

**Observed:** A square rounded thumbnail sits above a centered title and a smaller grey caption separated by 5px. The whole tile is the link, with no enclosing painted card.

**Transfer:** Use one strong image per destination and a short title plus descriptor.

### Profile row

**Only for:** people directories

**Use:** Human or partner directory detail.

**CSS:** `width: 638px; height: 220px; display: flex; align-items: flex-start; gap: 10px; border-radius: 13px; overflow: hidden`

**Text style:** `label` — Graphik 500 · 18px/1.1 · tracking -0.04em

**Observed:** A narrow monochrome portrait sits left of name and muted role; a tiny blue origin badge follows the name. Rows are unboxed against the canvas, separated by 20px.

**Transfer:** Retain the photographic intimacy and straightforward role labels; use metadata only when meaningful.

### Chapter link

**Only for:** editorial chapter pages

**Use:** End a narrative chapter with a full-screen onward route.

**CSS:** `height: 890px; border-radius: 10px; padding: 0px 20px 0px 30px; background: #ededed; color: #1c1c1c; display: flex; flex-direction: column; align-items: center; justify-content: center`

**Text style:** `hero-statement` — Graphik 500 · 40px/1.05 · tracking -0.05em

**Observed:** An almost viewport-sized link has a 5px surrounding inset. Two compact lines sit at the exact visual center, the destination in grey; the dark version preserves the black theme.

**Transfer:** Use for a genuine next chapter rather than adding a conventional multi-column footer.

### Testimonial card

**Only for:** capability and credibility chapters

**Use:** Personal social proof on a dark chapter.

**CSS:** `max-width: 450px; background: #1c1c1c; color: #ededed; border-radius: 15px`

**Text style:** `quote` — Graphik 500 · 24px/1.1 · tracking -0.021em

**Observed:** Quote at the top, monochrome circular portrait and two-line attribution at the bottom; two staggered columns float past a large central proof heading.

**Transfer:** Use attributable short quotes and preserve the deep space between statement and author.

## Imagery and graphics

### Convergent light field

**Use:** Signature atmospheric opening and its continuing scroll scene.

**Observed:** Hundreds of fine blue-white rays converge on one small luminous point near the center, spreading beyond all edges on a near-black blue field. Some rays are crisp, others softly blooming; the brightest nucleus sits behind the sentence.

**Transfer:** Express the new product's emotional premise through light rather than literal illustration. The minimum version is a static SVG ray field with a tiny glow, not a generic gradient.

**Build:** Create a 1440px × 900px SVG over black. Fan 120–200 irregular radial line segments outward from the center to beyond the viewBox edges, leaving many rays faint or interrupted near the nucleus. Use rgba(237,237,237,0.12) and rgba(94,129,255,0.25), stroke widths 0.5px–2px. Duplicate about 15 brighter rays at 3px–8px widths with 4px–10px Gaussian blur. Add a 12px pale central disc with a 25px blue-white blurred halo. Darken the outer field with an alpha-black vignette; preserve the optical depth and uneven density.

### Tangible product worlds

**Use:** Expansive proof media panels.

**Observed:** Oversized sculptural products, devices and printed objects sit on richly colored or tactile backings: a glossy purple chair against blue fabric, exploded dark goggles with turquoise accents, a diagonal phone on warm ochre material, packaging under hard directional light, and a tablet on figured plywood. Objects fill much of the panel, often continuing beyond its edges.

**Transfer:** Photograph or render the new product in a composed physical environment. For software, place one clean interface on a believable phone, laptop or tablet with a single textured backing and directional light; keep interface details subordinate to the composition.

### Monochrome portrait constellation

**Only for:** culture and people pages

**Use:** Image-only people-page opening and directory portraits.

**Observed:** Expressive black-and-white photo-booth portraits, often with a dark curtain behind them, sit inside slim white rounded print borders. The opening scatters many differently scaled vertical prints in a loose tall oval, with overlap and open grey space; the directory uses larger aligned versions.

**Transfer:** Use candid portraits with varied expression, consistent monochrome treatment and print-like frames, rather than corporate headshot circles.

**Build:** Arrange portrait images in an SVG or positioned container in several loose vertical arcs. Vary image widths around 65px–110px for the desktop constellation, use white 4px frames and 4px corners, and overlap a minority of prints. Keep most upright and leave generous gaps so the silhouette reads as a floating crowd.

### Editorial recognition rail

**Only for:** capability and credibility chapters

**Use:** Dense proof without image tiles.

**Observed:** A thin pale vertical rule separates the small label from a long stacked list. Each entry combines a tiny electric-blue capsule, small contextual text and a prominent pale publication or award name on black.

**Transfer:** Use comparable verified credentials or milestones; maintain the typographic rail rather than substituting a logo grid.

## Section recipes

How recurring sections are built.

### First screen: Optical sentence opening

**Observed:** The first 900px is entirely the Optical stage, with Convergent light field behind a single centered hero-statement sentence, roughly half the screen width. The focal point aligns with the sentence's middle. Floating navigation sits near the top center as the foremost layer; no separate sales button or support paragraph competes in this first screen. Further explanation enters below the fold as a narrow centered 40px statement over the continuing light scene, which later becomes an inset rounded media panel against grey.

**Transfer:** Give a different product one emotional sentence and an equally immersive luminous field; the SVG fallback is sufficient without a render. Catalogue pages instead open immediately into Project tiles on white; culture pages use the portrait constellation; dark editorial chapters open with a small rail label and 60px lead paragraph.

**Avoid:** Do not replace the scene with a conventional split hero, giant wordmark, dashboard collage or two-button sales stack. Do not make the central sentence 60px merely because later editorial text is larger.

**Text style:** `hero-statement` — Graphik 500 · 40px/1.05 · tracking -0.05em

### Full-width editorial statement

**Observed:** A 60px display paragraph stretches almost the entire grey width with 20px left and 40px right inset, followed by 100px bottom space. Selected project names within the sentence are grey.

**Transfer:** Use one substantial positioning statement with a few meaningful inline references rather than a row of feature cards.

**Text style:** `display` — Graphik 500 · 60px/1 · tracking -0.05em

### Media proof stack

**Observed:** Heading action pair introduces Tangible product worlds. Wide rounded panels sit in the media canvas with minimal gaps; each has a Project capsule at its lower center.

**Transfer:** Use a small set of visually distinct outcomes, demonstrations or applications; vary materials and object scale instead of repeating identical device mockups.

**Text style:** `display` — Graphik 500 · 60px/1 · tracking -0.05em

### Object and invitation close

**Observed:** Closing invitation combines Signup object above and Heading action pair below, with the identity preceding the low-left text. The default grey close fills a 900px screen. Editorial chapter pages instead end with Chapter link, preserving their light or dark canvas.

**Transfer:** Close a landing page with a quiet invitation after image-led proof; use the chapter exit only when another narrative chapter really follows.

**Text style:** `display` — Graphik 500 · 60px/1 · tracking -0.05em

### White visual catalogue

**Only for:** catalogue pages

**Observed:** The catalogue grid begins about 100px below the top and uses Project tiles in four columns on white. The repeated title/caption hierarchy stays tiny relative to the images and broad inter-column voids.

**Transfer:** Use for product collections or customer stories when rapid browsing matters more than a single narrative.

### Sticky statement directory

**Only for:** people and partner directories

**Observed:** A 40px statement stays near the upper left while the right side scrolls through Profile rows, separated by a thin vertical rule. A large centered recruitment heading/action pair sits between the portrait opening and directory.

**Transfer:** Use for people, partners or other human-led lists; preserve the independent pace of left statement and right list.

**Text style:** `hero-statement` — Graphik 500 · 40px/1.05 · tracking -0.05em

### Dark capability rail

**Only for:** capability and credibility chapters

**Observed:** Dark chapter opens with 200px of top space. A small label occupies a narrow left rail; a pale vertical rule marks the beginning of a broad 60px paragraph. Later capabilities are arranged as sparse text columns, each with a tiny heading and a ruled list.

**Transfer:** Use for a detailed point of view or capability explanation that needs a slower, more editorial mode.

**Text style:** `display` — Graphik 500 · 60px/1 · tracking -0.05em

### Floating social proof

**Only for:** capability and credibility chapters

**Observed:** A centered 60px proof headline holds the middle while Testimonial cards form two widely separated, staggered streams. The chapter leaves extensive black breathing room before the recognition rail.

**Transfer:** Let a small set of strong endorsements create depth around a central proposition instead of filling a compact three-card grid.

**Text style:** `display` — Graphik 500 · 60px/1 · tracking -0.05em

## Page flow

**Storyline:** Emotional premise → expanded positioning → visual or human proof → focused credibility → invitation or onward chapter.

### Image-led marketing landing page

1. **Emotional promise** — Optical sentence opening with a luminous focal point.
2. **Positioning** — Centered explanation over the continuing scene, then a broad editorial statement.
3. **Orientation** — A restrained jump-to rail precedes the proof.
4. **Product proof** — Heading action pair and a sequence of large tactile media panels.
5. **Closing call** — Blue signup object and low-left invitation.

**Transfer:** Substitute the new product's promise and strongest applications; preserve the optical opening, image scale and distinctive closing contrast.

### People and culture narrative

1. **Human introduction** — Portrait constellation fills the opening.
2. **Participation invitation** — Centered recruitment heading and grey action.
3. **Human proof** — Sticky statement beside the portrait directory.
4. **Onward chapter** — Centered two-line chapter link on grey.

**Transfer:** Use for the people behind a product or service rather than treating portraits as generic feature art.

### Browsable work or product index

1. **Breadth of proof** — Immediate four-column visual catalogue on white.
2. **Closing call** — Blue signup object and oversized two-line invitation.
3. **Context** — A shallow contextual note follows beneath the invitation.

**Transfer:** Keep the index image-first and reserve the principal conversion for its ending.

### Capability and credibility narrative

1. **Point of view** — Large pale positioning paragraph beside a small label rail on black.
2. **Capability chapters** — Ruled text lists in spacious columns.
3. **Social proof** — Staggered testimonial streams around a central headline.
4. **External validation** — Recognition list with blue badges and large names.
5. **Onward chapter** — Centered next-step link on the same black canvas.

**Transfer:** Use the dark variant for a coherent deeper explanation, with the proof supplied by the new product's own verified material.

## Writing

Confident, warm and design-literate. Emotional premises lead, but short functional labels and concrete descriptions keep the voice from becoming theatrical.

**Do not copy:** Do not reuse the Analogue name, wordmark, project artwork, client names, employee names, awards, quotations, claims or contact details. Replace them with the new product's own assets and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you/your for the reader, especially at the invitation. Describe collections and capabilities with plain nouns.
- **Rhythm:** One compact sentence can carry the opening; longer positioning thoughts run as tightly set editorial paragraphs. Headings and actions often form two clipped lines, with the action shorter than the proposition.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening premise | A human belief stated as a simple declarative sentence. | 7–12 words | “Emotion is the heart of every decision” |
| Positioning | Name the kind of practice, the place or focus, and what it makes in one continuous thought. | 25–45 words | “[Brand] is a brand and digital design studio in Amsterdam, building identity systems and digital experiences for design-led product brands.” |
| Section and action | A very short noun phrase paired with a direct onward verb. | 2–3 words per line | “Our work.”<br>“See all” |
| Closing invitation | Low-pressure readiness statement, then a plain action. | 2–5 words per line | “Ready when you are.”<br>“Book call” |
| Social proof heading | Conversationally hand the claim to other people. | 5–8 words | “Don't take our word for it.” |
| Chapter exit | A small narrative cue followed by the next subject. | 2–3 words per line | “Next chapter”<br>“Process & Pricing” |

**Words and phrasing to use:** meaningful; experiences; crafting; building; people; your product; next chapter; ready

**Avoid:** revolutionary platform; unlock limitless potential; best-in-class ecosystem; hurry; buy now!!!

**Rules:**

- Lead with a belief or felt benefit, then make the offering concrete.
- Use sentence case for prose and headings; reserve uppercase for dot-matrix navigation and tiny functional media actions.
- Keep project descriptors to one short line.
- Prefer a direct invitation to urgency or exaggerated performance promises.

## Do's and Don'ts

### Do

- Use 40px/42px type for the central opening sentence.
- Keep 60px display text at weight 500 with -0.05em tracking.
- Keep the navigation compact at 470px × 53px on desktop.
- Allow large proof imagery to approach the edges within 20px gutters.
- Keep most interface surfaces grey, black or white, concentrating vivid blue in one conversion object and tiny metadata.
- Make the action line share its heading's typography, changing its color to #7a7a7a.
- Use 110px gaps for the four-column catalogue variant.
- Keep a 900px closing composition with strong negative space rather than a dense sitemap.

### Don't

- Do not turn the 20px navigation corners into a fully circular pill.
- Do not add drop shadows to the flat editorial panels or portrait rows.
- Do not set all headings in bold 700; the medium 500 cut is the defining weight.
- Do not wash every section in blue; color should remain concentrated in objects and media.
- Do not enclose catalogue titles in additional bordered cards; the thumbnail and caption stand alone.
- Do not use colorful corporate headshot circles for the people-page constellation.
- Do not replace the low-left grey action with a bright full-width CTA button.
- Do not bring the black chapter theme into an ordinary grey landing page as arbitrary alternating stripes.

## Motion and responsive

### Motion

**Observed:**

- The opening sentence sits in a sticky layer above a continuing optical scene; subsequent views show the media becoming inset against grey.
- The people directory uses a sticky statement while its rows continue vertically.
- The floating navigation persists across scroll positions; dark proof cards overlap a central headline.

**Transfer:**

- Retain the light scene's focal point as the optical anchor while the frame contracts into the editorial canvas.
- Let layered proof and portrait scenes have a legible static composition as well as a moving one.

**Unknown:**

- Exact scene animation timing, ray motion, easing, hover treatments and focus-visible styles are not established.

### Responsive

**Observed:**

- Desktop layouts use a 1440px-wide viewport; declared width boundaries include 810px and 1200px, with additional component-specific boundaries.

**Transfer:**

- On narrow screens, preserve the centered focal sentence and a shallow floating navigation; wrap the sentence rather than making the optical field a side illustration.
- Reduce catalogue columns and stack directory text above rows when two halves no longer fit; retain image-led hierarchy and the grey action line.

**Unknown:**

- Exact mobile type sizes, spacing, column counts and navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
