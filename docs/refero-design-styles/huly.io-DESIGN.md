# Huly — luminous digital machinery

## Overview

A cinematic software style that alternates near-black stages with cool off-white chapters. Tightly packed geometric sans headlines and restrained grotesk text sit beside polished interfaces, blue-violet light, warm edge flares and tactile digital objects. It suits ambitious technical products with many capabilities: spacious at the chapter level, richly layered inside demonstrations.

### Essentials

- Headlines feel compressed and sculptural rather than editorial: 84px/0.9 at weight 600 with -0.04em tracking opens the story; 80px chapter titles tighten to -0.05em and line heights of 0.8–1.
- The opening is a light-powered product stage: left-aligned copy in a 616px measure starts after 184px of top space, while a vertical blue-white beam bends into a broad interface entering the bottom of the first 900px.
- Conversion buttons look electrically heated: 40px silver pills, 12px bold capitals and a cream-orange flare concentrated at the right tip; secondary actions remain dark outlined pills.
- Color behaves as emitted light, not painted branding: most of the page stays #090a0c, #111111 or #f6f6f6; blue-violet and peach are localized to media edges, clipped headline gradients and small annotations.
- Interfaces become theatrical objects: dark demonstrations sit inside 12px rounded frames with white rings, selective illumination and fading peripheral detail; include both a major framed demonstration and a rounded, uneven capability mosaic.
- The closing call is another object scene, not a plain text banner: an oversized dark circular artifact with concentric detail, orange and violet raking light, and an 80px two-line invitation alongside it. Use a layered dial or sculpted product symbol when no physical equivalent exists.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot edge | `#e98463` | `--color-ember` | accent, border | Concentrated warm pill edge, never a whole-section fill. |
| Link blue | `#5683da` | `--color-hover-blue` | link | Navigation hover and collaboration annotations. |
| Flare apricot | `#ffaa81` | `--color-apricot` | accent | Warm halo surrounding the action light. |
| Flare gold | `#ffda9f` | `--color-gold` | accent | Middle ring of the action glow. |
| Warm button ink | `#5a250a` | `--color-button-ink` | text | Main action labels. |
| Headline lavender | `#d5d8f6` | `--color-lavender` | text, accent | Late stop in white-to-lavender display gradients. |
| Blue-gray haze | `#cbd3eb` | `--color-haze` | background, accent | Cool lower portion of diffuse light backdrops. |
| Diffuse peach | `#f8e6dd` | `--color-peach` | background, accent | Blurred illumination behind light-field card groups. |
| Headline pearl | `#fdf7fe` | `--color-pearl` | text, accent | Final display gradient stop. |
| Flare center | `#fffff5` | `--color-cream` | accent | Bright center of the main action light. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Button silver | `#d1d1d1` | `--color-silver` | action, surface | Main pill substrate under the warm light. |
| Night canvas | `#090a0c` | `--color-canvas` | background | Opening, closing and the base of dark pages. |
| Secondary action black | `#0b0c0f` | `--color-secondary` | action | Companion pill background. |
| Media black | `#0c0c0d` | `--color-media` | surface | Inset capability demonstrations. |
| Near-black ink | `#0b0d10` | `--color-ink` | text | Large titles on light fields; inverse pricing action text. |
| Charcoal band | `#111111` | `--color-band` | background, surface | Dark technical demonstration chapters. |
| Graphite | `#303236` | `--color-body` | text | Paragraphs on light fields. |
| Footer gray | `#61656b` | `--color-footer` | text | Low-emphasis footer text. |
| Muted silver | `#95979e` | `--color-muted` | text | Support copy on charcoal. |
| Soft white caption | `#a9a9aa` | `--color-caption` | text | White at 65% over night-black media; use rgba(255,255,255,0.65) inside cards. |
| Light gray link | `#c9cbcf` | `--color-link` | text, link | Footer legal links and subordinate price units. |
| Silver text | `#e5e5e7` | `--color-support` | text | Opening and closing support lines. |
| Cool paper | `#f6f6f6` | `--color-paper` | background | Broad light capability chapters; the predominant middle-page field. |
| White | `#ffffff` | `--color-white` | text, surface | Dark-field titles and highlighted plan actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Smoked plan glass | `#0b0c0e` | `--color-plan-fill` | surface | rgba(13,15,17,0.4) over night canvas. |
| pricing pages | Smoked hairline | `#151618` | `--color-hairline` | border | White at 5% over night canvas; faint plan edges. |
| pricing pages | Pill outline | `#3a3b3d` | `--color-outline` | border | White at 20% over night canvas; outlined plan actions. |

