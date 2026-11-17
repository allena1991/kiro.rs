# Aave — soft sculpted confidence

## Overview

An airy, approachable technology style that makes complex infrastructure feel like a polished consumer product. White space, charcoal grotesk typography and lavender light surround oversized interfaces and softly sculpted objects. Rounded panels and small pill actions keep the tone friendly, while measured proof and restrained technical diagrams lend credibility. A green product variant and a violet-black developer variant retain the same spacious underlying system.

### Essentials

- Headlines feel substantial without becoming heavy: Aave Repro at 72px/1.1, weight 550, with -0.05em tracking and selected phrases relaxed to -0.02em; section headings use 40px/1.2 at 500.
- The opening is a luminous product stage, not a text-and-image split: centered copy in a 986px content width, a small product identifier above it, 48px pill actions, and a three-layer interface composition rising from below.
- Color behaves like light around an object: the default page remains predominantly white, with broad pale lavender atmosphere in major stages and the ending; solid lavender is concentrated in actions, marks, icons and data.
- Actions are friendly capsules rather than outlined rectangles: 48px height, 24px horizontal padding and 99px radius; the compact navigation action is 32px high with 16px horizontal padding.
- Proof is arranged as a collection of small designed objects: 313px-wide cards with 24px corners, 32px padding, a simple icon above a modest 24px metric and an explanatory caption.
- Every new page carries both a soft atmospheric field and a sculptural product illustration or layered interface stage. If no device interface exists, use rounded isometric blocks or an extruded product-relevant symbol with lavender faces and a soft floor shadow.
- The ending is a designed destination: a pale atmospheric field behind five compact link columns, followed by a small wordmark and social-symbol row, with low-contrast explanatory text beneath; the default framing retains 24px outer gutters.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender | `#978eff` | `--color-lavender` | action, accent | Primary action fill and graphic accents. |
| Orchid lavender | `#9c8cff` | `--color-footer-accent` | text, accent | Footer labels, brand marks and small highlights. |
| Lavender wash | `#f5f4ff` | `--color-lavender-wash` | surface, background | Visible 10% #978eff over white; soft buttons and a starting point for atmospheric fields. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep lavender | `#8578ff` | `--color-lavender-link` | link, text | Text on soft lavender buttons. |
| Pearlescent violet | `#9391fe` | `--color-gradient-mid` | accent | Center of gradient-emphasized headline phrases. |
| Pearlescent edge | `#e5e5ff` | `--color-gradient-light` | accent | Light ends of gradient-emphasized headline phrases. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, white cards and reversed text. |
| Near-white card | `#fbfbfb` | `--color-card` | surface, background | Very subtle feature cards and capability bands. |
| Soft field grey | `#f8f8f9` | `--color-field` | surface | Visible input fill: #252228 at 3% over white. |
| Hairline grey | `#f4f4f4` | `--color-edge` | border | Visible 5% charcoal edge on white panels. |
| Faint charcoal | `#bebdbf` | `--color-faint` | text | Visible tertiary text from #272228 at 30% over white; reserved for low-priority annotations. |
| Reversed muted text | `#b7b7b7` | `--color-night-muted` | text | Visible 70% white over near black in dark chapters. |
| Muted charcoal | `#736f73` | `--color-muted` | text, link | Visible supporting copy color: #272228 at 65% over white. |
| Caption grey | `#636161` | `--color-caption` | text | Solid grey captions and editorial body text. |
| Soft charcoal | `#3d383e` | `--color-heading` | text | Visible large heading color: charcoal #272228 at 90% over white. |
| Action charcoal | `#252228` | `--color-action-ink` | action, text | Compact navigation button and dark utility controls. |
| Charcoal ink | `#221d1d` | `--color-ink` | text | Primary dark text and small metric labels. |
| Near black | `#0f0f10` | `--color-night` | background | Inset advanced-product chapter; base beneath the developer theme. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company storytelling | Editorial near-white | `#fcfcfc` | `--color-editorial-card` | surface | Infographic backing. |
| developer product pages | Violet night | `#1a1928` | `--color-developer-night` | background | Visible #8075ff at 10% over near black. |
| developer demonstrations | Terminal shell | `#323042` | `--color-terminal` | surface | Framing around the technical demonstration. |
| developer demonstrations | Terminal screen | `#373647` | `--color-terminal-screen` | surface | Inner terminal backing. |
| green product family | Fresh green | `#28d358` | `--color-green` | action, accent, text | Replaces lavender for the green product family; vivid objects and data use the same hue. |
| green product family | Mint label | `#78e394` | `--color-green-label` | text | Footer group labels in the green family. |
| green product family | Mint atmosphere | `#f5fcf7` | `--color-green-wash` | background | Pale green chapter atmosphere. |
| green product family | Mint fade | `#fafefb` | `--color-green-end` | background | Lighter end of the green chapter wash. |
| green product conversion callouts | Lime light | `#e2ffce` | `--color-lime-glow` | background | Credit-callout radial light. |
| green product conversion callouts | Mint light | `#cbfad1` | `--color-mint-glow` | background | Credit-callout radial midpoint. |
| green product conversion callouts | Mint edge | `#c3f4d4` | `--color-mint-edge` | background | Credit-callout radial outer color. |

