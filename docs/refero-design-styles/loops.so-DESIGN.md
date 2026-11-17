# Loops — paper tools, sunset rails

## Overview

An approachable editorial style for technical products, pairing bookish serif headings with matter-of-fact grotesk text and finely drawn interface demonstrations. Warm off-white dominates, with charcoal controls and a sunset-colored rail that resolves into a deep brick-red ending. The pages feel spacious between chapters but practical and compact inside each product example; logos, diagrams, and working interfaces do the persuasion rather than decorative photography.

### Essentials

- Bookish headlines stay human-sized: Newsreader 500 at 44px/1.08 with -0.02em tracking opens the page, while ordinary chapter headings are 25.3px/1.15 rather than oversized display slogans.
- The opening is a left-aligned promise above a broad tool: a 1248px stage, 800px support measure, 44px pill actions, a slim logo row, then a browser-framed demonstration beginning within the first 900px.
- Sunset rails give the paper a physical boundary: four hard-edged bands of golden yellow, orange, vermilion, and brick red occupy about 79px at the outer edge, bend around the content, and resolve into a brick-red closing field. Include this graphic on new general marketing pages even when product artwork is unavailable.
- Color lives at the edges and in tiny signals: most of the page is #fdfdfc to #f9f9f8, text is #21201c and #63635e, and #fc5200 is reserved for small marks, annotations, or graph lines until the colored ending.
- Product proof looks like a usable instrument: 14px rounded demonstration panels, 1px warm-gray borders, pale dotted workspaces, fine connector lines, and restrained low-alpha shadows. If no interface exists, construct a short real process diagram in the same frame.
- Actions are tactile dark lozenges, not bright rectangles: the opening primary uses #21201c, 40px radius, 10px 20px padding, and a 44px height; its pale outlined companion stays visually subordinate.
- A little booking card behaves like a paper calling card: 160px by 156px with a 9px radius, a calendar icon, a two-line 22px Georgia title, and a ruled action strip; its compact serif/sans contrast echoes the whole page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brick red | `#7d1b0c` | `--color-brick` | background, accent, text | Deepest rail and general marketing closing field; also text on the closing cream button. |
| Tangerine rail | `#ff8a1f` | `--color-tangerine` | accent | Middle band in the sunset edge artwork. |
| Golden rail | `#ffb21c` | `--color-gold` | accent | Outermost bright band in the sunset edge artwork. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#fc5200` | `--color-orange` | accent | Sunset rail, small signal dots, thin graph lines, and handwritten explanatory marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Raised paper | `#fdfdfc` | `--color-paper` | background, surface, text | Upper page canvas, raised demonstrations, and text on dark buttons. |
| Warm canvas | `#f9f9f8` | `--color-canvas` | background, surface | Lower canvas, dotted workspaces, resource pills, and booking card. |
| Closing cream | `#fff4ec` | `--color-cream` | text, action | Heading and primary action on the brick ending. Secondary text uses rgba(255,236,226,0.74) or rgba(255,236,226,0.78) over brick for muted peach lettering. |
| Putty chrome | `#f1f0ef` | `--color-chrome` | surface, background | Browser framing, answer bubbles, and the top of pricing bands. |
| Soft hairline | `#e9e8e6` | `--color-hairline` | border, surface | Demo boundaries, resource pills, dot fields, and fine separators. |
| Defined edge | `#dad9d6` | `--color-edge` | border | Outlined buttons and more structural panel boundaries. |
| Calling-card edge | `#cfceca` | `--color-card-edge` | border | Booking card outline and its action separator. |
| Pencil gray | `#63635e` | `--color-muted` | text, border | Paragraphs, captions, small icons, and stronger interactive edges. |
| Warm charcoal | `#21201c` | `--color-ink` | text, action | Main headings, primary controls, diagram emphasis, and icons. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer directories | Directory white | `#ffffff` | `--color-white` | surface | White logo tiles, distinct from the warm main paper. |
| customer directories | Directory outline | `#e2e1de` | `--color-logo-edge` | border | Faint outline around white logo tiles. |
| developer installation sections | Terminal black | `#111110` | `--color-terminal` | surface | One-command installation bars; not a site-wide dark theme. |
| developer capability catalogs | Released mint | `#d7edd3` | `--color-released` | surface | Small released-status labels, not a broad accent wash. |

## Typography

