# Voicenotes — painted skies, practical promises

## Overview

An ivory editorial setting pairs personable, rounded serif headlines with slender literary section titles and matter-of-fact sans-serif copy. Vivid painted skies, botanical textures and floating white interfaces bring warmth to otherwise restrained productivity software. It suits trustworthy, approachable tools with a real workflow to demonstrate; the overall density is spacious, with denser pockets of customer proof and plan details.

### Essentials

- Two serif voices separate the promise from the chapters: a rounded Mackinac opening at 60px/68px with -0.03em tracking, then slender Instrument Serif section titles at 60px/1 with -0.02em tracking.
- The opening is an equal partnership of argument and object: a 1240px two-column stage, 48px gutter, 596×620px painted product scene, left-aligned three-line promise, paired actions and small reassurance rows.
- Conversion controls are compact ink capsules, not colorful slabs: 9999px radius, 12px 24px padding, 15px/20px semibold text, with a 1px outlined companion; header versions are 36px tall.
- Color lives inside the pictures, not across the page: #faf9f5 remains the continuous canvas, #0d0d0d anchors text and actions, and saturated blue and green occupy bounded media rather than whole marketing bands.
- Make the interface feel like an object in a brighter world: white or translucent panels float over textured sky, plants or abstract artwork, clipped into 16px feature frames and a more rounded hero frame. If there is no finished interface, stage a small believable task panel on a painted or textured backdrop.
- A luminous retrieval scene is a signature device: a 600×56px white capsule sits sharply above a faded two-row field of content, with a 600×66px mint-to-blue glow blurred by 82.4px at 0.5 opacity. Adapt the foreground to the product's central interaction.
- The finish returns to literary scale rather than spectacle: a centered 60px/70px closing promise within 720px, a single black capsule 32px below, then four plain link columns and a 2px pale footer rule.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue light | `#4baafc` | `--color-glow-blue` | accent | Visible blue wash from rgba(0,136,255,0.7) over ivory in the interaction glow. |
| Aqua light | `#92f3e6` | `--color-glow-aqua` | accent | Visible aqua wash from rgba(102,240,224,0.7) over ivory in the interaction glow. |
| Mint light | `#ddfae3` | `--color-glow-mint` | accent | Visible mint wash from rgba(209,250,219,0.7) over ivory, softened further in the interaction glow. |
| Pale demonstration blue | `#eaf2f8` | `--color-blue-backdrop` | surface | Bounded workflow-image backing, not a page-wide theme. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0d0d0d` | `--color-ink` | text, action, border | Main text, filled actions and outlined controls. |
| Reassurance ink | `#18181b` | `--color-micro-ink` | text | Small reassurance lines under opening actions. |
| Literary charcoal | `#222222` | `--color-heading` | text | Instrument Serif section and closing headings. |
| Feature description gray | `#646462` | `--color-description` | text | Visible black at 0.6 opacity on ivory, used for feature descriptions and step numbers. |
| Footer heading gray | `#6c6b6a` | `--color-footer-muted` | text | Visible ink at 0.6 opacity on ivory for footer category labels. |
| Support gray | `#717171` | `--color-muted` | text | Supporting copy on proof cards and centered demonstration introductions. |
| Trust caption gray | `#898989` | `--color-caption` | text | Small serif caption beside the customer-logo strip. |
| Quote edge | `#cfcfcf` | `--color-quote-edge` | border | Visible 20% ink border over white testimonial cards. |
| Footer divider | `#ebebeb` | `--color-footer-rule` | border | The 2px rule above copyright and social links. |
| Proof edge | `#f3f3f3` | `--color-card-edge` | border | Visible 5% ink border over white security cards. |
| Warm ivory | `#faf9f5` | `--color-canvas` | background, surface | Continuous page ground; also the inset feature tiles on white plan cards. |
| Panel white | `#ffffff` | `--color-white` | surface, text | Proof cards, interface panels and labels on dark actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing actions and interaction demonstrations | Sales blue | `#0088ff` | `--color-action-blue` | action | Enterprise-plan sales action; the same hue contributes at 0.7 alpha to the demonstration glow. |
| pricing pages | Plan edge | `#e7e7e7` | `--color-plan-edge` | border | Visible 10% ink border over white plan cards. |
| download conversion sections | Warm tab track | `#f0eee6` | `--color-tab-track` | surface | Platform selector track behind the white selected pill. |

