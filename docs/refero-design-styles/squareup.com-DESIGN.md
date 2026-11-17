# Square — commercial theatre, editorial soul

## Overview

A business-facing style with the confidence of a product launch and the warmth of an editorial spread. White and black expanses surround electric blue, metallic product close-ups, lived-in photography and crisp interface demonstrations. Refined serif headlines contrast with practical grotesk text and widely spaced mono labels; the overall density is low until the detailed service footer.

### Essentials

- The opening is a product theatre, not a text column: a 1424×820px stage with 20px corners and 8px outer margins, a macro object, and a centered 760×420px white word sculpture. Carry the oversized lettering device to new products with original rounded SVG lettering over a close-up or a carefully lit interface detail.
- Editorial promises sit above utilitarian detail: Exact Block headings at 40px/45px, weight 400, -0.02em tracking contrast with 16px/24px sans body text and 14px/21px uppercase mono labels tracked at 0.1em.
- Conversion lives in small capsules: 44px actions with 50px or 100px radii, white-and-blue pairing, and a 770×66px translucent black action dock with 14px backdrop blur in the opening.
- Color arrives as a scene, not scattered decoration: electric #004bff fills the opening behind the object; most subsequent content is white, then a long #000000 environment. Action blue #006aff is reserved for compact conversion controls.
- Demonstrations feel inhabited: a large interface floats over soft-focus, grainy real-world photography; text occupies roughly one third and the visual roughly three fifths of the split section. If no physical product exists, stage a real workflow interface over a relevant working environment.
- The closing promise becomes an intimate poster inside a dark room: a 480px square photographic tile, rounded corners, 72px/72px white serif headline with -0.04em tracking, and paired pill actions. Preserve this concentrated photographic call to action somewhere in the page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric stage blue | `#004bff` | `--color-stage-blue` | background, accent, text | Saturated opening field and white-button text within that scene. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion blue | `#006aff` | `--color-action-blue` | action, link | Filled conversion buttons and blue labels on white companion actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background | Primary text on white and the continuous dark environment for proof, pricing, conversion and footer. |
| Charcoal badge | `#1f1f1f` | `--color-badge` | surface | Small value badge within dark pricing. |
| Dark divider | `#2d2d2d` | `--color-dark-rule` | border | Visible footer edge from rgba(128,128,128,0.35) over black. |
| Utility gray | `#707070` | `--color-muted` | text, border | Light-theme eyebrows, footer category labels and the inset input edge. |
| Dark-theme label gray | `#999999` | `--color-dark-label` | text | Uppercase labels on black. |
| Secondary inverse | `#bbbbbb` | `--color-secondary-inverse` | text | Small supporting and consent text on black. |
| Light divider | `#cccccc` | `--color-rule` | border | Accordion separators and pricing title dividers. |
| Warm porcelain | `#f7f6f5` | `--color-product-backdrop` | surface | Neutral backing for isolated product tiles. |
| White | `#ffffff` | `--color-paper` | text, background, surface, border | Light canvas, inverse headings, white buttons and strong pricing dividers. |

## Typography

- **Exact Block** — Section headlines, closing promise and price figures. Expressive editorial serif with fine strokes, compact spacing and prominent curved forms. If unavailable, use **Instrument Serif**. Use regular for headings; preserve tight tracking and balanced short lines. Font stack: "Exact Block", "Instrument Serif", Georgia, "Times New Roman", serif.
- **Cash Sans** — Body copy, navigation, statistics and plan titles. Clean business grotesk with open, readable lowercase and restrained medium weights. If unavailable, use **Inter**. Use 400 and 500; retain the compact line lengths. Font stack: "Cash Sans", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Square Sans Text VF** — Action labels and footer navigation. Practical sans with compact, sturdy medium letterforms. If unavailable, use **Inter**. Font stack: "Square Sans Text VF", "Inter", Helvetica, Arial, sans-serif.
- **Cash Sans Mono** — Uppercase section markers and small badges. Evenly spaced utility lettering with conspicuously open tracking. If unavailable, use **IBM Plex Mono**. Font stack: "Cash Sans Mono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | Exact Block | 400 | 72px | 1 | -0.04em, features "calt", "clig", "dlig", "hlig", "liga" | Concentrated two-line conversion headline. |
| statistic | Cash Sans | 500 | 56px | 1 | -0.03em | Large numeric proof and audience-panel labels. |
| heading | Exact Block | 400 | 40px | 1.125 | -0.02em, features "calt", "clig", "dlig", "hlig", "liga" | Default section promise in short balanced lines. |
| hero-support | Cash Sans | 400 | 20px | 1.2 | -0.01em | One-line benefit inside the opening action dock. |
| navigation | Cash Sans | 500 | 18px | 1.5 | normal | Opening navigation labels. |
| body | Cash Sans | 400 | 16px | 1.5 | normal | Explanatory paragraphs and short plan descriptions. |
| action | Square Sans Text VF | 500 | 16px | 1.5 | normal | Buttons and underlined text actions. |
| feature-label | Cash Sans | 500 | 16px | 1.5 | normal | Accordion capability titles. |
| footer-category | Square Sans Text VF | 500 | 16px | 1.75 | normal | Muted category headings in footer. |
| eyebrow | Cash Sans Mono | 500 | 14px | 1.5 | 0.1em, uppercase | Section category labels; gray on light, lighter gray on black. |
| footer-link | Square Sans Text VF | 500 | 14px | 1.5 | normal | Dense but clearly separated footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing comparisons | price | Exact Block | 500 | 56px | 1 | -0.03em | Large monthly prices with the cadence of a headline. |
| pricing comparisons | plan-title | Cash Sans | 500 | 24px | 1.2 | -0.01em, features "calt", "clig", "dlig", "hlig", "liga" | Plan names in a comparison row. |

