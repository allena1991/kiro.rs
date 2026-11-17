# Arcade — fluorescent product playground

## Overview

A bright, spacious software style with matter-of-fact grotesk typography and playful, tactile interface illustrations. White and pale gray carry the reading experience, while electric yellow, lime and mint illuminate product scenes. It suits creative tools and business platforms that want to feel capable without becoming corporate or heavy; sparse text surrounds large, carefully staged demonstrations.

### Essentials

- Headlines sound conversational and look almost unstyled: regular Inter Display at 48px/1.2 with -0.02em tracking, stepping down to 36px/1.2 for chapters rather than using bold display type.
- The default opening is an asymmetric promise, not a giant hero picture: two equal columns, 48px headline left, 16px support right aligned toward its baseline, one black action below, and a 72px fixed navigation above.
- Actions are little rounded rectangles, not capsules: 42px high with 16px corners and 14px/20px medium text; navigation actions shrink to 32px with 12px corners.
- Fluorescence belongs inside the demonstration: keep the page canvas white and supporting cards near #fafafa, concentrating yellow-to-mint color in large 24px-radius media panels and tiny selected chips. Include at least one luminous product stage on a new landing page.
- The interface is treated as a physical exhibit: enlarged white UI fragments, fine edges, soft shadows, oversized black pointers with white outlines, and intentional clipping inside 664px-wide or 1344px-wide panels. Without finished media, stage a simplified but meaningful workflow in the same treatment.
- Small captions stay attached to big pictures: 32px panel padding, 16px/24px semibold titles above regular explanations, placed along the lower edge; 16px gutters join large media cards to low, icon-led supporting cards.
- The ending turns the volume down: a two-line 24px closing promise with its second line #a2a2a2, paired actions on the opposite side, then 80px-spaced footer bands, three text-link columns and a low utility strip.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#fcff5d` | `--color-yellow` | accent, background | Luminous stage palette and selected testimonial chip; a small savings marker on pricing. |
| Lime light | `#d0ff6c` | `--color-lime` | accent, background | Transition from yellow into green in luminous artwork. |
| Mint light | `#9df89c` | `--color-mint` | accent, background | Green portion of luminous artwork. |
| Cool light | `#91e0fb` | `--color-sky` | accent, background | Cool end of the selected-chip gradient and a cool counterpoint in stage artwork. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Utility blue | `#2142e7` | `--color-blue` | link | One highlighted cross-product footer link, not the primary action color. |
| Utility blue wash | `#f1f3fe` | `--color-blue-wash` | surface | Backing for the highlighted footer link. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, interface layers and reversed action text. |
| Soft card | `#fafafa` | `--color-soft-card` | surface | Small feature cards; also the visible result of 2% black over white. |
| Media gray | `#f7f7f7` | `--color-media-base` | surface | Visible result of 3% black over white on large neutral demonstration cards. |
| Control gray | `#f4f4f4` | `--color-control` | surface | Subtle controls, play wells, testimonial tiles and plan shells. |
| Control edge | `#e7e7e7` | `--color-edge` | border | Secondary actions and bordered horizontal notices. |
| Faded line | `#a2a2a2` | `--color-faded` | text | Second line of the closing promise and tertiary copy. |
| Muted copy | `#717171` | `--color-muted` | text, link | Secondary descriptions and footer links. |
| Quote metadata | `#545454` | `--color-quote-meta` | text | Role beneath the testimonial author. |
| Support ink | `#404040` | `--color-support` | text, action | Opening support paragraph and primary-action hover fill. |
| Black ink | `#000000` | `--color-ink` | text, action | Headlines, primary copy, pointers and primary button fills. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Accordion gray | `#f5f5f5` | `--color-faq` | surface | FAQ rows and selected calculator controls. |
| pricing pages | Panel edge | `#e5e5e5` | `--color-panel-edge` | border | Calculator card and its inputs. |
| pricing pages | Accordion ink | `#171717` | `--color-faq-ink` | text | Question text and its focus outline. |

