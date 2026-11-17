# Parallel — cinematic human potential

## Overview

An editorial, human-centered style that pairs expressive narrow serifs with matter-of-fact sans-serif interfaces. Warm ivory and near-black hold the page together, with orange used like a small ember and cinematic photography supplying the richer color. Spacious compositions, softly floating product fragments, and sculptural symbols make it suited to products about personal progress, discovery, or thoughtful professional tools.

### Essentials

- A literary promise sits inside a cinematic scene: white Advercase Demo at 100.8px, weight 400, 1.14 line height and -0.03em tracking, centered over almost a full viewport of photography with an 8px outer inset and 16px corners.
- The action feels like a bright instrument inside the scene: a 514px-wide translucent search well, 5px glass rim, 15px white inner corners and a 38px orange-gradient circular submit control; other buttons are compact 10–12px rounded rectangles rather than universal pills.
- Color belongs to people and moments, not the whole interface: long #f9f9f9 and #f4f3f1 fields surround photographic color; #ef6e07 to #ffb77d is concentrated in tiny action controls, while business-oriented variants use a #161616 canvas.
- Product explanations appear as small floating arrangements, not dense dashboards: three roughly 418px-wide cards with 20px corners, pale white gradient fills, a 248px-tall illustration zone and 32px text insets.
- A sculptural identity interrupts the explanation: a tone-on-tone beveled emblem sits between a 60px serif statement at upper left and a 372px-wide support column at lower right. Use a simple extruded geometric symbol when no equivalent artwork exists.
- The ending has architectural scale: compact four-column navigation above a full-content-width wordmark, 1280px wide and 369px tall at desktop, with 90px of separation after the navigation content. Every new page retains this monumental typographic finish using its own name.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ember | `#ef6e07` | `--color-orange` | action, accent | Upper stop of small submit gradients and business action focus rings. |
| Peach light | `#ffb77d` | `--color-peach` | accent, action | Lower stop of the orange submit gradient. |
| Live signal | `#ff8210` | `--color-live` | accent | 8px glowing availability dot. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, border | Hero lettering, bright panels, glass and translucent hairlines. |
| Input white | `#fdfdfd` | `--color-input` | surface | Opaque inner search surface, distinct from translucent white rims. |
| Warm base | `#fbfaf9` | `--color-canvas` | background | Underlying warm page base. |
| Cool mist | `#f9f9f9` | `--color-mist` | background | Feature-card and discovery bands. |
| Warm stone | `#f4f3f1` | `--color-stone` | background, surface | Editorial symbol sections and the default footer. |
| Light separator | `#e2e1e0` | `--color-light-rule` | border | Visible 8% dark separator over warm stone, built with rgba(23,23,23,0.08). |
| Warm gray labels | `#999694` | `--color-footer-muted` | text | Footer category labels and secondary metadata. |
| Muted ink | `#72716f` | `--color-muted` | text | Visible supporting copy made with rgba(5,5,5,0.56) on warm stone; use the alpha recipe to adapt to adjacent pale fields. |
| Card link ink | `#232323` | `--color-link-ink` | text, link | Semibold card actions. |
| Button charcoal | `#1f1f1f` | `--color-button` | action, surface | Compact dark editorial action. |
| Primary ink | `#050505` | `--color-ink` | text | Headings on pale fields; 88% alpha for softer editorial statements and 72% for links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| business and long-form editorial pages | Night canvas | `#161616` | `--color-dark` | background | Full-page dark canvas. |
| business and long-form editorial pages | Raised night panel | `#202020` | `--color-dark-panel` | surface | Raised services panel and 4% white card surfaces over night. |
| dark pages | Night hairline | `#292929` | `--color-dark-rule` | border | 8% white edges over night. |
| dark pages | Night supporting text | `#989898` | `--color-night-muted` | text | 56% white support text over night. |
| assessment and category explorers | Forest light | `#42583c` | `--color-forest` | surface | Top of the identity-card gradient. |
| assessment and category explorers | Forest middle | `#243422` | `--color-forest-mid` | surface | Middle of the identity-card gradient. |
| assessment and category explorers | Forest shadow | `#0a110a` | `--color-forest-deep` | surface | Dark lower corner of the identity card. |

## Typography

