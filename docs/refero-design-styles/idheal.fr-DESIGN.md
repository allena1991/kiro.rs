# IDHEAL — civic print in motion

## Overview

An outspoken editorial style that pairs bookish serif prose with plain grotesk headings and floating, tactile navigation. White pages and fine rules carry dense information, with brick red, olive, electric blue and magenta marking different editorial territories. Documentary photography and vividly printed poster art give cultural and research-led products a public-facing, human character.

### Essentials

- The opening reads like a public statement, not a slogan above a mockup: 35px book serif at 1.08 line height spans nearly the full width, beneath floating navigation.
- Navigation looks like loose objects on paper: 57px white circles and a 57px category capsule with a colored dot, 37.5px radius and a 4px 2px 4px translucent black shadow.
- Two voices share the hierarchy: lowercase 45.9px grotesk section headings introduce 16px serif prose; monumental heading pairs use 62px medium grotesk over the same-size book serif.
- Color behaves like an editorial index: white dominates the page, black carries reading text, and brick red marks headings, dates, rules and small actions. Large saturated fields belong inside poster artwork, not section backgrounds.
- Information is divided like a printed broadsheet: 20px outer text insets, three flush columns with 1px vertical rules, and two-part full-width chapters divided by 1px horizontal rules.
- A vivid portrait-format poster is a required visual counterweight to the prose: center a flat, high-contrast graphic at 690px wide with white on both sides; when no finished artwork exists, create an original typographic poster with cut-paper shapes.
- Actions remain modest next to the text: 30px outlined lowercase pills handle navigation and conversion, while 25px accent-outline uppercase pills close detailed chapters.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brick red | `#bc5346` | `--color-accent` | text, border, action, accent | Default landing-page territory: category marker, section headings, numbered subheads, dates and outlined actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Print black | `#000000` | `--color-ink` | text, border | Main reading text, icons and current-content rules. |
| Pale edge | `#ededed` | `--color-edge` | border | Floating control outlines and soft pale shadows. |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas and floating controls; reversed action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| organization pages | Electric blue | `#005bff` | `--color-institution` | text, border, accent | Replaces brick red for organizational information and its category marker. |
| editorial portal cards | Hot magenta | `#ff00bc` | `--color-news` | text, accent | News category dots, dates and short continuation links. |
| publication catalogs | Olive | `#51633c` | `--color-research` | text, background, border, accent | Research category marker, selected category pill, dates and attribution lead-ins. |
| editorial portal cards | Grey paper | `#e5e5e5` | `--color-news-paper` | surface, border | Glossary card backing and its hover outline. |

## Typography

