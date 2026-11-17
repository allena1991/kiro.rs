# Interfere — prismatic software on paper

## Overview

A white, technically literate style with soft spectral light and unusually delicate interface staging. Medium-weight grotesk headlines and compact product detail are balanced by broad empty space, with a literary serif reserved for human testimony. It suits software platforms and tools that want to feel capable without looking heavy: mostly monochrome, lightly architectural, and punctuated by translucent color rather than saturated blocks.

### Essentials

- The promise is a compact sentence, not a billboard: InterVariable 56px/1, weight 500, -0.02em tracking in the main opening; ordinary section heads drop to 28px/36px with -0.01em tracking.
- The opening couples a left-hand two-line promise with right-aligned explanation and tiny actions, then lets a full-size application window overflow the right edge: 1200px content width, 144px top breathing room and a 1440px-wide product stage.
- Conversion controls stay tool-sized and squared-off: 32px height, 8px radius, 13px/20px medium text, a near-black primary and white raised secondary separated by 12px.
- Color behaves like refracted light around an otherwise neutral page: warm orange through pink and violet to blue at 20% alpha, blurred 50px behind the main object and 100px at the closing boundary; keep text and ordinary sections overwhelmingly monochrome.
- Product imagery emerges from white instead of sitting in opaque picture boxes: 12px outer shells, 0.5px low-contrast edges, light neutral backings and white gradient fades across the bottom and sides. Use a legible representative workflow panel if no finished application artwork exists.
- The ending is a second visual identity moment: centered 56px two-line promise, paired compact actions, an assistant-link utility strip, four restrained footer columns and a 1200×180px pale pixel-stepped word sculpture fading into white. Recreate the sculpture with the new product's own name or a short promise.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Selected-word blue | `#0588f0` | `--color-blue` | text, accent | Isolated emphasized verb in an explanatory headline; #0086f0 at 98% over white, never a broad marketing fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Refracted orange | `#ffd8cc` | `--color-glow-orange` | accent, background | Warm end of the spectral light; #ff3b00 at 20% over white. |
| Refracted blue | `#cce8ff` | `--color-glow-blue` | accent, background | Cool end of spectral light; #008eff at 20% over white. |
| Refracted pink | `#fdcceb` | `--color-glow-pink` | accent, background | Pink portion of spectral light; #f6009d at 20% over white. |
| Refracted violet | `#ead8f4` | `--color-glow-violet` | accent, background | Violet portion of spectral light; #973ec6 at 20% over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black action | `#0d0d0d` | `--color-action` | action, background | Primary action fill; black at 95% over white. |
| Primary ink | `#202020` | `--color-ink` | text | Main headings and strong labels; visible result of black at 87.5% over white. |
| Secondary ink | `#646464` | `--color-secondary` | text, link | Body copy and secondary links; black at 60.8% over white. |
| Tertiary ink | `#8d8d8d` | `--color-tertiary` | text, link | Metadata, footer links and subdued halves of heading pairs; black at 44.7% over white. |
| Hairline and pale fill | `#f0f0f0` | `--color-edge` | border, surface | Black at 6% over white for panel edges, rules and small pale backing shapes; also the solid rule color in information rows. |
| Pearl glass | `#f1f1f1` | `--color-glass` | surface | Visible glass-shell backing from #ebebeb at 70% over white, softened by backdrop blur. |
| Closing shell | `#f6f6f6` | `--color-shell` | background | Top of the closing area, gradually returning to white. |
| Whisper card | `#f9f9f9` | `--color-card` | surface | Visible neutral card backing, black at 2.4% over white. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page, application panels, secondary controls and reversed primary-button labels. |

## Typography

