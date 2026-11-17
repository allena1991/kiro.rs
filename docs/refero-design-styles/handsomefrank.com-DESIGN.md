# Handsome Frank — storybook swagger

## Overview

A confident, playful editorial style with chunky, characterful serif headlines and matter-of-fact grotesk supporting text. Deep violet and warm paper anchor a succession of saturated colour stages, populated by lively illustration and carefully isolated product photography. It suits creative products and services with work worth showing: spacious in composition, rich in imagery, and conversational rather than corporate.

### Essentials

- A storybook voice at billboard scale: Millik headlines at 80px/0.95 with 1.6px tracking open the page; 70px/0.98 with -1.6px tracking carry the chapters.
- The opening is a declaration, not a conversion dashboard: a 900px deep-violet stage, a centered 864px headline group, a 42px serif support line 24px below, and only a small identity and 42px circular menu above.
- Colour occupies whole chapters rather than small decorations: most of the narrative is made of edge-to-edge 720px colour stages; warm #f8f3ef gallery interludes provide contrast. Each stage pairs its background with deliberately chosen headline and link colours.
- Actions remain part of the typography: 38px serif text links have no enclosing button; the browse action adds a 42px orange eye disc. Rounded 58px form controls are a separate, limited family.
- Artwork leads the proof: sharp rectangular portrait tiles in four columns with 40px gutters and 22px serif captions alternate with half-width, edge-anchored cutouts. Use original product compositions or simplified editorial illustrations when no portfolio artwork exists.
- Keep the playful closing machinery: coloured editorial cards with 220px circular image windows, a 70px single-line news ticker with 124px circular pictures, and a 120px violet action band. Adapt the subjects and placement, not these contrasting geometric devices.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet ink | `#160572` | `--color-ink` | text, background, link | Primary headings on paper and the closing action band. |
| Opening violet | `#15047d` | `--color-hero` | background | Default full-screen opening field. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Opening cream | `#fffac2` | `--color-cream` | text | Serif support line on the default violet opening. |
| Menu mint | `#27d5b4` | `--color-mint` | action, text | Circular menu background; also headings and links inside specialist service cards. |
| Eye orange | `#ff4500` | `--color-orange` | action | Eye disc beside browse links. |
| Peach stage | `#edaf78` | `--color-peach` | background | A warm feature stage paired with terracotta text. |
| Terracotta | `#d64e2e` | `--color-terracotta` | text, link | Headlines, copy and links on the peach stage. |
| Film violet | `#6f43f5` | `--color-purple` | background | Vivid media-led stage paired with yellow titles and white copy. |
| Film yellow | `#f9e44d` | `--color-yellow` | text, link | Heading and action on the vivid violet stage. |
| Newsletter blue | `#2d82e7` | `--color-blue` | background | Full-width signup stage. |
| Editorial green | `#28642f` | `--color-card-green` | surface | Default rectangular editorial card background. |
| Editorial butter | `#ffe778` | `--color-card-yellow` | text, surface | Editorial card title and circular image backing on green. |
| Ticker red | `#df1a19` | `--color-ticker-red` | text | Oversized news copy on the white ticker. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background | Text on colour stages, eye motif and the ticker background. |
| Warm paper | `#f8f3ef` | `--color-canvas` | background | Gallery and editorial canvas. |
| Editorial paper | `#f2ebe6` | `--color-editorial-paper` | background | Slightly darker paper behind the editorial card rail. |
| Black | `#000000` | `--color-black` | text | Gallery captions, supporting copy on paper and FAQ questions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company storytelling and FAQ sections | Salmon pink | `#f59895` | `--color-pink` | text, action | Selected names in the typographic proof wall and circular FAQ toggles. |
| FAQ sections | Paper rule | `#e6e1dc` | `--color-rule` | border | Thin FAQ separators. |
| company storytelling | Story slate | `#425570` | `--color-slate` | background | Illustrated origin-story carousel with white text. |
| specialist service pages | Service navy | `#1e2338` | `--color-service-card` | surface | Specialist information cards with mint headings and white paragraphs. |
| directory pages | Directory green | `#056538` | `--color-directory-green` | background | Closing cross-service illustrated stage. |
| directory pages | Directory lime | `#c8e81b` | `--color-lime` | text, link | Headline and action against directory green. |

