# CLOU — expansive spatial optimism

## Overview

A light, architectural editorial style with assertive geometric grotesk typography, near-white paper and black rules. Its enormous verbal statements coexist with compact explanatory columns and richly colored photography, models and technical drawings. The feeling is cosmopolitan, optimistic and culturally assured rather than sales-driven; it suits design-led products, studios and portfolios with substantial visual proof.

### Essentials

- Statements act like architecture: regular-weight Circular Std headlines use 165.6px/1.06 with -0.07em tracking at the opening, and 109.1px/1.1 with the same tracking for major claims.
- The opening is a full-width verbal promise above a photographic stage: a 76px fixed masthead, 25.2px side margins and a centered headline beginning about 116px down establish the scale. Keep the promise readable and follow it with real visual proof rather than an empty stage.
- Chapters are indexed like an exhibition: parenthesized 20.1px numbers sit on the baseline of underlined 50.4px section labels; 2px black rules turn titles and links into graphic objects.
- Actions are underlined words, not capsules: 16.8px/1.5 bold text ends in a plus sign, with a 2px underline and no filled button body.
- Color belongs to the work, not the chrome: the entire interface uses #fffffc and #000000, while rectangular photography supplies blue, red, green, wood and warm illuminated tones. There are no colored UI bands or tinted cards.
- Visual proof becomes a spatial object: include an open elliptical ribbon of closely spaced image panels, projected in perspective on the paper canvas. If physical-product photography is unavailable, use genuine interface details or process studies as the panels.
- Proof reads like an editorial ledger: underlined 31.9px labels precede 109.1px numerals, short explanations and small plus-links; the ending returns to a 2px rule and an oversized underlined navigation directory rather than a promotional banner.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, action, link | All interface lettering, rules, plus signs and monochrome identity marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Almost-white paper | `#fffffc` | `--color-canvas` | background, surface | Continuous page canvas, fixed masthead and unraised content surfaces. |

## Typography

- **Circular Std** — All Latin headings, paragraphs, navigation and captions. Geometric grotesk with circular counters, a high x-height and an approachable regular weight; large settings become dense through negative tracking. If unavailable, use **DM Sans**. Use 400 and 700; retain tight display tracking and check headline width. Font stack: "Circular Std", "DM Sans", "Noto Sans CJK SC", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| word-definition | Circular Std | 400 | 201.4px | 0.8 | -0.07em | fixed | Monumental keyword in a dictionary-like brand or concept definition. |
| display | Circular Std | 400 | 165.6px | 1.06 | -0.07em | size clamp(20px, 11.5vw, 400px) | Centered opening promise on a marketing page. |
| accordion-title | Circular Std | 400 | 134.3px | 1.15 | -0.07em | fixed | Oversized names in full-width disclosure rows. |
| statement | Circular Std | 400 | 109.1px | 1.1 | -0.07em | fixed | Major chapter claims and unadorned proof numerals. |
| section-label | Circular Std | 400 | 50.4px | 1.1 | -0.05em | fixed | Underlined chapter names, large supporting statements and featured-item titles. |
| editorial-heading | Circular Std | 400 | 50.4px | 1 | -0.05em | fixed | Compact multi-line introductory statements and article chapter headings. |
| directory-link | Circular Std | 400 | 33.6px | 1.1 | -0.03em | fixed | Footer directory links and contributor names. |
| metric-label | Circular Std | 400 | 31.9px | 1.5 | -0.03em | fixed | Underlined label directly above a proof number. |
| support | Circular Std | 400 | 25.2px | 1.1 | -0.03em | fixed | Secondary introductory explanation, narrower and smaller than a manifesto. |
| index | Circular Std | 400 | 20.1px | 1.1 | -0.01em | fixed | Parenthesized chapter numbers aligned with the larger section label. |
| body | Circular Std | 400 | 16.8px | 1.5 | -0.01em | fixed | Explanatory paragraphs and small directory labels. |
| action | Circular Std | 700 | 16.8px | 1.5 | -0.01em | fixed | Small underlined plus-sign actions. |
| navigation | Circular Std | 400 | 16.8px | 1.1 | -0.01em | fixed | Compact masthead navigation. |
| utility | Circular Std | 700 | 13.4px | 1.5 | -0.0125em | fixed | Back-to-top action and compact result labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| people and culture pages | culture-title | Circular Std | 400 | 134.3px | 1.06 | -0.07em | fixed | Full-width page title. |
| recognition indexes | recognition-title | Circular Std | 400 | 109.1px | 1.06 | -0.07em | fixed | Persistent page title above a short statement in a left rail. |
| case-study pages | case-title | Circular Std | 400 | 83.9px | 1.06 | -0.07em | fixed | Persistent left-hand case title wrapping into short lines. |
| recognition indexes | index-item-title | Circular Std | 400 | 50.4px | 1.3 | -0.05em | fixed | Project title above its photograph, paired with a small plus-link. |
| recognition lists | recognition-name | Circular Std | 400 | 33.6px | 1.5 | -0.03em | fixed | Award or external credential name in a ruled row. |
| recognition lists | recognition-category | Circular Std | 400 italic | 13.4px | 1.5 | -0.0125em | fixed | Small italic classification beneath the credential name. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Most lettering is weight 400. Reserve 700 for small actions, role labels and utility information; never make the giant claims bold.
- Tracking tightens with scale: -0.01em for body and masthead, -0.03em for directory links, -0.05em for medium headings and -0.07em for monumental titles.
- The root size follows calc(7.1px + 0.66964vw), resolving to 16.8px at 1440px. Non-jumbo rem-based type and spacing scale with that root; the opening display has its own explicit clamp.
- Sentence case and visible terminal periods give large statements an unusually direct, spoken quality.

