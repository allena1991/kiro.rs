# Bose — condensed type, expansive sound

## Overview

A light, image-dominant retail style with muscular condensed headlines and direct, friendly grotesk body copy. White space and pale warm-gray merchandise tiles frame saturated studio scenes, intimate lifestyle photography and oversized product renders. It suits physical products whose performance can be made tangible through people, materials and close-up demonstrations; the interface stays sparse even when the imagery is exuberant.

### Essentials

- Headlines act like compact posters rather than spacious editorial titles: Bose Headline at 60px, weight 900, 53px line height and 0.02em tracking, paired with much calmer 24px/36px support.
- The opening is a full-width media stage beneath a 72px white navigation bar and a 56px promotional strip: a 747px-tall scene carries a lower-left headline, support and one 48px action, with 40px side insets.
- Actions are little rectangular labels, not bubbles: 2px corners, 12px 24px padding, 16px/24px medium uppercase text and 0.05em tracking; white on imagery, near-black on white.
- Color belongs predominantly to the pictures: keep navigation, reading sections, proof rows and the closing invitation white; reserve electric blue #005bff for small links and use the muted #b4bec7 promotional band sparingly.
- Product presence must alternate between monumental scenes and tangible detail: use large edge-cropped lifestyle or studio media plus isolated packshots on #f8f7f6 tiles. When campaign photography is unavailable, use carefully lit product stills with strong scale and negative space, not abstract filler.
- The close is a billboard followed by a directory: a centered 60px condensed invitation, a dark rectangular action, then small four-column navigation and a thin #e6e6e6 social/legal divider. Preserve that contrast of loud invitation and quiet utility.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric link blue | `#005bff` | `--color-link` | link | Small text actions, ratings and keyboard-focus outlines; not broad page fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-white` | background, text, action | Visible page canvas, navigation and reversed text or buttons over media. |
| Soft gray | `#f8f8f8` | `--color-soft` | surface | Circular benefit-icon backings and category navigation. |
| Warm merchandise backing | `#f8f7f6` | `--color-merchandise` | surface | Isolated product tiles. |
| Warm search gray | `#f1efee` | `--color-search` | surface | Search field backing. |
| Directory divider | `#e6e6e6` | `--color-rule` | border | Thin divider below social links. |
| Subtle media edge | `#dcdcdd` | `--color-panel-edge` | border | Visible soft edge produced by 12.5% near-black over the pale outer canvas; media panels use rgba(19,19,23,0.125). |
| Promotional blue-gray | `#b4bec7` | `--color-promotion` | background | The shallow promotional strip above navigation. |
| Secondary gray | `#40464b` | `--color-secondary` | text | Footer links and supporting utility text. |
| Near-black ink | `#131317` | `--color-ink` | text, action | Primary headings, body text, icons and dark actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| business inquiry pages | Question divider | `#cccccc` | `--color-faq-rule` | border | Top borders of question rows. |

## Typography

