# Employment Hero — lavender with superpowers

## Overview

A buoyant, practical software-marketing style that makes complicated work feel manageable. Heavy, rounded sans-serif headlines sit on white and pale lavender, with vivid purple actions, human workplace photography and friendly sticker-like illustrations. Product interface fragments make benefits tangible, while spacious chapters alternate with denser proof and resource collections.

### Essentials

- Headlines feel like a friendly heavyweight: Saiga at 64px/68px, weight 900 and -0.2px tracking for the opening; major chapter titles remain nearly as bold at 60px/65px.
- The opening is a lavender enclosure, not a generic split hero: a 1300px-wide, 20px-radius panel holds a centered badge, breadcrumbs, two-line promise, 600px-wide support paragraph and one purple action; its dark trust rail appears within the first 900px.
- Actions have two distinct personalities: ordinary product CTAs are purple 52px-high pills with 32px corners and 14px 24px padding; the bright closing band uses a black 48px-high button with 8px corners.
- Color behaves like a confidence boost: white and #f9f5ff carry most of the page, #7622d7 concentrates on actions and links, and a full-width #a569ff band provides the vivid closing payoff. Dark purple-to-black is a contained trust or demonstration stage, not the ordinary canvas.
- Human work and software coexist in one image: natural workplace portraits sit inside lavender mats with floating white status or metric cards; standalone interface fragments get playful black-outlined purple, lime and cyan stickers. Every new page needs this human-plus-product device; use a relevant portrait and one simplified result card when richer media is unavailable.
- The closing payoff is theatrical but approachable: a 356px violet band pairs a white 42px/48px promise with proof badges, a black action and a large friendly character or product object. Preserve this illustrated payoff with an original character or a dimensional device illustration, then resolve into a dense near-black footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action purple | `#7622d7` | `--color-purple` | action, link, accent, border | Primary pills, inline links, checks and active controls. |
| Bright violet | `#a569ff` | `--color-violet` | background, accent | Full-width illustrated closing band and product-media accents. |
| Deep purple | `#460078` | `--color-purple-dark` | background, action | Primary-button hover and dark trust-stage gradient top. |
| Lavender depth | `#e6d5fe` | `--color-lavender-deep` | background, border, accent | Gradient endpoints, promotional-panel edges and media backing. |
| Lavender wash | `#f9f5ff` | `--color-lavender` | background, surface | Hero enclosure, proof bands, FAQ headers and product-family cards. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Light violet accent | `#9a58fc` | `--color-light-violet` | text, accent, background | Small accent labels, gradient edges and scoped service closing band. |
| Electric lime | `#bafc58` | `--color-lime` | accent | A narrow portion of the multicolor badge edge and trust-control focus outline. |
| Electric cyan | `#70ddff` | `--color-cyan` | accent | A narrow portion of the multicolor badge edge; also compatible with sticker artwork. |
| Plan edge | `#bb91eb` | `--color-plan-edge` | border | Fine purple outline around wide plan panels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#0a0a0b` | `--color-stage-black` | background | Dark gradient endpoint for trust rails and immersive demonstrations. |
| Near-black ink | `#121214` | `--color-ink` | text, background, action | Default heading and body ink, footer background and dark actions. |
| Footer bottom | `#27272a` | `--color-footer-bottom` | background | Copyright strip beneath the near-black footer. |
| Dark hover | `#3f3f46` | `--color-hover-ink` | action, text | Hover fill for black actions and secondary paragraph ink. |
| Muted gray | `#71717a` | `--color-muted` | text, border | Supporting labels, trust labels and footer form borders. |
| Footer gray | `#a9a9b2` | `--color-footer-muted` | text, border | Footer headings and secondary text, feature-accordion separators. |
| Neutral hairline | `#e4e4e7` | `--color-rule` | border, text | Navigation rules, FAQ outlines and light text in footer links. |
| Soft gray | `#f4f4f5` | `--color-soft-gray` | background, border | Header utility groups and subtle resource-card outlines. |
| Price paper | `#fcfbff` | `--color-price-paper` | surface | Near-white price sidebar. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, raised cards and text on saturated surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| managed-service landing pages | Service action lime | `#94e022` | `--color-service-lime` | action | High-contrast action on the centered service closing band. |
| journey-led product pages | Power-up lavender | `#f0ebff` | `--color-power-wash` | surface | Solution callout within a numbered journey. |
| overview and journey-led product pages | Pure black | `#000000` | `--color-pure-black` | text, action | High-impact overview and journey hero text; small plan actions. |
| journey-led product pages | Journey lavender | `#f5f3fc` | `--color-hiring-wash` | background | Capability, proof and pricing sections in the journey-led variant. |

## Typography

