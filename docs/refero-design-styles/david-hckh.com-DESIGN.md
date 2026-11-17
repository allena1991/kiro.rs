# David Heckhoff — toy worlds, technical soul

## Overview

A personable, playful portfolio language that puts soft toy-like 3D worlds next to emphatic geometric sans-serif lettering and small retro-computer labels. Warm cream, brown-black and orange frame the main marketing experience, with vivid blue technical scenes providing theatrical contrast. Spacious compositions and compact controls suit interactive products, creative software and maker-led launches; detailed product stories shift to restrained light or navy galleries.

### Essentials

- Big friendly lettering meets a crooked technical sticker: Urbanist 88px/96px at 900 with 0.02em tracking, paired with white 28px bold monospace on a navy label rotated −5deg.
- The opening is a room, not a card: a 900px-high full-bleed cream stage reserves roughly the left third for a two-line title while a softly lit 3D scene fills the right and lower edges. Use a rounded product-object diorama when there is no character artwork.
- Controls feel like small physical tokens: the main action is a 44px-high orange pill with 26px horizontal padding; companion utilities are 44px circles with 24px icons.
- Color lives in the theater rather than the prose: cream and brown-black dominate the ordinary marketing shell, orange is concentrated in actions and active navigation, and saturated imagery occupies entire media frames. A blue technical interlude contrasts with the warm scenes instead of tinting every section.
- Demonstration becomes an illuminated exhibit: include a dark-blue inspection scene with cyan outlines, a perspective grid, a circular pedestal and short connected labels. A simple outlined product silhouette on the same luminous base is the minimum equivalent.
- Proof is image-first and the goodbye is a scene: 16px-rounded landscape previews carry 22px titles underneath, while a monumental 72px/80px invitation shares a full-height closing diorama with small circular contact actions.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sticker navy | `#263c70` | `--color-sticker` | surface | Tilted role and selection labels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange | `#ff8400` | `--color-orange` | action, accent | Primary conversion pill and active section marker; not broad content backgrounds. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sand edge | `#dfd2bf` | `--color-edge-strong` | border, surface | Invitation tile dashed edge and audio control backing. |
| Soft sand | `#f1e5d5` | `--color-sand` | surface | Navigation tray and preview media backing. |
| Brown black | `#2d2a24` | `--color-ink` | text, action | Main headings, navigation, icons and hover fills. |
| Warm secondary ink | `#5f5646` | `--color-muted` | text | Short project descriptions and the invitation tile icon. |
| Cream edge | `#e9ded0` | `--color-edge` | border, surface | Outlined footer controls and the dashed invitation tile fill. |
| Warm cream | `#f5efe6` | `--color-canvas` | background, surface | Default marketing canvas, sticker outline and contact icon backing. |
| White | `#ffffff` | `--color-white` | text, background, surface | Reversed action and sticker text; also the light case-study canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark case studies | Raised blue band | `#364e7c` | `--color-night-band` | background, surface | Large gallery surround and caption tabs. |
| dark case studies | Night edge | `#2b4169` | `--color-night-edge` | surface, border | Utility circles and subtle next-item outlines. |
| dark case studies | Night canvas | `#1c2f4f` | `--color-night` | background, surface | Case-study canvas and media backing. |
| dark case studies | Dark-theme action blue | `#008dff` | `--color-night-blue` | action | Conversion and live-demo buttons. |
| light case studies | Light-theme action blue | `#1f81f9` | `--color-case-blue` | action | Conversion pill and circular back navigation. |
| light case studies | Cool ink | `#141d25` | `--color-case-ink` | text, action | Light case-study text and hover fill. |
| light case studies | Slate caption | `#485561` | `--color-case-muted` | text | Next-item prefix. |
| dark case studies | Pale slate | `#c3ccdb` | `--color-night-muted` | text | Next-item prefix. |
| light case studies | Cool edge | `#e2e9ee` | `--color-case-edge` | surface, border | Utility circles, language outlines and next-item border. |
| light case studies | Ice gallery | `#f3f7fa` | `--color-case-canvas` | background, surface | Gallery band and its integrated captions. |

## Typography

