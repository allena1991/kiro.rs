# Destroy Today — small type, expansive stages

## Overview

A personal, matter-of-fact introduction gives way to unusually expansive, art-directed demonstrations. Native system sans-serif and ordinary underlined links keep the voice approachable while white, charcoal, bright blue, red and forest-green chapters give each piece its own world. The sparse text and large product cutouts, vector scenes and candid photography suit craft-led products, independent studios and portfolios with a story behind the work.

### Essentials

- The headline behaves like an introduction, not a billboard: 24px system sans at 400 with 1.4 line height, with only the opening name at 600; body copy stays 16px/1.5.
- A narrow letter sits above a full-width stage: the opening copy is 666px wide inside a 730px shell with 32px side padding, while the first illustration begins only 250px down the page.
- Actions retain the look of the early web: 16px underlined blue text, no filled conversion buttons, no pills; the lone compact solid control is a square 40px identity tab.
- Color belongs to whole chapters rather than decorative cards: white bookends frame broad charcoal and saturated blue, red and green fields; colored or dark chapters occupy about half the long page.
- Small narration accompanies oversized, unboxed visual demonstrations: use a 333px or 666px copy column with artwork extending beyond it, including an exploded or layered product scene. For an intangible product, separate meaningful interface layers instead of using generic ornaments.
- The sign-off is a full-screen exhale: a 900px white closing stage centers a small left-aligned 24px question and two 16px paragraphs with embedded links rather than a conventional multi-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Web blue | `#0000ff` | `--color-link` | link, action, background | Default underlined links and the square identity tab; not the ordinary page background. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Illustration blue | `#3498db` | `--color-sky` | background | Full-width illustrated benefit stage. |
| Signal red | `#ff0000` | `--color-red` | background | A high-impact full-width editorial media chapter. |
| Studio green | `#00361c` | `--color-forest` | background | Photographic collage backing. |
| Pale rose | `#e9d5d5` | `--color-rose` | text, link | Gentle contrasting links on forest green. |
| Violet link | `#555abf` | `--color-violet-link` | link | Links within the violet illustrated project stage. |
| Burnt orange link | `#eb5e28` | `--color-orange-link` | link | Links and identity-tab accent within the warm-charcoal product stage. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Default page canvas and inverse text on colored stages. |
| Light edge | `#dcdcdc` | `--color-rule` | border | A single fine division where an image-backed stage meets the white canvas. |
| Warm inverse text | `#d8d4cf` | `--color-soft-ink` | text, link | Softer copy and links on near-black. |
| Warm charcoal | `#2c2b28` | `--color-charcoal` | background | Immersive physical-product demonstrations. |
| Body ink | `#222222` | `--color-ink` | text | All ordinary headings, descriptions and dates on white. |
| Green black | `#121311` | `--color-near-black` | background | Dark editorial media chapters. |

## Typography

- **-apple-system** — All live headings, prose, navigation, links and dates. Unembellished native system sans-serif with regular prose and a semibold introductory name. Font stack: "-apple-system", system-ui, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| intro-heading | -apple-system | 400 | 24px | 1.4 | normal | Opening identification sentence and closing question. |
| intro-emphasis | -apple-system | 600 | 24px | 1.4 | normal | The name or product identity embedded at the start of the opening sentence. |
| body | -apple-system | 400 | 16px | 1.5 | normal | Narration, project actions, article titles and dates. Links share the paragraph recipe. |

**Notes:**

- Hierarchy is deliberately shallow: the opening and closing headings are only 1.5 times body size. Do not turn project descriptions into giant headlines.
- Section identities are often logos or drawn wordmarks, not an additional live-text type family. Use a compact original product mark or the introductory heading recipe for new chapter labels.
- Keep normal tracking at both sizes; visual drama comes from composition and artwork rather than compressed typography.

## Layout

