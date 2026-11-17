# ethereum.org — an illustrated public future

## Overview

An optimistic, people-first technology style that pairs extremely heavy sans-serif headlines with expansive illustrated worlds. White and pale gray layouts keep the reading experience practical, while violet actions and pastel cyan, lavender and peach artwork supply the personality. It suits complex platforms that need approachable explanations, hands-on learning and multiple audience entry points; the overall density is airy in storytelling and compact in resource navigation.

### Essentials

- A public-world illustration leads before the sales pitch: a full-width 1440×480px panorama sits above a centered 64px/0.9, weight-900 headline in an 893px maximum text width. Preserve the illustrated environment; use a simple architectural SVG scene with people and a product-related focal object when bespoke art is unavailable.
- Headlines are black, blunt and unusually heavy rather than tightly tracked: Inter 900 at 60px/1.2 for major chapters, 48px/1.2 for large card titles and 24px/1.3 for smaller cards, all with normal tracking.
- Violet is a navigation signal and an occasional proof spotlight, not the page canvas: white dominates, #f7f7f7 groups content, #6c24e0 fills actions, and one standout proof tile uses a #561bb6-to-#9357f4 gradient with white text.
- Controls are squarer than the content they unlock: primary hero actions use 8px corners and 12px vertical padding, ordinary actions use 4px corners and 8px vertical padding, while storytelling cards use 24px corners and audience-route cards use 38px corners.
- Illustrations are lived-in places, not isolated futuristic gadgets: pastel environments, dark violet outlines, small human activity and plants occupy full-width panoramas or 512×700px portrait scenes. Floating white and violet fact plaques connect these worlds to concrete benefits.
- The proof system mixes sober numbers with expressive art: 36px/1.2 bold numerals sit beside thin dividers, while the violet proof card combines a 48px heavy title, a 30px bold figure and a translucent lower-corner illustration.
- A soft-lit choice of next steps replaces the single giant closing slogan: a top-centered lavender-to-blue radial wash backs white, finely outlined route cards with 352×192px illustrations, concise bullet lists and bottom-aligned violet actions. Carry this softly lit route-selection device into every new landing page, adapting the number of routes to the audience.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#6c24e0` | `--color-primary` | action, link, accent | Filled actions, outlined secondary actions, linked labels and small icons. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep violet | `#41128c` | `--color-label` | text | Uppercase chapter labels on white. |
| Proof violet shade | `#561bb6` | `--color-proof-start` | surface | Top stop of the highlighted proof card. |
| Proof violet light | `#9357f4` | `--color-proof-end` | surface | Bottom stop of the highlighted proof card. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas and white cards; inverse text on violet panels. Editorial image-overlay panels use white at 80% opacity. |
| Grouping gray | `#f7f7f7` | `--color-soft` | background, surface | Feature bands, the footer's social strip and editorial catalog cards. |
| Hairline gray | `#cfcfcf` | `--color-edge` | border | Card edges, navigation and footer dividers. |
| Utility gray | `#8c8c8c` | `--color-utility` | text, border | Search outline and keyboard hints. |
| Reading gray | `#616161` | `--color-muted` | text | Long supporting paragraphs, captions and footer links. |
| Near-black ink | `#121212` | `--color-ink` | text, border | Primary headlines, body copy on editorial pages, dark outlines and navigation text. |

## Typography

- **Inter** — All marketing headlines, paragraphs, navigation, labels and controls. Neutral contemporary sans with an emphatic black weight for headings and a relaxed regular cut for explanations. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 900 | 64px | 0.9 | normal | Centered landing-page promise, balanced into two lines. |
| heading-lg | Inter | 900 | 60px | 1.2 | normal | Major storytelling chapters and centered section introductions. |
| heading-feature | Inter | 900 | 48px | 1.2 | normal | Large proof cards and illustrated editorial hero headings. |
| stat | Inter | 700 | 36px | 1.2 | normal | Unboxed quantitative proof beside a chapter introduction. |
| heading-small | Inter | 900 | 30px | 1.3 | normal | Smaller benefit tiles and feedback section headings. |
| proof-stat | Inter | 700 | 30px | 1.3 | normal | Inverse numeric proof within the highlighted violet card. |
| heading-card | Inter | 900 | 24px | 1.3 | normal | Audience routes, catalog cards and update titles. |
| body-lead | Inter | 400 | 24px | 1.625 | normal | Large, gray explanatory paragraphs in storytelling splits. |
| hero-support | Inter | 400 | 24px | 1.625 | 0.003em | Centered promise support, constrained to 741px. |
| body-lg | Inter | 400 | 18px | 1.6 | normal | Hero actions, editorial hero support and introductory text. |
| body | Inter | 400 | 16px | 1.6 | normal | Card descriptions, editorial paragraphs, navigation and standard actions. |
| eyebrow | Inter | 600 | 14px | 1.6 | 0.05em, uppercase | Compact deep-violet chapter labels above major headings. |
| caption | Inter | 400 | 14px | 1.6 | normal | Footer links, update summaries and numeric annotations. |
| footer-heading | Inter | 900 | 14px | 1.6 | normal | Dense resource-column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| guided product demonstrations | demo-heading | Inter | 900 | 60px | 1.25 | normal | Centered invitation to a guided interactive lesson. |
| editorial and catalog pages | heading-editorial | Inter | 900 | 36px | 1.2 | normal | Section titles in explanatory articles and application catalogs. |
| explanatory FAQ sections | question | Inter | 600 | 20px | 1.4 | normal | Full-sentence accordion questions. |

