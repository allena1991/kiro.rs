# Fiasco — feeling at full volume

## Overview

An expressive editorial style that pairs an almost-black olive canvas with warm paper and electric yellow. Airy grotesk headlines change voice mid-sentence through italic serif phrases, while vivid project films, dimensional graphics and candid photography supply the energy. It suits ambitious products and creative services that need to feel human as well as commercially credible; the density stays low even when the story is long.

### Essentials

- Headlines change register inside a sentence: regular 80px grotesk at 1.1 line height and -0.4px tracking mixes with same-size italic serif for the emotional or outcome-bearing phrase.
- The opening is a statement, not a dashboard: a centered 1152px-wide text composition on #1d1e19, a 20px italic label, three lines of headline, and the first media chapter entering near the bottom of a 900px screen.
- Buttons are compact punctuation under monumental type: 44px-high pills, 800px radius, 8px 20px padding, 18px semibold text and a small diagonal arrow.
- Color arrives in concentrated bursts: the default is a long dark narrative, a warm-paper proof layer and a full-width #fff714 conversion panel; green, blue and orange remain 24px chapter markers outside the imagery.
- Media is staged as artwork rather than boxed features: 496px × 372px films beside narrow editorial text, broad breathing spaces of 80px–160px, and vivid color contained within the image. Use a composed still-life or an abstract material film when product footage is unavailable.
- The page has physical layers and an enormous sign-off: 40px rounded full-width sheets with a 28px-down, 80px-blur shadow, followed by compact footer columns and a nearly edge-to-edge wordmark. Render the new product name as a bold fitted word sculpture when no wordmark exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric yellow | `#fff714` | `--color-yellow` | background, action, accent | Large conversion sheet, yellow button on dark ground and selected proof numerals. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fd6b01` | `--color-orange` | accent | Small expression-capability marker. |
| Signal green | `#03ac47` | `--color-green` | accent | Small capability symbol; also a numeral accent in quantified storytelling. |
| Sky blue | `#84bdff` | `--color-blue` | accent | Small digital-capability marker. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep olive | `#151612` | `--color-footer` | background | Footer and wordmark backing; darker than the main narrative. |
| Olive ink | `#1d1e19` | `--color-ink` | background, text, action | Default dark narrative canvas, text on paper and dark pill buttons. |
| Warm graphite | `#3e3f3b` | `--color-raised` | surface, action | Upper stop of proof-card gradients and dark-button hover fill. |
| Soft chalk | `#e9eae2` | `--color-chalk` | text, surface | Primary text on the dark canvas; muted neutral image backing and back-to-top disc. |
| Paper tag wash | `#edeee8` | `--color-tag-wash` | surface, border | Visible 5% olive ink over paper, used for tags and subtle light-layer edges. |
| Warm paper | `#f8f9f3` | `--color-paper` | background, text, surface | Light proof sheets and reversed button text. |
| White | `#ffffff` | `--color-white` | text | Navigation on dark ground; used with alpha for restrained secondary text and edges. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| quantified storytelling | Orchid pink | `#fcc5fe` | `--color-pink` | text | A contrasting proof numeral. |
| quantified storytelling | Dark card edge | `#343530` | `--color-dark-edge` | border | Visible white at 10% over olive ink, forming the fine outline of dark proof cards. |

## Typography

