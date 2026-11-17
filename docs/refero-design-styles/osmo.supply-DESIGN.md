# Osmo — playful developer machinery

## Overview

An airy, technically minded style with the energy of an experimental design studio. Warm black and off-white alternate with electric violet and acid green, pairing tightly packed grotesk headlines with tiny monospace markings and handwritten asides. Interfaces and moving examples become physical-looking cards, wheels and oversized demonstrations rather than conventional dashboard thumbnails. It suits creative tools, learning products and memberships that need both practical credibility and a sense of play.

### Essentials

- Headlines feel stretched across a workbench: regular Haffer XH at 112px/1 with -0.06em tracking in the opening, 150px/0.9 with -0.05em tracking for monumental chapter titles, and 80px/1 for benefit leads.
- The opening is an exhibition, not a two-column sales pitch: a centered 608px floating navigation, a wide single-line promise, a 528px support line and a curved fan of dark-framed examples rising into the first 900px. Use constructed sample outputs when there is no product interface.
- Actions mix squared utility with soft selection: 40px height, 18px horizontal padding, 2px corners for conversion bars and 48px corners for standalone discovery actions or selected tabs.
- Color arrives as concentrated objects against neutral space: off-white is the ordinary landing-page default, warm black forms full chapter bands, violet fills proof and plan cards, and lime marks invitations and selected details. Keep the majority of the page neutral rather than tinting every section.
- Demonstrations have an orbital grammar: tilted cards, enormous oval backings and fine radial ticks recur around actual output. Recreate at least one such stage with representative content, not stock device mockups.
- Human marginalia punctures the technical system: 11px/1 uppercase mono tags sit beside 25px/0.8 handwritten notes in coral on light and lime on dark, often with a thin curved arrow.
- The ending becomes graphic architecture: a useful newsletter-and-links area gives way to a repeated, edge-clipped wordmark sculpture about 295px high, with tiny mono credits below. Use the new identity's lettering at the same monumental scale.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#6840ff` | `--color-violet` | surface, action, accent, link | Solid proof and plan cards, discovery buttons, small identity accents and inline links. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid green | `#a1ff62` | `--color-lime` | surface, action, accent, text | Join action, promo ribbon, selected geographic area, micro-tags and full contrasting product cards. |
| Coral red | `#f84131` | `--color-coral` | text, action, accent | Handwritten asides on light and the footer's small join action; not a broad background theme. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Off-white | `#f4f4f4` | `--color-canvas` | background, text, surface | Default landing canvas, reversed text and light alternative cards. |
| Pale panel | `#eaeaea` | `--color-panel` | surface, background | Oversized oval media backings, testimonial surrounds, inactive tabs and form fields. |
| Light rule | `#e1e1e1` | `--color-rule` | border | Hairlines between benefits and FAQ questions on light backgrounds. |
| Muted gray | `#b8b8b8` | `--color-muted` | text, accent | Past-item headings and inactive slider ticks. |
| Login charcoal | `#4f4c4c` | `--color-login` | action | Secondary login action within the floating dark navigation. |
| Raised charcoal | `#312e2e` | `--color-raised` | surface, border | Elevated dark cards, inactive controls and rules within dark chapters. |
| Warm ink | `#201d1d` | `--color-ink` | text, background, action | Primary text on light; dark section canvas and black action fills. |
| Deep media ink | `#151313` | `--color-deep` | surface, text | Dark product cards and dense media framing; slightly deeper than the dark section canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| expanded navigation | Menu charcoal | `#2a2727` | `--color-menu` | surface | Expanded navigation panel backing. |

## Typography

