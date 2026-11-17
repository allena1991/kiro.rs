# Krea — sculpted creative workspaces

## Overview

A bright, gallery-like style for powerful creative software, with oversized Swiss grotesk type and tactile, pearlescent ribbon artwork. Black cinematic demonstrations interrupt white and pale-gray editorial space, while colorful product outputs carry most of the visual energy. The feeling is capable and accessible rather than technical or corporate; spacious storytelling gives way to dense, practical buying information.

### Essentials

- An oversized two-line name behaves like a graphic object: regular-weight Suisse Intl at 109.4px, 0.98 line height and -0.065em tracking, balanced by a narrow 360px support column rather than a centered slogan.
- The opening sells through a workspace, not an abstract promise alone: a 1.8:1 text split above a nearly full-width 1344px framed product view, with 48px side padding and a 48px separation before the view.
- Pearlescent ribbon sculpture is a signature device: looping blue, cyan and blush material on a pale grainy background, partly cut off by the frame. Include an original ribbon treatment on every landing page; a shaded SVG loop with grain is the minimum equivalent.
- The interface around the art stays monochrome: white canvas, black text and actions, #f5f5f5 grouping bands, with blue #006eff reserved for tiny status or discount markers and focus. Large saturated areas belong to media, not ordinary text sections.
- Actions are compact solid pills, not oversized panels: the default black action uses 14px/20px medium text, 12px 24px padding and a 44px height; the light inversion sits over dark media.
- Proof is staged at two radically different scales: enormous cinematic image demonstrations with 72px overlay type, and small reusable cards with 16px corners and 24px internal padding. Preserve both the immersive and the practical register.
- The ending is a real directory: four columns of 14px links, 14px row spacing and 48px between groups, followed by a small AI-assistant link cluster and a separate copyright/social baseline on a pale-gray band.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Utility blue | `#006eff` | `--color-blue` | accent, action, border | Small new/discount markers and action focus; not the main conversion color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas and raised cards; inverse text and actions over dark demonstrations. |
| Near white | `#fafafa` | `--color-soft-canvas` | background, surface | Inset capability bands and soft demonstration surrounds. |
| Soft gray | `#f5f5f5` | `--color-band` | surface, background | Proof cards, contact bands and the light directory footer. |
| Accordion edge | `#e6e6e6` | `--color-faq-edge` | border | Slightly lighter outlines around question rows. |
| Panel edge | `#e5e5e5` | `--color-edge` | border | Fine outlines on product frames and light cards. |
| Label gray | `#737373` | `--color-muted` | text | Eyebrows, footer links and secondary descriptions. |
| Supporting charcoal | `#525252` | `--color-support` | text | Introductory support paragraphs, especially beside the opening title. |
| Paragraph charcoal | `#404040` | `--color-body` | text | Standard descriptive paragraphs on white. |
| Dark charcoal | `#171717` | `--color-dark-band` | background, text | Testimonial band; plan titles on light cards. |
| Black | `#000000` | `--color-ink` | text, action, background | Primary text, default conversion pills and immersive demonstration backing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| tool directories and dark demonstrations | Workspace charcoal | `#101010` | `--color-dark-canvas` | background | Dark tool-discovery canvas and some cinematic backing. |
| standalone pricing pages | Deep pricing charcoal | `#0a0a0a` | `--color-deep-canvas` | background | Dedicated dark pricing canvas. |
| solution-page inset calls to action | Cloud blue | `#e2ebfc` | `--color-blue-wash` | surface | Visible pale-blue corner wash from rgba(170,200,255,0.3) over near white. |
| solution-page inset calls to action | Cloud blush | `#fbe9f0` | `--color-pink-wash` | surface | Visible blush corner wash from rgba(255,190,215,0.28) over near white. |

## Typography

