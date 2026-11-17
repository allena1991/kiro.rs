# Superlist — room for real life

## Overview

An approachable software style that makes capable tools feel like a little relief rather than another system to manage. Warm ivory, near-black plum and tomato-red actions surround tightly drawn grotesk headlines and relaxed sans-serif paragraphs. Sunlit domestic product photography and floating interface windows give the sparse default presentation a lived-in feeling; darker feature presentations add violet, electric pink and theatrical layered screens.

### Essentials

- Relief is the headline, not speed or dominance: compact two-line Haffer XH Bold promises at 68px/1.02 with -3px tracking, supported by 18px/1.65 Inter.
- A small promise sits above a very real product: a centered 700px headline measure, 570px support measure and red action pair lead into a 1120px-wide interface window that continues below the first fold.
- Actions look like polished red lozenges: 51px height, 100px radius, a vertical warm-red gradient and a tiny white inset highlight, paired with unboxed dark secondary links.
- The default page is overwhelmingly warm ivory, not a rainbow of panels: #fffdf9 canvas, #181825 headings, #59575c copy, occasional #f0eeea or #faeee7 panels, then a full-width #181824 closing world. Bright color occupies actions, a small violet hand-mark and footer category labels.
- The product belongs in everyday surroundings: 520px square, 20px-radius device scenes show warm timber, plants, ceramics and daylight beside equally sized text columns. Every new landing page needs a tangible product scene; use a photographed work surface with a composited interface if bespoke media is unavailable.
- A human hand interrupts the exact typography: a short violet underline under one meaningful headline word, rather than gradient-filled text or decorative shapes everywhere.
- The final invitation is bigger than the opening: an 88px/1.02 two-line white closing statement, short reassurance and one red action on plum-black, followed by colorful footer headings and a compact current-update card.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hand-mark violet | `#8f89fa` | `--color-violet` | accent, border, text, surface | Small hand-drawn underline on ivory; dark feature highlights, bright feature tiles and pricing artwork use a closely related wide-gamut violet. |
| Electric pink | `#f739f7` | `--color-pink` | accent, text, surface | Footer category heading; full tiles and headline emphasis only in dark feature variants. |
| Lemon yellow | `#fbe74e` | `--color-yellow` | text | One footer category heading. |
| Link blue | `#2590f1` | `--color-blue` | text | One footer category heading. |
| Fresh green | `#22c55e` | `--color-green` | text | Footer update-category heading. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Headlines on dark, action labels and active tabs. |
| Warm ivory | `#fffdf9` | `--color-canvas` | background | Default marketing canvas. |
| Peach paper | `#faeee7` | `--color-peach` | surface | Audience-switcher content panel. |
| Tab stone | `#f0eeeb` | `--color-tab-track` | surface | Segmented-control track. |
| Warm stone | `#f0eeea` | `--color-stone` | surface | Broad inset demonstration band. |
| Soft white | `#eeeeee` | `--color-soft-white` | text | Neutral footer headings and selected dark headline spans. |
| Pale lavender gray | `#d6d4df` | `--color-closing-body` | text | Reassurance copy in the dark closing band. |
| Muted lavender gray | `#8e8da0` | `--color-muted` | text | Footer links and attribution. |
| Warm graphite | `#59575c` | `--color-body` | text | Body copy on ivory. |
| Raised violet-black | `#26253b` | `--color-raised-night` | surface | Footer update card; testimonial and integration panels on dark feature pages. |
| Plum ink | `#181825` | `--color-ink` | text | Default headings and strong links. |
| Night plum | `#181824` | `--color-night` | background, text | Closing band and footer; also navigation text on ivory. Full-page canvas for dark feature and pricing variants. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark feature and pricing pages | Feature gray | `#8b8aa0` | `--color-dark-body` | text | Support text on dark feature and pricing pages. |
| dark feature pages | Signal red | `#ff3a27` | `--color-red` | accent, surface | Hard offset edges and bright tiles, distinct from the polished action gradient. |
| dark feature pages | Tile blue | `#2486e0` | `--color-tile-blue` | surface | Saturated feature tile backing. |
| pricing pages | Plan interior | `#1d1f31` | `--color-plan` | surface | Paid-plan interiors. |
| pricing pages | Plan backing | `#1d2031` | `--color-plan-edge` | surface, border | Thin outer wrapper around paid-plan cards. |

## Typography

