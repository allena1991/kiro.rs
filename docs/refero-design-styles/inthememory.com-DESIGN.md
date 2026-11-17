# Vusion — sunshine meets execution

## Overview

A warm, businesslike technology style that makes complex software feel tangible and approachable. Pale cream and white reading areas meet sunflower-yellow landmarks and deep green-black conversion sections, with medium-weight grotesk headings and light body text. Layered interface illustrations, practical workplace photography and translucent geometric accents give spacious product storytelling a physical presence.

### Essentials

- An outcome-led headline sits beside a tangible product assembly: 44px/1.32 grotesk at weight 500, a 507px text column and a 612px square image stage on pale cream.
- Sunflower yellow acts as architecture rather than scattered decoration: a 75px navigation band, a 24px-radius benefit panel and a full-width closing field punctuate predominantly white and cream content.
- Actions have two distinct levels of commitment: dark filled 48px pills for contact, versus 64px outlined pills for exploration, with 100px corner radii and normal tracking.
- Interfaces become physical objects: a central dashboard overlaps smaller tilted panels on a yellow rounded-square backing; a simpler product gets one credible interface with two enlarged functional details.
- Capability stories use open three-column groups before becoming substantial photographic cards: 16px gutters, 20px feature titles, 32px card titles and 24px card corners.
- The ending becomes a brand-scale object: compact footer links and a 32px helping statement sit above a dark wordmark stretched across a 1360px-wide yellow field. Use the new identity or a short typographic brand statement at this monumental scale.
- Soft translucent geometry connects the practical sections: pale yellow edge ribbons on white and frosted slanted plates on dark green-black keep the atmosphere luminous without turning the entire page into glass.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sunflower | `#fdcd38` | `--color-yellow` | background, surface, accent | Navigation, benefit highlight, product-art backing and closing field. |
| Warm cream | `#fdf6e3` | `--color-cream` | background, surface | Default product-opening field; capability-detail bands also use this warm ground. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Green-black ink | `#0d2126` | `--color-ink` | text, background, border, action | Default text, outlined controls, primary buttons and deep conversion bands. |
| Raised charcoal | `#27363a` | `--color-panel` | surface | Form panel above the deeper green-black band. |
| Cool mist | `#f3f5f5` | `--color-card` | surface | Photographic capability-card bodies. |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Main reading canvas, interface backing and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| announcement pages | Letter yellow | `#fecd38` | `--color-announcement-yellow` | background, accent | Lower announcement canvas and luminous perimeter accent. |
| announcement pages | Letter slate | `#677b82` | `--color-muted` | text | Long-form announcement paragraphs and signature role. |
| announcement pages | Letter ink | `#102126` | `--color-announcement-ink` | text, action | Body emphasis and action fill in the announcement format. |
| announcement pages | Letter edge | `#f0f0f0` | `--color-edge` | border | Visible black at 0.06 alpha over white, used for the announcement-card hairline. |

## Typography

- **TWKEverett** — All standard marketing headings, paragraphs, labels and controls. Open, contemporary grotesk with round bowls; medium headings contrast with distinctly light paragraphs. If unavailable, use **DM Sans**. Use 300, 400 and 500; retain normal tracking and the open line spacing. Font stack: "TWKEverett", "DM Sans", Arial, sans-serif.
- **graphik** (only for announcement pages) — Announcement text, title and action. Compact geometric grotesk, less light in paragraph use than the marketing face. If unavailable, use **Inter**. Font stack: "graphik", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | TWKEverett | 500 | 44px | 1.32 | normal | Hero title, major capability headings and dark contact-section title. |
| heading | TWKEverett | 500 | 32px | 1.32 | normal | Explanatory section titles and the helping statement in the closing field. |
| card-heading | TWKEverett | 500 | 32px | 42px | normal | Photographic capability-card titles. |
| feature-heading | TWKEverett | 500 | 20px | 1.4 | normal | Open-column capability titles. |
| lead | TWKEverett | 300 | 20px | 1.5 | normal | Hero support and dark contact introduction. |
| body | TWKEverett | 300 | 18px | 1.5 | normal | Reading paragraphs, benefit lists and card descriptions. |
| explore-action | TWKEverett | 400 | 16px | 1 | normal | Outlined exploration pills. |
| navigation | TWKEverett | 500 | 14px | 1 | normal | Main dropdown navigation. |
| action | TWKEverett | 400 | 14px | 1 | normal | Compact filled contact buttons. |
| media-caption | TWKEverett | 400 | 14px | 1.5 | normal | White explanatory text inside a translucent media caption. |
| eyebrow | TWKEverett | 300 | 12px | 1 | normal, uppercase | Product-family or audience label immediately above the main title. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| announcement pages | letter-display | graphik | 500 | 32px | 35px | normal | Two-line announcement title over golden artwork. |
| announcement pages | letter-body | graphik | 400 | 16px | 1.5 | normal | Short letter paragraphs. |
| announcement pages | letter-emphasis | graphik | 500 | 16px | 1.5 | normal | Letter emphasis and three reassurance headings. |
| announcement pages | letter-action | graphik | 500 | 14px | 20px | normal | Full-width announcement action. |

