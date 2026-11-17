# Groq — dot matrix monumentality

## Overview

A light industrial identity pairs enormous rounded grotesk lettering with tiny dot-matrix labels and typewriter-like technical prose. Warm ivory and brown-black carry most of the composition, interrupted by vermilion signals and emphatic olive and orange chapters. It suits infrastructure and ambitious technical products, with sparse geometric marks and luminous data sculptures rather than lifestyle photography.

### Essentials

- Headlines behave like product nameplates: medium-weight esBuild at 184.2px/0.85 with -0.045em tracking, stacked on the left opposite a small 16px technical paragraph.
- The opening is a low-set typographic stage rather than a picture hero: an 80px fixed masthead, 49px announcement strip, 32px side margins and broad empty space precede the two-line name; a 57px orange dot punctuates it.
- Controls read like machine markings: komuna capitals with 0.08em tracking sit in transparent, 1px orange pill outlines; the main action uses 21.3px type and 16px 24px padding.
- Color is a signal and a chapter, not a wash: ivory #f3f3ee dominates the opening, grids and ending; orange #f43e01 marks actions and small geometry, while full-width olive #475c05 and orange #e93b01 interrupt the light canvas.
- Data becomes a luminous physical object: a near-white dotted sculpture rises out of the ivory field with thin orange trajectories and tiny location pills. Include a data-object stage; without geographic content, use a dotted sphere or product-shaped network with truthful annotations.
- The ending is a second billboard: a two-line uppercase value statement at 135.5px/0.95 spans the 32px margins, with words distributed across the width, a small brand/social row above and utility navigation below.
- Small geometric punctuation ties the system together: orange circles touching capsule labels, stepped pixel fragments near page edges and huge cropped tone-on-tone symbols supply identity without card decoration.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Machine olive | `#475c05` | `--color-olive` | background | Full-width technical capability chapter, contrasting with white headings. |
| Vermilion field | `#e93b01` | `--color-orange-band` | background, accent | Conversion band, circle punctuation and category capsules. Distinct from the brighter action orange. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#f43e01` | `--color-signal` | action, link, border, accent | Outlined actions, active links, network nodes and sparse geometric accents. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, border | Large statements and outlined action on saturated bands; luminous data art. |
| Warm ivory | `#f3f3ee` | `--color-canvas` | background, text | Default page ground, transparent-card backing, navigation and footer; also pale text on saturated surfaces. |
| Stone rule | `#cecebf` | `--color-rule` | border, text | Hairlines, grid dividers and unrevealed prose. |
| Faded olive gray | `#929289` | `--color-ticker` | text | Technical ticker copy; visible result of olive gray at 70% opacity on ivory. |
| Olive gray | `#69695d` | `--color-muted` | text | Quiet utility navigation. |
| Soft brown | `#575350` | `--color-support` | text | Technical paragraphs on ivory; visible result of brown-black at 80% opacity. |
| Graphite | `#2d2f33` | `--color-body-ink` | text | Footer billboard and inherited supporting text. |
| Brown black | `#302b28` | `--color-ink` | text | Default headlines and primary lettering. |

## Typography

