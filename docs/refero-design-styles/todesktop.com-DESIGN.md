# ToDesktop — luminous software machinery

## Overview

A software-first style that makes infrastructure feel like a polished desktop object. Deep violet and electric blue dissolve into a predominantly white, lightly modeled landscape of interface windows, translucent controls and miniature product illustrations. Rounded grotesk headlines meet practical sans-serif copy and tiny technical monospace labels; the overall pace is spacious, with denser comparison and capability areas.

### Essentials

- Headlines feel like part of the software object: Aeonik Pro at 74px/84px, weight 500 and -0.015em tracking, with a small rounded app-like object embedded in the line and a translucent white gradient on dark backgrounds.
- The opening is a luminous machine room rather than a flat banner: a full-width dark violet stage, centered two-line promise, compact 36px paired actions, three small process summaries and the top of a large desktop window within the first 900px.
- Controls look gently molded: pill-shaped marketing buttons use 14px/22px Inter at 500, fine inset highlights and low-opacity layered shadows; white and translucent secondary variants accompany the electric-blue action.
- Color is concentrated into theatrical stages: the opening gradient runs through violet, cobalt and cyan before fading to white over 2850px; most later content is white with #f7f7f7 cards and #141414 text. Repeat the luminous stage device for a major conversion moment.
- Capabilities are illustrated as small physical software scenes: 456px-wide cards with 24px corners pair pale floating UI, soft shadows, an object metaphor and centered 16px titles above 14px explanatory copy. When product media is unavailable, construct a real miniature workflow with panels and an object rather than decorative stock photography.
- Proof borrows the desktop dock: a large app window fades into a blue atmosphere above a rounded translucent tray of colorful 72px app tiles, with thin hand-drawn arrows and short handwritten annotations. Use original product, integration or workflow tiles when customer media is unavailable.
- The exit becomes lighter, not louder: a 32px-radius pastel blue-and-pink alternative-path panel precedes a spacious white footer with four link columns, a small green operational indicator and 120px vertical padding.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0036ff` | `--color-action` | action, accent | Saturated primary pills and small app-like highlights. |
| Cobalt light | `#1046e9` | `--color-cobalt` | background | Bright middle portion of atmospheric stages. |
| Indigo depth | `#061db6` | `--color-indigo` | background | Middle depth of the luminous stage. |
| Deep violet | `#13023a` | `--color-violet` | background | Dark violet transition within atmospheric gradients. |
| Violet night | `#0f071d` | `--color-night` | background | Top of the luminous hero and conversion stages. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cyan light | `#1096e5` | `--color-cyan` | background | Lower blue glow around proof windows and dock imagery. |
| Pastel blue | `#d1e9ff` | `--color-pastel-blue` | background | Left edge of the alternative-path panel. |
| Ice fade | `#e6f4f7` | `--color-ice` | background | Transition from saturated stage to white canvas. |
| Pastel pink | `#ffedfe` | `--color-pastel-pink` | background | Visible pink wash in the alternative-path panel; source pink #ffdefd at 56% opacity over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#141414` | `--color-ink` | text, surface | Main headings and labels; also the dark recommended pricing card. |
| Supporting gray | `#656565` | `--color-muted` | text | Supporting copy on light backgrounds. |
| Quiet labels | `#a4a4a4` | `--color-subtle` | text | Footer category labels and secondary technical markings. |
| Light hairline | `#f1f1f1` | `--color-edge` | border | Visible light-card outlines and rules; built with dark ink at about 6% opacity over white. |
| Ghost gray | `#f7f7f7` | `--color-ghost` | surface, background | Visible pale feature-card fill; equivalent to 4% dark gray over white. Also the neutral end of pastel fades. |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Main page canvas, raised panels and reversed text. Dark-stage body copy uses white at 80% opacity. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#14a362` | `--color-status` | accent | Tiny green operational-status dot, not a broad brand accent. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| self-serve builder product pages | Download blue | `#3238f2` | `--color-builder-blue` | action, text | Rectangular download and pricing actions. |
| self-serve builder product pages | Step brown | `#713f12` | `--color-step-ink` | text | Text inside yellow step badges. |
| self-serve builder product pages | Step yellow | `#fff6cc` | `--color-step-yellow` | surface | Small numbered step and version badges. |
| self-serve builder product pages | Charcoal copy | `#2f3033` | `--color-builder-copy` | text | Introductory support copy. |
| self-serve builder product pages | Cool panel edge | `#e4e5eb` | `--color-builder-edge` | border | Explicit panel and tile outlines. |
| self-serve builder product pages | Cool panel | `#fafafc` | `--color-builder-panel` | surface | Cool-white panels and gradients; at 70% over white the visible fill is nearly white. |

