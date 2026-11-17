# Morgen — warm orbits after dark

## Overview

A dark software-marketing style with friendly, substantial geometric headings and restrained interface detail. Charcoal and blue-black surfaces are warmed by peach, pink and honey-yellow edges, while product scenes glow softly in muted violet. The feeling is capable and human rather than futuristic: spacious storytelling surrounds compact, practical demonstrations and conversational reassurance.

### Essentials

- Human-scale boldness on a dark stage: Faktum 700 headlines at 64px/1.05, centered across an 880px measure, with a near-white text gradient rather than rainbow words.
- A promise above a real working object: an 88px fixed navigation, centered support at 20.8px/1.5, a 56px honey-yellow action, and an 1100px-wide application window entering the first screen about 594px down.
- Warmth lives at the edges: keep most of the page #191a23 and raised charcoal; use #ff8295 → #f3c26a for 1px outlines and the signature 96px-high closing legal ribbon, not full-page color washes.
- Actions are rounded rectangles, not pills: 12px corners, 16px padding, a dark 24px arrow tile inside the solid primary action; secondary actions have dark interiors and pink-to-gold hairline rims.
- Capabilities read as calm demonstrations: 431px text columns beside roughly 580px media panels, separated by 82px, with three lime circled-check benefits and muted violet light behind enlarged interface fragments.
- A designed ending, not a link dump: a 1160px bordered conversion panel carries floating product fragments on its right; the dense dark footer resolves into an inset pink-to-honey ribbon. Recreate the fragments as simplified product primitives when polished media is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Honey | `#f3c26a` | `--color-honey` | action, accent, link | Primary action fill, warm text links and the right edge of brand gradients. |
| Rose | `#ff8295` | `--color-rose` | accent, action | Left edge of warm gradients and action hover or active tint. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue charcoal canvas | `#191a23` | `--color-canvas` | background, text | Default page canvas and dark text on solid primary actions. |
| Inset charcoal | `#1c1d26` | `--color-inset` | surface | Compact independent-information panel and the darker end of radial pricing cards. |
| Feature tile | `#1f212d` | `--color-tile` | surface | Feature cards and the nested reassurance capsule. |
| Raised charcoal | `#20222e` | `--color-panel` | surface, background | Conversion panels and the lighter end of the footer gradient. |
| Control charcoal | `#21222d` | `--color-control` | surface, text | Small dark controls and dark text on the closing ribbon. |
| Translucent white edge | `#2b2c35` | `--color-alpha-edge` | border | Visible white at 8% over the canvas; used on compact dark controls. |
| Control slate | `#2a2e3c` | `--color-ui-slate` | surface, border | Social icon squares, arrow-control rims and control hover fill. |
| Feature outline | `#444444` | `--color-edge` | border | Thin feature-card edges. |
| Soft gray text | `#cbcccc` | `--color-body` | text, link | Paragraphs, lists and footer links. |
| Heading white | `#ffffff` | `--color-white` | text, border | Headlines, emphasized benefit phrases and navigation. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Circled-check lime | `#d8fd9d` | `--color-lime` | accent, text | Small positive checks and favorable comparison values; never a page canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| companion-product announcements | Announcement green | `#4fa55b` | `--color-green` | action | Small waitlist action within the cream announcement. |
| pricing comparison tables | Violet comparison wash | `#1d1e30` | `--color-comparison-tint` | surface | Visible 6% violet wash over dark canvas, made with rgba(98,94,252,0.06); stronger 12% wash belongs to the column header. |
| companion-product announcements | Announcement cream | `#f4f0e1` | `--color-cream` | surface, text | Cream announcement card and its inverse button label. |
| companion-product announcements | Announcement ink | `#120700` | `--color-brown` | text, border | Serif headline, hard outline and offset shadow on the cream announcement. |
| long product-detail pages | Community band | `#0f1017` | `--color-abyss` | background | A darker full-width review and community chapter. |
| dense proof and pricing sections | Deep card | `#16171f` | `--color-deep` | surface | Review cards and comparison table backing. |
| dense proof and pricing sections | Deep outline | `#24252c` | `--color-fine-edge` | border | Review cards and comparison rules. |
| pricing pages | Radial slate | `#262938` | `--color-pricing-glow` | surface | Off-center highlight on plan and integration tiles. |
| dense social proof | Muted review text | `#8b8d98` | `--color-muted` | text | Review prose, metadata and stat captions. |
| dense social proof | Proof white | `#e8e9ed` | `--color-proof-white` | text | Review names, proof headings and statistics. |

## Typography

