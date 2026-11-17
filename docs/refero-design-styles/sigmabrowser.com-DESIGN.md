# Sigma — luminous utility stages

## Overview

A dark, approachable software style with soft pools of electric blue, violet and cyan surrounding tangible product interfaces. Medium-weight grotesk typography and direct, benefit-led language keep the atmosphere practical rather than futuristic. Spacious black chapters alternate with bright demonstration stages, fine-line diagrams and compact proof graphics; it suits consumer tools and technically capable products that need to feel easy to use.

### Essentials

- The promise continues in a dimmer voice at the same scale: 60px/1, weight 500, -0.01em tracking, with the supporting headline span at 0.6 opacity.
- A usable product is the hero object: left-aligned text above a 1202px-wide desktop interface, a tall secondary device overlapping its right edge, and a blue–violet–cyan atmosphere behind both.
- Actions are white rounded rectangles, not pills: the opening action is 58px tall with an 18px radius; compact navigation actions use 36px height and 10px radius; the conversion stage expands to 77px and 25px.
- Black remains the connective tissue: #040404 chapters and #aaaaaa support text occupy most of the long page; saturated color belongs in media stages, bottom-lit cards, segmented proof bars and the luminous ending, not ordinary body text.
- Capability stories are physical stages: a 12px-radius colored panel, 32px inset text, a 42px headline and an oversized floating interface with a 14px radius and dark shadow. Use a simplified working-state mockup when finished product media is unavailable.
- Proof has a distinctive comb texture: 6×28px rounded segments with 7px gaps shift from violet to cyan, with the leading result at 42px/0.8 and subsequent results at 32px/1.
- The ending rekindles the opening light: a centered product emblem and 60px conversion headline rise over a purple glow, followed by understated questions and a substantial cyan-to-violet illuminated directory footer. A simple original rounded emblem can replace a detailed product icon.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof cyan | `#6cd1fe` | `--color-bar-cyan` | accent | Right end of the segmented comparison spectrum. |
| Proof violet | `#6f71ff` | `--color-bar-violet` | accent | Left end of the segmented comparison spectrum. |
| Lavender line | `#a991ff` | `--color-luminous-rule` | border | Center of the conversion stage's 1px gradient rule, fading to 0.1 opacity at the edges. |
| Purple illumination | `#421582` | `--color-glow` | background | Visible central purple of the conversion glow, made with rgba(125,38,255,0.5) over near black; fades to transparent. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, action, border | Headings, primary actions and luminous edges. Headline continuations and product-stage labels use white at 0.6 opacity. |
| Comparison ink | `#000000` | `--color-tab-ink` | text | Active comparison-tab text on white. |
| Near black | `#040404` | `--color-canvas` | background, text | Default page canvas and text on white actions. |
| Question charcoal | `#131313` | `--color-faq` | surface | White at 0.06 over near black for collapsed question rows. |
| Soft charcoal edge | `#181818` | `--color-edge` | border, surface | White at 0.08 over near black: directory separators, inactive comparison tabs and unfilled bar segments. |
| Raised charcoal | `#222222` | `--color-raised` | surface, border | White at 0.12 over near black: secondary actions and inset card outlines; the same alpha picks up color over illuminated backdrops. |
| Dim gray | `#575757` | `--color-footnote` | text | Visible result of rgba(170,170,170,0.5) over the canvas for benchmark methodology. |
| Support gray | `#aaaaaa` | `--color-muted` | text, link | Paragraphs on black, navigation labels and directory links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| platform-specific landing pages | Subtle tile | `#0e0e0e` | `--color-tile` | surface | White at 0.04 over near black under overview media. |

## Typography