- **InterVariable** — All marketing headings, paragraphs, labels, actions and navigation. Neutral modern grotesk, with a high x-height and restrained medium-weight display cuts. OpenType features: "ss03". If unavailable, use **Inter**. Use variable weights 400, 450 and 500 with the specified tracking. Font stack: "InterVariable", "Inter", Arial, sans-serif.
- **HeldaneText** — Customer testimony inside the atmospheric quotation panel. Literary text serif with bracketed serifs and a warmer cadence than the surrounding interface type. If unavailable, use **Source Serif 4**. Use weight 400 and tune wrapping to the 560px quote measure. Font stack: "HeldaneText", "Source Serif 4", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| opening-display | InterVariable | 500 | 56px | 1 | -0.02em | Default marketing opening promise, usually two lines. |
| display | InterVariable | 500 | 56px | 1 | -0.01em | Centered closing promise and audience-specific product opening. |
| heading | InterVariable | 500 | 28px | 36px | -0.01em | Section leads and dark-to-muted heading pairs. |
| quotation | HeldaneText | 400 | 28px | 36px | -0.01em, features "ss03" | Centered multi-line customer quotation. |
| body | InterVariable | 400 | 15px | 24px | normal | Supporting paragraphs. |
| item-title | InterVariable | 500 | 15px | 24px | normal | Capability titles, row questions and small proof labels. |
| text-link | InterVariable | 450 | 15px | 24px | normal | Learn-more and detail links with a small trailing chevron. |
| label | InterVariable | 500 | 13px | 20px | normal | Buttons, footer group titles and restrained sentence-case eyebrows. |
| small | InterVariable | 400 | 13px | 20px | normal | Footer links, capability lists and compact metadata. |
| navigation | InterVariable | 450 | 13px | 16px | normal | Main navigation links. |
| release-date | InterVariable | 500 | 12px | 1 | normal, uppercase | Compact date above a release title. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| recruiting pages | culture-display | InterVariable | 500 | 36px | 44px | -0.01em | Centered mission statement below an abstract identity graphic. |
| trust and policy pages | trust-introduction | InterVariable | 500 | 18px | 24px | normal | Narrow introductory statement with an ink lead-in and muted continuation. |

**Notes:**

- Display weight is 500, not bold. The default opening tightens tracking to -0.02em; other large promises and section heads use -0.01em.
- Marketing paragraphs remain 15px even beside 56px headlines. Sentence-case 13px labels are more characteristic than all-caps eyebrows.
- The same 28px heading recipe can form a compact sentence with a dark first statement, muted second statement and one selected blue verb. Color establishes emphasis without changing weight.
- Keep serif type confined to customer testimony; the pixel-stepped closing artwork is a graphic, not another body typeface.

## Layout

**Density:** Airy at section scale and compact at control scale: broad white intervals surround small, readable product-oriented text.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-label and control-internal gaps. |
| 8px | Footer title-to-links and compact list gaps. |
| 12px | Paired action gap and compact support spacing. |
| 16px | Section heading-to-body gap and image-to-card-copy gap. |
| 24px | Release-card top padding and opening support-to-actions gap. |
| 40px | Default two- and three-column grid gutter. |
| 48px | Closing headline-to-actions and quote-to-attribution gap. |
| 64px | Inset of the compact proof band. |
| 96px | Vertical padding around capability chapters. |
| 120px | Quote inset and release-section vertical padding. |
| 144px | Opening top inset below navigation and overview-section vertical padding. |
| 160px | Closing-call vertical padding; separation of trust-page chapters. |
| 200px | Visual interval between closing actions and the assistant-link strip. |

### Containers and grids

- **container**: max width 1244px · side padding 22px. Centered outer wrapper yielding 1200px of usable content at desktop; at 1440px the inner content begins 120px from either edge.
- **capability split**: 2 columns · gap 40px. Two equal tracks; left text has a 480px maximum measure, while a larger product stage occupies and overflows the right track.
- **three-column overview**: 3 columns · gap 40px. Three 373px columns across the inner container for small demonstrations, release items or people.
- **footer columns**: max width 1028px · 4 columns. Four left-aligned link groups with measures up to 240px, leaving room for a small identity symbol at the far right.
- **trust grid** (only for trust and policy pages): 3 columns · gap 16px. Dense controls arranged as 389px-wide panels, two rows high; accreditation and supplier groups use four columns with the same 16px gutter.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 8px |
| navigation and compact controls | 6px |
| application outer frame | 12px |
| application inner panel | 10px |
| proof and quote panels | 16px |
| avatars | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| small raised control | `0px 0px 0px 0.5px rgba(0,0,0,0.06), 0px 1px 1px -1px rgba(0,0,0,0.1), 0px 1px 2px 0px rgba(0,0,0,0.05)` | White secondary buttons and utility icon buttons; an edge and a tiny lift, not a floating card. |
| hero stage | `0px 0px 0px 0.5px rgba(0,0,0,0.07), 0px 149px 199px 0px rgba(0,0,0,0.07), 0px 62.2px 83.1px 0px rgba(0,0,0,0.05), 0px 33.3px 44.4px 0px rgba(0,0,0,0.04), 0px 18.7px 24.9px 0px rgba(0,0,0,0.04), 0px 9.9px 13.2px 0px rgba(0,0,0,0.03), 0px 4.1px 5.5px 0px rgba(0,0,0,0.02)` | The large opening application shell, combined with spectral backlighting. |

### Surfaces

#### Canvas · level 0

**Use:** Default background throughout the marketing story.

**CSS:** `background: #ffffff; color: #202020`