- **esBuild** — All major headlines, card names, manifesto prose and the closing billboard. Rounded geometric grotesk with broad circular forms, a high x-height and dense medium-weight display settings. OpenType features: "ss09", "ss10", "ss14", "ss16". If unavailable, use **Manrope**. Use 500; tune width before adjusting the negative tracking. Font stack: "esBuild", "Manrope", system-ui, "Helvetica Neue", Helvetica, Arial, sans-serif.
- **komuna** — Navigation, announcements, buttons, tickers and small category labels. Fine dot-matrix, machine-lettered capitals; despite the serif fallback, the visible construction is technical and monospaced in spirit. OpenType features: "ss09", "ss10", "ss14", "ss16". If unavailable, use **Doto**. Use the light dotted construction and retain 0.08em tracking. Font stack: "komuna", "Doto", Georgia, "Times New Roman", serif.
- **aether** — Technical supporting paragraphs and oversized technical watermark lettering. Typewriter-like mono with small seriffed terminals and tightly fitted spacing. OpenType features: "ss09", "ss10", "ss14", "ss16". If unavailable, use **IBM Plex Mono**. Use 400 with -0.04em paragraph tracking. Font stack: "aether", "IBM Plex Mono", ui-monospace, "Cascadia Code", "Source Code Pro", Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | esBuild | 500 | 184.2px | 0.85 | -0.045em | Two-line product name in the opening. |
| conversion-display | esBuild | 500 | 159.6px | 0.8 | -0.05em | Oversized short command on the orange conversion band. |
| closing-billboard | esBuild | 500 | 135.5px | 0.95 | -0.01em, uppercase | Two distributed rows of closing positioning copy. |
| chapter-statement | esBuild | 500 | 89.8px | 0.9 | -0.035em | White multiline statement on the olive capability field. |
| proof-heading | esBuild | 500 | 67.3px | 0.95 | -0.035em | Centered two-line headline over the data-object stage. |
| heading | esBuild | 500 | 50.5px | 0.95 | -0.03em | Names in the adjoining capability cards. |
| button-display | komuna | 100 | 28.4px | 1.3 | 0.08em, uppercase | White outlined action in the orange conversion band. |
| button | komuna | 100 | 21.3px | 1.3 | 0.08em, uppercase | Main hero action. |
| ticker | komuna | 100 | 21.3px | 1 | 0.08em, uppercase | Single-line technical specifications in edge-clipped strips. |
| technical-body | aether | 400 | 16px | 1.35 | -0.04em | Compact supporting paragraphs in the hero, cards and technical chapter. |
| utility | komuna | 100 | 16px | 1 | 0.08em, uppercase | Navigation, announcement and footer links. |
| button-compact | komuna | 100 | 16px | 1.3 | 0.08em, uppercase | Header and footer pill actions. |
| chip | komuna | 100 | 12px | 1 | 0.08em, uppercase | Small orange capability labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical capability chapters | technical-watermark | aether | 400 | 358.3px | 252.5px | -0.0334em | Huge cropped abbreviated product mark at the foot of the olive field. |
| manifesto-led brand pages | essay-display | esBuild | 500 | 50.5px | 1 | -0.03em | Continuous large-format argument rather than conventional body paragraphs. |

**Notes:**

- Display headings use weight 500 rather than a heavy bold. Tracking becomes most compressed in the opening and conversion statement; the uppercase closing billboard relaxes to -0.01em.
- Technical support is mono, not miniature sans body copy. Keep its line length narrow: about 335px in the opening and 364px in cards.
- The dot-matrix label face has visibly short glyphs within its line box. Center the glyphs optically inside pills rather than treating the full line-height as the painted letter height.
- Viewport interpolation is not prescribed here; preserve the strong relative scale between display, mono support and fine utility labels.

## Layout

**Density:** Airy overall, with dense headline line spacing and compact controls; large open intervals separate a few forceful elements.

### Spacing

**Spacing system:**

- **grid** 8px — Main padding and layout rhythm; fine control padding is a separate exception.

| Value | Use |
| --- | --- |
| 8px | Chip horizontal inset and small alignment steps. |
| 16px | Heading-to-paragraph separation and announcement vertical padding. |
| 24px | Masthead vertical padding and main-action horizontal inset. |
| 32px | Global side gutters, card inset and primary grid gaps. |
| 40px | Navigation spacing and hero support-to-action gap. |
| 48px | Vertical padding of the broad technical ticker. |
| 56px | Saturated chapter top padding and footer row spacing. |
| 64px | Opening bottom padding and standard section rhythm. |
| 80px | Masthead height and louder section rhythm. |
| 140px | Data-stage top breathing room and category-to-card-title interval. |
| 45px | Only for manifesto-led brand pages: separation between large prose statements. |

### Containers and grids

