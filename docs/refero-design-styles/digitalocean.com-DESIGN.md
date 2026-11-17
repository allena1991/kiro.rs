# DigitalOcean — luminous systems terrain

## Overview

A dark, builder-facing style that makes complex technology feel integrated and approachable. Bold geometric sans headings and practical grotesk body copy sit on black and deep green, with cyan controls and restrained pools of teal, olive and violet light. Wireframe terrain, drafting-like diagrams and compact proof cards give it a technical atmosphere without the density of a product dashboard. It suits infrastructure, developer tools and technical platforms, with warmer photography reserved for people-focused stories.

### Essentials

- A luminous landscape carries the promise rather than a giant interface mockup: center a 48px/56px, weight 800 headline above a full-width fine-line terrain, with an overhead teal-to-olive radial glow and small 10px/14px mono scale markings.
- Bold but contained headlines leave the scene room to breathe: Plus Jakarta Sans at 48px with -1.5px tracking for the opening, 36px/48px with -1px tracking for major chapters, and Inter 16px/24px for explanation.
- Actions are small bright capsules in a very dark world: 40px height, 8px 24px padding, cyan fill with black text, beside an off-white 1px inset-outline alternative; labels use Inter 16px/24px at 500.
- Black is the majority of the page, deep green separates content, and color behaves like light: #000000 canvas, #000f0f cards, #6fe0ed controls and links; broad color belongs to the opening atmosphere and contained illustrated panels, not every section.
- Proof is embedded in the technical landscape: three 347px-wide, 16px-radius dark cards with 24px 32px inner padding, 36px/48px statistics and bottom-aligned arrow links. Use verified outcomes or concrete operational facts when numerical proof is unavailable.
- Technical art stays fine-lined and instrument-like: circles, rectangular frames, dotted coordinates and narrow teal rules on dark green backings; include an original diagram panel even when no product media exists.
- A luminous invitation punctuates the ending: a 1088px-wide, 16px-radius panel with dotted orbital arcs, a blue-to-violet glow rising from below, a centered 36px heading and a white capsule action, followed by a spacious five-column black footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Luminous cyan | `#6fe0ed` | `--color-cyan` | action, link, accent | Primary actions, active tabs, inline links and circular carousel controls. |
| Announcement teal | `#104b55` | `--color-announcement` | background | Slim utility announcement strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sage annotation | `#6f908c` | `--color-muted` | text | Technical annotations, small labels and depth-scale numerals. |
| Green rule | `#1f403e` | `--color-rule` | border, surface | Content dividers and accordion answer rules; secondary green actions in pricing. |
| Black canvas | `#000000` | `--color-canvas` | background, text | Main page and navigation background; text on cyan and light controls. |
| Deep green panel | `#000f0f` | `--color-panel` | surface | Cards, illustrated panels, accordion rows and closing invitation backing. |
| Raised green | `#081f1e` | `--color-raised` | surface | Segmented-control tracks and selected pricing-card backing. |
| Panel edge | `#182625` | `--color-edge` | border | Visible soft-white 10% edge on deep green panels; use rgba(244,245,245,0.1) in CSS. |
| Green white | `#e5eceb` | `--color-body` | text | Paragraphs, navigation and footer links. |
| Soft white | `#f4f5f5` | `--color-heading` | text, action, border | Headings, outline controls and white closing buttons. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing catalogs | Offer blue | `#477fa5` | `--color-pricing-blue` | surface | Full-width contextual offer panel with black text. |
| product compatibility and plan comparisons | Compatibility olive | `#a6b559` | `--color-lime` | surface, accent | Compatibility-name pills and trial credit highlight. |
| pricing catalogs | Sales ice | `#c6ddf8` | `--color-sales-blue` | surface | Sales-assistance banner with black text. |

## Typography

