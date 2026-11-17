# Paradigm — editorial workflow theatre

## Overview

An editorial serif gives technical software an unusually literary, assured presence, while compact grotesk text keeps the explanation practical. Pale gray and white content fields sit between near-black bookends, with cool blue gradients reserved for staged interface illustrations. The imagery is product-led: enlarged interface details, floating workflow cards and dense working tables rather than lifestyle photography. It suits complex business products that need an expansive introduction and a more systematic, moderately dense explanation below.

### Essentials

- Literary promises, operational detail: Atacama headlines at 55px/1.15 with -0.05em tracking give way to 40.4px/1.15 section headings with -0.06em tracking; Neue Montreal carries the practical text.
- The opening feels like standing inside the product: a full-bleed enlarged interface scene behind a lower-left, 672px-wide text group, one pale 44px action and a 71px dark navigation bar. Use a constructed interface macro if no finished product film exists.
- A ruled editorial chassis holds the page together: a 1060px content span at 1440px, 0.5px separators and vertical rails, 120px section padding, and equal 530px feature halves with 32px copy insets.
- Actions are deliberately unrounded: 44px-high rectangles, 8px 24px padding, 14px/1.6 medium text and an understated 16px arrow. Outline actions belong in the dark navigation; pale filled actions punctuate dark scenes.
- Color is scenery rather than decoration: most of the long-form body stays white or pale gray, near-black frames the opening and closing, and blue occupies bounded demonstration panels rather than entire content bands.
- Small white cards float inside blue architectural stages: 530×600px panels, a 135deg steel-blue-to-ice gradient, 320px-wide cards with 4px corners and fine shadows. Every landing page needs this staged demonstration device; a simple three-card SVG or HTML workflow is the minimum equivalent.
- The ending is a real design event, not a link dump: a dark, ruled closing area combines a small identity, a 40.4px serif imperative, a pale action and five compact navigation columns. Preserve this closing device with new words and an appropriate identity.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0a33ff` | `--color-blue` | text, border, accent | Focus outlines on light fields and short underlines; promotional text and border only in pricing. |
| Lit blue | `#4c7de8` | `--color-deep-light` | background | Lower glow in deep demonstration stages. |
| Horizon blue | `#103b91` | `--color-deep-mid` | background | Middle of the deep demonstration gradient. |
| Steel blue | `#7b95c4` | `--color-stage-blue` | background | Darker upper-left end of the soft demonstration gradient. |
| Periwinkle light | `#bad0ff` | `--color-deep-base` | background | Bottom of deep demonstration stages. |
| Ice blue | `#dfecff` | `--color-stage-ice` | background | Light lower-right end of the soft demonstration gradient. |
| Deep night | `#010818` | `--color-deep-night` | background | Upper dark hold of deep demonstration stages. |
| Night blue | `#010b18` | `--color-deep-top` | background | Top of deep demonstration stages. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool paper | `#f6f7f8` | `--color-canvas` | background, text, action | Page canvas, pale action fill and inverse headline text. |
| Midnight ink | `#080b12` | `--color-ink` | text, background, action | Primary text, dark bands and inverse pricing buttons. |
| Dark hairline | `#3c3f45` | `--color-rule-inverse` | border | Visible pale 22% rule over midnight ink; use rgba(246,247,248,0.22). |
| Graphite | `#606167` | `--color-muted` | text, link | Supporting prose and light-theme labels. |
| Silver text | `#b7b7bb` | `--color-muted-inverse` | text, link | Dark-theme eyebrows, support text and navigation. |
| Light hairline | `#d0d1d4` | `--color-rule` | border | Visible neutral edge on cool paper; made with midnight-violet rgba(8,8,23,0.16). |
| Silver paper | `#f0f0f2` | `--color-sunken` | background, surface | FAQ and standalone statement bands; explanatory half of task panels. |
| White | `#ffffff` | `--color-raised` | surface, background, text | Explanatory bands and floating cards. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Blue pricing wash | `#e7ebff` | `--color-pricing-wash` | surface | Visible 10% electric-blue wash on a white pricing card. |

## Typography

