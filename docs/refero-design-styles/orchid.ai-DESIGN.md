# Orchid — dreamlike everyday delegation

## Overview

An airy, near-white editorial style that makes capable software feel personal and unhurried. Dark navy old-style serif headlines sit beside restrained grotesk text, while blurred, grainy blue-hour scenes bring a cinematic warmth to practical interface demonstrations. It suits consumer tools and human-centered services, with sparse text and richly staged moments rather than dense technical exposition.

### Essentials

- An editorial promise with a conversational turn: centered Louize at 64px/1.05, weight 500 and -0.04em tracking, with the capability phrase in matching italic.
- A small invitation above a tangible product: a 36px announcement capsule, 32px vertical gaps, a 520px support line and a centered 450px-wide device that continues below the first screen.
- Tiny pills carry the actions rather than shouting: 14px/1 medium sans, 9999px radius, 34px dark chapter actions, a 40px pale opening action and a 52px pale cinematic action.
- Color lives inside pictures, not across the canvas: #fcfcfd and #08152e govern text and page space; saturated blue, teal, orange and violet remain concentrated in rounded media occupying roughly half a feature row.
- Dream-soft surroundings support crisp software: 540×440px atmospheric panels with 24px corners hold sharp floating icons, messages or a meaningful product fragment. Use a blue-hour everyday scene with grain and bloom when bespoke art is unavailable.
- A human-scale ornament and a cinematic invitation punctuate the experience: thin rules interrupted by a short sequence of seed-like marks, plus a 16:9 image-backed call with 80px white serif type, 32px corners and a single pale pill. Reinterpret the ornament with a simple organic silhouette rather than dropping it.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight ink | `#08152e` | `--color-ink` | text, action, background | Headlines, primary actions and dark brand panels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Strong secondary | `#394357` | `--color-strong-secondary` | text | Navigation and form labels; ink at 80% over porcelain. |
| Footer gray | `#515a6c` | `--color-link` | link, text | Footer links; ink at 70% over porcelain. |
| Reading gray | `#5d6676` | `--color-body` | text | Default body text; visible result of ink at 65% over porcelain. |
| Caption gray | `#6a7181` | `--color-secondary` | text | Stat descriptions and secondary text; ink at 60% over porcelain. |
| Soft marking | `#767d8b` | `--color-muted` | text | Live label and descriptive gallery captions; ink at 55% over porcelain. |
| Hairline gray | `#e4e5e8` | `--color-rule` | border | Ink at 10% over porcelain; fine dividers and inset outlines. |
| Panel wash | `#f2f3f5` | `--color-wash` | surface | Ink at 4% over porcelain; media backing, Live capsule and expanded FAQ. |
| Cool card | `#f5f6f8` | `--color-card` | surface | Opening capsules, supporting buttons and listing cards. |
| Porcelain | `#fcfcfd` | `--color-canvas` | background, text | Default page canvas and reversed text. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#10b981` | `--color-status` | accent | The tiny 8px operational-status dot, not a general button color. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| role listing metadata | Category gray | `#8e949f` | `--color-category` | text | Ink at 45% over porcelain. |
| numbered benefits | Index gray | `#a7abb5` | `--color-index` | text | Ink at 35% over porcelain. |
| application forms | Form wash | `#f5f5f7` | `--color-form-wash` | surface | Ink at 3% over porcelain. |
| culture and recruiting pages | Benefits band | `#f7f7f9` | `--color-band` | background | Ink at 2% over porcelain. |
| product demonstrations | Message blue | `#0088ff` | `--color-message-blue` | surface | Outgoing messages inside demonstrations only. |
| product demonstrations | Message gray | `#e9e9ea` | `--color-message-gray` | surface | Incoming messages inside demonstrations only. |

## Typography

