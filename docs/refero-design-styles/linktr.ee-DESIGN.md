# Linktree — big blocks, playful worlds

## Overview

An exuberant, approachable style for products that help people create, share and grow. Heavy rounded grotesk headlines sit on full-bleed lime, blue, burgundy and lilac fields, balanced by warm off-white proof sections. Human photography, dimensional interface collages and candy-colored cards make the product feel tangible; spacious chapters give way to denser comparison and educational content.

### Essentials

- Billboard language in a friendly heavy grotesk: 80px/1.07 weight 800 opening type with -0.02em tracking; 56px/1.06 weight 700 section headlines, not thin display lettering.
- An asymmetric opening with a living visual tower: two 616px columns separated by 64px at desktop, left-aligned promise and conversion form opposite vertically clipped 576px photographic scenes. Use staged product outputs with people or physical props when equivalent photography is unavailable.
- Color is architecture, not decoration: full-width lime, blue and burgundy chapters carry the early product story, with off-white carrying the central proof and card areas and deep purple closing the page. Use one dominant flat field per chapter rather than a uniform neutral canvas with tiny accent marks.
- Soft controls contrast with blunt fields: 300×60px pill actions, a white 290×60px input with 8px corners, and a floating white 90px-high navigation capsule.
- Product worlds float rather than sit in browser chrome: layered interface cards, isolated objects and small stat tiles fill roughly half a split section, backed by the section color. A minimum version uses three overlapping rounded output cards and one tangible object.
- Proof has a shape vocabulary: a centered claim with a blue category word, edge-clipped 400px-high portrait/logo tiles with mixed pill and rounded-rectangle masks, and wide capsule portraits above headline-sized quotes.
- The ending is a second brand scene: purple field, lilac 56px closing line, oversized edge-cut silhouette artwork, a lime claim action and a white four-column footer panel with 16px corners and 64px padding. Recreate the silhouettes with product-relevant outlines when portraits are unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Chartreuse | `#d2e823` | `--color-lime` | background, action, text, accent | Opening canvas, bright buttons, highlighted comparison headers and headlines on blue. |
| Dahlia | `#502274` | `--color-purple` | background, text | Closing canvas, paired with lilac. |
| Lavender | `#e9c0e9` | `--color-lilac` | background, surface, text, action | Burgundy chapter lettering, soft action variant, benefit bands and cards. |
| Currant | `#780016` | `--color-burgundy` | background, surface, text, action | Dark product chapters, default FAQ field and instructional cards. |
| Hydrangea | `#2665d6` | `--color-blue` | background, text | Product demonstration field and category word under proof claims. |
| Forest | `#254f1a` | `--color-forest` | text, action | Opening headline and button on lime. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light green | `#e8efd6` | `--color-sage` | background | Pale analytics chapter paired with ink and lilac. |
| Iris | `#061492` | `--color-iris` | background, surface, action | Tall bento card and dimensional design demonstrations. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text, background | Navigation, input, footer panel, light cards and comparison canvas. |
| Marble | `#f3f3f1` | `--color-canvas` | background, text | Off-white proof and reading canvas; light lettering on dark scenes. |
| Navigation hairline | `#d3d3d3` | `--color-nav-edge` | border | Visible black at 0.173 over white around the navigation. |
| Concrete | `#676b5f` | `--color-muted` | text, link | Secondary reading copy and footer links. |
| Deep currant | `#54000f` | `--color-faq-dark` | surface | Visible black at 0.3 over burgundy in FAQ rows. |
| Shade | `#1e2330` | `--color-ink` | text, action, background, border | Default text and dark controls; also an inset educational panel. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| outcome-focused solution campaigns | Orchid | `#cc01dd` | `--color-orchid` | background | High-intensity campaign canvas paired with off-white and lime. |
| commerce capability chapters | Goldenrod | `#d6a336` | `--color-gold` | background | Warm commerce demonstration canvas. |
| commerce capability chapters | Root | `#4c2e05` | `--color-root` | background, text, action | Brown chapter canvas or brown controls on lime and gold. |
| pricing pages | Plan lavender light | `#f6f2ff` | `--color-plan-light` | surface | First gradient stop for the recommended plan. |
| pricing pages | Plan lavender shade | `#e8e1f7` | `--color-plan-deep` | surface | Second recommended-plan gradient stop. |
| pricing pages | Electric violet | `#7f22fe` | `--color-plan-action` | action | Recommended-plan action. |
| pricing pages | Deep electric violet | `#7008e7` | `--color-plan-hover` | action, border, text | Recommended-plan ring and action hover. |
| pricing pages | Plan gradient gray | `#f7f7f7` | `--color-plan-gray` | surface | Subtle ordinary-plan gradient end. |

