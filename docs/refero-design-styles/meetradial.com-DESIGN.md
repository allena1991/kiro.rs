# Radial — sunlit ripples of reassurance

## Overview

A warm, light marketing style that makes advanced services feel approachable rather than institutional. Buttercream, peach, powder blue, lilac and pale green surround light-weight neo-grotesk typography, grainy concentric artwork and candid human photography. Broad rounded shells and spacious compositions carry moderately dense explanations, making the style suited to services and products that need both trust and a sense of possibility.

### Essentials

- Reassurance comes through a light voice, not oversized shouting: use Unica 77 LL at 48px/1.1, weight 300 for the opening promise and 44.8px/1.1 for section statements, with normal tracking and sentence case.
- The opening is an enveloping ripple field rather than a product pedestal: a 900px-tall peach stage, concentric softly shaded bands, a centered headline about 729px wide, one cream action 24px below it and a delicate vertical line descending beneath.
- The interface floats inside rounded cream architecture: a 72px-high translucent navigation capsule with 160px radius and 7px blur, broad content shells with 80px corners, and smaller media cards with 28.8px corners.
- Actions feel like small lozenges against a large stage: 16px/24px text, 48px radius, 12.8px vertical and 32px horizontal padding; cream-filled primary actions and brown 1px outlined secondary actions.
- Color belongs to the atmosphere, not to noisy controls: pastel artwork fills the opening and closing stages and remains visible as narrow outer gutters around cream content through most of the body. Brown #625543 carries text, fine rules and restrained solid actions; large dark fields are limited to the 40px announcement strip.
- Human proof interrupts abstract softness: rounded 16:9 photographs show people using the service, while a tall 622px-wide image pairs with an equally broad tinted explanation panel. Use an authentic working scene for products without people-centered media, retaining the soft light and generous framing.
- A second signature device gives the softness structure: thin brown radial connectors with dot terminals turn a complex problem into a spacious diagram. Recreate this with the new product’s relationships, alongside the recurring grainy curved-band artwork; neither device depends on proprietary imagery.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Apricot light | `#f9e2bd` | `--color-peach` | background, accent | Opening stage, warm diagram chapter and focus outline. |
| Powder blue | `#c8d9f5` | `--color-blue` | background, surface | Default underlying canvas and tall image backing; one of the atmospheric chapter colors. |
| Lilac atmosphere | `#ddc8e2` | `--color-lilac` | background, accent | Curved-band closing atmosphere and later body chapters. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue panel light | `#c5d9f8` | `--color-blue-fade` | surface | Top of the blue explanation panel, fading to transparent. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Buttercream | `#fefbed` | `--color-cream` | background, surface, text | Broad content shells, footer, primary action fill and reversed text. |
| Warm brown ink | `#625543` | `--color-ink` | text, border, action | Primary text, fine connectors, outlined controls and the few solid dark actions. |
| Soft brown text | `#817667` | `--color-muted` | text | Secondary descriptions; visible result of brown at 80% over cream. |
| Cream hairline | `#dfdacf` | `--color-rule` | border | Visible result of brown at 20% over cream, used for separators and newsletter edges. |
| Warm card wash | `#f6f3e5` | `--color-card-wash` | surface | Visible result of brown at 5% over cream for understated directory cards. |
| Milky navigation | `#f3f4ef` | `--color-nav-wash` | surface | Cream at 80% over the blue canvas; the actual translucent navigation adapts to the chapter beneath it. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalog openings and culture-page endings | Pale sage | `#d3e6c7` | `--color-green` | background | Fresh green atmospheric chapter transitions. |
| offering catalogs | Catalog lilac | `#dccae1` | `--color-catalog-lilac` | background | Underlying offering-catalog canvas. |
| people directories | Directory lilac | `#dfcadf` | `--color-directory-lilac` | background, surface | Underlying people-directory canvas and tinted explanatory panel. |

## Typography