## Typography

- **Inter** — All marketing body copy, navigation, actions, card titles and prices. Neutral contemporary grotesk; regular copy, medium labels and semibold action emphasis. Font stack: "Inter", Arial, sans-serif.
- **P22MackinacPro** — Opening promise and small customer-trust caption. Warm, broad, softly bracketed serif with a substantial medium cut. If unavailable, use **Lora**. Use 500; retain the tight opening tracking and generous line height. Font stack: "P22MackinacPro", "Lora", Georgia, serif.
- **InstrumentSerif** — Section titles, closing promise and pricing display. Tall, narrow, high-contrast serif with fine hairlines and a conversational literary quality. Font stack: "InstrumentSerif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | P22MackinacPro | 500 | 60px | 68px | -0.03em | Default marketing opening headline; broad letters wrap into a compact three-line promise. |
| heading | InstrumentSerif | 400 | 60px | 1 | -0.02em | Centered section headings. |
| closing | InstrumentSerif | 400 | 60px | 70px | -0.02em | Closing heading with room for two lines. |
| lead | Inter | 400 | 18px | 28px | normal | Opening support and centered demonstration introductions. |
| feature-title | Inter | 600 | 18px | 28px | -0.009em | Workflow step and feature titles beneath imagery. |
| card-title | Inter | 500 | 18px | 24px | normal | Titles in small trust cards. |
| body | Inter | 400 | 16px | 22px | normal | Trust-card descriptions and testimonial paragraphs. |
| navigation | Inter | 500 | 16px | 21px | normal | Primary navigation links and dropdown triggers. |
| utility-body | Inter | 400 | 16px | 24px | normal | Footer copyright and demonstration input text; also the base rhythm for plan details. |
| feature-copy | Inter | 400 | 15px | 22px | normal | Compact supporting text beneath feature and workflow titles. |
| action | Inter | 600 | 15px | 20px | normal | Marketing conversion actions. |
| compact-action | Inter | 500 | 14px | 20px | normal | Header conversion actions and selected platform label. |
| footer-link | Inter | 500 | 14px | 24px | normal | Footer links and muted category labels. |
| trust-caption | P22MackinacPro | 500 | 14px | 20px | normal | Two-line caption at the start of the logo strip. |
| reassurance | Inter | 400 | 13px | 20px | normal | Opening trust and compatibility rows. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | InstrumentSerif | 400 | 80px | 44px | -0.02em | Single-line centered pricing promise; allow visible glyphs to extend beyond the short line box. |
| pricing pages | price | Inter | 600 | 48px | 1 | -0.0002em | Large price numerals with smaller billing units aligned at the baseline. |
| pricing pages | plan-title | Inter | 500 | 24px | 32px | normal | Plan names. |
| pricing pages and FAQ lists | plan-label | Inter | 500 | 16px | 24px | normal | Plan feature labels and FAQ questions. |

**Notes:**

- Use the rounded serif for the initial promise and the slender serif for chapters; do not flatten them into one display family.
- The small serif trust caption is a deliberate exception among sans-serif utility labels.
- The visual Inter weights are 400, 500 and 600 even where separate font-cut declarations use the same numeric weight.
- Headlines stay sentence case. Large serif tracking is negative; ordinary body and label tracking stays normal.

## Layout

**Density:** Airy between arguments, compact inside cards: broad unpainted intervals make the colorful interface scenes feel curated rather than busy.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Gap between title and explanation inside pricing feature tiles. |
| 8px | Feature title to support copy and trust-card title to description. |
| 12px | Paired opening actions and internal testimonial separation. |
| 16px | Pricing column gutters, testimonial column gutters and footer list rhythm. |
| 20px | Proof-card padding and trust-card gutters. |
| 24px | Opening headline to supporting paragraph and workflow image to caption. |
| 32px | Support to action, closing heading to action, footer column gutter. |
| 40px | Workflow grid gutters and title-to-grid interval; plan header padding. |
| 48px | Opening gutter, feature-grid gutter and title-to-feature interval. |
| 56px | Trust heading to card row. |
| 80px | Vertical padding of the download-selector closing variant. |
| 110px | Vertical padding of the default closing call. |
| 120px | Common separation between major content chapters. |
| 150px | Breathing room between the staggered feature rows. |