## Layout

**Density:** Airy at chapter scale, compact within explanations: the large typographic pauses are balanced by tightly edited paragraph columns and underlined lists.

### Spacing

| Value | Use |
| --- | --- |
| 8.4px | Half a root-size step; index-to-title separation and close divider spacing. |
| 16.8px | Paragraph separation, masthead item gap and directory row spacing. |
| 25.2px | Side padding, shared grid gutters and list horizontal padding. |
| 50.4px | Media-to-heading spacing, introductory image margins and footer directory offset from its rule. |
| 75.5px | Article chapter separation and recognition/contributor chapter margins. |
| 83.9px | Chapter label-to-claim space and proof-section top padding. |
| 100.7px | Recurring major chapter margins, equivalent to six root-size steps. |
| 134.3px | Separation before the footer directory, equivalent to eight root-size steps. |

### Containers and grids

- **page-frame**: max width 1440px · side padding 25.2px. Fluid edge-to-edge desktop composition, not a narrow centered box. At 1440px the usable width is 1390px; allow the frame to grow with the viewport.
- **editorial-grid**: 24 columns · gap 25.2px. Underlying fractional layout. Large claims span about twenty columns; explanatory text begins after the left third and occupies two separated seven-column regions.
- **proof-columns**: 4 columns · gap 25.2px. Four small proof groups spread across the page with deliberate extra horizontal breathing room; each label, number, sentence and action forms one vertical unit.
- **case-rail** (only for case-study and recognition pages): max width 446px. Left title rail occupies roughly one third; a one-column offset separates it from a fifteen-column scrolling article with about 859px of usable media width.
- **portrait-grid** (only for people and culture pages): 7 columns · gap 25.2px. Dense staff portrait wall following a much more open leadership layout; media tiles are about 174px wide.

## Corner radius

| Element | Radius |
| --- | --- |
| Content and actions | 0px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous ground for words and media.

**CSS:** `background: #fffffc; color: #000000`

**Observed:** No alternating neutral panels, drop shadows or elevated cards separate the editorial content.

**Transfer:** Create hierarchy with scale, offsets and rules, keeping the same paper surface throughout.

#### Ruled chapter · level 0

**Use:** Recognition summaries and major proof sections.

**CSS:** `background: #fffffc; border-top: 2px solid #000000; padding-top: 83.9px`

**Observed:** The rule stretches across the usable page width; the content continues on the same ground.

**Transfer:** Use the line as a clear editorial reset, not a container border around every block.

#### Technical plate · level 0

**Only for:** case-study pages

**Use:** Plans and selected technical drawings.

**CSS:** `border: 2px solid #000000; border-radius: 0px`

**Observed:** Rectangular drawing sheets sit at article width. Photographs generally remain unframed.