## Typography

- **__esbuild_b38aaf** — All major display and capability headings. A proportional geometric sans appearance with broad circular counters and tightly fitted lowercase; not a code-like monospace appearance. If unavailable, use **Manrope**. Use weights 400–600 and retain tight tracking; check line breaks against the intended measure. Font stack: "__esbuild_b38aaf", "Manrope", Arial, sans-serif.
- **__Inter_f367f3** — Supporting copy, navigation, captions, actions and pricing. Compact neutral grotesk with a tall x-height and crisp UI numerals. Font stack: "__Inter_f367f3", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | __esbuild_b38aaf | 600 | 84px | 0.9 | -0.04em | Main opening headline, usually two closely stacked lines. |
| heading | __esbuild_b38aaf | 600 | 80px | 0.8 | -0.05em | Default light-field chapter headline. |
| heading-two-line | __esbuild_b38aaf | 600 | 80px | 0.9 | -0.05em | Longer light-field titles broken into two emphatic phrases. |
| heading-editorial | __esbuild_b38aaf | 600 | 80px | 1 | -0.05em | Titles integrated with live editing graphics and prose. |
| heading-dark | __esbuild_b38aaf | 500 | 80px | 0.9 | -0.02em | Technical chapter titles on charcoal fields. |
| closing | __esbuild_b38aaf | 500 | 80px | 0.8 | -0.03em | Two-line closing invitation with the pearlescent text treatment. |
| feature-title-dark | __esbuild_b38aaf | 400 | 32px | 1 | -0.02em | Open-grid headings on charcoal. |
| feature-title | __esbuild_b38aaf | 400 | 28px | 1 | -0.02em | Small light-field capability headings. |
| editorial-body | __Inter_f367f3 | 400 | 22px | 1.375 | -0.04em | Demonstration prose interwoven with editor annotations. |
| body | __Inter_f367f3 | 400 | 18px | 1.25 | -0.04em | Default chapter support paragraphs on light fields. |
| hero-support | __Inter_f367f3 | 400 | 18px | 1.375 | -0.04em | Opening support paragraph. |
| body-dark | __Inter_f367f3 | 400 | 16px | 1.375 | -0.04em | Support copy in dark technical and closing sections. |
| card-copy | __Inter_f367f3 | 300 | 16px | 1.375 | -0.02em | Muted sentence inside demonstration cards. |
| card-lead | __Inter_f367f3 | 500 | 16px | 1.375 | -0.02em | White capability name inline at the beginning of card-copy. |
| navigation | __Inter_f367f3 | 400 | 14px | 1.5 | normal | Main navigation links. |
| footer | __Inter_f367f3 | 400 | 14px | 1 | -0.02em | Compact bottom utility row. |
| action | __Inter_f367f3 | 700 | 12px | 1.5 | -0.015em, uppercase | Warm primary pill labels. |
| action-secondary | __Inter_f367f3 | 700 | 12px | 1.5 | -0.01em, uppercase | Companion community pill labels. |
| account-action | __Inter_f367f3 | 700 | 11px | 1.5 | -0.01em, uppercase | Small header account pills. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | __Inter_f367f3 | 600 | 64px | 1.375 | -0.04em | Dominant integer price; smaller decimal and cadence sit on its baseline. |
| pricing pages | pricing-prose | __Inter_f367f3 | 500 | 36px | 1.75 | normal | Large explanatory paragraphs, including the final contact invitation. |
| pricing pages | plan-title | __Inter_f367f3 | 600 | 20px | 1.375 | -0.04em | Plan names above price. |
| pricing pages | plan-summary | __Inter_f367f3 | 500 | 18px | 1.375 | -0.03em | Short audience description under the price. |
| pricing pages | plan-action | __Inter_f367f3 | 600 | 18px | 1.75 | -0.02em, capitalize | Full-width pricing actions, distinct from marketing capitals. |

**Notes:**

- Display is visually proportional sans despite its technical family name. Preserve its roundness and condensed line spacing rather than substituting a monospace.
- The tightest tracking belongs to 80px light-field headings; dark technical headings are lighter and less tightly spaced.
- Keep the small inline capability name brighter and heavier than its continuation; do not turn every card into a separate title-and-paragraph stack.

