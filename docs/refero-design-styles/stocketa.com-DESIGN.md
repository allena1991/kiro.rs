# Stocketa — prismatic pocket theater

## Overview

An airy, light product presentation pairs a white reading pane with a dreamy pastel stage. Rounded geometric sans typography, rainbow-tinted headlines, frosted floating tiles and a crisp device demonstration make technical software feel personal and easy. The density is low around the promise and more practical through the feature list, ending with an oversized statement softened into colored light.

### Essentials

- A reading sheet beside a persistent product theater: the desktop pane is 634px wide against an 806px stage, with 57.6px inner side padding and 34px right-hand corners.
- The promise wears the rainbow rather than a colored box: 62.4px/1.1, weight 800, -1px tracking, with clipped violet–blue–mint color and a restrained 0.5px shadow.
- Conversion stays soft-spoken: a 46px-high pale blue-gray pill with 100px radius sits beside a smaller unfilled launch link; there is no saturated solid CTA.
- Pastel atmosphere occupies the media half, while the reading half remains predominantly white: low-opacity mint, cyan, lavender and rose light sit behind a sharp, upright product object.
- Tiny frosted satellites make the demonstration a scene: three roughly 98px square tiles with 18px corners, white micrographics, slight rotation and 5px backdrop blur surround the main object. Use abstract capability glyphs when there is no equivalent data.
- The ending becomes a monumental whisper: two weight-800 lines at 3.5vw and 3.65vw lead into a 6.8vw final line, blended over a deliberately blurred product silhouette; a 320px centered note and small maker credit close the reading pane.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Feature violet | `#995bb9` | `--color-violet` | accent, text | Feature glyph and tint source. Titles use brightness(0.5) saturate(0.5), so they read as dark plum rather than bright violet; other feature groups shift subtly toward mint and rose. |
| Powder-blue ending | `#d6e0ef` | `--color-footer-wash` | background | Visible blue fade at the bottom of the white sheet, rgba(132,161,208,0.33) over white. |
| Lavender icon wash | `#f9f6fb` | `--color-icon-wash` | surface | Circular glyph backing, rgba(228,212,237,0.22) over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate action | `#545f7a` | `--color-action-ink` | text, action | Pill label, using rgba(58,71,102,0.87) over white. |
| Misty blue-gray | `#909faf` | `--color-body` | text | Feature descriptions over white; rgba(43,72,103,0.525). |
| Launch-link mist | `#a1acbf` | `--color-link` | link | Secondary launch link, rgba(92,111,144,0.576) over white. |
| Black anchor | `#000000` | `--color-ink` | text | Brand name and base closing slogan; the latter is softened by overlay blending. |
| Hovered slate | `#1b2232` | `--color-hover-ink` | action, text | Pill label on hover. |
| Graphite lead | `#3f4650` | `--color-lead` | text | Visible lead copy over white, using rgba(29,38,48,0.85). |
| Footer mist | `#aab1c2` | `--color-muted` | text, link | Centered closing note and maker links, using rgba(85,99,132,0.5) over white; the blue footer wash subtly deepens it. |
| Frosted blue-gray | `#d5d8da` | `--color-glass` | surface | Floating tile base over the gray stage, rgba(83,116,152,0.07), with a white radial highlight. |
| Atmospheric gray base | `#dfdfdf` | `--color-canvas` | background | Underlying stage canvas, visible through atmospheric light. |
| Pale action wash | `#f1f4f7` | `--color-action-wash` | surface, action | Pill fill, rgba(164,184,204,0.157) over white. |
| White reading sheet | `#ffffff` | `--color-paper` | surface, background | Dominant reading-pane surface and highlights on floating tiles. |

## Typography

