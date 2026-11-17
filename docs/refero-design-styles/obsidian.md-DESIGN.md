# Obsidian — tools for private thought

## Overview

A dark, utilitarian software style with an unusually personal, reader-first voice. Near-black space, soft gray grotesk typography and small violet actions surround substantial, legible interface demonstrations. The feeling is independent and capable rather than enterprise-polished: spacious marketing passages alternate with dense working tools, with occasional lavender-backed white panels providing a crisp flash of contrast.

### Essentials

- Short sentences become solid headline objects: system sans at 60px/1, weight 600 and -0.02em tracking, with full stops rather than decorative display effects.
- The opening behaves like a workbench, not a poster: left-aligned text in a 1120px stage, a 672px headline measure, 576px supporting measure, then an overlapping desktop-and-phone demonstration beginning within the first 900px.
- Conversion is violet and rectangular: #7c3aed buttons with 8px corners, white medium-weight text and a faint inset edge; the main landing action is 60px high, not a pill.
- Most of the page stays almost achromatic: #0f0f0f canvas, #1f1f1f cards, #eeeeee headings and #bcbcbc descriptions. Lavender #a78bfa belongs to links, fine outline icons and isolated demonstration backings, not continuous colored bands.
- Working interfaces are the primary visual proof: large dark application windows, overlapping devices and inset demonstrations clipped inside 12px cards. Every new landing page needs tangible product proof; use a carefully typeset representative workflow when finished product imagery is unavailable.
- A bright cutaway interrupts the dark tool world: a white functional panel inset 48px from the top and left of a roughly 544px lavender square with 24px outer corners. Recreate this device with a meaningful editor, control panel or output specimen.
- The closing becomes personal again: a centered 60px invitation and 60px violet action, followed by compact resource cards and a broad, unboxed footer with 96px top and 128px bottom padding.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#7c3aed` | `--color-violet` | action | Primary button fill and its focus outline. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender | `#a78bfa` | `--color-lavender` | link, accent, background | Text links, thin feature icons and isolated square demonstration backings. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Basalt canvas | `#0f0f0f` | `--color-canvas` | background | The continuous page ground; translucent navigation uses the same hue at 72% opacity. |
| Raised charcoal | `#1f1f1f` | `--color-card` | surface | Feature cards, resource cards and large editorial panels. |
| Control charcoal | `#262626` | `--color-control` | surface, border | Navigation hover fills, menu surfaces and subdued divider lines. |
| Secondary action gray | `#404040` | `--color-secondary-action` | action, border | Secondary filled actions and billing switch outline. |
| Faint gray | `#a3a3a3` | `--color-faint` | text | Footer group labels, utility controls and supporting captions. |
| Description gray | `#bcbcbc` | `--color-muted` | text | Supporting prose and navigation text. |
| Soft emphasis | `#e5e5e5` | `--color-emphasis` | text, border | Inline bold labels and brighter utility hover text. |
| Primary text | `#eeeeee` | `--color-text` | text | Headlines, card titles and footer links. |
| White | `#ffffff` | `--color-white` | text, surface | Button labels and bright demonstration panels; not the page canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing controls | Secondary hover gray | `#525252` | `--color-secondary-hover` | action | Hover fill and focus outline for gray secondary buttons. |
| pricing and inclusion statements | Confirmation green | `#22c55e` | `--color-success` | text, accent | Included-feature checks and the green underline of the free-offer statement. |

## Typography