- **Unica 77 LL** — All headings, labels, prose and controls. Open, humane neo-grotesk with restrained regular text and notably light statement headings. If unavailable, use **Public Sans**. Use weights 300, 400 and 500; preserve normal tracking and tune line breaks to the broad original measure. Font stack: "Unica 77 LL", "Public Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Unica 77 LL | 300 | 48px | 1.1 | normal | Centered opening promise and select major closing statements. |
| heading | Unica 77 LL | 300 | 44.8px | 1.1 | normal | Main section statements, including explanatory panels and the final conversion invitation. |
| portal-heading | Unica 77 LL | 400 | 38.4px | 1.2 | normal | Centered question or destination title within a large illustrated link tile. |
| card-heading | Unica 77 LL | 400 | 25.6px | 1.2 | normal | Capability titles, process steps, article titles and names. |
| body-lead | Unica 77 LL | 400 | 19.2px | 1.5 | normal | Section introductions and closing support paragraphs. |
| body | Unica 77 LL | 400 | 16px | 1.5 | normal | Standard explanatory copy, actions and footer links. |
| eyebrow | Unica 77 LL | 500 | 16px | 1.2 | normal | Sentence-case category label above a statement heading. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| people directories | person-role | Unica 77 LL | 500 | 20px | 1.4 | normal | Professional role beneath a person’s name. |
| offering catalogs | compact-description | Unica 77 LL | 400 | 12.8px | 24px | normal | Small supporting explanations within secondary offering cards. |

**Notes:**

- Statement headings are lighter than their supporting text. Do not replace weight 300 with a bold display face.
- Normal tracking applies throughout; the identity comes from weight, measure and soft framing rather than tight letterspacing.
- Use 16px labels to introduce 44.8px statements, with a 16px gap. Card headings step down to 25.6px, not another oversized display tier.
- The desktop scale has no established viewport formula; preserve these sizes as the default and reflow copy before reducing it.

## Layout

**Density:** Airy at the chapter level, with comfortable explanatory text inside clearly grouped panels.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Base rhythm for section gaps and padding; type-related margins and button padding also use proportional values.

| Value | Use |
| --- | --- |
| 8px | Announcement padding and newsletter control inset. |
| 12.8px | Button vertical padding and card-heading bottom margin. |
| 16px | Eyebrow-to-heading spacing and stacked directory-card separation. |
| 22.4px | Bottom margin beneath statement headings. |
| 24px | Column gutter, standard card-body padding and headline-to-action gap. |
| 32px | Button horizontal padding, capability-column top padding and image separation. |
| 48px | Standard section top padding. |
| 60px | Large explanatory panel inner padding. |
| 64px | Catalog chapter inset and footer top padding. |
| 80px | Standard section bottom padding. |
| 160px | Top padding of compact secondary openings. |

### Containers and grids

- **content-container**: max width 1400px · side padding 86px. Centered desktop content spans about 1268px at a 1440px viewport; side inset is the desktop target, not extra padding added inside the max-width.
- **outer-shell**: max width 1568px · side padding 43px. Navigation and main cream shell leave narrow pastel gutters; the footer uses a slightly wider 1368px shell with 36px outer gutters at desktop.
- **paired-panels**: 2 columns · gap 24px. Two equal 622px-wide panels across the main content measure, used for media/text pairs, article pairs and illustrated destinations.
- **capability-columns**: 3 columns · gap 0px. Three equal columns about 430px wide with 24px inner side padding and 1px separating rules, not floating boxed cards.
- **process-columns**: 4 columns · gap 0px. An introductory column followed by three numbered columns across the main measure.
- **directory-column** (only for catalogs and people directories): max width 837px. Centered narrow stack for split offering cards or biographies, leaving generous cream space on both sides.
- **staff-grid** (only for people directories): 2 columns · gap 24px. Two portrait-first cards across the narrow directory column.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 48px |
| media-and-directory-cards | 28.8px |
| broad-shells-and-feature-panels | 80px |
| navigation | 160px |
| appointment-note | 16px |
| number-badges | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| appointment-note | `2px 4px 16px 0px rgba(0, 0, 0, 0.2)` | The small floating confirmation note only; large shells and cards stay flat. |

### Surfaces