- **Faktum** — All marketing headings and footer group labels. Friendly geometric sans with broad circular bowls and substantial bold strokes. If unavailable, use **DM Sans**. Use 700; preserve wide headline measures and open round forms. Font stack: "Faktum", "DM Sans", sans-serif.
- **Inter Variable font** — Body copy, navigation, labels and actions. Compact neutral sans that makes long product explanations readable. If unavailable, use **Inter**. Font stack: "Inter Variable font", Inter, system-ui, sans-serif.
- **Inter** — Review cards, statistics and independent-information controls. Neutral compact sans, with tighter tracking on numerical proof. Font stack: "Inter", system-ui, sans-serif.
- **Erode** (only for companion-product announcements) — Cream announcement headline only. Warm editorial serif contrasting with the dark software layout. If unavailable, use **Lora**. Font stack: "Erode", "Lora", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Faktum | 700 | 64px | 1.05 | normal | Default centered marketing headline. |
| heading | Faktum | 700 | 48px | 1 | normal | Centered chapter headings and conversion-panel headlines; also the pricing-page opening. |
| feature-heading | Faktum | 700 | 32px | 1.25 | normal | Left-aligned capability chapters and large feature cards. |
| compact-heading | Faktum | 700 | 28px | 1.25 | normal | Compact independent-information callout heading. |
| hero-support | Inter Variable font | 400 | 20.8px | 1.5 | normal | Default centered hero description, up to 800px wide. |
| card-heading | Faktum | 700 | 20px | 1.2 | 0.0125em | Feature-card titles and reassurance heading. |
| body | Inter Variable font | 400 | 16px | 1.5 | normal | Paragraphs and footer links. |
| benefit | Inter Variable font | 400 | 16px | 1.3 | normal | Compact circled-check feature lists; short lead phrases may be white and bold. |
| primary-label | Inter Variable font | 500 | 16px | 1.429 | 0.0156em | Large solid opening and closing actions. |
| group-label | Faktum | 700 | 16px | 1.5 | normal | Footer column headings. |
| action-label | Inter Variable font | 500 | 14px | 1.43 | 0.018em | Secondary actions, header CTA and compact conversion actions. |
| navigation | Inter Variable font | 600 | 14px | 1.43 | 0.018em | Dropdown labels and language control. |
| information-label | Inter | 500 | 14px | 1.5 | normal | Independent-information destination controls. |
| note | Inter Variable font | 400 | 12px | 1.5 | normal | Low-emphasis reassurance under opening action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience landing pages | audience-display | Faktum | 700 | 63.2px | 0.9375 | normal | Tightly stacked three-line split hero headline. |
| pricing pages | plan-heading | Faktum | 700 | 40px | 1.25 | normal | Names of billing alternatives. |
| pricing pages | price | Inter Variable font | 700 | 40px | 1.25 | normal | Honey-colored plan price. |
| dense social proof | proof-heading | Faktum | 700 | 38px | 1.18 | -0.025em | Compact centered proof-band heading. |
| dense social proof | stat | Inter | 700 | 28px | 1.5 | -0.02em | Compact numerical proof, centered in a three-item row. |
| companion-product announcements | announcement-heading | Erode | 700 | 24px | 1.2 | -0.02em | Warm serif announcement title. |
| FAQ sections | faq-title | Faktum | 700 | 20px | 1.2 | normal | Question labels within accordion rows. |
| dense social proof | quote | Inter | 400 | 14px | 1.65 | normal | Small readable testimonial prose. |
| audience and detailed product landing pages | eyebrow | Inter Variable font | 700 | 12px | 1.5 | normal | Small textured capsule above headings. |

**Notes:**

- Keep the geometric heading face distinct from the functional body sans. Most headings use normal tracking; negative tracking belongs to the compact proof module, not the default hero.
- The default 48px section title is tightly led at 1; the feature-grid chapter uses a softer 48px/1.2 variant.
- Product-detail openings use the same 64px display with a smaller 16px body description. Do not spread that smaller support treatment into the default marketing opening.

## Layout

**Density:** Airy between chapters, compact within lists and proof cards; large dark breathing spaces separate readable demonstrations.

### Spacing

**Spacing system:**

- **step** 8px — Dominant reusable rhythm for gaps and padding; retain the distinct 20px, 40px and 82px values where specified.

| Value | Use |
| --- | --- |
| 8px | Card heading-to-description gap and accordion separation. |
| 16px | List item spacing, action group gaps and review-card gutters. |
| 24px | Heading-to-body separation, feature-card inner padding and standard content spacing. |
| 32px | Feature-grid gutters and closing support-to-action gap. |
| 40px | Desktop page side padding and compact callout inner padding. |
| 48px | Opening heading-to-description separation. |
| 70px | Reassurance-note-to-main-product-stage interval. |
| 82px | Two-column capability gutter and grouped capability vertical gap. |
| 88px | Default major section vertical padding and navigation clearance. |
| 104px | Reassurance capsule section vertical padding. |
| 120px | Large pricing chapter lead-in. |

### Containers and grids