- **Newsreader** — Marketing headlines, chapter headings, and plan numbers. Literary, compact serif with soft, lively curves; mostly medium rather than heavy. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Newsreader", Georgia, serif.
- **Inter** — Body copy, navigation, buttons, and marketing labels. Clear grotesk with compact negative tracking in short labels. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Inter", system-ui, sans-serif.
- **ui-sans-serif** — Utility labels and compact integration links. Unobtrusive platform sans, slightly more utilitarian than the editorial pair. Font stack: "ui-sans-serif", system-ui, -apple-system, sans-serif.
- **Iowan Old Style** — Editorial testimonial quotations. Warm old-style serif in italic, a more conversational voice than the headlines. If unavailable, use **Libre Baskerville**. Use regular italic and retain the restrained quotation measure. Font stack: "Iowan Old Style", "Libre Baskerville", Baskerville, "Times New Roman", serif.
- **Georgia** — The small two-line booking-card title. Familiar sturdy serif, tightly tracked. Font stack: "Georgia", "Times New Roman", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Newsreader | 500 | 44px | 1.08 | -0.02em | Default opening headline, usually one line at desktop. |
| closing-display | Newsreader | 500 | 44px | 48px | -0.0364em | Cream-colored line in the brick closing field. |
| heading | Newsreader | 500 | 25.3px | 1.15 | normal | Main capability chapter headings. |
| booking-title | Georgia | 400 | 22px | 1.1 | -0.035em | Two short lines in the booking card. |
| quote | Iowan Old Style | 400 italic | 21px | 1.45 | -0.01em | Two-column testimonial quotations. |
| hero-support | Inter | 400 | 20px | 1.4 | -0.01em | Opening explanation, usually two lines. |
| body | Inter | 400 | 16.8px | 1.7 | normal | Default chapter support copy. |
| primary-label | Inter | 500 | 16px | 1.25 | -0.01em | Main opening action. |
| navigation | Inter | 500 | 16px | 1.5 | 0.01em | Main navigation links. |
| action | Inter | 500 | 15px | 20px | -0.01em | Closing actions; 52px action variants on product landing pages. |
| compact-action | Inter | 500 | 14px | 20px | -0.01em | Secondary opening action and header actions. |
| utility | ui-sans-serif | 400 | 14px | 1.2 | normal | Resource pills below a demonstration. |
| integration-label | ui-sans-serif | 500 | 14px | 1.3 | normal | Compact integration grid labels. |
| footer-link | Inter | 400 | 14px | 1.5 | -0.02em | Footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| directories and developer guides | compact-display | Newsreader | 500 | 40px | 1.1 | -0.02em | Compact title in directory and developer-guide openings. |
| product-guide pricing bands | plan-number | Newsreader | 500 | 32px | 1.1 | -0.02em | Plan facts in a two-by-two ruled grid. |
| product and developer guides | compact-closing | Newsreader | 600 | 28px | 1.25 | -0.02em | Closing panel headline. |
| product guides | chapter-label | Newsreader | 500 | 20px | 1.25 | -0.02em | Numbered headings in the narrow explanation rail. |
| product-guide FAQs | question | Inter | 600 | 17px | 1.3 | normal | Closed FAQ row questions. |

**Notes:**

- The visual contrast comes from serif versus grotesk, not from enormous differences in size or heavy weights. Keep ordinary chapter headings modest beside full-width demonstrations.
- Negative tracking is generally -0.01em in actions and -0.02em in large serif text. The brick closing line is tighter at -1.6px; do not apply that value to every heading.
- The main text carries the listed font-feature-settings; compact standalone button labels do not require them.

## Layout

**Density:** Airy between chapters, compact within tools: long stretches of warm paper isolate tightly assembled controls and diagrams.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Chapter heading to support text; utility gaps and FAQ row spacing. |
| 10px | Opening action gap and compact control clusters. |
| 12px | Integration grid gutters and icon-to-label spacing. |
| 14px | Closing heading-to-support gap and small card rhythm. |
| 16px | Space between a demonstration and its resource row. |
| 24px | Outer side padding within the wide shell and chapter text-to-demo separation. |
| 32px | Closing panel padding and larger internal separation. |
| 48px | Testimonial column gap and directory block separation. |
| 64px | Product-guide section padding and explanatory-rail gutter. |
| 200px | Default separation between the main marketing capability chapters. |

### Containers and grids

