# Granola — paper tools, playful texture

## Overview

An editorial, human-feeling style for software that makes work feel less mechanical. White and warm paper surfaces, charcoal serif headlines and olive-green actions sit beside tactile print collages, sunlit landscapes and carefully staged interfaces. The overall density is low, with compact functional details inside expansive compositions and occasional dark proof chapters.

### Essentials

- Headlines feel like oversized book typography rather than software UI: quadrant at weight 400, an 86.4px opening with 0.93 line height and -0.02em tracking; major chapter statements grow to 108px with 0.97 line height.
- The opening is an asymmetric desk-like stage: a narrow four-line promise on the left, one 56px olive pill action, and a large paper application window over overlapping printed textures on the right. Keep text readable within the first 900px while the object reaches toward the outer edge.
- Color arrives in concentrated chapters, not across the whole canvas: white dominates, #f7f7f2 adds paper warmth, #b2c248 supplies occasional full-width bands, and #292929 supports inverted proof. Use #5b6f00 for the opening conversion pill.
- Software looks like a physical artifact: cream windows with rounded corners float above grainy landscape photography or halftone print panels. Include this tactile staging; without finished product media, construct one legible sample workflow on a paper window over a simple printed collage.
- The closing is a product-shaped invitation, not a generic centered banner: an 88px serif promise sits inside a 768px paper window with 28px top corners, over an edge-to-edge print collage. The alternative feature-page closing uses a green frame and one handwritten word.
- The identity gets a monumental final gesture: compact four-column footer navigation gives way to a 1200px-wide, 253px-high wordmark artwork. Render the new identity at comparable width; a bold custom typeset wordmark is the fallback, not a tiny centered logo.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Printed chartreuse | `#b2c248` | `--color-brand` | background, accent | Concentrated chapter bands and framed closing invitations. |
| Olive action | `#5b6f00` | `--color-action` | action | Opening primary button; platform conversion buttons on feature and pricing pages. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fresh yellow green | `#d1e043` | `--color-new` | accent, surface | Small New badge inside an announcement, not a substitute for the large green bands. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Dominant page background, flat cards and inverted text. |
| Warm inverse | `#fcfcf8` | `--color-inverse` | text | Light text inside dark or olive core conversion buttons. |
| Warm paper | `#f7f7f2` | `--color-paper` | surface, background | Application windows, integration chapters and softly differentiated panels. |
| Soft paper edge | `#eaebe5` | `--color-soft-edge` | border, surface | Quiet panel outlines and announcement hover fill. |
| Paper edge | `#d5d5d2` | `--color-rule` | border | 0.5px card edges, comparison cells and FAQ separators. |
| Warm gray text | `#72726e` | `--color-secondary` | text | Support lines, metadata and less prominent explanatory copy. |
| Charcoal ink | `#292929` | `--color-ink` | text, background, action | Default headings and text; inverted proof bands and dark secondary conversion buttons. |
| Deep reading ink | `#0e0f0c` | `--color-deep-ink` | text | Supporting opening text and compact workflow paragraphs; feature-page heading variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| feature demonstrations and pricing pages | Pale olive | `#e5eacd` | `--color-soft-green` | surface, action | Prompt arrow disks, inclusion checks and secondary platform buttons. |

## Typography