## Layout

**Density:** Airy between chapters, compact inside demonstrations and utility controls.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-label gaps in companion actions. |
| 14px | Header action gaps. |
| 18px | Rounded capability mosaic gutters. |
| 20px | Default demonstration card gutters and opening headline-to-copy gap. |
| 24px | Card caption inset and default chapter title-to-copy gap. |
| 32px | Container side padding. |
| 40px | Support-to-card-grid spacing. |
| 44px | Opening support-to-action gap. |
| 56px | Rounded mosaic lead-in and pricing card separation. |
| 64px | Three-column capability grid gutters. |
| 96px | Dark capability grid column gap. |
| 160px | Light chapter top padding and dark demo-to-feature spacing. |
| 184px | Opening top padding. |
| 240px | Immersive light scene vertical padding. |
| 247px | Wide light mosaic lead-in and editorial chapter lower breathing room. |

### Containers and grids

- **main container**: max width 1280px · side padding 32px. Centered border-box wrapper; 1216px usable content at desktop. Align navigation, opening and standard card groups.
- **technical container**: max width 1024px · side padding 32px. 960px usable width for a focused dark demonstration and its feature grid.
- **wide scene**: max width 1408px · side padding 32px. Broad, nearly edge-to-edge capability mosaic; let atmospheric backgrounds bleed beyond it.
- **feature grid**: 3 columns · gap 64px. Open capability explanations beneath an immersive light demonstration.
- **dark feature grid**: 3 columns · gap 96px. Six open explanations in two rows, with 80px vertical row gaps.
- **prose column** (only for pricing pages): max width 960px · side padding 32px. 896px text measure, with left alignment inside a centered narrow wrapper.
- **plan rail** (only for pricing pages): gap 56px. 390px nonshrinking cards in a horizontal snap rail, with neighboring cards visible and outer edges fading.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 9999px (pill) |
|  | demo cards | 12px |
|  | mosaic cards | 30px |
| pricing pages | plan cards | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | white demo ring | `0px 0px 0px 6px rgba(255,255,255,0.4)` | Dark demonstration cards resting on light fields. |
| pricing pages | plan depth | `4px 6px 25px 0px rgba(0,0,0,0.56)` | Smoked pricing panels. |

### Surfaces

#### Night canvas · level 0

**Use:** Dark atmospheric opening and closing stages.

**CSS:** `background: #090a0c`

#### Light chapter · level 0

**Use:** Long capability and prose chapters.

**CSS:** `background: #f6f6f6`

**Observed:** Dark inset media supplies contrast; the field itself stays nearly white.

**Transfer:** Keep the light field clean enough that localized illumination remains visible.

#### Technical band · level 0

**Use:** Focused technical proof.

**CSS:** `background: #111111`

#### Pearlescent title

**Use:** Opening and closing headline treatment.

**CSS:** `background-image: linear-gradient(to right bottom, #ffffff 30%, #d5d8f6 80%, #fdf7fe); background-clip: text; color: rgba(0,0,0,0)`

**Observed:** The gradient remains predominantly white; its color shift is subtle.

**Transfer:** Apply to whole display phrases, not individual rainbow words.

#### Diffuse light wash

**Use:** Atmosphere behind card groups on cool paper.

**CSS:** `background-image: linear-gradient(#f8e6dd 15%, #cbd3eb 83.5%); border-radius: 50%; filter: blur(64px); opacity: 0.6`

**Observed:** A tall soft ellipse sits behind, not over, the cards.

**Transfer:** Use an approximately 599px by 1000px decorative layer and match the soft glow; exact stops are not essential.

#### Smoked plan glass · level 1

**Only for:** pricing pages

**Use:** Plan panel backing.

**CSS:** `background: rgba(13,15,17,0.4); border: 1px solid rgba(255,255,255,0.05); border-radius: 24px; box-shadow: 4px 6px 25px 0px rgba(0,0,0,0.56)`

**Observed:** The highlighted entry plan has luminous mint artwork around its perimeter; other panels remain dark.

**Transfer:** Reserve the electric outline for one selected plan.

## Components

### Navigation link

**Use:** Main header browsing.

**CSS:** `display: inline-flex; padding: 12px; color: #ffffff`

**Text style:** `navigation` — __Inter_f367f3 400 · 14px/1.5

**Observed:** A compact logo sits at left, links form a single cluster beside it, and repository/account actions align right. Resources and community use tiny chevrons. Header height is 64px.