- **content**: max width 1160px · side padding 40px. Centered primary desktop container; leaves 140px margins at 1440px.
- **hero-copy**: max width 880px. Centered headline measure; support nests inside an 800px measure.
- **chapter-copy**: max width 640px. Centered section title and paragraph before a broad demonstration.
- **capability-pair**: max width 1160px · 2 columns · gap 82px. Text takes about 40%, media about 60%; text is roughly 431px and visible media roughly 580px wide.
- **feature-mosaic**: max width 1160px · 3 columns · gap 32px. Two narrow columns each contain two stacked cards; a double-height wide card occupies the remaining half.
- **review-grid** (only for dense social proof): max width 1120px · 3 columns · gap 16px. Three equal cards; long product stories use independent-height masonry columns.
- **faq** (only for FAQ sections): max width 760px · side padding 40px. Narrow centered accordion beneath a centered chapter title.
- **plans** (only for pricing pages): max width 940px · 2 columns · gap 40px. Two equal billing alternatives below a centered audience tab control.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-panels | 12px |
|  | feature-cards-and-main-media | 8px |
|  | reassurance-capsule | 220px |
| dense social proof | review-cards | 14px |
| audience and detailed product landing pages | eyebrow-capsule | 32px |
| companion-product announcements | announcement | 22px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | main-product-stage | `0px 0px 20px 5px rgba(0,0,0,0.15)` | Subtle dark separation around the large application window. |
| companion-product announcements | announcement-offset | `4px 4px 0px 0px #120700` | Hard printed shadow on the cream card, not a general card effect. |

### Surfaces

#### Canvas · level 0

**Use:** Default dark page.

**CSS:** `background: #191a23; color: #cbcccc`

#### Raised panel · level 1

**Use:** Conversion panel interior.

**CSS:** `background: #20222e; border-radius: 12px`

**Observed:** Quietly lighter than the page, without a prominent drop shadow.

**Transfer:** Use the distinction in brightness to group a major call rather than increasing saturation.

#### Luminous hairline shell · level 1

**Use:** Subtle framed panels, FAQ rows and neutral plan cards.

**CSS:** `background: linear-gradient(45deg, rgba(255,255,255,0.2), rgba(255,255,255,0.07)); padding: 1px; border-radius: 12px`

**Observed:** A nested dark interior leaves only a thin graded rim visible.

**Transfer:** Use two nested layers; keep the outer layer to 1px rather than making a broad silver border.

#### Warm hairline shell · level 1

**Use:** Secondary controls, information panel and highlighted pricing alternative.

**CSS:** `background: linear-gradient(90deg, #ff8295, #f3c26a); padding: 1px; border-radius: 12px`

**Observed:** Warm color is restricted to the rim by a dark inset face.

**Transfer:** Use the same shell as a product-independent brand device.

#### Feature card · level 1

**Use:** Compact illustrated capability cards.

**CSS:** `background: #1f212d; border: 1px solid #444444; border-radius: 8px; overflow: hidden`

#### Footer band · level 0

**Use:** Dense multi-column ending.

**CSS:** `background: linear-gradient(#20222e, #191a23); padding-bottom: 24px`

#### Closing ribbon · level 1

**Use:** Signature final legal and social strip.

**CSS:** `background: linear-gradient(to right, #ff8295, #f3c26a); border-radius: 8px; padding: 24px 32px; margin: 24px; color: #21222d`

**Observed:** A 96px-high warm ribbon is inset from the viewport; it carries legal copy on the left and compact utility controls on the right.

**Transfer:** Keep this saturated finish even on short pages; use relevant legal and utility content.

#### Plan radial interior · level 1

**Only for:** pricing pages

**Use:** Plan cards and small integration tiles.

**CSS:** `background: radial-gradient(circle at 117% 73%, #262938, #1c1d26); border-radius: 12px`

#### Review interior · level 1

**Only for:** dense social proof

**Use:** Low-contrast review cards.

**CSS:** `background: #16171f; border: 1px solid #24252c; border-radius: 14px`

#### Community depth band · level 0

**Only for:** long product-detail pages

**Use:** Full-width community and review chapter.

**CSS:** `background: #0f1017`

#### Announcement paper · level 1

**Only for:** companion-product announcements

**Use:** Small contrasting promotional insert.

**CSS:** `background: #f4f0e1; border: 1.5px solid #120700; border-radius: 22px; box-shadow: 4px 4px 0px 0px #120700; padding: 28px 32px`

**Observed:** An illustrated character, serif title and green waitlist action make a deliberately separate visual dialect.

**Transfer:** Reserve this treatment for a genuine companion launch, not routine feature cards.

## Components

### Fixed navigation

**Use:** Persistent site orientation.

**CSS:** `position: fixed; height: 88px; width: 100%; z-index: 100; background: rgba(33,34,45,0.62)`