## Typography

- **Aave Repro** — All marketing headlines, paragraphs, navigation and actions. A rounded contemporary grotesk with a generous x-height, open counters and distinctive friendly letterforms; medium rather than bold headlines. OpenType features: "cv11". If unavailable, use **DM Sans**. Use variable weights 400–550 and preserve the tight heading tracking. Font stack: "Aave Repro", "DM Sans", ui-sans-serif, system-ui, sans-serif.
- **Aave Repro Mono** (only for developer setup instructions) — Step numbers and endpoint strings. A restrained monospace companion, colored lavender for numbering. If unavailable, use **IBM Plex Mono**. Font stack: "Aave Repro Mono", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, monospace.
- **Aave Aguzzo** (only for green product conversion callouts) — One expressive phrase inside an otherwise sans-serif callout. Bold, sloped editorial serif; a brief contrast, not a second headline system. If unavailable, use **Libre Baskerville**. Use bold italic for the sloped silhouette. Font stack: "Aave Aguzzo", "Libre Baskerville", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Aave Repro | 550 | 72px | 1.1 | -0.05em | Default marketing hero and large centered chapter statements. |
| display-highlight | Aave Repro | 550 | 72px | 1.1 | -0.02em | Selected phrase inside the display heading; also the gradient-emphasized phrase in a dark chapter. |
| heading | Aave Repro | 500 | 40px | 1.2 | -0.03em | Main section headings and compact closing calls. |
| proof-stat | Aave Repro | 500 | 32px | 1.35 | -0.02em | Partner proof figures. |
| card-heading | Aave Repro | 450 | 24px | 1.35 | -0.03em | Proof-card values and newsletter title. |
| lead | Aave Repro | 400 | 20px | 1.36 | -0.01em | Hero and section supporting paragraphs. |
| card-title | Aave Repro | 450 | 20px | 1.35 | -0.01em | Market-card headings and chart titles. |
| question | Aave Repro | 450 | 18px | 1.35 | -0.0183em | Accordion question text. |
| button | Aave Repro | 500 | 17px | 1.18 | -0.01em | 48px action capsules. |
| body | Aave Repro | 400 | 16px | 1.45 | -0.01em | Card descriptions. |
| proof-caption | Aave Repro | 400 | 16px | 1.4 | -0.01em | Short supporting text under proof metrics. |
| text-link | Aave Repro | 450 | 16px | 1 | -0.011em | Arrow-ended secondary reading links. |
| eyebrow | Aave Repro | 450 | 14px | 1.1 | 0.01em | Card category labels and footer group headings; sentence case. |
| nav | Aave Repro | 450 | 14px | 1.25 | normal | Header menu buttons. |
| compact-button | Aave Repro | 450 | 14px | 1.1 | -0.01em | 32px header action. |
| footer-link | Aave Repro | 450 | 14px | 1.25 | normal | Compact footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| developer product pages | developer-display | Aave Repro | 500 | 72px | 1.1 | -0.05em | Two-line technical hero with one lavender gradient phrase. |
| company storytelling | editorial-display | Aave Repro | 550 | 56px | 1.15 | -0.04em | Left-aligned two-line mission opening. |
| company storytelling and FAQ section labels | editorial-heading | Aave Repro | 500 | 40px | 1.35 | -0.02em | Editorial section titles with a looser vertical measure. |
| green product conversion callouts | serif-emphasis | Aave Aguzzo | 700 | 40px | 1.2 | -0.03em | A single sloped-serif phrase paired with a sans-serif callout heading. |
| developer setup instructions | step-number | Aave Repro Mono | 450 | 20px | 1.36 | -0.01em | Two-digit step index followed by a slash. |
| integration product pages | product-eyebrow | Aave Repro | 400 | 18px | 1.36 | -0.007em | Lavender topic labels above section titles. |
| green product family | green-eyebrow | Aave Repro | 450 | 16px | 1.36 | -0.01em | Green topic labels and feature-card titles. |
| integration request forms | form-label | Aave Repro | 400 | 16px | 1.5 | -0.011em | Visible labels above fields. |
| developer setup instructions | code | Aave Repro Mono | 400 | 14px | 1.5 | normal | Short endpoint or command strings outside a demo. |

**Notes:**

- Use sentence case throughout; the hierarchy comes from scale, spacing and weight rather than capitals.
- Keep headings tightly tracked and paragraphs much less compressed. Do not apply the 72px heading tracking to 16px descriptions.
- Selected phrases can have a subtly different tracking or a pearl-lavender text gradient, but the default light hero is solid charcoal.
- Use "ss07" only in the alternate card-heading treatment; the default marketing text uses "cv11".

## Layout

**Density:** Airy at section scale, compact within controls: large product stages alternate with neatly packed cards and short text blocks.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title-to-caption gaps and icon-to-label gaps. |
| 12px | Headline-to-support gap; newsletter field-to-button gap. |
| 16px | Paired actions and footer link spacing. |
| 24px | Outer stage gutters, standard grid gaps and small-card padding. |
| 32px | Proof-card padding, action separation from introductory copy and chart padding. |
| 48px | Large-panel padding and ordinary desktop section side padding. |
| 56px | Section introduction to supporting illustration or card grid. |
| 72px | Newsletter section padding and footer column separation. |
| 100px | Ordinary product section top and bottom padding. |
| 120px | Default FAQ chapter top and bottom padding. |
| 184px | Major luminous-stage top padding including the first screen. |

