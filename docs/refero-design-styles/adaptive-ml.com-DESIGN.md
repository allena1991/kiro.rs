# Adaptive ML — editorial spectrum engineering

## Overview

An enterprise technology style with the authority of a printed manifesto and the vividness of light passing through film. Warm charcoal, white and pale stone carry tightly set serif statements, economical grotesk explanations and small monospaced markings. Grainy spectral artwork frames real interfaces and proof, while spacious compositions keep technically dense content approachable.

### Essentials

- Manifesto typography meets engineering notation: upright Egyptienne display at 94.1px/0.9 with -2.6px tracking, contrasted with 13px uppercase mono labels at 0.03em.
- The opening is a centered statement, not a split-screen sales pitch: a three-line serif headline above a separate support-and-action row, with a 1380px-wide product stage entering the first 900px.
- Actions are compact equipment-like rectangles: charcoal fills, pale lettering, 9px corners and 16px vertical padding; navigation labels start rectangular and round on hover.
- Color lives inside physical-looking media rather than across the text system: predominantly white and warm neutral sections, spectral blue, green, violet and amber artwork in bounded panels and a full-width closing band. A solid purple 47px announcement strip is a separate announcement variant.
- Every page needs the grainy spectrum device: soft irregular fields with dark troughs, luminous edges and fine flecks, used behind a product view or proof poster and again at the ending. Without product media, stage a simple original diagram on the same material.
- Rules behave like editorial emphasis: 0.5px separators organize text, while the selected capability gets an 8px top rule; explanatory serif text sits beside clean 48px grotesk headings.
- The ending is an atmospheric destination: a spacious four-column footer, centered small identity, then a roughly 342px-high spectral field carrying a tiny centered mono legal stack.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#272421` | `--color-ink` | text, background, action | Default text, primary actions and dark closing sections. |
| Dark hairline | `#413e3b` | `--color-rule-dark` | border | Gray at 25% over charcoal for footer and column dividers; source gray is #908d89. |
| Faded charcoal | `#7d7c7a` | `--color-muted-ink` | text | Secondary labels on white; charcoal at 60% opacity. |
| Faded stone | `#9e9b98` | `--color-muted-reverse` | text, link | Secondary footer links on charcoal; stone at 60% opacity. |
| Light hairline | `#e1e0e0` | `--color-rule-light` | border | Charcoal at 14% over white for card edges and separators; allow it to blend into stone when used there. |
| Pale stone | `#edebe8` | `--color-stone` | surface, background, text, border | Editorial bands, feature cards, tab borders and text on charcoal. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default marketing canvas and interface backing; reversed spotlight lettering. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| sitewide announcements | Announcement purple | `#632ca6` | `--color-announcement` | background | Solid announcement strip, not general-purpose section or button color. |
| editorial previews and dark company navigation | Black | `#000000` | `--color-black` | text, surface | Small editorial tag lettering and selected dark navigation chips. |
| editorial previews | Stone tag wash | `#dfddda` | `--color-tag-wash` | surface, border | Gray #908d89 at 15.1% over stone for editorial category capsules. |

## Typography