- **Urbanist** — All headings, descriptions, navigation and controls. Rounded geometric sans with open, friendly forms; extra-bold display weights give it a toy-like presence. Font stack: "Urbanist", Arial, sans-serif.
- **ProFontWindows** — Crooked role stickers and technical annotation lettering. Compact retro-computer monospace with a visibly mechanical rhythm. If unavailable, use **VT323**. Use the available regular cut; tune width to preserve the compact label silhouette. Font stack: "ProFontWindows", "VT323", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Urbanist | 900 | 88px | 96px | 0.02em | Two-line identity or product headline on the opening stage. |
| section-heading | Urbanist | 900 | 72px | 80px | 0.02em | Selection headings and the two-line closing invitation. |
| role-sticker | ProFontWindows | 700 | 28px | 45px | 0.0114em, uppercase | Short role or product-category sticker attached to the display headline. |
| selection-sticker | ProFontWindows | 700 | 22px | 32px | 0.0145em, uppercase | Compact sticker overlapping the top of a section heading. |
| preview-title | Urbanist | 700 | 22px | 30px | 0.0145em | Titles below landscape preview images. |
| preview-description | Urbanist | 500 | 16px | 19px | 0.02em | One-line secondary descriptions below preview titles. |
| action | Urbanist | 800 | 16px | 19px | 0.02em, uppercase | Conversion pills and locale controls. |
| navigation | Urbanist | 700 | 16px | 19px | 0.02em, uppercase | Centered section navigation. |
| caption | Urbanist | 400 | 14px | 17px | 0.023em | Centered footer credits and copyright. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case-study openings | case-title | Urbanist | 700 | 72px | 1.1 | 0.0044em | Product name beside an explanatory paragraph. |
| case-study endings | next-title | Urbanist | 700 | 22px | 1.1 | 0.0145em | Next-item name inside the outlined onward card. |
| case-study introductions | case-body | Urbanist | 400 | 16px | 1.3 | 0.02em | Compact descriptive paragraphs in a 443px-wide column. |
| case-study galleries | media-label | Urbanist | 700 | 16px | 19px | 0.02em | Sentence-case notched captions attached to media. |
| case-study endings | next-prefix | Urbanist | 400 | 16px | 19px | 0.02em | Muted prefix above the next-item name. |

**Notes:**

- Display and section headings use positive 0.02em tracking rather than compressed editorial tracking. Smaller sans roles keep 0.3px tracking.
- The 900-weight marketing headings are deliberately more emphatic than the 700-weight case-study title. Preserve this distinction.
- Monospace belongs to stickers and technical annotations, not general paragraphs. Keep its uppercase sticker treatment distinct from sentence-case media labels.

## Layout

**Density:** Airy scene-scale composition with compact labels and controls; imagery receives more room than explanatory text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Preview image-to-title separation and small caption vertical padding. |
| 12px | Header action-to-audio gap, title-to-technology row and footer credit spacing. |
| 18px | Social action gaps, annotation rhythm and caption horizontal padding. |
| 20px | Outer page gutters. |
| 28px | Preview grid gaps and footer link separation. |
| 36px | Primary grid gutters and closing headline-to-social spacing. |
| 48px | Case-study media stack gaps. |
| 64px | Gallery band top and bottom padding; selection heading-to-grid gap. |
| 120px | Top padding for case-study introductions under fixed navigation. |
| 144px | Top and bottom breathing room around the marketing preview section. |

### Containers and grids

- **Wide scene grid**: max width 1920px · 12 columns · gap 36px · side padding 20px. Underlying desktop grid for full-bleed stages and inset text. Scene art can extend past content columns.
- **Preview grid**: 2 columns · gap 28px. Centered image-first cards; at desktop each image is 447px by 251px. The grid uses auto-fit with a 360px minimum track.
- **Closing stage**: max width 1440px · 12 columns · gap 36px · side padding 20px. Full-height illustrated invitation; left text column, central character or product object, right supporting props.
- **Case media** (only for case studies): max width 900px · side padding 0px. Centered 16:9 media within the gallery band.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Pill controls | 100px |
|  | Circular utilities | 50% |
|  | Media frames | 16px |
| case-study endings | Onward card | 12px |
| case studies | Gallery band | 48px |

## Surfaces and depth

### Surfaces

#### Warm canvas · level 0

**Use:** Default marketing shell.

**CSS:** `background: #f5efe6; color: #2d2a24`