- **Haffer XH** — Headlines, navigation, actions and footer headings. Compact, rounded grotesk with a substantial x-height and friendly, tightly fitting bold forms. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11" on the principal light-theme editorial text.. If unavailable, use **Inter Tight**. Use 600 and 700; preserve compact measures and tight headline spacing. Font stack: "Haffer XH", "Inter Tight", Arial, sans-serif.
- **Inter** — Body copy, eyebrows, utility links, FAQs and tab labels. Clear, neutral sans-serif whose relaxed paragraph leading contrasts with the dense headlines. Font stack: "Inter", Arial, sans-serif.
- **CUSTOM;Blender** (only for dark review walls) — Review body copy. Compact utilitarian sans-serif treatment in small testimonial cards. If unavailable, use **Barlow**. Use 400 with the compact 1.3 leading. Font stack: "CUSTOM;Blender", "Barlow", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | Haffer XH | 700 | 88px | 1.02 | -0.0341em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Monumental two-line closing invitation. |
| display | Haffer XH | 700 | 68px | 1.02 | -0.0441em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Centered opening promise, normally split into two balanced lines. |
| heading-wide | Haffer XH | 600 | 56px | 1.08 | -0.0179em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Broad audience or context-switching section title. |
| heading | Haffer XH | 600 | 48px | 1.08 | -0.0208em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Core feature chapters and centered introductory statements. |
| card-heading | Haffer XH | 600 | 32px | 1.15 | normal | Heading inside a large audience panel. |
| quote | Haffer XH | 400 | 32px | 1.4 | normal | Single centered testimonial, separate from capability chapters. |
| update-heading | Haffer XH | 600 | 24px | 1.2 | -0.02em | Short footer update title. |
| body | Inter | 400 | 18px | 1.65 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Default paragraphs and opening support; pale lavender on the dark closing band. |
| action | Haffer XH | 600 | 18px | 1.2 | -0.01em | Primary action labels. |
| question | Inter | 600 | 18px | 1.4 | normal | Accordion question label. |
| navigation | Haffer XH | 600 | 16px | 1.2 | normal | Top navigation. |
| footer-heading | Haffer XH | 600 | 16px | 1.5 | -0.015em | Colored footer category headings; also plan feature lists. |
| secondary-action | Inter | 600 | 15px | 1.2 | normal | Unboxed opening secondary action. |
| footer-link | Inter | 400 | 14px | 1.3 | -0.005em | Footer link lists and quiet metadata. |
| eyebrow | Inter | 600 | 11px | 1.5 | 0.136em, uppercase, features "blwf", "cv03", "cv04", "cv09", "cv11" | Tiny chapter labels, numbered labels and context lines. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| dark feature pages | feature-display | Haffer XH | 600 | 52px | 1 | -0.02em | Centered dark feature opening. |
| dark feature and pricing pages | review-closing | Haffer XH | 600 | 48px | 1.2 | -0.02em | Centered conversion statement above a faded review wall. |
| pricing pages | price | Haffer XH | 600 | 48px | 1.1 | -0.02em | Dollar sign and amount form one prominent price; small per-person and billing metadata sits beside and below. |
| dark feature pages | feature-heading | Haffer XH | 600 | 44px | 1 | -0.02em | Dark split-section headings with an accent-colored ending. Scenario-led voice sections use Bold at the same size. |
| pricing pages | plan-heading | Haffer XH | 600 | 30px | 1.2 | -0.02em | Plan names. |
| dark feature pages | feature-tile-heading | Haffer XH | 600 | 29px | 1.1 | -0.02em | White headings on saturated capability tiles. |
| dark feature pages | feature-support | Inter | 500 | 18px | 1.4 | -0.02em | Centered dark opening description. |
| dark feature pages | feature-body | Inter | 400 | 16px | 1.5 | -0.012em | Narrow supporting copy beside dark demonstrations. |
| dark review walls | review-body | CUSTOM;Blender | 400 | 16px | 1.3 | normal | Compact review paragraphs. |

**Notes:**

- Keep the large letterforms dense and the surrounding space open: 68px and 88px bold titles retain -3px tracking while the 48px chapter title uses -1px.
- The 11px uppercase eyebrow is deliberately much smaller than the 48px heading below it. Its 1.5px tracking is not used on body text.
- Use Haffer Regular for the standalone testimonial, not the semibold chapter face. Buttons and small Haffer labels retain the visual weight of the Semibold cut.
- Body paragraphs are narrow and generously led. The dark feature variant is more compact, using 16px/1.5 rather than replacing the core 18px/1.65 recipe.

## Layout

**Density:** Airy in editorial composition, compact inside controls and interface imagery. Long pauses between chapters make the product feel unhurried.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight dark heading-to-copy and update-card internal gaps. |
| 20px | Footer list and testimonial-card internal rhythm. |
| 24px | Default eyebrow, heading, paragraph and action-group spacing. |
| 40px | Side padding of core sections and large cards. |
| 80px | Core section top and bottom padding and split-column gap. |
| 96px | Centered introduction-band vertical padding. |
| 104px | Dark closing-band top and bottom padding. |
| 120px | Dark feature split-column separation. |

### Containers and grids

