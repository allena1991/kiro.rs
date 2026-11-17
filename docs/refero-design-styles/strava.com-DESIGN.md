# Strava — shared momentum, orange heat

## Overview

An energetic, people-first style that makes personal progress feel like belonging to a team. Wide geometric sans headlines, warm black-and-white foundations and concentrated orange accents balance expansive photography with approachable product explanations. It suits consumer tools, memberships and products that turn individual effort into shared achievement; the overall density is airy, with darker, more immersive moments punctuating a light page.

### Essentials

- Headlines stretch sideways rather than shout in condensed capitals: BoathouseExtended at 72px/1 and 60px/1.2, weight 600, normal tracking; mixed-case lines occupy an approximately 811px text measure.
- The default opening feels like a membership ceremony: a full-width 798px dark, ember-lit stage, small emblem above centered white type, one orange action and a giant low-contrast seal cut off at the lower right. Recreate the emblem and seal with the new product's own simple geometry.
- Orange acts as heat, not a blanket: #fc5200 belongs to actions, small status chips, checks and restrained graphic marks. Most explanatory content remains white; large color fields belong to the opening atmosphere or a dedicated closing campaign band.
- Actions are sturdy rectangles, not lifestyle pills: 4px corners, 64px height, 16px 24px padding and 22px/28px semibold labels for the default marketing button.
- Evidence of usefulness is staged as an object: three 384px-wide product illustrations sit across a white field with 32px visible gutters, followed by centered 28px/34px benefit titles and 22px/28px support. Without interface media, use a simplified, legible diagram of an actual product outcome.
- A monumental belonging statement gives the page an emotional landing: 60px/72px white extended type over full-bleed, warmly shaded human photography, then a #353633 directory footer. Use a truthful outcome or invitation rather than relying on a repeated button. If photography is unavailable, carry the same statement on the ember-lit stage.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange | `#fc5200` | `--color-orange` | action, link, accent | Primary actions, feature chips, comparison checks and graphic paths; also the heat source in atmospheric artwork. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep ember | `#450600` | `--color-ember` | background, accent | Dark red atmosphere within hero artwork and flat geographic artwork; match the warm red-black feeling rather than exact gradient stops. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default explanatory canvas and text on dark media. The fixed light navigation uses this hue at 98% opacity. |
| Near-white | `#fafafa` | `--color-soft` | background, surface | Comparison and question bands; secondary authentication buttons. |
| Cool navigation edge | `#f0f0f5` | `--color-nav-rule` | border | Light fixed-navigation bottom and account-action divider. |
| Soft rule | `#e0e0de` | `--color-rule` | border | Question-row separators and compact outline actions. |
| Lavender grey | `#b2afc0` | `--color-muted` | text | Footer category headings and secondary legal information. |
| Graphite edge | `#555555` | `--color-edge` | border | Underlines beneath secondary directory legal links. |
| Warm graphite | `#43423f` | `--color-body` | text | Supporting paragraphs and compact footer links. |
| Directory charcoal | `#353633` | `--color-footer` | background | Long-form marketing directory footer. |
| Warm ink | `#21211f` | `--color-ink` | text, surface | Benefit titles, tab labels and compact dark community cards. |
| True black | `#000000` | `--color-black` | text, background, surface | Major headings, immersive bands and pricing panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| registration and acquisition pages | Warm off-white | `#f9f8f5` | `--color-cream` | background | Compact directory footer. |
| registration pages | Authentication edge | `#64635e` | `--color-auth-edge` | border, text | Secondary authentication action outlines and existing-member prompt. |

## Typography

