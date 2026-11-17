# Notion — work with a wink

## Overview

An approachable software style that pairs oversized, tightly packed grotesk headlines with small, practical interface text. The mostly white and warm-gray world is punctuated by blue actions, pastel tokens, black line-drawn characters and richly tinted customer portraits. It suits collaborative tools and complex products that want to feel useful rather than intimidating, with airy page compositions surrounding dense, believable product demonstrations.

### Essentials

- A serious promise gets a playful interruption: centered 96px/100px weight-600 headlines with -4.6px tracking incorporate a rounded pastel word token, set at 72px/1.21 weight 500.
- The product arrives before the pitch becomes long: a centered two-line promise, 20px/28px support and paired 38px-high actions lead into a roughly 960px-wide interface stage that extends beyond the first screen.
- Conversion controls are compact rectangles, not oversized pills: 8px corners, 16px/24px weight-500 text, 6px 15px padding and a 16px gap between blue primary and pale-blue secondary actions.
- Color behaves like a small cast of characters against paper: white and #f9f9f8 dominate the default layout; #0075de marks actions, pastel tokens interrupt type, and saturated red, blue and yellow are concentrated into a three-card proof row rather than broad decorative bands.
- The software has human company: fine black line drawings peek around a softly elevated interface, while 12px-rounded feature panels frame cropped, overlapping product fragments. Include a small original line-drawn companion and a tangible interface demonstration; a simplified document or workflow mockup is the fallback.
- Proof changes material: 394px × 492px portrait cards use colored screen/multiply layers and white 18px/28px serif quotations, followed by small inline icon-and-stat statements rather than giant numerals.
- The last invitation is unusually unhurried: a full-width #f6f5f4 closing band is 630px tall on desktop, carrying only a 42px/48px heading and two compact actions, before a white multi-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#0075de` | `--color-action` | action, link, accent | Primary buttons, links and focus outlines. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale action blue | `#e6f3fe` | `--color-secondary` | surface, action | Secondary conversion buttons. |
| Deep action blue | `#005bab` | `--color-link-dark` | text, link, action | Secondary action text and compact-button hover; also the blue multiply layer for portrait proof. |
| Word-token lavender | `#eadbfa` | `--color-lavender` | surface | Pastel inline word token; other token colors can change with the word. |
| Portrait red light | `#f64932` | `--color-portrait-red` | accent | Screen layer at 0.42 opacity over portrait photography; also small circular feature icons. |
| Portrait red depth | `#e32d14` | `--color-portrait-red-dark` | accent | Multiply layer at 0.8 opacity over red portrait proof. |
| Portrait blue light | `#097fe8` | `--color-portrait-blue` | accent, link | Screen layer at 0.42 opacity over blue portrait proof and small feature icons. |
| Portrait yellow light | `#ffb110` | `--color-portrait-yellow` | accent | Screen layer at 0.42 opacity over yellow portrait proof and small feature icons. |
| Portrait yellow depth | `#e89d01` | `--color-portrait-yellow-dark` | accent | Multiply layer at 0.8 opacity over yellow portrait proof. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Default page and interface canvas; reversed text on colored portraits and technical bands. |
| Almost-white panel | `#f9f9f8` | `--color-panel` | surface | Large product feature backings. |
| Warm gray | `#f6f5f4` | `--color-warm` | background, surface, border | Closing band, feature panels on standalone product pages and soft plan outlines. |
| Hairline gray | `#e6e6e6` | `--color-rule` | border | Black at 0.1 alpha over white for compact cards, FAQ dividers and footer separators. |
| Context gray | `#757575` | `--color-muted` | text | Captions, attribution and footer labels; black at 0.54 alpha over white. |
| Reading ink | `#1a1a1a` | `--color-text` | text | Body, navigation and ordinary headings; black at 0.898 alpha on white. |
| Headline ink | `#0d0d0d` | `--color-ink` | text | Primary display and major section headings; black at 0.95 alpha over white. |
| Solid black | `#000000` | `--color-black` | text, surface | Feature-card titles, line art and circular arrow controls. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Recommended-plan blue | `#f2f9ff` | `--color-pricing-wash` | surface | A continuous pale blue backing for the advanced plan family. |
| developer-oriented pages | Technical ultramarine | `#1313ba` | `--color-technical-blue` | background, text, border | Full hero and footer fields, technical headings, diagrams and terminal strips. |
| developer-oriented pages | Technical lavender paper | `#f6f6fc` | `--color-technical-paper` | background, surface | Broad technical capability backdrop and tinted demonstrations. |
| developer-oriented pages | Technical body blue | `#6363d1` | `--color-technical-muted` | text, border | Ultramarine at 0.66 alpha over white for supporting paragraphs and dashed connectors. |
| developer-oriented pages | Code lavender gray | `#7171a8` | `--color-code-muted` | text | Code text on light technical panels. |
| developer-oriented pages | Technical panel edge | `#e8e8f8` | `--color-technical-edge` | border | Visible lavender edge from rgba(203, 203, 239, 0.44) over white. |
| standalone utility-product pages | Mint tile | `#ddfcfa` | `--color-tile-mint` | surface | Small floating illustrated tokens. |
| standalone utility-product pages | Teal tile edge | `#03c1ba` | `--color-tile-teal` | border, accent | Left stripe and line drawing on mint tokens. |
| standalone utility-product pages | Peach tile | `#ffe9d3` | `--color-tile-peach` | surface | Small floating illustrated tokens. |
| standalone utility-product pages | Orange tile edge | `#ff6522` | `--color-tile-orange` | border, accent | Left stripe and drawing on peach tokens. |
| standalone utility-product pages | Lilac tile | `#f7e5ff` | `--color-tile-purple` | surface | Small floating illustrated tokens. |
| standalone utility-product pages | Violet tile edge | `#a361ff` | `--color-tile-violet` | border, accent | Left stripe and drawing on lilac tokens. |

