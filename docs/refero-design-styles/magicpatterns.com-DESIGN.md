# Magic Patterns — aurora meets workbench

## Overview

A bright, friendly software style that pairs a spacious white stage with pastel light and a practical grid of miniature interfaces. Rounded geometric sans headlines feel personable rather than corporate, while restrained teal-black controls keep the page grounded. It suits collaborative tools and complex products that need tangible demonstrations, human proof, and a little sculptural playfulness without becoming visually dense.

### Essentials

- A product name becomes the hero object: Poppins 112px/0.96, weight 500, -0.055em tracking, centered in a nearly full-width white stage with a flowing cyan, mint and lilac ribbon behind it.
- The opening is a luminous stage, not a dashboard billboard: 16px outer inset, 12px corners, an 820px-tall panel, two restrained lines of support and a 44px paired action row; a pale logo ticker sits at its foot.
- Controls feel like small polished objects: teal-black primary buttons and white secondary buttons have subtle white inset highlights, 12px corners and 20px horizontal padding; navigation versions shrink to 36px high with 8px corners.
- Most of the page stays almost-white: #f9f9fb bands surround white cards with 1px ink-at-12% outlines. Color concentrates in the hero ribbon, small blue labels, low-opacity proof-card glows and the playful bottom artwork, not in full-page saturated fills.
- Capabilities are staged as little workbenches: 16px rounded cards put light interface vignettes above ruled white copy trays, using 24px padding and 14px blue labels; combine two wide cards with three narrower ones rather than repeating identical feature icons.
- The ending carries both utility and delight: a 24px rounded closing panel uses a 20px dot grid and a 48px two-part statement, followed by an orderly white footer and a 148px bottom-clipped parade of soft colorful sculptures. Keep both the graphic closing panel and the sculptural sign-off; original rounded SVG objects are the fallback when custom 3D art is unavailable.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Capability blue | `#0070ac` | `--color-blue-label` | text, accent | Small capability labels, not primary button fills. |
| Aurora mint | `#7cd27f` | `--color-mint` | accent | Green light in the atmospheric artwork; low-opacity mesh layers use 20% of this hue. |
| Aurora sky | `#51b6f8` | `--color-sky` | accent | Blue light in atmospheric artwork; mesh layers use 17% of this hue. |
| Aurora lilac | `#a390cb` | `--color-lilac` | accent | Purple light in atmospheric artwork; mesh layers use 17% of this hue. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | surface, text, background | Hero stage, cards, footer and reversed button text. |
| Lilac white canvas | `#f9f9fb` | `--color-canvas` | background | Main page bands and navigation backing. |
| Cool pressed surface | `#f2f3f4` | `--color-muted-surface` | surface | Interface vignette backing and quiet information panels; ink at 4% over the light canvas. |
| Soft ink edge | `#dee0e1` | `--color-edge` | border | Hairlines and panel outlines; ink at 12% over the light canvas. |
| Hero gray | `#667374` | `--color-hero-gray` | text | The two-line opening description. |
| Muted teal gray | `#657273` | `--color-muted` | text | Secondary prose; ink at 60% over the light canvas. |
| Teal black | `#001617` | `--color-ink` | text, action, background | Headlines, principal controls and dark micro-bands; softer text and edges derive from this ink. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| case studies and enterprise capability grids | Reading charcoal | `#1c2024` | `--color-body-ink` | text | Long-form reading text and technical capability titles. |
| case-study articles | Periwinkle quote wash | `#e1e9ff` | `--color-quote-tint` | surface | Full-width editorial pull-quote panels. |

## Typography

