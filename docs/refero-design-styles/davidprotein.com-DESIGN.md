# David — sculptural appetite and discipline

## Overview

A dark, aspirational retail style that pairs the elegance of narrow editorial serifs with utilitarian sans and monospace details. Black stages, white interruptions and restrained gray panels frame glossy studio products, tactile ingredients and tightly cropped human photography. It suits physical products with a performance story, balancing spacious brand scenes with dense, practical shopping information.

### Essentials

- Editorial elegance sits over athletic imagery: regular Instrument Serif headlines at 45px/1.05 with 0.01em tracking, not oversized bold sans slogans.
- The opening is a cinematic product encounter: a full-width 701px image stage below a 109px header, with a compact lower-left promise and two white 45px pill actions.
- Black owns the long-form brand story: #000000 canvas and #161616 cards dominate; white discovery and information bands interrupt it. Saturated color belongs mainly to the products and photography, with #ff6900 restricted to 27px status labels.
- Products look like precious objects rather than thumbnails: isolated packs sit in generous charcoal fields; editorial scenes use reflective floors, rim lighting and ingredient sculpture. Use a carefully lit single-object still life when elaborate photography is unavailable.
- Technical credibility is deliberately small: 12px/1.4 mono captions and 14px/1 mono actions sit beside 35–50px regular serif headings; a thin 40px benefit ticker supplies a dense contrasting rhythm.
- A monumental typographic sign-off anchors the ending: a muted gray wordmark fills a 1300px-wide, 449px-tall field after the useful footer. Recreate this with the new identity as vector lettering rather than a conventional small footer logo.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Edition orange | `#ff6900` | `--color-orange` | surface, accent | Small limited-edition badges; not a general CTA color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, action | Primary text on black, white pill actions, discovery bands and testimonial cards. |
| Warm pale canvas | `#f7f5f5` | `--color-paper` | background, surface | Product purchase canvas and small numbered FAQ chips; also primary-button hover. |
| Warm badge | `#e5deca` | `--color-badge` | surface | New and shipping-status chips. |
| Soft white | `#dcdcdc` | `--color-soft-text` | text, border | Expert descriptions and dashed FAQ separators. |
| Cool review edge | `#d7dae4` | `--color-review-edge` | border | Fine outline around white testimonial cards. |
| Selected tab edge | `#909090` | `--color-tab-edge` | border, text | Selected segmented-control outline and inactive labels on black. |
| Medium gray | `#6e6e6e` | `--color-muted` | text, surface, border | Secondary text on white, inactive catalog categories and active education tabs. |
| Dark tab track | `#202020` | `--color-tab-track` | surface | Segmented controls on black. |
| Charcoal card | `#161616` | `--color-card` | surface | Product and expert cards on the black stage. |
| Stage black | `#000000` | `--color-black` | background, text, action | Default marketing canvas; text and purchase actions on light sections. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Focus violet | `#1a00ff` | `--color-focus` | border | Declared focus-visible outline on primary actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product detail pages | Gallery gray | `#efeded` | `--color-gallery` | surface | Product gallery backing and guarantee panel. |
| testimonial carousels | Review link blue | `#0042e4` | `--color-review-link` | link | Read-more text within white testimonial cards. |

## Typography