**Transfer:** Frame technical detail that benefits from a sheet-like boundary, rather than treating every image as a card.

## Components

### Fixed masthead

**Use:** Persistent site orientation.

**CSS:** `position: fixed; top: 0px; height: 76px; padding: 0px 25.2px; background: #fffffc; display: flex; align-items: center; justify-content: space-between; z-index: 50`

**Text style:** `navigation` — Circular Std 400 · 16.8px/1.1 · tracking -0.01em

**Observed:** A compact black identity mark anchors the left, followed by a few short links; the language switch sits alone at the far right. The active information link is underlined.

**Transfer:** Use the new identity at a similarly compact scale and keep the navigation sparse.

### Plus link

**Use:** Primary and contextual navigation to deeper content.

**CSS:** `display: inline-block; position: relative; padding: 0px 1.7px 1.7px; border-bottom: 2px solid #000000; color: #000000; overflow: hidden; border-radius: 0px`

**Text style:** `action` — Circular Std 700 · 16.8px/1.5 · tracking -0.01em

**Observed:** Text ends with a literal plus. The underline hugs the wording, with no surrounding filled button; repeated labels support a clipped text treatment rather than repeated visible copy.

**Transfer:** Use one concise destination-specific action, including for the main conversion.

### Indexed chapter label

**Use:** Exhibition-like navigation through the narrative.

**CSS:** `display: inline-flex; align-items: baseline; padding-right: 2px; overflow: hidden`

**Text style:** `section-label` — Circular Std 400 · 50.4px/1.1 · tracking -0.05em

**Observed:** The index uses the index recipe with an 8.4px gap. Only the larger title is underlined by a 2px rule, not the number.

**Transfer:** Give sections short topic names and preserve the contrast between the tiny number and the large label.

### Monumental disclosure

**Use:** Expandable categories such as locations or product families.

**CSS:** `padding: 8.4px 25.2px 25.2px; background: #fffffc; color: #000000; border-top: 2px solid #000000; border-radius: 0px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `accordion-title` — Circular Std 400 · 134.3px/1.15 · tracking -0.07em

**Observed:** An enormous name occupies the left of a roughly 190px-tall full-width row; a small black plus is isolated at the far right. Stacked rows share horizontal rules.

**Transfer:** Use a handful of meaningful, short disclosure labels rather than a dense FAQ.

### Proof group

**Use:** Quantified credibility without dashboard styling.

**CSS:** `background: #fffffc; color: #000000`

**Text style:** `statement` — Circular Std 400 · 109.1px/1.1 · tracking -0.07em

**Observed:** An underlined metric-label precedes a giant regular-weight numeral, then a short body sentence and a Plus link. There is no card outline or tinted fill.

**Transfer:** Use genuine counts tied to specific evidence; preserve the small-label/giant-number relationship.

### Directory link

**Use:** Footer navigation and contributor references.

**CSS:** `display: inline-block; position: relative; padding-bottom: 5px; margin-bottom: 16.8px; color: #000000; border-bottom: 2px solid #000000; overflow: hidden`

**Text style:** `directory-link` — Circular Std 400 · 33.6px/1.1 · tracking -0.03em

**Observed:** Each word has its own underline. Footer navigation and social destinations form two-column lists under small body-size group labels.

**Transfer:** Keep links visibly textual and allow each column to end naturally rather than forcing equal item counts.

### Back to top

**Use:** Closing utility before the footer divider.

**CSS:** `display: flex; justify-content: flex-end; color: #000000`

**Text style:** `utility` — Circular Std 700 · 13.4px/1.5 · tracking -0.0125em

**Observed:** A small solid upward arrow follows the bold label; the action is aligned to the page's right edge immediately above the full-width rule.

**Transfer:** Keep this understated return action separate from the larger directory links.

### Directory footer

**Use:** The page's closing destination map.

**CSS:** `margin-top: 134.3px; padding-bottom: 16.8px; position: relative; color: #000000`

**Text style:** `body` — Circular Std 400 · 16.8px/1.5 · tracking -0.01em

**Observed:** Back to top precedes a 2px divider. Below it, the compact identity occupies the left quarter, navigation occupies the next quarter and social links occupy the right region. Small legal information sits at the bottom after a substantial pause.

