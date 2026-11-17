# visitors.now — friendly instruments, lavender landscapes

## Overview

A bright, approachable software style with rounded sans-serif lettering, compact floating controls and unusually playful product demonstrations. White and pale gray dominate, with lavender actions and small green, blue, pink and amber signals. Colorful landscape backdrops and oversized circular artwork bring warmth to an otherwise orderly, moderately dense interface-led story.

### Essentials

- A small dark control island floats above a light page: the navigation is 460px × 52px, fixed 32px from the top, with 24px corners; dark surfaces remain concentrated in this island and tiny readouts.
- The promise is narrow rather than panoramic: a centered 448px headline block uses OpenRunde 60px/68px, weight 600 and -0.05em tracking, followed by 18px/24px support and paired 44px pill actions.
- Lavender is the conversion color, not the page color: #918df6 fills the primary pills and marks selected data, while white and near-white surfaces occupy almost all the surrounding area; green, blue, pink and amber label individual capabilities.
- The product sits in a landscape, not a generic browser mockup: a 984px-wide white interface is staged over a full-bleed soft violet and pink mountain scene, with a white scalloped tab notch above it. Recreate a simplified layered landscape if photographic media is unavailable.
- Capabilities are working miniatures: 16px-radius gray cards combine a colored 24px/28px lead, equally sized dark benefit text, tiny utility lists and a substantial cropped visualization in the lower half. Use legible bars, activity rows or a spatial model when the new product has no rich demo.
- The ending becomes graphic architecture: beneath small muted footer columns, a monumental pale lavender ring and a smaller saturated ring rise from the bottom edge, cut off by an 8px blue-to-lavender baseline. Carry this oversized geometric brand gesture into every new page using original circles or an equally simple brand-derived shape.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender | `#918df6` | `--color-accent` | action, accent, text, border | Primary actions, selected column outlines, step numbers and highlighted quantities. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Amber | `#ffa600` | `--color-amber` | text, accent | Performance-related capability accents and service-status dots. |
| Clear blue | `#2c78fc` | `--color-blue` | text, accent | A capability title and announcement accents, rather than large page fills. |
| Profile pink | `#d6409f` | `--color-pink` | text, accent | A capability title and matching small icons. |
| Fresh green | `#33c758` | `--color-green` | text, accent | Capability titles and positive quantitative signals; contained within demonstrations and small labels. |
| Soft sky | `#bed5fe` | `--color-sky` | accent | Left end of the thin closing gradient. |
| Pale sky | `#ebf2ff` | `--color-sky-light` | accent | Middle of the thin closing gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Navigation black | `#14141f` | `--color-nav` | surface | Floating navigation and compact dark data badges. |
| Midnight ink | `#181925` | `--color-ink` | text | Headlines, card benefits and primary labels. |
| Body gray | `#666666` | `--color-body` | text | Supporting paragraphs and secondary actions. |
| Muted gray | `#999999` | `--color-muted` | text | Footer links, quiet labels and auxiliary information. |
| Silver navigation text | `#bbbcc3` | `--color-nav-text` | text | Links on the dark navigation island. |
| Hairline gray | `#e8e8e8` | `--color-rule` | border | Comparison-table separators. |
| Soft gray | `#f7f7f7` | `--color-card` | surface | Visible card and secondary-button wash; rgba(0,0,0,0.03) over white. |
| Almost white | `#fafafa` | `--color-subtle` | surface | FAQ rows and closing callout. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, white interface stages and text on colored actions. |

## Typography

- **OpenRunde** — All marketing headlines, body copy, navigation and controls. A rounded contemporary sans with soft terminals and friendly, open counters; medium weights dominate. If unavailable, use **Inter**. Use weights 400–600 and preserve the tight spacing; its terminals will be less rounded. Font stack: "OpenRunde", "Open Runde", Inter, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | OpenRunde | 600 | 60px | 68px | -0.05em | Centered opening promise, balanced over two lines. |
| heading | OpenRunde | 500 | 36px | 44px | -0.0175em | Default section heading and closing headline. |
| heading-tight | OpenRunde | 500 | 36px | 44px | -0.05em | Capability overview and comparison headings; a tighter alternate for these dense heading groups. |
| feature-lead | OpenRunde | 500 | 24px | 28px | -0.0133em | Colored capability name and dark benefit sentence within a card. |
| lead | OpenRunde | 500 | 18px | 24px | -0.018em | Opening support, larger section support and compact benefit descriptions. |
| body | OpenRunde | 500 | 16px | 1.5 | -0.02em | Default support paragraphs, main actions and FAQ questions. |
| small | OpenRunde | 500 | 14px | 20px | -0.023em | Navigation, section tags, learn-more actions and footer text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| interactive pricing demonstrations | quantity | OpenRunde | 500 | 48px | 1 | -0.0067em | Highlighted usage quantity and adjacent simulated activity metric. |

