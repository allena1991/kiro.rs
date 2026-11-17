# Redis — midnight data machinery

## Overview

A dark technical style with a playful, almost toy-like sense of machinery. Deep blue-green grounds, white geometric grotesk text and extremely condensed display capitals are punctuated by signal red and acid yellow-green. Isometric platform sculptures, fine-line diagrams and small command panels make abstract software feel tangible; the layout is spacious around the story and compact inside its controls. It suits developer tools, infrastructure and complex products that need both technical credibility and an approachable entry point.

### Essentials

- Headlines switch registers rather than merely grow: the opening uses condensed uppercase primaryFont at 100px/0.85 with -0.01em tracking; ordinary chapters use Space Grotesk at 32px/1.2, weight 500.
- The first promise sits over a working miniature: center an approximately 810px-wide headline above a 430px command panel, separated by 48px, with paired 47px actions below and a nearly invisible geometric grid behind.
- Conversion controls look like illuminated equipment, not candy pills: 5px corners, a 1px red edge over #351d22, white 14px/21px labels; the partner action uses #163341 with a #2d4754 edge.
- Darkness remains the dominant material: #091a23 canvas and #0d212c panels cover almost the whole default page; #ff4438 belongs to actions and machine art, while #dcff1e marks isolated words, tiny rings and proof signals rather than broad backgrounds.
- Abstract capability becomes a physical system: include an isometric layered platform or connected geometric machine, staged in an open dark field or half of a bordered panel. A simple SVG stack with one red slab and dark outlined modules is the minimum equivalent.
- Small technical markings carry the playful engineering voice: Space Mono at 12px/18px for commands, widely tracked uppercase labels, 10px acid ring markers and red arrow links; pair a practical promise with a concrete demonstration.
- A friendly sculptural sign-off interrupts the formal close: after a contained conversion panel, give a small red-and-white character or product-related object its own centered dark stage before the compact multi-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Red action well | `#351d22` | `--color-red-well` | surface, action | Dark warm fill inside the primary action; keep the red edge brighter than the fill. |
| Signal red | `#ff4438` | `--color-red` | accent, border, link, action | Primary action outlines, arrow links, logos and saturated parts of technical sculptures. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid signal | `#dcff1e` | `--color-lime` | text, accent, border | Emphasized words, command prompts, tiny rings and positive result marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue-green hairline | `#163341` | `--color-edge` | border, surface, background | Panel edges, announcement band and secondary action fill. |
| Control edge | `#2d4754` | `--color-edge-strong` | border, surface | Secondary action outline, selected controls and stronger separators. |
| Raised midnight | `#0d212c` | `--color-panel` | surface | Subtly lifted command panels, cards and closing calls. |
| Midnight blue-green | `#091a23` | `--color-canvas` | background, text | Default page canvas; also the ink on light technical sections. |
| Footer slate | `#8a99a0` | `--color-quiet` | text, border | Low-priority footer links, subdued proof and resource-card outlines. |
| Cool muted text | `#b9c2c6` | `--color-muted` | text | Technical labels, command text and secondary explanations. |
| Body silver | `#d9d9d9` | `--color-body` | text, border | Main supporting paragraphs on dark surfaces; accordion rules on white. |
| Signal white | `#ffffff` | `--color-white` | text, background | Headlines and action labels; full-width white sections in the light technical variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Offer purple | `#8f2ec4` | `--color-offer` | surface | Compact promotional badge on the featured plan. |
| pricing pages | Offer lilac edge | `#b76be2` | `--color-offer-edge` | border | Fine edge of the purple offer badge. |
| light technical solution pages | Technical frost | `#f8f8f8` | `--color-light-band` | background | Feature-benefit band between white technical explanations. |

## Typography