- **Instrument Serif** — Marketing headlines, editorial card titles and catalog category navigation. Tall, narrow, high-contrast editorial serif with expressive curved terminals. Font stack: "Instrument Serif", Georgia, serif.
- **Suisse International** — Descriptions, navigation, product names and shopping information. Restrained neo-grotesk, mostly regular with subtly open tracking. If unavailable, use **Inter**. Use 400 and 450; retain the 0.01em tracking. Font stack: "Suisse International", "Inter", Arial, sans-serif.
- **ABC Monument Grotesk Mono** — Actions, eyebrows, serial numbers and small technical captions. Plain mechanical monospaced lettering that counterbalances the serif. If unavailable, use **IBM Plex Mono**. Use regular weight for brand labels and buttons. Font stack: "ABC Monument Grotesk Mono", "IBM Plex Mono", ui-monospace, monospace.
- **Work Sans** (only for testimonial carousels) — Customer quotation titles and text. Friendly utilitarian sans distinct from the brand editorial typography. Font stack: "Work Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading-lg | Instrument Serif | 400 | 50px | 1.1 | 0.01em | size min(max(40px, 3.47222vw), 50px) | Centered authority or educational statement. |
| display | Instrument Serif | 400 | 45px | 1.05 | 0.01em | size min(max(35px, 3.125vw), 45px) | Default hero promise, split promotional heading and FAQ title. |
| heading | Instrument Serif | 400 | 40px | 1.05 | 0.01em | fixed | Product rail heading and compact proof chapter title. |
| heading-sm | Instrument Serif | 400 | 35px | 1.05 | 0.01em | size min(max(25px, 2.43056vw), 35px) | Category image labels and ruled benefit titles. |
| product-name | Suisse International | 400 | 18px | 1.35 | 0.01em | size min(max(16px, 1.25vw), 18px) | Product and expert names; newsletter invitation. |
| body | Suisse International | 400 | 16px | 1.4 | 0.01em | size min(max(14px, 1.11111vw), 16px) | Promotional bullet copy and FAQ questions. |
| body-sm | Suisse International | 400 | 14px | 1.4 | 0.01em | size min(max(12px, 0.972222vw), 14px) | Hero support, metadata, navigation and compact descriptions. |
| utility | ABC Monument Grotesk Mono | 400 | 14px | 1 | normal | size min(max(12px, 0.972222vw), 14px) | Pill actions and underlined editorial links. |
| footer-link | Suisse International | 400 | 14px | 18px | 0.01em | size min(max(12px, 0.972222vw), 14px) | Footer column links. |
| answer | Suisse International | 400 | 14px | 20px | 0.01em | size min(max(12px, 0.972222vw), 14px) | Muted expanded FAQ answer. |
| caption | ABC Monument Grotesk Mono | 400 | 12px | 1.4 | normal | size min(max(12px, 0.833333vw), 12px) | Eyebrows, status labels and numbered chapters. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| product detail review sections | review-display | Instrument Serif | 400 | 56px | 1.4 | 0.01em | fixed | Centered invitation above the detailed rating and review list. |
| product detail pages | purchase-title | Suisse International | 450 | 22px | 1.35 | 0.01em | fixed | Functional product title above purchase options. |
| testimonial carousels | review-title | Work Sans | 500 | 18px | 25px | 0.01em | fixed | Customer quotation heading. |
| product detail pages | purchase-body | Suisse International | 400 | 15px | 1.4 | 0.01em | fixed | Sensory description beside the product gallery. |
| testimonial carousels | review-body | Work Sans | 400 | 14px | 24px | 0.01em | size min(max(12px, 0.972222vw), 14px) | Customer quotation body and read-more link. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Serif headings stay regular and slightly positively tracked; their narrow construction supplies grandeur without giant font sizes.
- Monospace is a utility counterpoint, not the body face. Keep sentence case on most brand labels; dense review tools have their own more mechanical treatment.
- Use one compact paragraph or a short stack of bullet lines beside the serif; do not enlarge supporting text to compete with the object.

## Layout

**Density:** Airy brand scenes alternate with compact shopping metadata and utility bands.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Tight metadata stacks and education tab gutters. |
| 10px | Product-rail gutters and eyebrow-to-heading spacing. |
| 15px | Footer link gaps and compact supporting stacks. |
| 20px | Product card padding, rail side gutters and button inline padding. |
| 24px | Testimonial card padding and testimonial rail gaps. |
| 30px | Benefit-stack gaps and compact section padding. |
| 40px | Proof-section vertical padding and ticker height. |
| 70px | Editorial inset, centered statement padding and footer row separation. |
| 80px | Large internal promotional separation. |
| 100px | FAQ vertical padding and proof-column separation. |
| 140px | Footer opening space. |

### Containers and grids