### Containers and grids

- **main-container**: max width 1240px · side padding 32px. Centered marketing stage; at a 1440px desktop width its outer margins are 100px. At narrower widths use side padding rather than a fixed width.
- **opening-grid**: max width 1240px · 2 columns · gap 48px. Equal 596px columns; left text and reassurance rows balance a portrait-like product scene on the right.
- **workflow-grid**: max width 1240px · 3 columns · gap 40px. Three equal image-first steps.
- **feature-grid**: max width 1040px · 2 columns · gap 48px. Two 496px image-led columns, staggered vertically instead of forced into equal-height cards.
- **proof-grid**: max width 1040px · 4 columns · gap 20px. Four compact trust cards beneath a centered headline.
- **testimonial-grid**: max width 1050px · 3 columns · gap 16px. Independent vertical stacks create a masonry-like wall of quotes.
- **closing-width**: max width 720px. Centered two-line closing statement.
- **footer-grid**: max width 1240px · 4 columns · gap 32px. Four plain link columns; copyright left and social icons right in the separate bottom row.
- **plan-grid** (only for pricing pages): max width 1150px · 3 columns · gap 16px. Equal-width plan columns with content-dependent card heights.
- **faq-width** (only for pricing pages): max width 700px. Single narrow question list centered under a much wider serif heading.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-input | 9999px (pill) |
|  | cards-and-feature-images | 16px |
|  | hero-frame | 40px |
| product demonstrations | floating-interface | 32px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | interaction-capsule | `0px 2px 5px rgba(0,0,0,0.05), 0px 8px 40px rgba(0,0,0,0.04), 0px 0px 2px rgba(0,0,0,0.15)` | White interaction bar above a softly faded field of content. |
| product demonstrations | floating-interface | `0px 24px 60px -12px rgba(0,0,0,0.25)` | Glass-like app panel over vivid artwork. |

### Surfaces

#### Ivory canvas · level 0

**Use:** Unbroken page ground.

**CSS:** `background: #faf9f5`

**Observed:** Sections generally change composition, not background color.

**Transfer:** Keep proof, conversion and footer on the same warm ground.

#### White proof card · level 1

**Use:** Small reassurance cards.

**CSS:** `background: #ffffff; border: 1px solid rgba(13,13,13,0.05); border-radius: 16px; box-shadow: none`

**Observed:** The light edge separates white from ivory without a raised dashboard effect.

**Transfer:** Use this for short verifiable assurances.

#### Blue workflow frame · level 1

**Use:** Clipped backing for sequential product imagery.

**CSS:** `background: #eaf2f8; border-radius: 16px; overflow: hidden`

**Observed:** Cool blue stays inside each image, with open captions beneath.

**Transfer:** Repeat the same backing across a short workflow.

#### Interaction light · level 1

**Use:** Diffuse light behind the central interaction capsule.

**CSS:** `width: 600px; height: 66px; background-image: linear-gradient(90deg, rgba(255,255,255,0.7), rgba(209,250,219,0.7) 15%, rgba(102,240,224,0.7) 50%, rgba(0,136,255,0.7) 100%, rgba(255,255,255,0.7) 0px); filter: blur(82.4px); opacity: 0.5`

**Observed:** A low horizontal glow, not a sharply defined rainbow border.

**Transfer:** Match the soft wash; exact stops are not essential.

#### Glass demonstration panel · level 2

**Only for:** product demonstrations

**Use:** Floating app UI over artwork.

**CSS:** `background: rgba(255,255,255,0.9); border-radius: 32px; padding: 16px; backdrop-filter: blur(24px); box-shadow: 0px 24px 60px -12px rgba(0,0,0,0.25)`

**Observed:** Soft translucency admits the artwork while dark labels remain crisp.

**Transfer:** Apply only to a small interface object, not marketing prose.

## Components

### Fixed navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: fixed; top: 0px; height: 70px; width: 100%; z-index: 50; background: rgba(250,249,245,0.95); border-bottom: 1px solid rgba(13,13,13,0.024)`

**Text style:** `navigation` — Inter 500 · 16px/21px