## Typography

- **Inter Display** — All marketing headings, statements and quotes. Open, contemporary grotesk; regular weight and tight tracking provide the identity. If unavailable, use **Inter**. Use weight 400 and retain the role-specific tracking. Font stack: "Inter Display", "Inter", Arial, sans-serif.
- **Inter Variable** — Body copy, actions, statistics and navigation. Neutral, highly legible sans with restrained medium and semibold emphasis. If unavailable, use **Inter**. Font stack: "Inter Variable", "Inter", Arial, sans-serif.
- **Geist Mono Variable** (only for testimonial selector graphics) — Tiny uppercase names inside the testimonial tile field. Compact monospaced labels with lightly expanded tracking. If unavailable, use **Geist Mono**. Font stack: "Geist Mono Variable", "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter Display | 400 | 48px | 1.2 | -0.02em | Default opening promise. |
| heading | Inter Display | 400 | 36px | 1.2 | -0.02em | Capability chapter headings and statement prose. |
| proof-heading | Inter Display | 400 | 32px | 1.2 | -0.01em | Trust-strip introduction and centered testimonial quote. |
| stat | Inter Variable | 600 | 30px | 1.2 | normal | Compact multiplier or percentage in proof cards. |
| heading-small | Inter Display | 400 | 24px | 1.2 | -0.005em | Card headings and the two-line closing promise. |
| body | Inter Variable | 400 | 16px | 1.5 | normal | Support paragraphs and card explanations. |
| card-title | Inter Variable | 600 | 16px | 1.5 | normal | Title attached to product-media captions and small capability cards. |
| action | Inter Variable | 500 | 14px | 20px | normal | Buttons and navigation labels. |
| caption | Inter Variable | 400 | 14px | 20px | normal | Short metric descriptions, pricing details and FAQ questions. |
| footer-link | Inter Variable | 400 | 14px | 1.25 | normal | Footer text links. |
| footer-heading | Inter Variable | 500 | 14px | 1.25 | normal | Footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| interactive creative-tool openings | playground-display | Inter Display | 400 | 56px | 1.2 | -0.02em | Centered headline with inline playful objects above a prompt composer. |
| testimonial selector sections | spotlight-quote | Inter Display | 400 | 36px | 40px | -0.02em | Two-line quote beside a faded tile field. |
| pricing pages | price | Inter Display | 400 | 36px | 1 | normal, features "ss01", "tnum" | Price amount or short custom-price label. |
| pricing calculators | calculator-heading | Inter Display | 400 | 24px | 32px | -0.02em | Title inside the calculator panel. |
| pricing pages | faq-heading | Inter Display | 400 | 24px | 32px | -0.005em | Heading above the centered FAQ column. |
| testimonial selector graphics | tile-label | Geist Mono Variable | 600 | 11px | 1.4 | 0.02em, uppercase | Names on selection tiles. |

**Notes:**

- Use regular display type even for the biggest promise. Weight 600 is reserved for compact statistics and card labels, not headline emphasis.
- Tracking is tightest in headings at -0.02em, relaxes to -0.01em at 32px and -0.005em at 24px, and returns to normal for body and controls.
- Keep distinct pricing and testimonial line-height variants; do not stretch every heading to the same ratio.

## Layout

**Density:** Airy between chapters, compact within controls and captions; large demonstrations carry most of the visual weight.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Dominant vertical rhythm for layout-level padding and gaps; 6px caption gaps and 140px chapter gaps are deliberate exceptions.

| Value | Use |
| --- | --- |
| 8px | Action groups and FAQ row separation. |
| 16px | Grid gutters and footer link stacks. |
| 24px | Hero-to-action gap and pricing panel padding. |
| 32px | Feature card padding. |
| 40px | Icon-to-copy space in small cards and testimonial internal gaps. |
| 48px | Chapter heading to demonstration grid and trust heading to logos. |
| 56px | Gap between chapter heading and support columns; footer grid columns. |
| 80px | Footer bands and testimonial panel padding. |
| 96px | Opening top padding below the navigation. |
| 140px | Major chapter gaps and opening bottom padding. |

