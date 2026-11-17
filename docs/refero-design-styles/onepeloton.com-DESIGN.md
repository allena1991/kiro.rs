# Peloton — human energy, engineered ease

## Overview

An inviting performance-led style that pairs cinematic human movement with clean, carefully staged products. Cool off-white and charcoal frame natural skin tones, warm interiors and restrained photographic color; the typography is an approachable sans grotesk. The overall density is airy and consumer-friendly, with compact shopping controls and a more practical, information-rich ending. It suits premium connected products and services that need to make sophisticated technology feel personal.

### Essentials

- Human action is the main opening object: a full-width 852px media stage under a 72px charcoal navigation bar, with centered white 48px/1.3 semibold type and a 26px supporting line.
- Headlines encourage rather than shout: Inter 600, sentence case, -0.2px tracking, with 36px section leads and 32px feature leads rather than oversized condensed capitals.
- Conversion controls feel like smooth equipment handles: 56px white hero pills with 28px corners and 2px borders; the dark product-stage action is 48px tall with 24px corners.
- Color belongs chiefly to people and places: most editorial content sits on #f5f7f9 or #ffffff, punctuated by full-width #181a1d bands; there is no recurring saturated marketing fill.
- Alternate the living scene with the isolated object: show authentic activity in warm or softly tinted rooms, then a crisp dark product on an almost-white studio floor with a soft contact shadow. For an intangible product, use a legible interface or physical output in that same neutral staging.
- Make exploration tangible through a rounded image-led rail: compact 207px-wide product tiles use 18px corners and 16px gaps, while larger portrait or activity rails reveal the next item at the edge. Include an equivalent browseable family of outcomes or uses even when there is only one product.
- Finish the persuasion with practical reassurance, not visual fireworks: a charcoal band uses centered 18px labels over 16px muted explanations, followed by an open white service footer and a cool-gray utility strip.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#181a1d` | `--color-ink` | text, background, action, border | Primary text, sticky navigation, reassurance bands and dark buttons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pure black | `#000000` | `--color-black` | text | High-contrast FAQ questions and selected product labels. |
| Secondary charcoal | `#222529` | `--color-press-charcoal` | text, background | Footer group labels; a slightly lifted charcoal band for institutional press calls. |
| Secondary gray | `#65666a` | `--color-muted` | text, link, action | Support paragraphs and secondary links; dark-button hover fill. |
| Field and accordion edge | `#888b93` | `--color-edge` | border | Thin input outlines and FAQ row separators. |
| Reverse secondary gray | `#a8acb1` | `--color-reverse-muted` | text | Support text on charcoal reassurance bands. |
| Control gray | `#e4e6e7` | `--color-control-track` | surface, border | Segmented-control track and understated dividers. |
| Cool off-white | `#f5f7f9` | `--color-canvas` | background, surface | Default long-form marketing canvas, active segmented-control thumb and utility footer strip. |
| Clean white | `#ffffff` | `--color-white` | text, background, surface, action, border | Cards, service sections, hero buttons, and reverse text on photography or charcoal. |

## Typography

- **Inter** — All marketing headings, paragraphs, controls and service text. A practical contemporary grotesk with open counters; semibold headings feel friendly rather than monumental. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 600 | 48px | 1.3 | -0.0042em | Centered media-led opening and major community statement. |
| heading-lg | Inter | 600 | 36px | 1.3 | -0.0056em | Centered section leads and closing invitation. |
| heading | Inter | 600 | 32px | 1.3 | -0.0063em | Product-stage headings, left-aligned split-section leads and product-offer names. |
| statement | Inter | 600 | 26px | 1.3 | -0.0077em | Hero support line, lineup title and large testimonial quotation. |
| label | Inter | 500 | 18px | 1.3 | normal | Navigation, compact product labels and reassurance titles. |
| body | Inter | 400 | 16px | 1.5 | normal | Supporting copy, descriptions and prices. |
| action | Inter | 500 | 16px | 1.3 | normal | Default hero and product-stage buttons; also small editorial-card titles. |
| reassurance-body | Inter | 400 | 16px | 1.5 | 0.025em | Centered explanations in reassurance columns. |
| field-label | Inter | 400 | 14px | 1.5 | 0.025em | Email field label. |
| footer-heading | Inter | 400 | 14px | 1.714 | normal | Service-footer group headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| offer catalogs and institutional pages | compact-action | Inter | 600 | 16px | 1.3 | normal | Small outlined shopping and institutional actions. |
| offer explanation and objection-handling sections | question | Inter | 600 | 16px | 1.5 | normal | FAQ question text and short benefit subheads. |

