# Genie — cloudborne creative play

## Overview

An airy, light marketing style that makes capable software feel like an imaginative companion. Near-white sky blue and lavender stages surround rounded grotesk typography, cheerful vector characters and toy-like interface objects. Large illustrated moments alternate with compact pastel product cards, giving creative tools and approachable digital services a playful but legible presentation.

### Essentials

- Headlines behave like illustrated sentences: Aeonik 48px/56px at weight 500, with circular pictograms inserted between words; explanatory statements expand to 72px/80px with -0.02em tracking.
- The opening is a cloud-framed stage, not a dashboard billboard: a 20px inset, pale-blue 1400px-wide field, a centered two-line promise and one 48px-high dark action, with floating objects around the edges and a character beneath.
- Conversion controls are little charcoal capsules: #181d27, white Geist 16px/24px at 600, 12px 32px padding and 32px corners; the navigation action shrinks to 32px high with 16px corners.
- Color lives in atmosphere and objects rather than text: white and near-white fields dominate, blue and lavender wash whole scenes, and stronger blue, peach, mint and yellow are confined to pictograms and media. Feature cards use #cce7ff, #f1e6ff and #d3f6e3 while headlines stay #0a0d12.
- Illustration carries the personality: scalloped clouds, rounded four-point sparkles and friendly flat characters frame the message; glossy 24px-corner tiles add toy-like depth inside otherwise flat 32px-corner cards. Use original simple vector objects when there is no character artwork.
- A monumental word interlude and an illustrated curtain-call give the page theatrical punctuation: 148px/156px words sit in 480px-tall bands, and an oversized friendly figure emerges behind white scallops before a tiny centered footer. These devices belong in new adaptations, without requiring the same section order.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue token | `#99cfff` | `--color-badge-blue` | accent, surface | Circular illustrated badges and friendly sky accents. |
| Peach token | `#ffcfb4` | `--color-peach` | accent, surface | Circular inline illustration badges and small decorative objects. |
| Mint token | `#a8ecc7` | `--color-badge-mint` | accent, surface | Inline illustration token backing. |
| Yellow token | `#fff2be` | `--color-badge-yellow` | accent, surface | Warm illustration token backing. |
| Blue feature | `#cce7ff` | `--color-feature-blue` | surface | Tall capability card. |
| Purple token | `#e4ccff` | `--color-badge-purple` | accent, surface | Inline illustration tokens and soft decorative squares. |
| Closing sky | `#d6ecff` | `--color-closing-blue` | background | Most visible blue in the closing gradient. |
| Mint feature | `#d3f6e3` | `--color-feature-mint` | surface | Short capability card, paired with blue and lilac. |
| Lilac feature | `#f1e6ff` | `--color-feature-purple` | surface | Short capability card with a pale inset interface. |
| Cloud band | `#ebf5ff` | `--color-blue-band` | background | Broad typographic interlude band. |
| Lavender air | `#f9f5ff` | `--color-lavender-wash` | background | Gallery field and middle of the pricing atmosphere. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal action | `#181d27` | `--color-action` | action, surface | All marketing conversion buttons; not a full-page dark theme. |
| Headline ink | `#0a0d12` | `--color-ink` | text, border | Headlines, names and the fine dark edge of primary actions. |
| Slate copy | `#535862` | `--color-body` | text, link | Supporting sentences, feature lists and footer links. |
| Soft gray copy | `#93979f` | `--color-muted` | text, link | Navigation, quotations, secondary attribution and billing qualifiers. |
| Navigation edge | `#f4f5f6` | `--color-nav-edge` | border | Subtle one-pixel shadow under the floating navigation. |
| Quote gray | `#f9fafb` | `--color-quote` | surface | Flat testimonial cards. |
| Accordion white | `#fcfcfd` | `--color-faq` | surface | Almost-white question rows. |
| Sky paper | `#fafdff` | `--color-hero` | background | Opening stage and the light end of blue atmospheric transitions. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Base canvas, navigation and pricing cards; reversed action labels and cloud silhouettes. |

