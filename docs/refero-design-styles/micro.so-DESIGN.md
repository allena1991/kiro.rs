# Micro — painterly work companions

## Overview

An airy software style that puts capable, matter-of-fact interfaces inside a surprisingly pastoral world. Heavy grotesk promises trade phrases with nostalgic, narrow serif lettering, while warm charcoal and taupe sit on a pale gray canvas. Painted skies and meadows, small friendly character drawings, and tactile book objects soften the product density. It suits ambitious productivity products that want to feel personal rather than corporate.

### Essentials

- Promises have two voices in the same breath: 72px/0.95 weight-900 Haffer phrases alternate with weight-700 Perfectly Nineties phrases at the same size, 0.02em tracking and half-opacity warm ink.
- The opening is a centered promise above a working object: a 32px announcement badge, two headline lines, a 672px support measure and paired 44px actions lead into a 1200px-wide application stage visible above the fold.
- Controls feel like small physical keys: 10px-radius dark and white buttons, 24px horizontal padding and a 2px inset lower shadow on the dark action. Navigation actions step down to 28px height and 8px radius.
- Color belongs to scenery and objects rather than the page shell: #f5f5f5 dominates, with #fafafa panels and #221f1c text. Painted blue skies, olive fields and colored book spines supply concentrated color; near-black and coral are a technical-chapter variant.
- Software is staged against a painted horizon: rounded 18px outer windows surround almost-white interfaces with textured sky above muted fields. Include this landscape-backed product device and a matching 1056×540px closing panel; without finished media use a restrained SVG landscape with paper grain.
- Personality comes in tangible interruptions: a monochrome friendly character peeks over the product window, while a shelf of 300px-tall colored book objects makes abstract capabilities collectible. Translate these into an original character and relevant objects rather than floating blobs.
- The last promise is monumental but relaxed: a 96px/1 black-weight sans outcome sits over a 32px serif afterthought shifted to its right with a -16px overlap, followed by paired actions and an airy multi-column footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Book ochre | `#e5a057` | `--color-ochre` | surface, accent | Warm companion book spine. |
| Book blue and focus | `#518bdb` | `--color-blue` | accent, border, link | Book covers, focus borders and the support link; not the ordinary primary action. |
| Book rose | `#ed6d68` | `--color-rose` | surface, accent | Soft red companion book spine. |
| Book turquoise | `#36bab8` | `--color-teal` | accent, surface | Lead book cover and small illustrated accents. |
| Book lilac | `#bf89cd` | `--color-lilac` | surface, accent | Purple companion book spine. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#221f1c` | `--color-ink` | text, action | Primary text and dark actions; 50% opacity for secondary display phrases and 75% for hero support. |
| Taupe gray | `#797267` | `--color-muted` | text | Descriptions, captions, footer links and outline icons. |
| Control edge | `#d8d8d8` | `--color-input-edge` | border | Visible black-at-12% control edge over the canvas. |
| Soft gray hairline | `#e1e1e1` | `--color-edge` | border | Visible black-at-8% separator over the pale canvas; constructed with rgba(0,0,0,0.08). |
| Landscape quote white | `#e4e4e4` | `--color-quote` | text | Serif quotation over a darkened meadow. |
| Pale gray canvas | `#f5f5f5` | `--color-canvas` | background, text | Default canvas and inverse text on dark actions. |
| Near-white panel | `#fafafa` | `--color-panel` | surface | Cards and application surfaces, subtly lighter than the canvas. |
| White | `#ffffff` | `--color-white` | surface, text | Secondary actions and elevated pricing panels; 75% white is used for translucent navigation. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| developer-oriented chapters | Technical coral | `#ff6257` | `--color-coral` | text, action, accent | Technical headings, faint grid lines and chapter action. |
| developer-oriented chapters | Technical black | `#050505` | `--color-night` | background | Technical chapter background. |

## Typography