**Notes:**

- The opening's enormous white lettering is artwork rather than the editorial type family. Give it its own SVG treatment; do not scale the normal section serif to imitate it.
- Use sentence case for promises and actions. Uppercase is reserved for mono category markers.
- Keep section copy near 548px wide and accordion text near 440px wide. Tighten serif tracking from -0.02em to -0.04em as the headline grows.

## Layout

**Density:** Airy: large media-led chapters surround short text stacks; only the footer becomes dense.

### Spacing

**Spacing system:**

- **step** 10px — Primary rhythm for component gaps, padding and section spacing.

| Value | Use |
| --- | --- |
| 10px | Tight action pair and title-to-description gaps. |
| 20px | Standard text-stack gaps, media gutters and eyebrow-to-heading separation. |
| 30px | Pricing card side padding and footer column gaps. |
| 40px | Text-to-action separation and internal plan row spacing. |
| 60px | Desktop outer content margins and footer vertical padding. |
| 80px | Standard major-section vertical padding. |
| 120px | Large chapter spacing and heading-to-plan separation. |
| 140px | Separation between the capability heading and accordion group. |
| 160px | Vertical padding around the concentrated closing composition. |

### Containers and grids

- **content**: max width 1320px · side padding 60px. Centered desktop content with aligned chapter headings and footer columns.
- **text-stack**: max width 548px. Compact editorial text block; leave adjacent space to the media.
- **capability-split**: 12 columns · side padding 60px. 440px left sidebar with a large 830px visual on the right, extending to the viewport edge.
- **product-carousel**: gap 20px. Horizontally scrolling 440×540px product stages; show the next item continuing beyond the viewport.
- **comparison**: max width 1320px · 3 columns · gap 20px. Equal-width, ruled pricing columns rather than floating cards.
- **footer-columns**: max width 1320px · 4 columns · gap 30px. Four broad navigation columns, with additional categories nested within the final column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 50px |
|  | hero-actions-and-dock | 100px |
|  | hero-stage | 20px |
|  | input | 10px |
| pricing comparisons | value-badge | 5px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| input-edge | `0px 0px 0px 1px #707070 inset` | An inset outline defines the black newsletter field; not a raised card shadow. |

### Surfaces

#### Light canvas · level 0

**Use:** Product browsing and capability explanations.

**CSS:** `background: #ffffff; color: #000000`

#### Dark environment · level 0

**Use:** Proof, rich media, plan comparison, closing call and service footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Continuous black chapters dominate the latter portion of the page; they do not become individually rounded containers.

**Transfer:** Use a sustained dark environment to deepen the page, rather than alternating every small block.

#### Electric stage · level 1

**Use:** Opening product launch scene.

**CSS:** `background: #004bff; border-radius: 20px; overflow: hidden`

**Observed:** Large metallic media covers much of the blue field; white framing remains visible outside.

**Transfer:** Let blue remain a single emphatic environment behind the hero object.

#### Porcelain product stage · level 1

**Use:** Isolated product selection tiles.

**CSS:** `background: #f7f6f5; overflow: hidden`

**Observed:** Tall rectangular stages center the object without a decorative frame.