- **editorial**: max width 1300px · side padding 70px. Desktop proof and footer content span the viewport less generous equal side margins.
- **rails**: gap 10px · side padding 20px. Edge-near horizontal discovery and product rails; show the next item clipped at the right.
- **faq**: max width 1280px · 2 columns · gap 0px. A left heading and link balance a 640px question column on the right.
- **proof**: 2 columns · gap 100px. A 750px visual field on the left balances a 400px editorial stack on the right.
- **footer-columns**: 4 columns · gap 45px. Four narrow utility columns sit beside the newsletter block, separated from it by 113px.
- **catalog** (only for collection pages): 3 columns · gap 8px · side padding 20px. Dense three-column charcoal product grid; card heights accommodate different object shapes.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 9999px (pill) |
| product cards | 5px |
| testimonial cards | 6px |
| status chips | 2px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| carousel arrow | `0px 0px 18px rgba(28,29,33,0.12), 0px 6px 6px rgba(28,29,33,0.06)` | White testimonial carousel controls only. |

### Surfaces

#### Black stage · level 0

**Use:** Default marketing canvas and full-width feature bands.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Scenes and panels meet without decorative section dividers.

**Transfer:** Let imagery and alternating density distinguish chapters.

#### Charcoal panel · level 1

**Use:** Isolated product and authority content.

**CSS:** `background: #161616; border-radius: 5px; box-shadow: none`

**Observed:** A subtle value difference from black, not a floating elevated card.

**Transfer:** Reserve the panel for a clear unit of merchandise or proof.

#### White interruption · level 0

**Use:** Discovery, FAQ and detailed review bands.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Full-width hard change from the black environment.

**Transfer:** Use white for a useful browsing or explanation moment, not every alternate section.

#### Photo label scrim

**Use:** Category tile readability.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0) 70.91%, rgba(0, 0, 0, 0.6) 100%)`

**Observed:** Darkening stays at the bottom of an otherwise vivid full-frame still life.

**Transfer:** Preserve product lighting while supporting the white serif title.

#### Purchase canvas · level 0

**Only for:** product detail pages

**Use:** Product gallery and purchase configuration.

**CSS:** `background: #f7f5f5; color: #000000`

**Observed:** Gallery sits on a warmer gray backing while most controls remain pale and low contrast.

**Transfer:** Keep commerce practical and calm before returning to black editorial storytelling.

## Components

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `background: #ffffff; color: #000000; border-radius: 9999px; padding: 0px 20px; height: 45px; display: inline-flex; align-items: center; justify-content: center; gap: 10px`

**Text style:** `utility` — ABC Monument Grotesk Mono 400 · 14px/1

**Observed:** Short sentence-case mono label, normally one or two adjacent pills. Purchase pages invert to black on the pale canvas; an outlined white-on-black version is used for the secondary newsletter channel.

**States:** Declared: hover background #f7f5f5, black text and no text decoration; focus-visible solid #1a00ff outline with width and offset controlled by variables.

**Transfer:** Use the white version as the default on dark editorial stages.

### Navigation

**Use:** Compact global shopping and identity strip.

**CSS:** `height: 69px; padding: 0px 20px; display: grid; align-items: center; gap: 30px; background: #000000; color: #ffffff; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.2), inset 0px -1px 0px rgba(255,255,255,0.2)`

**Text style:** `body-sm` — Suisse International 400 · 14px/1.4 · tracking 0.01em

**Observed:** Small serif identity at left, shopping links immediately beside it, locator and business links plus search, account and white cart pill at right. A separate 40px announcement strip completes the 109px opening header.

**Transfer:** Keep the identity and navigation subordinate to the hero.

### Product card

**Use:** Merchandise rail and catalog item.

**CSS:** `background: #161616; border-radius: 5px; padding: 20px; display: flex; flex-direction: column; gap: 5px; overflow: hidden`

**Text style:** `product-name` — Suisse International 400 · 18px/1.35 · tracking 0.01em

**Observed:** Large centered object above bottom-aligned category dot and mono label, sans name, price and pack count. Eye-shaped quick-view and white circular plus controls occupy the lower right. Marketing rails use 606px by 368px landscape cards with 10px gutters; catalogs use three narrower columns.

**Transfer:** Use a transparent packshot and leave enough charcoal around it to read as a display case.