**Observed:** Brand at left, navigation centered, login and two conversion pills at right. The inner rail is 1280px wide including 20px side padding. Header pills use compact-action and are 36px tall.

**Transfer:** Keep the fixed rail visually almost continuous with the ivory page.

### Navigation trigger

**Use:** Short links and dropdown entry points.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 6px 12px; height: 35px; border: 1px solid transparent; border-radius: 9999px; color: #0d0d0d`

**Text style:** `navigation` — Inter 500 · 16px/21px

**Observed:** Dropdown labels end with a tiny gray chevron; ordinary links omit it.

**States:** Declared: hover background-color rgba(13,13,13,0.06); focus-visible treatment not established.

### Primary button

**Use:** Main marketing action.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #0d0d0d; color: #ffffff; border-radius: 9999px; padding: 12px 24px; height: 46px`

**Text style:** `action` — Inter 600 · 15px/20px

**Observed:** The opening favors the demo action as the filled control. Closing controls are 44px tall and can include a small platform glyph. Text width determines capsule width.

**States:** Declared: hover background-color rgba(13,13,13,0.85); focus-visible appearance unknown.

### Outline button

**Use:** Companion conversion path.

**CSS:** `display: flex; justify-content: center; align-items: center; background: transparent; color: #0d0d0d; border: 1px solid #0d0d0d; border-radius: 9999px; padding: 12px 24px; height: 46px`

**Text style:** `action` — Inter 600 · 15px/20px

**Observed:** A small desktop glyph precedes the opening self-serve label. It sits beside Primary button rather than in a separate row.

**States:** Declared: hover background-color rgba(13,13,13,0.05); focus-visible appearance unknown.

### Trust card

**Use:** A compact verifiable assurance.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 24px; background: #ffffff; border: 1px solid rgba(13,13,13,0.05); border-radius: 16px; padding: 20px 20px 28px`

**Text style:** `card-title` — Inter 500 · 18px/24px

**Observed:** A 46px monochrome emblem occupies the top, followed by a title and body description separated by 8px. Cards form a horizontal row.

**Transfer:** Use concrete safeguards or quality assurances appropriate to the product.

### Testimonial card

**Use:** Readable customer proof in independent vertical stacks.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 12px; background: #ffffff; border: 1px solid rgba(13,13,13,0.2); border-radius: 16px; padding: 20px`

**Text style:** `body` — Inter 400 · 16px/22px

**Observed:** Quote first, small circular avatar and author/source lockup last. Card heights vary substantially with the quote; narrow columns preserve conversational line lengths.

**Transfer:** Keep genuine variation in quote length rather than cropping every quote to identical height.

### Interaction capsule

**Use:** One crisp product interaction over a contextual content field.

**CSS:** `position: relative; display: flex; align-items: center; width: 600px; height: 56px; padding: 16px 20px; background: #ffffff; border-radius: 9999px; box-shadow: 0px 2px 5px rgba(0,0,0,0.05), 0px 8px 40px rgba(0,0,0,0.04), 0px 0px 2px rgba(0,0,0,0.15); z-index: 10`

**Text style:** `utility-body` — Inter 400 · 16px/24px

**Observed:** A short natural-language prompt runs along the left; a bright circular arrow occupies the right. The faded background remains subordinate.

**Transfer:** Use a believable input, search or command that reveals the product's core value.

### Footer columns

**Use:** Plain utility navigation after the closing call.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 32px; color: #0d0d0d`

**Text style:** `footer-link` — Inter 500 · 14px/24px

**Observed:** Muted category labels share the link recipe; lists run at 16px gaps. Below the columns a 2px pale rule introduces a bottom row with copyright left and five monochrome social marks right.

**States:** Declared: hover link color rgba(13,13,13,0.5); focus-visible appearance unknown.

### Plan card

**Only for:** pricing pages

**Use:** Detailed tier comparison.

**CSS:** `display: flex; flex-direction: column; align-items: center; background: #ffffff; border: 1px solid rgba(13,13,13,0.1); border-radius: 16px; padding-bottom: 32px`

**Text style:** `plan-title` — Inter 500 · 24px/32px

**Observed:** Header uses 40px padding and 16px vertical gaps: plan name, audience line, price and full-width action. A thin divider separates the feature body, inset 32px. Free-tier action is outlined, paid self-serve is black, sales-led is blue; plan actions are 44px tall with 16px semibold labels. Cards end when their content ends.

