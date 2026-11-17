# International Magic — floating gallery placards

## Overview

A pale, almost silent gallery shell gives richly colored creative work the entire stage. Medium-weight grotesk text, miniature translucent navigation and floating captions make the experience feel curated rather than promotional. It suits visually demonstrable products, cultural platforms and design-led services, with extremely sparse copy and immersive photography, moving image and rendered objects.

### Essentials

- The promise reads as a centered statement, not a billboard: 32px medium grotesk, 1.2 line height and -0.01em tracking across a 1088px text measure.
- A small control floats over an enormous empty field: the centered navigation is 451×56px, while the opening statement sits near the vertical middle of an 812px introduction; only the beginning of the media appears within the first 900px.
- Controls are tiny architectural rectangles, not pills: 3px corners, 48px button heights, 20px horizontal padding and a 0.5px edge on the surrounding glass.
- Color belongs to the exhibited work: the shell stays #f7f7f7 with #4d4d4d statement text and #121212 controls; saturated photography and graphics remain confined to media rectangles rather than coloring page bands.
- An image floats in front of another image: a 1177×724px broad stage is paired with a centered 461–700px detail, using 3px corners and a 0px 64px 72px shadow at 25% black. Every new page carries this layered exhibit device; use an actual product detail over a wide usage photograph when bespoke art is unavailable.
- The caption behaves like a museum label that follows the exhibit: a bottom-centered translucent 56px-high placard holds two 15px lines, with the second line at 58% ink. A compact updates ticker uses the same glass language.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control ink | `#121212` | `--color-ink` | text, link, action | Navigation, caption titles and the moving graphic strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Frosted white | `#fbfbfb` | `--color-glass` | surface | Visible white-glass tone on the canvas, made with white at 50% opacity; media beneath it changes its tone. |
| Gallery canvas | `#f7f7f7` | `--color-canvas` | background | Continuous page ground around every exhibit. |
| Control wash | `#e3e3e3` | `--color-button-wash` | surface, action | Visible 8% black button fill on the canvas. |
| Glass edge | `#d4d4d4` | `--color-edge` | border | Visible 14% black hairline over the pale canvas. |
| Secondary ink | `#727272` | `--color-secondary` | text | Visible 58% #121212 text on the canvas for caption subtitles. |
| Statement grey | `#4d4d4d` | `--color-statement` | text | Opening statement and restrained editorial headings. |
| Media black | `#000000` | `--color-media-black` | background | Backing inside dark media stages, not a replacement page theme. |

## Typography

- **Wand UI Pro** — All editorial text, navigation and captions. Matter-of-fact grotesk with medium strokes, broad lowercase forms and little contrast between editorial and interface lettering. OpenType features: "ordn", "ss01". If unavailable, use **Inter**. Use weight 500 and preserve the small positive tracking on controls. Font stack: "Wand UI Pro", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Wand UI Pro | 500 | 32px | 1.2 | -0.01em | Centered introductory paragraph serving as the main headline. |
| control | Wand UI Pro | 500 | 15px | 1.25 | 0.0125em | Short navigation and updates buttons. |
| placard | Wand UI Pro | 500 | 15px | 1.2 | 0.0125em | Two-line identity in the navigation and title/category pairs in exhibit captions. |

**Notes:**

- The main statement is only a little over twice the size of the interface text; imagery, not giant typography, provides spectacle.
- Keep headings in sentence case and at medium weight. Tighten the statement slightly while giving small labels a slight positive tracking.
- Exhibit chapter titles are centered short title/category pairs. Carry the statement recipe into new chapter headings rather than introducing a bold display family.

## Layout

**Density:** Extremely airy at page level, compact inside floating controls; the media sequence alternates concentrated images with long breathing intervals.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Inset around controls inside glass housings. |
| 12px | Page grid side padding and caption-button horizontal inset. |
| 16px | Column gap in the 24-column media grid. |
| 20px | Horizontal button padding. |
| 90px | One media-detail separation in the underlying scroll composition; some exhibits use 211px instead. |
| 211px | More spacious media-detail separation before the detail moves over the broad stage. |

### Containers and grids

