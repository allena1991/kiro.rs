# EPIC — couture type, playful machinery

## Overview

An editorial, art-directed style where razor-edged serif lettering meets small utilitarian sans-serif labels and imaginative objects. The default is light grey and black, with saturated color concentrated in photographic or rendered subjects; cream and coral, mint and teal, and charcoal and pale gold form distinct editorial themes. It suits expressive product launches, creative technology and portfolios, with sparse interfaces, expansive stages and moments of dense storytelling.

### Essentials

- Fashion-editorial lettering carries the drama: Sang Bleu at 80px/1 and weight 900 for the main project title, contrasted with Inter actions at 14px/1.4 and weight 700.
- The opening is an object stage, not a centered sales stack: a 900px-tall grey scene, a 1200px content width, a large isolated subject across the middle, title and actions at lower left, and a 300px ruled editorial rail at right.
- Controls feel like fine outlines rather than blocks: 1px borders, 30px button radii, 4.9px by 17.5px padding and an arrow after the label; social controls are 36px circles.
- Color belongs to the subject first: #d4d4d4 and #121212 cover the ordinary page furniture, while vivid photographic or rendered media occupies bounded stages. Alternate page themes replace both canvas and ink together, not individual rainbow sections.
- Ideas become a small theatrical machine: include an outlined, faceted object or assemblage paired with a short bold serif phrase; a simple SVG construction over a fading graph grid is the minimum equivalent.
- The ending becomes a typographic destination: centered 80px/1.2 uppercase serif words, a 10px label with 5px tracking, fine horizontal rules, then an 80px-padded compact footer. Keep this monumental text-link device even when the destination changes.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted brass | `#c0ae7e` | `--color-hover-fill` | action | Hover fill on outlined actions and social circles. |
| Brown gold | `#775f2d` | `--color-hover-ink` | text, link | Hover lettering on links and small actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Studio grey | `#d4d4d4` | `--color-canvas` | background, surface | Default continuous page and studio backing. |
| Near-black ink | `#121212` | `--color-ink` | text, border, action | Default lettering, rules and outlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| capability and process pages | Coral red | `#ff4552` | `--color-coral` | text, border, action | Single ink color throughout the expressive capability theme. |
| capability and process pages | Warm cream | `#fef6e5` | `--color-cream` | background, surface | Continuous backing and photographic print borders in the coral theme. |
| capability and process pages | Pale coral edge | `#ffaebc` | `--color-print-edge` | border | Visible half-opacity coral over cream; built with rgba(255,69,82,0.5). |
| responsibility and institutional stories | Deep teal | `#00738c` | `--color-teal` | text, border, action | Single ink for explanatory editorial pages. |
| responsibility and institutional stories | Mint paper | `#eef8e6` | `--color-mint` | background | Continuous pale backing for teal lettering and documentary photographs. |
| portfolio and reference galleries | Portfolio charcoal | `#3a3b43` | `--color-charcoal` | background | Dark gallery canvas. |
| portfolio and reference galleries | Pale gold ink | `#f1dca8` | `--color-pale-gold` | text, border, action | Gallery typography and rules. |
| portfolio and reference galleries | Dark exhibit backing | `#272928` | `--color-gallery-dark` | surface | Example dark project-specific backing for isolated imagery. |
| portfolio and reference galleries | White lettering | `#ffffff` | `--color-white` | text, surface | Light lettering on dark project artwork and light exhibit backing. |

## Typography

