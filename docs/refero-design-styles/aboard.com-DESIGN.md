# Aboard — editorial warmth, operational grit

## Overview

A light, literary style that makes complex technology feel like the work of experienced people rather than an abstract machine. Fine-lined serif headlines sit beside practical sans-serif explanations, warm paper tones, brown ink and bursts of burnt orange. Real-world photography is layered with working interfaces, while spacious compositions and ruled editorial lists suit consultative products and substantial product stories.

### Essentials

- Literary promises above working proof: Tobias 400 at 77.8px/1 with -0.02em tracking opens over a 1328px-wide photographic interface montage, not a centered app icon.
- A paper-and-earth palette with a furnace-orange ending: #fffefb and #271503 dominate the reading area; #de4c00 is concentrated in small actions and the full-width contact-and-footer field, about 1238px tall.
- Actions have a disc inside a capsule: the main brown pill is 48px high with 6px 6px 6px 24px padding and a 36px translucent circular arrow well; the orange navigation action is 42px high.
- Proof lives in the world: stage a real interface rising from the lower edge of a photographic setting inside 12px corners, with small floating status annotations. When photography is unavailable, use a product-relevant still life and a credible interface rather than abstract blobs.
- Operational detail is typeset like an editorial index: 12.8px uppercase sans labels with 0.15em tracking, numbered square-corner capability cells and 1px brown rules at 10% opacity.
- Include a soft-focus atmospheric statement and a monumental cropped wordmark device: a 900px-tall warm photographic field carries a dark serif statement; the closing orange field ends with an 877px-wide low-contrast wordmark cut by the lower edge. Use the new product’s own lettering and a softly blurred workspace or material study.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brown ink | `#271503` | `--color-ink` | text, action, surface | Default serif headings, navigation and dark buttons; also the dark backing for detailed interface panels. |
| Burnt orange | `#de4c00` | `--color-accent` | accent, action, background, link | Contact action, short emphasis, small arrows and the expansive closing contact field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Taupe markings | `#766757` | `--color-muted` | text | Eyebrows, dates, indices and captions. |
| Photographic espresso | `#1a110a` | `--color-espresso` | surface | Backing behind full-bleed photographic proof scenes. |
| Warm body ink | `#54493f` | `--color-body` | text | Default explanatory paragraphs. |
| Paper hairline | `#e9e7e2` | `--color-rule` | border | Visible separator made with rgba(39,21,3,0.1) over warm paper. |
| Warm atmospheric ground | `#efe8de` | `--color-atmosphere` | background | Ground beneath soft-focus photographic statement fields. |
| Warm paper | `#fffefb` | `--color-canvas` | background, text | Default page canvas and reversed text on orange or dark media. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and methodology narratives | Near-black ink | `#06070a` | `--color-cool-ink` | text | Company and methodology headline variant; brown remains the landing-page default. |
| methodology and detailed product stories | Soft gray paper | `#f5f4f1` | `--color-panel` | surface, background | Methodology band, service cards and light interface demonstration panels. |
| long-form customer stories | Peach cream | `#fbf3ec` | `--color-cream` | background | Related-story recommendation band. |
| company and methodology narratives | White | `#ffffff` | `--color-white` | background, surface | White editorial sections and process sheets. |

## Typography