#### Pastel canvas · level 0

**Use:** Atmospheric background outside the main content shell.

**CSS:** `background: #c8d9f5`

**Observed:** Warm peach dominates the opening, then blue and lilac frame later chapters. Color changes are broad environments rather than small badges.

**Transfer:** Keep a single pastel environment visible around each cream chapter.

#### Cream shell · level 1

**Use:** Continuous backing for multiple explanatory sections.

**CSS:** `background: linear-gradient(#fefbed, rgba(254, 251, 237, 0.65)); border-radius: 80px; box-shadow: none`

**Observed:** The landing-page body finishes with rounded lower corners; other long-form bodies round both ends. The visually prominent entrance is also softly rounded.

**Transfer:** Let several sections share this backing rather than adding a separate card around every paragraph.

#### Blue explanation fade · level 1

**Use:** Text panel beside a tall working-scene photograph.

**CSS:** `background: linear-gradient(#c5d9f8, rgba(197, 217, 248, 0)); border-radius: 80px; padding: 60px`

**Observed:** The tint is strongest at the top and dissolves into the cream body. A lilac version belongs to people-focused pages.

**Transfer:** Match the panel tint to the surrounding chapter, keeping the bottom visually open.

#### Footer cream · level 1

**Use:** The final broad utility panel.

**CSS:** `background: #fefbed; border-radius: 80px 80px 0px 0px`

**Observed:** This panel rises out of the closing atmosphere and reaches the bottom edge.

**Transfer:** Keep the final destination visually solid and reassuring after the textured closing field.

#### Low-contrast directory fill · level 2

**Only for:** catalogs and people directories

**Use:** Secondary offering and biography cards.

**CSS:** `background: rgba(98, 85, 67, 0.05); border-radius: 28.8px; overflow: hidden; box-shadow: none`

**Observed:** The warm wash barely separates the text half from the cream shell; the image half supplies most contrast.

**Transfer:** Use a tint, not a white elevated card.

## Components

### Floating navigation

**Use:** Persistent site orientation above every chapter.

**CSS:** `background: rgba(254, 251, 237, 0.8); border-radius: 160px; backdrop-filter: blur(7px); height: 72px`

**Text style:** `body` — Unica 77 LL 400 · 16px/1.5

**Observed:** A mark and wordmark sit left, medium-weight links occupy the middle, and two outlined utility actions sit right. The surrounding sticky header is 112px tall with 20px top and bottom breathing room; the selected link has a fine underline.

**Transfer:** Keep this as one continuous capsule, with a compact brand lockup and a concise link set.

### Cream primary button

**Use:** Primary action on illustrated opening and closing stages.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #fefbed; color: #625543; border-radius: 48px; padding: 12.8px 32px`

**Text style:** `body` — Unica 77 LL 400 · 16px/1.5

**Observed:** Text-only, centered, approximately 50px high; it sits directly on the atmospheric artwork without an icon.

**States:** Declared: hover background-color #62554333, outline 0px, text-decoration none; focus-visible 2px solid #f9e2bd outline with 2px offset; active outline 0px.

### Outline button

**Use:** Exploration actions in content sections and directory cards.

**CSS:** `display: flex; justify-content: center; align-items: center; border: 1px solid #625543; border-radius: 48px; padding: 12.8px 32px; color: #625543; background: transparent`

**Text style:** `body` — Unica 77 LL 400 · 16px/1.5

**Observed:** Approximately 52px high, sized to its short label. Navigation actions use 20px horizontal padding; sign-in has the weaker 20%-brown edge.

**States:** Declared: hover background-color #62554333, border-color rgba(98, 85, 67, 0), outline 0px and text-decoration none; focus-visible 2px solid #f9e2bd outline with 2px offset; active outline 0px.

### Illustrated destination tile

**Use:** Answer a practical question or lead to a useful destination.

**CSS:** `position: relative; aspect-ratio: 16 / 9; border-radius: 28.8px; overflow: hidden`

**Text style:** `portal-heading` — Unica 77 LL 400 · 38.4px/1.2

