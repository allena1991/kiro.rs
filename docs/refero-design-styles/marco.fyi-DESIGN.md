# marco.fyi — a desk of possibilities

## Overview

A light, personable portfolio language that feels like a desk covered in carefully arranged little software objects. Cool off-white tiles, black grotesk headings and soft gray prose make room for colorful interfaces, tilted phones and small tactile details. It suits product introductions and design-led software stories that prefer demonstrations and candid explanation to hard-selling spectacle.

### Essentials

- The first impression is a collection, not a billboard: a 672px square text tile sits beside a wide 328px-high demonstration and smaller objects, on a four-column grid with 16px gutters.
- Headlines speak at conversational volume: Graphik 31px/1.25, weight 500, -0.4px tracking; black nouns and an underlined destination interrupt a gray sentence.
- The page behaves like a tray of objects: #f7f7f9 tiles have 32px corners, 24px or 32px padding and clipped media; at least one demonstration is enlarged beyond its tile and one compact object is isolated with space around it.
- Color belongs to the things being shown: the canvas stays white and most tile area stays cool gray; saturation is concentrated in interface selections, tiny red markers and occasional miniature artifacts rather than full-page brand bands.
- Navigation floats like a system control: a centered 458×54px translucent white capsule, 56px radius, 16px backdrop blur, four 44px-high destinations and a pale active pill. Text actions repeat the capsule silhouette with a 2px faint outline.
- Small peripheral cues reward exploration: 14px captions sit above the collection, circular 36px diagonal-arrow links sit near tile corners, and a 7px red dot marks a navigation destination. If finished product imagery is unavailable, use a legible working interface fragment and a simple tactile symbol instead of stock illustration.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| New-work red | `#ff4141` | `--color-signal` | accent | Tiny navigation dot and footnote asterisk; not a primary button fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, miniature interface sheets and reversed text. |
| Cool porcelain | `#f7f7f9` | `--color-tile` | surface | The dominant tile backing; cooler than the white page. |
| Active pill | `#f2f2f2` | `--color-active` | surface | Selected navigation destination. |
| Translucent edge on white | `#e6e6e6` | `--color-rule` | border | Visible result of black at 10% on white for navigation and action edges. |
| Soft control edge | `#dedee0` | `--color-edge` | border | Circular project-link outlines. |
| Inactive gray | `#999999` | `--color-nav-muted` | text | Inactive navigation labels. |
| Sentence gray | `#949494` | `--color-muted` | text | Connecting words in the opening heading and exploration captions. |
| Warm gray prose | `#707070` | `--color-body` | text | Conversational introductory paragraphs. |
| Black ink | `#000000` | `--color-ink` | text, link | Headings, active navigation and primary labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalogs and case studies | Editorial secondary | `#747474` | `--color-case-muted` | text | Project descriptors and uppercase metadata labels. |
| color-customization case studies | Mint stage | `#cceede` | `--color-mint` | surface | Tall color-customization demonstration backing. |
| product demonstrations | Selection wash | `#eff0ff` | `--color-ui-selection` | surface | Selected rows inside software demonstrations. |
| product demonstrations | Selection indigo | `#6366f1` | `--color-ui-outline` | border, accent | Thick rounded focus cursor inside software demonstrations. |
| reward-interface demonstrations | Reward red | `#e92f48` | `--color-artifact-red` | surface | Small reward-card artifact and phone interface, surrounded by neutral staging. |

## Typography