**Notes:**

- Use one rounded family throughout rather than introducing an editorial serif or technical monospace.
- Headlines get tighter as their visual footprint grows: the display and tight section variant use -0.05em, while small text generally keeps -0.3px.
- Color is often a semantic break within a single typographic sentence: a colored feature name continues into a dark benefit with the same 24px/28px recipe.

## Layout

**Density:** Airy between chapters, compact within controls and working demonstrations; large white margins frame tightly organized product detail.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing and tight control groups. |
| 12px | Feature-header content stack. |
| 16px | Grid gutters and opening text/action stack gaps. |
| 20px | Section heading-stack gaps and page side padding. |
| 24px | Vertical feature-card padding and pricing content spacing. |
| 32px | Feature-card horizontal padding and pricing panel inset. |
| 48px | Heading group to section content. |
| 64px | Main section top and bottom padding; broad opening gaps. |
| 160px | Opening top whitespace before the announcement. |

### Containers and grids

- **main-container**: max width 1024px · side padding 20px. Centered outer wrapper, including padding; yields 984px of usable content on desktop.
- **heading-container**: max width 768px · side padding 20px. Centered section-introduction wrapper; heading and support text narrow further to 384–512px.
- **opening-copy**: max width 448px. Narrow centered headline and opening support.
- **feature-grid**: 2 columns · gap 16px. Equal 484px-wide large cards; a smaller utility-card pair can follow.
- **step-grid**: 3 columns · gap 16px. Three equal approximately 317px-wide demonstration cards.
- **faq-container**: max width 576px · side padding 20px. 536px-wide question stack centered beneath its heading.

## Corner radius

| Element | Radius |
| --- | --- |
| action-pills | 9999px (pill) |
| feature-cards | 16px |
| faq-rows | 12px |
| closing-panel-and-navigation | 24px |
| section-tags | 6px |
| product-image | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| small-control | `0px 1px 1px rgba(0,0,0,0.08), 0px 0px 0px 1px rgba(0,0,0,0.05)` | Small white learn-more pills and the navigation island. |
| product-stage | `0px 1px 3px rgba(0,0,0,0.08), 0px 0px 0px 1px rgba(0,0,0,0.02)` | Barely raised product interface image. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous light page background.

**CSS:** `background: #ffffff`

**Observed:** White margins separate almost all major blocks.

**Transfer:** Keep the page light even when the product itself has richer interface colors.

#### Soft card · level 1

**Use:** Capability cards, process cards and the shared pricing panel.

**CSS:** `background: rgba(0,0,0,0.03); border-radius: 16px; overflow: hidden`

**Observed:** Flat, borderless gray modules; clipped art can meet the lower and side edges.

**Transfer:** Use content and clipping rather than heavy elevation to establish depth.

#### Subtle closing panel · level 1

**Use:** Final invitation before the footer.

**CSS:** `background: #fafafa; border-radius: 24px; padding: 64px 32px`

**Observed:** A full-container panel surrounding a narrow centered text stack.

**Transfer:** Repeat the original conversion pair without adding decorative cards inside.

#### Landscape stage · level 0

**Use:** Full-width backing for the principal product demonstration.

**CSS:** `position: relative; overflow: hidden; padding: 112px 0px 80px`

**Observed:** Soft-focus lilac, violet and pink mountains sit behind a sharp white interface; a white tab notch interrupts the top edge.

**Transfer:** Use the Landscape demonstration imagery recipe; maintain sharp interface detail against a soft expansive background.

## Components

### Floating navigation

**Use:** Persistent compact navigation above the page.

**CSS:** `position: fixed; top: 32px; left: 50%; transform: translateX(-50%); width: 460px; height: 52px; background: #14141f; border-radius: 24px; backdrop-filter: blur(16px); box-shadow: 0px 1px 1px rgba(0,0,0,0.08), 0px 0px 0px 1px rgba(0,0,0,0.05); z-index: 99`