- **page-frame**: side padding 32px. Full-width marketing frame. Color bands and card grids extend to viewport edges; their contents align to the same side gutters.
- **opening-grid**: 12 columns · gap 32px · side padding 32px. Large stacked name occupies roughly the left seven columns, narrow support and action occupy the right four, with their baselines aligned at the bottom.
- **capability-grid**: 3 columns · gap 0px. Equal adjoining columns, each 480px wide at a 1440px viewport; no detached tiles.
- **support-column**: max width 335px. Compact hero explanation opposing monumental type.
- **proof-heading-frame**: max width 1213px. Centered headline above the luminous data object.
- **essay-column** (only for manifesto-led brand pages): max width 732px. Centered narrow column of left-aligned large prose, with generous blank outer margins.

## Corner radius

| Element | Radius |
| --- | --- |
| action-pills | 1000px |
| category-labels | 24px |
| punctuation-dot | 50% |
| capability-panels | 0px |

## Surfaces and depth

### Surfaces

#### Ivory canvas · level 0

**Use:** Default continuous background across opening, grids and footer.

**CSS:** `background: #f3f3ee; color: #302b28`

**Observed:** Warm and matte, without grain, gradients or elevation.

**Transfer:** Let typography and hairlines create hierarchy on a shared ground.

#### Ruled panel · level 0

**Use:** Adjoining capability cards.

**CSS:** `background: transparent; border: 1px solid #cecebf; border-radius: 0px; box-shadow: none`

**Observed:** Panels remain flush with the page, separated by fine edges rather than raised material.

**Transfer:** Use shared dividers and equal columns for related product layers.

#### Olive chapter · level 0

**Use:** Immersive technical statement and tone-on-tone schematic.

**CSS:** `background: #475c05; color: #ffffff; overflow: hidden`

**Observed:** Flat saturated field with white headline, pale technical support and darker multiplied graphic at its foot.

**Transfer:** Reserve for a major capability assertion, not every feature.

#### Orange conversion field · level 0

**Use:** High-impact conversion chapter.

**CSS:** `background: #e93b01; color: #ffffff; padding: 56px 32px; overflow: hidden`

**Observed:** A giant darker angular symbol extends beyond the field; content sits above it.

**Transfer:** Pair a short imperative and one outlined action with an original oversized geometric emblem.

## Components

### Fixed masthead

**Use:** Persistent brand and compact navigation.

**CSS:** `position: fixed; height: 80px; padding: 24px 32px; display: flex; justify-content: space-between; align-items: center; background: #f3f3ee; z-index: 650`

**Text style:** `utility` — komuna 100 · 16px/1 · tracking 0.08em · uppercase

**Observed:** Orange brand mark at left, four quiet links and a compact outlined action at right; a thin stone rule finishes the lower edge. Links are spaced by 40px.

**Transfer:** Use the new identity's compact wordmark; keep navigation sparse.

### Primary button

**Use:** Main hero conversion action.

**CSS:** `display: flex; align-items: center; background: transparent; color: #f43e01; border: 1px solid #f43e01; border-radius: 1000px; padding: 16px 24px; max-width: 100%; transition: color 0.25s ease-in-out`

**Text style:** `button` — komuna 100 · 21.3px/1.3 · tracking 0.08em · uppercase

**Observed:** A thin open capsule, 251px by 47px for the two-word label. Compact header/footer variant is 181px by 32px, with 10px 14px padding and button-compact type.

**States:** Declared: hover color #f3f3ee; focus-visible solid outline with .3ch offset and color #f3f3ee; active color #f3f3ee.

**Transfer:** Keep a short verb-led label and allow width to follow the text.

### Utility link

**Use:** Header and footer navigation.

**CSS:** `color: #69695d; position: relative; transition: color 0.15s ease-in-out`

**Text style:** `utility` — komuna 100 · 16px/1 · tracking 0.08em · uppercase

**Observed:** Unboxed fine capitals; active navigation uses signal orange and a thin underline aligned to the masthead bottom.

**States:** Declared: hover color #f43e01; focus-visible solid outline with .3ch offset and color #f43e01.

### Announcement strip

**Use:** One topical announcement under the masthead.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 16px 32px; padding: 16px 32px; background: #f3f3ee; border-bottom: 1px solid #cecebf`

**Text style:** `utility` — komuna 100 · 16px/1 · tracking 0.08em · uppercase

**Observed:** A single centered announcement with a separate orange 'Read more' link and small right chevron; desktop band is 49px tall.

