# Lóvi — clinical care, pearlescent warmth

## Overview

A bright, personal style that makes technical assistance feel like a caring conversation. Black, tightly set grotesk headlines sit on white and pale lavender-gray, with soft violet and pink light around human photography and floating interface fragments. The composition is spacious at section level but compact inside rounded cards, suited to consumer tools that need to balance expertise with emotional reassurance.

### Essentials

- Headlines feel spoken rather than institutional: regular grotesk at 48px/44px with -2px tracking in the opening, then 44px/40px with -1px tracking for major sections.
- The opening pairs a small centered promise with an oversized human-and-product scene: a 36px-high proof pill, a three-line headline, 24px to the support line, and a translucent device rising into the lower half of the first screen.
- White objects float in a near-white world: #ffffff cards on #f6f6fa, 40px corners, faint #f6f5f4 edges, and tightly joined 6px card gutters; saturated blue is reserved for small conversational prompts rather than page-sized bands.
- Conversion is restrained and tactile: a compact black 122×47px download badge in the fixed header, 16px-radius secondary buttons, and broad 295×88px white choices with 24px corners.
- Technical proof becomes a friendly conversation: staggered white 24px-radius bubbles, 24px/30px medium text, and a round luminous assistant avatar; retain the conversational demonstration even when the product is not a chat tool.
- Soft light bridges rational and emotional content: include low-contrast lavender-pink halos around an interaction and a rounded photographic closing panel with pearlescent haze and a white 44px message. Without bespoke media, use a real product-in-use photo, translucent interface frame, and blurred radial color fields.
- The ending remains editorial rather than corporate: a left-aligned, heading-sized sentence of social links with inline platform symbols, a small black action beneath, and a low-contrast legal baseline separated by substantial breathing room.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversation blue | `#5163ff` | `--color-blue` | surface, accent | Small, high-emphasis conversational prompts. Keep the surrounding page neutral. |
| Prompt blue | `#5263ff` | `--color-blue-text` | text | Text in pale-blue suggestion chips. |
| Suggestion wash | `#eeefff` | `--color-blue-wash` | surface | Visible tint of rgba(81,99,255,0.1) over white for question suggestions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline black | `#000000` | `--color-ink` | text, action | Headlines, navigation mark, social symbols and the black conversion badge. |
| Warm charcoal | `#292824` | `--color-text` | text | Conversation text, short labels and portrait names. |
| Soft caption gray | `#a9a9a7` | `--color-muted` | text | Secondary portrait credentials; rgba(41,40,36,0.4) over white produces this visible tone. |
| Warm porcelain | `#f6f5f4` | `--color-edge` | surface, border | Faint card outlines and neutral portrait backing. |
| Lavender gray | `#f6f6fa` | `--color-canvas` | background, surface | Main lower-page field and secondary button fill. |
| White | `#ffffff` | `--color-white` | background, surface, text | Opening canvas, cards, bubbles and reverse text over photography or blue prompts. |

## Typography

- **ES Rebond Grotesque** — All marketing headlines, FAQ questions and feature captions. Rounded, approachable grotesk with broad circular forms; regular display weight and a slightly firmer medium caption cut. If unavailable, use **DM Sans**. Use 400 for headings and 500 for captions; retain tight tracking and compact line breaks. Font stack: "ES Rebond Grotesque", "DM Sans", Arial, sans-serif.
- **Inter** — Conversation text, proof pill and portrait metadata. Compact neutral sans with clear small text; medium weight is used for conversational emphasis. Font stack: "Inter", Arial, sans-serif.
- **Geist** — Opening support line and explanatory secondary action. Clean contemporary sans, quieter and smaller than the rounded display face. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ES Rebond Grotesque | 400 | 48px | 44px | -0.0417em | Centered opening promise; composed as a compact three-line statement. |
| heading | ES Rebond Grotesque | 400 | 44px | 40px | -0.0227em, features "ss02" | Major section titles, question-led conversion and white closing statement. |
| manifesto | ES Rebond Grotesque | 400 | 44px | 46px | -0.0227em | Long-form introductory statement; more open line spacing than short section headings. |
| question | ES Rebond Grotesque | 400 | 28px | 32px | -0.0357em | FAQ row labels. |
| conversation | Inter | 500 | 24px | 1.25 | -0.0417em | Demonstration messages and short assistant answers. |
| feature-caption | ES Rebond Grotesque | 500 | 22px | 24px | -0.0455em | Centered benefit captions beneath feature art and broad choice labels. |
| support | Geist | 400 | 18px | 22px | -0.028em, features "dlig", "ss01", "ss02", "ss06" | Single-line opening support. |
| body | Inter | 400 | 16px | 22px | -0.04em | Portrait names and supporting credentials; distinguish hierarchy by color. |
| secondary-action | Geist | 400 | 16px | 22px | -0.031em | Explanatory read-more button. |
| proof-label | Inter | 500 | 16px | 1.25 | -0.0625em | Small proof announcement above the opening headline. |
| suggestion | Inter | 500 | 16px | 1.25 | -0.031em | Pale blue question chips. |