**Observed:** Two equal-width tiles pair peach and blue curved-band artwork. A centered question sits above a cream action, with no separate description.

**Transfer:** Use short questions or destinations and retain enough central low-contrast space for text.

### Number badge

**Use:** Mark stages in a concise process explanation.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 32px; height: 32px; border: 1px solid #625543; border-radius: 50%`

**Text style:** `body` — Unica 77 LL 400 · 16px/1.5

**Observed:** Two-digit number above a horizontal rule and a card-heading title. The badge is small enough to read as an annotation rather than a pictogram.

### Newsletter capsule

**Use:** Single-field subscription form in the footer.

**CSS:** `display: flex; justify-content: space-around; border: 1px solid rgba(98, 85, 67, 0.2); border-radius: 48px; padding: 8px 8px 8px 24px`

**Text style:** `body` — Unica 77 LL 400 · 16px/1.5

**Observed:** Email entry and a dark brown Subscribe pill share one 514px-wide, 66px-high outline. The inset action is about 121px by 48px with 24px horizontal padding; a small heading and smaller support line sit above.

### Footer directory

**Use:** Final navigation, contact information and subscription.

**CSS:** `background: #fefbed; border-radius: 80px 80px 0px 0px; padding: 64px 0px 32px`

**Text style:** `body` — Unica 77 LL 400 · 16px/1.5

**Observed:** A small standalone mark and newsletter form occupy about five twelfths of the content width. The right half is a three-column directory, followed by another row of legal and contact groups. Group headings are medium weight, links regular; a small trust badge finishes beneath the first utility group.

**Transfer:** Preserve the asymmetry and generous empty space beneath the form rather than balancing all columns to equal density.

### Capability column

**Use:** Parallel comparison of a few major capabilities.

**CSS:** `padding: 32px 24px; border-right: 1px solid rgba(98, 85, 67, 0.2)`

**Text style:** `card-heading` — Unica 77 LL 400 · 25.6px/1.2

**Observed:** Title, regular body description and Outline button occupy the upper region; a rounded landscape photograph anchors the bottom. Three columns share a top rule and two fading vertical separators; the last column has no outer rule.

**Transfer:** Align media bottoms and allow descriptions to vary slightly in length instead of forcing equal text blocks.

### Split directory card

**Only for:** catalogs and people directories

**Use:** A secondary offering or expert biography with adjacent photographic proof.

**CSS:** `background: rgba(98, 85, 67, 0.05); border-radius: 28.8px; overflow: hidden; margin-bottom: 16px`

**Text style:** `card-heading` — Unica 77 LL 400 · 25.6px/1.2

**Observed:** A centered 837px-wide card divides into roughly equal text and image halves. Text has 24px padding; title, role or concise explanation and an Outline button stack in that order. The image fills the right half to the outer rounded edge; height follows the text.

**Transfer:** Use the same framing for specialists, partners or detailed capabilities, not as the default container for every section.

## Imagery and graphics

### Grainy concentric light

**Use:** Signature opening artwork, illustrated destination tiles and the closing conversion atmosphere.

**Observed:** Broad nested circular or pill-shaped bands feel like softly lit paper relief: peach on cream in the opening, opposing blue curves in a destination tile, lilac curved folds behind the closing call. Fine grain prevents the gradients from looking digitally slick; the center stays pale enough for brown text.

**Transfer:** Use these curves as a complete visual asset even when the product has no photography or render. Match the soft glow; exact gradient stops are not essential.

**Build:** Create an SVG with 5–7 nested ellipses, centered for the opening and offset beyond opposite edges for tiles. At 1440px width, start the central opening ellipse around 800px wide and 850px high; expand successive contours by roughly 150px horizontally. Fill each band with a cream-to-peach gradient, adding rgba(210, 120, 90, 0.18) along one edge and rgba(254, 251, 237, 0.5) along the other. Layer a low-opacity SVG feTurbulence grain texture over the field. For the close, switch to lilac with rgba(155, 90, 170, 0.18) shading and mirrored curves entering from left and right. Keep the text region free of hard edges.

### Radial relationship diagram