## Typography

- **Millik** — Headlines, captions and prominent actions. Heavy, broad, swelling serif shapes with lively asymmetric details and a friendly storybook silhouette. If unavailable, use **Fraunces**. Use weight 700; retain broad shapes and the tight chapter-leading. Font stack: "Millik", "Fraunces", Georgia, "Times New Roman", serif.
- **Klarheit Grotesk** — Supporting paragraphs and explanatory text. Clean, rounded grotesk with substantial x-height; semibold support copy offsets the ornate serif. If unavailable, use **DM Sans**. Use 600 for feature support and 400 for long service explanations. Font stack: "Klarheit Grotesk", "DM Sans", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Millik | 700 | 80px | 0.95 | 0.02em | Centered full-screen opening headline. |
| heading | Millik | 700 | 70px | 0.98 | -0.0229em | Feature chapter titles, editorial section leads and ticker text. |
| hero-support | Millik | 700 | 42px | 0.95 | 0.038em | Serif companion sentence beneath the opening headline. |
| heading-small | Millik | 700 | 38px | 0.98 | -0.042em | Centered introductory statement, browse links and FAQ questions. |
| action | Millik | 700 | 38px | 1 | -0.021em | Prominent unboxed text actions within coloured stages. |
| editorial-card-title | Millik | 700 | 32px | 0.98 | -0.05em | Compact, multi-line titles in editorial cards. |
| body | Klarheit Grotesk | 600 | 22px | 1.28 | normal | Default supporting paragraphs on feature stages. |
| caption | Millik | 700 | 22px | 1.1 | normal | Centered names beneath portrait gallery tiles. |
| form-action | Millik | 700 | 20px | 1 | normal | Centered submit label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| directory pages | directory-display | Millik | 700 | 88px | 0.98 | -0.0182em | Text-only directory opening. |
| directory and specialist service pages | body-strong | Klarheit Grotesk | 700 | 22px | 1.36 | normal | Directory introduction and specialist information card paragraphs. |
| specialist service pages | body-regular | Klarheit Grotesk | 400 | 22px | 1.36 | normal | Longer centered service introduction. |

**Notes:**

- The serif does the expressive work even in captions and links; the grotesk is reserved for explanation, not substituted for display headings.
- Opening tracking is positive, while chapter titles and compact statements tighten. Preserve these role-specific differences rather than applying one global tracking value.
- Headings use sentence case and often a terminal full stop. Long titles wrap into compact blocks rather than shrinking to fit a line.

## Layout

**Density:** Airy composition with dense expressive headlines; broad uninterrupted media stages separate regular gallery rhythms.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 18px | Feature title to supporting copy. | fixed |
| 20px | Gallery image to caption and form submit separation. | fixed |
| 24px | Opening headline to support; editorial card side and top padding. | fixed |
| 30px | FAQ rule offsets and gaps between FAQ items. | fixed |
| 36px | Supporting paragraph to feature text action. | fixed |
| 40px | Four-column gallery gutters and specialist card padding. | fixed |
| 60px | Gallery row separation and signup form offset from copy. | fixed |
| 80px | Major paper-section top and bottom spacing. | fixed |
| 86.4px | Default side inset for page content. | 6vw |

### Containers and grids

- **paper-content**: side padding 86.4px. Full-width paper sections with fluid side insets; content spans 1267px at a 1440px viewport.
- **opening-copy**: max width 864px. Centered opening headline and support group spanning about three fifths of desktop width.
- **gallery**: 4 columns · gap 40px. Equal portrait columns, 287px wide at desktop, with centered captions and 60px separation after each tile.
- **feature-stage**: 2 columns · gap 0px. Two 720px halves at desktop within a 720px-tall full-bleed stage; one side hosts art, the other a vertically centered text group.
- **signup**: max width 480px. One column of three inputs and one submit control.
- **service-grid** (only for specialist service pages): 2 columns · gap 38px. 615px-wide information modules alternating sides with paired media.

## Corner radius

| Element | Radius |
| --- | --- |
| gallery and editorial cards | 0px |
| eye and menu discs | 50% |
| editorial image windows | 50% |
| form controls | 30px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Neutral intervals and gallery backing.

**CSS:** `background: #f8f3ef`

