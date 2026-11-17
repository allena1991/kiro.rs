# Flying Papers — oversized poster play

## Overview

A playful, full-color poster language with enormous, tightly stacked grotesk lettering and small utilitarian monospace details. Butter yellow, dusty violet, salmon pink and brick red make broad color fields rather than restrained accents, with forest green providing a distinctive farewell. It suits expressive consumer products and participation-led campaigns, pairing sparse copy with oversized product objects and illustration.

### Essentials

- Headlines behave like solid poster shapes: ObviouslyVariable at 186px, weight 900, line height 0.8 and normal tracking; short words stack into a nearly full-width composition.
- The opening is a typographic stage, not a split-column sales pitch: a centered 16px eyebrow above three 186px lines, a layered object field and a centered 40px support paragraph within a 793px opening.
- Color is the architecture: use butter yellow #f9cc73 with violet #61609a for the default landing treatment, covering whole sections; reserve forest green #375027 for the closing band and off-white #f9f5f2 for controls and utility text.
- Buttons are little mechanical pop-outs: 43px faces with 6px corners, 16px uppercase bold labels and a separate offset backing; category controls alone use fully rounded ends.
- Images occupy stages rather than framed cards: large layered media in the opening and 540px square product stages in a two-column catalog, with captions directly on the section color. Use original isolated product art or a simple dimensional object when no equivalent media exists.
- Every new page carries a monumental word composition and a generous farewell: a 100px uppercase closing line on a 496px forest-green footer, followed by compact navigation and utility controls. The word composition may serve a promise, a benefit or a closing thought.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty violet | `#61609a` | `--color-ink` | text, background, action | Default text and button face on the yellow canvas; full-page catalog ground with pink or off-white lettering. |
| Brick red | `#c94245` | `--color-red` | text, background | Expressive display ink on pink; full promotional bands in the catalog. |
| Butter yellow | `#f9cc73` | `--color-canvas` | background, surface, accent | Default landing canvas; also promotional text and action faces in contrasting color chapters. |
| Salmon pink | `#f8c1ba` | `--color-pink` | background, text, accent | Large expressive text on violet and the farewell line on green; alternate warm editorial canvas. |
| Forest green | `#375027` | `--color-footer` | background | The full-width closing footer. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Utility black | `#000000` | `--color-black` | text | Small navigation labels on off-white. |
| Near-black | `#1a1a1a` | `--color-dark` | text, surface, accent | Mechanical backings, solid offset shadows and printed dot texture. |
| Warm off-white | `#f9f5f2` | `--color-paper` | text, surface, action | Button labels on violet, utility controls, catalog captions and footer links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalog add-on badges | Bubblegum pink | `#ed87b8` | `--color-sticker` | surface | Small oval add-on badges, not general page backgrounds. |

## Typography

