# Signal — friendly conviction in blue

## Overview

A bright, approachable product style that pairs emphatic sans-serif headlines with everyday human moments. Cornflower blue, aqua and lilac illustrations soften a predominantly white page, while black outlines and halftone dots give the art a playful editorial character. The density is relaxed in explanatory sections and more compact in navigation and the dark plum footer. It suits consumer tools and services that need to make an important promise feel understandable and welcoming.

### Essentials

- Short promises carry unusual typographic confidence: Inter 800 at 60px/64px for the opening and 40px/44px for section headings, with normal tracking rather than fashionable compression.
- The opening is a blue product stage, not a centered slogan: a 680px-high #9dbbf8 band pairs a roughly two-fifths text column with oversized overlapping, diagonally tilted product views that extend below the band.
- Actions stay friendly and modest: white rectangular buttons with 8px corners, blue 20px/28px semibold labels and a 50px height; the white-page variant adds a 2px blue outline.
- Color belongs to stages and pictures: one broad blue opening, aqua or lilac illustration backings and a #f6f6f6 card band sit among white explanatory sections; the only broad dark fill is the #3c3744 footer.
- Human product imagery and comic-like illustration work together: large interface views show real use, while 370px card illustrations combine black outlines, flat pastel forms and halftone patches. Every new page should carry this illustrated device; a simple outlined product metaphor with dotted texture is the fallback.
- Benefits are housed in generous white cards rather than tiny icon tiles: 660px-wide desktop cards use 30px padding, 16px corners, soft two-layer shadows, centered 28px/32px headings and 16px/22px support.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cornflower stage | `#9dbbf8` | `--color-hero-blue` | background | Broad opening product stage. |
| Action blue | `#2c6bed` | `--color-action` | action, link, border, accent | Button labels and outlined action borders; navigation hover. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Illustration aqua | `#a5cad5` | `--color-aqua` | surface, background | Flat rounded media backing and illustration panels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Main page, navigation, feature cards and buttons. |
| Feature band | `#f6f6f6` | `--color-band` | background | Full-width band behind raised white capability cards. |
| Navigation hairline | `#ebeaeb` | `--color-rule` | border | Single bottom rule on the white fixed header. |
| Footer light | `#e9e9e9` | `--color-inverse` | text, link | All footer copy, headings and links. |
| Supporting slate | `#404654` | `--color-secondary` | text | Compact card descriptions. |
| Footer plum | `#3c3744` | `--color-footer` | background | Closing directory band. |
| Primary ink | `#1b1b1b` | `--color-ink` | text | Headings, explanatory paragraphs and navigation. |

## Typography

- **Inter** — Headings, paragraphs, navigation, feature cards and footer. Readable contemporary sans serif, with a friendly open regular cut and emphatic extra-bold headings. Font stack: "Inter", sans-serif.
- **system-ui** — Primary and outlined button labels. Native interface sans serif with a firm semibold label. Font stack: "system-ui", -apple-system, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 800 | 60px | 64px | normal | Brief opening promise, left aligned. |
| heading | Inter | 800 | 40px | 1.1 | normal | Main explanatory headings and the centered introductory question. |
| card-heading | Inter | 800 | 28px | 32px | normal | Centered capability card titles. |
| body | Inter | 400 | 20px | 1.4 | normal | Opening support and primary explanatory paragraphs. |
| button | system-ui | 600 | 20px | 1.4 | normal | Both white and outlined action labels. |
| compact-body | Inter | 400 | 16px | 22px | normal | Card descriptions and footer text. |
| navigation | Inter | 400 | 16px | 1.5 | normal | Header navigation and language label. |
| footer-heading | Inter | 600 | 16px | 22px | normal | Footer directory category names. |

**Notes:**

- Keep normal letter spacing throughout; the contrast comes from 800-weight headings against 400-weight prose, not tracking changes.
- The main prose is deliberately substantial at 20px; switch to 16px only for denser cards and directory text.
- Headings use sentence or title case, never an all-caps eyebrow system. Let a section heading wrap naturally into two strong lines.

## Layout