**Observed:** Even product chapters remain visually white around the object; the faint panel backing belongs to the interface, not an entire gray section.

**Transfer:** Let whitespace, type and clipped imagery define chapters rather than alternating colored bands.

#### Whisper panel · level 1

**Use:** Contained quote and compact proof bands.

**CSS:** `background: rgba(0, 0, 0, 0.024); border-radius: 16px; outline: 1px solid rgba(0, 0, 0, 0.05); outline-offset: -1px; overflow: hidden`

**Observed:** A barely gray sheet set within the content width, with little contrast from the white page.

**Transfer:** Use for selected moments of proof rather than wrapping every paragraph in a card.

#### Product frame · level 1

**Use:** Large capability demonstrations.

**CSS:** `background: rgba(0, 0, 0, 0.024); border: 0.5px solid rgba(0, 0, 0, 0.06); border-radius: 12px`

**Observed:** A 1200×640px backing contains white inner panels with 10px corners and equally delicate edges. White fade layers soften the bottom and lateral edges.

**Transfer:** Construct a useful product workflow and preserve the light framing even when the application's native UI is visually denser.

#### Opening glass · level 2

**Use:** Main opening application stage.

**CSS:** `background: rgba(235, 235, 235, 0.7); border-radius: 12px; backdrop-filter: blur(20px); overflow: hidden; box-shadow: 0px 0px 0px 0.5px rgba(0,0,0,0.07), 0px 149px 199px 0px rgba(0,0,0,0.07), 0px 62.2px 83.1px 0px rgba(0,0,0,0.05), 0px 33.3px 44.4px 0px rgba(0,0,0,0.04), 0px 18.7px 24.9px 0px rgba(0,0,0,0.04), 0px 9.9px 13.2px 0px rgba(0,0,0,0.03), 0px 4.1px 5.5px 0px rgba(0,0,0,0.02)`

**Observed:** A pearl-gray rail and pale application panels receive a warm glow at left and a cooler glow toward the right.

**Transfer:** Keep the shell translucent and put color behind it, not on the application window itself.

#### Spectral light · level 0

**Use:** Atmosphere behind the opening product and along quote and closing boundaries.

**CSS:** `background: linear-gradient(90deg, rgba(255, 59, 0, 0.2) 0%, rgba(246, 0, 157, 0.2) 38%, rgba(151, 62, 198, 0.2) 71%, rgba(0, 142, 255, 0.2) 100%); border-radius: 300px; filter: blur(50px); pointer-events: none`

**Observed:** The opening light is a 1496×856px rounded field. The closing variant is a 1200×200px pill blurred 100px and centered over the upper boundary.

**Transfer:** Keep the chromatic light broad and diffuse, with white above and below it; match the soft glow rather than emphasizing discrete color stops.

#### Closing shell · level 0

**Use:** Continuous conversion and footer area.

**CSS:** `background: linear-gradient(180deg, #f6f6f6 0%, #ffffff 100%); overflow: hidden`

**Observed:** The full-width shell returns gradually to white beneath the spectral boundary.

**Transfer:** Treat call, utility strip, footer links and final word sculpture as one connected ending.

## Components

### Fixed navigation

**Use:** Persistent site orientation.

**CSS:** `height: 64px; position: fixed; top: 0px; width: 100%; z-index: 50; background: #ffffff; border-bottom: 1px solid rgba(0, 0, 0, 0.06)`

**Text style:** `navigation` — InterVariable 450 · 13px/16px

**Observed:** Identity sits left, four compact navigation items sit centrally, and login plus a small white registration control sit right. Tiny keycap hints accompany account actions.

**Transfer:** Keep the three-part balance; use the new product's identity and concise menu nouns.

### Navigation link

**Use:** Main header menu items.

**CSS:** `height: 28px; padding: 0px 8px; border-radius: 6px; color: #646464; display: flex; align-items: center`

**Text style:** `navigation` — InterVariable 450 · 13px/16px

**Observed:** Small text-only triggers sit in a close horizontal group rather than large navigation tabs.

### Primary button

**Use:** Main signup or conversion action.

**CSS:** `height: 32px; padding: 0px 12px; background: rgba(0, 0, 0, 0.95); color: #ffffff; border-radius: 8px; display: flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `label` — InterVariable 500 · 13px/20px

**Observed:** A compact dark rectangle paired with Secondary button. Recruiting uses a 40px-high version with 14px horizontal padding.

**Transfer:** Choose a short literal action rather than expanding the control to make it seem more important.

### Secondary button

**Use:** Sales or assisted conversion beside the primary action.

**CSS:** `height: 32px; padding: 0px 12px; background: #ffffff; color: #202020; border-radius: 8px; box-shadow: 0px 0px 0px 0.5px rgba(0,0,0,0.06), 0px 1px 1px -1px rgba(0,0,0,0.1), 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `label` — InterVariable 500 · 13px/20px