**Transfer:** End with a navigable directory on the paper canvas, not a contrasting CTA panel.

### Recognition row

**Only for:** recognition lists

**Use:** External proof inside a case study or evidence index.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 20.1px 25.2px; border-bottom: 2px solid #000000; color: #000000`

**Text style:** `recognition-name` — Circular Std 400 · 33.6px/1.5 · tracking -0.03em

**Observed:** A regular-weight credential name sits over an italic category; a tiny bold result is aligned at the far right. Rows form a ledger rather than badges.

**Transfer:** Use this for certifications, independent evaluations or other named external credentials.

## Imagery and graphics

### Spatial image ribbon

**Use:** Signature visual proof object within the introductory narrative.

**Observed:** Two visible runs of upright rectangular architectural photographs bend around an open horizontal ellipse. White gutters separate the panels; the front panels retain full color while the distant return is pale. The object is biased to the right, extends off the viewport and leaves open paper for text at the left.

**Transfer:** Construct the ribbon from genuine product details, environments, outcomes or process photographs. The minimum version is a perspective arrangement of rectangular images along two arcs; it must still read as an open spatial loop, not a flat carousel.

**Build:** Use a transparent WebGL plane scene or SVG image quadrilaterals on the paper canvas. Lay 12–18 panels with narrow paper gaps around a broad horizontal ellipse; show a large front arc and a smaller back arc, leaving the center empty. Project the panels so they narrow near the left-hand turn, place the loop's center beyond the right half of the page and clip its right edge to the viewport. Fade only the distant panels toward the canvas with a translucent paper overlay; do not add shadows or a colored base.

### Architectural photographic stage

**Use:** Dominant visual proof between editorial chapters and throughout case narratives.

**Observed:** Large square-edged photographs show built environments, people inhabiting them, reflective materials, foliage, warm interior light and blue daylight or dusk. Color remains natural and can be intense; there are no uniform marketing tints. Full-frame images span about 1390px; case-study media spans about 859px and varies in aspect ratio.

**Transfer:** Photograph the product in a real setting, alternating wide context with material or usage details. For a digital product, show purposeful full-width interface compositions and real working environments, not decorative mockups floating on gradients.

### Model and process studies

**Use:** Support the central concept with tangible design thinking.

**Observed:** Physical models appear against pale studio backgrounds, sometimes held by human hands; plans and exploded views alternate with completed photography. These make the work feel researched and material.

**Transfer:** Use prototypes, annotated assembly views or process artifacts at the same editorial scale. Preserve the clean background and avoid ornamental framing.

### Technical social diagrams

**Only for:** case-study pages

**Use:** Explain how the design works between photographic chapters.

**Observed:** White-backed line drawings combine fine gray structure, strong black roof or massing forms and small saturated-red human silhouettes. Other program diagrams use sparse pale-blue or warm-yellow fills and black labels; color remains inside the artwork.

**Transfer:** Translate the product's mechanism into restrained linework with one purposeful highlight color. People or activity markers provide scale, not decorative illustration.

**Build:** Draw the underlying structure with fine low-contrast SVG paths, use solid black for one key structural plane, and add small red activity silhouettes at important interaction points. Keep the background unprinted and the drawing in a rectangular article-width plate; pair it with real outcome imagery.

### Portrait wall

**Only for:** people and culture pages

**Use:** Human proof after workplace imagery and an introduction.

**Observed:** Leadership portraits are black and white, chest-up, with plain gray or dark studio backgrounds. The leadership layout is sparse and asymmetric; smaller staff portraits form a denser seven-column field. Names and small bold roles sit directly below, without card shells.

**Transfer:** Use consistently lit monochrome portraits, respecting the open layout for leaders and tighter rhythm for the broader group.

### Icons

**Observed:** Iconography is unusually sparse: black plus signs support links and disclosure rows; a small solid 8×11px arrow accompanies Back to top. Disclosure plus artwork is about 17×17px.

**Transfer:** Prefer typographic plus signs and simple solid arrows over a library of outlined feature icons.

## Section recipes

How recurring sections are built.

### First screen: Verbal promise and visual stage

