# Custo — objects meet monumental type

## Overview

An airy, object-led style that pairs industrial product confidence with an approachable editorial voice. White, sage-grey and deep green-grey form an almost monochrome setting for neutral grotesk typography, oversized wordmark artwork, architectural lifestyle photography and carefully lit product renders. It suits tangible technology and well-designed services that can show how they fit into everyday life; the density is deliberately low outside the product imagery.

### Essentials

- A modest promise sits above a monumental identity: 57.6px regular grotesk headlines at 60.3px line height coexist with white wordmark artwork spanning nearly the full hero width.
- The opening is a layered product poster, not a centered text stack: a 900px sage-grey stage, upper-left two-line promise and underlined action, a central dark object extending below the frame, and giant lettering across its foreground.
- Actions split into two distinct constructions: a translucent white pill with 31.7px corners and 17px 41px 19px padding for conversion; 304px-wide arrow links with 15px bottom padding for exploration.
- Color belongs to large muted stages and real media: most of the page stays white, the opening uses #9ea29f, and an extended demonstration chapter uses #4b514d; bright colors stay inside photographs, interfaces and small proof marks.
- Images behave like architecture rather than floating cards: close product details, domestic context and overscaled device views sit in flat 8px-radius frames, with 24px gutters and no decorative shadows.
- Narrative hierarchy comes from asymmetry and silence: a 12-column grid puts small 20.2px leads on the left and 57.6px arguments over seven columns on the right; numbered 38.4px rows use grey-to-black emphasis and 1px rules.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep green grey | `#4b514d` | `--color-chapter` | background, surface | Extended immersive demonstration chapter. |
| Sage grey | `#9ea29f` | `--color-hero` | background | Full-screen opening stage. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Translucent sage highlight | `#adb0ad` | `--color-button-wash` | action, surface | Visible white-at-15% wash over the sage opening, used for the primary pill. |
| Black | `#000000` | `--color-ink` | text, link, accent | Headlines, active step text, arrows and rules that indicate progress. |
| Reading grey | `#8e9194` | `--color-secondary` | text, link | Supporting paragraphs, footer links and social symbols. |
| Inactive grey | `#a7aaad` | `--color-muted` | text | Inactive numbered steps and small ancillary text. |
| Hairline grey | `#d8d8d8` | `--color-rule` | border | Step dividers, footer boundaries and form outlines. |
| White | `#ffffff` | `--color-canvas` | background, text | Main page canvas and reversed text over the muted stages. |

## Typography

- **PP Neue Montreal** — All marketing text, from display promises to navigation and paragraphs. Neutral contemporary grotesk with open counters, compact proportions and an unforced regular-looking medium cut. OpenType features: "kern", "liga". If unavailable, use **Inter**. Use regular weight and normal tracking; preserve the headline widths rather than adding boldness. Font stack: "PP Neue Montreal", "Inter", Roboto, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | PP Neue Montreal | 400 | 57.6px | 1.047 | normal, features "kern", "liga" | size max(4vw, 40px) | Two-line opening promise and major editorial section arguments; reverse to white on muted stages. |
| heading | PP Neue Montreal | 400 | 38.4px | 1.25 | normal, features "kern", "liga" | size max(2.66667vw, 30px) | Numbered process statements and product names below images. |
| body | PP Neue Montreal | 400 | 20.2px | 1.428571 | normal | fixed | Paragraphs, short section leads, feature titles, navigation and action labels. Titles use ink; explanation uses reading grey. |
| footer-link | PP Neue Montreal | 400 | 20.2px | 1.619048 | normal, features "kern", "liga" | fixed | Stacked discovery and information links in the footer. |
| caption | PP Neue Montreal | 400 | 15.4px | 1.375 | normal, features "kern", "liga" | size max(1.06667vw, 14px) | Small newsletter consent line beneath the input. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use one family and one regular-looking weight throughout; scale and placement do the work normally assigned to bold type.
- Tracking stays normal even at display sizes. Keep display leading near 1.05 and process headings at 1.25.
- The monumental identity is artwork rather than another heading tier; keep its size independent of readable marketing headings.

## Layout

**Density:** Airy, with long pauses between chapters and tightly related text kept together.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 18px | Feature title to explanation. | fixed |
| 24px | Main grid gutters and repeated media gaps. | fixed |
| 40px | Numbered-row vertical padding and footer link-column insets. | fixed |
| 76.8px | Desktop page side inset. | 5.33333vw |
| 110px | Footer top padding and separation from the preceding chapter. | fixed |
| 182px | Deep-stage chapter vertical padding. | fixed |
| 278px | Long white breathing room around product and process chapters. | fixed |