- **Space Grotesk** — Chapter headings, paragraphs, navigation and action labels. Geometric grotesk with open counters, distinctive squared curves and a technical but friendly rhythm. Font stack: "Space Grotesk", Arial, sans-serif.
- **primaryFont** — Condensed campaign headlines and monumental organizational statistics. Extremely narrow, tall, irregular-looking display sans; letters form a dense white silhouette. If unavailable, use **Anton**. Use 400; compress width further to match the narrow word silhouette without reducing height. Font stack: "primaryFont", "Anton", Impact, sans-serif.
- **Space Mono** — Commands and small uppercase technical markings. Clearly monospaced, mechanical and lightly spaced rather than decorative. Font stack: "Space Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | primaryFont | 400 | 100px | 0.85 | -0.01em, uppercase | Default marketing opening: a single centered condensed statement. |
| heading | Space Grotesk | 500 | 32px | 1.2 | normal | Main chapter headings, panel promises and closing calls. |
| card-heading | Space Grotesk | 500 | 20px | 1.45 | normal | Titles inside capability and deployment cards. |
| footer-heading | Space Grotesk | 500 | 18px | 1.5 | normal | Footer category headings and compact accordion titles. |
| body | Space Grotesk | 400 | 16px | 1.6 | normal | Supporting paragraphs and substantive explanations. |
| action | Space Grotesk | 400 | 14px | 1.5 | normal | Visible button, navigation and compact card labels. |
| command | Space Mono | 400 | 12px | 1.5 | normal | Readable command examples and prompt questions. |
| footer-link | Space Grotesk | 400 | 12px | 1.4 | normal | Dense sitemap links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| organizational scale proof | monumental-stat | primaryFont | 500 | 180px | 0.9 | -0.01em | Red numeral sculptures, with smaller white explanatory captions underneath. |
| organizational pages | company-display | primaryFont | 500 | 100px | 0.85 | -0.01em, uppercase | Short identity statement framed by portraits. |
| solution pages | solution-display | Space Grotesk | 500 | 64px | 1.05 | -1px | Sentence-case solution promise, centered or in a split opening. |
| pricing pages | pricing-display | Space Grotesk | 500 | 64px | 1.05 | normal | Centered commercial headline above plans. |
| light technical solution pages | resource-heading | Space Grotesk | 500 | 50px | 1.1 | -1px | Centered lead for the dark resource band. |
| light technical solution and organizational pages | heading-lg | Space Grotesk | 500 | 40px | 1.05 | normal | Larger editorial and feature-band heading. |
| resource collections and solution problem grids | resource-title | Space Grotesk | 400 | 26px | 31px | normal | Multi-line resource titles in square outlined cards. |
| light technical solution pages | technical-heading | Space Grotesk | 500 | 24px | 1.2 | normal | Diagram chapter headings on light ground. |

**Notes:**

- Keep ordinary headings at medium weight; the display face supplies visual force through compression, not a generic heavy grotesk.
- The display and large solution headings tighten tracking, but the 32px chapter style stays at normal tracking. Do not apply one negative tracking rule to the entire hierarchy.
- Acid words use the same size and weight as the surrounding chapter title; the change is color, not an oversized highlighted badge.
- Visible action text is regular even when its outer control sets a medium inherited weight.

## Layout

**Density:** Airy between narrative chapters, compact within navigation and technical panels; 72px section padding surrounds much tighter 8–36px internal relationships.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon groups and footer link stacking. |
| 12px | Command-panel item spacing. |
| 16px | Paired hero actions and compact control groups. |
| 20px | Prompt-panel padding and headline-to-support spacing in closing panels. |
| 24px | Section support spacing and tab gaps. |
| 32px | Card padding, three-column gaps and title-to-panel separation. |
| 36px | Text-to-action separation in closing calls. |
| 48px | Opening stack gaps and closing-panel vertical padding. |
| 72px | Main chapter vertical padding. |
| 80px | Container horizontal padding and deep section-to-grid spacing. |
| 100px | Wide gap between a technical diagram and its text. |
| 110px | Default hero top padding beneath navigation. |
| 118px | Default hero bottom breathing room. |

### Containers and grids

- **desktop-shell**: max width 1280px · side padding 80px. Centered border-box shell: at 1440px, its outer edges sit at 80px and its usable 1120px content starts at 160px.
- **centered-copy**: max width 900px. Centered solution and commercial opening content; shorter support lines may use 760px.
- **capability-grid**: 3 columns · gap 32px. Three equal 352px cards across the usable desktop width.
- **footer-sitemap**: 4 columns · gap 32px. Four compact columns beside a wider brand, social and legal rail.
- **technical-split** (only for technical explanation chapters): 2 columns · gap 100px. Two 510px fields for text and diagrams, alternating sides.
- **outcome-grid** (only for long-form solution pages): 4 columns · gap 60px. Four 235px unboxed benefit columns; repeat as a second row when needed.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 5px |
|  | panels | 10px |
|  | tabs | 4px |
|  | utility-controls | 50% |
| organizational pages | portrait-tiles | 10px |

## Surfaces and depth

### Surfaces

#### Midnight canvas · level 0

**Use:** Continuous page ground.

**CSS:** `background: #091a23; color: #ffffff`

