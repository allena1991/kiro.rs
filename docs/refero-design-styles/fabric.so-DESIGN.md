# Fabric — serif with playmates

## Overview

An airy, white editorial identity gives intelligent software a friendly, almost domestic character. Light serif promises sit beside practical grotesk copy, while rounded interface collages, candid work photography and bright little illustrated companions supply the energy. Violet and electric blue live mainly inside media, leaving the surrounding page spare and readable. It suits creative tools, personal productivity products and approachable technical services with substantial visual stories.

### Essentials

- Literary promises, practical explanations: light serif headlines at 80px/1.08 with -0.02em tracking, recurring section heads at 52px/1.08, and Inter support at 18px/1.3.
- The opening is a patient centered invitation: a compact rating above a 600px headline measure, a 415px support measure, 50px vertical gaps and one compact action; the large product stage only begins at the bottom of the first 900px.
- Conversion stays small and nearly black: 8px-radius buttons, 50px tall with 18px medium text, rather than oversized pills or saturated default actions.
- White is the room; color belongs to the objects: white page canvas, #fafafa demonstration panels and #f9f9fa feature tiles carry isolated violet, electric-blue and green graphic areas. Colored fills occupy portions of media, not whole page backgrounds.
- Product proof feels like a tabletop collage: a 972×612px white interface floats on a 1180×722px softly lit backdrop; later square scenes and 430×580px human photographs make the product tangible. Include flat, smiling geometric companions within this visual language; use original SVG characters if no equivalent media exists.
- The farewell becomes artwork: a spacious two-line 52px serif invitation and compact black action precede an extensive white directory and a 1320×200px pale geometric word sculpture. Make an original sculptural rendering of the new product's name, not a normal enlarged footer logo.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep indigo links | `#19154e` | `--color-link` | link, text | Quiet inline and directory links. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Media violet | `#7b5eff` | `--color-violet` | surface, accent | Isolated demonstration backing and diffuse media light, not a page-wide theme. |
| Electric blue | `#0610ff` | `--color-electric` | surface, accent | A single bright illustration panel within the pale feature collection. |
| Task green | `#48e300` | `--color-green` | accent, surface | Playful task illustration within feature media; not a global success or action token. |
| Proof orange | `#ff5900` | `--color-stat` | text, accent | A large quantified proof figure in a neutral demonstration panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White room | `#ffffff` | `--color-canvas` | background, surface, text | Dominant page canvas, interface cards and reversed action text. |
| Demonstration chalk | `#fafafa` | `--color-panel` | surface | Broad rounded demonstration panels, audience links and pale secondary actions. |
| Feature mist | `#f9f9fa` | `--color-tile` | surface | Visible result of #f2f2f5 at 50% over white on compact feature tiles. |
| Pale gray | `#e5e5e5` | `--color-edge` | surface, border | Billing selector backing; pale edge and geometric word-art tone. |
| Rating count gray | `#b3b3b3` | `--color-faint` | text | Visible #666666 at 50% over white, used for the subordinate rating count. |
| Utility gray | `#737373` | `--color-muted` | text | Copyright and inactive navigation. |
| Explanation gray | `#666666` | `--color-body` | text | Secondary descriptions; also the visible result of black at 60% over white. |
| Secondary action ink | `#404040` | `--color-login-ink` | text | Low-emphasis login action. |
| Soft charcoal | `#333333` | `--color-subheading` | text | Secondary serif titles and demonstration subheads. |
| Action charcoal | `#0a0a0a` | `--color-action` | action, text | Default primary action fill and directory headings. |
| Headline black | `#000000` | `--color-ink` | text, background | Serif headlines, strong feature labels and occasional inverted proof panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience and feature landing openings | Audience violet | `#7421fc` | `--color-badge-ink` | text | Text on a small category badge. |
| audience and feature landing openings | Lavender badge wash | `#f1e9ff` | `--color-badge-wash` | surface | Visible #7421fc at 10% over white. |
| pricing pages | Plan violet | `#3200ff` | `--color-pricing-action` | action, text | Full-width plan actions; replaces black within plan cards only. |
| pricing and visual-workflow FAQ sections | FAQ answer gray | `#9ba1a5` | `--color-faq-muted` | text | Compact FAQ answers, lighter than ordinary marketing copy. |

## Typography