- **statement measure**: max width 1088px. Centered introductory copy, about three quarters of the desktop width.
- **exhibit grid**: 24 columns · gap 16px · side padding 12px. Broad stage spans the central 20 columns, producing a 1177px width at desktop. Details are centered on the same axis and occupy narrower spans.
- **floating controls**: max width 451px. Centered top navigation and bottom updates housing share the same compact width; exhibit captions hug their text instead.

## Corner radius

| Element | Radius |
| --- | --- |
| controls and media | 3px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating artwork | `0px 64px 72px 0px rgba(0, 0, 0, 0.25)` | Central detail image over the broad exhibit. |
| placard | `0px 12px 32px 0px rgba(0, 0, 0, 0.12)` | Bottom exhibit caption and updates toast, not the top navigation. |

### Surfaces

#### Gallery canvas · level 0

**Use:** Continuous ground.

**CSS:** `background: #f7f7f7`

**Observed:** No colored section bands interrupt the exhibition.

**Transfer:** Let differences between examples come from the media itself.

#### Navigation glass · level 2

**Use:** Top floating controls.

**CSS:** `background: rgba(255, 255, 255, 0.5); border: 0.5px solid rgba(0, 0, 0, 0.14); border-radius: 3px; backdrop-filter: blur(96px)`

**Observed:** The small panel remains legible while picking up the tone of media behind it.

**Transfer:** Use glass only for compact navigation and labels, not for a field of content cards.

#### Placard glass · level 3

**Use:** Floating caption and updates housings.

**CSS:** `background: rgba(255, 255, 255, 0.5); border: 0.5px solid rgba(0, 0, 0, 0.14); border-radius: 3px; backdrop-filter: blur(96px); box-shadow: 0px 12px 32px 0px rgba(0, 0, 0, 0.12)`

**Observed:** Slightly raised relative to the navigation; captions sit close to the lower edge of the viewport.

**Transfer:** Keep the text compact enough that the artwork remains the dominant layer.

#### Floating artwork · level 1

**Use:** Image details layered over a larger stage.

**CSS:** `border-radius: 3px; overflow: hidden; box-shadow: 0px 64px 72px 0px rgba(0, 0, 0, 0.25)`

**Observed:** A deep, diffuse downward shadow makes the flat image feel suspended.

**Transfer:** Apply to the front image only; leave the broad backing image visually flat.

#### Dark media backing · level 0

**Use:** Contain dark films and renders within an exhibit.

**CSS:** `background: #000000; border-radius: 3px; overflow: hidden`

**Observed:** The surrounding page still remains pale.

**Transfer:** Use black only inside the bounds of imagery that needs it.

## Components

### Floating navigation

**Use:** Persistent compact orientation above the exhibits.

**CSS:** `width: 451px; height: 56px; background: rgba(255, 255, 255, 0.5); border: 0.5px solid rgba(0, 0, 0, 0.14); border-radius: 3px; backdrop-filter: blur(96px); overflow: hidden`

**Text style:** `control` — Wand UI Pro 500 · 15px/1.25 · tracking 0.0125em

**Observed:** A central two-line identity is flanked by one short button on each side. The control stays visually centered over changing imagery rather than stretching into a full-width masthead.

**Transfer:** Use two useful destinations around a short product identity.

### Ghost button

**Use:** Side destinations inside the navigation.

**CSS:** `height: 48px; padding: 0px 20px; border-radius: 3px; background: transparent; color: #121212; display: flex; align-items: center; justify-content: center; gap: 10px`

**Text style:** `control` — Wand UI Pro 500 · 15px/1.25 · tracking 0.0125em

**Observed:** Text only, with no icon or visible default outline; the housing supplies the shared edge.

**States:** Declared: hover background-color rgba(0,0,0,.08), color #121212; focus-visible box-shadow 0 0 0 4px hsla(0,0%,7%,.16), outline 0px; active background-color rgba(0,0,0,.1).

### Center identity

**Use:** Home link at the center of the navigation.

**CSS:** `width: 225px; height: 56px; color: #121212; text-align: center`

