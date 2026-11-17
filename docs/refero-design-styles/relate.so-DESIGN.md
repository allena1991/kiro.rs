# Relate — blue horizons for work

## Overview

An airy, light software-marketing style with a cool blue horizon underneath confident, tightly set grotesk headlines. Near-white interfaces float in translucent frames, with soft blue illumination and restrained product-detail illustrations rather than lifestyle photography. Dark navy is reserved for a compact, self-contained ending; the overall feeling is approachable, organized and product-led.

### Essentials

- A promise sits above a blue horizon: centered 80px/1.05 Inter at 600 with -1.5px tracking, one blue word inside an otherwise midnight headline, and a 400px-wide supporting paragraph.
- Light is a structural device, not decoration: a 1240px-wide, 630px-tall opening stage ends in 44px lower corners, with a blue floor, faint 50px grid and a white center fading into it. Include this luminous staging even when the product has no finished interface.
- The main action is a small porcelain object: the opening uses a 211×56px near-white pill, 50px radius, blue gradient lettering and layered inset blue edges; compact navigation actions instead use 36px blue-gradient pills.
- Most of the page remains near-white: #fcfcfc canvas, #14141e headings and #696a72 supporting text. Saturated #145aff belongs to a single headline word, actions and links; broad color is diffuse blue light, with dark fill concentrated in the 370px closing panel.
- Software is shown at architectural scale: broad 1136×540px interface demonstrations inside 28px translucent outer frames and 16px inner panels, with faint edges and blue ambient shadows. If no interface exists, construct one coherent representative workflow rather than unrelated icon tiles.
- Short verb chapters and soft proof cards punctuate the technical story: 56px/1.05 headings can be a single word with a period; testimonial cards are 800×360px with 40px corners, centered 22px/1.4 quotes and blue names.
- The ending is an inset navy room: a 24px-radius radial-gradient footer, 48px desktop outer margins, left identity and signup form, three narrow link columns on the right, and a fine rule above the bottom metadata.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#145aff` | `--color-blue` | accent, action, link, text | Single emphasized headline word, primary compact actions, text links and customer names. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gradient blue | `#3b82f6` | `--color-blue-top` | action | Lighter upper stop of compact action gradients. |
| Blue lettering shade | `#023f78` | `--color-button-ink` | text | Lower stop of the porcelain action's gradient lettering. |
| Horizon light | `#a1c2fe` | `--color-horizon` | accent | Inset blue illumination at the base of the opening. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer blue-black | `#0f1f3d` | `--color-navy-light` | background, text | Lighter footer stop and deep support text. |
| Midnight headline | `#020520` | `--color-midnight` | text | Opening headline and testimonial quotes. |
| Footer midnight | `#000714` | `--color-navy` | background | Dark starting stop of the inset footer. |
| Heading ink | `#14141e` | `--color-ink` | text | Default section headings and navigation. |
| Supporting gray | `#696a72` | `--color-body` | text | Supporting copy and attribution details. |
| Date gray | `#95959b` | `--color-muted` | text | Subordinate metadata, especially release dates. |
| Reversed gray | `#9fa6b2` | `--color-footer-muted` | text | Visible subdued footer lettering; white at 60% over the navy gradient. |
| Panel hairline | `#e6e6e6` | `--color-edge` | border | Fine feature-card and interface boundaries. |
| Near-white canvas | `#fcfcfc` | `--color-canvas` | background, surface, text | Default page canvas, porcelain action face and reversed navigation labels. |
| Interface white | `#ffffff` | `--color-white` | surface, text | Interface panels, pricing cards and reversed display text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| document-product landing pages | Product label blue | `#2563ff` | `--color-docs-blue` | text, accent | Product chapter labels and localized light fields. |
| document-product landing pages | Lavender support | `#b8ccff` | `--color-lavender` | text, accent | Support text on the purple closing stage and pale blue light. |
| document-product landing pages | Purple closing stage | `#14062d` | `--color-purple-night` | background | Product-specific closing demonstration band. |
| release archives | Release body black | `#000000` | `--color-black` | text | Dense release summaries. |
| pricing pages | Price black | `#090c10` | `--color-price-ink` | text | Plan amounts and controls. |
| document-product landing pages | Product heading black | `#0c0f12` | `--color-docs-ink` | text | Product-specific headline and feature headings. |
| pricing pages | Pricing text | `#15151e` | `--color-pricing-ink` | text | Pricing-page narrative text. |
| release archives | Release heading gray | `#222222` | `--color-release-ink` | text | Release titles. |
| pricing pages | Question charcoal | `#333333` | `--color-faq-title` | text | Question headings. |
| pricing pages | Answer charcoal | `#3d3d3d` | `--color-faq-body` | text | Compact answer paragraphs. |
| release archives | New release orange | `#f36f12` | `--color-new-ink` | text | New-release badge lettering. |
| release archives | Improvement violet | `#4a4fb5` | `--color-quality-ink` | text | Improvement badge lettering. |
| release archives | Peach badge wash | `#fde4cc` | `--color-new-wash` | surface | Visible peach produced by rgba(255,191,128,0.39) over the near-white canvas. |
| release archives | Lilac badge wash | `#e3e4fd` | `--color-quality-wash` | surface | Visible lilac produced by rgba(128,134,255,0.2) over near-white. |

