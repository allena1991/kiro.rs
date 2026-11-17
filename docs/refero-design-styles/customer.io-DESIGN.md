# Customer.io — forest ink, electric edges

## Overview

An open, human-facing software style with oversized grotesk typography, forest-green ink and small electric-green signals. White editorial space gives way to deep teal infrastructure panels, tinted customer stories and contextual interface imagery. It suits complex products that need to feel approachable without losing technical substance; the overall density is spacious, with compact navigation and information-rich comparison areas.

### Essentials

- Headlines feel spoken rather than shouted: Saans at weight 475, 96px/1 with 0.2px tracking for the main promise, and 40px/1.125 for ordinary section leads.
- The opening gives the promise its own air: left-aligned two-line type, a roughly 501px support line, paired 48px actions, and a wide contextual product scene beginning beneath the text rather than competing beside it.
- Conversion controls look electrically edged, not elevated: forest-filled and white-outline pills, 2px borders, 4px outer rings and 12px between paired actions.
- White is the dominant canvas; deep teal forms substantial contrast chapters and the footer. Saturation is concentrated in mint action rings, individual words, contained artwork and peach or blue proof panels, not spread across every section.
- Human context is a signature device: include a wide interface staged over warm daylight photography and a strip of tall, heavily teal-veiled photographic panels. For a product without interface media, stage a clear working artifact over a real setting and use documentary process photographs in the strip.
- Proof has its own graphic grammar: rectangular tinted quote panels, angular portrait backings and restrained 20px semibold statistics divided by 1px vertical rules. Preserve this device with genuine outcomes or attributed qualitative proof.
- Small markers tie the spacious page together: 16px sentence-case eyebrows with a mustard geometric tab, fine 1px grid rules, and a monumental 64px closing line framed by vertical edges and a subtle 15px dot field.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest ink | `#00262b` | `--color-ink` | text, action | Default headline and strong text color; hover fill on light action buttons. |
| Deep teal | `#00191c` | `--color-night` | background | Infrastructure chapters and shared footer. |
| Spruce action | `#0b363b` | `--color-action` | action, border, surface | Primary button fill and dark-theme panel edges. |
| Teal panel | `#032125` | `--color-panel` | surface | Dark panel fill and the source hue for translucent text and photographic veils. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal mint | `#abffae` | `--color-mint` | accent, action, border | Small signal marks and inverse call-to-action fills and borders; match the brighter outer glow of light-theme buttons without extending it into a page wash. |
| Peach proof | `#fdf0e9` | `--color-peach` | surface | Warm customer quotation panel. |
| Rust proof ink | `#863d1c` | `--color-peach-ink` | text, border | Text and statistic rules on peach proof panels. |
| Blue proof | `#e2f4ff` | `--color-ice` | surface | Cool customer quotation panel. |
| Blue proof ink | `#123a88` | `--color-ice-ink` | text, border | Text and statistic rules on blue proof panels. |
| Mustard marker | `#bb8908` | `--color-mustard` | accent | Small geometric section markers. |
| Violet emphasis | `#6e3ebe` | `--color-violet` | text, accent | Individual words in the large explanatory statement. |
| Orange emphasis | `#eb7133` | `--color-orange` | text, accent | Individual words and angular illustrative accents. |
| Blue emphasis | `#0a6de6` | `--color-blue` | text, accent | Individual words and contained technical illustrations. |
| Pink emphasis | `#b52473` | `--color-pink` | text, accent | Individual highlighted words. |
| Gold emphasis | `#e1a70e` | `--color-gold` | text, accent | Individual highlighted words. |
| Green emphasis | `#41a251` | `--color-green` | text, accent | Individual highlighted words. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Dominant page canvas and inverse text. |
| Near-white wash | `#fafafa` | `--color-wash` | surface, background | Product backings, listing areas and newsletter bands. |
| Light rule | `#ebebeb` | `--color-rule` | border | Shared hairlines and grid seams. |
| Inverse body | `#cde3e5` | `--color-inverse-body` | text | Paragraphs in teal panels. |
| Inverse muted | `#a1c2c6` | `--color-inverse-muted` | text | Footer links and small inverse labels. |
| Muted text | `#4f6466` | `--color-muted` | text | Visible result of forest-panel hue at 70% alpha over white; secondary accordion labels. |
| Subtle text | `#354d51` | `--color-subtle` | text | Visible result of forest-panel hue at 80% alpha over white; paragraph text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| subscription forms | Input edge | `#d9d9d9` | `--color-input-edge` | border | Newsletter field outline. |
| customer-story collections | Charcoal canvas | `#141414` | `--color-charcoal` | background | Alternate dark hero, resources and testimonial carousel. |
| customer-story collections | Warm inverse | `#fbfaf9` | `--color-warm-white` | text, surface | Text on charcoal and warm industry tiles. |
| customer-story collections | Charcoal rule | `#313131` | `--color-charcoal-rule` | border | Outlined quote-carousel cards. |
| customer-story collections | Bright green story | `#c6fdc4` | `--color-proof-green` | surface | Full-width illustrated result card. |
| customer-story collections | Lavender story | `#e6e7ff` | `--color-proof-lavender` | surface | Full-width illustrated result card. |
| customer-story collections | Aqua story | `#c7ffff` | `--color-proof-aqua` | surface | Full-width illustrated result card. |