- **Haffer XH** — Headlines and card titles. Open, wide grotesk with a very large x-height; regular weight and tightly interlocking spacing. If unavailable, use **DM Sans**. Use 400; tune headline width before increasing weight. Font stack: "Haffer XH", "DM Sans", Arial, sans-serif.
- **Haffer VF** — Paragraphs, navigation, actions and prices. Matter-of-fact contemporary grotesk, mainly regular, with compact spacing. If unavailable, use **DM Sans**. Use 400 for almost all text and 700 for the newsletter prompt. Font stack: "Haffer VF", "DM Sans", Arial, sans-serif.
- **Haffer Mono** — Micro-labels, counters, metadata and legal chips. Tiny uppercase machine markings without added tracking. If unavailable, use **IBM Plex Mono**. Font stack: "Haffer Mono", "IBM Plex Mono", ui-monospace, monospace.
- **Brisa Pro** — Short marginal notes, arrows' captions and testimonial signatures. Fine, slanted handwritten script that contrasts with the heavy visual scale of the grotesk. If unavailable, use **Caveat**. Use 400 and keep the notes delicate rather than brush-bold. Font stack: "Brisa Pro", "Caveat", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| chapter | Haffer XH | 400 | 150px | 0.9 | -0.05em | Monumental short chapter titles and single-product dark hero titles. |
| display | Haffer XH | 400 | 112px | 1 | -0.06em | Default opening promise, expansive showcase headline and large closing invitation. |
| heading-lg | Haffer XH | 400 | 80px | 1 | -0.04em | Centered benefit or offer leads; also oversized statistics. |
| card-title | Haffer XH | 400 | 64px | 1 | -0.04em | Short centered titles in large product carousel cards. |
| heading | Haffer XH | 400 | 62px | 1 | -0.04em | Pricing, FAQ, conversion panels and editorial benefit statements. |
| compact-card-title | Haffer XH | 400 | 44px | 0.95 | -0.04em | Longer multi-line titles within product carousel cards. |
| statement | Haffer XH | 400 | 40px | 1.05 | -0.03em | Centered explanatory manifestos, proof quotes and workflow headings. |
| item-heading | Haffer XH | 400 | 30px | 1.08 | -0.03em | Update entries and content-card headings. |
| aside | Brisa Pro | 400 | 25px | 0.8 | normal | Handwritten annotations and signatures. |
| hero-support | Haffer VF | 400 | 22px | 1.2 | -0.0073em | Centered opening support with selected terms backed by pale inline chips. |
| footer-heading | Haffer VF | 400 | 20px | 1.08 | -0.02em | Footer column headings. |
| newsletter-heading | Haffer VF | 700 | 20px | 1.08 | -0.02em | Newsletter invitation. |
| lead | Haffer VF | 400 | 19px | 1.25 | -0.02em | Section support, numbered benefit headings and FAQ questions. |
| action | Haffer VF | 400 | 18px | 1 | -0.02em | Button labels and floating navigation. |
| body | Haffer VF | 400 | 16px | 1.3 | -0.01em | Paragraphs, explanatory card text and footer links. |
| marking | Haffer Mono | 400 | 11px | 1 | normal, uppercase | Eyebrows, tags, numeric metadata and attribution chips. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| course landing openings | course-display | Haffer XH | 400 | 112px | 0.9 | -0.05em | Two-line centered course title on dark. |
| pricing sections | plan-title | Haffer XH | 400 | 60px | 1 | -0.04em | Plan names. |
| pricing sections | price | Haffer VF | 400 | 36px | 1.08 | -0.02em | Currency, amount and unit arranged on one baseline. |

**Notes:**

- Keep headings regular. Their impact comes from the large x-height, width and negative tracking rather than boldness.
- Large display lines use 0.9–1 line height; explanatory statements relax to 1.05 and body copy to 1.3.
- The script stays at 25px even beside enormous headings. Mono metadata stays at 11px and reads as an attached marking, not another hierarchy of headlines.
- Preserve actual wording in accessible text when composing headlines as independently animated lines.

## Layout

**Density:** Airy at the section level, compact inside controls and metadata. Long neutral intervals separate highly composed media stages.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight text, pricing support and newsletter field gaps. |
| 10px | Update-row separation, button icon gaps and nested content-card inset. |
| 16px | Card heading-to-description gap. |
| 20px | Primary card/grid gutter and benefit-row top padding. |
| 24px | FAQ icon separation and expanded-navigation gutters. |
| 30px | Page side inset, button-to-support groups and intermediate content spacing. |
| 40px | Heading-to-support stacks, card content groups and footer top inset. |
| 48px | Major heading-to-support or heading-to-toggle separation. |
| 60px | Large proof and plan-card padding. |
| 80px | Media-to-support separation and compact chapter padding. |
| 120px | Section endings and editorial transitions. |
| 160px | Standard large-section vertical padding. |
| 200px | Major chapter introductions and media-stage lead-in. |
| 240px | Deep editorial or update-stage lead-in. |

### Containers and grids

- **wide-container**: max width 1440px · side padding 30px. Default centered desktop container; 1380px working width at the desktop reference width.
- **content-container**: max width 1188px · side padding 30px. Centered demonstration and two-column benefit container with 1128px inner width.
- **reading-container**: max width 720px · side padding 30px. FAQ and narrow reading sections; questions occupy 660px.
- **benefit-grid**: 2 columns · gap 20px. Numbered benefits with about 554px per column inside the content container.
- **feature-grid**: 3 columns · gap 20px. Small demonstrations below a large product stage.
- **plan-pair**: 2 columns · gap 20px. Centered 560px plan cards; preserve their equality while changing the fill.
- **footer-links**: 3 columns · gap 20px. Three 214px link columns to the right of a 563px newsletter block; the two major groups are separated by 136px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | utility-actions | 2px |
|  | discovery-actions | 48px |
|  | large-cards | 16px |
|  | navigation-backing | 6px |
|  | media-tiles | 5px |
|  | oval-stages | 9999px (pill) |
|  | portraits | 50% |
|  | form-fields | 3px |
| course content | chapter-cards | 8px |

## Surfaces and depth

### Surfaces

#### Light canvas · level 0

**Use:** Default marketing-page background.

**CSS:** `background: #f4f4f4; color: #201d1d`

**Observed:** Neutral space carries most of the layout; color remains concentrated in objects.

**Transfer:** Use as the baseline before introducing dark narrative chapters.

#### Dark chapter · level 0

**Use:** Pricing, showcases and immersive product chapters.

**CSS:** `background: #201d1d; color: #f4f4f4`

**Observed:** Full-width warm black rather than pure black; headings and the tiniest labels reverse together.

**Transfer:** Change chapter mood at full-width boundaries rather than fading the entire page into a gradient.

#### Oval media backing · level 0

**Use:** Large interface demonstrations and template showcases.