- **Suisse Intl** — All marketing headlines, paragraphs, labels and actions. Neutral Swiss grotesk with a high x-height, straightforward lowercase and very tightly fitted display text. If unavailable, use **Inter**. Use weights 400–600; retain the unusually tight display tracking and check line breaks. Font stack: "Suisse Intl", "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Suisse Intl | 400 | 109.4px | 0.98 | -0.065em | size clamp(64px, 7.6vw, 116px) | Default landing-page opening name, normally split into two lines. |
| cinematic-heading | Suisse Intl | 500 | 72px | 1.08 | -0.025em | fixed | Large sentence over a full-width demonstration. |
| heading-lg | Suisse Intl | 500 | 60px | 1.05 | -0.025em | fixed | Major editorial promise chapters. |
| heading | Suisse Intl | 500 | 48px | 1.25 | -0.025em | fixed | Section leads for proof, capabilities and contact. |
| closing-heading | Suisse Intl | 500 | 48px | 1.1 | -0.0267em | fixed | Centered final invitation. |
| feature-heading | Suisse Intl | 500 | 40px | 1.15 | -0.025em | fixed | Split capability and trust chapters. |
| quotation | Suisse Intl | 500 | 36px | 1.375 | -0.025em | fixed | Long customer quotation on a dark band. |
| faq-heading | Suisse Intl | 500 | 32px | 1.313 | -0.02em | fixed | Question-section lead, using a subtle charcoal-to-black text fill. |
| card-heading | Suisse Intl | 500 | 24px | 1.25 | -0.025em | fixed | Proof card titles. |
| intro | Suisse Intl | 400 | 18px | 1.625 | normal | fixed | Support beside the opening and major chapter headings. |
| question | Suisse Intl | 500 | 18px | 1.5 | -0.01em | fixed | Default narrower question rows. |
| body | Suisse Intl | 400 | 16px | 1.625 | normal | fixed | Feature explanations; medium black phrases within paragraphs establish a second reading speed. |
| navigation | Suisse Intl | 400 | 15px | 1.5 | 0.01em | fixed | Horizontal marketing navigation. |
| small-body | Suisse Intl | 400 | 14px | 1.625 | normal | fixed | Proof-card descriptions and compact capability summaries. |
| action | Suisse Intl | 500 | 14px | 1.43 | normal | fixed | Default conversion pills and text links. |
| small | Suisse Intl | 400 | 14px | 1.43 | normal | fixed | Footer links and compact feature lists. |
| small-heading | Suisse Intl | 450 | 14px | 1.43 | normal | fixed | Footer group titles and navigation registration action. |
| eyebrow | Suisse Intl | 500 | 12px | 1.333 | 0.1em, uppercase | fixed | Chapter category above a feature heading. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| integration launch pages | proof-statement | Suisse Intl | 600 | 72px | 1.05 | -0.025em | fixed | Three large left-aligned statements introducing the buying section. |
| industry solution pages | solution-display | Suisse Intl | 600 | 60px | 1.04 | -0.04em | size clamp(36px, 4.8vw, 60px) | Centered two-line promise over a scenic hero. |
| standalone pricing add-on cards | metal-number | Suisse Intl | 700 | 60px | 1 | -0.05em | fixed | Silver-gradient quantity numerals above miniature hardware-like credit illustrations. |
| interactive tool demonstrations | immersive-tool-heading | Suisse Intl | 450 | 60px | 1 | -0.025em | fixed | Centered heading above a glowing prompt field. |
| integration launch pages | integration-heading | Suisse Intl | 500 | 56px | 1.111 | -0.02em | fixed | Alternating image/text feature chapters. |
| integration launch pages | integration-display | Suisse Intl | 500 | 50px | 0.96 | -0.02em | fixed | Compact centered title above the floating workspace composition. |
| industry solution pages | solution-heading | Suisse Intl | 500 | 44px | 1.08 | -0.016em | fixed | Capability chapters and the transition into pricing. |
| standalone pricing pages | pricing-title | Suisse Intl | 500 | 32px | 1 | normal | fixed | Direct left-aligned opening heading, subordinate to the plan grid. |
| embedded pricing sections | plan-title | Suisse Intl | 600 | 24px | 1.333 | normal | fixed | Plan names within light pricing cards. |
| integration and solution pages | wide-question | Suisse Intl | 500 | 24px | 1.333 | -0.02em | fixed | Questions spanning the wider page container. |
| tool-discovery directories | directory-heading | Suisse Intl | 450 | 24px | 1.333 | normal | fixed | Compact leads beneath media and above carousels. |
| embedded pricing sections | plan-action | Suisse Intl | 600 | 13px | 1 | normal | fixed | Full-width, softly rectangular plan conversion buttons. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Default headlines use weight 500, not bold; only the opening name is regular at 400. The tightest tracking belongs to the largest opening name.
- Body remains untracked; section headings typically use -0.025em and uppercase eyebrows open to 0.1em.
- Keep separate headline registers for scenic solution heroes, integration compositions and utilitarian buying pages rather than forcing the opening display recipe onto all three.

## Layout

**Density:** Airy editorial chapters around large media, with compact controls and denser buying and directory sections.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card-title support gaps and compact control spacing. |
| 12px | Navigation-link padding and close label relationships. |
| 14px | Footer link-row spacing. |
| 16px | Eyebrow-to-heading and paragraph-to-paragraph separation. |
| 24px | Card padding, carousel gap and related actions. |
| 28px | Feature paragraph to action. |
| 32px | Cinematic heading to action and footer baseline grouping. |
| 40px | Section heading to proof cards and inset black-panel padding. |
| 48px | Opening text to product frame; separation between directory groups. |
| 64px | Split feature-column gap and standard chapter vertical padding. |
| 80px | Proof-section vertical padding and final invitation top space. |
| 96px | Major chapter and contact-band vertical padding. |
| 112px | Footer top padding and closing-section bottom padding. |
| 128px | Wide FAQ top padding on integration and solution pages. |
| 176px | Wide FAQ bottom padding. |

### Containers and grids