- **Overused Grotesk** — All marketing headings, paragraphs, labels and actions. An open, modern grotesk with rounded curves, compact headline proportions and a friendly medium weight. If unavailable, use **Inter**. Use weights 400–600 and retain the tight headline tracking. Font stack: "Overused Grotesk", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Overused Grotesk | 500 | 60px | 1 | -0.01em | Opening promise and centered conversion headline. |
| heading | Overused Grotesk | 500 | 46px | 1 | -0.01em | Main chapter headings and feature-detail titles. |
| stage-heading | Overused Grotesk | 500 | 42px | 1 | -0.01em | Benefit title inside luminous product stages. |
| result-leading | Overused Grotesk | 500 | 42px | 0.8 | normal | First comparison result, subtly luminous. |
| stage-label | Overused Grotesk | 500 | 32px | 1.01 | normal | Sentence-case capability label above the stage title, at 0.6 opacity. |
| result | Overused Grotesk | 500 | 32px | 1 | normal | Subsequent comparison values at 0.8 opacity. |
| large-action | Overused Grotesk | 500 | 29px | 1 | normal | Paired actions in the centered conversion stage. |
| card-heading | Overused Grotesk | 500 | 26px | 1 | -0.02em | Bottom-lit feature card titles. |
| item-heading | Overused Grotesk | 500 | 24px | 1 | -0.02em | Line-diagram benefit items and ruled trust cells. |
| article-heading | Overused Grotesk | 500 | 24px | 1.2 | -0.02em | Multi-line editorial-card titles. |
| lead | Overused Grotesk | 500 | 24px | 1.4 | normal | Gray introductions and feature-detail support. |
| comparison-label | Overused Grotesk | 500 | 24px | 1 | normal | Comparison row labels. |
| comparison-tab | Overused Grotesk | 500 | 24px | 1.01 | normal | Comparison category tabs. |
| stage-body | Overused Grotesk | 500 | 22px | 1.4 | -0.02em | White explanatory paragraphs within colorful product stages. |
| primary-action | Overused Grotesk | 500 | 22px | 1 | normal | Opening conversion action. |
| directory-heading | Overused Grotesk | 600 | 22px | 1 | -0.03em | Footer group headings. |
| body | Overused Grotesk | 500 | 20px | 1.4 | normal | Supporting card and trust-grid descriptions. |
| text-link | Overused Grotesk | 500 | 20px | 1 | normal | Underlined stage detail links. |
| question | Overused Grotesk | 500 | 18px | 1 | normal | Closed FAQ questions and comparison result suffixes. |
| navigation | Overused Grotesk | 500 | 16px | 1.2 | normal | Top-level navigation labels. |
| compact-action | Overused Grotesk | 500 | 16px | 1 | normal | Header actions and small card controls. |
| directory-link | Overused Grotesk | 500 | 16px | 1.4 | normal | Footer navigation links. |
| note | Overused Grotesk | 400 | 16px | 1.4 | normal | Methodology and footer company information. |

**Notes:**

- Headings are medium rather than bold. Display and chapter tracking stays at -0.01em; smaller card and item titles tighten to -0.02em.
- Keep the headline continuation at display scale instead of turning it into a small subtitle. It is a continuation of the main promise.
- Use sentence case throughout; category labels are not tiny uppercase eyebrows.
- The base text size has a declared 1.11111vw rule; the role recipes above are the desktop sizes. Do not assume that every role shares that viewport formula.

## Layout

**Density:** Airy chapters with compact controls: expansive black pauses surround dense, tangible product demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-action label gap. |
| 8px | Stage label to stage title; paired header actions. |
| 12px | Headline-to-support and footer-link gaps; paired conversion actions. |
| 14px | Between collapsed question rows. |
| 20px | Three-column feature and editorial grid gaps. |
| 26px | Gap between large demonstration panels. |
| 28px | Feature text stacks and bottom-lit card padding. |
| 32px | Product-stage text insets and comparison row gaps. |
| 52px | Chapter heading to feature card grid. |
| 60px | Footer band padding and conversion action-group top padding. |
| 64px | Vertical chapter padding in platform-specific landing pages. |
| 76px | Opening actions to product object. |
| 82px | Desktop side gutters. |
| 120px | Default chapter top and bottom padding. |
| 176px | Default opening top padding. |

### Containers and grids

- **main-container**: max width 1276px · side padding 82px. Centered desktop alignment for navigation, chapters and footer; usable chapter width is 1274px within the outer page edge.
- **feature-grid**: 3 columns · gap 20px. Equal 411px feature or editorial columns.
- **product-panels**: 2 columns · gap 26px. A full-width demonstration above two 624px portrait panels.
- **detail-copy**: max width 406px. Narrow left text column beside a roughly 620px visual.
- **question-layout**: 2 columns · gap 62px. Heading and contact copy on the left, a 60% question-list column on the right with 30px inner side padding.
- **directory-grid**: 4 columns · gap 40px. Lower footer link-directory groups separated by horizontal hairlines.
- **overview-grid** (only for platform-specific landing pages): 4 columns · gap 20px. Four compact benefit columns with 304×319px media above category, title and explanation.