- **louize** — Display, section headings, testimonial, metrics and footer headings. Literary old-style serif with fine contrast, tapered forms and a lively italic. If unavailable, use **Cormorant Garamond**. Use 400–500; preserve tight spacing and check line breaks. Font stack: "louize", "Cormorant Garamond", ui-serif, Georgia, "Times New Roman", serif.
- **lausanne** — Body, navigation, labels and actions. Clean, open grotesk with understated medium-weight controls. If unavailable, use **Inter**. Use 400–500; keep body tracking normal. Font stack: "lausanne", "Inter", system-ui, -apple-system, "Segoe UI", sans-serif.
- **jetbrainsMono** (only for code and numbered benefits) — Code and small numerical indexes. Compact technical monospace that stays subordinate to the serif. If unavailable, use **JetBrains Mono**. Font stack: "jetbrainsMono", "JetBrains Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| metric | louize | 400 | 84px | 1 | -0.03em | fixed | Large live counters. |
| closing-display | louize | 500 | 80px | 1.05 | -0.04em | size clamp(40px, 6vw, 80px) | White headline over atmospheric closing media. |
| display | louize | 500 | 64px | 1.05 | -0.04em | fixed | Centered opening promise. |
| display-italic | louize | 500 italic | 64px | 1.05 | -0.04em | fixed | The capability phrase on the second headline line. |
| quote | louize | 400 | 44px | 1.5 | -0.02em | size clamp(26px, 3.8vw, 44px) | Centered customer quotation. |
| proof-heading | louize | 400 | 44px | 1.1 | -0.03em | size clamp(28px, 4vw, 44px) | Heading over quantified proof. |
| feature-heading | louize | 400 | 28px | 1.1 | -0.03em | fixed | Compact chapter heading beside media. |
| metric-label | louize | 400 | 19px | 1.1 | -0.01em | fixed | Names directly below counters. |
| footer-heading | louize | 500 | 18px | 1 | -0.01em | fixed | Footer column headings. |
| body | lausanne | 400 | 16px | 1.5 | normal | fixed | Support lines and feature benefit rows. |
| action | lausanne | 500 | 14px | 1 | normal | fixed | Buttons and form labels. |
| link | lausanne | 400 | 14px | 1 | normal | fixed | Navigation and footer links. |
| caption | lausanne | 400 | 14px | 1.5 | normal | fixed | Short explanations under metrics. |
| announcement | lausanne | 500 | 13px | 1 | normal | fixed | Announcement capsule text. |
| live-label | lausanne | 400 | 12px | 1.5 | 0.14em, uppercase | fixed | Small Live capsule above proof heading. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| resource and recruiting pages | editorial-display | louize | 500 | 72px | 1.02 | -0.045em | size clamp(40px, 7vw, 72px) | Left-aligned title over wide photography. |
| recruiting pages | culture-heading | louize | 500 | 52px | 1.05 | -0.04em | size clamp(32px, 5vw, 52px) | Recruiting chapter headings. |
| recruiting FAQ | faq-heading | louize | 500 | 48px | 1.3 | -0.02em | size clamp(32px, 5vw, 48px) | Centered FAQ section heading. |
| resource pages | resource-heading | louize | 500 | 40px | 1.05 | -0.04em | size clamp(28px, 4vw, 40px) | Resource chapter headings. |
| recruiting pages | listing-heading | louize | 500 | 24px | 1.15 | -0.02em | fixed | Role cards and application form title. |
| culture pages | principle-heading | louize | 500 | 22px | 1.15 | -0.01em | fixed | Principle list headings. |
| recruiting pages | benefit-heading | louize | 500 | 20px | 1.15 | -0.01em | fixed | Numbered benefit card headings. |
| FAQ sections | question | lausanne | 500 | 18px | 1.5 | normal | fixed | Accordion question buttons. |
| resource galleries | gallery-caption | lausanne | 400 | 13px | 1.625 | normal | fixed | Evocative descriptions below titled art. |
| numbered benefits | index | jetbrainsMono | 400 | 12px | 1 | normal | fixed | Two-digit card indexes. |
| role listings | category | lausanne | 500 | 12px | 16px | 0.12em, uppercase | fixed | Role and location metadata. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Serif headings tighten progressively: -0.01em at small labels, -0.03em in feature headings and counters, -0.04em in display. Sans reading text remains normally tracked.
- Keep the italic phrase equal in size and weight to its surrounding display text; it is a change of voice, not a small subheading.
- Use the 28px feature heading for the default product chapter, not the 52px recruiting chapter style.

## Layout

