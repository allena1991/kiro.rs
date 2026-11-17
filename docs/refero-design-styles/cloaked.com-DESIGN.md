# Cloaked — cream, ember, human shields

## Overview

A warm, human-facing technology style with bookish serif headlines and lean grotesk supporting text. Cream and oatmeal canvases alternate with brown-black chapters, while hot orange concentrates attention on actions and oversized proof. Rounded lifestyle photography carries small floating interface panels, making an abstract service feel tangible without turning the page into a dashboard. The overall density is airy in its framing and compact inside cards, suited to consumer memberships and products that need to earn trust.

### Essentials

- Bookish urgency rather than tech bravado: Simula headlines at 56px/1.1 and 48px/1.1, weight 400, tracking -0.02em; supporting text uses Stkbureausans at 18px/1.4, weight 300.
- A human scene shares the opening with a compact argument: an approximately equal split inside a 1280px ruled container, a 543px text measure, and a 606×514px photograph with 32px corners and a floating status panel. Use an everyday-use photograph plus a simplified outcome panel when no product scene exists.
- Actions feel like small capsules within soft architecture: buttons are 36px or 48px high with fully rounded ends; the signature input is 64px high with a 48px circular submit control nested on the right.
- Color arrives as a concentrated burst of proof: cream #fbf8ef dominates, brown-black #130f02 supplies substantial contrast chapters and the ending, and orange #ff550c is mostly reserved for actions and one emphatic proof-card cluster rather than continuous bands.
- Product benefits inhabit real life: warm photographs with 32px corners carry restrained olive-smoke or ivory interface overlays; pair a wide 820px scene with a 410px device scene or use tall 360×480px media cards.
- Proof changes typographic register: orange 32px-radius cards carry 112px/0.9 sans numerals with -0.06em tracking, including a stacked unit word, followed by a much smaller 24px label. Include a bold proof device using substantiated metrics or an equally concrete outcome.
- The ending is a designed destination: a brown-black footer with 32px top corners begins with a broad wordmark plaque opposite a serif newsletter invitation and pill input, then five link columns and a fine-print base. Substitute the new identity at the same visual scale.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff550c` | `--color-accent` | action, accent, surface, link | Primary buttons, proof cards, small link accents and selected feature edges. |
| Peach cream | `#ffe9e0` | `--color-proof-text` | text, surface | Giant numerals on orange proof cards; also the highlighted pricing column. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brown black | `#130f02` | `--color-ink` | text, background, action | Headlines, dark chapters, footer and dark action variant. |
| Raised umber | `#1c180b` | `--color-dark-panel` | surface, background | Dark illustrations, newsletter field and footer wordmark plaque. |
| Dark rail | `#201c0f` | `--color-dark-rule` | border | Subtle vertical rails within brown-black chapters. |
| Umber edge | `#292519` | `--color-dark-edge` | border, surface | Edges on dark cards, newsletter fields and footer separators. |
| Olive charcoal | `#454030` | `--color-body` | text, border | Main supporting copy, outlined actions and dark-button hover. |
| Warm gray | `#a09c8f` | `--color-muted` | text, border | Secondary support lines, footer group names and subdued outlines. |
| Cream edge | `#e9e6da` | `--color-rule` | border, surface, text | Container rules, light card edges, small badges and footer links. |
| Oatmeal | `#f3efe2` | `--color-card` | surface, background | Soft cards, neutral media backings and pale hover fills. |
| Warm cream | `#fbf8ef` | `--color-canvas` | background, text | Default canvas and reversed text on dark sections. |
| White edge | `#ffffff` | `--color-white` | border, surface | Fine edges on orange proof cards and the luminous conversion input. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing comparisons | Peach stripe | `#ffdbcc` | `--color-comparison-stripe` | surface | Alternating rows within the highlighted comparison column. |
| problem and risk chapters | Coral red | `#ec4545` | `--color-warning` | text, accent | Selected danger words in a dark problem statement and threat illustration details. |

## Typography