#### Opening field · level 0

**Use:** Default first-screen stage.

**CSS:** `background: #15047d`

**Observed:** Flat, full-bleed violet with no texture, visible gradient or framing.

**Transfer:** Let the type establish the first impression; integrate media without adding a boxed hero panel.

#### Colour stage · level 0

**Use:** Feature chapters.

**CSS:** `background: #edaf78; border-radius: 0px; box-shadow: none`

**Observed:** Whole-width flat colour fields meet directly, without gutters or section cards. The default warm version pairs with terracotta text; other chapters use distinct contrasting colours.

**Transfer:** Choose one flat stage colour that relates to each featured object and keep it continuous behind copy and image.

#### Film stage · level 0

**Use:** Moving-image feature.

**CSS:** `background: #6f43f5; color: #ffffff`

**Observed:** Yellow title and action contrast with white explanation; media occupies the opposite half.

**Transfer:** Use this especially vivid pairing for a demonstrative or process-led chapter.

#### Editorial rail · level 0

**Use:** Backing for editorial cards.

**CSS:** `background: #f2ebe6; padding-top: 52px; padding-bottom: 80px`

#### Story field · level 0

**Only for:** company storytelling

**Use:** Narrative illustration carousel.

**CSS:** `background: #425570; color: #ffffff; padding-top: 160px; padding-bottom: 100px`

#### Service module · level 1

**Only for:** specialist service pages

**Use:** Detailed service information.

**CSS:** `background: #1e2338; color: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** Mint headline and link at opposite ends of a tall rectangular panel.

**Transfer:** Use for practical requirements and a related project, not as the default landing-page card style.

## Components

### Fixed navigation

**Use:** Persistent identity and menu access.

**CSS:** `position: fixed; display: flex; justify-content: space-between; align-items: center; height: 104px; padding-top: 28px; padding-left: 44px; padding-right: 44px; z-index: 123`

**Observed:** A compact two-line script identity sits at upper left and a small circular menu at upper right. The header has no opaque bar behind it; the light identity continues across coloured content.

**Transfer:** Use the new identity as a compact expressive mark, keeping navigation visually sparse.

### Menu disc

**Use:** Navigation toggle.

**CSS:** `width: 42px; height: 42px; background: #27d5b4; border-radius: 50%`

**Observed:** Two short centered horizontal lines inside the disc. The directory and specialist service variants use violet discs instead.

### Feature text link

**Use:** Action after feature support copy.

**CSS:** `display: inline-flex; align-items: center; height: 38px; margin-top: 36px; color: #d64e2e`

**Text style:** `action` — Millik 700 · 38px/1 · tracking -0.021em

**Observed:** An unboxed serif phrase matched to the chapter palette. It has an arrow mechanism and layered text, while the resting appearance is a simple text action.

**Transfer:** Write a contextual invitation, keeping the action visually continuous with the chapter headline.

### Eye browse link

**Use:** Centered gallery expansion and final browse action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 42px; color: #160572`

**Text style:** `heading-small` — Millik 700 · 38px/0.98 · tracking -0.042em

**Observed:** Orange eye disc precedes the label with a 10px gap. White eye and violet pupil animate within the disc; duplicated label layers present a single visible phrase. White lettering is used in the final violet band.

**Transfer:** Keep the eye as a small playful wayfinding device beside a browse action.

### Gallery tile

**Use:** Image-first proof of breadth.

**CSS:** `position: relative; width: 287px; margin-bottom: 60px`

**Text style:** `caption` — Millik 700 · 22px/1.1

**Observed:** Portrait image above a centered name with 20px separation; no panel fill, outline or rounded frame. New-item badges are white circles over selected directory images.

**Transfer:** Use a consistent portrait window for different subjects; let their original visual styles remain distinct.

### Editorial card

**Use:** Short reading recommendations.

**CSS:** `position: relative; width: 287px; height: 420px; padding: 24px 24px 38px; background: #28642f; color: #ffe778; border-radius: 0px`

**Text style:** `editorial-card-title` — Millik 700 · 32px/0.98 · tracking -0.05em

**Observed:** A tight multi-line title is pinned at the top; a 220px circular image window sits beneath it, centered toward the lower part. Each adjacent card gets its own high-contrast colour pairing.