- **sang-bleu** — High-contrast display headings, editorial statements and large numerals. Sharp triangular serifs, exceptionally thin hairlines against very heavy stems, with expressive angular curves. If unavailable, use **Bodoni Moda**. Use 900 for display, 400 for prose and 200 for numerals; preserve wide letterforms. Font stack: "sang-bleu", "Bodoni Moda", Georgia, serif.
- **inter** — Body text, tiny labels, controls and captions. Matter-of-fact contemporary grotesk that deliberately recedes beside the serif. Font stack: "inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | sang-bleu | 900 | 80px | 1 | normal | Default featured title in sentence case. |
| destination | sang-bleu | 900 | 80px | 1.2 | normal, uppercase | Monumental centered destination links and closing calls. |
| statement | sang-bleu | 400 | 42px | 1.65 | normal | Centered editorial manifesto spanning several lines. |
| statement-emphasis | sang-bleu | 700 | 42px | 1.65 | normal | A few action words within the statement and accompanying object scene. |
| body | inter | 400 | 18px | 1.65 | normal | Lead paragraphs and supporting prose. |
| body-compact | inter | 400 | 16px | 1.563 | normal | Long-form explanations and capability descriptions. |
| action | inter | 700 | 14px | 1.4 | normal, uppercase | Outlined actions and adjacent arrow links. |
| small-copy | inter | 400 | 14px | 1.563 | normal | Editorial rail titles and gallery filters. |
| footer | inter | 400 | 14px | 1.65 | 0.036em | Contact information. |
| language | inter | 600 | 13px | 1.65 | normal, uppercase | Language selector. |
| micro-action | inter | 700 | 11px | 1.4 | normal, uppercase | Compact newsletter control. |
| eyebrow | inter | 400 | 10px | 3 | 0.5em, uppercase | Centered chapter labels and header motto. |
| metadata | inter | 400 | 10px | 1.3 | 0.2em, uppercase | Dates in the opening editorial rail. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability and process pages | chapter-number | sang-bleu | 200 | 240px | 1 | normal | Very thin chapter numerals with a period. |
| capability and process pages | chapter-title | sang-bleu | 900 | 130px | 1.077 | normal | Oversized capability names, process verbs and horizontal gallery headings. |
| institutional and capability editorial pages | editorial-title | sang-bleu | 900 | 120px | 1.2 | normal | Large two-line title for an institutional story. |
| institutional editorial pages | editorial-heading | sang-bleu | 900 | 50px | 1.2 | normal | Question-like left-column headings. |
| capability and process pages | lead-copy | inter | 400 | 30px | 1.333 | normal | Right-half introduction below the poster title. |
| portfolio and reference galleries | project-title | sang-bleu | 900 | 30px | 1.1 | normal | Lower-left labels inside gallery exhibits. |
| institutional editorial pages | accordion-question | inter | 600 | 20px | 1.25 | normal | Full-width FAQ triggers. |
| capability and process pages | print-caption | inter | 400 | 12px | 1.3 | normal | Small, conversational captions inside framed prints. |

**Notes:**

- Keep tracking normal on the large serif; its dramatic shapes do the work. Wide spacing belongs to tiny sans-serif labels, not titles.
- Use sentence case on featured titles, title case on capability names, and capitals on destination links. Do not normalize all of these into one heading style.
- The capability poster is fitted typographic artwork: stretch its lines across the content width while keeping the letter shapes undistorted, with tiny factual annotations tucked into the rag. Treat this as a separate composition rather than a normal paragraph.

## Layout

**Density:** Airy stages with compact utility details; long pauses around imagery contrast with tightly packed editorial rails and footers.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Print padding, small action gaps and editorial row padding. |
| 15px | Label-to-destination spacing and gaps between social circles. |
| 20px | Featured title to actions and heading to support text. |
| 30px | Gallery gutters and separation between prose blocks. |
| 34px | Paragraph bottom margins in long-form editorial copy. |
| 40px | FAQ heading-to-list gap. |
| 60px | Editorial grid gaps and footer bottom clearance. |
| 80px | Major section margins, footer top padding and rule-to-content pauses. |
| 100px | Editorial column offset and inset process composition. |
| 130px | Space between oversized capability chapters. |
| 180px | Opening content clearance above the bottom of the stage. |

### Containers and grids

