# Bumble — sunny card theatre

## Overview

A bright, people-first style that pairs sunny yellow with charcoal lettering and open white space. Rounded sans-serif typography, candid lifestyle photography and overlapping portrait cards make it feel sociable and optimistic rather than technical. It suits consumer products and community-led services, with spacious storytelling and compact, approachable controls.

### Essentials

- Brand lettering becomes a stage rather than a conventional headline: an almost full-width, 1360×286px wordmark sits behind three overlapping portrait planes on an 811px yellow opening.
- Friendly headings retain a firm silhouette: BumbleSans at 68px/70px, weight 600 and 0.5px tracking; paragraphs are 20px/25px with 0.3px tracking.
- Sunshine arrives in substantial blocks, not confetti: #ffdb5b fills the opening, a product card and the closing conversion panel; white carries the explanatory stretches, with #fff386 distinguishing a sibling offering.
- Controls are soft rectangles, not capsules: charcoal primary buttons are 50px tall with 16px corners and 14px 24px padding; the floating navigation uses translucent white and the same corner family.
- Photography behaves like a deck of people: a 368×461px front portrait overlaps two progressively smaller portraits, with vertical yellow pill labels; retain a layered human or real-use photo deck even when no product imagery exists.
- Large content panels feel lightly upholstered: 24px corners, 40px inset, a 1px charcoal-at-8% edge and a restrained 0px 1px 8px shadow; the closing yellow panel pairs a direct action with oversized product imagery.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sun yellow | `#ffdb5b` | `--color-sun` | background, surface, accent | Opening field, primary offering cards, portrait badges and conversion panels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light lemon | `#fff386` | `--color-lemon` | surface | Sibling offering card, kept within the yellow family instead of adding another brand hue. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#202020` | `--color-ink` | text, action, border | Primary lettering, solid conversion buttons and dark iconography. |
| Soft charcoal | `#343333` | `--color-badge-ink` | text | Vertical portrait labels. |
| Subdued gray | `#575656` | `--color-muted` | text | Footer column headings. |
| Soft edge | `#ededed` | `--color-edge` | border | Visible charcoal-at-8% hairline over white; use rgba(32,32,32,0.08) so the same edge adapts to yellow and gray. |
| Soft gray | `#f3f3f3` | `--color-panel` | surface | Large image-and-copy feature panel. |
| Near white | `#fcfcfc` | `--color-media` | surface | Backing within product media stages. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, image stages and reversed button text. Navigation uses white at 80% opacity, appearing creamy over yellow and white over the canvas. |

## Typography

- **BumbleSans** — All marketing headings, prose, labels and controls. Rounded, open sans-serif with friendly geometric forms and a sturdy semibold cut. If unavailable, use **DM Sans**. Use weights 400, 500 and 600; preserve open counters and the slightly positive tracking. Font stack: "BumbleSans", "DM Sans", BumbleSansFallback, -apple-system, "San Francisco", "Helvetica Neue", Roboto, "Segoe WP", "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | BumbleSans | 600 | 68px | 70px | 0.0068em | Large promise, feature and closing headings, in sentence case. |
| quote | BumbleSans | 600 | 49px | 55px | 0.0086em | Editorial testimonial statement, larger than prose but subordinate to section headings. |
| portrait-label | BumbleSans | 400 | 40px | 1 | normal | Vertical label on the leading portrait; trailing cards reduce this to 34px and 24px with matching line heights. |
| card-heading | BumbleSans | 600 | 34px | 1 | 0.0118em | Offering names beneath their media stages. |
| body | BumbleSans | 400 | 20px | 1.25 | 0.016em | Support paragraphs, card descriptions and quote attribution. |
| footer-link | BumbleSans | 500 | 20px | 1.25 | 0.016em | Footer destination links and compact conversion-widget copy. |
| action | BumbleSans | 500 | 17px | 22px | 0.0165em | Solid primary button labels. |
| navigation | BumbleSans | 500 | 17px | 20px | 0.0176em | Header navigation items. |
| text-link | BumbleSans | 400 | 17px | 1.5 | normal | Underlined offering-card links. |
| caption | BumbleSans | 400 | 15px | 20px | 0.02em | Subdued footer category labels. |
| utility-link | BumbleSans | 500 | 15px | 20px | 0.02em | Compact utility navigation in the footer. |