## Typography

- **Aeonik Pro** — Default marketing headlines, plan names and large prices. Rounded contemporary grotesk with an open, smooth silhouette; medium rather than heavy. OpenType features: "ss02", "ss05", "ss10", "ss11". If unavailable, use **Inter**. Use 400–500 weights and preserve the tight tracking. Font stack: "Aeonik Pro", "Inter", ui-sans-serif, system-ui, sans-serif.
- **Inter** — Body copy, labels, buttons, navigation and footer links. Compact and functional sans-serif, restrained in both size and weight. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **Geist Mono** — Tiny technical eyebrows, status markings and feature labels. Clean monospace in small tracked capitals. Font stack: "Geist Mono", ui-monospace, SFMono-Regular, Menlo, monospace.
- **TT Hoves Pro** (only for self-serve builder product pages) — Headlines, download controls and step headings. Direct geometric grotesk with firmer semibold section headings. If unavailable, use **Inter**. Use 500 for the hero and 600 for section headings. Font stack: "TT Hoves Pro", "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Aeonik Pro | 500 | 74px | 84px | -0.015em | Default two-line opening headline; translucent white on a dark luminous stage. |
| heading-lg | Aeonik Pro | 500 | 64px | 72px | -0.015em | Centered major section headings on the white canvas. |
| heading | Aeonik Pro | 500 | 48px | 52px | -0.015em | Conversion-stage headings, social-proof heading and large price numerals. |
| heading-panel | Aeonik Pro | 400 | 36px | 44px | -0.01em | Alternative-path panel headline. |
| plan-title | Aeonik Pro | 500 | 24px | 32px | -0.01em | Plan titles and enterprise labels. |
| body-lead | Inter | 400 | 16px | 26px | normal | Section introductions and conversion-stage support text. |
| feature-title | Inter | 500 | 16px | 26px | -0.01em | Centered titles within capability cards. |
| body | Inter | 400 | 14px | 22px | normal | Card descriptions, pricing details, footer links and status text. |
| label | Inter | 500 | 14px | 22px | -0.01em | Marketing button labels and compact FAQ questions. |
| eyebrow | Geist Mono | 500 | 11px | 16px | 0.03em, uppercase | Technical section markers and tiny pill labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| self-serve builder product pages | builder-display | TT Hoves Pro | 500 | 72px | 1 | normal | Centered light-theme product opening. |
| self-serve builder product pages | builder-heading | TT Hoves Pro | 600 | 48px | 1.25 | normal | Left-aligned capability, proof, pricing and FAQ section headings. |
| self-serve builder product pages | builder-subheading | TT Hoves Pro | 600 | 36px | 40px | normal | Numbered workflow step titles and plan names. |
| self-serve builder product pages | builder-intro | Inter | 400 | 24px | 32px | normal | Two-line opening support paragraph. |
| self-serve builder product pages | builder-body | Inter | 400 | 18px | 28px | normal | Workflow explanations and testimonials. |
| self-serve builder product pages | builder-action | TT Hoves Pro | 600 | 18px | 28px | normal | Primary download and pricing buttons. |

**Notes:**

- Keep the display hierarchy medium and rounded; section headings do not become extra-bold. Tracking is -0.015em at the three largest default sizes and -0.01em for smaller titles and labels.
- Use a vertical white alpha gradient for dark-stage headlines: 90% white at the top to 75% at the bottom. Body text remains a solid readable alpha rather than sharing this treatment.
- Technical monospace stays tiny and peripheral. Do not use it for ordinary paragraphs or every navigation label.
- The light self-serve product treatment is a scoped alternative, not a mixture of both heading families within an ordinary marketing section.

## Layout

**Density:** Airy between chapters, compact inside controls and technical detail; imagery receives more space than card copy.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Main heading to short support line. |
| 12px | Eyebrow to heading, plan title to support copy and compact footer-link gaps. |
| 16px | Paired hero actions and FAQ-column/item gaps. |
| 24px | Default feature and pricing grid gaps. |
| 32px | Support text to action row and inner panel groups. |
| 40px | Horizontal text inset in feature cards. |
| 48px | Bottom inset of illustrated cards and separation between workflow panels. |
| 56px | Footer header to link grid. |
| 96px | Between large capability groups. |
| 120px | Default major chapter and footer vertical padding. |

### Containers and grids