- **Simula** — Display headings and editorial invitations. Warm, relatively compact book serif with lively curved forms; not an ultra-high-contrast fashion face. If unavailable, use **Lora**. Use regular weight and -0.02em tracking for large headings; retune wrapping to the measured text widths. Font stack: "Simula", "Lora", Georgia, serif.
- **Stkbureausans** — Body copy, navigation, actions, prices and quantitative proof. Direct grotesk with open counters; lightweight supporting copy contrasts with dense oversized numbers. If unavailable, use **Inter**. Use 300–500 weights; retain the unusually tight proof-number tracking. Font stack: "Stkbureausans", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| proof-number | Stkbureausans | 400 | 112px | 0.9 | -0.06em | Large outcome numerals and stacked unit words on orange cards. |
| display | Simula | 400 | 56px | 1.1 | -0.02em | Opening promise and the strongest dark chapter statement. |
| heading | Simula | 400 | 48px | 1.1 | -0.02em | Section leads, closing calls and feature-detail headlines. |
| invitation | Simula | 200 | 32px | 1.1 | normal | Newsletter invitation; an orange feature-name label uses the same dimensions on detail pages. |
| dark-card-title | Simula | 300 | 32px | 1.1 | normal | Bottom-anchored titles of illustrated dark cards. |
| proof-label | Stkbureausans | 300 | 24px | 1.4 | -0.021em | Plain-language description below each large metric. |
| subhead | Stkbureausans | 400 | 20px | 1.4 | normal | Short benefit names, emphatic support line and plan names. |
| footer-group | Stkbureausans | 300 | 20px | 1.1 | normal | Muted footer column labels. |
| body | Stkbureausans | 300 | 18px | 1.4 | normal | Hero supporting text, section introductions and long editorial prose. |
| quote | Stkbureausans | 300 | 18px | 24px | -0.01em | Centered testimonial copy. |
| navigation | Stkbureausans | 300 | 16px | 1.4 | normal | Navigation and footer links; also compact explanatory paragraphs. |
| action | Stkbureausans | 300 | 16px | 1.1 | normal | Pill button labels. |
| body-small | Stkbureausans | 300 | 14px | 1.4 | normal | Compact explanations beneath media cards. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Stkbureausans | 500 | 128px | 1.1 | normal | The integer portion of a plan price. |
| pricing pages | price-small | Stkbureausans | 300 | 48px | 1.1 | normal | Currency sign and decimal portion, aligned near the top of the giant integer. |
| capability indexes and team directories | tile-title | Stkbureausans | 400 | 24px | 1.4 | normal | Names on large capability tiles and portrait captions. |
| feature-detail navigation | feature-link-title | Stkbureausans | 400 | 16px | 1.4 | -0.0125em | Compact related-capability names. |

**Notes:**

- Serif headlines remain regular rather than bold; their -0.02em tracking is consistent at both main sizes.
- Supporting copy is lighter and smaller, with 1.4 line height. Avoid promoting all descriptive copy into 20px text.
- Only quantitative proof uses the aggressively compressed -0.06em tracking and 0.9 line height. Prices remain open at 1.1 line height.
- Keep the full number and unit treatment as typography, not artwork; preserve a generous gap before the label.

## Layout

**Density:** Airy section framing with compact interior descriptions; media occupies more space than prose.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Benefit title to description and small inline separations. |
| 12px | Footer link rhythm and input-to-terms spacing. |
| 16px | Card-grid gutters, media inset from the container and heading-to-support gaps. |
| 24px | Hero content rhythm, dark-card padding and action separations. |
| 32px | Proof-card padding, closing-call action gap and wider benefit gutters. |
| 48px | Inset for section headings, heading-to-content distance and testimonial vertical padding. |
| 64px | Opening text-panel vertical padding. |
| 80px | Desktop outer gutters and common section bottom padding. |
| 96px | Major chapter top padding and capability-index inset. |

### Containers and grids

- **ruled-container**: max width 1280px · side padding 80px. Centered desktop frame at 1440px with 1px vertical rules; headings inset another 48px, media grids another 16px.
- **three-card-grid**: 3 columns · gap 16px. Three approximately 405px cards inside the ruled frame for proof, pricing or feature explanations.
- **benefit-row**: 3 columns · gap 32px · side padding 48px. Three text benefits with small icons above the shared media demonstration.
- **asymmetric-media**: 2 columns · gap 16px. Two-to-one media pair: approximately 820×480px and 410×480px.
- **centered-lead**: max width 560px. Short centered opening for capability indexes and company pages.
- **closing-copy**: max width 630px. Centered serif closing statement within a broad oatmeal panel.
- **footer-links**: max width 1140px · 5 columns · gap 24px. Five modest, equally weighted link groups beneath the two-part newsletter row.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards-and-media | 32px |
|  | buttons | 9999px (pill) |
|  | input | 48px |
|  | footer-plaque | 20px |
|  | portrait-or-submit-circle | 50% |
| feature-detail navigation | related-feature | 24px |
| feature-detail navigation | icon-backing | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | conversion-input | `0px 20px 68px 0px rgba(95, 17, 0, 0.3)` | Warm diffuse light around the pale conversion input; not a general card elevation. |
| feature-detail navigation | selected-feature | `0px 20px 40px -25px rgba(255, 85, 12, 0.25)` | A small warm lift beneath the selected related feature. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default page field.

