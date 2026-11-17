# Strawberry — friendly tools, tiled light

## Overview

A warm, light software-marketing style that makes capable technology feel like a personable colleague. Cream and oatmeal surfaces, charcoal grotesk type and soft pastel characters sit alongside believable interface demonstrations. The overall density is airy, with compact controls and reassuring conversational details rather than loud promotional graphics.

### Essentials

- Headlines speak at human scale rather than billboard scale: the default is 47.8px Strawberry Sans, weight 480, line height 1.1 and -0.04em tracking, centered in a 478px measure.
- The opening is a little stage: a narrow two-line promise and paired 47px pill actions sit above a 1040px-wide interface, with small colorful characters standing on its upper edge. Use original simplified character or product-object sculptures when no mascot exists.
- Light is made of tiles, not neon: faint squares, circles and diamonds form a softly fading geometric field behind the opening and at warm-band boundaries. Recreate this device on every new landing page.
- Most of the page stays cream, white and oatmeal; color is concentrated in pastel illustration windows, small identity chips and tiny orange links or badges. Primary actions remain charcoal, never accent-colored.
- Controls are rounded pebbles while proof feels conversational: 100px button radii, 24px quote cards with one square lower corner, and white question bubbles answered by right-aligned dark bubbles.
- Media has its own tabletop: 13px-radius pale panels support floating interface windows or small sculptures, with thin soft shadows rather than hard outlines. A narrow centered closing invitation returns to 44px type, one dark action and a faded monochrome logo ribbon.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt orange | `#ed5a31` | `--color-orange` | accent, link | Small comparison links and compact offer badges, not broad backgrounds. |
| Clay lettering | `#8e544f` | `--color-clay` | text | Highlighted word and warm category lettering. |
| Peach word capsule | `#f7e3d4` | `--color-peach` | surface | A single changing word embedded in an editorial headline. |
| Lilac stage | `#fbf2f8` | `--color-lilac-wash` | surface | Purple category illustration backdrop. |
| Mist stage | `#f1f6f7` | `--color-blue-wash` | surface | Blue category illustration backdrop. |
| Apricot stage | `#fcf5ef` | `--color-apricot-wash` | surface | Warm category illustration backdrop. |
| Sage stage | `#f5f9f2` | `--color-sage-wash` | surface | Green category illustration backdrop. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#252522` | `--color-ink` | text, action | Headings, main text, dark buttons and answer bubbles. |
| Secondary charcoal | `#666563` | `--color-body-muted` | text | Support copy; charcoal at 0.7008 alpha over cream. |
| Tertiary charcoal | `#858481` | `--color-muted` | text | Navigation, short descriptions and trust captions; charcoal at 0.56 alpha over cream. |
| Warm hairline | `#efe6dc` | `--color-rule` | border | Vertical detail rules and footer separator. |
| Oatmeal | `#f7f2ed` | `--color-band` | background, surface | Long proof bands, soft content cards and segmented-control tracks. |
| Warm porcelain | `#fcf8f5` | `--color-panel` | surface | Illustration stages, quote cards and plan overviews. |
| Cream canvas | `#fffcfa` | `--color-canvas` | background, text | Default page ground and inverse button text. |
| Paper white | `#ffffff` | `--color-white` | surface | Secondary buttons, floating windows and question bubbles. |

## Typography