- **ObviouslyVariable** — Poster headlines, section titles, compact footer links and eyebrows. Very heavy, broad grotesk with exuberant mass; lighter cuts supply small labels. If unavailable, use **Archivo Black**. Use its broad heavy shapes for display; use Archivo for the lighter eyebrow weight. Font stack: "ObviouslyVariable", "Archivo Black", sans-serif.
- **DegularDisplay** — Large supporting paragraphs and bold action labels. Compact soft grotesk, mixing personable forms with very tight leading. If unavailable, use **DM Sans**. Use 500–700 weights and preserve the short line heights. Font stack: "DegularDisplay", "DM Sans", sans-serif.
- **bergen_monoregular** — Navigation, prices and product names. Straightforward monospaced capitals contrast with the giant display shapes. If unavailable, use **IBM Plex Mono**. Font stack: "bergen_monoregular", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| chapter | ObviouslyVariable | 900 | 275px | 0.8 | normal, uppercase, features "calt" 0 | One- or two-word process chapter titles. |
| display | ObviouslyVariable | 900 | 186px | 0.8 | normal, uppercase, features "calt" 0 | Default centered opening headline, stacked into short lines. |
| farewell | ObviouslyVariable | 900 | 100px | 0.8 | normal, uppercase, features "calt" 0 | Monumental closing footer line. |
| body-lead | DegularDisplay | 600 | 60px | 0.85 | normal | Short, prominent explanatory paragraphs beneath chapter titles. |
| support | DegularDisplay | 600 | 40px | 0.85 | normal | Centered opening support copy. |
| footer-link | ObviouslyVariable | 800 | 20px | 1 | normal, uppercase, features "calt" 0 | Main footer destination links. |
| eyebrow | ObviouslyVariable | 350 | 16px | 0.9 | 0.05em, uppercase | Small category label above an opening or editorial heading. |
| button | DegularDisplay | 700 | 16px | 1 | 0.05em, uppercase | Pop-out button faces and category controls. |
| navigation | bergen_monoregular | 400 | 14px | 0.8 | normal, uppercase, features "calt" 0 | Compact top navigation labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company-history stories | year | ObviouslyVariable | 800 | 480px | 1 | normal, uppercase, features "calt" 0 | Enormous timeline year figures. |
| participation and help sections | faq-title | ObviouslyVariable | 800 | 320px | 0.8 | normal, uppercase, features "calt" 0 | Oversized abbreviation anchoring the question section. |
| catalog pages | catalog-display | ObviouslyVariable | 900 | 309px | 0.8 | normal, uppercase, features "calt" 0 | Two-line catalog opening title. |
| immersive brand-story sections | word-sculpture | ObviouslyVariable | 900 | 241px | 0.9 | normal, features "calt" 0 | An expressive sentence broken into individually positioned words. |
| participation and help sections | question | ObviouslyVariable | 800 | 55px | 0.8 | normal, uppercase, features "calt" 0 | Accordion question labels. |
| catalog add-on badges | badge | ObviouslyVariable | 800 | 26px | 0.8 | 0.01em, uppercase | Oval product add-on labels. |
| company-history stories | timeline-body | DegularDisplay | 500 | 25px | 0.9 | 0.02em | Compact narrative paragraph below timeline labels. |
| catalog pages | product-label | bergen_monoregular | 400 | 24px | 29px | normal, uppercase | Product names and prices on one shared baseline. |
| catalog pages | product-category | DegularDisplay | 700 | 12px | 16px | 0.15em, uppercase | Small product category labels above product names. |

**Notes:**

- Normal tracking is part of the heavy display treatment; density comes from the 0.8 line height, not aggressive negative letter spacing.
- Supporting paragraphs remain unusually large and tightly led. Keep them short enough to read as a single visual block.
- DegularDisplay-Bold is treated as visual weight 700, including the 12px category labels whose declared weight is 400. Do not use the 10px document default as a body-text recipe.

## Layout

**Density:** Airy in section rhythm, dense within the letterforms: broad empty intervals separate compact blocks of giant type.

### Spacing

**Spacing system:**

- **vertical rhythm** 10px, vertical — The main non-fluid rhythm for chapter padding and inter-block gaps.

| Value | Use |
| --- | --- |
| 10px | Tight utility-control and inline grouping gaps. |
| 20px | Eyebrow grouping, question-row vertical padding and common side insets. |
| 40px | Action separation from explanatory copy and footer group gaps. |
| 60px | Chapter-title to paragraph gap and catalog item bottom spacing. |
| 80px | Catalog opening inner vertical padding. |
| 100px | Opening headline to support separation. |
| 110px | Default opening top padding. |
| 140px | Process chapter top padding. |
| 190px | Process chapter bottom padding. |
| 220px | Question-section top padding. |

### Containers and grids

- **opening stage**: max width 1440px · side padding 0px. Full-width color field; centered type nearly spans the viewport.
- **support column**: max width 660px · side padding 20px. Centered opening support text, yielding a 620px text measure.
- **chapter column**: max width 1060px · side padding 40px. Broad left-aligned process content, inset toward the right of a narrow side rail.
- **question column**: max width 1020px · 1 column · gap 40px. Centered heading and stacked question rows.
- **catalog grid** (only for catalog pages): max width 1300px · 2 columns · gap 180px · side padding 20px. Two 540px product columns, separated by a very generous gutter.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | button faces | 6px |
|  | icon controls | 50% |
| catalog pages | category controls | 100px |
| catalog add-on badges | oval stickers | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| catalog add-on badges | sticker offset | `3px 3px 0px 0px #1a1a1a` | Crisp printed depth beneath small oval labels. |

### Surfaces

#### Yellow canvas · level 0

**Use:** Default landing-page field.

**CSS:** `background-color: #f9cc73; color: #61609a`

**Observed:** Continuous flat color carries both opening and process chapters without card boundaries.

**Transfer:** Let typography and section scale create structure rather than alternating neutral cards.

#### Forest farewell · level 0

**Use:** Shared ending.

**CSS:** `background-color: #375027; color: #f8c1ba`

