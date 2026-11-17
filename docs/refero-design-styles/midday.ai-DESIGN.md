# Midday — serif meets ledger

## Overview

An editorial face for practical software: expansive white space, bookish serif headlines and matter-of-fact sans-serif detail. White, warm stone and charcoal dominate, with color largely confined to the working interface and tiny status signals. Large interface demonstrations, lightly skewed testimonial cards and a monumental outlined wordmark make the otherwise sparse pages feel tangible. It suits tools that promise less operational friction rather than spectacle.

### Essentials

- Book-cover headlines meet ledger-like detail: regular Hedvig Letters Serif at 72px/1 with -0.025em tracking opens the default landing page; recurring section titles shrink to 24px/32px rather than competing with the opening.
- A centered promise leads into a dark product stage: a 768px headline column, 576px support column and one 138×44px action sit above a 1248px-wide monochrome demonstration. Its top enters the first 900px; the working detail continues below.
- Conversion is rectangular, compatibility is rounded: primary actions have square corners, #18181b fill and 14px/20px medium text; 34px-high integration chips use 9999px radii and 1px stone outlines.
- Nearly the whole page is white or warm neutral: #e6e4e0 marks icon squares, summary panels and giant lettering; #dbdad7 draws thin edges. Green is a tiny 8px operational signal, not a marketing wash; saturated hues belong mainly inside product demonstrations.
- Proof looks like paperwork, not glossy tiles: white square-edged cards use 1px borders, 20–24px padding and no elevation; include a warm-stone aggregate proof panel with a right-aligned 48px/1 number.
- The ending becomes typography-as-object: include an oversized sans word sculpture with warm-stone fill and a 1px gray outline, clipped at the sides and bottom. The desktop lettering is 508px/1; use the new identity or a short meaningful word, even when no product media is available.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm stone | `#e6e4e0` | `--color-stone` | surface, background, text | Summary panels, icon squares, announcement band and oversized closing letters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal action | `#18181b` | `--color-action` | action, background, border, text | Primary button fill, sign-in text and emphasized plan outline. |
| Reading ink | `#121212` | `--color-ink` | text, link | Headlines, active labels and primary reading text. |
| Secondary gray | `#616161` | `--color-muted` | text, link, border | Support copy, navigation, secondary links, icons and the word sculpture outline. |
| Paper edge | `#dbdad7` | `--color-edge` | border | Card outlines, rules and chip edges. |
| Button white | `#fafafa` | `--color-on-action` | text | Text on charcoal actions. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | The continuous page and default card surface. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#22c55e` | `--color-status` | accent | Tiny operational status dot and its translucent pulse; never a broad section fill. |

## Typography