**Transfer:** Use documentary photos, product details or illustrations in the circles; preserve the rectangular outside and circular inside.

### Signup input

**Use:** Email and personal-name fields on the signup stage.

**CSS:** `width: 480px; height: 58px; padding: 16px 16px 15px 32px; background: rgba(0, 0, 0, 0.1); border: 2px solid transparent; border-radius: 30px`

**Observed:** Three stacked fields with 10px separation; the blue backing remains visible through their dark tint.

### Signup submit

**Use:** Newsletter submission.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 480px; height: 58px; padding: 16px 16px 15px 32px; margin-top: 20px; background: rgba(0, 0, 0, 0.6); color: #ffffff; border-radius: 30px`

**Text style:** `form-action` — Millik 700 · 20px/1

**Observed:** Same width and silhouette as the inputs, with a much deeper translucent fill; a small consent control sits above it.

### News ticker

**Use:** Animated editorial closing device.

**CSS:** `display: flex; position: relative; align-items: center; height: 265px; padding-bottom: 20px; overflow: hidden; background: #ffffff`

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

**Observed:** A single oversized horizontal stream extends beyond both screen edges, interleaving coloured serif phrases and 124px circular images. A small centered copyright line sits below.

**Transfer:** Populate with genuine updates or useful product notes, not a row of partner logos.

### FAQ row

**Only for:** FAQ sections

**Use:** Answer practical questions without a dense text wall.

**CSS:** `display: flex; justify-content: space-between; align-items: center; min-height: 42px; color: #000000`

**Text style:** `heading-small` — Millik 700 · 38px/0.98 · tracking -0.042em

**Observed:** Full-width question with a 42px salmon circle containing a white plus at the far right. A 1px paper-coloured rule sits 30px below the title; the following item has another 30px separation.

### Service information card

**Only for:** specialist service pages

**Use:** Explain a capability, requirements or a related project.

**CSS:** `position: relative; width: 615px; height: 620px; padding: 40px; background: #1e2338; color: #ffffff`

**Text style:** `body-strong` — Klarheit Grotesk 700 · 22px/1.36

**Observed:** Mint 38px serif heading, 30px gap to the paragraph, illustrated detail in the middle when available and a mint action near the bottom. Cards alternate left and right in a spacious media-led grid.

## Imagery and graphics

### Portrait proof gallery

**Use:** Repeated image-led selection blocks.

**Observed:** Vivid editorial illustrations with varied subjects, from stylized people and architecture to food and graphic characters. Tall rectangular windows sit directly on warm paper; neither uniform colour grading nor UI-style frames flatten their differences.

**Transfer:** Show the new product's outputs, use cases or crafted details with similarly confident colour and consistent portrait proportions. A minimum version is a small set of original flat-colour illustrations with strong silhouettes.

### Edge-anchored feature artwork

**Use:** The main visual in colour-stage chapters.

**Observed:** Isolated illustrated figures, packaging and photographed objects occupy roughly one half of a full-width stage. Objects are anchored to the lower edge or intentionally clipped at the side; background colours merge into the section. Product photography retains material detail and natural object shadows.

**Transfer:** Prepare a transparent cutout or a photo on a precisely matching background. Use one dominant object rather than a collage of floating cards; when no object exists, draw a bold editorial metaphor in a limited palette.

### Circular editorial windows

**Use:** Inside rectangular reading cards and the horizontal ticker.

**Observed:** Hard circular masks show detailed prints, architectural photographs, animals and group portraits. The cards use 220px windows, while the ticker uses 124px circles; images are saturated and unfiltered.

**Transfer:** Use topical images with a readable central subject; keep the circle geometry even when the content changes.

**Build:** Use an SVG circle clipPath or an overflow-hidden element with border-radius:50%; size the card window to 220px and ticker window to 124px, then fill with object-fit:cover. Place the card circle centrally below the title, backed by the title's contrasting colour. Keep card corners square.

### Eye wayfinding motif

**Use:** A recurring browse-action signature.

**Observed:** A 42px orange disc contains a white 26px by 17px almond-shaped eye with a small violet circular pupil.

**Transfer:** Retain an equally small, animated editorial eye beside discovery actions; it is an interface ornament rather than a large illustration.