- **Poppins** — Display names, section headings and the geometric text of secondary page types. Rounded geometric sans with single-storey forms and medium-weight headings. Font stack: "Poppins", ui-sans-serif, system-ui, sans-serif.
- **Inter** — Navigation, buttons, feature descriptions, FAQs and numeric proof. Compact neutral sans; a practical counterpoint to rounded headings. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **Inter Tight** — Opening supporting description. Narrower sans that holds long support lines without competing with the wordmark. Font stack: "Inter Tight", ui-sans-serif, system-ui, sans-serif.
- **Source Sans 3** (only for case-study articles) — Long reading paragraphs and pull quotes. Open humanist sans that changes the pace from the geometric marketing typography. Font stack: "Source Sans 3", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Poppins | 500 | 112px | 0.96 | -0.055em | fixed | Single short product-name headline in the luminous opening. |
| stat | Inter | 500 | 60px | 1 | -0.02em | fixed | Large time or outcome value inside a proof card. |
| closing-heading | Poppins | 500 | 48px | 1.25 | -0.01em | fixed | Closing panel statement, often split into two complementary lines. |
| section-heading | Poppins | 500 | 36px | 1.25 | -0.01em | fixed | Core section leads; centered for proof and objections, left aligned for a gallery. |
| greeting | Poppins | 500 | 24.6px | 1.2 | -0.01em | fixed | Short muted introduction immediately above the display name. |
| hero-support | Inter Tight | 400 | 20px | 1.6 | 0.005em | fixed | Two centered lines under the display name. |
| card-heading | Poppins | 500 | 20px | 1.25 | -0.01em | fixed | Capability copy-tray titles. |
| support | Inter | 400 | 18px | 1.625 | normal | fixed | Section support and closing support text. |
| button | Inter | 500 | 16px | 1 | normal | fixed | Core action buttons. |
| faq-question | Inter | 600 | 16px | 1.625 | normal | fixed | Accordion questions. |
| body-small | Inter | 400 | 14px | 1.625 | normal | fixed | Capability descriptions and footer tagline. |
| capability-label | Inter | 600 | 14px | 1.625 | 0.025em | fixed | Blue mixed-case labels above capability titles. |
| nav-action | Inter | 500 | 14px | 1 | normal | fixed | Navigation links and compact conversion buttons. |
| footer-link | Inter | 400 | 14px | 20px | normal | fixed | Footer navigation. |
| footer-label | Poppins | 600 | 12px | 16px | 0.14em, uppercase | fixed | Footer column labels and small trust-band labels. |
| media-caption | Inter | 600 | 11px | 1.5 | normal | fixed | Watch-story badge on human proof media. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| customer collections and enterprise pages | secondary-display | Poppins | 500 | 56px | 1.05 | -0.02em | size clamp(2.5rem, 5vw, 3.5rem) | Centered title on customer collections and enterprise introductions. |
| pricing pages | pricing-display | Poppins | 500 | 56px | 1.1 | -0.02em | size clamp(2.5rem, 5vw, 3.5rem) | Balanced two-line pricing promise. |
| case-study articles | article-title | Poppins | 500 | 44px | 1.05 | -0.02em | size clamp(2rem, 4vw, 2.75rem) | Long outcome-led article title. |
| customer collections and enterprise pages | quote-display | Poppins | 500 | 30px | 1.25 | -0.01em | fixed | Featured customer quote and compact social-proof section titles. |
| case-study articles | article-heading | Poppins | 500 | 24px | 1.1 | -0.02em | fixed | Reading-column chapter headings. |
| pricing, customer collections and enterprise pages | secondary-support | Poppins | 400 | 18px | 1.625 | normal | fixed | Geometric support text on secondary marketing pages. |
| case-study articles | article-body | Source Sans 3 | 400 | 18px | 1.6 | -0.0025em | fixed | Reading paragraphs and pull quotes. |
| customer collections and enterprise pages | quote-body | Poppins | 400 | 16px | 1.625 | normal | fixed | Testimonial cards. |
| pricing pages | plan-label | Poppins | 600 | 16px | 1.625 | normal | fixed | Plan titles. |
| pricing pages | billing-control | Poppins | 500 | 14px | 20px | normal | fixed | Billing-period tabs and pricing actions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Heading weight stays at 500 even at display scale. The product name tightens to -0.055em, while ordinary headings keep -0.01em and secondary page titles use -0.02em.
- Inter carries the default small functional text; do not spread the article's Source Sans 3 treatment across the marketing page.
- Use the declared clamp recipes for secondary titles; the main product-name display is a separate treatment.

## Layout

**Density:** Airy at section scale, compact inside the cards: large pauses separate evidence-rich groups while labels, headings and descriptions stay close.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Tight vertical gap in capability copy trays. |
| 8px | Compact control and icon spacing. |
| 12px | Paired action gap and gallery heading-to-support gap. |
| 16px | Standard stacked text gap, hero outer inset and pricing-grid gutters. |
| 20px | Button horizontal padding and testimonial masonry gutters. |
| 24px | Card copy padding and default gallery or feature-grid gap. |
| 28px | Opening support-to-actions separation. |
| 32px | Desktop section side padding. |
| 40px | Heading-group separation from content. |
| 48px | Footer column gaps and article-to-sidebar gap. |
| 64px | Footer vertical padding. |
| 96px | Closing-panel vertical padding; narrower-screen major section padding. |
| 112px | Secondary marketing opening top padding. |
| 128px | Desktop major section vertical padding and space after the closing panel. |

### Containers and grids