**Text style:** `placard` — Wand UI Pro 500 · 15px/1.2 · tracking 0.0125em

**Observed:** Two compact centered lines replace a large logo; the name occupies the middle half of the navigation.

**Transfer:** Break a short product or company name naturally across two lines.

### Exhibit placard

**Use:** Active artwork title and short category at the bottom center.

**CSS:** `height: 56px; padding: 4px; background: rgba(255, 255, 255, 0.5); border: 0.5px solid rgba(0, 0, 0, 0.14); border-radius: 3px; backdrop-filter: blur(96px); box-shadow: 0px 12px 32px 0px rgba(0, 0, 0, 0.12); text-align: center`

**Text style:** `placard` — Wand UI Pro 500 · 15px/1.2 · tracking 0.0125em

**Observed:** Content-hugging glass contains a clickable two-line title/category pair, inset horizontally by 12px within the inner button. The second line uses 58% ink. The label changes with the active exhibit and stays separate from the media frame.

**Transfer:** Name the example on line one and its function on line two; retain the bottom-centered anchoring.

### Updates button

**Use:** Action at the right of the lower updates housing.

**CSS:** `height: 48px; padding: 0px 20px; border-radius: 3px; background: rgba(0, 0, 0, 0.08); color: #121212; display: flex; align-items: center; gap: 10px`

**Text style:** `control` — Wand UI Pro 500 · 15px/1.25 · tracking 0.0125em

**Observed:** The restrained filled button is embedded in glass, never presented as an oversized standalone conversion button.

**States:** Declared: hover background-color transparent, color #121212; focus-visible box-shadow 0 0 0 4px hsla(0,0%,7%,.16), outline 0px; active background #121212 with color #121212.

### Updates ticker

**Use:** Compact lower-screen announcement device.

**CSS:** `width: 451px; height: 56px; padding: 4px 4px 4px 0px; display: flex; align-items: center; justify-content: space-between; gap: 4px; background: rgba(255, 255, 255, 0.5); border: 0.5px solid rgba(0, 0, 0, 0.14); border-radius: 3px; backdrop-filter: blur(96px); box-shadow: 0px 12px 32px 0px rgba(0, 0, 0, 0.12); overflow: hidden`

**Observed:** A 345×46px masked graphic strip moves to the left of the Updates button. It shares the bottom toast position with the changing exhibit placard.

**Transfer:** Create an original repeated product-name or announcement strip, clipped inside the left slot; keep the action outside the moving strip.

### Floating detail image

**Use:** The foreground detail in the layered exhibit.

**CSS:** `border-radius: 3px; box-shadow: 0px 64px 72px 0px rgba(0, 0, 0, 0.25); overflow: hidden; position: relative; z-index: 2`

**Observed:** Centered square, portrait and landscape images vary between 342px and 700px wide, usually around 581px. They pass over a wider sticky teaser during the scroll.

**Transfer:** Choose a tighter view of the same story as the background, not a generic decorative card.

## Imagery and graphics

### Layered editorial exhibit

**Use:** The signature visual proof device throughout the page.

**Observed:** Large photographs and films show printed matter, exhibition interiors, fashion, devices and graphic identities. A broad 1177×724px image is overlaid by a narrower centered portrait or square. Images remain crisply rectangular with minimal rounding; color is vivid and unfiltered, while the grey shell recedes.

**Transfer:** Pair a wide real-world context image with a detail showing the product or its output. For software, use a filmed device in use behind a crisp single-screen detail rather than a grid of feature cards.

**Build:** Use a centered 24-column grid with 16px gaps and 12px side padding. Put the broad image across the central 20 columns with a sticky wrapper. Place a 581px-wide foreground image on the same centerline above it at z-index 2; clip to a 3px radius and apply the Floating artwork shadow. Preserve the foreground asset's aspect ratio. Connect the overlap to scroll position so the detail traverses the broad image, then exits into the pale canvas.

### Physical and synthetic material studies

**Use:** Inside individual exhibits as high-impact product proof.

**Observed:** Glossy chrome objects, molded bright plastic, screens held in hands, clean studio figures and reflective surfaces alternate with documentary interiors. Dark renders use black backing; lighter studies use clean studio space. Lighting and palette belong to each artwork, not to the surrounding UI.