- **Plus Jakarta Sans** — Marketing headings, proof statistics and prices. Geometric sans with broad round counters, firm heavy cuts and compact headline tracking. Font stack: "Plus Jakarta Sans", sans-serif.
- **Inter** — Paragraphs, controls, navigation, metadata and footer. Practical grotesk with a high x-height, used mostly at regular and medium weights. Font stack: "Inter", "Inter Fallback", sans-serif.
- **JetBrains Mono** — Tiny instrumental scale numerals around technical scenes. Monospaced technical lettering, deliberately subordinate to the marketing copy. Font stack: "JetBrains Mono", "JetBrains Mono Fallback", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Plus Jakarta Sans | 800 | 48px | 56px | -0.03125em | Centered primary promise; also the left-aligned corporate opening. |
| heading | Plus Jakarta Sans | 700 | 36px | 48px | -1px | Default centered chapter heading, closing invitation and proof statistic. |
| heading-emphasis | Plus Jakarta Sans | 800 | 36px | 48px | -1px | Heavier capability chapters and left-aligned resource headings. |
| subheading | Plus Jakarta Sans | 700 | 24px | 32px | normal | Feature titles, resource-card titles and tab-content heading. |
| body | Inter | 400 | 16px | 1.5 | normal | Paragraphs and centered support lines. |
| control | Inter | 500 | 16px | 1.5 | normal | Buttons, selected tabs and primary navigation. |
| text-action | Inter | 600 | 16px | 1.5 | normal | Arrow-ended card and section links. |
| footer-heading | Inter | 700 | 16px | 1.5 | normal | Footer column headings. |
| small | Inter | 400 | 14px | 20px | normal | Footer links, inline technical links and dense supporting descriptions. |
| metadata | Inter | 500 | 14px | 20px | normal | Dates, utility links and compatibility labels. |
| instrument | JetBrains Mono | 400 | 10px | 1.4 | normal | Scale labels integrated into the landscape. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| dedicated product pages | product-display | Plus Jakarta Sans | 800 | 48px | 56px | -1px | Long product-name opening. |
| pricing catalogs | price | Plus Jakarta Sans | 700 | 48px | 56px | -0.03125em | Starting prices, paired with much smaller billing units. |
| pricing catalogs | category | Plus Jakarta Sans | 700 | 28px | 36px | normal | Left-aligned category headings above catalog cards. |
| product and pricing comparisons | card-heading | Plus Jakarta Sans | 700 | 20px | 1.4 | normal | Plan names and detailed product-card titles. |
| recruitment listings | listing-heading | Inter | 700 | 20px | 1.4 | normal | Department names and job titles. |
| FAQ and benefit disclosures | question | Inter | 500 | 18px | 26px | normal | Accordion question labels. |
| preview product openings | eyebrow | Inter | 600 | 14px | 20px | normal | Muted release-stage label directly above the product name. |

**Notes:**

- The default hierarchy is deliberately modest in scale but heavy in weight: 48px to 36px to 24px. Do not replace it with oversized thin display text.
- Tracking tightens only on the larger headings; body, labels and controls keep normal tracking. Use sentence case rather than widely tracked capitals.
- Keep centered support copy near 640px wide; the closing panel narrows its copy to 464px. Long resource titles wrap over several lines rather than shrinking.

## Layout

**Density:** Airy between chapters, comfortable within cards, compact within utility navigation.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Primary horizontal spacing step; 16px and 24px are the dominant multiples.

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap, footer-list gap and compact control padding. |
| 16px | Adjacent hero actions and vertical tab-item gap. |
| 24px | Card-grid gap, card vertical padding and major card-content gaps. |
| 32px | Card horizontal padding and opening action separation. |
| 40px | Container side padding and closing-copy-to-action gap. |
| 64px | Wide editorial-grid gap and heading-to-content separation. |
| 72px | Vertical space outside closing invitation panels. |
| 80px | Opening vertical padding and roomy heading-to-media separation. |
| 96px | Main section and footer vertical padding. |
| 120px | Roomier lower spacing after resource or feature chapters. |

### Containers and grids

- **content shell**: max width 1168px · side padding 40px. Centered desktop shell with 1088px usable content at a 1440px viewport.
- **hero text**: max width 864px. Centered headline and action group, with narrower supporting text.
- **support copy**: max width 640px. Centered paragraphs above grids and illustrations.
- **three card grid**: max width 1088px · 3 columns · gap 24px. Equal proof and resource cards, about 347px wide.
- **editorial pair**: max width 1088px · 2 columns · gap 64px. Two 512px-wide feature or editorial blocks; text and illustration can share this split.
- **footer grid**: max width 1088px · 5 columns · gap 32px. Five left-aligned columns of approximately 192px each.
- **catalog shell** (only for pricing catalogs): max width 1440px · gap 56px · side padding 64px. A 192px category sidebar beside a 1064px catalog region; three approximately 339px cards with 24px gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsule controls | 9999px (pill) |
|  | active feature tab | 64px |
|  | cards and media | 16px |
| dedicated product pages | product FAQ | 8px |
| corporate timelines | history panel | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| panel delineation | `inset 0px 0px 0px 2px rgba(244, 245, 245, 0.1)` | A restrained edge rather than a floating drop shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous page background.

