# Tripsy — pocket-sized product theatre

## Overview

A bright, approachable product style with the polish of a native app launch. Black system sans headlines and cool gray explanations sit on white, with warm orange reserved for emphasis and tiny proof marks. Large interface-and-device compositions carry the visual storytelling, while softly rounded cards add friendly density and a black closing area provides a decisive finish.

### Essentials

- Promise-sized headlines, not billboard typography: centered system-ui at 54px, weight 600, line-height 1 and -0.2px tracking, often split into two compact lines.
- An airy promise above a tangible product: a 1000px-wide stage pairs a roughly 600px support measure with a central device and floating interface fragments; use a layered browser or workflow composition when a handheld device is inappropriate.
- Native-app actions stay compact and pill-shaped: the navigation action is 138×31px with a 100px radius, while the closing action is 160×48px with translucent gray material.
- Orange is a verbal highlighter, not the canvas: #ff7733 marks occasional full-size heading lines, links, ratings and small labels; the ordinary page remains predominantly white and neutral.
- Proof has a friendly physical shape: 32px-radius cards, 28px review padding, orange 16px stars with 2px tracking, and three staggered 320px columns with 20px gaps.
- The finish changes the lighting: a black closing field uses the same 54px headline in white, a 20px gray support line and a small glassy pill, flowing into a restrained four-column black footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Apricot orange | `#ff7733` | `--color-accent` | text, accent, link, action | Heading emphasis, stars, proof labels and the free-plan action; never an ordinary full-section fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, action | Headlines, compact navigation actions, closing field and footer; full canvas only for pricing. |
| Smoked glass | `#525252` | `--color-glass` | action | Visible gray of the closing action on black, made with rgba(102,102,102,0.8) and a faint dark gradient. |
| Reading gray | `#545454` | `--color-review-ink` | text | Longer customer quotations. |
| Cool gray | `#606266` | `--color-body` | text | Primary supporting paragraphs and review metadata. |
| Navigation gray | `#666666` | `--color-nav-muted` | text | Navigation links on white. |
| Closing gray | `#757575` | `--color-closing-muted` | text | Support text in the black closing call. |
| Silver | `#b3b3b3` | `--color-footer-muted` | text, link | Footer links and secondary navigation on dark backgrounds. |
| Review hairline | `#d4d5d6` | `--color-review-edge` | border | Visible result of #606266 at approximately 27% opacity over white. |
| Light silver | `#d9d9d9` | `--color-hover-light` | link | Hovered footer links. |
| Metadata mist | `#f0f2f6` | `--color-tag` | surface | Small source badges on reviews. |
| Warm porcelain | `#fbf6f3` | `--color-warm-card` | surface | A warm counterpoint for selected proof and relationship cards. |
| Soft fade | `#f7f7f7` | `--color-band-end` | background | Bottom of white-to-gray full-width bands. |
| Porcelain | `#fafafa` | `--color-feature-card` | surface | Feature and editorial proof cards. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas and cards; inverse text and pricing purchase buttons. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Charcoal | `#1c1c1c` | `--color-pricing-card` | surface | Plan cards against black. |
| pricing pages | Purchase ink | `#222222` | `--color-purchase-ink` | text | Text on white purchase pills. |
| pricing pages | Pricing silver | `#a1a1a1` | `--color-pricing-muted` | text | Pricing subtitle and comparison explanations. |

## Typography