- **Advercase Demo** — Expressive headlines and section titles. Narrow high-contrast serif with long, lively terminals and tightly joined word shapes. If unavailable, use **Instrument Serif**. Use regular weight; tune wrapping before changing the tight tracking. Font stack: "Advercase Demo", "Instrument Serif", Georgia, serif.
- **ui-sans-serif** — Navigation, feature titles, supporting copy and footer links. Neutral system grotesk, chiefly regular and medium. Font stack: "ui-sans-serif", system-ui, sans-serif.
- **__Inter_8a0ba0** — Editorial support copy and semibold text actions. Direct contemporary sans with a high x-height. If unavailable, use **Inter**. Font stack: "__Inter_8a0ba0", "Inter", system-ui, Arial, sans-serif.
- **__rulesFont_d96771** (only for dark editorial prose and testimonials) — Long centered narrative and customer quotations. Soft, compact grotesk with close-set sentence shapes. If unavailable, use **Inter**. Font stack: "__rulesFont_d96771", "Inter", system-ui, Arial, sans-serif.
- **Instrument Serif** (only for assessment and category explorers) — Category names and identity-card titles. Delicate narrow editorial serif, lighter and more restrained than the main display face. Font stack: "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Advercase Demo | 400 | 100.8px | 1.14 | -0.03em | size clamp(72px, 7vw, 104px) | Centered photographic opening promise. |
| closing-heading | Advercase Demo | 500 | 64px | 1.05 | -0.02em | fixed | Two-line white headline on the photographic closing panel. |
| editorial-heading | Advercase Demo | 400 | 60px | 1.2 | -0.016em | fixed | Left-aligned two-line statement beside a sculptural symbol. |
| heading | Advercase Demo | 500 | 40px | 1.2 | -0.02em | fixed | Centered feature and explanatory section titles. |
| card-title | ui-sans-serif | 500 | 23px | 1.2 | -0.02em | fixed | Feature-card titles and short capability names. |
| editorial-body | __Inter_8a0ba0 | 500 | 20px | 1.4 | -0.02em | fixed | Narrow support column in symbol-led editorial sections. |
| body | ui-sans-serif | 400 | 17px | 1.4 | normal | fixed | Feature descriptions, generally two or three lines. |
| action | ui-sans-serif | 600 | 16px | 1.5 | normal | fixed | Navigation actions and inverse conversion buttons. |
| text-action | __Inter_8a0ba0 | 600 | 16px | 1.5 | normal | fixed | Semibold card actions with a right arrow. |
| button-label | __Inter_8a0ba0 | 500 | 16px | 1.5 | normal | fixed | Dark editorial buttons. |
| chip | ui-sans-serif | 500 | 14px | 1 | normal | fixed | Short photographic-hero filters. |
| footer-link | ui-sans-serif | 500 | 14px | 1.5 | normal | fixed | Footer links and uppercase category labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| long-form editorial pages | manifesto-display | Advercase Demo | 400 | 68px | 1 | -0.02em | fixed | Centered single-line statement above monochrome documentary media. |
| business landing pages | business-heading | Advercase Demo | 400 | 62px | 1.07 | -0.0226em | fixed | Centered capability, testimonial and FAQ headings. |
| assessment product pages | assessment-display | Advercase Demo | 400 | 60px | 1.1 | -0.03em | fixed | Two-line opening statement with a gray first line and dark second line. |
| long-form editorial pages | manifesto-close | ui-sans-serif | 500 | 57px | 1.1 | -0.02em | fixed | Sans-serif closing call inside a dark glass band. |
| assessment and category explorers | identity-title | Instrument Serif | 400 | 49px | 1.1 | normal | fixed | Large name in the lower part of a colored identity card. |
| business proof sections | quotation | __rulesFont_d96771 | 400 | 20px | 1.2 | normal | fixed | Customer quotations inside dark cards. |
| business FAQ sections | question | ui-sans-serif | 500 | 18px | 1.5 | normal | fixed | Accordion summary labels. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The serif carries the emotional promise; the sans-serif explains and operates. Do not make every paragraph serif.
- Tighten display tracking to -0.03em at the opening; most smaller serif headings use -0.02em. Keep body tracking normal except the Inter editorial support recipe.
- Preserve sentence case and natural contractions. Footer category labels are the small uppercase exception.
- The monumental footer name is graphic lettering rather than an extension of the headline scale; size it by its full-width silhouette.

## Layout

**Density:** Airy at section scale, with compact controls and closely grouped interface illustrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card title-to-description gap and hero filter spacing. |
| 12px | Search contents and dark proof-grid gaps. |
| 13px | Default three-card grid gap. |
| 16px | Footer link gaps and category-list spacing. |
| 24px | Support paragraph-to-action spacing and testimonial padding. |
| 28px | Opening headline-to-search separation. |
| 32px | Feature-card text insets. |
| 40px | Heading-to-card-grid separation and footer top padding. |
| 64px | Closing photographic panel inner inset. |
| 80px | Desktop content gutters and major section padding. |
| 120px | Feature explanation band top padding. |
| 150px | Desktop footer column separation. |