**CSS:** `background: #000000; color: #e5eceb`

**Observed:** Most chapters share the same black field; separation comes from spacing rather than alternating bands.

**Transfer:** Keep the black field continuous through the narrative.

#### Deep panel · level 1

**Use:** Proof cards, resource cards and illustrated invitations.

**CSS:** `background: #000f0f; border-radius: 16px; box-shadow: inset 0px 0px 0px 2px rgba(244, 245, 245, 0.1); overflow: hidden`

**Observed:** The outline is faint and often implemented as an inset overlay; panels remain nearly flush with the page.

**Transfer:** Use the same dark panel construction for new content rather than introducing elevated white cards.

#### Overhead atmosphere · level 0

**Use:** Opening scene light.

**CSS:** `background-image: radial-gradient(100% 41.1% at 50% 0%, rgba(201, 238, 242, 0.75) 0%, rgba(48, 203, 217, 0.6) 10%, rgba(135, 155, 66, 0.3) 50%, rgba(0, 0, 0, 0) 100%); background-position: 50% 0%; background-size: cover`

**Observed:** A pale cyan source at the top center spreads through turquoise and muted olive before dissolving into black. Short informational openings use a shallower stage with a 70% vertical radial extent; dedicated product openings use 100%.

**Transfer:** Match the soft luminous falloff while leaving copy and wireframe edges crisp.

#### Segment track · level 1

**Use:** Horizontal multi-step selectors.

**CSS:** `background: #081f1e; border-radius: 9999px; padding: 8px; display: flex; gap: 8px`

**Observed:** A cyan active capsule sits inside the dark-green track.

**Transfer:** Use for staged processes and timelines; vertical capability tabs stay on the black canvas.

#### Offer band · level 1

**Only for:** pricing catalogs

**Use:** A contextual offer interrupting dense catalog content.

**CSS:** `background: #477fa5; color: #000000; border: 2px solid rgba(244, 245, 245, 0.1); border-radius: 16px; padding: 24px`

**Observed:** Short bold lead, explanatory text and a dark-green capsule on the right. The sales-assistance variant uses #c6ddf8.

**Transfer:** Reserve these blue fills for exceptional assistance messages, not standard feature cards.

## Components

### Sticky navigation

**Use:** Persistent global wayfinding.

**CSS:** `position: sticky; top: 0px; z-index: 1000; background: #000000`

**Text style:** `control` — Inter 500 · 16px/1.5

**Observed:** Two tiers total 110px: a 38px teal announcement strip with a left message and right utility links, then a 72px black navigation bar. The lower bar has 64px horizontal and 16px vertical padding, a left logo, centered menu choices with small chevrons, and login plus cyan signup on the right.

**Transfer:** Keep the two-tier information hierarchy and restrained density with a different identity.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #6fe0ed; color: #000000; border-radius: 9999px; padding: 8px 24px; height: 40px`

**Text style:** `control` — Inter 500 · 16px/1.5

**Observed:** A short centered text label, paired with an outline action in the opening. The navigation uses narrower 16px horizontal padding. The luminous closing invitation uses a #f4f5f5 fill instead of cyan.

**States:** Declared: hover background #1aafbf; focus-visible background and 2px solid outline #1aafbf with 2px offset. The white closing variant changes to cyan with black text on hover and focus-visible, with a cyan 2px outline and 2px offset.

**Transfer:** Use one clear primary action per decision point.

### Outline button

**Use:** Secondary exploration alongside a primary action.

**CSS:** `background: transparent; color: #f4f5f5; border-radius: 9999px; padding: 8px 24px; height: 40px; box-shadow: inset 0px 0px 0px 1px #f4f5f5`

**Text style:** `control` — Inter 500 · 16px/1.5

**Observed:** The same capsule silhouette as the primary button; standalone browse links can append a right arrow.

**States:** Declared: hover removes inset shadow, fills cyan and changes text to black; focus-visible does the same with a 2px solid cyan outline and 2px offset.

### Arrow text link

**Use:** Card and section continuation.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; color: #f4f5f5`

**Text style:** `text-action` — Inter 600 · 16px/1.5

**Observed:** Text followed by a small 18px by 12px outline arrow, frequently anchored near the bottom of a card.

