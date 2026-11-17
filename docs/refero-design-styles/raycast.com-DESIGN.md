# Raycast — luminous command surfaces

## Overview

A near-black product theatre with hot red light, smoky glass and small, practical controls. Clean grotesk typography and technical monospace captions give luminous interface scenes an engineered rather than futuristic feel. It suits capable software and carefully made hardware, combining spacious storytelling with dense, useful detail.

### Essentials

- A modest headline inside a dramatic light sculpture: the default opening uses centered Inter 64px/1.1 at weight 600 in a 540px measure, over diagonal crimson blades on a near-black stage.
- Black is the connective tissue, not alternating color bands: #07080a surrounds almost every chapter; saturated color is concentrated inside the opening artwork and selected media panels while ordinary text remains white, #9c9c9d or #6a6b6c.
- Actions feel like illuminated physical keys: default buttons are 36px high with 8px corners, 14px/16px medium labels, pale #e6e6e6 faces, inset bevels and a restrained white halo.
- Small heading pairs introduce oversized demonstrations: white and gray 20px medium lines sit directly together, followed by 48px–64px of air before a product scene as wide as 1204px.
- The product floats out of darkness: interface windows get hairline light edges, translucent charcoal backing and gradients that dissolve their lower edges; use a carefully composed functional mockup when finished product media is unavailable.
- A recurring light motif ties the ending to the opening: diagonal red artwork rises behind the footer's top hairline, above six narrow link columns and a separate newsletter row; recreate the motif with layered gradient blades rather than a generic full-page glow.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal coral | `#ff6363` | `--color-red` | accent, text | Small uppercase feature labels; crimson and pink light in artwork is much more concentrated than this text accent. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-foreground` | text, action | Headlines, selected labels and brightest highlights. |
| Key face | `#e6e6e6` | `--color-button-face` | action | Primary button background. |
| Readable gray | `#9c9c9d` | `--color-secondary` | text, link | Body copy and navigation; also the visible result of 60% white on the canvas. |
| Receding gray | `#6a6b6c` | `--color-muted` | text | Support lines, technical copy and subdued annotations; also 40% white on the canvas. |
| Dormant gray | `#434345` | `--color-inactive` | text | Inactive capabilities in the interactive text wall. |
| Strong charcoal edge | `#2f3031` | `--color-edge` | border, text | Pricing outlines, technical dot fields and dark button labels. |
| Quiet dividing line | `#1b1c1e` | `--color-rule` | border | Footer separators and square technical-grid outlines. |
| Glass hairline | `#161719` | `--color-hairline` | border | Visible 6% white outline on the canvas; use the alpha recipe on layered glass. |
| Input wash | `#131416` | `--color-input` | surface, border | Visible 5% white fill and outline on the canvas. |
| Lit charcoal | `#111214` | `--color-panel-top` | surface | Upper stop of smoky panel gradients; navigation uses this hue at 75% alpha. |
| Receding charcoal | `#0c0d0f` | `--color-panel-bottom` | surface | Lower stop of panel gradients; navigation uses this hue at 90% alpha. Also the visible 2% white wash on the canvas. |
| Near-black canvas | `#07080a` | `--color-canvas` | background | Continuous background across chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| organization and pricing pages | Capability blue | `#56c2ff` | `--color-blue` | text, accent | Feature identifiers, included-plan checks and selected pricing accents. |
| pricing pages | Raised graphite | `#222326` | `--color-plan-top` | surface | Upper gradient stop of the promoted plan. |
| pricing pages | Raised graphite shade | `#151619` | `--color-plan-bottom` | surface | Lower gradient stop of the promoted plan. |
| mobile-app landing pages | Mobile glass wash | `#0b0c0e` | `--color-mobile-card` | surface | Visible rgba(49,49,49,0.1) over the near-black canvas. |

## Typography