- **content**: max width 1152px · side padding 32px. Centered desktop content area; the primary alignment shared by cards, proof panels, closing call and footer.
- **heading measure**: max width 672px. Centered explanatory heading groups and closing statements.
- **faq measure**: max width 768px. Narrow accordion column independent of the wider card grids.
- **feature workbench**: 6 columns · gap 24px. Two cards spanning three tracks above three cards spanning two tracks.
- **gallery**: 3 columns · gap 24px. Equal-width media cards with 3:2 images and shallow caption strips.
- **plans** (only for pricing pages): 4 columns · gap 16px. Aligned plan cards with matching heights and bottom-aligned actions.
- **article** (only for case-study articles): max width 720px · gap 48px · side padding 16px. Reading column with 688px usable prose width beside a compact fact card.
- **testimonials** (only for customer collections): 3 columns · gap 20px. Variable-height quote cards in masonry columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | core actions | 12px |
|  | compact actions | 8px |
|  | cards | 16px |
|  | hero frame | 12px |
|  | closing and featured proof panels | 24px |
|  | media badge | 9999px (pill) |
| case-study articles | article quotes | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | card | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Ordinary cards; a trace of lift rather than visible floating elevation. |
|  | primary action | `inset 0px 1px 0px 0px rgba(255,255,255,0.08), 0px 1px 2px -1px rgba(15,23,42,0.24)` | The polished solid button. |
| pricing pages | recommended plan | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Single emphasized plan. |

### Surfaces

#### Canvas · level 0

**Use:** Default main-page field.

**CSS:** `background: #f9f9fb`

#### White card · level 1

**Use:** Gallery, proof and capability panels.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,22,23,0.12); border-radius: 16px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Observed:** A nearly invisible edge separates white cards from the cooler page field.

**Transfer:** Keep the border visible but subordinate to the content.

#### Polished closing panel · level 1

**Use:** Graphic closing statement.

**CSS:** `background-color: #ffffff; background-image: linear-gradient(135deg, rgba(255,255,255,0.4), rgba(255,255,255,0) 45%), linear-gradient(rgba(255,255,255,0.28), oklch(0.58 0.03 255 / 0.03)); border: 1px solid rgba(0,22,23,0.12); border-radius: 24px; padding: 96px 32px; overflow: hidden; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.32), 0px 6px 12px -10px rgba(40,50,70,0.06)`

**Observed:** A delicate glazed white panel; the default version contains a dot field, while secondary marketing versions contain a diffuse three-color mesh.

**Transfer:** Use the panel as a distinct graphic punctuation, not as a generic container for every section.

#### Dot field

**Use:** Workbench-like texture inside the closing panel and miniature interface scenes.

**CSS:** `background-image: radial-gradient(circle, rgba(0,22,23,0.24) 1.2px, rgba(0,0,0,0) 1.6px); background-size: 20px 20px; background-position: 50% 50%`

**Observed:** Regular pale pin dots across the white field, underneath all text.

**Transfer:** Keep dots low contrast and clip to the panel corners.

#### Quiet inset

**Use:** Backing behind small interface demonstrations.

**CSS:** `background: rgba(0,22,23,0.04)`

**Observed:** Neutral fields hold the miniature controls; selective blue, green and purple details provide the color.

**Transfer:** Do not turn this into a dark product mockup stage.

#### Editorial quote wash

**Only for:** case-study articles

**Use:** Pull quotes that interrupt long reading passages.

**CSS:** `background: #e1e9ff; border-radius: 8px; padding: 24px`

**Observed:** Flat periwinkle backing without the marketing cards' outlined glaze.

**Transfer:** Use only for substantial first-person quotations with an attribution.

## Components

### Navigation

**Use:** Compact shared top bar.

**CSS:** `height: 56px; padding: 0px 16px; display: flex; align-items: center; justify-content: space-between; background: #f9f9fb`

**Text style:** `nav-action` — Inter 500 · 14px/1

**Observed:** Brand at left, product links immediately beside it, account and two compact conversion controls aligned to the right. The product entry carries a small downward chevron.

**Transfer:** Keep navigation subordinate to the luminous opening.

### Primary button

**Use:** Main action in hero and closing panels.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 10px; height: 44px; padding: 0px 20px; border: 0px; border-radius: 12px; background-color: #001617; background-image: linear-gradient(135deg, rgba(255,255,255,0.1), rgba(255,255,255,0) 42%), linear-gradient(rgba(255,255,255,0.06), rgba(255,255,255,0) 55%); color: #ffffff; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.08), 0px 1px 2px -1px rgba(15,23,42,0.24)`

**Text style:** `button` — Inter 500 · 16px/1

**Observed:** Text can be followed by a right arrow. Compact navigation versions use the nav-action recipe, 36px height, 16px side padding and 8px corners. Enterprise-opening versions are 48px high.

