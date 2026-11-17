# Assurestor — olive and electric assurance

## Overview

A dark, olive-toned technical style with electric lime signals and warm pale lettering. Rounded geometric sans headlines sit beside sober explanatory copy, while simplified interface illustrations make complex services feel tangible. The density is purposeful and information-rich, suited to business platforms and infrastructure products rather than lifestyle storytelling.

### Essentials

- Headlines resolve into a lime conclusion: 56px/1.03 semibold display type in the opening, 44px/1.08 in sections, both tracked at -0.02em, with the final meaningful phrase colored #c6f24e.
- The opening pairs a substantial argument with a working-looking console: two equal columns inside 1180px, separated by 56px, with text and a 562px-wide demonstration sharing the first screen.
- Dark olive is the environment, not an accent: #141d08 canvas and #1c280c panels dominate; lime is concentrated in headline phrases, small marks, actions and one emphatic 18px-radius conversion panel.
- Actions are compact rounded rectangles, not capsules: 48px high, 8px radius, 11px 18px padding, with a lime primary and outlined secondary; the bright conversion panel reverses the primary to dark.
- A small lime dash acts as a recurring editorial marker: pair it with 11px uppercase labels at 0.06em tracking, and echo its squared geometry in tiny list bullets and status marks.
- Proof is staged as bordered machinery rather than photography: include a simplified operational panel with legible states and rows; if there is no software interface, diagram the product's process inside the same 14px-radius olive frame.
- Information alternates between rounded dossiers and square ruled matrices: 380px-wide cards use 28px padding and 20px gutters, while three-column feature cells meet on 1px #33461a rules with no gutters or shadows.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Raised olive | `#1c280c` | `--color-panel` | surface | Rounded content panels and comparison table headers. |
| Deep olive | `#141d08` | `--color-canvas` | background, text | Page canvas and dark text on lime surfaces. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#c6f24e` | `--color-signal` | accent, text, action, border, background | Headline conclusions, markers, primary actions and the standout conversion surface. |
| Lime comparison wash | `#1b260b` | `--color-comparison-wash` | surface | Visible result of 4% lime over deep olive in the preferred comparison column. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive edge | `#33461a` | `--color-rule` | border | Hairlines, table divisions and panel outlines. |
| Sage text | `#95a67a` | `--color-muted` | text, link | Support paragraphs, navigation and secondary metadata. |
| Pale leaf | `#ecf2e0` | `--color-text` | text | Headlines, feature names and emphasized body copy. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Console olive | `#223110` | `--color-console-bar` | surface | Interface illustration toolbar and message bubble backing. |

## Typography

- **Assurestor Display** — Headlines, card headings and question summaries. Rounded geometric sans with open, friendly counters and firm semibold strokes. If unavailable, use **Manrope**. Use 600; preserve tight tracking and headline line breaks. Font stack: "Assurestor Display", "Manrope", "Segoe UI", system-ui, sans-serif.
- **Assurestor Text** — Paragraphs, navigation, labels and actions. Readable contemporary sans with a soft geometric construction and restrained emphasis. If unavailable, use **Inter**. Use 400–600; keep the relaxed body leading. Font stack: "Assurestor Text", "Inter", "Segoe UI", system-ui, sans-serif.
- **JetBrains Mono Variable** (only for technical badges and operational illustrations) — Small status labels and technical category badges. Compact engineering-style monospace, used sparingly. Font stack: "JetBrains Mono Variable", "JetBrains Mono", ui-monospace, menlo, consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Assurestor Display | 600 | 56px | 1.03 | -0.02em | size clamp(36px, 4.6vw, 56px) | Opening promise, with a pale setup and lime resolution. |
| section-heading | Assurestor Display | 600 | 44px | 1.08 | -0.02em | size clamp(30px, 3.6vw, 44px) | Main section headings; accent only a semantically complete phrase. |
| conversion-heading | Assurestor Display | 600 | 42px | 1.08 | -0.02em | size clamp(28px, 3.4vw, 42px) | Dark heading on the lime conversion surface. |
| card-heading | Assurestor Display | 600 | 22px | 1.2 | -0.02em | fixed | Multi-line headings in audience or solution cards. |
| feature-heading | Assurestor Display | 600 | 19px | 1.6 | -0.02em | fixed | Compact feature cells and benefit names. |
| lead | Assurestor Text | 400 | 19px | 1.6 | normal | fixed | Opening support paragraph; selected clauses become pale and weight 500. |
| question | Assurestor Display | 600 | 18px | 1.6 | normal | fixed | Accordion summaries. |
| body | Assurestor Text | 400 | 17px | 1.6 | normal | fixed | Section support and expanded explanations. |
| small-body | Assurestor Text | 400 | 15px | 1.6 | normal | fixed | Feature explanations, navigation links and compact supporting text. |
| action | Assurestor Text | 600 | 15px | 1.6 | normal | fixed | Main buttons and card text links. |
| eyebrow | Assurestor Text | 600 | 11px | 1.6 | 0.06em, uppercase | fixed | Section markers, audience labels and footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| operational illustrations | technical-label | JetBrains Mono Variable | 400 | 11px | 1.6 | 0.08em, uppercase | fixed | Quiet status legends within the demonstration. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display tracking stays at -0.02em across headline sizes; body and actions retain normal tracking.
- The contrast between sage explanatory text and pale emphasized clauses creates hierarchy without introducing another font or a heavy bold paragraph.
- Keep headlines in sentence case; uppercase belongs to tiny navigational and technical markings.