- **Boathouse** — Body, actions, navigation and benefit titles. Open, friendly sans with a practical human tone and generous counters. If unavailable, use **Lato**. Use 400, 600 and 700; preserve the open body spacing rather than tightening it. Font stack: "Boathouse", "Lato", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **BoathouseExtended** — Default marketing display and section headlines, plus large pricing figures. Broad geometric sans with rounded bowls and a distinctive horizontally expansive silhouette. If unavailable, use **Montserrat**. Use 600 and retain wide mixed-case measures; do not substitute a condensed face. Font stack: "BoathouseExtended", "Montserrat", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Arial** (only for membership question accordions) — Large question labels. Plain system sans, visually separate from the extended marketing headlines. Font stack: "Arial", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | BoathouseExtended | 600 | 72px | 1 | normal | Default hero headline; white, centered and wrapped into two balanced lines. |
| heading-lg | BoathouseExtended | 600 | 60px | 1.2 | normal | Chapter headings, broad positioning statements and monumental closing copy. |
| heading | BoathouseExtended | 600 | 48px | 56px | normal | Comparison-table introductions. |
| hero-support | Boathouse | 400 | 34px | 41px | normal | White hero and photographic chapter support. |
| benefit-title | Boathouse | 600 | 28px | 34px | normal | Feature benefits, short narrative subheads and onboarding step titles. |
| body | Boathouse | 400 | 22px | 28px | normal | Feature descriptions and comparison-row labels. |
| action | Boathouse | 600 | 22px | 28px | normal | Default filled marketing actions and prominent text actions. |
| chapter-tab | Boathouse | 600 | 22px | 1.1 | 0.09em, uppercase | Sticky chapter navigation on long product explanations. |
| nav | Boathouse | 400 | 20px | 29px | normal | Opening navigation links over dark media. |
| new-chip | Boathouse | 700 | 17px | 21px | normal, uppercase | Short release marker above benefit titles. |
| footer-link | Boathouse | 400 | 13px | 16px | normal, uppercase | Long-form directory links. |
| footer-heading | Boathouse | 700 | 13px | 16px | normal, uppercase | Muted directory category headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| activity-specific acquisition pages | acquisition-display | Boathouse | 600 | 80px | 1.1 | normal | Left-aligned photographic hero rather than the default extended display. |
| pricing comparisons | price | BoathouseExtended | 600 | 60px | 29px | normal | Large price on a black panel; keep the short line box isolated from adjacent lines. |
| membership and company narratives | split-heading | BoathouseExtended | 600 | 48px | 1.25 | normal | Split media/text stories and onboarding introductions. |
| activity-specific acquisition pages | acquisition-heading | Boathouse | 600 | 48px | 1.1 | normal | Community and editorial section headlines. |
| membership question accordions | question | Arial | 400 | 34px | 41px | normal | Large conversational question labels. |
| registration pages | registration-heading | Boathouse | 600 | 32px | 1 | normal | Compact centered promise between photographic side panels. |
| membership and company narratives | editorial-body | Boathouse | 400 | 24px | 34px | normal | Wider narrative paragraphs beside product or people media. |
| pricing comparisons | plan-label | Boathouse | 600 | 22px | 28px | 0.08em, uppercase | Plan names over price figures. |
| pricing comparisons | plan-body | Boathouse | 400 | 17px | 22px | normal | Compact plan inclusions. |

**Notes:**

- The extended face provides breadth, not extra tracking. Keep normal tracking on all large mixed-case headlines; tracking is reserved for uppercase tabs and plan labels.
- Body text is unusually substantial on long-form marketing: use 22px/28px rather than shrinking every explanation to interface size.
- Keep the compact acquisition and registration systems scoped; they use the regular sans for display and should not replace the default extended headline.

## Layout

**Density:** Airy, with large uninterrupted media bands and generous white space around tightly grouped benefit copy.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight compact-control and small copy spacing. |
| 16px | Benefit title-to-description gap and inner horizontal column inset. |
| 24px | Hero headline-to-support and support-to-action gaps; button horizontal padding. |
| 32px | Visible benefit gutters, pricing gaps and media-to-copy spacing. |
| 64px | Comparison row rhythm and acquisition section padding. |
| 72px | Split-story and comparison section vertical padding; heading-to-table separation. |
| 80px | Chapter-navigation horizontal gaps. |
| 128px | Default long-form section top and bottom padding. |

### Containers and grids