### Containers and grids

- **content**: max width 986px · side padding 48px. Centered content inside full-width sections. At 1440px, the inner content extends from 227px to 1213px.
- **navigation-and-footer**: max width 1082px · side padding 48px. Border-box wrapper whose padded interior aligns with the 986px content.
- **stage**: side padding 24px. Near-full-width art chapters framed by white outer gutters; 1392px inner width at 1440px.
- **support-copy**: max width 620px. Centered one- or two-line support beneath a major statement.
- **three-card-grid**: 3 columns · gap 24px. 313px-wide proof and feature cards across the content wrapper.
- **capability-grid** (only for integration and developer product pages): 3 columns · gap 32px. 307px-wide compact capability cards.
- **split-instructions** (only for integration and developer setup chapters): 2 columns · gap 56px. Narrow introductory column on the left and a taller step stack on the right.
- **request-form** (only for integration request forms): max width 758px · 2 columns · gap 24px · side padding 48px. Centered form panel with paired fields, full-width message and submit control.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 99px |
|  | cards | 24px |
|  | major-panels | 32px |
|  | inputs | 36px |
| company storytelling | infographic-cards | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | panel-edge | `0px 0px 0px 1px rgba(37,34,40,0.05)` | Newsletter and large white panels. |
|  | proof-glass | `0px 0px 0px 1px rgba(37,34,40,0.05), 0px 1px 2px 0px rgba(0,0,0,0.03)` | Partner proof cards and charts. |
| company culture card fans | lavender-card-lift | `0px 1px 1.5px 0px rgba(146,137,247,0.05), 0px 5px 2.5px 0px rgba(146,137,247,0.04), 0px 12px 3.5px 0px rgba(146,137,247,0.03), 0px 22px 4.5px 0px rgba(146,137,247,0.01)` | Subtle lilac elevation beneath overlapping illustrated cards. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing page.

**CSS:** `background: #ffffff; color: #221d1d`

#### Luminous stage · level 0

**Use:** Hero, builder chapter, proof atmosphere and footer.

**CSS:** `background: radial-gradient(ellipse at 50% 100%, rgba(151,142,255,0.32), rgba(151,142,255,0) 75%), #ffffff; border-radius: 32px; overflow: hidden`

**Observed:** White at the text-heavy top, with broad diffused lavender clouds gathering around the lower objects. The footer has a gentler version of the field.

**Transfer:** Recreate the light with oversized low-opacity gradients, not a small spotlight. Match the soft glow; exact stops are not essential.

#### White panel · level 1

**Use:** Newsletter and structured proof panels.

**CSS:** `background: #ffffff; border-radius: 32px; box-shadow: 0px 0px 0px 1px rgba(37,34,40,0.05)`

**Observed:** The edge is just visible; no dramatic floating shadow.

#### Advanced chapter · level 0

**Use:** Inset advanced-product demonstration.

**CSS:** `background: #0f0f10; color: #ffffff; border-radius: 32px`

**Observed:** An entire rounded chapter reverses the contrast, rather than scattering dark cards across a light layout.

**Transfer:** Reserve it for a distinct advanced capability with an interface worth showing.

#### Dark translucent card · level 1

**Use:** Cards within the advanced chapter.

**CSS:** `background: rgba(255,255,255,0.03); border-radius: 24px`

**Observed:** Low-contrast fill, white heading and 70% white body text. Developer variants add a 1px 5% white border and 4px backdrop blur.

#### Developer canvas · level 0

**Only for:** developer product pages

**Use:** Whole-page technical variant.

**CSS:** `background: #1a1928; color: #ffffff`

**Observed:** Near-black tinted violet with sparse vertical data flecks; not a saturated purple page.

**Transfer:** Keep light-page widths and spacing, reverse text and make UI surfaces slightly lighter than the ground.

#### Mint chapter · level 0

**Only for:** green product family

**Use:** Savings and chart chapters.

**CSS:** `background: linear-gradient(#f5fcf7, #fafefb, rgba(0,0,0,0))`

**Observed:** A pale mint field; saturated green remains localized to objects, curves and actions.

#### Mint conversion panel · level 1

**Only for:** green product conversion callouts

**Use:** Sales-oriented inset callout.

**CSS:** `background: linear-gradient(90deg, #ffffff, rgba(0,0,0,0)), radial-gradient(40% 100% at 65% 50%, #e2ffce, #cbfad1, #c3f4d4); border-radius: 32px; box-shadow: inset 0px 0px 0px 1px rgba(39,34,40,0.05)`

**Observed:** Soft white-to-green light under a text-and-object split.

## Components

### Navigation

**Use:** Persistent, small-scale orientation above the product stage.

**CSS:** `position: fixed; top: 0px; height: 71px; width: 100%; z-index: 100; box-shadow: 0px 0.6px 0px 0px rgba(0,0,0,0.03)`

**Text style:** `nav` — Aave Repro 450 · 14px/1.25