- **GT Alpina** — Display promises, section headings and restrained closing lines; the Light cut is the default. Soft, literary serif with personable curves and a light, unforced silhouette. If unavailable, use **Lora**. Use the lightest available cut; preserve narrow measures and negative tracking. Font stack: "GT Alpina", "Lora", Georgia, serif.
- **Inter** — Body, navigation, buttons, captions and proof numerals. Matter-of-fact grotesk, mostly medium weight rather than a delicate regular. Font stack: "Inter", Arial, sans-serif.
- **Manrope** (only for visual-workflow demonstration chapters) — Compact demonstration subheads. Rounded geometric sans, heavier than the main explanations. Font stack: "Manrope", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GT Alpina | 300 | 80px | 1.08 | -0.02em | Main centered promise. |
| stat | Inter | 500 | 68px | 1 | normal | Single vivid proof number amid a neutral visual. |
| heading | GT Alpina | 300 | 52px | 1.08 | -0.02em | Recurring chapter headings and both lines of the closing invitation. |
| platform-title | GT Alpina | 300 | 36px | 1.3 | normal | Names in a platform-access strip. |
| body | Inter | 500 | 18px | 1.3 | normal | Short support paragraphs and image descriptions. |
| primary-label | Inter | 500 | 18px | 1.2 | -0.01em | Main action text and compact FAQ questions. |
| feature-label | Inter | 700 | 18px | 1.3 | normal | Bold opening phrase beneath square feature scenes. |
| rating | Inter | 500 | 18px | 1.5 | -0.01em | Rating and subordinate rating-count text. |
| directory-heading | Inter | 600 | 18px | 1.5 | -0.015em | Footer group labels and arrow-ended category links. |
| tile-title | Inter | 600 | 16.5px | 1.2 | 0.01em | Compact feature-collection titles. |
| navigation | Inter | 500 | 16px | 2 | -0.01em | Central navigation links. |
| utility-action | Inter | 500 | 16px | 1.2 | -0.01em | Header action labels. |
| directory-link | Inter | 400 | 16px | 1.4 | normal | Footer directory links. |
| audience-link | Inter | 500 | 16px | 1.5 | normal | Emoji-backed audience tiles and compatibility items. |
| caption | Inter | 500 | 14.5px | 21px | normal | Compact feature-tile explanations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience and feature landing openings | scoped-display | GT Alpina | 300 | 74px | 1.08 | -0.02em | Two-line promises with a small category badge. |
| pricing pages | plan-name | GT Alpina | 300 | 38px | 50px | normal | Plan card names. |
| feature explainer articles | reading-heading | GT Alpina | 300 | 28px | 1.4 | -0.018em | Small literary heads within a narrow reading column. |
| pricing pages | price | Inter | 500 | 24px | 20px | normal | Price and cadence on a single line. |
| long-form audience and feature pages | reading-body | Inter | 500 | 18px | 1.5 | normal | Long explanations and badge text. |
| visual-workflow demonstration chapters | demo-heading | Manrope | 700 | 18px | 1.4 | normal | Subheads beside demonstration art. |
| pricing pages | comparison | Inter | 500 | 15px | 20px | normal | Plan descriptions, features and comparison data. |
| pricing pages | plan-action | Inter | 500 | 15px | 2 | normal | Plan card actions. |
| pricing and visual-workflow FAQ sections | faq-answer | Inter | 400 | 15px | 1.5 | -0.01em | Compact FAQ answers. |

**Notes:**

- Keep serif tracking at -0.02em for the 80px, 74px and 52px tiers; hierarchy comes from scale and line breaks, not bold serif weights.
- Ordinary descriptions are Inter 500. Reserve 700 for short benefit phrases and 600 for compact tile titles and directory labels.
- Use the 52px heading as the default chapter voice; the 28px serif is a scoped reading-page role, not a replacement for marketing headings.

## Layout

**Density:** Airy: compact controls sit inside very spacious chapters, often separated by 200px top and bottom padding.

### Spacing

| Value | Use |
| --- | --- |
| 7px | Compact tile title-to-description gap. |
| 10px | Small component stacks and nested rows. |
| 12px | Navigation action gaps, audience tile gutters and demonstration panel inset. |
| 16px | Tile vertical text padding and directory heading separation. |
| 20px | Paragraph spacing and pricing card padding. |
| 24px | Feature media-to-caption gap and tile horizontal text padding. |
| 30px | Wide portrait-story gutters. |
| 34px | Compact feature-grid gutters. |
| 40px | Chapter heading-to-media or support gap. |
| 50px | Opening's main vertical cadence. |
| 80px | Footer identity-to-directory gap and generous grouping. |
| 120px | Compact feature-collection section padding. |
| 200px | Major visual chapter and closing-call top and bottom padding. |