**Observed:** A white raised control, not a heavy outlined or tinted button; typically sits 12px after the primary.

### Detail link

**Use:** Secondary paths below proof and release content.

**CSS:** `color: #646464; display: flex; align-items: center; gap: 8px; text-decoration: none`

**Text style:** `text-link` — InterVariable 450 · 15px/24px

**Observed:** Text is followed by a small right-pointing chevron with no enclosing button surface.

### Release item

**Use:** Compact editorial or product-update card.

**CSS:** `border-top: 1px solid rgba(0, 0, 0, 0.06); padding: 24px 24px 0px 0px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `item-title` — InterVariable 500 · 15px/24px

**Observed:** Uppercase date in release-date type, then title and one paragraph with a 4px gap. Three equal columns have no card fill or rounded enclosure.

**Transfer:** Use dated, specific progress as proof of momentum.

### Proof band

**Use:** Compact reassurance within the main marketing story.

**CSS:** `background: rgba(0, 0, 0, 0.024); border-radius: 16px; padding: 64px; display: flex; gap: 40px; outline: 1px solid rgba(0, 0, 0, 0.05); outline-offset: -1px`

**Text style:** `heading` — InterVariable 500 · 28px/36px · tracking -0.01em

**Observed:** A dark/muted two-line statement and detail link occupy the left; two small icon-led proof groups sit to the right, separated with delicate vertical rules.

**Transfer:** Use two genuinely substantiated credentials, reliability facts or service commitments.

### Utility icon button

**Use:** Assistant-query links in the closing utility strip.

**CSS:** `width: 32px; height: 32px; background: #ffffff; border-radius: 8px; display: flex; align-items: center; justify-content: center; box-shadow: 0px 0px 0px 0.5px rgba(0,0,0,0.06), 0px 1px 1px -1px rgba(0,0,0,0.1), 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Observed:** Five monochrome assistant marks in separate white controls follow a muted introductory phrase, with 8px between controls.

**Transfer:** Use supported assistant-query destinations and accessible names describing each destination.

### Footer link

**Use:** Quiet navigation under footer category titles.

**CSS:** `min-height: 28px; display: flex; align-items: center; color: #8d8d8d; text-decoration: none`

**Text style:** `small` — InterVariable 400 · 13px/20px

**Observed:** A simple unbulleted vertical list. Category titles use label type in primary ink.

### Control card

**Only for:** trust and policy pages

**Use:** Dense evidence of operational safeguards.

**CSS:** `background: rgba(0, 0, 0, 0.024); border: 1px solid rgba(0, 0, 0, 0.06); border-radius: 16px; padding: 16px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `item-title` — InterVariable 500 · 15px/24px

**Observed:** Title above three compact checkmarked lines and a small view-all link; a very pale green wash grows toward the bottom. Cards form a three-column grid with 16px gaps.

**Transfer:** Use only verified safeguards and let the final tile act as a route to a complete list.

### Question row

**Only for:** trust and policy pages

**Use:** Scannable objection handling.

**CSS:** `min-height: 56px; padding: 16px; border-bottom: 1px solid #f0f0f0; display: grid`

**Text style:** `item-title` — InterVariable 500 · 15px/24px

**Observed:** Muted category on the left, question in the main track and a small plus at the far right. Rows span the content width without rounded card enclosures.

**Transfer:** Keep category, question and expansion affordance separate; retain full-row activation.

## Imagery and graphics

### Large application scenes

**Use:** Main opening and capability chapters.

**Observed:** Light desktop application interfaces with a narrow icon rail, readable issue details, activity streams, charts and code. The opening object is 1440×800px and runs beyond the right viewport edge; later scenes occupy about half the page beside a narrow text column. White gradient masks dissolve the lower and side edges so the objects feel embedded in paper.

**Transfer:** Show a coherent task from the new product at believable scale. If a full interface is unavailable, build a minimum representative panel with a slim navigation rail, one clear record and a compact activity or result pane; keep text legible and the surrounding chrome pale.

**Build:** Place white panels in Product frame or Opening glass. Add an absolutely positioned 160px side overlay and a bottom overlay up to 480px high, each fading from transparent white to opaque white. Keep useful content concentrated near the unfaded upper-left of the scene.

### Prismatic atmosphere

**Use:** Signature light around major objects, testimony and closing transition.