- **averta standard** — All marketing text, from the nameplate to the closing statement. Friendly geometric sans with open counters, rounded curves and a sturdy extra-bold display cut. If unavailable, use **Nunito Sans**. Use weights 400–800; retain the tight headline tracking and broad rounded proportions. Font stack: "averta standard", "Nunito Sans", -apple-system, system-ui, Segoe UI, Roboto, Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-final | averta standard | 800 | 97.9px | 1.2 | -0.0031em | size 6.8vw | Very short final line at almost twice the preceding size. |
| hero | averta standard | 800 | 62.4px | 1.1 | -0.016em | fixed | Three-line, left-aligned promise with a clipped multicolor fill. |
| closing-line-emphasis | averta standard | 800 | 52.6px | 1.35 | -0.0057em | size 3.65vw | Second line, slightly larger to equalize visual width. |
| closing-line | averta standard | 800 | 50.4px | 1.35 | -0.006em | size 3.5vw | First line of the blended closing statement. |
| brand | averta standard | 700 | 28px | 1.15 | normal | fixed | Compact nameplate next to the app icon. |
| lead | averta standard | 500 | 27.2px | 1.35 | -0.0184em | fixed | Two-line product explanation below the promise. |
| feature-heading | averta standard | 600 | 19px | 1.25 | -0.0105em | fixed | Compact sentence-case capability titles. |
| body | averta standard | 500 | 17px | 1.35 | -0.006em | fixed | One or two lines of practical explanation per capability. |
| button | averta standard | 500 | 16px | 1.4 | normal | fixed | Centered pill labels. |
| closing-note | averta standard | 400 | 15.2px | 1.4 | normal | fixed | Centered product philosophy paragraphs. |
| credit | averta standard | 500 | 14.4px | 1 | normal | fixed | Small centered maker links. |
| secondary-link | averta standard | 500 | 14.4px | 1.15 | normal | fixed | Small unfilled action alongside the pill. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the headline extra-bold but the support only medium; rounded letterforms provide warmth without a second font.
- Sentence case dominates. The title, lead and feature copy each have their own modest negative tracking; small actions and credits use normal tracking.
- Feature titles are darkened accent colors, not black labels or fully saturated purple. Body text has a delicate embossed white highlight.

## Layout

**Density:** Airy around the opening and ending, with a regular compact reading rhythm in the feature list.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 4.8px | Feature title-to-description gap. | fixed |
| 16px | Feature inset, icon gap and closing paragraph separation. | fixed |
| 20px | Bottom padding of feature rows. | fixed |
| 32px | Space around the small brand row. | fixed |
| 40px | Declared bottom margin of feature rows, combined with -16px top margin on the next row. | fixed |
| 44px | Lead paragraph top and bottom margins. | fixed |
| 57.6px | Reading-pane side padding. | 4vw |
| 128px | Breathing room after the capabilities before the closing note. | fixed |
| 160px | Top margin before the feature list. | fixed |
| 180px | Opening promise offset below the brand area. | fixed |

### Containers and grids

- **Split theater**: 2 columns · gap 0px. At 1440px, a 634px reading sheet occupies about 44% of the width, leaving an 806px product stage. The sheet scrolls while the atmospheric stage and satellites persist.
- **Reading sheet**: side padding 57.6px. 518px inner text width within the desktop sheet; 6px outside inset on top, bottom and left.
- **Feature list**: 1 column · gap 16px. A single column of icon-led rows. Each row has a 44px icon column and flexible text; expanded hit area is 550px wide.
- **Closing note**: max width 320px. Centered narrow paragraphs and maker credit inside the wider reading sheet.

## Corner radius

| Element | Radius |
| --- | --- |
| Reading sheet right corners | 34px |
| Feature rows | 22px |
| Floating tiles | 18px |
| Pills and icon discs | 100px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Reading sheet | `rgba(71, 83, 109, 0.13) 1px 1px 20px 0px, rgba(255, 255, 255, 0.88) 0px 1px 1px 0px inset, rgba(255, 255, 255, 0.53) 1px 0px 0px 0px inset` | A cool soft outer shadow and luminous inset edges separate the long pane from the stage. |
| Floating tile | `rgba(97, 110, 124, 0.114) 0px 4px 15px 0px, rgba(255, 255, 255, 0.39) 0px 1px 1px 0px inset, rgba(34, 50, 94, 0.08) 0px 1px 1px 0px` | Soft depth with a restrained glass edge, not a hard outline. |

### Surfaces

#### Atmospheric canvas · level 0

**Use:** Continuous stage beneath all content.

**CSS:** `background: #dfdfdf`

**Observed:** An almost neutral base carries diffuse moving pastel light, very fine grain and sparse luminous flecks.

**Transfer:** Keep the light field low-contrast enough that a dark device edge and white satellites remain legible.

#### Reading sheet · level 2

**Use:** Long-form marketing content pane.