**Text style:** `small` — OpenRunde 500 · 14px/20px · tracking -0.023em

**Observed:** A compact white emblem leads muted links, then login and a smaller purple register pill. It stays centered while the page scrolls.

**Transfer:** Keep a short set of primary destinations rather than expanding to a full-width header.

### Primary button

**Use:** Main conversion action in opening, pricing and closing.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 0px 20px; gap: 8px; background: #918df6; color: #ffffff; border-radius: 9999px`

**Text style:** `body` — OpenRunde 500 · 16px/1.5 · tracking -0.02em

**Observed:** A simple text-only pill, paired with the Secondary button in the opening and closing.

**States:** Declared: hover opacity 0.9; focus-visible outline-style none with no visible shadow.

**Transfer:** Use one clear acquisition verb and a short offer.

### Secondary button

**Use:** Lower-commitment companion to the primary action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 0px 20px; background: rgba(0,0,0,0.03); color: #666666; border-radius: 9999px`

**Text style:** `body` — OpenRunde 500 · 16px/1.5 · tracking -0.02em

**Observed:** Text-only, same height as the primary action, with a 16px gap between the pair.

**States:** Declared: hover background-color rgba(0,0,0,0.05) and color #666666; focus-visible outline-style none with no visible shadow.

### Learn more pill

**Use:** Small navigation action inside capability cards.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 32px; padding: 0px 6px 0px 10px; gap: 4px; background: #ffffff; color: #181925; border-radius: 9999px; box-shadow: 0px 1px 1px rgba(0,0,0,0.08), 0px 0px 0px 1px rgba(0,0,0,0.05)`

**Text style:** `small` — OpenRunde 500 · 14px/20px · tracking -0.023em

**Observed:** Label followed by a small right chevron; sits after a compact utility list and before the main visualization.

### Section tag

**Use:** Quiet category marker above recurring section headings.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 24px; padding: 0px 8px; background: rgba(0,0,0,0.03); color: rgba(0,0,0,0.4); border: 1px solid transparent; border-radius: 6px`

**Text style:** `small` — OpenRunde 500 · 14px/20px · tracking -0.023em

**Observed:** Sentence-case label, centered and visually much weaker than the heading below.

### Feature card

**Use:** A self-contained product capability with explanatory text and a working miniature.

**CSS:** `display: flex; flex-direction: column; background: rgba(0,0,0,0.03); border-radius: 16px; overflow: hidden; min-height: 280px`

**Text style:** `feature-lead` — OpenRunde 500 · 24px/28px · tracking -0.0133em

**Observed:** Header inset 24px vertically and 32px horizontally; a colored icon in a white lozenge precedes colored title, dark benefit, small utility list and Learn more pill. Large cards are 484px × 658px; their lower visual is allowed to overflow and clip.

**Transfer:** Replace the data with a coherent example of the new product, not unrelated decorative widgets.

### FAQ row

**Use:** Compact objection-handling accordion.

**CSS:** `background: #fafafa; border-radius: 12px; min-height: 44px; overflow: hidden`

**Text style:** `body` — OpenRunde 500 · 16px/1.5 · tracking -0.02em

**Observed:** Full-width question action has 10px top/bottom, 16px left and 12px right padding. A lavender 16px chevron sits at the far right; rows are separated by 2px. The full stack is 536px wide on desktop.

**Transfer:** Keep questions short enough to scan; preserve the narrow stack.

### Footer links

**Use:** Low-emphasis destination groups and a short human brand note.

**CSS:** `color: #999999; display: flex; flex-direction: column; gap: 4px`

**Text style:** `small` — OpenRunde 500 · 14px/20px · tracking -0.023em

**Observed:** Dark group headings sit above gray links. A 288px-wide descriptive note and a service-status line occupy the left side; link groups form two columns on the right.

**States:** Declared: hover color #666666.

**Transfer:** Use concise functional categories and a truthful status label.

## Imagery and graphics

### Landscape demonstration

**Use:** The principal product stage below the opening promise.

**Observed:** An expansive violet and rosy mountain landscape is soft, hazy and low in detail. A sharp, nearly full-container white interface floats over it with 8px corners and very slight elevation. The scene is the first large color field, while the promise above remains completely white.