- **system-ui** — Marketing headlines, explanatory copy, navigation and footer. Familiar native grotesk with compact semibold headlines and practical text shapes. Font stack: "system-ui", -apple-system, "Segoe UI", Roboto, "Helvetica Neue", sans-serif.
- **ui-rounded** — Action labels and pricing numerals. Native rounded sans softens the otherwise sober system typography. Font stack: "ui-rounded", system-ui, -apple-system, "Segoe UI", sans-serif.
- **Inter** — Review stars and small review metadata. Even, crisp small text with an open x-height. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | system-ui | 600 | 54px | 1 | -0.0037em | Opening promise, section headings and inverse closing headline. |
| card-heading | system-ui | 600 | 28px | 1 | normal | Feature-card titles; also pricing tier names and comparison headers. |
| body | system-ui | 500 | 20px | 1.3 | normal | Default centered support text. |
| body-regular | system-ui | 400 | 20px | 1.2 | normal | Longer feature explanations and permission cards. |
| proof-heading | system-ui | 600 | 20px | 1.2 | normal | Review titles and editorial proof statements. |
| closing-action | ui-rounded | 400 | 18px | 1.2 | -0.01em | Closing glass action. |
| compact-body | system-ui | 400 | 17px | 1.2 | 0.0235em | Review paragraphs, navigation, announcement text and plan explanations. |
| nav-action | ui-rounded | 500 | 16px | 1.2 | 0.0125em | Compact navigation conversion label. |
| stars | Inter | 400 | 16px | 1 | 0.125em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Orange five-star review markings. |
| footer-link | system-ui | 400 | 15px | 1 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Footer links. |
| footer-heading | system-ui | 600 | 15px | 1 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Footer column and subgroup labels. |
| metadata | Inter | 400 | 13px | 1.4 | 0.015em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Review attribution, date and source badge. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | system-ui | 600 | 81px | 0.9 | normal | Centered product name with orange premium suffix. |
| pricing pages | price | ui-rounded | 600 | 54px | 1 | normal | Large plan prices. |
| pricing pages | pricing-subtitle | system-ui | 400 | 22px | 1.2 | 0.018em | Muted one-line subtitle beneath the product name. |
| pricing pages | purchase-action | ui-rounded | 700 | 20px | 1 | -0.01em | White paid-plan purchase buttons. |
| pricing pages | free-action | ui-rounded | 600 | 18px | 1 | 0.011em | Orange free-plan action. |
| pricing pages | comparison-note | system-ui | 400 | 14px | 1.4 | 0.0286em | Secondary comparison-row descriptions. |

**Notes:**

- The default headline and section headline share one size; hierarchy comes from position, whitespace, color and imagery rather than a long display scale.
- Orange lead-ins can be as large as the following black headline, not miniature uppercase eyebrows.
- Use rounded type only for actions and prices; body text remains the native system sans. Keep 54px headlines compact with -0.2px tracking, but retain positive 0.4px tracking on 17px text.

## Layout

**Density:** Airy around product scenes; compact within cards, navigation and footer.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Default heading-to-support gap and small horizontal arrangements. |
| 14px | Review-card content gaps. |
| 16px | Closing stack gaps and feature-card inner relationships. |
| 20px | Review column and stacked-card gaps. |
| 24px | Two-column proof and feature grids; pricing card gaps. |
| 28px | Review-card padding. |
| 32px | Feature, proof and pricing-card padding. |
| 40px | Desktop section side padding and common text-to-media separation. |
| 48px | Navigation link spacing and spacious inset treatments. |
| 56px | Review heading-to-grid separation. |
| 60px | Footer top padding and separation before its bottom row. |
| 120px | Major capability chapter separation and closing top and bottom padding. |
| 180px | Opening section top padding before the inner 32px inset. |

### Containers and grids