## Typography

- **NotionInter** — All marketing headlines, navigation, body and actions. Neutral high-x-height grotesk; large text becomes tightly fitted and bold, small text stays practical. OpenType features: "lnum", "locl" 0. If unavailable, use **Inter**. Use weights 400–700 and preserve the tight display tracking. Font stack: "NotionInter", Inter, -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif.
- **Lyon Text** — Customer quotations and the footer's short editorial thought. Bookish serif with moderate contrast, bringing a human editorial register into the software layout. If unavailable, use **Lora**. Use regular 400; preserve narrow quotation measures. Font stack: "Lyon Text", "Lora", Georgia, serif.
- **iA Writer Mono** (only for developer-oriented pages) — Code, command strips, bracketed navigation and diagram labels. Plain writerly monospace that reads like working tooling, not futuristic display lettering. If unavailable, use **IBM Plex Mono**. Font stack: "iA Writer Mono", "IBM Plex Mono", Menlo, Courier, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | NotionInter | 600 | 96px | 100px | -4.6px | size clamp(42px, -25.5px + 11.25vw, 96px), line height clamp(48px, -17px + 10.8333vw, 100px), tracking clamp(-4.6px, 2.4px - 0.645833vw, -1.5px) | Default centered marketing promise, usually in two broad lines. |
| word-token | NotionInter | 500 | 72px | 1.21 | -0.0278em | fixed | A short action word nested into the oversized promise. |
| heading-lg | NotionInter | 700 | 54px | 56px | -0.0347em, features "lnum", "locl" 0 | fixed | Left-aligned major chapter titles and proof headings. |
| heading | NotionInter | 700 | 42px | 48px | -0.0357em, features "lnum", "locl" 0 | fixed | Closing invitation; centered benefit chapters on standalone utility-product pages. |
| card-title | NotionInter | 700 | 22px | 28px | -0.0114em, features "lnum", "locl" 0 | fixed | Feature-card result statement and plan name or price. |
| deck | NotionInter | 400 | 20px | 1.4 | -0.006em, features "lnum", "locl" 0 | fixed | One-line supporting explanation below the main promise. |
| portrait-quote | Lyon Text | 400 | 18px | 28px | normal | fixed | White customer quotations within tinted portrait cards. |
| body | NotionInter | 400 | 16px | 1.5 | normal, features "lnum", "locl" 0 | fixed | Supporting paragraphs and explanatory answers. |
| body-strong | NotionInter | 700 | 16px | 1.5 | normal, features "lnum", "locl" 0 | fixed | Compact use-case tile labels. |
| button | NotionInter | 500 | 16px | 1.5 | normal, features "lnum", "locl" 0 | fixed | Hero and closing conversion actions. |
| footer-thought | Lyon Text | 400 | 16px | 1.5 | normal, features "liga", "lnum", "locl" 0 | fixed | Short two-line editorial statement beneath the footer identity. |
| navigation | NotionInter | 500 | 14px | 20px | normal | fixed | Global navigation, footer links and compact actions. |
| caption | NotionInter | 400 | 14px | 20px | normal, features "lnum", "locl" 0 | fixed | Sentence-case card eyebrows, proof context and attributions. |
| footer-label | NotionInter | 500 | 12px | 16px | 0.01em, features "lnum", "locl" 0 | fixed | Muted footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| standalone product, developer and pricing pages | product-display | NotionInter | 700 | 64px | 1 | -0.0332em | fixed | Short centered product promise or left-aligned pricing promise. |
| pricing and company-story pages | group-heading | NotionInter | 700 | 32px | 1.25 | -0.0234em, features "lnum", "locl" 0 | fixed | Plan-family promises and late editorial section headings. |
| pricing pages | editorial-quote | Lyon Text | 400 | 32px | 1.25 | normal, features "liga", "lnum", "locl" 0 | fixed | A freestanding testimonial below the simpler plan family. |
| standalone product and developer pages | feature-heading | NotionInter | 700 | 18px | 28px | -0.007em | fixed | Small benefit headings above demonstrations. |
| question-and-answer sections | faq-question | NotionInter | 600 | 16px | 1.5 | normal | fixed | Single-line collapsed question. |
| pricing comparison tables | comparison | NotionInter | 400 | 15px | 20px | normal | fixed | Plan-cell values and explanatory text. |
| pricing comparison tables | comparison-label | NotionInter | 600 | 15px | 20px | normal | fixed | Underlined feature labels with explanatory affordances. |
| developer-oriented pages | technical-mono | iA Writer Mono | 400 | 14px | 20px | -0.009em | fixed | Commands, code and technical navigation. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display tracking is dramatically tighter than body tracking; do not spread the large headline to make it feel luxurious.
- Sentence case is the norm even for eyebrows and navigation. The card eyebrow is quieter and smaller than the result statement below it.
- Serif is a change of speaker, not an alternate heading style. Reserve it for testimony and a small editorial footer note.

