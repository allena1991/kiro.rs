# savor.it — sensory science in motion

## Overview

A cinematic, tactile style that makes technical invention feel human and desirable. Warm cream and deep oxblood frame sweeping photographic passages, with tall, delicate condensed serifs balanced by unassuming grotesk text and occasional technical monospace. It suits material innovation, crafted products and ambitious consumer brands, with sparse editorial layouts rather than dense feature cards.

### Essentials

- Headlines behave like expressive lettering, not interface titles: light condensed serif, 120px/0.9 with -0.01em tracking for major headings; the opening enlarges this to a two-line word composition about 840px wide.
- The first impression is a film still with a promise laid over it: a 900px-tall full-bleed scene, 40px side gutters, headline low on the left and 22px support plus a single action low on the right. Use a richly lit close-up photograph when film is unavailable.
- Actions are small verbal bridges: 63px-tall rectangles with 5px corners and 20px 42px padding, splitting a two-part label with a 35px × 1px rule instead of an arrow.
- Color belongs to materials, not a rainbow of UI panels: cream #fff9eb and oxblood #370808 govern editorial space, beige #f0e7d7 grounds the ending, while full-screen imagery carries amber, forest green and ocean blue. Butter yellow #f8e47d is reserved for the expanded menu.
- A fine wandering line makes the story continuous: cream 1px paths curve between short sans-serif phrases and small rectangular picture inserts over immersive imagery. Include this device even when the narrative is brief; a static SVG path is the minimum version.
- Pictures form a meandering ribbon rather than a card grid: square-edged close-ups alternate portrait and landscape formats, staggered through cream space. Pair this with a broad elliptical cream edge where editorial space meets an immersive scene.
- The ending is a typographic landmark: a full-width beige footer, small navigation on the left, a 28px/1.25 invitation on the right, and an enormous oxblood wordmark spanning almost the entire 1360px content width. Set the new identity as oversized expressive lettering if it has no drawn wordmark.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Oxblood | `#370808` | `--color-ink` | text, action, border | Main text, identity artwork and dark conversion buttons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#fff9eb` | `--color-canvas` | background, text, border | Default editorial canvas and reversed lettering and fine paths on dark imagery. |
| Soft beige | `#f0e7d7` | `--color-sand` | surface, text, action | Footer band and light buttons; reversed labels on dark buttons. |
| Media black | `#000000` | `--color-black` | background | Backing behind full-screen media and dark storytelling chapters; not the default editorial text color. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| expanded navigation and text selection | Butter yellow | `#f8e47d` | `--color-menu` | background | Full-screen expanded navigation and selection lettering. |
| question-and-answer sections | Cream-tinted hairline | `#ebe1d4` | `--color-rule` | border | Visible result of 10% oxblood over cream; FAQ dividers use rgba(55,8,8,0.1). |

## Typography