- **marketing-container**: max width 1128px · side padding 24px. Centered pricing, alternative-path panel and footer; 156px outer margins at 1440px.
- **illustrated-feature-grid**: max width 960px · 2 columns · gap 24px · side padding 12px. Two equal 456px illustrated cards; centered narrower than the pricing container.
- **pricing-grid**: max width 1128px · 3 columns · gap 24px. Three equal 360px plan cards; middle plan reverses to dark.
- **faq-grid**: max width 952px · 2 columns · gap 16px · side padding 14px. Two independent columns of compact question cards.
- **stage-copy**: max width 686px · side padding 32px. Text group within the luminous conversion card; support paragraph is capped at 600px.
- **footer-grid**: max width 1128px · 4 columns · gap 24px. Equal link categories with extensive white space above and below.
- **builder-container** (only for self-serve builder product pages): max width 1280px · side padding 32px. Broader light-product chapters, workflow panels and footer.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing-controls | 9999px (pill) |
|  | feature-and-pricing-cards | 24px |
|  | raised-plan-header | 20px |
|  | large-stage-and-alternative-panel | 32px |
|  | faq-cards | 14px |
| self-serve builder product pages | builder-panels | 16px |
| self-serve builder product pages | builder-buttons | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-navigation | `0px 1px 2px rgba(0,0,0,0.08), 0px 4px 16px rgba(0,0,0,0.08), 0px 16px 56px rgba(0,0,0,0.08)` | White capsule navigation over both light and saturated stages. |
| raised-plan-header | `0px 6px 6px -3px rgba(0,0,0,0.02), 0px 3px 3px -1.5px rgba(0,0,0,0.02), 0px 1px 1px -0.5px rgba(0,0,0,0.03), 0px 12px 12px -3px rgba(0,0,0,0.04)` | Soft white pricing header nested inside a pale plan shell. |
| desktop-window | `0px 24px 32px -3px rgba(0,0,0,0.04), 0px 12px 24px -3px rgba(0,0,0,0.06), 0px 6px 6px -3px rgba(0,0,0,0.04), 0px 3px 3px -1.5px rgba(0,0,0,0.04), 0px 1px 1px -0.5px rgba(0,0,0,0.03)` | Large white interface demonstrations; fine contact shadow beneath a broad diffuse lift. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading environment after the opening stage.

**CSS:** `background: #ffffff; color: #141414`

#### Luminous stage · level 0

**Use:** Full-width opening atmosphere and repeated conversion-stage material.

**CSS:** `background: linear-gradient(0deg, #ffffff, #e6f4f7 6.29%, #1096e5 21.57%, #1046e9 42.64%, #061db6 53.09%, #13023a 75.33%, #0f071d 86.09%, #0f071d)`

**Observed:** The opening backdrop spans 2850px vertically and dissolves beneath proof into the white feature chapter. A smaller 936px-wide, 32px-radius version repeats the same dark-to-blue-to-white material.

**Transfer:** Preserve the luminous progression rather than treating it as a repeating section background; match the soft glow, exact intermediate stops are not essential.

#### Ghost card · level 1

**Use:** Illustrated capabilities and pale pricing shells.

**CSS:** `background: rgba(55,55,55,0.04); border-radius: 24px; overflow: hidden`

**Observed:** Almost white, with no heavy border or broad drop shadow around the outer card.

**Transfer:** Let internal objects provide depth; keep the surrounding card low-contrast.

#### Frosted software glass · level 2

**Use:** Floating controls and interface panels on saturated scenes.

**CSS:** `background: rgba(5,6,27,0.5); border: 1px solid rgba(255,255,255,0.06); border-radius: 24px; backdrop-filter: blur(8px); box-shadow: inset 0px 1px 3px rgba(255,255,255,0.06), 0px 16px 56px rgba(2,9,44,0.24)`

**Observed:** Dark translucent panels pick up the blue atmosphere, with narrow bright top edges and subtle inset light.

**Transfer:** Use this for a dock or compact floating workflow panel, not every content card.

#### Pastel alternative panel · level 1

**Use:** A lower-friction route or adjacent product invitation near the end.

**CSS:** `background: linear-gradient(114.58deg, #d1e9ff -1.34%, rgba(255,222,253,0.56) 24.05%, #f7f7f7 74.82%); border-radius: 32px; outline: 1px solid rgba(55,55,55,0.04); outline-offset: -1px; overflow: hidden`

**Observed:** A horizontal blue-to-pink wash becomes neutral behind the interface on the right.