## Typography

- **Linksans** — All marketing headings, prose and controls. Broad, friendly grotesk with circular counters, blunt terminals and very heavy display cuts; regular text remains compact and readable. If unavailable, use **Inter**. Use 400, 500, 700 and 800; preserve tight display spacing and rebalance line breaks. Font stack: "Linksans", "Linksans Fallback", Inter, ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Linksans | 800 | 80px | 1.07 | -0.02em | fixed | Opening promise, balanced across about three lines. |
| heading | Linksans | 700 | 56px | 1.06 | -0.02em | size clamp(20px, 4vw, 56px) | Section leads, closing line and large customer quotes. |
| category-word | Linksans | 700 | 56px | 1.28 | -0.02em | size clamp(20px, 4vw, 56px) | Centered blue category word directly below proof headline. |
| card-heading | Linksans | 500 | 28px | 1.3 | -0.01em | fixed | Bento tile captions anchored beneath imagery. |
| footer-heading | Linksans | 500 | 24px | 1.5 | normal | fixed | Footer column names. |
| question | Linksans | 500 | 20px | 1.5 | -0.01em | fixed | Accordion questions. |
| body | Linksans | 400 | 18.2px | 1.5 | -0.02em | size clamp(14px, 1.29vw, 19px) | Supporting paragraphs beside demonstrations and attribution lines. |
| action | Linksans | 500 | 16px | 1.5 | normal | fixed | Main conversion actions. |
| body-small | Linksans | 400 | 16px | 1.5 | normal | fixed | Accordion answers and compact reading copy. |
| footer-link | Linksans | 400 | 13px | 1.5 | -0.013em | size 0.928vw | Footer link lists. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| quantified feature proof | stat-callout | Linksans | 700 | 80px | 1 | -0.02em | fixed | Centered multiplier plus a short outcome phrase, with the multiplier in burgundy. |
| pricing pages | pricing-display | Linksans | 800 | 48px | 1.1 | -0.04em | fixed | Compact centered pricing promise. |
| feature landing pages | stat | Linksans | 500 | 40px | 1.3 | -0.01em | fixed | Four-up short metrics in white rounded cards. |
| pricing pages | plan-title | Linksans | 800 | 36px | 1 | -0.015em | fixed | Plan names in tinted card headers. |
| educational and pricing pages | compact-card-heading | Linksans | 500 | 24px | 1.3 | -0.01em | size clamp(18px, 1.67vw, 28px) | Repeated benefit, tutorial and resource cards. |
| feature and solution landing pages | eyebrow | Linksans | 400 | 16px | 1.5 | -0.02em, uppercase | fixed | Short chapter labels above product capability headings. |
| pricing pages | plan-action | Linksans | 400 | 16px | 1 | normal | fixed | Compact full-width plan actions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the heaviest type for the opening; section leads are weight 700, while cards drop to weight 500 rather than mimicking mini hero headings.
- Negative tracking is generally -0.02em for large headings and body prose; card and question tracking is gentler at -0.01em. The pricing opener is more tightly packed at -0.04em.
- Use balanced line breaks and a broad text measure. Text sits directly on color; do not add heading badges or individual word highlights except the blue category word and scoped stat accent.

## Layout

**Density:** Airy, with viewport-scale color chapters and compact 16px gutters inside card collections.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Claim input to action and small icon gaps. |
| 16px | Repeated cards and accordion row gaps. |
| 24px | Heading-to-paragraph-to-action rhythm. |
| 32px | Feature card padding and inset blocks. |
| 40px | FAQ summary padding and horizontal bento padding. |
| 48px | Bento vertical padding and larger stack gaps. |
| 64px | Split-section gutter and footer panel padding. |
| 96px | Short proof section and compact closing-call padding. |
| 128px | Default major chapter vertical padding. |
| 160px | FAQ and standalone call-to-action vertical padding. |
| 250px | Top breathing room in the purple closing scene. |