- **Atacama-b538b26c81f7b413** — Display promises, section headings and closing imperatives. Fine, high-contrast editorial serif, with narrow proportions, sharp serifs and conspicuously tight spacing. If unavailable, use **Instrument Serif**. Use regular weight; tune width before increasing size. Font stack: "Atacama-b538b26c81f7b413", "Instrument Serif", Palatino, Garamond, Cambria, Georgia, serif.
- **Neue Montreal-664db4e45422dff6** — Body prose, navigation, actions, cards and small labels. Compact modern grotesk with understated medium weights and a high working density. If unavailable, use **Inter**. Use weights 400–600 and preserve role-specific tracking. Font stack: "Neue Montreal-664db4e45422dff6", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Atacama-b538b26c81f7b413 | 400 | 55px | 1.15 | -0.05em | fixed | Default media-backed landing promise, balanced over two lines. |
| heading | Atacama-b538b26c81f7b413 | 370 | 40.4px | 1.15 | -0.06em | size clamp(1.75rem, 0.86rem + 1.85vw, 2.75rem) | Section leads, statement bands and closing call. |
| lead | Neue Montreal-664db4e45422dff6 | 450 | 18px | 1.5 | -0.015em | size clamp(0.9375rem, 0.84rem + 0.35vw, 1.125rem) | Hero support and short section introductions. |
| question | Neue Montreal-664db4e45422dff6 | 400 | 18px | 1.5 | -0.015em | fixed | FAQ summaries. |
| feature-body | Neue Montreal-664db4e45422dff6 | 500 | 16px | 1.5 | normal | fixed | Default practical explanation beside illustration stages. |
| body | Neue Montreal-664db4e45422dff6 | 450 | 16px | 1.5 | -0.01em | size clamp(0.9375rem, 0.91rem + 0.1vw, 1rem) | Longer answers and explanatory paragraphs. |
| text-link | Neue Montreal-664db4e45422dff6 | 400 | 15px | 1.387 | -0.02em | fixed | Underlined feature-detail links with a separate arrow. |
| action | Neue Montreal-664db4e45422dff6 | 500 | 14px | 1.6 | -0.015em | fixed | All rectangular conversion buttons. |
| navigation | Neue Montreal-664db4e45422dff6 | 500 | 14px | 1.43 | -0.02em | fixed | Header links. |
| workflow-title | Neue Montreal-664db4e45422dff6 | 500 | 14px | 1.25 | -0.015em | fixed | Titles inside floating demonstration cards. |
| small-copy | Neue Montreal-664db4e45422dff6 | 400 | 14px | 1.486 | -0.015em | fixed | Catalog descriptions and pricing feature lists. |
| footer-heading | Neue Montreal-664db4e45422dff6 | 600 | 13px | 1.54 | -0.01em | fixed | Compact footer column headings. |
| eyebrow | Neue Montreal-664db4e45422dff6 | 500 | 12px | 1.667 | 0.14em, uppercase | fixed | Numbered capability labels and thematic section markers. |
| footer-link | Neue Montreal-664db4e45422dff6 | 500 | 12px | 1.667 | -0.01em | fixed | Footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| text-led feature and pricing pages | feature-display | Atacama-b538b26c81f7b413 | 317 | 55px | 1.15 | -0.05em | fixed | Lighter display variant on solid fields; left aligned for features and centered for pricing. |
| pricing pages | plan-title | Neue Montreal-664db4e45422dff6 | 400 | 24px | 1.167 | -0.02em | fixed | Plan names and equally sized monetary amounts; prices are muted, not giant statistics. |
| process explanations | step-title | Neue Montreal-664db4e45422dff6 | 500 | 18px | 1.3 | -0.015em | size clamp(1rem, 0.94rem + 0.22vw, 1.125rem) | Three-column step headings. |
| searchable catalogs | catalog-title | Neue Montreal-664db4e45422dff6 | 500 | 16px | 1.375 | normal | fixed | Linked card titles. |
| process explanations | step-number | Neue Montreal-664db4e45422dff6 | 500 | 13px | 1 | normal | fixed | Small square process markers. |
| catalogs and pricing annotations | tag | Neue Montreal-664db4e45422dff6 | 400 | 12px | 1.667 | -0.01em | fixed | Small data tags and promotional badge text. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Serif spacing tightens from -0.05em at display size to -0.06em for section headings; keep the fine weight rather than making headings bold.
- The grotesk hierarchy changes primarily through size and spacing, not heavy weight. The uppercase eyebrow is the exception to otherwise negative or neutral tracking.
- Keep display text as balanced phrases with deliberate line breaks; paragraph text remains left aligned, including on dark fields.

## Layout

**Density:** Airy at section scale, compact at interface and catalog scale; large pauses separate tightly organized explanations.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Heading-to-support gaps and action icon gaps. | fixed |
| 12px | Floating-card padding and catalog grid gaps. | fixed |
| 16px | Hero text stack, prose groups and item spacing. | fixed |
| 20px | Catalog card and footer-cell padding. | fixed |
| 24px | Feature text stacks and FAQ summary vertical padding. | fixed |
| 32px | Copy insets inside ruled frames. | fixed |
| 40px | Short social-proof band padding and split-heading gap. | fixed |
| 72px | Horizontal inset of the dark trust panel and its large internal separation. | fixed |
| 80px | Identity-to-closing-headline separation; spacious internal section gaps. | clamp(2.5rem, 6vw, 5rem) |
| 120px | Major section top and bottom padding. | fixed |