- **Hedvig Letters Sans** — Body copy, navigation, actions, numerals and oversized closing lettering. Open, unforced sans-serif with regular-weight detail and a distinctly editorial softness. Font stack: "Hedvig Letters Sans", system-ui, arial, sans-serif.
- **Hedvig Letters Serif** — Opening promises and recurring section titles. Literary serif with lively stroke contrast and expressive letter shapes, kept upright and regular. Font stack: "Hedvig Letters Serif", Georgia, "Times New Roman", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| word-sculpture | Hedvig Letters Sans | 400 | 508px | 1 | normal | Decorative closing identity, with outline and intentional clipping. |
| display | Hedvig Letters Serif | 400 | 72px | 1 | -0.025em | Default centered landing headline, usually two balanced lines. |
| stat | Hedvig Letters Sans | 400 | 48px | 1 | normal | Single aggregate benefit number in a warm-stone summary card. |
| heading | Hedvig Letters Serif | 400 | 24px | 32px | normal | Recurring section headings and process introduction. |
| closing-line | Hedvig Letters Sans | 400 | 20px | 1.4 | normal | Short right-aligned footer proposition; process step titles use the same scale. |
| hero-support | Hedvig Letters Sans | 400 | 18px | 28px | normal | Opening support line; also quantitative card titles. |
| body | Hedvig Letters Sans | 400 | 16px | 1.5 | normal | Section support paragraphs and standard body text. |
| label | Hedvig Letters Sans | 400 | 14px | 20px | normal | Navigation, text links, footer headings and compact card descriptions. |
| button | Hedvig Letters Sans | 500 | 14px | 20px | normal | Primary conversion actions. |
| tile-label | Hedvig Letters Sans | 400 | 14px | 1.5 | normal | Centered capability names and short descriptions under icon squares. |
| quote | Hedvig Letters Sans | 400 | 14px | 1.625 | normal | Longer testimonial text. |
| caption | Hedvig Letters Sans | 400 | 12px | 16px | normal | Trial reassurance, short announcement pill and small supporting annotations. |
| proof-label | Hedvig Letters Sans | 400 | 12px | 16px | 0.025em | Sentence-case labels above quantified proof. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| dedicated feature landing pages | feature-display | Hedvig Letters Serif | 400 | 128px | 1 | normal | Single-line benefit promise above a large interface demonstration. |
| company essays | article-title | Hedvig Letters Serif | 400 | 30px | 1.3 | normal | Restrained centered title for a prose-led page. |
| feature chapters and pricing comparisons | feature-heading | Hedvig Letters Sans | 400 | 24px | 32px | normal | Left-aligned headings beside interface studies; also compact plan prices. |
| company essays | article-body | Hedvig Letters Sans | 400 | 16px | 26px | normal | Long-form explanatory paragraphs. |
| dedicated feature landing pages | feature-eyebrow | Hedvig Letters Sans | 400 | 12px | 16px | 0.05em, uppercase | Category marker above the feature promise. |

**Notes:**

- The serif carries the promise while the sans explains the mechanics. Use regular weight almost everywhere; medium is reserved for conversion labels and occasional prose emphasis.
- Only the default large headline tightens tracking. Small labels remain normal except for lightly spaced proof captions and uppercase feature eyebrows.
- Closing lettering is an independent decorative scale, not another reading heading. Its outline and clipping are as important as its size.

## Layout

**Density:** Airy section composition around compact administrative detail: broad white intervals surround small cards, labels and interfaces.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and inline chip spacing. |
| 12px | Action-to-reassurance gap, chip side padding and testimonial-row spacing. |
| 16px | Section heading-to-support gap, card-grid gutters and paragraph separation. |
| 20px | Quantified proof card padding. |
| 24px | Panel and testimonial padding; opening headline-to-support separation. |
| 40px | Opening support-to-action interval and capability-row spacing. |
| 48px | Section introduction-to-content gap and article title-to-prose gap. |
| 64px | Two-column demonstration gutter and footer top padding. |
| 80px | Horizontal gap between capability tiles. |
| 96px | Default major section top and bottom padding. |
| 128px | Prose opening top padding and separation between large feature chapters. |
| 192px | Default opening content top padding below the announcement offset. |

### Containers and grids

- **Main container**: max width 1280px · side padding 16px. Centered outer marketing container. At 1440px it gives a 1248px content span and 96px effective side margins; nested 1400px maxima do not expand it.
- **Opening copy**: max width 768px. Centered headline width; support narrows to 576px.
- **Section introduction**: max width 672px · side padding 16px. Centered supporting paragraph under the serif section title.
- **Demonstration split**: 2 columns · gap 64px. Equal 592px columns at desktop, with copy vertically centered beside a tall working interface; alternate the demonstration side.
- **Quantified proof grid**: 3 columns · gap 16px. Three equal compact cards followed by a row with a narrower card and a wide aggregate panel.
- **Capability matrix**: 4 columns · gap 80px. Centered 150px-wide icon-and-caption tiles, with 40px between rows.
- **Testimonial row**: max width 1024px · gap 12px. Four narrow cards centered in a gently irregular desktop row.
- **Footer container**: max width 1400px · 2 columns · gap 64px · side padding 32px. Link groups on the left; short proposition and trust controls on the right. Four populated link columns occupy part of the left half.
- **Pricing comparison** (only for pricing comparisons): max width 800px · 2 columns · gap 28px. Two equally sized square-edged plan columns.
- **Essay column** (only for company essays): max width 896px · side padding 32px. 832px reading span at desktop for prose and a full-column portrait.