- **Inter** — Marketing headlines, paragraphs, controls and navigation. Neutral contemporary grotesk with a high x-height; medium weights do most of the work. OpenType features: "calt", "kern", "liga", "ss03". Font stack: "Inter", "Inter Fallback", sans-serif.
- **GeistMono** — Requirements, utility links, small counts and technical explanations. Compact, even-width technical text that reads like equipment annotation. If unavailable, use **Geist Mono**. Use weights 400–500. Font stack: "GeistMono", "Geist Mono", ui-monospace, SFMono-Regular, "Roboto Mono", Menlo, Monaco, monospace.
- **jetBrainsMono** — Feature eyebrows and mobile-app chapter labels. Firm, narrow monospace, often uppercase with deliberate letterspacing. If unavailable, use **JetBrains Mono**. Use weight 500. Font stack: "jetBrainsMono", "JetBrains Mono", Menlo, Monaco, Courier, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 600 | 64px | 1.1 | normal, features "liga" 0, "ss02", "ss08" | Default two-line opening headline. |
| feature-heading | Inter | 500 | 32px | 1.2 | -0.025em | Larger feature chapter heading above a main demonstration. |
| capability-wall | Inter | 500 | 24px | 1.6 | 0.0083em | Interactive paragraph-like capability index and technical tile headings. |
| body | Inter | 500 | 14px | 1.6 | 0.014em | Compact explanatory paragraphs, card descriptions and footer headings. |
| button | Inter | 500 | 14px | 16px | 0.014em | Primary and secondary action labels. |
| utility | GeistMono | 400 | 12px | 1.6 | 0.017em | Platform requirements and alternate installation links. |
| eyebrow | jetBrainsMono | 500 | 12px | 16px | 0.12em, uppercase | Small coral feature marker above a heading. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| organization landing pages | organization-display | Inter | 700 | 72px | 84px | normal | Two-line white-to-ice-blue opening headline. |
| pricing pages | price | Inter | 600 | 64px | 1 | 0.0047em, features "liga" 0, "ss02", "ss08" | Large price with small baseline-aligned billing unit. |
| technical capability chapters | technical-display | Inter | 400 | 56px | 1.17 | 0.0036em | Narrow, multi-line headline in the engineering grid. |
| upgrade promotions | upgrade-display | Inter | 600 | 52px | 1.1 | normal | Playful upgrade headline with a glowing repeated syllable. |
| hardware landing pages | hardware-display | Inter | 500 | 50px | 1 | -0.025em | Compact hardware opening headline. |
| organization landing pages | organization-heading | Inter | 700 | 36px | 40px | normal | Centered introductions and final invitation. |
| hardware landing pages | hardware-heading | Inter | 500 | 32px | 1.25 | -0.0125em | Feature heading with white leading clause and gray secondary clause. |
| mobile-app landing pages | mobile-heading | Inter | 500 | 32px | 1.6 | 0.0063em | Spacious mobile chapter headings. |
| organization landing pages | organization-feature | Inter | 600 | 30px | 1.2 | normal | Two-line alternating feature-row headings. |
| hardware landing pages | hardware-stat | Inter | 400 | 30px | 1.15 | -0.025em | Small bento statistic with dimmed same-size unit and icon caption below. |
| mobile-app landing pages | mobile-support | Inter | 400 | 18px | 1.5 | 0.011em | Mobile chapter descriptions in a 516px measure. |
| FAQ sections | question | Inter | 600 | 16px | 1.5 | normal | Accordion question labels. |
| technical chapters and community cards | technical-copy | GeistMono | 500 | 14px | 1.6 | 0.021em | Engineering grid explanations and small community metrics. |
| mobile-app landing pages | mobile-eyebrow | jetBrainsMono | 500 | 14px | 1.15 | 0.014em, uppercase | Gray chapter identifier above mobile headings. |
| hardware landing pages | spec-label | GeistMono | 500 | 12px | 1.2 | 0.075em, uppercase | Specification headings and table labels. |

**Notes:**

- Keep the default display at weight 600, not a heavy 800; the surrounding artwork provides the impact.
- The ordinary section heading is only 20px and shares its recipe with the support line. Contrast, not size, separates the two lines.
- Negative tracking belongs to selected 32px feature headings and hardware headings; do not apply it universally to the normal-tracked opening.
- Technical chapters deliberately switch from compact proportional body copy to monospace paragraphs and a lighter, larger headline.

## Layout

**Density:** Airy between chapters, compact within controls and demonstrations; long dark intervals let each product scene stand alone.

### Spacing

**Spacing system:**

- **step** 8px — Primary declared spacing step; 12px and 4px serve tighter intermediate adjustments.

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and close eyebrow spacing. |
| 12px | Button horizontal padding and close chapter text spacing. |
| 16px | Card text gaps, navigation inset and requirements below actions. |
| 24px | Default card padding and section side padding. |
| 32px | Opening text gap, navigation side padding and grid spacing. |
| 40px | Feature-grid gaps and mobile tile padding. |
| 48px | Heading-to-feature-grid space and large card padding. |
| 64px | Heading-to-main-scene gap. |
| 96px | Footer upper inset and major internal separations. |
| 168px | Mobile-app chapter vertical padding. |
| 224px | Default major chapter vertical padding and final-call bottom space. |

### Containers and grids

- **main-stage**: max width 1204px · side padding 24px. Centered large product scenes and feature grids; media may overflow the measure and fade at the viewport edges.
- **text-measure**: max width 520px · side padding 16px. Centered short heading-and-support blocks; opening headline uses a closely related 540px measure.
- **footer**: max width 1064px · 6 columns · gap 32px · side padding 24px. Six narrow left-aligned link groups; newsletter sits below across the same measure.
- **feature-grid**: 2 columns · gap 40px. One full-width demonstration above two half-width cards.
- **organization-row** (only for organization landing pages): 2 columns · gap 64px · side padding 32px. Equal-width illustration and text columns, reversing alignment by chapter.
- **pricing-grid** (only for pricing pages): max width 1110px · 3 columns · gap 0px. Joined plan cards with the center card lifted above its neighbors.
- **hardware-stage** (only for hardware landing pages): max width 1000px · side padding 20px. Focused product rows; internal bento uses four tracks and 20px gaps.
- **mobile-grid** (only for mobile-app landing pages): max width 1067px · 2 columns · gap 36px · side padding 24px. Large near-square mobile feature tiles and asymmetric stacked subtiles.
- **faq** (only for FAQ sections): max width 700px · side padding 32px. Narrow centered question list.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-inputs | 8px |
|  | feature-cards | 12px |
|  | navigation | 16px |
|  | large-demo-cards | 30px |
| mobile-app landing pages | mobile-tiles | 20px |
| pricing pages | pricing-cards | 16px |
| pricing and category selectors | segmented-controls | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| key-bevel | `0px 0px 0px 2px rgba(0,0,0,0.5), 0px 0px 14px 0px rgba(255,255,255,0.19), 0px -1px 0.4px 0px rgba(0,0,0,0.2) inset, 0px 1px 0.4px 0px #ffffff inset` | Primary action, with light concentrated close to its face. |
| technical-grid-edge | `0px 0px 0px 1px #1b1c1e, 0px 0px 0px 1px #07080a inset` | Square technical grid cells and comparison-table cells. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark stage.