### Containers and grids

- **page grid**: 12 columns · gap 24px · side padding 76.8px. Fluid full-width grid, 1286px usable width at a 1440px viewport; no fixed maximum content width.
- **editorial split**: 12 columns · gap 24px. A three-column supporting lead at left, then a seven-column argument beginning at column six. Supporting prose below occupies five columns on the same right-hand alignment.
- **product pair**: 12 columns · gap 24px. Eight-column product image beside a four-column context image; product name and starting price sit underneath the larger image.
- **immersive chapter**: gap 24px · side padding 62px. Deep-stage surface inset 18px from the viewport, then a 12-column inner grid; left copy and right tall device frames share the chapter.

## Corner radius

| Element | Radius |
| --- | --- |
| media and panels | 8px |
| primary button | 31.7px |
| language select | 7px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Main narrative sections and footer.

**CSS:** `background: #ffffff; color: #000000`

#### Sage stage · level 0

**Use:** Opening product poster.

**CSS:** `background: #9ea29f; color: #ffffff; overflow: hidden`

**Observed:** A continuous full-bleed field behind text, object and wordmark; no gradient or texture.

**Transfer:** Use the muted field to silhouette a product or a constructed service artifact.

#### Deep stage · level 0

**Use:** Long-form demonstration chapter.

**CSS:** `background: #4b514d; border-radius: 8px; padding: 182px 62px; box-shadow: none`

**Observed:** A single extended rounded band, not a grid of dark feature cards; 18px of white remains at either side.

**Transfer:** Carry one coherent product story through the darker material.

#### Outlined field · level 1

**Use:** Newsletter input and restrained form controls.

**CSS:** `border: 1px solid #d8d8d8; border-radius: 8px; background: #ffffff; box-shadow: none`

**Observed:** The outline is the only elevation cue.

**Transfer:** Keep the same flat treatment for other short forms.

## Components

### Primary pill

**Use:** Main conversion in the opening header.

**CSS:** `color: #ffffff; background: rgba(255,255,255,0.15); border-radius: 31.7px; padding: 17px 41px 19px; text-align: center`

**Text style:** `body` — PP Neue Montreal 400 · 20.2px/1.428571

**Observed:** A single unadorned label inside a translucent fill, aligned at the far right of the navigation.

**States:** Declared: hover color #000000; focus-visible outline blue solid 2px with outline-offset -1px.

### Header navigation

**Use:** Opening navigation over the sage stage.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 37px 76.8px; position: absolute; color: #ffffff`

**Text style:** `body` — PP Neue Montreal 400 · 20.2px/1.428571

**Observed:** Small wordmark at left, four lightweight text destinations across the center and Primary pill at right. The header does not need a separate background.

**Transfer:** Keep destination names short enough to leave clear space between the identity and action.

### Arrow link

**Use:** Exploratory action beneath an argument or at the end of a chapter heading.

**CSS:** `display: inline-flex; justify-content: space-between; align-items: center; width: 304px; padding-bottom: 15px; color: #000000; position: relative; overflow: hidden`

**Text style:** `body` — PP Neue Montreal 400 · 20.2px/1.428571

**Observed:** Text on the left, simple right arrow at the far edge, thin current-color underline beneath the whole control. The opening uses a white reversed version.

**States:** Declared: hover is not specified; focus-visible outline blue solid 2px with outline-offset -1px.

**Transfer:** Use a verb-led label rather than a standalone icon.

### Media frame

**Use:** Product details, context images and tall demonstration panels.

**CSS:** `border-radius: 8px; clip-path: inset(0px round 8px); position: relative; overflow: clip; background-size: cover`

**Observed:** Edge-to-edge image with no caption overlay, card border or added drop shadow. Aspect ratios vary with subject; the main product frame is 850px by 720px on desktop.

**Transfer:** Let cropping and image scale provide variety while corners remain consistent.

### Numbered process row

**Use:** Progressive explanation with a small associated image to its left.

**CSS:** `padding: 40px 0px; border-bottom: 1px solid #d8d8d8; position: relative; color: #a7aaad`

**Text style:** `heading` — PP Neue Montreal 400 · 38.4px/1.25