- **Diatype** — Section headings, body, card titles and supporting copy. Plain-spoken grotesk, neutral in paragraphs and sharply tightened in large headings. If unavailable, use **Inter**. Use 400, 500 and 700; preserve the tight display tracking. Font stack: "Diatype", "Inter", Arial, sans-serif.
- **Egyptienne F LT** — Primary statements and selected editorial explanations. Sturdy upright serif with bracketed serifs, broad lowercase and compact monumental lines. If unavailable, use **Source Serif 4**. Use 400–500 with optical sizing tuned for display; retain upright posture. Font stack: "Egyptienne F LT", "Source Serif 4", Georgia, serif.
- **Diatype Mono** — Navigation, actions, technical labels, numbering and metadata. Functional monospaced capitals with deliberate spacing. If unavailable, use **IBM Plex Mono**. Font stack: "Diatype Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Egyptienne F LT | 500 | 94.1px | 0.9 | -0.028em, features "liga" | Centered opening statements and monumental product promises; upright, not italic. |
| display-secondary | Egyptienne F LT | 500 | 77px | 1 | -0.028em, features "liga" | Centered platform introduction and serif emphasis within mixed-family statements. |
| heading-lg | Diatype | 500 | 72px | 1 | -0.03em | Major capability chapters and service statements. |
| heading | Diatype | 500 | 48px | 1 | -0.03em | Regular section headings, use-case titles and prominent card headings. |
| story-title | Diatype | 400 | 32px | 1.2 | -0.03em | Editorial preview titles. |
| support | Diatype | 500 | 24px | 1.3 | normal | Short product subheads and prompts paired with an action. |
| editorial-summary | Egyptienne F LT | 400 | 22px | 1.2 | -0.03em | Expanded capability text beneath a grotesk title. |
| body | Diatype | 400 | 18px | 1.3 | normal | Main paragraphs and descriptive card copy. |
| hero-support | Diatype | 400 | 18px | 1.4 | normal | Supporting sentence below the display statement. |
| body-bold | Diatype | 700 | 18px | 1.3 | normal | Compact feature headings and icon-led section markers. |
| small | Diatype | 400 | 15px | 1.4 | normal | Footer links and capability detail bullets. |
| eyebrow | Diatype Mono | 400 | 13px | 1.4 | 0.03em, uppercase | Section numbering, dates and technical categories. |
| action | Diatype Mono | 400 | 13px | 1 | 0.03em, uppercase | Buttons, tabs, navigation and arrow links. |
| micro | Diatype Mono | 400 | 11px | 1.4 | 0.09em, uppercase | Category capsules and centered legal stack. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company narratives | company-display | Diatype | 500 | 88px | 0.9 | -0.03em | Large sans companion line beneath a serif declaration and centered values heading. |
| technical essays and company narratives | editorial-body | Egyptienne F LT | 400 | 22px | 1.3 | -0.03em, features "liga" | Longer explanatory passages inset behind a vertical rule. |

**Notes:**

- Serif supplies the large promise; grotesk supplies the operational explanation; mono marks controls and taxonomy.
- Large sans headings use -0.03em tracking and nearly touching line boxes. Body text returns to normal tracking and 1.3–1.4 line height.
- Do not make semantic emphasis italic merely because the display face is used inside emphasized text. The visual posture is upright.

## Layout

**Density:** Airy at section scale, compact within controls and technical cards; long pauses separate dense explanatory clusters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Top inset under rules and compact heading separation. |
| 10px | Inner site gutter and small control horizontal padding. |
| 12px | Tab gaps, footer link rhythm and icon-to-label spacing. |
| 16px | Button vertical padding and media-to-text gaps. |
| 20px | Small text stacks and capability card side insets. |
| 32px | Large feature-card padding and inner content gaps. |
| 64px | Main headline-to-content and two-column editorial gaps. |
| 80px | Inset prose beside vertical rules and selected section bottoms. |
| 136px | Major section top and bottom padding and spacious chapter separation. |

### Containers and grids

- **Full stage**: max width 1400px · side padding 10px. Centered wide wrapper for hero media and card tracks; at desktop the media itself is 1380px wide.
- **Reading container**: max width 1040px. Centered narrative sections, proof panels and services; produces 200px outer margins at 1440px.
- **Statement container**: max width 865px. Centered serif introductions, active landscape feature card and footer content.
- **Reading column**: max width 520px. Upper bound for short supporting narratives and compact feature content.
- **Editorial pair**: 2 columns · gap 64px. Equal-width editorial columns, one large preview opposite two smaller previews.
- **Capability selector**: 2 columns · gap 136px. 452px text list beside a matching tall media poster.
- **Footer grid**: 4 columns · gap 32px. Four centered 192px link columns within the statement container.
- **Capability rail** (only for detailed product pages): gap 22.5px. Horizontal track of 332px-wide feature cards with overflow visible; do not squeeze four into the reading container.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Controls and panels | 9px |
|  | Selected tabs | 9999px (pill) |
| editorial previews | Category capsule | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Landscape feature card | `0px 4px 12px 0px rgba(39, 36, 33, 0.1)` | Only the landscape feature rail needs this modest elevation. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #272421`