**States:** Declared: hover background-color var(--c-solid-hover); focus-visible transparent solid 2px outline with 2px offset and retained inset highlight; active background-color var(--c-solid-active).

### Secondary button

**Use:** Lower-commitment action beside the primary.

**CSS:** `height: 44px; padding: 0px 20px; border: 1px solid rgba(0,22,23,0.12); border-radius: 12px; background-color: #ffffff; background-image: linear-gradient(135deg, rgba(255,255,255,0.4), rgba(255,255,255,0) 45%), linear-gradient(rgba(255,255,255,0.28), oklch(0.58 0.03 255 / 0.03)); color: #001617; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.35)`

**Text style:** `button` — Inter 500 · 16px/1

**Observed:** Paired with the solid action at equal height. Navigation uses a muted pressed variant rather than a second dark fill.

**States:** Declared: hover background-color var(--c-muted) and border-color var(--c-border-hover); focus-visible transparent solid 2px outline with 2px offset; active background-color var(--c-muted-hover).

### Capability card

**Use:** Explain one feature through a tangible interface fragment.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,22,23,0.12); border-radius: 16px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `card-heading` — Poppins 500 · 20px/1.25 · tracking -0.01em

**Observed:** The upper portion stages a miniature interface; a top-ruled white copy tray below contains Capability-label, Card-heading and Body-small with a 6px stack and 24px padding. The wider cards have 240px media areas, narrower ones 220px.

**Transfer:** Illustrate one visible product behavior per card instead of a floating abstract icon.

### Gallery card

**Use:** Show completed outputs and community examples.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,22,23,0.12); border-radius: 16px; overflow: hidden; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `nav-action` — Inter 500 · 14px/1

**Observed:** A 3:2 image fills most of the card. A shallow bottom strip contains avatar, short title and author, with an outlined heart and count at the right.

**Transfer:** Use authentic outputs across several use cases with consistent framing.

### Story badge

**Use:** Invite video viewing without obscuring the customer image.

**CSS:** `background: rgba(255,255,255,0.9); border: 1px solid rgba(0,22,23,0.12); border-radius: 9999px; padding: 4px 12px; backdrop-filter: blur(12px); display: flex; gap: 6px; align-items: center`

**Text style:** `media-caption` — Inter 600 · 11px/1.5

**Observed:** Small play triangle, label and duration, pinned near the top-right of a landscape interview still.

### FAQ row

**Use:** Objection handling as a thin ruled list.

**CSS:** `width: 100%; padding: 20px 0px; border-bottom: 1px solid rgba(0,22,23,0.12); display: flex; align-items: center; justify-content: space-between; gap: 16px`

**Text style:** `faq-question` — Inter 600 · 16px/1.625

**Observed:** Question left and tiny downward chevron right; the list also begins with a top rule. Closed rows occupy about 67px, with no card backplates.

**Transfer:** Keep questions short enough to scan within the 768px reading column.

### Footer link

**Use:** Low-emphasis grouped site navigation.

**CSS:** `color: rgba(0,22,23,0.6); opacity: 0.8; text-decoration: none`

**Text style:** `footer-link` — Inter 400 · 14px/20px

**Observed:** Four columns with uppercase Footer-label titles; 12px vertical gaps between links.

**States:** Declared: hover opacity 1.

### Recommended plan

**Only for:** pricing pages

**Use:** One emphasized subscription option.

**CSS:** `background: #ffffff; border: 1px solid #001617; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Text style:** `plan-label` — Poppins 600 · 16px/1.625

**Observed:** Plan name, short fit description, large price with a small crossed-out comparison, checkmarked feature list and bottom-aligned action. Recommended plan gets the solid button; others get outlined actions. All four cards align at 584px tall on desktop.

**Transfer:** Emphasize one useful entry plan without a saturated banner or oversized badge.

### Billing switch

**Only for:** pricing pages

**Use:** Choose billing period.

**CSS:** `display: flex; align-items: center; padding: 4px; background: #ffffff; border: 1px solid rgba(0,22,23,0.12); border-radius: 9999px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `billing-control` — Poppins 500 · 14px/20px

**Observed:** Active period is a dark pill with white text; inactive period is muted text. Each tab uses 8px vertical and 16px horizontal padding. The outer control is 46px high.

### Article pull quote

**Only for:** case-study articles

**Use:** Human evidence in the reading column.

**CSS:** `background: #e1e9ff; border-radius: 8px; padding: 24px; display: flex; flex-direction: column`

**Text style:** `article-body` — Source Sans 3 400 · 18px/1.6 · tracking -0.0025em

**Observed:** Quote first, then a small round portrait with bold name and muted role; the panel spans the prose column.

## Imagery and graphics