**CSS:** `background: #fbf8ef; color: #130f02`

**Observed:** An uninterrupted warm field is structured by fine vertical rails rather than broad background gradients.

**Transfer:** Keep most explanatory material on this field.

#### Oatmeal panel · level 1

**Use:** Closing calls, testimonials, neutral tiles and media backing.

**CSS:** `background: #f3efe2; border-radius: 32px; box-shadow: none`

**Observed:** Tone-on-tone separation is sufficient; borders are added for pricing cards but most panels remain unoutlined.

**Transfer:** Use the slight color shift to group content without heavy elevation.

#### Dark chapter · level 0

**Use:** Contrast statement and final destination.

**CSS:** `background: #130f02; color: #fbf8ef`

**Observed:** Internal rails change to dark brown; illustrations sit on a subtly lighter umber. The footer alone has rounded top corners.

**Transfer:** Use for a concentrated problem or contrast chapter; keep the remainder predominantly cream.

#### Umber inset · level 1

**Use:** Illustrated dark cards and dark fields.

**CSS:** `background: #1c180b; border: 1px solid #292519; border-radius: 32px`

**Observed:** The subtle dark-on-dark edge is visible without a shadow.

**Transfer:** Layer one step above the dark canvas, not as a cold charcoal panel.

#### Footer shell · level 0

**Use:** Newsletter, identity display, navigation and legal ending.

**CSS:** `background: #130f02; border-radius: 32px 32px 0px 0px; overflow: hidden`

**Observed:** A complete destination approximately 838px tall on desktop, with understated horizontal separators.

**Transfer:** Retain the identity-and-newsletter split and generous lower link region.

#### Highlighted comparison · level 1

**Only for:** pricing comparisons

**Use:** Emphasize the primary offering within a dense comparison.

**CSS:** `background: #ffe9e0; border-radius: 32px 32px 0px 0px`

**Observed:** A peach column contains alternating deeper-peach rows; the other columns stay neutral.

**Transfer:** Highlight a whole column rather than every positive cell.

## Components

### Navigation

**Use:** Persistent desktop orientation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; max-width: 1280px; padding: 18px 24px; border-left: 1px solid #e9e6da; border-right: 1px solid #e9e6da`

**Text style:** `navigation` — Stkbureausans 300 · 16px/1.4

**Observed:** A fixed two-tier header totals 113px: dark announcement strip above cream navigation. The wordmark and short menu group sit left; login and orange conversion action sit right. Dropdown labels carry small chevrons.

**Transfer:** Use a short announcement and a compact menu instead of stretching every item across the row.

### Primary button

**Use:** Default high-priority action.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #ff550c; color: #fbf8ef; border-radius: 9999px; height: 36px; padding: 0px 16px`

**Text style:** `action` — Stkbureausans 300 · 16px/1.1

**Observed:** Compact in navigation; the expanded version is 48px high with 24px side padding and can span the width of a pricing card.

**States:** Declared: hover background #cc3d00 and no text decoration; active outline 0px; focus-visible unknown.

### Outline button

**Use:** Secondary choice and feature-detail opening action.

**CSS:** `display: flex; align-items: center; justify-content: center; color: #130f02; background: transparent; border: 1px solid #454030; border-radius: 9999px; height: 48px; padding: 12px 24px`

**Text style:** `action` — Stkbureausans 300 · 16px/1.1

**Observed:** Same capsule construction as the primary action but visually quieter; the navigation login variant is 36px high with 16px side padding.

**States:** Declared: hover background #fbf8ef and border #a09c8f; active outline 0px; focus-visible unknown.

### Dark button

**Use:** Action within a pale closing call or surrounded by orange proof.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #130f02; color: #fbf8ef; border-radius: 9999px; height: 36px; padding: 0px 16px`

**Text style:** `action` — Stkbureausans 300 · 16px/1.1

**Observed:** A restrained black capsule under the centered proof invitation. Closing-call variants are 48px high with 24px side padding.

**States:** Declared: hover background #454030; active outline 0px; focus-visible unknown.

### Conversion input

**Use:** Low-friction first step in the opening and repeated closing split.