**States:** Declared: hover color #5683da; focus-visible unknown.

### Account pill

**Use:** Low-profile authentication actions in the header.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 32px; padding: 0px 16px; border-radius: 9999px; background: #090a0c; border: 1px solid rgba(255,255,255,0.3); color: #ffffff`

**Text style:** `account-action` — __Inter_f367f3 700 · 11px/1.5 · tracking -0.01em · uppercase

**Observed:** Two small outlined actions sit beside the repository link. A layered pseudo-element border grades from brighter top to dimmer bottom.

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; position: relative; height: 40px; padding: 0px 64px; border-radius: 9999px; background: #d1d1d1; border: 1px solid rgba(255,255,255,0.6); color: #5a250a`

**Text style:** `action` — __Inter_f367f3 700 · 12px/1.5 · tracking -0.015em · uppercase

**Observed:** A right-pointing arrow follows the opening label. The pill has a warm illuminated right tip, with a larger halo behind the perimeter. The closing version is 174px wide rather than the opening's 240px.

**Transfer:** Construct the glow as separate decorative layers so text stays sharp; use the action-light recipe.

### Companion button

**Use:** Secondary route beside a closing main action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; height: 40px; padding: 0px 24px 0px 20px; border-radius: 9999px; background: #0b0c0f; border: 1px solid rgba(255,255,255,0.1); color: #ffffff`

**Text style:** `action-secondary` — __Inter_f367f3 700 · 12px/1.5 · tracking -0.01em · uppercase

**Observed:** A small colored destination icon precedes the label. It does not share the main action's hot white center.

**States:** Declared: hover border-color rgba(255,255,255,0.15); focus-visible unknown.

### Demonstration card

**Use:** Uneven two-column capability gallery.

**CSS:** `position: relative; height: 420px; overflow: hidden; background: #0c0c0d; border-radius: 12px; box-shadow: 0px 0px 0px 6px rgba(255,255,255,0.4)`

**Text style:** `card-copy` — __Inter_f367f3 300 · 16px/1.375 · tracking -0.02em

**Observed:** Alternate narrow and wide cards across two rows, 428px and 768px at desktop. Media fills the card; an inline bright capability label and muted continuation sit at the bottom with a 24px inset over a dark fade.

**Transfer:** Make each card a miniature illuminated demonstration, not a generic icon tile.

### Mosaic tile

**Use:** Compact multi-capability overview.

**CSS:** `position: relative; overflow: hidden; border-radius: 30px; outline: 4px solid rgba(255,255,255,0.6)`

**Observed:** Dark illustrated tiles have captions at their top and interfaces below, with wide and narrow proportions interlocked. A circular calendar-like object punctuates the rectangular rhythm; bright white gutters separate pieces.

**Transfer:** Use unequal spans, one circular graphic, and light paths linking the cards.

### Footer utility link

**Use:** Legal links in the single-row footer.

**CSS:** `display: inline-flex; align-items: center; color: #c9cbcf`

**Text style:** `footer` — __Inter_f367f3 400 · 14px/1 · tracking -0.02em

**Observed:** Copyright sits left, legal links follow with a 26px gap, monochrome social icons occupy the middle, and a warm pixel-heart maker credit sits at the right. The footer occupies an 82px bottom strip rather than a multi-column sitemap.

**States:** Declared: hover color #ffffff; focus-visible unknown.

### Plan card

**Only for:** pricing pages

**Use:** Plan comparison in a horizontal rail.

**CSS:** `display: flex; flex-direction: column; flex-shrink: 0; width: 390px; height: 529px; padding: 28px 28px 25px; border-radius: 24px; background: rgba(13,15,17,0.4); border: 1px solid rgba(255,255,255,0.05); box-shadow: 4px 6px 25px 0px rgba(0,0,0,0.56)`

**Text style:** `plan-title` — __Inter_f367f3 600 · 20px/1.375 · tracking -0.04em

**Observed:** Order is plan name, large price with small cadence, two-line audience summary, hairline, five check rows, then a bottom-pinned action. The entry plan gets the electric outline and white action.

**Transfer:** Keep names and summaries brief enough that dividers and actions line up.

### Plan button

**Only for:** pricing pages

**Use:** Full-width action at the base of each plan.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 332px; height: 56px; border-radius: 9999px; border: 1px solid rgba(255,255,255,0.2); color: #ffffff; background: rgba(0,0,0,0)`