**Observed:** Paper canvas sits behind a 76px Fixed masthead. Below the masthead, a centered single-line promise uses the display recipe, spanning most of the usable width with its top about 116px into the page. The next layer is a full-width rectangular photographic stage within 25.2px side gutters, with a nominal 762px-high media region after a 50.4px headline margin. The composition prioritizes the statement and object over explanatory prose: there is no separate hero CTA button or small support line competing with the headline. The main introduction and its actions belong below this opening sequence.

**Transfer:** State the new product's core human outcome in a brief declarative sentence, then give it a substantial real photograph or a well-composed product demonstration as its visual stage. Keep all headline letters readable. If there is no photography, use a purposeful product detail composition on the same paper ground. Case-study and recognition pages instead open with a persistent left title rail and right-hand detail stream; culture pages use a large left-aligned title and workplace imagery.

**Avoid:** Do not turn the opening into a conventional two-column SaaS hero with a paragraph and pill CTA. Do not leave the visual stage empty or permanently clip the headline behind a black rectangle.

**Text style:** `display` — Circular Std 400 · 165.6px/1.06 · tracking -0.07em

### Indexed editorial chapter

**Observed:** An Indexed chapter label leads a regular-weight statement at 109.1px, often spanning about five sixths of the page. The label-to-statement gap is 83.9px. Compact body columns begin after the left third, leaving a conspicuous open left region; a Plus link closes the right-hand explanation. Major chapters use 100.7px margins.

**Transfer:** Alternate one decisive claim with two succinct explanatory angles and a destination-specific action. Use the asymmetric alignment to make room for emphasis, not to scatter unrelated cards.

**Text style:** `statement` — Circular Std 400 · 109.1px/1.1 · tracking -0.07em

### Concept definition

**Observed:** The word-definition recipe makes one keyword enormous. Pronunciation-like notation sits near its baseline, with a grammatical label at the opposite edge. A full-width black rule separates that line from a 50.4px definition phrase; small explanatory paragraphs at left balance a model photograph at right.

**Transfer:** Give one meaningful product concept an editorial definition. Use a short keyword and an honest explanation rather than imitating a dictionary entry without substance.

**Text style:** `word-definition` — Circular Std 400 · 201.4px/0.8 · tracking -0.07em

### Capabilities as an offset list

**Observed:** An Indexed chapter label and a multi-line statement sit above a list positioned in the right half. Underlined service names use roughly 33.6px type with small body-size explanations on the same row.

**Transfer:** Present a concise set of capabilities as text pairs instead of icon cards; keep the capability name visibly stronger than the explanation.

### Monumental disclosure stack

**Observed:** An Indexed chapter label precedes a full-width stack of Monumental disclosure rows. Black horizontal rules and huge regular-weight names dominate; a tiny plus at right supplies the affordance.

**Transfer:** Use for product families, regions or other short category names with deeper information.

**Text style:** `accordion-title` — Circular Std 400 · 134.3px/1.15 · tracking -0.07em

### Proof ledger and featured work

**Observed:** A Ruled chapter begins with its index at left and a large supporting statement in the right two thirds. Four Proof groups follow horizontally, each showing an underlined label, large numeral, explanation and small action. A pair of large photographic items follows, with section-label-size titles and Plus links.

**Transfer:** Support an assertion with truthful metrics and then concrete examples. Retain the ledger's unboxed treatment even when the metrics differ.

**Text style:** `metric-label` — Circular Std 400 · 31.9px/1.5 · tracking -0.03em

### Directory ending

**Observed:** The final content hands off to Back to top at the upper right, a full-width 2px rule and the Directory footer. Underlined links at 33.6px remain far more prominent than the compact group labels and bottom legal line.

**Transfer:** Let the final action be exploration through a legible directory, maintaining the same light paper surface to the end.

**Text style:** `directory-link` — Circular Std 400 · 33.6px/1.1 · tracking -0.03em

### Persistent case narrative

**Only for:** case-study pages

**Observed:** A roughly 446px left rail holds a case-title near the top and a 50.4px underlined collection-return link near the viewport bottom. The right 859px stream contains a summary, six metadata fields, editorial headings, body paragraphs and many rectangular images. Recognition rows and a contributor list close the article; some cases add a large final context label and a horizontal monochrome image strip before the Directory footer.

**Transfer:** Use this variant for detailed launches or case studies requiring sustained visual explanation. Keep the rail outside the scrolling article and release it before the footer.