## Corner radius

| Element | Radius |
| --- | --- |
| header-action | 10px |
| opening-action | 18px |
| conversion-action | 25px |
| question-row | 20px |
| luminous-card | 24px |
| product-stage | 12px |
| floating-interface | 14px |
| hero-interface | 20px |
| comparison-tab | 16px |
| product-emblem | 32px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-interface | `0px 12px 32px 0px rgba(0,0,0,0.35), 0px 0px 0px 0px rgba(0,0,0,0.23)` | Floating browser windows inside demonstration stages. |
| hero-interface | `0px 13px 40px 0px rgba(0,0,0,0.35), 0px 0px 0px 1px rgba(0,0,0,0.23)` | Main opening product window. |

### Surfaces

#### Black canvas · level 0

**Use:** Connective background for chapters.

**CSS:** `background: #040404; color: #ffffff`

**Observed:** The dark canvas remains continuous through utility and proof sections.

**Transfer:** Keep ordinary content on black; reserve large color for media-bearing stages.

#### Navigation glass · level 3

**Use:** Fixed header backdrop.

**CSS:** `background: rgba(4, 4, 4, 0.88); backdrop-filter: blur(50px); border-bottom: 1px solid rgba(255, 255, 255, 0.08)`

**Observed:** Content passes beneath a near-opaque dark strip.

**Transfer:** Retain the restrained translucency rather than a bright frosted bar.

#### Bottom-lit feature · level 1

**Use:** Illustrated feature cards.

**CSS:** `background-color: #040404; background-image: radial-gradient(circle farthest-side at 50% 100%, rgba(129, 56, 255, 0.5) 10%, rgba(59, 0, 153, 0.12)); border-radius: 24px; box-shadow: 0px 0px 0px 1px rgba(255, 255, 255, 0.12) inset`

**Observed:** Light swells toward the bottom behind a translucent illustration; sibling cards use red and blue radial washes.

**Transfer:** Use distinct low-key hues to differentiate capabilities while leaving the title area nearly black.

#### Question charcoal · level 1

**Use:** Closed FAQ rows.

**CSS:** `background: rgba(255, 255, 255, 0.06); border-radius: 20px`

**Observed:** A soft neutral lift with no bright outline.

**Transfer:** Group one concise question per row.

#### Conversion glow · level 0

**Use:** Centered conversion stage backdrop.

**CSS:** `background-image: radial-gradient(circle closest-side, rgba(125, 38, 255, 0.5), rgba(125, 38, 255, 0))`

**Observed:** A 1274×1025px elliptical light field is clipped inside a shallower stage; its lower half is brightest.

**Transfer:** Keep the top and sides near black so the headline and emblem stand clear.

#### Ruled trust grid · level 0

**Use:** Two-by-two compact assurance blocks.

**CSS:** `border-right: 1px solid rgba(255, 255, 255, 0.12); border-bottom: 1px solid rgba(255, 255, 255, 0.12); padding: 32px 30px`

**Observed:** Shared interior rules divide cells instead of separate filled cards; remove exterior rules at the outer edges.

**Transfer:** Use for concise operational facts or product principles.

#### Instruction panel · level 1

**Only for:** platform-specific onboarding sections

**Use:** Numbered setup cards.

**CSS:** `background: linear-gradient(90deg, rgba(34, 47, 140, 0.2), rgba(56, 86, 165, 0.2)); border-radius: 24px; padding: 24px`

**Observed:** Dark navy panels hold friendly platform illustrations above compact numbered text.

**Transfer:** Keep setup guidance visually distinct from the brighter marketing feature cards.

## Components

### Fixed navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: fixed; height: 69px; padding: 16px 82px; border-bottom: 1px solid rgba(255, 255, 255, 0.08)`

**Text style:** `navigation` — Overused Grotesk 500 · 16px/1.2

**Observed:** Logo at left, grouped menu labels toward the right, then a dark secondary action and white primary action. Navigation glass sits behind it; menu labels have small gray chevrons.

### Primary button