- **Roslindale Display Condensed** — Expressive headlines, editorial statements and large sectional titles. Tall narrow high-contrast serif with fine hairlines, sculptural terminals and very light display weight. If unavailable, use **Instrument Serif**. Use regular with tightened tracking; preserve narrow proportions and tall line shapes. Font stack: "Roslindale Display Condensed", "Instrument Serif", Georgia, "Times New Roman", serif.
- **Suisse Intl** — Navigation, body, buttons, invitations and names. Neutral contemporary grotesk, almost entirely regular weight; it supports rather than competes with the serif. If unavailable, use **Inter**. Use 400 and retain the subtle negative tracking. Font stack: "Suisse Intl", "Inter", helvetica, arial, sans-serif.
- **Suisse Intl Mono** (only for technical chapters and documentary credits) — Small uppercase chapter indicators and contextual labels. Light, widely tracked monospace gives the story an annotated scientific register. If unavailable, use **IBM Plex Mono**. Use 300 with 0.1em tracking. Font stack: "Suisse Intl Mono", "IBM Plex Mono", "SF Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| hero-lettering | Roslindale Display Condensed | 300 | 180px | 0.9 | -0.01em | size 12.5vw | Oversized two-line opening promise; fit its narrow letterforms inside an 840px-wide composition at desktop. |
| display | Roslindale Display Condensed | 300 | 120px | 0.9 | -0.01em | size min(4.42817rem + 5.25822vw, 12rem), line height min(4.8507rem + 4.13146vw, 10.8rem) | Centered major section headings and the base character of expressive editorial lettering. |
| invitation | Suisse Intl | 400 | 28px | 1.25 | -0.01em | fixed | Newsletter invitation, constrained to 504px. |
| support | Suisse Intl | 400 | 22px | 1.35 | -0.01em | size min(1.65915rem + 0.375587vw, 2.2rem), line height min(2.23986rem + 0.507042vw, 2.97rem) | Hero support, short annotations, names and accordion questions. |
| body | Suisse Intl | 400 | 18px | 1.45 | -0.01em | size min(1.52958rem + 0.187793vw, 1.8rem), line height min(2.21789rem + 0.2723vw, 2.61rem) | Editorial support paragraphs, desktop navigation and compact explanatory copy. |
| action | Suisse Intl | 400 | 16px | 1.45 | normal | size min(1.32958rem + 0.187793vw, 1.6rem), line height min(1.92789rem + 0.2723vw, 2.32rem) | Button labels and secondary controls. |
| footer-link | Suisse Intl | 400 | 14px | 1.25 | normal | size min(1.12958rem + 0.187793vw, 1.4rem) | Small footer navigation and contact details. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| long-form explanations and documentary stories | statement | Roslindale Display Condensed | 300 | 44px | 1.2 | -0.01em | fixed | Centered editorial statements and testimonial passages. |
| expanded navigation | menu-link | Suisse Intl | 400 | 40px | 1.25 | normal | fixed | Primary links in the expanded yellow menu. |
| people and culture pages | credit-role | Roslindale Display Condensed | 400 italic | 24px | 1.2 | 0.04em | size min(1.85915rem + 0.375587vw, 2.4rem) | Parenthesized job titles beside regular sans-serif names. |
| technical chapters | chapter-number | Suisse Intl Mono | 300 | 13px | 1 | 0.1em, uppercase | size min(1.02958rem + 0.187793vw, 1.3rem) | Small outlined progress fractions. |
| technical chapters | chapter-label | Suisse Intl Mono | 300 | 13px | 1.2 | 0.1em, uppercase | size min(1.02958rem + 0.187793vw, 1.3rem) | Technical chapter descriptor below the fraction. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display and body both tighten by -0.01em; the contrast comes from construction and scale, not heavy weights.
- Keep serif display light at 300 and supporting grotesk at 400. Italic serif is a deliberately scoped credits accent, not a second default headline style.
- The fluid formulas use a 10px root rem basis at desktop. Preserve that basis or convert the rem terms equivalently; do not silently interpret the caps using a 16px root.
- Expressive headlines can divide into offset phrases while prose remains conventionally readable. Do not scatter individual letters in the final resting layout.

## Layout

**Density:** Airy and cinematic: whole-screen scenes alternate with sparse cream compositions; the small controls remain compact.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 20px | Grid gutters and support-to-action grouping. | fixed |
| 24px | Compact editorial copy-to-action gap. | fixed |
| 32px | Roomier copy-to-action separation. | fixed |
| 37px | Footer invitation-to-button gap. | fixed |
| 40px | Desktop outer gutters and hero support-to-action margin. | fixed |
| 42px | Horizontal button padding. | min(1.22535rem + 2.06573vw, 4.2rem) |
| 95px | Major heading separation and section breathing room. | min(3.41549rem + 4.22535vw, 9.5rem) |
| 100px | Footer top padding. | fixed |
| 120px | Broad editorial spacing. | fixed |
| 200px | Large cream section closing space. | fixed |

### Containers and grids

- **editorial-container**: max width 1440px · 12 columns · gap 20px · side padding 40px. Centered desktop grid. Let large media bleed outside it while lettering, support and controls align to its columns.
- **hero-copy**: max width 840px. Headline occupies roughly the left two thirds of the content area; the support column is 264px wide on the right.
- **support-column**: max width 504px. Footer invitation; other editorial paragraphs use narrower 396px measures on the far right.
- **proof-grid**: 4 columns · gap 20px. Centered unboxed logo cells, 325px × 187px at desktop; a smaller partner set centers three cells.
- **faq-column** (only for question-and-answer sections): max width 670px. Centered question stack with a large title above.
- **chapter-stage** (only for technical chapters): max width 850px. Centered square diagram and parenthetical chapter summary within a 900px scene.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 5px |
| technical chapters | chapter-fraction | 12.5px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default light editorial surface.

**CSS:** `background: #fff9eb; color: #370808`