**Density:** Airy at section scale and comfortable within prose: compact reading blocks float inside stages roughly a screen tall or longer.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Horizontal navigation link padding. |
| 16px | Paragraph separation and navigation vertical hit-area padding. |
| 32px | Outer copy gutters and split-composition separation. |
| 64px | Four margin units: copy-to-media separation and opening block bottom space. |
| 135px | Top and bottom padding for editorial media chapters. |
| 225px | Top and bottom breathing room for expansive white and photographic chapters. |
| 297px | Deep vertical padding for the long exploded-product chapter. |

### Containers and grids

- **reading-shell**: max width 730px · side padding 32px. Centered shell yielding a 666px reading measure. Header, introduction and sign-off share its alignment.
- **copy-measure**: max width 666px. Full narrative blocks and compact section introductions.
- **split-stage**: max width 666px · 2 columns · gap 32px. A 333px copy area paired with a tall visual. Let visual widths and overlap exceed the underlying columns instead of forcing equal tiles.
- **wide-media**: max width 1080px. Centered landscape presentation underneath a narrow narrative introduction; 64px separates the two.

## Corner radius

| Element | Radius |
| --- | --- |
| page-panels | 0px |
| identity-tab | 0px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| collage-photograph | `rgba(0, 0, 0, 0.5) 0px 22.9px 45.7px -11.4px` | The middle photograph within a layered collage; the other two images use shallower and deeper shadows to separate their planes. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading surface and both bookends.

**CSS:** `background: #ffffff; color: #222222`

**Observed:** No page texture, card framing or rounded container treatment.

**Transfer:** Make white space the organizing material, not a collection of tinted panels.

#### Warm product stage · level 0

**Use:** A long-form dimensional product demonstration.

**CSS:** `background: #2c2b28; color: #ffffff; padding: 297px 32px`

**Observed:** A narrow exploded object stands beside sticky narration; the field continues far beyond a single screen.

**Transfer:** Choose a materially convincing object or interface-layer stack whose parts reward sustained viewing.

#### Dark media stage · level 0

**Use:** Editorial presentation with landscape media.

**CSS:** `background: #121311; color: #d8d4cf; padding: 135px 0px`

**Observed:** Narrow copy above a wider media area with 64px of separation.

**Transfer:** Use a real poster frame or playable film to carry the visual weight.

#### Red media stage · level 0

**Use:** A contrasting editorial interlude.

**CSS:** `background: #ff0000; color: #ffffff; padding: 135px 0px`

**Observed:** Flat saturated red edge to edge, with ordinary prose rather than a matching oversized red headline.

**Transfer:** Reserve this intensity for one coherent chapter rather than scattering red UI accents.

#### Blue illustrated stage · level 0

**Use:** A benefit or product story supported by an atmospheric vector scene.

**CSS:** `background: #3498db; color: #ffffff; overflow: hidden`

**Observed:** The scene fills a 900px stage, with narration above layered landscape silhouettes.

**Transfer:** Keep the upper area clear for text and concentrate layered forms toward the bottom.

#### Green collage stage · level 0

**Use:** Human or environmental proof.

**CSS:** `background: #00361c; color: #ffffff; padding: 225px 0px; overflow: hidden`

**Observed:** Photographs overlap freely around the reading column.

**Transfer:** Let genuine photographs bring warm, varied color against the single dark field.

## Components

### Sticky header

**Use:** Persistent orientation without a full-width toolbar.

**CSS:** `display: flex; position: sticky; top: 0px; justify-content: space-between; align-items: flex-end; max-width: 730px; padding-left: 32px; padding-right: 32px; margin-bottom: 32px; z-index: 10`

**Observed:** A square identity tab sits at the left reading edge and a short horizontal list of links at the right. The tab persists through the story; the full navigation is visible at the white bookends.

**Transfer:** Keep destinations few and literal; do not add a full-width opaque bar.

### Identity tab

**Use:** Small persistent brand anchor.

**CSS:** `width: 40px; height: 40px; background-color: #0000ff; color: #ffffff; border-radius: 0px; transition: background-color .35s cubic-bezier(.37, 0, .63, 1)`

**Observed:** A white two-letter monogram is centered in the square. The tab changes color to harmonize with individual stages.