**CSS:** `background: #07080a; color: #ffffff`

#### Smoked glass · level 1

**Use:** Floating navigation and community cards.

**CSS:** `background: linear-gradient(137deg, rgba(17,18,20,0.75) 4.87%, rgba(12,13,15,0.9) 75.88%); border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; box-shadow: 0px 1px 1px 0px rgba(255,255,255,0.15) inset; backdrop-filter: blur(10px)`

**Observed:** Subtle top-edge illumination rather than a uniformly bright frame. Navigation has its own larger corner treatment.

**Transfer:** Use for compact information floating above colorful art; keep the glass mostly opaque.

#### Feature shell · level 1

**Use:** Wide-and-half product demonstration cards.

**CSS:** `background: linear-gradient(45deg, #0c0d0f 0%, #07080a 100.67%); border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; box-shadow: 0px 1px 0px 0px rgba(255,255,255,0.1) inset; overflow: hidden`

**Observed:** Real interface fragments, sculpted keycaps and colorful backdrops share the shell; content can extend behind its description.

**Transfer:** Use one meaningful product operation per card.

#### Luminous demonstration frame · level 2

**Use:** Main desktop product scene.

**CSS:** `background: radial-gradient(85.77% 49.97% at 51% 5.12%, rgba(255,150,150,0.11) 0%, rgba(222,226,255,0.08) 45.83%, rgba(241,242,255,0.02) 100%), rgba(0,0,0,0.44); border: 1px solid rgba(255,255,255,0.08); border-radius: 19px; padding: 8px; box-shadow: 0px 0px 40px 20px rgba(255,255,255,0.03), 0px 0.5px 0px 0px rgba(255,255,255,0.3) inset; backdrop-filter: blur(2px)`

**Observed:** An outer glass rim surrounds an inner dark window; light pink and icy white remain nearly neutral.

**Transfer:** Frame a functional mockup with a similarly thin luminous rim, not a thick browser chrome.

#### Footer veil · level 1

**Use:** Shared ending beneath the red light motif.

**CSS:** `background: linear-gradient(rgba(7,8,10,0.8) 0.1%, #07080a 32.45%), radial-gradient(49.41% 64.58% at 49.4% 0px, rgba(255,255,255,0.03) 0%, rgba(255,255,255,0) 100%); border-top: 1px solid #1b1c1e; box-shadow: 0px -4px 10px 0px rgba(0,0,0,0.11); backdrop-filter: blur(20px)`

**Observed:** A dark translucent cap cuts across the lower part of the artwork, leaving its bright peaks above the line.

**Transfer:** Carry the opening light motif into this threshold; let the link area settle back into darkness.

#### Technical drawing field · level 1

**Only for:** technical capability chapters

**Use:** Engineering illustrations inside square grid cells.

**CSS:** `background-image: radial-gradient(#2f3031 0.5px, rgba(0,0,0,0) 0px); background-size: 17px 17px; background-position: -8.5px -8.5px; box-shadow: 0px 0px 0px 1px #1b1c1e, 0px 0px 0px 1px #07080a inset; padding: 50px`

**Observed:** The field supports low-contrast wireframes with a single luminous blue plane.

**Transfer:** Give technical ideas a diagrammatic material distinct from polished UI scenes.

## Components

### Floating navigation

**Use:** Persistent global wayfinding.

**CSS:** `max-width: 1204px; padding: 16px 32px; border-radius: 16px; background: linear-gradient(137deg, rgba(17,18,20,0.75) 4.87%, rgba(12,13,15,0.9) 75.88%); border: 1px solid rgba(255,255,255,0.06); box-shadow: 0px 1px 1px 0px rgba(255,255,255,0.15) inset; backdrop-filter: blur(5px); display: flex`

**Text style:** `button` — Inter 500 · 14px/16px · tracking 0.014em

**Observed:** Fixed wrapper sits 16px below the viewport top. The 76px-high island contains identity left, compact links centered, account and a pale action right; it is not an edge-to-edge bar.

### Primary button

**Use:** Download, trial and primary conversion.

**CSS:** `background: #e6e6e6; color: #2f3031; border-radius: 8px; padding: 8px 12px; height: 36px; display: flex; align-items: center; justify-content: center; gap: 8px; box-shadow: 0px 0px 0px 2px rgba(0,0,0,0.5), 0px 0px 14px 0px rgba(255,255,255,0.19), 0px -1px 0.4px 0px rgba(0,0,0,0.2) inset, 0px 1px 0.4px 0px #ffffff inset`