**Transfer:** Show the new product's clearest single screen against an original landscape in the same cool-pink atmosphere. A well-composed interface facsimile is sufficient when production assets are unavailable.

**Build:** Create a full-width landscape layer behind the interface. As a minimum version, use three overlapping SVG mountain silhouettes with broad uneven ridgelines: a pale lavender sky, a distant pink-lilac ridge and a nearer violet ridge. Soften the rear layers with 12–24px blur and keep contrast low. Add a translucent lavender wash; leave the foreground white interface crisp. Cut a centered 466px-wide, 52px-deep white tab tray into the stage top, with 32px lower corners and matching concave shoulder cutouts.

### Working product miniatures

**Use:** Lower halves of capability cards and upper panels of process cards.

**Observed:** Realistic short bar lists, visitor rows, score readouts and a large terrestrial globe give each card its own focal object. The globe has cyan water, pale green land, map labels and small multicolored pins, cropped firmly at card edges. Process illustrations use blurred neighboring logos or a single integration mark above a divider.

**Transfer:** Use the new product's equivalent high-signal miniatures with believable data. Keep a large clipped spatial or diagrammatic visual among the flatter lists; if no spatial concept fits, use a simple original process model with colored nodes.

**Build:** For list-based miniatures, make 36px horizontal rows with pale neutral bars, green-tinted value segments, a small left icon and a right-aligned value. For a spatial fallback, use a large pale sphere or circular diagram rising from the lower edge, add fine map-like lines and a handful of colored points, and clip it inside the gray module. Keep text outside the illustration readable.

### Monumental ring ending

**Use:** Signature graphic beneath footer information.

**Observed:** A giant pale lavender rounded ring rises from below the page, surrounding a smaller saturated lavender ring with a white center. Only the upper arcs remain visible. The art sits in a 480px-high clipped area and meets a full-width 8px pastel gradient strip.

**Transfer:** Use original geometric brand artwork at monumental scale. With no emblem available, two concentric broad rings are the minimum acceptable closing device.

**Build:** Use a relative overflow-hidden stage 480px high. Center a 974px square SVG ring at the stage top, with a broad stroke in rgba(145,141,246,0.35) and white interior. Center a second 361px ring 296px down in #918df6, again with a white opening. Make the contours gently organic rather than mathematically thin. Overlay an 8px strip along the bottom using linear-gradient(to right in oklab, #bed5fe 0%, #ebf2ff 50%, #918df6 100%).

### Muted proof marks

**Use:** Small credibility strip between the opening actions and landscape stage.

**Observed:** A single centered row of varied customer symbols and wordmarks is rendered in low-contrast gray, with generous space above and below.

**Transfer:** Use legitimate customer marks or a compact neutral integration-symbol row; keep this strip subordinate to both the promise and product.

### Icons

**Observed:** Mostly 16px and 20px SVG outlines, 1.5px strokes with round caps; a few 16px action chevrons use 1.3px strokes. Capability icons adopt their title color, often on white rounded lozenges; comparison checks are lavender and partial support is amber.

**Transfer:** Choose simple rounded line icons, keeping them small and color-matched to the relevant capability rather than using large illustrative icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Narrow promise above landscape

**Observed:** A white canvas carries Floating navigation at the top center. The central promise begins after 160px of top space: a small blue-tinted announcement pill, then the two-line display headline in a 448px block, a two-line support sentence and the Primary button/Secondary button pair, all separated by 16px. A muted proof-mark row sits beneath. Within the first 900px the complete headline, support, actions and proof marks are visible; the full-width violet landscape begins around the lower third, with a centered white scalloped tab tray and the top of the 984px-wide interface appearing before the fold. The rest of the interface extends below the viewport. Layers run white page, landscape, white interface, then the floating dark navigation above everything.

**Transfer:** Make the new promise a compact two-line idea, not a wall-width slogan. Stage the clearest new-product screen or a credible interface reconstruction over the Landscape stage. For a focused feature or campaign page, retain this centered promise-to-product relationship and shorten the supporting proof rather than changing to a split hero.

**Avoid:** Do not turn the first screen into a dark gradient hero, a left-aligned text/image split or a giant headline laid directly over scenery.

**Text style:** `display` — OpenRunde 600 · 60px/68px · tracking -0.05em

### Centered chapter introduction