**CSS:** `background: #fbf8ef; border: 1px solid #ffffff; border-radius: 48px; height: 64px; max-width: 413px; padding: 8px 8px 8px 60px; box-shadow: 0px 20px 68px 0px rgba(95, 17, 0, 0.3)`

**Observed:** A leading country marker and trailing circular arrow live inside the field. A compact terms line with chevron sits underneath. The arrow is visually subdued before entry.

**Transfer:** Use a meaningful single field for the new product, with a small context icon and nested submit control; retain its soft luminous outline.

### Newsletter input

**Use:** Email signup opposite the identity plaque.

**CSS:** `background: #1c180b; border: 1px solid #292519; border-radius: 48px; height: 64px; padding: 8px 8px 8px 20px`

**Observed:** The orange 48px Subscribe capsule is inset on the right; a short muted consent line follows below. The field fills the invitation column.

**Transfer:** Preserve the nested action rather than placing a detached rectangular button below.

### Illustrated dark card

**Use:** Make an abstract problem legible in a contrast chapter.

**CSS:** `display: flex; flex-direction: column; justify-content: flex-end; background: #1c180b; border: 1px solid #292519; border-radius: 32px; padding: 24px; overflow: hidden`

**Text style:** `dark-card-title` — Simula 300 · 32px/1.1

**Observed:** Tall illustration occupies most of the card, with a serif title at bottom left and a small circular plus control at bottom right. Related explanatory text is kept compact.

**Transfer:** Use a simple low-contrast diagram with one coral or orange signal, leaving clear space for the title.

### Proof card

**Use:** Emphatic quantified outcome.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #ff550c; border: 1px solid #ffffff; border-radius: 32px; padding: 32px; overflow: hidden`

**Text style:** `proof-number` — Stkbureausans 400 · 112px/0.9 · tracking -0.06em

**Observed:** The unit word is stacked directly under the number. A 48px spacer separates the large peach type from the smaller cream proof label; three equal cards create one concentrated orange event.

**Transfer:** Keep the type-led construction even with different metrics; choose short unit words.

### Testimonial card

**Use:** Human proof in a horizontally overflowing carousel.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: space-between; background: #f3efe2; border-radius: 32px; padding: 48px 32px; max-width: 680px; gap: 48px`

**Text style:** `quote` — Stkbureausans 300 · 18px/24px · tracking -0.01em

**Observed:** Orange stars precede a centered quote; name and review platform follow. The selected card stays strong while neighboring cards are faded to about 0.4 opacity. Pagination uses 8px dots with a 24px-wide orange active marker.

**Transfer:** Use real concise quotations and retain the visible neighboring-card continuity.

### Footer link columns

**Use:** Utility navigation beneath the newsletter row.

**CSS:** `display: grid; grid-template-columns: repeat(5, 1fr); column-gap: 24px; row-gap: 16px; max-width: 1140px`

**Text style:** `navigation` — Stkbureausans 300 · 16px/1.4

**Observed:** Five groups use muted 20px titles above cream 16px links with 12px vertical gaps. Social links include compact monochrome marks. Fine print occupies a separate ruled base.

**Transfer:** Match the breadth and hierarchy of the utility region without expanding every link into a button.

### Pricing card

**Only for:** pricing pages

**Use:** Present a small family of membership choices.

**CSS:** `display: flex; flex-direction: column; justify-content: center; background: #f3efe2; border: 1px solid #e9e6da; border-radius: 32px; padding: 32px 24px; gap: 48px`

**Text style:** `subhead` — Stkbureausans 400 · 20px/1.4

**Observed:** Plan name and optional saving badge sit above a centered price. The integer is much larger than currency and decimals. A full-width orange capsule is followed by plain billing and cancellation language.

**Transfer:** Keep all plan cards equally calm; reserve stronger tinting for the comparison table rather than adding a flashy recommended-plan banner.

### Related feature link

**Only for:** feature-detail navigation

**Use:** Offer adjacent capabilities after the feature story.

**CSS:** `display: flex; align-items: center; gap: 24px; background: #fbf8ef; border: 1px solid #ff550c; border-radius: 24px; padding: 16px; box-shadow: 0px 20px 40px -25px rgba(255, 85, 12, 0.25)`

**Text style:** `feature-link-title` — Stkbureausans 400 · 16px/1.4 · tracking -0.0125em

**Observed:** The selected link has an orange edge and tinted icon square; ordinary links use a pale edge with no shadow. Each has a compact title above one short description. A coming-soon variant is muted.

