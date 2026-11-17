# Good Glyphs — mint pictographic poster

## Overview

A mint-green and black graphic poster with oversized grotesk lettering and an irreverent collection of monochrome drawings. It suits creative tools, independent products and participatory projects whose work can become the visual proof. The composition is dense and edge-to-edge, balancing monumental statements with tiny utilitarian credits and controls; there is no photographic polish or simulated depth.

### Essentials

- The name becomes a pictographic poster: uppercase Helvetica Neue at 288px/0.8, weight 400 and -0.03em tracking, with illustrated forms replacing selected letters in a two-line composition.
- Mint is the paper, not an accent: #c7ffcd covers almost the entire page; #000000 supplies every mark, outline and the single inverted demonstration panel. Keep the entire marketing palette to these two colors.
- Support copy has headline force: 72px/0.9 uppercase, weight 400 and -0.03em tracking, contrasted with 14px normal-case credits rather than intermediate tiers of promotional text.
- Controls look like drawn geometry: 1px black outlines, 105px circles beside a 105px-high elongated action with 140px radius; the primary label is 28px, weight 300, uppercase.
- The product is an exhibition of graphic specimens: center large, flat silhouettes or line drawings inside 461px square, 14px-radius outlined tiles in three columns with 14px visible gutters. For nonvisual products, create original black diagrams or pictograms of their functions.
- An inverted playground makes the work tangible: a full-width black panel with mint drawings, a small top-left invitation, a centered fine-line slider and a tiny reset icon. Use a small interactive diagram when there is no directly editable visual product.
- The ending stays deliberately small: leave the final gallery row incomplete rather than stretching its tiles, then use an 84px top margin before one left-aligned line of 14px/1.5 underlined utility links. No oversized closing sales banner.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint paper | `#c7ffcd` | `--color-mint` | background, surface, text, border, action | Continuous page canvas, outlined controls and reversed artwork and labels inside black regions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, border, action, link | All typography, drawings and hairline outlines; solid background of the interactive stage and selected specimen keys. |

## Typography

- **Helvetica Neue** — All readable text, including monumental titles, descriptions and controls. Neutral neo-grotesk, predominantly regular; light controls contrast with tight, uppercase poster text. If unavailable, use **Roboto**. Use 400 for poster text and 300 for action labels; preserve tight tracking and compact leading. Font stack: "Helvetica Neue", "Roboto", Helvetica, Arial, sans-serif.
- **good-glyphs** (only for graphic specimens) — Illustrated symbols rendered as font glyphs, not readable prose. A varied collection of silhouettes, wiry drawings, cartoon creatures and geometric emblems. Font stack: "good-glyphs", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Helvetica Neue | 400 | 288px | 0.8 | -0.03em, uppercase | size 20vw | Two-line product-name poster with selected letter positions occupied by drawings. |
| statement | Helvetica Neue | 400 | 72px | 0.9 | -0.03em, uppercase | size 5vw | Oversized explanatory paragraph and gallery section headings. |
| edition | Helvetica Neue | 400 | 72px | 0.8 | normal, uppercase | size 5vw | Small-in-relation-to-title superscript edition marker beside the product name. |
| action | Helvetica Neue | 300 | 28px | 1 | 0.025em, uppercase | fixed | Centered text within the elongated primary action. |
| utility | Helvetica Neue | 400 | 14px | 1.5 | normal | fixed | Utility text default for the footer. Credits, specimen labels, stage invitation and explanatory text use the same family, size and weight with normal line-height. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| graphic specimens | stage-art | good-glyphs | 400 | 288px | 1 | normal | fixed | Mint pictograms inside the inverted playground. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Poster text uses negative tracking and leading tighter than its size, while utility text keeps normal tracking and leading.
- Use normal-case labels at 14px to make the 72px statements and 288px name feel even more monumental. Do not introduce a conventional ladder of medium-sized subheadings.
- The illustrated font is artwork, not a text alternative. Original SVG drawings can occupy its role without inheriting its literal character codes.

## Layout