- **Saiga** — Headlines, capability headings, FAQ questions and prominent numerals. Heavy, rounded, compact sans with broad friendly forms and a slightly informal silhouette. If unavailable, use **DM Sans**. Use 900 for display and retain compact line heights; less distinctive but close in width and roundness. Font stack: "Saiga", "DM Sans", -apple-system, system-ui, Segoe UI, Roboto, sans-serif.
- **DM Sans** — Paragraphs, actions, navigation, quotations and labels. Clear geometric sans, open and friendly at text sizes. Font stack: "DM Sans", -apple-system, system-ui, Segoe UI, Roboto, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Saiga | 900 | 64px | 68px | -0.0031em | size clamp(44px, 21.1px + 2.9762vw, 64px) | Default centered product opening headline. |
| price | Saiga | 800 | 64px | 1.125 | normal | fixed | Price sidebar numeral. |
| heading-lg | Saiga | 900 | 60px | 1.083 | -0.0033em | fixed | Major capability, proof, plan and resource chapter titles. |
| heading | Saiga | 800 | 42px | 1.143 | -0.0048em | size clamp(36px, 29.1px + 0.8929vw, 42px) | FAQ lead and illustrated closing promise. |
| spotlight-heading | Saiga | 800 | 40.3px | 1.15 | -0.005em | size clamp(30px, 17.1px + 1.6071vw, 44px) | Inset gradient announcement heading. |
| spotlight-accent | Saiga | 800 italic | 40.3px | 1.15 | -0.005em | fixed | Short purple conclusion within the announcement heading. |
| subheading | Saiga | 500 | 28px | 1.143 | -0.007em | fixed | Capability headings in alternating image-and-copy chapters. |
| stat | Saiga | 900 | 28px | 1.143 | -0.007em | fixed | Four-column result numerals under a larger proof headline. |
| question | Saiga | 700 | 24px | 1.25 | -0.0083em | fixed | Questions in the broad FAQ accordion. |
| quote | DM Sans | 400 | 24px | 1.1 | normal | fixed | Large customer quotations; selected result phrases become weight 700. |
| hero-support | DM Sans | 400 | 18px | 1.333 | normal | fixed | Narrow centered support beneath the default opening. |
| body | DM Sans | 400 | 18px | 1.5 | normal | fixed | Longer product feature explanations. |
| body-compact | DM Sans | 400 | 16px | 1.3 | normal | fixed | Compact explanations, resource summaries, benefit lists and plan copy. |
| button | DM Sans | 600 | 16px | 1.25 | normal | fixed | Main actions. |
| caption | DM Sans | 400 | 14px | 1.43 | normal | fixed | Navigation and quote attribution. |
| small-button | DM Sans | 600 | 14px | 1.43 | normal | fixed | Compact header conversion control. |
| badge | DM Sans | 700 | 14px | 1.55 | normal | fixed | White technology-commitment badge above the default hero. |
| footer-link | DM Sans | 400 | 14px | 1.43 | normal | fixed | Footer navigation links. |
| footer-heading | DM Sans | 700 | 11px | 1.3 | normal | fixed | Small uppercase footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| journey-led product pages | journey-display | Saiga | 900 | 80px | 85px | -0.0025em | fixed | Short centered outcome promise with a purple sparkle. |
| platform overview pages | overview-display | Saiga | 900 | 80px | 85px | -0.015em | fixed | Two-line platform promise with animated word entrance. |
| journey-led product pages | journey-heading | Saiga | 900 | 44.8px | 1.143 | -0.0045em | size clamp(28.8px, 3.5vw, 44.8px) | Centered journey chapter heading. |
| journey-led product pages | journey-eyebrow | DM Sans | 700 | 16px | 1.3 | 0.12em, uppercase | fixed | Purple chapter framing such as a proof label. |
| managed-service landing pages | service-eyebrow | DM Sans | 700 | 14px | 1.43 | 0.12em, uppercase | fixed | Purple all-cap labels over service proof and demonstration chapters. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The hierarchy mixes nearly equal hero and chapter sizes: 64px opening versus 60px major chapters. Do not make every later heading small.
- Most Saiga roles keep the same -0.2px tracking; the platform overview is a deliberately tighter -0.015em exception.
- Use sentence case and heavy rounded forms, not extended all-cap display typography. Uppercase belongs to small labels.
- Body copy is regular weight. Dense 16px/1.3 copy and 18px/1.5 feature explanations are distinct recipes; quotes use a notably tight 24px/1.1.

## Layout

**Density:** Airy chapter spacing with compact copy inside cards, accordions and navigation.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight text groups, icon gaps and footer link rhythm. |
| 12px | Small labels and utility groups. |
| 16px | Related actions, card title spacing and compact text groups. |
| 20px | Closing-band content gap and compact card padding. |
| 24px | Default page gutters, paragraph separation and resource-grid gap. |
| 32px | FAQ header padding and result-grid gap. |
| 36px | Feature-column gap and plan sidebar padding. |
| 40px | Testimonial card padding and heading-to-support breathing space. |
| 48px | Proof heading-to-results gap and announcement grid gap. |
| 52px | Inner side padding of the main lavender enclosure. |
| 56px | Feature-accordion column gap, promotional-panel padding and FAQ lead gap. |
| 80px | Major section top and bottom padding, opening enclosure offset below navigation. |
| 120px | Short centered integration pitch vertical padding. |

### Containers and grids