### Containers and grids

- **container**: max width 1436px · side padding 46px. Centered outer wrapper; at 1440px the usable width is 1344px and content starts 48px from each edge.
- **opening pair**: 2 columns · gap 16px. Equal headline and support columns; support sits near the headline's lower baseline.
- **chapter heading pair**: 2 columns · gap 56px. Equal-weight heading and support widths, vertically centered.
- **media pair**: 2 columns · gap 16px. Two 664px-wide demonstration panels, or one full-width panel in place of the pair.
- **supporting grid**: 3 columns · gap 16px. Low feature cards beneath a demonstration; two columns when content has only two distinct supporting points.
- **proof grid**: 4 columns · gap 16px. Compact outcome cards.
- **quote panel**: max width 1080px. Centered testimonial panel, narrower than the chapter grid.
- **narrow utility** (only for pricing pages): max width 700px. Centered calculator and FAQ column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media and feature cards | 24px |
|  | primary and secondary actions | 16px |
|  | compact controls | 12px |
|  | icon frame | 8px |
|  | proof cards | 16px |
| pricing pages | plan inset | 22px |
| testimonial selector sections | testimonial tiles | 14px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | proof edge | `rgba(0, 0, 0, 0.12) 0px 0px 0px 1px` | A crisp outline around proof cards without conventional elevation. |
|  | footer rule | `rgba(0, 0, 0, 0.12) 0px -1px 0px 0px` | Fine boundary at the start of the footer. |
| creative-tool showcases | floating media | `rgba(0, 0, 0, 0.1) 0px 16px 30px 0px, rgba(0, 0, 0, 0.08) 0px 32px 70px 0px` | Overlapping output thumbnails in a floating showcase. |

### Surfaces

#### Canvas · level 0

**Use:** Default background.

**CSS:** `background: #ffffff`

#### Neutral media panel · level 1

**Use:** Large UI demonstration without fluorescent backing.

**CSS:** `background: rgba(0, 0, 0, 0.03); border: 1px solid rgba(0, 0, 0, 0.04); border-radius: 24px; overflow: hidden`

**Observed:** Pale neutral backing lets a white enlarged interface sit visibly above it; captions remain at the bottom.

**Transfer:** Use alongside a luminous panel so a chapter has contrast without two competing color fields.

#### Soft feature card · level 1

**Use:** Low supporting cards.

**CSS:** `background: rgba(0, 0, 0, 0.02); border: 1px solid rgba(0, 0, 0, 0.04); border-radius: 24px; padding: 32px`

**Observed:** Flat surface with an almost invisible perimeter; no drop shadow.

**Transfer:** Give supporting points a lower visual weight than demonstrations.

#### Luminous stage · level 1

**Use:** Signature backing for product exhibits.

**CSS:** `background: linear-gradient(110deg, #fcff5d, #d0ff6c, #9df89c, #91e0fb); border-radius: 24px; overflow: hidden`

**Observed:** Broad acid-yellow areas blend into lime, mint and cool cyan, with grainy diagonal transitions and translucent architectural planes. Color stays inside the panel.

**Transfer:** Recreate the soft, textured light and spatial planes rather than a flat two-stop gradient; use the imagery build recipe.

#### Inset feature band · level 0

**Only for:** creative-tool capability sections

**Use:** A large interactive capability chapter.

**CSS:** `background: #fafafa; border-radius: 32px; padding: 140px 0`

**Observed:** Almost edge-to-edge band with 8px outer side space, large square media left and a narrower text interaction right.

**Transfer:** Use when one workflow deserves a slower, immersive explanation.

## Components

### Navigation

**Use:** Persistent lightweight orientation.