**Text style:** `button` — Inter 500 · 14px/16px · tracking 0.014em

**Observed:** Optional leading platform or action icon; width follows label except full-width plan actions. Mobile store actions use a 48px two-line version.

**States:** Declared: hover background #ffffff; active background #cdcece. The bevel and halo remain.

### Secondary button

**Use:** Video, contact and less-prominent plan actions.

**CSS:** `background: linear-gradient(rgba(255,255,255,0.03) 0%, rgba(255,255,255,0.1) 100%); color: #ffffff; border-radius: 8px; height: 36px; padding: 8px 12px; gap: 8px; box-shadow: 0px 1px 0px 0px rgba(255,255,255,0.05) inset, 0px 0px 0px 1px rgba(255,255,255,0.25), 0px -1px 0px 0px rgba(0,0,0,0.2) inset`

**Text style:** `button` — Inter 500 · 14px/16px · tracking 0.014em

**Observed:** Often pairs with the pale primary action; a small play or contact icon precedes the label.

**States:** Declared: hover outer 1px ring increases to rgba(255,255,255,0.5); active ring reduces to rgba(255,255,255,0.15).

### Utility link

**Use:** Alternate installation method beneath primary actions.

**CSS:** `color: #9c9c9d; border-radius: 4px`

**Text style:** `utility` — GeistMono 400 · 12px/1.6 · tracking 0.017em

**Observed:** Two tiny links share a line beneath platform requirements; they do not compete with the main button.

**States:** Declared: hover color #ffffff; focus-visible box-shadow 0px 0px 0px 2px rgba(255,255,255,0.5).

### Feature card

**Use:** A product behavior explained through a compact scene.

**CSS:** `background: linear-gradient(45deg, #0c0d0f 0%, #07080a 100.67%); border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; box-shadow: 0px 1px 0px 0px rgba(255,255,255,0.1) inset; overflow: hidden`

**Text style:** `body` — Inter 500 · 14px/1.6 · tracking 0.014em

**Observed:** Title with small icon and short description occupies one zone; product media fills the rest. A wide card can span both columns above two smaller cards.

**Transfer:** Show an actual task or result rather than a decorative icon alone.

### Community card

**Use:** Proof of an active ecosystem and onward participation.

**CSS:** `background: linear-gradient(137deg, rgba(17,18,20,0.75) 4.87%, rgba(12,13,15,0.9) 75.88%); border: 1px solid rgba(255,255,255,0.06); border-radius: 12px; padding: 24px; backdrop-filter: blur(10px); box-shadow: 0px 1px 1px 0px rgba(255,255,255,0.15) inset`

**Text style:** `body` — Inter 500 · 14px/1.6 · tracking 0.014em

**Observed:** Icon and title left, tiny monospace metric right, short body below and directional join link at the bottom. A pair sits over subdued red artwork.

**Transfer:** Use a genuine participation destination and a verifiable compact metric.

### Newsletter input

**Use:** Email signup at the bottom of the footer.

**CSS:** `background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.05); border-radius: 8px; padding: 8px 12px; height: 42px`

**Observed:** A 276px-wide email field sits beside a 138px pale submit button, with 16px gap. Small consent copy sits below; the introduction stays in a separate left column.

### Footer columns

**Use:** Useful, dense ending navigation.

**CSS:** `display: grid; grid-template-columns: repeat(6, minmax(144px, 1fr)); gap: 32px; padding-top: 96px; padding-left: 24px; max-width: 1064px`

**Text style:** `body` — Inter 500 · 14px/1.6 · tracking 0.014em

**Observed:** White group headings precede muted link stacks with 20px between links and 40px from heading to stack; small external-link arrows remain subdued.

### Technical tile

**Only for:** technical capability chapters

**Use:** Explain architecture or extensibility through a drawing.

**CSS:** `background-image: radial-gradient(#2f3031 0.5px, rgba(0,0,0,0) 0px); background-size: 17px 17px; background-position: -8.5px -8.5px; padding: 50px; box-shadow: 0px 0px 0px 1px #1b1c1e, 0px 0px 0px 1px #07080a inset`

**Observed:** Square-edged, interconnected cells alternate text and exploded isometric drawings; a tiny figure marker attaches to the upper-left corner.

**Transfer:** Split a process into a few diagrammable parts, with one highlighted plane per drawing.

### Promoted plan

**Only for:** pricing pages

**Use:** Highlight the main paid option without a loud colored fill.

**CSS:** `background: linear-gradient(137deg, #222326 4.87%, #151619 75.88%); border: 1px solid #2f3031; border-radius: 16px; padding: 48px 32px; display: flex; flex-direction: column; gap: 16px; margin-top: -16px; margin-bottom: -16px`

**Text style:** `price` — Inter 600 · 64px/1 · tracking 0.0047em

**Observed:** Raised above joined neighboring plans; title, benefit sentence, pill-shaped tier selector, amount, annual billing detail, full-width pale action, then checkmarked benefits. Outer plans use darker actions. Enterprise uses a broad split panel with a vertical divider and centered custom-pricing area.

### FAQ row

**Only for:** FAQ sections