**Observed:** Flat and untextured behind text. Physical depth comes from scene lighting, not card shadows.

**Transfer:** Keep ordinary copy surfaces matte and warm.

#### Sand media backing · level 1

**Use:** Preview frames and the compact navigation tray.

**CSS:** `background: #f1e5d5; border-radius: 16px; box-shadow: none`

**Observed:** Preview artwork fills its frame; descriptions remain directly on the page canvas.

**Transfer:** Use the backing as an intentional frame, not an empty content tile.

#### Light gallery band · level 0

**Only for:** light case studies

**Use:** Continuous surround for the full product gallery.

**CSS:** `background: #f3f7fa; border-radius: 48px; padding: 64px 20px; display: flex; flex-direction: column; gap: 48px`

**Observed:** One large rounded band contains multiple centered media panels, without separate elevated card shells.

**Transfer:** Group visual proof into one continuous field.

#### Dark gallery band · level 0

**Only for:** dark case studies

**Use:** Dark product-gallery surround.

**CSS:** `background: #364e7c; color: #ffffff; border-radius: 48px; padding: 64px 20px; display: flex; flex-direction: column; gap: 48px`

**Observed:** The surround is lighter than the #1c2f4f page canvas; media and captions sit flush into it.

**Transfer:** Use this as a complete dark case-study theme, not the ordinary warm landing-page palette.

## Components

### Primary button

**Use:** Persistent main conversion action.

**CSS:** `background: #ff8400; color: #ffffff; border-radius: 100px; height: 44px; padding: 0px 26px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Urbanist 800 · 16px/19px · tracking 0.02em · uppercase

**Observed:** The header places it next to an audio circle. Light case studies use action blue; dark case studies use the brighter blue, including a shorter live-demo version.

**States:** Declared: hover background-color #2d2a24 and color #ffffff; focus-visible unknown. Light case-study hover uses #141d25; dark case-study hover uses #060f1f.

**Transfer:** Keep one compact, direct conversion label rather than a large hero button cluster.

### Section navigation

**Use:** Fixed centered navigation between the major marketing chapters.

**CSS:** `background: #f1e5d5; border-radius: 100px; padding: 3px; display: flex; width: 390px`

**Text style:** `navigation` — Urbanist 700 · 16px/19px · tracking 0.02em · uppercase

**Observed:** Three equal text segments sit in a shallow tray, with a sliding orange active pill and white active text. The fixed header is 96px high; the tray is 33px high.

**States:** Declared: hover text color #ffffff; focus-visible unknown. Seen: orange active segment with white text.

**Transfer:** Use three short section names and keep the active treatment legible over both warm and dark scenes.

### Audio utility

**Use:** Small sound control beside the main action.

**CSS:** `background: #dfd2bf; color: #2d2a24; border-radius: 50%; width: 44px; height: 44px; padding: 10px; display: flex; align-items: center; justify-content: center`

**Observed:** A filled 24px speaker glyph communicates sound status. Case-study themes replace the backing with their own edge color.

**States:** Declared: hover background-color #2d2a24 and color #ffffff; focus-visible unknown.

**Transfer:** If the experience contains sound, make its control a clearly named utility rather than part of the primary action.

### Social circle

**Use:** Small contact destinations under the closing invitation.

**CSS:** `background: #f5efe6; border-radius: 50%; width: 44px; height: 44px; padding: 10px; display: flex; align-items: center; justify-content: center`

**Observed:** Four destinations appear in a row with 18px gaps. Icons are brown-black; in case-study footers the circles use the theme edge color.

**Transfer:** Choose actual destinations and retain accessible action names.

### Tilted sticker

**Use:** A technical-category counterpoint to rounded display typography.

**CSS:** `background: #263c70; color: #ffffff; outline: 4px solid #f5efe6; padding: 8px 12px; transform: rotate(-5deg)`

**Text style:** `role-sticker` — ProFontWindows 700 · 28px/45px · tracking 0.0114em · uppercase

**Observed:** A sharp-cornered rectangle overlaps the lower-right of the two-line title. The smaller section variant uses 4px 8px padding, the selection-sticker recipe and a −6deg rotation.

**Transfer:** Attach a short category label to the heading rather than making it a conventional eyebrow above a paragraph.

### Preview card

