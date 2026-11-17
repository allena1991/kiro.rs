# Qonto — business in motion

## Overview

A matter-of-fact business style with a cinematic, human face. Black and white architecture, rounded grotesk typography and softly illuminated gray panels give practical software an assured, approachable presence. Warm workplace photography and isolated interface fragments alternate across spacious, modular layouts; it suits products that turn complicated daily work into something manageable.

### Essentials

- A promise reads like a stack of confident full stops: QontoSans 72px/80px, weight 700, normal tracking; section statements step down to 56px/64px at 600.
- The default opening puts real work behind the words: an edge-to-edge 900px photographic stage, a lower-left headline spanning about two thirds of the width, and actions 48px above its bottom edge. Focused product pages instead use white split or centered openings.
- Actions are small rectangles, not capsules: 8px corners, 52px height, 18px/28px regular labels, 16px horizontal padding, and a filled primary beside a 1px outlined secondary.
- Color belongs to life and demonstration, not the page furniture: all recurring marketing text, buttons and panels use neutrals. Alternate substantial #050505 chapters with white chapters; warm photos carry most chroma, while tiny interface status accents stay inside demonstrations.
- Capabilities sit in soft spotlights: 24px rounded cards, 24px gutters and radial gray backings, with a brief title at the top and an isolated interface or device below. Include this illuminated product-card device even when the product must be represented by a simple custom diagram.
- The conversion appeal becomes a scene: a wide photographic panel inset 48px horizontally and 80px vertically, rounded 24px, with a dark left scrim and a 56px promise. Retain a real-world scene and functional product detail rather than replacing this device with an abstract gradient.
- The ending changes key: a dense black directory gives way to a white identity-and-assurance strip, a prominent wordmark-sized identity, small monochrome credentials, and a 1px separating rule. Carry this two-tone signature into the new brand's footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#050505` | `--color-ink` | text, background, action, border | Primary text on white, inverse section canvas and dark filled actions on light backgrounds. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, action, border | Main light canvas, inverse text and filled actions on dark backgrounds. |
| Charcoal panel | `#1a1a1a` | `--color-panel` | surface | Outer dark-card backing, footer pricing tile and assurance panel. |
| Charcoal spotlight midtone | `#2c2c2c` | `--color-radial-mid` | surface | Middle stop in dark card illumination. |
| Charcoal spotlight center | `#3d3d3d` | `--color-radial-center` | surface, text | Center of inverse radial cards; small dark support text on white. |
| Dark-panel edge | `#616161` | `--color-dark-rule` | border | Outlined dark tiles and calculator input edges. |
| Inactive pagination | `#626262` | `--color-pagination` | surface | Inactive carousel dots on inverse sections. |
| Muted statement | `#8f8f8f` | `--color-muted` | text | Secondary phrase within a large inverse heading. |
| Light divider | `#b8b8b8` | `--color-rule` | border, surface | Comparison and accordion dividers; inactive vertical progress rails. |
| Inverse secondary text | `#cccccc` | `--color-secondary` | text, border | Footer directory text, small inverse support text and the white footer's separator. |
| Light spotlight center | `#e0e0e0` | `--color-spotlight` | surface | Center of the light radial card illumination. |
| Soft gray | `#f5f5f5` | `--color-soft` | surface, background | Flat feature panels and the outer edge of light radial card backings. |

## Typography

- **QontoSans** — All marketing headings, body copy, actions and navigation. A friendly rounded grotesk with open counters and a strong, broad bold cut; the same family handles both practical labels and assertive display lines. If unavailable, use **DM Sans**. Use 400, 600 and 700; preserve the relaxed normal tracking and check line wraps. Font stack: "QontoSans", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | QontoSans | 700 | 72px | 80px | normal | Hero promises, often split into short punctuated lines. |
| heading-lg | QontoSans | 600 | 56px | 64px | normal | Main section leads, conversion-panel promises and large proof numbers. |
| heading | QontoSans | 600 | 40px | 48px | normal | Compact split-section headings and assurance statements. |
| card-title | QontoSans | 600 | 24px | 32px | normal | Feature titles, accordion questions and proof-strip lead claims. |
| body | QontoSans | 400 | 18px | 28px | normal | Standard paragraphs, support copy and full-size action labels. |
| body-compact | QontoSans | 400 | 18px | 24px | normal | Denser feature explanations and the footer pricing link. |
| small | QontoSans | 400 | 16px | 26px | normal | Navigation line boxes, compact answers and comparison content. |
| header-action | QontoSans | 400 | 16px | 1.5 | normal | Compact conversion action in navigation. |
| directory-label | QontoSans | 700 | 16px | 26px | normal | Uppercase footer category names; not a general section eyebrow. |
| caption | QontoSans | 400 | 14px | 22px | normal | Footer links and secondary explanatory lines. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| customer-story sections | quote | QontoSans | 400 | 22px | 32px | normal | Editorial customer quotation beside a portrait. |