- **ui-sans-serif** — All marketing headings, body text and controls. A system grotesk with an open, practical body and compact semibold headlines. Font stack: "ui-sans-serif", system-ui, -apple-system, Roboto, Inter, "Helvetica Neue", Arial, "Noto Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ui-sans-serif | 600 | 60px | 1 | -0.02em | Primary promise, major landing section headings and the closing invitation. |
| hero-support | ui-sans-serif | 400 | 36px | 40px | normal | Large two-line introductory description. |
| section-support | ui-sans-serif | 400 | 24px | 32px | normal | Lead paragraphs beneath section headings. |
| feature-title | ui-sans-serif | 600 | 24px | 32px | normal | Titles at the top of illustrated feature cards. |
| statement-link | ui-sans-serif | 500 | 24px | 32px | normal | Principle statements and inline lavender continuation links. |
| card-title | ui-sans-serif | 600 | 20px | 28px | normal | Resource cards, compact benefit groups and plan names. |
| feature-description | ui-sans-serif | 400 | 20px | 1.25 | normal | Descriptions in illustrated feature cards. |
| primary-label | ui-sans-serif | 500 | 20px | 28px | normal | Large landing and closing actions. |
| benefit-body | ui-sans-serif | 400 | 18px | 1.5 | normal | Inline feature-selection rows. |
| benefit-label | ui-sans-serif | 600 | 18px | 1.5 | normal | Short inline bold phrase before benefit prose. |
| column-body | ui-sans-serif | 400 | 18px | 24px | normal | Three-column benefit descriptions. |
| resource-body | ui-sans-serif | 400 | 18px | 1.25 | normal | Compact closing resource-card descriptions. |
| body | ui-sans-serif | 400 | 16px | 1.5 | normal | Plan details and normal-size functional text. |
| footer-link | ui-sans-serif | 500 | 16px | 1.25 | normal | Footer directory links. |
| footer-group | ui-sans-serif | 400 | 16px | 1.25 | normal | Muted labels grouping footer links. |
| nav-label | ui-sans-serif | 500 | 14px | 20px | normal | Navigation and small social links. |
| utility | ui-sans-serif | 400 | 14px | 20px | normal | Language selector and small utility text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing cards | price | ui-sans-serif | 600 | 48px | 1 | -0.025em | Plan price numerals with a small baseline currency label. |
| company pages | people-heading | ui-sans-serif | 600 | 48px | 1 | normal | Centered introduction to the people behind a product. |
| dedicated product and pricing pages | heading | ui-sans-serif | 600 | 36px | 40px | normal | More compact feature-chapter and FAQ headings. |
| service landing pages | product-support | ui-sans-serif | 400 | 30px | 1.2 | normal | Centered product introduction description. |
| editorial and company pages | editorial-body | ui-sans-serif | 400 | 18px | 28px | normal | Long-form principles and explanatory prose. |
| pricing and dedicated product pages | compact-action | ui-sans-serif | 500 | 16px | 1.5 | normal | 48px actions on plan cards and dedicated product pages. |
| dedicated product feature chapters | eyebrow | ui-sans-serif | 600 | 14px | 28px | 0.1em, uppercase | Lavender chapter label above a heading. |
| billing controls | switch-label | ui-sans-serif | 600 | 14px | 20px | normal | Yearly and monthly billing options. |
| customer-output galleries | gallery-caption | ui-sans-serif | 600 | 14px | 1.25 | normal | Centered gray credit beneath a linked work sample. |

**Notes:**

- Semibold display type is tightly tracked, but body, card titles and controls keep normal tracking. Do not carry the display tracking into paragraphs.
- Hierarchy comes from size and measure more than weight: regular 36px opening prose sits below 60px semibold type, while recurring support drops to 24px.
- Full stops in major headlines are part of the compact, declarative silhouette. Dedicated product pages also use multi-line centered headlines.
- Small code and interface text belongs within demonstrations, not the marketing type scale.

## Layout

**Density:** Airy between chapters, compact inside tools and cards; 96px section padding surrounds interfaces with much tighter internal spacing.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Utility icon-to-label spacing. |
| 8px | Footer list rhythm and small label separations. |
| 12px | Resource title-to-description separation and secondary action separation. |
| 16px | Close heading-to-description gaps and compact card padding. |
| 24px | Default card padding, grid gutters and action-row gap. |
| 32px | Hero headline-to-support gap, plan-card padding and split-column gutter. |
| 48px | Action separation, inset demonstration framing and larger media gaps. |
| 64px | Section-heading group to feature grid; introduction to wide demonstration. |
| 96px | Default chapter top and bottom padding and footer top padding. |
| 128px | Centered closing section padding and footer bottom padding. |

### Containers and grids