- **Editorial container**: max width 1280px · side padding 48px. Default centered chapter shell, producing 1184px of content at desktop.
- **Opening container**: max width 1440px · gap 48px · side padding 48px. Opening text in a 1.8fr 1fr split; product frame spans both columns underneath.
- **Split feature**: 2 columns · gap 64px. Equal image and text columns, vertically centered. Alternate their sides by chapter.
- **Wide marketing container**: max width 1536px · side padding 64px. Navigation, directory footer and broad integration layouts.
- **Proof carousel**: gap 24px. 360px-wide cards in a horizontal scroll-snap row, with a next card partly visible.
- **FAQ container**: max width 896px · side padding 24px. Default narrow centered question stack with left-aligned heading.
- **Embedded pricing grid** (only for embedded pricing sections): 3 columns · gap 20px. Three equal cards followed by a team-plan row, sharing aligned bottom actions.
- **Solution container** (only for industry solution pages): max width 1180px · side padding 20px. Capability, workflow and inset call-to-action content.
- **Tool directory shell** (only for tool-discovery directories): side padding 48px. A 256px persistent sidebar sits beside the media-rich charcoal content area.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Conversion pills | 9999px (pill) |
|  | Product frames and proof cards | 16px |
|  | Question shells | 20px |
|  | Large inset trust panels | 24px |
| embedded pricing sections | Pricing actions | 8px |
| industry solution pages | Solution media and inset calls | 14px |
| solution-page article carousels | Editorial image cards | 32px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Raised demonstration | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | White interactive product panels float softly above near-white surrounds. |
| tool-discovery directories | Dark media separation | `0px 0px 32px rgba(0,0,0,0.85)` | Separates dark media stages and carousel cards from the charcoal canvas. |

### Surfaces

#### Gallery canvas · level 0

**Use:** Default marketing-page background.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Most editorial chapters sit directly on white without card shells.

**Transfer:** Let typography and media proportions organize ordinary sections.

#### Soft grouping band · level 0

**Use:** Contact region, proof cards and directory footer.

**CSS:** `background: #f5f5f5`

**Observed:** A low-contrast change in value groups content without decorative outlines.

**Transfer:** Use as a full-width band or as a restrained card material.

#### Raised product panel · level 1

**Use:** Contained interactive capability demonstration.

**CSS:** `background: #ffffff; border: 1px solid #e5e5e5; border-radius: 16px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Observed:** White controls sit inside a larger near-white rounded backing, so the frame is visible without a heavy shadow.

**Transfer:** Show one understandable interaction rather than an entire administrative interface.

#### Black inset panel · level 1

**Use:** A concentrated trust or assurance message.

**CSS:** `background: #000000; color: #ffffff; border-radius: 24px; padding: 40px`

**Observed:** An emblem and explanation occupy the left; a white action sits to the right.

**Transfer:** Use for one substantiated assurance, keeping the surrounding page white.

#### Testimonial band · level 0

**Use:** A full-width pause for customer testimony.

**CSS:** `background: #171717; color: #ffffff; padding: 96px 0px`

**Observed:** A long, left-aligned quotation takes most of a 1024px text measure; attribution and inverted action sit beneath.

**Transfer:** Give the quotation its own reading space rather than turning it into a tiny rotating card.

#### Cloud corner panel · level 1

**Only for:** solution-page inset calls to action

**Use:** A light atmospheric invitation between chapters.

**CSS:** `background-color: #fafafa; background-image: radial-gradient(60% 90% at 88% 0%, rgba(170, 200, 255, 0.3), rgba(0, 0, 0, 0) 60%), radial-gradient(55% 85% at 8% 100%, rgba(255, 190, 215, 0.28), rgba(0, 0, 0, 0) 60%); border-radius: 14px; padding: 96px 24px`

**Observed:** Blue is concentrated at the top right and blush at the bottom left; the center remains almost white.

**Transfer:** Keep the colors as corner atmosphere, not a vivid all-over gradient.

#### Dark pricing canvas · level 0

**Only for:** standalone pricing pages

**Use:** Dense buying and comparison information.

**CSS:** `background: #0a0a0a; color: #ffffff`

**Observed:** Warm blurred color appears behind the opening plan row; translucent dark plan headers and a blue recommended-plan crest sit in front.

**Transfer:** Contain decorative color near the opening; let long comparison tables revert to nearly black.

## Components

### Marketing navigation

**Use:** Global page navigation.

**CSS:** `height: 79px; padding: 16px 64px; background: rgba(255,255,255,0.8); backdrop-filter: blur(24px); border-bottom: 0.5px solid rgba(0,0,0,0.15)`

**Text style:** `navigation` — Suisse Intl 400 · 15px/1.5 · tracking 0.01em

**Observed:** Small standalone symbol at left, compact centered link group, registration and login pills at right. Dark demonstrations use an inverted header treatment.

**Transfer:** Keep the central group terse and let the product mark remain small.

### Primary button

**Use:** Default page conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #000000; color: #ffffff; border-radius: 9999px; padding: 12px 24px; height: 44px`

**Text style:** `action` — Suisse Intl 500 · 14px/1.43

**Observed:** Usually text only; white inversion is used over black and cinematic media. The final centered invitation increases the pill to 56px high.