**Use:** Opening conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; padding: 18px 20px; height: 58px; border-radius: 18px; background: #ffffff; color: #040404`

**Text style:** `primary-action` — Overused Grotesk 500 · 22px/1

**Observed:** A solid platform icon precedes the label. The platform-specific opening uses 44px horizontal padding.

**States:** Declared: hover scale(1.03); focus-visible unknown; active scale(0.97).

### Compact action

**Use:** Header conversion and small secondary actions.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 36px; padding: 0px 13px; border-radius: 10px; background: #ffffff; color: #040404`

**Text style:** `compact-action` — Overused Grotesk 500 · 16px/1

**Observed:** The secondary sibling replaces the white fill with white at 0.12 alpha and uses white text. Small feature-card controls use that secondary treatment.

**States:** Declared: hover scale(1.05); focus-visible unknown; active scale(0.97).

### Stage detail link

**Use:** Subordinate navigation under product explanations.

**CSS:** `color: #ffffff; opacity: 0.6; border-bottom: 1px solid #ffffff`

**Text style:** `text-link` — Overused Grotesk 500 · 20px/1

**Observed:** The underline hugs the words rather than spanning the text column.

### Luminous feature card

**Use:** Compact illustrated capability summaries.

**CSS:** `padding: 28px; border-radius: 24px; background-color: #040404; background-image: radial-gradient(circle farthest-side at 50% 100%, rgba(129, 56, 255, 0.5) 10%, rgba(59, 0, 153, 0.12)); box-shadow: 0px 0px 0px 1px rgba(255, 255, 255, 0.12) inset`

**Text style:** `card-heading` — Overused Grotesk 500 · 26px/1 · tracking -0.02em

**Observed:** An icon and Compact action share the top row; title and gray description follow, then a hairline and a large low-contrast illustration. Desktop cards are 411×565px. An expanded face replaces the illustration with larger explanation text and a Minimize control.

**Transfer:** Use an original translucent metaphor relevant to the feature; keep the content hierarchy intact.

### Comparison tab

**Use:** Switching among kinds of quantified proof.

**CSS:** `padding: 13px 20px; height: 50px; border-radius: 16px; background: #ffffff; color: #000000`

**Text style:** `comparison-tab` — Overused Grotesk 500 · 24px/1.01

**Observed:** Active tab is white; inactive tabs use white at 0.08 alpha with white labels. Tabs sit inline with the chapter heading and wrap as a group.

**States:** Declared: hover scale(1.03); focus-visible unknown; active scale(0.97).

### Segmented comparison

**Use:** Readable comparative proof without a conventional axis chart.

**CSS:** `display: flex; gap: 7px; height: 28px`

**Text style:** `comparison-label` — Overused Grotesk 500 · 24px/1

**Observed:** A comparison label and tiny competitor icon sit above a strip of 64 segments, each 6×28px with fully rounded ends. The strip spans 825px; result text sits 36px to its right. Fill proceeds violet to cyan, with unused segments at white 0.08 alpha. The first result uses result-leading and a white glow; following results use result.

**Transfer:** Represent substantiated values with the same comb-like meter; put the method note beneath the group.

### Question row

**Use:** Objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 22px; min-height: 62px; border-radius: 20px; background: rgba(255, 255, 255, 0.06); color: #ffffff`

**Text style:** `question` — Overused Grotesk 500 · 18px/1

**Observed:** Question text on the left, a small gray chevron at the far right. Rows are separated by 14px.

### Conversion button

**Use:** Large action pair in the centered conversion stage.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; padding: 24px 26px; height: 77px; border-radius: 25px; background: #ffffff; color: #040404`

**Text style:** `large-action` — Overused Grotesk 500 · 29px/1

**Observed:** A platform icon precedes the primary label. The adjacent secondary action uses white text on white at 0.12 alpha, allowing the purple backdrop to show through.

**States:** Declared: hover scale(1.03); focus-visible unknown; active scale(0.97).

### Footer directory link

**Use:** Dense but readable closing navigation.

**CSS:** `color: #aaaaaa`

**Text style:** `directory-link` — Overused Grotesk 500 · 16px/1.4

**Observed:** Links form vertical lists with 12px gaps, grouped beneath directory-heading titles. The footer has a primary navigation tier, a topic-directory tier and a final company-information row.

### Instruction card