## Layout

**Density:** Comfortable between chapters, compact within technical groups; 96px section starts contrast with tightly ruled rows.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-copy gap in feature cells. |
| 12px | Space between paired or stacked actions. |
| 16px | Internal vertical gap in audience cards. |
| 20px | Three-card grid gutter and minimum page inset. |
| 26px | Feature cell vertical padding. |
| 28px | Rounded card inner padding and capability strip vertical padding. |
| 40px | Section heading group to its content. |
| 48px | Gap between heading and support columns; horizontal conversion padding. |
| 56px | Opening column gap and conversion vertical padding. |
| 72px | Space before footer. |
| 96px | Major chapter top spacing and separation before conversion panel. |

### Containers and grids

- **main-container**: max width 1180px · side padding 20px. Centered marketing content; at 1440px this leaves 130px margins.
- **opening-columns**: 2 columns · gap 56px. Equal-width copy and demonstration, vertically centered.
- **section-heading-pair**: 2 columns · gap 48px. Headline at left, support at right, aligned at the bottom; support max-width 612px.
- **dossier-grid**: 3 columns · gap 20px. Three equal rounded cards, each 380px wide on desktop.
- **ruled-grid**: 3 columns · gap 0px. Feature cells share edges, forming a continuous matrix.
- **footer-grid**: 4 columns · gap 32px. A wider brand introduction followed by three link columns; proportions 1.4fr repeat(3, 1fr).

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 8px |
| content-panels | 14px |
| nested-demonstrations | 10px |
| conversion-panel | 18px |
| technical-badges | 5px |

## Surfaces and depth

### Surfaces

#### Olive canvas · level 0

**Use:** Continuous page environment.

**CSS:** `background: #141d08; color: #ecf2e0`

**Observed:** No photographic texture or floating shadow treatment; tonal changes are subtle and green throughout.

**Transfer:** Use uninterrupted dark olive between chapters rather than alternating white and black bands.

#### Dossier panel · level 1

**Use:** Audience cards, capability spotlights and product illustrations.

**CSS:** `background: #1c280c; border: 1px solid #33461a; border-radius: 14px; box-shadow: none`

**Observed:** Low-contrast fill and outline define the panel, not elevation.

**Transfer:** Group substantive arguments in this surface; keep decorative containers to a minimum.

#### Comparison emphasis · level 1

**Use:** Preferred column of a comparison table.

**CSS:** `background: rgba(198, 242, 78, 0.04); border-left: 1px solid #33461a`

**Observed:** A very faint lime tint persists down the full column, paired with a lime header label.

**Transfer:** Highlight an actual differentiator without a bright full-column fill.

#### Signal conversion panel · level 1

**Use:** Emphatic conversion call.

**CSS:** `background: #c6f24e; color: #141d08; border-radius: 18px; padding: 56px 48px`