**Text style:** `plan-action` — __Inter_f367f3 600 · 18px/1.75 · tracking -0.02em · capitalize

**Observed:** Outlined on paid plans; white-filled with near-black text on the entry plan.

**States:** Declared: hover border-color rgba(255,255,255,0.5); focus-visible unknown.

## Imagery and graphics

### Beam-powered product stage

**Use:** Signature opening graphic and major demonstrations.

**Observed:** A hairline blue-white vertical shaft descends just right of center through a near-black textured field, flares outward near the bottom and follows the top edge of a dark interface. Violet/cyan halos reveal faint background UI; most of the field remains dark. A large interface is only partly visible at the first fold.

**Transfer:** Stage the new product's strongest screen as an object receiving light. Without finished media, render a simplified but credible interface with one legible workflow and the same beam, rounded rim and deep backing.

**Build:** Use an SVG path running vertically near 57% of the scene width, then curving outward with a broad radius into a horizontal ledge. Stack a 2px white core, an 8px rgba(180,190,255,0.8) stroke blurred 5px and a 56px rgba(90,100,255,0.45) stroke blurred 32px. Add a low-opacity radial blue haze and a masked dot texture behind. Place the dark interface above the ledge, with a 12px radius and a thin bright top/right rim. These dimensions are a reconstruction recipe.

### Action light

**Use:** Signature primary pill finish.

**Observed:** A silver body burns cream at its right tip, surrounded by apricot-orange light. The illumination spills outside the pill but leaves the label dark and sharp.

**Transfer:** Retain the asymmetry: one hot tip rather than an evenly glowing outline.

**Build:** Inside the pill, place a 121px radial layer centered on the right edge: #fffff5 3.5%, #ffaa81 26.5%, #ffda9f 37.5%, rgba(255,170,129,0.5) 49%, rgba(210,106,58,0) 92.5%. Add a broad cream/peach elliptical highlight blurred 5px. Behind the pill, draw a slightly larger rounded rim with a 103.7deg gradient from translucent warm gray through translucent peach to #e98463 at 85% and #ffffff at 92%; blur a duplicate for the outer halo.

### Illuminated interface fragments

**Use:** Demonstration cards and capability mosaics.

**Observed:** Floating panels, command menus, task cards, avatar circles and notifications appear over almost-black backing. White foreground panels catch peach light while peripheral panels disappear into gradients; tiny dots make the glow look tactile rather than flat. Some card groups sit on faint peach and blue-gray haze.

**Transfer:** Select a single useful interaction per card. Keep foreground detail clear and simplify background UI; use two or three translucent layers rather than a full unreadable dashboard.

**Build:** Layer a dark base, two offset interface panels and one focused foreground panel. Put a radial cool halo behind one corner and a smaller warm halo behind the opposite edge. Overlay an SVG dot pattern with 1px dots at 3px spacing, at low alpha, masked to the illuminated region. Apply black-to-transparent edge fades without obscuring the primary interaction.

### Light architectural scene

**Use:** Immersive collaboration or human-centered capability proof.

**Observed:** A bright white room-map relief extends beyond the content. Cyan light washes through its compartments. A large natural-light video portrait sits in a frosted white rounded frame with a vertical strip of three smaller participant portraits and circular controls.

**Transfer:** Use authentic human imagery only where the product has a human interaction. Otherwise stage the equivalent real activity in a bright relief-like environment rather than inserting unrelated portraits.

**Build:** Create thin white rectangular wall segments with subtle cool-gray shadows over #f6f6f6, add broad cyan radial washes beneath, and float a large framed demonstration above. Keep the wall geometry low-contrast so the main activity remains dominant.

### Editorial live canvas

**Use:** Long-form product explanation interwoven with the tool itself.

**Observed:** An offset prose column is annotated by avatars, cursor stems, a yellow selected passage and a floating formatting bar. A small collaboration card floats in the left margin. Large real-world billboard imagery is embedded below the text; it is supporting content rather than a full-bleed lifestyle hero.

**Transfer:** Turn one paragraph into a believable interaction with the new product. Keep annotations purposeful; use a relevant real-world output image below rather than generic decorative photography.

### Sculpted closing artifact

**Use:** Signature dark closing scene.

**Observed:** A large oblique black clock-like disc occupies the left half, with concentric engraved rings, fine dotted texture, a thick beveled rim and slim hands. Orange light from upper-left and blue-violet light from lower-right rake across it; diagonal light planes extend beyond the scene. Copy occupies the right half.

