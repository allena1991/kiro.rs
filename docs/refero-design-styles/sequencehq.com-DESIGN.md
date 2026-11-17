# Sequence — editorial automation atmosphere

## Overview

A light, editorial technology style that makes complex operational software feel composed and approachable. Fine serif promises sit beside light grotesk explanations, with charcoal text, near-white panels and restrained lilac and blue atmosphere. Detailed interface scenes, particle fields and documentary customer photography carry the story without making the surrounding page dense.

### Essentials

- Editorial promises above a field of activity: a centered 64px/1.05 light serif headline with -1.2px tracking occupies roughly two thirds of the opening width; a pale particle landscape lives below rather than competing with the words.
- Small, cushioned conversion controls: charcoal buttons use 14px/14px regular sans text, 16px corners and a 40px height, not oversized pills or sharp rectangles.
- Color is atmosphere, not navigation paint: white and #f9f9f9 dominate; lilac and icy blue collect around the lower hero, demonstration backings and closing panel. A dark assurance band is a bounded contrast, not the default theme.
- Product detail is staged like a document on a desk: 12px rounded pale gradient panels, 0.5px edges, 40px inset and clipped white interface layers keep complex UI legible without full-bleed dashboard clutter.
- Proof has two distinct registers: 72px light-looking regular sans numerals in a three-cell white slab, and 480px-tall documentary photo cards with small white outcome captions at their lower edge.
- Atmospheric light is a signature device: include a fine lilac-blue particle field and a soft blue-lilac illuminated panel on a new landing page. When no proprietary animation exists, use SVG dots and blurred gradient forms rather than omitting the atmosphere.
- Headings can step sideways: a second line is indented by about three character widths in editorial section titles; the closing promise returns to centered 56px light serif above one compact action.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pastel blue light | `#bad9f9` | `--color-glow-blue` | accent | Blue half of soft conic light around raised integration tiles. |
| Pastel lilac light | `#d7caf2` | `--color-glow-lilac` | accent | Lilac half of soft conic light around raised integration tiles. |
| Hero lilac | `#ebe5fb` | `--color-hero-lilac` | background | Left edge of atmospheric hero gradient, washed toward white above. |
| Mist blue | `#e3ebf8` | `--color-hero-blue` | background | Cool edge of hero gradient. |
| Pale lilac | `#f6f3ff` | `--color-hero-pale-lilac` | background | Interior of the hero atmosphere. |
| Icy white blue | `#f5f9ff` | `--color-hero-ice` | background | Interior of hero atmosphere on its cool side. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#202120` | `--color-ink` | text, action | Primary headings and filled conversion actions. |
| Night middle | `#0c0d0c` | `--color-night-middle` | background | Deep center of assurance band. |
| Night return | `#131212` | `--color-night-end` | background | Far edge of assurance band. |
| Night edge | `#171717` | `--color-night-start` | background | Dark assurance band gradient. |
| Body graphite | `#505050` | `--color-body` | text | Body copy and secondary action text. |
| Muted gray | `#757575` | `--color-muted` | text, link | Supporting explanations, navigation and footer links. |
| Pale edge | `#efefef` | `--color-rule` | border | Card outlines and accordion separators. |
| Panel middle | `#f5f5f5` | `--color-panel-mid` | surface | Subtle middle tone of demonstration backings. |
| Panel return | `#f8f8f8` | `--color-panel-end` | surface | Final tone of neutral demonstration gradients. |
| Off-white panel | `#f9f9f9` | `--color-panel` | surface, background | Wide bands and feature card backings. |
| Panel light | `#fcfcfc` | `--color-panel-light` | surface | Light end of neutral demonstration gradients. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, interface sheets and text on charcoal. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing comparison tables | Violet check | `#a565ff` | `--color-check-purple` | accent | Small filled inclusion checks, not broad background fills. |
| pricing pages | Call glow violet | `#716fff` | `--color-call-violet` | accent | Source hue of 40% blurred light behind white closing card. |
| pricing pages | Call glow cyan | `#77e8e9` | `--color-call-cyan` | accent | Source hue of 40% blurred light behind white closing card. |
| company and recruiting pages | Company deep ink | `#1d1d20` | `--color-company-deep` | text | Company chapter titles. |
| company and recruiting pages | Company heading ink | `#42424a` | `--color-company-ink` | text | Company-story headings and resource strip text. |
| product detail pages | Card explanation gray | `#6e6e6e` | `--color-card-copy` | text | Small explanatory copy on product feature cards. |

## Typography