**Observed:** Flat and uninterrupted, with no card elevation or paper-grain overlay.

**Transfer:** Let typography and real material photographs supply the texture.

#### Immersive media stage · level 0

**Use:** Full-bleed film, macro photography and dark storytelling.

**CSS:** `background: #000000; color: #fff9eb; overflow: hidden`

**Observed:** Media fills the viewport; restrained darkening keeps pale text readable without a separate text panel.

**Transfer:** Use object-fit cover imagery with natural texture and a dark translucent scrim as needed.

#### Beige closing band · level 0

**Use:** Full-width closing navigation, invitation and identity.

**CSS:** `background: #f0e7d7; color: #370808; padding-top: 100px; padding-bottom: 36px`

**Observed:** One broad flat band, not a raised conversion card.

**Transfer:** Give the closing identity its own monumental amount of space.

#### Yellow menu · level 2

**Only for:** expanded navigation

**Use:** Dedicated full-screen navigation surface.

**CSS:** `background: #f8e47d; color: #370808`

**Observed:** Yellow belongs to this navigation state rather than ordinary content panels.

**Transfer:** Keep the editorial page cream; use this high-color surface only for navigation.

## Components

### Desktop navigation

**Use:** Persistent brand and primary destinations.

**CSS:** `position: fixed; z-index: 10; height: 90px; width: 100%; padding-left: 40px; padding-right: 40px`

**Text style:** `body` — Suisse Intl 400 · 18px/1.45 · tracking -0.01em

**Observed:** Large serif identity at the left; a compact single row of links at the right with 20px gaps. Links are cream over the opening film and oxblood over light editorial content. The bar is not a boxed floating capsule.

**States:** Declared: hover link opacity 1 from 0.9; focus-visible outline black solid 0.2rem with 0.2rem offset and a cream 0.4rem outer ring.

### Light bridge button

**Use:** Editorial navigation and film entry actions.

**CSS:** `background: #f0e7d7; color: #370808; border-radius: 5px; padding: 20px 42px; min-height: 63px`

**Text style:** `action` — Suisse Intl 400 · 16px/1.45

**Observed:** Two separate words flank a short horizontal rule. The rule is 35px wide and 1px high; label length determines overall width.

**States:** Declared: hover background-color #e2d4bc; focus-visible outline black solid 0.2rem, outline-offset 0.2rem, box-shadow cream 0px 0px 0px 0.4rem.

**Transfer:** Choose a two-part action that still reads naturally as one phrase.

### Dark bridge button

**Use:** Final subscription or conversion action.

**CSS:** `background: #370808; color: #f0e7d7; border-radius: 5px; padding: 20px 42px; min-height: 63px`

**Text style:** `action` — Suisse Intl 400 · 16px/1.45

**Observed:** Same verbal bridge construction as the light version, reversed on the beige closing band; the short invitation action is 195px wide.

**States:** Declared: hover background-color #522925; focus-visible outline black solid 0.2rem, outline-offset 0.2rem, box-shadow cream 0px 0px 0px 0.4rem.

### Footer navigation

**Use:** Small destination and social columns around the monumental closing identity.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; row-gap: 9.2px; color: #370808`

**Text style:** `footer-link` — Suisse Intl 400 · 14px/1.25

**Observed:** Primary links occupy the far-left column, social links a second column. A final baseline distributes policy links left, contact centered and copyright right.

**Transfer:** Keep small links subordinate to the large identity, not inside a dense multi-column sitemap.

### Proof logo grid

**Use:** Press or partner credibility without testimonial cards.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: center; gap: 20px`

**Observed:** Unboxed, centered monochrome marks in equal cells beneath a centered display heading. Eight marks form four columns and two rows; a three-mark set remains centered.

**Transfer:** Normalize visual weight rather than forcing every logo to the same bounding-box width.

### Question row

**Only for:** question-and-answer sections

**Use:** Objection handling in a narrow centered stack.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding-top: 21px; padding-bottom: 17px; border-top: 1px solid rgba(55,8,8,0.1); color: #370808`

**Text style:** `support` — Suisse Intl 400 · 22px/1.35 · tracking -0.01em

**Observed:** Question is left aligned, with a small 16px plus at the right. Rows span 670px; body answers stay within the same measure. A small parenthesized Show more control sits centered below.

**Transfer:** Use specific questions about mechanism, authenticity and practical differences.

### Chapter fraction

**Only for:** technical chapters