### Containers and grids

- **Editorial chassis**: max width 1920px · side padding 190px. Outer website frame at desktop; at 1440px this creates a centered 1060px working span. Vertical rails mark its edges rather than enclosing every section in a rounded box.
- **Feature halves**: 2 columns · gap 0px. Equal 530px text and demonstration halves; alternate the illustration side between chapters.
- **Header frame**: max width 1920px · side padding 20px. Full-width navigation with identity left, links centered and account actions right; not aligned to the narrower editorial column.
- **Question split**: 3 columns · gap 24px. Short heading and help text in the first column; accordion occupies the other two columns, each with 32px text insets.
- **Footer grid**: 5 columns · gap 0px. Five ruled 212px navigation cells across the working span.
- **Catalog grid** (only for searchable catalogs): 3 columns · gap 12px. Equal-height 345px-wide cards within the editorial chassis.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Conversion buttons | 0px |
|  | Content cards | 4px |
| catalogs | Data tags | 2px |
| pricing pages | Promotional badge | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Workflow lift | `0px 3px 6px rgba(7,7,22,0.04), 0px 2px 4px rgba(7,7,15,0.03), 0px 1px 2px rgba(8,8,18,0.02)` | Floating cards on illustration stages. |
| Stage lift | `0px 16px 24px rgba(10,12,30,0.06), 0px 8px 16px rgba(8,10,25,0.05), 0px 4px 8px rgba(7,7,15,0.04), 0px 2px 4px rgba(7,7,15,0.03)` | Large blue demonstration panels, not ordinary catalog cards. |

### Surfaces

#### Cool canvas · level 0

**Use:** Light page field.

**CSS:** `background: #f6f7f8; color: #080b12`

#### White explanation band · level 0

**Use:** Capability chapters and catalogs.

**CSS:** `background: #ffffff; border-top: 0.5px solid rgba(8,8,23,0.16)`

**Observed:** Broad rectangular bands keep the chassis rails visible.

**Transfer:** Use full-width bands, with content constrained inside.

#### Sunken statement band · level 0

**Use:** FAQ groups and editorial statements.

**CSS:** `background: #f0f0f2; border-top: 0.5px solid rgba(8,8,23,0.16)`

#### Dark ruled field · level 0

**Use:** Opening backing, trust interlude and closing area.

**CSS:** `background: #080b12; color: #f6f7f8; border-top: 0.5px solid rgba(246,247,248,0.22)`

**Observed:** Faint horizontal rules and outer vertical rails define large empty areas; the dark field is flat rather than glowing.

**Transfer:** Keep the inverse section sparse and typographic.

#### Soft blue stage · level 1

**Use:** Signature demonstration backing.

**CSS:** `background: linear-gradient(135deg, #7b95c4, #dfecff); padding: 20px; overflow: hidden; box-shadow: 0px 16px 24px rgba(10,12,30,0.06), 0px 8px 16px rgba(8,10,25,0.05), 0px 4px 8px rgba(7,7,15,0.04), 0px 2px 4px rgba(7,7,15,0.03)`

**Observed:** Square-edged 530×600px panel carrying small white cards; the shorter task-panel variant is about 530×434px.

**Transfer:** Stage only the few objects needed to explain one workflow.

#### Deep blue stage · level 1

**Use:** Alternate validation and product demonstration backing.

**CSS:** `background: linear-gradient(#010b18, #010818 16%, #103b91 49%, #4c7de8 78%, #bad0ff 97%); padding: 20px; overflow: hidden`

**Observed:** An almost black top opens into a bright blue horizon and pale bottom behind a white result card.

**Transfer:** Use the light gradient to separate the result from the dark upper environment.

#### Fine-edge card · level 1

**Use:** Catalog and pricing grouping.

**CSS:** `background: #ffffff; border: 0.5px solid rgba(8,8,23,0.16); border-radius: 4px`

**Observed:** Flat cards have no visible decorative elevation; shadows belong to staged illustration cards instead.

**Transfer:** Use for functional collections, with regular gutters and content-driven height.

## Components

### Primary button

**Use:** Main conversion action on dark or media-backed fields.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 8px 24px; background: #f6f7f8; color: #080b12; border: 0.5px solid transparent; border-radius: 0px`