- **Graphik** — All page-level headings, prose, captions, navigation and buttons. Clear geometric grotesk with round counters, compact headings and unshowy regular prose. If unavailable, use **Inter**. Use weights 400 and 500; retain compact heading tracking. Font stack: "Graphik", "Inter", Arial, sans-serif.
- **Chirp** (only for social-post tiles) — Post body within a recreated social card. Casual platform sans with a softer text rhythm. If unavailable, use **Roboto**. Font stack: "Chirp", "Roboto", Arial, sans-serif.
- **Sohne** (only for cinematic concept introductions) — White display text over an immersive desktop scene. Broad, direct neo-grotesk with medium weight. If unavailable, use **Inter**. Font stack: "Sohne", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Graphik | 500 | 31px | 1.25 | -0.013em | Opening sentence, with black emphasized nouns, gray connecting text and an underlined destination. |
| intro-prose | Graphik | 400 | 20px | 1.5 | 0.005em | Short reflective paragraphs inside the large opening tile. |
| navigation | Graphik | 500 | 16px | 1.25 | normal | Floating capsule destinations. |
| button | Graphik | 500 | 16px | 1.375 | normal | Outlined text actions. |
| caption | Graphik | 400 | 14px | 1 | 0.007em | Exploration cue and small footnote. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| cinematic concept introductions | cinematic-display | Sohne | 500 | 120px | 1 | normal | Centered sentence on a vivid desktop scene. |
| case studies | case-title | Graphik | 500 | 40px | 1 | -0.02em | Editorial project title. |
| catalog pages | catalog-heading | Graphik | 500 | 32px | 1 | -0.025em | Heading at the top of a project tile. |
| long-form product case studies | feature-heading | Graphik | 500 | 28px | 1.5 | normal | Capability chapters, sometimes preceded by a small colored dot. |
| long-form product case studies | chapter-heading | Graphik | 500 | 28px | 1.8 | -0.007em | Intro and outro editorial chapter boundaries. |
| social-post tiles | social-post | Chirp | 400 | 24px | 1.35 | normal | Post excerpt, with inline platform links. |
| catalogs and case studies | descriptor | Graphik | 400 | 20px | 1 | normal | One-line secondary explanation below a project name. |
| long-form product case studies | subheading | Graphik | 500 | 18px | 2 | normal | Smaller explanatory headings inside a capability chapter. |
| case studies | body | Graphik | 400 | 16px | 2 | normal | Explanatory case-study paragraphs. |
| case studies | metadata-value | Graphik | 400 | 16px | 1.375 | normal | Compact details under metadata labels. |
| case studies | metadata-label | Graphik | 500 | 12px | 1 | normal, uppercase | Role, team, tools, timeline and context labels. |

**Notes:**

- Use the conversational display as the default landing-page headline, not the cinematic scale.
- Large page headings stop at weight 500. Contrast is made with black versus gray, compact tracking and differing line lengths rather than heavy bold type.
- The introduction has 30px lines and separated statements; the case-study body is smaller but has 32px lines. Preserve those distinct reading rhythms.
- Keep interface typography inside demonstrations separate from page typography; a depicted product can have its own font without changing the marketing shell.

## Layout

**Density:** Airy outside the objects, dense inside the demonstrations; tight gutters join substantial tiles while small text groups retain room to breathe.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Caption-to-grid separation and small icon-to-label gaps. |
| 12px | Navigation vertical padding and paragraph separation in case studies. |
| 16px | Grid gutters and title-to-descriptor spacing. |
| 24px | Small tile padding and feature-heading-to-body separation. |
| 26px | Separation between reflective introductory statements. |
| 32px | Large tile padding and spacing between editorial blocks. |
| 40px | Metadata sidebar-to-narrative gap and navigation top offset. |
| 64px | Inset around enlarged interface demonstrations. |
| 120px | White breathing room below the final collection or article. |

### Containers and grids

- **collection-container**: max width 1400px · side padding 16px. Centered near-full-width tray. At 1440px the home grid begins 36px from each edge after the container and inner padding.
- **object-grid**: 4 columns · gap 16px. Mix 328px square cells, 672px square two-cell tiles, wide strips and tall phone stages. Read as a coherent mosaic rather than equal cards.
- **editorial-column** (only for case studies): max width 800px · side padding 16px. Centered long-form case-study text and demonstration stages.
- **case-introduction** (only for case studies): max width 800px · 2 columns · gap 40px. Narrow metadata sidebar beside a wider description and context column; sidebar occupies roughly a quarter of the width.
- **catalog-grid** (only for catalog pages): 2 columns · gap 16px. Two equal 672px square project tiles per desktop row, with the same visual shell as the mosaic.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | stage-tiles | 32px |
|  | navigation-and-text-actions | 56px |
|  | active-navigation | 230px |
|  | project-link | 100px |
| product demonstrations | miniature-interface-panels | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating-navigation | `rgba(0, 0, 0, 0.1) 0px 10px 10px -5px` | Shallow shadow under the translucent navigation capsule. |
| product demonstrations | interface-sheet | `rgba(0, 0, 0, 0.1) 0px 15px 10px -3px, rgba(0, 0, 0, 0.05) 0px 6px 4px -2px` | Lift a miniature interface above its neutral backing. |
| cinematic concept introductions | cinematic-screen | `rgba(0, 0, 0, 0.25) 0px 50px 25px -12px` | Deep grounding shadow under the immersive screen. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous white page around all objects.