- **marketing-frame**: max width 1248px · side padding 16px. Centered desktop frame; at 1440px the outer frame starts 96px from either side and the content begins at 112px.
- **headline-measure**: max width 811px. Centered hero and major section headline/support measure.
- **benefit-grid**: 3 columns · gap 32px. Three equal 384px media/text columns across the content frame. Columns use 16px inner side insets, creating the visible gutter.
- **comparison-measure**: max width 616px. Narrow, centered two-tier feature comparison; broader three-tier membership tables use the full 1216px inner frame.
- **acquisition-frame** (only for activity-specific acquisition pages): max width 1728px · side padding 64px. Wider 1312px desktop working area for community and article rows.
- **editorial-grid** (only for activity-specific acquisition pages): 4 columns · gap 32px. Four 304px-wide story thumbnails with unboxed text beneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-chips | 4px |
| pricing comparisons | pricing-panels | 6px |
| community directories | community-panels | 5px |
| question accordions | open-question-top | 8px |
| pricing comparisons | recommendation-badge | 9999px (pill) |
| community directories | profile-images | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | sticky-navigation | `0px 13px 26px 0px rgba(0, 0, 0, 0.09)` | Soft downward shadow for sticky chapter tabs and light navigation. |
| company team sections | portrait | `0px 10px 20px 0px rgba(0, 0, 0, 0.1)` | Small lift beneath square leadership portraits. |

### Surfaces

#### White canvas · level 0

**Use:** Default explanation field.

**CSS:** `background: #ffffff`

**Observed:** Feature groups live directly on the canvas, not inside another card.

**Transfer:** Let media supply the contrast while the surrounding text remains unboxed.

#### Ember stage · level 0

**Use:** Default opening atmosphere.

**CSS:** `background: radial-gradient(ellipse at 90% 120%, rgba(252, 82, 0, 0.95) 0%, rgba(252, 82, 0, 0) 55%), linear-gradient(180deg, #000000 0%, #450600 100%); overflow: hidden`

**Observed:** A near-black upper field moves through deep red into orange light along the lower edge, strongest toward the right. Typography stays flat white above it.

**Transfer:** Match the soft red-orange heat; exact stops are not essential. Reserve the brightest region for the edge, not directly behind the headline.

#### Pale information band · level 0

**Use:** Comparison and question sections.

**CSS:** `background: #fafafa; padding: 72px 0px`

**Observed:** Very slight tonal separation rather than a colored pricing wash.

**Transfer:** Use when the content becomes tabular or question-led.

#### Directory charcoal · level 0

**Use:** Default long-form footer.

**CSS:** `background: #353633; padding: 83px 0px 116px; color: #ffffff`

**Observed:** A deep, flat, warm charcoal field; no decorative gradient or surrounding card.

**Transfer:** Keep the closing navigation utilitarian after the expressive last section.

#### Light navigation · level 2

**Use:** Scrolled top navigation.

**CSS:** `background: rgba(255, 255, 255, 0.98); border-bottom: 2px solid #f0f0f5; height: 64px`

**Observed:** An almost opaque white bar with a small orange brand lockup and a right-aligned account action.

**Transfer:** Let the immersive opening navigation simplify when the reader reaches the white content.

#### Compact cream footer · level 0

**Only for:** registration and acquisition pages

**Use:** Shorter directory ending.

**CSS:** `background: #f9f8f5; padding: 64px; color: #43423f`

**Observed:** Approximately 360px tall with store badges and social icons on the left and compact link columns to the right.

**Transfer:** Use for a transactional or direct-response page rather than the flagship long-form ending.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `display: inline-flex; background: #fc5200; color: #ffffff; border: 2px solid #fc5200; border-radius: 4px; padding: 16px 24px; min-height: 64px; box-sizing: border-box; justify-content: center`

**Text style:** `action` — Boathouse 600 · 22px/28px

**Observed:** Usually one action, centered under a hero or group of benefits. A dedicated orange closing campaign uses a white-filled, black-text variant.

**Transfer:** Use a concrete verb tied to the benefit immediately above.

### Opening navigation link

**Use:** Simple editorial navigation over immersive media.

**CSS:** `color: #ffffff; padding-bottom: 10px; text-decoration: none`

**Text style:** `nav` — Boathouse 400 · 20px/29px

**Observed:** Brand lockup at left, four spaced links in the center, account links at right; no heavy boxed menu treatment. The scrolled bar reduces to brand and account action.

### Chapter tabs

**Use:** Persistent navigation through long capability chapters.

**CSS:** `display: flex; justify-content: center; gap: 80px; height: 78px; background: #ffffff; box-shadow: 0px 13px 26px 0px rgba(0, 0, 0, 0.09); position: sticky; z-index: 110`

**Text style:** `chapter-tab` — Boathouse 600 · 22px/1.1 · tracking 0.09em · uppercase

**Observed:** Three uppercase chapter labels. The selected item has a fine orange underline; the row sits immediately below the hero and remains beneath the light header.