**Density:** Airy explanatory sections alternate with substantial image-led cards; navigation and footer remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Card title-to-description gap. |
| 12px | Column inner padding, navigation horizontal padding and footer category-to-list gap. |
| 16px | Centered heading-to-support gap and header vertical padding. |
| 24px | Opening heading, support and action separation; visible gutters between feature cards. |
| 30px | Capability card internal padding. |
| 32px | Explanatory heading-to-paragraph separation. |
| 48px | Desktop section padding and main side inset at 1440px. |
| 64px | Breathing space after the opening band, accommodating overlapping media. |
| 96px | Footer bottom padding. |

### Containers and grids

- **main-container**: max width 1344px · side padding 48px. Centered desktop content container within full-width bands; 48px side insets at a 1440px viewport.
- **hero-split**: 2 columns · gap 24px. Text occupies roughly two fifths of the container, with a 523px support measure; overlapping product objects dominate the remaining right-hand area.
- **explanatory-split**: 2 columns · gap 24px. A 432px text column pairs with a larger media region holding 680px-wide art. Alternate the media side; align both blocks at the top.
- **capability-grid**: 2 columns · gap 24px. Equal 660px-wide cards, arranged in two desktop columns with equal gutters in both axes.
- **footer-directory**: 5 columns · gap 24px. A broad two-fifths legal/contact column is followed by four equal directory columns.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons | 8px |
| cards-and-media | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| feature-card | `rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px` | Raised capability cards against the pale gray band. |
| button | `rgba(51, 51, 51, 0.05) 0px 1.3px 2.5px 0px, rgba(51, 51, 51, 0.05) 0px 2.5px 5px 0px` | Very slight depth beneath both button variants. |

### Surfaces

#### Canvas · level 0

**Use:** Explanatory page regions.

**CSS:** `background: #ffffff; color: #1b1b1b`

#### Blue opening stage · level 0

**Use:** Full-width opening scene.

**CSS:** `background: #9dbbf8`

**Observed:** A flat fill without texture or gradients; product objects overlap its lower edge.

**Transfer:** Keep the blue as a broad stage behind a concrete product demonstration.

#### Capability band · level 0

**Use:** Backdrop for repeated benefit cards.

**CSS:** `background: #f6f6f6; padding: 48px`

#### Raised card · level 1

**Use:** Feature illustrations and concise explanations.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 30px; box-shadow: rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px`

#### Aqua media panel · level 0

**Use:** Large illustration or product-mechanism stage.

**CSS:** `background: #a5cad5; border-radius: 16px; padding: 16px`

**Observed:** Flat pastel panel, approximately square for the mechanism demonstration and wider for editorial art.

**Transfer:** Populate the panel with a legible outlined mechanism diagram or product metaphor.

#### Plum directory · level 0

**Use:** Footer ending.

**CSS:** `background: #3c3744; color: #e9e9e9; padding: 48px 24px 96px`

## Components

### Fixed navigation

**Use:** Persistent page navigation.

**CSS:** `position: fixed; top: 0px; width: 100%; z-index: 30; background: #ffffff; border-bottom: 1px solid #ebeaeb; padding: 16px 0px; height: 85px; box-sizing: border-box`

**Observed:** A compact brand mark sits on the left of the main container, while text links and a globe-language control align at the right. The first conversion link is plain text, not a second button.

**Transfer:** Keep a simple wordmark and a short utility navigation; offset page content by the header height.

### Navigation link

**Use:** Header destinations.

**CSS:** `display: flex; align-items: center; padding: 8px 12px; gap: 12px; color: #1b1b1b; text-decoration: none`

**Text style:** `navigation` — Inter 400 · 16px/1.5

**Observed:** Links form one right-aligned row; the language link adds a small globe before its label.

**States:** Declared: hover color #2c6bed with no underline; focus-visible solid 1px outline in hsl(233deg,100%,63%) with 1px offset; active outline-width 1px.

### Primary button

**Use:** Main action on the blue opening stage.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 50px; padding: 0px 20px; background: #ffffff; color: #2c6bed; border-radius: 8px; box-shadow: rgba(51, 51, 51, 0.05) 0px 1.3px 2.5px 0px, rgba(51, 51, 51, 0.05) 0px 2.5px 5px 0px; text-decoration: none`

**Text style:** `button` — system-ui 600 · 20px/1.4

**Observed:** A standalone text-only action below the support paragraph, sized to its label rather than stretched across the text column.

**States:** Declared: hover color #1851b4, white background and no underline; focus-visible border-color hsl(233deg,100%,63%), outline none, and 0 0 0 0.1875em hsla(233deg,100%,63%,0.25) box-shadow; active outline none.