**Build:** Draw a white almond using two quadratic SVG curves inside a 26px by 17px viewBox. Center it within a 42px orange circle; clip an 8px violet pupil to the almond and position the disc before the text with a 10px gap.

### Illustrated origin sequence

**Only for:** company storytelling

**Use:** A personal story or history chapter.

**Observed:** A wide cinematic illustration in muted slate, cream and pink shows a human encounter. It sits centered on a slate field, with a large white serif question above, explanatory copy below and vertical arrows and progress dots at the right.

**Transfer:** Commission a small narrative sequence about the product's human motivation. A minimum version is one wide illustrated scene with a clear human focal point, rather than generic office stock photography.

### Icons

**Observed:** Tiny functional motifs rather than an icon library: two-line menu, arrow links, eye emblem and FAQ plus. The eye is a filled white SVG, 26px by 17px; FAQ plus lines are 2px thick inside 42px coloured discs.

**Transfer:** Keep navigation and action marks simple and geometric. Use expressive imagery for subject matter rather than adding feature-icon grids.

## Section recipes

How recurring sections are built.

### First screen: Declaration opening

**Observed:** The first 900px are one flat Opening field. A transparent Fixed navigation overlays it, with identity at the upper left and Menu disc at upper right. The centered 864px copy group occupies about three fifths of the width and the middle quarter of the screen: an 80px white serif headline wraps to two lines, followed 24px later by a single cream 42px serif support line. A full-stage media layer lies behind the copy, which remains the clear foreground. There is no hero button or visible gallery in the first screen; the paper introduction begins below it.

**Transfer:** Lead with a short, broad promise and a companion sentence of similar verbal confidence. If there is no suitable moving artwork, keep the violet declaration intact and let original imagery enter in the proof chapters. Specialist-service openings retain the centered declaration on a distinct colour field; directory openings use a compact text-only paper hero instead.

**Avoid:** Do not replace this composition with a left-aligned SaaS headline, small sans-serif support and two pill CTAs beside a browser mockup.

**Text style:** `display` — Millik 700 · 80px/0.95 · tracking 0.02em

### Paper statement and proof gallery

**Observed:** A centered heading-small statement on Paper canvas follows 80px of breathing room. Four-column Gallery tiles sit beneath it with 40px gutters; the Eye browse link centers beneath the selection.

**Transfer:** State the breadth of the offer briefly, then show it through varied examples rather than feature bullets.

**Text style:** `heading-small` — Millik 700 · 38px/0.98 · tracking -0.042em

### Colour-stage chapter

**Observed:** Colour stage uses two equal halves in a 720px-high band. Edge-anchored feature artwork occupies one half; the other has a vertically centered heading, an 18px gap to body copy and a Feature text link 36px below. Text can switch sides between chapters.

**Transfer:** Use this recipe for a tangible benefit, use case, release or project. Select a background from the artwork's palette and keep the composition open rather than panelized.

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

### Paired illustrated teasers

**Observed:** Two 720px-wide tiles share a 720px-high row without a gutter. Each has its own saturated background, white heading near the upper left, a short paragraph below, an action near the lower left and artwork rising from the lower right.

**Transfer:** Pair two related routes or benefits. Keep the artwork below the explanatory text and make each half feel like its own poster.

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

### Blue signup stage

**Observed:** A full-width 720px blue stage sets heading and supporting paragraph above a 480px form on the left. Signup input controls stack below the copy, while a humorous illustrated person and oversized sleep letters occupy the lower right.

**Transfer:** Use a human, lightly comic illustration related to the new product's context. Keep the form usable and concise rather than turning the scene into decoration behind fields.

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

### Editorial rail and kinetic close

**Observed:** Editorial rail presents four Editorial cards with 40px gaps. News ticker follows on white, with coloured oversized type and circular pictures; a 120px violet band finishes with a centered white Eye browse link.

**Transfer:** Use the card-and-circle contrast and kinetic update line as recognizable punctuation. The final action should route back to useful work or a collection rather than open a conventional multi-column footer.

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

### Typographic proof wall

**Only for:** company and credibility pages

**Observed:** A small centered sans-serif section label introduces a long, centered stream of comma-separated names. The names use the 70px heading recipe, wrapping across the paper content width; violet text alternates selectively with salmon-pink links. Lines are separated by 16px item margins rather than logo boxes.