- **Bose Headline** — All poster headlines and condensed benefit headings. Very narrow, heavy, upright sans with tall proportions and strongly packed counters. If unavailable, use **Barlow Condensed**. Use weight 900 for poster titles; preserve the narrow width and positive tracking. Font stack: "Bose Headline", "Barlow Condensed", sans-serif.
- **Bose Text** — Body copy, actions, navigation, prices and captions. Clean open grotesk, regular to medium weight; less compressed than the display face. If unavailable, use **Inter**. Use weights 400–500, with the specified negative body tracking. Font stack: "Bose Text", "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Bose Headline | 900 | 60px | 53px | 0.02em | fixed | Default media-stage and campaign headline. |
| heading | Bose Headline | 900 | 60px | 53px | 0.02em | size clamp(2.875rem, 2.625rem + 1.25vw, 3.75rem), line height calc(clamp(3.125rem, 3.0713rem + .2686vw, 3.313rem)) | Section headings above product ribbons, media galleries and proof groups. |
| closing-invitation | Bose Headline | 900 | 60px | 41px | 0.02em | fixed | The single-line centered invitation above the footer directory; allow the title box adequate height. |
| support | Bose Text | 500 | 24px | 1.5 | normal | fixed | One short supporting thought below a media headline. |
| body | Bose Text | 400 | 18px | 1.5 | -0.02em | fixed | Reading paragraphs and benefit descriptions. |
| product-label | Bose Text | 500 | 18px | 1.5 | -0.02em | fixed | Merchandise names and prices. |
| action | Bose Text | 500 | 16px | 1.5 | 0.05em, uppercase | fixed | Filled rectangular actions. |
| text-action | Bose Text | 500 | 16px | 1.5 | 0.05em | fixed | Blue chevron links beneath reading copy. |
| navigation | Bose Text | 400 | 15px | 1.2 | normal, uppercase | fixed | Primary navigation labels. |
| directory | Bose Text | 400 | 12px | 16px | normal | fixed | Compact footer navigation and promotional-strip copy. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling | heritage-display | Bose Headline | 900 | 110px | 96px | 0.015em | fixed | A monumental short title over archival imagery. |
| business inquiry campaigns | campaign-display | Bose Headline | 900 | 96px | 0.875 | 0.015em | fixed | Extra-large media headline within a business campaign scene. |
| company storytelling | story-label | Bose Text | 500 | 25px | 1.2 | normal | fixed | Plain labels underneath editorial image cards. |
| business inquiry pages | question | Bose Text | 400 | 20px | 1.35 | -0.018em | fixed | Question rows. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the display face truly condensed; a normal-width bold grotesk changes the character even at the same size.
- Large headings have positive tracking, while 18px reading copy tightens to -0.02em. Do not apply the body tracking globally.
- Display headings sit on unusually short line boxes. Write short lines and control wrapping rather than spreading letters or increasing leading indiscriminately. Benefit headings use Bose Headline 32px, weight 400, normal line height and 0.03em tracking; business inquiry headings and quotations use Bose Headline 46px, weight 700, normal line height and 0.03em tracking.

## Layout

**Density:** Airy between major scenes, compact within merchandise and utility regions. Large media carries the density rather than long blocks of interface.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small internal gaps and directory item spacing. |
| 12px | Headline-to-message spacing and tile side inset. |
| 16px | Media text stack and action gaps; image-to-story-label gap. |
| 24px | Grid gutters and centered invitation-to-action gap. |
| 32px | Benefit title spacing and icon-to-copy separation. |
| 40px | Desktop outer rail. |
| 48px | Media-panel vertical padding. |
| 64px | Closing invitation vertical padding and editorial text top inset. |
| 120px | Major section separation. |

### Containers and grids

- **content rail**: max width 1440px · side padding 40px. Centered desktop content rail; leaves 1360px for media and grids at the standard desktop width.
- **media text**: max width 628px. Support line and actions remain narrow over a much wider image.
- **paired campaign**: 2 columns · gap 24px. Two equal tall editorial media cards beneath a full-width scene.
- **benefit columns**: 4 columns · gap 0px. Four equal 340px desktop slots; copy occupies a narrower left-aligned portion of each slot.
- **story grid**: 3 columns · gap 24px. Three image-led editorial links with open white backing.
- **directory grid**: 4 columns · gap 24px. Four footer groups, with a separate app-link rail at the right.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 2px |
| editorial media | 3px |
| portrait video | 10px |
| search | 24px |
| benefit medallion | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| action hover | `0px 3.2px 7.2px rgba(0,0,0,0.133), 0px 0.6px 1.8px rgba(0,0,0,0.11)` | Temporary hover elevation on filled actions; resting surfaces stay flat. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and reading sections.

**CSS:** `background: #ffffff`

**Observed:** The same white field continues through the navigation, benefits, invitation and footer.

**Transfer:** Let photographic chapters create tonal changes rather than alternating arbitrary colored section backgrounds.

#### Editorial media frame · level 1

**Use:** Large image panels and paired campaign cards.

**CSS:** `border: 1px solid rgba(19,19,23,0.125); border-radius: 3px; position: relative; overflow: hidden`

**Observed:** Nearly square corners and a faint edge; text and actions sit in front of edge-to-edge imagery.

**Transfer:** Use it for a fully rendered scene, not a raised content box.

#### Merchandise tile · level 0

**Use:** Product selection ribbons.

**CSS:** `background: #f8f7f6; border: 1px solid #ffffff`

**Observed:** Adjacent warm pale tiles are separated by narrow white seams, without shadows.

**Transfer:** Use consistent backing across a product family so color and silhouette do the comparison.

#### Promotional strip · level 0

