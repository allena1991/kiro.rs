# Shopify Design — oversized words, playful objects

## Overview

A bright, type-led editorial style with oversized grotesk lettering and a playful gallery sensibility. White and black dominate, interrupted by electric green, acid yellow, warm stone and emphatic red-orange. Product films, interface compositions, portraits and glossy sculptural objects give an otherwise sparse page a lively, experimental character. It suits ambitious creative tools, platforms and product stories that can demonstrate their craft visually.

### Essentials

- Words act as the opening object: centered two-line grotesk at 220px, weight 500, 0.7 line height and -0.04em tracking, with only a 20px supporting line beneath.
- The first screen is a poster above a gallery: a sparse corner-to-corner header, a headline spanning about 1110px, a mono live-feed rail near the bottom and the top of three media columns visible within 900px.
- Actions are small linked beads rather than big rectangles: 44px-high pills, 9999px radii and a detached 44px arrow disc separated by 8px for the dark action.
- Color arrives in concentrated islands: keep the page canvas white and type black; use #dfd5cb, #6bff91 and #bfff04 for individual editorial cards and #fe432a for a short monumental statement, not continuous colored bands.
- Media behaves like a collection of crafted artifacts: three uneven columns with 21.6px gaps and 24px rounded edges; editorial cards add smaller, lightly tilted media with soft shadows. Use original interface studies or photographed prototypes when films are unavailable.
- Include a monumental proof graphic and a typographic word sculpture: a cropped dial with a giant number makes one fact physical; staggered 160px lines with tiny mono annotations give a later statement a spatial rhythm. A simple SVG dial and a text-only staggered composition are the minimum equivalents.
- The ending stays human and spare: a 14px uppercase mono identity/year rail, 1px rule, 40px invitation, compact outlined pill and a glossy freestanding object on the right; a shaded two-tone capsule supplies a buildable fallback.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#bfff04` | `--color-acid` | surface | Another editorial card backing; concentrated rather than page-wide. |
| Vermilion | `#fe432a` | `--color-vermilion` | text, accent | Emphatic oversized statement and the warm orange-red family of the dial artwork. |
| Electric mint | `#6bff91` | `--color-green` | surface, accent | Selected editorial card backing and tiny live-status dot. |
| Forest lettering | `#1c3b36` | `--color-forest` | text | Oversized cropped background lettering on the green editorial card. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, background | Default display and body text, dark action fills. |
| Rail ink | `#1a1a1a` | `--color-rail-ink` | text | Small footer identity and date markings. |
| Muted action text | `#6f7680` | `--color-muted` | text | Secondary descriptor within the closing outlined action. |
| Warm stone | `#dfd5cb` | `--color-stone` | surface | Neutral backing for editorial media cards. |
| Divider gray | `#e6e6e6` | `--color-rule` | border | Thin horizontal separators and the visible outlined-pill edge, the latter made with black at 0.1 alpha over white. |
| Gallery edge | `#f5f5f5` | `--color-edge-soft` | border | Visible gallery hairline; made with black at 0.04 alpha over white. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text, border | Continuous page field, pale action surfaces and reversed lettering on dark actions. |

## Typography