**Text style:** `case-title` — Circular Std 400 · 83.9px/1.06 · tracking -0.07em

### Recognition index

**Only for:** recognition indexes

**Observed:** The left rail pairs recognition-title with a compact statement near the bottom. On the right, each entry begins with an index-item-title and Plus link, then a large photograph and a ruled list of Recognition rows. The pattern repeats without card boundaries, followed by the Directory footer.

**Transfer:** Turn a long proof archive into a sequence of named outcomes with visual evidence and concise external results.

**Text style:** `recognition-title` — Circular Std 400 · 109.1px/1.06 · tracking -0.07em

### Culture and people narrative

**Only for:** people and culture pages

**Observed:** A culture-title and short descriptor introduce an editorial text-and-photo composition. Large office images mix full-width and unequal-width pairs; a sparse leadership portrait layout follows, then a dense monochrome Portrait wall and the Directory footer.

**Transfer:** Show real working conditions before listing people; use portrait hierarchy rather than decorative biography cards.

**Text style:** `culture-title` — Circular Std 400 · 134.3px/1.06 · tracking -0.07em

## Page flow

**Storyline:** Verbal promise → visual demonstration → editorial capability chapters → concrete and quantified proof → contextual detail → directory ending.

### Broad marketing introduction and exploration

1. **Promise** — A monumental centered sentence and full-width visual stage.
2. **Positioning** — Compact manifesto paired with a spatial loop of visual evidence.
3. **Capability chapters** — Indexed large claims, offset explanatory columns, a concept definition, capability list and monumental disclosures.
4. **Social and quantified proof** — Human imagery, monochrome client marks, four unboxed metrics and featured visual examples.
5. **Closing navigation** — Back-to-top utility and ruled directory.

**Transfer:** Choose relevant chapters freely while retaining the characteristic index labels, spatial image object, proof ledger and directory ending.

### Establish people, culture and expertise

1. **Introduction** — Large title, collective descriptor and split editorial text.
2. **Human demonstration** — Large workplace photographs and unequal image pairs.
3. **Expertise proof** — Sparse leadership portraits followed by a denser monochrome staff wall.
4. **Closing navigation** — Portrait field gives way to the shared directory.

**Transfer:** Use the people-page variant when human authorship is a main reason to trust the product.

### Explain a large, complex flagship outcome

1. **Identity and summary** — Persistent title rail and return action beside an introductory statement and metadata.
2. **Product demonstration** — Long sequence of editorial headings, completed photography and program diagrams.
3. **External and contributor proof** — Recognition ledger and underlined contributor list.
4. **Contextual close** — Large context heading, monochrome image strip and shared directory.

**Transfer:** Use the case-study rail to support a complex offering with many distinct visual explanations.

### Provide an independent-proof archive

1. **Framing** — Persistent short page title and compact recognition statement in the left rail.
2. **Repeated proof** — Named item, plus-link, large photograph and recognition ledger repeat down the right.
3. **Closing navigation** — The archive ends in the shared ruled directory.

**Transfer:** Adapt to an evidence library without replacing the photographic entries with badge grids.

### Explain a focused design through experience and detail

1. **Identity and summary** — Persistent case title, collection-return action and six-field metadata.
2. **Experience chapters** — Compact headings and paragraphs alternate with dusk photography, exploded drawings, linework and interior details.
3. **Technical proof** — Framed plans conclude the media narrative.
4. **Attribution and close** — Recognition ledger, contributors and specialist credits lead directly to the shared directory.

**Transfer:** Use this focused variant for a single product story where a few mechanisms deserve deep visual treatment.

## Writing

Confident and direct about the work, warm and collective about the people. Editorial explanation combines ambitious human outcomes with concrete descriptions of how the result works.

**Do not copy:** Do not reuse CLOU's identity artwork, founder and staff names, project names, proprietary slogans, client marks, award claims or numerical achievements. Source examples illustrate cadence only.