**Observed:** Most sections merge into one dark field; edges and slight fill shifts define structure instead of drop shadows.

**Transfer:** Preserve uninterrupted darkness across normal marketing chapters.

#### Instrument panel · level 1

**Use:** Capability cards, demonstrations and contained calls.

**CSS:** `background: #0d212c; border: 1px solid #163341; border-radius: 10px; box-shadow: none`

**Observed:** A low-contrast lift rather than a floating white card; thin dividers may partition its bottom proof rail.

**Transfer:** Use for content that is grouped or actionable, not every paragraph.

#### Technical paper · level 0

**Only for:** light technical solution pages

**Use:** Long-form educational diagrams, comparisons and the final conversion band.

**CSS:** `background: #ffffff; color: #091a23`

**Observed:** A sustained light body follows a dark opening, then returns to dark for resources and the footer.

**Transfer:** Choose this as a page-level technical variant, not an alternating decoration on the default dark page.

#### Frost feature band · level 0

**Only for:** light technical solution pages

**Use:** Benefit summaries between white technical chapters.

**CSS:** `background: #f8f8f8; color: #091a23`

**Observed:** A large heading occupies the left third while line icons and benefit text form a two-column field on the right.

**Transfer:** Separate architecture explanation from the practical value summary.

#### Deepening hero · level 0

**Only for:** split solution openings

**Use:** Backing for a text-and-isometric-art hero.

**CSS:** `background: linear-gradient(#163341 0.05%, #091a23 100%)`

**Observed:** The upper blue-green glow fades vertically into the normal page without an obvious seam.

**Transfer:** Keep this atmospheric shift subtle; it is not a multicolor gradient.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #351d22; color: #ffffff; border: 1px solid #ff4438; border-radius: 5px; padding: 10px 24px; height: 43px; box-sizing: border-box`

**Text style:** `action` — Space Grotesk 400 · 14px/1.5

**Observed:** Rectangular and restrained. The opening pair has a roomier 47px height and 12px 40px padding; plan-card versions stretch across the available width.

**States:** Declared: hover background-color #8a221c, border-color #eb352a, color #fff; focus-visible outline 2px solid #ff4438, outline-offset 2px; active background-color and border-color #ff4438.

**Transfer:** Use one primary action per decision point; reserve its brighter active fill for interaction.

### Secondary button

**Use:** Human-assisted alternative beside the main action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #163341; color: #ffffff; border: 1px solid #2d4754; border-radius: 5px; padding: 12px 40px; height: 47px; box-sizing: border-box`

**Text style:** `action` — Space Grotesk 400 · 14px/1.5

**Observed:** Matches the hero primary in silhouette. Outside the opening it uses 10px 24px padding and 43px height.

**States:** Declared: hover background-color #2d4754, border-color #5c707a, color #fff; focus-visible outline 2px solid #ff4438, outline-offset 2px; active matches hover.

### Arrow link

**Use:** Lightweight onward reading inside panels.

**CSS:** `display: inline-flex; align-items: center; color: #ff4438; background: transparent; text-decoration: none`

**Text style:** `action` — Space Grotesk 400 · 14px/1.5

**Observed:** A small right arrow follows the label; it is not wrapped in a pill. Links inside cards align near their lower edge.

**States:** Declared: hover color #fd736a and background-color transparent; focus-visible outline 2px solid #ff4438, outline-offset 2px; active color #ff4438.

### Sticky navigation

**Use:** Persistent primary site navigation.

**CSS:** `position: sticky; z-index: 20; background: #091a23; height: 70px`

**Text style:** `action` — Space Grotesk 400 · 14px/1.5

**Observed:** A compact red brand mark anchors the left, followed by a small featured-product chip and category links with red chevrons. Circular search and account controls precede a meeting link and Primary button. Above it sits a 38px announcement band with a tiny acid marker and report link.

**Transfer:** Keep the main categories short; one highlighted product chip is enough.

### Prompt panel

**Use:** Make the opening promise directly usable.

**CSS:** `display: flex; flex-direction: column; gap: 12px; max-width: 430px; padding: 20px; background: #0d212c; border: 1px solid #163341; border-radius: 10px`

**Text style:** `command` — Space Mono 400 · 12px/1.5

**Observed:** A small acid command marker and muted uppercase label precede a two-line question. Small square destination icons line up below at the left, with a Copy control at the right.

**Transfer:** Use a real command, short task or shareable question appropriate to the product.

### Capability card

**Use:** Parallel product choices and capabilities.

