# Whop — ambition made tangible

## Overview

An expansive, operator-minded style that puts everyday enterprise on a cinematic stage, then makes software feel tangible through pale interface objects and tactile controls. White and black dominate, with hot orange-red reserved for action and occasional emphasis; regular grotesk headlines contrast with practical sans-serif explanations. It suits ambitious platforms and product ecosystems, balancing low-density storytelling with concrete demonstrations.

### Essentials

- Cinematic promise, practical follow-through: a full 900px dark photographic opening carries a lower-left 96px/90px regular grotesk headline, a 28px support line and one 300×64px orange action before switching to white product chapters.
- Headlines are broad, not heavy: Acid Grotesk 400 at 72px/80px with -0.035em tracking for major chapters; 48px/58px with -0.028em tracking for split explanations.
- Actions have a physical lip: orange-red #fa4616 faces, #b62600 1px edges and a 3px solid bottom shadow; 16px corners on the opening action and 10px on 52px-high chapter actions.
- Color is concentrated into tools and calls to action: neutral canvases occupy most of the page, orange-red marks conversion, and stronger blues or greens live inside product illustrations rather than marketing bands.
- Software becomes a staged object: white interface fragments float over near-white panels with 1px translucent-black edges, soft downward shadows and lower-edge fades; use a faithful simplified interface when no polished artwork exists.
- Proof has a distinctive silhouette: include a wide media fan with a 826×464px active panel and progressively narrower neighboring previews, plus a monumental closing statement beside photography fading into white. A single real outcome image and layered previews provide the minimum equivalent.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange-red | `#fa4616` | `--color-accent` | action, accent | Primary buttons, small emphasis and illustrated accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pressed orange edge | `#b62600` | `--color-accent-edge` | border | Hard bottom lip and edge of default primary actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cinema black | `#000000` | `--color-black` | background | Opening scene and default footer. |
| Primary ink | `#202020` | `--color-ink` | text | Headlines and primary explanations on white. |
| Navigation gray | `#454544` | `--color-nav-ink` | text | Navigation on the light header. |
| Secondary gray | `#646464` | `--color-muted` | text | Card descriptions and subdued controls. |
| Caption gray | `#838383` | `--color-tertiary` | text | Thumbnail captions and list category labels. |
| Inverse secondary | `#afafaf` | `--color-inverse-muted` | text | White at 0.686 over black for footer links. |
| Light edge | `#e0e0e0` | `--color-rule` | border | Visible black at 0.12 over white on cards and separators. |
| Soft white | `#eeeeee` | `--color-hero-text` | text | Hero headline and footer headings. |
| Badge wash | `#f0f0f0` | `--color-badge` | surface | Black at 0.06 over white for section badges and circular controls. |
| Pale gray panel | `#f9f9f9` | `--color-panel` | surface | Visible result of black at 0.024 over white for product panels. |
| Raised white | `#fcfcfc` | `--color-raised` | surface | Floating recommendation and terminal surfaces. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main chapter canvas, raised interfaces and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| business solution pages | Deep night | `#10101a` | `--color-deep-purple` | background | Footer below the closing conversion band. |
| business solution pages | Proof charcoal | `#151515` | `--color-charcoal` | background | Dark live-outcomes globe band. |
| business solution pages | Night purple | `#171721` | `--color-purple` | background | Closing conversion band and dark illustration backing. |
| business overview pages | Sand chapter | `#f5f0eb` | `--color-sand` | background | Tabbed capability chapters. |
| business solution pages | Warm illustration backing | `#f5f1ed` | `--color-warm-panel` | surface, background | Toolkit band and product illustration backing. |
| business solution pages | Warm canvas | `#faf8f6` | `--color-warm` | background | Warm bordered landing-page system. |

## Typography