**States:** Declared: hover border #a09c8f, box-shadow none and opacity 1; active outline 0px; focus-visible unknown.

## Imagery and graphics

### Human scenes with outcome overlays

**Use:** The opening, capability explanation and final conversion split.

**Observed:** Natural urban and indoor scenes show people using phones in everyday moments. Clothing and interiors are warm and tactile, with subdued backgrounds, soft daylight or lamplight and no aggressive color grading. Large 32px-radius frames carry rounded olive-smoke or pale interface fragments, often offset to the side of the person rather than covering the face.

**Transfer:** Photograph a believable moment in the new product's use, then add one simple outcome panel. Minimum version: one well-lit human scene and a clear status card; no need to recreate a full application.

**Build:** Place a 606×514px object-fit:cover image in a 32px-radius clipping frame. Overlay a roughly 200×155px rounded card near its upper left, using an olive-black fill at about 0.75 alpha, a subtle blur and cream labels. Draw an SVG semicircular status track with three colored arcs and one short white marker, or replace the gauge with an equally simple product outcome. Keep the panel subordinate to the human subject.

### Tall capability stories

**Use:** Image-led explanation cards and horizontal product rail.

**Observed:** 360×480px or 405×480px media show warm lifestyle scenes, a hand holding a phone, or pale browser panels on a peach-to-orange backing. One or two layered UI fragments explain the benefit; captions live outside the image.

**Transfer:** Alternate human context and readable product detail at the same tall aspect ratio. Keep one action or result legible rather than shrinking an entire dashboard.

**Build:** For a media-free alternative, fill the rounded frame with a pale peach field fading toward orange near the bottom. Place two ivory browser-like rectangles, one large near the upper-left and one smaller overlapping its lower-right edge. Give each restrained neutral rules, one meaningful status and only a small accent action; use soft diffuse shadows, not thick outlines.

### Dark problem diagrams

**Use:** Illustrated cards in the brown-black contrast chapter.

**Observed:** Low-contrast dark illustrations show overlapping identity cards, a message alert and connected location tiles. Coral red outlines and warning marks are sparse; black fades preserve title readability near the bottom.

**Transfer:** Use two or three recognizable objects to diagram the new problem rather than adopting alarmist stock photography.

**Build:** Within a 405×444px umber card, stack three rounded rectangles rotated between -12deg and 12deg, or connect small tiles with thin orange SVG paths. Use #292519 fills, muted cream markings and coral strokes at reduced opacity. Add a bottom black gradient from transparent to rgba(0,0,0,0.9) at 0.3 overall opacity; leave the bottom quarter for the title.

### Proof portrait constellation

**Use:** Humanize the centered proof invitation.

**Observed:** Small circular portraits approximately 67px across are staggered at the two sides of a centered headline, leaving the copy unobstructed. Their natural colors are varied but quiet.

**Transfer:** Use authentic customer or collaborator portraits where permitted; without suitable portraits, replace the constellation with small circular detail photographs of real product-use contexts.

**Build:** Arrange four 67px circular image masks on each flank of a centered 748px text block, alternating vertical positions. Clip with border-radius:50%, maintain clear separation from the text and keep the circles independent rather than drawing connecting lines.

### Capability index mosaic

**Only for:** capability index pages

**Use:** A browsable catalogue below a short centered opening.

**Observed:** A three-column mosaic alternates 825×400px two-column photographic tiles with approximately 405px-wide oatmeal tiles. Photos have bottom darkening and cream captions; plain tiles have a black outline icon at top, text near the bottom and a circular arrow.

**Transfer:** Let major capabilities occupy wide human scenes and minor ones use flat icon tiles; preserve the alternating weight rather than making a uniform screenshot wall.

### Company photography and directory

**Only for:** company and team pages

**Use:** Culture strip, founders and people roster.

**Observed:** A loose horizontal strip mixes candid event images with varied aspect ratios. Formal portraits share bright warm office lighting and rounded corners; founders occupy two columns and leaders three. Names use 24px sans, with muted 18px roles; the extended team becomes a three-column text directory.

**Transfer:** Use consistent environmental portraits for leadership, candid images for culture and lighter text-only treatment for a large roster. Keep names and roles left aligned.

### Icons

**Observed:** Small navigation chevrons are about 13px. Common inline icons are 16px with 1.5px rounded strokes; larger capability icons use 32px with 2px rounded strokes. Orange or ink line art sits on small pale backing squares; round arrow controls are outlined rather than solid square buttons.

