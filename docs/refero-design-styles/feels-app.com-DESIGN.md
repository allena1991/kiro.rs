# Feels — neon nights, human stories

## Overview

A cinematic, after-dark style with youthful warmth and a spacious, almost stage-like pace. White geometric display lettering and light grotesk text sit on deep green-black, while violet light and saturated lifestyle footage supply the energy. It suits consumer apps and experience-led products, pairing immersive human imagery with isolated portrait-format product demonstrations rather than dense card grids.

### Essentials

- A film becomes the opening canvas: edge-to-edge imagery fills a 900px desktop screen, with a transparent-to-#141919 fade beginning halfway down and white text layered over it.
- Headlines feel oversized but unforced: Clashdisplay at 115.2px/93.6px, weight 400, normal tracking for the opening; paired statements use 86.4px/100.8px at weight 300.
- Conversion controls are bright islands: the main action is a white 317px × 65px pill with black 20.2px weight-600 lettering and a 900px radius.
- Color lives in light and media, not interface chrome: most of the long page remains #141919 with white text, while violet-blue halos, colorful demonstrations and the opening film carry saturation.
- Product proof is staged as a solo performance: a roughly 353px × 747px portrait demonstration stands near the center of a 900px chapter, with a short side caption alternating left and right. Use a real workflow or a designed portrait-format outcome when no app interface exists.
- A luminous oversized orb anchors the ending: a soft violet-blue light is clipped by the lower-left edge beneath a centered 72px two-line invitation and paired white destination pills; retain this light device even when the product has no photographic media.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender light | `#b5a0ff` | `--color-orb-light` | accent | Pale violet core of atmospheric orb artwork; use as a light source fading into the dark canvas, never as a flat section fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White lettering | `#ffffff` | `--color-foreground` | text | Headlines, navigation, feature copy and small captions. |
| Black action ink | `#000000` | `--color-action-ink` | text | Text and destination symbols on white actions. |
| Green-black stage | `#141919` | `--color-canvas` | background | Continuous canvas beneath the film, product chapters and final invitation. |
| Soft gray | `#afafaf` | `--color-muted` | text | Centered supporting statement below the paired display scene. |
| White action fill | `#ffffff` | `--color-action` | action, surface | Solid primary and destination pills; the principal bright opaque surfaces. |

## Typography

- **Clashdisplay** — Opening headline, paired statements, feature titles and closing invitation. Wide, geometric display sans with distinctive shapes and a delicate, open rhythm. If unavailable, use **Space Grotesk**. Use weights 300–400; preserve broad proportions and normal tracking. Font stack: "Clashdisplay", "Space Grotesk", Arial, sans-serif.
- **Aeonik** — Support copy, navigation, action labels and compact captions. Clean rounded grotesk; most prose is light, with sharply localized bold emphasis. If unavailable, use **Inter**. Use weight 300 for prose, 400 for navigation and 600 for primary actions. Font stack: "Aeonik", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Clashdisplay | 400 | 115.2px | 93.6px | normal | size 8vw, line height 6.5vw | Single-line centered opening promise. |
| heading-pair | Clashdisplay | 300 | 86.4px | 100.8px | normal | size 6vw, line height 7vw | Two short statements separated by a central visual. |
| closing | Clashdisplay | 400 | 72px | 1.16 | normal | size 5vw | Centered two-line conversion invitation. |
| feature-title | Clashdisplay | 400 | 34.6px | 0.625 | normal | size 2.4vw | Short single-line side captions beside product demonstrations. |
| section-support | Aeonik | 300 | 21.6px | 0.926 | -0.0133em | size 1.5vw | A muted, single-line bridge between conceptual scene and product proof. |
| hero-support | Aeonik | 300 | 20.2px | 1.357 | -0.014em | size 1.4vw | Centered one-sentence explanation beneath the opening promise. |
| action | Aeonik | 600 | 20.2px | 0.992 | -0.014em | size 1.4vw | Primary conversion label. |
| navigation | Aeonik | 400 | 17.3px | 0.833 | -0.0116em | size 1.2vw | Small plain-text header links. |
| body | Aeonik | 300 | 16.6px | 1.304 | -0.0174em | size 1.15vw | Brief feature explanations; emphasize only the key mechanism at weight 700. |
| caption | Aeonik | 300 | 14.4px | 1.39 | -0.02em | size 1vw | Parenthetical reassurance beneath the main action and compact footer line. |
| footer-link | Aeonik | 300 | 14.4px | 2 | -0.02em | size 1vw | Underlined utility links in the closing section. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display lettering keeps normal tracking rather than heavy negative spacing; body lettering uses a small negative offset.
- The very tight feature-title line box is for short single-line headings. Give longer replacement headings room rather than forcing multiple lines into it.
- The main contrast is scale and lightness, not a proliferation of weights: large display, modest feature captions and very small footer utilities.