**Transfer:** Use genuine customer, contributor or partner names as an expressive text composition. Scale its length to the available proof instead of inventing filler.

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

### Questions and further exploration

**Only for:** company and FAQ pages

**Observed:** A 70px violet section title sits above FAQ rows on paper. Later illustrated colour teasers transition back to a centered 38px invitation, one row of Gallery tiles and an Eye browse link with 80px section padding.

**Transfer:** Resolve practical objections, then end by showing a small selection of useful examples rather than forcing the same footer onto every page.

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

### Specialist service modules

**Only for:** specialist service pages

**Observed:** A large centered serif service statement and regular grotesk paragraph introduce a flexible two-column media grid. Tall Service information cards alternate across it. The final visible block is a navy project card with mint title and action, followed by paper breathing room, not a universal footer.

**Transfer:** Use this more explanatory variant for a service with practical requirements. Pair information with substantive demonstrations, preserving media space without treating missing artwork as content.

**Text style:** `heading` — Millik 700 · 70px/0.98 · tracking -0.0229em

### Directory opening and cross-route ending

**Only for:** directory pages

**Observed:** A text-only paper opening has 130px top padding, an 88px centered violet title, a 24px gap to a 576px-wide bold grotesk introduction and 80px before the gallery. A long four-column gallery ends with an illustrated 720px green stage, lime heading and action, and white support copy.

**Transfer:** Use for a browsable collection. Finish with a related capability or route, represented by one large edge-anchored illustration.

**Text style:** `directory-display` — Millik 700 · 88px/0.98 · tracking -0.0182em

## Page flow

**Storyline:** Confident declaration → explanation through visible work → colourful capability stories → editorial or practical depth → renewed exploration.

### Image-led marketing landing page

1. **Promise** — Full-screen violet declaration with serif companion line.
2. **Product proof** — Short paper introduction and portrait gallery.
3. **Capability stories** — Alternating full-bleed illustrated stages and paired teaser posters.
4. **Relationship building** — Conversational signup stage and process or editorial features.
5. **Closing call** — Circular-image reading cards, oversized news ticker and violet browse band.

**Transfer:** Let the work substantiate the promise. Choose chapters appropriate to the new product while retaining the expressive stage and closing devices.

### Specialist capability explanation

1. **Promise** — Centered full-screen coloured declaration.
2. **Explanation** — Large serif statement on paper with a practical paragraph.
3. **Capability demonstration** — Media-led flexible grid alternating tall navy information cards.
4. **Closing proof** — Final project card with a contextual action; paper space completes the page.

**Transfer:** Use for a focused service, moving from what it does to what the customer needs to provide, with a real project as the close.

### Browse a broad collection

1. **Orientation** — Compact centered paper introduction.
2. **Selection** — Long four-column portrait gallery with serif names and occasional circular new badges.
3. **Cross-route invitation** — Green illustrated closing stage with lime text action.

**Transfer:** Keep collection browsing repetitive and visually consistent, reserving a contrasting poster for the related next step.

### Human story and credibility

1. **Identity** — Violet declaration layered over illustrated people.
2. **Human context** — Slate narrative carousel with cinematic illustration and explanatory text.
3. **Social proof** — Monumental comma-separated typographic customer wall.
4. **Objection handling** — Paper FAQ rows with salmon plus discs.
5. **Values and process** — Vivid film stage and paired illustrated commitments.
6. **Closing exploration** — Small portrait gallery and centered eye browse link on paper.

**Transfer:** Give a company page a human narrative and expressive proof, then return the reader to concrete examples.

## Writing

Warm, assured and slightly cheeky. Professional competence is expressed through concrete work and direct explanations, while titles and actions allow wordplay, sound effects and small conversational asides.

**Do not copy:** Do not reuse the agency name, identity artwork, artist or client names, project titles, proprietary illustrations, numerical claims, historical anecdotes or source claims as facts about another product. Source examples illustrate tone only.