## Corner radius

| Element | Radius |
| --- | --- |
| Cards and primary actions | 0px |
| Chips and announcement pill | 9999px (pill) |
| Status dot | 50% |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Continuous background across the page.

**CSS:** `background: #ffffff; color: #121212`

**Observed:** Section boundaries are white space and occasional hairlines rather than alternating color bands.

**Transfer:** Keep the background uninterrupted through most of the narrative.

#### Paper card · level 1

**Use:** Proof, testimonial, pricing and demonstration panels.

**CSS:** `background: #ffffff; border: 1px solid #dbdad7; border-radius: 0px; box-shadow: none`

**Observed:** Flat, square-edged panels sit on the same white as the surrounding page.

**Transfer:** Let the edge carry the grouping; use real content density instead of elevation.

#### Stone panel · level 1

**Use:** Aggregate proof, concise checklists and icon backing.

**CSS:** `background: #e6e4e0; border: 1px solid #dbdad7; border-radius: 0px; box-shadow: none`

**Observed:** Warm gray is a local emphasis surface, not a full-page tint.

**Transfer:** Choose one compact summary or proof grouping to receive this emphasis.

#### Navigation veil · level 2

**Use:** Fixed navigation under the announcement strip.

**CSS:** `background: rgba(255,255,255,0.8); backdrop-filter: blur(12px)`

**Observed:** White translucency allows underlying dark media to soften through the navigation while text stays crisp.

**Transfer:** Keep the blur confined to the navigation, not every card.

#### Announcement band · level 2

**Use:** Thin full-width news strip above navigation.

**CSS:** `background: #e6e4e0; border-bottom: 1px solid #dbdad7`

**Observed:** A 37px band holds a centered short announcement with an underlined link.

**Transfer:** Use for a real timely update, with the rest of the page retaining its own promise.

#### Marquee edge fade · level 2

**Use:** Soft horizontal termination of moving compatibility chips.

**CSS:** `background: linear-gradient(to right, #ffffff 0%, #ffffff 30%, rgba(255,255,255,0.8) 50%, rgba(255,255,255,0.4) 70%, rgba(0,0,0,0) 100%); width: 128px; height: 80px; pointer-events: none`

**Observed:** The right edge mirrors the left gradient. Two 34px rows sit 12px apart.

**Transfer:** Fade chips into the surrounding white rather than cutting them against a visible container border.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #18181b; color: #fafafa; border-radius: 0px; padding: 8px 24px; height: 44px`

**Text style:** `button` — Hedvig Letters Sans 500 · 14px/20px

**Observed:** A single compact filled action anchors the centered opening. Pricing uses full-width 36px-high actions: outlined for the entry plan, charcoal for the emphasized plan.

**States:** Declared: hover background-color hsl(240 5.9% 10% / .9); focus-visible outline-offset 2px and transparent 2px solid outline.

### Fixed navigation

**Use:** Persistent orientation without a heavy header block.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 56px; padding: 16px 24px; gap: 24px; backdrop-filter: blur(12px)`

**Text style:** `label` — Hedvig Letters Sans 400 · 14px/20px

**Observed:** A small 24px identity mark sits left; sparse text links align right with dropdown chevrons and a vertical divider before sign-in. It sits beneath the news strip on the Navigation veil.

### Integration chip

**Use:** Compatibility evidence and feature-mode labels.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 6px 12px; height: 34px; background: #ffffff; border: 1px solid #dbdad7; border-radius: 9999px; white-space: nowrap`

**Text style:** `label` — Hedvig Letters Sans 400 · 14px/20px

**Observed:** A 16px tool mark precedes the text. In capability chapters the same shell can be a text-only non-action tag.

**States:** Declared: hover border-color hsl(0, 0%, 7% / .2).

### Text link

**Use:** Secondary exploration and footer navigation.