**Observed:** The largest saturated fill is a contained, wide panel rather than a full-bleed band.

**Transfer:** Reserve this degree of brightness for one decisive ask.

#### Roadmap inset

**Use:** Future availability or mixed-ownership variants.

**CSS:** `border: 1px dashed #33461a; border-radius: 10px; padding: 14px 16px`

**Observed:** Dashed edges distinguish provisional information from the solid current offering; larger mixed-option cards use 14px corners.

**Transfer:** Use dashed treatment only when the content is genuinely provisional or a blended alternative.

## Components

### Sticky navigation

**Use:** Persistent brand and top-level access.

**CSS:** `position: sticky; top: 0px; z-index: 10; background: rgba(20, 29, 8, 0.92); backdrop-filter: blur(8px); border-bottom: 1px solid #33461a; padding: 14px 20px`

**Text style:** `small-body` — Assurestor Text 400 · 15px/1.6

**Observed:** A left wordmark balances small right-aligned links, downward chevrons and a compact lime action. Inner content follows the main container; total height is 71px. The compact action is 42px high with 14px text and 9px 14px padding.

**Transfer:** Keep navigation visually subdued so the lime action is the strongest element.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; background: #c6f24e; color: #141d08; border: 1px solid transparent; border-radius: 8px; padding: 11px 18px; height: 48px; gap: 8px`

**Text style:** `action` — Assurestor Text 600 · 15px/1.6

**Observed:** Text-only button sized to its label; paired with a quieter outline action. On the lime conversion panel, the primary reverses to deep olive with lime text.

**States:** Declared: hover background #d6fa6e; focus-visible outline 2px solid #c6f24e, outline-offset 3px, border-radius 4px. The dark variant hover background is #22310f.

### Outline button

**Use:** Secondary conversion or exploratory action.

**CSS:** `display: flex; align-items: center; background: transparent; color: #c6f24e; border: 1px solid #c6f24e; border-radius: 8px; padding: 11px 18px; height: 48px`

**Text style:** `action` — Assurestor Text 600 · 15px/1.6

**Observed:** Sits beside the primary in the opening. On lime, text becomes deep olive and the border uses rgba(20, 29, 8, 0.4).

**States:** Declared: hover color #141d08 and background #c6f24e; focus-visible outline 2px solid #c6f24e, outline-offset 3px, border-radius 4px.

### Dossier card

**Use:** Self-selection by starting point or operating model.

**CSS:** `display: flex; flex-direction: column; gap: 16px; background: #1c280c; border: 1px solid #33461a; border-radius: 14px; padding: 28px`

**Text style:** `card-heading` — Assurestor Display 600 · 22px/1.2 · tracking -0.02em

**Observed:** Audience label, short heading, explanation, ruled bullet list and bottom-aligned text link. Sibling cards share equal height even with uneven copy; model cards replace bullets with key-value rows.

**Transfer:** Use content-driven equal-height cards, not a fixed empty spacer copied between the list and link.

### Feature cell

**Use:** Dense benefits or capabilities in a continuous grid.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 26px 24px; border-right: 1px solid #33461a; border-bottom: 1px solid #33461a`

**Text style:** `feature-heading` — Assurestor Display 600 · 19px/1.6 · tracking -0.02em

**Observed:** A heading and small-body explanation sit in a square-edged matrix; the parent supplies top and left borders. No individual card radius or gutter.

**Transfer:** Use a logo or tiny category badge in place of the heading for an integration catalog.

### Card text link

**Use:** Next step at the foot of a content card.

**CSS:** `color: #c6f24e; text-decoration: none`

**Text style:** `action` — Assurestor Text 600 · 15px/1.6

**Observed:** Lime words sit directly on the card surface without a button box and align across a row of cards.

**States:** Declared: hover text-decoration underline; focus-visible outline 2px solid #c6f24e, outline-offset 3px, border-radius 4px.

### Comparison table

**Use:** Explain structural differences between approaches.

**CSS:** `border: 1px solid #33461a; border-radius: 14px; overflow: hidden`

**Text style:** `small-body` — Assurestor Text 400 · 15px/1.6

**Observed:** Three columns use proportions 0.8fr 1fr 1fr, with small uppercase row labels, a raised-olive header, horizontal rules and Comparison emphasis on the preferred column. Cell padding is 16px 22px.