**Observed:** A low-saturation ribbon moves from peach and pink at left through lavender to cool blue at right. It illuminates the space around the hero window and pools below the quotation; it is never a hard-edged rainbow banner.

**Transfer:** Keep this spectral light in every new landing-page composition, including when the object is a simplified workflow instead of finished product media.

**Build:** Use Spectral light behind the object: orange rgba(255,59,0,0.2) at 0%, pink rgba(246,0,157,0.2) at 38%, violet rgba(151,62,198,0.2) at 71%, blue rgba(0,142,255,0.2) at 100%. Give the opening field 300px corners and 50px blur; use a 1200×200px pill with 100px blur at the closing boundary. Keep pointer events off and contain horizontal overflow.

### Pixel-stepped word sculpture

**Use:** Signature final identity artwork below footer navigation and legal text.

**Observed:** A 1200×180px SVG stretches across the content width at the very bottom. Large serif-like letter silhouettes and a dispersed square symbol are rebuilt with staircase pixel contours; their near-white gray fill and fine edge dissolve downward into the page.

**Transfer:** Render the new product name or a short identifying phrase as a pale architectural word sculpture. It must remain an oversized decorative endpoint, not an extra navigation heading.

**Build:** Create a wide SVG viewBox with a 20:3 ratio. Trace a high-contrast serif word silhouette into coarse rectilinear steps on an 8px construction grid, adding a small group of detached squares at one side. Fill with the pale edge neutral at reduced opacity, outline with black at about 6% alpha and mask from full opacity at the top to zero at the bottom. Use the whole 1200px measure and clip the lower edge.

### Quotation architecture

**Use:** Customer testimony panel.

**Observed:** A centered literary quote floats over a pale spectral pool, flanked by extremely faint oversized angular contours. A small circular portrait and two-line attribution anchor it beneath the text.

**Transfer:** Pair a real human statement with one small portrait; keep the background architectural rather than adding a large headshot or decorative quotation mark.

**Build:** Use Whisper panel at 1200px width, a 560px quote measure and 120px inset. Place two mirrored SVG outlines wider than 700px outside the left and right edges; draw bent, rounded-corner polygonal paths with black at roughly 3% alpha. Put the spectral ribbon low behind the text.

### Drafting-grid product tableau

**Only for:** audience-specific product pages

**Use:** Alternative opening illustration beside the promise.

**Observed:** A large right-hand drafting grid carries fine dashed guides, a circular construction outline, tiny annotation text, a small selection box and a stack of light session cards. Product line charts supply limited color; a spectral wash lies along the base.

**Transfer:** Stage a representative result card within a faint construction grid, using the audience's own work as the subject rather than copying the exact diagram.

**Build:** Use an SVG grid of thin black lines at 6% alpha over a white half-width stage. Add a 320px dashed circle, a small handled selection rectangle, and three overlapping white 480px-wide cards with 12px corners and fine borders. Place pale utility annotations outside the main card, then fade the scene toward its outer edges.

### Translucent trust emblem

**Only for:** trust and policy pages

**Use:** Centered opening atmosphere.

**Observed:** Three nested shield silhouettes form a 350×452px translucent object behind a 56px headline. Fine gray outlines, subtly darker right facets and a faint spectral halo make it resemble stacked glass sheets rather than a solid badge.

**Transfer:** Use an appropriate simple protective or assurance symbol in the same translucent material.

**Build:** Draw three nested rounded shield paths in SVG, with white-to-pale-gray translucent fills and black outlines at about 6% alpha. Offset the inner facets slightly to suggest thickness. Add a 488×56px horizontal spectral field blurred 40px behind the headline.

### Culture diagrams and portraits

**Only for:** recruiting pages

**Use:** Mission opening, principles and people.

**Observed:** The opening shows scattered pearl-gray square planes converging toward one blue-lit square. Three principle illustrations use a dot lattice with one dark dot, an arc joining two endpoints, and an array of crosses with one check. People appear as small grayscale circular portraits in ruled rows, not large lifestyle photography.

**Transfer:** Turn principles into minimal geometric exceptions within a repeated system, and pair compact portraits with roles and social controls.

**Build:** For the opening, arrange low-contrast squares of varied sizes in a diagonal cluster with faint horizontal trails, lighting one square with a soft blue shadow. For principle art, use 373×240px Whisper panels with 12px corners; draw a 240px-wide dot grid, a single 240px arc, or a cross grid using thin pale-gray SVG marks and just one dark point or check.

### Icons

**Observed:** Mostly compact filled monochrome SVGs at 14px, 16px and 20px. Chevrons and expansion symbols are finer and quieter; document motifs use 1px outlines. Avatars are circular and proof symbols sit within small rounded white tiles.