- **core-container**: max width 1200px · side padding 40px. Centered outer section width; 1120px usable width for imagery and paired chapters.
- **split-chapter**: 2 columns · gap 80px. Equal 520px media and text columns, vertically centered, alternating media side.
- **opening-copy**: max width 700px. Centered headline measure; supporting text is narrowed to 570px.
- **footer-container**: max width 1400px · side padding 50px. Wide dark footer with a 1300px inner row of link groups and update card.
- **dark-feature-container** (only for dark feature pages): max width 1300px · side padding 20px. Larger product composites and asymmetrical media-led chapters.
- **plan-grid** (only for pricing pages): 3 columns · gap 16px. Three similarly sized cards across an 1180px row; free tier is less filled than paid tiers.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 100px |
|  | media-and-panels | 20px |
|  | footer-update | 10px |
| voice feature demonstrations | dark-feature-media | 30px |
| dark feature openings | hero-glass-frame | 38px |
| pricing pages | plan-interior | 30px |
| pricing pages | plan-wrapper | 31px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | polished-action | `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px, rgba(255, 255, 255, 0.45) 0px 0.5px 0px 0px inset` | Small material cue on primary red buttons. |
| dark review walls | review-card | `rgba(0, 0, 0, 0.08) 0px 10px 15px 0px` | Subtle separation in dark review walls. |
| dark feature demonstrations | signal-offset | `-8px 8px 0px 0px #ff3a27` | Solid red edge under feature imagery; violet switches to positive horizontal offset, pink uses negative offset. |

### Surfaces

#### Ivory canvas · level 0

**Use:** Default landing-page field.

**CSS:** `background: #fffdf9; color: #181825`

**Observed:** Continuous warm field rather than alternating boxed rows.

**Transfer:** Let the page breathe around a few substantial scenes.

#### Stone demonstration band · level 0

**Use:** Wide inset demonstration chapter.

**CSS:** `background: #f0eeea; padding: 80px 40px`

**Observed:** Square outer band contains a rounded, wide lifestyle product scene.

**Transfer:** Use one broad change in material to distinguish a major collaborative or multi-step outcome.

#### Peach panel · level 1

**Use:** Audience-specific value panel.

**CSS:** `background: #faeee7; border-radius: 20px; padding: 40px`

**Observed:** Soft warm backing supports dark copy and a floating light interface.

**Transfer:** Use a low-saturation backing rather than a saturated promotional card.

#### Night canvas · level 0

**Use:** Closing world and footer; default field for the dark feature variant.

**CSS:** `background: #181824; color: #ffffff`

**Observed:** Nearly black with a slight violet cast, not pure black.

**Transfer:** Use the dark change as an emotional final pause on an otherwise light landing page.

#### Raised night panel · level 1

**Use:** Footer update and feature-proof panels.

**CSS:** `background: #26253b; border-radius: 10px`

**Observed:** Update card uses 10px corners; larger feature quote and integration panels use 30px corners.

**Transfer:** Keep the raised layer close to the canvas hue.

#### Glass product frame · level 1

**Only for:** dark feature openings

**Use:** Main product-window surround.

**CSS:** `border: 16px solid rgba(255,255,255,0.09); border-radius: 38px; box-shadow: rgba(255, 255, 255, 0.25) 0px -1px 1px 0px`

**Observed:** A thick translucent bevel encloses a large dark interface, with a smaller tilted device or call window in front.

**Transfer:** Frame the primary product view, not each small illustration.

#### Plan panel · level 1

**Only for:** pricing pages

**Use:** Paid-plan card interior.

**CSS:** `background: #1d1f31; border-radius: 30px`

**Observed:** A 2px wrapper in #1d2031 has 31px corners. Thin violet outlines visually distinguish paid tiers, with stronger violet on the highest tier.

**Transfer:** Keep the free tier close to the page field and make tier distinction primarily about the edge, not a giant colored badge.

## Components

### Primary button

**Use:** The main conversion action.

**CSS:** `background-image: linear-gradient(0deg, color(display-p3 0.772358 0.137098 0.050813) 0%, color(display-p3 0.97561 0.379986 0.256739) 100%); color: #ffffff; border-radius: 100px; padding: 14px 25px 15px; height: 51px; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px, rgba(255, 255, 255, 0.45) 0px 0.5px 0px 0px inset; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Haffer XH 600 · 18px/1.2 · tracking -0.01em

**Observed:** Text-only lozenge with small inset label wrappers. The header has a compact 40px signup variant. Main actions are red on both light and dark fields.

**Transfer:** Keep the short action label and polished material independent of the new product's imagery.

### Secondary text action

**Use:** A lower-commitment action beside the main button.

**CSS:** `color: #181825; text-decoration: none`

**Text style:** `secondary-action` — Inter 600 · 15px/1.2

**Observed:** Unboxed and aligned to the center of the adjacent primary action; the group has a 24px gap.