### Containers and grids

- **main container**: max width 1440px · side padding 80px. Centered outer container yielding 1280px of content at desktop.
- **feature grid**: 3 columns · gap 13px. Three equal explanation cards, each roughly 418px wide.
- **action column**: max width 514px. Centered search well; constrain it independently of the headline.
- **editorial support**: max width 372px. Narrow support copy at lower right, opposed to the upper-left heading.
- **business container** (only for business landing pages): max width 1195px · side padding 0px. Centered capability tabs, preview and three-card explanations; outer gutters are 122px at desktop.
- **faq column** (only for business landing pages): max width 800px. Centered single column for disclosure rows.
- **narrative column** (only for long-form editorial pages): max width 674px. Centered prose with 156px padding above and below narrative groups.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | hero | 16px |
|  | cards and closing media | 20px |
|  | dark buttons | 10px |
|  | inverse buttons | 12px |
|  | search interior | 15px |
|  | filters and submit | 9999px (pill) |
| business proof sections | testimonial cards | 12px |
| assessment and category explorers | identity card | 29px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| search rim | `0px 12px 36px rgba(0,0,0,0.18)` | Soft dark lift under the glass search well. |
| active audience | `0px 6px 27px rgba(0,0,0,0.07)` | Small lift under the white selected audience segment. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default marketing page and footer foundation.

**CSS:** `background: #f4f3f1`

**Observed:** The pale editorial field is slightly warmer and darker than the feature band.

**Transfer:** Keep neutral fields visibly distinct without turning them into alternating colored stripes.

#### Feature band · level 0

**Use:** Explanatory card sections.

**CSS:** `background: #f9f9f9`

#### Pale card · level 1

**Use:** Feature explanations.

**CSS:** `background: linear-gradient(rgba(255,255,255,0.77), rgba(255,255,255,0.88)); border: 2px solid rgba(255,255,255,0.56); border-radius: 20px`

**Observed:** Almost-white translucent surfaces have very little edge contrast; the illustration supplies the depth.

**Transfer:** Avoid adding a strong outline or a second heavy panel inside the card.

#### Photographic scrim · level 1

**Use:** White opening text over warm photography.

**CSS:** `background: linear-gradient(rgba(15,15,15,0.4), rgba(15,15,15,0.3), rgba(15,15,15,0.45))`

**Observed:** The image stays richly colored but dark enough for white letters and glass controls.

**Transfer:** Apply above the image and below all text.

#### Night canvas · level 0

**Only for:** business and long-form editorial pages

**Use:** Dark-page foundation.

**CSS:** `background: #161616; color: #ffffff`

#### Night card · level 1

**Only for:** business landing pages

**Use:** Feature and proof surfaces.

**CSS:** `background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.08); border-radius: 12px`

**Observed:** Proof cards use 12px corners; illustrated feature cards use 20px. Services form a larger #202020 panel with 32px corners and 120px 64px padding.

**Transfer:** Use the same low-contrast layering, not pitch-black cards on a brightly colored canvas.

#### Identity gradient · level 1

**Only for:** assessment and category explorers

**Use:** A selected category's tactile identity card.

**CSS:** `background: linear-gradient(153.271deg, #42583c 0%, #243422 46.218%, #0a110a 84.032%); border-radius: 29px; padding: 34px`

**Observed:** A small symbol sits high left, faint oversized line art occupies the upper right and the serif name anchors the lower left.

**Transfer:** Reserve this richer surface for the selected category rather than all explanatory cards.

## Components

### Glass navigation

**Use:** Persistent top navigation.

**CSS:** `position: fixed; top: 0px; height: 75px; width: 100%; z-index: 50; background: rgba(255,255,255,0.404); backdrop-filter: blur(13.4px)`

**Text style:** `action` — ui-sans-serif 600 · 16px/1.5

**Observed:** Logo and small dropdown at left, audience switch centered, sign-in and low-emphasis sign-up at right. Text is white over the opening image and becomes dark over pale content. The dark business version uses translucent charcoal; editorial navigation is 88px tall.

**Transfer:** Keep the central audience switch only when the product truly serves two distinct audiences.

### Audience switch

**Use:** Two related destination choices in the header.

**CSS:** `display: flex; position: relative; width: 228px; height: 40px; padding: 2px; border-radius: 14px; background: rgba(255,255,255,0.12)`

