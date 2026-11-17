# Glow — porcelain product theater

## Overview

A bright, app-like marketing style with a stationary pitch beside a scrolling gallery of product demonstrations. White and cool pale gray give softly modeled devices a porcelain quality, while orchid actions and tiny multicolored emblems add playful energy. Rounded grotesk typography and short, friendly benefit statements suit approachable consumer software with visually demonstrable capabilities.

### Essentials

- A pitch that stays while the product moves: a fixed left half holds a 450px-wide message; the right half scrolls 688px-wide panels capped at 700px, separated by 24px.
- A compact, substantial promise rather than a giant slogan: Roobert 56px/1, weight 600, -1px tracking, left-aligned and wrapped into roughly three lines; feature titles shrink to 24px/1.28 at weight 600.
- Porcelain exhibits, not bordered cards: cool #f4f5f6 stages with 40px corners contain white device shells and softly floating interface fragments. Every new page needs this sculptural product treatment; a carefully rebuilt interface fragment is the fallback when device artwork is unavailable.
- Small orchid pills are the conversion language: #cc62d5 actions, 38px tall, 19px radius, 10px 14px padding and white 16px medium labels; dark pills belong to platform-specific downloads.
- Color behaves like a set of exhibit markers: most of the page stays white or pale gray; 48px colored circles with 24px white symbols introduce individual capabilities. Saturated fields stay inside product artwork or a contained circular backdrop, never across the page canvas.
- The ending is a useful chooser with a little spectacle: a 40px/1.1 bold violet-to-pink gradient call precedes centered option groups, white platform pills and dark download buttons, all inside the same rounded gray stage.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orchid | `#cc62d5` | `--color-action` | action, border, accent | Primary acquisition actions and their focus outline. |
| Electric violet | `#8800ff` | `--color-gradient-start` | text, accent | Starting stop of the closing call's clipped radial gradient. |
| Warm violet | `#a732d6` | `--color-gradient-middle` | text, accent | Middle stop of the closing call's clipped radial gradient. |
| Light pink | `#ef79ff` | `--color-gradient-end` | text, accent | Final stop of the closing call's clipped radial gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement orange | `#ec660d` | `--color-orange` | text, surface, accent | Release text, NEW badge and one capability marker. |
| Capability violet | `#682fff` | `--color-purple` | accent | A capability medallion. |
| Capability blue | `#325ffa` | `--color-blue` | accent | A capability medallion. |
| Capability ochre | `#d19d20` | `--color-gold` | accent | A capability medallion. |
| Capability coral | `#e83b47` | `--color-red` | accent, surface | A capability medallion and a contained circular product-art backdrop. |
| Capability green | `#07a460` | `--color-green` | accent | A capability medallion. |
| Peach wash | `#fef5ef` | `--color-announcement-wash` | surface | Visible announcement backing; orange at 0.067 alpha over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#131517` | `--color-ink` | text | Headlines and body text. |
| Charcoal | `#333537` | `--color-button-dark` | action, border | Platform-specific download buttons. |
| Secondary gray | `#737577` | `--color-secondary` | text | Quotation text and uppercase exploration prompt. |
| Tertiary gray | `#b3b5b7` | `--color-muted` | text, link | Attribution and persistent utility links. |
| Cool porcelain | `#f4f5f6` | `--color-stage` | surface | All large product exhibition panels and the closing chooser. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, option pills, device-like surfaces and reversed button labels. |

## Typography

- **Roobert** — All marketing text, headings and controls. Rounded geometric grotesk with open counters, single-storey forms and a friendly but substantial bold cut. If unavailable, use **DM Sans**. Use weights 400–700; preserve compact headline width and tight display tracking. Font stack: "Roobert", "DM Sans", "Noto Sans", "Noto Sans JP", "Noto Sans KR", "Noto Sans SC", "Noto Sans TC", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Roobert | 600 | 56px | 1 | -1px | Main promise in the stationary pitch. |
| closing-call | Roobert | 700 | 40px | 1.1 | normal | Gradient conversion headline in the final chooser. |
| feature-heading | Roobert | 600 | 24px | 1.28 | normal | Centered capability headings, usually one or two lines. |
| option-heading | Roobert | 700 | 24px | 28px | normal | Option-group headings inside the closing chooser. |
| quote | Roobert | 400 | 18px | 1.2 | normal | A short quotation and its lighter attribution. |
| body | Roobert | 400 | 16px | 1.5 | normal | Support text, release announcement, option captions and utility links. |
| button | Roobert | 500 | 16px | 1.5 | normal | Primary and platform-specific action labels. |
| badge | Roobert | 600 | 13px | 1.5 | normal | Compact NEW marker within an announcement. |
| eyebrow | Roobert | 600 | 12px | 1.5 | 1px, uppercase | Two-line exploration cue at the base of the opening stage. |