**Transfer:** Compare operational consequences rather than displaying a sea of checkmarks.

### Question accordion

**Use:** Direct objection handling.

**CSS:** `padding: 18px 0px; border-bottom: 1px solid #33461a`

**Text style:** `question` — Assurestor Display 600 · 18px/1.6

**Observed:** Full-width native details rows, pale question left and small lime plus right; a top rule encloses the group. Open answers use body text in sage below the summary.

**States:** Declared: hover not specified; focus-visible outline 2px solid #c6f24e, outline-offset 3px, border-radius 4px.

### Footer directory

**Use:** Final brand summary and navigation.

**CSS:** `border-top: 1px solid #33461a; padding: 64px 0px 32px; margin-top: 72px`

**Text style:** `small-body` — Assurestor Text 400 · 15px/1.6

**Observed:** Brand summary plus three link columns, each headed by a dash-marked uppercase label. A lower rule separates legal copy and a right-aligned social/legal group. The footer remains olive after the bright conversion panel.

## Imagery and graphics

### Operational console illustration

**Use:** Primary visual proof in the opening and smaller examples inside capability spotlights.

**Observed:** A front-facing, flat olive console occupies roughly half the opening width. A slim branded toolbar sits above status tiles, an approval sequence and a small assistant conversation. Pale text, sage secondary labels and lime squares make the states readable; there is no perspective, device bezel, photograph or luminous atmospheric backdrop.

**Transfer:** Show a representative workflow in the new product's own terminology. For a service without software, make a process board with status tiles and a short request/result exchange; the minimum is a legible static HTML/SVG panel, not a generic laptop image.

**Build:** Use a 14px-radius #1c280c frame with a 1px #33461a edge, a 50px toolbar in #223110, and an 18px-padded body with 14px gaps. Arrange compact status tiles over two stacked #141d08 inset panels with 10px corners. Mark completed steps with small #c6f24e squares and pending steps with dashed olive outlines. Keep the view orthographic and shadow-free.

### Dash and square signal system

**Use:** Repeated markers for eyebrows, lists and status, throughout the page.

**Observed:** Short horizontal lime strokes lead tiny uppercase labels. Lists use small square lime bullets, subtly rounded, rather than oversized check icons. The rhythm ties explanatory content to the operational illustration.

**Transfer:** Preserve these markers even when no equivalent product imagery is available; use them to connect labels, proof rows and a process board.

**Build:** Render a short 16px by 2px #c6f24e line before an eyebrow using an inline pseudo-element and a 9px gap. For list items, use a 7px square with 2px corners and a lime fill, aligned near the first text line; separate items with olive rules.

### Partner marks

**Use:** Integration and ecosystem proof.

**Observed:** Partner wordmarks are pale monochrome, placed in the top-left of ruled cells alongside small outlined technical tags. They are embedded in explanatory content, not isolated in a colorful logo carousel.

**Transfer:** Use authorized marks in one pale color where permitted, or simple text names; accompany each with a concrete explanation of what it contributes.

### Icons

**Observed:** Navigation chevrons are 10px by 6px with 1.6px round strokes in sage. Social glyphs are 18px solid monochrome. Larger capability symbols use pale rounded outlines with a small lime focal detail.

**Transfer:** Choose simple outline symbols for capabilities, tiny chevrons for menus and restrained monochrome social marks. Avoid a different decorative icon color for each feature.

## Section recipes

How recurring sections are built.

### First screen: Argument and console opening

**Observed:** A 71px Sticky navigation crowns the dark canvas. Inside the 1180px container, the opening has 76px top and 64px bottom padding, equal columns and a 56px gap. The left stack contains a dash-marked eyebrow, a four-line 56px promise whose concluding two lines are lime, a 19px support paragraph with selected pale clauses, then Primary button and Outline button separated by 12px. The right half is the Operational console illustration, approximately 562px by 511px, vertically balanced with the text. Layers remain flat: canvas, panel, inset panels, labels and state markers. Within the first 900px the complete promise, support, actions, console and a five-column capability strip are visible; the next card-led chapter begins at the fold.