**Notes:**

- Normal tracking remains the default even for the heaviest headlines; compression comes from weight, wrapping and line height, not negative letter spacing.
- The landing promise is more tightly led than all other headings. Major chapter titles have visibly more room between lines.
- Large storytelling paragraphs use muted gray and 1.625 leading; denser cards retain 1.6 leading at 16px.
- Use uppercase sparingly for chapter labels and metadata, not for the principal headline. Editorial hero labels can be 16px regular uppercase, while the main title retains the 48px heavy recipe.

## Layout

**Density:** Airy narrative sections alternate with compact utility navigation and card content; long vertical pauses separate distinct ideas.

### Spacing

**Spacing system:**

- **space** 16px — Primary content spacing unit; half-units supply 8px control gaps and 24px card padding is one and a half units.

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-heading separation and icon/label gaps. |
| 16px | Action-pair gaps, ordinary card-grid gutters and stacked small content. |
| 24px | Editorial card and accordion interior spacing. |
| 32px | Wide card padding, desktop page sides and bento gutters. |
| 40px | Story heading group to large support copy. |
| 48px | Story section vertical padding and gaps before major card groups. |
| 64px | Space beneath the panorama before the centered hero text. |
| 72px | Editorial split-column separation and catalog chapter intervals. |
| 80px | Top padding of the illuminated closing region. |
| 96px | Vertical padding of the gray proof band. |
| 128px | Landing-page separation between major narrative sections. |

### Containers and grids

- **page shell**: max width 1536px · side padding 16px. Centered overall site width. Landing narrative bands sit within slim sides; the hero panorama runs to the shell edges.
- **utility frame**: max width 1536px · side padding 32px. Navigation, editorial pages and footer share the wider desktop side padding.
- **feature container**: max width 1280px · side padding 16px. Centered proof, updates and closing-route grids.
- **hero text**: max width 893px. Centered two-line display promise; supporting paragraph narrows further to 741px.
- **story split**: 2 columns · gap 32px. Large left-aligned copy balanced by a 512×700px illustrated scene; reverse the sides for the next benefit.
- **proof grid**: 12 columns · gap 32px. Highlighted proof tile spans seven tracks, adjacent white tile spans five; smaller tiles use an even three-column row.
- **route grid**: 3 columns · gap 16px. Equal-height closing cards, each 416px wide at the desktop composition.
- **footer grid**: 6 columns · gap 16px · side padding 32px. Six even resource columns; a utilitarian index rather than a sparse promotional footer.
- **editorial reading** (only for editorial pages): max width 768px. Readable introductory paragraphs on otherwise full-width explanatory pages.
- **catalog with index** (only for catalog pages): max width 896px · gap 72px. Left article column beside a 320px sticky index on the right; three 288px cards fit in the article width.
- **principle grid** (only for editorial principle pages): 4 columns · gap 16px. Four 332px-wide explanation cards across the desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | ordinary actions | 4px |
|  | hero actions | 8px |
|  | proof cards | 24px |
|  | route cards | 38px |
|  | feedback launcher | 9999px (pill) |
| editorial and catalog pages | editorial cards | 28px |
| FAQ sections | accordion rows | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| highlighted proof | `0px 20px 25px -5px rgba(0, 0, 0, 0.1), 0px 8px 10px -6px rgba(0, 0, 0, 0.1)` | Only the vivid proof tile receives this stronger lift. |
| floating plaques | `0px 10px 15px -3px rgba(0, 0, 0, 0.1), 0px 4px 6px -4px rgba(0, 0, 0, 0.1)` | Small fact plaques layered across illustrated story scenes. |
| route edge | `0px 0px 0px 1px #cfcfcf` | Fine outline of white audience-route cards, without a raised shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Main reading ground.