**Use:** Late-stage objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 32px; padding: 39px 0px; max-width: 700px; color: #ffffff`

**Text style:** `question` — Inter 600 · 16px/1.5

**Observed:** Full-width question trigger with a tiny downward chevron; separators appear extremely subdued. Rows are about 103px high and do not look like individual cards.

### Mobile feature tile

**Only for:** mobile-app landing pages

**Use:** App-level capability and platform-integration demonstrations.

**CSS:** `background: rgba(49,49,49,0.1); border: 1px solid rgba(255,255,255,0.06); border-radius: 20px; padding: 40px; display: flex; flex-direction: column; gap: 8px; backdrop-filter: blur(10px); overflow: hidden`

**Text style:** `body` — Inter 500 · 14px/1.6 · tracking 0.014em

**Observed:** Large interface detail takes the upper portion, fading into the tile before title, description and occasional underlined link. Tiles can nest a short text-only card beside a taller demonstration.

**Transfer:** Keep each tile focused on one platform behavior, with coherent device scale.

## Imagery and graphics

### Diagonal light sculpture

**Use:** Signature opening artwork and a repeated footer threshold motif.

**Observed:** Parallel crimson blades slope from upper left toward lower right. Hard diagonal edges alternate with grainy red light and near-black valleys; fine red and blue edge glints extend beyond the main mass. The opening artwork fills most of the first viewport behind a small centered text block; the footer shows only its peaks.

**Transfer:** Create an original abstract sculpture with the same directional rhythm and lighting. It is required even if the product has no finished media; a clean gradient-and-grain construction is sufficient.

**Build:** On a near-black 1200px-wide stage, layer 5–7 long narrow SVG parallelograms running about 45deg downward right. Vary their lengths and offsets, shade each from black through deep crimson to intense red, and overlap dark triangular occluders. Add a duplicate red layer blurred 18px–32px beneath, thin cool-white edge strokes at low alpha, and a low-opacity SVG turbulence grain mask. Fade all outer edges into the canvas. Reuse a smaller, darker portion behind the footer veil.

### Desktop interface theatre

**Use:** Primary proof scene and selected feature cards.

**Observed:** Large dark application windows float above subdued red or blue light with a thin glowing rim. The first scene suggests a desktop within a glass frame; feature scenes often omit desktop chrome and dissolve into black at the bottom. Media has much more area than its introductory text.

**Transfer:** Stage one meaningful task in a legible product mockup; if a real interface is unavailable, construct a coherent two-pane task view rather than filling panels with arbitrary controls.

**Build:** Layer a soft red or cool-blue radial glow under a dark rounded window, then add a 1px white-alpha outline, a half-pixel inset highlight and a broad low-alpha white halo. Use an opaque-to-transparent black gradient over the lower edge to blend the scene with its card.

### Colored capability cards

**Use:** Horizontal catalog of related tools or integrations.

**Observed:** Tall 360px by 536px cards use deep violet, blue or green interiors, small app identity and explanatory text at the top, with a large cropped visual below. The row extends beyond the viewport and fades at the right edge.

**Transfer:** Assign color to the content's ecosystem or function while keeping it contained inside the cards. Use a cropped artifact, content sample or small task scene instead of a generic illustration.

**Build:** Give each rounded card a dark radial color pool, low-alpha white inset outline, soft top highlight and dark edge vignette. Keep the surrounding page near-black and the text white.

### Closing keyboard field

**Use:** Large atmospheric prelude to the default final invitation.

**Observed:** An oversized key field extends beyond the viewport, masked so its keys emerge only in a central pool of light, with the subsequent invitation and small action stack centered below.

**Transfer:** Use the new product's repeated functional units as a dark oversized field; for non-keyboard products use original tiles, modules or workflow cells rather than literal keyboard keys.

**Build:** Repeat dark bevelled rectangular units in an SVG grid wider than the viewport, then apply an elliptical radial mask strongest near the lower center. Illuminate a small central cluster in muted red and fade the remainder into near-black.

### Engineering drawings

**Only for:** technical capability chapters

**Use:** Technical capability grid.

**Observed:** Low-contrast isometric outlines on a fine dotted field, with a single blue-lit layer or part. Exploded interfaces, objects and components are labeled like a small technical plate; tiny figure numbers anchor the corners.

**Transfer:** Use original wireframe diagrams of the new product's system, with an isolated highlighted part rather than glossy decorative objects.

**Build:** Use SVG paths with thin charcoal strokes to draw offset isometric planes, connected by vertical construction lines. Fill one plane in translucent blue, brighten its active strip, and place small monospace labels with leader lines. Back with the Technical drawing field.

### Orbital organization scene

**Only for:** organization landing pages

**Use:** Organization opening and connective process illustrations.

**Observed:** Small circular portraits and glass feature icons trace faint dotted rings around centered text. A diffuse blue-to-teal cloud illuminates the middle; objects remain peripheral and leave a clear text well.

**Transfer:** Orbit genuine participant or workflow symbols around the promise; do not turn the motif into a busy network map.

**Build:** Draw 3 concentric dotted SVG circles around a centered 520px text area; distribute small circular nodes on their paths. Put blurred blue and teal ellipses behind them and fade the rings toward the edges.

### Hardware studio scenes