**Density:** Dense poster composition with very narrow outer margins, tight text stacking and spacious interiors only within specimen tiles.

### Spacing

| Value | Use |
| --- | --- |
| 7px | Body side inset and half of the visible gallery gutter. |
| 14px | Panel margin, tile inner label inset, visible gallery gutter and footer bottom padding. |
| 28px | Right margin between footer links. |
| 42px | Bottom breathing room inside the inverted stage. |
| 84px | Top margin before the tiny footer. |

### Containers and grids

- **edge-to-edge canvas**: side padding 7px. Fluid full-width composition without a maximum-width container; an additional 7px inset places panels and tile borders 14px from the viewport edge.
- **specimen grid**: 3 columns · gap 14px. Equal square tiles, 461px per side at a 1440px viewport. Each occupies a roughly 475px layout cell including inset gutters; incomplete final rows remain left-aligned.
- **conversion row**: 12 columns · gap 14px. Five circular choices each occupy one twelfth of the usable row; the elongated action fills the remaining seven twelfths. All controls share the same height.
- **explanatory note**: side padding 7px. A short paragraph beneath the conversion row occupies half the desktop width, leaving the right half open.

## Corner radius

| Element | Radius |
| --- | --- |
| panels and tiles | 14px |
| primary action | 140px |
| amount choices | 50% |

## Surfaces and depth

### Surfaces

#### Mint canvas · level 0

**Use:** The continuous material behind all sections.

**CSS:** `background: #c7ffcd; color: #000000`

**Observed:** One uninterrupted flat field; no texture, gradient or alternating neutral bands.

**Transfer:** Let the colored paper remain visible inside tiles and around every component.

#### Outlined specimen · level 1

**Use:** Framing individual drawings or product examples.

**CSS:** `background: #c7ffcd; border: 1px solid #000000; border-radius: 14px; box-shadow: none`

**Observed:** The frame groups content without creating elevation or a different fill.

**Transfer:** Keep the canvas visible through the tile; use the border rather than color or shadow to separate items.

#### Inverted stage · level 1

**Use:** Interactive graphic demonstration.

**CSS:** `background: #000000; color: #c7ffcd; border: 1px solid #c7ffcd; border-radius: 14px; padding-bottom: 42px`

**Observed:** A wide, shallow black field is the only substantial interruption in the mint paper.

**Transfer:** Reserve the solid black area for live work or a compelling graphic demonstration, not ordinary copy.

## Components

### Project credit

**Use:** Minimal identity and attribution at the upper right instead of a navigation bar.

**CSS:** `position: absolute; text-align: right; padding: 0 7px; font-size: 14px; color: #000000`

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

**Observed:** A short plain-text prefix followed by one underlined studio link sits in the unused space beside the first title line.

**Transfer:** Use a maker credit or one discreet product-home link, keeping the poster dominant.

### Primary action

**Use:** Main conversion beside round choices.

**CSS:** `background: #c7ffcd; color: #000000; border: 1px solid #000000; border-radius: 140px; height: 105px; text-align: center`

**Text style:** `action` — Helvetica Neue 300 · 28px/1 · tracking 0.025em · uppercase

**Observed:** The wide capsule shares its baseline and height with the circular controls. Its label remains visually light rather than bold.

**States:** Declared: hover background #000 and color #c7ffcd; focus-visible unknown.

**Transfer:** Pair two concrete verbs when the action has two meaningful outcomes.

### Round choice

**Use:** Preset amounts or compact numeric selections.

**CSS:** `width: 105px; height: 105px; border: 1px solid #000000; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: #000000; line-height: normal; letter-spacing: normal; text-transform: none`

**Text style:** `action` — Helvetica Neue 300 · 28px/1 · tracking 0.025em · uppercase

**Observed:** Four presets are followed by a matching custom-value circle with a currency prefix and underlined input.

**Transfer:** Use for genuinely short choices; retain the distinctive circle-and-capsule relationship.

### Custom amount input

**Use:** Freeform numeric choice inside the last round control.