- **product-stage**: max width 1000px · side padding 40px. Centered content and media stage inside a 1080px outer wrapper; occasional imagery expands to the viewport edges.
- **support-measure**: max width 671px. Centered feature explanations; opening support is narrower at 597px.
- **navigation**: max width 920px. Floating fixed capsule, narrower than the product stage.
- **paired-cards**: max width 1000px · 2 columns · gap 24px. Equal 488px proof or feature cards.
- **reviews**: max width 1000px · 3 columns · gap 20px. Independent vertical stacks of 320px review cards, not equal-height rows.
- **footer**: max width 1000px · 4 columns. Four evenly distributed text columns, with a second small subgroup inside one column.
- **plans** (only for pricing pages): max width 1024px · 3 columns · gap 24px. Three equal plan cards above a full-width comparison table.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards | 32px |
|  | navigation-and-small-actions | 100px |
|  | closing-action | 48px |
| pricing pages | plan-cards | 30px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation | `rgba(0, 0, 0, 0.05) 0px 3px 5px 0px, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px` | Soft floating capsule separation. |
| review-card | `rgba(0, 0, 0, 0.09) 0px 1px 3px 0px` | Minimal lift under white review cards. |
| closing-action | `rgba(0, 0, 0, 0.1) 0px 6px 18px 0px` | Low-key depth beneath the smoked glass pill. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

#### Fading band · level 0

**Use:** Selected product chapters and the review area.

**CSS:** `background: linear-gradient(#ffffff 0%, #f7f7f7 100%)`

**Observed:** Very low contrast, full-width neutral fade rather than a visible colored panel.

**Transfer:** Use to gather several cards or ground a large interface composition.

#### Porcelain card · level 1

**Use:** Feature explanations and editorial proof.

**CSS:** `background: #fafafa; border-radius: 32px; padding: 32px`

**Observed:** A selected partner card uses warm porcelain instead; the shape stays identical.

**Transfer:** Alternate cool and warm neutrals sparingly within a matched pair.

#### Black finish · level 0

**Use:** Closing conversion field and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** The closing field and footer form one continuous black ending, separated by a subtle rule.

**Transfer:** Make the closing message the final high-contrast moment.

#### Charcoal plan · level 1

**Only for:** pricing pages

**Use:** Plan options on black.

**CSS:** `background: #1c1c1c; border-radius: 30px; padding: 32px`

**Observed:** Three equally sized cards; no oversized recommended card.

**Transfer:** Distinguish purchase routes through button fill, not unequal geometry.

## Components

### Floating navigation

**Use:** Persistent navigation above the product story.

**CSS:** `width: 920px; height: 60px; background: #ffffff; border-radius: 100px; padding: 10px 16px 10px 32px; box-shadow: rgba(0, 0, 0, 0.05) 0px 3px 5px 0px, rgba(0, 0, 0, 0.04) 0px 1px 1px 0px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `compact-body` — system-ui 400 · 17px/1.2 · tracking 0.0235em

**Observed:** Small icon-and-wordmark at left, four plain links in the middle, compact conversion at right. The wrapper is fixed. Pricing uses black navigation with inverse logo and action.

### Navigation action

**Use:** Default compact conversion action.

**CSS:** `background: #000000; color: #ffffff; border-radius: 100px; height: 31px; padding: 6px 12px 6px 8px; display: flex; align-items: center; gap: 10px`

**Text style:** `nav-action` — ui-rounded 500 · 16px/1.2 · tracking 0.0125em

**Observed:** A small circular download symbol precedes the label; black on white is the ordinary marketing variant.

### Navigation text link

**Use:** Secondary navigation.

**CSS:** `color: #666666; text-decoration: none`

**Text style:** `compact-body` — system-ui 400 · 17px/1.2 · tracking 0.0235em

**Observed:** Links remain plain text with no individual container; the link group uses 48px gaps.

**States:** Declared: hover color #000000 with no underline; focus-visible unknown.

### Proof card

**Use:** Editorial endorsement or external recognition.

**CSS:** `background: #fbf6f3; border-radius: 32px; padding: 32px; display: flex; flex-direction: column; align-items: center; gap: 12px`

**Text style:** `proof-heading` — system-ui 600 · 20px/1.2

**Observed:** Small publication or award mark, date/category label and concise centered statement. Its paired counterpart uses Porcelain card.

### Feature card

**Use:** Explain adjacent product roles or capabilities.

**CSS:** `background: #fafafa; border-radius: 32px; padding: 32px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-heading` — system-ui 600 · 28px/1