### Outlined button

**Use:** Closing action on white.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 50px; box-sizing: border-box; padding: 9px 19px; background: #ffffff; color: #2c6bed; border: 2px solid #2c6bed; border-radius: 8px; box-shadow: rgba(51, 51, 51, 0.05) 0px 1.3px 2.5px 0px, rgba(51, 51, 51, 0.05) 0px 2.5px 5px 0px`

**Text style:** `button` — system-ui 600 · 20px/1.4

**Observed:** Appears below an explanatory closing paragraph rather than inside a separate colored CTA banner.

**States:** Declared: hover text and border #1851b4, background white, no underline; focus-visible border-color hsl(233deg,100%,63%), outline none, and 0 0 0 0.1875em hsla(233deg,100%,63%,0.25) box-shadow; active outline none.

### Capability card

**Use:** Repeated illustrated benefit explanations.

**CSS:** `background: #ffffff; padding: 30px; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px; text-align: center`

**Text style:** `card-heading` — Inter 800 · 28px/32px

**Observed:** A centered 370px illustration precedes a short heading and compact slate description. The heading-to-description gap is tight; the visual takes most of the card height. No separate CTA or corner badge.

**Transfer:** Use one understandable capability per card with a real scene or outlined visual metaphor.

### Footer link

**Use:** Directory destinations and inline legal/contact links.

**CSS:** `color: #e9e9e9; text-decoration: none`

**Text style:** `compact-body` — Inter 400 · 16px/22px

**Observed:** Plain light text against the plum footer; list links occupy consecutive lines without button framing.

**States:** Declared: hover color #1851b4 with underline; focus-visible solid 1px outline in hsl(233deg,100%,63%) with 1px offset; active outline-width 1px.

### Footer category

**Use:** Labels above footer link lists.

**CSS:** `display: block; color: #e9e9e9; margin-bottom: 12px`

**Text style:** `footer-heading` — Inter 600 · 16px/22px

**Observed:** Semibold sentence-case label above a compact vertical list, aligned to the top of the legal column.

## Imagery and graphics

### Overlapping product views

**Use:** Dominant opening visual.

**Observed:** Two large black phones tilt diagonally in parallel, overlap each other and break below the flat blue band. One shows a lively collage of people in a call; the other shows a dark conversation interface. The text stays upright and unobstructed to the left.

**Transfer:** Show two complementary views of the new product with credible human content. Without polished hardware renders, use two crisp interface panels in dark rounded frames with the same overlapping diagonal stance; keep them much larger than the action button.

**Build:** Create two portrait interface frames about 500px wide, each with a dark shell and rounded edges. Rotate each about 20deg clockwise, stagger their top edges, place the front frame above and right of the back frame, and let the lower frame extend beyond the blue stage. Use real product content, not decorative empty screens.

### Outlined collage illustrations

**Use:** Signature treatment for capability cards and editorial chapters.

**Observed:** Flat pastel speech-like shapes and simplified interface windows use dark contours, small black or blue halftone patches, and occasional photographic cutouts. Card art is roughly square and centered; larger chapters use a 680px by 533px rounded pastel panel. The later scenes show stacked windows crossed out on lilac and a blue halftone globe with speech bubbles on aqua.

**Transfer:** Translate the new product's benefits into simple objects and human moments, keeping the combination of flat color, dark outlines, dot texture and a few photographic fragments. The minimum version is a well-composed set of overlapping outlined panels plus a dotted patch on a pastel backing.

**Build:** Use an SVG artboard with rounded panels filled in aqua, cornflower blue and white, outlined in near-black at 2–3px. Layer three to five shapes with small overlaps; introduce one circular badge and a restrained photograph clipped into a rounded rectangle. Define a repeating 6px square SVG pattern containing a 1px-radius ink or blue dot; apply it to one offset patch behind the main shapes. For a wide scene, center the composition inside a 680px by 533px panel with 16px corners.

### Mechanism demonstration

**Use:** Visual explanation beside a long-form benefit paragraph.

**Observed:** An aqua rounded panel contains a partial view of a coded message bubble and lock at its lower edge.

**Transfer:** Explain one mechanism with populated interface fragments or a simple outlined diagram using the same aqua stage; the visual must communicate an actual process rather than merely provide a colored rectangle.

### Icons

**Observed:** Marketing navigation is mainly text. A small dark globe accompanies the language selector; illustrations use simple solid document, play, camera, heart and lock symbols inside outlined scenes.

