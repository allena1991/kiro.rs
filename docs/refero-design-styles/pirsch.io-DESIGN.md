# Pirsch — cream cards, mint signals

## Overview

A friendly, light software-marketing style with black geometric sans typography, warm cream panels and small mint-green and buttery-yellow signals. Large centered promises give way to neatly arranged product explanations, miniature interface diagrams and human proof. The feel is approachable and spacious rather than enterprise-heavy, with dense information contained inside soft cards.

### Essentials

- Big promises stay plain black and medium-weight: DM Sans 96px/1.25 with -2px tracking for the main opening, then 64px/1.25 with -1px tracking for section leads.
- The opening is a centered promise above a tangible product: 192px top padding, a 768px support measure, paired 48px-high actions and a 1200px-wide cream-backed interface entering the first screen.
- Warmth belongs in the containers, not the whole canvas: white page, #f8f5ed cards with 24px corners, 48px feature-card padding and 32px grid gaps.
- Conversion color is a small signal, not a full-page theme: mint #6ece9d leads, yellow #ffda6e marks a secondary emphasis; both carry black text in 12px-radius buttons, with 6px corners on compact actions.
- Capabilities read as numbered chapters: a 40px-high translucent capsule combines a circular number with a 14px uppercase label tracked at 4px, above a centered heading and support line.
- Product explanation is diagrammatic and gently faded: cream-backed interface fragments, thin mint paths, neutral chips and clipped edge fades. Every new page needs a concrete product stage and small explanatory diagrams; use an honest schematic workflow when a finished interface is unavailable.
- The ending stays light and expansive: a centered 64px closing question with one mint action gives way to a white footer whose broad identity area sits left of two stacked columns of link groups.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint action | `#6ece9d` | `--color-mint` | action, accent | Primary conversion actions, active indicators and restrained diagram outlines. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter yellow | `#ffda6e` | `--color-yellow` | action, accent | Highlighted feature actions, diagram tags and recommended-tier markers. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text | Headings, navigation, button labels and primary diagram marks. |
| Reading gray | `#707070` | `--color-muted` | text | Paragraphs, footer links and secondary labels. |
| Soft neutral wash | `#f5f5f5` | `--color-soft` | surface, border | Visible result of black at 4% over white; secondary actions, numbered capsules and table rules use rgba(0, 0, 0, 0.04). |
| Warm cream | `#f8f5ed` | `--color-card` | surface | Feature cards, product stages, quotes, plan cards and question panels. |
| White canvas | `#ffffff` | `--color-canvas` | background | Default page background and open space between cream panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Quote gray | `#adadad` | `--color-quote-action` | action | Custom-plan contact actions rather than the default conversion action. |

## Typography

- **DM Sans** — All marketing headings, paragraphs, navigation and actions. Open geometric sans with rounded counters; medium headings and regular supporting copy. OpenType features: "ss03", "ss04". Font stack: "DM Sans", Roboto, -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | DM Sans | 500 | 96px | 1.25 | -2px | Primary landing-page promise. |
| heading-lg | DM Sans | 500 | 64px | 1.25 | -1px | Centered section headings and closing question; also the restrained title on pricing pages. |
| heading | DM Sans | 500 | 28px | 1.25 | normal | Feature-card titles and accordion questions. |
| footer-heading | DM Sans | 500 | 24px | 1.25 | normal | Footer identity and link-group headings. |
| attribution | DM Sans | 500 | 20px | 1.5 | normal | Customer name beside a circular portrait. |
| body | DM Sans | 400 | 18px | 1.5 | normal | Introductory support lines and feature descriptions. |
| action | DM Sans | 500 | 18px | 1.5 | normal | Full-size action labels and emphasized inline links. |
| small-body | DM Sans | 400 | 16px | 1.5 | normal | Customer quotations, supporting identity labels and footer links. |
| navigation | DM Sans | 500 | 16px | 1.5 | normal | Navigation, compact actions and chapter numbers. |
| eyebrow | DM Sans | 500 | 14px | 1.5 | 4px, uppercase | Short chapter descriptors inside numbered capsules. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | DM Sans | 500 | 56px | 1.5 | normal | Large price amount and currency, or a short custom-price word. |
| pricing pages | plan-title | DM Sans | 500 | 32px | 1.5 | normal | Tier names above the price. |
| pricing pages | comparison | DM Sans | 400 | 16px | 1.2 | normal | Compact comparison-table values. |