### Benefit item

**Use:** A single product capability within the three-column explanation.

**CSS:** `padding: 0px 16px; text-align: center`

**Text style:** `benefit-title` — Boathouse 600 · 28px/34px

**Observed:** Media first, optional New chip, title, then body description after a 16px gap. The artwork is 384px by about 342px. The text block has no enclosing border or shadow.

**Transfer:** Use one distinct outcome per item; make each image explain a different capability.

### New chip

**Use:** Small release signal above a benefit title.

**CSS:** `display: inline-flex; background: #fc5200; color: #ffffff; border-radius: 4px; padding: 4px 6px`

**Text style:** `new-chip` — Boathouse 700 · 17px/21px · uppercase

**Observed:** Centered between the artwork and title, not attached to the corner of a card.

### Directory link

**Use:** Default footer navigation.

**CSS:** `color: #ffffff; text-decoration: none`

**Text style:** `footer-link` — Boathouse 400 · 13px/16px · uppercase

**Observed:** Short uppercase labels in a long single column; muted category labels precede each group. Social links pair a small white platform icon with text. Legal links use muted grey and a subtle graphite underline.

### Question row

**Only for:** membership question accordions

**Use:** Objection handling in a pale information band.

**CSS:** `display: flex; justify-content: space-between; gap: 16px; background: #ffffff; padding: 16px 8px 16px 16px; border-radius: 8px 8px 0px 0px`

**Text style:** `question` — Arial 400 · 34px/41px

**Observed:** Large left question and a simple 24px chevron at right. The surrounding accordion item ends with a 1px soft rule. Open answers appear on the pale band beneath; later rows may remain collapsed.

**Transfer:** Keep the entire question row interactive and preserve readable wrapping for longer questions.

### Plan panel

**Only for:** pricing comparisons

**Use:** Equal-footing comparison of membership tiers.

**CSS:** `display: flex; flex-direction: column; gap: 32px; background: #000000; color: #ffffff; border-radius: 6px; padding: 72px 32px 24px; width: 384px; min-height: 454px; box-sizing: border-box`

**Text style:** `plan-label` — Boathouse 600 · 22px/28px · tracking 0.08em · uppercase

**Observed:** Plan name, large extended price, compact inclusions and billing note anchored near the bottom. All tiers stay black; the preferred tier is distinguished by a white pill above its label, not by an orange panel.

### Community tile

**Only for:** community directories

**Use:** Repeated people or group proof against a black band.

**CSS:** `background: #21211f; border-radius: 5px; padding: 24px 8px; width: 176px; min-height: 252px; box-sizing: border-box`

**Observed:** A 160px square image area precedes a short white caption. People are circular, groups use logo artwork. Rows contain six tiles at desktop with 16px gaps; verification marks sit over image corners.

**Transfer:** Use authentic community portraits or partner marks; retain the contrast between black band and warm charcoal tiles.

### Authentication button

**Only for:** registration pages

**Use:** Provider-based account creation.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #fafafa; color: #21211f; border: 1px solid #64635e; border-radius: 4px; padding: 10px 50px; height: 44px; width: 404px; box-sizing: border-box`

**Observed:** 16px semibold sans labels use normal line height. Provider icon sits on the left while the label remains centered. Stack provider choices above a filled orange email action with 8px separation.

## Imagery and graphics

### Membership emblem and seal

**Use:** Signature brand-neutral device for the default opening.

**Observed:** A small orange outlined badge sits above the headline; a much larger, almost black circular seal is pushed into the lower-right corner and clipped by two edges. The large seal is atmospheric, not readable UI.

**Transfer:** Use an original geometric emblem related to the new product's promise. The minimum version is a simple outlined shield or medallion repeated at two scales.

**Build:** Draw a roughly 72px outlined pentagonal badge in SVG with a 4px orange stroke and a simple inner angular symbol. Duplicate its geometry within a roughly 480px circular ring, render black at low contrast, rotate slightly and position partly outside the lower-right edge of the Ember stage. Keep the small emblem centered above the headline; keep the large duplicate behind text.

### Human photographic chapters

**Use:** Full-width benefit chapter banners and the monumental closing statement.