**Transfer:** Choose a consistent small filled icon family with simple silhouettes. Use 16px for labels and 20px in 32px utility buttons; keep marketing icons gray rather than adding colored circles to every feature.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** Below Fixed navigation, a white 1200px-wide content area has 144px of top breathing room. A two-line 56px opening-display promise occupies the left half, about 444px wide; a 512px support block sits on the right with two lines of 15px body copy aligned right and paired Primary button and Secondary button below it. The text row ends 48px above the main product. Back-to-front layers are white canvas, Prismatic atmosphere, Opening glass and a legible desktop application. The 1440×800px window starts about 368px down the document, aligned to the content's left edge but cut by the right viewport edge. Within the first 900px the navigation, complete headline, support, both actions and the upper majority of the main object are visible; the object continues below the fold. The later logo strip is below it.

**Transfer:** Keep this asymmetric text row and oversized task-oriented object as the default marketing opening. Without finished artwork, construct the representative panel described in Large application scenes. Audience-specific pages instead use a left eyebrow, stacked 56px promise and actions beside Drafting-grid product tableau; trust pages center a promise over Translucent trust emblem, while recruiting centers Culture diagrams and portraits above a 36px mission.

**Avoid:** Do not replace the composition with a centered giant slogan above a small browser thumbnail, or allow the glow to cover the entire first screen as an opaque gradient.

**Text style:** `opening-display` — InterVariable 500 · 56px/1 · tracking -0.02em

### Trust strip

**Observed:** A shallow white band below the opening uses a small outlined 166×32px label followed by monochrome customer and funder marks. It is separated with a delicate bottom rule and 48px vertical inset.

**Transfer:** Use a single line of relevant, authorized proof marks with a muted label; keep their optical heights similar rather than using identical bounding boxes.

### Capability overview

**Observed:** A compact 28px statement spans roughly 576px, mixing muted clauses, primary ink and one blue selected verb. After 64px, a three-column overview places a small faded product fragment above each 15px item title and paragraph. Columns have 40px gutters and 16px image-to-copy gaps.

**Transfer:** Explain the new product's mechanism in a short chain of actions, then make each action visible in a small demonstration.

**Text style:** `heading` — InterVariable 500 · 28px/36px · tracking -0.01em

### Human testimony

**Observed:** Quotation architecture sits within Whisper panel, 1200×492px, with a 560px centered quote and 48px before the portrait attribution. A spectral pool occupies the lower half without changing text contrast.

**Transfer:** Use a short authenticated statement about the user's regained ability or time; maintain the literary contrast to the surrounding application imagery.

**Text style:** `quotation` — HeldaneText 400 · 28px/36px · tracking -0.01em

### Capability chapter

**Observed:** A two-column split with 40px gutter and 96px vertical section padding. The left column contains a 28px headline and support 16px below, with a small ruled capability list near its lower edge; the right contains an oversized Product frame, white panels and fading edges. Text occupies at most 480px of its track. Chapters are spacious but their controls and annotations stay small.

**Transfer:** Use one outcome per chapter; carry the same representative workflow through successive chapters rather than changing illustration language.

**Text style:** `heading` — InterVariable 500 · 28px/36px · tracking -0.01em

### Reassurance and momentum

**Observed:** Proof band offers a compact dark/muted heading and two icon-led credentials. A following white editorial area uses a 28px section title, 40px gap and three Release items with fine top rules, then Detail link.

**Transfer:** Combine a concise substantiated reassurance with recent, concrete activity. Either device can stand alone when the narrative calls for it.

**Text style:** `heading` — InterVariable 500 · 28px/36px · tracking -0.01em

### Luminous closing and footer

**Observed:** Closing shell spans the full width for about 1294px. Spectral light straddles its upper edge. Centered display type makes a two-line closing promise with actions 48px below, surrounded by 160px vertical padding. The assistant utility strip follows, then a rule and four Footer link groups with 13px medium titles. A separate lower rule precedes compact legal copy; 40px below that, Pixel-stepped word sculpture finishes at the page edge. The audience variant changes the promise but not this construction.

**Transfer:** Make the ending a spacious return to the product's core outcome, not just a list of links. Preserve the luminous boundary, compact utility strip, restrained columns and pale word sculpture with new content.

**Text style:** `display` — InterVariable 500 · 56px/1 · tracking -0.01em

### Information chapters

**Only for:** trust and policy pages