**States:** Declared: hover background-color #262626; focus-visible outline-width 2px with outline-offset 4px and blue outline-color.

### Registration pill

**Use:** Low-emphasis registration in the header.

**CSS:** `background: #ffffff; color: #000000; border: 0.5px solid rgba(0,0,0,0.2); border-radius: 9999px; height: 36px; padding: 8px 16px`

**Text style:** `small-heading` — Suisse Intl 450 · 14px/1.43

**Observed:** Paired with a dark login pill rather than another oversized conversion button.

**States:** Declared: hover background-color #f5f5f5; focus-visible automatic blue outline and gray border.

### Proof card

**Use:** Customer or use-case story in the horizontal proof row.

**CSS:** `position: relative; background: #f5f5f5; border-radius: 16px; width: 360px; min-height: 440px; overflow: hidden`

**Text style:** `card-heading` — Suisse Intl 500 · 24px/1.25 · tracking -0.025em

**Observed:** Inner content uses 24px padding. Small identity marks sit at the top; pearlescent ribbon art bleeds from the upper-right corner; title and short paragraph anchor the bottom. Circular arrows sit below the row.

**Transfer:** Pair a real outcome title with a short process description; preserve the art-to-text imbalance.

### Question row

**Use:** Default objection-handling accordion shell.

**CSS:** `border: 1px solid #e6e6e6; border-radius: 20px; padding: 8px 24px`

**Text style:** `question` — Suisse Intl 500 · 18px/1.5 · tracking -0.01em

**Observed:** A full-width inner button uses 16px vertical padding with a plus at the far right. Rows have 10px gaps. Wider solution and integration variants use the wide-question recipe instead.

**States:** Declared: hover question color #737373; focus-visible blue border and automatic blue outline on the inner button.

### Footer directory

**Use:** The full site ending.

**CSS:** `background: #f5f5f5; padding: 112px 64px 40px; color: #737373`

**Text style:** `small` — Suisse Intl 400 · 14px/1.43

**Observed:** Four equal columns; black small-heading group titles, 16px title-to-list gaps, 14px link-row gaps, 48px between groups. The lower area includes a compact assistant-link icon cluster, then copyright left and social links right. Dark variants use black backing and white links.

**Transfer:** Keep the four-column directory structure but adjust the number of links to the product's real information architecture.

### Contact form panel

**Use:** Sales-led conversion chapter.

**CSS:** `background: #ffffff; border-radius: 16px; overflow: hidden`

**Observed:** A 560px white form sits beside explanatory copy on a soft-gray band. First and last name share a row; work email and industry share a row; company, size and message span the panel. Inputs are pale-gray rectangles; submit is a small centered black pill.

**Transfer:** Use only necessary qualification fields and provide alternate support or self-serve paths in the text column.

### Navigation link

**Use:** Individual top-level page destinations.

**CSS:** `color: #000000; padding: 12px; border-radius: 8px`

**Text style:** `navigation` — Suisse Intl 400 · 15px/1.5 · tracking 0.01em

**Observed:** Dropdown labels add a tiny downward chevron; ordinary links remain unadorned.

**States:** Declared: hover background-color rgba(0,0,0,0.05); focus-visible automatic blue outline.

### Plan card

**Only for:** embedded pricing sections

**Use:** Compact self-service buying options.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid #e5e5e5; border-radius: 16px; padding: 24px; min-height: 520px`

**Text style:** `plan-title` — Suisse Intl 600 · 24px/1.333

**Observed:** Plan name, short explanation, price and allowance precede checked features; the action aligns to the bottom. The custom team tier inverts to black and uses a white action.

### Plan action

**Only for:** embedded pricing sections

**Use:** Full-width conversion inside plan cards.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #000000; color: #ffffff; border-radius: 8px; padding: 12px 20px; height: 40px`

**Text style:** `plan-action` — Suisse Intl 600 · 13px/1

**Observed:** A deliberately squarer alternative to the editorial pill; the custom dark tier reverses to white.

**States:** Declared: hover background-color #171717; focus-visible automatic blue outline.

## Imagery and graphics

### Pearlescent ribbon sculpture

**Use:** Signature artwork in the opening and proof-card family.

**Observed:** Thick folded loops with rounded tubular edges, chalky white highlights, cyan and blue shadowed faces and pale blush turns. Fine grain softens the rendered material. The hero uses enlarged partial loops behind black type; proof cards repeat smaller upper-right fragments on pale gray.

**Transfer:** Create an original looping form rather than a logo-shaped ornament. Keep enough blank space for black type. A shaded SVG ribbon with grain is the minimum acceptable version.

**Build:** Draw a broad looping cubic SVG path that bends through an S and returns through a loose loop. Layer a wide pale-gray stroke beneath a narrower white-to-cyan-to-blue-to-blush gradient stroke, both with round joins. Add a narrow white highlight offset along the upper edge, and a soft dark-blue shadow on the underside. Apply low-opacity fractal-noise grain with an SVG filter, clip the loop at the top or right edge, and fade the backing into white through the lower third. Use a 360px by 280px art field for a proof card; enlarge and partially conceal it behind the opening title.

