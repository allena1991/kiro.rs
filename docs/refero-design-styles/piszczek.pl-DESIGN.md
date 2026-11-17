# Piszczek — terminal-lit conviction

## Overview

A near-black, technically literate style that feels like an engineer's public workstation rather than a conventional sales brochure. Electric mint, cold gray text, geometric grotesk headlines and small monospaced annotations create a deliberate contrast between bold opinions and operational detail. Terminal windows, equations and faint network graphics replace photography; spacious chapters contain dense pockets of proof. It suits technical products, infrastructure platforms and expert-led businesses with something concrete to demonstrate.

### Essentials

- The name or promise reads like a two-tone command banner: Space Grotesk 86.4px/1.04, weight 700, -0.03em tracking, with white followed by a silver-gray text gradient.
- The opening is an identity masthead above a working console: a 65px sticky navigation, left-aligned status pill and headline, then a two-column promise and 420×440px terminal with a 48px gap. Both actions and the console fit in the first 900px.
- Color behaves like an active signal, not a painted theme: #030303 dominates; #00ff94 marks prompts, selective phrases, live dots and thin edges. Broad washes use only 7–9% mint and stay almost black.
- Conversion controls look like compact hardware keys: primary white and secondary translucent charcoal rectangles, 6px corners, 16px 32px padding and 15px/1.6 bold uppercase text; pills are reserved for metadata.
- Every major claim has an instrument-like counterpart: a terminal, equation or code panel on #0d0d0d with 14px corners, 1px translucent white edges and a 43px dark title bar. When no product interface exists, use a readable command/output demonstration rather than decorative stock art.
- Proof is catalogued, not merely celebrated: 11px/1.6 JetBrains Mono labels with 0.15em tracking, numbered capability tiles, and a mint 44.8px/1 metric isolated by a vertical rule inside a dark highlighted card.
- The atmosphere and ending retain the workstation fiction: faint grain and connected nodes behind content, short mint-to-transparent heading rules, and a centered 57.6px closing invitation above a constrained contact panel and monospaced directory footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Live mint | `#00ff94` | `--color-mint` | accent, text, link, action | Only dominant chromatic accent: prompts, active labels, important short phrases, focus rings and hover fill. |
| Status mint wash | `#031c12` | `--color-mint-wash` | surface | Visible result of rgba(0,255,148,0.1) over the canvas, used in the live update pill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal white | `#ffffff` | `--color-white` | text, action | Headlines, key statements and primary button fill. |
| Button ink | `#000000` | `--color-black` | text | Text and arrow on white primary buttons. |
| Near-black canvas | `#030303` | `--color-canvas` | background | Dominant page canvas and dark text selection foreground. |
| Closing black | `#050505` | `--color-closing` | background | Closing invitation and footer background. |
| Translucent card black | `#080808` | `--color-translucent-card` | surface | Visible result of rgba(10,10,10,0.72) over the canvas on case cards and the stat band. |
| Card charcoal | `#0a0a0a` | `--color-card` | surface | Process and contact panels; also the source hue of translucent case cards. |
| Console charcoal | `#0d0d0d` | `--color-panel` | surface | Opaque terminal, equation and code windows. |
| Quiet hairline | `#121212` | `--color-edge` | border | Visible canvas-relative result of rgba(255,255,255,0.06); chapter dividers and subdued card outlines. |
| Window title bar | `#1a1a1a` | `--color-titlebar` | surface | Title bars distinguish code windows from their bodies. |
| Window edge | `#1c1c1c` | `--color-edge-strong` | border | Visible canvas-relative result of rgba(255,255,255,0.1); console and linked-tile outlines. |
| Faint slate | `#7d8795` | `--color-faint` | text | Secondary numbering and annotations; darkest stop in metallic headline text. |
| Blue-gray ink | `#8f9ba8` | `--color-muted` | text | Main explanatory copy, navigation and terminal output; middle stop in metallic headline text. |
| Code silver | `#d1d5db` | `--color-code` | text | Longer code and principle text, subordinate to white headlines. |
| Cool pale ink | `#e2e8f0` | `--color-body-strong` | text | Emphasized body phrases and utility text. |

## Typography