- **twkLausanne** — Body, navigation, controls, numeric proof and many feature headings. Clean, open grotesk with restrained geometry; light cuts keep large headings unforced. If unavailable, use **Inter**. Use 300–500 for most copy; reserve 700 for plan names. Font stack: "twkLausanne", "Inter", Arial, sans-serif.
- **moderatSerif** — Hero promises, editorial chapter leads and closing call. Fine, softly bracketed editorial serif; predominantly weight 300, with close leading and restrained contrast. If unavailable, use **Newsreader**. Use 300; tune line breaks to retain the broad editorial silhouette. Font stack: "moderatSerif", "Newsreader", Georgia, serif.
- **Rock Salt** (only for team photo captions) — Handwritten annotations under overlapping team photographs. Small informal handwritten capitals and irregular strokes. Font stack: "Rock Salt", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| metric | twkLausanne | 400 | 72px | 1 | -0.035em, features "tnum" | Prominent proof numerals; suffix is 28.8px and superscripted. |
| display | moderatSerif | 300 | 64px | 1.05 | -0.0187em | Default centered landing-page promise, balanced across two lines. |
| closing-heading | moderatSerif | 300 | 56px | 1 | -0.02em | Centered emotional closing statement. |
| editorial-heading | moderatSerif | 300 | 48px | 1.05 | -0.02em | Editorial chapter leads with an indented second line. |
| heading | twkLausanne | 300 | 48px | 1.05 | -0.02em | Centered capability statements. |
| dark-heading | twkLausanne | 400 | 40px | 1.1 | -0.02em | White heading inside the dark assurance band. |
| quote | twkLausanne | 300 | 32px | 1.3 | -0.015em | Centered testimonial statement. |
| feature-heading | twkLausanne | 300 | 30px | 1.2 | -0.01em | Feature chapter title over a demonstration. |
| photo-outcome | twkLausanne | 300 | 28px | 1 | normal | Short outcome on documentary proof cards. |
| panel-copy | twkLausanne | 400 | 20px | 1.45 | -0.01em | Short explanations within wide product scenes; dark opening phrase followed by muted elaboration. |
| question | twkLausanne | 500 | 20px | 1.4 | normal | Accordion question rows. |
| lead | twkLausanne | 300 | 18px | 1.556 | normal | Two-line opening support. |
| body | twkLausanne | 400 | 16px | 1.5 | normal | Standard explanatory paragraphs and section support. |
| answer | twkLausanne | 400 | 16px | 1.55 | normal | Accordion answer copy. |
| action | twkLausanne | 400 | 14px | 1 | normal | Buttons and navigation. |
| footer-link | twkLausanne | 400 | 14px | 1.714 | normal | Footer navigation. |
| footer-label | twkLausanne | 400 | 13px | 1.846 | normal | Column labels in the footer. |
| eyebrow | twkLausanne | 400 | 12px | 1.8 | 0.1em, uppercase | Category framing above the main landing promise. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product detail pages | product-display | moderatSerif | 300 | 48px | 1 | -0.025em | Left-aligned product promise. |
| pricing pages | pricing-display | moderatSerif | 400 | 48px | 1 | -0.025em | Centered pricing title. |
| product detail pages | product-heading | moderatSerif | 300 | 40px | 1 | normal | Product detail chapters and closing call. |
| company pages | company-display | twkLausanne | 500 | 40px | 1.2 | -0.03em | Compact centered company introduction. |
| company and recruiting pages | company-heading | twkLausanne | 500 | 36px | 1.333 | -0.025em | Company narrative and recruiting section leads. |
| product detail pages | card-title | twkLausanne | 500 | 18px | 1.556 | normal | Feature card title and product-category label. |
| pricing pages | plan-name | twkLausanne | 700 | 18px | 1.556 | normal | Plan name at top of each comparison card. |
| company pages | resource-label | twkLausanne | 500 | 16px | 1.5 | normal | Resource strip links. |
| product detail pages | card-body | twkLausanne | 400 | 14px | 1.375 | normal | Feature card explanations. |
| pricing pages | comparison | twkLausanne | 400 | 13px | 1.43 | normal | Dense repeated inclusion cells. |
| team photo captions | photo-note | Rock Salt | 400 | 12px | 1.333 | normal | Small handwritten team photo annotations. |

**Notes:**

- Keep serif promises light and close-led; the default hero is 64px, not a huge bold sans headline.
- Section-level sans headlines and serif editorial leads share a 48px scale but remain separate roles.
- Tracking tightens with scale: -0.01em on 30px feature titles, -0.02em on 48px chapter titles, -0.035em on proof numerals.
- Use sentence case almost everywhere. The 12px uppercase eyebrow is the deliberate exception.

## Layout

**Density:** Airy outside, compact inside: broad section breathing room surrounds tightly organized controls and detailed interface scenes.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing and small repeated item gaps. |
| 12px | Action-row gap and compact card text groups. |
| 16px | Grid gutters, footer link gaps and small scene separation. |
| 24px | Headline-to-support gap and feature card inset. |
| 28px | Centered capability title to support line. |
| 32px | Demonstration stacks, accordion row vertical padding and larger card inset. |
| 40px | Product-scene inset and major local separation. |
| 48px | Metric cell padding and heading-to-chapter spacing. |
| 56px | Product opening copy to media; footer top inset. |
| 64px | Editorial side rail gap and closing panel vertical inset. |
| 80px | Product detail section vertical padding. |
| 96px | Landing section vertical padding. |
| 120px | Major editorial chapter introduction. |
| 128px | Extra breathing room around a major illuminated demonstration. |