### Product workspace frames

**Use:** Main opening object and recurring capability demonstrations.

**Observed:** Large, sharp application views with visible content and legible broad controls. The main frame is nearly edge-to-edge beneath the opening text, with a 1px pale border and 16px upper corners; smaller panels sit in pale-gray surrounds. Color belongs to the work shown inside the interface.

**Transfer:** Show a meaningful task and its result using the new product's real UI. If no complete interface exists, compose a credible focused workflow view with one input, one operation and one tangible output.

### Cinematic output stage

**Use:** Immersive demonstration that interrupts the white editorial rhythm.

**Observed:** Warm studio-lit product imagery fills a 1440px-wide, 760px-tall stage. A black 40% scrim makes the centered white sentence readable. A translucent tab rail and pause control float above; an inverted pill and short closing caption sit below the headline.

**Transfer:** Use a finished result with recognizable material and lighting, not a stock-office scene. For nonvisual products, stage a high-quality result document or interactive artifact at a comparable scale.

### Scenic solution hero

**Only for:** industry solution pages

**Use:** Outcome-first opening.

**Observed:** A 1320px by 743px scenic film with 14px corners fills most of the first screen. The visible scene is an organically curved planted-roof building in misty trees under warm dawn light. White promise and actions sit in its lower center over a bottom darkening gradient.

**Transfer:** Choose an industry-specific aspirational result with real depth and soft atmospheric light, preserving the lower-center readable area.

### Floating integration workspace

**Only for:** integration launch pages

**Use:** Dark opening and repeated download stage.

**Observed:** A central illustrated subject rises from the bottom edge beneath a compact centered headline. Dim editing panels float at left; a brighter narrow tool panel anchors the right. Fine blue selection edges and small tool labels make the scene feel actively editable.

**Transfer:** Use a central product artifact with two or three authentic cropped tool panels. Keep peripheral panels dim so they do not compete with the title or the main subject.

### Material study sequence

**Only for:** integration capability chapters

**Use:** Alternating image-and-text sections.

**Observed:** Red ribbon and blue ring forms on deep navy, warm architectural backgrounds, and wireframe-to-shaded progressions. Images are roughly 568px by 317px with rounded corners and occupy about half the chapter; surrounding bands alternate white and near white.

**Transfer:** Show the same original object through meaningful stages or consistent related outputs, with a tightly limited material palette.

### Dark particle prompt stage

**Only for:** interactive tool demonstrations

**Use:** Immersive product-use moment in a tool directory.

**Observed:** An almost-black star field swirls around a broad rounded prompt box. Small white and icy-blue particles concentrate around a cool glowing rim, while the heading and prompt remain clear in the center.

**Transfer:** Carry the luminous working-field treatment to an actual interaction, not a generic background decoration.

**Build:** On black, distribute tiny white and pale-blue dots with SVG circles at varying low alpha. Stretch some dots into short tangential strokes around an elliptical orbit below the heading. Layer several thin rounded-rectangle strokes around the prompt, blur the outer strokes and leave the inner border sharp; mask particles out of the text and input interiors.

### Metal credit hardware

**Only for:** standalone pricing add-ons

**Use:** A distinctive graphic for consumable purchase packs.

**Observed:** Five dark 24px-radius cards carry large silver-gradient quantities and miniature chip-like objects with layered bevels, metallic pins and green/cyan illuminated edges.

**Transfer:** Use the hardware metaphor only for metered capacity or credit purchases; ordinary feature cards remain flat.

**Build:** Construct a small nested stack of rounded squares: dark outer plate, silver beveled edge, charcoal inner face and a fine inset light line. Repeat small metallic pin rectangles along all four sides. Add a low-opacity green-to-cyan blurred rim behind the chip and silver-gradient quantity type above it.

### Icons

**Observed:** Mostly small SVG outline icons with rounded caps: 16px at 2px stroke for controls and checks; 24px at 1.5px stroke for question plus signs. Solid identity and social glyphs are kept to compact 16–22px marks.

**Transfer:** Use a consistent rounded-stroke family for actions and disclosures; reserve filled symbols for identities and platforms.

## Section recipes

How recurring sections are built.

### First screen: Sculptural workspace opening

**Observed:** A translucent Marketing navigation sits over a white-to-pale-gray art field. Pearlescent ribbon sculpture crosses behind the left-hand title and is clipped by the top edge. Under the navigation, 148px top padding and 48px side padding establish the intro. The display title occupies about three fifths of a 1.8fr 1fr split and breaks into two monumental lines; the right column has a 360px intro and black Primary button. A 48px gap leads to the wide Product workspace frame. Within the first 900px, the entire title, support and action are visible and the large workspace fills the lower half; its bottom and later social proof fall below the fold.

**Transfer:** Replace the name with a short two-line product promise or product/category pair, and show a real working result beneath it. Preserve the ribbon signature even without finished media by using the shaded SVG construction and a focused workflow panel. Solution pages instead open with Scenic solution hero; integration launches use Floating integration workspace; buying pages lead directly into plans.