**Transfer:** Keep the pastel panel visibly distinct from the saturated main conversion stage.

#### Builder workflow panel · level 1

**Only for:** self-serve builder product pages

**Use:** Wide numbered walkthrough steps.

**CSS:** `background: linear-gradient(to bottom right, #fafafc, rgba(250,250,252,0.7)); border: 1px solid #e4e5eb; border-radius: 16px`

**Observed:** Pale grid texture supports text on the left and product demonstrations on the right; a 1px outer inset creates a double-skin edge.

**Transfer:** Use for sequential setup or onboarding rather than replacing the illustrated marketing cards.

## Components

### Floating navigation

**Use:** Persistent navigation after the wide opening header compacts.

**CSS:** `background: rgba(255,255,255,0.88); border-radius: 9999px; padding: 12px 12px 12px 18px; max-width: 656px; backdrop-filter: blur(12px); box-shadow: 0px 1px 2px rgba(0,0,0,0.08), 0px 4px 16px rgba(0,0,0,0.08), 0px 16px 56px rgba(0,0,0,0.08)`

**Observed:** Brand icon at left, compact resource links in the middle, account controls at right. The first screen uses a wide transparent header; the scrolled state becomes a centered white capsule near the top.

**Transfer:** Keep the floating capsule short enough to read as a desktop toolbar, not a full-width white strip.

### Primary button

**Use:** Default marketing conversion control.

**CSS:** `background: linear-gradient(rgba(255,255,255,0.12), rgba(255,255,255,0.06)), #0036ff; color: #ffffff; border-radius: 9999px; padding: 7px 10px 7px 14px; height: 36px; box-shadow: inset 0px 1px 2px -0.5px rgba(255,255,255,0.12), inset 0px 8px 24px -4px rgba(255,255,255,0.16), 0px 3px 3px -1.5px rgba(8,1,20,0.03)`

**Text style:** `label` — Inter 500 · 14px/22px · tracking -0.01em

**Observed:** A short white label is followed by a fine right chevron. The pricing version expands to 280px by 48px with 13px padding; the alternative-path version is 40px tall.

### Secondary button

**Use:** Documentation or comparison beside a primary action.

**CSS:** `background: linear-gradient(rgba(255,255,255,0.16), rgba(255,255,255,0.08)), rgba(255,255,255,0.04); color: #ffffff; border-radius: 9999px; padding: 7px 16px 7px 14px; height: 36px; box-shadow: inset 0px -4px 12px -4px rgba(255,255,255,0.08), inset 0px 1px 3px rgba(255,255,255,0.06)`

**Text style:** `label` — Inter 500 · 14px/22px · tracking -0.01em

**Observed:** A translucent dark-stage pill. On light panels and non-highlighted plans it becomes a white raised pill with ink text; plan actions are 280px by 48px.

**States:** Declared: hover background-color rgba(255,255,255,0.1); focus-visible not specified; active background-color rgba(255,255,255,0.02) with inset shadow.

### Technical badge

**Use:** Small feature category, section marker or product-mode label.

**CSS:** `background: rgba(55,55,55,0.04); color: #656565; border-radius: 9999px; padding: 4px 10px; display: flex; align-items: center; gap: 4px`

**Text style:** `eyebrow` — Geist Mono 500 · 11px/16px · tracking 0.03em · uppercase

**Observed:** A small capsule above a headline; dark-stage variants use 8% white glass and white gradient lettering.

### Illustrated feature card

**Use:** Explain one capability with a focused visual metaphor.

**CSS:** `background: rgba(55,55,55,0.04); border-radius: 24px; overflow: hidden; text-align: center`

**Text style:** `feature-title` — Inter 500 · 16px/26px · tracking -0.01em

**Observed:** The upper majority is a pale layered software scene; title, fine divider and a short muted description sit below. Text is inset 40px horizontally and 48px at the bottom. Both 612px-tall and shorter 421px-tall cards occur.

**Transfer:** Use a real task or result as the scene and keep the copy to one idea.

### Pricing card

**Use:** Compare commercial tiers.

**CSS:** `background: rgba(55,55,55,0.04); border-radius: 24px; padding: 4px`

**Text style:** `plan-title` — Aeonik Pro 500 · 24px/32px · tracking -0.01em

**Observed:** A raised rounded header contains plan title and description; price, full-width pill action and feature lists follow. The middle tier reverses to ink with a translucent raised header and the blue action; outer tiers retain white actions. Prices use the heading recipe with a small baseline billing suffix.

**Transfer:** Use the same nested-header construction even when the number of plans changes.

