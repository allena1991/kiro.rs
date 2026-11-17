# Arctic Design Range — tactile editorial collage

## Overview

A light, gallery-like editorial style that makes physical materials feel culturally alive. Black grotesk typography and pale grey bands leave room for vivid photography, playful still lifes and scattered image compositions. It suits design-led products, creative tools and material collections, with sparse controls and unusually substantial reading passages.

### Essentials

- The opening is a typographic exhibition, not a sales panel: one uppercase word at 230.4px/1, weight 700, sits behind scattered rectangular pictures across a 900px-tall white stage.
- A tiny masthead balances the oversized artwork: a 52×41px symbol at left, a 141×27px centered wordmark and a 46×46px menu control with 80px side gutters.
- Editorial reading carries the proposition: 40px/1.2 bold headings introduce 30px/1.35 regular paragraphs in an 816px centered column, with 40px between them.
- Conversion is a plain black rectangle: white 20px/1.5 weight-900 text, 13.8px by 37.5px padding, no rounding; secondary actions are bold underlined text.
- Color belongs to the work, not the furniture: white and #f7f7f7 cover almost all structural surfaces; saturated color stays inside photography and artwork, with #143c9c reserved for action hover.
- A tactile image stage must accompany the word collage: use large borderless photographs of objects, materials and human work; without finished product imagery, compose physical prototypes or process details on a softly lit neutral tabletop.
- The ending feels like a publication colophon: a #f7f7f7 footer uses 80px top and side padding, 52px bottom padding, a left signature and small bold link columns on the right.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#143c9c` | `--color-interaction` | action, link | Hover fill on the black button and hover color on the bold underlined link; not a resting brand fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | All main text, symbols and primary action fills. |
| Pale grey paper | `#f7f7f7` | `--color-band` | background, surface | Editorial introduction bands, gallery backing, resource panels and footer. |
| White paper | `#ffffff` | `--color-canvas` | background, text | Default canvas and reversed text on dark surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| detailed product stories | Charcoal | `#181818` | `--color-technical` | background | Full-width reversed specification chapter. |

## Typography

- **Munken Sans Web** — Every text role, from exhibition word to footer navigation. Open, rounded grotesk with a friendly single-storey character and substantial bold cuts; editorial rather than technical. If unavailable, use **Albert Sans**. Use 400, 700 and 900; preserve normal tracking and open paragraph leading. Font stack: "Munken Sans Web", "Albert Sans", system-ui, -apple-system, "Segoe UI", Roboto, Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Munken Sans Web | 700 | 230.4px | 1 | normal, uppercase | size 16vw | Single-word exhibition artwork in the opening collage. |
| heading | Munken Sans Web | 700 | 40px | 1.2 | normal | fixed | Main editorial title and broad two-column section title. |
| lead | Munken Sans Web | 400 | 30px | 1.35 | normal | fixed | Long opening editorial passages in the centered reading column. |
| body | Munken Sans Web | 400 | 20px | 1.5 | normal | fixed | Compact product summaries and related-story descriptions. |
| action | Munken Sans Web | 900 | 20px | 1.5 | normal | fixed | Primary rectangular button text; also strong inline credit labels in technical chapters. |
| text-link | Munken Sans Web | 700 | 20px | 1.5 | normal | fixed | Underlined secondary exploration actions. |
| navigation | Munken Sans Web | 700 | 16px | 1.5 | normal | fixed | Footer link columns. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| detailed product stories | chapter-heading | Munken Sans Web | 700 | 30px | 1.35 | normal | fixed | Headings beside large product detail photographs. |
| range and resource pages | emphasis-heading | Munken Sans Web | 900 | 30px | 1.35 | normal | fixed | Resource-panel heading and inline named product variants. |
| detailed product stories and resource pages | reading | Munken Sans Web | 400 | 24px | 1.5 | normal | fixed | Product chapter paragraphs, specifications and resource links. |
| detailed product stories | spec-label | Munken Sans Web | 900 | 24px | 1.5 | normal | fixed | Strong section labels in reversed specifications. |
| related-story collections | teaser-heading | Munken Sans Web | 700 | 24px | 1.35 | normal | fixed | Linked title below a related-story image. |
| related-story collections | category | Munken Sans Web | 700 | 20px | 1.5 | 0.05em, uppercase | fixed | Label above the related-story grid. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Normal letter spacing is central to the rounded, readable texture; uppercase tracking is reserved for the small category label, not the giant word.
- The 30px lead is deliberately close to the 40px title in scale: the proposition reads as an editorial essay rather than a small support caption.
- Weight 900 adds compact emphasis to actions and technical labels without introducing a second family.