**Transfer:** Always close a broad marketing story with a tactile symbolic object and an invitation. Use a layered product token or dial if no physical product exists.

**Build:** Build an SVG dial with nested near-black ellipses, alternating thin rings and broad bevel gradients, a low-opacity dot pattern and a central abstract product glyph. Tilt slightly using perspective or asymmetric ellipses. Put orange and violet radial washes behind opposing sides; add two broad diagonal trapezoids with gradient fades and matching dot texture. A convincing layered SVG is the minimum substitute for a 3D render.

### Electric selected plan

**Only for:** pricing pages

**Use:** Emphasized entry or selected pricing tier.

**Observed:** A mint electric filament surrounds the whole rounded panel, with a brighter top edge, scattered sparks and a soft green internal reflection. The rail fades at the viewport edges.

**Transfer:** Use this as a selection treatment, not a general-purpose green brand identity.

**Build:** Trace a rounded rectangle twice in SVG: a thin white-mint core and a wider rgba(70,255,213,0.6) glow blurred 12px. Add a slightly perturbed parallel path and sparse small particles around its edge. Place a broad rgba(70,255,213,0.12) radial reflection behind the upper-left panel corner. Match the mint effect; exact light values are not essential.

### Icons

**Observed:** Utility and social marks are compact solid monochrome SVGs, generally 16px–18px. Pricing rows use 16px check marks; demonstration control icons may use 20px–28px forms. Colored marks are restricted to recognizable destinations and collaboration cues.

**Transfer:** Use a consistent simple icon set, keeping social marks monochrome in the footer and capability glyphs subordinate to the illustrated scenes.

## Section recipes

How recurring sections are built.

### First screen: Light-powered opening

**Observed:** A transparent 64px navigation strip floats over Night canvas. The main content starts after 184px of top space inside the main container: a left-aligned 616px headline measure, two 84px/0.9 lines in Pearlescent title, a 448px support measure 20px below, then Primary button after 44px. Behind the copy are faint UI silhouettes and a cool textured glow; a narrow vertical beam sits just right of center. It bends outward into a large dark interface across the lower portion. Within the first 900px, navigation, the complete promise, support and action are visible, plus the upper portion of the product object entering around the lower fifth. Most of the demonstration and the small capability strip continue below the fold.

**Transfer:** Replace the promise and interface with the new product's clearest benefit and one credible workflow. Preserve the contrast between compact left copy and oversized light scene; use the beam-powered product-stage reconstruction when polished media is unavailable. Pricing-style information pages instead begin with large left-aligned prose in a narrow column on Night canvas.

**Avoid:** Do not center the whole composition, shrink the scene to a thumbnail, or put a bright interface behind the headline where it competes with reading.

**Text style:** `display` — __esbuild_b38aaf 600 · 84px/0.9 · tracking -0.04em

### Capability gallery

**Observed:** Light chapter uses heading and a support paragraph separated by 24px, followed after 40px by Demonstration cards. Alternating 428px and 768px cards create an unequal two-column gallery with 20px gaps. Diffuse light wash sits behind the group; captions sit at the bottom.

**Transfer:** Group several primary benefits into distinct mini-scenes, varying panel widths with the complexity of each interaction.

**Text style:** `heading` — __esbuild_b38aaf 600 · 80px/0.8 · tracking -0.05em

### Immersive light proof

**Observed:** A two-line title and narrow support paragraph are offset toward the center-right above the Light architectural scene. The scene extends beyond the text container. Beneath it, a larger support statement leads into three open capability explanations with 64px gaps. The chapter has 240px vertical breathing room.

**Transfer:** Use a luminous, human-readable activity scene to interrupt darker demonstrations, then summarize the concrete capabilities beneath it.

**Text style:** `heading-two-line` — __esbuild_b38aaf 600 · 80px/0.9 · tracking -0.05em

### Dark technical proof

**Observed:** Technical band contains a 672px two-line title and 580px supporting measure. A 960px wide framed interface dominates the center, warmed along the top/right and cooled along the left. Below, six icon-led explanations form an open three-column grid with 96px column gaps and 80px row gaps.

**Transfer:** Give an important integration, workflow or technical distinction its own contrasting chapter; keep the feature explanations unboxed.

**Text style:** `heading-dark` — __esbuild_b38aaf 500 · 80px/0.9 · tracking -0.02em