- **content**: max width 1200px · side padding 0px. Centered desktop content with 120px outer margins at 1440px; media stages can extend beyond it.
- **opening rail**: max width 300px. Right-hand stack of short editorial updates aligned with the title and actions across the stage.
- **editorial split** (only for institutional editorial pages): 2 columns · gap 100px. A 500px left heading column and a 600px right text column within the main width.
- **project grid** (only for portfolio and reference galleries): max width 1200px · 2 columns · gap 30px. Two 585px-wide exhibits, each 380px tall.
- **principle grid** (only for institutional editorial pages): 3 columns · gap 80px. Unboxed text columns, about 347px wide, with a short bold sans-serif heading.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | outlined actions | 30px |
|  | language selector | 20px |
|  | social controls | 50% |
|  | video frame | 10px |
| portfolio and reference galleries | project exhibits | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| capability and process pages | print offset | `10px 10px 0px 0px rgba(0,0,0,0.2)` | Hard displaced shadow behind the layered photographic prints. |

### Surfaces

#### Studio canvas · level 0

**Use:** Default page surface.

**CSS:** `background: #d4d4d4; color: #121212`

**Observed:** A continuous neutral field, not alternating white cards.

**Transfer:** Let object lighting supply depth while the page itself remains flat.

#### Coral paper · level 0

**Only for:** capability and process pages

**Use:** Expressive editorial theme.

**CSS:** `background: #fef6e5; color: #ff4552`

**Observed:** One cream and coral pairing extends through headings, rules, captions and footer.

**Transfer:** Apply the pairing to a whole page, not a stray callout.

#### Mint paper · level 0

**Only for:** responsibility and institutional stories

**Use:** Documentary editorial theme.

**CSS:** `background: #eef8e6; color: #00738c`

**Observed:** Flat pale green backing with teal type and large unrounded photographs.

**Transfer:** Use natural photography and an explanatory two-column rhythm.

#### Dark gallery · level 0

**Only for:** portfolio and reference galleries

**Use:** Showcase theme.

**CSS:** `background: #3a3b43; color: #f1dca8`

**Observed:** Warm pale lettering and thin rules surround independently colored project exhibits.

**Transfer:** Keep the gallery furniture consistent while each exhibit has its own backing.

#### Photographic print · level 1

**Only for:** capability and process pages

**Use:** Layered examples and candid culture photographs.

**CSS:** `background: #fef6e5; border: 1px solid rgba(255,69,82,0.5); padding: 10px; box-shadow: 10px 10px 0px 0px rgba(0,0,0,0.2)`

**Observed:** Square-cornered prints overlap at varied angles; a narrow caption sits beneath each image.

**Transfer:** Use real product work or candid moments; preserve the physical-paper illusion.

## Components

### Sticky navigation

**Use:** Persistent compact orientation.

**CSS:** `position: sticky; height: 102px; z-index: 2000`

**Observed:** A small symbol at left, tiny spaced motto or page label at center, language selector and three-line menu at right. A fine rule spans the content width at the opening; after scrolling the compact controls sit near the viewport edges.

**Transfer:** Use the new identity symbol and a short editorial motto, not a full row of navigation links.

### Outlined action

**Use:** Primary case or capability action.

**CSS:** `display: flex; align-items: center; padding: 4.9px 17.5px; border: 1px solid #121212; border-radius: 30px; background: transparent; color: #121212; transition: background-color 0.2s`

**Text style:** `action` — inter 700 · 14px/1.4 · uppercase

**Observed:** A right-pointing arrow follows the label. A secondary arrow link sits beside it without the outline. Theme ink replaces black on alternate pages.

**States:** Declared: hover color #775f2d, background-color #c0ae7e, fill #000000; focus-visible not specified.

### Language selector

**Use:** Small header language control.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; padding: 4px 12px; border: 1px solid #121212; border-radius: 20px; background: #d4d4d4; color: #121212`

**Text style:** `language` — inter 600 · 13px/1.65 · uppercase

**Observed:** A small downward chevron follows a two-letter language code; both ink and backing follow the page theme.

### Editorial update row

**Use:** Compact opening news or release rail.