## Layout

**Density:** Airy, with full-screen stages and small text groups occupying only a fraction of each scene.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 13.5px | Gap from the primary action to its parenthetical reassurance. | fixed |
| 14.4px | Feature caption inner padding. | 1vw |
| 16px | Destination-pair and navigation gaps. | fixed |
| 21.6px | Top inset of the opening stage. | 1.5vw |
| 28.8px | Page side inset, opening support separation and feature-title bottom margin. | 2vw |
| 36px | Opening action top margin. | fixed |
| 63px | Closing destination-pair top margin. | fixed |
| 90px | Top and bottom padding of product chapters. | fixed |

### Containers and grids

- **stage**: max width 1440px · side padding 28.8px. Full-width dark scenes; desktop stages are 900px tall and content is allowed to sit in a broad empty field.
- **navigation**: 5 columns · gap 16px. Compact right-hand group of three text links and two destination pills, balanced against a white logo on the left.
- **portrait demonstration**: max width 418px. Portrait media appears at roughly 353px × 747px near the center, with captions in the outer thirds.
- **closing text**: max width 634px. Centered invitation limited to two lines above a horizontal action pair.

## Corner radius

| Element | Radius |
| --- | --- |
| primary pill | 900px |

## Surfaces and depth

### Surfaces

#### Dark stage · level 0

**Use:** Continuous page canvas and product stages.

**CSS:** `background: #141919; color: #ffffff`

**Observed:** No visible card shells or separators between the major scenes.

**Transfer:** Let media and typography define chapters without adding panel chrome.

#### Film fade · level 1

**Use:** Legibility layer over opening footage and transition into the dark page.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0) 50%, #141919)`

**Observed:** The upper image remains vivid; the bottom merges into the next dark stage.

**Transfer:** Place over full-bleed footage, below all text and controls.

#### White action · level 2

**Use:** Primary conversion controls.

**CSS:** `background: #ffffff; color: #000000; border-radius: 900px`

**Observed:** Solid, flat and borderless rather than translucent or glowing.

**Transfer:** Keep white fills confined to actions so they retain priority.

## Components

### Primary button

**Use:** Main opening conversion.

**CSS:** `background: #ffffff; color: #000000; width: 317px; height: 65px; border-radius: 900px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Aeonik 600 · 20.2px/0.992 · tracking -0.014em

**Observed:** One centered text-only pill with a separate reassurance caption below it.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

### Navigation link

**Use:** Lightweight chapter navigation in the opening header.

**CSS:** `color: #ffffff; text-align: center; background: transparent`

**Text style:** `navigation` — Aeonik 400 · 17.3px/0.833 · tracking -0.0116em

**Observed:** Three short links precede two smaller destination pills; all sit directly on the film.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

### Destination pair

**Use:** Two equal-weight destinations in the final conversion stage.

**CSS:** `display: grid; grid-template-columns: 187px 187px; gap: 16px; margin-top: 63px; justify-content: center`

**Observed:** Each destination is a white capsule containing a black platform symbol and label. The same artwork appears smaller in the header; the closing pair is 64px tall.

**Transfer:** Use two genuine distribution channels or meaningful product destinations, keeping equal visual weight.

### Feature caption

**Use:** Minimal explanation beside the large portrait demonstration.

**CSS:** `padding: 14.4px; color: #ffffff`

**Text style:** `body` — Aeonik 300 · 16.6px/1.304 · tracking -0.0174em

**Observed:** A Feature-title heading sits above two short lines of body copy. The side facing the demonstration is used for alignment; selected mechanism words are bold.

**Transfer:** Name one action or outcome, then explain it in one sentence.

### Reassurance caption

**Use:** A small personal aside below the main action.

**CSS:** `margin-top: 13.5px; color: #ffffff; text-align: center`

**Text style:** `caption` — Aeonik 300 · 14.4px/1.39 · tracking -0.02em

**Observed:** A parenthetical line lends conversational social reassurance without a separate proof card.

### Footer link

**Use:** Small utility navigation at the bottom of the closing stage.

**CSS:** `color: #ffffff; text-decoration: underline; margin-right: 10px`

**Text style:** `footer-link` — Aeonik 300 · 14.4px/2 · tracking -0.02em

**Observed:** A short centered horizontal run sits above a single compact ownership/contact line, not a multi-column sitemap.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

### Portrait demonstration

**Use:** Main product proof within each capability chapter.