**CSS:** `background: #ffffff`

#### Object tray · level 1

**Use:** Default backing for text and media tiles.

**CSS:** `background: #f7f7f9; border-radius: 32px; box-shadow: none; overflow: hidden`

**Observed:** Adjacent tiles share the same material even when their shapes and contents differ.

**Transfer:** Keep the shell neutral so media supplies the variation.

#### Floating glass · level 2

**Use:** Navigation surface.

**CSS:** `background: rgba(255, 255, 255, 0.8); border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 56px; backdrop-filter: blur(16px); box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 10px -5px`

**Observed:** The page remains visible through the capsule as it floats above content.

#### Interface sheet · level 2

**Only for:** product demonstrations

**Use:** White floating panel within a gray demonstration stage.

**CSS:** `background: rgba(255, 255, 255, 0.85); border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.1) 0px 15px 10px -3px, rgba(0, 0, 0, 0.05) 0px 6px 4px -2px`

**Observed:** Rows, icons and a colored selection occupy the panel; the shell alone is not the illustration.

#### Mint stage · level 1

**Only for:** color-customization case studies

**Use:** Tall scrolling interface specimen.

**CSS:** `background: #cceede; border-radius: 32px; padding: 28px; overflow: hidden`

**Transfer:** Confine a customization color to one specimen rather than recoloring the whole article.

## Components

### Floating navigation

**Use:** Persistent primary wayfinding.

**CSS:** `display: flex; width: 458px; height: 54px; padding: 4px; background: rgba(255, 255, 255, 0.8); border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 56px; backdrop-filter: blur(16px); box-shadow: rgba(0, 0, 0, 0.1) 0px 10px 10px -5px`

**Text style:** `navigation` — Graphik 500 · 16px/1.25

**Observed:** Four centered destinations in a sticky wrapper above the collection. A separate pale pill sits behind the active item; a tiny red dot precedes one destination.

**Transfer:** Use four short product-relevant destinations and keep the active state separate from the glass shell.

### Navigation item

**Use:** Single destination in the capsule.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 12px 24px; border-radius: 230px; color: #999999`

**Text style:** `navigation` — Graphik 500 · 16px/1.25

**Observed:** Active text becomes black over the pale active pill. The dot is a status cue, not part of every label.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

### Outline action

**Use:** Low-pressure external or supporting action.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 46px; padding: 10px 16px; border: 2px solid rgba(0, 0, 0, 0.1); border-radius: 56px; backdrop-filter: blur(16px); color: #000000`

**Text style:** `button` — Graphik 500 · 16px/1.375

**Observed:** Label and a small northeast arrow sit together in the center. A wider horizontal padding variant serves an article-level external destination.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

### Statement tile

**Use:** The human introduction inside the collection.

**CSS:** `background: #f7f7f9; border-radius: 32px; padding: 32px; max-width: 672px`

**Text style:** `display` — Graphik 500 · 31px/1.25 · tracking -0.013em

**Observed:** A mixed-gray sentence leads, followed by a hairline, separate reflective paragraphs and a tiny asterisk footnote near the bottom. The text remains left aligned.

**Transfer:** State what the product is trying to improve in a few plain sentences; keep each statement visually distinct.

### Project corner link