**CSS:** `width: 300px; border-top: 1px solid #121212; padding: 10px 0px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `small-copy` — inter 400 · 14px/1.563

**Observed:** Date above title, with a 5px internal gap. A tiny category label and see-all arrow sit above the rail. Three rows form a quiet counterweight to the large object.

**States:** Declared: hover color #775f2d and filter brightness(1.2); focus-visible not specified.

### Newsletter action

**Use:** Tertiary footer subscription control.

**CSS:** `display: flex; align-items: center; padding: 3.9px 13.8px; border: 1px solid #121212; border-radius: 30px; background: transparent; color: #121212`

**Text style:** `micro-action` — inter 700 · 11px/1.4 · uppercase

**Observed:** A tiny document icon ends the label; the control sits below and right-aligned with the social row.

**States:** Declared: hover color #000000, background-color #c0ae7e and fill #000000; focus-visible not specified.

### Social circle

**Use:** Footer external social links.

**CSS:** `width: 36px; height: 36px; display: flex; align-items: center; justify-content: center; border: 1px solid #121212; border-radius: 50%`

**Observed:** Four small filled platform symbols are centered in outlined circles; the row has 15px gaps and follows the page ink.

**States:** Declared: hover background-color #c0ae7e, fill #000000 and color #775f2d; focus-visible not specified.

### Contact footer

**Use:** Final utility and contact area.

**CSS:** `max-width: 1200px; display: flex; justify-content: space-between; border-top: 1px solid #121212; padding-top: 80px; margin-bottom: 60px; background: #d4d4d4`

**Text style:** `footer` — inter 400 · 14px/1.65 · tracking 0.036em

**Observed:** Left: bold organization name, postal address, phone. Middle: three small outline emblems above stacked policy links. Right: Social circle row above Newsletter action. All four themes retain this structure without a large logo or colored footer band.

**Transfer:** Keep the hierarchy small and practical after the monumental destination link.

### Project exhibit

**Only for:** portfolio and reference galleries

**Use:** Clickable selected work card.

**CSS:** `width: 585px; height: 380px; position: relative; overflow: hidden; border-radius: 8px; background: #272928`

**Text style:** `project-title` — sang-bleu 900 · 30px/1.1

**Observed:** A centered square image occupies most of the card height; a serif title is pinned lower left with about 30px side inset. Each project chooses a complementary background and title ink. No separate white card footer.

**Transfer:** Show a cutout product, architectural subject or miniature 3D scene on a backing that makes it legible.

### Gallery filter

**Only for:** portfolio and reference galleries

**Use:** Category navigation above exhibits.

**CSS:** `display: flex; align-items: center; gap: 5px; padding: 3.5px 10px; border: 1px solid #f1dca8; border-radius: 96px; color: #f1dca8; transition: border-color 0.35s ease-in-out`

**Text style:** `small-copy` — inter 400 · 14px/1.563

**Observed:** Only the selected filter has a visible outline; other pills retain transparent borders. Counts appear as tiny superscripts, with an award emblem on the selected highlight filter. The full filter row sits between two horizontal rules.

**States:** Declared: hover color #775f2d; focus-visible not specified.

### FAQ row

**Only for:** institutional editorial pages

**Use:** Closing objection handling.

**CSS:** `display: flex; justify-content: space-between; padding: 20px 0px; color: #00738c; background: transparent`

**Text style:** `accordion-question` — inter 600 · 20px/1.25

**Observed:** Full-width question with a 28px downward arrow at the far right; the enclosing row has a 1px teal top rule. Answers use 18px/25px prose with selective bold emphasis.

**Transfer:** Use plain-language questions that address genuine reservations, not promotional headings.

### Print figure

**Only for:** capability and process pages

**Use:** Tactile proof and candid captions.

**CSS:** `position: relative; padding: 10px; background: #fef6e5; border: 1px solid rgba(255,69,82,0.5); box-shadow: 10px 10px 0px 0px rgba(0,0,0,0.2)`