- **Strawberry Sans** — Marketing headings, paragraphs, navigation and controls. A compact, friendly contemporary grotesk with rounded bowls, a generous x-height and tightly fitted display text. If unavailable, use **Inter**. Use variable weights 400–650 and preserve tight display tracking. Font stack: "Strawberry Sans", "Inter", system-ui, -apple-system, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Strawberry Sans | 480 | 47.8px | 1.1 | -0.04em | fixed | Default landing-page promise and expressive split headline. |
| heading-lg | Strawberry Sans | 480 | 44px | 1.1 | -0.04em | fixed | Proof-section headline and centered closing invitation. |
| heading | Strawberry Sans | 480 | 40px | 1.2 | -0.04em | fixed | Centered capability-gallery headings. |
| heading-sm | Strawberry Sans | 480 | 36px | 1.1 | -0.04em | fixed | Onboarding and question-section titles. |
| detail-lead | Strawberry Sans | 480 | 28px | 1.4 | -0.03em | size clamp(1.625rem, 2.5vw, 1.75rem) | Left-hand introduction to a ruled detail matrix. |
| hero-support | Strawberry Sans | 400 | 21.6px | 1.38 | -0.01em | fixed | Centered two-line supporting promise. |
| card-title | Strawberry Sans | 500 | 20px | 1.35 | -0.01em | fixed | Capability title underneath its media panel. |
| detail-title | Strawberry Sans | 500 | 18px | 1.35 | -0.01em | fixed | Short labels in icon-and-rule detail cells. |
| support | Strawberry Sans | 400 | 17px | 1.55 | -0.01em | fixed | Section introductions and reassurance. |
| quote | Strawberry Sans | 400 | 17px | 1.6 | -0.01em | fixed | Customer quotes. |
| body | Strawberry Sans | 400 | 16px | 1.5 | normal | fixed | Compact capability descriptions. |
| category-label | Strawberry Sans | 540 | 16px | 1.2 | -0.02em | fixed | Small colored identity pills on illustrated cards. |
| navigation | Strawberry Sans | 400 | 15.3px | 1.2 | -0.0065em | fixed | Header links. |
| action | Strawberry Sans | 500 | 15px | 1.5 | normal | fixed | Main and secondary hero actions. |
| caption | Strawberry Sans | 400 | 15px | 1.5 | normal | fixed | Centered trust statement above a logo ribbon. |
| action-sm | Strawberry Sans | 500 | 14px | 1.5 | normal | fixed | Compact actions, video thumbnail controls and pricing tabs. |
| footer-link | Strawberry Sans | 400 | 14px | 1.43 | normal | fixed | Footer navigation and utility links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| use-case landing pages | use-case-display | Strawberry Sans | 480 | 50.8px | 1.1 | -0.04em | fixed | Centered task-oriented opening. |
| company story pages | company-display | Strawberry Sans | 480 | 46.8px | 1.1 | -0.04em | fixed | Left-aligned opening statement. |
| feature detail pages | feature-display | Strawberry Sans | 480 | 45.6px | 1.15 | normal | fixed | Longer centered outcome headline above a single demo. |
| use-case landing pages | use-case-heading | Strawberry Sans | 540 | 40px | 1.1 | -0.04em | size clamp(1.85rem, 3vw, 2.5rem) | Section headings above workflow explanations. |
| pricing pages | pricing-display | Strawberry Sans | 480 | 38px | 1.1 | -0.04em | fixed | Short left-aligned page title. |
| use-case landing pages | workflow-title | Strawberry Sans | 540 | 30px | 1.18 | -0.03em | size clamp(1.5rem, 2.3vw, 1.875rem) | Alternating workflow chapter titles. |
| pricing pages | price | Strawberry Sans | 650 | 30px | 1.2 | -0.025em | fixed | Price, with smaller muted period alongside the baseline. |
| feature detail pages | article-heading | Strawberry Sans | 500 | 28.4px | 1.37 | -0.0214em | fixed | Editorial article subsections. |
| company story pages | person-name | Strawberry Sans | 480 | 26px | 1.4 | -0.0185em | fixed | Name in a horizontal portrait card. |
| pricing pages | plan-title | Strawberry Sans | 650 | 22px | 1.2 | -0.025em | fixed | Names of tiers. |
| company story pages | story-body | Strawberry Sans | 400 | 20px | 1.4 | normal | fixed | Narrative paragraphs with occasional dark inline emphasis. |
| pricing and company question sections | question | Strawberry Sans | 400 | 18px | 1.6 | -0.0075em | fixed | Questions and expanded conversational answers. |
| feature detail pages | article-body | Strawberry Sans | 400 | 18px | 1.72 | 0.02em | fixed | Open, readable explanatory paragraphs. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display hierarchy relies on width and line breaks rather than heavy bold: weight 480 and -0.04em tracking stay together.
- Most body copy is muted charcoal; titles stay full-strength. Short card titles are only moderately heavier than paragraphs.
- Do not turn category pills into uppercase eyebrows. Sentence case dominates the hierarchy.

## Layout

**Density:** Airy overall, with compact controls and substantial pauses around media and conversion blocks.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-label gap and title-to-card-description gap. |
| 12px | Section title to support copy; pricing-column gap. |
| 14px | Gap between hero actions. |
| 16px | Headline-to-hero-support gap, quote-grid gutters and question-stack gaps. |
| 20px | Container side padding and category-grid gutters. |
| 24px | Quote and plan inner padding; closing headline-to-action gap. |
| 32px | Internal section padding and controls-to-plan spacing. |
| 40px | Capability row gaps and proof-band top padding. |
| 48px | Gallery heading-to-media space and portrait-card stack gaps. |
| 64px | Workflow text-to-media gap and common lower section padding. |
| 96px | Vertical interval between workflow chapters. |
| 116px | Top padding before the final centered invitation. |
| 128px | Breathing space before the split editorial character scene. |
| 160px | Footer bottom breathing space. |