**Text style:** `action` — Neue Montreal-664db4e45422dff6 500 · 14px/1.6 · tracking -0.015em

**Observed:** Default landing variant has a right arrow after the label; solid-field feature introductions use the label alone. Pricing inverts the fill to ink with white text.

**States:** Declared: hover opacity 0.75; focus-visible border-radius 2px, outline 2px solid #e2efff, outline-offset 3px. Pricing uses #0a33ff for the focus outline.

### Outline button

**Use:** Compact header conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 8px 24px; color: #f6f7f8; background: transparent; border: 0.5px solid #f6f7f8; border-radius: 0px`

**Text style:** `action` — Neue Montreal-664db4e45422dff6 500 · 14px/1.6 · tracking -0.015em

**Observed:** Sits after a subdued account link at the right edge of the navigation.

**States:** Declared: hover opacity 0.75; focus-visible border-radius 2px, outline 2px solid #e2efff, outline-offset 3px.

### Navigation

**Use:** Persistent orientation over long pages.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 71px; background: #080b12; color: #b7b7bb; border-bottom: 0.5px solid rgba(246,247,248,0.22)`

**Text style:** `navigation` — Neue Montreal-664db4e45422dff6 500 · 14px/1.43 · tracking -0.02em

**Observed:** Small white identity left, centered text links with 16px side padding, account link and Outline button right. Over media, the dark backing becomes translucent with about 4.7px backdrop blur.

**States:** Declared: hover link background changes to a dark gray mix and text to #f6f7f8; focus-visible outline 2px solid #e2efff with 3px offset.

### Detail link

**Use:** Secondary explanation link under feature copy.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; color: rgba(8,11,18,0.6); text-decoration: underline; text-decoration-color: #0a33ff; text-underline-offset: 4px`

**Text style:** `text-link` — Neue Montreal-664db4e45422dff6 400 · 15px/1.387 · tracking -0.02em

**Observed:** A small arrow follows the underlined words but is not itself underlined.

**States:** Declared: hover color #080b12; focus-visible border-radius 2px, outline 2px solid #0a33ff, outline-offset 3px.

### Workflow card

**Use:** Human-readable operations inside blue stages.

**CSS:** `display: flex; align-items: flex-start; gap: 16px; max-width: 320px; padding: 12px; background: #ffffff; border: 0.5px solid rgba(8,8,23,0.16); border-radius: 4px; box-shadow: 0px 3px 6px rgba(7,7,22,0.04), 0px 2px 4px rgba(7,7,15,0.03), 0px 1px 2px rgba(8,8,18,0.02)`

**Text style:** `workflow-title` — Neue Montreal-664db4e45422dff6 500 · 14px/1.25 · tracking -0.015em

**Observed:** Simple prompt cards contain only a two-line title. Workflow variants add a small square service icon, a muted detail line and thin white connector lines between cards.

**Transfer:** Use one concise input or output per card, not a miniature dashboard.

### FAQ row

**Use:** Objection handling on pale fields.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 24px 0px; color: #080b12; border-bottom: 0.5px solid rgba(8,8,23,0.16)`

**Text style:** `question` — Neue Montreal-664db4e45422dff6 400 · 18px/1.5 · tracking -0.015em

**Observed:** Native disclosure row; text left and 20px plus right. Closed rows are about 76px tall. Body text appears below the summary with 24px bottom padding; the plus rotates 45deg when open.

**States:** Declared: hover unspecified; focus-visible border-radius 2px, outline 2px solid #0a33ff, outline-offset 3px.

### Footer column

**Use:** Small, ruled navigation cells in the closing field.

**CSS:** `padding: 20px; border-right: 0.5px solid rgba(246,247,248,0.22)`

**Text style:** `footer-link` — Neue Montreal-664db4e45422dff6 500 · 12px/1.667 · tracking -0.01em

**Observed:** A footer-heading label precedes a short vertical list by 16px; links have 8px gaps and pale 60% text, brightening to full pale text on hover. The final row places copyright left and a two-line address right.

**States:** Declared: hover link color #f6f7f8; focus-visible border-radius 2px, outline 2px solid #e2efff, outline-offset 3px.

### Catalog card

**Only for:** searchable catalogs