### Containers and grids

- **chapter container**: max width 1200px · side padding 100px. Centered outer chapter shell with a 1000px inner storytelling measure at desktop.
- **hero measure**: max width 600px. Centered headline; support narrows to 415px.
- **product stage**: max width 1180px. Wide introduction media, broader than the ordinary 1000px chapter.
- **feature collection**: max width 1000px · 3 columns · gap 34px. Compact equal feature cards; 311px-wide tiles at desktop.
- **portrait rail**: 3 columns · gap 30px. 430px-wide tall cards continue toward or beyond the right edge rather than being compressed into small cards.
- **footer directory**: max width 1120px · 4 columns · gap 56px. Four long link columns on white.
- **reading column** (only for feature explainer articles): max width 760px. Centered left-aligned prose column.
- **plan grid** (only for pricing pages): max width 1060px · 3 columns · gap 48px. Three 321px-wide plan cards.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 8px |
| audience tiles | 14px |
| feature tiles | 16px |
| product window | 20px |
| demonstration panels | 24px |
| portrait stories | 30px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| primary action | `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px` | Subtle lift under nearly black buttons. |
| product window | `rgba(0, 0, 0, 0.1) 0px 1px 22px 0px` | Broad soft elevation for the opening interface. |

### Surfaces

#### White room · level 0

**Use:** Continuous marketing canvas.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Very faint divisions organize long pages without creating alternating colored bands.

**Transfer:** Keep the surrounding canvas white even when the product's media is vivid.

#### Demonstration panel · level 1

**Use:** A graphic paired with short explanatory copy.

**CSS:** `background: #fafafa; border-radius: 24px; padding: 12px; overflow: hidden`

**Observed:** A typical panel is 1000×517px with a roughly 493px square graphic on one side.

**Transfer:** Pair a purpose-built product vignette with a much narrower text block.

#### Feature mist tile · level 1

**Use:** Compact illustrated capability collection.

**CSS:** `background: rgba(242, 242, 245, 0.5); border-radius: 16px; overflow: hidden`

**Observed:** Pale cool tiles group a large upper illustration and a modest lower caption.

**Transfer:** Use a single clear visual metaphor per tile, not a miniature full application.

#### Floating interface · level 2

**Use:** Main product introduction.

**CSS:** `background: #ffffff; border-radius: 20px; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 22px 0px; overflow: hidden`

**Observed:** The white application window is inset into a broader softly lit scene.

**Transfer:** Show a populated, intelligible state with a small number of meaningful objects.

#### Inverted trust panel · level 1

**Use:** Compact trust or assurance proof.

**CSS:** `background: #000000; border-radius: 24px; padding: 30px; color: #ffffff`

**Observed:** A 1000×228px black panel holds evenly spaced white assurance symbols; the heading remains outside on white.

**Transfer:** Use only verifiable proof and keep inversion localized.

## Components

### Fixed navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: fixed; top: 0px; height: 71px; width: 100%; z-index: 10; background: #ffffff`

**Text style:** `navigation` — Inter 500 · 16px/2 · tracking -0.01em

**Observed:** Small serif wordmark and face symbol at left, a compact central run of links and chevrons, then a low-emphasis login beside a black action. Central links use 20px gaps; header primary action is 39px tall with utility-action type.

**States:** Declared: hover navigation text becomes gray with no underline; focus-visible and active appearance are unspecified.

**Transfer:** Keep the central link count restrained and retain the small right-side action pair.

### Primary button

**Use:** Single prominent conversion action in openings and closings.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #0a0a0a; color: #ffffff; border-radius: 8px; padding: 14px; height: 50px; box-sizing: border-box; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.05) 0px 2px 4px 0px`

**Text style:** `primary-label` — Inter 500 · 18px/1.2 · tracking -0.01em

**Observed:** A short text-only label, approximately 120px total width; no decorative arrow or icon.

### Secondary login

**Use:** Low-emphasis account access beside the primary header action.

**CSS:** `background: rgba(229, 229, 229, 0.2); color: #404040; border-radius: 8px; padding: 10px; height: 40px; box-sizing: border-box`