### Interlocking capability mosaic

**Observed:** A broad light field leads into Mosaic tiles after 56px. Rounded dark cards vary in span across two rows; a circular date object supplies a numerical focal point. White gutters, cyan connecting light and small warm reflections make the cluster read as one connected system rather than separate widgets.

**Transfer:** Give the new product a connected visual overview with one large numeral or meaningful symbolic object; the numeral is a graphic anchor, not automatically a business statistic.

**Text style:** `heading` — __esbuild_b38aaf 600 · 80px/0.8 · tracking -0.05em

### Annotated editorial demonstration

**Observed:** A 707px prose column sits to the right of a narrow floating-card rail. A large two-line title is interrupted by a collaborator avatar/cursor. Paragraphs, selected yellow text, a toolbar, embedded media and a version-history side demonstration make the page read like a live document.

**Transfer:** Show the product's effect on actual content. Keep the editorial column readable and the marginal card secondary.

**Text style:** `heading-editorial` — __esbuild_b38aaf 600 · 80px/1 · tracking -0.05em

### Artifact closing call

**Observed:** A 694px Night canvas scene pairs the Sculpted closing artifact on the left with a 510px two-line pearlescent invitation on the right. Support copy follows after 8px; a warm Primary button and dark Companion button follow after 28px with 31px between them. The Footer utility link row is integrated into the scene's bottom edge.

**Transfer:** Make the final invitation optimistic and brief; pair it with a relevant symbolic object and repeat the same warm main action.

**Text style:** `closing` — __esbuild_b38aaf 500 · 80px/0.8 · tracking -0.03em

### Large-prose pricing explanation

**Only for:** pricing pages

**Observed:** Night canvas stays uninterrupted. An 896px text column begins after 212px of top padding with 36px/1.75 medium prose. Inline sculpted app/resource icons replace occasional nouns; later words brighten as the narrative progresses. Paragraph blocks are separated by 64px, creating 83px visible baseline-box gaps. A Plan card rail interrupts the prose. The ending returns to custom-needs prose and a prominent underlined blue-to-cyan contact link with a paper-plane icon, followed by ample dark space and the same single-row footer.

**Transfer:** Explain the charging model before offering choices. Use large conversational paragraphs rather than a standard title and dense comparison table, and end with a direct custom-contact route.

**Text style:** `pricing-prose` — __Inter_f367f3 500 · 36px/1.75

## Page flow

**Storyline:** Promise or rationale → tangible product or commercial proof → capability explanation → focused detail → invitation → compact utility footer.

### Broad product marketing and capability storytelling

1. **Promise** — Compressed two-line claim beside an electric light stage and one warm action.
2. **Product demonstration** — Large framed interface followed by an uneven gallery of illuminated interaction cards.
3. **Capability chapters** — An immersive light activity scene alternates with a focused dark technical demonstration and open feature grids.
4. **Connected-system overview** — Interlocking rounded tiles and a circular numerical object convey breadth.
5. **Detailed proof** — Annotated prose and embedded real output make a workflow tangible.
6. **Closing call** — Sculptural dark object, two-line invitation, paired actions and compact footer.

**Transfer:** Adapt the number and order of capability chapters to the product. Retain the contrast between luminous demonstrations, light reading space and the tactile closing scene.

### Explain commercial logic and let people choose or request a tailored plan

1. **Rationale** — Large readable prose explains the business model, with occasional inline illustrated nouns.
2. **Objection handling** — Separate spacious paragraphs clarify each resource or charging dimension.
3. **Pricing** — Horizontal plan rail with a mint-highlighted entry plan, price-led cards and aligned actions.
4. **Custom route** — Large prose describes tailored needs and asks a direct question, followed by an underlined illustrated contact link.
5. **Utility ending** — Substantial dark breathing room ends in the shared compact footer.

**Transfer:** Use transparent explanations based on the new product's real pricing logic. Keep this all-dark prose treatment scoped to information-heavy commercial pages.

## Writing

Confident and optimistic, with direct functional explanations under sweeping short headlines. Technical detail is approachable rather than jargon-heavy; commercial copy explains the rationale before asking for commitment.

