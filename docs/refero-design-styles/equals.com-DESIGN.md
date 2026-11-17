# Equals — spreadsheets meet the broadsheet

## Overview

An editorial software style that pairs tall, literary serif headlines with plainspoken grotesk text and miniature technical labels. Warm ivory dominates, with orchid actions, restrained vermilion markings and translucent pastel bars at the edges. Real interfaces and fine-line system illustrations carry the explanation, while a lavender wash and monumental black wordmark give the ending unusual weight. The feeling is spacious, credible and human rather than futuristic or dashboard-dense.

### Essentials

- Editorial scale without bold display type: Serrif Condensed at 110px/1, weight 400, -0.02em tracking for the opening; 48px/50px, -0.01em for section statements.
- A centered question floats between pastel edge markings: a 618px supporting line, 380×56px email capsule and a broad monochrome proof field fill the first 900px; the detailed product demonstration comes later.
- Conversion is a capsule within a capsule: white 50px-radius email shells surround orchid 60px-radius buttons, with a 6px inset and a subtle half-pixel edge rather than a black rectangular CTA.
- Color acts as annotation, not a blanket: the long middle stays #faf9f5 with black and 60%-black text; #ff3716 marks 14px uppercase chapter labels and #b074ce marks actions. Pastel edge bars and a lavender ending supply the larger color gestures.
- Product imagery is treated as a working document: large white interface windows, fine borders, 10–12px corners and soft layered shadows; repeated demonstrations sit in 603×402px neutral trays with captions outside.
- The ending is a brand-scale event: a centered two-line 48px serif call flows into a lavender footer with three sparse link columns, a 180px pause and a 1266×261px black wordmark artwork. Use the new identity at that scale, or a custom typographic rendering of its name. Preserve the pastel edge-bar motif even when product media must be rebuilt.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orchid | `#b074ce` | `--color-orchid` | action, accent | Default conversion buttons; occasional chapter label variant on pricing. |
| Lavender wash | `#ddc3e5` | `--color-lavender` | background | Soft lavender destination of the closing-to-footer wash; keep the transition broad and subtle, not a solid panel with a hard top edge. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#ff3716` | `--color-vermilion` | text, accent, action | Numbered technical chapter labels; entry-tier action variant on pricing only. |
| Pastel lemon | `#f8ed9a` | `--color-lemon` | accent | Small peripheral bar clusters and the lowest layer of the technical illustration. |
| Pastel aqua | `#b5eeea` | `--color-aqua` | accent | Translucent rectangular edge bars and the faint tint of technical sheet illustrations. |
| Pastel rose | `#f4cecb` | `--color-rose` | accent | Low-intensity edge-bar variation, never a large content panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, accent | Headlines, ordinary text, monochrome marks and the monumental footer identity. |
| Muted ink | `#646462` | `--color-muted` | text | Visible result of rgba(0,0,0,0.6) on warm ivory; equal-scale second heading clauses, body support and category labels. |
| Question rule | `#e1e0dd` | `--color-strong-rule` | border | Visible result of 10% black over warm ivory; tab and FAQ separators. |
| Fine rule | `#e6e5e1` | `--color-rule` | border | Visible result of 8% black over warm ivory; testimonial and pricing separators. |
| Demonstration tray | `#eeede9` | `--color-tray` | surface | Visible result of 5% black over warm ivory; backs interface demonstrations. |
| Warm ivory | `#faf9f5` | `--color-canvas` | background, surface | Default page canvas, sticky navigation and plan surfaces. |
| Off-white window | `#fcfcfc` | `--color-window` | surface | Large browser-like product stage. |
| Window white | `#ffffff` | `--color-white` | surface, text | Email shells, product windows and white action labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company narrative pages | Editorial blue | `#0000bb` | `--color-editorial-blue` | link | Inline linked phrases within the large serif letter. |
| pricing pages | Plan green | `#20a277` | `--color-green` | action, text | Highest-tier labels and buttons. |
| pricing pages | Plan purple | `#8d3eb5` | `--color-plan-purple` | text | Middle-tier name, paired with the ordinary orchid button. |
| use-case detail pages | Figure edge | `#d5d4d0` | `--color-figure-edge` | border | Visible result of 15% black over warm ivory; half-pixel outlines on detail-page media and badges. |
| pricing pages | Comparison band | `#f7f6f2` | `--color-table-band` | surface | Subtle grouped category bands in comparison tables. |

## Typography

