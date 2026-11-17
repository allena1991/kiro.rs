# Rainbow — pocket-sized luminous theater

## Overview

A dark, friendly product theater with rounded sans-serif lettering and small jewel-like bursts of color. Near-black space, white headlines and smoky gray support copy make detailed interface imagery feel tangible rather than technical. It suits consumer apps and approachable tools that can tell their story through a single persistent product object, then open into a rich collage of possibilities.

### Essentials

- A pocket-sized object outscales the promise: a 354px × 767px upright device sits left of a compact three-line 42px, weight-700 headline, not underneath a giant centered slogan.
- Rounded letters soften the dark stage: SF Rounded Web throughout, with 42px headings at 0.3px tracking and 30px support at 0.2px tracking; small navigation tightens to -0.2px.
- Conversion looks like a softly lit physical control: translucent white at 6%, 80px corner radius, a 2px edge and a restrained white halo; 48px utility and 72px closing sizes.
- Color behaves like emitted light, not painted section bands: #111111 dominates the canvas, with orange, violet, teal and red concentrated in 64px medallions, product imagery and a low closing aurora.
- One product becomes a moving exhibit: keep the rounded device stage through capability chapters with 400px-wide text and 42px internal gaps; use a polished representative interface when no finished product media exists.
- The controlled stage must eventually spill outward: a full-width, edge-clipped collage surrounds a centered 52px two-line statement, followed by a lone glowing 90px app emblem and a dim multicolor horizon. Recreate this with new product cards and a simple proprietary emblem if necessary.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Amber light | `#ff9900` | `--color-orange` | accent, surface | Warm capability medallion and its surrounding glow; not a section fill. |
| Violet light | `#a615d4` | `--color-violet` | accent, surface | Alternate capability medallion. |
| Teal rim | `#077f70` | `--color-teal-edge` | border | Fine rim of the teal medallion. |
| Deep teal light | `#064c43` | `--color-teal` | accent, surface | Alternate capability medallion. |
| Violet rim | `#814388` | `--color-violet-edge` | border | Pink-violet rim, rgba(240,116,255,0.5), visually blended against the dark stage. |
| Amber rim | `#88704c` | `--color-amber-edge` | border | White-gold rim, rgba(255,207,135,0.5), visually blended against the dark stage. |
| Red ember wash | `#3c1e1c` | `--color-red-wash` | surface, accent | Visible red medallion wash: rgba(230,80,72,0.2) over charcoal. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft white | `#f1f1f1` | `--color-action-text` | text, action | Visible button label color: white at 94% over charcoal. |
| Charcoal stage | `#111111` | `--color-canvas` | background | Continuous page canvas, including the closing region. |
| Lit charcoal | `#1f1f1f` | `--color-button-fill` | surface, action | Visible button surface made with white at 6% over charcoal. |
| Smoke shadow | `#3f3f3f` | `--color-copy-bottom` | text | Dark end of the support-copy fade, using white at 24% with overall opacity 0.8. |
| Smoke highlight | `#787878` | `--color-copy-top` | text | Bright end of the support-copy fade, using white at 54% with overall opacity 0.8. |
| Utility gray | `#9f9f9f` | `--color-muted` | text, link | Navigation and availability text; the availability line is further reduced to 0.4 opacity. |
| Clear white | `#ffffff` | `--color-headline` | text | Headlines and the base of footer links; footer links render at 0.6 opacity. |

## Typography

- **SF Rounded Web** — All marketing headings, support, actions and navigation. Soft rounded terminals, open counters and substantial medium-to-bold weights; friendly without cartoon distortion. If unavailable, use **Nunito**. Use weights 500–700; preserve compact headline wrapping and tune width before increasing size. Font stack: "SF Rounded Web", "Nunito", ui-rounded, "SF Pro Rounded", system-ui, -apple-system, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | SF Rounded Web | 700 | 52px | 62px | 0.0073em | Centered two-line statement above the expansive product collage. |
| heading | SF Rounded Web | 700 | 42px | 50px | 0.0083em | Opening promise and capability headings; the promise wraps to three compact lines. |
| support | SF Rounded Web | 500 | 30px | 36px | 0.0067em | Short feature explanations, rendered in a dim text-clipped gradient. |
| button | SF Rounded Web | 600 | 20px | 1 | 0.019em | Closing conversion action. |
| utility | SF Rounded Web | 500 | 16px | 1.25 | -0.0125em | Navigation, footer links and small utility labels. |
| button-small | SF Rounded Web | 600 | 16px | 1 | -0.0125em | Persistent utility action. |
| availability | SF Rounded Web | 500 | 16px | 1.5 | -0.0125em | Centered two-line availability note below the closing action. |