### Containers and grids

- **container**: max width 1080px · side padding 20px. Centered border-box wrapper yields 1040px of usable content at desktop.
- **hero-copy**: max width 528px. Centered support line, with the headline narrowed to 478px and actions directly below.
- **category-grid**: 3 columns · gap 20px. Equal illustrated cards, about 333px wide; rows separated by 40px.
- **capability-grid**: 2 columns · gap 17.6px. Equal 511px-wide media-and-caption modules with 40px row gaps.
- **quote-grid**: 3 columns · gap 16px. Equal 336px quote cards in two desktop rows.
- **article**: max width 720px. Narrow feature narrative; demonstration expands beyond it to 880px.
- **workflow-guide** (only for use-case landing pages): max width 1120px · 2 columns · gap 64px · side padding 29.6px. Alternating 0.85fr text and 1.15fr media, aligned vertically at center.
- **plans** (only for pricing pages): 4 columns · gap 12px. Free tier beside a shared three-tier paid grouping; align all actions along one baseline.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 100px |
| media-stages | 13px |
| illustrated-cards | 20px |
| content-and-plan-cards | 24px |
| question-bubbles | 28px |
| icon-discs | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| porcelain-edge | `rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 2px -1px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px` | Cards, white pills and small floating surfaces. |
| hero-window | `rgba(15, 23, 42, 0.02) 0px 16px 34px 0px, rgba(15, 23, 42, 0.07) 0px 60px 120px 0px` | Broad, diffuse lift under the opening interface. |
| conversation | `rgba(15, 23, 42, 0.04) 0px 10px 34px 0px` | Question and answer bubbles. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #fffcfa; color: #252522`

#### Oatmeal band · level 0

**Use:** Long comparison and proof chapters.

**CSS:** `background: #f7f2ed`

**Observed:** A continuous warm field can span several adjacent sections; geometric tile fades soften its entrance and exit.

**Transfer:** Group related proof into one broad region rather than alternating background color at every section.

#### Porcelain media stage · level 1

**Use:** Backplate for illustrations and demonstrations.

**CSS:** `background: #fcf8f5; border-radius: 13px; box-shadow: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 2px -1px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px; overflow: hidden`

**Observed:** Media sits inside a lightly raised panel, with its caption outside below.

**Transfer:** Keep the backing almost the same brightness as the canvas.

#### Opening window · level 2

**Use:** Large hero product demonstration.

**CSS:** `background: #ffffff; border: 0.5px solid rgba(15, 23, 42, 0.16); border-radius: 13px; box-shadow: rgba(15, 23, 42, 0.02) 0px 16px 34px 0px, rgba(15, 23, 42, 0.07) 0px 60px 120px 0px; overflow: hidden`

#### Pastel illustration window · level 1

**Use:** Category art within a porcelain card.

**CSS:** `background: #fcf5ef; border-radius: 20px; overflow: hidden`

**Observed:** Other categories use sage, mist and lilac washes. A light geometric pattern fades behind the figure, and the bottom dissolves toward cream.

**Transfer:** Assign each category a restrained tint; keep surrounding copy and controls neutral.

## Components

### Fixed navigation

**Use:** Persistent orientation and a compact conversion action.

**CSS:** `position: fixed; height: 64px; background-color: rgba(255, 252, 250, 0.05); box-shadow: rgba(239, 230, 220, 0.85) 0px 1px 0px 0px; z-index: 50`

**Text style:** `navigation` — Strawberry Sans 400 · 15.3px/1.2 · tracking -0.0065em

**Observed:** A three-part inner grid holds a small symbol-and-wordmark left, navigation in the center and account plus dark download pill right. Links have 8px 14px hit padding. Current-page markers are tiny warm diamonds; detail and company pages use an opaque cream header.

**States:** Declared: hover links change to full charcoal.

### Primary button

**Use:** Default major conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; background-color: #252522; color: #fffcfa; border-radius: 100px; padding: 12px 28px`

**Text style:** `action` — Strawberry Sans 500 · 15px/1.5

**Observed:** A small filled platform icon precedes the label. Main action is 47px tall; compact card actions use 14px text and 8px 16px padding, and the header uses 13px text with 8px 20px padding.

**States:** Declared: hover opacity 0.9.

### Secondary button

**Use:** Sales or secondary hero action.