**Transfer:** Do not artificially stretch the shortest tier to the height of the longest.

### Plan feature tile

**Only for:** pricing pages

**Use:** Explain included capabilities inside a plan.

**CSS:** `display: flex; flex-direction: column; gap: 6px; padding: 16px 20px; background: #faf9f5; border-radius: 16px`

**Text style:** `plan-label` — Inter 500 · 16px/24px

**Observed:** Medium-weight feature label above regular 16px/24px explanation; tiles are separated by 16px. A small green novelty badge appears on one new feature.

**Transfer:** Make the label scannable and the explanation practical.

### FAQ row

**Only for:** pricing pages and objection-handling sections

**Use:** Collapsed questions in a narrow list.

**CSS:** `display: flex; align-items: flex-start; gap: 8px; padding: 24px 0px; cursor: pointer`

**Text style:** `plan-label` — Inter 500 · 16px/24px

**Observed:** A 26px chevron precedes the question; subtle horizontal rules separate rows. Questions can wrap, while icons stay aligned to the first line. The list is 700px wide.

**Transfer:** Keep it on the canvas rather than enclosing every question in a white card.

### Platform selector

**Only for:** download conversion sections

**Use:** Choose a native download before the closing action.

**CSS:** `display: flex; align-items: center; gap: 2px; padding: 4px; height: 44px; background: #f0eee6; border-radius: 9999px; overflow-x: auto`

**Text style:** `compact-action` — Inter 500 · 14px/20px

**Observed:** A white 36px-high active pill sits behind the selected icon and label. Inactive labels are muted; a matching black download action follows beneath.

**Transfer:** Use only when the product genuinely has distinct platform choices.

## Imagery and graphics

### Painted interface stage

**Use:** Signature opening image and colorful feature scenes.

**Observed:** The opening places a small translucent notification over a richly textured cobalt sky, thick white clouds, green leaves, tiny birds and scattered colored diamonds. The 596×620px scene fills the right half of the stage and has strongly rounded corners. Later feature frames combine enlarged white UI with saturated botanical or abstract textures.

**Transfer:** Produce an original painted sky or close-up tactile nature texture, then float one legible interface moment over it. Minimum acceptable version: a textured blue field, irregular white cloud masses and green foliage in opposing corners, with a real task panel rather than a generic dashboard.

**Build:** Clip the opening scene with a 40px radius. Layer a cobalt base, irregular white SVG cloud paths along lower-left and upper-right edges, clustered green leaf ellipses in upper-left and lower-right, then a low-opacity SVG turbulence texture to simulate paint grain. Add a few small rotated diamond shapes. Center a compact white translucent task panel with soft shadow; keep decoration behind the panel.

### Sequential workflow frames

**Use:** Explain a small sequence through product states.

**Observed:** Three 387×340px cool-blue frames show a detection prompt, an active working panel and the resulting document. UI is enlarged and partially clipped by the frame; captions sit outside the pictures with numbers at left.

**Transfer:** Choose start, engaged and completed states of the new workflow; preserve the consistent backing and changing interface scale.

### Feature still-life pairs

**Use:** Richer capability chapters.

**Observed:** White interface close-ups sit over lime, pink, orange or cobalt botanical and abstract imagery in two 496px columns. Image heights vary, and columns are vertically offset. One conceptual scene uses white word capsules rotated in several directions over a bright floral field.

**Transfer:** Alternate concrete interface detail with a conceptual capability illustration. Translate categories or options into scattered white capsules only inside an image, not across marketing text.

**Build:** For a conceptual option scene, clip a colorful textured backdrop to 16px corners; place white rounded capsules at varied angles and staggered vertical positions. Use dark serif option labels and let some capsules run beyond the clipping edge.

### Luminous context field

**Use:** Signature demonstration of finding or acting on existing information.

**Observed:** A two-row field of pale content cards fills a broad 459px-high stage. Ivory veiling and 96px side fades reduce contrast toward the edges; Interaction capsule is the only fully crisp foreground object. Mint and aqua light is barely visible behind it.

**Transfer:** Populate the field with plausible product records. If the product has no search, use its primary command or creation action while retaining the sharp-foreground, faded-context contrast.