**CSS:** `width: 59px; height: 35px; border-bottom: 1px solid #000000`

**Observed:** The field is a short underline after a currency symbol, not a separate rectangular input.

**Transfer:** Use the same treatment for a numeric override when a preset row needs it.

### Interactive stage

**Use:** A tangible product playground with simple controls.

**CSS:** `background: #000000; color: #c7ffcd; border: 1px solid #c7ffcd; border-radius: 14px; padding-bottom: 42px; position: relative`

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

**Observed:** A tiny invitation at top left, fine-line horizontal slider near the center and reset icon at top right sit above a left-aligned row of oversized mint specimens. The panel is 413px tall at desktop.

**Transfer:** Expose one immediately understandable adjustment and one reset action. Keep the artwork much larger than the controls.

### Specimen card

**Use:** Repeated gallery item.

**CSS:** `border: 1px solid #000000; border-radius: 14px; overflow: hidden; position: relative; aspect-ratio: 1`

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

**Observed:** An underlined attribution sits at the upper left with miniature variant keys immediately after it. Large black artwork is centered below; each card can contain multiple variants.

**Transfer:** Use original pictograms, diagrams or monochrome product outputs rather than a feature title and paragraph.

### Variant key

**Use:** Small controls for switching artwork within a specimen.

**CSS:** `color: #c7ffcd; background: #000000; border: 1px solid #c7ffcd; border-radius: 10%; padding: 3.5px 4.2px 1.4px; margin-right: 3.5px`

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

**Observed:** The selected key is black-filled with mint lettering; unselected keys have black lettering and a black outline on the mint canvas. Labels are tiny letter-like markers, not wide tabs.

**Transfer:** Use terse variant identifiers and preserve the compact typewriter-key feel.

### Underlined text link

**Use:** Credits, supporting details and attribution.

**CSS:** `color: #000000; text-decoration: underline`

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

**Observed:** Native-looking text links, without arrows, icons or surrounding capsules.

**Transfer:** Keep supporting links visually modest so they never compete with the drawn controls.

### Utility footer

**Use:** Final copyright and utility links.

**CSS:** `margin-top: 84px; padding: 0 7px 14px; color: #000000`

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

**Observed:** One left-aligned horizontal line: copyright, maker link, social link, newsletter and contact. Individual links have 28px right margins. No separate fill or top rule.

**Transfer:** End with the smallest useful set of links, leaving the artwork as the final substantial impression.

## Imagery and graphics

### Letter-substitution poster

**Use:** Signature graphic within the monumental opening name.

**Observed:** Two letter positions become black pictograms: one intricate chain-like line drawing and one solid insect silhouette. The illustrations sit at letter scale on the same mint field, with no bounding box or photographic backing.

**Transfer:** Replace one or two letters in a short product name or proposition with original concept-relevant shapes. If the product has no visual object, use a geometric knot, loop or abstract emblem that retains the letter's silhouette.

**Build:** Use inline SVG viewBoxes aligned to the cap-height of the display text. Reserve approximately 230px square slots at desktop. Combine one black filled silhouette with one drawing built from nested black paths and mint cutouts; use #000000 and #c7ffcd only. Keep the lettering readable and the SVG flat, with no blur, texture or shadow.

### Monochrome specimen collection

**Use:** The main proof gallery and the inverted playground.

**Observed:** An eclectic mix of cartoon creatures, smiling faces, emblems, wire-like drawings and pixel-edged architecture. Black drawings float on mint square tiles, while mint versions float on black in the stage. Each drawing occupies the central portion of its frame with generous empty space around it; the visual variety comes from the drawing style, not from changing colors.

**Transfer:** Develop a family of original product-related symbols with differing silhouette, stroke density and geometry. The minimum equivalent is a set of distinct vector diagrams, not repeated generic UI icons or colorful mockups.

**Build:** Create square SVG canvases using only black shapes and mint negative space. Mix filled paths, outlined paths and a few stepped polygons. Center an approximately 288px artwork envelope within a 461px tile, preserving the top label strip; use the same artwork with reversed colors in the black stage. Vary the visual mass so the collection feels authored rather than mechanically uniform.