### Luminous ribbon

**Use:** Signature atmospheric object behind the opening product name.

**Observed:** A broad, soft, translucent band of mint, cyan and lilac crosses the white stage. It narrows toward the middle and rises slightly toward the right; white haze keeps the dark title and support readable. It is a light field, not a photograph or a solid gradient rectangle.

**Transfer:** Create an original aurora ribbon for any product; no product artwork is needed. Maintain white space above and below and reserve the highest contrast for the title.

**Build:** Use three overlapping SVG curved bands across a 1406px by 609px viewBox. Sweep them from the lower left toward the upper right, narrowing around the center; tint bands cyan, mint and lilac using the aurora palette at roughly half opacity. Apply Gaussian blur around 24px and layer a white radial haze over the central text zone. Let the tails run off both edges and mask the outer edges to white. Match the soft glow; exact stops are not essential.

### Miniature workbench scenes

**Use:** Capability-card media.

**Observed:** Small white interface fragments, controls, layered documents, sharing panels and cursors float on pale neutral or dotted fields. Color appears in tiny swatches, cursor tags and occasional pastel gradient shapes; most interface lines remain gray.

**Transfer:** Rebuild a simplified real workflow with 2–4 recognizable interface pieces. Keep the illustration area light and detailed enough to explain a behavior, without reproducing a full application.

### Customer documentary

**Use:** Human proof beside case-study headlines and within articles.

**Observed:** Landscape interview imagery in real workspaces, natural subdued light, warm skin and furniture tones. The image is framed with 16px rounded corners and a Story badge; the home proof layout gives it about three fifths of the row width.

**Transfer:** Use an actual customer in context; a simple authentic landscape portrait is preferable to glossy anonymous stock imagery.

### Sculptural sign-off

**Use:** Signature bottom edge after the utilitarian footer.

**Observed:** A row of friendly glossy clay-like forms peeks up from a white 148px strip. Shapes vary between rings, blobs, droplets, capsules and faceted solids, with tiny dark eyes and mint, peach, blue, pink, yellow, teal and purple finishes. Their lower bodies are clipped by the page edge.

**Transfer:** Create original playful objects related to the new product, with varied heights and a shared soft material. Preserve this small moment of delight even for serious software.

**Build:** Arrange 10–12 original rounded SVG forms along a centered baseline spanning about 1000px. Vary height from 60px to 140px, clip the lower portions in a 148px-high white wrapper, and leave white breathing room above. Shade each with a pale radial highlight at upper left and a darker same-hue lower-right edge; add two tiny near-black oval eyes. A simple softly shaded SVG parade is the minimum acceptable alternative to custom 3D.

### Diffuse proof mesh

**Only for:** secondary marketing closing panels and featured customer quotes

**Use:** Low-energy atmospheric backing behind human proof and a final invitation.

**Observed:** Large overlapping organic green, blue and purple patches dissolve into white. Text remains dark. Unlike the opening ribbon, these colors barely tint the panel.

**Transfer:** Keep these panels a soft variation of the white card rather than a colorful new theme.

**Build:** Layer three absolute organic ellipses behind content in an overflow-hidden panel: mint at 20% opacity, sky and lilac at 17%. Use widths around 600px to 720px and heights around 200px to 280px, irregular elliptical corners, and a shared 60px blur. Place green toward the left/top, blue to the right, lilac below; keep the text above all layers.

### Technical line diagrams

**Only for:** enterprise capability grids

**Use:** Translate controls and infrastructure into approachable technical illustrations.

**Observed:** Very pale gray wireframes, networks, globes, certificates and application outlines sit in generous white upper areas. A small blue focal point, check or lock provides emphasis; lower captions carry most of the explanation.

**Transfer:** Use thin SVG strokes and a single accent focal node. Alternate wide and narrow panels rather than a dense diagram wall.

**Build:** Draw an original 300px by 150px SVG with light-gray 1px paths, small circular junctions and a central 32px blue control. For a globe use intersecting elliptical meridians and parallels; for a workflow use three rounded rectangles and orthogonal connectors. Keep the backing white.

### Icons

**Observed:** Small functional SVGs: 14px–18px arrows, chevrons and social marks; most outline icons use round caps and roughly 2px strokes. Video badges have a 12px play triangle. Enterprise role cards use 22px outline icons in 48px tinted squares; pricing checks are 16px with 1.8px strokes.

**Transfer:** Use a consistent rounded outline set; reserve filled shapes for play triangles, social marks and compact directional controls.

## Section recipes

How recurring sections are built.

### First screen: Luminous product opening