**CSS:** `display: flex; align-items: center; justify-content: center; background-color: #ffffff; color: #252522; border-radius: 100px; padding: 12px 20px; box-shadow: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 2px -1px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px`

**Text style:** `action` — Strawberry Sans 500 · 15px/1.5

**Observed:** Same vertical scale as the adjacent primary action, but reads as a white pebble rather than a stroked ghost button.

**States:** Declared: hover background-color #ffffff.

### Video thumbnail pill

**Use:** Human demonstration link beside a conversion button.

**CSS:** `display: flex; align-items: center; gap: 9.6px; padding: 4.8px 20px 4.8px 4.8px; border-radius: 100px; background-color: #ffffff; box-shadow: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 2px -1px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px`

**Text style:** `action-sm` — Strawberry Sans 500 · 14px/1.5

**Observed:** A tiny rounded landscape video thumbnail with a play glyph is inset on the left. The 41px-height version is the default supporting control.

**States:** Declared: hover box-shadow rgba(0, 0, 0, 0.1) 0px 0px 0px 1px, rgba(0, 0, 0, 0.08) 0px 1px 2px -1px, rgba(0, 0, 0, 0.06) 0px 3px 6px.

### Capability media card

**Use:** Visual explanation followed by a short title and paragraph.

**CSS:** `background-color: #fcf8f5; border-radius: 13px; box-shadow: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 2px -1px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px; overflow: hidden`

**Observed:** The art panel is 511px by 309px in the two-column gallery. Title and description sit outside it, with 20px top padding and a 6px title-to-description gap.

**Transfer:** Use one comprehensible visual metaphor or interface task per panel.

### Quote card

**Use:** Human social proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 24px; background-color: #fcf8f5; border-radius: 24px 24px 24px 0px; box-shadow: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 2px -1px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px`

**Text style:** `quote` — Strawberry Sans 400 · 17px/1.6 · tracking -0.01em

**Observed:** Quote above, author row anchored below with circular photo, compact name and muted role. Adjacent cards alternate which bottom corner is square; the square corner quietly echoes speech bubbles.

**Transfer:** Vary quote length without enlarging the author treatment.

### Ruled detail cell

**Use:** Trust, team or practical-benefit matrices.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px; padding: 0px 36px; border-left: 1px solid #efe6dc`

**Text style:** `detail-title` — Strawberry Sans 500 · 18px/1.35 · tracking -0.01em

**Observed:** Small dark icon on a white circular disc, title, then muted description; the text group has an 8px internal gap. A left introductory column spans the matrix height.

**Transfer:** Use this light structure instead of boxing every reassurance in another card.

### Conversation bubble

**Use:** FAQ presented as a dialogue.

**CSS:** `position: relative; background-color: #ffffff; border-radius: 28px; padding: 12px 22px; max-width: 80%; box-shadow: rgba(15, 23, 42, 0.04) 0px 10px 34px 0px`

**Text style:** `question` — Strawberry Sans 400 · 18px/1.6 · tracking -0.0075em

**Observed:** Questions align left within a 510px column; expanded charcoal answers align right, with cream lettering and a lower-right tail. Question tails point lower-left. The column uses 16px gaps; answers appear 12px below their trigger. A small character stands beside its lower edge. The general landing version uses 18px system-sans questions at weight 500.

**Transfer:** Preserve the asymmetrical chat silhouette and show one open answer; do not substitute a conventional ruled FAQ list.

### Footer link

**Use:** Compact multi-column site index.

**CSS:** `color: #252522`

**Text style:** `footer-link` — Strawberry Sans 400 · 14px/1.43

**Observed:** Four narrow navigation groups sit to the right of a wider identity-and-copyright column. Muted group labels precede links by 16px; links follow an 8px grid gap. A warm top rule separates a final utility row.

**States:** Declared: hover color hsl(60deg 4% 14% / .7).

### Segmented selector

**Only for:** pricing pages

**Use:** Audience and billing choices.

**CSS:** `display: grid; align-items: center; padding: 4px; background-color: #f7f2ed; border-radius: 100px`

**Text style:** `action-sm` — Strawberry Sans 500 · 14px/1.5

**Observed:** A white raised pill marks the selected segment inside a 48px track. Audience choices sit left and billing choices right. An orange compact offer badge lives inside the annual label.

### Plan overview

**Only for:** pricing pages

**Use:** Compare cost and scale of service.

**CSS:** `position: relative; background-color: #fcf8f5; padding: 24px; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.06) 0px 0px 0px 1px, rgba(0, 0, 0, 0.06) 0px 1px 2px -1px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px`