**Notes:**

- Keep tracking normal throughout: hierarchy comes from size, weight, line breaks and contrast, not compressed letterspacing.
- Headings use 600 except the 700 hero; body and action labels remain 400. Large numbers reuse heading-lg instead of introducing a separate numeral face.
- Use sentence case and visible punctuation in display promises. There is no recurring uppercase eyebrow above the main section headings.

## Layout

**Density:** Airy at section scale and compact inside demonstrations; wide breathing room separates short, information-rich cards.

### Spacing

**Spacing system:**

- **grid** 8px — Dominant layout rhythm; small optical and control offsets can fall outside it.

| Value | Use |
| --- | --- |
| 8px | Compact title-to-copy gaps and gaps between vertical selector items. |
| 16px | Body-copy gaps, paired actions and compact inner padding. |
| 24px | Card padding, grid gutters and quote-to-attribution separation. |
| 32px | Larger stacked text spacing and comparison inner vertical padding. |
| 48px | Desktop page sides, heading-to-actions spacing and inset-panel inner padding. |
| 56px | Section-heading to feature-grid or story-carousel separation. |
| 64px | Split feature section vertical padding. |
| 80px | Standard section top and bottom padding; vertical inset around panoramic panels. |
| 128px | Top clearance for white product openings under the fixed header. |

### Containers and grids

- **page-container**: max width 1600px · 12 columns · gap 24px · side padding 48px. Centered desktop architecture. At 1440px the usable span is 1344px; full-bleed bands sit outside this container.
- **feature-trio**: 3 columns · gap 24px. Equal 432px feature cards or centered benefit columns at the desktop width.
- **paired-panels**: 2 columns · gap 24px. Two 660px choices; also a useful base for copy and product-scene splits.
- **bento**: 24 columns · gap 24px. Fine-grained spans support short, tall and double-width cards within the same 1344px chapter.
- **copy-measure**: max width 510px. Short support copy within split layouts; narrower card paragraphs follow their panel width.
- **story-split**: 12 columns · gap 24px. Seven columns for text and four for a right-side portrait, with breathing room between; text spans roughly 774px and portrait 432px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 8px |
|  | cards-and-scenes | 24px |
|  | pagination | 6px |
| interactive estimate sections | calculator-inputs | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| assurance-halo | `0px 0px 20px 0px rgba(255, 255, 255, 0.08)` | Subtle luminous edge on the dark assurance panel; ordinary cards have no drop shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default light sections and identity footer.

**CSS:** `background: #ffffff; color: #050505`

#### Inverse chapter · level 0

**Use:** Cinematic opening, grouped capability chapters, customer carousel and directory footer.

**CSS:** `background: #050505; color: #ffffff`

**Observed:** Dark areas form continuous chapters rather than little dark cards scattered on white.

**Transfer:** Group related product demonstrations into one inverse region, then switch cleanly to white.

#### Light spotlight card · level 1

**Use:** Default light capability tiles and product illustration backings.

**CSS:** `background: radial-gradient(66.82% 50%, #e0e0e0 0%, #f5f5f5 100%); border-radius: 24px; overflow: hidden`

**Observed:** Soft tonal center behind floating interface fragments; no colorful marketing wash or heavy shadow.

**Transfer:** Retain the gradient even for a minimal custom product diagram.

#### Dark spotlight card · level 1

**Use:** Capability bento and inverse lifecycle carousel.

**CSS:** `background: radial-gradient(50% 50%, #3d3d3d 0%, #2c2c2c 50%, #1a1a1a 100%); border-radius: 24px; color: #ffffff; overflow: hidden`

**Observed:** A restrained gray spotlight separates dark interface art from the black section.

**Transfer:** Let the product fragment occupy the lower portion, with clear text above.

#### Flat soft panel · level 1

**Use:** Simple solution summaries, comparison column backings and light explanatory bands.

**CSS:** `background: #f5f5f5; border-radius: 24px`