**Transfer:** Use an original short monogram or simple silhouette; retain the compact top-edge tab.

### Navigation link

**Use:** Header destinations.

**CSS:** `color: #0000ff; font-size: 16px; font-weight: 400; line-height: normal; text-decoration: underline; padding: 16px 8px; transition: color .35s cubic-bezier(.37, 0, .63, 1)`

**Text style:** `body` — -apple-system 400 · 16px/1.5

**Observed:** Plain text links form one continuous row, with padded hit areas but no enclosing button shape.

### Text action

**Use:** Inline references and standalone project or conversion links.

**CSS:** `color: #0000ff; font-size: 16px; font-weight: 400; line-height: 24px; text-decoration: underline`

**Text style:** `body` — -apple-system 400 · 16px/1.5

**Observed:** Actions occur within prose or in their own paragraph, without arrows. Contextual link colors include violet on the pale illustrated stage, orange on charcoal, white on blue and red, and pale rose on green.

**Transfer:** A primary conversion can remain an ordinary underlined link; label the destination or action explicitly.

### Narrative paragraph

**Use:** Short explanatory blocks around large visual demonstrations.

**CSS:** `font-size: 16px; font-weight: 400; line-height: 24px; max-width: 666px; margin-top: 16px`

**Text style:** `body` — -apple-system 400 · 16px/1.5

**Observed:** Full-width narration uses the reading measure; descriptions beside objects often narrow to half that width. Links are embedded naturally in complete sentences.

### Dated article entry

**Use:** A compact library of process stories or practical resources.

**CSS:** `font-size: 16px; line-height: 24px; font-weight: 400; margin-top: 16px; margin-bottom: 16px; max-width: 666px`

**Text style:** `body` — -apple-system 400 · 16px/1.5

**Observed:** An underlined title comes first, followed immediately by an unlinked dark date on a new line. The actual list sits in a 333px column and has no bullets, rules, cards or thumbnail per item.

**Transfer:** Use useful descriptive titles and real dates; keep metadata at body size rather than turning it into an eyebrow.

### Floating photograph

**Use:** Naturalistic proof within the collage stage.

**CSS:** `box-shadow: rgba(0, 0, 0, 0.5) 0px 22.9px 45.7px -11.4px; margin-top: 64px; margin-left: -64px; margin-right: -64px`

**Observed:** A landscape photograph extends beyond its underlying column and overlaps neighboring images. It is unframed and square-cornered; a larger portrait and smaller landscape occupy different depth planes.

**Transfer:** Use original environment, detail and people photographs with different proportions; keep their natural color.

### Closing copy block

**Use:** The final low-pressure invitation.

**CSS:** `margin: 64px 32px; color: #222222`

**Text style:** `body` — -apple-system 400 · 16px/1.5

**Observed:** A small introductory-heading question precedes two short paragraphs. Each paragraph begins with a blue Text action and continues with context; the entire block is vertically centered in a white screen.

**Transfer:** Offer one deeper-reading path and one direct next step without duplicating the navigation as footer columns.

## Imagery and graphics

### Architectural vector stage

**Use:** The first large demonstration, immediately beneath the introduction.

**Observed:** A pale cool field supports staggered, sloping blue and violet rectangular planes rising across the right and lower edges. Thin warm-colored paths climb in rounded steps and end in arrowheads; small narration remains clear at the left. The artwork is full bleed, not a card.

**Transfer:** Make a product-relevant diagram feel spatial and oversized. A minimum version uses layered interface planes and two routing paths, preserving a large clear text zone.

**Build:** Use a full-width SVG with a 1440 by 889 viewBox. Stack long parallelograms sloping upward toward the right, alternating dark violet and lighter blue faces with subtle shaded edges. Draw two unfilled paths with 2px to 3px strokes in warm yellow and orange at roughly 0.7 opacity; round their ninety-degree turns and add open arrowheads. Keep the left half largely pale and empty around the 333px narrative column.

### Exploded product assembly

**Use:** A distinctive demonstration device within the visual story.