### FAQ card

**Use:** Compact objection handling in two columns.

**CSS:** `border: 1px solid rgba(22,22,22,0.06); border-radius: 14px; overflow: hidden`

**Text style:** `label` — Inter 500 · 14px/22px · tracking -0.01em

**Observed:** The full question is a button with 23px top, bottom and left padding, 15px right padding and a right-aligned 24px chevron. Closed cards are 72px tall or 92px when the question wraps.

### Operational status

**Use:** A small trust signal in the footer header.

**CSS:** `border: 1px solid rgba(22,22,22,0.03); border-radius: 9999px; padding: 5px 9px 5px 5px; display: flex; align-items: center; gap: 4px; height: 32px`

**Text style:** `body` — Inter 400 · 14px/22px

**Observed:** A 6px green dot sits within a softly glowing 22px indicator beside a short factual status line.

**States:** Declared: hover background-color rgba(22,22,22,0.02); focus-visible not specified.

### Footer link column

**Use:** Grouped product, resource, policy and contact links.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 12px`

**Text style:** `body` — Inter 400 · 14px/22px

**Observed:** A muted category title precedes plain dark links. Four equal columns align to a wide container, separated from the upper brand-and-status row and lower copyright-and-affiliation row by faint rules.

**States:** Declared: hover text-decoration underline; focus-visible not specified.

### Download button

**Only for:** self-serve builder product pages

**Use:** Download or start a self-serve product.

**CSS:** `background: #3238f2; color: #ffffff; border-radius: 8px; padding: 12px 32px; height: 52px; box-shadow: 0px 0px 0px 1px #3238f2, 0px 1px 2px rgba(0,0,0,0.05)`

**Text style:** `builder-action` — TT Hoves Pro 600 · 18px/28px

**Observed:** Larger and more rectangular than the default marketing pills. A white outlined documentation button sits beside it; the preferred plan uses the filled blue variant.

**States:** Declared: hover background-color rgb(50 85 235 / 1); focus-visible not specified.

### Numbered step badge

**Only for:** self-serve builder product pages

**Use:** Anchor a sequential walkthrough.

**CSS:** `background: #fff6cc; color: #713f12; border: 1px solid rgba(102,83,0,0.1); border-radius: 8px; padding: 4px 12px`

**Observed:** Small semibold label above the step headline; 16px/24px display lettering and 40px separation from the title.

## Imagery and graphics

### Luminous software stage

**Use:** Signature atmosphere in the opening and a major conversion moment.

**Observed:** Very dark violet at the top, intense indigo and blue through the middle, cyan near the base, then a misty white dissolve. Thin rounded circuit-like tracks flank the headline and frame a large desktop window. The white headline includes a luminous blue rounded-square app object.

**Transfer:** Recreate the light field and an original software object even without a mature product interface. Keep the object a small interruption in the headline rather than a mascot.

**Build:** Use the Luminous stage gradient on a tall layer behind the content. Add SVG paths with 1px white strokes at 6–10% opacity: horizontal tracks that bend diagonally and turn through rounded corners. Create a 64px rounded-square object with blue fill, two fine white inset outlines and a faint wireframe grid; add a blurred blue halo behind it. Scale this object with the headline line box.

### Dock proof scene

**Use:** Signature social-proof or integration scene on the luminous stage.

**Observed:** A large dark app window, roughly 992px wide in its framed composition, fades at its bottom into cyan light. A 684px-wide glass dock floats in front with nine colorful square app icons. Fine off-white handwritten labels and loose curved arrows explain interaction.

**Transfer:** Show an original product view with integration icons, workflow destinations or original sample-project tiles. If no interface exists, use a believable task window with a real content hierarchy and a dock of meaningful outputs.

**Build:** Layer a dark rounded desktop window behind a bottom-to-top transparent-to-cyan mask. Place a 24px-radius translucent dark tray below it with a 6px inset, fine white rim, blue-tinted shadow and 72px icon hit areas. Add two or three SVG curved arrows with irregular 1px strokes and brief handwritten-style annotations rendered as original SVG paths.

### Pale capability miniatures

**Use:** Repeated illustrations in the two-column capability grid.

**Observed:** White and pale gray objects on pale gray cards: an open carton below a floating build panel, a magnifying glass over a code window, certificate and device objects, small charts and download controls. Soft contact shadows, translucent overlaps and bottom fades make them feel modeled rather than flat.

**Transfer:** Give each capability a concrete task metaphor and a small authentic interface fragment. Minimum version: two or three white CSS/SVG panels with a meaningful symbol, fine dividers and soft shadows, not an empty rectangle.