**Transfer:** Keep the announcement specific and subordinate to the opening.

### Capability card

**Use:** Explain adjoining product layers or capability tiers.

**CSS:** `display: grid; padding: 32px; border: 1px solid #cecebf; border-radius: 0px; background: transparent`

**Text style:** `heading` — esBuild 500 · 50.5px/0.95 · tracking -0.03em

**Observed:** Category chip at upper left; title comes after 140px of breathing room, followed 16px later by technical-body copy. Equal cards are 380px tall at desktop.

**Transfer:** Use a category label, a concise name and one narrow explanatory paragraph; remove duplicate borders between neighbors.

### Dot category chip

**Use:** Mark the layer represented by each capability panel.

**CSS:** `display: flex; align-items: center; padding: 0px 8px; height: 24px; background: #e93b01; color: #f3f3ee; border-radius: 24px`

**Text style:** `chip` — komuna 100 · 12px/1 · tracking 0.08em · uppercase

**Observed:** One, two or three 24px solid orange circles touch the label's left edge, indicating cumulative layers.

**Transfer:** Carry the touching-circle grammar into a meaningful progression, not arbitrary badges.

### Specification ticker

**Use:** Technical proof between major chapters.

**CSS:** `display: flex; align-items: center; gap: 32px; overflow: hidden`

**Text style:** `ticker` — komuna 100 · 21.3px/1 · tracking 0.08em · uppercase

**Observed:** Repeated single-line specifications extend beyond both viewport edges in faded olive-gray; strips are separated by 32px gaps. One band has 48px vertical padding and a lower hairline.

**Transfer:** Use verified product specifications; keep the line uninterrupted and edge-clipped.

### Conversion button

**Use:** Single action on the orange field.

**CSS:** `display: flex; align-items: center; padding: 24px; color: #ffffff; background: transparent; border-radius: 1000px; transition: color 0.25s ease-in-out`

**Text style:** `button-display` — komuna 100 · 28.4px/1.3 · tracking 0.08em · uppercase

**Observed:** A white 1px capsule outline is drawn by an inset pseudo-element; the two-word action occupies 316px by 65px.

**States:** Declared: hover color #f43e01; focus-visible solid outline with .3ch offset, outline-color #f3f3ee and color #f43e01; active color #f43e01.

### Billboard footer

**Use:** Memorable positioning and final utility navigation.

**CSS:** `display: flex; flex-direction: column; gap: 56px; background: #f3f3ee; border-top: 1px solid #cecebf; padding: 56px 32px 32px`

**Text style:** `closing-billboard` — esBuild 500 · 135.5px/0.95 · tracking -0.01em · uppercase

**Observed:** Small orange brand mark sits opposite 30px social icons, above two giant rows of uppercase words distributed to fill the width. Bottom row puts legal links on the left and utility links plus compact action on the right. Desktop total height is 528px.

**Transfer:** Write a short, ownable positioning line whose words can make two balanced rows; keep the footer visually louder than the utilities.

## Imagery and graphics

### Luminous data sculpture

**Use:** Large quantified-proof stage on the ivory canvas.

**Observed:** A near-white globe with gray dot continents rises from below the section, about 982px across with a broader 1228px effects layer. Its soft rim nearly disappears into the page. Vermilion nodes, tiny orange location pills and fine arcing paths are the only saturated details; the centered heading remains separate above.

**Transfer:** Use a spatial network, product silhouette or dotted sphere to express reach or scale. The minimum version is a carefully shaded dotted SVG object with real annotations and a few fine arcs, not a stock photograph.

**Build:** Create an SVG sphere with a white-to-transparent rim and a low-opacity gray dot field clipped to the silhouette. Project dots more tightly toward the edges. Draw sparse 1px orange cubic curves across and above the object with rgba(244,62,1,0.25), then place solid orange nodes and tiny pale-lettered capsules at real endpoints. Keep the body white/ivory and crop the lower half beyond the section.

### Geometric signal grammar

**Use:** Opening punctuation and recurring small edge ornaments.