**Observed:** Candid people in motion, natural outdoor greens, dusty earth and warm light. Subjects are often right-weighted, leaving landscape for white left-aligned copy. Closing imagery is more immersive, with people entering from the foreground edges and a warm orange-red veil. Banners span the viewport and range from about 493px to 565px tall; the closing scene is 758px tall.

**Transfer:** Photograph real use and human results in the new domain, not isolated glossy objects. Keep environmental context and room for copy. Without photography, use the Ember stage for the closing statement rather than fake stock lifestyle scenes.

### Product benefit artwork

**Use:** Three-column product explanations.

**Observed:** Dark, gently rounded backing plates contain enlarged interface fragments: charts, short insight text, maps and outcome badges. The UI floats within the plate with subtle warm edge light; the external page stays white. Each artwork is about 384px by 342px and outweighs its text block.

**Transfer:** Show one believable workflow or output per image. If no finished interface exists, create a restrained dark diagram with one primary metric, one line chart or one result; avoid rendering tiny illegible dashboard screens.

### Phone stories

**Only for:** membership narratives

**Use:** Alternating split media/text explanations.

**Observed:** Upright black phone hardware with rounded glass corners and a soft contact shadow, isolated on white. A 384px by 670px media allocation contains a narrower phone; adjacent type occupies roughly twice that column's width.

**Transfer:** Show only the relevant step or result in a realistic device, switching sides between stories. For a non-mobile product use an equally tall focused interface panel rather than unrelated hardware.

### Route ribbon and achievement seals

**Only for:** activity-specific acquisition campaigns

**Use:** Playful graphic interruptions and compact achievement proof.

**Observed:** A thick orange freehand path enters from the edges of a white section, bending into loops and a zigzag. Four orange scalloped achievement seals carry white outlined numerals and small illustrative details.

**Transfer:** Translate movement into a path or progress line appropriate to the product; translate achievements into original milestone stamps.

**Build:** Use an SVG viewBox 0 0 1440 480. Draw an open cubic path with no fill, 26px orange stroke, rounded caps and joins, entering from the lower-left edge and reappearing at the lower-right before a high zigzag. Keep the central text area clear. Build stamps with a scalloped radial polygon, orange fill, inset white outline at partial opacity and a large short milestone label.

### Company portrait grid

**Only for:** company team sections

**Use:** Humanize leadership or contributors.

**Observed:** Square 308px portraits with pale warm-grey studio backgrounds, natural clothing and soft side shadows. Names and roles are left aligned below; three columns wrap into a centered final row.

**Transfer:** Use consistent light and framing, not an assortment of circular avatars.

### Geographic footprint graphic

**Only for:** company footprint stories

**Use:** A broad visual pause before a short location narrative.

**Observed:** A flat dark burgundy world silhouette stretches nearly the whole page on white. A pale horizontal strip crosses behind the continents, and a small number of bright orange dots identify locations.

**Transfer:** Show the relevant distribution honestly; for a non-geographic footprint use a comparably broad network silhouette with a few orange nodes.

**Build:** Place a simplified SVG geographic silhouette in deep ember over a white 1440px by 600px field. Add a pale neutral rectangular band across the middle behind the silhouette, then orange circles about 16px across at the relevant locations. Omit labels from the artwork and explain it in adjacent prose.

### Icons

**Observed:** Marketing comparison checks are filled 32px circles with white checkmarks, orange for the promoted tier and black for other tiers. Other small SVG icons sit at 24px or 32px; navigation chevrons are simple and monochrome. Onboarding uses spare orange pictograms with ample surrounding space.

**Transfer:** Use filled circular checks for availability and simple orange pictograms for steps. Do not turn every benefit into an outlined icon card.

## Section recipes

How recurring sections are built.

### First screen: Ember membership opening

**Observed:** The full-width Ember stage occupies 798px of the first screen. Opening navigation link groups float across its top in white with the brand at left and account controls at right. A compact product descriptor and orange emblem sit above an 811px centered headline measure. The display is 72px/72px, two lines, followed by hero-support and one Primary button, separated by 24px. The large dark seal sits behind the right side and is clipped by the stage. Back-to-front: red-black atmosphere, seal, small emblem, white headline/support, orange action, navigation. All of these fit within the first 900px, including the 78px Chapter tabs below the hero; the next white section only begins at the bottom and its heading is below the fold.