- **marketing-stage**: max width 1120px. Centered desktop content stage at 1440px, leaving 160px side margins. Align navigation, hero, wide product media and footer to this stage.
- **heading-measure**: max width 672px. Narrative section introductions; the block is centered in the stage but its text remains left-aligned.
- **opening-description**: max width 576px. Opening support line wraps earlier than its headline.
- **feature-grid**: 2 columns · gap 24px. Large, equally weighted illustrated feature cards.
- **split-demonstration**: 2 columns · gap 32px. Vertically centered text and feature selectors beside a square demonstration; text measure is 512px.
- **benefit-columns**: 3 columns · gap 48px. Unboxed icon, title and text columns above wide interface media.
- **resource-grid**: 3 columns · gap 24px. Compact all-clickable resource cards near the closing invitation.
- **plan-grid** (only for pricing pages): max width 752px · 2 columns · gap 24px. Two 364px plan cards with 32px internal padding.
- **editorial-panel** (only for company and editorial pages): max width 768px · side padding 48px. Centered long-form panel with a 672px readable interior.
- **people-grid** (only for company pages): max width 896px · 3 columns · gap 16px. Compact profile wall.
- **output-gallery** (only for customer-output galleries): max width 1296px · 3 columns · gap 16px. Wider-than-normal sample grid with small captions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 8px |
|  | feature-cards | 12px |
|  | bright-demonstration-frame | 24px |
| company and service closing panels | editorial-panels | 16px |
| company profiles | portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card-edge | `inset 0px 0px 0px 1px rgba(255,255,255,0.05)` | Faint structural edge rather than a conspicuous drop shadow. |
| interface-window | `0px 0px 0px 1px rgba(255,255,255,0.2), 0px 25px 50px -12px rgba(0,0,0,0.25)` | Large dark interface window against the dark page. |

### Surfaces

#### Basalt canvas · level 0

**Use:** Continuous marketing ground.

**CSS:** `background: #0f0f0f; color: #eeeeee`

#### Charcoal card · level 1

**Use:** Illustrated feature cards and compact link cards.

**CSS:** `background: #1f1f1f; border-radius: 12px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.05)`

**Observed:** Cards are flat charcoal slabs with very faint inset rims. A pointer-relative screen-blended radial mask is declared on the decorative layer.

**Transfer:** Use the same material for text-only resources and media-heavy cards, varying padding rather than inventing more elevations.

#### Lavender cutaway · level 1

**Use:** Signature backing for a bright functional specimen.

**CSS:** `background: #a78bfa; border-radius: 24px; padding: 48px 0px 0px 48px; overflow: hidden`

**Observed:** A white inner panel begins inward from the top-left and continues flush beyond the lower and right boundaries; the square outer frame clips it.

**Transfer:** Use an actual workflow fragment or a meaningful output, not abstract empty rectangles.

#### White specimen · level 2

**Use:** Bright functional panel inside the Lavender cutaway.

**CSS:** `background: #ffffff; color: #262626; border-top-left-radius: 12px; padding: 32px 32px 0px 32px`

**Observed:** The panel reads like a small, crisp editor or settings surface, with restrained gray rules and compact detail.

**Transfer:** Simplify the product to one understandable task and retain the white-on-lavender contrast.

#### Framed interface · level 1

**Use:** Wide standalone product demonstration.

**CSS:** `border-radius: 12px; box-shadow: 0px 0px 0px 1px rgba(255,255,255,0.2), 0px 25px 50px -12px rgba(0,0,0,0.25)`

**Observed:** Wide UI remains rectangular and legible, with its lower edge sometimes dissolving into the page through a short transparent-to-basalt gradient.

**Transfer:** Keep the application structure visible instead of treating the interface as a heavily blurred atmospheric texture.

#### Editorial slab · level 1

**Only for:** company and service closing panels

**Use:** Long-form introduction or contained closing action.

**CSS:** `background: #1f1f1f; border-radius: 16px; padding: 48px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.05), 0px 25px 50px -12px rgba(0,0,0,0.25)`

**Observed:** The company variant is a narrow readable panel; the service closing variant expands across the main stage with centered content and 96px vertical padding.

**Transfer:** Contain a coherent reading or conversion task rather than boxing every paragraph.

## Components

### Fixed navigation

**Use:** Persistent site orientation.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 68px; z-index: 50; background-color: rgba(15,15,15,0.72); border-bottom: 1px solid rgba(38,38,38,0.72); display: flex; align-items: center; justify-content: center`

**Text style:** `nav-label` — ui-sans-serif 500 · 14px/20px

**Observed:** A compact symbol-and-wordmark sits left, followed by plain product links. Language, community and account controls occupy the right. Links use 8px 12px padding and 8px rounded hover areas. A 74px-high variant with 54.5% background opacity belongs to service and company pages.

**States:** Declared: hover navigation link becomes #ffffff on #262626.

### Primary button

**Use:** Main conversion at the opening and closing.

**CSS:** `background-color: #7c3aed; color: #ffffff; border-radius: 8px; padding: 16px 24px; height: 60px; text-align: center; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.1), 0px 1px 3px 0px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `primary-label` — ui-sans-serif 500 · 20px/28px