**Observed:** A hard color change establishes the closing block.

**Transfer:** Retain a contrasting green ending even when the main page uses another theme.

#### Violet catalog · level 0

**Only for:** catalog pages

**Use:** Product browsing and oversized product spotlights.

**CSS:** `background-color: #61609a; color: #f9f5f2`

**Observed:** Pink display lettering and off-white captions sit directly on the same ground.

**Transfer:** Keep product stages unboxed.

#### Pink editorial field · level 0

**Only for:** immersive brand and company stories

**Use:** Long-form expressive words and history.

**CSS:** `background-color: #f8c1ba; color: #c94245`

**Observed:** Warm pink supports brick-red monumental type; the company-story ground also uses a near-identical pink.

**Transfer:** Use this pair for narrative chapters rather than blending it into the default yellow theme.

#### Printed dot backing · level 1

**Only for:** catalog promotions and pop-out action backings

**Use:** Crisp graphic texture behind a face or band.

**CSS:** `background-image: radial-gradient(#1a1a1a 30%, rgba(0,0,0,0) 30%), radial-gradient(#1a1a1a 30%, rgba(0,0,0,0) 30%); background-size: 8px 8px; background-position: 0px 0px, 20px 20px`

**Observed:** Two radial dot layers make a mechanical print texture rather than a soft shadow.

**Transfer:** Use behind a solid foreground so the texture reads as a displaced backing.

## Components

### Compact navigation

**Use:** Small top-level menu and bag controls around the identity.

**CSS:** `display: flex; justify-content: space-between; align-items: center; max-width: 345px; height: 40px; padding: 0px 15px; background-color: #f9f5f2; color: #000000`

**Text style:** `navigation` — bergen_monoregular 400 · 14px/0.8 · uppercase

**Observed:** A compact centered utility strip, not an edge-to-edge navigation bar. The identity sits between the two controls.

### Primary pop-out button

**Use:** Main conversion action after an explanatory chapter.

**CSS:** `display: flex; justify-content: center; align-items: center; background-color: #61609a; color: #f9f5f2; border-radius: 6px; padding: 10.6px 18.8px; height: 43px; box-sizing: border-box; position: relative; overflow: hidden; transition: transform 0.3s, color 1s ease-in-out, background-color 1s ease-in-out`

**Text style:** `button` — DegularDisplay 700 · 16px/1 · tracking 0.05em · uppercase

**Observed:** The foreground is a separate layer from its same-size backing. A displaced face gives a tactile pop-out construction; words use duplicated masked layers for rolling text. The promotional variant swaps to a yellow face and dark label.

**Transfer:** Size width to the action phrase; preserve the separate face and backing, not a blurred drop shadow.

### Farewell footer

**Use:** Shared final brand statement and practical destinations.

**CSS:** `background-color: #375027; padding: 40px 40px 60px 20px; display: flex; flex-direction: column; gap: 40px; overflow: hidden`

**Text style:** `farewell` — ObviouslyVariable 900 · 100px/0.8 · uppercase

**Observed:** The large pink farewell is left-aligned within a 1197px measure. Below it sit off-white destination links, social graphics, locale controls and compact legal links. Desktop block height is 496px.

**Transfer:** End with a warm sentence, not another generic conversion panel.

### Footer destination link

**Use:** Main footer destinations.

**CSS:** `color: #f9f5f2; position: relative; overflow: hidden`

**Text style:** `footer-link` — ObviouslyVariable 800 · 20px/1 · uppercase

**Observed:** Short uppercase words, grouped across the broad footer; duplicated word layers support the same rolling-label treatment as the buttons.

### Question row

**Only for:** participation and help sections

**Use:** Large, conversational objection handling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 20px; padding: 20px 0px; position: relative; overflow: hidden; color: #61609a`

**Text style:** `question` — ObviouslyVariable 800 · 55px/0.8 · uppercase

**Observed:** Full-width question on the left and a separate circular toggle on the right; rows wrap for long questions without becoming cards.

**Transfer:** Use real questions rather than feature labels.

### Circular toggle

**Only for:** participation and help sections

**Use:** Accordion expansion affordance.

**CSS:** `width: 40px; height: 40px; border-radius: 50%; background-color: #61609a; display: flex; align-items: center; justify-content: center; transform: translate(-3px, -3px); transition: transform 0.22s, color 1s ease-in-out, background-color 1s ease-in-out`