**CSS:** `background: #ffffff; color: #121212`

#### Proof band · level 0

**Use:** A broad visual pause containing differentiated benefits.

**CSS:** `background: #f7f7f7; padding: 96px 0px`

**Observed:** The inner cards remain white or violet; the band itself has square outer corners.

**Transfer:** Separate a compact proof story from surrounding open-white chapters.

#### White proof card · level 1

**Use:** Supporting benefits beside the highlighted proof tile.

**CSS:** `background: #ffffff; border: 1px solid #cfcfcf; border-radius: 24px; padding: 32px; overflow: hidden`

**Observed:** Small conceptual art sits toward the lower right, with readable copy above it. One variant uses a near-black edge and the gray band showing through instead of white fill.

**Transfer:** Keep art subordinate to the text and maintain a shared corner treatment across differently sized tiles.

#### Violet proof card · level 1

**Use:** The principal expressive proof spotlight.

**CSS:** `background: linear-gradient(in oklab, #561bb6 0%, #9357f4 100%); border-radius: 24px; padding: 32px; color: #ffffff; overflow: hidden; box-shadow: 0px 20px 25px -5px rgba(0, 0, 0, 0.1), 0px 8px 10px -6px rgba(0, 0, 0, 0.1)`

**Observed:** A translucent illustration bleeds beyond the lower-right corner, behind foreground text.

**Transfer:** Highlight the strongest verifiable benefit rather than coloring every card.

#### Closing light · level 0

**Use:** Soft illumination behind the next-step route cards.

**CSS:** `background: radial-gradient(120% 80% at 50% -30%, oklab(0.605953 0.100786 -0.199559 / 0.24) 33%, oklab(0.586711 -0.0150739 -0.195399 / 0.08) 66%, rgba(0, 0, 0, 0) 100%); border-radius: 32px 32px 0px 0px; padding: 80px 32px 32px`

**Observed:** The tint is strongest above the title and becomes almost white around the cards.

**Transfer:** Match the broad soft glow; it should read as ambient light rather than a saturated gradient banner.

#### Editorial hero glass · level 1

**Only for:** editorial and catalog openings

**Use:** Readable introduction over a detailed panoramic illustration.

**CSS:** `background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(8px); border-radius: 4px; padding: 32px; max-width: 384px`

**Observed:** A left-anchored panel floats over the image, vertically centered, without a pronounced border or shadow.

**Transfer:** Keep the scene visible through the panel while protecting dark-text legibility.

#### Editorial gray card · level 1

**Only for:** editorial and catalog pages

**Use:** Repeated principles or application entries.

**CSS:** `background: #f7f7f7; border-radius: 28px; box-shadow: none`

**Observed:** Principle entries use a heading and violet symbol across the top. Catalog entries use an image above the title and a bottom action.

**Transfer:** Maintain equal-height rows even when titles wrap differently.

## Components

### Sticky navigation

**Use:** Persistent orientation and utility access.

**CSS:** `position: sticky; top: 0px; height: 76px; max-width: 1536px; padding: 16px 32px; background: #ffffff; border-bottom: 1px solid #cfcfcf; display: flex; align-items: center`

**Text style:** `body` — Inter 400 · 16px/1.6

**Observed:** A small illustrated brand symbol precedes six plain-text destinations. Search, a theme icon and a language control align on the right. Navigation destinations are not filled tabs.

**Transfer:** Use the same low-key utility strip for the new product's main destinations.

### Primary hero button

**Use:** Main landing-page next step.

**CSS:** `background: #6c24e0; color: #ffffff; border: 1px solid transparent; border-radius: 8px; padding: 12px 24px 12px 32px; min-height: 55px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `body-lg` — Inter 400 · 18px/1.6

**Observed:** A right chevron follows the label. The adjacent secondary action is outlined rather than filled.

**States:** Declared: hover background hsla(263, 88%, 65%) with white text and a 4px 4px pale-violet offset shadow; focus-visible 4px solid hsla(263, 88%, 65%) outline with -1px offset and 8px radius.

### Secondary hero button

**Use:** Alternative exploration beside the main action.

**CSS:** `color: #121212; background: transparent; border: 1px solid #121212; border-radius: 8px; padding: 12px 32px 12px 24px; min-height: 55px; display: inline-flex; gap: 8px; align-items: center`