**Text style:** `print-caption` — inter 400 · 12px/1.3

**Observed:** Image first, then an informal caption after a 10px gap. Several figures stack and tilt, with corners spilling beyond the column.

**Transfer:** Reserve this physical collage treatment for the expressive editorial theme.

## Imagery and graphics

### Isolated hero subject

**Use:** Main object in the default first screen.

**Observed:** A glossy red vintage sports car is shown in side profile, horizontally centered across the lower middle of a grey studio. Broad pale light and soft floor shadows detach it from the neutral field; the title sits partly beneath its left half and the editorial rail overlays its right edge. The subject is vivid, while the rest stays nearly monochrome.

**Transfer:** Use one crisply isolated product or an object that embodies its benefit. For software, render a single sculptural device or physical metaphor rather than a collage of dashboard panels.

**Build:** Place a transparent subject image above a broad elliptical radial-gradient in rgba(255,255,255,0.45) fading to transparent, and a shallow black ellipse at rgba(0,0,0,0.15) blurred beneath it. Use the studio-grey canvas as the base; keep light soft and shadow close to the floor.

### Faceted idea machine

**Use:** Signature conceptual interlude accompanying a short serif phrase.

**Observed:** A thin black wire-outline floating castle with balloon-like faceted forms sits on a graph-paper field that fades toward its edges. Grey planar faces give just enough volume, and a black circular seal hangs beneath. In the coral theme, smaller outline binoculars, gears and speakers overlap the large process words.

**Transfer:** Construct an original machine or object assembly that represents the new product's verbs. A static line-drawn SVG with shallow facets, a subtle grid and one seal-like action is the minimum version.

**Build:** Create an SVG assemblage about 350px wide by 650px tall using polygonal planes filled with the page canvas and black strokes around 1px. Add a few darker low-opacity facets, long thin connector lines, and a 110px circular ink seal with reversed lettering. Behind it, layer 25px graph lines in rgba(18,18,18,0.05), every fifth line slightly darker; fade the grid with a radial mask. Overlay the short phrase in statement-emphasis. On coral paper, use coral outline strokes and omit the graph backing.

### Project miniatures

**Only for:** portfolio and reference galleries

**Use:** Self-contained project exhibits.

**Observed:** Architecture cutouts, exploded packaging, circular animal photography and playful low-poly floating islands sit centered on bespoke plain backings. Subjects have soft environmental shadows or a small halo rather than busy edge-to-edge montages.

**Transfer:** Choose one dominant artifact per project and render it as an exhibit, keeping generous breathing room around it.

### Documentary widescreen photographs

**Only for:** responsibility and institutional stories

**Use:** Large proof pauses between explanatory blocks.

**Observed:** Unrounded 1200px by 730px images show outdoor group activity, real offices, handcraft, alpine landscape and collaborative gestures. Natural daylight, real environments and moderately rich greens contrast with the pale mint canvas; a certification emblem overlays some images.

**Transfer:** Use authentic workplace, use-context or landscape photography with a similarly direct documentary quality. Any trust mark should be justified and visually secondary.

### Captioned print collage

**Only for:** capability and process pages

**Use:** Examples beside chapters and candid images beneath culture headings.

**Observed:** Cream-framed full-color images of websites, games, workshops and informal team moments form overlapping stacks and a long horizontal strip. Slightly different rotations and hard offset shadows make them feel casually placed on paper, with humorous coral captions.

**Transfer:** Combine output examples with real behind-the-scenes pictures. If photography is unavailable, frame well-composed product exports in the same print construction instead of filling the page with generic stock scenes.

### Icons

**Observed:** Mostly small filled SVG symbols in the active page ink: 15–20px action arrows and footer symbols, a 13px by 7px language chevron, a 35px header identity mark, and 28px FAQ arrows. The menu uses three fine horizontal bars; conceptual illustrations use outlines instead of the filled control style.

**Transfer:** Keep interface icons tiny and functional. Use filled marks for controls and reserve complex outline drawing for the conceptual object scenes.