- **page-container**: max width 1440px · side padding 24px. Centered page shell with full-width bands escaping the side gutters.
- **enclosed-product**: max width 1300px · side padding 52px. Lavender opening enclosure and broad proof content; at desktop the enclosure leaves 70px outer margins.
- **hero-copy**: max width 600px. Centered support paragraph beneath a much wider headline.
- **feature-split**: 2 columns · gap 36px. Approximately equal image and text columns; alternating sides, images about 654px wide at desktop.
- **accordion-split**: 2 columns · gap 56px. Narrower text accordion beside a larger photographic panel, using a 1:1.4 width relationship.
- **resource-grid**: 3 columns · gap 24px. Three equal resource cards with 16:9 media.
- **family-grid**: max width 1300px · 3 columns · gap 16px. Three tall lavender cross-sell cards with centered copy above bottom-clipped interface artwork.
- **results-grid**: 4 columns · gap 32px. Four centered outcomes, short labels and one numeral per column.
- **closing-container**: max width 1200px · 2 columns · gap 20px · side padding 24px. Copy and illustrated object centered vertically inside the bright closing band.
- **journey-container** (only for journey-led product pages): max width 1240px · side padding 24px. Numbered process narrative with a slim rail, left copy and right product scene.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | product-actions | 32px |
|  | header-actions | 10px |
|  | closing-action | 8px |
|  | hero-and-family-cards | 20px |
|  | testimonials | 12px |
|  | announcement | 24px |
|  | faq-shell | 16px |
|  | plan-panel | 4px |
|  | newsletter | 9999px (pill) |
| immersive managed-service demonstrations | immersive-stage | 48px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | announcement-detail | `rgba(118, 34, 215, 0.08) 0px 4px 24px 0px, rgba(118, 34, 215, 0.06) 0px 1px 4px 0px` | White detail card floating within the pale gradient announcement. |
| immersive managed-service demonstrations | immersive-stage | `rgba(118, 34, 215, 0.25) 0px -30px 120px -20px, rgba(0, 0, 0, 0.5) 0px 40px 60px -15px, rgba(255, 255, 255, 0.05) 0px 0px 0px 1px` | Large demonstration enclosure with a violet halo and deep lower shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #ffffff; color: #121214`

#### Lavender enclosure · level 0

**Use:** Opening and early capability panel.

**CSS:** `background: #f9f5ff; border-radius: 20px; padding: 44px 52px`

**Observed:** One continuous enclosure connects the headline, trust rail and image-led accordion.

**Transfer:** Let the product promise and its first explanation share a single pale stage.

#### Proof wash · level 0

**Use:** Broad proof and adjacent results sections.

**CSS:** `background: linear-gradient(#f9f5ff 0%, #ffffff 100%)`

**Observed:** The direction can reverse when leading into customer proof.

**Transfer:** Use a gentle vertical transition rather than isolated colored cards everywhere.

#### Announcement glow · level 1

**Use:** Inset timely product announcement.

**CSS:** `background: linear-gradient(135deg, #ffffff 0%, #f9f5ff 55%, #e6d5fe 100%); border: 1px solid #e6d5fe; border-radius: 24px; padding: 56px; overflow: hidden`

**Observed:** The pale field has a soft extra violet bloom at the upper right and lower left; a white detail card sits over it.

**Transfer:** Keep the glow diffuse and subordinate to the text.

#### Trust stage · level 1

**Use:** Compact trust rail beneath the opening action.

**CSS:** `background: linear-gradient(#460078 0%, #0a0a0b 80%); border-radius: 20px; color: #ffffff`

**Observed:** A sparse 24px dotted texture and translucent outlined controls provide detail on the dark strip.

**Transfer:** Keep it narrow and purposeful, emphasizing verifiable trust dimensions.

#### Violet payoff · level 0

**Use:** Illustrated closing call.

**CSS:** `background: #a569ff; color: #ffffff`

**Observed:** A broad flat violet field, not a gradient, backs the main closing illustration.

**Transfer:** Reserve strong full-bleed saturation for this decisive moment.

#### Dark footer · level 0

**Use:** Dense site navigation and newsletter.

**CSS:** `background: #121214; color: #e4e4e7`

**Observed:** Muted headings, a fine divider above an acknowledgment line, then a #27272a legal strip.

**Transfer:** Use compact columns and restrained gray contrast after the vivid payoff.

#### Immersive stage · level 1

**Only for:** immersive managed-service demonstrations

**Use:** A contained cinematic product demonstration.

**CSS:** `background: linear-gradient(#460078 0%, #0a0a0b 80%); border: 1px solid rgba(255,255,255,0.08); border-radius: 48px; box-shadow: rgba(118,34,215,0.25) 0px -30px 120px -20px, rgba(0,0,0,0.5) 0px 40px 60px -15px, rgba(255,255,255,0.05) 0px 0px 0px 1px`

**Observed:** White headline above a large inset video, faint dots, then a two-column translucent support panel.

**Transfer:** Use for a genuinely richer demonstration, not as the page-wide default.