**Avoid:** Do not center the default opening into a conventional slogan-and-three-cards hero, or shrink the workspace into a thumbnail beside the title.

**Text style:** `display` — Suisse Intl 400 · 109.4px/0.98 · tracking -0.065em

### Editorial heading pair

**Observed:** A small category precedes a heading-lg lead on the left; intro copy and Primary button sit in a separate right column. The chapter uses the Editorial container, 96px vertical padding and 40px before the demonstration.

**Transfer:** Use the heading to promise an outcome and the separate support column to explain the mechanism.

**Text style:** `heading-lg` — Suisse Intl 500 · 60px/1.05 · tracking -0.025em

### Capability split

**Observed:** Split feature places media and a feature-heading with eyebrow, explanatory paragraph, short medium-weight proof phrase and Primary button in opposing columns. Use 64px vertical chapter padding and alternate media position.

**Transfer:** Make each chapter explain one useful operation, keeping the explanatory hierarchy intact.

**Text style:** `feature-heading` — Suisse Intl 500 · 40px/1.15 · tracking -0.025em

### Immersive demonstration

**Observed:** Cinematic output stage spans the page, with the centered cinematic-heading occupying up to 1024px, tab rail above and white action below. A short bottom caption closes the scene.

**Transfer:** Demonstrate an outcome at immersive scale and let the overlay read as a concrete instruction or desired result.

**Text style:** `cinematic-heading` — Suisse Intl 500 · 72px/1.08 · tracking -0.025em

### Proof carousel

**Observed:** A heading lead sits 40px above Proof cards in a 24px-gap scroll-snap rail. The rail begins on the editorial content line but continues beyond the right edge. Two pale circular arrows sit beneath on the right.

**Transfer:** Use a handful of distinct outcome stories; give each enough text to explain the work, not just a logo.

**Text style:** `heading` — Suisse Intl 500 · 48px/1.25 · tracking -0.025em

### Assurance chapters

**Observed:** Near-white rounded grouping surrounds alternating copy and Raised product panel demonstrations. A Black inset panel provides a concentrated certification or trust statement after the broader capability explanations.

**Transfer:** Explain ownership, control or reliability with a small focused interaction and one substantiated assurance rather than a wall of badges.

**Text style:** `feature-heading` — Suisse Intl 500 · 40px/1.15 · tracking -0.025em

### Testimonial pause

**Observed:** Testimonial band switches to charcoal with a 36px long quotation, wide left alignment, muted attribution and a white conversion pill. The measure is 1024px, not a narrow card.

**Transfer:** Use a specific customer account with process detail; size the section to the quotation rather than forcing equal-height tiles.

**Text style:** `quotation` — Suisse Intl 500 · 36px/1.375 · tracking -0.025em

### Sales contact chapter

**Observed:** Soft grouping band uses 96px vertical padding and a two-column grid with a 64px gap. A heading and intro explain the next step on the left, followed by alternate routes. Contact form panel fills the right.

**Transfer:** Separate sales, support and self-service paths clearly, making the form a practical next step.

**Text style:** `heading` — Suisse Intl 500 · 48px/1.25 · tracking -0.025em

### Questions and closing invitation

**Observed:** FAQ heading is left-aligned over a narrow Question row stack; rows use 10px spacing and plus controls. The final invitation returns to centered closing-heading within a 672px measure, followed by support at 19px separation and a 56px-high pill after 32px. Footer directory closes the page.

**Transfer:** Answer real adoption objections before a short final invitation. Use the directory as a separate navigational ending, not as another sales banner.

**Text style:** `closing-heading` — Suisse Intl 500 · 48px/1.1 · tracking -0.0267em

### Embedded buying chapter

**Only for:** integration and solution pages

**Observed:** A large left-aligned statement introduces pricing; integration pages use three 72px proof statements, while solutions use a 44px two-line progression statement. Centered billing controls precede a three-column Plan card row, then a team-plan row with a black custom tier.

**Transfer:** Adapt the lead to the visitor's adoption path and retain aligned bottom actions. Pricing density should be visibly tighter than the preceding editorial chapters.

**Text style:** `plan-title` — Suisse Intl 600 · 24px/1.333

### Dark comparison page

**Only for:** standalone pricing pages

**Observed:** A compact left-aligned pricing-title and billing pill introduce three translucent plan headers. Blue distinguishes the recommended plan; a warm blurred background recedes behind the row. Two team cards and metallic credit add-ons precede a detailed comparison matrix. The matrix has 1px low-alpha row rules, sticky plan information and a floating category pill. Dark question cards and a centered help invitation with scattered square result thumbnails lead into a black directory footer.

**Transfer:** Keep quick plan selection at the top and exhaustive detail lower down; use the same subdued neutrals throughout the table.

**Text style:** `pricing-title` — Suisse Intl 500 · 32px/1

### Solution ending

**Only for:** industry solution pages