**Transfer:** Keep the arrow adjacent to the label rather than in a separate filled square.

### Inline link

**Use:** Technical names inside prose and lists.

**CSS:** `color: #6fe0ed; background-image: linear-gradient(#6fe0ed, #6fe0ed); background-size: 1px 1px; background-position: 50% 100%; background-repeat: repeat-x`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** Cyan text with a fine baseline underline; unlike the arrow link it lives within a sentence.

**States:** Declared: hover text changes to #f4f5f5.

### Proof card

**Use:** A verified operational outcome with supporting context.

**CSS:** `background: #000f0f; border-radius: 16px; padding: 24px 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 24px; box-shadow: inset 0px 0px 0px 2px rgba(244, 245, 245, 0.1)`

**Text style:** `heading` — Plus Jakarta Sans 700 · 36px/48px · tracking -1px

**Observed:** Three equal cards sit over the terrain. Each begins with a prominent statistic, then an 18px bold outcome label, explanatory body copy, an identity mark and an Arrow text link at the bottom.

**Transfer:** Keep the statistic and its meaning separate, and ground every metric in a specific use case.

### Resource card

**Use:** Article, tutorial or news continuation.

**CSS:** `background: #000f0f; border-radius: 16px; padding: 24px 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 24px; box-shadow: inset 0px 0px 0px 2px rgba(244, 245, 245, 0.1)`

**Text style:** `subheading` — Plus Jakarta Sans 700 · 24px/32px

**Observed:** A small category icon and label precede the multiline title; 14px medium metadata and a bottom Arrow text link follow. The desktop carousel exposes three full cards and part of the next, with 24px gaps; its header has an outline browse action and two 40px cyan circular arrow controls. Editorial variants use a full-width image above the text.

### Feature tab

**Use:** Select among integrated capability chapters.

**CSS:** `background: #6fe0ed; color: #000000; border-radius: 64px; padding: 8px 16px; height: 40px`

**Text style:** `control` — Inter 500 · 16px/1.5

**Observed:** The active text capsule follows a small technical symbol outside its left edge. Inactive tabs are unfilled with light text. The vertical list has 16px gaps; its content panel combines an illustration with title, body and ruled link groups. Horizontal process and history variants use Segment track.

**States:** Declared: hover keeps cyan background and black text in the dark theme.

**Transfer:** Keep the selected state unambiguous; use the same scene language for each capability.

### Footer columns

**Use:** Complete global ending below the luminous invitation.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(192px, 1fr)); gap: 32px; background: #000000`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** Five left-aligned columns begin after 96px of space, with 16px bold headings and link lists separated from headings by 16px. Link rows have 8px gaps. The final baseline places the small logo, copyright and sitemap at left and monochrome social icons at right.

**States:** Declared: footer-link hover changes text from green white to soft white.

**Transfer:** Scale the number of links to the new information architecture while retaining the clear column hierarchy and generous final baseline.

### FAQ row

**Only for:** FAQ and benefit disclosures

**Use:** Compact objection handling.

**CSS:** `background: #000f0f; border: 1px solid rgba(244, 245, 245, 0.1); border-radius: 16px; padding: 20px; overflow: hidden`

**Text style:** `question` — Inter 500 · 18px/26px

**Observed:** Question left, 24px outline plus at right, typically a 68px closed row. Two 532px columns with 24px gaps for product and pricing questions; a single 864px stack for people-focused content. Dedicated product rows use an 8px radius. Expanded answers begin below a 1px green divider.

**Transfer:** Keep answers behind disclosure controls rather than printing every answer into the page.

### Price card

**Only for:** pricing catalogs

**Use:** Compare starting costs and capabilities.

**CSS:** `background: #000f0f; border-radius: 16px; box-shadow: inset 0px 0px 0px 2px rgba(244, 245, 245, 0.1); padding: 24px 32px; display: flex; flex-direction: column; align-items: flex-start; gap: 24px`

**Text style:** `card-heading` — Plus Jakarta Sans 700 · 20px/1.4

**Observed:** Name, starting-at label, 48px price with a small billing suffix, concise purpose, dotted rule, olive checkmarked benefits and a bottom Arrow text link. Rows align card bottoms even when lists vary. Selected offerings use Raised green. Subscription comparisons use compact plan-price pills instead of catalog-size price figures.

**Transfer:** Keep costs, units and qualification visibly adjacent; preserve equal row heights without fabricating empty features.