**Build:** Use 14–20px rounded white panels, 1px dark edges at 4–5% opacity and multiple low-opacity contact shadows. Layer a simple SVG object in front; fade the lower illustration into the card with a transparent-to-ghost gradient. Reserve saturated syntax or status colors for tiny functional details.

### Large interface demonstration

**Use:** A deeper product walkthrough between capability groups.

**Observed:** A 1128px-wide white desktop interface sits inside a 1152px pale shell with 32px corners and 12px inset. Browser chrome, sidebar and content panels remain recognizable without making their internal typography the marketing system.

**Transfer:** Use a true interface or carefully authored product mockup. Preserve desktop framing and readable structural hierarchy, but simplify incidental UI text.

### Pastel panel interface

**Use:** The alternative-path invitation near the end.

**Observed:** Text takes the left half of a broad pastel panel; a large white app window enters from the right and extends beyond the frame. Its far-right and lower edges dissolve into the neutral background.

**Transfer:** Pair a simpler workflow or adjacent offer with one relevant interface view. Keep the illustration subordinate to the panel headline and actions.

**Build:** Position a rounded white app window in the right half, extending beyond the panel boundary. Overlay rightward and downward gradients ending in #f7f7f7 so the UI merges into the backing; preserve the upper-left chrome and sidebar.

### Icons

**Observed:** Small marketing glyphs are mostly muted solid icons at 20–22px, with 16px checks and 24px chevrons. Outline variants use 1.5px rounded strokes; action arrows are white and compact.

**Transfer:** Choose one rounded icon set, use neutral gray for feature lists and reserve white for dark-stage controls. Treat app icons as colorful product objects, not generic line icons.

## Section recipes

How recurring sections are built.

### First screen: Luminous product opening

**Observed:** A wide transparent header sits over a full-bleed Luminous stage. Center a small technical badge above a two-line display headline spanning roughly two thirds of the viewport; embed a 64px rounded software object within the second line. A single short support line follows, then Primary button and Secondary button in a compact centered row with 16px gap. Below them, three equal small process summaries introduce the demonstration. Within the first 900px, the headline, support, actions, three summaries and upper portion of a large desktop/terminal window are visible; the full process scene and dock proof continue below. Back-to-front layers are gradient atmosphere, faint circuit tracks, text and object, controls, then the luminous framed interface.

**Transfer:** Write a multi-verb outcome promise and replace the inline object with an original product tile. Build a believable workflow window if finished media is unavailable. A self-serve product opening instead uses the scoped light theme: soft lavender-and-cream atmosphere, version badge, three short capability labels, 72px centered heading, 24px support text, rectangular Download button pair and the first row of proof tiles within 900px.

**Avoid:** Do not replace the stage with a white split hero, a huge right-hand stock image or a single flat purple rectangle; do not force the whole demonstration above the fold.

**Text style:** `display` — Aeonik Pro 500 · 74px/84px · tracking -0.015em

### Major heading pair

**Observed:** Centered heading-lg with an 8px support gap; body-lead support remains narrow and muted. Tiny Technical badge or eyebrow can identify a chapter such as FAQ. Large chapter padding is 120px.

**Transfer:** Use a short plain-language chapter claim and one clarifying sentence; leave explanatory detail to cards.

**Text style:** `heading-lg` — Aeonik Pro 500 · 64px/72px · tracking -0.015em

### Illustrated capability chapter

**Observed:** Illustrated feature card pairs occupy the illustrated-feature-grid. A large interface demonstration interrupts the smaller cards; a later grid uses shorter cards, followed by compact three-column icon-and-copy rows.

**Transfer:** Alternate conceptual miniatures with a concrete interface to show both benefits and product reality; adapt the number of groups to the story.

### Luminous conversion reprise

**Observed:** A 936px-wide, 32px-radius Luminous stage contains a stage-copy group, Technical badge, heading, body-lead and paired actions. The Dock proof scene anchors the lower portion, reusing the opening's light and software-object language.

**Transfer:** Repeat the atmosphere at the point where the promise has become credible, with a clearer conversion statement rather than merely duplicating the hero.

**Text style:** `heading` — Aeonik Pro 500 · 48px/52px · tracking -0.015em

### Nested pricing comparison

**Observed:** Centered heading-lg, short reassurance, segmented billing switch and pricing-grid. Pricing card headers are raised 20px-radius islands; the middle plan is dark. An enterprise offer forms a low horizontal band beneath the grid.