### Containers and grids

- **marketing container**: max width 1504px · side padding 72px. Centered 1296px content at a 1440px desktop window; broad color fields extend to the viewport edges.
- **split chapter**: 2 columns · gap 64px. Two equal 616px columns, vertically centered; alternate text and object sides.
- **bento**: 2 columns · gap 16px. Two stacked landscape cards on the left beside a single tall card on the right.
- **reading column**: max width 1024px. Centered FAQ stack with a 48px heading-to-list gap.
- **footer columns**: 4 columns · gap 0px. Four equal link columns inside the white panel; actions and social controls share its bottom row.
- **benefit grid** (only for educational and pricing sections): 3 columns · gap 16px. Equal-width white or colored cards under a centered heading.
- **plans** (only for pricing pages): max width 1200px · 3 columns · gap 24px. Three equal 384px plan cards, with supporting horizontal offers beneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and navigation | 9999px (pill) |
|  | inputs and arrow controls | 8px |
|  | footer panel | 16px |
|  | bento and accordion | 32px |
|  | wide media tiles | 64px |
| educational and pricing sections | feature cards | 48px |
| pricing pages | plan cards | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | navigation | `0px 3.1px 15.3px rgba(0,0,0,0.043)` | A restrained edge lift for the floating white capsule. |
| pricing pages | recommended plan | `0px 16px 32px 4px rgba(0,0,0,0.12)` | Promotes the middle plan without affecting the flat marketing chapters. |

### Surfaces

#### Reading canvas · level 0

**Use:** Proof, cards and editorial sections.

**CSS:** `background: #f3f3f1; color: #1e2330`

**Observed:** Flat warm off-white without texture or atmospheric effects.

**Transfer:** Use as a quiet interval between strong color chapters.

#### Color chapter · level 0

**Use:** Primary product-story architecture.

**CSS:** `background: #2665d6; padding: 128px 0px`

**Observed:** Blue pairs lime headings with white prose; burgundy pairs lilac headings with white prose; pale green pairs ink with lilac actions. Lime opens the page and purple closes it.

**Transfer:** Assign a single contrasting palette pair to each capability; keep fields flat and edge-to-edge.

#### Closing canvas · level 0

**Use:** Final brand scene.

**CSS:** `background: #502274; color: #e9c0e9; padding: 250px 0px 32px; overflow: hidden`

**Observed:** Oversized silhouetted artwork bleeds beyond the canvas behind the centered conversion message and the white footer panel.

**Transfer:** Treat it as an illustrated finale, not merely a darker footer.

#### White card · level 1

**Only for:** educational and pricing sections

**Use:** Benefits, metrics and instructional steps.

**CSS:** `background: #ffffff; border-radius: 48px; padding: 32px; box-shadow: none`

**Observed:** Image or icon first, then medium-weight title and support. Related explanation cards use 42px corners and 36px padding.

**Transfer:** Keep fewer, larger cards rather than tiny dashboard tiles.

#### Recommended plan · level 1

**Only for:** pricing pages

**Use:** Featured subscription tier.

**CSS:** `background: linear-gradient(144deg, #f6f2ff 72.5%, #e8e1f7 101.9%); border-radius: 24px; box-shadow: 0px 16px 32px 4px rgba(0,0,0,0.12)`

**Observed:** A separate 2px violet inset ring wraps the entire card; a lavender header and a recommendation badge distinguish it from the white tiers.

**Transfer:** Reserve this gradient and shadow treatment for the purchasing decision.

## Components

### Floating navigation

**Use:** Persistent global wayfinding.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.173); border-radius: 9999px; height: 90px; padding: 13px 13px 13px 44px; max-width: 1568px; display: flex; align-items: center; gap: 48px; box-shadow: 0px 3.1px 15.3px rgba(0,0,0,0.043)`

**Text style:** `body-small` — Linksans 400 · 16px/1.5

**Observed:** Wordmark left, five compact navigation destinations in the middle, plain login and dark signup pill right; the capsule floats within page margins in a sticky wrapper.

**Transfer:** Use a short product wordmark and only the main destinations.

### Primary button

**Use:** Main action on the lime opening.

**CSS:** `background: #254f1a; color: #f3f3f1; border-radius: 9999px; height: 60px; width: 300px; padding: 0px 36px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — Linksans 500 · 16px/1.5