**Notes:**

- Keep the same -0.2px tracking across the 26px–48px heading family; do not progressively tighten it into a compressed display style.
- Use sentence case throughout the hierarchy. Small section eyebrows are medium-weight 16px text, not widely tracked uppercase.
- The 26px hero supporting line is deliberately stronger than ordinary 16px prose; retain this intermediate tier.
- Default button lettering is weight 500; the smaller institutional and offer-catalog controls use weight 600.

## Layout

**Density:** Airy through the narrative, with compact shopping controls and a denser utility ending.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Explains the predominant section padding and stacked-content intervals; horizontal layouts also frequently use multiples of 8px.

| Value | Use |
| --- | --- |
| 8px | Tight icon and short-item grouping. |
| 16px | Hero action gap, compact tile padding and title-to-description gaps. |
| 24px | Heading-to-support spacing, card-grid gaps and card body padding. |
| 32px | Heading-to-segmented-control spacing and secondary section gutters. |
| 40px | Hero support-to-action spacing and common outer gutters. |
| 48px | Larger grid intervals and footer margins. |
| 64px | Community heading-to-rail spacing and larger call-to-action separation. |
| 80px | Default top and bottom padding for major narrative sections. |

### Containers and grids

- **content-container**: max width 1224px · side padding 40px. Centered desktop content for feature rows, reassurance columns and three-card groups.
- **heading-column**: max width 680px. Centered section lead and supporting paragraph; also closing invitations.
- **split-copy**: max width 464px. Vertically centered copy beside a half-width photograph.
- **editorial-grid**: max width 1224px · 3 columns · gap 24px. Three equal 392px editorial cards.
- **reassurance-grid**: max width 1224px · 4 columns · gap 12px. Four compact centered explanations across a dark closing band.
- **wide-media**: max width 1336px. Near-full-width editorial video with visible canvas margins.
- **offer-grid** (only for offer catalogs): max width 1224px · 2 columns · gap 24px. Two broad 600px product-offer cards with generous object space.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | hero-button | 28px |
|  | product-button | 24px |
|  | outline-button | 204px |
|  | editorial-card | 16px |
|  | lineup-tile | 18px |
|  | quote-card | 19px |
|  | media | 8px |
|  | email-field | 2px |
|  | footer-submit | 3px |
|  | segmented-control | 48px |
| offer catalogs | offer-card | 12px |
| offer catalogs and institutional pages | compact-button | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| editorial-card | `rgba(0, 0, 0, 0.05) 0px 16px 40px 4px` | Soft lift for white editorial cards on the cool canvas. |
| active-segment | `rgba(0, 0, 0, 0.04) 0px 4px 8px 0px` | Very shallow lift under the selected product segment. |

### Surfaces

#### Cool canvas · level 0

**Use:** Default narrative background.

**CSS:** `background-color: #f5f7f9`

**Observed:** Large uninterrupted fields connect multiple media and copy sections.

**Transfer:** Let space and imagery organize the narrative instead of enclosing every block.

#### White service band · level 0

**Use:** Practical explanations, FAQ, disclosures and footer.

**CSS:** `background-color: #ffffff`

#### Charcoal band · level 0