- **Space Grotesk** — Display, headlines, prose and prominent action labels. Geometric grotesk with blunt terminals and distinctive technical shapes; bold headings sit above light prose. Font stack: "Space Grotesk", system-ui, -apple-system, sans-serif.
- **JetBrains Mono** — Navigation, numbered labels, command windows, technical captions and footer directory. Open, coding-oriented monospace; small text is usually light and loosely tracked when uppercase. Font stack: "JetBrains Mono", ui-monospace, "SF Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Space Grotesk | 700 | 86.4px | 1.04 | -0.03em | size clamp(2.6rem, 1rem + 6.5vw, 5.4rem) | Opening identity or short promise, white with a metallic-gray continuation. |
| closing-heading | Space Grotesk | 700 | 57.6px | 1.15 | -0.02em | size clamp(2rem, 1.2rem + 3.5vw, 3.6rem) | Centered final invitation. |
| spotlight-heading | Space Grotesk | 700 | 55.2px | 1.08 | -0.035em | size clamp(2rem, 1.2rem + 3vw, 3.45rem) | Split white-and-mint heading inside the protocol spotlight. |
| catalog-heading | Space Grotesk | 700 | 51.2px | 1.15 | -0.03em | size clamp(2rem, 1.3rem + 2.6vw, 3.2rem) | Centered capability catalogue title. |
| heading | Space Grotesk | 700 | 48px | 1.15 | -0.02em | size clamp(1.9rem, 1.2rem + 2.5vw, 3rem) | Default left-aligned chapter title. |
| featured-stat | Space Grotesk | 700 | 44.8px | 1 | -0.04em | size clamp(2rem, 1.4rem + 2vw, 2.8rem) | Mint metric at the left of a highlighted proof card. |
| thesis | Space Grotesk | 600 | 35.2px | 1.3 | -0.01em | size clamp(1.4rem, 1rem + 1.6vw, 2.2rem) | Multiline opinion or strategic argument beside an equation window. |
| stat | Space Grotesk | 700 | 35.2px | 1 | -0.04em | fixed | Numbers in the four-column proof strip. |
| case-title | Space Grotesk | 700 | 28.8px | 1.15 | normal | fixed | Case or product card heading. |
| hero-statement | Space Grotesk | 300 | 25.6px | 1.45 | normal | size clamp(1.15rem, 0.9rem + 1vw, 1.6rem) | Light first line of the opening contrast statement. |
| hero-statement-strong | Space Grotesk | 600 | 25.6px | 1.45 | normal | fixed | Stronger second line of the opening statement, paired with hero-statement. |
| step-title | Space Grotesk | 600 | 18.4px | 1.15 | normal | fixed | Process card heading. |
| hero-body | Space Grotesk | 300 | 17.9px | 1.6 | normal | size clamp(1rem, 0.9rem + 0.4vw, 1.12rem) | Opening explanatory paragraph. |
| tile-title | Space Grotesk | 600 | 17.5px | 1.2 | -0.01em | size clamp(15px, 13px + 0.35vw, 17.5px) | Compact linked capability tiles. |
| body | Space Grotesk | 300 | 16px | 1.6 | normal | fixed | Default explanatory prose and final support line. |
| button | Space Grotesk | 700 | 15px | 1.6 | normal | fixed | Uppercase primary and secondary hero actions. |
| terminal-output | JetBrains Mono | 600 | 15px | 1.75 | normal | fixed | Main terminal output, with smaller commands and prompts. |
| case-body | Space Grotesk | 300 | 14.5px | 1.7 | normal | fixed | Dense explanatory card descriptions; weight 600 phrases emphasize the outcome. |
| caption | Space Grotesk | 300 | 13.5px | 1.6 | normal | fixed | Process-card descriptions. |
| navigation | JetBrains Mono | 300 | 12.5px | 1.6 | normal | fixed | Top navigation and footer links. |
| eyebrow | JetBrains Mono | 300 | 11px | 1.6 | 0.15em, uppercase | fixed | Role labels, metadata and compact section labels; step labels use the same spacing. |
| status | JetBrains Mono | 300 | 11px | 1.6 | 0.1em | fixed | Live update pill with a short white title embedded in mint metadata. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Large type is bold rather than ultralight: display tracking is -0.03em, spotlight tracking tightens to -0.035em, and compact numerical proof tightens to -0.04em.
- Prose is predominantly weight 300. White or pale weight 600 inserts carry conclusions without making every paragraph bright.
- Mint emphasis in large headings and the thesis stays upright; it is a color switch, not a conventional italic voice.
- Use the fluid formulas for their named roles; fixed desktop sizes alone would lose the size relationships on smaller screens.

## Layout

**Density:** Airy chapter spacing around compact, information-rich panels; small annotations and metadata supply density without crowding the main argument.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card title-to-description gap and compact utility gaps. |
| 10px | Tile content rhythm and metadata groups. |
| 14px | Catalogue grid gaps and labels above process titles. |
| 16px | Process grid gutters and prose separation. |
| 18px | Paired hero action gap. |
| 24px | Default container side padding and case-grid gutter. |
| 28px | Process card vertical padding and thesis-to-body spacing. |
| 32px | Case and contact-panel padding. |
| 48px | Hero copy-to-console gap and spotlight interior padding. |
| 56px | Thesis split-layout gap. |
| 60px | Chapter heading-to-case-grid separation. |
| 96px | Closing section top padding. |
| 100px | Default major chapter vertical padding. |

