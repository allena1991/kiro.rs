# Evernote — paper with playful sparks

## Overview

A warm, practical software style that makes digital work feel tangible and approachable. Cream paper surfaces, tightly fitted humanist sans headings, small candy-colored labels and layered interface collages balance usefulness with personality. The default is light and spacious, with occasional charcoal interludes; a fully dark feature-launch variant adds luminous edge artwork.

### Essentials

- Friendly headlines are tightly packed rather than oversized billboards: Figtree 600 at 72px/1 with -0.05em tracking for the opening, and 50px/1.1 with -0.05em tracking for capability chapters.
- A cream product stage leads the page: a centered promise and support line sit above a single black action, followed by a large white interface object; the 1320px stage has 16px corners and a fine #e7e7e7 outline.
- Color behaves like a highlighter, not wall paint: #f9f6f2 and #f4eee5 dominate; pink, orange, yellow and lime occupy small 29px-high category pills and illustration details. Include these small colorful chapter markers on new landing pages.
- Buttons are compact rectangles, not capsules: 5px corners, black fill, white semibold labels; opening actions use 16px 40px padding while chapter actions use 10px 24px. Lime reverses the hierarchy on charcoal.
- Product imagery is a paper collage: a large interface or real-life photograph is layered with smaller white UI fragments, subtle baked-in shadows and occasional tilted paper. Include a layered proof scene; if photography is unavailable, use a convincing product screen with two contextual detail cards.
- Oversized pale geometric cutouts give the cream chapters a playful second layer: approximately 472px starbursts, scallops or quarter-circle forms sit behind the collage and clip into panel corners. Include this device rather than leaving every panel undecorated.
- A charcoal announcement interrupts the paper rhythm: centered 50px white heading, 20px support and a lime action, with soft colored shapes at the outer edges and a clear center. Carry this contrast device into new landing pages without turning the whole default page dark.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lime highlighter | `#94e130` | `--color-lime` | accent, action, surface | Small category pills and dark-section calls to action. |
| Action green | `#00a82d` | `--color-green` | action, link, accent | Declared action hover color, affirmative marks and small identity accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Yellow highlighter | `#ffd919` | `--color-yellow` | accent, surface | Short category markers and small collage shapes. |
| Orange highlighter | `#ffa24d` | `--color-orange` | accent, surface | Short category markers and small collage shapes. |
| Pink highlighter | `#fad0f6` | `--color-pink` | accent, surface | Short category markers and small collage details. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#141414` | `--color-ink` | text, action, background | Primary headings, black actions and the full dark-theme canvas. |
| Charcoal text | `#262626` | `--color-body` | text, surface | Introductory text and dark raised panels; also the charcoal announcement backing. |
| Warm gray text | `#4e4d4c` | `--color-muted` | text | Descriptions within light feature cards and tertiary text. |
| Quiet gray | `#737373` | `--color-fine-print` | text | Footer utility text. |
| Control outline | `#a1a1a1` | `--color-control-edge` | border | Outline buttons, carousel controls and light FAQ rules. |
| Navigation rule | `#d9d9d9` | `--color-navigation-rule` | border | Light-theme header divider. |
| Panel edge | `#e7e7e7` | `--color-edge` | border | Faint outlines on cream panels and pricing groups. |
| Cream inset | `#f4eee5` | `--color-panel` | surface, background | Hero stage, capability panels and selected promotional bands. |
| Warm paper | `#f9f6f2` | `--color-canvas` | background | Default page, navigation and footer canvas; also pale decorative cutouts. |
| Soft white | `#fdfcfc` | `--color-reverse-copy` | text | Supporting text on charcoal sections. |
| White paper | `#ffffff` | `--color-white` | surface, text | Feature cards, interface artwork and reversed headings or button labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Lavender marker | `#d9b6fd` | `--color-purple` | accent, surface | Business-tier badge. |
| pricing pages | Table gray | `#666666` | `--color-table-muted` | text | Comparison labels and explanatory text. |
| pricing pages | Table rule | `#e6e6e6` | `--color-table-rule` | border | Thin horizontal separators in the comparison matrix. |
| dark feature launches | Dark card copy | `#f3f2f1` | `--color-dark-secondary-copy` | text | Descriptions in dark feature cards. |