- **quadrant** — Editorial headings, quotations, section labels and prominent numerals. A broad, soft old-style serif with assertive brackets, generous lowercase forms and a conversational bookish presence. If unavailable, use **Libre Baskerville**. Use regular 400; preserve the tight line heights and check headline wrapping. Font stack: "quadrant", "Libre Baskerville", Georgia, serif.
- **melange** — Paragraphs, navigation, buttons, metadata and functional labels. A clean, round humanist grotesk that stays unobtrusive next to the serif. If unavailable, use **DM Sans**. Use 300–600; use a variable weight near 430 for core buttons. Font stack: "melange", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| monumental-line | quadrant | 400 | 160px | 1 | -0.015em | size min(12vw, 160px) | Short audience-oriented editorial statement passing behind a proof band. |
| chapter-display | quadrant | 400 | 108px | 0.97 | -0.02em | size clamp(72px, 7.5vw, 120px) | Major product capability statement; substantially larger than the ordinary section heading. |
| closing-display | quadrant | 400 | 88px | 0.98 | -0.01em | fixed | Large invitation inside the paper closing window. |
| display | quadrant | 400 | 86.4px | 0.93 | -0.02em | size clamp(68px, 6vw, 110px) | Default landing-page headline, constrained to a narrow measure with deliberate multiline wrapping. |
| proof-heading | quadrant | 400 | 60px | 1 | -0.015em | fixed | Centered white title in the dark testimonial chapter. |
| heading | quadrant | 400 | 48px | 1 | -0.015em | fixed | Regular section titles, centered feature chapters and right-column transitional statements. |
| quote | quadrant | 400 | 36px | 1.1 | normal | fixed | White editorial quotations on dark proof cards. |
| feature-heading | quadrant | 400 | 32px | 1.05 | -0.01em | fixed | Feature title in a heading-and-description row above wide media. |
| footer-heading | quadrant | 400 | 24px | 0.95 | -0.01em | fixed | Footer column headings. |
| body-lg | melange | 400 | 22px | 1.35 | normal | fixed | Capability descriptions beside feature headings. |
| lead | melange | 400 | 20px | 1.4 | normal | fixed | Short opening support lines; split into two clean sentences. |
| eyebrow | quadrant | 400 | 16px | 1.5 | 0.02em | fixed | Sentence-case section markers above large chapter titles. |
| body | melange | 400 | 16px | 1.5 | normal | fixed | Workflow explanations and normal marketing prose. |
| button | melange | 430 | 16px | 1.125 | 0.01em | fixed | Core conversion and outline action labels. |
| navigation | melange | 400 | 14px | 24px | 0.01em | fixed | Header links and compact header actions. |
| footer-link | melange | 400 | 14px | 0.95 | 0.02em | fixed | Compact footer links with generous separation between rows. |
| caption | melange | 400 | 13px | 16px | 0.01em | fixed | Platform availability and small utility annotations. |
| announcement | melange | 500 | 13px | 16px | 0.01em | fixed | Announcement label next to the New badge. |
| badge | melange | 500 | 12px | 16px | 0.02em | fixed | New marker inside the announcement pill. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| feature landing pages | feature-display | quadrant | 400 | 68px | 0.9 | -0.015em | fixed | Centered product feature headline. |
| feature, pricing and recruiting pages | framed-closing-heading | quadrant | 400 | 68px | 1 | -0.015em | fixed | Green-framed closing title; also the recruiting opening headline. |
| pricing pages | pricing-display | quadrant | 400 | 68px | 0.6 | -0.015em | fixed | Single-line pricing headline; keep the unusually tight box to this single-line use. |
| enterprise pages | enterprise-heading | quadrant | 400 | 54px | 1.1 | -0.015em | fixed | Enterprise opening and section titles, allowing more text at a measured pace. |
| pricing pages | price | quadrant | 400 | 36px | 40px | normal | fixed | Plan price aligned to a much smaller billing qualifier. |
| enterprise case-study proof | stat | quadrant | 400 | 32px | 1.25 | -0.02em | fixed | Evidence numerals in compact paper tiles over photography. |
| feature, pricing and recruiting pages | support-light | melange | 300 | 24px | 32px | normal | fixed | Muted centered supporting lines beneath feature headings and closing invitations. |
| FAQ sections | question | quadrant | 400 | 24px | 32px | normal | fixed | Full-width accordion questions. |
| feature demonstrations | prompt-label | melange | 400 | 24px | 32px | normal | fixed | Short example tasks inside moving prompt pills. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use regular serif weight throughout the hierarchy; scale and measure, not boldness, establish emphasis. Large headings tighten to -0.02em while smaller titles sit at -0.01em or -0.015em.
- Keep body copy sans-serif. The handwritten emphasis is an illustrated word, not a third paragraph font; limit it to the scoped recruiting opening or green-framed invitation.
- The logo is artwork, not a display-font recipe. Its heavy, informal silhouette intentionally contrasts with the light serif headlines.

## Layout

**Density:** Airy overall, with tightly assembled controls and metadata inside broad editorial spaces.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon gaps and heading-to-short-description separation. |
| 12px | Small grids, prompt interior spacing and compact controls. |
| 16px | Minor group gaps and space below feature-row separators. |
| 24px | Card padding, repeated-card gutters and small content clusters. |
| 32px | Opening content stack and title-to-support spacing on feature pages. |
| 40px | Desktop container side padding and paper-window content gaps. |
| 48px | Two-column enterprise gutters and paper closing side padding. |
| 64px | Framed invitation inset and footer separation. |
| 96px | Workflow chapter separation and paper closing bottom padding. |
| 112px | Dark and green chapter vertical padding; footer block separation. |
| 124px | Vertical gap between wide capability-media chapters. |
| 128px | Major product section vertical padding. |
| 160px | Editorial transition padding and enterprise chapter spacing. |
| 192px | Feature and pricing chapter separation. |

### Containers and grids

- **Editorial container**: max width 1280px · side padding 40px. Centered desktop outer container; its 1200px inner width anchors the opening, proof, grids and footer.
- **Wide capability stage**: max width 1280px · side padding 0px. Wide media chapters extend to the full container width with a 448px description column beside a flexible serif title.
- **Feature cards**: 3 columns · gap 24px. Three 384px cards across the 1200px inner content area.
- **Narrow reading block**: max width 768px. FAQ list, focused quotations and closing paper window.
- **Enterprise pair** (only for enterprise pages): 2 columns · gap 48px. Two 576px media or content columns in enterprise sections.
- **Centered feature title** (only for feature landing pages): max width 896px. Centered feature-page opening and social-proof headings.
- **Recruiting editorial** (only for recruiting pages): max width 1152px · side padding 24px. 1104px inner editorial layout with text on the left and people or role lists on the right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions and navigation | 9999px (pill) |
|  | Marketing cards | 8px |
|  | Media stages | 16px |
|  | Paper demonstration window | 24px |
|  | Closing window top corners | 28px |
| enterprise case-study proof | Stat tile | 4px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Closing paper lift | `0px 4px 50px 0px rgba(54,54,53,0.25)` | Separates the paper invitation from busy printed artwork. |
|  | Demonstration window lift | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Physical depth for cream product windows, not flat marketing cards. |
| feature demonstrations | Prompt lift | `0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)` | Small floating prompt pills. |