- **AntiqueLegacy** — Display headlines, paragraphs and actions. A compact neo-grotesk with blunt terminals, a high x-height and dense headline color; visually sans serif. If unavailable, use **Inter**. Use 400 and 500; preserve tight tracking and tune line breaks to the compact silhouette. Font stack: "AntiqueLegacy", "Inter", Arial, sans-serif.
- **FragmentMono** — Live-feed markings, captions, annotations and footer metadata. Plain, mechanical monospace that sharply contrasts the enormous proportional headlines. If unavailable, use **Fragment Mono**. Font stack: "FragmentMono", "Fragment Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | AntiqueLegacy | 500 | 220px | 0.7 | -0.04em | Opening two-line promise, centered and optically fitted. |
| chapter-display | AntiqueLegacy | 500 | 160px | 0.9 | -0.04em | Centered editorial chapter title. |
| sculpture-display | AntiqueLegacy | 500 | 160px | 0.85 | -0.04em | Staggered statement and oversized list composition. |
| card-background-display | AntiqueLegacy | 500 | 139px | 0.85 | -0.04em | Decorative oversized text behind inset editorial media; clipped by the card boundary. |
| heading | AntiqueLegacy | 500 | 40px | 0.85 | -0.03em | Compact manifesto beside a supporting paragraph. |
| closing-heading | AntiqueLegacy | 500 | 40px | 1 | -0.03em | Closing invitation, constrained to 320px. |
| body | AntiqueLegacy | 400 | 20px | 1.1 | -0.02em | Short support lines and brief explanatory paragraphs. |
| action | AntiqueLegacy | 500 | 16px | 19px | -0.015em | Pill labels and their secondary descriptors. |
| card-caption | FragmentMono | 400 | 14.1px | 17px | normal, uppercase | Paired editorial card captions pinned to the lower corners. |
| metadata | FragmentMono | 400 | 14px | 17px | 0.05em, uppercase | Live-feed label and footer identity/year rail. |
| annotation | FragmentMono | 400 | 13.5px | 1.1 | normal | Tiny two-line annotations next to monumental words. |

**Notes:**

- Use the grotesk's real medium weight, not an extra-bold substitution, to create the dense display silhouette. Extreme size and -0.04em tracking do much of the work.
- Opening line boxes are deliberately shorter than the letterforms; compose the two lines as a poster and check that descenders do not collide.
- Maintain the abrupt jump from 160–220px display to 20px body and 13.5–14.1px mono annotations. Avoid filling the hierarchy with many intermediate headline sizes.

## Layout

**Density:** Airy at the page scale, tightly packed inside display line stacks; galleries are visually dense while editorial text remains brief.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Gap between action pill and detached arrow disc, and status-dot label gap. |
| 12px | Vertical action padding and space from proof copy to its action. |
| 16px | Space around the live-feed rail and between giant words and small annotations. |
| 21.6px | Gallery column and stacked-card gaps. |
| 24px | Editorial carousel gap and closing heading-to-action gap. |
| 28.2px | Editorial card inset. |
| 40px | Opening headline-to-support spacing. |
| 48px | Primary page side inset. |
| 64px | Chapter title-to-support gap and footer body top padding. |
| 100px | Top padding before the centered editorial chapter. |
| 112px | Separation between the opening headline wrapper and live-feed rail. |
| 140px | Vertical breathing room around the inset manifesto pair. |
| 200px | Separation and breathing room around the typographic statement. |

### Containers and grids

- **page-container**: max width 1440px · side padding 48px. Centered desktop composition with wide media reaching the side inset.
- **display-grid**: max width 1440px · 10 columns. Invisible equal-column structure for offset headline lines and the inset two-part manifesto.
- **gallery**: 3 columns · gap 21.6px · side padding 48px. Independent vertical stacks with uneven media heights rather than aligned rows; cards are 434px wide at the desktop width.
- **editorial-strip**: gap 24px · side padding 48px. Horizontal row of 415px by 558px cards with a partial next card continuing beyond the right edge.
- **manifesto-copy**: max width 408px. Two adjacent narrow text columns, well inside the page edges; heading left, body and action right.

## Corner radius

| Element | Radius |
| --- | --- |
| media-cards | 24px |
| inset-editorial-media | 24.1px |
| actions | 9999px (pill) |
| status-dot | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| inset-media | `0px 24px 32px 0px rgba(0, 0, 0, 0.12)` | Small portrait or artwork frames floating inside editorial cards. |
| header-action | `0px 2px 32px 0px rgba(0, 0, 0, 0.12)` | White header pill and its detached arrow disc. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous white field connecting the whole story.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No alternating dark section bands; large graphics and type sit directly on the page.

**Transfer:** Separate chapters with scale and whitespace instead of changing the page background.

#### Gallery frame · level 1

**Use:** Edge-to-edge image and film cards.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.04); border-radius: 24px; overflow: hidden`

**Observed:** The outline is barely visible; imagery provides nearly all of each card's color. There is no visible resting elevation.

**Transfer:** Use one continuous media composition per frame.

#### Editorial backing · level 1

**Use:** A solid rounded stage for an inset media artifact.

**CSS:** `background: #dfd5cb; border-radius: 24px; padding: 28.2px; overflow: hidden`