## Layout

**Density:** Airy outer composition with compact controls and dense, credible product views.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-card-title spacing and gaps within compact tile rows. |
| 12px | Headline-to-deck spacing and small content group gaps. |
| 16px | Paired action gap and heading-to-paragraph spacing. |
| 20px | Deck-to-actions spacing. |
| 24px | Default card padding and feature-grid gutters. |
| 32px | Chapter-title-to-grid spacing; wider product and plan interior padding. |
| 64px | Utility hero top and bottom padding; closing-band minimum interior padding. |
| 80px | Hero opening inset, technical chapter spacing and footer top padding. |
| 96px | Major marketing chapter top and bottom breathing room. |
| 140px | Only for company-story pages: separation between illustrated editorial story rows. |

### Containers and grids

- **Marketing content**: max width 1252px · side padding 64px. Centered broad content frame. At desktop, feature and proof chapters have about 106px side margins and approximately 1229px of actual content.
- **Hero product stage**: max width 960px. Centered interface beneath the hero copy, narrower than the headline frame.
- **Feature bento**: 2 columns · gap 24px. Two equal feature cards followed by a full-width horizontal demonstration; shift emphasis through the image rather than different card colors.
- **Compact use cases**: 5 columns · gap 8px. A single desktop row of compact navigation tiles.
- **Portrait proof**: 3 columns · gap 24px. Equal-height portrait cards with a small stat strip beneath.
- **Footer columns**: 4 columns · gap 24px. Four link columns occupy the right two thirds; identity and serif thought occupy the left third.
- **Utility content** (only for standalone utility-product pages): max width 1024px · gap 24px. Large full-width demonstrations alternate with two- and three-column feature grids.
- **Technical and pricing content** (only for developer and pricing pages): max width 1190px · side padding 125px. Desktop frame for technical demonstrations, plan families and comparison rows.
- **Editorial story** (only for company-story pages): max width 940px · 2 columns · gap 40px. 450px-wide illustrated column paired with short, top-aligned reading text.
- **FAQ measure** (only for question-and-answer sections): max width 800px. A narrow left-aligned accordion under a larger chapter heading.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions | 8px |
|  | Feature and portrait cards | 12px |
|  | Navigation hit area | 4px |
|  | Inline word and locale selector | 9999px (pill) |
| developer-oriented pages | Technical panels | 4px |
| standalone utility-product pages | Floating illustrated tokens | 6.5px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Paper elevation | `0px 0.2px 1px 0px rgba(0,0,0,0.01), 0px 0.8px 2.9px 0px rgba(0,0,0,0.02), 0px 2px 7.8px 0px rgba(0,0,0,0.027), 0px 4px 18px 0px rgba(0,0,0,0.04)` | Soft separation of white interface fragments from pale backing, not a dramatic floating-card effect. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page field.

**CSS:** `background: #ffffff; color: #1a1a1a`

#### Feature backing · level 1

**Use:** Product-led benefit panels.

**CSS:** `background: #f9f9f8; border-radius: 12px; overflow: hidden`

**Observed:** The backing visually joins the text header and illustration area. Standalone utility panels use warm gray instead.

**Transfer:** Keep backing nearly neutral so the interface remains the visual event.

#### White interface sheet · level 2

**Use:** Overlapping interface fragments.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: 0px 0.2px 1px 0px rgba(0,0,0,0.01), 0px 0.8px 2.9px 0px rgba(0,0,0,0.02), 0px 2px 7.8px 0px rgba(0,0,0,0.027), 0px 4px 18px 0px rgba(0,0,0,0.04)`

**Observed:** Sheets are cropped by their surrounding panel and can have only their top corners visible.

**Transfer:** Show a few legible, useful interface details rather than many tiny illegible windows.

#### Closing field · level 0

**Use:** Quiet final conversion section.

**CSS:** `background: #f6f5f4; padding: 64px 32px`

**Observed:** A tall empty field surrounds a very compact message and action group.

**Transfer:** Treat spare area as deliberate breathing space.

#### Portrait legibility layer · level 2

**Use:** Shade under white quotation copy.

**CSS:** `background: linear-gradient(rgba(0, 0, 0, 0) 35%, rgba(0, 0, 0, 0.55) 100%)`

#### Plan wash · level 1

**Only for:** pricing pages

**Use:** More capable plan family.

**CSS:** `background: #f2f9ff; border-radius: 12px; padding: 32px`

**Observed:** The pale field continues through the feature list; the simpler family stays white with a warm-gray 2px edge.

#### Technical field · level 0

**Only for:** developer-oriented pages

**Use:** Technical hero, terminals and playful footer.

**CSS:** `background: #1313ba; color: #ffffff`

**Observed:** Hero and footer reverse to white; intervening capability fields use pale lavender and ultramarine text.

#### Technical paper · level 1

**Only for:** developer-oriented pages

**Use:** Light technical capability areas and diagrams.

**CSS:** `background: #f6f6fc; color: #1313ba`

#### Technical outline · level 2

**Only for:** developer-oriented pages

**Use:** Code and tool panels.

**CSS:** `background: #ffffff; border: 1px solid rgba(203, 203, 239, 0.44); border-radius: 4px`

## Components

### Global navigation

**Use:** Persistent orientation and compact conversion access.