- **area-normal** — Display statements, body, navigation, numerals and actions. Open, broad geometric-humanist sans with light-looking regular headlines and an easy conversational texture. If unavailable, use **Manrope**. Use 400 and 600; preserve broad measures rather than increasing weight. Font stack: "area-normal", "Manrope", "Area Normal", sans-serif.
- **HAL Timezone** — Inline headline emphasis, chapter titles, quotes, italic labels and tiny metadata. Expressive editorial serif with a flowing italic and crisp, slightly idiosyncratic shapes. If unavailable, use **Source Serif 4**. Use regular italic for emphasis and 400–500 for editorial text; tune wrapping to the sans. Font stack: "HAL Timezone", "Source Serif 4", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | area-normal | 400 | 80px | 1.1 | -0.005em | fixed | Main marketing statement and monumental conversion heading. |
| display-emphasis | HAL Timezone | 400 italic | 80px | inherit | -0.005em | fixed | Inline emphasis only, inside the display line box; never a standalone block with zero line height. |
| heading | area-normal | 400 | 42px | 1.2 | -0.0095em | fixed | Centered supporting-section headings. |
| editorial | HAL Timezone | 400 | 34px | 1.2 | -0.0118em | fixed | Capability titles, testimonial statements and light editorial openings. |
| body-lead | area-normal | 400 | 24px | 1.24 | -0.0167em | fixed | Centered narrative support in the surrounding-media section. |
| eyebrow | HAL Timezone | 400 italic | 20px | 1.4 | -0.02em | fixed | Sentence-case opening labels, chapter labels and capability-list items. |
| body | area-normal | 400 | 18px | 1.6 | -0.022em | fixed | Paragraphs and media descriptions. |
| navigation | area-normal | 600 | 18px | 1.5 | -0.022em | fixed | Header and footer navigation. |
| button | area-normal | 600 | 18px | 1 | -0.022em | fixed | Pill actions. |
| attribution | area-normal | 400 | 18px | 1.4 | -0.022em | fixed | Name and role below a testimonial. |
| metadata | HAL Timezone | 400 | 12px | 2 | 0.01em | fixed | Category pills and reading metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| quantified storytelling | stat | area-normal | 400 | 88px | 0.95 | -0.03em | size clamp(56px, 7vw, 88px) | Colored proof numbers in square cards. |
| immersive method narratives | fluid-statement | area-normal | 400 | 86.4px | 1.1 | -0.0046em | size 6vw | Viewport-sized thesis behind floating proof cards. |
| immersive method narratives | timeline-word | area-normal | 400 | 80px | 1 | -0.02em | size clamp(42px, 5.6vw, 80px) | Single words along a vertical argument. |
| process and method chapters | chapter-heading | area-normal | 400 | 30px | 1.2 | -0.0133em | fixed | Short proposition within a layered explanation. |
| further-reading sections | article-title | HAL Timezone | 500 | 22px | 1.2 | -0.018em | fixed | Editorial card titles. |
| project collections and related projects | project-title | HAL Timezone | 500 italic | 20px | 1.4 | -0.02em | fixed | Titles under portfolio images. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headlines stay regular, not bold; contrast comes from scale and switching family. Most text keeps the same -0.4px tracking rather than proportionally tightening every size.
- Italic emphasis shares the surrounding display size and baseline. Its zero line height is an inline construction detail: the sans parent supplies the readable line box.
- Serif is not reserved for prestige headlines: it also appears at 20px in lists and 12px in category labels. Avoid all-capital technical eyebrows.

## Layout

**Density:** Airy: full-width scenes are interrupted by narrow reading measures, with pauses as important as the content.

### Spacing

**Spacing system:**

- **horizontal token** 16px, horizontal — Base side-padding and grid token; desktop section padding commonly doubles it to 32px.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 12px | Eyebrow-to-display gap, button icon gap and tag side padding. | fixed |
| 18px | Project image-to-title spacing. | fixed |
| 24px | Capability-list row gap and paragraph separations. | fixed |
| 32px | Desktop page gutters, grid gap and quote-stack separation. | fixed |
| 56px | Capability heading-to-body and body-to-list separation. | fixed |
| 64px | Start of the first media chapter. | fixed |
| 80px | Layer padding and overlap depth. | fixed |
| 120px | Footer upper padding and roomy editorial pauses. | fixed |
| 160px | Major chapter separation and portfolio row pauses. | fixed |
| 30px | Proof-card padding. | clamp(18px, 3vw, 30px) |

### Containers and grids