**Observed:** Section tag, heading and support form a centered stack with 20px gaps. Headings use heading or heading-tight; support stays within 384–448px. Main sections use 64px vertical padding and a 48px gap before their content.

**Transfer:** Use the tag to classify the chapter and the headline to state its useful outcome; keep the same hierarchy for different topics.

**Text style:** `heading` — OpenRunde 500 · 36px/44px · tracking -0.0175em

### Capability gallery

**Observed:** Feature cards fill a two-column 16px-gutter grid in the main-container. Colored names lead directly into dark benefit text at the same size. Tiny lists and Learn more pills occupy the top portion, with large working miniatures below. Smaller utility cards follow at a shallower height.

**Transfer:** Group the new product into a few substantial capabilities and reserve large card area for actual demonstrations.

**Text style:** `feature-lead` — OpenRunde 500 · 24px/28px · tracking -0.0133em

### Three-step demonstration

**Observed:** A centered chapter introduction sits above three 317px × 368px Soft cards separated by 16px. Each has an approximately 200px illustration panel with a fine lower divider, then a white number lozenge, short action heading and centered explanation.

**Transfer:** Explain an adoption or usage process through concrete miniature scenes; keep the steps visually equal.

### Outlined comparison column

**Observed:** A 984px-wide table gives half its width to feature labels and four equal 123px columns to alternatives. Rows are 57px high with Hairline gray dividers. The selected product is enclosed by a continuous 2px lavender outline with 24px rounded top and bottom ends. Small checks, crosses and partial-support marks do the comparison work.

**Transfer:** Use this treatment for meaningful option comparisons, with a single highlighted choice and concise row labels; do not simulate a heavy spreadsheet.

### Usage paired with simulation

**Observed:** A shared Soft card 984px wide is divided into equal columns with a faint vertical rule. The left has 32px inset content, a small billing toggle, lavender 48px quantity, slider, trial action and two-column inclusion list. The right shows a centered simulated rate above a large clipped globe, linking the number to a tangible visual.

**Transfer:** For a usage-based offer, pair the pricing control with a visual consequence of the selected amount; use a workload or capacity diagram when geography is irrelevant.

### Narrow questions and soft closing call

**Observed:** A centered introduction leads into a narrow FAQ row stack after 48px. The following Subtle closing panel spans the main-container and repeats a narrow 36px heading, 16px support and the same paired conversion actions, separated by 20px.

**Transfer:** Resolve practical objections in a compact column, then give the primary offer one calm, generous reprise.

### Small footer, enormous emblem

**Observed:** After 64px of top space, Footer links share the main-container with a short note and service-status dot on the left. Two compact columns of destination groups sit on the right. Generous white space separates the information from the Monumental ring ending, which is clipped at the page's final gradient baseline.

**Transfer:** Let utility copy stay small while original geometric artwork provides the final emotional impression.

## Page flow

**Storyline:** clear promise → tangible product scene → compact reasons to trust → capability demonstrations → easy adoption → decision support → objections → renewed invitation → graphic sign-off

### A product landing page that makes a technical tool feel easy, useful and personable

1. **Promise** — Centered narrow headline, direct support, two conversion paths and a muted proof strip.
2. **Product demonstration** — A broad white interface over a violet landscape, reached through a scalloped tab tray.
3. **Trust** — Three concise benefits in a horizontal row with small lavender icons.
4. **Capability chapters** — Large two-column gray cards pair colorful capability names with functional visualizations; smaller utility cards complete the picture.
5. **Adoption** — Three numbered cards explain the short path from setup to useful results.
6. **Decision support** — A lightly ruled comparison table outlines the favored column; a usage-pricing panel pairs controls with a vivid simulation.
7. **Objection handling** — A narrow stack of small, softly rounded questions.
8. **Closing call** — A pale broad panel repeats the main conversion pair.
9. **Graphic sign-off** — Muted footer groups precede oversized lavender circular artwork and a thin pastel bottom stripe.

**Transfer:** Adapt the narrative to the product's buying questions. Preserve the landscape product stage, working card miniatures and monumental geometric ending without treating this exact section order or number as fixed.

## Writing

Friendly technical clarity with an independent-maker undertone. Benefits are concrete and direct; reassurance comes from simple setup language, not grand enterprise rhetoric.