**Notes:**

- Keep display headings regular rather than bold; emphasis comes from line breaks, density and surrounding space.
- The 44px heading uses unusually tight 40px leading; only the longer manifesto opens to 46px.
- Medium captions use the medium font cut even though it is declared as a separate family; treat it as visual weight 500.
- Use sentence case and mixed-case questions. Do not introduce an uppercase eyebrow system.

## Layout

**Density:** Airy between chapters, closely fitted within feature mosaics and conversation objects.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Narrow joins between large feature cards. |
| 8px | Suggestion stacks and small repeated elements. |
| 10px | Gap between paired broad choices and between avatar and message. |
| 12px | Chip padding and caption-to-secondary-action gap. |
| 16px | Proof pill to headline and message vertical padding. |
| 24px | Opening headline to supporting line. |
| 32px | Conversation row separation and portrait padding. |
| 40px | FAQ and closing-panel padding. |
| 48px | Feature card side padding and media-to-caption space. |
| 64px | Feature-chapter vertical padding and title-to-conversation separation. |
| 120px | Major chapter padding and the inset from outer frame to inner content. |
| 200px | Extended lead-in to a conversation or social-proof chapter. |

### Containers and grids

- **outer-frame**: max width 1200px. Centered desktop frame; at 1440px it leaves 120px on each side.
- **feature-stage**: max width 960px. Inner centered stage for feature mosaics, proof carousel, FAQ and closing photograph.
- **feature-grid**: 2 columns · gap 6px. One full-width hero feature above a pair of nearly equal half-width cards.
- **conversation-stage**: max width 780px · gap 32px. Alternating left and right message groups with avatars outside the bubbles.
- **choice-pair**: max width 600px · 2 columns · gap 10px. Two equal choices below a compact centered question.

## Corner radius

| Element | Radius |
| --- | --- |
| feature cards | 40px |
| portrait cards | 48px |
| proof enclosure | 64px |
| messages and choices | 24px |
| secondary buttons | 16px |
| download badge | 12px |
| proof pill | 56px |
| assistant avatar | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| message | `rgba(36, 36, 41, 0.07) 0px 9px 34px 0px, rgba(37, 36, 41, 0.09) 0px 1px 2px 0px` | Floating white conversation bubbles. |
| announcement | `rgba(0, 0, 0, 0.1) 0px 5px 20px 0px, rgba(0, 0, 0, 0.13) 0px 1px 1px 0px` | Small proof announcement above the opening. |

### Surfaces

#### Light canvas · level 0

**Use:** Neutral page ground.

**CSS:** `background: #f6f6fa`

**Observed:** The opening is pure white; the long body becomes a subtly lavender-gray field.

**Transfer:** Keep the top luminous white and allow the soft gray to distinguish white content objects later.

#### Porcelain card · level 1

**Use:** Primary feature, FAQ and proof objects.

**CSS:** `background: #ffffff; border: 1px solid #f6f5f4; border-radius: 40px`

**Observed:** Large, almost borderless modules rely on their silhouette rather than heavy shadow.