### Icons

**Observed:** The stage reset uses a 25px square mint SVG made from thin 1px strokes with butt caps, depicting angular opposing arrows. Icons otherwise give way to illustrated specimens.

**Transfer:** Keep control icons thin, geometric and unfilled; use them only for functional controls rather than as the gallery's content.

## Section recipes

How recurring sections are built.

### First screen: Pictographic poster opening

**Observed:** Mint canvas is the back layer. A left-aligned two-line uppercase name at 288px/0.8 occupies roughly the first 461px of height; illustrated letter replacements share its black ink and cap-height. A 72px edition marker perches beside the second line while the 14px Project credit sits in the far upper-right open space. Immediately underneath, a 72px/0.9 uppercase statement spans three tight lines and completes the 655px opening block. Within the first 900px, the entire title and statement are visible along with the top of the Interactive stage beginning near 697px, including its controls and partial artwork. The conversion action is below the first fold, not an opening button cluster.

**Transfer:** Use a short name or sharply compressed proposition, with original SVG letter substitutions as the main object rather than a separate mockup. Preserve the contrast between giant type and tiny attribution. For secondary marketing pages, use the same poster relationship with a shorter title and relevant specimens; the edition marker belongs only where a meaningful edition exists.

**Avoid:** Do not turn this into a centered SaaS hero with a normal-sized headline, floating device mockup and two buttons. Do not separate the pictograms from the word into a decorative illustration beside it.

**Text style:** `display` — Helvetica Neue 400 · 288px/0.8 · tracking -0.03em · uppercase

### Inverted playground band

**Observed:** Interactive stage spans nearly the full width with 14px outer edges, 14px corners and a 413px height. A shallow controls row sits above oversized specimens; 42px bottom padding protects their silhouettes.

**Transfer:** Show a small manipulable set of outputs or one live diagram; keep the invitation tiny and the result graphic dominant.

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

### Choice and conversion strip

**Observed:** A single row of five Round choice controls and one Primary action sits beneath the black stage, with 14px spacing between control edges. A 14px explanatory paragraph follows in a half-width left column before the next major heading.

**Transfer:** Adapt the choices to the transaction or configuration being offered, with the elongated action taking all remaining space.

**Text style:** `action` — Helvetica Neue 300 · 28px/1 · tracking 0.025em · uppercase

### Poster heading and specimen wall

**Observed:** A 72px uppercase heading introduces the three-column specimen grid. The square Specimen cards use 1px outlines, 14px corner radii, top-left attribution and Variant keys, with large centered drawings and 14px visible gutters. The wall remains consistent across many rows.

**Transfer:** Use the wall to establish range and authorship through actual outputs. Keep metadata short and on a single top strip.

**Text style:** `statement` — Helvetica Neue 400 · 72px/0.9 · tracking -0.03em · uppercase

### Gallery tail and small-print ending

**Observed:** The gallery finishes with two ordinary square cards aligned to the left of the three-column grid, leaving mint space in the last column. After an 84px top margin the Utility footer closes on the same canvas, with 14px/1.5 text and 14px bottom padding.

**Transfer:** Let the final row reflect the real item count. Close quietly with utility links rather than adding a new promotional composition.

**Text style:** `utility` — Helvetica Neue 400 · 14px/1.5

## Page flow

**Storyline:** graphic identity and concise promise → hands-on proof → simple conversion → compact context → expansive output collection → tiny utility ending

### A single-product creative landing page that presents an artifact, invites experimentation and makes acquisition straightforward

1. **Promise** — Monumental two-line name with pictographic letter substitutions and an oversized factual description.
2. **Product demonstration** — Black inverted playground with mint specimens and minimal controls.
3. **Conversion** — Round preset choices beside an elongated primary action, followed by compact explanatory context.
4. **Breadth and authorship proof** — A long three-column wall of attributed graphic specimens with tiny variant switches.
5. **Utility ending** — Incomplete final gallery row, generous final gap and one small line of underlined links.