**Notes:**

- Weight 500 is the heading ceiling, not a cue to substitute a heavy bold. Body weight 300 keeps long explanations visually lighter than their headings.
- Tracking remains normal throughout; distinction comes from size, weight and surface contrast rather than condensed uppercase typography.
- Use the 44px recipe for major section leads and the 32px recipe for supporting chapters. Card headings use their own 42px line height.

## Layout

**Density:** Airy at the section level, with practical reading density inside cards and long explanations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-title gap. |
| 12px | Benefit-list and compact link-list rhythm. |
| 16px | Column gutters and title-to-description spacing within capability items. |
| 24px | Paragraph stacks, icon-to-copy grouping and compact interior spacing. |
| 40px | Card-body side and bottom padding; form-panel padding. |
| 60px | Inner desktop inset of the broad grid container. |
| 64px | Section-heading to grid spacing and photographic-card top padding. |
| 80px | Standard top and bottom section padding. |
| 160px | Opening top offset for the narrow announcement card. |

### Containers and grids

- **Content container**: max width 1360px · 12 columns · gap 16px · side padding 60px. Centered broad grid with 1240px usable width at a 1440px viewport, leaving content edges at 100px.
- **Three-column content**: max width 1240px · 3 columns · gap 16px. Equal 403px capability columns or cards; repeated card rows also have 16px gaps.
- **Split opening**: max width 1240px · 12 columns · gap 16px. Five grid columns for text, one column of separation and six for the square visual. The opening is 612px high.
- **Closing field**: max width 1360px · side padding 40px. Wider lower wordmark area; helping copy and link columns align to the inner content grid.
- **Announcement letter** (only for announcement pages): max width 644px · side padding 24px. Single centered card with a wider 978px reassurance row beneath it.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Panels and cards | 24px |
|  | Action pills | 100px |
|  | Search control | 50% |
|  | Media caption | 66px |
| announcement pages | Announcement card | 16px |
| announcement pages | Announcement action | 12px |

## Surfaces and depth

### Surfaces

#### Reading canvas · level 0

**Use:** Main reading sections.

**CSS:** `background: #ffffff; color: #0d2126`

**Observed:** Flat white, without raised-card shadows.

**Transfer:** Separate sections by rhythm and occasional field changes instead of adding rules everywhere.

#### Cream field · level 0

**Use:** Default product opening and detailed capability bands.

**CSS:** `background: #fdf6e3; color: #0d2126`

#### Yellow highlight · level 1

**Use:** Bright benefit panel.

**CSS:** `background: #fdcd38; border-radius: 24px; color: #0d2126`

**Observed:** A contained, broad image-and-text panel rather than a small accent badge.

#### Dark field · level 0

**Use:** Contact and demo conversion areas.

**CSS:** `background: #0d2126; color: #ffffff; padding: 80px 0px`

**Observed:** Deep green-black with the form one tonal step above it.

#### Form panel · level 1

**Use:** Contact-form backing.

**CSS:** `background: #27363a; border-radius: 24px; padding: 40px`

**Observed:** Occupies the right six columns and extends with the actual form length.

#### Media glass · level 2

**Use:** Caption directly over a large interface visual.

**CSS:** `background: rgba(13, 33, 38, 0.4); backdrop-filter: blur(6px); border-radius: 66px; padding: 16px 24px; color: #ffffff`