**Transfer:** Use one consistent surface for marketing content instead of creating a new fill for each capability.

#### Portrait backing · level 1

**Use:** Human authority cards.

**CSS:** `background: #f6f5f4; border-radius: 48px; overflow: hidden`

**Observed:** Bright, cutout-like portraits merge into pale backing and fade to white at the text baseline.

**Transfer:** Choose high-key portraits and preserve the lower white fade.

#### Pearlescent interaction field · level 0

**Use:** Atmosphere behind a question or conversation.

**CSS:** `background: radial-gradient(ellipse at 35% 68%, rgba(206,162,255,0.12), rgba(206,162,255,0) 38%), radial-gradient(ellipse at 72% 50%, rgba(255,133,177,0.1), rgba(255,133,177,0) 38%), #f6f6fa`

**Observed:** Diffuse lilac and blush halos appear beneath and around white interaction objects, with no hard edge.

**Transfer:** Match the soft glow; exact stops are not essential. Keep the light behind, never over, dark text.

## Components

### Fixed navigation

**Use:** Persistent brand and conversion anchors.

**CSS:** `position: fixed; display: flex; justify-content: space-between; align-items: center; max-width: 1200px; padding: 32px 48px 12px; height: 91px`

**Observed:** Only a black brand mark on the left and a compact black download badge on the right; a progressive background blur sits behind them. No central menu competes with the page.

**Transfer:** Use the new product mark and one primary destination.

### Download badge

**Use:** Primary conversion in the header and again beneath the closing social invitation.

**CSS:** `width: 122px; height: 47px; border-radius: 12px; overflow: hidden; background: #000000; color: #ffffff`

**Observed:** A compact image-based marketplace lockup with white symbol and two-line wording, not a large pill CTA.

**Transfer:** Use a legitimate marketplace badge when relevant; otherwise a compact black branded action in the same footprint.

### Proof pill

**Use:** Brief announcement directly above the opening promise.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 7px; height: 36px; padding: 6px 12px 6px 10px; border-radius: 56px; background: rgba(255,255,255,0.2); color: #292824; box-shadow: rgba(0, 0, 0, 0.1) 0px 5px 20px 0px, rgba(0, 0, 0, 0.13) 0px 1px 1px 0px`

**Text style:** `proof-label` — Inter 500 · 16px/1.25 · tracking -0.0625em

**Observed:** Tiny emblem precedes one compact announcement; small circular details at the trailing edge make it feel like a thought bubble.

**Transfer:** Use one supportable distinction or timely update.

### Secondary button

**Use:** Read-more action beneath a feature caption.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #f6f6fa; color: #000000; padding: 18px 20px; height: 58px; border-radius: 16px`

**Text style:** `secondary-action` — Geist 400 · 16px/22px · tracking -0.031em

**Observed:** A quiet filled rectangle, centered under the caption, with no decorative arrow.

### Feature card

**Use:** Visual benefit modules.

**CSS:** `background: #ffffff; border-radius: 40px; padding: 40px 48px 48px; display: flex; flex-direction: column; justify-content: space-between; align-items: center`

**Text style:** `feature-caption` — ES Rebond Grotesque 500 · 22px/24px · tracking -0.0455em

**Observed:** Large device or UI scene occupies most of the module; the centered benefit caption is anchored near its lower edge. Wide modules sit above paired smaller cards.

**Transfer:** Demonstrate a specific outcome rather than placing generic icons above prose.

### Conversation bubble

**Use:** Friendly product demonstration.

**CSS:** `background: #ffffff; color: #292824; border-radius: 24px; padding: 16px 14px; max-width: 410px; box-shadow: rgba(36, 36, 41, 0.07) 0px 9px 34px 0px, rgba(37, 36, 41, 0.09) 0px 1px 2px 0px`

**Text style:** `conversation` — Inter 500 · 24px/1.25 · tracking -0.0417em

**Observed:** White messages alternate across the stage, with small round tail details and an 88px avatar outside the bubble. Some answers expand into a row of recommendation cards.

