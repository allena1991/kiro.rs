# Next.js — outlined engineering confidence

## Overview

A light, almost monochrome technical style with fine outlines, tightly packed grotesk headlines and unusually spacious section pacing. Electric blue punctuates the neutral canvas through small actions and a concentrated announcement panel. Diagrammatic interface illustrations, grayscale website compositions and tactile resource objects make complex software feel tangible without turning the page into a dense dashboard.

### Essentials

- A monumental outline introduces an otherwise practical page: a roughly 793px-wide, 191px-high blue outline word sculpture fades into the #fafafa canvas above a centered 64px/1 headline, weight 450 and -0.06em tracking. Use a custom outlined product name or geometric letterform when no existing artwork exists.
- Big promises are lightly weighted but tightly fitted: main section headings use 56px/1 at weight 450 with -0.06em tracking; ordinary descriptions drop directly to 18px/28px or 16px/24px rather than a ladder of bold subheads.
- The opening behaves like an installation, not a sales banner: a 64px navigation bar sits over an airy centered stage, a 648px-wide two-line title and support block, and a single 40px-high command capsule as its action.
- Color is a deliberate interruption in a neutral technical field: #0057ff belongs on action pills, fine illustration highlights and a single emphatic 448px-wide announcement card, not on continuous colored bands. Keep the overwhelming majority of the page off-white, white and gray.
- Controls are rounded while information is nearly square: 40px-high action pills contrast with 2px-radius, 1px-outlined cards and 6px-radius utility controls; the distinction stays visible throughout the page.
- Proof is staged as designed artifacts: fine-line diagrams sit in 5:4 frames, customer interfaces form a grayscale collage with 8px corners, and reusable resources take the shape of folded-corner documents. Include diagrammatic and artifact-like proof even when it must be recreated from simple SVG and representative interfaces.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0057ff` | `--color-blue` | action, background, accent | Primary actions, outline artwork and announcement panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#171717` | `--color-ink` | text | Headings, card titles and active navigation. |
| Secondary ink | `#4d4d4d` | `--color-secondary` | text, link | Descriptions, navigation and supporting labels. |
| Muted index | `#8f8f8f` | `--color-muted` | text | Command prompts and secondary indexing. |
| Media edge | `#c9c9c9` | `--color-strong-edge` | border | Stronger edges around grayscale website compositions. |
| Card hairline | `#e6e6e6` | `--color-edge` | border | Fine card outlines and diagram construction lines. |
| Control edge | `#ebebeb` | `--color-control-edge` | border, surface | Subtle utility outlines, footer theme control and directory rules. |
| Off-white canvas | `#fafafa` | `--color-canvas` | background | Continuous page ground, including navigation and footer. |
| White material | `#ffffff` | `--color-white` | surface, text | Utility controls and secondary buttons; reversed text on blue. |

## Typography