## Section recipes

How recurring sections are built.

### First screen: Studio object opening

**Observed:** The first 900px is one grey stage beneath a 102px sticky navigation. Back to front: grey field, soft broad studio light, isolated vivid subject across roughly the middle half of the width, then black title and utility overlays. The 80px featured title occupies the lower left, with Outlined action and a borderless secondary arrow link 20px below; the 300px Editorial update row rail sits on the right at the subject's lower edge. There is intentionally no supporting paragraph. Object, title, both actions and the editorial rail are visible above the fold, with 180px of lower clearance; the media reel begins below.

**Transfer:** Replace the subject with one photoreal product cutout or an original physical metaphor with the same soft lighting; retain the asymmetric title-and-rail balance. Gallery pages instead open with a wide reel, institutional stories use a two-line editorial title, and expressive capability pages use a fitted serif poster with micro-annotations.

**Avoid:** Do not turn this into a centered headline over a full-bleed photo, or place a standard dashboard mockup inside a rounded browser card.

**Text style:** `display` — sang-bleu 900 · 80px/1

### Reel stage

**Observed:** An eyebrow labels a centered 1200px by 675px media frame with 10px corners and a large circular play affordance. Thin rules and 80px outer pauses separate it from surrounding content.

**Transfer:** Use a real short demonstration or a deliberate poster image, with understated player controls rather than a grid of thumbnails.

### Statement into object

**Observed:** A tiny centered label sits 30px above a 42px/1.65 centered serif paragraph spanning the content width. Three bold action words separate from the prose and meet the Faceted idea machine in a spacious visual interlude.

**Transfer:** Write a compact product philosophy and carry a few meaningful verbs into the conceptual scene. The scene belongs somewhere in the narrative, not necessarily directly after the statement.

**Text style:** `statement` — sang-bleu 400 · 42px/1.65

### Monumental destination and utility ending

**Observed:** A hairline spans the content width, then a tiny tracked label sits 15px above centered uppercase 80px/96px serif lettering. The default destination is one line; the gallery and expressive editorial variants use two lines with 15px between them and a tiny trailing phrase. Contact footer follows after another rule and an 80px pause. The institutional variant instead ends with FAQ rows before the same compact footer.

**Transfer:** Give the next meaningful step the visual weight of a poster, not a colored conversion banner. Retain the typographic destination device somewhere on every new marketing page, even if a different final section follows it.

**Text style:** `destination` — sang-bleu 900 · 80px/1.2 · uppercase

### Editorial explanation pair

**Only for:** institutional editorial pages

**Observed:** A 50px serif question occupies the 500px left column, while 16px prose sits in the 600px right column after a 100px offset. Bold phrases mark proof, paragraphs use 34px bottom margins, and 80px pauses lead into Documentary widescreen photographs. A three-column principle grid can replace prose for grouped explanations.

**Transfer:** Use for rationale, standards, product methodology or detailed trust stories; vary text and photographic proof rather than boxing every claim.

**Text style:** `editorial-heading` — sang-bleu 900 · 50px/1.2

### Numbered capability spread

**Only for:** capability and process pages

**Observed:** A 240px hairline numeral and 1px vertical divider balance a heavy 130px two-line title. Small uppercase descriptors sit above the title, compact 16px prose and Outlined action below. A stack of Print figures overlaps from the opposite side, with chapter orientation alternating and about 130px between chapters.

**Transfer:** Use for a small set of substantial capabilities or use cases. Preserve the contrast between nearly weightless numerals and extremely heavy words.

**Text style:** `chapter-title` — sang-bleu 900 · 130px/1.077

### Alternating process words

**Only for:** capability and process pages

**Observed:** Inside a 100px inset, oversized 130px process verbs alternate left and right beside compact explanatory paragraphs. Small outline objects overlap letterforms; one word breaks across two lines to make room for its illustration.

**Transfer:** Use the new product's own action verbs and original related objects; let the words and drawings share a single composition.