- **Acid Grotesk** — Default marketing headlines. Open, contemporary grotesk with broad lowercase forms; regular weight and close spacing produce authority without boldness. OpenType features: "calt", "liga". If unavailable, use **Inter**. 400 with the specified negative tracking; rebalance line breaks for its narrower shapes. Font stack: "Acid Grotesk", "Inter", system-ui, sans-serif.
- **Inter** — Supporting paragraphs, actions, labels and default navigation. Compact, neutral sans-serif with a high x-height. OpenType features: "calt", "liga". Font stack: "Inter", -apple-system, system-ui, sans-serif.
- **Geist Variable** (only for business solution pages) — All marketing text in the warm, bordered system. Crisp grotesk with medium-weight tightly spaced headings and more neutral body tracking. OpenType features: "calt", "liga". Font stack: "Geist Variable", system-ui, sans-serif.
- **ui-monospace** (only for developer demonstrations) — Terminal output. System monospace, regular output with bold command names. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Acid Grotesk | 400 | 96px | 90px | -0.026em | Lower-left cinematic opening headline. |
| heading-lg | Acid Grotesk | 400 | 72px | 80px | -0.035em | Broad chapter headings above grids and demonstrations. |
| heading | Acid Grotesk | 400 | 48px | 58px | -0.028em | Split feature headlines and active demonstration titles. |
| card-heading | Acid Grotesk | 400 | 32px | 1.2 | -0.019em | Feature card and customer titles. |
| hero-support | Inter | 400 | 28px | 1.45 | -0.0286em | Single-line support under the cinematic headline. |
| body | Inter | 400 | 20px | 1.45 | -0.02em | Primary explanatory paragraphs in split chapters. |
| hero-action | Inter | 600 | 20px | 1.5 | -0.009em | Opening action label. |
| recommendation | Inter | 600 | 20px | 1.45 | -0.0165em | Short action statements on floating cards. |
| card-body | Inter | 400 | 18px | 28px | -0.011em | Muted feature card explanations. |
| eyebrow | Inter | 500 | 18px | 1.45 | -0.0144em | Sentence-case label in a pale rounded rectangle. |
| action | Inter | 600 | 18px | 1.5 | -0.01em | Orange chapter button labels. |
| tab | Inter | 500 | 18px | 1.2 | -0.0144em | Rounded demonstration controls. |
| caption | Inter | 500 | 16px | 1.2 | -0.011em | Preview captions and directory row text. |
| nav | Inter | 500 | 14px | 20px | normal | Default navigation links. |
| footer-link | Inter | 400 | 14px | 1.45 | -0.006em | Footer column links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| business solution pages | business-display | Geist Variable | 500 | 56px | 1 | -0.03em | Warm landing-page hero headings. |
| culture and hiring pages | culture-display | Acid Grotesk | 400 | 54px | 1.1 | -0.03em, features "ss12" | Mission-led opening with selected words in orange-red. |
| culture and hiring pages | directory-heading | Acid Grotesk | 400 | 48px | 40px | -0.02em, features "ss12" | Directory title aligned beside filters. |
| business solution pages | business-heading | Geist Variable | 500 | 40px | 1 | -0.03em | Toolkit, proof, FAQ and closing headings. |
| business solution pages | business-title | Geist Variable | 500 | 20px | 1.2 | -0.02em | Capability card titles. |
| business solution pages | business-body | Geist Variable | 400 | 18px | 1.4 | normal | Hero and centered support paragraphs. |
| business solution pages | business-action | Geist Variable | 500 | 18px | 1.2 | -0.02em | Primary actions and FAQ questions. |
| business solution pages | business-caption | Geist Variable | 400 | 16px | 1.4 | normal | Card explanations and footer links. |
| developer demonstrations | terminal | ui-monospace | 400 | 15px | 23px | normal | Dense terminal output only. |

**Notes:**

- Default headings remain weight 400 even at their largest size. Keep body text in Inter instead of extending the display face into every paragraph.
- Tracking is strongest in the 72px chapter scale; do not normalize all roles to one negative value.
- The business solution system is a complete scoped alternative: use Geist throughout it, rather than mixing its 56px hero with the default Acid Grotesk chapter scale.

## Layout

**Density:** Airy in storytelling, denser inside demonstrated software; chapters have long breathing room while controls stay compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Business card title-to-description gap. |
| 12px | Card title-to-copy gap and compact control groups. |
| 16px | Floating card padding and paired elements. |
| 24px | Feature grid gutters and horizontal action padding. |
| 28px | Default feature card inner padding. |
| 32px | Split heading-to-body spacing and navigation gaps. |
| 40px | Copy group-to-action spacing; business grid cell padding. |
| 60px | Demonstration-to-control-rail spacing. |
| 80px | Major heading-to-feature-block spacing. |
| 96px | Default chapter top and bottom padding. |
| 120px | Business FAQ padding and directory section padding. |
| 128px | Business closing conversion band vertical padding. |

### Containers and grids

