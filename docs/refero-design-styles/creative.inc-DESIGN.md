# creative.inc — monumental type, tactile play

## Overview

An expansive editorial style with an imaginative, handmade streak, suited to thoughtful consumer products and creative tools. Warm paper and near-black fields frame regular-weight grotesk headlines, a slender serif reading voice, candid photography and tactile product scenes. The density is sparse and cinematic rather than dashboard-like, with small explanatory captions and playful graphics interrupting the monumental typography.

### Essentials

- Headlines behave like a staggered poster: regular 150px sans with -0.04em tracking, a short first phrase at the left and a longer second phrase anchored right; small 13.7px supporting copy occupies the opposite pocket.
- A persistent conversion capsule floats above the story: a 326×53px dark form with 50px corners and an inset 38px circular arrow; reverse its colors over the dark chapters.
- Color belongs to the pictures, not the interface: cream #f3f2e9 dominates, a continuous near-black #191816 chapter occupies roughly a third of the long composition, and saturated colors remain inside photography or artwork.
- The opening layers a handmade black-and-cream object graphic across the seam between giant text and a nearly edge-to-edge photograph; use a simplified textured silhouette when no product render exists.
- Images alternate between cinematic scale and loose printed fragments: 1402px-wide media with 19px side gutters contrasts with a dispersed collage surrounding a centered 28px/32px statement.
- A monumental conversion poster and a participatory ending are signature devices: 183.3px closing type wraps around a cream email capsule, while a paper-colored drawing field ends the story with a faint organic mark and a tiny centered invitation.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm paper | `#f3f2e9` | `--color-paper` | background, surface, text, action | Default canvas, pale capsules and reversed text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft paper | `#dddcd4` | `--color-muted-inverse` | text | Secondary explanatory text on charcoal; paper at 90% opacity over the dark field. |
| Soft ink | `#888780` | `--color-muted` | text | Secondary biographies: ink at 50% opacity over warm paper. |
| Warm ink | `#1c1b17` | `--color-ink` | text, action, surface | Primary lettering, arrows and the compact conversion capsule. |
| Charcoal chapter | `#191816` | `--color-dark` | background, surface, action | Continuous inverted storytelling band and the large email submit control. |

## Typography

- **Messina Sans Web** — Display lettering, explanatory copy and captions. Neutral open grotesk, always regular; unusually tight spacing at display sizes. If unavailable, use **Inter**. Use 400; preserve the tightly tracked display and check line widths. Font stack: "Messina Sans Web", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Albaro Text** — Long editorial statement between image narrative and inverted chapters. Slender, narrow literary serif with strong thick-thin contrast. If unavailable, use **Instrument Serif**. Use 400 upright; tune line breaks to retain the long narrow reading shape. Font stack: "Albaro Text", "Instrument Serif", Georgia, "Times New Roman", serif.
- **Yetson Sans** — Small navigation links only. Unobtrusive regular sans, sized like captions. If unavailable, use **Inter**. Font stack: "Yetson Sans", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-display | Messina Sans Web | 400 | 183.3px | 147.9px | -0.04em | Oversized conversion headline, split across opposing edges. |
| display | Messina Sans Web | 400 | 150px | 147.9px | -0.04em | Two staggered phrases in the opening poster. |
| statement | Albaro Text | 400 | 40px | 1.2 | -0.03em | Wide multi-line editorial statement. |
| centered-heading | Messina Sans Web | 400 | 28px | 1.143 | -0.03em | Centered belief statement within the photographic collage. |
| chapter-copy | Messina Sans Web | 400 | 26px | 1.154 | -0.03em | Short lead sentences and supporting paragraphs in inverted chapters. |
| section-label | Messina Sans Web | 400 | 17.9px | 1.412 | -0.0095em | Sentence-case labels at the left of major editorial sections. |
| body | Messina Sans Web | 400 | 14.7px | 1.286 | normal | Names, biographies and footer contact information. |
| caption | Messina Sans Web | 400 | 13.7px | 1.385 | normal | Hero support, image captions, small chapter labels and drawing instructions. |
| navigation | Yetson Sans | 400 | 13.7px | 1.385 | normal | Header and footer navigation. |