**Transfer:** Write a short real user question and an equally practical answer.

### Suggestion chip

**Use:** Sample questions inside a feature demonstration.

**CSS:** `background: rgba(81,99,255,0.1); color: #5263ff; border-radius: 23px; padding: 12px; display: flex; align-items: center; gap: 8px`

**Text style:** `suggestion` — Inter 500 · 16px/1.25 · tracking -0.031em

**Observed:** Several short questions stack as rounded, pale blue speech fragments; each has a tiny trailing bubble detail.

### Choice button

**Use:** Two-way reflective conversion question.

**CSS:** `background: #ffffff; color: #000000; border-radius: 24px; padding: 32px 28px; width: 295px; height: 88px; display: flex; align-items: center; justify-content: center`

**Text style:** `feature-caption` — ES Rebond Grotesque 500 · 22px/24px · tracking -0.0455em

**Observed:** Equal white choices sit side by side on a diffuse pastel field; neither receives a saturated fill.

**Transfer:** Offer a low-pressure entry point with two equally clear responses.

### Authority card

**Use:** Human expertise proof.

**CSS:** `background: #f6f5f4; border-radius: 48px; padding: 32px; display: flex; flex-direction: column; justify-content: flex-end; gap: 32px; overflow: hidden`

**Text style:** `body` — Inter 400 · 16px/22px · tracking -0.04em

**Observed:** A large bright portrait dominates, fading into white above a dark name and pale credentials. Cards form a horizontally clipped carousel with a circular next control.

**Transfer:** Use people with relevant expertise and concise factual credentials.

### FAQ panel

**Use:** Compact objection handling.

**CSS:** `background: #ffffff; border: 1px solid #f6f5f4; border-radius: 40px; padding: 40px; max-width: 960px`

**Text style:** `question` — ES Rebond Grotesque 400 · 28px/32px · tracking -0.0357em

**Observed:** The section title occupies a narrow left column; four question rows sit in a 600px right column with hairline separators and plus icons at the far edge.

**Transfer:** Use short concerns about trust, suitability and operation; keep the collapsed state visually spare.

### Blue conversation prompt

**Only for:** conversational demonstrations

**Use:** High-emphasis continuation inside the conversational demonstration.

**CSS:** `background: #5163ff; color: #ffffff; border-radius: 68px; padding: 20px 20px 20px 28px; height: 92px; display: flex; align-items: center; justify-content: center; gap: 12px`

**Text style:** `conversation` — Inter 500 · 24px/1.25 · tracking -0.0417em

**Observed:** A white circular arrow sits at the right of the phrase. This blue treatment belongs to the conversation, not every marketing action.

## Imagery and graphics

### Human product stage

**Use:** Opening signature scene.

**Observed:** A large, natural close portrait on white is overlaid with a translucent silver-edged phone. The face remains visible through the device; a dark camera capsule, white interface lettering and a thin scan line make the technology legible. The scene extends well below the first fold.

**Transfer:** Pair a high-key photograph of the product's human context with a glass-like device or interface frame. Minimum version: one excellent photo plus a translucent rounded UI panel with a small authentic task state.

**Build:** Center a portrait with its background removed or masked into white. Overlay a tall rounded rectangle about one third of the viewport width, with a translucent white fill, a fine bright inner edge and a soft gray outer edge. Add a dark camera capsule when a phone is relevant; keep real UI sparse. Use a white-to-transparent mask to merge the outer image edges into the page.

### Floating product evidence

**Use:** Feature cards and conversation recommendations.

**Observed:** Phone mockups, cosmetic pack shots, ingredient tags, small graphs and recommendation cards are layered on white. Device frames carry soft realistic shadows while tiny colored statuses remain confined to the demonstration.

**Transfer:** Show the new product's actual outputs as isolated objects with pale backing. If no polished mockups exist, compose a few legible UI panels rather than inventing complex decorative charts.

### Pearlescent light

**Use:** Signature atmosphere around assistant interactions and the closing image.

**Observed:** Very soft lavender, pink and cool blue glows dissolve into near-white. The final portrait carries a more visible pink-lilac reflective veil with fine grain, while the question field is barely tinted.

