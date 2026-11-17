# Cap — cloudlit software craft

## Overview

An airy, light software style with a surprisingly tactile, almost desktop-native finish. Cool white and misty blue surroundings frame warm cloud illustrations, luminous controls and expansive interface demonstrations. Regular sans-serif headlines meet literary serif explanations and occasional tiny mono markings, making capable technical products feel approachable rather than corporate.

### Essentials

- A plainspoken sans headline gets a handwritten-feeling editorial turn: the opening pairs Instrument Sans 60px/0.98 at weight 400 with Source Serif 4 italic 63.6px/0.98, rather than making the whole headline bold.
- The promise floats in a sky, not a flat banner: a 660px cloudscape inside 24px rounded top corners fades from blue into #edf1f6, with centered copy and the top of a substantial product object visible within the first 900px.
- Conversion controls feel like little pieces of native software: the primary is 48px high with 12px corners, a pale blue vertical gradient, inset highlights and a blue underglow; its white secondary has 10px corners and a #d3dce6 edge.
- Most of the page stays cool and nearly colorless: #f8fafc surrounds white panels, while blue, purple, mint and amber are concentrated in chapter badges, tiny icon tiles and demonstration backings, not whole saturated sections.
- Product proof is staged as an object with depth: 1120px-wide demonstrations use 28px outer corners, restrained hairline shadows and smaller floating interface windows. Use a constructed workflow scene if a product has no polished interface to show.
- The ending expands instead of shouting: a 78px/0.98 regular closing line sits in a 900px centered measure, followed by a gray directory footer with a monumental 1300px brand-symbol watermark at 0.05 opacity, cut off by the lower edge.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Distant blue | `#a3bfea` | `--color-sky-top` | background | Top of the atmospheric sky gradient. |
| Cloud blue | `#c8dbf4` | `--color-sky-mid` | background | Middle sky gradient stop. |
| Horizon haze | `#e2eaf5` | `--color-sky-low` | background | Transition from blue sky to mist. |
| Button highlight | `#f5fafe` | `--color-button-top` | action | Top of luminous primary controls. |
| Button pearl | `#e3effb` | `--color-button-mid` | action | Middle of primary control gradient. |
| Button blue | `#cfe2f6` | `--color-button-base` | action | Bottom of primary control gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Chapter violet | `#6d28d9` | `--color-purple` | accent, text | Editing chapter labels and selected controls. |
| Chapter emerald | `#047857` | `--color-green` | accent, text | Image-workflow chapter labels. |
| Chapter ochre | `#b45309` | `--color-amber` | accent, text | AI-workflow chapter emphasis. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White porcelain | `#ffffff` | `--color-white` | surface, background, text | Cards, secondary actions and outer page surround. |
| Cool canvas | `#f8fafc` | `--color-canvas` | background, surface | Long rounded marketing canvas. |
| Directory gray | `#f2f2f2` | `--color-footer` | background | Footer outside the rounded content canvas. |
| Sky mist | `#edf1f6` | `--color-mist` | background, surface | Lower sky, editorial opening field and subdued hover fills. |
| Cool hairline | `#e1e7ee` | `--color-rule` | border | FAQ, timeline and comparison separators. |
| Control outline | `#d3dce6` | `--color-control-edge` | border | White secondary button outline. |
| Directory links | `#838383` | `--color-directory-link` | link, text | Muted footer link lists. |
| Muted explanation | `#646566` | `--color-muted` | text | Visible result of rgba(17,17,17,0.64) over the cool canvas; capability descriptions. |
| Soft reading ink | `#454647` | `--color-body` | text | Visible result of rgba(17,17,17,0.78) over the cool canvas; introductory serif text. |
| Directory headings | `#202020` | `--color-directory-ink` | text, action | Footer headings and dark account buttons. |
| Near-black ink | `#111111` | `--color-ink` | text, background | Headlines and strong text; also dark announcement capsules. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and company-story pages | Frosted blue | `#e4f0fb` | `--color-pastel-blue` | surface | Recommended-plan rim and company-story gradient cards. |
| company-story pages | Lilac paper | `#efe9fb` | `--color-pastel-violet` | surface | Company-story multicolor card base. |
| company-story pages | Mint paper | `#e5f3ec` | `--color-pastel-green` | surface | Company-story multicolor card base. |
| company-story pages | Apricot paper | `#f9f0e2` | `--color-pastel-cream` | surface | Company-story multicolor card base. |

## Typography