**Observed:** The opening action can append the detected platform. A plain text alternative sits beside it, 24px away. The closing variant has 32px horizontal padding. Dedicated product actions use compact-action, 48px height and 12px 24px padding; plan actions use 12px 16px padding and fill the card interior.

**States:** Declared: hover background becomes rgb(139 92 246 / 1), text stays white; focus-visible outline #7c3aed solid 2px with 2px offset.

### Continuation link

**Use:** In-line next step at the end of a section description.

**CSS:** `color: #a78bfa; text-decoration: none`

**Text style:** `statement-link` — ui-sans-serif 500 · 24px/32px

**Observed:** Reads as a continuation of the paragraph rather than a separate button; the short label carries a full stop.

**States:** Declared: hover color becomes rgb(196 181 253 / 1); focus-visible behavior is unspecified.

### Illustrated feature card

**Use:** Explain one core capability through text and a working visual.

**CSS:** `background-color: #1f1f1f; border-radius: 12px; overflow: hidden; display: flex; flex-direction: column; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.05)`

**Text style:** `feature-title` — ui-sans-serif 600 · 24px/32px

**Observed:** Title and feature-description occupy a 24px-padded upper region, separated by 4px. A substantial functional illustration fills the lower region and is clipped by the card. The desktop two-column version is roughly 548px wide and 547px tall.

**Transfer:** Make the lower visual demonstrate the promise in the title, rather than repeat an icon at huge scale.

### Feature selector row

**Use:** Connect a short benefit explanation to the adjacent demonstration.

**CSS:** `position: relative; padding: 16px 12px 16px 36px; border-radius: 8px`

**Text style:** `benefit-body` — ui-sans-serif 400 · 18px/1.5

**Observed:** A lavender 24px outline icon occupies the leading gutter. An inline semibold benefit-label ends in a period, followed immediately by regular prose. One selected row receives a charcoal backing while neighboring rows remain unboxed.

**Transfer:** Switch the adjoining visual with the selected benefit while preserving the text column's height.

### Resource card

**Use:** Secondary paths after the main closing action.

**CSS:** `background: #1f1f1f; border-radius: 12px; padding: 24px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.05)`

**Text style:** `card-title` — ui-sans-serif 600 · 20px/28px

**Observed:** The whole card is a link. A resource-body description follows the title after 12px; no oversized badge or media is needed. Desktop cards form three equal columns.

### Footer directory

**Use:** Shared ending on every page type.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); column-gap: 12px; row-gap: 24px; padding-left: 24px`

**Text style:** `footer-link` — ui-sans-serif 500 · 16px/1.25

**Observed:** The directory takes the right half of the stage. On the left sit the compact wordmark, two columns of social links, language selector and copyright. Faint footer-group labels divide multiple lists; list items have 8px top spacing. The outer footer has 96px top and 128px bottom padding and no separate colored band.

**States:** Declared: hover links become #a78bfa.

### Language selector

**Use:** Footer utility and compact header localization control.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 6px 12px; border-radius: 8px; color: #a3a3a3; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.1)`

**Text style:** `utility` — ui-sans-serif 400 · 14px/20px

**Observed:** A globe precedes the label and a chevron sits at the trailing edge. The footer version is 160px wide and 32px high; its menu opens upward with a charcoal backing and compact rows.

**States:** Declared: hover text becomes #e5e5e5 and background #262626.

### Secondary button

**Only for:** pricing pages

**Use:** Non-conversion detail action directly beneath the primary plan action.

**CSS:** `background-color: #404040; color: #ffffff; border-radius: 8px; padding: 12px 16px; height: 48px; display: block; text-align: center`

**Text style:** `compact-action` — ui-sans-serif 500 · 16px/1.5

**Observed:** Fills the 300px card interior and follows the violet action after 12px.

**States:** Declared: hover background #525252 with white text; focus-visible outline #525252 solid 2px with 2px offset.

### Billing switch

**Only for:** pricing controls

**Use:** Two-option billing-period selection.

**CSS:** `border: 1px solid #404040; border-radius: 8px; padding: 2px; max-width: 300px`

**Text style:** `switch-label` — ui-sans-serif 600 · 14px/20px

**Observed:** Two equal-width options sit inside a 28px-high track. The active choice is white on a gray rounded inset block; the other remains muted. The service pricing variant is 223px wide.

### FAQ row

**Only for:** pricing pages

**Use:** Answer practical purchase objections before the footer.