- **Tobias** — Promises, chapter headings, editorial titles, statements and statistics. Fine-stroked contemporary editorial serif with delicate contrast, expressive curves and a true italic. If unavailable, use **Libre Caslon Display**. Use regular for the fine display texture; tune wrapping before increasing weight. Font stack: "Tobias", "Libre Caslon Display", Georgia, serif.
- **Work Sans** — Body copy, navigation, buttons, labels and technical explanations. Open, practical grotesk with generous counters and a matter-of-fact tone. Font stack: "Work Sans", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Tobias | 400 | 77.8px | 1 | -0.02em | fixed | Default landing-page promise, usually two lines and left aligned. |
| heading-lg | Tobias | 400 | 74.9px | 1.02 | -0.02em | size clamp(41.6px, 5.2vw, 76px) | Primary section leads; narrow columns allow three-line wrapping. |
| heading | Tobias | 400 | 60.5px | 1.02 | -0.02em | size clamp(38.4px, 4.2vw, 64px) | Split image-and-explanation sections. |
| media-title | Tobias | 300 | 47.5px | 1.06 | -0.015em | size clamp(32px, 3.3vw, 52.8px) | Reversed editorial title over the photographic proof stage. |
| card-heading | Tobias | 300 | 33.1px | 1.05 | -0.02em | size clamp(25.6px, 2.3vw, 33.6px) | Numbered capability cells. |
| closing-heading | Tobias | 300 | 32px | 1.1 | -0.01em | fixed | Small, welcoming heading above the closing contact form. |
| row-title | Tobias | 400 | 28.8px | 1.12 | -0.02em | size clamp(23.2px, 2vw, 29.6px) | Editorial feed titles with an inline northeast arrow. |
| lead | Work Sans | 400 | 17.6px | 1.6 | normal | fixed | Opening explanation beneath the proof stage. |
| body | Work Sans | 400 | 15.7px | 1.55 | normal | fixed | Default compact explanatory paragraphs in capability cells. |
| button | Work Sans | 500 | 15.2px | 1.6 | normal | fixed | Primary brown disc-button labels. |
| navigation | Work Sans | 400 | 15px | 1.6 | normal | fixed | Desktop navigation and secondary editorial summaries. |
| footer-link | Work Sans | 400 | 15px | 1.6 | normal | fixed | Footer column links. |
| nav-action | Work Sans | 400 | 14.7px | 1.6 | normal | fixed | Orange contact capsule in navigation. |
| filter | Work Sans | 500 | 14.1px | 1.6 | normal | fixed | Editorial filter pills. |
| eyebrow | Work Sans | 600 | 12.8px | 1.6 | 0.15em, uppercase | fixed | Small section labels and partner-strip introductions. |
| metadata | Work Sans | 600 | 11.5px | 1.6 | 0.14em, uppercase | fixed | Content category above an editorial row title; dates and cell indices use weight 400. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| portfolio and editorial indexes | index-display | Tobias | 400 | 123.8px | 0.94 | -0.035em | size clamp(54.4px, 8.6vw, 134.4px) | Oversized low-set title for a collection index. |
| methodology narratives | process-display | Tobias | 400 | 95px | 0.98 | -0.02em | fixed | Methodology opening statement, with a struck-through phrase followed by orange italic correction of the same size. |
| quantified customer stories | stat-number | Tobias | 400 | 92.2px | 0.92 | -0.035em | fixed | Four-column quantified proof; longer numbers reduce to 84.4px and suffixes are much smaller. |
| company narratives | company-display | Tobias | 400 | 72px | 1.02 | -0.025em | fixed | Broad three-line company introduction above a wide office photograph. |
| company narratives | quote | Tobias | 300 | 63.4px | 1.04 | -0.022em | fixed | Large founder quotation with separate orange quotation mark and ruled attribution. |
| long-form customer stories | story-display | Tobias | 400 | 59px | 1.02 | -0.025em | fixed | Customer-story title beside a compact identity rail. |
| methodology narratives | phase-heading | Tobias | 400 | 51.2px | 1 | -0.02em | size clamp(35.2px, 3.6vw, 51.2px) | Individual chapter names in the scroll-linked process story. |
| long-form customer stories | result-heading | Tobias | 400 | 37.4px | 1.04 | -0.02em | size clamp(25.6px, 2.6vw, 38.4px) | Ruled outcome rows. |
| long-form customer stories | detail-label | Work Sans | 600 | 16.8px | 1.4 | -0.01em | fixed | Compact left-hand label inside technical explanation rows. |
| methodology and customer stories | chapter-kicker | Work Sans | 600 | 15.2px | 1.5 | -0.005em | fixed | Sentence-case orange chapter label with short leading rule, or phase number separated by a middle dot. |
| detailed product stories | caption | Work Sans | 500 | 14.1px | 1.5 | normal | fixed | Stat explanations and interface-panel captions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep serif headings fine rather than bold; weight 300 distinguishes the light capability and photographic title treatments from weight 400 promises.
- Most headline tracking is -0.02em. The very large index title tightens to -0.035em, while small sans labels expand to 0.14–0.15em.
- Use sentence case in headlines and paragraphs. Reserve widely tracked capitals for navigational markings and metadata, not the main promise.
- Body text remains sans serif even when titles, statistics and quotations are serif. A heading can wrap deeply in a narrow left rail while the adjacent grid stays dense.

## Layout

**Density:** Airy at section scale, compact within explanatory blocks: wide pauses separate substantial text and media rather than padding every small item equally.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Metadata stacks and footer link-list gaps. | fixed |
| 12px | Phase text stacks and small internal groups. | fixed |
| 14px | Capability-cell stack and primary action icon gap. | fixed |
| 24px | Lead-to-action gap and vertical feed-row padding. | fixed |
| 31.7px | Default twelve-column desktop gutter. | fixed |
| 37.4px | Capability-cell padding. | clamp(24px, 2.6vw, 40px) |
| 43.2px | Editorial-row column gap. | clamp(24px, 3vw, 44px) |
| 56px | Desktop side inset and headline-to-proof-stage gap. | clamp(28px, 4vw, 56px) |
| 120px | Closing form vertical padding. | fixed |
| 144px | Substantial proof-band vertical padding. | fixed |
| 170px | Large capability and story chapter top padding. | fixed |