**Use:** Signature explanatory graphic within a spacious problem or possibility chapter.

**Observed:** A fine vertical stem connects the preceding stage to a central node. Thin unevenly angled brown spokes end in small solid dots with nearby 16px labels. The headline occupies the upper left while a larger supporting paragraph sits at the lower right; the diagram owns the central negative space.

**Transfer:** Map a product’s real relationships or challenges with short plain-language labels. This is a diagram, not a quantitative chart, and it needs no fabricated statistics.

**Build:** Use a responsive SVG with a 1px brown vertical line through the middle and 6–8 1px radial lines reaching uneven distances to both sides. Place 4–8px brown terminal circles, then position labels just outside each terminal. Reserve the upper-left and lower-right quadrants for prose and fade the vertical stem toward the section edges.

### Human working scenes

**Use:** Capability photography and the tall media half of an explanatory pair.

**Observed:** People interact with real treatment equipment in bright rooms. Landscape images show faces, hands and devices at a useful scale; the tall scene includes the practitioner, seated patient, equipment, floor and a small rug against a strong blue wall. Images are naturally colored, softly lit and clipped to rounded frames, without heavy overlay text.

**Transfer:** Show a real user and the mechanism of the offering in context. If people are not relevant, use a complete working environment or a close operational scene rather than a glossy isolated render.

### Diffused editorial photography

**Use:** Article-pair media that should suggest a theme without illustrating a literal procedure.

**Observed:** Anonymous human silhouettes appear behind rippled or translucent glass, in muted green, teal and warm beige. The two 622px by 350px images have softened detail and rounded corners; titles and summaries sit below, not over them.

**Transfer:** Photograph a simple human presence through translucent material, or combine a softly defocused portrait with a subtle ribbed-glass displacement treatment. Keep the result atmospheric but legible as photography.

### Individual portrait directory

**Only for:** people directories

**Use:** Expert biographies and portrait-first staff grids.

**Observed:** Head-and-shoulders or seated portraits retain their original natural, studio or office backgrounds. Some are monochrome, most full color; all fill their image half with consistent rounded outer clipping. The main directory uses horizontal text-left cards, while a later staff group uses two portrait-first cards per row.

**Transfer:** Unify varied portraits by framing and card construction rather than applying a uniform color filter.

### Petal-like principle symbols

**Only for:** culture and principles sections

**Use:** Graphic markers above text in a four-column values panel.

**Observed:** Solid warm-brown circular, petal and intersecting-lobe silhouettes sit above 25.6px titles. Their abstract forms are fuller and softer than standard outline interface icons.

**Transfer:** Give each principle a simple geometric emblem, not a literal stock pictogram.

**Build:** Compose 2–6 filled circles or elongated ellipses in SVG, using rotations or cream cutouts to create a crescent, petal cluster or overlapping lobes. Keep each within roughly 64px square, filled with the same ink as the text.

### Icons

**Observed:** Interface iconography is sparse. A small chevron accompanies the announcement, the brand mark appears alone at roughly 26px by 28px in the footer, and filled abstract emblems belong to the principles panel.

**Transfer:** Do not introduce a large library of line icons into ordinary feature cards. Let small circles, rules and numbers carry most of the annotation work.

## Section recipes

How recurring sections are built.

### First screen: Enveloping ripple opening

**Observed:** A full-width 900px peach stage sits below a 40px announcement strip. Back to front: softly grainy concentric relief artwork, a pale central opening, centered brown display text, one Cream primary button, then the Floating navigation near the top. The headline spans about half the viewport in two lines, with a 729px measure and 48px/1.1 weight-300 type. It sits near the middle vertically, with a 24px action gap. A delicate brown line begins below the action and extends downward into the next chapter. Within the first 900px the announcement, navigation, entire promise, action and most of the ripple field are visible; supporting explanation and the diagram belong below the fold. There is no separate hero support paragraph or product object competing with the headline.