**Do not copy:** Do not reuse the Visitors name, emblem, customer logos, revenue milestones, exact pricing or usage numbers, competitive claims, service status, integration endorsements or performance/privacy promises without independent support. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the makers and product decisions. Prefer imperatives when describing a task.
- **Rhythm:** Short sentence-case headlines, one-sentence support lines and compact action labels. Card titles often flow directly into a plain-language benefit; setup steps use short verbs and periods.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A clear commercial priority attached to the product category. | 3–6 words | “Revenue-first web analytics” |
| Supporting line | Tell the reader what they will see or accomplish in concrete terms. | 12–22 words | “See every visitor in realtime and witness the moment they become a customer.” |
| Capability benefit | Start with See or Watch, followed by a specific observable result. | 9–16 words | “Watch visitors arrive and interact with your site as it happens.” |
| Process step | A short verb-object instruction followed by a practical explanation. | 2–3 words for the lead | “Install script.”<br>“Connect revenue.” |
| Primary action | An active start verb plus a specific low-risk offer. | 3–6 words | “Start 14 day free trial” |
| Reassurance | Plain-language removal of a specific source of friction. | One short sentence | “No confusing tiers.”<br>“Change or cancel your plan at any given moment.” |

**Words and phrasing to use:** See; Watch; Get started; simple; tiny; realtime; friendly; No confusing; everything is included

**Avoid:** revolutionary; synergy; unleash; enterprise-grade transformation; hypergrowth; game-changing

**Rules:**

- Connect each capability to a visible outcome instead of listing abstract platform nouns.
- Put setup friction and commercial terms in ordinary language.
- Use a few credible human details in the footer rather than expanding them into a manifesto.
- Keep question labels in the reader's voice and action labels as verbs.

## Do's and Don'ts

### Do

- Keep the primary headline at 60px/68px with weight 600 and -0.05em tracking on desktop.
- Center the promise within 448px while allowing the product stage to span the viewport.
- Use a 1024px outer container with 20px side padding for the main content.
- Keep feature-grid gutters at 16px and major chapter spacing at 64px.
- Use 44px lavender conversion pills and 32px white learn-more pills for distinct action levels.
- Give each large capability card a real lower-half visualization rather than just an icon.
- Carry the closing geometric artwork down into the 8px pastel baseline.
- Use a single 2px lavender outline to identify the preferred comparison column.

### Don't

- Do not spread the dark navigation surface into dark backgrounds for every chapter.
- Do not replace 16px flat gray capability cards with heavily shadowed white dashboards.
- Do not use all-caps wide-tracked eyebrows; section tags are 14px sentence case.
- Do not color entire paragraphs green, blue or pink; color the short capability lead and leave the benefit dark.
- Do not make every CTA lavender; secondary paths stay gray and learn-more actions stay white.
- Do not give small body labels the headline's -0.05em tracking; use the -0.3px small-text spacing.
- Do not turn the muted proof-mark strip into saturated logo tiles.
- Do not shrink the ending artwork to a conventional footer logo; its 974px outer form is intentionally monumental.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare all-property transitions at .15s cubic-bezier(.4,0,.2,1); color transitions use the same duration and curve.
- Some miniature bar widths declare 0.3s cubic-bezier(0,0,.2,1) transitions.
- A service-status effect declares ping 1s cubic-bezier(0,0,.2,1) infinite.
- The navigation remains fixed while sections move beneath it.

**Transfer:**

- Use the short declared transitions for compact controls and bar updates; keep the page's primary structural effect the fixed dark navigation over a moving white document.

**Unknown:**

- The timing and choreography of canvas/globe animation and on-scroll entrances are not established.
- Active-scale behavior is ambiguous; no enlargement rule is prescribed.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1600px.
- Feature and pricing grids declare one column by default and two at the medium breakpoint; the opening action pair changes from a column to a row at that breakpoint.
- The ending art stage declares heights of 260px, 340px and 480px, with artwork scales 0.55, 0.7 and 1 across the base, small and medium ranges.

**Transfer:**

- Stack the capability and pricing modules on narrow screens while preserving clipped visual objects and 20px outer padding.
- Scale the monumental closing artwork as a unit so it remains a cropped graphic, not a tiny logo.

**Unknown:**

- The narrow-screen navigation treatment and comparison-table alternative are not established.
- Desktop type sizes are known; no fluid typography formula is established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