**Transfer:** Give each product the same backing and object scale.

#### Smoked action dock · level 2

**Use:** Legible benefit and actions over opening media.

**CSS:** `background: rgba(0, 0, 0, 0.48); backdrop-filter: blur(14px); border-radius: 100px; padding: 10px`

**Observed:** The dock is centered near the stage's bottom, bringing a thumbnail, benefit and paired actions into one horizontal unit.

**Transfer:** Keep glass confined to this functional overlay instead of spreading it across the page.

## Components

### Global navigation

**Use:** Orientation at the top and a compact conversion strip while reading.

**CSS:** `height: 72px; background: #ffffff; color: #000000; display: flex; align-items: center; gap: 12px; padding: 4px 22px`

**Text style:** `navigation` — Cash Sans 500 · 18px/1.5

**Observed:** A small symbol leads, product categories run left, account and utility controls align right. While scrolling, this becomes a white strip with the symbol and two actions.

**Transfer:** Use the project's own small symbol and a short set of product categories.

### Primary button

**Use:** Compact sales or trial conversion.

**CSS:** `height: 44px; background: #006aff; color: #ffffff; border-radius: 100px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Square Sans Text VF 500 · 16px/1.5

**Observed:** The filled blue action sits beside a white companion; its width follows the label, about 143px for the sales action.

**States:** Declared: hover color inherit; focus-visible not specified; active color #000000.

### White companion button

**Use:** A secondary path over photography or dark surfaces.

**CSS:** `height: 44px; background: #ffffff; color: #006aff; border-radius: 50px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Square Sans Text VF 500 · 16px/1.5

**Observed:** White fills create a calm counterweight to the blue action. The opening variant uses stage-blue text and 100px corners; the scrolling navigation companion has a blue outline.

**Transfer:** Keep the white-and-blue pair small enough that media remains dominant.

### Underlined text link

**Use:** Exploration below short explanations and product imagery.

**CSS:** `color: #000000; background-image: linear-gradient(#000000, #000000); background-size: 100% 1.5px; background-repeat: no-repeat; background-position: 100% 100%; padding-bottom: 3px`

**Text style:** `action` — Square Sans Text VF 500 · 16px/1.5

**Observed:** Text is underlined rather than surrounded by a button box. The inverse version uses white type and underline on black.

**States:** Declared: hover color inherit; focus-visible not specified; active color #000000. Background-size transition .3s cubic-bezier(0, 0, .2, 1).

### Hero action dock

**Use:** Connect the spectacular opening to a concrete benefit and next steps.

**CSS:** `max-width: 770px; height: 66px; display: flex; align-items: center; gap: 12px; padding: 10px; border-radius: 100px; background: rgba(0, 0, 0, 0.48); backdrop-filter: blur(14px)`

**Text style:** `hero-support` — Cash Sans 400 · 20px/1.2 · tracking -0.01em

**Observed:** A small rounded video thumbnail with play icon leads the single-line benefit; a white button and blue button finish the row.

**Transfer:** Use one meaningful product thumbnail, not an avatar stack.

### Capability accordion

**Use:** Explain a family of features while one large demonstration stays in view.

**CSS:** `border-top: 1px solid #cccccc; color: #000000; max-width: 440px`

**Text style:** `feature-label` — Cash Sans 500 · 16px/1.5

**Observed:** Closed rows are about 65px tall. A right-aligned plus becomes a minus for the open item; its paragraph and underlined action sit beneath. Summary padding is 10px 0 30px.

**Transfer:** Each item should reveal a materially different product scene.

### Newsletter input

**Use:** Single-field sign-up near the ending.

**CSS:** `background: #000000; height: 45px; border-radius: 10px; padding: 12px 16px; box-shadow: 0px 0px 0px 1px #707070 inset`

**Observed:** A 510px field and 120px submit action form a 650px row with 20px gap, with consent text below.

**Transfer:** Keep the form subordinate to the closing poster and provide a visible field label.

### Footer link column

**Use:** Dense site navigation in the black ending.

**CSS:** `display: flex; flex-direction: column; gap: 10px; color: #ffffff`

**Text style:** `footer-link` — Square Sans Text VF 500 · 14px/1.5

**Observed:** Muted category headings precede white links. Four columns share the 1320px content width; contact details and company links occupy the final column.

**States:** Declared: hover color #ffffff; focus-visible not specified; active color #000000.

### Ruled plan column

**Only for:** pricing comparisons

**Use:** Present comparable plans without heavy card chrome.