**Transfer:** Use the product's outputs as the proof rather than adding testimonials, metrics or feature cards by default. The narrative can shorten or move conversion closer to the relevant proof while retaining poster identity, interactive contrast and a specimen-based visual vocabulary.

## Writing

Direct, factual and community-minded, with friendliness carried by the drawings rather than exuberant sales language. The page states what the artifact is, who made it and what the action accomplishes.

**Do not copy:** Do not reuse the Good Glyphs name, Violet Office identity, contributor names, original dingbat artwork, edition number, designer count, charity beneficiary, donation claims or historical crisis context. Replace all brand assets, examples and factual claims with the new product's own. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal product description; occasional collective 'we' and 'us' in explanatory copy. Actions use short imperatives rather than lengthy second-person promises.
- **Rhythm:** The name is a two-word visual event. The large support statement combines two short factual sentences, while labels are one to three words and context is a compact paragraph.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero name | Short product identity, treated as the headline rather than a benefit slogan. | 2 words | “[Brand]” |
| Supporting statement | Define the artifact, establish participation, then explain the concrete purpose. | 2 short sentences | “A dingbat font created by 32 designers. All proceeds go to Doctors Without Borders.” |
| Demonstration invitation | Try plus the product name. | 3 words | “Try [Brand]” |
| Primary action | Two specific verbs joined by an ampersand. | 3 words | “Donate & Download” |
| Gallery heading | One factual collective noun. | 1 word | “Contributors” |

**Words and phrasing to use:** try; created by; a project by; download; contributors; contact

**Avoid:** revolutionary; supercharge; seamless ecosystem; unlock your potential; game-changing

**Rules:**

- Put verifiable facts in the oversized statement, not abstract aspirations.
- Use uppercase as a typographic treatment for major statements and the main action; leave utility labels in normal case.
- Keep attribution visible and honest; a compact label can carry the author rather than a paragraph of praise.
- Explain transaction or access details in a small, plain paragraph adjacent to the action.

## Do's and Don'ts

### Do

- Use weight 400 for monumental text and weight 300 for the 28px controls.
- Keep display and statement leading at 0.8 and 0.9 respectively.
- Let mint continue inside the outlined gallery cards, without a second card fill.
- Make the gallery artwork about 288px within 461px square frames at desktop.
- Align the 105px circles and 105px-high primary capsule on one row when space permits.
- Keep the utility footer at 14px/1.5 after an 84px top margin.

### Don't

- Do not add white, gray or multicolored section fills to the two-color paper-and-ink system.
- Do not apply gradients, glows, drop shadows or 3D bevels to the artwork or controls.
- Do not increase poster weight to 700; its impact comes from size and compact spacing.
- Do not replace the 1px tile outlines with heavy borders or filled panels.
- Do not enlarge tiny variant keys into a full-width segmented control.
- Do not make every specimen the same stock line icon; the gallery needs varied drawing density and silhouettes.

## Motion and responsive

### Motion

**Observed:**

- The primary action declares a hover inversion to black fill and mint text.
- Specimen slides use transform-based movement; the rendered title incorporates pictographic letter substitutions.
- No action transition durations were established.

**Transfer:**

- Keep color inversion as the primary action feedback and use lateral movement only where specimen variants need it.

**Unknown:**

- Timing and cadence of title-art changes, slider behavior, slide transitions and focus-visible styling.

### Responsive

**Observed:**

- Width breakpoints are declared at 550px, 750px, 1000px and 1400px.
- The title uses 20vw and large statements use 5vw; the form permits wrapping.

**Transfer:**

- Preserve the two-line poster and pictographic letter relationship as width decreases. Wrap the choice controls and elongated action instead of distorting circles.
- Reduce gallery column count when square tiles cannot hold the label strip and artwork legibly; keep square frames and left-aligned final rows.

**Unknown:**

- Exact mobile column counts, control sizing and title substitutions at each breakpoint.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