- **HelveticaNeueLTPro-Roman** — Headings, actions, dates and detailed chapter prose. Unadorned neo-grotesk with Roman, Light, Medium and Bold cuts. If unavailable, use **Roboto**. Use 300, 400, 500 and 700; preserve normal tracking. Font stack: "HelveticaNeueLTPro-Roman", "Roboto", Arial, sans-serif.
- **NewCenturySchlbkLTStd-Roman** — Opening statement, thematic titles and compact editorial prose. Sturdy schoolbook serif with generous counters, bracketed serifs and an approachable printed texture. If unavailable, use **Libre Baskerville**. Use regular; check line wrapping against the wider schoolbook construction. Font stack: "NewCenturySchlbkLTStd-Roman", "Libre Baskerville", Georgia, serif.
- **sans-serif** — Large category capsule label. Plain browser sans, deliberately utilitarian beside the book serif. Font stack: "sans-serif", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading-pair-sans | HelveticaNeueLTPro-Roman | 500 | 62px | 1.03 | normal | Centered first line of a major editorial heading pair. |
| heading-pair-serif | NewCenturySchlbkLTStd-Roman | 400 | 62px | 1.03 | normal | Centered thematic second line, directly below the grotesk. |
| section-heading | HelveticaNeueLTPro-Roman | 400 | 45.9px | 1.04 | normal, lowercase | Colored heading at the top of an information column. |
| category | sans-serif | 400 | 42px | 1 | normal, lowercase | Floating category capsule. |
| statement | NewCenturySchlbkLTStd-Roman | 400 | 35px | 1.08 | normal | Full-width opening statement, chapter title and thematic introduction. |
| chapter-body | HelveticaNeueLTPro-Roman | 400 | 19.9px | 1.1 | normal | Detailed chapter questions and explanations; colored subheads share this recipe. |
| action | HelveticaNeueLTPro-Roman | 400 | 19.9px | 1 | normal, lowercase | Main outline pills and sticky subsection navigation. |
| body-serif | NewCenturySchlbkLTStd-Roman | 400 | 16px | 1.1 | normal | Compact explanatory text in narrow columns. |
| chapter-date | HelveticaNeueLTPro-Roman | 400 | 16px | 1.1 | normal, uppercase | Date anchored at the bottom left of a chapter. |
| read-more | HelveticaNeueLTPro-Roman | 500 | 12px | 1.2 | normal, uppercase | Small continuation pills. |
| caption | HelveticaNeueLTPro-Roman | 400 | 12px | 1.2 | normal | Photographic credits, caption and image counter. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial portal cards | glossary-letter | HelveticaNeueLTPro-Roman | 500 | 105px | 0.8 | normal | Single oversized letter inside a glossary card. |
| publication catalogs | catalog-title | NewCenturySchlbkLTStd-Roman | 400 | 42.9px | 1.08 | normal | Publication title in a text-only tile. |
| multi-channel portals | portal-heading-sans | HelveticaNeueLTPro-Roman | 400 | 39px | 1.1 | normal | First line of the centered editorial feature heading. |
| multi-channel portals | portal-heading-serif | NewCenturySchlbkLTStd-Roman | 400 | 39px | 1.1 | normal | Second line of the centered editorial feature heading. |
| publication catalogs | catalog-credit | HelveticaNeueLTPro-Roman | 700 | 16px | 1.1 | normal, uppercase | Author attribution anchored to the bottom of a publication tile. |
| publication catalogs | catalog-date | HelveticaNeueLTPro-Roman | 300 | 12px | 1.2 | normal, uppercase | Small date above a publication title. |

**Notes:**

- Normal tracking is consistent across both families; contrast comes from type class, case and size rather than compressed lettering.
- Use the Medium cut as visual weight 500 and the Bold cut as 700. The large serif remains regular.
- The book-serif statement can be several full-width lines. Do not shrink it into a conventional small supporting paragraph.

## Layout

**Density:** Dense editorial reading areas alternate with open paper around major titles and artwork; compact controls float above both.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Inner column and catalog tile inset. |
| 15px | Paragraph separation, chapter top padding and gaps between small navigation pills. |
| 20px | Outer text inset and fixed navigation offset. |
| 30px | Section-heading-to-prose gap, poster-to-next-block gap and column bottom padding. |
| 45px | Heading pair to statement gap and archive top inset. |
| 75px | Space beneath archive title pairs before their rule. |
| 80px | Major section separation. |

### Containers and grids

- **full-width editorial**: side padding 20px. At 1440px the text spans 1400px; use the viewport rather than a narrow centered max-width.
- **ruled information columns**: 3 columns · gap 0px · side padding 10px. Three equal columns within a 1420px band; each column is about 473px with 10px inner side padding. Only the first two have a right rule.
- **chapter split**: 2 columns · gap 0px · side padding 20px. A 1400px chapter: title occupies 560px at left, explanatory list occupies 700px at right, leaving breathing room between them.
- **poster stage**: max width 690px. Portrait artwork centered in the full-width page; a 690px by 1035px image keeps its complete outline.
- **catalog grid** (only for publication catalogs): 3 columns · gap 0px. Edge-to-edge 480px-wide, approximately 669px-tall cells at desktop; rules, not gutters, divide the grid.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | text pills | 15px |
|  | category capsule | 37.5px |
|  | utility circles | 50% |
| editorial portal cards | editorial cards | 10px |
| organization pages | portraits | 30px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating navigation | `4px 2px 4px 0px rgba(0,0,0,0.2)` | Category capsule and utility circles only. |
| multi-channel portals | paper edge | `2px -1px 6px 0px #ededed` | Ticker and small editorial action cards. |

### Surfaces

#### White canvas · level 0