- **GeistSans** — All marketing headings, descriptions, navigation and controls. Compact modern grotesk with a high x-height and restrained, slightly softened construction. OpenType features: "calt" 0, "rlig", "ss11". If unavailable, use **Geist**. Use variable weights 400–600 and retain the tight display tracking. Font stack: "GeistSans", "Geist", Arial, sans-serif.
- **Geist Mono** — Executable command text and its prompt. Small neutral monospaced lettering gives the main action the character of a terminal instruction. Font stack: "Geist Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GeistSans | 450 | 64px | 1 | -0.06em | Primary page headline; balanced into short lines. |
| heading | GeistSans | 450 | 56px | 1 | -0.06em | Major narrative section headings. |
| announcement | GeistSans | 450 | 40px | 1.2 | -0.06em | Oversized title and arrow within the blue announcement. |
| quote | GeistSans | 400 | 32px | 1.25 | -0.04em | Centered customer quotations. |
| lead | GeistSans | 400 | 18px | 28px | normal | Hero support and introductions to conversion sections. |
| body | GeistSans | 400 | 16px | 1.5 | normal | Feature and resource descriptions. |
| card-title | GeistSans | 450 | 16px | 1.5 | -0.02em | Standard outlined card heading. |
| resource-title | GeistSans | 600 | 16px | 1.5 | -0.02em | Stronger title within folded-document resource cards. |
| feature-label | GeistSans | 550 | 16px | 1.5 | normal | Feature labels in unboxed capability lists. |
| action | GeistSans | 500 | 16px | 1.5 | normal | Default 40px-high conversion button text. |
| label | GeistSans | 400 | 14px | 20px | normal | Navigation, metadata, footer links and quote attribution detail. |
| label-strong | GeistSans | 500 | 14px | 20px | normal | Footer column titles, resource origins and person names. |
| utility-action | GeistSans | 500 | 14px | 1.65 | normal | Small utility buttons and the compact 36px-high closing actions. |
| command | Geist Mono | 400 | 14px | 20px | normal | Copyable terminal command. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| customer proof pages | stat | GeistSans | 450 | 64px | 1 | -0.02em | Large concise proof numbers above smaller descriptions. |
| people directories | directory-heading | GeistSans | 450 | 48px | 56px | -0.06em | Team group headings. |
| learning catalogs | chapter-index | GeistSans | 400 | 24px | 1.5 | normal | Two-digit index at the top of each curriculum tile. |

**Notes:**

- Headlines are not bold: weight 450 and -0.06em tracking carry both the 64px title and 56px section scale. Preserve that relationship rather than substituting weight 700.
- Body text uses normal tracking. Small card headings tighten only to -0.02em, while proof numerals are more open than equally large headlines.
- There is no recurring uppercase eyebrow system. Most sections begin immediately with the main heading.
- The large outline word sculpture is vector artwork, separate from the text hierarchy.

## Layout

**Density:** Airy across sections, compact within controls and cards; long stretches of off-white separate terse content groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact heading-to-description gaps. |
| 12px | Feature heading-to-copy and footer link gaps. |
| 16px | Button pairs and resource inner padding. |
| 24px | Main grid gutter, page side margins and standard card padding. |
| 32px | Card internal separation and alternate opening action gaps. |
| 40px | Hero support-to-command gap and footer vertical inset. |
| 72px | Large heading-to-grid separation. |
| 96px | Capability grid row spacing and compact closing section padding. |
| 120px | Quote section top padding and directory heading-to-grid gap. |
| 144px | Default major section top and bottom padding. |
| 168px | Long trailing space beneath quotations. |

### Containers and grids

- **page container**: max width 1448px · side padding 24px. Centered wide page shell; at 1440px the content spans 1392px.
- **structural grid**: 12 columns · gap 24px. Underlying alignment for headings, thirds, half-width quotes and split resource sections.
- **hero copy**: max width 648px. Centered headline and support measure.
- **capability thirds**: 3 columns · gap 24px. Three 448px-wide columns at desktop; illustrated leads followed by short unboxed feature groups.
- **resource split**: 3 columns · gap 24px. A one-third introduction sits beside two columns of document cards. The introduction stays sticky while the cards continue.
- **directory** (only for people directories): 3 columns · gap 0px. Equal people cells, 464px wide and 296px tall, with thin vertical rules.
- **catalog grid** (only for customer proof pages): 4 columns · gap 16px. Website preview cards, 336px wide at desktop.
- **curriculum grid** (only for learning catalogs): 3 columns · gap 16px. Dense indexed curriculum tiles beneath the demonstration.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | conversion buttons | 9999px (pill) |
|  | information cards | 2px |
|  | utility controls | 6px |
|  | announcement panel | 4px |
|  | customer media | 8px |
| people directories | portraits | 50% |
| learning product demonstrations | browser stage | 20.9px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| small material | `0px 0px 0px 1px rgba(0,0,0,0.08), 0px 2px 2px 0px rgba(0,0,0,0.04), 0px 0px 0px 1px #fafafa` | Command capsule; softly raised rather than floating. |
| control ring | `0px 0px 0px 1px #ebebeb` | White utility controls and secondary pills. |