**Notes:**

- Headings are compact rather than monumental: 42px is the main storytelling size; 52px is reserved for the expansive collage statement.
- Display and support use slightly positive tracking while 16px utility text uses -0.0125em. Keep this distinction instead of applying global tight tracking.
- Support paragraphs are unusually prominent at 30px but visually recede through their fading gray fill. Use 36px support lines, 50px headline lines and 62px statement lines.

## Layout

**Density:** Airy theatrical pacing: each capability gets nearly a viewport while the copy itself remains compact.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Explains major pads such as 32px, 64px, 120px and 160px, not every local gap.
- **horizontal step** 6px, horizontal — Explains 12px, 24px, 36px and 42px local intervals; retain exceptions rather than forcing all spacing onto this unit.

| Value | Use |
| --- | --- |
| 8px | Navigation link padding. |
| 12px | Vertical navigation list gap. |
| 16px | Gap between compact app emblem and wordmark. |
| 18px | Closing button-to-availability gap. |
| 24px | Footer link gap. |
| 32px | Footer edge padding. |
| 42px | Feature icon-to-heading and heading-to-support gap; opening logo top padding. |
| 120px | Capability top padding and large collage-stage gap. |
| 148px | Closing action group to app emblem gap. |
| 160px | Closing section top and bottom padding; collage heading top padding. |

### Containers and grids

- **desktop stage**: max width 1280px · side padding 80px. At 1440px, the centered stage leaves equal outer margins. Treat 1280px as the desktop reference width rather than a universal fixed maximum.
- **product and story**: 2 columns · gap 83px. A 354px-wide device is inset within the left 521px rail, with 400px feature copy aligned in the right region. The opening support expands to 420px. Leave a generous far-right margin for the fixed chapter index.
- **closing footer**: gap 24px · side padding 32px. Company line left, a single horizontal row of resource and legal links right; both sit at the bottom of the aurora.

## Corner radius

| Element | Radius |
| --- | --- |
| action pills | 80px |
| device shell | 41.4px |
| capability medallions | 50% |
| small app emblem | 16px |
| closing app emblem | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| button halo | `0px 4px 9px 0px rgba(0,0,0,0.15), 0px 0px 64px 0px rgba(255,255,255,0.04)` | Subtle neutral light surrounding conversion pills. |
| device depth | `0px 4px 24px 0px rgba(0,0,0,0.4)` | Dark contact shadow around the product shell. |
| app emblem glow | `0px 2px 100px 0px rgba(60,112,216,0.5), 0px 4px 16px 0px rgba(0,0,0,0.32)` | Blue bloom around opening and closing app emblems. |

### Surfaces

#### Charcoal canvas · level 0

**Use:** Continuous dark theater behind the entire page.

**CSS:** `background: #111111; overflow-x: clip`

**Observed:** No alternating light bands or visible section dividers.

**Transfer:** Separate chapters with scale and breathing room rather than background changes.

#### Smoky text fill

**Use:** Large supporting copy.

**CSS:** `background-image: linear-gradient(170deg, rgba(255, 255, 255, 0.54) 9%, rgba(255, 255, 255, 0.24) 110%); background-clip: text; -webkit-background-clip: text; color: rgba(0,0,0,0); opacity: 0.8`

**Observed:** The same fade dims the first line of the collage statement at 0.6 opacity.

**Transfer:** Keep the brightest support weaker than the white headline, with a perceptible top-to-bottom fade.

#### Glass control · level 1

**Use:** Conversion pill material.