**CSS:** `position: sticky; top: 0px; height: 64px; background: #ffffff; z-index: 100; padding: 14px 24px; display: grid; grid-template-columns: 1fr auto 1fr; gap: 16px; align-items: center`

**Text style:** `navigation` — NotionInter 500 · 14px/20px

**Observed:** Small identity mark at left, sparse central links and dropdown chevrons, login and a smaller primary action at right. Technical variant replaces ordinary links with bracketed mono shortcuts and reverses over its colored hero.

**Transfer:** Keep the central list short; use the same compact text scale rather than a large app-style toolbar.

### Navigation link

**Use:** Header and compact menu actions.

**CSS:** `border-radius: 4px; padding: 5px 10px; display: flex; gap: 8px; align-items: center`

**Text style:** `navigation` — NotionInter 500 · 14px/20px

**Observed:** A small downward chevron follows expandable labels; standalone links share the same hit-area construction.

**States:** Declared: hover background rgba(0,0,0,0.05), text rgba(0,0,0,0.898); focus-visible outline-color #0075de.

### Primary button

**Use:** Main marketing conversion action.

**CSS:** `background: #0075de; color: #ffffff; border: 1px solid transparent; border-radius: 8px; padding: 6px 15px; height: 38px; display: flex; justify-content: center; align-items: center`

**Text style:** `button` — NotionInter 500 · 16px/1.5

**Observed:** Paired actions have equal width, about 156px in the opening. Header actions use the navigation recipe and 36px height. Utility-product pages use a near-black primary instead; pricing rows use compact blue controls.

**States:** Declared: hover background rgba(0,0,0,0.75); focus-visible background rgba(0,0,0,0.75), outline-color #0075de; active background rgba(0,0,0,0.898).

### Secondary button

**Use:** Assisted conversion beside the self-serve action.

**CSS:** `background: #e6f3fe; color: #005bab; border: 1px solid transparent; border-radius: 8px; padding: 6px 15px; height: 38px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — NotionInter 500 · 16px/1.5

**Observed:** Matches the primary's size without competing for contrast. In the closing field the backing becomes white.

**States:** Declared: hover background rgba(255,255,255,0.75), text #000000; focus-visible background rgba(255,255,255,0.75), outline-color #0075de; active background rgba(255,255,255,0.66).

### Inline word token

**Use:** Playful action-word interruption within the default hero.

**CSS:** `background: #eadbfa; border-radius: 9999px; padding: 8px 28px; display: inline-flex; align-items: baseline; gap: 12px`

**Text style:** `word-token` — NotionInter 500 · 72px/1.21 · tracking -0.0278em

**Observed:** A colored circular dot precedes one short verb. The capsule is slightly taller than the adjacent text line; changing words change its width and tint.

**Transfer:** Use a meaningful verb that completes the promise, not a promotion label.

### Feature bento card

**Use:** Show one outcome and the product mechanism that makes it possible.

**CSS:** `background: #f9f9f8; border-radius: 12px; overflow: hidden; position: relative`

**Text style:** `card-title` — NotionInter 700 · 22px/28px · tracking -0.0114em

**Observed:** A 24px-padded header contains caption, title and a black 32px circular arrow; a large product montage fills the remaining area. Two tall cards lead into a wider horizontal panel.

**Transfer:** Keep one claim per card and make the demonstration directly substantiate it.

### Compact use-case tile

**Use:** Link a broad product to concrete applications.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.1); border-radius: 12px; padding: 24px; display: flex; flex-wrap: wrap; gap: 16px`

**Text style:** `body-strong` — NotionInter 700 · 16px/1.5

**Observed:** A 40px colored circular pictogram precedes a short title and inline arrow. Desktop tiles are about 239px × 161px, five across.

### Portrait proof card

**Use:** Let a real user carry the claim.

**CSS:** `border-radius: 12px; overflow: hidden; position: relative; display: grid; color: #ffffff`

**Text style:** `portrait-quote` — Lyon Text 400 · 18px/28px

**Observed:** Full-bleed portrait, colored layers and Portrait legibility layer sit behind a 24px-padded content layer. Identity sits at top; quote and 14px sans attribution sit at bottom.

**States:** Declared: hover soft paper box-shadow; focus-visible the same shadow and outline-color #0075de.

**Transfer:** Use real permissioned testimony; maintain the same framing and treatment across the row.

### Footer

**Use:** End with a human note and practical routes onward.

**CSS:** `background: #ffffff; padding: 80px 0px 24px`

**Text style:** `navigation` — NotionInter 500 · 14px/20px

**Observed:** Identity and a two-line serif thought sit at left. Four link columns sit at right under muted 12px labels. Copyright, privacy controls and a bordered pill locale selector complete a lower row; other page types add a top hairline.

**Transfer:** Use a short original statement about the product's philosophy rather than another oversized sales pitch.

### FAQ row

**Only for:** question-and-answer sections

**Use:** Address adoption and purchase objections.

**CSS:** `border-bottom: 1px solid rgba(0,0,0,0.1); max-width: 800px`

**Text style:** `faq-question` — NotionInter 600 · 16px/1.5

**Observed:** A 56px-high collapsed summary has text at left and a small plus at right. The group has a top hairline; expanded answers use body text with 16px bottom padding.

**States:** Declared: hover unspecified; focus-visible outline-color #0075de.

### Plan family

**Only for:** pricing pages