- **default container**: max width 1320px · side padding 48px. Centered default marketing content; at 1440px the max width leaves 60px visible side margins.
- **feature grid**: 3 columns · gap 24px. Equal-width cards; 424px-wide cells at desktop, with a second row when needed.
- **split explanation**: max width 1320px · gap 64px. Text column capped near 504px with a larger right-hand media object; allow developer media to extend beyond the right edge.
- **business container** (only for business solution pages): max width 1200px · side padding 64px. Continuous left and right hairlines align all warm sections and dark proof bands.
- **directory container** (only for culture and hiring pages): max width 1200px · side padding 40px. Wide title/location/action rows and a compact filter header.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | hero action | 16px |
|  | chapter action | 10px |
|  | feature cards | 24px |
|  | demonstration panel | 32px |
|  | floating cards | 16px |
|  | tabs | 14px |
|  | media | 12px |
|  | badge | 8px |
|  | round controls | 50% |
| business solution pages | business action | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| action lip | `0px 3px 0px 0px #b62600` | Default orange primary buttons. |
| floating recommendation | `0px 3px 0px 0px rgba(0,0,0,0.15), 0px 22px 44px 0px rgba(0,0,0,0.1)` | Stacked recommendation objects. |
| terminal lift | `0px 32px 64px 0px rgba(0,0,0,0.08)` | Large terminal window. |
| tab lift | `0px 1px 2px 0px rgba(0,0,0,0.06)` | White demonstration tab controls. |

### Surfaces

#### White chapter · level 0

**Use:** Default product storytelling canvas.

**CSS:** `background: #ffffff; color: #202020`

#### Cinema stage · level 0

**Use:** Opening media backing and footer.

**CSS:** `background: #000000; color: #eeeeee`

**Observed:** Opening imagery is dimmed by a half-black layer and a bottom fade to solid black.

**Transfer:** Keep the media legible as a scene while protecting the lower-left copy.

#### Pale product panel · level 1

**Use:** Capability cards and wide product demonstrations.

**CSS:** `background: rgba(0,0,0,0.024); border: 1px solid rgba(0,0,0,0.12); border-radius: 24px`

**Observed:** The wide demonstration uses 32px corners instead of card corners; both sit directly on white.

**Transfer:** Differentiate containers by width rather than adding more colors.

#### Warm ruled canvas · level 0

**Only for:** business solution pages

**Use:** Business landing chapters.

**CSS:** `background: #faf8f6; border-left: 1px solid rgba(0,0,0,0.12); border-right: 1px solid rgba(0,0,0,0.12)`

**Observed:** Ruled content runs continuously through sections; warmer #f5f1ed and #f5f0eb bands separate capability chapters.

**Transfer:** Treat the page as a single aligned editorial grid.

#### Night conversion · level 0

**Only for:** business solution pages

**Use:** Business closing call.

**CSS:** `background: #171721; border-bottom: 1px solid rgba(255,255,255,0.1)`

**Observed:** Footer beneath is a deeper #10101a; side rules persist in white at low opacity.

**Transfer:** Keep the final action visually separate from the utility footer.

#### Proof charcoal · level 0

**Only for:** business solution pages

**Use:** Large live-metric art band.

**CSS:** `background: #151515; color: #ffffff`

**Observed:** Orange point art and white numbers are the only high-contrast layers.

**Transfer:** Use this dark field for one decisive proof moment, not every capability.

## Components

### Primary button

**Use:** Opening conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 300px; height: 64px; padding: 0px 24px; background: #fa4616; color: #ffffff; border: 1px solid #b62600; border-radius: 16px; box-shadow: 0px 3px 0px 0px #b62600`

**Text style:** `hero-action` — Inter 600 · 20px/1.5 · tracking -0.009em

**Observed:** A flat face sits above a hard lower lip. It is the sole large opening action.

### Chapter button

**Use:** Action after a feature explanation or closing statement.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 52px; padding: 0px 24px; background: #fa4616; color: #ffffff; border: 1px solid #b62600; border-radius: 10px; box-shadow: 0px 3px 0px 0px #b62600`

**Text style:** `action` — Inter 600 · 18px/1.5 · tracking -0.01em

**Observed:** Short labels sit in moderately wide rectangular controls; chapter examples are about 220px wide.

### Navigation

**Use:** Fixed default marketing header.

**CSS:** `position: fixed; top: 0px; height: 70px; width: 100%; z-index: 50`

**Text style:** `nav` — Inter 500 · 14px/20px

**Observed:** Brand mark left, centered links with 32px gaps, sign-in and compact orange action right. Transparent inverse treatment overlays the opening; light treatment follows on white chapters. Compact action is 32px high with 8px corners.

**States:** Declared: hover navigation-link opacity 0.7.

### Section badge

**Use:** Label a split explanatory chapter.

**CSS:** `display: inline-flex; padding: 4px 12px; background: rgba(0,0,0,0.06); border-radius: 8px; color: #202020`

**Text style:** `eyebrow` — Inter 500 · 18px/1.45 · tracking -0.0144em

**Observed:** Sentence-case text in a snug rectangle above the heading, not an uppercase overline.

### Capability card