**Transfer:** Let the emphasized tier be selected by product strategy; preserve the pale-shell/raised-header construction and the contrast between white and blue actions.

### Two-column questions

**Observed:** Centered major heading above faq-grid; compact FAQ cards have consistent quiet outlines and trailing chevrons. A small centered support prompt below links to documentation and human contact.

**Transfer:** Use real objections and maintain compact questions; the self-serve variant uses larger 18px questions, cool filled panels and a left-aligned 48px section heading.

### Alternative-path close

**Observed:** A centered heading-lg question with a short body-lead introduces the Pastel alternative panel. Inside, a left-aligned heading-panel, muted short paragraph, two-column icon list and paired actions balance the faded Pastel panel interface on the right.

**Transfer:** Use this as a genuinely easier route or adjacent offer. Preserve the pastel invitation device near the exit; a single-product business can use a guided-start offer instead of a second product.

**Text style:** `heading-panel` — Aeonik Pro 400 · 36px/44px · tracking -0.01em

### Operational footer

**Observed:** White canvas with a faint top rule and 120px vertical padding. Brand lockup aligns left and Operational status right. After a rule and 56px separation, four Footer link columns appear; a lower rule separates copyright left from a small affiliation mark right. Both light-product and default treatments end this way.

**Transfer:** Keep the ending useful and reassuring rather than adding another giant sales headline; use truthful status and affiliation information.

### Numbered workflow

**Only for:** self-serve builder product pages

**Observed:** Wide Builder workflow panels stack 48px apart. Each pairs a Numbered step badge and builder-subheading on the left with desktop UI, code or installation demonstrations on the right; text has 48px horizontal panel inset and panels carry a pale grid texture.

**Transfer:** Explain an actual setup sequence with one action per panel, then follow with smaller feature or testimonial cards.

## Page flow

**Storyline:** Promise → tangible product demonstration → proof → capability explanations → conversion opportunity → commercial detail → objection handling → reassuring exit.

### A flagship technical-product landing page that turns a complex service into understandable software objects

1. **Promise** — Dark luminous centered opening with an inline product object and compact paired actions.
2. **Product demonstration** — Three short process summaries lead into a large framed desktop scene.
3. **Social proof** — A blue-lit app window and glass icon dock make adoption feel tangible.
4. **Capability chapters** — Pale illustrated two-column cards alternate with a large real interface and compact supporting feature rows.
5. **Conversion** — A contained luminous stage repeats the promise with actions and proof.
6. **Pricing** — Nested three-tier comparison, emphasized dark plan and low enterprise band.
7. **Objection handling** — Compact two-column FAQ with documentation and contact links.
8. **Alternative route** — Pastel invitation offers a simpler path with a faded interface.
9. **Reassurance** — White four-column footer with operational status and restrained legal/affiliation row.

**Transfer:** Use the luminous stages, modeled software cards and pastel exit as recurring devices; choose their placement and frequency to suit the new product's narrative rather than preserving a fixed section count.

### A self-serve creation or download product that must explain setup and reduce effort anxiety

1. **Promise** — Light atmospheric centered opening with version badge, capability labels and large rectangular download controls.
2. **Social proof** — Two horizontal rows of small app tiles.
3. **Workflow explanation** — Numbered wide setup panels with text and product demonstrations.
4. **Capabilities** — Cool feature cards and a bordered strip of additional capability names.
5. **Customer proof** — Three testimonial cards with outcome titles, quotations, attribution and small avatars.
6. **Conversion** — Charcoal rounded panel pairs a large download invitation with a partially framed interface and a small cost clarification.
7. **Pricing** — Three cool outlined plans and a wider dark enterprise band.
8. **Alternative route** — Contained luminous gradient points toward a more advanced offer.
9. **Objection handling** — Larger two-column FAQs with resource links.
10. **Reassurance** — Shared operational footer in the broader container.

**Transfer:** Use the scoped light typography and controls for a setup-led product, while retaining the luminous cross-offer device and shared footer.

## Writing

Practical, technically literate and reassuring. The prose promises relief from tedious work, then explains exactly what the product takes care of without sounding enterprise-bureaucratic.