## Typography

- **Inter** — Default display, marketing copy, navigation and testimonials. Contemporary neutral grotesk with a tall x-height and compact, firm semibold headlines. Font stack: "Inter", Arial, sans-serif.
- **Pretendard** — Pricing headings, amounts, answers and a few compact action labels. Clean sans with regular, medium, semibold and bold cuts; the static cut determines the visual weight. Font stack: "Pretendard", Inter, Arial, sans-serif.
- **Roboto Mono** (only for product demonstrations) — Revenue totals and small chart annotations within interface illustrations. Compact technical numerals; not an alternate marketing headline voice. Font stack: "Roboto Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 600 | 80px | 1.05 | -0.0187em | Default opening headline; two centered lines with one blue keyword. |
| heading | Inter | 600 | 56px | 1.05 | -0.0268em | Core section headings and short verb chapters. |
| quote | Inter | 500 | 22px | 1.4 | -0.009em | Centered testimonial quote. |
| support | Inter | 400 | 20px | 1.4 | -0.01em | Opening explanation and centered section support. |
| card-title | Inter | 600 | 20px | 1.5 | normal | Feature-card heading. |
| hero-action | Inter | 500 | 20px | 1.4 | -0.01em | Porcelain opening action. |
| quote-name | Inter | 600 | 18px | 1.5 | normal | Blue author attribution. |
| body | Inter | 400 | 16px | 1.5 | normal | General descriptive copy and footer links. |
| card-body | Inter | 400 | 16px | 1.45 | 0.006em | Short feature-card explanation. |
| nav | Inter | 500 | 16px | 1 | normal | Navigation labels and compact gradient action text. |
| footer-heading | Inter | 500 | 16px | 1 | 0.0125em | Footer column labels. |
| demo-action | Pretendard | 700 | 15px | 1 | normal | Compact secondary demo action. |
| small-proof | Inter | 400 | 15px | 1.2 | 0.007em | Small institutional proof line. |
| caption | Inter | 400 | 14px | 1.25 | 0.007em | Customer role beneath the author name. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| document-product landing pages | product-display | Inter | 600 | 64px | 1.2 | normal | Product-specific centered opening promise. |
| release archives | archive-display | Inter | 600 | 60px | 1.05 | -0.025em | Left-aligned archive introduction. |
| pricing pages | pricing-heading | Pretendard | 600 | 56px | 1.05 | -0.0268em | Pricing intro, proof and FAQ section headings. |
| document-product landing pages | product-heading | Inter | 600 | 48px | 1.2 | normal | Product feature, split-section and FAQ headings. |
| document-product landing pages | product-closing | Inter | 600 | 48px | 1 | normal | Reversed closing demonstration heading. |
| pricing pages | price | Pretendard | 400 | 36px | 1.5 | -0.0333em | Plan amount or Free label. |
| pricing pages | pricing-closing | Pretendard | 700 | 32px | 1.5 | -0.0313em | Left-aligned closing call beside an oversized interface. |
| release archives | release-title | Inter | 600 | 26px | 1.3 | -0.01em | Linked release heading. |
| document-product landing pages | product-support | Inter | 400 | 18px | 1.5 | normal | Product intro and closing support. |
| release archives | release-date | Inter | 500 | 18px | 1 | normal | Date on the timeline rail. |
| release archives | release-body | Inter | 400 | 16px | 1.2 | normal | Release summary below media. |
| release archives | release-link | Inter | 500 | 16px | 1.5 | -0.02em | Read-more link. |
| pricing pages | question | Pretendard | 700 | 16px | 1.4 | normal | Question above a compact answer. |
| pricing pages | answer | Pretendard | 400 | 15px | 1.6 | -0.02em | Compact pricing FAQ answer. |
| document-product landing pages | eyebrow | Inter | 500 | 14px | 18px | -0.01em | Sentence-case blue label in a pale pill above a product chapter. |
| release archives | release-tag | Inter | 700 | 12px | 1 | -0.01em, uppercase | New and improvement category badges. |

**Notes:**

- Inter is the default, not the pricing-page sans. Static Pretendard Bold and SemiBold cuts use visual weights 700 and 600 even when their CSS weight is regular.
- Large default headlines share -1.5px tracking while body support uses -0.01em; product-specific 64px and 48px headings deliberately use normal tracking.
- Keep supporting paragraphs much narrower than the demonstration panels. The opening uses 400px; chapter explanations are generally one or two centered lines.

## Layout