**CSS:** `background: #eaeaea; border-radius: 9999px`

**Observed:** A 1380px-wide backing sits behind the media, visually broad and softly rounded without blur or shadow.

**Transfer:** Let the interface overlap its upper curve; keep its controls legible and its lower edge partially concealed.

#### Violet proof card · level 1

**Use:** Testimonials, primary plan and high-emphasis invitation panels.

**CSS:** `background: #6840ff; color: #f4f4f4; border-radius: 16px; box-shadow: none`

**Observed:** Flat saturated fill with generous internal space. It is nested in a pale frame for testimonials, but stands directly on the canvas for plans.

**Transfer:** Use a concentrated rectangular violet object rather than a page-wide violet wash.

#### Pale surround · level 0

**Use:** Testimonial framing and inactive controls.

**CSS:** `background: #eaeaea; border-radius: 16px`

**Observed:** The testimonial surround is substantially larger than its inner proof card.

**Transfer:** Use a clear outer frame/inner object relationship without adding elevation shadows.

#### Lime object · level 1

**Use:** Alternative product offers and small invitation markers.

**CSS:** `background: #a1ff62; color: #201d1d; border-radius: 16px`

**Observed:** Solid acid-green rectangles contrast with violet and black; smaller tags reduce corners to 2px.

**Transfer:** Reserve full lime panels for a clear alternative or included benefit, not every feature.

#### Dark raised panel · level 1

**Use:** Content collections and inactive dark controls.

**CSS:** `background: #312e2e; color: #f4f4f4; box-shadow: none`

**Observed:** A small step lighter than the canvas communicates layering without glow.

**Transfer:** Separate dense content with fill and fine rules instead of drop shadows.

## Components

### Floating navigation

**Use:** Persistent top-level access without a full-width masthead.

**CSS:** `background: #201d1d; color: #f4f4f4; max-width: 608px; height: 54px; padding: 7px; border-radius: 6px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `action` — Haffer VF 400 · 18px/1 · tracking -0.02em

**Observed:** Centered with 20px top clearance; hamburger and Menu on the left, identity centered, rounded gray Login and squared lime Join on the right. Expanded navigation uses broad charcoal panels with 40px padding and large text links.

**Transfer:** Maintain the compact floating island and avoid replacing it with a row of numerous desktop links.

### Utility button

**Use:** Primary conversions, pricing bars and paired secondary actions.

**CSS:** `background: #201d1d; color: #f4f4f4; height: 40px; padding: 0px 18px 1px; border-radius: 2px; display: flex; align-items: center; justify-content: center; gap: 10px; overflow: hidden`

**Text style:** `action` — Haffer VF 400 · 18px/1 · tracking -0.02em

**Observed:** Labels sit in a masked wrapper with duplicate animated layers. Plan actions stretch across the content column; light, violet and lime variants use the same compact construction.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

**Transfer:** Choose black on violet or lime, violet on light, and light for a secondary action against dark.

### Discovery button

**Use:** Standalone exploration action under a product stage or inside a media card.

**CSS:** `background: #6840ff; color: #f4f4f4; height: 40px; padding: 0px 18px 1px; border-radius: 48px; display: flex; align-items: center; justify-content: center; overflow: hidden`

**Text style:** `action` — Haffer VF 400 · 18px/1 · tracking -0.02em

**Observed:** Rounded discovery actions coexist with squared conversion bars; light and dark variants appear with the same label treatment.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

### Promotion ribbon

**Use:** A tiny secondary offer immediately beneath the navigation.

**CSS:** `background: #a1ff62; color: #201d1d; height: 20px; border-radius: 3px; overflow: hidden; display: flex`

**Text style:** `marking` — Haffer Mono 400 · 11px/1 · uppercase

**Observed:** Repeated uppercase wording is punctuated with small symbols and reads as a narrow ticker, not a second navigation row.

**Transfer:** Use one short real offer, repeated horizontally with ample separation.

### Product carousel card

**Use:** Present related products or complementary capabilities as physical objects.

**CSS:** `background: #151313; color: #f4f4f4; width: 440px; height: 572px; border-radius: 16px; overflow: hidden; position: relative`

**Text style:** `card-title` — Haffer XH 400 · 64px/1 · tracking -0.04em

**Observed:** A tiny membership tag sits above a centered symbol, title and short description. The lower half contains a clipped interface. Neighboring violet and lime cards tilt away from the upright center card; longer titles use compact-card-title.

**Transfer:** Use a real sample output in the lower half and retain distinct card fills rather than making all siblings identical.

### Benefit row

**Use:** Explain practical value beneath a large editorial statement.

**CSS:** `border-top: 1px solid #e1e1e1; padding-top: 20px; display: flex; align-items: flex-start; gap: 20px`

**Text style:** `body` — Haffer VF 400 · 16px/1.3 · tracking -0.01em

**Observed:** A short lead-size title is beside a denser paragraph, with a narrow title column and a wider explanation. Numbered variants form two columns and use charcoal rules on dark.

**Transfer:** Make each row one benefit and one concrete explanation.

### Testimonial card

**Use:** Large personal proof panel.

**CSS:** `background: #6840ff; color: #f4f4f4; border-radius: 16px; padding: 60px; display: flex; flex-direction: column; gap: 40px; max-width: 680px`