- **page**: max width 1440px · side padding 32px. Full-width layered page with a persistent inner gutter.
- **opening**: max width 1152px. Centered marketing headline spanning about four fifths of the desktop width.
- **reading**: max width 680px. Centered supporting narrative or a narrow text column.
- **conversion**: max width 940px. Centered closing question or invitation.
- **testimonial**: max width 960px. Centered editorial quote; attribution occupies a much narrower measure.
- **capability split**: 2 columns · gap 32px. Two 496px-wide content fields separated by open grid columns; left media, right editorial content.
- **article grid** (only for further-reading sections): 4 columns · gap 32px. Four approximately 320px-wide editorial cards.
- **proof grid** (only for quantified storytelling): max width 940px · 3 columns · gap 34px. Three 291px square proof cards with staggered vertical positions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | layer | 40px |
|  | pill | 800px |
|  | media | 8px |
|  | back-to-top | 44px |
| quantified storytelling | proof card | 10px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | layer lift | `rgba(0, 0, 0, 0.16) 0px 28px 80px 0px` | Broad soft separation beneath overlapping paper and yellow sheets. |
| process and method chapters | chapter lift | `rgba(0, 0, 0, 0.08) 0px -20px 80px 0px` | Soft upward separation between paper explanation layers. |

### Surfaces

#### Dark canvas · level 0

**Use:** Default opening and capability narrative.

**CSS:** `background: #1d1e19; color: #e9eae2`

**Observed:** A flat olive-black ground, not a cool blue-black gradient.

**Transfer:** Let saturated art supply local color against this neutral field.

#### Paper sheet · level 1

**Use:** Testimonials and longer light editorial content.

**CSS:** `background: #f8f9f3; color: #1d1e19; border-radius: 40px; box-shadow: rgba(0, 0, 0, 0.16) 0px 28px 80px 0px; padding-bottom: 80px`

**Observed:** A full-width sheet overlaps the preceding scene by 80px; rounding belongs to page-scale layers.

**Transfer:** Keep the same material change for a proof or reassurance block.

#### Yellow sheet · level 1

**Use:** High-impact conversion band.

**CSS:** `background: #fff714; color: #1d1e19; border-radius: 40px; box-shadow: rgba(0, 0, 0, 0.16) 0px 28px 80px 0px; padding-top: 80px`

**Observed:** It sits beneath the preceding sheet and is progressively revealed.

**Transfer:** Keep yellow concentrated into a decisive editorial moment.

#### Footer ground · level 0

**Use:** Navigation and monumental wordmark.

**CSS:** `background: #151612; color: #e9eae2`

#### Proof graphite · level 2

**Only for:** quantified storytelling

**Use:** Floating numerical proof.

**CSS:** `background: linear-gradient(#3e3f3b, #1d1e19); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 10px`

**Observed:** A restrained vertical gradient adds material depth without glass blur.

**Transfer:** Use for a small set of verified outcomes, not every feature.

#### Paper chapter · level 1

**Only for:** process and method chapters

**Use:** Stacked explanation panels.

**CSS:** `background: #f8f9f3; border-top: 1px solid rgba(29, 30, 25, 0.05); box-shadow: rgba(0, 0, 0, 0.08) 0px -20px 80px 0px; padding: 80px 32px`

**Observed:** Full-width sticky layers, each approximately 540px tall, pair copy with media.

**Transfer:** Give each layer one proposition.

## Components

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; padding: 20px 32px 30px; display: flex; justify-content: space-between; align-items: center; z-index: 99`

**Text style:** `navigation` — area-normal 600 · 18px/1.5 · tracking -0.022em

**Observed:** Wordmark at left; a single unboxed row of links at right, followed by a local clock with a small country indicator. Text flips between dark and light with the ground.

**Transfer:** Use a short destination set and keep the logo optically larger than the links.

### Dark pill

**Use:** Action on paper or yellow.

**CSS:** `display: inline-flex; align-items: center; gap: 12px; background: #1d1e19; color: #f8f9f3; border-radius: 800px; padding: 8px 20px; height: 44px; box-sizing: border-box`

**Text style:** `button` — area-normal 600 · 18px/1 · tracking -0.022em

**Observed:** Text precedes a small down-right arrow. Width is content-driven.

**States:** Declared: hover background-color #3e3f3b and color #f8f9f3; focus-visible background-color #1d1e19, color #f8f9f3, outline 1px solid #1d1e19 and outline-offset 3px.

### Yellow pill