### Status chip

**Use:** Newness, shipping and limited-edition flags.

**CSS:** `background: #e5deca; color: #000000; border-radius: 2px; padding: 5px; height: 27px; display: flex; align-items: center`

**Text style:** `caption` — ABC Monument Grotesk Mono 400 · 12px/1.4

**Observed:** Small rectangular flags sit at the image's upper left. Limited editions invert to white text on orange; sold-out labels are outlined and have no bright fill.

**Transfer:** Keep labels factual and visually minor.

### Editorial link

**Use:** Small secondary actions within dark chapters.

**CSS:** `color: #ffffff; border-bottom: 1px solid #ffffff; padding: 0px 0px 5px; display: inline-flex; align-items: center`

**Text style:** `utility` — ABC Monument Grotesk Mono 400 · 14px/1

**Observed:** The rule is a separate bottom border rather than an oversized call-to-action. On white explanatory sections, use black text and a black rule.

**States:** Declared: hover removes text decoration and changes the border to black; focus-visible removes text decoration.

### Segmented control

**Use:** Two ways of viewing the same product proof or promotion.

**CSS:** `background: #202020; border-radius: 9999px; height: 46px; display: flex; align-items: center`

**Text style:** `body-sm` — Suisse International 400 · 14px/1.4 · tracking 0.01em

**Observed:** Two equal segments; active segment is #161616 with a 1px #909090 pill outline. Labels are small sans text; inactive text is muted. The proof variant is 400px wide.

**Transfer:** Use only when both views change the same visual or offer; do not turn all headings into tabs.

### Testimonial card

**Use:** Bright social proof against black.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #d7dae4; border-radius: 6px; padding: 24px; width: 400px; height: 322px; display: flex`

**Text style:** `review-body` — Work Sans 400 · 14px/24px · tracking 0.01em

**Observed:** Reviewer and verification at top left, date at top right, brown stars, medium-weight review title, short quote, then a small product image and product link at bottom. Cards sit in a clipped rail with 24px gaps and white circular arrow controls; read-more links are blue.

**Transfer:** Retain the bright rectangular proof-card silhouette even for non-retail testimonials.

### FAQ row

**Use:** Objection handling in a white two-column section.

**CSS:** `border-bottom: 1px dashed #dcdcdc; position: relative`

**Text style:** `body` — Suisse International 400 · 16px/1.4 · tracking 0.01em

**Observed:** Numbered mono chip at left, question in the middle, small chevron at right. Closed rows are about 86px tall; an open answer uses muted 14px/20px text and 30px bottom space. First question is shown expanded.

**Transfer:** Number the questions and keep answers visually secondary.

### Footer link

**Use:** Support, company, partnership and legal navigation.

**CSS:** `color: #ffffff; display: block; text-decoration: none`

**Text style:** `footer-link` — Suisse International 400 · 14px/18px · tracking 0.01em

**Observed:** Four narrow columns with mono group labels and 15px vertical link gaps; social symbols and legal utility rows follow below.

**States:** Declared: hover text-decoration underline.

### Education tab

**Only for:** education and explainer pages

**Use:** Chapter selection above a large video poster.

**CSS:** `background: #6e6e6e; color: #ffffff; border-radius: 5px; padding: 16px 20px; display: flex; flex-direction: column; gap: 13px; height: 86px`

**Text style:** `product-name` — Suisse International 400 · 18px/1.35 · tracking 0.01em

**Observed:** Four numbered tabs in one row with 5px gaps; active tab is medium gray, inactive tabs charcoal. Small plus/minus markers align at upper right, mono number above sans label.

**Transfer:** Use for genuinely chaptered demonstrations, not as an ordinary landing-page feature grid.

## Imagery and graphics

### Human product encounter

**Use:** Default full-bleed marketing opening.

**Observed:** A dramatically cropped torso, mouth and hand hold a partially opened metallic pack in a black studio. Soft directional highlights reveal skin and foil texture while edges disappear into near-black; the object occupies the center and the copy stays lower left.

**Transfer:** Photograph the new product in an intimate human interaction with low-key lighting. Minimum version: a large tactile object close-up against black, with one strong rim light and enough dark space for the caption.