**Text style:** `body-lg` — Inter 400 · 18px/1.6

**Observed:** A small sparkle icon precedes the label; the pair is centered as a single group.

**States:** Declared: hover violet text and a 4px 4px pale-violet offset shadow; focus-visible 4px solid hsla(263, 88%, 65%) outline with -1px offset.

### Standard action

**Use:** Card destinations and secondary conversion sections.

**CSS:** `background: #6c24e0; color: #ffffff; border: 1px solid transparent; border-radius: 4px; padding: 8px 16px; min-height: 44px; display: inline-flex; gap: 8px; align-items: center; justify-content: center`

**Text style:** `body` — Inter 400 · 16px/1.6

**Observed:** Content-sized when used alone; stretches across the available inner card width for routes and catalog entries.

**States:** Declared: hover white text, background hsla(263, 88%, 65%) and a 4px 4px pale-violet offset shadow; focus-visible 4px solid hsla(263, 88%, 65%) outline at -1px offset, with 2px radius.

### Search trigger

**Use:** Header search entry.

**CSS:** `border: 1px solid #8c8c8c; border-radius: 4px; padding: 8px 16px; min-height: 44px; width: 169px; display: inline-flex; gap: 8px; align-items: center`

**Text style:** `body` — Inter 400 · 16px/1.6

**Observed:** Magnifier and lowercase search label precede two small outlined shortcut keys. The visible label is dark; shortcut glyphs are gray monospace.

**States:** Declared: hover border and text hsla(263, 88%, 65%); focus-visible 4px solid outline in the same violet at -1px offset.

### Highlighted proof tile

**Use:** Combine a differentiated benefit with quantified support.

**CSS:** `background: linear-gradient(in oklab, #561bb6 0%, #9357f4 100%); color: #ffffff; border-radius: 24px; padding: 32px; position: relative; overflow: hidden`

**Text style:** `heading-feature` — Inter 900 · 48px/1.2

**Observed:** Icon tile, heavy title, short contrast statement, bold numerical proof and a small caption are stacked in the foreground. A low-opacity conceptual illustration anchors the lower-right corner.

**Transfer:** Use the Violet proof card surface and a real product-specific measure; retain the title/claim/proof hierarchy.

### Audience route card

**Use:** Closing next-step selection for different reader intentions.

**CSS:** `background: #ffffff; border-radius: 38px; box-shadow: 0px 0px 0px 1px #cfcfcf; display: flex; flex-direction: column`

**Text style:** `heading-card` — Inter 900 · 24px/1.3

**Observed:** An inset wide illustration precedes an icon-and-title row, a short description, three compact bullet links and a full-width Standard action aligned to the bottom. Media and text use separate 32px padded regions; images have 6px corners.

**States:** Declared: hover scale 100% 100%, preserving the fine outline rather than lifting or zooming; focus-visible 2px violet outline with 2px offset.

**Transfer:** Name the routes by user intention and preserve equal-height cards with aligned actions.

### Resource footer

**Use:** Deep navigation and a grounded, informational ending.

**CSS:** `border-top: 1px solid #cfcfcf; background: #ffffff`

**Text style:** `caption` — Inter 400 · 14px/1.6

**Observed:** A small italic update date and outlined Go to top action begin the footer. The linked site name precedes six resource columns with heavy small labels. A gray bottom strip centers four solid social icons above wrapping administrative links.

**Transfer:** Keep the depth appropriate to the new site's information architecture; retain the utility row, grouped destinations and contrasting social strip.

### Editorial entry card

**Only for:** editorial and catalog pages

**Use:** Principle explanations and browsable application categories.

**CSS:** `background: #f7f7f7; border-radius: 28px; display: flex; flex-direction: column`

**Text style:** `heading-card` — Inter 900 · 24px/1.3

**Observed:** Principle cards place a violet icon opposite the title and use outlined actions. Application cards place contained conceptual art above the title, muted description below and a filled Standard action at the bottom. Inner content is padded 24px.

**Transfer:** Use the icon-led variant for abstract commitments and image-led variant for concrete capabilities.

### FAQ row

**Only for:** explanatory FAQ sections

**Use:** Handle skeptical questions without overwhelming the main story.

**CSS:** `border: 1px solid #cfcfcf; border-radius: 16px; background: #ffffff`

**Text style:** `question` — Inter 600 · 20px/1.4

**Observed:** The whole question is a button with 24px padding. A small violet More label sits at the right, not a large decorative plus. Rows are separated by 16px.