**States:** Declared: hover color #f84f39 and no text decoration; focus-visible and active are unspecified.

### Navigation

**Use:** Top-level wayfinding.

**CSS:** `height: 100px; max-width: 1200px; padding: 26px 50px; display: flex; align-items: center; justify-content: center; gap: 22px; backdrop-filter: blur(29px)`

**Text style:** `navigation` — Haffer XH 600 · 16px/1.2

**Observed:** Logo at left, small central links with tiny filled dropdown chevrons, sign-in and compact red signup at right. Light navigation is the default; dark feature pages have pale text and a full-width fixed header.

**Transfer:** Preserve the light touch: navigation should not compete with the opening promise.

### Audience tabs

**Use:** Switch between several reader contexts.

**CSS:** `background: #f0eeeb; border-radius: 100px; padding: 5px; display: inline-flex; gap: 4px`

**Observed:** A centered pill track contains three text tabs. Active tab is white, 47px tall, with 14px 24px padding and 16px/1.2 regular Inter; inactive labels are muted. Content below changes as one large Peach panel.

**Transfer:** Use real audience contexts rather than treating this as a decorative filter.

### Audience panel

**Use:** Connect one product to distinct everyday contexts.

**CSS:** `background: #faeee7; border-radius: 20px; padding: 40px; display: flex; align-items: center; gap: 48px`

**Text style:** `card-heading` — Haffer XH 600 · 32px/1.15

**Observed:** Eyebrow, heading, paragraph and action at left; a slightly tilted, shadowed interface at right occupies more than half the panel width.

**Transfer:** Change the scenario and interface state together.

### FAQ row

**Use:** Answer common objections without visual clutter.

**CSS:** `background: #fffdf9; padding: 12px 24px; min-height: 68px; display: flex; align-items: center; gap: 16px`

**Text style:** `question` — Inter 600 · 18px/1.4

**Observed:** Full-width question label, small plus at the far right, faint horizontal separation. Rows sit in a 1040px column rather than individual floating cards.

**Transfer:** Keep questions concrete, short and recognizable.

### Footer link column

**Use:** Dense secondary navigation on dark.

**CSS:** `display: flex; flex-direction: column; gap: 20px; color: #8e8da0`

**Text style:** `footer-link` — Inter 400 · 14px/1.3 · tracking -0.005em

**Observed:** A small colored Haffer category heading stands 30px above the list. The company group spans two link columns; other groups are narrower.

**States:** Declared: hover color #fff with no underline; focus-visible and active are unspecified.

**Transfer:** Use category color only in headings, not every link.

### Update card

**Use:** A living-product signal inside the footer.

**CSS:** `background: #26253b; border-radius: 10px; width: 325px; padding: 23px 23px 30px; display: flex; flex-direction: column; gap: 10px`

**Text style:** `update-heading` — Haffer XH 600 · 24px/1.2 · tracking -0.02em

**Observed:** Small version metadata sits above a short white release headline, followed by a small date. It is one linked card, aligned with the footer lists.

**Transfer:** Use the latest useful product change, not a second signup form.

### Review card

**Only for:** dark review walls

**Use:** Human proof beneath the closing conversion statement.

**CSS:** `background: #181824; border-radius: 20px; padding: 40px; width: 340px; display: flex; flex-direction: column; gap: 20px; box-shadow: rgba(0, 0, 0, 0.08) 0px 10px 15px 0px`

**Text style:** `review-body` — CUSTOM;Blender 400 · 16px/1.3

**Observed:** Variable-height text cards include reviewer name and platform attribution. Three staggered columns sit under fading top and bottom masks.

**Transfer:** Use genuine reviews of varied lengths; keep the main conversion message above them.

### Feature tile

**Only for:** dark feature capability grids

**Use:** A small family of vivid capability demonstrations.

**CSS:** `background: #2486e0; border-radius: 20px; padding: 40px; height: 550px; overflow: hidden`

**Text style:** `feature-tile-heading` — Haffer XH 600 · 29px/1.1 · tracking -0.02em

**Observed:** Unequal-width paired tiles use violet, blue, red and pink. White short headings sit beside a field of small floating objects or beneath stacked interface cards.

**Transfer:** Choose one easy-to-read capability and one oversized illustration per tile.

### Plan card

**Only for:** pricing pages

**Use:** Parallel comparison of plan value.

**CSS:** `background: #1d1f31; border-radius: 30px; padding: 40px 35px 32px; color: #ffffff`

**Text style:** `plan-heading` — Haffer XH 600 · 30px/1.2 · tracking -0.02em

**Observed:** Name on the left and price on the right; per-person metadata beside the amount, annual total beneath it. Paid cards use a loose hand-drawn separator and checkmark or sparkle feature lists. A shared red upgrade action appears beneath the entire row rather than repeated in every card.

**Transfer:** Keep the plan rows aligned but let the premium card have the strongest violet edge.