### Ingredient sculpture

**Use:** Discovery tiles and editorial product scenes.

**Observed:** Cookies stack vertically beside a diagonal foil pack; a cream stream pours from a tipped bottle into a glass; a whisk carries a sculptural peak of chocolate; a tilted dessert tub balances over a stemmed cup. Full-bleed 336px by 416px tiles use black-to-gray spotlight backings or desaturated teal, glossy reflections and sharp material detail.

**Transfer:** Pair one product with one related material or use-context object. Compose with deliberate tilt, balance or a suspended gesture rather than a flat ingredient collage.

**Build:** For a minimal still-life stage, place a transparent object cutout over a dark neutral field. Add an elliptical white radial gradient at 35% opacity behind the object, about 85% of tile width; use a bottom reflection as a vertically flipped duplicate with a fading alpha mask and low opacity. Place the Photo label scrim above the art and the serif title above that.

### Precious packshot

**Use:** Product cards and product detail galleries.

**Observed:** Metallic gold and bronze packs are horizontal and centered in the charcoal cards; bottles and tubs stand vertically with generous surrounding space. Detail photography adds a desaturated blue-green horizon glow and a reflective floor behind a single upright bottle.

**Transfer:** Maintain honest material texture, restrained saturation and large object scale. For a product without packaging, photograph its defining form or a simple material sample on the same carefully lit stage.

### Authority portrait

**Use:** Expert or contributor proof.

**Observed:** Chest-up portraits against black sit beside matching charcoal text panels. Faces remain naturally colored and clearly lit; the image and compact text split a 700px by 269px card.

**Transfer:** Use real people with simple dark wardrobe or professional context; pair credentials with a small editorial link.

### Community video rail

**Use:** Human experience proof.

**Observed:** A centered serif invitation sits above a horizontal series of upright user videos, mixing real homes and close-up faces. White shopping strips appear beneath the clips.

**Transfer:** Use believable handheld demonstrations rather than replacing all photography with polished studio material. Give the rail the same dark surrounding stage.

### Quantified comparison

**Use:** A data-backed proof chapter.

**Observed:** A black chart field displays upright comparison bars; the leading bars glow blue and olive-gold downward into black, while secondary bars are outlined. White percentages hover above, tiny product images anchor the baseline, and compact methodology text stays below. A serif benefit stack occupies the right.

**Transfer:** Use only defensible comparisons. Preserve the luminous leading bar, thin chart rules and small technical labeling; a simple SVG chart is sufficient.

**Build:** Draw a baseline, thin gray horizontal ticks and outlined rectangular bars in SVG. Fill the primary bar with a vertical saturated blue-to-transparent gradient and the secondary bar with an olive-gold-to-transparent gradient, each fading to the black stage. Put the value above each bar and a small representative object below; avoid decorative grid backgrounds.

### Monumental closing identity

**Use:** Every page ending after utility navigation.

**Observed:** A huge muted gray serif wordmark occupies a 1300px by 449px artwork field on black with 70px side insets. Its lower edge meets the end of the page; open black space above separates it from the legal details.

**Transfer:** Use the new project's own wordmark or an elegant vector-set identity spanning the same near-full width. A word-based business can use custom-spaced serif lettering as the minimum version.

**Build:** Create an SVG with a wide viewBox fitted to the identity, set one word in tall high-contrast serif lettering, convert to outlines if possible, and fill with medium gray. Size the SVG to the content width with its aspect ratio preserved; place it after a deep black spacer, never in a boxed card.

### Icons

**Observed:** Small outline search, account, eye and chevron utilities accompany solid circular plus controls and arrows. Testimonial stars are brown; navigation icons are monochrome and discreet.

**Transfer:** Choose thin functional outline SVGs for navigation and chevrons; keep the round plus as the more visible commerce affordance. Avoid illustrative icon grids.

## Section recipes

How recurring sections are built.

### First screen: Cinematic product opening