**CSS:** `border-left: 1px solid #ffffff; padding: 0px 30px; display: grid; gap: 40px; color: #ffffff`

**Text style:** `plan-title` — Cash Sans 500 · 24px/1.2 · tracking -0.01em

**Observed:** Title and brief description share a bottom divider; a large serif price follows, then a small conversion pill. White vertical rules distinguish equal columns on the black environment.

**Transfer:** Align prices and actions across plans; do not turn the recommendation into a giant colored card.

### Value badge

**Only for:** pricing comparisons

**Use:** Flag a recommended plan.

**CSS:** `background: #1f1f1f; color: #ffffff; border-radius: 5px; padding: 5px 10px`

**Text style:** `eyebrow` — Cash Sans Mono 500 · 14px/1.5 · tracking 0.1em · uppercase

**Observed:** Small uppercase mono label sits inline to the right of the plan title.

## Imagery and graphics

### Macro product theatre

**Use:** Primary opening image with monumental lettering.

**Observed:** Extreme close-up of a silver and black device sweeps diagonally across electric blue. Soft reflections and a thin iridescent edge bring material realism. The object extends outside the scene, and a white rounded word sculpture occupies its center.

**Transfer:** Photograph or render one defining product detail at macro scale. For software, use a dramatically enlarged real interface detail with a tactile device edge, not a generic laptop mockup.

**Build:** Create a blue full-bleed layer, then a cover-fitted product photo. Overlay original white SVG lettering within a 760×420px viewBox: thick vertical capsules, circular joins and narrow negative-space counters. Center the artwork at about half the stage width; keep its contours bold enough to read over reflections. Without custom lettering, outline a condensed heavy word into SVG and round its terminal shapes.

### Interface over lived texture

**Use:** Large capability demonstration beside an accordion.

**Observed:** A crisp white interface panel floats in the upper part of an enormous photographic field. The photograph is softly focused, warm and grainy, with a green work surface and a pale cup; the sharp interface is the focal plane.

**Transfer:** Use a genuine workflow panel over an environmental detail related to the user's work. Keep the photo blurred and subdued so its colors do not compete with legible UI.

### Isolated product plates

**Use:** Horizontal browsing carousel.

**Observed:** Product pictures sit on warm off-white rectangular backings, around 440×540px, with a linked product label. The sequence continues beyond the right edge.

**Transfer:** Use consistent lighting, framing and scale across the selection. For intangible products, use equivalent interface or workflow plates rather than unrelated stock images.

### Audience and immersion media

**Use:** Proof panels and a full-width capability chapter.

**Observed:** The dark environment contains image-led audience panels, an expanded 700×540px panel beside narrow 213px panels, and a later 1440×900px video scene. White proof figures and short copy accompany the media.

**Transfer:** Use authentic user environments and product-in-use footage. Retain one expanded proof panel and narrow adjacent previews rather than a generic equal-card testimonial grid.

### Closing photographic poster

**Use:** Concentrated conversion composition in the dark environment.

**Observed:** A 480×480px square image shows hands using a payment device at a table, darkened heavily under the headline. Broad rounded corners make it a compact poster with generous black space around it.

**Transfer:** Use hands completing the product's key task in a believable working setting. If photography is unavailable, use an original tightly framed workflow scene and preserve the dark overlay and square silhouette.

**Build:** Create a 480px square with about 60px corner radius and overflow hidden. Place a cover-fitted task photograph behind a black overlay near 70% opacity, adjusting for legibility. Center a two-line white closing-display headline and a row of two 44px actions on top.

### Icons

**Observed:** Compact monochrome utility symbols: search, cart, plus/minus, globe and social marks. Navigation marks are roughly 21–24px; small social symbols are 20px. Outline symbols use 1–2px strokes, with solid glyphs where appropriate.

**Transfer:** Use clean black or white utility symbols and preserve their small scale; do not introduce colorful feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Product theatre opening

**Observed:** The first 900px contains a 72px white Global navigation, then an 820px-tall Electric stage inset 8px on each side. Back to front: saturated blue, oversized metallic product close-up extending past the stage edges, a centered white word sculpture 760×420px, and the Hero action dock near the bottom. The word sculpture spans slightly over half the viewport width and about half the stage height; it is a tall, rounded, condensed graphic rather than a serif paragraph. The dock includes hero-support text, thumbnail and two actions. The headline artwork, main object, benefit and actions are all visible before the fold; ordinary explanatory sections begin below it.