**Notes:**

- The entire hierarchy uses weight 400; scale, alignment and font contrast do the work of bold weights.
- Sans display uses -0.04em tracking; medium statements and chapter copy relax to -0.03em; small copy returns to normal spacing.
- The closing headline has tighter-than-size leading and must be composed as separate phrases, not a conventional stacked paragraph.

## Layout

**Density:** Airy, with long photographic and typographic pauses punctuated by small islands of explanatory text.

### Spacing

| Value | Use |
| --- | --- |
| 19px | Desktop side gutter around large photographic media. |
| 24px | Navigation gap. |
| 25px | Separation between a linked name and the start of its biography. |
| 27px | Left inset of the large email input within its capsule. |
| 232px | Opening title starts after a deep upper field beneath the fixed header. |

### Containers and grids

- **edge-to-edge-stage**: max width 1440px · side padding 19px. At the desktop design width, media spans 1402px. Let the composition follow the viewport rather than sit inside a conventional narrow centered website container.
- **editorial-reading-stage**: max width 786px. Wide serif reading block begins around the left third of the page. Above it, a tall central photograph is flanked by a small section label on the far left and narrow captions on the right.
- **chapter-pair**: 2 columns. Tiny label in the left half, approximately 497px-wide 26px copy in the right half; empty space is structural.
- **collage-statement**: max width 458px. Centered four-line statement; scattered photographs stay outside its reading area.

## Corner radius

| Element | Radius |
| --- | --- |
| conversion-capsules | 50px |
| photographic-panels | 8px |
| video-control | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| video-hover | `0px 6px 20px rgba(0,0,0,0.25)` | Hover only on the circular video control; the page otherwise stays flat. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page field and final participatory area.

**CSS:** `background: #f3f2e9; color: #1c1b17`

**Observed:** A warm untextured ground; photographs and type sit directly on it, not on cards.

**Transfer:** Retain the paper warmth even for a digital-only product.

#### Charcoal chapter · level 0

**Use:** Continuous inverted band linking narrative copy, product demonstration, uses and conversion.

**CSS:** `background: #191816; color: #f3f2e9`

**Observed:** Full-width uninterrupted dark field. Very faint horizontal rules divide a few editorial beats.

**Transfer:** Group related beats into one continuous dark chapter rather than alternating every row.

#### Secondary biography · level 1

**Use:** Muted supporting text beneath linked names.

**CSS:** `color: rgba(28,27,23,0.5)`

**Observed:** Names stay full ink; biography paragraphs recede without a separate card surface.

**Transfer:** Use for secondary credentials, not core product promises.

#### Soft inverse copy · level 1

**Use:** Supporting prose inside dark narrative rows.

**CSS:** `color: rgba(243,242,233,0.9)`

**Observed:** The lead sentence remains full paper while the explanation is slightly softened.

**Transfer:** Keep the distinction subtle rather than using a separate accent color.

## Components

### Fixed navigation

**Use:** Persistent brand and orientation above the story.

**CSS:** `display: flex; gap: 24px; color: #1c1b17`

**Text style:** `navigation` — Yetson Sans 400 · 13.7px/1.385

**Observed:** A compact stacked wordmark sits at the upper left, conversion form in the center and three small text links on the right. The 69px fixed header has no heavy panel backing; only the conversion capsule persists prominently while scrolling.

**Transfer:** Use a compact typographic mark and a minimal link set, leaving the center to conversion.

### Compact conversion form

**Use:** Always-available subscription action.

**CSS:** `width: 326px; height: 53px; background: #1c1b17; border-radius: 50px`

**Observed:** A short invitation or input occupies the left; a pale circular arrow control is inset at the right. Over charcoal the capsule becomes pale with a dark arrow.