**Observed:** Sentence-case 13px muted section labels sit above thin full-width rules. Introductory copy is 18px/24px in a 560px measure; accreditations are left-ruled compact columns, suppliers are pale icon cards, questions are Question rows and controls are Control cards. Chapters are separated by 160px; the resource ending uses a horizontal row of document silhouettes, titles and update metadata.

**Transfer:** Turn due-diligence information into a calm directory with explicit status, direct detail links and factual questions; retain the common conversion ending.

**Text style:** `trust-introduction` — InterVariable 500 · 18px/24px

### Mission and people

**Only for:** recruiting pages

**Observed:** A centered abstract square scene precedes the 36px mission and 40px-high dark action. Below, a 28px left heading sits beside a right-hand stack of 15px paragraphs. Three principle illustrations form a 40px-gutter row; people appear in three columns of thin top-ruled rows with small circular portraits and 32px social controls. Open roles are full-width ruled rows with title, location, compensation and a right-aligned detail path.

**Transfer:** Use the geometric system to express a few authentic principles; let compact people and role details make the page useful rather than filling it with lifestyle imagery.

**Text style:** `culture-display` — InterVariable 500 · 36px/44px · tracking -0.01em

### Audience demonstration

**Only for:** audience-specific product pages

**Observed:** A 28px headline and 15px support sit beside a large application scene. Three text-only feature rows have horizontal separators and an active dark rule; expanded support belongs directly below the active label. Later, a horizontally spread card tableau precedes a left heading paired with a two-column icon-and-copy feature list.

**Transfer:** Explain the same product in the audience's vocabulary, changing which workflow is foregrounded while retaining the light staging and common typography.

**Text style:** `heading` — InterVariable 500 · 28px/36px · tracking -0.01em

## Page flow

**Storyline:** Outcome promise → tangible product or symbolic demonstration → concrete capabilities and proof → practical reassurance → luminous closing call and identity-rich footer.

### Broad product marketing landing page

1. **Promise and demonstration** — Asymmetric text row over a large glowing application stage.
2. **Social proof** — Shallow monochrome logo strip.
3. **Mechanism** — Selected-word sentence and three small workflow demonstrations.
4. **Human proof** — Serif quotation inside a luminous pale panel.
5. **Capability chapters** — Spacious text-and-application splits carry a common workflow through distinct outcomes.
6. **Reassurance and momentum** — Compact proof band and three ruled update items.
7. **Closing call** — Spectral boundary, centered promise, action pair and complete decorative footer.

**Transfer:** Use as a flexible landing-page narrative; choose the most useful proof and capability moments without treating the section count as a template.

### Trust and due-diligence resource

1. **Orientation** — Breadcrumb and report-availability strip under the fixed header.
2. **Promise** — Centered headline over a translucent emblem.
3. **Evidence** — Introductory position followed by accreditation statuses and supplier cards.
4. **Objection handling** — Categorized question rows.
5. **Detailed proof** — Checkmarked control grid and document resource strip.
6. **Closing call** — Shared luminous conversion area and full word-sculpture footer.

**Transfer:** Present verified claims as an orderly resource with visible statuses, then return to the main product outcome.

### Recruiting and culture landing page

1. **Mission** — Abstract square scene, centered smaller display and direct roles action.
2. **Context** — Left heading with right-hand mission paragraphs.
3. **Principles** — Three geometric exception-within-a-system illustrations and concise statements.
4. **People** — Ruled team rows with compact grayscale portraits and social controls.
5. **Practical conversion** — Open-role rows with location and compensation metadata.
6. **Closing call** — Shared product promise and full luminous footer.

**Transfer:** Let cultural ambition be supported by tangible people and clear opportunities; keep the visual system diagrammatic and restrained.

### Audience-specific product landing page

1. **Audience promise** — Left eyebrow, multiline outcome and action pair beside a drafting-grid card tableau.
2. **Social proof** — Monochrome proof strip.
3. **Product demonstration** — Text feature selector beside an enlarged application task.
4. **Benefits** — Spread of representative cards followed by a two-column icon-and-copy list.
5. **Closing call** — Audience-specific promise in the shared luminous footer.

**Transfer:** Keep the shared brand frame while selecting the tasks and wording most relevant to a new audience.

## Writing

Confident and plainspoken about product outcomes, with concrete verbs and technical credibility. Human testimony is warmer; recruiting copy is more ambitious and metaphorical, while trust copy is factual and status-led.