**Transfer:** Use compact recognizable symbols within the illustration system; avoid adding a standalone icon above every section heading.

## Section recipes

How recurring sections are built.

### First screen: Blue product-stage opening

**Observed:** A fixed white navigation sits above a 680px cornflower band. Upright left-aligned copy occupies about two fifths of the container, with a short 60px/64px extra-bold headline, a three-line 20px/28px paragraph, then the Primary button at 24px intervals. Two overlapping tilted phones occupy most of the right half, starting near the top of the band and extending approximately 108px below its lower edge. Layers are flat blue, rear product view, front product view, then unobscured text and action. Within the first 900px, the header, complete promise and action, both product views and the beginning of the next centered heading are visible; its support text lies farther down.

**Transfer:** Lead with one brief outcome and two concrete views that make the product immediately intelligible. For a product without device media, use populated framed panels with the same diagonal overlap. More informational pages can open with a shorter text introduction while retaining the heavy sentence-case heading and illustrated product device elsewhere.

**Avoid:** Do not turn this into a centered oversized headline over a small floating thumbnail, or place text on top of the busy product imagery.

**Text style:** `display` — Inter 800 · 60px/64px

### Centered bridge

**Observed:** A white introductory block uses 48px section padding, a centered Heading and a single Body line 16px below it. It serves as a calm bridge from the oversized opening object into detailed explanation.

**Transfer:** Use a short reader-oriented question or invitation to introduce the product's reasons to believe.

**Text style:** `heading` — Inter 800 · 40px/1.1

### Asymmetric explanatory chapter

**Observed:** White section with 48px padding, a 432px text measure and a larger media side containing 680px-wide artwork. Heading and Body are separated by 32px. Both sides align at the top, leaving visible white space below short copy. Media alternates sides between chapters.

**Transfer:** Pair one substantial benefit or objection with a concrete visual explanation. Vary the media side to sustain pace without changing the typography.

**Text style:** `heading` — Inter 800 · 40px/1.1

### Illustrated capability grid

**Observed:** Capability band contains two columns of Capability cards separated by 24px. The 370px art, Card heading and Compact body align centrally; the card title is followed by just 4px before its description.

**Transfer:** Group related capabilities into equally weighted illustrated explanations, with concise captions rather than a long feature checklist.

**Text style:** `card-heading` — Inter 800 · 28px/32px

### Illustrated closing invitation

**Observed:** The last white chapter pairs a large aqua-backed outlined illustration on the left with a Heading, Body paragraph and Outlined button on the right. It has the same 48px padding as the preceding information sections and gives way directly to the Plum directory.

**Transfer:** Close with the product's practical reason to act and an appropriate conversion, support or participation action, maintaining the explanatory tone rather than switching to a sales billboard.

**Text style:** `heading` — Inter 800 · 40px/1.1

### Plum directory ending

**Observed:** A 288px-high full-width footer ends the page. The main container places a wide copyright, legal and contact block at left, with four compact directory columns to the right. Footer categories and Footer links share a 22px line rhythm; the surface uses 48px top and 96px bottom padding.

**Transfer:** End with useful destinations and concise legal/contact context in a compact dark band; preserve the visual hierarchy of one broad information column and narrow lists.

**Text style:** `footer-heading` — Inter 600 · 16px/22px

## Page flow

**Storyline:** Plainspoken promise → product in use → reasons to believe → illustrated capabilities → objection handling → invitation to act → practical directory.

### Consumer product landing page that makes a strong promise understandable through approachable demonstration

1. **Promise and demonstration** — Blue stage with short extra-bold promise, support, white action and two oversized product views.
2. **Orientation** — Centered question and a one-line invitation to explore.
3. **Reason to believe** — Longer explanatory paragraph beside a rounded visual mechanism panel.
4. **Capability chapters** — Two-column collection of illustrated white cards on a pale gray band.
5. **Objection handling** — Asymmetric white chapter with blunt heading and a pastel-backed editorial illustration.
6. **Closing call** — Mirrored illustration-and-copy chapter with outlined action.
7. **Utility ending** — Plum directory with legal/contact text and compact category lists.

**Transfer:** Adapt this argument to the new product's strongest promise, supporting mechanisms and genuine reader concerns. Retain the alternation between concrete product views, approachable illustrations and readable explanations without requiring a fixed number of blocks.