**Text style:** `statement` — Haffer XH 400 · 40px/1.05 · tracking -0.03em

**Observed:** A large quote heading spans the top. Beneath it, a circular portrait and handwritten name occupy a narrow column beside the body quote; a small dark mono role chip completes the attribution. The card sits inside Pale surround with short vertical progress ticks at the edge.

**Transfer:** Use a short outcome as the heading and a specific firsthand explanation below.

### FAQ row

**Use:** Compact objection handling with topical tab filters.

**CSS:** `border-top: 1px solid #e1e1e1; padding: 20px 0px; display: flex; justify-content: space-between; align-items: center; gap: 24px`

**Text style:** `lead` — Haffer VF 400 · 19px/1.25 · tracking -0.02em

**Observed:** A 660px-wide column of roughly 65px collapsed rows; a tiny 12px plus sits at the right. Expanded body text lives below the question. The final row has a bottom rule; dark versions reverse text and use charcoal rules.

**Transfer:** Keep questions sentence-case and avoid enclosing every item in a separate rounded box.

### Newsletter field

**Use:** Footer signup with first-name and email fields.

**CSS:** `background: #eaeaea; height: 48px; padding: 12px 16px; border: 1px solid transparent; border-radius: 3px; box-shadow: none`

**Text style:** `body` — Haffer VF 400 · 16px/1.3 · tracking -0.01em

**Observed:** Two equal fields share a row with an 8px gap. Consent checkbox and privacy link sit below at the left; the dark update action sits at the right.

**Transfer:** Retain the useful compact form above the monumental footer artwork.

### Plan card

**Only for:** pricing sections

**Use:** Compare membership tiers without a dense comparison matrix.

**CSS:** `background: #6840ff; color: #f4f4f4; width: 560px; padding: 60px; border-radius: 16px; overflow: hidden`

**Text style:** `plan-title` — Haffer XH 400 · 60px/1 · tracking -0.04em

**Observed:** Order is mono user-count tag, plan name, compact 36px price and billing line, full-width Utility button, ruled benefits, then an underlined benefits link. On dark marketing sections the paired plan is off-white with a violet action. On the dedicated pricing page the paired plan is dark instead, and benefits are expanded.

**Transfer:** Keep prices subordinate to the plan title; place any savings note off to the side in script.

### Update card

**Only for:** release or collection sections

**Use:** Prove ongoing activity through a dated list.

**CSS:** `background: #312e2e; color: #f4f4f4; padding: 10px; border-radius: 5px`

**Text style:** `item-heading` — Haffer XH 400 · 30px/1.08 · tracking -0.03em

**Observed:** A 1128px by 220px row pairs a large text area on the left with a 320px by 200px preview on the right. A lime relative-date chip precedes a muted new-item tag, with category metadata below the title. Rows are separated by 10px.

**Transfer:** Use real recent additions and place a subtle dark fade over the trailing list edge.

### Chapter card

**Only for:** course or curriculum pages

**Use:** Preview a structured body of content in a horizontal rail.

**CSS:** `background: #312e2e; color: #f4f4f4; width: 431px; padding: 10px; border-radius: 8px; display: flex; flex-direction: column`

**Text style:** `item-heading` — Haffer XH 400 · 30px/1.08 · tracking -0.03em

**Observed:** A numbered top block with 30px inset contains title, short paragraph and lime lesson-count tag. A darker inset list contains numbered lessons separated by hairlines. The rail shows a partially clipped next card, with 20px gaps.

**Transfer:** Apply to genuinely sequential material rather than generic feature cards.

## Imagery and graphics

### Orbital example fan

**Use:** Signature opening demonstration and related-product stages.

**Observed:** Dark rectangular frames carry colorful working examples rather than isolated illustrations. A broad arc rises from below the viewport; central cards are nearly upright and outer cards rotate away, with clipped peripheral cards suggesting a larger wheel. Caption strips remain attached to the dark frames.

**Transfer:** Use representative reports, outputs, editorial spreads or simple live examples for a new product. The minimum is three well-designed output cards, not empty tiles.

**Build:** Arrange five to six cards around a large invisible ellipse below the hero. Use approximately 360px-wide frames, 6px dark inset and 5px corners; rotate outer cards in opposite directions, leaving the center close to upright. Add fine, low-contrast radial tick marks behind the arc using SVG lines, with the text layer in front.

### Instrument-ring markings

**Use:** Signature technical ornament behind demonstrations, testimonials and showcases.

**Observed:** Faint circular tick rings, crosshair-like rules and sparse small markers suggest a dial. Their contrast is low enough that the main media always wins.

**Transfer:** Include a ring or arc somewhere in the new page, tied to the staged object rather than scattered as decorative confetti.

**Build:** Create an SVG circle with 120–180 short radial lines. Set stroke to warm ink at about 0.08 alpha on light or off-white at about 0.1 alpha on dark; use 1px strokes and vary every fifth tick's length. Enlarge beyond the media, clip the ring to its section and fade sections of the arc with an opacity mask.

### Large working demonstration

**Use:** Main product chapter or dark product opening.