**Use:** Equal-width product capability grid.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 28px; background: rgba(0,0,0,0.024); border: 1px solid rgba(0,0,0,0.12); border-radius: 24px; overflow: hidden`

**Text style:** `card-heading` — Acid Grotesk 400 · 32px/1.2 · tracking -0.019em

**Observed:** Large interface illustration first, title second, muted card-body paragraph last. Illustrations fade into the container before the copy; the card has no external shadow.

**Transfer:** Show one recognizable operation rather than a full application screen.

### Recommendation card

**Use:** Stacked, tangible advice illustration.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 16px; background: #fcfcfc; border: 1px solid rgba(0,0,0,0.15); border-radius: 16px; box-shadow: 0px 3px 0px 0px rgba(0,0,0,0.15), 0px 22px 44px 0px rgba(0,0,0,0.1)`

**Text style:** `recommendation` — Inter 600 · 20px/1.45 · tracking -0.0165em

**Observed:** Illustrated icon in a pale square left, short actionable sentence right. Rear cards step upward, shrink and partly hide behind the foremost card.

**Transfer:** Use concrete suggested actions tied to the new product.

### Demonstration tab

**Use:** Switch active content in a wide demonstration.

**CSS:** `height: 48px; padding: 0px 24px; background: #ffffff; color: #646464; border: 1px solid rgba(0,0,0,0.12); border-radius: 14px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.06)`

**Text style:** `tab` — Inter 500 · 18px/1.2 · tracking -0.0144em

**Observed:** Horizontal rail of content-sized controls below the stage. Selected control adds a 2px #202020 outline and primary ink.

**States:** Declared: hover background-color #f0f0f0; color #202020.

### Footer link column

**Use:** Utility navigation in the default black footer.

**CSS:** `display: flex; flex-direction: column; gap: 10px; width: 160px; color: rgba(255,255,255,0.686)`

**Text style:** `footer-link` — Inter 400 · 14px/1.45 · tracking -0.006em

**Observed:** Small semibold heading above regular links; four columns with 80px separation and a brand mark at far right.

**States:** Declared: hover link color #eeeeee.

### Business action

**Only for:** business solution pages

**Use:** Conversion in the warm ruled system.

**CSS:** `height: 48px; padding: 0px 24px; background: #fa4616; color: #ffffff; border-radius: 12px`

**Text style:** `business-action` — Geist Variable 500 · 18px/1.2 · tracking -0.02em

**Observed:** Flat rather than hard-lipped. Compact header and capability versions are 40px high with 10px corners; secondary closing action is transparent with a 1px white-at-0.2 border.

**States:** Declared: hover background-color #ff6a24.

### Email conversion form

**Only for:** business solution pages

**Use:** Low-friction lead entry alongside the product hero.

**CSS:** `display: flex; align-items: center; gap: 10px; padding: 4px 4px 4px 20px; background: #ffffff; border: 1px solid rgba(0,0,0,0.12); border-radius: 16px`

**Observed:** A single unboxed email field on the left and Business action nested on the right; overall desktop height 58px. Submit uses 20px horizontal padding.

### FAQ row

**Only for:** business solution pages

**Use:** Compact objection handling.

**CSS:** `background: #ffffff; border-bottom: 1px solid rgba(0,0,0,0.12); min-height: 71px`

**Text style:** `business-action` — Geist Variable 500 · 18px/1.2 · tracking -0.02em

**Observed:** Question left and down chevron right inside a 24px-padded inner row. White rows form one contiguous stack, not isolated rounded cards.

**States:** Declared: hover background-color oklab(0 none none / 0.02).

### Directory row

**Only for:** culture and hiring pages

**Use:** Grouped opportunities or index entries.

**CSS:** `display: flex; align-items: center; padding: 24px 0px; width: 100%`

**Text style:** `caption` — Inter 500 · 16px/1.2 · tracking -0.011em

**Observed:** A roughly 67px-high full-width link with title occupying the broad left column, muted location in the middle and orange-red Learn more at far right. Hairline rules separate rows; category headings precede groups by 12px.

**Transfer:** Adapt to any browsable catalogue that needs one item, one metadata field and one action.

## Imagery and graphics

### Cinematic working scene

**Use:** Default first-screen backdrop.

**Observed:** Full-bleed footage of a person doing real work, tightly framed on hands, face and tools. Natural colors are darkened substantially; no device frame or floating mockup surrounds it. The subject occupies the right and upper field while text sits low left.

**Transfer:** Film a real user performing a task; minimum version is a high-resolution candid still with the same framing and dark overlays.

**Build:** Cover a black 900px-high stage with the image; add rgba(0,0,0,0.5) above it, then a vertical transparent-to-black gradient staying clear until 65% and reaching black at 90%. Put copy above both layers.

### Interface objects

**Use:** Capability cards, terminal and wide demonstrations.