- **haffer** — Heavy promises, body copy, controls and interface framing. Friendly geometric grotesk, broad at black weight with rounded lowercase. If unavailable, use **DM Sans**. Use 400–900 with normal tracking; match the broad black headline measure. Font stack: "haffer", "DM Sans", Arial, sans-serif.
- **perfectlyNineties** — Conversational headline phrases, section headings and pastoral quotations. Narrow nostalgic display serif with lively curved terminals; upright rather than italic. If unavailable, use **Instrument Serif**. Preserve narrow proportions and 0.02em tracking; use the available regular cut where heavier cuts are unavailable. Font stack: "perfectlyNineties", "Instrument Serif", Georgia, serif.
- **ui-monospace** (only for developer-oriented chapters) — Technical chapter headline and tool labels. Utilitarian monospace interrupting the softer editorial typography. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| monument | haffer | 900 | 96px | 1 | normal | fixed | Short chapter statements and closing outcome. |
| chapter-strong | haffer | 900 | 75.2px | 1 | normal | size clamp(2.15rem, 6.2vw, 4.7rem) | Centered product-family statement. |
| hero-strong | haffer | 900 | 72px | 0.95 | normal | fixed | Strong clauses in the two-line opening promise. |
| hero-soft | perfectlyNineties | 700 | 72px | 0.95 | 0.02em | fixed | Secondary opening clauses in ink at 50% opacity. |
| chapter-interjection | perfectlyNineties | 900 | 64px | 1 | 0.02em | size clamp(2rem, 5.55vw, 4rem) | Middle line between monumental sans phrases. |
| chapter-tail | perfectlyNineties | 900 | 48.8px | 1 | 0.02em | size clamp(1.6rem, 3.9vw, 3.05rem) | Right-aligned continuation under a chapter statement. |
| section-heading | perfectlyNineties | 700 | 48px | 1 | 0.02em | fixed | Default capability chapter headings. |
| landscape-quote | perfectlyNineties | 700 | 36px | 1.2 | 0.02em | fixed | Quotation over pastoral artwork. |
| closing-afterthought | perfectlyNineties | 700 | 32px | 1.429 | 0.02em | fixed | Right-shifted closing continuation. |
| subheading | haffer | 500 | 24px | 1.333 | normal | fixed | Secondary groups and feature-panel text tabs. |
| hero-support | haffer | 400 | 20px | 1.4 | normal | fixed | Centered opening explanation within 672px. |
| card-heading | haffer | 500 | 20px | 1.25 | normal | fixed | Capability card titles. |
| body-lead | haffer | 400 | 18px | 1.556 | normal | fixed | Chapter support lines in muted taupe. |
| action | haffer | 500 | 16px | 1.5 | normal | fixed | Main buttons and FAQ triggers. |
| small-medium | haffer | 500 | 14px | 1.43 | normal | fixed | Navigation, announcement and compact controls. |
| caption | haffer | 400 | 14px | 1.43 | normal | fixed | Metadata, footer links and concise details. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-heading | perfectlyNineties | 400 | 60px | 1 | 0.02em | fixed | Single centered pricing promise. |
| developer-oriented chapters | technical-heading | ui-monospace | 900 | 48px | 1 | normal | fixed | Centered technical statement. |
| pricing pages | faq-heading | haffer | 700 | 36px | 1.111 | normal | fixed | FAQ side-column title. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Positive 0.02em tracking is a serif family treatment; sans headings retain normal tracking even at 96px.
- Pair forceful outcomes in black-weight sans with a softer serif qualification within one statement.
- The chapter-tail overlaps by -0.14em. The closing-afterthought overlaps by -16px and begins around 36% into the main text width.
- Do not treat the serif as italic; its character comes from narrow letterforms and shaped terminals.

## Layout