**Only for:** platform-specific onboarding sections

**Use:** Short visual setup steps.

**CSS:** `padding: 24px; border-radius: 24px; background: linear-gradient(90deg, rgba(34, 47, 140, 0.2), rgba(56, 86, 165, 0.2))`

**Text style:** `item-heading` — Overused Grotesk 500 · 24px/1 · tracking -0.02em

**Observed:** Three equal cards place a 363×206px illustration above a row with a 44px numbered badge, title and small gray instruction. The badge has a 14px radius, pale blue at 0.1 alpha fill and pale gray at 0.08 alpha border.

## Imagery and graphics

### Atmospheric product opening

**Use:** Signature opening and closing illumination.

**Observed:** Near-black upper areas dissolve into broad violet and blue fields, with cyan concentrated at the lower left and lavender toward the lower right. Fine grain prevents a sterile flat gradient. The opening holds a large crisp desktop window with a dark mobile device overlapping its right edge.

**Transfer:** Stage an actual workflow, not a detached logo. Without finished media, create one convincing interface frame with a document or working state and a smaller companion view.

**Build:** Layer large radial gradients over near black: cyan rgba(50,190,240,0.65) anchored lower left, violet rgba(90,55,225,0.65) below center and lavender rgba(150,100,220,0.5) lower right. Let the top third fade to black; use broad overlapping ellipses rather than sharp rings. Add a very low-opacity monochrome noise layer. Match the soft light; exact stops are not essential.

### Luminous demonstration panels

**Use:** Primary capability storytelling.

**Observed:** Wide panels pair a narrow left text column with a large floating browser view at right. Portrait variants move the media between title and body. Backdrops include charcoal-to-orange and pink, cyan-to-violet, and green-to-teal light. UI remains crisp and mostly light, with subtle dark shadows and rounded window edges.

**Transfer:** Use real product interactions or a carefully simplified workflow mockup; keep media much larger than the copy and allow edge clipping inside the colored panel.

**Build:** Use a 12px clipped rectangle with a near-black base. Add two or three oversized blurred radial color fields below and to the right; keep the upper-left corner dark for the title. Place the window 32px from its framing edge, give it a 14px radius and floating-interface shadow. For a paired layout, use equal-width panels separated by 26px.

### Translucent feature metaphors

**Use:** Lower half of bottom-lit cards.

**Observed:** A laptop and lock, a stop-hand and a word-network diagram appear as muted translucent forms, tinted by purple, red or blue light rather than full-color clip art.

**Transfer:** Choose one simple literal metaphor per feature. A flat translucent line illustration is the minimum version; maintain the dark monochrome tint.

**Build:** Draw one central SVG silhouette or outline with white at 0.12–0.35 alpha, set it above the card's radial light and soften only secondary layers. Keep the main object within roughly 350×250px, with no white rectangular backing.

### Desktop detail vignettes

**Use:** Long-form feature chapters.

**Observed:** A tall blue desktop-wallpaper tile at right backs floating interface fragments, highlighted text, extension icons or tab stacks. Left text remains on black with a small dark rounded icon badge above its title.

**Transfer:** Use a restrained blue abstract backdrop and one legible interaction fragment per chapter; preserve the asymmetry and black text-side breathing room.

**Build:** Create a vertical clipped tile about 620px wide, layering a pale sky-blue upper field with curved deep-blue and cyan bands across the lower half. Blur the large curves gently, then overlay crisp workflow fragments with rounded edges and shadows.

### Wireframe principles

**Use:** A quieter visual counterpoint to saturated product scenes.

**Observed:** Three white hairline isometric diagrams—layered planes, interlocking pieces and a faceted geometric form—float on black above text columns. Each image area is 384×280px, with thin vertical dividers between columns.

**Transfer:** Abstract the new product's principles into a small family of related geometric constructions, not stock photos.

**Build:** Use SVG with roughly 1px white strokes at reduced opacity and no filled background. Draw repeated parallelograms, exploded modular blocks or connected facets with consistent isometric angles. Center one diagram in each media area.

### Illuminated directory ending

**Use:** Signature footer atmosphere.

**Observed:** The footer starts near black, then blooms into cyan at the lower left, blue through the middle and violet at the lower right. White and gray lists sit directly over the grainy light, divided by faint horizontal rules. Small monochrome assurance marks close the right edge of the company-information row.