**Use:** Navigation, practical reassurance and reverse statements.

**CSS:** `background-color: #181a1d; color: #ffffff`

**Observed:** A full-bleed flat field, not a gradient or floating panel.

**Transfer:** Use dark sections as deliberate changes of pace within the predominantly light page.

#### Raised editorial card · level 1

**Use:** Related-product and adjacent-category recommendations.

**CSS:** `background-color: #ffffff; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.05) 0px 16px 40px 4px; overflow: hidden`

#### Media legibility veil · level 1

**Use:** White text on lifestyle media.

**CSS:** `background-color: rgba(24, 26, 29, 0.3)`

**Observed:** A transparent dark layer preserves the visible room and person beneath it.

**Transfer:** Use only enough darkening to retain the natural light and readable text.

#### Offer card · level 1

**Only for:** offer catalogs

**Use:** Large isolated product-and-price panels.

**CSS:** `background-color: #ffffff; border-radius: 12px; overflow: hidden`

**Observed:** Flat white panels sit on the cool canvas without the editorial-card shadow.

## Components

### Sticky navigation

**Use:** Persistent shopping and category orientation.

**CSS:** `height: 72px; position: sticky; top: 0px; z-index: 4; display: flex; align-items: center; gap: 40px; padding: 0px 24px; background-color: #181a1d; color: #ffffff`

**Text style:** `label` — Inter 500 · 18px/1.3

**Observed:** A compact letterspaced wordmark sits left; category links occupy the center, with small chevrons where relevant; account and cart line icons sit right.

### Hero button

**Use:** Primary action over moving imagery.

**CSS:** `height: 56px; padding: 0px 22px; border: 2px solid #ffffff; border-radius: 28px; background-color: #ffffff; color: #181a1d; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 500 · 16px/1.3

**Observed:** Two equal-status actions sit side by side when two products lead the story; widths follow their labels.

**States:** Declared: hover background-color #f5f7f9 and border-color #f5f7f9; text-decoration none.

### Dark product button

**Use:** Conversion beneath the isolated product stage.

**CSS:** `height: 48px; padding: 0px 22px; border: 2px solid #181a1d; border-radius: 24px; background-color: #181a1d; color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 500 · 16px/1.3

**Observed:** One centered action follows a short support paragraph.

**States:** Declared: hover background-color #65666a and border-color #65666a; text-decoration none.

### Outline action

**Use:** Browse a larger content collection without overpowering the imagery.

**CSS:** `height: 56px; padding: 24px; border: 2px solid #181a1d; border-radius: 204px; background-color: transparent; color: #181a1d; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 500 · 16px/1.3

**Observed:** The inner label can use 15px semibold lettering; the pill remains visually light against the canvas.

**States:** Declared: hover background-color #181a1d, border-color #181a1d and color #ffffff; text-decoration none.

### Editorial card

**Use:** Recommend adjacent products or experiences.

**CSS:** `width: 392px; background-color: #ffffff; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.05) 0px 16px 40px 4px; overflow: hidden`

**Text style:** `action` — Inter 500 · 16px/1.3

**Observed:** Full-width 392px by 232px image above a padded body; small title, paragraph and low-emphasis underlined destination link. The whole card acts as a destination.

**Transfer:** Use a consistent image ratio and aligned body structure rather than mixing arbitrary card heights.

### Lineup tile

**Use:** Fast image-led exploration near a media stage.

**CSS:** `width: 207px; padding: 16px; border-radius: 18px; background-color: #ffffff; display: flex; flex-direction: column; gap: 16px`

**Text style:** `label` — Inter 500 · 18px/1.3

**Observed:** A 175px square product image sits above a compact label, with a small directional icon. Six tiles form a horizontally browseable family.

### Segmented product selector

**Use:** Choose variants above a single large product visualization.