**Observed:** Two 112px-wide labels sit over a moving white selected segment, 36px tall with 12px corners and a subtle shadow. The pale product variant uses a 5% dark track.

**Transfer:** Use destination links with visible selected state rather than pretending this is an on-page filter.

### Search well

**Use:** Primary low-friction opening action.

**CSS:** `max-width: 514px; padding: 5px; border-radius: 20px; background: rgba(255,255,255,0.14); backdrop-filter: blur(12px); box-shadow: 0px 12px 36px rgba(0,0,0,0.18)`

**Observed:** Opaque #fdfdfd interior is 504px by 66px with 15px corners, 14px 20px padding and 12px between input and submit. The business variant uses a text submit capsule in place of the circular arrow.

**Transfer:** Use one meaningful entry field; without search, use the same bright action dock for one short input or a single next-step action.

### Ember submit

**Use:** Small high-salience action inside the search well.

**CSS:** `width: 38px; height: 38px; border-radius: 9999px; background: linear-gradient(#ef6e07, #ffb77d); display: flex; align-items: center; justify-content: center`

**Observed:** An 18px white line arrow is centered in the circle. The business version expands to a 104px by 44px capsule with a short verbal label.

**Transfer:** Keep the colored area small even when expanding for text.

### Glass filter

**Use:** Secondary shortcuts below the opening search.

**CSS:** `height: 36px; padding: 10px 16px; border-radius: 9999px; background: rgba(255,255,255,0.1); border: 1px solid rgba(255,255,255,0.3); backdrop-filter: blur(8px); color: #ffffff`

**Text style:** `chip` — ui-sans-serif 500 · 14px/1

**Observed:** A centered row of short category labels follows the action dock, separated by 8px.

**States:** Declared: hover background-color rgba(255,255,255,0.25); focus-visible solid 2px outline with 4px offset.

### Illustrated feature card

**Use:** Explain one benefit through a miniature product scene.

**CSS:** `display: flex; flex-direction: column; overflow: hidden; border-radius: 20px; border: 2px solid rgba(255,255,255,0.56); background: linear-gradient(rgba(255,255,255,0.77), rgba(255,255,255,0.88)); padding-bottom: 16px`

**Text style:** `card-title` — ui-sans-serif 500 · 23px/1.2 · tracking -0.02em

**Observed:** Illustration first, then a 32px-inset text region containing title, body and bottom-aligned Text action. The illustrated zone is about 248px tall within a 451px card. Dark feature variants use 1px white-alpha edges and 32px bottom padding.

**Transfer:** Depict one legible outcome per card, not a full application squeezed into every tile.

### Text action

**Use:** Low-friction follow-through at the bottom of a feature card.

**CSS:** `display: flex; align-items: center; height: 36px; color: #232323`

**Text style:** `text-action` — __Inter_8a0ba0 600 · 16px/1.5

**Observed:** The arrow is inline with the label and the action is aligned consistently across the card row.

**Transfer:** Use a short verb phrase and a plain arrow, without an enclosing pill.

### Dark button

**Use:** Editorial next step on a pale background.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 10px 18px; border-radius: 10px; background: #1f1f1f; color: #ffffff; backdrop-filter: blur(8px)`

**Text style:** `button-label` — __Inter_8a0ba0 500 · 16px/1.5

**Observed:** Small and restrained relative to the serif statement.

**States:** Declared: hover background-color rgb(44 44 44/1).

### Inverse button

**Use:** Conversion action over closing photography.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 43px; width: 154px; padding: 12px 20px; border-radius: 12px; background: rgba(255,255,255,0.96); color: rgba(5,5,5,0.72)`

**Text style:** `action` — ui-sans-serif 600 · 16px/1.5

**Observed:** Placed far below the headline within the same left alignment, keeping the middle of the image open.

### Footer navigation

**Use:** Utility navigation before the monumental name.

**CSS:** `display: flex; align-items: flex-start; justify-content: space-between; gap: 40px; border-top: 1px solid rgba(23,23,23,0.08); padding-top: 40px`

**Text style:** `footer-link` — ui-sans-serif 500 · 14px/1.5

**Observed:** Small symbol and one-line promise at left; four labeled link columns at right. Category-to-links gap is 24px and links have 16px gaps. Copyright sits low left, social icons low right. Dark variants use white links and 8% white top rules.

**Transfer:** Keep the compact navigation distinct from the oversized name below it.

### Testimonial card

**Only for:** business proof sections

**Use:** Human proof in a three-column, two-row grid.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 24px; border-radius: 12px; background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.08)`