**Use:** Tiny progress signal above a chapter summary.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 57px; height: 25px; border: 1px solid #fff9eb; border-radius: 12.5px; color: #fff9eb`

**Text style:** `chapter-number` — Suisse Intl Mono 300 · 13px/1 · tracking 0.1em · uppercase

**Observed:** A small capsule floats above a tracked uppercase descriptor, separated from it by 12px. It is not a large numbered feature card.

### Expanded menu link

**Only for:** expanded navigation

**Use:** Primary destination in the yellow menu.

**CSS:** `color: #370808; position: relative; overflow: hidden`

**Text style:** `menu-link` — Suisse Intl 400 · 40px/1.25

**Observed:** Left-aligned links stack with 16px gaps and 36px top space. A plain Close control sits at the upper right.

**States:** Declared: focus-visible outline black solid 0.2rem, outline-offset 0.2rem and a cream 0.4rem outer ring.

## Imagery and graphics

### Cinematic material close-ups

**Use:** Opening screen and immersive narrative passages.

**Observed:** Hands dusted with flour, glossing liquid, butter ridges, moss, bark and prepared dishes are photographed extremely close. Soft focus, natural directional light and dark surroundings make the materials tactile; warm gold, olive and blue-green come from the subject. The scene takes the full screen while copy occupies little of it.

**Transfer:** Photograph the new product being made, touched or used. For an intangible product, shoot a real human task or an evocative physical material rather than replacing the entire scene with a generic interface mockup. A carefully lit still photograph is a sufficient baseline.

### Wandering narrative line

**Use:** Signature link between phrases, diagrams and small picture inserts.

**Observed:** Thin cream curves and occasional dashed segments meander across photographic fields. Short 22px sans-serif fragments sit at endpoints; small square-edged portrait and detail images interrupt the path. It feels like an elegant annotation drawn over a living material.

**Transfer:** Use the device to connect a genuine transformation, sequence or benefit. Preserve the open field and sparse labels; the path is the story's thread.

**Build:** Overlay an SVG with viewBox 0 0 1440 900. Draw a few cubic Bézier segments with fill none, stroke #fff9eb and stroke-width 1; alternate a solid segment with stroke-dasharray 6 6. Use broad 150–400px curves and short straight links. Place two or three text nodes near endpoints and one 200px-wide rectangular image along a bend. Keep the path clear of letterforms.

### Elliptical cream transition

**Use:** Signature soft boundary between editorial space and immersive scenes.

**Observed:** The cream foreground bows into a very wide shallow oval at its lower edge, revealing photographic content underneath. It is a page-scale gesture, not a rounded card.

**Transfer:** Use this broad bowed edge when entering an immersive passage; keep ordinary pictures square.

**Build:** Layer a cream SVG shape above the media. In a 1440px-wide viewBox, use vertical sides and a lower cubic curve from the left edge to a central low point and back to the right edge, with about 350px total depth. Fill #fff9eb, omit stroke, and let the image continue underneath. Mirror the curve when revealing a scene from below.

### Staggered photo ribbon

**Use:** Product-use proof and human editorial passages.

**Observed:** Rectangular portrait and landscape photographs are staggered in height, often touching edge to edge along a loose wave. The cream field remains exposed around them. Product pictures range from hands preparing ingredients to finished objects; human pictures are candid conversations, not isolated headshots.

**Transfer:** Mix process, detail and outcome photography. Use a varied strip of sharp-edged pictures; keep the composition deliberately uneven rather than making uniform tiles.

### Monumental identity lettering

**Use:** Signature lower half of the closing band.

**Observed:** An oxblood lowercase serif wordmark fills almost the entire content width, with deep thick-thin contrast and oversized curved terminals. Small links and invitation copy above amplify its scale.

**Transfer:** Use the new identity or a custom-set short word in a highly expressive serif. The minimum acceptable version is a tightly fitted live-type wordmark, not a tiny logo centered in empty space.

**Build:** Set the identity as one unbroken SVG text line or vector outlines in #370808. Fit the viewBox to its letter shapes and render it at the 1360px content width with roughly 380px visible letter height at desktop. Leave cream-beige space around it and align its outer edges to the 40px gutters.

### Grainy credits atmosphere

**Only for:** people and culture pages

**Use:** Long team-credit passage.

**Observed:** Cream names and italic parenthesized roles sit over a muted, softly blurred gray-olive photographic field with fine grain and small prismatic light artifacts. The roster is centered rather than separated into portrait cards.