**Text style:** `chapter-title` — sang-bleu 900 · 130px/1.077

### Horizontal photographic story

**Only for:** capability and process pages

**Observed:** Large serif chapter words travel horizontally above a continuous chain of tilted Print figures. Short 18px explanatory paragraphs sit under the headings, while the images overlap and occasionally run outside the viewport.

**Transfer:** Use for the people, practices or real-world context behind the product; preserve readable chapter-sized groupings rather than making a random photo wall.

**Text style:** `chapter-title` — sang-bleu 900 · 130px/1.077

### Gallery with index

**Only for:** portfolio and reference galleries

**Observed:** Gallery filter precedes a two-column Project exhibit grid, followed by a centered small outlined load-more control. A monumental destination link separates the exhibits from a dense alphabetized client index in four columns; index letters are bold and names regular at 18px/31.5px.

**Transfer:** Use exhibits for selected proof and a text-only index for breadth, such as integrations, customers or supported contexts.

## Page flow

**Storyline:** art-directed hook → tangible proof → explanatory point of view → deeper capability or trust story → monumental next step → compact contact utilities

### General marketing landing page

1. **Hook** — Studio object, featured title, two small actions and editorial update rail.
2. **Demonstration** — Wide reel with a compact centered label.
3. **Point of view** — Large centered serif statement whose emphasized verbs join a conceptual outline object.
4. **Next step** — Monumental destination link between hairlines.
5. **Utilities** — Compact contact, policy, social and newsletter footer.

**Transfer:** Keep one vivid object as the entry point and use the editorial statement to explain why the product matters.

### Institutional trust story

1. **Promise** — Huge two-line serif title on mint with teal ink, followed by a right-half introduction.
2. **Context and proof** — Documentary photography alternates with left-heading/right-copy explanations.
3. **Detailed rationale** — Unboxed three-column principles and short priority lists.
4. **Objection handling** — Ruled FAQ rows with arrows.
5. **Utilities** — Theme-colored compact footer without a separate large closing call.

**Transfer:** Use this quieter explanatory branch for trust, methodology or commitments supported by real proof.

### Portfolio or proof library

1. **Demonstration** — Large reel on a charcoal canvas.
2. **Selection** — Ruled category filter with superscript counts.
3. **Proof** — Two-column isolated-artwork exhibits and load-more action.
4. **Breadth** — Large destination link followed by a four-column alphabetical name index.
5. **Closing call** — Two-line monumental invitation and compact pale-gold footer.

**Transfer:** Combine a few expressive artifacts with a dense text index that demonstrates range.

### Capabilities and process narrative

1. **Promise** — Enormous fitted serif poster on cream with coral ink and tiny factual side annotations.
2. **Positioning** — 30px right-half introduction and an outline-object interlude.
3. **Capability chapters** — Hairline numerals, heavy two-line titles and layered captioned prints.
4. **Method** — Alternating giant verbs and line-drawn objects.
5. **Human proof** — Horizontal oversized headings with candid photographic prints and playful captions.
6. **Closing call** — Two-line monumental invitation above the coral utility footer.

**Transfer:** Use this more theatrical variant for a product with several deep capabilities and a human story; the chapter count is content-led.

## Writing

Confident craft language with a warm, mischievous streak. Technical competence is made approachable through physical metaphors, short candid asides and grounded explanations rather than corporate distance.

**Do not copy:** Do not reuse EPIC's identity, castle, custom emblems, slogans, client names, project artwork, certifications, dates, employee figures or business claims. Examples illustrate rhythm only; replace them with truthful content and original assets.