**Text style:** `utility-action` — Inter 500 · 16px/1.2 · tracking -0.01em

**Observed:** Pale backing nearly merges with the white navigation; label is centered.

### Directory link

**Use:** Footer links and quiet supporting navigation.

**CSS:** `color: #19154e; text-decoration: none`

**Text style:** `directory-link` — Inter 400 · 16px/1.4

**Observed:** Text-only, usually in vertically spaced groups; group headers can end in a plain right arrow.

**States:** Declared: hover color #6e6e6e with text-decoration-line none; focus-visible and active appearance are unspecified.

### Audience tile

**Use:** Scannable audience or use-case index.

**CSS:** `display: flex; align-items: center; gap: 12px; background: #fafafa; border-radius: 14px; padding: 8px; height: 51px; box-sizing: border-box; color: #666666`

**Text style:** `audience-link` — Inter 500 · 16px/1.5

**Observed:** A colorful emoji-like symbol in a white 50×35px inset precedes the label. Four 250px columns are the broad index version; scoped audience indexes use three 325px or two 494px columns.

**Transfer:** Use a relevant small illustrated symbol and a short role or task name.

### Feature tile

**Use:** Dense secondary capability collection.

**CSS:** `background: rgba(242, 242, 245, 0.5); border-radius: 16px; overflow: hidden; display: flex; flex-direction: column; width: 311px`

**Text style:** `tile-title` — Inter 600 · 16.5px/1.2 · tracking 0.01em

**Observed:** 279px overall height; approximately 178px upper graphic and lower copy inset 16px vertically and 24px horizontally. Caption uses caption type with 7px separation. One tile's upper graphic is electric blue; the rest stay pale.

**Transfer:** Keep the illustration-to-copy proportion and vary the visual metaphor, not card shapes.

### Rating stack

**Use:** Compact reassurance above the opening promise.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 12px; color: #666666`

**Text style:** `rating` — Inter 500 · 18px/1.5 · tracking -0.01em

**Observed:** Score sits beside five yellow stars; a lighter rating-count line sits below. It is much smaller than the promise.

**Transfer:** Use only real supporting proof; if ratings are unavailable, substitute a similarly compact verified trust statement.

### Split demonstration

**Use:** Explain one capability using a single scene and short copy.

**CSS:** `display: flex; justify-content: space-between; align-items: center; background: #fafafa; border-radius: 24px; padding: 12px; overflow: hidden`

**Text style:** `body` — Inter 500 · 18px/1.3

**Observed:** 1000×517px panel with a 493px square visual on one side and a narrow centered text column on the other. In visual-workflow chapters the copy is about 280px wide with demo-heading subheads. Image and text sides alternate.

**Transfer:** Give the art room to breathe; keep the surrounding explanation much shorter than the demonstration.

### Category badge

**Only for:** audience and feature landing openings

**Use:** Audience or feature qualifier above a centered headline.

**CSS:** `background: rgba(116, 33, 252, 0.1); color: #7421fc; border-radius: 20px; padding: 0px 12px; height: 27px`

**Text style:** `reading-body` — Inter 500 · 18px/1.5

**Observed:** A narrow lavender chip between the rating stack and the two-line serif promise.

### Plan card

**Only for:** pricing pages

**Use:** Tier selection.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 32px; background: #ffffff; border-radius: 16px; padding: 20px; width: 321px; box-sizing: border-box`

**Text style:** `plan-name` — GT Alpina 300 · 38px/50px

**Observed:** Tall equal cards, about 700px high, with name and one-line fit statement, Plan button, compact price and billing note, then a checked feature list. A tiny dark popularity tag overlaps the preferred card's top edge; a faint edge distinguishes white cards from the canvas.

**Transfer:** Keep all tiers visually equal except for the small recommendation tag.

### Plan button

**Only for:** pricing pages

**Use:** Action within plan cards.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #3200ff; color: #ffffff; border-radius: 8px; height: 40px; width: 281px`

**Text style:** `plan-action` — Inter 500 · 15px/2

**Observed:** Full-width violet action; the comparison-header version is smaller, 122×30px with 12px text.

## Imagery and graphics

### Soft-lit product stage

**Use:** The first large product proof and selected chapter media.

**Observed:** A real white interface, filled with colorful visual references, sits on a warm-gray backing washed by blurred leaf-like daylight shadows. The main window is 972×612px inside a 1180×722px scene. Later media may use a sky-blue cloud backing with layered document and phone cutouts.