**Density:** Airy overall, with compact controls and short lists inside widely separated editorial chapters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon/button gaps and small heading-to-description gaps. |
| 12px | Feature heading to support line; benefit row vertical padding. |
| 16px | Listing and benefit card grid gaps. |
| 20px | Resource gallery column gaps and form field groups. |
| 24px | Small card padding and footer link gaps. |
| 32px | Opening stack gaps, form padding and listing-card padding. |
| 40px | Closing headline-to-action gap and logo-to-status gap. |
| 64px | Product feature column gap. |
| 96px | Closing section vertical padding and desktop footer column gaps. |
| 112px | Live proof section vertical padding. |
| 120px | Desktop page side gutters and footer padding. |
| 128px | Resource and recruiting section vertical padding. |
| 144px | Opening content top inset. |
| 176px | Editorial opening inset and product chapter-group vertical padding. |
| 192px | Recruiting FAQ vertical padding. |

### Containers and grids

- **page container**: max width 1200px · side padding 120px. Centered desktop content across a 1440px canvas.
- **opening copy**: max width 520px. Centered two-line support paragraph; headline can expand to 738px.
- **feature row**: max width 1200px · 2 columns · gap 64px. Alternating text and a fixed 540×440px image panel. Text fills the remaining space; paragraph width is 470px.
- **proof**: max width 1000px · 2 columns · gap 0px. Equal centered counters divided by one vertical rule.
- **recruiting column** (only for recruiting lists and forms): max width 920px. Narrow centered listings and application form.
- **benefits grid** (only for recruiting pages): max width 1200px · 4 columns · gap 16px. Two rows of numbered cards.
- **resource grid** (only for resource pages): max width 1200px · 3 columns · gap 20px. Specimens or image galleries. Logo presentations instead use two columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | feature media | 24px |
|  | cinematic call | 32px |
| resource pages | resource cards | 16px |
| recruiting pages | listing cards and fields | 20px |
| culture pages | culture portrait | 28px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | capsule lift | `0 0 0 1px rgba(8,21,46,0.1), 0 2px 8px rgba(8,21,46,0.06)` | Opening action and announcement. |
| recruiting benefits | benefit lift | `0 0 0 1px rgba(8,21,46,0.1) inset, 0 1px 2px rgba(8,21,46,0.04), 0 8px 24px rgba(8,21,46,0.05)` | Low, soft lift for small cards. |

### Surfaces

#### Porcelain canvas · level 0

**Use:** Default background throughout.

**CSS:** `background: #fcfcfd; color: #08152e`

**Observed:** Continuous near-white space; no alternating dark full-page themes.

**Transfer:** Let images, rather than section fills, carry saturated color.

#### Dream scene panel · level 1

**Use:** Atmospheric backing behind feature demonstrations.

**CSS:** `background: rgba(8,21,46,0.04); border-radius: 24px; overflow: hidden`

**Observed:** Full-bleed blue-hour artwork beneath a 40% ink overlay in several panels, with crisp UI above it.

**Transfer:** Use the Dream-soft imagery treatment and keep the product fragment sharp.

#### Cinematic call · level 1

**Use:** Immersive invitation near conversion.

**CSS:** `border-radius: 32px; overflow: hidden; aspect-ratio: 16 / 9; position: relative`

**Observed:** Full-cover scene with an ink overlay at 35%, centered light type and a pale action.

**Transfer:** Use an everyday scene that suggests the benefit after the product has done its work.

#### Inset resource card · level 1

**Only for:** resource pages

**Use:** Artwork frames, logo plates and font specimens.

**CSS:** `border-radius: 16px; box-shadow: 0 0 0 1px rgba(8,21,46,0.1) inset; overflow: hidden`

**Observed:** Plain, almost unraised frames; logo plates alternate cool card and ink fills.

**Transfer:** Keep labels below visual assets rather than adding heavy card chrome.

#### Application panel · level 1

**Only for:** application forms

**Use:** Single-column form backing.

**CSS:** `background: rgba(8,21,46,0.03); border-radius: 24px; padding: 32px; box-shadow: 0 0 0 1px rgba(8,21,46,0.06) inset`

#### Benefits band · level 0

**Only for:** recruiting pages

**Use:** Subtle full-width contrast behind numbered cards.