**CSS:** `display: flex; flex-direction: column; gap: 28px; padding: 32px; background: #0d212c; border: 1px solid #163341; border-radius: 10px`

**Text style:** `card-heading` — Space Grotesk 500 · 20px/1.45

**Observed:** Small line icon first, title and concise body second, Arrow link last. Default cards form a three-column row; longer solution cards can add bullets. A two-card secondary row uses the canvas fill with the same thin edge.

**Transfer:** Use equal card heights within a row; keep illustrations small so text leads.

### Problem tab

**Use:** Switch a large demonstration panel between reader problems.

**CSS:** `border: 1px solid #163341; border-radius: 4px; padding: 10px 20px; color: #b9c2c6; background: transparent`

**Text style:** `action` — Space Grotesk 400 · 14px/1.5

**Observed:** A horizontally arranged strip leads the panel. The selected tab uses blue-green fill and a stronger outline; other tabs remain outlined rather than underlined.

**States:** Declared: hover color #fff and border-color #2d4754; focus-visible outline 2px solid var(--themeFgBrand), outline-offset 2px.

**Transfer:** Let a real reader problem name each tab; connect the selection to the panel story and proof.

### Closing panel

**Use:** A calm final conversion point.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 36px; padding: 48px 24px; background: #0d212c; border: 1px solid #163341; border-radius: 10px`

**Text style:** `heading` — Space Grotesk 500 · 32px/1.2

**Observed:** A centered heading sits over one short support sentence separated by 20px; actions sit below. The default contained panel spans the usable 1120px width. Commercial pages use one chat action; solutions and organizational pages usually pair self-serve and assisted routes.

**Transfer:** Resolve the next step instead of introducing a new benefit list.

### Footer columns

**Use:** Compact sitemap and institutional information.

**CSS:** `background: #091a23; padding: 44px 0px 92px`

**Text style:** `footer-link` — Space Grotesk 400 · 12px/1.4

**Observed:** A wide left rail holds the red mark, six small social links, legal links and a language selector. Four narrow sitemap columns use brighter 18px category headings, 8px gaps between muted links and 32px gaps between columns.

**Transfer:** Keep the footer information-dense without turning it into a contrasting light band.

### Resource square

**Only for:** resource collections

**Use:** Editorial onward reading near the end of a technical page.

**CSS:** `display: flex; flex-direction: column; width: 268px; height: 268px; background: #091a23; border: 1px solid #8a99a0; border-radius: 5px; box-sizing: border-box`

**Text style:** `resource-title` — Space Grotesk 400 · 26px/31px

**Observed:** Text occupies the top with a small reading link at the bottom. Content receives 20px padding; four squares sit in a row with 16px gaps.

**Transfer:** Treat the title itself as the visual; no stock thumbnail is needed.

### Featured plan

**Only for:** pricing pages

**Use:** Give one commercial tier extra prominence.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 30px; max-width: 370px; background: #0d212c; border: 2px solid #2d4754; border-radius: 10px; transform: scale(1.1)`

**Text style:** `card-heading` — Space Grotesk 500 · 20px/1.45

**Observed:** The rightmost tier grows beyond its joined neighbors and carries an uppercase title plus purple offer badge. Price, billing qualifier, full-width Primary button and hairline-separated feature list follow; lime checks identify inclusions.

**Transfer:** Use the enlargement for one tier only, retaining the same dark material as the other plans.

## Imagery and graphics

### Isometric platform sculpture

**Use:** Signature product mechanism in an open chapter or beside an explanation.

**Observed:** Dark teal beveled slabs form an exploded stack with a vivid red middle layer. Small outlined modules occupy the upper plane, with fine dashed lower ghosts. The object is isolated on the page ground, approximately 400px wide within a larger scene, with generous darkness around it.

**Transfer:** Translate the product's core relationship into stacked layers and small modules. The minimum version is a clean SVG stack, not a generic interface screenshot.

**Build:** Use an SVG viewBox about 664 by 830. Draw three rounded rhombi with roughly 2:1 width-to-height perspective, offset vertically by 35–55px. Add 18–24px side faces in #163341 and #091a23; make one slab #ff4438 with a darker red side using rgba(255,68,56,0.65). Place a 3-by-3 grid of smaller dark rhombi with white outline glyphs on top. Add lower ghost planes with 1px #2d4754 dashed strokes. Keep the background transparent and omit heavy cast shadows.

### Connected geometric machine

**Use:** Signature explanation art occupying roughly half a large demonstration panel.