**Transfer:** Retain both a faint interaction halo and a richer image-local light treatment; color belongs around objects, not in body-text backgrounds.

**Build:** For the interaction, layer two or three 250–400px radial ellipses behind the controls, using lilac rgba(206,162,255,0.12), pink rgba(255,133,177,0.1) and cool blue rgba(102,127,255,0.08), with 60–100px blur. For a closing photo, lay broad translucent pink and lilac gradients over the right side and a pale diagonal light band across the center; add a low-opacity SVG turbulence texture clipped to the panel.

### Expert portrait carousel

**Use:** Human authority proof.

**Observed:** Front-facing waist-up portraits in bright neutral clothing on pale gray-beige grounds. Large heads and shoulders fill 48px-rounded cards; a white gradient fades the lower torso behind restrained name and credential text.

**Transfer:** Use consistent, natural portraits with comparable scale and light; keep credentials readable in the white fade.

### Emotional closing photograph

**Use:** Large closing brand statement before the editorial footer.

**Observed:** A tightly framed, natural face fills a 960px-wide, 760px-high rounded panel. Fine skin texture remains visible under pink and lavender haze; a short white heading sits at the lower left with 40px inset.

**Transfer:** Use an intimate, believable image of the human outcome of the product. For non-personal products, use a close tactile detail of use rather than a generic smiling office scene.

### Icons

**Observed:** Mostly filled black SVG symbols; common standalone sizes are 32–34px, with smaller 17–24px status symbols in product art. FAQ rows use simple plus marks, carousel navigation uses a white chevron, and footer platform symbols sit inline with the sentence.

**Transfer:** Favor simple solid silhouettes and recognizable platform marks. Keep functional plus and chevron shapes understated; reserve colored symbols for product proof.

## Section recipes

How recurring sections are built.

### First screen: Human product stage opening

**Observed:** A minimal fixed navigation sits above a white, centered composition. The proof pill begins 120px down; its 36px height is followed by a 16px gap to the compact three-line 48px/44px promise and a 24px gap to the 18px support line. The text wrapper is 659px wide, but the visible lettering forms a narrower central column. Beneath a broad white breathing zone, an oversized portrait and translucent device rise from the lower half of the first screen; roughly the upper face and device are visible within 900px while the full scene and subsequent demonstration continue below. Layers are white ground, human photograph, translucent phone/interface, then white UI markings. The black download action stays in the header rather than forming a large hero button row.

**Transfer:** Keep a concise centered promise over a large human-context object. Without custom 3D or video, use the Human product stage recipe with a still photo and translucent interface frame. A focused feature page can use the same centered title and one relevant scene with a shorter continuation.

**Avoid:** Do not convert this into a left-text/right-dashboard split, a full-bleed gradient hero or an oversized colored CTA stack.

**Text style:** `display` — ES Rebond Grotesque 400 · 48px/44px · tracking -0.0417em

### Introductory statement

**Observed:** A broad 1200px frame gives a long 44px/46px statement its own 790px-tall chapter, with 120px vertical padding and a slight left inset.

**Transfer:** Use a concise explanatory passage to connect the opening promise to the coming capabilities; retain display-sized prose rather than a small body paragraph.

**Text style:** `manifesto` — ES Rebond Grotesque 400 · 44px/46px · tracking -0.0227em

### Feature mosaic

**Observed:** A 960px-wide Feature card spans the stage, followed by two half-width modules separated by 6px. White art-led cards on the Light canvas use 40px corners; device scenes dominate, with short centered captions near the bottom and occasional Secondary button beneath. Chapters use 64px or 120px vertical padding.

**Transfer:** Group related capabilities into one big demonstration and smaller supporting outcomes. Keep technical labels inside the art and marketing captions outside its details.

**Text style:** `feature-caption` — ES Rebond Grotesque 500 · 22px/24px · tracking -0.0455em

### Conversation chapter