## Typography

- **saansFont** — All marketing headings, paragraphs, navigation and controls. An open contemporary grotesk with broad round forms, a substantial x-height and friendly but unforced shapes. If unavailable, use **Inter**. Use variable weight 475 for ordinary text and headings; retain the slightly positive tracking. Font stack: "saansFont", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | saansFont | 475 | 96px | 1 | 0.0021em | Main landing-page promise, typically two lines. |
| closing | saansFont | 475 | 64px | 1 | 0.0031em | Centered closing statement; also the culture-page opening. |
| heading | saansFont | 475 | 40px | 1.125 | 0.005em | Default section headings and large explanatory statement. |
| heading-small | saansFont | 475 | 30px | 1.125 | 0.0067em | Panel leads and featured editorial titles. |
| card-heading | saansFont | 475 | 24px | 1.125 | 0.0083em | Solution-tile titles. |
| quote | saansFont | 500 | 24px | 1.25 | 0.0083em | Customer quotations in tinted panels. |
| lead | saansFont | 475 | 20px | 1.375 | 0.01em | Opening support paragraph and FAQ questions. |
| photo-title | saansFont | 600 | 20px | 1.125 | 0.01em | Bottom-aligned titles on photographic capability panels. |
| stat | saansFont | 600 | 20px | 1.375 | 0.01em | Small outcome numerals in quotation panels. |
| eyebrow | saansFont | 475 | 16px | 1 | 0.0125em | Sentence-case section identification. |
| body | saansFont | 475 | 16px | 1.375 | 0.0125em | Main paragraph and feature text. |
| action | saansFont | 600 | 16px | 1.375 | 0.0125em | Main conversion buttons, text links and compact feature titles. |
| small | saansFont | 475 | 14px | 1.375 | 0.014em | Footer links and compact metadata. |
| stat-caption | saansFont | 475 | 14px | 1.125 | 0.014em | Compact two-line explanation beneath each result. |
| reassurance | saansFont | 475 | 12px | 1.375 | 0.017em | Short checked assurances underneath conversion actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| customer-story collections | story-display | saansFont | 475 | 64px | 1 | -0.0016em | Centered warm-white headline on charcoal. |
| pricing pages | pricing-display | saansFont | 475 | 64px | 1.125 | -0.0016em | Centered two-line pricing opening. |
| pricing pages | price | saansFont | 700 | 60px | 1.125 | -0.025em | Entry-plan price; long prices and enterprise invitation use 48px/1.125, weight 700 and -0.025em. |
| resource hubs and customer-story collections | editorial-display | saansFont | 475 | 48px | 1.125 | -0.002em | Editorial opening and large collection section leads. |

**Notes:**

- Large type is not generally bold: 475 carries almost all headings. Reserve 600 for controls and compact emphasis, 700 for pricing numerals.
- Keep 0.2px tracking through the core hierarchy rather than imposing fashionable tight negative tracking. Editorial collection leads use the separately scoped -0.1px variants.
- Body copy is substantially smaller than section leads; support paragraphs remain narrow instead of filling the container. No viewport-relative type formula is prescribed.

## Layout

**Density:** Airy at chapter level, compact within controls and proof details; generous blank space separates narrative ideas without making every card oversized.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Feature title-to-copy and check-to-assurance gaps. |
| 8px | Tile title-to-copy gaps and internal control spacing. |
| 12px | Paired conversion actions. |
| 16px | Editorial grids, panel title-to-paragraph spacing and action-to-assurance spacing. |
| 24px | Feature vertical padding and photo-panel insets. |
| 32px | Default grid gap, section eyebrow-to-heading gap and panel padding. |
| 64px | Split media/text gap and footer vertical padding. |
| 80px | Opening top padding. |
| 96px | Section heading-to-main-content separation and opening bottom padding. |
| 112px | Resource collection section vertical padding. |
| 128px | Major narrative chapter vertical padding. |
| 160px | Closing call vertical padding. |

### Containers and grids

- **Main container**: max width 1320px · side padding 32px. Centered outer container; yields 1256px usable width and 92px text margins at 1440px.
- **Header container**: max width 1680px · side padding 32px. Wider than the body, with logo at left, navigation centered and conversion controls at right.
- **Heading grid**: 12 columns · gap 32px. Section heading occupies eight columns; secondary link rests at the lower right.
- **Feature trio**: 3 columns · gap 32px. Narrow left-rule features, approximately 397px each.
- **Split demonstration**: 2 columns · gap 64px. Balanced media and prose, each approximately 596px wide.
- **Solution grid**: 2 columns · gap 1px. Rectangular tiles share hairline seams inside one outer rule.
- **Editorial grid** (only for resource hubs): 3 columns · gap 16px. Approximately 408px cards; a featured row can span two columns alongside one tall dark card.
- **Plan grid** (only for pricing pages): 3 columns · gap 24px. Equal-width plan cards, approximately 397px wide, aligned at top and bottom.