### Containers and grids

- **container**: max width 1200px · side padding 24px. Centered desktop wrapper including side padding; its inner 1152px content width aligns almost all chapters.
- **hero split**: 2 columns · gap 48px. Flexible prose column beside a 360px–420px console; full-width headline and credentials sit above the split.
- **case grid**: 2 columns · gap 24px. Substantial equal-width case cards; a final long case spans both columns.
- **process grid**: 4 columns · gap 16px. Four compact steps with arrows bridging the cards.
- **capability grid**: 4 columns · gap 14px. Numbered linked tiles in repeated rows, with proof underneath each capability name.
- **proof card**: max width 880px · gap 22px. Centered highlighted evidence row; isolated metric, explanatory middle and trailing destination.
- **contact panel**: max width 640px. Centered boxed scope statement above the final action.
- **footer directory**: max width 1200px · 5 columns · gap 24px · side padding 20px. Five monospaced link columns below an identity row and thin divider.

## Corner radius

| Element | Radius |
| --- | --- |
| action keys | 6px |
| console and major cards | 14px |
| compact tiles | 10px |
| metadata pills | 9999px (pill) |
| status dots and back to top | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| console | `0px 30px 70px 0px rgba(0,0,0,0.55), 0px 0px 0px 1px rgba(0,255,148,0.06)` | Opening terminal; dark elevation with an almost invisible mint rim. |
| code panel | `0px 30px 60px 0px rgba(0,0,0,0.5)` | Equation and code windows. |
| live dot | `0px 0px 8px 0px #00ff94` | Small active status indicator, not whole-card neon. |

### Surfaces

#### Canvas · level 0

**Use:** Entire page backing.

**CSS:** `background: #030303; color: #e2e8f0`

**Observed:** Near-black remains dominant across all chapters; the atmospheric layer is restrained.

**Transfer:** Keep the page dark even when switching between narrative and catalogue sections.

#### Chapter band · level 0

**Use:** Separate opinion or principles chapters without a bright color break.

**CSS:** `background: rgba(20,20,20,0.2); border-top: 1px solid rgba(255,255,255,0.06); border-bottom: 1px solid rgba(255,255,255,0.06); padding: 100px 0px`

**Observed:** The fill changes only slightly from the page canvas.

**Transfer:** Use for a considered argument rather than for every feature row.

#### Console window · level 1

**Use:** Command, equation and code content.

**CSS:** `background: #0d0d0d; border: 1px solid rgba(255,255,255,0.1); border-radius: 14px; overflow: hidden; box-shadow: 0px 30px 60px 0px rgba(0,0,0,0.5)`

**Observed:** A darker body sits under a #1a1a1a title bar; three small colored circles establish desktop-window grammar.

**Transfer:** Use actual readable output, not a screenshot-shaped empty rectangle.

#### Protocol spotlight · level 1

**Use:** A featured strategic proposition with supporting principles.

**CSS:** `background: radial-gradient(circle at 82% 38%, rgba(0,255,148,0.09), rgba(0,0,0,0) 34%), linear-gradient(145deg, rgba(13,17,15,0.96), rgba(6,7,7,0.98)); border: 1px solid rgba(0,255,148,0.22); border-radius: 14px; box-shadow: 0px 28px 80px 0px rgba(0,0,0,0.4), 0px 1px 0px 0px rgba(255,255,255,0.04) inset; overflow: hidden`

**Observed:** A thin green edge and extremely faint orthogonal grid lend instrument-panel depth; the right principles box is darker.

**Transfer:** Reserve the strongest atmospheric card treatment for one important proposition.

#### Closing field · level 0

**Use:** Final invitation and directory footer.

**CSS:** `background: #050505; border-top: 1px solid rgba(255,255,255,0.1); padding: 96px 0px 48px`

**Observed:** The invitation is centered, while the directory below returns to left-aligned columns.

**Transfer:** End with an intentional destination, not a generic contact form tacked onto the last card.

## Components

### Sticky navigation

**Use:** Persistent small-scale orientation and contact access.

**CSS:** `position: sticky; top: 0px; height: 65px; z-index: 100; background: rgba(3,3,3,0.898); border-bottom: 1px solid rgba(27,255,159,0.12); backdrop-filter: blur(16px)`

**Text style:** `navigation` — JetBrains Mono 300 · 12.5px/1.6

**Observed:** A prompt-like identity sits left, slash-prefixed categories with tiny chevrons follow, and a command-search key plus CONTACT() sit right. The content wrapper is 1200px with 20px side padding.