### Surfaces

#### Canvas · level 0

**Use:** Full marketing ground, including closing sections and footer.

**CSS:** `background: #fafafa; color: #171717`

**Observed:** The footer does not switch to a dark theme or a contrasting band.

**Transfer:** Keep the ground visually continuous while spacing and rules separate chapters.

#### Outlined panel · level 1

**Use:** Capabilities, foundation cards and catalog tiles.

**CSS:** `border: 1px solid #e6e6e6; border-radius: 2px; box-shadow: none`

**Observed:** Usually shares the page ground; framing is more important than fill.

**Transfer:** Use a fine perimeter rather than elevation to group information.

#### White control · level 2

**Use:** Secondary pills and small utility buttons.

**CSS:** `background: #ffffff; box-shadow: 0px 0px 0px 1px #ebebeb`

**Observed:** Only a subtle ring distinguishes white controls from off-white ground.

**Transfer:** Reserve this raised material for interactive elements.

#### Blue interruption · level 1

**Use:** A concentrated announcement among neutral feature content.

**CSS:** `background: #0057ff; color: #ffffff; border: 2px solid #0057ff; border-radius: 4px`

**Observed:** A large title at top and a short support line at bottom leave the center mostly empty.

**Transfer:** Use for a release, milestone or focused product invitation rather than a general colored section.

#### Browser stage · level 1

**Only for:** learning product demonstrations

**Use:** A near-full-width product demonstration.

**CSS:** `background: #ffffff; border-radius: 20.9px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 2px 2px 0px rgba(0,0,0,0.04), 0px 0px 0px 1px #fafafa`

**Observed:** A shallow browser toolbar and rounded URL field sit above a real interface.

**Transfer:** Use a coherent small application or workflow, not unrelated decorative charts.

## Components

### Navigation

**Use:** Persistent orientation without a heavy header.

**CSS:** `position: sticky; top: 0px; height: 64px; z-index: 40; background: #fafafa; display: flex; align-items: center; justify-content: space-between`

**Text style:** `label` — GeistSans 400 · 14px/20px

**Observed:** Small identity and product menu at left, plain text links beside it; search, shortcut, compact assistant control and repository icon align to the right. Text-link padding is usually 12px per side.

**States:** Declared: hover text links darken to hsla(0, 0%, 9%, 1); focus-visible outline-color hsla(212, 100%, 48%, 1).

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #0057ff; color: #ffffff; border-radius: 9999px; height: 40px; padding: 0px 12px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — GeistSans 500 · 16px/1.5

**Observed:** Text adds another 6px inset on each side inside the control. A smaller closing variant is 36px high with utility-action text.

**States:** Declared: hover unspecified; focus-visible outline-color hsla(212, 100%, 48%, 1).

### Secondary button

**Use:** Companion action or catalog navigation.

**CSS:** `background: #ffffff; color: #171717; border-radius: 9999px; height: 40px; padding: 0px 12px; box-shadow: 0px 0px 0px 1px #ebebeb; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — GeistSans 500 · 16px/1.5

**Observed:** Sits beside the primary with a 16px gap. Uses the same internal label inset. Compact closing and load-more variants are 36px high.

**States:** Declared: hover unspecified; focus-visible outline-color hsla(212, 100%, 48%, 1).

### Command capsule

**Use:** Single low-friction start action for a technical product.

**CSS:** `height: 40px; padding: 0px 8px 0px 12px; background: #ffffff; border-radius: 9999px; display: inline-flex; align-items: center; gap: 4px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 2px 2px 0px rgba(0,0,0,0.04), 0px 0px 0px 1px #fafafa`

**Text style:** `command` — Geist Mono 400 · 14px/20px

**Observed:** Muted prompt, executable instruction and a small copy icon form one horizontal object. Copy has a 28px circular target.