**CSS:** `width: 428px; height: 58px; max-width: 100%; display: grid; grid-template-columns: repeat(3, minmax(120px, 1fr)); border: 1px solid #e4e6e7; border-radius: 48px; background-color: #e4e6e7; position: relative`

**Observed:** A pale 134px by 48px active thumb floats within the track with a shallow shadow. Labels remain compact and centered; the selected variant changes the central object.

**States:** Declared: selected-thumb transform transition 150ms.

### Quote card

**Use:** Make personal transformation readable in a horizontal proof rail.

**CSS:** `width: 390px; height: 393px; background-color: #ffffff; color: #181a1d; border-radius: 19px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `statement` — Inter 600 · 26px/1.3 · tracking -0.0077em

**Observed:** Large quotation at top, attribution near bottom and product context beneath. Alternating image-backed cards reverse the text and use a dark translucent veil.

**Transfer:** Pair authentic quotations with portraits or activity imagery; keep the rail wider than the viewport rather than shrinking every card to fit.

### Email field

**Use:** Compact newsletter signup in the service footer.

**CSS:** `width: 269px; height: 50px; padding: 14px 12px 0px; border: 1px solid #888b93; border-radius: 2px; background-color: #ffffff`

**Text style:** `field-label` — Inter 400 · 14px/1.5 · tracking 0.025em

**Observed:** A separate floating label overlays the field; the submit control sits alongside with a 10px gap. The offer-page closing form uses a wider 428px by 56px field with 4px corners.

**Transfer:** Keep labels explicit and the utility form visually more rectangular than shopping CTAs.

### Footer submit

**Use:** Complete the newsletter form.

**CSS:** `height: 50px; padding: 0px 22px; border: 2px solid #181a1d; border-radius: 3px; background-color: #181a1d; color: #ffffff; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 500 · 16px/1.3

**Observed:** A compact rectangular button, distinct from the rounded editorial actions.

**States:** Declared: hover background-color #65666a and border-color #65666a.

### Compact outline action

**Only for:** offer catalogs and institutional pages

**Use:** Product-card shopping and secondary institutional invitations.

**CSS:** `height: 40px; padding: 0px 22px; border: 2px solid #181a1d; border-radius: 20px; background-color: transparent; color: #181a1d; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `compact-action` — Inter 600 · 16px/1.3

**Observed:** Shopping cards use label-sized widths; institutional invitations often expand to 240px. On charcoal, both the border and text reverse to white.

**States:** Declared: hover background-color #181a1d and color #ffffff; reverse variant hover background-color #ffffff and color #181a1d; text-decoration none.

### FAQ row

**Only for:** offer explanation and objection-handling sections

**Use:** Address practical purchasing questions.

**CSS:** `width: 808px; max-width: 100%; border-bottom: 1px solid #888b93`

**Text style:** `question` — Inter 600 · 16px/1.5

**Observed:** An approximately 72px question button uses 24px vertical padding, left-aligned text and a small right chevron; the answer expands below. A separate section title occupies the left column.

**States:** Declared: background-color transition 250ms ease.

## Imagery and graphics

### Cinematic human activity

**Use:** The opening and major experience-led chapters.

**Observed:** Full-bleed moving people in real interiors: window light, reflections, wood, greenery and dark equipment. Soft teal or warm beige environments keep skin and motion prominent; activity fills much more space than copy. The opening subject is off-center behind the centered message.

**Transfer:** Show a person using or benefiting from the new product in a believable environment. If video is unavailable, use a strong still with the same layered room, natural light and off-center action; retain a full-width media stage.

### Isolated engineered object

**Use:** Product comparison stage, compact lineup and offer cards.

**Observed:** Dark products are shown whole in profile or three-quarter view against white or very pale gray. Fine edges remain crisp, screens are visible, and diffuse ground shadows give weight without decorative scenery.

**Transfer:** Photograph or render the object on a near-white floor with a broad soft key light and a low-contrast contact shadow. For software, stage one clear interface view or a representative output on the same neutral field instead of a collage of tiny screens.