### Containers and grids

- **marketing-container**: max width 1280px · side padding 80px. Centered desktop content at 1440px; navigation, feature chapters, broad proof and footer share its edges.
- **marketing-grid**: 12 columns · gap 16px. Main alignment grid; full-span sections contain more focused inner compositions.
- **editorial-rail**: 2 columns · gap 64px. 180px category rail beside flexible feature content inside the marketing container.
- **photo-grid**: 3 columns · gap 16px. Three tall customer proof cards, aligned at top and bottom.
- **faq-container**: max width 848px. Centered landing-page question stack.
- **product-container** (only for product detail and pricing pages): max width 1080px · side padding 24px. Narrower centered framework, leaving 180px outer margins at 1440px.
- **pricing-grid** (only for pricing pages): 3 columns · gap 8px. Equal-width cards within a 1080px frame.
- **culture-grid** (only for company pages): 3 columns · gap 24px. 325px-wide value cards; first cell is a section heading rather than a card.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary buttons | 16px |
|  | navigation hover target | 14px |
|  | demonstration panels and photo cards | 12px |
|  | feature cards and closing panel | 16px |
|  | interface sheets | 8px |
|  | status chips | 9999px (pill) |
| pricing pages | pricing cards | 4px |
| company pages | team value cards | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| button lift | `0px 10px 15px -3px rgba(0,0,0,0.07), 0px 4px 6px -4px rgba(0,0,0,0.07)` | Compact primary and secondary conversion buttons. |
| document lift | `0px 20px 25px -5px rgba(0,0,0,0.05), 0px 8px 10px -6px rgba(0,0,0,0.05)` | White sheets floating over pale demonstration backings. |

### Surfaces

#### Canvas · level 0

**Use:** Main page background.

**CSS:** `background: #ffffff; color: #505050`

#### Atmospheric hero · level 0

**Use:** Opening particle field backing.

**CSS:** `background: radial-gradient(100% 150% at 50% 0px, #ffffff 40%, rgba(0,0,0,0) 80%), linear-gradient(90deg, #ebe5fb, #f6f3ff, #f5f9ff, #e3ebf8)`

**Observed:** Nearly white upper center gives way to faint lilac and blue toward lower corners.

**Transfer:** Keep text over the white clearing and concentrate the activity beneath it.

#### Neutral demonstration stage · level 1

**Use:** Wide product scenes.

**CSS:** `background: linear-gradient(135deg, #fcfcfc, #f5f5f5 65%, #f8f8f8); border-radius: 12px; box-shadow: 0px 0px 0px 0.5px rgba(117,117,117,0.2); overflow: clip`

**Observed:** White document layers rise from a faintly graded neutral tray.

**Transfer:** Show one convincing workflow fragment rather than an entire application at unreadable scale.

#### Soft band · level 0

**Use:** Proof and capability groups.

**CSS:** `background: #f9f9f9; border-radius: 12px; border: 0.5px solid rgba(117,117,117,0.15)`

**Observed:** Broad inset bands leave a thin white perimeter, often 16px at desktop.

**Transfer:** Use as a chapter wrapper, not around every paragraph.

#### Night band · level 0

**Use:** Bounded assurance chapter.

**CSS:** `background: linear-gradient(135deg, #171717, #0c0d0c 20%, #131212); border-radius: 12px; color: #ffffff`

**Observed:** A single sustained dark contrast within a mostly light page, with faint outlined cards.

**Transfer:** Use for operational confidence or infrastructure assurances, not generic feature emphasis.

#### Glass prompt · level 2

**Use:** Natural-language configuration demonstration.

**CSS:** `background: rgba(255,255,255,0.2); border: 0.5px solid rgba(255,255,255,0.5); border-radius: 16px; backdrop-filter: blur(12px); box-shadow: 0px 25px 50px -12px rgba(0,0,0,0.05)`

**Observed:** A translucent text composer rests over diffused blue-lilac light, with small inline noun chips.

**Transfer:** Use a realistic instruction sentence to explain how a new product is directed.

#### Feature card · level 1

**Only for:** product detail pages

**Use:** Feature explanation and image pairs.

**CSS:** `background: #f9f9f9; border: 1px solid #efefef; border-radius: 16px; overflow: hidden`

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #202120; color: #ffffff; border-radius: 16px; padding: 12px 20px; height: 40px; display: flex; align-items: center; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.07), 0px 4px 6px -4px rgba(0,0,0,0.07)`

**Text style:** `action` — twkLausanne 400 · 14px/1

**Observed:** Short label without an icon. Navigation uses a compact 34px-high version with 10px 12px padding; product-detail calls use 38px height and 12px 16px padding.

**States:** Declared: hover background #333333; focus-visible outline none with retained elevation; active scale 0.98, radius 14px and background #1a1a1a.

### Secondary button

**Use:** Browse supporting proof or integrations.