**Observed:** Small illustrative cue above a heading and regular 20px explanation; paired cards are equal width. A wider warm card below can carry a centered relationship benefit.

### Review card

**Use:** Dense but friendly customer proof.

**CSS:** `background: #ffffff; border: 0.5px solid rgba(96, 98, 102, 0.27); border-radius: 32px; padding: 28px; box-shadow: rgba(0, 0, 0, 0.09) 0px 1px 3px 0px; display: flex; flex-direction: column; gap: 14px`

**Text style:** `compact-body` — system-ui 400 · 17px/1.2 · tracking 0.0235em

**Observed:** Orange stars and an optional small source pill form the top row; semibold title, gray quotation and smaller attribution follow. Text length determines height.

**Transfer:** Use genuine varied-length quotations; keep the resulting staggered silhouette.

### Closing glass action

**Use:** Conversion inside the black finish.

**CSS:** `width: 160px; height: 48px; background-color: rgba(102, 102, 102, 0.8); background-image: linear-gradient(135deg, rgba(0, 0, 0, 0.03) 0%, rgba(0, 0, 0, 0.01) 100%); color: #ffffff; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 48px; box-shadow: rgba(0, 0, 0, 0.1) 0px 6px 18px 0px; backdrop-filter: blur(18px) saturate(1.2); display: flex; align-items: center; justify-content: center`

**Text style:** `closing-action` — ui-rounded 400 · 18px/1.2 · tracking -0.01em

**Observed:** Outlined download-in-circle symbol and text are centered together. An inset rounded edge adds a second faint boundary; the finish is smoky, not luminous.

### Footer link

**Use:** Grouped utility navigation in the black ending.

**CSS:** `color: #b3b3b3; text-decoration: none`

**Text style:** `footer-link` — system-ui 400 · 15px/1

**Observed:** White semibold group labels sit above plain links with about 16px vertical gaps; a few emphasized links remain white.

**States:** Declared: hover color #d9d9d9 without underline; focus-visible unknown.

### Plan card

**Only for:** pricing pages

**Use:** Compare purchase options.

**CSS:** `background: #1c1c1c; border-radius: 30px; padding: 32px; height: 285px; display: flex; flex-direction: column; gap: 40px`

**Text style:** `card-heading` — system-ui 600 · 28px/1

**Observed:** Orange tier name, large rounded white price, two compact gray details and a bottom full-width purchase action. All cards have equal geometry.

### Purchase pill

**Only for:** pricing pages

**Use:** Paid-plan purchase.

**CSS:** `background: #ffffff; color: #222222; border-radius: 100px; height: 52px; padding: 16px 15px; display: flex; justify-content: center; align-items: center`

**Text style:** `purchase-action` — ui-rounded 700 · 20px/1 · tracking -0.01em

**Observed:** Paid plans use white buttons. The entry plan instead uses orange, a download icon and the free-action recipe with 12px 15px padding.

### Comparison row

**Only for:** pricing pages

**Use:** Resolve feature and entitlement questions.

**CSS:** `background: #000000; height: 75px; padding: 14px 20px 14px 0px; display: flex; align-items: center; justify-content: space-around; box-shadow: rgba(0, 0, 0, 0.05) 0px -1px 0px 0px inset`

**Text style:** `compact-body` — system-ui 400 · 17px/1.2 · tracking 0.0235em

**Observed:** Wide left label area, optional 14px muted description, and two aligned status columns. Included premium features use an orange filled circle with a black check; unavailable features use gray hollow rings. Thin horizontal rules separate rows.

## Imagery and graphics

### Layered native product stage

**Use:** Opening and major capability chapters; the principal visual signature.

**Observed:** A realistically edged upright phone is centered on white, with a colorful screen photograph and crisp white interface fragments overlapping its sides. Floating itinerary, transport and expense panels have soft shadows and rounded edges; the interface appears brighter than the hardware. The opening image is 1000px wide and continues below the first screen.