## Typography

- **Aeonik** — Headlines, large narrative statements, feature titles, questions and attribution names. Rounded contemporary grotesk with open counters and a friendly medium weight. OpenType features: "case". If unavailable, use **DM Sans**. Use weight 500; preserve the broad counters and restrained tracking. Font stack: "Aeonik", "DM Sans", sans-serif.
- **Geist** — Supporting copy, navigation, buttons, quotations and small labels. Clean neutral sans with compact spacing and a slightly more utilitarian texture than the display face. OpenType features: "case". Font stack: "Geist", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| word-sculpture | Aeonik | 500 | 148px | 156px | normal | size 10.277778vw, line height 10.833333vw | Monumental single-word interlude; keep letters visually together when settled. |
| statement | Aeonik | 500 | 72px | 80px | -0.02em | size 5vw, line height 5.555556vw | Large explanatory sentence with illustrated tokens between phrases. |
| heading | Aeonik | 500 | 48px | 56px | normal | size 3.333333vw, line height 3.888889vw | Default first-screen headline and centered section headings; also the price numeral. |
| card-heading | Aeonik | 500 | 32px | 1.25 | normal | size 2.222222vw | Two-line capability titles inside pastel cards. |
| question | Aeonik | 500 | 24px | 28px | normal | size 1.666667vw | Accordion summaries. |
| quote | Geist | 500 | 20px | 1.4 | -0.01em | size 1.388889vw | Testimonial quotations and expanded question answers. |
| name | Aeonik | 500 | 20px | 1.2 | normal | size 1.388889vw | Person names and the footer tagline. |
| support | Geist | 500 | 18px | 24px | -0.01em | size 1.25vw | One-sentence support below headings and pricing feature lists. |
| button-pricing | Geist | 600 | 18px | 24px | -0.01em | size 1.25vw | Full-width pricing action. |
| small | Geist | 500 | 16px | 1.5 | -0.01em | size 1.111111vw | Navigation, attribution roles and gallery interaction hint. |
| button | Geist | 600 | 16px | 1.5 | -0.01em | size 1.111111vw | Default conversion button. |
| button-small | Geist | 600 | 14px | 16px | -0.01em | size 0.972222vw | Compact navigation conversion action. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the medium-weight display face distinct from the semibold action labels. The hero is deliberately smaller than the explanatory statement and word interlude.
- Body and action tracking is -0.01em; only the 72px statement tightens to -0.02em. Display headings otherwise use normal tracking.
- Sentence case, natural word breaks and centered one- or two-line headings are the default. Illustrations interrupt a sentence without becoming separate labels.
- Viewport scaling applies to the desktop rem-based system. Use readable lower bounds and reflow at narrow widths rather than shrinking all text indefinitely.

## Layout

**Density:** Airy theatrical scenes with sparse centered copy, followed by more compact card-based proof and conversion blocks.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight icon/action and social icon gaps. |
| 12px | Attribution portrait-to-text spacing and statement line separation. |
| 16px | Accordion row gaps and inline word-to-token spacing. |
| 20px | Outer opening inset. |
| 24px | Heading-to-support distance, grid gutters and testimonial row spacing. |
| 32px | Navigation side padding and explanatory lead-to-statement gap. |
| 40px | Support-to-hero-action distance and quote card padding. |
| 48px | Feature card content inset. |
| 56px | Pricing card padding and heading-to-price-card gap. |
| 88px | Feature and testimonial section top padding. |
| 120px | Gallery top padding and FAQ heading-to-list separation. |
| 160px | Deep lower-page section breathing room. |

### Containers and grids