**Observed:** Wide 1128px by 705px video or interface view, lightly rounded and shown front-on. A product walkthrough may include a presenter inset; course video shows a warmly lit real person with plants, shelving and personal objects. Timeline markings below look like a fine ruler.

**Transfer:** Show the product working at readable scale, backed by Oval media backing on light or the unadorned Dark chapter. For a non-interface product show a closely framed process film or specimen of its output.

### Handwritten marginalia

**Use:** Signature human annotation around controls, headings and proof.

**Observed:** Fine coral script on light or lime on dark, a tiny curved arrow and short spontaneous notes sit just outside the formal alignment of the main text.

**Transfer:** Write a genuine aside that explains a nearby action, result or change.

**Build:** Set a short phrase in the aside recipe, rotate it slightly, and draw a 1px SVG cubic curve ending in two short arrowhead strokes. Keep its dimensions small relative to the heading; use coral or lime rather than a rainbow of notes.

### Showcase deck

**Use:** Visual proof of outcomes.

**Observed:** A lime-edged front card shows a richly colored site or output. Darkened, slightly smaller angled cards recede on both sides over warm black. The front card includes a small title and mono creator chips underneath.

**Transfer:** Show complete real outcomes rather than an array of corporate logos. If there are no external examples, create clearly labeled representative outputs.

**Build:** Layer three to five landscape cards with the central one fully opaque, lime backing and 6px corners. Reduce neighboring cards to roughly 0.5–0.75 opacity, rotate them away and move them behind; add a faint instrument ring underneath.

### Monumental identity strip

**Use:** Signature footer artwork on every page.

**Observed:** A thick, repeated black wordmark runs past both viewport edges in a band about 295px high. The crop turns lettering into a bold graphic field, sharply contrasting with the delicate footer details.

**Transfer:** Use the new identity's own lettering, or a heavy typographic rendering of its name, with repetition and tight overlap.

**Build:** Create an accessible SVG wordmark band approximately 1757px wide at a 1440px viewport, centered and horizontally clipped. Repeat the new name without generous word gaps, fill in warm ink, and reserve a 32px gap before the mono legal/credit row.

### Geographic proof instrument

**Only for:** community or geographically distributed proof

**Use:** Make a testimonial feel connected to a real person and place.

**Observed:** A tall dark oval contains a low-contrast globe, a lime highlighted region and a tick ring. It pairs with the violet proof card on a pale surround. The community introduction uses a broad violet world map instead; the selected statistic is shown in a light 475px by 204px panel with an 80px percentage.

**Transfer:** Use geography only when it supports a truthful claim; otherwise use a subject-specific diagram or portrait inside the same oval instrument construction.

**Build:** Clip a simple vector map to a circle inside a dark stadium-shaped panel. Fill unselected land in raised charcoal, selected land in lime, and add short off-white radial ticks at low opacity. Place a tiny top label and handwritten bottom caption.

### Human collage sculpture

**Only for:** people-led closing invitations and creator introductions

**Use:** An expressive counterpart to a clean conversion panel.

**Observed:** A person or clothing figure is fractured into curved strips or twisting forms, layered across repeated giant white words inside a dark oval; the adjacent violet card remains simple. Creator panels similarly warp a portrait against violet.

**Transfer:** Use the product's people or materials if suitable; a minimum version can interleave a cutout silhouette with three curved text masks rather than attempting a complex 3D simulation.

**Build:** Place a high-resolution cutout over two to three large stacked display lines, clip alternating fragments with broad curved SVG masks and offset/rotate those fragments. Use a dark oval backing, white words and one lime handwritten sign-off.

### Documentary portrait stack

**Only for:** community, events and creator stories

**Use:** Add social warmth to otherwise technical chapters.

**Observed:** Natural-color candid photos and circular avatar cutouts; event images overlap as tall slightly rotated prints without elaborate frames. They can extend beyond the content edge.

**Transfer:** Use authentic environments and informal gestures, not uniform corporate headshots or a heavily color-graded campaign shoot.

### Icons

**Observed:** Small filled SVG symbols dominate: 20px inside actions, 12px plus/check details and 32px expressive accents. Fine 1px outline icons and 24px circular arrow affordances appear where needed. Icons inherit the local light/dark contrast; lime or coral is reserved for emphasis.

**Transfer:** Choose compact geometric symbols with a consistent visual weight. Pair tiny pluses, checks and arrows with text, and replace identity-specific symbols with the new product's own mark.

## Section recipes

How recurring sections are built.

### First screen: Orbital promise opening

**Observed:** Light canvas is the default. Floating navigation sits centered above generous empty space with Promotion ribbon tucked beneath. A single-line 112px display promise spans about four fifths of the width near the upper-middle of the screen, split by a small violet identity symbol. A centered 528px support block follows, with pale inline chips around selected nouns. Fine vertical and radial markings sit behind everything. The main visual is a fan of dark-framed examples rising from the bottom, nearly upright at the center and angled at the edges. Within the first 900px the full title, support, navigation actions and upper portion of this media fan are visible; most of the fan and the explanatory chapter continue below. Conversion is carried by the top-right Join action and the slim offer ribbon, not a large button cluster under the hero.