## Imagery and graphics

### Floating light interface

**Use:** Opening product object and audience panels.

**Observed:** A pale, almost frosted multi-column application window on ivory, with rounded edges and a soft grounded shadow. The opening view is straight-on and broad; the audience view is gently tilted. Interface content is detailed enough to be credible but stays subordinate to the large promise.

**Transfer:** Compose a real, purposeful workflow for the new product. If no interface exists, build one convincing three-part working view with readable titles and understated controls, not a stack of empty wireframes.

### Sunlit everyday product scene

**Use:** Core chapter media and the broad demonstration band.

**Observed:** Phones lie on stone or wood beside herbs, coffee, lemon, paper and scissors; larger computer scenes sit in bright rooms with plants, textiles and warm furniture. Square 520px media with 20px corners alternates beside text; the wider laptop scene occupies a 1120px-wide panel. Light is warm and directional, with real shadows and restrained saturation.

**Transfer:** Stage the new product in the reader's own life or workplace. The minimum version is a clean photograph of a relevant real surface with one carefully composited working screen, matching perspective and light.

### Hand-drawn emphasis

**Use:** A brief human gesture inside an otherwise exact typographic composition.

**Observed:** A single violet, slightly uneven stroke under one word of the dark opening headline. It is a small accent, not a full scribble cloud.

**Transfer:** Underline the emotional hinge of a new headline, keeping the gesture shorter than the line of text.

**Build:** Use an SVG path with round caps in #8f89fa beneath the chosen word. Draw one shallow, slightly rising curve with a 5px stroke; match its width to the word and leave a small gap beneath the baseline.

### Dark layered product theater

**Only for:** dark feature openings and demonstrations

**Use:** Feature-specific opening object and alternating demonstration scenes.

**Observed:** Large dark application windows sit in translucent, rounded frames. A tilted phone or video-call strip crosses the lower-right edge. Secondary demonstrations combine dark UI with luminous landscape imagery and a solid 8px red, violet or pink offset edge.

**Transfer:** Show one complete working view and one complementary input or output layer; preserve hierarchy instead of multiplying decorative windows.

**Build:** Use Glass product frame around a dark product image approximately 1200px wide. Overlay one smaller rounded window, rotated slightly, extending past the main frame. For chapter images use a 20px radius and -8px 8px 0px #ff3a27 shadow; alternate a positive 8px violet offset and negative 8px pink offset.

### Soft chromatic atmosphere

**Only for:** AI capability overview openings

**Use:** Atmospheric backing behind a centered promise and layered product object.

**Observed:** Diffuse violet and burgundy light blooms through the upper dark field, brightest behind and beneath the product. The edge returns to near-black; it is not a hard rainbow gradient.

**Transfer:** Match the soft glow; exact stops are not essential. Keep white headlines legible and preserve a dark outer margin.

**Build:** Over #181824 layer broad radial gradients in rgba(143,137,250,0.25) at the upper-right, rgba(247,57,247,0.15) through the middle and rgba(255,58,39,0.16) at the lower-left. Blur the atmospheric layer by 80px and fade its edges into the canvas behind, never over, the interface.

### Saturated miniature stages

**Only for:** dark feature capability grids

**Use:** Illustrative feature tiles.

**Observed:** Bright flat violet, blue, red and pink panels frame floating flag-like objects, layered task strips and cropped dark dialogs. Objects cast small real-looking shadows; typography remains white and large enough to balance the art.

**Transfer:** Use a small family of recognizable objects appropriate to the new feature. The minimum acceptable illustration is a well-spaced set of simple SVG symbols with subtle offset shadows, plus one carefully constructed product fragment.

**Build:** Make two unequal panels in a row with 20px corners and 40px inner padding. Place an oversized clustered SVG group to one side in the wide panel, and a centered stack of three dark rounded cards in the narrow one. Offset each rear card downward and inward so the front card remains dominant.

### Pricing word-art

**Only for:** pricing openings

**Use:** Expressive title above the plan comparison.

**Observed:** A broad violet hand-lettered uppercase title is interrupted by a loose white currency-symbol drawing. Its 686px by 190px SVG stage is much larger and more casual than ordinary section headings.

**Transfer:** Make an original hand-lettered category word with one relevant white doodle; do not replace the whole site's heading system with this lettering.

**Build:** Draw the title as thick, rounded, slightly leaning SVG strokes in violet. Overlay one thin irregular white line-symbol through its center. Keep the word legible and the artwork centered above the support paragraph.

### Icons

**Observed:** Marketing icons are small filled SVGs: 18px chevrons beside dropdown labels, 20px utility/check shapes and a restrained plus in FAQ rows. Dark integration bands use larger recognizable app marks in a single horizontal row.

**Transfer:** Choose simple filled or lightly drawn utility symbols that match the surrounding text color. Keep large logos limited to genuine integrations or proof bands.