#### Stone band · level 0

**Use:** Editorial previews and related-content regions.

**CSS:** `background: #edebe8; color: #272421`

#### Charcoal band · level 0

**Use:** Closing information section and default footer; full-page variant belongs to company narratives.

**CSS:** `background: #272421; color: #edebe8`

**Transfer:** Use dark sections as decisive changes of chapter rather than alternating every block.

#### Landscape panel · level 1

**Use:** Paired illustration and explanation in a horizontal feature rail.

**CSS:** `border: 0.5px solid rgba(39, 36, 33, 0.14); border-radius: 9px; box-shadow: 0px 4px 12px 0px rgba(39, 36, 33, 0.1); overflow: clip`

**Observed:** An 865px by 433px panel divides into two near-square halves; the adjacent panel is partially visible and faded.

**Transfer:** Put an original diagram on stone in one half and a heading, index and explanation on white in the other.

#### Spectral material

**Use:** Hero media backing, editorial art, narrow decorative strips and closing field.

**CSS:** `position: relative; overflow: hidden`

**Observed:** Irregular saturated color fields mingle with almost-black valleys under a tactile, flecked texture. This is image-like material, not a clean rainbow UI gradient.

**Transfer:** Use the Spectral field imagery recipe; match the soft transitions and grain rather than exact color stops.

#### Dark spotlight · level 1

**Only for:** customer case studies

**Use:** A concentrated proof story with contextual photography.

**CSS:** `background: #272421; color: #ffffff; border-radius: 9px; padding: 12px 12px 64px`

**Observed:** A shallow photo banner spans the top; a vertical mono caption anchors the left edge beneath it, beside narrative and proof columns.

## Components

### Primary button

**Use:** Contact, exploration and conversion actions.

**CSS:** `background: #272421; color: #edebe8; border: 0.5px solid #272421; border-radius: 9px; padding: 16px 56px`

**Text style:** `action` — Diatype Mono 400 · 13px/1 · tracking 0.03em · uppercase

**Observed:** A compact broad rectangle, commonly 170px by 46px. Hero variant has a right arrow and asymmetric 24px/22px horizontal insets; dark company sections reverse the fill and lettering.

**Transfer:** Use one direct verb phrase. Keep the action smaller than the supporting text block.

### Navigation chip

**Use:** Centered desktop navigation between identity and contact action.

**CSS:** `background: #ffffff; color: #272421; border: 0.5px solid #ffffff; border-radius: 9px; padding: 8px 10px 6px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Diatype Mono 400 · 13px/1 · tracking 0.03em · uppercase

**Observed:** Small labels appear visually unboxed at rest because border and fill match the canvas. Current-page chips use stone pills. The dark company variant uses charcoal with pale type and black selection.

**States:** Declared: hover changes fill and border to stone and rounds corners to 48px; focus-visible uses a 2px solid charcoal outline. Dark navigation uses a pale focus outline.

### Media tab

**Use:** Switch the large product presentation beneath the opening.

**CSS:** `background: #ffffff; color: #272421; border: 0.5px solid #edebe8; border-radius: 9px; padding: 16px 24px`

**Text style:** `action` — Diatype Mono 400 · 13px/1 · tracking 0.03em · uppercase

**Observed:** Centered row of short verbs; selected category is a pill and the remaining controls are restrained rectangles.

**States:** Declared: hover uses stone fill and border, black text and 1600px radius; focus-visible uses a 2px solid charcoal outline.