## Imagery and graphics

### Wireframe terrain

**Use:** Signature opening scene beneath and behind the promise and proof.

**Observed:** A full-bleed dark mountain-like mesh fills the lower opening. Thin pale teal triangles and pinpoints form uneven peaks, with a low central valley that holds a row of monochrome customer marks. Depth labels run down the right edge. The terrain is darker than the copy and remains visible between foreground cards.

**Transfer:** Represent the new product as a continuous technical field, not a literal mountain asset. The minimum is an original SVG triangulated landscape with two distinct peaks, depth fade and sparse nodes.

**Build:** Create a 1440px-wide SVG with a perspective triangulated grid across the lower 600px. Displace rows into asymmetric peaks on the left and right, leaving a central valley. Draw 1px strokes in rgba(201,238,242,0.18), brighten a few near ridges to 0.4 alpha, add 1px nodes and fade the bottom with a black mask. Place Overhead atmosphere behind it, Instrument labels at the right, and opaque Proof cards in front.

### Technical diagram panels

**Use:** Capability art, resource thumbnails and a corporate split opening.

**Observed:** Dark green square or landscape panels contain fine teal rectangles, circles, ellipses, dashed orbital paths, coordinate ticks and small numerical labels. Circular dark forms have restrained rust-colored contours; low blue, olive or violet light rises from an edge. A feature illustration is 275px square, a larger capability scene 512px square, and editorial thumbnails approximately 512px by 296px.

**Transfer:** Draw an original geometric diagram related to the product's operation; a few layered shapes are preferable to an unrelated interface mockup.

**Build:** Use a dark green rounded panel with an SVG overlay: a 24px-spaced dot grid at low alpha, 1px teal rectangular frames, three concentric or offset ellipses and several dashed guide paths. Fill the central circle nearly black; outline one ring in rgba(175,79,57,0.45). Add a blurred bottom radial wash in rgba(48,203,217,0.22) plus muted olive or violet light. Keep the center legible and line contrast subordinate to text.

### Orbital closing light

**Use:** Signature closing invitation artwork.

**Observed:** The wide dark-green panel contains a sparse dot field, large dotted arcs entering from both sides, vertical coordinate annotations, a cyan-blue lower glow and a violet center rising from the bottom. Copy and the white action are centered in the clear upper-middle region.

**Transfer:** Recreate the illumination and orbital framing without requiring an existing product image.

**Build:** Clip layers to a 16px-radius panel. On deep green place a bottom-centered elliptical radial gradient with rgba(171,104,170,0.65) at its core, rgba(75,154,178,0.45) around it and transparent edges. Add a 30px-spaced 1px pale dot grid at 0.15 alpha. Overlay large dashed SVG ellipses centered beyond the left and right panel edges, plus tiny vertical labels. Keep arcs outside a clear central 464px text column.

### People photography

**Only for:** recruitment and culture stories

**Use:** Human context in editorial pairs and process panels.

**Observed:** Natural-color photographs of colleagues learning, interviewing and meeting, plus group portraits. Images use wide landscape framing, 16px rounded corners and no dramatic duotone overlay; a common split is 512px by roughly 296px next to text on black.

**Transfer:** Use authentic working scenes with bright natural interiors and varied group sizes, maintaining the simple dark-page framing.

### Dot geography

**Only for:** company reach and distributed-team stories

**Use:** A broad geographic proof illustration.

**Observed:** A 1088px-wide world map formed from small pale dots on black, with dark-green rectangular country labels. The map occupies much more space than the centered introductory copy.

**Transfer:** Use a dot-based network or geographic footprint appropriate to the new organization.

**Build:** Create an SVG silhouette sampled into a regular 8px dot grid. Use small pale circles, remove continuous outlines and float compact deep-green labels over relevant regions; preserve black negative space between landmasses.

### Icons

**Observed:** Most functional icons are simple outline SVGs with round caps: 16px, 20px or 24px, typically 2px strokes. Card continuation arrows are 18px by 12px at 1.5px. Feature category symbols combine thin stacked horizontal lines with tiny circles rather than filled pictograms.

**Transfer:** Use restrained outline arrows, chevrons, plus signs and checkmarks. For category symbols draw simple diagrammatic stacks with a single cyan or muted warm accent; keep social and partner marks monochrome where possible.

## Section recipes

How recurring sections are built.

### First screen: Luminous terrain opening

