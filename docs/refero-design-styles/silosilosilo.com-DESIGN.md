# SILO — objects before words

## Overview

An object-led showroom with the restraint of an industrial parts catalogue. White space, warm grey sans-serif lettering and a solid graphite transaction strip frame softly lit film and isolated metallic objects. It suits tactile products, configurable goods and small, considered ranges; the visual field is expansive while the language is exceptionally sparse.

### Essentials

- The opening sells through handling rather than a slogan: a full-bleed 1440×810px film with a 78px white emblem centered horizontally near the top, without a headline or hero button.
- Names behave like specimen labels: 24px light-weight capitals at 1 line height and 0.02em tracking, followed by 11px technical notes at 0.12em tracking.
- Comparison is a borderless exhibition: three equal 480px columns at desktop, isolated objects about 148px wide, and tiny labels flanking the objects at mid-height.
- The action is architecture, not a pill: a square-edged 120px-high full-width grey link carrying a 56px total on the left and a 40px uppercase action on the right.
- Color belongs to the object and its surroundings: white dominates the catalogue, grey carries all typography and the closing band, while warm skin, silver and gold appear only in media.
- A physical encounter and a clean specimen view are signature counterparts: retain both the immersive handling scene and the isolated object display; for an intangible product use an actual working artifact or a carefully rendered representation instead.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Transaction graphite | `#616161` | `--color-transaction` | background, action | Full-width closing action surface. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fine edge | `#5b5b5b` | `--color-rule` | border | 0.5px top rules at the transaction boundary. |
| Object label grey | `#666666` | `--color-ink` | text | Material headings, offer names and prices. |
| Technical grey | `#707070` | `--color-secondary` | text | Technical designations and availability notes. |
| Muted reverse | `#b8b8b8` | `--color-hint` | text | Visible instruction text on graphite, produced by white at 0.55 opacity. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Catalogue canvas, column headers, emblem and reversed transaction text. |

## Typography

- **Kantumruy Pro Variable** — All headings, specifications, prices and actions. Light, open sans-serif with plain technical numerals; most lettering is regular, with a lighter cut for product-family names. Font stack: "Kantumruy Pro Variable", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| transaction-total | Kantumruy Pro Variable | 400 | 56px | 1 | normal | Prominent total in the closing action band. |
| transaction-action | Kantumruy Pro Variable | 400 | 40px | 1.2 | normal, uppercase | Large right-aligned conversion label. |
| material-heading | Kantumruy Pro Variable | 300 | 24px | 1 | 0.02em, uppercase | Centered product-family or variant names. This is the first visible heading treatment; the film itself has no textual headline. |
| offer-price | Kantumruy Pro Variable | 400 | 14px | 1 | normal | Price beside an isolated object. |
| technical-note | Kantumruy Pro Variable | 400 | 11px | 1.5 | 0.12em, uppercase | Centered technical designation beneath a variant name. |
| offer-label | Kantumruy Pro Variable | 400 | 11px | 1 | 0.1em, uppercase | Small product-unit label on the opposite side of the object from its price. |
| availability | Kantumruy Pro Variable | 400 | 11px | 1 | 0.06em, uppercase | Plain availability text beneath a price, not a badge. |
| transaction-hint | Kantumruy Pro Variable | 400 | 11px | 1.5 | 0.1em, uppercase | Subdued instruction centered inside the transaction band. |

**Notes:**

- Hierarchy comes from scale, position and letter spacing rather than boldness. Family names use weight 300; transactional and technical text use 400.
- Capitals are the default for names and labels, but prices retain ordinary numeral and currency forms. Do not apply the technical labels' tracking to prices.
- There is no oversized promotional headline or paragraph-led introduction. Keep any additional explanatory copy subordinate to the object and its concise identification.

## Layout

**Density:** Airy object staging with compact annotation: the objects have broad white surroundings, while names, specifications and prices remain closely grouped.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Separation between a family name and its technical note. |
| 16px | Horizontal inset of the centered column heading. |
| 20px | Horizontal inset of the object content within each column. |
| 28px | Gap between the central specimen rail and flanking offer annotations. |
| 32px | Bottom padding of column headings and vertical padding of the transaction band. |
| 40px | Space above the isolated object below its heading block. |
| 48px | Horizontal inset of the closing total and action. |
| 56px | Space above each product-family heading. |
| 72px | Vertical separation within the object presentation rail. |

### Containers and grids