- **Wide shell**: max width 1296px · side padding 24px. Centered outer shell producing 1248px of usable content; at 1440px the usable content starts 96px from the edge.
- **Capability column**: max width 920px. Centered, narrower marketing chapters; headings, demos, and resource rows align to one left edge.
- **Integration grid**: 3 columns · gap 12px. Compact icon-and-label tiles, three columns within the capability or demonstration column.
- **Testimonial pair**: 2 columns · gap 48px. Two open quotations, each introduced by a rule and a customer logo.
- **Guide split** (only for product and developer guides): max width 1248px · 2 columns · gap 64px. A 320px explanatory rail beside an 864px demonstration column. The developer guide sustains this asymmetry down the page.
- **Directory grid** (only for customer directories): max width 1248px · 4 columns · gap 12px. Equal 303px by 132px logo tiles.
- **Story grid** (only for customer directories): 2 columns · gap 24px. Two columns of 612px wide story links with explanatory copy beneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Opening primary | 40px |
|  | Pill actions | 9999px (pill) |
|  | Demonstration panels | 14px |
|  | Integration tiles | 10px |
|  | Booking card | 9px |
|  | Browser frame | 20px |
| customer directories | Directory tiles | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Demonstration lift | `0px 1px 2px 0px rgba(0,0,0,0.024), 0px 18px 44px 0px rgba(0,0,0,0.055), inset 0px 1px 0px 0px rgba(253,253,252,0.9)` | Large light product demonstrations. |
| Booking lift | `0px 2px 3px 0px rgba(28,25,23,0.04), 0px 8px 18px -8px rgba(28,25,23,0.16)` | Paper calling card floating near the lower right. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default continuous page field.

**CSS:** `background: linear-gradient(#fdfdfc 0%, #f9f9f8 100%)`

**Observed:** The shift is extremely subtle and spans the page rather than restarting in every section.

**Transfer:** Keep the background warm and almost flat; let borders and shadows distinguish raised tools.

#### Demonstration paper · level 1

**Use:** Workflow, code, theme, and reporting demonstrations.

**CSS:** `background: #fdfdfc; border: 1px solid #e9e8e6; border-radius: 14px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.024), 0px 18px 44px 0px rgba(0,0,0,0.055), inset 0px 1px 0px 0px rgba(253,253,252,0.9); overflow: hidden`

**Observed:** A shallow toolbar sits above the workspace. Resource links live outside the panel, not in its shadow.

**Transfer:** Give each proof panel one task rather than turning it into a dense feature collage.

#### Dotted workspace · level 1

**Use:** Process diagrams within Demonstration paper.

**CSS:** `background-color: #f9f9f8; background-image: radial-gradient(circle, rgba(99,99,94,0.24) 1px, rgba(0,0,0,0) 1px); background-size: 16px 16px`

**Observed:** Tiny faint dots recede behind light nodes and narrow gray connectors.

**Transfer:** Use the dot field as a drafting surface, not a high-contrast pattern; the 16px repeat is a practical construction choice.

#### Browser chrome · level 1

**Use:** The main opening product stage.

**CSS:** `background: #f1f0ef; border-radius: 20px; padding: 8px; box-shadow: inset 0px 0px 0px 1px #dad9d6, 0px 1px 2px -1px rgba(33,32,28,0.05), 0px 24px 48px -24px rgba(33,32,28,0.22); overflow: clip`

**Observed:** The frame has a slim 34px browser bar and an inset light application pane with its own 14px corners.

**Transfer:** Show an actual task in progress in a large browser-like window; retain the light material even for technical products.

#### Brick closing field · level 0

**Use:** Default general marketing ending, behind the closing line and footer.

**CSS:** `background: #7d1b0c; color: #fff4ec`

**Observed:** The upper paper ends with a rounded lower-left turn above the brick field. Sunset rails continue down the left and curve beneath the footer.

**Transfer:** Use the closing color as the payoff to the edge artwork, not as an unrelated full-width banner.

#### Plan band · level 1

**Only for:** product-guide pricing sections

**Use:** One short value explanation beside four plan facts.

**CSS:** `background: linear-gradient(#f1f0ef 0%, #f9f9f8 100%); border-top: 1px solid #dad9d6; border-radius: 16px; padding: 56px 40px`

**Observed:** The pale band is 1248px wide with a two-by-two fact grid; numbers sit above muted captions separated by fine horizontal rules.

**Transfer:** Use verified allowances, coverage, or limits, with equal visual weight rather than a giant single metric.

## Components

### Navigation

**Use:** Persistent brand and route navigation.

**CSS:** `display: flex; align-items: center; gap: 24px; height: 68px; color: #21201c`

**Text style:** `navigation` — Inter 500 · 16px/1.5 · tracking 0.01em

**Observed:** Small serif wordmark and colored symbol sit left; product and guide menus, plain links, and compact login/conversion pills sit right. The inner link group uses 16px gaps. Product-guide headers are fixed.

**Transfer:** Keep the wordmark small and the navigation in a single clear line; use a new identity rather than a large display logo.

### Primary button