**Only for:** hardware landing pages

**Use:** Physical-product openings, detail bento and specification closing.

**Observed:** Black hardware emerges from black space with raking highlights, selective red controls and macro views of machined edges. A ring of floating keycaps and an exploded switch show physical construction; the closing returns to a broad low-angle product silhouette above specifications.

**Transfer:** Render the new object with low-key studio lighting, material detail and one selective color accent. If full 3D is unavailable, use sharply lit photography on black and a simple exploded vector diagram for construction.

### Mobile glass and photography

**Only for:** mobile-app landing pages

**Use:** Mobile-app openings and capability chapters.

**Observed:** A tilted dark phone rises above the headline with a warm red rim and a luminous app icon. Later scenes alternate upright phones, extreme-perspective translucent UI planes and a monochrome hand holding a phone. Red glow recurs behind widgets while platform UI stays recognizable.

**Transfer:** Use coherent original app screens on one device family; combine a hero device render, a few planar UI details and one human-scale monochrome image.

**Build:** For the hero, place a tilted dark device over two blurred red ellipses, add a narrow warm edge-light and a small icon halo. For planar scenes, stack 2–3 translucent rounded rectangles in perspective and fade the far edge into black.

### Icons

**Observed:** Most small outline icons are 16px or 24px with 1.5px round strokes; 10px external arrows are exceptionally discreet. Filled platform symbols accompany actions; pricing checks can use 2px strokes.

**Transfer:** Choose a consistent rounded outline set, inherit text color and keep icons subordinate to the label. Use filled icons only for platform or content identity.

## Section recipes

How recurring sections are built.

### First screen: Light sculpture opening

**Observed:** Canvas behind a fixed Floating navigation island; an approximately 1200px-wide diagonal light sculpture fills the center and recedes into black at the sides. In front, a centered 540px-wide two-line display headline occupies the middle of the screen, with hero-support 32px below. Artwork remains visible both above and below the type. A small Primary button is separated from the support by a dramatic 212px interval, followed by Utility text and links. Within the first 900px the navigation, artwork, full headline, support, button and requirements are visible; a small announcement pill and the next chapter fall below. The headline begins well below the navigation, not directly under it.

**Transfer:** Preserve the small centered promise against oversized directional light, even without source-quality 3D: build the Diagonal light sculpture and place an original functional motif behind the copy. Organization openings instead put a 72px headline inside an orbital scene; hardware puts the 50px headline and actions above a wide low-key object; mobile puts the device above a 48px headline. Pricing opens directly on a billing toggle and joined plans.

**Avoid:** Do not substitute a left-copy/right-dashboard split, a huge full-width headline, or an immediate button tucked directly below the support; those remove the theatrical pause.

**Text style:** `display` — Inter 600 · 64px/1.1

### Compact heading pair

**Observed:** A white section-pair line directly above a gray line in the same recipe; no oversized title. Usually centered, with 48px–64px before the demonstration and generous 224px chapter padding.

**Transfer:** Write one concise promise and one clarifying line, then let the media explain the mechanism.

**Text style:** `body` — Inter 500 · 14px/1.6 · tracking 0.014em

### Wide-and-half capability stage

**Observed:** Feature card spans a two-column 1204px stage, followed by two half-width cards with 40px gaps. Some scenes place text beside media, others put an interface above a lower description.

**Transfer:** Group related benefits by how they are demonstrated, varying one wide scene with smaller focused behaviors.

### Selectable capability paragraph

**Observed:** A 400px measure of 24px capability-wall text sits left of a framed product scene. Most phrases are #434345; the selected phrase is white. A small descriptive caption and tag sit below, separated by 80px from the text wall.

**Transfer:** Use a readable paragraph of short capabilities as navigation for a corresponding preview; keep only one capability visually selected.

**Text style:** `capability-wall` — Inter 500 · 24px/1.6 · tracking 0.0083em

### Professional proof selector

**Observed:** Compact heading pair over a row of portrait/name selectors; the active selector has smoked glass and a faint glow, while adjacent choices recede. Below a thin line, small favorite-feature details occupy one column and a 20px quote another, with selected words white and the rest gray.

**Transfer:** Show a real person's particular workflow and a specific quote, not only a logo wall.

### Closing invitation

**Observed:** Closing keyboard field gives way to a compact centered heading pair, then 80px before the main action, 16px before requirements and 8px before alternate links. The block has 224px bottom space. Organization pages use a bolder 36px invitation, softly multicolored action halo and command-line alternative before community cards.

**Transfer:** Restate the benefit in a short imperative; retain the enormous dark breathing room and one clear conversion rather than a full-width colored banner.

### Art threshold footer

**Observed:** Red diagonal peaks rise above Footer veil. Six Footer columns begin 96px inside the panel. A separate Newsletter input row is divided by a #1b1c1e hairline, with introduction left and form right; the final page content is the form's small consent copy, not a second sales headline.

**Transfer:** Keep the opening motif and a substantial useful navigation ending. Scale the number of destinations to the product without replacing the ending with an unrelated bright band.

### Technical plate chapter

**Only for:** technical capability chapters