**Build:** Lay out two rows of content cards behind an ivory radial veil. Add white-to-transparent 96px edge gradients. Put Interaction light directly behind Interaction capsule at the center, with the capsule above the veil. Keep the glow diffuse rather than a colored outline.

### Laurel proof and handwritten compatibility

**Use:** Compact recognition and ecosystem proof near conversion.

**Observed:** Four short proof marks use gray laurel branches around two-line black claims with small colored symbols above. A separate centered row of colorful app icons varies in size, with the largest near the middle; below it a tiny handwritten caption and curved black arrow point upward.

**Transfer:** Use substantiated compact proof inside original laurel-style ornaments, and relevant ecosystem icons with a brief handwritten aside. These are small accents in generous ivory space, not a full-width logo billboard.

**Build:** Draw mirrored thin gray SVG stems with small paired leaves around each short proof label. For the ecosystem row, vary icon scale gently toward the center. Draw one black curved SVG path with an arrowhead from a short handwritten-style annotation to the icon row.

### Icons

**Observed:** Marketing navigation uses tiny gray dropdown chevrons; reassurance rows use small neutral line icons; buttons can carry 18px desktop or small platform glyphs. Trust cards use larger 46px monochrome emblems. Footer social symbols are solid black and approximately 22px.

**Transfer:** Choose simple neutral line icons for explanations and recognizable solid glyphs for platforms and social links; keep color in app artwork and bounded demonstrations rather than tinting every icon.

## Section recipes

How recurring sections are built.

### First screen: Painted product opening

**Observed:** A 70px Fixed navigation overlays the ivory canvas. The first stage has 96px top and bottom breathing room and a 1240px equal-column composition with a 48px gutter. The left half contains a broad three-line display headline, 24px to an 18px support paragraph capped at 520px, then 32px to paired Primary button and Outline button. Three 13px reassurance rows sit much lower, visually anchoring the text column to the bottom of the artwork. The right half is a 596×620px Painted interface stage. Layer order is ivory, bounded painted scene, floating translucent UI, then crisp text and controls. Within the first 900px the complete headline, paragraph, actions, reassurance rows and main image are visible; customer logos begin below the fold.

**Transfer:** Use the default split composition for a new marketing landing page: a concrete promise balanced by one vivid task scene. Without finished product media, construct a small convincing task panel over original tactile art. Pricing pages instead open with a centered pricing-display promise and support, followed immediately by the plan columns; no competing hero artwork.

**Avoid:** Do not center the default opening, replace the artwork with a generic laptop mockup, or push the actions below the entire image.

**Text style:** `display` — P22MackinacPro 500 · 60px/68px · tracking -0.03em

### Serif chapter lead

**Observed:** Centered heading at 60px/1 in charcoal, generally without an eyebrow. The content starts 40px or 48px below; the demonstration chapter adds a centered 18px support line 16px under the title.

**Transfer:** Introduce one plain-language outcome per chapter and let the imagery carry the detail.

**Text style:** `heading` — InstrumentSerif 400 · 60px/1 · tracking -0.02em

### Numbered image workflow

**Observed:** Serif chapter lead above a three-column workflow-grid. Each Blue workflow frame is followed 24px later by a number beside a feature-title, then feature-copy 8px below.

**Transfer:** Use a short progression with distinct visual states and terse action labels; preserve open captions outside the colored frames.

**Text style:** `feature-title` — Inter 600 · 18px/28px · tracking -0.009em

### Staggered capabilities

**Observed:** A centered chapter title precedes two feature columns within 1040px. Large images are staggered, captions are left-aligned, and the next pair follows after substantial 150px breathing room. Titles use feature-title and support uses feature-copy.

**Transfer:** Make each picture a separate useful moment rather than repeating the same full dashboard four times.

### Interaction in context

**Observed:** A centered serif heading and two-line lead introduce Luminous context field. Interaction capsule sits sharply in its center, supported by Interaction light.

**Transfer:** Give this signature device the page's most immediately comprehensible interaction; it need not occupy the same position in every narrative.

### Assurance row

**Observed:** A centered serif heading sits 56px above four Trust cards in a 1040px row with 20px gutters.

**Transfer:** Use concise proof categories and evidence-backed support, not an invented security checklist.