### Landscape feature card

**Use:** Explain one key mechanism with a diagram.

**CSS:** `display: flex; border: 0.5px solid rgba(39, 36, 33, 0.14); border-radius: 9px; box-shadow: 0px 4px 12px 0px rgba(39, 36, 33, 0.1); overflow: clip`

**Text style:** `heading` — Diatype 500 · 48px/1 · tracking -0.03em

**Observed:** Square visual first, then mono index, multiline title and compact paragraph. Text half has 32px padding. The centered active card is flanked by a partially visible neighbor.

### Capability selector row

**Use:** Pair selectable benefit summaries with a tall proof poster.

**CSS:** `border-top: 8px solid #272421; padding-top: 8px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `heading` — Diatype 500 · 48px/1 · tracking -0.03em

**Observed:** Active row reveals a serif summary and uppercase arrow link below its title. Inactive siblings collapse to label and title with a 0.5px hairline.

**States:** Declared: border-width transitions over 0.225s with cubic-bezier(0.455, 0.03, 0.515, 0.955).

### Footer link

**Use:** Secondary navigation in spacious footer columns.

**CSS:** `color: rgba(237, 235, 232, 0.6); text-decoration: none`

**Text style:** `small` — Diatype 400 · 15px/1.4

**Observed:** Centered beneath a full-contrast group title with a 12px vertical gap. Light variants inherit the surrounding white or stone canvas and use faded charcoal links.

**States:** Declared: hover restores full stone text; focus-visible uses a 2px solid stone outline.

### Capability card

**Only for:** detailed product pages

**Use:** Dense but scannable operational features in horizontal rails.

**CSS:** `background: #edebe8; border-radius: 9px; display: flex; flex-direction: column; gap: 4px; overflow: clip; width: 332px`

**Text style:** `body-bold` — Diatype 700 · 18px/1.3

**Observed:** Image area above mono ordinal, bold title, regular paragraph and two small open-circle bullets. Text has 20px side insets and 32px bottom inset; cards are about 497–520px tall.

**Transfer:** Keep equal visual height within each rail and allow horizontal browsing.

### Category capsule

**Only for:** editorial previews

**Use:** Small content taxonomy below article titles.

**CSS:** `background: rgba(144, 141, 137, 0.15098); border: 0.5px solid rgba(144, 141, 137, 0.15098); border-radius: 20px; padding: 8px 10px 6px; color: #000000`

**Text style:** `micro` — Diatype Mono 400 · 11px/1.4 · tracking 0.09em · uppercase

**Observed:** Muted capsule on stone, changed to translucent black on the dark company variant; not a colored status badge.

### Announcement bar

**Only for:** sitewide announcements

**Use:** A single high-priority site message above navigation.

**CSS:** `background: #632ca6; color: #ffffff; height: 47px; display: flex; justify-content: center; align-items: center`

**Text style:** `body` — Diatype 400 · 18px/1.3

**Observed:** One centered underlined sentence; separated from the navigation by a thin spectral ribbon near the initial page top.

## Imagery and graphics

### Spectral field

**Use:** Signature media material repeated in product stages, proof posters and the full-width ending.

**Observed:** Defocused blue-violet, cyan, acid green, amber and pink masses overlap with charcoal pockets. Fine gray specks, scratches and uneven grain make the surface feel like light projected onto worn film. Wide fields sit behind white UI; tall versions support white annotation.

**Transfer:** Always include this device. Minimum acceptable version is several irregular blurred color masses under a fine noise texture, used as a deliberate media backing and closing band rather than coloring the body canvas.

**Build:** Create an overflow-hidden charcoal base. Layer 4–6 oversized ellipses of blue, violet, cyan, yellow-green and amber with alpha 0.7–0.95, rotated on opposing diagonals and blurred 35–75px. Keep some hard-to-soft luminous boundaries by adding a smaller blurred duplicate at an ellipse edge. Overlay SVG feTurbulence noise at 0.1–0.18 opacity and sparse 1px dark flecks. At desktop, use a 1380px-wide framed stage or a full-width 342px-high band; shift the field composition between uses.

