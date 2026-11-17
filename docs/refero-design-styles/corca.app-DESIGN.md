# Corca — highlighted thinking aloud

## Overview

An open, white software style with unusually large conversational typography and pale blue interaction cues. Tightly packed grotesk headlines alternate black assertions with very light gray connective language, while crisp interface imagery makes the product tangible. It suits knowledge tools and collaborative software that want to feel approachable without looking playful or decorative.

### Essentials

- Headlines behave like selectively emphasized speech: GeistSans 600 at 80px/0.9 with -0.05em tracking, black assertions inside light-gray sentences; feature headings repeat the device at 60px/0.9.
- The opening is a typographic argument beside a cropped product detail: a 750px headline block, a deliberately open right edge, and the beginning of a full product view entering the first 900px.
- The product noun becomes the action: blue headline text sits on a pale-blue 20px-radius highlight extending beyond its letters. Preserve this inline action device for the new product.
- Color is local rather than environmental: white dominates, black and #d1d5dc structure the text, and blues are reserved for actions, selection and the pale #eff6ff product stage; no saturated section fills.
- Product proof has two scales: an overlapping desktop-and-phone view, then isolated interaction details beside 60px headings. If no ready-made media exists, construct a credible interface around one real workflow.
- Actions are soft rectangles, not capsules: 10px corners with #dbeafe fill and #2b7fff text; the closing action grows to 26px type in a 65px-high button.
- A selectable scenario shelf makes the product concrete: 298×200px icon-and-title cards, 16px gutters, 20px corners, and a blue-selected card paired with a broad interface stage. A short 80px question supplies the final invitation.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline blue | `#155dfc` | `--color-headline-action` | text, link | The product-category link within the opening headline. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue wash | `#dbeafe` | `--color-action-fill` | surface, action | Button backgrounds and the headline highlight. |
| Action blue | `#2b7fff` | `--color-action` | text, action, link | Buttons, arrow glyphs and focus outlines. |
| Selected blue edge | `#bedbff` | `--color-selected-edge` | border, action | Selected card edge and button hover fill. |
| Blue stage wash | `#eff6ff` | `--color-stage` | surface | Selected scenario and wide product demonstration backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text | Assertions, paragraph text and ordinary navigation. |
| Footer label gray | `#99a1af` | `--color-muted` | text | Small group labels, not the main feature copy. |
| Pale connective text | `#d1d5dc` | `--color-secondary` | text, border | De-emphasized phrases in large headings and 1px dividers. |
| Inactive card gray | `#f3f4f6` | `--color-card` | surface, border | Inactive scenario cards and their matching borders. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | The continuous page and opaque navigation background. |

## Typography

- **GeistSans** — All marketing headings, paragraphs, navigation and controls. Contemporary compact grotesk; semibold large text and regular explanatory copy. If unavailable, use **Geist**. Use weights 400–600 and retain tight tracking. Font stack: "GeistSans", "Geist", Arial, sans-serif.
- **Peano** — Right-arrow glyphs in the proof strip and closing button. Technical monospace used as a punctuation accent, not a second body voice. If unavailable, use **Geist Mono**. Font stack: "Peano", "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GeistSans | 600 | 80px | 0.9 | -0.05em | Opening statement and final short question. |
| heading | GeistSans | 600 | 60px | 0.9 | -0.05em | Capability statements with black and pale-gray phrases. |
| card-title | GeistSans | 600 | 34px | 0.9 | -0.04em | Multiline titles on scenario selectors. |
| body | GeistSans | 400 | 30px | 1 | -0.02em | Short explanatory paragraphs beneath capability headings; inline keywords can be weight 700. |
| proof-label | GeistSans | 600 | 30px | 1.5 | -0.06em | Introductory label in the endorsement strip. |
| closing-action | GeistSans | 500 | 26px | 1.5 | -0.02em | Large final conversion button. |
| navigation | GeistSans | 400 | 18px | 1.3 | -0.02em | Navigation, footer headings and footer links. |
| compact-action | GeistSans | 500 | 18px | 1.3 | -0.02em | Header conversion button. |

**Notes:**

- Large text uses very tight line boxes: the 0.9 heading rhythm is essential to the compact blocks, despite the spacious page around them.
- Use pale gray for connective language within a heading, not a separate subtitle. Important phrases can change color mid-line.
- Body copy remains unusually large at 30px and tightly led; keep it short enough for two or three lines rather than reducing its scale.