## Section recipes

How recurring sections are built.

### First screen: Relief-first opening

**Observed:** On Ivory canvas, a 100px Navigation row precedes a centered promise stack with 56px top padding and approximately 24px spacing. A tiny uppercase eyebrow introduces a two-line display headline in a 700px measure; one word receives Hand-drawn emphasis. The paragraph is narrowed to 570px, followed by Primary button and Secondary text action on one centered row. Behind everything is the uninterrupted ivory field; in front, the Floating light interface occupies nearly the whole 1120px content width. Within the first 900px, the complete headline, paragraph and actions are visible, followed by the upper portion of the main interface. The lower interface and small creator/platform line continue below the fold.

**Transfer:** Write an equally short emotional benefit and show a convincing, large working artifact beneath it. Without custom media, make one polished interface composite rather than shrinking the product to a thumbnail. Dark feature pages open with feature-display, a short centered gray description and Dark layered product theater; capability overviews add Soft chromatic atmosphere and an immediate action. Pricing opens with Pricing word-art instead of a standard headline.

**Avoid:** Do not turn this into a left-copy/right-dashboard hero, place all product media below the first screen, or fill the ivory background with gradients.

**Text style:** `display` — Haffer XH 700 · 68px/1.02 · tracking -0.0441em

### Centered reset

**Observed:** A tiny eyebrow precedes heading and a short centered body paragraph. The 1200px outer section uses 96px vertical padding and 40px side padding; inner copy remains much narrower.

**Transfer:** Use this as a breathing space that turns the promise into a simple explanation rather than introducing a second hero.

**Text style:** `heading` — Haffer XH 600 · 48px/1.08 · tracking -0.0208em

### Numbered everyday chapter

**Observed:** Two 520px columns with an 80px gap sit inside the core container with 80px vertical padding. The Sunlit everyday product scene alternates sides; the text stack has a numbered 11px uppercase eyebrow, heading, body and occasional text link at roughly 24px intervals.

**Transfer:** Make each chapter a recognizable moment followed by one product-enabled outcome; alternate media side only when the story benefits.

**Text style:** `heading` — Haffer XH 600 · 48px/1.08 · tracking -0.0208em

### Wide lived-in demonstration

**Observed:** Stone demonstration band carries a left-aligned eyebrow, heading and paragraph above a wide, 20px-radius room-and-device scene. The image dominates the lower portion rather than becoming a tiny card beside the explanation.

**Transfer:** Give a major combined workflow a full-width scene with one concise explanation above it.

**Text style:** `heading` — Haffer XH 600 · 48px/1.08 · tracking -0.0208em

### Context switcher

**Observed:** Centered heading-wide above Audience tabs and one Audience panel. The panel has a smaller card-heading and approximately 397px text measure beside a larger floating interface.

**Transfer:** Use it when the same product genuinely serves several contexts, keeping a single visible panel instead of a wall of small persona cards.

**Text style:** `heading-wide` — Haffer XH 600 · 56px/1.08 · tracking -0.0179em

### Standalone human proof

**Observed:** A centered 32px regular-weight quote in an 850px measure, with a tiny tracked attribution below and 80px vertical padding.

**Transfer:** Select one credible, concise observation that proves an interaction benefit.

**Text style:** `quote` — Haffer XH 400 · 32px/1.4

### Plainspoken objections

**Observed:** Left-aligned eyebrow and heading above FAQ row components; the list occupies a 1040px inner column with faint horizontal separation.

**Transfer:** Answer practical questions in one calm list rather than a colored accordion grid.

**Text style:** `heading` — Haffer XH 600 · 48px/1.08 · tracking -0.0208em

### Monumental exhale

**Observed:** Night canvas spans the full page width. A two-line closing-display sits in a 780px centered measure above a 460px support paragraph and one Primary button. Padding is 104px vertically and 40px horizontally; a short final reassurance sits under the action.

**Transfer:** Close with a human outcome and a very small next step. Preserve the abrupt light-to-dark change and the unusually large closing type.

**Text style:** `closing-display` — Haffer XH 700 · 88px/1.02 · tracking -0.0341em

### Living-product footer

**Observed:** Night canvas continues without a new border or contrasting strip. A wide footer row has colored footer-heading labels, quiet Footer link column groups and one Update card. A separate, subdued comparison-link band sits lower, followed by centered copyright/imprint. Footer interior uses 80px top and 40px bottom padding; major internal bands are separated by 100px.

**Transfer:** Keep a current-product signal alongside useful navigation; if there is no release feed, use a dated useful product note in the same compact card.

**Text style:** `footer-heading` — Haffer XH 600 · 16px/1.5 · tracking -0.015em

### Dark scenario chapter

**Only for:** dark feature pages