## Layout

**Density:** Airy framing around comfortable, substantial reading blocks; large images and long paragraphs occupy the space rather than many small UI units.

### Spacing

**Spacing system:**

- **space** 12px — Declared spacing family: 12px through 96px in eight steps.
- **gutter-step** 16px, horizontal — Side-padding base; desktop 80px gutters are five steps.

| Value | Use |
| --- | --- |
| 16px | Paragraph-to-secondary-action separation and short supporting-copy breaks. |
| 32px | Image-to-teaser-title separation and masthead column gap. |
| 40px | Title-to-paragraph separation. |
| 48px | Related-story column gaps and resource heading-to-copy separation. |
| 64px | Reading passage-to-centered-button gap, category-to-grid gap and footer copyright separation. |
| 80px | Desktop side gutters and footer top padding. |
| 96px | Two-column summary section vertical padding and resource panel padding; eight space units. |
| 112px | Top padding before large gallery media and technical content. |
| 128px | Main editorial band top inset, two-column gutter and chapter separation. |

### Containers and grids

- **wide stage**: max width 1280px · side padding 80px. At 1440px, images, feature rows and footer span the remaining width. Full-bleed hero artwork ignores this inset.
- **reading column**: max width 816px · side padding 80px. Centered outer reading column; left-aligned editorial text inside it.
- **compact text**: max width 640px. Short titles, supporting details and credits nested in the reading column.
- **feature pair**: 2 columns · gap 128px · side padding 80px. Two equal 576px columns at desktop, alternating image and copy. Summary aligns vertically centered; long chapters align to the top.
- **related grid** (only for related-story collections): 3 columns · gap 48px · side padding 80px. Three approximately 395px-wide borderless editorial teasers.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons and media | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default page and exhibition backing.

**CSS:** `background: #ffffff; color: #000000`

#### Pale editorial band · level 0

**Use:** Long introduction, gallery and footer backing.

**CSS:** `background: #f7f7f7; color: #000000`

**Observed:** Flat full-width planes with no border, elevation or decorative edge.

**Transfer:** Use changes between white and pale grey to group narrative blocks rather than enclosing every block in a card.

#### Resource inset · level 0

**Only for:** range and resource pages

**Use:** A final help and resource panel.

**CSS:** `background: #f7f7f7; padding: 96px 80px; border-radius: 0px`

**Observed:** Inset within the wide gutters, with another centered reading column inside; white separates it from the footer.

**Transfer:** Offer a small number of direct next steps in prose.

#### Reversed specification band · level 0

**Only for:** detailed product stories

**Use:** Technical detail and production credits.

**CSS:** `background: #181818; color: #ffffff; padding: 112px 80px 128px`

**Observed:** A single broad dark interruption in an otherwise light story, with left-aligned text in the reading column.

**Transfer:** Use for real material, process or implementation details, not decorative feature tiles.

## Components

### Exhibition masthead

**Use:** Minimal brand orientation over the opening artwork.

**CSS:** `display: grid; grid-template-columns: minmax(0px, 1fr) minmax(0px, auto) minmax(0px, 1fr); gap: 32px; padding: 36px 80px 0px`

**Observed:** A small angular symbol occupies the left edge, the wordmark is independently centered, and Menu toggle sits at the right. The artwork extends behind this transparent header.