- **scene**: max width 1440px · side padding 20px. Full-width illustrated stages, with an inset only on the opening.
- **navigation**: max width 1002px · side padding 32px. Centered floating capsule; logo and two links on the left, small action on the far right.
- **heading-column**: max width 620px · side padding 28px. Centered section title, normally limited to two lines.
- **feature-grid**: max width 954px · 2 columns · gap 24px · side padding 16px. One 465px-wide tall card beside two equally wide stacked cards; tall card 696px high, short cards 336px high.
- **pricing**: max width 730px · 2 columns · gap 24px · side padding 56px. One horizontal pricing card with cost and action left, inclusions right.
- **faq**: max width 794px · 2 columns · gap 120px · side padding 16px. Small left heading beside a 560px-wide accordion list.

## Corner radius

| Element | Radius |
| --- | --- |
| cards-and-primary-action | 32px |
| opening-top-corners | 24px |
| illustrated-tiles | 24px |
| navigation-action | 16px |
| pricing-action | 36px |
| inline-tokens | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| primary-action | `rgba(10, 13, 18, 0.8) 0px 1px 2px 0px, #0a0d12 0px 0px 0px 1px` | Slight raised edge on the primary dark pill. |
| navigation | `#f4f5f6 0px 1px 1px 0px` | Nearly imperceptible edge beneath the navigation capsule. |
| toy-tile | `rgba(4, 69, 144, 0.08) 0px 14px 20px 4px` | Soft blue-tinted floating shadows below decorative image tiles; not general card shadows. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and proof-section background.

**CSS:** `background: #ffffff`

**Observed:** Large white areas separate illustrated environments.

**Transfer:** Keep text-heavy material on white rather than extending a tint through the entire page.

#### Opening sky · level 0

**Use:** First-screen stage.

**CSS:** `background: #fafdff; border-radius: 24px 24px 0px 0px`

**Observed:** White cloud silhouettes and extremely pale blue air surround the content.

**Transfer:** Use the same light backing behind original flat illustrations.

#### Lavender atmosphere · level 0

**Use:** Gallery and animated explanatory stage.

**CSS:** `background: #f9f5ff`

**Observed:** A flat pale field carries more colorful objects; transitions to adjacent white fields are soft.

**Transfer:** Reserve this field for immersive visual explanations.

#### Pricing atmosphere · level 0

**Use:** Single-plan conversion scene.

**CSS:** `background: linear-gradient(#ffffff, #f9f5ff 51.92%, #ffffff)`

**Observed:** White card floats within a lavender middle, with cloud and sparkle decorations outside it.

**Transfer:** Keep the gradient low contrast and content fully legible.

#### Closing atmosphere · level 0

**Use:** Illustrated curtain-call.

**CSS:** `background: linear-gradient(#ffffff 6.81%, #d6ecff 55.2%, #ffffff)`

**Observed:** A stronger sky band supports a large friendly figure, with white scallops masking the bottom.

**Transfer:** Recreate the light sky and foreground cloud mask even with simpler artwork.

#### Pastel capability card · level 1

**Use:** Feature grouping.

**CSS:** `background: #cce7ff; border-radius: 32px; overflow: hidden`

**Observed:** Blue is the tall variant; lilac and mint are the short variants. No general border or drop shadow.

**Transfer:** Use one pastel per capability and let diagrams extend behind the bottom edge.

#### Soft proof card · level 1

**Use:** Testimonials.

**CSS:** `background: #f9fafb; border-radius: 32px`

**Observed:** Flat and barely separated from white, with no outline.

**Transfer:** Use surface tone and whitespace, not strong shadows, to separate endorsements.

## Components

### Floating navigation

**Use:** Persistent lightweight orientation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; max-width: 1002px; height: 64px; padding: 0px 32px; background: #ffffff; border-radius: 32px; box-shadow: #f4f5f6 0px 1px 1px 0px`

**Text style:** `small` — Geist 500 · 16px/1.5 · tracking -0.01em

**Observed:** A fixed outer wrapper centers the capsule. A dark wordmark leads two muted links; the compact action is right-aligned. Logo-to-links gap is 56px and link gap is 30px.