**Use:** A short announcement above primary navigation.

**CSS:** `background: #b4bec7; height: 56px`

**Observed:** Tiny centered copy and a close affordance at the far right.

**Transfer:** Give one concise announcement this treatment rather than introducing a new large accent field.

## Components

### Primary button

**Use:** The main action over a large media scene.

**CSS:** `background: #ffffff; color: #131317; border-radius: 2px; padding: 12px 24px; height: 48px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Bose Text 500 · 16px/1.5 · tracking 0.05em · uppercase

**Observed:** A plain text label with no compulsory icon; the button follows the support line in a left-aligned stack.

**States:** Declared: hover white background, near-black text and border, with 0px 3.2px 7.2px rgba(0,0,0,0.133), 0px 0.6px 1.8px rgba(0,0,0,0.11) shadow; focus-visible #005bff solid 2px outline inset by 2px; active rgba(19,19,23,0.06) background and no shadow.

**Transfer:** Keep it brief and choose one primary verb per scene.

### Dark button

**Use:** Conversion on a white surface, especially the closing invitation.

**CSS:** `background: #131317; color: #ffffff; border-radius: 2px; padding: 16px 24px; height: 48px; display: inline-flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `action` — Bose Text 500 · 16px/1.5 · tracking 0.05em · uppercase

**Observed:** The centered closing action reverses the light media button. Business inquiry scenes also use a dark variant against light product photography.

**States:** Declared: hover background #3e474a with white text and the action-hover shadow; focus-visible #005bff solid 2px outline with -2px offset; active rgba(19,19,23,0.06) background with near-black text and no shadow.

### Chevron text link

**Use:** Secondary discovery under a paragraph or benefit.

**CSS:** `color: #005bff; padding: 8px 0px; height: 40px; display: inline-flex; align-items: center`

**Text style:** `text-action` — Bose Text 500 · 16px/1.5 · tracking 0.05em

**Observed:** A small right chevron follows the words; no filled backing.

**States:** Declared: hover and active #00518a, no text decoration or filled background; focus-visible outline 0px with -2px offset.

**Transfer:** Use this smaller blue action in reading sections, not as the dominant control on saturated imagery.

### Navigation bar

**Use:** Persistent global wayfinding.

**CSS:** `background: #ffffff; height: 72px; padding: 0px 40px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — Bose Text 400 · 15px/1.2 · uppercase

**Observed:** Three short links at left, a centered wide wordmark, then a warm-gray search field and account, wishlist and cart line icons. The promotional strip sits above it; the full header is sticky.

### Search field

**Use:** Compact catalog search in the global navigation.

**CSS:** `background: #f1efee; border-radius: 24px; width: 343px; height: 40px; display: flex; gap: 12px`

**Observed:** A light field with a magnifier at the right; the surrounding utility area is visually subordinate to the centered identity.

### Product tile

**Use:** A repeated merchandise choice in a product ribbon.

**CSS:** `background: #f8f7f6; border: 1px solid #ffffff; width: 336px; min-height: 562px; display: flex; flex-direction: column`

**Text style:** `product-label` — Bose Text 500 · 18px/1.5 · tracking -0.02em

**Observed:** Wishlist heart at top right; isolated packshot first, then color name and circular swatches, a compact dark novelty badge where relevant, product name, star rating with blue review link, and price. Descriptions are not the primary content.

**Transfer:** Keep the silhouette and available finishes readable before showing specifications.

### Benefit medallion

**Use:** Visual anchor above a benefit heading.

**CSS:** `background: #f8f8f8; border-radius: 50%; width: 150px; height: 150px; padding: 50px; box-sizing: border-box; margin-bottom: 32px`

**Observed:** A simple black 50px pictogram is centered on a very pale circle; the text below is left-aligned, not centered with the circle.

**Transfer:** Choose familiar physical-service or feature symbols rather than detailed colored illustrations.

### Portrait video tile

**Use:** Social proof through short creator or customer clips.

**CSS:** `width: 300px; height: 533px; border-radius: 10px; position: relative; overflow: hidden; background-size: cover; background-position: 50% 50%`

**Observed:** Four portrait clips sit in a horizontal strip with 20px spaces, central play controls and a separate next chevron. A blurred duplicate image can back the clip; its blur is 20px at 0.6 opacity.