### Containers and grids

- **Desktop frame**: max width 1440px · side padding 56px. Default centered marketing wrapper; 1328px of content at desktop.
- **Editorial grid**: 12 columns · gap 31.7px. Heading rails occupy four columns, substantial prose begins at column four or six, and media may span the entire frame.
- **Capability matrix**: 2 columns · gap 0px. A 761px-wide matrix on the right, beside a narrow heading rail; cells share edges.
- **Contact frame**: max width 1120px · side padding 90px. Centered closing form and footer content, intentionally narrower than the main content frame.
- **Collection grid** (only for portfolio indexes): 2 columns · gap 64px. 632px-wide proof cards following one full-width featured project.
- **Secondary editorial frame** (only for company and methodology narratives): max width 1440px · side padding 48px. Slightly broader company and methodology content area.
- **Related stories** (only for long-form customer stories): 3 columns · gap 31.7px. Three approximately 422px-wide photographic cards under a heading and right-aligned action.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Capsules | 9999px (pill) |
|  | Media frames | 12px |
|  | Arrow wells | 50% |
| methodology narratives | Process sheets | 14px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| methodology narratives | Paper stack | `rgba(6, 7, 10, 0.06) 0px 1px 2px 0px, rgba(6, 7, 10, 0.35) 0px 24px 50px -24px` | Soft substantial grounding beneath stacked process sheets. |

### Surfaces

#### Warm paper · level 0

**Use:** Default marketing background.

**CSS:** `background: #fffefb; color: #271503`

**Observed:** Reading areas are flat and nearly white; separation comes from hairlines and space.

**Transfer:** Keep the majority of the page on this background.

#### Photographic stage · level 1

**Use:** Large photographic proof composites.

**CSS:** `background: #1a110a; border-radius: 12px; overflow: hidden`

**Observed:** A wide scenic image fills the frame. A local lower-left shade protects the reversed caption while the right-hand interface remains bright.

**Transfer:** Use the dark backing only where media fills it.

#### Caption shade

**Use:** Readability layer over photographic proof.

**CSS:** `background-image: radial-gradient(125% 100% at 0px 100%, rgba(20, 12, 6, 0.7) 0px, rgba(20, 12, 6, 0.46) 30%, rgba(20, 12, 6, 0.14) 56%, rgba(20, 12, 6, 0) 74%)`

**Observed:** The shade is deepest behind the lower-left title and clears across the photograph.

**Transfer:** Keep the image visible; do not darken all four corners equally.

#### Contact orange · level 0

**Use:** Shared closing contact and footer field.

**CSS:** `background: #de4c00; color: #fffefb`

**Observed:** The color extends continuously through the form, separator and footer, creating a much stronger ending than a dark utility footer.

**Transfer:** Give this field enough height to feel like a destination.

#### Floating navigation glass · level 2

**Use:** Compact navigation after scrolling.

**CSS:** `background: rgba(240, 241, 239, 0.84); backdrop-filter: blur(10px) saturate(140%); border-radius: 9999px`

**Observed:** A pale capsule floats over content; the first-screen navigation is spread widely across the top.

**Transfer:** Keep the glass local to navigation rather than turning cards into glass.

#### Soft panel · level 1

**Only for:** methodology and detailed product stories

**Use:** Process band, service cards and interface backings.

**CSS:** `background: #f5f4f1; border-radius: 12px`

**Observed:** A neutral warm gray, without decorative gradients.

**Transfer:** Use for explanatory panels, not every ordinary paragraph.

#### Paper sheet · level 2

**Only for:** methodology narratives

**Use:** Scroll-linked stack of deliverable illustrations.

**CSS:** `background: #ffffff; border-radius: 14px; padding: 22px; box-shadow: rgba(6, 7, 10, 0.06) 0px 1px 2px 0px, rgba(6, 7, 10, 0.35) 0px 24px 50px -24px`

**Observed:** White portrait sheets overlap, slightly rotated, above the gray band.

**Transfer:** Use actual deliverable structures as the graphic rather than decorative blank sheets.

#### Related-story cream · level 0

**Only for:** long-form customer stories

**Use:** Recommendation band after the inline conversion call.

**CSS:** `background: #fbf3ec`

**Observed:** A peach-tinted paper field separates related work from the main narrative.

**Transfer:** Keep this tint confined to the recommendation chapter.

## Components

### Primary button

**Use:** Main in-content conversion or exploration action.

**CSS:** `display: inline-flex; align-items: center; gap: 14px; background: #271503; color: #fffefb; border-radius: 9999px; padding: 6px 6px 6px 24px; height: 48px`

**Text style:** `button` — Work Sans 500 · 15.2px/1.6