- **Addressing the reader:** Mostly first-person plural in broad marketing statements; third-person descriptive narration in detailed cases. Direct second-person selling is rare.
- **Rhythm:** Short declarative headlines, often beginning with 'We', contrast with explanatory paragraphs of several clauses. Section labels are brief possessive noun phrases; action labels are terse verb-plus-destination phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct collective subject, active verb and concise human outcome, ending with a period. | 4–7 words | “We do social space.” |
| Chapter claim | An optimistic, self-contained sentence rather than a feature noun. | 4–10 words | “We are a community of optimists.”<br>“We work with ambitious clients.” |
| Section label | A possessive noun phrase, preceded visually by a parenthesized index. | 2–3 words | “Our approach”<br>“Our services” |
| Support | Connect creative method to a practical result using plain active language. | 15–30 words | “Combining smart creativity with commercial savvy, we take our clients’ challenges and transform them into exceptionally innovative design.” |
| Action | View plus a concrete destination and a trailing plus sign. | 2–4 words | “View projects +”<br>“View our team +” |
| Detail chapter | Name the lived experience or mechanism, not a generic benefit. | 4–10 words | “Framing the Journey Home”<br>“Integrating sports with celebration, events and retail” |

**Words and phrasing to use:** we; our; collective; optimistic; connected; ambitious; create; transform; experience; community

**Avoid:** disruptive; 10x; game-changing; unlock limitless potential; hurry; exclusive deal

**Rules:**

- Let large headlines make one claim; let the smaller columns explain it.
- Tie praise to a real process, artifact or result.
- Treat collaborators and users as participants rather than targets.
- Use destination-specific View actions instead of generic Learn more everywhere.
- Keep named results and qualifications factual in the recognition ledger.

## Do's and Don'ts

### Do

- Set major claims at weight 400 with -0.07em tracking; let scale, not boldness, provide authority.
- Maintain the 25.2px desktop outer gutter and its relationship to the inner grid.
- Pair 50.4px chapter labels with 20.1px parenthesized indices and a 2px title underline.
- Keep body explanations at 16.8px/1.5 in offset columns rather than stretching them across the page.
- Use natural-color rectangular media to supply the chromatic richness against #fffffc.
- Include the spatial image ribbon as a genuine proof object with open paper through its center.
- Make proof numerals as large as chapter claims, supported by underlined 31.9px labels.
- Close with the 2px divider, Back to top and 33.6px underlined directory links.

### Don't

- Do not introduce a rainbow UI palette; strong color belongs inside the media.
- Do not substitute heavy black display weights for the regular grotesk; the tight tracking already creates density.
- Do not turn Plus links into rounded filled buttons or add oversized hit-area-looking visual padding.
- Do not add soft shadows or rounded photo corners; media and content remain square-edged and unraised.
- Do not use a uniformly centered card grid for every explanation; the asymmetrical text offsets are essential.
- Do not add decorative feature icons where a text pair or underlined list communicates the capability.
- Do not recolor all photography to monochrome; reserve that treatment for portraits, identity marks and contextual strips.
- Do not turn the ending into a dark newsletter takeover; retain the paper-ground directory.

## Motion and responsive

### Motion

**Observed:**

- Declared masthead background-color transition: 0.3s ease-in-out.
- Declared transitions elsewhere include opacity 0.3s and transform 0.3s ease-in-out.
- Text uses clipped wrappers and wipe-like reveals; media is held inside overflow-hidden image wrappers. Case-study title rails remain persistent while the article advances.

**Transfer:**

- Keep reveal treatments subordinate to readable editorial text; the settled state must show the whole statement and image.
- Keep the title-and-return rail persistent only within a long case narrative, releasing it before the directory ending.

**Unknown:**

- Exact reveal timing, scroll choreography and spatial-ribbon interaction are unspecified.

### Responsive

**Observed:**

- The opening display explicitly follows clamp(20px, 11.5vw, 400px); the root follows calc(7.1px + 0.66964vw).
- Desktop masthead navigation and language controls have small-screen and touch-specific visibility variants. Columns have full-width base classes and fractional wider-layout variants.

**Transfer:**

- On narrow layouts, stack explanatory text and media in reading order while keeping chapter indices attached to labels.
- Convert the case title rail into an in-flow heading and return link before the article; keep the spatial image ribbon visible without forcing horizontal document overflow.
- Reflow proof groups and directory columns rather than shrinking the desktop grid to illegible widths.

**Unknown:**

- Exact mobile menu construction, breakpoint-to-layout mapping and narrow-screen image-ribbon behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