**Transfer:** For a new landing page, let the curved field be the main object and place a concise promise in its pale center. Products without suitable media still use the complete ripple artwork, not an empty hero. Secondary catalog and directory openings compress the same idea: 160px top padding, a centered sentence-case eyebrow, 48px statement and optional 16px support, with a rounded cream body entering within the first screen.

**Avoid:** Do not substitute a left-aligned SaaS hero with a dashboard on the right, or pack supporting bullets and multiple actions into the central aperture.

**Text style:** `display` — Unica 77 LL 300 · 48px/1.1

### Problem constellation

**Observed:** An almost full-screen warm peach chapter puts an eyebrow and Heading at upper left, the Radial relationship diagram across the center and a Body-lead paragraph at lower right. The vertical connector visually continues the opening line.

**Transfer:** Explain a complex context with a small set of short labels while preserving large areas of negative space.

**Text style:** `heading` — Unica 77 LL 300 · 44.8px/1.1

### Practical reassurance pair

**Observed:** Inside the Cream shell, an eyebrow and multi-line Heading occupy the left half while a Body-lead explanation occupies the right. After about 55px, two Illustrated destination tiles span the Paired-panels grid.

**Transfer:** Use this to answer two concrete pre-conversion questions, such as availability, setup or commercial fit, without changing to a dense FAQ layout.

**Text style:** `heading` — Unica 77 LL 300 · 44.8px/1.1

### Numbered process strip

**Observed:** The Process-columns grid gives the first quarter to a Heading and Body-lead introduction, followed by three Number badges, rules, Card-heading titles and regular supporting copy. An Outline button and short reassuring line sit beneath the step region.

**Transfer:** Choose a small number of concrete stages and make their verbs easy to scan; the introductory column should remain distinct from the numbered items.

**Text style:** `card-heading` — Unica 77 LL 400 · 25.6px/1.2

### Working scene and explanation

**Observed:** Paired-panels aligns a tall Human working scenes image with the Blue explanation fade. A Heading and two short paragraphs lead into fine ruled benefit lines. A small cream confirmation note with 16px corners and the Appointment-note shadow overlaps the lower text region.

**Transfer:** Pair a complete working scene with an explanation of the operating model. The floating note should show a credible moment of service, not decorative analytics.

**Text style:** `heading` — Unica 77 LL 300 · 44.8px/1.1

### Capability overview

**Observed:** A centered eyebrow and two-line Heading introduce three Capability columns. Their upper text regions contain title, explanation and exploration action, with landscape human imagery anchored below.

**Transfer:** Compare major categories with practical distinctions; keep the shared shell and rules instead of making each column an elevated card.

**Text style:** `heading` — Unica 77 LL 300 · 44.8px/1.1

### Editorial pair

**Observed:** A centered Heading introduces two equal landscape images from Diffused editorial photography, each followed by a Card-heading title and short Body summary. There is no heavy card border or separate button beneath the summary.

**Transfer:** Offer two substantial reading routes, allowing the title itself to carry the action.

**Text style:** `heading` — Unica 77 LL 300 · 44.8px/1.1

### Atmospheric closing and useful footer

**Observed:** A centered Heading, Body-lead support and Cream primary button sit on lilac curved-band artwork. The total closing region is about 1059px tall including a 591px Footer directory, whose cream panel rises in front of the artwork. Newsletter and utility navigation remain visible all the way to the bottom. The people-focused ending instead uses a pale-green-to-cream field with a short 48px recruitment question and Outline button before the same footer.

**Transfer:** End the ordinary marketing page with a human-scale invitation and a full atmospheric field, then the grounded utility panel. Use the shorter green ending for recruiting or organizational content.

**Text style:** `heading` — Unica 77 LL 300 · 44.8px/1.1

### Narrow offering stack

**Only for:** offering catalogs

**Observed:** A compact green curved-band opening leads into two broad primary-offering columns with 44.8px headings, Body-lead descriptions, solid brown actions and large photographs. A later chapter narrows to an 837px column, with a Heading and introduction above three Split directory cards.

**Transfer:** Distinguish primary categories from detailed secondary offerings by changing measure and card construction, not by adding a new visual theme.

**Text style:** `heading` — Unica 77 LL 300 · 44.8px/1.1