**CSS:** `background: #ffffff; color: #505050; border-radius: 16px; padding: 12px 16px; height: 38px; box-shadow: 0px 0px 0px 1px rgba(117,117,117,0.15), 0px 10px 15px -3px rgba(0,0,0,0.07), 0px 4px 6px -4px rgba(0,0,0,0.07)`

**Text style:** `action` — twkLausanne 400 · 14px/1

**Observed:** A short right arrow follows the label with 8px separation. Product-detail customer-story buttons use a flat #efefef fill and 20px radius.

### Navigation link

**Use:** Centered navigation in a three-part header.

**CSS:** `color: #757575; height: 32px; padding: 0px 12px; border-radius: 14px; display: flex; align-items: center`

**Text style:** `action` — twkLausanne 400 · 14px/1

**Observed:** Wordmark sits left, compact navigation in the middle, sign-in and dark conversion action right. The navigation row is 67px tall with an 8px blur and saturation 1.2; an announcement variant adds a 36px pastel strip above.

**States:** Declared: hover background #f9f9f9 and color #202120; focus-visible outline none; active scale 0.98.

### Footer link

**Use:** Low-emphasis utility navigation.

**CSS:** `color: #757575; border-radius: 2px; display: block`

**Text style:** `footer-link` — twkLausanne 400 · 14px/1.714

**Observed:** Four columns use Footer label headings and 16px link gaps; a separate symbol anchors the left side. A fine ruled bottom row holds small social icons left and copyright right.

**States:** Declared: hover color #505050; focus-visible outline none.

### Demonstration panel

**Use:** Explain one capability with contextual UI.

**CSS:** `background: linear-gradient(135deg, #fcfcfc, #f5f5f5 65%, #f8f8f8); border-radius: 12px; padding: 40px 0px 0px 40px; min-height: 448px; overflow: clip; box-shadow: 0px 0px 0px 0.5px rgba(117,117,117,0.2); display: flex`

**Text style:** `panel-copy` — twkLausanne 400 · 20px/1.45 · tracking -0.01em

**Observed:** A short explanation sits low on the left; white document or application fragments occupy the right and can run beyond the lower edge. A Feature heading sits outside above it.

**Transfer:** Replace the document with the new product's recognizable working artifact.

### Metric slab

**Use:** Early quantified proof.

**CSS:** `background: #ffffff; border-radius: 16px; display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); box-shadow: 0px 0px 0px 0.5px rgba(117,117,117,0.25)`

**Text style:** `metric` — twkLausanne 400 · 72px/1 · tracking -0.035em

**Observed:** Three equal cells share one white slab; each is 320px tall with 48px inset and a fine vertical divider. Large black numerals sit above low-positioned outcome labels, with reduced superscript suffixes.

**Transfer:** Use genuinely supported outcomes, keeping the amount and explanatory label visually distinct.

### FAQ row

**Use:** Resolve detailed objections near the end.

**CSS:** `border-bottom: 1px solid #efefef`

**Text style:** `question` — twkLausanne 500 · 20px/1.4

**Observed:** Full-width question button has 32px vertical padding, text left and a small chevron right; the answer uses Answer type, 32px right inset and 32px bottom space. First answer is expanded in the initial arrangement.

### Photo proof card

**Use:** Customer stories with one memorable outcome.

**CSS:** `border-radius: 12px; height: 480px; position: relative; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(117,117,117,0.25)`

**Text style:** `photo-outcome` — twkLausanne 300 · 28px/1

**Observed:** Documentary photo fills the card, white customer mark sits near the upper left, outcome and one-line context sit at the bottom over a charcoal fade. Product-detail variants are roughly 416px tall with 24px outcome text.

**Transfer:** Use real workplaces, customers or events; let the photo establish reality rather than illustrate a metaphor.

### Dark assurance card

**Use:** Operational reliability statements within Night band.

**CSS:** `background: rgba(255,255,255,0.02); border: 0.5px solid rgba(255,255,255,0.1); border-radius: 16px; padding: 32px; width: 360px`

**Observed:** Muted 14px category label at top, white 21px statement near the bottom. A horizontal row extends beyond the container and uses small circular previous/next controls.

### Plan card

**Only for:** pricing pages

**Use:** Present a commercial tier.

**CSS:** `background: #ffffff; border-radius: 4px; padding: 20px; display: flex; flex-direction: column; box-shadow: 0px 0px 0px 1px rgba(117,117,117,0.2)`

**Text style:** `plan-name` — twkLausanne 700 · 18px/1.556

**Observed:** Name, price basis, short audience line, full-width action, inclusion list and optional additions. Entry tier uses a gray action; higher tiers use dark actions. All three cards are equally weighted rather than giving one a saturated fill.

### Resource strip

**Only for:** company pages