**CSS:** `padding: 24px 0px; border-bottom: 1px solid #262626`

**Text style:** `card-title` — ui-sans-serif 600 · 20px/28px

**Observed:** Rows fill a centered 672px measure. The question sits left and a small downward chevron aligns right. The group follows a heading and support paragraph, then ends with a short help link.

### Profile card

**Only for:** company pages

**Use:** Introduce individuals without a corporate portrait treatment.

**CSS:** `background: #1f1f1f; border-radius: 8px; padding: 16px; display: flex; flex-direction: column; gap: 16px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.05)`

**Text style:** `card-title` — ui-sans-serif 600 · 20px/28px

**Observed:** A 120px circular photo appears above the name, compact handle and role, and a short 14px personal biography. Cards are about 288px wide and 284px high.

## Imagery and graphics

### Overlapping working tools

**Use:** Opening product proof and large capability demonstrations.

**Observed:** A large front-facing desktop window anchors the page with a smaller portrait phone overlapping its lower-right edge. Dark title bars, sidebars, tabs, text and node-link diagrams remain recognizable; the interface is not tilted into perspective. In the opening the desktop window is about 963px wide and the phone is 220px wide by 440px tall.

**Transfer:** Stage the new product at a meaningful working moment. If product media is unavailable, construct a clean front-facing interface specimen with a real task, sidebar and useful output; keep the device overlap and substantial scale.

### Bright functional cutaway

**Use:** High-contrast visual punctuation within an otherwise dark landing page.

**Observed:** A lavender square frames a white application fragment, offset down and right. Black-gray text, thin pale rules and small controls give the white panel a useful, document-like character. The two versions show a member list and a theme editor; the outer backing remains simple and flat.

**Transfer:** Show a small, understandable function of the new product. A well-typeset white output sheet is the minimum equivalent if a complete interface cannot be drawn.

**Build:** Make a 544px square with background #a78bfa, 24px radius and overflow hidden. Inset the white panel 48px from the top and left, give it a 12px top-left corner and at least 496px height, and let it extend to the right and lower edges. Add a short dark title and 3–5 purposeful rows with pale separators. Keep the lavender exposed as an L-shaped top-and-left margin.

### Inset capability scenes

**Use:** Lower region of Illustrated feature card.

**Observed:** Miniature editors, menus, a fine gray node-link network with a few green nodes, and canvas-like connected cards sit in darker inner workspaces. The scene starts below the short copy and is clipped at the card's lower edge.

**Transfer:** Use a different scene for each capability while keeping the same dark framing and legible task structure. Diagrams should explain actual relationships rather than serve as random particle decoration.

### Tablet and phone pair

**Only for:** mobile product pages

**Use:** Large media below each feature chapter.

**Observed:** Front-facing tablets dominate the 1120px stage, with a narrow phone overlapping at one side. Black device bezels are thin and outlined; both light and dark interfaces are shown against the unchanged dark page. The devices are not embedded in lifestyle photographs.

**Transfer:** Pair two relevant form factors, alternating overlap side when useful. Let genuine interface contrast create variety rather than changing the marketing canvas.

### Output gallery

**Only for:** customer-output showcases

**Use:** Late-page proof of what customers can produce.

**Observed:** A three-column, two-row display of mostly light web pages. Each image uses a 3:2 frame, 8px rounded corners and a centered faint-gray semibold credit 16px below it. The gallery expands beyond the normal stage to 1296px.

**Transfer:** Use genuine finished outputs with enough visual variation to prove flexibility, but keep every frame and caption consistent.

### Circular personal portraits

**Only for:** company pages

**Use:** Profile wall.

**Observed:** Small circular color photos show people in varied everyday settings, with casual framing rather than matched studio lighting. They sit top-left in compact charcoal cards.

**Transfer:** Keep natural photos and distinct personalities; use a consistent 120px circular mask without forcing identical photographic backdrops.

### Icons

**Observed:** Feature icons are lavender outline SVGs, commonly 24px with 1.8px round strokes. Utility icons use 16px boxes and 2px round strokes. Pricing checks are green 24px outline marks; store actions use small white solid platform marks.

**Transfer:** Use one rounded-stroke outline family for marketing features, small utility glyphs for controls, and solid logos only when representing platforms.

## Section recipes

How recurring sections are built.

### First screen: Workbench opening