**Density:** Airy marketing composition surrounding dense software examples; page-level pauses are much larger than internal card gaps.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Feature-card heading to description. |
| 8px | Small form or icon relationships. |
| 12px | Footer links and FAQ question-to-answer gap. |
| 16px | Navigation action group and compact internal spacing. |
| 20px | Core section heading-to-support gap and bento gutters. |
| 24px | Product chapter text stack and action separation. |
| 36px | Opening headline-to-support relationship. |
| 40px | Large content grouping and footer row separation. |
| 52px | Demonstration separation and testimonial vertical padding. |
| 60px | Opening stage padding and footer side inset. |
| 64px | Product-section padding and pricing closing call vertical padding. |
| 80px | Heading group to feature grid and pricing FAQ grid. |
| 92px | Major page-block separation. |

### Containers and grids

- **Marketing stage**: max width 1400px · side padding 100px. Centered desktop composition; opening has 1240px available at 1440px.
- **Demonstration container**: max width 1200px · side padding 40px. Broad UI examples and feature grids; reference content occupies 1160px.
- **Asymmetric bento**: 11 columns · gap 20px. Four feature panels alternate six- and five-column spans across two rows.
- **Footer columns**: max width 500px · 3 columns · gap 55px. Three approximately 130px link columns opposite identity and signup.
- **Archive** (only for release archives): max width 1024px · side padding 20px. Date rail at left and a 720px content column at right.
- **Pricing content** (only for pricing pages): max width 1200px · side padding 0px. Paired two-plan groups, long comparison table and closing call.
- **FAQ grid** (only for pricing pages): max width 1192px · 3 columns · gap 32px. Two rows of equal question cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Opening lower corners | 44px |
|  | Hero action | 50px |
|  | Compact actions | 500px |
|  | Feature cards | 20px |
|  | Interface inner panel | 16px |
|  | Glass outer frame | 28px |
|  | Testimonials | 40px |
|  | Footer | 24px |
|  | Form input | 12px |
| document-product landing pages | Product actions | 10px |
| pricing pages | FAQ cards | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Blue interface aura | `rgba(20, 90, 255, 0.1) 0px 0px 100px -28px` | Large interface panel, surrounded by blue illumination. |
|  | Opening edge light | `rgb(161, 194, 254) 0px -4px 62px 5px inset` | Luminous lower edge of opening stage. |
|  | Testimonial lift | `rgba(0, 0, 0, 0.082) 0px 0.4px 1.8px -1.4px, rgba(0, 0, 0, 0.07) 0px 1.4px 6.9px -2.8px, rgba(0, 0, 0, 0.016) 0px 6px 30px -4.3px` | Soft layered testimonial elevation. |
| pricing pages | FAQ lift | `rgba(9, 12, 16, 0.03) 0px 12px 40px 0px` | Faint shadow under white FAQ cards. |

### Surfaces

#### Canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #fcfcfc`

#### Horizon stage · level 1

**Use:** Opening luminous stage.

**CSS:** `background: radial-gradient(41.9% 83.8% at 50% 36.7%, #fcfcfc 0%, rgba(252, 252, 252, 0) 100%); border-radius: 0px 0px 44px 44px; box-shadow: rgb(161, 194, 254) 0px -4px 62px 5px inset; overflow: hidden`

**Observed:** The upper field almost disappears into the canvas; lower blue light and a faint grid emerge beneath the support and action.

**Transfer:** Layer the blue floor and grid behind this surface's white radial veil.

#### Glass demonstration frame · level 1

**Use:** Outer backing around a large product example.

**CSS:** `background: rgba(252, 252, 252, 0.2); border: 1px solid rgba(255, 255, 255, 0.15); border-radius: 28px; padding: 12px; backdrop-filter: blur(5px)`

**Observed:** A translucent rim surrounds a white inner interface, keeping the blue ambient backing visible at the edges.

**Transfer:** Use a single coherent product view with readable focal details.

#### Feature outline · level 1

**Use:** Feature-panel shell.

**CSS:** `border: 1px solid #e6e6e6; border-radius: 20px; overflow: hidden`

**Observed:** Almost flush with the canvas; faint light inside and oversized UI clipping create hierarchy instead of a heavy shadow.

**Transfer:** Place text at one end and let a useful UI fragment occupy the rest.

#### Navy ending · level 1

**Use:** Shared inset footer.

**CSS:** `background: radial-gradient(86.9% 191.973% at 5.7% 15.5%, #000714 0%, #0f1f3d 100%); border-radius: 24px; padding: 40px 60px 32px; overflow: hidden`

**Observed:** A subtle grain overlays the dark field without competing with navigation.

**Transfer:** Use understated texture and subdued reversed copy, not a full-page dark theme.

#### Product controls band · level 1

**Only for:** document-product landing pages

**Use:** Alternating explanation and small product illustrations.

**CSS:** `background: rgb(244, 244, 244); border-radius: 30px; padding: 64px 84px 74px`

**Observed:** A pale cool cast and very soft glows keep the wide gray band from feeling flat.

**Transfer:** Group related controls or customization details inside one quiet band.

#### Purple demonstration close · level 1

**Only for:** document-product landing pages

**Use:** Product-specific final conversion stage.