**Use:** Non-sales ending for company storytelling.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 20px; border: 0.5px solid rgba(117,117,117,0.15); border-radius: 6px 0px 0px 6px`

**Text style:** `resource-label` — twkLausanne 500 · 16px/1.5

**Observed:** Three adjoining equal-width links form a single 1080px-wide strip. Outer corners alone are rounded; small icons align at the far right of each cell. A short invitation sits 24px above it.

## Imagery and graphics

### Particle landscape

**Use:** Signature opening atmosphere.

**Observed:** Tiny lilac, blue and gray particles form a loose flowing terrain across the lower half of an otherwise white hero. A few white-centered colored nodes carry minute status chips; the field is sparse near the headline and denser near the bottom.

**Transfer:** Translate the product's activity into a subtle system landscape. A static vector dot field is the minimum acceptable equivalent; it must still feel like flowing activity rather than a regular dot wallpaper.

**Build:** Layer an SVG across the lower 400px of an 800px stage. Scatter small circles along overlapping shallow wave paths with irregular density; use pastel lilac and blue, with many dots at 10–30% opacity. Fade the SVG upward with a white mask. Add two or three white-centered nodes with 2px colored rings and translucent 8px halos; place tiny white rounded status chips nearby.

### Diffused light panel

**Use:** Signature demonstration and closing-call atmosphere.

**Observed:** Wide rounded panels contain an almost-white pink-lilac center, with soft vertical cobalt-blue and lavender forms at the side edges. Text or a glass prompt remains crisp in front; the light feels translucent and out of focus.

**Transfer:** Retain the luminous side framing around a meaningful artifact or closing invitation. It does not require a custom 3D object.

**Build:** Use a 12px or 16px clipped panel, white base and pale lilac wash. Place tall blue and lilac ellipses partly beyond left and right edges, blur them by 32px–120px, and overlay a broad white radial clearing across the center. Keep the dark text plane above all light layers; match the soft glow rather than emphasizing exact gradient stops.

### Product sheets

**Use:** Detailed capability proof.

**Observed:** White app windows, invoices, editor documents, email threads and compact tables are isolated on neutral trays. Shadows are soft; edges are faint. Some views crop at the bottom and fade secondary details, while a key line or action stays sharp.

**Transfer:** Create believable UI for the new workflow with a clear title, navigation hint and one relevant output; preserve a low-contrast neutral shell and limited status color.

### Integration constellation

**Use:** Ecosystem compatibility.

**Observed:** Many compact logo tiles form staggered rows around one elevated center tile. The center has a 106px white face, 20px corners and a blue-lilac glow; surrounding tiles have restrained edges. Product-detail versions use a flat 5-by-5 matrix of 74px cells.

**Transfer:** Use authentic integrations for the new product, or neutral service-category symbols with one central product symbol.

**Build:** Arrange three staggered rows of white rounded square tiles with fine gray edges. Raise the center tile slightly and place two 108px conic-gradient layers behind it: pastel blue to pastel lilac from 90 degrees, one at 30% opacity with 32px blur and one at 60% with 120px blur.

### Documentary proof photography

**Use:** Customer story cards and human credibility.

**Observed:** Real gatherings, offices and product presentations, with a mixture of muted color and black-and-white. Tall framing emphasizes people in real settings; dark lower fades make white metrics readable.

**Transfer:** Choose natural workplace or customer-context images, not glossy staged handshakes. Use authentic scenes with enough lower visual calm for a caption.

### Vertical light demonstration

**Only for:** product detail pages

**Use:** Immersive workflow chapter and hero backings.

**Observed:** Broad pale blue, mint and lavender light curtains with softly visible vertical striations. White email or app windows enter over the light; a centered serif title anchors the upper area.

**Transfer:** Use a restrained blue-green light field behind a single workflow demonstration, not behind all text sections.

**Build:** Layer very broad translucent blue and mint linear gradients, add sparse vertical translucent white strips of varying widths, blur the color layer heavily and mask the edges into white. Clip the composition to 16px corners; place a white interface card in the foreground.

### Company craft graphics

**Only for:** company pages

**Use:** Company introduction, principles and team story.

**Observed:** A 16-by-6 matrix of pale lavender cells suggests accumulated progress. Principle cards use very faint white extruded geometric symbols over hairline construction grids, paired with small violet icons. Team photos overlap like casually stacked instant prints, with handwritten notes below.

**Transfer:** Represent the new organization's accumulated work and principles with equally understated geometry, then introduce genuine informal team images.

**Build:** For the progress matrix use 64px by 32px cells in several near-white lavender intensities, with 0.5px grid lines fading into white at the perimeter. For principle art draw a simple star, heart or polygon in isometric SVG with white top face, pale gray side face and thin gray strokes. Give photo prints a 6px white border, a deeper lower caption margin and slight alternating rotations.

### Pricing closing light

**Only for:** pricing pages

**Use:** Consultative closing card.

**Observed:** A white 1024px-wide rounded card has extremely pale cyan-violet light and broad curving corner shapes rather than the stronger blue edges of the default closing panel.

**Transfer:** End commercial detail with a softer advisory invitation.

**Build:** Behind the white card layer 258px circles with a violet-to-cyan gradient, 40% opacity and 100px blur; clip broad pale curved forms at opposite corners and retain a soft 0px 4px 10px shadow.

### Icons

**Observed:** Most utility glyphs are filled 14px or 16px symbols in muted gray; small chevrons and arrows sit beside labels. Accordion chevrons use 16px outlines with 2px round strokes. Product integration marks preserve their own colors; table checks are tiny violet filled circles.

**Transfer:** Use one restrained utility icon family; keep navigation marks subordinate to 14px text and reserve colored marks for integrations, status or inclusion.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric editorial opening

**Observed:** An 800px-tall stage places a centered text stack above a low particle landscape. Back to front: pale lilac-to-blue gradient, broad white upper clearing, particle terrain and small status nodes, then a 12px uppercase eyebrow, 64px light serif promise, 18px support and compact action row. The headline spans roughly 940px across two lines; support is about 590px wide. Headline-to-support gap is 24px and support-to-action gap 32px. The main action is Primary button, paired with an unfilled text exploration action 12px away. The slim header remains separate above the content. Within the first 900px the full promise, support, actions, particle scene and 88px monochrome customer-logo belt are visible. Detailed product panels and numeric proof arrive below this first screen.

**Transfer:** Use the new product's central outcome as a two-line editorial promise and activity nodes as its main visual object. Rebuild the particle terrain with SVG when no custom animation exists. Product-detail openings instead use a left-aligned 48px serif promise and action beside short right-column support, followed 56px later by a 1080px-wide illuminated app scene. Pricing opens with a centered 48px title and three plan cards; company storytelling opens with a compact 40px medium sans statement and progress matrix.

**Avoid:** Do not substitute a giant dashboard behind the headline, a high-saturation full-screen gradient or a heavy bold sans promise.

**Text style:** `display` — moderatSerif 300 · 64px/1.05 · tracking -0.0187em

### Stepped editorial chapter

**Observed:** Editorial heading sits at the container edge; its second line moves right by roughly three character widths. Feature chapters below pair a 180px navigation rail with Demonstration panel content, separated by 64px.

**Transfer:** Use a category rail only when it helps explain a multi-part workflow; preserve the stepped heading as an editorial gesture.

**Text style:** `editorial-heading` — moderatSerif 300 · 48px/1.05 · tracking -0.02em

### Quantified proof slab

**Observed:** A short two-tone introductory sentence precedes Metric slab by 40px inside Soft band. Major vertical padding is 96px; numerals and explanatory labels are separated by open space rather than charts.

**Transfer:** Give a small set of substantiated outcomes room to register; the band can appear wherever proof best supports the story.

**Text style:** `metric` — twkLausanne 400 · 72px/1 · tracking -0.035em

### Centered system demonstration

**Observed:** Heading and 16px support are centered, 28px apart. A large Neutral demonstration stage or illuminated Glass prompt sits 44px–56px below, framed by broad white space.

**Transfer:** Use a recognizable system output or instruction as the anchor, with subordinate surrounding UI.

**Text style:** `heading` — twkLausanne 300 · 48px/1.05 · tracking -0.02em

### Editorial testimonial

**Observed:** A broad 1280px rounded panel contains a centered Quote statement within about 953px, with large pale serif quotation marks, customer mark and compact author attribution. Inner padding is 64px.

**Transfer:** Use one specific quote about a complicated task becoming manageable, not a collage of short slogans.

**Text style:** `quote` — twkLausanne 300 · 32px/1.3 · tracking -0.015em

### Compatibility and proof

**Observed:** Integration constellation supplies a graphic compatibility proof, followed by documentary Photo proof cards with concise outcomes. The image devices stay visually distinct: white tiles for systems and real photography for people.

**Transfer:** Use real ecosystem relationships and customer contexts relevant to the new product.

### Dark assurance chapter

**Observed:** Night band contains a stepped 40px white heading, horizontally overflowing Dark assurance cards with 16px gaps, then small compliance links and monochrome seals. The band is inset 16px from the viewport and has 12px corners.

**Transfer:** Give reliability its own material treatment; include only assurances that can be substantiated.

**Text style:** `dark-heading` — twkLausanne 400 · 40px/1.1 · tracking -0.02em

### Objection stack

**Observed:** A centered title sits above an 848px FAQ column. FAQ row components use 20px questions and 16px answers. Pricing uses a split arrangement with a left serif heading and a narrower answer stack on the right.

**Transfer:** Address the likely integration, trust and adoption concerns with concrete mechanisms, not reassurance alone.

**Text style:** `question` — twkLausanne 500 · 20px/1.4

### Illuminated closing call

**Observed:** A 1280px-wide, 364px-tall panel has 16px corners, a fine outline and Diffused light panel backing. A centered 56px serif statement, muted support and Primary button sit inside 64px vertical padding. Product-detail variants use a 1080px panel, 40px serif statement and faint large cyan-lilac circular arcs. Pricing uses Pricing closing light and an advisory call; company storytelling ends with Resource strip instead of a sales panel.

**Transfer:** Close with one recognizable pain reframed as relief and one next step. Retain illuminated light framing as the visual resolution of the page.

**Text style:** `closing-heading` — moderatSerif 300 · 56px/1 · tracking -0.02em

### Utility footer

**Observed:** White footer uses a 1280px container, 56px top inset, left symbol and four link columns with 16px gutters. Headings are 13px/24px; links 14px/24px. Deep breathing room precedes a thin bottom rule, social icons and small copyright. This treatment is shared across all page types.

**Transfer:** Keep footer informational and visually recessive; preserve its column hierarchy and final ruled baseline.

### Product feature mosaic

**Only for:** product detail pages

**Observed:** A centered 40px serif heading introduces a pale band. White 8px-radius cards combine large interface fragments above compact 16px titles and 14px explanation. Other chapters use two equal columns of Feature card with 24px inset and 18px titles.

**Transfer:** Group secondary capabilities in a compact mosaic, balancing two wide cards with smaller cells rather than flattening everything into uniform icon cards.

**Text style:** `product-heading` — moderatSerif 300 · 40px/1

### Commercial comparison

**Only for:** pricing pages

**Observed:** Three Plan cards sit within a 1080px frame over a faint pastel opening background, with dotted construction lines extending their edges. Detailed comparison uses 56px rows, 0.5px rules and 13px copy in three aligned plan columns; violet checks repeat beside included features.

**Transfer:** Keep tier hierarchy neutral and readable; put complexity into organized rows rather than marketing-size text in every cell.

**Text style:** `comparison` — twkLausanne 400 · 13px/1.43

## Page flow

**Storyline:** outcome promise → tangible workflow → quantified and human proof → capability depth → adoption and trust → objection handling → illuminated next step → utility footer

### Broad platform landing page

1. **Promise** — Centered editorial headline over an activity landscape, followed by a monochrome logo belt.
2. **Quantified proof** — Three-cell numeric slab.
3. **Capability chapters** — Stepped editorial heading, category side rail and document-like demonstrations.
4. **Product demonstration** — Human-in-the-loop work board and natural-language composer.
5. **Compatibility and social proof** — Integration tile constellation and documentary story cards.
6. **Adoption and trust** — Migration questions and a bounded dark assurance band.
7. **Objection handling** — Expanded-first FAQ stack.
8. **Closing call** — Illuminated serif invitation and white utility footer.

**Transfer:** Adapt the depth to the product, retaining the editorial-to-operational contrast and the atmospheric visual devices.

### Workflow-focused product landing page

1. **Promise** — Split serif promise and support above an illuminated application scene.
2. **Product demonstration** — Immersive light-curtain chapter with email-to-action progression and three compact mode tabs.
3. **Capability depth** — Active feature list beside invoice artifact, then feature mosaic and a larger customer-facing portal grid.
4. **Compatibility** — Systems-of-record heading beside a 5-by-5 integration matrix.
5. **Social proof** — Three documentary customer outcome cards.
6. **Closing call** — Pale circular-arc invitation panel followed by shared footer.

**Transfer:** Show a clear incoming request, its handling and its resulting artifact; do not repeat one media image for every capability.

### Complex product explanation

1. **Promise** — Split headline, support and action above a large app sheet.
2. **Quantified proof** — Three compact numeric benefit cards.
3. **Capability chapters** — Selectable model list with UI, centered transformation diagram, then a two-column amendment grid.
4. **Capability breadth** — Pale feature mosaic.
5. **Compatibility and social proof** — Integration matrix and photographic outcome cards.
6. **Closing call** — Circular-arc serif invitation and shared footer.

**Transfer:** Explain complexity by grouping distinct behaviors into focused artifact demonstrations.

### Plan selection and commercial reassurance

1. **Pricing** — Centered serif title, support and three neutral tier cards.
2. **Comparison** — Long categorized table with repeated plan columns and fine rules.
3. **Trust** — Compact enterprise credentials.
4. **Quantified proof** — Pale case-study band with statistics and a fine perspective-grid graphic.
5. **Objection handling** — Split FAQ layout and short time-to-value proof beside a customer quote.
6. **Closing call** — Softly illuminated advisory card and shared footer.

**Transfer:** Use detailed comparison for high-consideration purchases while reserving the lower page for proof and reassurance.

### Company credibility and recruiting

1. **Mission** — Centered medium sans statement above pale progress-cell matrix.
2. **Origin** — Founder narrative with natural environmental portrait.
3. **Principles** — Three-column grid with a heading cell and understated isometric illustrations.
4. **Credibility** — Fine-ruled investor row.
5. **People and opportunity** — Team story, stacked annotated photos, prior-company strip and categorized job rows.
6. **Continued engagement** — Three adjoining resource links and shared utility footer.

**Transfer:** Use the human, crafted variant for organizational storytelling rather than adding sales CTAs to every chapter.

## Writing

Confident, practical and unusually close to the everyday work. It names concrete operational friction, then explains the mechanism of relief without breathless futurism.

**Do not copy:** Do not reuse Sequence's name, logo, customer marks, proprietary interface labels, acquisition announcement, customer quotations, compliance claims, performance figures, prices or migration guarantees as facts for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use your and you for the reader's team and work; the product is generally named in support copy. Company narrative uses we and founders' first-person experience.
- **Rhythm:** Headlines are usually 4–10 words, with compact paired clauses and occasional deliberate fragments. Support is one or two specific sentences; feature captions stay short enough to scan beside an artifact.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Promise a concrete outcome or transformation, not an abstract category alone. | 6–10 words | “AI-native revenue automation from quote to cash”<br>“Turn complex contracts into accurate invoices” |
| Section headline | Pair the difficult condition with the steady response; sentence case and plain punctuation. | 4–9 words | “Contracts change. Billing keeps up.”<br>“Invoices that go out right. Every time.” |
| Supporting line | Name recognizable inputs, work and exceptions; explain what happens automatically. | 1–2 sentences | “Configure agents with your standard operating procedures and guardrails, then embed them in your core revenue workflows.” |
| Feature caption | Use an active verb and specific output. | 5–14 words | “Track live invoice totals before the billing period ends.” |
| Primary action | Low-friction invitation, verb first. | 2–4 words | “Book a demo”<br>“Book a call” |
| Closing line | Recognize a lived pain with a humane negative, then offer a calmer alternative. | 7–10 words | “Your month-end shouldn't be a fire drill.” |

**Words and phrasing to use:** runs itself; built in; every time; in one place; before; automatically; guardrails; human in the loop; real-time; your team

**Avoid:** revolutionary; unleash limitless potential; game-changing; supercharge everything; magic with no explanation; effortless perfection

**Rules:**

- Explain the mechanism after promising the result.
- Use the vocabulary of actual work: inputs, outputs, exceptions and review.
- Prefer restrained specificity to adjective stacks.
- Let a short dark lead phrase and muted elaboration share a caption when contrasting outcome with detail.
- Treat trust and control as part of the product story, not a legal afterthought.

## Do's and Don'ts

### Do

- Keep the default promise at 64px/1.05 serif weight 300 and preserve balanced two-line phrasing.
- Use 1280px marketing containers and a narrower 1080px product-detail framework.
- Pair 40px-high charcoal actions with 14px text and 16px corners.
- Leave 80px–96px vertical breathing room around substantive chapters.
- Stage artifacts on 12px rounded neutral trays with 0.5px edges.
- Let metric suffixes shrink to 40% of 72px numerals.
- Use the dark assurance treatment as one bounded material contrast.
- Resolve the page with illuminated light framing and a restrained white footer.

### Don't

- Do not turn small 14px actions into 56px-high saturated conversion pills.
- Do not replace all serif roles with the sans family; that erases the editorial/operational contrast.
- Do not make every panel a shadowy floating card; most edges are only 0.5px or 1px.
- Do not put saturated purple behind paragraphs; reserve it for tiny status or inclusion details and diffused light.
- Do not use the 4px pricing-card radius as the default for 12px scene panels.
- Do not uppercase section headlines like the 12px eyebrow.
- Do not spread the 72px metric recipe to ordinary feature titles.
- Do not give the footer giant headings or a second high-contrast sales message.

## Motion and responsive

### Motion

**Observed:**

- Primary controls declare background-color, scale and border-radius transitions of 0.15s with cubic-bezier(0,0,0.2,1). Active primary controls scale to 0.98 and tighten corners from 16px to 14px.
- Navigation declares 0.1s transitions with cubic-bezier(0.25,0.46,0.45,0.94).
- Broad inset bands declare view-timeline expansion with linear timing; photo story cards declare 0.25s flex-grow and box-shadow transitions.
- The customer-logo belt declares a 200s infinite linear marquee; team cells declare 2.2s linear fade animation.

**Transfer:**

- Keep the operational scenes and atmosphere slow enough to read while compact controls respond quickly.
- Use the slight active corner tightening on cushioned conversion controls; preserve the calm resting silhouette.

**Unknown:**

- Exact particle simulation behavior and scroll choreography are not specified.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- Desktop navigation switches at 1080px; main editorial rail becomes a distinct two-column layout at 1360px.
- Below 1080px the default hero declares a 48px headline; product heroes declare 36px. The default closing title declares 32px.
- Narrow customer-story cards use a horizontal snap row, with cards capped at 320px and based on 80% of the viewport; dark assurance cards reduce to 280px.
- Company progress matrix is hidden below the medium layout. Desktop container gutters reduce to 40px and then 20px.

**Transfer:**

- Keep the atmospheric field behind and below the promise when narrowing the opening; do not squeeze the desktop side rail alongside the scene.
- Stack product hero support below its promise and preserve a readable artifact window rather than scaling every UI label down.
- Retain horizontally browsable proof cards where stacking would create repetitive page length.

**Unknown:**

- Exact rendered mobile compositions and intermediate breakpoint behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