### Surfaces

#### Canvas · level 0

**Use:** Default page field.

**CSS:** `background: #ffffff; color: #292929`

**Observed:** Mostly unboxed white space surrounds the content.

**Transfer:** Let type and staged media create structure rather than enclosing every section.

#### Paper band · level 0

**Use:** Warm capability chapters and softer proof regions.

**CSS:** `background: #f7f7f2; padding: 128px 0px`

**Observed:** Full-width warmth, not a high-contrast card grid.

**Transfer:** Use for one sustained chapter with a larger statement.

#### Green chapter · level 0

**Use:** A concentrated product promise or demonstration.

**CSS:** `background: #b2c248; padding: 112px 0px; overflow-x: clip`

**Observed:** A flat printed green field interrupts the white page.

**Transfer:** Keep dark text and the restrained product-window vocabulary within it.

#### Dark proof · level 0

**Use:** Customer evidence with editorial impact.

**CSS:** `background: #292929; color: #ffffff; padding: 112px 0px; overflow: hidden`

**Observed:** Large serif quotations and white customer identities sit on the same charcoal field.

**Transfer:** Use the inversion for proof, not as the default whole-page theme.

#### Flat card · level 1

**Use:** Grouped examples, resources and recipe cards.

**CSS:** `background: #ffffff; border: 0.5px solid #d5d5d2; border-radius: 8px; padding: 24px`

**Observed:** Edges are hairline and corners modest; no blanket drop shadow.

**Transfer:** Use the same shell for new examples or documentation entry points.

#### Closing paper · level 2

**Use:** Default closing invitation window.

**CSS:** `background: #f7f7f2; border-radius: 28px 28px 0px 0px; padding: 28px 48px 96px; max-width: 768px; box-shadow: 0px 4px 50px 0px rgba(54,54,53,0.25)`

**Observed:** The bottom meets the section edge while the rounded top floats over the collage.

**Transfer:** Retain the application-window metaphor and let content determine height.

#### Green invitation frame · level 1

**Only for:** feature, pricing and recruiting pages

**Use:** Alternative compact closing treatment.

**CSS:** `background: #b2c248; border: 0.5px solid #eaebe5; border-radius: 8px; padding: 64px 64px 0px`

**Observed:** A white panel with 8px top corners sits inside the green frame; its interior uses 96px vertical and 64px horizontal padding.

**Transfer:** Use a single emphasized handwritten word and a pair of platform actions, preserving the paper-window silhouette.

## Components

### Floating navigation

**Use:** Persistent desktop orientation and conversion.

**CSS:** `height: 56px; padding: 0px 8px; background: rgba(255,255,255,0.584); border: 0.5px solid rgba(213,213,210,0.584); border-radius: 9999px; display: flex; align-items: center; box-shadow: 0px 0.6px 1.2px rgba(0,0,0,0.024), 0px 3.5px 11.7px rgba(0,0,0,0.035)`

**Text style:** `navigation` — melange 400 · 14px/24px · tracking 0.01em

**Observed:** Logo left, small links centered, two compact actions right. It is fixed 8px below the top within the editorial container. At the opening it visually recedes into white; over later content it reads as a white floating capsule.

**States:** Declared: hover navigation links use #f7f7f2; focus-visible state for those links is unknown. The capsule transitions background-color, border-color and box-shadow over 0.3s ease-out.

**Transfer:** Keep the central links sparse and reserve the right edge for the action pair.

### Primary button

**Use:** Default opening conversion.

**CSS:** `background: #5b6f00; color: #fcfcf8; height: 56px; padding: 9px 24px; border-radius: 9999px; display: inline-flex; align-items: center; justify-content: center; gap: 4px`

**Text style:** `button` — melange 430 · 16px/1.125 · tracking 0.01em

**Observed:** Text followed by a small downward arrow. Later capability sections and the default paper closing use the charcoal version rather than repeating the green fill. Feature-page platform buttons use a larger 20px/28px, weight 500 label and leading platform icon.

**States:** Declared: hover opening fill #788c15; focus-visible outline 2px solid color-mix(in srgb,#b2c248 60%,transparent), offset 1px. Charcoal variant hover fill #acada8.

### Outline button

**Use:** Secondary action beside the closing conversion or case-study links.