**Transfer:** Give a different product an equally concrete two-part promise and an operational illustration of its central value. With no interface, use a process board in the same frame. More focused product pages can shorten the copy while keeping the paired argument-and-proof composition.

**Avoid:** Do not substitute a centered oversized slogan, full-bleed stock photograph or empty dashboard silhouette; the opening needs enough readable operational detail to support its argument.

**Text style:** `display` — Assurestor Display 600 · 56px/1.03 · tracking -0.02em

### Capability rail

**Observed:** Five narrow columns span the container between top and bottom olive rules, with 28px vertical padding and 24px column gaps. Each has a dash-led uppercase label, a pale feature name and a short sage explanation.

**Transfer:** Use compact value signals to summarize the product's breadth, keeping each explanation to a few short lines.

### Split chapter heading

**Observed:** Section-heading type at left and 17px sage support at right use equal columns with a 48px gap and bottom alignment. Main chapters begin with 96px top spacing; the content begins 40px after the heading group. The final phrase of the headline is lime.

**Transfer:** Write a concrete consequence in the heading and the mechanism in the support paragraph.

**Text style:** `section-heading` — Assurestor Display 600 · 44px/1.08 · tracking -0.02em

### Audience dossiers

**Observed:** A Split chapter heading introduces three Dossier cards in a 20px-gap row. Uppercase starting-point labels precede tightly led headings, explanations and fine-ruled bullet lists. Links share a bottom baseline.

**Transfer:** Offer useful paths based on the reader's existing situation, not arbitrary product tiers.

### Capability spotlight

**Observed:** A Split chapter heading precedes one broad Dossier panel paired with a ruled stack or narrow Feature cells. The large panel combines an outline symbol, label, explanation and an inset operational example near its base. The security example uses roughly 638px for the panel and 522px for the ruled stack.

**Transfer:** Choose one consequential mechanism to demonstrate and use adjacent cells for related controls or advantages.

### Operating model comparison

**Observed:** Three equal cards share pale product labels, short introductions and ruled key-value rows. Two have solid olive panel surfaces; the mixed alternative is outlined with a dashed 14px-radius boundary. A small lime left rule calls attention to practical migration notes.

**Transfer:** Contrast ownership, responsibility or delivery models using the same row vocabulary, reserving dashed edges for a genuinely mixed alternative.

### Compact trust ledger

**Observed:** A left column holds an eyebrow, pale-and-lime heading and support paragraph. The right is a six-row ledger, with sage labels left and pale factual values right, separated by thin olive rules. Numbers are inline rather than giant statistical sculptures.

**Transfer:** Use verified operational facts, standards or scope measures; keep them part of the reading rhythm rather than making inflated numerals.

### Objections and signal close

**Observed:** A Split chapter heading introduces Question accordion rows. After 96px separation, the Signal conversion panel uses a 1.2fr 0.8fr grid with a 32px gap: Conversion-heading and short paragraph left, two actions stacked 12px apart at right. The panel is 253px tall at desktop. Footer directory follows after 72px, returning to the dark canvas with brand summary, three link groups and a final social/legal row.

**Transfer:** Answer friction in plain language, then offer one direct product-specific next step in the bright panel. Retain the bright conversion device even if its position changes in a shorter page.

**Text style:** `conversion-heading` — Assurestor Display 600 · 42px/1.08 · tracking -0.02em

## Page flow

**Storyline:** Promise and operational proof → reader fit → differentiated mechanisms → practical options and commercial value → trust and objections → direct conversion and directory.

### A platform landing page that helps professional buyers understand breadth without losing sight of their existing setup

1. **Promise** — Two-color argument beside a readable console, followed by a compact capability rail.
2. **Reader fit** — Three starting-point dossiers let visitors identify an appropriate path.
3. **Differentiation** — A ruled ecosystem catalog, structural comparison table and feature matrix explain how the parts work together.
4. **Capability chapters** — A broad mechanism panel with an operational inset sits beside supporting cells; an assistant chapter follows the same visual grammar.
5. **Practical options** — Three operating-model cards compare ownership and responsibilities, followed by a business-value grid.
6. **Trust** — A concise promise beside a ruled factual ledger.
7. **Objection handling** — Full-width question accordions with direct answers.
8. **Closing call** — A bright contained conversion panel, then a dark four-column directory and restrained legal/social row.