**Transfer:** Use one highly resolved object or product detail, with believable directional light and material texture. The minimum equivalent is a well-lit close-up photograph on a simple backing; do not replace it with generic abstract blobs.

### Moving identity strip

**Use:** Graphic content inside the Updates ticker.

**Observed:** A clipped ink-colored graphic strip occupies most of the compact lower housing and repeats horizontally.

**Transfer:** Use original lettering or small original product marks in a continuous strip; the housing and motion matter more than matching the graphic.

**Build:** Create a 345×46px overflow-hidden slot containing two identical adjacent SVG strips. Use #121212 silhouettes on transparent backing, repeat enough original letterforms to fill the strip, and translate the pair horizontally in a seamless linear loop. Keep the 100px action fixed beside the slot.

## Section recipes

How recurring sections are built.

### First screen: Centered statement opening

**Observed:** The Gallery canvas fills the first screen. Floating navigation sits centered near the top, occupying less than one third of the 1440px width. The main statement spans a 1088px measure at 32px/1.2 in grey, centered as three lines near the vertical middle of an 812px introduction. There is no separate eyebrow, supporting paragraph or hero CTA row: the statement contains both positioning and scope. Within the first 900px the full statement, navigation, lower updates housing and top edge of a centered 700px-wide media piece are visible; the complete media exhibit falls below the fold. Layers run from pale canvas to statement and emerging media, then compact glass controls.

**Transfer:** Open a new marketing page with one composed two-sentence promise stating what the product does and for whom. Keep the spectacle below the statement, with only its leading edge visible. If no custom artwork exists, begin with an excellent product-in-use photograph. A more focused detail page can use a short centered title/category pair before its exhibit while retaining the small floating navigation.

**Avoid:** Do not turn this into a giant split-screen headline and product mockup, or add a row of bright conversion buttons under the statement.

**Text style:** `statement` — Wand UI Pro 500 · 32px/1.2 · tracking -0.01em

### Chapter title interlude

**Observed:** Short centered project-name and discipline pairs sit in a broad pale field before the next broad media stage rises into view. Their restrained scale leaves the imagery to supply emphasis; the bottom Exhibit placard repeats the active title in a smaller persistent form.

**Transfer:** Use a short example or capability title paired with a specific category. Keep the surrounding field open and avoid adding an unrelated explanatory text column.

**Text style:** `statement` — Wand UI Pro 500 · 32px/1.2 · tracking -0.01em

### Layered proof stage

**Observed:** The broad stage occupies the central 1177px at desktop, with a nominal 724px media height. A Floating detail image comes over it on the central axis, often 581×755px or 581×581px, while the Exhibit placard stays bottom-centered. Portrait detail variants can be 461px wide; landscape details reach 700px.

**Transfer:** Give each proof chapter one wide context view and one closer detail. Alternate photography, screen recordings and object studies without changing the shell.

### Exhibit release and continuation

**Observed:** After the close-up, the broad media moves upward out of the pale field while its small placard remains near the lower viewport edge. The narrative continues as another centered title and media exhibit, rather than becoming a dense card index.

**Transfer:** Close a new page with the same visual grammar: finish on a strong final demonstration and keep the compact navigation or a concise lower action accessible. Let the final content determine the ending rather than introducing a contrasting oversized sales band.

## Page flow

**Storyline:** concise positioning → visual proof chapters → context/detail reveals → continued exploration

### Introduce a visually led practice or product through curated examples rather than a feature inventory

1. **Positioning** — A centered two-sentence statement explains breadth and working scope in one compact grey paragraph.
2. **Visual proof** — The first narrower media exhibit establishes the image-led character.
3. **Capability chapters** — Repeated centered title interludes lead into wide photographs or films with floating detail images; a changing lower placard supplies the name and category.
4. **Continued exploration** — The final structural block retains the same broad stage and raised detail construction, with navigation providing the route onward instead of a separate conventional footer composition.