**Observed:** Crisp white forms, charts, chat fragments and overlapping code/output windows sit on pale gray backing. Fine borders and soft shadows establish depth; artwork is considerably larger than its accompanying copy. Card illustrations lose contrast into a white lower-edge fade.

**Transfer:** Use faithful simplified interface fragments with real labels and one obvious outcome. Minimum version is a clean HTML form or chart with a white-to-transparent mask, not a generic abstract blob.

**Build:** Layer two white rounded panels with a 1px rgba(0,0,0,0.12) edge and a downward rgba(0,0,0,0.08) shadow; offset the foreground result toward the lower right. For grid art, add a bottom linear fade matching the container.

### Rising recommendation stack

**Use:** Illustrated decision-making chapter.

**Observed:** Four white advice cards overlap in a rising stack on the right, the front card largest. Small dimensional object icons sit on pale squares. A thin green upward path and extremely pale wash run behind the stack.

**Transfer:** Keep the stack and ascending path but replace recommendations and icons with the new product's useful next actions.

**Build:** Use Recommendation card for four layers; anchor bottoms together, step rear layers upward by about 80px and inward by about 24px, reducing scale each time. Draw a thin green SVG rising curve behind, with a near-transparent green area beneath fading to white; exact curve shape is not essential.

### Customer media fan

**Use:** Signature social-proof gallery.

**Observed:** An active landscape image or video is followed by successively narrower clipped landscape previews, all 12px-rounded. Documentary people, workshops and restrained title cards create variety; title and short description sit below the active image.

**Transfer:** Use real customer environments and outcomes. When video is unavailable, use one strong candid photograph and related detail stills; retain the diminishing preview fan.

**Build:** Create a horizontal flex rail with one 826×464px active panel and six same-height panels clipped to progressively narrower widths; keep narrow gutters and rounded clipping. Place 48px circular previous/next controls below at the right.

### Photographic closing statement

**Use:** Signature monumental closing chapter.

**Observed:** Large left-aligned type occupies roughly the left three-fifths; a tall street photograph fills the right 576px of a 900px-tall chapter. A broad white horizontal fade dissolves the photograph's left edge into the page.

**Transfer:** Pair a consequential closing statement with an authentic scene of the product's wider effect. Minimum version is a place or user photograph with the same dissolve, not a stock business handshake.

**Build:** Position a portrait image at the right edge with cover sizing. Overlay a left-to-right white-to-transparent gradient across its first 38%, keeping text in the clear white region.

### Point globe

**Only for:** business solution pages

**Use:** Dark live-outcomes proof scene.

**Observed:** A huge near-black sphere rises from below the frame. Orange-red points describe land and a fine glowing rim; an oversized white live counter sits above it, with three bordered stat cells below.

**Transfer:** Translate reach into a point sphere or equivalent network object. Minimum version is an SVG hemisphere with orange points, a soft rim and real verified metrics.

**Build:** Project evenly spaced longitude/latitude dots onto a circle about 760px wide; dim the left hemisphere, show continent-shaped point clusters in rgba(250,70,22,0.55), and stroke the upper rim in rgba(250,70,22,0.7). Add a broad low-opacity orange shadow, clip the lower half behind a three-column stat strip.

### Culture globe

**Only for:** culture and hiring pages

**Use:** Mission-led opening illustration.

**Observed:** A giant silver-white globe sits on the right, clipped by the viewport bottom and right. Gray points form continents; small white activity notifications and pink location glows bring human scale.

**Transfer:** Use a pale point globe only for reach or participation narratives, keeping the left copy clear.

**Build:** Use a white sphere with a soft gray inset edge and gray projected dots; place a few tiny rounded white notification cards over it with low-opacity pink radial location glows.

### Dotted warm atmosphere

**Only for:** business overview pages

**Use:** Backing for the centered rotating hero phrase.

**Observed:** An almost invisible dot field and diffuse orange wash sit behind the centered headline; the page remains visibly warm white.

**Transfer:** Retain the restrained atmosphere when no product object belongs in the opening.

**Build:** Tile radial-gradient(rgba(0,0,0,0.12) 1px, transparent 1px) at a fine spacing behind the hero. Add a centered 720×420px orange ellipse at opacity 0.07 with blur(100px).

### Icons

**Observed:** Utility icons are mostly 16px or 20px outline SVGs, 1.5px strokes with round caps. Carousel chevrons sit inside circular controls; capability art uses larger illustrated objects rather than enlarging utility icons.