**Use:** Continuous light page surface.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No large tinted marketing bands or atmospheric gradients. Editorial rules and artwork carry the structure.

**Transfer:** Keep surrounding paper white even when the art is intensely colored.

#### Ruled column · level 0

**Use:** Parallel explanatory content.

**CSS:** `border-right: 1px solid #bc5346; padding: 0px 10px 30px`

**Observed:** The rule continues to the common column bottom, beyond short text. The final column has no right rule; organizational pages use electric blue instead.

**Transfer:** Let columns share a baseline without filling the short column with extra material.

#### Floating paper · level 2

**Use:** Navigation controls above scrolling text.

**CSS:** `background: #ffffff; border: 1px solid #ededed; box-shadow: 4px 2px 4px 0px rgba(0,0,0,0.2)`

**Observed:** A visible low-offset shadow makes the control look separate from the flat printed page.

**Transfer:** Reserve this elevation for navigation, not every content block.

#### Grey editorial card · level 1

**Only for:** editorial portal cards

**Use:** Compact letter-led articles.

**CSS:** `background: #e5e5e5; border: 1px solid transparent; border-radius: 10px; overflow: hidden`

**Observed:** Magenta metadata sits above a black initial and serif text.

**Transfer:** Use a short index letter or symbol to organize a topical series.

## Components

### Utility circle

**Use:** Persistent home, account, search and menu access.

**CSS:** `width: 57px; height: 57px; padding: 10.5px; background: #ffffff; border: 1px solid #ededed; border-radius: 50%; box-shadow: 4px 2px 4px 0px rgba(0,0,0,0.2)`

**Observed:** A home control sits at upper left, while account, search and menu form a fixed upper-right cluster. Icons are black except the territory-colored home.

**Transfer:** Keep the cluster compact and visibly independent of the page text.

### Category capsule

**Use:** Persistent page identity beside the home circle.

**CSS:** `height: 57px; padding: 1.5px 19.5px 1.5px 63px; background: #ffffff; color: #bc5346; border: 1px solid #ededed; border-radius: 37.5px; box-shadow: 4px 2px 4px 0px rgba(0,0,0,0.2); display: flex; align-items: center`

**Text style:** `category` — sans-serif 400 · 42px/1 · lowercase

**Observed:** A solid circular territory marker precedes the lowercase title. Width follows the label. In the catalog, the selected category reverses white text and dot onto olive.

**Transfer:** Use a concise category noun, not a promotional sentence.

### Outline action

**Use:** Primary navigation and conversion, including the sticky subsection row.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #000000; border-radius: 15px; height: 30px; padding: 6px 7.5px 2.3px; margin-right: 15px`

**Text style:** `action` — HelveticaNeueLTPro-Roman 400 · 19.9px/1 · lowercase

**Observed:** Several short pills sit in a single wrapping row underneath the category controls. Width follows text; they remain small beside the statement.

**States:** Declared: hover color #ffffff, border-color #bc5346, background #bc5346; transition 0.2s.

**Transfer:** Use direct destinations or task labels; one conversion can share the same visual weight as supporting navigation.

### Read more pill

**Use:** Continue a detailed chapter or expand an archive item.

**CSS:** `background: #ffffff; color: #bc5346; border: 1px solid #bc5346; border-radius: 15px; height: 25px; padding: 6px 7.5px 2.3px`

**Text style:** `read-more` — HelveticaNeueLTPro-Roman 500 · 12px/1.2 · uppercase

**Observed:** Placed at the far lower right of a chapter, opposite the date, or beneath an archive heading pair.

**States:** Declared: hover color #ffffff, border-color #bc5346, background #bc5346; transition 0.2s.

### Chapter row

**Use:** Explain a capability or theme with a sequence of concrete questions.

**CSS:** `border-top: 1px solid #000000; padding-top: 15px; display: flex; flex-wrap: wrap; justify-content: space-between`

**Text style:** `statement` — NewCenturySchlbkLTStd-Roman 400 · 35px/1.08

**Observed:** Left serif title faces a right-hand numbered list of colored grotesk subheads and black explanations. A date at lower left and Read more pill at lower right finish the row.

**Transfer:** Preserve the asymmetry and use real subtopics; let content determine row height.