**Observed:** On white, floating grayscale bedding layers are separated vertically above a mattress. A later charcoal chapter stretches a slim dark stylus into a long vertical sequence of detached housing, circuitry and tip, with subtle photographic lighting and tiny gold details. The latter sits beside compact narration.

**Transfer:** Include an exploded or layered demonstration with meaningful parts. For software, separate input, processing and output screens; for services, separate actual artifacts. The minimum is three clean, well-aligned layers, not stock technology particles.

**Build:** Prepare transparent cutouts or SVG layers of the new product. Align their shared center axis, introduce substantial vertical separation, and retain consistent scale and directional lighting. Use a white or warm-charcoal full-width backing; place the explanation beside the assembly rather than labeling every part.

### Illustrated atmosphere

**Use:** An expansive colored benefit chapter.

**Observed:** A flat blue sky contains layered mountain silhouettes, small clouds, dots and a pale crescent moon. The cool blue layers become darker toward the foreground and extend beyond both edges. Text occupies the clear upper portion.

**Transfer:** Create a restrained landscape or similarly layered metaphor that supports the desired feeling. Keep it flat, tonal and subordinate to the small narrative, not a glossy three-dimensional fantasy scene.

**Build:** Use an SVG sized to the stage. Fill the base with illustration blue, then add two broad irregular polygon ridgelines along the bottom in darker blue at different opacities. Add sparse tiny circles and small cloud silhouettes in translucent white. Form a crescent with a white circle and an offset circle masked out. Clip the scene at the stage edges and reserve the upper third for narration.

### Device demonstration

**Use:** A tall product-in-use visual beside a resource list.

**Observed:** A 300px by 628px phone demonstration sits on white beside a 333px text list. A bright cyan device edge frames a black face and a light interface; the phone is imagery, not a page-wide UI theme.

**Transfer:** Use a current device or a clean interface recording relevant to the new product, with the same tall silhouette and unboxed placement. Keep internal interface colors local to the demonstration.

### Environmental photo collage

**Use:** A humanizing proof chapter.

**Observed:** Three naturally lit photographs show a street-facing exterior, a warm interior with plants and wood, and people in the space. A 500px square portrait dominates the right, a 461px by 308px interior overlaps below the copy, and a 333px by 229px exterior projects out to the left. Broad dark shadows separate them from forest green.

**Transfer:** Use people, workspace and detail images from the new product's real world. Preserve different aspect ratios and loose overlap; the minimum is one strong people image paired with one environmental detail.

### Icons

**Observed:** Iconography is sparse and identity-led: a filled white monogram in a 40px square and project wordmarks or symbols. Actions do not acquire decorative arrow icons.

**Transfer:** Use a compact original identity mark and meaningful project symbols only; let underlines communicate interactivity.

## Section recipes

How recurring sections are built.

### First screen: Letter above an oversized stage

**Observed:** A white Sticky header anchors the 666px reading alignment, with its 40px Identity tab at the top edge and ordinary links opposite. Beneath it, a single 24px introductory sentence starts with semibold identity and continues in regular weight. A 16px paragraph follows after 16px; 64px of space finishes the copy block. The full-width Architectural vector stage begins at 250px and occupies the rest of the first 900px screen. Back to front: pale artwork field, layered planes and climbing paths, then a small left-aligned project identity and 333px narrative with embedded actions. The introduction, navigation, support paragraph and much of the first visual are above the fold; the illustrated stage continues below. There is no hero button row.

**Transfer:** Introduce the new product in one factual sentence, then demonstrate its craft immediately at immersive scale. Without specialist art, build the layered vector or interface-plane fallback with a clear text zone. Editorial or secondary pages can open with the same narrow introductory block and move directly into their main artifact.

**Avoid:** Do not substitute a giant centered slogan, twin pill buttons or a boxed dashboard beneath a full-height empty hero.

**Text style:** `intro-heading` — -apple-system 400 · 24px/1.4

### Identity plus short narrative