**Text style:** `quotation` — __rulesFont_d96771 400 · 20px/1.2

**Observed:** Quote at top, small square portrait and name/role block pinned to the lower edge; roughly 419px by 281px per card.

### Question disclosure

**Only for:** business FAQ sections

**Use:** Concise objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; min-height: 72px; gap: 24px; padding: 20px 0px; color: #ffffff`

**Text style:** `question` — ui-sans-serif 500 · 18px/1.5

**Observed:** Summary inside a native disclosure row with a 1px 10% white bottom rule; a 20px chevron turns when open. Answers use muted white text at 16px/1.6.

**States:** Declared: hover unknown; focus-visible solid 2px white outline with 4px offset.

## Imagery and graphics

### Cinematic human photography

**Use:** Opening scene and photographic closing call.

**Observed:** People are absorbed in an activity rather than posing: a person with a laptop in a warmly lit interior, or outdoors among grass under a teal sky. Cream clothing, amber highlights and deep green shadows create an analog editorial feel. The opening fills almost the whole viewport; closing photography is a wide 1280px by 492px panel with 20px corners.

**Transfer:** Show the new product's human context with candid posture, warm directional light and enough dark negative space for white type. A still commissioned or licensed photograph is sufficient; keep the scene more prominent than interface chrome.

### Tone-on-tone identity sculpture

**Use:** Signature editorial interruption between practical explanations and a conversion call.

**Observed:** A beveled circular emblem with upward forms is rendered as a pale stone object against warm stone, centered between widely separated text columns. It has visible thickness, soft directional highlights and little contrast. The dark variant becomes graphite on charcoal; an editorial closing variant reduces it to a faint outline.

**Transfer:** Use the new product's own simple geometric symbol. Minimum version: a ring or monogram with a believable offset edge and directional tonal shading, not a generic colorful 3D mascot.

**Build:** Create an SVG symbol about 380px square, with a thick ring and two or three strong internal geometric strokes. Add a slightly offset duplicate beneath it to suggest a 12px extrusion; use a white-to-gray linear gradient on the face, lower-contrast gray on the edge, and a faint blurred shadow. For dark pages, invert the tonal family to graphite without adding neon. For the outline variant, remove fills and use thin low-opacity white strokes.

### Floating product fragments

**Use:** Illustration zones in explanation cards and large business previews.

**Observed:** Small white sheets, profile lists, match badges and chat bars overlap with gentle perspective, soft wide shadows and lower edges fading into the pale card. Color occurs in small icons and status badges. The business preview instead stages a large bright interface window over atmospheric amber-and-teal photography.

**Transfer:** Create two or three simplified fragments that demonstrate an actual outcome, keep most of their area white, and fade the arrangement toward the card's text boundary. At minimum show one recognizable sheet with an action or status, not an empty rectangle.

**Build:** Use a 248px-high clipped stage. Layer two rounded white panels with slight offsets, a broad low-opacity black shadow and a small colored symbol or badge; add a white transparent-to-opaque linear gradient over the bottom 86px. Keep the main text label and result readable while reducing secondary detail.

### Documentary monochrome

**Only for:** long-form editorial pages

**Use:** Opening media and visual pauses in an argument-led story.

**Observed:** A commuter passing a train is softly out of focus in black and white, framed in a wide 1280px panel with 24px corners and a 5px low-contrast white border. The subject feels observed rather than advertised.

**Transfer:** Use documentary people-in-motion imagery that embodies the problem or aspiration, with deep blacks and a single readable human gesture.

### Motion-blurred atmosphere

**Only for:** assessment product pages

**Use:** Large result stage and closing photographic banner.

**Observed:** Warm peach and orange light bleeds into deep teal-blue, with a moving human figure in the closing image. Horizontal motion blur and grain soften the scene. A white result sheet floats over the atmospheric image; the closing banner keeps white serif type at upper left and a small inverse action at lower left.

**Transfer:** Use a deliberately motion-blurred photo or soft directional color field behind a crisp result sheet. Keep the human scene and interface on separate layers.

**Build:** Place a blurred photograph as a cover layer, with warm highlights above and teal shadows below. If photography is unavailable, combine oversized peach, amber and deep teal elliptical gradients, blur them heavily and add a subtle monochrome noise overlay; retain a crisp white foreground sheet. Match the soft light rather than requiring exact gradient stops.

### Icons

**Observed:** Functional icons are small outline forms, chiefly 18–20px, white over photos and dark on pale panels. Chevrons use 1.5px rounded strokes; the search arrow is 18px with a 2.2px rounded stroke. Service icons are larger orange-gradient abstract symbols.