- **Serrif Condensed** — Display headlines, section statements and pricing numerals. Tall, narrow editorial serif with sharp contrast, compact proportions and expressive bracketed forms. If unavailable, use **Instrument Serif**. Use regular 400; tune width before changing the tight tracking. Font stack: "Serrif Condensed", "Instrument Serif", Georgia, serif.
- **Unica77** — Support lines, body copy, navigation, buttons and names. Unadorned neo-grotesk, open and legible at regular weight; serves as the practical foil to the serif. If unavailable, use **Helvetica Neue**. If unavailable, use the freely available Libre Franklin at 400 with width tuning. Font stack: "Unica77", "Helvetica Neue", Arial, sans-serif.
- **Aeonik Fono** — Uppercase chapter labels, footer categories and figure captions. Technical, monospaced-looking lettering, compact and regular rather than heavy. If unavailable, use **IBM Plex Mono**. Font stack: "Aeonik Fono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Serrif Condensed | 400 | 110px | 1 | -0.02em | Primary opening statement; centered by default, left-aligned on detail and company narratives. |
| heading | Serrif Condensed | 400 | 48px | 50px | -0.01em | Section lead, equal-size muted continuation and closing call. |
| lead | Unica77 | 400 | 24px | 32px | -0.0037em | Opening support, testimonial quotes and FAQ questions. |
| body | Unica77 | 400 | 18px | 24px | -0.005em | Capability titles, captions, short explanatory paragraphs and attribution. |
| action | Unica77 | 400 | 16px | 20px | normal | Main capsule action. |
| footer-link | Unica77 | 400 | 16px | 1 | normal | Footer navigation links. |
| eyebrow | Aeonik Fono | 400 | 14px | 24px | 0.02em, uppercase | Numbered chapter marker, normally vermilion. |
| navigation | Unica77 | 400 | 14px | 20px | -0.006em | Small top navigation and sign-in links. |
| action-small | Unica77 | 400 | 14px | 18px | normal | Compact navigation button and plan actions. |
| caption | Unica77 | 400 | 14px | 16px | normal | Demo tab metadata, small badges and brief secondary labels. |
| footer-category | Aeonik Fono | 400 | 13px | 20px | normal, uppercase | Small muted headings above footer link groups. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | plan-price | Serrif Condensed | 400 | 48px | 1.1 | -0.0083em | Large annual price, with a smaller muted serif period suffix. |
| company narrative pages | letter | Serrif Condensed | 400 | 40px | 1.1 | -0.0022em | Long-form founder or company argument; links retain the surrounding serif scale. |
| use-case detail pages | figure-caption | Aeonik Fono | 400 | 12px | 16px | 0.007em, uppercase | Centered descriptive line beneath the full-width product figure. |

**Notes:**

- Keep the serif at weight 400 even at its largest scale. Display tracking tightens to -0.02em; section statements use -0.01em.
- A muted continuation is not a subtitle: it retains exactly the section heading's family, size, line height and weight.
- The sans hierarchy changes size rather than becoming bold. Technical uppercase labels are the only strongly coded annotation voice.
- The giant footer name is vector identity artwork, not another paragraph or display-heading recipe.

## Layout

**Density:** Airy at the page level, compact within working interfaces; long editorial pauses alternate with small practical labels.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Inset around the main button inside its email shell; icon-to-label gap in datasource badges. |
| 12px | Footer link spacing and capability text spacing below a visual. |
| 16px | Metadata-to-prompt spacing in demonstration tabs; compact inline groups. |
| 24px | Chapter label to section statement; FAQ vertical question padding. |
| 30px | Main twelve-column grid gutter and three-column groups. |
| 32px | Plan inner padding and normal text-group separation. |
| 40px | Opening statement to support and support to email form. |
| 56px | Vertical padding of testimonial rows. |
| 60px | Two-column capability grid gutters, both axes. |
| 64px | Heading-to-media group separation and compact section padding. |
| 80px | Closing call vertical padding and company-opening top padding. |
| 112px | Main chapter top and bottom padding. |
| 128px | Extra top or bottom breathing room at major transitions. |
| 160px | Footer top padding before link groups. |
| 180px | Footer pause between navigation and monumental identity. |

### Containers and grids