**Observed:** Sticky navigation occupies the first 110px. Below it, Overhead atmosphere extends across the viewport. A centered Display headline sits 80px into the scene, using one compact line at 48px/56px rather than filling the width. The support line follows after 8px; Primary button and Outline button sit 16px apart with 32px separation from support copy. Behind them, Wireframe terrain begins lower in the composition and fills the width; its valley frames a centered proof introduction and five monochrome marks. Instrument labels descend along the right edge. Three Proof cards start within the first 900px, while their lower content and the next capability chapter fall below the fold. Layer order is black, overhead light, terrain and markers, then live text, marks and opaque cards.

**Transfer:** For a new product, keep this centered promise over an original luminous technical field, followed by genuine proof. Without complex artwork, use the triangulated SVG terrain recipe and a concise monochrome proof strip. Dedicated product pages can replace terrain with a centered row of six technical symbols, a release eyebrow, a longer product name and one action. Pricing and recruitment use a compact overhead glow; corporate storytelling uses a left text/right diagram split.

**Avoid:** Do not turn the first screen into a huge dashboard, a flat cyan band, a white hero or a headline that overwhelms the landscape. Keep decorative mesh out of the text's readable center.

**Text style:** `display` — Plus Jakarta Sans 800 · 48px/56px · tracking -0.03125em

### Heading and support

**Observed:** Centered Heading or Heading-emphasis above Body copy, 8px apart, usually in a 640px text measure. Content follows after 64px or 80px; major chapters have 96px top and bottom spacing.

**Transfer:** Use a concise claim followed by a practical explanation; choose a left-aligned heading when introducing a resource carousel rather than centering every heading.

**Text style:** `heading` — Plus Jakarta Sans 700 · 36px/48px · tracking -1px

### Integrated capability selector

**Observed:** Feature tab list at left in a 240px region, 275px-square diagram in the middle, text at right. The overall group spans 1088px and uses 64px major gaps. Text contains Subheading, Body, green rules, muted labels and Inline links. A centered Outline button follows below.

**Transfer:** Use to explain a family of related capabilities without repeating large illustrated cards.

### Benefits beside an instrument

**Observed:** Heading-emphasis centered above a two-column composition. Four text blocks stack in one 512px column with 24px titles, 8px title/body gaps and fine green separators; a 512px-square Technical diagram panel anchors the other side.

**Transfer:** Pair concrete performance or workflow benefits with one coherent technical scene rather than one unrelated illustration per sentence.

### Resource continuation

**Observed:** A left-aligned Heading-emphasis and compact controls sit 64px above a horizontal Resource card row. Equal-height dark cards keep actions aligned at the bottom; the row can extend beyond the centered content edge.

**Transfer:** Use fresh educational or editorial material to deepen the promise without adding another sales grid.

### Detailed product chapter

**Observed:** Centered heading and support introduce either three unboxed problem columns with 80px technical thumbnails, two detailed Deep panels, or four unboxed benefit blocks arranged in two columns with 64px gaps. Detailed panels use 14px supporting copy and olive checkmarks.

**Transfer:** Move from pain to mechanism to practical benefit; reserve cards for content that genuinely needs grouping.

**Text style:** `heading-emphasis` — Plus Jakarta Sans 800 · 36px/48px · tracking -1px

### Luminous invitation and footer

**Observed:** A 1088px by 352px Deep panel sits within 72px vertical outer spacing. Orbital closing light backs centered Heading, support copy 8px below and a white Primary button after 40px. The text column is 464px wide. Dedicated product copy can use the heavier heading and 24px action gap. Pricing instead splits this into two 532px panels for sales assistance and self-service signup. All page types then enter Footer columns and finish with the identity/legal baseline and social icons.

**Transfer:** Make the final invitation a short next step in the product's language. Preserve the luminous panel and plain black footer as distinct moods; adapt one or two actions to the buying journey.

**Text style:** `heading` — Plus Jakarta Sans 700 · 36px/48px · tracking -1px

### Catalog comparison

**Only for:** pricing catalogs

**Observed:** Compact luminous opening leads into Catalog shell. A left category index accompanies repeated Category headings, three-column Price card rows and occasional Offer bands. Later chapters leave the sidebar for wide calculator art, included-benefit lists, two illustrated economic-proof panels and FAQ rows.

**Transfer:** Keep costs scannable and separate commercial assistance from individual offer details.

**Text style:** `category` — Plus Jakarta Sans 700 · 28px/36px