**Transfer:** Use real hands, environments and product usage; retain a natural phone-video feel instead of polishing every clip into advertising.

### Directory link

**Use:** Footer navigation groups.

**CSS:** `color: #40464b; display: flex`

**Text style:** `directory` — Bose Text 400 · 12px/16px

**Observed:** Small links sit beneath slightly stronger group names in four columns; social icons and a thin divider precede the final legal line.

**States:** Declared: hover #1e1e1e and underline.

**Transfer:** Keep this utility region small and typographic rather than turning it into another marketing panel.

### Question row

**Only for:** business inquiry pages

**Use:** Compact objection handling beneath benefit columns.

**CSS:** `border-top: 1px solid #cccccc; padding: 25px 0px; display: flex; justify-content: space-between; margin-bottom: 15px`

**Text style:** `question` — Bose Text 400 · 20px/1.35 · tracking -0.018em

**Observed:** Questions form a centered narrow column about 718px wide. A plus at the far right balances each single-line question; the resting appearance is flat and unboxed.

**Transfer:** Use brief purchasing or setup questions; keep long answers out of the closed row.

### Story card

**Only for:** company storytelling

**Use:** Related editorial routes near the end of a narrative.

**CSS:** `display: block; color: #131317`

**Text style:** `story-label` — Bose Text 500 · 25px/1.2

**Observed:** An approximately 437px by 292px rectangular photograph sits above a plain label with a 16px gap. No visible card border, shadow or filled caption area.

**Transfer:** Use three distinct contextual photographs of equal proportions.

## Imagery and graphics

### Immersive editorial scenes

**Use:** Opening and major feature chapters; the dominant visual device.

**Observed:** Large landscape media fills almost the whole content width. Tight portraits, cropped products and tactile interiors share controlled directional light, true material detail and dark lower regions that support white copy. Subjects occupy far more area than text.

**Transfer:** Make a product-specific studio or lifestyle scene with an unmistakable silhouette and room at the lower left for text. A carefully lit still-life with one hero object is the minimum equivalent when people or video are unavailable.

### Isolated packshots

**Use:** Product ribbons and comparison choices.

**Observed:** Three-quarter product renders float without scenery on warm off-white tiles, with enough air to separate complex shapes. Colors range from pale pink and mint to dark brown and black; these are product finishes rather than interface accents.

**Transfer:** Render consistent angles and lighting for every choice, keeping color variation in the objects rather than tinting each tile.

### Everyday portrait clips

**Use:** The horizontal social-proof gallery.

**Observed:** Phone-format clips show users, hands holding products, flowers, travel interiors and casual picnic arrangements. Natural light, visible surroundings and embedded captions contrast with the polished campaign scenes.

**Transfer:** Collect real usage clips with varied contexts and retain their human irregularity while using uniform portrait frames.

### Outline product campaign

**Only for:** promotional sale campaigns

**Use:** A distinctive illustrated opening variant.

**Observed:** Mint-green technical outlines of differently scaled products float on a rich green field that becomes deep teal toward the bottom. Large objects are cut by the top and side edges; speaker grilles use regular dot arrays. The lower-left area is quieter for white copy.

**Transfer:** Draw the new product's own silhouette and material details as a sparse technical constellation, preserving the oversized cropping and low text zone.

**Build:** Use an SVG viewBox 0 0 1440 747. Layer a vertical green-to-deep-teal gradient behind three to five original product contour groups. Use thin pale-green strokes at varied opacity, no solid object fills; repeat small circles inside grille or vent masks. Scale one group to roughly a third of the canvas width and crop two groups at the edges. Fade outlines beneath the text with a transparent-to-dark lower overlay.

### Monochrome product plinths

**Only for:** business inquiry campaigns

**Use:** A commercial-service hero illustration.

**Observed:** Blue products sit on stacked blue rectangular platforms against a matching blue studio wall, with soft shadows and open negative space at left. Another scene uses personalized products on a very light neutral backing.

**Transfer:** Use a small stepped arrangement in one restrained tonal family to make customization or product tiers tangible; let real material highlights separate objects from their platforms.

### Archival and contextual photography

**Only for:** company storytelling

**Use:** Origin chapters, leadership and related-story links.

**Observed:** Black-and-white archival portraits and chalkboard scenes are paired with text; a formal portrait has a dark neutral background. Related links use landscape images of people at work, outdoor scenery and product-in-hand details.