**Transfer:** Use one low-commitment action appropriate to the new product; keep the capsule silhouette.

### Compact submit

**Use:** Arrow action inside the persistent conversion form.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 38px; height: 38px; background: #f3f2e9; border-radius: 50px`

**Observed:** A 13×10px right arrow replaces a text button label; its surrounding capsule supplies the context.

### Large email form

**Use:** Primary conversion in the monumental dark poster.

**CSS:** `width: 491px; height: 91px; background: #f3f2e9; border-radius: 50px`

**Observed:** Pale pill centered between opposing headline fragments. An unboxed email input occupies the left and a 76×76px charcoal circular arrow is inset at the right; the arrow artwork is 21×16px.

**Transfer:** Keep the visible form singular; adapt the invitation rather than adding competing buttons.

### Play control

**Use:** Launch a product film from the image stage.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 69px; height: 69px; background: #f3f2e9; border-radius: 50%`

**Observed:** A dark triangular glyph sits centrally over the product; its 25px icon has a 2px optical shift to the right.

**States:** Declared: hover transform scale(1.08), box-shadow 0px 6px 20px rgba(0,0,0,0.25); focus-visible not specified.

**Transfer:** Retain the small central circular control rather than covering the image with a toolbar.

### Editorial media tile

**Use:** Present a use case as image plus restrained explanation.

**CSS:** `object-fit: cover; color: #f3f2e9`

**Text style:** `caption` — Messina Sans Web 400 · 13.7px/1.385

**Observed:** A short category label appears above a photograph, with caption below. Three tiles use deliberately unequal image sizes; the largest image is 518×518px. No raised card, outline or rounded shell surrounds the tile.

**Transfer:** Show different human situations rather than three matching feature icons.

### Personal text link

**Use:** Names and direct contact information.

**CSS:** `color: #1c1b17; text-decoration: none`

**Text style:** `body` — Messina Sans Web 400 · 14.7px/1.286

**Observed:** Plain linked text, paired with a subdued biography or placed alone in the footer.

**States:** Declared: hover text-decoration underline, text-underline-offset 0.16em; focus-visible outline solid 2px, outline-offset 4px.

### Drawing invitation

**Use:** Participatory close after the conversion and credibility content.

**CSS:** `height: 610px; width: 100%; background: #f3f2e9; text-align: center`

**Text style:** `caption` — Messina Sans Web 400 · 13.7px/1.385

**Observed:** Full-width drawing field with a faint central organic ornament. A narrow 214px text block explains the interaction; a sparse footer baseline places company left, email center and navigation right.

**Transfer:** Offer a small creative interaction related to the product. A simple ink-trail canvas with clear instructions is an acceptable minimum.

## Imagery and graphics

### Handmade object emblem

**Use:** Overlapping focal graphic in the opening.

**Observed:** A black-and-cream camera-shaped illustration is tilted clockwise and crosses the headline/photo seam, around one fifth of the page width. Grainy ink, concentric circles and slightly imperfect contours give it a printed, toy-like character.

**Transfer:** Make an equally simple emblem of the new product or its central activity. For software, use a symbolic tool or gesture rather than a floating dashboard.

**Build:** Draw a simplified SVG silhouette in warm ink with paper-colored inner cutouts; use 3–5 bold geometric primitives, thick concentric circles or similarly legible details, a subtle SVG turbulence texture clipped to the ink, and roughly 20–25 degree clockwise rotation. Layer above both the photo and the paper field; keep it clear of readable letters.

### Domestic cinematic photography

**Use:** Wide opening media and smaller use-case tiles.

**Observed:** Warm daylight through wooden windows, lived-in rooms, children and parents engaged in ordinary activities. Natural clutter, tactile materials and soft grain make the scenes feel personal. The opening image spans almost the full width and continues below the first viewport.

**Transfer:** Photograph the people and places the new product serves, with environmental detail and believable gestures. Preserve natural light and warmth rather than glossy corporate stock staging.

### Scattered memory collage