**Observed:** Text precedes a northeast arrow in a 36px circular well filled with rgba(255,255,255,0.14). Width follows the label.

**States:** Declared: hover background #de4c00, transparent border and #fffefb text; focus-visible 2px #de4c00 outline with 4px offset and 2px radius; active scale(0.98).

### Navigation action

**Use:** Persistent contact action at the right end of navigation.

**CSS:** `display: inline-flex; align-items: center; gap: 12px; background: #de4c00; color: #fffefb; border-radius: 9999px; padding: 5px 5px 5px 18px; height: 42px`

**Text style:** `nav-action` — Work Sans 400 · 14.7px/1.6

**Observed:** A 32px translucent circular well encloses a small northeast arrow; it remains the strongest color in the header.

**States:** Declared: hover background #271503; focus-visible 2px #271503 outline with 4px offset and 2px radius.

### Navigation link

**Use:** Top-level desktop destinations.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; padding: 9px 14px; border-radius: 9999px; color: #271503`

**Text style:** `navigation` — Work Sans 400 · 15px/1.6

**Observed:** Wordmark sits left, links right; dropdown categories add tiny chevrons. Current destinations use the same pale gray pill as hover.

**States:** Declared: hover background rgba(128,128,128,0.16); focus-visible 2px #de4c00 outline with 4px offset and 2px radius.

### Filter chip

**Use:** Category controls above an editorial list.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; height: 40px; padding: 0px 16px 0px 14px; border: 1px solid rgba(39,21,3,0.1); border-radius: 9999px; color: #271503`

**Text style:** `filter` — Work Sans 500 · 14.1px/1.6

**Observed:** Small outline icon precedes the label. Chips wrap with 10px gaps. The selected chip reverses to warm paper on brown with a brown border.

**States:** Declared: hover border-color #271503; focus-visible 2px #de4c00 outline with 4px offset and 2px radius.

### Capability cell

**Use:** Numbered, substantive capability explanations.

**CSS:** `display: flex; flex-direction: column; gap: 14px; padding: 37.4px; border-right: 1px solid rgba(39,21,3,0.1); border-bottom: 1px solid rgba(39,21,3,0.1)`

**Text style:** `card-heading` — Tobias 300 · 33.1px/1.05 · tracking -0.02em

**Observed:** Small taupe two-digit index at top, a generous pause before the serif title, then sans explanation. Parent matrix supplies the top and left rules; cells are square and flush.

**Transfer:** Use fewer or more rows as needed, preserving the shared-edge table construction.

### Editorial row

**Use:** A whole-row link to an article, interview or resource.

**CSS:** `display: grid; grid-template-columns: 259.2px minmax(0px, 1.15fr) minmax(0px, 1fr); align-items: center; gap: 43.2px; padding: 24px 0px`

**Text style:** `row-title` — Tobias 400 · 28.8px/1.12 · tracking -0.02em

**Observed:** A 4:3 image in 12px corners sits left; category, serif title, orange inline arrow and date sit centrally; a concise sans summary sits right. The list owns thin horizontal separators.

**States:** Declared: hover translateX(8px); focus-visible 2px #de4c00 outline with 4px offset and 2px radius.

### Proof carousel

**Use:** Dominant first-screen photographic proof.

**CSS:** `position: relative; aspect-ratio: 21 / 9; background: #1a110a; border-radius: 12px; overflow: hidden; margin-top: 56px`

**Text style:** `media-title` — Tobias 300 · 47.5px/1.06 · tracking -0.015em

**Observed:** Photographic stage and Caption shade sit behind a lower-left client/category line and light serif outcome title. The interface rises at the lower right. Small line indicators and a pause control sit below the caption; slim previous/next chevrons sit beyond the image edges.

**Transfer:** Keep one persuasive proof composition as the dominant object even when only one story is available.

### Footer columns

**Use:** Utility navigation within the continuous orange ending.

**CSS:** `border-top: 1px solid rgba(255,254,251,0.3); padding: 64px 90px 256px; position: relative; overflow: hidden; color: #fffefb`

**Text style:** `footer-link` — Work Sans 400 · 15px/1.6

**Observed:** A small white wordmark and copyright occupy the left. Four narrow link columns align at right, each with a short heading and fine divider. An oversized low-contrast wordmark is centered at the bottom and cut by the page edge.

**States:** Declared: hover link color rgb(243 217 200/1); focus-visible 2px #de4c00 outline with 4px offset and 2px radius.

### Interface panel

**Only for:** detailed product stories

**Use:** Paired close views of important product workflows.

**CSS:** `display: flex; flex-direction: column; justify-content: center; gap: 22px; padding: 51.8px; background: #f5f4f1; border-radius: 12px`

**Text style:** `caption` — Work Sans 500 · 14.1px/1.5