### Product stage

**Use:** First proof beneath the opening statement.

**Observed:** A real white application window sits inside a saturated textured surround, with generous colored edge exposure and rounded corners. The broad image occupies almost the whole page width while text stays much narrower.

**Transfer:** Show a plausible actual product view, focusing on one meaningful workflow. If no interface exists, render a tidy original system diagram on white inside the spectral surround.

### Technical diagrams

**Use:** Mechanism cards and workflow strips.

**Observed:** Pale stone backings, concentric dotted rings, thin hexagon outlines, small colored nodes and connecting arrows. Low-contrast structure keeps black labels and central symbols readable. Workflow diagrams are wide and shallow.

**Transfer:** Represent the new product's inputs, process and outcomes with sparse nodes and directional links; avoid detailed fake interface chrome.

**Build:** On a stone rectangle, place 3–5 concentric SVG dotted circles around a simple original central symbol. Use small charcoal dots with declining outer opacity, a thin polygon outline and a few amber or blue nodes. For a workflow, arrange 3–4 modules horizontally with thin straight arrows and mono captions.

### Annotated proof poster

**Use:** Tall media beside a capability selector or service statement.

**Observed:** Grainy spectral field, pale sans headline and oversized metric or short process words encircled by imperfect thin ovals. Rounded portrait or square format. The hand-marked oval contrasts with the technical typography.

**Transfer:** Use a verified metric, or a short process phrase if no quantitative proof exists; preserve the circled annotation device.

**Build:** Layer readable pale text over the Spectral field. Draw an SVG ellipse with a slightly asymmetric path and 2–3px pale stroke around the central number or keyword. Use arrows or stacked circled verbs sparingly; keep the labels substantially smaller than the marked content.

### Documentary photo strip

**Only for:** company narratives

**Use:** Human introduction against the dark canvas.

**Observed:** Candid people working and talking in warm natural light, close framing and shallow depth. A broad central image is flanked by narrow portrait slices, separated by dark 4px edges with 9px corners.

**Transfer:** Use genuine working scenes with varied viewpoints and a deliberately unequal-width strip, not uniform headshots.

### Contextual case-study photograph

**Only for:** customer case studies

**Use:** Shallow banner across the top of a dark proof panel.

**Observed:** Rich warm documentary photograph of books and shelves, tightly framed across the panel width, with the panel's dark backing continuing below.

**Transfer:** Choose a real environment or object relevant to the customer's work; retain warm, tactile detail instead of using a generic office handshake.

### Icons

**Observed:** Small outline arrows and linked hexagonal forms, generally 12–16px with 1.4px butt-capped strokes in the current text color. Section markers can pair a small abstract outline with an 18px bold label.

**Transfer:** Use simple geometric outline icons and straight arrows. Keep them subordinate to words; do not substitute large colorful filled icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Statement and product stage

**Observed:** White canvas under a fixed 135px header with a 47px announcement strip, fine spectral ribbon and navigation. A centered upright serif display fills about the middle three-fifths of the screen width in three compact lines at 94.1px/0.9. A separate support-and-action row sits about 64px beneath, with a two-line 18px paragraph on the left and a small dark arrow button on the right. Below another generous pause, the rounded 1380px product stage begins near 690px down the first 900px viewport, so its top and some interface content are visible while the rest, media tabs and customer proof continue below the fold. Back to front: white canvas, narrow atmospheric ribbon, typographic statement and action row, then colored media surround with white interface on top.

