# Givingli — paper with heart

## Overview

An expressive, tactile style that makes a digital product feel like something chosen and wrapped by a person. Warm paper and espresso brown alternate with confident red and dusty blue chapters; oversized regular-weight grotesk type is balanced by tiny spaced labels and occasional handwritten accents. Cutout objects, illustrated stationery, candid monochrome photography and layered product scenes give the spacious layouts a human, slightly offbeat warmth. It suits consumer products and emotionally led services, with a more restrained, material-rich variation for business software.

### Essentials

- Headlines feel spoken at poster scale: mori at 128px/0.9, weight 400 and -0.045em tracking, with the final benefit isolated in red rather than a heavier weight.
- The opening is an airy paper stage, not a dashboard billboard: a centered headline within 896px, a 672px search capsule above, and tilted objects roughly 250–313px wide floating around its outer edges.
- Actions resemble small seals on paper: fully rounded 56px-high hero buttons with 16px 32px padding, red for the first action and espresso for its companion; smaller navigation actions keep the same pill silhouette.
- Color arrives in whole chapters: cream is the resting canvas, white is the gallery, and red, espresso and dusty blue occupy full-width sections rather than a sprinkling of unrelated colored cards. Preserve at least one red poster-like statement and one dark display stage on a new landing page.
- Digital features become tangible objects: portrait artwork, overlapping cards, envelopes, dashed receipt-like outlines and mono numerals are staged at generous scale. If there is no physical product, turn one meaningful output into a layered paper artifact instead of using generic floating app windows.
- The ending has a monumental typographic signature: a dark espresso footer with compact columns above a white wordmark artwork spanning 1200px by 341px at desktop. Set the new product's own name as a fitted vector word sculpture when no equivalent artwork exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Heart red | `#c42121` | `--color-red` | background, accent, action, text | Headline payoff, primary conversion and entire emotional statement chapters. |
| Espresso | `#210c02` | `--color-ink` | text, background, border, action | Primary lettering, dark chapter backgrounds and companion actions; warmer and browner than black. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty blue | `#5a6a92` | `--color-blue` | background, surface, action | Full-width collection chapters; also the business variant's primary action and step-card base. |
| Soft teal blue | `#9abdcc` | `--color-reaction` | surface | Large human-reaction panels rather than ordinary utility cards. |
| Pale blue | `#d3e6ff` | `--color-ice` | surface, accent | Review cards and small status badges; a cool counterpoint to the brown ink. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft brown text | `#695a50` | `--color-muted` | text | Secondary body copy on paper; brown at 65% opacity over the paper canvas. |
| Faded brown label | `#7e7067` | `--color-label` | text | Small labels on paper; brown at 55% opacity. |
| Paper hairline | `#dbd5cc` | `--color-edge` | border | Brown at 10% opacity over paper; search and catalog edges. |
| Envelope paper | `#f0ebe2` | `--color-canvas` | background, text, surface | Default canvas, paper artifacts and reversed lettering on espresso. |
| Gallery white | `#ffffff` | `--color-white` | background, surface, text, action | Gallery chapters, search fields and reversed headlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| business proof sections | Olive sage | `#909267` | `--color-sage` | surface | Tall business testimonial cards. |
| business product pages | Warm taupe | `#7b6556` | `--color-taupe` | accent, background | Low-opacity atmospheric light mixed with blue over paper. |
| business product pages | Light stationery | `#f6f1ea` | `--color-paper-ui` | surface, background, text | Business marketing panels and warm reversed headings. |

## Typography