**Transfer:** Use the new identity in these three roles without turning the masthead into a horizontal link bar.

### Menu toggle

**Use:** Persistent navigation access.

**CSS:** `position: fixed; padding: 6px; width: 46px; height: 46px; mix-blend-mode: difference; z-index: 12`

**Observed:** Three fine horizontal lines within a 34px icon. Only the menu remains visible while reading lower sections; contrast reverses over the dark chapter.

### Primary button

**Use:** Single focused conversion below editorial copy.

**CSS:** `background: #000000; color: #ffffff; padding: 13.8px 37.5px; border-radius: 0px; text-align: center`

**Text style:** `action` — Munken Sans Web 900 · 20px/1.5

**Observed:** Compact rectangular silhouette, approximately 58px high and 182–188px wide for short labels; centered beneath the reading column, without an arrow.

**States:** Declared: hover background-color #143c9c; focus-visible unknown; active transform scale(0.95).

### Exploration link

**Use:** Secondary route after a concise product summary.

**CSS:** `color: #000000; text-decoration: underline; position: relative`

**Text style:** `text-link` — Munken Sans Web 700 · 20px/1.5

**Observed:** A bare inline text action immediately following the paragraph, with no surrounding panel or icon.

**States:** Declared: hover color #143c9c and text-decoration none; focus-visible unknown; active unknown.

### Publication footer

**Use:** Shared page ending and secondary navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; background: #f7f7f7; padding: 80px 80px 52px`

**Text style:** `navigation` — Munken Sans Web 700 · 16px/1.5

**Observed:** Combined symbol and wordmark at left, approximately 203×39px. At right, two compact navigation columns and a separate social column use 10px row gaps and 72px main column gaps. A regular 16px/24px rights line sits 64px below the links.

**Transfer:** Retain the small publication-like signature and right-weighted navigation rather than a large closing slogan.

### Related story teaser

**Only for:** related-story collections

**Use:** Continue exploration after the main product story.

**CSS:** `position: relative; border-radius: 0px`

**Text style:** `teaser-heading` — Munken Sans Web 700 · 24px/1.35

**Observed:** Landscape image approximately 395×273px, then title after 32px, regular body after 16px and an underlined Exploration link. Text has a 336px maximum width; no card fill or outline.

**Transfer:** Use a few adjacent products or editorial stories with image-led differences.

### Resource link

**Only for:** range and resource pages

**Use:** Direct external next steps within prose.

**CSS:** `color: #000000; text-decoration: underline`

**Text style:** `reading` — Munken Sans Web 400 · 24px/1.5

**Observed:** Regular-weight URL appears inline or on the next line of explanatory prose, not as a button.

**States:** Declared: hover text-decoration none; focus-visible unknown; active unknown.

### Specification label

**Only for:** detailed product stories

**Use:** Organize technical detail without a table.

**CSS:** `color: #ffffff`

**Text style:** `spec-label` — Munken Sans Web 900 · 24px/1.5

**Observed:** Strong standalone labels precede regular 24px detail lines; credits below use the smaller 20px body with bold inline role names.

**Transfer:** Describe substantiated construction, compatibility or production details using stacked text rather than badges.

## Imagery and graphics

### Floating editorial collage

**Use:** Signature exhibition artwork for the main marketing opening.

**Observed:** Around a dozen sharp-edged rectangular pictures float at varied heights over and around the giant black word. Portraits, food, workshops, print objects and saturated graphic patterns mix documentary and designed imagery. Images stay upright, approximately 130–215px across at desktop, with ample white between them; some occlude the letters.

**Transfer:** Curate process, people, outcomes and material closeups for the new product. When finished media is unavailable, photograph prototypes, tools, textures and simple original color studies; the collage remains essential.