**Observed:** A wide low capsule inset from the lower image edges; the background image remains visible through it.

#### Letter shell · level 1

**Only for:** announcement pages

**Use:** Announcement article.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.06); border-radius: 16px; overflow: hidden`

**Observed:** A fine golden perimeter beam reinforces the flat white card; it is not a drop shadow.

**Transfer:** Use the perimeter effect only in this concentrated message format.

## Components

### Navigation menu item

**Use:** Top-level navigation inside the yellow header.

**CSS:** `display: flex; gap: 4px; padding: 12px 12px 12px 16px; border-radius: 100px; color: #0d2126`

**Text style:** `navigation` — TWKEverett 500 · 14px/1

**Observed:** Text followed by a small downward chevron. The opening header pairs a 40px dark utility strip with a 75px yellow main band; on scroll the yellow band remains with a compact identity mark.

**States:** Declared: hover background #FEE187; focus-visible background #FEE187.

### Primary button

**Use:** Contact conversion, particularly at the right edge of navigation.

**CSS:** `display: flex; background: #0d2126; color: #ffffff; border-radius: 100px; padding: 16px 24px; height: 48px; box-sizing: border-box`

**Text style:** `action` — TWKEverett 400 · 14px/1

**Observed:** A short text-only pill, with no mandatory arrow. It sits beside the round search action.

**States:** Declared: hover text-decoration none.

### Outline button

**Use:** Explore a capability from its card.

**CSS:** `display: inline-flex; background: transparent; color: #0d2126; border: 1px solid #0d2126; border-radius: 100px; padding: 23px 32px; height: 64px; box-sizing: border-box; transition: background-color 0.3s, color 0.3s`

**Text style:** `explore-action` — TWKEverett 400 · 16px/1

**Observed:** Aligned at the lower left of the card body, with 40px minimum separation from the text block. Repeated buttons align across a row.

**States:** Declared: hover background #0D2126 and color #FFF, text-decoration none; active background #0D2126 and color #FFF. Ancestor hover also applies the filled treatment.

### Capability card

**Use:** A navigable product capability or audience path.

**CSS:** `display: flex; flex-direction: column; background: #f3f5f5; border-radius: 24px; overflow: hidden`

**Text style:** `card-heading` — TWKEverett 500 · 32px/42px

**Observed:** A 403px-wide card starts with a 403×268px photograph with rounded corners and centered category emblem. The body uses 64px top padding, 40px sides and bottom, a title, a 16px gap to body text and an Outline button. Typical height is 588–615px.

**Transfer:** Use one actual work situation per card and normalize the content length, not the claims.

### Open capability item

**Use:** Explain differentiators without adding more card boxes.

**CSS:** `display: flex; flex-direction: column; gap: 24px`

**Text style:** `feature-heading` — TWKEverett 500 · 20px/1.4

**Observed:** Large simple line icon first, title next, then an 18px body paragraph separated from the title by 16px. Three items share a row; text has 40px right inset.

**Transfer:** Choose parallel, comparable capabilities and keep the group visually unboxed.

### Benefit panel

**Use:** A concentrated outcome statement paired with human context.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); column-gap: 12px; row-gap: 40px; background: #fdcd38; border-radius: 24px`

**Text style:** `heading` — TWKEverett 500 · 32px/1.32

**Observed:** A broad 1240×426px panel, with a photograph occupying the left half and a vertically centered heading plus three checkmarked statements on the right.

**Transfer:** Use three concrete outcomes, not a decorative quote.

### Contact panel

**Use:** Contact inquiry form within the Dark field.

**CSS:** `background: #27363a; border-radius: 24px; padding: 40px`

**Observed:** Right-hand panel is 612px wide. A single column of light-outlined inputs sits below compact uppercase labels; a taller message field and consent checkboxes follow. Left side carries the white headline and a short reassurance paragraph.

**Transfer:** Use a real accessible form and let its contents determine the band's height; do not manufacture empty space to match a fixed length.

### Media caption

**Use:** Explain the large interface image without placing a paragraph below it.

**CSS:** `display: flex; align-items: center; gap: 24px; background: rgba(13, 33, 38, 0.4); backdrop-filter: blur(6px); border-radius: 66px; padding: 16px 24px; color: #ffffff`