**Use:** Discoverable exit from a visual tile.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 36px; height: 36px; background: rgba(255, 255, 255, 0.5); border: 2px solid #dedee0; border-radius: 100px; backdrop-filter: blur(16px)`

**Observed:** A gray northeast arrow is centered in a frosted disc near the lower-left tile corner. Catalog tiles use a larger 64px disc near the upper-right heading area.

**Transfer:** Make the visual tile and its corner cue lead to the same destination; give icon-only links an accessible name.

### Exploration caption

**Use:** Small invitation above the mosaic.

**CSS:** `color: #949494; margin-left: 8px; font-size: 14px; line-height: 14px; letter-spacing: 0.1px`

**Text style:** `caption` — Graphik 400 · 14px/1 · tracking 0.007em

**Observed:** A small cursor icon precedes right-aligned text; the caption sits outside the tile field rather than becoming an eyebrow on every tile.

### Project tile

**Only for:** catalog pages

**Use:** Project or capability directory entry.

**CSS:** `position: relative; background: #f7f7f9; border-radius: 32px; padding: 32px; max-width: 672px; overflow: hidden`

**Text style:** `catalog-heading` — Graphik 500 · 32px/1 · tracking -0.025em

**Observed:** Title, single gray descriptor, thin separator, then a large product scene. The corner link occupies the heading's opposite corner. Media is centered or bleeds off the lower edge.

**Transfer:** Use one meaningful demonstration per entry rather than a stack of feature bullets.

### Social post tile

**Only for:** social-post tiles

**Use:** A short personal update or launch excerpt.

**CSS:** `background: #f7f7f9; border-radius: 32px; padding: 24px; overflow: hidden`

**Text style:** `social-post` — Chirp 400 · 24px/1.35

**Observed:** Avatar and identity at top left, a platform app icon at top right, a short informal post beneath and an Outline action pinned toward the bottom.

**Transfer:** Use a real attributed update or a clearly labeled product note, not an invented testimonial.

## Imagery and graphics

### Oversized software objects

**Use:** Main visual language throughout the mosaic and project tiles.

**Observed:** Crisp, mostly white interface fragments float on cool-gray backing. Phones have dark realistic edges, often tilt slightly and extend beyond the tile's bottom. Dock strips and large interface panels are deliberately clipped at the right or bottom edge; color remains in the displayed content.

**Transfer:** Show real product workflows at readable scale. If no polished interface exists, assemble a short legible list or document panel with meaningful content, a clear selected row and two or three recognizable controls.

**Build:** Use an overflow-hidden 32px-radius gray stage. Place a white 8–16px-radius panel with a soft two-layer shadow inside it; enlarge until one edge extends outside the stage. Pair it elsewhere with a much smaller centered artifact so every image does not share the same scale.

### Tactile shortcut sculpture

**Use:** A small symbolic object that punctuates the collection.

**Observed:** Two white raised keyboard keys bearing black symbols sit side by side in the center of a generously empty gray square. The key tops have rounded corners and a faint grounding shadow.

**Transfer:** Include an equivalent tactile symbol for the new product: a meaningful shortcut, a pair of controls or two simple tool-shaped objects. It should communicate an action, not merely decorate.

**Build:** Center two white rounded squares in a gray stage; use an 18px radius and a faint gray shadow below each. Put one bold black symbol on each key, with equal optical size and a modest gap. Preserve ample gray area on all sides.

### Pastel specimen fan

**Only for:** color-customization demonstrations

**Use:** Wide tile showing expressive variants of the same interface.

**Observed:** Repeated pale command panels overlap in a diagonal fan across soft rainbow ribbons. Their structure stays the same while mint, butter, pink and blue tints change. The backdrop is much less saturated than the panels' content.

**Transfer:** Repeat one small interface in a handful of gentle theme variations. Keep labels and hierarchy consistent so the visual argument is customization rather than complexity.

**Build:** Arrange five or six duplicate white panels in an overlapping horizontal row, rotating the group slightly counterclockwise. Tint each panel with a low-alpha theme wash. Behind them draw broad curved SVG ribbons at 0.2 opacity and clip all layers inside the gray rounded tile.

### Cinematic desktop scene