- **container**: max width 1266px · side padding 20px. Centered content width; at a 1440px viewport the content begins about 87px from each side. The side padding sits within an outer centered wrapper.
- **editorial grid**: 12 columns · gap 30px. Base alignment for section statements, media, split quotes and opening support.
- **capability grid**: 2 columns · gap 60px. Equal 603px-wide demonstrations, with neutral visual trays above free-standing captions.
- **three-column group**: 3 columns · gap 30px. 402px-wide demo selectors, footer navigation and company people lists.
- **hero support**: max width 618px. Centered two-line opening explanation beneath the display headline.
- **letter column** (only for company narrative pages): max width 834px. Left-aligned eight-column statement and long serif letter, leaving the right side conspicuously open.
- **plan grid** (only for pricing pages): 3 columns · gap 0px. Three contiguous columns inside one fine rectangular outline; no floating rounded plan cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action button | 60px |
|  | email shell | 50px |
|  | demonstration tray | 12px |
| use-case detail pages | detail figure | 10px |
| use-case detail pages | datasource badge | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| email shell | `rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px, rgba(0, 0, 0, 0.05) 0px 2px 8px -2px, rgba(0, 0, 0, 0.14) 0px 2px 10px -4px` | Soft shallow edge around the white email capsule. |
| large window | `rgba(38, 38, 38, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.2) 0px 2px 8px -4px` | Large browser-like product stage. |
| floating window | `rgba(38, 38, 38, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.16) 0px 8px 24px -6px, rgba(0, 0, 0, 0.14) 0px 18px 48px -12px` | Smaller assistant window overlapping the large product stage. |

### Surfaces

#### Ivory canvas · level 0

**Use:** Default canvas throughout the long explanatory body.

**CSS:** `background: #faf9f5; color: #000000`

**Observed:** Navigation, prose and testimonials share one continuous light material.

**Transfer:** Let content hierarchy and rules distinguish sections instead of alternating full-color bands.

#### Neutral visual tray · level 1

**Use:** Backing for repeated product demonstrations.

**CSS:** `background: rgba(0, 0, 0, 0.05); border-radius: 12px; overflow: hidden`

**Observed:** The neutral frame belongs to the visual only; title and support sit outside it.

**Transfer:** Frame a realistic working moment, leaving a visible border of neutral backing.

#### Browser window · level 2

**Use:** Main product proof stage.

**CSS:** `background: #fcfcfc; border-radius: 12px; box-shadow: rgba(38, 38, 38, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.2) 0px 2px 8px -4px`

**Observed:** A wide working interface has small browser chrome and a dense, credible document interior.

**Transfer:** Use an actual workflow or faithfully constructed interface, not abstract empty cards.

#### Floating assistant window · level 3