**Observed:** Text-only, centered; pairs with the claim input. Chapter variants are lime on blue or purple, lilac on burgundy or sage, and ink on neutral canvases.

**States:** Declared: hover translate 0 0; focus-visible outline-style none and zero box shadows; active scale 0.97.

### Claim input

**Use:** Low-friction account or workspace reservation beside the opening and closing action.

**CSS:** `background: #ffffff; border-radius: 8px; height: 60px; width: 290px; padding: 8px 16px; border: none`

**Observed:** Short fixed domain prefix gives context; input and primary button sit in one row with an 8px gap.

**Transfer:** Use a workspace name, handle or short email field that genuinely starts the product journey.

### Bento capability tile

**Use:** Visual summaries of capabilities after the proof rail.

**CSS:** `background: #e9c0e9; color: #1e2330; border-radius: 32px; padding: 48px 40px; display: flex; flex-direction: column; align-items: flex-start; justify-content: flex-end; gap: 80px`

**Text style:** `card-heading` — Linksans 500 · 28px/1.3 · tracking -0.01em

**Observed:** Artwork occupies the upper area, caption sits low and left. The neighboring short tile is lime; the tall tile is iris with white text. No separate button competes with the tile link.

**Transfer:** Make each whole tile the destination and vary artwork scale to suit its aspect ratio.

### FAQ row

**Use:** Objection handling near the end of the story.

**CSS:** `background: rgba(0,0,0,0.3); color: #e9c0e9; border: 2px solid transparent; outline: 2px solid rgba(0,0,0,0.3); border-radius: 32px; overflow: hidden; max-width: 1024px`

**Text style:** `question` — Linksans 500 · 20px/1.5 · tracking -0.01em

**Observed:** Burgundy section holds a 16px-spaced stack. Summary has 40px padding, left question and right chevron; expanded answer uses body-small and 40px side padding. Neutral educational variants use white rows on marble with ink text.

**Transfer:** Write short practical objections and expose answers through real details/summary behavior.

### Footer panel

**Use:** Structured navigation within the illustrated closing scene.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 64px; display: flex; flex-direction: column; gap: 48px`

**Text style:** `footer-heading` — Linksans 500 · 24px/1.5

**Observed:** Four columns of links, a language row, then login and lime signup at left with dark app and circular social controls at right. Small flags and a centered acknowledgement/legal line sit outside the panel below.

**Transfer:** Use relevant resource groups and locale/legal information; preserve the broad panel and contrasting bottom controls.

### Footer link

**Use:** Dense secondary navigation.

**CSS:** `color: #676b5f; text-decoration: none`

**Text style:** `footer-link` — Linksans 400 · 13px/1.5 · tracking -0.013em

**Observed:** Left-aligned lists use 16px vertical gaps below a larger column title.

**States:** Declared: hover opacity 0.7.

### Plan card

**Only for:** pricing pages

**Use:** Subscription selection.

**CSS:** `background: linear-gradient(145deg, #ffffff 65.7%, #f7f7f7 101.2%); border-radius: 24px; padding: 0px 0px 32px; width: 384px; display: flex; flex-direction: column; overflow: clip; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.02), 0px 1px 2px rgba(0,0,0,0.02), 0px 8px 32px rgba(0,0,0,0.05)`

**Text style:** `plan-title` — Linksans 800 · 36px/1 · tracking -0.015em

**Observed:** Tinted header, price and billing note, full-width action, divider, then checklist. The recommended middle card uses Recommended plan with a violet action; ordinary plans use white outlined actions.

### Plan action

**Only for:** pricing pages

**Use:** Trial action inside the recommended card.

**CSS:** `background: #7f22fe; color: #ffffff; border-radius: 9999px; height: 48px; width: 336px; padding: 0px 24px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `plan-action` — Linksans 400 · 16px/1

**Observed:** Sits above the feature checklist; nonrecommended tiers use a white fill and a fine dark-alpha border.

**States:** Declared: hover background-color #7008e7.

### Platform tab rail

**Only for:** step-by-step educational content

**Use:** Choose among parallel setup guides.

**CSS:** `background: #ffffff; border-radius: 80px; padding: 12px; max-width: 960px; overflow: hidden`