**Text style:** `plan-title` — Strawberry Sans 650 · 22px/1.2 · tracking -0.025em

**Observed:** Tier name, short analogy, compact bold allowance, price, playful character grouping, then full-width dark action. Pale lower blocks carry feature lists; paid tiers share a wider backing rather than one neon recommended tier.

## Imagery and graphics

### Ambient geometric light field

**Use:** Signature opening backdrop and soft boundaries of oatmeal bands.

**Observed:** A nearly tone-on-tone tiled field of squares, rounded squares, circles and diamonds drifts through broad waves. It is visible behind rather than on top of text, then disappears into cream. On pastel category art it becomes brighter and more legible.

**Transfer:** Keep this device even without illustration assets. Match the low-contrast patterned light; exact fade stops are not essential.

**Build:** Use an SVG pattern with a roughly 20px cell, alternating 8–14px squares, circles and rotated squares. Fill shapes with oatmeal at low alpha over cream; vary sizes in slow wave envelopes across the width. Apply a broad radial mask fading to zero at the margins and a cream-to-transparent vertical overlay. For section boundaries invert to cream shapes over oatmeal; for pastel windows use white shapes. These dimensions are a practical reconstruction recipe.

### Personable miniature sculptures

**Use:** Signature humanizing layer around product demonstrations and category cards.

**Observed:** Small stylized, big-eyed, oversized-head figures in desaturated violet, teal, green and clay, rendered with soft matte shading and tiny grounding shadows. Some use keyboards or books. They stand directly on the large browser frame, float in a trio beside editorial text, or occupy the lower part of a tinted card.

**Transfer:** Create original figures or personified product objects with simple rounded silhouettes and one muted hue each. Minimum version: a small set of clean flat-vector characters with a subtle oval ground shadow, consistent proportions and a clear pose; retain the small-scale staging.

**Build:** Construct head, hair and torso as broad rounded SVG silhouettes, with eyes as white ovals and dark pupils. Use two closely related tones per figure, little surface detail, a soft translucent charcoal ellipse below and a short platform or prop where relevant. Keep surrounding space cream and let figures overlap the product-stage edge.

### Product task demonstrations

**Use:** Opening proof, capability panels and use-case chapters.

**Observed:** Large white browser windows with pale gray chrome, rounded corners, restrained shadows and tiny traffic-light controls. The content shows a real task progressing: a prompt followed by structured output, tables, previews or a useful action. Smaller panels layer and overlap for comparison scenes.

**Transfer:** Show a plausible completed task for the new product. Use its authentic interface or a carefully simplified task mockup; keep enough content visible to explain the benefit rather than filling the scene with decorative dashboards.

### Floating capability metaphors

**Use:** Visual variety within the media gallery and architecture explanation.

**Observed:** Translucent pale-cyan folder stacks, overlapping presentation covers, compact white workflow chips and a thin isometric platform all float over warm porcelain. Colors become stronger inside actual document covers, not across the panel background.

**Transfer:** Use one light material metaphor per capability: layered folders, a few output previews or connected task chips. Minimum version is a clean SVG arrangement of two or three rounded planes with thin neutral edges and diffuse shadows.

**Build:** For a platform, draw a rounded diamond top plane and a shallow offset underside in white, edged with charcoal at 0.09 alpha, then add a blurred oval shadow below. For stacked output cards use three rounded rectangles at slightly different rotations and depths; reserve strong color for their contents.

### Monochrome trust ribbon

**Use:** Below the initial product scene and beneath the closing invitation.

**Observed:** Recognizable organization logos become low-contrast monochrome marks about 20px high, spaced widely in a horizontally moving ribbon with faded ends and a small centered caption.

**Transfer:** Use approved proof marks where available; otherwise a restrained ribbon of genuine ecosystem or compatibility marks fulfills the same quiet proof function.

**Build:** Place same-height monochrome SVG marks in a repeating flex strip with 64px gaps, then mask the left and right edges to transparent. Keep their rendered opacity low against cream.

### Natural team photography

**Only for:** company story pages

**Use:** Team context and personal biographies.

**Observed:** Outdoor group photography with sunlit green foliage; portraits use a softly blurred garden background, natural skin tones and relaxed dark clothing. A broad group image sits in an oatmeal frame; individual 304px by 376px portraits sit left inside cream 1040px-wide horizontal cards.

**Transfer:** Use authentic, warm daylight photography rather than cutout executive headshots. Keep biographies alongside, not over, the image.