**CSS:** `color: #616161; font-size: 14px; line-height: 20px; font-weight: 400`

**Text style:** `label` — Hedvig Letters Sans 400 · 14px/20px

**Observed:** Section-ending links are centered and underlined; footer links are unadorned in narrow columns with 10px vertical gaps. Keep the variant tied to its context.

**States:** Declared: hover color hsl(0, 0%, 7%).

### Capability tile

**Use:** An easily scanned product breadth matrix.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 60px; height: 60px; background: #e6e4e0; border: 1px solid #dbdad7; border-radius: 0px; margin-bottom: 16px`

**Text style:** `tile-label` — Hedvig Letters Sans 400 · 14px/1.5

**Observed:** The CSS describes the icon square; a 24px gray icon sits inside. A centered name and a muted one-line descriptor sit outside below it in a 150px-wide column.

### Quantified proof card

**Use:** Translate a routine friction into a legible cost.

**CSS:** `background: #ffffff; border: 1px solid #dbdad7; border-radius: 0px; padding: 20px; overflow: hidden`

**Text style:** `hero-support` — Hedvig Letters Sans 400 · 18px/28px

**Observed:** A lightly tracked 12px sentence-case label precedes an 18px quantified title and a 14px gray explanation, separated by 4px intervals. Desktop cards are about 405×134px.

**Transfer:** Use real task costs, cycle times or counts appropriate to the new product.

### Aggregate proof panel

**Use:** Resolve several smaller costs into one memorable total.

**CSS:** `background: #e6e4e0; border: 1px solid #dbdad7; border-radius: 0px; padding: 24px; overflow: hidden`

**Text style:** `stat` — Hedvig Letters Sans 400 · 48px/1

**Observed:** A wide panel pairs a small left-aligned explanation with a single large right-aligned total, vertically centered. It takes seven of ten columns beside a smaller card in the lower proof row.

**States:** Declared: hover border-color hsl(0, 0%, 38%).

### Testimonial paper

**Use:** Human proof in a row of narrow notes.

**CSS:** `display: flex; flex-direction: column; gap: 16px; background: #ffffff; border: 1px solid #dbdad7; border-radius: 0px; padding: 24px`

**Text style:** `quote` — Hedvig Letters Sans 400 · 14px/1.625

**Observed:** Country in tiny uppercase, avatar and name, organization, then the quote. Slight rotations include -1deg; the row resembles loose paper rather than a rigid dashboard. A small star summary sits above the row.

### Checklist panel

**Use:** Concrete reassurance after a broader benefit statement.

**CSS:** `background: #e6e4e0; border: 1px solid #dbdad7; padding: 24px; max-width: 672px; border-radius: 0px`

**Text style:** `label` — Hedvig Letters Sans 400 · 14px/20px

**Observed:** Five 20px-high rows are separated by 24px, with small outlined check squares, a 12px icon-to-copy gap and dark text. A centered underlined Text link follows the panel.

**Transfer:** Use a concise set of outcomes or assurances, with no decorative badges.

### Plan card

**Only for:** pricing comparisons

**Use:** Compare tiers with restrained emphasis.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid #dbdad7; border-radius: 0px; padding: 24px 16px`

**Text style:** `body` — Hedvig Letters Sans 400 · 16px/1.5

**Observed:** Plan name, short gray positioning line, 24px price and small billing caption precede a hairline and compact bulleted feature list. The emphasized plan changes the outline to charcoal and carries a small outlined pill straddling the top-right edge. Bottom-aligned actions preserve equal card heights.

## Imagery and graphics

### Monochrome product theater

**Use:** Large first product reveal and principal visual proof.

**Observed:** A wide near-black-to-gray grainy field backs an inset white desktop interface. The backing is brightest toward the upper right and dark at the left; crisp rectilinear UI contrasts with the soft, noisy illumination. At desktop the backing spans 1248×900px and the interface about 1034px wide, extending beyond the first screen.

**Transfer:** Show a real working view of the new product on the same monochrome stage. If there is no interface, use a clean white schematic or an artifact of the workflow rather than unrelated stock imagery.