#### Journey power-up · level 1

**Only for:** journey-led product pages

**Use:** Solution callout beneath a process pain point.

**CSS:** `background: #f0ebff; border-radius: 14px; padding: 24px`

**Observed:** Small purple uppercase label, bold practical promise and regular explanatory paragraph.

**Transfer:** Turn each problem into a concrete product action.

## Components

### Navigation

**Use:** Persistent desktop header.

**CSS:** `position: sticky; top: 0px; height: 59px; background: #ffffff; border-bottom: 1px solid #e4e4e7; z-index: 1005`

**Text style:** `caption` — DM Sans 400 · 14px/1.43

**Observed:** Logo and a Work/Jobs toggle occupy the left, navigation is centered, search/login/region utilities and a purple 42px-high, 10px-radius action sit at right. Navigation links use 6px 10px padding.

**States:** Declared: hover navigation text #7622D7 with underline.

**Transfer:** Keep this bar low and utility-dense so it does not compete with the heavy hero.

### Primary button

**Use:** Default product conversion action.

**CSS:** `background: #7622d7; color: #ffffff; border: 2px solid #7622d7; border-radius: 32px; padding: 14px 24px; height: 52px; box-sizing: border-box`

**Text style:** `button` — DM Sans 600 · 16px/1.25

**Observed:** A text-led pill, centered in the hero and aligned with copy in feature chapters. Smaller 40px versions occur in compact summaries.

**States:** Declared: hover background and border #460078, color #FFFFFF; transition 0.3s.

**Transfer:** Use one decisive verb phrase; allow width to follow its label.

### Closing button

**Use:** Conversion within the saturated illustrated payoff.

**CSS:** `background: #121214; color: #ffffff; border: 2px solid #121214; border-radius: 8px; padding: 12px 13px; height: 48px; box-sizing: border-box`

**Text style:** `button` — DM Sans 600 · 16px/1.25

**Observed:** A compact black rounded rectangle beneath a small review-badge line, deliberately different from ordinary purple pills.

**States:** Declared: hover background and border #3F3F46, color #FFFFFF; transition 0.3s.

**Transfer:** Keep its rectangular shape scoped to the bright payoff.

### Commitment badge

**Use:** A compact technology or trust statement above the hero breadcrumbs.

**CSS:** `background: #ffffff; border-radius: 8px; height: 40px; padding: 0px 16px; display: inline-flex; align-items: center; position: relative`

**Text style:** `badge` — DM Sans 700 · 14px/1.55

**Observed:** A small purple sparkle precedes the text. A 1px masked multicolor gradient edge wraps the white face.

**Transfer:** State a relevant system-level benefit, not a long promotional sentence.

### FAQ accordion

**Use:** Broad product objection handling.

**CSS:** `background: #f9f5ff; padding: 32px; display: flex; justify-content: space-between; align-items: center; gap: 8px`

**Text style:** `question` — Saiga 700 · 24px/1.25 · tracking -0.0083em

**Observed:** Contiguous rows are about 95px high, within a white 1px #e4e4e7 outlined shell; only the outside top and bottom corners receive 16px rounding. Purple plus signs sit at the far right.

**Transfer:** Use real product questions and reveal answers in place; do not turn every row into a separate floating card.

### Testimonial card

**Use:** Large customer proof carousel.

**CSS:** `background: #ffffff; border: 1px solid transparent; border-radius: 12px; padding: 40px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `quote` — DM Sans 400 · 24px/1.1

**Observed:** Cards are about 420px wide and 526px tall. Customer logo leads, quotation follows with a bold result phrase, then a small attribution and purple case-study link. The right edge fades out to imply more cards; circular outlined arrow controls sit below.

**Transfer:** Keep proof substantial and human; do not substitute short anonymous praise.

### Resource card

**Use:** Three-column educational resource collection.

**CSS:** `background: #ffffff; border: 1px solid #f4f4f5; display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `body-compact` — DM Sans 400 · 16px/1.3

**Observed:** A 446px by 251px image leads; category, 24px Saiga title, compact description and purple arrow link follow. Cards are restrained rectangles rather than strongly rounded floating tiles.

**Transfer:** Use publication mockups, workplace scenes or strong editorial artwork, keeping category and reading action visible.

### Wide plan panel

**Use:** Feature-rich plan explanation with a single price sidebar.

**CSS:** `background: #ffffff; border: 1px solid #bb91eb; border-radius: 4px; display: flex; overflow: hidden`

**Text style:** `body-compact` — DM Sans 400 · 16px/1.3

**Observed:** A broad feature area holds a 42px heading and two columns of purple-check benefits. A 363px-wide #fcfbff sidebar uses 36px padding, a 64px price numeral and compact black pill; a lavender upgrades box sits beneath. A rounded segmented selector sits above the panel.

**Transfer:** Use a wide, calm plan comparison rather than forcing all offerings into equal narrow cards.

### Newsletter field

**Use:** Footer email subscription.

**CSS:** `border: 1px solid #71717a; border-radius: 9999px; height: 42px; display: flex; justify-content: space-between; overflow: hidden`