**Observed:** A square-edged three-track grid of 355px columns with 1px joints extends into outer gutters. A narrow technical-display block sits beside a double-width diagram. Subsequent rows alternate drawings and concise technical-copy, using Technical tile and Technical drawing field.

**Transfer:** Use this distinct visual dialect when explaining how the system is built or extended; a compact version can preserve the same diagrams, mono copy and figure labels.

**Text style:** `technical-display` — Inter 400 · 56px/1.17 · tracking 0.0036em

### Upgrade light chapter

**Only for:** upgrade promotions

**Observed:** Centered 52px upgrade-display splits a word so one repeated syllable glows pink. A small tinted announcement pill precedes a large luminous pink product composition and three compact feature cards.

**Transfer:** Make a short, comprehensible verbal hinge between basic and advanced capability; reserve the rose glow for this promotion.

**Text style:** `upgrade-display` — Inter 600 · 52px/1.1

### Decision and comparison

**Only for:** pricing pages

**Observed:** Billing toggle above three joined plans, promoted center card raised 16px. Enterprise follows in a broad split panel. A six-column ruled comparison matrix uses 24px by 16px cell padding, small labels and simple checks rather than colorful category cards.

**Transfer:** Separate quick choice from exhaustive comparison, preserving the same tier names and aligned actions throughout.

**Text style:** `price` — Inter 600 · 64px/1 · tracking 0.0047em

### Hardware feature and specification ending

**Only for:** hardware landing pages

**Observed:** Alternating object/detail rows use hardware-heading with a white clause and dimmed gray clause. A four-track 20px-gap bento mixes macro photography, line diagrams, small glass captions and a 30px number with equally sized dim unit. Closing returns to centered 32px copy, a purchase-state button and a wide low-angle product image, then two columns of thin-rule specifications and uppercase mono labels.

**Transfer:** Explain tactile qualities with detail imagery before presenting a restrained, useful specification inventory.

**Text style:** `hardware-heading` — Inter 500 · 32px/1.25 · tracking -0.0125em

### Mobile capability chapter

**Only for:** mobile-app landing pages

**Observed:** mobile-eyebrow, mobile-heading and mobile-support lead device scenes with 168px vertical padding. Large two-column Mobile feature tiles alternate with borderless planar UI and monochrome device-in-hand media. A final centered heading pair leads to a small framed QR code, caption and platform requirement; FAQ follows.

**Transfer:** Alternate platform utility closeups with device-scale views, then offer an appropriate cross-device acquisition mechanism.

**Text style:** `mobile-heading` — Inter 500 · 32px/1.6 · tracking 0.0063em

## Page flow

**Storyline:** Promise → immersive demonstration → focused capability chapters → human or ecosystem proof → deeper detail or decision support → compact final invitation → art-linked utility footer.

### Broad product introduction

1. **promise** — Centered headline over red directional light.
2. **product demonstration** — Large luminous desktop frame and keyboard-first scene.
3. **capability chapters** — Colored tool catalog, main agent demonstration and automation cards.
4. **social proof** — Selectable people with specific workflow quotes.
5. **ecosystem proof** — Capability text wall, community cards and media strip.
6. **technical depth** — Square grid with figure labels and blue exploded drawings.
7. **closing call** — Oversized masked key field, small invitation and download stack.
8. **utility ending** — Red-art threshold, six-column links and newsletter form.

**Transfer:** Keep the light-led first impression, varied product staging and art-linked ending; choose only chapters that advance the new product's argument.

### Organization adoption

1. **promise** — Orbital portrait and icon scene around a blue-white headline.
2. **social proof** — Muted trusted-company marks.
3. **capability chapters** — Alternating illustrated process rows, vivid blue-violet demonstration, then shared-workflow scenes.
4. **upgrade value** — Pink illuminated wordplay chapter and feature trio.
5. **pricing** — Two plan cards, billing control and enterprise split panel.
6. **implementation support** — Three template previews and a compact action.
7. **closing call** — Centered take-off invitation, luminous action and command alternative.
8. **utility ending** — Community cards followed by the shared art threshold and newsletter footer.

**Transfer:** Move from shared outcomes to implementation confidence and purchase choice, using the orbital opening only for collective workflows.

### Plan selection and comparison

1. **decision** — Billing control and raised-middle three-plan composition under a red-art fragment.
2. **enterprise option** — Broad split panel separates security detail from custom-pricing contact.
3. **comparison** — Dense hairline matrix with checkmarks and repeated bottom actions.
4. **objection handling** — Narrow FAQ rows.
5. **utility ending** — Shared red peaks, link columns and newsletter.

**Transfer:** Begin with useful decision tools, not a generic hero headline, and let detail grow denser below.

### Physical product launch

1. **promise** — Restrained centered title above dramatic low-key hardware.
2. **construction proof** — Floating part ring, exploded mechanism, specification snippets and sound preview.
3. **capability chapters** — Macro-detail bento with glass captions and small statistic.
4. **closing call** — Centered final headline, purchase state and broad side-view object.
5. **technical detail** — Uppercase mono specification tables and discreet design credit.
6. **utility ending** — Shared red-art threshold, links and newsletter.

**Transfer:** Use material and engineering proof instead of software-style feature screenshots; keep availability states truthful.

### Companion mobile-app adoption