## Typography

- **Figtree** — Headings, navigation, chapter copy, badges and action labels. Open, rounded humanist sans with a compact, friendly display silhouette. Font stack: "Figtree", Arial, sans-serif.
- **Inter** — Introductory support, feature-card descriptions and footer links. Neutral, crisp sans that lends smaller information a utilitarian cadence. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Figtree | 600 | 72px | 1 | -0.05em | Centered opening promise and selected closing overview headings. |
| heading | Figtree | 600 | 50px | 1.1 | -0.05em | Primary chapter headings, centered section leads and price numerals. |
| heading-small | Figtree | 600 | 40px | 1.1 | -0.03em | Compact conversion section headings. |
| card-heading | Figtree | 600 | 24px | 1.1 | normal | Feature and download card titles. |
| label-large | Figtree | 600 | 20px | 1.3 | normal | Opening action labels, footer group headings and FAQ questions. |
| intro | Inter | 400 | 20px | 1.5 | -0.05em | Centered opening support and selected section introductions. |
| support | Inter | 400 | 20px | 1.5 | normal | Announcement and tool-promotion support paragraphs. |
| body | Figtree | 400 | 18px | 1.6 | 0.01em | Capability chapter descriptions and account prompts. |
| detail | Inter | 400 | 16px | 1.3 | normal | Feature-card descriptions, footer links and FAQ answers. |
| body-small | Figtree | 400 | 16px | 1.4 | normal | Download-card and overview-grid descriptions. |
| label | Figtree | 600 | 16px | 1.3 | normal | Chapter markers and compact action labels. |
| navigation | Figtree | 500 | 16px | 1.5 | normal | Header navigation labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| business and benefits pages | proof-heading | Figtree | 500 | 30px | 1.1 | -0.03em | Social-proof lead and testimonial quotation. |
| business and benefits pages | overview-title | Figtree | 600 | 18px | 1.4 | 0.01em | Unboxed overview-grid titles. |
| pricing pages | table-label | Figtree | 600 | 15px | 1.5 | normal | Comparison row labels. |
| pricing pages | table-value | Figtree | 400 | 15px | 1.5 | normal | Centered comparison values. |

**Notes:**

- Keep the display and chapter heading tracking equally tight at -0.05em; do not carry it into card titles or labels.
- The 18px chapter copy is Figtree with slightly positive tracking; the centered 20px introductory voice is Inter. These are distinct roles rather than one universal body style.
- Use sentence case throughout. The compact uppercase recommendation badge is a pricing-specific exception.
- Headings reverse to white without changing their size or weight in the dark variant.

## Layout

**Density:** Airy at section scale, useful and compact within cards; large cream panels surround narrow text columns and substantial visual collages.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card title to description and tight icon/text relationships. |
| 12px | Stacked download actions and small internal lists. |
| 16px | Chapter marker to heading and heading to body; regular flex gaps. |
| 24px | Opening headline to support, carousel card separation and FAQ trigger vertical padding. |
| 32px | Feature-card padding and announcement headline-to-support gap. |
| 40px | Body-to-action space, panel outer margins and conversion heading-to-card space. |
| 48px | Compact conversion section padding and logo-strip separation. |
| 64px | Footer and overview-section vertical padding; FAQ heading-to-list separation. |
| 80px | Inset capability-panel padding and FAQ section vertical padding. |
| 120px | Larger feature-overview and testimonial section breathing room. |
| 144px | Centered announcement content vertical padding. |
| 192px | Footer gap between link directory and final legal row. |

### Containers and grids

- **wide-container**: max width 1320px · side padding 20px. Centered desktop wrapper for navigation, footer, pricing and wide promotional sections; 60px outside margins at a 1440px viewport.
- **chapter-container**: max width 1024px. Capability content inside an approximately 1186px-wide cream panel. Illustration occupies about 640px while the text is a narrow 348px column with 36px separation padding.
- **hero-copy**: max width 820px. Centered headline block in the opening stage.
- **support-measure**: max width 672px. Centered support paragraphs, generally two lines.
- **conversion-grid**: max width 1024px · 3 columns · gap 24px. Three white download or access cards underneath a centered compact heading.
- **overview-grid** (only for business and benefits pages): max width 1320px · 4 columns · gap 80px. Unboxed icon-led cells with 56px row gaps.
- **pricing-groups** (only for pricing pages): max width 1320px · 2 columns · gap 16px. Two audience containers, each subdivided into two tier columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 5px |
|  | feature-cards | 10px |
|  | inset-panels | 16px |
|  | category-markers | 52px |
|  | carousel-controls | 50% |
| pricing pages | billing-toggle | 100px |
| business pages | use-case-tabs | 48px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default landing-page background.