**Observed:** A solid orange dot terminates the opening's first line, while small right-angle pixel fragments sit at the far page edges. Category labels use touching circles. These are flat marks, not outlined decorative icons.

**Transfer:** Include original sparse orange punctuation to activate the large empty fields without competing with type.

**Build:** Use a 57px circle beside the first display line. For edge fragments, combine 8px to 24px SVG squares into two- or three-step corner shapes with occasional small square cutouts, filled signal orange. Keep marks near outer margins and away from paragraph letterforms.

### Multiplied technical emblem

**Use:** Lower part of the olive capability chapter.

**Observed:** Huge mono abbreviation at left and an equally large simplified chip-shaped schematic at right, darkened into the olive rather than displayed as a separate image card.

**Transfer:** Use an original short technical name and a schematic of the product's core object. Keep it subordinate to the white statement.

**Build:** Set a short mono abbreviation at 358.3px and anchor it to the bottom edge with partial clipping. Beside it draw a simplified SVG plate with nested rectangular cutouts. Apply an olive-gray fill at 40% opacity and mix-blend-mode:multiply so both forms appear embedded in the field.

### Cropped conversion emblem

**Use:** Background of the orange conversion field.

**Observed:** An enormous darker angular mark occupies the right half, extends beyond the band vertically and is clipped hard at the edges; text and action remain above it.

**Transfer:** Use an original angular emblem or one simple zigzag, not a complex illustration.

**Build:** Draw a broad stepped diagonal polygon in SVG, fill it with rgba(233,59,1,1), apply mix-blend-mode:multiply and size it around 822px by 1248px at desktop. Center it in the right half of the 605px band and clip overflow. Preserve a clear left action zone.

### Icons

**Observed:** Small solid orange SVGs rather than thin line pictograms: 24px circular layer marks and 30px social glyphs. The brand symbol is angular; social marks stay in the header/footer color family.

**Transfer:** Use filled simple glyphs at 24px or 30px. Let circles and square fragments carry ordinary decoration; reserve recognizable logos for real outbound destinations.

## Section recipes

How recurring sections are built.

### First screen: Typographic product opening

**Observed:** Ivory canvas behind an 80px Fixed masthead and 49px Announcement strip. A large clear upper field brings the two-line product name into the lower middle of the first screen. The 184.2px display spans a little over half the page on the left, with a 57px vermilion dot following its first line. A 335px-wide technical-body paragraph and Primary button occupy the right third, aligned with the bottom of the name; 40px separates support from action. Layers are flat canvas, sparse edge geometry, giant dark lettering, then support and action. Within 900px the complete opening and action are visible and the top of the adjoining capability grid appears; the cards' supporting paragraphs continue below the fold.

**Transfer:** Make the new product name or a concise category phrase the main object; no hero artwork is needed. Keep a two-line name, orange punctuation and narrow technical support. Manifesto-led brand pages instead open with a centered 732px-wide column of 50.5px prose, beginning with parallel everyday outcomes.

**Avoid:** Do not replace this stage with a centered slogan over a dashboard, a stock photograph or a row of floating cards; do not enlarge the technical paragraph to rival the product name.

**Text style:** `display` — esBuild 500 · 184.2px/0.85 · tracking -0.045em

### Adjoining capability layers

**Observed:** Capability cards form three equal edge-to-edge columns with no gaps. Each uses a Dot category chip at top, generous internal blank space, a heading near the lower half and compact technical-body text below.

**Transfer:** Use for a small set of complementary layers or offerings; retain the equal ruled construction rather than presenting unrelated promotional tiles.

**Text style:** `heading` — esBuild 500 · 50.5px/0.95 · tracking -0.03em

### Saturated technical chapter

**Observed:** Olive chapter uses 56px top padding, a broad left-aligned white chapter-statement and a much smaller technical paragraph positioned lower at the right. The Multiplied technical emblem anchors the bottom of the 1044px field. Specification ticker strips bridge the light and saturated regions.

**Transfer:** Pair one substantial capability promise with one factual explanation and an original tone-on-tone schematic. The typography, not a photo, should dominate.

**Text style:** `chapter-statement` — esBuild 500 · 89.8px/0.9 · tracking -0.035em