**Notes:**

- Only the main promise has negative tracking. Keep feature titles and body copy at normal tracking rather than applying a global tight-letterspacing treatment.
- Use sentence case for promises and most benefits; reserve tracked uppercase for the tiny exploration cue and compact release marker.
- The closing call is smaller than the main promise but gains emphasis through weight and a text-clipped gradient. It is not a new full-width display tier.

## Layout

**Density:** Airy around the pitch and within product stages; compact in controls and option groups.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Most vertical margins and padding follow an 8px rhythm; button padding and horizontal gaps use separate practical values.

| Value | Use |
| --- | --- |
| 8px | Action separation, badge spacing and quote-to-attribution separation. |
| 12px | Utility-link gaps and announcement side padding. |
| 16px | Medallion-to-heading spacing, option heading separation and paired download gap. |
| 24px | Panel-to-panel gap and page top inset. |
| 32px | Right gutter of the scrolling gallery. |
| 40px | Feature stage top margin and heading-to-art separation. |
| 48px | Separation around the main pitch's headline and testimonial area. |
| 64px | Closing chooser top and bottom padding. |
| 100px | Top breathing room above the opening product object. |

### Containers and grids

- **desktop split**: 2 columns · side padding 24px. A fixed message occupies the left half while product stages scroll down the right. The small wordmark sits at the upper left and utility links at the lower left of the fixed area.
- **pitch column**: max width 450px. Vertically centered within a 696px-wide left region at desktop. App emblem, announcement, promise, paired actions and quote align to the same left edge.
- **exhibit column**: max width 700px · 1 column · gap 24px · side padding 32px. Right-side gallery; panels are 688px wide at a 1440px viewport, with variable heights of 624px–779px. Media can extend outside its own frame but is clipped by the panel.
- **closing option row**: gap 16px. Centered platform-specific actions. A separate four-option row pairs platform symbols with white label pills.

## Corner radius

| Element | Radius |
| --- | --- |
| exhibit panels | 40px |
| action and option pills | 19px |
| app emblem backing | 18px |
| announcement strip | 8px |
| release badge | 4px |
| medallions | 100px |
| circular art backdrop | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| app emblem lift | `0px 13px 13px rgba(0,0,0,0.03), 0px 3px 7px rgba(0,0,0,0.04)` | Soft lift for the small app emblem, not the large stage panels. |

### Surfaces

#### White canvas · level 0

**Use:** The uninterrupted background behind the fixed pitch and between exhibits.

**CSS:** `background: #ffffff; color: #131517`

#### Porcelain stage · level 1

**Use:** Product demonstrations and final conversion chooser.

**CSS:** `background: #f4f5f6; border-radius: 40px; overflow: hidden; box-shadow: none`

**Observed:** Large, borderless slabs; depth comes from the objects inside rather than shadows around the slab.

**Transfer:** Keep this neutral stage consistent even when capability artwork changes color.

#### Announcement wash · level 1

**Use:** Release information above the main promise.

**CSS:** `background: rgba(236, 102, 13, 0.067); border-radius: 8px; padding: 8px 12px`

**Observed:** A shallow warm strip with an orange badge followed by orange text.

**Transfer:** Use for one timely update, not as a repeated promotional banner.

#### App emblem backing · level 2

**Use:** The compact app object above the announcement.

**CSS:** `width: 74px; height: 74px; background: #ffffff; border-radius: 18px; filter: drop-shadow(rgba(0, 0, 0, 0.03) 0px 13px 13px) drop-shadow(rgba(0, 0, 0, 0.04) 0px 3px 7px) drop-shadow(rgba(0, 0, 0, 0.04) 0px 0px 0px)`