**Use:** Primary action against dark ground.

**CSS:** `display: inline-flex; align-items: center; gap: 12px; background: #fff714; color: #1d1e19; border-radius: 800px; padding: 8px 20px; height: 44px; box-sizing: border-box`

**Text style:** `button` — area-normal 600 · 18px/1 · tracking -0.022em

**Observed:** Same compact geometry as the dark variant, with the same trailing diagonal arrow.

**States:** Declared: hover background-color #dcd401 and color #1d1e19; focus-visible background-color #fff714, color #1d1e19, outline 1px solid #fff714 and outline-offset 3px.

### Capability list

**Use:** A chapter's concrete offer beneath its introductory paragraph.

**CSS:** `display: grid; gap: 24px; margin-top: 56px; color: #f8f9f3`

**Text style:** `eyebrow` — HAL Timezone 400 italic · 20px/1.4 · tracking -0.02em

**Observed:** One italic serif item per row, no bullets, dividers or enclosing card. A small group of subdued project links follows the list.

**Transfer:** List specific capabilities rather than slogans.

### Category pill

**Use:** Small taxonomy attached to media and articles.

**CSS:** `background: rgba(29, 30, 25, 0.05); color: #1d1e19; border-radius: 800px; padding: 0px 12px; height: 24px`

**Text style:** `metadata` — HAL Timezone 400 · 12px/2 · tracking 0.01em

**Observed:** A tiny solid symbol precedes text. Tags wrap with a 4px gap. The dark-ground variant uses white at 5% for the fill and chalk text.

**Transfer:** Keep this subordinate to the title.

### Quote stack

**Use:** Focused social proof on the paper sheet.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 32px; max-width: 960px; text-align: center`

**Text style:** `editorial` — HAL Timezone 400 · 34px/1.2 · tracking -0.0118em

**Observed:** Quotation mark above the statement, then a two-line attribution. Three client-logo selectors sit well below the quote, followed by one Dark pill linking to the associated project.

**Transfer:** Use one substantial quote at a time rather than a wall of small testimonial cards.

### Back to top

**Use:** Discrete navigation at the bottom left of a major sheet.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 44px; height: 44px; background: #e9eae2; border-radius: 44px`

**Observed:** A thin upward arrow sits inside the pale disc, aligned with the page gutter.

### Footer columns

**Use:** Final navigation above the word sculpture.

**CSS:** `display: grid; gap: 32px; color: #e9eae2`

**Text style:** `navigation` — area-normal 600 · 18px/1.5 · tracking -0.022em

**Observed:** Three short link columns occupy the left portion; copyright sits farther right. The surrounding Footer ground has 120px upper padding and 32px gutters.

**Transfer:** Keep destinations terse and leave the lower area to the enormous name.

### Project tile

**Only for:** project collections and related projects

**Use:** Editorial proof through a body of visual work.

**CSS:** `object-fit: cover`

**Text style:** `project-title` — HAL Timezone 500 italic · 20px/1.4 · tracking -0.02em

**Observed:** Image first, italic title after an 18px–20px pause, then 18px body summary and category pills. No card backing or independent card shadow. Sizes and aspect ratios vary across staggered columns.

**Transfer:** Use real outcomes as the caption; preserve mixed media proportions.

### Proof card

**Only for:** quantified storytelling