**CSS:** `background: #f9f6f2`

**Observed:** Warm, flat and opaque; no texture or raised page chrome.

**Transfer:** Let this neutral occupy most of a new page.

#### Cream stage · level 1

**Use:** Opening stage and recurring inset capability panels.

**CSS:** `background: #f4eee5; border: 1px solid #e7e7e7; border-radius: 16px; box-shadow: none; overflow: hidden`

**Observed:** Large panels are differentiated by tone and edge, not elevation.

**Transfer:** Place the product collage and text together inside the same surface.

#### White utility card · level 1

**Use:** Feature carousel and access/download cards.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 32px; box-shadow: none`

**Observed:** Simple white rectangles sit directly on paper.

**Transfer:** Keep exterior treatment restrained even when the image within is layered.

#### Charcoal announcement · level 0

**Use:** High-contrast promotional interlude.

**CSS:** `background: #262626; border-top: 1px solid #141414; border-bottom: 1px solid #141414`

**Observed:** Full-width dark band with softly blurred colored artwork at its edges.

**Transfer:** Keep the center clear for white copy and the Lime button.

#### Dark canvas · level 0

**Only for:** dark feature launches

**Use:** Full-page inverted product-launch presentation, including navigation and footer.

**CSS:** `background: #141414; color: #ffffff`

**Observed:** Warm cream is replaced with near-black; the geometry and typography remain related to the light system.

**Transfer:** Use as a complete page-level variant rather than randomly darkening individual utility cards.

#### Dark raised panel · level 1

**Only for:** dark feature launches

**Use:** Capability collages and feature cards.

**CSS:** `background: #262626; border: 1px solid rgba(255,255,255,0.2); border-radius: 16px; box-shadow: none`

**Observed:** Large panels use 16px corners; small cards use 10px corners.

**Transfer:** Preserve light interface objects against the charcoal backing.

## Components

### Primary button

**Use:** Opening conversion action.

**CSS:** `background: #141414; color: #ffffff; border-radius: 5px; padding: 16px 40px; min-width: 250px; text-align: center`

**Text style:** `label-large` — Figtree 600 · 20px/1.3

**Observed:** A single centered rectangle carries the primary opening action; the surrounding content does not compete with a second filled CTA.

**States:** Declared: hover background-color rgb(0 168 45/1), transform remains identity; focus-visible unknown.

### Compact button

**Use:** Capability and tool-section conversion.

**CSS:** `background: #141414; color: #ffffff; border-radius: 5px; padding: 10px 24px; min-width: 200px; text-align: center`

**Text style:** `label` — Figtree 600 · 16px/1.3

**Observed:** Placed below the descriptive paragraph. A 151px-wide version belongs in the header.

**States:** Declared: hover background-color rgb(0 168 45/1), transform remains identity; focus-visible unknown.

### Outline button

**Use:** Downloads and secondary conversion choices.

**CSS:** `background: transparent; color: #141414; border: 1px solid #a1a1a1; border-radius: 5px; padding: 10px 24px; text-align: center`

**Text style:** `label` — Figtree 600 · 16px/1.3

**Observed:** Download cards stretch these across the content width and add a platform icon before the label; pricing choices use the same construction.

**States:** Declared: hover background-color rgb(20 20 20/1); label reverses to white; focus-visible unknown.

### Lime button

**Use:** Primary conversion on the Charcoal announcement.

**CSS:** `background: #94e130; color: #141414; border-radius: 5px; padding: 16px 40px; min-width: 250px; text-align: center`

**Text style:** `label-large` — Figtree 600 · 20px/1.3

**Observed:** The dark feature-launch variant also uses this color for its compact header and chapter actions.

**States:** Declared: hover background-color rgb(0 168 45/1); focus-visible unknown.