**Observed:** After the wide question stack, a pale-gray inset invitation includes four overlapping 48px result thumbnails, centered title, support and black pill. A separate related-destination row uses four compact outlined 16px-radius tiles before Footer directory.

**Transfer:** Close the immediate conversion path, then offer adjacent use cases as lightweight navigation rather than reopening the main story.

### Integration bookend

**Only for:** integration launch pages

**Observed:** The black download composition returns after alternating feature chapters, now with a 72px compressed multiline headline and dim peripheral editor panels. A white Download pill anchors it. Large proof statements, light pricing, wide questions and Footer directory follow.

**Transfer:** Use the repeated dark stage as a memorable product bookend, without treating it as the literal end of the page.

### Tool discovery gallery

**Only for:** tool-discovery directories

**Observed:** A persistent 256px black sidebar accompanies a #101010 canvas with 48px content padding. A wide release image and compact caption lead to integration tiles, result carousels, the Dark particle prompt stage, model carousels and a three-column edge-to-edge image gallery. The ending is a dark Footer directory without a separate final sales invitation.

**Transfer:** Use this denser app-adjacent pattern for browsing many capabilities, not as the default new marketing-page shell.

**Text style:** `directory-heading` — Suisse Intl 450 · 24px/1.333

## Page flow

**Storyline:** Promise and working product → tangible demonstration → proof and capability chapters → adoption reassurance → buying or contact route → objections → renewed invitation and directory.

### Sales-led platform landing page

1. **Promise** — Oversized split introduction, ribbon atmosphere and wide working product frame.
2. **Social proof** — Compact trust strip and customer identities.
3. **Product demonstration** — Editorial promise pair, large workflow panel and cinematic result stage.
4. **Proof and capabilities** — Proof carousel, tabbed tools and alternating image/text chapters.
5. **Adoption reassurance** — Focused control demonstrations, assurance panel, industry use cases and large quotation.
6. **Conversion** — Split contact form and alternate self-service routes.
7. **Objection handling and ending** — Narrow question stack, centered final invitation and light four-column directory.

**Transfer:** Best default for a new full marketing or product landing page: combine aspirational visual work with practical adoption detail.

### App-adjacent tool discovery hub

1. **Announcement** — Wide release artwork with compact caption inside a sidebar shell.
2. **Capability discovery** — Integration promotion, tool tiles and result carousels.
3. **Product interaction** — Immersive prompt stage followed by model discovery.
4. **Visual proof** — Searchable masonry-like three-column output gallery.
5. **Ending** — Dark four-column directory and small assistant/social links.

**Transfer:** Use for a product with many browsable tools or outputs; retain a faster, denser scanning rhythm.

### Buying and detailed plan comparison

1. **Plan selection** — Direct heading, billing toggle and three plans, followed by team options.
2. **Expansion purchase** — Metallic add-on credit cards.
3. **Detailed comparison** — Long ruled matrix with plan and category navigation.
4. **Objection handling** — Dark question-card stack.
5. **Closing call and ending** — Help invitation among square output images, then a black directory.

**Transfer:** Prioritize actual differences and keep decorative color near the initial selection area.

### Integration launch and installation

1. **Promise** — Dark floating workspace composition with centered title and download action.
2. **Activation** — Three installation cards: download, install, open.
3. **Capability chapters** — Centered capability lead followed by alternating image/text bands.
4. **Renewed invitation** — Repeated dark download stage.
5. **Buying confidence** — Monumental proof statements and embedded pricing.
6. **Objection handling and ending** — Wide question stack, then light directory with assistant and social links.

**Transfer:** Demonstrate the integration in context, explain the few steps to use it, then address compatibility and cost.

### Industry-specific workflow adoption

1. **Outcome promise** — Scenic hero with white lower-center text and dual actions.
2. **Social proof** — Compact centered trust statement and customer-logo rail.
3. **Workflow explanation** — Tabbed source-to-result study, live-workflow chapter and reusable-process chapter.
4. **Adoption reassurance** — Four numbered practice cards and a black controls panel.
5. **Renewed invitation and editorial proof** — Soft corner-wash invitation and large image-led article cards.
6. **Buying and objections** — Progression statement, embedded pricing and wide questions.
7. **Ending** — Thumbnail invitation, related-destination tiles and pale-gray directory.

**Transfer:** Replace the domain-specific workflow with the visitor's own starting materials, review stages and concrete outputs.

## Writing

Direct, visually minded and product-literate. The language is confident without ceremonial enterprise jargon; concrete tools and workflows support short aspirational promises.

**Do not copy:** Do not reuse Krea names, logos, proprietary artwork, partner marks, model names, customer quotations, user counts, performance claims, prices or security assurances. Source examples illustrate rhythm only; replace them with truthful content and assets belonging to the new product.