**CSS:** `background: rgba(8,21,46,0.02); padding: 128px 120px`

## Components

### Navigation link

**Use:** Compact top-level navigation beside the wordmark.

**CSS:** `display: inline-flex; padding: 8px 16px; border-radius: 8px; color: rgba(8,21,46,0.8)`

**Text style:** `link` — lausanne 400 · 14px/1

**Observed:** Header is absolute, 70px tall with 20px vertical and 120px side padding. Wordmark and navigation form a left group with 36px gap; login and a dark action sit at right. Login is a 30px pale translucent capsule with 12px backdrop blur; the dark header action is also 30px.

**States:** Declared: hover background ink at 5% and text ink.

### Primary button

**Use:** Default action beside product capability chapters.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #08152e; color: #fcfcfd; border-radius: 9999px; padding: 10px 16px`

**Text style:** `action` — lausanne 500 · 14px/1

**Observed:** Small, label-sized dark pill rather than a wide block. Recruiting actions use 12px 20px padding and 38px height; the resource download adds a leading download icon.

**States:** Declared: hover opacity 0.9; active scale 0.97.

### Opening action

**Use:** Friendly primary conversion under the opening paragraph.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; background: #f5f6f8; color: #08152e; padding: 10px 16px; border-radius: 9999px; box-shadow: 0 0 0 1px rgba(8,21,46,0.1), 0 2px 8px rgba(8,21,46,0.06)`

**Text style:** `action` — lausanne 500 · 14px/1

**Observed:** A 20px messaging icon precedes the text, producing a 40px-high control.

**States:** Declared: hover retains outline and soft shadow; active scale 0.97.

### Closing action

**Use:** High-contrast conversion over the cinematic call.

**CSS:** `display: inline-flex; align-items: center; gap: 10px; background: #fcfcfd; color: #08152e; padding: 16px 24px; border-radius: 9999px`

**Text style:** `action` — lausanne 500 · 14px/1

**Observed:** A 20px messaging icon leads the label. The text-only recruiting version is shorter at 46px, versus the default 52px.

**States:** Declared: hover opacity 0.9; active scale 0.96.

### Announcement capsule

**Use:** A low-key product news invitation above the opening headline.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; height: 36px; padding: 4px 12px 4px 4px; background: #f5f6f8; border-radius: 9999px; box-shadow: 0 0 0 1px rgba(8,21,46,0.1), 0 2px 8px rgba(8,21,46,0.06)`

**Text style:** `announcement` — lausanne 500 · 13px/1

**Observed:** Dark inset New capsule on the left, short announcement in the middle and a small thin chevron on the right.

### Benefit row

**Use:** Three concise supporting outcomes under a feature paragraph.

**CSS:** `display: flex; padding: 12px 0px; border-bottom: 0.5px solid rgba(8,21,46,0.1); color: rgba(8,21,46,0.65)`

**Text style:** `body` — lausanne 400 · 16px/1.5

**Observed:** An 18px outline icon leads each line by 12px; the last row does not need a bottom rule.

### Live badge

**Use:** Small operational cue above quantified proof.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 6px 12px; background: rgba(8,21,46,0.04); border-radius: 9999px; color: rgba(8,21,46,0.55)`

**Text style:** `live-label` — lausanne 400 · 12px/1.5 · tracking 0.14em · uppercase

**Observed:** A 6px ink dot accompanies the tracked uppercase label.

### Metric column

**Use:** Quantified usage proof without a dashboard.

**CSS:** `display: flex; flex-direction: column; align-items: center; padding: 0px 40px; text-align: center; border-right: 1px solid rgba(8,21,46,0.1)`

**Text style:** `metric` — louize 400 · 84px/1 · tracking -0.03em

**Observed:** Number first, then a small serif label and a muted sentence. Only the first column carries the divider. Numerals use tabular alignment.

**Transfer:** Use verifiable counts; keep definitions legible instead of adding charts.

### Footer link column

**Use:** Lightweight site directory after the closing content.

**CSS:** `display: flex; flex-direction: column; gap: 24px`

**Text style:** `link` — lausanne 400 · 14px/1

**Observed:** Small serif heading above sans links. Three columns align at the right with 96px gaps; logo and an 8px green status dot sit in a separate left column. Footer has 120px padding on all sides.

**States:** Declared: hover link color becomes ink.

### Numbered benefit card

**Only for:** recruiting pages

**Use:** A compact factual package in an airy grid.

**CSS:** `background: #fcfcfd; border-radius: 20px; padding: 24px; display: flex; flex-direction: column; gap: 12px; box-shadow: 0 0 0 1px rgba(8,21,46,0.1) inset, 0 1px 2px rgba(8,21,46,0.04), 0 8px 24px rgba(8,21,46,0.05)`