**Notes:**

- Semibold headings and regular paragraphs share a single family; positive tracking remains slight rather than tightening into a dense display style.
- The opening's monumental lettering is wordmark artwork, not the 68px heading recipe. Keep that distinction: large identity artwork for the stage, sentence-case headings for explanation.
- No eyebrow is needed above the principal section headings; hierarchy comes from scale, adjacency and space.

## Layout

**Density:** Airy storytelling with compact controls: large photographs and short text groups are separated by clear white gutters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-icon and optional button-content gaps. |
| 12px | Compact conversion-widget inset and utility-link row gaps. |
| 16px | Card heading-to-description and description-to-link gaps; footer destination rows. |
| 20px | Offering-card inset and promise heading-to-support gap. |
| 24px | Media-to-card-copy gap and quote-to-attribution gap. |
| 34px | Copy-group to primary action gap. |
| 40px | Main side gutters, section separation and large-panel inset. |
| 48px | Quote-to-image horizontal separation. |

### Containers and grids

- **page**: max width 1440px · side padding 40px. Centered desktop composition; the opening color field spans the full width.
- **inset panels**: max width 1360px · side padding 40px. Large rounded feature and conversion panels within the page gutters; padding is the panel's inner inset.
- **offering pair**: 2 columns · gap 40px. Equal 660px-wide offering cards at the desktop width.
- **promise split**: 2 columns · gap 20px. Text on the left and an overlapping portrait deck on the right; copy begins 60px inside its column.

## Corner radius

| Element | Radius |
| --- | --- |
| controls and portraits | 16px |
| panels and media stages | 24px |
| portrait badges | 9999px (pill) |
| QR backing | 9px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| panel lift | `0px 1px 8px 0px rgba(32,32,32,0.12)` | Large gray and yellow panels and the footer conversion widget; not every offering card. |

### Surfaces

#### White canvas · level 0

**Use:** Long-form storytelling and footer.

**CSS:** `background: #ffffff`

#### Yellow stage · level 0

**Use:** Immersive opening identity stage.

**CSS:** `background: #ffdb5b`

**Observed:** Edge-to-edge flat color behind monumental lettering and photographic planes.

**Transfer:** Use the brand-yellow field as the dominant opening color rather than scattering small yellow accents.

#### Soft feature panel · level 1

**Use:** A self-contained image-and-copy chapter.

**CSS:** `background: #f3f3f3; border: 1px solid rgba(32,32,32,0.08); border-radius: 24px; box-shadow: 0px 1px 8px 0px rgba(32,32,32,0.12); padding: 40px`

**Observed:** Broad, low-contrast rounded panel; the photo and text sit side by side without nested card chrome.

**Transfer:** Contain a meaningful participation or capability chapter without making it look like a dashboard.

#### Yellow conversion panel · level 1

**Use:** High-visibility conversion chapter.

**CSS:** `background: #ffdb5b; border: 1px solid rgba(32,32,32,0.08); border-radius: 24px; box-shadow: 0px 1px 8px 0px rgba(32,32,32,0.12); padding: 40px; overflow: hidden`

**Observed:** Large product media is cropped against the panel's bottom edge.

**Transfer:** Pair one easy next step with a large tangible view of the product or its outcome.

#### Frosted navigation · level 2

**Use:** Persistent menu and language control over changing page backgrounds.

**CSS:** `background: rgba(255,255,255,0.8); border: 1px solid rgba(32,32,32,0.08); border-radius: 16px; backdrop-filter: blur(16.9px)`

**Observed:** Separate floating islands rather than a fully filled header bar.

**Transfer:** Keep translucency restricted to navigation controls; the rest of the page uses opaque surfaces.

## Components

### Floating navigation

**Use:** Persistent primary destinations.

**CSS:** `display: flex; align-items: center; gap: 16px; background: rgba(255,255,255,0.8); border: 1px solid rgba(32,32,32,0.08); border-radius: 16px; backdrop-filter: blur(16.9px)`

**Text style:** `navigation` — BumbleSans 500 · 17px/20px · tracking 0.0176em

**Observed:** Centered island with five destinations; a small identity mark sits separately at left and a language control at right. The header stays fixed during scrolling.