**Observed:** Red wireframe discs, polyhedra and cubes connect by fine red lines to a central raised circular hub. Dark red translucent faces contrast with delicate outlines; the panel can clip the lower satellites.

**Transfer:** Represent one hub and several related inputs or outputs with simple geometry, keeping red restricted to the mechanism.

**Build:** In an SVG approximately 438 by 400, arrange a central 140px disc and four 70–90px satellite circles. Use 1px #ff4438 strokes at about 0.65 opacity and fills rgba(255,68,56,0.2). Add elliptical base rings offset downward by 12px and connect centers with thin lines. Place cubes, faceted diamonds and a filled circle inside the nodes; let the bottom pair extend beyond the panel edge.

### Faint geometric field

**Use:** Subtle technical atmosphere behind the opening command panel.

**Observed:** Very low-contrast triangular and isometric grid lines fade into the dark field; no noisy texture or bright aura competes with the headline.

**Transfer:** Retain the geometric field even without complex product media.

**Build:** Tile an SVG pattern made from vertical lines and diagonals at 30 and 150 degrees, with cells about 80px wide. Stroke #163341 at 0.25 opacity and 1px width. Mask with a radial fade centered behind the 430px panel so the outer canvas is nearly solid.

### Friendly closing object

**Use:** Signature pause between the closing action and footer on the default marketing page.

**Observed:** A small rounded robot floats in a 428px by 242px canvas stage: white shell, red torso, dark visor and a tiny antenna. The actual character occupies much less than the stage, surrounded by uninterrupted dark ground.

**Transfer:** Create a small approachable product-related character, tool or symbolic object with the same rounded red-and-white construction; keep it subordinate to the conversion panel.

**Build:** Use SVG ellipses for a rounded white head and belly, a red torso, two tapered white side shapes, a dark rounded visor with two tiny white eyes and three thin antenna rings. Group it within the center third of a 428 by 242 viewBox. Use subtle dark-teal side faces rather than realistic highlights.

### Technical architecture diagrams

**Only for:** technical solution explanations

**Use:** Alternating two-column chapters and architecture proof.

**Observed:** On white, sparse black and gray connectors join outlined cylinders, application boxes and red server blocks; captions are small and diagrammatic. The dark variant uses a framed dark field with red nodes and subdued connectors. Diagrams occupy around 510px of a 1120px row.

**Transfer:** Draw the actual new system's flow with a small set of consistently repeated primitives. Keep arrows and labels legible rather than replacing the mechanism with abstract decoration.

### Pastel data tiles

**Only for:** split solution openings

**Use:** Isometric hero art alongside sentence-case copy.

**Observed:** A white tilted vertical plane holds a grid of shallow raised tiles, with cyan, lilac and acid accents. More tiles float on faint vertical rails outside the plane. The art is about 528px by 406px and sits directly on the blue-green gradient.

**Transfer:** Use a small structured collection that illustrates the product's inputs and assembled result; keep the pastel color confined to this art.

**Build:** Draw a white parallelogram in SVG, offset a dark-teal copy behind it, and populate it with a 3-by-4 grid of outlined extruded tiles. Give only a few tiles cyan, lavender or #dcff1e faces; surround the plane with several smaller offset tiles and low-opacity vertical rules.

### Portrait collage and directory

**Only for:** organizational pages

**Use:** Humanize the identity opening and leadership grid.

**Observed:** Black-and-white portraits on pale backgrounds. In the opening, differently sized 100–200px tiles scatter at the far edges and partly leave the viewport, leaving the center clear. The directory regularizes portraits into 250px square tiles with 10px corners, names and uppercase monospaced job labels below.

**Transfer:** Use authentic people in consistent grayscale light. Keep the collage limited to the organizational opening and the regular grid for the directory.

### Icons

**Observed:** Small functional arrows are 12px; utility glyphs fit 14–16px inside 32px controls. Capability icons are usually 32px line-art symbols with white or gray strokes and occasional red dots. Light technical benefits use 64px outline illustrations with red details; result lists use acid filled check circles.

**Transfer:** Choose simple geometric line symbols with consistent optical weight. Give red dots and acid checks a specific functional meaning rather than coloring every icon.

## Section recipes

How recurring sections are built.

### First screen: Command stage opening