### People-first editorial media

**Use:** Expert introduction, category browsing and split explanatory sections.

**Observed:** Close portraits and active bodies alternate with full-person product use. Studio portraits have warm neutral backdrops and confident direct expressions; home-use scenes preserve plants, windows and wood. Large videos use gently rounded corners, while split photographs meet section edges.

**Transfer:** Choose credible experts or users with natural expressions. Keep the face or action large, and vary portrait closeness without changing the soft light and restrained surroundings.

### Dark woven institutional banner

**Only for:** institutional story openings

**Use:** Short text-led masthead without a dominant product object.

**Observed:** An almost-black, subtly woven diagonal texture fills a 400px banner behind a centered white title and a small supporting line. The texture is low contrast and secondary to the words.

**Transfer:** Use a material associated with the new product's craft, reduced to a subdued dark texture rather than copying a specific weave.

**Build:** Layer two repeating diagonal SVG dot grids at opposing 45-degree directions over charcoal. Use small translucent white dots at roughly 3%–6% opacity, modulate their opacity in broad diagonal bands, and soften the tile slightly. Keep the title area dark and free of visible high-contrast pattern.

### Icons

**Observed:** Small functional SVGs, not colorful illustrations: 32px account, cart and playback controls use roughly 2px strokes; navigation chevrons are tiny and gray. Reassurance graphics use approximately 44px monochrome symbols, and category photos carry a pale circular activity badge.

**Transfer:** Use one coherent monochrome icon set with simple silhouettes or 2px outlines. Keep icons subordinate to products and people; use circles for media controls and small activity badges.

## Section recipes

How recurring sections are built.

### First screen: Human activity opening

**Observed:** A 72px Sticky navigation caps a full-width 852px moving-image stage. The environmental scene is the back layer; a centered white display headline spans roughly half the desktop width, followed by a 26px statement with 24px separation and two Hero buttons after about 40px. The image subject sits off-center and occupies much of the stage rather than appearing as a small cutout beside the text. A lineup title and the tops of the Lineup tiles emerge near the bottom of the first 900px, visually bridging into exploration; full tile labels continue below the fold. The headline, support, actions and activity are all visible immediately.

**Transfer:** Use a short product promise over one immersive human-use scene. Without video, use a carefully art-directed photograph and keep the foreground text and actions as HTML. Institutional and offer-explanation pages instead open with a compact 400px image or material banner and a centered 48px title, leaving the following explanatory block visible in the first screen.

**Avoid:** Do not replace the immersive stage with a small right-hand image, giant typographic poster, or empty abstract gradient. Do not force the full lineup into the first viewport at the cost of the human scene.

**Text style:** `display` — Inter 600 · 48px/1.3 · tracking -0.0042em

### Centered heading pair

**Observed:** A heading-lg lead above 16px secondary copy, centered within 680px. Use 24px between title and paragraph, then another 24px to a browse action when present; narrative sections typically receive 80px top and bottom space.

**Transfer:** State one human benefit, then explain the concrete offer in two or three readable lines.

**Text style:** `heading-lg` — Inter 600 · 36px/1.3 · tracking -0.0056em

### Product comparison stage

**Observed:** A 32px centered heading and Segmented product selector sit above a very wide, pale product stage. The object is isolated centrally with ample floor around it. Small direct manipulation labels sit beneath the object; a narrow support column and Dark product button finish the stage.

**Transfer:** Let users compare meaningful variants or see one purposeful state change. Keep the object dominant and controls below the headline rather than surrounding it with feature badges.

**Text style:** `heading` — Inter 600 · 32px/1.3 · tracking -0.0063em

### Asymmetric demonstration triptych

**Observed:** Within 1224px, a centered 32px lead precedes three media panels: one 588px-wide panel and two 294px-wide portrait panels, all about 392px tall and separated by 24px. Short captions use translucent gray pills over the media; a support paragraph sits beneath the wide panel.