**Observed:** Small wordmark at left, four restrained menu items at right and Compact button at the far edge. The inner wrapper is 1082px including 48px side padding; menu targets are 32px high with 16px side padding.

**States:** Declared: hover menu background rgba(0,0,0,0.03) and text #272228; focus-visible 2px lavender outline.

### Primary button

**Use:** Main conversion in a light product stage.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 0px 24px; border-radius: 99px; background: #978eff; color: #ffffff`

**Text style:** `button` — Aave Repro 500 · 17px/1.18 · tracking -0.01em

**Observed:** Content-sized capsule, paired with Secondary button at a 16px gap. A platform symbol may precede the label. Dark chapters use white fill and charcoal text; the green family uses green fill.

**States:** Declared: hover fill color(display-p3 0.55 0.51 0.92); focus-visible 2px lavender outline with 2px offset; active scale(0.99).

### Secondary button

**Use:** Adjacent explanation or documentation action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 0px 24px; border-radius: 99px; background: rgba(151,142,255,0.1); color: #8578ff`

**Text style:** `button` — Aave Repro 500 · 17px/1.18 · tracking -0.01em

**Observed:** Soft filled rather than outlined. In a dark chapter it becomes 10% white fill with white text; the green family uses 12% green fill and green text.

**States:** Declared: hover background rgba(151,142,255,0.18); focus-visible 2px lavender outline with 2px offset; active scale(0.99).

### Compact button

**Use:** Persistent header conversion.

**CSS:** `height: 32px; padding: 0px 16px; border-radius: 99px; background: #252228; color: #ffffff; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `compact-button` — Aave Repro 450 · 14px/1.1 · tracking -0.01em

**Observed:** Smaller and darker than the light hero action. It reverses to white on the developer theme.

**States:** Declared: hover background #3b383e; focus-visible 2px #252228 outline with 2px offset; active scale(0.99).

### Proof card

**Use:** Concise quantified or verified proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 24px; padding: 32px; background: #ffffff; border: 1px solid rgba(38,34,40,0.05); border-radius: 24px`

**Text style:** `card-heading` — Aave Repro 450 · 24px/1.35 · tracking -0.03em

**Observed:** A 32px lavender symbol is separated from a bottom-aligned metric and caption. The common card is 313px by 193px; a three-column grid can wrap into a second row.

**Transfer:** Keep values modest in size and explain the unit or meaning in a single proof-caption line.

### Partner proof card

**Use:** Credibility presented in a horizontal carousel.

**CSS:** `display: flex; max-width: 365px; height: 210px; background: rgba(255,255,255,0.23); border-radius: 24px; box-shadow: 0px 0px 0px 1px rgba(37,34,40,0.05), 0px 1px 2px 0px rgba(0,0,0,0.03); overflow: hidden`

**Text style:** `proof-stat` — Aave Repro 500 · 32px/1.35 · tracking -0.02em

**Observed:** Logo or partner label above a figure and a short caption; inner content uses 32px padding. A separate 20% white layer has 12px backdrop blur. Cards sit 16px apart with a fading track edge and small 32px circular previous/next controls.

**Transfer:** Use a small set of real partner outcomes, not long testimonial quotes.

### Newsletter panel

**Use:** A gentle final action above the footer.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 32px; padding: 48px; background: #ffffff; border-radius: 32px; box-shadow: 0px 0px 0px 1px rgba(37,34,40,0.05)`

**Text style:** `card-heading` — Aave Repro 450 · 24px/1.35 · tracking -0.03em

**Observed:** Centered title, one 20px support line and an inline email form. The panel is 986px wide and 250px high; input and notify capsule are separated by 12px. The notify capsule is 42px high, charcoal, visually subdued to 50% opacity in its initial state.

### Soft field

**Use:** Email entry; also paired fields in an integration form.

**CSS:** `background: rgba(37,34,40,0.03); border-radius: 36px; padding: 10px 16px; height: 43px; max-width: 420px`

**Observed:** Fill is almost indistinguishable from white, without a strong rectangular outline. Integration fields are 44px high; labels sit above rather than relying on placeholder text.

**Transfer:** Retain actual labels for multi-field forms and use a 20px-radius full-width textarea.

### FAQ row

**Use:** Low-density objection handling near the end.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 8px; padding: 24px 16px 14px; width: 662px`

**Text style:** `question` — Aave Repro 450 · 18px/1.35 · tracking -0.0183em

**Observed:** Question left and fine lavender plus right, with 10px spacing below the button. Rows have very faint dividers, not a card around every question. The visual plus is inside a 52px SVG area.

### Footer

**Use:** A complete low-key ending inside the atmospheric field.

**CSS:** `position: relative; padding: 48px; max-width: 1082px`

**Text style:** `footer-link` — Aave Repro 450 · 14px/1.25

**Observed:** Five link columns with 14px lavender category labels and 16px vertical link gaps; a small wordmark sits below at left while monochrome social and ecosystem symbols align right. Low-contrast explanatory text follows after 72px. Mint labels and a dark wordmark belong to the green family; the developer ending remains dark with lavender labels.

### Terminal demonstration

**Only for:** developer product pages

**Use:** The principal product object beneath the technical hero.

**CSS:** `display: flex; flex-direction: column; background: #323042; border: 1px solid rgba(255,255,255,0.14); border-radius: 24px; box-shadow: 0px 6px 20px 0px rgba(0,0,0,0.07); overflow: hidden; max-width: 729px`