**Use:** Default opening conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #21201c; color: #fdfdfc; border-radius: 40px; padding: 10px 20px; height: 44px; box-shadow: inset 0px 1px 2px 0px rgba(255,255,255,0.05), 0px 2px 5px 0px rgba(28,25,23,0.14), 0px 8px 18px -12px rgba(28,25,23,0.3)`

**Text style:** `primary-label` — Inter 500 · 16px/1.25 · tracking -0.01em

**Observed:** A short label in a subtly lifted charcoal lozenge. Product-guide actions use 15px action text, 14px 18px padding, and 52px height. Header versions are 40px tall with compact-action text. On the brick ending, the fill reverses to cream with brick text.

**Transfer:** Use one direct conversion verb; retain the dark default rather than promoting orange into the CTA.

### Secondary button

**Use:** Alternative action beside the primary.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #fdfdfc; color: #21201c; border: 1px solid #dad9d6; border-radius: 9999px; padding: 8px 14px; height: 44px`

**Text style:** `compact-action` — Inter 500 · 14px/20px · tracking -0.01em

**Observed:** A clean outlined pill without the primary's dark lift. The closing dark-field variant is transparent with a cream alpha outline; product-guide versions share the taller action size.

**States:** Declared: focus-visible outline 2px solid #21201c, outline-offset 3px.

**Transfer:** Keep it next to, not below or larger than, the primary at desktop.

### Resource pill

**Use:** A small learn-more row below a product demonstration.

**CSS:** `background: #f9f9f8; color: #63635e; border: 1px solid #e9e8e6; border-radius: 9999px; padding: 7px 13px; max-width: 190px`

**Text style:** `utility` — ui-sans-serif 400 · 14px/1.2

**Observed:** An unboxed introductory label precedes several outlined pills and a plain More link; the row wraps with 8px gaps.

**Transfer:** Choose a few task-specific documentation destinations rather than adding another conversion bar.

### Integration tile

**Use:** Compact ecosystem links.

**CSS:** `display: flex; align-items: center; gap: 12px; background: #fdfdfc; border: 1px solid #e9e8e6; border-radius: 10px; padding: 12px; height: 44px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.04)`

**Text style:** `integration-label` — ui-sans-serif 500 · 14px/1.3

**Observed:** An 18px icon precedes one muted label; tiles form a three-column grid, with a View all link using the same construction.

**States:** Declared: hover border-color #dad9d6 and box-shadow 0px 1px 2px rgba(0,0,0,0.05), 0px 6px 16px rgba(0,0,0,0.05).

**Transfer:** Use relevant tools with similarly sized marks; keep each cell light rather than using a separate brand-colored tile.

### Booking card

**Use:** Persistent, compact human-contact route.

**CSS:** `display: flex; flex-direction: column; width: 160px; height: 156px; background: #f9f9f8; color: #21201c; border: 1px solid #cfceca; border-radius: 9px; box-shadow: 0px 2px 3px 0px rgba(28,25,23,0.04), 0px 8px 18px -8px rgba(28,25,23,0.16); overflow: hidden`

**Text style:** `booking-title` — Georgia 400 · 22px/1.1 · tracking -0.035em

**Observed:** Placed near the lower-right edge with 20px clearance. A 16px-padded body contains a calendar icon and two-line serif title; a 44px lower strip has 13px sans text and an up-right arrow. A small dismiss control sits at the top right. It changes to cream outlines and text over the brick ending.

**States:** Declared: hover on ancestor strengthens border to #63635e and the shadow; focus-visible outline 2px solid #21201c with 4px offset.

**Transfer:** Keep the two-line calling-card treatment for a consultation, guided trial, or equivalent human next step.

### Footer links

**Use:** Secondary navigation at the ending.

**CSS:** `display: flex; flex-direction: column; gap: 18px; color: rgba(255,236,226,0.74)`

**Text style:** `footer-link` — Inter 400 · 14px/1.5 · tracking -0.02em

**Observed:** Four widely separated columns sit between fine rules, with headings slightly brighter than links. A small legal row occupies the bottom left and a green operational dot sits at right. The guide and directory variant is light with charcoal links, muted 12px uppercase column labels, and the same legal/status arrangement.

**States:** Declared: hover color #fff4ec, underline with 2px offset; light variant hovers to #21201c.

**Transfer:** Retain the sparse four-column structure; use only relevant destinations.

### FAQ row

**Only for:** product-guide FAQs

**Use:** Compact objection handling in the wide demonstration column.

**CSS:** `background: #fdfdfc; border-top: 1px solid #dad9d6; border-radius: 12px; padding: 22px 24px; min-height: 66px`

**Text style:** `question` — Inter 600 · 17px/1.3