**Notes:**

- The two largest roles tighten tracking but retain a relaxed 1.25 line height; do not substitute a heavy display cut.
- Support copy is usually gray and centered outside cards, left-aligned inside them. Body and action labels share size but differ in weight and color.
- Uppercase is reserved for the tiny, widely spaced chapter labels. Headings and buttons favor title case.

## Layout

**Density:** Airy between chapters and within introductions; comfortably compact inside explanatory cards and comparison rows.

### Spacing

**Spacing system:**

- **grid** 8px — Primary layout rhythm; 16px, 24px, 32px, 48px, 64px, 128px and 192px carry most reusable spacing.

| Value | Use |
| --- | --- |
| 8px | Footer-link vertical separation. |
| 16px | Heading-to-copy gap within cards and gap between paired actions. |
| 24px | Navigation gaps, table column gaps and horizontal button padding. |
| 32px | Main grid gaps, centered heading-stack gaps and quote or question-panel padding. |
| 48px | Default feature and plan-card padding; hero support-to-action gap. |
| 64px | Footer vertical padding and comparison-table separation. |
| 128px | Separation after the opening product stage. |
| 192px | Opening top padding and separation between major chapters. |

### Containers and grids

- **main-container**: max width 1200px · side padding 16px. Centered content frame; at 1440px the main content has 120px outer margins.
- **support-measure**: max width 768px. Centered explanatory copy, usually two lines.
- **feature-grid**: 3 columns · gap 32px. Equal feature cards, with two-column and 2:1 / 1:2 bento variants using the same frame.
- **footer-grid**: max width 1200px · 5 columns · gap 48px. Broad left identity region, open middle space, then link groups in two right-hand columns; secondary groups stack below the first pair.
- **comparison-grid** (only for pricing pages): max width 960px · 4 columns · gap 24px. One feature column at 1.5fr followed by three equal plan columns.

## Corner radius

| Element | Radius |
| --- | --- |
| cards | 24px |
| main-actions | 12px |
| compact-actions | 6px |
| chapter-capsules | 20px |
| portraits | 50% |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default light marketing page.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Open white space surrounds warm content islands; there are no alternating dark marketing bands.

**Transfer:** Use the cream panels to group information instead of tinting the entire page.

#### Cream card · level 1

**Use:** Reusable information and media panel.

**CSS:** `background: #f8f5ed; border-radius: 24px; backdrop-filter: blur(24px); box-shadow: none`

**Observed:** The warm opaque fill is visually dominant; edges are rounded without a visible outline.

**Transfer:** Carry the same material through features, proof and plans.

#### Neutral wash · level 1

**Use:** Secondary controls and chapter markers.

**CSS:** `background: rgba(0, 0, 0, 0.04)`

**Observed:** A very pale black tint distinguishes controls without introducing a new hue.

**Transfer:** Use for low-emphasis UI, not as a replacement for cream content cards.

#### Recommended column · level 1

**Only for:** pricing pages

**Use:** Continuous emphasis through a comparison table.

**CSS:** `background: rgba(0, 0, 0, 0.04); border-radius: 24px 24px 0px 0px`

**Observed:** The selected column is gray rather than yellow; its small action is yellow. The lower end closes with rounded bottom corners.

**Transfer:** Shade one column continuously rather than coloring every cell independently.

## Components

### Fixed navigation

**Use:** Persistent, compact site navigation.

**CSS:** `position: fixed; height: 88px; padding: 0px 16px; z-index: 10; display: grid; grid-template-columns: 1fr minmax(320px, 1200px) 1fr`

**Text style:** `navigation` — DM Sans 500 · 16px/1.5

**Observed:** A black symbol and wordmark sit left; dropdown labels, plain links and Compact button align right with 24px gaps. Small filled chevrons mark dropdowns.