**CSS:** `position: fixed; top: 0px; height: 72px; width: 100%; background: rgba(255, 255, 255, 0.627); z-index: 999; display: flex; align-items: center; justify-content: space-between`

**Text style:** `action` — Inter Variable 500 · 14px/20px

**Observed:** Brand mark left, short navigation group after it, login and black signup action far right. Compact actions are 32px high with 12px corners; active page gets a 6% black fill. Other light variants use 74% white.

**Transfer:** Retain the unusually light bar and short navigation; use the main container alignment.

### Primary button

**Use:** Main conversion.

**CSS:** `background: #000000; color: #ffffff; height: 42px; border-radius: 16px; padding: 0px 12px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter Variable 500 · 14px/20px

**Observed:** Text-only by default, sized to its label. Footer actions use 16px side padding and matching widths around 130px.

**States:** Declared: hover background #404040; focus-visible box-shadow rgba(0, 0, 0, 0.2) 0px 0px 0px 2px; active transform scale(0.97).

### Secondary button

**Use:** Alternative sales or detail action.

**CSS:** `background: #ffffff; color: #000000; height: 42px; border: 1px solid #e7e7e7; border-radius: 16px; padding: 0px 16px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter Variable 500 · 14px/20px

**Observed:** Usually sits 8px from a black action; its faint outline is the only emphasis.

**States:** Declared: hover background #fafafa; focus-visible box-shadow rgba(0, 0, 0, 0.2) 0px 0px 0px 2px; active transform scale(0.97).

### Media caption card

**Use:** One large visual explanation with a short attached benefit.

**CSS:** `background: rgba(0, 0, 0, 0.03); border-radius: 24px; padding: 32px; display: flex; flex-direction: column; justify-content: flex-end; position: relative; overflow: hidden`

**Text style:** `card-title` — Inter Variable 600 · 16px/1.5

**Observed:** Illustration fills the upper region; title and regular body explanation form a lower-left caption with a 6px gap. A 664px by 608px panel pairs with another; full-width versions are 1344px by 683px. Luminous stage is the colored variant.

**Transfer:** Crop deliberately into the enlarged interface but keep the caption unobstructed.

### Capability card

**Use:** Supporting points beneath a large demonstration.

**CSS:** `background: rgba(0, 0, 0, 0.02); border-radius: 24px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 40px; border: 1px solid rgba(0, 0, 0, 0.04)`

**Text style:** `card-title` — Inter Variable 600 · 16px/1.5

**Observed:** Outlined 40px icon frame with 8px radius above a short semibold title and regular body explanation. Three-column cards are about 437px wide and 200–222px high.

**Transfer:** Keep each point to one clear capability; use fewer cards rather than filling empty slots.

### Outcome card

**Use:** Compact quantitative proof and chapter routing.

**CSS:** `border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.12) 0px 0px 0px 1px; padding: 4px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `stat` — Inter Variable 600 · 30px/1.2

**Observed:** Four cards across; each 324px by 270px has a 12px-radius inner frame with 16px padding, small identifying artwork above and number plus 14px descriptor anchored low.

**Transfer:** Use a short verified metric and a clear description; preserve the compact number rather than making it a giant display.

### Testimonial panel

**Use:** An authoritative pause between capability chapters.

**CSS:** `border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 24px; padding: 80px; display: flex; flex-direction: column; align-items: center; gap: 40px`

**Text style:** `proof-heading` — Inter Display 400 · 32px/1.2 · tracking -0.01em

**Observed:** Centered quote, small identity or portrait above, author and muted role below, then a bordered 70px-high story action with an inset gray play well. Panel width 1080px.

**Transfer:** Use a credible short quotation and keep ample whitespace around it.

### Footer link

**Use:** Low-emphasis navigation in three columns.

**CSS:** `color: #717171`

**Text style:** `footer-link` — Inter Variable 400 · 14px/1.25