**Transfer:** Use your product in a genuinely useful state. Without elaborate artwork, place one clear interface on a warm off-white plane with a restrained organic shadow and one overlapping card.

**Build:** Use a rounded 1180×722px backing with a white-to-warm-gray image or gradient. Overlay several irregular translucent gray SVG leaf silhouettes at the edges, blur them 20–40px, and keep the center lighter. Center the white Floating interface above this layer; do not wash out the interface itself.

### Smiling geometric companions

**Use:** A recurring playful presence in product scenes and human stories.

**Observed:** Flat flower, sun, star, blob and diamond characters use saturated pastel-like colors, tiny black eyes, a simple curved mouth and occasional cheek dots. They overlap photographs or sit among UI objects rather than forming a separate cartoon world.

**Transfer:** Create an original small family of abstract friendly shapes. Include at least one companion in the page's visual storytelling; a simple SVG with a face is the minimum acceptable version.

**Build:** In SVG, union 5–8 rounded lobes around a circle or soften the points of a star. Use one solid violet, green or warm accent fill; place two small black arcs or circles and a short curved smile at the center. Keep facial marks thick and rounded; place the character partially across a photo or media edge.

### Candid portrait stories

**Use:** Human context and outcome examples.

**Observed:** Warm, natural-light work or study scenes, often indoors with plants, tables and laptops. Tall 430×580px images have 30px corners; smiling companions appear as flat overlays. Beneath, a tiny avatar/name row introduces a short gray past-tense outcome caption.

**Transfer:** Photograph people using the new product in believable surroundings; retain natural shadows and warm neutrals. Pair each portrait with one concrete completed task, not a slogan.

### Violet search light

**Use:** Focused capability media within a larger neutral chapter.

**Observed:** A saturated violet center fades to white behind floating reference cards, documents or image cutouts. A white horizontal search field crosses the middle; some objects are sharp with white edges while distant objects blur.

**Transfer:** Use a product-specific input or control as the central anchor with 4–6 related objects around it. Match the soft glow; exact stops are not essential.

**Build:** Inside a 493px square white stage, place a 320px violet ellipse at center using rgba(123,94,255,0.8), blur 55px and fade the outer area to transparent. Layer 4–6 rounded media cards around a white pill-shaped central control. Rotate selected cards by 6–12 degrees; blur one rear card by 8px and keep foreground edges crisp.

### Geometric word sculpture

**Use:** A signature full-width footer artwork.

**Observed:** An enormous pale-gray name built from different geometric letterforms: scallops, quarter circles, rounded bars, a pinwheel-like form, diamond and polygonal strokes. It occupies a 1320×200px field with 60px side and 30px vertical framing, distinct from the small serif identity above.

**Transfer:** Create an original word sculpture from the new name. If custom lettering is limited, construct each letter from a consistent set of circles, quarter circles and rounded bars; this device must remain artwork rather than plain text.

**Build:** Draw SVG letters on a 1320×200 viewBox. Give each letter a different but related geometric construction, align the baseline and cap height, and space shapes evenly. Render black paths as a group at opacity 0.1 over white, producing pale gray.

### Purpose collage

**Use:** A values or mission proof chapter.

**Observed:** A 1000×517px light-gray stage pairs a large flat green line illustration with two overlapping documentary photographs in white print-like frames; one print is rotated. The factual explanation and quiet text link sit underneath.

**Transfer:** Use a truthful non-product story relevant to the new business, with original documentary photos and one simple drawn symbol. Preserve the print-and-drawing contrast rather than requiring a particular cause.

**Build:** Use a pale Demonstration panel. Place a simple thick round-ended SVG symbol on the left, then two portrait photo rectangles with white 8px frames on the right, one rotated about -7 degrees and slightly in front. Add only a faint gray shadow under the prints.

### Icons

**Observed:** Small black filled symbols and restrained gray utility marks accompany colorful emoji-like audience symbols. Navigation chevrons are about 12px with 1.5px round strokes; other utility marks are commonly 24–28px. Platform symbols are larger, around 48–50px.

**Transfer:** Use a coherent compact utility set for controls, but retain the more colorful, friendly miniature illustration treatment for audience tiles; do not turn every symbol into the same outlined icon.

## Section recipes

How recurring sections are built.

### First screen: Centered invitation opening