**Transfer:** Create one central real interface in a device or browser frame and pull two to four useful details into overlapping cards. If photography is irrelevant, use a polished product canvas with restrained color inside it rather than substituting stock lifestyle photography.

**Build:** Center a dark, rounded device frame about one third of a 1000px stage width. Inset the interface with rounded clipping, then layer white UI cards across its left and right edges at several heights. Use low-opacity black shadows, keep the surrounding field white, and ensure each fragment demonstrates one understandable task. Use a subtle pale radial wash behind a later scene, not a saturated full-page gradient.

### Embedded destination photography

**Use:** Inside product imagery rather than as a marketing background.

**Observed:** Natural, bright architectural travel photography occupies the phone screen, with a turquoise sky providing the strongest color in the opening composition.

**Transfer:** Show the product's actual output or subject inside its interface. Keep photographic color contained by the UI and balance it with abundant white.

### Sculpted app icon

**Only for:** pricing pages

**Use:** Premium identity above the pricing headline.

**Observed:** A 164px rounded-square app icon has a warm off-white backing, glossy orange object and dark soft-edged handle, with tactile highlights and recesses.

**Transfer:** Use the new product's own dimensional app emblem; a carefully shaded rounded tile with a simple original object is the minimum equivalent.

**Build:** Place an original orange rounded object within an off-white rounded-square tile; add a dark handle or similarly simple identifying shape, a narrow top highlight, inset dark recesses and soft contact shadows. Keep the silhouette readable at navigation size.

### Release ribbon

**Only for:** release announcement campaigns

**Use:** Thin black announcement strip above navigation.

**Observed:** A 48px-high strip carries small centered release text, with orange version emphasis and glossy multicolored looping cords entering from the outer corners. The middle stays visually clear.

**Transfer:** Confine celebratory artwork to the strip edges and keep the release sentence short.

**Build:** Draw a few curved SVG paths with rounded ends that loop in from each corner. Apply multicolor strokes with a narrow highlight and soft colored blur underneath; clip them to the 48px black strip and reserve the central half for text.

### Icons

**Observed:** Small native-style symbols accompany actions; the closing download symbol is an 18px white outline with 1.8px stroke. Comparison states use 24–25px filled checks and outlined empty circles. Most marketing navigation is text-only.

**Transfer:** Use familiar compact download and entitlement symbols. Keep decorative icon color inside product imagery or tiny orange proof marks, rather than adding a colored icon above every section.

## Section recipes

How recurring sections are built.

### First screen: Promise above a product stage

**Observed:** White canvas behind a thin black release strip and Floating navigation. After 180px top padding and a 32px inner inset, a centered 54px two-line headline occupies roughly a third of the viewport width. A 597px-wide gray support paragraph follows at 10px, then a compact horizontal row of recognition and rating marks. The layered device stage begins around 570px down, centered under the text; its upper half is visible within the first 900px and its lower panels continue below. The conversion action is in navigation, not an extra oversized hero button. Layers run white field, text/proof, central device, then overlapping UI details, with navigation floating above.

**Transfer:** Make the promise two short, complementary lines and show a concrete product artifact directly underneath. Replace unavailable device art with an equally polished browser-and-detail-card composition, and use truthful small proof marks. A pricing page opens instead with a centered app emblem, premium product title and subtitle over black, with plan cards already visible in the first screen.

**Avoid:** Do not turn this into a left-text/right-image split hero, a giant all-caps wordmark, or a dark gradient SaaS opening with two oversized buttons.

**Text style:** `display` — system-ui 600 · 54px/1 · tracking -0.0037em

### Capability chapter

**Observed:** Centered display heading and body support over a 1000px product image; heading-to-support gap is typically 10px and text-to-media 24–45px. Selected chapters pair a full-size orange lead-in with a black heading. Major chapters are separated by 120px; some scenes expand to full viewport width over Fading band.