**Observed:** A 339px-wide outlined capsule sits on the dark footer. The transparent field shares its shell with a light, partially translucent arrow button at right; a consent checkbox and muted explanation follow.

**Transfer:** Keep the field visibly integrated with the footer, not a large white form card.

### Footer columns

**Use:** Dense terminal navigation.

**CSS:** `background: #121214; color: #e4e4e7; padding: 30px 24px 0px`

**Text style:** `footer-link` — DM Sans 400 · 14px/1.43

**Observed:** Small uppercase gray labels lead tight link columns; region flags and social circles add compact utilities, while a wider newsletter column balances the right. A horizontal divider, acknowledgment and darker legal strip finish the page.

**States:** Declared: hover links #7622D7 with underline and 4px underline offset.

**Transfer:** Group links by task; keep 8px link gaps and the dark ending instead of adding another promotional hero.

## Imagery and graphics

### Workplace portrait with result overlays

**Use:** Main capability explanation and alternating product chapters.

**Observed:** Warm, naturally lit business owners or team members are shown at work, often amid real furniture and plants. A lavender mat encloses the photograph and a bold name/company/location caption anchors its bottom. White interface fragments overlap the photograph at opposing corners, pairing purple metrics with lime success checks. The media takes about half the section width.

**Transfer:** Photograph a person doing relevant work and overlay one or two concise result cards. Preserve natural color and human scale rather than recoloring the entire photograph purple.

### Friendly product fragments

**Use:** Standalone feature scenes and cross-sell cards.

**Observed:** White interface cards float on white or lavender, with purple headers, tabular fragments and status chips. Cartoon eyes, currency, pointing hands, rockets and check-medallions add black-outlined sticker accents in violet, lime and cyan. Tall family cards clip larger interface artwork along the lower edge.

**Transfer:** Show only the action or result needed to understand the benefit. A minimum equivalent is one well-typeset white interface panel plus one original playful sticker.

**Build:** Construct a white 12px-radius panel with a faint gray edge and soft local shadow. Add a lavender header, 2–4 simplified data rows and one purple status chip. Draw an original compact SVG sticker with a thick dark contour, violet and lime fill, a white offset outline and a slight rotation; overlap one corner rather than covering the data.

### Gradient announcement atmosphere

**Use:** Pale inset announcement panel.

**Observed:** A white-to-lavender diagonal field has soft blooms at opposing corners; the right-side white explanation card seems gently lifted from it.

**Transfer:** Use the same material for a launch, deadline or newly available capability, with a compact comparison diagram instead of source artwork.

**Build:** Use the Announcement glow surface. Add an absolutely positioned radial gradient, 500px by 350px centered at 90% -10%, rgba(179,130,253,0.18) fading to transparent by 65%; add a lower-left lavender bloom at 10% 110%. Keep content above both layers and match the soft glow; exact secondary stops are not essential.

### Multicolor badge edge

**Use:** The small white commitment badge in the default opening.

**Observed:** A fine luminous border cycles through violet, cyan, pale lavender and lime without filling the badge face.

**Transfer:** Carry this restrained spectral detail into a trust badge; it should remain a tiny fraction of the page's color.

**Build:** Place an 8px-radius absolute layer behind the white badge, with 1px padding and a 90deg gradient through #9a58fc, #70ddff, #e6d5fe, #bafc58 and #9a58fc. Mask out the center, use background-size 300% 100%, and keep the text face white.

### Illustrated closing object

**Use:** The saturated closing payoff.

**Observed:** A plush purple caped character holds a large tilted phone with luminous concentric rings. The cutout has no enclosing card and occupies the right half, about 480px by 276px, balanced against the left-aligned white promise.

**Transfer:** Commission an original friendly character or dimensional product object with tactile material and an oversized device. Minimum equivalent: a polished original vector character beside a tilted device with luminous rings; retain the large cutout silhouette and violet-on-violet staging.

**Build:** For the vector fallback, draw rounded original character shapes with violet midtones, dark-purple shadows and white highlights. Place a dark tilted rounded-rectangle device in front; use concentric purple strokes and a blurred white/cyan center to suggest an active screen. Keep the silhouette clear against the flat bright-violet band.

### Editorial media mosaic

**Only for:** resource-led home and editorial hubs

**Use:** Mixed-density article and video collections.

**Observed:** Natural workplace photos, publication mockups and interview stills mix in a grid. Small article tiles have a 16:9 image and text below; wide video tiles use dark top/bottom scrims, colored category pills and centered circular play buttons. Plain quote cards punctuate the photographic rhythm.

**Transfer:** Alternate two-column video features with smaller article cards, using original editorial material rather than repeating one generic thumbnail.

### Dotted immersive atmosphere

**Only for:** immersive managed-service demonstrations

**Use:** Dark product stage and its lighter explanatory chapters.

**Observed:** Sparse dots and an occasional very faint grid add technical texture without competing with the rounded typography. The large dark stage adds a violet halo and inset translucent support panel.

**Transfer:** Use a contained technical atmosphere for a rich demo; keep the ordinary feature sections light.