**CSS:** `background: rgba(255,255,255,0.06); border: 2px solid transparent; border-radius: 80px; box-shadow: 0px 4px 9px 0px rgba(0,0,0,0.15), 0px 0px 64px 0px rgba(255,255,255,0.04)`

**Observed:** A masked pseudo-element supplies a fine white edge fading from 5% to 2% alpha from top to bottom.

**Transfer:** Make the edge subtle and reflective rather than using a bright solid outline.

#### Closing aurora · level 0

**Use:** Atmospheric light behind the final emblem and footer.

**CSS:** `background: radial-gradient(ellipse at 15% 110%, rgba(166,21,212,0.16), rgba(166,21,212,0) 58%), radial-gradient(ellipse at 43% 120%, rgba(255,153,0,0.13), rgba(255,153,0,0) 55%), radial-gradient(ellipse at 95% 110%, rgba(20,150,134,0.22), rgba(20,150,134,0) 60%), #111111`

**Observed:** Low, blurred purple and warm reddish light at the left meets yellow-green near center and cyan-teal on the right. Most of the upper region remains charcoal.

**Transfer:** Match the soft colored horizon; exact stops are not essential. Keep the action well above the brightest light.

## Components

### Utility button

**Use:** Persistent conversion at the upper-right edge.

**CSS:** `background: rgba(255,255,255,0.06); color: rgba(255,255,255,0.94); border: 2px solid transparent; border-radius: 80px; padding: 14px 36px; height: 48px; box-sizing: border-box; box-shadow: 0px 4px 9px 0px rgba(0,0,0,0.15), 0px 0px 64px 0px rgba(255,255,255,0.04)`

**Text style:** `button-small` — SF Rounded Web 600 · 16px/1 · tracking -0.0125em

**Observed:** Uses Glass control material with a small centered availability note underneath. It is separate from the main story column.

**States:** Declared: hover color #ffffff, background rgba(255,255,255,0.08), shadow 0px 4px 9px rgba(0,0,0,0.15), 0px 0px 84px rgba(255,255,255,0.1).

**Transfer:** Use one persistent action, not a competing pair.

### Closing button

**Use:** Main final conversion.

**CSS:** `background: rgba(255,255,255,0.06); color: rgba(255,255,255,0.94); border: 2px solid transparent; border-radius: 80px; padding: 24px 40px; height: 72px; box-sizing: border-box; box-shadow: 0px 4px 9px 0px rgba(0,0,0,0.15), 0px 0px 64px 0px rgba(255,255,255,0.04)`

**Text style:** `button` — SF Rounded Web 600 · 20px/1 · tracking 0.019em

**Observed:** Centered as a standalone pill using Glass control material, with a dim availability note and a separate emblem far below.

**States:** Declared: hover color #ffffff, background rgba(255,255,255,0.08), shadow 0px 4px 9px rgba(0,0,0,0.15), 0px 0px 84px rgba(255,255,255,0.1).

### Chapter navigation

**Use:** Fixed right-hand index through the product story.

**CSS:** `color: #9f9f9f; padding: 8px; text-align: right`

**Text style:** `utility` — SF Rounded Web 500 · 16px/1.25 · tracking -0.0125em

**Observed:** Plain short text in a right-aligned vertical stack with 12px list gaps. The current chapter is brighter; the rest recede.

**States:** Declared: hover opacity 1.

**Transfer:** Use capability names rather than a conventional full-width navigation bar.

### Device stage

**Use:** Persistent visual proof across capability chapters.

**CSS:** `width: 354px; height: 767px; border-radius: 41.4px; overflow: hidden; position: sticky; box-shadow: 0px 4px 24px 0px rgba(0,0,0,0.4)`

**Observed:** Portrait shell with extremely dark framing and fine inset edge reflections. Screen content changes with each adjacent capability while the device stays in the left rail.

**Transfer:** Use a focused, internally consistent product screen per chapter; a clean schematic interface is preferable to stock device photography.

### Capability medallion

**Use:** Small luminous chapter marker above a heading.