**Density:** Airy at chapter scale and compact inside software objects; broad pauses surround detailed cards without enlarging controls.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Navigation padding and tight clusters. |
| 8px | Icon-label and form control gaps. |
| 12px | Paired actions, card gutters and footer link gaps. |
| 16px | Heading-to-support gap and compact card padding. |
| 20px | Featured card padding and announcement separation. |
| 24px | Action horizontal padding, pricing padding and footer brand gaps. |
| 32px | Large card padding and support-to-action spacing. |
| 48px | Desktop side padding and shelf lead-in. |
| 64px | Footer column gaps and compact chapter pauses. |
| 80px | Split demonstration vertical padding. |
| 96px | Default major section and footer vertical padding. |
| 128px | Immersive chapter and resource section padding. |

### Containers and grids

- **marketing-container**: max width 1152px · side padding 48px. Centered border-box wrapper yielding 1056px usable desktop content. Side padding becomes 24px on narrow layouts.
- **hero-copy**: max width 672px. Centered explanation under the broader mixed-face headline.
- **hero-stage**: max width 1280px. Wide stage enclosing a 1200×675px application window.
- **card-grid**: 4 columns · gap 12px. Four 255px compact cards within the content measure; longer collections overflow horizontally.
- **bento**: 10 columns · gap 12px. Asymmetric broad and narrow trust panels.
- **pricing-grid** (only for pricing pages): max width 1024px · 3 columns · gap 0px. Aligned plans with one raised center offer.
- **comparison-grid** (only for pricing pages): 4 columns · gap 0px. Feature names plus three 264px plan columns within 1056px.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons-and-inputs | 10px |
| compact-actions | 8px |
| small-cards-and-nav | 14px |
| feature-panels-and-landscapes | 18px |
| floating-demo-window | 22px |
| book-edge | 3px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | button-bottom | `inset 0px -2px 0px 0px rgba(0,0,0,0.2)` | Tactile lower edge on dark actions. |
|  | small-card | `0px 0px 0px 1px rgba(34,31,28,0.065), 0px 4px 6px -1px rgba(0,0,0,0.05), 0px 2px 4px -2px rgba(0,0,0,0.05)` | Low elevation for repeated content objects. |
| pricing pages | raised-plan | `0px 0px 0px 1px rgba(34,31,28,0.1), 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Recommended plan and comparison column. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous light marketing ground.

**CSS:** `background: #f5f5f5; color: #221f1c`

**Observed:** Most chapters retain the same background.

**Transfer:** Distinguish chapters with spacing and type.

#### Soft panel · level 1

**Use:** Bento and capability panels.

**CSS:** `background: #fafafa; border: 1px solid rgba(0,0,0,0.08); border-radius: 18px; box-shadow: 0px 0px 0px 1px rgba(34,31,28,0.065), 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Observed:** A small tonal step separates panel from canvas.

**Transfer:** Use faint relief rather than bright fills.

#### Landscape stage · level 1

**Use:** Painted product backing and closing promise.

**CSS:** `border-radius: 18px; overflow: hidden; position: relative`

**Observed:** Pale sky and low horizon wrap light software; the closing scene adds a 25% white veil and inset shading.

**Transfer:** Use an original pastoral composition with generous sky.

#### Technical field · level 0

**Only for:** developer-oriented chapters

**Use:** Immersive technical interruption.

**CSS:** `background: #050505; color: #ff6257; padding: 128px 0px`

**Observed:** Coral grid fades into black; tool chips are rectangular.

**Transfer:** Keep this theme local to the technical story.

## Components

### Floating navigation

**Use:** Persistent compact navigation.

**CSS:** `position: fixed; top: 12px; background: rgba(255,255,255,0.75); backdrop-filter: blur(24px); border-radius: 14px; padding: 6px 0px 6px 6px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 4px 6px -1px rgba(0,0,0,0.065), 0px 2px 4px -2px rgba(0,0,0,0.065)`

**Text style:** `small-medium` — haffer 500 · 14px/1.43

**Observed:** Centered content-width shell. Initial header has a left wordmark and right account actions; after scrolling the shell includes a small symbol and compact signup action. Menu items use 28px height, 8px corners and 4px 12px padding.

**States:** Declared: hover menu items use ink-at-5% background and full ink text; focus-visible removes menu-item outline.