**Transfer:** Keep only the essential navigation anchors so the capsule retains its sparse silhouette.

### Primary button

**Use:** Opening and closing conversion.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 48px; padding: 12px 32px; gap: 8px; background: #181d27; color: #ffffff; border-radius: 32px; box-shadow: rgba(10, 13, 18, 0.8) 0px 1px 2px 0px, #0a0d12 0px 0px 0px 1px; overflow: hidden`

**Text style:** `button` — Geist 600 · 16px/1.5 · tracking -0.01em

**Observed:** A single text-only pill is centered beneath the support line; no competing secondary hero action.

**Transfer:** Use a short verb-led conversion label.

### Navigation button

**Use:** Compact header conversion.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 32px; padding: 8px 16px; background: #181d27; color: #ffffff; border-radius: 16px; overflow: hidden`

**Text style:** `button-small` — Geist 600 · 14px/16px · tracking -0.01em

**Observed:** Same charcoal silhouette as the main action, reduced without an additional icon.

### Pricing button

**Use:** Conversion within the cost column.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 234px; height: 40px; padding: 8px 24px; background: #181d27; color: #ffffff; border-radius: 36px`

**Text style:** `button-pricing` — Geist 600 · 18px/24px · tracking -0.01em

**Observed:** Fills the left pricing column and sits below the cost qualifier; its label is slightly larger than the hero action.

### Capability card

**Use:** Show a discrete product benefit with a visual demonstration.

**CSS:** `display: flex; flex-direction: column; position: relative; background: #cce7ff; border-radius: 32px; padding: 48px; overflow: hidden`

**Text style:** `card-heading` — Aeonik 500 · 32px/1.25

**Observed:** Title at upper left, diagram below. Tall blue version contains floating rounded image tiles and a folder; short lilac and mint versions contain simplified collaborative or editing interface fragments.

**Transfer:** Show one meaningful operation, not a fully detailed application screen.

### Testimonial card

**Use:** Human proof in a wide moving wall.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; max-width: 465px; height: 320px; padding: 40px; background: #f9fafb; border-radius: 32px`

**Text style:** `quote` — Geist 500 · 20px/1.4 · tracking -0.01em

**Observed:** Muted quote at top; circular portrait, dark name and gray role at bottom left; small organization mark at bottom right. Cards repeat in two staggered edge-clipped rows with 24px gaps.

**Transfer:** Use authentic short quotations and maintain the large separation before attribution.

### Question accordion

**Use:** Low-friction objection handling.

**CSS:** `background: #fcfcfd; border-radius: 32px; max-width: 560px`

**Text style:** `question` — Aeonik 500 · 24px/28px

**Observed:** A semantic summary row is 92px high when closed, with 32px 40px padding, text left and a thin plus at right. An answer uses the quote recipe beneath it. Rows are separated by 16px.

**States:** Declared: hover unknown; focus-visible outline-offset 4px and outline-color rgb(102, 184, 255); active unknown.

**Transfer:** Keep questions practical and sentence case; preserve the plus affordance.

### Single plan card

**Use:** One clear commercial offer.

**CSS:** `display: flex; justify-content: space-between; gap: 24px; padding: 56px; background: #ffffff; border-radius: 32px; max-width: 730px`

**Text style:** `support` — Geist 500 · 18px/24px · tracking -0.01em

**Observed:** Price in the heading recipe, a muted billing qualifier and Pricing button occupy the left. Four short inclusion rows sit right with small blue sparkles instead of checkboxes.

**Transfer:** Adapt the actual terms, not the original cost or allowance.

### Centered footer

**Use:** Final identity and utility beneath the illustration.

**CSS:** `display: flex; justify-content: center; background: #ffffff; padding: 64px 32px 56px`

**Text style:** `small` — Geist 500 · 16px/1.5 · tracking -0.01em