**Transfer:** Create a cinematic credits roll over a low-detail environmental photograph, keeping the text more prominent than the image.

**Build:** Blur a low-contrast environment photo, darken it with rgba(0,0,0,0.2), and overlay monochrome SVG feTurbulence noise at low opacity. Keep highlights diffuse and the center sufficiently uniform for cream text; exact photographic hues are not essential.

### Icons

**Observed:** Iconography is extremely sparse: a 16px oxblood plus marks accordion rows, a downward arrow appears in discovery prompts, and hairlines replace most button icons.

**Transfer:** Prefer typographic arrows, plus/minus and fine rules to a general-purpose icon library. Do not add decorative badges to every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Cinematic promise opening

**Observed:** A 900px full-screen material film sits on Immersive media stage, darkened enough for cream lettering. Desktop navigation floats above it with the identity at left and small links at right. The lower-left promise is a two-line condensed serif composition approximately 840px wide, with 180px lettering and tightly stacked lines; it spans about three fifths of the viewport. A 264px support column sits low on the right, using support text and one Light bridge button below a 40px gap. The scene, complete headline, short support and action all fit within the first 900px. The next editorial content begins below that screen.

**Transfer:** Use one compelling human or material action as the main object, filling the background rather than sitting in a product card. A still close-up with rich light works without film. Long-form and product-story openings distribute two short headline phrases diagonally across the upper left and lower right, linked by a fine curved line, with a small discovery prompt near the lower left.

**Avoid:** Do not turn the opening into a centered SaaS headline above a small rectangular media card, and do not crowd it with multiple conversion buttons.

**Text style:** `hero-lettering` — Roslindale Display Condensed 300 · 180px/0.9 · tracking -0.01em

### Asymmetric editorial handoff

**Observed:** Cream canvas carries a large offset serif heading toward the left and center, a modest portrait material image near the middle, and body copy with a Light bridge button at the far right. The 12-column editorial-container and 20px gutters organize an apparently free composition.

**Transfer:** Use a short conceptual heading, one revealing detail image and a concise explanation. Keep the three elements unequal in scale rather than laying them out as matching cards.

**Text style:** `display` — Roslindale Display Condensed 300 · 120px/0.9 · tracking -0.01em

### Immersive annotated transformation

**Observed:** Cinematic material close-ups fill the field beneath the Wandering narrative line. Short sans-serif fragments and small pictures unfold across the scene; a broad Elliptical cream transition provides the entry or exit.

**Transfer:** Explain one meaningful transformation visually. Static layouts can present a complete path in one screen instead of requiring a long scroll.

### Photo ribbon proof

**Observed:** Staggered photo ribbon travels through a broad cream region. A short serif benefit statement can sit beside the flow, while compact supporting copy and a Light bridge button make the next step legible.

**Transfer:** Show the product's effects through a mix of making, detail and finished use. A short horizontal strip or staggered vertical sequence can carry the same device without an extended scroll.

### Centered credibility field

**Observed:** A display heading is centered above Proof logo grid, with 95px heading separation and 40px outer gutters. Logos are black and unboxed on cream.

**Transfer:** Use trusted external organizations or genuine publications; keep the region editorial rather than promotional.

**Text style:** `display` — Roslindale Display Condensed 300 · 120px/0.9 · tracking -0.01em

### Identity-led closing

**Observed:** Beige closing band begins with small navigation and social columns at left and a 504px invitation block at right. Dark bridge button sits 37px below the invitation. Monumental identity lettering dominates the lower half, followed by a fine baseline of legal, contact and copyright links. The overall band is 964px tall at desktop.

**Transfer:** Retain the small-to-huge type contrast and single warm invitation regardless of the new product's category. The identity artwork is the closing visual payoff, not an extra conversion panel.

**Text style:** `invitation` — Suisse Intl 400 · 28px/1.25 · tracking -0.01em

### Parenthetical chapter summary

**Only for:** technical explanations

**Observed:** An 850px square stage is centered within a 900px immersive scene. Chapter fraction and chapter-label sit above a 44px centered statement, with smaller sans-serif explanation beneath. Large open curved parentheses frame the message rather than enclosing it in a card.

**Transfer:** Summarize the mechanism after a visual explanation. Draw two opposing 1px cream Bézier arcs at the sides of the text area; leave top and bottom open.