**Observed:** Medium black column headings above 16px-spaced links. One cross-product link is blue on a pale blue rounded rectangle with an arrow; small gray social wells sit in the far-right grid cell.

**States:** Declared: hover color black; focus-visible unspecified.

### Plan card

**Only for:** pricing pages

**Use:** Tier comparison.

**CSS:** `background: #f4f4f4; border-radius: 24px; padding: 2px; display: flex; flex-direction: column`

**Text style:** `price` — Inter Display 400 · 36px/1

**Observed:** Three equal columns at 16px gutters. White upper inset has 22px corners and 24px padding; tier, brief description, price, billing detail, allowance and full-width action sit above a gray checklist. The middle paid tier gets the black button while outer plans use pale actions.

**Transfer:** Align comparable price and action rows; do not color-fill the promoted tier.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling.

**CSS:** `background: #f5f5f5; border-radius: 16px; min-height: 56px; padding: 16px 24px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `caption` — Inter Variable 400 · 14px/20px

**Observed:** A 700px-wide stack with 8px between rows, small text left and a fine plus at the right.

**States:** Declared: hover unspecified; focus-visible outline #171717 solid 2px with outline-offset -2px.

### Calculator panel

**Only for:** pricing pages

**Use:** Make usage-based pricing concrete.

**CSS:** `background: #ffffff; border: 1px solid #e5e5e5; border-radius: 24px; padding: 80px; max-width: 700px`

**Text style:** `calculator-heading` — Inter Display 400 · 24px/32px · tracking -0.02em

**Observed:** Title above small segmented options and a thin horizontal length slider; a faint divider separates controls from a result with black amount and gray unit. Inputs have 12px corners; helper labels remain small and neutral.

**Transfer:** Use only the inputs that affect the quote; retain the airy panel rather than turning it into a dense form.

## Imagery and graphics

### Fluorescent interface exhibit

**Use:** Signature large product demonstrations throughout a landing page.

**Observed:** Large white interface fragments float over luminous yellow, lime and mint planes. Fine grain breaks up the gradients, softly blurred transitions cross the panel, and a large dark pointer with white edging and shadow adds a tangible playful scale. UI is often enlarged past the panel edge rather than shown as an entire browser window.

**Transfer:** Show one real workflow or meaningful output at a readable, enlarged scale. Minimum version: a white card with a few truthful controls or content rows, a clear active selection, and a pointer over a luminous textured backing.

**Build:** Within a 24px-radius clipped panel, lay a 110deg yellow/lime/mint/cool-blue gradient. Overlay two broad translucent mint and yellow polygons, one vertical near the left third and one diagonal crossing the lower edge; soften their transitions with 40px blur. Add an SVG fractal-noise layer in black at 0.04 opacity, clipped to the backing only. Put the white interface above it with a faint black edge and soft downward shadow. Draw a black arrow pointer in SVG with a white outline and gray drop shadow, overlapping the interface edge. Match the soft glow; exact stops are not essential.

### Neutral interface enlargement

**Use:** Companion panels to the luminous exhibits.

**Observed:** Pale gray backing with centered white permissions, activity or audience fragments. UI edges and shadows are restrained; the lower illustration often fades gently into the panel before the caption.

**Transfer:** Simplify to the one interaction that proves the capability; use a soft bottom mask so the media does not collide with its caption.

### Floating output fan

**Only for:** creative-tool showcases

**Use:** Product-output proof before explanatory chapters.

**Observed:** A compact central fan of overlapping, slightly rotated output cards on a huge white field; saturated blue and dark thumbnails interrupt white content, with broad soft shadows and 16px corners.

**Transfer:** Use actual representative outputs, or designed examples that demonstrate the new tool's range. Keep the fan a small island rather than a full-width collage.

### Spotlight tile field

**Only for:** testimonial selector sections

**Use:** Interactive alternative to the centered testimonial panel.