**Transfer:** Use a similarly short destination set; preserve separation between identity, navigation and utility controls.

### Navigation item

**Use:** Individual destination inside the floating navigation.

**CSS:** `display: flex; align-items: center; padding: 14px 22px; height: 50px; box-sizing: border-box; border: 1px solid transparent; color: #202020`

**Text style:** `navigation` — BumbleSans 500 · 17px/20px · tracking 0.0176em

**Observed:** A simple text label with no persistent active-colored fill.

**States:** Declared: hover background #ffffff, border 1px solid rgba(32,32,32,0.08), border-radius 16px.

### Primary button

**Use:** Main conversion or continuation action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #202020; color: #ffffff; border-radius: 16px; padding: 14px 24px; height: 50px; box-sizing: border-box`

**Text style:** `action` — BumbleSans 500 · 17px/22px · tracking 0.0165em

**Observed:** One action follows each main copy group; widths fit the label rather than stretching across the column.

### Offering card

**Use:** Introduce one of two parallel products or use cases.

**CSS:** `display: flex; flex-direction: column; gap: 24px; background: #ffdb5b; color: #202020; border: 1px solid rgba(32,32,32,0.08); border-radius: 24px; padding: 20px; overflow: hidden`

**Text style:** `card-heading` — BumbleSans 600 · 34px/1 · tracking 0.0118em

**Observed:** Media first, title second, descriptive paragraph third and underlined link last. The sibling card uses light lemon. These cards have no visible drop shadow.

**Transfer:** Make the alternatives equally prominent and keep the second color a close yellow relative.

### Underlined card link

**Use:** Low-chrome continuation within offering cards.

**CSS:** `display: inline-flex; align-items: center; height: 50px; color: #202020; text-decoration: underline`

**Text style:** `text-link` — BumbleSans 400 · 17px/1.5

**Observed:** Left-aligned below the description, without a button background or arrow.

### Portrait badge

**Use:** Attach a short attribute to a portrait deck.

**CSS:** `position: absolute; padding: 20px 10px; border-radius: 9999px; background: #ffdb5b; color: #343333; writing-mode: vertical-rl; text-align: center`

**Text style:** `portrait-label` — BumbleSans 400 · 40px/1

**Observed:** Pinned near the leading photo's upper-right edge. Successive labels shrink with the rear cards.

**Transfer:** Use one short human-readable trait, not a multi-line pitch.

### Language control

**Use:** Compact header and footer utility.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 8px; padding: 12px 24px; width: 104px; height: 50px; box-sizing: border-box; background: rgba(255,255,255,0.8); border: 1px solid rgba(32,32,32,0.08); border-radius: 16px; backdrop-filter: blur(16.9px)`

**Observed:** Globe icon followed by a downward chevron, with an accessible language label. Footer variant has a solid charcoal outline.

### Footer destination

**Use:** Primary footer navigation.

**CSS:** `color: #202020; display: inline-block`

**Text style:** `footer-link` — BumbleSans 500 · 20px/1.25 · tracking 0.016em

**Observed:** Plain destination text in columns; external destinations carry a northeast arrow. Despite link underline styling, resting links read as unruled text.

**States:** Declared: hover color #202020; color transition 0.2s.

### Compact conversion widget

**Use:** Repeat the conversion path at the bottom of the footer.

**CSS:** `display: flex; align-items: center; gap: 15px; background: #ffdb5b; border: 1px solid rgba(32,32,32,0.08); border-radius: 16px; box-shadow: 0px 1px 8px 0px rgba(32,32,32,0.12); padding: 12px`

**Text style:** `footer-link` — BumbleSans 500 · 20px/1.25 · tracking 0.016em

**Observed:** A white-backed QR code sits at left and a short instruction wraps at right; desktop widget is 338×184px.

**Transfer:** For an app use a genuine scannable destination; for other products use a similarly compact actionable access panel.

### QR tile

**Use:** Readable access code on yellow surfaces.

**CSS:** `background: #ffffff; border-radius: 9px; padding: 14px; width: 218px; height: 218px; box-sizing: border-box`

**Observed:** Large variant contains a 190px code. The compact footer version is 158px square with 12px inset.