## Corner radius

| Element | Radius |
| --- | --- |
| Conversion buttons | 9999px (pill) |
| Editorial cards and fields | 2px |
| Plan and story cards | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Primary signal ring | `0px 0px 0px 4px oklch(0.9263 0.136 145.2)` | Electric mint edge around the main filled action. |
| Secondary neutral ring | `0px 0px 0px 4px oklch(0.97 0 0)` | Pale outer edge around the outlined action. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing surface.

**CSS:** `background: #ffffff; color: #00262b`

**Observed:** Most chapters remain white and divide with restrained horizontal rules.

**Transfer:** Let large type and contained imagery provide the visual weight.

#### Subtle band · level 0

**Use:** Listing, product and subscription backing.

**CSS:** `background: #fafafa; border-top: 1px solid #ebebeb`

#### Dark chapter · level 0

**Use:** Technical confidence and footer.

**CSS:** `background: #00191c; color: #ffffff`

**Observed:** A full-width dark teal field, not a floating rounded rectangle.

**Transfer:** Use for a substantive contrasting chapter, not alternate dark and light at every block.

#### Dark panel · level 1

**Use:** Contained technical illustrations and supporting copy.

**CSS:** `background: #032125; border: 1px solid #0b363b; padding: 32px`

**Observed:** Panels share 1px seams and remain square-cornered.

**Transfer:** Use one wide panel above a balanced split, with restrained colored symbols inside.

#### Warm proof · level 1

**Use:** Attributed quote panel.

**CSS:** `background: #fdf0e9; color: #863d1c; padding: 32px`

**Observed:** Cool variant uses blue proof fill with blue proof ink; portrait and prose switch sides between rows.

**Transfer:** Keep color local to the customer story.

#### Dot field · level 0

**Use:** Closing-call texture behind the central statement.

**CSS:** `background-image: radial-gradient(circle, rgba(3,33,37,0.7) 1px, rgba(0,0,0,0) 1px); background-size: 15px 15px; opacity: 0.3`

**Observed:** An inset background layer behind text, bounded by vertical hairlines.

**Transfer:** Keep the dots visually secondary.

#### Charcoal collection · level 0

**Only for:** customer-story collections

**Use:** Alternate proof-led opening and resource chapters.

**CSS:** `background: #141414; color: #fbfaf9`

**Observed:** True charcoal replaces teal only within this collection theme.

#### Bright result card · level 1

**Only for:** customer-story collections

**Use:** Large illustrated case-study result.

**CSS:** `background: #c6fdc4; border-radius: 4px`

**Observed:** Lavender and aqua variants follow; each is 1256px wide and 580px tall with a two-column composition.

**Transfer:** Pair a concise result with one custom schematic.

#### Plan wash · level 1

**Only for:** pricing pages

**Use:** Inset header area of each plan.

**CSS:** `background-color: #ffffff; background-image: linear-gradient(oklch(0.955 0.06 143.4) 0px, rgba(0,0,0,0) 100%); border-radius: 4px; padding: 24px 24px 8px`

**Observed:** All three plans receive the same green-to-white wash rather than highlighting one with an unrelated color.

**Transfer:** Keep tier differentiation in words, price and included features.

## Components

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: sticky; top: 0px; height: 64px; background: #ffffff; border-bottom: 1px solid #ebebeb; z-index: 40`

**Text style:** `action` — saansFont 600 · 16px/1.375 · tracking 0.0125em

**Observed:** Logo left, a compact centered group with small down chevrons, then sign-in and two 40px conversion pills at right. Navigation labels use 16px/22px, weight 600, normal tracking.

**Transfer:** Use a similarly short information architecture rather than filling the available width.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #0b363b; color: #ffffff; border: 2px solid #0b363b; border-radius: 9999px; padding: 8px 28px; height: 48px; box-shadow: 0px 0px 0px 4px oklch(0.9263 0.136 145.2)`

**Text style:** `action` — saansFont 600 · 16px/1.375 · tracking 0.0125em

**Observed:** The bright perimeter is a ring, not a downward shadow. Header version is 40px tall with 20px horizontal padding and 14px semibold text. Inverse closing variant uses mint fill and forest text.

**States:** Declared: hover background and border become #00262b; focus-visible removes box-shadow and sets outline-style none.

**Transfer:** Retain the electric edge on principal actions; provide a discernible keyboard focus treatment when implementing.

### Secondary button

**Use:** Sales-assisted alternative beside the primary action.

**CSS:** `background: #ffffff; color: #00262b; border: 2px solid #0b363b; border-radius: 9999px; padding: 8px 28px; height: 48px; box-shadow: 0px 0px 0px 4px oklch(0.97 0 0)`