- **Instrument Sans** — Marketing headlines, capability lists and conversion controls. Open, contemporary sans with regular-weight display forms and a compact, tightly tracked heading rhythm. Font stack: "Instrument Sans", ui-sans-serif, system-ui, sans-serif.
- **Source Serif 4** — Supporting paragraphs, customer quotations and italic opening emphasis. Literary serif with fine detail; light text and a more expressive regular italic. Font stack: "Source Serif 4", Georgia, serif.
- **DM Mono** — Small chronological dates, technical commands and occasional uppercase metadata. Compact monospaced annotations with widely tracked capitals. Font stack: "DM Mono", ui-monospace, monospace.
- **defaultFont** — Navigation and directory footer. Neutral sans-serif utility typography, less tightly tracked than marketing display text. If unavailable, use **Inter**. Use 400–500 for navigation and directory text. Font stack: "defaultFont", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing | Instrument Sans | 400 | 78px | 0.98 | -0.03em | size clamp(44px, 6.4vw, 78px) | Expansive final invitation. |
| display-italic | Source Serif 4 | 400 italic | 63.6px | 0.98 | normal | fixed | Short second-line audience or benefit phrase paired with display. |
| display | Instrument Sans | 400 | 60px | 0.98 | normal | fixed | Main opening statement; let a complete thought occupy a broad centered line. |
| heading-proof | Instrument Sans | 400 | 56px | 1 | -0.03em | size clamp(38px, 5vw, 56px) | Broad social proof and general section statements. |
| heading | Instrument Sans | 400 | 54px | 1 | -0.03em | size clamp(34px, 4.6vw, 54px) | Default capability chapter headline. |
| heading-split | Instrument Sans | 400 | 48px | 1 | -0.03em | size clamp(34px, 4vw, 48px) | Left-aligned split sections and FAQ leads. |
| footer-heading | defaultFont | 500 | 20px | 1.4 | normal | fixed | Directory column titles. |
| intro | Source Serif 4 | 300 | 19px | 1.5 | -0.01em | fixed | Opening explanation in a narrow centered measure. |
| question | Instrument Sans | 400 | 19px | 1.5 | -0.02em | fixed | FAQ summary rows. |
| body | Source Serif 4 | 300 | 18px | 1.5 | -0.01em | fixed | Capability supporting paragraphs, usually below a sans heading. |
| action-primary | Instrument Sans | 500 | 16px | 24px | normal | fixed | Primary conversion labels. |
| action-secondary | Instrument Sans | 400 | 16px | 24px | normal | fixed | White supporting action labels. |
| quote | Source Serif 4 | 300 | 15.5px | 1.55 | -0.01em | fixed | Customer quotation cards; preserve natural paragraph lengths. |
| answer | Source Serif 4 | 300 | 15.5px | 1.6 | -0.01em | fixed | Expanded FAQ explanations. |
| feature-title | Instrument Sans | 500 | 15px | 1.55 | normal | fixed | Inline capability label before the lighter explanation. |
| feature-copy | Instrument Sans | 400 | 15px | 1.55 | normal | fixed | Small capability explanations and demonstration captions. |
| eyebrow | Instrument Sans | 500 | 14px | 24px | -0.01em | fixed | Colored chapter label within a white luminous capsule. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company-story pages | story-display | Instrument Sans | 400 | 84px | 0.98 | -0.03em | size clamp(42px, 6.4vw, 84px) | Company-story opening statement. |
| pricing pages | pricing-display | Instrument Sans | 400 | 80px | 0.98 | -0.03em | size clamp(42px, 6.2vw, 80px) | Single centered pricing-page title. |
| pricing sections | price | Instrument Sans | 400 | 46px | 1 | -0.03em | fixed | Plan numerals, with billing qualifier much smaller beside the baseline. |
| company-story pages | story-card-heading | Instrument Sans | 400 | 26px | 1.1 | -0.02em | fixed | Multicolor editorial card title. |
| company-story pages | statement-quote | Source Serif 4 | 300 | 26px | 1.35 | -0.01em | fixed | One prominent editorial quotation alongside a small priority grid. |
| timelines | date | DM Mono | 400 | 12px | 1 | 0.05em, uppercase | fixed | Narrow date rail beside chronological entries. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep large sans headings at 400; emphasis comes from tight -0.03em tracking and compact line height, not heavy weight.
- Pair the plain sans statement with light serif explanation. The italic is an opening flourish, not the default style for every heading.
- The introductory serif is 19px; ordinary chapter support is 18px; dense quotations and answers are 15.5px. Small capability lists switch back to sans.
- The short connector before the opening italic word uses -0.025em tracking; the emphasized final word retains normal tracking.

## Layout

**Density:** Airy at section scale, compact inside controls and supporting grids; large product scenes receive more room than text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and compact local stacks. |
| 12px | Paired actions and tightly grouped cards. |
| 16px | Masonry gutters and editorial card-grid gaps. |
| 20px | Default heading-to-support gap and section side padding. |
| 24px | Badge-to-heading gap, testimonial padding and grid row gaps. |
| 32px | Plan and editorial card padding; capability-grid top inset. |
| 36px | Support-to-action gap. |
| 40px | Horizontal gaps in three- and four-column capability grids. |
| 56px | Heading group to testimonial grid; opening top inset. |
| 64px | Split-demo gap and separation before supporting feature lists. |
| 80px | FAQ and timeline column gap; directory top padding. |
| 112px | Social proof, pricing and editorial section vertical padding. |
| 128px | Default capability chapter vertical padding. |
| 144px | Closing invitation top padding. |
| 160px | Closing invitation bottom padding. |