### Process and timeline selector

**Only for:** corporate histories and staged processes

**Observed:** A Segment track selects a step or year. The history version sits inside a 1088px by 296px Deep panel with 24px corners, a centered 20px bold statement and two cyan 40px circular controls below. Recruitment process content uses a horizontal track above a photo/text pair.

**Transfer:** Use short state labels and one active detail at a time, not an overlong vertical chronology.

### Recognition ledger

**Only for:** awards and external recognition

**Observed:** A centered Heading introduces full-width rows separated by faint dashed rules. Each row pairs a 48px cyan circular mark at left, an 18px bold recognition title, and a small year or cyan year link aligned right.

**Transfer:** Use for verified certifications or recognition when relevant; keep each row to one externally grounded item.

## Page flow

**Storyline:** Promise in a luminous technical world → credible proof → integrated capability explanation → practical benefits and deeper resources → objections where needed → luminous invitation → complete global footer.

### Platform marketing landing page

1. **Promise and social proof** — Centered luminous terrain opening, monochrome marks and quantified proof cards.
2. **Capability overview** — Vertical selector connecting related capabilities to one diagram and explanatory copy.
3. **Reasons to believe** — Benefits beside a large technical instrument panel.
4. **Deeper exploration** — Resource-card carousel.
5. **Closing call and wayfinding** — Single luminous invitation followed by five footer columns and social/legal baseline.

**Transfer:** Lead with a coherent system promise, then show how its parts work together and substantiate the benefits.

### Dedicated technical product page

1. **Product promise** — Technical symbol row, release-stage label, product-name headline, explanatory paragraph and one action.
2. **Problem framing** — Three illustrated problem columns.
3. **Mechanism** — Two detailed panels explain the integrated system.
4. **Compatibility and commercial clarity** — Olive compatibility pills, three subscription cards and a qualification strip.
5. **Social proof and benefits** — A framed quotation, four illustrated benefit blocks and adjacent-system link tiles.
6. **Objection handling** — Two columns of closed FAQ rows.
7. **Closing call and wayfinding** — Product-specific luminous invitation, then the shared footer and legal/social baseline.

**Transfer:** Use a pain-to-mechanism-to-adoption argument, explaining technical responsibilities before asking for commitment.

### Commercial catalog

1. **Commercial promise** — Compact centered glow opening with one action.
2. **Offer navigation** — Left category index and repeated three-card pricing rows interrupted by assistance banners.
3. **Cost justification** — Illustrated calculator link, included-benefit panel and paired economic-proof cards.
4. **Objection handling** — Two-column billing FAQ.
5. **Closing choices and wayfinding** — Paired assistance and self-service panels followed by the shared footer and final baseline.

**Transfer:** Separate browsing, detailed terms and decision support so price discovery stays scannable.

### Recruitment and culture

1. **Invitation and discovery** — Compact glow opening with keyword search and three illustrated role-category cards.
2. **Actionable inventory** — Filterable department disclosures with counts and location links.
3. **Working context** — Three work-mode columns, photo-led culture carousel and embedded employee video.
4. **Expectation setting** — Tabbed benefits, hiring-process selector and four photo-led preparation stories.
5. **Trust and objections** — FAQ stack, recognition ledger, employee stories and news cards.
6. **Closing call and wayfinding** — Shared luminous invitation, five-column footer and social/legal baseline.

**Transfer:** Move between actionable listings and authentic human context; use photography instead of forcing every story into technical art.

### Corporate identity and reach

1. **Mission** — Left-aligned promise beside a tall technical diagram.
2. **Context and history** — Two-column story copy, then year-selector history panel.
3. **Organizational proof** — Centered team introduction with dotted world map and location labels.
4. **Deeper exploration** — Two-column illustrated editorial destinations.
5. **Closing call and wayfinding** — Single luminous invitation followed by the complete shared footer and final baseline.

**Transfer:** Ground the mission in a story, visible reach and useful destinations rather than a wall of corporate declarations.

## Writing

Confident, practical and technically fluent. It presents integration and simplicity as concrete relief from operational work, then supports the claim with specific mechanisms and outcomes.

**Do not copy:** Do not reuse DigitalOcean names, logos, artwork, partner marks, proprietary product names, customer quotations, numerical performance claims, prices, dates or employment claims. Source examples illustrate voice only; new content needs its own substantiated facts and assets.