**Observed:** A 480px by 400px masked field of pale 72px-high rounded tiles sits beside a 560px quote. One 163px-wide tile is yellow-to-mint highlighted with an uppercase mono name, a thin vertical cursor line and playful pointer. Side tiles fade into white.

**Transfer:** Use names or short categories relevant to genuine stories. Fill tiles with meaningful subdued labels rather than treating empty rectangles as a visual motif.

**Build:** Create staggered rows of 14px-radius #f4f4f4 tiles separated by 16px. Mask the field horizontally from transparent to opaque at 20%, remaining opaque to 80%, then transparent. Fill one tile with linear-gradient(110deg, #fcff5d, #d0ff6c, #9df89c, #91e0fb), add an 11px uppercase mono label and a 2px black vertical line; place an outlined black pointer near its lower-right corner.

### Icons

**Observed:** Small monochrome interface symbols, generally 20px or 24px. Inline SVG controls use 1.5px strokes with round caps; feature symbols sit in 40px outlined squares. Large illustration pointers are intentionally more tactile than the navigation icons.

**Transfer:** Use simple rounded line icons with black strokes and no multicolor badge system; reserve the large outlined pointer for product exhibits.

## Section recipes

How recurring sections are built.

### First screen: Asymmetric promise opening

**Observed:** White canvas behind a 72px fixed Navigation. The hero begins with 96px top padding, filling a 1344px content width. A regular 48px two-line promise occupies the left half; a 16px support paragraph occupies the right half, aligned toward the bottom of the headline. Primary button follows below the left column at a 24px gap. After 140px breathing room, the trust introduction uses 32px type and a single gray logo strip. Within the first 900px, navigation, full promise, support, action, trust heading and logos are visible; the next chapter heading starts near the lower edge. There is no giant media object above the fold; the large luminous demonstration arrives later.

**Transfer:** For a different product, lead with a specific outcome and one explanatory paragraph; make the first large media stage prove that outcome below the opening. Creative-tool pages can instead use the centered 56px playground-display with inline objects, a 680px-wide prompt composer and short suggestion chips. Pricing opens with a 48px title, compact billing selector to its right and the plan grid immediately below.

**Avoid:** Do not insert a full-bleed hero video, giant decorative gradient behind the headline, or centered oversized SaaS headline into the default split opening.

**Text style:** `display` — Inter Display 400 · 48px/1.2 · tracking -0.02em

### Trust strip

**Observed:** Two-line proof-heading at the left, then a horizontally moving row of desaturated gray logos separated from it by 48px. Logos remain visually subordinate and fade at the horizontal edges.

**Transfer:** Use authenticated customer, partner or integration proof with similar optical logo heights; retain the restrained gray treatment.

### Capability chapter

**Observed:** Chapter heading pair uses heading and body recipes with a 56px column gap. Media begins 48px below: either a Media caption card pair with one Luminous stage and one Neutral media panel, or a single full-width luminous exhibit. A 16px gutter separates the media from a lower two- or three-column row of Capability cards. Chapters have 140px gaps.

**Transfer:** Turn each product benefit into one visual proof plus a few specific supporting details; vary full-width and paired media to avoid an endless identical grid.

**Text style:** `heading` — Inter Display 400 · 36px/1.2 · tracking -0.02em

### Quantified proof

**Observed:** A short heading and explanatory line introduce four Outcome cards at 16px gutters. Metrics use 30px semibold type and small contextual labels rather than enormous billboard numerals.

**Transfer:** Use defensible metrics with enough context to make the result meaningful; adapt the number of cards to available proof.

**Text style:** `stat` — Inter Variable 600 · 30px/1.2

### Testimonial pause

**Observed:** A 1080px-wide Testimonial panel centers a 32px quote, identity, attribution and story action, with 80px inner padding. The selector variant places Spotlight tile field left and a 36px/40px quote right with small previous/next controls.

**Transfer:** Choose the centered version for institutional credibility and the selector variant for several compact product stories; keep both far lighter than the product stages.