**Transfer:** Use natural full-sentence objections and keep the closed rows short enough to scan.

### Feedback buttons

**Only for:** editorial and catalog endings

**Use:** A brief usefulness check before the resource footer.

**CSS:** `color: #6c24e0; background: transparent; border: 1px solid #6c24e0; border-radius: 4px; padding: 8px 16px; min-height: 44px; display: inline-flex; gap: 8px; align-items: center`

**Text style:** `body` — Inter 400 · 16px/1.6

**Observed:** A 30px heavy heading asks about usefulness, followed by Yes and No buttons with violet thumb icons. A separate fixed violet feedback launcher uses a pill or circle form.

**States:** Declared: hover violet text and a 4px 4px pale-violet shadow; focus-visible 4px violet outline at -1px offset.

## Imagery and graphics

### Inhabited future panorama

**Use:** Signature landing opening and smaller route-card illustrations.

**Observed:** Hand-drawn architectural worlds feature people talking, working and exploring among palms, terraces, glass roofs and civic interiors. Dark blue-violet contours enclose pastel cyan, lilac, pale blue and peach fills. The landing panorama is a wide, symmetrical hall with a central floating emblem; white light behind the focal object keeps it airy rather than cinematic-dark.

**Transfer:** Depict the new product's benefit as a welcoming shared place with visible human activity. The minimum equivalent is a clean SVG environment with people, plants, architectural frames and one central product-related form, not a lone icon on a gradient.

**Build:** Create a 1440×480 SVG viewBox. Layer a pale cyan ground, lavender arched or rectilinear architectural frames, receding perspective floor lines and a bright central opening. Add blue-violet contour strokes, flat pastel panels, a few simplified human silhouettes and foreground foliage. Center one faceted symbolic object above the horizon, leaving the lower image edge clean against the white text section. Reuse scene details in the route-card banners.

### Portrait benefit scenes and plaques

**Use:** Alternating benefit chapters.

**Observed:** Tall 512×700px illustrated scenes have softly rounded corners and show the same social world at closer range. Small white fact plaques and a violet comparison plaque overlap the scene edges. White plaques have thin gray outlines, soft shadows and compact dark headlines; the violet plaque uses white text.

**Transfer:** Zoom into a task or place from the opening world and overlay one or two concise outcome facts rather than UI clutter.

**Build:** Clip a portrait illustration to a 24px rounded rectangle. Position a 24px-radius white plaque with 16px 24px padding partly across an edge; add a second plaque using the Violet proof card gradient if a meaningful contrast exists. Use the Floating plaques shadow and keep the scene visible behind the labels.

### Conceptual object art

**Use:** Proof tiles, FAQs and capability cards.

**Observed:** Transparent-backed hands, faceted objects, layered blocks, miniature machines and symbolic assemblies sit directly on white or gray. Most use lavender and cyan with violet outlines, while catalog art varies in material and detail. In the proof spotlight the art is translucent and partly clipped; the FAQ image is much larger and given an entire column.

**Transfer:** Use a small library of conceptual illustrations tied to capabilities. Preserve contained framing, generous surrounding space and cool pastel emphasis rather than forcing every asset into identical 3D rendering.

**Build:** For a minimal system, draw isometric stacks from repeated diamond and rectangle SVG faces in lilac, pale cyan and violet outline. Arrange the stack or symbolic mechanism off-center with a few separated floating parts. On the proof tile place it at the lower right at 25% opacity with part of the form outside the clipping boundary.

### Campaign illustration banner

**Only for:** event or campaign promotions

**Use:** A temporary mid-page invitation and compact announcement strip.

**Observed:** A rounded, wide illustrated night scene has a dark radial overlay, white centered 48px heavy title, supporting promotional line and a violet action. Small identity and schedule details occupy its top corners. The compact top announcement uses a dark-violet gradient.

**Transfer:** Use a campaign-specific illustrated scene that can support white text; keep this darker treatment isolated from the ordinary light page.

### Editorial thumbnails

**Only for:** update and news sections

**Use:** Three-column update cards.

**Observed:** Wide 373×210px images can retain a publisher's own visual language, including bright graphics, black backgrounds and wordmarks. Below them sit a heavy 24px title, small italic source, gray excerpt, pale-violet category pill and uppercase date.

**Transfer:** Allow actual resource imagery to vary while making framing, title hierarchy and metadata consistent.

### Icons

**Observed:** Most interface icons are 24×24px outline SVGs with 2px round strokes, in near-black, violet or white. Small external-link marks are 12×12px in gray. Principle-card symbols are larger 48px violet filled icons; footer social marks are 36px solid silhouettes.