**Transfer:** Keep the nav visually light and the conversion action compact.

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #6ece9d; color: #000000; border-radius: 12px; height: 48px; padding: 0px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — DM Sans 500 · 18px/1.5

**Observed:** A flat mint rectangle with softened corners, without an arrow. Yellow is the warm emphasis variant in feature panels and recommended plans; custom-plan contact actions are gray.

**States:** Declared: hover opacity 0.8; focus-visible and active unspecified.

**Transfer:** Use the mint variant as the default, yellow only for a deliberate local emphasis.

### Secondary button

**Use:** Paired exploratory action.

**CSS:** `background: rgba(0, 0, 0, 0.04); color: #000000; border-radius: 12px; height: 48px; padding: 0px 24px`

**Text style:** `action` — DM Sans 500 · 18px/1.5

**Observed:** Sits beside Primary button at equal height, with 16px between them; uses fill instead of an outline.

**States:** Declared: hover opacity 0.8; focus-visible and active unspecified.

### Compact button

**Use:** Navigation and smaller conversion prompts.

**CSS:** `background: #6ece9d; color: #000000; border-radius: 6px; height: 36px; padding: 0px 16px`

**Text style:** `navigation` — DM Sans 500 · 16px/1.5

**Observed:** Same flat action treatment at a smaller scale. Comparison-table variants use 12px side padding and mint, yellow or gray fills.

**States:** Declared: hover opacity 0.8; focus-visible and active unspecified.

### Chapter capsule

**Use:** Numbered category above a capability introduction.

**CSS:** `display: flex; align-items: center; background: rgba(0, 0, 0, 0.04); border-radius: 20px; height: 40px; backdrop-filter: blur(24px); overflow: hidden`

**Text style:** `eyebrow` — DM Sans 500 · 14px/1.5 · tracking 4px · uppercase

**Observed:** A 40px circular number uses Navigation type and a second layer of neutral wash; the uppercase descriptor follows with 16px left and 24px right padding.

**Transfer:** Use short benefit categories and a simple sequence number; do not turn these into navigation tabs.

### Feature card

**Use:** One compact product argument with a visual explanation.

**CSS:** `background: #f8f5ed; border-radius: 24px; padding: 48px; display: flex; flex-direction: column; gap: 32px; backdrop-filter: blur(24px)`

**Text style:** `heading` — DM Sans 500 · 28px/1.25

**Observed:** Title and paragraph are grouped with a 16px gap; a small diagram or interface fragment follows. Cards stretch to their grid row and can span two columns.

**Transfer:** Give each card one outcome and one visual mechanism.

### Testimonial card

**Use:** Human proof in a three-column card wall.

**CSS:** `background: #f8f5ed; border-radius: 24px; padding: 32px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `small-body` — DM Sans 400 · 16px/1.5

**Observed:** A 64px circular portrait precedes a name in Attribution type and a gray organization label. The quotation is gray body text below, not a large decorative pull quote.

**Transfer:** Retain real variation in quote length; keep people and prose more prominent than logos.

### Footer link

**Use:** Quiet directory links.

**CSS:** `color: #707070; margin-top: 8px; margin-bottom: 8px; transition: opacity 0.1s`

**Text style:** `small-body` — DM Sans 400 · 16px/1.5

**Observed:** Plain text in long vertical lists below black Footer-heading labels; no boxes or arrows.

**States:** Declared: hover opacity 0.8; focus-visible and active unspecified.

### Question panel

**Only for:** pricing and objection-handling sections

**Use:** Accordion question row.

**CSS:** `background: #f8f5ed; border-radius: 24px; padding: 32px; max-width: 960px`

**Text style:** `heading` — DM Sans 500 · 28px/1.25

**Observed:** Question left, thin black plus right; closed rows are about 99px high and stack 32px apart. Answer text uses Body with a 24px separation when expanded.

**Transfer:** Keep questions specific and answers explanatory rather than promotional.

### Comparison cell

**Only for:** pricing pages

**Use:** Dense feature matrix.

**CSS:** `border-top: 2px solid rgba(0, 0, 0, 0.04); padding: 16px 24px; display: flex; align-items: center; justify-content: center; height: 56px`