**Transfer:** Use a short product identifier with a mint prompt and underscore rather than a large pictorial logo.

### Navigation link

**Use:** Category navigation and the matching directory vocabulary.

**CSS:** `color: #8f9ba8; padding: 6px 0px 6px 6px; border-bottom: 1px solid transparent`

**Text style:** `navigation` — JetBrains Mono 300 · 12.5px/1.6

**Observed:** Compact labels use a leading slash and a separate small downward chevron.

**States:** Declared: hover color #ffffff; focus-visible outline 2px solid #00ff94 with 3px offset.

### Primary button

**Use:** Main next step in the opening and final invitation.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; background: #ffffff; color: #000000; border-radius: 6px; padding: 16px 32px; height: 58px`

**Text style:** `button` — Space Grotesk 700 · 15px/1.6

**Observed:** The opening variant ends with a right arrow. The final protected-contact variant is narrower in height, uses a decryption verb and brackets the label with pale chevrons.

**States:** Declared: hover background #00ff94 and box-shadow 0 0 30px -5px #00ff94; focus-visible outline 2px solid #00ff94 with 3px offset; active transform translateY(1px).

### Secondary button

**Use:** Companion exploration action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: rgba(16,16,16,0.86); border: 1px solid rgba(255,255,255,0.1); color: #ffffff; border-radius: 6px; padding: 16px 32px; height: 58px`

**Text style:** `button` — Space Grotesk 700 · 15px/1.6

**Observed:** Sits beside the primary rather than below it at desktop.

**States:** Declared: hover border-color rgba(255,255,255,0.3) and background rgba(28,28,28,0.9); focus-visible outline 2px solid #00ff94 with 3px offset; active transform translateY(1px).

### Live update pill

**Use:** Compact editorial announcement above the opening title.

**CSS:** `display: inline-flex; align-items: center; gap: 10px; background: rgba(0,255,148,0.1); border: 1px solid rgba(0,255,148,0.2); border-radius: 9999px; padding: 7px 16px; color: #00ff94`

**Text style:** `status` — JetBrains Mono 300 · 11px/1.6 · tracking 0.1em

**Observed:** An 8px glowing live dot precedes tracked metadata; the actual title is white and the trailing arrow returns to mint.

**States:** Declared: hover border-color rgba(0,255,148,0.55) and background rgba(0,255,148,0.14); focus-visible outline 2px solid #00ff94 with 3px offset.

### Terminal card

**Use:** Primary visual demonstration in the opening.

**CSS:** `width: 420px; background: #0d0d0d; border: 1px solid rgba(255,255,255,0.1); border-radius: 14px; overflow: hidden; box-shadow: 0px 30px 70px 0px rgba(0,0,0,0.55), 0px 0px 0px 1px rgba(0,255,148,0.06)`

**Text style:** `terminal-output` — JetBrains Mono 600 · 15px/1.75

**Observed:** A 43px title bar contains three 12px circles, a centered path and a right-side LIVE marker. The body has 22px 24px 20px padding, green prompts, short white commands, gray output and a mint block cursor. The complete opening window is 440px tall.

**Transfer:** Show three short exchanges that explain identity, capability and operating principle; use a valid product workflow or readable pseudocode.

### Case card

**Use:** Detailed product or outcome evidence.

**CSS:** `background: rgba(10,10,10,0.72); border: 1px solid rgba(255,255,255,0.05); border-radius: 14px; padding: 32px; position: relative; overflow: hidden`

**Text style:** `case-title` — Space Grotesk 700 · 28.8px/1.15

**Observed:** Title, mint role, subdued status capsule, inset metric row, narrative description, technical tags and an uppercase text action form a vertical stack. A low-contrast outline symbol sits in the upper right. A radial mint wash at 6% sits over the card without obscuring content.

**Transfer:** Replace case identities with product modules or customer outcomes, preserving proof and operational detail.

### Process card

**Use:** Show a repeatable method as a compact connected sequence.

**CSS:** `background: #0a0a0a; border: 1px solid rgba(255,255,255,0.06); border-radius: 14px; padding: 28px 24px`

**Text style:** `step-title` — Space Grotesk 600 · 18.4px/1.15

**Observed:** Mint STEP_01 label, white short title, muted description. Small mint arrows bridge adjacent cards; an understated mono sentence below resolves the sequence.

### Capability tile

**Use:** Compact linked catalogue with attached proof.

**CSS:** `display: flex; flex-direction: column; gap: 10px; background: linear-gradient(160deg, rgba(16,20,18,0.92), rgba(8,8,8,0.92)); border: 1px solid rgba(255,255,255,0.1); border-radius: 10px; padding: 18px 18px 16px; position: relative`

**Text style:** `tile-title` — Space Grotesk 600 · 17.5px/1.2 · tracking -0.01em