**Transfer:** Retain the white quiet area and strong charcoal contrast; keep any center emblem small enough for scanning.

## Imagery and graphics

### Monumental identity and portrait fan

**Use:** Signature opening artwork.

**Observed:** A charcoal wordmark nearly spans the page, behind three upright rounded photo planes. The largest portrait is near the center-left; two narrower planes step toward the right and recede in size. Perspective makes the photo edges angle like standing cards. Saturated, candid faces and natural light counterbalance the flat yellow field.

**Transfer:** Use the new identity as original lettering with a three-plane deck of real users or real-world product outcomes. If custom motion or 3D assets are unavailable, a static perspective fan of three original photographs is the minimum equivalent.

**Build:** Place a dark SVG wordmark in a 1360×286px centered layer inside an 811px yellow section. Overlay three clipped rounded photographic planes in a perspective wrapper; make the front plane about 330px wide and 650px tall, and step the rear planes down in size and to the right. Use CSS perspective around 1200px and rotateY around -20deg as a starting construction, adjusting angles to keep faces readable. Keep the deck above lettering and below navigation; use no glow or decorative texture.

### Stepped portrait deck

**Use:** Image partner for the main promise.

**Observed:** Three natural-light outdoor lifestyle portraits at 368×461px, 313×392px and 258×323px overlap horizontally. The front image is largest, subsequent images are vertically centered and partially hidden. All have 16px corners and a vertical yellow label near the right edge.

**Transfer:** Show three different people or use contexts with similar light and candid expressions. Keep the descending scales and visible vertical labels rather than replacing the deck with three equal tiles.

**Build:** Use a positioned wrapper about 588px wide and 461px tall. Place three object-fit cover images in increasing z-order toward the front; align their vertical centers and overlap the rear images behind the front. Add vertical-rl yellow capsules with 20px 10px padding near each top-right edge; use 40px, 34px and 24px label text.

### Editorial photo with circular seal

**Use:** A large feature panel with a human invitation.

**Observed:** Warm restaurant photography shows two people laughing over a meal. The 599×618px image has softly rounded corners; a flat yellow circular seal overlaps its lower-left area, approximately 208px square.

**Transfer:** Use a genuine scene showing the benefit in progress, with an original circular program or feature seal. Warm ambient color stays in the photo, not as a page-wide filter.

**Build:** Create a transparent SVG seal with two yellow circular strokes and uppercase text on a circular textPath. Put a simple original emblem at center and position the 208px seal over the lower-left photo area. Avoid shadow, bevel or distressed texture.

### Product collage stage

**Use:** Offering cards and closing conversion artwork.

**Observed:** Real product screens and portrait photographs are layered within white or near-white media wells. Offering media measures 618×329px with 24px clipping. The closing panel uses three tall phone mockups, one dominant in front and two angled behind, cropped at the bottom.

**Transfer:** Use authentic views of the new product, arranged as a small scene rather than a full dashboard screenshot. For a physical product, substitute three cleanly cut-out views with the same scale hierarchy and bottom crop.

### Testimonial portrait

**Use:** Image beside a large customer quotation.

**Observed:** A 555×520px, object-fit cover image sits to the right of the quotation with 16px rounded clipping.

**Transfer:** Choose a credible, warm customer portrait or contextual customer photograph and keep the quote at least as prominent as the image.

### Icons

**Observed:** Small dark icons are 22–24px; utility chevrons and external arrows use simple strokes with rounded ends, around 2px wide. Social marks sit unboxed in a horizontal footer row.

**Transfer:** Choose a consistent simple outline set for utilities and external arrows. Reserve filled icons for familiar social marks; do not turn features into a colorful icon grid.

## Section recipes

How recurring sections are built.

### First screen: Identity theatre opening

**Observed:** An 811px-tall yellow stage fills almost the first screen. Layers run from flat yellow to a 1360×286px charcoal identity wordmark, then a central perspective fan of three rounded portraits, then the fixed floating navigation. Lettering occupies nearly the entire width with 40px side gutters and is deliberately obscured by the deck. The deck extends from beneath the menu down toward the lower edge of the stage. Within the first 900px the identity, portraits and navigation are visible, followed by a thin start of the white canvas. There is no supporting paragraph or conversion button in this opening; the 68px explanatory heading and primary action are below the fold.