**Observed:** A centered two-line heading introduces a 780px stage of staggered Conversation bubbles with 32px row gaps. Assistant messages align left with luminous circular avatars; user questions align right. White answer cards can broaden into a three-card recommendation row. Blue conversation prompts finish the exchange.

**Transfer:** Demonstrate the product through a realistic question, useful answer and tangible output even when the underlying product is not a chatbot.

**Text style:** `heading` — ES Rebond Grotesque 400 · 44px/40px · tracking -0.0227em

### Social and expert proof

**Observed:** A centered 44px heading leads a horizontally clipped row of white review cards on pale lavender-gray, with edge fades. A separate white 960px enclosure with 64px outer corners holds another centered heading and the Expert portrait carousel. Two full portraits and part of the next are visible; a circular next arrow overlays the right edge.

**Transfer:** Use authentic customer evidence followed by named authority when relevant. Preserve the distinction between compact written proof and image-led human proof.

**Text style:** `heading` — ES Rebond Grotesque 400 · 44px/40px · tracking -0.0227em

### Reflective choice

**Observed:** An airy 900px-high chapter centers a three-line question over two Choice buttons in a 600px pair. Faint pearlescent light sits behind the buttons, leaving most of the field near-white.

**Transfer:** Turn a meaningful self-assessment into a gentle conversion entry. Keep choices equally weighted and use product-appropriate questions.

**Text style:** `heading` — ES Rebond Grotesque 400 · 44px/40px · tracking -0.0227em

### Objection panel

**Observed:** The FAQ panel uses a left title and a wider right stack of four collapsed questions. The 960px white module has 40px padding and sits almost flush above the closing photograph.

**Transfer:** Answer the last few practical concerns in a compact object rather than a long document-like section.

**Text style:** `question` — ES Rebond Grotesque 400 · 28px/32px · tracking -0.0357em

### Photographic close and editorial footer

**Observed:** An intimate, pearlescent photographic panel with 40px corners carries a white 44px/40px statement at its lower left. Below it, a left-aligned black invitation to read and follow wraps over several heading-sized lines, with inline social symbols. The Download badge sits beneath. A very low-contrast single legal row and a short location sign-off anchor the bottom after a broad empty interval.

**Transfer:** End with an emotional image and an editorial invitation, not another feature grid. Use a short sentence linking the new brand's genuine channels, a compact primary action and a subdued legal baseline.

**Text style:** `heading` — ES Rebond Grotesque 400 · 44px/40px · tracking -0.0227em

## Page flow

**Storyline:** Personal promise → human product demonstration → explanatory statement → capability scenes → conversational proof → social and expert trust → reflective action → objections → emotional close and editorial invitation.

### Introduce a personal technology product while making its competence and care tangible

1. **Promise** — Compact centered headline and proof pill above a luminous human-and-device scene.
2. **Product framing** — A display-sized explanatory statement connects the benefit to practical use.
3. **Capability chapters** — Repeated large-and-paired white feature mosaics show real outcomes, devices and small evidence fragments.
4. **Product demonstration** — An alternating conversation makes the assistance feel immediate and specific.
5. **Social proof** — Clipped customer review strip and a separate bright portrait carousel establish lived experience and expertise.
6. **Closing call** — A large personal question with two broad white responses.
7. **Objection handling** — A compact split-column FAQ panel resolves trust and suitability concerns.
8. **Emotional close** — A grainy pearlescent photograph and short white promise lead into sentence-like social links, a small conversion badge and quiet legal baseline.

**Transfer:** Adapt the amount and order of proof to the product. Preserve the intimate opening, conversational demonstration, restrained card system, pastel light and image-led ending without requiring the same number of chapters.

## Writing

Warm, direct and gently expert. Technical confidence is paired with personal reassurance and concrete everyday usefulness, not intimidating institutional language.