**Use:** Surround a compact centered statement with lived experience.

**Observed:** Small mixed-aspect photographs float loosely across the cream field, some touching the viewport edges. Their subjects include everyday play, people, beach views and objects; varied scale and large gaps create a constellation rather than a grid.

**Transfer:** Use a family of authentic contextual photographs, maintaining an empty center for text. If bespoke images are scarce, vary the framing of a few strong photographs rather than adding blank tiles.

**Build:** Place 8–12 rectangular image fragments on separate absolute-positioned layers around a centered reading column. Vary widths approximately 60–175px at desktop, alternate portrait and landscape ratios, and let a few extend beyond the edges. Keep the photographs upright and shadowless; reserve the middle 458px for the statement.

### Imaginative transformation

**Use:** Central editorial demonstration of a changed perspective.

**Observed:** A tall street photograph shows a child with a small blue creature, followed by the same context transformed into an enormous furry companion. Warm photographic realism makes the improbable element feel tangible. A small reference thumbnail and restrained captions sit beside the main image.

**Transfer:** Pair an ordinary input with an emotionally vivid result using consistent viewpoint and lighting. For a non-generative product, use a carefully art-directed before/after or two states of a real activity.

### Sunlit product stage

**Use:** Large film poster within the dark chapter.

**Observed:** A tactile gray-and-green physical object lies on warm sandy paper under directional sunlight, with a long soft-edged shadow and blurred foliage shadows. The product dominates the center while 80px words sit at far left and right.

**Transfer:** Use a real product render or photograph against a warm physical backing. For software, stage a printed artifact or device in the same directional light rather than using a neon abstract environment.

### Faint organic end mark

**Use:** Back the drawing invitation without competing with its copy.

**Observed:** A pale, vertically stretched branching doodle sits at the center of the warm-paper ending; rounded tendrils curl outward behind the centered caption.

**Transfer:** Create a new organic mark that suggests the product's creative gesture, keeping contrast extremely low.

**Build:** Use an SVG with 8–12 curved branching paths and rounded ends, about 380px wide and 410px tall at desktop. Fill or stroke with rgba(28,27,23,0.04), using broad 20–35px strokes. Layer behind a 214px centered caption; do not add a glow or drop shadow.

### Icons

**Observed:** Sparse functional icons: thin right arrows in circular submit controls and one solid play triangle. Arrow artwork is 13×10px in the compact form and 21×16px in the large form; the play SVG is 25×25px.

**Transfer:** Limit icons to directional or media controls, using warm ink/paper contrast instead of colored icon badges.

## Section recipes

How recurring sections are built.

### First screen: Staggered poster opening

**Observed:** Paper canvas supports a 69px fixed navigation layer, with stacked brand mark left, Compact conversion form centered and text navigation right. After deep upper breathing room, the 150px Display headline begins as a short left phrase; its longer second phrase moves to the right edge on the next tier. Caption-sized support fills the small left pocket beneath the first phrase. The Handmade object emblem overlaps the seam into a 1402px-wide photograph with 19px side gutters, beginning around 535px down the composition. Within the first 900px the entire headline, support, persistent action, emblem and upper portion of the environmental photograph are visible; the rest of the photograph falls below. The emblem is the foreground layer, media sits beneath it, and no extra hero buttons compete.

**Transfer:** Compose two semantically connected short phrases with opposing alignment and a clear left pocket for explanation. Replace the emblem and photograph with a product-related silhouette and a natural context image. Editorial page variants can keep the staggered title and support pocket while using an image relevant to the article.

**Avoid:** Do not turn this into a centered headline over a gradient with a pair of rectangular CTA buttons, or put the object inside a separate card.

**Text style:** `display` — Messina Sans Web 400 · 150px/147.9px · tracking -0.04em

### Collage belief pause

**Observed:** Scattered memory collage floats around a 458px centered block in Centered heading typography. Large paper gaps keep the statement the reading anchor while photography supplies emotional context.