**Observed:** A narrow text block faces a larger 673px or 734px-wide demonstration with hard offset color. Dark feature headings use 44px/1 and finish with a red, violet or pink phrase; gray body text follows closely. Rows alternate sides, using 120px column gaps and substantial vertical pauses.

**Transfer:** Translate a reader situation into a visible product result; pair each accent phrase with the adjacent image's edge color.

**Text style:** `feature-heading` — Haffer XH 600 · 44px/1 · tracking -0.02em

### Bright capability grid and proof band

**Only for:** dark feature pages

**Observed:** A heading/support pair introduces unequal paired Feature tiles with 50px gutters. A low, wide Raised night panel below combines a short compatibility statement with a horizontal integration-logo row. A separate wide quote panel uses the same material with a portrait and oversized quotation-mark decoration.

**Transfer:** Use bright tiles for visually distinct capabilities, then a subdued horizontal proof band to restore the dark page rhythm.

**Text style:** `feature-tile-heading` — Haffer XH 600 · 29px/1.1 · tracking -0.02em

### Faded review conversion

**Only for:** dark feature and pricing pages

**Observed:** A centered review-closing and red download action float above three staggered columns of Review card components. Dark-to-transparent gradients mask the top and bottom of the wall, leaving the central reviews most legible.

**Transfer:** Give social proof depth without displacing the primary invitation. Use real review lengths rather than identical cards.

**Text style:** `review-closing` — Haffer XH 600 · 48px/1.2 · tracking -0.02em

### Handmade plan comparison

**Only for:** pricing pages

**Observed:** Pricing word-art and centered support precede two outlined billing pills, then three Plan card columns separated by 16px. Names and prices share the top row; small billing metadata, loose drawn separators and check/sparkle lists complete each card. One red upgrade action and a small contact invitation sit beneath the row.

**Transfer:** Keep the category title playful while making all money and billing information sober and aligned.

**Text style:** `price` — Haffer XH 600 · 48px/1.1 · tracking -0.02em

## Page flow

**Storyline:** Human promise → visible working product → familiar situations and capabilities → human proof → practical reassurance → small next step → living-product footer.

### Broad product landing page that makes a capable tool feel approachable

1. **Promise** — Centered emotional benefit above a large light interface.
2. **Reframing** — Short centered explanation of a small everyday change.
3. **Capability chapters** — Numbered alternating lifestyle scenes, then a wider combined-workflow scene.
4. **Audience relevance** — Context tabs and a warm panel with a floating interface.
5. **Human proof** — One centered quote followed by cross-device reassurance.
6. **Objection handling** — Plain FAQ rows.
7. **Closing call** — Monumental white statement on a dark band, continuing into the colored-category footer.

**Transfer:** Replace the scenarios with the new reader's actual day; retain the emotional relief, substantial demonstrations and dark final pause.

### Single-feature landing page built around familiar situations

1. **Promise** — Short centered feature title and large layered dark product object.
2. **Capability chapters** — Alternating scenario headlines with colored ending phrases and matching offset image edges.
3. **Demonstration** — Wide video thumbnail with a central play control.
4. **Closing call and proof** — Centered invitation over a faded staggered review wall.
5. **Wayfinding** — Shared dark footer with category colors and current update.

**Transfer:** Lead with the reader's circumstance, show the result and use color as a paired text-and-media cue.

### Feature landing page with deeper technical and compatibility reassurance

1. **Promise** — Centered feature headline over layered application and call imagery.
2. **Capability chapters** — Alternating dark product demonstrations with accent phrases.
3. **Human proof** — Wide violet-black quote panel with a portrait and emphatic result inside the quote.
4. **Capability depth** — Heading pair followed by saturated unequal feature tiles.
5. **Compatibility reassurance** — Low dark panel with a short assertion and integration marks.
6. **Closing call and proof** — Faded review conversion, then shared footer.

**Transfer:** Separate core outcomes from detailed capabilities; keep a quantified claim within authentic attributed proof, not an invented stat strip.

### Capability overview connecting several related product functions

1. **Promise** — Centered headline, description and signup over a soft violet/burgundy atmosphere.
2. **Product demonstration** — Layered desktop and smaller-device product composition.
3. **Social proof** — Centered explanation followed by a restrained monochrome customer-mark grid.
4. **Capability chapters** — Alternating compact demonstrations and short outcome-led copy with repeated signup actions.
5. **Closing call and proof** — Review wall invitation and shared dark footer.

**Transfer:** Unify several capabilities through a single visible workflow rather than an abstract AI diagram.

### Plan selection with an expressive introduction and sober comparison

1. **Promise** — Hand-lettered violet category art with a white doodle and short benefit statement.
2. **Pricing** — Billing pills and three aligned plan cards; single upgrade action below.
3. **Sales reassurance** — Small contact invitation beneath the shared action.
4. **Closing call and proof** — Review conversion wall followed by the shared footer.