**Text style:** `benefit-heading` — louize 500 · 20px/1.15 · tracking -0.01em

**Observed:** Faint two-digit mono index, serif title and a short 14px sans description. Cards are 288px wide in a four-column desktop grid.

### Application field

**Only for:** application forms

**Use:** Rounded single-column text input, select and longer note.

**CSS:** `background: #fcfcfd; color: #08152e; border-radius: 20px; padding: 14px 16px; box-shadow: 0 0 0 1px rgba(8,21,46,0.1) inset; width: 100%`

**Text style:** `body` — lausanne 400 · 16px/1.5

**Observed:** Label sits 8px above each field. Normal fields are 52px high and the note area is 172px; field groups are separated by 20px.

### FAQ item

**Only for:** FAQ sections

**Use:** Direct objection handling with one answer expanded.

**CSS:** `border-radius: 24px; overflow: hidden; background: rgba(8,21,46,0.04); box-shadow: 0 0 16px rgba(0,0,0,0.02)`

**Text style:** `question` — lausanne 500 · 18px/1.5

**Observed:** Expanded item receives the wash; collapsed questions sit on the canvas. Questions have 18px 24px padding, reduced to 8px at the bottom when open. Plus or minus is aligned at far right; answer is 16px/1.5 sans.

## Imagery and graphics

### Tangible product stage

**Use:** The opening's main object.

**Observed:** A realistic silver-edged phone, 450×920px, centered on porcelain. The white screen carries an informal messaging exchange and overlapping photo cards. Small pale organic marks hover near its upper corners; the device, not an abstract glow, anchors the page.

**Transfer:** Present one credible interaction in a device or closely framed interface with a tactile edge. For non-mobile products, use a similarly narrow isolated product object rather than an entire desktop dashboard.

**Build:** For a simplified substitute, frame a 450px-wide interface with concentric dark and metallic-gray rounded outlines, white interior and a small top speaker cutout. Place the product interaction inside; keep the surrounding canvas empty.

### Dream-soft scenes

**Use:** Required atmospheric media language for capability illustrations and cinematic invitations.

**Observed:** Everyday desks, glowing laptops, hands, cups, shopfronts and people at dusk become hazy cinematic scenes. Deep navy and teal shadows, blue illumination and small orange, pink or yellow light sources mix with grain, bloom and soft chromatic fringes. Feature scenes fill 540×440px panels; closing scenes fill a 1200×675px frame.

**Transfer:** Photograph an ordinary moment in the customer's life, soften it into colored atmosphere and place a sharp relevant product fragment above it. Minimum acceptable treatment is a carefully graded blue-hour photograph with a warm light source, controlled blur and grain.

**Build:** Use a full-cover photograph as the bottom layer. Add a navy wash at 35–40% opacity, a broad cool-blue light near the upper center and a smaller warm bloom toward one side. As guidance, soften the photo with 8–16px blur while keeping overlaid interface layers unfiltered. Add a low-opacity SVG fractal-noise texture, and offset faint red/cyan copies by 1–2px for a restrained optical fringe. Match the luminous softness; exact glow stops are not essential.

### Floating product fragments

**Use:** Crisp demonstrations above atmospheric feature art.

**Observed:** White app tiles orbit a larger central tile; elsewhere blue and gray message bubbles, a softly shadowed photo or a translucent notification card float over the scene. Foreground fragments occupy a minority of each panel, leaving the environment visible.

**Transfer:** Use one small cluster of meaningful artifacts rather than a whole application. Keep saturated action color inside the demonstration.

**Build:** Arrange 44–56px white rounded tiles around a 68px focal tile; give the focal tile a deeper soft shadow. Alternatively stack two rounded message balloons and one small portrait photo. Maintain clear silhouettes above the darkened backing.