**Build:** Create a 1248px-wide clipped rectangle. Layer a charcoal base, a broad radial gray highlight near 85% 10%, and a subtle grayscale SVG feTurbulence texture at low opacity. Keep all light neutral, with a soft transition into the dark left half. Inset the white product view about 8% from each side and 12% from the top; leave the corners square. Match the soft grain and illumination; exact gradient stops are not essential.

### Working interface studies

**Use:** Process explanations and alternating capability chapters.

**Observed:** White bordered interface fragments show tables, documents, small stats and matching workflows with restrained green or blue status marks. They are framed as flat working documents, not perspective devices. Large panels occupy roughly half a split section, with far less text beside them.

**Transfer:** Reduce the new workflow to one believable task per panel. Preserve table rules, ample white backing and small labels without copying every detail of the full app.

### Small tangible object

**Use:** A compact material cue above a reassurance section.

**Observed:** A grayscale folder-like object with sheets peeking out sits centered above the serif heading. Its soft dimensional shading and small scale contrast with otherwise flat UI and icons.

**Transfer:** Use one relevant grayscale workflow object, such as a folder, tray or document stack. Keep it small enough that it reads as a chapter marker rather than a mascot.

**Build:** For a minimal version, assemble a 112×96px SVG with two off-white sheets behind a rounded folder silhouette, a small top tab and a vertical light-to-gray gradient. Add a faint contact shadow and restrained edge highlights; do not tint the object with a brand accent.

### Closing word sculpture

**Use:** Signature decorative ending on every page type.

**Observed:** Huge warm-stone lowercase sans lettering has a fine gray outline. The word is wider than the viewport and its lower portion is hidden by the footer boundary; it remains behind and below usable navigation and status text.

**Transfer:** Use the new identity or a short relevant word, scaled to overflow the width. Preserve the neutral fill and thin outline instead of treating it as another headline.

**Build:** Use live sans text at 508px with line-height 1, #e6e4e0 fill and -webkit-text-stroke:1px #616161. Position at the bottom center of an overflow-hidden footer, translate horizontally -50% and vertically 40%. Reserve about 320px bottom padding so utility text stays separate. Adjust width for the new word, keeping deliberate side and bottom clipping.

### Graph-paper feature stage

**Only for:** dedicated feature landing pages

**Use:** Backing behind the larger feature promise and interface reveal.

**Observed:** Very faint orthogonal lines appear behind the text and large pale interface, then fade into white around the perimeter. The interface is 1152px wide and continues below the opening viewport.

**Transfer:** Use the grid to give a document or interface a technical stage without adding a colored hero panel.

**Build:** Layer two repeating linear gradients at right angles using rgba(97,97,97,0.06) for 1px lines on a roughly 44px grid, over white. Mask the layer with a broad radial fade toward the edges. Place the interface in front and add a 150px white fade at its lower boundary. Keep grid contrast secondary to the headline.

### Editorial portrait

**Only for:** company essays

**Use:** Human sign-off after long-form prose.

**Observed:** A full-column founders image is framed at 832×450px with centered cover fitting; short captions follow below.

**Transfer:** Use an authentic team or maker portrait at the reading column width, followed by a concise attribution.

### Icons

**Observed:** Small mostly monochrome SVG marks: 24px capability icons centered in 60px squares, 16px integration marks, 14px checks and 18px muted marks under the opening action. The forms are restrained functional pictograms, not expressive illustrations.

**Transfer:** Choose simple document, tool and workflow symbols with consistent visual weight; use gray for supporting icons and reserve recognizable colored marks for actual integrations.

## Section recipes

How recurring sections are built.

### First screen: Centered editorial opening

**Observed:** The white canvas sits behind a thin fixed announcement band and translucent navigation. A centered copy stack begins after 192px of top padding below the announcement offset: short outlined announcement pill, then a two-line 72px serif promise in a 768px column with 24px above it. The upright headline occupies a little over half the viewport width. A two-line 18px gray support paragraph narrows to 576px, followed after 40px by Primary button, then a 12px reassurance line after 12px and a small muted tool-mark row. All of that is visible within the first 900px. The Monochrome product theater enters near the bottom, beginning at about 712px; only the upper interface is visible before the fold, while the full working view extends below.