**Use:** Clickable product or capability proof.

**CSS:** `border-radius: 16px; background: #f1e5d5; overflow: hidden; aspect-ratio: 16 / 9`

**Text style:** `preview-title` — Urbanist 700 · 22px/30px · tracking 0.0145em

**Observed:** The CSS describes the media frame, not an all-enclosing painted card. A title sits 8px below the image, followed by a muted preview-description line on the bare canvas.

**Transfer:** Use vivid original artwork or a strongly composed product image; keep all text outside the media frame.

### Invitation tile

**Use:** An explicit new-work action within the preview grid.

**CSS:** `background: #e9ded0; border: 4px dashed #dfd2bf; border-radius: 16px; aspect-ratio: 16 / 9; display: flex; align-items: center; justify-content: center`

**Text style:** `preview-title` — Urbanist 700 · 22px/30px · tracking 0.0145em

**Observed:** A centered 36px plus icon is the intentional content of the media-sized tile. Its action title sits underneath like the other previews.

**Transfer:** Use as a real creation or contact action, not as a loading or unavailable-media state.

### Locale pill

**Use:** Compact language action in the footer utility row.

**CSS:** `border: 2px solid #e9ded0; border-radius: 100px; height: 38px; padding: 0px 16px; display: flex; align-items: center; justify-content: center; color: #2d2a24`

**Text style:** `action` — Urbanist 800 · 16px/19px · tracking 0.02em · uppercase

**Observed:** Sits after two plain legal links. Case-study variants use their theme edge and text colors.

**States:** Declared: hover background-color #2d2a24, color #ffffff and border-color #2d2a24; focus-visible unknown.

### Back to top

**Use:** Centered footer navigation utility.

**CSS:** `border: 2px solid #e9ded0; border-radius: 50%; width: 44px; height: 44px; padding: 10px; display: flex; align-items: center; justify-content: center`

**Observed:** A heavy round-ended upward arrow is centered independently of the right-aligned legal group. Case-study footers retain the same arrangement and add social circles at the left.

**Transfer:** Keep this as a small centered destination marker above the credit lines.

### Notched media caption

**Only for:** case-study galleries

**Use:** Short capability title integrated into the lower-right media edge.

**CSS:** `background: #f3f7fa; border-top-left-radius: 16px; padding: 8px 18px; position: absolute; right: 0px; bottom: 0px`

**Text style:** `media-label` — Urbanist 700 · 16px/19px · tracking 0.02em

**Observed:** The caption matches the surrounding band and visually cuts into the picture. Small 16px concave corner pieces make the join fluid; the dark variant uses the dark gallery-band fill and white text.

**Transfer:** Use an SVG corner mask or matching quarter-circle cutouts to merge the caption into the surround.

### Onward card

**Only for:** case-study endings

**Use:** Single next item after the gallery.

**CSS:** `border: 2px solid #e2e9ee; border-radius: 12px; padding: 8px 28px 8px 8px; display: flex; align-items: center; justify-content: space-between; width: 443px; height: 120px`

**Text style:** `next-title` — Urbanist 700 · 22px/1.1 · tracking 0.0145em

**Observed:** A 178px by 100px landscape thumbnail is followed by a muted next-prefix above the title and a 28px chevron at the far edge. The dark variant changes the border to night edge, text to white and prefix to pale slate.

**Transfer:** Offer one related destination, not an entire recommendation grid.

## Imagery and graphics

### Soft dimensional dioramas

**Use:** Opening and closing scene-scale illustrations.

**Observed:** Matte, softly rounded 3D characters and everyday props sit in a cream world with broad diffuse lighting and gentle contact shadows. The opening shows a workspace from behind the character; the closing faces the character toward the visitor among parcels and envelopes. The scene fills the viewport, leaving deliberate negative space for text rather than sitting in a rectangular image box.

**Transfer:** Create a similarly tactile scene around the new product: a friendly rounded object with a few contextual props. Keep the floor and wall close to the warm canvas and confine stronger colors to selected props.

**Build:** Use bevelled rounded boxes, cylinders and simple spheres in a small 3D scene or shaded SVG composition. Place the main object on the right, secondary props farther back and a warm floor plane below. Use a large soft light from upper-left and low-contrast ambient occlusion at contacts. Minimum version: one rounded product model, two supporting props and soft elliptical floor shadows, leaving the left third clear.