**Transfer:** Adapt the depth and ordering to the product's actual buying questions. Preserve the paired argument/proof, ruled information structures and emphatic lime conversion device without requiring the same number of chapters.

## Writing

Confident, practical and protective, with technical specificity rather than visionary hype. The tone understands the reader's existing tools, commercial constraints and fear of disruption.

**Do not copy:** Do not reuse Assurestor names, product names, wordmarks, assistant persona, customer examples, certifications, partner names or numerical claims as facts for another brand. Source copy is reference language only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we and our for the provider. Explain what remains under the reader's control.
- **Rhythm:** Short declarative headlines often split into a pale premise and lime conclusion. Support uses one or two concrete explanatory sentences, with contractions and occasional compact sentence fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the capability, then state why the combination matters. | Two short statements | “Five best‑of‑breed engines. Greater than the sum of their parts.” |
| Section heading | Complete a direct reader-facing thought with a meaningful final phrase. | 4–10 words | “Start where you are.”<br>“Your infrastructure, ours, or both.” |
| Support | Explain the mechanism and its practical consequence without a superlative. | 1–3 sentences | “A vendor's own assistant only knows its own product. Mia works across all five engines and every customer you run them for.” |
| Primary action | Verb plus concrete low-friction next step. | 3–6 words | “Book a no-obligation demo” |
| Objection answer | Answer yes or no first; explain what changes and what does not. | 2–3 sentences | “No. With [Brand] Control you keep your own licences and your own vendor relationship. The platform runs over what you already have.” |

**Words and phrasing to use:** keep; your; one place; across; same; without; fits; run; connect; approve

**Avoid:** revolutionary; game-changing; unparalleled; magic; seamless digital transformation

**Rules:**

- Tie every benefit to a mechanism or a concrete working consequence.
- Use contrast constructions such as keep what works / add what is missing.
- Put risk and ownership in everyday language before technical acronyms.
- Keep action labels explicit; avoid vague aspirational verbs.

## Do's and Don'ts

### Do

- Keep the 1180px centered container consistent across headings, grids and conversion panel.
- Use 56px display and 44px section headlines at weight 600 with -0.02em tracking.
- Set explanations in sage with 1.6 line height; use pale text for meaningful emphasis.
- Give rounded dossiers 28px padding and 20px gutters.
- Let matrix cells meet at 1px olive rules with 26px 24px padding.
- Keep the large bright conversion panel at 18px corners and invert its main action to dark.
- Carry the small dash marker into section labels and footer headings.
- Show specific readable workflow states in the opening visual rather than a generic product thumbnail.

### Don't

- Do not replace deep olive with neutral charcoal; the green cast is structural.
- Do not distribute lime background fills across every feature card; most content stays dark.
- Do not turn 8px-radius actions into pill buttons.
- Do not add card drop shadows; elevation is expressed with olive fill and fine edges.
- Do not center all chapter headings; use the 48px-gap heading/support pair.
- Do not enlarge trust numbers into oversized decorative stats; the proof ledger uses compact rows.
- Do not mix colorful ecosystem logos into the pale monochrome catalog.
- Do not use monospace for body paragraphs or all navigation; it is a small technical accent.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions are declared at 0.15s; buttons transition background, border-color and color at 0.15s.
- Two pulse animations are declared at 2.4s ease-in-out with infinite repetition.

**Transfer:**

- Keep interaction changes chromatic and restrained; do not animate whole content panels as if they were floating objects.

**Unknown:**

- The precise animated targets and pulse keyframes are not established here; scroll choreography is unknown.

### Responsive

**Observed:**

- Headline sizes use clamps: opening 36–56px, sections 30–44px and conversion 28–42px.
- Only the desktop two- and three-column arrangements are established.

**Transfer:**

- On narrow layouts, stack the promise before the operational illustration, keeping its labels legible rather than scaling the entire panel into unreadable text.
- Collapse heading/support pairs and dossiers to a single reading column while preserving their distinct surfaces; retain the contained lime conversion panel.

**Unknown:**

- Exact breakpoint widths, mobile navigation and mobile spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