**Observed:** A colorful rounded app symbol sits over this softly lifted backing.

**Transfer:** Use the new product's own compact symbol, retaining its object-like presence.

## Components

### Primary button

**Use:** Paired acquisition actions in the fixed pitch.

**CSS:** `display: flex; align-items: center; justify-content: center; box-sizing: border-box; height: 38px; padding: 10px 14px; background: #cc62d5; border: 1px solid #cc62d5; border-radius: 19px; color: #ffffff`

**Text style:** `button` — Roobert 500 · 16px/1.5

**Observed:** Two text-only actions sit side by side and wrap when needed. The first targets desktop use and the second opens mobile acquisition.

**States:** Declared: hover text-decoration none, color #fff, background-color #bb2dc7, border-color #bb2dc7; focus-visible outline #cc62d5 solid 2px with 2px offset.

**Transfer:** Keep labels short and destination-specific rather than adding a large arrow or oversized icon.

### Platform download button

**Use:** Platform-specific actions in the closing chooser.

**CSS:** `display: flex; align-items: center; justify-content: center; box-sizing: border-box; height: 38px; padding: 10px 14px; background: #333537; border: 1px solid #333537; border-radius: 19px; color: #ffffff`

**Text style:** `button` — Roobert 500 · 16px/1.5

**Observed:** A small white platform symbol precedes the label; a pair is centered below brief mobile support copy.

**States:** Declared: hover color #fff, background-color #535557, border-color #535557; focus-visible outline #333537 solid 2px with 2px offset.

### Exhibit panel

**Use:** One visual capability chapter.

**CSS:** `background: #f4f5f6; border-radius: 40px; max-width: 700px; margin-bottom: 24px; overflow: hidden`

**Text style:** `feature-heading` — Roobert 600 · 24px/1.28

**Observed:** Centered medallion and benefit title precede a large product scene. Art changes between a single device, multiple devices and floating interface fragments.

**Transfer:** Give each panel one visible job; let the interface provide the explanation rather than adding long text.

### Capability medallion

**Use:** Small color-coded marker above each exhibit title.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 48px; height: 48px; border-radius: 100px; background: #325ffa; color: #ffffff`

**Observed:** A 24px white filled symbol is centered in the disk. Other chapters use orange, green, coral, violet or ochre; the disk remains the same size.

**Transfer:** Assign a distinct solid hue to each capability, while keeping the glyph simple and white.

### Release announcement

**Use:** Timely availability update above the main promise.

**CSS:** `display: flex; align-items: center; padding: 8px 12px; border-radius: 8px; background: rgba(236, 102, 13, 0.067); color: #ec660d; height: 40px; box-sizing: border-box`

**Text style:** `body` — Roobert 400 · 16px/1.5

**Observed:** A Release badge precedes a single short sentence. The strip is narrower than the pitch column.

### Release badge

**Use:** Compact marker at the start of the release announcement.

**CSS:** `padding: 2px 8px; margin-right: 8px; background: #ec660d; color: #ffffff; border-radius: 4px`

**Text style:** `badge` — Roobert 600 · 13px/1.5

**Observed:** A rectangular uppercase tag, deliberately less rounded than the surrounding controls.

### Platform option pill

**Use:** Caption and selection target beneath a platform symbol.

**CSS:** `width: 82px; height: 40px; box-sizing: border-box; padding: 8px 0px; background: #ffffff; border-radius: 19px; text-align: center; color: #131517`

**Text style:** `body` — Roobert 400 · 16px/1.5

**Observed:** Four equal pills form a centered row, each beneath its own full-color platform logo.

**Transfer:** Use equal-width options for comparable destinations; preserve the symbol-above-label arrangement.

### Utility link

**Use:** Persistent lower-left documentation, help and legal navigation.

**CSS:** `color: #b3b5b7; text-decoration: none`

**Text style:** `body` — Roobert 400 · 16px/1.5

**Observed:** An unboxed horizontal row with 12px gaps, ending in a small social symbol. It remains visible alongside the scrolling gallery.