**Transfer:** Mix original archive material with contemporary human photography. Use monochrome only for historical material, not as a global desaturation filter.

### Dark product demonstration

**Only for:** immersive product comparison pages

**Use:** Feature explanation and direct choice between two models.

**Observed:** A near-black continuous field holds oversized floating product renders, alternating offset image/text columns, saturated green and yellow usage scenes, and full-bleed close-ups. A gray ear model shows a localized cyan glow at the point of operation. Color chapters use huge diagonally cropped products against smoky dark gradients.

**Transfer:** Explain one mechanism through a close-up model and one localized light cue. If advanced animation is unavailable, use a static sectional render with the same focal point and short benefit copy.

**Build:** For the mechanism cue, place a small cyan radial glow at the interaction point on a grayscale model. Layer a compact bright core with two softer transparent cyan ellipses clipped to the relevant anatomy or product surface; keep the rest of the scene gray and black. Preserve textured photographic detail rather than replacing the mechanism with a page-wide glow.

### Icons

**Observed:** Global utilities are thin black outline symbols. Benefit pictograms are larger and centered in pale circles; play controls use a simple white triangle on a dark translucent disk. Ratings use compact filled stars.

**Transfer:** Use a consistent outline icon family for navigation and benefits; reserve filled shapes for play, ratings and a few simple emphasis symbols.

## Section recipes

How recurring sections are built.

### First screen: Full-width media opening

**Observed:** A 56px blue-gray promotional strip and 72px white Navigation bar precede a 747px full-width Editorial media frame. Back to front: rich campaign image, quieter dark lower area, then a lower-left white display headline, support line and Primary button. Imagery occupies the majority of the screen; the text stack has 40px side and 48px bottom breathing room, 16px internal gaps and a support measure of 628px. At 900px height the complete headline, support, button and main product artwork are visible, while only the beginning of the 88px category strip appears; product-grid content is below the fold.

**Transfer:** Use the same lower-left composition with a strong new product scene. Without campaign artwork, create an oversized lit still-life with deliberate negative space for copy. A business inquiry page can start with a short text introduction before an inset scene; company storytelling can open with an uncaptioned immersive human portrait; an immersive comparison can center its promise low over full-bleed video.

**Avoid:** Do not replace this opening with a small centered product thumbnail, a floating white text card or a symmetrical software-style two-column hero.

**Text style:** `display` — Bose Headline 900 · 60px/53px · tracking 0.02em

### Merchandise ribbon

**Observed:** A left-aligned heading introduces four Product tiles on the 40px content rail. Warm pale backings meet at narrow white seams; the product photograph leads the information order.

**Transfer:** Use a short related assortment or a small family of variants. Preserve consistent packshot scale and information order.

**Text style:** `heading` — Bose Headline 900 · 60px/53px · tracking 0.02em

### Campaign mosaic

**Observed:** One broad Editorial media frame is followed by two equal tall frames separated by 24px. Each anchors a short display title, supporting sentence and Primary button toward the lower left. Main panels are about 755px tall at desktop.

**Transfer:** Use one principal product promise and two distinct situations, rather than repeating the same image with changed copy.

**Text style:** `display` — Bose Headline 900 · 60px/53px · tracking 0.02em

### Heading and social gallery

**Observed:** A heading and 18px body line are followed by a strip of four Portrait video tiles. The body line is 12px below the heading; the media begins after a substantial breathing gap.

**Transfer:** Bring in user-scale proof after polished product imagery. Keep the gallery recognizably social and portrait-oriented.

**Text style:** `heading` — Bose Headline 900 · 60px/53px · tracking 0.02em

### Four benefit columns

**Observed:** A section heading sits above four open white columns. Each begins with a Benefit medallion, followed by a condensed benefit-heading, a short body description and a Chevron text link. Major sections are separated by 120px.

**Transfer:** Translate actual purchase reassurance or distinctive capabilities into four compact ideas, without enclosing each one in a card.

**Text style:** `heading` — Bose Headline 900 · 60px/53px · tracking 0.02em

### Billboard invitation and directory

**Observed:** The White canvas continues into a centered closing-invitation headline with 64px vertical padding and a Dark button 24px below. A small terms line sits lower, then four quiet directory groups with an app rail, social icons, a thin divider and a final legal line. This closing treatment is shared even after a dark product experience.

