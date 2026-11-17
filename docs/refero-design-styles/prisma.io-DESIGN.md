# Prisma — spectrum-lit workbench

## Overview

A bright technical style with the optimism of refracted light and the practicality of a developer workbench. Geometric sans headlines sit above fine, understated interface text; cyan, yellow and rose travel through an otherwise white and charcoal world. Frosted panels, metallic glass objects, softly textured landscapes and real interface scenes give complex products a tangible presence. The pacing is spacious, while individual cards and comparison tables remain information-rich.

### Essentials

- Headlines are broad, friendly geometry rather than heavy slogans: Sora 500, 62px/1.06 for the opening, 48px/1.1 for major chapters, normal tracking and balanced two-line wraps.
- The opening is a luminous workbench: a 24px-radius inset stage with 16px outer gutters, centered 896px headline region, 18px supporting text and a 896px-wide interface emerging from below the text.
- Actions are black capsules with spectral edges: 48px tall, 12px 24px padding, Inter 16px/24px at 600; pair with a transparent 1px gray-outline capsule separated by 16px.
- Color behaves like light, not paint: white dominates reading areas; cyan #01d7e4, yellow #f3c306 and rose #f34a60 collect behind objects, in thin edges and 8px status dots. Keep long copy charcoal or muted gray.
- Make the spectrum physically travel: use a continuous cyan–yellow–rose three-band ray behind a product scene and through a monumental closing word sculpture. Use a simplified white interface panel and an outlined glass object when custom 3D media is unavailable.
- Close with luminous depth and oversized identity: a 24px-radius atmospheric frame contains a 14px-radius frosted conversion panel; the final white footer ends in a near-full-width black word sculpture crossed by the same colored ray.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Prism cyan | `#01d7e4` | `--color-cyan` | accent | First band of the spectral ray, light fields and status dots. |
| Prism yellow | `#f3c306` | `--color-yellow` | accent | Middle ray band, warm glows and small marks. |
| Prism rose | `#f34a60` | `--color-rose` | accent | Last ray band, small marks and warm light fields. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Spectrum orange | `#f37a03` | `--color-orange` | accent | Intermediate stop in moving action halos and thin spectrum edges. |
| Spectrum red | `#f43531` | `--color-red` | accent | Intermediate stop in action halos, not a broad background. |
| Spectrum pink | `#f00e5c` | `--color-pink` | accent | Terminal warm stop in action halos. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Dominant page canvas, cards and text on black actions. |
| Warm paper | `#f9faf5` | `--color-paper` | surface, text | Compact navigation action text; warm panels and highlighted columns on pricing pages. |
| Cool card wash | `#f4f7f7` | `--color-wash` | surface | Muted supporting bands and media backings. |
| White-canvas hairline | `#f0f0f0` | `--color-edge` | border | Visible result of black at 6% over white, used around cards and stages. |
| Panel rule | `#e5e5e5` | `--color-rule` | border | Fine dividers and interface panel edges; also used with 70% or 80% opacity. |
| Muted gray | `#646567` | `--color-muted` | text, border | Paragraphs, navigation links, metadata and secondary button outlines. |
| Reading charcoal | `#3a3b3c` | `--color-foreground` | text, link | Emphasized body text, quotations and secondary action labels. |
| Headline charcoal | `#151515` | `--color-ink` | text, action | Headlines and compact navigation actions. |
| Action black | `#000000` | `--color-black` | action, text | Primary conversion capsule and monumental footer lettering. |

## Typography