### Fixed navigation

**Use:** Persistent site orientation and conversion.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 81px; z-index: 50; background: #f9f6f2; border-bottom: 1px solid #d9d9d9`

**Text style:** `navigation` — Figtree 500 · 16px/1.5

**Observed:** Brand mark left, compact topical navigation in the middle, then plain login, outline download and black signup at right. Inner content uses the wide container. Dark launch pages reverse text, darken the backing and use lime signup.

**Transfer:** Use a compact product identity and a small set of product-oriented destinations, keeping conversion actions distinct.

### Category marker

**Use:** Small colored chapter eyebrow.

**CSS:** `background: #fad0f6; color: #141414; border-radius: 52px; padding: 4px 12px; width: fit-content; margin-bottom: 16px`

**Text style:** `label` — Figtree 600 · 16px/1.3

**Observed:** Pink, orange, yellow and lime distinguish successive chapters. Labels remain sentence case and fit their content.

**Transfer:** Name the capability with one or two plain words; do not add a badge container around an entire paragraph.

### Feature card

**Use:** Horizontal capability browsing.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 32px; width: 300px; display: flex; flex-direction: column; box-shadow: none`

**Text style:** `card-heading` — Figtree 600 · 24px/1.1

**Observed:** A colorful pictogram sits above the title and detail paragraph. Cards sit in a horizontally overflowing rail with 24px separation and two centered circular arrow controls below. Cards are 271px tall for short copy and grow with longer descriptions.

**Transfer:** Show a few concise capabilities with enough overflow to imply continuation.

### Footer directory

**Use:** Shared page ending.

**CSS:** `background: #f9f6f2; padding: 64px 20px`

**Text style:** `detail` — Inter 400 · 16px/1.3

**Observed:** A top row combines compact identity, language selector and social icons. Four link columns follow, with 20px semibold headings and 28px spacing between link rows. A generous 192px gap precedes the subdued legal and privacy row. Dark launch pages preserve the full directory on near-black.

**Transfer:** End with practical destinations and utility links, not a second visual hero.

### FAQ row

**Only for:** pricing and dark feature-launch pages

**Use:** Expandable objection handling.

**CSS:** `border-bottom: 1px solid #a1a1a1; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `label-large` — Figtree 600 · 20px/1.3

**Observed:** The collapsed trigger has 24px vertical padding, a left-aligned question and a green plus aligned at the far right. Answers use Detail; dark rows use a 40% white bottom rule. The list spans the wide container.

**Transfer:** Keep questions short enough to scan without turning them into cards.

### Pricing audience group

**Only for:** pricing pages

**Use:** Group related tiers by buyer type.

**CSS:** `background: #f4eee5; border: 1px solid #a1a1a1; border-radius: 16px; overflow: hidden`

**Text style:** `card-heading` — Figtree 600 · 24px/1.1

**Observed:** A full-width group heading and divider sit above two internal tier columns, each with a colored name pill, prominent price or sales phrase, short description, aligned action and checkmarked feature list. The individual-buyer group uses a transparent fill and lighter edge. A free tier is a separate horizontal strip underneath.

**Transfer:** Use the dark action only for the favored self-serve tier, and outline actions for neighboring tiers.

### Timeline step card

**Only for:** business onboarding pages

**Use:** Concrete short-horizon adoption proof.

**CSS:** `border: 1px solid #141414; border-radius: 16px; padding: 24px; width: 300px; display: flex; flex-direction: column; gap: 12px`

**Observed:** Three outlined cards hang beneath a dotted horizontal timeline. Small rounded time labels above the line and scattered colored geometric pieces make the sequence feel lightweight.

**Transfer:** Use a few realistic milestones and checkmarked outcomes; keep the timeline a distinct illustrated proof block.

## Imagery and graphics

### Layered product proof

**Use:** Hero and major capability chapters.

**Observed:** White note windows, lists, search results, task fragments and status chips overlap lifestyle photographs or tangible paper artifacts. Photos show people working, travel, food and real environments, with natural or lightly colored light. The opening object sits below the centered CTA; chapter collages take more width than the text and occupy roughly a 640px-wide art area. Rounded photos may tilt slightly while the main UI stays legible.