**Transfer:** Make one short invitation to a relevant ongoing relationship or conversion, then let utility links finish the page without another visual campaign.

**Text style:** `closing-invitation` — Bose Headline 900 · 60px/41px · tracking 0.02em

### Process and objections

**Only for:** business inquiry pages

**Observed:** A three-column numbered process uses condensed 32px headings and regular 18px paragraphs. Later, Question rows occupy a centered narrow column; a broad 46px condensed customer quote with a small attribution provides proof. Longer explanatory copy follows on white before the shared close.

**Transfer:** Explain how to engage, remove practical concerns and support the promise with a real quotation. Keep process steps, questions and testimonial visually distinct.

**Text style:** `heading` — Bose Headline 900 · 60px/53px · tracking 0.02em

### Editorial split and monumental chapter

**Only for:** company storytelling

**Observed:** Equal-width text and tall photographic columns sit on the 40px rail, with 64px top padding on the text side. An inset full-width archival scene carries the heritage-display title and light action. Related Story cards create a three-column exit before the closing invitation.

**Transfer:** Pair a concise origin or craft narrative with authentic imagery, then give one short chapter title exceptional scale.

**Text style:** `heritage-display` — Bose Headline 900 · 110px/96px · tracking 0.015em

### Immersive comparison chapters

**Only for:** immersive product comparison pages

**Observed:** An opening portrait scene gives way to paired floating renders on dark backing. Full-bleed fit and mechanism scenes alternate with offset, narrower image/text pairs. Short headings act as chapter markers, and individual phrases receive colored emphasis matching the scene. Small rounded white Shop controls belong to this dark experience rather than the default rectangular interface.

**Transfer:** Use a continuous dark product story for a focused two-option comparison. End the story with paired product images, swatches, prices, actions and vertically aligned icon/specification rows, then return sharply to the white shared close.

## Page flow

**Storyline:** Image-led promise → product choices or feature chapters → human or practical proof → reassurance → centered invitation → quiet utility directory.

### Retail marketing landing page

1. **Promise** — Full-width campaign media with lower-left title and one action, followed by category shortcuts.
2. **Product choices** — Four pale merchandise tiles.
3. **Capability chapters** — Large image mosaic translating products into situations.
4. **Human proof** — Portrait social-video strip.
5. **Reassurance** — Open icon-led benefits and a final broad lifestyle scene; a small notice stays typographic.
6. **Closing call** — Centered invitation, dark action and full utility directory.

**Transfer:** Use the media-and-proof contrast as the default landing-page language, without requiring the same number or order of chapters.

### Immersive two-product comparison

1. **Promise** — Centered benefit headline low over a full-bleed portrait video.
2. **Product demonstration** — Paired floating renders lead into fit, comfort and mechanism chapters.
3. **Differentiation** — Offset feature imagery and oversized color renders on a continuous dark field.
4. **Decision support** — Two aligned product choices with price, swatches, small Shop controls and icon-led specification rows; footnote below.
5. **Closing call** — Hard transition from dark comparison to the shared white invitation and directory.

**Transfer:** Separate emotional demonstration from final side-by-side buying facts; keep this immersive dark variant scoped to focused product experiences.

### Business inquiry landing page

1. **Context** — Short text introduction before a tonal studio hero and quote action.
2. **Process** — Three numbered columns explain engagement.
3. **Capability** — A second product scene demonstrates customization.
4. **Reassurance** — Four icon-led benefits followed by narrow question rows.
5. **Social proof** — Broad condensed quotation and attribution.
6. **Objection handling** — Longer plain-text program explanation precedes the shared centered invitation and directory.

**Transfer:** Use the white, service-oriented variant for a complex buying journey; show the engagement process before deep explanatory text.

### Company narrative

1. **Emotional promise** — Full-width human portrait and category navigation.
2. **Origin** — Text-and-archive split with a short quotation.
3. **Historical proof** — Large archival image with a monumental short title.
4. **People** — Leadership portrait and understated text link.
5. **Related routes** — Three plain image-and-label cards.
6. **Closing call** — The same centered invitation and compact directory.

**Transfer:** Carry the poster typography and expansive media into an editorial narrative, using archive and people imagery instead of merchandise density.