**Use:** Scannable collection of capabilities or supported tools.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 20px; border: 0.5px solid rgba(8,8,23,0.16); border-radius: 4px`

**Text style:** `catalog-title` — Neue Montreal-664db4e45422dff6 500 · 16px/1.375

**Observed:** Tool variant starts with a 36px service logo, then a linked title and small-copy description separated by 6px. Scenario variant omits the logo, grows to about 249px tall and pins small data tags at the bottom; tool cards are about 163px tall.

**Transfer:** Use specific capability descriptions, not generic benefits.

### Catalog search

**Only for:** searchable catalogs

**Use:** Filter the card collection.

**CSS:** `width: 288px; height: 36px; padding: 0px 8px; background: #f6f7f8; border: 0.5px solid rgba(8,8,23,0.16); border-radius: 4px`

**Observed:** A narrow, lightly filled field sits above the first card column rather than stretching across the grid.

### Data tag

**Only for:** scenario catalogs

**Use:** Show the concrete inputs or dimensions behind a scenario.

**CSS:** `padding: 2px 6px; border: 0.5px solid rgba(8,8,23,0.16); border-radius: 2px; color: #080b12`

**Text style:** `tag` — Neue Montreal-664db4e45422dff6 400 · 12px/1.667 · tracking -0.01em

**Observed:** Compact tags wrap with 4px gaps beneath a small uppercase data label. They are not rounded pills.

### Plan card

**Only for:** pricing pages