**CSS:** `color: #292929; background: transparent; border: 0.5px solid #292929; border-radius: 9999px; padding: 9px 24px; height: 56px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — melange 430 · 16px/1.125 · tracking 0.01em

**Observed:** Shares the primary action silhouette without competing with its solid fill. Enterprise case-study variants are 48px high with 16px/24px medium sans labels.

**States:** Declared: hover background-color #625a220f; focus-visible outline 2px solid color-mix(in srgb,#b2c248 60%,transparent), offset 1px.

### Announcement pill

**Use:** Small news hook above the opening promise.

**CSS:** `background: #f7f7f2; border-radius: 9999px; padding: 6px 12px 6px 6px; height: 32px; display: flex; align-items: center; gap: 8px`

**Text style:** `announcement` — melange 500 · 13px/16px · tracking 0.01em

**Observed:** A small yellow-green New badge leads the label and a fine arrow ends the row. The badge uses the badge recipe with 2px 8px padding and 10px corners.

**States:** Declared: hover background-color #eaebe5; focus-visible state unknown.

### Footer link

**Use:** Secondary navigation below the closing invitation.

**CSS:** `display: flex; align-items: center; min-height: 24px; padding: 2px 0px; color: #292929; text-decoration-line: underline; text-decoration-color: transparent; text-underline-offset: 2px`

**Text style:** `footer-link` — melange 400 · 14px/0.95 · tracking 0.02em

**Observed:** Sentence-case labels are stacked at 6px gaps beneath serif column headings. Social icons and copyright occupy a separate low row before the monumental wordmark.

**States:** Declared: hover text-decoration-color #6a6c6a and text-underline-offset 4px; focus-visible state unknown.

### Example card

**Only for:** feature landing pages

**Use:** A compact capability example or reusable workflow.

**CSS:** `background: #ffffff; border: 0.5px solid #d5d5d2; border-radius: 8px; padding: 24px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `body` — melange 400 · 16px/1.5

**Observed:** Small task tag first, short explanation next, then author/avatar attribution. Neighboring cards can contain product media on warm paper rather than more copy.

**States:** Declared: transform transition 0.3s cubic-bezier(.4,0,.2,1); focus-visible state unknown.

**Transfer:** Use a genuine example with a concrete output; retain the restrained shell instead of turning it into a promotional tile.

### Prompt pill

**Only for:** feature demonstrations

**Use:** Examples of tasks the product can perform.

**CSS:** `background: #ffffff; border: 0.5px solid #d5d5d2; border-radius: 9999px; padding: 12px 12px 12px 20px; display: flex; align-items: center; justify-content: space-between; gap: 12px; box-shadow: 0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)`

**Text style:** `prompt-label` — melange 400 · 24px/32px

**Observed:** An upward arrow in a pale olive disk follows each short task. Rows extend beyond the visible region and fade at the sides.

**Transfer:** Use a moving vocabulary of real tasks, not feature names or decorative filler.

### FAQ row

**Only for:** FAQ sections

**Use:** Resolve practical objections.

**CSS:** `padding: 20px 0px; border-bottom: 0.5px solid #d5d5d2; display: flex; align-items: center; width: 100%`

**Text style:** `question` — quadrant 400 · 24px/32px

**Observed:** A serif question fills the left and a small downward chevron sits at the right. The list is 768px wide, with a top rule on the first row; ordinary closed rows are about 73px high.

**Transfer:** Allow longer questions to wrap naturally without fixing every row to one height.

### Plan card

**Only for:** pricing pages

**Use:** Choose among subscription levels.

**CSS:** `border: 0.5px solid #d5d5d2; border-radius: 8px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `body` — melange 400 · 16px/1.5

**Observed:** Three equal cards: plan label and short audience description above a separator; price and small billing qualifier; full-width olive pill; checklist and a warm-paper lower summary. Content padding is 28px. The enterprise option adds a pale olive secondary button. No oversized recommended-plan badge.

**Transfer:** Preserve alignment of prices and actions across plans; use honest feature differences rather than stronger decorative emphasis.

### Stat tile

**Only for:** enterprise case-study proof

**Use:** Quantified customer outcomes.

**CSS:** `background: #f7f7f2; border-radius: 4px; padding: 24px; display: flex; flex-direction: column; gap: 8px`

**Text style:** `stat` — quadrant 400 · 32px/1.25 · tracking -0.02em

**Observed:** A stack of three compact paper tiles is centered over a turquoise pool image. Each numeral has a small warm-gray explanatory line; a longer customer quotation occupies the adjacent column.

**Transfer:** Keep the number integrated into a scene and explain the unit or time period; do not inflate it into a giant dashboard counter.

## Imagery and graphics

### Printed collage stage

**Use:** Signature backing for the opening object and the closing window.

**Observed:** Overlapping rectangular scraps combine acid-green paper, black diagram markings, large cropped type and a vivid radial pink-blue-orange halftone textile-like print. Grain and ink irregularity make it feel physically printed rather than digitally glossy. In the opening the collage stays to the right behind the cream application; in the closing it fills the section.