### Icons

**Observed:** Small filled 16px icons accompany buttons; simple charcoal benefit icons sit in 52px white discs. Link chevrons use 16px outlines with 1.8px rounded strokes; pricing checklist icons use 18px outlines with 2px rounded strokes.

**Transfer:** Choose one compact filled utility family and one simple rounded outline family. Keep colorful logos confined to ecosystem illustrations and product scenes.

## Section recipes

How recurring sections are built.

### First screen: Character-and-product opening

**Observed:** A fixed navigation spans the top 64px. Behind it, Cream canvas carries Ambient geometric light field across roughly the first 570px. Center the 47.8px display promise in a 478px measure, normally two lines; give the 528px support line a 16px gap, then place Primary button and Secondary button 28px below with 14px between them. The copy begins around the upper sixth of the viewport. A 1040px Opening window begins near mid-screen, 79.2px below the actions, with miniature figures perched on the left and right portions of its upper edge. Within the first 900px the headline, support, both actions, figures and upper part of the interface are visible; the interface continues below the fold, with trust marks following it.

**Transfer:** Use a short outcome promise and an authentic product task; build an original small cast or personified object set if there are no mascots. Keep the interface as the dominant lower-half object. Use-case openings can replace the large lower interface with widely spaced floating integration discs and a following split introduction. Feature detail openings use a 720px text column, breadcrumb and single 880px demo; pricing and company narratives start left-aligned.

**Avoid:** Do not replace this layered stage with a full-bleed colored hero, huge display lettering or a text-only first screen.

**Text style:** `display` — Strawberry Sans 480 · 47.8px/1.1 · tracking -0.04em

### Split editorial character scene

**Observed:** A narrow left copy column faces a larger trio of miniature figures. The headline includes a clay word inside a peach pill; supporting copy uses short paragraphs and the Primary button plus Video thumbnail pill underneath.

**Transfer:** Use the pill to emphasize a changing quantity or stage of adoption; pair it with a small personable scene, not a second dense screenshot.

**Text style:** `display` — Strawberry Sans 480 · 47.8px/1.1 · tracking -0.04em

### Capability gallery

**Observed:** Centered heading, 48px pause, then a two-column grid of Capability media card modules. Illustrations take most of each module; compact titles and muted descriptions remain outside below. Category catalogs instead use three columns of 333px cards with tinted illustration windows, identity pills and two compact actions.

**Transfer:** Alternate functional demonstrations and light visual metaphors while keeping caption positions stable.

**Text style:** `heading` — Strawberry Sans 480 · 40px/1.2 · tracking -0.04em

### Warm proof field

**Observed:** Oatmeal band holds side-by-side comparison media, compact linked comparisons, an architecture illustration, the Quote card grid and a ruled reassurance matrix. Geometric light fades mark the broad region rather than every individual section.

**Transfer:** Use whichever evidence suits the product; retain a continuous warm proof region and light structure rather than a rigid sequence.

**Text style:** `heading-lg` — Strawberry Sans 480 · 44px/1.1 · tracking -0.04em

### Conversation questions

**Observed:** Heading, support and two actions occupy the left half; Conversation bubble fills the right. A small character near the lower-left edge of the dialogue makes the exchange feel hosted. White questions and one right-aligned dark answer form the main contrast.

**Transfer:** Use genuine objections and short factual answers; keep the response visually conversational.

**Text style:** `heading-sm` — Strawberry Sans 480 · 36px/1.1 · tracking -0.04em

### Closing invitation and site index

**Observed:** Every page ends with a centered 480px-wide invitation, 44px headline wrapped over two lines, one dark action 24px below and a trust caption 55px after the action. A low-contrast logo ribbon bridges into the footer. The footer uses the main 1080px wrapper: identity and copyright left, four narrow link columns right, then a utility row separated by a warm 1px rule, with 160px bottom padding.

**Transfer:** End with one low-commitment invitation and restrained external proof. Preserve the compact multi-column index rather than adding another promotional panel.

**Text style:** `heading-lg` — Strawberry Sans 480 · 44px/1.1 · tracking -0.04em

### Workflow chapters

**Only for:** use-case landing pages

**Observed:** A trait-card row leads into alternating image-and-copy chapters. The guide uses a 64px column gap and 96px vertical intervals. A 573px by 382px Porcelain media stage contains a floating browser, while a 30px title and brief explanation sit opposite with a compact dark action.

**Transfer:** Give each chapter one verb-led task and one visible output; alternate sides to establish rhythm.