**Transfer:** Use your own product interface with a relevant real-world object or person. The minimum equivalent is one legible product screen, a secondary detail card and a small status chip; retain their layered white-paper treatment.

**Build:** Compose a transparent SVG or positioned image group about 640px wide: a rounded photo or document plane behind, a white primary UI plane in front and two smaller detail fragments offset across its edges. Keep tilt to the backing object. Use gentle internal artwork shadows while leaving the outer marketing panel flat.

### Pale corner geometry

**Use:** Required decorative layer inside cream capability panels.

**Observed:** Large nearly paper-white starbursts, scalloped blocks and circular cutouts sit behind the main collage, often clipped by the upper corner of the cream stage. They are low contrast and never cross the text.

**Transfer:** Keep the motif abstract and content-independent, shifting its side along with the collage.

**Build:** Use a 472px SVG at an upper panel corner behind content. Fill with the canvas color against the cream panel. Construct a sunburst from repeated radial rectangles, or subtract circles from a square to make a scalloped block. Clip at the panel boundary and do not outline it.

### Soft edge color forms

**Use:** Required atmosphere for the dark announcement device; also expanded on dark launch pages.

**Observed:** Blurred green-to-blue forms intrude from the left, with violet and pink rounded forms on the right. The dark center stays broad and readable; these are soft abstract silhouettes, not a full-screen rainbow gradient.

**Transfer:** Recreate a restrained pair of peripheral forms; the exact gradient stops are not essential.

**Build:** Place an irregular lime polygon off the left edge and a tall rotated lavender ellipse off the right edge behind all copy. Layer translucent blue and pink regions inside the forms, blur their edges by roughly 24px, and fade them toward the dark center with an alpha mask. Keep most of the band dark.

### Illustrated interface boards

**Only for:** business pages

**Use:** Team-oriented capability scenes and use-case tabs.

**Observed:** Large white app boards have thin black contours, rounded corners and a slightly offset dark edge. Floating cursor labels, avatar notices and simple green, orange and purple geometric pieces surround the board. These are diagrammatic scenes rather than photographic collages.

**Transfer:** Draw a simplified but credible interface for the new product and add only the few collaboration or status details needed to prove the chapter.

### Typographic feature film

**Only for:** dark feature-launch openings

**Use:** Media-first hero alternative.

**Observed:** A 1240px by 698px rounded video stage fills most of the first screen on near-black. The visible film has a white field, bold black phrase and vertically arranged colored words; it is designed motion content rather than a static empty media panel.

**Transfer:** Create a short benefit-led typographic product film or a fully composed poster using your own terms, retaining the simple white stage and black-plus-highlight palette.

**Build:** Use a 16:9 white stage with 16px corners, a fixed black lead phrase and a clipped vertical stack of colored benefit nouns beside it. Center the composition and keep the phrase readable even when motion is stopped.

### Icons

**Observed:** Utility SVGs are mostly filled at 16px, 20px or 24px; carousel arrows use a finer directional treatment inside 56px circles. Large capability pictograms are colorful and simple, commonly 48px to 64px, mixing rounded filled silhouettes with open symbols.

**Transfer:** Choose friendly pictograms with simple recognisable silhouettes. Use small monochrome icons for actions and navigation, and colorful larger symbols for capabilities; do not substitute a uniform technical hairline icon set everywhere.

## Section recipes

How recurring sections are built.

### First screen: Cream product-stage opening

**Observed:** The fixed navigation sits above a cream stage that spans 1320px with 60px desktop side margins. The stage begins directly below the 81px header. Back to front: paper page, Cream stage, centered text and actions, then a large white product scene below. The 72px display headline fits an 820px measure, followed after 24px by a two-line 20px Inter support paragraph within 672px. A Primary button follows about 40px later, then a small account/login prompt. Within the first 900px, the full headline, support, CTA and login are visible, followed by the upper part of the centered interface scene. The product art begins in the lower half of the viewport and continues below the fold; the stage itself also ends below it.

**Transfer:** Lead with one short product promise, one support sentence and one action. Use a credible product board instead of source-specific artwork, keeping the lower-half visual reveal. Business openings allow a two-line promise and omit the login prompt; pricing opens directly on paper with a decision question and billing control; dark launches open with the Typographic feature film.