**Do not copy:** Do not reuse the Interfere name, marks, customer logos, named people, quotations, compliance claims, product facts, dates, compensation figures or other source-specific claims. Write new substantiated content and use authorized assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team in benefits and support; use we for company commitments. Name the product when describing its mechanism, rather than anthropomorphizing it in every sentence.
- **Rhythm:** Headlines are compact outcome statements, often split into two clauses or two lines. Supporting paragraphs usually contain one or two explanatory sentences. Actions are literal one- to three-word labels; punctuation is restrained.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Imperative or direct outcome with a concrete undesirable condition removed. | 5–9 words | “Ship software that never breaks”<br>“Understand user problems before they're reported.” |
| Capability heading | Start with a useful verb and describe what the reader gains, not an internal feature name. | 4–10 words | “Learn about issues before your customers do”<br>“Fix problems with confidence” |
| Supporting explanation | Name the mechanism, then describe the user's consequence or control. | 18–35 words | “[Brand] connects user behavior, sessions, releases, and engineering context into a single explanation.”<br>“[Brand] turns insight into action by suggesting fixes, linking them to your codebase, and tracking progress until resolved. You're always in control.” |
| Paired reassurance | Two parallel compact assertions; the second completes or softens the first. | 3 words per clause | “Secure by design.”<br>“Safe by default.” |
| Action | Literal verb plus object where needed, with no embellished sales phrase. | 1–3 words | “Sign up”<br>“Contact sales”<br>“View open roles” |
| Culture statement | Ambitious assertion made concrete by a short explanation of behavior. | 4–8 word heading | “Difficulty Wakes the Genius”<br>“We do not hide behind intent, process, or bad luck.” |

**Words and phrasing to use:** understand; learn; fix; confidence; real-time context; before; your users; your team; by design; by default; view details

**Avoid:** revolutionary all-in-one platform; unlock limitless potential; game-changing synergy; effortless magic; exclamation-heavy urgency

**Rules:**

- Lead with an outcome, then explain how it happens in ordinary language.
- Keep technical specificity where it answers a real reader question; translate its consequence for nontechnical audiences.
- Use factual status words such as completed or in progress only when supportable.
- Reserve grand metaphors for mission-oriented culture writing, not every product capability.
- Describe continuing user control alongside automation rather than promising a mysterious autonomous cure.

## Do's and Don'ts

### Do

- Keep the default opening at 56px/56px, weight 500, with -0.02em tracking.
- Use the 1244px wrapper with 22px inner padding to yield a 1200px desktop content measure.
- Make action pairs 32px high with 8px corners and a 12px gap.
- Stage the main product at full desktop scale and let it exceed the right content boundary.
- Keep paragraph text 15px/24px and capability headings 28px/36px.
- Use 40px gutters for editorial and capability grids, reserving 16px gutters for denser trust grids.
- Keep spectral light translucent at about 20% alpha and blurred 50–100px.
- Finish with a pale, content-width stepped word sculpture beneath the ruled footer.

### Don't

- Do not turn every heading into 700-weight black type; the measured headline weight is 500.
- Do not promote the selected-word blue into the default CTA fill; primary actions are near-black.
- Do not use pill-shaped conversion buttons in place of the 8px rounded rectangles.
- Do not box release items in tinted rounded cards; they use a single top hairline and 24px top inset.
- Do not stretch body paragraphs across the whole 1200px content area; feature text measures are about 480px.
- Do not add large lifestyle photography to ordinary product chapters; the dominant objects are light application scenes.
- Do not make every surface float with a long shadow; broad depth belongs to the main opening stage, while small controls have only an edge and tiny lift.
- Do not apply serif type to navigation, feature headings or body copy; it is reserved for testimony.

## Motion and responsive

### Motion

**Observed:**

- Settled headings and application scenes use clean, unblurred text. Some text elements expose transform and blur properties, and selected explanatory words have color-transition classes.
- Matched action and surface state rules did not provide a complete transition system; no numerical timing is established here for marketing entrances.

**Transfer:**

- If revealing the selected-word sentence or quote progressively, end with fully readable copy and preserve the static hierarchy and spectral backing.

**Unknown:**

- Entrance timing, scroll choreography and complete hover, focus and active appearances are not established.

### Responsive

**Observed:**

- A 600px width breakpoint is declared. Desktop content uses 1244px outer wrappers with 22px side padding.
- Layout classes distinguish stacked and two-column capability arrangements, single-column and three-column overview grids, and horizontally scrollable trust cards and release items.

**Transfer:**

- On narrow layouts, stack promise, support and actions before the product stage; retain the product object's deliberately partial framing rather than shrinking all interface text to fit.
- Collapse the chapter text above its demonstration, and keep the luminous closing boundary plus word sculpture scaled to the available content width.
- Let dense card collections scroll horizontally when a full grid would make their text illegible.

**Unknown:**

- Exact mobile viewport compositions, menu behavior, type sizes and breakpoint-to-layout mapping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