**Build:** Create a white 100%-wide, 900px-tall relative stage. Center a single uppercase word with the display recipe across roughly two thirds of the width. Position 10–12 rectangular images in an irregular ring spanning upper, middle and lower areas; mix portrait and landscape aspect ratios. Layer several images above the word and others outside its bounds, with no rotation, shadow or frame. Keep the masthead in the foreground and leave the word legible as a whole.

### Tactile still life

**Use:** Large gallery image and product-detail opening.

**Observed:** A white printed object tilts diagonally above a pale timber tabletop, balanced by a sculptural yellow fruit, red rounded form, black-rimmed clock and tiny green die. Warm grey backing, directional daylight and real contact shadows make the arrangement playful but physically believable. The image occupies nearly an entire screen.

**Transfer:** Stage the new object with two or three contrasting physical forms and a restrained neutral horizon. A photographed prototype with one colored prop is the minimum acceptable alternative; keep the photographic light and material texture rather than replacing it with floating UI.

### Product detail photographs

**Use:** Summary feature row and alternating editorial chapters.

**Observed:** Open books and printed sheets sit on a muted blue-grey plane in a landscape frame; single upright volumes use a warm grey backing in 576×720px portrait frames. White materials retain embossing, fibers and edge shadows. Photographs fill their rectangular area without rounded masking.

**Transfer:** Show real construction or use details on a subdued studio plane, keeping texture visible and graphic content secondary to the physical object.

### Material macro film

**Only for:** range and resource pages

**Use:** Full-bleed opening before the factual range title.

**Observed:** An extreme close view of reflective metallic folds beside a bright green stack of finely cut layered material; neutral grey ground and shallow focus emphasize surfaces. The visual fills a 1440×804px field.

**Transfer:** Use a macro photograph or film of the new product's defining material interaction, with one vivid material accent and a neutral surrounding field.

### Icons

**Observed:** Navigation uses a 34×34px SVG with 2px butt-ended line work inside a 46px control. Brand marks are black, angular and compact; ordinary text actions have no icon.

**Transfer:** Keep functional iconography limited to a simple three-line menu. Use the new identity for symbols, and resist adding feature-icon grids.

## Section recipes

How recurring sections are built.

### First screen: Word and image exhibition

**Observed:** A white, full-bleed 900px stage places Exhibition masthead above a centered uppercase display word at 230.4px/1 and weight 700. The word occupies roughly two thirds of the width across the middle; Floating editorial collage pictures surround it and overlap selected letters, spreading from just below the masthead to near the bottom edge. Layers run white ground, black word, upright photographs, then identity and menu. Within the first 900px the whole collage and masthead are visible; support prose and actions fall below the fold.

**Transfer:** Choose one short conceptual word and surround it with original process, people, object and outcome images. Keep the exhibition device even for digital products by photographing their working context. A detail story can instead open with the Tactile still life filling the viewport, followed by a centered 40px title below; a range story uses Material macro film with its title entering near the bottom of the first screen.

**Avoid:** Do not squeeze an H1, paragraph, two CTAs and a mockup into a conventional split hero, or replace the upright floating images with a rigid thumbnail grid.

**Text style:** `display` — Munken Sans Web 700 · 230.4px/1 · uppercase

### Editorial proposition

**Observed:** Pale editorial band contains a centered 816px column with left-aligned heading and lead. Top inset is 128px, title-to-lead gap 40px, and a centered Primary button follows after 64px. Detailed stories use White canvas for the same reading language.

**Transfer:** State the cultural or practical motivation in a substantial paragraph before asking for action; let the section height follow the prose.

**Text style:** `lead` — Munken Sans Web 400 · 30px/1.35

### Large photographic interlude

**Observed:** Pale editorial band continues behind an inset 1280px-wide gallery image, with 112px top and 96px bottom breathing room. The Tactile still life is allowed to dominate rather than being captioned as a small card.

**Transfer:** Give one major photographic scene room to reward the preceding reading block.

### Two-column product chapter