**Observed:** Project chapter headings are compact wordmarks or marks followed by Narrative paragraph and a Text action. The text aligns left within 666px or 333px, with 16px paragraph rhythm. Large imagery supplies the section's main hierarchy.

**Transfer:** Use a restrained product or capability label with a concise account of what changed and why. Do not require a separate oversized heading for every chapter.

**Text style:** `body` — -apple-system 400 · 16px/1.5

### Floating product on white

**Observed:** A white chapter uses 225px vertical breathing room, a narrow narrative introduction and an exploded product assembly below. Photographic cutouts are unboxed and can extend wider than the text.

**Transfer:** Reveal the construction or useful layers of the new product on the simplest possible field.

### Long material demonstration

**Observed:** Warm product stage extends for 2373px, with a slim 95px-wide assembly beside a roughly 333px sticky copy block. The separated object parts scroll past while the explanation remains the local anchor.

**Transfer:** Use a longer stage only when successive views genuinely reveal more of the object or system.

### Editorial media chapter

**Observed:** Dark media stage and Red media stage share a narrow logo-plus-prose introduction, then a 64px gap to 1080px-wide landscape media. Vertical padding is 135px; text stays small despite the dramatic backing.

**Transfer:** Use one coherent film, demonstration or narrated explanation and supply a meaningful poster frame.

### Immersive illustrated benefit

**Observed:** Blue illustrated stage is 900px tall. Copy begins after 225px of top breathing room, followed by a white underlined action. Illustrated atmosphere fills the lower field and bleeds out at the sides.

**Transfer:** Translate an intangible outcome into a layered, tonal scene while keeping the explanation in the standard reading column.

### Resources beside a tall demonstration

**Observed:** On white, a 300px by 628px Device demonstration sits left of a 333px narrative and Dated article entry list. The centered pair has 225px vertical padding and 32px separation.

**Transfer:** Pair a genuine use example with a short selection of detailed supporting material, not a card grid.

### Photographic world

**Observed:** Green collage stage pairs small left narration with Environmental photo collage. The images escape the 666px reading alignment, overlap at different depths and leave the text unobscured.

**Transfer:** Let the real environment provide proof and warmth instead of another abstract illustration.

### Full-screen sign-off

**Observed:** The final white stage is 900px tall. Closing copy block sits vertically centered at the same reading alignment as the opening. A 24px question and two 16px paragraphs occupy only a small part of the field, with 16px text gaps. Header links reappear above; there is no footer sitemap.

**Transfer:** Close with an unhurried, conversational next step and a deeper-reading option.

**Text style:** `intro-heading` — -apple-system 400 · 24px/1.4

## Page flow

**Storyline:** plain introduction → immersive demonstrations → process and editorial depth → human context → conversational next step

### A craft-led landing page that earns trust through work and process rather than a dense feature taxonomy

1. **Introduction** — A compact identity sentence and personal statement above the first visual stage.
2. **Product demonstration** — Several large, separately art-directed chapters pair short narration with layered vectors, physical cutouts and interface imagery.
3. **Depth and credibility** — Long material demonstration and landscape editorial media give the work a sense of process.
4. **Benefit** — A saturated illustrated stage connects a product to the feeling it enables.
5. **Further reading** — A tall demonstration accompanies a plain list of dated process stories.
6. **Human proof** — An editorial interlude and warm photographic collage introduce the people and context behind the work.
7. **Closing call** — A whole white screen makes room for a small question and two linked paragraphs.

**Transfer:** Choose the demonstrations that best explain the new product; preserve the contrast between modest narration and immersive artwork rather than reproducing a fixed number or sequence of chapters.

## Writing

Personal, candid and quietly proud of the work. Credibility comes from describing specific contributions and motivations, with occasional warmth and self-aware understatement rather than marketing superlatives.

**Do not copy:** Do not reuse the author's name, monogram, client logos, product artwork, biographical facts, project credits, dates or personal claims. The excerpts illustrate voice; write original copy for the new product.