**Only for:** cinematic concept introductions

**Use:** An immersive alternative opening for a flagship concept story.

**Observed:** A nearly full-width rounded screen carries layered purple, magenta and pale pink wallpaper, large centered white sentences and a translucent dock. Later beats reduce the screen to a smaller centered object, surround it with contextual windows and bring the story back to text.

**Transfer:** Use a product-native environment as the stage for a short problem-and-resolution story. A static layered scene with actual recognizable product content is the minimum; do not reproduce a dock of empty blocks.

**Build:** Draw broad overlapping curved SVG shapes sweeping from dark violet at lower left through magenta toward pale pink at upper right. Clip to a 28–32px-radius screen, ground it with a deep downward shadow, and overlay a real product view plus centered white text. Match the broad color fields; exact wallpaper contours are not essential.

### Annotated mechanism diagram

**Only for:** explanatory case studies

**Use:** Clarify why a product response occurs.

**Observed:** A small interface view is surrounded by handwritten black notes, curved arrows and restrained coral connectors on a wide gray tray; a circular magnifier sits at the bottom right.

**Transfer:** Show one causal mechanism with short handwritten annotations pointing to actual controls or outcomes. Keep the diagram quieter and smaller than the main demonstrations.

### Icons

**Observed:** Northeast arrows and cursor cues are thin gray outline symbols; action icons are commonly 22px and corner-link glyphs 24px. Product demonstrations contain colorful app marks, avatars and badges with a different visual role.

**Transfer:** Use a consistent restrained outline set for page actions. Keep colored, filled app or object icons inside demonstrations rather than scattering them through prose; do not infer a precise stroke width.

## Section recipes

How recurring sections are built.

### First screen: Collection opening

**Observed:** White canvas, centered Floating navigation 40px below the top, then the exploration cue above a mosaic beginning at 164px. The large Statement tile occupies the left half, a wide dock demonstration the upper right, and a tall tilted-phone stage plus a smaller Social post tile fill the remaining right area. The 31px mixed-color heading sits at the top of the left tile; 20px gray statements occupy most of its depth, with the small footnote near its bottom. Back-to-front layers are white canvas, gray tile shells, white product objects with local shadows, then corner cues and the sticky glass navigation. Within 900px the complete statement, upper interface strip, social action and most of the phone are visible; the next media row only begins to appear. There is no detached centered hero or dominant filled conversion button.

**Transfer:** For a new product, use a conversational promise tile beside an enlarged real workflow strip, one device or interface view and one compact note. Include the tactile symbolic object somewhere in the collection even without finished media. Catalogs instead open directly on equal titled Project tiles; editorial studies open with metadata, while cinematic concept introductions can start with the immersive scene.

**Avoid:** Do not replace the asymmetrical opening with a huge central slogan above a single full-width mockup, and do not turn the introduction into a conventional sales bullet list.

**Text style:** `display` — Graphik 500 · 31px/1.25 · tracking -0.013em

### Object collection

**Observed:** Object tray tiles mix squares, double-height stages and wide strips with 16px gaps. Some contain tightly clipped interfaces while others center a small artifact in open gray space. Project corner links recur at the lower left.

**Transfer:** Vary object scale and tile spans around distinct product capabilities, maintaining a single shell material. Let the visual object explain the capability before adding extra prose.

### Collection ending

**Observed:** The mosaic ends on small visual marks and phone or website specimens, followed by 120px of white space. The catalog ends with its final pair of Project tiles and the same white release. The short campaign story ends with a specimen mosaic including a tall mint interface, a laptop image and a social excerpt. These endings have no separate footer columns or oversized closing conversion band.

**Transfer:** Finish collection-led pages with a resolved last row of useful demonstrations and a clean white release, keeping persistent navigation as the way out.

### Editorial introduction

**Only for:** case studies

**Observed:** An 800px centered column begins with a 40px title, a 20px secondary descriptor 16px below and a hairline. Below, a narrow metadata rail sits beside description and context paragraphs, with a 40px gap. Labels are uppercase 12px; values are 16px/22px, prose 16px/32px.