**Observed:** Five equal text tabs in one horizontal capsule; active tab is ink with off-white lettering, inactive tabs are muted. The corresponding description and white tutorial-card rail follow below.

**Transfer:** Use only for genuine alternative workflows, not ordinary global navigation.

## Imagery and graphics

### Human product scenes

**Use:** Opening visual tower and product-feature openings.

**Observed:** Bright studio or workplace photography shows makers with oversized phone-shaped product displays integrated as physical props. Scenes have highly coordinated sets, such as cobalt corrugated walls or green tiled interiors. Rounded rectangular scenes stack in a narrow tower on the right, clipped above and below the opening, with small captions near their lower edge.

**Transfer:** Stage users with an enlarged representation of the new product's output in a real environment. Keep strong set colors and tactile props; a simpler version combines one real person photograph with a carefully composited output card.

### Dimensional output collage

**Use:** At least one major product demonstration and bento artwork.

**Observed:** Phone-like profiles, content tiles, controls and stat badges overlap in shallow perspective; isolated headphones, records, food or products add material variety. The art sits directly on the flat section color with no enclosing browser frame. It occupies a roughly 616px square beside text.

**Transfer:** Show the product's recognizable outputs, not a generic laptop dashboard. Keep a clear hero object and a few supporting artifacts.

**Build:** Within a 616px square stage, layer a tall rounded output card in the center, a smaller square in front near its lower edge, and two offset cards behind. Use 16–32px card corners, rotate selected cards about 5–10 degrees and add restrained local contact shadows. Pair lilac, lime and iris tiles with real cutout object imagery; if only CSS is available, use three legible output cards and one bold circular token rather than detailed faux 3D.

### Proof tile rail

**Use:** Signature social-proof device.

**Observed:** Edge-to-edge row of 316×400px portraits and logo panels with 16px gaps, sometimes including a wider 500px tile. Masks alternate between 16px or 64px rounded rectangles and vertical capsules. Small white handle pills can overlay the artwork. The row extends beyond both content margins.

**Transfer:** Use genuine customer portraits, outputs or partner marks with diverse shapes. A brand without customers can show verified use-case outputs instead of fabricated endorsements.

**Build:** Create a horizontal flex track with fixed 400px-high tiles and 16px gaps; alternate border-radius 16px, 64px and 9999px. Apply object-fit cover to portraits and center marks on solid palette backgrounds. Clip the outer track at viewport edges.

### Capsule testimonial

**Use:** Human proof paired with oversized quotes.

**Observed:** A wide 830×420px capsule contains either interview footage or a smiling cutout portrait against high-contrast flat color shapes. A large centered quote follows with about 64px separation, then muted attribution and paired outlined arrow controls.

**Transfer:** Use a real customer's portrait or interview still; use product-relevant flat shapes behind cutouts, not desaturated corporate headshots.

### Closing silhouettes

**Use:** Signature purple finale behind the conversion message and footer panel.

**Observed:** Oversized flat human-profile silhouettes in bright contrasting colors emerge from the outer edges; the right edge includes lilac cutout forms. The artwork extends beyond the viewport while central text remains clear.

**Transfer:** Translate the silhouette idea into recognizable user or product-object profiles, preserving the exaggerated scale and flat poster-like layering.

**Build:** Use two SVG path silhouettes approximately 600–750px wide and 700–950px tall behind the content. Anchor them outside the left and right margins on a purple field; fill one lilac and the other a strong contrasting flat hue drawn from the product artwork. Keep their profiles irregular and recognizable, not soft gradient blobs. Place centered text and the white footer panel above them with relative positioning.

### Icons

**Observed:** Utility arrows and chevrons are simple round-cap strokes, usually 20–24px with 2px strokes and current text color. Social marks are solid white within 64px dark circular buttons; checks and crosses distinguish comparison outcomes.

**Transfer:** Choose a consistent round-cap outline set for utilities; keep filled platform marks confined to platform controls and use tiny check/cross marks rather than decorative illustrations in tables.

## Section recipes

How recurring sections are built.

### First screen: Color tower opening

**Observed:** A lime field starts beneath a narrow burgundy announcement strip. Floating navigation overlays the top. In the 1296px-wide content area, two equal columns are separated by 64px: a three-line forest display headline at left occupies most of its column width, followed by a two-line support paragraph and a white Claim input plus Primary button. At right, 576px-wide rounded photographic scenes form a vertical tower that extends above and below the viewport. Layers run flat lime, clipped media tower, text/form, then floating white navigation. Within the first 900px the headline, support, entire action row and parts of two scenes are visible; the tower and the opening's lower edge continue below the fold.