**Observed:** A foreground circle sits over a dark circular backing and contains a solid graphic icon.

### Product listing

**Only for:** catalog pages

**Use:** Browsable product with compact specifications and price.

**CSS:** `display: block; width: 540px; color: #f9f5f2`

**Text style:** `product-label` — bergen_monoregular 400 · 24px/29px · uppercase

**Observed:** A square product stage is followed by a 62px caption block with 14px top padding. A small category line sits above a baseline row with name left and price right. The whole item is linked, not enclosed in a painted card.

**Transfer:** Keep media dominant; limit the caption to category, name, short quantity and price.

### Category pill

**Only for:** catalog pages

**Use:** Browsing filters beneath the catalog title.

**CSS:** `background-color: #f9f5f2; color: #1a1a1a; border-radius: 100px; height: 43px; padding: 10.6px 26.9px 10.6px 29.4px; box-sizing: border-box`

**Text style:** `button` — DegularDisplay 700 · 16px/1 · tracking 0.05em · uppercase

**Observed:** A centered horizontal family of pop-out pills; the selected all-items control uses a pink face. Dark offset backings continue the mechanical control language.

### Oval add-on badge

**Only for:** catalog add-on badges

**Use:** Small product inclusion or extra.

**CSS:** `background-color: #ed87b8; color: #f9f5f2; border-radius: 50%; box-shadow: 3px 3px 0px 0px #1a1a1a; padding: 7.7px 11.5px 11.5px; position: absolute`

**Text style:** `badge` — ObviouslyVariable 800 · 26px/0.8 · tracking 0.01em · uppercase

**Observed:** A flattened oval placed near the lower corner of the square product stage, not above the title like a standard status chip.

## Imagery and graphics

### Layered object stage

**Use:** The main opening and large product spotlights.

**Observed:** The opening contains multiple overlapping canvas media layers around the enormous headline; the catalog also pairs full-width canvas stages with two-line product names. The object is treated as part of the typographic scene, not as a thumbnail.

**Transfer:** Use original isolated product renders or a clean dimensional proxy that can overlap the headline without hiding its meaning. Keep the section color continuous behind it; use an SVG object silhouette if a high-quality render is unavailable.

**Build:** Place the headline in a relative full-width stage and the object in a separate absolute layer across its central lines. Use transparent imagery or an SVG silhouette with a few dimensional planes in the page palette. Preserve readable outer letter shapes and avoid adding a rectangular image backing.

### Square product stages

**Only for:** catalog pages

**Use:** Repeated browseable items.

**Observed:** Product assets identify individual packages and product variants. Each is centered in a 540px square stage above the unboxed caption; several assets extend slightly beyond that nominal stage.

**Transfer:** Use consistent isolated views with a shared angle and light across variants. Keep the original product's colors distinct from the flat violet page ground; do not invent empty image cards.

### Printed offset texture

**Only for:** catalog promotions and pop-out action backings

**Use:** Graphic depth without atmospheric effects.

**Observed:** Hard black dots and offset foreground layers create a printed, playful material language.

**Transfer:** Use the Printed dot backing surface behind a solid color face; keep the texture graphic rather than noisy or distressed.

**Build:** Repeat two radial gradients with dark circles stopping at 30%, on an 8px square grid, positioned at 0px 0px and 20px 20px. Extend the backing beyond the foreground and clip it to the overall stage; offset by a few pixels to expose an edge.

### Icons

**Observed:** Utility graphics use off-white and near-black, mixed solid shapes and outlines. Footer graphics are roughly 40px tall; the locale chevron is 12px by 8px with a 3px butt-ended stroke. Question controls use a 40px circle containing a solid icon.

**Transfer:** Use bold, simple graphics that can survive at small sizes. Keep the tactile circular backing for expansion controls rather than substituting a thin outlined square.

## Section recipes

How recurring sections are built.

### First screen: Typographic object opening

**Observed:** The Yellow canvas fills a 793px opening. Compact navigation occupies the top center. A centered Eyebrow begins after 110px top padding; a three-line uppercase Display headline starts 20px below it and spans almost the full width. Its 186px letters use 0.8 leading, forming a block about 446px tall. Multiple media layers cross the central type field. A centered Support paragraph follows after 100px in a 660px container with 20px side padding. Within the first 900px, the eyebrow, headline, object stage and support are all included, and the next chapter begins below. The primary action belongs after the process explanation rather than in the opening.