**Observed:** A compact 56px Navigation sits above a white, lightly outlined stage inset 16px from each side. A separate 43px announcement strip precedes navigation when there is a timely message. The stage is 820px tall with 12px corners. Its upper quarter is mostly breathing room; the short Greeting and tightly tracked Display name occupy the central third, the name about one third of viewport width. Behind them the Luminous ribbon flows edge to edge; in front are two centered Hero-support lines within a 736px measure and a Primary button plus Secondary button, 12px apart, 28px below the prose. A pale monochrome logo ticker hugs the stage's foot. Within the first 900px the full title, support, actions, ribbon and ticker are visible; capability cards begin below this screen.

**Transfer:** Use a short new product or category name as the object and build the ribbon without proprietary art. If the name is long, give it a deliberate compact two-line lockup rather than shrinking everything. Pricing opens with a 56px two-line promise and plan controls; enterprise and collection pages use a 56px centered title with 112px top padding. Articles instead open left-aligned with a 44px outcome headline and a right-hand fact card.

**Avoid:** Do not replace the opening with a split-screen dashboard mockup, a dark hero, a long paragraph, or a huge solid-color gradient slab.

**Text style:** `display` — Poppins 500 · 112px/0.96 · tracking -0.055em

### Heading pair

**Observed:** A 36px Section-heading with 12px–16px to an 18px Support line precedes content by about 40px. Most headings are centered; output galleries use a left-aligned group with a 576px measure. Major sections use 128px vertical padding.

**Transfer:** Announce the benefit or the proof in a short phrase; let the cards explain the detail.

**Text style:** `section-heading` — Poppins 500 · 36px/1.25 · tracking -0.01em

### Capability workbench

**Observed:** Feature workbench layout inside the Content container: two wide Capability cards above three narrower cards. The illustrations are more prominent than the copy trays and share a restrained light palette.

**Transfer:** Group related capabilities by visual complexity, letting the most explanatory scenes span wider tracks.

### Output gallery

**Observed:** A left-aligned Heading pair introduces a three-column Gallery of six cards, 24px apart. Images dominate each card, while the caption strip remains shallow.

**Transfer:** Present a curated range of realistic outputs, not generic decorative illustrations.

### Layered social proof

**Observed:** A centered Heading pair leads to documentary media beside a case-study title and understated read link. A separate 1152px by 320px proof card carries a large 60px Stat, small explanatory text, a read link and atmospheric artwork; compact carousel indicators sit at the lower right. Smaller quote cards can follow.

**Transfer:** Combine a human story with one verified outcome. Keep the outcome typography much larger than the explanatory text.

**Text style:** `stat` — Inter 500 · 60px/1 · tracking -0.02em

### Featured quote and story mosaic

**Observed:** A 24px-corner featured quote panel uses the Diffuse proof mesh and 30px Quote-display. Below it, a wide interview tile sits beside a narrower testimonial; a lower row contains three compact quote cards with logos, attributions and small dark circular arrows.

**Transfer:** Use this arrangement for a customer collection or enterprise proof chapter, not as the default hero.

**Text style:** `quote-display` — Poppins 500 · 30px/1.25 · tracking -0.01em

### Testimonials masonry

**Observed:** Three columns of White cards with 20px gutters, 24px inner padding and varied heights. Quote-body is 16px/1.625; circular portraits and two-line attributions sit below each quote.

**Transfer:** Let genuine quote length set card height and keep author rows consistent.

### Plans and practical details

**Observed:** A centered pricing title and support lead to Billing switch and four plan cards with 16px gutters. Recommended plan receives a dark outline and stronger shadow. Beneath, one 24px-corner quiet information panel splits into two text columns, followed by a monochrome trust-logo band.

**Transfer:** Give plan fit, price, inclusions and action separate aligned zones. Keep operational details outside the plan cards.

**Text style:** `pricing-display` — Poppins 500 · 56px/1.1 · tracking -0.02em

### Enterprise capability bento

**Observed:** A Heading pair precedes alternating two-thirds and one-third White cards in a six-track grid with 16px gutters. Technical line diagrams occupy the upper half; small blue labels, 20px titles and compact gray descriptions sit at the bottom. Role-oriented cards elsewhere use three equal columns with 32px padding and 48px icon wells.

**Transfer:** Use the wide panels for concepts requiring context and the narrow ones for a single assurance.

### Editorial customer story

**Observed:** A 688px prose area sits beside a compact persistent fact card with a 48px gap. The opening contains a back link, Article-title, a left-ruled lead quote, introductory prose and landscape video. Article-heading chapters alternate paragraphs and Article pull quote panels. A final author row closes the reading column, then the shared footer begins without an extra marketing CTA.

**Transfer:** Tell the practical sequence of problem, changed workflow and outcome; use the sidebar for contextual facts rather than repeating the article.