**CSS:** `background: linear-gradient(0deg, rgb(255, 255, 255) 91%, rgba(255, 255, 255, 0.93), rgba(255, 255, 255, 0.85), rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.72), rgba(255, 255, 255, 0.33)); border-radius: 0px 34px 34px 0px; box-shadow: rgba(71, 83, 109, 0.13) 1px 1px 20px 0px, rgba(255, 255, 255, 0.88) 0px 1px 1px 0px inset, rgba(255, 255, 255, 0.53) 1px 0px 0px 0px inset; backdrop-filter: blur(30px); padding: 16px 57.6px`

**Observed:** White through most of its height, faintly translucent near the decorative header; only the right corners are rounded.

**Transfer:** Use one continuous sheet rather than a stack of separate white cards.

#### Powder-blue footer fade · level 1

**Use:** Bottom 480px of the reading sheet.

**CSS:** `background: linear-gradient(0deg, rgba(132, 161, 208, 0.33), rgba(0, 0, 0, 0)); border-radius: 0px 0px 34px 0px; box-shadow: rgba(255, 255, 255, 0.33) 0px -1px 0.5px 0px inset, rgba(255, 255, 255, 0.33) -1px 0px 0.5px 0px inset`

**Observed:** The last capability flows into a pale blue ending without a hard section boundary.

**Transfer:** Let the color rise gently behind the closing note.

#### Frosted satellite · level 3

**Use:** Small floating capability artifacts around the hero object.

**CSS:** `background-color: rgba(83, 116, 152, 0.07); background-image: radial-gradient(110% 100% at 80% 70%, rgba(255, 255, 255, 0.435) 0%, rgba(255, 255, 255, 0) 100%); border-radius: 18px; backdrop-filter: blur(5px); box-shadow: rgba(97, 110, 124, 0.114) 0px 4px 15px 0px, rgba(255, 255, 255, 0.39) 0px 1px 1px 0px inset, rgba(34, 50, 94, 0.08) 0px 1px 1px 0px`

**Observed:** Translucent square tiles have white labels and a single white line graphic; subtle rotation keeps them weightless.

**Transfer:** Keep these as peripheral artifacts rather than content cards.

## Components

### Brand row

**Use:** Small identity anchor above the opening promise.

**CSS:** `display: grid; grid-template-columns: 32px 1fr; gap: 16px; align-items: center; margin: 32px 0px; color: #000000`

**Text style:** `brand` — averta standard 700 · 28px/1.15

**Observed:** A compact rounded app icon precedes a bold name; there is no multi-link desktop navigation.

**Transfer:** Use a simple original product mark and short name.

### Rainbow promise

**Use:** Primary marketing headline.

**CSS:** `background-image: linear-gradient(-333deg, rgb(96, 235, 140) -100%, rgb(235, 205, 96) -60%, rgb(235, 133, 96) -20%, rgb(159, 96, 235) 20%, rgb(96, 180, 235) 60%, rgb(96, 235, 110) 100%); background-clip: text; color: rgba(0, 0, 0, 0); filter: drop-shadow(rgba(42, 49, 103, 0.85) 0px 0.5px 0px); opacity: 0.88`

**Text style:** `hero` — averta standard 800 · 62.4px/1.1 · tracking -0.016em

**Observed:** Left-aligned and broken into three broad lines, the letters carry the only strong multicolor treatment in the text pane.

**Transfer:** Choose line breaks that keep the promise compact and balanced.

### Soft pill button

**Use:** Low-pressure primary reading action.

**CSS:** `background: rgba(164, 184, 204, 0.157); color: rgba(58, 71, 102, 0.87); border-radius: 100px; padding: 12.8px 29.6px 13.6px; text-align: center; transition: 0.15s ease-out`

**Text style:** `button` — averta standard 500 · 16px/1.4

**Observed:** A text-only pill about 141px wide and 46px high, placed before the secondary launch link.

**States:** Declared: hover color #1b2232; background rgba(197,210,222,0.467); box-shadow rgba(68,76,95,0) 0px 0px 1px 1px inset; focus-visible unknown.

### Launch link

**Use:** Secondary opt-in action next to the pill.

**CSS:** `color: rgba(92, 111, 144, 0.576); padding-bottom: 1px; transition: color 0.25s ease-out`

**Text style:** `secondary-link` — averta standard 500 · 14.4px/1.15

**Observed:** Unboxed muted text aligned with the pill label, with a small horizontal separation.

**States:** Declared: hover color rgba(25,30,40,0.9); focus-visible unknown.

### Feature row

**Use:** Repeated compact capability explanation.