**Avoid:** Do not turn the default first screen into a split-screen portrait hero, place a huge eyebrow above the promise, or squeeze the whole product visual above the fold.

**Text style:** `display` — Figtree 600 · 72px/1 · tracking -0.05em

### Centered overview and carousel

**Observed:** A centered Heading and Intro establish the benefit, with 40px separation. Below, Feature cards extend past the viewport edges, followed by two circular arrow controls. The section uses generous 120px upper and 170px lower padding.

**Transfer:** Use the rail for a browsable set of distinct capabilities rather than a dense feature checklist.

**Text style:** `heading` — Figtree 600 · 50px/1.1 · tracking -0.05em

### Dark promotional interlude

**Observed:** Charcoal announcement with Soft edge color forms, centered Heading, Support after 32px and Lime button after 40px. The centered content has 144px vertical padding and a roughly 775px maximum measure.

**Transfer:** Use for a consequential release, stronger promise or related product invitation. Keep the message compact.

**Text style:** `heading` — Figtree 600 · 50px/1.1 · tracking -0.05em

### Alternating collage chapter

**Observed:** Cream stage contains a 1024px content row with a broad Layered product proof scene and narrow text column. Category marker, Heading and Body stack with 16px gaps; Compact button sits 40px below copy. Panel padding is 80px and outer margins 40px. Pale corner geometry sits behind the art. Neighboring chapters alternate the art side.

**Transfer:** Give each chapter one clear outcome and one proof scene; vary the art instead of adding more text.

**Text style:** `heading` — Figtree 600 · 50px/1.1 · tracking -0.05em

### Tool invitation band

**Observed:** A full-width cream band centers a Heading, Support and Compact button with 24px gaps. A wide interface scene anchors the lower edge, partially meeting the section boundary.

**Transfer:** Offer a low-friction way to experience the product, using a wide tool preview rather than another feature collage.

**Text style:** `heading` — Figtree 600 · 50px/1.1 · tracking -0.05em

### Access-card closing

**Observed:** A 40px compact heading sits above three White utility cards in the conversion grid. Each card orders platform pictogram, 24px title, short description and access/download actions. Cards use 32px padding; actions stack with 12px gaps. The Footer directory follows on the same paper canvas.

**Transfer:** Close a general landing page with concrete ways to start, install or access the product rather than an unrelated final slogan.

**Text style:** `heading-small` — Figtree 600 · 40px/1.1 · tracking -0.03em

### Audience pricing and comparison

**Only for:** pricing pages

**Observed:** A centered 72px decision headline and 20px support lead to a centered capsule billing toggle. Pricing audience groups show two internal tiers each; a free strip follows. A 50px comparison heading precedes a matrix with a 370px label column and five 190px value columns. The plan/action header remains visible while scrolling; rows use fine rules, gray labels and green checks. FAQ rows and Footer directory form the ending.

**Transfer:** Separate quick buyer decisions from exhaustive comparison. Keep price numerals in the same Heading recipe as capability leads.

**Text style:** `display` — Figtree 600 · 72px/1 · tracking -0.05em

### Business proof and adoption

**Only for:** business pages

**Observed:** A 30px medium proof statement sits above four customer logos. Later, Timeline step cards make adoption tangible. A use-case section has outlined capsule tabs above an interface-and-copy split; the active tab has a dark outline and faint ink wash.

**Transfer:** Use genuine proof and a concrete adoption horizon for the new product. Preserve the timeline's small graphic moments instead of converting it into a heavy process dashboard.

**Text style:** `proof-heading` — Figtree 500 · 30px/1.1 · tracking -0.03em

### Testimonial pause

**Only for:** benefits pages

**Observed:** A large quotation-mark graphic sits beside a 30px medium quotation, with a 20px semibold attribution below after 40px. The paper section uses 120px vertical padding.

**Transfer:** Use one human, specific quotation as a pause between feature chapters and the final overview.

**Text style:** `proof-heading` — Figtree 500 · 30px/1.1 · tracking -0.03em

### Unboxed overview closing

**Only for:** business and benefits pages

**Observed:** A centered Display heading opens a four-column, two-row overview with 80px horizontal and 56px vertical gaps. Colorful 64px pictograms lead 18px semibold titles and short Body-small descriptions. The business version adds a centered Primary button; both lead to Footer directory.