**Transfer:** Use a Lucide-like outline family for actions and utility controls, reserving filled marks for category symbols and social identities. Keep icons subordinate to text labels.

## Section recipes

How recurring sections are built.

### First screen: Illustrated world opening

**Observed:** A 76px white Sticky navigation tops the screen. A campaign-only 69px announcement strip can intervene before the full-width 480px panorama. The illustration occupies slightly over half of the first 900px and precedes, rather than sits behind, the promise. Beneath it, 64px of white breathing room introduces a small violet product label, followed by the centered display headline in an 893px maximum width. The headline forms two dense lines; the surrounding area stays empty and white. In the first 900px the navigation, announcement, complete scene, product label and headline are visible; the support paragraph begins at the lower edge and the Primary hero button / Secondary hero button pair falls below the fold. Back-to-front layers are the white canvas, flat outlined scene, its central symbolic object, then the separate white text block.

**Transfer:** Lead with a product-relevant inhabited world, using the SVG panorama recipe if custom illustration is unavailable. Keep the scene large enough to establish an optimistic atmosphere before the copy. Editorial and catalog pages instead use a 576px panorama with the Editorial hero glass panel at the left, a 48px heavy heading, 18px support and an action where appropriate.

**Avoid:** Do not shrink the world into a small right-hand thumbnail, put the default promise in a glass panel, or force both buttons into the first screen by compressing the image.

**Text style:** `display` — Inter 900 · 64px/0.9

### Benefit with sober proof

**Observed:** An eyebrow and heading-lg pair anchor a wide left text column; the body-lead paragraph follows 40px below the heading group. At the right, two stat values with small labels and thin icons stack in a narrow column, separated from the narrative by a 1px gray vertical rule.

**Transfer:** Make one clear product benefit concrete with a small number of meaningful measures rather than a full dashboard.

**Text style:** `heading-lg` — Inter 900 · 60px/1.2

### Alternating illustrated chapters

**Observed:** Story splits use 48px vertical padding and 128px between major sections. Text includes the eyebrow, heading-lg, body-lead paragraphs and a small violet arrow link; a 512×700px Portrait benefit scene balances the other side. The next chapter reverses image and copy.

**Transfer:** Use each scene to explain one distinct benefit and keep floating fact plaques tied to that scene's claim.

**Text style:** `heading-lg` — Inter 900 · 60px/1.2

### Expressive proof mosaic

**Observed:** Proof band contains a centered heading-lg and short support line. The 12-track Proof grid puts a Highlighted proof tile beside a White proof card, followed by an even row of smaller white benefit tiles. The white tile uses a 48px title at the top level; smaller tiles use 30px titles. A centered hero-sized violet action closes the band.

**Transfer:** Preserve the unequal emphasis: one expressive, quantified proof and a quieter supporting set. Adapt tile count to the story.

**Text style:** `heading-lg` — Inter 900 · 60px/1.2

### Illuminated route closing

**Observed:** Closing light backs a centered heading-lg, a short reassurance and three Audience route cards in the Route grid. Cards use vivid illustrated banners but restrained white bodies, matching bullet density and bottom-aligned actions. The illuminated area is inset 16px from the shell and has rounded top corners.

**Transfer:** Offer a small set of intention-based routes with clear next steps and a shared illustration vocabulary. Keep the softly lit choice architecture even when there are only two suitable routes.

**Text style:** `heading-lg` — Inter 900 · 60px/1.2

### Utility-rich ending

**Observed:** Resource footer starts with a thin top rule, italic update line and Go to top action. Beneath the linked name, six compact columns occupy most of the footer height. The final pale-gray strip centers solid social marks and a line of administrative links. Editorial pages place a usefulness question before this shared footer; the main landing page instead reaches it after the illuminated routes.

**Transfer:** Finish with useful navigation, not another oversized campaign statement. Retain the contrast between the white resource index and gray social strip.

**Text style:** `footer-heading` — Inter 900 · 14px/1.6

### Guided try-it section

**Only for:** guided product demonstrations

**Observed:** A centered demo-heading and concise support line introduce a two-column lesson: numbered instruction copy on the left and a 322×600px phone-like interactive example on the right. The frame is white with a 5px gray edge, 24px corners and a blurred oval shadow below. A small guide link closes the section.

**Transfer:** Teach one real task through a compact interactive surface and short steps, keeping product-interface styling contained to the demonstration.