**Text style:** `workflow-title` — Strawberry Sans 540 · 30px/1.18 · tracking -0.03em

### Narrow feature article

**Only for:** feature detail pages

**Observed:** A 720px editorial column follows the oversized single demonstration. Subsection headings introduce open paragraphs with 16px gaps; 24px-rounded oatmeal cards list output categories. A short final paragraph explains continued refinement.

**Transfer:** Describe when the feature helps, what it produces and how users refine the result.

**Text style:** `article-heading` — Strawberry Sans 500 · 28.4px/1.37 · tracking -0.0214em

### Company story and people

**Only for:** company story pages

**Observed:** A left-aligned statement and 736px-wide paragraphs precede a broad daylight group photo. An oatmeal story band pairs narrative with character art, then stacks cream horizontal portrait cards with 48px gaps and 24px corners. Geometric fades dissolve the band at both ends.

**Transfer:** Keep the story personal and concrete; use actual people and a modest illustration counterpoint rather than an abstract manifesto.

**Text style:** `company-display` — Strawberry Sans 480 · 46.8px/1.1 · tracking -0.04em

### Pricing comparison

**Only for:** pricing pages

**Observed:** Left-aligned compact title and support above widely separated audience and billing selectors. Four aligned tier columns carry Plan overview, with character groups between price and dark action. Included-feature blocks and two short allowance explanations follow.

**Transfer:** Make differences legible through clear amounts and practical analogies, not saturated recommendation panels.

**Text style:** `pricing-display` — Strawberry Sans 480 · 38px/1.1 · tracking -0.04em

## Page flow

**Storyline:** Promise → tangible product proof → capability explanation → human reassurance → simple final invitation and site index.

### Broad product landing page

1. **Promise** — Centered character-and-interface stage followed by faded proof marks.
2. **Capability explanation** — Split editorial scene, ecosystem illustration, category catalog and visual feature gallery.
3. **Adoption reassurance** — Three straightforward getting-started steps.
4. **Differentiation and proof** — Warm comparison field, architecture scene, quote cards and ruled trust matrix.
5. **Objection handling** — Hosted question-and-answer conversation.
6. **Closing call** — Centered invitation, trust ribbon and full site index.

**Transfer:** Use enough visual chapters to explain a broad offer, but let media carry the complexity.

### Task-specific landing page

1. **Promise** — Centered task-led headline surrounded by floating ecosystem marks.
2. **Product introduction** — Large split character card and short trait-card row.
3. **Product demonstration** — Alternating workflow chapters with genuine task outputs.
4. **Team reassurance** — Ruled detail matrix.
5. **Closing call** — Shared centered invitation, trust ribbon and site index.

**Transfer:** Narrow the promise to one audience and prove it through concrete workflows.

### Single-feature explanation

1. **Promise** — Breadcrumb, long centered outcome headline and single action.
2. **Product demonstration** — One oversized framed interface and a small understated caption.
3. **Capability explanation** — Narrow editorial article with soft output-category cards and refinement guidance.
4. **Closing call** — Shared centered invitation, trust ribbon and site index.

**Transfer:** Keep the narrative narrower and calmer than the broad landing page.

### Plan selection

1. **Offer framing** — Short left-aligned title, reassurance and two compact selectors.
2. **Pricing** — Aligned tier overviews, practical allowances and shared feature blocks.
3. **Social proof** — Quote-card grid.
4. **Objection handling** — Conversational questions about buying and usage.
5. **Closing call** — Shared centered invitation, trust ribbon and site index.

**Transfer:** Explain what changes as customers grow, then answer purchasing objections directly.

### Company narrative

1. **Motivation** — Left-aligned statement, short narrative and broad natural group photo.
2. **Origin and people** — Warm story region with personable illustration and horizontal portrait biographies.
3. **Objection handling** — Shared hosted question conversation.
4. **Closing call** — Shared centered invitation, trust ribbon and site index.

**Transfer:** Ground the product motivation in actual experience and introduce people without abandoning the product's friendly visual language.

## Writing

Friendly, practical and quietly ambitious. Capabilities are explained through work the reader recognizes, with warmth supplied by colleague metaphors rather than jokes or hype.

**Do not copy:** Do not reuse the brand name, companion names, logo, character likenesses, customer identities, testimonials, prices, numerical outcomes, certifications or company-history claims. Examples illustrate voice only.