**Text style:** `comparison` — DM Sans 400 · 16px/1.2

**Observed:** Values align under plan headings; feature labels align left. Mint, yellow and gray ticks distinguish the tier accents. Category strips use the Neutral wash and fade softly at the table edges.

**Transfer:** Use a wider first column and a single shaded recommendation column.

## Imagery and graphics

### Product stage

**Use:** Large opening proof object and selected capability illustrations.

**Observed:** A straight-on, warm cream dashboard fills nearly the container width beneath the opening copy. Its top corners are rounded; mint outlines emphasize a few controls. It enters the first screen as a partial object, with the full interface below. There is no dramatic perspective, device mockup or hard shadow.

**Transfer:** Render a real primary workflow in a warm neutral frame. Without finished UI, build a legible schematic with a toolbar, main content area and one meaningful result; do not replace the object with abstract blobs.

**Build:** Use a 1200px-wide cream panel with 24px corners. Arrange a toolbar above white content blocks, gray labels and restrained mint paths. Highlight only a few meaningful controls with thin mint rounded outlines.

### Miniature mechanism diagrams

**Use:** Inside feature cards, below the text.

**Observed:** Tiny funnels, step paths, tags, filters and chart fragments use black text, pale neutral chips, thin mint rules and occasional yellow separators. They stay subordinate to the heading and are often faded into the cream backing along their outer or lower edges.

**Transfer:** Show the new product's mechanism in a few labels and connectors rather than inserting a full unreadable screen into every card.

**Build:** Create SVG or HTML groups on a transparent backing: small neutral rectangles, black labels, mint 1px connectors and a few yellow markers. Place the diagram below the paragraph with 32px separation; apply a transparent-to-opaque mask over the last 15–25% of a fading edge.

### Orbital collaboration diagram

**Use:** A wide capability card with text left and a large diagram right.

**Observed:** Thin pale-gray concentric arcs are clipped within the right half of a cream card. A circular portrait and yellow rounded domain-like labels ride on the arcs; peripheral labels fade softly.

**Transfer:** Translate this into people, documents, tasks or connected entities appropriate to the new product. The minimum version uses one circle token and three short yellow labels on fine arcs.

**Build:** In a clipped right-half SVG, draw two or three large unfilled circles with rgba(0,0,0,0.12) 1px strokes, with their centers beyond the right edge. Add one circular portrait or initials token and yellow tags along the curves; mask the top and bottom edges into the cream panel.

### People and logos

**Use:** Trust strip, customer quotes and compatibility proof.

**Observed:** Small overlapping circular headshots pair with yellow stars near the opening actions. Testimonials use individual circular portraits. Customer and integration logos are mostly black or gray with ample separation, not brightly colored tiles.

**Transfer:** Use genuine authorized portraits and restrained monochrome marks; a compact real endorsement can replace a star rating when no rating exists.

### Theme preview pair

**Only for:** customization demonstrations

**Use:** A visual comparison beside two stacked descriptive cards.

**Observed:** Two tall interface panels sit side by side in a larger cream panel, one charcoal and one deep forest green. Chart lines remain mint or pale neutral; the outer edges fade into the cream backing.

**Transfer:** Keep alternate palettes confined to the actual product preview; preserve the surrounding light marketing system.

**Build:** Place two rounded interface images in an overflow-hidden cream card and use a horizontal alpha mask that fades only the outer ends.

### Icons

**Observed:** Simple black outline symbols, typically 24px with 2px strokes; question-panel plus icons sit in approximately 34px boxes. Dropdown chevrons are small filled shapes about 10px by 6px.

**Transfer:** Choose unembellished line icons; reserve full-color marks for recognizable product or integration identities.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and product opening

**Observed:** White Canvas behind Fixed navigation. The content starts with 192px top padding: a single centered Display line spans roughly two thirds of the content width. A gray Body paragraph follows after 32px within Support-measure, then Primary button and Secondary button after 48px, separated by 16px. A compact portrait-and-rating trust row sits below the actions. The cream Product stage spans the 1200px frame and begins around 632px down the page. Within the first 900px, the full headline, two-line support, both actions, trust row and upper interface are visible; most of the interface and the logo strip fall below.