**Observed:** Small muted number sits above the title; a small arrow sits top right. A bottom monospaced proof line is introduced by a mint return arrow. Tiles are about 278×128px.

**States:** Declared: hover border-color rgba(0,255,148,0.45), transform translateY(-2px); focus-visible the same border and transform plus outline 2px solid #00ff94 with 3px offset.

### Featured proof card

**Use:** Give one measured public result more prominence than the surrounding links.

**CSS:** `display: grid; grid-template-columns: auto minmax(0px, 1fr) auto; align-items: center; column-gap: 22px; row-gap: 6px; max-width: 880px; padding: 22px 24px; background: linear-gradient(135deg, rgba(0,255,148,0.07), rgba(10,10,10,0.9) 55%); border: 1px solid rgba(0,255,148,0.28); border-radius: 14px`

**Text style:** `featured-stat` — Space Grotesk 700 · 44.8px/1 · tracking -0.04em

**Observed:** Large mint metric at left with a small uppercase unit below; a vertical rule isolates it from the middle label, artifact title and description. A compact destination is aligned right.

**States:** Declared: hover border-color rgba(0,255,148,0.6), transform translateY(-2px); focus-visible the same border and transform plus outline 2px solid #00ff94 with 3px offset.

### Contact scope panel

**Use:** Qualify the final invitation with specific useful conversation areas.

**CSS:** `max-width: 640px; padding: 32px; background: #0a0a0a; border: 1px solid rgba(255,255,255,0.06); border-radius: 14px; box-shadow: 0px 25px 50px 0px rgba(0,0,0,0.5); overflow: hidden; position: relative`

**Text style:** `eyebrow` — JetBrains Mono 300 · 11px/1.6 · tracking 0.15em · uppercase

**Observed:** A thin mint left rail, small live dot and uppercase heading introduce a two-column list of muted monospaced topics with prompt marks.

**Transfer:** State concrete fit criteria or use cases rather than filling it with broad promises.

### Footer link

**Use:** Dense directory navigation below the closing invitation.

**CSS:** `color: #8f9ba8; padding: 5px 0px`

**Text style:** `navigation` — JetBrains Mono 300 · 12.5px/1.6

**Observed:** Five columns have mint slash-prefixed headings. Above them, a compact identity row pairs prompt-style initials with a right-aligned descriptor; below them, hairlines divide copyright and small build/utility notes.

**States:** Declared: hover color #ffffff; focus-visible outline 2px solid #00ff94 with 3px offset.

## Imagery and graphics

### Network atmosphere

**Use:** Persistent low-contrast backdrop behind both prose and panels.

**Observed:** Sparse tiny gray nodes and faint connecting lines sit across a black field, with subtle grain and a dim green wash toward the upper right. The visual stays subordinate to even the smallest annotations; there is no photographic hero.

**Transfer:** Retain the connected-node atmosphere for any product; it should read as latent activity rather than a wallpaper illustration.

**Build:** Place a pointer-events:none SVG behind content. Distribute sparse 1px–2px gray nodes, connect only nearby nodes with 1px white lines at roughly 3–6% opacity, and keep the centers of text blocks visually clear. Add a fixed full-viewport radial-gradient(55% 38% at 82% -5%, rgba(0,255,148,0.07), rgba(0,0,0,0) 65%). Overlay tiled SVG fractalNoise with baseFrequency 0.65, numOctaves 3 at opacity 0.03. Match the barely visible network; exact node positions are not essential.

### Readable instrument windows

**Use:** Hero visual, thesis equation and principles illustration.

**Observed:** The art is constructed from text: a command session in the opening, a fraction-style equation in a window, and syntax-colored JavaScript-like principles later. Windows remain upright and front-facing, around the same scale as the prose they accompany, without perspective mockups or photographic backing.

**Transfer:** Create one readable product-specific command session or result trace. For nontechnical products, show an input → decision → outcome log inside the same window rather than inventing a code-heavy interface.

**Build:** Use the Terminal card or Console window surface. Build the title bar in HTML, using three 12px traffic-light dots and an 11px monospaced path label. Set the content in real selectable mono text, green prompts and pale outputs. For the equation variant, use a short centered fraction with a thin gray rule and a mint denominator; keep surrounding comments muted.

### Metallic headline and command markings

**Use:** Signature title finish, chapter markers and small explanatory flourishes.

**Observed:** The opening title begins white and ends silver-gray. Left-aligned chapter headings often have a 96×4px mint rule fading to transparent; small code/query chips sit at the opposite side. These details evoke a system console rather than decorative illustration.

**Transfer:** Apply the metallic split to two meaningful parts of a short product promise; use real process notation or a concise pseudo-query beside selected chapter headings.