**Build:** Tile radial-gradient(rgba(255,255,255,0.15) 1px, transparent 1px) at 24px 24px with opacity 0.5 on a dark gradient stage. For light chapters use #e4e4e7 dots over white. Clip the dark stage to 48px corners and apply the Immersive stage shadow; never make dots high-contrast.

### Icons

**Observed:** Marketing icons combine small filled purple SVGs, 24px purple checks in benefits, 12px rounded-stroke utility chevrons at 1.5px stroke, and larger colorful outlined sticker illustrations. FAQ plus signs and text-link arrows are simple and purple.

**Transfer:** Use restrained monochrome utilities for navigation and controls; reserve the friendly multicolor outlined illustration language for content accents.

## Section recipes

How recurring sections are built.

### First screen: Lavender promise opening

**Observed:** The white 59px sticky Navigation sits above an 80px breathing gap and a centered 1300px Lavender enclosure. Inside, a small Commitment badge and breadcrumb line lead to a heavy two-line headline spanning most of the enclosure width. The display recipe is 64px/68px, weight 900; a 600px-wide, 18px/24px centered support paragraph follows after 24px, then one Primary button after another 24px. Back-to-front layers are white canvas, pale rounded enclosure, tiny spectral badge edge, black headline/support, purple action, and the dark Trust stage below. Within the first 900px the entire promise, support, action and 80px trust rail are visible; the large portrait-and-accordion scene begins below the fold, so there is no oversized hero photograph competing with the headline.

**Transfer:** For a different product, write a two-line audience-and-outcome promise and show three genuine trust dimensions in the rail. The first portrait or simplified product-result scene belongs beneath it. A journey-led page instead opens on white with an 80px short outcome headline, sparkle and early customer logos; a platform overview uses an 80px two-line title on a lavender-to-white field with a video below. A resource hub uses a compact left/right headline-and-action arrangement above a large media banner; a managed service uses a centered 42px promise, two brief explanations and an early illustrative video.

**Avoid:** Do not default to a full-bleed photo, a left-text/right-dashboard hero, three competing CTAs, or an enormous empty lavender area. Preserve the deliberate text-first fold.

**Text style:** `display` — Saiga 900 · 64px/68px · tracking -0.0031em

### Accordion plus human scene

**Observed:** Within the Lavender enclosure, a two-column 1:1.4 composition pairs a narrow explanatory accordion with a larger lavender-matted workplace portrait. The columns are separated by 56px; one item is expanded with copy and a purple action, while later titles are separated by fine rules.

**Transfer:** Use a handful of distinct benefits, one clear expanded story and a human result scene relevant to the new product.

### Announcement spotlight

**Observed:** Announcement glow holds two columns separated by 48px. The left combines a small pill label, Spotlight heading with a short purple italic conclusion, compact copy, three small metrics divided by vertical rules and paired solid/outlined actions. The right uses a white, lavender-edged detail card.

**Transfer:** Apply to a timely feature or meaningful change; show before/after or process detail instead of creating decorative abstract art.

**Text style:** `spotlight-heading` — Saiga 800 · 40.3px/1.15 · tracking -0.005em

### Alternating capability chapters

**Observed:** A centered heading-lg introduces a spacious white section. Beneath it, a roughly half-width 654px product scene faces three Subheading and body groups, with 24px separations and one Primary button. Image placement alternates between chapters; some media are photos with overlays and others are standalone interface fragments.

**Transfer:** Organize around distinct outcomes rather than repeating the same feature inventory. Preserve variety between human scenes and simplified interface scenes.

**Text style:** `heading-lg` — Saiga 900 · 60px/1.083 · tracking -0.0033em

### Quantified proof

**Observed:** A light gradient band pairs a small playful sticker above a centered heading-lg with four result columns. Numerals use Stat rather than the enormous price recipe; labels sit 20px beneath them. A compact outlined action follows after 48px. The journey variant uses purple 48px DM Sans numerals with small uppercase labels and source notes.

**Transfer:** Use substantiated outcomes and units; leave each result visually isolated, without adding dashboard-like chart scaffolding.

### Customer proof carousel

**Observed:** A lavender proof band uses a large left-aligned chapter heading above Testimonial cards. A partially visible right card is softened by a horizontal fade and outlined circular arrows sit below. The managed-service variant includes a near-black dotted rating card among the white quote cards.

**Transfer:** Let one customer outcome per card do the persuading. Recreate the edge fade rather than compressing all cards until every quotation is tiny.

**Text style:** `heading-lg` — Saiga 900 · 60px/1.083 · tracking -0.0033em

### Plans and objections

**Observed:** A centered heading introduces a segmented selector and Wide plan panel. The broad FAQ section then uses a 42px left-aligned lead, 56px lead-to-list gap and FAQ accordion. The journey variant uses two 20px-radius plan cards on pale lavender, one with a stronger purple outline; its conversational objection set has individually spaced 14px-radius white cards.

**Transfer:** Choose the broad feature-and-price composition for a feature-rich plan, or the paired plan cards for a genuinely simple fork. Keep FAQ questions direct and useful.