**Observed:** A 38px announcement band precedes the 70px Sticky navigation. The Midnight canvas hero occupies the next 614px, with 110px top and 118px bottom padding. A centered 100px condensed uppercase headline spans roughly 810px, a little over half the viewport width. Behind it and the small working panel is the Faint geometric field. A 430px-wide Prompt panel follows after 48px; its body question acts as the practical support rather than an additional prose deck. Another 48px separates it from the paired Primary button and Secondary button, each 47px high with a 16px gap. The headline, whole command panel and actions are visible within the first 900px; the following 32px chapter title and top of its tabbed panel also enter the first screen, while its detailed explanation and machine art continue below.

**Transfer:** Keep the centered statement-plus-working-miniature composition for a new marketing page. Replace the prompt with an authentic small task or executable example, and use the geometric field when there is no hero illustration. Solution pages instead open with a 64px sentence-case promise, short supporting paragraph and actions, either centered within 900px or split beside isometric art. Commercial pages center a 64px heading over a plan selector; organizational pages frame a condensed identity statement with edge portraits.

**Avoid:** Do not enlarge the command panel into a full dashboard, place a huge colorful screenshot behind the headline, or add an extra oversized prose deck that displaces the actions below the fold.

**Text style:** `display` — primaryFont 400 · 100px/0.85 · tracking -0.01em · uppercase

### Acid chapter heading

**Observed:** A 32px heading carries one acid-colored word or phrase without changing its weight. A 10px outlined acid ring precedes the title with a 20px gap. Centered versions place a 16px supporting line about 18px below; left-aligned versions sit about 32px above their panel.

**Transfer:** Use the highlight for the pivot in the promise, not an entire sentence.

**Text style:** `heading` — Space Grotesk 500 · 32px/1.2

### Tabbed mechanism and proof

**Observed:** Problem tab controls line the top of an Instrument panel. A left text column contains a technical label, 32px promise, 16px explanation and Arrow link; Connected geometric machine fills the right. A bottom rail is divided into two halves: one pairs a 40px metric with a short explanation and a 2px acid left rule, while the other holds a command question.

**Transfer:** Tie each reader problem to one mechanism and one credible proof point, keeping evidence attached to the explanation rather than in a disconnected testimonial strip.

### Capability shelf

**Observed:** An Acid chapter heading sits over three Capability cards with 32px column gaps. A pair of lower, canvas-filled cards may extend the story with short product labels and parallel benefit statements.

**Transfer:** Use the upper row for clear routes or core capabilities, and the lower row for complementary operating advantages.

### Quiet proof rail

**Observed:** Small proof numbers use 32px medium grotesk and muted gray rather than bright giant numerals. On solution pages, four 280px proof cells use 32px left/right padding and thin left rules; captions sit 12px below.

**Transfer:** Use verified metrics with short labels; let the proof reassure rather than outshout the opening.

### Resources and resolved close

**Observed:** Closing panel provides the default final ask, followed by the Friendly closing object and Footer columns. The light technical variant first places four Resource squares on a dark band under a 50px heading, then uses a white conversion band with a red filled primary action and pale secondary action before the dark footer. Pricing closes with a single chat action in the contained panel. Organizational and long-form dark solution pages use paired actions in the contained panel and proceed directly to the footer.

**Transfer:** Preserve a clear end-state: helpful next step, visual breathing room, then navigation. The default marketing sign-off object supplies the warm pause; do not force it into every scoped page type.

### Solution chapter and outcomes

**Only for:** long-form dark solution pages

**Observed:** An uppercase mono eyebrow, 32px heading and support text form a left-aligned lead with about 24px gaps. Unboxed four-column lists sit well below the lead, using 60px column gaps. Problem lists use subdued minus symbols; outcome lists use acid check circles. Thin horizontal rules separate major chapters.

**Transfer:** Contrast the failure mode and the practical result with parallel item structures; do not box every item.

### Technical diagram alternation

**Only for:** light technical solution pages

**Observed:** Technical paper holds alternating 510px diagram and text fields separated by 100px. Text uses a 24px title, 16px paragraphs and a red Arrow link. Broad 72px chapter spacing keeps the repeated architecture patterns distinct.

**Transfer:** Make one chapter per meaningful mechanism, changing diagram orientation only to maintain narrative rhythm.

### Technical comparison and benefits

**Only for:** light technical solution pages

**Observed:** A hairline comparison table contrasts two approaches, with a pale first header and a red advanced header. A later Frost feature band gives a 40px heading the left third and a two-column benefit field the remaining width. FAQ rows on white have bottom rules and compact toggles.

**Transfer:** Use the table to clarify tradeoffs, the feature band to summarize reliability and operating value, and FAQs to answer remaining objections.