**Do not copy:** Do not reuse Lóvi names, logos, award wording, SkinID, Fit Score, medical credentials, examination claims, customer reviews or source statistics. New claims and endorsements must be independently true for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to you and your situation. The product can introduce itself in the first person inside a demonstration; general marketing copy stays benefit-led.
- **Rhythm:** Short sentence-case headlines, often split into two or three compact lines. Feature captions are brief verb-led promises; conversational copy uses ordinary questions and concise replies.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Credible basis + product role + personal reassurance. | 7–10 words | “Science-backed AI Cosmetologist you can trust” |
| Supporting line | A single reader-centered reassurance, not a feature inventory. | 6–9 words | “Focused around you and your beauty” |
| Feature caption | Start with an active verb and name a concrete outcome. | 5–10 words | “Scan your face to see it in its full glory”<br>“Find better-fit-to-you alternatives” |
| Explanatory action | A quiet invitation naming what the reader will learn. | 5–8 words | “Read more about [Brand] Fit Score” |
| Conversational prompt | A practical first-person question. | 5–9 words | “How can I improve my evening routine?”<br>“What else could you suggest?” |
| Reflective call | Ask about the reader's current experience; offer plain short responses. | 9–14 words | “So, do you love the current state of your skin?” |
| Closing promise | Connect functional care to an emotional feeling. | 9–13 words | “[Brand] is a skin care that feels like self care” |

**Words and phrasing to use:** you; your; trust; personalized; best-fit; help; see; check; track; feel; backed by

**Avoid:** revolutionary disruption; dominate; unlock limitless potential; enterprise-grade synergy; miracle; flawless perfection

**Rules:**

- Pair each benefit with an understandable demonstration rather than piling up adjectives.
- Make expertise specific and supportable, then translate it into a reader benefit.
- Let questions create warmth; keep answers useful rather than promotional.
- Keep choice labels plain and equal in tone.

## Do's and Don'ts

### Do

- Set the main promise at 48px/44px and -2px tracking with regular weight.
- Keep major section headings at 44px/40px and allow compact multiline wrapping.
- Center the 960px inner stage within the 1200px outer frame.
- Use 40px corners for main white modules and 6px joins in feature mosaics.
- Keep conversation messages at 24px/30px with 24px-rounded white surfaces.
- Include a faint lilac-pink interaction glow and a richer image-local pearlescent closing treatment.
- Use small black conversion badges and quiet 16px-radius explanatory buttons.
- Make portraits large, bright and naturally textured, fading the lower image into the text backing.

### Don't

- Do not replace regular display type with a heavy 700-weight headline system.
- Do not make every button a 9999px pill; preserve the 12px, 16px and 24px action shapes by role.
- Do not turn #5163ff into a full-width marketing background; it belongs to small conversational emphasis.
- Do not add hard dark card outlines where #f6f5f4 hairlines suffice.
- Do not give all feature cards heavy floating shadows; depth is strongest on messages and device objects.
- Do not shrink the conversation into tiny dashboard text; its 24px dialogue is part of the marketing story.
- Do not flatten the closing image into an untextured stock banner; preserve intimate framing and soft light.
- Do not turn the footer into a dense multi-column sitemap; keep its principal links in a large editorial sentence.

## Motion and responsive

### Motion

**Observed:**

- A progressive fixed-header blur is built from masked layers with blur values rising from 0.1px to 8px.
- Product demonstrations use video elements and the page includes horizontally clipped review and portrait strips.
- No action transitions or animation keyframes are established.

**Transfer:**

- Keep the white header visually light while preserving legibility over scrolling photographs.
- A still scene must retain the same layered portrait, translucent interface and luminous composition as a moving demonstration.

**Unknown:**

- Exact video sequencing, scroll choreography, carousel timing, hover feedback and easing duration are not established.

### Responsive

**Observed:**

- Styles declare width boundaries at 810px and 1200px; desktop composition uses 1200px and 960px maximum-width frames.

**Transfer:**

- On narrower screens, preserve the centered promise and human-interface overlap before reducing decorative details.
- Stack the two-column mosaic and broad choices when needed, retaining their rounded white silhouettes.
- Let the portrait and review strips remain horizontally browsable; move the FAQ title above its rows. These are adaptation rules rather than fixed mobile measurements.

**Unknown:**

- Narrow-screen font sizes, exact mobile padding and device-scene scaling are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