**Observed:** A tiny centered app mark sits above a tagline, followed by copyright, one short legal-link row and three muted social/contact icons. It is not a multi-column sitemap.

**Transfer:** Keep identity vertically stacked and subordinate to the illustrated ending.

### Inline illustration token

**Use:** Replace punctuation-like gaps within a narrative heading.

**CSS:** `display: inline-flex; width: 80px; height: 80px; border-radius: 50%; background: #ffcfb4; position: relative`

**Observed:** Circular pastel backing contains a cheerful pictogram. Blue, mint, purple and yellow variants match the words they accompany; they align with the 80px statement line box.

**Transfer:** Use a small original symbol for each concept; never let the tokens obscure the words.

## Imagery and graphics

### Clouds, sparkles and friendly figures

**Use:** Signature illustration language across opening, explanatory interludes, pricing and ending.

**Observed:** Mostly flat vector art: blue cloud-like smiling characters, peach objects, tiny rounded sparkles and softly shaded white clouds. The hero has a ring of small objects around a clear reading zone and a medium figure beneath the CTA; the ending enlarges a figure to roughly half the page width behind white scallops. Line details are round and minimal, with occasional darker color facets rather than realistic lighting.

**Transfer:** Create a friendly original guide or anthropomorphic product object using the same rounded silhouette language. Minimum version: a simple blue abstract companion, several task-related vector tokens and broad white cloud masks, with no need for complex 3D rendering.

**Build:** Use SVG unions of circles and rounded paths for cloud silhouettes; add two dark curved eyes and a small curved mouth to an original central shape. Layer white cloud silhouettes along the lower corners over a pale blue stage. Scatter rounded four-point star paths in pale blue, lilac and peach at 12px–28px, with no glow. Place peripheral objects at varied scales while protecting the center text area.

### Toy image tiles

**Use:** Product diagrams and image-selection gallery.

**Observed:** Rounded square tiles feel like thick collectible cards: pale tinted rims, white inner frame and colorful artwork. Capability tiles are gently shaded with soft blue shadows; gallery tiles use stronger artwork color, alternating rotations and an arc that runs off both sides. Gallery items are about 190px square; capability tiles vary from 152px to 191px.

**Transfer:** Frame real product outputs, templates or original illustrative samples as collectible objects. When output imagery is unavailable, use finished diagrams or symbols rather than empty rectangles.

**Build:** Make 190px square tiles with 24px corners, a tinted backing and white inset frame. Add a low-opacity white inner edge and rgba(4,69,144,0.08) 0px 14px 20px 4px shadow. Rotate a sequence gently in opposite directions; use -30deg, 5deg and 15deg as the capability tile family. Raise central gallery tiles and lower outer ones to form an arc; clip only at scene edges.

### Product stage

**Use:** A broad product demonstration between conceptual scenes.

**Observed:** A large white desktop application window occupies about three quarters of the width, with softly rounded corners over a blue-white atmospheric field. Sidebar, prompt area and output area are simplified and softly colored; the surrounding stage remains lighter than the interface accents.

**Transfer:** Use an actual coherent product screen or a complete simplified flow, keeping its framing pale and emphasizing one interaction rather than dense UI detail.

### Word sculpture

**Use:** A signature typographic pause between explanations.

**Observed:** Three short words appear as separate 148px statements in spacious 480px bands. White and pale blue alternate; a large scalloped cloud contour intrudes into the middle band, and small round character tokens float nearby. Letters can offset during motion but settle as readable words.

**Transfer:** Use a short original promise, split into emphatic words. Preserve the scale shift and cloud silhouette even if the words are arranged differently.

**Build:** Set live Aeonik text at the word-sculpture recipe in centered 480px-tall blocks. Place a pale blue SVG cloud contour behind one block and small circular pictograms off-axis. Keep settled letters at normal tracking; use independent spans only for the letter motion.

### People and organization marks

**Use:** Testimonial attribution.