**Transfer:** Show a simple benefit workflow through three concrete moments, making the first explanatory moment twice as wide as the others. Use stills if moving demonstrations cannot be produced.

**Text style:** `heading` — Inter 600 · 32px/1.3 · tracking -0.0063em

### Edge-revealing exploration rail

**Observed:** A centered heading and Outline action introduce large activity photographs in a horizontal rail. Each image carries a small circular category icon; labels and short underlined preview links sit below. Circular arrows overlay the rail edges and centered pagination uses one elongated active mark among dots.

**Transfer:** Use this device to make a family of uses feel browseable and populated. Keep the next card partly visible to communicate continuation.

### Community proof rail

**Observed:** A full-bleed photographic background supports a centered white 48px statement above alternating Quote cards and image-backed quotations. Cards are 390px wide with 24px gaps; the rail has 64px separation from the heading and circular previous/next controls.

**Transfer:** Translate brand-level belonging into credible individual outcomes. Keep the visual contrast between a readable white quotation and an intimate human photograph.

**Text style:** `display` — Inter 600 · 48px/1.3 · tracking -0.0042em

### Editorial recommendations

**Observed:** Centered heading pair over the three-column editorial-grid, with 72px from the support copy to card imagery. Editorial cards combine studio objects and atmospheric human images rather than a uniform icon grid.

**Transfer:** Introduce adjacent offerings or next steps after the central proposition has been established.

### Practical reassurance closing

**Observed:** Charcoal band with 80px vertical padding, centered 36px title and muted support. Four reassurance columns combine monochrome symbols, 18px labels and muted 16px explanations with 0.025em tracking. It leads into white disclosures and the service footer.

**Transfer:** Resolve four real purchase or adoption concerns using specific commitments. Preserve this practical closing device, but choose concerns appropriate to the new offer.

**Text style:** `heading-lg` — Inter 600 · 36px/1.3 · tracking -0.0056em

### Open service footer

**Observed:** White, open layout with four link groups on the left and a roughly 386px newsletter-and-support column on the right. Group titles are 14px, links use muted 14px lettering with about 10px between rows; the email field and Footer submit share a line. Contact methods and monochrome social icons follow. A separate download-badge row sits below, then a full-width Cool canvas strip holds locale, a thin divider, policy links and copyright.

**Transfer:** End with useful navigation, contact and distribution destinations. Keep the practical footer light even when the preceding call is dark.

**Text style:** `footer-heading` — Inter 400 · 14px/1.714

### Alternating editorial split

**Only for:** institutional and offer explanation pages

**Observed:** A half-width photograph pairs with a vertically centered copy column of about 464px. Headings are 32px and paragraphs 16px; alternating image sides changes pace. Some images meet the viewport edge, while more practical explanations use inset media and 80px vertical padding.

**Transfer:** Pair origin, process or use-case explanations with genuine people and environments instead of generic illustrations.

**Text style:** `heading` — Inter 600 · 32px/1.3 · tracking -0.0063em

### Flat offer catalog

**Only for:** offer catalogs

**Observed:** Two columns of white Offer cards on the Cool canvas, separated by 24px. Each card centers a 32px product name, price, Compact outline action and financing line above a large isolated product. Product scale varies with its natural shape while the card structure stays consistent.

**Transfer:** Make options easy to scan without turning the page into a dense comparison table.

**Text style:** `heading` — Inter 600 · 32px/1.3 · tracking -0.0063em

### Institutional close

**Only for:** institutional pages

**Observed:** A slightly lighter charcoal press invitation precedes a darker centered contact call. The final block uses a 36px two-line question and two white-outline 240px by 40px Compact outline actions, with 80px top and bottom space.

**Transfer:** Finish an institutional narrative with a low-pressure invitation to make contact or explore the organization.

**Text style:** `heading-lg` — Inter 600 · 36px/1.3 · tracking -0.0056em