**Transfer:** Use a consistent rounded 1.5px outline set for navigation and controls. Keep colorful dimensional icons inside the demonstration layer.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A full-width, 900px-high Cinema stage fills the first screen. Back to front: tightly framed working footage, half-black dimming layer, black bottom fade, fixed Navigation, and lower-left copy. The headline spans about two-thirds of the width in display, with a 24px gap to hero-support and 40px to Primary button. The copy group is bottom-anchored with 96px breathing room and aligns with the 1320px container. Within the first 900px all of headline, support, orange action and the main working subject are visible; the first white explanatory chapter begins below the fold.

**Transfer:** For a different product, use a real task scene or an equally well-framed still, one ambitious promise and one direct action. Business solution pages instead open inside a 1200px ruled warm container with a 56px Geist headline and a product object, or a centered rotating phrase over dotted atmosphere. Culture pages use a left 54px mission line and pale point globe.

**Avoid:** Do not replace the working scene with a centered dashboard floating on a generic gradient, and do not center the default headline or add a second hero action.

**Text style:** `display` — Acid Grotesk 400 · 96px/90px · tracking -0.026em

### Split explanation

**Observed:** White chapter with 96px vertical padding. Section badge, heading, body and Chapter button occupy a roughly 504px left column; the media object fills the wider right field. Heading-to-copy spacing is 32px and copy-to-action spacing is 40px. Terminal media can extend beyond the right edge.

**Transfer:** Give one operation a concrete explanation and one large staged artifact; vary the artifact rather than the text system.

**Text style:** `heading` — Acid Grotesk 400 · 48px/58px · tracking -0.028em

### Broad capability chapter

**Observed:** heading-lg sits above a three-column grid of Capability card with 80px separation and 24px gutters. Cards use card-heading and card-body under faded interface illustrations.

**Transfer:** Group related capabilities into short named operations without forcing any particular number of cards.

**Text style:** `heading-lg` — Acid Grotesk 400 · 72px/80px · tracking -0.035em

### Interactive product stage

**Observed:** A broad heading precedes a 1320×582px Pale product panel with 32px corners. Active title and explanation sit low left; overlapping code and result objects fill the right. A small progress indicator sits high left and a Demonstration tab rail follows 60px below.

**Transfer:** Show one active workflow at a time and pair its implementation with its visible result.

**Text style:** `heading-lg` — Acid Grotesk 400 · 72px/80px · tracking -0.035em

### Template preview gallery

**Observed:** Large heading above a split explanation and 700px-wide elevated browser preview. A row of 208×130px thumbnails with 24px gaps and caption labels follows; selection has a double light-and-dark ring.

**Transfer:** Adapt to configurations, templates or sample outputs. Keep the active output large enough to read its composition rather than turning everything into tiny tiles.

### Proof fan

**Observed:** Broad headline, Customer media fan, card-heading and a short outcome explanation; circular controls sit beneath the media on the right.

**Transfer:** Let a real person or environment carry credibility before adding explanatory copy.

**Text style:** `heading-lg` — Acid Grotesk 400 · 72px/80px · tracking -0.035em

### Monumental closing statement

**Observed:** A 900px-tall white chapter uses a 72px regular statement on the left and Photographic closing statement treatment on the right. Supporting prose, Chapter button and small contact lines stay in the white region. It transitions directly into the black utility footer.

**Transfer:** Close with a consequential reason to act, not another feature grid. Keep the large statement and photographic dissolve even when the content is not a company mission.

**Text style:** `heading-lg` — Acid Grotesk 400 · 72px/80px · tracking -0.035em

### Utility ending

**Observed:** Default ending is a 699px black footer. A top app-access row combines a small tilted phone illustration, compact heading and explanation, with a 144×144px white QR card at far right. Hairlines divide this from Footer link column groups, a brand mark and the final legal row. Business pages use a 680px deep-purple version in the ruled container. Culture pages end with a 465px white footer, four link groups plus mark, top rule and legal row, without the app-access band.

**Transfer:** Preserve the clear separation between access/help, navigation and legal information. If there is no app, adapt the access band to one useful handoff such as a demo or downloadable guide.

### Warm product opening

**Only for:** business solution pages

**Observed:** Under a 40px orange announcement strip and 65px navigation, a ruled 1200px split stage gives each half about 599px. The left uses 64px inset, small orange category label, business-display, business-body and Email conversion form. A white upright checkout object floats on the warm right backing; logos continue immediately below.

**Transfer:** Choose one strong product object that demonstrates the promised outcome; keep the warm backing and equal split.

**Text style:** `business-display` — Geist Variable 500 · 56px/1 · tracking -0.03em

### Ruled capability chapters

**Only for:** business solution pages

**Observed:** Continuous 1200px side rules enclose a heading row and border-separated 399px grid cells with 40px padding. Illustration, business-title and business-caption stack vertically. Overview variants use full-width three-part tabs and a 50/50 text-and-dark-product-image split, reversing the image in the next chapter.