**CSS:** `width: 64px; height: 64px; border-radius: 50%; display: flex; align-items: center; justify-content: center; background: #ff9900; border: 1px solid rgba(255,207,135,0.5); box-shadow: inset 0px 11px 12px 0px rgba(255,201,119,1), 0px 2px 100px 0px rgba(255,155,6,0.5)`

**Observed:** A centered 40px symbol sits within a shaded circular badge. Variants use violet with a pink rim, dark teal with a teal rim, a dim red beacon, or metallic gold imagery.

**Transfer:** Assign one small lit badge to a capability, not a rainbow of badges within every paragraph.

### App emblem

**Use:** A tangible identity anchor in the opening and closing.

**CSS:** `width: 90px; height: 90px; border-radius: 24px; box-shadow: 0px 2px 100px 0px rgba(60,112,216,0.5), 0px 4px 16px 0px rgba(0,0,0,0.32)`

**Observed:** A rounded-square icon appears alone below the closing action. Its opening variant is 56px with a 16px radius and sits beside the wordmark.

**Transfer:** Use the new product's own mark, with dimensional shading and a very restrained blue bloom.

### Footer link

**Use:** Compact resources and legal navigation at the very bottom.

**CSS:** `color: #ffffff; opacity: 0.6; text-decoration: none`

**Text style:** `utility` — SF Rounded Web 500 · 16px/1.25 · tracking -0.0125em

**Observed:** One horizontal link row uses 24px gaps; the company line balances it from the far left.

**States:** Declared: hover opacity 0.85.

## Imagery and graphics

### Persistent pocket theater

**Use:** Opening and capability storytelling.

**Observed:** An upright, front-facing app screen occupies nearly the full viewport height on the left. Its black frame is only just distinguishable from the charcoal page. Interface panels carry the strongest blue, green and other saturated accents; no lifestyle photos or explanatory arrows surround the phone.

**Transfer:** Show a real task in a dark product interface. If polished media is unavailable, build a restrained portrait interface with a few readable rows and one active control; keep the same coherent shell across views.

**Build:** Create a 354px × 767px rounded clipping wrapper with 41.4px corners. Layer a dark device frame, subtle top-edge inset highlights, the screen and a soft bottom darkening gradient. Preserve front-on perspective rather than tilting the device.

### Edge-spilling possibility collage

**Use:** A signature expansion after focused product chapters.

**Observed:** Many dark, rounded product tiles form staggered vertical stacks, with different widths and heights. Some are short horizontal rows, others tall panels with charts or choices. The wall extends beyond both sides and below the visible region. Subtle jewel-tinted surfaces remain subordinate to bright tiny symbols and interface details; a clear space shelters the centered two-line statement above.

**Transfer:** Turn the new product's useful outputs into diverse tiles: documents, projects, results or objects. The minimum version uses several tile shapes, distinct restrained tints and meaningful content; a uniform feature-card grid loses the effect.

**Build:** Use a clipped full-width wrapper with staggered columns. Mix roughly 150px–307px-wide compact tiles and taller panels up to 260px. Back each with a charcoal-to-translucent-accent gradient, a low-alpha white inset edge and rounded corners; vary vertical offsets and let outer columns leave the viewport. Keep center-top space free for the statement. Do not hard-code blur or partial opacity as the resting appearance.

### Low aurora horizon

**Use:** Signature final atmosphere behind the app emblem and footer.

**Observed:** Diffuse multicolor light grows upward from the bottom edge, strongest around the footer. The isolated emblem has its own blue halo, visually separate from the broader purple-to-teal horizon.

**Transfer:** Retain a dim multicolor closing horizon even if the new product has no photographic or 3D assets. Use a simple shaded emblem as the focal point.

**Build:** Use Closing aurora as the base. Spread three or four broad radial gradients across the lower 765px, centered below the bottom edge. Keep purple at left, warm orange near left-center and teal at right with alpha roughly 0.13–0.22. Add a vertical charcoal fade over the upper half so the button remains surrounded by darkness.

### Icons

**Observed:** The menu uses two short white horizontal strokes. Feature markers are larger filled symbols or dimensional coin-like emblems centered in 64px lit circles, with 40px inner artwork. Small UI glyphs belong inside the product imagery.