**Transfer:** Use the playful artwork once; keep feature, price and billing details consistent across tiers.

## Writing

Warm, direct and reassuring. The product sounds capable without sounding bossy: it recognizes a busy life and offers a little less effort, not a total personal transformation.

**Do not copy:** Do not reuse Superlist or Wunderlist names, product labels such as Talk, logos, interface artwork, customer identities, review quotes, proprietary feature claims, plan prices, usage limits, numerical performance claims or release details. Source examples illustrate tone only; write truthful equivalents for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Name the product when clarifying what it does; use we sparingly. Reader situations lead, product mechanics follow.
- **Rhythm:** Short paired headlines, often two complete fragments with periods. Follow them with a concrete paragraph of two or three sentences; let tiny labels organize the story rather than explain it.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An understated human benefit rather than a feature superlative. | 5–9 words | “A little less on your mind.” |
| Chapter heading | Two balanced phrases connect an everyday moment with a felt result. | 6–12 words | “Catch the thought. Keep your flow.”<br>“A full life. A doable day.” |
| Supporting paragraph | Begin with familiar details, then describe the useful action plainly. | 25–45 words | “The follow-up you remembered on your walk. The idea that arrived between meetings. Type it or say it with Talk, and give it a place before it gets away.” |
| Dark feature promise | Concise conversational outcome or scenario followed by a short punchline. | 3–14 words | “Talk and done.”<br>“Stay in the flow with instant notes.” |
| Primary action | A small, low-pressure first step with a clear verb. | 2–5 words | “Start for free”<br>“Start your first list” |
| Closing statement | A large emotional release paired with a small concrete next move. | 5–9 words | “Big exhale. Small first step.” |

**Words and phrasing to use:** a little less; make room; keep your flow; next step; together; right there; everyday details; one place

**Avoid:** crush your goals; dominate; 10x your life; revolutionary ecosystem; unlock limitless potential; hustle harder

**Rules:**

- Use ordinary verbs before technical nouns.
- Describe the reader's situation before naming the mechanism.
- Use contrast gently: less remembering, more living; avoid fear or guilt.
- Keep action labels concrete and avoid exclamation marks.
- Make numerical claims only when there is real proof; the core voice does not need a metric to feel persuasive.

## Do's and Don'ts

### Do

- Keep the default page on #fffdf9 and reserve #181824 for the closing world and footer.
- Pair 48px/1.08 Haffer chapter headings with 18px/1.65 Inter paragraphs.
- Keep the tiny chapter eyebrow at 11px with 1.5px tracking.
- Use equal 520px text/media columns and an 80px gap for core chapters.
- Give square lifestyle media and large panels 20px corners.
- Preserve the 51px red polished action as the primary conversion cue on both themes.
- Let the closing statement grow to 88px while narrowing its measure to 780px.
- Use colored 16px footer headings above muted 14px links and a single current-update card.

### Don't

- Do not make the default landing page uniformly dark just because feature pages use that variant.
- Do not use the 44px dark feature title as the ordinary light-page heading; its tight 1.0 leading belongs to that variant.
- Do not apply Haffer Bold to long paragraphs; body copy is Inter 400.
- Do not turn the red action into a flat rectangular 8px-radius button; the visible surface is a 100px-radius lozenge.
- Do not scatter the footer's yellow, blue, green and pink across ordinary body paragraphs.
- Do not turn the 20px-radius media system into fully pill-shaped image frames.
- Do not make every plan a bright solid fill; paid tiers remain near-black with thin violet emphasis.
- Do not imitate a product dashboard through generic empty blocks; demonstrate an intelligible working state.

## Motion and responsive

### Motion

**Observed:**

- Footer link color declares a 0.2s cubic-bezier(0.44, 0, 0.56, 1) transition, becoming white on hover.
- Light secondary actions declare a warm-red hover color without an underline.
- Core product scenes use video media; no matched marketing animation timing is specified.

**Transfer:**

- Keep the known link behavior a restrained color change. Let product motion explain a single interaction inside its scene rather than moving the whole editorial layout.

**Unknown:**

- Button hover, active and focus-visible styling is unspecified.
- Scroll choreography, video playback timing and review-wall movement are not established.

### Responsive

**Observed:**

- Width breakpoints cluster around 810px and 1200px, with wider-layout adjustments around 1260px–1400px.

**Transfer:**

- On narrow screens, stack paired chapters into a single story while keeping the device scene substantial and the eyebrow/title relationship intact.
- Keep the hand-mark attached to its word, and let the large opening and closing lines rewrap without losing their paired rhythm.
- Collapse plan comparisons and saturated paired tiles vertically rather than squeezing detailed content into miniature columns.

**Unknown:**

- Exact mobile type sizes, margins, navigation behavior and breakpoint-specific layout rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