**Observed:** Small circular photographic portraits provide a human counterpoint to illustration, paired with names and roles. Small company marks anchor the opposite bottom corner.

**Transfer:** Use real portraits with restrained size and authentic organization marks; keep photography out of the main illustrated hero.

### Icons

**Observed:** Marketing iconography favors rounded four-point sparkles, especially 20px blue bullets in the plan list. Accordion plus signs are thin and gray. Footer social/contact icons are small muted outlines; product diagrams use their own contained symbols.

**Transfer:** Use a consistent simple round-ended symbol family, preserving sparkles as proof-list bullets and thin plus signs for disclosure rather than replacing both with generic filled circles.

## Section recipes

How recurring sections are built.

### First screen: Cloud stage opening

**Observed:** A 900px-tall first screen has a 20px inset pale sky stage with rounded top corners. Floating navigation sits near the top. The centered headline is a two-line 48px/56px medium grotesk sentence, occupying roughly the middle half of the page width and interrupted by overlapping circular illustration tokens. The support line follows with 24px separation and the Primary button follows 40px later. Behind and around it: nearly white sky, large white cloud masses at the lower corners, small blue and peach objects at the sides, and a friendly blue figure centered beneath the action. Navigation, full headline, support, action and the figure all fit within the first 900px; the next explanatory scene is below the fold.

**Transfer:** Keep a clear central promise, illustrated inline concept tokens and a small original companion beneath the CTA. Without specialist artwork, use the SVG construction in Clouds, sparkles and friendly figures. A narrower-purpose page can open with a shorter promise using the same stage and one action.

**Avoid:** Do not replace the peripheral illustration world with a giant interface panel directly under a jumbo headline or move the conversion below the first screen.

**Text style:** `heading` — Aeonik 500 · 48px/56px

### Illustrated explanation

**Observed:** A centered short support line precedes a 72px/80px statement by 32px. Text wraps into multiple centered lines within about 878px, with 80px Inline illustration tokens between concepts and 12px line separation. Sparse clouds sit outside the reading area.

**Transfer:** Turn a small set of product benefits into one flowing statement, with icons for key nouns rather than an ordinary bullet list.

**Text style:** `statement` — Aeonik 500 · 72px/80px · tracking -0.02em

### Immersive operation scene

**Observed:** A lavender full-screen environment has a short central sentence with a large glossy dark action-object embedded inline. Soft lavender squares and white clouds float around it. Later the environment becomes a pale warm output gallery with a compact prompt composer and image samples.

**Transfer:** Explain one operation through a tactile object and a visible result. Keep this look within a product demonstration, not as the default marketing button treatment.

### Arc gallery

**Observed:** A 48px centered two-line heading and 18px supporting sentence sit at the top of Lavender atmosphere with 120px top padding. A broad arc of framed colorful tiles occupies the lower half, rotated and partly offscreen. A 16px interaction hint is centered near the bottom.

**Transfer:** Use the arc for a browsable set of outputs, choices or templates; provide visible labels or touch access alongside the desktop hover behavior.

**Text style:** `heading` — Aeonik 500 · 48px/56px

### Heading pair and capability bento

**Observed:** Heading and one-line support are centered with a 24px gap, above a 954px two-column Capability card grid with 24px gutters. One 696px blue card balances two 336px lilac and mint cards. Titles are 32px/40px and diagrams fill the lower areas.

**Transfer:** Allocate the tall card to the most visual benefit and the short cards to simpler operations; a different number of benefits can use the same size hierarchy.

**Text style:** `card-heading` — Aeonik 500 · 32px/1.25

### Simple offer in an illustrated wash

**Observed:** A centered 48px heading sits above Single plan card with a 56px gap. Pricing atmosphere surrounds the card; sparse clouds and colored sparkles remain outside the content. The numeral is not oversized beyond the main section heading.

**Transfer:** Present a compact offer or equivalent commitment card, keeping terms practical and the illustration subordinate.