**Transfer:** Keep few short labels so the bar reads like a tool.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #221f1c; color: #f5f5f5; height: 44px; padding: 0px 24px; border-radius: 10px; box-shadow: inset 0px -2px 0px 0px rgba(0,0,0,0.2); gap: 8px`

**Text style:** `action` — haffer 500 · 16px/1.5

**Observed:** Paired with Secondary button at 12px gap. Navigation version is 28px high with 8px corners; resource version is 56px high. Pricing versions are 32px high and full width; only the recommended offer is dark.

**States:** Declared: hover background-color color-mix(in oklab,#221f1c 85%,transparent); focus-visible border-color #518bdb; active scale 0.98 and background-color color-mix(in oklab,#221f1c 75%,transparent).

### Secondary button

**Use:** Demo or alternative conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #221f1c; height: 44px; padding: 0px 24px; border: 1px solid rgba(0,0,0,0.12); border-radius: 10px`

**Text style:** `action` — haffer 500 · 16px/1.5

**Observed:** Shares the primary action's proportions; white remains visibly lighter than canvas.

**States:** Declared: hover translate 0 0; focus-visible border-color #518bdb; active scale 0.98.

### Announcement badge

**Use:** News entry above the opening promise.

**CSS:** `display: inline-flex; align-items: center; height: 32px; padding: 4px 12px 4px 4px; gap: 8px; background: #ffffff; border: 1px solid rgba(0,0,0,0.12); border-radius: 10px; margin-bottom: 20px`

**Text style:** `small-medium` — haffer 500 · 14px/1.43

**Observed:** A 40×20px thumbnail with 5px corners precedes the single-line label; a little key-shaped button rather than a pill.

### Capability card

**Use:** Browsable capability collection.

**CSS:** `display: flex; flex-direction: column; background: #fafafa; border-radius: 14px; padding: 20px; width: 224px; height: 288px; box-shadow: 0px 0px 0px 1px rgba(34,31,28,0.065), 0px 4px 6px -1px rgba(0,0,0,0.05), 0px 2px 4px -2px rgba(0,0,0,0.05)`

**Text style:** `card-heading` — haffer 500 · 20px/1.25

**Observed:** Icon or emoji, title, muted metadata and short description. A full-card action overlays the content. Strip extends beyond the text measure; smaller cards use 255×192px with 16px padding.

**Transfer:** Give each card one outcome and realistic metadata.

### Integration chip

**Use:** Short objects in horizontally moving ecosystem rows.

**CSS:** `display: flex; align-items: center; gap: 12px; padding: 12px 16px; height: 50px; background: #fafafa; border: 1px solid rgba(0,0,0,0.08); border-radius: 14px; box-shadow: 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `small-medium` — haffer 500 · 14px/1.43

**Observed:** Colored service symbol, label and occasional small status. Row masks become solid at 10% and transparent again after 90%.

**Transfer:** Keep color in the symbols rather than chip fills.

### Email field

**Use:** Resource-download form.

**CSS:** `background: #fafafa; color: #221f1c; border: 1px solid rgba(0,0,0,0.08); border-radius: 10px; padding: 0px 20px; height: 56px; width: 390px`

**Observed:** One field beside tall Primary button with 8px gap in a 576px measure; a reassurance line sits beneath.

**Transfer:** Ask for one item with clear delivery reassurance.

### Footer link

**Use:** Grouped navigation after the closing scene.

**CSS:** `color: #797267; text-decoration: none`

**Text style:** `caption` — haffer 400 · 14px/1.43

**Observed:** Short links with 12px vertical gaps, darker group labels and 64px column gaps. Brand description and social marks sit above; a faint rule separates the copyright and attribution row.

**States:** Declared: hover color #221f1c; color transition 0.15s cubic-bezier(.4,0,.2,1).

### Recommended plan

**Only for:** pricing pages

**Use:** Elevated central offer and comparison column.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 24px; display: grid; gap: 32px; backdrop-filter: blur(8px); box-shadow: 0px 0px 0px 1px rgba(34,31,28,0.1), 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Observed:** Middle plan alone is raised. Order is name, audience, price and cadence, full-width action, inclusion list. Comparison version continues as a white column with 14px outer corners.

**Transfer:** Highlight one offer with elevation, not a saturated badge.

### FAQ row

**Only for:** pricing pages

**Use:** Grouped objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 16px; padding: 16px 0px; border-bottom: 1px solid rgba(0,0,0,0.08); color: #221f1c`

**Text style:** `action` — haffer 500 · 16px/1.5

**Observed:** Question left and muted down-chevron right. Wrappers have 24px side insets; categories are separated by 48px.

**States:** Declared: hover text-decoration-line none; focus-visible border-color #518bdb.

## Imagery and graphics

### Painted horizon

**Use:** Signature backing for product scenes, quotation and closing call.

**Observed:** Traditional landscape painting with raised brush texture: pale blue sky, cream clouds, blue-gray distant hills, lake, olive meadows and trees. The closing panel is mostly sky with a low horizon; product stages expose narrow scenery margins. The quotation uses a closer dark meadow with grasses and wildflowers.

**Transfer:** Make an original softly lit pastoral painting. Keep natural perspective, restrained saturation and visible texture; the minimum equivalent is a layered SVG landscape, not a gradient alone.

**Build:** Use a wide SVG with sky occupying about three quarters of its height, soft cream cloud shapes, overlapping blue-gray hill paths and olive foreground paths. Add clustered trees near the lower left and a narrow lake near the horizon. Overlay low-opacity fractal noise and short irregular brush strokes. Apply brightness(1.22) saturate(0.92), object-fit: cover and object-position: center 62%; layer rgba(255,255,255,0.25) over the closing scene.

### Inset working windows

**Use:** Hero demonstration and capability chapters.

**Observed:** Plausible working interfaces in light windows. Opening stage is 1200×675px with 18px corners and broad low shadow. Later windows sit within roughly 550px landscape squares with 22px floating frames; lower interface content can fade toward the edge.

**Transfer:** Show one coherent workflow or faithful mockup. Keep tiny UI typography within the object rather than applying it to marketing text.

### Friendly character

**Use:** Humanizing accent over the product stage and beside selected chapter titles.

**Observed:** Rounded black-and-white figure with oversized eyes peeks over the left stage edge at roughly 173×185px; smaller expressive drawings accompany headings.

**Transfer:** Develop an original symbolic companion with thick-contour monochrome simplicity.

**Build:** Use an SVG rounded dark silhouette, inset cream face patch, two tall overlapping white eye ovals with dark pupils and a short curved smile. Keep shapes few and position it peeking over the frame rather than inside a separate illustration box.

### Tactile book shelf

**Use:** Signature object treatment for resources or packaged capabilities.

**Observed:** 300px-tall shelf with one 180px-wide turned face and adjacent 56px-wide spines, separated by 12px. Turquoise, ochre, lilac, rose and blue covers carry white serif titles, faint graphics, paper grain and vertical highlights. Smaller plugin books use 95×160px faces.

**Transfer:** Package relevant resources or modules as original books or boxes. Preserve this tangible device even without a downloadable guide by using a compact capability collection.

**Build:** Use CSS preserve-3d with a 180×300px front rotated 30deg on the Y axis, narrow spine face, 3px edge corners and 56×300px companion spines. Use the book palette, vertical white titles and faint line art. Add grayscale noise at 0.2 opacity with overlay blending, a black/white horizontal lighting gradient at 0.2 opacity and small inset highlights.

### Connected object cloud

**Use:** Explain a connected product model.

**Observed:** Small rounded data and message cards overlap in an 896×480px field with curved connectors and scattered service icons. Opacity falls toward the perimeter and bottom.

**Transfer:** Show genuine object types and relationships rather than a decorative dashboard collage.

**Build:** Arrange 100–200px light cards in three loosely staggered layers; use 14px corners, black-at-8% borders and 1–3px shadows. Draw thin translucent curved SVG connectors behind them. Fade the field edges with a radial mask; reserve color for connection icons.

### Technical grid

**Only for:** developer-oriented chapters

**Use:** Dark chapter atmosphere.

**Observed:** Fine coral square cells behind mono text and outlined tool chips fade into black.

**Transfer:** Use diagram-like structure rather than neon cyberpunk effects.

**Build:** Layer horizontal and vertical repeating linear gradients with rgba(255,98,87,0.14) 0.5px lines every 40px over #050505. Apply a radial mask so the grid vanishes at the edges; place coral-at-28% 1px outlined chips above it.

### Icons

**Observed:** Rounded outline SVGs commonly 16×16px at 2px stroke and 20×20px around 1.8px stroke, in taupe or warm ink. Chevrons are smaller; service symbols keep their own color. Emoji appear in pale icon wells.

**Transfer:** Use consistent rounded outlines for marketing affordances. Keep colorful marks within ecosystem or product objects.

## Section recipes

How recurring sections are built.

### First screen: Companion and working stage opening

**Observed:** On Canvas, the header has an outer wordmark and account controls with Floating navigation centered between them. After 160px of top breathing room: Announcement badge, then a two-line mixed-face headline across about two thirds of the viewport. Black grotesk clauses anchor the lines and half-opacity serif clauses complete them. A centered two-line hero-support paragraph follows, then Primary button and Secondary button with 12px gap. Below, a monochrome companion peeks above the left of a broad stage; a compact tab row leads into a 1200px application window. Within the first 900px the whole promise, support, actions, companion, tabs and application top are visible. Remaining interface and trust caption fall below.

**Transfer:** Use strong sans for the tangible outcome and serif for its human qualification. Without finished UI, make one coherent workflow mockup in a real rounded frame, retaining an original companion. Pricing-style openings instead use a centered 60px serif heading, reassurance sentence and three offers.

**Avoid:** Do not substitute a side-by-side hero, a full-bleed photograph behind the opening copy, or a working object hidden entirely below the first screen.

**Text style:** `hero-strong` — haffer 900 · 72px/0.95

### Mixed-face chapter pause

**Observed:** Short centered monumental statements occupy open stages. Sans lines surround a 64px serif interjection, or a 75.2px sans statement ends in a 48.8px right-aligned serif tail. Compact product tabs ground the latter variant.

**Transfer:** Use a brief outcome and qualifying phrase as a breathing device between dense stories.

**Text style:** `chapter-strong` — haffer 900 · 75.2px/1

### Capability heading and collection

**Observed:** A 48px serif section-heading and small character sit at the left content edge, with 18px muted support 16px below. Compact filters precede a horizontally extending Capability card strip at 12px gutters. A lower four-card group is shorter.

**Transfer:** Use concrete outcomes and keep the heading independently readable; let overflow suggest more content.

**Text style:** `section-heading` — perfectlyNineties 700 · 48px/1 · tracking 0.02em

### Split working demonstration

**Observed:** A text column faces a roughly 550px landscape-backed product window within 1056px. Text combines outline icon, 48px serif title, 18px description and two compact benefit columns. A related variant encloses selectable rows and demonstration in one 1056×544px Soft panel.

**Transfer:** Make the visible result larger than its explanation. Selected rows expose a useful description; inactive rows stay muted.

### Pastoral quotation

**Observed:** A full-width darkened meadow carries a left-aligned 36px/1.2 serif quotation in an 896px measure, followed by a small portrait, name and role. A following light chapter can rise with 22px rounded top corners.

**Transfer:** Use one credible account in subdued textured scenery, leaving room for its words.

**Text style:** `landscape-quote` — perfectlyNineties 700 · 36px/1.2 · tracking 0.02em

### Trust bento

**Observed:** 48px serif heading introduces a ten-column grid with 12px gutters. Seven Soft panels vary in span and height, with 32px padding. Objects include UI slices, raised keyboard keys, security badge, tall phone and explanatory video.

**Transfer:** Use verifiable trust properties with one illustrative object each; vary spans to fit the proof.

### Object shelf and simple form

**Observed:** Centered serif heading and support lead to Tactile book shelf after 48px. Compatibility labels and logos sit beneath. Selected resource name and description lead to Email field and tall Primary button, followed by reassurance.

**Transfer:** Keep the form subordinate to a useful resource and tangible objects.

### Landscape closing and full footer

**Observed:** Landscape stage is 1056×540px with 18px corners and pale painted sky. A centered 96px outcome overlays a 32px half-opacity serif afterthought shifted right with -16px overlap. Paired actions follow. After 96px, the footer has a wordmark, description, social marks and five loose link groups including a download badge. A faint rule separates copyright and attribution. Both page types share this ending.

**Transfer:** Close with a one- or two-word outcome and short human consequence. Keep the painted monumental device using the Painted horizon fallback when necessary; finish with useful navigation rather than another banner.

**Text style:** `monument` — haffer 900 · 96px/1

### Technical interruption

**Only for:** developer-oriented chapters

**Observed:** Technical field fills a viewport-height chapter with 128px vertical padding. A centered 48px mono coral title, support, rectangular tool chips and paired actions sit on Technical grid.

**Transfer:** Translate tool labels and ecosystem while preserving the local contrast.

**Text style:** `technical-heading` — ui-monospace 900 · 48px/1

### Pricing and comparison

**Only for:** pricing pages

**Observed:** Centered pricing-heading and 18px reassurance introduce three plans. Recommended plan alone is raised. A four-column matrix follows with 56px rows, black-at-8% rules, green checks and neutral crosses in 20px circles. White elevation continues down the recommended column. FAQ uses a two-fifths title column and three-fifths question column.

**Transfer:** Align decision information, elevate only one recommendation and separate offers from detailed comparison.

**Text style:** `pricing-heading` — perfectlyNineties 400 · 60px/1 · tracking 0.02em

## Page flow

**Storyline:** Promise → working proof → capability and ecosystem depth → confidence and objections → tangible next step → pastoral outcome and useful footer.

### Broad product landing with software detail and emotional relief

1. **Promise** — Mixed-face headline, news badge, paired actions and companion above a working stage.
2. **Credibility** — Modest centered trust caption and monumental chapter pause.
3. **Capability depth** — Outcome cards, selectable demonstrations, command cards and tangible packaged modules.
4. **Ecosystem** — Context cards and fading integration rows.
5. **Product demonstration** — Mixed-face chapter statement followed by large text-and-interface scenes.
6. **Social proof** — Extended quotation in a painted meadow.
7. **Technical confidence** — Connected-object field, dark developer chapter and trust bento.
8. **Low-commitment conversion** — Colorful shelf and resource form.
9. **Closing call** — Painted outcome panel and full footer.

**Transfer:** Adapt chapter count to the product; alternate detailed objects with typographic or painterly pauses while retaining the signature devices.

### Decision page for comparing plans

1. **Promise** — Centered serif title and trial reassurance.
2. **Pricing** — Three offers with a raised central plan.
3. **Detailed comparison** — Four-column matrix with continuous recommended-plan elevation.
4. **Objection handling** — Grouped FAQ in a split layout.
5. **Closing call** — Shared painted outcome and full footer.

**Transfer:** Reduce decoration during comparison and restore the pastoral closing for brand continuity.

## Writing

Confident about practical capability, conversational about relief. Everyday work becomes simpler through specific mechanisms rather than abstract transformation.

**Do not copy:** Do not reuse Micro's name, mascot, wordmark, named resources, customer identities, quotations, prices, integration totals, certifications or trial and capability claims. Examples illustrate tone only; replace them with truthful product-specific content and original artwork.

- **Addressing the reader:** Second person for outcomes and reassurance; product name in third person for capability statements.
- **Rhythm:** Short headline clauses followed by one explanatory sentence. Compact labels contrast with occasional long human quotations. Ampersands and fragments feel natural; exclamation marks do not.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Capable thing in a forceful clause, human benefit in a softer continuation. | Two short clauses per line | “An agent to do your work & An everything app to manage it” |
| Capability heading | Product name plus direct verb and familiar outcome. | 5–9 words | “[Brand] automates your repetitive work”<br>“[Brand] takes action when you ask” |
| Support | Explain the mechanism and end with the useful result. | One sentence, 15–25 words | “Choose from real automations that keep follow-ups, records, meetings, and projects moving in the background.” |
| Pricing reassurance | State commitment and exit plainly. | Two short sentences | “Start with a 14-day free trial. Cancel anytime.” |
| Action | Explicit verb-led next step. | 2–4 words | “Request a Demo”<br>“Get the free guide”<br>“Start Free Trial” |
| Closing outcome | Achieved state plus human consequence. | One word plus short sentence | “Organized”<br>“So you don't have to be.” |

**Words and phrasing to use:** your work; connect; organized; take action; built for; moving in the background; ask; find; custom; free

**Avoid:** revolutionary; synergy; unleash limitless potential; next-generation paradigm; disrupt everything

**Rules:**

- Explain a broad promise with a mechanism in the next sentence.
- Use recognizable work examples rather than category buzzwords.
- End forms with concrete delivery or commitment reassurance.
- Let outcome words carry emotion; keep body copy literal.
- Keep technical and trust claims accurate.

## Do's and Don'ts

### Do

- Keep black sans tracking normal and serif tracking at 0.02em.
- Use a 1152px wrapper including 48px desktop side padding.
- Keep 12px card gutters inside chapters with 96px vertical space.
- Pair equal-height 44px actions at a 12px gap.
- Use 14px corners for small objects and 18px for larger stages.
- Make the landscape visibly brush-textured scenery.
- Use 96px closing outcome with an overlapping 32px serif tail.
- Concentrate color in objects, scenery and the technical variant.

### Don't

- Do not make default buttons capsules; use 10px corners.
- Do not make primary marketing actions blue; they are warm charcoal.
- Do not flatten #f5f5f5 canvas and #fafafa cards to one white.
- Do not add dark borders everywhere; edges use black at 8–12%.
- Do not apply coral mono headings to ordinary capability chapters.
- Do not replace tangible books with identical flat tiles.
- Do not inflate software-object spacing; its compact rhythm is 6–12px.
- Do not make every plan heavily shadowed; elevate only the recommendation.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare all-property transitions of 0.15s cubic-bezier(.4,0,.2,1) and active scale 0.98.
- Footer links declare 0.15s color transitions; card wrappers declare 0.3s transform transitions.
- Integration rows use translated content and edge masks; marquee-scroll is declared.
- Large chapter type uses scroll-linked blur, opacity and translation with pinned wrappers.
- Technical grid cells declare background-color and box-shadow transitions of 0.15s.

**Transfer:**

- Use tactile press scaling rather than pronounced floating hover.
- Keep text crisp at rest; blur is only a transition.
- Fade moving object rows at the ends.

**Unknown:**

- Exact marquee timing and complete scroll choreography are not established.

### Responsive

**Observed:**

- Declared width breakpoints: 640px, 768px, 782px, 1024px, 1280px and 1536px.
- Container classes switch 24px and 48px side padding; opening serif clauses become blocks on small screens.
- Opening sans declares 36px, 60px and 72px tiers; closing outcome declares 36px, 60px and 96px tiers.
- Resource form switches column to row at the small breakpoint; footer begins as two columns.
- Bento declares one-, two- and ten-column configurations; comparison declares two and four columns.

**Transfer:**

- Stack mixed-face clauses intentionally rather than shrinking the desktop line.
- Keep scenery attached to the working window when columns stack.
- Retain horizontally browsable 224px cards.
- Stack the form while preserving the smaller monumental closing and right-shifted tail.

**Unknown:**

- Narrow navigation expansion, comparison interaction and final artwork framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