**Text style:** `action` — saansFont 600 · 16px/1.375 · tracking 0.0125em

**Observed:** Paired with the filled pill, not presented as a plain text link. Dark closing variant uses mint border and text on forest fill.

**States:** Declared: hover background and border become #00262b and text becomes #ffffff; focus-visible removes box-shadow and sets outline-style none.

### Left-rule feature

**Use:** Compact supporting benefit.

**CSS:** `border-left: 1px solid #ebebeb; padding: 24px 0px 24px 32px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `body` — saansFont 475 · 16px/1.375 · tracking 0.0125em

**Observed:** Small outline icon precedes a semibold title; the title and paragraph sit 4px apart. Three features form one open row, without filled card shells.

### Photographic capability panel

**Use:** Interactive capability overview.

**CSS:** `height: 500px; padding: 24px; border-right: 1px solid #0b363b; display: flex; flex-direction: column; justify-content: space-between; position: relative; overflow: hidden`

**Text style:** `photo-title` — saansFont 600 · 20px/1.125 · tracking 0.01em

**Observed:** Full-bleed human photograph sits beneath a #032125 veil at 0.88 opacity and a dark lower gradient. A circular plus occupies the upper left and a white title anchors the lower left. Five narrow panels form a horizontally overflowing strip.

**States:** Declared: group hover and active reduce the veil opacity to 0; flex-grow transitions over 0.4s cubic-bezier(0,0,.2,1).

**Transfer:** Use your own process or customer-context photography; preserve the dark resting view and readable labels.

### Tinted quote panel

**Use:** Human, attributed social proof.

**CSS:** `background: #fdf0e9; color: #863d1c; padding: 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 64px`

**Text style:** `quote` — saansFont 500 · 24px/1.25 · tracking 0.0083em

**Observed:** A partner badge and small stat group occupy the top. A prominent quotation mark introduces the quote; attribution and a case-study link finish the bottom. A separate portrait cell takes about 30% of the row. Blue variant reverses the portrait side.

**Transfer:** Use an actual attributed statement and a matching warm or cool monochrome text treatment.

### Ruled statistic

**Use:** Outcome annotation within proof.

**CSS:** `border-left: 1px solid #863d1c; padding-left: 16px; display: flex; flex-direction: column`

**Text style:** `stat` — saansFont 600 · 20px/1.375 · tracking 0.01em

**Observed:** The numeral is only 20px, with a 14px tight two-line caption beneath it. Paired statistics are separated by 32px; the blue variant changes both ink and rule together.

**Transfer:** Keep the metric subordinate to the quotation, not a giant isolated dashboard number.

### Footer

**Use:** Shared navigation ending.

**CSS:** `background: #00191c; padding: 64px 0px; display: flex; flex-direction: column; gap: 96px`

**Text style:** `small` — saansFont 475 · 14px/1.375 · tracking 0.014em

**Observed:** A white logo takes the left area; four columns of muted links fill the right. Small outlined mint novelty tags appear inline. Social squares precede a long bottom rule, then legal text left and a glowing green status dot with status text right.

**Transfer:** Preserve the spacious top-to-bottom hierarchy even with fewer links.

### Arrow text link

**Use:** Secondary exploration at section edges and within stories.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; padding: 2px 0px; color: #00262b`

**Text style:** `action` — saansFont 600 · 16px/1.375 · tracking 0.0125em

**Observed:** A small thin right arrow appears before the label in core section links. Story links can follow the label and inherit their panel's ink.

**Transfer:** Use one restrained link per section heading rather than another pill.

### Editorial card

**Only for:** resource hubs

**Use:** Article or guide preview.

**CSS:** `border: 1px solid #ebebeb; border-radius: 2px; display: flex; flex-direction: column`

**Text style:** `card-heading` — saansFont 475 · 24px/1.125 · tracking 0.0083em

**Observed:** A colorful 16:10 cover leads into category, title and bottom-aligned author avatar with name and role. Standard titles use 20px/22.5px at weight 475; featured titles use heading-small. Tall dark guide cards span two rows and use inverse text.

**Transfer:** Vary card proportions deliberately while keeping shared edges and aligned author rows.

### Newsletter field

**Only for:** subscription forms

**Use:** Email entry in a broad near-white band.

**CSS:** `height: 48px; background: #fafafa; border-top: 1.5px solid #d9d9d9; border-bottom: 1.5px solid #d9d9d9; border-left: 1.5px solid #d9d9d9; border-right: 0px; border-radius: 2px 0px 0px 2px; padding: 8px 16px`

**Observed:** A 375px field joins directly to a 133px dark submit button, with only the two outside corners rounded. The complete form sits opposite a short heading.

**Transfer:** Use a visible or programmatic field label and retain the joined construction.

### Plan header

**Only for:** pricing pages

**Use:** Top decision area within a bordered plan card.