**Observed:** The fixed navigation occupies a slim 68px strip. Below it, a left-aligned 60px semibold single-line promise sits in the left portion of the 1120px stage, beginning after 96px of opening padding. Its 36px regular support line is 32px below and wraps into two lines within 576px. After 48px, a 60px Primary button and lavender alternative form one action row. The large dark desktop-and-phone scene begins around 538px down the page: at 900px the title, support, actions and upper two-thirds of the desktop interface are visible, with the phone entering on the right. The full lower demonstration continues below the fold. Layers are basalt ground, interface window, then foreground phone; the open right side above the media stays empty.

**Transfer:** Keep a concise benefit at the top-left and let a meaningful product specimen take over the lower half. Without finished media, build the Overlapping working tools treatment around a representative task. Dedicated service pages instead center a two-line promise in a 768px measure with a small lavender product label and 48px action; mobile product pages center the promise above paired devices. Pricing opens with a centered offer, and editorial pages open inside the Editorial slab.

**Avoid:** Do not replace the first screen with a centered giant slogan over a gradient orb, a tiny floating mockup, or equal-sized action pills. The workbench needs visible, substantial working content before the fold.

**Text style:** `display` — ui-sans-serif 600 · 60px/1 · tracking -0.02em

### Principle list and emblem

**Observed:** A two-column interlude pairs a readable list with a raised square application emblem. Short 24px medium statements precede 24px regular explanations; thin top dividers and 16px list gaps give structure. A small download link sits under the emblem.

**Transfer:** Use this composition for concise product assurances or operating principles relevant to the buyer, pairing the text with a product symbol rather than another full interface.

### Heading pair and illustrated grid

**Observed:** A centered 672px text block retains left alignment. A display headline leads its section-support paragraph by 16px, followed by 64px before a two-column feature-grid of Illustrated feature card.

**Transfer:** Frame a small set of core capabilities with one larger outcome, then make each illustrated card prove a different part of that outcome.

**Text style:** `display` — ui-sans-serif 600 · 60px/1 · tracking -0.02em

### Split interactive chapter

**Observed:** The split-demonstration layout pairs a 512px text measure with the Lavender cutaway. A display headline and 24px support line precede Feature selector rows after 32px. Each selector begins with a thin icon, and the selected row has a charcoal backing. The whole chapter uses 96px vertical padding.

**Transfer:** Give each selector a distinct meaningful visual state. The service-page variant can reverse the image and text and use eyebrow plus heading instead of display.

### Wide demonstration and benefits

**Observed:** A left-aligned display heading and 24px supporting paragraph introduce three unboxed benefit-columns. Each has a lavender outline icon, card-title and column-body. A Framed interface follows 64px below. Its lower edge is clipped and softly faded to basalt, with a restrained centered caption beneath.

**Transfer:** Use this for a workflow whose depth is best understood through one large interface. Keep the benefit text short enough that the demonstration remains the focus.

### Personal closing invitation

**Observed:** A centered display invitation is followed 48px later by the Primary button. The surrounding section uses 128px vertical padding. Three Resource cards form a lower row, about 128px after the action. The Footer directory follows on the same continuous dark ground.

**Transfer:** End a general landing page with a reader-centered outcome and one clear next step, then useful secondary paths. A dedicated service page can contain its closing heading, support and compact action in the Editorial slab. A mobile page can close with a product emblem and paired store buttons; neither needs a duplicate resource row.

**Text style:** `display` — ui-sans-serif 600 · 60px/1 · tracking -0.02em

### Centered offer and plan pairs

**Only for:** pricing pages

**Observed:** A centered 60px offer has a green underline, followed by a 36px semibold reassurance split over two lines. Considerable dark space separates this from a 24px offer explanation, Billing switch and paired Charcoal cards. Each plan stacks name, 48px price, small currency and billing cadence, violet action, gray action and a green-check inclusion list. A second pair can introduce optional support purchases. The page ends with FAQ row and the shared footer, not a forced promotional closing.

**Transfer:** Separate the core value proposition from optional paid services. Use simple comparable cards and explicit billing units rather than decorative recommended-plan badges.

### Compact performance cards

**Only for:** dedicated service pages

**Observed:** A lavender uppercase eyebrow, 36px heading and 24px support line introduce a two-by-two grid of charcoal cards with 16px gutters. Each card contains a thin lavender icon, 20px semibold title and 18px/24px explanation; cards are approximately 552px wide and 219px high.

**Transfer:** Group assurance and technical quality claims into short, readable proof cards; no numerical statistic is needed when the strongest proof is practical.

### Editorial opening and people wall