**Observed:** Two-digit number and period occupy a narrow leading column using body type; the statement occupies the rest. Active row becomes black and a short black progress line overlays the divider. The first row omits top padding.

**Transfer:** Use short everyday actions and synchronize the left image with the emphasized row.

### Newsletter field

**Use:** Footer subscription action.

**CSS:** `border: 1px solid #d8d8d8; border-radius: 8px; padding: 20px 32px; height: 74px; width: 429px; box-sizing: border-box`

**Observed:** Email entry with a right arrow submit control inside the far edge. A short invitation precedes it; a small grey consent sentence sits below.

**Transfer:** Keep one field and an integrated action, not a second large pill.

### Footer link

**Use:** Navigation columns in the final white section.

**CSS:** `color: #8e9194; position: relative; text-decoration: none`

**Text style:** `footer-link` — PP Neue Montreal 400 · 20.2px/1.619048

**Observed:** Plain stacked text under black body-size group labels, without bullets or individual boxes.

**States:** Declared: hover text-decoration none; focus-visible outline blue solid 2px with outline-offset -1px.

### Footer shell

**Use:** Complete page ending and secondary conversion.

**CSS:** `border-top: 1px solid #d8d8d8; padding: 110px 76.8px 0px; margin-top: 110px; background: #ffffff`

**Observed:** Brand and brief reassurance at left; two discovery and information columns in the middle; newsletter at right. Small awards sit beneath the brand area. A second horizontal rule separates a lower flex row containing language selection, social marks, a small partner mark, legal links and copyright.

**Transfer:** Use authentic proof marks when available, keeping the end functional and low-key rather than adding a giant closing sales banner.

## Imagery and graphics

### Silhouetted hero object

**Use:** Dominant opening media.

**Observed:** Dark graphite industrial object shown in a slightly elevated three-quarter view against sage-grey; soft highlights describe matte metal, with a narrow glossy black control strip and a small white illuminated detail. It starts near the middle of the first screen, occupies about two fifths of the width and continues beyond the lower edge.

**Transfer:** Use an isolated product render with restrained lighting. For a service, construct a dimensional stack of its most recognizable working artifact or interface, dark-edged against the same matte backdrop; retain the strong silhouette.

### Monumental identity overlay

**Use:** Signature graphic across the lower opening foreground.

**Observed:** Huge white uppercase wordmark spans almost the full content width in front of the product, with letterforms roughly 260px tall at desktop and a small raised registration symbol at its end.

**Transfer:** Create a similarly oversized treatment of the new product's own short name or a compact category word; keep it graphic rather than duplicating the headline.

**Build:** Place an SVG wordmark on a foreground layer above the product, fill white, spanning the content width with around 76.8px side insets. Set its letterform height near 260px at 1440px width, about 18% of viewport width, and anchor the baseline close to the lower edge. Use broad neutral grotesk uppercase outlines, without extrusion, gradient, shadow or blur.

### Architectural lifestyle and detail strip

**Use:** Product explanation, product pair and human-context closing chapter.

**Observed:** Candid domestic use outside a modern grey-brick home, natural daylight, gravel and green planting; an orange-red garment gives a localized human accent. Neighboring close-ups emphasize the dark object's finish and luminous control. Wide strips can extend off the right edge; other photos use portrait-oriented frames.

**Transfer:** Photograph the new product in a believable built environment with muted natural surfaces and one human color accent. Mix whole-scene use with material close-ups instead of unrelated stock portraits.

### Overscaled device demonstration

**Use:** Deep-stage chapter.

**Observed:** Tall phone views sit on pale cool-grey image backings inside rounded frames. Black hardware surrounds a predominantly white interface; each view is intentionally enlarged and cut off at the bottom. Successive panels form a right-hand vertical sequence beside numbered text explanations.

**Transfer:** Use readable examples of the actual interface inside a physical device or a simple dark-edged browser frame. Preserve the pale backing, tight framing and large scale; avoid reproducing tiny interface details as marketing typography.

### Icons

**Observed:** Sparse directional arrows in actions and familiar monochrome social silhouettes at the footer, generally around 20px. Footer symbols use reading grey; action arrows inherit black or white.

**Transfer:** Favor simple arrows and recognizable social marks, not colorful feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Layered product poster