**Observed:** The question sits left and a small plus sits right; closed rows stack with 8px gaps. A modest serif section label sits outside the group in the narrow rail.

**Transfer:** Use actual evaluation questions. Preserve the closed-list density rather than exposing long answers by default.

### Closing panel

**Only for:** product and developer guides

**Use:** A contained conversion prompt before the light footer.

**CSS:** `display: flex; align-items: center; gap: 32px; background: #fdfdfc; border-top: 1px solid #dad9d6; border-radius: 8px; padding: 32px; box-shadow: 0px 1px 1px 0px rgba(0,0,0,0.05)`

**Text style:** `compact-closing` — Newsreader 600 · 28px/1.25 · tracking -0.02em

**Observed:** Headline and one practical support line sit left, two pills right. The developer variant occupies the 864px right column and omits the support sentence.

**Transfer:** Close with a concrete first task, using the same primary/secondary control hierarchy.

### Logo tile

**Only for:** customer directories

**Use:** A browsable wall of customer identities.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; border: 1px solid #e2e1de; border-radius: 12px; padding: 28px 22px; height: 132px; box-shadow: inset 0px 1px 3px 0px rgba(28,25,23,0.04), 0px 2px 5px -2px rgba(28,25,23,0.08), 0px 6px 16px -8px rgba(28,25,23,0.08)`

**Observed:** Each logo has substantial surrounding white space. Most marks are dark, but native logo color is retained in small areas.

**Transfer:** Normalize optical size, not logo width; include accessible destination labels.

## Imagery and graphics

### Sunset rail artwork

**Use:** Signature boundary for general marketing pages and their colored ending.

**Observed:** Four parallel, hard-edged sunset bands run down the opening's right edge, bend beneath the large demo, then continue down the long page at left. At the end they wrap around the brick footer in a broad rounded corner. They are solid print-like color, not gradients or glowing light.

**Transfer:** Carry the rail device into a different product's page with the same warm colors and restrained edge occupancy. It works without any bespoke imagery.

**Build:** Use an absolutely positioned SVG behind the content. Draw four nested paths with rounded 90-degree turns, separated by about 20px: gold #ffb21c outside, tangerine #ff8a1f, orange #fc5200, brick #7d1b0c inside. Keep the total band about 79px at desktop. The opening right turn uses nested lower-right radii of 172.8px, 153px, and 133.2px; use matching concentric geometry on the left and footer turns. Clip art to the page boundary and let the warm-paper content cover its center. Do not blur or interpolate between colors.

### Live product stage

**Use:** Largest proof object in the opening.

**Observed:** A broad pale browser window occupies nearly the full content width. Real side navigation, lists, workflow nodes, or an assistant show an ordinary task in progress; fine gray divisions and sparse colored signals make it legible without looking like a glossy render.

**Transfer:** Use an authentic core task from the new product. Without a finished interface, construct a credible browser pane with a short navigation list and one meaningful editable process; do not substitute stock photography.

### Drafting diagrams

**Use:** Recurring product proof panels and explanatory chapters.

**Observed:** Pale dotted workspaces hold small paper nodes, thin gray connectors, and occasional orange signals. One branching workflow fans from a central spine into three paths. Technical explanation variants add orange handwritten callouts and curved arrows around a vertical chain or a two-by-two trigger layout.

**Transfer:** Reduce the new product's mechanism to a few real steps; make the outcome obvious before adding labels. Keep handwritten orange annotations confined to explanation diagrams.

**Build:** Place the Dotted workspace inside Demonstration paper. Lay out white or warm-paper nodes with 10px corners and 1px #e9e8e6 edges; use 1px #dad9d6 SVG connector paths behind them. Emphasize one decision or successful endpoint with a #21201c outline. For explanation variants add short 18px Kalam-style handwritten orange labels and 34px by 22px curved SVG arrows with 1.6px rounded strokes; use two or three labels rather than covering the board.

### Fine-line health graph

**Use:** A compact reassurance demonstration within a capability chapter.

**Observed:** A thin orange line rises gently across a light panel with a very faint peach fill underneath. A large editorial serif status word sits above; two compact lists of handled events and safeguards sit beneath. No large axes, saturated chart bars, or heavy grid dominates.

**Transfer:** Use a truthful health, progress, or coverage signal appropriate to the new product. Preserve the expressive status word and subdued graph/list pairing rather than copying a numerical claim.

**Build:** Draw an SVG polyline with a narrow #fc5200 stroke and a small terminal dot. Close a second path below it with an orange fill fading from low alpha to zero. Add a 44px Didot-like regular status word and two neutral text lists below; keep color restricted to the line.

### Identity proof

**Use:** A slim opening logo row, testimonial marks, and larger directory cards.