**Transfer:** Choose simple filled silhouettes with rounded geometry for marketing badges; do not replace the medallions with thin outlined icons scattered across the page.

## Section recipes

How recurring sections are built.

### First screen: Pocket theater opening

**Observed:** Charcoal canvas runs edge to edge. A small menu sits upper left; a 56px app emblem and wordmark align over the story column, while Utility button occupies the upper right with a dim availability note below it. The main composition pairs Device stage on the left with a 376px-wide, three-line white promise in the middle-right. The 42px heading is vertically centered against the device, followed by Smoky text fill support at 30px across 420px with a 42px gap. Chapter navigation anchors the far-right edge around mid-height. Within the first 900px the complete phone, identity, headline, support and persistent action are visible; the next capability begins below. Layers are canvas, dark device shadow and frame, screen, then white story text and fixed controls.

**Transfer:** Keep one substantial product object at nearly viewport height and let a compact benefit statement balance it. Without finished media, use a carefully drawn representative interface in Device stage. For a more specific landing page, open on the relevant task while retaining this object-to-copy hierarchy.

**Avoid:** Do not turn the opening into an enormous centered headline with a tiny phone floating underneath, or put the only action below the first screen.

**Text style:** `heading` — SF Rounded Web 700 · 42px/50px · tracking 0.0083em

### Lit capability chapter

**Observed:** The same left Device stage pairs with a 400px-wide right story stack: Capability medallion, white heading, then Smoky text fill support, each separated by 42px. Chapters occupy about 932px with 120px top padding; the copy block remains centered beside the device, not top-aligned to a card.

**Transfer:** Use each chapter for a single capability and its concrete user outcome. Change the screen and medallion hue while retaining the shell and text alignment.

**Text style:** `heading` — SF Rounded Web 700 · 42px/50px · tracking 0.0083em

### Expansion statement and collage

**Observed:** The constrained two-column theater gives way to Edge-spilling possibility collage. A centered pair of 52px bold lines sits at the top with a 7px gap: the first is subdued using Smoky text fill at 0.6 opacity, the second white. The stage starts with 160px top padding and lets staggered media spill past the side boundaries.

**Transfer:** Express a unifying promise in two short phrases, then show variety through the collage rather than adding a long explanation.

**Text style:** `statement` — SF Rounded Web 700 · 52px/62px · tracking 0.0073em

### Action above a colored horizon

**Observed:** Closing button is centered within a 696px-tall closing region with 160px vertical padding. The availability note follows by 18px, then App emblem sits 148px below the action group. Closing aurora rises behind the emblem into the footer, whose company line sits left and Footer link row right with 32px edge padding. There is no extra giant closing headline.

**Transfer:** End with a decisive action, a short practical qualifier and an isolated product identity. Give the low aurora and footer enough space to feel like the theater's final scene.

**Text style:** `button` — SF Rounded Web 600 · 20px/1 · tracking 0.019em

## Page flow

**Storyline:** Compact promise beside product proof → focused capability chapters → expansive range of possibilities → isolated conversion and luminous closing identity.

### Consumer-product landing page that makes a complex app feel approachable and immediately usable

1. **Promise** — A full-height portrait product view balances a concise benefit headline and dim supporting explanation.
2. **Capability chapters** — The product shell persists as screen content changes alongside lit medallions, short headings and outcome-focused paragraphs.
3. **Breadth proof** — A two-line unifying statement introduces an overflowing collage of product outputs.
4. **Closing call** — One glassy action and availability line sit above an isolated app emblem, dim aurora and compact footer.

**Transfer:** Adapt the number and order of capability chapters to the new product, keeping the contrast between a focused persistent object and a later exuberant field of outputs.

## Writing

Casual, confident and helpful. Complex capabilities are translated into everyday actions with a little conversational wit rather than technical ceremony.