**Text style:** `statement` — Roslindale Display Condensed 300 · 44px/1.2 · tracking -0.01em

### Documentary portrait chapter

**Only for:** customer films and editorial product stories

**Observed:** A full-screen close-up carries a large centered serif archetype title with small tracked credits underneath, followed by a centered 44px quote. Wandering narrative line joins excerpts, portrait inserts and outcome details; a large Play Episode call is framed by open parentheses with a tiny duration above.

**Transfer:** Give each practitioner a real point of view and one clear statement about the experience. Use an actual interview or story rather than an invented endorsement.

**Text style:** `statement` — Roslindale Display Condensed 300 · 44px/1.2 · tracking -0.01em

### Credits and questions

**Only for:** people and culture pages

**Observed:** Grainy credits atmosphere carries centered sans-serif names with italic serif parenthesized roles. A cream FAQ follows, using a centered display heading and Question row stack within 670px, then a centered partner-logo field.

**Transfer:** Use the roster treatment for a substantive group of contributors; follow human character with practical answers, not more portrait tiles.

**Text style:** `display` — Roslindale Display Condensed 300 · 120px/0.9 · tracking -0.01em

## Page flow

**Storyline:** Sensory promise → visual transformation → practical or human proof → focused credibility or answers → warm invitation and monumental identity.

### Broad brand and product landing

1. **Promise** — Full-screen tactile film and oversized lower-left promise with a supporting action.
2. **Mechanism** — Immersive material story with wandering annotations, then an asymmetric cream editorial handoff.
3. **Product proof** — Staggered close-up ribbon and a short benefit headline.
4. **Emotional payoff** — Full-bleed outcome photograph with expressive lettering.
5. **Credibility** — Centered heading and unboxed monochrome press marks.
6. **Closing call** — Beige invitation, navigation and giant wordmark.

**Transfer:** This is the default landing-page grammar: alternate immersive material passages with cream editorial relief, choosing proof appropriate to the product.

### Belief, people and trust

1. **Promise** — Two offset serif phrases over underwater material footage.
2. **Belief** — Centered serif manifesto over dark leaves, then concise company prose on cream.
3. **Human proof** — Candid photographs travel through a staggered horizontal strip.
4. **Contributors** — Centered cinematic credits with italic roles.
5. **Objection handling** — Narrow FAQ and partner marks.
6. **Closing call** — Shared identity-led beige ending.

**Transfer:** Let the belief become tangible through candid human detail and useful answers; keep the credits treatment scoped to a substantive people story.

### Long-form mechanism education

1. **Promise** — Diagonal split headline and a discovery prompt over moss.
2. **Framing** — Centered serif introduction on cream.
3. **Capability chapters** — Roman-numeral title stages over blue, green and amber natural textures, followed by thin-line annotated transformations.
4. **Explanation** — Each chapter resolves in a parenthetical statement with progress fraction and small technical label.
5. **Product proof** — Cream handoff and staggered product-use photo ribbon.
6. **Closing call** — Shared identity-led beige ending.

**Transfer:** Break a complex mechanism into a few distinct visual environments. Keep supporting technical labels small and the explanatory prose readable; scroll length need not match the length of the original story.

### Documentary use cases and practitioner endorsement

1. **Promise** — Two offset phrases over a close-up product-use scene.
2. **Practitioner stories** — Repeated full-bleed material portraits with archetype titles and compact credits.
3. **Testimonial proof** — Centered serif quotes transition into annotated fragments and small portrait or process inserts.
4. **Deep engagement** — Parenthetical episode-play calls with small durations.
5. **Closing call** — Shared beige newsletter and identity footer.

**Transfer:** Use a series of authentic practitioner stories with a distinct visual material for each. A shorter page can use one story while preserving its title, quote, line-path and film-entry treatment.

## Writing

Warm, sensory and assured, with the wonder of a discovery rather than the bravado of a launch. Technical explanations remain plainspoken and are balanced by appetizing, familiar language.