**Transfer:** Center a short outcome-led promise above a concrete product stage, using a schematic workflow if necessary. Pricing-oriented pages open with Heading-lg instead of Display, then a usage selector and billing switch above three cream plans; their first screen reveals the plan headings and prices.

**Avoid:** Do not split the default opening into left text and right illustration, or shrink the product into a floating phone beside the headline.

**Text style:** `display` — DM Sans 500 · 96px/1.25 · tracking -2px

### Numbered capability chapter

**Observed:** Chapter capsule, Heading-lg and centered Body support stack with 32px gaps. A Feature-card grid follows, separated from the support by roughly 64px to the card edge. Major chapters have 192px separation.

**Transfer:** Organize capabilities around user outcomes; preserve the capsule and centered introduction without requiring a particular number or order of chapters.

**Text style:** `heading-lg` — DM Sans 500 · 64px/1.25 · tracking -1px

### Bento explanation

**Observed:** Feature cards combine 2:1 and 1:2 rows, equal pairs, equal triples, or a wide top card with a pair below. Gaps stay 32px throughout. Orbital collaboration diagram uses a wide card; Theme preview pair uses two stacked text cards beside one larger visual.

**Transfer:** Vary span according to explanation complexity while keeping corners and inner spacing consistent.

### Human proof wall

**Observed:** A centered capability introduction precedes three equal columns of Testimonial cards. Names and portraits sit above gray, moderately sized quotations; warm panels give the wall cohesion despite different quote lengths.

**Transfer:** Show verified experiences with enough detail to substantiate the promise rather than a row of anonymous superlatives.

### Open closing invitation

**Observed:** A centered Heading-lg question, two-line Body reassurance and one Primary button sit directly on Canvas, with 32px gaps. There is no colored enclosure. The footer begins after a 192px interval and retains 64px vertical padding, a wide identity area left, and two columns of link groups right; secondary groups sit below them.

**Transfer:** Close with one specific next step and its friction-reducing condition, then an extensive but visually quiet directory.

### Plans and comparison

**Only for:** pricing pages

**Observed:** Three equal Cream cards carry Plan-title, Price, a quiet separator, ticked benefits and bottom-aligned actions. The recommendation gets yellow markers and action, not a different card material. A later 960px comparison matrix uses Comparison cell and Recommended column; a usage slider and small billing switch precede the plans.

**Transfer:** Keep tiers immediately understandable and move exhaustive detail to the narrower matrix.

### Objection handling

**Only for:** pricing and objection-handling sections

**Observed:** Centered Heading-lg and gray Body support with dark inline links lead into a 960px-wide stack of Question panels. The closed presentation is spare: one question and one plus per row.

**Transfer:** Use this treatment for practical uncertainties after the offer; do not expose all answer paragraphs at once.

## Page flow

**Storyline:** Promise → tangible product or offer → trust → structured explanation → proof or objection handling → open closing invitation → directory.

### Product marketing landing page

1. **Promise** — Oversized centered outcome with paired trial and demo actions.
2. **Product demonstration** — Large cream interface stage followed by restrained customer logos.
3. **Capability chapters** — Numbered centered introductions and varying cream bento grids explain ease, depth and adaptability.
4. **Social proof** — Portrait-led three-column quote wall.
5. **Closing call** — Large centered question, short reassurance and mint action.
6. **Directory** — White footer with broad identity area and stacked right-hand link groups.

**Transfer:** Choose chapters around the new product's buyer journey; retain product concreteness, small mechanism diagrams and human proof without duplicating the subject matter.

### Pricing and purchase evaluation page

1. **Offer** — Smaller centered title, short trial reassurance, usage and billing controls.
2. **Pricing** — Three cream plans with large amounts and distinct action accents.
3. **Social proof** — Monochrome customer logo strip.
4. **Detailed comparison** — Narrow four-column matrix with a continuous gray recommendation column.
5. **Objection handling** — Cream question-panel stack with direct support links.
6. **Closing call** — Same open invitation treatment and directory ending.