**Transfer:** Use a short benefit promise broken into three dense lines with one original object layered through the words. Without product media, use a simple dimensional SVG emblem that carries the product's function. Catalog openings use the violet field, a two-line 309px title and Category pills; company-story openings use pink with brick-red stacked type and an illustration beneath.

**Avoid:** Do not turn this into a conventional left-copy/right-image hero, shrink the headline to a normal heading, or add a cluster of unrelated call-to-action buttons.

**Text style:** `display` — ObviouslyVariable 900 · 186px/0.8 · uppercase

### Process chapter

**Observed:** A broad inset column holds a Chapter title, 60px gap, then a Body-lead paragraph. Each chapter has 140px above and 190px below. The final chapter adds the Primary pop-out button after 40px.

**Transfer:** Use a short action verb for each stage of an explanation; keep the number of chapters appropriate to the new offer rather than forcing a fixed sequence.

**Text style:** `chapter` — ObviouslyVariable 900 · 275px/0.8 · uppercase

### Warm farewell

**Observed:** The Forest farewell surface ends every page. Farewell footer starts with the 100px pink uppercase line, then destination links, social graphics, locale selection and legal links, all within a 496px desktop band.

**Transfer:** Use a warm closing phrase tied to the new product's verbal world and preserve the abrupt green chapter change.

**Text style:** `farewell` — ObviouslyVariable 900 · 100px/0.8 · uppercase

### Monumental question section

**Only for:** participation and help sections

**Observed:** A centered 1020px column begins with a 320px FAQ title, followed by Question rows and Circular toggles. The section has 220px top and 160px bottom padding; the main grid gap is 40px.

**Transfer:** Give practical questions the same confidence as campaign headlines. Keep the question text short enough for a wide row.

**Text style:** `question` — ObviouslyVariable 800 · 55px/0.8 · uppercase

### Catalog with editorial interruptions

**Only for:** catalog pages

**Observed:** Product listings repeat in a two-column Catalog grid with 180px gutter. Full-width type-and-object spotlights interrupt browsing; one red promotional band uses yellow headline and button with Printed dot backing.

**Transfer:** Alternate useful browsing with a few strong product or campaign moments without framing every item as a card.

### Word composition

**Only for:** immersive brand-story sections

**Observed:** An expressive sentence is separated into individual word layers, with 241px heavy type at 0.9 leading. Smaller introductory words sit above the main sentence; individual words have transformed positions and rotations.

**Transfer:** Make a short belief or benefit feel physical. For a static implementation, retain individually arranged words and a coherent readable order rather than requiring a complex canvas.

### Timeline stage

**Only for:** company-history stories

**Observed:** A sticky stage carries 480px year figures at the top and a compact lower narrative block, with 16px eyebrow, 20px gap and 25px paragraph in a 660px text measure. Small year markers and a track support navigation.

**Transfer:** Use milestone dates or similarly meaningful numerals as artwork; keep the explanatory story much smaller than the numbers.

**Text style:** `year` — ObviouslyVariable 800 · 480px/1 · uppercase

## Page flow

**Storyline:** oversized promise → immersive product or process explanation → practical detail or invitation → monumental farewell

### Participation-led marketing landing page

1. **Promise** — Centered oversized headline, layered object media and a short benefit paragraph.
2. **Process explanation** — Large verb-led chapters with prominent supporting paragraphs.
3. **Conversion** — A single pop-out signup action after the explanation.
4. **Objection handling** — Monumental question heading and large accordion rows.
5. **Closing** — Shared green farewell and practical navigation.

**Transfer:** Use this as the default new landing-page pattern, adapting the process chapters to the offer.

### Immersive brand introduction

1. **Promise** — Huge expressive words in a full-width colored stage.
2. **Product storytelling** — Extended visual chapters separate the opening from the closing statement.
3. **Brand belief** — A sentence becomes an individually arranged word composition.
4. **Closing** — A final color field leads into the shared farewell footer.

**Transfer:** Borrow the scale and word composition; give every visual chapter concrete new content rather than reproducing long empty intervals.

### Catalog browsing with campaign energy

1. **Orientation** — Oversized title, layered product object and category pills on violet.
2. **Product discovery** — Repeated two-column square stages with category, name and price.
3. **Product spotlight** — Full-width object stages and giant two-line product titles interrupt the grid.
4. **Invitation** — A contrasting red campaign band with yellow action.
5. **Closing** — The same green farewell footer after the last products.

**Transfer:** Preserve the contrast between systematic browsing and theatrical product moments.