**CSS:** `background-color: #ffffff; background-image: linear-gradient(oklch(0.955 0.06 143.4) 0px, rgba(0,0,0,0) 100%); border-radius: 4px; padding: 24px 24px 8px; margin: 16px; display: flex; flex-direction: column; align-items: center; gap: 20px; text-align: center`

**Text style:** `price` — saansFont 700 · 60px/1.125 · tracking -0.025em

**Observed:** Tier name, small starting-price label, price, billing qualifier, audience description and full-width dark pill align across three equal cards. Included-feature lists sit below a horizontal rule.

**Transfer:** Make tier choice legible without a loud recommended-plan banner.

## Imagery and graphics

### Contextual product stage

**Use:** Large visual anchor immediately after the opening promise.

**Observed:** A bright office with large windows, pale warm walls and plants fills a 1256×707px rectangle. A crisp, front-facing white software interface, 1096×617px, is inset over it; the upper edge is visible before the first fold, while the full interface extends below.

**Transfer:** Use a real environment relevant to the product, warm daylight and an oversized legible interface or working artifact. Keep it frontal and grounded, not a tilted floating browser.

### Teal human strip

**Use:** Signature capability imagery.

**Observed:** Narrow vertical photographs show people using phones and computers or collaborating. The heavy teal veil unifies varied photography into a single continuous dark strip; white titles and small plus controls remain the brightest elements.

**Transfer:** Choose documentary images with people engaged in distinct activities. If the product is abstract, show the work around it rather than unrelated smiling portraits.

**Build:** Place object-fit:cover photographs in equal flex panels, height 500px. Layer an absolute #032125 overlay at opacity 0.88 and a bottom dark gradient. Keep text above both; use a 40px dark circular plus control at top left and 24px panel padding.

### Angular portrait proof

**Use:** Signature human proof artwork.

**Observed:** A cutout portrait sits inside an elongated diagonal polygon on a white cell; warm orange or saturated blue backing matches the adjacent quote theme. The head remains natural and recognizable rather than heavily duotoned.

**Transfer:** Use a consented customer portrait and a single contrasting polygon; if portraits are unavailable, use a photographed product artifact inside the same angular backing.

**Build:** Create an SVG six-point slanted block with clipped opposite corners, roughly 312×317px. Clip a portrait cutout inside the block, anchoring the face toward its center; place it on a white cell with about 32px breathing room.

### Technical symbol scenes

**Use:** Dark infrastructure panels and explanatory tiles.

**Observed:** Sparse geometric blocks, thin connecting arrows, small integration-logo squares and mint line illustrations sit on deep teal or white. The dark chapter's wide panel puts text on one side and a loose array of small partner tiles on the other.

**Transfer:** Reduce the new product's mechanism to a few symbols and connections. A minimal SVG of two angular blocks and a curved connector is preferable to generic glossy 3D.

**Build:** Use flat SVG polygons with clipped corners, blue and pale warm faces, a thin curved path and small arrowhead. On dark panels use mint squares as label markers and subdued teal tile backings; leave substantial empty space around the symbols.

### Editorial geometry

**Only for:** resource hubs

**Use:** Distinctive article-cover artwork.

**Observed:** Color-blocked navy, violet, mint and blue covers mix slanted short bars, angular blocks, looping thin arrows, document mockups and occasional photography. Covers remain clean rectangular media, without ornamental frames.

**Transfer:** Assign one geometric metaphor to each article rather than repeating a generic gradient.

**Build:** In a 16:10 SVG, distribute clipped rectangular bars in a loose swirl, or connect two flat polygonal blocks with a looping path. Use two dominant colors and one small accent; keep fine grain subtle and text outside the artwork.

### Illustrated result scenes

**Only for:** customer-story collections

**Use:** Half-width schematic inside bright result cards.

**Observed:** A central framed mini-interface is surrounded by floating logo tiles, labels and cursor annotations. Dark teal controls stand against mint, lavender or aqua backing; soft localized glow gives the schematic depth.

**Transfer:** Show one concrete mechanism behind the result. A central two-control mockup with three relevant orbiting labels is a sufficient replacement.

**Build:** Use an outlined central rectangle, two stacked dark controls and several small pale tiles positioned around it. Add low-opacity blurred teal ellipses behind the controls; preserve a wide clear text half.

### Culture documentary and data art

**Only for:** culture and hiring pages

**Use:** Human-scale employer storytelling.

**Observed:** Wide retreat photography, orchard family scenes and working-together images are paired with a dotted world map on vivid blue. A values panel uses an orthogonal grid and one small grainy multicolor sphere, flanked by compact text cells.

**Transfer:** Use candid photography and truthful geography for the organization. Keep these culture devices out of an ordinary product opening.

**Build:** For the map, mask a regular dark dot pattern to a world silhouette and overlay small circular location markers. For a values diagram, use a fine square grid on near-white and a single small circular pink-to-gold gradient with fine noise; flank it with ruled text cells.

### Icons