**Only for:** company pages

**Observed:** An Editorial slab opens with a lavender 20px label, 60px headline, 24px support and repeated 18px bold subheads with 18px/28px prose. After 144px, a centered 48px people-heading leads the people-grid. The final content is a short centered contribution acknowledgment with an inline lavender credit link, then the shared footer.

**Transfer:** Use the opening for a sustained point of view, the profile wall for individual credibility and the final acknowledgment for the wider network behind the product.

## Page flow

**Storyline:** Personal promise → tangible working proof → reasons to trust → capability chapters → useful next action → resource directory; depth and order adapt to the page's purpose.

### General product landing page

1. **Promise** — Left-aligned short outcome, large regular support and platform-specific action.
2. **Product demonstration** — Overlapping desktop and phone scene.
3. **Trust** — Brief principle list paired with an application emblem.
4. **Capability chapters** — Illustrated two-column cards, a split bright cutaway and a wide dark demonstration.
5. **Closing call** — Centered personal invitation, large action and three secondary resource cards.
6. **Directory** — Shared broad footer with social, language and grouped links.

**Transfer:** Make the product feel like a useful personal tool before presenting service depth; retain the media-led proof and personal close without reproducing a fixed chapter count.

### Pricing and purchase reassurance

1. **Offer** — Centered offer statement with green underline and a strong two-line reassurance.
2. **Pricing** — Billing switch and two balanced plan cards.
3. **Business model** — Centered explanatory heading and optional-support card pair.
4. **Objection handling** — Narrow FAQ, then a short help continuation.
5. **Directory** — Shared footer; no additional conversion panel.

**Transfer:** Explain what is available before discussing optional purchases, and resolve practical doubts just before the directory.

### Mobile product landing page

1. **Promise** — Lavender product label, centered multiline display, short support and paired store actions.
2. **Product demonstration** — Large tablet-and-phone pairing.
3. **Capability chapters** — Narrow left-aligned heading and prose above successive full-width device pairs.
4. **Closing call** — Raised product emblem and repeated paired store buttons.
5. **Directory** — Shared footer.

**Transfer:** Use real device-scale proof of continuity and touch-oriented functionality rather than a feature-card-heavy desktop story.

### Dedicated service landing page

1. **Promise** — Centered display with lavender product label, 30px description, compact action and adjacent price link.
2. **Capability chapters** — Split selector-and-interface introduction, wide authoring demonstration and a contained pricing panel.
3. **Control and assurance** — Reversed bright cutaway chapter followed by compact performance cards.
4. **Output proof** — Wide grid of varied light customer outputs with centered credits.
5. **Closing call** — Centered contained charcoal panel with heading, support, compact action and price link.
6. **Directory** — Shared footer.

**Transfer:** A focused service can foreground the result, then explain operation, price, control and proof without borrowing the general landing page's left-aligned opening.

### Company and editorial page

1. **Point of view** — Narrow charcoal editorial panel with a display heading and repeated short principle subheads.
2. **People** — Centered heading and three-column profile wall.
3. **Acknowledgment** — Short centered contributor statement with credit link.
4. **Directory** — Shared footer, with no unrelated product CTA.

**Transfer:** Let readable prose and individual voices establish credibility while preserving the same dark materials and type hierarchy.

## Writing

Direct, independent and warmly practical. The copy makes the product feel like a tool under the reader's control, with plain benefits followed by concrete explanations rather than marketing spectacle.

**Do not copy:** Do not reuse Obsidian's name, logo, product-interface content, personal identities, proprietary illustrations, claims about privacy or independence, prices, community examples or exact marketing slogans. Source examples below demonstrate cadence only; all new facts and claims must belong to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your, especially their work and desired outcomes. Use we for beliefs and responsibility; use the product name when explaining concrete operation.
- **Rhythm:** Major headlines are often two or three words with a full stop. Support lines are usually one clear sentence. Feature rows begin with a short bold phrase, then explain the practical consequence in regular prose.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A short imperative promises a personal improvement; dedicated product introductions can stretch to one compact sentence. | 3–10 words | “Sharpen your thinking.”<br>“Give your knowledge a home on the web.” |
| Section heading | Verb and adverb, or a compact familiar phrase that makes capability feel immediate. | 2–4 words | “Sync securely.”<br>“Speed of thought” |
| Supporting line | Say what the tool is or what the reader can do; keep the benefit specific and free of inflated adjectives. | 10–24 words | “The free and flexible app for your private thoughts.”<br>“Access your notes on any device, secured with end-to-end encryption.” |
| Feature explanation | Short bold noun phrase with a period, then one practical sentence. | 15–30 words | “Version history. Easily track changes between revisions, with one year of version history for every note.” |
| Primary action | Plain verb plus product, destination or result; platform actions name the store. | 2–5 words | “Create your site”<br>“More platforms” |
| Reassurance | Remove a concrete concern with short parallel declarations. | 3–12 words | “No sign-up required. No strings attached.” |
| Closing invitation | Return attention to the reader's outcome rather than the company. | 4–7 words | “It’s your time to shine.” |