### Containers and grids

- **outer-shell**: side padding 32px. Default desktop marketing page has a white surround and a rounded inner canvas; navigation occupies the first 76px. Pricing and company-story variants use 16px side surround.
- **content**: max width 1120px · side padding 20px. Centered demonstration and capability container.
- **heading-measure**: max width 760px. Centered chapter titles; support narrows further to 560–640px.
- **opening-measure**: max width 1020px. Broad centered headline group; intro paragraph has a 660px measure.
- **proof-grid**: max width 1200px · 3 columns · gap 16px. Unequal-height customer cards in masonry columns.
- **capability-grid**: 3 columns · gap 40px. Open, unboxed capability items; row gaps are 24px, with a fourth column for short technical assurances.
- **split-demo**: max width 1120px · 2 columns · gap 64px. Text takes 0.85 shares and media 1.15 shares; vertically centered.
- **split-list**: max width 1100px · 2 columns · gap 80px. A 340px heading rail beside a 680px FAQ or chronology list.
- **closing-measure**: max width 900px. Centered final invitation and paired actions.
- **footer-directory**: max width 1536px · 5 columns · gap 32px. Five narrow link columns beside a separate brand-summary rail, with 64px between the rail and directory.
- **editorial-grid** (only for company-story pages): max width 1200px · 2 columns · gap 16px. Broad multicolor story cards.
- **plan-grid** (only for pricing pages): max width 1120px · 3 columns · gap 16px. Equal-height plan cards that overlap the bottom of the sky header by 152px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-controls | 12px |
|  | secondary-controls | 10px |
|  | chapter-capsules | 9999px (pill) |
|  | testimonial-cards | 14px |
|  | standard-cards | 20px |
|  | page-canvas | 24px |
|  | demonstration-stage | 28px |
| pricing pages | pricing-cards | 22px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| panel-depth | `0 0 0 1px rgba(17,17,17,0.06), 0 1px 2px rgba(17,17,17,0.03), 0 30px 60px -40px rgba(17,24,39,0.25)` | Broad white demonstration stages. |
| card-hairline | `0 0 0 1px rgba(17,17,17,0.05)` | Customer cards; an edge, not a floating drop shadow. |
| button-luminosity | `inset 0 0 0 1px rgba(63,127,205,0.65), inset 0 2px 3px -1px rgba(255,255,255,0.8), inset 0 -1px 1px rgba(61,119,194,0.2), 0 1px 2px rgba(61,119,194,0.2), 0 10px 24px -10px rgba(120,178,240,0.55)` | Primary conversion controls. |

### Surfaces

#### Rounded cool canvas · level 0

**Use:** The main continuous page surface, inside a white surround.

**CSS:** `background: #f8fafc; border-radius: 24px; box-shadow: 0 0 0 1px rgba(17,17,17,0.043)`

**Observed:** A very fine monochrome grain softens the nearly white field; it is not visibly speckled.

**Transfer:** Keep the same cool, continuous material through several chapters instead of alternating heavy colored bands.

#### Cloud sky · level 0

**Use:** Default landing-page opening backdrop.

**CSS:** `background: radial-gradient(80% 42% at 50% 74%, rgba(255,240,224,0.5) 0%, rgba(255,240,224,0) 72%), linear-gradient(#a3bfea 0%, #c8dbf4 34%, #e2eaf5 64%, #edf1f6 92%); border-radius: 24px 24px 0px 0px; overflow: hidden`

**Observed:** Soft volumetric clouds sit at several depths around an open central reading zone. Warm upper-right light counters the blue.

**Transfer:** Retain an atmospheric sky and restrained warm light even when the product has no natural photographic setting.

#### Demonstration porcelain · level 1

**Use:** Large media stages under capability headings.

**CSS:** `background: #ffffff; border-radius: 28px; box-shadow: 0 0 0 1px rgba(17,17,17,0.06), 0 1px 2px rgba(17,17,17,0.03), 0 30px 60px -40px rgba(17,24,39,0.25)`

**Observed:** Pale chapter-tinted light washes across the upper backing, fading to white below; inner interface windows sit above it.

**Transfer:** Let the stage carry color while the surrounding page remains cool neutral.

#### Directory ground · level 0

**Use:** Footer outside the rounded marketing canvas.

**CSS:** `background: #f2f2f2; border-top: 1px solid rgba(232,232,232,1); overflow: hidden; position: relative`

**Observed:** A pale overscale emblem sits behind the lower links and legal rail.

**Transfer:** Keep this as a distinct utilitarian ending, with the symbol behind rather than replacing readable content.

#### Editorial aurora · level 1

**Only for:** company-story pages

**Use:** Belief and principle cards.