### Conversational proof wall

**Observed:** A two-line serif title precedes three 339px testimonial columns with 16px gutters and tightly stacked variable-height Testimonial cards. Below the wall, small laurel proof marks and the handwritten compatibility scene lead toward conversion.

**Transfer:** Combine candid customer language with a restrained summary of independent recognition.

### Literary closing and utility ending

**Observed:** Default closing uses 110px vertical padding, a centered two-line closing heading within 720px and a Primary button 32px below. The download variant uses 80px padding, Platform selector and a matching download action. Footer columns follow on the same ivory canvas, then a separate 108px-high bottom row with a 2px pale rule, 28px top and 48px bottom padding, copyright left and social symbols right.

**Transfer:** Make the last promise immediate and achievable; then step down into plain navigation rather than adding a dark or decorative footer.

**Text style:** `closing` — InstrumentSerif 400 · 60px/70px · tracking -0.02em

### Plan comparison

**Only for:** pricing pages

**Observed:** The centered 80px pricing promise sits above three white Plan cards in 1150px, separated by 16px. Each header aligns plan name, audience, 48px price and action. Warm inset Plan feature tiles explain what each tier adds. Shorter cards terminate naturally.

**Transfer:** Let audience and capability differences explain the tier structure; keep the overall canvas light.

**Text style:** `pricing-display` — InstrumentSerif 400 · 80px/44px · tracking -0.02em

### Objection list

**Only for:** pricing pages

**Observed:** A centered 60px serif FAQ heading sits above a 700px list, with a 40px interval before the first FAQ row. Six collapsed questions use leading chevrons and very faint dividers.

**Transfer:** Address practical purchase objections in the reader's words rather than adding another benefit grid.

**Text style:** `heading` — InstrumentSerif 400 · 60px/1 · tracking -0.02em

## Page flow

**Storyline:** Promise → practical demonstration or offer → recognizable proof → objections and assurance → low-friction closing action → plain utility ending.

### A product landing page that makes a trustworthy tool feel useful and approachable

1. **Promise** — Split serif statement and painted interface stage with paired actions and compact reassurances.
2. **Social proof** — Low customer-logo strip with a small serif trust caption.
3. **Product demonstration** — Numbered three-image workflow.
4. **Capability chapters** — Staggered two-column interface still lifes, then a luminous interaction scene.
5. **Assurance** — Four white cards with monochrome emblems and short factual explanations.
6. **Customer proof** — Variable-height testimonial wall, laurel recognition marks and playful compatibility strip.
7. **Closing call** — Centered literary statement and one dark capsule.
8. **Utility ending** — Four footer columns, copyright and monochrome social links.

**Transfer:** Keep the contrast between tactile product scenes and plain credible proof; reorder chapters to match the product's buying questions.

### A pricing page that makes tier choice and purchase objections legible

1. **Promise** — Centered slender serif headline with a brief audience-oriented support line.
2. **Pricing** — Three white plan columns with increasingly detailed warm feature tiles; outlined, black and blue actions differentiate routes.
3. **Social proof** — Customer-logo strip after the plan details.
4. **Objection handling** — Narrow FAQ list with leading chevrons.
5. **Assurance** — The same four-card reassurance pattern.
6. **Closing call** — Literary statement, platform selector and black download action.
7. **Utility ending** — The same four plain link columns and divided bottom row.

**Transfer:** Prioritize comparison, then doubts and reassurance. Carry over the editorial type and ivory ground without importing the full marketing illustration sequence.

## Writing

Plainspoken and reassuring, with warm confidence rather than bravado. Benefits are framed as everyday relief, and factual safeguards make the confidence credible.