**Use:** Organize four tiers into two understandable product families.

**CSS:** `background: #f2f9ff; border-radius: 12px; padding: 32px; display: grid; gap: 32px`

**Text style:** `group-heading` — NotionInter 700 · 32px/1.25 · tracking -0.0234em

**Observed:** Two families sit side by side; each contains two plan columns. The advanced family has the blue wash, a recommended tag and stronger primary CTA; the simpler family is white with a 2px warm-gray outline. Prices stay at 22px, not giant display numerals.

### Technical command strip

**Only for:** developer-oriented pages

**Use:** Offer an immediate working entry point.

**CSS:** `background: #ffffff; color: #1313ba; padding: 8px 16px; border-radius: 0px; display: flex; align-items: center; gap: 12px`

**Text style:** `technical-mono` — iA Writer Mono 400 · 14px/20px · tracking -0.009em

**Observed:** One line of command text ends in a copy icon, with a quieter documentation line below. Repeated in hero and technical footer; light sections can invert the strip to ultramarine.

## Imagery and graphics

### Software stage with line-drawn companions

**Use:** Default hero and product-led feature chapters.

**Observed:** A pale, front-facing desktop workspace dominates the stage, with light browser chrome, soft borders and tiny pastel status details. Small black-and-white faces or figures peek from behind its edges; they do not turn the whole scene into an illustration.

**Transfer:** Create one accurate central workflow view for the new product. If no finished interface exists, make a restrained document/list mockup with real labels and one clear active state, then add an original small line-drawn companion.

**Build:** Use a centered white interface sheet around 960px wide with an 8px hero edge and fine gray border. Behind two opposite edges place small SVG figures: open black paths for face and limbs, white fill, solid black hair or clothing, no colored shadows or gradients. Keep drawing line widths visually around 2px and figures much smaller than the interface.

### Feature interface collage

**Use:** Inside Feature bento card and utility-product panels.

**Observed:** Readable product fragments overlap on near-white or warm-gray backing: lists, a document, a chart, a prompt or result bubble. White cards have subtle layered shadows; edges fade softly or are clipped at the outer panel. Utility scenes sometimes include laptop and phone hardware with black bezels.

**Transfer:** Build a few purposeful layers around the product's input and output. Keep interface colors muted, with only the active point of interest saturated.

### Duotone portrait testimony

**Use:** Distinctive colorful proof row.

**Observed:** Close head-and-shoulders portraits fill equal 394px × 492px rounded cards. Red, blue and golden-yellow treatments preserve recognizable faces and texture. White identity marks sit above serif quotations; the lower image darkens strongly.

**Transfer:** Use consistently framed customer or practitioner portraits, not generic lifestyle scenes. If portrait assets are unavailable, commission simple monochrome face illustrations and retain the colored card treatment and quotation layout.

**Build:** Within an isolated 12px-rounded wrapper, cover-fit a neutral portrait. Add an inset screen-blend layer at opacity 0.42 using #f64932, #097fe8 or #ffb110, then an inset multiply layer at opacity 0.8 using #e32d14, #005bab or #e89d01. Add Portrait legibility layer above both and text above all layers.

### Floating illustrated tiles

**Only for:** standalone utility-product pages

**Use:** Scatter small product-metaphor tokens around short centered chapter headings.

**Observed:** Small pastel rectangular tiles with a saturated left stripe carry thin, friendly drawings of everyday objects and tasks. Tokens occupy the margins, leaving the centered copy readable; some are clipped at section edges.

**Transfer:** Choose simple metaphors for the new product's daily uses and keep the tokens secondary to the message.

**Build:** Draw 90px × 80px rectangles with 6.5px corners and a 10px left stripe. Use mint/teal, peach/orange and lilac/violet palette pairs. Place a simple same-color SVG line icon in each, with generous internal space. Arrange asymmetrically at the sides rather than in a visible grid.

### Technical diagram and connector world

**Only for:** developer-oriented pages

**Use:** Make technical capabilities feel like a connected working system.

**Observed:** Ultramarine hero reverses an interface to white/lavender lines, with pale event cards connected by right-angle dashed paths. Light chapters pair code and product output, traversed by dotted connectors and small pixel-like symbols. The final synthesis is a wide labeled architecture diagram.

**Transfer:** Make the diagram reflect actual inputs, processing and outcomes, while keeping geometry orthogonal and the palette restricted.

**Build:** Use SVG paths composed of horizontal and vertical segments, 1px dashed ultramarine at 0.66 alpha on light lavender. Add 4px-corner pale cards and small square glyph nodes at turns; invert path color on the saturated hero. Keep lines behind text and panels.

### Pixel-play closing scene

**Only for:** developer-oriented pages

**Use:** A distinctive playful ending below the practical footer controls.

**Observed:** A full-width 512px-high arcade-like world sits on ultramarine: blocky lavender clouds, a small character, a thin ground line, score labels and a centered outlined pixel title with a keyboard-start prompt.

**Transfer:** End technical pages with a small original toy or interactive visual related to the product, preserving the deliberately low-resolution aesthetic rather than a polished 3D scene.

**Build:** Draw on a low-resolution canvas or integer SVG grid and scale with crisp edges. Use translucent white/lavender blocks over Technical field; construct clouds from stepped rectangles and a ground from a horizontal line plus sparse dashes. Center a short pixel-letter title and a mono keyboard prompt; place a tiny original character near the ground.