**Observed:** A 71px fixed white navigation caps a spacious white hero. The centered rating stack is followed by a single-line 80px light-serif promise in a 600px measure, a two-line 18px support statement in a 415px measure, and Primary button; main groups are separated by 50px. The headline spans about two fifths of the viewport rather than filling the screen. In the first 900px, all text and the action are fully visible, while only the top of the 1180px-wide Soft-lit product stage and a large companion peeking over its right edge enter at the bottom. Back-to-front layers are white canvas, softly lit media backing, raised interface, overlapping flat character, then the persistent navigation.

**Transfer:** Lead with one short human benefit and one short explanation; create an equally strong product stage using an original interface and simple companion SVG when custom media is unavailable. Audience and feature openings use the scoped 74px two-line promise and Category badge; pricing opens left-aligned with a 52px promise, inline rating, selectors and the top of plan cards.

**Avoid:** Do not turn the opening into a split hero with a right-side dashboard, fill it with a full-bleed gradient, or drag the entire interface above the fold.

**Text style:** `display` — GT Alpina 300 · 80px/1.08 · tracking -0.02em

### Wide editorial chapter

**Observed:** A left-aligned heading and optional support line sit in the 1000px inner measure, typically 40px apart, above a broad media object. Major chapter padding is 200px top and bottom; the heading can run across two lines without becoming a narrow centered stack.

**Transfer:** Give one capability a complete visual chapter and explain what the reader can do, not the abstract feature category.

**Text style:** `heading` — GT Alpina 300 · 52px/1.08 · tracking -0.02em

### Portrait outcome rail

**Observed:** A broad serif heading introduces three tall Candid portrait stories, with 30px gutters and captions beneath. The rail reaches beyond the ordinary inner measure and can reveal only part of the third card.

**Transfer:** Use a small set of distinct human outcomes; preserve large portraits and edge continuation rather than shrinking every card to fit.

### Alternating demonstration chapter

**Observed:** Split demonstration panels stack with 40px gaps; media and copy exchange sides. Chapter headings use heading type. The visual-workflow variant repeats pairs of 1000×517px panels with roughly 240px between chapters and Manrope demo-heading labels.

**Transfer:** Use alternating sides to sustain a longer walkthrough without inventing new card styles for every feature.

**Text style:** `heading` — GT Alpina 300 · 52px/1.08 · tracking -0.02em

### Quantified proof scene

**Observed:** A 1000px-wide pale panel places a curved procession of app symbols and names along the left, with one 68px orange number anchored on the right and a small black noun beneath it. A short explanatory paragraph follows outside the panel.

**Transfer:** Show one defensible number alongside a sparse visual inventory. If integrations are irrelevant, use a corresponding set of outputs, categories or workflow objects.

**Text style:** `stat` — Inter 500 · 68px/1

### Small capability cabinet

**Observed:** A heading introduces Feature tiles in a three-column collection with 34px gaps. Most cards are pale; one upper illustration is intensely blue. Rounded cropped UI fragments, a clock, a text highlight or an abstract task form occupy the upper two thirds.

**Transfer:** Collect secondary benefits here, using a different visual metaphor for each and keeping titles compact.

**Text style:** `tile-title` — Inter 600 · 16.5px/1.2 · tracking 0.01em

### Reading explainer

**Observed:** A left-aligned 760px prose column combines 28px serif heads and 18px/1.5 gray body text, with 20px paragraph separation and bold inline lead-ins. The audience-guide variant uses an 800px column and larger 52px section heads.

**Transfer:** Use this scoped treatment for detailed setup, control, compatibility and objections after the more visual story.

**Text style:** `reading-heading` — GT Alpina 300 · 28px/1.4 · tracking -0.018em

### Pricing and comparison

**Observed:** A left-aligned promise leads into audience tabs, a right-aligned yearly/monthly selector and three Plan cards at 48px gaps. A separate comparison table uses a 1060px measure, 50px rows, faint rules, a broad label column and four compact tier columns with check marks. Compact FAQ answers follow; an illustrated purpose chapter leads directly to the footer rather than adding the standard closing CTA.

**Transfer:** Support a buying decision with consistent feature categories, explicit billing terms and restrained recommendation styling.

**Text style:** `plan-name` — GT Alpina 300 · 38px/50px

### Verification invitation

**Observed:** An audience offer lives in a 1000px white rounded panel with 60px padding and a faint dashed outline. A cheerful small symbol precedes a 52px heading and short explanation. A single 680×54px softly shadowed white input bar ends with an inset black 40px action.