**Text style:** `article-title` — Poppins 500 · 44px/1.05 · tracking -0.02em

### Ruled objections

**Observed:** A centered Section-heading and optional Support precede the FAQ measure by 40px. FAQ rows form a continuous stack of fine rules with quiet chevrons, no rounded individual cards.

**Transfer:** Use this format for focused objections specific to the current buying decision.

### Graphic closing call

**Observed:** Polished closing panel at 1152px width, followed by 128px of separation before the footer. Default treatment uses Dot field and two 48px statement lines, slightly staggered horizontally, followed by paired actions. Secondary marketing versions substitute Diffuse proof mesh, one centered headline and a short support line.

**Transfer:** Use complementary reader/product clauses to give the closing a memorable cadence. Keep the graphic device even when changing the words.

**Text style:** `closing-heading` — Poppins 500 · 48px/1.25 · tracking -0.01em

### Utility footer and playful edge

**Observed:** A white footer with a fine top border uses 64px vertical padding inside the Content container. Brand and a short gray tagline sit left; four link columns sit right with 48px gaps. A ruled lower row carries copyright and 18px social icons. The Sculptural sign-off sits below this utility area in its own 148px white strip on every page type.

**Transfer:** Keep the operational footer orderly and restrained so the small sculptural ending feels intentional.

## Page flow

**Storyline:** Luminous promise → tangible capabilities or choices → human and quantified proof → focused objections → graphic invitation → practical footer with playful sign-off.

### Product marketing landing page

1. **Promise** — Product-name stage with aurora light, paired actions and pale trust ticker.
2. **Capability chapters** — Illustrated workbench cards with wide and narrow spans.
3. **Product demonstration** — Output gallery with author captions.
4. **Social proof** — Documentary story, oversized outcome card and smaller quotations.
5. **Objection handling** — Narrow ruled FAQ.
6. **Closing call** — Two-part statement on a dotted glazed panel.
7. **Wayfinding and sign-off** — White footer followed by clipped colorful sculptures.

**Transfer:** Keep the contrast between a spacious atmospheric promise and concrete evidence-rich middle blocks; adapt their order to the product.

### Customer outcome article

1. **Outcome hook** — Long left-aligned title, lead quotation and contextual fact sidebar.
2. **Context** — Introduction and interview still.
3. **Changed workflow** — Short chapters of humanist prose interrupted by periwinkle pull quotes.
4. **Outcome** — Concluding paragraphs and author attribution.
5. **Wayfinding and sign-off** — Direct transition into the shared footer and sculpture strip.

**Transfer:** Keep an editorial reading pace rather than adding sales cards between every chapter.

### Pricing decision page

1. **Choice framing** — Centered promise and support with a pill billing switch.
2. **Pricing** — Four aligned plans with one recommended entry option.
3. **Risk reduction** — Two-column operational details and trust-logo band.
4. **Objection handling** — Plan-specific ruled FAQ.
5. **Closing call** — Mesh-backed free-start invitation with paired actions.
6. **Wayfinding and sign-off** — Shared footer and sculpture strip.

**Transfer:** Make price, fit and inclusions comparable before explaining the operational details.

### Customer proof collection

1. **Orientation** — Compact centered title and explanatory line.
2. **Featured proof** — Mesh-backed quote, documentary story and smaller customer cards.
3. **Breadth of trust** — Monochrome logo grid.
4. **Peer proof** — Three-column masonry quotes.
5. **Closing call** — Soft mesh panel with a short question and paired actions.
6. **Wayfinding and sign-off** — Shared footer and sculpture strip.

**Transfer:** Move from a single memorable story to broad corroboration, rather than treating all proof as identical logo tiles.

### Enterprise evaluation page

1. **Promise** — Centered two-line title, outcome support and two 48px actions.
2. **Trust** — Two-row monochrome logo grid.
3. **Audience fit** — Three role cards with pastel icon wells.
4. **Capability assurance** — Alternating wide/narrow diagram bento.
5. **Customer proof** — Featured quote and documentary mosaic.
6. **Objection handling** — Enterprise-specific ruled FAQ.
7. **Closing call** — Soft mesh panel with self-service and sales actions.
8. **Wayfinding and sign-off** — Shared footer and sculpture strip.

**Transfer:** Keep the airy brand presentation while making technical assurance concrete through diagrams, concise descriptions and independently supportable proof.

## Writing

Confident, helpful and product-literate, with brief flashes of play. Benefits are expressed as tangible changes to work rather than grand predictions.