**CSS:** `width: 353px; height: 747px; object-fit: cover; overflow: hidden`

**Observed:** An upright rounded device silhouette with a brightly colored rim contains moving interface content. A violet-blue glow emerges behind one side; there is no surrounding card.

**Transfer:** Show a real workflow. If no phone product exists, place a portrait-format output in a similarly tall rounded frame, keeping it visually dominant.

## Imagery and graphics

### Nightlife film

**Use:** Immersive first-screen backdrop.

**Observed:** Close, candid human footage in a crowded karaoke setting, with magenta ceiling light, deep blue shadows and foreground blur. It fills the viewport behind white lettering; a dark lower fade keeps controls legible.

**Transfer:** Use candid footage of the product's human outcome with colored ambient light, imperfect close framing and visible activity. The minimum equivalent is a full-bleed still with the same cinematic crop and light.

### Portrait product stories

**Use:** Central product demonstrations in capability chapters.

**Observed:** Tall rounded mobile views show people, story cards and prompt selection, with violet, pale lime or blue rims. The vivid product content occupies roughly a quarter of the screen width while the adjacent caption remains small.

**Transfer:** Keep internal UI faithful to the new product; preserve the tall framing, one-task focus and saturated edge treatment, not the depicted interface.

### Luminous orb

**Use:** Signature light behind demonstrations and at the page ending.

**Observed:** A soft violet-blue circular light with a pale lavender core and very blurred dark edges sits behind the product. In the ending it grows dramatically, with most of the circle extending beyond the lower-left edge.

**Transfer:** Retain a localized, luminous orb rather than tinting the whole page; use it as the atmospheric counterpart to clean white type.

**Build:** Layer a 576px circular radial gradient behind the demonstration: rgba(181,160,255,0.9) at the core, rgba(126,104,241,0.6) through the middle, and rgba(96,117,236,0) at the edge. Blur by 32px and keep the product above it. For the ending, enlarge the light to roughly 1440px wide and move over half its width outside the left edge; clip it within the stage. Match the soft light falloff; exact stops are not essential.

### Central collage strip

**Use:** Visual separator between two monumental benefit statements.

**Observed:** A narrow central moving strip of rounded activity-image tiles separates large left and right headings; image fragments and a bright lime tile provide the color against the dark canvas.

**Transfer:** Use a compact montage of real outputs or customer moments between two short complementary statements. Populate every tile with meaningful material rather than empty decorative boxes.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A 900px full-bleed Film fade stage layers candid colored footage, then a dark bottom fade, then an unboxed header and centered conversion group. A white logo occupies the top left while plain navigation and two compact destination pills occupy the top right, inset 28.8px from the sides. The 115.2px Display headline spans roughly two thirds of the width around the vertical middle; the 20.2px Hero-support line follows beneath it. A Primary button and Reassurance caption form a centered stack below. All of this fits inside the first 900px, with no next-section heading above the fold.

**Transfer:** Choose one short product promise and an immersive human-outcome scene. Without film, use a strongly lit still with the same fade and layered type. Other page types can open with the same cinematic hierarchy and a topic-specific promise, keeping the action visible.

**Avoid:** Do not turn the opening into a left-aligned text column beside a small framed image, or replace the large light headline with a heavy all-caps slogan.

**Text style:** `display` — Clashdisplay 400 · 115.2px/93.6px

### Paired benefit scene

**Observed:** Two Heading-pair statements occupy opposing sides of the dark stage with a Central collage strip between them. A muted Section-support line sits below, separated by substantial empty space.

**Transfer:** Pair two complementary reader benefits, leaving the center for a compact visual bridge rather than a third paragraph.

**Text style:** `heading-pair` — Clashdisplay 300 · 86.4px/100.8px

### Solo capability chapter

**Observed:** A 900px Dark stage uses 90px vertical and 28.8px horizontal padding. Portrait demonstration is near the center with Luminous orb behind it. Feature caption alternates between left and right across successive scenes and aligns toward the media.

**Transfer:** Give each important capability its own dominant demonstration and a short caption. Adapt the chapter count to the product rather than compressing the proof into a card grid.

**Text style:** `feature-title` — Clashdisplay 400 · 34.6px/0.625

### Luminous closing invitation

**Observed:** A full 900px Dark stage holds a centered two-line Closing headline in a 634px text measure, a Destination pair beneath, and a huge Luminous orb clipped at lower left. Footer links and one compact ownership/contact line finish the stage near the bottom. The ending remains sparse and image-led rather than becoming a dense footer.

**Transfer:** Close with an inviting action phrase and the actual acquisition destinations. Keep the oversized off-edge light and compact utilities even for a non-app product.