- **Addressing the reader:** First-person singular describes the maker's work; the reader is addressed directly in the final invitation. A team-led product can use an equally accountable first-person plural.
- **Rhythm:** Complete conversational sentences, usually one or two per paragraph. Short literal links punctuate the narrative; compact introductory and closing lines replace slogan-like display copy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Introduction | Name followed by a plain statement of role and context. | One short sentence | “Jonnie Hallman is an independent design engineer in New York.” |
| Narrative support | Describe the work and the principles behind it using concrete verbs. | One or two sentences | “My work focuses on crafting thoughtful, intuitive, and delightful interactions for the web, with a devotion to process, transparency, and sharing what I learn.” |
| Editorial aside | A brief personal comment breaks up factual explanation. | One sentence | “No spoilers, but this is a real rollercoaster ride of a talk.” |
| Action | Verb plus an explicit destination, often embedded in prose. | Three to seven words | “Read about the Pencil page”<br>“Send me an email” |
| Closing heading | A casual statement followed by a direct question. | Four to six words | “That’s all. What now?” |

**Words and phrasing to use:** built; worked with; process; sharing; thoughtful; behind-the-scenes; good fit

**Avoid:** revolutionary; unlock limitless potential; best-in-class; 10x; hurry; dominate

**Rules:**

- Explain what you actually made or improved before evaluating its quality.
- Link the specific project, artifact or next step instead of writing repeated vague calls to action.
- Keep warmth in personal motivation and asides, not in excessive punctuation.
- Make the last invitation conditional on fit rather than manufacturing urgency.

## Do's and Don'ts

### Do

- Keep live prose at 16px/24px across light and colored sections.
- Use 24px/1.4 for the introductory sentence and closing question.
- Align the header and bookends to the same 666px reading measure with 32px gutters.
- Keep the 40px identity tab square and visually separate from the navigation.
- Give meaningful demonstrations the full viewport width while narrowing accompanying text to 333px when needed.
- Maintain 16px paragraph rhythm even inside stages with 225px vertical breathing room.
- Use real differing photo proportions and deep soft shadows for the green collage.
- Preserve a full-screen white pause for the final linked invitation.

### Don't

- Do not add pill-shaped conversion controls to a system built around underlined text links.
- Do not apply the 600 heading weight to every heading; the opening identity is the emphasis.
- Do not replace the 16px dates with tiny uppercase metadata labels.
- Do not turn every project into an equal bordered card; the stages need different silhouettes.
- Do not spread the red and forest-green chapter colors across small badges throughout the white introduction.
- Do not add a decorative icon to every link; typography and underlines already do the work.
- Do not apply the collage's dark shadows to ordinary prose blocks or navigation.
- Do not finish with a dense multi-column sitemap that fills the deliberate white closing space.

## Motion and responsive

### Motion

**Observed:**

- Identity-tab background-color and header-link color have declared .35s cubic-bezier(.37, 0, .63, 1) transitions.
- The identity tab changes color between chapters; some project narration is sticky while neighboring visual parts move through the stage.
- Layered artwork and photographs have scroll-related depth; a tall device demonstration contains video.

**Transfer:**

- Use color changes to tie the persistent identity tab to the current visual chapter.
- Keep the narrative anchor stable while meaningful object layers or collage planes move relative to it; the static arrangement must still read as a finished composition.

**Unknown:**

- Exact scroll mappings, playback behavior and timing of the visual demonstrations are not established.
- Hover and focus-visible endpoint colors are not established.

### Responsive

**Observed:**

- The desktop reading measure is 666px, with 32px side gutters; visual stages occupy the full width.
- No width breakpoints are established.

**Transfer:**

- On narrow screens, retain the 16px body recipe and readable side gutters; stack the narrative and demonstration instead of shrinking the text.
- Preserve the exploded-layer axis and tonal silhouette of each stage. Recompose overlapping photographs so no text is covered.
- Allow the introductory identity sentence and closing question to wrap naturally instead of using a giant fluid heading.

**Unknown:**

- Mobile navigation, exact small-screen spacing and actual device-specific motion behavior are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