**Transfer:** Summarize useful situations or adjacent capabilities without card borders or a new visual theme.

**Text style:** `display` — Figtree 600 · 72px/1 · tracking -0.05em

### Dark capability launch

**Only for:** dark feature launches

**Observed:** Dark canvas supports a media-first opening, a centered Heading and three compact dark feature cards. Subsequent Dark raised panels retain the split collage structure and lime compact actions. A smaller 40px lead introduces an asymmetric card group: one tall card next to two short stacked cards. A soft-edge graphic trust band, further chapters and FAQ rows precede the inverted Footer directory.

**Transfer:** Carry the familiar panel rhythm into a concentrated launch story. Make darker panels and lighter interface artwork do the separation, not neon outlines.

**Text style:** `heading` — Figtree 600 · 50px/1.1 · tracking -0.05em

## Page flow

**Storyline:** promise → approachable product proof → capability overview → focused benefit chapters and invitations → practical next steps or objection handling → directory footer

### General product landing page

1. **promise** — Centered cream product stage with short headline, support, conversion and large interface reveal.
2. **capability overview** — Overflowing icon-card rail.
3. **announcement** — Full-width charcoal contrast band.
4. **capability chapters** — Alternating cream collage panels, interrupted by a tool invitation.
5. **closing conversion** — Three platform/access cards.
6. **navigation ending** — Full directory, language and social row, then separated legal utilities.

**Transfer:** Use the light paper version as the default, choosing the most persuasive capabilities and a practical access ending.

### Plan selection and detailed comparison

1. **decision framing** — Question headline, support and billing cadence toggle.
2. **pricing** — Audience groups, colored tier names, prices and aligned actions; free strip below.
3. **comparison** — Long ruled matrix with persistent plan-action header.
4. **objection handling** — Fine-print strip and collapsed FAQ list.
5. **navigation ending** — Shared light directory footer.

**Transfer:** Keep the fast decision layer separate from the detailed matrix and end with answers rather than a forced closing hero.

### Business adoption and trust

1. **promise** — Cream hero with team-oriented interface collage and single action.
2. **social proof** — Medium-sized proof statement and logo strip.
3. **sales invitation** — Centered cream promotional band with colorful peripheral shapes.
4. **capability proof** — Three concise icon benefits followed by large illustrated interface chapters.
5. **adoption proof** — Lightweight milestone timeline and outlined step cards.
6. **use-case depth** — Capsule tabs, explanatory list and large interface board.
7. **closing conversion** — Unboxed capability grid with centered action.
8. **navigation ending** — Shared light directory footer.

**Transfer:** Use actual organizational proof, specific adoption steps and reassuring capability detail.

### Benefits and product-fit explanation

1. **promise** — Cream product-stage opening.
2. **overview** — Longer descriptive capability carousel and dark announcement.
3. **benefit proof** — Alternating cream photo-and-interface chapters.
4. **social proof** — Single quotation pause.
5. **closing overview** — Large heading and unboxed icon-led use-case grid.
6. **navigation ending** — Shared light directory footer without another conversion band.

**Transfer:** Make the reader recognize everyday situations, then finish with breadth rather than adding more sales pressure.

### Feature launch

1. **demonstration opening** — Large typographic video stage on near-black.
2. **promise and overview** — Centered heading and three dark cards.
3. **capability depth** — Raised charcoal collage panel and asymmetric function cards.
4. **trust** — Soft edge artwork behind a centered promise and four compact cards.
5. **capability chapters** — Further interface-and-copy splits with lime actions.
6. **objection handling** — Four collapsed FAQ rows.
7. **navigation ending** — Complete directory footer in the dark theme.

**Transfer:** Use the dark theme for a focused launch narrative, retaining typography, corners, panel scale and utility ending.

## Writing

Helpful, optimistic and direct. Strong benefits are expressed in everyday language, then backed by specific product behaviors rather than abstract technical bravado.