### Illustrated editorial history

**Only for:** company-story pages

**Use:** Long-form origin, mission or explanatory story.

**Observed:** Black line-drawn people, tools and documents share a 450px-wide image column with grayscale archival photographs. Some figures overlap the photographs; thin black baselines anchor the scenes. The facing text is short, unboxed and aligned near the image top.

**Transfer:** Pair original diagrams or drawings with relevant documentary imagery. Keep the story visual and lightly humorous rather than replacing it with a corporate team-photo wall.

**Build:** Use grayscale photographs with a thin dark edge and overlay simple black-and-white SVG figures. Anchor each composition to a 2px black baseline; leave the surrounding white field unframed.

### Icons

**Observed:** Mostly small filled SVG utility marks, with 10px dropdown chevrons, 14–20px action icons, 18px comparison checks and larger 40px colored circular feature badges. Decorative character art uses outlines rather than the filled utility vocabulary.

**Transfer:** Use simple legible filled icons at action scale. Keep line-drawn character art distinct; do not replace every small icon with a colorful illustration.

## Section recipes

How recurring sections are built.

### First screen: Playful promise above a working product

**Observed:** White paper extends behind Global navigation. The copy begins 80px below the 64px header, centered across a broad content frame. Display forms two tightly packed lines, with an Inline word token interrupting the second line; the headline spans roughly two thirds of the viewport width. Deck follows after 12px, then paired Primary button and Secondary button after 20px. About 81px below the actions, a roughly 960px-wide front-facing interface stage begins, with small line-drawn companions peeking from behind. Within the first 900px the entire headline, deck and buttons are visible, together with the upper portion of the main object; the complete interface and fuller trust block continue below. A low monochrome logo strip can overlap the lower visual edge.

**Transfer:** Preserve the hierarchy of a compact verbal promise, one playful token and an immediately tangible product. If no interface exists, construct a useful document or workflow mockup instead. Utility-product openings use a small product emblem, a 64px short headline, centered narrow support and floating illustrated tiles; pricing opens left-aligned with a 64px promise and trust logos; company stories open with a muted label and a 54px editorial title; developer openings invert the product stage onto ultramarine and introduce a command strip.

**Avoid:** Do not use a split-screen text/photo hero, a full-bleed background image or a token that reads as an unrelated badge. Do not shrink the product to a thumbnail above the fold.

**Text style:** `display` — NotionInter 600 · 96px/100px · tracking -4.6px

### Outcome bento chapter

**Observed:** A left-aligned heading-lg leads by 32px into Feature bento card. Two equal columns use 24px gutters; a subsequent full-width card places text at left and layered interface output toward the right. Compact use-case tile follows in a five-item row beneath a small context label.

**Transfer:** Choose two or three distinct outcomes and support each with a specific working scene rather than a list of abstract adjectives.

**Text style:** `heading-lg` — NotionInter 700 · 54px/56px · tracking -0.0347em

### Portrait proof and quiet statistics

**Observed:** A heading-lg sits 32px above a three-column Portrait proof card row. Beneath the portraits, a horizontal strip uses muted small icons and 14px medium statements; numbers stay inline with their labels, with some portions emphasized by weight rather than giant size.

**Transfer:** Use permissioned testimony and concise, verifiable evidence. Keep statistics secondary to people, and retain one concentrated colorful proof device.

**Text style:** `heading-lg` — NotionInter 700 · 54px/56px · tracking -0.0347em

### Quiet closing invitation

**Observed:** Closing field runs full width for 630px at desktop. A centered heading and two compact actions occupy only a small portion of it, with 16px between title and actions. No additional long-form selling copy competes with the invitation.

**Transfer:** Give the reader one simple next step and one assisted alternative; keep the visual pause even when preceding content is dense.

**Text style:** `heading` — NotionInter 700 · 42px/48px · tracking -0.0357em

### Practical editorial footer

**Observed:** Footer uses a broad centered content frame, with identity and footer-thought at left, four navigation columns at right and a lower legal/locale row. The developer variant condenses these practical controls onto Technical field, repeats Technical command strip and ends in Pixel-play closing scene.

**Transfer:** Keep useful routes and the small philosophical note together; use the playful technical ending only within the technical theme.

**Text style:** `footer-thought` — Lyon Text 400 · 16px/1.5

### Utility benefit chapters

**Only for:** standalone utility-product pages

**Observed:** Centered 42px headings sit in a 750px measure, about 60px above a warm-gray full-width demonstration. Each large panel contains a small blue utility icon, an 18px bold heading and body support over the product image. Two-column smaller panels and three-column integration cards extend the chapter; illustrated tokens sit in the white margins.

**Transfer:** Alternate broad demonstrations with smaller supporting benefits. Group by reader outcomes, not by every product feature.

**Text style:** `heading` — NotionInter 700 · 42px/48px · tracking -0.0357em

### Technical capability chapter

**Only for:** developer-oriented pages

**Observed:** Ultramarine heading-lg and a 560px-wide supporting paragraph lead into side-by-side code and rendered output on Technical paper. 80px vertical chapter spacing and dashed right-angle connectors unify successive demonstrations. Later chapters use three bordered cards or a two-column tool catalog, followed by a centered summary heading and wide system diagram.

**Transfer:** Show how the system works with a real input-to-output relationship, then provide docs or an executable command. Use the technical theme consistently within this page type.