## Writing

Warm, direct and certain. The language makes a serious distinction without sounding institutional, alternating practical explanations with little flashes of humor.

**Do not copy:** Do not reuse Signal names, logos, artwork, interface content, privacy or security guarantees, nonprofit status, ownership assertions, donation claims, legal statements or source-specific facts. Source examples illustrate cadence only; write truthful new claims for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the organization when making a clear commitment. Name the product naturally inside explanatory paragraphs.
- **Rhythm:** Headlines are brief, often two to six words. Body paragraphs use short declarative sentences, with occasional repeated phrases or a three-part cadence. Actions name the task directly.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Two-word imperative or outcome stated without qualifiers. | 2–4 words | “Speak Freely” |
| Section headline | A concrete benefit, short question or emphatic repeated negative. | 3–7 words | “Share Without Insecurity”<br>“No ads. No trackers. No kidding.”<br>“Why use [Brand]?” |
| Supporting line | Friendly invitation followed by tangible product qualities. | One sentence for a bridge; a short paragraph for explanation. | “Explore below to see why [Brand] is a simple, powerful, and secure messenger” |
| Capability description | Lead with what the reader can do, then explain its everyday advantage. | 1–2 sentences | “Make crystal-clear voice and video calls to people who live across town, or across the ocean, with no long-distance charges.” |
| Primary action | Plain verb plus product or recipient, without promotional urgency. | 2–4 words | “Get [Brand]”<br>“Donate to [Brand]” |

**Words and phrasing to use:** you; your; share; simple; for everyone; every time; no kidding; the people who matter

**Avoid:** revolutionary ecosystem; synergy; enterprise-grade transformation; limited-time urgency; unsubstantiated superlatives

**Rules:**

- Translate mechanisms into what the reader can actually do or stop worrying about.
- Use humor sparingly in headings, then make the paragraph precise and useful.
- A repeated sentence fragment can provide emphasis; do not turn every heading into a slogan.
- Keep the main action label literal and brief.

## Do's and Don'ts

### Do

- Use 800-weight Inter at 60px/64px for the opening promise and 40px/44px for section leads.
- Keep the 20px/28px body recipe for explanatory sections rather than shrinking it to interface size.
- Use 48px desktop section insets and a 1344px maximum content width.
- Stage substantial product objects on flat blue, with controlled overlap beyond the band's lower edge.
- Construct illustration cards with 16px corners, 30px padding and a 24px grid gutter.
- Keep conversion buttons at 50px high with 8px corners and blue semibold text.
- Carry the black-outline and halftone illustration language into new product metaphors.
- Finish with a compact plum directory and light 16px/22px text.

### Don't

- Do not tighten display tracking into a condensed tech aesthetic; tracking is normal at every measured role.
- Do not replace the white blue-text primary button with a dark filled pill.
- Do not make the whole site blue; white sections and the pale gray feature band provide most of its pacing.
- Do not use gradients, glass blur or neon glow in place of flat pastel stages.
- Do not reduce capability cards to small icons and a sentence; their 370px image is the main content.
- Do not add rounded borders to every prose region; the white explanatory chapters remain open.
- Do not turn the footer into another oversized headline or a subscription form; it is a small-text directory.
- Do not place headings in thin weights or uppercase micro-labels; heavy sentence-case headings supply the hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 294ms ease transitions for background-color, border-color and color; the two button variants also transition box-shadow.
- No matching element animations are established for the main marketing elements.

**Transfer:**

- Use the declared short color and border transitions on text links and buttons; keep the product-stage composition visually stable.

**Unknown:**

- The timing and behavior of the illustrated mechanism animation are not established.

### Responsive

**Observed:**

- Declared width breakpoints occur at 768px, 769px, 770px, 1023px, 1024px, 1215px, 1216px, 1407px and 1408px.
- Explanatory rows are designated desktop layouts; the final illustration is designated hidden on touch layouts and the wide legal column hidden on mobile.

**Transfer:**

- For narrow screens, use a single readable text column and stack capability cards; retain their image-first hierarchy.
- Reduce the diagonal opening scene as one composition rather than allowing either product frame to obscure the promise or action.
- Treat the large closing illustration as dispensable at narrow widths while keeping the closing copy and action.

**Unknown:**

- Exact mobile type sizes, navigation expansion behavior and breakpoint-specific spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