**Observed:** Small outline SVGs generally use 1.5px strokes at 20px or 24px, with square caps; arrows and chevrons often use 14px with 2px strokes. Labels have tiny mustard geometric tabs; dark labels switch to mint squares. Solution illustrations combine forest outlines, white faces and mint details.

**Transfer:** Use a consistent thin-line icon family. Keep icons secondary to the text and reserve filled marks for section tabs, partner logos and small status dots.

## Section recipes

How recurring sections are built.

### First screen: Promise above contextual stage

**Observed:** A 64px white Navigation sits above a white text-first opening. Main content aligns to the shared 92px left margin at 1440px, beginning after 80px of top space. A two-line display headline spans roughly two thirds of the canvas, with a changing final noun on the second line and generous empty space to its right. The support paragraph follows after 24px, constrained to about 501px; Primary button and Secondary button follow after 36px, with a checked reassurance row underneath. The text section ends at about 632px from the top of the page. Within the first 900px the full promise, support, controls and assurances are visible, followed by the top portion of Contextual product stage; the complete interface continues below. Layer order is white canvas, warm photographic stage, crisp interface, with the text block entirely above the media.

**Transfer:** Make a similarly short outcome promise, leaving room for a concrete noun or small set of nouns. Stage a working artifact over relevant warm photography if there is no interface. Resource hubs instead use a 48px left-aligned editorial lead and category toolbar; pricing uses a centered 64px lead above plans; customer-story collections use a centered 64px warm-white lead on charcoal; hiring uses a 64px left lead with a compact right-side invitation.

**Avoid:** Do not convert this into a centered headline over a giant gradient orb or a conventional half-text, half-floating-dashboard hero. Do not enlarge an animated noun beyond the surrounding headline.

**Text style:** `display` — saansFont 475 · 96px/1 · tracking 0.0021em

### Marked chapter heading

**Observed:** Eyebrow with a mustard tab, 32px gap to heading, then 96px to the main content. Heading grid places the lead across eight columns and Arrow text link at the bottom right. Dark chapters use white type and mint square markers.

**Transfer:** Use short categorical labels and a useful promise, then let the next component demonstrate it.

**Text style:** `heading` — saansFont 475 · 40px/1.125 · tracking 0.005em

### Colored explanatory statement

**Observed:** Centered 40px explanatory paragraph with individual nouns in violet, orange, blue, pink, gold and green. Left-rule feature trio sits beneath with compact body copy.

**Transfer:** Highlight only the concepts that organize the new product's value; preserve the single flowing sentence rather than making separate rainbow cards.

### Capability and demonstration

**Observed:** Marked chapter heading precedes the Teal human strip. A separate Split demonstration pairs one large technical illustration with a headline, short paragraph, link and ruled accordion details.

**Transfer:** Let the photo strip name major capabilities and the split scene explain one deeply; choose content order according to the story.

### Ruled solution tiles

**Observed:** A two-by-two white grid uses 1px shared seams, 40px inner padding, 24px titles and compact paragraphs. Small mint-and-forest line illustrations occupy the upper-right area of each tile.

**Transfer:** Use for distinct jobs or outcomes; keep the whole grid visually lighter than the photographic strip.

### Technical confidence chapter

**Observed:** Dark chapter carries a centered 40px lead above Dark panel. One wide integration panel sits over a lower split of abstract illustration and two text modules. Labels, text and image areas are aligned to shared internal edges.

**Transfer:** Use contained mechanism art to make reliability tangible; keep the deep teal palette distinct from the brighter proof chapters.

### Alternating human proof

**Observed:** Marked chapter heading leads into two rectangular Tinted quote panel rows, each about 383px tall, separated by 32px. Angular portrait proof alternates left and right; Ruled statistic remains small at the top of the text panel.

**Transfer:** Use one warm and one cool story, or preserve one strong row if there is less genuine proof.

### Framed closing and trust seam

**Observed:** White closing panel has a 64px centered line, paired action pills, reassurance row and Dot field behind the content. Vertical edge rules frame the 1256px interior; 160px vertical padding gives it monumentality. A 106px white credential strip with five equal divided cells leads into Footer.

**Transfer:** End a marketing story with a short action-oriented line and the same action pair. Populate any credential strip only with relevant, verified assurances.

**Text style:** `closing` — saansFont 475 · 64px/1 · tracking 0.0031em

### Compact inverse closing

**Only for:** resource hubs and customer-story collections

**Observed:** A 336px dark teal band uses a small geometric emblem at left, 48px white headline in the center area and mint action pair with tiny assurances. Vertical rules split the emblem from the text area. Footer follows directly.

**Transfer:** Use this compact ending when a long collection needs a conversion reminder without another large white chapter.

**Text style:** `editorial-display` — saansFont 475 · 48px/1.125 · tracking -0.002em

### Collection mosaic and subscription

**Only for:** resource hubs