- **Sora** — Display, section and card headings, prices and footer column labels. Geometric sans with rounded bowls, open counters and distinctive wide lowercase forms. Font stack: "Sora", sans-serif.
- **Inter** — Body copy, navigation, actions, captions and interface text. Neutral sans with an unusually light 380 body weight and crisp semibold labels. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Sora | 500 | 62px | 1.06 | normal | size clamp(2.5rem, 4.5vw, 3.875rem) | Default marketing opening, balanced over two lines. |
| heading-lg | Sora | 500 | 48px | 1.1 | normal | size clamp(2.125rem, 3.5vw, 3rem) | Major narrative chapters. |
| closing-heading | Sora | 500 | 44px | 1.08 | normal | size clamp(2rem, 3.2vw, 2.75rem) | Centered conversion panel heading. |
| heading | Sora | 500 | 38px | 1.1 | normal | size clamp(1.75rem, 2.75vw, 2.375rem) | Proof sections, shorter information headings and secondary chapters. |
| feature-heading | Sora | 500 | 24px | 32px | normal | fixed | Product rows and featured editorial cards. |
| card-heading | Sora | 500 | 20px | 1.4 | normal | fixed | Step titles, benefit headings and story cards. |
| lead | Inter | 380 | 18px | 1.625 | normal | fixed | Centered opening and chapter support paragraphs. |
| body | Inter | 380 | 16px | 1.625 | normal | fixed | Explanations, closing support and FAQ answers. |
| action | Inter | 600 | 16px | 1.5 | normal | fixed | Full-size action labels. |
| question | Sora | 500 | 16px | 1.5 | normal | fixed | FAQ question buttons. |
| body-small | Inter | 380 | 15px | 1.625 | normal | fixed | Feature descriptions and benefit lists. |
| quote | Inter | 500 | 15px | 1.5 | normal | fixed | Compact testimonial statements. |
| label | Inter | 600 | 14px | 20px | normal | fixed | Sentence-case dot eyebrows, names and compact actions. |
| caption | Inter | 380 | 14px | 20px | normal | fixed | Metadata and footer links. |
| navigation | Inter | 500 | 14px | 20px | normal | fixed | Main navigation links. |
| footer-heading | Sora | 500 | 14px | 20px | normal | fixed | Footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company, recruiting and customer-story index openings | editorial-display | Sora | 500 | 56px | 1.06 | normal | size clamp(2.5rem, 4vw, 3.5rem) | Compact centered opening without a large product demonstration. |
| pricing pages | pricing-display | Sora | 500 | 49px | 1.06 | normal | size clamp(2.25rem, 3.4vw, 3.125rem) | Left-aligned explanatory opening above plan cards. |
| pricing pages | price | Sora | 500 | 36px | 40px | -0.025em | fixed | Plan prices with a smaller monthly suffix. |
| recruiting pages | stat | Sora | 600 | 36px | 40px | normal | fixed | Three equal headline statistics above small labels. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Most typography keeps normal tracking, including the largest headlines. Negative tracking belongs to prices, not to the entire heading scale.
- Use Sora 500 rather than bold for display hierarchy; body copy is Inter 380, with 600 emphasis and labels.
- Headlines balance into compact blocks; major centered headings use about 24 characters of width per line, while the default opening uses about 20.

## Layout

**Density:** Airy between chapters, compact within tools and proof cards; large white pauses make the luminous scenes feel like deliberate exhibits.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Dot-to-label gaps and small metadata relationships. |
| 12px | Feature list gaps, card text separation and footer link rhythm. |
| 16px | Action pair gaps, testimonial gaps and photographic gutters. |
| 20px | Three-column marketing card gutters and body-to-heading separation. |
| 24px | Default card padding and lead paragraph top margin. |
| 28px | Pricing and editorial information card padding. |
| 32px | Desktop side gutters and closing-frame inset. |
| 36px | Product feature-row text padding. |
| 40px | Opening action top margin and footer side gutters. |
| 56px | Opening proof-to-demo separation and testimonial heading-to-rail gap. |
| 64px | Section heading-to-grid separation and footer top padding. |
| 80px | Photographic gallery vertical padding and closing-panel vertical padding. |
| 96px | Secondary section and FAQ vertical padding. |
| 128px | Main narrative section vertical padding. |
| 144px | Default opening text top padding inside its stage. |

### Containers and grids

- **content**: max width 1400px · side padding 32px. Centered marketing content; at 1440px the usable span is 1376px.
- **stage**: max width 1536px · side padding 16px. Near-edge hero and closing atmospheric frames.
- **opening-column**: max width 896px. Centered opening heading and main interface; paragraph narrows to 724px.
- **reading-column**: max width 768px. FAQ and long comparison-resource lists.
- **marketing-grid**: 3 columns · gap 20px. Equal-width step, benefit and story cards.
- **feature-row**: 2 columns · gap 0px. Equal text and media halves inside one bordered card; alternate the media side.
- **footer-columns**: 5 columns · gap 32px. Five link columns beside a separate identity/contact area; identity and links use an 80px gap.
- **plan-grid** (only for pricing pages): 4 columns · gap 24px. Equal desktop plans with aligned content and full-width actions.
- **photo-grid** (only for company and recruiting pages): 3 columns · gap 16px. Two rows of 4:3 documentary photographs.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | stage | 24px |
|  | cards | 18px |
|  | glass-panel | 14px |
| product demonstrations | small-interface-panels | 10px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| fine-card | `0px 1px 2px 0px rgba(21,21,21,0.04)` | Editorial and informational cards. |
| glass-lift | `0px 12px 32px -14px rgba(21,21,21,0.18)` | Frosted closing panel and demonstration windows. |
| navigation-lift | `0px 1px 2px 0px rgba(21,21,21,0.02), 0px 8px 24px -8px rgba(21,21,21,0.08)` | Floating navigation capsule. |