- **Addressing the reader:** Use we for the people behind the offer and you or your for the reader. Contractions and direct questions make the relationship personal.
- **Rhythm:** Short declarative headlines often end with a full stop. Support is usually one compact paragraph; practical explanations can be longer. Follow a useful statement with a brief human aside, not an uninterrupted joke.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A confident plain-language position, phrased as a human relationship or a direct capability. | 4–8 words | “Home to the world’s greatest illustrators.”<br>“We do animation too.” |
| Companion line | A second serif sentence that complements rather than restates the promise. | 6–17 words | “Friend to the world’s greatest brands.” |
| Feature title | Concise introduction with a pun, a direct question or a simple content noun. | 1–5 words | “Blease to meet you!”<br>“So who is Frank?”<br>“Watch.” |
| Supporting copy | Explain what is offered in concrete language, with an occasional self-aware aside. | 1–3 short sentences | “Want to stay in touch? Not in a needy way.” |
| Feature action | Context-specific invitation, sometimes a sound or everyday phrase. | 1–5 words | “Two sugars.”<br>“Quiet Please.”<br>“Let’s get things moving.” |
| Practical question | Voice a real customer's concern in everyday speech. | 5–15 words | “We've never commissioned illustration before. Can you help us?” |

**Words and phrasing to use:** we; you; bring to life; explore; bespoke; from … to …; a little; let’s

**Avoid:** unlock synergies; revolutionary ecosystem; enterprise-grade transformation; frictionless solutions; excessive superlative chains

**Rules:**

- Name a concrete output or experience in support copy rather than adding abstract benefit stacks.
- Let chapter actions respond to their immediate subject; keep functional form labels straightforward.
- Use humour as a small aside after useful information.
- Keep serif headlines conversational and in sentence case rather than turning them into uppercase slogans.

## Do's and Don'ts

### Do

- Keep the opening at 80px/0.95 and its serif companion at 42px/0.95.
- Use 70px/0.98 headings to make each colour stage read as a poster.
- Preserve 40px gallery gutters and the 20px image-to-caption gap.
- Pair flat full-width backgrounds with edge-anchored objects occupying roughly half the stage.
- Keep browse controls expressive with the 42px eye disc.
- Use 32px tight serif titles and 220px circular windows inside square editorial cards.
- Reserve the 30px radius for 58px form controls.
- Use the 70px ticker and 120px closing band to make the ending feel designed.

### Don't

- Do not introduce shadows or elevated white feature cards into the flat colour chapters.
- Do not round portrait gallery images or rectangular editorial card corners.
- Do not replace all serif text actions with solid pill buttons.
- Do not shrink gallery captions into tiny uppercase sans-serif metadata; they are 22px serif names.
- Do not use mint as a default full-page background; it primarily marks the menu and specialist-card text.
- Do not turn the typographic proof wall into an equal-size monochrome logo grid.
- Do not impose one colour pairing on every chapter; related objects and text carry distinct stage palettes.
- Do not attach a dense multi-column footer to every page type; the endings have different narrative jobs.

## Motion and responsive

### Motion

**Observed:**

- Declared menu-disc transition: 0.26s cubic-bezier(0.23, 0.82, 0.6, 2).
- Declared gallery caption transition: 0.36s cubic-bezier(0.05, 0.64, 0.42, 1.56).
- Declared editorial title transition: 0.38s cubic-bezier(0.17, 0.84, 0.44, 1).
- The interface includes layered action labels, an eye blink mechanism and a horizontally scrolling news stream.

**Transfer:**

- Preserve the contrast between calm flat stage compositions and small playful interface movement.
- Keep the ticker on one horizontal line with recurring circles rather than wrapping it into a static paragraph.

**Unknown:**

- Exact ticker speed, playback triggers and hover/focus visual endpoints are unspecified.

### Responsive

**Observed:**

- Content side padding follows 6vw. Declared width breakpoints include 414px, 680px, 681px, 768px, 834px, 835px, 900px, 1024px, 1025px, 1280px, 1440px, 1660px, 1720px and 1780px.

**Transfer:**

- On narrower screens, reduce the gallery column count while preserving portrait proportions and centered serif captions.
- Stack the copy and artwork of colour stages without adding card borders; retain the edge-anchored composition and one dominant object.
- Keep the ticker horizontal and clipped, and fit the 480px form to the available content width.

**Unknown:**

- Exact narrow-screen type sizes, grid counts and section heights are unspecified; stacking guidance is an adaptation rule.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