**Text style:** `media-caption` — TWKEverett 400 · 14px/1.5

**Observed:** Wide capsule overlaid near the image bottom, inset 16px horizontally. It can hold several compact sentences rather than just a title.

### Announcement card

**Only for:** announcement pages

**Use:** A personal transition or launch letter.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.06); border-radius: 16px; overflow: hidden; max-width: 644px`

**Text style:** `letter-body` — graphik 400 · 16px/1.5

**Observed:** Golden 642×270px artwork header with small metadata and a two-line title; below comes a small message icon, short paragraphs, a bold pivot sentence and an avatar signature. The action runs across the card bottom.

**Transfer:** Reserve this intimate format for a single announcement, not a full product landing page.

### Announcement action

**Only for:** announcement pages

**Use:** The single onward action below a letter.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #102126; color: #ffffff; border-radius: 12px; padding: 8px 12px; height: 36px; box-sizing: border-box; margin: 0px 24px 24px; transition: transform 0.16s, background-color 0.16s`

**Text style:** `letter-action` — graphik 500 · 14px/20px

**Observed:** Full inner-card width rather than an intrinsic-width pill.

**States:** Declared: hover background #24373d and transform translateY(-1px); focus-visible outline #3368db solid 3px with 3px offset.

## Imagery and graphics

### Layered interface assembly

**Use:** Primary visual in the default opening.

**Observed:** A bright white dashboard floats in front of a softly layered yellow rounded square. Smaller report cards fan out at slight angles on both sides, with a physical device near the lower edge. Pastel chart colors stay inside the interface; soft contact shadows give the assembly depth. The whole scene occupies the right half, balancing a substantial text column.

**Transfer:** Use the new product's central workspace and two or three enlarged functional details. Without polished art, build one clean interface panel and two overlapping detail cards; preserve the cream surround and yellow backing rather than substituting unrelated stock art.

**Build:** Use a 612px square stage. Center a yellow rounded square at about three quarters of its width, with two larger translucent yellow outlines behind it. Overlay a white central interface; place smaller white panels at the left and right edges, rotated in opposing directions by a few degrees. Use soft rgba(13,33,38,0.12) shadows only within this illustration, not on the marketing cards.

### Large interface plate

**Use:** Product demonstration after the opening explanation.

**Observed:** A 1240×698px landscape interface image with a warm pale backing and rounded corners dominates the section. Its internal dashboard is readable as a whole, not reconstructed as dozens of marketing tiles. A Media caption overlays the lower portion.

**Transfer:** Show a coherent workflow at landscape scale. Keep demonstration colors within the visual instead of turning them into new page accents.

### Workplace photography

**Use:** Benefit panel, capability cards and focused solution openings.

**Observed:** Natural-color images show people using tablets or handheld tools in real stocked workplaces. Cropping is purposeful and close, retaining shelves, hands and equipment. The benefit image is a broad half-panel; card photography is 3:2 with a subtly darkened lower edge and a category emblem centered on it. Focused solution openings use a full 612px square photograph against a dark field.

**Transfer:** Photograph the new product in its actual working environment. Favor hands doing a task, practical lighting and tangible equipment over posed portraits or blue-tinted abstract offices.

### Luminous edge geometry

**Use:** Atmospheric connective device around explanatory and conversion sections.

**Observed:** Pale yellow translucent ribbons and slanted stacked bands enter from the outer edges of white sections. In the dark contact band, overlapping frosted parallelogram-like plates sit behind and between the text and form. Shapes remain subordinate to content.

**Transfer:** Retain one luminous geometric motif, positioned behind content and clipped at section edges. Match the soft glow; exact gradient stops are not essential.

**Build:** Create a 350px SVG with three stacked slanted rounded quadrilaterals. Fill each with a transparent-to-rgba(253,205,56,0.25) gradient and a faint bright edge; space the layers so white gaps remain visible. Pair with two crossing curved ribbon paths on the opposite edge. For dark sections replace yellow with rgba(255,255,255,0.2), fade centers to transparent, and offset overlapping plates diagonally. Keep decoration behind foreground content and clip overflow.

### Monumental identity