**Text style:** `heading` — Aeonik 500 · 48px/56px

### Staggered human proof wall

**Observed:** A centered heading and support precede two staggered rows of Testimonial card. The wall bleeds past both viewport edges and has 24px horizontal and vertical gaps. Quotes are gray, names are dark, portraits and company marks sit low.

**Transfer:** Use enough real proof to sustain the wall; preserve the staggered composition and readable attribution without padding with invented endorsements.

**Text style:** `quote` — Geist 500 · 20px/1.4 · tracking -0.01em

### Side-heading questions

**Observed:** A 794px centered composition places a 48px heading at left and a 560px question stack at right, separated by 120px. Each almost-white rounded row has a plus and 16px separation from the next.

**Transfer:** Use this less symmetrical composition to interrupt the repeated centered title pattern and answer the final practical objections.

**Text style:** `question` — Aeonik 500 · 24px/28px

### Illustrated curtain-call

**Observed:** Closing atmosphere forms an 800px stage with a centered 48px heading, a one-line support and Primary button near its top. A very large friendly blue figure emerges behind white scalloped clouds lower down, visually turning the scene into the white footer. Centered footer follows with a tiny app mark, tagline, copyright, legal links and a small social/contact row.

**Transfer:** End with an original welcoming character or personable product-shaped object peeking over a cloud mask. Keep the final identity stack small so the illustration remains the last memorable image.

**Text style:** `heading` — Aeonik 500 · 48px/56px

## Page flow

**Storyline:** Promise → illustrated explanation → operation and output demonstration → visual punctuation → capability proof → offer → human proof → practical objections → illustrated invitation.

### An immersive product landing page that moves from creative possibility to a simple commitment

1. **Promise** — Cloud-framed headline with inline pictograms, a concise outcome sentence and one dark action.
2. **Explanation** — Large flowing sentence with circular concept tokens, followed by a pale product stage.
3. **Product demonstration** — An immersive action-object scene turns into output samples and a compact composer.
4. **Visual punctuation** — Monumental words and cloud contours reset the pace before a tilted gallery.
5. **Capability proof** — A pastel bento shows focused operations rather than long feature descriptions.
6. **Offer** — One white two-column card presents cost, action and a short inclusion list in lavender air.
7. **Social proof** — Two staggered edge-clipped rows of quotes with people and company attribution.
8. **Objection handling** — Side-heading accordion list answers practical questions.
9. **Closing invitation** — A concise CTA sits over an oversized friendly illustration that transitions into a tiny centered utility footer.

**Transfer:** Borrow the alternation of immersive scenes and practical compact blocks. Choose the order and frequency around the new product's story while retaining illustrated sentences, a word-scale interlude and a character-led ending.

## Writing

Friendly, imaginative and lightly magical without sounding technical or grandiose. Benefits feel easy and collaborative; practical details stay plain and reassuring.

**Do not copy:** Do not reuse Genie branding, its mascot or artwork, product-specific claims, pricing, credit counts, customer names, testimonials or organization marks. Source copy examples illustrate rhythm only.

- **Addressing the reader:** Speak directly to you and your; use we for the helpful product team and name the product naturally when explaining what it does.
- **Rhythm:** Short sentence-case headlines, usually 3–9 words, balanced against occasional longer explanatory statements. Supporting copy is normally one sentence; fragments and contractions keep it conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Tell the audience which frustrating starting point they can leave behind. | 7–10 words | “Teams don’t have to start from scratch” |
| Supporting sentence | Name the concrete outcome, not the underlying technology. | 6–11 words | “Get visuals true to your brand identity.”<br>“Start with style. Not a blank canvas.” |
| Capability title | Lead with an active verb and an everyday convenience. | 5–8 words | “Create collections on the fly”<br>“Collaborate with team members” |
| Playful reassurance | Combine simple actions with one small imaginative flourish. | 7–10 words | “Just tap, tweak, and poof, it’s done.”<br>“Bring the idea. We’ll bring the sparkles” |
| Primary action | Use an unembellished two-word action even when the surrounding prose is playful. | 2 words | “Sign up” |
| Practical answer | Answer first, then add a short reassurance in plain language. | 1–3 short sentences | “Definitely. [Brand] works great solo or with a team. Everyone stays on-brand.” |