1. **promise** — Red-rimmed phone above two-line headline and paired store/video actions.
2. **product demonstration** — Upright phone with floating content, followed by perspective glass planes.
3. **capability chapters** — App-feature tile groups, monochrome device-in-hand image and system-integration tiles.
4. **closing call** — Compact heading pair with framed QR download and requirement.
5. **objection handling** — Four narrow FAQ rows.
6. **utility ending** — Shared art-linked footer and newsletter.

**Transfer:** Show both the app's own workspace and how it participates in the operating system, maintaining the dark theatre.

## Writing

Confident, practical and lightly playful. Technical capability is translated into everyday relief, with occasional short wordplay rather than inflated futurism.

**Do not copy:** Do not reuse Raycast names, marks, proprietary artwork, customer identities, quotes, membership counts, prices, performance claims, compatibility claims or availability states. Source copy examples illustrate cadence only; write original claims grounded in the new product.

- **Addressing the reader:** Speak directly to you and your team; use we or our when discussing the product's craft or implementation.
- **Rhythm:** Short sentence-case headlines, often with a full stop; compact explanatory sentences underneath. Contrasts, parallel clauses and question-and-answer constructions keep technical material approachable.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A possessive benefit with broad scope. | 4–7 words | “Your shortcut to everything.”<br>“Your team, reimagined.” |
| Section heading pair | Short confident assertion followed by a clarifying outcome. | 4–9 words per line | “Take shortcuts, not detours.”<br>“One interface, everything you need.” |
| Feature explanation | Recognizable friction, then a concrete mechanism. | 1–3 short sentences | “Tired of typing the same thing? Create a snippet and insert it by simply typing its keyword.” |
| Physical quality | Two terse complementary clauses. | 2–4 words per clause | “Quiet by design.”<br>“Mechanical feel.” |
| Action | Plain verb, sometimes including destination or platform. | 1–4 words | “Download for Mac”<br>“Get started today”<br>“Watch video” |
| Closing invitation | Return to the promise in a small imperative. | 4–8 words | “Take the short way.”<br>“Be more productive today and everyday.” |

**Words and phrasing to use:** shortcut; your tools; without leaving; make it yours; ready to reuse; get started; one interface; built-in

**Avoid:** revolutionary; unparalleled; disruptive; next-generation everything; effortlessly unlock limitless potential

**Rules:**

- Give each chapter one human outcome, then explain the specific operation that delivers it.
- Use technical nouns when they identify a real capability; pair them with familiar verbs.
- Keep button labels literal even when adjacent headlines are playful.
- Let one small joke or verbal contrast carry a chapter; avoid piling puns into paragraphs.
- Keep requirements, billing details and compatibility in compact factual supporting copy.

## Do's and Don'ts

### Do

- Keep the default opening headline at 64px/1.1, weight 600, with a narrow two-line measure.
- Maintain #07080a between scenes so the light sculpture and product media feel continuous.
- Use 36px-high, 8px-radius beveled actions instead of oversized conversion controls.
- Place 20px white and gray heading lines directly together before large demonstrations.
- Give default feature cards 12px corners, 1px faint white edges and 40px grid gaps.
- Preserve the 17px dotted field and square joints when using the technical drawing chapter.
- Carry diagonal red light into the footer threshold and leave the newsletter as the final useful interaction.
- Keep mobile-app tile padding at 40px and technical specification labels at 12px monospace in their respective variants.

### Don't

- Do not use red as the default button fill; the primary face is pale gray.
- Do not make every chapter a 48px or 64px headline; most default section titles are only 20px.
- Do not give all cards the 30px radius of the large demonstration shell; ordinary feature cards use 12px.
- Do not turn muted #434345 capability phrases into equally bright navigation choices.
- Do not apply the 72px bold organization headline to an ordinary product landing page.
- Do not carry blue pricing checks or rose upgrade wordplay across every section as general decoration.
- Do not replace thin glass edge highlights with thick white borders and opaque light panels.
- Do not enlarge 30px hardware statistics into dashboard-style monumental metrics or put them on bright accent cards.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-image and background-color transitions of 0.2s, box-shadow 0.2s ease-in-out and transform 0.1s ease-in-out.
- Footer links declare color 0.3s; navigation links declare 0.2s ease-in-out.
- Organization orbit layers declare 180s linear infinite rotation with compensating rotation on their contents.
- Hardware opening elements declare 0.6s ease-out entry with sibling-index stagger.

**Transfer:**

- Keep utility control feedback short and surface-based; use slow rotation only for the scoped orbital scene.
- Preserve counter-rotation so orbital portraits and symbols stay upright.

**Unknown:**

- Complete scroll choreography, interactive demo playback and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 640px, 768px, 900px, 1024px, 1064px and 1200px; distinct component rules use additional thresholds.

**Transfer:**

- As a design adaptation, retain a centered light sculpture and readable narrow headline before stacking media; do not shrink the whole desktop scene uniformly.
- Stack wide-and-half cards and alternating feature rows into a single reading column; keep diagram figure labels and the footer's art threshold.
- Let comparison data scroll horizontally rather than squeezing six columns into unreadable labels.

**Unknown:**

- Exact narrow-screen typography, navigation conversion and footer column behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