### Quantified data-object proof

**Observed:** A centered proof-heading, preceded by a small uppercase orange status line, leads into the Luminous data sculpture. The section has 140px top padding, 32px side gutters and an open interval of about 207px before the object begins.

**Transfer:** Turn a verified measure of reach, volume or connectivity into a calm spatial data scene; keep labels sparse and the headline clear of the object.

**Text style:** `proof-heading` — esBuild 500 · 67.3px/0.95 · tracking -0.035em

### High-voltage conversion band

**Observed:** Orange conversion field is 605px tall with a huge white conversion-display and a Conversion button at its lower left. The Cropped conversion emblem sits behind the content and runs beyond the right edge.

**Transfer:** Give the reader a direct next step, with one short command and one action; let the emblem provide scale without extra copy.

**Text style:** `conversion-display` — esBuild 500 · 159.6px/0.8 · tracking -0.05em

### Monumental closing identity

**Observed:** Billboard footer returns immediately to ivory. Brand and social marks form a restrained upper row; the two uppercase closing rows consume most of the width, then small navigation and a compact action conclude the page.

**Transfer:** Make a fresh positioning statement into a typographic lockup, distributing words instead of stretching letterforms. Preserve the switch from monumental promise to tiny utilities.

**Text style:** `closing-billboard` — esBuild 500 · 135.5px/0.95 · tracking -0.01em · uppercase

### Progressive manifesto

**Only for:** manifesto-led brand pages

**Observed:** Left-aligned essay-display prose lives in a centered 732px column. Parallel short statements expand into longer arguments, separated by 45px. Upcoming words are stone gray and active passages become brown-black; orange pixel fragments remain near the outer edges. It ends in the same Billboard footer, without a separate saturated conversion band.

**Transfer:** Use this quieter variant for a single persuasive thesis. Establish everyday consequences, name the problem, state the differentiator and finish with a concise promise.

**Text style:** `essay-display` — esBuild 500 · 50.5px/1 · tracking -0.03em

## Page flow

**Storyline:** clear product promise → explanation of the offer → technical and spatial proof → direct action → monumental positioning and utilities

### Product and platform landing page

1. **Promise** — Large stacked product name opposite a narrow explanation and outlined action.
2. **Offer structure** — Three touching ruled capability panels with cumulative dot labels.
3. **Technical proof** — Specification strips and an olive typographic chapter with embedded schematic.
4. **Quantified proof** — Centered factual headline over a pale data sculpture.
5. **Closing call** — Full-width orange statement with a single capsule action and cropped emblem.
6. **Brand closure** — Ivory two-line billboard footer and compact utilities.

**Transfer:** Use this as the default product-page vocabulary, adapting the number and order of proof blocks to the offer rather than copying a fixed sequence.

### Manifesto-led brand introduction

1. **Recognizable outcomes** — Parallel everyday examples begin a large single-column essay.
2. **Problem framing** — Brief contrast statements name a growing constraint.
3. **Differentiation** — Longer large-type paragraphs explain why the product matters.
4. **Final promise** — A concise scale-oriented declaration concludes the essay.
5. **Brand closure** — The same monumental ivory footer provides navigation and an action.

**Transfer:** Use when persuasion is primarily verbal; keep the essay reveal and geometric punctuation rather than introducing a conventional feature-card hero.

## Writing

Direct, industrial and calmly ambitious. Broad claims are expressed in plain language, then supported by concrete specifications and operational explanations rather than promotional flourish.