**CSS:** `display: grid; grid-template-columns: 44px 1fr; gap: 16px; padding: 16px 16px 20px; margin: -16px -16px 40px; border-radius: 22px; overflow: hidden; transition: box-shadow 0.3s ease-out`

**Text style:** `body` — averta standard 500 · 17px/1.35 · tracking -0.006em

**Observed:** A circular icon sits beside a heading and short description. The heading uses feature-heading with a 4.8px bottom gap. Rows remain visually open, without permanent filled cards.

**Transfer:** Give each row one user task and one concrete detail; maintain icon alignment when descriptions wrap.

### Icon disc

**Use:** Small capability markers in the feature list.

**CSS:** `display: grid; place-items: center; width: 44px; height: 44px; border-radius: 100px; background: rgba(228, 212, 237, 0.22); color: #995bb9`

**Observed:** A 26px glyph sits at the center. Tint families change across the list, while titles remain darkened.

**Transfer:** Use a single consistent family of simple capability glyphs.

### Floating artifact

**Use:** Decorative product-adjacent proof fragment.

**CSS:** `width: 98px; height: 98px; border-radius: 18px; transform: rotate(-10deg); color: #ffffff; backdrop-filter: blur(5px)`

**Observed:** Uses Frosted satellite. Three artifacts sit at loose upper-left, right-middle and lower-left positions around the main object, each with a short label and a simple line graph.

**Transfer:** Replace graph content with a small white workflow trace, metric or schematic appropriate to the product.

### Maker credit

**Use:** Minimal footer navigation.

**CSS:** `color: rgba(85, 99, 132, 0.5); text-align: center; text-shadow: rgba(255, 255, 255, 0.75) 0px 1px 0px; transition: 0.25s ease-in-out`

**Text style:** `credit` — averta standard 500 · 14.4px/1

**Observed:** Two short links separated by a small connective word form a single centered line, well below the closing note.

**States:** Declared: hover color rgba(47,66,85,0.7); focus-visible unknown.

## Imagery and graphics

### Upright product theater

**Use:** Dominant demonstration beside the reading sheet.

**Observed:** A crisp dark-edged phone stands vertically on a pale atmospheric background, about 326px wide and roughly 660px tall in the desktop scene. The bright interface is the focus, not a photographic environment. Additional screen states follow the capability narrative; a softened secondary silhouette gives depth.

**Transfer:** Use an authentic interface in a restrained device frame. For non-mobile products, use a similarly upright or compact floating panel with a dark edge and bright surface, preserving a dominant central object and generous surrounding air.

### Pastel light and grain

**Use:** Signature atmospheric backing across the stage, strengthening at the ending.

**Observed:** Broad mint, cyan, lavender and rose fields merge without visible geometric edges. Fine grain and faint scattered luminous specks prevent a sterile flat gradient; the opening is subdued and the ending more chromatic.

**Transfer:** Recreate the light field even without product artwork; use a simple translucent product-shaped panel as the central object.

**Build:** Layer oversized elliptical radial gradients over the gray canvas: mint rgba(105,201,102,0.4), cyan rgba(39,187,219,0.33), violet rgba(139,71,206,0.2), and rose rgba(218,64,134,0.1). Spread them across opposing stage corners, blur their boundaries by about 80px, and add an SVG turbulence layer with soft-light blending at low opacity. Add sparse tiny white flecks. Match the soft glow; exact stops are not essential.

### Header contour veil

**Use:** Decorative top of the reading sheet.

**Observed:** Fine parallel flowing contours sweep from the upper edge down toward the brand row and then dissolve into white. Their gray-violet strokes are extremely faint, with a mint-to-lilac wash behind them.

**Transfer:** Keep this small topographic flourish above the promise, not behind paragraph text.

**Build:** Draw roughly 25–35 open SVG Bézier curves across the sheet width, offset vertically by about 8px, bowing downward near the middle. Use a 0.5px gray-violet stroke at low opacity and a vertical fade mask over the lower edge. Back with the pastel radial field at about 0.33 opacity.

### Pastel brush highlight

**Use:** Behind the first line of the lead sentence.

**Observed:** A thin, irregular horizontal brush swipe in pale mint, cyan and lilac sits behind dark text; the second line remains mostly unpainted.

**Transfer:** Use one lightly textured swash to emphasize the product explanation without making it a badge.

**Build:** Place an SVG irregular flattened path behind the first line, about 502px wide and 36px high, with feathered irregular edges and a very low-opacity mint-to-violet linear gradient. Keep text above the mark.