**Transfer:** Use for deep product rationale, process or launch context rather than imposing metadata on every landing page.

**Text style:** `case-title` — Graphik 500 · 40px/1 · tracking -0.02em

### Capability chapter

**Only for:** long-form product case studies

**Observed:** A 28px medium heading precedes prose by 24px. Paragraphs use 12px separation; a gray rounded demonstration stage follows. Stages are often 800px wide and 672px high with generous 64px insets. Some chapter headings use a small colored dot; smaller 18px headings introduce a sub-mechanism.

**Transfer:** Explain the problem, show the proposed behavior, then use a concise scenario to connect the mechanism to daily use. Alternate legible writing and object stages rather than embedding a whole application.

**Text style:** `feature-heading` — Graphik 500 · 28px/1.5

### Conversational outro

**Only for:** long-form product case studies

**Observed:** After a combined demonstration and reflective paragraph, a 28px chapter heading introduces a short invitation to share a response. The final paragraph retains the same 16px/32px body recipe; the page ends on white without a button stack.

**Transfer:** End a concept or essay with a modest statement of its limits and a genuine question about the reader's experience.

**Text style:** `chapter-heading` — Graphik 500 · 28px/1.8 · tracking -0.007em

## Page flow

**Storyline:** personal intent → tangible demonstrations → context and deeper mechanisms where needed → resolved objects or an invitation to respond

### Introduce a maker or product through a browsable object collection

1. **Promise** — A conversational statement tile shares the first screen with working product fragments.
2. **Product demonstration** — A mosaic mixes large interfaces, tilted devices, tiny artifacts and a tactile symbolic pair.
3. **Human connection** — A compact informal post and outlined reading action are woven into the objects.
4. **Closing proof** — A final group of small marks and device specimens resolves into white space.

**Transfer:** Let the reader discover the product through multiple scales of object, not a rigid conversion funnel.

### Present a short expressive product campaign with rationale

1. **Context** — Centered title and metadata introduce the work and its question.
2. **Rationale** — Description, context and italic reflective passages explain the design stance.
3. **Action** — An outlined external destination bridges writing and specimens.
4. **Closing demonstration** — An irregular mosaic combines a launch post, colored interface fan, image tile, laptop and tall mint specimen.

**Transfer:** Pair one design question with concrete variations showing how the answer behaves.

### Explain a speculative product through an immersive introduction and detailed mechanisms

1. **Promise** — A vivid rounded desktop environment carries large simple statements.
2. **Problem framing** — The screen shrinks into an object amid scattered windows before a contrasting resolution.
3. **Context** — An editorial title, metadata and introduction establish the proposal's limits.
4. **Capability chapters** — Repeated prose-and-stage sections explain navigation, related information and contextual assistance.
5. **Mechanism explanation** — A handwritten annotated diagram makes a specific rule visible.
6. **Synthesis** — A combined view reunites the components and a short paragraph reflects on the benefit.
7. **Closing invitation** — A plain outro paragraph asks the reader for their own perspective.

**Transfer:** Reserve the immersive treatment for a genuine concept narrative; preserve the editorial column and specific behavior examples in the longer explanation.

### Provide a visually rich directory of projects

1. **Product overview** — Equal square tiles open directly with title, descriptor and corner arrow.
2. **Breadth of proof** — Each row pairs two different product scenes while maintaining identical gray shells.
3. **Closing proof** — The last row shows complete website specimens and releases into white space, without an extra sales footer.

**Transfer:** Keep directory navigation simple and make the product scene, not a category badge, the primary differentiator.

## Writing

Candid, reflective and curious. It sounds like a designer thinking in public: plain assertions, everyday frustrations and concrete proposals rather than polished superlatives.