**Transfer:** Start a new marketing page with its own monumental identity or short original word sculpture and three real-use photo planes. Keep the explanatory promise in a subsequent split section. A focused product page can use a short product name as the stage lettering while retaining the same media overlap and navigation islands.

**Avoid:** Do not turn the opening into a centered 68px headline with a paragraph and two buttons, or move the entire photo deck below the lettering.

**Text style:** `heading` — BumbleSans 600 · 68px/70px · tracking 0.0068em

### Promise beside a portrait deck

**Observed:** A 618px white section pairs a left-aligned heading and support paragraph with the Stepped portrait deck on the right. The heading occupies roughly half the width and wraps into three short lines; support begins 20px below it and a Primary button follows after 34px. Text and imagery are vertically centered.

**Transfer:** State the human outcome in a short sentence, then connect it to a few visible use contexts through portrait labels.

**Text style:** `heading` — BumbleSans 600 · 68px/70px · tracking 0.0068em

### Image-led invitation panel

**Observed:** Soft feature panel is 1360×700px, with a nearly square photograph on the left and vertically centered copy on the right. A circular seal overlays the photo. The heading is followed by 16px of space, one or two body paragraphs, then a Primary button after 34px.

**Transfer:** Use for participation, a key capability or a service invitation. Retain the photo-and-seal device without requiring any particular program topic.

**Text style:** `heading` — BumbleSans 600 · 68px/70px · tracking 0.0068em

### Parallel offering cards

**Observed:** Two Offering cards fill a two-column grid with 40px gap. Each starts with a white media stage, then a 34px title, 20px description and Underlined card link. Media consumes about three fifths of each card's height. The backgrounds alternate sun yellow and light lemon.

**Transfer:** Use for two related offerings, audiences or jobs to be done; maintain equal visual weight instead of implying a pricing winner.

**Text style:** `card-heading` — BumbleSans 600 · 34px/1 · tracking 0.0118em

### Oversized customer voice

**Observed:** A white 600px section has a 757px quote area and 555×520px image with 48px between. The 49px semibold quotation is left-aligned, followed by 24px to attribution and 34px to a Primary button.

**Transfer:** Use one specific human statement with a concise attribution rather than a grid of small testimonials.

**Text style:** `quote` — BumbleSans 600 · 49px/55px · tracking 0.0086em

### Bright conversion and spacious footer

**Observed:** Yellow conversion panel is 1360×450px. A 68px heading, one body line and large QR tile occupy the left; three oversized phone screens occupy the right and meet the lower clipping edge. The white footer follows immediately, padded 40px: a 300×63px wordmark at left, three destination groups on the right, then a lower row with Compact conversion widget at left, social icons near the middle and Language control at right. Destination text is 20px; utility links and category labels are 15px.

**Transfer:** Make the final action tangible and low-effort, supported by a large product view. Preserve the white, open footer and repeated compact conversion path rather than ending on a dark legal strip.

**Text style:** `heading` — BumbleSans 600 · 68px/70px · tracking 0.0068em

## Page flow

**Storyline:** identity spectacle → human promise → invitation or capability → parallel paths → customer voice → tangible next step → useful destinations

### A consumer marketing landing page that creates emotional recognition before explaining the offer

1. **Identity hook** — Full-width yellow theatre with monumental lettering and a portrait fan.
2. **Promise** — Large outcome heading beside a labeled portrait deck, with a single action.
3. **Participation or capability** — Soft gray image-and-copy panel with a circular seal and a focused action.
4. **Choice** — Two yellow-family offering cards with product collages and text links.
5. **Social proof** — One oversized customer quotation paired with a portrait.
6. **Closing call** — Bright inset conversion panel, readable access code and large product mockups.
7. **Navigation and reassurance** — White footer with a large identity mark, grouped links, repeated access widget, social marks and language utility.

**Transfer:** Borrow the escalation from emotional identity to clear benefit, proof and an easy next step. Rearrange the explanatory chapters to fit the offer while keeping the signature lettering-and-photo theatre, labeled deck and bright tangible conversion device.

## Writing

Warm, optimistic and straightforward. It treats the product as a helpful route to a meaningful personal outcome, using assured invitations rather than pressure or technical grandstanding.