**Transfer:** Keep utility icons simple and monochrome; reserve filled pictorial or colored symbols for product fragments and identity categories.

## Section recipes

How recurring sections are built.

### First screen: Cinematic action opening

**Observed:** An 8px white frame surrounds a 1424px by 868px photographic stage with 16px corners. Photography is the back layer, followed by Photographic scrim, then a centered white serif promise spanning about three fifths of the width, then Search well and Glass filters. Glass navigation sits above the scene with logo left and audience switch centered. The headline is 100.8px and visually centered above the midline; the 514px action dock sits 28px below the headline, with filters 14px below. A small live-count pill with an 8px glowing orange dot sits near the bottom. Within the first 900px the whole scene, heading, actions and live proof are visible; the explanation heading remains below the fold. There is no separate support paragraph in this opening.

**Transfer:** Use a short human-outcome promise over a candid product-context photograph. If no bespoke media exists, one carefully lit still photograph and the bright action dock preserve the composition. For business pages, move the heading onto a dark field above an inset 1280px by 480px photo and add a small trust-logo row. For assessment pages, use a pale three-part header: two-line serif promise left, small tonal sculpture center, support and action right, then the large result scene. Editorial pages open with a centered 68px serif statement above monochrome documentary media.

**Avoid:** Do not replace the image with a generic gradient hero, add a paragraph-and-two-buttons stack, or confine the photograph to a small right-hand thumbnail.

**Text style:** `display` — Advercase Demo 400 · 100.8px/1.14 · tracking -0.03em

### Illustrated explanation row

**Observed:** Feature band with 120px top padding, a centered Heading, 40px to a three-column Feature grid and about 80px below. Each Illustrated feature card puts its floating scene above left-aligned title, 8px support gap and bottom Text action. Dark business variants enlarge the heading to Business heading and use Night card surfaces.

**Transfer:** Explain a small set of outcomes with consistent image scale and text baselines rather than mixing icon-only and photographic cards.

**Text style:** `heading` — Advercase Demo 500 · 40px/1.2 · tracking -0.02em

### Editorial sculpture split

**Observed:** Warm canvas section about 626px tall, with 80px inner gutters and padding. Editorial heading occupies the upper left, the identity sculpture fills the center, and Editorial support sits at lower right with 24px before Dark button. The composition is intentionally diagonal rather than three evenly aligned columns.

**Transfer:** Pair a conviction about the user's future with a short practical explanation and the new product's tonal symbol. Keep the center object away from the text.

**Text style:** `editorial-heading` — Advercase Demo 400 · 60px/1.2 · tracking -0.016em

### Photographic closing panel

**Observed:** 80px of surrounding Warm canvas frames a 1280px by 492px photograph. Closing heading sits 64px in from the upper-left edge, usually on two lines. Inverse button sits on the same left edge near the bottom; a left-to-right 28% black-to-transparent scrim supports readability without darkening the entire scene.

**Transfer:** Restate the desired outcome with new copy and a single action; choose a photograph whose subject can occupy the center or right.

**Text style:** `closing-heading` — Advercase Demo 500 · 64px/1.05 · tracking -0.02em

### Monumental footer finish

**Observed:** Footer navigation begins with a faint top rule and 40px top padding. A broad left identity block faces four narrow link columns. Below their lower metadata baseline, 90px of separation leads to a full-width black wordmark about 1280px by 369px, with 32px bottom space. Dark pages invert the wordmark to white and use an approximately 1196px-wide content area.

**Transfer:** Render the new name as an SVG or tightly fitted graphic wordmark across the content width. If the name is long, construct a compact typographic lockup of similar visual mass; keep it graphic rather than turning it into another slogan.

### Product capabilities chapter

**Only for:** business landing pages

**Observed:** Centered Business heading above five equal tabs on a 1195px-wide rail. A bright product preview fills a roughly 1195px by 580px rounded stage below. Six capability descriptions follow in a three-column, two-row arrangement with vertical rules, 23px titles and muted 19px support copy; one understated text action ends the chapter.

**Transfer:** Keep one selected product view and explain related capabilities beneath it; the colorful photograph is a stage for the interface, not a marketing card background.

**Text style:** `business-heading` — Advercase Demo 400 · 62px/1.07 · tracking -0.0226em

### Proof and reassurance

**Only for:** business landing pages

**Observed:** A centered Business heading introduces a 12px-gapped grid of Testimonial cards. Later a centered 800px FAQ column uses Question disclosures beneath another serif heading. A separate services panel is almost full-width with 32px corners, 120px 64px padding, two equal offerings and one fine center divider.