**Transfer:** Write one concise point of view and surround it with real situations that support it, without requiring the same subject matter.

**Text style:** `centered-heading` — Messina Sans Web 400 · 28px/1.143 · tracking -0.03em

### Editorial transformation spread

**Observed:** A small Section label stays far left, a tall photo occupies the central column, and compact captions plus a reference thumbnail sit on its right. The image narrative resolves into a 786px-wide Statement block aligned with the photo's left edge.

**Transfer:** Demonstrate a meaningful change, then articulate why it matters in a serif passage rather than a feature list.

**Text style:** `statement` — Albaro Text 400 · 40px/1.2 · tracking -0.03em

### Inverted narrative rows

**Observed:** Charcoal chapter carries tiny labels on the far left and approximately 497px-wide Chapter copy starting in the right half. Lead sentence and explanation are separated by a paragraph break; subtle rules divide the rows.

**Transfer:** Use for design rationale or capability explanations. Retain two scales of text and the strongly asymmetric empty left half.

**Text style:** `chapter-copy` — Messina Sans Web 400 · 26px/1.154 · tracking -0.03em

### Film and human outcomes

**Observed:** Sunlit product stage fills the inset width; regular 80px sans words with -0.04em tracking flank the central object and Play control. Use natural leading for these single-word overlays. Below, Editorial media tiles show three ways the experience continues, with unequal image widths and small captions directly on the dark field.

**Transfer:** Present one memorable demonstration and then a handful of human outcomes, not a uniform icon feature grid.

### Monumental conversion poster

**Observed:** Closing display stretches a short invitation across opposing edges of Charcoal chapter. Large email form sits in the middle gap. A small left-aligned paragraph near the lower phrase explains what subscribing means; the composition reads as a poster rather than a boxed callout.

**Transfer:** Use a brief invitation suited to the conversion goal, with a single form or equivalent capsule action and honest supporting expectations.

**Text style:** `closing-display` — Messina Sans Web 400 · 183.3px/147.9px · tracking -0.04em

### Credibility and participatory ending

**Observed:** The canvas returns to paper. A small introductory line leads into staggered portrait and biography columns. A faint divider then opens the Drawing invitation field; the final baseline has company left, contact centered and two navigation links right. The page ends with creative participation, not another dense sitemap.

**Transfer:** Use the new product's most relevant credibility content before a playful interaction, then finish with a minimal contact baseline.

**Text style:** `body` — Messina Sans Web 400 · 14.7px/1.286

## Page flow

**Storyline:** Evocative promise → lived-context imagery → point of view → transformation demonstration → product rationale → human outcomes → singular conversion → credibility → participation.

### A long-form consumer-product introduction that establishes a worldview before asking for ongoing interest

1. **Promise** — Staggered poster title, tiny support, handmade emblem and wide environmental photograph.
2. **Emotional context** — Small candid image fragments orbit a centered statement.
3. **Product demonstration** — An ordinary scene changes into a vividly imagined result, followed by a serif explanation.
4. **Capability rationale** — Inverted asymmetric text rows lead to a sunlit film stage.
5. **Human outcomes** — Unequal photographic tiles show the experience in use.
6. **Conversion** — Monumental invitation and one pale email capsule on charcoal.
7. **Credibility** — Staggered portraits, linked names and short muted biographies.
8. **Participatory close** — Paper drawing field, faint organic artwork, centered invitation and sparse contact footer.

**Transfer:** Borrow the alternation of visual immersion and succinct explanation. Reorder or compress beats to fit the product while retaining the poster typography, handmade overlap, photographic context, monumental conversion and participatory close.

## Writing

Warm, thoughtful and quietly opinionated. Concrete objects and ordinary actions make an ambitious idea feel personal; the copy is confident about its convictions but candid about the product's stage.

**Do not copy:** Do not reuse the source's company or product names, founder identities, artwork, biographical credentials, adoption figures, quotes or product-specific claims. Examples illustrate tone, not claims available to another brand.