### Defocused closing scene

**Use:** Signature final visual payoff.

**Observed:** The phone becomes a heavily blurred silhouette beneath the centered three-line closing slogan. Small pale product-related symbols drift diagonally through the scene while the frosted satellite tiles remain clearer.

**Transfer:** Blur the same hero object rather than introducing unrelated closing artwork. Use a few original symbols related to the new product.

**Build:** Reuse the hero object behind the closing text with about 10px blur and reduced contrast. Set the slogan wrapper to mix-blend-mode: overlay and add a 1px translucent white text highlight. Scatter a handful of 20–30px pale glyphs on a diagonal below the text; leave most of the stage empty.

### Icons

**Observed:** Capability icons are predominantly filled 26px SVG glyphs inside 44px tinted circles; one combines fill with a 2px stroke. Their hues shift with the capability group. Floating artifacts use white miniature line drawings.

**Transfer:** Use simple recognisable glyphs of consistent optical weight; reserve delicate white traces for the atmospheric satellites.

## Section recipes

How recurring sections are built.

### First screen: Split promise and demonstration

**Observed:** The first 900px show a white Reading sheet on the left, about 44% of the desktop width, and a full-height atmospheric product stage on the right. Back-to-front layers are pastel light and grain, the sheet and contour veil, Brand row, Rainbow promise and lead with brush highlight, then the sharp device and three Floating artifacts. The small brand row sits near the top, followed by a large breathing space before the three-line 62.4px promise. The 27.2px lead sits 44px below it; Soft pill button and Launch link form a restrained action row. The upright device fills most of the stage height and is centered within its half. The first feature row begins near the bottom of the viewport; the rest of the capabilities and closing material continue below.

**Transfer:** Keep the split between a readable promise and a singular product object. Without finished product media, construct a convincing original interface panel with the same upright emphasis, soft lighting and satellites. More focused landing pages can shorten the capability list but retain this opening scale relationship.

**Avoid:** Do not replace the composition with a centered headline above a wide dashboard or fill the whole first screen with a rainbow gradient.

**Text style:** `hero` — averta standard 800 · 62.4px/1.1 · tracking -0.016em

### Capability rail

**Observed:** Feature row repeats down the continuous Reading sheet in one column. Each pairs an Icon disc with feature-heading and body. The 44px icon column, 16px gap and 4.8px title gap stay stable. The right stage changes product views while the left rail remains calm and readable.

**Transfer:** Group a different product's tasks into concise icon-led explanations. Let the adjacent demonstration illustrate the narrative without turning every feature into a separate full-width section.

**Text style:** `feature-heading` — averta standard 600 · 19px/1.25 · tracking -0.0105em

### Monumental blended ending

**Observed:** The last capabilities flow into Powder-blue footer fade. Two centered closing-note paragraphs occupy a 320px measure, followed well below by Maker credit. In the stage, Defocused closing scene carries two short centered action statements and a much larger concluding line. The upper lines use closing-line and closing-line-emphasis; the final uses closing-final. There is no large final signup box, link directory or high-contrast footer band.

**Transfer:** Close with a succinct distillation of the product's promise, not another sales paragraph. Preserve the dramatic scale change and blurred-object backdrop even if this device appears elsewhere in the page.

**Text style:** `closing-final` — averta standard 800 · 97.9px/1.2 · tracking -0.0031em

## Page flow

**Storyline:** Ease-of-use promise → focused product demonstration → practical capability rail → philosophy of restraint → oversized distillation and maker credit.

### Introduce a focused software product through both its design and its everyday usefulness

1. **Promise** — A three-line rainbow headline names a familiar task and reframes it as easy; a short lead and two understated actions follow.
2. **Product demonstration** — A sharp upright device on a pastel stage makes the proposition tangible.
3. **Capability chapters** — An icon-led reading rail provides concrete tasks beside changing interface views.
4. **Positioning** — A narrow centered note explains the value of doing fewer things well.
5. **Closing statement** — A three-line monumental slogan overlays a blurred version of the product, with minimal maker links closing the sheet.

**Transfer:** Adapt the number of capabilities and the placement of the closing device to the new narrative. Keep the movement from simple promise to practical detail to an emotionally concise ending.

## Writing

Friendly, design-conscious and opinionated about simplicity. The product is explained through everyday actions rather than enterprise jargon, with understated confidence instead of urgency.