**Observed:** Warm stone is repeated; selected siblings use electric mint and acid yellow. An inset film or image floats over the backing, sometimes over clipped huge lettering.

**Transfer:** Use a small palette of flat backings, not gradients or washed-out tints.

#### Floating media · level 2

**Use:** Inset portrait or printed-work frame inside editorial cards.

**CSS:** `border-radius: 24.1px; box-shadow: 0px 24px 32px 0px rgba(0, 0, 0, 0.12); overflow: hidden`

**Observed:** Media is roughly 240–253px wide inside a 415px card and subtly rotated.

**Transfer:** Keep the dimensional effect on the inset artifact, not the entire backing.

## Components

### Sparse header

**Use:** Orient the reader without a conventional menu bar.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 32px; padding: 24px 48px 48px; position: absolute; z-index: 1`

**Observed:** A compact black logo is alone at the left; a small object, white destination pill and detached external-arrow disc form a cluster at the right.

**Transfer:** Use a single destination rather than adding a row of navigation categories.

### Dark split action

**Use:** Contextual primary action below a short explanation.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid #ffffff; border-radius: 9999px; height: 44px; padding: 12px 24px 12px 20px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — AntiqueLegacy 500 · 16px/19px · tracking -0.015em

**Observed:** The label capsule and separate circular arrow are one click target; the arrow disc sits 8px away. A small leading symbol can accompany the label.

**Transfer:** Allow label width to follow content; retain the separate circular arrow.

### Outlined closing action

**Use:** Final invitation with a main label and secondary destination description.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 9999px; height: 44px; padding: 12px 18px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — AntiqueLegacy 500 · 16px/19px · tracking -0.015em

**Observed:** One outline encloses the main label, a small solid symbol and muted descriptor, with 12px internal gaps. The source example is 254px wide.

**Transfer:** Use a relevant destination descriptor rather than a second competing button.

### Header destination pill

**Use:** Single secondary destination at the upper right.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 9999px; height: 44px; padding: 12px 18px; box-shadow: 0px 2px 32px 0px rgba(0, 0, 0, 0.12)`

**Text style:** `action` — AntiqueLegacy 500 · 16px/19px · tracking -0.015em

**Observed:** Paired with a detached white external-arrow disc of equal height and a miniature sculptural object.

### Live feed rail

**Use:** Transition from opening promise into the media gallery.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 0px 52px; max-width: 1440px`

**Text style:** `metadata` — FragmentMono 400 · 14px/17px · tracking 0.05em · uppercase

**Observed:** A 6px green dot precedes the left label; a long fine gray rule fills the middle; a short source link anchors the right.

**Transfer:** Use a truthful status or collection label and a short provenance link.

### Gallery tile

**Use:** Show visual product proof in the uneven three-column collection.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.04); border-radius: 24px; position: relative; overflow: hidden`

**Observed:** Mixed landscape, square and tall formats contain interface films, phone mockups, portraits and experimental art; no standard title/body/button stack overlays every tile.

**Transfer:** Favor tangible demonstrations and varied aspect ratios over repeated feature text.

### Editorial media card

**Use:** Human conversations, work stories or related resources.