**Use:** Signature graphic in the yellow closing field.

**Observed:** A dark identity wordmark spans 1360px in width and about 270px in height, anchored below much smaller closing copy and link columns; the lower portion is intentionally clipped by the page end.

**Transfer:** Use a custom vector identity or a short heavy typographic brand statement. It must feel like an architectural base rather than a routine footer logo.

**Build:** Place an SVG wordmark in a 1360px-wide wrapper with 40px outer side margins. Scale proportionally to nearly fill the available width; use the ink color on yellow, no shadow or outline. Clip the bottom edge within the footer to retain the oversized scale.

### Golden letter artwork

**Only for:** announcement pages

**Use:** Artwork header of the announcement card.

**Observed:** Luminous diagonal yellow and gold streaks with pale lemon highlights flow behind white metadata and a two-line message. The first title line is softened to 0.64 white alpha; the second is white.

**Transfer:** Make an abstract golden motion field rather than a photograph, leaving contrast for the title and metadata.

**Build:** Layer broad diagonal linear gradients in yellow, rgba(182,137,0,0.55) and rgba(255,255,255,0.45), then add narrower blurred streaks rising toward the right. Clip inside 15px top and 24px bottom corners. Add a fine masked conic-gradient perimeter to the letter shell, with a blurred duplicate at 6px and opacity 0.75 for a restrained edge glow.

### Icons

**Observed:** Navigation uses small downward chevrons and a 24px search glyph in a 48px white circle. Feature icons are larger simple line drawings, yellow on white for the default product treatment and dark on cream for focused detail pages. Lists use fine checkmarks. Social icons are compact dark glyphs around 24px.

**Transfer:** Use consistent outline geometry for capability concepts and small functional arrows; keep multicolored category emblems confined to photographic card artwork.

## Section recipes

How recurring sections are built.

### First screen: Cream product assembly opening

**Observed:** A dark utility strip and yellow navigation frame the top. Below, the Cream field forms a 612px-high split hero: a vertically centered five-column text group at left and a 612px square Layered interface assembly at right, separated by a grid column. The 12px uppercase eyebrow sits 8px above the 44px/1.32 medium headline, which wraps into several deliberate lines across a 507px column. A 20px light support paragraph follows with about 16px separation. Layers run cream field, translucent yellow backing, white interface assembly, then foreground detail panels. There is no extra hero button; the visible primary action is Contact us in navigation. Within the first 900px, the complete headline, support, navigation action and product object are visible, together with the start of the next white section and its centered heading; the main demonstration image lies below.

**Transfer:** Start a new marketing page with this cream split composition and an outcome-led promise. Without existing media, construct the simpler interface assembly described in imagery. A focused solution page can open with the same proportions on the Dark field, white type and a square workplace photograph; an announcement instead uses the narrow Announcement card under a small centered identity.

**Avoid:** Do not center a giant slogan above a full-width mockup, add a competing CTA cluster to the hero, or reduce the main object to a small thumbnail.

**Text style:** `display` — TWKEverett 500 · 44px/1.32

### Heading and explanation

**Observed:** White reading sections use 80px top and bottom padding. A 32px heading leads a short explanation with 24px paragraph spacing; richer capability chapters use a 44px heading. Audience labels can precede the major heading with the Eyebrow recipe.

**Transfer:** Choose heading scale by narrative importance, keeping explanatory text in the 18px light Body recipe.

### Capability index and demonstration

**Observed:** A centered supporting heading precedes a compact underlined index of capabilities separated by slash marks. The next white section presents the Large interface plate with 80px vertical spacing and a Media caption.

**Transfer:** Use anchor links for a broad platform with several destinations; simplify the index for a focused product but keep the demonstration legible at full content width.

### Outcome highlight

**Observed:** The Benefit panel couples Workplace photography on the left with a heading and checkmarked outcome statements on the right. It sits within white space, not as a full-bleed yellow page background.

**Transfer:** Condense the value proposition into three parallel, specific benefits and show the human activity they support.

### Open differentiators

**Observed:** A major heading sits 64px above three Open capability items. Default treatment is white with yellow line icons; focused-detail treatment uses the Cream field with dark icons and can expand into longer explanatory lists.