### Resources and product-family extension

**Observed:** A heading-lg leads three Resource cards separated by 24px. A later centered headline introduces three tall 20px-radius lavender family cards: uppercase category, 28px heavy title, purple action and interface art clipped at the bottom.

**Transfer:** Offer useful next reading and related capabilities without turning this area into a second feature catalogue.

### Illustrated payoff and footer

**Observed:** Violet payoff is 356px tall with a 1200px centered two-column inner layout and 40px vertical padding. A white two-line Heading, small review badges and Closing button occupy the left; Illustrated closing object occupies the right without a card. Dark footer follows immediately, ending in a darker legal strip. The managed-service variant instead uses a centered 296px #9a58fc band with a lime pill, then a broad FAQ and the same footer.

**Transfer:** Carry a friendly, dimensional product payoff into the close. The character or object must be original; a polished vector fallback is acceptable. For service propositions use the scoped centered band when illustration would distract.

**Text style:** `heading` — Saiga 800 · 42px/1.143 · tracking -0.0048em

### Numbered pain-to-power journey

**Only for:** journey-led product pages

**Observed:** A thin vertical rail connects 48px outlined numbered circles. Each step has a small gray uppercase step label, a bold heading and problem statement at left, then Journey power-up below; the right holds a compact product scene. The overall row is about 480px tall with ample separation.

**Transfer:** Use for a workflow with a meaningful transformation at each stage, keeping pain and remedy adjacent rather than creating an exhaustive instruction manual.

## Page flow

**Storyline:** Promise → tangible product or service explanation → trust and outcomes → capability chapters → customer proof → choice and objections → useful next steps → illustrated payoff and dense footer.

### Default detailed product landing page

1. **Promise** — Lavender enclosed headline, narrow support and primary action, followed by compact dark trust rail.
2. **Product explanation** — Accordion beside a workplace portrait with status overlays.
3. **Credibility** — Customer logo strip, timely gradient announcement and four measured outcomes.
4. **Capability chapters** — Alternating product scenes and grouped benefit explanations.
5. **Social proof** — Large quotation cards in a lavender carousel, followed by a compact synthesis and integration pitch.
6. **Choice and objection handling** — Wide plan panel, segmented selector and broad FAQ rows.
7. **Continuation and closing call** — Editorial resources, related capability cards, illustrated violet payoff and dark footer.

**Transfer:** Use the enclosed promise as the default; select narrative blocks according to the new product rather than matching the original page length.

### Resource-led home and discovery hub

1. **Promise** — Compact split headline/support arrangement above a vivid campaign banner and trust logos.
2. **Discovery** — Filter chips and a dense mixed article/video/quote mosaic.
3. **Orientation** — Compact FAQ beside a section lead, then tabbed category navigation and link columns.
4. **Proof and closing call** — Four plain outcome numerals, illustrated violet payoff and shared dark footer.

**Transfer:** Use when visitors need broad discovery rather than a single-product sales narrative.

### Managed-service reassurance page

1. **Promise** — Centered moderate-scale headline, two explanatory paragraphs and one action above an illustrative video.
2. **Service explanation** — Trust rating, three progressively tinted benefit cards and a self-serve versus managed comparison.
3. **Credibility** — Outlined benefit grid, customer carousel with dark rating card, and a large expert-credentials panel.
4. **Product demonstration** — A violet-to-black rounded stage contains an inset video and translucent two-column support strip.
5. **Closing call and objections** — Centered violet band with lime action, broad FAQ, then the dark footer without a second illustrated payoff.

**Transfer:** Emphasize who handles the complexity and what control remains with the reader; use the dark stage as a bounded demonstration.

### Workflow-led product transformation page

1. **Promise** — Short 80px centered outcome claim on white, sparkle, logos and a product video.
2. **Proof** — Purple outcome numerals and a pale capability accordion.
3. **Transformation** — Numbered pain-to-power workflow with alternating text callouts and interface scenes.
4. **Reassurance** — Customer outcome cards, conversational objections and a visual handoff to the wider platform.
5. **Choice and closing call** — Two plan cards, broad FAQ, resources, related capability cards, illustrated violet payoff and dark footer.

**Transfer:** Use the numbered treatment only when the product changes a recognizable sequence of work.

### Platform overview and product directory

1. **Promise** — 80px two-line title over a lavender-to-white gradient with one action and video.
2. **Product exploration** — Tabbed capability showcase with small white product-scene cards on lavender.
3. **Breadth** — A long two-column directory of modest headings, short descriptions and purple links.
4. **Proof and choice** — Quotation carousel, four outcomes and wide feature-rich plan panel.
5. **Audience routing and closing call** — Two illustrated audience cards, gradient-backed FAQ, illustrated violet payoff and shared footer.

**Transfer:** Use for a genuinely broad platform; the long link directory is a scoped browsing pattern, not a default landing-page requirement.

## Writing

Confident, practical and reassuring, with a little playful energy. Big promises are translated into everyday work saved, clearer outcomes and a feeling that the complicated parts are handled.