**Observed:** Caption comes above a sharp rectangular interface image. The adjacent variant uses #271503 and a white caption at 62% opacity. Two panels share a 16px gap within broader media insets.

### Process sheet

**Only for:** methodology narratives

**Use:** Tangible evidence alongside process chapters.

**CSS:** `background: #ffffff; border-radius: 14px; padding: 22px; box-shadow: rgba(6, 7, 10, 0.06) 0px 1px 2px 0px, rgba(6, 7, 10, 0.35) 0px 24px 50px -24px`

**Observed:** A portrait sheet around 396px by 488px combines orange serif numbering, bold sans deliverable name, thin rules and simple diagrams. Several sheets fan behind the current one; progress caption sits below.

## Imagery and graphics

### Photographic interface montage

**Use:** Signature proof stage and customer-story cards.

**Observed:** Real settings establish context: aerial houses, coastlines, city streets, libraries or scientific imagery. A bright working interface rises from the lower edge, sometimes partly cut off. White floating annotations connect functions to objects in the scene. The photo occupies much more area than the copy and preserves recognizable natural color.

**Transfer:** Choose a setting relevant to the user’s real work, then layer a believable interface with one or two meaningful status annotations. Minimum acceptable treatment is one sharp environmental photograph and one carefully typeset interface panel.

**Build:** Fill a 21:9 frame with an object-cover photo. Add the Caption shade above the photograph. Position a rounded interface panel across roughly the lower-right half, extending below the frame. Place 2–3 compact white status labels above with small colored dots and short connector marks. Keep all layers clipped to the 12px outer frame.

### Soft-focus statement field

**Use:** Signature atmospheric pause between editorial detail and conversion.

**Observed:** A full-width warm, defocused workspace-like image becomes an almost abstract field of beige, gray and pale window light. Dark large serif text sits in the upper left, with two wide underlined directional links near the bottom. It reads as an environmental photograph, not a luminous mesh gradient.

**Transfer:** Use a softly focused workspace, product material or relevant environment. Keep the text sharp and the background low contrast.

**Build:** Use a cover photograph on #efe8de in a 900px-tall overflow-hidden band. Blur a slightly oversized image layer by about 35px and soften it with a warm-paper translucent wash. Leave broad unoccupied space around a serif statement; add bottom-aligned two-column text links with thin brown rules. Match the muted softness rather than particular image details.

### Closing wordmark sculpture

**Use:** Signature bottom-edge brand device on the orange contact field.

**Observed:** Very large dark-orange lowercase lettering sits centered at the base; only its upper mass is visible, making the footer feel physically stamped rather than ending with a small logo alone.

**Transfer:** Use the new product’s own wordmark or a custom typographic rendering of its name.

**Build:** Set an SVG wordmark to 877px wide, constrained to 92% of the container. Anchor it bottom center inside an overflow-hidden footer with 256px of bottom breathing room. Render it in brown at low opacity over #de4c00 so the silhouette is legible but subordinate to white footer links.

### Printed expertise still life

**Use:** Image-and-text argument sections.

**Observed:** A warm wood tabletop holds open printed pages and dark booklets, photographed obliquely with tangible paper grain and subdued light. The image is nearly square, around 648px by 605px, with rounded corners.

**Transfer:** Photograph a relevant manual, physical artifact, sketchbook or material sample; keep real texture, gentle shadows and an editorial rather than glossy advertising finish.

### People at work

**Only for:** company and methodology narratives

**Use:** Wide opening image, conversation scene, paired event photographs and compact biographies.

**Observed:** Daylit offices, glass partitions, city windows and candid conversations. Natural color is slightly softened; portraits are straightforward and framed from the torso up. Paired event images are 4:3; biography portraits are tall.

**Transfer:** Show actual people in their working context and pair candid wide photographs with restrained individual portraits. Avoid corporate handshake staging.

### Stacked deliverables

**Only for:** methodology narratives

**Use:** Scroll-linked illustration adjacent to phase explanations.

**Observed:** A small fan of white paper cards with fine gray rules, orange numbers, wireframe outlines, checklists, small bars and plotted dots. The active sheet stays bright while lower sheets rotate and darken slightly.

**Transfer:** Represent real outputs from the new product’s process, keeping them legible as structured documents rather than reproducing full app screens.

**Build:** Create portrait Paper sheet panels around 396px by 488px. Offset successive sheets by roughly 10–20px and rotate within about 4deg. Add an orange serif index, bold sans title and a 1px separator. Draw task-specific diagrams with SVG lines, a small grid or dashed orange wireframe rectangles. Apply the Paper stack shadow; show a centered phase counter below.

### Icons

**Observed:** Small northeast arrows dominate actions and inline title endings: 13–14px outlined SVGs, 1.4–1.5px strokes with butt caps. Navigation and main buttons place them in translucent 32px or 36px circular wells. Filter icons are compact 15px outlines; editorial category icons use orange.