**Observed:** Small logos are optically normalized in a horizontal row; testimonial marks are dark. Directory story cards enlarge a centered dark logo above a divided title strip with a circular right-arrow control; supporting prose sits outside the card beneath.

**Transfer:** Use permissioned identities and preserve their proportions. When identities are unavailable, use genuine concise proof statements rather than inventing endorsements.

### Icons

**Observed:** Mostly small outline symbols in pencil gray or charcoal: 14px to 18px, 1.5px to 2px strokes with rounded caps. Arrows are delicate; orange 13px arrows mark prompts and handwritten diagram arrows use a 1.6px stroke. Logo marks and the booking calendar can be filled.

**Transfer:** Choose one restrained line-icon family, optically sized to adjacent labels. Reserve orange icons for a small directional or status cue.

## Section recipes

How recurring sections are built.

### First screen: Paper promise and product stage

**Observed:** A slim 68px navigation line tops a warm Paper canvas. The promise begins around 141px down, aligned to the wide shell's left edge, with a single-line 44px Newsreader display headline and a two-line 20px support paragraph beneath it. The copy occupies roughly two thirds of the usable width, leaving the right side open against the Sunset rail artwork. Two 44px actions sit together below the paragraph with a 10px gap. A low, full-width row of small customer identities separates the copy from the browser stage. The 1248px-wide Browser chrome demonstration begins around 479px, so the first 900px shows its upper application area but not its lower edge. Back to front: sunset rail, paper page, editorial copy and logos, framed product stage, then Booking card at the lower right.

**Transfer:** Preserve the low headline, open right side, slim proof row, and large tool entering the first screen for a new product. A credible task diagram inside Browser chrome is the minimum substitute for unavailable interface media. Focused product-guide openings instead pair copy, actions, and two compact testimonials at left with a 460px by 520px assistant at right; directories use a centered 40px title before story cards, and developer guides use the narrow title rail beside a command bar and prompt field.

**Avoid:** Do not replace this with a centered giant slogan above a tiny floating dashboard, a full-screen dark hero, or a decorative illustration that delays seeing the product.

**Text style:** `display` — Newsreader 500 · 44px/1.08 · tracking -0.02em

### Capability chapter

**Observed:** A 920px Capability column pairs a 25.3px serif heading with 16.8px muted support text at an 8px gap. Demonstration paper follows after 24px; a Resource pill row sits outside the panel below. Large 200px chapter gaps make each ordinary task feel like its own exhibit.

**Transfer:** Use this as the default recurring chapter for a new landing page; vary the proof object rather than inventing a new panel style each time.

**Text style:** `heading` — Newsreader 500 · 25.3px/1.15

### Open testimonial pair

**Observed:** Two equal quotations sit in the Capability column, separated by 48px. Each starts with a fine top rule and a dark customer logo, followed by 21px italic serif text and small sans attribution. There is no enclosing card fill.

**Transfer:** Use short, concrete quotations and modest attribution; retain the rule/logo/quote/author order.

**Text style:** `quote` — Iowan Old Style 400 italic · 21px/1.45 · tracking -0.01em

### Sunset closing and footer

**Observed:** The paper's rounded lower corner reveals Brick closing field. A 44px cream serif call and one muted peach support line sit left, with a cream primary pill and outlined companion right. Below a fine rule, four sparse footer columns lead to a small legal/status line. Sunset rail artwork curves down the left and across the bottom to bind the ending to the opening.

**Transfer:** Use a concrete closing promise appropriate to the new product. The rail and its colored payoff remain the signature device, but their placement and frequency need not force a particular chapter sequence.

**Text style:** `closing-display` — Newsreader 500 · 44px/48px · tracking -0.0364em

### Numbered explanation rail

**Only for:** product guides

**Observed:** A 320px explanation at left contains a 20px serif numbered heading, a 12px gap, and 17px/1.6 support text. A 64px gutter separates it from an 864px right column holding grids, code, or diagrams. Sections generally have 64px vertical padding. The label rail can remain sticky while the right proof continues.

**Transfer:** Use when a product needs stepwise education rather than the default single-column exhibit.

**Text style:** `chapter-label` — Newsreader 500 · 20px/1.25 · tracking -0.02em

### Plan facts band

**Only for:** product-guide pricing sections

**Observed:** Plan band places a modest heading, explanatory paragraph, and primary action opposite a two-by-two matrix of facts. Each fact uses 32px Newsreader above a small sans caption, with fine rules rather than boxed stat cards.

**Transfer:** Show verified boundaries or inclusions in an evenly weighted matrix, without turning the band into a tier-comparison table.