## Layout

**Density:** Airy between narrative blocks, compressed within text; large statements occupy little vertical space relative to their scale.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Header action gap and footer label separation. |
| 16px | Scenario-card gutters. |
| 20px | Header padding and primary heading-to-paragraph separation. |
| 27px | Top and left inner padding of scenario cards. |
| 33px | Main navigation link gap. |
| 36px | Text-column top inset beside capability illustrations. |
| 60px | Gap after the endorsement strip and footer column gutters. |
| 80px | Desktop main side padding, opening top inset and capability-section separation. |
| 85px | Space above the closing invitation. |
| 138px | Breathing room below the closing invitation before the footer boundary. |

### Containers and grids

- **main-container**: max width 1400px · side padding 80px. Centered outer shell; yields a 1240px content span at a 1440px viewport.
- **opening-text**: max width 750px. Broad left-aligned statement, with product imagery escaping toward the right edge.
- **capability-row**: 2 columns · gap 0px. Text occupies about 54% of the content span, with a 570px interaction image to the right; heading width 650px and paragraph width 580px.
- **scenario-grid**: 4 columns · gap 16px. Equal-width selectors above one wide demonstration.
- **footer-columns**: 3 columns · gap 60px. One broad social group followed by two narrow resource groups; brand mark sits above them.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons | 10px |
| cards-and-highlight | 20px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Continuous background, including closing invitation and footer.

**CSS:** `background: #ffffff; color: #000000`

#### Inactive selector · level 1

**Use:** Resting scenario-card surface.

**CSS:** `background: #f3f4f6; border: 3px solid #f3f4f6; border-radius: 20px; box-shadow: none`

**Observed:** A flat neutral tile, without a floating-card effect.

**Transfer:** Use it to distinguish selectable content from the white page.

#### Selected selector · level 1

**Use:** Active scenario-card surface.

**CSS:** `background: #eff6ff; border: 3px solid #bedbff; border-radius: 20px; box-shadow: none`

**Observed:** The same dimensions and typography as inactive cards; selection changes fill and outline.

**Transfer:** Reserve the blue treatment for the active choice.

#### Product stage · level 1

**Use:** Broad demonstration underneath scenario cards.

**CSS:** `background: #eff6ff; border-radius: 20px; overflow: hidden`

**Observed:** A 1240×584px rounded pale backing holds nearly full-width interface artwork. Its visible edge is blue and the interface itself has a soft lavender-blue halo.

**Transfer:** Use a faint blue frame and a lightly glowing inset interface, not a heavy colored slab.

## Components

### Sticky navigation

**Use:** Persistent compact orientation and conversion.

**CSS:** `height: 81px; padding: 20px; display: flex; align-items: center; position: sticky; top: 0px; z-index: 20; background: #ffffff; border-bottom: 1px solid #d1d5dc`

**Text style:** `navigation` — GeistSans 400 · 18px/1.3 · tracking -0.02em

**Observed:** Thin black symbol-and-wordmark at left, two informational links nearby; login and pale-blue action sit at the far right. The mark is 186×42px.

**Transfer:** Keep the brand area slender and the navigation sparse.

### Primary button

**Use:** Default compact conversion action in navigation.

**CSS:** `background: #dbeafe; color: #2b7fff; border-radius: 10px; padding: 8px 20px`

**Text style:** `compact-action` — GeistSans 500 · 18px/1.3 · tracking -0.02em

**Observed:** A compact text-only action, about 135×39px; does not use a saturated fill.

**States:** Declared: hover background #bedbff; focus-visible 2px solid #2b7fff outline with 2px offset; active translate 0 0.

### Closing button

**Use:** Expanded conversion action beneath the final question.

**CSS:** `background: #dbeafe; color: #2b7fff; border-radius: 10px; padding: 12px 50px 13px; display: inline-block`

**Text style:** `closing-action` — GeistSans 500 · 26px/1.5 · tracking -0.02em

**Observed:** Centered beneath the headline, about 271×65px. A Peano right arrow follows the label with a 9px gap.

**States:** Declared: hover background #bedbff; focus-visible 2px solid #2b7fff outline with 2px offset; active translate 0 0.