- **mori** — All ordinary marketing headings, paragraphs and navigation. Open, rounded contemporary grotesk; light-looking regular display text with tightly joined words. If unavailable, use **DM Sans**. Use 400 for display, 500–600 for controls; retain the tight display tracking. Font stack: "mori", "DM Sans", ui-sans-serif, system-ui, sans-serif.
- **Fragment Mono** — Receipt-like figures, numbered collection headings and technical markings. Monospaced numerals with an unmistakable slashed zero and plain mechanical spacing. Font stack: "Fragment Mono", ui-monospace, SFMono-Regular, Menlo, Consolas, monospace.
- **qekunjar** — Large personal quotation and small handwritten annotations. Loose, narrow handwritten strokes that contrast with the orderly grotesk. If unavailable, use **Caveat**. Use regular weight and a large open line; do not use it for navigation. Font stack: "qekunjar", "Caveat", cursive.
- **romie** (only for business product pages) — Italic audience phrase and delicate editorial captions. High-contrast literary serif in a flowing italic. If unavailable, use **Bodoni Moda**. Use italic 400; tune width before changing size. Font stack: "romie", "Bodoni Moda", ui-serif, Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| poster-number | mori | 400 | 224px | 0.95 | -0.045em | size clamp(5rem, 18vw, 14rem) | A single monumental figure in the emotional poster chapter. |
| step-number | mori | 400 | 176px | 0.85 | -0.05em | size clamp(4.5rem, 14vw, 11rem) | Oversized process numbering on red. |
| display | mori | 400 | 128px | 0.9 | -0.045em | size clamp(3.25rem, 10.5vw, 8rem) | Hero and monumental chapter headings. |
| personal-quote | qekunjar | 400 | 104px | 1.05 | -0.025em | size clamp(2.25rem, 8vw, 6.5rem) | One expressive standalone human quotation. |
| heading-lg | mori | 400 | 96px | 0.95 | -0.04em | size clamp(2.75rem, 8vw, 6rem) | Major explanatory and proof headings. |
| artifact-number | Fragment Mono | 400 | 96px | 1 | -0.025em | size clamp(3.5rem, 10vw, 6rem) | Oversized balance or other meaningful figure on a paper artifact. |
| closing-heading | mori | 400 | 80px | 0.95 | -0.04em | size clamp(2.5rem, 7vw, 5rem) | Centered invitation at the end of shorter pages. |
| heading | mori | 400 | 64px | 0.97 | -0.04em | size clamp(2.5rem, 5.5vw, 4rem) | Alternating feature chapters. |
| step-heading | mori | 400 | 56px | 1.05 | -0.04em | size clamp(2rem, 4.5vw, 3.5rem) | Process step title beside an object. |
| poster-support | mori | 400 | 52px | 1.05 | -0.035em | size clamp(1.75rem, 4vw, 3.25rem) | Short large sentence beneath the poster figure. |
| tile-title | mori | 400 | 40px | 1 | -0.04em | size clamp(1.5rem, 3vw, 2.5rem) | White title over portrait imagery. |
| body | mori | 400 | 18px | 1.625 | normal | fixed | Supporting paragraphs, generally constrained to 512–576px. |
| body-small | mori | 400 | 16px | 1.625 | normal | fixed | Reviews and expanded answers. |
| action | mori | 500 | 16px | 24px | normal | fixed | Hero buttons, inline conversion links and question labels. |
| nav | mori | 500 | 14px | 20px | normal | fixed | Compact navigation and small pills. |
| eyebrow | mori | 600 | 12px | 16px | 0.22em, uppercase | fixed | Small proof or chapter label, 16–20px above heading. |
| chapter-label | mori | 400 | 12px | 16px | 0.22em, uppercase | fixed | Lighter all-caps introductions to broad colored chapters. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling pages | culture-display | mori | 400 | 120px | 0.95 | -0.045em | size clamp(3rem, 10vw, 7.5rem) | Mission opening and split-line proof statements. |
| catalog pages | catalog-display | mori | 400 | 112px | 0.9 | -0.045em | size clamp(3rem, 9vw, 7rem) | Simple category title. |
| business product pages | business-emphasis | romie | 400 italic | 96px | 0.95 | -0.04em | fixed | Italic conclusion to a grotesk section heading. |
| business product pages | business-display | mori | 400 | 93.6px | 0.95 | -0.04em | size clamp(2.75rem, 6.5vw, 6rem) | Compact main promise above an italic audience phrase. |
| business product pages | business-audience | romie | 400 italic | 93.6px | 1.4 | -0.04em | size clamp(2.75rem, 6.5vw, 6rem) | Rotating audience or use-case phrase below the main promise. |
| catalog pages | catalog-number | Fragment Mono | 400 | 56px | 1 | normal | size clamp(2rem, 5vw, 3.5rem) | Two-digit ordinal beside a pale slash and collection title. |
| catalog pages | catalog-heading | mori | 400 | 44px | 1 | -0.03em | size clamp(1.5rem, 3.5vw, 2.75rem) | Collection heading aligned to ordinal baseline. |
| business product pages | business-caption | romie | 400 italic | 16px | 24px | normal | fixed | Delicate section prefaces in place of the usual capital label. |
| business product pages | business-marking | Fragment Mono | 400 | 11px | 1.5 | 0.22em, uppercase | fixed | Feature indexing and closing form introduction. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep display lettering regular rather than bold: the impact comes from size, tight negative tracking and line heights below 1.
- The all-caps labels move in the opposite direction: small 12px type opens to 0.22em tracking. Body paragraphs keep normal tracking.
- Use the handwritten face for human speech, not as a decorative replacement for every heading. Serif italics belong to the business variation.
- The giant footer name is artwork, not another ordinary heading recipe; fit its proportions to the available width.

## Layout

**Density:** Airy at chapter scale, compact within controls: 112–192px section breathing room surrounds tightly grouped labels and actions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label or close metadata gap. |
| 12px | Button-pair and accordion-row gaps. |
| 16px | Chapter label to headline; small internal spacing. |
| 20px | Proof eyebrow to heading; quote-to-rating separation. |
| 24px | Gallery gutters and heading-to-body separation. |
| 28px | Review card padding and navigation gaps. |
| 32px | Paragraph-to-action gap and small horizontal dividers. |
| 40px | Desktop container side padding and section title-to-carousel gap. |
| 48px | Paper artifact padding and footer stack gap. |
| 64px | Large reaction-panel padding and editorial two-part heading gap. |
| 80px | Two-column feature gutter and footer top padding. |
| 112px | Feature chapter vertical padding. |
| 128px | Company and business chapter vertical padding. |
| 192px | Deep gallery and proof-section breathing room. |

### Containers and grids