**Text style:** `navigation` — Inter Variable font 600 · 14px/1.43 · tracking 0.018em

**Observed:** Centered 1160px inner row: identity left, compact navigation in the middle, sign-in and warm-outline CTA right. Background is translucent; content behind it appears softly softened.

**Transfer:** Keep the centered menu sparse rather than turning the whole header into a pill.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #f3c26a; color: #191a23; border-radius: 12px; padding: 16px; height: 56px; display: flex; align-items: center; justify-content: center; gap: 16px`

**Text style:** `primary-label` — Inter Variable font 500 · 16px/1.429 · tracking 0.0156em

**Observed:** Label precedes an up-right white arrow in a 24px dark rounded tile. Compact conversion variants are 48px high with 14px labels.

**States:** Declared: hover inset shadow 46px 14px 41px -14px #ff8295; active background #ff8295. Transition box-shadow 0.4s, background-color 0.4s.

### Secondary button

**Use:** Feature education and secondary destinations.

**CSS:** `background: linear-gradient(to right, #ff8295, #f3c26a 56%); border-radius: 12px; padding: 1px; height: 48px; color: #ffffff; position: relative; overflow: hidden`

**Text style:** `action-label` — Inter Variable font 500 · 14px/1.43 · tracking 0.018em

**Observed:** Use a dark inset face with 16px horizontal content padding so only the gradient rim remains; text then a small right chevron. Header version uses the same outlined construction without a chevron.

**States:** Declared: hover inset shadow 46px 14px 41px -14px #ff8295 and text #191a23; active background #ff8295 with inset shadow 172px 53px 41px -14px #ff8295. Transition box-shadow, color, border-color and background-color 0.4s.

**Transfer:** Preserve the dark default interior; the gradient is not a solid multicolor button face.

### Benefit list item

**Use:** Short capability explanations below feature body copy.

**CSS:** `padding: 5px 0px 5px 40px; margin-bottom: 16px; color: #cbcccc; background-position: 0% 50%`

**Text style:** `benefit` — Inter Variable font 400 · 16px/1.3

**Observed:** Small lime outlined circle/check at left; a brief bold white lead-in precedes regular gray explanation. Usually three items.

### Feature tile

**Use:** Dense capability overview.

**CSS:** `background: #1f212d; border: 1px solid #444444; border-radius: 8px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `card-heading` — Faktum 700 · 20px/1.2 · tracking 0.0125em

**Observed:** Media at the top, then a 24px-padded title-and-body area. Small card media is about 256×144px; the tall companion uses a larger image and a 32px title.

**Transfer:** Assign each tile a concrete interface moment, not a generic symbol.

### Information destination

**Use:** Independent-information links inside a warm-rimmed compact callout.

**CSS:** `background: #21222d; border: 1px solid rgba(255,255,255,0.08); border-radius: 12px; padding: 12px 20px; display: flex; align-items: center; gap: 10px`

**Text style:** `information-label` — Inter 500 · 14px/1.5

**Observed:** An 18px service mark precedes the label. Three controls stack beside the callout text, each about 200×47px.

**States:** Declared: hover background #2a2e3c, border rgba(255,255,255,0.15), translateY(-2px), shadow 0px 4px 12px rgba(0,0,0,0.3) plus 1px white 6% inset; active translateY(0px), no shadow, background #1c1d26.

### Reassurance capsule

**Use:** Trust or safety statement between major call and footer.

**CSS:** `background: #1f212d; border: 1px solid rgba(100,102,112,0.1); border-radius: 220px; padding: 24px 56px 24px 32px; display: flex; align-items: center; gap: 32px`

**Text style:** `card-heading` — Faktum 700 · 20px/1.2 · tracking 0.0125em

**Observed:** A 120px warm-ringed circular shield sits left of a small title and a paragraph. Two larger concentric capsule outlines surround the interior, spaced by 24px of padding; the outer composition is 1056×270px.

**Transfer:** Use one concrete reassurance theme with a clear icon; retain the nested contour device.

### Footer link group

**Use:** Dense navigational ending.

**CSS:** `display: flex; flex-direction: column; gap: 16px; color: #cbcccc`

**Text style:** `body` — Inter Variable font 400 · 16px/1.5

**Observed:** A bold white Group-label heads gray links. Five thematic groups spread across the container; one broad group has two link columns. A white-outline language control aligns at the upper right.

**States:** Declared: links hover #f3c26a; active #ff8295.

### Review card

**Only for:** dense social proof

**Use:** Compact third-party proof.

**CSS:** `background: #16171f; border: 1px solid #24252c; border-radius: 14px; padding: 26px 24px 22px 24px; display: flex; flex-direction: column`

**Text style:** `quote` — Inter 400 · 14px/1.65

**Observed:** Avatar and name/role form a compact header with a small profile link, followed by muted prose with selected brighter phrases and a tiny review-source attribution. Width is about 363px.