**Observed:** Browser-like shell with colored window dots, small task tabs and replay/copy controls; a lighter violet-grey inner screen has 14px corners. The text demonstration uses monospace and lavender emphasis rather than a full application dashboard.

**Transfer:** Show one short input-to-result workflow; keep detailed interface styles inside the demonstration.

### Integration form

**Only for:** integration request forms

**Use:** High-intent final conversion after FAQs.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 48px; max-width: 758px; background: #ffffff; border-radius: 24px; box-shadow: 0px 0px 0px 1px rgba(38,34,40,0.05)`

**Text style:** `form-label` — Aave Repro 400 · 16px/1.5 · tracking -0.011em

**Observed:** Two-column labeled fields, lavender required dots, full-width message area and a full-width 44px lavender submit pill. Centered heading and support sit 40px above the panel.

**Transfer:** Ask only for information needed to qualify the next step; keep fields paired until width requires stacking.

## Imagery and graphics

### Layered interface stage

**Use:** Primary product demonstration and later ecosystem-product proof.

**Observed:** Three front-facing phone interfaces overlap, with the center device higher and in front; side screens recede and darken. Individual device artwork is about 323px wide; the group occupies most of the lower hero and continues beyond the first screen. Lavender charts are legible inside realistic metallic black device frames.

**Transfer:** Use a comparable trio of your own product states, keeping the central result bright and foremost. For a non-mobile product, use overlapping rounded interface windows with a clear center/front hierarchy.

**Build:** Place three images in a centered relative stage. Use roughly 323px-wide panels, overlap adjacent panels by about 67px, lift the center above its neighbors and put it at the highest z-index. Put a wide low-opacity lavender radial field behind the entire group rather than individual drop shadows.

### Sculpted modular objects

**Use:** Signature visual explanation of a product's building blocks.

**Observed:** Three isometric rounded-square block stacks rise from one to three layers against pale lavender light. Top faces are lighter than sides, with simple white emblems; purple saturation increases across the group. A separate integration hero uses a floating lavender percentage symbol with a mint highlight and a faint floor shadow.

**Transfer:** Use a simple product-relevant shape or modular blocks, not decorative abstract blobs. Minimum acceptable treatment is crisp SVG isometric geometry with curved corners, two or three lavender face tones and a soft floor shadow.

**Build:** In SVG, draw three groups of rounded isometric slabs using a diamond top and two vertical side faces. Offset repeated layers vertically, keep top faces pale, and darken one side. Use lavender as the base with translucent white highlights and translucent charcoal shading; add a blurred low-opacity elliptical shadow beneath each group.

### Atmospheric light field

**Use:** Required connective visual device in major stages and the ending.

**Observed:** Broad lavender clouds fade smoothly into white around interfaces, illustrations and proof cards. The footer uses an especially pale wash and remains text-first.

**Transfer:** Use the same field around different objects; retain ample unpainted white around headings.

**Build:** Layer two oversized radial gradients over white: one lavender field anchored low and centered at roughly 20–30% opacity, another offset to a side at 8–12%. Let both fade completely before the upper headline. Clip within the rounded stage and use a shallower, lower-opacity version behind the footer.

### Data as friendly objects

**Use:** Quantified proof, comparisons and mechanism explanations.

**Observed:** Charts are thin, softly colored and minimally gridded. Proof illustrations turn data into rounded vertical bars, an open semicircular gauge and orderly dot arrays. Charcoal labels and restrained annotations keep them readable; a featured curve is lavender or green while comparisons are grey.

**Transfer:** Use real data and only the chart form the story needs. SVG text and paths should remain crisp rather than looking like a dashboard screenshot.

**Build:** Construct rounded bars or equal circles in SVG; vary opacity across the lavender or green series. Place the main value at upper left, caption beneath, and let the graphic occupy the lower or right portion. For line comparisons, use a thin colored path, a faint area fade and small endpoint capsules, with grey comparison lines.

### Mechanism diagrams

**Only for:** integration and explanatory product chapters

**Use:** Show what happens underneath a simple user action.

**Observed:** Light rounded modules connected by fine dashed arrows, tiny colored arrowheads and occasional lavender dot clusters. Wide diagrams occupy the 986px content width without a dark dashboard frame.

**Transfer:** Reduce the mechanism to a few labeled boxes and one clear flow; use faint connectors and local accents rather than every node getting a different color.

### Mint token sculpture

**Only for:** green product family

**Use:** Compact hero object and sales callout illustration.

**Observed:** Glossy green coin-like discs with beveled rims, white face symbols and reflective mint edges float above very faint oval shadows. A later callout uses a leaning disc beside a short coin stack.

**Transfer:** Translate the disc into a product-relevant badge or round object, retaining bright green material and white face detail.

**Build:** Layer concentric SVG ellipses with green gradients, offset the back disc for thickness and add repeated short rim strokes. Put a white symbol on the front face, a pale mint highlight along the upper rim and a blurred green-grey ellipse beneath. A secondary lavender reflection may touch one lower edge.