### Surfaces

#### Canvas · level 0

**Use:** Default background.

**CSS:** `background: #ffffff; color: #3a3b3c`

**Observed:** Long white reading fields separate luminous exhibits.

**Transfer:** Keep the ordinary reading canvas white rather than tinting every section.

#### Hairline card · level 1

**Use:** Steps, testimonials, product rows and editorial cards.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 18px`

**Observed:** Very faint edges define content without making a heavy dashboard grid.

**Transfer:** Use borders before shadows; reserve depth for media and selected cards.

#### Atmospheric stage · level 0

**Use:** Opening, grouped capability scenes and conversion calls.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 24px; overflow: hidden`

**Observed:** Pale cloudy mineral texture, refracted cyan/yellow/rose light and translucent outlined geometry sit behind readable foreground panels.

**Transfer:** Use the spectral atmosphere recipe; keep the center pale enough for charcoal text.

#### Frosted conversion panel · level 2

**Use:** Inner panel of the luminous conversion frame.

**CSS:** `background: rgba(255,255,255,0.7); border: 1px solid #e5e5e5; border-radius: 14px; backdrop-filter: blur(16px); box-shadow: 0px 12px 32px -14px rgba(21,21,21,0.18)`

**Observed:** Light passes through the entire panel rather than collecting only around a card shadow.

**Transfer:** Place over atmosphere, not a flat saturated rectangle.

#### Cool supporting band · level 1

**Use:** Secondary information groups.

**CSS:** `background: #f4f7f7; border-radius: 18px`

**Observed:** Very low-contrast wash with dark sentence-case text and small colored marks.

**Transfer:** Use as a calm compact counterpoint to the more dimensional media.

#### Pricing paper · level 1

**Only for:** pricing pages

**Use:** Calculator panels and recommended comparison-table column.

**CSS:** `background: #f9faf5; border: 1px solid rgba(0,0,0,0.06); border-radius: 18px`

**Observed:** Barely warm off-white distinguishes editable or emphasized regions.

**Transfer:** Keep the warmth subtle; the preferred plan gains a spectrum edge, not a saturated fill.

## Components

### Floating navigation

**Use:** Persistent site navigation.

**CSS:** `display: flex; align-items: center; justify-content: space-between; height: 64px; max-width: 1220px; padding: 0px 42.3px; border-radius: 9999px; background: rgba(255,255,255,0.419); border: 1px solid rgba(0,0,0,0.03); backdrop-filter: blur(5.9px); box-shadow: 0px 1px 2px rgba(21,21,21,0.02), 0px 8px 24px -8px rgba(21,21,21,0.08)`

**Text style:** `navigation` — Inter 500 · 14px/20px

**Observed:** Identity left, restrained links in the middle, search, login and compact black action right. It visually contracts into a narrower floating capsule on scroll; its starting treatment is less prominent against the opening stage.

**Transfer:** Keep the middle links few and retain clear separation of browsing and conversion.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 12px 24px; background: #000000; color: #ffffff; border-radius: 9999px`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** Black capsule has a thin luminous spectrum halo outside its edge, built as a separate blurred layer so the label stays crisp.

**Transfer:** Use a verb-led label and the same halo, regardless of product category.

### Secondary button

**Use:** Alternative next step beside the primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 11px 22px; background: transparent; color: #3a3b3c; border: 1px solid #646567; border-radius: 9999px`

**Text style:** `action` — Inter 600 · 16px/1.5

**Observed:** No fill; a masked spectrum ring replaces the ordinary outline during interaction.

**States:** Declared: hover border-color rgba(0,0,0,0); transition color and border-color 0.5s cubic-bezier(.4,0,.2,1).

### Compact navigation action

**Use:** Conversion button within navigation.

**CSS:** `height: 36px; padding: 8px 16px; background: #151515; color: #f9faf5; border-radius: 9999px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `label` — Inter 600 · 14px/20px

**Observed:** Smaller and less luminous than the main conversion capsule.

**States:** Declared: hover scale 1.04; focus-visible border-color lab(36.2% 0 .00000596046).

### Step card

**Use:** Explain a short process visually.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 18px; overflow: hidden`