**Transfer:** Create an original print vocabulary related to the new product. The minimum version is a chartreuse textured rectangle, a dark diagram scrap and a grainy radial color print behind one readable paper window.

**Build:** Use three independently clipped SVG or image layers. Make one green sheet with fine monochrome noise, 1px diagram arcs and oversized partially clipped ink lettering; one charcoal sheet with small pale dots and thin lines; one radial field of alternating warm and cool wedges covered by a 3px dotted halftone pattern and low-opacity noise. Offset the sheets by 80–180px, crop at the stage edge, and place the cream window in front. Keep texture contrast below the application content.

### Landscape-backed product scene

**Use:** Recurring feature media and workflow demonstrations.

**Observed:** Cream application windows, detached popovers and small video-call portraits are backed by alpine lakes, turquoise water, warm rock and soft skies. Media occupies more space than the explanation, commonly 1280×527px wide or a 600×600px workflow square. Windows are cropped to emphasize a single action rather than showing the entire desktop.

**Transfer:** Choose bright, natural environmental photography with soft grain. Stage a small, readable interaction on top; if no interface exists yet, build a short real-content mockup with one outcome rather than a decorative blank window.

**Build:** Set a landscape photograph as an object-fit cover backing; layer a warm-paper rounded window with a fine translucent brown edge and the demonstration-window shadow. Place one smaller white action card overlapping its lower edge. Clip the complete scene to a modest rounded rectangle, preserving enough natural background to give the composition air.

### Paper diagrams and application emblems

**Use:** Compatibility and ecosystem proof.

**Observed:** Large familiar application emblems sit in white rounded-square tiles over desaturated cream notebook paper, faint ruling, pencil-like arcs and numeric markings. A wider integration row uses individual white tiles that rise and fall slightly in height.

**Transfer:** Use genuine supported destinations or neutral pictograms for the new ecosystem, maintaining the pale paper field and clear emblem scale.

**Build:** Layer an off-white field with 1px gray horizontal rules roughly 80px apart, a few oversized low-opacity pencil curves and sparse numeric ticks. Center three white rounded-square tiles with faint edges; keep colored emblems inside the tiles rather than tinting the whole section.

### Editorial proof portraits

**Use:** Dark customer quote chapter.

**Observed:** Black-and-white square headshots sit toward the lower-right of large rectangular quote cards. Fine grid lines cross the portrait backing; company identity is above the quotation, person and role below it.

**Transfer:** Pair authentic attribution with restrained monochrome portraiture, leaving the serif quotation as the dominant object.

### Monumental identity artwork

**Use:** The final visual statement below footer navigation.

**Observed:** A heavy, informal black wordmark and symbol span 1200×253px on white. The mark has more visual mass than any footer text and sits above a narrow green end strip.

**Transfer:** Set the new product identity at near-container width. If there is no custom mark, make a bold, compact typeset wordmark with an original simple symbol and preserve the large horizontal silhouette.

**Build:** Use an SVG viewBox sized to the wordmark's actual bounds, fill it with charcoal, and render width 100% with proportional height. Keep 40px above and 48px below inside the editorial container; do not imitate the source symbol.

### Handwritten word insert

**Only for:** feature, pricing and recruiting pages

**Use:** A single human emphasis inside a serif headline.

**Observed:** A loose black brush-script word replaces one word in the headline, extending above and below the serif baseline. Examples communicate a mental or emotional benefit rather than a technical term.

**Transfer:** Draw one original word as SVG strokes or use a carefully lettered image. Keep it readable and close to the serif cap-height; do not make a whole script headline.

**Build:** Create a transparent SVG with an ink-colored, slightly right-slanted brush-lettered word. Fit it inline using its viewBox, with slight vertical overflow and no rectangular backing. For a simpler version, hand-draw a single expressive word and vectorize it.

### People collage and gallery

**Only for:** recruiting pages

**Use:** Opening cultural image and later life-at-work chapter.

**Observed:** A handful of overlapping photographs with 16px corners hover in the upper-right above the opening headline: people outdoors, an office, a work screen and architectural detail. Later, a five-column irregular gallery uses candid color images with gentle rotations and varied proportions. A separate dense portrait matrix sits beside editorial text and small team filters.

**Transfer:** Use genuine work-life photography with mixed scales and informal framing; retain the feeling of a physical stack and contact sheet instead of a uniform stock-photo grid.

**Build:** Place five rounded photo layers within a right-weighted stage, rotate each by a few degrees and overlap them substantially with tiny contact shadows. For the gallery, stagger five narrow columns with 10px gutters and preserve each image's native aspect ratio.

### Icons

**Observed:** Functional arrows and controls are mostly 16–24px. Thin rounded line icons use approximately 1.9px strokes; platform and social symbols use solid silhouettes. Interface scenes contain more icons than the surrounding marketing text.

**Transfer:** Use simple round-ended outline icons for utilities and arrows, with solid platform marks only when meaningful. Keep arrows adjacent to action text rather than adding large decorative feature icons.