**Transfer:** Use an equally large short promise and a vivid output scene with people or props, keeping the action easy to read against the plain field. Without bespoke photography, make a tower from real outputs paired with one human photograph. Feature pages open with a single square scene, optional eyebrow and a secondary outlined action; outcome campaigns can use orchid and a dimensional collage. Pricing opens on marble with a centered compact heading and the top of the plan grid.

**Avoid:** Do not center the default opening, shrink its image to a small decorative corner, or put the headline over the busy photography.

**Text style:** `display` — Linksans 800 · 80px/1.07 · tracking -0.02em

### Split color chapter

**Observed:** Color chapter contains a vertically centered 616px object stage opposite a text column. Use heading, body and a pill action with 24px gaps and 128px outer vertical padding. Alternate image side across successive chapters. The object floats on the same background as the section rather than inside a separate neutral panel.

**Transfer:** Give each chapter one concrete capability and one scene; carry the palette pairing into headline and button.

**Text style:** `heading` — Linksans 700 · 56px/1.06 · tracking -0.02em

### Centered proof rail

**Observed:** Reading canvas, 128px vertical padding, centered heading with the blue category-word immediately beneath it. After a 50px gap the Proof tile rail spans beyond the normal container.

**Transfer:** Use a short earned proof statement and an audience or use-case category; preserve the shape-changing rail even when the proof comes from outputs rather than famous customers.

**Text style:** `heading` — Linksans 700 · 56px/1.06 · tracking -0.02em

### Capability bento

**Observed:** Bento capability tile repeats as two short left tiles beside one tall iris tile. Gutters are 16px and captions use card-heading, much smaller and lighter than section titles.

**Transfer:** Group three connected benefits and let artwork communicate before captions.

**Text style:** `card-heading` — Linksans 500 · 28px/1.3 · tracking -0.01em

### Portrait and quote

**Observed:** A Capsule testimonial centers on the Reading canvas or a lime proof band. The 830px-wide visual precedes a centered heading-sized quote, attribution and 48×48px arrow controls with 8px corners.

**Transfer:** Use a short specific customer statement as a headline, not a paragraph in a tiny review card.

**Text style:** `heading` — Linksans 700 · 56px/1.06 · tracking -0.02em

### Objection stack

**Observed:** A burgundy field with 160px vertical padding carries a centered lilac heading above FAQ row components in a 1024px column. Other landing types use the neutral white-row variant on marble.

**Transfer:** Keep answers practical and concise; preserve the broad rounded summary rows and small chevron.

**Text style:** `question` — Linksans 500 · 20px/1.5 · tracking -0.01em

### Illustrated closing and footer

**Observed:** Closing canvas begins with a centered lilac heading, a claim form/action and Closing silhouettes around the edges. A generous 250px interval separates the call from the Footer panel. The white panel is followed by small flag imagery and a centered acknowledgement/legal line on purple; the page ends on that purple, not on white. A focused feature landing can add a compact lime conversion band immediately before this shared finale.

**Transfer:** Close with a memorable invitation and product-relevant oversized silhouettes; keep resource links in the white inset panel and applicable legal information below.

**Text style:** `heading` — Linksans 700 · 56px/1.06 · tracking -0.02em

### Benefit grid

**Only for:** educational and pricing sections

**Observed:** Centered headline and support introduce three White cards with 16px gutters; images occupy the upper half with title and description below. Lilac may fill the entire outer band. A related content grid uses two rows of three cards with icon/category pills.

**Transfer:** Explain reasons to choose the product using distinct concrete outcomes rather than six nearly identical slogans.

**Text style:** `compact-card-heading` — Linksans 500 · 24px/1.3 · tracking -0.01em

### Comparison and plan selection

**Only for:** pricing and feature-comparison pages

**Observed:** A white comparison section uses a centered heading and short intro, then broad three-column rows with alternating very light gray bands. The preferred column has a lime rounded-top header. Subscription selection instead uses three Plan cards on marble, a recommended center tier and secondary full-width offers beneath. Long feature comparison adds a category rail at left and a persistent plan header.