### Offer questions and email close

**Only for:** offer explanation pages

**Observed:** On white, a left-hand 32px FAQ heading sits beside an 808px stack of FAQ rows. A cool-canvas closing invitation follows with a centered 36px line, support, a 428px by 56px email field and a 240px by 56px rounded outline submit action. Disclosures remain beneath the conversion block.

**Transfer:** Answer the main operational objections before requesting contact information; make the email ask a continuation of the offer rather than a separate promotional interruption.

**Text style:** `heading-lg` — Inter 600 · 36px/1.3 · tracking -0.0056em

## Page flow

**Storyline:** Human promise → tangible product exploration → experience and capability proof → personal credibility → practical reassurance → useful next steps and service.

### Flagship consumer landing page

1. **Promise** — Immersive activity opening with centered message and paired actions; compact lineup begins within the stage.
2. **Product exploration** — Variant selector and isolated object stage followed by an experience-led media statement.
3. **Capability demonstration** — Asymmetric demonstration triptych and wide expert portrait video.
4. **Breadth** — Centered browse invitation and edge-revealing category rail.
5. **Social proof** — Large reverse statement and alternating personal quotation cards.
6. **Adjacent opportunities** — Three raised editorial recommendation cards.
7. **Objection handling** — Dark four-column practical reassurance band.
8. **Service ending** — White disclosures, open multi-column footer, download badges and cool utility strip.

**Transfer:** Use the alternation of human experience and tangible object proof as the default landing-page rhythm; select and reorder modules to suit the new offer.

### Institutional story page

1. **Orientation** — Short textured dark masthead with centered title and support.
2. **Origin** — Full-height team photograph beside a readable story column.
3. **Purpose** — Centered short statements alternate charcoal and cool off-white bands.
4. **Principles** — White three-column group with circled numerals, 18px labels and centered descriptions.
5. **Belonging** — Large human-led film invitation on a dark field.
6. **Differentiation** — Alternating image-and-copy splits explain the operating model and distinctive experience.
7. **External credibility** — Secondary charcoal press invitation.
8. **Closing call** — Darker contact invitation with paired white outlined actions.
9. **Service ending** — Shared white footer and cool utility strip.

**Transfer:** Scope material textures, principle numerals and organization invitations to an institutional narrative; retain the same type and color discipline.

### Offer explanation and risk reduction

1. **Offer promise** — 400px home-use photographic banner with white title, then centered explanatory heading and support on white.
2. **Process explanation** — Large contextual photo beside three short practical benefit explanations.
3. **Risk reduction** — Opposite-side image with plain-language return process and a compact outline link.
4. **Selection** — Centered invitation leading into a two-column flat product catalog.
5. **Objection handling** — Left-aligned FAQ title beside ruled accordion rows.
6. **Closing conversion** — Cool off-white centered email invitation with broad field and rounded submit action.
7. **Service ending** — Disclosures, shared white footer, download row and utility strip.

**Transfer:** Lead with the offer, make the process credible, present relevant options, and resolve operational questions before the contact ask.

## Writing

Confident, encouraging and conversational. It blends aspiration with everyday flexibility, making advanced equipment and services sound accessible rather than exclusive.

**Do not copy:** Do not reuse Peloton names, logos, product names, proprietary program names, member quotations, performance claims, catalog counts, prices, financing terms or guarantees. Replace all with truthful content and assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your goals. Use we when explaining service commitments, and refer to the product plainly by name rather than as an abstract platform.
- **Rhythm:** Short sentence-case headlines, often with two linked thoughts. Support copy expands through two or three conversational sentences; practical information stays explicit and calm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Introduce a new product generation with a direct, welcoming announcement. | 6–9 words | “Meet the next generation of Treads” |
| Supporting line | Three simple verbs or choices, ending in personal agency. | 5–10 words | “Run, walk, and train your way.” |
| Section headline | A concise benefit or playful familiar phrase, adapted to the offer. | 4–9 words | “Class is always in session”<br>“Instructors for every you” |
| Reassurance headline | Remove anxiety with a familiar idiom and a concrete process. | 4–8 words | “Send it back, no sweat” |
| Primary action | A clear verb and a named destination or product. | 2–4 words | “Explore Tread Flex”<br>“Meet the team” |
| Closing invitation | An open question or personally framed time-bound opportunity. | 5–9 words | “Interested in learning more about [Brand]?”<br>“30 days to find your groove” |