## Writing

Assured, sensory and approachable. Big promises are phrased as direct human benefits, while practical details are explained without inflated technical language.

**Do not copy:** Do not reuse Bose names, logos, campaign art, product names, founder or customer quotations, proprietary claims, discounts, prices, performance numbers or service guarantees. Write original equivalents supported by the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your life; use we sparingly for service commitments. Product names appear in supporting copy and commerce tiles rather than burdening every headline.
- **Rhythm:** Short punchy headlines often split into two beats. Supporting sentences are longer but stay focused on one benefit; practical columns use straightforward sentences and action labels are very short.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Media headline | A sensory or behavioral promise, often two terse clauses. | 3–8 words | “Go all in. Never tune out.”<br>“Cinema sound. Made simple.” |
| Support | Connect the product to a recognizable moment rather than restating the headline. | 8–20 words | “From movie night to music listening, enjoy more with the [Brand] TV Speaker (2nd Gen).” |
| Section lead | Plain signpost or a compact emotional theme. | 2–6 words | “Trending products”<br>“Sound is Power” |
| Reassurance | Direct benefit followed by a short concrete explanation. | One brief sentence | “Try it for 30 days to make sure it’s right for you.” |
| Action | Verb first, no rhetorical flourish. | 1–3 words | “BUY NOW”<br>“REQUEST QUOTE”<br>“Read our history” |

**Words and phrasing to use:** your everyday; more of the moment; made simple; stay open; power; enjoy; try; learn more

**Avoid:** revolutionary ecosystem; paradigm-shifting; unlock limitless possibilities; overloaded engineering jargon; formal corporate throat-clearing

**Rules:**

- Lead with how the product changes a moment; explain the mechanism in its own chapter.
- Use sentence case for headlines and uppercase visual styling for filled action labels.
- Separate a short emotional headline from the practical product identification in supporting copy.
- Let commercial information be direct and specific; do not turn every benefit into an exclamation.

## Do's and Don'ts

### Do

- Keep the default 60px condensed headline paired with a calmer 24px/36px support line.
- Use 40px outer rails and 120px between major inset sections.
- Anchor scene text low and left with a narrow 628px support measure.
- Keep default filled actions 48px high with 2px corners.
- Use #005bff for small links and focus outlines against neutral interface surfaces.
- Use the same pale #f8f7f6 backing across a merchandise ribbon.
- Retain the centered 60px closing invitation even when the main narrative uses a dark theme.
- Give portrait social clips a consistent 300px by 533px frame and 10px radius.

### Don't

- Do not replace the condensed headline face with a wide geometric bold font.
- Do not add resting drop shadows to merchandise tiles or editorial image panels.
- Do not round default rectangular buttons into pills; rounded Shop controls belong to the immersive comparison variant.
- Do not tint every section with a different product-finish color.
- Do not make body paragraphs as heavy or as tightly led as the display headlines.
- Do not center all benefit copy beneath its circular icon; the benefit columns are left-aligned.
- Do not turn the footer into a dark, oversized branded billboard; its directory is white and compact.
- Do not make all imagery polished studio work; retain the contrast between campaign scenes and everyday portrait clips.

## Motion and responsive

### Motion

**Observed:**

- Filled actions and blue links declare 0.3s linear transitions.
- The sticky header declares transform 0.5s; the category strip declares a 0.3s transition.
- Portrait media includes visible play controls; immersive media includes pause or replay affordances.

**Transfer:**

- Keep control feedback restrained; use media playback, rather than decorative moving interface elements, for the expressive layer.
- Preserve an explicit play or pause affordance on large video scenes.

**Unknown:**

- Exact video sequencing, scroll-trigger timing and animation curves for the immersive scenes are not specified.

### Responsive

**Observed:**

- Heading size declares clamp(2.875rem, 2.625rem + 1.25vw, 3.75rem); heading line height also uses a clamp.
- CSS includes major breakpoint families around 544px, 768px, 992px and 1200px.

**Transfer:**

- On narrow layouts, preserve a large media stage with readable lower text rather than shrinking the whole desktop composition.
- Let product ribbons and portrait clips remain horizontally browsable; stack paired editorial scenes and reduce benefit columns before compressing their copy.

**Unknown:**

- Mobile column counts, exact side rails, navigation behavior and alternate image framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