**Text style:** `proof-heading` — Inter Display 400 · 32px/1.2 · tracking -0.01em

### Low-volume closing and footer

**Observed:** A fine top rule introduces an 80px-padded closing band. The left has a two-line heading-small promise with a faded second line; Primary button and Secondary button sit right. Below a hairline, the footer uses a five-cell grid: symbol, three navigation columns, social controls. Bands are 80px apart. A final thin rule introduces an AI-assistant utility row at left and copyright at right; a single blue-wash cross-product link punctuates the neutral columns.

**Transfer:** End with a short two-part benefit rather than another giant hero. Preserve the split action layout, column rhythm and low utility strip; adapt utility destinations to the product.

**Text style:** `heading-small` — Inter Display 400 · 24px/1.2 · tracking -0.005em

### Interactive utility chapter

**Only for:** pricing pages

**Observed:** Three Plan cards first, followed by a bordered horizontal cross-product notice. After 140px separation, the centered Calculator panel explains the unit economics. The 700px FAQ column follows with 32px between its heading and row stack.

**Transfer:** Separate comparison, calculation and objections into distinct reading tasks while sharing the narrow utility alignment.

**Text style:** `faq-heading` — Inter Display 400 · 24px/32px · tracking -0.005em

## Page flow

**Storyline:** Promise → trust → concrete proof → capability chapters → human endorsement → reassurance or objections → understated closing action.

### Broad product discovery for a creative tool

1. **Promise** — Centered text with playful inline objects and a prompt-like interaction.
2. **Social proof** — Two-line trust statement and gray logo strip.
3. **Product demonstration** — Floating output fan followed by short statement prose with inline graphic objects.
4. **Capability chapters** — Inset interactive workflow band, then paired integration or access cards.
5. **Human endorsement** — Selectable tile-field testimonial.
6. **Closing call** — Low-volume closing and footer.

**Transfer:** Let visitors encounter an inviting lightweight interaction before explaining the mechanism; use output examples and a concise statement to bridge into capabilities.

### Plan selection and pricing confidence

1. **Pricing** — Simple title and billing selector over three aligned Plan cards.
2. **Alternative route** — Bordered full-width notice points to a related offering.
3. **Cost explanation** — Narrow Calculator panel makes usage concrete.
4. **Objection handling** — Long but compact FAQ row stack.
5. **Closing call** — Shared understated closing and footer.

**Transfer:** Keep pricing visually neutral so comparison remains easy; place promotional color only in a small savings marker.

### A scalable business-platform landing page; the default visual composition

1. **Promise** — Asymmetric promise opening with one sales-oriented action.
2. **Social proof** — Gray logo strip followed by an outcome-oriented introduction.
3. **Quantified proof** — Four compact Outcome cards.
4. **Capability chapters** — Alternating paired and full-width luminous demonstrations with supporting cards.
5. **Human endorsement** — Centered bordered Testimonial panel interrupts the chapters.
6. **Reassurance** — More capability chapters address operational reliability, visibility and trust.
7. **Closing call** — Low-volume closing and footer.

**Transfer:** Use the spacious split composition and vivid demonstrations for any complex product; choose chapters around actual buyer concerns instead of copying the original subject matter.

## Writing

Confident, plainspoken and practical, with a playful edge carried by short contrasts and tangible verbs. It makes sophisticated software sound controllable rather than magical.

**Do not copy:** Do not reuse Arcade's name, marks, customer logos, customer names, quotations, proprietary artwork, numerical claims, plan prices, certifications or product-specific promises. Examples illustrate tone only; all new claims need the new product's own substantiation.