### Archive heading row

**Use:** Close a long page with prior editions or related collections.

**CSS:** `position: relative; border-bottom: 1px solid #bc5346; padding-bottom: 75px; color: #bc5346`

**Text style:** `heading-pair-sans` — HelveticaNeueLTPro-Roman 500 · 62px/1.03

**Observed:** A centered grotesk edition line is immediately followed by a serif theme line, both in brick red. The small continuation pill sits at lower right; rows are flat, broad and separated by colored rules.

**Transfer:** Use a version, collection or period as the first line, and its editorial idea as the second.

### Publication tile

**Only for:** publication catalogs

**Use:** Link to an individual publication in a continuous grid.

**CSS:** `position: relative; border-right: 1px solid #000000; border-bottom: 1px solid #000000`

**Text style:** `catalog-title` — NewCenturySchlbkLTStd-Roman 400 · 42.9px/1.08

**Observed:** Alternate complete portrait cover art with deliberately text-only tiles. Text tiles put a small olive date at top, large serif title below and uppercase bold attribution at bottom; whole cells are linked.

**Transfer:** The text-only version is an editorial cover, not an empty image slot. Match neighboring cover proportions.

### Glossary card

**Only for:** editorial portal cards

**Use:** A compact educational article in a feed.

**CSS:** `background: #e5e5e5; border: 1px solid transparent; border-radius: 10px; overflow: hidden`

**Text style:** `glossary-letter` — HelveticaNeueLTPro-Roman 500 · 105px/0.8

**Observed:** Date, category and small magenta dot form the header; a giant initial introduces a serif definition and explanatory text. Inner padding is 10px.

**States:** Declared: hover background-color #ffffff and border 1px solid #e5e5e5; transition background-color 0.2s linear.

**Transfer:** Choose one meaningful initial per entry and keep the definition conversational.

### Bottom ticker

**Only for:** multi-channel portals

**Use:** Persistent editorial signature at the bottom edge.

**CSS:** `position: fixed; bottom: 0px; height: 30px; background: #ffffff; border: 1px solid #ededed; box-shadow: 2px -1px 6px 0px #ededed; overflow: hidden`

**Observed:** A continuous horizontal line alternates a serif institutional descriptor with a medium grotesk motto; both are 18px with 18px line height.

**Transfer:** Write an original descriptor and counterpoint, repeat them seamlessly and leave page content clear of the band.

## Imagery and graphics

### Printed thematic poster

**Use:** Required visual anchor for a marketing page, separating prose-led explanation from detailed chapters.

**Observed:** Portrait, flat-edged art centered on white paper. One treatment uses a deep blue field, roughly cut red and white hands, a golden key and angled cyan and red lettering. The artwork is forceful and screen-print-like, not photorealistic.

**Transfer:** Commission or construct a subject-specific editorial metaphor with one dominant field, two or three cut-paper forms and emphatic lettering. The minimum is an original oversized typographic poster with a simple symbolic silhouette.

**Build:** Use a 2:3 SVG viewBox. Fill the field with a strong contrasting color chosen for the artwork; layer two irregular polygon or hand-drawn path silhouettes in contrasting flat colors, no blur or shadow. Add one small linking symbol and rotate a short heavy title across the forms. Keep small edition text at the top and a tiny credit at the bottom.

### Documentary photograph

**Use:** Human proof inside explanatory columns and organizational introductions.

**Observed:** Natural-color architecture and people: inhabited balconies, residential towers and an outdoor group under cloudy skies. Rectangular, uncropped-looking frames preserve context; a 12px sans credit sits about 5px below, sometimes paired with an image counter.

**Transfer:** Show the actual people, places or use environment of the new product. Keep natural daylight and contextual detail instead of studio polish.

### Publication cover wall

**Only for:** publication catalogs

**Use:** Dominant imagery in a ruled catalog.

**Observed:** Full portrait covers nearly fill each cell with around 10px white inset. Treatments vary: red-purple photocopy collage, expressive oversized lettering, diagrammatic marks, line illustration and soft colored fields. These are separate editorial artworks, not a uniform marketing card template.

**Transfer:** Give each publication its own coherent cover while keeping scale and cell proportions consistent.