**Transfer:** Recreate the light field behind useful navigation, keeping the upper area dark and text readable. Use genuine assurance marks only where applicable; otherwise close with neutral utility links.

**Build:** Reuse the Atmospheric product opening gradient layers but anchor all bright ellipses near the bottom edge of a roughly 1039px footer. Overlay content above the light with 82px side padding, 60px band padding and white 0.08 alpha rules.

### Editorial thumbnails

**Only for:** resource and editorial sections

**Use:** Three-column article previews.

**Observed:** Wide 411×236px thumbnails use deep navy and electric violet, bold white topic text and floating miniature panels or icons; article title and gray summary sit beneath on the black canvas.

**Transfer:** Keep graphics in the product's visual world and give the actual article title priority below the image.

### Icons

**Observed:** Small gray outline chevrons use round caps: 16px with 1.6–1.8px strokes; tiny navigation dropdown marks are 10×6px with 1.5px strokes. Feature badges contain simple pale solid symbols in dark rounded squares; platform icons on white actions are dark and 22px in the opening or 29px in the conversion stage.

**Transfer:** Use one consistent rounded icon family, with restrained solid feature symbols and light outline navigational marks. Keep icons subordinate to titles.

## Section recipes

How recurring sections are built.

### First screen: Luminous product opening

**Observed:** A 69px Fixed navigation overlays a dark-to-blue-violet atmosphere. The content begins with 176px top padding and 82px side gutters. A left-aligned display promise continues in a 0.6-opacity span at the same 60px scale, wrapping as a broad two-to-three-line block across most of the available width. One Primary button follows. After 76px, the desktop interface appears at 1202px wide with a 20px radius, while a roughly 380px-wide tall mobile device overlaps its right edge. Within the first 900px, the full promise and action are visible plus the upper portion of the product scene; the lower device and stage continue below the fold. Layers run from atmospheric field to desktop window to overlapping mobile device, with the fixed header above all.

**Transfer:** Open with a plain category promise and a dimmer run of short benefits. Use an original workflow window plus companion detail if no device photography exists. Platform-specific pages instead center the display title, add a smaller two-line support statement, center the action and place one large laptop view below.

**Avoid:** Do not center the default opening, shrink its continuation into ordinary body text, or fit the whole device composition into the first screen.

**Text style:** `display` — Overused Grotesk 500 · 60px/1 · tracking -0.01em

### Capability stage cluster

**Observed:** Luminous demonstration panels combine a full-width stage with two portrait stages, separated by 26px. Stage labels sit above stage-heading titles; stage-body explanations and Stage detail links occupy the lower text area. Wide panels use a 440px copy column and an oversized product window at right.

**Transfer:** Group related capabilities into image-led stages; vary the full-width versus paired arrangement according to the story.

**Text style:** `stage-heading` — Overused Grotesk 500 · 42px/1 · tracking -0.01em

### Heading and support pair

**Observed:** A heading sits 12px above a muted lead, followed by roughly 52–62px before a card or illustration grid. Default chapters use 120px top and bottom padding.

**Transfer:** Use a concrete outcome as the heading and a short explanation of the mechanism below.

**Text style:** `heading` — Overused Grotesk 500 · 46px/1 · tracking -0.01em

### Bottom-lit capability trio

**Observed:** Three Luminous feature cards sit under a chapter title, using 20px gaps and equal widths. Small controls occupy the upper edge while large translucent metaphors fill the lower half.

**Transfer:** Use for a compact family of distinct benefits; retain the illustration-led hierarchy and low-key colored light.

**Text style:** `card-heading` — Overused Grotesk 500 · 26px/1 · tracking -0.02em

### Feature detail chapters

**Observed:** A 406px copy column on black faces a large blue-backed vignette. Small icon, heading and muted lead stack with 28px gaps; tall repeated scenes create long black pauses between explanations.

**Transfer:** Explain one interaction at a time, retaining the text-left, object-right relationship rather than building a dense card wall.

**Text style:** `heading` — Overused Grotesk 500 · 46px/1 · tracking -0.01em

### Quantified comb proof

**Observed:** The chapter heading shares a line with Comparison tabs. Comparison rows begin about 70px below, each with a label, Segmented comparison and numeric result. A dim methodology note follows below the group.