**Observed:** Feature pair combines a 576px-wide image with equal-width copy across a 128px gap. Summary uses heading, body and Exploration link on the left, landscape photograph on the right, and 96px vertical padding. Longer chapters alternate portrait photographs and top-aligned chapter-heading plus reading text, separated by 128px.

**Transfer:** Use the short summary for a related offering and the longer variant for two distinct capabilities; alternate by narrative need rather than repeating identical cards.

### Publication ending

**Observed:** Publication footer is the common final element. The light grey plane, left signature, compact right link groups and low rights line end the story without a giant closing headline.

**Transfer:** Preserve this modest colophon even when the preceding closing content varies.

### Reversed production notes

**Only for:** detailed product stories

**Observed:** Reversed specification band centers an 816px column. Specification label begins the chapter, followed by regular reading text, grouped specifications and a compact credit block with inline strong role names. The chapter is text-only and generously padded.

**Transfer:** Use a dark technical pause to substantiate the promise through actual materials, implementation facts or credited collaborators.

**Text style:** `spec-label` — Munken Sans Web 900 · 24px/1.5

### Related editorial collection

**Only for:** related-story collections

**Observed:** Category label precedes the Related story teaser grid by 64px. Three columns have 48px gutters and 96px row gaps, and the collection leaves 128px before Publication footer.

**Transfer:** Offer a small coherent set of adjacent stories or products with real imagery and concise descriptions.

**Text style:** `category` — Munken Sans Web 700 · 20px/1.5 · tracking 0.05em · uppercase

### Resource closing panel

**Only for:** range and resource pages

**Observed:** Resource inset contains an emphasis-heading, then reading text after 48px. Two resource prompts are separated by 40px and include Resource link. An 80px white interval separates panel from Publication footer.

**Transfer:** Close informational pages with practical routes such as samples, documentation or contact rather than inventing a promotional banner.

**Text style:** `emphasis-heading` — Munken Sans Web 900 · 30px/1.35

## Page flow

**Storyline:** visual exhibition → editorial motivation → tangible demonstration → deeper context or practical proof → routes to further exploration → publication colophon

### Introduce a creative product and invite deeper reading

1. **Visual promise** — A monumental conceptual word surrounded by a loose photographic constellation.
2. **Motivation** — A pale editorial introduction and centered rectangular reading action.
3. **Product demonstration** — Large inset still-life gallery.
4. **Broader context** — A concise two-column overview and underlined exploration route.
5. **Navigation ending** — Shared pale publication footer.

**Transfer:** Use a small number of generous editorial blocks, with the collage establishing the product's world before explanatory copy.

### Explain a range, material or company capability

1. **Sensory promise** — Full-width material macro film and centered title.
2. **Explanation** — Large regular paragraphs and strong inline variant names.
3. **Substantiation** — A compact certification mark followed by factual supporting paragraphs.
4. **Practical next steps** — Inset resource panel with two direct prose links.
5. **Navigation ending** — Shared pale publication footer.

**Transfer:** Trade campaign-like collage emphasis for a material-led introduction, then explain meaningful differences and provide substantiated proof.

### Tell an in-depth product story

1. **Object introduction** — Full-bleed tactile still life, followed by centered title.
2. **Motivation and conversion** — Long editorial reading passage and a centered order action.
3. **Capability chapters** — Alternating portrait product images and substantial explanatory text.
4. **Technical proof** — Dark material specifications and production credits.
5. **Continued exploration** — Three related editorial teasers.
6. **Navigation ending** — Shared pale publication footer.

**Transfer:** Expand the physical demonstration into focused chapters; use technical detail to earn the claims rather than adding a generic testimonial carousel.

## Writing

Cultured, sensory and assured, with the feel of an exhibition introduction followed by a useful product essay. It connects creative ambitions to tangible properties and then turns matter-of-fact when specifying details.

**Do not copy:** Do not reuse Arctic or Surface identities, issue names, proprietary artwork, contributor lists, certification claims, production facts or numerical product specifications. Source examples illustrate cadence only.