**Text style:** `heading-lg` — NotionInter 700 · 54px/56px · tracking -0.0347em

### Plan selection and comparison

**Only for:** pricing pages

**Observed:** A left-aligned product-display promise and monochrome trust logos precede a small rounded billing switch. Two Plan family groups present four tiers using compact 22px prices, feature checks and short descriptions. A serif editorial quote fills the space beneath the shorter family. A heading-lg introduces a comparison matrix: a double-width label column plus four equal plan columns, 1px row rules, 15px text, 10px vertical padding and roughly 45px standard rows. Plan titles and actions remain available above the table while scrolling.

**Transfer:** Separate quick plan choice from detailed comparison. Use pale tint for the advanced family without making every tier a differently colored card.

**Text style:** `product-display` — NotionInter 700 · 64px/1 · tracking -0.0332em

### Illustrated editorial sequence

**Only for:** company-story pages

**Observed:** A 940px-wide two-column story pairs 450px illustrations and grayscale history images with short body paragraphs; rows are separated by about 140px. The ending changes to a bold attributed quotation, a ruled participation block, a three-by-two press-logo grid on warm-gray tiles and a compact email signup, then Footer.

**Transfer:** Use a narrative of problem, historical context, point of view and invitation. Illustrate each idea without forcing a product-grid layout onto the story.

**Text style:** `heading-lg` — NotionInter 700 · 54px/56px · tracking -0.0347em

### Utility download close and objections

**Only for:** standalone utility-product pages

**Observed:** A centered 42px invitation, short support and blue arrow link precede two warm-gray platform cards: desktop and mobile, each with a product image and compact platform download actions. A left-aligned question heading and FAQ row group follow, then a large white gap and a hairline-separated Footer.

**Transfer:** When delivery is platform-specific, make the close an explicit device choice rather than repeating a generic signup band.

**Text style:** `heading` — NotionInter 700 · 42px/48px · tracking -0.0357em

## Page flow

**Storyline:** Promise → tangible product → outcome chapters → credible proof → suitable next step → practical footer; comparison and objection handling expand when the purchase needs more explanation.

### Broad marketing landing page

1. **Promise** — Centered oversized headline with a changing pastel verb token and paired compact actions.
2. **Product demonstration** — Large interface stage with small line-drawn companions and monochrome trust marks.
3. **Capability chapters** — Outcome-focused bento demonstrations followed by compact application links.
4. **Social proof** — Three strongly tinted portrait testimonials and a quiet inline stat strip.
5. **Closing call** — Tall warm-gray invitation field followed by the editorial multi-column footer.

**Transfer:** Lead with a product promise, substantiate it visually and concentrate color into the proof rather than spreading it evenly.

### Technical product platform

1. **Promise** — Reversed ultramarine hero, short technical title, install command and connected interface scene.
2. **Capability chapters** — Pale technical chapters show code, output, workflow triggers and runtime behavior with dashed connector paths.
3. **Adoption paths** — Agent collaboration cards and a tool catalog offer docs, commands and availability labels.
4. **System synthesis** — Centered headline and a wide architecture diagram summarize the whole system.
5. **Closing call** — Ultramarine footer repeats the command, practical links and a low-resolution arcade scene.

**Transfer:** Use a restricted technical palette, truthful executable examples and a playful ending suited to builders.

### Standalone utility product

1. **Promise** — Emblem, short centered title and two acquisition actions surrounded by pastel illustrated tiles.
2. **Product demonstration** — Wide video framed in desktop and phone hardware.
3. **Capability chapters** — Centered outcome headings alternate with large demonstrations and smaller feature grids.
4. **Integration proof** — Compact logo-and-description tiles connect the product to familiar tools.
5. **Closing call** — Desktop and mobile platform cards make the delivery choice explicit.
6. **Objection handling** — Short FAQ, then the standard white editorial footer.

**Transfer:** Organize around a few day-to-day outcomes, then make installation or access unmistakable.

### Pricing and purchase explanation

1. **Promise** — Left-aligned compact display and trust logos.
2. **Pricing** — Billing toggle, paired plan families, recommended badge and integrated feature lists.
3. **Social proof** — A freestanding serif quote supports the plan choice.
4. **Detailed comparison** — Long ruled matrix with persistent tier actions.
5. **Objection handling** — A narrow FAQ closes with a help-center route, then the standard footer rather than a large CTA band.

**Transfer:** Provide a fast decision surface before detailed rows; keep prices compact and comparison semantics legible.

### Company story and point of view

1. **Editorial opening** — Muted contextual label and a large left-aligned story title.
2. **Narrative explanation** — Sequential paired illustrations, archival photography and conversational paragraphs.
3. **Point of view** — A brief attributed bold quotation distills the argument.
4. **Participation and credibility** — Ruled invitation section, press-logo grid and a small email signup.
5. **Ending** — Standard white footer with serif thought and practical links.

**Transfer:** Tell an illustrated origin or explanatory story rather than converting the page into feature cards; finish with ways to participate.

## Writing

Clear and useful with a confident, lightly mischievous streak. Big promises are short; support copy names concrete actions, while technical and company storytelling can become more conversational.