- **Addressing the reader:** Speak directly to builders as you; use we for responsibility and support. Name the product when precision matters rather than relying on vague platform language.
- **Rhythm:** Short sentence-case headlines, a concise supporting paragraph, then crisp benefit fragments. Longer technical explanations use plain sentences; repeated short clauses and occasional em dashes create momentum.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A compact category promise or direct benefit, not a lyrical slogan. | 2–5 words for broad openings | “AI-Native Cloud”<br>“Simple, predictable pricing” |
| Chapter heading | A decisive assertion that joins capability with openness, simplicity or operational value. | 5–10 words | “Built for agents. Open at every layer.”<br>“Performance, economics, and simplicity — together.” |
| Support line | Explain what is integrated and why that matters as usage grows. | One sentence or a short paragraph | “One integrated platform, silicon to agent, with economics that improve as you scale.” |
| Benefit explanation | Concrete operational relief, often expressed as parallel short clauses. | Two to four short sentences | “One CLI. One API. One bill. Migrate in one line of code, and leave on the same terms.” |
| Action | Plain verb plus destination or task. | 1–4 words | “Get started”<br>“View case study”<br>“We'll do the math” |
| Closing invitation | Immediate building language followed by a clear division of responsibility. | Short headline and one sentence | “Start building today”<br>“Bring the harness and model you already use. We'll handle the runtime.” |

**Words and phrasing to use:** build; run; deploy; scale; open; integrated; one stack; no lock-in; production; your code; one bill

**Avoid:** magical; revolutionary without proof; limitless possibilities; enterprise jargon without a mechanism; cute technical puns in primary sales copy

**Rules:**

- Explain the work the reader no longer has to do, then name the mechanism that removes it.
- Place a measured outcome next to the workload and context it describes.
- Expand technical detail in body copy while keeping the headline readable without domain expertise.
- Use parallel clauses sparingly to make integration tangible.
- Keep employment copy more human and conversational than infrastructure copy.

## Do's and Don'ts

### Do

- Keep the primary headline at 48px/56px and weight 800 rather than inflating its scale.
- Use #000f0f panels on #000000 with faint 10% soft-white edges.
- Keep main actions 40px high and fully rounded, with 16px/24px medium labels.
- Use 24px gaps for three-card grids and 64px for editorial pairs.
- Carry the 8px heading-to-support relationship through the page.
- Give diagram art fine strokes, low-contrast dots and a dark central field.
- Preserve the luminous closing invitation before the black footer.
- Align repeated card actions at the bottom even when titles wrap.

### Don't

- Do not replace the geometric display family with a monospace headline; mono belongs at 10px in instrumentation.
- Do not use pure white as the standard paragraph color; use green white #e5eceb.
- Do not turn every card cyan; cyan is primarily a control and link accent.
- Do not give all sections colored backgrounds; the black canvas must remain visually continuous.
- Do not use heavy soft drop shadows to lift panels; delineate them with inset edges.
- Do not make footer links 16px bold like navigation; keep the links 14px/20px regular.
- Do not spread headline-style negative tracking into 14px metadata or 16px body copy.
- Do not use the olive compatibility pills as the default primary button treatment.

## Motion and responsive

### Motion

**Observed:**

- Declared button and tab transitions use background or background-color and color at 300ms ease-in-out.
- Navigation chevrons declare transform 300ms ease-in-out.
- Carousel and tab content have declared reveal and progress animations; a 30s linear infinite animation is also declared.

**Transfer:**

- Keep capsule color changes at the declared 300ms pace; scene decoration must not compete with live copy.
- Use clear active capsules and progress indicators for changing capability or culture content.

**Unknown:**

- Exact terrain animation, carousel autoplay timing and the purpose of every declared keyframe are not established.

### Responsive

**Observed:**

- Declared styles include width breakpoints at 500px, 520px, 604px, 719px, 768px, 1024px, 1280px and 1440px; additional page-specific thresholds also exist.

**Transfer:**

- Recommended adaptation: stack editorial pairs and three-card rows while retaining the dark framing and 16px card corners.
- Recommended adaptation: let capability selectors scroll horizontally on narrow screens, keep the active cyan capsule visible, and simplify rather than remove the wireframe scene.
- Recommended adaptation: keep the closing panel's text clear by pushing orbital arcs toward the edges and allowing its height to grow.

**Unknown:**

- Exact mobile type sizes, navigation collapse behavior and breakpoint-specific spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