### Seed-mark divider

**Use:** Signature punctuation between capability chapters.

**Observed:** A faint horizontal rule is interrupted at center by five small gray organic petal/seed marks, within a 152×60px ornament area.

**Transfer:** Use a repeated tiny organic silhouette related to the new identity; retain the low-contrast rhythm and interrupted rule.

**Build:** Draw five small asymmetric oval paths in an SVG, varying their rotations and width, within a 152×60px viewBox. Fill with ink at roughly 35% opacity. Center over a porcelain patch across a 1px rule in ink at 10% opacity.

### Editorial art gallery

**Only for:** resource and culture pages

**Use:** Wide opening scenes, a tall culture illustration and downloadable art collections.

**Observed:** The same grainy soft-focus treatment expands to a 1200px-wide opening banner, a 560×700px solitary desk-by-water portrait and three-column landscape or tall image collections. Small titles and poetic sans captions sit below the gallery images.

**Transfer:** Show life around the product: a place to think, a social moment, a restful desk. Keep specific actions recognizable beneath the dreamy treatment rather than using arbitrary gradient wallpaper.

### Icons

**Observed:** Feature rows use 18×18px outline SVGs with 1.6px round strokes in ink at 70%; small navigation chevrons use roughly 14px outlines. Demonstration app logos are colorful filled tiles, visually separate from marketing icons.

**Transfer:** Choose simple round-capped line symbols for benefit rows. Keep product-specific logos within demonstrations and action icons.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** An unboxed, near-white first screen: 70px absolute navigation at the top, centered opening content beginning at 144px. Announcement capsule, two-line 64px serif headline, a support paragraph no wider than 520px and Opening action are separated by 32px. The headline's first line is roman and the role phrase on the second is italic. Behind everything is Porcelain canvas; below the action comes the Tangible product stage, with a 450px-wide phone beginning around the lower third of the viewport. Within the first 900px the headline, support, action and upper device interaction are visible; the lower phone and subsequent proof fall below.

**Transfer:** Keep the small capsule, literary promise and narrow tactile product demonstration for an ordinary landing page. Without device artwork, construct a restrained framed interaction with one visible outcome. Resource and recruiting openings instead use left-aligned editorial-display type at a 176px top inset, followed by wide Dream-soft scenes and actions beneath the image.

**Avoid:** Do not turn this into a side-by-side SaaS dashboard hero or a full-bleed dark first screen; do not shrink the device to fit its full height above the fold.

**Text style:** `display` — louize 500 · 64px/1.05 · tracking -0.04em

### Capability chapter

**Observed:** Feature row alternates image and text across a 1200px container with 64px gap. A 28px feature-heading, 12px-separated support text, three Benefit rows and a Primary button sit beside Dream scene panel. Rows are 440px tall; Seed-mark divider punctuates the space between them.

**Transfer:** Each chapter explains one useful outcome, supported by concrete behaviors and one crisp visual example. Vary the number of chapters to suit the product.

**Text style:** `feature-heading` — louize 400 · 28px/1.1 · tracking -0.03em

### Human proof pause

**Observed:** An airy centered section with 96px vertical padding, a small rounded portrait above a 940px-wide quote, 44px/1.5 serif text and a small sans attribution beneath. The section occupies 810px of height.

**Transfer:** Use a genuine short story with a specific moment of usefulness; let it breathe without a bordered quote card.

**Text style:** `quote` — louize 400 · 44px/1.5 · tracking -0.02em

### Live quantified proof

**Observed:** A 1000px-wide centered composition with 112px vertical padding. Live badge sits above a 44px proof-heading; two Metric columns follow after 48px. Counters use 84px serif numerals, small serif labels and muted 14px explanations.

**Transfer:** Use operational proof when genuine counts exist; otherwise retain the oversized serif-number treatment for a verified outcome rather than simulating a live feed.

**Text style:** `proof-heading` — louize 400 · 44px/1.1 · tracking -0.03em

### Cinematic invitation

**Observed:** Cinematic call is surrounded by 96px vertical and 120px side padding. Centered closing-display text is limited to 720px, in porcelain over the dim image; Closing action follows after 40px.