**Transfer:** Use a short category-plus-benefit promise, the new product's own symbol and several tangible outputs. If there is no interface, design output specimens at the same scale. Product-detail variants open on Dark chapter with a centered 150px short title or course-display on two lines, a small inclusion marker under the navigation and a large walkthrough beginning below the support. Pricing pages use an 80px promise followed immediately by a billing toggle and plan pair.

**Avoid:** Do not collapse this into a standard left-text/right-laptop hero, add a giant colored gradient background, or replace the example fan with anonymous abstract blobs.

**Text style:** `display` — Haffer XH 400 · 112px/1 · tracking -0.06em

### Monumental heading pair

**Observed:** A short chapter title uses chapter at 150px, with a tiny coral handwritten aside close to its upper edge. Centered lead text is limited to about 544px and separated by 48px; the following media stage gets another 80px of breathing room.

**Transfer:** Use very short nouns or concepts for oversized titles, then explain practical value in one concise paragraph.

**Text style:** `chapter` — Haffer XH 400 · 150px/0.9 · tracking -0.05em

### Editorial statement and benefits

**Observed:** A centered statement at 40px occupies roughly 768–1128px above a two-column numbered grid with 20px gutters. Each item has a fine top rule, a small number at left and a short lead heading plus body. The light editorial variant shifts the whole block right, pairing a 62px statement with an 800px-wide stack of Benefit rows and a handwritten note in the left margin.

**Transfer:** Move from a broad promise to specific mechanisms. Highlight one meaningful phrase in lime on dark or violet on light rather than coloring the whole statement.

**Text style:** `statement` — Haffer XH 400 · 40px/1.05 · tracking -0.03em

### Oval demonstration stage

**Observed:** Oval media backing fills the wide container; a 1128px front-on demonstration sits above it. Support and a Discovery button follow beneath the demonstration. Template variants show one centered large preview and clipped side previews, with mono slide index and tiny count labels.

**Transfer:** Give the main object room to dominate; use the backing as a stage, not as a card enclosing multiple paragraphs.

### Product orbit

**Observed:** An 80px heading and 19px support introduce a row of compact category controls. Below, Product carousel card stands upright in the center with violet and lime neighbors leaning outward; about 48px separates controls from cards. Fine ring marks echo the opening.

**Transfer:** Use this for a collection of genuinely distinct offers or capabilities, with each card carrying a real demonstration.

**Text style:** `heading-lg` — Haffer XH 400 · 80px/1 · tracking -0.04em

### Proof instrument pair

**Observed:** An approximately one-third-width dark oval instrument pairs with a two-thirds pale surround containing Testimonial card. A globe or subject diagram anchors the left, while the actual quote gets the brighter violet rectangle. Thin progress ticks sit at the outer edge.

**Transfer:** Connect a human outcome to a visual context, keeping the proof headline much shorter than the body quote.

**Text style:** `statement` — Haffer XH 400 · 40px/1.05 · tracking -0.03em

### Objection handling

**Observed:** A 62px centered heading is accompanied by a small handwritten joke or reassurance just beyond its edge. Topic buttons follow after 40px; the FAQ row stack begins after a broader interval. The reading container keeps this chapter narrow. Light is the default; course pages use a dark inverted version.

**Transfer:** Group questions by a few familiar topics and preserve the short collapsed rhythm rather than displaying all answers at once.

**Text style:** `heading` — Haffer XH 400 · 62px/1 · tracking -0.04em

### Demo closing invitation

**Observed:** A dark 16px-corner panel inset 30px from the page edge, about 626px high. The left half has a tiny mono tag, short support, 62px two-line invitation, violet Utility button and lime handwritten arrow note. The right half is a large cropped interface reaching the panel's lower and right edges. Faint tick arcs run behind both halves.

**Transfer:** Offer a concrete next step or sample. Without interface media use a large specimen or process view on the right.

**Text style:** `heading` — Haffer XH 400 · 62px/1 · tracking -0.04em

### Identity-scale footer

**Observed:** Light canvas returns for a 900px desktop ending. At the top, Newsletter field and a short bold prompt occupy the left; three link columns occupy the right. Small login/join controls and social icons sit below the links. Substantial empty space separates utility content from Monumental identity strip; a 32px gap leads to tiny legal chips at left, copyright centered and maker credits at right.

**Transfer:** Preserve the dramatic size change from practical small content to giant identity artwork. End a course page directly after its dark FAQ with this same light footer; it does not need another conversion panel.

**Text style:** `footer-heading` — Haffer VF 400 · 20px/1.08 · tracking -0.02em

### Membership comparison

**Only for:** pricing sections

**Observed:** Dark chapter with centered 62px heading, a 48px gap to the billing selector and a script savings note offset beside it. Two equal Plan cards follow with a 20px gutter; violet and off-white are the marketing defaults. Dedicated pricing uses violet and black on light and expands the benefits. An alternative course offer pairs a dark oval one-time price against a lime rectangular included option, joined by a small circular 'or'.

**Transfer:** Keep a clear visual comparison and use real billing choices; make the alternative offer materially different rather than adding more identical tiers.

**Text style:** `heading` — Haffer XH 400 · 62px/1 · tracking -0.04em

### Activity ledger

**Only for:** release or collection sections

**Observed:** A dark chapter opens with two 80px headings at opposite ends: a category at left and recency at right. A handwritten note bridges the center above a brief support paragraph. A compact vertical stack of Update cards occupies the content container below.