**Transfer:** For a new product, make its defining visual detail the enormous backdrop and a short original word the central white sculpture. Use heading for supporting editorial promises and hero-support for the dock; do not imitate the sculpture with the section serif. A focused product page can open with one product detail instead of a portfolio scene, preserving the stage, lettering and dock relationship.

**Avoid:** Do not replace the composition with a left-aligned SaaS headline beside a small floating dashboard, or put a large text paragraph over the central word.

**Text style:** `hero-support` — Cash Sans 400 · 20px/1.2 · tracking -0.01em

### Editorial section stack

**Observed:** A gray eyebrow leads a 40px serif promise by 20px. A concise 16px paragraph follows, then Underlined text link after a larger 40px separation. The block is left aligned within the 1320px container, generally near 548px wide.

**Transfer:** Use a short category label, one outcome-focused sentence fragment and one practical explanation. Switch text polarity with the environment.

**Text style:** `heading` — Exact Block 400 · 40px/1.125 · tracking -0.02em

### Browsable product runway

**Observed:** An Editorial section stack sits above a horizontally scrolling line of Porcelain product stage tiles, with 20px gaps and small previous/next controls. Large media does more work than long descriptions.

**Transfer:** Use this for a small set of related products or workflow options. Let partial next content signal horizontal continuation.

### Capability sidebar and environment

**Observed:** A 440px text sidebar with a serif heading and Capability accordion sits next to an approximately 830px-wide photographic demonstration. The visual reaches the right edge and is substantially taller than its floating UI panel.

**Transfer:** Use one clear active feature and sync the demonstration to it. Keep environmental media larger than the text stack.

### Expanding proof panels

**Observed:** On Dark environment, a mono label and serif heading precede image-led panels with 20px gutters. The active panel expands to 700px while adjacent panels are near 213px wide; a 56px statistic, short explanation and inverse text link occupy its lower region.

**Transfer:** Use relevant audiences or distinct outcomes and verified proof. The expandable composition can be repositioned wherever proof strengthens the story.

**Text style:** `statistic` — Cash Sans 500 · 56px/1 · tracking -0.03em

### Ruled comparison

**Observed:** A heading and support line introduce three Ruled plan column components after 120px separation. Serif 56px prices contrast with 24px sans plan titles; a Value badge marks one option without a brighter card background.

**Transfer:** Compare genuinely meaningful options with aligned information rather than an exhaustive feature checklist.

**Text style:** `price` — Exact Block 500 · 56px/1 · tracking -0.03em

### Intimate closing poster

**Observed:** A Closing photographic poster sits alone in a broad black section with 160px vertical padding. A centered 72px serif promise overlays the square image and paired actions sit below it; the surrounding black space gives the small image unusual prominence.

**Transfer:** End the principal sales story with a concise invitation and a task-focused photograph. Preserve the strong scale contrast between the quiet square and the spacious environment.

**Text style:** `closing-display` — Exact Block 400 · 72px/1 · tracking -0.04em

### Service ending

**Observed:** The black environment continues through a centered single-field update form, a left-aligned disclosure column near 620px wide, and the multi-column footer. Below the navigation comes a full-width service notice, a locale/social row bounded by faint rules, then muted copyright left and a right-aligned stack of policy links. Footer content uses 60px outer margins and 60px vertical padding.

**Transfer:** Let the ending become useful and detailed without changing theme. Include only disclosures relevant to the new product, keep locale and social controls on one ruled row, and separate policies from the main product navigation.

## Page flow

**Storyline:** Spectacle → tangible product choice → working demonstration → audience proof → deeper capability → commitment options → concentrated invitation → service ending.

### Broad marketing landing page that makes a multi-part product feel like one practical system

1. **Promise** — A macro product stage with oversized lettering and a small benefit/action dock.
2. **Product choice** — A light editorial introduction and horizontally browsable product plates.
3. **Capability demonstration** — A feature accordion beside an inhabited photographic interface scene.
4. **Social proof** — The palette turns black for expanded audience panels and a large numeric proof treatment.
5. **Capability depth** — An immersive full-width video chapter with a short explanatory overlay.
6. **Commitment options** — Three spare ruled comparison columns on the same black field.
7. **Closing call** — A small rounded photographic poster with a large serif invitation and paired actions.
8. **Ongoing relationship and service** — Updates form, relevant disclosures, detailed navigation and locale/policy utilities complete the black ending.