- **Addressing the reader:** Use we for the maker and you or your for the reader. Explain benefits as a relationship between the two, not impersonal category leadership.
- **Rhythm:** Featured titles are terse; editorial headings can be questions. Prose often pairs a plain claim with a longer explanation, while captions allow one light joke. Tiny labels and actions remain direct and functional.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Featured title | Short evocative noun phrase. | 2–4 words | “AVD revival” |
| Poster promise | Active physical metaphor for technical work. | 4–7 words | “We Breathe Life into Pixels” |
| Explanatory heading | Ask the reader's obvious question plainly. | 4–9 words | “Why become a B Corp?” |
| Supporting prose | A technical idea introduced with a playful comparison. | 1–3 sentences | “We haven’t cracked the Universe’s code yet, but we do have a PhD in pixel behavior. Suffice to say, we’re like dolphins mapping the digital ocean.” |
| Action | Direct verb plus object; no inflated promise. | 2–5 words | “Visit project”<br>“Start a”<br>“Load more” |
| Caption | Candid observation with gentle self-deprecation. | 5–12 words | “Nicolas faking a deep expertise in wine making” |

**Words and phrasing to use:** build; imagine; story; experience; tools; craft; your goals; real-world outcomes

**Avoid:** best-in-class solutions; synergy; disruptive ecosystem; unmatched excellence; frictionless transformation

**Rules:**

- Anchor technical promises in concrete outputs and actual working practices.
- Keep humor in captions or an occasional aside; explanations should still answer the question.
- Use selective bold words to help readers scan long prose, not a bold sentence in every paragraph.
- Treat micro-labels as editorial signposts, not miniature sales pitches.

## Do's and Don'ts

### Do

- Keep the default page furniture grey and near-black, with vivid color inside the main subject.
- Use 80px heavy serif titles beside 10px widely tracked labels to retain the extreme scale contrast.
- Keep the main desktop content width at 1200px and gallery gutters at 30px.
- Use 1px outlines and 30px radii for the small primary actions.
- Give the conceptual object its own broad breathing room and pair it with a short bold serif phrase.
- Preserve the 10px paper border and hard 10px offset shadow in the print theme.
- Keep the footer top pause at 80px and its social controls at 36px.
- Allow one page theme to recolor type, dividers, buttons and footer as a complete system.

### Don't

- Do not apply negative tracking to every serif heading; normal tracking is part of its angular character.
- Do not convert the small outline buttons into tall filled conversion slabs.
- Do not scatter coral, teal and pale gold together across a single ordinary page.
- Do not use diffuse elevated-card shadows on the print collages; their shadows have no blur.
- Do not replace the unboxed institutional text columns with rounded feature cards.
- Do not remove the little captions from the print figures or enlarge them to body size.
- Do not give the utility footer a contrasting dark slab on the default grey page.
- Do not use a uniformly rounded treatment: gallery exhibits are 8px, video 10px, but photographic prints and documentary images have square corners.

## Motion and responsive

### Motion

**Observed:**

- Actions declare background-color transitions of 0.2s; social controls declare background-color and fill transitions of 0.15s.
- Gallery filters declare border-color 0.35s ease-in-out; images declare opacity 0.25s.
- The centered statement has a scroll-linked phase where emphasized words remain and join the outlined object. The expressive photographic story advances horizontally during vertical page travel.

**Transfer:**

- Let the conceptual transition connect the page's key verbs to its object rather than adding unrelated entrance effects.
- If using the horizontal photographic story, keep each heading paired with its own prose and images throughout the travel.

**Unknown:**

- Exact scroll mapping, durations and easing of the conceptual scenes and horizontal gallery are not established.
- Expanded menu and FAQ motion are not established.

### Responsive

**Observed:**

- Styles contain width breakpoints including 480px, 768px, 960px, 1024px, 1200px, 1280px, 1360px, 1440px and 1600px.

**Transfer:**

- On narrow screens, preserve the hierarchy by placing the object above the left-aligned featured title and moving the editorial rail below the actions.
- Stack institutional heading and prose columns; reduce the gallery to one exhibit per row while keeping captions and artwork together.
- Keep poster lines as deliberately composed groups rather than shrinking an entire desktop poster to illegibility.

**Unknown:**

- Exact mobile typography, padding and navigation transformations are not established. These narrow-screen arrangements are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