**Do not copy:** Do not reuse Notion names, marks, character artwork, customer logos, product-specific commands, customer quotations, user counts, rankings, prices or other claims. Use original identity, authorized assets and verifiable facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader's work, we for the maker's point of view, and the product name only when it adds clarity.
- **Rhythm:** Headlines are brief, sentence case and often punctuated with a period. Supporting lines tend to be a single practical sentence; feature descriptions are short enough to scan beside a demonstration. Longer editorial paragraphs use questions, direct address and occasional friendly asides.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A short declarative promise or familiar phrase with a small twist. | 2–9 words | “It’s time.”<br>“One tool to run your company.” |
| Supporting line | Concrete verbs explain what the user accomplishes and why the product belongs in the workflow. | 12–25 words | “Capture context, find answers, and automate tasks with AI built for your team.” |
| Chapter heading | Outcome first, sometimes a compressed three-part cadence. | 4–11 words | “AI where your team works.”<br>“Any data. Any tool. Any agent. All in [Brand].” |
| Card heading | Verb plus practical result, with a useful qualifier rather than a broad adjective. | 3–10 words | “Get answers, instantly—with citations.”<br>“See your schedule at a glance” |
| Primary action | Direct acquisition or setup verb; distinguish self-serve from assisted action. | 2–5 words | “Get [Brand] free”<br>“Request a demo”<br>“Read the docs” |
| Editorial story | Talk to the reader as a person, then use a question to open the explanation. | Short paragraphs with varied sentence lengths | “Hi there! If you’re reading this, you’re probably like me—spending most of your days in your office, in front of a computer.” |

**Words and phrasing to use:** your team; together; built for; find; bring; keep; work; tools; get started; read the docs

**Avoid:** revolutionary synergy; unprecedented paradigm; effortless magic everywhere; enterprise-grade excellence; unlock limitless potential

**Rules:**

- Anchor a benefit to a visible mechanism in the adjacent demonstration.
- Keep feature eyebrows in sentence case and name a task or category, not a marketing slogan.
- Use documentation links and availability labels plainly on technical pages.
- Keep playfulness in a concise phrase or visual gesture; let the practical sentence below do the explaining.

## Do's and Don'ts

### Do

- Keep the main promise tightly set at 96px/100px, weight 600, with a smaller pastel word interruption.
- Use 54px/56px weight-700 chapter headings above product and proof sections.
- Keep default actions at 38px high with 8px corners and a 16px paired gap.
- Use 24px card padding and 24px major grid gutters; reserve 8px gutters for compact tile rows.
- Give portraits a consistent 394px × 492px desktop proportion and bottom-aligned serif quotation.
- Keep ordinary captions at 14px/20px and footer labels at 12px/16px rather than promoting everything into a heading.
- Let the warm-gray closing field occupy 630px of desktop height while its message stays compact.
- Carry the technical theme through its diagram, command strips and playful footer instead of changing just the headline color.

### Don't

- Do not turn standard blue conversion controls into fully rounded pills; pills belong to word tokens and locale controls.
- Do not apply ultramarine full-page fields to the default marketing theme; that is a technical-page variant.
- Do not use large gradient text or glowing atmospheric backgrounds as a substitute for the product stage.
- Do not make the three proof cards three unrelated visual styles; keep identical framing and vary the duotone treatment.
- Do not enlarge plan prices beyond the compact 22px title scale just because pricing pages often do.
- Do not make the comparison table a stack of heavy bordered boxes; preserve 1px row rules and the double-width label column.
- Do not turn small captions into uppercase tracked labels; this voice uses ordinary sentence case.
- Do not use thick colorful cartoon outlines for decorative people; the illustration vocabulary is black linework with selective solid black shapes.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary marketing actions declare background-color and color transitions of 0.2s cubic-bezier(.42, 0, 1, 1). Navigation links declare a 0.15s background-color transition.
- Portrait cards declare a 0.2s box-shadow transition with cubic-bezier(0.645, 0.045, 0.355, 1).
- Utility illustrated tiles declare opacity 0.25s linear with 0.2s delay, and transform 0.5s cubic-bezier(0.25, 1, 0.33, 1) with 0.2s delay.
- Technical hero connector and tool entrances declare 0.6s cubic-bezier(0.16, 1, 0.3, 1); a technical shimmer declares 1.5s linear infinite.

**Transfer:**

- Let the word token carry the hero's playful change while keeping the surrounding promise stable.
- Use the declared understated color and shadow transitions for controls; keep technical connector entrances within the technical theme.

**Unknown:**

- Exact word-token cycle timing, scroll-trigger sequencing and the arcade interaction behavior are unspecified.

### Responsive

**Observed:**

- The main display scales from 42px to 96px with the supplied fluid formula; line height scales from 48px to 100px and tracking from -1.5px to -4.6px.
- Styles include multiple breakpoint rules around 600px, 768px, 840px, 960px, 1080px and 1200px; these are not a single unified layout switch. Compact use-case tiles declare a column layout before the wide row layout.

**Transfer:**

- Retain a centered promise and a readable inline word capsule as type shrinks; simplify the sentence before letting the token collide with adjacent text.
- Stack feature panels and compact tile navigation on narrow layouts. Scale the product stage as a coherent scene and reduce decorative companions or tokens at the margins before reducing reading text.
- For detailed comparison, preserve column relationships through a deliberate narrow-screen comparison treatment rather than compressing all four plans into unreadable text.

**Unknown:**

- Exact mobile navigation behavior, narrow-screen table treatment and all mobile illustration placements are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