**Transfer:** Make the invitation about what life or work feels like after adopting the product. Keep the atmosphere human and the call brief.

**Text style:** `closing-display` — louize 500 · 80px/1.05 · tracking -0.04em

### Directory ending

**Observed:** Footer link column groups sit on Porcelain canvas with 120px padding. A compact wordmark and status line occupy the left; three serif-titled link columns occupy the right. No giant terminal wordmark or dark legal band.

**Transfer:** End with a useful directory appropriate to the new product, retaining the separated status/identity block.

### Resource collection

**Only for:** resource pages

**Observed:** Left-aligned 40px serif chapter headings, short sans explanations and 128px vertical section padding. Two-column light/dark logo plates precede three-column font specimens and art galleries. Landscape art and tall covers carry captions below. The final Questions block uses a simple underlined contact link, then the directory footer rather than a cinematic call.

**Transfer:** Use this quieter resource-page variant for downloads, documentation indexes or press kits; keep functional captions and generous chapter separation.

**Text style:** `resource-heading` — louize 500 · 40px/1.05 · tracking -0.04em

### Culture and recruiting chapters

**Only for:** recruiting pages

**Observed:** A tall Dream-soft scene pairs with 52px heading and ruled principle list. Benefits band holds numbered cards in four columns. A centered 920px column carries 20px-radius listing cards with uppercase metadata, serif titles and short summaries, then Application panel. A centered FAQ follows with 48px heading, 48px heading-to-list gap and 192px vertical padding; a cinematic invitation and directory finish the page.

**Transfer:** Borrow the distinct modules for a people-focused page; do not force culture content or an application form onto an ordinary product landing page.

**Text style:** `culture-heading` — louize 500 · 52px/1.05 · tracking -0.04em

## Page flow

**Storyline:** Personal promise → tangible demonstration → human or factual proof → outcome chapters → invitation → practical directory; adapt the middle to the page's purpose.

### Introduce a product and make everyday usefulness believable

1. **Promise** — Centered literary headline, small news capsule and pale action.
2. **Product demonstration** — Large isolated phone with one conversational exchange.
3. **Social proof** — Spacious portrait and serif quotation.
4. **Capability chapters** — Alternating atmospheric media and compact outcome lists with repeated small actions.
5. **Quantified proof** — Live badge and paired oversized serif counters.
6. **Closing call** — Rounded cinematic image, white headline and one pale action.
7. **Directory** — Status/identity block and three link columns.

**Transfer:** Use this as the default marketing rhythm, replacing each proof device with relevant verified material and choosing only the chapters the product needs.

### Provide reusable assets with clear guidance

1. **Orientation** — Left-aligned editorial title, wide atmospheric scene and download action.
2. **Usage guidance** — Short naming rules and two-column logo plates.
3. **System explanation** — Three font specimen cards.
4. **Asset collection** — Landscape and portrait artwork grids with small titled captions.
5. **Support** — Small Questions chapter and inline contact link.
6. **Directory** — Shared light footer.

**Transfer:** For a resource hub, keep the clear chapter structure and actionable downloads; end with human support rather than a sales scene.

### Explain the working environment and convert suitable applicants

1. **Invitation** — Left-aligned title, wide illustration and two application paths below.
2. **Principles** — Tall image beside ruled values.
3. **Concrete package** — Numbered benefit cards in a subtly tinted band.
4. **Available choices** — Narrow stacked listing cards.
5. **Conversion** — One-column rounded application form.
6. **Objection handling** — Uncluttered FAQ with one expanded answer.
7. **Closing call** — Cinematic people scene with pale action.
8. **Directory** — Shared status and link footer.

**Transfer:** For recruitment or participation, let specific terms and the form carry the decision; reserve emotional imagery for invitation and closure.

## Writing

Warm, capable and plainspoken. Practical verbs and recognizable moments do the persuasion; the more lyrical language belongs to image captions, not inflated product claims.

**Do not copy:** Do not reuse Orchid or Keiki names, logos, proprietary artwork, customer quotations, metrics, hiring terms or product claims. Examples illustrate the voice, not reusable facts.