**Observed:** A 40px announcement strip and 69px Navigation sit above a 701px full-width image stage. Back to front: black field, edge-to-edge low-key Human product encounter, then a lower-left compact text cluster inset 70px. The hero promise uses display at 45px, followed by a 14px support line and two Primary buttons; three thin 40px progress marks sit below. The human and product fill the center and right rather than yielding half the frame to text. Within the first 900px the complete headline, support, both actions, main object, 40px benefit ticker and the start of a light discovery band are visible; the discovery heading and tiles continue below.

**Transfer:** Make the opening a single strong encounter with the new object, using the minimum dark object still life if a human scene is unavailable. Keep copy compact in a low corner, not stretched across the object. Product detail pages instead open with a 676px square gallery on the left and a 514px purchase column on a pale canvas; collection pages use a short photographic banner and large serif category links; education pages use a centered serif promise and support line on black.

**Avoid:** Do not substitute a white SaaS-style hero, giant bold sans headline, gradient pill, or a small product thumbnail isolated beside a large text column.

**Text style:** `display` — Instrument Serif 400 · 45px/1.05 · tracking 0.01em

### Benefit ticker

**Observed:** A full-width 40px band repeats compact shipping, satisfaction or product-benefit phrases with dot separators. The black version uses pale text; a pale version interrupts the dark proof sequence.

**Transfer:** Include the dense ticker device with a few genuine product or service benefits; place it where it can punctuate larger scenes.

### Discovery gallery

**Observed:** White interruption with a 40px serif heading, compact arrows at top right and a clipped row of 336px by 416px Ingredient sculpture tiles. Gaps are 10px; each tile has a white 35px serif label low in frame, Photo label scrim and occasional Status chip.

**Transfer:** Show several meaningful ways into the range through material-led images, not ordinary feature icons.

**Text style:** `heading` — Instrument Serif 400 · 40px/1.05 · tracking 0.01em

### Split offer stage

**Observed:** Black full-width composition with a centered text and action group on the left and a large studio or context photograph on the right. The offer heading is 45px serif with 16px bullet support and a white Primary button. A Segmented control can switch the offer; scenes use a nearly half-width image, including reflective stacks or a carefully arranged refrigerator interior.

**Transfer:** Pair one tangible offer or usage benefit with a large specific image; keep the text vertically centered and short.

**Text style:** `display` — Instrument Serif 400 · 45px/1.05 · tracking 0.01em

### Merchandise rail

**Observed:** Black stage with optional 12px mono eyebrow, a 40px serif heading at the left and Editorial link plus arrows at right. Product cards form a clipped horizontal rail with 10px gutters and 20px outer padding.

**Transfer:** Use for variants or related offers while retaining large isolated objects and bottom-aligned metadata.

**Text style:** `heading` — Instrument Serif 400 · 40px/1.05 · tracking 0.01em

### Authority panel pair

**Observed:** Centered 50px serif statement with 70px padding above and below, followed by two side-by-side Authority portrait cards with 10px gap. Names use product-name; supporting credentials use body-sm in soft white.

**Transfer:** Use a relevant expert, maker or independent authority; make the specific relationship clear.

**Text style:** `heading-lg` — Instrument Serif 400 · 50px/1.1 · tracking 0.01em

### Quantified proof and ruled benefits

**Observed:** A 750px visual field balances a 400px right column across a 100px gap inside 70px side insets. The right stack has a mono caption, 40px serif heading, Segmented control and three benefits separated by white 1px top rules with 14px top padding and 30px gaps. Each benefit uses a 35px serif title and small sans support.

**Transfer:** Use a product comparison, process diagram or measurable outcome as the visual; preserve the contrast between technical visualization and elegant verbal benefits.

**Text style:** `heading-sm` — Instrument Serif 400 · 35px/1.05 · tracking 0.01em

### White question desk

**Observed:** White interruption with 100px vertical padding and a centered 1280px two-column layout. Left: 45px serif heading and Editorial link 30px below. Right: numbered FAQ rows, with the first answer expanded.

**Transfer:** Use for purchase objections and practical details; allow the section height to follow the number of questions.

**Text style:** `display` — Instrument Serif 400 · 45px/1.05 · tracking 0.01em