**Transfer:** Lead with a short product-category promise and a clear audience or outcome. Reproduce the centered hierarchy and strong dark-to-white product reveal with a real interface or a tidy workflow schematic. Dedicated feature pages instead use the scoped 128px one-line serif promise, uppercase category and faint grid behind the interface, without inserting a hero button. Prose-led company pages open with the scoped 30px title and move directly into text.

**Avoid:** Do not turn the opening into a conventional left-copy/right-device split, put the entire demonstration above the fold, or replace the serif with a bold geometric slogan.

**Text style:** `display` — Hedvig Letters Serif 400 · 72px/1 · tracking -0.025em

### Section heading pair

**Observed:** A 24px/32px centered serif title is followed by 16px/24px muted support with a 16px gap, within the Section introduction width. Content generally starts 48px later and sections use 96px vertical padding.

**Transfer:** Use a short result-led heading and a single plain-language explanatory sentence.

**Text style:** `heading` — Hedvig Letters Serif 400 · 24px/32px

### Process with active step

**Observed:** A two-column composition places a compact serif process heading and three sans step titles beside a tall Working interface study. A thin vertical guide with small square markers aligns the step list; the active step is dark, inactive steps are pale, and a short 14px explanation appears beneath the active title.

**Transfer:** Explain one small sequence with a visibly active stage and one corresponding artifact, not several unrelated interface views.

### Alternating feature chapter

**Observed:** Equal columns with a 64px gutter pair vertically centered copy and a tall flat interface artifact. Scoped 24px sans headings precede 16px body text after 20px; Integration chips wrap beneath. The next chapter reverses the panel side.

**Transfer:** Tie each chapter to a concrete task; vary panel content while keeping the same flat document-like framing.

**Text style:** `feature-heading` — Hedvig Letters Sans 400 · 24px/32px

### Capability matrix

**Observed:** Section heading pair introduces two centered rows of four Capability tiles. Each tile column is 150px wide, with 80px between columns and 40px between rows.

**Transfer:** Use a compact taxonomy of the new product's capabilities; captions should clarify the icon rather than restate the headline.

### Cost-to-total proof

**Observed:** Section heading pair leads to three Quantified proof cards with 16px gutters. A second row places a smaller cost card beside Aggregate proof panel, whose 48px total is aligned right.

**Transfer:** Make the wide summary the payoff to credible smaller facts. The proof device belongs in the visual language, but its subject and position can vary.

### Tangible reassurance

**Observed:** Small tangible object precedes Section heading pair. A 672px Checklist panel follows, with a centered underlined Text link beneath and generous white space around it.

**Transfer:** Turn complex reassurance into a short checkable set of outcomes; choose the object according to the workflow.

### Loose-paper social proof

**Observed:** Section heading pair and a small monochrome star row lead to four Testimonial paper cards. Tiny country labels, small avatars and slight rotations make the cards feel collected. A centered Text link closes the group.

**Transfer:** Use genuine attributed accounts. Keep the narrow note-like proportions even when quotations vary in length.

### Compatibility ribbons

**Observed:** Section heading pair is followed after 40px by two moving rows of Integration chips. Opposite directions and Marquee edge fade keep the wide set light rather than visually boxed.

**Transfer:** Use actual compatible tools or equivalent concrete ecosystem proof; the heading explains the relationship.

### Restrained plan comparison

**Observed:** Section heading pair leads to a compact monthly/yearly selector, then two Plan cards inside an 800px grid with 28px gap. Currency links and small reassurance sit below. The highlighted card stays white, distinguished by charcoal outline and dark action.

**Transfer:** Use this scoped composition when purchasing requires a comparison, not as a required section on every page.

**Text style:** `feature-heading` — Hedvig Letters Sans 400 · 24px/32px