**Transfer:** Choose simple rounded-stroke symbols at these sizes; use filled icons sparingly for checks, social marks or platform identity. Keep orange icon accents local to a benefit or action.

## Section recipes

How recurring sections are built.

### First screen: Human split opening

**Observed:** The fixed Navigation sits above an equal split within the ruled-container. The cream text half has 64px vertical and 48px horizontal inset; a 56px serif promise wraps to roughly three lines over a 543px measure, followed by a 20px emphasis line, muted 18px support and Conversion input. The right half is a 606×514px Human scenes with outcome overlays frame, inset 16px and rounded 32px. Layers read cream rails, photograph, floating outcome panel, text and action. The hero ends at about 652px: within the first 900px the complete headline, support, field and main image are visible, together with the opening of a full-width dark statement. Its illustrated cards fall below that first view.

**Transfer:** Create the same balance with a real use-context image and one outcome overlay; if the product has no visual interface, show a task or person benefiting from it and a compact result card. A pricing opening instead centers the promise and billing switch above three cards; capability and company indexes use a 560px centered serif lead with a single pill action. Feature-detail pages retain the split but add a 32px orange feature label and an outline action.

**Avoid:** Do not turn this into a centered giant headline above a floating device render, or replace the image half with a grid of tiny app screenshots.

**Text style:** `display` — Simula 400 · 56px/1.1 · tracking -0.02em

### Dark contrast chapter

**Observed:** Dark chapter keeps the same 1280px rails with 96px top and 80px bottom spacing. A left-aligned serif statement and short gray support line precede either three Illustrated dark cards or a three-benefit row over an asymmetric media pair. Selected warning words turn coral, not the whole headline.

**Transfer:** Frame the real friction the new product solves, then make the mechanism tangible with diagrams or a contrasting use scene.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

### Benefit heading and shared demonstration

**Observed:** A 48px left-aligned lead is inset 48px within the rails. Three compact benefit columns use small orange icons, 20px names and 14px descriptions with 8px internal gaps; a 32px gap leads to the asymmetric-media pair.

**Transfer:** Divide one broad promise into three short mechanisms, then demonstrate them together rather than assigning every paragraph its own box.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

### Capability carousel

**Observed:** A 48px serif heading shares its row with small outlined circular previous and next controls. Tall capability stories sit below with 16px gutters; a fourth card continues beyond the visible rail. Labels and compact descriptions are outside the pictures.

**Transfer:** Use horizontal continuity to show breadth without reducing image size. Keep the next card visibly entering the edge.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

### Media spotlight

**Observed:** A centered or left-aligned 48px lead introduces large 863×485px video or press-image slides. A white circular play control with orange triangle marks playable content; neighboring content is visibly subdued.

**Transfer:** Use this recipe only for genuine demonstrations, interviews or third-party coverage, keeping the media large enough to read.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

### Concentrated proof

**Observed:** A centered 48px serif invitation is surrounded by the Proof portrait constellation and a small Dark button. Three Proof cards follow with 16px gutters. A centered Testimonial card carousel below changes the tempo back to oatmeal and small text.

**Transfer:** Separate quantitative outcomes from human testimony while treating them as a single trust chapter; retain the bright type-led proof device wherever it fits the story.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

### Closing conversion split

**Observed:** A broad Oatmeal panel on the left contains a small trust-mark row, a 48px serif statement, short gray support and Conversion input. A rounded photograph on the right carries another outcome overlay. This repeats the opening action at a more reassuring moment.

**Transfer:** Return to one clear action after proof. Use relevant verification or reputation marks above the copy, and show a different everyday context from the opening.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

### Centered closing call

**Observed:** A rounded Oatmeal panel holds a 630px centered text block with a 48px serif statement, 18px support after 16px and one or two pill actions after 32px. Vertical breathing room is 80px.

**Transfer:** Use for a focused feature or company ending; pair a dark primary capsule with an outlined alternative when two paths are genuinely useful.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

### Identity and newsletter ending

**Observed:** Footer shell begins with a two-part row about 288px high: a broad 20px-radius umber identity plaque at left and a serif invitation with Newsletter input at right. A fine dark rule separates five Footer link columns, then another rule separates restrained legal text. It is not merely a narrow copyright bar.

**Transfer:** Make the new identity a large calm object and the signup a secondary destination, then provide a complete utility region.

**Text style:** `invitation` — Simula 200 · 32px/1.1

### Pricing and comparison