**States:** Declared: hover text-decoration none, color #737577; focus-visible behavior is unknown.

### Gradient closing call

**Use:** Headline of the final acquisition chooser.

**CSS:** `background-image: radial-gradient(86% 86% at 6% 9%, #8800ff 0%, #a732d6 51%, #ef79ff 100%); background-clip: text; color: rgba(0, 0, 0, 0)`

**Text style:** `closing-call` — Roobert 700 · 40px/1.1

**Observed:** One short centered line introduces the option groups; the surrounding stage stays neutral.

**Transfer:** Use a direct imperative appropriate to the new product, keeping the gradient confined to the letters.

## Imagery and graphics

### Porcelain device exhibits

**Use:** Opening product stage and recurring capability demonstrations.

**Observed:** White, softly beveled phones are shown straight-on, with delicate cool edge shading and diffuse shadows. A single phone dominates the opening stage; later exhibits enlarge one phone until its lower edge is clipped, or arrange three phones in a horizontal lineup clipped at the right. Interfaces remain readable, predominantly white, and supply most of the fine detail.

**Transfer:** Render the new product in similarly frontal white shells, or use one carefully composed interface panel with softly modeled edges. The minimum version is a real interface image with a white surround and low-contrast layered shadow, never a generic empty device.

**Build:** Place a white rounded device shell over the porcelain stage, with a subtle inset gray edge and diffuse rgba(0,0,0,0.08) shadow. Center a tall device around half the stage width, or arrange narrower shells side by side. Keep lighting frontal, the background flat and the content sharp.

### Whispered feature typography

**Use:** Behind the main object in the opening exhibit.

**Observed:** Oversized, pale gray capability phrases repeat across several tightly stacked lines behind the phone. The words are clipped at the panel edges and interrupted by the device, reading as texture rather than a second headline.

**Transfer:** Use relevant short capability phrases for the new product. Preserve this typographic backing even without device art: place a polished interface fragment in front of it.

**Build:** Create a clipped absolute layer across the middle of the stage; repeat bold capability phrases separated by bullets over roughly six lines. Use low-opacity near-black text, approximately 40px with tight leading, and position the opaque product object above it. Do not let this backing compete with the main pitch.

### Floating interface fragments

**Use:** Capability demonstrations that do not need a full device.

**Observed:** A large white summary card floats above a receding stack of smaller activity or reward rows. Lower rows fade into the pale stage. The art is taller and wider than its short heading, and remains centered.

**Transfer:** Show one informative summary and a few supporting records from the new product; use depth, overlap and fading instead of surrounding explanatory paragraphs.

**Build:** Stack white rounded interface images vertically with soft low-alpha shadows; keep the first fully opaque and reduce opacity down the stack. Clip or mask the bottom into the stage color. Use a meaningful status accent inside the art without turning the whole stage into a colored card.

### Contained color theater

**Use:** Selected capability-art backdrops.

**Observed:** A coral circular field backs one device scene. Another scene layers a phone and browser approval panel over vivid pink, yellow, green and violet sculptural artwork on black; the dark area is confined inside the pale exhibit, not used as a page theme. Translucent iridescent token-like disks accent another device.

**Transfer:** Give at least one product scene a contained, playful object or color field. A flat coral disk behind a polished interface is the minimum substitute for elaborate sculptural artwork.

**Build:** For the simple variant, position a 360px coral circle behind a centered device inside the stage. For a richer variant, layer a dark art rectangle behind white product windows and add a few oversized curved SVG ribbons in orchid, violet and gold; clip the composition to the exhibit. Keep saturated forms behind the product rather than over its controls.

### Icons

**Observed:** Capability markers use white filled 24px SVG silhouettes in 48px colored disks. Action symbols are 16px filled icons; the opening scroll arrow is a 20px gray outline with 2px round strokes. The small dark wordmark occupies the upper-left corner without a navigation bar.

**Transfer:** Use a single family of uncomplicated filled symbols for capabilities and recognizable platform marks for downloads. Keep the outlined arrow as a distinct navigation cue, not a style for all icons.

## Section recipes

How recurring sections are built.

### First screen: Stationary pitch and product stage