**Observed:** A 900px-high Sage stage holds Header navigation at the top. Below it, a left-aligned two-line display promise occupies roughly the upper-left third, beginning beneath the header around 162px from the top. Arrow link follows without a separate supporting paragraph. Behind the foreground lettering, a dark three-quarter object fills the central lower region and extends through the bottom boundary. Monumental identity overlay runs across the lower third in front of the object; a small proof badge sits at the lower-right edge. Within the first 900px the navigation, complete readable promise, action, upper product body and huge identity are visible; the white editorial explanation begins below.

**Transfer:** Make an equally strong silhouette from a new product render or dimensional service artifact and overlap it with the new identity artwork. Keep the modest readable promise distinct from the monumental lettering. A detail-led secondary page can open with the same left-aligned promise and one enlarged relevant artifact rather than introducing a new visual language.

**Avoid:** Do not turn the poster into a centered SaaS headline above a small floating dashboard, or place the giant lettering behind the object.

**Text style:** `display` — PP Neue Montreal 400 · 57.6px/1.047

### Offset editorial argument

**Observed:** White canvas with a short body-size lead on the left and a seven-column display argument beginning in column six. Arrow link follows the argument; a horizontal image strip comes below. Feature titles and reading-grey explanations continue down the right alignment, with 18px between each title and paragraph.

**Transfer:** Pair a concise everyday frustration with a larger confident answer, then explain the mechanics through images and limited supporting prose.

**Text style:** `display` — PP Neue Montreal 400 · 57.6px/1.047

### Asymmetric product presentation

**Observed:** Offset editorial heading pair above an eight-column Media frame and a four-column context photograph, separated by 24px. A heading-size product name and smaller grey starting price sit below the larger image. Large white intervals separate this from the next chapter.

**Transfer:** Present one main product or offering at a time, pairing its clean specimen view with real-life context.

**Text style:** `heading` — PP Neue Montreal 400 · 38.4px/1.25

### Numbered integration sequence

**Observed:** A display argument sits left with Arrow link aligned at the far right. Below, a small 304px by 206px context image accompanies a right-hand list of four Numbered process rows. Grey inactive statements contrast with a single black active statement and divider progress indicator.

**Transfer:** Explain a short user journey with a few sequential actions; the graphic and active row should clarify the same step.

**Text style:** `heading` — PP Neue Montreal 400 · 38.4px/1.25

### Extended deep-stage demonstration

**Observed:** Deep stage creates a long green-grey chapter inside an 18px white rim. A narrow white display heading stays in the left column while a vertical sequence of large pale-backed phone images runs at right. Numbered feature titles and reading-grey paragraphs sit beneath the heading, corresponding to successive views.

**Transfer:** Use the chapter for a coherent workflow, keeping one repeated device-framing language and short explanations rather than unrelated feature cards.

**Text style:** `display` — PP Neue Montreal 400 · 57.6px/1.047

### Human context into functional ending

**Observed:** After the dark chapter, White canvas returns with a large lifestyle image at left and a narrow, tall display argument at right. Arrow link and a smaller credibility title plus grey explanation complete the chapter. Footer shell begins after 110px of separation and ends with its language, social, legal and copyright row; there is no separate monumental closing CTA.

**Transfer:** Finish the narrative with evidence of design intent or practical trust, then let the newsletter and navigation provide the final actions.

**Text style:** `display` — PP Neue Montreal 400 · 57.6px/1.047

## Page flow

**Storyline:** Product promise → everyday problem and explanation → tangible offering → short user journey → immersive demonstration → human credibility → useful footer and subscription.

### Introduce a designed product as both a desirable object and a useful part of daily life

1. **Promise** — Layered product poster with modest headline, underlined exploration and giant identity.
2. **Problem and answer** — Offset editorial argument, image strip and right-aligned explanatory text.
3. **Offering** — Asymmetric product presentation with starting-price caption.
4. **Workflow** — Numbered integration sequence with an active row and companion image.
5. **Product demonstration** — Extended deep-stage demonstration with repeated device views.
6. **Credibility** — Architectural human-context image paired with a narrow editorial argument and supporting rationale.
7. **Final action** — Functional footer with brief reassurance, proof marks, link columns, newsletter and legal utility row.

**Transfer:** Adapt the number and order of chapters to the new story while retaining the object poster, asymmetrical arguments, numbered explanation and a contrasting immersive stage as recognizable devices.

## Writing

Calm, direct and conversational, with an optimistic belief that thoughtful technology removes an everyday nuisance. Confidence is expressed through plain promises and explanations rather than technical bravado.