**Do not copy:** Do not reuse Rainbow names, logos, token names, account identities, third-party marks, numerical balances, leverage claims or availability claims unless they are true for the new product. Source examples demonstrate tone, not reusable product claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Direct second person: your phone, your pocket, your balance. Name the product sparingly, mainly in the action or an important benefit.
- **Rhythm:** Short noun headings contrast with conversational paragraphs of two or three brief sentences. Fragments and compressed pairs provide emphasis; exclamation marks are unnecessary.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Make a complex activity sound easy, broad and close at hand. | About 12–16 words over three lines | “The easiest way to trade any market from your phone” |
| Capability heading | Use a familiar noun or a compact action-plus-outcome phrase. | 1–2 words | “Live Data”<br>“Earn Rewards” |
| Supporting copy | Begin with a plain-language simplification or punchy fragments, then explain the concrete convenience. | About 20–40 words | “Real-time prices. Pro-level charts.”<br>“Crypto, minus the hard stuff.” |
| Unifying statement | Pair singular simplicity with expansive reach. | Two phrases of 2 words each | “One App”<br>“Every Market” |
| Primary action | A direct verb, optionally followed by the product name. | 1–2 words | “Download [Brand]” |

**Words and phrasing to use:** your; from your pocket; minus the hard stuff; everything you need; any; every; real-time

**Avoid:** revolutionary ecosystem; paradigm shift; unlock limitless potential; enterprise-grade synergies

**Rules:**

- Lead with what someone can do rather than infrastructure.
- Allow a friendly everyday reference to make an unfamiliar feature feel familiar.
- Use a short practical availability line beneath the action, not another sales pitch.
- Keep chapter paragraphs short enough to fit within a 400px column without becoming an essay.

## Do's and Don'ts

### Do

- Keep the page canvas #111111 through both storytelling and conversion.
- Use 42px rounded bold headings and 30px medium support as the primary storytelling pair.
- Preserve 42px gaps in the capability stack instead of shrinking them to standard paragraph margins.
- Keep Device stage front-facing and at 354px × 767px in the desktop composition.
- Use 64px glowing medallions as small chromatic anchors rather than colored section backgrounds.
- Render pills with a 6% white surface, subtle edge and 80px radius.
- Create varied tile proportions in the full-width collage and let its outer columns extend out of view.
- Finish with the 90px emblem separated from the action group by 148px and a low dim aurora.

### Don't

- Do not apply negative tracking to 42px headings; their slight 0.3px openness is part of the rounded character.
- Do not render the 30px supporting text as solid white; it must recede behind the headline.
- Do not turn the translucent buttons into saturated blue or white-filled rectangles.
- Do not use sharp 8px corners for the device or identity emblem; their silhouettes are deeply rounded.
- Do not spread feature colors across large flat panels; the dark stage should remain dominant.
- Do not promote tiny charts, percentages or UI labels into a separate marketing type system.
- Do not apply persistent blur to the collage tiles; their interface detail should remain legible.
- Do not add a tall multi-column sitemap or a newsletter form to the understated closing horizon.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background, color and box-shadow transitions of 0.3s cubic-bezier(.25,1,.5,1), with transform at 1s cubic-bezier(.22,1,.36,1).
- Opening word reveals declare opacity, transform and filter transitions of 1.1s cubic-bezier(.22,1,.36,1), staggered in 80ms increments.
- Collage elements declare 0.12s linear opacity, transform and filter transitions. Footer and navigation opacity transitions use 0.2s cubic-bezier(0.25,1,0.5,1).

**Transfer:**

- Use the slow word reveal to introduce the compact promise, then resolve to crisp text.
- Let the product screen change with the active chapter while its outer silhouette stays stable.
- Keep interaction light centered on the pill's halo rather than introducing unrelated bouncing controls.

**Unknown:**

- Exact scroll thresholds, device-screen choreography and canvas aurora implementation are not specified.
- Focus-visible and pressed treatments are not established.

### Responsive

**Observed:**

- Declared width breakpoints occur at 600px, 959px, 960px, 1279px and 1280px.

**Transfer:**

- On narrow screens, retain one dominant rounded product object and compact rounded headline; stack the story rather than squeezing the full desktop rail and index side by side.
- Keep the collage edge-clipped and varied in tile size, and allow footer links to wrap while preserving the isolated final emblem.

**Unknown:**

- Narrow-screen layouts and actual breakpoint-specific sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