**Observed:** The first 900px presents two nearly equal halves. A small dark wordmark anchors the upper-left corner; the fixed left pitch is vertically centered with an app emblem, warm Release announcement, a left-aligned 56px/1 promise spanning about three lines, paired Primary buttons, then a short gray quotation with lighter attribution. No conventional top navigation spans the page. Behind and to the right, a Porcelain stage begins near the page top, with 40px corners, an oversized pale typographic backing, and a centered white phone about 260px wide and 530px tall. The full object, exploration cue and a white circular arrow tab at the stage's lower edge are visible. The first panel is 779px tall, and the start of the next panel peeks into the bottom of the first viewport. Utility links sit at the fixed left area's bottom edge. Subsequent capability details extend below the fold.

**Transfer:** Keep a persistent, compact promise opposite a visually richer scrolling exhibit. Replace the phone with a real product object or a polished interface fragment while retaining the pale phrase texture behind it. For a narrower-purpose landing page, the pitch can name that specific outcome and the gallery can show fewer, deeper demonstrations; preserve the split relationship rather than adding a conventional hero above it.

**Avoid:** Do not center the pitch across the page, replace the right stage with an unframed flat image, or let the opening become an oversized headline with the product pushed entirely below the fold.

**Text style:** `display` — Roobert 600 · 56px/1 · tracking -1px

### Medallion-led capability exhibit

**Observed:** The Exhibit panel starts with 40px of breathing room, a centered Capability medallion, a 16px gap and a 24px/1.28 benefit title. Roughly 40px separates the title group from the main image. Device and fragment compositions dominate the remaining panel; no repeated paragraph block accompanies every feature. Panels are separated by 24px.

**Transfer:** Pair one clear outcome with one convincing visual. Vary the product scene between a large detail, a device lineup and floating records while keeping the stage and title construction stable.

**Text style:** `feature-heading` — Roobert 600 · 24px/1.28

### Contained theatrical demonstration

**Observed:** Within the same exhibit system, a device may overlap a 360px coral disk, or multiple product windows may sit over vivid sculptural art on a dark rectangle. The medallion and short heading remain above this scene on pale gray.

**Transfer:** Use this treatment to emphasize an especially tangible benefit or cross-context interaction; retain the neutral outer shell so the theatrical scene feels like an exhibit rather than a new page theme.

**Text style:** `feature-heading` — Roobert 600 · 24px/1.28

### Gradient option chooser ending

**Observed:** The final Porcelain stage is 624px tall with 64px top and bottom padding. A centered Gradient closing call leads into an option heading and two short centered support lines. Four platform symbols sit above equal white Platform option pills. A second option heading and brief support copy precede a centered pair of Platform download buttons. The fixed pitch and Utility links remain visible to the left; no separate full-width footer follows the chooser.

**Transfer:** End with a practical set of acquisition routes, device options or comparable next steps. Preserve the compact gradient invitation and the two-level option hierarchy, adapting the number of choices to the new offering.

**Text style:** `closing-call` — Roobert 700 · 40px/1.1

## Page flow

**Storyline:** Persistent promise and acquisition actions alongside product introduction → visual capability chapters → contained theatrical proof → practical acquisition chooser.

### Introduce approachable consumer software and turn exploration into installation

1. **Promise** — Stationary app emblem, release update, substantial three-line headline, paired acquisition actions and a short endorsement.
2. **Product introduction** — A white device floats in a pale rounded exhibit over whispered capability phrases, with a scroll cue.
3. **Capability chapters** — Repeated medallion-led panels use device details, phone lineups and fading interface stacks to show outcomes.
4. **Cross-context proof** — Overlapping mobile and desktop product windows sit on vivid contained artwork.
5. **Closing call** — A gradient invitation introduces centered platform choices and direct download controls while the pitch stays accessible.

**Transfer:** Keep the promise and next step accessible while the reader explores visual proof. Choose capabilities relevant to the new product rather than reproducing a particular chapter count or order.

## Writing

Friendly, direct and product-confident rather than technical or grandiose. Benefits are expressed in ordinary language, with visual demonstrations doing most of the explaining.