**Text style:** `demo-heading` — Inter 900 · 60px/1.25

### Resource updates

**Only for:** news-rich landing pages

**Observed:** A centered heading-lg introduces three image-led columns with 16px gutters. Each uses an inset wide image, heading-card, italic publisher, caption-sized excerpt, category pill and date. A centered Standard action sits 48px beneath the grid.

**Transfer:** Use actual resource titles and publishers; distinguish editorial material from the primary benefit narrative.

**Text style:** `heading-lg` — Inter 900 · 60px/1.2

### Editorial explanation and objections

**Only for:** editorial explanation pages

**Observed:** A heading-editorial and 768px reading-width introduction lead into a four-column Editorial entry card grid. Later text-and-image splits use a 72px gap and a tall scene. The final content section pairs a large transparent-backed conceptual illustration with a column of FAQ rows.

**Transfer:** Move from the problem to distinct principles, then explain how they reinforce one another and answer the reader's skeptical questions.

**Text style:** `heading-editorial` — Inter 900 · 36px/1.2

### Catalog chapters and inset callouts

**Only for:** application and capability catalogs

**Observed:** A left article column holds heading-editorial, short support and three-column image-led Editorial entry cards. A 320px pale blue-violet sticky index sits to the right. Between chapters, a pale horizontal lavender gradient callout uses a 24px heavy title, 18px support, a small conceptual illustration and Standard action. The ending uses a similar callout with a readiness statement and two actions, then Feedback buttons.

**Transfer:** Group capabilities by reader intent, preserve the narrow article plus index composition and use inset callouts for related next steps.

**Text style:** `heading-editorial` — Inter 900 · 36px/1.2

## Page flow

**Storyline:** Illustrated invitation → plain-language benefit → concrete proof → deeper exploration → appropriate next steps → resource navigation.

### Broad marketing landing page for a complex platform

1. **Promise** — A panoramic illustrated world precedes a compact, heavy centered promise and paired actions.
2. **Benefit and proof** — A large chapter introduction pairs with sober metrics, then alternating illustrated benefit chapters use fact plaques.
3. **Product experience** — A guided browser lesson makes an abstract promise tangible.
4. **Differentiation** — Gray-backed proof mosaic contrasts a vivid violet lead tile with quieter supporting benefits.
5. **Current activity** — An isolated illustrated campaign invitation and three editorial updates demonstrate a living ecosystem.
6. **Closing action** — A soft radial wash frames illustrated audience routes, each with a concrete destination.
7. **Resource navigation** — A full resource footer ends with a gray social-and-administrative strip.

**Transfer:** Use the image-led, long-form benefit narrative as the default for new landing pages. Arrange proof, demonstration and current activity according to the product's strongest material.

### Explain the convictions or operating principles behind a product

1. **Framing** — An illustrated panorama with a small translucent left panel introduces the subject.
2. **Problem and alternatives** — Readable introductory text leads to a four-card explanation grid.
3. **Reasoning** — A text-and-portrait split explains how the commitments work together.
4. **Objection handling** — A large conceptual illustration balances four compact question rows.
5. **Reader feedback** — A usefulness question and two outlined thumb buttons precede the shared resource footer.

**Transfer:** Use this more compact editorial hierarchy when the goal is comprehension and trust rather than a broad conversion story.

### Help readers discover concrete applications or capabilities

1. **Invitation** — An illustrated panorama, left glass panel and direct exploration action establish the catalog.
2. **Orientation** — Update metadata, contributors, a short introduction and a persistent chapter index prepare the reader.
3. **Capability chapters** — Category headings and short explanations introduce contained illustrations, descriptions and aligned card actions.
4. **Related opportunity** — A pale lavender inset callout spotlights a related emerging capability.
5. **Readiness and action** — A compact tinted closing callout explains prerequisites and provides two practical actions.
6. **Feedback and navigation** — A usefulness prompt leads into the same six-column resource footer.

**Transfer:** Use the article-and-index variant for a longer catalog; preserve grouping and practical descriptions instead of turning it into an undifferentiated wall of tiles.

## Writing

Confident and educational, with an optimistic belief that technical systems can give people more agency. Plain-language explanations and everyday contrasts make the subject feel accessible rather than exclusive.

**Do not copy:** Do not reuse Ethereum names, symbols, distinctive artwork, campaign identities, discount codes, statistics, uptime claims, product-specific assertions or source headlines as new-product claims. The quoted examples illustrate voice only.