**CSS:** `background: #14062d; border-radius: 30px; overflow: hidden`

**Observed:** White heading, lavender support and paired actions sit above a large white interface that runs below the section edge; blue and violet glows illuminate it.

**Transfer:** Repeat the product promise in one line and stage a final demonstration, not just an isolated button.

#### Plan card · level 1

**Only for:** pricing pages

**Use:** White individual plans inside translucent paired groups.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 8px`

**Observed:** Each card has a second 16px internal inset; the recommended plan has a fine blue edge, Popular flag and a soft 0px 4px 56px shadow at black 8%.

**Transfer:** Equalize plan anatomy and align price and action rows; reserve emphasis for one paid plan.

## Components

### Navigation

**Use:** Persistent desktop wayfinding.

**CSS:** `background: rgba(252, 252, 252, 0.396); backdrop-filter: blur(4.5px); padding: 24px 100px; display: flex; align-items: center`

**Text style:** `nav` — Inter 500 · 16px/1

**Observed:** A 90px sticky header holds a floating translucent capsule. Identity and menu items are left; login, outlined Demo button and blue Compact button are right. Menus use tiny light chevrons. The capsule becomes more apparent over content.

**Transfer:** Preserve the left/right grouping and compact height; use a pill-shaped outer silhouette.

### Hero button

**Use:** Default main action in the opening.

**CSS:** `background: #fcfcfc; border-radius: 50px; padding: 14px 32px; height: 56px; backdrop-filter: blur(2px); box-shadow: rgba(71, 136, 255, 0.675) 0px -0.3px 0.2px -1.2px inset, rgba(71, 136, 255, 0.608) 0px -1.1px 0.9px -2.3px inset, rgba(71, 136, 255, 0.3) 0px -5px 4px -3.5px inset, rgba(0, 0, 0, 0.18) 0px 0.6px 0.6px -1.3px, rgba(0, 0, 0, 0.16) 0px 2.3px 2.3px -2.5px, rgba(0, 0, 0, 0.063) 0px 10px 10px -3.8px`

**Text style:** `hero-action` — Inter 500 · 20px/1.4 · tracking -0.01em

**Observed:** Centered alone beneath the opening paragraph. Lettering has a 177deg blue-to-deep-blue text gradient; no trailing icon in this default variant.

**Transfer:** Keep the porcelain face and blue edge light even if the action wording changes.

### Compact button

**Use:** Navigation conversion action.

**CSS:** `background: linear-gradient(#3b82f6 0%, #145aff 100%); color: #fcfcfc; border-radius: 500px; padding: 10px 20px; height: 36px`

**Text style:** `nav` — Inter 500 · 16px/1

**Observed:** Sits after the secondary action. Pricing variants are 40px tall, radius 70px and commonly 220px wide, with a right arrow.

**Transfer:** Use the blue fill for conversion rather than for every navigation item.

### Demo button

**Use:** Secondary action in navigation.

**CSS:** `background: #fcfcfc; color: #145aff; border-radius: 500px; padding: 10px 20px; height: 36px`

**Text style:** `demo-action` — Pretendard 700 · 15px/1

**Observed:** Visually outlined in pale blue, positioned between login and the filled action.

**Transfer:** Retain a lighter visual weight than the adjacent blue action.

### Feature card

**Use:** Bento summary of a capability.

**CSS:** `border: 1px solid #e6e6e6; border-radius: 20px; overflow: hidden; display: flex; flex-direction: column; gap: 32px`

**Text style:** `card-title` — Inter 600 · 20px/1.5

**Observed:** Title and card-body copy have 40px side insets and 36px top inset. Panels are roughly 516–624px wide and 360–400px high; UI fragments or integration badges fill the remaining area. Text can sit above or below the media.

**Transfer:** Give each card a distinct useful artifact, not the same icon-and-paragraph pattern.

### Testimonial card

**Use:** Human proof in a horizontal strip.

**CSS:** `background: #fcfcfc; border-radius: 40px; padding: 52px 72px; width: 800px; height: 360px; display: flex; flex-direction: column; align-items: center; gap: 28px; box-shadow: rgba(0, 0, 0, 0.082) 0px 0.4px 1.8px -1.4px, rgba(0, 0, 0, 0.07) 0px 1.4px 6.9px -2.8px, rgba(0, 0, 0, 0.016) 0px 6px 30px -4.3px`

**Text style:** `quote` — Inter 500 · 22px/1.4 · tracking -0.009em

**Observed:** Customer wordmark above the centered quote; blue quote-name and gray caption below. Adjacent cards are 44px apart, partially visible through an edge fade.

**Transfer:** Keep a substantive quote and named role; the logo may be replaced with a simple customer name.

### Footer column

**Use:** Compact navigation within Navy ending.

**CSS:** `width: 130px; display: flex; flex-direction: column; gap: 24px; color: #fcfcfc`

**Text style:** `footer-heading` — Inter 500 · 16px/1 · tracking 0.0125em

**Observed:** Heading followed by body links at white 60% with 12px vertical gaps; three columns form the right-hand group.