**Transfer:** State the benefit first, then make one large product composition demonstrate it. Vary full-width and contained scenes without changing the type scale.

**Text style:** `display` — system-ui 600 · 54px/1 · tracking -0.0037em

### Matched proof and feature cards

**Observed:** Two equal 488px cards at 24px gap use Proof card or Feature card. Warm and cool porcelain distinguish adjacent ideas. Editorial proof is followed by a six-logo monochrome row and a small orange text link; relationship features can resolve into a full-width warm card.

**Transfer:** Pair two complementary proofs or capability roles, keeping visual weight balanced. Use customer or integration marks only where relevant.

### Review wall

**Observed:** A centered display statement introduces a three-column masonry-like wall after 56px. Review card stacks have independent heights with 20px gaps, set on Fading band; orange stars, tiny source pills and low-contrast edges carry the detail.

**Transfer:** Let actual quote lengths create the rhythm; retain the compact title, body and attribution hierarchy.

### Compact black closing call

**Observed:** Black finish spans 400px with centered white display headline, gray body line and Closing glass action separated by 16px. Top and bottom padding are 120px. It flows into the same black footer rather than ending as an isolated rounded card.

**Transfer:** Close with a simple near-future outcome and one action. State platform or availability information in the smaller gray line.

**Text style:** `display` — system-ui 600 · 54px/1 · tracking -0.0037em

### Shared utility ending

**Observed:** Four footer columns fill a 1000px measure, beginning about 60px below the top. Labels use footer-heading and links use Footer link. One column holds an additional subgroup. A bottom horizontal rule separates copyright at left from two small social marks at right; the complete footer is 515px tall.

**Transfer:** Group product, organization, ecosystem and help links according to the new information architecture. Preserve the sparse black ending rather than adding another promotional banner.

### Premium offer and comparison

**Only for:** pricing pages

**Observed:** Black canvas, a centered 164px app emblem, 81px white product title with orange suffix and 22px muted subtitle. Three Plan cards sit in a 1024px grid with 24px gaps. A broad comparison table follows, with a 28px heading row and repeated Comparison rows. The table ends directly above the shared utility footer; there is no separate closing conversion field.

**Transfer:** Make price choices legible above the fold, then explain differences in a calm aligned matrix. Keep the default marketing page light; reserve the full dark treatment for purchase decisions.

**Text style:** `pricing-display` — system-ui 600 · 81px/0.9

## Page flow

**Storyline:** promise → tangible product demonstration → credible proof → capability chapters → decision support → conversion or utility ending

### Introduce a consumer app and make its usefulness feel immediate

1. **Promise** — Centered two-part benefit, explanatory paragraph and small proof marks above an overlapping device composition.
2. **External proof** — Paired recognition cards, monochrome press marks and a small editorial link.
3. **Capability chapters** — Large repeated product stages alternate with paired feature cards and occasional orange heading lead-ins.
4. **Objection handling** — A short centered alternative-to-existing-tools statement uses the same heading/body structure.
5. **Social proof** — A staggered wall of real reviews under a broad display statement.
6. **Closing call** — Black full-width outcome headline and smoked glass download action.
7. **Utility ending** — Four-column black footer, divider and compact bottom row.

**Transfer:** Use only the chapters needed to explain the new product; keep the tangible layered product device and the decisive black ending rather than reproducing the original length.

### Convert interest into a choice between entry and premium access

1. **Offer identity** — Dimensional app emblem and large inverse product name with orange premium emphasis.
2. **Pricing** — Three equal charcoal plan cards with prominent white prices; entry action orange and paid actions white.
3. **Decision support** — Long aligned comparison matrix with short labels, muted notes and orange check circles.
4. **Utility ending** — The same black footer follows the comparison directly.

**Transfer:** Present the available buying models clearly, with equal-width plans and a factual comparison. Do not add a second promotional close after the table.

## Writing

Friendly, direct and utility-led, with a little delight in how effortless the product feels. Confidence comes from concrete tasks, native-platform familiarity and actual third-party proof rather than sweeping category claims.