### Culture card fan

**Only for:** company culture storytelling

**Use:** A playful tactile collection within an otherwise editorial page.

**Observed:** Five overlapping pastel illustrated cards tilt slightly in alternating directions. Small soft white character sculptures float in lavender, mint and pale pink light; headings and short copy occupy the lower card area. Corners are 24px and shadows are lilac, very faint.

**Transfer:** Create original small symbolic sculptures for cultural principles, keeping the fan composition and pastel material rather than duplicating mascots.

**Build:** Use rounded cards roughly 290px wide, overlap them into a 986px row and rotate by a few degrees. Place an original softly shaded icon in the upper half over broad pastel gradients; use the lavender-card-lift shadow.

### Human editorial photography

**Only for:** company storytelling

**Use:** A grounding wide image after the mission statement.

**Observed:** A naturally lit event discussion with people and surroundings visible, framed as one wide 986px by 409px image with rounded corners. No heavy tint or black overlay competes with the scene.

**Transfer:** Choose candid collaboration or real work imagery in natural light; keep it wide and understated.

### Pixel emblem field

**Only for:** developer product closing calls

**Use:** A distinctive closing action scene.

**Observed:** A huge, low-contrast violet emblem built from a dense pixel grid backs centered copy and two pills. Sparse vertical data flecks continue around it; the emblem does not become a giant text heading.

**Transfer:** Use an original product symbol as a faint pixel sculpture behind a 40px closing headline.

**Build:** Rasterize a simple SVG symbol into a grid of tiny squares or circles, tint lavender and vary opacity toward the perimeter. Scale it to occupy most of a 1266px-wide closing stage, keep its contrast low and place readable white copy above it.

### Icons

**Observed:** Mostly simple filled geometric symbols at 32px in cards, often lavender or grey. Action arrows use 13px SVG strokes with 2px round caps; footer social symbols are monochrome at roughly 18–23px. FAQ plus signs are fine and lavender within generous target areas.

**Transfer:** Choose simple geometric filled icons for features and small rounded-stroke arrows for links; do not mix detailed multicolor illustrations into the icon system.

## Section recipes

How recurring sections are built.

### First screen: Luminous product opening

**Observed:** A fixed 71px Navigation sits above a near-full-width Luminous stage, framed by 24px white gutters. Centered content begins with a small icon and product identifier around 184px down; the single-line 72px headline spans most of the 986px content width, followed by a 20px support line at a 12px gap. Primary button and Secondary button sit side by side, 16px apart, with about 32px of separation from the support. Below a generous pause, the Layered interface stage rises into the lower half: the center device is higher and brighter than the two rear devices. In the first 900px the identifier, headline, support, both actions and most of the upper devices are visible; device bottoms and the following proof panel fall below the fold. Layers run white canvas, diffused lavender field, overlapping devices, then centered copy and actions.

**Transfer:** Keep the same centered hierarchy and decisive lower product object for a different product; use layered interface windows or Sculpted modular objects if phones are inappropriate. A focused integration product can use one small floating symbol below the actions. Company storytelling instead opens left-aligned at 56px above a wide photograph; developer products use a two-line 72px hero over a dark field and a terminal; the green family opens over mint light with a compact pair of sculpted discs.

**Avoid:** Do not replace the product stage with a conventional left-copy/right-stock-photo hero, or shrink the main object into a decorative thumbnail.

**Text style:** `display` — Aave Repro 550 · 72px/1.1 · tracking -0.05em

### Heading and support chapter

**Observed:** Within the 986px content width, a short category label precedes a 40px heading by 12px; another 12–16px separates the heading and 20px support. Actions sit about 32px below copy and the supporting grid or diagram about 56px later. Ordinary sections use 100px vertical padding. Centered versions use a narrow support-copy measure.

**Transfer:** Choose left alignment for explanation and centered alignment for a broad statement or proof; retain the gap hierarchy.

**Text style:** `heading` — Aave Repro 500 · 40px/1.2 · tracking -0.03em

### Advanced product chapter

**Observed:** Advanced chapter forms a near-full-width rounded dark island. A centered 72px heading includes one pearl-lavender gradient phrase, followed by support and white/soft-white pills. A large desktop interface occupies the middle; a later 40px heading leads into three Dark translucent cards.

**Transfer:** Use the dark island to signal a more capable mode of the product, not as an unrelated color break.

**Text style:** `display-highlight` — Aave Repro 550 · 72px/1.1 · tracking -0.02em

### Sculpture and partner proof

**Observed:** A Luminous stage combines a centered headline and paired actions, Sculpted modular objects across the middle, then a left-aligned 40px proof statement. Partner proof cards extend horizontally with carousel controls near the right edge.

**Transfer:** Move from a simple visual metaphor into concrete adoption evidence; the sculpture and carousel can be separated if the narrative needs it.

### Proof collection and comparison

**Observed:** A centered large statement precedes a three-column Proof card grid with 24px gaps. Below, a 40px section title and support introduce a white 24px-radius comparison chart with 32px padding and small legends.

**Transfer:** Mix a few concise proof facts with one readable comparison rather than putting every metric into a giant number.

### Objections and final action