- **Main container**: max width 1280px · side padding 40px. Centered outer container; at 1440px the content runs across 1200px after its side padding.
- **Wide gallery**: 3 columns · gap 24px · side padding 40px. Full-width portrait gallery with 1360px of inner content at desktop.
- **Feature split**: 2 columns · gap 80px. Two equal 560px areas inside the main container; alternate text and tangible object.
- **Hero copy**: max width 896px. Centered display headline; support copy narrows further to 576px.
- **Review grid**: max width 1216px · 3 columns · gap 24px. Two pale-blue cards flank an espresso card.
- **Business bento** (only for business product pages): 3 columns · gap 20px. A two-column-wide feature beside a narrow proof card, then three smaller feature panels.
- **Business closing split** (only for business conversion sections): max width 1280px · 2 columns · gap 64px · side padding 40px. A narrower promise column beside a 640px paper form; align their tops.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions and search | 9999px (pill) |
|  | Portrait tiles and accordions | 16px |
|  | Review and feature panels | 24px |
| business product pages | Dashboard stage | 12px |
| business product pages | Stationery panels | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Small pill lift | `0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | Hero pills and search field. |
| business product pages | Dashboard lift | `0px 32px 80px rgba(33,12,2,0.22), 0px 14px 28px rgba(33,12,2,0.1), 0px 0px 0px 1px rgba(33,12,2,0.08)` | One large product demonstration rather than every card. |
| business conversion sections | Paper form lift | `0px 30px 80px rgba(0,0,0,0.45)` | Light form on an espresso closing band. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f0ebe2; color: #210c02`

**Observed:** Flat warm paper supports most text-led sections.

**Transfer:** Let the color suggest stationery; avoid adding texture to every cream area.

#### Red chapter · level 0

**Use:** Emotional statements, process demonstrations and editorial chapters.

**CSS:** `background: #c42121; color: #ffffff`

**Observed:** Continuous edge-to-edge fields, with no border or rounding around the section itself.

**Transfer:** Use a whole red field for one clear message, with white type and substantial empty area.

#### Espresso stage · level 0

**Use:** Conversion chapters, dark display trays and footer.

**CSS:** `background: #210c02; color: #f0ebe2`

**Observed:** Full-width bands are square-edged; inset collection trays use 24px corners.

**Transfer:** Use the warm dark brown rather than neutral black.

#### White gallery · level 0

**Use:** Artwork grids and functional catalog content.

**CSS:** `background: #ffffff; color: #210c02`

#### Blue collection · level 0

**Use:** Popular-artwork display chapter.

**CSS:** `background: #5a6a92; color: #f0ebe2`

**Observed:** A flat dusty-blue field surrounds an inset espresso tray.

**Transfer:** Keep the backing subdued so the artwork supplies the sharp colors.

#### Receipt artifact · level 1

**Use:** Explain a balance, aggregate, allocation or other numerical benefit.

**CSS:** `background: #f0ebe2; border: 1px dashed rgba(33,12,2,0.25); border-radius: 24px; padding: 48px`

**Observed:** A large mono number sits between small uppercase markings and a dashed divider; smaller related artifacts repeat below.

**Transfer:** Make a real product output legible as a paper object.

#### Business feature paper · level 1

**Only for:** business product pages

**Use:** Bento feature explanations.

**CSS:** `background: #f6f1ea; border: 1px solid rgba(33,12,2,0.06); border-radius: 6px; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.5), 0px 18px 44px -24px rgba(33,12,2,0.18)`

**Observed:** Subtle square grid lines sit behind miniature explanatory graphics.

**Transfer:** Use a barely visible drafting-paper grid, not a dense technical graph.

#### Business atmospheric paper · level 0

**Only for:** business product pages

**Use:** Hero and onboarding scenes.

**CSS:** `background: radial-gradient(70% 50% at 25% 20%, rgba(211,230,255,0.5) 0%, rgba(211,230,255,0) 65%), radial-gradient(70% 50% at 80% 25%, rgba(123,101,86,0.22) 0%, rgba(123,101,86,0) 65%), #f0ebe2`

**Observed:** Blue, cream and taupe light pools soften a material-rich paper background.

**Transfer:** Keep the light diffuse and low-contrast rather than neon.

## Components

### Sticky navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 30; background: #f0ebe2; height: 80px`

**Text style:** `nav` — mori 500 · 14px/20px

**Observed:** Logo at left; personal/business segmented switch followed by four compact links; login and dark action at right. The inner row is 1280px wide with 32px side padding. A separate 40px espresso announcement strip sits above the navigation at entry.

**Transfer:** Use the segment switch only when the product truly serves two audiences; keep the centered link cluster compact.

### Primary button

**Use:** First conversion action on the default marketing opening.

**CSS:** `background: #c42121; color: #ffffff; border-radius: 9999px; padding: 16px 32px; height: 56px; box-shadow: 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `action` — mori 500 · 16px/24px

**Observed:** Short text-only red pill, paired with the dark companion action. Smaller navigation actions use 14px text and 8px 16px padding.

**States:** Declared: hover background-color color-mix(in oklab, #c42121 90%, transparent); focus-visible not specified.

### Companion button

**Use:** Secondary hero action and conversion on light sections.

**CSS:** `background: #210c02; color: #f0ebe2; border-radius: 9999px; padding: 16px 32px; height: 56px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action` — mori 500 · 16px/24px