## Section recipes

How recurring sections are built.

### First screen: Tactile product opening

**Observed:** The first 900px is white with a slim navigation at the top. A left-aligned text stack starts well below it: Announcement pill, a roughly 562px-wide four-line display headline, two short 20px support lines, Primary button and a muted availability caption. The title occupies about two-fifths of the screen width. On the right, Printed collage stage begins higher than the headline and holds a tall cream application window plus a small overlapping portrait strip; it reaches the lower and right edges. Back-to-front layers are white canvas, paper scraps, cream product window, then detached controls and people. All the promise, support, conversion and main object are visible above 900px; the explanation of how it works begins below.

**Transfer:** Use the same visual asymmetry for a different product: a specific narrow promise and one recognizable sample output staged as a physical tool. Without polished media, construct a legible window showing one real input and outcome over the printed collage. Feature pages can instead center the 68px headline above a pale perspective field of interface cards; enterprise pages use a 54px promise beside a smaller conceptual collage; recruiting opens with a photo stack above the text; pricing opens directly with a centered title and three plan cards.

**Avoid:** Do not replace this with a centered headline over a generic full-width dashboard, or shrink the main object into a small illustration beside a large empty white region.

**Text style:** `display` — quadrant 400 · 86.4px/0.93 · tracking -0.02em

### Editorial chapter transition

**Observed:** Short serif eyebrow above a very large chapter statement; the default chapter-display is 108px. A compact conversion button follows, then a large pause before the detail. Another transition places a 48px statement in the right half of a white two-column container with 160px vertical padding.

**Transfer:** Alternate broad promises with more focused explanations; choose the headline scale according to narrative weight rather than giving every section the same title treatment.

### Workflow rail

**Observed:** A small left rail names stages while a 600px right column carries a serif feature title, a 16px explanation and a 600px square Landscape-backed product scene. The stages are separated by 96px. Active rail labels are dark; inactive ones are gray with thin dividing lines.

**Transfer:** Use stages that describe the new user's process, not a list of unrelated features. Keep the media outcome as the chapter's focal point.

### Wide capability chapter

**Observed:** A fine horizontal rule precedes the 32px feature title on the left and a 448px-wide, 22px description on the right. The media begins 32px below and spans 1280×527px. Chapters are separated by 124px; a mobile-oriented capability can split the image into two unequal panels and add a dark action above it.

**Transfer:** Write one capability per chapter and use tightly selected interface details, natural photography and varied media arrangements while keeping the consistent heading row.

**Text style:** `feature-heading` — quadrant 400 · 32px/1.05 · tracking -0.01em

### Audience proof and dark quotation

**Observed:** A 160px short serif line on white passes behind a charcoal customer band containing two rows of six white identities, small crosshair-like registration marks and a centered serif caption. A separate Dark proof chapter uses a 60px centered title over horizontally extending 700×439px quote cards, with 36px serif quotations and monochrome portraits.

**Transfer:** Keep the visual interruption and the editorial proof format. Use genuine adoption evidence or attributable outcomes rather than fabricating a wall of logos.

**Text style:** `proof-heading` — quadrant 400 · 60px/1 · tracking -0.015em

### Paper-window closing

**Observed:** Printed collage stage fills the background while Closing paper rises from the bottom of the section. Three tiny window dots establish the application metaphor; a large left-aligned 88px promise, short explanation and charcoal Primary button plus Outline button complete the invitation. The alternate Green invitation frame carries a 68px title with Handwritten word insert and two platform actions.

**Transfer:** Restate the benefit in a product-shaped invitation. Match the invitation variant to the page's tone without adding another unrelated visual system.

**Text style:** `closing-display` — quadrant 400 · 88px/0.98 · tracking -0.01em

### Identity footer ending

**Observed:** Four footer columns occupy a 1200px inner width: one short column at left and three grouped at the right, separated by 80px. Footer-heading titles sit above Footer link stacks. A low social-and-copyright row precedes Monumental identity artwork. A thin green full-width strip is the visual terminus.

**Transfer:** Always give the new identity a large final gesture. Use useful navigation and the new wordmark; keep legal utilities visually subordinate rather than making them a second footer.

### Centered feature toolkit

**Only for:** feature landing pages

**Observed:** Centered 48px title and light 24px support lead into three 384px warm-paper demonstration cards. Later chapters alternate the Prompt pill rows, small phase labels in pale yellow, lavender and pink, and paired larger demonstrations with Example cards below.

**Transfer:** Make each chapter demonstrate an action, then show what it enables. Use the moving pills for a range of tasks and the larger panels for depth.

### Enterprise evidence pair

**Only for:** enterprise pages

**Observed:** A two-column heading-and-prose introduction is followed by paired 576px-wide media scenes. The quantified-proof variation places three Stat tiles over water photography beside a serif quote and Outline button. A later Paper band uses one tall white testimonial beside two stacked case-study cards.