**Transfer:** Keep arrow direction and light stroke consistent. Use small outline symbols for categories rather than large illustrated feature icons.

## Section recipes

How recurring sections are built.

### First screen: Promise over working proof

**Observed:** The first screen is warm paper with fixed navigation at the top: small wordmark left, compact links and orange Navigation action right. A two-line dark serif promise begins after 156px of top space, aligned to the 56px frame inset; its text occupies less than half the total width even though the heading area can grow wider. The display is 77.8px/1 with -0.02em tracking. After a 56px pause, the Proof carousel spans 1328px at 21:9, starting around the upper-middle of the screen. Layers run photograph, contextual interface and annotations, Caption shade, then lower-left client metadata and a 47.5px light serif outcome. Slim controls sit around the frame. Within the first 900px the headline, navigation action, most of the main scene and its caption are visible; the image’s lower edge, supporting paragraph and brown Primary button fall below the fold.

**Transfer:** Write a short two-line promise and supply one credible environmental interface composition. If the product lacks elaborate media, create a real-world still life with a single representative interface and concise outcome caption. Index pages can instead open with a low-set oversized title and small right-hand explanation; customer stories use an identity rail beside a smaller headline; company and methodology pages use broad statements over photography.

**Avoid:** Do not compress the headline, support paragraph, two buttons and three small feature cards into one centered hero. Do not replace the dominant proof scene with an isolated floating logo.

**Text style:** `display` — Tobias 400 · 77.8px/1 · tracking -0.02em

### Heading rail and capability matrix

**Observed:** An eyebrow and heading-lg occupy the left four columns; Capability cells fill the right seven columns in a flush two-column matrix. The section has about 170px top and 150px bottom padding. Two-digit indices sit far above light serif card titles.

**Transfer:** Group a small set of capabilities into a table-like matrix while giving the left rail one memorable promise.

**Text style:** `heading-lg` — Tobias 400 · 74.9px/1.02 · tracking -0.02em

### Artifact beside an argument

**Observed:** A nearly square warm photographic artifact fills the left half. An eyebrow, heading, substantial sans paragraph and Primary button form a narrower right column with a deliberate gap between image and text.

**Transfer:** Use a tangible artifact to substantiate a conceptual claim, not merely decorate it.

**Text style:** `heading` — Tobias 400 · 60.5px/1.02 · tracking -0.02em

### Editorial feed

**Observed:** A broad heading pair introduces the content area, with a large left title and right-side support. Filter chips precede ruled Editorial rows; a Primary button follows the list.

**Transfer:** Use this for useful resources, releases or customer learning rather than a generic grid of raised cards.

### Atmospheric statement

**Observed:** Soft-focus statement field fills a 900px band. A multi-line serif statement occupies the upper-left area, while a pair of long text links anchor the lower edge.

**Transfer:** Use an enduring product belief or credibility statement to create a visual pause before conversion.

### Orange contact and stamped ending

**Observed:** Contact orange begins with a small closing-heading and a form in the 1120px Contact frame, with 120px vertical padding. Full-width name field, phone/email row and a large message field appear as darker orange inset rectangles with light labels; a small pale submit pill follows. A thin reversed separator leads to Footer columns, then the Closing wordmark sculpture. The complete field is about 1238px tall.

**Transfer:** Ask for a small set of useful details in an actual closing form, then carry the same orange continuously through utility navigation. Keep the oversized bottom lettering as the final visual gesture.

**Text style:** `closing-heading` — Tobias 300 · 32px/1.1 · tracking -0.01em

### Collection opening and proof gallery

**Only for:** portfolio indexes

**Observed:** A 123.8px serif headline sits low in a 900px paper first screen, paired with a narrow sans explanation on the right. A full-width featured project leads into a two-column Collection grid. Each project uses a top rule, compact identity/category, right-aligned serif outcome title and a 12px rounded photographic montage.

**Transfer:** Let one piece of proof receive full width before the balanced collection; preserve generous whitespace around the index title.

**Text style:** `index-display` — Tobias 400 · 123.8px/0.94 · tracking -0.035em

### Customer story chapters

**Only for:** long-form customer stories

**Observed:** An identity rail sits beside the story-display title and lead, followed by a broad scenic montage. Four oversized stats introduce evidence. Subsequent chapters pair orange left-rail kickers with a 761px right reading column; technical details use ruled label/prose rows. Interface panels periodically span almost the full width. Outcomes use stronger brown rules and result-heading. A rounded orange inline call precedes a cream recommendation band and the shared orange ending.

**Transfer:** Alternate context, implementation detail, product demonstration and outcomes; keep the hierarchy of rail, reading column and media width.