**Observed:** Opening category toolbar and search precede a large featured cover beside stacked compact story rows. Later sections use 16px-gap Editorial card mosaics, including a tall dark guide card. A near-white subscription band pairs a 30px short invitation with the joined Newsletter field. A centered topic cloud uses outlined rectangular tags with small circular count badges before the inverse closing.

**Transfer:** Give one resource a clear lead, vary the grid by importance and keep browsing controls compact.

### Plans, comparison and objections

**Only for:** pricing pages

**Observed:** A centered two-line lead gives way to three Plan headers. A monochrome logo row and a dark program banner bridge into a long comparison table. The table has one label column and three equal plan columns, alternating near-white plan stripes, 68–74px rows and 24px category headings. Mini plan summaries stay beneath the sticky navigation. FAQ ends the comparison: a 30px heading at left and an approximately 837px ruled question column at right, with one answer expanded. Credential strip and Footer finish without an extra conversion chapter.

**Transfer:** Retain persistent column context and calm row contrast for any complex offer; use objections to close the decision.

### Culture and opportunity list

**Only for:** culture and hiring pages

**Observed:** A candid wide photo follows the split opening. Benefits use an accordion beside a large personal photograph; a blue dotted map and portrait pairing introduce operating principles. Colored words, a grid-and-sphere diagram and a panoramic photo strip add character. The opportunities area switches to near-white, 24px department headings and 97px ruled job rows. Dark article rows lead into Footer, with no product conversion band.

**Transfer:** Use lived evidence and concrete employee information before a filterable opportunity list; let the ending remain editorial rather than sales-led.

### Bright story stack and charcoal resources

**Only for:** customer-story collections

**Observed:** An award-led charcoal opening leads to a featured split story, then sticky Bright result cards. Warm-white industry tiles combine centered text above composited mini-interface imagery. The lower collection returns to charcoal for a three-column resource grid and an outlined quote carousel, then a white credential strip, Compact inverse closing and Footer.

**Transfer:** Use the bright cards for a small number of deep outcomes, and the charcoal chapter for secondary evidence rather than repeating the same light grid throughout.

## Page flow

**Storyline:** Outcome promise → tangible product or human context → supporting proof → capability or editorial chapters → confidence and evidence → purpose-specific closing → shared dark navigation ending.

### General product landing page

1. **Promise** — Oversized left headline, support, paired actions and reassurance.
2. **Product demonstration** — Large frontal interface over warm office photography.
3. **Social proof** — Ruled customer-logo band.
4. **Value framework** — Colored-word statement and left-rule feature trio.
5. **Capability chapters** — Teal photographic strip, split demonstration and solution tiles.
6. **Technical confidence** — Deep teal infrastructure panel grid.
7. **Quantified proof** — Alternating warm and cool portrait-quote rows.
8. **Closing call** — Framed dotted white call, credentials, dark footer.

**Transfer:** Preserve the contrast between open promise, human context and dense technical confidence, not a fixed section count.

### Customer proof collection

1. **Trust promise** — Charcoal centered headline and award imagery.
2. **Featured proof** — Split feature followed by bright illustrated sticky result cards.
3. **Audience relevance** — Warm-white industry tiles.
4. **Supporting evidence** — Charcoal resource grid and testimonial carousel.
5. **Closing call** — Credentials, compact inverse conversion band and dark footer.

**Transfer:** Move from strongest result to breadth of relevance, then a concise action.

### Resource discovery hub

1. **Editorial promise** — Left-aligned headline, category toolbar and search.
2. **Featured content** — Large cover beside stacked compact previews.
3. **Discovery and retention** — Resource-type cards and a joined newsletter form.
4. **Topic chapters** — Editorial mosaics with tall dark guide cards.
5. **Closing call** — Topic-count tags, compact inverse conversion band and dark footer.

**Transfer:** Prioritize content hierarchy and useful navigation rather than a product demonstration.

### Offer evaluation page

1. **Pricing promise** — Centered headline above three softly washed plan cards.
2. **Confidence bridge** — Customer logos and a dark program banner.
3. **Detailed evaluation** — Long ruled comparison with persistent mini-plan summaries.
4. **Objection handling** — Two-column FAQ with one expanded answer.
5. **Trust ending** — Credential strip and shared dark footer.

**Transfer:** Make the dense comparison calm and navigable; do not insert an unnecessary sales hero at the end.

### Employer and hiring page

1. **Employer promise** — Split headline and invitation followed by documentary team photo.
2. **Practical value** — Benefits accordion and personal photograph.
3. **Working model** — Dotted geographic artwork, candid work image and compact principles.
4. **Culture proof** — Colored words, grid diagram, quote, photo panorama and inclusion panels.
5. **Opportunity** — Near-white filtered, grouped and ruled role listings.
6. **Editorial ending** — Dark article list followed by shared footer.

**Transfer:** Show concrete lived conditions before opportunities; retain an editorial ending rather than product trial messaging.

## Writing

Confident and practical, with a human warmth that offsets technical complexity. Benefits lead, mechanisms explain them, and proof supplies specificity rather than superlatives.