### Monumental letter architecture

**Only for:** multi-channel portals

**Use:** A signature top layer across independently framed editorial channels.

**Observed:** Huge black grotesk wordmark fragments align above four unequal white columns. Letter silhouettes occupy roughly the upper 300px of the 900px view, with small colored category capsules directly beneath; fine black vertical rules run through the full frame.

**Transfer:** Construct an original short product word or meaningful initial sequence across channels. If the name is long, use a short original editorial word instead of squeezing a long logo.

**Build:** Create an SVG wordmark from a plain neo-grotesk face, convert lettering to paths and scale its visible cap height to about 300px at 1440px width. Split the word into four logical fragments, fitted above unequal channel widths; leave 20px inner whitespace and align all fragments on one baseline. Use pure black on white, without outlines or effects.

### Icons

**Observed:** Simple 34px SVG pictograms inside 57px circles: filled person and house silhouettes, open magnifying glass and three horizontal menu bars. Black for utilities; category color for the house.

**Transfer:** Use plain geometric symbols with generous negative space; do not replace these with a thin, detailed icon library.

## Section recipes

How recurring sections are built.

### First screen: Editorial statement opening

**Observed:** White paper is the back layer. A fixed home circle and brick-red Category capsule float 20px from the upper-left edge; three Utility circles float at upper right. A sticky row of Outline actions sits below, around 93px from the top. The main statement begins around 139px, set in the 35px serif recipe across almost the entire 1400px text width. It fills about six lines rather than forming a short display slogan. A small accent support credit and compact certification mark follow. After open paper, the three-column explanatory band begins around 564px: lowercase red headings and dense serif prose are already visible before the 900px fold, while the central documentary photograph continues below it. There is no giant background media behind the text.

**Transfer:** Lead with a substantive description of what the product does, who acts through it and why it matters. Place real endorsement or qualification information below only when available, keeping the open space before the information columns. The equivalent main object is editorial text, not a device rendering. Organization pages use a two-thirds statement and photograph beside a narrow factual column; catalog pages use a shorter full-width statement above cover art. Multi-channel portals use the Monumental letter architecture instead.

**Avoid:** Do not turn the opening into a centered two-line startup slogan, a full-bleed video hero or a colored rectangle with an oversized filled CTA.

**Text style:** `statement` — NewCenturySchlbkLTStd-Roman 400 · 35px/1.08

### Three ruled explanations

**Observed:** Ruled column surface creates three equal, flush information columns. Each starts with section-heading, followed 30px later by body-serif. A contextual photograph can sit beneath one column's prose; a compact outline caption-link follows it.

**Transfer:** Explain three complementary facets rather than three generic benefits. Let the columns be unequal in content density but equal in width.

**Text style:** `section-heading` — HelveticaNeueLTPro-Roman 400 · 45.9px/1.04 · lowercase

### Editorial title and poster stage

**Observed:** A centered brick-red heading-pair-sans sits directly over a black heading-pair-serif. After 45px comes a full-width statement; the Printed thematic poster follows with 30px separation and ample white on both sides.

**Transfer:** Use a collection label and a compelling thematic name, then explain the theme before showing its original poster. This device can occur wherever the page needs a shift from facts to an editorial idea.

**Text style:** `heading-pair-serif` — NewCenturySchlbkLTStd-Roman 400 · 62px/1.03

### Detailed chapter sequence

**Observed:** Chapter row repeats with a black top rule and 15px inset. The left title is large book serif; the right list alternates accent numbered subheads and black chapter-body text, with 15px paragraph spacing. Date and Read more pill finish the lower edge.

**Transfer:** Use this for capabilities, curricula, research questions or a structured product argument. Keep the list editorial rather than turning it into a feature-card grid.

**Text style:** `chapter-body` — HelveticaNeueLTPro-Roman 400 · 19.9px/1.1

### Archive closing register

**Observed:** A red archive label introduces broad Archive heading rows. Each pairs an edition label with its serif theme, adds a small continuation pill, and ends with a red rule. The final rule and white page margin are the ending; there is no dark promotional footer.

**Transfer:** Close with useful related material, previous editions or deeper reading. The generous paired typography can also frame a final editorial invitation without inventing a multi-column site footer.