**Transfer:** Keep decision tables readable and structurally distinct from the colorful capability scenes; highlight just one preferred column.

**Text style:** `pricing-display` — Linksans 800 · 48px/1.1 · tracking -0.04em

### Educational selector and stat

**Only for:** long-form feature education

**Observed:** An ink inset panel with 64px corners and 80px padding pairs a vertical list of medium-weight capability labels with a changing collage; active content is white and inactive labels subdued. Separate step-card rails use 416px-wide burgundy cards with 48px corners and 32px padding. A compact stat interlude uses stat-callout with a burgundy multiplier, brief explanation and small methodology note. Platform tab rail introduces alternative setup guides.

**Transfer:** Use interactive explanation where visitors need to learn a workflow, and a typographic stat to punctuate long content rather than another dense chart.

**Text style:** `stat-callout` — Linksans 700 · 80px/1 · tracking -0.02em

## Page flow

**Storyline:** Bold promise → tangible capability scenes → shaped social proof → deeper benefits or purchasing detail → human endorsement → practical objections → illustrated conversion finale.

### Broad product marketing landing page

1. **promise** — Lime split opening with photographic tower and claim form.
2. **capability chapters** — Alternating blue, burgundy and pale-green demonstrations.
3. **social proof** — Centered claim, blue category word and shaped portrait/logo rail.
4. **capability summary** — Colorful asymmetrical bento followed by a compact plan invitation.
5. **credibility** — Publication marks in white rounded badges and a large capsule testimonial.
6. **objection handling** — Burgundy FAQ stack.
7. **closing call** — Purple silhouette scene and white resource panel.

**Transfer:** Use the broad landing pattern when the product needs both emotional appeal and a clear explanation of several capabilities.

### Subscription decision page

1. **pricing** — Compact centered promise, three plan cards and secondary enterprise/free offers.
2. **social proof** — Shared shaped proof rail.
3. **benefit framing** — Lilac benefit cards and a simple outcome comparison.
4. **detailed comparison** — Long categorized matrix with plan columns.
5. **upgrade rationale** — Three richly colored capability cards.
6. **human proof** — Wide portrait and headline quote.
7. **sales route** — Lilac split scene with team contact action.
8. **objection handling** — Neutral FAQ.
9. **closing call** — Shared purple illustrated finale.

**Transfer:** Lead with the buying decision, then use selective brand scenes to explain value rather than giving every matrix row a section.

### Feature education and acquisition page

1. **promise** — Lime split opening with eyebrow and two actions.
2. **quantified and social proof** — Four metric cards followed by shaped proof rail.
3. **category explanation** — Blue demonstration and lilac reasons-to-use cards.
4. **capability chapters** — Content grid and iris, lime and gold demonstrations.
5. **human proof** — Capsule testimonial.
6. **decision support** — Example/template resource cards, plan comparison and ink selector panel.
7. **onboarding education** — Burgundy step rail, large multiplier and platform-specific tutorial tabs.
8. **objection handling** — Neutral FAQ.
9. **closing call** — Compact lime conversion band before shared purple finale.

**Transfer:** Support visitors unfamiliar with the category through concrete examples and workflow education; compress tutorial depth to match the new product.

### Outcome-oriented solution campaign

1. **promise** — Orchid opening with off-white display type, lime action and dimensional output collage.
2. **capability chapters** — Alternating lime, brown, lilac, orchid and blue scenes with short checklists.
3. **decision support** — White outcome comparison.
4. **human proof** — Lime band with capsule interview and large quote.
5. **objection handling** — Short neutral FAQ.
6. **closing call** — Shared purple illustrated finale.

**Transfer:** Use a more intense palette and action-specific checklists when the visitor already understands the category and wants a particular result.

## Writing

Confident, welcoming and energetic without sounding technical. Benefits are expressed as things a person can do immediately, with playful compression in headings and practical explanation underneath.