- **Film stage**: max width 1440px · side padding 0px. Edge-to-edge 810px-high media at the desktop reference size; use cover framing rather than a boxed player.
- **Specimen grid**: 3 columns · gap 0px · side padding 0px. Equal-width columns spanning the viewport, 480px each at 1440px. No visible card borders or alternating backgrounds.
- **Object rail**: max width 800px · side padding 20px. Centered within each column; available inner width is 440px on desktop. The assembled specimen is approximately 148px wide and 343px tall.
- **Transaction band**: gap 40px · side padding 48px. Full-width closing row with total on the left, the action on the right and an independently centered hint.

## Corner radius

| Element | Radius |
| --- | --- |
| Transaction and column surfaces | 0px |

## Surfaces and depth

### Surfaces

#### White showroom · level 0

**Use:** Catalogue and comparison canvas.

**CSS:** `background: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** Column headers share the same white backing as the object field, so groups are separated by alignment and air rather than panels.

**Transfer:** Keep the comparison field continuous even when the product types differ.

#### Transaction edge · level 1

**Use:** Boundary between the object field and the conversion strip.

**CSS:** `background: #ffffff; border-top: 0.5px solid #5b5b5b`

**Observed:** A very fine horizontal edge defines the closing utility area.

**Transfer:** Use the hairline at the functional boundary, not as a repeated decorative grid.

#### Graphite action plane · level 1

**Use:** Closing conversion surface.

**CSS:** `background: #616161; color: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** The only substantial solid dark fill is a full-width transaction strip rather than a small button.

**Transfer:** Reserve this strong neutral inversion for the page's main transactional action.

## Components

### Floating emblem

**Use:** Single identity marker over the opening film.

**CSS:** `position: absolute; display: flex; justify-content: center; align-items: center; width: 78px; height: 78px; top: 100px; left: 50%; transform: translateX(-50%); color: #ffffff; z-index: 2`

**Observed:** A white line-built square emblem floats directly on the film without a navigation bar or backing plate.

**Transfer:** Use the new identity as a compact white outline mark; retain the isolated placement and scale.

### Variant header

**Use:** Identify each specimen column.

**CSS:** `padding: 56px 16px 32px; text-align: center; background: #ffffff`

**Text style:** `material-heading` — Kantumruy Pro Variable 300 · 24px/1 · tracking 0.02em · uppercase

**Observed:** A light uppercase name sits above a technical-note line with a 6px separation. Headers remain backed by white over their scrolling columns.

**Transfer:** Use short parallel family names with one material, model or availability designation beneath each.

### Specimen offer

**Use:** Attach a product name and price to an isolated selectable object.

**CSS:** `display: grid; position: absolute; align-items: center; column-gap: 28px; grid-template-columns: minmax(0px, 1fr) 147.5px minmax(0px, 1fr); transform: translate(0px, -50%); z-index: 6`

**Text style:** `offer-label` — Kantumruy Pro Variable 400 · 11px/1 · tracking 0.1em · uppercase

**Observed:** The central rail is occupied by the object, not text. The small unit label sits to its left and an offer-price sits to its right, aligned around the object's mid-height. Selecting the object is the add interaction.

**Transfer:** Keep the image itself as the primary selection target rather than adding a separate bright button.

### Availability note

**Use:** Explain an unavailable or forthcoming variant beside its price.

**CSS:** `color: #707070`

**Text style:** `availability` — Kantumruy Pro Variable 400 · 11px/1 · tracking 0.06em · uppercase

**Observed:** Unboxed uppercase text sits below the price. It has no tinted badge or status icon.

**Transfer:** Use a short literal stock or release status without a promotional flourish.

### Transaction total

**Use:** Show the current selection's cost.

**CSS:** `color: #ffffff; font-size: 56px; line-height: 1; font-weight: 400; letter-spacing: normal`

**Text style:** `transaction-total` — Kantumruy Pro Variable 400 · 56px/1

**Observed:** The largest live text is the total at the left of the action band, not a sales headline.

**Transfer:** For a non-commerce product, use a meaningful selection count or equally concise decision summary in this role.

### Checkout band

**Use:** Primary conversion action and page ending.

**CSS:** `display: block; position: relative; height: 120px; background: #616161; color: #ffffff; border-radius: 0px; max-width: 100%`

**Text style:** `transaction-action` — Kantumruy Pro Variable 400 · 40px/1.2 · uppercase

**Observed:** The entire band is a link. Its inner row has 48px side insets and 32px vertical padding, pairing Transaction total at left with the uppercase action at right. Transaction hint is centered independently between them. The page ends here without footer columns.

**States:** Declared: hover background-color remains #616161; focus-visible styling is unknown.