- **Addressing the reader:** Speak directly to you and your team. Use we for promises and accountability; refer to the product as a useful collaborator rather than an omniscient machine.
- **Rhythm:** Headlines are usually short sentence-case promises; longer task headlines wrap into two clear lines. Support is one or two plain sentences, with compact verb-led capability names and direct action labels.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A familiar work relationship or a concrete sequence of verbs, followed by the benefit. | 6–11 words | “AI teammates that work alongside you”<br>“Test, debug, and build in a real browser” |
| Supporting line | Name the category, then describe the work removed from the reader. | 12–25 words | “[Brand] is a browser with built-in AI companions that take real work off your hands” |
| Capability title | A plain verb and a concrete object. | 2–4 words | “Debug web apps”<br>“Create Beautiful Visuals” |
| Reassurance | Answer a practical concern in ordinary language. | 5–14 words | “Trying [Brand] is easy, fast and requires no commitment.”<br>“Passwords stay local” |
| Primary action | Name the immediate action and destination or platform. | 2–4 words | “Download for Mac”<br>“See how it works” |
| Final invitation | Experience the product with low commitment. | 4–7 words | “Experience [Brand] for free” |

**Words and phrasing to use:** alongside you; your team; get started; real work; learns your preferences; pick up where the work left off; ready to send

**Avoid:** revolutionize everything; unleash limitless potential; 10x guaranteed; disruptive ecosystem; enterprise-grade synergy

**Rules:**

- Lead with the task or result before explaining the technology.
- Use specific nouns such as tables, drafts or reports instead of broad productivity claims.
- Pair ambitious promises with a visible demonstration or attributable proof.
- Keep transactional copy direct; preserve conversational warmth in explanatory copy.

## Do's and Don'ts

### Do

- Keep the default hero promise at 47.8px, weight 480 and -0.04em tracking.
- Use the 1080px wrapper with 20px side padding to align headers, galleries and footer.
- Repeat geometric tile light at the opening and at a broad warm-band boundary.
- Keep major action pills at 47px high, with 100px corners and a 6px icon gap.
- Stage capability media in pale 13px-radius panels with captions outside.
- Give quote cards 24px padding and alternate their square lower corner.
- Reserve 44px centered type and a 480px measure for the closing invitation.
- Keep pricing actions on one baseline and use the same charcoal treatment for every tier.

### Don't

- Do not turn the cream canvas into a dark technology theme.
- Do not spread orange across primary actions or section backgrounds; it belongs to tiny links and badges.
- Do not make all headings weight 700; the 480 display weight is central to the softness.
- Do not use a bright blue-gray for marketing card edges; keep rules warm and shadows low-alpha.
- Do not apply a uniform 24px radius to everything: media stages use 13px and illustrated catalogs use 20px.
- Do not render customer logos at full contrast alongside the main headline; they form a subdued ribbon.
- Do not enlarge benefit icons into colorful hero graphics; use compact charcoal symbols in white discs.
- Do not compress the footer into a dark strip; preserve the light index and 160px lower breathing room.

## Motion and responsive

### Motion

**Observed:**

- Declared primary-action opacity transition is 0.15s; navigation color transition is .3s cubic-bezier(.45, 0, .55, 1).
- Declared hero title entrance is 0.4s cubic-bezier(0.16, 1, 0.3, 1); ambient-grid reveal is 1.6s ease-out with 0.16s delay.
- Logo ribbons declare 25s linear infinite scrolling; other marquees declare 50s linear infinite.
- Answer bubbles declare opacity and transform transitions over 0.38s, using separate easing curves. Illustrations include floating figures, cycling examples and a pause control.

**Transfer:**

- Use movement to make figures feel alive and to demonstrate useful work; keep text and CTA positions stable.
- Keep the proof ribbon slow and continuous, and provide pause control for an extended illustrative sequence.

**Unknown:**

- Exact paths, amplitudes and timing variables for character floating and full demonstration choreography are not established.

### Responsive

**Observed:**

- CSS includes width breakpoints at 480px, 640px, 767px, 768px, 1023px, 1024px, 1280px and 1536px, with additional component-specific thresholds.
- Workflow headings explicitly use clamp formulas; header navigation is hidden below its medium layout.

**Transfer:**

- As design guidance, stack the opening actions and scale the product window to the content width while keeping small figures attached to its upper edge.
- Reduce multi-column card galleries to fewer columns; keep the article's narrow reading measure and the conversation's left-question/right-answer alignment.
- Preserve the faint geometric field as a background layer rather than squeezing its desktop pattern into a high-contrast texture.

**Unknown:**

- Mobile compositions, exact breakpoint-specific paddings and interactive menu behavior are not visually confirmed.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