**Observed:** FAQ row groups occupy a 662px right column beside a short section label where present. The ending action varies: Newsletter panel for broad marketing, a centered three-card choice for the green family, or Integration form for high-intent business products. Footer follows within a pale atmospheric field; the developer theme stays dark through its footer.

**Transfer:** Choose the final action by the audience's next step. Keep the quiet, complete footer and a deliberate background fade rather than ending abruptly.

### Editorial proof and culture

**Only for:** company storytelling

**Observed:** Left-aligned 40px headings lead to two-column prose, a two-column infographic mosaic with one tall card, a Culture card fan, and a three-column editorial story grid. News images are wide rounded rectangles, with title and description below, not overlaid.

**Transfer:** Combine human context, scale and craft in separate visual modes while retaining the same content alignment.

**Text style:** `editorial-heading` — Aave Repro 500 · 40px/1.35 · tracking -0.02em

### Technical setup and approval story

**Only for:** developer product pages

**Observed:** A split chapter holds a narrow heading block on the left and three numbered setup groups on the right. Client tiles lead to a short endpoint control and prompt cards. Later, three translucent cards show a request, preparation and approval sequence; a Pixel emblem field supports a centered closing call.

**Transfer:** Teach the shortest path to first success and explicitly show where the user retains control.

### Mechanism and capability chapters

**Only for:** integration product pages

**Observed:** A comparison illustration and text share one rounded two-part panel. Other chapters use three illustrated benefits, a left-heading/right-step stack, a near-white capability band with a three-column card grid, and a wide Mechanism diagram.

**Transfer:** Alternate visible user benefit with one layer of underlying mechanism; avoid turning the entire page into architecture documentation.

### Mint sales callout

**Only for:** green product conversion callouts

**Observed:** Mint conversion panel is 986px wide, with text left and a 280px-wide glossy token stack right. A 40px sans-serif line is followed by one green sloped-serif phrase, body copy and a soft green action.

**Transfer:** Use this contained material shift for a higher-touch offering rather than changing the whole typography system.

**Text style:** `serif-emphasis` — Aave Aguzzo 700 · 40px/1.2 · tracking -0.03em

## Page flow

**Storyline:** Clear promise → tangible product object → capability and mechanism → credible proof → questions and control → audience-appropriate action → atmospheric utility ending.

### Broad product and platform marketing

1. **Promise** — Centered luminous hero with a layered mobile interface.
2. **Quantified proof** — Compact metric strip and a gentle newsletter invitation.
3. **Advanced capability** — Inset dark chapter with a desktop interface and three market-style cards.
4. **Ecosystem proof** — Sculpted modular blocks followed by partner outcomes.
5. **Trust** — Rounded proof-card collection and comparative chart.
6. **Objection handling** — Right-column FAQ rows.
7. **Closing action** — White newsletter panel on a pale lavender field, then five-column footer.

**Transfer:** Use this pattern for a broad product portfolio, assigning different contrast chapters to different levels of capability.

### Company credibility and culture

1. **Mission** — Left-aligned two-line statement above a candid wide event image.
2. **Context** — History heading and split-column prose.
3. **Quantified proof** — Asymmetric infographic mosaic with lavender bars and dots.
4. **Human character** — Overlapping illustrated culture cards and a restrained hiring link.
5. **Current activity** — Three editorial story cards.
6. **Closing action** — Newsletter panel and lavender atmospheric footer.

**Transfer:** Use for a company story that balances people, scale and craft; preserve the editorial alignment rather than forcing a centered product hero.

### Developer product adoption

1. **Promise and demonstration** — Dark two-line headline and a terminal workflow.
2. **Compatibility** — Compact capability strip.
3. **Use cases** — Two-column visual workflow cards.
4. **Activation** — Three numbered setup groups with client choices and prompts.
5. **Depth** — Workflow cards and alternating capability rows.
6. **Control** — Three-card authorization explanation.
7. **Closing action** — Centered dual action over a faint pixel emblem.
8. **Objection handling and ending** — FAQs then dark footer with expanded cautionary text.

**Transfer:** Make the technical object and setup path concrete, then explain permissions and limits before the final utility ending.

### Focused consumer-facing product education

1. **Promise** — Mint-lit centered hero with glossy compact objects.
2. **Benefits** — Short value explanation and three cards.
3. **Product demonstration** — Simple savings steps and a prominent live rate.
4. **Quantified proof** — Comparison chart and mechanism diagram.
5. **Trust and choice** — Three data illustrations and two acquisition-path cards.
6. **Depth** — Three educational cards.
7. **Higher-touch conversion** — Mint sales panel with serif emphasis and token stack.
8. **Closing action** — Three action cards, FAQs and mint atmospheric footer.

**Transfer:** Use a single scoped accent to unite benefit, evidence and choice without losing the white-space-led structure.

### Business integration lead generation

1. **Promise** — Centered integration statement and a floating percentage sculpture.
2. **Problem and solution** — Rate-comparison graphic beside a concise benefit list.
3. **Capability** — Three illustrated benefits and a numbered process stack.
4. **Breadth** — Three-column capability collection on near-white.
5. **Product proof** — Layered mobile interface stage.
6. **Mechanism** — Wide labeled architecture diagram.
7. **Objection handling** — Right-column FAQs with more questions available.
8. **Closing action** — Centered two-column request form, then lavender atmospheric footer.