**Transfer:** Carry the same broad rectangular conversion treatment to reserve, configure or continue actions.

### Transaction hint

**Use:** Explain the object-selection gesture.

**CSS:** `position: absolute; left: 50%; top: 50%; transform: translate(-50%, -50%); color: #ffffff; opacity: 0.55; transition: opacity 0.3s`

**Text style:** `transaction-hint` — Kantumruy Pro Variable 400 · 11px/1.5 · tracking 0.1em · uppercase

**Observed:** A single faint instruction sits on the band's central axis, visually secondary to the total and action.

**Transfer:** Name one specific gesture and its immediate result.

## Imagery and graphics

### Handling film

**Use:** Immersive opening and primary emotional demonstration.

**Observed:** Close-up footage shows hands opening and using cylindrical metal objects on a pale tabletop. Large objects extend beyond the frame edges. Diffuse daylight, shallow focus and low-contrast silver surfaces make the scene soft rather than glossy; skin and small contents supply the natural color. The film occupies almost the entire first screen.

**Transfer:** Show the new product being touched, assembled or used in a real, pale setting. For software or services, film the tangible working context or a real output artifact. A carefully lit still with hands and a clear interaction is the minimum substitute; preserve the full-bleed composition.

### Isolated specimens

**Use:** Comparable product views in the white showroom.

**Observed:** Three upright cylindrical stacks are shown from the same slightly elevated angle, exposing their elliptical top rims. Silver, warm gold and darker silver finishes distinguish the variants through reflected vertical highlights, fine seams and realistic material grain. Each object is roughly 148px wide and 343px tall on a pure white field, far smaller than its surrounding column, with no decorative pedestal or card shadow.

**Transfer:** Render or photograph each variant at a consistent scale and angle with soft studio reflections. Keep silhouettes isolated on white. For intangible products, use a clearly bounded representative artifact with equivalent consistency; avoid filling the columns with dense interface detail.

### Line emblem

**Use:** Graphic signature on the opening media.

**Observed:** A compact white rectangular line mark provides identity while leaving the product scene dominant.

**Transfer:** Use an original mark built for the new identity, retaining a compact line-based silhouette rather than a text navigation masthead.

**Build:** Place an original SVG in a 78px square. Use a simple rectangular contour and a few rectilinear inner strokes, white with no fill, around 3–4px stroke thickness. Keep the film visible through its negative spaces and add no badge, glow or shadow.

## Section recipes

How recurring sections are built.

### First screen: Film-first opening

**Observed:** An edge-to-edge Handling film forms the back layer, covering a 1440×810px stage with centered cover framing. A Floating emblem is the only foreground layer: horizontally centered, 78px square, 100px from the top. There is no hero headline, support paragraph, navigation row or action overlay. Objects and hands fill most of the frame and run beyond its edges. Within the first 900px, the film ends and the three material-heading names of the Variant headers appear on white; their technical notes and the selectable specimen views continue below the fold.

**Transfer:** Lead with an equally tangible interaction for the new product and let the small identity mark carry recognition. If film is unavailable, use the Handling film still-image alternative rather than replacing the scene with promotional type. More informational page types can retain this media-first opening and put their short heading in the white region that follows.

**Avoid:** Do not turn the film into a dimmed background for a centered slogan and two rounded buttons; that reverses the object-first hierarchy.

**Text style:** `material-heading` — Kantumruy Pro Variable 300 · 24px/1 · tracking 0.02em · uppercase

### Borderless specimen comparison

**Observed:** White showroom spans the viewport as a three-column Specimen grid. Each Variant header begins with 56px top padding and carries a technical designation. Isolated specimens sit about 40px beneath the header area. Specimen offer annotations flank the central object at mid-height, with Availability note appearing only where needed. White space remains broad below and around the objects.

**Transfer:** Compare a small set of product variants or representative outputs with the same camera angle, image scale and annotation positions. Preserve the showroom device without requiring the same materials or number of variants.

**Text style:** `material-heading` — Kantumruy Pro Variable 300 · 24px/1 · tracking 0.02em · uppercase

### Transactional ending

**Observed:** Transaction edge separates the white comparison field from Graphite action plane. Checkout band is the final visible page element, 120px tall, with Transaction total on the left, Transaction hint in the center and the 40px uppercase action on the right. There is no separate marketing close, sitemap or social-link footer.

**Transfer:** End the selection experience with a similarly decisive full-width action. Replace the total with an appropriate compact decision summary if necessary, while maintaining the three-part alignment and quiet instruction.