**Transfer:** Use temporal proof or another truthful live metric instead of substituting generic feature claims.

**Text style:** `heading-lg` — Haffer XH 400 · 80px/1 · tracking -0.04em

### Curriculum rail

**Only for:** course or curriculum pages

**Observed:** A 150px centered chapter heading precedes tiny lesson-count and duration tags, 19px support and a horizontal Chapter card rail. Part of the next card remains visible; actions sit below the rail.

**Transfer:** Break a long body of material into numbered, scan-friendly blocks with actual contents.

**Text style:** `chapter` — Haffer XH 400 · 150px/0.9 · tracking -0.05em

### Sculpture closing invitation

**Only for:** people-led or membership product closings

**Observed:** Two nearly equal side-by-side panels with a 20px gap: Human collage sculpture in a dark oval on the left, and a violet rectangle with a 112px two-line invitation on the right. A small avatar proof strip appears above; support and paired black/light actions sit below.

**Transfer:** Pair expressive visual art with an extremely clear next step. A simple cutout-and-type composition is sufficient when complex art is unavailable.

**Text style:** `display` — Haffer XH 400 · 112px/1 · tracking -0.06em

## Page flow

**Storyline:** Promise → tangible demonstration → practical mechanisms → human or output proof → clear offer → objection handling or low-risk next step → monumental identity ending.

### Broad marketing landing page

1. **Promise** — Wide one-line title over an orbital fan of output examples.
2. **Product demonstration** — Centered manifesto and compact reel, followed by creator/recency objects and an oversized interface stage.
3. **Capability chapters** — Product orbit followed by a right-shifted editorial statement and ruled benefits.
4. **Social proof** — Geographic proof instrument and violet quote card.
5. **Pricing** — Dark chapter with compact plan pair.
6. **Output proof** — Spread-out display heading over a lime-fronted showcase deck.
7. **Closing call** — Dark demo invitation with oversized cropped product view.
8. **Identity ending** — Newsletter, links, giant repeated wordmark and mono credits.

**Transfer:** Adapt the order to the product; preserve the interplay of large stages, quiet practical explanations and concentrated proof objects.

### Dedicated pricing and purchase decision page

1. **Promise** — Centered 80px value promise on light, small avatar proof and billing toggle.
2. **Pricing** — Violet and black plan cards with expanded ruled inclusions.
3. **Alternative offers** — Dark oval discount offer paired with lime one-time product card.
4. **Workflow reassurance** — Dark two-column compatibility explanation with large documentation views.
5. **Objection handling** — Light narrow FAQ with category controls.
6. **Closing call** — Dark demo invitation.
7. **Identity ending** — Full light newsletter-and-wordmark footer.

**Transfer:** Move commercial facts earlier; keep inclusions readable rather than turning the page into a spreadsheet.

### Community or network benefit landing page

1. **Promise** — Single giant light title on dark with a violet world-map stage.
2. **Quantified proof** — Selected region statistic and geographic distribution bars beside direct invitation copy.
3. **Capability chapters** — Large statement followed by a rounded communication-interface view and a short ruled benefits list.
4. **Output proof** — Dark showcase deck with lime front card.
5. **Human proof** — Light monumental heading over event list and overlapping candid prints, followed by testimonial pair.
6. **Objection handling** — Light narrow FAQ.
7. **Closing call** — Dark oval sculpture beside violet invitation.
8. **Identity ending** — Full light newsletter-and-wordmark footer.

**Transfer:** For other network products use credible participation evidence and real people, with geography only if meaningful.

### Course or guided-learning product page

1. **Promise** — Two-line centered course title on dark with inclusion labels and short explanatory support.
2. **Product demonstration** — Large presenter video and fine ruler-like playback timeline.
3. **Capability chapters** — Dark statement, numbered benefits and horizontal curriculum rail.
4. **Product proof** — Light template stage, concrete numbered mechanisms and tilted outcome examples with creator portraits.
5. **Social proof** — Geographic instrument beside a violet learner quote.
6. **Pricing** — One-time dark oval price versus lime included-with-membership offer.
7. **Objection handling** — Dark narrow FAQ.
8. **Identity ending** — Immediate transition to full light footer without an extra conversion panel.

**Transfer:** Show the teaching experience and actual deliverables before the purchase choice; keep the dark opening and light demonstration chapters distinct.

### Flagship software or resource-library product page

1. **Promise** — Giant short title on dark followed by a wide working walkthrough.
2. **Practical mechanisms** — Centered statement and two-column numbered benefits.
3. **Activity proof** — Large recency heading pair and compact preview ledger.
4. **Capability chapters** — Light monumental heading and oval-backed interface stage, followed by a three-column demonstration grid.
5. **Workflow reassurance** — Dark compatibility split with documentation views.
6. **Low-risk trial** — Dark demo panel on light.
7. **Offer breadth** — Light product orbit and small identity proof.
8. **Pricing** — Dark compact plan pair.
9. **Objection handling** — Light FAQ.
10. **Closing call** — Sculptural oval and violet invitation.
11. **Identity ending** — Full light newsletter-and-wordmark footer.