**Do not copy:** Do not reuse Bumble names, wordmarks, program seals, personal names, customer quotations, product claims or relationship outcomes. Write original claims supported by the new product and use original imagery and identity assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for purpose and you or your for invitations and choices. Name the product when distinguishing offerings; otherwise focus on the reader's desired outcome.
- **Rhythm:** Short sentence-case headings, often 3–9 words, lead into one or two plain-language sentences. Longer invitations can use two short paragraphs. Actions are usually 2–3 words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Purpose heading | A direct shared-purpose statement, with the desired human outcome at the end. | 6–10 words | “We exist to bring people closer to love.” |
| Invitation heading | An uncomplicated verb plus something the reader can contribute. | 3–5 words | “Share your ideas” |
| Supporting line | Explain a meaningful benefit with warm, concrete emotional language. | One sentence, around 15–25 words | “We want our members to find meaningful and authentic relationships that ignite confidence and joy.” |
| Choice description | Recognize two familiar situations before explaining how the offering helps. | One sentence, around 25–35 words | “Whether you’ve moved to a new city or just want to expand your circle, BFF makes it easy to meet like-minded people who match your vibe.” |
| Primary action | Plain verb and destination; no cleverness that hides the action. | 2–3 words | “Download [Brand]”<br>“Sign up”<br>“Read more stories” |
| Closing instruction | Make the mechanics feel easy and immediate. | One short sentence | “Just scan the QR code to get started.” |

**Words and phrasing to use:** closer to; meaningful; authentic; confidence; joy; your; help shape; find; get started

**Avoid:** disruptive; revolutionary; unlock synergies; dominate; limited time only; guaranteed happiness

**Rules:**

- Lead with an everyday human outcome before listing mechanisms.
- Use inviting verbs and specific next steps, not urgency.
- Keep offering descriptions inclusive of both newcomers and returning users.
- Let quotations carry personal enthusiasm; keep surrounding marketing language composed.

## Do's and Don'ts

### Do

- Use 68px/70px semibold headings for major explanatory chapters.
- Keep primary controls at 50px high with 16px corners.
- Preserve 40px desktop page gutters and section separations.
- Use 24px corners for large panels and offering media wells.
- Let the foreground portrait visibly overlap two smaller rear portraits.
- Keep the closing product artwork large enough to meet the panel's bottom edge.
- Give testimonial text its own 49px/55px display treatment.
- Keep the footer white with substantial open space around its identity mark.

### Don't

- Do not apply negative tracking to the 68px headings; the recipe uses 0.5px.
- Do not make primary buttons yellow-on-white or fully pill-shaped.
- Do not replace the near-yellow sibling card with an unrelated saturated hue.
- Do not add dark full-width bands between the light storytelling chapters.
- Do not give every offering card a heavy floating shadow; their edges are 1px at 8% charcoal.
- Do not set body paragraphs at a compact dashboard scale below the 20px marketing recipe.
- Do not fill the open footer with boxed link tiles or a heavy divider grid.
- Do not spread the navigation's blur treatment across content panels.

## Motion and responsive

### Motion

**Observed:**

- Declared action and surface transitions include color 0.2s and opacity 0.2s.
- Navigation items declare a white hover fill with a soft charcoal border and 16px corners.
- The navigation remains fixed as the content scrolls.

**Transfer:**

- Keep subtle interaction changes secondary to the layered photographic composition; do not make motion necessary to read the opening identity or the portrait labels.

**Unknown:**

- The timing and choreography of portrait swaps are not established.
- Focus-visible and active treatments beyond the available declarations are not established.

### Responsive

**Observed:**

- The desktop header separates identity, centered navigation and language utility.
- Width-dependent stylesheet rules exist, including 600px, 768px, 1024px and 1200px boundaries.

**Transfer:**

- On narrow screens, retain identity lettering behind a compact three-plane fan rather than replacing the opening with a generic text block.
- Stack explanatory text and its photo scene, and stack the offering pair while preserving their individual yellow-family colors.
- Keep access instructions legible and offer a direct action alongside any QR route for same-device users.

**Unknown:**

- Narrow-screen layout, exact collapse thresholds and type scaling are not established; the stacking rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