- **Addressing the reader:** Address the reader as you and your; use we for the team and the product name when describing what acts on the user's behalf.
- **Rhythm:** Brief sentence-case headlines, generally 3–8 words, often with a period. Support is one or two concise sentences; fragments and everyday lists provide pace.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Introduce the product as a familiar useful role, with the role emphasized in italic. | 4–8 words | “Meet [Brand], your calendar coordinator.” |
| Capability headline | State an outcome or reduce a familiar burden. | 3–9 words | “Connect with your stack.”<br>“Your second brain.” |
| Support | Name ordinary tasks, then explain the relief without technical jargon. | 15–30 words | “Bills, bookings, follow ups, forms. The boring stuff still gets done, you just stop being the one doing it.” |
| Action | Short literal verb phrase. | 2–4 words | “Get Started”<br>“Download all assets”<br>“See open roles” |
| Principle | A direct standard followed by a practical consequence. | 2–5 word title plus one short paragraph | “We care whether the product works, not whether we can announce it.” |
| Art caption | Describe an evocative scene and connect it to a human feeling. | 15–30 words | “Two hands, almost touching. The quiet trust of handing something off and knowing it is held.” |

**Words and phrasing to use:** get things done; connect once; handled; your tools; tell the truth; short note; room to think

**Avoid:** revolutionary; unlock limitless potential; synergy; hyperautomation; game-changing; unprecedented

**Rules:**

- Describe one concrete behavior before making an abstract benefit claim.
- Keep feature lists parallel and short enough to read as single lines.
- Use contractions naturally; avoid exclamation marks in marketing headlines.
- Reserve lowercase chat slang and emoji for believable product conversations, not navigation or section headings.
- Make resource instructions literal and unambiguous; let gallery captions carry the poetry.

## Do's and Don'ts

### Do

- Keep the 64px roman/italic opening pair at the same weight and line height.
- Use 120px desktop side gutters around the 1200px composition.
- Confine saturated scenery to rounded media and keep the page canvas porcelain.
- Make feature media 540×440px with 24px corners and sharp foreground fragments.
- Keep default chapter actions compact with 10px 16px padding and 14px text.
- Include the seed-mark punctuation and cinematic invitation as recognizable devices, adapting their content and placement.
- Use 84px serif numerals with small explanatory labels for factual proof.
- Keep the footer light, with 18px serif headings and 14px sans links.

### Don't

- Do not replace the main serif hierarchy with heavy geometric sans display text.
- Do not use blue message-bubble color as the marketing button palette.
- Do not apply photographic blur to text, actions or foreground UI fragments.
- Do not give every informational row a raised shadow card; feature benefits use 0.5px rules.
- Do not make all buttons 52px high; that size belongs to the image-backed conversion action.
- Do not import numbered recruiting cards or role metadata into every ordinary feature chapter.
- Do not alternate whole-page navy and white bands; the dark atmosphere belongs inside image frames.
- Do not turn the footer into a huge wordmark poster; its identity block remains compact.

## Motion and responsive

### Motion

**Observed:**

- Action opacity/scale transitions are 0.15s cubic-bezier(.4, 0, .2, 1). Primary actions reduce opacity to 0.9 on hover and scale to 0.97 on press; the closing action scales to 0.96.
- FAQ backgrounds and shadows transition over 0.3s cubic-bezier(0, 0, .2, 1).
- The opening capability phrase changes while retaining the same italic treatment.

**Transfer:**

- Keep feedback on the small capsules restrained; preserve the difference between the fixed crisp interface and atmospheric media.
- If rotating the capability phrase, maintain the two-line headline footprint rather than letting subsequent content jump.

**Unknown:**

- Runtime reveal timings, phrase-rotation cadence and image-layer animation choreography are not specified.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Feature rows use a column layout below 1024px. Benefits declare one, two and four columns; galleries declare one and three columns.
- Desktop navigation links and login are hidden below the medium breakpoint. Editorial title and closing headline use the stated clamp formulas.

**Transfer:**

- On narrow screens, use 24px side padding, stack media and copy, keep message fragments inside their media frame and preserve the tactile opening object.
- Reduce multi-column grids rather than shrinking card text. Keep the cinematic frame's centered invitation readable with its clamp type.

**Unknown:**

- Exact narrow-screen navigation replacement and settled mobile compositions are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