**Transfer:** Use this scoped structure for eligibility checks or a single-field enrollment, retaining the compact inline action.

**Text style:** `heading` — GT Alpina 300 · 52px/1.08 · tracking -0.02em

### Unhurried closing and directory

**Observed:** The closing occupies about 626px with 200px top and bottom breathing room. Two centered heading lines in an 800px measure are separated by 24px; Primary button follows after 40px. Below is a white directory with small identity, language selector and social link, then four columns at 56px gutters. The Geometric word sculpture follows the directory, and a small gray copyright finishes the page. Broad marketing and student variants also place a compact AI-advice prompt and four platform-access cells before the closing.

**Transfer:** End with a human invitation rather than urgency; retain the expansive pale word artwork even when the footer directory is shorter.

**Text style:** `heading` — GT Alpina 300 · 52px/1.08 · tracking -0.02em

## Page flow

**Storyline:** Human promise → visible product proof → outcome-led capability chapters → reassurance and detail → low-pressure invitation → directory and geometric farewell.

### Broad product introduction

1. **promise** — Centered rating, short literary benefit, narrow explanation and small action.
2. **product demonstration** — Soft-lit wide interface followed by small benefit labels and trust names.
3. **capability chapters** — Oversized media, portrait outcomes, square feature rails, audience index and alternating demonstrations.
4. **quantified proof** — One vivid count, compatibility inventory and localized black assurance panel.
5. **closing call** — Small feature cabinet, advice and platform-access strips, then the two-line invitation.
6. **directory** — Four link columns, pale geometric name artwork and copyright.

**Transfer:** Choose only the chapters that establish the new product's promise; preserve the contrast between big media and modest controls.

### Purchase evaluation

1. **promise** — Left-aligned serif positioning with a compact inline rating.
2. **pricing** — Audience tabs, billing selector and three equal white plan cards with violet actions.
3. **comparison** — Long categorized ruled feature table with checks and compact values.
4. **objection handling** — Short questions and pale gray answers.
5. **values proof** — Illustrated documentary purpose collage.
6. **directory** — Direct transition to the shared footer, geometric name artwork and copyright, without the standard two-line CTA.

**Transfer:** Let practical comparison dominate; use the scoped violet buttons only in the plan-selection system.

### Audience-specific adoption

1. **promise** — Two-line centered benefit followed by wide product stage and institutional trust strip.
2. **eligibility** — Single-field verification offer and a literary proof statement paired with a character.
3. **capability chapters** — Human portrait outcomes, three-up media benefits and large product scenes.
4. **social proof** — Three pale testimonial cards with stars, short quotes and attribution.
5. **detailed explanation** — Large serif heads and gray prose, an audience index and extensive FAQ.
6. **closing call** — Small capability cabinet, advice and platform-access strips, patient CTA, directory, geometric artwork and copyright.

**Transfer:** Replace the audience's workflows and proof with genuine specifics; retain the warm human examples and restrained offer form.

### Visual-workflow audience landing

1. **promise** — Rating, lavender audience badge, two-line 74px serif promise and layered product collage.
2. **capability chapters** — Repeated alternating pale split panels grouped beneath 52px literary chapter heads.
3. **objection handling** — Compact light-gray FAQ answers and an emoji audience-link index.
4. **closing call** — Small illustrated capability cabinet and standard patient closing.
5. **directory** — Shared columns, monumental pale name artwork and copyright.

**Transfer:** Use sustained visual walkthroughs for a visually oriented product rather than adding long general-purpose prose.

### Explain a specific advanced capability

1. **promise** — Centered rating, small lavender category badge, two-line promise and action.
2. **product demonstration** — Wide candid team photograph with flat characters, followed by three alternating split demonstrations.
3. **detailed explanation** — Narrow reading column with 28px serif heads, practical instructions, control details and use cases.
4. **objection handling** — Inline bold questions and ordinary gray answers within the same reading measure.
5. **closing call** — Illustrated capability cabinet, patient CTA, directory, geometric name artwork and copyright.

**Transfer:** Explain setup and boundaries in a readable article after the visual proof; keep this smaller heading system scoped to detail content.

## Writing

Warm, direct and capable, with a literary headline and an unusually practical explanation immediately after it. The product feels like a companion, not an enterprise command center.