**Transfer:** Use this pattern for mechanism or differentiation, leaving photographic navigation to the Capability cards.

### Photographic capability grid

**Observed:** A small audience eyebrow and 44px heading precede a three-column grid with 16px gaps. Capability cards combine image, category emblem, 32px title, body and Outline button.

**Transfer:** Adjust item count to the product; retain coherent image ratios and row-aligned actions.

### Dark contact chapter

**Observed:** The Dark field carries a 44px white helping headline and 20px support on the left, Contact panel on the right. Luminous edge geometry sits behind the foreground. The form is a single column and the band accommodates its length.

**Transfer:** Turn intent into a real next step, with brief reassurance about what happens after submission. A focused detail page can use a short demo-request title instead.

### Yellow identity ending

**Observed:** A full-width yellow field starts with 80px top spacing. A 32px helping statement and social links occupy the left half, while three narrow link columns occupy the right. Small legal content follows; Monumental identity fills the lower field with a deliberately clipped base.

**Transfer:** Keep the closing field and monumental identity as a signature device, while tailoring link groups and the helping statement to the new product.

### Single-letter announcement

**Only for:** announcement pages

**Observed:** A centered 644px Announcement card begins after 160px of top space. Its golden header leads into a personal message, signature and Announcement action. The canvas changes sharply from white to yellow behind the lower card. Three unboxed reassurance statements sit in a wider 978px row beneath, followed by Monumental identity; there is no conventional multi-column footer.

**Transfer:** Use this special format for one consequential announcement and a single onward destination, preserving the human signature and concise reassurance.

## Page flow

**Storyline:** Outcome promise → tangible demonstration → mechanism and benefits → capability paths → personal conversion → monumental identity close.

### Broad platform marketing landing page

1. **Promise** — Cream split opening with outcome headline and layered interface assembly.
2. **Orientation** — Centered capability index with underlined anchor links.
3. **Product demonstration** — Full-content-width interface plate and translucent caption.
4. **Explanation and benefit** — Short details chapter with luminous edge art, then a yellow photo-and-checklist panel.
5. **Differentiation** — Three open icon-led columns.
6. **Capability paths** — Photographic navigation cards with outlined exploration actions.
7. **Conversion** — Dark two-column helping statement and contact form.
8. **Identity close** — Yellow footer with compact links and monumental wordmark.

**Transfer:** Use the overall narrative as a flexible platform story; expand the demonstration and capability paths according to actual product breadth.

### Focused solution detail and demo acquisition

1. **Promise** — Dark split hero with short solution title, support and square workplace photograph.
2. **Mechanism** — Full-width explanatory paragraphs followed by a supporting heading and summary.
3. **Capability chapters** — Cream three-column icon-led explanation with lists.
4. **Synthesis** — A concise concluding paragraph on white.
5. **Conversion** — Dark demo-request chapter with right-hand form.
6. **Identity close** — Yellow helping statement, link columns and monumental identity.

**Transfer:** Use this denser explanatory variant when the audience already knows the category and needs operational detail.

### A personal announcement with an onward destination

1. **Announcement** — Golden artwork header inside a narrow white message card.
2. **Reassurance** — Short letter, emphasized pivot, circular portrait signature and full-width action.
3. **Continuity proof** — Three brief unboxed reassurance statements over yellow.
4. **Identity close** — Oversized dark identity clipped at the lower edge.

**Transfer:** Use one clear change, one personal voice and one destination rather than a long feature narrative.

## Writing

Practical, optimistic and commercially focused. The language explains how complex systems improve everyday decisions, then becomes warmer and more personal at conversion or announcement moments.

**Do not copy:** Do not reuse Vusion, Memory, VusionLive, proprietary product names, logos, people, dates, interface figures, testimonials or business claims. All examples illustrate voice only; replace them with verified content for the new product.