### Headline action

**Use:** Turn the product-category noun into the opening action.

**CSS:** `display: inline-block; position: relative; color: #155dfc`

**Text style:** `display` — GeistSans 600 · 80px/0.9 · tracking -0.05em

**Observed:** A pale-blue rounded backing extends 13px left, 23px right, 5px above and 7px below the text line. It is a separate layer behind the glyphs rather than text padding.

**States:** Declared: focus-visible 2px solid #2b7fff outline with 2px offset; active translate 0 0.

**Transfer:** Choose a concise product noun that reads naturally as the end of the sentence.

### Text link

**Use:** Informational navigation, login and footer resources.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `navigation` — GeistSans 400 · 18px/1.3 · tracking -0.02em

**Observed:** Plain sentence-case text without an icon or surrounding shape. Login has an 8px 20px padded hit area.

**States:** Declared: hover underline; focus-visible 2px solid #2b7fff outline with 2px offset.

### Scenario selector

**Use:** Choose a concrete product use case.

**CSS:** `background: #f3f4f6; border: 3px solid #f3f4f6; border-radius: 20px; padding: 27px 17px 30px 27px; display: flex; flex-direction: column; align-items: flex-start; text-align: left`

**Text style:** `card-title` — GeistSans 600 · 34px/0.9 · tracking -0.04em

**Observed:** Four equal 298×200px tiles. Each has a 34px icon above a short multiline title, separated by 11px. The selected variant uses Selected selector and controls the stage below.

**States:** Declared: focus-visible 2px solid #2b7fff outline with 2px offset.

**Transfer:** Use real scenarios rather than a list of abstract features.

### Endorsement strip

**Use:** Low-key external validation between product overview and capabilities.

**CSS:** `display: flex; border-bottom: 1px solid #d1d5dc; padding-bottom: 52px; margin-bottom: 60px`

**Text style:** `proof-label` — GeistSans 600 · 30px/1.5 · tracking -0.06em

**Observed:** A centered label and blue monospace arrow occupy about one third of the row; four understated investor marks sit across the remainder at roughly 50px high.

**Transfer:** Substitute legitimate partner or customer marks; preserve the horizontal, unboxed presentation.

### Footer groups

**Use:** Resource navigation after the closing call.

**CSS:** `padding: 40px 80px 0px; max-width: 1400px; margin-left: auto; margin-right: auto`

**Text style:** `navigation` — GeistSans 400 · 18px/1.3 · tracking -0.02em

**Observed:** A thin divider precedes the footer. A 186×42px wordmark sits above three groups: a broad left group and two narrow right groups. Labels use muted gray, links black. Copyright sits below the left group; 80px of trailing space completes the ending.

**Transfer:** Keep links as simple vertical text lists and preserve the asymmetric open space.

## Imagery and graphics

### Desktop and phone product portrait

**Use:** Large product overview immediately after the opening.

**Observed:** A bright desktop document editor with narrow sidebars fills most of the content width; a black-edged phone overlaps its right side. Fine interface color is sparse and pastel. The desktop window has softly rounded edges and a restrained shadow against white.

**Transfer:** Show a believable core workflow in a wide desktop window and a matching narrow mobile view. When finished product media is unavailable, build a clean HTML interface composition with meaningful content rather than generic dashboard bars.

### Isolated interaction details

**Use:** Opening right edge and capability-row illustrations.

**Observed:** Cropped autocomplete menus, collaborative cursors and export controls float on white. The opening detail is 961×381px and escapes beyond the right viewport edge; capability examples are 570px wide. White menu surfaces have faint gray edges, soft shadows, and pale-blue selected rows. Small green and pink collaborator accents stay inside the interface.

**Transfer:** Isolate one recognizable interaction for each claim; use white backing and minimal contextual chrome. Keep internal UI colors local, not part of the surrounding marketing palette.

### Blue-framed working document

**Use:** Scenario demonstration stage.

**Observed:** A detailed working document spans almost the entire pale-blue stage; its top and side panels are visible while the bottom is clipped. A thin blue edge and soft lavender halo make the interface feel gently illuminated, not three-dimensional.

**Transfer:** Place a realistic dense working artifact inside the stage. Preserve the ratio of small interface detail to large marketing type.