**Do not copy:** Do not reuse the Fabric name, logo, character designs, proprietary interface artwork, customer or institution names, prices, review counts, integration totals, environmental claims, certifications or testimonial quotes as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and describe their material as your work, your ideas or your stuff. Use we sparingly for genuine commitments; the product is named when necessary to explain an action.
- **Rhythm:** Headlines are short conversational promises, sometimes split into two full-sentence beats. Support is typically one or two concrete sentences; longer explanations use repeated action-led phrases and occasional terse fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A familiar human metaphor rather than a technical category. | 3–8 words | “Your second brain”<br>“The home for your creative universe” |
| Chapter heading | A short capability expressed as an outcome or plain action. | 2–12 words | “Think visually.”<br>“Share beautifully with clients.”<br>“Set it once, benefit forever.” |
| Supporting explanation | Concrete action, objects and useful result; no abstract platform manifesto. | 1–3 short sentences | “Spread out a client brief, plan a launch, arrange assets and notes side by side. Think spatially, work visually. With your AI at your side.” |
| Primary action | Short verb and low-risk commitment. | 2–4 words | “Try for $0”<br>“Get started” |
| Closing line | Invitation that leaves the reader in control. | 3–8 words per line | “The workspace that thinks with you.”<br>“Ready when you are.” |
| Outcome caption | Past-tense completed task with specific objects and a human context. | 1 sentence | “read the meeting notes and updated the project roadmap.” |

**Words and phrasing to use:** your; a home for; think; save; find; create; work; all in one place; knows your; ready when you are

**Avoid:** revolutionary; enterprise-grade synergy; unlock limitless potential; dominate; 10x everything; hurry; last chance

**Rules:**

- Follow poetic headings with literal explanations of what happens.
- Use product-specific examples in natural language, including plausible queries or tasks.
- Distinguish an actual result from a possible use; make control and permissions understandable.
- Use sentence case for navigation, cards and buttons; avoid uppercase editorial eyebrows.
- Do not manufacture scarcity for the closing invitation.

## Do's and Don'ts

### Do

- Pair 80px light-serif promises with compact 18px medium sans explanations.
- Keep the opening support measure near 415px and its primary groups 50px apart.
- Use 200px vertical chapter breathing room around substantial visual proof.
- Keep default actions nearly black, 50px tall and 8px rounded.
- Use the 1000px inner chapter measure for broad scenes and 34px gutters for small feature tiles.
- Retain both playful flat companions and the pale geometric word sculpture in the visual language.
- Make compact tile titles 16.5px/1.2 with 14.5px/21px supporting captions.
- Keep colored graphic areas bounded within neutral rounded media panels.

### Don't

- Do not replace the literary serif with a bold geometric sans hero.
- Do not turn all corners into 9999px pills; controls use 8px and broad panels 24px.
- Do not use violet pricing actions as the default marketing CTA.
- Do not make ordinary paragraphs pale #9ba1a5; that lighter gray belongs to compact FAQ variants.
- Do not fill the entire page with black because one assurance panel is inverted.
- Do not wrap every paragraph in a raised card; most text sits directly on white.
- Do not flatten all imagery into identical interface thumbnails; retain human portraits, layered object scenes and small illustrative metaphors.
- Do not use a standard serif logo enlarged as the footer artwork; construct geometric letterforms instead.

## Motion and responsive

### Motion

**Observed:**

- Navigation links declare color 0.3s cubic-bezier(0.44, 0, 0.56, 1).
- Text links declare a muted-gray hover with no underline; button hover, focus-visible and active treatments are not specified.

**Transfer:**

- Keep hover emphasis primarily in the text color rather than making the small navigation controls jump or expand.
- Use the same rounded static composition as the resting state for any moving media.

**Unknown:**

- Scroll choreography, playback timing, reveal distances and most media animation easing are unspecified.

### Responsive

**Observed:**

- Width breakpoints include 810px and 1200px; pricing also includes 640px.

**Transfer:**

- As a design adaptation, stack split demonstrations below the compact layout threshold while retaining media-before-explanation reading order.
- Reduce the geometric name artwork proportionally as an SVG; preserve its pale graphic presence rather than substituting ordinary footer text.
- Let portrait-story rails retain their large-card character with controlled horizontal continuation instead of shrinking portraits into tiny tiles.

**Unknown:**

- Exact mobile type sizes, navigation collapse, grid changes and spacing overrides are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