**Do not copy:** Do not reuse the brand name, wordmark, proprietary mascot, product names, customer logos, testimonials, review ratings, scale claims, performance numbers, prices or regulatory claims. Examples illustrate structure and tone only; replace them with verified material for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your team'; use 'we' for accountable service delivery and product names sparingly for clarity.
- **Rhythm:** Headlines are often 4–9 words, sentence case and punchy; short paired statements sit beside longer explanatory paragraphs. Contractions and occasional ellipses make the voice conversational without becoming jokey.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category and audience, or state an immediate outcome. | 4–9 words | “Payroll software for Australian businesses”<br>“Your next hire is already here.” |
| Capability headline | Translate complexity into a plain result, often contrasting work with busywork. | 4–9 words | “Payroll that just works without the busywork.”<br>“Hiring on autopilot.” |
| Proof framing | Conversational confidence followed by specific proof. | 4–7 words | “The results speak for themselves”<br>“Real teams. Real time saved.” |
| Supporting line | Acknowledge the reader's work, then give a concrete improvement. | One brief sentence or a compact paragraph | “Take people from “Hi” to Hired without switching tabs.”<br>“One platform. Every hiring capability. Fully integrated.” |
| Primary action | Direct verb plus specific next step, not an abstract brand slogan. | 2–5 words | “Request a demo”<br>“Compare options” |
| Objection heading | Ask the question a cautious buyer actually has. | 5–12 words | “But is AI hiring… impersonal?”<br>“Do I still control my team?” |

**Words and phrasing to use:** less admin; more time; all in one; without the busywork; just works; your team; we handle; real results; built-in; one click

**Avoid:** synergistic; paradigm-shifting; unparalleled ecosystem; magic with no explanation; corporate superlatives without proof

**Rules:**

- Follow every automation claim with the task it performs and the human benefit.
- Use contrast pairs to clarify a proposition: less process, more people; one platform, fewer switches.
- Keep technical and compliance terms accurate and explain their effect in ordinary language.
- Reserve playful phrasing for headings and small accents; keep plan descriptions and objections precise.

## Do's and Don'ts

### Do

- Use 64px/68px weight-900 display text for the default promise and keep its supporting paragraph at 600px maximum width.
- Give major chapters real 60px/65px titles so the long page retains its bold voice.
- Preserve the default 24px gutters and 80px section breathing room.
- Keep ordinary product actions at 52px height with 32px corners.
- Mat workplace portraits in lavender and overlap concise white result cards.
- Use 40px padding in large quotation cards and keep the 24px/1.1 quote treatment.
- Finish the illustrated payoff in flat #a569ff and resolve into #121214 footer columns.
- Use the 1px #e4e4e7 outline to organize FAQ rows rather than adding heavy shadows.

### Don't

- Do not replace Saiga-like heavy round headings with thin geometric display type.
- Do not distribute #a569ff across every section; large saturated fields are a payoff, not the base canvas.
- Do not use the 8px-corner closing button as the default product CTA.
- Do not turn ordinary feature copy into a wall of 24px quote-sized paragraphs.
- Do not place thick black borders around white proof cards; their definition comes from pale backing and subtle edges.
- Do not build every feature scene as a full browser dashboard; isolated action fragments are more characteristic.
- Do not cover natural photography in a uniform purple filter; the lavender mat supplies the brand connection.
- Do not apply 48px immersive-stage rounding to resource cards or pricing panels.
- Do not use oversized 64px pricing numerals for every proof metric; ordinary outcomes use the smaller heavy stat recipe.

## Motion and responsive

### Motion

**Observed:**

- Primary and black actions declare 0.3s transitions; navigation links declare color 0.15s.
- The spectral commitment-badge border declares an 8s ease infinite gradient flow.
- The platform title declares 0.2s ease-out word entrances with forwards fill; some journey scenes declare 4s ease-in-out infinite floating.
- Carousels use arrow controls and clipped or faded continuation at the right edge.

**Transfer:**

- Keep the tiny spectral edge as the luminous motion accent instead of animating whole section backgrounds.
- Use the declared action timing for button feedback; keep floating illustration motion scoped to product scenes.

**Unknown:**

- Actual scroll-trigger sequencing and most animation keyframe trajectories are unspecified.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- Desktop compositions are centered at a 1440px viewport.
- The default hero size follows clamp(44px, 21.1px + 2.9762vw, 64px); the 42px heading follows clamp(36px, 29.1px + 0.8929vw, 42px).
- Declared styles include breakpoint families around 767–782px and 1024–1025px.

**Transfer:**

- On narrow screens, preserve the lavender enclosure and promise-first hierarchy; stack the portrait after the accordion rather than squeezing both columns.
- Stack the closing illustration beneath its copy, retaining its cutout silhouette and the distinct black action.
- Allow testimonial continuation to remain horizontally browsable instead of shrinking quotation text; collapse resource and family grids to readable single columns.

**Unknown:**

- Exact mobile header structure, stacking rules and padding values are not established; the stacking guidance is a design recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