**Words and phrasing to use:** your way; find; choose; move; every day; at home; together; no problem; confidence

**Avoid:** disruptive ecosystem; crush the competition; elite only; revolutionary paradigm; guaranteed transformation

**Rules:**

- Lead with the human benefit, then explain the technology that enables it.
- Pair confidence with choice: different moods, goals and schedules are welcomed rather than ranked.
- Use a little everyday wordplay in headings, but keep prices, obligations and service policies literal.
- Keep CTAs destination-specific; reserve the plain label Submit for forms.
- Support community language with identifiable people and genuine stories rather than anonymous hype.

## Do's and Don'ts

### Do

- Set the main media headline at 48px/1.3, weight 600, with -0.2px tracking.
- Use the 26px statement tier for a prominent hero support line rather than shrinking it into body copy.
- Keep centered narrative text within 680px and multi-column content within 1224px.
- Use 24px card gaps and 80px vertical section padding as the main narrative rhythm.
- Maintain the 56px white hero pill and the 48px dark product-stage pill as distinct defaults.
- Show crisp isolated products against near-white and lived-in people scenes with natural light.
- Preserve horizontal continuation in image-led exploration rails.
- Use 16px muted explanations beneath 18px reassurance labels.
- Keep the footer form rectangular with 2px field corners and 3px submit corners.

### Don't

- Do not make every heading 48px; the regular section lead is 36px and feature lead 32px.
- Do not use an ultra-heavy, condensed or all-capital display face in place of Inter semibold.
- Do not introduce recurring bright red, neon or gradient marketing panels; let photography carry chromatic energy.
- Do not apply the 16px editorial-card shadow treatment to flat 12px offer cards.
- Do not wrap each paragraph or feature in a bordered box; broad uninterrupted canvas is essential.
- Do not replace 2px pill outlines with hairline rectangular shopping buttons.
- Do not put muted #65666a support copy on charcoal; use the lighter reverse secondary gray.
- Do not turn the white service footer into another dark cinematic section.
- Do not shrink full product silhouettes into decorative background fragments; they must remain recognizable and comparable.

## Motion and responsive

### Motion

**Observed:**

- Hero and editorial media include play or pause controls.
- Main action transitions are declared as 0.15s ease-in-out; dark controls change fill and outline together.
- The segmented selector thumb declares transform 150ms.
- FAQ rows declare background-color 250ms ease; the sticky navigation declares background-color 0.2s.

**Transfer:**

- Retain visible playback control on cinematic media and keep product-state changes tied to the segmented selector.
- Use the short declared color transitions for buttons rather than adding bouncy scale effects.

**Unknown:**

- Automatic playback policy, scroll choreography, video timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Desktop composition is based on a 1440px-wide viewport.
- Styles declare width breakpoints including 375px, 480px, 668px, 768px, 1024px, 1280px and 1920px; no fluid type formula is established.

**Transfer:**

- As a narrow-screen adaptation, preserve the immersive media and centered foreground promise while stacking paired actions only when needed.
- Keep exploration rails horizontally browseable rather than compressing all tiles into a tiny grid.
- As a narrow-screen adaptation, stack split photographs and copy, then reduce offer grids to one column; keep the complete product visible.

**Unknown:**

- Exact mobile typography, navigation behavior, spacing changes and breakpoint-specific grid rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