- **Addressing the reader:** Mostly speaks about people and their experiences, with occasional first-person plural for convictions and direct imperatives for actions.
- **Rhythm:** Headlines are brief fragments. Narrative leads often use 3–7 words, followed by one or two plain sentences. Longer serif passages provide an occasional reflective pause.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name an everyday category, then complete it with a human purpose. | 5–9 words | “A camera for their story” |
| Narrative lead | A short conviction or pair of compact imperatives. | 4–7 words | “The present comes first.”<br>“Notice it. Imagine it otherwise.” |
| Support | Physical nouns and a clear contrast explain the design choice. | 1–2 sentences | “Buttons, weight, one clear purpose. Obscura keeps children in the room, not in a feed.” |
| Conversion | A plain invitation, followed by candid expectations rather than urgency. | 3–5 words for the invitation | “Join our newsletter”<br>“More families soon. Sign up to follow what we make, learn and get wrong.” |
| Participation | Tell readers exactly what they can make and what happens next. | 2 short sentences | “Draw something and add it to the public gallery. Anyone can see it and download it.” |

**Words and phrasing to use:** notice; make; imagine; real world; things; one clear purpose; together; learn

**Avoid:** revolutionary; supercharge; unlock potential; seamless ecosystem; limited-time offer; industry-leading

**Rules:**

- Lead with the human experience rather than the technology category's jargon.
- Explain a conviction through tangible materials or behaviors.
- Use full stops and sentence case; let typographic scale create emphasis.
- State availability and limitations plainly in conversion support.

## Do's and Don'ts

### Do

- Keep the main display at weight 400 with -0.04em tracking.
- Preserve the 19px desktop media gutters and near-full-width photographic stage.
- Keep navigation small at 13.7px with 24px gaps.
- Use 50px capsule corners and inset circular arrow controls for conversion.
- Maintain a full charcoal chapter rather than isolated black cards.
- Use the 40px/1.2 serif statement as a deliberate change of reading voice.
- Keep small captions directly on the page field, outside image shells.
- Give the participatory close a full 610px drawing field and sparse contact baseline.

### Don't

- Do not replace warm paper #f3f2e9 with pure white or charcoal #191816 with blue-black.
- Do not add a saturated interface accent; vivid color belongs inside media.
- Do not use bold or semibold headline weights to manufacture hierarchy.
- Do not add default shadows to media tiles; reserve the declared shadow for video-control hover.
- Do not normalize the unequal outcome photographs into matching raised cards.
- Do not turn the faint organic end mark into a high-contrast logo wall.
- Do not style section labels as tracked uppercase technical eyebrows.
- Do not expand the closing contact baseline into a multi-column corporate sitemap.

## Motion and responsive

### Motion

**Observed:**

- Display and support reveals use tilt-rise and masked reveals, commonly 0.85s cubic-bezier(0.22,1,0.36,1).
- Navigation transforms use 0.45s cubic-bezier(0.22,1,0.36,1); the compact form background transitions over 0.35s.
- Product media declares 0.9s reveal and 1.2s image motion with cubic-bezier(0.22,1,0.36,1).
- The play control transitions opacity, transform and box-shadow over 0.35s; hover scales to 1.08.

**Transfer:**

- Animate the two headline phrases and small supporting lines as separate masked elements, preserving their poster alignment.
- Use image reveals to carry the large media stage rather than adding decorative UI motion.

**Unknown:**

- Exact scroll thresholds, pinning durations and the complete interaction behavior of the drawing gallery are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 700px, 767px, 768px, 1024px, 1100px and 1200px.

**Transfer:**

- On narrow layouts, preserve the two-phrase poster relationship but reduce type until both phrases remain readable; keep the overlapping emblem subordinate to text.
- Stack right-hand explanations beneath the main image and disperse fewer collage fragments around the reading area.
- Keep the conversion capsule usable without competing with navigation, and let footer contact items wrap.

**Unknown:**

- Narrow-screen typography values, exact breakpoint behavior and mobile navigation construction are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