**Transfer:** Use real customer proof, concrete service options and actual objections as separate rhetorical beats; retain the understated dark surfaces.

**Text style:** `business-heading` — Advercase Demo 400 · 62px/1.07 · tracking -0.0226em

### Editorial narrative and closing band

**Only for:** long-form editorial pages

**Observed:** Short centered prose lines form narrow stanzas in a 674px column, at 28px/1.4 with -0.02em tracking. White phrases and dimmer 45% white phrases create a reading emphasis against Night canvas. Documentary media and a large subdued emblem interrupt the prose. The closing call is a 1021px-wide translucent charcoal band over faint outline art, with top and bottom 24% white rules, 6px backdrop blur, 96px vertical padding, a 57px sans-serif headline left and a small glass action right.

**Transfer:** Write a coherent argument with deliberate stanza breaks and a few visual pauses. Finish with a restrained action band rather than a photographic sales panel.

**Text style:** `manifesto-close` — ui-sans-serif 500 · 57px/1.1 · tracking -0.02em

### Result and category explorer

**Only for:** assessment and category explorers

**Observed:** A large white result sheet with 24px corners sits over a rounded atmospheric stage. Centered serif result name, tiny green tags and a small italic example caption establish a personalized report. Later an eight-item vertical serif selector at left controls a central 378px by 346px Identity gradient card, with a 24px Inter summary and three numbered supporting lines at right. A centered dark conversion action and small duration label sit underneath.

**Transfer:** Show an honest sample output, then let visitors inspect a manageable taxonomy. Use this structure for profiles, recommendations or product configurations, not ordinary feature navigation.

**Text style:** `identity-title` — Instrument Serif 400 · 49px/1.1

## Page flow

**Storyline:** Human promise → tangible mechanism → deeper conviction or proof → low-friction next step → compact navigation and a monumental identity finish.

### Broad consumer-facing marketing landing page

1. **Promise and action** — Immersive human photography, centered serif promise, search dock, shortcuts and live activity proof.
2. **Mechanism** — Three pale illustrated explanation cards.
3. **Conviction** — Diagonal statement-and-support composition around a tonal sculpture.
4. **Closing call** — Wide human photograph, short white headline and inverse action.
5. **Brand finish** — Light footer navigation followed by a giant dark name.

**Transfer:** Use the compact, image-led story as the default landing-page structure, adapting its beats to the product rather than adding exhaustive feature chapters.

### Argument-led brand or philosophy page

1. **Purpose** — Centered serif statement over monochrome documentary media.
2. **Problem and belief** — Long centered stanzas with alternating bright and muted phrases.
3. **Visual pause** — Wide subdued imagery and an emblem break up the reading.
4. **Resolution** — Further narrative resolves the argument into an offer of help.
5. **Closing call** — Faint outline symbol behind a ruled glass action band.
6. **Brand finish** — Dark footer and giant white name.

**Transfer:** Use sustained centered prose only when there is a real argument to read; keep the dark theme scoped to this editorial experience.

### Business product landing page with detailed reassurance

1. **Promise and action** — Large serif heading above inset photo, one entry field, small friction-reducing line and customer logos.
2. **Mechanism** — Three dark illustrated cards.
3. **Product demonstration** — Tabbed bright application preview and six capability descriptions.
4. **Social proof** — Six customer quotations with portraits.
5. **Conviction** — Graphite symbol between headline and support.
6. **Offer expansion** — Two service offerings in one large raised panel.
7. **Objection handling** — Five disclosure rows.
8. **Closing call** — Full-width blurred human scene, 84px serif call, entry field and two underlined alternatives.
9. **Brand finish** — Dark footer and giant white name.

**Transfer:** Use the richer dark variant when a professional audience needs capabilities, proof and answers before committing.

### Focused assessment or discovery product page

1. **Promise** — Pale three-part header with two-tone serif heading, tonal symbol and an action with duration.
2. **Sample outcome** — Large personalized result sheet over an atmospheric scene.
3. **Mechanism** — Three pale illustrated explanation cards.
4. **Exploration** — Vertical category selector, rich identity card and numbered explanation.
5. **Closing call** — Motion-blurred photographic banner with white serif heading and inverse action.
6. **Brand finish** — Light navigation footer and giant dark name.

**Transfer:** Make a sample result tangible before asking for effort, then let readers explore meaningful categories.

## Writing

Warm, purposeful and direct. The emotional claim is about a person's future, while the supporting language is concrete about what the tool does.