**Transfer:** Adapt the number and order of explanatory chapters to the product. Preserve the visual devices—monumental word art, inhabited demonstration and concentrated closing poster—without treating this sequence as a fixed template.

## Writing

Direct, businesslike and encouraging, with an editorial warmth rather than corporate grandeur. Big promises describe smoother work; supporting copy explains concrete functionality and removes practical objections.

**Do not copy:** Do not reuse Square or Block names, logos, custom wordmark paths, product names, customer statistics, pricing, financial claims, testimonials or legal language. Source examples illustrate cadence only.

- **Addressing the reader:** Speak to the reader as you and your. Name the product when needed; keep the user's work and outcomes as the subject.
- **Rhythm:** Headlines are usually 4–9 words, often an imperative or a short outcome phrase. Support is one or two straightforward sentences; actions are brief verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Section promise | A concrete outcome expressed in ordinary words, with a small rhythmic twist. | 4–9 words | “Smooth checkout, every time”<br>“See your whole business click into place” |
| Supporting line | Explain the benefit through the product's actual capability; remove a practical barrier. | 12–25 words | “No hidden fees or locked-in contracts. Cancel or switch plans anytime.”<br>“Ask [Brand] AI anything about your business to get immediate insights.” |
| Primary action | Plain verb plus a concrete destination or next step. | 2–6 words | “Get started”<br>“Try free for 30 days” |
| Closing promise | Short, encouraging invitation centered on the reader's momentum. | 4–6 words | “Make your next move” |

**Words and phrasing to use:** your; smooth; works; grow; manage; connect; easy to use; get started

**Avoid:** revolutionary ecosystem; disruptive synergy; unparalleled excellence; unlock limitless possibilities

**Rules:**

- Tie each short promise to a specific demonstration or practical explanation.
- Prefer active verbs and everyday work language over abstract platform jargon.
- Answer commitment concerns in plain sentences near the conversion options.
- Keep category labels functional and short; let the headline carry personality.

## Do's and Don'ts

### Do

- Keep default section headlines at 40px/45px with -0.02em tracking.
- Give mono category markers 14px type and 0.1em tracking.
- Preserve the 72px white navigation band above the opening spectacle.
- Use 20px gutters for media runs and 60px desktop margins for aligned content.
- Pair blue and white 44px actions rather than making every link a filled button.
- Carry black through proof, conversion and the service ending as one environment.
- Use 1px rules to organize accordion and plan content.
- Keep the closing photograph near 480px square so the surrounding black remains meaningful.

### Don't

- Do not make all headlines geometric sans; the 40px serif is the main editorial voice.
- Do not use the 56px sans proof recipe for price figures; those use the serif.
- Do not round every content tile: the 20px hero and pill actions contrast with rectangular product stages.
- Do not apply colored shadows to marketing cards; separation comes from backing, photography and rules.
- Do not spread the electric blue field across ordinary explanatory sections.
- Do not increase body text into a 24px manifesto; the supporting voice is 16px/24px.
- Do not turn the footer gray or white after the black closing environment.
- Do not use the 14px uppercase mono recipe for normal buttons or paragraph copy.

## Motion and responsive

### Motion

**Observed:**

- Declared: text-link underline background-size .3s cubic-bezier(0, 0, .2, 1); media opacity .6s with the same curve.
- Declared: audience panel flex transitions .4s and .6s cubic-bezier(0, 0, .2, 1); compact scrolling navigation transform 0.2s cubic-bezier(0.4, 0, 1, 1).
- Declared: opening blue media layer opacity 1.2s. No matched CSS animation was established for the main marketing elements.

**Transfer:**

- Use expansion to emphasize the active proof panel while adjacent media remains narrow.
- Keep the compact conversion strip distinct from the full opening navigation; use the declared transform transition when exchanging them.

**Unknown:**

- Exact video choreography, scroll thresholds and the full word-art animation sequence are unspecified.

### Responsive

**Observed:**

- The desktop composition uses 12-column section grids and a 1320px maximum content width.
- Declared stylesheet widths include 480px, 768px, 1024px and 1280px among many component-specific breakpoints.

**Transfer:**

- On narrow screens, keep the macro stage and large white word-art relationship, reducing the artwork as a single SVG rather than wrapping individual letters.
- Stack the dock's benefit and actions when needed; keep actions readable and inside the stage.
- Place accordion text before its demonstration and stack comparison columns while retaining their fine-rule language. Preserve horizontal browsing for product plates.

**Unknown:**

- Mobile layouts, alternate type sizes and which breakpoint controls each major section are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