**Only for:** pricing pages

**Observed:** A centered 56px serif promise is followed by an 18px flexibility line, a 188×48px segmented billing pill and three Pricing cards. Below, a 305px label column meets 195px comparison columns with 64px rows; the main offering receives Highlighted comparison and peach striping. Orange check marks and sparse crosses carry the comparison. Testimonials precede the shared footer.

**Transfer:** Keep plan choice emotionally simple first, then use the dense table for detailed differentiation. Make billing terms plain and adjacent to the action.

**Text style:** `display` — Simula 400 · 56px/1.1 · tracking -0.02em

### Editorial company story

**Only for:** company pages

**Observed:** After a centered serif opening and loose candid-photo strip, a two-column founder letter places a 48px title and handwritten signatures on the cream left side and long 18px prose in a tall Oatmeal panel on the right. Portrait grids transition from two founders to three-column leadership and then a compact text-only directory. A centered closing call leads to the shared footer.

**Transfer:** Use an authentic origin account with a visible human author; vary the treatment between long-form story, portraits and directory instead of repeating cards throughout.

**Text style:** `heading` — Simula 400 · 48px/1.1 · tracking -0.02em

## Page flow

**Storyline:** Promise → friction made visible → mechanisms and demonstrations → human and quantitative proof → renewed action → identity-led utility ending.

### Broad consumer product landing page

1. **Promise** — Human split opening with a low-friction single-field action.
2. **Problem framing** — Brown-black illustrated chapter with selective coral words.
3. **Mechanisms** — Three compact benefits over a wide human scene and narrow device scene.
4. **Capability breadth** — Tall media carousel with captions beneath.
5. **Third-party proof** — Large media spotlight slides.
6. **Quantified and human proof** — Portrait constellation, giant orange metrics and testimonial carousel.
7. **Renewed action** — Pale conversion split with another human scene.
8. **Utility ending** — Shared identity-and-newsletter footer.

**Transfer:** Adapt the tension and proof depth to the product; retain the warm human opening, concentrated proof and complete footer without requiring this exact section sequence.

### Membership selection and detailed evaluation

1. **Choice framing** — Centered promise and billing switch above three equal plan cards.
2. **Detailed comparison** — Striped table with a peach primary column.
3. **Reassurance** — Large testimonial carousel.
4. **Utility ending** — Shared identity-and-newsletter footer directly after reviews.

**Transfer:** Lead with a few comprehensible choices, then disclose the detailed comparison; no additional promotional ending is needed.

### Focused capability explanation

1. **Orientation** — Previous and next capability links with a small central category tag.
2. **Focused promise** — Split hero with orange serif capability name and hand-held product photo.
3. **Problem framing** — Dark benefits and two-to-one media pair.
4. **Demonstration** — Three tall media explanations with compact captions.
5. **Closing call** — Centered oatmeal statement with dark and outline actions.
6. **Adjacent discovery** — Three-column compact related-feature links.
7. **Utility ending** — Shared identity-and-newsletter footer.

**Transfer:** Keep one capability as the main argument, with related discovery deferred until after the action.

### Browse the complete capability set

1. **Breadth promise** — Short centered serif introduction and outlined action.
2. **Capability discovery** — Three-column mosaic alternating wide photographic tiles and plain icon tiles.
3. **Utility ending** — Shared identity-and-newsletter footer immediately after the mosaic.

**Transfer:** Replace long narrative with a weighted visual catalogue; let media and tile size express priority.

### Establish human authorship and organizational trust

1. **Mission** — Centered serif statement and orange recruiting action.
2. **Culture context** — Loose moving strip of candid images.
3. **Origin story** — Split founder letter with signatures and tall prose panel.
4. **People proof** — Founder pair, leadership portrait grid and extended text-only roster.
5. **Invitation** — Centered oatmeal mission call with dark capsule.
6. **Utility ending** — Shared identity-and-newsletter footer.

**Transfer:** Use real people, an authored account and a proportionate team treatment; keep the culture motifs scoped to organizational storytelling.

## Writing

Protective, direct and conversational, with an editorial seriousness softened by practical reassurance. The copy names a concrete problem, then offers agency rather than abstract technological superiority.