**Transfer:** Use cells for parallel capabilities and tabs for alternate workflows, keeping all section edges aligned.

**Text style:** `business-heading` — Geist Variable 500 · 40px/1 · tracking -0.03em

### Live proof band

**Only for:** business solution pages

**Observed:** A 913px Proof charcoal chapter begins with a small orange live badge, oversized white rolling metric and muted caption. Point globe occupies the lower middle; three equal border-separated metrics sit along the bottom in 32px medium Geist.

**Transfer:** Use verified cumulative outcomes with short labels; if a live feed is unavailable use an honestly labeled total, while retaining the point-art proof stage.

### Objections and closing call

**Only for:** business solution pages

**Observed:** FAQ heading occupies the left third and a contiguous 799px-wide FAQ row stack the right two-thirds, within 120px vertical padding. A separate 443px Night conversion band centers business-heading, a support line after 16px and paired solid/outlined actions after 32px, with 128px vertical padding.

**Transfer:** Answer operational concerns in plain questions, then offer self-service and assisted paths.

**Text style:** `business-heading` — Geist Variable 500 · 40px/1 · tracking -0.03em

### Culture directory

**Only for:** culture and hiring pages

**Observed:** A spare globe-led first screen is followed by directory-heading on the left and two 200×40px filters on the right. Category groups are separated by 48px; each begins with a muted 16px label and Directory row entries. The final category flows into a white utility footer after 120px of section padding.

**Transfer:** Use the directory as a purposeful browsing experience rather than importing the marketing card grid.

**Text style:** `directory-heading` — Acid Grotesk 400 · 48px/40px · tracking -0.02em

## Page flow

**Storyline:** Ambitious promise → tangible operation → capability breadth → real-world proof → larger consequence or objection handling → useful final action and utility navigation.

### Broad platform introduction

1. **Promise** — Full-screen working scene with one large statement and one action.
2. **Product demonstration** — Advice stack and terminal-led split explanations make the system operational.
3. **Capability breadth** — Illustrated card grid, API stage and large output preview with thumbnail rail.
4. **Social proof** — Diminishing media fan followed by a restrained logo strip.
5. **Closing consequence** — Monumental statement dissolved into a street photograph, action and contacts.
6. **Utility ending** — Black access band, QR handoff, link columns and legal row.

**Transfer:** Move from aspiration to concrete use before widening the offer; close with an image-backed reason to care.

### Mission-led recruitment and browsing

1. **Invitation** — Left mission statement with orange key words beside a pale point globe and two actions.
2. **Browse** — Directory heading and paired filters, then categorized three-field rows.
3. **Utility ending** — After the final category, a spare white ruled footer with links and brand mark.

**Transfer:** Keep the invitation human and let the majority of the page serve the reader's search task.

### Specific product-solution conversion

1. **Promise and entry** — Warm split hero with product object and integrated email form.
2. **Trust** — Compact monochrome logo grid.
3. **Capability chapters** — Ruled toolkit cells with product illustrations.
4. **Social proof** — Image-and-quote carousel with centered heading and round controls.
5. **Quantified proof** — Live counter, orange point globe and three metrics.
6. **Outcome explanation** — Three illustrated benefit cells.
7. **Objection handling** — Split FAQ stack.
8. **Closing call** — Dark paired-action band, then deeper footer with access handoff and columns.

**Transfer:** Make the product object and the low-friction entry the core of the opening; use proof and FAQs to support action.

### Business-system overview

1. **Promise** — Centered rotating orange audience phrase over a dotted warm atmosphere, support and one action.
2. **Trust** — Horizontal logo marquee with faded edges.
3. **Capability chapters** — Two tabbed chapters with reversed text/product-image halves.
4. **Social proof** — Customer media and quote carousel.
5. **Quantified proof** — Dark live metric and orange globe followed by a benefit grid.
6. **Objection handling** — FAQ stack beside a short heading.
7. **Closing call** — Dark paired actions, deep-purple access footer and legal ending.

**Transfer:** Adapt the rotating phrase to real audiences and organize the system into distinct workflow chapters rather than repeating a card catalogue.

## Writing

Confident, direct and economically practical. Big promises are followed quickly by concrete operations, useful verbs and simple explanations rather than abstract brand poetry.