**Do not copy:** Do not reuse Glow's name, emblem, artwork, wallet claims, Solana-specific promises, platform availability, quoted endorsement or attribution. Use only the new product's supported claims and properly authorized assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader with you and your; name the product when describing availability or an action. Feature titles often omit the subject and begin directly with a verb.
- **Rhythm:** Short benefit headlines, sometimes split into two punchy sentence fragments. Support copy stays to one short sentence over one or two centered lines; actions use a verb plus destination. Exclamation is reserved for a release update.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Main promise | A personal, welcoming product-category promise that suggests preference rather than corporate superiority. | 6–9 words | “Your new favorite Solana wallet awaits.” |
| Capability heading | A plain verb and benefit, or two short fragments that compress a practical outcome. | 3–11 words | “All your activity. In one place.”<br>“Effortlessly Explore NFTs”<br>“Connect to apps on desktop, and on-the-go.” |
| Support copy | A concise explanation of where and how the product helps. | One sentence | “Turn your browser into an easy-to-use Solana wallet.” |
| Primary action | Get plus the destination or platform; no cleverness. | 3–4 words | “Get for Chrome”<br>“Get Mobile App” |
| Release update | Name the product and announce a concrete availability change. | One short sentence | “[Brand] is now available on Android!” |

**Words and phrasing to use:** your new favorite; in one place; effortlessly; easy-to-use; get; explore; now available

**Avoid:** revolutionary ecosystem; unparalleled; industry-leading solution; unlock limitless possibilities; enterprise transformation

**Rules:**

- Lead with a visible user outcome rather than architecture.
- Let the product demonstration carry details; do not add a paragraph beneath every feature title.
- Make destination labels specific enough that paired actions are meaningfully different.
- Use a real short endorsement only when available; otherwise use a concise factual reassurance in the same secondary position.

## Do's and Don'ts

### Do

- Keep the main promise at 56px/1 and weight 600 with -1px tracking on desktop.
- Keep the left pitch within 450px while right exhibits remain capped at 700px.
- Use 40px panel corners and 24px separations to make a continuous exhibition column.
- Introduce capabilities with 48px solid medallions and 24px white glyphs.
- Keep acquisition controls compact at 38px tall with 19px corners.
- Use 64px top and bottom breathing room for the final chooser.
- Preserve the contrast between sharply readable product content and softly shaded white device shells.
- Keep the lower-left utility row visually subordinate in #b3b5b7 with 12px gaps.

### Don't

- Do not replace the pale gallery with a grid of small bordered feature tiles; the 688px-wide exhibits are the visual unit.
- Do not apply shadows to the outer stage panels; reserve depth for the emblem and product objects.
- Do not use the violet-to-pink headline gradient on every heading; it is a conversion flourish.
- Do not turn colorful medallion hues into full-page background bands.
- Do not enlarge pill buttons into tall rectangular blocks or add heavy shadows to them.
- Do not apply uppercase or 1px tracking to normal headings and body text.
- Do not use dark device shells as the default; white porcelain-like objects establish the visual tone.
- Do not append a dense full-width link directory after the chooser; the utility navigation belongs with the stationary pitch.

## Motion and responsive

### Motion

**Observed:**

- Actions and several surfaces declare all 0.3s cubic-bezier(0.4,0,0.2,1) transitions.
- Buttons also declare outline 0s so focus outlines are immediate.
- The left pitch remains fixed while the right product gallery scrolls.

**Transfer:**

- Preserve immediate focus outlines and the declared short color transitions on compact actions.
- Make gallery scrolling the main spatial behavior, with the pitch and acquisition actions stationary at desktop.

**Unknown:**

- Playback and timing of device-art animation are not established; named keyframes alone do not define a reusable animation sequence.

### Responsive

**Observed:**

- Declared width breakpoints are 450px, 650px, 820px and 1000px.
- The desktop pitch's action row supports wrapping.

**Transfer:**

- On screens too narrow for the split, use a stacked pitch followed by full-width exhibits; keep the product object, pale phrase backing and rounded stage together.
- Let option rows wrap before reducing pill labels, and scale device compositions within their clipped stage rather than shrinking the text hierarchy indiscriminately.

**Unknown:**

- Exact mobile stacking order, fixed-position behavior and typography changes are not established. The stacking treatment is guidance rather than a measured mobile layout.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