**Do not copy:** Do not reuse the Groq name, product names, logo, lightning asset, customer or partner names, funding announcement, source claims, performance figures, geographic totals or positioning line. Replace all with the new product's own identity and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use 'you' and 'your' to describe control and practical outcomes; use 'we' for a brand argument and the product name for technical assertions.
- **Rhythm:** Short, declarative headlines contrast with one compact explanatory paragraph. Parallel phrases and deliberate repetition create momentum; commands are brief and unembellished.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product opening | Product name as the headline, followed by a plain statement of what can be assembled or achieved. | 1–3 words in the name; 25–35 words in support | “[Brand] Platform”<br>“Build your perfect stack.” |
| Manifesto premise | Repeat a simple sentence structure around familiar outcomes, then identify their shared mechanism. | 3–5 words per opening statement | “Every customer served.”<br>“Training creates the possibility.”<br>“Inference creates the value.” |
| Capability explanation | Describe the underlying offer, then the practical benefit or control it gives the reader. | 15–25 words | “Dedicated bare-metal infrastructure, tuned for speed and reliability, with full control in your hands.” |
| Quantified proof | A current operational fact in a sentence; numbers remain inside the headline rather than isolated stat tiles. | 8–12 words | “Now operating 13 data centers across four continents” |
| Closing call | Put the core activity to work; a direct verb-led action follows. | 2–5 words | “Put inference to work”<br>“Start Building” |

**Words and phrasing to use:** build; control; dedicated; reliable; production-ready; at scale; full control in your hands

**Avoid:** magical; revolutionary; game-changing; unlock infinite possibilities; supercharge everything

**Rules:**

- Give technical specificity its own small mono paragraph; do not pack qualifications into the billboard headline.
- Describe a benefit as an outcome the reader recognizes before explaining the machinery behind it.
- Use verified numbers in sentence-like proof headings or continuous specification strips, not decorative statistics without context.
- Let parallel constructions do persuasive work; avoid exclamation points and breathless adjective stacks.

## Do's and Don'ts

### Do

- Keep the default canvas #f3f3ee and align major content to 32px side gutters.
- Set giant opening type at weight 500, line-height 0.85 and -0.045em tracking.
- Keep supporting technical prose around 16px/1.35 and roughly 335px wide in the opening.
- Use 1px #cecebf rules and zero-gap adjoining cards.
- Retain dot-matrix uppercase labels with 0.08em tracking across navigation and actions.
- Make color fields full-width and deliberate: olive for a capability chapter, vermilion for a conversion chapter.
- Include the pale dotted data-object stage with sparse orange routes or equivalent truthful connections.
- Close with a two-line 135.5px uppercase positioning billboard, followed by small utilities.

### Don't

- Do not turn the 500-weight display into heavy 700-weight tech typography.
- Do not add drop shadows, beveled panels or glass effects to the flush ruled capability grid.
- Do not round ordinary cards to 16px or 24px; those curves belong to chips and actions.
- Do not use the dot-matrix face for multi-sentence support paragraphs; that role belongs to the mono family.
- Do not scatter orange fills through every panel; the ivory regions must remain continuous and calm.
- Do not substitute a dark neon globe for the near-white data sculpture; it should almost dissolve into the ivory.
- Do not convert the closing identity into a conventional dense multi-column sitemap.
- Do not center all text: the opening, technical chapter and cards are left aligned; the data-proof heading is the centered exception.

## Motion and responsive

### Motion

**Observed:**

- Utility links declare color 0.15s ease-in-out; buttons declare color 0.25s ease-in-out.
- Specification strips are horizontally translated and clipped at the viewport edges.
- The manifesto advances from pale stone words to dark active passages as the reader progresses.
- Data-location elements declare opacity and filter transitions of 0.35s cubic-bezier(0.19,1,0.22,1), with visibility 0s.

**Transfer:**

- Use motion to guide attention through technical text and the edge-clipped specification strip, not to float card surfaces.
- Keep geometric decoration out of the reading column and preserve the calm data-object stage.

**Unknown:**

- Ticker speed, data-object rotation, reveal synchronization and complete button background transitions are not specified.

### Responsive

**Observed:**

- Styles declare width breakpoints at 481px, 599px, 600px, 959px, 960px, 1280px and 1600px.

**Transfer:**

- On narrow screens, preserve the hierarchy of large product name, small technical explanation and outlined action; stack the support below the name when the two-column relationship no longer fits.
- Retain shared dividers when capability panels stack. Reflow the closing statement into balanced rows instead of shrinking it to utility scale.
- Crop the data object within its section and keep its annotations readable rather than compressing all paths into the headline.

**Unknown:**

- Exact mobile layouts, breakpoint-specific font sizes and navigation replacement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