- **Addressing the reader:** Speak to you and your team; refer to the product by its name when clarifying what performs an action. Use we mainly in proof or conversational buying statements.
- **Rhythm:** Short outcome headlines contrast with practical explanatory paragraphs. Paired clauses and short full-stop fragments give promise copy momentum; action labels remain plain and specific.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | A product/category pair or an outcome stated without decorative adjectives. | 2–9 words | “[Brand] Enterprise”<br>“Visualise design intent at every stage” |
| Chapter promise | Short paired fragments or a concrete action/result. | 4–9 words | “Your ideas. Brought to life.”<br>“Build workflows that work for you”<br>“Keep shots visually consistent” |
| Supporting explanation | Name the input, operation and output, then explain how the user's workflow benefits. | 1–3 sentences | “Give your team an agent that turns creative direction into images, video, and finished assets. You set the vision. Agent works through the steps.” |
| Reassurance | A plain ownership statement with a decisive short ending. | 5–10 words | “Your data stays yours. Full stop.” |
| Action | Verb plus destination or immediate next step. | 1–5 words | “Contact Sales”<br>“Try with your own viewport”<br>“Download” |
| Closing invitation | Ask a direct readiness question or offer a simple first step. | 4–10 words | “Ready to bring AI to your team?”<br>“Get started for free” |

**Words and phrasing to use:** your team; from idea to; built for; workflows; create; explore; keep; control; repeatable; start with

**Avoid:** revolutionize everything; unparalleled synergy; next-gen ecosystem; magical one-click transformation; exclamation-heavy encouragement

**Rules:**

- Make the headline name the outcome; let the support explain the mechanism.
- Describe actual starting materials and finished work rather than a list of abstractions.
- Use medium-weight phrases inside body paragraphs to provide a fast reading path.
- When introducing a buying path, explicitly distinguish individual exploration from team rollout.
- Make compatibility and setup answers practical and concise.

## Do's and Don'ts

### Do

- Set the default opening in regular 109.4px type with -0.065em tracking and a two-line composition.
- Use the 1280px editorial shell with 48px side padding and 64px split-column gaps.
- Keep default conversion actions black, 44px high and fully pill-shaped.
- Include original pearlescent loop artwork, softly grainy and partly clipped at a frame edge.
- Use 16px corners for product panels and proof cards, with 24px card padding.
- Give cinematic result demonstrations a different scale from ordinary cards: 72px overlay type and broad full-width media.
- Use #f5f5f5 for the ending directory, with four columns and 14px link gaps.
- Keep small uppercase chapter labels at 12px with 0.1em tracking.

### Don't

- Do not substitute a heavy geometric display face for the regular Swiss grotesk opening.
- Do not turn the utility blue into the default full-width section color or primary CTA fill.
- Do not apply glass blur to ordinary white proof cards; translucent material belongs to navigation and media controls.
- Do not make every action an 8px rectangle; that shape belongs to embedded pricing actions.
- Do not put a thick border or a deep shadow around every editorial section; most sit directly on white.
- Do not use a black canvas for the default long-form marketing story; reserve it for dramatic interruptions and scoped dark page types.
- Do not collapse the directory into a single logo-and-copyright strip; preserve grouped navigation and a lower icon baseline.
- Do not center every capability chapter; split columns and left-aligned explanations carry the practical reading rhythm.

## Motion and responsive

### Motion

**Observed:**

- Primary pills declare color/background transitions of 150ms with cubic-bezier(.4,0,.2,1).
- Navigation links declare color 0.2s ease-out, background-color 0.1s ease-out and scale 0.5s ease-out; the header declares transform 0.7s cubic-bezier(0.4,0,0.2,1).
- Proof-card art declares a 0.7s transform transition with cubic-bezier(0,0,.2,1) and a supported-hover scale of 1.05.
- Integration title entry declares 0.75s cubic-bezier(0.22,1,0.36,1); the logo entry declares 0.8s cubic-bezier(0.16,1.3,0.3,1) with a 0.18s delay.
- A logo marquee declares 32s linear infinite movement; immersive showcases include pause controls.

**Transfer:**

- Keep hover changes local to the action or artwork; the proof-card text stays stable while its art gently enlarges.
- Use the integration entry treatment only for the theatrical product composition, not every paragraph.
- Provide a pause control when presenting a moving full-width showcase.

**Unknown:**

- Actual scroll-trigger timing, video sequencing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- The default opening display uses clamp(64px, 7.6vw, 116px); scenic solution titles use clamp(36px, 4.8vw, 60px).
- Layout declarations include single-column bases with two-column larger-screen splits and three-column wider pricing grids; exact breakpoint widths are not established.
- Proof rails use scroll snapping; footer declarations support two columns before the four-column layout.

**Transfer:**

- On narrow layouts, stack the opening support below the title but keep the workspace as the next large object; preserve clipped ribbon fragments rather than squeezing a whole loop between words.
- Stack feature chapters into a clear copy/media reading order and keep horizontally scrollable proof cards recognizably card-sized.
- Reduce the floating integration composition to the central artifact and one legible tool panel instead of shrinking every panel.
- Keep dense comparison information in a separately navigable area rather than reducing all table text to illegibility.

**Unknown:**

- Mobile spacing, navigation disclosure behavior, exact breakpoints and narrow-screen cinematic compositions remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