- **Addressing the reader:** Speak directly to you and your. Name the product when explaining what it does; use we sparingly, mainly when guiding a lesson.
- **Rhythm:** Short benefit headlines, then complete explanatory sentences. Contrasts and brief parallel negatives give longer paragraphs momentum without slogans full of hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A broad category promise made personal through ownership or agency. | 5–9 words | “The internet that belongs to you” |
| Benefit heading | A direct verb-led outcome, or an exceptionally short durability claim. | 3–9 words | “Use the internet without being watched”<br>“Built to last” |
| Supporting explanation | Explain a familiar situation before contrasting the alternative in plain language. | 2–4 sentences | “No account tied to your name. No company watching your balance.” |
| Primary action | A plain verb and a concrete next step, with little promotional decoration. | 2–4 words | “Start here”<br>“Start exploring” |
| Question | State the reader's real skepticism rather than an internal feature taxonomy. | 9–18 words | “I'm fine with how things work now. Why should I care?” |
| Closing reassurance | Address practical friction with short parallel clauses. | 1–2 sentences | “Takes 2 minutes to get started. No credit check, no paperwork, no minimum balance.” |

**Words and phrasing to use:** you; your; control; own; open; explore; start; learn; in plain language; without

**Avoid:** revolutionary; disruptive; next-gen; synergy; exclusive access as a default promise; unexplained acronyms

**Rules:**

- State what readers can do before explaining the machinery.
- Define specialist terms when first introduced; parenthetical abbreviations can follow a plain-language name.
- Use everyday comparisons to explain abstract infrastructure.
- Keep numerical proof labeled and make its relation to the benefit explicit.
- Use questions to acknowledge concerns rather than pretend there are none.

## Do's and Don'ts

### Do

- Keep the landing promise at 64px, weight 900 and 0.9 leading, with balanced two-line wrapping.
- Give major story chapters 128px of separation so the illustrated scenes do not become a dense gallery.
- Keep the 14px uppercase chapter label close to its heading with an 8px gap.
- Use 32px interior padding in proof and audience-route cards, and 24px in the editorial card variant.
- Give the highlighted proof tile an actual captioned measure, not just a decorative oversized number.
- Carry the opening illustration vocabulary into the closing 352×192px route banners.
- Keep card actions aligned at the bottom across unequal paragraph lengths.
- Maintain 14px footer links and heavy 14px resource labels to make the dense ending scan well.

### Don't

- Do not replace weight-900 headings with a light luxury sans or introduce a serif display face.
- Do not add negative tracking to every headline; normal tracking is part of the broad, direct character.
- Do not apply 38px card corners to ordinary controls; their default corners are 4px or 8px.
- Do not spread saturated violet across every section; concentrate it in actions and the highlighted proof treatment.
- Do not give every card a large drop shadow; most are flat gray or white with a 1px edge.
- Do not turn contained conceptual card art into full-bleed photographic backgrounds.
- Do not make all resource links violet by default; footer links are muted gray.
- Do not replace the dense utility ending with a huge centered logo and a lone copyright line.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare box-shadow and transform transitions of 0.2s cubic-bezier(.4, 0, .2, 1).
- Clickable route and editorial cards declare all-property transitions of 0.3s cubic-bezier(.4, 0, .2, 1); their declared hover scale remains 100% 100%.
- The interface declares short fade-in animations of 0.15s ease-in-out, plus accordion and carousel-related keyframes.

**Transfer:**

- Use the pale-violet offset-shadow hover on actions rather than a zoom effect.
- Keep content cards visually stable on hover; the fine outline and focus indicator carry the interaction.

**Unknown:**

- Illustration animation, carousel autoplay cadence and actual accordion travel timing are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints are 480px, 768px, 992px, 1280px and 1536px.
- The landing headline declares smaller text sizes before reaching its 64px desktop size; its leading changes to 0.9 at the larger layout.
- Hero actions use a column on narrow layouts and a row at the small breakpoint. Editorial hero panels become absolute translucent overlays only in the widest layout.
- Catalog layout declares a reversed column layout below its large breakpoint. Closing cards use auto-fill with a 352px minimum constrained to the available width.

**Transfer:**

- On narrow screens, preserve the panorama's central focal object and move readable text into its own white block rather than squeezing a translucent panel over busy art.
- Stack benefit scenes and proof tiles; keep the visual emphasis on one violet tile.
- Stack routes without losing their illustrated banners or bottom-aligned actions. Reflow the catalog index above the article when side-by-side space is insufficient.

**Unknown:**

- Exact mobile panorama cropping, navigation menu presentation and settled narrow-screen typography are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