### Plans and comparison

**Only for:** pricing pages

**Observed:** Centered heading, supporting sentence and rounded two-way selector lead into three joined dark plan cards. Featured plan grows to 1.1 times its layout size. A four-column comparison table below aligns feature names with three plan columns, repeating conversion buttons at its top; rows use thin rules and acid or muted inclusion marks.

**Transfer:** Keep billing context next to price and allow the comparison to carry detail instead of crowding the opening.

### Organizational proof

**Only for:** organizational pages

**Observed:** A condensed portrait-framed opening leads into split mission copy, compact value statements and a four-column grayscale directory. A later three-part metric row uses 180px red condensed numerals; locations use red pins rather than maps.

**Transfer:** Translate identity into people, operating principles and genuine scale facts; keep the monumental figures specific to institutional storytelling.

**Text style:** `monumental-stat` — primaryFont 500 · 180px/0.9 · tracking -0.01em

## Page flow

**Storyline:** Promise → usable demonstration → reader problem and mechanism → proof → capability or architecture chapters → resolved next step → compact institutional navigation.

### Introduce a broad platform through an immediately usable task

1. **promise** — Condensed statement above a small command panel and paired actions.
2. **problem and demonstration** — Tabbed Instrument panel connects reader problems to a mechanism and a proof rail.
3. **activation** — Short setup command makes the time-to-first-use tangible.
4. **product model** — An isolated isometric stack explains the unifying platform.
5. **social proof** — Muted metrics and a restrained logo collection.
6. **capability choices** — Three capability cards and a smaller paired benefit row.
7. **closing call** — Contained conversion panel, friendly sculptural interlude and dark sitemap footer.

**Transfer:** Make an abstract product understandable through one working miniature and one physical metaphor; adapt chapter order to the buying story.

### Help readers select and compare commercial options

1. **commercial promise** — Centered sentence-case heading and billing/deployment selector.
2. **pricing** — Three joined plan cards with one enlarged featured tier.
3. **comparison** — Aligned feature matrix with repeated plan actions and fine horizontal rules.
4. **objection handling** — Contained pricing-question panel with one chat action.
5. **institutional navigation** — Dark sitemap footer without a separate sculptural interlude.

**Transfer:** Keep comparison and conversion close together; reserve the emphasized tier for a real recommendation.

### Teach a technical approach and establish enterprise readiness

1. **promise** — Centered dark solution hero with paired actions.
2. **explanation** — White split introductory content and supporting media.
3. **comparison and proof** — Two-approach feature table and customer-logo band.
4. **architecture chapters** — Alternating diagrams and explanations across sustained white ground.
5. **capability summary** — Pale benefit band with a large left heading.
6. **objection handling** — Compact white FAQ rows.
7. **further learning** — Dark resource band with four outlined squares.
8. **closing call** — White conversion band followed by the shared dark footer.

**Transfer:** Use the sustained light body when the reader needs to inspect diagrams and compare patterns; do not average it into the default dark treatment.

### Connect a complex product architecture to business and technical outcomes

1. **promise** — Split gradient hero with 64px copy and pastel isometric art.
2. **quantified proof** — Four compact metrics beneath local chapter navigation.
3. **problem** — Eyebrow-led framing and four unboxed failure modes.
4. **solution model** — Three tall capability cards followed by a split accordion explanation.
5. **outcomes** — Two rows of four acid-check result items.
6. **architecture** — Dark technical diagram paired with explanatory copy.
7. **applications and ecosystem** — Three application cards followed by a text-and-stacked-panel compatibility chapter.
8. **closing call** — Contained paired-action panel and dark sitemap footer.

**Transfer:** Give complex enterprise pages local chapter navigation and alternate compact unboxed lists with substantial panels.

### Establish organizational identity, credibility and human presence

1. **identity** — Local navigation and portrait-framed condensed headline.
2. **purpose and principles** — Split organizational statement followed by compact values.
3. **human proof** — Four-column grayscale leadership directory.
4. **quantified scale** — Three monumental red display figures.
5. **presence** — Distributed location labels with red pins.
6. **closing call** — Contained conversion panel and shared dark footer.

**Transfer:** Keep the company-specific portrait and monumental-stat language scoped to institutional storytelling.

## Writing

Direct, technically fluent and brisk, with a dry playful turn in headline language. Confidence comes from naming the mechanism and the operational result, not from ceremonial enterprise language.