**Transfer:** If the product has no terminal workflow, use a similarly compact copyable setup instruction or invitation token.

### Foundation card

**Use:** A small group of core building blocks or supporting capabilities.

**CSS:** `border: 1px solid #e6e6e6; border-radius: 2px; padding: 24px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `card-title` — GeistSans 450 · 16px/1.5 · tracking -0.02em

**Observed:** A small monochrome mark sits above a title with right arrow and a short description; space-between alignment makes the title-and-copy block settle low in the card.

**States:** Declared: hover border-color hsla(0, 0%, 79%, 1); focus-visible outline-color hsla(212, 100%, 48%, 1).

### Announcement card

**Use:** High-contrast editorial interruption within capabilities.

**CSS:** `background: #0057ff; color: #ffffff; border: 2px solid #0057ff; border-radius: 4px; padding: 16px 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `announcement` — GeistSans 450 · 40px/1.2 · tracking -0.06em

**Observed:** Occupies a column across two feature rows, with an oversized title-and-arrow at top and a body-sized release description at bottom.

**States:** Declared: hover background-color hsla(0, 0%, 98%, 1) and color #0057ff; focus-visible uses the same inversion, outline-offset 4px and outline-color hsla(212, 100%, 48%, 1).

### Folded document card

**Use:** Reusable starter, integration or resource list.

**CSS:** `position: relative; height: 180px; padding: 16px; border: 1px solid transparent; border-radius: 2px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `resource-title` — GeistSans 600 · 16px/1.5 · tracking -0.02em

**Observed:** A thin document silhouette has a clipped top-right corner and diagonal fold line. Title and short description sit above a bottom-pinned icon-and-origin label. Cards use two columns next to an introductory column.

**States:** Declared: hover border-color hsla(0, 0%, 79%, 1) and background-color hsla(0, 0%, 100%, 1); focus-visible outline-color hsla(212, 100%, 48%, 1).

**Transfer:** Build the visible perimeter with an SVG polygon inset around the card, cutting a small triangle off the upper-right corner and drawing its diagonal in #e6e6e6.

### Footer link

**Use:** Compact multi-column navigation at the page ending.

**CSS:** `color: #4d4d4d; text-decoration: none; border-radius: 4px`

**Text style:** `label` — GeistSans 400 · 14px/20px

**Observed:** Grouped below small medium-weight column labels with 16px title spacing and 12px gaps between links.

**States:** Declared: hover color hsla(0, 0%, 9%, 1); focus-visible outline-style none and outline-color hsla(212, 100%, 48%, 1).

### Newsletter input

**Use:** Small signup form integrated into the footer.

**CSS:** `height: 32px; border-radius: 6px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08); display: flex; overflow: hidden`

**Text style:** `label` — GeistSans 400 · 14px/20px

**Observed:** A 210px-wide white email field and separate compact Subscribe control share a 312px-wide column with a 12px gap. Supporting copy appears underneath rather than above the field.

### Website preview card

**Only for:** customer proof pages

**Use:** Filterable catalog of examples.