**CSS:** `background: #dfd5cb; border-radius: 24px; width: 415px; height: 558px; padding: 28.2px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `card-caption` — FragmentMono 400 · 14.1px/17px · uppercase

**Observed:** Inset portrait or artwork is centered above bottom-corner metadata. Green and acid variants punctuate the row; the green version places giant forest-colored lettering behind the media.

**Transfer:** Pair a content title with a contributor or format caption; keep the outer card a mostly flat color.

### Footer invitation

**Use:** End the narrative with one forward-looking action.

**CSS:** `display: flex; flex-direction: column; padding: 0px 48px 164px`

**Text style:** `closing-heading` — AntiqueLegacy 500 · 40px/1 · tracking -0.03em

**Observed:** An identity/date rail precedes a rule. The body begins 64px later, with a narrow heading and outlined closing action 24px below it; a glossy object balances the right side.

**Transfer:** Keep the final invitation personal and compact, without a multi-column link directory.

## Imagery and graphics

### Mixed media gallery

**Use:** The main visual demonstration of product craft.

**Observed:** Three independent columns mix close-up phone interfaces, isolated product objects, naturalistic flower imagery, rendered typographic experiments and conversational video portraits. Individual backdrops range from black to pale gray and vivid green, all constrained by rounded frames. Media dominates the long gallery; surrounding captions remain minimal.

**Transfer:** Create original interface sequences, small physical prototypes and portrait clips with varied dark, light and saturated backing. With limited assets, combine real interface stills and carefully lit object photographs rather than empty decorative panels.

### Monumental dial

**Use:** A required physical treatment of one meaningful quantitative proof point.

**Observed:** A white clock-like face grows beyond the viewport, with a fine orange-red circular edge, pale gray ticks, a warm orange-red dimensional hand and hub, and enormous numerals that appear as outlines and then black fills. Colorful isolated objects float in front. The scene is much larger than the explanatory copy that follows it.

**Transfer:** Choose a metric that has a valid relationship to the product; express it through a dial or similarly physical measuring instrument. Minimum version: a clean SVG dial, enormous live-text numeral and a few isolated product cutouts.

**Build:** Use an SVG circle exceeding the viewport width, a thin vermilion perimeter and repeated short gray radial tick marks. Layer oversized black numeral text at the center, with a pale gray stroke-only version for the outline treatment. Add a rounded vermilion hand rotated from a circular hub; use a narrow lighter highlight along one edge and a soft rgba(0,0,0,0.12) shadow. Place two or three transparent-background object images in the foreground. Clip the scene to its stage so the dial feels too big to fit.

### Editorial inset artifacts

**Use:** Media within the horizontal resource strip.

**Observed:** Warm stone, green and acid card backings surround smaller rounded portrait or printed-work frames. Frames are subtly tilted, one at 1.3deg, and elevated by a broad soft shadow. Some frames include small play triangles; giant background text is clipped behind them.

**Transfer:** Use real people, prototypes or printed artifacts rather than generic lifestyle banners. A still image with a slight rotation and a soft shadow is a sufficient equivalent.

### Inline photographic interruption

**Use:** A small image embedded between words in the typographic statement.

**Observed:** A warm, wood-lined interior photograph fits between two huge words, with rounded corners, a small white identifying mark and expand arrows. It remains subordinate to the lettering.

**Transfer:** Use one relevant environment or product-detail image inside a word gap; preserve the surrounding baseline rhythm instead of making a separate image row.

### Glossy closing object

**Use:** A required playful sculptural counterweight to the final invitation.

**Observed:** An isolated two-tone capsule stands on the white field at the right, red above and purple below, with a smooth plastic highlight and no enclosing card. It is far larger here than the tiny object accents elsewhere.

**Transfer:** Use one simple product-adjacent sculptural object. A shaded two-tone capsule is the minimum equivalent; keep it free-standing rather than turning it into a flat icon.

**Build:** Create a tall rounded capsule from two joined SVG half-shapes, with red-orange upper and muted purple lower materials. Use broad translucent white highlights near the upper-left, a dark translucent overlay along the lower-right edge, and a faint seam across the middle. Give it a slight tilt and keep its silhouette about the height of the closing heading/action group. Match the soft plastic sheen; exact gradient stops are not essential.

### Icons

**Observed:** Utility icons are sparse: approximately 20px arrows in 44px discs, small solid white play triangles around 14–15px over media, and compact identity symbols inside actions.

**Transfer:** Use simple arrows and solid play symbols; do not add a colored feature-icon system.

## Section recipes

How recurring sections are built.

### First screen: Poster over gallery

**Observed:** White canvas, then a sparse header anchored to opposing corners, then a centered black two-line headline spanning about 1110px of the 1440px composition. The headline begins well below the header and uses the display recipe; the second line is wider, producing a broad poster silhouette. A centered body line sits 40px below. The first 900px includes the complete promise and support, a live feed rail near 712px, and the upper edge of three gallery tiles beginning near 773px. The headline is the main object; there is no hero illustration or central conversion button. The header destination is the opening action, while the substantive gallery continues below the fold.

**Transfer:** Write a short transformational promise that can form two powerful lines, then prove it with original media immediately below the rail. Without film, use interface studies and object stills. For narrower-purpose pages, shorten the gallery but preserve the poster-first hierarchy and a visible glimpse of proof.

**Avoid:** Do not replace the opening with a standard left-copy/right-dashboard split or push the gallery below an added pair of large hero buttons.

**Text style:** `display` — AntiqueLegacy 500 · 220px/0.7 · tracking -0.04em

### Uneven proof collection

**Observed:** Gallery tiles fill three independently stacked columns inside the page-container. Maintain 21.6px gaps and varied tile heights, letting vivid internal media contrast with the continuous Canvas.

**Transfer:** Show a curated range of capabilities or outcomes through different media formats instead of equal-height textual feature cards.

### Physical proof and manifesto pair

**Observed:** The Monumental dial occupies an immersive viewport-sized stage. An inset pair follows: compact 40px heading on the left, 20px paragraph on the right, with Dark split action below the paragraph. Both text columns are roughly 408px wide, comfortably inside the outer edges.

**Transfer:** Make one real metric tangible, then explain why it matters in a short statement and a fact-based paragraph. The giant instrument is the spectacle; the text stays small.

**Text style:** `heading` — AntiqueLegacy 500 · 40px/0.85 · tracking -0.03em

### Centered chapter and editorial strip

**Observed:** A centered two-line chapter-display starts after 100px top padding. Its 20px supporting copy sits 64px below. Editorial media cards continue across a 24px-gap horizontal strip with the next card partially exposed at the right.

**Transfer:** Introduce resources, stories or examples with a concise editorial title; maintain the solid backing/inset-media distinction.

**Text style:** `chapter-display` — AntiqueLegacy 500 · 160px/0.9 · tracking -0.04em

### Staggered word sculpture

**Observed:** A short red-orange statement leads into black oversized lines offset across the invisible ten-column grid. Sculpture-display uses tightly stacked 0.85 line height. Small annotation labels cling to the ends or beginnings of selected lines; one photographic tile interrupts a line. The composition ends with 200px breathing room.

**Transfer:** Use short outcomes, capabilities or principles as the giant words. Keep the staggered typography device even when there are no locations or team stories; use tiny factual annotations and one relevant detail image.

**Text style:** `sculpture-display` — AntiqueLegacy 500 · 160px/0.85 · tracking -0.04em

### Spare invitation ending

**Observed:** Footer invitation places a 14px uppercase identity at left and year at right, above a full-width 1px gray rule. The narrow closing-heading and Outlined closing action sit below at the left, while Glossy closing object occupies the right. The white field continues to the end with 164px bottom padding.

**Transfer:** End with one concise invitation and destination; let the final sculpture supply personality rather than adding a dense promotional band.

**Text style:** `closing-heading` — AntiqueLegacy 500 · 40px/1 · tracking -0.03em

## Page flow

**Storyline:** Transformational promise → visible work → physicalized proof → editorial depth → monumental statement → personal invitation.

### A flagship marketing story that demonstrates creative capability before asking for commitment

1. **Promise** — Oversized two-line poster and brief support, followed by a live-feed rail.
2. **Product demonstration** — A long uneven gallery of films, interface studies, objects and human portraits.
3. **Quantified proof** — A giant dial and number become a physical scene, then resolve into a small explanatory heading/copy pair.
4. **Editorial depth** — A centered chapter heading introduces a row of colorful inset-media cards.
5. **Capability statement** — A staggered word sculpture combines red-orange emphasis, black giant words, tiny annotations and an inline photograph.
6. **Closing call** — A metadata rail, narrow invitation, outlined action and glossy sculptural object end the story.

**Transfer:** Adapt the relative length of proof and editorial chapters to the new product. Preserve the changes of scale and required graphic devices without treating the sequence or number of sections as fixed.

## Writing

Confident, curious and collective. Short manifesto-like statements are grounded by plain explanations, human conversations and a concrete fact rather than a barrage of sales claims.

**Do not copy:** Do not reuse Shopify names, logos, branded artwork, contributor identities, the merchant-sale statistic, location claims or source slogans as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Uses we and our for a collective point of view; headlines often speak through imperatives without repeatedly saying you.
- **Rhythm:** Two-to-five-word display phrases; one short support sentence or two linked thoughts; compact paragraphs and understated action labels. Punctuation is restrained and sentence case predominates outside metadata.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A compact imperative reframes an accepted condition. | 4–6 words | “Make the new normal” |
| Support | Two simple linked thoughts move from change to possibility. | 10–16 words | “How we work is changing shape. So is what’s possible.” |
| Chapter heading | A short activity phrase that reads like an editorial title. | 3–5 words | “Design in public” |
| Proof paragraph | A specific factual sentence followed by its implication for the work. | 20–30 words | “Every 26 seconds, a merchant makes their first sale on Shopify. That kind of scale changes the job and how we approach design.” |
| Contextual action | A short, plain destination name rather than a high-pressure command. | 2–4 words | “Our design philosophy” |
| Closing invitation | An inclusive imperative oriented toward what happens next. | 5–7 words | “Help shape what comes next” |

**Words and phrasing to use:** make; shape; work; possible; together; ideas; conversations; next

**Avoid:** revolutionary solution; supercharge; best-in-class; unlock limitless potential; hurry; !!!

**Rules:**

- Give each monumental line a simple grammatical idea; line breaks should intensify the thought rather than create a keyword pile.
- Use a concrete fact to earn a big graphic, and explain the consequence in ordinary language.
- Use uppercase for metadata and annotation, not for every headline or button.
- Let labels name the destination; keep the closing invitation warmer than the contextual navigation.

## Do's and Don'ts

### Do

- Set the opening at 220px/0.7 with -0.04em tracking on the desktop poster.
- Retain 48px side insets around the main gallery and footer.
- Mix tall and landscape media while keeping gallery gaps at 21.6px.
- Use 24px rounded outer cards and reserve broad shadows for the smaller inset media.
- Keep actions at 44px high with fully rounded ends.
- Pair 160px typographic statements with 13.5px mono annotations for the extreme scale contrast.
- Concentrate electric mint and acid yellow in individual resource cards on a white page.
- Finish with a 40px invitation, thin rule and a free-standing glossy object.

### Don't

- Do not use the declared serif fallback as the visual headline style; the letterforms are grotesk.
- Do not turn weight 500 display lettering into an extra-bold 800 treatment.
- Do not give every gallery tile an opaque text caption panel or a repeated CTA.
- Do not add resting box shadows to all gallery cards; their edge is only black at 0.04 alpha.
- Do not spread green, yellow or red-orange across full-page background bands.
- Do not replace mono rail markings with oversized rounded badges.
- Do not normalize the staggered word sculpture into a centered bulleted list.
- Do not enlarge the 44px action pills into dominant rectangular conversion blocks.

## Motion and responsive

### Motion

**Observed:**

- The visual sequence includes changing film content, a large dial scene with outline and filled numeral treatments, and a subtly tilted inset-media composition.
- The dial stage uses a sticky 900px-high viewport while its surrounding stage extends through a long scroll region.

**Transfer:**

- Keep the dial's giant scale legible as the scene changes; maintain meaningful static text alongside the spectacle.
- Use poster stills that retain the same material and framing when moving media is unavailable.

**Unknown:**

- Animation timings, easing curves and button hover/focus transitions are not specified.

### Responsive

**Observed:**

- The desktop composition uses a 1440px maximum width, ten-column display alignment and a three-column media gallery.

**Transfer:**

- On narrow layouts, preserve the short two-line poster silhouette with fitted type, reduce gallery columns and keep the media-first hierarchy.
- Let the editorial strip retain a partial next card; scale the word sculpture and annotations together while allowing intentional line breaks.
- Keep the final invitation before its sculptural counterweight in the reading order.

**Unknown:**

- Mobile breakpoints, exact smaller-screen type sizes and touch interaction details are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