**Transfer:** Use a two-part ownership or outcome statement of comparable visual weight; adapt line breaks to the new phrase rather than shrinking the type. Build an original diagram if no product UI exists. Detailed product pages can use a one-line serif product name with centered support; solution pages use a compact 48px title/support pairing above proof media; technical narratives open with a circled product term and left-aligned explanation; company narratives reverse to charcoal and introduce candid photography.

**Avoid:** Do not turn the first screen into a dashboard-sized screenshot beside a small left-aligned headline, or place a gradient behind the entire headline region.

**Text style:** `display` — Egyptienne F LT 500 · 94.1px/0.9 · tracking -0.028em

### Mechanism rail

**Observed:** Centered display-secondary statement above the Landscape feature card track; 64px separates heading, card and the support-plus-Primary button row. The active card is crisp while a neighbor peeks from the side.

**Transfer:** Explain one mechanism at a time rather than turning the horizontal composition into a wall of equal square tiles.

**Text style:** `display-secondary` — Egyptienne F LT 500 · 77px/1 · tracking -0.028em

### Benefits and proof poster

**Observed:** A monumental centered serif promise precedes the Capability selector row stack on the left and Annotated proof poster on the right. The Reading container uses two 452px columns separated by 136px.

**Transfer:** Connect each benefit to a concise outcome illustration; retain selected-rule emphasis and the marked-up visual language.

**Text style:** `display` — Egyptienne F LT 500 · 94.1px/0.9 · tracking -0.028em

### Services pairing

**Observed:** Square spectral process poster on the left; icon-led bold section marker and long 72px grotesk statement on the right, followed by the Primary button. Both sit within the Reading container.

**Transfer:** Use for implementation, support or another human-assisted offering; the large sentence can carry more content than a conventional heading.

**Text style:** `heading-lg` — Diatype 500 · 72px/1 · tracking -0.03em

### Editorial preview band

**Observed:** Stone band with a 48px heading and small uppercase arrow link at opposite ends. After a 136px pause, two columns present a large illustrated article on the left and two rule-topped previews on the right; dates use eyebrow, titles use story-title, and category capsules sit below.

**Transfer:** Use for updates, research or useful resources; dark company narratives keep the same composition with reversed text.

**Text style:** `story-title` — Diatype 400 · 32px/1.2 · tracking -0.03em

### Closing information triptych

**Observed:** Charcoal band with a centered identity-and-heading combination above three text columns. Bold arrow links begin each column; regular 18px copy explains each route. Thin vertical dividers rather than card boxes separate them.

**Transfer:** Provide three distinct next steps such as technical depth, partnership and a conversation. Keep this as an informational close rather than a giant button billboard.

**Text style:** `heading` — Diatype 500 · 48px/1 · tracking -0.03em

### Footer and spectral tail

**Observed:** Default Charcoal band footer with a 0.5px muted top edge, centered small identity and four centered link columns in an 865px container. About 136px section padding supplies the vertical breathing room. Beneath it is the full-width Spectral field with a tiny centered legal stack. Solution pages use stone footer backing; detailed product pages use white, while the spectral tail remains.

**Transfer:** Keep both the spacious navigation field and the vivid final material. Do not replace the closing atmosphere with a thin legal row.

**Text style:** `small` — Diatype 400 · 15px/1.4

### Operational capability chapters

**Only for:** detailed product pages

**Observed:** A small linked-shape marker and bold label precede a 72px multiline chapter heading. A rail of stone Capability cards follows; broad 136px pauses separate chapters. A small support-and-action row ends the content before the white footer.

**Transfer:** Group detailed functionality into a few outcome-led chapters and let the rails carry the dense feature information.

**Text style:** `heading-lg` — Diatype 500 · 72px/1 · tracking -0.03em

### Challenge, solution and spotlight

**Only for:** solution and customer pages

**Observed:** Compact opening title and support share a row above a wide dark proof image. Challenge and solution explanations form two columns separated by a hairline. The Dark spotlight follows, with contextual photo, vertical caption, large narrative and narrower proof column; workflow media and related links lead into the stone footer.