### Holographic inspection stage

**Use:** Signature technical demonstration interlude in the warm marketing experience.

**Observed:** A front-facing toy character stands on a luminous cyan circular base in a deep blue environment. Curved perspective grid lines and tiny points recede into the floor; parts of the figure become cyan scan contours. Thin connector lines lead to compact translucent annotation plaques on both sides, and a small numeric badge sits on the pedestal front.

**Transfer:** Retain the inspection-stage device with an original product object, workflow shape or rounded silhouette. Explain the new product with only a few short labels, keeping the luminous object dominant.

**Build:** Layer a navy field with a broad radial cyan wash near the lower center. Draw an SVG perspective grid with 1px cyan lines at low alpha and small glowing intersection dots. Build a centered elliptical pedestal from stacked dark-blue ellipses with a cyan 2px rim and blurred duplicate beneath. Clip repeating 2px horizontal cyan scan lines to an outlined product silhouette; add a soft cyan outer glow. Put translucent navy plaques on either side with 1px cyan edges, 12px corners and straight connector lines ending in dots. Use rgba(0,220,255,0.15) for the wash and rgba(0,220,255,0.8) for luminous edges; exact gradient stops are not essential.

### Colorful preview art

**Use:** Proof grid media.

**Observed:** Bright toy-like game worlds, character renders and luminous particle art occupy landscape frames. Imagery is much more saturated than the page shell; the treatment varies with the demonstrated work but the framing stays consistent.

**Transfer:** Create a legible, image-first cover for each capability using its own product colors. Keep the marketing shell neutral and the cover free of extra marketing badges.

### Product gallery panels

**Only for:** case studies

**Use:** Large sequential demonstrations.

**Observed:** Centered landscape panels show gameplay, avatar arrangements, and side-by-side mobile interfaces. Bright blues and turquoise dominate the product media; light and dark interface variants remain inside the panels. The surrounding gallery is restrained and the only external text is the notched caption.

**Transfer:** Use actual product views or intentional interface mockups, preserving 16:9 framing. Pair mobile views in one landscape panel rather than scattering tiny devices around prose.

### Icons

**Observed:** Utilities use 24px filled SVG glyphs, with a 24px outlined mail symbol at 2px stroke. Directional symbols are heavier, round-ended 4px strokes: 20px back-to-top, 28px onward chevron and 36px plus for the invitation tile. Icons inherit the warm or case-study text color.

**Transfer:** Choose simple solid utility marks and bold rounded directional icons; keep them centered in the 44px circles without adding label chips.

## Section recipes

How recurring sections are built.

### First screen: Room-scale opening

**Observed:** A full-bleed 900px-high cream stage sits behind a fixed 96px header. The shallow Section navigation tray floats at the top center, with Primary button and Audio utility at the upper-right; a small identity mark appears at the left as the experience develops. The two-line display headline occupies roughly the left third and is vertically centered slightly above the stage midpoint, with a Tilted sticker overlapping its lower-right. Behind and to the right is a softly lit dimensional workspace scene that fills about two thirds of the width and extends through the lower edge. Layers run from warm environment to props and character, then headline and sticker, then fixed controls. Within the first 900px the complete title, category sticker, controls, main scene and bottom-center mouse/down indicator are visible. There is no supporting paragraph or large hero CTA cluster; deeper explanation and proof appear below.

**Transfer:** Use the display recipe for a short product name or two-line promise, and make an equally tactile scene from a rounded product object and contextual props when character art is unavailable. Case-study openings instead use a 120px top inset, a 72px 700-weight product name and compact technology pills on the left, a 16px/1.3 explanatory column on the right, then the gallery band below; a live-demo pill can sit under the name.

**Avoid:** Do not turn this into a centered text-only SaaS hero, a photographic office banner or a small illustration confined to a floating card.

**Text style:** `display` — Urbanist 900 · 88px/96px · tracking 0.02em

### Technical inspection chapter

**Observed:** The warm room gives way to a full-window Holographic inspection stage. The object is centered, with sparse connected labels placed around rather than over it. Navigation reverses for the blue field while the orange main conversion remains recognizable.