**Observed:** A right arrow follows the label. On red or dark chapters, supporting actions invert to white pills; business conversion actions use dusty blue.

**States:** Declared: hover background-color color-mix(in oklab, #210c02 90%, transparent); focus-visible not specified.

### Search capsule

**Use:** Prominent product discovery above the hero or catalog.

**CSS:** `background: #ffffff; border: 1px solid rgba(33,12,2,0.1); border-radius: 9999px; padding: 16px 24px; max-width: 672px; height: 58px; display: flex; align-items: center; gap: 12px; box-shadow: 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Observed:** A small outlined magnifier precedes a borderless transparent input. The field is an independent centered object, not a full-width toolbar.

**Transfer:** For a non-searchable product, substitute a single useful input or compact action capsule in the same visual position.

### Portrait category tile

**Use:** Visually browse a collection of outcomes.

**CSS:** `position: relative; aspect-ratio: 4 / 5; overflow: hidden; background: #210c02; color: #ffffff; border-radius: 16px`

**Text style:** `tile-title` — mori 400 · 40px/1 · tracking -0.04em

**Observed:** An object-cover image fills the tile; brown-to-transparent overlays darken the top and bottom. The title sits 24px inside the upper left; a tiny uppercase browse label sits at the lower left. Images gently enlarge on hover.

**Transfer:** Create a product-specific paper composition for each category, not a flat color tile with a stock icon.

### Review card

**Use:** Readable personal proof against photography.

**CSS:** `background: #d3e6ff; color: #210c02; border: 1px solid #210c02; border-radius: 24px; padding: 28px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px`

**Text style:** `body-small` — mori 400 · 16px/1.625

**Observed:** Five red stars above a short quotation; a small circular avatar and name anchor the bottom. An espresso card with pale text interrupts each three-card row.

**Transfer:** Use authentic concise quotes; retain the alternating contrast instead of a uniform wall of pale cards.

### Question accordion

**Use:** Objection handling near the end of a landing page.

**CSS:** `background: #210c02; color: #ffffff; border-radius: 16px; padding: 16px 24px; min-height: 56px; display: flex; align-items: center; justify-content: space-between; gap: 16px`

**Text style:** `action` — mori 500 · 16px/24px

**Observed:** Stacked details rows have 12px gaps. A plus sign at the right rotates 45 degrees when open; answer text uses body-small, 24px side padding and 20px bottom padding.

**Transfer:** Keep the answer attached to the same dark rounded container, not in a separate white popover.

### Monumental footer

**Use:** Final brand impression after the conversion and supporting content.

**CSS:** `background: #210c02; color: #ffffff; padding: 80px 40px 48px`

**Observed:** Within a 1280px outer container, a small symbol leads three columns of links, contact and social actions with 40px gutters. A white name artwork spans 1200px by 341px below; a fine white-at-10% rule separates the legal row. Social buttons are 36px circles.

**Transfer:** Use the new product name as broad vector lettering; preserve the substantial name-to-links scale contrast.

### Business proof card

**Only for:** business proof sections

**Use:** Company-level testimonial grid.

**CSS:** `background: #909267; color: #ffffff; border-radius: 6px; padding: 32px; display: flex; flex-direction: column; gap: 24px`

**Observed:** Tall 285px by 502px cards in a four-column row. White stars lead a company name, quotation and bottom attribution. Type stays regular, not bold.

**Transfer:** Keep this restrained olive variation distinct from the blue-and-brown consumer review cards.

### Stationery conversion form

**Only for:** business conversion sections

**Use:** Consultative closing action.

**CSS:** `background: #f0ebe2; color: #210c02; border-radius: 6px; max-width: 640px; box-shadow: 0px 30px 80px rgba(0,0,0,0.45); overflow: hidden`

**Observed:** A cream sheet sits on the espresso band beside a large promise. Dark rounded binder perforations run down its left edge. A small emblem and human quotation lead numbered uppercase mono labels, underline-only fields and a dark pill submit. The form content scrolls inside the sheet.

**Transfer:** Rebuild as a simple paper sheet with perforations and understated rules; keep the form useful rather than making the paper effect obstruct fields.

## Imagery and graphics

### Tangible product cutouts

**Use:** Hero satellites and alternating product chapters.

**Observed:** Tilted gift cards, open envelopes with illustrated greetings, and isolated physical objects sit directly on cream or red. They have crisp cutout edges, soft natural shading and no generic browser frame; hero objects are secondary to the headline.

**Transfer:** Photograph or render meaningful outputs from the new product as tactile objects. At minimum, create two original paper cards with genuine content and a softly shaded envelope or folded backing.

**Build:** Use transparent PNGs or SVG groups with rounded rectangular cards about 250–310px wide, rotated in opposing directions by roughly 8–12 degrees. Layer a cream polygon envelope behind one card, add a soft low-opacity brown shadow below the overlap, and keep the central headline clear.

### Stationery portrait compositions

**Use:** Category grids and collection browsing.

**Observed:** A 4:5 scene pairs illustrated paper with a branded card, envelope or photographic object. Soft blue, cream, red and gray backings are lit like small studio still lifes; a dark edge gradient makes white titles readable.

**Transfer:** Compose original outputs with one supporting object and one colored backing per category. Keep the same ratio and tactile lighting even if the subject is software.

**Build:** Place a softly shaded paper rectangle in the middle of a 4:5 SVG or image canvas, a second smaller card overlapping its lower third at a slight angle, and an envelope polygon behind. Add a brown transparent-to-dark gradient at both ends for labels.

### Human photography and collage

**Use:** Personal proof and editorial imagery.

**Observed:** Candid celebration photography is monochrome and fills the proof section behind blue and espresso reviews. Editorial cards mix close-up paper, handwriting, ribbons, fashion-like crops and layered instant-photo borders; people look caught in a real moment rather than posed for a corporate portrait.

**Transfer:** Use warm, candid human context for the new product. Convert busy background photography to black and white; preserve color for paper artwork and product outputs.

### Handwritten testimony

**Use:** Emotional pause between product explanation and further browsing.

**Observed:** A large centered handwritten quotation occupies an 896px column with a small spaced label and restrained attribution. A separate reaction scene pairs a tall conversation image with oversized regular text inside a soft-blue 24px-radius panel.

**Transfer:** Use one believable verbatim reaction, with personal language and small imperfections, and one legible contextual image instead of a fabricated testimonial.

**Build:** Set the quote in the personal-quote recipe, constrain it to 896px, use brown ink on cream and leave 32px between label, quotation and attribution.

### Footer word sculpture

**Use:** Signature at the bottom of default marketing and catalog pages.

**Observed:** A giant flat white name spans the available 1200px width, with a visible artwork height of 341px. It dominates the footer much more than the link columns.

**Transfer:** Create a clean SVG of the new name fitted to the same wide stage; for a very long name use a custom condensed or stacked composition while retaining the monumental area.

**Build:** Use an SVG viewBox matching the name's proportions, convert fitted grotesk lettering to paths when available, fill white, set width to 100% and preserve its aspect ratio. Leave a 48px-scale gap around the artwork.

### Textured business materials

**Only for:** business product pages

**Use:** Audience chapters, product choices and onboarding cards.

**Observed:** Dusty blue fibrous paper, pale cream creases and olive bookcloth-like surfaces carry subtle wear and grain. Product cards hover above these materials with warm shadows. Atmospheric blue and taupe glows remain behind the main content rather than crossing text.

**Transfer:** Use subtle original paper textures or procedural grain; keep them much softer than the product imagery.

**Build:** Overlay a monochrome SVG feTurbulence grain on a blue or cream base with multiply blending at 0.18–0.3 opacity. Add broad radial blue light at 25% 20% with 0.5 alpha fading to zero by 65%, and taupe light at 80% 25% with 0.22 alpha. Keep the grain fine and the contrast low.

### Red material proof tiles

**Only for:** company storytelling proof sections

**Use:** A compact quantified proof wall.

**Observed:** Three 282px square red tiles have subtly different fabric or paper textures; 32px cream claims sit high with short captions pinned low. An outlined fourth tile is an action, not another statistic.

**Transfer:** Use verified measures in a small material-backed proof set; retain one outlined action tile rather than adding another invented number.

**Build:** Create red square panels with 16px corners, overlay a fine monochrome grain or very faint vertical fabric streaks, and lay text in a top-and-bottom flex column. The action tile has no fill and a 1px cream-at-80% outline.

### Icons

**Observed:** Small functional arrows and chevrons are rounded outline strokes, usually 14–20px with 2–2.5px strokes. Stars are filled red on pale consumer proof and white on olive business proof. Social glyphs are white within small translucent circular buttons.

**Transfer:** Use simple rounded outline icons at the same scale as control text; reserve solid shapes for ratings and status marks. Business illustrations can enlarge the same sparse outline vocabulary with a single dusty-blue detail.

## Section recipes

How recurring sections are built.

### First screen: Paper stage opening

**Observed:** A 40px espresso announcement strip and 80px cream Sticky navigation lead into the Paper canvas. A centered Search capsule appears near the top of the stage, followed by a broad expanse of cream. Two cutout objects flank a centered 896px headline column: a tilted card at upper left and an illustrated card emerging from an envelope at upper right, each around one fifth of the viewport width. The 128px regular headline wraps into a compact three-line mass with the final payoff red. A 576px support line follows by 32px. Within the first 900px the navigation, search, two main objects, complete headline and support are visible; the paired Primary button and Companion button, work-oriented link and further floating objects continue below the fold. The whole opening extends beyond one viewport rather than forcing all actions onto its first screen.

**Transfer:** Keep the same headline-first still life for a different product using two meaningful outputs as paper artifacts. Place actions directly beneath the support even when they fall below the initial viewport. Catalog openings compress to a single 112px category title, centered explanation and search. Company storytelling opens with a 120px mission statement over paired portraits; business pages use the smaller business-display and italic audience phrase, side objects, an email capsule and demo tabs.

**Avoid:** Do not replace this with a left-aligned SaaS headline beside a giant laptop mockup, or fill the cream breathing room with decorative feature badges.

**Text style:** `display` — mori 400 · 128px/0.9 · tracking -0.045em

### Alternating product chapter

**Observed:** Feature split combines a numbered label, 64px heading, 18px support and a short pill action with one large isolated object. Use 20px label-to-heading, 24px heading-to-copy and 32px copy-to-action gaps. Chapters alternate red, cream and espresso with 112px vertical padding.

**Transfer:** Explain one mode or benefit per composition; reverse media and text to maintain rhythm without turning every section into a card grid.

**Text style:** `heading` — mori 400 · 64px/0.97 · tracking -0.04em

### Process theater

**Observed:** A Red chapter begins with a monumental heading and larger support sentence. A viewport-height sticky scene puts a 176px step number at one side, an oversized tangible demonstration in the middle, and a 56px heading with small label and body at the other. Circular previous/next controls and a white conversion pill sit below. Later steps swap left/right emphasis.

**Transfer:** Show a few concrete actions on the product's output; use staged cards or a meaningful conversation rather than a numbered list alone.

**Text style:** `step-heading` — mori 400 · 56px/1.05 · tracking -0.04em

### Gallery chapter

**Observed:** A White gallery has a centered chapter-label and 128px heading, then 128px of separation before Portrait category tiles in a three-column 24px-gutter grid. Short 40px text links form a loose row beneath the artwork.

**Transfer:** Group outcomes visually; keep the number of tiles proportional to the new catalog and preserve portrait scale.

**Text style:** `display` — mori 400 · 128px/0.9 · tracking -0.045em

### Receipt explanation

**Observed:** A two-column White gallery pairs a 128px multi-line heading and restrained body with the Receipt artifact. Small divided benefit captions sit beneath the text. A dashed large balance card breaks into three smaller paper cards with mono figures.

**Transfer:** Visualize aggregation, customization or distribution as physical paper rather than reproducing a detailed account screen.

**Text style:** `artifact-number` — Fragment Mono 400 · 96px/1 · tracking -0.025em

### Human proof pause

**Observed:** An editorial heading occupies about two thirds of a 12-column line, while a short aside sits in the right third, separated by 64px. A thin brown rule leads to a 1200px blue reaction panel with 64px padding; a tall conversation image is paired with a large quoted reaction. The standalone Handwritten testimony follows on cream.

**Transfer:** Let lived language and a real artifact of use interrupt the product pitch; preserve the contrast between orderly heading and expressive quotation.

**Text style:** `heading-lg` — mori 400 · 96px/0.95 · tracking -0.04em

### Editorial and collection trays

**Observed:** A Red chapter houses a large heading, short support and a 24px-radius Espresso stage holding portrait editorial cards. A separate Blue collection uses a split heading stretched toward both edges, centered support, a white toggle capsule and another dark tray of artwork with tiny mono sequence labels and creator names.

**Transfer:** Use one tray for related stories or outputs, with a visible next control and a closing browse action. Preserve the broad colored surround rather than boxing the whole chapter in a white card.

**Text style:** `display` — mori 400 · 128px/0.9 · tracking -0.045em

### Photographic review wall

**Observed:** Monochrome candid photography fills the background behind a white 128px heading. Review card rows alternate with cream press panels that join an image half and a text half inside a 24px outline. The reviews use a three-column 24px-gutter layout and red stars.

**Transfer:** Balance several short personal reactions with one stronger editorial endorsement. Use original context photography and verified attribution.

**Text style:** `display` — mori 400 · 128px/0.9 · tracking -0.045em

### Emotional poster

**Observed:** A full-width Red chapter first centers a 224px figure above a 52px sentence in a 768px column. The scene resolves into a large white two-line emotional invitation with one espresso action. The sticky presentation gives the message the scale of a poster, not a dashboard metric.

**Transfer:** Include a bold red statement device, using a verified meaningful number or an equally short human outcome when no numeric claim fits. Let the new page decide its position and frequency.

**Text style:** `poster-number` — mori 400 · 224px/0.95 · tracking -0.045em

### Questions and social runway

**Observed:** On cream, a very large stacked heading and a translucent help strip occupy the left; Question accordion rows occupy the right with 64px separation. A social handle and horizontal square-image strip follow before the Monumental footer.

**Transfer:** Use real objections in the questions; end supporting content with a small curated human or product gallery, not an unrelated promotional banner.

**Text style:** `display` — mori 400 · 128px/0.9 · tracking -0.045em

### Short closing invitation

**Observed:** Shorter pages close with an 80px centered invitation and one pill, with 128px top and bottom padding. Catalog pages reverse it onto espresso; company storytelling keeps it cream before the dark Monumental footer.

**Transfer:** Make the final action a simple continuation of the page's purpose. Keep the footer's oversized identity even when the rest of the page is brief.

**Text style:** `closing-heading` — mori 400 · 80px/0.95 · tracking -0.04em

### Numbered catalog rail

**Only for:** catalog pages

**Observed:** On white, a 56px Fragment Mono ordinal, pale slash and 44px heading share a baseline with 24px gaps. A shop-all link or 44px circular arrows sit at the opposite edge. A 40–56px gap leads to horizontally overflowing portrait artworks or landscape card tiles, spaced 24px apart; creator names sit below rather than on a colored caption bar.

**Transfer:** Use baseline numbering to organize multiple collections; show a partial next item to communicate horizontal browsing.

**Text style:** `catalog-heading` — mori 400 · 44px/1 · tracking -0.03em

### Company story and proof wall

**Only for:** company storytelling pages

**Observed:** A cream opening pairs a centered mission statement with two 478px by 598px portraits. A smaller founder collage and story share a split below. A red statement pairs huge white type with an envelope object; three rounded white product cards lead into a white values section. The proof wall reverses to espresso with a loosely split 120px phrase over Red material proof tiles.

**Transfer:** Use the same material-rich alternation for the new company's motivation, product breadth and verified scale without importing a fixed list of topics.

**Text style:** `culture-display` — mori 400 · 120px/0.95 · tracking -0.045em

### Business product stage

**Only for:** business product pages

**Observed:** A 72px sticky cream header leads to a centered 93.6px grotesk promise and equally sized italic audience phrase over Business atmospheric paper. Side objects flank short support and a single email/demo capsule with a separate sign-in pill. Feature tabs, a 44px demo title, caption and small indexed arrows introduce a 1240px by 612px dashboard stage with 12px corners and a deep warm shadow.

**Transfer:** Keep the main interface readable and singular; follow with a compact dark logo band instead of adding several tiny competing mockups.

**Text style:** `business-display` — mori 400 · 93.6px/0.95 · tracking -0.04em

### Business material chapters

**Only for:** business product pages

**Observed:** A grotesk heading with italic final phrase introduces a Business feature paper bento. A blue textured audience band uses cream headings, white tabs and pale illustrated cards. Cream textured product-choice panels and an olive material feature alternate with a dark inline email conversion. An onboarding rail uses 384px-wide cards with 4:5 cream art above dusty-blue text bases.

**Transfer:** Use texture, outlined diagrams and staged outputs to warm functional software explanations; keep this smaller-radius business vocabulary separate from the default consumer tiles.

**Text style:** `heading-lg` — mori 400 · 96px/0.95 · tracking -0.04em

### Business paper-form ending

**Only for:** business conversion sections

**Observed:** A four-column olive proof grid leads into an espresso closing band with 128px vertical padding. The left promise is set large above three small mono reassurance lines. The Stationery conversion form occupies the right. A compact five-part business footer continues the same dark field with product identity and four link groups; it does not use the giant consumer wordmark.

**Transfer:** For consultative products use the paper-form ending and compact business footer as a complete scoped alternative to the default monumental ending.

**Text style:** `business-marking` — Fragment Mono 400 · 11px/1.5 · tracking 0.22em · uppercase

## Page flow

**Storyline:** Human promise → tangible demonstration → breadth of outcomes → personal or professional proof → confidence-building details → emotionally direct invitation → strong identity ending.

### Broad consumer marketing landing page

1. **Promise** — Paper stage, floating artifacts, red payoff and discovery input.
2. **Product demonstration** — Alternating colored feature chapters and red numbered process theater.
3. **Breadth** — White portrait gallery and paper-based explanation of flexible value.
4. **Personal proof** — Reaction scene, handwritten quotation and editorial browsing tray.
5. **Social proof** — Artwork rail followed by monochrome photographic reviews and press panels.
6. **Closing call** — Red monumental figure transforms into an emotional invitation.
7. **Objection handling and identity** — Cream FAQ, social-image runway and giant white name on espresso.

**Transfer:** Borrow the emotional-to-functional alternation, not the page's length; maintain tactile demonstrations and a strong identity ending.

### Browsable product catalog

1. **Orientation** — Breadcrumb, centered category title, short explanation and search on cream.
2. **Discovery** — White category-pill band and numbered landscape product rail.
3. **Selection** — Portrait artwork rail with creator captions, followed by visual category tiles.
4. **Closing call** — Centered espresso invitation with a white action.
5. **Identity** — Three-column footer and monumental name artwork.

**Transfer:** Use numbered rails to organize a new catalog without turning it into a dense marketplace grid.

### Company and brand story

1. **Belief** — Centered mission statement over paired portraits.
2. **Human origin** — Small founder collage beside a substantial narrative.
3. **Brand promise** — Full red statement with a tangible envelope-like object.
4. **Product breadth** — Three white rounded cards with rich images and small numbered badges.
5. **Principles** — White editorial heading over four restrained text columns.
6. **Quantified proof** — Split monumental phrase and red material proof tiles on espresso.
7. **Closing call and identity** — Cream invitation before the large-name footer.

**Transfer:** Use real human material and a distinct proof wall for a new company; select principles and facts that are actually relevant.

### Business product and lead-generation landing page

1. **Promise** — Grotesk-plus-italic audience headline, light pools and compact email action.
2. **Product demonstration** — Tabbed dashboard stage with deep warm shadow.
3. **Social proof** — Narrow espresso logo ticker.
4. **Capabilities** — Bento paper panels with small explanatory diagrams.
5. **Audience fit and options** — Textured blue audience chapter, cream product choices and olive material feature.
6. **Conversion and onboarding** — Dark inline email call followed by illustrated numbered step rail.
7. **Professional proof** — Four tall olive testimonial cards.
8. **Closing call and identity** — Espresso promise beside a perforated paper form, then compact business link footer.

**Transfer:** Use this scoped treatment for business software: more material detail, smaller corners, serif italics and consultative conversion, while keeping the warm brown foundation.

## Writing

Warm, emotionally perceptive and conversational, with confident short promises and practical explanations. It makes ease feel personal rather than frictionlessly corporate; playful asides add humanity without making every line a joke.

**Do not copy:** Do not reuse Givingli names, logos, proprietary artwork, partner logos, customer quotations, review counts, gift-card counts, performance claims or the universal percentage claim. Supply the new product's own assets, substantiated facts and permissions. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Talk directly to you and the people affected by your action. Use we for the company viewpoint, and the product name sparingly where functional clarity needs it.
- **Rhythm:** Headlines tend toward 3–9 words with direct verbs; longer emotional headings break into two or three tight lines. Support is usually one or two plain sentences. Short fragments and triplets provide emphasis; customer speech can remain informal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Simple action or belief with a compact emotional or speed payoff. | 4–9 words | “Send the perfect gift, instantly.”<br>“We make gifting feel like it matters.” |
| Supporting line | Explain what can happen, then remove a concrete obstacle. | 15–35 words | “Send by text or email now, or schedule it for later. They open it on any device. No app required.” |
| Chapter heading | Plain benefit expressed as a short instruction or human outcome. | 3–10 words | “Stack your gifts.”<br>“This is what they'll say when you remember.” |
| Eyebrow | Small framing phrase, sometimes rhythmic fragments. | 3–8 words | “For any budget. Any person. Any occasion.”<br>“Real texts. Real people.” |
| Primary action | Direct verb plus concrete object; no inflated urgency. | 2–4 words | “Start Gifting”<br>“Book a Demo” |
| Reassurance | Short precise terms that lower the cost of trying. | 5–12 words | “Book a 15-minute demo. No commitment, no minimums.” |

**Words and phrasing to use:** thoughtful; show up; feel; choose; your people; anywhere; actually; a little; no guesswork

**Avoid:** revolutionary ecosystem; unlock synergy; supercharge everything; industry-disrupting; limited-time urgency

**Rules:**

- Start with a human result, then explain the practical mechanism.
- Name real places and moments when helpful; use ordinary speech rather than abstract audience segmentation in consumer copy.
- Use a small playful aside after a serious benefit, not as a substitute for product clarity.
- Distinguish expressive sentiment from factual proof; quantitative copy must be supportable.
- Keep button labels concrete and short enough to remain compact pills.

## Do's and Don'ts

### Do

- Set the principal display at weight 400 with -0.045em tracking and a 0.9 line height.
- Keep support copy close to 18px/1.625 and roughly 576px wide.
- Use 24px gallery gutters and 80px two-column feature gaps at desktop.
- Let red occupy a complete statement chapter rather than limiting it to tiny buttons.
- Keep hero actions fully rounded at 56px high and pair red with espresso.
- Make at least one meaningful product output tangible with overlapping paper, dashed lines or mono figures.
- Retain the oversized white name artwork in the default dark footer.
- Keep blue review panels at 24px radius with a brown 1px edge and 28px padding.

### Don't

- Do not turn the regular display into 700-weight headings; that removes its open, humane character.
- Do not replace espresso #210c02 with generic neutral black across the page.
- Do not use purple-blue neon gradients as the default canvas; the primary look is flat warm paper and solid chapters.
- Do not give all components the same radius: pills, 16px portrait tiles and 24px proof panels have distinct roles.
- Do not use tiny three-across browser windows as a substitute for the large tangible demonstrations.
- Do not add thick gray borders to pale panels; 1px low-alpha brown rules are sufficient outside the deliberate review outlines.
- Do not apply the business serif italic or 6px bento corners indiscriminately to ordinary consumer sections.
- Do not reduce the default footer to a small logo and legal links; its name artwork is a major visual event.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare 0.15s transitions with cubic-bezier(.4, 0, .2, 1). Portrait tile images declare a 0.5s transform transition and 1.03 hover scale.
- Process and emotional-poster chapters use viewport-height sticky scenes with changing content.
- Business step cards declare a 5s ease-in-out infinite float; logo ticker declares 35s linear infinite movement. Product still lifes declare slow 8s or 18s ease-in-out motion.

**Transfer:**

- Keep the paper objects gently alive while the headline remains easy to read; retain the portrait tile's very small hover enlargement.
- Use a red sticky presentation only where a changing demonstration or statement justifies the stage; preserve a coherent static composition as the resting state.

**Unknown:**

- Exact transform amplitudes and all scene-transition timings are not established.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Main containers use 24px narrow padding and 40px desktop padding; the wide desktop navigation appears at 1024px. The hero search is hidden below 768px.
- Feature splits declare one column before their two-column layout. The portrait category grid declares two columns before three at 768px. Review grids move from one to two to three columns.
- The large sticky process demonstration is desktop-only from 768px; hero actions stack before a horizontal arrangement from 640px.

**Transfer:**

- Keep portrait objects large enough to read; remove peripheral hero satellites before shrinking the main promise into a dense cluster.
- Carry collection rails into horizontal touch browsing rather than reducing every artwork to thumbnail size.
- Use the supplied clamp formulas for display type; fit the monumental footer name to the available width.

**Unknown:**

- Full narrow-screen compositions, menu behavior and alternate mobile process presentation are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