### Bright testimonial rail

**Observed:** White Testimonial cards cross the black stage with 24px gutters and partial cards clipped at both sides. The full band is about 462px tall with ample black space around the 322px cards.

**Transfer:** Use a concise authentic quote per card. Detailed product review pages instead use a white review desk, a centered 56px serif invitation, rating distribution, filters and ruled full-width review rows.

**Text style:** `review-title` — Work Sans 500 · 18px/25px · tracking 0.01em

### Utility then monument ending

**Observed:** A black footer begins with 140px of space. Newsletter invitation, Email/SMS pills and a discreet email field occupy the left; four Footer link columns occupy the right, separated from the newsletter by 113px. Social and privacy details follow. After a substantial black pause, Monumental closing identity spans 1300px inside 70px insets; the complete footer is 1174px tall.

**Transfer:** Preserve both useful navigation and the oversized identity sign-off. Adapt column labels and newsletter invitation to the business rather than replacing this ending with a generic CTA card.

### Chaptered education

**Only for:** education and explainer pages

**Observed:** A centered 50px serif statement and short 14px support open on black with 70px vertical breathing room. Four Education tabs sit above a wide 1382px by 777px video poster with a dark portrait-led composition and translucent circular play control.

**Transfer:** Adapt to the new product's chapters and demonstrations; let the poster carry the editorial scale rather than making the tabs decorative.

**Text style:** `heading-lg` — Instrument Serif 400 · 50px/1.1 · tracking 0.01em

## Page flow

**Storyline:** Sensory promise → browse or configure → staged product benefit → human and quantified credibility → practical reassurance → useful navigation and monumental identity.

### Brand-led marketing and discovery

1. **Promise** — Cinematic object encounter, compact offer and benefit ticker.
2. **Product discovery** — Light editorial gallery, dark split offer and merchandise rail.
3. **Credibility** — Authority portraits, community videos and a luminous comparison beside ruled benefits.
4. **Social proof** — Bright testimonial rail.
5. **Closing identity** — Newsletter and utility columns followed by the enormous gray identity.

**Transfer:** Default to a dark sensory landing page with both tactile media and compact technical credibility; reorder chapters around the new offer.

### Focused product selection and purchase

1. **Configuration** — Pale gallery-and-purchase opening with ratings, title, description, plan selector and inverted action.
2. **Product demonstration** — Thin benefit ticker and black split image stage.
3. **Related discovery** — Dark merchandise rail.
4. **Objection handling** — White numbered FAQ desk.
5. **Social proof** — Centered serif invitation, rating histogram, filters and long ruled review list.
6. **Closing identity** — Shared black utility footer and monumental sign-off.

**Transfer:** Use the pale commerce variant when selection and recurring purchase decisions matter; retain the black editorial chapter after the practical opening.

### Range browsing

1. **Promise** — Short full-width dark photographic banner with centered editorial identity.
2. **Product discovery** — Large serif category navigation and dense three-column charcoal merchandise grid.
3. **Progress** — Compact pagination and viewed-item count.
4. **Social proof** — White testimonial cards on black.
5. **Objection handling** — White numbered FAQ desk.
6. **Closing identity** — Shared utility footer and monumental sign-off.

**Transfer:** Prioritize object visibility and category navigation; keep the emotional banner brief.

### Education and product rationale

1. **Promise** — Centered regular-serif statement with one short support line on black.
2. **Capability chapters** — Four numbered tabs above a large portrait-led video poster.
3. **Authority** — Contributor portrait with credentials and biography link.
4. **Product discovery** — Dark merchandise rail.
5. **Social proof** — Bright testimonial rail.
6. **Closing identity** — Shared black utility footer and monumental sign-off.

**Transfer:** Make the new product's explanation navigable through chapters while keeping a short path back to the offer.

## Writing

Confident, disciplined and sensual in equal measure. Brand language is terse and aspirational, while product descriptions are tactile and support answers are direct and practical.