**Do not copy:** Do not reuse the Voicenotes name, logo, original artwork, customer identities or quotations, customer logos, prices, download totals, ratings, certification claims or other brand-specific claims without independent rights and verification. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team. Refer to the product directly; use we sparingly and only for accountable statements.
- **Rhythm:** Short sentence-case headlines, often with periods. Longer explanatory copy uses one or two straightforward sentences; paired fragments and repeated words create emphasis without shouting.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category and the sensitive or valuable context it serves. | 6–10 words | “The notetaker for your confidential meetings.” |
| Supporting line | State the useful result, then resolve the principal fear in concrete terms. | 18–30 words | “Turn every meeting into notes you can trust. Nothing joins your call, nothing trains on your data, every word stays.” |
| Chapter heading | Use a compact transformation or a familiar phrase with a full stop. | 3–7 words | “From conversation to clarity.”<br>“Simple as it gets.” |
| Feature label | Describe the completed state or a small action, not the underlying technology. | 2–7 words | “Hit record”<br>“Done discussing, already executing.” |
| Conversion action | Direct verb with clear commitment level. | 2–4 words | “Book a demo”<br>“Start for free” |
| Closing promise | Make adoption feel possible before the reader's next real task. | 6–10 words | “Set it up before your next meeting.” |
| Objection question | Ask the practical question in the buyer's first-person language. | 7–18 words | “Can I import recordings from other tools?” |

**Words and phrasing to use:** your team; ready; all in one place; next steps; works with; before your next; nothing; every

**Avoid:** revolutionary; supercharge; 10x; disrupt; game-changing platform; enterprise synergy

**Rules:**

- Lead with what becomes easier or safer, then explain how it works.
- Use conversational repetition for emphasis rather than capitalized slogans.
- Keep factual assurance copy specific and testable.
- Let customer quotations retain their conversational texture; keep authored marketing copy more concise.

## Do's and Don'ts

### Do

- Keep the canvas #faf9f5 through the closing action and footer.
- Pair the 60px/68px opening serif with 60px/1 slender serif chapter headings.
- Keep feature titles at 18px semibold and their descriptions at 15px/22px.
- Use 16px corners for proof cards and feature-image frames.
- Retain a 12px gap between the filled and outlined opening actions.
- Leave about 120px between major chapters rather than filling every interval.
- Make foreground interaction controls crisp against intentionally faded context.
- Finish with four plain footer columns and a separate 2px-rule bottom row.

### Don't

- Do not turn every headline into bold Inter; the two serif voices carry the identity.
- Do not expand saturated blue into a page-wide pricing theme; it is a single sales route and a bounded media accent.
- Do not add drop shadows to ordinary proof cards; their 1px outlines do the separating.
- Do not use 8px rectangular marketing buttons; conversion controls are full capsules.
- Do not make all feature images the same height; the 496px columns deliberately stagger.
- Do not turn the testimonial wall into equal-height centered quote slides.
- Do not enlarge the handwritten ecosystem aside into a display heading; it is a tiny annotation under the icons.
- Do not mistake the 80px/44px single-line pricing display for the ordinary multiline marketing headline.

## Motion and responsive

### Motion

**Observed:**

- Action transitions include all 0.15s cubic-bezier(0.4,0,0.2,1); navigation color transitions use 0.2s with the same curve.
- The fixed header declares border-color and background-color transitions of 0.2s cubic-bezier(0,0,0.2,1).
- FAQ chevrons declare transform transitions of 0.3s cubic-bezier(0.4,0,0.2,1).
- Reduced-motion utility classes suppress some page and header transitions.

**Transfer:**

- Keep conversion feedback chiefly to surface-color changes so the capsule geometry remains stable.
- Use chevron rotation to signal FAQ state rather than introducing another visual motif.

**Unknown:**

- Exact scroll-reveal behavior, playback timing and full interaction sequences are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 428px, 480px, 768px, 769px, 991px, 992px, 1024px, 1200px, 1300px, 1400px and 1900px.
- Narrow-layout classes switch the opening and plans to one column, reduce the opening headline to 48px/56px, and center opening text.
- Section headings have 36px and 34px narrow variants; the closing uses a 40px line height in a narrow variant.
- The main container declares 32px side padding below its fixed-width range and 16px at its smallest variant.
- Trust cards declare horizontal overflow and snap-start behavior; desktop footer columns and platform selector have hidden narrow variants.

**Transfer:**

- For narrow implementations, preserve the painted object as a substantial separate scene rather than shrinking it into a thumbnail.
- Keep the glow and input within the available width, retaining the foreground-versus-context hierarchy.
- Use horizontal access for compact reassurance cards when four columns cannot fit.

**Unknown:**

- Exact breakpoint-to-variant mapping, mobile menu construction and hidden footer replacement are not established; narrow layout recommendations are not a verified mobile design.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