### FAQ row

**Only for:** FAQ sections

**Use:** Objection handling in a narrow centered stack.

**CSS:** `background: linear-gradient(45deg, rgba(28,29,40,1), rgba(30,32,44,1)); border-radius: 12px; padding: 32px 32px 32px 48px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `faq-title` — Faktum 700 · 20px/1.2

**Observed:** A Luminous hairline shell surrounds the dark row. White question is left aligned and a white plus sits at right; nominal outer row is 760×96px with 8px separation. Expanded answers use body copy.

### Plan card

**Only for:** pricing pages

**Use:** Billing alternative with a clear price and action.

**CSS:** `background: radial-gradient(circle at 117% 73%, #262938, #1c1d26); border-radius: 12px; padding-top: 40px; display: flex; flex-direction: column; align-items: center`

**Text style:** `plan-heading` — Faktum 700 · 40px/1.25

**Observed:** A 450px-wide outer shell contains a 32px-inset title, explanation, honey price, compact billing chip, Primary button and separated benefit list. Recommended alternative gets a warm rim and small honey badge at top right.

### Announcement card

**Only for:** companion-product announcements

**Use:** A small contrasting companion-launch insert.

**CSS:** `background: #f4f0e1; color: #120700; border: 1.5px solid #120700; border-radius: 22px; box-shadow: 4px 4px 0px 0px #120700; padding: 28px 32px; display: flex; align-items: center; gap: 24px`

**Text style:** `announcement-heading` — Erode 700 · 24px/1.2 · tracking -0.02em

**Observed:** An 88px character image, serif heading and short brown support line sit before a small green pill action. The card is roughly 772×147px.

**States:** Declared: hover translate(-1px, -1px) with 5px 5px hard shadow; active translate(2px, 2px) with 2px 2px hard shadow; transform and box-shadow 140ms.

## Imagery and graphics

### Working application stage

**Use:** Main opening object and broad demonstrations.

**Observed:** A straight-on dark desktop application window, about 1100px wide, with restrained border and 8px corners. It is large enough to read as a real working environment and extends below the fold. The default opening has no bright surrounding mat; detailed-product variants use a lavender mat and strong window shadow.

**Transfer:** Show one authentic working state with enough meaningful detail to support the promise. If no application exists, construct a faithful simplified work surface from domain-specific objects rather than using a generic dashboard.

**Build:** For the default stage use a dark rectangular window, 1px muted gray border, 8px corners and 0px 0px 20px 5px rgba(0,0,0,0.15) shadow. Nest a sidebar and one main workspace; reserve any colored marks for data or active objects.

### Soft orbital product panels

**Use:** Signature illustration treatment for capability chapters and integration diagrams.

**Observed:** Large dark rounded media squares contain enlarged interface fragments, notification cards, small avatars or tool marks. A smoky violet or rose glow lives near the lower/right edge. Fine outlines, curved arrows and dotted orbital paths add motion without turning the image into glossy 3D.

**Transfer:** Keep one demonstrable operation per image, remove irrelevant UI chrome, and place the useful objects in the front plane. Minimum version: two or three clearly labeled product objects, one curved connector and a low-contrast glow.

**Build:** Use a roughly 580×528px dark panel with a 1px rgba(255,255,255,0.08) rim and softly rounded corners. Behind the content place a broad elliptical radial gradient rgba(98,94,252,0.12) fading to transparent, plus rgba(255,130,149,0.08) near the bottom right. Blur the light, not the front-plane text. Draw 1px dotted SVG arcs and a thin white curved arrow between foreground objects. Keep exact glow stops soft.

### Floating closing fragments

**Use:** Signature artwork on the right half of major conversion panels.

**Observed:** Thin vertical lanes under floating rectangular product blocks; a few translucent hatched or dashed-outline regions; small round markers along the upper area. Muted violet, green and honey accents appear in the fragments, with one pale lime filled item. Artwork is clipped at the panel's right edge.

**Transfer:** Use your product's smallest recognizable work units—documents, messages, assets or results—rather than calendar objects. Preserve the contrast between translucent regions and a few solid labels.

**Build:** Behind the right half of a Raised panel, draw three or four vertical 1px rgba(255,255,255,0.04) rules. Place staggered dark rounded rectangles with short labels and 3px colored leading bars. Add two dashed rectangles containing 45deg repeating translucent hatching, three 36px translucent circular markers and one compact lime-filled object. Clip the composition inside the 12px panel corners.

### Monochrome logo proof

**Use:** Compact credibility bridge after a product opening.

**Observed:** A centered gray support sentence sits above white customer marks arranged in a broad row with a short centered second row. Marks vary in width but share visual weight, without individual cards.

**Transfer:** Use authorized partner or customer marks, balancing their optical size. For products without customer logos, provide a similarly compact row of credible integration or compatibility marks.

### Nested trust contours

**Use:** Reassurance capsule ornament.

**Observed:** Three concentric pill silhouettes, a muted raised core and a warm circular icon rim create a restrained protective enclosure.

**Transfer:** Use this contour motif for a genuine reliability promise, keeping the content short.

**Build:** Center a 956×170px dark pill inside 1006×220px and 1056×270px outlined pills. Use 220px radii; inner and outer outlines rgba(100,102,112,0.1), middle outline rgba(100,102,112,0.3). Add a 120px circular pink-to-honey 1px shell around a dark shield icon.

### Icons

**Observed:** Functional monochrome SVG icons, mostly 16–24px, sit beside actions or inside dark squares. Positive benefits use a lime circled check. Detailed feature lists sometimes use 24px round-ended outline icons at about 1.5px stroke; arrow tiles are 24px with 8px corners.

**Transfer:** Use simple rounded strokes and one consistent optical size. Keep brand/service marks only where the destination or integration requires them; circled checks carry the benefit-list rhythm.

## Section recipes

How recurring sections are built.

### First screen: Promise and working object

**Observed:** An 88px fixed navigation overlays a blue-charcoal canvas with a faint broad cool halo behind the title. The centered 64px/1.05 bold headline occupies an 880px measure and typically breaks into two balanced lines; its white gradient is almost imperceptible. A 48px interval leads to a centered 800px support line at 20.8px/1.5. Below are the 56px Primary button and a subdued two-line 12px note, then a 70px pause before the 1100px Working application stage. Within the first 900px the entire headline, support, action and reassurance are visible, plus roughly the top 300px of the product window; the remaining object and logo proof continue below. Layer order is canvas, diffuse halo, text/actions, then the crisp product window.

**Transfer:** Give a different product an equally legible promise and one concrete working object. A simplified but credible interface composition is sufficient. Audience-specific pages can use a left-aligned three-line Audience-display with a smaller demonstration to the right; detailed-product pages retain the centered title but use 16px support and a lavender-backed stage. Pricing opens with a smaller 48px heading and plan alternatives rather than the oversized application window.

**Avoid:** Do not compress the complete product window above the fold, put the default opening in a split layout, or replace the working object with a decorative stock image.

**Text style:** `display` — Faktum 700 · 64px/1.05

### Centered chapter demonstration

**Observed:** A centered 48px Heading sits in a 640px text measure; body copy follows at 24px. A broad isolated demonstration roughly 880×504px begins about 45px later. Default vertical section padding is 88px.

**Transfer:** Introduce a major value shift with a readable title and one uncluttered product operation; let the artwork carry the detailed explanation.

**Text style:** `heading` — Faktum 700 · 48px/1

### Capability pair

**Observed:** Capability-pair layout aligns a 431px text stack with roughly 580px media. Feature-heading, paragraph, three Benefit list items and Secondary button form the left side; Soft orbital product panels sit right. Heading-to-body and body-to-list spacing is 24px; checks have 16px rhythm. Audience and detailed-product variants add a small textured Eyebrow capsule above the title.

**Transfer:** Keep chapters aligned the same way rather than mechanically alternating left/right. Describe one outcome per chapter and demonstrate the corresponding interaction.

**Text style:** `feature-heading` — Faktum 700 · 32px/1.25

### Capability mosaic

**Observed:** A centered 48px title and short support lead into a 32px-gutter mosaic. Four Feature tiles form two narrow stacked columns while a larger tall tile fills the right half. Media-first cards use compact 20px titles; the tall card has a 32px title and multiple short explanations.

**Transfer:** Use the tall card for the richest capability and the small cards for discrete supporting actions; do not flatten all five into equal boxes.

### Independent-information callout

**Observed:** An 820px Warm hairline shell wraps an Inset charcoal interior with 40px padding. Compact-heading and short support are left, three Information destination controls stack right.

**Transfer:** Offer credible independent routes for learning or validation. Keep the external-source character rather than making another sales CTA.

### Peer proof

**Observed:** The default proof uses three approximately 360px-wide variable-height testimonial cards, a 32px section label at left, square previous/next controls at right and 12px pagination dots below. Handles have warm clipped-gradient text. Dense variants use Review cards in three 16px-gutter columns, a 38px centered proof title, and a compact three-stat row separated by a faint top rule with 40px padding; stats use 28px/1.5 and small gray captions.

**Transfer:** Use short concrete testimony and modest numbers; keep the dense module scoped to longer proof-heavy stories rather than making every quote a monumental display.

### Closing conversion and reassurance

**Observed:** A 1160px Luminous hairline shell encloses a Raised panel about 358–366px tall. A 460px headline/support stack is inset well inside the left half; title is 48px/1, body follows by 24px, action by 32px. Floating closing fragments fill the right half. The default ending adds the Reassurance capsule in a separate 104px-padded section; audience pages go straight from the conversion panel to the footer. Detailed product stories may have two closing actions.

**Transfer:** Reprise the core benefit with one low-friction action and a useful product-fragment composition. Place a separate trust statement where the purchase context warrants it.

### Warm ribbon footer

**Observed:** Footer band begins with a thin light gradient rule. A 1160px inner region has 72px top/bottom padding, five link groups with 16px vertical rhythm and a white outlined language control. The Closing ribbon stretches nearly viewport-wide with 24px outer margins; dark legal text sits left and legal links plus 32px dark social squares sit right.

**Transfer:** End with this warm utility ribbon regardless of how many narrative chapters precede it. Scale link groups to the new information architecture without losing the contrast between dark directory and bright final strip.

### Pricing decision system

**Only for:** pricing pages

**Observed:** Centered 48px promise, short trial reassurance and three small trust chips precede audience tabs with a 2px honey active underline. Two Plan cards are separated by 40px. A wide comparison table later uses a near-black surface, 16px corners, fine rules, compact status icons and a softly violet-highlighted preferred column. A six-column integration grid and two discount/support panels finish the purchase argument.

**Transfer:** Separate billing choice from feature comparison. Make the preferred option visible through a thin warm rim and one small badge, not a much larger card.

### Practical principles grid

**Only for:** long product-detail pages

**Observed:** A centered 48px title introduces four icon-led text blocks in a two-column grid. Each block pairs a 72px outlined circular icon housing with a 20px card heading and 16px support. A wider before/after product demonstration follows.

**Transfer:** Use the grid to explain four operating principles or safeguards, not another generic feature checklist.

### Objection handling

**Only for:** FAQ sections

**Observed:** A centered 48px heading sits above a 760px-wide stack of FAQ rows, with 8px gaps. Outer sections have 100px vertical padding on pricing and 140px on detailed product stories.

**Transfer:** Use direct purchase or workflow questions and concise expanded answers. Keep closed rows visually calm.

## Page flow

**Storyline:** promise → working demonstration → credibility → capability chapters → proof and reassurance → low-friction action → dark directory with a warm final ribbon

### Broad product marketing and category introduction

1. **Promise** — Centered two-line display, large support, solid action and working application stage.
2. **Credibility** — Monochrome logo field and a centered chapter demonstration.
3. **Capability chapters** — Repeated same-direction capability pairs followed by an asymmetric media-first mosaic.
4. **Independent validation** — Compact external-information callout, then peer testimonials with navigation.
5. **Closing call** — Wide conversion panel with floating product fragments.
6. **Reassurance and directory** — Nested trust capsule, dark link groups and warm legal/social ribbon.

**Transfer:** Use the broad story when the new product needs both category clarity and several capabilities; retain signature devices without fixing the chapter count.

### Purchase evaluation and plan selection

1. **Pricing promise** — Compact trust pill, 48px centered title, trial terms and trust chips.
2. **Plan selection** — Audience tabs, two billing cards with a highlighted preferred alternative, then logo proof.
3. **Social and quantified proof** — Three compact reviews followed by a restrained three-stat row.
4. **Comparison** — Wide ruled comparison table with one softly violet-highlighted column.
5. **Compatibility and switching** — Integration tiles followed by two supportive offer cards.
6. **Objection handling** — Narrow FAQ stack.
7. **Directory** — Dark footer ending in the warm utility ribbon; no extra large closing CTA.

**Transfer:** Place the decision early, then remove practical objections. Do not force a product-style closing panel onto a completed pricing decision.

### Audience-specific product adoption

1. **Audience promise** — Textured eyebrow and tightly stacked left display beside a compact working demonstration.
2. **Credibility and demonstration** — Monochrome logo field followed by a centered value chapter.
3. **Capability chapters** — Several text-left/media-right demonstrations with small category capsules.
4. **Closing call** — Audience-specific conversion panel with a single solid trial action and product fragments.
5. **Directory** — Dark footer and the common warm final ribbon.

**Transfer:** Adapt the benefit framing and use cases for the audience while retaining the shared media treatment; do not invent a separate visual brand.

### Deep explanation of one flagship capability

1. **Capability promise** — Centered display, explanatory body, trial action and lavender-backed application demonstration.
2. **Credibility** — Monochrome customer marks.
3. **Capability chapters** — Repeated 32px feature headings with three compact benefits and focused interface panels; a small companion-launch card interrupts the long story.
4. **Operating principles** — Four circular icon-led principles and a before/after demonstration.
5. **Community and proof** — Darker band with centered invitation, profile links, masonry reviews and compact statistics.
6. **Objection handling** — Narrow FAQ stack.
7. **Closing call and directory** — Two-action conversion panel with product fragments, dark footer and warm final ribbon.

**Transfer:** Use the longer treatment for an unfamiliar capability that needs mechanism, control and proof explained separately. Treat the companion announcement as a scoped insert.

## Writing

Practical, reassuring and benefit-led. It offers capable assistance while repeatedly preserving the reader's agency; technical explanations support a concrete everyday outcome.

**Do not copy:** Do not reuse Morgen, Kai, product marks, branded feature names, customer logos, review quotations, professional counts, ratings, discounts, trial terms, security promises or platform claims as facts for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use our or the product name when explaining behavior. Audience pages speak to your team without becoming corporate or impersonal.
- **Rhythm:** Headlines are generally short sentence-case promises of about 5–11 words. Supporting copy alternates one clear overview sentence with short operational explanations; action labels stay brief and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | State a useful outcome, then qualify who stays in control. | 6–11 words | “Daily plans designed by AI, perfected by you”<br>“Turn your to-do list into a clear plan” |
| Capability heading | Name a recognizable pain or reassure against a likely worry. | 5–11 words | “Your time shouldn't be scattered across apps”<br>“Get help from AI without giving up control” |
| Benefit lead | A short bold outcome phrase, then an explanation of the mechanism. | 3–5 words plus one sentence | “Plans that adapt.”<br>“Don't miss a task.” |
| Support | Explain the concrete behavior in plain language rather than adding another slogan. | 1–3 short sentences | “[Brand] helps you plan ahead and easily adapt to schedule changes as they arise.” |
| Action | Use a literal next step; educational actions name the destination. | 2–6 words | “Get Started”<br>“Learn about the AI Planner”<br>“Start your team trial” |
| Closing headline | Invite a manageable next step or reiterate a personalized outcome. | 4–8 words | “Ready to take control of time?”<br>“Your personalized daily plans await” |

**Words and phrasing to use:** your; plan; prioritize; adapt; control; in one place; work that matters; clear; protect; built-in

**Avoid:** revolutionary; autonomous everything; 10x your life; crush it; disruptive ecosystem; magic with no explanation

**Rules:**

- Pair capability claims with a visible mechanism or a specific user action.
- Reassure about control and flexibility where automation might cause anxiety.
- Use sentence case for most headings and plain descriptive labels for navigation.
- Keep proof grounded in attributable experiences and qualified statements.

## Do's and Don'ts

### Do

- Keep the default display at 64px/1.05 and section headings at 48px/1.
- Use the 1160px desktop container and 40px outer padding as the main alignment system.
- Preserve 82px gutters in capability pairs and 32px gutters in the feature mosaic.
- Use 12px rounded rectangles for conversion controls and 8px corners for compact feature cards.
- Keep copy #cbcccc and headings white against the blue-charcoal canvas.
- Give product panels subtle violet/rose light and legible foreground interface fragments.
- Include the inset 96px-high warm closing ribbon as a recognizable ending.
- Use lime only for small circled checks and positive comparison marks.

### Don't

- Do not turn ordinary secondary actions into solid rainbow fills; keep their dark inset face.
- Do not replace the geometric bold headings with a thin neo-grotesk or the announcement serif.
- Do not spread the announcement's cream, green pills and hard offset shadows across ordinary marketing sections.
- Do not use oversized gradient-colored statistics; the proof values are compact 28px figures.
- Do not make the main media panels white cards; their dark UI and smoky backing are part of the character.
- Do not change the feature mosaic into five equal generic icon cards.
- Do not round the standard 12px action into a full pill.
- Do not render every explanation at hero size; keep body copy at 16px/1.5 and compact benefit text at 16px/1.3.

## Motion and responsive

### Motion

**Observed:**

- Primary button declares box-shadow 0.4s and background-color 0.4s transitions; secondary actions add color and border-color at 0.4s.
- Text links commonly declare color 0.2s; the translucent header background declares opacity 0.4s.
- Independent-information controls declare background, border, transform and shadow 0.3s, with a -2px hover lift.
- Review cards declare border-color, box-shadow and transform 0.25s; companion announcement uses transform and shadow 140ms.

**Transfer:**

- Let warm inset hover light reinforce actions without making the default control glow continuously.
- Reserve the crisp pressed-paper translation for the companion announcement; standard panels should not bounce.

**Unknown:**

- Exact scroll-trigger choreography, media playback timing and most transition easing assignments are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 480px, 640px, 767px, 768px, 991px, 1024px, 1100px and 1920px across the site.

**Transfer:**

- On narrower layouts, preserve the centered promise above the working object; scale the window to available width rather than preserving desktop overflow.
- Stack capability copy before its corresponding media and collapse the mosaic while keeping the richer card visually prominent.
- Allow the legal/social ribbon to wrap into clear groups while retaining its inset warm strip identity.

**Unknown:**

- Mobile font sizes, exact navigation collapse, mobile section gaps and breakpoint-specific art placement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