### Footer signup

**Use:** Low-pressure subscription inside Navy ending.

**CSS:** `background: rgba(255, 255, 255, 0.08); border-radius: 12px; padding: 15px; width: 326px; height: 48px`

**Observed:** Email input alongside a small 86×48px Sign Up control with white at 80% and matching rounded corners. The pair sits below identity, tagline and small social icons.

### Chapter pill

**Only for:** document-product landing pages

**Use:** Product-section categorization.

**CSS:** `background: linear-gradient(91.9138deg, rgba(37, 99, 255, 0.05) 0%, rgba(37, 99, 255, 0) 100%); border-radius: 48px; padding: 8px 16px; color: #2563ff`

**Text style:** `eyebrow` — Inter 500 · 14px/18px · tracking -0.01em

**Observed:** A faint blue perimeter makes the pale pill distinct from its ground; it remains sentence case, never a wide uppercase banner.

### Product button

**Only for:** document-product landing pages

**Use:** Product access action alongside a white demo action.

**CSS:** `background: #145aff; color: #fcfcfc; border-radius: 10px; padding: 15px 20px 15px 24px; height: 53px; box-shadow: rgba(20, 90, 255, 0.12) 0px 1px 10px 0px`

**Observed:** Semibold 16px/20px Inter label followed by a right arrow. The white secondary action shares the shape and can end with a calendar icon.

**Transfer:** Keep this squared-off action family limited to the product-specific variant.

### Release link

**Only for:** release archives

**Use:** Continuation below each release summary.

**CSS:** `color: #145aff; text-decoration-line: none`

**Text style:** `release-link` — Inter 500 · 16px/1.5 · tracking -0.02em

**Observed:** Plain inline action; title links remain charcoal and do not gain an underline.

**States:** Declared: hover color #145aff and underline; focus-visible unknown.

### FAQ card

**Only for:** pricing pages