**Text style:** `plan-number` — Newsreader 500 · 32px/1.1 · tracking -0.02em

### Directory proof and discovery

**Only for:** customer directories

**Observed:** A centered eyebrow, 40px title, and support sentence introduce two-column story cards. Story cards use centered identity artwork and a divided title/action strip with supporting copy outside. A pill-shaped category selector and adjacent search field precede the four-column Logo tile wall.

**Transfer:** Separate a few explanatory stories from the larger browsable collection, and make native identity colors the only strong color within the tiles.

### Prompt and answer chapter

**Only for:** developer guides

**Observed:** An 864px right column carries 10px-radius white panels. Each has a serif title strip separated by a rule, a right-aligned outlined prompt bubble with a copy control, then a broad putty answer bubble with asymmetric corners: 18px 18px 18px 4px. Related documentation pills sit inside the answer. Chapters are separated by 32px.

**Transfer:** Show a believable short request and a specific result, not a generic chat transcript. The developer catalog above them uses two columns of 401px by 139px cards, small mint status pills, and dashed outlines for forthcoming entries.

### Contained guide ending

**Only for:** product guides, developer guides, and directories

**Observed:** Closing panel appears after the FAQ or final example, followed by a light four-column Footer links variant. A directory ends directly after its final logo row and light footer, without an added conversion panel.

**Transfer:** Keep these purpose-specific endings distinct from the default brick marketing ending.

**Text style:** `compact-closing` — Newsreader 600 · 28px/1.25 · tracking -0.02em

## Page flow

**Storyline:** Promise → credible product or identity proof → task-oriented capability chapters → reassurance or value boundaries → a concrete next step and sparse footer.

### General marketing landing page

1. **Promise** — Left-aligned serif headline, explanatory support, paired actions.
2. **Social proof** — Slim row of small customer identities.
3. **Product demonstration** — Large browser-framed ordinary task.
4. **Capability chapters** — Narrower editorial heading pairs over workflow, design, reporting, code, ecosystem, and health demonstrations.
5. **Social proof** — Open pair of ruled italic testimonials.
6. **Closing call** — Brick field, cream actions, sunset rails, and four-column footer.

**Transfer:** Choose the chapters that prove the new product's promise; keep the editorial rhythm and rail-linked ending rather than copying the specific feature order.

### Focused integration or technical product landing page

1. **Promise** — Split hero with explanation and actions, short testimonials, and a task assistant.
2. **Setup** — Numbered narrow rail opposite command bar, language/tool choices, and a code demonstration.
3. **Capability education** — Definition cards, annotated process chain, and concrete use-case cards.
4. **Value boundaries** — Pale plan band with four equal serif facts.
5. **Objection handling** — Closed FAQ stack aligned to the right column.
6. **Closing call** — Contained light conversion panel then light footer.

**Transfer:** Make integration and evaluation easy to understand; preserve the numbered rail and the compact light ending.

### Workflow-oriented product landing page

1. **Promise** — Split promise and assistant hero with short proof quotations.
2. **Setup** — Ecosystem grid plus code proof beside a numbered explanation.
3. **Capability education** — Audience or input cards, annotated trigger diagram, and a branching process demonstration.
4. **Practical applications** — Two-by-two task cards.
5. **Value boundaries** — Pale fact band.
6. **Objection handling** — FAQ rows.
7. **Closing call** — Light action panel and four-column footer.

**Transfer:** Tell an input-to-outcome story using relevant steps and data; keep diagrams concrete and compact.

### Customer proof directory

1. **Promise** — Centered compact serif introduction.
2. **Social proof** — Two-column identity-led story cards with summaries.
3. **Discovery** — Category pills, search, and a four-column logo wall.
4. **Ending** — Collection ends directly into a light footer.

**Transfer:** Use a small editorial selection to give meaning to a larger searchable wall; do not append an unrelated CTA merely to match another page type.

### Developer or agent guide

1. **Promise** — Narrow editorial rail beside one-command installation and a prompt field.
2. **Capability catalog** — Two-column bordered cards with small released-status pills and dashed forthcoming cards.
3. **Product demonstration** — Repeated prompt-and-answer panels with copy controls and related docs.
4. **Closing call** — Compact conversion panel in the right column, then a full-width light footer.

**Transfer:** Sustain the left/right asymmetry and make each example end in a concrete, inspectable result.

## Writing

Practical, friendly, and quietly assured. The product is explained through ordinary tasks and small implementation details rather than abstract transformation claims.