**Build:** Create a 1240×584px #eff6ff stage with 20px corners and a thin #bedbff inset edge. Inset the white interface approximately 30px from the top and sides. Behind it layer a diffuse rounded rectangle using rgba(135,110,210,0.14), blurred by 18px; keep the light concentrated at the interface perimeter. Clip the interface at the bottom. Match the soft halo; exact gradient stops are not essential.

### Icons

**Observed:** Scenario cards place 34×34px SVG icons above their titles with an 11px gap. Blue right-arrow glyphs act as directional punctuation in the endorsement strip and final action; the final arrow uses 26px type.

**Transfer:** Use simple compact line symbols for scenarios and text-like arrows for direction. Do not introduce oversized decorative icon badges.

## Section recipes

How recurring sections are built.

### First screen: Highlighted argument opening

**Observed:** An opaque Sticky navigation sits above a white field. The main content begins after an 80px top inset. A left-aligned 750px-wide statement dominates roughly the left two thirds: black problem assertion, pale-gray belief clause, then a separated second thought ending in black benefits and a blue Headline action. All use display typography. A cropped interaction detail occupies the upper right and extends beyond the edge, behind the headline's foreground layer. Within the first 900px, the full statement and inline action are visible; the top of the desktop product portrait enters around the bottom of the screen, while most of that overview lies below. There is no separate small support paragraph or button row in the hero.

**Transfer:** Write a short problem-to-alternative argument with a highlighted product noun. Construct a close-up of the new product's central interaction if original artwork is unavailable, and let the broad product view enter below. More focused landing pages can shorten the argument while retaining the mixed-color headline and inline action.

**Avoid:** Do not replace the argument with a centered slogan, a small subtitle and two pill buttons; do not box the right-hand detail into a colored hero card.

**Text style:** `display` — GeistSans 600 · 80px/0.9 · tracking -0.05em

### Wide product proof

**Observed:** The desktop-and-phone product portrait occupies a full content-width band, followed by Endorsement strip. Both remain on White canvas, without a section title above the portrait.

**Transfer:** Move quickly from the verbal promise into an inspectable product view, then place concise external validation alongside it.

### Capability statement pair

**Observed:** Repeated two-column rows use a 54% text column and 570px interaction artwork on the right. Text starts 36px below the row top. A black-and-pale-gray heading uses heading typography; one short body paragraph follows at a 13–20px gap. Rows are separated by 80px.

**Transfer:** Use one literal benefit and one interaction detail per row. Let black words carry the claim and pale words complete the sentence.

**Text style:** `heading` — GeistSans 600 · 60px/0.9 · tracking -0.05em

### Scenario shelf and working stage

**Observed:** Four Scenario selector cards form one row with 16px gaps, followed about 14px later by Product stage. The active blue selector is visually tied to the stage; the others remain gray. The broad demonstration is about three times the card height.

**Transfer:** Pair specific jobs-to-be-done with credible product artifacts. Preserve a single active scenario rather than making every card equally prominent.

**Text style:** `card-title` — GeistSans 600 · 34px/0.9 · tracking -0.04em

### Brief question closing

**Observed:** After 85px of white space, a centered black display question is followed by Closing button with a 26px visible gap. The invitation occupies only 163px vertically, then yields 138px of breathing room before the footer boundary. Footer groups finish the page with restrained text columns and copyright.

**Transfer:** End with a very short question that names the visitor's activity, then one action. Preserve the clean white ending and compact asymmetrical footer.

**Text style:** `display` — GeistSans 600 · 80px/0.9 · tracking -0.05em

## Page flow

**Storyline:** problem and alternative → tangible product view → external validation → capability details → contextual scenarios → short invitation → utility links

### Introduce a collaborative software tool and turn familiarity with a problem into product trial

1. **Promise** — Large mixed-color argument ending in an inline highlighted product noun.
2. **Product demonstration** — Wide desktop view with overlapping phone.
3. **Social proof** — Understated horizontal endorsement strip.
4. **Capability chapters** — Short, tightly led statements beside isolated interactions.
5. **Contextual proof** — Selectable scenario shelf paired with a wide working document.
6. **Closing call** — Oversized short question, pale-blue action and spacious utility footer.