**Observed:** The full-width explanatory band has square outer edges; rounded corners belong to contained panels.

**Transfer:** Use flat gray for text-led panels, radial gray for product-led ones.

#### Photographic scrim · level 1

**Use:** Panoramic conversion scene.

**CSS:** `background: linear-gradient(90deg, rgba(5, 5, 5, 0.67) 0%, rgba(5, 5, 5, 0.67) 20%, rgba(5, 5, 5, 0) 60%); border-radius: 24px`

**Observed:** Overlaid on photography so white copy remains legible at the left while the right-side subject stays bright.

**Transfer:** Keep the subject beyond the darkest part of the scrim.

#### Assurance edge light · level 1

**Use:** A compact trust or reliability panel on an inverse chapter.

**CSS:** `background: linear-gradient(#1a1a1a, #1a1a1a) padding-box, conic-gradient(from 229.56deg, rgba(255,255,255,0) 0%, rgba(255,255,255,0.8) 8%, rgba(255,255,255,0) 18%, rgba(255,255,255,0) 100%) border-box; border: 1px solid transparent; border-radius: 24px; padding: 48px; box-shadow: 0px 0px 20px 0px rgba(255,255,255,0.08)`

**Observed:** The tiny bright segment follows the edge, not a glow filling the whole page.

**Transfer:** Pair a plain assurance statement with a small row of concrete trust facts.

## Components

### Fixed navigation

**Use:** Persistent global orientation and compact conversion.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 80px; padding: 0px 48px; background: rgba(5,5,5,0.7); backdrop-filter: blur(6px); color: #ffffff`

**Text style:** `small` — QontoSans 400 · 16px/26px

**Observed:** Identity on the left, six short destinations across the middle, locale and sign-in before a compact filled action at the right. It changes to dark lettering and a dark action over white content; it is not a floating pill.

**Transfer:** Use the inverse treatment over a cinematic opening and a light treatment over white chapters.

### Primary button

**Use:** Main conversion in the default inverse opening and scene panels.

**CSS:** `background: #ffffff; color: #050505; border-radius: 8px; padding: 12px 16px; height: 52px; text-align: center; white-space: nowrap`

**Text style:** `body` — QontoSans 400 · 18px/28px

**Observed:** A plain filled rectangle with no leading icon. On white sections the polarity reverses to near-black fill and white text. Width follows the label; the typical short label occupies 175px.

**Transfer:** Keep one dominant action, with the outlined companion only when it offers a meaningful alternative.

### Secondary button

**Use:** Plan exploration or lower-commitment companion action.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid #ffffff; border-radius: 8px; padding: 11px 16px; height: 52px; text-align: center`

**Text style:** `body` — QontoSans 400 · 18px/28px

**Observed:** Sits 16px from the primary. The light-section variant changes text and border to ink without adding a fill.

### Header action

**Use:** Compact always-available conversion in the navigation.

**CSS:** `background: #ffffff; color: #050505; padding: 12px 16px; height: 48px; border-radius: 8px`

**Text style:** `header-action` — QontoSans 400 · 16px/1.5

**Observed:** Smaller type than the main page buttons; its light-page variant uses dark fill.