**Do not copy:** Do not reuse Loops names, logos, artwork, customer identities, testimonials, pricing allowances, dates, retention claims, or performance figures. Substitute the new product's own identity and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; use we for a small team taking responsibility. Name the product naturally when describing what it does.
- **Rhythm:** Usually four to nine words in a heading, then one or two plain sentences of explanation. Lists and short task names supply rhythm; avoid exclamations and overly clever fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | State the complete job or unifying promise without an adjective pile. | 4–8 words | “One platform for every email”<br>“Product emails triggered by your app” |
| Chapter heading | Tie one capability to a concrete result or reduction of effort. | 5–9 words | “Lifecycle workflows that run themselves”<br>“An easy yes from engineering” |
| Supporting explanation | Start with the task, then explain how it works in real use. | 1–2 sentences | “Reach users after they close the tab. Set up onboarding, activation, upgrade, and winback emails once, then improve them over time.” |
| Primary action | A short verb-led next step with low-friction qualification only when true. | 2–4 words | “Start for free”<br>“Read the API docs” |
| Guide step | Number plus a concrete setup or process verb. | 4–8 words | “1. Connect your app” |
| Closing call | Invite a first usable result rather than an abstract commitment. | 5–9 words | “Build your first product email workflow” |

**Words and phrasing to use:** your app; set up; connect; send; build; test; from one place; works with; without the bloat

**Avoid:** revolutionize; 10x everything; game-changing; unleash; enterprise-grade synergy; effortless magic

**Rules:**

- Let the headline make one clear promise and let the support sentence name the mechanism.
- Use examples of actual actions, inputs, or results to make a technical concept understandable.
- Mention operational constraints plainly; a requirement or limit is not something to bury in tiny copy.
- Keep resource labels short and noun-led while conversion labels remain verb-led.

## Do's and Don'ts

### Do

- Keep the default serif display at 44px and weight 500; let product proof carry the scale.
- Use #fdfdfc and #f9f9f8 as the dominant page materials with #63635e paragraph text.
- Carry the four-color 79px sunset boundary through a general marketing composition and into its brick payoff.
- Align headings, demonstrations, and resource rows to the same 920px capability column.
- Use 14px demo corners and fine #e9e8e6 edges rather than thick borders.
- Make integration cells compact at 44px with 18px icons and 12px gutters.
- Give the 160px booking card its own serif title and ruled action strip.
- Separate major marketing chapters by 200px while keeping heading/support gaps at 8px.

### Don't

- Do not turn #fc5200 into the default button fill; charcoal actions and warm paper are the dominant interaction palette.
- Do not replace the hard sunset bands with a blurred mesh gradient or neon glow.
- Do not use weight 700 grotesk headings as the main voice; the editorial hierarchy depends on medium Newsreader.
- Do not add 30px corners to every panel; 9px, 10px, and 14px distinguish the small card, tiles, and demonstrations.
- Do not wrap testimonials in colored quote cards; use open rules and italic text.
- Do not enlarge plan numbers into billboard statistics; 32px serif facts stay in an equal two-by-two matrix.
- Do not color every ecosystem cell with its logo's background; native color belongs in the small mark.
- Do not force the brick ending onto directories or technical guides, whose scoped ending is light and compact.

## Motion and responsive

### Motion

**Observed:**

- Integration tiles declare box-shadow and border-color transitions at 150ms.
- Prompt actions declare background-color, border-color, transform, and box-shadow transitions at 160ms; hover lifts by 1px and active returns to translateY(0px) scale(0.98).
- Booking card declares border-color and box-shadow at 180ms and transform at 180ms cubic-bezier(0.23,1,0.32,1).
- Workflow nodes declare a 1px upward hover movement and a 2px charcoal focus outline with a 2px offset.

**Transfer:**

- Keep motion concentrated in working demonstrations and small tactile controls. Preserve the subtle lift rather than making panels float continuously.

**Unknown:**

- No general scroll choreography or exact playback sequence is established; do not infer a rail-drawing animation from its shape.

### Responsive

**Observed:**

- Declared width boundaries include 500px, 810px, and 1200px; only the desktop composition is specified here.
- Testimonial grid uses repeat(auto-fit, minmax(min(320px, 100%), 1fr)); developer catalog uses auto-fill with a 280px minimum.

**Transfer:**

- On narrow screens, stack guide explanation above the demonstration, retaining the serif/sans contrast. Reduce sunset artwork to an edge strip rather than letting its full desktop width displace content.
- Let resource pills wrap and keep diagram connectors coherent; simplify the diagram to one legible path before shrinking every label.
- Move the booking route into a compact dismissible treatment if the full card would cover the product proof.

**Unknown:**

- Exact mobile type sizes, navigation collapse behavior, and small-screen rail geometry are unspecified; these are adaptation recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