**Do not copy:** Do not reuse Whop's name, marks, customer logos, proprietary imagery, mission wording, testimonials, financial claims, business counts or performance statistics; replace them with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you or your. Use we for deliberate product decisions, and the product name when explaining what the system does.
- **Rhythm:** Headlines are usually short declarative promises or imperative verb phrases. Support is one compact sentence or a short operational paragraph; card titles are often one to three words. Periods can finish headlines; exclamation marks are not part of the main voice.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name a broad shift, or define the engine behind a specific audience's outcome. | 3–8 words | “The new economy.”<br>“The revenue engine for software companies.” |
| Chapter headline | Active verb plus a concrete destination or capability. | 4–8 words | “Deploy a business instantly.”<br>“Power your platform from our API.” |
| Supporting line | Explain actual operations in a compact parallel list. | 6–16 words | “Build businesses, run ads, get paid.”<br>“Accept subscriptions, manage licenses, and handle global tax automatically.” |
| Card explanation | Describe what is included and what becomes easier, using operational nouns. | 10–25 words | “Global payment acceptance, invoicing, ACH, wires, and financing, out of the box.” |
| Primary action | Short imperative; use a task-specific label when the action is not generic entry. | 2–5 words | “Get started”<br>“Install the [Brand] CLI”<br>“See open positions” |
| Objection heading | Ask the user's direct practical question. | 5–10 words | “Do I need to be technical to integrate [Brand]?” |

**Words and phrasing to use:** build; run; get paid; power; deploy; automatically; out of the box; your next; start for free

**Avoid:** revolutionary synergy; unleash limitless possibilities; game-changing magic; enterprise-grade excellence; delighted to announce

**Rules:**

- Follow ambitious statements with specific operations the product performs.
- Prefer present-tense verbs and concrete outputs to strings of adjectives.
- Use numbers only where a real measurement supports them.
- Keep labels sentence case and let typography, not shouting, establish emphasis.

## Do's and Don'ts

### Do

- Keep default display and chapter headlines at weight 400.
- Anchor the opening copy low left with 96px breathing room above the next chapter.
- Use 24px card gutters and 28px card padding in the default three-column grid.
- Retain the orange button's 3px hard bottom lip on default marketing pages.
- Stage software in near-white objects with 1px translucent-black edges.
- Include the narrowing media fan and photographic closing dissolve in the default narrative vocabulary.
- Keep business sections aligned to the same 1200px vertical rules.
- Use a black utility ending for the default page and the white ending only for the culture directory variant.

### Don't

- Do not turn the 72px regular headings into bold condensed slogans.
- Do not round orange actions into pills; reserve circles for directional controls.
- Do not paint ordinary feature chapters solid orange; neutral space should dominate.
- Do not spread interface blues and greens into the marketing navigation or body copy.
- Do not put heavy drop shadows on every capability card; lift belongs to staged inner objects.
- Do not mix the flat 48px business action with the hard-lipped default hero control as interchangeable variants.
- Do not replace directory rows with 24px-rounded marketing cards.
- Do not bury the media fan's caption inside the image; title and explanation belong below it.

## Motion and responsive

### Motion

**Observed:**

- Opening copy declares 0.8s arrival with cubic-bezier(0.23,1,0.32,1); the support line has a 0.1s delay.
- Default reveal elements declare opacity and transform over 0.8s with cubic-bezier(0.23,1,0.32,1).
- Default hard-lipped actions declare all-property transitions of 0.1s cubic-bezier(.4,0,.2,1); demonstration tabs use 0.15s color transitions.
- Logo animations declare 40s linear landing-marquee and 25s linear scroll-seamless loops. Culture opening declares 0.76s cubic-bezier(0.16,1,0.3,1) rise-in.
- Story slots declare 350ms cubic-bezier(0.25,0.1,0.25,1) transitions.

**Transfer:**

- Preserve the slow reveal of large editorial content and faster tactile control response.
- Keep scrolling logo strips subordinate to the readable main narrative; use rolling numbers only in the scoped proof stage.

**Unknown:**

- Exact scroll thresholds, globe motion behavior and autoplay durations are not established.

### Responsive

**Observed:**

- The default feature grid has one-column, two-column and three-column class variants.
- Split explanation classes change to a vertical composition below the wide layout; the recommendation object has an earlier reading order in the narrow composition.
- Business hero declares a single-column grid changing to two columns; email entry changes from a vertical group to a horizontal form.
- Culture heading declares 44px below a 720px minimum-width condition and 54px above it.

**Transfer:**

- On narrow layouts retain the working-scene background and bottom-anchored copy, reducing headline size without centering the default composition.
- Stack explanatory media and copy while retaining pale backing and object depth. Allow the tab rail to scroll rather than shrinking controls.
- For the warm ruled system, preserve a single pair of outer rules and stack the product object below the copy. Let the point globe remain clipped as atmosphere, not a miniature beside unreadable text.

**Unknown:**

- Exact breakpoint widths for framework prefixes and complete mobile renders are unavailable.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