**Words and phrasing to use:** your; create; bring; style; tap; tweak; on the fly; friendly; idea; a restrained magical metaphor

**Avoid:** revolutionary; enterprise-grade ecosystem; unprecedented; leverage; disrupt; technical model jargon in the hero

**Rules:**

- Let the heading promise relief or possibility; let the support sentence specify the outcome.
- Use playful language at major transitions, not in every control or billing term.
- Keep questions concrete: collaboration, exports, trial and cancellation are practical topic models.
- Keep feature titles brief enough to form two comfortable lines.

## Do's and Don'ts

### Do

- Keep the default heading at 48px/56px medium weight while reserving 72px/80px for the explanatory statement.
- Pair a 24px heading-to-support gap with 40px before the primary hero action.
- Keep the 48px hero action charcoal and compact instead of stretching it across the content column.
- Use 32px corners on flat capability and proof cards, with 24px gutters.
- Let original pictograms occupy 80px circular tokens within the large narrative statement.
- Use soft blue-tinted shadows only on floating toy tiles and a fine dark edge on primary actions.
- Make the feature grid 954px wide with a tall-to-stacked size relationship.
- Keep footer identity small and centered below the oversized illustrated ending.

### Don't

- Do not turn the page into a dark theme; charcoal is concentrated in text and actions.
- Do not use bright blue as the default button fill; the marketing actions use #181d27.
- Do not put gradients in heading letters; headline color remains #0a0d12.
- Do not apply a 148px headline throughout; that scale is a punctuation device, not the normal hierarchy.
- Do not add heavy outlines and shadows to every card; proof cards are flat #f9fafb.
- Do not replace the tilted collectible gallery with a dense edge-to-edge thumbnail table.
- Do not introduce a serif or monospace marketing voice; the contrast is between two sans families.
- Do not expand the footer into a dark multi-column directory; it is a centered white identity stack.

## Motion and responsive

### Motion

**Observed:**

- The illustrated narrative uses pinned stages and individually transformed words or tokens.
- Floating capability tiles declare transform, top, right and left transitions of 1.2s ease; the purple and peach tiles have 0.3s and 0.5s delays respectively. A smaller tile adjustment declares 0.3s ease.
- Navigation declares transform 0.4s. Testimonial rows use marquee structures; typing and spin keyframes also exist.

**Transfer:**

- Animate toy objects as a family with staggered settling rather than giving every text block the same reveal.
- Keep the final word formations readable; the scattered letter configuration is a transition, not the resting layout.
- For reduced motion, present the settled illustrated compositions and readable proof rows without pinning.

**Unknown:**

- Exact scroll choreography, marquee duration, full canvas animation timing and button hover behavior are not established.

### Responsive

**Observed:**

- The root rem basis follows 0.694444vw, making desktop rem-based values proportional to viewport width.
- CSS width breakpoints include 424px, 425px, 500px, 501px, 767px, 768px, 769px, 919px and 1441px.
- Some large scenes and navigation elements have separate desktop/tablet variants.

**Transfer:**

- On narrow screens, reflow illustrated sentences so tokens stay attached to the associated words; retain the cloud stage rather than scaling a full desktop canvas into unreadability.
- Stack the capability cards, the pricing columns and the FAQ heading/list as necessary while preserving 24px family gutters and generous rounded corners.
- Use a compact static or lightly animated original companion when the full illustration environment cannot fit. Keep the centered curtain-call and footer identity.

**Unknown:**

- Exact mobile layouts, font lower bounds, navigation replacement and touch gallery behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