### Expert directory chapters

**Only for:** people directories

**Observed:** A compact peach opening and centered relational statement lead to a three-image community strip. Category headings and short introductions then separate a long narrow stack of Split directory cards. Names use Card-heading; professional roles use Person-role. A later group switches to the Staff-grid with portrait-first cards.

**Transfer:** Group people by meaningful expertise, letting description length determine card height while image framing keeps the long scroll coherent.

**Text style:** `card-heading` — Unica 77 LL 400 · 25.6px/1.2

### Principles panel

**Only for:** culture and principles sections

**Observed:** A 48px light heading sits above a four-column panel on a pale green environment. A horizontal rule separates the heading from filled Petal-like principle symbols, Card-heading titles and regular paragraphs; fine vertical rules separate columns.

**Transfer:** Use this format for a small set of commitments or decision principles, keeping the graphic emblems abstract.

**Text style:** `display` — Unica 77 LL 300 · 48px/1.1

## Page flow

**Storyline:** promise → context and reassurance → explanation or detailed choices → human proof → useful next step → utility directory

### Broad marketing landing page that makes an advanced offering feel understandable and accessible

1. **Promise** — Full-screen curved-band opening with one centered statement and action.
2. **Problem framing** — A sparse radial diagram links a complex field to one central model.
3. **Objection handling** — A cream-shell heading pair introduces two practical illustrated destinations.
4. **Process explanation** — An introductory column and small numbered stages reduce uncertainty.
5. **Human proof** — Tall working-scene photo, tinted explanation panel and small confirmation note; professional affiliations provide a quieter proof strip.
6. **Capability chapters** — Centered introduction and three ruled, photo-backed capability columns.
7. **Education** — Two atmospheric article cards extend the explanation.
8. **Closing call** — Lilac curved-band invitation followed by the newsletter and full utility directory.

**Transfer:** Use this as a narrative of confidence-building, adapting the number and placement of explanations to the product rather than reproducing every block.

### Offering catalog that helps readers distinguish approaches and explore details

1. **Category promise** — Compact green illustrated opening with a category label and centered statement.
2. **Primary choices** — Two large offering columns combine plain-language mechanisms, photographs and solid brown actions.
3. **Detailed choices** — A narrower stack of split image-and-copy cards carries secondary offerings, followed by a centered qualification note.
4. **Closing call** — The same lilac invitation and utility directory used for the general marketing experience.

**Transfer:** Separate primary and secondary choices through layout scale, and add a clear scope or availability note before the closing invitation.

### People and organizational trust page, with enough detail to support expert selection

1. **Expertise promise** — Compact peach illustration, category label, centered statement and a short human introduction.
2. **Social proof** — A relational heading and three community photographs.
3. **Expertise directory** — Category-led horizontal biographies, then a smaller portrait-first staff grid.
4. **Operating model** — A tall working scene and lilac explanation panel with concrete service details.
5. **Principles** — Four ruled columns with abstract filled emblems and descriptive commitments.
6. **Closing call** — Short recruitment invitation on a green fade followed by the full cream utility directory.

**Transfer:** Keep biographies grouped and readable, then use operating principles and a purpose-specific final invitation instead of forcing a sales close.

## Writing

Warm, clear and optimistic, with institutional confidence expressed in accessible language. Technical mechanisms and qualifications support the promise rather than replacing it with jargon.