**Do not copy:** Do not reuse Tripsy names, icons, device artwork, press endorsements, awards, customer quotes, prices, download totals, ratings or competitor claims as assets or facts for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; the product name acts as a helpful agent. Imperatives describe useful actions rather than issuing sales pressure.
- **Rhythm:** Headlines often use two short clauses or a brief benefit followed by its practical meaning. Support paragraphs are one to three clear sentences with concrete lists. Action labels are two or three words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Bring scattered work together, then name the relief in a second clause. | 7–12 words | “All your trip details. Finally, in one place.” |
| Capability heading | Pair reader effort with product payoff, or lead with an everyday verb. | 4–9 words | “You book it. [Brand] builds it.”<br>“Stay ahead of every flight change” |
| Support | Name the mechanism and the practical reassurance it creates. | 15–45 words for a focused benefit | “Get instant notifications about delays, gates, and baggage info—so you can travel confidently.” |
| Action | Literal verb plus object; no cleverness at the click. | 2–3 words | “Get the app”<br>“Buy Now” |
| Closing | A near-future outcome starts here. | 5–8 words | “Your next trip starts here” |

**Words and phrasing to use:** all in one place; organized; instantly; keep; share; sync; ready; your; so you can

**Avoid:** disruptive; revolutionary; unparalleled; unlock your potential; enterprise-grade synergy

**Rules:**

- Explain how a feature changes a familiar task before naming its implementation.
- Use specific lists to make broad promises tangible, but keep headings much shorter than the supporting text.
- Use delight sparingly: a phrase such as 'like magic' works only after the practical mechanism is explained.
- Keep purchase terms and entitlement descriptions literal and compact.

## Do's and Don'ts

### Do

- Keep ordinary section headings at 54px/1, weight 600, with -0.2px tracking.
- Maintain a centered 1000px product stage and a narrower 597–671px support measure.
- Use #ff7733 for selected heading lines, stars and concise action accents.
- Make feature cards 32px-radius with 32px padding; use 28px padding for reviews.
- Keep review stacks independently sized with 20px gaps rather than forcing equal heights.
- Carry the black finish into a four-column footer with 15px link typography.
- Use the compact 31px navigation action and the separate 48px closing action for their distinct roles.
- For pricing, align equal plan cards at 24px gaps and use rounded 54px prices.

### Don't

- Do not make the full ordinary marketing canvas black just because pricing uses a dark variant.
- Do not spread orange across large card backgrounds or alternate entire orange sections.
- Do not substitute a geometric display font for the native system headline voice.
- Do not use rounded typography for every paragraph; reserve it for actions and price numerals.
- Do not add hard black borders and heavy drop shadows to the pale feature cards.
- Do not enlarge navigation buttons to the 52px pricing-button height.
- Do not equalize review heights or truncate all quotations into uniform tiles.
- Do not turn the footer into a giant brand-wordmark poster; its hierarchy is small text, columns and a bottom rule.

## Motion and responsive

### Motion

**Observed:**

- No specific action or surface transition timing is established. Links have color-only hover changes, with an underline added on selected emphasized footer links.

**Transfer:**

- Preserve the stable, readable layering of product fragments; motion must not obscure the demonstrated task.

**Unknown:**

- Scroll-scene choreography, duration and easing are unspecified; no repeatable animation sequence is established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px, 1024px and 1200px; the pricing layout also declares 1024px and 1200px boundaries.

**Transfer:**

- As a layout adaptation, reduce paired cards and the review wall to fewer columns while retaining 32px card corners and distinct quote lengths.
- Scale the product montage as a single composition before reducing overlap; keep the central interface legible and the headline centered.
- Collapse pricing choices into a vertical stack while preserving the ordering of tier, price, terms and action.

**Unknown:**

- Exact narrow-screen font sizes, side padding, navigation replacement and comparison-table overflow behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