- **Addressing the reader:** Speak directly to 'you' and 'your team'; name the product when explaining what it does. Team-wide outcomes often use 'every' and 'one' to make scale feel manageable.
- **Rhythm:** Headlines are usually 4–10 words, often with a contrast or a short sentence pair. Support is one or two compact sentences; feature labels are short noun phrases. Contractions and occasional clipped sentences keep the tone human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Active verb plus the outcome, widened to the whole team. | 6–10 words | “Scale the product story across every team” |
| Chapter heading | Name a practical frustration and its opposite. | 5–9 words | “Beautiful, branded content without a design queue”<br>“Demos that work everywhere, even offline” |
| Support | Start with a real-world interruption, then describe the dependable behavior. | 15–30 words | “Wi-Fi dies. Your demo shouldn't. Your full library travels with you, ready for boardrooms, conferences, and on-site visits.” |
| Feature label | Concrete capability or short assurance, no adjective pileup. | 2–5 words | “On-brand by default”<br>“You control what ships” |
| Action | Direct verb and destination; match commitment to the page. | 2–6 words | “Get started”<br>“Talk to a GTM expert”<br>“View demo plans” |
| Closing promise | Reassuring two-part contrast, with the second phrase visually softened. | 8–12 words | “Your next video doesn’t have to look like AI.” |

**Words and phrasing to use:** your; every team; one; build; shape; share; ready; control; by default; without

**Avoid:** revolutionary; unparalleled; synergize; unlock limitless potential; magic-powered; next-generation ecosystem

**Rules:**

- Lead with the result a person can recognize, then explain the concrete behavior that produces it.
- Use contrast to sharpen a benefit rather than adding unsupported superlatives.
- Keep acronyms only where the intended buyer already uses them; keep labels understandable without reading the paragraph.
- Let short sentences carry reassurance and let detailed support explain the mechanism.

## Do's and Don'ts

### Do

- Keep main headings regular at 48px or 36px with -0.02em tracking.
- Align large grids to the 1344px usable width inside the 1436px wrapper.
- Pair a luminous media panel with a neutral one at 16px gutters.
- Keep feature captions 32px inside the panel and clear of the illustration.
- Use 140px chapter separation and 48px from chapter header to media.
- Make primary actions black, 42px high and 16px rounded.
- Retain the faded second line of the 24px closing statement.
- Use soft shadow depth for floating interface fragments, not for every marketing card.

### Don't

- Do not switch the white page into a dark theme to make the fluorescent colors brighter.
- Do not replace 16px-radius action rectangles with fully pill-shaped buttons.
- Do not make headings bold or add uppercase marketing eyebrows everywhere.
- Do not apply the tiny mono tile-label style to ordinary navigation or body copy.
- Do not turn the utility blue into the main brand CTA color.
- Do not put drop shadows on the low supporting cards; their 4% black perimeter is enough.
- Do not enlarge the compact 30px metrics into oversized hero numerals.
- Do not put every product scene in a complete browser chrome; use enlarged, deliberately clipped fragments.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary actions declare all 0.15s cubic-bezier(0.4, 0, 0.2, 1), with active scale(0.97).
- Logo strips declare logoSlide 40s linear infinite.
- The footer utility title declares a 2s linear infinite text shimmer.
- FAQ surfaces declare background-color 150ms; navigation background declares 150ms ease-in.

**Transfer:**

- Keep action motion small and tactile; the selected tile and playful pointers provide the expressive layer.
- Use continuous slow movement for logo proof, not for body copy or whole chapters.

**Unknown:**

- Scroll reveal choreography and canvas interactions are not fully established; do not invent timing for them.

### Responsive

**Observed:**

- Styles declare breakpoints at 479px, 767px, 768px, 991px and 992px across the pages; additional creative-tool and pricing rules include 639px.

**Transfer:**

- Recommended adaptation: stack split heading/support pairs in reading order, then stack media panels and supporting cards; keep the caption attached below its visual.
- Recommended adaptation: scale down UI illustrations within their clipped rounded stage rather than shrinking their labels into unreadability; turn the five-cell footer into grouped rows.

**Unknown:**

- Only the 1440px desktop composition is established; exact narrow-screen dimensions, navigation behavior and type resizing are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