**Transfer:** Keep the same centered ceremonial hierarchy for a new product: original small emblem, broad two-line promise, one support sentence, one action and a giant faint echo of the emblem. No source media is needed: the Ember stage and SVG seal provide the main object. For a shared-plan offer, switch to a 650px human-photo hero with left-aligned extended text; for direct acquisition, use a 634px photo hero under a 74px dark header and regular-sans acquisition-display. A registration page instead uses a compact white center column between two photographic panels.

**Avoid:** Do not replace this with a generic left-copy/right-dashboard SaaS split, an empty black rectangle or several equally prominent buttons. Do not make the giant seal the readable headline.

**Text style:** `display` — BoathouseExtended 600 · 72px/1

### White declaration pause

**Observed:** A centered 811px heading measure on White canvas, with 128px top and bottom padding. The 60px/72px heading can wrap to two lines without support or actions.

**Transfer:** Use a short assertion that bridges the opening promise to detailed capabilities.

**Text style:** `heading-lg` — BoathouseExtended 600 · 60px/1.2

### Photo chapter and benefit trio

**Observed:** A full-bleed photographic banner uses white heading-lg and hero-support on a left-aligned measure, followed by a white 128px-padded benefit group. Three Benefit items fill the marketing frame; a single centered Primary button sits 24px below the group. Chapter tabs track the active topic.

**Transfer:** Pair an emotional result with concrete product proof. Vary the number of chapters to suit the product; retain the contrast between immersive banner and disciplined unboxed explanation.

**Text style:** `heading-lg` — BoathouseExtended 600 · 60px/1.2

### Availability comparison

**Observed:** A heading introduces an unboxed comparison table. The default two-tier version is 616px wide on White canvas; a three-tier membership version expands to 1216px on Pale information band. Row rhythm is 64px, labels use body and uppercase column labels sit above aligned circular checks. The promoted tier's checks are orange, the others black.

**Transfer:** Choose capabilities that explain a real upgrade. Leave unavailable cells empty instead of adding visual clutter.

**Text style:** `heading` — BoathouseExtended 600 · 48px/56px

### Belonging finale

**Observed:** A 758px full-width photographic band carries a centered heading-lg in white: a quantified result statement followed by a separated invitation. Warm orange shading unifies the image. It resolves directly into Directory charcoal with no intervening card. Footer columns group identity/legal, menu, social and account/download actions; category labels use footer-heading and links footer-link.

**Transfer:** End on a truthful achievement or shared ambition in monumental type. If no trustworthy metric exists, use a strong non-numeric invitation. Preserve this emotional close even when earlier content is shorter.

**Text style:** `heading-lg` — BoathouseExtended 600 · 60px/1.2

### Split object story

**Only for:** membership and company narratives

**Observed:** 72px vertical padding around a centered marketing frame. A tall Phone stories object sits beside a wider text column: split-heading, editorial-body after 24px and an orange text action. Consecutive stories reverse the media side.

**Transfer:** Give each split one objection, benefit or setup concept. Preserve the isolated object and generous open white space.

**Text style:** `split-heading` — BoathouseExtended 600 · 48px/1.25

### Plan choice

**Only for:** pricing comparisons

**Observed:** An extended 48px/60px introduction precedes three Plan panels with 32px gutters. A white recommendation pill floats above the preferred tier's title. A single orange action sits below the grid rather than one button competing inside every panel.

**Transfer:** Use comparable price units and short inclusion lists. Distinguish the recommended choice with the badge, keeping panels equal in color.

**Text style:** `split-heading` — BoathouseExtended 600 · 48px/1.25

### Three-step start

**Only for:** membership onboarding explanations

**Observed:** Centered split-heading, then 72px of separation before three equal columns. Each starts with a small orange pictogram, followed by benefit-title and body after 16px. One centered Primary button closes the group.

**Transfer:** Reduce adoption to concrete actions; align the steps in an open row without card shells.

**Text style:** `split-heading` — BoathouseExtended 600 · 48px/1.25

### Community and editorial proof

**Only for:** activity-specific acquisition pages

**Observed:** A black full-width band holds a centered acquisition-heading and two rows of six Community tiles. Later, a pale band displays four landscape article thumbnails with direct, left-aligned titles and a small orange more-stories link.

**Transfer:** Combine belonging proof with useful education, using authentic people, groups or practitioners rather than abstract praise.