- **Addressing the reader:** Headlines usually describe an action or outcome directly. Supporting text names the product and its users; helping sections use we and your, and announcements use a collective first person.
- **Rhythm:** Headlines range from compact category names to multi-line outcome statements. Support is generally one complete explanatory sentence; detail pages allow longer paragraphs. Lists and cards use short parallel verbs rather than slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Turn an input into a practical outcome; use active verbs and name both sides of the transformation. | 8–13 words for a platform; 2–4 for a focused solution | “Turn Shelf and Store Data Into Real-Time Execution and Decisions”<br>“Store Operations” |
| Capability title | A short adjective-plus-noun phrase that states a concrete mechanism. | 3–5 words | “Accurate Shelf Signals”<br>“Actionable Store Tasks” |
| Benefit line | Lead with an imperative and connect the mechanism to everyday execution. | 7–14 words | “Focus store teams on the highest-impact actions.” |
| Primary action | Plain, low-friction invitation with no inflated urgency. | 2–4 words | “Contact us”<br>“Discover More”<br>“Request a Demo” |
| Helping support | Explain what happens next in straightforward human language. | 1–2 sentences | “Submit the contact form and we’ll make sure it gets to the right person. They’ll be in touch as soon as possible.” |
| Announcement reassurance | Repeat a short stabilizing phrase, then give a personal supporting line. | 2–3 word title with one sentence | “Same team”<br>“The people you know, by your side.” |

**Words and phrasing to use:** turn … into …; real-time; actions; aligned; improve; effective; connected; your team; we are here to help

**Avoid:** magic; mind-blowing; crush it; revolutionary without explanation; fake scarcity; unverified percentage gains

**Rules:**

- Name the practical outcome before describing the technology stack.
- Make card and benefit copy parallel in grammatical form.
- Technical terms belong where they explain a mechanism, not as decorative jargon.
- Keep contact copy explicit about the next human step.
- Use personal continuity language only for genuine organizational or product transitions.

## Do's and Don'ts

### Do

- Keep main headings at 44px and weight 500, with a 1.32 line height.
- Pair 18px/1.5 light body copy with the medium headings.
- Use 80px vertical section padding and 16px three-column gutters as the main desktop rhythm.
- Give capability-card bodies 40px side padding and 64px top padding.
- Use 24px corners for cards and panels, but 100px corners for exploration and contact pills.
- Keep sunflower yellow concentrated in navigation, a contained highlight and the monumental ending.
- Stage software art on a cream field with a yellow backing and white interface layers.
- Keep the conversion form one tonal step lighter than its #0d2126 background.

### Don't

- Do not replace medium grotesk headings with 700-weight compressed display type.
- Do not apply negative tracking to the whole type system; the default is normal.
- Do not turn every reading section yellow; white and cream carry the long explanations.
- Do not give marketing cards drop shadows; depth belongs inside the interface illustration.
- Do not make every action a 36px rounded rectangle; that compact format belongs only to announcements.
- Do not spread the dashboard's pastel chart colors across navigation, body text and page backgrounds.
- Do not use multicolor filled icons for the open capability columns; their default is simple yellow line work.
- Do not reduce the closing identity to a small logo beside legal text; it spans nearly the full width.

## Motion and responsive

### Motion

**Observed:**

- Outlined exploration actions declare background-color 0.3s and color 0.3s transitions; cards declare background-color 0.3s.
- Announcement elements declare enter animation at 0.8s with cubic-bezier(0.25, 0.46, 0.45, 0.94); the announcement action transitions transform and background-color over 0.16s.
- The announcement perimeter has a named orbit animation; its timing is not specified here.
- The yellow navigation remains visible during scrolling and uses a compact identity mark.

**Transfer:**

- Preserve the outlined-to-filled exploration transition and the announcement action's restrained upward 1px hover movement.
- Keep decorative edge motion subordinate to the copy; its settled geometry must work without animation.

**Unknown:**

- Scroll-trigger timing, perimeter orbit duration and full motion choreography are unspecified.

### Responsive

**Observed:**

- Marketing CSS includes breakpoints at 768px, 1024px and 1280px among several component-specific thresholds.
- The announcement format declares 420px and 720px breakpoints.

**Transfer:**

- On narrow screens, stack the cream opening text before the interface assembly, keeping the yellow backing and overlapping detail panels together as one scaled scene.
- Collapse photographic cards and the contact split to a single reading column; retain the distinction between white reading areas, yellow landmarks and the dark conversion field.
- Scale the monumental identity to the available width rather than wrapping it like body copy.

**Unknown:**

- Exact narrow-screen font sizes, navigation behavior and card-column thresholds are not established; these stacking rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