**Do not copy:** Do not reuse Redis names, logos, mascot artwork, product names, customer marks, benchmark numbers, uptime or savings claims, quotations or source commands as claims for another product. Source examples illustrate voice only.

- **Addressing the reader:** Address the reader as you or your when describing a problem or route forward. Use we for help and expertise; name the product when explaining a specific mechanism.
- **Rhythm:** Short headlines and action labels alternate with concrete explanatory sentences. Parallel clauses, clipped contrasts and occasional questions create pace; technical paragraphs can be longer when they explain a real dependency.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | An energetic statement or direct question that invites the reader into a task. | 4–9 words | “Inquiring agents want to know:”<br>“Make instant decisions with real-time data” |
| Chapter promise | A practical result phrased with repetition or an explicit contrast. | 4–10 words | “Find the right context, right away.”<br>“Scale your data. Not your spend.” |
| Support line | Say what the reader can do, with a specific tool, deployment or mechanism. | One sentence, usually 10–30 words | “Work seamlessly from any stack with one unified platform for real-time agents and apps”<br>“Find the right fit for your business and start building fast apps fast.” |
| Technical explanation | Explain a causal relationship, not just a benefit adjective. | Two or three sentences when necessary | “Decisions require multi-hop lookups across 6 to 8 disconnected systems. Each hop adds unpredictable latency and incomplete context.” |
| Action | Verb plus clear destination, product or human route. | 2–4 words | “Get started”<br>“Talk to an expert”<br>“Chat now” |

**Words and phrasing to use:** build; fast; right away; scale; context; work seamlessly; real-time; your; not your; get started

**Avoid:** revolutionary synergy; unlock limitless possibilities; effortlessly transform everything; world-class innovation without a mechanism; ceremonial welcome language

**Rules:**

- Pair each abstract benefit with a concrete mechanism, task or measurable operational consequence.
- Use parallel syntax to make a contrast memorable, then explain it in plain language.
- Keep action labels specific to the commitment: trying, learning or speaking with a person.
- Use questions to surface reader intent, not as filler between every chapter.

## Do's and Don'ts

### Do

- Keep the desktop usable content width at 1120px inside the 1280px padded shell.
- Use the 100px condensed display only for the default opening; return to 32px medium grotesk for chapters.
- Give normal chapters 72px vertical padding and cards 32px inner padding.
- Use 1px #163341 borders and 10px corners to distinguish dark panels without shadows.
- Pair 47px hero actions with 16px separation; use 43px controls elsewhere.
- Make acid emphasis one word or phrase at the same size and weight as its 32px heading.
- Retain a small usable command or task panel and a physical geometric product metaphor.
- Set the footer links at 12px/1.4 and keep their columns compact with 32px gaps.

### Don't

- Do not turn every action into a rounded pill; 5px corners are the conversion-button default.
- Do not fill ordinary marketing sections with lime or red; those hues act as signals within a dark field.
- Do not replace the subtle panel separation with white cards or soft gray shadows on the default page.
- Do not use the 180px red numeral recipe for ordinary capability-card statistics; it belongs to organizational scale proof.
- Do not distribute the pastel tile palette into navigation, body typography or generic cards.
- Do not use a glossy photorealistic render for every technical diagram; preserve flat outlined geometry and legible system relationships.
- Do not give every chapter a 64px heading; that size belongs to solution and commercial openings.
- Do not introduce a white footer to follow the light technical variant; the shared ending returns to midnight.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.2s transitions. Problem tabs declare background-color, color and border-color transitions of 0.15s.
- The sticky header declares transform and box-shadow transitions of 0.3s with cubic-bezier(0.4, 0, 0.2, 1).
- Some elements declare staggered 1s ease-in-out fade-ins with 0s, 0.1s, 0.2s and 0.3s delays.

**Transfer:**

- Preserve quick border/fill feedback on equipment-like controls. The product sculpture can be a staged scene, but its settled state must explain the mechanism without motion.

**Unknown:**

- The exact scroll choreography, scene durations and trigger behavior of canvas art are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 660px, 768px, 900px, 1024px and 1260px; the desktop shell is 1280px including side padding.

**Transfer:**

- For narrower layouts, retain the command miniature beneath the condensed statement and keep its controls usable; reduce headline width rather than making a giant dashboard.
- Reflow technical splits and capability grids into a readable sequence while preserving the diagram-to-explanation pairing; keep the small sign-off object centered.

**Unknown:**

- Exact mobile typography, gutter sizes, column changes and navigation behavior are not established. These reflow rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