**Text style:** `acquisition-heading` — Boathouse 600 · 48px/1.1

### Questions and last action

**Only for:** membership offer pages

**Observed:** Pale information band, heading-lg, then stacked Question rows with soft dividers. The first answer is open. A separate white action pause follows, containing one centered Primary button with 184px above and 128px below before the dark footer.

**Transfer:** Answer cost, eligibility, migration and cancellation in plain language; let the isolated final action feel easy rather than urgent.

**Text style:** `heading-lg` — BoathouseExtended 600 · 60px/1.2

### Company narrative ending

**Only for:** company pages

**Observed:** A broad geographic footprint graphic gives way to a short split-heading and editorial-body location statement on white. A 540px orange product-promotion band follows with white extended heading, large support, a white-filled action and device media toward the right; Directory charcoal ends the page.

**Transfer:** Connect organizational reach back to what the product enables. Keep the company-specific geographic device out of an ordinary feature page.

**Text style:** `split-heading` — BoathouseExtended 600 · 48px/1.25

## Page flow

**Storyline:** Shared promise → clear product outcomes → tangible capability proof → reasons to join or upgrade → emotional invitation → utilitarian directory.

### Fast account acquisition

1. **Promise and conversion** — A white signup column between two large human-photo panels, with small product/device imagery overlapping the right scene.
2. **Directory** — Immediate warm off-white compact footer with store badges, social marks and link columns.

**Transfer:** Use when conversion is the whole task; do not stretch it into the default long-form marketing experience.

### Explain a shared membership offer and remove adoption friction

1. **Offer** — Full-bleed people photograph with a left-aligned extended headline and orange action.
2. **Value comparison** — Three black pricing panels followed by a wide availability table.
3. **Capability and suitability** — Alternating isolated-phone stories with benefit copy.
4. **Adoption** — Three open pictogram steps, then a subscriber-migration explanation.
5. **Objection handling** — Large question accordion on a pale band.
6. **Final conversion and directory** — Isolated centered action on white, then tall charcoal footer.

**Transfer:** Balance economic value with ease of switching, using the membership-specific panel and question variants.

### Acquire people around one specific use case

1. **Promise** — Regular-sans photo hero with activity-path artwork and a wide orange action; a repeating wordmark strip separates it from the next section.
2. **Product demonstration** — Three illustrated outcomes, then achievement stamps framed by a thick orange ribbon.
3. **Community proof** — Black band with group logos and people tiles.
4. **Compatibility and education** — Monochrome device-mark strip followed by a four-story editorial row.
5. **Conversion** — Black split photo-and-copy callout.
6. **Objection handling and directory** — Compact FAQ system then cream footer.

**Transfer:** Use a use-case-specific photographic story and concrete examples; keep this denser regular-sans system distinct from flagship marketing.

### Make an upgrade feel comprehensive and personally useful

1. **Promise** — Centered emblem, extended headline and single action over the ember stage, followed by sticky chapter tabs.
2. **Positioning** — A generous white declaration pause.
3. **Capability chapters** — Human-photo introductions alternate with three-up product benefit artwork and chapter-specific actions.
4. **Upgrade rationale** — Narrow, unboxed availability comparison.
5. **Emotional close** — Warmly shaded full-bleed people scene with a monumental outcome statement and invitation, then charcoal directory.

**Transfer:** This is the default landing-page model: lead with aspiration, explain through outcomes and finish with belonging rather than another generic action box.

### Make the organization feel human, inclusive and credible

1. **Identity** — Centered extended headline on the ember atmosphere, one short supporting line and action.
2. **Belief and scale** — Narrow white narrative paragraphs alternate with a black monumental statement band.
3. **Origin and people** — Founders' photo-and-copy banner, then a consistent square portrait grid.
4. **Reach** — Full-width geographic illustration followed by a short location narrative.
5. **Product invitation and directory** — Orange product-promotion band with a white action, then charcoal footer.

**Transfer:** Tell a company's belief through people and behavior; include origin or geography only when relevant to the new story.

## Writing

Encouraging, conversational and confidently inclusive. Ambition is framed as something people pursue together, while practical explanations are direct and specific.

**Do not copy:** Do not reuse Strava's name, logos, proprietary badge or route artwork, branded feature names, people, prices, statistics, subscription claims or quoted factual assertions. Source copy examples illustrate cadence only; supply new, verified facts and original language.