**Words and phrasing to use:** your; tools; ideas; create; make it your own; instantly; simple; control; explore

**Avoid:** revolutionary; game-changing; unlock limitless potential; next-generation ecosystem; synergy; dominate

**Rules:**

- Pair each promise with an explanation of how it works or what changes for the reader.
- Use familiar metaphors sparingly to make technical functions understandable.
- Prefer explicit billing cadence and plain purchase terms to sales urgency.
- Allow the occasional personal aside in biographies, but keep product descriptions factual.
- Put technical terms in useful context rather than using them as status signals.

## Do's and Don'ts

### Do

- Keep the largest marketing headings at 60px/1 and weight 600 with -0.02em tracking.
- Keep opening support at 36px/40px and regular weight so it feels conversational beneath the headline.
- Use the 1120px desktop stage and 672px readable heading measure to alternate broad proof with focused prose.
- Retain 8px button corners, 12px feature-card corners and 24px lavender demonstration corners as distinct scales.
- Use 24px feature-grid gutters and 32px split-column gutters.
- Show useful interfaces large enough to read their structure; retain the white-on-lavender cutaway as visual punctuation.
- Use #bcbcbc for descriptions, reserving #eeeeee for the hierarchy and #a78bfa for continuation links and fine icons.
- Give the shared footer 96px above its content and 128px below it rather than squeezing it into a thin strip.

### Don't

- Do not set all headings to heavy 700–900 weights; the 600-weight silhouette is important.
- Do not change the full dark canvas to pure black or alternate entire chapters with white bands; the white areas belong to functional media.
- Do not turn every lavender text link into a filled button; inline continuation is a recurring hierarchy level.
- Do not use rounded pills for primary actions; the measured rectangular 8px construction should remain recognizable.
- Do not add loud drop shadows to ordinary charcoal cards; their edge is a 5% white inset line.
- Do not sprinkle orange, cyan or pink accents through the marketing layout; extra colors belong to meaningful interface detail.
- Do not make the gallery credits as prominent as feature headings; keep them at 14px and faint gray.
- Do not force a sales CTA onto every editorial or pricing ending; acknowledgment or practical help can lead directly into the directory.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color and background transitions at 150ms cubic-bezier(0.4, 0, 0.2, 1).
- The fixed header declares all-property transition at 0.25s cubic-bezier(0.4, 0, 0.2, 1).
- Card decoration declares a 700px pointer-relative radial mask with screen blending; the emblem tile declares transform 1s and box-shadow 2000ms ease-in-out.
- Selected feature rows are paired with active demonstration panels.

**Transfer:**

- Keep interaction feedback primarily in color and selected-row backing; the page's identity does not depend on entrance choreography.
- If implementing the pointer shimmer, keep it at the faint rim/material level rather than a bright moving spotlight over text.

**Unknown:**

- Exact feature-switch timing, autoplay behavior and pointer-response trajectory are unspecified.
- No settled entrance-animation sequence is established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- The opening headline class declares 13vw with 1.1 line height below the small breakpoint, then the 60px title treatment.
- The opening text is centered below the small breakpoint and left-aligned above it; its action row changes from column to row.
- Illustrated cards declare one column then two at the medium breakpoint; split chapters declare two columns at the large breakpoint. The desktop navigation list is hidden below the medium breakpoint.

**Transfer:**

- Preserve the overlapping product scene on narrow screens with a deliberate clipped wide stage rather than shrinking interface content until illegible.
- Stack the cutaway and text on narrow screens; keep the lavender top-left reveal but reduce its inset from 48px to the declared 24px horizontal and 32px vertical compact treatment.
- Let the footer directory move above the identity block and reduce to two columns, retaining the grouped-link rhythm.

**Unknown:**

- Only desktop layouts are established visually; exact mobile media cropping, menu interaction and all intermediate widths remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