**Do not copy:** Do not reuse the brand names, logos, character artwork, customer quotations, usage counts, speed claims, certifications, prices or other proprietary claims. Substitute original assets and substantiated facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for possibilities, we for the product's contribution, and named people or teams for proof. Product descriptions can use direct imperatives.
- **Rhythm:** Short benefit headings, a single support sentence or two balanced lines, then compact explanatory prose. Case-study headlines can be longer and outcome-led; article paragraphs stay straightforward and conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening | A brief introduction followed by a short product name. | One introductory word plus a compact name | “Introducing” |
| Capability heading | An active verb plus a concrete object or outcome. | 4–8 words | “Match your existing designs”<br>“From idea to handoff, on one canvas” |
| Support | Explain the workflow change in plain language. | One sentence, roughly 12–25 words | “Turn a prompt, requirement, or feature idea into high-fidelity UI in minutes, and explore directions before you commit.” |
| Proof headline | Name a user and contrast the old time or difficulty with the new outcome. | 12–18 words | “How Toast turns weeks of design work into research-ready prototypes in days” |
| Primary action | Short direct invitation; emphasize a low barrier when true. | 2–4 words | “Get Started”<br>“Start for Free” |
| Closing statement | A reader contribution paired with the product contribution, or a short possibility question. | Two short clauses or one brief question | “You bring the context.”<br>“What will you build?” |

**Words and phrasing to use:** bring; build; explore; ideas; together; your; from…to…; before you commit; with confidence

**Avoid:** revolutionary; paradigm shift; unleash limitless potential; disrupt everything; synergy; unsubstantiated superlatives

**Rules:**

- Tie feature copy to something the reader can make, decide or hand off.
- Explain enterprise value with specific controls and practical consequences, not only the word enterprise.
- Let customer voices sound like people; keep the product's own prose more restrained.
- Use a memorable balanced closing line rather than another exhaustive feature summary.

## Do's and Don'ts

### Do

- Keep the product-name headline at medium weight with -0.055em tracking.
- Preserve the 16px inset white stage and the light ribbon as the first-screen focus.
- Use 1152px alignment for cards, closing panels and footer.
- Give capability copy trays 24px padding and a thin top rule.
- Use 128px desktop section padding to separate dense groups.
- Keep ordinary card shadows near 0px 1px 2px at 5% black.
- Pair 44px dark and white actions with 12px between them.
- Retain the 20px dot field and the clipped sculptural sign-off as distinct brand-like devices.

### Don't

- Do not make all text Poppins; small functional copy defaults to Inter.
- Do not turn 44px action buttons into full pills; pills belong to badges and switches.
- Do not color-fill every card with mint, blue or purple; most panels remain white.
- Do not use bold 700-weight display headings in place of the medium geometric treatment.
- Do not apply the recommended-plan shadow to ordinary capability cards.
- Do not enlarge the 11px watch badge into a dominant video overlay.
- Do not make testimonial columns equal-height rows when variable quote lengths create the intended masonry rhythm.
- Do not replace pale technical line diagrams with heavy multicolor infographic blocks.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color/background/border transitions at 0.1s with cubic-bezier(0.4,0,0.2,1). Footer opacity transitions use the same duration and easing.
- The pale logo marquee declares a 190s linear animation.
- Diffuse mesh layers declare 11s, 14s and 17s ease-in-out infinite alternate animations.
- Opening entry declarations include 0.65s cubic-bezier(0.22,1,0.36,1); some title and light effects are paused. A feature demonstration includes a Pause control.

**Transfer:**

- Keep atmospheric movement much slower than control feedback.
- Treat ribbon and mesh as background movement while the text and action row remain stable.
- Provide a pause mechanism for a continuously playing workflow demonstration.

**Unknown:**

- The complete opening animation sequence, exact mesh keyframe paths and all interaction outcomes are not established.

### Responsive

**Observed:**

- Declared widths include 640px, 768px, 1024px and 1280px among other framework breakpoints.
- Gallery classes declare one column, then two at the small breakpoint, then three at the large breakpoint. Feature cards declare a single column before the six-track layout.
- Pricing declares one, two and four plan columns. The article declares stacked layout before a side-by-side medium-width layout.
- Major sections declare 96px vertical padding before 128px on larger screens; desktop side padding is 32px, with 24px used at narrower widths.
- Secondary titles use the clamp formulas given in their type recipes.

**Transfer:**

- Stack capability scenes before their text trays; keep their pale backing and clipped corners intact.
- Keep the aurora ribbon edge-to-edge inside the opening frame, shorten support copy rather than creating many centered lines.
- Let the sculptural parade clip horizontally while preserving its shared baseline and white backing.

**Unknown:**

- Exact mobile opening display size, navigation collapse behavior and sculpture rearrangement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