**Use:** A small collection of consequential numbers.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; width: 291px; height: 291px; box-sizing: border-box; padding: 30px; background: linear-gradient(#3e3f3b, #1d1e19); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 10px`

**Text style:** `stat` — area-normal 400 · 88px/0.95 · tracking -0.03em

**Observed:** Number at top, short body explanation at bottom; yellow, pink and green distinguish the numbers. Cards float at different heights across the headline.

**Transfer:** Use defensible product outcomes and keep explanations brief.

### Reading tile

**Only for:** further-reading sections

**Use:** Extend the story into editorial material.

**CSS:** `position: relative; overflow: hidden; border: 1px solid transparent`

**Text style:** `article-title` — HAL Timezone 500 · 22px/1.2 · tracking -0.018em

**Observed:** Image, serif title, then tiny category and reading-time pills. Four cards share the row without panel fills.

**Transfer:** Keep imagery heterogeneous: conceptual graphics next to candid working photographs.

## Imagery and graphics

### Capability films

**Use:** The recurring visual counterpart to capability chapters.

**Observed:** A compact 4:3 stage carries changing work: glossy green folded material, a cyan-and-pink dimensional emblem on paper, a colorful phone interface and an orange vehicle-like dimensional model. Color is rich, light is soft and directional, and the media occupies roughly the same width as its text column.

**Transfer:** Create a tactile product detail, a deliberately styled interface close-up or a simple dimensional form. Minimum acceptable treatment is one sharply art-directed still per capability, with coherent lighting and no stock-photo collage.

### Surrounding media constellation

**Use:** A centered narrative surrounded by independent visual fragments.

**Observed:** Small films and images sit near the edges at different heights and proportions, with a broad central clearance for the text. Individual scenes have their own color backdrops; the page ground stays dark.

**Transfer:** Use product applications, process details and people as peripheral fragments. Preserve a quiet reading island rather than a symmetric card grid.

**Build:** Use a relatively positioned full-width stage around a centered 680px text column. Place four or five rectangular media elements in outer columns, at alternating upper and lower positions; use widths around 302px–475px and varied 4:3, 16:9 and square ratios. Allow some edge clipping, but never cover the text.

### Monumental name

**Use:** Required final graphic sign-off.

**Observed:** A warm-paper wordmark fills a 1376px × 391px region within 32px gutters on deep olive. It is a solid, clean vector shape, not outlined or textured; the name dominates the final screen far more than the links.

**Transfer:** Fit the new brand's own name to nearly the full width. If no logo artwork exists, use a bold sans word rendered as a fitted SVG and treat it as artwork rather than a normal heading.

**Build:** Create an SVG with a tight viewBox around one bold word; set its fill to #f8f9f3 and width to 100%, keeping 32px page gutters. Size the word by its actual length so its silhouette fills the available width; keep 80px above and 32px below the artwork.

### Culture constellation

**Only for:** culture and company storytelling

**Use:** Immersive bright opening and people-led interludes.

**Observed:** Candid workplace portraits, a dog on a sofa, conversations and project applications float around the margins of a flat yellow field. Rectangles are square-edged and unevenly sized, with the central statement left clear.

**Transfer:** Photograph actual people in their working environment with natural light. Keep spontaneous poses and varied crops rather than formal headshots.

**Build:** Use a solid #fff714 full-width stage. Distribute six or more separate image rectangles around the outer perimeter with mixed portrait and landscape ratios; clip several at the viewport edges. Reserve the central half for dark text, then reuse the constellation around smaller centered passages.

### Case-study art direction

**Only for:** project detail pages

**Use:** Long-form visual demonstration of a single system.

**Observed:** Wide graphic panels alternate with narrow paper text, dimensional device photographs, dense application mosaics, outdoor advertising and paired portrait/landscape details. A central carousel panel is flanked by partly visible neighbours. Each project's own palette stays within its imagery.

**Transfer:** Show the product across scales: system view, close detail, real-world context and human use. Keep project-specific type and colors inside the demonstration rather than importing them into the marketing shell.

### Icons

**Observed:** Buttons use small 16px diagonal arrows; the back-to-top disc uses a thin upward arrow. Capability markers are 24px solid abstract geometry: stacked ellipses, an inset square and offset bars. Tags use much smaller solid category symbols.

**Transfer:** Use simple filled geometric chapter symbols rather than a generic outlined feature-icon set. Construct markers with SVG ellipses, rectangles or stepped paths in one accent color; keep action arrows visually lighter.

## Section recipes

How recurring sections are built.

### First screen: Statement opening

**Observed:** Dark canvas behind a fixed Navigation. A small centered italic label begins the statement well below the header; the 80px display is centered in a 1152px measure and occupies three lines, switching to display-emphasis on two key phrases. The intro region is 720px tall with 100px vertical padding and a 12px label gap. Within the first 900px the entire statement is visible, followed by generous dark space and the top of a 496px-wide media stage on the left and a serif chapter title on the right. There is no hero button, extra support paragraph or central product object: the first media chapter begins below the headline, near the fold.

**Transfer:** Write one complete product promise that can carry the opening without a render. Emphasize the feeling and outcome through serif phrases, then introduce the first product scene at the fold. A collection can instead open with a compact 34px serif introduction over paper; a project detail can lead with a full-width film before its paper editorial summary; culture stories use Culture constellation.

**Avoid:** Do not convert this into a left-aligned headline beside a giant laptop, a two-button hero or a gradient-text slogan.

**Text style:** `display` — area-normal 400 · 80px/1.1 · tracking -0.005em

### Capability chapter

**Observed:** Dark canvas carries left-hand Capability films and right-hand editorial content, each about 496px wide. A 24px accent symbol precedes the 34px serif title. Body follows after 56px, then Capability list after another 56px. Subdued related links finish the chapter. Chapter transitions leave around 160px of air, while the media stage remains sticky.

**Transfer:** Use one chapter per substantial promise, matching the film to the content rather than adding a separate card for every list item.

**Text style:** `editorial` — HAL Timezone 400 · 34px/1.2 · tracking -0.0118em

### Narrative island

**Observed:** A 42px centered heading and 24px body-lead sit within a 680px measure on Dark canvas, with paragraph gaps of 24px and a Yellow pill 40px below the copy. Surrounding media constellation occupies the outer edges of a tall stage.

**Transfer:** Use for an ecosystem, collaboration story or broader product value; let the text remain the center of attention.

**Text style:** `heading` — area-normal 400 · 42px/1.2 · tracking -0.0095em

### Paper testimonial

**Observed:** Paper sheet rises over the dark stage with a soft layer shadow and 40px corners. Quote stack sits centrally with abundant top and bottom breathing room, client-logo selectors and a project action. Back to top sits at the lower left.

**Transfer:** Replace the quote and logo set with genuine proof; keep the transition from dark narrative to paper reassurance.

**Text style:** `editorial` — HAL Timezone 400 · 34px/1.2 · tracking -0.0118em

### Closing invitation and name

**Observed:** Yellow sheet is revealed beneath the preceding paper layer, carrying a centered 80px regular invitation in a 940px measure and a Dark pill. Footer columns follow on Footer ground, then Monumental name fills almost all the width. The closure is a large graphic event, not a small legal strip.

**Transfer:** Write a plain-spoken invitation appropriate to the new conversion. Retain both the concentrated bright panel and the huge name, adapting their content rather than reproducing a fixed section count.

**Text style:** `display` — area-normal 400 · 80px/1.1 · tracking -0.005em

### Staggered portfolio

**Only for:** project collections

**Observed:** On paper, image-led Project tiles occupy two independently paced columns with 160px pauses. Images range from 497px to 672px wide and mix landscape and portrait proportions. A dark floating category filter sits near the bottom center; a dark question band can interrupt the collection before a fresh rounded paper layer.

**Transfer:** Group examples by visual and narrative rhythm rather than equalizing every card.

**Text style:** `project-title` — HAL Timezone 500 italic · 20px/1.4 · tracking -0.02em

### Floating numerical proof

**Only for:** quantified storytelling

**Observed:** Three Proof cards cross the large centered statement, staggered vertically in a 940px grid. Their 88px numerals use short symbols and percentages; explanations remain 18px body. A separate paper variant presents 80px unboxed numbers in three rows, with explanations alongside.

**Transfer:** Use cards for immersive thesis proof and unboxed rows for company outcomes; do not mix both formats into a dense analytics dashboard.

**Text style:** `stat` — area-normal 400 · 88px/0.95 · tracking -0.03em

### Vertical argument and layered explanation

**Only for:** process and method narratives

**Observed:** Single 80px words form a centered vertical chain, joined by slender lines with changing color highlights. A short centered paragraph and Yellow pill resolve the chain. Later, Paper chapter layers pair a 20px italic label, 30px proposition and 18px body with a right-side 584px × 329px media panel; a 42px centered heading anchors the group.

**Transfer:** Translate a product's causal story into a few human-readable concepts; then give each concept an explanatory layer and a real demonstration.

**Text style:** `chapter-heading` — area-normal 400 · 30px/1.2 · tracking -0.0133em

### Case-study editorial rhythm

**Only for:** project detail pages

**Observed:** A full-width opening film gives way to a rounded paper introduction: italic 20px project label, 34px serif summary, 18px paragraphs and small taxonomy. Wide media panels alternate with text confined to roughly 496px in a 1024px interior measure. Dark and paper testimonial interruptions lead to a dark closing invitation, two related projects and the shared footer.

**Transfer:** Use the long form only when the product warrants an unfolding visual argument; carry the project's palette in media, not in the shell.

**Text style:** `editorial` — HAL Timezone 400 · 34px/1.2 · tracking -0.0118em

## Page flow

**Storyline:** Statement → visual capability or application → human explanation → credible proof → direct invitation → monumental name.

### Present a product or service offer with depth

1. **Promise** — Dark mixed-family statement with a small italic label.
2. **Capability chapters** — Sticky media opposite serif headings, paragraphs and italic lists.
3. **Broader value** — Centered narrative island surrounded by work fragments.
4. **Social proof** — Paper quote with logo selectors and a project action.
5. **Closing call** — Yellow invitation, footer links and enormous name.

**Transfer:** Default landing-page approach: vary the number of chapters while preserving the editorial scale and decisive ending.

### Explain a method and why it matters

1. **Thesis** — Mixed-family statement with floating colored proof cards.
2. **Causal explanation** — A vertical word chain resolves into a short statement and action.
3. **Credibility** — Monochrome logo matrix on paper.
4. **Problem recognition** — A list of familiar situations paired with an example.
5. **Method demonstration** — Stacked paper explanation layers, followed by further reading.
6. **Closing call** — Testimonial, yellow invitation and shared monumental footer.

**Transfer:** Use the immersive effects only when a causal argument earns the scroll space.

### Make a company feel human and capable

1. **Human introduction** — Yellow scene with a centered statement and peripheral candid photographs.
2. **Character** — Small centered passages within the photo constellation.
3. **Trust** — Paper split composition with a corkboard photograph, image ribbons and partner-oriented copy.
4. **Quantified proof** — Large unboxed outcome numbers beside an editorial paragraph.
5. **Closing call** — Yellow invitation and monumental footer.

**Transfer:** Center genuine people and verified outcomes rather than generic company-value cards.

### Let examples prove breadth

1. **Introduction** — Compact centered serif editorial statement on paper.
2. **Visual demonstration** — Wide opening film followed by staggered two-column tiles.
3. **Value reminder** — Dark oversized question interrupts the collection.
4. **Evidence** — More varied project tiles with a floating category filter.
5. **Closing call** — Yellow invitation and shared footer.

**Transfer:** Apply to use cases, customer stories or a visual product catalogue without turning it into a uniform commerce grid.

### Show a single transformation in depth

1. **Visual hook** — Large film before the paper project introduction and taxonomy.
2. **Context and insight** — Narrow editorial passages alternate with wide graphic scenes.
3. **Demonstration** — Typography, system mosaics, device scenes, applications and carousel views.
4. **Validation** — Substantial client quotes on contrasting grounds.
5. **Next step** — Dark invitation, two related visual stories and shared footer.

**Transfer:** Build a visual case argument around the new product's actual problem, decisions and results.

## Writing

Warm, assured and emotionally literate without becoming sentimental. Commercial outcomes are expressed through human experience and concrete design decisions rather than hard-sell superlatives.

**Do not copy:** Do not reuse the Fiasco name or wordmark, client identities, project artwork, proprietary slogans, testimonials, statistics or business claims. Source examples illustrate rhythm only; new claims and proof must belong to the new product.

- **Addressing the reader:** Use we for the maker and you or your for the reader. Invite a conversation rather than addressing an anonymous market segment.
- **Rhythm:** Full-sentence opening statements, short punchy propositions and compact explanatory paragraphs. Sentence case throughout; paired clauses and em dashes create movement, with contractions keeping the voice approachable.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Connect what the product does to a human effect and a consequential outcome. | About 12–20 words | “Blending brand and digital we turn emotional connection into meaningful growth.” |
| Chapter proposition | Two short active clauses, or a compact relational claim. | 2–8 words | “Find the feeling. Build the brand.”<br>“Together is better” |
| Supporting explanation | Define the subject in ordinary language, explain its human significance, then describe the offer. | About 35–65 words | “Brand is how your business shows up in the world. It shapes perception, builds trust, and gives people a reason to believe in what you do. We define the strategy, narrative and identity that bring your brand into focus.” |
| Recognition heading | A short conversational question that names a reader's concern indirectly. | 2–5 words | “Sound familiar?” |
| Action | Direct conversational verb phrase. | 2–4 words | “Get in touch”<br>“Talk to us”<br>“Find out how” |

**Words and phrasing to use:** feeling; clarity; connection; together; built for; turn into; move forward; what matters

**Avoid:** revolutionary; best-in-class; 10x everything; unlock synergies; frictionless ecosystem; act now

**Rules:**

- Lead with what changes for people, then explain the mechanism.
- Make lists concrete and spare; they should read as capabilities, not keyword stuffing.
- Keep proof specific and attributable, with a person or outcome behind it.
- A closing line should invite the next move, not summarize the whole page.

## Do's and Don'ts

### Do

- Keep the default opening dark, with 80px regular sans and inline italic serif emphasis.
- Use 32px desktop gutters and leave 160px pauses between substantial chapters.
- Keep primary pills 44px high and pair their fill with the section ground.
- Reserve 40px corners and broad shadows for full-width overlapping sheets.
- Use 34px serif text for quotes instead of making every heading sans.
- Show media in varied scales and ratios while keeping editorial text measures narrow.
- End with compact link columns and a near-full-width solid word sculpture.

### Don't

- Do not replace the warm olive neutrals with pure black and icy gray.
- Do not make display headings 700 weight; the visual contrast depends on regular sans against italic serif.
- Do not turn the 20px italic labels into tiny uppercase, widely tracked technical eyebrows.
- Do not apply the 40px layer radius to every project image or editorial tile.
- Do not make yellow the permanent canvas for an ordinary product page; the extended yellow treatment belongs to culture storytelling.
- Do not surround every portfolio example with a filled panel and drop shadow.
- Do not treat the 12px category pills as primary conversion controls.
- Do not reduce the final name to another small footer logo.

## Motion and responsive

### Motion

**Observed:**

- Pill backgrounds declare a 0.2s ease-in-out transition.
- Media panels declare transform and visibility transitions of 0.35s linear; the chapter media stage is sticky.
- Article link underlines declare background-size 0.1s ease-in-out.
- Paper sheets overlap by 80px; the closing yellow sheet and footer use sticky positioning to reveal layers.
- The vertical word argument and staggered proof cards change emphasis and position through scrolling.

**Transfer:**

- Preserve the feeling of a held media stage while the adjacent editorial story advances.
- Let full-width layers reveal the closing invitation rather than animating many small cards independently.
- Keep moving fragments outside the central narrative reading area.

**Unknown:**

- Scroll progress mappings, JavaScript easing and full animation durations are not specified.

### Responsive

**Observed:**

- The main page is capped at 1440px. Declared horizontal padding starts at 16px and resolves to 32px in the desktop compositions.
- The immersive statement uses 6vw; proof numerals use clamp(56px, 7vw, 88px), and timeline words use clamp(42px, 5.6vw, 80px).
- Styles include width breakpoints around 600px, 768px, 1024px and 1240px; a Menu label exists in navigation.

**Transfer:**

- On narrow layouts, keep the mixed-family statement intact but wrap for meaning rather than preserving desktop line breaks.
- Stack each capability's media with its corresponding copy and keep that relationship clearer than the sticky effect.
- Move peripheral imagery out of the reading column and fit the final word sculpture to the available width.

**Unknown:**

- Exact mobile composition, menu behavior and breakpoint-to-component mappings are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