**Transfer:** Use activity and readable software demonstrations to prove a living product; avoid requiring a new product to inherit the same content categories.

## Writing

Confident maker-to-maker conversation: practical, informal and a little mischievous. Claims are followed by mechanisms, examples or personal testimony, with occasional jokes in the margins rather than polished corporate slogans.

**Do not copy:** Do not reuse the Osmo name, identity artwork, proprietary symbols, named people, customer quotes, awards, resource counts, membership counts, discounts, prices or product claims as facts about another brand. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and use 'we' for the people making the product. Prefer concrete verbs over impersonal platform language.
- **Rhythm:** Short punchy headings, a single compact support paragraph and clear verb-led actions. Longer manifesto-style statements can span several tightly set lines; marginal script notes are brief conversational interruptions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Category plus an energetic practical promise, or a very short product noun. | 1–7 words | “Dev Toolkit Built to Flex”<br>“The Vault” |
| Supporting line | Explain what people can actually access, adapt or achieve. | 1–3 sentences | “Build, tweak, and make them your own.”<br>“Learn how to build seamless page transitions using BarbaJS and GSAP.” |
| Primary action | A direct verb and tangible destination or commitment. | 1–5 words | “Become a member”<br>“Unlock the demo”<br>“Buy the Course” |
| Benefit heading | Plain verb-led improvement with no jargon padding. | 3–6 words | “Build faster and better”<br>“Speed without compromise” |
| Handwritten aside | A candid nudge, joke or small reassurance about the neighboring element. | 3–9 words | “New stuff is added every week!”<br>“Finally, your kind of group chat”<br>“We even answered without ChatGPT ;)” |
| Objection handling | Real customer question followed by a plain, direct answer. | One question; a short answer paragraph | “Can I pause or cancel my subscription anytime?”<br>“Got questions? We’ve got answers.” |

**Words and phrasing to use:** build; tweak; make it your own; ready-to-go; real-world; toolkit; production-ready; take a peek; yep; we built

**Avoid:** revolutionary ecosystem; synergize; unlock unprecedented potential; enterprise-grade excellence; frictionless digital transformation

**Rules:**

- Use precise mechanisms to support benefit claims: what is included, how it works and what the user can change.
- Keep jokes and expressive punctuation mainly in asides, not in every headline.
- Let technical language remain technical where useful; do not replace clear tool names with vague innovation language.
- Frame choice and reassurance in the reader's own terms, especially billing, support and prerequisites.

## Do's and Don'ts

### Do

- Use 112px regular display type with -0.06em tracking for a wide opening promise.
- Keep the default landing canvas off-white and concentrate violet in individual 16px-corner objects.
- Stage at least one example fan or oval-backed demonstration with fine radial ticks.
- Use 11px uppercase mono labels at metadata scale rather than enlarging them into subheadings.
- Mix 2px utility buttons and 48px discovery buttons intentionally, retaining the 40px height.
- Use 20px grid gutters and 60px internal padding for large plan and quote cards.
- Let a real interface occupy about 1128px of width in its main demonstration chapter.
- End with useful footer content and an edge-clipped identity band about 295px high.

### Don't

- Do not make headings bold to compensate for a narrower substitute; retain regular weight and tune width.
- Do not turn all action shapes into pills; plan bars and ordinary conversion buttons have 2px corners.
- Do not apply violet as a faint full-page tint; it functions as an opaque proof object or action.
- Do not introduce shadow-heavy floating cards; depth comes from overlap, charcoal fill changes and rotation.
- Do not use pure black for the ordinary dark chapter; its base is the warmer #201d1d.
- Do not enlarge script annotations to compete with 62–150px headlines.
- Do not replace 1px ruled benefit or FAQ lists with stacks of padded bordered boxes.
- Do not use tiny unreadable software thumbnails where a 1128px demonstration is the narrative focus.

## Motion and responsive

### Motion

**Observed:**

- Slider tick lines declare transform 0.55s cubic-bezier(0.625, 0.05, 0, 1) and background-color 0.2s ease transitions.
- Other action/surface rules declare transform 1.2s cubic-bezier(0.625, 0.05, 0, 1) and opacity 0.2s.
- Headline lines and button labels are built with clipped wrappers; carousels use translated and rotated items. The promotion ribbon repeats wording horizontally.

**Transfer:**

- Use the masking architecture for headline reveals and button-label movement, with media cards moving as whole physical objects.
- Keep tick/progress feedback quieter and quicker than the large orbital card movement.

**Unknown:**

- Autoplay duration, scroll-linked choreography, video progression and precise reveal triggers are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 600px, 767px, 768px and 991px.

**Transfer:**

- On narrow screens, preserve the centered floating navigation with reduced side clearance and keep account actions reachable.
- Scale or wrap display promises before sacrificing their tight spacing; retain an upright central demonstration while peripheral cards can remain clipped.
- Stack proof and offer pairs while keeping the dark oval and saturated rectangle visibly different. Turn wide curriculum and collection stages into deliberate horizontal rails.
- Preserve edge-clipped identity artwork instead of shrinking it into an ordinary small footer logo.

**Unknown:**

- Exact mobile type sizes, spacing, menu expansion and section reordering are not established; these are adaptation guidelines, not measured mobile specifications.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