**States:** Declared: hover background-color color-mix(in oklab, #fff 92%, transparent); active background-color rgb(55, 55, 55).

### Capability card

**Use:** A visual benefit in an inverse bento.

**CSS:** `background: radial-gradient(50% 50%, #3d3d3d 0%, #2c2c2c 50%, #1a1a1a 100%); border-radius: 24px; padding: 24px 24px 0px 24px; display: flex; flex-direction: column; gap: 24px; color: #ffffff; overflow: hidden`

**Text style:** `card-title` — QontoSans 600 · 24px/32px

**Observed:** Title and a short paragraph lead; a product fragment anchors the bottom. Common footprint is 432px by 408px, with tall or double-width siblings. The light variant uses Light spotlight card and ink text.

**Transfer:** Show one task or benefit per tile, not a complete dashboard.

### Outlined proof tile

**Use:** A short text-led fact inside the bento.

**CSS:** `border: 1px solid #616161; border-radius: 24px; padding: 24px; display: flex; flex-direction: column; gap: 24px; color: #ffffff`

**Text style:** `card-title` — QontoSans 600 · 24px/32px

**Observed:** No illustration required: a short lead and 18px support sit on the same black as the chapter. It balances larger illustrated tiles.

### Progress pagination

**Use:** Customer-story and capability carousels.

**CSS:** `background: #626262; border-radius: 6px; height: 12px; width: 72px; position: relative; overflow: hidden`

**Observed:** The active marker is a horizontal 72px bar with a white progress fill; inactive markers are 12px circles. A pause control accompanies the story carousel. Light sections use an ink active bar and lighter inactive dots.

**Transfer:** Keep the longer active marker rather than using identical dots for every slide.

### Footer pricing tile

**Use:** A promoted commercial destination beside the directory.

**CSS:** `background: #1a1a1a; border-radius: 24px; padding: 24px; width: 212px; color: #ffffff`

**Text style:** `body-compact` — QontoSans 400 · 18px/24px

**Observed:** Short link and a circular diagonal arrow occupy the top; 14px secondary copy sits below. Ratings stack beneath the tile, separate from the directory columns.

### Directory link

**Use:** Dense multi-column footer navigation.

**CSS:** `color: #cccccc; padding-bottom: 2px; background-image: linear-gradient(to right, #050505 0%, #050505 100%); background-size: 0px 1px; background-position: 100% 100%; background-repeat: no-repeat`

**Text style:** `caption` — QontoSans 400 · 14px/22px

**Observed:** Regular links sit below uppercase bold category labels; row wrappers add 8px bottom space. A different white identity strip follows the directory.

### Comparison cell

**Only for:** product comparison sections

**Use:** Detailed choice between related product formats.

**CSS:** `border-bottom: 1px solid #b8b8b8; padding: 16px; display: flex; flex-direction: column; justify-content: center; text-align: center`

**Text style:** `small` — QontoSans 400 · 16px/26px

**Observed:** Three 329px product columns beside a 358px left label column. Alternating light-gray column backings run vertically behind all rows; product thumbnails and names crown the columns. Inner cells add 32px vertical and 16px horizontal padding.

**Transfer:** Keep row labels left-aligned and product answers centered; separate full columns tonally rather than boxing every answer.

### Calculator input

**Only for:** interactive estimate sections

**Use:** User-entered values in a dark savings or value estimator.

**CSS:** `background: #050505; color: #ffffff; border: 1px solid #616161; border-radius: 4px; padding: 8px 12px; height: 44px`

**Text style:** `small` — QontoSans 400 · 16px/26px

**Observed:** Two columns of labeled fields sit in an 8px-radius charcoal panel with 16px padding. The result is a separate thin outlined panel, with an uppercase label and a larger total, then comparison rows and paired actions.

**Transfer:** Use a transparent formula and a concise qualification below results.

## Imagery and graphics

### Working-life cinematography

**Use:** Default opening and panoramic conversion scenes; supporting photographic feature tiles.

**Observed:** Close views of hands, a device and the act of using a service; wider views place an independent professional in a real shop or studio. Warm daylight, wood, ceramics, fabric and human skin provide color against neutral page furniture. Subjects generally favor the right side when copy overlays the left; photography is full bleed in the opening and rounded elsewhere.

**Transfer:** Photograph the new product in a real, tactile working setting. Without video, use a high-quality still of a person completing the key task; a practical object or screen must communicate the service, rather than a generic smiling portrait.

### Floating interface fragments

**Use:** Product-card lower halves, split explanations and occasional overlays on workplace photography.

**Observed:** Small groups of white or dark application panels are isolated from the full app: transaction rows, a document, a confirmation, a compact form or a phone screen. Layered sheets and subtle shadows give shallow depth, while neutral radial illumination backs the group. A phone can be intentionally cut off at the card bottom. Tiny green and blue statuses belong to the interface, not headline decoration.

**Transfer:** Create two or three readable task fragments using the new product's own interface. The minimum version is a precise custom vector diagram with one primary control and one outcome, not an unrelated dashboard.

**Build:** Use a neutral radial card backing; center a stack of two or three SVG or HTML panels in its lower two thirds. Offset successive sheets by 8px–16px, draw 1px low-opacity dark outlines and modest corner curves, and place a single foreground action or result. For a phone, add a near-black rounded outline around a white screen and let its bottom pass through the card clipping edge.

### Photographic feature tile

**Use:** Audience examples and photo-led bento cells.

**Observed:** Natural-color images fill a 24px rounded tile, typically 432px by 592px or a 660px paired format. White title and copy sit at the top over a dark-to-transparent vertical scrim. A softened image layer makes the copy region feel continuous with the sharp photograph beneath.

**Transfer:** Use distinct real-use contexts for distinct tiles; reserve calm darker image space at the top.

**Build:** Fill the rounded container with an object-fit cover image. Duplicate the image as an absolute layer with blur(6px), mask it into the upper copy area, and overlay linear-gradient(rgba(5,5,5,0.67) 0%, rgba(5,5,5,0.67) 10%, rgba(5,5,5,0) 50%). Keep the rest of the photograph sharp.

### Customer portraits

**Use:** Story proof, either a dark image carousel or white editorial split.

**Observed:** Authentic people in their workplace, with warm natural backgrounds, eye-level framing and 24px rounded corners. The white split uses a tall 432px-wide portrait; the carousel uses landscape panels with white quote text and a customer mark near the top.

**Transfer:** Use credible practitioners in their own environment. Keep the portrait subordinate to the result and quotation, not a fashion-style campaign.

### Neutral orbital integration art

**Use:** A wide integration or ecosystem panel.

**Observed:** A light radial backing supports a large dark central product mark and smaller circular partner marks on pale concentric rings; circles extend beyond the clipped edges. Text occupies the left half.

**Transfer:** Represent the new product's ecosystem with truthful partner marks or simple labeled circular nodes.

**Build:** On Light spotlight card, place three low-contrast concentric SVG circles behind a central dark disk in the right half. Position smaller disks around the rings, partly clipped at the panel boundary. Leave the left half free for a two-line heading and short paragraph.

### Edge-light assurance graphic

**Use:** Trust panel on dark sections.

**Observed:** A faint white halo and one moving bright border segment make a charcoal panel feel lightly metallic without a glossy fill.

**Transfer:** Use the Assurance edge light surface as the minimum equivalent; populate it with specific reliability facts.

**Build:** Layer an opaque charcoal linear gradient clipped to padding-box above a conic gradient clipped to border-box. Keep a 1px transparent border, 24px radius, a short white peak near the first 8% of the sweep, and a 20px white shadow at 0.08 alpha.

### Icons

**Observed:** Small, practical monochrome pictograms; feature icons commonly sit at 32px within 56px rounded-square backings. Outline navigation or utility symbols use roughly 1.5px strokes at 16px–25px. Chevrons sit at the right of questions; diagonal arrows signal destination links.

**Transfer:** Choose consistent simple outline symbols in the local text color. Use pale squares on white and charcoal squares on black; keep multicolor partner marks in imagery rather than turning them into the marketing icon system.

## Section recipes

How recurring sections are built.

### First screen: Cinematic working-life opening

**Observed:** A 900px-tall edge-to-edge photographic/video stage fills the first viewport. Back to front: a near-black base, cover imagery of hands completing a task with the key object dominating the right half, a 15% near-black veil and bottom fade to black starting at 78.6%, then white text and actions. Fixed navigation overlays the top 80px. The lower-left copy spans about 870px: a compact rating line, a three-line 72px/80px bold promise, and a filled Primary button plus Secondary button. Side inset is 48px; the actions sit 48px above the bottom. No separate long explanatory paragraph appears in this opening. The whole promise, actions and main object are visible within 900px; the three-part proof strip begins below the fold.

**Transfer:** Stage the new product's decisive real-world moment and write three short benefit or category statements that remain readable over the left side. Use a sharp still when video is unavailable. Focused product pages use a scoped white opening: 128px top clearance, black display copy left, a 560px-wide rounded workplace image right, support copy near the lower part of the text column and actions below. A focused audience page can center the promise and actions above three photographic tiles.

**Avoid:** Do not turn the default into a centered text-only SaaS hero, obscure the object with copy, or add decorative colored blobs behind the headline.

**Text style:** `display` — QontoSans 700 · 72px/80px

### Proof strip

**Observed:** Three equal columns, 24px gaps, each with a 24px semibold claim and an 18px support line 16px below. It continues the inverse opening on black; product overview variants use soft-gray panels on white. Compact icon tiles can precede the claim.

**Transfer:** Use three different reasons to trust the product, not three paraphrases of the same promise.

### Heading pair and bento

**Observed:** Inverse chapter with 80px vertical padding. A 56px lead pairs white wording with a muted-gray qualifying phrase, and an outlined action aligns at the right. After 56px, Capability cards, Outlined proof tile and photographic cells form an asymmetric 24px-gutter grid: short fact tile, tall product tile, a photograph and a double-width material close-up.

**Transfer:** Vary tile size by the explanatory value of the content. Include one restrained tonal heading contrast and one wider visual, rather than forcing all cells into equal cards.

**Text style:** `heading-lg` — QontoSans 600 · 56px/64px

### Task-selector split

**Observed:** White chapter with a 40px two-line heading at the left, then three vertically stacked 24px titles and compact 18px copy. Each item has a 2px vertical rail; the selected item is dark and inactive items are muted. A large 740px square product illustration fills the right side; an outlined action follows the left text.

**Transfer:** Use for a product with several related modes. Keep one illustration active and make the selector's rail communicate progression rather than adding tab pills.

**Text style:** `heading` — QontoSans 600 · 40px/48px

### Light feature trio

**Observed:** A 56px section statement and optional right-side action precede three Light spotlight cards with 24px gutters. Title and body occupy the upper part; interface art occupies the lower part, often 432px square. Cards are around 612px–644px tall.

**Transfer:** Explain three discrete jobs with coherent art and similarly sized paragraphs. Keep each interface fragment simpler than the actual application.

**Text style:** `heading-lg` — QontoSans 600 · 56px/64px

### Focused split explanation

**Observed:** White or soft-gray band, 64px vertical padding, copy and a roughly 560px square illustration or photograph in opposite halves. A 56px heading breaks into two or three lines, followed by a short paragraph and compact paired actions.

**Transfer:** Use to explain price, a difficult edge case or a single important feature. Choose side placement for the image composition, not by mechanically alternating every section.

**Text style:** `heading-lg` — QontoSans 600 · 56px/64px

### Immersive story carousel

**Observed:** Black chapter with 56px white heading and oversized landscape photographic story panels after a 56px gap. One panel is prominent while the next peeks in from the right. Quote and identity sit within the darkened top-left image area; Progress pagination and pause control sit centered below.

**Transfer:** Use when there are several visual customer stories; retain partial-next-slide visibility and the elongated active marker.

### Panoramic conversion scene

**Observed:** A 664px section contains a 1344px by 504px photograph with 48px side and 80px vertical insets and 24px corners. Photographic scrim supports a left-aligned 56px promise, an 18px line 16px below and actions after 48px. The working subject or device remains clear on the right. A light radial panel with an oversized cropped phone is the product-led variant.

**Transfer:** Bring the promise back to a person doing the work. Use one decisive benefit and one primary action; the scene is the visual payoff, not another feature grid.

**Text style:** `heading-lg` — QontoSans 600 · 56px/64px

### Two-tone directory ending

**Observed:** A near-black directory starts with 80px padding and a 12-column, 24px-gutter layout: Footer pricing tile and ratings at left, grouped directory columns to the right. Labels are 16px bold capitals, links 14px regular gray. Then a white identity strip gives a 343px by 100px wordmark-sized mark substantial room at left, with social links, credentials and app badges to the right. A #cccccc 1px rule separates this from compact legal links, locale and legal copy.

**Transfer:** End with the same black-to-white shift. Scale the new identity to comparable visual prominence and use only relevant assurance or distribution badges.

### Customer result spread

**Only for:** customer-story sections

**Observed:** White split with an upper-left 56px heading, two plain black 56px metrics lower in the text column, short 18px metric captions, a 22px quote and an attribution. A tall rounded workplace portrait fills the right side. In the variant without metrics, deliberate open space separates title and quote.

**Transfer:** Give the numbers breathing room and truthful short labels; keep the portrait, attribution and result visibly connected.

**Text style:** `quote` — QontoSans 400 · 22px/32px

### Value estimator

**Only for:** interactive estimate sections

**Observed:** Inverse two-column section: 40px heading and explanatory copy on the left, Calculator inputs in a charcoal panel on the right. A bordered result block emphasizes the primary total, then smaller comparison rows and equal-width filled and outlined actions. Small qualification text follows.

**Transfer:** Show assumptions near the controls and explain the result in ordinary language. Restrict the interactive visual system to the actual estimator.

**Text style:** `heading` — QontoSans 600 · 40px/48px

### Detailed product comparison

**Only for:** product comparison sections

**Observed:** A centered 56px heading precedes three product thumbnails and names. Comparison cells continue in long aligned rows against alternating white and soft-gray vertical columns. The leftmost column contains feature labels; thin rules span the rows. A centered order action follows the table.

**Transfer:** Use only for genuinely comparable choices, and preserve the strong continuous column backings rather than making independent pricing cards.

### Question split

**Only for:** detail pages with buying objections

**Observed:** White section with 80px vertical padding. A 40px heading occupies the left, while a 774px question column sits on the right. Question controls use 24px/32px semibold type, right-aligned chevrons and roughly 64px title rows; answers use 16px/26px and bottom rules.

**Transfer:** Write questions as actual purchase concerns. Keep the short answers in the same column, with chevrons indicating expansion.

**Text style:** `card-title` — QontoSans 600 · 24px/32px

## Page flow

**Storyline:** Promise → concrete proof → grouped capabilities → practical reassurance → customer outcome → conversion scene → directory and identity.

### Broad brand and product introduction

1. **Promise** — Full-viewport working-life scene with three stacked statements and paired actions.
2. **Social proof** — Three compact trust claims continue the inverse canvas.
3. **Capability chapters** — Asymmetric dark bento, white selector split and light task cards introduce the breadth of the product.
4. **Ecosystem and onboarding** — Wide integration art, three benefit columns and a photographic product-in-use panel.
5. **Customer proof and reassurance** — Dark story carousel and a lightly illuminated assurance panel.
6. **Closing call** — Inset panoramic photograph with a short problem-and-resolution promise.
7. **Directory** — Black navigation and pricing area resolves into the white identity and legal strip.

**Transfer:** Use this as the default broad landing-page narrative, selecting the chapters that explain the new product without requiring the same section count.

### Detailed product page for a physical or on-the-go workflow

1. **Promise** — Centered black display promise on white, paired actions and three real-use photographic tiles.
2. **Solution choice** — Two soft-gray solution summaries introduce alternative methods.
3. **Quantified value** — Inverse estimator makes the economic benefit tangible.
4. **Capability chapters** — Dark bento gives way to a white price explanation and short platform-choice panels.
5. **Comparison** — Long feature table with device thumbnails, tonal columns and an order action.
6. **Customer proof** — White editorial quote-and-portrait spread.
7. **Conversion and objections** — Photographic closing scene, compact related-product bridge and split FAQ.
8. **Directory** — Shared two-tone directory and identity ending.

**Transfer:** For a product with several formats, let the centered opening clarify the promise and let the comparison table carry detailed differences.

### Detailed product page for a digital workflow

1. **Promise** — White split opening combines a short two-line promise, low-set support and workplace photo with outcome overlays.
2. **Workflow demonstration** — Dark horizontal lifecycle cards show adjacent stages and a peek of the next card.
3. **Capabilities** — Light three-card grid and concise icon benefits.
4. **Practical reassurance** — Photographic compliance panel, gray edge-case explanation and centered offer with a wide workplace image.
5. **Quantified customer proof** — Two large plain-black metrics, quotation and right-side portrait.
6. **Closing call** — Light spotlight panel pairs actions with a bottom-clipped phone.
7. **Related capability** — Two photographic tiles point to a complementary workflow before the shared directory ending.

**Transfer:** Use for end-to-end software: explain the lifecycle, handle a difficult exception, then prove the result.

### Category overview that routes between related solutions

1. **Promise** — White split opening with a workplace portrait and compact outcome overlay.
2. **Trust and routes** — Three soft proof panels followed by paired photo-led and interface-led destination cards.
3. **Social proof** — Centered monochrome customer marks.
4. **Demonstration** — Split heading and short introduction above a wide video.
5. **Benefits and breadth** — Inverse three-column benefits followed by a light horizontal capability carousel.
6. **Closing call** — Photographic conversion scene followed by the two-tone directory ending.

**Transfer:** Keep an overview focused on choosing a path; put exhaustive feature differences on the detail pages.

## Writing

Direct, capable and reassuring, with a conversational simplification of complex business work. Benefits are expressed as everyday outcomes, with practical details and qualifications close to factual claims.

**Do not copy:** Do not reuse Qonto's name, logo, customer identities, quotes, ratings, client counts, financial rates, regulatory claims, partner marks or proprietary product imagery. Replace them with the new brand's own assets and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to 'you' and 'your business'; use 'we' for practical support and the product name for capabilities. Favor verbs that describe a completed task.
- **Rhythm:** Short headline clauses, often 3–9 words, use periods, questions and parallel phrasing. Supporting copy is usually one or two sentences; action labels are concise verbs. Longer detail belongs in comparison rows or answers, not the hero.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name the task, then remove the friction in a short second clause. | 4–8 words | “Get paid online. Seamlessly.”<br>“Get paid in person. Effortlessly.” |
| Section statement | Balance the user's gain with a reassuring qualifier or a second audience's gain. | 5–10 words | “Flexible for your clients. Trackable for you.”<br>“Transparent pricing. No fixed fees.” |
| Supporting explanation | Lead with a concrete action or outcome, then describe the mechanism without jargon-heavy framing. | 12–35 words | “Connect over 2,000 external tools & accounts directly to [Brand] - let all your data sync automatically.”<br>“Track payments, invoices, expenses, and cash flow in one place.” |
| Primary action | Verb plus the object of the next step. | 2–4 words | “Open an account”<br>“Calculate my savings”<br>“Book a demo” |
| Closing promise | A simple objection and its answer, or a readiness question tied to the main benefit. | 4–9 words | “Complicated? Not with [Brand].”<br>“Ready to get paid faster?” |

**Words and phrasing to use:** in one place; directly; automatically; your business; faster; transparent; no manual follow-ups; you review & approve

**Avoid:** revolutionary; disrupt the future; unparalleled synergy; magical; guaranteed success; shouting exclamations

**Rules:**

- Pair a simple promise with the actual mechanism that makes it possible.
- Use parallel short clauses to make breadth readable without a long introductory paragraph.
- Attach a timeframe, quantity or price only when it can be substantiated and appropriately qualified.
- Keep reassurance concrete: what happens, when it happens, and what remains under the user's control.

## Do's and Don'ts

### Do

- Keep the hero at 72px/80px and 700, with 56px/64px and 600 for main chapter statements.
- Use the 8px spacing rhythm, especially 24px gutters and 80px chapter padding.
- Maintain 48px desktop side insets and align text, cards and footer columns to the same container.
- Use 24px corners for major media and 8px for actions; let the difference signal scale.
- Include a neutral radial product-card device with a simple, sharply rendered task fragment.
- Keep the default cinematic stage grounded in a visible real-world action and use the dark scrim to protect the words.
- Give large customer metrics the same plain 56px treatment as section headings, with small factual labels.
- Preserve the black directory to white identity-strip transition at the ending.

### Don't

- Do not add a saturated brand-color button or headline gradient: recurring marketing controls are monochrome.
- Do not tighten the display with fashionable negative tracking; all main recipes retain normal spacing.
- Do not make the 52px actions pill-shaped or inflate their labels to semibold.
- Do not apply heavy drop shadows to every panel; gray radial backing provides the usual depth.
- Do not scale full application dashboards into unreadable thumbnails; isolate one task and outcome instead.
- Do not use identical equal-height tiles for the whole page; alternate asymmetric bento, split scenes and compact proof columns.
- Do not turn footer category labels into general uppercase eyebrows above every section.
- Do not replace naturally colored workplace photos with sterile blue-tinted corporate stock imagery.

## Motion and responsive

### Motion

**Observed:**

- Directory underline backgrounds declare background-size 200ms ease-in-out.
- Product cards declare transform-related transitions of 0.25s cubic-bezier(.4, 0, .2, 1).
- The active carousel marker declares width 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94).
- Navigation declares background-color 0.5s ease-out; the assurance border declares rotate-gradient 3s linear infinite and box-shadow 0.3s.

**Transfer:**

- Keep movement attached to the demonstrated mechanisms: story progression, active-selector rails and the subtle assurance edge. Retain a pause control for an automatically progressing story carousel.
- A still photograph preserves the opening's composition when video cannot be produced.

**Unknown:**

- Exact video edit timing, scroll choreography, fade-in durations and focus-visible states are not established.

### Responsive

**Observed:**

- Desktop uses a 12-column layout and 48px side padding. Layout classes also define six-column and nine-column grids, 16px smaller-screen side padding and 16px card corners before the 24px desktop treatment.
- Declared width breakpoints include 600px, 640px, 768px, 1024px and 1280px among other values. The comparison region declares horizontal overflow and snapping.

**Transfer:**

- On narrow screens, prioritize the decisive object and readable promise in the cinematic opening; preserve a dark text-safe area rather than shrinking the entire desktop composition.
- Stack copy and imagery for split explanations; convert capability trios to a vertical sequence or a clearly navigable horizontal strip. Keep the comparison horizontally scrollable rather than squeezing three products into unreadable columns.

**Unknown:**

- Exact mobile heading sizes, navigation interaction, stacking order and art direction are not established; narrow-screen transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