**Transfer:** Adapt the narrative to a new product's strongest workflow; retain the contrast between oversized spoken language and fine-grained product detail rather than prescribing a fixed number of sections.

## Writing

Direct, optimistic and conversational. It explains software through familiar activities rather than technical grandstanding, with an understated confidence in the alternative being offered.

**Do not copy:** Do not reuse Corca's name, logo, investor marks, product images, mathematical examples, claims or source-specific scenarios as assets or facts for another product. Source quotations below illustrate voice only.

- **Addressing the reader:** Use we for the maker's belief and you or direct imperatives for the reader's workflow. Describe capabilities plainly rather than speaking as a corporate institution.
- **Rhythm:** Brief assertions and sentence fragments in headings, followed by one or two short explanatory sentences. The opening can be a longer conversational argument; the closing contracts to a two-word question.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening argument | Name a familiar old behavior, state belief in an alternative, then identify the product. | About 20–30 words across two thoughts. | “People still do math on paper. We believe there is a better way. We are building a fast, intuitive math editor” |
| Capability heading | A plain benefit or removal of friction, often followed by a short instruction. | 3–9 words. | “No syntax or coding. Just start typing.”<br>“Simple export to LaTeX.” |
| Supporting explanation | Explain behavior with a familiar analogy or concrete action. | One or two sentences. | “It’s like working at a blackboard, discussing and solving problems together.” |
| Closing question | Short colloquial question naming the reader's activity. | 2–4 words. | “Got Math?” |
| Primary action | Straightforward imperative without marketing qualifiers. | 2 words. | “Get Started” |

**Words and phrasing to use:** just; simple; type; together; like; copy; share

**Avoid:** revolutionary; unleash; supercharge; seamless ecosystem; next-generation platform

**Rules:**

- Make the benefit legible without understanding the product's technical field.
- Support abstract promises with concrete verbs and familiar comparisons.
- Let one or two phrases carry emphasis; surrounding words should sound like natural speech.
- Use short action labels consistently across navigation and closing.

## Do's and Don'ts

### Do

- Keep display headings at 600 weight, 0.9 line height and -0.05em tracking.
- Give the hero text up to 750px and let the right-hand product detail extend beyond the viewport.
- Keep feature paragraphs at 30px/1 with a 580px maximum width.
- Use 10px corners for ordinary buttons and 20px for selectors and headline highlighting.
- Separate capability rows by 80px while keeping internal text gaps around 13–20px.
- Reserve the 3px pale-blue border for selected scenario cards.
- Finish with an 80px short question and a 65px-high pale-blue action.

### Don't

- Do not turn pale-gray connective words into medium-gray body copy; #d1d5dc is deliberately faint at display scale.
- Do not use blue as a full-page or full-width saturated background.
- Do not use capsule corners on the rectangular actions.
- Do not add drop shadows to the marketing selector cards; their hierarchy comes from fill and border.
- Do not shrink the capability paragraphs to conventional 16px prose.
- Do not alternate feature rows into a decorative zigzag; keep the repeated text-left, detail-right rhythm.
- Do not replace the footer's open three-group layout with a dense multi-column sitemap or a dark ending.

## Motion and responsive

### Motion

**Observed:**

- Actions declare pale-blue hover fills or text underlines and 2px blue focus-visible outlines with 2px offset.
- No transitions or animations are matched to the marketing actions and surfaces.

**Transfer:**

- Let selection and interaction details explain the product; retain the immediate pale-blue action-state changes.

**Unknown:**

- Timing, easing and playback behavior of product illustrations are unspecified.

### Responsive

**Observed:**

- Declared CSS includes width breakpoints at 359px, 639px, 640px, 767px, 1023px, 1279px and 1280px.
- Responsive classes reduce the opening type to 60px/-3px and then 46px; capability headings have a 48px/-2.4px variant. Main side padding has a 25px variant and opening top padding a 40px variant.
- Declared variants stack capability rows, reverse image/text order on the smallest layout, hide the wide scenario stage, and wrap footer groups.

**Transfer:**

- On narrower layouts preserve the black/gray sentence emphasis and highlighted product noun while scaling the statement down.
- Stack interaction imagery with its related claim and keep the scenario selectors useful even when the wide stage is hidden.

**Unknown:**

- Exact breakpoint-to-variant mapping and rendered mobile composition are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