**Do not copy:** Do not reuse Custo names, wordmarks, proprietary product imagery, award marks, prices, investor claims or numerical performance claims. Replace the examples with truthful facts belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; use we sparingly for shared everyday realities, and name the product when describing what it does.
- **Rhythm:** Short two-line opening promise, longer sentence-like section arguments, then compact feature titles and a single explanatory paragraph. Sentence case and full stops predominate.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A broad benefit brought into an everyday personal setting. | 6–10 words | “Receive the world at your doorstep.” |
| Editorial argument | Name the familiar frustration, retire it, and finish with reassurance. | 12–22 words | “Spending time looking for your parcel around the neighbourhood is a thing of the past. That’s a promise.” |
| Supporting lead | One plain sentence about regaining control of ordinary life. | 8–14 words | “Never let a parcel delivery rule your entire schedule again.” |
| Process statement | Direct verb followed by an everyday action or result. | 4–9 words | “Order online, as much as you want.”<br>“Get notified of your delivery.” |
| Action | Discover or learn followed by a specific destination; conversion is shorter. | 2–5 words | “Discover how it works”<br>“Order now” |

**Words and phrasing to use:** your; never worry; works for you; seamlessly; discover; personal assistant

**Avoid:** disruptive ecosystem; revolutionary platform; hypergrowth; unprecedented synergy

**Rules:**

- Lead with what changes for a person, then explain the mechanism.
- Let feature titles sound like normal statements rather than stacked nouns.
- Keep exploration labels specific and conversion labels brief.
- Use reassurance without exclamation marks or repeated urgency.

## Do's and Don'ts

### Do

- Keep major headings at 57.6px with normal tracking and near-1.05 leading at desktop.
- Preserve the 12-column structure with 24px gutters and 76.8px fluid side insets.
- Use 8px media corners consistently across product, lifestyle and device images.
- Let the product silhouette extend past the bottom of the 900px opening.
- Use #8e9194 for explanatory copy and #000000 for the corresponding short title.
- Keep process rows at 40px vertical padding with 1px #d8d8d8 dividers.
- Give the long contrasting chapter an 18px white rim and #4b514d background.
- End with functional newsletter and utility navigation rather than another hero. Breathe with 110px footer top padding.

### Don't

- Do not replace the 57.6px readable display tier with the wordmark artwork's monumental scale.
- Do not make every action a filled pill; exploration uses 304px arrow links.
- Do not add card shadows to the flat 8px media frames.
- Do not color section headings with saturated gradients; large fields stay sage-grey, green-grey or white.
- Do not bold the entire hierarchy; maintain the regular-looking grotesk treatment.
- Do not compress all chapter spacing to a uniform 64px rhythm; long product pauses reach 278px.
- Do not turn inactive process statements into bordered boxes; use the open ruled list.
- Do not shrink device panels into small isolated thumbnails; their close framing is part of the demonstration.

## Motion and responsive

### Motion

**Observed:**

- Headline lines declare transform 1.2s cubic-bezier(0.165, 0.84, 0.44, 1), with staggered delays of 0.58s and 0.66s.
- Media frames declare clip-path 0.6s cubic-bezier(0.165, 0.84, 0.44, 1).
- Process rows declare color 0.8s cubic-bezier(0.165, 0.84, 0.44, 1).
- Primary action declares opacity 0.8s cubic-bezier(0.77, 0, 0.175, 1). The demonstrated chapter keeps its title visually anchored across successive device views.

**Transfer:**

- Use line-wise masked reveals for the short opening promise and restrained clipping on media.
- Keep row emphasis and the corresponding illustration synchronized rather than animating all rows at once.

**Unknown:**

- Exact scroll triggers, device-panel pinning implementation and complete animation choreography are not specified.

### Responsive

**Observed:**

- Declared width breakpoints are 579px, 600px, 767px, 768px, 979px, 1024px and 1280px.
- Headlines scale with max(4vw, 40px), secondary headings with max(2.66667vw, 30px), and page inset with 5.33333vw.
- Small-screen grid classes indicate full-width product and footer groups.

**Transfer:**

- On narrow layouts, stack editorial lead before argument and device panels after their corresponding explanations; keep the giant identity overlay proportional rather than wrapping it.
- Retain the 8px frame treatment and the contrast between the white narrative and deep-stage demonstration.

**Unknown:**

- Exact mobile navigation, spacing overrides and hero object positioning are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