**Do not copy:** Do not reuse the David identity, packaging artwork, expert names, customer quotations, nutrition numbers, review counts, guarantees or promotional claims. Replace them with the new project's own assets and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct action verbs and occasional you/your for the customer; we/our appears mainly in support and product reassurance.
- **Rhythm:** Headlines usually run three to eight words with a period. Parallel clauses, short declarative support and compact bullet lists carry the brand story; long prose belongs in answers, not hero copy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A simple category reframing in one short sentence. | 4–7 words | “Protein has a new bar.” |
| Support | A short sensory payoff joined to an aspirational idea. | 4–8 words | “Discipline never tasted so good.” |
| Authority heading | Two parallel claims, each with its own period. | 6–10 words | “Built on science. Backed by partners.” |
| Primary action | Plain shopping verb or a first-person ownership action. | 2–4 words | “Build my bundle”<br>“Shop all” |
| Product description | Sensory adjective triad followed by a concrete experience. | 1–2 sentences | “Rich, smooth, and cocoa-forward. A chocolate milkshake worth savoring, velvety and satisfying down to the last sip.” |
| Review invitation | Hand the authority to the customer in balanced clauses. | 4–6 words | “Your words, not ours.” |

**Words and phrasing to use:** discipline; form; excellence; foundation; satisfying; smooth; built; backed; tools; straightforward action verbs

**Avoid:** game-changing; revolutionary platform; unlock your potential; cute food puns; luxury superlatives without product detail

**Rules:**

- Pair a sensory promise with a concrete product fact rather than adding another abstract slogan.
- Use periods in editorial headlines and sentence case in actions.
- Keep proprietary brand language out of practical answers; address storage, delivery or use plainly.
- Keep enthusiasm and irregular punctuation inside authentic customer quotations rather than polishing it into the brand voice.

## Do's and Don'ts

### Do

- Keep serif marketing headings regular at 35–50px with 0.01em tracking.
- Use 45px white pill actions on the default black stage.
- Keep product rails close to the viewport edges with 20px side gutters and 10px gaps.
- Give charcoal cards a restrained 5px radius and no elevation shadow.
- Use 12px mono captions to carry proof labels and chapter numbers.
- Use a white full-width information band rather than a pale floating FAQ card.
- Let the closing identity fill the 1300px content width after the utility footer.

### Don't

- Do not make orange the main CTA fill; it belongs to small edition flags.
- Do not put Work Sans throughout the brand story; it is the testimonial-carousel voice.
- Do not apply the 6px testimonial outline treatment to every dark product card.
- Do not turn 45px pills into oversized 64px promotional buttons.
- Do not center all editorial text; proof stacks and product-rail headings remain left aligned.
- Do not add soft colored shadows beneath merchandise; the lift comes from lighting inside the imagery.
- Do not compress the monumental footer into a narrow legal bar.
- Do not use pastel gradients as a substitute for tactile materials and low-key studio lighting.

## Motion and responsive

### Motion

**Observed:**

- Declared: primary action background, color, border-color and opacity transition over .15s ease-in-out.
- Declared: header transform-related transitions use .7s cubic-bezier(.4,0,.2,1).
- Declared: active proof-pill opacity and colors transition over 0.3s cubic-bezier(.4,0,.2,1).
- Declared: education-tab color transitions use 0.5s cubic-bezier(.4,0,.2,1).

**Transfer:**

- Keep hover feedback tonal rather than enlarging the pill buttons.
- Retain visible progress marks for the cinematic carousel and arrow controls for object rails.

**Unknown:**

- Automatic slide timing, video playback behavior and scroll-trigger choreography are not specified.

### Responsive

**Observed:**

- Headline formulas clamp the default display between 35px and 45px; the centered authority heading between 40px and 50px; compact serif labels between 25px and 35px.
- Declared layout breakpoints include 640px, 768px, 1024px and 1280px. Education desktop content has a separately hidden narrow-screen variant.

**Transfer:**

- On narrow layouts, retain clipped horizontal object rails rather than squeezing all tiles into one row.
- Stack proof and purchase columns while preserving the object's prominence and readable compact copy.
- Keep the closing identity near full width with its aspect ratio intact.

**Unknown:**

- Exact mobile hero composition, navigation replacement and education-tab behavior are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