**Text style:** `heading-pair-serif` — NewCenturySchlbkLTStd-Roman 400 · 62px/1.03

### Organization directory

**Only for:** organization pages

**Observed:** Three ruled columns use electric-blue headings and rules. Names are compact medium grotesk, roles and biographies are book serif; small 60px round portraits sit beside staff labels. Partners and an advisory directory sit in the other columns. Contact lines remain in the first column near the bottom, followed by a small unboxed design-credit line at the page end.

**Transfer:** Use a restrained people-and-credentials directory, keeping contact information part of the editorial column rather than a giant separate callout.

### Catalog as exhibition wall

**Only for:** publication catalogs

**Observed:** A full-width short serif introduction leads immediately to an edge-to-edge three-column cover grid. Publication tiles mix full artwork and authored text-only covers. The final row finishes on the grid baseline, then white margin; no conversion band is appended.

**Transfer:** Maintain the continuous ruled wall and alternate media with editorial text only when there is real title and attribution content.

**Text style:** `catalog-title` — NewCenturySchlbkLTStd-Roman 400 · 42.9px/1.08

### Portal channels and ticker

**Only for:** multi-channel portals

**Observed:** Monumental letter architecture spans four unequal channels. Beneath colored category chips are photography, centered title pairs with actions, publication covers and Glossary cards. The Bottom ticker runs over the lower edge of the 900px stage; channel content continues within the composition rather than into a conventional page ending.

**Transfer:** Use only when multiple editorial destinations deserve simultaneous visibility. Adapt channel widths to the density of each destination; keep the word-art, categorized columns and moving editorial strip as one coherent device.

**Text style:** `portal-heading-serif` — NewCenturySchlbkLTStd-Roman 400 · 39px/1.1

## Page flow

**Storyline:** substantive premise → complementary explanations → editorial theme and visual metaphor → detailed questions → useful onward reading

### A flagship informational landing page

1. **Premise** — A full-width serif statement under floating category and action navigation.
2. **Explanation** — Three ruled columns describe complementary ways the offering works.
3. **Editorial promise** — A large grotesk/serif heading pair and introductory argument frame an original portrait poster.
4. **Capability chapters** — Repeated two-part rows develop concrete questions with dates and continuation pills.
5. **Onward reading** — Broad accent-colored archive heading pairs end on a final fine rule.

**Transfer:** Borrow the argument-led progression for a product with depth; use as many chapters as the content warrants.

### An organizational credibility page

1. **Positioning** — Two-thirds serif statement and architectural photograph beside a compact ambitions and projects column.
2. **Human and institutional proof** — A three-column directory combines staff biographies, partners and advisors.
3. **Contact** — Named contacts and email addresses end the first column; a small credit line closes the canvas.

**Transfer:** Adapt to people, collaborators and practical contacts instead of adding generic testimonials.

### A browseable publication catalog

1. **Orientation** — A short serif statement defines the breadth of the collection.
2. **Exploration** — A long ruled three-column wall alternates finished covers and large-title text covers.
3. **Completion** — Final authored text tiles terminate the grid with a fine bottom edge and white margin.

**Transfer:** Let the work itself do the selling; preserve full cover art and visible authorship.

### An editorial gateway to multiple channels

1. **Identity** — Oversized wordmark fragments crown four ruled channels.
2. **Choice** — Color-coded category chips introduce distinct content streams.
3. **Preview** — Documentary image, title pair with two pills, publication cover and glossary article provide different ways in.
4. **Persistent signature** — A bottom ticker alternates descriptive and motto-like text; the composition has no conventional scroll-end footer.

**Transfer:** Use this as a scoped portal rather than the default single-product landing structure.

## Writing

Public-minded, knowledgeable and willing to question received ideas. Serious explanations coexist with playful chapter titles and everyday metaphors; authority comes from specific mechanisms, named expertise and useful questions.