### Company or origin narrative

1. **Identity promise** — Three large red headline lines on pink, followed by illustration and centered support.
2. **Narrative transition** — An oversized word composition introduces the story.
3. **History** — A sticky timeline uses monumental dates, small markers and concise narrative text.
4. **Closing** — The shared green farewell ends the story.

**Transfer:** Use dates only when the new organization has a meaningful chronology; otherwise transfer the large-number stage to genuine milestones.

## Writing

Cheerful, direct and slightly mischievous, with the confidence of a printed campaign. Practical explanations are plainspoken; large headlines carry the wordplay.

**Do not copy:** Do not reuse the Flying Papers name, mascot, logos, product names, travel and smoking claims, prices, historical dates, promotion details or the source's exact slogans as new-product content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you, and use we for the people behind the product. Action labels name the next concrete step.
- **Rhythm:** One- or two-word chapter titles contrast with short stacked promises and one brief explanatory paragraph. Questions sound conversational rather than institutional.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct benefit with a playful second meaning, broken into compact lines. | 4–7 words | “Earn money while flying high” |
| Chapter title | A simple imperative verb or verb phrase. | 1–2 words | “Sign up”<br>“Promote”<br>“Earn” |
| Supporting explanation | Describe the action and outcome in one plain sentence. | 10–30 words | “Make money while promoting your favorite [Brand] products.” |
| Primary action | Verb plus the concrete destination or service. | 2–5 words | “Sign up to Refersion” |
| Question | Casual spoken question that acknowledges a real uncertainty. | 5–15 words | “Do you ship internationally?” |
| Farewell | Warm thanks using the campaign's central metaphor. | 4–7 words | “Thanks for flying with us” |

**Words and phrasing to use:** you; we; your favorite; start; sign up; earn; thanks; conversational questions

**Avoid:** enterprise transformation; best-in-class; synergy; frictionless ecosystem; dense technical qualifiers

**Rules:**

- Keep each giant title short enough to function as a shape.
- Let a clear action verb lead process chapters.
- Use one coherent metaphor across the promise and farewell, not a new pun in every paragraph.
- Separate practical instructions from playful headline language.

## Do's and Don'ts

### Do

- Keep default display at 186px with 0.8 leading and weight 900.
- Use 40px support copy in a 620px text measure for the centered opening.
- Maintain a 60px title-to-paragraph gap in process chapters.
- Construct actions with 6px faces and separate offset backings.
- Let full-color fields carry most of the page area.
- Retain a 100px pink farewell on the green closing band.
- Pair 24px mono product labels with 12px tracked category labels in catalog variants.

### Don't

- Do not use pale gray dashboard cards as the main section structure.
- Do not give every headline negative tracking; the heavy display uses normal tracking.
- Do not replace the 43px action faces with oversized capsule buttons throughout the page.
- Do not add soft ambient shadows to flat color stages; the characteristic depth is hard and offset.
- Do not set long explanatory paragraphs in the heavy uppercase display face.
- Do not introduce hairline outlines around every product item; captions sit on the shared ground.
- Do not treat the catalog's 180px gutter as a universal paragraph or navigation gap.

## Motion and responsive

### Motion

**Observed:**

- Section color transitions are declared as color 1s ease-in-out and background-color 1s ease-in-out.
- Pop-out foregrounds declare transform 0.3s; circular controls declare transform 0.22s alongside the color transitions.
- Printed dot backing declares a 4s linear infinite animation.
- Word layers use individual translations and rotations; button and link labels contain duplicated masked words.

**Transfer:**

- Preserve the layered face/backing and masked-word construction so interaction can remain graphic and tactile.
- Keep long text static and reserve individually transformed words for the monumental sentence device.

**Unknown:**

- Exact trigger states and end transforms for hover, focus-visible and active are not established.
- Scroll choreography and the behavior of the infinite dot animation are not established.

### Responsive

**Observed:**

- CSS includes width breakpoints at 768px, 1024px and 1500px; participation content also includes 375px, and history content includes 2000px.

**Transfer:**

- On narrow screens, preserve short stacked headline lines and the object/type overlap; reduce their scale together as design guidance.
- Reflow the catalog to one column and keep name and price aligned within the available width as design guidance.
- Keep footer hierarchy intact: large farewell first, practical destinations second, locale and legal last.

**Unknown:**

- Mobile type sizes, gutters, navigation expansion and actual breakpoint-specific layouts are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