**Transfer:** Use for evidence that benefits from repeated comparisons or measured outcomes; keep all rows aligned to the same meter length.

**Text style:** `result-leading` — Overused Grotesk 500 · 42px/0.8

### Diagram benefits and trust matrix

**Observed:** A three-column diagram section uses 384×280px wireframes above item headings and gray body text, with vertical hairlines. A separate trust section uses the Ruled trust grid for four icon-and-text cells.

**Transfer:** Use diagrams for conceptual foundations and the ruled matrix for concise operational assurances.

**Text style:** `item-heading` — Overused Grotesk 500 · 24px/1 · tracking -0.02em

### Centered conversion beacon

**Observed:** A 124px rounded product emblem sits above a centered display headline, with a pair of Conversion buttons below and muted availability text underneath. Conversion glow rises from below; a 1px lavender gradient rule terminates the stage.

**Transfer:** Return to one clear action and one useful alternative. Replace platform availability with the relevant practical reassurance for the product.

**Text style:** `display` — Overused Grotesk 500 · 60px/1 · tracking -0.01em

### Questions beside a human contact

**Observed:** The heading and short contact invitation occupy the left column; eight Question rows form a 704px-wide list on the right. A generous black pause separates this utility block from the directory ending.

**Transfer:** Use real buying or usage objections and one clear contact route rather than promotional claims disguised as questions.

**Text style:** `heading` — Overused Grotesk 500 · 46px/1 · tracking -0.01em

### Luminous directory close

**Observed:** A large linked brand lockup and social buttons occupy the left of the upper tier, with primary navigation groups at right. A lower four-column resource directory follows between white 0.08 alpha rules. Final company information aligns left and small assurance marks align right. The entire roughly 1039px footer brightens toward its lower cyan–violet edge.

**Transfer:** End with a useful navigation landscape, not a second hero. Scale the groups to available content while preserving two tiers, horizontal separators and bottom illumination.

**Text style:** `directory-heading` — Overused Grotesk 600 · 22px/1 · tracking -0.03em

### Platform onboarding

**Only for:** platform-specific landing pages

**Observed:** Four compact overview columns introduce benefits; later, three Instruction cards clarify setup. Chapters use 64px vertical padding instead of the default 120px.

**Transfer:** Use this denser variant for task-oriented acquisition pages where compatibility and next steps matter.

## Page flow

**Storyline:** promise → tangible product demonstration → capability and foundation chapters → quantified proof → conversion beacon → objections → illuminated navigation close

### Broad product marketing with room for discovery

1. **Promise** — Large two-tone sentence-case headline and overlapping multi-device product view.
2. **Product demonstration** — Wide and paired luminous capability stages.
3. **Capability chapters** — Bottom-lit cards, long feature vignettes and wireframe principles.
4. **Quantified proof** — Tabbed segmented comparison meters and method note.
5. **Trust and exploration** — Ruled assurance cells and illustrated editorial previews.
6. **Closing call** — Centered emblem, luminous action pair and practical reassurance.
7. **Objection handling** — Split question block with human contact route.
8. **Navigation close** — Two-tier illuminated directory and company row.

**Transfer:** Use the default expansive rhythm for a flagship product; select chapters that establish the new product's mechanism and credibility without reproducing a fixed section count.

### Focused platform acquisition and setup

1. **Promise** — Centered platform title, concise support line, action and large laptop.
2. **Benefit overview** — Four compact media-led columns.
3. **Product demonstration** — Successive full-width luminous panels.
4. **Quantified proof** — Comparison meters with a method note and deeper comparison link.
5. **Activation guidance** — Three numbered illustrated setup cards.
6. **Closing call** — Shared conversion beacon.
7. **Objection handling** — Questions tailored to compatibility and installation.
8. **Navigation close** — Shared illuminated directory ending.

**Transfer:** For a narrow audience or platform, compress the rhythm to 64px chapter padding, center the opening and add explicit setup guidance while retaining the core luminous stage language.

## Writing

Confident and practical, with friendly consumer-software simplicity. Benefits arrive first, then concrete descriptions of what the product actually does.