**Do not copy:** Do not reuse the brand name, wordmark, slogans, publication artwork, personal names, addresses, research claims, dates, accreditation marks, program names or source-specific numbers as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly collective nous and notre, or an impersonal explanatory voice. Questions invite readers to think together rather than commanding them to buy.
- **Rhythm:** Long explanatory opening sentences establish scope; short thematic titles and wry questions interrupt dense prose. Actions are brief lowercase destinations, while dates and small continuation controls use capitals.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Describe a real activity, its participants and its public consequence in connected sentences. | A substantive paragraph, often several full-width lines. | “Un voyage d’études est organisé pour comparer, s'inspirer, apprendre.” |
| Thematic title | A compact phrase with a double meaning or a familiar expression redirected toward the subject. | 2–8 words. | “ÉLIRE DOMICILE”<br>“Du nouveau avec du vieux” |
| Chapter question | Name a real tension, then ask an accessible question without promising an effortless solution. | A short title or a few explanatory sentences. | “Session 8 - C'est qui le patron ?”<br>“1. La jeunesse est-elle un business ?” |
| Action | Destination noun or plain continuation label, not inflated sales language. | 1–4 words. | “inscriptions”<br>“lire +” |
| Image caption | Describe the place or object, then credit makers and photographer. | One compact factual line or short wrap. | “53 logements et espaces partagés à Lille. Sophie Delhay Architecte pour SIA Habitat. Photo : Julien Lanoo.” |

**Words and phrasing to use:** comprendre, comparer, apprendre; questions phrased in everyday language; concrete mechanisms and actors; collective verbs and inclusive forms; familiar idioms used with a light twist

**Avoid:** revolutionary or game-changing claims; frictionless and effortless promises; vague innovation superlatives; aggressive urgency; empty benefit triplets

**Rules:**

- Give the reader an argument before a conversion request.
- Pair a witty title with a factual explanation, not another joke.
- Use visible authorship and dates where editorial content benefits from them.
- Use inclusive French forms consistently when writing in French; keep the equivalent collective tone in other languages.

## Do's and Don'ts

### Do

- Keep the opening statement at 35px with 1.08 line height and normal tracking.
- Pair 62px grotesk and serif lines directly, without a decorative divider between them.
- Use 1px rules to structure flush columns and chapter rows.
- Keep floating navigation at 57px high with the visible low-offset shadow.
- Keep action pills compact: 30px main actions and 25px continuation controls.
- Center complete portrait artwork at 690px wide on the desktop paper canvas.
- Retain 12px sans photographic credits and counters beneath documentary images.
- Use brick red for the default text-and-rule territory, with blue and olive limited to their own page types.

### Don't

- Do not make all text Helvetica-like; the 16px and 35px book serif is essential.
- Do not apply negative tracking to the heading system; its tracking is normal.
- Do not give flat editorial columns 16px rounded corners or drop shadows.
- Do not stretch poster covers into landscape thumbnails or clip away their printed titles.
- Do not spread all four accent colors through a single landing-page section.
- Do not upgrade the modest outlined actions into 56px solid black conversion buttons.
- Do not replace the ruled information architecture with a spaced dashboard of identical cards.
- Do not use a charcoal footer to conclude pages that otherwise end on white paper and fine rules.

## Motion and responsive

### Motion

**Observed:**

- Continuation and subsection actions declare 0.2s transitions; glossary cards declare background-color 0.2s linear.
- The portal ticker declares opacity 0.3s ease-in-out and its text has a repeating linear translation animation.
- Other declared surface transitions include transform 0.2s linear.

**Transfer:**

- Keep the color-fill response of the small outlined pills.
- For a portal ticker, repeat the editorial phrase continuously within the narrow bottom band rather than making the entire page move.

**Unknown:**

- Ticker cycle duration and precise channel-expansion interaction timing are not established.

### Responsive

**Observed:**

- Stylesheets declare width breakpoints at 320px, 576px, 768px, 1024px, 1200px, 1440px, 1800px and 2200px.
- Information columns carry full-width and large-screen one-third-width classes.

**Transfer:**

- On narrow screens, stack the ruled explanations in reading order and keep category navigation from colliding with the utility cluster.
- Scale the portrait poster to the available width without changing its ratio or trimming its title.
- Let the two-part chapters become title-then-list while keeping the date and continuation action at the chapter ending.

**Unknown:**

- Exact mobile type sizes, navigation transformations and portal channel behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