**Do not copy:** Do not reuse Cloaked names, logos, proprietary illustrations, customer portraits or quotes, numerical claims, insurance promises, coverage counts or brand-specific assertions. Replace them with the new product's own assets and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to 'you' and 'your'; use 'we' for practical actions the service performs. Collective and family language makes consequences feel human rather than technical.
- **Rhythm:** Headlines are usually one sentence of about 5–12 words, sometimes wrapping across three lines. Supporting blocks are one or two direct sentences; card explanations are compact. Actions are brief verb phrases rather than clever slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a tangible problem or desired control in a direct sentence. | 6–10 words | “Fight against surveillance, spam, & identity theft.” |
| Supporting emphasis | A short human truth, followed by practical explanation. | 6–12 words for the emphasis | “You can’t fight what you can’t see.” |
| Benefit label | Active verb plus a clear time horizon or outcome. | 3–5 words | “Clean your past exposure” |
| Section question | Ask the reader's practical mechanism question without marketing jargon. | 6–10 words | “How does [Brand] protect my data?” |
| Primary action | Literal verb phrase describing the next step. | 2–3 words | “Get Started”<br>“Scan for Exposure” |
| Pricing reassurance | Plain flexibility and cancellation language close to the choice. | One short sentence | “Easily switch plans at any time” |
| Closing invitation | Give the reader agency through a concrete shared mission. | 8–12 words | “Join the mission to create a more private online world” |

**Words and phrasing to use:** take back control; protect; your; we; one tap; stop; generate; remove; together

**Avoid:** revolutionary ecosystem; next-generation synergy; military-grade everything; effortless magic; vague superlatives

**Rules:**

- Pair every emotionally charged problem statement with an understandable mechanism or action.
- Use specific evidence in proof blocks and plain descriptions of what the metric measures.
- Keep interface and action language literal; reserve expressive language for the serif statements.
- Use the new product's actual stakes: do not import fear-based language into a low-risk category.

## Do's and Don'ts

### Do

- Keep serif headings regular at 56px or 48px with 1.1 line height and -0.02em tracking.
- Align desktop chapters to the 1280px ruled frame with 80px outer gutters.
- Use 16px gutters for image and proof grids, with 32px corners across their frames.
- Concentrate orange in a deliberate proof cluster and the small action system.
- Stage at least one credible human use scene with a restrained floating outcome panel.
- Use 112px/0.9 sans proof type with a separate 24px descriptive label.
- Give the footer its own 32px top corners, wordmark plaque, newsletter row and five-column utility region.
- Retain the 64px nested-action input silhouette when adapting the lead-generation interaction.

### Don't

- Do not substitute a cold white-and-blue SaaS palette for the cream, oatmeal and brown-black neutral ramp.
- Do not make every heading a bold sans; the serif-to-sans contrast is fundamental.
- Do not apply the warm input glow as a shadow system on all cards.
- Do not put thick black outlines on pale 32px-radius panels; separation is mostly tonal or a 1px cream rule.
- Do not use orange as the background of every alternating section; its large-area role is concentrated quantitative proof.
- Do not make pricing integers serif or give them the proof number's compressed line height; prices use 128px sans at 1.1.
- Do not replace the bottom identity-and-newsletter destination with a compact legal strip.
- Do not fade main testimonials to 0.4 opacity; that treatment belongs to neighboring slides only.

## Motion and responsive

### Motion

**Observed:**

- Declared dark-card width transition: 0.3s.
- Declared outline-action background-color transition: 0.3s.
- Declared testimonial opacity transition: 0.25s ease-out; neighboring slides are visibly faded.
- Declared 3s ease-in-out infinite bounce animations and a 25s linear infinite scroll animation occur in the broader page styling.

**Transfer:**

- Preserve the contrast between an opaque selected testimonial and faded neighboring slides.
- Use width or opacity changes to support the existing card and rail architecture, not to create a separate cinematic opening.

**Unknown:**

- Exact triggers and trajectories of decorative movement are not established.
- Focus-visible styling and most interaction timing beyond the listed declarations are unknown.

### Responsive

**Observed:**

- CSS includes width breakpoints at 479px, 767px, 768px, 991px, 1280px, 1440px and 1920px; other page-specific breakpoints also exist.

**Transfer:**

- Recommended adaptation: stack the opening copy above its rounded human scene, preserving one legible outcome overlay.
- Recommended adaptation: collapse the three-card grids to one column while retaining 16px gutters and readable internal spacing; let intentional media rails remain horizontal.
- Recommended adaptation: place the footer plaque above the newsletter and wrap the five link groups without compressing their text.

**Unknown:**

- Mobile arrangements, type-size overrides and navigation collapse behavior were not observed.
- No viewport-relative type formulas are established; the desktop recipes are fixed measured roles.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