- **Addressing the reader:** Speak directly to you and your goals. Use we for a shared belief and the product name for clear functional explanations; collective language invites rather than excludes beginners.
- **Rhythm:** Short mixed-case headlines, often two clipped sentences or a trio of parallel verbs. One or two fuller sentences explain the benefit. Actions are brief, with energetic verbs and little punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Product promise followed by personal relevance, or a short chain of participatory verbs. | 4–10 words | “The best of [Brand]. Built for your goals.”<br>“Record. Sweat. Share. Kudos.” |
| Supporting line | An invitation plus two or three concrete outcomes. | 10–22 words | “Say hello to smarter training, constant improvement and endless exploring.” |
| Benefit title | Verb-led improvement the reader can picture. | 3–6 words | “Compare your progress”<br>“Explore with confidence” |
| Primary action | Start plus the activity, or a direct low-friction invitation. | 2–5 words | “Get Started”<br>“Start exploring” |
| Reassurance | Name the concern in a short question, then answer it immediately. | 2 short sentences before detail | “Not related? No problem.” |
| Closing invitation | Pair a concrete outcome with a simple welcome. | One statement and one short invitation | “Every 19 seconds, a Subscriber hits their goal. Welcome to the club.” |

**Words and phrasing to use:** your goals; together; progress; explore; get started; crew; confidence; say hello to; more; best

**Avoid:** revolutionary ecosystem; unlock unprecedented synergy; elite-only language; fear-based urgency; technical jargon without an outcome

**Rules:**

- Lead with what a person can do, then explain the enabling feature.
- Use parallel, everyday verbs to make breadth feel simple.
- Normalize different starting points; write invitations that include new users.
- Use numerical proof only when it is verifiable, and translate it into a human result.
- Keep pricing and migration requirements explicit instead of hiding them behind aspirational language.

## Do's and Don'ts

### Do

- Keep default hero type at 72px/72px and the broad mixed-case silhouette.
- Let chapter headlines use the same extended family at 60px/72px.
- Give major white explanation groups 128px of vertical breathing room.
- Stage three 384px-wide benefit artworks with 32px visible gutters.
- Use orange #fc5200 for the one primary action and small signals of progress.
- Keep default actions rectangular with 4px corners and 64px height.
- Give the final outcome statement enough room to read as a scene, then resolve into charcoal.
- Use simple 32px filled-circle checks to make upgrade differences scannable.

### Don't

- Do not tighten large display type with aggressive negative tracking; its breadth is part of the character.
- Do not introduce a serif or mono headline voice into the marketing hierarchy.
- Do not fill every explanation section with orange; keep the core reading canvas white.
- Do not turn the 4px action shape into a fully rounded pill; reserve pills for pricing recommendation badges.
- Do not put another bordered, shadowed card behind each benefit's title and paragraph.
- Do not shrink the default 22px body copy to 14px merely to fit more claims.
- Do not make all media circular: circles belong to community profiles, while product art and company portraits retain rectangular framing.
- Do not mix the cream compact footer into the default long-form charcoal directory system without changing the page purpose.

## Motion and responsive

### Motion

**Observed:**

- Chapter navigation is sticky and the light 64px navigation is fixed. The opening navigation is visually richer than the scrolled state.
- Repeated brand and compatibility strips appear as horizontal rows; no action-transition timing is established.

**Transfer:**

- Keep the persistent chapter row subordinate to the top account bar and synchronize its orange selected underline with the chapter being read.
- Retain legible repeated marks if a horizontal strip is animated; its role is continuity, not a new headline.

**Unknown:**

- Hover, focus-visible and active declarations for actions were not established.
- Animation duration, easing and exact navigation-transform timing are unspecified.

### Responsive

**Observed:**

- The desktop composition uses full-width media and centered text/media frames.

**Transfer:**

- On narrower screens, preserve the opening emblem → headline → support → action hierarchy and keep the large seal clipped to an edge rather than reducing it to a second logo.
- Stack the benefit items and split stories while preserving media-before-copy order within each item; keep comparison labels associated with their check columns.
- Keep chapter labels short enough to remain a distinct navigation row below the account header.

**Unknown:**

- Exact mobile breakpoints, type sizes, navigation menus and stacking rules are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