**Transfer:** State the practical risk, then the mechanism, then customer proof. Let a short technical workflow explain how the result is achieved.

**Text style:** `heading` — Diatype 500 · 48px/1 · tracking -0.03em

### Technical editorial column

**Only for:** technical essays and company narratives

**Observed:** Tall spectral image strip at left, 72px grotesk heading at right, then serif explanatory paragraphs inset 80px behind a 0.5px vertical rule. A smaller white inset callout can sit inside a softly colored frame.

**Transfer:** Use this asymmetry for substantive explanations or beliefs rather than ordinary feature bullets.

**Text style:** `editorial-body` — Egyptienne F LT 400 · 22px/1.3 · tracking -0.03em

## Page flow

**Storyline:** Statement → visible product or mechanism → proof → outcome-led chapters → useful next steps → spacious navigation and atmospheric ending.

### Broad marketing landing page

1. **Promise** — Centered multiline serif declaration over a separate support-and-action row.
2. **Product demonstration** — Wide interface stage, compact media tabs and monochrome customer marks.
3. **Mechanism** — Centered serif introduction and landscape feature rail.
4. **Applications** — Monumental statement, selectable benefit list and annotated proof poster.
5. **Assisted adoption** — Process poster and large grotesk service statement.
6. **Ongoing credibility** — Stone editorial preview band.
7. **Next steps and ending** — Dark information triptych, dark footer and spectral legal tail.

**Transfer:** Move between a compelling promise, something tangible and evidence of practical value; preserve the visual devices without requiring the same topic sequence.

### Focused solution page

1. **Outcome** — Compact heading/support pairing and wide comparative proof graphic.
2. **Problem and mechanism** — Two-column challenge and solution narrative.
3. **Customer proof** — Dark documentary spotlight with narrow outcome column.
4. **Process** — Wide workflow illustration and compact benefit summaries.
5. **Further exploration and ending** — Stone related-content band, stone footer and spectral tail.

**Transfer:** Center one practical problem and substantiate the answer before offering adjacent solutions.

### Technical credibility page

1. **Technical identity** — Circled technical term, mono label, 48px description and short centered support.
2. **Architecture explanation** — Two-column explanation, inset callout and rule-topped qualities.
3. **Working advantage** — Tall spectral strip alongside large heading and inset serif paragraphs.
4. **Ending** — Dark footer and spectral tail without an added giant CTA.

**Transfer:** Lead with what the technology enables, then provide enough architectural detail to earn confidence.

### Detailed product page

1. **Product identity** — One-line serif name and centered support.
2. **Capability chapters** — Large grotesk chapter statements and horizontally overflowing stone card rails.
3. **Conversion** — Short practical prompt beside a compact dark action.
4. **Ending** — White footer and spectral tail.

**Transfer:** Use chapter headings to make a dense feature inventory feel like an operational story.

### Company and recruiting narrative

1. **Belief** — Serif declaration and large sans companion on charcoal.
2. **Human proof** — Unequal-width candid portrait strip.
3. **Mission** — Tall spectral strip and mixed serif/sans statement with inset serif prose.
4. **Principles and credibility** — Three-column values grid with thin vertical rules, framed belief callout and partner marks.
5. **Participation** — Spacious recruiting section with a large heading and small arrow link.
6. **Continuity and ending** — Reversed editorial previews, dark footer and spectral tail.

**Transfer:** Use the dark variant for a substantive human narrative, not as the default for a product launch.

## Writing

Confident, technical and outcome-oriented without hype. Editorial declarations establish conviction, while explanatory copy names concrete mechanisms and operational constraints.