**Transfer:** Balance emotional imagery with concrete controls, outcomes and honest attribution; allow denser explanatory material here than on a general landing page.

**Text style:** `enterprise-heading` — quadrant 400 · 54px/1.1 · tracking -0.015em

### Plan selection and comparison

**Only for:** pricing pages

**Observed:** Single-line 68px title and 24px support open above three equal Plan cards. A focused customer quote separates the cards from a 1200px comparison table with 16px outer corners, 0.5px rules, warm-paper category bands, small uppercase category labels and pale green circular inclusion checks. FAQ row sections and resource cards follow.

**Transfer:** Make plan differences scannable before offering exhaustive comparison. Keep the page white and resist assigning each plan a different decorative theme.

**Text style:** `pricing-display` — quadrant 400 · 68px/0.6 · tracking -0.015em

### Culture editorial and roles

**Only for:** recruiting pages

**Observed:** A right-weighted photo collage precedes a 68px serif mission headline with a handwritten insert. Long-form editorial text sits beside a compact job list; later sections pair 48px headings with proof points, a dense portrait matrix, small filter pills and benefit rows. A loose five-column photo gallery leads into a narrower two-column role listing.

**Transfer:** Translate this into a company narrative and authentic people evidence, using role rows with a small emblem, title and location rather than oversized recruitment cards.

**Text style:** `framed-closing-heading` — quadrant 400 · 68px/1 · tracking -0.015em

## Page flow

**Storyline:** Specific human promise → product in use → credible adoption → capability chapters → deeper proof or practical detail → product-shaped invitation → monumental identity.

### Introduce a product through its everyday value

1. **Promise** — Asymmetric opening with a narrow serif promise and tactile product collage.
2. **Product demonstration** — An enhancement explanation and stage-based workflow with a left rail.
3. **Adoption proof** — Oversized audience line, dark identity band and editorial quotations.
4. **Capability chapters** — A large chapter statement followed by repeated wide media and heading-description pairs.
5. **Ecosystem** — A warm-paper chapter with moving integration tiles.
6. **Closing call** — Paper-window invitation over printed artwork, followed by navigation and monumental identity.

**Transfer:** Adapt the number of demonstrations to the product; preserve the shift between sparse editorial statements and concrete product scenes.

### Explain a focused feature through actions and examples

1. **Promise** — Centered headline and action over a pale perspective field of interface cards with a floating prompt.
2. **Demonstration** — Three example scenes, moving task pills and a small phase diagram.
3. **Depth** — Reusable workflow examples paired with author-backed cards.
4. **Social proof** — Customer identities and a masonry wall of native-looking social posts.
5. **Closing call** — Green-framed paper invitation, footer columns and monumental identity.

**Transfer:** Use increasingly specific examples to establish usefulness before social proof. Keep social embeds visually native rather than forcing them into the editorial serif system.

### Help a team evaluate organizational adoption

1. **Promise** — 54px promise and sales action beside a compact conceptual print collage.
2. **Trust** — Warm-paper identity grid followed by security and compliance detail.
3. **Capability depth** — Paired media explanations and outcome tiles over photography.
4. **Objection handling** — Administrative controls, practical proof and a narrow FAQ list.
5. **Customer proof** — Warm-paper case studies with one tall quotation beside stacked stories.
6. **Closing call** — Large paper-window sales invitation over printed artwork, then common identity footer.

**Transfer:** Preserve the quieter headline scale, detailed prose and control explanations while reordering the proof to suit the buyer.

### Invite candidates into a product-minded team

1. **Mission** — Overlapping candid photos above a mission headline with one handwritten word.
2. **Context** — Editorial motivations beside a compact role list.
3. **Momentum and people** — Proof points, team portrait matrix, small filters and benefit rows.
4. **Culture** — Native social proof and a loose candid-photo gallery.
5. **Action** — Grouped job rows, a product invitation and the common large identity footer.

**Transfer:** Use authentic people and workplace evidence, retaining editorial text and compact listings rather than turning the page into a job portal.

### Make purchase options and boundaries understandable

1. **Choice** — Centered promise, short support and three equal subscription cards.
2. **Validation** — A focused customer quote with attribution.
3. **Comparison** — Long category-banded feature table.
4. **Objection handling** — Narrow FAQ list and three small resource cards.
5. **Social proof** — Native social posts and a fading horizontal identity row.
6. **Closing call** — Green-framed invitation followed by the common monumental footer.

**Transfer:** Make the first decision simple and leave exhaustive detail to the comparison; keep the closing benefit-led rather than price-led.

## Writing

Warm, direct and product-literate. It speaks about ordinary working moments with enough specificity to sound useful, mixing matter-of-fact explanation with a little informal wordplay.

**Do not copy:** Do not reuse the brand name, spiral logo, handwritten assets, customer names or logos, quotations, proprietary feature names, funding figures, adoption statistics, prices or product claims. Examples illustrate structure and voice only; replace them with truthful content for the new product.