**CSS:** `background: radial-gradient(92% 95% at 6% 6%, rgba(143,193,247,1) 0%, rgba(143,193,247,0) 66%), radial-gradient(70% 78% at 96% 2%, rgba(205,235,244,1) 0%, rgba(205,235,244,0) 60%), radial-gradient(82% 76% at 92% 96%, rgba(221,215,248,1) 0%, rgba(221,215,248,0) 62%), radial-gradient(92% 88% at 24% 100%, rgba(175,214,248,1) 0%, rgba(175,214,248,0) 70%), #e4f0fb; border-radius: 20px; padding: 32px`

**Observed:** Each card varies the corner pools: blue/cyan/lilac, lilac/pink/mint, mint/cream, or pale peach/apricot. Text remains dark, never reversed.

**Transfer:** Use adjacent pastel pools and fine grain for editorial stories, not as a general replacement for white feature lists.

## Components

### Primary button

**Use:** The preferred landing-page conversion control.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 24px; border-radius: 12px; background: linear-gradient(#f5fafe 0%, #e3effb 52%, #cfe2f6 100%); color: #111111; box-shadow: inset 0 0 0 1px rgba(63,127,205,0.65), inset 0 2px 3px -1px rgba(255,255,255,0.8), inset 0 -1px 1px rgba(61,119,194,0.2), 0 1px 2px rgba(61,119,194,0.2), 0 10px 24px -10px rgba(120,178,240,0.55); text-shadow: 0px 1px 0px rgba(255,255,255,0.45)`

**Text style:** `action-primary` — Instrument Sans 500 · 16px/24px

**Observed:** A small platform glyph may precede the label. The default is pale blue, not the dark account-navigation treatment.

**States:** Declared: hover filter has no resolved value; focus-visible outline-offset 2px with transparent 2px outline and retained inset shadows; active transform resolves to identity.

### Secondary button

**Use:** A supporting action beside the luminous primary.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 24px; gap: 10px; border-radius: 10px; border: 1px solid #d3dce6; background: #ffffff; color: #111111`

**Text style:** `action-secondary` — Instrument Sans 400 · 16px/24px

**Observed:** A small down-arrow can sit in a pale circular backing after the label; other instances are plain text.

**States:** Declared: hover background-color #edf1f6; focus-visible outline-offset 2px with transparent 2px outline.

### Chapter capsule

**Use:** A compact label introducing a capability chapter.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 4px 14px 4px 4px; border-radius: 9999px; background: #ffffff; color: #047857; box-shadow: 0 0 0 1px rgba(16,185,129,0.22), 0 8px 20px -12px rgba(16,185,129,0.7)`

**Text style:** `eyebrow` — Instrument Sans 500 · 14px/24px · tracking -0.01em

**Observed:** A 24px circular gradient icon medallion leads the label. Blue, violet, amber and slate variants identify other chapters, with matching low glows.

**Transfer:** Choose a stable hue per capability family and reuse it in the nearby icon tiles and selected demonstration control.

### Feature item

**Use:** Small supporting capability descriptions beneath a broad demonstration.

**CSS:** `font-size: 15px; line-height: 1.55; color: rgba(17,17,17,0.64)`

**Text style:** `feature-copy` — Instrument Sans 400 · 15px/1.55

**Observed:** A 32px pastel tile with 10px corners sits above an inline medium-weight label and regular explanation. Items are unboxed; the grid as a whole may have a top rule.

**Transfer:** Keep each description to a short practical explanation rather than giving every feature a separate card.

### Customer card

**Use:** Human proof in a variable-height masonry grid.

**CSS:** `display: block; background: #ffffff; border-radius: 14px; padding: 24px; margin-bottom: 16px; box-shadow: 0 0 0 1px rgba(17,17,17,0.05)`

**Text style:** `quote` — Source Serif 4 300 · 15.5px/1.55 · tracking -0.01em

**Observed:** Serif quotation first, then a small round avatar with sans name and muted handle. Cards retain unequal heights.

**Transfer:** Use authentic, specific customer wording with natural paragraph breaks.

### FAQ row

**Use:** Objection handling beside a short heading rail.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 24px 0px; color: rgba(17,17,17,0.75)`

**Text style:** `question` — Instrument Sans 400 · 19px/1.5 · tracking -0.02em

**Observed:** Native disclosure rows sit between #e1e7ee rules. The right-hand plus is housed in a 32px pale circle. Expanded serif answers use the answer recipe, with 40px right inset and 28px bottom padding.

**States:** Declared: hover color #111111; focus-visible outline-offset 2px with transparent 2px outline.

### Directory columns

**Use:** A dense but visually subordinate footer navigation.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); column-gap: 32px; row-gap: 40px`

**Text style:** `footer-heading` — defaultFont 500 · 20px/1.4

**Observed:** Headings have 8px bottom inset; muted 16px links form narrow wrapping lists. A separate summary rail carries a small logo, 14px description and social icons. A lower rule separates compliance and legal information.

**Transfer:** Adapt column categories to actual navigation and keep the low-contrast monumental watermark behind them.

### Navigation bar

**Use:** Persistent utility navigation with restrained account actions.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 0px 32px; gap: 24px; height: 76px`

**Text style:** `action-secondary` — Instrument Sans 400 · 16px/24px

**Observed:** Small logo at left, close-spaced utility links and dropdown chevrons through the middle, repository proof and outlined Login/dark Sign Up at right. Utility text uses the legacy sans at 15.5px, weight 500. On scroll the bar becomes a centered white rounded floating strip, about 1200px wide.

**Transfer:** Use fewer real destinations when needed; keep the account controls smaller and darker than the main conversion pair.

### Plan card

**Only for:** pricing pages

**Use:** Detailed paid-tier comparison.

**CSS:** `display: flex; flex-direction: column; padding: 32px; border-radius: 22px; background: #ffffff; box-shadow: 0 0 0 1px rgba(17,17,17,0.06), 0 24px 48px -32px rgba(17,17,17,0.28)`

**Text style:** `price` — Instrument Sans 400 · 46px/1 · tracking -0.03em

**Observed:** Title and small status badge lead into serif description, price, billing switch, quantity controls, full-width action and a checkmarked list. The recommended plan has a 6px pastel blue-to-lilac rim around an 18px inner white card. Check circles take their plan hue.

**Transfer:** Make billing units explicit; preserve generous internal spacing rather than compressing every tier into a short tile.

### Chronology row

**Only for:** company-story timelines

**Use:** A compact dated narrative alongside an editorial heading.

**CSS:** `display: grid; grid-template-columns: 120px minmax(0px, 1fr) auto; gap: 24px; padding: 24px 0px; align-items: start`

**Text style:** `date` — DM Mono 400 · 12px/1 · tracking 0.05em · uppercase

**Observed:** Mono date at left, sans event title over a light serif explanation, and a small northeast arrow in a pale circle at right; each row has a cool top rule.

**Transfer:** Use dated releases, milestones or decisions appropriate to the new product.

## Imagery and graphics

### Clouds and sun haze

**Use:** Signature atmospheric opening device.

**Observed:** Softly shaded, rounded cloud clusters occupy the sides and lower horizon, with smaller distant wisps above. The central headline remains black against a clear reading zone. Lighting is warm from the upper right; clouds are blue-gray beneath and cream-white above.

**Transfer:** Recreate an actual soft cloudscape rather than a generic two-color gradient. The minimum version is a handful of softly lit SVG cloud clusters layered over the sky surface.

**Build:** Use the Cloud sky surface as the base. Construct 6–8 SVG clusters from overlapping irregular ellipses, wider than tall, with white/cream tops and rgba(52,80,122,0.14) shaded undersides. Blur edges lightly and reduce distant clusters to roughly half opacity. Put broad translucent white mist near the lower third; add a roughly 1032px radial sun glow at upper right using rgba(255,248,236,0.95), rgba(255,227,196,0.5) and transparent. Fade the whole scene into #edf1f6 at the bottom.

### Desktop product object

**Use:** The large opening proof object extending below the fold.

**Observed:** A dark rounded laptop bezel and metallic base frame a bright illustrated desktop: a sunny coastal city, water, distant bridge and warm clouds. The product's small native recording window floats centrally. It is a substantial object, roughly 1120px across, with a soft blue halo behind.

**Transfer:** Show the new product working in a believable polished environment. Without device artwork, use a dark rounded desktop frame, a carefully illustrated or softly colored workspace background and one legible key interface panel.

**Build:** Center a wide dark frame with approximately 30px corners, an inner screen inset and a thin gray metallic base below. Place an approximately 813px by 448px #bfdcfc light ellipse behind it at 0.55 opacity and blur 64px. Keep the frame's lower shadow soft and broad.

### Layered workflow demonstration

**Use:** Large chapter-level product proof scenes.

**Observed:** Interface windows float above pale blue, violet, mint or warm apricot backings. An example scene pairs a large recording playback window with a smaller summary panel; another adds camera portrait circles and a miniature share preview to a landscape-backed desktop. The composition is much larger than the accompanying text.

**Transfer:** Construct one understandable before-to-after or input-to-result workflow, using two or three panels and a small status control. If there is no interface, show a real output artifact in the same luminous stage rather than stock photography.

**Build:** Use Demonstration porcelain at up to 1120px wide. Add a broad chapter-tinted radial wash behind the object, fading to white. Put the main panel at roughly two thirds of the stage width, round its corners 16px, add a faint dark edge and a low shadow, then overlap one smaller result card. Use a floating segmented control beneath, plus a brief sans caption.

### Monumental footer emblem

**Use:** Signature finishing artwork behind the directory and legal rail.

**Observed:** A huge pale blue ring-like brand emblem rises from below the footer; only its upper arc is visible. The graphic is 1300px square at 0.05 opacity, not a giant readable wordmark.

**Transfer:** Use the new brand's simple emblem as an overscale watermark. If it has no suitable symbol, build an abstract open ring or arc from its existing visual geometry.

**Build:** Position a 1300px-square SVG centrally at the footer bottom, translate it downward by about two thirds of its height, set opacity to 0.05 and clip overflow. Render a broad circular or brand-derived stroke in blue with a soft pale inner band, keeping all footer text above it.

### Editorial pastel fields

**Only for:** company-story pages

**Use:** Multicolor backings for long-form principle cards and the opening video frame.

**Observed:** Diffuse corner pools mix blue into lilac, mint into cream, or peach into apricot. Fine grain makes them feel like dyed paper rather than glass. The opening video is monochrome domestic footage of a laptop, inset into a cool pastel frame.

**Transfer:** Use candid work-in-context footage with a restrained monochrome treatment; let the surrounding pastel frame supply color. Reuse the same softened multicolor fields for editorial principles.

**Build:** Use Editorial aurora, varying its corner pool hues across adjacent cards. Overlay a 200px repeating SVG fractalNoise tile with baseFrequency 0.8, two octaves, grayscale and alpha slope 0.1. Keep all gradients broad and low-frequency.

### Icons

**Observed:** Marketing icons are mainly 14–16px outline SVGs with 2px round strokes. Chapter medallions are 24px circles, feature icons sit in 32px rounded pastel tiles, and plan checks use 12px round-stroked glyphs inside tinted circles.

**Transfer:** Use one coherent outline family; reserve filled glyphs for platform or social marks. Match chapter icon color to the capsule and demonstration tint.

## Section recipes

How recurring sections are built.

### First screen: Cloudlit product opening

**Observed:** A 76px navigation band sits above a 660px atmospheric field inside the rounded shell. From back to front: blue-to-mist sky, distant clouds, warm right-side haze, near clouds, then centered content. A dark 36px announcement capsule leads a 42px mode switch; the headline occupies about two thirds of the viewport width with a 60px regular sans statement and a 63.6px italic serif second line. The 19px light serif explanation is centered in a 660px measure, followed by Primary button and Secondary button separated by 12px, a small migration link and platform icons. Within the first 900px, all of this is visible plus the upper portion of the broad dark laptop object; the rest of the device continues below.

**Transfer:** Keep the atmospheric opening, mixed-type promise and product object for a different product. If no interface exists, show a well-composed output artifact in a desktop-like frame. Pricing opens with a single 80px sans title and overlapping plan cards; a company story opens with an 84px title, support and actions above a wide monochrome contextual video on a pastel rim.

**Avoid:** Do not turn the opening into a left-text/right-dashboard split, replace the cloud atmosphere with a flat blue rectangle, or put a full dense dashboard above the promise.

**Text style:** `display` — Instrument Sans 400 · 60px/0.98

### Capability chapter

**Observed:** Within Content, a Chapter capsule sits 24px above a heading in a 760px centered measure; light serif support follows after 20px, often with a short phrase emphasized in the chapter hue. A large Demonstration porcelain stage follows, then a floating pill control, concise sans caption and open Feature item grid with a 32px top inset and 24px by 40px gaps. Chapters commonly have 128px top and bottom padding.

**Transfer:** Organize each chapter around a specific result; use matching color only for its label, icon tiles, selected demo tab and a few words.

**Text style:** `heading` — Instrument Sans 400 · 54px/1 · tracking -0.03em

### Split artifact explanation

**Observed:** Split-demo places a 449px text column beside a 607px media scene, with 64px between. A left-aligned Chapter capsule, 48px heading and serif explanation precede four narrow feature rows; a single isolated artifact floats on a mint-to-white stage.

**Transfer:** Use this for one especially visual capability, with the text establishing what changes and the object making that result visible.

**Text style:** `heading-split` — Instrument Sans 400 · 48px/1 · tracking -0.03em

### Human proof masonry

**Observed:** A centered 56px heading and narrow serif support lead a three-column Customer card layout in a 1200px container. Grid begins 56px below support; cards have 16px gutters and unequal heights. A Secondary button ends the group.

**Transfer:** Let real quotation length shape the card wall rather than forcing identical blocks.

**Text style:** `heading-proof` — Instrument Sans 400 · 56px/1 · tracking -0.03em

### Split heading and disclosures

**Observed:** Split-list gives a short 48px heading and small serif help note a 340px left rail. The right 680px rail uses FAQ row with cool rules and circular plus controls. The same architecture becomes a timeline with Chronology row and tiny mono dates.

**Transfer:** Use the FAQ version for buying objections; scope the dated variation to a company or release narrative.

**Text style:** `heading-split` — Instrument Sans 400 · 48px/1 · tracking -0.03em

### Compact migration callout

**Observed:** A single 1120px-wide white card with 24px corners and 48px inner spacing pairs a 40px regular sans heading and short serif explanation on the left with a Primary button and small coupon capsule on the right.

**Transfer:** Use a compact practical bridge for import, setup or switching concerns before the final invitation, without adding another large feature chapter.

### Expansive closing invitation

**Observed:** The main ending uses a centered 900px measure, 78px regular heading, serif support 28px below and paired actions after 36px. Top and bottom padding expand to 144px and 160px. The pricing variation uses a smaller 56px invitation with a discreet discount link; the company-story variation adds tiny uppercase community links and a light serif team sign-off.

**Transfer:** End with an attainable next step and the same luminous/white action pair, then transition out of the rounded canvas into Directory ground.

**Text style:** `closing` — Instrument Sans 400 · 78px/0.98 · tracking -0.03em

### Watermarked directory ending

**Observed:** The rounded content canvas stops before the gray footer. A separate brand rail faces five narrow Directory columns, followed by a ruled legal/compliance strip. Monumental footer emblem rises behind the lower area at 0.05 opacity. The composition is consistent across all three page types.

**Transfer:** Keep the emblem watermark, low-contrast link density and separate legal rail; reduce destination count to the real needs of the new product.

### Pricing choices and matrix

**Only for:** pricing pages

**Observed:** Plan-grid overlaps the sky by 152px. Three equal-height Plan cards are separated by 16px; the center recommendation is outlined by a soft blue/lilac rim. A small free-use reassurance precedes a centered heading and 1060px white comparison matrix with 22px corners and 12px inset. Rows are about 51px high with subtle rules; the recommended column carries a pale blue wash throughout, and small uppercase mono category labels break up the matrix.

**Transfer:** Keep the distinction between narrative plan cards and scannable comparison rows. Highlight one recommended column consistently without making every tier colorful.

**Text style:** `pricing-display` — Instrument Sans 400 · 80px/0.98 · tracking -0.03em

### Editorial explanation and principles

**Only for:** company-story pages

**Observed:** A left-aligned 56px statement and serif support introduce two equal text columns with 24px subheadings and long 17.5px serif paragraphs. A separate centered heading leads a two-column Editorial aurora card grid with 16px gutters, 32px inset and 26px sans card headings. Later, one white 26px serif quotation sits beside a subdued two-by-two priority panel.

**Transfer:** Use this slower, text-rich variation for philosophy or an origin story; choose themes relevant to the new product rather than copying the subject matter.

**Text style:** `story-card-heading` — Instrument Sans 400 · 26px/1.1 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible product proof → focused capability or belief chapters → trust and buying clarity → low-friction invitation → watermarked directory.

### A product landing page that turns a broad promise into tangible workflows

1. **Promise** — Cloudlit mixed-type opening with an announcement and paired actions.
2. **Product demonstration** — Large illustrated desktop object makes the product feel real.
3. **Capability chapters** — Colored chapter capsules, expansive workflow scenes, small open feature lists and one split artifact section.
4. **Trust** — Ownership and technical assurances, platform availability and a contained developer terminal demonstration.
5. **Social proof** — Serif customer masonry cards with avatars.
6. **Buying clarity** — Two plan cards followed by split-rail FAQs and a compact migration bridge.
7. **Closing call** — Monumental centered invitation and paired buttons, then the watermarked directory.

**Transfer:** Choose the relevant capability chapters and proof forms for the new product; preserve the alternation of atmospheric promise, tangible demonstration and compact explanation.

### A pricing page that explains payment choices without pressuring the reader

1. **Promise** — Short sky-backed title, support and small trust capsule.
2. **Pricing** — Three plan cards overlap the header; the recommendation receives a pastel rim.
3. **Comparison** — White ruled feature matrix with one pale highlighted column.
4. **Objection handling** — Split-rail pricing FAQs.
5. **Social proof** — Customer masonry wall.
6. **Closing call** — Smaller centered invitation, upgrade/download pair and discreet discount link before the shared directory.

**Transfer:** Lead with billing logic and clear entitlements; let proof and answers support the choice after the cards.

### A company-story page that earns trust through beliefs and concrete progress

1. **Origin promise** — Large sans title, serif context and paired actions above monochrome work footage in a pastel frame.
2. **Problem and response** — Two text columns beneath an editorial lead.
3. **Principles** — Two-column multicolor grain-backed cards.
4. **Progress proof** — Dated ruled chronology alongside a narrow heading rail.
5. **Credibility and priorities** — One large serif quotation beside a small four-cell priority panel.
6. **Closing call** — Large invitation, product and community actions, tiny community links and a team sign-off before the shared directory.

**Transfer:** Use an honest origin, actual constraints and verifiable milestones rather than repeating landing-page capability scenes.

## Writing

Direct, friendly and product-literate, with the confidence of someone explaining a useful tool they built. Warmth comes from plain language and specific workflow relief, not enthusiasm punctuation.

**Do not copy:** Do not reuse Cap's name, logo, artwork, customer names, quotations, pricing, adoption numbers, discounts, competitor comparisons, certifications or ownership claims. Use the new product's real assets and verifiable facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Use we for builder intent and accountability; use the product name sparingly when explaining behavior.
- **Rhythm:** Headlines are usually short practical statements, sometimes two clipped sentences. Support paragraphs explain an action and its immediate payoff; longer editorial prose remains conversational. Actions start with a verb.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the product category plainly, then broaden its audience with a brief expressive tail. | 6–10 words | “The open source screen recorder for everyone.” |
| Capability heading | Lead with the result or remove a familiar delay; short sentences can form a causal pair. | 4–9 words | “Stop recording. The link is already copied.”<br>“Your recordings. Actually yours.” |
| Support | Explain the workflow in ordinary verbs and close with a concrete benefit or clear payment condition. | 1–3 short sentences | “Start free. Pay when you need commercial rights or the cloud, and cancel whenever you like.” |
| Primary action | Verb plus destination, outcome or platform; free is factual reassurance rather than hype. | 2–5 words | “Download free for macOS”<br>“See how [Brand] works” |
| Help note | Sound like a person is available, without support-center jargon. | One short line | “Still stuck? Mail and a human answers.” |
| Closing invitation | Offer a low-risk next step or invite participation in a short, confident sentence. | 4–9 words | “Start free. Upgrade when it earns it.”<br>“Build it with us.” |

**Words and phrasing to use:** simple; free; yours; built-in; one click; share; polish; no account needed; when you need it; a human answers

**Avoid:** revolutionary; game-changing; unlock unparalleled potential; synergy; enterprise-grade everything; limited-time urgency

**Rules:**

- Use a concrete verb and an observable result in each capability explanation.
- Differentiate free, paid and optional additions with literal conditions.
- Let technical specificity appear where it answers a real concern, not as decoration.
- Use contractions and occasional clipped sentences; avoid inflated superlatives.
- Keep feature labels short enough to run directly into their explanation.

## Do's and Don'ts

### Do

- Keep major sans headings regular at 400 with -0.03em tracking outside the opening statement.
- Use the 19px light serif intro and 18px serif chapter support to counterbalance the sans display.
- Maintain 48px conversion controls, with a luminous 12px-radius primary and outlined 10px-radius secondary.
- Give core demonstrations a 1120px container and 128px chapter padding.
- Use 32px pastel icon tiles above compact 15px capability descriptions.
- Let authentic quotation cards vary in height within 16px masonry gutters.
- Carry a chapter's accent consistently across its capsule, selected control and small emphasized phrases.
- Retain the oversized low-opacity emblem and gray directory ground at the ending.

### Don't

- Do not make every headline weight 600 or 700; the display hierarchy depends on regular weight.
- Do not convert every paragraph to sans; the light serif is a structural part of the voice.
- Do not use a saturated blue full-page theme; blue is mist, control light or a local chapter accent.
- Do not make primary conversion controls fully pill-shaped; their corners are 12px.
- Do not box each capability item; use open lists with small icon tiles and shared separators.
- Do not flatten all customer cards to equal heights or replace serif quotes with giant bold slogans.
- Do not spread company-story multicolor cards throughout an ordinary capability page.
- Do not turn the contained dark terminal demonstration into a dark default page theme.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions commonly use 0.2s cubic-bezier(0.4,0,0.2,1); the luminous primary transitions filter, transform and box-shadow.
- Declared opening rise uses 0.7s cubic-bezier(0.16,1,0.3,1) with staggered delays including 40ms, 80ms, 0.1s and 0.16s.
- The sky declares slow alternate sways at 16s and 21s, breathing at 10s and 13s, mist at 44s and sun movement at 9s.
- Floating demonstration selectors declare transform and width transitions at 0.5s cubic-bezier(0.34,1.4,0.5,1).

**Transfer:**

- Keep the sky's movement slower and softer than the interface controls.
- Reserve spring-like selector motion for contained product demonstrations; keep ordinary links on short color transitions.

**Unknown:**

- The exact cloud-drift duration and all runtime interaction sequences are not established.
- No resolved hover-filter value is available for the luminous button.

### Responsive

**Observed:**

- Declared width breakpoints include 360px, 480px, 640px, 768px, 900px, 1024px, 1200px, 1280px, 1400px and 1536px.
- Outer-shell classes change from 10px small-screen side inset to 20px and then 32px on the default landing layout; navigation space changes from 68px to 76px.
- Declared layouts progress from single-column capability lists to multiple columns; testimonials use two columns before three. Footer link groups use collapsed rows before desktop columns.
- The measured fluid heading recipes use clamp formulas rather than scaling every text size uniformly.

**Transfer:**

- On narrow screens stack the action pair and split demonstrations while preserving the centered cloudlit promise.
- Reduce the desktop object to the available width, retaining its bezel and glow rather than shrinking its internal labels into the main text hierarchy.
- Keep the oversized footer symbol clipped below the directory even when link groups become stacked rows.

**Unknown:**

- Only desktop visual layouts are established; exact small-screen navigation interactions and cloud placement remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