**Text style:** `card-heading` — Sora 500 · 20px/1.4

**Observed:** A 208px-high tinted illustration area sits over a 24px-padded text area. Small number badge, title and short paragraph form the lower half. Successive illustrations use pale cyan, pale yellow and pale rose.

**Transfer:** Show meaningful changes to a single task, not three unrelated stock icons.

### Testimonial card

**Use:** Dense social proof on horizontal rails.

**CSS:** `display: flex; flex-direction: column; width: 352px; padding: 24px; background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 18px`

**Text style:** `quote` — Inter 500 · 15px/1.5

**Observed:** Quote above a bottom-aligned attribution row with small logo or avatar, semibold name and lighter role. Two horizontal rows use 16px gaps and white fades at the rail ends.

**Transfer:** Use concise attributable statements so several cards can remain visible at once.

### FAQ row

**Use:** Objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; padding: 16px 0px; gap: 16px; color: #151515; background: transparent; border-radius: 8px`

**Text style:** `question` — Sora 500 · 16px/1.5

**Observed:** Text question and 16px chevron sit on a full-width button. The wrapper supplies a fine bottom rule; open answer uses body typography below. First answer is expanded in the initial view.

**Transfer:** Keep the question a real customer concern, and answer directly before qualifying.

### Footer link

**Use:** Compact footer navigation.

**CSS:** `display: block; color: #646567; line-height: 20px`

**Text style:** `caption` — Inter 380 · 14px/20px

**Observed:** Grouped beneath Sora footer-heading labels; 12px vertical separation, no oversized rounded link tiles.

**States:** Declared: hover color #3a3b3c.

### Story card

**Only for:** customer-story indexes

**Use:** Editorial proof library.

**CSS:** `display: flex; flex-direction: column; overflow: hidden; background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 18px; box-shadow: 0px 1px 2px rgba(21,21,21,0.04)`

**Text style:** `card-heading` — Sora 500 · 20px/1.4

**Observed:** Media first, then a small organization label, outcome-focused heading, muted summary and arrow link. One featured card spans two columns and uses the feature-heading recipe; regular cards use a 16:9 media area.