**Text style:** `closing` — Clashdisplay 400 · 72px/1.16

## Page flow

**Storyline:** Emotional promise → personal relevance → visual benefit bridge → focused capability demonstrations → luminous invitation and compact utilities.

### An experience-led product landing page that makes the product feel like an invitation rather than a specification sheet

1. **Promise** — Full-screen human footage with a monumental centered promise and one main action.
2. **Personal relevance** — A spacious dark conceptual passage slows the pace before the product appears.
3. **Benefit bridge** — Two large complementary statements surround a narrow image montage, followed by a subdued explanation.
4. **Capability chapters** — Successive portrait demonstrations with alternating short side captions and localized glowing light.
5. **Closing call** — A two-line invitation, paired destination actions, oversized off-edge glow and small centered utility links.

**Transfer:** Retain the emotional-to-concrete arc and screen-sized staging; vary the number and order of demonstrations according to the new product.

## Writing

Direct, youthful and inviting, with a little conversational swagger. The product is framed through what the reader can do and feel, not through technical superiority.

**Do not copy:** Do not reuse Feels branding, its logo, app UI, age restriction, audience-size claims, people/profile details, company information or contact details. Source examples illustrate cadence, not replacement claims.

- **Addressing the reader:** Speak to the reader with you and your; favor active invitations. The product can be named in the main action.
- **Rhythm:** Two-to-four-word benefit titles, one-sentence support lines and compact two-line feature explanations. Parentheses provide a softer aside beneath a decisive action.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact, categorical statement with a memorable constraint. | 3–5 words | “Strictly Under 30” |
| Paired benefits | Parallel possessive fragments with terminal periods. | 2 words each | “Your Time.”<br>“Your People.” |
| Supporting line | An active invitation connecting the product to a lived outcome. | 12–18 words | “Meet people who share your thirst for life and once-in-a-lifetime experiences.” |
| Feature title | Conversational imperative or familiar idiom. | 2–4 words | “Slide into DMs”<br>“Break the ice” |
| Primary action | Direct verb plus product name. | 2–3 words | “Join [Brand]” |
| Closing invitation | Practical action joined to an energetic invitation. | 6–9 words | “Download the app and jump in” |

**Words and phrasing to use:** your; meet; make it count; jump in; lasting memories; short everyday idioms

**Avoid:** enterprise-grade; leverage; unlock synergies; revolutionary platform; formal institutional language

**Rules:**

- Lead with an experience or outcome before naming the mechanism.
- Give each product chapter one idea; emphasize only its key noun phrase in bold.
- Use punctuation purposefully: periods for parallel fragments, parentheses for the small aside.
- Keep footer labels literal and short.

## Do's and Don'ts

### Do

- Keep the dark canvas at #141919 rather than neutral black.
- Use weight 300 for ordinary prose and weight 400 for the largest opening display.
- Preserve 28.8px desktop side insets and 16px action-pair gaps.
- Let the 353px × 747px demonstration dwarf its nearby 34.6px title.
- Keep the 317px × 65px primary pill centered below the opening support.
- Retain the huge clipped lower-left glow in the closing composition.
- Align side captions toward the central demonstration.

### Don't

- Do not use violet as a solid marketing-page button fill; white pills provide action contrast.
- Do not turn the green-black stages into alternating white and dark bands.
- Do not add borders, shadows and rounded card shells around every feature explanation.
- Do not shrink the paired 86.4px statements into ordinary body-sized labels.
- Do not put the entire support sentence in bold; weight 700 is reserved for a few mechanism words.
- Do not expand the small centered footer into a dense multi-column sitemap.
- Do not place the final glow as a small centered icon; its oversized off-edge scale is essential.

## Motion and responsive

### Motion

**Observed:**

- Opening and product media are videos.
- Product chapters and conceptual stages use sticky positioning.
- No action or surface transitions are declared for the reviewed elements.

**Transfer:**

- Let a stationary, central product scene carry changing demonstrations as the narrative advances; maintain readable captions and the isolated glow.
- Use a still image with the same framing when motion media is unavailable.

**Unknown:**

- Scroll choreography, fade timing and easing are not established.
- No focus-visible treatment was established.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 480px, 767px, 768px and 991px.
- Display, body and spacing roles use viewport-relative formulas on desktop.

**Transfer:**

- On narrow layouts, preserve the film-backed centered opening and white pill, while clamping text to readable sizes.
- Stack side captions with the portrait demonstration rather than squeezing a three-part desktop composition; retain the glow behind the media and clipped into the closing stage.

**Unknown:**

- Exact mobile navigation, stacking, sizing and sticky behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