**Do not copy:** Do not reuse Sigma names, logos, product-interface assets, article titles, benchmark values, competitor claims, security certifications or privacy promises. Source phrases are structural examples, not claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your. Use we for deliberate product decisions, and name the product when explaining its mechanism.
- **Rhythm:** Short sentence-case headings alternate with explanatory paragraphs. Three clipped benefit statements can form a rhythmic headline continuation; body copy uses direct verbs and occasional em dashes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product category plainly, then follow with a same-scale run of short benefits. | One short statement plus three clipped benefits. | “[Brand] is a private AI browser.”<br>“Impressively light. Packed with features. Fast by design.” |
| Capability title | State an outcome or a tight sequence of verbs. | 2–5 words. | “Your work, handled”<br>“Ask. Research. Create” |
| Mechanism explanation | Lead with a concrete user action, then explain the immediate result. | 2–3 direct sentences. | “Turn any site into a conversation. Ask questions, get instant summaries, and explore the content without leaving the page” |
| Primary action | Verb plus destination or platform, not an abstract invitation. | 2–4 words. | “Download for macOS” |
| Reassurance | Make the default behavior simple and tangible. | 3–8 words. | “Private by default”<br>“Your browsing stays on your Mac.” |
| Question | Use the reader's literal practical concern. | One clear question. | “How do I change my default browser on a Mac?” |

**Words and phrasing to use:** built-in; by default; your work; on your device; in seconds; handled; ask; create; keep; get things done

**Avoid:** revolutionary; disruptive; unlock limitless potential; next-generation ecosystem; synergy; enterprise transformation

**Rules:**

- Pair benefits with visible mechanisms or examples.
- Keep actions literal and specific to the next step.
- Explain comparisons with a method note rather than relying on a large number alone.
- Use technical terms only where they make a concrete user benefit more credible.
- Write contact invitations as useful help, not brand banter.

## Do's and Don'ts

### Do

- Keep display headlines at 60px/1 and weight 500, with a dimmer same-scale continuation.
- Use 82px desktop gutters to align the header, chapters and footer.
- Separate default chapters with 120px vertical padding.
- Give luminous panel copy a 32px inset and a 42px benefit headline.
- Maintain 20px gaps in equal three-column card grids.
- Use 6×28px segments and 7px gaps for the signature proof meter.
- Repeat the blue–violet atmosphere at both the opening and directory ending.
- Preserve white 0.08–0.12 alpha hairlines instead of heavy gray card outlines.

### Don't

- Do not replace medium-weight grotesk headlines with extra-bold geometric display type.
- Do not make all actions fully pill-shaped; keep the 10px, 18px and 25px radius hierarchy.
- Do not color ordinary headings violet; white carries the hierarchy.
- Do not use #aaaaaa for the main promise; dim only its continuation through opacity.
- Do not put every trust statement inside a separate raised card; retain the shared ruled matrix.
- Do not use conventional solid horizontal bars in place of the segmented proof texture.
- Do not treat all page types as equally spacious; task-focused pages use 64px chapter padding.
- Do not end on a plain black legal strip; the directory's lower light field is part of the visual identity.

## Motion and responsive

### Motion

**Observed:**

- Compact actions declare 0.2s ease-out transitions with hover scale(1.05) and active scale(0.97).
- Large actions use hover scale(1.03) and active scale(0.97).
- Comparison tabs declare 0.3s cubic-bezier(0.25, 0.46, 0.45, 0.94) with hover scale(1.03) and active scale(0.97).

**Transfer:**

- Keep interaction feedback as small scale changes on controls, not large shifts in the content layout.
- Keep expanded feature explanations inside their original card footprint.

**Unknown:**

- Card face-change timing, scroll-scene choreography and focus-visible appearance are not established.

### Responsive

**Observed:**

- CSS includes width breakpoints at 479px, 480px, 767px, 768px, 991px, 1440px and 1920px.
- The base text declares font-size: 1.11111vw; complete role-level viewport scaling is not established.

**Transfer:**

- On narrow screens, prioritize the headline and action before the product scene; let the companion device reduce in scale rather than obscure the workflow.
- Stack the wide demonstration panel's text and media while retaining its colored backing and clipped window edges.
- Collapse card and footer grids into readable stacks; preserve the meter's segment texture with a shorter visible strip rather than horizontal overflow.

**Unknown:**

- Mobile typography, gutter sizes, navigation behavior and precise column-collapse rules are not established; narrow-screen arrangements above are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