**Transfer:** Use a curated number of examples sufficient to demonstrate the new product. Preserve the shift from concise positioning to immersive evidence, but do not reproduce the long sequence or its number of chapters.

## Writing

Understated, descriptive and culturally fluent. Confidence comes from naming what the work does and showing it, not from superlatives or overt conversion pressure.

**Do not copy:** Do not reuse International Magic's name, project/client names, artwork, logos, service claims or specific collaborations. Source phrases are voice examples only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The organization speaks as 'we'; the introduction names the organization before describing its work. Direct second-person address is not prominent.
- **Rhythm:** A substantial two-sentence positioning paragraph is followed by extremely short noun labels and title/category pairs. Navigation is one word wherever possible; punctuation is restrained.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening positioning | Name the organization, define its operating territory, then state whom it works with and on what. | Two sentences; the source uses 32 words. | “[Brand] operates across communication, innovation and entertainment. We work with brands, institutions and artists on Creative Direction, Identity Design, Cultural Strategy and Platform Experience.” |
| Exhibit category | A succinct discipline or deliverable below a specific title. | 1–4 words | “Art Direction”<br>“Campaign & Identity”<br>“Digital Product Passports” |
| Navigation and action | Plain destination noun without persuasion or extra helper copy. | 1 word | “Projects”<br>“Studio”<br>“Updates” |

**Words and phrasing to use:** works with; operates across; specific discipline names; concrete deliverable nouns; short category pairs

**Avoid:** revolutionary; unlock your potential; best-in-class; seamless solutions; exclamation-led urgency

**Rules:**

- Let the opening paragraph carry both positioning and scope; do not repeat it as a second subtitle.
- Name the thing shown before describing its category.
- Keep captions factual enough to read as exhibition labels.
- Let detailed visual proof carry claims that would otherwise require promotional adjectives.

## Do's and Don'ts

### Do

- Keep the statement at 32px, weight 500 and -0.01em tracking.
- Center the 1088px opening measure on the same axis as the exhibits.
- Use 3px corners for buttons, glass housings and image edges.
- Keep controls at 15px with 0.0125em tracking.
- Apply the deep 64px-offset shadow only to foreground images.
- Retain the 0.5px glass edge and 96px backdrop blur on compact controls.
- Stage a narrow detail over a broad context image rather than beside it.
- Keep saturated color inside media while the canvas stays #f7f7f7.

### Don't

- Do not round controls into pills or soften image corners to 16px.
- Do not make the navigation a full-width opaque toolbar.
- Do not replace #4d4d4d statement text with heavy black display lettering.
- Do not distribute the foreground image shadow to every page element.
- Do not add a permanent brand-color gradient behind the pale gallery shell.
- Do not turn title/category placards into long paragraphs or multi-action panels.
- Do not frame every image in a fake browser window; preserve the editorial media treatment.
- Do not use oversized iconography or decorative UI badges to fill the open canvas.

## Motion and responsive

### Motion

**Observed:**

- Broad teaser wrappers use sticky positioning, and raised detail images travel over them through the image-led sequence.
- Navigation declares a 0.4s cubic-bezier(0.16, 1, 0.3, 1) transition; buttons declare 0.15s transitions.
- Toast motion declares transform 0.32s cubic-bezier(0.16, 1, 0.3, 1), with slide-in and slide-out animation names.
- The graphic strip declares infinite linear movement.

**Transfer:**

- Connect the foreground/background relationship to scroll progress rather than making it a static collage.
- Swap the lower exhibit label as the active proof chapter changes; use the declared toast timing for those compact changes.
- Keep linear looping motion confined to the clipped graphic slot so the adjacent action stays steady.

**Unknown:**

- Exact scroll trigger thresholds and the ticker loop duration are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 375px, 480px, 768px, 768px, 1024px, 1024px, 1200px, 1200px, 1440px, 1680px and 1680px.

**Transfer:**

- On narrow screens preserve the single centered axis and keep the compact controls within the available width.
- Scale broad and foreground media together while retaining their distinct widths and original aspect ratios; keep caption text separate from artwork.

**Unknown:**

- Mobile type sizes, menu expansion behavior and the precise narrow-screen overlap choreography are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