**Do not copy:** Do not reuse Customer.io names, logos, product names, customer identities, quotations, awards, statistics, prices, program promises, certification claims or trial terms. Replace them with the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your. Use we and our when describing a shared working relationship or company practice; product statements stay direct and active.
- **Rhythm:** Short outcome headlines, usually four to nine words; support is one or two straightforward sentences. Compact labels are sentence case, while longer editorial titles can use a question or explanatory colon.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A concise comparative outcome with a concrete object. | 4–9 words | “More impact from every message”<br>“Straightforward pricing that grows with you” |
| Supporting line | Connect an input or mechanism to a useful business outcome. | 12–25 words | “Turn customer data into personalized experiences that drive better business outcomes.” |
| Section lead | A plain benefit or useful promise, not a category alone. | 5–12 words | “Everything you need to engage customers”<br>“Distributed by design, not by default” |
| Feature explanation | Concrete verb, mechanism, outcome; a second short sentence can clarify the effect. | 12–25 words | “Optimize each message with insights from every result. Small gains compound over time.” |
| Primary action | Short verb phrase naming the next step. | 2–4 words | “Get started”<br>“Book a demo”<br>“View open positions” |
| Culture statement | Conversational contrast with a specific behavioral meaning. | 12–25 words | “Standards run high and elbows stay down here. We push on the work, not on each other.” |
| Editorial title | Tell readers exactly what they will learn. | 7–14 words | “How to create or audit your data tracking plan” |

**Words and phrasing to use:** build; connect; support; scale; personalized; meaningful; outcomes; what matters; your team; by design

**Avoid:** revolutionary; unparalleled; synergy; next-generation everything; excessive exclamation marks; vague category leadership

**Rules:**

- Lead with the reader's desired effect, then name the mechanism.
- Keep reassurance small, factual and close to its action.
- Use concrete nouns for category labels; let section headlines carry the benefit.
- Allow one conversational turn of phrase in culture prose, but keep product explanations literal.
- Tie metrics to an explained change and a named source of proof.

## Do's and Don'ts

### Do

- Keep the main promise at 96px/1 and weight 475 on desktop, not a heavy display cut.
- Use a 1320px outer container with 32px internal sides to align text and panels.
- Pair 48px pills with a 12px gap and preserve their 4px perimeter rings.
- Give major chapters 128px vertical breathing room and 96px heading-to-content separation.
- Use 1px seams to build square-cornered light and dark panel systems.
- Keep proof numerals at 20px with 14px captions and a 16px inset after their vertical rule.
- Include warm contextual media and a dark teal human capability strip as recognizable visual anchors.
- Use 2px editorial corners and 4px plan corners while keeping ordinary solution grids square.

### Don't

- Do not turn all text black: the core hierarchy uses forest ink and teal-tinted secondary text.
- Do not round content panels to 16px or 24px; that erases the architectural hairline grid.
- Do not give cards broad drop shadows; the strong perimeter effect belongs to action pills.
- Do not use mint as the default page canvas; it is concentrated in signals and scoped result cards.
- Do not make every heading weight 700; reserve that strength for offer numerals.
- Do not scale small proof metrics to compete with the 40px chapter heading.
- Do not transfer the charcoal collection theme into every ordinary product chapter; deep teal is the default inverse treatment.
- Do not repeat colorful cover-art palettes in navigation, body copy and every panel border.

## Motion and responsive

### Motion

**Observed:**

- Action transitions use all .2s cubic-bezier(0,0,.35,1); many surface color transitions share that duration and easing.
- Photographic capability panels declare flex-grow 0.4s cubic-bezier(0,0,.2,1), and their veils declare opacity .2s cubic-bezier(0,0,.35,1).
- A marquee animation is declared at 40s linear infinite across the shared styling.
- The opening's final noun varies between rendered views while staying aligned to the same type baseline.

**Transfer:**

- Use restrained action color changes and let the dark capability strip reveal more image on interaction.
- If rotating a final noun, reserve its line space so the promise and actions do not jump.

**Unknown:**

- Exact noun-cycle timing and choreography are unknown.
- Marquee direction, runtime activation and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Desktop navigation has a hidden-until-large layout; feature grids declare one column, then two, then three.
- The capability-strip wrapper supports horizontal overflow rather than shrinking all panels into tiny cards.
- The newsletter form declares a stacked layout before becoming joined horizontally; the dark footer link columns are hidden in the narrow layout.

**Transfer:**

- As implementation guidance, preserve readable photographic panels in a horizontal strip on narrow screens.
- Stack split demonstrations and proof rows while keeping portrait and quotation adjacent in reading order.
- Reduce headline size before compromising its phrase structure; retain the action pair and nearby assurances.
- Keep comparison-column identity visible when adapting the pricing table.

**Unknown:**

- Mobile type sizes, exact narrow-screen gutters, navigation-menu construction and footer replacement behavior are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