**States:** Declared: hover border-color color-mix(in oklab, #000 12%, transparent); translate 0 0; transition border-color, box-shadow, translate 0.3s cubic-bezier(.4,0,.2,1).

### Plan card

**Only for:** pricing pages

**Use:** Compare commercial options.

**CSS:** `display: flex; flex-direction: column; padding: 28px; background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 18px`

**Text style:** `price` — Sora 500 · 36px/40px · tracking -0.025em

**Observed:** Plan name, price with smaller suffix, product-group labels, checkmarked allowance lists and bottom action. Recommended plan is white with a spectrum outline, a small top badge and a lifted shadow; only its main action is black.

### Usage preset

**Only for:** pricing pages

**Use:** Choose a calculator scenario.

**CSS:** `display: flex; align-items: baseline; justify-content: space-between; gap: 12px; padding: 12px 16px; background: #ffffff; border: 1px solid #151515; border-radius: 14px`

**Text style:** `label` — Inter 600 · 14px/20px

**Observed:** Selected preset has a dark outline; inactive options use Pricing paper and a faint edge. Scenario name aligns left and smaller usage summary aligns right.

## Imagery and graphics

### Spectral atmosphere

**Use:** Signature backing for opening, capability exhibits and conversion panels.

**Observed:** Pale chalky cloud or stone texture with broad cyan light at the lower left, warm yellow near the center and rose at the right. Faint translucent cuboids occupy outer corners; white veils keep the text center almost neutral.

**Transfer:** Recreate the light and material rather than a flat rainbow wallpaper. Keep texture fine and low contrast.

**Build:** Layer three oversized elliptical radial gradients behind white: cyan rgba(1,215,228,0.34), yellow rgba(243,195,6,0.24), rose rgba(243,74,96,0.3), centered near 26%, 52% and 78% along the lower edge. Blur independent light blobs by 56px–96px; overlay a low-opacity SVG fractal-noise texture and a white top fade. Draw corner cuboids in SVG with white strokes and translucent white faces. Keep their scale subordinate to the heading.

### Three-band ray

**Use:** Signature continuous path through the product stage and closing identity artwork.

**Observed:** Three crisp parallel cyan, yellow and rose bands rise diagonally from left to right, partially hidden by the foreground interface or masked inside large lettering. Edges are lightly softened rather than neon outlines.

**Transfer:** Carry the same ray across a meaningful new product object and through the closing word sculpture.

**Build:** Create a 96px-high strip with linear-gradient(#01d7e4 0% 33%, #f3c306 33% 66%, #f34a60 66% 100%); make it wider than its stage, rotate about -16deg and place behind the white interface. Apply 0.5px blur and 0.85 opacity. For the footer, use an SVG text mask or background-clip:text to confine the strip to bold black letterforms.

### Product tableaux

**Use:** Opening demo and alternating capability rows.

**Observed:** White browser or console windows float over softly colored photographic landscapes. Stacked glass plates, a metallic cylinder and a gold-edged chip carry cyan/yellow/rose reflections. The media occupies about half a feature row; the opening window is much wider than its supporting copy.

**Transfer:** Use a real task interface plus one simple physical metaphor: layered sheets, a rounded cylinder or a beveled tile. Minimum version is an SVG glass tile with fine rim highlights, a colored ray and a legible white UI panel; avoid an unrelated stock render.

**Build:** Construct a white 18px-radius interface with a thin gray edge and soft downward shadow. Behind or beside it, layer rounded rectangles in perspective with translucent white faces, gold-toned rim lighting and the three-band ray clipped across each face. Use a low-contrast landscape or pale noise-backed gradient outside the panel; do not make the marketing copy look like code.

### Action halo

**Use:** Main capsules and selected comparison cards.

**Observed:** Thin rainbow light hugs black actions and outlines preferred white cards; it is not a large colored button fill.

**Transfer:** Keep the halo outside the content and leave the interior solid.

**Build:** Use a separate absolutely positioned rounded layer with an 85deg gradient through cyan, yellow, orange, red and pink. For capsules blur by 3.2px beneath the black face; for selected cards use a 1px padded masked gradient ring and a broader 18px-blurred copy at 0.2 opacity.

### Closing word sculpture

**Use:** Final identity gesture below footer navigation.

**Observed:** Very large black lettering nearly spans the page and can extend beyond the right edge. The diagonal spectral ray is clipped inside the letterforms; white negative space above separates it from the link columns.

**Transfer:** Use the new identity or a short defining word in a heavy geometric sans, sized to the available width. It must feel like artwork rather than another heading.

**Build:** Use oversized SVG text with a heavy geometric sans, fit it to nearly the full 1440px stage width and roughly 344px height, then mask the moving three-band strip into the letters over a black base. Clip overflow at the footer edge. Keep this artwork separate from the Sora heading recipes.

### Documentary photo wall

**Only for:** company and recruiting pages

**Use:** Humanize organizational narratives.

**Observed:** Six 4:3 photographs in a three-column, two-row wall: candid conversations, presentations, group gatherings and work events. Natural color and daylight, edge-to-edge within 18px rounded frames; no synthetic spectrum tint on faces.

**Transfer:** Use genuine working and gathering moments, mixing close portraits and wide group scenes.

### Customer story covers

**Only for:** customer-story indexes

**Use:** Distinctive editorial proof thumbnails.

**Observed:** Partner marks paired on dark green, navy, purple or bright branded fields; some covers include product screens, devices or abstract motifs. Regular covers are landscape and remain confined to the media region.

**Transfer:** Allow each story's visual identity inside its thumbnail while keeping card text and surrounding canvas neutral.

### Icons

**Observed:** Most navigation and action icons are 16px, with 2px round strokes; dropdown chevrons are 12px. Checkmarks are 16px with 2.5px round strokes, alternating cyan, yellow and rose. Feature symbols sit in small white rounded tiles with faint glows.

**Transfer:** Choose simple outline icons with consistent round caps; use filled partner logos only for proof attribution.

## Section recipes

How recurring sections are built.

### First screen: Luminous product opening

**Observed:** A narrow dark atmospheric announcement strip sits above an inset Atmospheric stage. Navigation spans its top. The central heading occupies about two thirds of the width in a maximum 896px text column, with display typography, two balanced black lines and a faint warm glow behind the second line. Lead copy sits 24px below and narrows to 724px. Three short checkmarked assurances follow, then Primary button and Secondary button with 16px separation and 40px top spacing. Small trust metrics precede the 896px interface window, which begins around 704px down the page. Within the first 900px, the complete promise, support, assurances, actions, trust line and upper interface are visible; the rest of the window and the stage bottom continue below. Back-to-front layers are pale texture, colored light and diagonal ray, white interface and crisp text.

**Transfer:** Center a specific outcome promise above one genuine task scene. Without custom art, use a simplified white interface and the Three-band ray with a glass-tile metaphor. Editorial indexes use editorial-display with a dot eyebrow and shorter stage; recruiting can add three statistics, company narratives can add three supporting cards. Pricing opens left-aligned with pricing-display and plans immediately below.

**Avoid:** Do not replace this with a split hero, full-screen dark gradient, oversized abstract orb or a tiny interface thumbnail. Do not squeeze the whole demonstration into the first viewport.

**Text style:** `display` — Sora 500 · 62px/1.06

### Section heading pair

**Observed:** Major chapter heading uses heading-lg, centered for conceptual introductions and left-aligned for processes or benefits. Centered support uses lead and follows by 20px; content typically starts 64px below the heading region. Main chapters have 128px vertical padding.

**Transfer:** Use alignment to distinguish framing chapters from practical explanations; do not introduce an eyebrow to every heading.

### Before and after exhibit

**Observed:** Centered heading above two columns in a 1024px region with a 48px gap. The muted old workflow is unframed or lightly treated; the improved workflow gains a white, rounded, spectrum-edged panel, illustrated mini UI and colored checks.

**Transfer:** Contrast the friction and the resolved task with parallel copy and visual density; give only the improved path dimensional emphasis.

### Process triptych

**Observed:** Three Step cards sit in a 20px-gutter grid, 64px below a left-aligned heading. Pale cyan, yellow and rose media compartments contain miniature interfaces. An outlined conversion action follows below rather than inside every card.

**Transfer:** Use short verbs and show one evolving task through a small number of concrete states.

### Connected capability exhibit

**Observed:** An Atmospheric stage groups alternating two-column Hairline cards. Each row pairs 36px-padded text with a Product tableau; category dot, feature-heading, body-small paragraph, concise bullet list and small arrow link form the text hierarchy. Between rows, a small file-label capsule sits on a short vertical connector with an italic gray caption.

**Transfer:** Explain related capabilities as a connected system. Retain the connector-and-caption device for the shared artifact or workflow, not necessarily a file.

### Outcome and orbit

**Observed:** Left side has a heading-lg and three icon-led benefits with card-heading and body-small text. Right side is a 648px square atmospheric illustration: a central physical object over a white label tile, thin circular orbit, small task capsules and a short spectral arc.

**Transfer:** Map the new product's feedback loop onto a pale orbital diagram. Minimum version uses SVG rings and labels with one glassy central tile, not a busy flowchart.

### Proof rails

**Observed:** Centered heading followed by two Testimonial card rails 56px below. Cards are 352px wide, separated by 16px; the viewport clips the rails and white 112px fades soften both ends.

**Transfer:** Use authentic concise statements and keep attributions attached; a small logo strip can supply an earlier, lighter proof beat.

### Luminous conversion call

**Observed:** Atmospheric stage frame sits in 16px page gutters with 128px section padding. A 32px inset creates a Frosted conversion panel with 80px vertical content padding. Centered closing-heading, body support, three inline checkmarked assurances and a paired action row form the hierarchy. Faint corner cuboids and cyan/yellow/rose light give depth without lowering text contrast.

**Transfer:** Return to the promise with a direct question or invitation and practical reassurance. Adapt the action to the page purpose; keep the luminous nested-panel device.

### FAQ reading column

**Observed:** A centered short heading introduces a 768px column 64px below. FAQ rows use 16px vertical button padding, fine separators and a chevron at the right. Answers are body typography; only the leading answer is initially expanded.

**Transfer:** Handle adoption, compatibility, cost and reversibility concerns in plain sentences.

### Monumental footer

**Observed:** White footer begins with 64px top padding and 40px side gutters. Identity and contact occupy the left; five link columns occupy the right with 32px gaps, 14px labels and 12px link rhythm. After a 144px pause, Closing word sculpture fills the lower edge and is clipped horizontally.

**Transfer:** Preserve both the utilitarian directory and the oversized identity gesture. A short new identity can be scaled wider; do not turn the artwork into another navigation row.

### Human organization chapters

**Only for:** company and recruiting pages

**Observed:** Compact editorial opening gives way to Documentary photo wall with 80px vertical padding. Centered heading sections use heading, white information cards and sparse colored dots. Recruiting adds a cool values band, two-column benefit list and narrow role-listing cards; company storytelling adds a monochrome logo row, five-column portrait/name grid and two cool-wash commitment cards with thin colored top rules.

**Transfer:** Use genuine organizational differentiators, small facts and human proof rather than product demonstrations. Role listings can lead directly into the footer without a separate conversion frame.

### Story library

**Only for:** customer-story indexes

**Observed:** A short editorial opening leads directly into a three-column Story card grid with 20px gaps; first card spans two columns. Individual story covers carry more saturated color than the rest of the site. Proof rails and Luminous conversion call complete the narrative.

**Transfer:** Lead with the strongest outcome story and keep each summary short enough to preserve the grid rhythm.

### Pricing decision workbench

**Only for:** pricing pages

**Observed:** Left-aligned opening introduces four Plan cards at 24px gaps. Explanatory two-column content leads to three Usage presets and a calculator split roughly three-fifths controls to two-fifths recommendations. A textured three-card cost comparison elevates the preferred white card with a spectrum border. The detailed comparison table has 53px rows, fine horizontal rules and a warm-paper recommended column with a thin spectrum top edge.

**Transfer:** Explain the billing model before asking users to manipulate it. Make recommendation logic legible, align suffixes and units, and use one visual recommendation rather than highlighting every plan.

## Page flow

**Storyline:** Outcome promise → tangible explanation → proof and practical detail → decision support → reassurance and action → monumental identity.

### Introduce an integrated product platform

1. **Promise** — Centered luminous opening, paired actions and a large task interface.
2. **Social proof** — Lightweight logo rail.
3. **Product explanation** — Before/after exhibit, process cards and connected capability rows.
4. **Outcome proof** — Benefits beside an orbital workflow and a small pricing comparison.
5. **Trust and objections** — Testimonial rails and FAQ reading column.
6. **Closing call** — Luminous conversion panel followed by directory and giant word sculpture.

**Transfer:** Let one coherent task connect the product scenes; reuse the signature devices without prescribing an identical chapter count.

### Recruit people into an organization

1. **Invitation** — Editorial opening, single recruiting action and three compact statistics.
2. **Human proof** — Six-image documentary wall.
3. **Reasons to join** — Three reason cards, values band and two-column benefits.
4. **Action** — Narrow categorized role listings.
5. **Ending** — Directory and monumental word sculpture without a separate closing call.

**Transfer:** Prioritize real working culture and practical conditions; end where applicants can act.

### Help prospects find relevant success stories

1. **Promise** — Short centered editorial opening.
2. **Outcome proof** — Featured wide story and repeated three-column story cards.
3. **Peer validation** — Two testimonial rails.
4. **Closing call** — Luminous conversion call, footer directory and word sculpture.

**Transfer:** Organize stories by meaningful outcomes and let varied partner artwork live only inside covers.

### Explain the organization and establish credibility

1. **Mission** — Editorial opening with three supporting rationale cards.
2. **Human proof** — Documentary photo wall.
3. **Credibility** — Investor logos, portrait/name directory and compact external links.
4. **Commitment** — Two pale information cards with colored top rules.
5. **Closing call** — Luminous panel with recruiting and editorial actions; monumental footer.

**Transfer:** Replace the source's proof categories with the new organization's genuine basis for trust.

### Make a commercial decision understandable

1. **Offer** — Left-aligned promise and four-plan grid.
2. **Model explanation** — Plain-language billing explanation and included-capability list.
3. **Decision support** — Preset calculator, cost comparisons and detailed plan matrix.
4. **Trust** — Testimonial rails.
5. **Closing call** — Luminous conversion panel.
6. **Objection handling** — FAQ followed by a narrow comparison-resource list.
7. **Ending** — Shared directory and monumental word sculpture.

**Transfer:** Keep the calculator and matrix scoped to buying decisions; give definitions and trade-offs equal prominence to prices.

## Writing

Practical, confident and technically literate, with warmth supplied by clarity rather than jokes. Benefits are explained through what the reader can do and the coordination they no longer need.

**Do not copy:** Do not reuse Prisma's identity, product names, partner marks, artwork, quotes, customer claims, developer counts, pricing, performance figures or organizational facts. Source examples illustrate tone only; replace them with truthful content for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your' task. Use 'we' for organizational commitments, and the product name for explanations that need a clear subject.
- **Rhythm:** Headlines are usually short outcome statements, sometimes extended across two balanced lines. Support is one or two explanatory sentences; lists use compact clauses. Repeated verbs and parallel phrasing give technical ideas momentum without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the reader's task and the complete outcome. | 6–12 words | “Your TypeScript app, from prompt to production” |
| Chapter heading | Describe what changes, or make a concrete process promise. | 5–10 words | “Ship a production TypeScript app in three steps”<br>“Pricing that scales with you” |
| Supporting line | Explain how the pieces work together and remove a specific source of friction. | 20–45 words | “ORM, database, and hosting designed to work together, so your agent can build, deploy, and iterate without coordinating between vendors.” |
| Benefit | A direct claim followed by operational clarification. | 4–12 words plus a short explanation | “Your agent handles the full loop”<br>“Build, deploy, debug, redeploy. No vendor coordination.” |
| Primary action | Verb plus immediate next step; lower commitment when factual. | 2–4 words | “Get started free”<br>“View open positions” |
| Objection answer | Lead with yes/no or a definition, then explain the practical boundary. | 2–4 sentences | “An operation is a single action against your [Brand] Postgres database — a create, read, update, or delete.” |

**Words and phrasing to use:** build; ship; deploy; together; one; shared; when you're ready; without; start free; works

**Avoid:** revolutionary; unleash limitless potential; magical; world-class solutions; disruptive ecosystem; empty superlatives

**Rules:**

- Make claims testable by naming the task, boundary or mechanism.
- Use compact parallel assurances to lower adoption friction.
- Explain technical vocabulary when it controls a decision.
- Differentiate product facts from customer testimony; keep testimony attributed.
- Prefer a concrete workflow verb over an abstract benefit noun.

## Do's and Don'ts

### Do

- Use Sora 500 with normal tracking for the 62px opening and 48px chapter headings.
- Keep main reading fields white and reserve the spectrum for light, edges and meaningful media.
- Pair the 48px black capsule with a 48px outlined capsule and a 16px gap.
- Give major chapters 128px vertical padding and desktop content 32px side gutters.
- Use 18px card corners, 24px stage corners and 14px inner glass corners as distinct layers.
- Make product scenes half of a capability row and larger than decorative icons.
- Use small sentence-case labels with 8px colored dots to organize technical categories.
- Carry the three-band ray into a final oversized identity artwork.

### Don't

- Do not set every heading in heavy 700 weight or apply negative tracking across the scale.
- Do not replace the black primary capsule with a solid cyan or rainbow-filled button.
- Do not give all cards large drop shadows; ordinary edges are black at only 6% opacity.
- Do not tint every reading section pastel; the dominant canvas is white.
- Do not turn testimonial rails into huge centered quotations with decorative quotation marks.
- Do not style the comparison matrix as detached rounded tiles for each cell; retain aligned rows and fine rules.
- Do not apply spectral grading to documentary faces or team photos.
- Do not make all corner radii pills; the 18px content cards must remain visibly rectangular.

## Motion and responsive

### Motion

**Observed:**

- Declared: logo and testimonial marquee 100s linear infinite; reduced-motion rails use horizontal overflow instead.
- Declared: opening rise 0.9s cubic-bezier(0.22,1,0.36,1), with separate 0.45s and 0.75s delays; ray reveal 1.2s cubic-bezier(0.33,0,0.2,1) after 0.15s.
- Declared: spectrum ring slide 2.5s linear infinite, status pulse 2.6s ease-in-out infinite and step-border cycle 7s linear infinite.
- Declared: navigation all 0.5s cubic-bezier(0.22,1,0.36,1); ordinary link color transitions .15s cubic-bezier(.4,0,.2,1).

**Transfer:**

- Animate light and continuity rather than moving all text continuously.
- Pause proof rails on hover and offer static horizontal access for reduced motion.
- Keep the interface legible while its background ray or status details move.

**Unknown:**

- Exact trajectories for uninspected keyframes and interaction-driven calculator animations are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1536px.
- Heading sizes use the supplied clamp formulas. Desktop navigation links are hidden below 768px.
- Process grids become three columns at 768px; product rows become two columns at 1024px. Plan cards use two columns at 768px and four at 1024px.
- Main marketing section padding changes from 96px vertically and 16px horizontally to 128px and 32px; opening outer gutters change from 12px to 16px.

**Transfer:**

- On narrow screens keep the ray, glow and foreground interface as one cropped scene; stack capability text and media without shrinking text into the artwork.
- Let assurances and actions wrap; keep the black capsule's label unbroken.
- Retain the footer word sculpture as clipped artwork rather than compressing it to body-text scale.

**Unknown:**

- Mobile menu construction, exact narrow-screen table behavior and mobile artwork framing are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