**Text style:** `story-display` — Tobias 400 · 59px/1.02 · tracking -0.025em

### Methodology as a document stack

**Only for:** methodology narratives

**Observed:** The opening uses process-display: a muted struck-through assumption followed by an orange italic correction above a booklet photograph. White argument and partnership sections lead into a gray-paper band with chapter copy left and a sticky Paper sheet stack right. Phases use orange chapter-kicker, phase-heading, a serif explanatory sentence and sans body. Current text is dark; inactive phases fade. Three soft service panels and photographic proof conclude before the orange ending.

**Transfer:** Choose a real sequence of decisions and deliverables. Make the physical documents explain progress, without requiring the same number of steps.

**Text style:** `phase-heading` — Tobias 400 · 51.2px/1 · tracking -0.02em

### People and editorial conviction

**Only for:** company narratives

**Observed:** A company-display statement sits over a broad office photograph. A white quotation chapter pairs an orange diagram tile with a 63.4px serif quote, an oversized orange quotation mark and attribution marked by a 2px orange left rule. Paired event photographs, team explanation, a subdued partner strip and two image-plus-biography units lead to the shared ending.

**Transfer:** Use a genuine expert perspective and actual working context; the diagram can express the product’s own craft.

**Text style:** `quote` — Tobias 300 · 63.4px/1.04 · tracking -0.022em

## Page flow

**Storyline:** promise → working proof → explanation of value → human or operational credibility → useful detail → direct invitation → expansive branded ending

### General marketing landing page

1. **Promise and proof** — Two-line literary headline above a broad photographic interface montage; support and primary action follow.
2. **Credibility** — Subdued partner strip.
3. **Capabilities** — Narrow heading rail beside a numbered shared-edge matrix.
4. **Reason to believe** — Tangible artifact paired with an argument and action.
5. **Ongoing expertise** — Filtered, ruled editorial list.
6. **Conviction** — Full-width soft-focus statement field.
7. **Conversion and navigation** — Orange contact form, footer columns and bottom-cut wordmark.

**Transfer:** Use proof to earn the claim, then deepen understanding before inviting contact; adapt the content depth without losing the signature media and ending.

### Detailed customer or implementation story

1. **Context** — Identity rail, measured headline, support and panoramic montage.
2. **Quantified proof** — Four large serif statistics.
3. **Challenge and solution** — Rail-led chapters alternate with paired light/dark interface panels and technical explanation rows.
4. **Outcomes** — Strongly ruled result rows and concise takeaways.
5. **Next step** — Inline orange conversion panel followed by cream related stories.
6. **Conversion and navigation** — Shared orange contact field and stamped footer.

**Transfer:** Present genuine constraints and outcomes rather than turning the story into an unbroken sales pitch.

### Proof collection index

1. **Framing promise** — Low-set monumental serif title with a narrow supporting paragraph.
2. **Featured proof** — One full-width montage and outcome title.
3. **Breadth** — Two-column grid of ruled project cards with photographic interfaces.
4. **Conversion and navigation** — Shared orange contact form and stamped footer.

**Transfer:** Use a visual portfolio as the body of the argument instead of surrounding it with additional feature sections.

### Company credibility narrative

1. **Identity** — Broad serif statement over candid office photography.
2. **Conviction** — Large quotation with orange typographic and diagram accents.
3. **Human proof** — Paired event imagery and split team explanation.
4. **Credibility** — Subdued partner strip followed by portrait biographies.
5. **Conversion and navigation** — Shared orange contact form and stamped footer.

**Transfer:** Make the team’s point of view and working environment visible; avoid a generic headshot directory.

### Methodology and risk-reduction narrative

1. **Reframe** — Large struck-through assumption and orange italic correction above a printed artifact.
2. **Objection handling** — White editorial argument with two ruled explanations.
3. **Working relationship** — Conversation photograph and four compact benefit columns.
4. **Process demonstration** — Gray band with scroll-linked phase copy and a fan of deliverable sheets.
5. **Capabilities and proof** — Three soft service cards followed by photographic results.
6. **Conversion and navigation** — Shared orange contact form and stamped footer.

**Transfer:** Turn abstract process into visible outputs and practical reassurance, then show its consequences.

## Writing

Experienced, candid and companionable. The speaker is confident enough to explain trade-offs, admit complexity and puncture technology hype without sounding cynical.

**Do not copy:** Do not reuse Aboard’s name, logos, customer identities, founder biographies, quotations, proprietary process or tool names, statistics, claims, dates or project outcomes. Source examples illustrate cadence only; supply independently true content for the new product.