**Do not copy:** Do not reuse the Linktree name, logo, proprietary imagery, creator identities, partner marks, customer quotes, audience counts, financial claims or conversion statistics. Replace them with truthful product-specific assets and substantiated claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your; use we sparingly for support and reassurance. Product mentions are functional rather than repeated in every sentence.
- **Rhythm:** Headlines usually contain one plain-language promise; support paragraphs run one to three sentences. Short fragments and paired clauses add momentum, with occasional exclamation marks rather than a constant sales shout.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact product idea followed by an expansive personal benefit. | 6–12 words | “The link in bio that grows with you”<br>“One link, endless ways to earn” |
| Capability headline | Start with an ordinary action verb and name the benefit, not an internal feature label. | 6–11 words | “Create and customize your [Brand] in minutes”<br>“Share your [Brand] anywhere you like!” |
| Support paragraph | Explain the mechanism through concrete actions and a small list of recognizable objects. | 25–45 words | “Track your engagement over time, monitor revenue and learn what’s converting your audience. Make informed updates on the fly to keep them coming back.” |
| Primary action | Verb plus immediate outcome; free-entry reassurance is explicit. | 2–6 words | “Get started for free”<br>“Create your first course” |
| Objection heading | Conversational question or quick reassuring answer. | 2–10 words | “Questions? Answered”<br>“Do I need a separate platform to sell digital products?” |
| Closing invitation | A warm imperative that gives the reader ownership of the outcome. | 7–12 words | “Jumpstart your corner of the internet today” |

**Words and phrasing to use:** your; create; grow; share; in minutes; get started; all in one place; no extra tools; when you’re ready

**Avoid:** synergize; leverage our ecosystem; enterprise-grade transformation; revolutionary solution; unprecedented innovation

**Rules:**

- Pair the promise with a concrete mechanism before making another claim.
- Use recognizable nouns and verbs rather than feature taxonomies in the opening.
- Put limitations beside the relevant action in a smaller support line.
- Keep proof specific and qualified; separate the headline benefit from its methodology note.

## Do's and Don'ts

### Do

- Use 80px weight-800 opening type with -0.02em tracking and strong three-line wrapping.
- Carry saturated color across full-width chapters with 128px vertical padding.
- Keep the desktop split at equal 616px columns and a 64px gutter.
- Pair blue with lime headlines and white prose; pair burgundy with lilac.
- Use 16px gutters to make bento and repeated cards feel closely related.
- Keep 60px conversion pills distinct from the 8px-corner claim input.
- Include both shaped proof media and an illustrated purple closing scene.
- Use 830×420px capsule media above headline-sized testimonials.

### Don't

- Do not make every panel white on marble; the primary product story belongs on broad color fields.
- Do not introduce serif or monospace marketing headings; the grotesk family carries the entire hierarchy.
- Do not use 800 weight for every card caption; the 28px card role is weight 500.
- Do not give the claim input the same pill silhouette as its action.
- Do not spread subscription gradients and heavy plan shadows into ordinary feature chapters.
- Do not add a full browser frame around every collage; output cards float directly on the section color.
- Do not turn the mixed-shape proof rail into a uniform small logo grid.
- Do not finish with a conventional black footer; retain the purple canvas around the white inset panel.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use background-color, transform, filter and box-shadow over 0.15s with cubic-bezier(0, 0, .2, 1); press scale is 0.97.
- Footer link opacity transitions run over 0.15s with cubic-bezier(.4, 0, .2, 1), reaching 0.7 on hover.
- The opening tower has a declared infinite vertical animation with ease-in-out; its duration is a variable.
- Navigation border and shadow transitions run over 0.2s with cubic-bezier(.4, 0, .2, 1).

**Transfer:**

- Keep button feedback small and quick; let the tower and changing output collages provide the expressive movement.
- Keep the category word in a clipped line so changing categories do not disturb the centered heading.

**Unknown:**

- Tower duration, carousel cadence and complete scroll-animation choreography are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 479/480px, 768px, 991/992px, 1279/1280px, 1439/1440px and 1920px.
- Section headings use clamp(20px, 4vw, 56px); body prose uses clamp(14px, 1.29vw, 19px).
- Markup classes center split-section text below the medium breakpoint and stack the claim form at narrow widths; card rails use horizontal scrolling and snap behavior.

**Transfer:**

- On narrow layouts retain the bold color fields, then place the product scene below the centered promise without reducing it to an icon.
- Use horizontal swipe rails to preserve the large rounded proof and tutorial cards; keep each card's reading content together.
- Stack footer groups and conversion controls while preserving the white panel within purple margins.

**Unknown:**

- Exact mobile geometry and first-screen media visibility are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