**Text style:** `transaction-action` — Kantumruy Pro Variable 400 · 40px/1.2 · uppercase

## Page flow

**Storyline:** Sensory demonstration → named choices → direct object selection → transactional close.

### A compact object-led marketing and purchasing experience

1. **Sensory promise** — A full-bleed interaction film communicates feel and use without a written claim.
2. **Choice and product demonstration** — Equal white columns identify variants and show consistent isolated specimens with tiny adjacent labels and prices.
3. **Closing action** — A graphite strip combines current total, one gesture instruction and a large conversion label; this is also the page ending.

**Transfer:** Use this pattern for a tightly edited range or configurable offer. Let demonstration replace a long pitch, let comparable objects carry the choice, and keep the conversion surface legible and architectural rather than multiplying persuasion sections.

## Writing

Matter-of-fact, technical and almost silent. The language identifies and instructs rather than persuading with adjectives; the objects carry the confidence.

**Do not copy:** Do not reuse the SILO name, emblem, footage, product artwork, material designations, prices or product-specific claims as assets or facts for another brand. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal noun labels. The occasional instruction uses an imperative addressed directly to the reader; there is no conversational we-led narrative.
- **Rhythm:** One-word names, short technical codes and single-line instructions. No visible paragraph-led pitch or exclamations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Variant heading | A single category or material noun. | 1 word | “Aluminum”<br>“Brass”<br>“Titanium” |
| Technical designation | A precise model or material code without explanatory prose. | 1 compact code | “6061-T6”<br>“C360” |
| Selection instruction | Gesture + object + immediate outcome. | 6–8 words | “Click the stack to add it” |
| Action and availability | One literal transaction or availability term. | 1 word | “Checkout”<br>“Waitlist” |

**Words and phrasing to use:** specific model names; material or construction terms; literal unit names; select; add; checkout; waitlist

**Avoid:** revolutionary; game-changing; unlock your potential; best-in-class; hype-heavy superlatives; chatty welcome copy

**Rules:**

- Use precise identification in place of broad benefit claims.
- If the object makes the proposition clear, let it stand without a hero sentence.
- Keep the instruction tied to a real interaction, not a generic call to explore.
- Use parallel naming and equally specific technical notes across comparable variants.

## Do's and Don'ts

### Do

- Keep family names at 24px, weight 300 and 0.02em tracking.
- Pair those names with 11px technical notes separated by 6px.
- Use three equal, gapless columns for a comparable desktop range.
- Maintain roughly 148px-wide isolated objects within the broad white columns.
- Keep side annotations small: 11px unit labels and 14px prices.
- Make the principal conversion a full-width 120px rectangle with 48px side insets.
- Reserve the 56px text size for the selection total and the 40px uppercase size for the closing action.
- Let natural footage and product finishes provide color while the surrounding interface remains neutral.

### Don't

- Do not set the variant names in bold; the display cut is light, not emphatic.
- Do not enlarge 11px technical notes into promotional subheadings.
- Do not add tinted panels or 16px-radius cards around the isolated specimens.
- Do not use gold from a product finish as the interface's button color.
- Do not apply floating card shadows to the continuous white showroom.
- Do not replace the flanking price and unit annotations with a dense block beneath each object.
- Do not give Waitlist a pill background or a colored status dot.
- Do not append a multi-column corporate footer after the decisive transaction strip.

## Motion and responsive

### Motion

**Observed:**

- The opening is video media.
- The centered instruction declares an opacity transition of 0.3s.
- A height transition of 0.28s and an ease easing declaration occur in the interface styles.
- Column headers and object rails use sticky positioning within the comparison area.

**Transfer:**

- Keep the film as the main moving element; do not add unrelated decorative motion around the technical labels.
- If an instruction changes with selection, preserve its restrained opacity-based treatment.

**Unknown:**

- Video playback controls and full sequence are not established.
- The complete object-selection and stacked-part motion is not established.
- Focus-visible and active appearances are not established; the closing link's hover fill is unchanged.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 767px, 991px, 992px and 1440px.

**Transfer:**

- On narrow layouts, prioritize a legible specimen and its adjacent price over retaining three compressed columns; use a single-column or horizontally navigable showroom as an adaptation.
- Keep the opening image full-bleed with the emblem on its central axis. Preserve meaningful hands and product detail when reframing.
- Adapt the three-part transaction strip to avoid collisions while retaining a clearly dominant action and selection summary.

**Unknown:**

- Actual narrow-screen column arrangement, media heights and transaction layout are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