**Do not copy:** Do not reuse ToDesktop names, logos, customer app icons, screenshots, customer quotations, prices, version numbers, adoption claims or performance claims. Replace them with original assets and verifiable product information. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we for responsibilities the product assumes. Name technical concepts when they reduce ambiguity.
- **Rhythm:** Short benefit headlines, one or two plain explanatory sentences, then terse action labels. Parallel clauses and lists of three are common; reassurance is calm rather than exuberant.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Combine direct outcome verbs with the product category, or a from-to transformation with a speed benefit. | 7–12 words | “Release, Secure and Scale your Electron App”<br>“Web app to desktop app in minutes” |
| Supporting line | Name concrete operational benefits in a concise parallel list. | 8–18 words | “Effortless deployment, robust security and seamless auto-updates.” |
| Feature title | Translate infrastructure into a task relieved or a useful result. | 3–9 words | “Focus on your app, not plumbing”<br>“Identify code vulnerabilities” |
| Responsibility split | State what the reader controls and what the product handles in two short sentences. | Two brief sentences | “You write the application. We do the infrastructure.” |
| Primary action | Verb first, with a clear next step and little ornament. | 2–4 words | “Start free trial”<br>“Download now” |
| Closing invitation | Offer an easier path as a conversational question. | 3–6 words | “Want something simpler?” |

**Words and phrasing to use:** build; release; secure; automate; your app; native; reliable; we handle; code optional; one-click

**Avoid:** revolutionary; disrupt the future; unparalleled synergy; magic without explanation; excessive superlatives

**Rules:**

- Lead with a user outcome, then give a concrete mechanism or responsibility.
- Use product-specific technical vocabulary in descriptions, but keep section headings readable without specialist knowledge.
- Explain commercial caveats near the relevant action in small plain language.
- Write compact labels that fit desktop-like controls; do not turn buttons into sentences.

## Do's and Don'ts

### Do

- Keep default display lettering at 500 with -0.015em tracking and 74px/84px desktop scale.
- Make the main white content container 1128px and the illustrated grid 960px with 24px gaps.
- Use 36px primary pills beside equally compact secondary pills on luminous stages.
- Keep pale illustrated-card text centered, 40px inset horizontally and 48px from the bottom.
- Use 11px/16px tracked monospace for technical eyebrows rather than oversized labels.
- Repeat the dark-to-blue-to-white luminous material at a meaningful conversion moment.
- Preserve the 32px-radius pastel invitation and the white operational footer as distinct exit devices.
- Use an ink middle plan with a raised translucent header when emphasizing a pricing tier.

### Don't

- Do not make default feature cards strongly outlined or elevated; the pale fill is only 4% dark gray over white.
- Do not use saturated blue as ordinary body text or flood every chapter with it; it belongs to actions and atmospheric stages.
- Do not turn the default headline weight into 700; the rounded 500-weight silhouette is important.
- Do not apply 8px rectangular download controls to the default marketing treatment; those belong to the self-serve product variant.
- Do not substitute a generic logo wall for the glass dock scene; preserve the desktop-object metaphor and annotation treatment.
- Do not render every capability as a dark UI tile; pale miniature scenes dominate the capability chapters.
- Do not enlarge the footer into a second hero; retain 14px/22px links and four calm categories.
- Do not put a thick border around every interface object; use low-alpha rims and layered contact shadows.

## Motion and responsive

### Motion

**Observed:**

- Marketing buttons declare all 0.2s cubic-bezier(0.6,0.6,0,1), with 50ms active timing; many panels and FAQ controls declare all 0.45s with the same curve.
- Process-core loops declare 1.5s ease-out; smoke-check loops declare 2.5s ease; a code magnification scene declares a 10s ease loop.
- The wide header compacts into a floating capsule as the page progresses.

**Transfer:**

- Use motion to explain a software process: a build completes, a check runs, or a lens reveals code. Keep each scene attached to its capability rather than adding unrelated ambient movement.
- Use the declared compact button timing and inset pressed treatment to maintain the molded-control feeling.

**Unknown:**

- Exact scroll-trigger thresholds, complete choreography and focus-visible styling are not established.

### Responsive

**Observed:**

- Styles include width breakpoints around 575/576px, 767/768px, 956/957px, 1040px and 1200px.
- Layout classes specify a single-column feature layout below the medium grid, 56px compact chapter padding versus 120px desktop padding, and narrower 480px feature containers.
- The alternative-path interface illustration is hidden below the large-layout treatment; opening actions can expand within their row.

**Transfer:**

- On narrow screens, retain the luminous atmosphere and inline product-object idea while shortening headline lines. Stack feature cards and plans; keep the desktop dock legible with fewer visible meaningful tiles rather than shrinking all icons into specks.
- Prioritize the alternative-path text and actions when its right-side interface is removed.

**Unknown:**

- Only desktop appearance is established; exact mobile headline sizes, navigation menu behavior and dock interaction require design testing.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