**Do not copy:** Do not reuse Stocketa or Stammy names, logo artwork, stock symbols, interface data, original claims about privacy or coverage, or the exact brand slogan as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use your and you for practical tasks, the product name for the introduction, and occasional conversational first-person plural reassurance.
- **Rhythm:** Headlines are brief sentence-case statements with periods; feature titles are short verb-led phrases without punctuation. Descriptions are generally one sentence, and the ending uses short repeated fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A familiar task followed by a plain claim of ease. | 8–12 words | “Checking your stocks & crypto should be easy.” |
| Lead | Product name plus a design-minded benefit in one sentence. | 12–18 words | “[Brand] is the most elegant way to keep an eye on your investments.” |
| Capability title | An action and its object, or a compact benefit. | 2–4 words | “Track your investments”<br>“Privacy first” |
| Capability explanation | Name the interaction, then a concrete detail that helps the reader picture it. | 12–22 words | “Dive into individual transactions with per-transaction gain/loss stats.” |
| Action | Low-pressure invitation or a plain opt-in outcome. | 2–5 words | “Read more”<br>“Get notified at launch” |
| Closing statement | Two short action sentences, followed by a still shorter expression of sufficiency. | 2–3 words per line | “Watch stocks.”<br>“Track holdings.”<br>“That's it.” |

**Words and phrasing to use:** easy; keep an eye on; tap; your; a few things well; simplicity; customize

**Avoid:** revolutionary; synergy; enterprise-grade; unlock limitless potential; act now; all-in-one platform

**Rules:**

- Make capability descriptions operational: say what the user can tap, add, import or change.
- Use contractions and occasional short questions to sound approachable.
- Reserve broad design opinions for the closing note; keep feature copy specific.
- Let the final statement compress the promise rather than introduce a new claim.

## Do's and Don'ts

### Do

- Maintain the 44% reading-pane / 56% stage balance on wide desktop layouts.
- Use weight 800 with 1.1 line height for the primary promise.
- Keep feature icons at 26px inside 44px circular backings.
- Use 16px icon-to-text gaps and 4.8px title-to-body gaps.
- Stage three frosted artifacts with 18px corners around one dominant product object.
- Keep closing paragraphs centered within 320px.
- Use the 6.8vw final line as a deliberate contrast to the roughly 3.5vw preceding lines.

### Don't

- Do not make the primary button black or neon; its fill is a very pale translucent blue-gray.
- Do not round all sheet corners equally; the desktop silhouette uses 34px right-hand corners.
- Do not turn the feature rail into a three-column card grid.
- Do not apply the rainbow treatment to every feature heading; keep those darkened and readable.
- Do not use heavy opaque borders on the floating glass tiles.
- Do not substitute stock photography for the focused interface object.
- Do not add an oversized multi-column link directory after the maker credit.

## Motion and responsive

### Motion

**Observed:**

- Pill transition is 0.15s ease-out; the launch link transitions color over 0.25s ease-out and maker links use 0.25s ease-in-out.
- Feature rows declare box-shadow 0.3s ease-out and radial pointer-position light layers.
- Floating artifacts declare 0.6s entrances followed by looping paths lasting 12s, 19s and 15s. The closing lines declare a 2s ease-out entrance after a 0.2s delay.
- The stage persists across the scrolling feature rail, with a clear product view near the opening and a defocused silhouette at the ending.

**Transfer:**

- Keep slow floating motion peripheral to the readable content; reserve the strongest visual transformation for the clear-to-blurred closing scene.

**Unknown:**

- Exact scroll trigger thresholds and continuous animation paths are not specified.
- Focus-visible and active treatments are unknown.

### Responsive

**Observed:**

- Desktop layout is documented at 1440px wide. Declared CSS includes breakpoints at 355px, 400px, 450px, 460px, 500px, 550px, 560px, 600px, 850px, 900px, 1100px, 1200px, 1250px, 1450px and 1460px.
- Reading-sheet side padding follows 4vw. The three closing lines follow 3.5vw, 3.65vw and 6.8vw respectively.

**Transfer:**

- On narrow screens, prioritize a legible promise and product object rather than compressing both desktop halves. Stack the sheet and stage when necessary, retaining the frosted satellites and the clear-to-defocused visual relationship.
- Keep the 44px icon discs and one-column feature structure; reduce surrounding stage space before shrinking the body text.

**Unknown:**

- Exact mobile stacking order, device scale and fixed-position behavior are unknown; the stacking guidance is a recommended adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