- **Addressing the reader:** Speak directly to you and your team. Use we for the builders' point of view and the product name when explaining what the tool does.
- **Rhythm:** Headlines are often 2–9 words, occasionally a longer conversational promise. Support is one or two short sentences; detailed enterprise prose can be longer. Commas, contractions and concrete lists keep the language spoken rather than ceremonial.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the tool or transformation and the user's recognizable working situation. | 7–11 words | “The AI notepad for back-to-back meetings”<br>“AI chat that actually understands your work” |
| Supporting line | Short concrete outcomes, then an important distinction. | Two short sentences or one brief paragraph | “Notes, actions and memory.”<br>“Without a meeting bot.” |
| Capability heading | A human benefit expressed in plain language, often with a contrast. | 3–8 words | “Humans in the room, not bots”<br>“Private by default, ready to share” |
| Feature chapter | An everyday invitation or light verb-based wordplay, supported by precise explanation. | 2–6 words | “Ask away”<br>“Stop prompting, start cooking” |
| Primary action | Concrete verb plus platform or low-friction qualifier. | 2–4 words | “Download for free”<br>“Talk to sales” |
| Objection handling | Actual reader questions, not vague themed headings. | 4–12 words | “Do you train on my data?”<br>“Things worth noting” |

**Words and phrasing to use:** you and your team; before, during and after; ready; work; help; notes; what matters; in a few clicks; ask; share

**Avoid:** revolutionary; unlock unprecedented potential; synergize; supercharge everything; enterprise-grade as an unexplained slogan; excessive AI jargon

**Rules:**

- Tie each promise to a recognizable action or setting in the following sentence.
- Explain limitations and privacy in direct questions and concrete answers.
- Use playful language sparingly; a witty chapter title is followed by clear functional copy.
- Keep action labels literal and avoid multiple differently worded buttons for the same action.

## Do's and Don'ts

### Do

- Keep the opening serif at weight 400, 0.93 line height and -0.02em tracking.
- Keep the 56px pill action visually compact next to the oversized display.
- Use 0.5px edges and 8px corners for ordinary marketing cards.
- Stage product detail over warm natural imagery or printed texture, with a clearly readable foreground.
- Give wide feature media a title-and-description row, including the 448px desktop text column.
- Concentrate green in discrete bands or frames while leaving most of the page white.
- Finish with a near-container-width identity artwork rather than another row of promotional cards.
- Keep enterprise proof numerals at 32px inside small paper tiles, paired with a unit-bearing explanation.

### Don't

- Do not set the editorial serif in bold or replace it with an all-caps geometric display face.
- Do not turn every section into a rounded bento grid; preserve long unboxed statements and wide scenes.
- Do not give ordinary cards the deep 50px paper-window shadow.
- Do not make olive the body-text color or paint the entire site green.
- Do not use neon gradients as the default canvas; the strong multicolor treatment belongs inside printed artwork.
- Do not replace physical paper and photo staging with glossy floating 3D cubes.
- Do not apply the pricing title's 0.6 line height to multiline headlines.
- Do not promote small utility or legal controls into a full-width white callout at the page ending.

## Motion and responsive

### Motion

**Observed:**

- Navigation capsule declares background, border and shadow transitions of 0.3s ease-out.
- Announcement and footer links declare .15s cubic-bezier(.4,0,.2,1) transitions.
- Task and logo rows declare linear infinite marquees, including 90s rows and a 30s seamless variant; opposite row directions also occur.
- Large product storytelling includes scroll-linked shrinking, parallax and a headline sliding behind the proof band. Product enhancement text declares a 0.9s ease-in-out color sweep.

**Transfer:**

- Keep task rows and ecosystem rows slow enough to read; use opposing movement only in multirow demonstrations.
- Use the audience headline passing behind the next band as an editorial transition, not as a repeated reveal for every heading.
- For reduced movement, keep the finished product and all text visible, and retain the physical layers as a static composition.

**Unknown:**

- Exact scroll-linked trajectories, trigger ranges for all scenes and complete playback behavior are not specified.

### Responsive

**Observed:**

- Desktop is organized around a 1280px outer container. Declared responsive classes include 768px and 1024px layout changes; wide heading recipes use viewport-relative formulas.
- The core opening declares a single-column grid before its desktop split. Footer columns declare a two-column grid before desktop flex grouping.
- The default paper closing declares narrower side padding and smaller headline sizes on smaller widths; its actions declare a vertical stack before a horizontal row.

**Transfer:**

- On narrow layouts, retain the narrow promise first and put the tactile object beneath it; preserve overlapping scraps but clip decorative overflow.
- Stack the 448px feature description beneath its title and let scenes scale proportionally. Convert three-card rows to a readable vertical sequence.
- Keep the identity artwork fluid at full available width rather than preserving the desktop height.
- Keep comparison-table content aligned; use a horizontally scrollable region if its minimum readable width exceeds the screen.

**Unknown:**

- Rendered mobile compositions and complete breakpoint-specific measurements are unknown; collapse rules beyond the declared patterns are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