**Do not copy:** Do not reuse the Evernote name, elephant identity, second-brain positioning, named partner relationships, customer logos, customer counts, prices, product claims or testimonial wording. Use original product facts and claims that can be supported. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Refer to the product by name when clarifying a behavior; use we sparingly for reassurance or policy.
- **Rhythm:** Short sentence-case headlines, usually a few words; one explanatory sentence or two compact clauses underneath. Chapter text can be longer when explaining business controls. Actions are direct verb phrases, not slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact, memorable description of the value. | 3–9 words | “Your second brain” |
| Chapter heading | Lead with an outcome or remove a familiar frustration. | 4–8 words | “Bring order to everything you do”<br>“Find what you need, fast”<br>“Hit every deadline” |
| Supporting line | Connect a practical task to the convenience the product provides. | One sentence, about 15–30 words | “Remember everything and tackle any project with your notes, tasks, and schedule all in one place.” |
| Category marker | A plain capability name or short verb. | 1–2 words | “Organize”<br>“Instant Sync” |
| Action | Name the immediate next step and, when true, reduce commitment. | 3–5 words | “Try it for free”<br>“Contact our team”<br>“Sign up for updates” |
| Objection handling | Use the exact question a reader would ask; answer plainly. | One short question | “Can I opt out of AI features?” |

**Words and phrasing to use:** simple; flexible; keep; find; save; your; all in one place; stay focused; ready to help

**Avoid:** paradigm shift; synergize; unprecedented disruption; best-in-class without proof; long strings of technical nouns

**Rules:**

- Pair each benefit headline with a concrete behavior or useful example.
- Use em dashes to join related thoughts, not to decorate every sentence.
- Keep category labels shorter than the headline.
- Explain technical terms when they matter to a buyer; do not use them as the emotional opening.
- Make reassurance specific, especially around privacy, permissions and billing.

## Do's and Don'ts

### Do

- Use 72px/1 Figtree 600 for the default opening and 50px/1.1 for chapters.
- Keep chapter headings and display tracking at -0.05em.
- Use 16px corners for cream stages and 10px corners for small white cards.
- Keep a narrow 348px chapter text column beside a wider visual.
- Place chapter CTAs about 40px below the descriptive copy.
- Give feature cards 32px internal padding and space rail cards by 24px.
- Keep the footer spacious, with four directory columns and a distinct low-contrast utility row.
- Use small colored pills and pale geometric cutouts to bring personality to the neutral canvas.

### Don't

- Do not make all buttons pill-shaped; reserve capsule shapes for markers, tabs and billing controls.
- Do not replace the cream canvas with pure white across the whole page.
- Do not apply heavy drop shadows to marketing panels; their separation comes from tone and a 1px edge.
- Do not turn every capability into a neon or fully saturated background section.
- Do not set all prose in one font and tracking recipe; 18px chapter prose and 20px intro prose have different constructions.
- Do not remove white UI planes from dark collages in favor of dark-on-dark dashboard art.
- Do not outline the unboxed final overview cells as pricing cards.
- Do not make the entire footer a compressed legal bar; its directory is a substantial ending.

## Motion and responsive

### Motion

**Observed:**

- Action transitions declare all 0.15s cubic-bezier(0.4,0,0.2,1). Navigation and footer links declare all 0.2s with the same easing; feature cards declare 0.3s.
- Filled actions change to green on hover without a transform offset. Outline actions darken and reverse their labels.
- The feature-launch opening uses a typographic video; carousel arrow controls are visible.

**Transfer:**

- Use color changes rather than button lifts to convey action feedback.
- Keep film motion confined to the opening media stage rather than animating the whole page canvas.

**Unknown:**

- Exact video sequence and timing, carousel autoplay behavior, scroll choreography and focus-visible styling are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 768px, 1024px and 1280px.
- Capability rows declare a column layout before their desktop split; overview grids declare two columns before four.
- Feature rail cards declare 70vw width before 300px desktop cards. Pricing comparison declares horizontal overflow below its desktop layout.

**Transfer:**

- On narrow screens, keep the centered promise above the product scene and reduce panel padding rather than pushing the scene beside the copy.
- Stack collage chapters, retain pale corner geometry behind the art and keep the text out of its overlap zone.
- Preserve the comparison table's column structure with horizontal scrolling; do not shrink its text into unreadability.

**Unknown:**

- Exact mobile headline sizes, navigation drawer construction and breakpoint-specific final positions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