- **Addressing the reader:** Mostly third-person description, with occasional direct you and your when discussing choices or practical next steps. Product names act as subjects rather than a constant first-person brand voice.
- **Rhythm:** Short conceptual display word, descriptive title, then multi-sentence paragraphs. Dashes and colons connect ideas; short concluding fragments punctuate longer passages. Actions stay at two words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Exhibition word | One broad sensory or cultural concept in capitals. | 1 word | “Analog” |
| Editorial title | Product or edition identifier followed by a plain-language proposition. | 5–9 words | “Surface N°4: The analog is back.” |
| Supporting passage | Connect a recognizable shift to a sensory or practical motivation before introducing the object. | Several sentences | “This is not mere nostalgia. It is a rebalancing – the world's thinness meeting our deep longing for sensory connection.” |
| Primary action | Simple verb plus the thing or reading action. | 2 words | “Read more”<br>“Order book” |
| Chapter heading | Named chapter plus a direct statement of value, joined with a dash. | 6–10 words | “ANALOG FAQ – The Paper Knowledge You Need” |
| Resource prompt | Explain the practical next step in a full sentence, then show a direct link. | 1 sentence | “Try the range for yourself by ordering samples or a dummy for your next project:” |

**Words and phrasing to use:** natural feel; materiality; craft; colour and contrast; meaningful objects; creative professionals; touch, sight, smell, and memory

**Avoid:** game-changing; 10x; disruptive platform; supercharge; frictionless ecosystem

**Rules:**

- Lead with why the object or experience matters, then explain what makes it work.
- Keep sensory language attached to real material or experiential qualities.
- Let factual detail become plainer and more specific as the story deepens.
- Use short action labels without promotional punctuation.

## Do's and Don'ts

### Do

- Keep the opening word at 230.4px/1 at desktop and preserve the image overlaps.
- Use 816px reading columns for substantial 30px/1.35 introductory prose.
- Keep desktop outer gutters at 80px and feature-pair separation at 128px.
- Use square rectangular actions with 20px weight-900 labels.
- Make photographic texture and the object's real shadows carry the sense of depth.
- Finish with small 16px bold navigation on a flat pale-grey footer.

### Don't

- Do not replace normal tracking with fashionable tightly compressed display lettering.
- Do not use pills, rounded media masks or floating shadow cards; the construction is square and flat.
- Do not spread the blue hover color into resting buttons, bands or headlines.
- Do not reduce the substantial editorial lead to a tiny conventional hero subtitle.
- Do not make all text 900 weight; regular 400 paragraphs carry most of the reading.
- Do not introduce separators and card outlines to organize the related grid; use its 48px gaps and aligned image edges.
- Do not make the whole page dark because one technical chapter uses charcoal.

## Motion and responsive

### Motion

**Observed:**

- Primary button declares transform 0.3s cubic-bezier(0.23, 1, 0.32, 1), background-color 0.15s cubic-bezier(0.25, 0, 0.25, 1), and color 0.15s with the same color easing.
- Text actions declare color 0.15s cubic-bezier(0.25, 0, 0.25, 1). Button active state scales to 0.95.
- The material-led opening uses video; the menu remains fixed while reading.

**Transfer:**

- Keep the compact press response and restrained blue hover as the main action feedback; preserve the collage's layered composition even when presented statically.

**Unknown:**

- Collage movement, scroll choreography, video timing and menu-open behavior are unspecified. Focus-visible styling is unspecified.

### Responsive

**Observed:**

- Styles declare width breakpoints at 359px, 479px, 480px, 719px, 720px, 959px, 960px, 1040px and 1280px.

**Transfer:**

- On narrower screens, preserve the short giant word and selected image overlaps while reducing image count per visible band; do not turn the signature scene into tiny equal tiles.
- Stack feature-pair copy and imagery in narrative reading order and reduce outer gutters before shrinking body text; retain the separate centered identity and menu roles.

**Unknown:**

- Exact narrow-screen spacing, type scale, gallery interaction and column-collapse behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