**Transfer:** Use the illuminated inspection device to explain the product's construction or capabilities; a static composed illustration can carry the same contrast without a complex live 3D model.

### Selection and previews

**Observed:** A warm canvas section uses 144px vertical padding, a small tilted selection sticker and a 72px section heading. A 64px separation leads to the two-column Preview grid with 28px gaps, image-first Preview cards and a real Invitation tile among them.

**Transfer:** Use this structure for selected features, use cases or outcomes. Let imagery carry the distinction between items; the labels identify rather than sell at length.

**Text style:** `section-heading` — Urbanist 900 · 72px/80px · tracking 0.02em

### Illustrated invitation

**Observed:** A full-height warm diorama carries the 72px/80px two-line invitation at the upper-left, with Social circles 36px below. A large friendly character occupies the center while parcels and envelopes balance the right and lower edges. Rounded lower corners separate the illustrated field from the small footer.

**Transfer:** Close with a short collaborative invitation and a product-object scene facing the visitor. Maintain the scale and physical warmth even when the product has no mascot.

**Text style:** `section-heading` — Urbanist 900 · 72px/80px · tracking 0.02em

### Onward and utility ending

**Observed:** Case studies conclude the gallery with one centered Onward card in a section padded 36px above and 64px below. The footer has 32px vertical padding, social circles at left on case studies, a centered Back to top, and legal links plus Locale pill at right. A second centered tier contains small music credit and copyright lines, separated by 12px; the main footer tiers have 36px separation. The warm marketing ending places social links in its illustrated invitation instead of duplicating them in the footer.

**Transfer:** Keep the ending lightweight and human: one onward destination when appropriate, practical utilities, and short centered credits. Do not substitute a dense multi-column sitemap.

### Continuous media gallery

**Only for:** case studies

**Observed:** The Light gallery band or Dark gallery band begins directly below the introduction, with 48px rounded outer corners and 64px inner top and bottom padding. A centered 900px-wide video or image leads a stack of 16:9 demonstrations separated by 48px. Each carries a Notched media caption on its lower-right edge rather than a separate heading paragraph.

**Transfer:** Tell the detailed story through distinct capability views; select the number of panels the new product needs and keep its interface styling inside the imagery.

## Page flow

**Storyline:** personality-led introduction → technical or visual demonstration → selected proof → human invitation or onward destination → compact utilities

### Immersive marketing or maker-led landing page

1. **Identity and promise** — Large two-line name, tilted category sticker and full-window soft 3D environment.
2. **Capability demonstration** — Blue holographic inspection scene with connected short annotations.
3. **Selected proof** — Warm image-first grid with category descriptions and an invitation tile.
4. **Closing call** — Monumental collaborative line, contact circles and a second warm diorama.
5. **Utilities** — Centered up-arrow, small legal and language group, credits below.

**Transfer:** Use the warm experience as the default for a new launch. Adapt the amount and order of proof to the product while retaining scene-scale imagery, technical contrast and a personable closing.

### Light product case study

1. **Context** — Split name-and-tags introduction with a compact factual account of the product.
2. **Product demonstration** — Video-led light gallery band with large views, avatar variants, mobile layouts and a dark-mode example inside the media.
3. **Onward discovery** — One bordered thumbnail card to another project.
4. **Utilities** — Social circles, up-arrow, legal and language actions, then centered credits.

**Transfer:** Use for a focused visual walkthrough with less theatrical introduction than the main landing page.

### Dark product case study

1. **Context and access** — White title and descriptive text on navy, technology pills and a blue live-demo action.
2. **Product demonstration** — Lighter blue gallery band showing large gameplay and interface views, including mobile and multi-user examples.
3. **Onward discovery** — Single thumbnail link with a subtle dark edge.
4. **Utilities** — Same compact footer structure, reversed into white and pale slate.

**Transfer:** Carry the whole navy theme through the case study rather than interleaving arbitrary dark marketing sections.

## Writing

Friendly, straightforward and maker-led. The visual world is playful, but descriptions are specific about what was built and how it works rather than full of jokes or grand promises.

**Do not copy:** Do not reuse the creator's name, project names, mascot, logos, authored artwork, technical experience claims, credits or ownership claims. Source phrases below illustrate tone, not assets or claims to transplant.