**Use:** Secondary view in overlapping product explanations.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: rgba(38, 38, 38, 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.16) 0px 8px 24px -6px, rgba(0, 0, 0, 0.14) 0px 18px 48px -12px`

**Observed:** A narrower window overlaps the lower-right area of the larger working document.

**Transfer:** Show the conversational or downstream consequence of the primary operation.

#### Lavender ending wash · level 0

**Use:** Continuous atmosphere beneath the final call, footer links and oversized identity.

**CSS:** `background: linear-gradient(#faf9f5, #ddc3e5)`

**Observed:** Lavender gradually accumulates downward; the footer does not look like a separate boxed panel.

**Transfer:** Match the broad soft wash; exact stops are not essential. Keep text black and preserve the pastel edge-bar layer.

#### Comparison category band · level 1

**Only for:** pricing pages

**Use:** Grouped table section rows.

**CSS:** `background: #f7f6f2; border-bottom: 1px solid rgba(0, 0, 0, 0.08)`

**Observed:** Very low contrast category strips distinguish feature families without breaking the continuous table.

**Transfer:** Use for genuine comparison groups, not as a decorative stripe pattern.

## Components

### Sticky navigation

**Use:** Persistent small-scale orientation and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 200; height: 52px; background: #faf9f5`

**Text style:** `navigation` — Unica77 400 · 14px/20px · tracking -0.006em

**Observed:** Compact identity at left, three navigation choices centered, sign-in and a small email capsule at right. The inner grid is 1fr auto 1fr with 24px between central links.

**Transfer:** Retain the unusually restrained header scale; prioritize the identity and conversion on tighter layouts.

### Primary button

**Use:** Default conversion action inside an email shell.

**CSS:** `background-color: #b074ce; background-image: linear-gradient(rgba(0, 0, 0, 0) 75%, rgba(0, 0, 0, 0.04) 100%); color: #ffffff; border-radius: 60px; padding: 12px 18px; height: 44px; border: none`

**Text style:** `action` — Unica77 400 · 16px/20px

**Observed:** Short white label; normally nested at the right of the white form, not paired with an outlined secondary button. Pricing variants use vermilion, orchid and green in corresponding tier order.

**States:** Declared: hover background-color color-mix(in srgb,#000 12%,#B074CE), box-shadow none, border-style none; focus-visible unknown; active box-shadow rgba(0, 0, 0, 0.17) 0px 1px 3px 0px inset.

**Transfer:** Use one short verb phrase and preserve the nested action relationship.

### Email capsule

**Use:** Main opening and closing conversion form.

**CSS:** `display: flex; position: relative; align-items: center; width: 380px; height: 56px; background: #ffffff; border-radius: 50px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 0px 0.5px, rgba(0, 0, 0, 0.05) 0px 2px 8px -2px, rgba(0, 0, 0, 0.14) 0px 2px 10px -4px`

**Observed:** The input spans the shell with 28px left padding and 150px reserved on the right; Primary button sits 6px inside the edge. Header variant is 220×34px with a 96×26px button. Plan variant is about 356×42px with a 96×30px action.

**Transfer:** Use a real email input and keep the reserved action space; do not treat the shell as a single button.

### Compact button

**Use:** Action in the persistent header; reduced-height variant for plan forms.

**CSS:** `background-color: #b074ce; color: #ffffff; border-radius: 60px; padding: 4px 12px; height: 26px; border: none`

**Text style:** `action-small` — Unica77 400 · 14px/18px

**Observed:** The header button is inset 4px in a shallow white capsule. Plan actions increase vertical padding to 6px and height to 30px.

**States:** Declared: hover background-color color-mix(in srgb,#000 12%,#B074CE), box-shadow none; focus-visible unknown; active box-shadow rgba(0, 0, 0, 0.17) 0px 1px 3px 0px inset.

### Demonstration selector

**Use:** Prompt-based switching above the large product video.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 16px 0px 32px; border-bottom: 1px solid rgba(0, 0, 0, 0.1); opacity: 0.55`

**Text style:** `body` — Unica77 400 · 18px/24px · tracking -0.005em

**Observed:** Three equal columns carry a small muted role label above a practical task prompt. Inactive choices fade; the active prompt is black with a thin progress marking near its lower edge.

**Transfer:** Write selectors as jobs a reader could actually request, not abstract feature names.

### Capability tile

**Use:** Repeated product-operation explanation.

**CSS:** `display: flex; flex-direction: column; gap: 12px`

**Text style:** `body` — Unica77 400 · 18px/24px · tracking -0.005em

**Observed:** Neutral visual tray first, then a short black title and muted support. The visual is 603×402px within a roughly 603×510px tile; two columns have a 60px gutter.

**Transfer:** Use one clear operation per tile; the caption must explain the product moment shown.

### Testimonial row

**Use:** Long-form social proof without a carousel or card mosaic.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); column-gap: 30px; padding: 56px 0px; border-bottom: 1px solid rgba(0, 0, 0, 0.08)`

**Text style:** `lead` — Unica77 400 · 24px/32px · tracking -0.0037em

**Observed:** Quote occupies about half the row at left. Right-hand attribution pairs a small square portrait with name and muted role, followed by a monochrome company mark. The first row also has a top rule.

**Transfer:** Use evidence-rich quotes with a concrete before-and-after consequence.

### Footer link group

**Use:** Sparse grouped navigation above the oversized identity.

**CSS:** `display: flex; flex-direction: column; gap: 12px`

**Text style:** `footer-link` — Unica77 400 · 16px/1

**Observed:** Three equal columns, each introduced by a muted uppercase technical category. No enclosing cards; ordinary links are black.

**States:** Declared: hover text-decoration underline; focus-visible unknown.

**Transfer:** Use a small number of real destinations and maintain the large pause before the identity.

### Plan column

**Only for:** pricing pages

**Use:** Contiguous annual plan summary.

**CSS:** `display: flex; flex-direction: column; padding: 32px; background: #faf9f5; border-left: 1px solid rgba(0, 0, 0, 0.08)`

**Text style:** `body` — Unica77 400 · 18px/24px · tracking -0.005em

**Observed:** Colored tier name, single-sentence promise, serif annual price with smaller period suffix, email form, then a compact checked feature list. The first column shares the group's outside edge rather than duplicating its left separator.

**Transfer:** Color-code names and actions, not the entire plan background.

### FAQ question

**Only for:** pricing and objection-handling sections

**Use:** Expandable objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 32px; padding: 24px 0px; border-bottom: 1px solid rgba(0, 0, 0, 0.1)`

**Text style:** `lead` — Unica77 400 · 24px/32px · tracking -0.0037em

**Observed:** Question at left, 24px thin-stroke plus at far right, fine horizontal rule below; first row also has a top edge. Questions form a full-width list.

**Transfer:** Keep questions conversational and direct; use the same restrained list even with fewer items.

### Datasource badge

**Only for:** use-case detail pages

**Use:** Compact integration metadata beneath the display title.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 6px 12px; background: #ffffff; border: 0.5px solid rgba(0, 0, 0, 0.15); border-radius: 16px`

**Text style:** `caption` — Unica77 400 · 14px/16px

**Observed:** Small service icon before the name; badges wrap with 8px gaps rather than becoming a feature-card grid.

**Transfer:** List only services genuinely relevant to the demonstrated workflow.

### Comparison cell

**Only for:** pricing pages

**Use:** Tabular plan comparison.

**CSS:** `background: #faf9f5; padding: 12px 16px; border-right: 1px solid rgba(0, 0, 0, 0.08); border-bottom: 1px solid rgba(0, 0, 0, 0.08)`

**Text style:** `body` — Unica77 400 · 18px/24px · tracking -0.005em

**Observed:** One wider left feature column and three centered plan columns. Header cells are sticky; grouped category bands span the table. Simple checks and crosses replace decorative icons.

**Transfer:** Preserve alignment and visible grid lines; use the subtle Comparison category band for group headings.

## Imagery and graphics

### Pastel edge bars

**Use:** Signature peripheral artwork around the first promise and final call.

**Observed:** Short translucent rectangular bars, with square corners and stepped offsets, enter from both viewport edges. Orchid, aqua, lemon and pale rose fade horizontally toward the empty center. Bars are roughly 32px high, often grouped in pairs or short stacks; the original background field is 2400px wide and clipped by the viewport.

**Transfer:** Keep this motif when no equivalent brand artwork exists; rebuild it with rectangles rather than substituting a stock illustration.

**Build:** Use an absolutely positioned SVG or overflow-hidden layer behind text. Place 32px-high rectangles in staggered stacks at both edges, mostly 80–210px wide in the visible region; vary their start by about 40px. Fill with horizontal gradients from rgba(176,116,206,0.35), rgba(181,238,234,0.8), rgba(248,237,154,0.8) or rgba(244,206,203,0.6) to zero alpha. Keep the central text field clear. In the ending use orchid-only bars with lower contrast over the lavender wash; do not blur away the rectangular edges.

### Working product windows

**Use:** Main proof chapters and repeated capability demonstrations.

**Observed:** Large light browser/document interfaces with realistic tables, charts, formula rows and compact chrome. One substantial stage is about 980×640px, overlapped by a 470×520px conversational window. Repeated examples crop working interfaces inside neutral trays, often leaving bottom content clipped to imply continuation.

**Transfer:** Use your own product's real workflow, with believable populated data. If no interface exists, construct one polished example showing input, operation and meaningful output; retain light materials and fine neutral edges.

### Exploded paper system

**Use:** Explanation of how a product's layers work together.

**Observed:** Three large isometric sheets float diagonally, occupying about two thirds of the section width; concise labels align down the right. Hairline black drawings describe a dashboard-like top sheet, a gridded middle and a connector foundation. Pale orchid, aqua and lemon tints distinguish layers, with diffuse shadows between them.

**Transfer:** Translate the actual product architecture into a few readable layers. Minimum version: three fine-line SVG parallelograms with distinct schematic contents and aligned side labels.

**Build:** Draw three matching SVG parallelograms roughly 800px wide, with vertices forming a shallow isometric diamond. Offset each layer downward about 160px. Use 1px rgba(0,0,0,0.65) outlines and very low-alpha orchid, aqua and lemon fills. Add blurred black ellipses or SVG drop shadows beneath each sheet at 8% opacity. Top layer: small chart and text-line blocks; middle: a fine grid; bottom: small connector blocks. Keep generous empty sheet area and no glossy bevels.

### Monochrome proof field

**Use:** Opening social proof and testimonial attribution.

**Observed:** Black company marks on the ivory canvas; the opening arranges fifteen compact marks in a loose five-column, three-row field. No logo cards or colorful badges. Small square portrait thumbnails appear beside testimonial identities.

**Transfer:** Use authentic permissioned proof at a consistent optical scale. When few marks exist, use fewer marks with the same breathing room rather than enlarging one to dominate.

### Monumental identity

**Use:** Signature finale beneath footer navigation.

**Observed:** A broad black vector wordmark and symbol nearly fill the 1266px container width and stand 261px high. The identity sits directly on lavender with small legal text at its lower edge.

**Transfer:** Render the new identity as a clean vector at comparable breadth. Without custom artwork, set the new name in a heavy, carefully spaced sans as one deliberate graphic lockup.

**Build:** Create an SVG with a viewBox matching the identity's wide aspect ratio, using outlined text or custom paths. Scale to the content width while preserving proportions; reserve about 261px height at 1440px viewport width and keep 180px between link groups and the identity. Use solid black with no texture, glow or extrusion.

### People directory

**Only for:** company narrative pages

**Use:** Human proof beneath the long-form letter.

**Observed:** Small 80×80px square color portraits on pale neutral backgrounds, each beside a name and muted role. A three-column list with 30px gutters avoids large biography cards; portraits feel natural rather than studio-glossy.

**Transfer:** Use consistent square crops of real people, with ordinary names and roles, not ornamental illustrations or oversized lifestyle photography.

### Icons

**Observed:** Marketing controls are spare: checks in plan lists, 16px support icons, 14px service marks in badges and 24px black plus signs in the FAQ. FAQ strokes are 1.5px with butt caps; smaller comparison support icons can use 1.3px rounded strokes.

**Transfer:** Choose tiny functional symbols with consistent optical weight. Use icons to indicate state or service identity, not as colorful decoration above every feature.

## Section recipes

How recurring sections are built.

### First screen: Editorial question opening

**Observed:** A 52px Sticky navigation sits above a centered 110px serif question. The headline occupies about three quarters of the content width but the ink itself remains a single compact line. After a 110px top pause, the headline leads to a 618px-wide two-line support paragraph with a 40px gap, then an Email capsule after another 40px. Behind them: Ivory canvas, clipped Pastel edge bars at the far sides, then the text and form in front. A broad Monochrome proof field occupies the lower part of the first 900px; headline, support, complete action and three rows of logos are visible. No large product window competes above the fold; the first detailed working demonstration starts below this screen.

**Transfer:** Ask a short category-changing question and pair it with one grounded explanatory sentence. Rebuild the edge bars and use permissioned proof or a compact typographic proof field if interface media is unavailable. Detail pages instead left-align the same display type above metadata, a short paragraph, form and a large figure; pricing centers a one-word title above contiguous plans; company narratives left-align a multiline statement over the serif letter.

**Avoid:** Do not replace the opening with a split-screen dashboard hero, a full-bleed illustration, two side-by-side CTA buttons or a bold sans headline.

**Text style:** `display` — Serrif Condensed 400 · 110px/1 · tracking -0.02em

### Numbered heading pair

**Observed:** Eyebrow sits 24px above a 48px serif statement. The next clause is equally large but uses 60%-black text, usually on the following line. Main chapters have 112px top and bottom padding, with 64px or more before the supporting media.

**Transfer:** Use the black line for the outcome and the muted line for the durable mechanism or reassurance; number the chapters when it helps navigation.

**Text style:** `heading` — Serrif Condensed 400 · 48px/50px · tracking -0.01em

### Demonstration chapter

**Observed:** Numbered heading pair precedes either Browser window plus Floating assistant window or three Demonstration selectors above a broad product video. Selectors use 30px gutters and have a 64px top separation from the statement.

**Transfer:** Show both the underlying work and the answer it enables, using realistic product content rather than explanatory prose alone.

### Capability operations grid

**Observed:** Capability tiles form two equal columns with 60px gutters. Each tile has a 603×402px Neutral visual tray, then title and muted explanatory copy outside the tray, with 12px text spacing.

**Transfer:** Group practical operations by what the reader wants to accomplish; vary the interface content while maintaining the tray and caption construction.

### Architecture explanation

**Observed:** A Numbered heading pair spans the section top; Exploded paper system fills the large left area with three aligned short explanations on the right. The illustration remains line-drawn and pale rather than a dark technical diagram.

**Transfer:** Explain relationships between a few real system layers. Keep labels short enough that the illustration remains the dominant explanatory object.

### Ruled social proof

**Observed:** A serif introduction is followed after 64px by full-width Testimonial rows. Each row uses 56px vertical padding, a left quote and a right portrait/name/role/mark block separated by generous empty columns.

**Transfer:** Use successive quotes to address different practical outcomes, without turning them into an animated card carousel.

**Text style:** `lead` — Unica77 400 · 24px/32px · tracking -0.0037em

### Detail figure

**Observed:** Left-aligned display title follows a back link; Datasource badges appear 40px below it. A compact explanation and left-aligned Email capsule precede a full-container product figure. The figure has a 0.5px edge, 10px corners and a very soft shadow; a centered uppercase figure-caption follows at 16px separation.

**Transfer:** Use this compact opening for a single workflow or artifact, and let the large demonstration carry most of the page.

**Text style:** `display` — Serrif Condensed 400 · 110px/1 · tracking -0.02em

### Company letter and directory

**Observed:** An 834px-wide left-aligned display statement opens over an equally wide 40px/1.1 serif letter, separated by 64px. Paragraphs and inline blue links make the argument. A 48px heading introduces the People directory; a separate restrained logo row supplies institutional proof.

**Transfer:** Use only for a genuine company or founder narrative. Follow a specific argument with human and institutional credibility, not a generalized marketing feature grid.

**Text style:** `letter` — Serrif Condensed 400 · 40px/1.1 · tracking -0.0022em

### Pricing and objections

**Observed:** Centered display title with Pastel edge bars leads to three contiguous Plan columns. Monochrome proof precedes a full-width comparison table with fine grid lines and category bands. Ruled social proof follows, then FAQ questions beneath a 48px serif lead.

**Transfer:** Use tier color sparingly on names and small actions. Let the table resolve factual comparison and the questions resolve buying objections.

### Lavender close and giant identity

**Observed:** A centered two-line 48px serif call has 80px vertical section padding and a 380×56px Email capsule about 38px below the text. Orchid edge bars flank it. Lavender ending wash continues behind the footer: 160px top padding, three Footer link groups, then 180px of separation before Monumental identity. Small legal text is aligned along the bottom. This ending is shared across all page types; the detail variant adds a 24px support line beneath the call.

**Transfer:** Finish with one crisp contrast between the old pain and the new dependable outcome. Preserve the continuous colored atmosphere and oversized identity even on a short page; adapt link count to genuine destinations.

**Text style:** `heading` — Serrif Condensed 400 · 48px/50px · tracking -0.01em

## Page flow

**Storyline:** category promise → working proof → practical operations and underlying mechanism → human proof → final conversion and monumental identity

### Broad product or marketing landing page

1. **Promise and early credibility** — Centered editorial question, short support, email action and monochrome proof field.
2. **Working demonstration** — Numbered heading pair over overlapping document and assistant views.
3. **Capability chapters** — Prompt selectors and large demonstration, followed by two-column practical operation tiles.
4. **Mechanism** — Fine-line exploded system illustration with aligned side labels.
5. **Social proof** — Ruled testimonial rows with separate attribution blocks.
6. **Closing call and navigation** — Lavender conversion close, sparse link groups and enormous black identity.

**Transfer:** Borrow the progression from promise to concrete work to trust; vary the number and order of middle chapters to fit the product.

### Focused workflow or use-case detail

1. **Orientation and promise** — Back link, left-aligned display title, small integration badges, explanatory paragraph and email form.
2. **Product demonstration** — One full-width dashboard figure with a tiny uppercase descriptive caption.
3. **Closing call and navigation** — Shared lavender call, an added support line, footer links and monumental identity.

**Transfer:** Keep the page narrow in purpose and let one convincing artifact replace a long feature story.

### Buying and comparison page

1. **Pricing** — Centered title and three contiguous annual plan columns with color-coded small actions.
2. **Credibility** — Restrained monochrome company marks.
3. **Comparison** — Dense but light ruled table with sticky plan headers and grouped category strips.
4. **Social proof** — Large quote rows support the purchase decision.
5. **Objection handling** — Full-width FAQ list with plus controls.
6. **Closing call and navigation** — Shared lavender conversion and oversized identity ending.

**Transfer:** Keep financial facts easy to scan; use color for tier identity, not a recommendation badge invented for the middle plan.

### Company or founder narrative

1. **Mission** — Large left-aligned multiline serif opening.
2. **Argument** — Long 40px serif letter with inline blue references and a personal sign-off.
3. **Human proof** — Small square portraits in a three-column directory.
4. **Institutional proof** — A separate heading and understated investor marks.
5. **Closing call and navigation** — The same lavender call, link groups and giant black identity.

**Transfer:** Use the letter variant for a point of view with a real argument; keep the commercial page's shared ending intact.

## Writing

Confident and specific, with an editorial point of view and occasional conversational bite. The product is explained through useful work and dependable outcomes rather than visionary abstractions.

**Do not copy:** Do not reuse Equals names, identity artwork, customer logos, testimonial text or attribution, proprietary product labels, pricing, dates, performance figures or category claims. Source examples illustrate syntax and tone only; new claims need the new product's own substantiation.

- **Addressing the reader:** Address the reader and their team directly with you and your. Use we for a genuine company argument, and name the product when explaining a mechanism.
- **Rhythm:** Short question or contrast headlines; one-sentence support lines; practical imperative titles. Longer quotes remain conversational. The company letter alternates argumentative paragraphs with abrupt short sentences.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A pointed category question with familiar language. | 3–6 words | “What’s after Excel?” |
| Supporting line | Name the product category, then balance the engineering promise with a human trust benefit. | One sentence, about 15–22 words | “[Brand] is the first new spreadsheet in 20 years, engineered for AI, designed for trust.” |
| Section heading pair | Concrete outcome followed by a shorter reassurance or mechanism. | Two brief clauses | “A single source of truth for the entire team. Same question? Same answer.”<br>“Wire your numbers into how your company operates. A system, not an artifact.” |
| Operation title | Verb plus the useful object or beneficiary. | 3–5 words | “Brief your team”<br>“Verify any number” |
| Primary action | Direct verb, no flourish. | 3 words | “Get a demo” |
| Closing call | Stop the unreliable behavior; start the dependable alternative. | Two short sentences | “Stop vibe-coding your numbers. Start trusting them.” |
| Buying question | Ask what a real buyer would ask without a promotional premise. | 5–10 words | “Is there a separate cost for implementation?” |

**Words and phrasing to use:** trust; build once; same answer; team; verify; sync; source; real-time; backed by; no back-and-forth

**Avoid:** revolutionary; supercharge; 10x everything; magic; limitless possibilities; game-changing as an unsupported narrator claim

**Rules:**

- Show the action and its operational consequence in the same support sentence.
- Contrast a brittle old way with a durable new one, but keep the promise technically grounded.
- Use product nouns and real tasks instead of adjective stacks.
- Keep numerals and comparative claims tied to proof; quotations can sound less formal than the surrounding narrative.
- Use the chapter label for a terse concept, not another long headline.

## Do's and Don'ts

### Do

- Keep the opening serif at 110px/1 and weight 400 on the desktop composition.
- Give muted second clauses the same 48px/50px recipe as the black first clause.
- Keep the email shell 380×56px with a 44px action inset by 6px.
- Use 30px gutters for the base grid and 60px for paired capability demonstrations.
- Keep large media corners at 10–12px while plan columns remain square.
- Use 56px vertical padding and fine 8%-black rules around testimonial rows.
- Retain pastel edge bars and a continuous lavender closing atmosphere.
- Give the final identity almost the full 1266px content width and a deliberate 180px pause above it.

### Don't

- Do not turn 14px chapter labels into big filled badges; they are small uppercase annotations.
- Do not use 700-weight section headlines; the regular narrow serif is the main contrast device.
- Do not use black-filled primary buttons in place of the orchid capsule action.
- Do not carry the lavender background through every middle chapter; the long explanatory body stays ivory.
- Do not wrap capability titles and descriptions inside the neutral visual tray.
- Do not round pricing columns into detached 24px-radius cards or add deep card shadows.
- Do not recolor monochrome proof marks into a multicolor logo wall.
- Do not enlarge people portraits into full-width biography imagery; the directory uses small 80px squares.

## Motion and responsive

### Motion

**Observed:**

- Declared button background-color transition is 0.15s ease-out; email-shell box-shadow transition is 0.1s ease-out.
- Declared link underline transition is text-decoration 0.1s ease-out.
- Demonstration tab progress uses build-tab-progress 7s linear forwards.
- The opening background artwork declares opacity 0.3s ease-in-out.

**Transfer:**

- Use the short color transition for nested capsule actions and the seven-second progress device only for timed demonstration selectors.
- Keep the pastel artwork subordinate; its role is atmospheric framing, not a distracting foreground animation.

**Unknown:**

- Exact demonstration animation sequences and scroll triggers are not established.
- A focus-visible visual treatment is not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 560px, 700px, 767px, 768px, 1100px, 1101px, 1150px and 1280px.
- Some large edge artwork and the wide comparison table are marked desktop-only.

**Transfer:**

- For a narrow layout, preserve the serif-to-grotesk contrast, nested email action and peripheral bars while reducing the headline to fit the available line length.
- Stack paired demonstrations and testimonial attribution; keep tray captions outside the visual and retain the continuous lavender ending.
- Scale the final vector identity proportionally rather than forcing a fixed 261px height into a narrow viewport.

**Unknown:**

- Actual narrow-screen type sizes, menu behavior, comparison-table replacement and mobile artwork are not established; these transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