**Do not copy:** Do not reuse the Parallel name, logo, emblem, WorkForm name, proprietary category artwork, customer names or quotations, activity counts, salary figures or performance claims. Write new truthful equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your'; use the product name sparingly in explanatory copy. Belief-led passages can use 'we' to take responsibility.
- **Rhythm:** Headlines are typically short phrases of four to eight words; support is one or two plain sentences. Editorial narrative breaks into compact stanzas and sentence fragments, without hype punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A discovery verb plus a personally meaningful outcome. | 4–7 words | “Find your life's work.”<br>“Find your perfect hire” |
| Supporting explanation | Start with an outcome, then describe the practical mechanism or next step. | 18–35 words | “Discover your strengths with our optional 8-minute WorkForm assessment. Or start browsing jobs.” |
| Card heading | Verb plus a short benefit, not a technical noun stack. | 3–5 words | “Find hidden roles”<br>“Hire in one place” |
| Action | Short verb phrase that says exactly what happens next. | 2–4 words | “Get Started”<br>“Post free” |
| Editorial conviction | A short declarative statement about why the category matters. | One brief sentence or a few linked fragments | “Finding work doesn’t work.”<br>“We exist to help.” |

**Words and phrasing to use:** find; discover; your; fit; guidance; what matters; next; build; intention

**Avoid:** revolutionize; 10x; crush it; disrupt everything; game-changing magic; unparalleled

**Rules:**

- Connect the product's practical mechanism to a human outcome rather than leading with a feature inventory.
- Keep supporting descriptions specific enough to picture an action or result.
- Place a duration or reassurance beside the relevant action, not in a detached promotional badge.
- Use compact contrasts and repetition in editorial passages, but keep functional labels literal.

## Do's and Don'ts

### Do

- Keep the opening serif at weight 400 and use the clamp(72px, 7vw, 104px) scale.
- Preserve 80px desktop gutters around the 1280px content area.
- Keep the orange gradient concentrated in the 38px submit circle or small business capsules.
- Use 32px text insets and 20px corners for pale explanation cards.
- Let the sculpture composition separate an upper-left statement from lower-right support.
- Keep photographic closing calls around 492px tall with 64px internal insets.
- Retain the full-width graphic name after the compact footer navigation.
- Use 1px white-alpha borders and 24px padding for dark testimonial cards.

### Don't

- Do not set body copy in the expressive display serif; keep 17px/1.4 sans for card descriptions.
- Do not turn all actions into fully rounded capsules; the default text buttons have 10–12px corners.
- Do not use bright orange as a section background; let the photography provide broad color.
- Do not apply black drop shadows to every pale card; depth belongs mainly to the floating illustrations and search well.
- Do not turn footer category labels into oversized headlines; retain 14px text above modest link stacks.
- Do not use bright white rules throughout dark pages; edges are generally only 8–10% white.
- Do not make the identity sculpture glossy chrome or saturated plastic; its tone stays close to the field behind it.
- Do not adopt the forest identity-card gradient as the general marketing canvas.

## Motion and responsive

### Motion

**Observed:**

- Navigation declares background-color and backdrop-filter transitions of 0.3s with cubic-bezier(0,0,0.2,1).
- The audience selection layer declares transform 0.3s cubic-bezier(0.22,1,0.36,1).
- Glass filter colors declare 0.15s cubic-bezier(0.4,0,0.2,1); text links also declare color transitions.
- Headline words use overflow-hidden reveal wrappers and transform layers.

**Transfer:**

- Keep audience switching as a contained sliding selection, not a whole-header animation.
- Preserve clipped word reveals for expressive serif headlines without moving the whole composition.

**Unknown:**

- Reveal timing and scroll trigger behavior are not established.
- Photography playback, looping and the sculpture's movement are not established.

### Responsive

**Observed:**

- Main container classes declare 24px base gutters, 40px medium gutters and 80px desktop gutters.
- The display headline uses clamp(72px, 7vw, 104px).
- Assessment card-and-description composition switches to a row at 960px; its gap becomes 60px at 1360px.
- Numerous desktop sections and the desktop navigation are hidden below the medium breakpoint; alternate small-screen implementations are not specified here.

**Transfer:**

- On narrow screens, retain the image-led promise and bright action dock, with an input width constrained to available space.
- Stack diagonal editorial text around the tonal symbol while preserving the distinction between statement and support.
- Reduce footer columns before shrinking the wordmark into a normal logo; the ending should still feel monumental.

**Unknown:**

- Exact mobile typography, alternate navigation, section visibility and photograph framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