**Do not copy:** Do not reuse the maker's name, project names, social identities, proprietary marks, quoted passages, client relationships, project outcomes or interface reward numbers as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use first-person singular for a maker's point of view; use we for shared problems and you for concrete product scenarios. Explain the product by name rather than giving it a grand corporate persona.
- **Rhythm:** Short conversational opening statements build through repetition. Descriptors are one line; long-form sections allow fuller explanatory paragraphs and rhetorical questions, with occasional italic thought experiments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | A person or product is doing one concrete thing; keep the connecting language informal. | 3–7 words | “Marco is building Turf.” |
| Reflective support | Repeat a simple sentence stem, then vary the thought. | 4–25 words | “i think there are too many things.”<br>“i think there should be fewer, but better things .” |
| Project descriptor | Name what the product is and the human benefit in one line. | 6–12 words | “A context-aware OS for a more personal computer” |
| Section heading | Use a direct capability name or a small memorable analogy. | 1–9 words | “Live Previews”<br>“The Waiting Room” |
| Action | Plain verb plus a modest destination; personal humor can soften a social action. | 2–4 words | “Read Thread”<br>“Read mid tweets” |
| Closing invitation | Qualify the proposal and invite a real response rather than claiming finality. | 1–2 sentences | “If this resonated with you, I'd love to hear what you think and what your version of an improved OS looks like.” |

**Words and phrasing to use:** things; what matters; what if; helps you; context; more personal; less, but better; small concept

**Avoid:** revolutionary platform; unparalleled; enterprise-grade transformation; unlock your potential; industry-leading solution

**Rules:**

- Make every abstract ambition answerable by a specific product behavior.
- Use repetition to create a human cadence, not a list of unrelated slogans.
- Lowercase first-person writing belongs to personal notes; retain normal sentence casing in explanatory articles.
- Allow questions, parentheses and small asides where they clarify the thought.
- Keep scope honest: a concept is a concept, not a proven outcome.

## Do's and Don'ts

### Do

- Keep the default headline at 31px, weight 500, with mixed black and gray words.
- Use 16px gutters consistently through the object field.
- Give large gray stages 32px corners and 32px padding; use 24px padding for smaller note tiles.
- Include both an enlarged clipped interface and a small centered tactile object.
- Keep the navigation centered, translucent and 54px high.
- Give editorial prose 32px line height at 16px size.
- Keep external text actions 46px high with faint 2px outlines.
- Resolve collection pages with the final object row and 120px of white breathing room.

### Don't

- Do not use the 120px cinematic heading recipe for ordinary mosaic introductions.
- Do not give every tile a different background color; gray shells are the unifying field.
- Do not add heavy shadows to the outer 32px-radius tiles; elevation belongs to inner objects and navigation.
- Do not replace the outline actions with black rectangular conversion buttons.
- Do not make every demonstration fit fully within its frame; selected scenes deliberately extend beyond an edge.
- Do not render introductory prose in black bold type; its 20px gray regular setting makes the opening conversational.
- Do not turn the 7px red navigation marker into a notification badge with text.
- Do not import the serif lettering or tiny numeric scales of depicted applications into the page-wide type system.

## Motion and responsive

### Motion

**Observed:**

- Declared surface and action transitions include background-color, border-color and box-shadow at 0.2s; additional shadow transitions range from 0.25s to 0.4s.
- The cinematic concept introduction changes screen scale and scene composition across its narrative; the glass navigation remains above scrolled editorial content.

**Transfer:**

- Keep ordinary interaction emphasis local to controls and inner object shadows.
- Use scene-scale storytelling only for the cinematic concept variant; the default mosaic should remain understandable as a static collection.

**Unknown:**

- Exact scroll-animation curves, durations and triggering behavior are not established.
- No confirmed focus-visible appearance or reduced-motion layout is available.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 768px, 991px, 1280px, 1440px and 1920px; some pages also declare 480px and 992px.
- The established composition is desktop at 1440×900px.

**Transfer:**

- On narrow screens, preserve the contrast between a text tile, an enlarged clipped demonstration and a small isolated object while reducing grid columns.
- Keep the four-destination glass capsule within the viewport; reduce horizontal item padding before sacrificing label legibility.
- Stack metadata above the narrative when the 800px editorial arrangement no longer fits. These are adaptation recommendations, not fixed alternate layouts.

**Unknown:**

- Actual mobile column order, tile heights, padding changes and breakpoint-specific font sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