**CSS:** `padding: 16px; border: 1px solid #e6e6e6; border-radius: 2px; max-width: 384px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `card-title` — GeistSans 450 · 16px/1.5 · tracking -0.02em

**Observed:** A full-color desktop website preview rests in a white image frame, followed by the organization name and a smaller category. Category controls form a restrained text tab row above the grid, with a pale active chip; a centered secondary button loads more.

**States:** Declared: hover border-color hsla(0, 0%, 79%, 1); focus-visible outline-color hsla(212, 100%, 48%, 1).

## Imagery and graphics

### Fading outline word sculpture

**Use:** Signature visual overture for the default marketing opening.

**Observed:** A huge hollow word in fine blue outlines occupies the space immediately above the centered black headline. Its lower strokes fade to the off-white ground; there is no photograph or filled logo slab. The vector is 793px wide by 191px high at desktop.

**Transfer:** Draw the new product name or a concise geometric initial construction at the same width relative to the copy. A custom outlined typographic SVG is the minimum acceptable version.

**Build:** Convert wide uppercase lettering to SVG paths with no fill and a fine approximately 1px blue stroke. Fit to a roughly 4.15:1 box. Overlay a vertical #fafafa gradient whose alpha rises from 0 at the top to 1 near the lower edge, softening the outline where it meets the title; exact fade stops are not essential.

### Technical construction diagrams

**Use:** The first illustrated capability row.

**Observed:** Pale line-art objects sit in 5:4 outlined frames: layered image sheets, a miniature browser on a construction grid, and connected circular nodes. Almost everything is white or gray, with tiny blue edge highlights. The illustration is larger than its short text caption below.

**Transfer:** Turn product capabilities into simple stacks, streams, nodes or window constructions rather than stock illustrations.

**Build:** Use SVG rectangles, circles and dotted connectors in #e6e6e6, with sparse #0057ff strokes at low alpha. Center the diagram in a 448px by 358px frame. For a browser scene, add a faint square grid behind a rounded window with skeleton blocks; for a graph, use six circles joined by short dashed lines. Keep fill close to #fafafa and do not add saturated illustration backgrounds.

### Grayscale interface collage

**Use:** Editorial social-proof composition.

**Observed:** Real customer websites appear as unequal large landscape and narrow portrait panels. Two smaller panels balance a large left heading above a lower wide–narrow–wide arrangement. All are grayscale by default, sharply legible and edged with #c9c9c9 and 8px corners.

**Transfer:** Use real customer outputs or representative product workflows. If customer assets are unavailable, construct two or three credible interface layouts in different aspect ratios rather than filling the space with logos.

### Color website previews

**Only for:** customer proof pages

**Use:** The catalog variant of interface proof.

**Observed:** Website thumbnails preserve their own original color, typography and imagery while the surrounding card and page stay neutral. Full previews, not browser chrome sculptures, are the focus.

**Transfer:** Let submitted work supply color; keep all category controls and framing monochrome.

### Circular portraits

**Only for:** people directories

**Use:** Human identity in long team grids.

**Observed:** Small grayscale circular headshots or personal avatar images are centered within spacious cells. Name, handle and small social icons stack below; fine vertical rules fade at the top and bottom of the directory.

**Transfer:** Use authentic portraits, grayscale consistently, and retain the large amount of surrounding space. Do not enlarge faces into full-bleed cards.

### Tactile resource books

**Only for:** learning catalogs

**Use:** Course opening and deeper-reading resource shelf.

**Observed:** The opening pairs a chapter list with a compact gray hardback book: dark spine, softly shaded cover, small black text and a circular mark. Further resources use shallow off-white book objects around 204px by 220px with subtly rounded left spines, page edges and restrained shadows.

**Transfer:** Package courses or long-form guides as a coherent family of small books. Keep their covers neutral and typographic rather than adding colorful cover art.

**Build:** Layer a dark narrow spine, a light-gray cover and a 6px pale page strip using CSS transforms or SVG. Use a diagonal light-to-gray cover gradient, thin inset vertical seams and a narrow side highlight. Add low-alpha black shadows below and along the spine, with a mild white inset highlight. Use asymmetric corners around 5.4px on the spine side and 1.8px on the fore edge; avoid glossy, thick 3D extrusion.

### Icons

**Observed:** Mostly small filled SVG silhouettes in neutral ink: 16px is the dominant size, with 12px external-link marks, 14px navigation symbols and occasional 32px capability marks. Right arrows follow headings; social icons sit under identity labels.

**Transfer:** Use simple filled or visually equivalent crisp monochrome symbols, not colorful icon tiles. Match optical weight at 16px and keep arrows inline with text.

## Section recipes

How recurring sections are built.

### First screen: Outline sculpture opening

**Observed:** A 64px sticky Navigation precedes a centered 694px-tall hero stage. The background is Canvas; behind and above the text sits the Fading outline word sculpture, roughly 55% of viewport width. Its lower edge meets the title. In front, the balanced two-line headline spans at most 648px, followed by a centered 18px support line after 24px. A Command capsule follows after 40px. The vector, title, support and action are all visible in the first 900px; the next section heading begins just below that boundary. The lower stage leaves breathing room rather than showing a dashboard peek.

**Transfer:** Use a concise product promise under a custom outline name or initial construction and one immediately useful setup action. For learning pages, switch to a left-aligned title and actions opposite a chapter list and book. For people directories, use a compact title-left, explanation-right opening. For customer proof pages, use a left-aligned promise, paired actions, short support and a monochrome logo row.

**Avoid:** Do not replace the outline sculpture with a filled giant black logo, a gradient headline or a full-bleed photograph. Do not add a floating dashboard across the lower half of this default opening.

**Text style:** `display` — GeistSans 450 · 64px/1 · tracking -0.06em

### Illustrated capability chapter

**Observed:** A heading up to 872px wide leads a three-column capability grid after 72px. Technical construction diagrams sit on Outlined panel frames above feature labels and descriptions; smaller unboxed capability groups continue with 96px row gaps. The Announcement card provides one concentrated blue interruption.

**Transfer:** Move from three visual explanations to terse supporting mechanisms; vary the number of items without losing the contrast between diagrams, text and one emphatic announcement.

**Text style:** `heading` — GeistSans 450 · 56px/1 · tracking -0.06em

### Foundation row

**Observed:** A large heading introduces three equal Foundation cards after 72px, with major section padding of 144px above and below.

**Transfer:** Use for supporting technology, principles, integrations or underlying services rather than inventing an extra heavy hierarchy.

### Editorial proof and quotations

**Observed:** A large left heading shares space with the Grayscale interface collage. A 24px narrative caption beneath mixes secondary text with a darker medium-weight phrase. A following two-column quotation section uses centered 32px/40px text, small monochrome customer marks above, and compact name-and-role attribution below with a 36px separation.

**Transfer:** Pair visible examples of output with specific accounts of outcomes. Keep quote panels unboxed on Canvas.

**Text style:** `quote` — GeistSans 400 · 32px/1.25 · tracking -0.04em

### Resource workbench

**Observed:** The resource split places a heading, 18px support and paired buttons in the left third. Folded document cards form two columns in the remaining width, spaced by 24px; the intro remains sticky alongside longer lists.

**Transfer:** Use for templates, recipes, integrations or ready-to-use projects. Keep each description short enough to leave the origin label visually separate.

**Text style:** `heading` — GeistSans 450 · 56px/1 · tracking -0.06em

### Compact closing and footer

**Observed:** A faint fading horizontal rule precedes a 96px-padded closing row: 56px question on the left, two 36px actions on the right. The footer stays on Canvas with 40px top inset, four compact link groups and a wider newsletter group. A small identity mark sits at the bottom left and a tiny theme selector at bottom right; substantial whitespace separates them from the link lists.

**Transfer:** Use the short closing row for a general marketing page. Directory pages may end directly with the shared footer; learning pages use a reference-resource row, and proof pages use a final benefit-led conversion section.

**Text style:** `heading` — GeistSans 450 · 56px/1 · tracking -0.06em

### People directory

**Only for:** people directories

**Observed:** A compact two-column introduction gives way to 48px group headings. Each group uses the directory grid, Circular portraits and centered label stacks. There are no enclosing individual card backgrounds; vertical rules and fading boundaries organize the long wall. The final group leads directly to the shared footer with no extra sales call.

**Transfer:** Preserve equal status and generous personal space across all people; grouping provides the hierarchy.

**Text style:** `directory-heading` — GeistSans 450 · 48px/56px · tracking -0.06em

### Learning ladder

**Only for:** learning catalogs

**Observed:** After the title/list/book opening, a large Browser stage demonstrates the intended finished product. Four compact progress benefits follow. A heading pair introduces numbered Outlined panel tiles in three columns; a centered secondary learning action follows. Two additional course cards lead to the Tactile resource books shelf and a final compact documentation row with a small object, title, support and right-aligned secondary button before the footer.

**Transfer:** Show the end result before the syllabus. Close with deeper resources and reference access, not a duplicate oversized hero.

**Text style:** `heading` — GeistSans 450 · 56px/1 · tracking -0.06em

### Customer proof catalog

**Only for:** customer proof pages

**Observed:** The left-aligned opening ends in a monochrome customer-logo row. A four-column metric band uses 64px figures with -0.02em tracking and 16px captions. A 56px catalog heading leads restrained category tabs, Website preview cards and centered load-more action. Resource workbench follows; the closing pitch has paired buttons and three icon-led short benefits before the shared footer.

**Transfer:** Alternate curated authority, quantification and browsable examples. Preserve full color inside the preview images only.

**Text style:** `stat` — GeistSans 450 · 64px/1 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible explanation → credible foundations → examples and outcomes → practical starting points → concise next step and shared utility footer.

### General product landing page

1. **Promise** — Centered outline artwork, balanced headline, support and command action.
2. **Capability explanation** — Large diagrams lead short feature groups and a blue announcement.
3. **Foundation proof** — Three outlined cards explain supporting building blocks.
4. **Social proof** — Grayscale output collage, narrative caption and two unboxed quotations.
5. **Activation** — Sticky introduction beside folded-document resources.
6. **Closing call** — Short question with compact paired actions, then multi-column footer and newsletter.

**Transfer:** Use the default neutral installation-like opening and alternate explanation with artifacts and evidence; adapt chapter order to the product narrative.

### People and organization directory

1. **Context** — Left title and right explanation in a compact opening.
2. **Human proof** — Group headings over equal-sized grayscale portrait cells, names and social links.
3. **Continuation** — Additional group repeats the same treatment.
4. **Utility ending** — Shared newsletter footer without an additional promotional section.

**Transfer:** Group people by meaningful responsibility while keeping every profile visually equal.

### Learning and onboarding catalog

1. **Invitation** — Left promise and actions opposite a chapter list and physical-book metaphor.
2. **Product demonstration** — Wide browser-framed finished application and four progress benefits.
3. **Curriculum** — Indexed three-column tiles and a centered continuation action.
4. **Related paths** — Two compact additional courses.
5. **Deeper resources** — Neutral book shelf and a compact reference-documentation call.
6. **Utility ending** — Shared link and newsletter footer.

**Transfer:** Sell the achievable outcome, then expose an orderly path and end with ways to continue learning.

### Customer work and enterprise proof

1. **Promise** — Left headline, paired actions, supporting paragraph and monochrome customer marks.
2. **Quantified proof** — Four large figures with concise captions.
3. **Browsable proof** — Category navigation and four-column full-color website previews.
4. **Activation** — Folded-document resources paired with a sticky introduction.
5. **Closing reassurance** — Short pitch with paired actions and three icon-led benefits.
6. **Utility ending** — Shared link and newsletter footer.

**Transfer:** Balance enterprise authority with an actual browsable body of work; derive proof from the new product's own customers and metrics.

## Writing

Direct, developer-literate and quietly assured. Confidence comes from concrete mechanisms, useful outputs and named outcomes rather than grandiose adjectives.

**Do not copy:** Do not reuse the Next.js or Vercel identity, product-specific commands, customer marks, names, testimonials, version announcements, rankings or performance claims. Replace all source assets and facts with the new product's own. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for practical benefits and setup guidance. Refer to the product by name for factual statements; use we sparingly.
- **Rhythm:** Short sentence-case headlines, often four to ten words, followed by one or two concise explanatory sentences. Actions are brief verb phrases. Feature descriptions are denser and more technical than hero support.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the product category and its purpose, or invite a concrete action. | 4–10 words | “The React Framework for the Web”<br>“Start building with [Brand]” |
| Section heading | Tie a grouping of capabilities to a useful outcome. | 4–12 words | “Everything you need to build great products on the web”<br>“Get started in seconds” |
| Supporting line | Explain how the promise becomes useful with specific nouns. | One or two sentences | “Learn [Brand] by building a full web application, step by step.” |
| Feature description | Describe the mechanism and its benefit without a slogan. | 12–30 words | “Automatic Image, Font, and Script Optimizations for improved UX and Core Web Vitals.” |
| Primary action | Verb plus the immediate next destination or task. | 2–4 words | “Deploy Now”<br>“Start Learning” |
| Closing question | A short readiness question that naturally introduces action. | 3–5 words | “Ready to deploy?” |

**Words and phrasing to use:** build; ship; get started; production-grade; step by step; foundations; performance; components; templates

**Avoid:** revolutionary; game-changing; unleash limitless potential; magic; !!!

**Rules:**

- Keep feature labels concrete and sentence case, with an inline arrow when the whole item links somewhere.
- Use technical terms when they explain how the product works, not as ornamental jargon.
- Let customer quotes sound like people; keep editorial marketing prose more concise.
- Place action labels close to the outcome they initiate.

## Do's and Don'ts

### Do

- Set the main title at 64px/1, weight 450, with -0.06em tracking.
- Use 56px/1 section headings and leave 72px before a major illustrated grid.
- Keep ordinary information cards at 2px radius with a 1px #e6e6e6 perimeter.
- Maintain 24px page margins and main gutters in the wide desktop composition.
- Reserve blue for the outline sculpture, primary pills, fine diagram highlights and concentrated announcements.
- Pair 16px/24px feature descriptions with 18px/28px introductory support.
- Carry the folded-corner document motif into practical resource cards.
- Keep the footer light, compact in typography and generous in trailing whitespace.

### Don't

- Do not make all headings weight 700; the display relies on weight 450 and tight fitting.
- Do not turn card grids into floating 16px-radius panels with broad shadows.
- Do not color every feature icon or give every capability a different pastel background.
- Do not default to a black footer or dark closing billboard; the page ground remains #fafafa.
- Do not use 24px captions as the default body scale; ordinary feature copy is 16px/24px.
- Do not apply the proof catalog's colorful thumbnails to the editorial grayscale collage.
- Do not stretch terminal monospace across the whole page; it belongs to commands.
- Do not add uppercase overlines to every section; headings usually stand on their own.

## Motion and responsive

### Motion

**Observed:**

- Declared control transitions commonly use 0.15s cubic-bezier(.4, 0, .2, 1); navigation links use 0.1s.
- Customer collage images transition filter over 0.2s and remove grayscale on group hover; reduced-motion styling disables that transition.
- Announcement arrow translates horizontally on interaction; its color inversion transition uses 0.2s.
- Resource books declare transform transitions of 0.6s.

**Transfer:**

- Preserve the grayscale-to-color reveal specifically for the editorial proof collage.
- Use restrained color and border changes rather than card bouncing; keep outline artwork visually calm.

**Unknown:**

- The timing and execution of opening and scroll-driven animation are not established.
- No exact interactive book rotation angle is established.

### Responsive

**Observed:**

- Styles declare width breakpoints including 640px, 768px, 1024px and 1280px.
- Heading classes include smaller 40px primary titles and 32px section headings before their desktop variants.
- People grids declare one, then two, then three columns; curriculum tiles also declare one, two and three columns.

**Transfer:**

- On narrow layouts, stack the resource intro over document cards and reduce the grid rather than shrinking labels.
- Keep the outline sculpture centered over the title and sized to the available width.
- Preserve a readable command capsule within the page margins; stack paired actions if necessary.
- Let the learning book shelf scroll horizontally rather than flattening its physical objects.

**Unknown:**

- Exact breakpoint-to-component mapping and mobile first-screen compositions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