### Prose chapter

**Observed:** A centered 30px serif title introduces an 832px reading span. Short 16px sans chapter headings and 16px/26px gray paragraphs use 16px internal gaps. Centered 320px hairline separators divide arguments; a full-column Editorial portrait signs off before the shared footer.

**Transfer:** Use for an origin, point of view or explanation that benefits from a linear argument rather than sales cards.

**Text style:** `article-body` — Hedvig Letters Sans 400 · 16px/26px

### Utility footer and monumental signature

**Observed:** The shared ending is an 850px white overflow-hidden footer, not a separate giant CTA band. Four compact link groups sit at left, with a 20px proposition and small trust/theme controls at right. A full-width hairline separates them from status at left and copyright at right. The Closing word sculpture fills the lower edge, with 320px bottom padding protecting utility content.

**Transfer:** Keep the closing identity graphic on every page type, adapt the link taxonomy and proposition, and show only real trust or operational indicators.

## Page flow

**Storyline:** Promise → working proof → task-level explanation → breadth and quantified relief → reassurance and human proof → ecosystem or purchase decision → utility links and monumental identity.

### Broad product introduction for an individual decision maker

1. **Promise** — Centered editorial opening with one action and concise reassurance.
2. **Product demonstration** — Large dark-backed interface, then an active-step explanation.
3. **Capability breadth** — Small icon matrix with concise descriptors.
4. **Quantified proof** — Routine costs resolve into a large neutral aggregate.
5. **Objection handling** — Tangible chapter marker and a checklist of operational outcomes.
6. **Social proof** — Collected testimonial papers and an exploration link.
7. **Ecosystem proof** — Two compatibility ribbons.
8. **Closing identity** — Utility footer with giant clipped outlined lettering.

**Transfer:** Adapt the beats to the product's buying questions; preserve the contrast between an editorial promise, concrete working artifacts and small-scale proof.

### Benefit-specific feature landing page with a purchase comparison

1. **Promise** — One-line oversized serif outcome, category marker and graph-paper interface stage.
2. **Capability chapters** — Two alternating copy-and-artifact studies with mode chips.
3. **Product breadth** — Compact capability matrix reconnects the feature to a larger system.
4. **Quantified proof** — Cost cards and aggregate benefit.
5. **Objection handling** — Checklist reassurance.
6. **Social and ecosystem proof** — Testimonial notes followed by compatibility ribbons.
7. **Pricing** — Two restrained plan cards with billing controls.
8. **Closing identity** — Shared utility footer and clipped word sculpture.

**Transfer:** Use the larger feature promise only when the benefit is short enough to remain a single strong statement; let detailed workflow proof carry the explanation.

### Company viewpoint or origin essay

1. **Editorial framing** — Small centered serif title rather than a product hero.
2. **Problem and argument** — Linear sans prose with modest chapter labels and short central rules.
3. **Human attribution** — Wide portrait with captions.
4. **Closing identity** — The same utility footer and giant outlined word sculpture.

**Transfer:** Replace sales modules with a clear argument while retaining the light palette, type pairing and shared monumental ending.

## Writing

Practical, plainspoken and sympathetic to people doing too much administrative work. Confidence comes from describing what happens and what disappears, not from hype.

**Do not copy:** Do not reuse the identity, logos, announcement, product-specific facts, bank coverage, time-saving numbers, prices, testimonial quotations, customer names or compliance claims. Source examples illustrate voice only; replace them with verified facts about the new product.