- **Addressing the reader:** Use we for the people doing the work and you/your for the reader’s problems and desired outcomes. Prefer a working partnership to an impersonal platform voice.
- **Rhythm:** Short, declarative serif headlines contrast with substantial explanatory paragraphs. Use conversational contractions, an occasional pointed question and short punch-line sentences after a longer explanation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct promise framed around the reader’s next consequential move. | 5–10 words | “Your partner for the big AI leap” |
| Section argument | A plainspoken contrast that acknowledges what got easier and what remains hard. | 8–14 words | “Code got easy. Building great software didn’t.” |
| Supporting explanation | Specific activities first, experienced people second, meaningful customer result last. | 20–45 words | “Building solutions, advising AI transformation, clearing roadmaps. We’re software veterans who solve problems for some of the world’s best companies.” |
| Primary action | Warm collaborative invitation or direct exploration verb. | 3–6 words | “Let’s make something great”<br>“Explore all perspectives” |
| Process subhead | A short everyday phrase makes a technical stage feel concrete. | 3–9 words | “Let’s find out what’s broken.”<br>“It’s moving day.” |
| Takeaway | A concise, opinionated principle earned by the preceding details. | 4–7 words | “Speed is not a solution”<br>“Design debt compounds” |

**Words and phrasing to use:** build; plan; work; careful; real; partner; your roadmap; what’s broken; ship; what to build

**Avoid:** revolutionary; seamless end-to-end ecosystem; unleash limitless potential; magic; 10x everything; token-heavy jargon without explanation

**Rules:**

- Explain the hard decision behind the product, not only its speed.
- Ground claims in specific workflows, constraints and evidence.
- Use technology terms when they clarify actual work; challenge hype with a useful alternative.
- Keep action labels human and direct rather than aggressive urgency.
- Let a short conversational sentence release tension after detailed prose.

## Do's and Don'ts

### Do

- Keep default headline weight at 400 and tracking near -0.02em; reserve 300 for fine editorial treatments.
- Use 56px desktop insets within the 1440px main frame.
- Keep proof media broad, clipped to 12px corners and grounded in real settings.
- Construct capability groups with shared 1px rules and zero grid gap.
- Keep body copy warm brown and small labels taupe rather than cooling everything to slate gray.
- Include the circular arrow well inside the 48px primary capsule.
- Give the closing orange contact field room for a form and utility columns, not just one button.
- Preserve the low-contrast oversized wordmark at the bottom edge.

### Don't

- Do not substitute a bold geometric sans headline for the fine serif display.
- Do not turn the entire page orange; ordinary reading sections remain warm paper.
- Do not put shadows and rounded corners on the square capability matrix.
- Do not shrink photographic proof into a row of tiny equal-weight thumbnails.
- Do not use giant filled feature icons; the normal arrow stroke is only 1.4–1.5px.
- Do not replace 0.14–0.15em label tracking with tightly packed uppercase headings.
- Do not convert the orange ending into a generic near-black footer.
- Do not apply the process-sheet shadow to editorial feed rows.

## Motion and responsive

### Motion

**Observed:**

- Primary buttons declare background and transform transitions of 0.4s cubic-bezier(0.32,0.72,0,1), with active scale(0.98).
- The hero film declares a 1.6s cubic-bezier(0.16,1,0.3,1) reveal after 0.45s; supporting rises use 1.1s with the same easing.
- The navigation contracts into a floating capsule; max-width and transform declare 0.7s cubic-bezier(0.65,0,0.35,1).
- Editorial rows declare hover translateX(8px) with a 0.6s cubic-bezier(0.32,0.72,0,1) transition.
- Partner strips declare a 48s linear infinite train animation. Process sheets declare opacity 0.5s and transform 0.9s transitions with separate easing.

**Transfer:**

- Use motion to reveal editorial words and physical media rather than animating every paragraph.
- Keep the carousel pause and manual selection controls when rotating proof.
- On methodology narratives, let the current sheet and current phase change together.

**Unknown:**

- Exact carousel autoplay timing and all runtime scroll thresholds are unspecified.
- Reduced-motion behavior is not established.

### Responsive

**Observed:**

- At 900px and below the hero proof frame changes from 21:9 to 2:3 and its radius reduces from 12px to 10px.
- Company and methodology grids declare full-width column spans and the process grid becomes a vertical flex layout below 900px.
- Editorial rows rearrange the summary under the title below 1100px; below 600px their image becomes square and summary spans the row.
- Footer declares 20px side padding, 150px bottom padding and 48px top padding below 900px.

**Transfer:**

- Preserve the photograph-plus-interface composition in the taller mobile proof frame, repositioning the interface and caption so both remain readable.
- Stack the heading rail above the capability matrix; retain shared rules instead of inventing raised mobile cards.
- Reflow footer columns and scale the bottom wordmark to the available width.

**Unknown:**

- Mobile renderings, exact menu interaction and the full breakpoint-specific type scale are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