**Use:** Compare plans without theatrical price numerals.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 0.5px solid rgba(8,8,23,0.16); border-radius: 4px; overflow: hidden`

**Text style:** `plan-title` — Neue Montreal-664db4e45422dff6 400 · 24px/1.167 · tracking -0.02em

**Observed:** Header has plan name, muted amount and dark Primary button, followed by ruled feature groups. Two plans share a row; a full-width enterprise option sits beneath them. A small blue outlined pill beside one title is the only promotional highlight.

**Transfer:** Keep plan names and prices the same scale; organize differences into clear lists.

## Imagery and graphics

### Interface macro film

**Use:** Default landing opening background.

**Observed:** An oversized, shallow-focus view of software controls fills the width: off-white tooling, black outline symbols and a blue control, with a granular screen-like texture. The scene is intentionally much larger than normal UI and runs behind the white serif promise rather than beside it.

**Transfer:** Use an enlarged detail of the new product's actual interaction. Without film, construct a high-quality still of a meaningful toolbar or control surface; retain the macro scale, subdued exposure and text legibility.

**Build:** Render a pale control strip in HTML or SVG at roughly twice normal interface scale, with large black outline controls and one blue active control. Frame it edge-to-edge with overflow hidden; soften the background detail slightly and add a subtle low-opacity dot texture. Add a black rgba(0,0,0,0.3) scrim and place crisp live text above it; keep texture off the live text.

### Blue workflow theatre

**Use:** Signature feature demonstrations throughout a landing page.

**Observed:** The illustration occupies one full feature half, usually 530×600px. A steel-blue-to-ice diagonal field holds small, crisp white cards centered with wide breathing room. Some are independent text prompts; others connect vertically and branch into two outputs via fine white right-angle lines. Small service logos supply local saturated color.

**Transfer:** Explain a real input-to-result relationship with a few HTML cards. If no interface assets exist, show three short operational statements in the same stage rather than inventing a full app.

**Build:** Use Soft blue stage. Center a 320px card stack with 20px gaps for independent prompts, or distribute nodes vertically for a flow. Place an SVG connector layer behind the cards with 1px white lines at about 92% opacity; use vertical spines and orthogonal branches, never curved neon paths. Use Workflow card and optional 40px square icon holders.

### Deep result stage

**Use:** Validation-oriented product proof and alternate demonstration chapters.

**Observed:** A dark navy upper panel transitions down through blue into periwinkle light. White, framed result details and source references float in front; faint nested rectangular lines suggest a bounded technical environment.

**Transfer:** Show a verifiable result and its supporting sources or inputs; retain the darker stage as contrast to the soft blue scenes.

**Build:** Use Deep blue stage at the same proportions as the soft stage. Add two or three inset rectangular SVG outlines using pale lines at low opacity. Place a white result card within 20px outer stage padding and leave the gradient visible around it.

### Compact proof marks

**Use:** Short credibility strip after the default opening and service marks in demonstrations.

**Observed:** Customer marks sit in a low 166px pale band under a centered small trust sentence; four roughly 160×40px logo slots share the row. Service marks elsewhere remain small and full-color within otherwise neutral constructions.

**Transfer:** Use authentic proof marks or an equivalent concise proof strip; if marks are unavailable, use restrained text credentials at the same small visual scale.

### Working product demonstration

**Only for:** detailed feature pages

**Use:** Large proof after the capability catalog.

**Observed:** A 1060×795px product video shows a pale spreadsheet-like workspace with narrow columns, realistic multi-line cell content, thin gray grid lines and small colored status labels. It is presented directly on the cool canvas, without a browser chrome mockup.

**Transfer:** Show the new product doing a complete task at readable scale; keep saturated status colors local to the product interface.

### Icons

**Observed:** Thin outline SVGs at 16px and 20px, 1.8px stroke with round caps, mostly ink or muted gray. Arrows sit after action text, plus signs at the right of disclosure rows and checks before compact claims. Service logos are colored square marks, not part of this outline family.

**Transfer:** Choose a single round-cap outline set with the same optical weight. Keep colored service identities separate from monochrome navigation and action symbols.

## Section recipes

How recurring sections are built.

### First screen: Immersive interface opening

**Observed:** Navigation sits on a dark 71px band over an edge-to-edge interface macro. Behind the live text, the media extends through a roughly 695px hero, with a dark scrim and text shadow establishing legibility. The headline and support form a 672px-wide lower-left group aligned to the editorial rail, not centered; the promise spans roughly two thirds of that group in two balanced lines at 55px. The lead occupies two short lines beneath it, then a single Primary button with an arrow. Within the first 900px, the entire headline, support, action and oversized control scene are visible, followed by most of the compact proof strip; capability chapters begin below the fold.

**Transfer:** Use a product interaction macro or constructed control still rather than a generic abstract render. For text-led feature pages, replace the macro with a roughly 430px dark field: a light-weight feature-display headline on the left and a narrower lead plus action on the right in a 3:2 split. Pricing instead opens on Cool canvas with centered feature-display text and a compact billing selector.

**Avoid:** Do not turn the default opening into a centered text block over an empty dark field, or place a small laptop mockup beside the promise.

**Text style:** `display` — Atacama-b538b26c81f7b413 400 · 55px/1.15 · tracking -0.05em

### Alternating capability chapter

**Observed:** Feature halves sit within White explanation band with outer rails and a hairline center split. The 530×600px Blue workflow theatre is paired with a vertically centered text stack inset 32px: eyebrow, 16px gap, heading, 24px gap, feature-body and Detail link. Illustration side alternates between chapters; 120px pauses keep the run editorial rather than tiled.

**Transfer:** Give each chapter one distinct benefit and one intelligible example; preserve the half-panel scale even when the workflow is simple.

**Text style:** `heading` — Atacama-b538b26c81f7b413 370 · 40.4px/1.15 · tracking -0.06em

### Standalone editorial statement

**Observed:** A broad Sunken statement band carries a left-aligned serif sentence across the editorial chassis with 120px vertical padding and no action. A white question variant uses the same construction immediately before the closing field.

**Transfer:** Use a short reframing sentence to interrupt detailed explanations or pose a final reader-centered question.

**Text style:** `heading` — Atacama-b538b26c81f7b413 370 · 40.4px/1.15 · tracking -0.06em

### Ruled tool matrix

**Observed:** A heading and lead sit above a shared-frame matrix rather than separate cards. Three category labels span the top; 265×69px service cells form four columns, divided by fine rules with some subtly tinted cells. Each has a small logo and restrained 14px label.

**Transfer:** Use this compact matrix to communicate breadth without making every item a feature card.

**Text style:** `heading` — Atacama-b538b26c81f7b413 370 · 40.4px/1.15 · tracking -0.06em

### Dark assurance interlude

**Observed:** Dark ruled field surrounds a 1060px-wide inner panel with 60px vertical and 72px horizontal padding. An eyebrow with a small seal leads into the heading; a large 72px internal pause and horizontal rule separate the title from a wrapping row of small checked assurances.

**Transfer:** Use a genuinely substantiated reliability or governance proof group. Keep its depth in the claims, not in badge count.

**Text style:** `heading` — Atacama-b538b26c81f7b413 370 · 40.4px/1.15 · tracking -0.06em

### Split FAQ

**Observed:** The Question split places a serif FAQ heading and a short help paragraph on the left, with ruled FAQ rows on the right. Pale gray fields and 120px padding make a dense answer collection feel unhurried. The general and pricing variants use Sunken statement band; the tool-specific variant uses Cool canvas.

**Transfer:** Choose real adoption objections; use collapsed disclosures so the default composition stays light.

**Text style:** `question` — Neue Montreal-664db4e45422dff6 400 · 18px/1.5 · tracking -0.015em

### Ruled closing invitation

**Observed:** A shared 662px dark ending begins with generous empty space and a small identity. About 80px below the identity, a single-line serif imperative sits left with Primary button to its right. The lower part becomes five Footer columns between fine rules, then a smaller copyright-and-address row. Vertical chassis rails continue through the entire ending.

**Transfer:** Use the closing imperative to restate the reader's agency, with one direct conversion action. The identity and column content change, but the dark invitation-plus-directory construction remains.

**Text style:** `heading` — Atacama-b538b26c81f7b413 370 · 40.4px/1.15 · tracking -0.06em

### Three-step explanation

**Only for:** process-led feature pages

**Observed:** Eyebrow and heading introduce three equal ruled columns. A horizontal strip aligns 28px square number markers over their centers; the first is dark with pale text and the others pale with fine inset outlines. Step-title and body copy sit in 32px insets below, with no large pictograms.

**Transfer:** Explain setup, use and result, or another three-part mental model with short, distinct text.

**Text style:** `step-title` — Neue Montreal-664db4e45422dff6 500 · 18px/1.3 · tracking -0.015em

### Task and output panel

**Only for:** role-based feature explanations

**Observed:** Four equal 45px tabs form a white strip with vertical dividers. Beneath it a roughly 1060×434px framed split pairs Blue workflow theatre on the left with a sunken text panel on the right. A 24px sans heading precedes two labeled prose groups for task and output, separated by a rule.

**Transfer:** Let each tab replace both the practical scenario and its illustrated result; describe user work rather than abstract personas.

### Searchable capability catalog

**Only for:** catalog pages

**Observed:** A left-aligned heading and lead precede Catalog search, then Catalog cards in a three-column 12px-gap grid. Service collections use icons and shorter descriptions; scenario collections use taller cards and Data tags. The last row can be incomplete without being padded with filler cards.

**Transfer:** Separate inventory from narrative chapters. Keep entries concrete and allow the catalog's natural length.

**Text style:** `heading` — Atacama-b538b26c81f7b413 370 · 40.4px/1.15 · tracking -0.06em

### Pricing comparison

**Only for:** pricing pages

**Observed:** Centered title above a two-option billing selector; the selected option is a dark 248×38px rectangle with 2px corners. Two white Plan cards share the first row and a broad custom-plan card follows. Blue appears only in the small outlined value badge. Feature lists use checks and fine ruled groups.

**Transfer:** Make costs and inclusions scannable without oversized prices or an entirely colored featured plan.

**Text style:** `plan-title` — Neue Montreal-664db4e45422dff6 400 · 24px/1.167 · tracking -0.02em

## Page flow

**Storyline:** Promise → credible breadth → concrete ways of working → proof and reassurance → practical objections → closing invitation; adapt the emphasis to the decision being made.

### Broad product landing narrative

1. **Promise** — Immersive interface opening with one action.
2. **Social proof** — Compact proof marks beneath the media.
3. **Capability chapters** — Alternating benefit-led text and staged demonstrations.
4. **Reframing** — Standalone editorial statement.
5. **Breadth** — Ruled tool matrix.
6. **Reassurance** — Dark assurance interlude followed by a result-and-sources demonstration.
7. **Objection handling** — Split FAQ.
8. **Closing call** — Ruled closing invitation and directory.

**Transfer:** Use staged examples to make an unfamiliar product understandable before asking the reader to evaluate implementation detail.

### Commercial comparison and purchase clarification

1. **Pricing** — Centered title, billing selector, two plan cards and a full-width custom plan.
2. **Objection handling** — Long split FAQ focused on units, costs and usage.
3. **Closing call** — Shared dark invitation and directory.

**Transfer:** Keep commercial density inside the plan and answer system, not in the opening headline.

### Explain connected capabilities and supported ecosystem

1. **Promise** — Text-led dark split introduction.
2. **Process explanation** — Three-step explanation.
3. **Use cases** — Editorial introduction followed by a role-tabbed task and output panel.
4. **Capability inventory** — Searchable tool cards and a small request link.
5. **Objection handling** — Split FAQ about access and supported work.
6. **Closing call** — Shared dark invitation and directory.

**Transfer:** Follow a simple mental model with a tangible task, then let readers inspect coverage.

### Explain a specialized capability through examples and live-looking proof

1. **Promise** — Text-led dark split introduction.
2. **Process explanation** — Three-step explanation.
3. **Use cases** — Searchable scenario cards with data tags.
4. **Product demonstration** — Large working table video on a pale field.
5. **Closing prompt** — Single serif reader question in a white band rather than FAQ.
6. **Closing call** — Shared dark invitation and directory.

**Transfer:** Use many short scenarios to define the capability, then show their shared mechanism in one large demonstration.

## Writing

Assured, practical and mildly contrarian. The tone respects the reader's existing expertise and explains how work changes rather than celebrating technology for its own sake.

**Do not copy:** Do not reuse Paradigm's identity, product-specific terminology as names, customer marks, prices, adoption numbers, certifications, addresses or factual claims. Examples illustrate the tone; write original copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Product explanations name the product as the actor; the company rarely foregrounds itself as we.
- **Rhythm:** Headlines are usually one clear sentence or two clipped parallel clauses. Support text is one or two short sentences; actions are brief verbs, with no exclamation marks or inflated slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | An imperative that puts the reader's own method in charge, or a specific capability plus a meaningful contrast. | 6–11 words | “Apply your playbook across the entire market”<br>“Account research beyond what's public”<br>“Track custom signals before the market catches up” |
| Supporting line | Name the practical mechanism, then the useful consequence. | 20–40 words | “Your reps don’t need more alerts. They need to know which accounts changed priorities, why, and what to do about it.” |
| Section heading | Describe a job or challenge in ordinary language; a concrete contrast often sharpens it. | 5–11 words | “Find opportunities no database filter can describe”<br>“Start with the work on your plate.” |
| Primary action | A direct verb plus a clear next step. | 2–4 words | “Request a demo”<br>“Get started” |
| Closing imperative | Return to the reader's way of working with a short active invitation. | 5–7 words | “Put your playbook to work” |

**Words and phrasing to use:** your team; the tools you already use; context; criteria; evidence; research; ready to review; what you get; without losing context

**Avoid:** revolutionary; game-changing; unlock limitless potential; magic; supercharge everything; AI-powered future

**Rules:**

- Lead with a recognizable work situation, then name the mechanism.
- Make contrasts specific: not more alerts, but changed priorities and the next move.
- Use plain verbs such as connect, find, review, update and send.
- Keep catalog descriptions literal about what an entry reads, searches or changes.
- Separate a claim from its supporting detail so headings remain concise.

## Do's and Don'ts

### Do

- Keep the display serif fine at about 55px, with 1.15 line height and tight negative tracking.
- Use 120px vertical section padding to separate compact content systems.
- Align major content to the 1060px working span at the desktop reference width.
- Preserve 32px text insets in split features and FAQs.
- Use 4px card corners and 0.5px neutral edges for a lightly engineered feel.
- Keep the stage shadow layered and faint; use flat cards for functional catalogs.
- Keep the closing heading at the section scale rather than enlarging it into an unrelated display treatment.
- Use 12px uppercase eyebrows with 0.14em tracking to label substantial chapters.

### Don't

- Do not replace the editorial serif with a bold geometric sans headline.
- Do not round 44px conversion actions into pills; the pill treatment belongs only to the small pricing badge.
- Do not spread electric blue across large marketing backgrounds; the broad color belongs to cool demonstration gradients.
- Do not add deep shadows to every white catalog card; their border is sufficient.
- Do not make pricing numbers larger than the 24px plan labels.
- Do not turn the three-step markers into oversized circular icons; they are 28px squares.
- Do not expand the 288px search field across all three catalog columns.
- Do not use lifestyle photography as the dominant product explanation; the visual language is software at work.

## Motion and responsive

### Motion

**Observed:**

- Actions declare opacity or color transitions at 0.15s with cubic-bezier(.33, 0, .15, 1); some opacity changes use 0.2s.
- Header declares background-color, transform and backdrop-filter transitions at 0.3s with cubic-bezier(.33, 0, .15, 1).
- Process number colors and shadows declare 0.3s transitions with the same curve.
- FAQ plus icons rotate 45deg for the open state with a 0.3s transform transition.
- A carousel-slide animation is declared linear and infinite; its duration is variable.

**Transfer:**

- Use the declared short opacity response for rectangular actions rather than scale or bounce effects.
- Keep working demonstrations and subtle process progress separate from navigation feedback.

**Unknown:**

- Video playback cadence, scroll reveal choreography and carousel duration are not established.

### Responsive

**Observed:**

- Fluid section headings, leads, bodies and step titles use the clamp formulas in their type recipes.
- Structural classes specify one-column catalogs by default, two columns at a portrait-tablet tier and three at a wider tier; footer navigation changes from two to five columns.
- The desktop header hides its central links and account-action group outside the portrait-tablet tier.

**Transfer:**

- On narrow screens, stack each feature's copy and stage while retaining the stage's clear card hierarchy; scale the illustration frame, not the text into illegibility.
- Use the one/two/three-column catalog progression and a two-column footer until the full five-column directory fits.
- Keep the macro media edge-to-edge and the live headline on a readable inset rather than shrinking the whole desktop hero.

**Unknown:**

- Exact breakpoint widths, mobile navigation interaction and mobile hero crop are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