**Do not copy:** Do not reuse Huly names, logos, artwork, plan names, competitor-replacement claims, prices, allowances, promises or customer identities. Source quotations below illustrate syntax and tone only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your team; name the product in explanatory prose. Use we or our for company commitments and custom service offers.
- **Rhythm:** Headlines are short phrases, often split by a full stop. Support lines use one or two concrete sentences. Capability captions begin with a brief functional label and continue in the same line; pricing switches to longer explanatory paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Broad product category followed by who it helps. | 5–8 words | “Everything App for your teams” |
| Chapter headline | An action or benefit, then a short clarifying fragment. | 3–8 words | “Work together. Like in the office.”<br>“Sync with GitHub. Both ways.” |
| Support | Explain the mechanism that makes the benefit real. | 18–35 words | “Create customized virtual office spaces for any department or event with high quality audio and video conferencing.” |
| Capability caption | Short noun label ending in a period, followed by a practical outcome. | 10–22 words | “Keyboard shortcuts. Work efficiently with instant access to common actions.” |
| Primary action | Short verb phrase that promises access or a demonstration. | 2–3 words | “See in Action”<br>“Start Free” |
| Commercial explanation | State the cost rule and its boundary plainly. | One or two full sentences | “Network charges apply only to audio and video calls.” |
| Closing invitation | Brief optimistic invitation rather than another feature list. | 3–5 words | “Join the Movement” |

**Words and phrasing to use:** work together; your team; create; manage; connect; sync; instantly; customized; workflow; getting started

**Avoid:** disruptive synergy; 10x everything; magical revolution; unexplained acronyms; ironic slang

**Rules:**

- Pair an ambitious headline with a specific functional explanation.
- Use sentence case for prose and headings; uppercase is a visual treatment for small marketing actions.
- Explain limitations and commercial boundaries as clearly as benefits.
- Keep card captions compact enough to stay subordinate to the illustration.

## Do's and Don'ts

### Do

- Keep the default opening headline at 84px/0.9 with -0.04em tracking.
- Keep chapter support measures around 448px–705px instead of spanning the full container.
- Use 12px demonstration corners and a 6px translucent white ring on light backgrounds.
- Use 30px mosaic corners to distinguish the connected overview from the regular gallery.
- Preserve the 40px marketing pill versus 56px pricing-action distinction.
- Allow 160px–247px chapter breathing room around rich media.
- Concentrate the orange flare on the main action's right tip.
- Finish with an 82px utility strip rather than a tall sitemap. 

### Don't

- Do not turn the interface demonstrations into flat pastel cards; the backing is near-black.
- Do not spread the mint selected-plan effect across ordinary marketing components.
- Do not replace the proportional geometric headline face with a monospace just because its technical family name looks developer-oriented.
- Do not apply the 36px/1.75 pricing prose treatment to ordinary support paragraphs.
- Do not use the 64px price recipe for unrelated claims or invent statistical proof from the circular date graphic.
- Do not make every card equally sized; the gallery and mosaic depend on unequal spans.
- Do not tint the entire light chapter blue or peach; leave the #f6f6f6 field recognizable.
- Do not enlarge footer social icons into a second navigation system; retain their 18px utility scale.

## Motion and responsive

### Motion

**Observed:**

- Navigation, main actions and utility links declare 0.2s color-related transitions using cubic-bezier(0.4,0,0.2,1).
- Pricing action borders declare 0.5s transitions with the same easing; explanatory word spans declare 0.5s opacity transitions.
- Pricing prose visibly progresses from dim words to bright words; selected-plan artwork and product scenes include video/canvas media.

**Transfer:**

- Treat illumination and selective word emphasis as the motion vocabulary; keep text geometry stable while light and opacity change.
- Maintain a complete readable demonstration and coherent object silhouette when motion is reduced.

**Unknown:**

- Scroll trigger thresholds, video timing and continuous-art animation curves are not known.

### Responsive

**Observed:**

- Width breakpoints are declared at 413px, 639px, 767px, 1023px, 1279px, 1280px and 1439px.
- Heading classes include smaller 64px and 36px variants; demonstration-card heights include 300px and 260px variants. Navigation has a hidden narrow-layout variant; mosaic classes include two-column then one-column layouts.

**Transfer:**

- On narrow screens, preserve the copy-versus-light hierarchy by letting the beam and product object move below the promise rather than squeezing into a side thumbnail.
- Let wide demonstrations extend or scroll while keeping their central interaction visible; keep the pricing rail horizontally scrollable.
- Stack closing copy and artifact without losing the diagonal light planes or the repeated warm action.

**Unknown:**

- Exact mobile compositions, menu behavior and breakpoint-specific art positions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