**Use:** Always-visible answer in a compact grid.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 32px; display: flex; flex-direction: column; gap: 12px; box-shadow: rgba(9, 12, 16, 0.03) 0px 12px 40px 0px`

**Text style:** `question` — Pretendard 700 · 16px/1.4

**Observed:** A question above answer text in a 376×170px card. No accordion chrome; the answer is immediately visible.

**Transfer:** Write short answers that fit a balanced grid without clipping.

## Imagery and graphics

### Blue horizon and grid

**Use:** Signature opening light field and ambient backing for product scenes.

**Observed:** White upper space gradually opens into a periwinkle-blue floor. A very fine rectilinear grid becomes visible only near the base; cyan-white light washes the center. Text stays crisp and dark over the bright region.

**Transfer:** Always provide this luminous foundation. For a product without artwork, pair it with a clean representative interface or process visualization.

**Build:** Inside a 1240×630px rounded-bottom stage, place a blue linear-gradient floor behind a white radial veil centered near 50% 36.7%. Draw 1px white lines at approximately 50px intervals using two repeating linear gradients at low alpha, mask them toward the bottom, then apply the Opening edge light inset shadow. Add large blue blurred ellipses at the sides of subsequent demonstrations; keep their centers out of the text.

### Broad interface demonstration

**Use:** Main proof immediately following the opening and within capability chapters.

**Observed:** Bright white software views with small neutral text, pale gray sidebars and tiny blue, green and red status cues. Interfaces occupy most of the section width, inside Glass demonstration frame; surrounding glows are much softer than the UI. The first panel is 1232×798px, later chapter panels 1136×540px.

**Transfer:** Show a representative task using your own data. Keep the full panel architectural but choose one legible focal operation; product-only colors stay inside the UI.

### Feature artifacts

**Use:** Feature card media.

**Observed:** Cropped white interface panels, a small blue line chart with a monospaced revenue amount and floating target labels, and staggered white integration-name tiles. Media can exceed the card boundary and fades into the near-white surface; chart and badge artifacts are subordinate to the headings.

**Transfer:** Use task-relevant UI, integrations or a small real metric visualization. Keep numerals technical only inside the demonstration, not as a competing marketing display.

### Navy grain

**Use:** Textured backing in the ending.

**Observed:** Very subtle fine-grained texture over a nearly black-to-navy gradient; not a starfield, photograph or bold illustration.

**Transfer:** Keep the material barely visible so the ending feels like a dark inset slab.

**Build:** Overlay a monochrome SVG turbulence texture at low opacity over Navy ending. Use fine noise rather than large mottled patches; clip everything to the 24px corners.

### Product grain stage

**Only for:** document-product landing pages

**Use:** Distinct product-opening backdrop and its final demonstration echo.

**Observed:** An almost white top descends through cyan into saturated blue-violet with fine visible grain. A large white software panel is tilted slightly in perspective, backed by a thick pale rim and a long soft shadow. The closing version uses a deep purple field and blue-violet glow.

**Transfer:** Use the same bright-to-saturated vertical atmosphere for a specialized product page, rather than changing the whole brand theme.

**Build:** Layer a white-to-cyan-to-blue vertical gradient with a violet radial pool near the bottom; place a fine SVG turbulence layer over it at low opacity. Add a centered white interface with 20px corners, a pale outer rim, slight perspective tilt and a broad shadow extending below. For the dark close, put 586–766px blue/violet circles behind the panel, blur 100px and reduce opacity to 0.3.

### Small control illustrations

**Only for:** document-product landing pages

**Use:** Split feature chapters and the gray controls band.

**Observed:** Small white floating browser cards, password fields, upload zones and blue action chips. Rounded avatar cutouts and a loose blue loop-arrow make an integration illustration more human; the UI fades to white at its outer edges.

**Transfer:** Illustrate a real operation with two or three layered control fragments, pale blue outlines and one vivid active control.

**Build:** Construct white rounded rectangles with faint gray shadows; use a pale-blue dashed upload zone or password field and a small blue circular control. For transfer between systems, connect the UI fragments with one curved SVG blue arrow, round caps and a loop; float a few 48–64px circular portraits along its route.

### Release cover images

**Only for:** release archives

**Use:** Repeated 720×411px editorial media.

**Observed:** Rounded covers vary by era: white or pale-gray announcement typography, blue-gradient release posters, or software panels over black folded-wave backdrops. Typography inside artwork can be serif and is distinct from the surrounding Inter archive system.

**Transfer:** Create coherent release-specific cover art at the same aspect ratio. Do not promote cover-art serif type or black wallpaper into the default marketing language.

### Icons

**Observed:** Small light outline glyphs support navigation and product controls; chevrons are around 10px, action arrows and calendar symbols around 16–24px. Social marks are compact monochrome silhouettes. Product illustrations mix simple black outline symbols and blue filled controls.

**Transfer:** Use a consistent light-stroke icon set for functional chrome. Keep arrow and calendar icons at the label's trailing edge; avoid oversized multicolor feature icons.

## Section recipes

How recurring sections are built.

### First screen: Horizon opening

**Observed:** A 90px navigation strip precedes a centered, 1240×630px Horizon stage. Back-to-front layers are blue floor and faint grid, white radial veil, a small proof line, two-line display headline, narrow support and Hero button. The headline spans roughly three fifths of the stage and uses one blue word inline, not a separate colored line. Support is 400px wide with 36px separation from the headline; the isolated action rests in the blue-lit lower zone. Within the first 900px the complete promise, support, action and rounded stage are visible, plus the top edge of a large white product interface beginning 92px below the stage. Most of that interface is below the fold.

**Transfer:** Keep the promise centered and put one product-defining word in blue. Recreate the horizon using Blue horizon and grid, then build an authentic task view below it if no finished media exists. Pricing opens instead with a left-aligned 56px heading and billing control; archives open with a left-aligned 60px title and short subscription invitation. A specialized product opening uses product-display over Product grain stage with paired actions.

**Avoid:** Do not put a dashboard beside the main headline, fill the entire opening dark, or replace the horizon with a generic floating blob.

**Text style:** `display` — Inter 600 · 80px/1.05 · tracking -0.0187em

### Verb chapter

**Observed:** Centered heading at 56px followed 20px later by support, then a broad Glass demonstration frame. White product UI fills most of the chapter; 40–52px separates major content groups. Single-word period-ended headings create a brisk rhythm.

**Transfer:** Choose short verbs that describe the reader's workflow, and prove each with a distinct interface state.

**Text style:** `heading` — Inter 600 · 56px/1.05 · tracking -0.0268em

### Paired smaller chapters

**Observed:** Two 570px-wide demonstration panels use 16px corners with extremely faint blue wash. Short 40px headings and 18px support pair with dense tabular UI; the arrangement balances text and UI across the row.

**Transfer:** Use paired treatments for related outcomes that do not each need a full-width chapter.

### Asymmetric feature grid

**Observed:** Heading and support sit 80px above the Asymmetric bento. Feature card spans alternate wider/narrower across rows. Oversized artifacts are clipped by Feature outline; headings and text do not all occupy the same corner.

**Transfer:** Vary artifact placement while keeping the shared text inset, border and corner construction.

### Customer proof strip

**Observed:** A centered heading and support introduce Testimonial card items on a horizontal track. Cards have 44px gaps; an edge mask fades from transparent to opaque over the first 12.5% and reverses over the final 12.5%. Logos, quote, author and role remain centered.

**Transfer:** Use authentic proof in the same wide card format; retain partial neighboring cards and edge fade even in a static strip.

### Product split explanation

**Observed:** Chapter pill, product-heading, body and actions form a 512px text column opposite a roughly 495×480px illustration. Related control details alternate sides within Product controls band. Text stacks use 24px gaps.

**Transfer:** Use this scoped layout for explaining discrete product operations rather than making all core sections split columns.

**Text style:** `product-heading` — Inter 600 · 48px/1.2

### Product questions and close

**Observed:** A centered Chapter pill and 48px FAQ heading precede three 700×75px question rows with 20px corners. Then Purple demonstration close repeats the promise in white, lavender support, paired Product button actions and a large overflowing interface. Navy ending follows after a generous pause.

**Transfer:** Use expandable question rows for product setup objections; reserve the purple stage for the specialized product conversion moment.

**Text style:** `product-heading` — Inter 600 · 48px/1.2

### Pricing opening and comparison

**Observed:** A left-aligned, three-line pricing-heading occupies about half of a 1200px container; monthly/yearly control sits toward the lower right. Four Plan cards are grouped into two translucent paired wrappers with pill group labels. Below ancillary offer rows and a logo proof block, a centered comparison heading introduces a long six-column table: one label column and five centered plan columns. Rows use 28px vertical padding, faint rules and small blue check circles; category headings repeat the plan names.

**Transfer:** Keep the commercial story direct and scannable; use groups only when plans truly serve different audience classes.

**Text style:** `pricing-heading` — Pretendard 600 · 56px/1.05 · tracking -0.0268em

### Pricing proof and objections

**Observed:** Detailed customer-story panels pair challenge/outcome prose with short quantified results. The Customer proof strip is followed by a centered FAQ heading and six FAQ card items in three columns with 32px gaps. A 1200×372px translucent closing call uses 64px vertical and 48px side padding, a 32px heading at left, blue action and an oversized product panel clipped at right; Navy ending concludes the page.

**Transfer:** Show proof before addressing billing objections; adapt the closing sentence and UI to the new product.

**Text style:** `pricing-heading` — Pretendard 600 · 56px/1.05 · tracking -0.0268em

### Release timeline

**Observed:** A 1024px left-aligned introduction has 120px top padding, support and a blue follow link. A very pale rounded subscription band pairs copy with a 504×52px email input. The timeline puts 18px gray dates and tiny ringed dots on the left, with a 720px article column on the right. Each article has a 26px title and peach New or lilac improvement pill, cover image after about 25px, summary 40px below media and Release link 12–14px later. Entries have 52px lower breathing room; the final oldest entry is followed by Navy ending.

**Transfer:** Use chronological proof for an evolving product; retain the date rail, large media and short summaries rather than collapsing releases into cards.

**Text style:** `release-title` — Inter 600 · 26px/1.3 · tracking -0.01em

### Inset ending

**Observed:** Navy ending is a 1344×370px panel inset 48px from the desktop edges, leaving 60px of canvas below. Identity, muted tagline and social icons sit left above Footer signup. Three Footer column groups sit right. A subtle horizontal rule separates the upper content from small legal text at left and institutional proof at right. It is a self-contained slab, not an edge-to-edge band.

**Transfer:** End each page type with this dark room; adapt link groups and form purpose to the new product.

## Page flow

**Storyline:** Promise → substantial product demonstration → trust → workflow chapters → capability details → customer proof or objections → inset ending.

### Broad software marketing landing page

1. **Promise** — Centered Horizon opening with one blue keyword and isolated porcelain action.
2. **Product demonstration** — Large glass-backed interface followed by compact logo proof.
3. **Capability chapters** — Short verb chapters with broad task views, then paired smaller outcomes.
4. **Capability details** — Asymmetric bento mixing UI fragments, integrations and a chart.
5. **Social proof** — Wide fading testimonial strip.
6. **Ending** — Inset navy footer with signup and link groups.

**Transfer:** Adapt the chapter sequence to the product journey while retaining luminous staging and substantial interface proof.

### Focused product explanation and access conversion

1. **Promise** — 64px centered headline over a grainy cyan-to-blue product stage, paired actions and perspective UI.
2. **Trust** — Small two-row logo proof.
3. **Product demonstration** — Centered chapter lead above a media panel with four vertical feature tabs.
4. **Capability chapters** — Integration split section and alternating control/customization illustrations in a gray band.
5. **Objection handling** — Narrow rounded FAQ rows.
6. **Closing call** — Deep-purple illuminated stage with white headline and overflowing software view.
7. **Ending** — Shared navy footer.

**Transfer:** Use the stronger product-specific gradient and rectangular action family only for a focused product story.

### Release archive demonstrating ongoing improvement

1. **Introduction** — Left title, short support and follow link.
2. **Subscription** — Pale horizontal invitation with inline email entry.
3. **Chronological proof** — Long date-rail timeline with title, status pill, large release cover, short summary and read-more link.
4. **Ending** — After the oldest release, shared navy footer.

**Transfer:** Let updates determine length; repeat a stable editorial anatomy rather than inventing landing-page chapters.

### Commercial decision and objection handling

1. **Pricing** — Left promise, billing toggle, grouped plan cards and ancillary offer rows.
2. **Trust** — Logo proof preceding a long comparison table.
3. **Comparison** — Repeated category headings, five plan columns and restrained check indicators.
4. **Quantified proof** — Customer challenge/outcome panels followed by testimonial strip.
5. **Objection handling** — Six always-visible question cards.
6. **Closing call** — Light translucent panel with conversion copy and oversized product view.
7. **Ending** — Shared navy footer.

**Transfer:** Keep plan cards, comparison, billing objections and conversion distinct; do not turn the pricing page into the default visual theme.

## Writing

Direct, practical and lightly optimistic. It sells simpler work through recognizable tasks and concrete outcomes, with occasional human warmth rather than grand technological language.

**Do not copy:** Do not reuse the Relate name, logo, customer marks, customer names or quotes, investor affiliation, price points, product-specific claims or measured outcomes. Use truthful equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for benefits and setup questions; refer to the product by name in explanations. Use we chiefly for updates and service answers.
- **Rhythm:** Brief category-and-audience hero promises, single-word workflow chapters and one or two explanatory sentences. Actions are short verb phrases; FAQ answers are conversational and can begin with a direct yes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product category and audience, or connect two familiar ideas. | 5–10 words | “Modern Sales CRM for B2B companies”<br>“Where PDF doc meets Google Analytics” |
| Chapter heading | One concrete workflow verb with a period. | 1 word | “Prospect.”<br>“Close.” |
| Supporting line | Explain the task and immediate benefit without abstract slogans. | 12–25 words | “Engage in sales opportunities as a team. Build and accelerate your sales pipeline.” |
| Feature heading | A plain capability or a task converted into an outcome. | 3–10 words | “Turn views into purchases”<br>“Custom branding and taglines” |
| Primary action | Verb plus a low-friction destination or condition. | 2–4 words | “Get started free”<br>“Schedule a demo” |
| Release summary | Say what users can now do. | 1–2 sentences | “You can now schedule emails in [Brand]” |
| Question | Use a real first-person buying objection. | 5–10 words | “Can I cancel my subscription?” |

**Words and phrasing to use:** simple; clean; in one place; track; connect; manage; custom; you can now; get started

**Avoid:** revolutionary; unleash; limitless; game-changing; AI magic; enterprise synergy

**Rules:**

- Lead with the operation a reader recognizes; explain the benefit in the next line.
- Use short chapter verbs to create pace without making every heading a slogan.
- Keep primary action labels stable across the page.
- Use real customer outcomes only when substantiated; keep qualifiers and context visible.
- Warmth can appear in an informal customer-proof heading or a friendly answer; keep product instructions literal.

## Do's and Don'ts

### Do

- Keep default display type at 80px/1.05 and 600 with -1.5px tracking.
- Use only one blue word in the main headline and keep its baseline continuous with the surrounding ink text.
- Keep the opening explanation at 400px wide so it stays subordinate to the promise.
- Preserve 92px pauses between major blocks and 20px heading-to-support spacing in core chapters.
- Show real workflow panels at roughly 1136px wide, with a 12px translucent outer rim.
- Use 20px bento corners but 40px testimonial corners; they serve different kinds of content.
- Make the dark ending inset with 24px corners and 60px internal side padding.
- Keep FAQ cards on pricing pages compact at 32px padding and 12px question-to-answer spacing.

### Don't

- Do not use 800-weight display type; the headline's firmness comes from 600 weight and tight spacing.
- Do not apply the 10px product-action radius to the default porcelain hero action.
- Do not turn faint panel boundaries into thick dark strokes; the core bento edge is 1px #e6e6e6.
- Do not use customer-avatar photography as a large hero backdrop; portraits belong to small interface or integration details.
- Do not make every feature card the same width and text/media arrangement; alternate the six/five-column emphasis.
- Do not enlarge release badges into decorative banners; their text is 12px with 8px 12px padding.
- Do not use the serif lettering inside release-cover art as the site's heading font.
- Do not turn the footer's navy into the default page background or spread saturated violet across ordinary sections.

## Motion and responsive

### Motion

**Observed:**

- Release continuation links declare a blue underline on hover; release title links retain charcoal without an underline.
- The testimonial strip uses a translated horizontal track and edge masking. The navigation remains sticky while reading.

**Transfer:**

- Retain the testimonial track's partial neighboring cards and edge fade; the static composition should still read as a strip.
- Preserve header legibility over both light product views and the dark closing regions.

**Unknown:**

- No reliable duration, transition or animation timing is established for the glass header, chapter entrances or testimonial movement.
- Focus-visible and pressed treatments for conversion buttons are unspecified.

### Responsive

**Observed:**

- Width breakpoints occur around 810px, 1000px, 1200px and 1400px.

**Transfer:**

- On narrow layouts, preserve the centered horizon and one blue inline keyword; let the promise wrap naturally without creating a separate colored slogan.
- Stack paired demonstrations and pricing groups while retaining their distinct outer wrappers. Keep the product panel as one intentional view rather than shrinking its entire text to illegibility.
- Reduce the testimonial panel to the reading width while keeping a hint of the adjacent card; let footer identity, signup and link groups stack inside the inset navy slab.

**Unknown:**

- Exact narrow-screen font sizes, navigation replacement and table overflow behavior are unspecified; these are adaptation rules rather than fixed mobile measurements.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