- **Addressing the reader:** Speak directly to the reader as you or your. Use we for an essay's intent and the product name when explaining a concrete capability.
- **Rhythm:** Short benefit headlines, often two balanced fragments, followed by one explanatory sentence. Longer prose uses compact paragraphs and everyday transitions; interface labels remain literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product category and audience, or state a direct outcome. | 3–8 words | “The business stack for modern founders”<br>“Get paid faster” |
| Section headline | Pair a removed burden with a gained benefit, or state readiness without extra effort. | 4–8 words | “Less admin. More focus.”<br>“Ready for accounting, without extra work” |
| Supporting line | Describe connected tasks or an everyday outcome in one concrete sentence. | 12–24 words | “Create invoices, send them to customers, and track payments while every update flows directly into your overview.” |
| Primary action | A direct verb phrase with ownership, without urgency. | 3–4 words | “Start your trial” |
| Reassurance | State real terms in short clauses separated by a middle dot. | 5–8 words | “14-day free trial · Cancel anytime” |
| Essay thesis | Explain the intended change in normal human language. | One short sentence | “Your business should stay organized and explain itself as it runs.” |
| Closing proposition | Contrast the reader's real job with the burden the product removes. | 6–8 words | “Run your company. Not the admin.” |

**Words and phrasing to use:** connected; organized; automatically; ready; without extra work; one system; clear; your workflow

**Avoid:** revolutionary; game-changing; unleash; 10x everything; ultimate platform; hurry; magic

**Rules:**

- Describe actions and consequences before naming technology.
- Prefer a concrete task or artifact over a broad innovation claim.
- Explain a number with the unit and context beside it.
- Keep action labels consistent; use descriptive underlined links for exploration.
- In essays, articulate a problem, an idea and a focus without turning each paragraph into a slogan.

## Do's and Don'ts

### Do

- Keep the default opening serif at 72px/1 and weight 400, with -0.025em tracking.
- Use 24px/32px serif section headings so the hero remains the clear typographic peak.
- Make major white sections breathe with 96px vertical padding and 16px heading-to-support gaps.
- Preserve square 1px-edged paper cards with 20–24px inner padding.
- Use 34px-high pill chips and 60px square capability icon backings as distinct shapes.
- Include the 48px aggregate proof treatment using verified product-relevant quantities.
- Keep the giant outlined closing lettering below the usable footer content.
- Use a neutral grainy product stage to give white interface media real contrast.

### Don't

- Do not round primary actions to match the integration pills; their 0px corners are intentional.
- Do not make every section heading 48px or heavier; the recurring title is only 24px and regular.
- Do not tint the entire canvas warm gray; #e6e4e0 is a local panel and lettering color.
- Do not add card drop shadows or floating glass tiles; grouping comes from #dbdad7 edges.
- Do not turn the 8px green status indicator into an accent-green campaign palette.
- Do not convert testimonial notes into large photographic quote billboards; they use small avatars and 14px text.
- Do not style plan emphasis as a saturated filled card; it remains white with a charcoal edge.
- Do not introduce arbitrary monospace or technical display fonts into administrative labels; the sans carries them.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions use 0.15s cubic-bezier(0.4, 0, 0.2, 1); many card transitions use all 0.2s with the same curve.
- Compatibility rows declare marquee-left at 30s linear infinite and marquee-right at 28s linear infinite; their group-hover rule pauses the motion.
- A small operational indicator has a translucent green pulse. Entry animation declarations include fadeInBlur at 0.35s ease-out and fadeInScale at 0.4s ease-out.

**Transfer:**

- Let the compatibility ribbons move gently in opposing directions, with white edge fades and hover pause.
- Use short border and color changes to reinforce the paper-card interaction rather than lifting cards with shadows.

**Unknown:**

- Exact scroll-trigger logic, timing of process changes and the full video choreography are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px, 1536px and 1800px.
- Main navigation links are desktop-only at the 1280px tier. Capability tiles declare a two-column narrow layout; proof cards declare one, two and then three columns.
- Major section padding declares 48px, 64px and 96px tiers. Decorative closing text declares 200px on narrow screens and 508px from the 640px tier.

**Transfer:**

- Use the declared column progression for the proof grid; stack copy and demonstration panels while preserving the white document framing.
- Keep the clipped closing word as a recognizable device at narrow widths using the 200px tier rather than removing it.
- Retain a compact centered serif opening and let its line count grow; keep the action visible before the main product stage.

**Unknown:**

- Exact mobile menu behavior, narrow-screen feature-hero arrangement and rendered mobile line breaks are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