**Do not copy:** Do not reuse Adaptive ML names, marks, product artwork, customer logos, acquisition news, customer quotations, performance figures or proprietary claims. Replace all examples with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use 'your' for ownership and business outcomes, imperative verbs for actions, and 'we' for organizational beliefs. Technical paragraphs often name the product directly.
- **Rhythm:** Short declarative headlines alternate with compact explanatory sentences. Large statements can be full sentences; support usually uses one or two sentences and CTAs use two to four words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Parallel ownership statements with repeated opening words. | 6–12 words | “Own your AI. Own your Intelligence Layer.” |
| Supporting line | Three concrete verbs, then the mechanism and business outcome. | 12–22 words | “Build, own, and deploy specialized LLMs. Drive business value through Reinforcement Learning.” |
| Capability heading | Outcome verb plus the specific method that delivers it. | 5–10 words | “Deploy with confidence using personalized evaluations” |
| Problem statement | Name the real operational failure in a plain declarative sentence. | 6–12 words | “In production, model hallucinations are unacceptable.” |
| Primary action | Direct invitation to a concrete next step; displayed as mono capitals. | 2–4 words | “book a demo”<br>“talk with AN EXPERT” |

**Words and phrasing to use:** own; build; deploy; specialized; production; evaluate; focus on; designed for; business value

**Avoid:** magic; revolutionary; game-changing; effortlessly; limitless; supercharge everything

**Rules:**

- Pair ambitious headline language with a specific mechanism in the paragraph that follows.
- State comparisons only with substantiated context; otherwise explain the process instead of inventing a number.
- Keep small labels functional: a category, ordinal or action, not a miniature slogan.
- Use technical vocabulary where it makes the offer more exact, not as decoration.

## Do's and Don'ts

### Do

- Keep the main promise upright serif at 94.1px with 0.9 line height on desktop.
- Preserve 72px tightly tracked grotesk chapter statements for major operational claims.
- Use 13px mono capitals for controls and numbered markings.
- Reserve the 8px top rule for a selected or emphasized item; use 0.5px elsewhere.
- Stage wide media at 1380px while keeping explanatory sections within 1040px.
- Use 136px chapter padding and 32px card insets to separate page-scale air from content-scale density.
- Include grain and dark pockets in the spectral material, including the final band.
- Keep footer links at 15px/1.4 with 12px vertical gaps and a small centered identity.

### Don't

- Do not make ordinary marketing pages entirely charcoal; the light canvas is the default.
- Do not apply the announcement purple to every CTA, heading or feature icon.
- Do not round all controls into pills at rest; retain 9px rectangular corners for primary buttons.
- Do not replace the warm stone cards with cool blue-gray surfaces.
- Do not add heavy elevation to all cards; only the landscape rail uses the 4px/12px soft shadow.
- Do not use cheerful multicolor icon tiles to represent technical capabilities; use restrained outline geometry.
- Do not stretch body copy across the 1400px stage; use the narrower reading composition.
- Do not replace textured spectrum fields with a polished evenly spaced rainbow gradient.

## Motion and responsive

### Motion

**Observed:**

- Navigation chips and media tabs declare 0.25s transitions for border radius, border color, text color and background color.
- Landscape panels declare box-shadow 0.4s and opacity 0.2s with cubic-bezier(0.455, 0.03, 0.515, 0.955).
- Expanding image-strip items declare flex-basis 0.55s with cubic-bezier(0.455, 0.03, 0.515, 0.955).

**Transfer:**

- Keep interaction focused on rounding controls, revealing selected text and shifting panel emphasis rather than adding unrelated entrance theatrics.

**Unknown:**

- Exact scroll choreography, pointer-responsive artwork behavior and autoplay cadence are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 352px, 425px, 440px, 479px, 576px, 767px, 768px, 845px and 991px.

**Transfer:**

- On narrower layouts, stack the support/action row and editorial pair while retaining statement-first hierarchy.
- Preserve horizontal browsing for capability rails instead of compressing 332px cards into unreadable columns.
- Reduce portrait-strip breadth while retaining the unequal image widths and dark separators.

**Unknown:**

- Exact mobile font sizes, header behavior and stacking thresholds are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