**Do not copy:** Do not reuse the Savor name or wordmark, its sustainability or chemical-equivalence claims, named partners, staff, chefs, publication logos, documentary titles or quotes. Replace all factual claims and endorsements with substantiated material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The company speaks as we; the reader is invited in through familiar experiences and occasional you. Collective future-facing language is more common than direct sales pressure.
- **Rhythm:** Short, often paired headline phrases contrast with conversational one-sentence support lines. Explanations use complete sentences and concrete causal relationships; an occasional playful phrase softens the scientific register.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Pair a familiar pleasure with a fresh origin or better outcome. | 4–7 words | “Feel good fats from scratch”<br>“Same food Better future” |
| Benefit headline | Repeat a simple adjective or noun structure for rhythm. | 4–6 words | “Real fats, real flavor” |
| Supporting line | Explain a meaningful change in one approachable sentence. | 9–18 words | “All our old favorites, just made a different way.”<br>“Pure, versatile, sustainably-made fats” |
| Action | Two plain words bridged visually by a hairline. | 2 words | “Watch Episode”<br>“Join now” |
| Invitation | Open with a warm category-related question, then describe the concrete value of staying informed. | One question and one sentence | “Hungry for more? Join our newsletter and be the first to know where and when to find us.” |
| Question | Ask the practical or skeptical question in the reader's language. | 5–12 words | “Is your fat real fat?” |

**Words and phrasing to use:** familiar pleasures; real; made a different way; craft; flavor; future; nature; look and listen; tasting is believing

**Avoid:** disruptive ecosystem; revolutionary platform; unlock exponential growth; best-in-class; hurry; limited-time offer

**Rules:**

- Lead with the felt benefit, then explain the mechanism.
- Name tangible materials, actions and outcomes instead of stacking abstract adjectives.
- Make technical claims specific and supportable; let first-person testimony sound like a person speaking.
- Use repetition and simple contrasts sparingly as memorable headline devices.
- Keep actions inviting and literal, not breathless.

## Do's and Don'ts

### Do

- Use light condensed serif headings at 120px with 0.9 line height and -0.01em tracking for major editorial landmarks.
- Keep desktop content aligned to a 12-column grid with 20px gutters and 40px page margins.
- Reserve 63px-tall, 5px-radius bridge buttons for clear actions; include the 35px hairline between words.
- Give full-bleed media enough dark tonal structure to hold cream text without a floating white panel.
- Let staggered square-edged photographs carry process and outcome proof through open cream space.
- Finish with a beige identity-led band and the strong contrast between 14px links and monumental lettering.
- Use the 44px serif statement role for sustained explanatory reading rather than scaling body prose into a giant heading.
- Keep 13px uppercase mono labels with 0.1em tracking confined to annotated technical or documentary contexts.

### Don't

- Do not replace oxblood text with neutral charcoal throughout the cream regions; the red-brown warmth is part of the identity.
- Do not give every photo 16px rounded corners, a border and shadow; imagery is unboxed and sharp-edged.
- Do not use pill buttons for ordinary actions; only the small 57px × 25px chapter fraction is capsule-shaped.
- Do not spread butter-yellow panels through ordinary landing-page sections; the yellow surface belongs to expanded navigation.
- Do not use bold sans-serif feature headings as the main display voice; serif weight 300 supplies the contrast.
- Do not convert the wandering annotation into a dense flowchart of boxed nodes and arrowheads.
- Do not present the photographic greens and golds as competing bright UI button colors.
- Do not shrink the closing identity to a standard small footer logo; its near-full-width scale is a signature payoff.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color 0.5s linear with 0.2s delay; navigation links declare opacity 0.1s linear.
- Storytelling uses sticky scenes, canvas lettering, path reveals and photo ribbons that progress through scroll.
- Other declared reveal transitions include transform 0.8s cubic-bezier(0,0,0,1) with opacity 0.3s linear, and clip-path 0.3s ease-out.

**Transfer:**

- Animate the narrative thread and material transitions rather than adding independent bounce effects to each component.
- Use a complete static word composition and visible SVG path as the baseline; keep copy and next actions legible without a long animation sequence.

**Unknown:**

- Exact scroll mapping, canvas animation sequences and playback controls.
- Whether every declared transition runs in each context.

### Responsive

**Observed:**

- A width breakpoint exists at 1024px.
- Fluid type and button-padding formulas cap at the desktop values above.

**Transfer:**

- On narrow screens, preserve the media-led opening but stack the support and action below the promise within the scene when space allows.
- Reflow staggered photo ribbons to a shorter vertical sequence while retaining mixed aspect ratios.
- Scale the closing wordmark to the available width and stack invitation and navigation without losing its dominance.

**Unknown:**

- Actual mobile layout, navigation trigger and portrait hero heights.
- Mobile scroll choreography and reduced-motion behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