- **Addressing the reader:** The main invitation speaks collaboratively. Case descriptions name the product directly and can use first-person singular for authentic authorship; technical explanations are mostly declarative.
- **Rhythm:** Headings are usually one to four words, with the closing invitation using a short exclamation. Grid descriptions are terse noun phrases. Introductions use several compact factual sentences instead of long sales paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening identity | A short name paired with an uppercase category sticker. | Name plus two-word role | “[Brand]”<br>“Web Developer” |
| Selection heading | One emphatic noun with a small selection marker. | One word per level | “Selected”<br>“Projects” |
| Preview description | Plain category description without a claim or punctuation flourish. | Three to four words | “Multiplayer strategy game”<br>“Open-source learning project” |
| Product explanation | State what the product is, then identify concrete capabilities and development context. | Two to four compact sentences | “Quibbo is a platform for fast, round-based multiplayer games.”<br>“I built the full stack myself, including the game engine, the client-side timeline system, and real-time networking with Redis-based matchmaking for smooth, high-concurrency gameplay.” |
| Media caption | A concise capability name in sentence or title case. | One to three words | “Avatar Variations”<br>“Party System” |
| Action and closing | Direct contact language and a collaborative invitation. | Two to four words | “Get in touch”<br>“Let's work together!”<br>“Start a new project” |

**Words and phrasing to use:** built; interactive; real-time; responsive; project; together; get in touch

**Avoid:** revolutionary; unlock limitless potential; enterprise-grade synergy; world-leading; unverified performance superlatives

**Rules:**

- Let the images provide playfulness while the text remains concrete.
- Use first-person authorship only for work actually done by the speaker.
- Name capabilities in gallery captions rather than writing a sales paragraph below every view.
- Reserve uppercase for controls and technical stickers, not descriptive paragraphs.

## Do's and Don'ts

### Do

- Keep the primary display at 88px/96px, weight 900 and positive 0.02em tracking on desktop.
- Pair rounded sans headlines with the sharp, −5deg navy category sticker.
- Stage the main illustration full-bleed and leave a clean left-third text zone.
- Use 44px pills and circles as the control family, with 24px utility icons.
- Keep preview imagery at 16:9 with 16px corners and titles 8px below it.
- Separate detailed gallery media by 48px inside one rounded band.
- Carry the warm illustrated invitation through to a compact footer with a centered up-arrow.
- Keep orange concentrated in the conversion control and active section indicator.

### Don't

- Do not apply negative tracking to the heavy display; its 0.02em spacing is part of the friendly shape.
- Do not replace the flat canvas with a pervasive glass or gradient UI treatment.
- Do not add drop shadows to every card; the page surfaces have no shadow system.
- Do not paint the preview descriptions inside a white card body; they sit on the canvas.
- Do not use the bright case-study blues as the default warm marketing action color.
- Do not turn the dashed creation tile into a generic empty-state pattern.
- Do not put 28px monospace on all navigation and paragraphs; it is a sticker treatment.
- Do not enlarge the footer into a dark mega-sitemap that competes with the illustrated ending.

## Motion and responsive

### Motion

**Observed:**

- Action color, background and border transitions are declared at 0.1s ease-in-out.
- Case-study title entrance is declared at 0.5s cubic-bezier(.6, 0, .25, 1).
- The main experience uses a sticky 900px scene through a longer scroll region, progressing from a warm room to a blue holographic inspection view. The centered section marker changes with the active chapter.

**Transfer:**

- Use the same object across warm and inspection views to connect personality with technical explanation.
- Keep control response crisp at the declared 0.1s rather than adding long bouncy hover animations.

**Unknown:**

- The full 3D timeline, camera interpolation, audio behavior and exact scene transition timing are not specified.

### Responsive

**Observed:**

- Styles declare width breakpoints at 480px, 840px, 1024px, 1280px and 1600px.
- Preview tracks use auto-fit with a 360px minimum.

**Transfer:**

- For narrow layouts, preserve the warm scene and tilted label as the signature rather than retaining a desktop-sized object behind unreadable text. Stack text and a simplified scene when needed.
- Let the proof grid reduce to one column and fit gallery media to the viewport while preserving their landscape proportion. These are adaptation rules, not separate measured mobile recipes.

**Unknown:**

- Exact mobile type sizes, navigation transformations and 3D camera framing are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