**Do not copy:** Do not reuse Radial’s name, logo, treatment names, staff identities, partnership announcement, affiliations, clinical outcome numbers, regulated claims or proprietary copy as the new product’s assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use “you” and “your” for the reader’s needs; use “we” for responsibility and service commitments. Prefer a named human role over an impersonal conversion funnel.
- **Rhythm:** Statement headlines are often 7–15 words and may run to two or three lines. Supporting paragraphs are short but explanatory, with occasional compact contrast sentences and almost no promotional punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Lead with access to a beneficial advance, using a complete sentence rather than a slogan fragment. | 8–13 words | “Access the world’s most advanced mental health treatments.” |
| Section statement | Name a real problem, then take responsibility for a better approach. | 8–16 words | “Mental health care is broken. We’re building a better way.”<br>“We believe in transformation, not just treatment.” |
| Supporting explanation | Describe the next interaction and how it reduces uncertainty in practical terms. | 20–40 words | “Your care navigator will explain the process, discuss insurance and costs, and connect you with a clinician to explore today’s most advanced mental health treatments.” |
| Primary action | A short familiar verb phrase without a promise crammed into the button. | 1–3 words | “Get started”<br>“Learn more” |
| Process step | Start with a concrete action involving a real person or clear milestone. | 2–5 words | “Talk with our team”<br>“Meet your clinician” |
| Final invitation | Offer a manageable first conversation instead of demanding a commitment. | 8–14 words | “Take the first step and talk to a care navigator.” |

**Words and phrasing to use:** access; support; understand; effective; evidence-backed; your journey; first step; team; transformation

**Avoid:** dominate; crush it; revolutionary magic; guaranteed results; hustle; exclusive elite access

**Rules:**

- Translate a technical mechanism into an everyday benefit in the same paragraph.
- Pair ambitious promises with concrete process, eligibility or qualification language.
- Use contrast sparingly to express a belief: a better outcome, not merely a smaller improvement.
- Write practical destination headings as the questions readers actually ask.
- Make reassurance specific: explain who responds, what happens next and what remains uncertain.

## Do's and Don'ts

### Do

- Keep opening statements at 48px/1.1 and weight 300, preserving their relaxed width.
- Use the 72px translucent capsule as a continuous navigation surface over changing pastel fields.
- Retain 80px radii for broad shells and tall feature panels, but 28.8px for ordinary media.
- Place 16px sentence-case eyebrows 16px above light statement headings.
- Use 1px brown hairlines at 20% opacity to organize cream content without boxed outlines.
- Keep the 12.8px by 32px action padding and 48px radius consistent across content actions.
- Stage human photography in 16:9 landscape frames or broad tall panels, with useful environmental context.
- Give the closing invitation a curved lilac atmosphere and a solid cream utility panel beneath it.

### Don't

- Do not replace warm brown text with pure black or introduce cold white as the dominant shell color.
- Do not turn the pastel palette into saturated button colors; controls remain brown and cream.
- Do not use tight negative tracking or weight 700 for the 44.8px section statements.
- Do not apply the confirmation note’s shadow to the main shell or directory cards.
- Do not use 8px corners on broad panels; that changes the soft architectural scale.
- Do not turn the three capability columns into detached elevated tiles with large gutters.
- Do not impose a uniform monochrome filter on varied expert portraits.
- Do not spread the compact 12.8px catalog-description recipe into ordinary body paragraphs.

## Motion and responsive

### Motion

**Observed:**

- Actions declare color, border-color and background-color transitions of 0.2s with ease timing; short links declare opacity transitions of 0.2s.
- Outlined buttons declare a translucent brown hover fill and transparent border. Text links declare hover opacity 0.75.
- Navigation stays above the content as a sticky header. The visual chapter palette changes as the page progresses.

**Transfer:**

- Keep interaction feedback subtle and localized to fill, border or opacity so that the large curved artwork remains the visual focus.
- Retain the sticky milky navigation as the stable layer over pastel chapter changes.

**Unknown:**

- No settled animation choreography or timing for atmospheric transitions is established.
- No reduced-motion behavior is established.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 768px, 991px, 992px and 1180px.
- Desktop column classes distinguish narrower layouts for paired panels, process strips, biography cards and capability columns.

**Transfer:**

- On narrow layouts, stack paired panels and horizontal biography halves; keep image context and reduce the large panel’s inner padding before shrinking body type.
- Keep the opening promise inside the pale center of the ripple art; clip the outer bands rather than scaling the entire composition into a tiny picture.
- Convert ruled multi-column sections into vertically separated items and let the footer form precede its utility groups.

**Unknown:**

- Exact mobile font sizes, navigation menu construction, shell radii and padding are not established.
- No viewport-relative typography formula is established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