**Transfer:** Let the entry offer remain concise while moving exhaustive feature differences and purchase concerns into scoped evaluation components.

## Writing

Friendly, direct and benefit-led, with concrete mechanisms following broad promises. Confidence comes from ease-of-use language and explicit practical reassurance rather than an austere technical tone.

**Do not copy:** Do not reuse Pirsch names, logos, customer identities, quotes, numerical adoption claims, compliance claims, locations or trial and pricing terms without independently valid equivalents. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; the product is named in explanatory paragraphs, while we appears naturally in support answers.
- **Rhythm:** Headlines are short title-case phrases, often imperative. Support is usually one or two sentences; feature paragraphs explain a mechanism in plain language, with longer detail reserved for questions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short verb-led outcome that expands what the reader can do. | 3–6 words | “See Beyond Clicks” |
| Capability heading | Concrete action plus a practical benefit. | 3–6 words | “Set Up in Minutes”<br>“Make It Your Own” |
| Supporting explanation | Name the method, then the result, using everyday vocabulary. | 1–2 sentences | “Effectively visualize and fully understand user journeys in a matter of seconds.” |
| Primary action | Start or get plus a clear low-friction offer. | 4–5 words | “Start Your Free Trial”<br>“Get Started For Free” |
| Closing invitation | A friendly readiness question tied to the central outcome. | 6–9 words | “Ready to Level up Your Analytics?” |
| Objection | A real buyer question with a direct explanatory answer. | 5–12 words | “Can I export my data?” |

**Words and phrasing to use:** simply; easy-to-use; get started; your; in minutes; with one click; make it your own

**Avoid:** revolutionary; synergize; disrupt; world-dominating; mysterious metaphors

**Rules:**

- Follow outcome headings with the actual mechanism that delivers the benefit.
- Pair conversion prompts with an accurate condition that lowers perceived risk.
- Use occasional conversational questions; avoid shouting punctuation and long strings of buzzwords.
- Keep navigation and action labels literal enough to predict the destination.

## Do's and Don'ts

### Do

- Keep the main promise at 96px, weight 500 and -2px tracking on desktop.
- Use 64px/1.25 headings to unify chapters and the final invitation.
- Hold support paragraphs to 768px and center them outside cards.
- Use 24px cream-card corners with 48px inner padding for capability explanations.
- Maintain 32px grid gaps even as card spans change.
- Reserve mint and yellow for small actions, markers and explanatory paths.
- Use 32px padding for quotes and question panels to distinguish them from feature cards.
- Preserve the broad identity area and stacked right-hand groups in the white footer.

### Don't

- Do not replace medium-weight headings with 700-weight condensed display type.
- Do not give main buttons pill corners; the default is 12px, compact actions 6px.
- Do not turn cream cards into bright mint or yellow feature blocks.
- Do not add strong drop shadows or dark borders around the flat cream panels.
- Do not let alternate dark product themes become full-page dark marketing sections.
- Do not style testimonials as oversized italic serif pull quotes.
- Do not highlight every plan with a saturated card background; recommendation emphasis is local.
- Do not make all supporting copy black; #707070 is the sustained secondary reading color.

## Motion and responsive

### Motion

**Observed:**

- Action opacity transitions are declared at 0.1s with hover opacity 0.8.
- Section and card entrances declare opacity and transform transitions of 0.4s ease.
- Three control highlights declare a 1.5s ease infinite pulse.
- Decorative rotation declares 30s or 40s linear infinite cycles in both directions.

**Transfer:**

- Keep action feedback understated through opacity rather than color inversion.
- Use slow decorative movement only within product explanation; keep the headline and grid geometry stable.

**Unknown:**

- Exact travel distances, animation triggers, full pulse keyframes and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 512px, 513px, 768px, 769px and 1024px.

**Transfer:**

- Recommended adaptation: preserve the centered promise and cream product stage while stacking actions and bento cards as space narrows.
- Recommended adaptation: retain readable plan and comparison content rather than compressing all four table columns into tiny text; use a scrollable comparison region.

**Unknown:**

- Mobile type sizes, navigation replacement, exact grid collapse and mobile spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