**Build:** Clip linear-gradient(to right, #ffffff, #8f9ba8, #7d8795) to the second title span with background-size:200% auto. Under chapter headings, draw a 96px wide, 4px high linear-gradient(to right, #00ff94, rgba(0,0,0,0)). Build query chips as 6px-radius translucent white panels with 12px padding and compact mono text, leaving their syntax secondary.

### Layered technical stack

**Only for:** deep technical capability explanations

**Use:** Extended explanation of how operational layers relate.

**Observed:** Five thin perspective planes with grid textures, edge labels and small tile-like details form an exploded stack beside a textual hierarchy. Green highlights single out one plane; the surrounding hierarchy is a separate text-and-tag structure.

**Transfer:** Use this only when a product genuinely has meaningful layers. A minimum viable version is five skewed SVG rectangles with faint grid strokes and one green-outlined layer, paired with a readable unskewed legend.

**Build:** Draw five dark SVG quadrilaterals with 6px-rounded visual corners, thin translucent white edges and a regular low-opacity orthogonal grid. Offset each plane vertically to expose its label strip; give one plane rgba(0,255,148,0.35) edging and a few rgba(0,255,148,0.16) filled cells. Keep all semantic labels outside the perspective transform.

### Icons

**Observed:** Icons are sparse: 48×48px pale outline symbols with 1px round strokes on case cards, 10px chevrons with 1.5px round strokes in navigation, and a 16px right arrow with 2.5px round stroke on the white primary action. Prompt marks, return arrows and underscores do much of the icon work.

**Transfer:** Choose simple outline symbols with plenty of empty space. Use arrows and terminal punctuation for navigation instead of a dense multicolor icon set.

## Section recipes

How recurring sections are built.

### First screen: Identity and console opening

**Observed:** The first screen starts with Sticky navigation, then a Live update pill above a left-aligned single-line two-tone display title spanning roughly two thirds of the content width. A compact mint monospaced credential line follows. Below, a light-to-bold contrast statement, gray support paragraph and paired Primary button / Secondary button occupy the left column; a 420×440px Terminal card occupies the right with a 48px gap. The hero has 54px top and 45px bottom padding inside a 1200px wrapper. Layers are black canvas, Network atmosphere, subtle upper-right mint wash, then all text and windows. Within 900px the title, credentials, full statement, paragraph, both actions and full console are visible; the stat strip begins at the bottom edge and continues below.

**Transfer:** Lead with a short product identity or promise and a product-specific live-update pill. Replace personal credentials with compact audience or operating-context metadata, and use a three-exchange workflow log if there is no interface to show. Related editorial or technical pages can open with the same small mono metadata and left-aligned headline at the appropriate chapter scale, retaining a concrete instrument-like demonstration.

**Avoid:** Do not turn this into a centered headline above a giant dashboard, put a terminal behind the text, or let the primary actions disappear below the first screen.

**Text style:** `display` — Space Grotesk 700 · 86.4px/1.04 · tracking -0.03em

### Horizontal proof strip

**Observed:** A 153px dark band uses four equal columns with 32px gaps, 40px vertical interior padding and subtle vertical separators. White 35.2px numbers sit above 11px tracked labels; the final metric switches to mint.

**Transfer:** Use a few genuinely different metrics with their units and contexts; allow one to be visually privileged.

**Text style:** `stat` — Space Grotesk 700 · 35.2px/1 · tracking -0.04em

### Protocol spotlight

**Observed:** Protocol spotlight surface holds a 48px-padded split grid with a 64px gap. A small mint label leads to a two-line white/mint assertion, compact prose and a green-tinted action key. A darker right panel contains three numbered principle rows separated by hairlines.

**Transfer:** Pair one decisive positioning statement with the operating constraints that make it credible.

**Text style:** `spotlight-heading` — Space Grotesk 700 · 55.2px/1.08 · tracking -0.035em

### Chapter title and case evidence

**Observed:** A left heading sits above a 96×4px fading mint rule; a small query chip aligns at its right. The Case grid begins 60px below and uses substantial Case cards with inset metrics and technical tags.

**Transfer:** Use the same composition for customer outcomes, product modules or operating environments, without requiring a fixed number of cases.

**Text style:** `heading` — Space Grotesk 700 · 48px/1.15 · tracking -0.02em

### Opinion and equation

**Observed:** Chapter band holds a 1.2fr / 1fr split with a 56px gap. Small uppercase metadata introduces a 35.2px thesis, with a mint phrase inline, followed by gray prose and compact text destinations. A Console window on the right makes the argument tangible as a short equation.

**Transfer:** Convert an abstract claim into a ratio, constraint or transparent decision model rather than adding generic benefit icons.

**Text style:** `thesis` — Space Grotesk 600 · 35.2px/1.3 · tracking -0.01em

### Centered research proof

**Observed:** A centered mono label sits over multiple rows of compact dark topic pills. Short supporting prose leads to Featured proof card, then a dense set of text links and a hairline-separated editorial recognition note.

**Transfer:** Use a topic cloud and one verifiable artifact to substantiate expertise. Keep destinations specific and the featured metric isolated.

**Text style:** `featured-stat` — Space Grotesk 700 · 44.8px/1 · tracking -0.04em

### Connected method

**Observed:** A chapter heading and query chip introduce four Process cards in one row with 16px gaps. Mint arrows bridge the cards; a centered small mono closing sentence sits beneath.

**Transfer:** Present a repeatable method using short verbs and a single outcome sentence; adapt the number of steps to the product.

**Text style:** `heading` — Space Grotesk 700 · 48px/1.15 · tracking -0.02em

### Principles as source code

**Observed:** A Chapter band pairs a numbered list of short monospaced maxims with a Console window containing syntax-colored pseudocode. The heading stays left-aligned with its fading mint rule.

**Transfer:** Express actual operating principles, supported by a small readable pseudo-object or policy block. Syntax colors belong inside the illustration, not across marketing headings.

**Text style:** `heading` — Space Grotesk 700 · 48px/1.15 · tracking -0.02em

### Proof under every capability

**Observed:** A centered catalogue heading and short support line introduce a four-column grid of Capability tiles. Each tile has a quiet index, white title, directional arrow and a bottom proof reference. An extended technical explanation can follow as Layered technical stack.

**Transfer:** Make each capability a destination with a concrete supporting example beneath it; do not turn all proof into a separate logo wall.

**Text style:** `catalog-heading` — Space Grotesk 700 · 51.2px/1.15 · tracking -0.03em

### Selective closing and directory

**Observed:** Closing field opens with a centered large invitation and two short gray support lines, the second italic. Contact scope panel sits below, followed by a small red access notice and a white decryption-style Primary button. Four compact social/editorial destination cards follow, one mint-edged. A restrained centered biography, tracked motto, security fingerprint and small sound control complete the invitation. The separate footer begins with an identity row, then a five-column monospaced directory and hairline-separated utility notes; a circular up-arrow remains at the lower right.

**Transfer:** Retain the selective invitation, explicit fit panel, single decisive action and structured directory. Adapt biography to a brief product/company description. Security fingerprints and sound controls belong only where functional; preserve the technical sign-off through real metadata rather than fake security theater.

**Text style:** `closing-heading` — Space Grotesk 700 · 57.6px/1.15 · tracking -0.02em

## Page flow

**Storyline:** identity and operating promise → compact proof → positioning with constraints → detailed evidence → thesis and measured artifact → repeatable method → capability catalogue → selective invitation → utility directory

### Expert-led marketing landing page that turns a strong point of view into credible operational proof

1. **Promise** — Two-tone identity masthead, short contrarian statement and live console demonstration.
2. **Quantified proof** — A four-part stat strip follows the opening without taking over the visual field.
3. **Positioning** — A green-edged protocol spotlight translates the promise into operating principles.
4. **Detailed evidence** — Substantial two-column cards combine concrete scope, metrics, descriptions and technical tags.
5. **Thought leadership** — An opinion beside an equation window leads into topic pills, a highlighted artifact and editorial links.
6. **Method and principles** — Connected steps and a numbered maxim/code pairing explain how outcomes are produced.
7. **Capabilities** — Numbered linked tiles attach proof directly to each capability; a deeper layer diagram extends the explanation.
8. **Human context** — A narrow muted band briefly steps outside the main operational narrative.
9. **Closing call** — A selective centered invitation, boxed fit criteria, protected-contact action and destination cards.
10. **Utility ending** — Brief contextual description and technical sign-off lead to an identity row and five-column directory.

**Transfer:** Borrow the progression from assertion to verification, not the source's section count. Choose evidence blocks that the product can honestly support, and retain a working-console device, a highlighted proof artifact and an intentional final invitation.

## Writing

Direct, technically fluent and skeptical of empty claims. The writing has the confidence of an operator explaining constraints, with occasional dry, deliberately selective language rather than welcoming everyone equally.

**Do not copy:** Do not reuse the person's name, initials, companies, product identities, proprietary concept names, motto, security fingerprint, numerical achievements or biographical claims. Source quotations are examples of structure and tone, not reusable marketing copy. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The source speaks as a first-person individual in assertions and uses the reader sparingly in practical invitations. For a product, use a consistent first-person plural or product subject while keeping accountability explicit.
- **Rhythm:** Short contrast headlines and terse action labels punctuate longer, specific explanatory sentences. Full stops make the claims feel final; slashes, arrows and code punctuation belong mainly in labels and utilities.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning headline | Reject the familiar category, then state the stronger operating idea. | 3–10 words across one or two assertions | “AI isn't a feature. It's an operating model.”<br>“Systems, not tools.” |
| Opening statement | A light denial followed by a more consequential positive statement. | A short first sentence, then a concrete outcome sentence | “I don't build companies.”<br>“I build systems that remove friction from entire industries.” |
| Supporting argument | Name the real constraint and change the metric by which success is judged. | One or two specific sentences | “The goal is not more AI. It is more verified work completed per unit of time, cost and risk.” |
| Method heading | Compact imperative naming an operational change. | 2–5 words | “Reduce complexity”<br>“Increase signal”<br>“Automate the decisions” |
| Action | Uppercase verb plus a specific destination; command-like phrasing for technical entry points. | 2–5 words | “READ THE MANIFEST”<br>“ACCESS TERMINAL”<br>“READ THE FULL THESIS” |
| Closing invitation | A filter for relevance, then a straightforward invitation. | One short heading and one support sentence | “High-signal connections only.”<br>“If the conversation has strategic value - I am open.” |

**Words and phrasing to use:** systems; signal; verified; constraints; workflow; economics; accountability; measured; operating model; friction

**Avoid:** revolutionary; magical; seamless everything; limitless possibilities; game-changing; unlock your potential

**Rules:**

- Tie each benefit to a workflow, constraint, measured result or inspectable artifact.
- Use contrast to clarify priorities, not just to sound provocative.
- Let technical labels use //, >, arrows and short paths; keep ordinary prose readable.
- Qualify access and fit calmly; do not imitate aggression where the product calls for trust.
- Keep action destinations explicit rather than repeating Learn more everywhere.

## Do's and Don'ts

### Do

- Use the 1200px wrapper with 24px side padding to align major chapters.
- Keep display weight 700 and prose mostly 300; use 600 only for selected conclusions.
- Pair a white primary key and charcoal secondary key with 6px corners and an 18px gap.
- Put 11px monospaced labels above or below the larger human-readable text.
- Keep a real command/output, equation or policy illustration readable at its displayed size.
- Attach a proof reference directly beneath each 17.5px capability title.
- Use 100px chapter padding to separate dense panels rather than increasing every small gap.
- Give the final invitation a 640px fit panel and a structured directory underneath.

### Don't

- Do not replace near-black chapters with alternating white sections or broad saturated mint fields.
- Do not turn the 14px console corners into oversized rounded bubbles.
- Do not set all prose in monospace; the narrative voice belongs to Space Grotesk.
- Do not make every number mint: the compact proof strip privileges only one figure.
- Do not use full-card neon outer glows; keep glow localized to live dots and interactive emphasis.
- Do not enlarge metadata to body size or remove its tracking; it should retain its equipment-label character.
- Do not introduce perspective dashboard mockups as the main hero; windows here face the reader directly.
- Do not scatter purple, blue and yellow syntax colors through the marketing layout; keep them inside code or status illustrations.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary actions declare background-color, border-color, color and box-shadow transitions of 0.3s; many text links use color 0.2s.
- Content reveals declare opacity 0.7s and transform 0.7s. Linked capability tiles declare border-color, background-color and transform 0.25s.
- The metallic headline declares shimmer for 3s ease-in-out, twice, alternating; prompt cursors declare a 1.12s steps(2,start) infinite blink.
- Other declared accents include a 4.5s ease-in-out CTA breath and 2s live-indicator pulses. Active buttons translate down 1px; capability links lift 2px on hover.

**Transfer:**

- Confine repeated animation to tiny live indicators, cursor punctuation and the restrained headline finish.
- Preserve the 1px pressed-key feedback and 2px linked-tile lift; reveal motion should settle into the clean readable composition.

**Unknown:**

- Exact reveal distances, full network animation behavior and timing of interactive contact decryption are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 560px, 640px, 760px, 768px, 820px, 821px, 900px, 960px, 961px, 1023px, 1024px, 1100px and 1179px.
- Headline formulas use clamps, preserving lower bounds while scaling toward desktop display sizes.

**Transfer:**

- On narrow screens, keep the identity and promise before the console, let the console fit the content width, and preserve visible title-bar details.
- Reduce four-column catalogues and processes to fewer columns before compressing their proof lines; preserve numbering and directional logic.
- Stack the proof card's metric and artifact text when the three-column composition becomes cramped; keep the metric visually separated.
- Simplify the command navigation into compact access controls without losing the prompt-style identity.

**Unknown:**

- Mobile layout states, exact breakpoint-to-component behavior and touch interactions were not visually verified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