**Transfer:** Move from a clear commercial result toward implementation detail, ending in a form rather than a generic sign-up pill.

## Writing

Confident, plainspoken and inviting. Benefits are made tangible with short verbs, concrete mechanisms and verifiable proof rather than breathless innovation language.

**Do not copy:** Do not reuse Aave names, logos, mascots, proprietary artwork, financial claims, rates, rankings, customer marks, numerical outcomes or source quotations as claims for another product. Examples below demonstrate phrasing only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your when explaining benefit or control. Use the product name for mechanisms and we for a human sales invitation.
- **Rhythm:** Short sentence-case headlines, often four to eight words; one or two concise supporting sentences. Periods create pairs and triplets, while verbs make steps feel immediate.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct product category or outcome, stated with uncomplicated confidence. | 4–8 words | “The World's Savings App”<br>“Embedded yield from [Brand]” |
| Section heading | Short declarative phrase or balanced sentence pair. | 3–9 words | “Backed by [Brand]. Built to save.”<br>“The agent prepares. Your wallet authorizes.” |
| Supporting line | Explain a benefit through an understandable mechanism, with minimal qualifiers. | 10–25 words | “Get paid every second with global rates and Balance Protection.”<br>“Deposit GHO, hold sGHO, and earn the savings rate. No lockup, no minimum, no cooldown.” |
| Primary action | Verb plus destination or concrete next step. | 2–3 words | “Start Building”<br>“Request Integration” |
| Process heading | Three plain verbs instead of an abstract promise. | 3–5 words | “Deposit, earn, withdraw.” |
| Trust caption | Explain exactly what a metric means in one fragment. | 3–7 words | “Monthly volume across markets.” |
| Final invitation | A gentle continuing relationship or a specific next action. | 2–5 words | “Stay Updated”<br>“Give agents a credit layer.” |

**Words and phrasing to use:** built for; put to work; simple; native; every second; your product; prepare; choose; earn; supported; verify

**Avoid:** revolutionize everything; disruptive; unparalleled; game-changing; limitless; guaranteed returns; effortless magic

**Rules:**

- Lead with the result, then explain how it works.
- Use technical nouns when they clarify the mechanism; immediately connect them to an action or user benefit.
- Keep proof captions specific about what is being counted.
- State user control and product limitations directly.
- Use short parallel clauses for lists of benefits or steps; avoid repeated promotional adjectives.

## Do's and Don'ts

### Do

- Keep the default hero at 72px/1.1 and weight 550, not a conventional heavy bold.
- Align ordinary content to the 986px interior shared by navigation and footer.
- Use 48px action capsules with 24px side padding and 16px between paired actions.
- Keep feature collections to 24px corners and 24px or 32px internal padding.
- Let lavender atmosphere spread behind the main object while preserving white around the heading.
- Build proof with an icon, a modest 24px metric and a 16px caption.
- Use 100px vertical padding for ordinary explanatory chapters.
- Carry the atmospheric field into the footer and retain its small five-column utility hierarchy.

### Don't

- Do not make the entire default page solid lavender; reserve strong color for controls and local graphic surfaces.
- Do not substitute 700-weight grotesk headings for the 500–550-weight display system.
- Do not give every card a deep shadow; edges are generally 5% charcoal and only 1px thick.
- Do not use square or 8px-radius primary buttons; actions are capsules.
- Do not turn proof into a wall of giant numbers; most card values are only 24px.
- Do not use the culture card fan or serif emphasis as the ordinary marketing layout; both are scoped expressive moments.
- Do not scatter dark cards across white chapters to mimic the advanced theme; reverse a coherent chapter.
- Do not make footer social icons colorful badges or enlarge the footer wordmark into a full-width closing headline.

## Motion and responsive

### Motion

**Observed:**

- Action controls declare transform, background-color, color and opacity transitions at 0.15s; navigation background and color transitions are 0.2s.
- Buttons declare active scale(0.99). Secondary lavender fill increases from 10% to 18% on hover.
- The layered hero declares 0.6s entrance animations with cubic-bezier(0.19,1,0.22,1), delayed 1.5s for the center and 1.6s for side elements.
- Two developer decorative elements declare 24s linear infinite idle rotation.

**Transfer:**

- Keep pill feedback small and quick; let product-stage entrances distinguish center from supporting elements.
- Use slow rotation only for a scoped sculptural or technical object, not the whole content layer.

**Unknown:**

- Exact scroll-trigger sequencing and canvas animation behavior are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 412px, 720px, 768px, 769px, 820px, 900px, 980px, 1000px and 1020px across the pages.
- Proof grids declare repeat(auto-fit, minmax(300px, 1fr)); some product card grids use a 312px minimum.

**Transfer:**

- On narrow layouts, retain the centered hero and overlapping object hierarchy while scaling the group together; wrap action pairs only when needed.
- Stack paired form fields and split instruction columns before their labels become cramped. Let the footer columns wrap rather than shrinking the link type.
- Keep the large atmosphere attached to its section rather than to a desktop-sized fixed image.

**Unknown:**

- Mobile typography, exact menu collapse behavior and mobile canvas composition are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
